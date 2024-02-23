Linux in India - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in India.

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

Total: 5215

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Thin GF63 12HW              | [b5b16477c3](https://linux-hardware.org/?probe=b5b16477c3) | Feb 02, 2024 |
| Dell          | Latitude 5420               | [9ca4bb32d7](https://linux-hardware.org/?probe=9ca4bb32d7) | Feb 01, 2024 |
| Dell          | Inspiron N5010              | [151239b938](https://linux-hardware.org/?probe=151239b938) | Feb 01, 2024 |
| Dell          | Inspiron 7501               | [5c071c25ab](https://linux-hardware.org/?probe=5c071c25ab) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480 20L50011US    | [bb6dd71048](https://linux-hardware.org/?probe=bb6dd71048) | Feb 01, 2024 |
| Dell          | Inspiron 16 Plus 7630       | [af2db531a1](https://linux-hardware.org/?probe=af2db531a1) | Jan 31, 2024 |
| Lenovo        | IdeaPad Y560                | [e9a51b1fa8](https://linux-hardware.org/?probe=e9a51b1fa8) | Jan 31, 2024 |
| Infinix       | INBOOK X1 NEO               | [aca7de6cf8](https://linux-hardware.org/?probe=aca7de6cf8) | Jan 31, 2024 |
| Lenovo        | V14-ADA 82C6                | [916a39975c](https://linux-hardware.org/?probe=916a39975c) | Jan 31, 2024 |
| MSI           | Bravo 15 B5DD               | [a989f7aa10](https://linux-hardware.org/?probe=a989f7aa10) | Jan 30, 2024 |
| Lenovo        | IdeaPad Y560                | [a32d1d3fa7](https://linux-hardware.org/?probe=a32d1d3fa7) | Jan 30, 2024 |
| MSI           | Thin GF63 12HW              | [5c79e92eb3](https://linux-hardware.org/?probe=5c79e92eb3) | Jan 30, 2024 |
| MSI           | GL63 9SD                    | [174a4f49ac](https://linux-hardware.org/?probe=174a4f49ac) | Jan 29, 2024 |
| Timi          | Xiaomi NoteBook Pro         | [2e4fa19ae6](https://linux-hardware.org/?probe=2e4fa19ae6) | Jan 29, 2024 |
| Dell          | Latitude E6410              | [1d71a03516](https://linux-hardware.org/?probe=1d71a03516) | Jan 29, 2024 |
| Dell          | Vostro 3558                 | [f2c958ad91](https://linux-hardware.org/?probe=f2c958ad91) | Jan 29, 2024 |
| HP            | EliteBook 840 g5            | [b9ca87e1e4](https://linux-hardware.org/?probe=b9ca87e1e4) | Jan 28, 2024 |
| Lenovo        | ThinkPad T480 20L6S4T80H    | [cb5f6705aa](https://linux-hardware.org/?probe=cb5f6705aa) | Jan 28, 2024 |
| Dell          | Inspiron 3537               | [e91c3bfd73](https://linux-hardware.org/?probe=e91c3bfd73) | Jan 28, 2024 |
| Dell          | Inspiron 3537               | [0ee7687e3f](https://linux-hardware.org/?probe=0ee7687e3f) | Jan 28, 2024 |
| Acer          | Aspire A715-51G             | [e6b8ceb566](https://linux-hardware.org/?probe=e6b8ceb566) | Jan 27, 2024 |
| Lenovo        | ThinkPad E14 20RAS1S600     | [8544584b30](https://linux-hardware.org/?probe=8544584b30) | Jan 27, 2024 |
| Dell          | Inspiron 3542               | [2a81d5f313](https://linux-hardware.org/?probe=2a81d5f313) | Jan 27, 2024 |
| Acer          | Aspire A715-51G             | [fad23c2b03](https://linux-hardware.org/?probe=fad23c2b03) | Jan 27, 2024 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [a354ee36fe](https://linux-hardware.org/?probe=a354ee36fe) | Jan 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3932a6e2cf](https://linux-hardware.org/?probe=3932a6e2cf) | Jan 26, 2024 |
| Fujitsu       | LIFEBOOK A555               | [4d1f942627](https://linux-hardware.org/?probe=4d1f942627) | Jan 25, 2024 |
| HP            | EliteBook 8470p             | [b892b5b8a4](https://linux-hardware.org/?probe=b892b5b8a4) | Jan 25, 2024 |
| Dell          | Inspiron 3501               | [2b4a8624c9](https://linux-hardware.org/?probe=2b4a8624c9) | Jan 24, 2024 |
| Acer          | Nitro AN515-45              | [decd7eb6dc](https://linux-hardware.org/?probe=decd7eb6dc) | Jan 24, 2024 |
| Acer          | Aspire A315-55G             | [c04d6bddfb](https://linux-hardware.org/?probe=c04d6bddfb) | Jan 24, 2024 |
| LG Electro... | 14Z990-V.AR52A2             | [346844d302](https://linux-hardware.org/?probe=346844d302) | Jan 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [59eb577232](https://linux-hardware.org/?probe=59eb577232) | Jan 23, 2024 |
| HP            | Laptop 15s-fq5xxx           | [c2d6eded11](https://linux-hardware.org/?probe=c2d6eded11) | Jan 23, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [5d754d0510](https://linux-hardware.org/?probe=5d754d0510) | Jan 23, 2024 |
| Apple         | MacBookPro8,1               | [ba1a3bef35](https://linux-hardware.org/?probe=ba1a3bef35) | Jan 21, 2024 |
| HP            | Pavilion g6                 | [58e29cfd8a](https://linux-hardware.org/?probe=58e29cfd8a) | Jan 21, 2024 |
| HP            | Laptop 15s-gr0xxx           | [320f2c215a](https://linux-hardware.org/?probe=320f2c215a) | Jan 21, 2024 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [ddb59f8c7e](https://linux-hardware.org/?probe=ddb59f8c7e) | Jan 21, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [833af537d7](https://linux-hardware.org/?probe=833af537d7) | Jan 21, 2024 |
| Dell          | Inspiron 14 5410            | [018d9742c7](https://linux-hardware.org/?probe=018d9742c7) | Jan 21, 2024 |
| HP            | Notebook                    | [71136f647b](https://linux-hardware.org/?probe=71136f647b) | Jan 20, 2024 |
| Dell          | Inspiron 15 3511            | [d79a7275ed](https://linux-hardware.org/?probe=d79a7275ed) | Jan 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [5797795e83](https://linux-hardware.org/?probe=5797795e83) | Jan 20, 2024 |
| Infinix       | ZERO BOOK 13                | [5f3718642b](https://linux-hardware.org/?probe=5f3718642b) | Jan 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [9fd92c9632](https://linux-hardware.org/?probe=9fd92c9632) | Jan 20, 2024 |
| HONOR         | BMH-WCX9                    | [45113bdfbb](https://linux-hardware.org/?probe=45113bdfbb) | Jan 19, 2024 |
| Dell          | Inspiron 3501               | [dcd7920f8c](https://linux-hardware.org/?probe=dcd7920f8c) | Jan 19, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [bf4f40eec4](https://linux-hardware.org/?probe=bf4f40eec4) | Jan 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [fb993819da](https://linux-hardware.org/?probe=fb993819da) | Jan 18, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [459fc53c83](https://linux-hardware.org/?probe=459fc53c83) | Jan 18, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 Ua 82F... | [741f29036a](https://linux-hardware.org/?probe=741f29036a) | Jan 17, 2024 |
| Lenovo        | ThinkPad X230 2330A17       | [589c4362a6](https://linux-hardware.org/?probe=589c4362a6) | Jan 16, 2024 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [78896edb96](https://linux-hardware.org/?probe=78896edb96) | Jan 16, 2024 |
| Infinix       | INBook X1 Pro               | [8fd49f9543](https://linux-hardware.org/?probe=8fd49f9543) | Jan 16, 2024 |
| Infinix       | INBOOK X1 NEO               | [ff730c7320](https://linux-hardware.org/?probe=ff730c7320) | Jan 16, 2024 |
| HP            | 15                          | [c84c138cef](https://linux-hardware.org/?probe=c84c138cef) | Jan 16, 2024 |
| Dell          | Latitude E5520              | [9700d44fe1](https://linux-hardware.org/?probe=9700d44fe1) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [d124634554](https://linux-hardware.org/?probe=d124634554) | Jan 15, 2024 |
| Dell          | Inspiron 3501               | [fecc6a63eb](https://linux-hardware.org/?probe=fecc6a63eb) | Jan 15, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [51693df272](https://linux-hardware.org/?probe=51693df272) | Jan 15, 2024 |
| HP            | 15                          | [c247a8a3fb](https://linux-hardware.org/?probe=c247a8a3fb) | Jan 14, 2024 |
| Timi          | Mi NoteBook Ultra           | [a14c93df78](https://linux-hardware.org/?probe=a14c93df78) | Jan 14, 2024 |
| Dell          | Latitude E6420              | [78cffcaf30](https://linux-hardware.org/?probe=78cffcaf30) | Jan 14, 2024 |
| Lenovo        | ThinkPad L380 20M6S1MG0X    | [74d87d7f6f](https://linux-hardware.org/?probe=74d87d7f6f) | Jan 14, 2024 |
| Lenovo        | ThinkPad L380 20M6S1MG0X    | [9551a51d17](https://linux-hardware.org/?probe=9551a51d17) | Jan 13, 2024 |
| MSI           | GL63 8RC                    | [2e52a98d20](https://linux-hardware.org/?probe=2e52a98d20) | Jan 13, 2024 |
| Dell          | Vostro 3500                 | [a6d51704d8](https://linux-hardware.org/?probe=a6d51704d8) | Jan 13, 2024 |
| Samsung       | RV408/RV508                 | [05836028b1](https://linux-hardware.org/?probe=05836028b1) | Jan 13, 2024 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [a74400cdb0](https://linux-hardware.org/?probe=a74400cdb0) | Jan 12, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [c9788a2dac](https://linux-hardware.org/?probe=c9788a2dac) | Jan 12, 2024 |
| HP            | Laptop 15-bs0xx             | [ddfda4248f](https://linux-hardware.org/?probe=ddfda4248f) | Jan 12, 2024 |
| HP            | 348 G5                      | [a7c6a60aaf](https://linux-hardware.org/?probe=a7c6a60aaf) | Jan 12, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8e72c34b9e](https://linux-hardware.org/?probe=8e72c34b9e) | Jan 11, 2024 |
| HP            | Notebook                    | [53e2f16b51](https://linux-hardware.org/?probe=53e2f16b51) | Jan 11, 2024 |
| HP            | Pavilion Laptop 14-dv0xx... | [cbce15965a](https://linux-hardware.org/?probe=cbce15965a) | Jan 11, 2024 |
| Dell          | Latitude 5511               | [a445a8c583](https://linux-hardware.org/?probe=a445a8c583) | Jan 11, 2024 |
| HP            | Victus by Gaming Laptop ... | [6394ca334a](https://linux-hardware.org/?probe=6394ca334a) | Jan 10, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [54f475b387](https://linux-hardware.org/?probe=54f475b387) | Jan 10, 2024 |
| Infinix       | ZERO BOOK 13                | [7101d9332b](https://linux-hardware.org/?probe=7101d9332b) | Jan 10, 2024 |
| Infinix       | ZERO BOOK 13                | [a3c73eb2fd](https://linux-hardware.org/?probe=a3c73eb2fd) | Jan 09, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1abf742848](https://linux-hardware.org/?probe=1abf742848) | Jan 09, 2024 |
| Dell          | Inspiron 3542               | [ce95868b75](https://linux-hardware.org/?probe=ce95868b75) | Jan 09, 2024 |
| Infinix       | INBOOK X3 Slim              | [a62bc72974](https://linux-hardware.org/?probe=a62bc72974) | Jan 09, 2024 |
| HP            | Laptop 14s-dy5xxx           | [f64c72ed00](https://linux-hardware.org/?probe=f64c72ed00) | Jan 09, 2024 |
| HP            | ENVY TS 14 Sleekbook        | [48871db703](https://linux-hardware.org/?probe=48871db703) | Jan 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81d7f1e405](https://linux-hardware.org/?probe=81d7f1e405) | Jan 08, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1673e31468](https://linux-hardware.org/?probe=1673e31468) | Jan 08, 2024 |
| Dell          | Latitude E6410              | [1260fc62f4](https://linux-hardware.org/?probe=1260fc62f4) | Jan 08, 2024 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [fff38da117](https://linux-hardware.org/?probe=fff38da117) | Jan 08, 2024 |
| Dell          | Latitude 5421               | [11ff1eb9a9](https://linux-hardware.org/?probe=11ff1eb9a9) | Jan 08, 2024 |
| Dell          | Vostro 5402                 | [4c1d546ae0](https://linux-hardware.org/?probe=4c1d546ae0) | Jan 08, 2024 |
| HP            | EliteBook 840 G3            | [a8bd0e8c75](https://linux-hardware.org/?probe=a8bd0e8c75) | Jan 08, 2024 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [132e89ac42](https://linux-hardware.org/?probe=132e89ac42) | Jan 08, 2024 |
| HP            | EliteBook Revolve 810 G1    | [c428c1eb3e](https://linux-hardware.org/?probe=c428c1eb3e) | Jan 08, 2024 |
| Lenovo        | IdeaPad 330S-15IKB D 81F... | [2068373a62](https://linux-hardware.org/?probe=2068373a62) | Jan 08, 2024 |
| Infinix       | INBOOK X3 Slim              | [8abae45d8f](https://linux-hardware.org/?probe=8abae45d8f) | Jan 07, 2024 |
| HP            | EliteBook 840 G3            | [d640505d97](https://linux-hardware.org/?probe=d640505d97) | Jan 07, 2024 |
| MSI           | Thin GF63 12HW              | [3b5cc98847](https://linux-hardware.org/?probe=3b5cc98847) | Jan 06, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [d922e42e7e](https://linux-hardware.org/?probe=d922e42e7e) | Jan 06, 2024 |
| Lenovo        | ThinkPad X390 20Q1S7RB00    | [cfcb27d0b7](https://linux-hardware.org/?probe=cfcb27d0b7) | Jan 06, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [7c5e33071f](https://linux-hardware.org/?probe=7c5e33071f) | Jan 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [9ccd4b5019](https://linux-hardware.org/?probe=9ccd4b5019) | Jan 04, 2024 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [cafe81526a](https://linux-hardware.org/?probe=cafe81526a) | Jan 04, 2024 |
| HP            | EliteBook 840 G3            | [840b965b43](https://linux-hardware.org/?probe=840b965b43) | Jan 04, 2024 |
| HP            | EliteBook 840 G1            | [1f5691daf4](https://linux-hardware.org/?probe=1f5691daf4) | Jan 02, 2024 |
| Acer          | Nitro AN515-47              | [b53ce5dfb5](https://linux-hardware.org/?probe=b53ce5dfb5) | Jan 02, 2024 |
| HP            | Laptop 14s-dy5xxx           | [4c531fb260](https://linux-hardware.org/?probe=4c531fb260) | Jan 02, 2024 |
| ASUSTek       | K53SV                       | [0cc0c3f5e0](https://linux-hardware.org/?probe=0cc0c3f5e0) | Jan 02, 2024 |
| Google        | Blooguard                   | [dc6c0354a9](https://linux-hardware.org/?probe=dc6c0354a9) | Jan 02, 2024 |
| Acer          | One 14 Z8-415               | [b022baea77](https://linux-hardware.org/?probe=b022baea77) | Jan 01, 2024 |
| Acer          | One 14 Z8-415               | [0e2bbf3d20](https://linux-hardware.org/?probe=0e2bbf3d20) | Jan 01, 2024 |
| Dell          | Vostro 3405                 | [78db308528](https://linux-hardware.org/?probe=78db308528) | Jan 01, 2024 |
| Dell          | XPS 15 9530                 | [22ba5950e3](https://linux-hardware.org/?probe=22ba5950e3) | Jan 01, 2024 |
| Dell          | XPS 15 9530                 | [dddd9b59bf](https://linux-hardware.org/?probe=dddd9b59bf) | Jan 01, 2024 |
| HP            | Laptop 14s-ef1xxx           | [961d2db618](https://linux-hardware.org/?probe=961d2db618) | Dec 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | [f96a0610cb](https://linux-hardware.org/?probe=f96a0610cb) | Dec 30, 2023 |
| Infinix       | INBOOK X1 NEO               | [71e74b3e03](https://linux-hardware.org/?probe=71e74b3e03) | Dec 30, 2023 |
| Dell          | Latitude E5420              | [0bc1fb2eaf](https://linux-hardware.org/?probe=0bc1fb2eaf) | Dec 30, 2023 |
| HP            | ProBook 440 G7              | [10d9fd3230](https://linux-hardware.org/?probe=10d9fd3230) | Dec 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2490d5b834](https://linux-hardware.org/?probe=2490d5b834) | Dec 30, 2023 |
| Dell          | Vostro 3405                 | [e527034e74](https://linux-hardware.org/?probe=e527034e74) | Dec 29, 2023 |
| Dell          | Vostro 3405                 | [aee31d728f](https://linux-hardware.org/?probe=aee31d728f) | Dec 29, 2023 |
| Acer          | Aspire A715-76G             | [e25984fb5e](https://linux-hardware.org/?probe=e25984fb5e) | Dec 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [42c812d36d](https://linux-hardware.org/?probe=42c812d36d) | Dec 29, 2023 |
| Dell          | Precision M6400             | [7ea3fcf3ed](https://linux-hardware.org/?probe=7ea3fcf3ed) | Dec 29, 2023 |
| Lenovo        | V145-15AST 81MT             | [493e09fce5](https://linux-hardware.org/?probe=493e09fce5) | Dec 28, 2023 |
| HP            | EliteBook 840 G4            | [412a23e374](https://linux-hardware.org/?probe=412a23e374) | Dec 28, 2023 |
| HP            | EliteBook 840 G3            | [ce26af0483](https://linux-hardware.org/?probe=ce26af0483) | Dec 28, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [6abb72e809](https://linux-hardware.org/?probe=6abb72e809) | Dec 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E1T    | [1948c445d8](https://linux-hardware.org/?probe=1948c445d8) | Dec 27, 2023 |
| HP            | EliteBook Revolve 810 G1    | [30d2bb71e5](https://linux-hardware.org/?probe=30d2bb71e5) | Dec 27, 2023 |
| Dell          | Vostro 3446                 | [ed9d04a3d2](https://linux-hardware.org/?probe=ed9d04a3d2) | Dec 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | [cce90b21c6](https://linux-hardware.org/?probe=cce90b21c6) | Dec 27, 2023 |
| HP            | Laptop 14s-dy5xxx           | [de602b4dc6](https://linux-hardware.org/?probe=de602b4dc6) | Dec 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8fae3225fd](https://linux-hardware.org/?probe=8fae3225fd) | Dec 26, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [c436ff8cab](https://linux-hardware.org/?probe=c436ff8cab) | Dec 26, 2023 |
| Lenovo        | ThinkPad L470 20J5S0JM00    | [c8f1140dc5](https://linux-hardware.org/?probe=c8f1140dc5) | Dec 26, 2023 |
| Timi          | Mi NoteBook Pro             | [5972225791](https://linux-hardware.org/?probe=5972225791) | Dec 25, 2023 |
| Dell          | Latitude 3520               | [2bac03be10](https://linux-hardware.org/?probe=2bac03be10) | Dec 24, 2023 |
| HP            | Victus by 15.6 inch Gami... | [b74170ede4](https://linux-hardware.org/?probe=b74170ede4) | Dec 23, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [d36af9d69e](https://linux-hardware.org/?probe=d36af9d69e) | Dec 22, 2023 |
| HP            | Laptop 15-bs0xx             | [e42f9ff8f6](https://linux-hardware.org/?probe=e42f9ff8f6) | Dec 22, 2023 |
| Acer          | Nitro AN515-58              | [c7a31a4dab](https://linux-hardware.org/?probe=c7a31a4dab) | Dec 22, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [18788fe1ea](https://linux-hardware.org/?probe=18788fe1ea) | Dec 22, 2023 |
| Dell          | Inspiron 15 3515            | [cdff1cf322](https://linux-hardware.org/?probe=cdff1cf322) | Dec 22, 2023 |
| Acer          | One 14 Z2-493               | [11215309a3](https://linux-hardware.org/?probe=11215309a3) | Dec 22, 2023 |
| HP            | Notebook                    | [9010ced489](https://linux-hardware.org/?probe=9010ced489) | Dec 21, 2023 |
| Dell          | Latitude 3410               | [3de48ebce1](https://linux-hardware.org/?probe=3de48ebce1) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | [870842c348](https://linux-hardware.org/?probe=870842c348) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c2eacfced7](https://linux-hardware.org/?probe=c2eacfced7) | Dec 20, 2023 |
| Dell          | Inspiron 15 3520            | [dac9572e21](https://linux-hardware.org/?probe=dac9572e21) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | [71bc732b86](https://linux-hardware.org/?probe=71bc732b86) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | [5d14b45611](https://linux-hardware.org/?probe=5d14b45611) | Dec 20, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | [71d03541a9](https://linux-hardware.org/?probe=71d03541a9) | Dec 20, 2023 |
| MSI           | Thin GF63 12HW              | [28287138f4](https://linux-hardware.org/?probe=28287138f4) | Dec 19, 2023 |
| Acer          | Swift SF314-71              | [5a5f20e49a](https://linux-hardware.org/?probe=5a5f20e49a) | Dec 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7d1b99f3a7](https://linux-hardware.org/?probe=7d1b99f3a7) | Dec 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [19fe61d807](https://linux-hardware.org/?probe=19fe61d807) | Dec 18, 2023 |
| Dell          | Vostro 3580                 | [90856c67e3](https://linux-hardware.org/?probe=90856c67e3) | Dec 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [16902836db](https://linux-hardware.org/?probe=16902836db) | Dec 17, 2023 |
| HP            | 2000                        | [3570eb7cd0](https://linux-hardware.org/?probe=3570eb7cd0) | Dec 17, 2023 |
| HP            | 15                          | [b1de66d4ed](https://linux-hardware.org/?probe=b1de66d4ed) | Dec 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9986fed725](https://linux-hardware.org/?probe=9986fed725) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [4a964fa296](https://linux-hardware.org/?probe=4a964fa296) | Dec 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [6689e06c77](https://linux-hardware.org/?probe=6689e06c77) | Dec 15, 2023 |
| realme        | RMNBXXXX                    | [c5e74761c7](https://linux-hardware.org/?probe=c5e74761c7) | Dec 15, 2023 |
| HP            | Laptop 15s-fq2xxx           | [0728e617a0](https://linux-hardware.org/?probe=0728e617a0) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S0U302    | [163493b62b](https://linux-hardware.org/?probe=163493b62b) | Dec 14, 2023 |
| HP            | ProBook 450 G1              | [f6f31f5ed6](https://linux-hardware.org/?probe=f6f31f5ed6) | Dec 13, 2023 |
| HP            | Pavilion g6                 | [f79863b604](https://linux-hardware.org/?probe=f79863b604) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | [4b88dcf6b3](https://linux-hardware.org/?probe=4b88dcf6b3) | Dec 13, 2023 |
| Lenovo        | G50-45 80E3                 | [1a63f79d28](https://linux-hardware.org/?probe=1a63f79d28) | Dec 13, 2023 |
| HP            | Pavilion dv6-1152tx (VB6... | [f8a2cfad5f](https://linux-hardware.org/?probe=f8a2cfad5f) | Dec 13, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [9c38707d13](https://linux-hardware.org/?probe=9c38707d13) | Dec 13, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [f837c928be](https://linux-hardware.org/?probe=f837c928be) | Dec 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [293fe3fb8e](https://linux-hardware.org/?probe=293fe3fb8e) | Dec 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [c9dd6aebbd](https://linux-hardware.org/?probe=c9dd6aebbd) | Dec 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [e5415e7df5](https://linux-hardware.org/?probe=e5415e7df5) | Dec 12, 2023 |
| Sony          | VPCEH25EN                   | [284401858f](https://linux-hardware.org/?probe=284401858f) | Dec 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bc96bd94d2](https://linux-hardware.org/?probe=bc96bd94d2) | Dec 11, 2023 |
| Dell          | Inspiron 3521               | [e96af5da4d](https://linux-hardware.org/?probe=e96af5da4d) | Dec 11, 2023 |
| HP            | Laptop 14s-dy5xxx           | [bfe021294b](https://linux-hardware.org/?probe=bfe021294b) | Dec 11, 2023 |
| Acer          | Nitro AN515-47              | [bfd1a093c9](https://linux-hardware.org/?probe=bfd1a093c9) | Dec 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9ae1729415](https://linux-hardware.org/?probe=9ae1729415) | Dec 10, 2023 |
| HP            | Laptop 15-da0xxx            | [a086fa3ad5](https://linux-hardware.org/?probe=a086fa3ad5) | Dec 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f0bcb0009e](https://linux-hardware.org/?probe=f0bcb0009e) | Dec 09, 2023 |
| Acer          | Aspire E1-531               | [7082f03269](https://linux-hardware.org/?probe=7082f03269) | Dec 08, 2023 |
| ASUSTek       | ROG Strix G533ZW_G533ZW     | [a696c1d832](https://linux-hardware.org/?probe=a696c1d832) | Dec 08, 2023 |
| Infinix       | INBOOK X3 Slim              | [124c166e5f](https://linux-hardware.org/?probe=124c166e5f) | Dec 08, 2023 |
| HP            | Pavilion Laptop 14-dv2xx... | [71cc90f71e](https://linux-hardware.org/?probe=71cc90f71e) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ed77f35114](https://linux-hardware.org/?probe=ed77f35114) | Dec 06, 2023 |
| Dell          | Vostro 3580                 | [896cdac0e2](https://linux-hardware.org/?probe=896cdac0e2) | Dec 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [0c0833952d](https://linux-hardware.org/?probe=0c0833952d) | Dec 06, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [aa183c25d7](https://linux-hardware.org/?probe=aa183c25d7) | Dec 06, 2023 |
| Dell          | Inspiron 3593               | [3a07569e5f](https://linux-hardware.org/?probe=3a07569e5f) | Dec 05, 2023 |
| Dell          | Inspiron 3583               | [84dc9cc524](https://linux-hardware.org/?probe=84dc9cc524) | Dec 05, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [8fbe891429](https://linux-hardware.org/?probe=8fbe891429) | Dec 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [3306bdcb6c](https://linux-hardware.org/?probe=3306bdcb6c) | Dec 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9535cecf0f](https://linux-hardware.org/?probe=9535cecf0f) | Dec 05, 2023 |
| HP            | Pavilion 15                 | [15b5925773](https://linux-hardware.org/?probe=15b5925773) | Dec 04, 2023 |
| Dell          | Inspiron 3558               | [29d253c1cd](https://linux-hardware.org/?probe=29d253c1cd) | Dec 04, 2023 |
| Lenovo        | E41-25 81FS                 | [d088539ba0](https://linux-hardware.org/?probe=d088539ba0) | Dec 04, 2023 |
| Acer          | Unknown                     | [6555dd06ac](https://linux-hardware.org/?probe=6555dd06ac) | Dec 03, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [a12d533400](https://linux-hardware.org/?probe=a12d533400) | Dec 03, 2023 |
| MSI           | Thin GF63 12HW              | [0612c99f8a](https://linux-hardware.org/?probe=0612c99f8a) | Dec 03, 2023 |
| MSI           | Modern 14 B4MW              | [69c3f996db](https://linux-hardware.org/?probe=69c3f996db) | Dec 02, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6c9bc77547](https://linux-hardware.org/?probe=6c9bc77547) | Dec 02, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [26d7ac2396](https://linux-hardware.org/?probe=26d7ac2396) | Dec 02, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [e33632af4f](https://linux-hardware.org/?probe=e33632af4f) | Dec 02, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [f86dd8a709](https://linux-hardware.org/?probe=f86dd8a709) | Dec 02, 2023 |
| Dell          | Inspiron 3558               | [6b97c68c9f](https://linux-hardware.org/?probe=6b97c68c9f) | Dec 01, 2023 |
| Dell          | Latitude 5480               | [dca8ec821b](https://linux-hardware.org/?probe=dca8ec821b) | Dec 01, 2023 |
| Lenovo        | K14 G2 IRU 21G1             | [b52ce46b0d](https://linux-hardware.org/?probe=b52ce46b0d) | Dec 01, 2023 |
| Lenovo        | K14 G2 IRU 21G1             | [22af506155](https://linux-hardware.org/?probe=22af506155) | Dec 01, 2023 |
| Dell          | Inspiron 3521               | [3e97ecc95d](https://linux-hardware.org/?probe=3e97ecc95d) | Nov 30, 2023 |
| Dell          | Inspiron 1525               | [7c8b100c86](https://linux-hardware.org/?probe=7c8b100c86) | Nov 30, 2023 |
| HP            | ProBook 440 G7              | [bb8295e3fa](https://linux-hardware.org/?probe=bb8295e3fa) | Nov 30, 2023 |
| HP            | ProBook 440 G7              | [0d3ea0a6dc](https://linux-hardware.org/?probe=0d3ea0a6dc) | Nov 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [62b38954c4](https://linux-hardware.org/?probe=62b38954c4) | Nov 30, 2023 |
| HP            | EliteBook 840 G1            | [da1096c1ed](https://linux-hardware.org/?probe=da1096c1ed) | Nov 29, 2023 |
| HP            | Victus by Gaming Laptop ... | [2f5a407d09](https://linux-hardware.org/?probe=2f5a407d09) | Nov 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 Ub 82KU    | [f99e3c8556](https://linux-hardware.org/?probe=f99e3c8556) | Nov 28, 2023 |
| HP            | ProBook 440 G2              | [608d264af2](https://linux-hardware.org/?probe=608d264af2) | Nov 27, 2023 |
| HP            | ProBook 440 G2              | [2ecc0c852a](https://linux-hardware.org/?probe=2ecc0c852a) | Nov 27, 2023 |
| HP            | Laptop 15s-fq5xxx           | [7d4c7e1af2](https://linux-hardware.org/?probe=7d4c7e1af2) | Nov 27, 2023 |
| HP            | Laptop 15-hr0xxx            | [a2bef1066d](https://linux-hardware.org/?probe=a2bef1066d) | Nov 27, 2023 |
| Lenovo        | G510 20238                  | [3f9a7e29e7](https://linux-hardware.org/?probe=3f9a7e29e7) | Nov 26, 2023 |
| Acer          | Aspire Lite AL15-41         | [1ab369fc06](https://linux-hardware.org/?probe=1ab369fc06) | Nov 26, 2023 |
| MSI           | Thin GF63 12HW              | [82a4c6642b](https://linux-hardware.org/?probe=82a4c6642b) | Nov 25, 2023 |
| Dell          | Precision M4500             | [c1833bf6b5](https://linux-hardware.org/?probe=c1833bf6b5) | Nov 25, 2023 |
| HP            | Pavilion 15                 | [1aa46b36ee](https://linux-hardware.org/?probe=1aa46b36ee) | Nov 25, 2023 |
| FUTOPIA GL... | ULTIMUS PRO                 | [96b6b163d8](https://linux-hardware.org/?probe=96b6b163d8) | Nov 24, 2023 |
| Timi          | Mi NoteBook Pro             | [90499ad4f0](https://linux-hardware.org/?probe=90499ad4f0) | Nov 24, 2023 |
| Timi          | RedmiBook 15                | [5bcef78473](https://linux-hardware.org/?probe=5bcef78473) | Nov 24, 2023 |
| Timi          | RedmiBook 15                | [3edc0a53ce](https://linux-hardware.org/?probe=3edc0a53ce) | Nov 24, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [df38b119a1](https://linux-hardware.org/?probe=df38b119a1) | Nov 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e5ad7dda0](https://linux-hardware.org/?probe=1e5ad7dda0) | Nov 23, 2023 |
| Acer          | Aspire Lite AL15-52         | [a86c46d6fa](https://linux-hardware.org/?probe=a86c46d6fa) | Nov 23, 2023 |
| Acer          | Predator PHN16-71           | [f202c6760e](https://linux-hardware.org/?probe=f202c6760e) | Nov 22, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [2474e3d0e7](https://linux-hardware.org/?probe=2474e3d0e7) | Nov 21, 2023 |
| HP            | Pavilion 15                 | [b12a3ea8d6](https://linux-hardware.org/?probe=b12a3ea8d6) | Nov 21, 2023 |
| HP            | Pavilion 15                 | [a38bb99384](https://linux-hardware.org/?probe=a38bb99384) | Nov 21, 2023 |
| Acer          | Nitro AN515-43              | [7dcf0b28c0](https://linux-hardware.org/?probe=7dcf0b28c0) | Nov 21, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [b312b34d74](https://linux-hardware.org/?probe=b312b34d74) | Nov 20, 2023 |
| Acer          | Predator PHN16-71           | [3b72eaca1a](https://linux-hardware.org/?probe=3b72eaca1a) | Nov 20, 2023 |
| Acer          | Predator PHN16-71           | [8248b93899](https://linux-hardware.org/?probe=8248b93899) | Nov 20, 2023 |
| HP            | Pavilion 15                 | [7239efa8fe](https://linux-hardware.org/?probe=7239efa8fe) | Nov 20, 2023 |
| HP            | Laptop 15s-fr2xxx           | [fff3e03a74](https://linux-hardware.org/?probe=fff3e03a74) | Nov 20, 2023 |
| Dell          | Vostro 1310                 | [bd82e2c035](https://linux-hardware.org/?probe=bd82e2c035) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [f118e9b0a7](https://linux-hardware.org/?probe=f118e9b0a7) | Nov 19, 2023 |
| Acer          | Predator PHN16-71           | [8901c21f98](https://linux-hardware.org/?probe=8901c21f98) | Nov 19, 2023 |
| HP            | ProBook 440 G2              | [6a9af286f8](https://linux-hardware.org/?probe=6a9af286f8) | Nov 19, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [aec2f789cf](https://linux-hardware.org/?probe=aec2f789cf) | Nov 18, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [3ad49c55c8](https://linux-hardware.org/?probe=3ad49c55c8) | Nov 18, 2023 |
| Acer          | Predator PHN16-71           | [92546d4efc](https://linux-hardware.org/?probe=92546d4efc) | Nov 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [70ca4894ab](https://linux-hardware.org/?probe=70ca4894ab) | Nov 18, 2023 |
| HP            | ProBook 430 G3              | [a02f6c770c](https://linux-hardware.org/?probe=a02f6c770c) | Nov 18, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | [54bad5da51](https://linux-hardware.org/?probe=54bad5da51) | Nov 17, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0f5f7fb08d](https://linux-hardware.org/?probe=0f5f7fb08d) | Nov 16, 2023 |
| HP            | Laptop 15s-du3xxx           | [72a6eac951](https://linux-hardware.org/?probe=72a6eac951) | Nov 15, 2023 |
| HP            | Notebook                    | [73567de74e](https://linux-hardware.org/?probe=73567de74e) | Nov 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [386519f50c](https://linux-hardware.org/?probe=386519f50c) | Nov 15, 2023 |
| HP            | Laptop 15s-fr2xxx           | [be79137b4b](https://linux-hardware.org/?probe=be79137b4b) | Nov 15, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [7df41d6e32](https://linux-hardware.org/?probe=7df41d6e32) | Nov 15, 2023 |
| MSI           | Thin GF63 12HW              | [bdac7a70aa](https://linux-hardware.org/?probe=bdac7a70aa) | Nov 14, 2023 |
| MSI           | Thin GF63 12HW              | [087220685a](https://linux-hardware.org/?probe=087220685a) | Nov 14, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [b8e2bf284d](https://linux-hardware.org/?probe=b8e2bf284d) | Nov 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [f3d934ed44](https://linux-hardware.org/?probe=f3d934ed44) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ba805ada14](https://linux-hardware.org/?probe=ba805ada14) | Nov 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [381c8b164d](https://linux-hardware.org/?probe=381c8b164d) | Nov 13, 2023 |
| HP            | Laptop 15s-fr2xxx           | [f5d3c3e682](https://linux-hardware.org/?probe=f5d3c3e682) | Nov 12, 2023 |
| ASUSTek       | X556UR                      | [c4b344c176](https://linux-hardware.org/?probe=c4b344c176) | Nov 12, 2023 |
| Alienware     | 15 R3                       | [c920563c0b](https://linux-hardware.org/?probe=c920563c0b) | Nov 12, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [197a03d08f](https://linux-hardware.org/?probe=197a03d08f) | Nov 12, 2023 |
| Timi          | Mi NoteBook Pro             | [f08c831e30](https://linux-hardware.org/?probe=f08c831e30) | Nov 11, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [565411e232](https://linux-hardware.org/?probe=565411e232) | Nov 11, 2023 |
| Dell          | Inspiron 5559               | [86d8fabf27](https://linux-hardware.org/?probe=86d8fabf27) | Nov 11, 2023 |
| Lenovo        | ThinkPad X250 20CLAOMLIN    | [88967f98bd](https://linux-hardware.org/?probe=88967f98bd) | Nov 09, 2023 |
| HP            | Notebook                    | [28b2b3c585](https://linux-hardware.org/?probe=28b2b3c585) | Nov 08, 2023 |
| HP            | Notebook                    | [8881671430](https://linux-hardware.org/?probe=8881671430) | Nov 08, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JLC... | [d44b69e61b](https://linux-hardware.org/?probe=d44b69e61b) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [63e0b9fc88](https://linux-hardware.org/?probe=63e0b9fc88) | Nov 08, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [79e23fd44a](https://linux-hardware.org/?probe=79e23fd44a) | Nov 07, 2023 |
| Timi          | Mi NoteBook Pro             | [a8a46eb495](https://linux-hardware.org/?probe=a8a46eb495) | Nov 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [1db5fee13c](https://linux-hardware.org/?probe=1db5fee13c) | Nov 05, 2023 |
| HP            | Pavilion 11 x360 PC         | [399dda92eb](https://linux-hardware.org/?probe=399dda92eb) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [49c91b6782](https://linux-hardware.org/?probe=49c91b6782) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [c39cd7480d](https://linux-hardware.org/?probe=c39cd7480d) | Nov 04, 2023 |
| HP            | 15                          | [5d5fb36764](https://linux-hardware.org/?probe=5d5fb36764) | Nov 04, 2023 |
| HP            | Compaq Presario CQ40        | [ede0c05f18](https://linux-hardware.org/?probe=ede0c05f18) | Nov 04, 2023 |
| Toshiba       | Satellite C55-C             | [07e66cf3c5](https://linux-hardware.org/?probe=07e66cf3c5) | Nov 04, 2023 |
| AVITA         | NS14A2                      | [738e0008ce](https://linux-hardware.org/?probe=738e0008ce) | Nov 04, 2023 |
| Lenovo        | G500s 20245                 | [c4aa915297](https://linux-hardware.org/?probe=c4aa915297) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [bb1da2575d](https://linux-hardware.org/?probe=bb1da2575d) | Nov 02, 2023 |
| Lenovo        | ThinkPad E14 20RAS13J00     | [ebfdc934b7](https://linux-hardware.org/?probe=ebfdc934b7) | Nov 02, 2023 |
| Acer          | Swift SF314-55G             | [fee0e3c809](https://linux-hardware.org/?probe=fee0e3c809) | Nov 02, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [137dba2261](https://linux-hardware.org/?probe=137dba2261) | Nov 02, 2023 |
| HONOR         | BRN-FXX                     | [e4b4501211](https://linux-hardware.org/?probe=e4b4501211) | Nov 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [54516fba78](https://linux-hardware.org/?probe=54516fba78) | Nov 01, 2023 |
| HP            | Compaq Presario CQ40        | [59e202bef7](https://linux-hardware.org/?probe=59e202bef7) | Nov 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [3c04d0213b](https://linux-hardware.org/?probe=3c04d0213b) | Nov 01, 2023 |
| HP            | Laptop 15q-bu0xx            | [9031850aa0](https://linux-hardware.org/?probe=9031850aa0) | Nov 01, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [70e4b3b007](https://linux-hardware.org/?probe=70e4b3b007) | Oct 31, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [352bf34e3b](https://linux-hardware.org/?probe=352bf34e3b) | Oct 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [2e35f866e3](https://linux-hardware.org/?probe=2e35f866e3) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 20RAS13J00     | [91a0aacae9](https://linux-hardware.org/?probe=91a0aacae9) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [ebec8d6fd1](https://linux-hardware.org/?probe=ebec8d6fd1) | Oct 31, 2023 |
| Acer          | One 14 Z8-415               | [e3b7fce5f3](https://linux-hardware.org/?probe=e3b7fce5f3) | Oct 31, 2023 |
| Chuwi         | CoreBook                    | [71b0d03991](https://linux-hardware.org/?probe=71b0d03991) | Oct 30, 2023 |
| Acer          | Aspire A715-51G             | [7ffe987b92](https://linux-hardware.org/?probe=7ffe987b92) | Oct 30, 2023 |
| Acer          | Aspire A715-51G             | [be3a00001c](https://linux-hardware.org/?probe=be3a00001c) | Oct 29, 2023 |
| HP            | 15                          | [cda635d432](https://linux-hardware.org/?probe=cda635d432) | Oct 28, 2023 |
| HP            | Pavilion g6                 | [ecc6e8d906](https://linux-hardware.org/?probe=ecc6e8d906) | Oct 28, 2023 |
| Acer          | Aspire 4752                 | [ce321700bc](https://linux-hardware.org/?probe=ce321700bc) | Oct 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c25324c2a2](https://linux-hardware.org/?probe=c25324c2a2) | Oct 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [49982fda5c](https://linux-hardware.org/?probe=49982fda5c) | Oct 28, 2023 |
| HCL Infosy... | HCL ME Laptop               | [a23dc90a3b](https://linux-hardware.org/?probe=a23dc90a3b) | Oct 27, 2023 |
| Timi          | Mi NoteBook Ultra           | [66cfbcd057](https://linux-hardware.org/?probe=66cfbcd057) | Oct 26, 2023 |
| HP            | ProBook 440 G6              | [f3407cd11d](https://linux-hardware.org/?probe=f3407cd11d) | Oct 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | [0ed2bd399f](https://linux-hardware.org/?probe=0ed2bd399f) | Oct 25, 2023 |
| Infinix       | INBOOK X2 SLIM              | [03333fbe23](https://linux-hardware.org/?probe=03333fbe23) | Oct 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [358936d398](https://linux-hardware.org/?probe=358936d398) | Oct 25, 2023 |
| HP            | Victus by Gaming Laptop ... | [71a22f4706](https://linux-hardware.org/?probe=71a22f4706) | Oct 25, 2023 |
| Dell          | XPS 9315                    | [9246bb9a28](https://linux-hardware.org/?probe=9246bb9a28) | Oct 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [ecde45a506](https://linux-hardware.org/?probe=ecde45a506) | Oct 24, 2023 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | [0f08eb340b](https://linux-hardware.org/?probe=0f08eb340b) | Oct 24, 2023 |
| Acer          | Aspire A315-510P            | [332b714861](https://linux-hardware.org/?probe=332b714861) | Oct 24, 2023 |
| Timi          | Mi NoteBook Pro             | [470eb40837](https://linux-hardware.org/?probe=470eb40837) | Oct 23, 2023 |
| HP            | Laptop 14s-dy5xxx           | [e873e5d24c](https://linux-hardware.org/?probe=e873e5d24c) | Oct 23, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | [399c501d43](https://linux-hardware.org/?probe=399c501d43) | Oct 23, 2023 |
| ASUSTek       | GL553VE                     | [9cb6cb4f5b](https://linux-hardware.org/?probe=9cb6cb4f5b) | Oct 22, 2023 |
| Acer          | Swift SF314-512             | [f6831bde3b](https://linux-hardware.org/?probe=f6831bde3b) | Oct 22, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 Ua 82F... | [735bb309a1](https://linux-hardware.org/?probe=735bb309a1) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [f204c7469c](https://linux-hardware.org/?probe=f204c7469c) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [5f376e3415](https://linux-hardware.org/?probe=5f376e3415) | Oct 21, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [97d1264314](https://linux-hardware.org/?probe=97d1264314) | Oct 21, 2023 |
| HP            | Victus by Gaming Laptop ... | [76632b6a09](https://linux-hardware.org/?probe=76632b6a09) | Oct 21, 2023 |
| ASUSTek       | X555LF                      | [b762dc0df0](https://linux-hardware.org/?probe=b762dc0df0) | Oct 20, 2023 |
| HP            | Victus by Gaming Laptop ... | [cc2f4a6fce](https://linux-hardware.org/?probe=cc2f4a6fce) | Oct 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9ce038aa93](https://linux-hardware.org/?probe=9ce038aa93) | Oct 20, 2023 |
| ASUSTek       | X555LF                      | [ee44c25ed9](https://linux-hardware.org/?probe=ee44c25ed9) | Oct 20, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [4e0af93a94](https://linux-hardware.org/?probe=4e0af93a94) | Oct 20, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [137f87e169](https://linux-hardware.org/?probe=137f87e169) | Oct 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [a7dbe29bbe](https://linux-hardware.org/?probe=a7dbe29bbe) | Oct 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [e7787b05fe](https://linux-hardware.org/?probe=e7787b05fe) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [cde2726f48](https://linux-hardware.org/?probe=cde2726f48) | Oct 18, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [2985805059](https://linux-hardware.org/?probe=2985805059) | Oct 18, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [57dbbcb9f3](https://linux-hardware.org/?probe=57dbbcb9f3) | Oct 18, 2023 |
| Acer          | Aspire A715-51G             | [8fb05c37a8](https://linux-hardware.org/?probe=8fb05c37a8) | Oct 18, 2023 |
| Dell          | Inspiron N5110              | [8543bed1b3](https://linux-hardware.org/?probe=8543bed1b3) | Oct 17, 2023 |
| Lenovo        | B50-70 20384                | [91d1297632](https://linux-hardware.org/?probe=91d1297632) | Oct 17, 2023 |
| Acer          | Aspire A515-57G             | [7116f7edd9](https://linux-hardware.org/?probe=7116f7edd9) | Oct 17, 2023 |
| HP            | OMEN by Laptop              | [c3bd837d33](https://linux-hardware.org/?probe=c3bd837d33) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K550... | [72e348d9bb](https://linux-hardware.org/?probe=72e348d9bb) | Oct 17, 2023 |
| Dell          | Inspiron 1545               | [03670e3e53](https://linux-hardware.org/?probe=03670e3e53) | Oct 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [73e2838408](https://linux-hardware.org/?probe=73e2838408) | Oct 16, 2023 |
| Lenovo        | G50-30 80G0                 | [3d308e7bb0](https://linux-hardware.org/?probe=3d308e7bb0) | Oct 16, 2023 |
| Dell          | Latitude 5591               | [ef0287bbad](https://linux-hardware.org/?probe=ef0287bbad) | Oct 15, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [7a732e8a25](https://linux-hardware.org/?probe=7a732e8a25) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [73f73df16b](https://linux-hardware.org/?probe=73f73df16b) | Oct 14, 2023 |
| Acer          | Aspire A715-42G             | [b63b919a75](https://linux-hardware.org/?probe=b63b919a75) | Oct 14, 2023 |
| Acer          | Aspire A715-51G             | [4ddde9e92e](https://linux-hardware.org/?probe=4ddde9e92e) | Oct 13, 2023 |
| ASUSTek       | UX430UAR                    | [e66e176aac](https://linux-hardware.org/?probe=e66e176aac) | Oct 13, 2023 |
| Dell          | Inspiron N5110              | [92726caa44](https://linux-hardware.org/?probe=92726caa44) | Oct 12, 2023 |
| Infinix       | ZERO BOOK 13                | [c20c04a240](https://linux-hardware.org/?probe=c20c04a240) | Oct 12, 2023 |
| Acer          | Swift SF315-41              | [804f28fe5b](https://linux-hardware.org/?probe=804f28fe5b) | Oct 12, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [605fcbffe8](https://linux-hardware.org/?probe=605fcbffe8) | Oct 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7aeb935c28](https://linux-hardware.org/?probe=7aeb935c28) | Oct 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a0e076c7f3](https://linux-hardware.org/?probe=a0e076c7f3) | Oct 11, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [7d7f268cec](https://linux-hardware.org/?probe=7d7f268cec) | Oct 11, 2023 |
| Acer          | Nitro AN515-58              | [767f2c26e0](https://linux-hardware.org/?probe=767f2c26e0) | Oct 10, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [50682769d9](https://linux-hardware.org/?probe=50682769d9) | Oct 10, 2023 |
| Apple         | MacBookPro11,3              | [2bc390851d](https://linux-hardware.org/?probe=2bc390851d) | Oct 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [640744cc70](https://linux-hardware.org/?probe=640744cc70) | Oct 10, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [5d606c8b1c](https://linux-hardware.org/?probe=5d606c8b1c) | Oct 10, 2023 |
| Acer          | Predator PH315-51           | [265a8e5346](https://linux-hardware.org/?probe=265a8e5346) | Oct 09, 2023 |
| Dell          | Vostro 1450                 | [55334a897d](https://linux-hardware.org/?probe=55334a897d) | Oct 08, 2023 |
| Dell          | Inspiron 14 5410            | [5f69a24978](https://linux-hardware.org/?probe=5f69a24978) | Oct 08, 2023 |
| HP            | Laptop 15s-fr2xxx           | [2dc2d438ea](https://linux-hardware.org/?probe=2dc2d438ea) | Oct 07, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [8619f7e43e](https://linux-hardware.org/?probe=8619f7e43e) | Oct 06, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [0a18c0ff5d](https://linux-hardware.org/?probe=0a18c0ff5d) | Oct 06, 2023 |
| Dell          | XPS 15 9530                 | [425aa2b0f7](https://linux-hardware.org/?probe=425aa2b0f7) | Oct 05, 2023 |
| Dell          | Inspiron 7577               | [ddadccf492](https://linux-hardware.org/?probe=ddadccf492) | Oct 05, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [1729f3bfbe](https://linux-hardware.org/?probe=1729f3bfbe) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ee95e8f5fd](https://linux-hardware.org/?probe=ee95e8f5fd) | Oct 05, 2023 |
| Lenovo        | G40-45 80E1                 | [0cf58ae6b1](https://linux-hardware.org/?probe=0cf58ae6b1) | Oct 05, 2023 |
| Sony          | VPCEB16FG                   | [9e655187a5](https://linux-hardware.org/?probe=9e655187a5) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [bdf9fff544](https://linux-hardware.org/?probe=bdf9fff544) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS06E00     | [549cad8b4f](https://linux-hardware.org/?probe=549cad8b4f) | Oct 05, 2023 |
| Dell          | Vostro 15-3568              | [3639fedec4](https://linux-hardware.org/?probe=3639fedec4) | Oct 04, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [eebbbc30b8](https://linux-hardware.org/?probe=eebbbc30b8) | Oct 03, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [f332024d38](https://linux-hardware.org/?probe=f332024d38) | Oct 03, 2023 |
| Dell          | Latitude 7400               | [bd6eee3b51](https://linux-hardware.org/?probe=bd6eee3b51) | Oct 03, 2023 |
| Acer          | Aspire A314-36M             | [5276b99f12](https://linux-hardware.org/?probe=5276b99f12) | Oct 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [160d49a81f](https://linux-hardware.org/?probe=160d49a81f) | Oct 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [445e604c2e](https://linux-hardware.org/?probe=445e604c2e) | Oct 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [4e0bb2d740](https://linux-hardware.org/?probe=4e0bb2d740) | Oct 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [840bfbb2cb](https://linux-hardware.org/?probe=840bfbb2cb) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [81027151d1](https://linux-hardware.org/?probe=81027151d1) | Oct 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f9a210173c](https://linux-hardware.org/?probe=f9a210173c) | Oct 01, 2023 |
| HP            | Laptop 14s-fq1xxx           | [3709e611a3](https://linux-hardware.org/?probe=3709e611a3) | Oct 01, 2023 |
| MSI           | Bravo 15 B5DD               | [1df2dc7261](https://linux-hardware.org/?probe=1df2dc7261) | Oct 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [59dcd18330](https://linux-hardware.org/?probe=59dcd18330) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [a6d0762090](https://linux-hardware.org/?probe=a6d0762090) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | [1c4b1aa68d](https://linux-hardware.org/?probe=1c4b1aa68d) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | [988f015a89](https://linux-hardware.org/?probe=988f015a89) | Sep 30, 2023 |
| Acer          | Aspire SW3-016              | [62c3855aa7](https://linux-hardware.org/?probe=62c3855aa7) | Sep 30, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [356b5f053d](https://linux-hardware.org/?probe=356b5f053d) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | [0c9b2c687a](https://linux-hardware.org/?probe=0c9b2c687a) | Sep 28, 2023 |
| HP            | Notebook                    | [7d55fd8520](https://linux-hardware.org/?probe=7d55fd8520) | Sep 28, 2023 |
| HP            | Notebook                    | [49192b29a6](https://linux-hardware.org/?probe=49192b29a6) | Sep 28, 2023 |
| Dell          | Inspiron 15-3567            | [d53c8ae481](https://linux-hardware.org/?probe=d53c8ae481) | Sep 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [001d5aa716](https://linux-hardware.org/?probe=001d5aa716) | Sep 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c5c6c5233a](https://linux-hardware.org/?probe=c5c6c5233a) | Sep 27, 2023 |
| Dell          | Latitude 3410               | [7b326dd690](https://linux-hardware.org/?probe=7b326dd690) | Sep 27, 2023 |
| Lenovo        | Z51-70 80K6                 | [167d2e893e](https://linux-hardware.org/?probe=167d2e893e) | Sep 27, 2023 |
| Acer          | Swift SF314-512             | [afdb68ccfe](https://linux-hardware.org/?probe=afdb68ccfe) | Sep 26, 2023 |
| Acer          | Swift SF314-512             | [d6982725f2](https://linux-hardware.org/?probe=d6982725f2) | Sep 26, 2023 |
| Infinix       | INBOOK Y1 PLUS NEO          | [30998449af](https://linux-hardware.org/?probe=30998449af) | Sep 26, 2023 |
| HP            | ProBook 430 G3              | [cc34f92566](https://linux-hardware.org/?probe=cc34f92566) | Sep 26, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [17bb721483](https://linux-hardware.org/?probe=17bb721483) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [14766bbd15](https://linux-hardware.org/?probe=14766bbd15) | Sep 26, 2023 |
| Lenovo        | Z50-70 20354                | [ccdfae441b](https://linux-hardware.org/?probe=ccdfae441b) | Sep 26, 2023 |
| Acer          | Nitro AN515-45              | [94ce4b6306](https://linux-hardware.org/?probe=94ce4b6306) | Sep 25, 2023 |
| Lenovo        | B480 20140                  | [960fe0be2b](https://linux-hardware.org/?probe=960fe0be2b) | Sep 25, 2023 |
| Infinix       | INBOOK X1 SLIM              | [bd6f358c7f](https://linux-hardware.org/?probe=bd6f358c7f) | Sep 25, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b69f53c8fe](https://linux-hardware.org/?probe=b69f53c8fe) | Sep 25, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [b42e3e4395](https://linux-hardware.org/?probe=b42e3e4395) | Sep 24, 2023 |
| Dell          | XPS 15 9570                 | [fe5f9ad018](https://linux-hardware.org/?probe=fe5f9ad018) | Sep 23, 2023 |
| Acer          | Aspire A515-56              | [4e91084325](https://linux-hardware.org/?probe=4e91084325) | Sep 23, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [793c32918d](https://linux-hardware.org/?probe=793c32918d) | Sep 23, 2023 |
| Acer          | Aspire A515-51              | [f6369d0be5](https://linux-hardware.org/?probe=f6369d0be5) | Sep 23, 2023 |
| Samsung       | 935XDB                      | [a0672b9726](https://linux-hardware.org/?probe=a0672b9726) | Sep 23, 2023 |
| Acer          | Aspire A715-51G             | [674c086aa5](https://linux-hardware.org/?probe=674c086aa5) | Sep 22, 2023 |
| HP            | ProBook 430 G3              | [67ac6fc0d9](https://linux-hardware.org/?probe=67ac6fc0d9) | Sep 22, 2023 |
| HP            | ProBook 430 G3              | [519a567ecb](https://linux-hardware.org/?probe=519a567ecb) | Sep 22, 2023 |
| Acer          | Nitro AN515-58              | [fc49b16c1c](https://linux-hardware.org/?probe=fc49b16c1c) | Sep 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c00e994c2c](https://linux-hardware.org/?probe=c00e994c2c) | Sep 21, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [874c33c481](https://linux-hardware.org/?probe=874c33c481) | Sep 21, 2023 |
| Timi          | RedmiBook 15                | [af7ac2b917](https://linux-hardware.org/?probe=af7ac2b917) | Sep 21, 2023 |
| HP            | Pavilion Notebook           | [a085f48523](https://linux-hardware.org/?probe=a085f48523) | Sep 20, 2023 |
| Dell          | Vostro 3583                 | [f01ce05b1f](https://linux-hardware.org/?probe=f01ce05b1f) | Sep 20, 2023 |
| Lenovo        | G580 20157                  | [9b576274e4](https://linux-hardware.org/?probe=9b576274e4) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [1850488dd1](https://linux-hardware.org/?probe=1850488dd1) | Sep 20, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [c122be4331](https://linux-hardware.org/?probe=c122be4331) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [a97463154d](https://linux-hardware.org/?probe=a97463154d) | Sep 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [00c6b8cced](https://linux-hardware.org/?probe=00c6b8cced) | Sep 20, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [8adb5c3a12](https://linux-hardware.org/?probe=8adb5c3a12) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [052438c7dd](https://linux-hardware.org/?probe=052438c7dd) | Sep 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [a87ec029ab](https://linux-hardware.org/?probe=a87ec029ab) | Sep 19, 2023 |
| Lenovo        | E41-25 81FS                 | [6233a0f825](https://linux-hardware.org/?probe=6233a0f825) | Sep 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [aeffbe0fe5](https://linux-hardware.org/?probe=aeffbe0fe5) | Sep 19, 2023 |
| HP            | Notebook                    | [3c10ef5d72](https://linux-hardware.org/?probe=3c10ef5d72) | Sep 19, 2023 |
| MSI           | Thin GF63 12HW              | [39a50dc7e8](https://linux-hardware.org/?probe=39a50dc7e8) | Sep 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [cad09f007e](https://linux-hardware.org/?probe=cad09f007e) | Sep 18, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [5b5eb2a0a5](https://linux-hardware.org/?probe=5b5eb2a0a5) | Sep 18, 2023 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [0460fafb99](https://linux-hardware.org/?probe=0460fafb99) | Sep 17, 2023 |
| Dell          | XPS L501X                   | [13d0075027](https://linux-hardware.org/?probe=13d0075027) | Sep 16, 2023 |
| HP            | 245 G8 Notebook PC          | [06e2986bbc](https://linux-hardware.org/?probe=06e2986bbc) | Sep 16, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [506d025e1e](https://linux-hardware.org/?probe=506d025e1e) | Sep 15, 2023 |
| Timi          | Mi NoteBook Ultra           | [1c5a009557](https://linux-hardware.org/?probe=1c5a009557) | Sep 15, 2023 |
| HP            | ENVY 15                     | [c5c9db023b](https://linux-hardware.org/?probe=c5c9db023b) | Sep 15, 2023 |
| HP            | ENVY 15                     | [9741cff4ca](https://linux-hardware.org/?probe=9741cff4ca) | Sep 15, 2023 |
| Dell          | Inspiron 15 5510            | [71a6a04c4c](https://linux-hardware.org/?probe=71a6a04c4c) | Sep 15, 2023 |
| Acer          | Predator PH315-54           | [bb4b6fe52f](https://linux-hardware.org/?probe=bb4b6fe52f) | Sep 15, 2023 |
| Apple         | MacBookPro9,2               | [37e1d06001](https://linux-hardware.org/?probe=37e1d06001) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [b30ec0e0a8](https://linux-hardware.org/?probe=b30ec0e0a8) | Sep 14, 2023 |
| Acer          | Predator PH315-54           | [e1a54edbdc](https://linux-hardware.org/?probe=e1a54edbdc) | Sep 14, 2023 |
| MSI           | Thin GF63 12HW              | [79e6e5fc48](https://linux-hardware.org/?probe=79e6e5fc48) | Sep 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1703cfdd5e](https://linux-hardware.org/?probe=1703cfdd5e) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | [e8b1e251a3](https://linux-hardware.org/?probe=e8b1e251a3) | Sep 13, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [deb3ba5bf7](https://linux-hardware.org/?probe=deb3ba5bf7) | Sep 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [c2b009d544](https://linux-hardware.org/?probe=c2b009d544) | Sep 12, 2023 |
| Lenovo        | IDEA 315-15 81WE            | [f148c9218a](https://linux-hardware.org/?probe=f148c9218a) | Sep 12, 2023 |
| Dell          | Inspiron 5570               | [005f0b4e53](https://linux-hardware.org/?probe=005f0b4e53) | Sep 11, 2023 |
| Dell          | Inspiron 7577               | [aabd401f54](https://linux-hardware.org/?probe=aabd401f54) | Sep 11, 2023 |
| Dell          | Inspiron 5570               | [bffb256730](https://linux-hardware.org/?probe=bffb256730) | Sep 11, 2023 |
| Acer          | Predator PH315-54           | [2088909e8a](https://linux-hardware.org/?probe=2088909e8a) | Sep 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [16b6bd1d3d](https://linux-hardware.org/?probe=16b6bd1d3d) | Sep 09, 2023 |
| Acer          | Aspire A715-51G             | [25649c8a92](https://linux-hardware.org/?probe=25649c8a92) | Sep 09, 2023 |
| Dell          | Latitude E6430              | [0ace4858e1](https://linux-hardware.org/?probe=0ace4858e1) | Sep 09, 2023 |
| HP            | 255 G8 Notebook PC          | [bdd270eddd](https://linux-hardware.org/?probe=bdd270eddd) | Sep 09, 2023 |
| HP            | Laptop 15s-fr1xxx           | [a6e3c47b2d](https://linux-hardware.org/?probe=a6e3c47b2d) | Sep 08, 2023 |
| Gateway       | NE56R                       | [ec2415b16d](https://linux-hardware.org/?probe=ec2415b16d) | Sep 08, 2023 |
| Gateway       | NE56R                       | [4871fca687](https://linux-hardware.org/?probe=4871fca687) | Sep 08, 2023 |
| Acer          | Aspire E5-575G              | [8ebe24476b](https://linux-hardware.org/?probe=8ebe24476b) | Sep 07, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [a2fab791b4](https://linux-hardware.org/?probe=a2fab791b4) | Sep 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [003d136012](https://linux-hardware.org/?probe=003d136012) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [24eca3030c](https://linux-hardware.org/?probe=24eca3030c) | Sep 07, 2023 |
| Dell          | Latitude 3520               | [0fa236983e](https://linux-hardware.org/?probe=0fa236983e) | Sep 06, 2023 |
| MSI           | Modern 15 A5M               | [eb92b04384](https://linux-hardware.org/?probe=eb92b04384) | Sep 06, 2023 |
| Gateway       | NE56R                       | [ade8432ca6](https://linux-hardware.org/?probe=ade8432ca6) | Sep 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4ed976d4ba](https://linux-hardware.org/?probe=4ed976d4ba) | Sep 06, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [bb7f6aed1a](https://linux-hardware.org/?probe=bb7f6aed1a) | Sep 05, 2023 |
| Gateway       | NE56R                       | [be83386f4d](https://linux-hardware.org/?probe=be83386f4d) | Sep 05, 2023 |
| HONOR         | BRN-FXX                     | [381e87228c](https://linux-hardware.org/?probe=381e87228c) | Sep 04, 2023 |
| Gateway       | NE56R                       | [99b1c83e93](https://linux-hardware.org/?probe=99b1c83e93) | Sep 04, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [f7a6b9d479](https://linux-hardware.org/?probe=f7a6b9d479) | Sep 04, 2023 |
| HP            | 247 G8 Notebook PC          | [74a7d9e304](https://linux-hardware.org/?probe=74a7d9e304) | Sep 04, 2023 |
| Toshiba       | Satellite C850              | [188a672b4d](https://linux-hardware.org/?probe=188a672b4d) | Sep 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [7b776b30bd](https://linux-hardware.org/?probe=7b776b30bd) | Sep 03, 2023 |
| HP            | Pavilion Gaming Laptop      | [733f5cb987](https://linux-hardware.org/?probe=733f5cb987) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [2ddf0c5c61](https://linux-hardware.org/?probe=2ddf0c5c61) | Sep 03, 2023 |
| Acer          | Aspire A715-75G             | [69b91f1c46](https://linux-hardware.org/?probe=69b91f1c46) | Sep 03, 2023 |
| HP            | Pavilion dv4                | [8d183fb271](https://linux-hardware.org/?probe=8d183fb271) | Sep 03, 2023 |
| Dell          | Vostro 14-3468              | [2f75949c09](https://linux-hardware.org/?probe=2f75949c09) | Sep 03, 2023 |
| Lenovo        | ThinkPad T490 20N3S77601    | [b659e310c9](https://linux-hardware.org/?probe=b659e310c9) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [f2f5e496f1](https://linux-hardware.org/?probe=f2f5e496f1) | Sep 02, 2023 |
| HP            | Pavilion g6                 | [0f0960322d](https://linux-hardware.org/?probe=0f0960322d) | Sep 01, 2023 |
| Timi          | Mi NoteBook Pro             | [7d3823ff94](https://linux-hardware.org/?probe=7d3823ff94) | Sep 01, 2023 |
| HP            | EliteBook 840 G3            | [929ae155ea](https://linux-hardware.org/?probe=929ae155ea) | Sep 01, 2023 |
| Dell          | Latitude 5400               | [dee2becb07](https://linux-hardware.org/?probe=dee2becb07) | Sep 01, 2023 |
| HP            | EliteBook 840 G3            | [3411b788bc](https://linux-hardware.org/?probe=3411b788bc) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [c3d8f5daca](https://linux-hardware.org/?probe=c3d8f5daca) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [f94ed7f5d1](https://linux-hardware.org/?probe=f94ed7f5d1) | Aug 31, 2023 |
| HP            | 15                          | [39567282e3](https://linux-hardware.org/?probe=39567282e3) | Aug 31, 2023 |
| MSI           | Thin GF63 12VE              | [0615d252af](https://linux-hardware.org/?probe=0615d252af) | Aug 31, 2023 |
| Lenovo        | G50-80 80E5                 | [8adf70b56e](https://linux-hardware.org/?probe=8adf70b56e) | Aug 31, 2023 |
| Dell          | Inspiron 3576               | [f69425a68d](https://linux-hardware.org/?probe=f69425a68d) | Aug 30, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [4bedf20d35](https://linux-hardware.org/?probe=4bedf20d35) | Aug 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [78e163bc13](https://linux-hardware.org/?probe=78e163bc13) | Aug 30, 2023 |
| Acer          | One Z1402                   | [2e917719ec](https://linux-hardware.org/?probe=2e917719ec) | Aug 29, 2023 |
| HONOR         | NMH-WCX9                    | [6e4b12a41e](https://linux-hardware.org/?probe=6e4b12a41e) | Aug 29, 2023 |
| Infinix       | INBOOK X2 SLIM              | [93fd8245ab](https://linux-hardware.org/?probe=93fd8245ab) | Aug 29, 2023 |
| Infinix       | INBOOK X2 SLIM              | [fafc374d46](https://linux-hardware.org/?probe=fafc374d46) | Aug 29, 2023 |
| Dell          | Inspiron 3501               | [9d092039d3](https://linux-hardware.org/?probe=9d092039d3) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | [8a7f22304b](https://linux-hardware.org/?probe=8a7f22304b) | Aug 29, 2023 |
| Dell          | Inspiron 3501               | [65f52f1180](https://linux-hardware.org/?probe=65f52f1180) | Aug 29, 2023 |
| HP            | Laptop 14s-dy2xxx           | [598458b278](https://linux-hardware.org/?probe=598458b278) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [de65d63e10](https://linux-hardware.org/?probe=de65d63e10) | Aug 28, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHC... | [dc9a79314c](https://linux-hardware.org/?probe=dc9a79314c) | Aug 28, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [15b81ebfc0](https://linux-hardware.org/?probe=15b81ebfc0) | Aug 28, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [a762e96941](https://linux-hardware.org/?probe=a762e96941) | Aug 28, 2023 |
| Dell          | Inspiron 5542               | [70fbf53140](https://linux-hardware.org/?probe=70fbf53140) | Aug 27, 2023 |
| Lenovo        | V15 G2 ALC Ua 82KD          | [79c52635ec](https://linux-hardware.org/?probe=79c52635ec) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [fe02fb8d64](https://linux-hardware.org/?probe=fe02fb8d64) | Aug 27, 2023 |
| Lenovo        | ThinkPad W540 20BG0016US    | [3b5476180b](https://linux-hardware.org/?probe=3b5476180b) | Aug 26, 2023 |
| Acer          | Aspire E1-531               | [1a1924897a](https://linux-hardware.org/?probe=1a1924897a) | Aug 26, 2023 |
| Lenovo        | G50-70 20351                | [25c5011587](https://linux-hardware.org/?probe=25c5011587) | Aug 25, 2023 |
| Dell          | Inspiron 5547               | [1fde0105bf](https://linux-hardware.org/?probe=1fde0105bf) | Aug 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3f37fa5636](https://linux-hardware.org/?probe=3f37fa5636) | Aug 25, 2023 |
| Dell          | Inspiron N5050              | [4d282e98b2](https://linux-hardware.org/?probe=4d282e98b2) | Aug 24, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [5bddf6d37d](https://linux-hardware.org/?probe=5bddf6d37d) | Aug 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [38573350a3](https://linux-hardware.org/?probe=38573350a3) | Aug 23, 2023 |
| Dell          | Vostro 3558                 | [61cb58f13b](https://linux-hardware.org/?probe=61cb58f13b) | Aug 23, 2023 |
| Dell          | Inspiron 1525               | [6c4e1108c1](https://linux-hardware.org/?probe=6c4e1108c1) | Aug 23, 2023 |
| HP            | EliteBook 840 G2            | [c8cc960675](https://linux-hardware.org/?probe=c8cc960675) | Aug 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [0b0926bb45](https://linux-hardware.org/?probe=0b0926bb45) | Aug 21, 2023 |
| Dell          | Inspiron 5547               | [b5b7a6d8f8](https://linux-hardware.org/?probe=b5b7a6d8f8) | Aug 21, 2023 |
| MSI           | Modern 15 A5M               | [f9742049fc](https://linux-hardware.org/?probe=f9742049fc) | Aug 20, 2023 |
| ASUSTek       | ROG Strix G712LU            | [7fd51c6d4d](https://linux-hardware.org/?probe=7fd51c6d4d) | Aug 20, 2023 |
| Lenovo        | G50-80 80E5                 | [6d8baa3226](https://linux-hardware.org/?probe=6d8baa3226) | Aug 20, 2023 |
| Lenovo        | ThinkPad E470 20H2S0XB00    | [517d8c57d2](https://linux-hardware.org/?probe=517d8c57d2) | Aug 19, 2023 |
| Dell          | Vostro 3401                 | [792ea03809](https://linux-hardware.org/?probe=792ea03809) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [80b304814d](https://linux-hardware.org/?probe=80b304814d) | Aug 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dee14abe77](https://linux-hardware.org/?probe=dee14abe77) | Aug 18, 2023 |
| Lenovo        | ThinkPad X230 23253B3       | [8da8bfe394](https://linux-hardware.org/?probe=8da8bfe394) | Aug 18, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [c95ab5ea6e](https://linux-hardware.org/?probe=c95ab5ea6e) | Aug 18, 2023 |
| Dell          | Vostro 3501                 | [5369c283ad](https://linux-hardware.org/?probe=5369c283ad) | Aug 18, 2023 |
| Infinix       | INBOOK X1 NEO               | [bb08f7158b](https://linux-hardware.org/?probe=bb08f7158b) | Aug 18, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [78d5f440ff](https://linux-hardware.org/?probe=78d5f440ff) | Aug 17, 2023 |
| Dell          | Latitude E6520              | [15420bd102](https://linux-hardware.org/?probe=15420bd102) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [145e7ceb96](https://linux-hardware.org/?probe=145e7ceb96) | Aug 16, 2023 |
| Acer          | Swift SF314-510G            | [11a4bc0bac](https://linux-hardware.org/?probe=11a4bc0bac) | Aug 16, 2023 |
| Dell          | Latitude 3520               | [33d3220fa3](https://linux-hardware.org/?probe=33d3220fa3) | Aug 16, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [8298417da7](https://linux-hardware.org/?probe=8298417da7) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [ff958dc821](https://linux-hardware.org/?probe=ff958dc821) | Aug 16, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [859e36f237](https://linux-hardware.org/?probe=859e36f237) | Aug 16, 2023 |
| Dell          | Latitude 5300               | [506c05d30c](https://linux-hardware.org/?probe=506c05d30c) | Aug 15, 2023 |
| Lenovo        | G50-70 20351                | [ea9845e55b](https://linux-hardware.org/?probe=ea9845e55b) | Aug 15, 2023 |
| MSI           | Katana GF76 11UD            | [31beedbfba](https://linux-hardware.org/?probe=31beedbfba) | Aug 15, 2023 |
| Lenovo        | Legion Y740-15IRH 81UF      | [2b0ec42ffb](https://linux-hardware.org/?probe=2b0ec42ffb) | Aug 15, 2023 |
| Acer          | Aspire A515-57G             | [5a2c741f84](https://linux-hardware.org/?probe=5a2c741f84) | Aug 14, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [cfc638b4b2](https://linux-hardware.org/?probe=cfc638b4b2) | Aug 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1c643cc90f](https://linux-hardware.org/?probe=1c643cc90f) | Aug 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5286543cae](https://linux-hardware.org/?probe=5286543cae) | Aug 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [464dc037bd](https://linux-hardware.org/?probe=464dc037bd) | Aug 13, 2023 |
| MSI           | GF63 Thin 10SC              | [f98e22f722](https://linux-hardware.org/?probe=f98e22f722) | Aug 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e0e0c962d5](https://linux-hardware.org/?probe=e0e0c962d5) | Aug 12, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [c336f9aa8c](https://linux-hardware.org/?probe=c336f9aa8c) | Aug 11, 2023 |
| HP            | Pavilion Notebook           | [980f6773f8](https://linux-hardware.org/?probe=980f6773f8) | Aug 10, 2023 |
| HP            | Pavilion Laptop 14-dv2xx... | [479f066821](https://linux-hardware.org/?probe=479f066821) | Aug 10, 2023 |
| Apple         | MacBookPro9,2               | [e703bb179f](https://linux-hardware.org/?probe=e703bb179f) | Aug 10, 2023 |
| Valve         | Jupiter                     | [eee501d93c](https://linux-hardware.org/?probe=eee501d93c) | Aug 09, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eec04bec1d](https://linux-hardware.org/?probe=eec04bec1d) | Aug 08, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c9c978701a](https://linux-hardware.org/?probe=c9c978701a) | Aug 08, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [f69459e15a](https://linux-hardware.org/?probe=f69459e15a) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [58446ba97c](https://linux-hardware.org/?probe=58446ba97c) | Aug 08, 2023 |
| MSI           | GL63 8RC                    | [d91d6193e6](https://linux-hardware.org/?probe=d91d6193e6) | Aug 07, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JRS... | [ebcf58253e](https://linux-hardware.org/?probe=ebcf58253e) | Aug 07, 2023 |
| HP            | ProBook 640 G2              | [8dae611904](https://linux-hardware.org/?probe=8dae611904) | Aug 06, 2023 |
| Dell          | Inspiron 15-3552            | [91376cc583](https://linux-hardware.org/?probe=91376cc583) | Aug 06, 2023 |
| HP            | EliteBook 840 G4            | [44d851d327](https://linux-hardware.org/?probe=44d851d327) | Aug 06, 2023 |
| Dell          | Inspiron 7572               | [2509709a1e](https://linux-hardware.org/?probe=2509709a1e) | Aug 06, 2023 |
| Dell          | Precision 3571              | [fdbbd33ee6](https://linux-hardware.org/?probe=fdbbd33ee6) | Aug 06, 2023 |
| Dell          | Precision 3571              | [76de48bd02](https://linux-hardware.org/?probe=76de48bd02) | Aug 06, 2023 |
| Dell          | Inspiron 3542               | [6af70944d8](https://linux-hardware.org/?probe=6af70944d8) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | [1790fa9d72](https://linux-hardware.org/?probe=1790fa9d72) | Aug 05, 2023 |
| HP            | 15                          | [77ae1d8e7e](https://linux-hardware.org/?probe=77ae1d8e7e) | Aug 05, 2023 |
| HP            | Pavilion Laptop 15-cc1xx    | [771a45e46f](https://linux-hardware.org/?probe=771a45e46f) | Aug 05, 2023 |
| Fujitsu       | LIFEBOOK LH532              | [ba3a2e1773](https://linux-hardware.org/?probe=ba3a2e1773) | Aug 04, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [0147060507](https://linux-hardware.org/?probe=0147060507) | Aug 04, 2023 |
| HP            | Compaq Presario CQ40        | [c5ea71f927](https://linux-hardware.org/?probe=c5ea71f927) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [082f92da07](https://linux-hardware.org/?probe=082f92da07) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [1078db460a](https://linux-hardware.org/?probe=1078db460a) | Aug 04, 2023 |
| Dell          | Vostro 3405                 | [db4954c21d](https://linux-hardware.org/?probe=db4954c21d) | Aug 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [0cf8e99478](https://linux-hardware.org/?probe=0cf8e99478) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | [38f33f3878](https://linux-hardware.org/?probe=38f33f3878) | Aug 03, 2023 |
| Alienware     | 14                          | [90512d5e80](https://linux-hardware.org/?probe=90512d5e80) | Aug 02, 2023 |
| HP            | Notebook                    | [258f6a82ad](https://linux-hardware.org/?probe=258f6a82ad) | Aug 02, 2023 |
| Dell          | Inspiron 1545               | [97d2508df2](https://linux-hardware.org/?probe=97d2508df2) | Aug 02, 2023 |
| Dell          | Inspiron 15-3552            | [2019699cac](https://linux-hardware.org/?probe=2019699cac) | Aug 02, 2023 |
| Acer          | Nitro AN515-45              | [5523e61097](https://linux-hardware.org/?probe=5523e61097) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [32d205bbdf](https://linux-hardware.org/?probe=32d205bbdf) | Aug 02, 2023 |
| HP            | ProBook 440 G5              | [c0de5c7032](https://linux-hardware.org/?probe=c0de5c7032) | Aug 02, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [6fe0b53a1b](https://linux-hardware.org/?probe=6fe0b53a1b) | Aug 02, 2023 |
| Dell          | Latitude E7470              | [d377538364](https://linux-hardware.org/?probe=d377538364) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [5650f66cd4](https://linux-hardware.org/?probe=5650f66cd4) | Jul 31, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [ff6816b285](https://linux-hardware.org/?probe=ff6816b285) | Jul 31, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | [f641b9c622](https://linux-hardware.org/?probe=f641b9c622) | Jul 30, 2023 |
| Dell          | Latitude E5270              | [ae07c57989](https://linux-hardware.org/?probe=ae07c57989) | Jul 30, 2023 |
| MSI           | Bravo 15 B5DD               | [d9d3f5bce4](https://linux-hardware.org/?probe=d9d3f5bce4) | Jul 30, 2023 |
| Lenovo        | G500s 20245                 | [eff9350e7f](https://linux-hardware.org/?probe=eff9350e7f) | Jul 29, 2023 |
| Dell          | Inspiron 5593               | [6a6420b23e](https://linux-hardware.org/?probe=6a6420b23e) | Jul 29, 2023 |
| Dell          | Precision 3550              | [0ecac77f90](https://linux-hardware.org/?probe=0ecac77f90) | Jul 28, 2023 |
| Dell          | Precision 3550              | [95ae018833](https://linux-hardware.org/?probe=95ae018833) | Jul 28, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [2f6969a3c9](https://linux-hardware.org/?probe=2f6969a3c9) | Jul 27, 2023 |
| MSI           | Alpha 15 B5EEK              | [d6a4c29101](https://linux-hardware.org/?probe=d6a4c29101) | Jul 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CJC... | [d7fa33e7b1](https://linux-hardware.org/?probe=d7fa33e7b1) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [1bac11c715](https://linux-hardware.org/?probe=1bac11c715) | Jul 26, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [1409af2a38](https://linux-hardware.org/?probe=1409af2a38) | Jul 26, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [866a4197cd](https://linux-hardware.org/?probe=866a4197cd) | Jul 26, 2023 |
| Acer          | Aspire A715-42G             | [a6abe36eef](https://linux-hardware.org/?probe=a6abe36eef) | Jul 26, 2023 |
| Acer          | Aspire A515-57G             | [8a297cb644](https://linux-hardware.org/?probe=8a297cb644) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [82a990b785](https://linux-hardware.org/?probe=82a990b785) | Jul 26, 2023 |
| Dell          | Vostro 3405                 | [dc97ca175a](https://linux-hardware.org/?probe=dc97ca175a) | Jul 25, 2023 |
| HP            | ENVY Notebook               | [9ab8362949](https://linux-hardware.org/?probe=9ab8362949) | Jul 25, 2023 |
| Timi          | Mi NoteBook Ultra           | [e1fea727ff](https://linux-hardware.org/?probe=e1fea727ff) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | [61646d77f1](https://linux-hardware.org/?probe=61646d77f1) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [61c84247e6](https://linux-hardware.org/?probe=61c84247e6) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [8377b87a66](https://linux-hardware.org/?probe=8377b87a66) | Jul 24, 2023 |
| ASUSTek       | X541UV                      | [eb0aac9c32](https://linux-hardware.org/?probe=eb0aac9c32) | Jul 24, 2023 |
| Acer          | Aspire A315-59              | [8ecb2eb1fc](https://linux-hardware.org/?probe=8ecb2eb1fc) | Jul 24, 2023 |
| Lenovo        | E41-25 81FS                 | [d9f18f8f28](https://linux-hardware.org/?probe=d9f18f8f28) | Jul 24, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [e822964466](https://linux-hardware.org/?probe=e822964466) | Jul 24, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [313f3aa210](https://linux-hardware.org/?probe=313f3aa210) | Jul 23, 2023 |
| Dell          | Latitude 3490               | [8988026686](https://linux-hardware.org/?probe=8988026686) | Jul 23, 2023 |
| Dell          | Latitude 3490               | [b7f8f886f8](https://linux-hardware.org/?probe=b7f8f886f8) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [6c0c0671df](https://linux-hardware.org/?probe=6c0c0671df) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [cc08425e5b](https://linux-hardware.org/?probe=cc08425e5b) | Jul 22, 2023 |
| Dell          | Inspiron 3558               | [2cad6d3cb7](https://linux-hardware.org/?probe=2cad6d3cb7) | Jul 22, 2023 |
| Timi          | Mi NoteBook Horizon Edit... | [72a5dfb7cd](https://linux-hardware.org/?probe=72a5dfb7cd) | Jul 21, 2023 |
| Lenovo        | Z50-70 20354                | [33150ea27b](https://linux-hardware.org/?probe=33150ea27b) | Jul 21, 2023 |
| Timi          | Mi NoteBook Ultra           | [6bb2b5bfb6](https://linux-hardware.org/?probe=6bb2b5bfb6) | Jul 20, 2023 |
| HP            | EliteBook 840 G5            | [df9e2bd667](https://linux-hardware.org/?probe=df9e2bd667) | Jul 20, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [061efe2135](https://linux-hardware.org/?probe=061efe2135) | Jul 20, 2023 |
| Acer          | Nitro AN515-58              | [18a6e9f055](https://linux-hardware.org/?probe=18a6e9f055) | Jul 20, 2023 |
| HP            | Pavilion Notebook           | [d366e7101c](https://linux-hardware.org/?probe=d366e7101c) | Jul 20, 2023 |
| AVITA         | NS14A6                      | [594afbeb74](https://linux-hardware.org/?probe=594afbeb74) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [77468bcff7](https://linux-hardware.org/?probe=77468bcff7) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [eb7b37c1d2](https://linux-hardware.org/?probe=eb7b37c1d2) | Jul 19, 2023 |
| HP            | Notebook                    | [2ccf016245](https://linux-hardware.org/?probe=2ccf016245) | Jul 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [38c5f4d547](https://linux-hardware.org/?probe=38c5f4d547) | Jul 19, 2023 |
| Dell          | Precision 3581              | [68d58784d5](https://linux-hardware.org/?probe=68d58784d5) | Jul 18, 2023 |
| Dell          | Latitude 5480               | [30aaaf3ba8](https://linux-hardware.org/?probe=30aaaf3ba8) | Jul 18, 2023 |
| Dell          | Latitude 3590               | [6386a869e5](https://linux-hardware.org/?probe=6386a869e5) | Jul 18, 2023 |
| Acer          | Predator PH315-53           | [3d0b2577a1](https://linux-hardware.org/?probe=3d0b2577a1) | Jul 18, 2023 |
| Dell          | Latitude 7480               | [83caa544f7](https://linux-hardware.org/?probe=83caa544f7) | Jul 18, 2023 |
| Dell          | Latitude 7480               | [526e020c94](https://linux-hardware.org/?probe=526e020c94) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d43ad7594c](https://linux-hardware.org/?probe=d43ad7594c) | Jul 16, 2023 |
| HP            | 15                          | [73b0c0312f](https://linux-hardware.org/?probe=73b0c0312f) | Jul 15, 2023 |
| Timi          | Mi NoteBook Ultra           | [94f963ff8c](https://linux-hardware.org/?probe=94f963ff8c) | Jul 15, 2023 |
| Lenovo        | G50-70 20351                | [b8481d7a4c](https://linux-hardware.org/?probe=b8481d7a4c) | Jul 14, 2023 |
| Dell          | Latitude 5480               | [c74dc748f5](https://linux-hardware.org/?probe=c74dc748f5) | Jul 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1e2b959156](https://linux-hardware.org/?probe=1e2b959156) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [e042e7c94e](https://linux-hardware.org/?probe=e042e7c94e) | Jul 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [76513f6a7d](https://linux-hardware.org/?probe=76513f6a7d) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [934947072a](https://linux-hardware.org/?probe=934947072a) | Jul 13, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [d5079cefe1](https://linux-hardware.org/?probe=d5079cefe1) | Jul 13, 2023 |
| MSI           | Katana GF66 11UC            | [d22ab22240](https://linux-hardware.org/?probe=d22ab22240) | Jul 13, 2023 |
| Acer          | Nitro AN515-58              | [b31130eea6](https://linux-hardware.org/?probe=b31130eea6) | Jul 13, 2023 |
| Timi          | Mi NoteBook Ultra           | [04c4e233af](https://linux-hardware.org/?probe=04c4e233af) | Jul 12, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [618c0c975b](https://linux-hardware.org/?probe=618c0c975b) | Jul 12, 2023 |
| Dell          | Inspiron 5590               | [f3c9995017](https://linux-hardware.org/?probe=f3c9995017) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [aea754f076](https://linux-hardware.org/?probe=aea754f076) | Jul 11, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [05f889dc1a](https://linux-hardware.org/?probe=05f889dc1a) | Jul 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [37bc760339](https://linux-hardware.org/?probe=37bc760339) | Jul 11, 2023 |
| Acer          | Nitro AN515-58              | [76d89b3b3b](https://linux-hardware.org/?probe=76d89b3b3b) | Jul 11, 2023 |
| Dell          | Inspiron 1545               | [50ed801045](https://linux-hardware.org/?probe=50ed801045) | Jul 11, 2023 |
| HP            | Pavilion - 14-CE2068ST      | [bdf8b67813](https://linux-hardware.org/?probe=bdf8b67813) | Jul 10, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [806e14ad19](https://linux-hardware.org/?probe=806e14ad19) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3a1baa8f6c](https://linux-hardware.org/?probe=3a1baa8f6c) | Jul 09, 2023 |
| HP            | Notebook                    | [a1c37a6a4b](https://linux-hardware.org/?probe=a1c37a6a4b) | Jul 09, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [ce4fed4466](https://linux-hardware.org/?probe=ce4fed4466) | Jul 08, 2023 |
| Dell          | Latitude E5440              | [9b4a70fe2b](https://linux-hardware.org/?probe=9b4a70fe2b) | Jul 08, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [629f165835](https://linux-hardware.org/?probe=629f165835) | Jul 07, 2023 |
| Dell          | Inspiron 3543               | [b7459d1653](https://linux-hardware.org/?probe=b7459d1653) | Jul 07, 2023 |
| HP            | ProBook 4525s               | [e70917548c](https://linux-hardware.org/?probe=e70917548c) | Jul 07, 2023 |
| HP            | Laptop                      | [30a1d8ec1c](https://linux-hardware.org/?probe=30a1d8ec1c) | Jul 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [e555b073b5](https://linux-hardware.org/?probe=e555b073b5) | Jul 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [b11fe33b8c](https://linux-hardware.org/?probe=b11fe33b8c) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | [f5f96d51ed](https://linux-hardware.org/?probe=f5f96d51ed) | Jul 05, 2023 |
| HP            | Laptop 14s-ef1xxx           | [14e321559e](https://linux-hardware.org/?probe=14e321559e) | Jul 04, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [a889efa719](https://linux-hardware.org/?probe=a889efa719) | Jul 04, 2023 |
| MSI           | GF63 Thin 11UC              | [86c82575ec](https://linux-hardware.org/?probe=86c82575ec) | Jul 04, 2023 |
| Dell          | Precision 3581              | [1d4db3cec3](https://linux-hardware.org/?probe=1d4db3cec3) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [dfd66d3d07](https://linux-hardware.org/?probe=dfd66d3d07) | Jul 03, 2023 |
| ASUSTek       | X541UAK                     | [c4dcbea71d](https://linux-hardware.org/?probe=c4dcbea71d) | Jul 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [da24c07da6](https://linux-hardware.org/?probe=da24c07da6) | Jul 02, 2023 |
| HP            | EliteBook 820 G3            | [09c7b86b2c](https://linux-hardware.org/?probe=09c7b86b2c) | Jul 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [835f3a390f](https://linux-hardware.org/?probe=835f3a390f) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [3271b3b559](https://linux-hardware.org/?probe=3271b3b559) | Jul 02, 2023 |
| HONOR         | NMH-WCX9                    | [a8caf9af8e](https://linux-hardware.org/?probe=a8caf9af8e) | Jul 02, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [0c4c59cf86](https://linux-hardware.org/?probe=0c4c59cf86) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | [d0fc2ea58e](https://linux-hardware.org/?probe=d0fc2ea58e) | Jul 01, 2023 |
| ASUSTek       | X541UV                      | [8b5dc3456b](https://linux-hardware.org/?probe=8b5dc3456b) | Jul 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [0aed51f639](https://linux-hardware.org/?probe=0aed51f639) | Jul 01, 2023 |
| Infinix       | INBOOK X2 PLUS              | [9a74f19725](https://linux-hardware.org/?probe=9a74f19725) | Jul 01, 2023 |
| Acer          | Aspire E5-575G              | [f127804b4a](https://linux-hardware.org/?probe=f127804b4a) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [10467d9f3e](https://linux-hardware.org/?probe=10467d9f3e) | Jun 30, 2023 |
| HP            | 15                          | [2d80407689](https://linux-hardware.org/?probe=2d80407689) | Jun 30, 2023 |
| HP            | 15                          | [398d659d8c](https://linux-hardware.org/?probe=398d659d8c) | Jun 30, 2023 |
| Acer          | Aspire E5-575               | [602d134940](https://linux-hardware.org/?probe=602d134940) | Jun 30, 2023 |
| Dell          | Inspiron N5010              | [eab5331f66](https://linux-hardware.org/?probe=eab5331f66) | Jun 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDC... | [62ff10cadc](https://linux-hardware.org/?probe=62ff10cadc) | Jun 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0f0defbd9c](https://linux-hardware.org/?probe=0f0defbd9c) | Jun 29, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | [0086cae258](https://linux-hardware.org/?probe=0086cae258) | Jun 29, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [de699b13ba](https://linux-hardware.org/?probe=de699b13ba) | Jun 28, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [5d30ae9d05](https://linux-hardware.org/?probe=5d30ae9d05) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6a29eda577](https://linux-hardware.org/?probe=6a29eda577) | Jun 28, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bf4abd6e9e](https://linux-hardware.org/?probe=bf4abd6e9e) | Jun 28, 2023 |
| Dell          | Inspiron 3543               | [4baea798b1](https://linux-hardware.org/?probe=4baea798b1) | Jun 27, 2023 |
| Acer          | Swift SFG14-71              | [f66ac636e6](https://linux-hardware.org/?probe=f66ac636e6) | Jun 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [fc7f2b378b](https://linux-hardware.org/?probe=fc7f2b378b) | Jun 27, 2023 |
| Dell          | Inspiron 1545               | [d6b3d5cb90](https://linux-hardware.org/?probe=d6b3d5cb90) | Jun 27, 2023 |
| Acer          | Aspire A715-51G             | [08ba4bf92b](https://linux-hardware.org/?probe=08ba4bf92b) | Jun 26, 2023 |
| Acer          | Aspire A715-51G             | [3dc15705c8](https://linux-hardware.org/?probe=3dc15705c8) | Jun 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA    | [8a764f6629](https://linux-hardware.org/?probe=8a764f6629) | Jun 26, 2023 |
| HP            | Laptop 14s-dq2xxx           | [23499b1838](https://linux-hardware.org/?probe=23499b1838) | Jun 25, 2023 |
| Acer          | Aspire E5-575G              | [2f5357533f](https://linux-hardware.org/?probe=2f5357533f) | Jun 25, 2023 |
| Lenovo        | E41-55 82FJ                 | [f725e1bd1a](https://linux-hardware.org/?probe=f725e1bd1a) | Jun 25, 2023 |
| Dell          | Precision M6400             | [b68c09e274](https://linux-hardware.org/?probe=b68c09e274) | Jun 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | [14cc9e067f](https://linux-hardware.org/?probe=14cc9e067f) | Jun 25, 2023 |
| Dell          | Precision 5540              | [7d6c1fe39d](https://linux-hardware.org/?probe=7d6c1fe39d) | Jun 25, 2023 |
| Dell          | Inspiron 1545               | [7f8217bce2](https://linux-hardware.org/?probe=7f8217bce2) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [5679200535](https://linux-hardware.org/?probe=5679200535) | Jun 24, 2023 |
| Dell          | Vostro 2520                 | [9279842ec3](https://linux-hardware.org/?probe=9279842ec3) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [628fca0448](https://linux-hardware.org/?probe=628fca0448) | Jun 24, 2023 |
| Dell          | Inspiron 15 3515            | [77473ea84c](https://linux-hardware.org/?probe=77473ea84c) | Jun 24, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [de0580cf77](https://linux-hardware.org/?probe=de0580cf77) | Jun 24, 2023 |
| HP            | Pavilion g6                 | [b8d79ce295](https://linux-hardware.org/?probe=b8d79ce295) | Jun 24, 2023 |
| Dell          | G5 5505                     | [dbe52869d7](https://linux-hardware.org/?probe=dbe52869d7) | Jun 23, 2023 |
| Lenovo        | G500s 20245                 | [515f5a5392](https://linux-hardware.org/?probe=515f5a5392) | Jun 23, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [15fd4078ea](https://linux-hardware.org/?probe=15fd4078ea) | Jun 23, 2023 |
| Lenovo        | G500s 20245                 | [4d9c9f9bd0](https://linux-hardware.org/?probe=4d9c9f9bd0) | Jun 23, 2023 |
| Dell          | G5 5505                     | [f435440e91](https://linux-hardware.org/?probe=f435440e91) | Jun 23, 2023 |
| Acer          | Aspire E5-575G              | [5c76172491](https://linux-hardware.org/?probe=5c76172491) | Jun 22, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | [110c366456](https://linux-hardware.org/?probe=110c366456) | Jun 22, 2023 |
| HP            | 250 G6 Notebook PC          | [7cc301b3f7](https://linux-hardware.org/?probe=7cc301b3f7) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | [baab7764b1](https://linux-hardware.org/?probe=baab7764b1) | Jun 21, 2023 |
| Acer          | Aspire R3-131T              | [ab7c961e2b](https://linux-hardware.org/?probe=ab7c961e2b) | Jun 21, 2023 |
| HP            | 250 G6 Notebook PC          | [1ba2e18bc1](https://linux-hardware.org/?probe=1ba2e18bc1) | Jun 21, 2023 |
| MSI           | Bravo 15 B5DD               | [c80413d259](https://linux-hardware.org/?probe=c80413d259) | Jun 21, 2023 |
| Dell          | Inspiron 3558               | [3375eaaeb3](https://linux-hardware.org/?probe=3375eaaeb3) | Jun 20, 2023 |
| Dell          | Precision 5560              | [ee53248c8c](https://linux-hardware.org/?probe=ee53248c8c) | Jun 20, 2023 |
| Lenovo        | ThinkPad T460s 20F9005BU... | [59a527c934](https://linux-hardware.org/?probe=59a527c934) | Jun 20, 2023 |
| Timi          | RedmiBook 15                | [f975205ebd](https://linux-hardware.org/?probe=f975205ebd) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [6dea148dd7](https://linux-hardware.org/?probe=6dea148dd7) | Jun 19, 2023 |
| Dell          | Inspiron 3501               | [63381e724a](https://linux-hardware.org/?probe=63381e724a) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| HP            | ProBook 440 G4              | [4b20fef62f](https://linux-hardware.org/?probe=4b20fef62f) | Jun 19, 2023 |
| Dell          | Vostro 1015                 | [e195f838c3](https://linux-hardware.org/?probe=e195f838c3) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [4907b6927a](https://linux-hardware.org/?probe=4907b6927a) | Jun 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [edd82d072b](https://linux-hardware.org/?probe=edd82d072b) | Jun 16, 2023 |
| HP            | EliteBook 2540p             | [20ddd7a28b](https://linux-hardware.org/?probe=20ddd7a28b) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| Dell          | Inspiron 15-3567            | [69048c54c9](https://linux-hardware.org/?probe=69048c54c9) | Jun 14, 2023 |
| HP            | ProBook 430 G4              | [fe39c9b2ce](https://linux-hardware.org/?probe=fe39c9b2ce) | Jun 14, 2023 |
| HP            | ProBook 430 G4              | [2b4d088695](https://linux-hardware.org/?probe=2b4d088695) | Jun 14, 2023 |
| Lenovo        | E41-25 81FS                 | [fffb0a25f1](https://linux-hardware.org/?probe=fffb0a25f1) | Jun 13, 2023 |
| Dell          | Vostro 3420                 | [1ede32fb28](https://linux-hardware.org/?probe=1ede32fb28) | Jun 13, 2023 |
| Dell          | XPS 17 9710                 | [9ab7a065c4](https://linux-hardware.org/?probe=9ab7a065c4) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [5e636c4693](https://linux-hardware.org/?probe=5e636c4693) | Jun 13, 2023 |
| Acer          | Aspire ES1-572              | [e6713db4c3](https://linux-hardware.org/?probe=e6713db4c3) | Jun 12, 2023 |
| Lenovo        | E41-25 81FS                 | [a192769f1b](https://linux-hardware.org/?probe=a192769f1b) | Jun 11, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [66aa96212a](https://linux-hardware.org/?probe=66aa96212a) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1d46e48d92](https://linux-hardware.org/?probe=1d46e48d92) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [1eeb12a5ca](https://linux-hardware.org/?probe=1eeb12a5ca) | Jun 10, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [e46f2fe66e](https://linux-hardware.org/?probe=e46f2fe66e) | Jun 10, 2023 |
| HP            | G42                         | [83eca37118](https://linux-hardware.org/?probe=83eca37118) | Jun 10, 2023 |
| HP            | Laptop 15-db0xxx            | [5dd8c1fed8](https://linux-hardware.org/?probe=5dd8c1fed8) | Jun 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| Valve         | Jupiter                     | [b23bc1dc48](https://linux-hardware.org/?probe=b23bc1dc48) | Jun 08, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [fb6aca39d9](https://linux-hardware.org/?probe=fb6aca39d9) | Jun 08, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [e103817b2d](https://linux-hardware.org/?probe=e103817b2d) | Jun 07, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [6062ee64a9](https://linux-hardware.org/?probe=6062ee64a9) | Jun 07, 2023 |
| Dell          | G15 5511                    | [ddee46cbfa](https://linux-hardware.org/?probe=ddee46cbfa) | Jun 07, 2023 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [721ff5908a](https://linux-hardware.org/?probe=721ff5908a) | Jun 06, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Dell          | Latitude E6430              | [bfa5da5406](https://linux-hardware.org/?probe=bfa5da5406) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [1e5a50fa47](https://linux-hardware.org/?probe=1e5a50fa47) | Jun 06, 2023 |
| Acer          | Aspire A314-36M             | [7cab0d1591](https://linux-hardware.org/?probe=7cab0d1591) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [503bc1f4cc](https://linux-hardware.org/?probe=503bc1f4cc) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [31a814cd0e](https://linux-hardware.org/?probe=31a814cd0e) | Jun 06, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [2a612dc748](https://linux-hardware.org/?probe=2a612dc748) | Jun 06, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [5159be9e2b](https://linux-hardware.org/?probe=5159be9e2b) | Jun 06, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Sony          | VPCEH25EN                   | [2b47c1b9a5](https://linux-hardware.org/?probe=2b47c1b9a5) | Jun 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [6528b4bffe](https://linux-hardware.org/?probe=6528b4bffe) | Jun 05, 2023 |
| Dell          | Latitude 3460               | [1a92cd0779](https://linux-hardware.org/?probe=1a92cd0779) | Jun 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [dbc9b8df0b](https://linux-hardware.org/?probe=dbc9b8df0b) | Jun 05, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [ceab55a00c](https://linux-hardware.org/?probe=ceab55a00c) | Jun 05, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| AVITA         | NS14A8                      | [a576b4d5cc](https://linux-hardware.org/?probe=a576b4d5cc) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [87b33e1181](https://linux-hardware.org/?probe=87b33e1181) | Jun 04, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [1e4ffa48ce](https://linux-hardware.org/?probe=1e4ffa48ce) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [e86a159ec5](https://linux-hardware.org/?probe=e86a159ec5) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [01cd20c83d](https://linux-hardware.org/?probe=01cd20c83d) | Jun 03, 2023 |
| Dell          | Inspiron 5490               | [a0cc355293](https://linux-hardware.org/?probe=a0cc355293) | Jun 03, 2023 |
| Acer          | Aspire ES1-523              | [a080a07f52](https://linux-hardware.org/?probe=a080a07f52) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b8c8f96b56](https://linux-hardware.org/?probe=b8c8f96b56) | Jun 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [13adb1e221](https://linux-hardware.org/?probe=13adb1e221) | Jun 02, 2023 |
| Acer          | Nitro AN515-42              | [0acaadb3d1](https://linux-hardware.org/?probe=0acaadb3d1) | Jun 01, 2023 |
| HP            | ProBook 440 G4              | [af2f742bc5](https://linux-hardware.org/?probe=af2f742bc5) | Jun 01, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [b7032438d2](https://linux-hardware.org/?probe=b7032438d2) | May 31, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [2c315764a9](https://linux-hardware.org/?probe=2c315764a9) | May 31, 2023 |
| Dell          | Inspiron 5559               | [6c814f5bb5](https://linux-hardware.org/?probe=6c814f5bb5) | May 31, 2023 |
| Toshiba       | Satellite L850              | [cee0a13d3f](https://linux-hardware.org/?probe=cee0a13d3f) | May 31, 2023 |
| Dell          | Inspiron 15-3567            | [dc6256036e](https://linux-hardware.org/?probe=dc6256036e) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [7653baa0f8](https://linux-hardware.org/?probe=7653baa0f8) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [89bb5ff663](https://linux-hardware.org/?probe=89bb5ff663) | May 29, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [087565aed3](https://linux-hardware.org/?probe=087565aed3) | May 29, 2023 |
| Acer          | Aspire A515-56              | [108833c92b](https://linux-hardware.org/?probe=108833c92b) | May 29, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [c5b13d6ea2](https://linux-hardware.org/?probe=c5b13d6ea2) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| Dell          | Inspiron 3542               | [423fe90cad](https://linux-hardware.org/?probe=423fe90cad) | May 28, 2023 |
| HP            | EliteBook 840 G1            | [a1aa06298d](https://linux-hardware.org/?probe=a1aa06298d) | May 28, 2023 |
| Acer          | Aspire A515-56              | [4d8767d94b](https://linux-hardware.org/?probe=4d8767d94b) | May 28, 2023 |
| HP            | Laptop 14s-dk0xxx           | [902b837f1a](https://linux-hardware.org/?probe=902b837f1a) | May 27, 2023 |
| Dell          | Latitude 7480               | [2c74ec8198](https://linux-hardware.org/?probe=2c74ec8198) | May 27, 2023 |
| HP            | Laptop 14s-dk0xxx           | [5cf35078b0](https://linux-hardware.org/?probe=5cf35078b0) | May 26, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [0316f8d274](https://linux-hardware.org/?probe=0316f8d274) | May 25, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [270540781d](https://linux-hardware.org/?probe=270540781d) | May 25, 2023 |
| Acer          | Aspire A715-51G             | [53cbfa6255](https://linux-hardware.org/?probe=53cbfa6255) | May 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1fea1a6529](https://linux-hardware.org/?probe=1fea1a6529) | May 25, 2023 |
| Dell          | Vostro 3480                 | [490c47960a](https://linux-hardware.org/?probe=490c47960a) | May 25, 2023 |
| MSI           | GF63 Thin 9RC               | [aef2c48b64](https://linux-hardware.org/?probe=aef2c48b64) | May 24, 2023 |
| Dell          | Vostro 3480                 | [ae4f8dba2c](https://linux-hardware.org/?probe=ae4f8dba2c) | May 24, 2023 |
| Dell          | Vostro 2420                 | [ebff669275](https://linux-hardware.org/?probe=ebff669275) | May 24, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [e8bc14fc34](https://linux-hardware.org/?probe=e8bc14fc34) | May 23, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | [c5615351bb](https://linux-hardware.org/?probe=c5615351bb) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [691b17e221](https://linux-hardware.org/?probe=691b17e221) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3d4cdd163c](https://linux-hardware.org/?probe=3d4cdd163c) | May 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c3251b8c63](https://linux-hardware.org/?probe=c3251b8c63) | May 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [d704fd9efd](https://linux-hardware.org/?probe=d704fd9efd) | May 23, 2023 |
| Dell          | Inspiron 5575               | [7d93944943](https://linux-hardware.org/?probe=7d93944943) | May 23, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [33773ecf4d](https://linux-hardware.org/?probe=33773ecf4d) | May 22, 2023 |
| Lenovo        | ThinkPad T490s 20NYS7K91... | [7d81e00b27](https://linux-hardware.org/?probe=7d81e00b27) | May 22, 2023 |
| Lenovo        | ThinkPad T440p              | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro9,2               | [88d77ec57e](https://linux-hardware.org/?probe=88d77ec57e) | May 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [59464cac80](https://linux-hardware.org/?probe=59464cac80) | May 20, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [ff730fcbf6](https://linux-hardware.org/?probe=ff730fcbf6) | May 20, 2023 |
| Apple         | MacBookAir7,2               | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| HP            | Laptop 15s-dr3xxx           | [4c44db2d32](https://linux-hardware.org/?probe=4c44db2d32) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [b0ed659e7d](https://linux-hardware.org/?probe=b0ed659e7d) | May 19, 2023 |
| Dell          | Inspiron 14 5408            | [c1853f7df2](https://linux-hardware.org/?probe=c1853f7df2) | May 17, 2023 |
| HP            | Pavilion g6                 | [da7af17667](https://linux-hardware.org/?probe=da7af17667) | May 17, 2023 |
| HP            | Laptop 15s-du0xxx           | [ddc3152cbc](https://linux-hardware.org/?probe=ddc3152cbc) | May 17, 2023 |
| MSI           | GF63 Thin 9RC               | [b8f2e92853](https://linux-hardware.org/?probe=b8f2e92853) | May 16, 2023 |
| Dell          | XPS 13 9350                 | [3e34d3a71c](https://linux-hardware.org/?probe=3e34d3a71c) | May 15, 2023 |
| HP            | Laptop 14s-dk0xxx           | [000f3c2444](https://linux-hardware.org/?probe=000f3c2444) | May 15, 2023 |
| HONOR         | NMH-WCX9                    | [b938ce8d64](https://linux-hardware.org/?probe=b938ce8d64) | May 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [fb4bda01b7](https://linux-hardware.org/?probe=fb4bda01b7) | May 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0060b3cb1c](https://linux-hardware.org/?probe=0060b3cb1c) | May 14, 2023 |
| Lenovo        | E41-25 81FS                 | [b9e5026a6a](https://linux-hardware.org/?probe=b9e5026a6a) | May 14, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [4a322b398b](https://linux-hardware.org/?probe=4a322b398b) | May 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TAS... | [d251ccd249](https://linux-hardware.org/?probe=d251ccd249) | May 13, 2023 |
| Dell          | Inspiron 7520               | [d06731c12e](https://linux-hardware.org/?probe=d06731c12e) | May 13, 2023 |
| Dell          | G3 3590                     | [696d2d38df](https://linux-hardware.org/?probe=696d2d38df) | May 13, 2023 |
| AVITA         | NS14A6                      | [253f084ba1](https://linux-hardware.org/?probe=253f084ba1) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c9597b5b24](https://linux-hardware.org/?probe=c9597b5b24) | May 11, 2023 |
| Dell          | Latitude E5470              | [59c95182ec](https://linux-hardware.org/?probe=59c95182ec) | May 11, 2023 |
| AVITA         | NS14A6                      | [d2cdbff22c](https://linux-hardware.org/?probe=d2cdbff22c) | May 11, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [328d899b1c](https://linux-hardware.org/?probe=328d899b1c) | May 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [601a09abf6](https://linux-hardware.org/?probe=601a09abf6) | May 10, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | [0308c5d0c5](https://linux-hardware.org/?probe=0308c5d0c5) | May 10, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [d2d1037c9d](https://linux-hardware.org/?probe=d2d1037c9d) | May 09, 2023 |
| Dell          | Latitude 3490               | [f9ed2aa5ab](https://linux-hardware.org/?probe=f9ed2aa5ab) | May 09, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [745096932c](https://linux-hardware.org/?probe=745096932c) | May 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [dfe5f362e2](https://linux-hardware.org/?probe=dfe5f362e2) | May 09, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [cbc45e8ffa](https://linux-hardware.org/?probe=cbc45e8ffa) | May 09, 2023 |
| HP            | Laptop 15-da1xxx            | [e1313af3e6](https://linux-hardware.org/?probe=e1313af3e6) | May 08, 2023 |
| Acer          | Aspire A315-53              | [c74bb83ac9](https://linux-hardware.org/?probe=c74bb83ac9) | May 08, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [f5acf4a186](https://linux-hardware.org/?probe=f5acf4a186) | May 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7e003cf7a9](https://linux-hardware.org/?probe=7e003cf7a9) | May 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b1b0fa7485](https://linux-hardware.org/?probe=b1b0fa7485) | May 07, 2023 |
| Dell          | Vostro 15-3568              | [08b1152328](https://linux-hardware.org/?probe=08b1152328) | May 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [741b9f90e1](https://linux-hardware.org/?probe=741b9f90e1) | May 07, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [1dbc92c072](https://linux-hardware.org/?probe=1dbc92c072) | May 07, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [845c2112be](https://linux-hardware.org/?probe=845c2112be) | May 06, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [3569e8fb31](https://linux-hardware.org/?probe=3569e8fb31) | May 06, 2023 |
| Dell          | Inspiron 3537               | [5b49eec8c6](https://linux-hardware.org/?probe=5b49eec8c6) | May 06, 2023 |
| HP            | EliteBook Folio 9470m       | [20461b100d](https://linux-hardware.org/?probe=20461b100d) | May 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [834d2304aa](https://linux-hardware.org/?probe=834d2304aa) | May 06, 2023 |
| HP            | Laptop 15-db1xxx            | [dd6f6a940f](https://linux-hardware.org/?probe=dd6f6a940f) | May 05, 2023 |
| HP            | Laptop 15-db1xxx            | [c7b66fbdc3](https://linux-hardware.org/?probe=c7b66fbdc3) | May 05, 2023 |
| Acer          | Aspire E5-576               | [a73b11b28f](https://linux-hardware.org/?probe=a73b11b28f) | May 05, 2023 |
| HP            | ProBook 440 G5              | [f6251eeeb1](https://linux-hardware.org/?probe=f6251eeeb1) | May 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS0SE00     | [c5d4b5a3a7](https://linux-hardware.org/?probe=c5d4b5a3a7) | May 05, 2023 |
| Sony          | SVE15117FNW                 | [7ec421e4a1](https://linux-hardware.org/?probe=7ec421e4a1) | May 04, 2023 |
| Dell          | Inspiron 1545               | [e60b96481a](https://linux-hardware.org/?probe=e60b96481a) | May 04, 2023 |
| Gateway       | NE46R                       | [05291d9029](https://linux-hardware.org/?probe=05291d9029) | May 04, 2023 |
| Dell          | Latitude 5490               | [2ce70b7a2c](https://linux-hardware.org/?probe=2ce70b7a2c) | May 04, 2023 |
| HP            | ProBook 440 G4              | [ac499d5a17](https://linux-hardware.org/?probe=ac499d5a17) | May 04, 2023 |
| Dell          | Latitude 5480               | [a8b85d06d8](https://linux-hardware.org/?probe=a8b85d06d8) | May 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [530aaeef9d](https://linux-hardware.org/?probe=530aaeef9d) | May 02, 2023 |
| Dell          | Inspiron 1564               | [e94ef67ab2](https://linux-hardware.org/?probe=e94ef67ab2) | May 01, 2023 |
| Dell          | Inspiron 14 5420            | [cc65b3de6f](https://linux-hardware.org/?probe=cc65b3de6f) | May 01, 2023 |
| Acer          | Aspire A715-51G             | [842333a8da](https://linux-hardware.org/?probe=842333a8da) | May 01, 2023 |
| Acer          | Aspire A715-51G             | [4f72daaab8](https://linux-hardware.org/?probe=4f72daaab8) | May 01, 2023 |
| Dell          | Latitude E5420              | [df8c9e7f40](https://linux-hardware.org/?probe=df8c9e7f40) | Apr 30, 2023 |
| Apple         | MacBook5,1                  | [7077a00b02](https://linux-hardware.org/?probe=7077a00b02) | Apr 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [446a548122](https://linux-hardware.org/?probe=446a548122) | Apr 30, 2023 |
| Dell          | Inspiron N5110              | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| Acer          | Nitro AN515-58              | [2c335c5bfb](https://linux-hardware.org/?probe=2c335c5bfb) | Apr 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [0ea5e1926e](https://linux-hardware.org/?probe=0ea5e1926e) | Apr 29, 2023 |
| Dell          | Latitude E5470              | [c6c943679f](https://linux-hardware.org/?probe=c6c943679f) | Apr 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [216a4b9b67](https://linux-hardware.org/?probe=216a4b9b67) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [6736f3d911](https://linux-hardware.org/?probe=6736f3d911) | Apr 28, 2023 |
| Acer          | Swift SF314-512             | [2ba1bab0fe](https://linux-hardware.org/?probe=2ba1bab0fe) | Apr 28, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | [65f390b956](https://linux-hardware.org/?probe=65f390b956) | Apr 28, 2023 |
| Acer          | Nitro AN515-54              | [000022b2dd](https://linux-hardware.org/?probe=000022b2dd) | Apr 28, 2023 |
| MSI           | Modern 14 C7M               | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Dell          | Inspiron 1545               | [a23cf53cec](https://linux-hardware.org/?probe=a23cf53cec) | Apr 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | [4bdb6b2a7f](https://linux-hardware.org/?probe=4bdb6b2a7f) | Apr 27, 2023 |
| Dell          | Vostro 1550                 | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| Valve         | Jupiter                     | [7ab7e066cf](https://linux-hardware.org/?probe=7ab7e066cf) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430s 23539MU      | [83a1144be6](https://linux-hardware.org/?probe=83a1144be6) | Apr 26, 2023 |
| HP            | EliteBook Folio 9470m       | [e0d69966e9](https://linux-hardware.org/?probe=e0d69966e9) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [ab52633e07](https://linux-hardware.org/?probe=ab52633e07) | Apr 26, 2023 |
| Timi          | Mi NoteBook Ultra           | [b6b7cdfe22](https://linux-hardware.org/?probe=b6b7cdfe22) | Apr 25, 2023 |
| Lenovo        | ThinkPad E14 20RAS1DB00     | [8e09a153f5](https://linux-hardware.org/?probe=8e09a153f5) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | [45199e8296](https://linux-hardware.org/?probe=45199e8296) | Apr 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [2787d97e6e](https://linux-hardware.org/?probe=2787d97e6e) | Apr 24, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [8bfea5add2](https://linux-hardware.org/?probe=8bfea5add2) | Apr 24, 2023 |
| HP            | G42                         | [58b0a0981e](https://linux-hardware.org/?probe=58b0a0981e) | Apr 23, 2023 |
| HP            | Laptop 15s-du3xxx           | [45af810de1](https://linux-hardware.org/?probe=45af810de1) | Apr 21, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [888b7bed45](https://linux-hardware.org/?probe=888b7bed45) | Apr 21, 2023 |
| Lenovo        | IdeaPad S540-15IWL          | [8578f44f47](https://linux-hardware.org/?probe=8578f44f47) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | [91999697ba](https://linux-hardware.org/?probe=91999697ba) | Apr 20, 2023 |
| Acer          | Aspire 5745                 | [19e6d70ce0](https://linux-hardware.org/?probe=19e6d70ce0) | Apr 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AHS... | [59d7ef5ddd](https://linux-hardware.org/?probe=59d7ef5ddd) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | [46ade409df](https://linux-hardware.org/?probe=46ade409df) | Apr 20, 2023 |
| Acer          | Aspire A715-42G             | [954388c5e0](https://linux-hardware.org/?probe=954388c5e0) | Apr 19, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WX0W    | [97447a0777](https://linux-hardware.org/?probe=97447a0777) | Apr 19, 2023 |
| HP            | Pavilion 15                 | [3a855386b4](https://linux-hardware.org/?probe=3a855386b4) | Apr 18, 2023 |
| MSI           | GP65 Leopard 10SEK          | [3b852bad57](https://linux-hardware.org/?probe=3b852bad57) | Apr 18, 2023 |
| Lenovo        | E41-25 81FS                 | [10bfabc1b8](https://linux-hardware.org/?probe=10bfabc1b8) | Apr 18, 2023 |
| HP            | 630                         | [daeae9f12e](https://linux-hardware.org/?probe=daeae9f12e) | Apr 18, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [9be6e0f395](https://linux-hardware.org/?probe=9be6e0f395) | Apr 18, 2023 |
| HP            | Laptop 15-da0xxx            | [d1d3cf9928](https://linux-hardware.org/?probe=d1d3cf9928) | Apr 17, 2023 |
| HP            | Laptop 15-da0xxx            | [786daebed0](https://linux-hardware.org/?probe=786daebed0) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| Dell          | Vostro 3580                 | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [0dfc78d12a](https://linux-hardware.org/?probe=0dfc78d12a) | Apr 15, 2023 |
| Apple         | MacBookPro16,1              | [bc7d49c64c](https://linux-hardware.org/?probe=bc7d49c64c) | Apr 15, 2023 |
| Acer          | AO756                       | [c17d5276ec](https://linux-hardware.org/?probe=c17d5276ec) | Apr 14, 2023 |
| Acer          | Aspire A515-57G             | [42e4889a44](https://linux-hardware.org/?probe=42e4889a44) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | [0d0ff5240b](https://linux-hardware.org/?probe=0d0ff5240b) | Apr 12, 2023 |
| ASUSTek       | K53U                        | [19ec753136](https://linux-hardware.org/?probe=19ec753136) | Apr 12, 2023 |
| Dell          | Precision 5520              | [32eb960b25](https://linux-hardware.org/?probe=32eb960b25) | Apr 12, 2023 |
| MSI           | GF63 Thin 9SCXR             | [3225aa17d2](https://linux-hardware.org/?probe=3225aa17d2) | Apr 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [40c7ac46e2](https://linux-hardware.org/?probe=40c7ac46e2) | Apr 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b9d22dfaea](https://linux-hardware.org/?probe=b9d22dfaea) | Apr 10, 2023 |
| HP            | Pavilion Sleekbook 15 PC    | [0bbe9702ca](https://linux-hardware.org/?probe=0bbe9702ca) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [c82c56c81e](https://linux-hardware.org/?probe=c82c56c81e) | Apr 09, 2023 |
| Dell          | Latitude 7275               | [d1a55f8f55](https://linux-hardware.org/?probe=d1a55f8f55) | Apr 09, 2023 |
| HONOR         | NMH-WCX9                    | [51c8f59aeb](https://linux-hardware.org/?probe=51c8f59aeb) | Apr 08, 2023 |
| Dell          | Latitude 3410               | [9fd7d9d439](https://linux-hardware.org/?probe=9fd7d9d439) | Apr 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [133568abf2](https://linux-hardware.org/?probe=133568abf2) | Apr 07, 2023 |
| ASUSTek       | K54C                        | [4f37849c94](https://linux-hardware.org/?probe=4f37849c94) | Apr 07, 2023 |
| Apple         | MacBookPro9,2               | [f29d8154a2](https://linux-hardware.org/?probe=f29d8154a2) | Apr 06, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [fef3cbc941](https://linux-hardware.org/?probe=fef3cbc941) | Apr 05, 2023 |
| Valve         | Jupiter                     | [8425bb5da3](https://linux-hardware.org/?probe=8425bb5da3) | Apr 04, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [d56565f374](https://linux-hardware.org/?probe=d56565f374) | Apr 04, 2023 |
| Dell          | Latitude E6420              | [b35bf27d28](https://linux-hardware.org/?probe=b35bf27d28) | Apr 04, 2023 |
| HP            | 1000                        | [111c9bd980](https://linux-hardware.org/?probe=111c9bd980) | Apr 04, 2023 |
| Unknown       | Unknown                     | [7325272558](https://linux-hardware.org/?probe=7325272558) | Apr 04, 2023 |
| Lenovo        | Unknown                     | [4216d2969c](https://linux-hardware.org/?probe=4216d2969c) | Apr 04, 2023 |
| Gateway       | NE56R                       | [ffa6b1d3f3](https://linux-hardware.org/?probe=ffa6b1d3f3) | Apr 03, 2023 |
| Lenovo        | ThinkPad E14 20RAS1RA00     | [6ace928ea5](https://linux-hardware.org/?probe=6ace928ea5) | Apr 03, 2023 |
| Lenovo        | Flex 2-14 20404             | [cc341f3faf](https://linux-hardware.org/?probe=cc341f3faf) | Apr 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Lenovo        | ThinkPad E14 20RAS0D800     | [ea2f5b484f](https://linux-hardware.org/?probe=ea2f5b484f) | Apr 02, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [d018871b72](https://linux-hardware.org/?probe=d018871b72) | Apr 02, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/India/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 729       | 18.82%  |
| Ubuntu 22.04                 | 317       | 8.18%   |
| Ubuntu 18.04                 | 277       | 7.15%   |
| Arch Rolling                 | 114       | 2.94%   |
| Pop!_OS 22.04                | 89        | 2.3%    |
| Arch                         | 80        | 2.07%   |
| Fedora 38                    | 74        | 1.91%   |
| Zorin 16                     | 72        | 1.86%   |
| ArcoLinux Rolling            | 58        | 1.5%    |
| KDE neon 20.04               | 56        | 1.45%   |
| Pop!_OS 20.04                | 54        | 1.39%   |
| Fedora 36                    | 54        | 1.39%   |
| Fedora 37                    | 53        | 1.37%   |
| Pop!_OS 21.04                | 49        | 1.27%   |
| Ubuntu 20.10                 | 46        | 1.19%   |
| Fedora 34                    | 45        | 1.16%   |
| Ubuntu 19.10                 | 39        | 1.01%   |
| Zorin 15                     | 38        | 0.98%   |
| Ubuntu 21.04                 | 38        | 0.98%   |
| Pop!_OS 20.10                | 36        | 0.93%   |
| Manjaro                      | 36        | 0.93%   |
| Fedora 39                    | 35        | 0.9%    |
| OpenMandriva 4.2             | 33        | 0.85%   |
| Ubuntu 19.04                 | 32        | 0.83%   |
| Fedora 35                    | 32        | 0.83%   |
| Debian 11                    | 31        | 0.8%    |
| Ubuntu 23.04                 | 30        | 0.77%   |
| OpenMandriva 4.3             | 30        | 0.77%   |
| Linux Mint 21.1              | 30        | 0.77%   |
| Ubuntu 21.10                 | 29        | 0.75%   |
| Linux Mint 20.2              | 26        | 0.67%   |
| Fedora 32                    | 26        | 0.67%   |
| EndeavourOS Rolling          | 26        | 0.67%   |
| Ubuntu Unity 16.04           | 25        | 0.65%   |
| Linux Mint 20.3              | 25        | 0.65%   |
| Linux Mint 20.1              | 25        | 0.65%   |
| Fedora 33                    | 25        | 0.65%   |
| openSUSE Tumbleweed-XXXXXXXX | 24        | 0.62%   |
| Linux Mint 21.2              | 24        | 0.62%   |
| Xero Rolling                 | 23        | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1562      | 41.97%  |
| Fedora        | 334       | 8.97%   |
| Pop!_OS       | 236       | 6.34%   |
| Arch          | 187       | 5.02%   |
| Linux Mint    | 175       | 4.7%    |
| OpenMandriva  | 128       | 3.44%   |
| Zorin         | 114       | 3.06%   |
| Manjaro       | 106       | 2.85%   |
| Debian        | 86        | 2.31%   |
| KDE neon      | 84        | 2.26%   |
| Kali          | 80        | 2.15%   |
| Kubuntu       | 68        | 1.83%   |
| ArcoLinux     | 64        | 1.72%   |
| Elementary    | 48        | 1.29%   |
| Ubuntu Unity  | 44        | 1.18%   |
| Endless       | 37        | 0.99%   |
| openSUSE      | 31        | 0.83%   |
| EndeavourOS   | 29        | 0.78%   |
| Xubuntu       | 28        | 0.75%   |
| Garuda Linux  | 25        | 0.67%   |
| Xero          | 23        | 0.62%   |
| RHEL          | 20        | 0.54%   |
| ROSA          | 17        | 0.46%   |
| Ubuntu Budgie | 15        | 0.4%    |
| Clear Linux   | 15        | 0.4%    |
| Ubuntu MATE   | 13        | 0.35%   |
| Parrot        | 12        | 0.32%   |
| MX            | 12        | 0.32%   |
| Nobara        | 11        | 0.3%    |
| Lubuntu       | 10        | 0.27%   |
| Void Linux    | 9         | 0.24%   |
| Solus         | 8         | 0.21%   |
| CentOS        | 8         | 0.21%   |
| Gentoo        | 7         | 0.19%   |
| Artix         | 7         | 0.19%   |
| LMDE          | 6         | 0.16%   |
| Archcraft     | 5         | 0.13%   |
| Slackware     | 4         | 0.11%   |
| UbuntuDDE     | 3         | 0.08%   |
| SteamOS       | 3         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 112       | 2.69%   |
| 5.4.0-40-generic         | 54        | 1.3%    |
| 5.15.0-56-generic        | 45        | 1.08%   |
| 5.11.0-27-generic        | 34        | 0.82%   |
| 5.10.14-desktop-1omv4002 | 33        | 0.79%   |
| 5.4.0-48-generic         | 30        | 0.72%   |
| 5.4.0-26-generic         | 30        | 0.72%   |
| 6.2.0-26-generic         | 29        | 0.7%    |
| 5.4.0-47-generic         | 29        | 0.7%    |
| 5.11.0-7620-generic      | 28        | 0.67%   |
| 5.4.0-58-generic         | 27        | 0.65%   |
| 5.16.7-desktop-1omv4003  | 27        | 0.65%   |
| 5.4.0-52-generic         | 26        | 0.62%   |
| 5.4.0-29-generic         | 24        | 0.58%   |
| 5.3.0-28-generic         | 24        | 0.58%   |
| 5.15.0-58-generic        | 24        | 0.58%   |
| 5.11.0-40-generic        | 23        | 0.55%   |
| 5.4.0-45-generic         | 22        | 0.53%   |
| 5.11.0-43-generic        | 22        | 0.53%   |
| 5.11.0-25-generic        | 22        | 0.53%   |
| 5.8.0-53-generic         | 21        | 0.5%    |
| 5.8.0-44-generic         | 21        | 0.5%    |
| 5.8.0-43-generic         | 21        | 0.5%    |
| 5.15.0-52-generic        | 21        | 0.5%    |
| 5.15.0-46-generic        | 21        | 0.5%    |
| 5.11.0-38-generic        | 21        | 0.5%    |
| 5.8.0-55-generic         | 20        | 0.48%   |
| 5.8.0-48-generic         | 20        | 0.48%   |
| 5.4.0-37-generic         | 20        | 0.48%   |
| 5.3.0-40-generic         | 20        | 0.48%   |
| 6.5.0-14-generic         | 19        | 0.46%   |
| 5.4.0-74-generic         | 19        | 0.46%   |
| 5.19.0-41-generic        | 19        | 0.46%   |
| 5.13.0-30-generic        | 19        | 0.46%   |
| 5.11.0-37-generic        | 19        | 0.46%   |
| 6.2.6-desktop-1omv2390   | 18        | 0.43%   |
| 5.4.0-39-generic         | 18        | 0.43%   |
| 4.15.0-45-generic        | 18        | 0.43%   |
| 5.8.0-7630-generic       | 17        | 0.41%   |
| 5.3.0-51-generic         | 17        | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 649       | 16.21%  |
| 5.15.0  | 341       | 8.52%   |
| 5.11.0  | 261       | 6.52%   |
| 5.8.0   | 229       | 5.72%   |
| 4.15.0  | 153       | 3.82%   |
| 5.13.0  | 152       | 3.8%    |
| 5.3.0   | 144       | 3.6%    |
| 5.19.0  | 144       | 3.6%    |
| 6.2.0   | 125       | 3.12%   |
| 5.0.0   | 91        | 2.27%   |
| 4.18.0  | 65        | 1.62%   |
| 5.10.0  | 59        | 1.47%   |
| 6.5.0   | 54        | 1.35%   |
| 6.1.0   | 41        | 1.02%   |
| 6.2.6   | 34        | 0.85%   |
| 5.10.14 | 33        | 0.82%   |
| 5.16.7  | 28        | 0.7%    |
| 5.14.0  | 28        | 0.7%    |
| 4.4.0   | 19        | 0.47%   |
| 5.17.5  | 18        | 0.45%   |
| 6.0.12  | 17        | 0.42%   |
| 6.0.0   | 16        | 0.4%    |
| 6.4.11  | 15        | 0.37%   |
| 4.19.0  | 15        | 0.37%   |
| 6.6.6   | 14        | 0.35%   |
| 6.2.9   | 13        | 0.32%   |
| 6.1.1   | 13        | 0.32%   |
| 6.0.8   | 13        | 0.32%   |
| 6.5.5   | 12        | 0.3%    |
| 6.0.6   | 12        | 0.3%    |
| 6.5.9   | 11        | 0.27%   |
| 5.9.0   | 11        | 0.27%   |
| 5.7.0   | 11        | 0.27%   |
| 6.6.8   | 10        | 0.25%   |
| 6.3.5   | 10        | 0.25%   |
| 5.18.0  | 10        | 0.25%   |
| 5.15.11 | 10        | 0.25%   |
| 6.5.6   | 9         | 0.22%   |
| 6.4.12  | 9         | 0.22%   |
| 6.5.4   | 8         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 675       | 17.09%  |
| 5.15    | 440       | 11.14%  |
| 5.11    | 293       | 7.42%   |
| 5.8     | 276       | 6.99%   |
| 6.2     | 214       | 5.42%   |
| 5.13    | 192       | 4.86%   |
| 5.19    | 190       | 4.81%   |
| 5.3     | 164       | 4.15%   |
| 4.15    | 153       | 3.87%   |
| 5.10    | 147       | 3.72%   |
| 6.5     | 120       | 3.04%   |
| 6.1     | 117       | 2.96%   |
| 6.0     | 98        | 2.48%   |
| 5.0     | 93        | 2.36%   |
| 5.16    | 80        | 2.03%   |
| 6.4     | 69        | 1.75%   |
| 5.17    | 69        | 1.75%   |
| 4.18    | 68        | 1.72%   |
| 6.6     | 67        | 1.7%    |
| 5.14    | 63        | 1.6%    |
| 5.18    | 51        | 1.29%   |
| 6.3     | 48        | 1.22%   |
| 5.12    | 45        | 1.14%   |
| 5.9     | 43        | 1.09%   |
| 5.7     | 40        | 1.01%   |
| 5.6     | 27        | 0.68%   |
| 5.5     | 22        | 0.56%   |
| 4.19    | 21        | 0.53%   |
| 4.4     | 20        | 0.51%   |
| 4.9     | 11        | 0.28%   |
| 6.7     | 9         | 0.23%   |
| 5.2     | 6         | 0.15%   |
| 5.1     | 3         | 0.08%   |
| 3.16    | 3         | 0.08%   |
| 3.10    | 3         | 0.08%   |
| 4.13    | 2         | 0.05%   |
| 4.1     | 2         | 0.05%   |
| 4.20    | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 4.16    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3528      | 98.96%  |
| i686   | 36        | 1.01%   |
| armv7l | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 2186      | 58.83%  |
| KDE5              | 480       | 12.92%  |
| Unknown           | 325       | 8.75%   |
| XFCE              | 168       | 4.52%   |
| X-Cinnamon        | 149       | 4.01%   |
| KDE               | 75        | 2.02%   |
| Unity             | 46        | 1.24%   |
| Pantheon          | 46        | 1.24%   |
| MATE              | 39        | 1.05%   |
| Cinnamon          | 30        | 0.81%   |
| i3                | 27        | 0.73%   |
| Budgie            | 22        | 0.59%   |
| GNOME Flashback   | 21        | 0.57%   |
| LXQt              | 15        | 0.4%    |
| LXDE              | 12        | 0.32%   |
| Deepin            | 10        | 0.27%   |
| awesome           | 9         | 0.24%   |
| qtile             | 8         | 0.22%   |
| KDE4              | 7         | 0.19%   |
| Hyprland          | 7         | 0.19%   |
| bspwm             | 7         | 0.19%   |
| sway              | 4         | 0.11%   |
| LeftWM            | 4         | 0.11%   |
| openbox           | 3         | 0.08%   |
| dwm               | 3         | 0.08%   |
| xmonad            | 2         | 0.05%   |
| lightdm-xsession  | 2         | 0.05%   |
| GNOME Classic     | 2         | 0.05%   |
| Yaru:ubuntu:GNOME | 1         | 0.03%   |
| xinitrc           | 1         | 0.03%   |
| i3-with-shmlog    | 1         | 0.03%   |
| i3-gaps           | 1         | 0.03%   |
| herbstluftwm      | 1         | 0.03%   |
| Endless:GNOME     | 1         | 0.03%   |
| chadwm            | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2576      | 69.79%  |
| Wayland | 857       | 23.22%  |
| Unknown | 214       | 5.8%    |
| Tty     | 44        | 1.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1700      | 45.88%  |
| GDM     | 661       | 17.84%  |
| GDM3    | 544       | 14.68%  |
| SDDM    | 426       | 11.5%   |
| LightDM | 271       | 7.31%   |
| TDM     | 79        | 2.13%   |
| XDM     | 9         | 0.24%   |
| KDM     | 6         | 0.16%   |
| LXDM    | 4         | 0.11%   |
| SLiM    | 2         | 0.05%   |
| Ly      | 2         | 0.05%   |
| LY-DM   | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang             | Notebooks | Percent |
|------------------|-----------|---------|
| en_IN            | 2208      | 59.64%  |
| en_US            | 1071      | 28.93%  |
| Unknown          | 258       | 6.97%   |
| en_GB            | 68        | 1.84%   |
| C                | 65        | 1.76%   |
| en_AG            | 8         | 0.22%   |
| POSIX            | 3         | 0.08%   |
| en_CA            | 3         | 0.08%   |
| zh_TW            | 2         | 0.05%   |
| mr_IN            | 2         | 0.05%   |
| en_IE            | 2         | 0.05%   |
| en_AU            | 2         | 0.05%   |
| pl_PL            | 1         | 0.03%   |
| ks_IN            | 1         | 0.03%   |
| es_ES            | 1         | 0.03%   |
| en_US.ISO-8859-1 | 1         | 0.03%   |
| en_SG            | 1         | 0.03%   |
| en_HK            | 1         | 0.03%   |
| en_BW            | 1         | 0.03%   |
| Default          | 1         | 0.03%   |
| C.UTF8           | 1         | 0.03%   |
| aa_DJ            | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2294      | 63.09%  |
| BIOS | 1342      | 36.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2854      | 77.64%  |
| Btrfs   | 422       | 11.48%  |
| Overlay | 151       | 4.11%   |
| Tmpfs   | 103       | 2.8%    |
| Unknown | 59        | 1.61%   |
| Xfs     | 45        | 1.22%   |
| Zfs     | 17        | 0.46%   |
| F2fs    | 11        | 0.3%    |
| Ext2    | 7         | 0.19%   |
| Ext3    | 6         | 0.16%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1779      | 48.83%  |
| GPT     | 1609      | 44.17%  |
| MBR     | 255       | 7%      |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3193      | 88.08%  |
| Yes       | 432       | 11.92%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2181      | 60.27%  |
| Yes       | 1438      | 39.73%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 852       | 23.91%  |
| Hewlett-Packard                | 801       | 22.47%  |
| Dell                           | 778       | 21.83%  |
| ASUSTek Computer               | 452       | 12.68%  |
| Acer                           | 296       | 8.31%   |
| MSI                            | 62        | 1.74%   |
| Sony                           | 51        | 1.43%   |
| Timi                           | 37        | 1.04%   |
| Toshiba                        | 36        | 1.01%   |
| Apple                          | 31        | 0.87%   |
| Samsung Electronics            | 27        | 0.76%   |
| AVITA                          | 21        | 0.59%   |
| Infinix                        | 14        | 0.39%   |
| HONOR                          | 10        | 0.28%   |
| HCL Infosystems Limited        | 9         | 0.25%   |
| Fujitsu                        | 9         | 0.25%   |
| HUAWEI                         | 8         | 0.22%   |
| LG Electronics                 | 6         | 0.17%   |
| Google                         | 6         | 0.17%   |
| Alienware                      | 6         | 0.17%   |
| Intel                          | 5         | 0.14%   |
| Gateway                        | 5         | 0.14%   |
| Unknown                        | 5         | 0.14%   |
| realme                         | 4         | 0.11%   |
| eMachines                      | 4         | 0.11%   |
| Valve                          | 3         | 0.08%   |
| Razer                          | 2         | 0.06%   |
| Micromax                       | 2         | 0.06%   |
| ITI LIMITED                    | 2         | 0.06%   |
| Dynabook                       | 2         | 0.06%   |
| Coconics Private Limited       | 2         | 0.06%   |
| WIPRO                          | 1         | 0.03%   |
| System76                       | 1         | 0.03%   |
| SmbiosType1_SystemManufacturer | 1         | 0.03%   |
| RDP                            | 1         | 0.03%   |
| ONDA                           | 1         | 0.03%   |
| Notebook                       | 1         | 0.03%   |
| NEC Computers                  | 1         | 0.03%   |
| iBall                          | 1         | 0.03%   |
| HASEE Computer                 | 1         | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP Notebook                          | 83        | 2.33%   |
| HP 15                                | 35        | 0.98%   |
| HP Pavilion 15                       | 32        | 0.9%    |
| HP Pavilion g6                       | 29        | 0.81%   |
| Dell Inspiron 3542                   | 29        | 0.81%   |
| Lenovo E41-25 81FS                   | 23        | 0.65%   |
| HP Laptop 15-bs0xx                   | 22        | 0.62%   |
| Dell Inspiron 15-3567                | 22        | 0.62%   |
| Dell Inspiron 5570                   | 20        | 0.56%   |
| Unknown                              | 20        | 0.56%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 19        | 0.53%   |
| Dell Inspiron 3521                   | 19        | 0.53%   |
| HP Pavilion Notebook                 | 18        | 0.51%   |
| ASUS TUF Gaming FX505DT_FX505DT      | 18        | 0.51%   |
| Acer Aspire A715-75G                 | 17        | 0.48%   |
| Lenovo G50-80 80E5                   | 16        | 0.45%   |
| Dell Vostro 15-3568                  | 16        | 0.45%   |
| Dell Vostro 3480                     | 15        | 0.42%   |
| Lenovo IdeaPad 320-15ISK 80XH        | 14        | 0.39%   |
| HP Pavilion Gaming Laptop 15-ec2xxx  | 14        | 0.39%   |
| HP Laptop 15-da0xxx                  | 14        | 0.39%   |
| Timi Mi NoteBook Ultra               | 13        | 0.36%   |
| Dell Vostro 3578                     | 13        | 0.36%   |
| Dell Inspiron 5559                   | 13        | 0.36%   |
| Dell Inspiron 1545                   | 13        | 0.36%   |
| Lenovo G50-45 80E3                   | 12        | 0.34%   |
| HP Pavilion Laptop 14-dv0xxx         | 12        | 0.34%   |
| Dell Inspiron N5010                  | 12        | 0.34%   |
| ASUS X510UNR                         | 12        | 0.34%   |
| ASUS VivoBook 15_ASUS Laptop X507UAR | 12        | 0.34%   |
| HP Laptop 15-bw0xx                   | 11        | 0.31%   |
| ASUS TUF Gaming FX505DY_FX505DY      | 11        | 0.31%   |
| Lenovo IdeaPad S540-15IWL D 81NE     | 10        | 0.28%   |
| Lenovo IdeaPad 320-15IKB 80XL        | 10        | 0.28%   |
| HP Pavilion Gaming Laptop 15-ec0xxx  | 10        | 0.28%   |
| HP Pavilion dv6                      | 10        | 0.28%   |
| HP EliteBook 840 G1                  | 10        | 0.28%   |
| Dell Vostro 3478                     | 10        | 0.28%   |
| Dell Latitude 3410                   | 10        | 0.28%   |
| AVITA NS14A8                         | 10        | 0.28%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| Dell Inspiron     | 366       | 10.27%  |
| Lenovo ThinkPad   | 297       | 8.33%   |
| Lenovo IdeaPad    | 294       | 8.25%   |
| HP Pavilion       | 231       | 6.48%   |
| ASUS VivoBook     | 188       | 5.27%   |
| HP Laptop         | 178       | 4.99%   |
| Dell Latitude     | 170       | 4.77%   |
| Acer Aspire       | 164       | 4.6%    |
| Dell Vostro       | 147       | 4.12%   |
| HP Notebook       | 84        | 2.36%   |
| HP EliteBook      | 63        | 1.77%   |
| ASUS ASUS         | 57        | 1.6%    |
| HP ProBook        | 55        | 1.54%   |
| ASUS ROG          | 46        | 1.29%   |
| Acer Nitro        | 46        | 1.29%   |
| ASUS TUF          | 43        | 1.21%   |
| Lenovo Legion     | 37        | 1.04%   |
| HP 15             | 36        | 1.01%   |
| Dell XPS          | 35        | 0.98%   |
| Acer Swift        | 33        | 0.93%   |
| Toshiba Satellite | 31        | 0.87%   |
| Lenovo ThinkBook  | 31        | 0.87%   |
| Timi Mi           | 27        | 0.76%   |
| Dell Precision    | 25        | 0.7%    |
| Lenovo E41-25     | 23        | 0.65%   |
| Acer Predator     | 21        | 0.59%   |
| Unknown           | 20        | 0.56%   |
| HP OMEN           | 19        | 0.53%   |
| HP Victus         | 17        | 0.48%   |
| Lenovo G50-80     | 16        | 0.45%   |
| HP ENVY           | 15        | 0.42%   |
| HP 245            | 15        | 0.42%   |
| ASUS ZenBook      | 15        | 0.42%   |
| Dell G3           | 14        | 0.39%   |
| MSI GF63          | 12        | 0.34%   |
| Lenovo G50-45     | 12        | 0.34%   |
| Infinix INBOOK    | 12        | 0.34%   |
| HP ZBook          | 12        | 0.34%   |
| HP Compaq         | 12        | 0.34%   |
| ASUS X510UNR      | 12        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 480       | 13.47%  |
| 2018    | 430       | 12.07%  |
| 2020    | 401       | 11.25%  |
| 2021    | 392       | 11%     |
| 2017    | 289       | 8.11%   |
| 2016    | 206       | 5.78%   |
| 2013    | 195       | 5.47%   |
| 2011    | 193       | 5.42%   |
| 2014    | 191       | 5.36%   |
| 2012    | 175       | 4.91%   |
| 2022    | 172       | 4.83%   |
| 2015    | 147       | 4.12%   |
| 2010    | 116       | 3.25%   |
| 2008    | 67        | 1.88%   |
| 2023    | 49        | 1.37%   |
| 2009    | 39        | 1.09%   |
| 2007    | 17        | 0.48%   |
| 2006    | 2         | 0.06%   |
| 2005    | 1         | 0.03%   |
| 2003    | 1         | 0.03%   |
| Unknown | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3564      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3062      | 84.98%  |
| Enabled  | 541       | 15.02%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3552      | 99.66%  |
| Yes  | 12        | 0.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1292      | 35.69%  |
| 3.01-4.0    | 736       | 20.33%  |
| 8.01-16.0   | 731       | 20.19%  |
| 16.01-24.0  | 602       | 16.63%  |
| 32.01-64.0  | 102       | 2.82%   |
| 1.01-2.0    | 90        | 2.49%   |
| 24.01-32.0  | 25        | 0.69%   |
| 2.01-3.0    | 25        | 0.69%   |
| 64.01-256.0 | 10        | 0.28%   |
| 0.51-1.0    | 6         | 0.17%   |
| 0.01-0.5    | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1231      | 31.4%   |
| 1.01-2.0   | 1092      | 27.85%  |
| 4.01-8.0   | 681       | 17.37%  |
| 3.01-4.0   | 656       | 16.73%  |
| 8.01-16.0  | 134       | 3.42%   |
| 0.51-1.0   | 108       | 2.75%   |
| 0.01-0.5   | 12        | 0.31%   |
| 16.01-24.0 | 5         | 0.13%   |
| 24.01-32.0 | 2         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2681      | 74.25%  |
| 2      | 858       | 23.76%  |
| 3      | 47        | 1.3%    |
| 0      | 24        | 0.66%   |
| 5      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2450      | 68.28%  |
| Yes       | 1138      | 31.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2848      | 79.73%  |
| No        | 724       | 20.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3530      | 98.99%  |
| No        | 36        | 1.01%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3169      | 88.03%  |
| No        | 431       | 11.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| India   | 3564      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Bengaluru     | 457       | 11.96%  |
| Chennai       | 247       | 6.46%   |
| Delhi         | 234       | 6.12%   |
| Mumbai        | 227       | 5.94%   |
| Hyderabad     | 205       | 5.36%   |
| Pune          | 199       | 5.21%   |
| New Delhi     | 148       | 3.87%   |
| Kolkata       | 141       | 3.69%   |
| Ahmedabad     | 87        | 2.28%   |
| Lucknow       | 80        | 2.09%   |
| Patna         | 66        | 1.73%   |
| Jaipur        | 63        | 1.65%   |
| Gurgaon       | 58        | 1.52%   |
| Ernakulam     | 58        | 1.52%   |
| Kochi         | 53        | 1.39%   |
| Coimbatore    | 53        | 1.39%   |
| Indore        | 47        | 1.23%   |
| Bhopal        | 43        | 1.13%   |
| Navi Mumbai   | 40        | 1.05%   |
| Trivandrum    | 37        | 0.97%   |
| Thrissur      | 36        | 0.94%   |
| Ludhiana      | 33        | 0.86%   |
| Nagpur        | 32        | 0.84%   |
| Surat         | 31        | 0.81%   |
| Guwahati      | 30        | 0.78%   |
| Malappuram    | 29        | 0.76%   |
| Bhubaneswar   | 29        | 0.76%   |
| Noida         | 26        | 0.68%   |
| Chandigarh    | 24        | 0.63%   |
| Mangalore     | 21        | 0.55%   |
| Ghaziabad     | 21        | 0.55%   |
| Visakhapatnam | 20        | 0.52%   |
| Thane         | 17        | 0.44%   |
| Kanpur        | 17        | 0.44%   |
| Mohali        | 16        | 0.42%   |
| Dehradun      | 16        | 0.42%   |
| Kozhikode     | 15        | 0.39%   |
| Kottayam      | 15        | 0.39%   |
| Vadodara      | 14        | 0.37%   |
| Tiruchi       | 14        | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 799       | 974    | 18.26%  |
| WDC                          | 712       | 860    | 16.27%  |
| Samsung Electronics          | 485       | 591    | 11.08%  |
| Toshiba                      | 448       | 512    | 10.24%  |
| SanDisk                      | 217       | 268    | 4.96%   |
| SK hynix                     | 195       | 223    | 4.46%   |
| Intel                        | 186       | 246    | 4.25%   |
| Micron Technology            | 168       | 196    | 3.84%   |
| HGST                         | 160       | 177    | 3.66%   |
| Crucial                      | 158       | 192    | 3.61%   |
| Kingston                     | 152       | 178    | 3.47%   |
| KIOXIA                       | 87        | 98     | 1.99%   |
| Unknown                      | 83        | 103    | 1.9%    |
| Hitachi                      | 80        | 95     | 1.83%   |
| China                        | 35        | 41     | 0.8%    |
| FORESEE                      | 27        | 31     | 0.62%   |
| A-DATA Technology            | 27        | 28     | 0.62%   |
| Micron/Crucial Technology    | 24        | 26     | 0.55%   |
| Unknown                      | 20        | 26     | 0.46%   |
| UMIS                         | 18        | 22     | 0.41%   |
| Apple                        | 18        | 22     | 0.41%   |
| Silicon Motion               | 17        | 20     | 0.39%   |
| Phison                       | 14        | 17     | 0.32%   |
| LITEON                       | 14        | 18     | 0.32%   |
| Kingston Technology Company  | 11        | 14     | 0.25%   |
| Hewlett-Packard              | 11        | 15     | 0.25%   |
| Acer                         | 10        | 11     | 0.23%   |
| Fujitsu                      | 9         | 9      | 0.21%   |
| Union Memory (Shenzhen)      | 7         | 10     | 0.16%   |
| Transcend                    | 6         | 7      | 0.14%   |
| Shenzhen Longsys Electronics | 6         | 9      | 0.14%   |
| Realtek Semiconductor        | 6         | 10     | 0.14%   |
| Lexar                        | 6         | 6      | 0.14%   |
| Gigabyte Technology          | 6         | 7      | 0.14%   |
| YMTC                         | 5         | 7      | 0.11%   |
| Yangtze Memory Technologies  | 5         | 8      | 0.11%   |
| SPCC                         | 5         | 6      | 0.11%   |
| Phison Electronics           | 5         | 5      | 0.11%   |
| Netac                        | 5         | 5      | 0.11%   |
| Lenovo                       | 5         | 7      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                    | 293       | 6.52%   |
| Toshiba MQ04ABF100 1TB                            | 149       | 3.32%   |
| Toshiba MQ01ABD100 1TB                            | 108       | 2.4%    |
| Seagate ST1000LM049-2GH172 1TB                    | 69        | 1.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 64        | 1.42%   |
| Seagate ST500LT012-1DG142 500GB                   | 62        | 1.38%   |
| Crucial CT240BX500SSD1 240GB                      | 54        | 1.2%    |
| Intel NVMe SSD Drive 512GB                        | 48        | 1.07%   |
| Toshiba MQ01ABF050 500GB                          | 44        | 0.98%   |
| HGST HTS541010A9E680 1TB                          | 41        | 0.91%   |
| WDC WD10SPZX-60Z10T0 1TB                          | 40        | 0.89%   |
| SanDisk NVMe SSD Drive 512GB                      | 40        | 0.89%   |
| Intel SSDPEKNW512G8 512GB                         | 39        | 0.87%   |
| Seagate ST1000LM048-2E7172 1TB                    | 37        | 0.82%   |
| Micron 2450_MTFDKBA512TFK 512GB                   | 37        | 0.82%   |
| WDC WD10SPZX-24Z10 1TB                            | 36        | 0.8%    |
| SanDisk NVMe SSD Drive 256GB                      | 36        | 0.8%    |
| Seagate ST2000LM007-1R8174 2TB                    | 35        | 0.78%   |
| Kingston SA400S37240G 240GB SSD                   | 35        | 0.78%   |
| Seagate ST9500325AS 500GB                         | 34        | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 33        | 0.73%   |
| Samsung NVMe SSD Drive 512GB                      | 33        | 0.73%   |
| SK hynix NVMe SSD Drive 512GB                     | 29        | 0.65%   |
| HGST HTS721010A9E630 1TB                          | 29        | 0.65%   |
| WDC WD10SPZX-21Z10T0 1TB                          | 28        | 0.62%   |
| WDC WD10JPVX-60JC3T1 1TB                          | 27        | 0.6%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD                  | 24        | 0.53%   |
| Crucial CT480BX500SSD1 480GB                      | 24        | 0.53%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 23        | 0.51%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                    | 23        | 0.51%   |
| HGST HTS545050A7E680 500GB                        | 23        | 0.51%   |
| Seagate ST500LT012-9WS142 500GB                   | 21        | 0.47%   |
| WDC WD5000LPVX-75V0TT0 500GB                      | 20        | 0.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 20        | 0.45%   |
| HGST HTS545050A7E380 500GB                        | 20        | 0.45%   |
| Unknown                                           | 20        | 0.45%   |
| WDC WD10JPVX-60JC3T0 1TB                          | 19        | 0.42%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB              | 19        | 0.42%   |
| WDC WD10SPZX-24Z10T0 1TB                          | 18        | 0.4%    |
| WDC WD10JPCX-24UE4T0 1TB                          | 18        | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 789       | 962    | 40.05%  |
| WDC                 | 493       | 583    | 25.03%  |
| Toshiba             | 400       | 450    | 20.3%   |
| HGST                | 160       | 177    | 8.12%   |
| Hitachi             | 80        | 95     | 4.06%   |
| Unknown             | 10        | 10     | 0.51%   |
| Fujitsu             | 9         | 9      | 0.46%   |
| Samsung Electronics | 7         | 7      | 0.36%   |
| Apple               | 5         | 5      | 0.25%   |
| TO Exter            | 4         | 4      | 0.2%    |
| Hewlett-Packard     | 4         | 5      | 0.2%    |
| External            | 4         | 6      | 0.2%    |
| MARSHAL             | 3         | 3      | 0.15%   |
| StoreJet            | 2         | 2      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 155       | 175    | 18.07%  |
| Crucial             | 142       | 175    | 16.55%  |
| WDC                 | 116       | 131    | 13.52%  |
| Kingston            | 88        | 109    | 10.26%  |
| SanDisk             | 53        | 71     | 6.18%   |
| SK hynix            | 36        | 38     | 4.2%    |
| China               | 34        | 40     | 3.96%   |
| Micron Technology   | 24        | 29     | 2.8%    |
| A-DATA Technology   | 20        | 21     | 2.33%   |
| FORESEE             | 18        | 22     | 2.1%    |
| Intel               | 17        | 19     | 1.98%   |
| LITEON              | 12        | 16     | 1.4%    |
| Unknown             | 11        | 11     | 1.28%   |
| Toshiba             | 10        | 10     | 1.17%   |
| Apple               | 10        | 11     | 1.17%   |
| Acer                | 9         | 10     | 1.05%   |
| Seagate             | 7         | 7      | 0.82%   |
| Hewlett-Packard     | 6         | 9      | 0.7%    |
| Gigabyte Technology | 6         | 7      | 0.7%    |
| Lexar               | 5         | 5      | 0.58%   |
| Unknown             | 4         | 4      | 0.47%   |
| PNY                 | 4         | 6      | 0.47%   |
| Netac               | 4         | 4      | 0.47%   |
| Maxtor              | 4         | 6      | 0.47%   |
| EVM                 | 4         | 6      | 0.47%   |
| CONSISTENT          | 4         | 5      | 0.47%   |
| Aarvex              | 4         | 5      | 0.47%   |
| Transcend           | 3         | 4      | 0.35%   |
| SPCC                | 3         | 4      | 0.35%   |
| POWER               | 3         | 3      | 0.35%   |
| geonix              | 3         | 3      | 0.35%   |
| Zebronics           | 2         | 2      | 0.23%   |
| Team                | 2         | 2      | 0.23%   |
| OSCOO               | 2         | 4      | 0.23%   |
| LITEONIT            | 2         | 3      | 0.23%   |
| KLEVV               | 2         | 3      | 0.23%   |
| HS-SSD-C100         | 2         | 2      | 0.23%   |
| BIWIN               | 2         | 2      | 0.23%   |
| BHT                 | 2         | 3      | 0.23%   |
| W800S               | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1942      | 2318   | 45.44%  |
| NVMe    | 1400      | 1789   | 32.76%  |
| SSD     | 833       | 1011   | 19.49%  |
| MMC     | 63        | 81     | 1.47%   |
| Unknown | 36        | 48     | 0.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2457      | 3293   | 61.49%  |
| NVMe | 1400      | 1787   | 35.04%  |
| SAS  | 76        | 86     | 1.9%    |
| MMC  | 63        | 81     | 1.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1376      | 1712   | 50.38%  |
| 0.51-1.0   | 1297      | 1555   | 47.49%  |
| 1.01-2.0   | 54        | 58     | 1.98%   |
| 4.01-10.0  | 3         | 3      | 0.11%   |
| 3.01-4.0   | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1105      | 29.29%  |
| 101-250        | 972       | 25.76%  |
| 501-1000       | 661       | 17.52%  |
| 51-100         | 331       | 8.77%   |
| 1001-2000      | 213       | 5.65%   |
| 1-20           | 190       | 5.04%   |
| 21-50          | 176       | 4.66%   |
| Unknown        | 57        | 1.51%   |
| 2001-3000      | 40        | 1.06%   |
| More than 3000 | 28        | 0.74%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1397      | 35.74%  |
| 21-50          | 869       | 22.23%  |
| 101-250        | 566       | 14.48%  |
| 51-100         | 521       | 13.33%  |
| 251-500        | 309       | 7.9%    |
| 501-1000       | 147       | 3.76%   |
| Unknown        | 57        | 1.46%   |
| 1001-2000      | 37        | 0.95%   |
| 2001-3000      | 3         | 0.08%   |
| More than 3000 | 2         | 0.05%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB       | 28        | 31     | 9.24%   |
| HGST HTS541010A9E680 1TB             | 14        | 14     | 4.62%   |
| HGST HTS545050A7E680 500GB           | 12        | 14     | 3.96%   |
| Toshiba MQ01ABD100 1TB               | 11        | 11     | 3.63%   |
| Seagate ST500LT012-1DG142 500GB      | 11        | 11     | 3.63%   |
| Seagate ST1000LM049-2GH172 1TB       | 10        | 12     | 3.3%    |
| Seagate ST9500325AS 500GB            | 9         | 9      | 2.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 8         | 8      | 2.64%   |
| Toshiba MQ04ABF100 1TB               | 6         | 7      | 1.98%   |
| Toshiba MQ01ABF050 500GB             | 6         | 6      | 1.98%   |
| Seagate ST500LT012-9WS142 500GB      | 6         | 7      | 1.98%   |
| Seagate ST500LM021-1KJ152 500GB      | 6         | 6      | 1.98%   |
| Seagate ST2000LM007-1R8174 2TB       | 5         | 5      | 1.65%   |
| HGST HTS545050A7E380 500GB           | 5         | 5      | 1.65%   |
| Seagate ST320LT007-9ZV142 320GB      | 4         | 5      | 1.32%   |
| HGST HTS725050A7E630 500GB           | 4         | 4      | 1.32%   |
| HGST HTS721010A9E630 1TB             | 4         | 4      | 1.32%   |
| WDC WD10SPZX-24Z10 1TB               | 3         | 3      | 0.99%   |
| WDC WD10JPVX-60JC3T1 1TB             | 3         | 3      | 0.99%   |
| SK hynix PC711 HFS512GDE9X073N 512GB | 3         | 4      | 0.99%   |
| Seagate ST9320325AS 320GB            | 3         | 3      | 0.99%   |
| Seagate ST1000LM048-2E7172 1TB       | 3         | 3      | 0.99%   |
| Hitachi HTS547575A9E384 752GB        | 3         | 3      | 0.99%   |
| Hitachi HTS545032B9A300 320GB        | 3         | 5      | 0.99%   |
| Hitachi HTS543232A7A384 320GB        | 3         | 3      | 0.99%   |
| Unknown                              | 3         | 3      | 0.99%   |
| WDC WDS480G2G0A-00JH30 480GB SSD     | 2         | 2      | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 2         | 2      | 0.66%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 2      | 0.66%   |
| WDC WD5000LPVT-22G33T0 500GB         | 2         | 2      | 0.66%   |
| WDC WD3200BEKT-75PVMT0 320GB         | 2         | 2      | 0.66%   |
| WDC WD10SPZX-60Z10T0 1TB             | 2         | 2      | 0.66%   |
| WDC WD10JPCX-24UE4T0 1TB             | 2         | 2      | 0.66%   |
| Toshiba MQ01ABD050 500GB             | 2         | 2      | 0.66%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 2         | 2      | 0.66%   |
| Seagate ST1000LM014-1EJ164 1TB       | 2         | 2      | 0.66%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD  | 2         | 2      | 0.66%   |
| Hitachi HTS542516K9SA00 160GB        | 2         | 2      | 0.66%   |
| Crucial CT500P1SSD8 500GB            | 2         | 2      | 0.66%   |
| China SSD 256GB                      | 2         | 2      | 0.66%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 106       | 116    | 35.1%   |
| WDC                 | 48        | 50     | 15.89%  |
| HGST                | 43        | 45     | 14.24%  |
| Toshiba             | 39        | 41     | 12.91%  |
| Hitachi             | 24        | 28     | 7.95%   |
| SK hynix            | 9         | 11     | 2.98%   |
| Samsung Electronics | 7         | 8      | 2.32%   |
| SanDisk             | 5         | 5      | 1.66%   |
| Intel               | 3         | 3      | 0.99%   |
| Unknown             | 3         | 3      | 0.99%   |
| Micron Technology   | 2         | 2      | 0.66%   |
| Crucial             | 2         | 2      | 0.66%   |
| China               | 2         | 2      | 0.66%   |
| Apple               | 2         | 2      | 0.66%   |
| Secure              | 1         | 1      | 0.33%   |
| POWER               | 1         | 1      | 0.33%   |
| MARSHAL             | 1         | 1      | 0.33%   |
| LITEONIT            | 1         | 1      | 0.33%   |
| Leven               | 1         | 1      | 0.33%   |
| Lenovo              | 1         | 2      | 0.33%   |
| A-DATA Technology   | 1         | 1      | 0.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 106       | 116    | 41.25%  |
| HGST                | 43        | 45     | 16.73%  |
| WDC                 | 40        | 42     | 15.56%  |
| Toshiba             | 39        | 41     | 15.18%  |
| Hitachi             | 24        | 28     | 9.34%   |
| Samsung Electronics | 2         | 2      | 0.78%   |
| Apple               | 2         | 2      | 0.78%   |
| MARSHAL             | 1         | 1      | 0.39%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 257       | 277    | 85.1%   |
| SSD  | 30        | 31     | 9.93%   |
| NVMe | 15        | 18     | 4.97%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB            | 1         | 1      | 16.67%  |
| Seagate ST9320320AS 320GB           | 1         | 1      | 16.67%  |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 16.67%  |
| Seagate ST1000LM 024 HN-M101MBB 1TB | 1         | 1      | 16.67%  |
| Apple HDD HTS545050A7E362 500GB     | 1         | 1      | 16.67%  |
| Acer SSD FA100 256GB                | 1         | 1      | 16.67%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 50%     |
| WDC     | 1         | 1      | 16.67%  |
| Apple   | 1         | 1      | 16.67%  |
| Acer    | 1         | 1      | 16.67%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2037      | 2913   | 53.96%  |
| Works    | 1434      | 2002   | 37.99%  |
| Malfunc  | 298       | 326    | 7.89%   |
| Failed   | 6         | 6      | 0.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 2640      | 59.35%  |
| AMD                                     | 486       | 10.93%  |
| Samsung Electronics                     | 339       | 7.62%   |
| SanDisk                                 | 275       | 6.18%   |
| SK hynix                                | 159       | 3.57%   |
| Micron Technology                       | 144       | 3.24%   |
| KIOXIA                                  | 90        | 2.02%   |
| Kingston Technology Company             | 76        | 1.71%   |
| Toshiba America Info Systems            | 48        | 1.08%   |
| Micron/Crucial Technology               | 38        | 0.85%   |
| Union Memory (Shenzhen)                 | 27        | 0.61%   |
| Silicon Motion                          | 21        | 0.47%   |
| Phison Electronics                      | 17        | 0.38%   |
| Shenzhen Longsys Electronics            | 16        | 0.36%   |
| Yangtze Memory Technologies             | 10        | 0.22%   |
| ADATA Technology                        | 10        | 0.22%   |
| Realtek Semiconductor                   | 9         | 0.2%    |
| Solid State Storage Technology          | 8         | 0.18%   |
| Nvidia                                  | 5         | 0.11%   |
| Lite-On Technology                      | 5         | 0.11%   |
| Lenovo                                  | 5         | 0.11%   |
| MAXIO Technology (Hangzhou)             | 3         | 0.07%   |
| INNOGRIT                                | 3         | 0.07%   |
| Apple                                   | 3         | 0.07%   |
| Transcend                               | 2         | 0.04%   |
| Shenzhen Unionmemory Information System | 2         | 0.04%   |
| Solidigm                                | 1         | 0.02%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.02%   |
| Netac Technology                        | 1         | 0.02%   |
| Marvell Technology Group                | 1         | 0.02%   |
| Hosin Global Electronics                | 1         | 0.02%   |
| Biwin Storage Technology                | 1         | 0.02%   |
| ASMedia Technology                      | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 489       | 10.38%  |
| AMD FCH SATA Controller [AHCI mode]                                            | 473       | 10.04%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 338       | 7.17%   |
| Intel Volume Management Device NVMe RAID Controller                            | 213       | 4.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 209       | 4.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 191       | 4.05%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 157       | 3.33%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 134       | 2.84%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 132       | 2.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 115       | 2.44%   |
| Intel Tiger Lake-LP SATA Controller                                            | 115       | 2.44%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 115       | 2.44%   |
| Intel Comet Lake SATA AHCI Controller                                          | 107       | 2.27%   |
| Intel SSD 660P Series                                                          | 104       | 2.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 94        | 1.99%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 74        | 1.57%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 74        | 1.57%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 60        | 1.27%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 56        | 1.19%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 54        | 1.15%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 54        | 1.15%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 54        | 1.15%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 48        | 1.02%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 46        | 0.98%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 43        | 0.91%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 41        | 0.87%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 41        | 0.87%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 39        | 0.83%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 39        | 0.83%   |
| SK hynix BC511 NVMe SSD                                                        | 35        | 0.74%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 35        | 0.74%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 34        | 0.72%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 31        | 0.66%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 31        | 0.66%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 28        | 0.59%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 23        | 0.49%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 22        | 0.47%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 21        | 0.45%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 21        | 0.45%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 19        | 0.4%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2552      | 55.39%  |
| NVMe | 1410      | 30.61%  |
| RAID | 572       | 12.42%  |
| IDE  | 73        | 1.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 2866      | 80.42%  |
| AMD    | 697       | 19.56%  |
| ARM    | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 185       | 5.19%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 122       | 3.42%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 106       | 2.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 84        | 2.36%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 83        | 2.33%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 82        | 2.3%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 59        | 1.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 54        | 1.51%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 53        | 1.49%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 53        | 1.49%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 53        | 1.49%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 52        | 1.46%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 51        | 1.43%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 47        | 1.32%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 45        | 1.26%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 45        | 1.26%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 41        | 1.15%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 41        | 1.15%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 40        | 1.12%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 40        | 1.12%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 39        | 1.09%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 38        | 1.07%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 37        | 1.04%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 37        | 1.04%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 35        | 0.98%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 33        | 0.93%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 31        | 0.87%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 31        | 0.87%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 30        | 0.84%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 0.81%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 29        | 0.81%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 29        | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 28        | 0.79%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 27        | 0.76%   |
| Intel 12th Gen Core i5-1240P                  | 26        | 0.73%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 26        | 0.73%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz       | 25        | 0.7%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 24        | 0.67%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 24        | 0.67%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 24        | 0.67%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1139      | 31.96%  |
| Intel Core i3           | 582       | 16.33%  |
| Intel Core i7           | 483       | 13.55%  |
| Other                   | 439       | 12.32%  |
| AMD Ryzen 5             | 297       | 8.33%   |
| AMD Ryzen 7             | 124       | 3.48%   |
| Intel Pentium           | 87        | 2.44%   |
| Intel Core 2 Duo        | 66        | 1.85%   |
| Intel Celeron           | 52        | 1.46%   |
| AMD Ryzen 3             | 49        | 1.37%   |
| AMD A6                  | 45        | 1.26%   |
| AMD A8                  | 28        | 0.79%   |
| AMD Ryzen 9             | 21        | 0.59%   |
| AMD A4                  | 21        | 0.59%   |
| Intel Atom              | 17        | 0.48%   |
| AMD A10                 | 17        | 0.48%   |
| Intel Pentium Dual-Core | 14        | 0.39%   |
| AMD E1                  | 13        | 0.36%   |
| AMD Ryzen 7 PRO         | 11        | 0.31%   |
| AMD E2                  | 8         | 0.22%   |
| Intel Pentium Silver    | 6         | 0.17%   |
| Intel Pentium Dual      | 5         | 0.14%   |
| Intel Core 2            | 5         | 0.14%   |
| AMD Ryzen 5 PRO         | 4         | 0.11%   |
| AMD E                   | 4         | 0.11%   |
| Intel Xeon              | 3         | 0.08%   |
| Intel Core i9           | 3         | 0.08%   |
| AMD C-60                | 3         | 0.08%   |
| AMD A12                 | 3         | 0.08%   |
| AMD PRO A10             | 2         | 0.06%   |
| AMD Athlon              | 2         | 0.06%   |
| Intel Pentium M         | 1         | 0.03%   |
| Intel Genuine           | 1         | 0.03%   |
| Intel Core m5           | 1         | 0.03%   |
| Intel Core m3           | 1         | 0.03%   |
| Intel Core M            | 1         | 0.03%   |
| Intel Core              | 1         | 0.03%   |
| Intel Celeron M         | 1         | 0.03%   |
| Intel Celeron Dual-Core | 1         | 0.03%   |
| AMD Turion 64 X2 Mobile | 1         | 0.03%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1671      | 46.87%  |
| 4      | 1286      | 36.07%  |
| 6      | 281       | 7.88%   |
| 8      | 189       | 5.3%    |
| 12     | 54        | 1.51%   |
| 10     | 29        | 0.81%   |
| 1      | 26        | 0.73%   |
| 14     | 22        | 0.62%   |
| 16     | 4         | 0.11%   |
| 3      | 2         | 0.06%   |
| 24     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3564      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 3098      | 86.85%  |
| 1      | 466       | 13.06%  |
| 4      | 2         | 0.06%   |
| 12     | 1         | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3535      | 99.13%  |
| Unknown        | 27        | 0.76%   |
| 32-bit         | 4         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 994       | 26.96%  |
| 0x806ec    | 217       | 5.89%   |
| 0x806ea    | 215       | 5.83%   |
| 0x806c1    | 161       | 4.37%   |
| 0x206a7    | 154       | 4.18%   |
| 0x40651    | 153       | 4.15%   |
| 0x306a9    | 153       | 4.15%   |
| 0x406e3    | 150       | 4.07%   |
| 0x806e9    | 142       | 3.85%   |
| 0x906ea    | 115       | 3.12%   |
| 0x306d4    | 112       | 3.04%   |
| 0x08108109 | 78        | 2.12%   |
| 0x706e5    | 75        | 2.03%   |
| 0x0a50000c | 72        | 1.95%   |
| 0x20655    | 54        | 1.46%   |
| 0x806eb    | 53        | 1.44%   |
| 0x08108102 | 50        | 1.36%   |
| 0xa0652    | 46        | 1.25%   |
| 0x06006705 | 46        | 1.25%   |
| 0x1067a    | 39        | 1.06%   |
| 0x08608103 | 36        | 0.98%   |
| 0x306c3    | 34        | 0.92%   |
| 0x906a3    | 33        | 0.9%    |
| 0x08600106 | 32        | 0.87%   |
| 0x07030105 | 32        | 0.87%   |
| 0x906e9    | 31        | 0.84%   |
| 0x08600104 | 26        | 0.71%   |
| 0x20652    | 25        | 0.68%   |
| 0x0a50000d | 25        | 0.68%   |
| 0x0810100b | 18        | 0.49%   |
| 0x08101007 | 18        | 0.49%   |
| 0x6fd      | 17        | 0.46%   |
| 0x906ed    | 15        | 0.41%   |
| 0x806d1    | 15        | 0.41%   |
| 0x30678    | 15        | 0.41%   |
| 0x506e3    | 13        | 0.35%   |
| 0x08600103 | 12        | 0.33%   |
| 0x06001119 | 12        | 0.33%   |
| 0x406c4    | 10        | 0.27%   |
| 0x06006704 | 10        | 0.27%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 991       | 27.75%  |
| Haswell          | 247       | 6.92%   |
| TigerLake        | 242       | 6.78%   |
| Skylake          | 222       | 6.22%   |
| SandyBridge      | 200       | 5.6%    |
| IvyBridge        | 197       | 5.52%   |
| Zen+             | 158       | 4.42%   |
| Broadwell        | 148       | 4.14%   |
| Unknown          | 125       | 3.5%    |
| IceLake          | 124       | 3.47%   |
| Zen 3            | 118       | 3.3%    |
| Alderlake Hybrid | 110       | 3.08%   |
| Westmere         | 103       | 2.88%   |
| Zen 2            | 102       | 2.86%   |
| Excavator        | 83        | 2.32%   |
| CometLake        | 68        | 1.9%    |
| Penryn           | 66        | 1.85%   |
| Puma             | 54        | 1.51%   |
| Silvermont       | 45        | 1.26%   |
| Zen              | 41        | 1.15%   |
| Core             | 28        | 0.78%   |
| Piledriver       | 18        | 0.5%    |
| Goldmont plus    | 15        | 0.42%   |
| K10 Llano        | 11        | 0.31%   |
| Bonnell          | 10        | 0.28%   |
| Goldmont         | 9         | 0.25%   |
| Bobcat           | 8         | 0.22%   |
| Jaguar           | 7         | 0.2%    |
| Tremont          | 6         | 0.17%   |
| Nehalem          | 6         | 0.17%   |
| P6               | 3         | 0.08%   |
| Steamroller      | 2         | 0.06%   |
| K10              | 2         | 0.06%   |
| K8 Hammer        | 1         | 0.03%   |
| Gracemont        | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2773      | 57.28%  |
| Nvidia                           | 1048      | 21.65%  |
| AMD                              | 1019      | 21.05%  |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                | 255       | 5.14%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 199       | 4.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 193       | 3.89%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 191       | 3.85%   |
| Intel HD Graphics 620                                                                 | 191       | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 187       | 3.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 183       | 3.69%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 183       | 3.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 171       | 3.45%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 159       | 3.2%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 156       | 3.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 150       | 3.02%   |
| Intel HD Graphics 5500                                                                | 134       | 2.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]         | 118       | 2.38%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                         | 100       | 2.02%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 99        | 2%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 85        | 1.71%   |
| Intel Core Processor Integrated Graphics Controller                                   | 77        | 1.55%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 70        | 1.41%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 67        | 1.35%   |
| AMD Lucienne                                                                          | 63        | 1.27%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 61        | 1.23%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 61        | 1.23%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 58        | 1.17%   |
| Nvidia GP108M [GeForce MX250]                                                         | 51        | 1.03%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 51        | 1.03%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 50        | 1.01%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                             | 50        | 1.01%   |
| Nvidia GP108M [GeForce MX150]                                                         | 44        | 0.89%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 44        | 0.89%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 40        | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 38        | 0.77%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 37        | 0.75%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 37        | 0.75%   |
| Nvidia GM108M [GeForce MX130]                                                         | 35        | 0.71%   |
| Intel HD Graphics 630                                                                 | 35        | 0.71%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 33        | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 33        | 0.67%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 32        | 0.65%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                      | 31        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1674      | 46.77%  |
| Intel + Nvidia | 800       | 22.35%  |
| 1 x AMD        | 461       | 12.88%  |
| Intel + AMD    | 290       | 8.1%    |
| AMD + Nvidia   | 181       | 5.06%   |
| 2 x AMD        | 89        | 2.49%   |
| 1 x Nvidia     | 66        | 1.84%   |
| 2 x Intel      | 14        | 0.39%   |
| Other          | 3         | 0.08%   |
| 1 x SiS        | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2974      | 82.31%  |
| Proprietary | 562       | 15.55%  |
| Unknown     | 77        | 2.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2307      | 62.91%  |
| 1.01-2.0   | 532       | 14.51%  |
| 0.01-0.5   | 334       | 9.11%   |
| 3.01-4.0   | 278       | 7.58%   |
| 0.51-1.0   | 163       | 4.45%   |
| 5.01-6.0   | 39        | 1.06%   |
| 7.01-8.0   | 8         | 0.22%   |
| 2.01-3.0   | 3         | 0.08%   |
| 8.01-16.0  | 3         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 800       | 21.04%  |
| Chimei Innolux          | 743       | 19.54%  |
| AU Optronics            | 727       | 19.12%  |
| LG Display              | 560       | 14.73%  |
| Samsung Electronics     | 273       | 7.18%   |
| PANDA                   | 121       | 3.18%   |
| Dell                    | 72        | 1.89%   |
| Goldstar                | 65        | 1.71%   |
| Sharp                   | 49        | 1.29%   |
| BenQ                    | 47        | 1.24%   |
| Chi Mei Optoelectronics | 43        | 1.13%   |
| Lenovo                  | 32        | 0.84%   |
| Acer                    | 31        | 0.82%   |
| Apple                   | 30        | 0.79%   |
| InfoVision              | 28        | 0.74%   |
| Hewlett-Packard         | 21        | 0.55%   |
| TMX                     | 19        | 0.5%    |
| Sony                    | 19        | 0.5%    |
| AOC                     | 10        | 0.26%   |
| LG Philips              | 9         | 0.24%   |
| HKC                     | 8         | 0.21%   |
| CSO                     | 8         | 0.21%   |
| InnoLux Display         | 7         | 0.18%   |
| Unknown                 | 6         | 0.16%   |
| Toshiba                 | 6         | 0.16%   |
| KDC                     | 6         | 0.16%   |
| ViewSonic               | 4         | 0.11%   |
| HJC                     | 4         | 0.11%   |
| Valve                   | 3         | 0.08%   |
| Panasonic               | 3         | 0.08%   |
| MSI                     | 3         | 0.08%   |
| LGD                     | 3         | 0.08%   |
| CPT                     | 3         | 0.08%   |
| STD                     | 2         | 0.05%   |
| STA                     | 2         | 0.05%   |
| SGT                     | 2         | 0.05%   |
| Philips                 | 2         | 0.05%   |
| KDB                     | 2         | 0.05%   |
| HannStar                | 2         | 0.05%   |
| AGO                     | 2         | 0.05%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 95        | 2.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 76        | 1.99%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 43        | 1.13%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 41        | 1.08%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 39        | 1.02%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 39        | 1.02%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                | 38        | 1%      |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 37        | 0.97%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 35        | 0.92%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 32        | 0.84%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 31        | 0.81%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 29        | 0.76%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 28        | 0.73%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 27        | 0.71%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 26        | 0.68%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 25        | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 25        | 0.66%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch        | 25        | 0.66%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 24        | 0.63%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 24        | 0.63%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch              | 20        | 0.52%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                | 20        | 0.52%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 20        | 0.52%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 20        | 0.52%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch          | 19        | 0.5%    |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 17        | 0.45%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 17        | 0.45%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 16        | 0.42%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 16        | 0.42%   |
| BOE LCD Monitor BOE07BD 1920x1080 309x174mm 14.0-inch                | 16        | 0.42%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 16        | 0.42%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 340x190mm 15.3-inch       | 16        | 0.42%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 15        | 0.39%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 15        | 0.39%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 15        | 0.39%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 14        | 0.37%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 14        | 0.37%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch            | 14        | 0.37%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                | 14        | 0.37%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                | 14        | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1873      | 51.32%  |
| 1366x768 (WXGA)    | 1359      | 37.23%  |
| 1600x900 (HD+)     | 58        | 1.59%   |
| 2560x1440 (QHD)    | 57        | 1.56%   |
| 1920x1200 (WUXGA)  | 49        | 1.34%   |
| 1280x800 (WXGA)    | 48        | 1.32%   |
| 3840x2160 (4K)     | 46        | 1.26%   |
| 2560x1600          | 37        | 1.01%   |
| 1440x900 (WXGA+)   | 21        | 0.58%   |
| 2880x1800          | 20        | 0.55%   |
| 3200x2000          | 13        | 0.36%   |
| 2560x1080          | 10        | 0.27%   |
| 1360x768           | 7         | 0.19%   |
| 1024x600           | 7         | 0.19%   |
| 1280x1024 (SXGA)   | 6         | 0.16%   |
| 3840x2400          | 4         | 0.11%   |
| 3456x2160          | 4         | 0.11%   |
| 2160x1440          | 4         | 0.11%   |
| 800x1280           | 3         | 0.08%   |
| 2288x1287          | 3         | 0.08%   |
| 2240x1400          | 3         | 0.08%   |
| 1680x1050 (WSXGA+) | 3         | 0.08%   |
| 3440x1440          | 2         | 0.05%   |
| 3072x1920          | 2         | 0.05%   |
| 2256x1504          | 2         | 0.05%   |
| 3840x1100          | 1         | 0.03%   |
| 3200x1800 (QHD+)   | 1         | 0.03%   |
| 2880x1620          | 1         | 0.03%   |
| 2732x768           | 1         | 0.03%   |
| 1920x1280          | 1         | 0.03%   |
| 1600x1200          | 1         | 0.03%   |
| 1280x768           | 1         | 0.03%   |
| 1280x720 (HD)      | 1         | 0.03%   |
| Unknown            | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2095      | 55.16%  |
| 14      | 599       | 15.77%  |
| 13      | 574       | 15.11%  |
| 21      | 83        | 2.19%   |
| 24      | 68        | 1.79%   |
| 12      | 46        | 1.21%   |
| 23      | 44        | 1.16%   |
| 27      | 43        | 1.13%   |
| 17      | 42        | 1.11%   |
| 16      | 41        | 1.08%   |
| 19      | 23        | 0.61%   |
| 18      | 22        | 0.58%   |
| 31      | 19        | 0.5%    |
| Unknown | 17        | 0.45%   |
| 11      | 16        | 0.42%   |
| 34      | 11        | 0.29%   |
| 20      | 10        | 0.26%   |
| 10      | 8         | 0.21%   |
| 72      | 6         | 0.16%   |
| 46      | 4         | 0.11%   |
| 40      | 4         | 0.11%   |
| 26      | 4         | 0.11%   |
| 86      | 3         | 0.08%   |
| 7       | 3         | 0.08%   |
| 142     | 2         | 0.05%   |
| 65      | 2         | 0.05%   |
| 54      | 2         | 0.05%   |
| 32      | 2         | 0.05%   |
| 58      | 1         | 0.03%   |
| 42      | 1         | 0.03%   |
| 35      | 1         | 0.03%   |
| 25      | 1         | 0.03%   |
| 22      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 3132      | 82.68%  |
| 201-300        | 192       | 5.07%   |
| 501-600        | 143       | 3.78%   |
| 401-500        | 141       | 3.72%   |
| 351-400        | 95        | 2.51%   |
| 601-700        | 26        | 0.69%   |
| Unknown        | 17        | 0.45%   |
| 701-800        | 13        | 0.34%   |
| 1001-1500      | 12        | 0.32%   |
| 1501-2000      | 6         | 0.16%   |
| 801-900        | 5         | 0.13%   |
| 1-100          | 3         | 0.08%   |
| More than 2000 | 2         | 0.05%   |
| 901-1000       | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3255      | 92.71%  |
| 16/10   | 197       | 5.61%   |
| Unknown | 15        | 0.43%   |
| 21/9    | 12        | 0.34%   |
| 4/3     | 8         | 0.23%   |
| 3/2     | 8         | 0.23%   |
| 5/4     | 4         | 0.11%   |
| 0.67    | 3         | 0.09%   |
| 0.56    | 3         | 0.09%   |
| 6/5     | 2         | 0.06%   |
| 1.00    | 2         | 0.06%   |
| 3.40    | 1         | 0.03%   |
| 2.00    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2093      | 55.18%  |
| 81-90          | 1082      | 28.53%  |
| 201-250        | 173       | 4.56%   |
| 71-80          | 89        | 2.35%   |
| 151-200        | 47        | 1.24%   |
| 301-350        | 44        | 1.16%   |
| 61-70          | 43        | 1.13%   |
| 121-130        | 39        | 1.03%   |
| 351-500        | 33        | 0.87%   |
| 111-120        | 30        | 0.79%   |
| 141-150        | 22        | 0.58%   |
| 51-60          | 17        | 0.45%   |
| Unknown        | 17        | 0.45%   |
| More than 1000 | 16        | 0.42%   |
| 91-100         | 14        | 0.37%   |
| 501-1000       | 9         | 0.24%   |
| 41-50          | 8         | 0.21%   |
| 251-300        | 8         | 0.21%   |
| 131-140        | 6         | 0.16%   |
| 1-40           | 3         | 0.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1803      | 48.08%  |
| 101-120       | 1341      | 35.76%  |
| 51-100        | 342       | 9.12%   |
| 161-240       | 169       | 4.51%   |
| More than 240 | 57        | 1.52%   |
| 1-50          | 21        | 0.56%   |
| Unknown       | 17        | 0.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3196      | 88.46%  |
| 2     | 346       | 9.58%   |
| 0     | 65        | 1.8%    |
| 3     | 6         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2355      | 40.34%  |
| Intel                             | 1624      | 27.82%  |
| Qualcomm Atheros                  | 837       | 14.34%  |
| Broadcom                          | 282       | 4.83%   |
| MediaTek                          | 126       | 2.16%   |
| Xiaomi                            | 77        | 1.32%   |
| Ralink                            | 66        | 1.13%   |
| Broadcom Limited                  | 55        | 0.94%   |
| TP-Link                           | 53        | 0.91%   |
| Samsung Electronics               | 53        | 0.91%   |
| OPPO Electronics                  | 45        | 0.77%   |
| Qualcomm                          | 36        | 0.62%   |
| Ralink Technology                 | 34        | 0.58%   |
| Marvell Technology Group          | 31        | 0.53%   |
| ASIX Electronics                  | 21        | 0.36%   |
| OnePlus Technology (Shenzhen)     | 16        | 0.27%   |
| Motorola PCS                      | 16        | 0.27%   |
| Huawei Technologies               | 13        | 0.22%   |
| Google                            | 10        | 0.17%   |
| ICS Advent                        | 8         | 0.14%   |
| DisplayLink                       | 8         | 0.14%   |
| D-Link                            | 8         | 0.14%   |
| JMicron Technology                | 6         | 0.1%    |
| Foxconn / Hon Hai                 | 5         | 0.09%   |
| vivo                              | 4         | 0.07%   |
| HMD Global                        | 4         | 0.07%   |
| Dell                              | 4         | 0.07%   |
| Qualcomm Atheros Communications   | 3         | 0.05%   |
| Nvidia                            | 3         | 0.05%   |
| Lenovo                            | 3         | 0.05%   |
| Ericsson Business Mobile Networks | 3         | 0.05%   |
| ASUSTek Computer                  | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.03%   |
| Sierra Wireless                   | 2         | 0.03%   |
| QinHeng Electronics               | 2         | 0.03%   |
| NTmore                            | 2         | 0.03%   |
| Edimax Technology                 | 2         | 0.03%   |
| Attansic Technology               | 2         | 0.03%   |
| Apple                             | 2         | 0.03%   |
| VIA Technologies                  | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 1511      | 22.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 578       | 8.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 318       | 4.67%   |
| Intel Wi-Fi 6 AX201                                                    | 173       | 2.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 170       | 2.5%    |
| Intel Wireless 8265 / 8275                                             | 148       | 2.17%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 147       | 2.16%   |
| Intel Wi-Fi 6 AX200                                                    | 144       | 2.11%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 120       | 1.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 116       | 1.7%    |
| Broadcom BCM43142 802.11b/g/n                                          | 110       | 1.62%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 107       | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 105       | 1.54%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 100       | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 96        | 1.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 93        | 1.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 89        | 1.31%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 83        | 1.22%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 83        | 1.22%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 78        | 1.15%   |
| Intel Wireless 7265                                                    | 73        | 1.07%   |
| Intel Wireless 3160                                                    | 70        | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 68        | 1%      |
| Intel Wireless 3165                                                    | 66        | 0.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 61        | 0.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 57        | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 53        | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 52        | 0.76%   |
| Intel Wireless 8260                                                    | 48        | 0.7%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 47        | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 45        | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 44        | 0.65%   |
| Intel Wireless 7260                                                    | 41        | 0.6%    |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 40        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                                  | 39        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 38        | 0.56%   |
| Intel Ethernet Connection I219-LM                                      | 35        | 0.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 35        | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                   | 34        | 0.5%    |
| Realtek Killer E2600 GbE Controller                                    | 32        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1571      | 42.79%  |
| Qualcomm Atheros                  | 760       | 20.7%   |
| Realtek Semiconductor             | 744       | 20.27%  |
| Broadcom                          | 253       | 6.89%   |
| MediaTek                          | 117       | 3.19%   |
| Ralink                            | 66        | 1.8%    |
| TP-Link                           | 47        | 1.28%   |
| Broadcom Limited                  | 43        | 1.17%   |
| Ralink Technology                 | 34        | 0.93%   |
| Qualcomm                          | 11        | 0.3%    |
| D-Link                            | 8         | 0.22%   |
| Dell                              | 4         | 0.11%   |
| Qualcomm Atheros Communications   | 3         | 0.08%   |
| Sierra Wireless                   | 2         | 0.05%   |
| Edimax Technology                 | 2         | 0.05%   |
| Philips (or NXP)                  | 1         | 0.03%   |
| NetGear                           | 1         | 0.03%   |
| Micro Star International          | 1         | 0.03%   |
| IMC Networks                      | 1         | 0.03%   |
| Ericsson Business Mobile Networks | 1         | 0.03%   |
| D-Link System                     | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 318       | 8.63%   |
| Intel Wi-Fi 6 AX201                                            | 173       | 4.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 170       | 4.61%   |
| Intel Wireless 8265 / 8275                                     | 148       | 4.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 147       | 3.99%   |
| Intel Wi-Fi 6 AX200                                            | 144       | 3.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 120       | 3.26%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 116       | 3.15%   |
| Broadcom BCM43142 802.11b/g/n                                  | 110       | 2.99%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 107       | 2.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 105       | 2.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 100       | 2.71%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 96        | 2.61%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 93        | 2.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 89        | 2.42%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 83        | 2.25%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 83        | 2.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 78        | 2.12%   |
| Intel Wireless 7265                                            | 73        | 1.98%   |
| Intel Wireless 3160                                            | 70        | 1.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 68        | 1.85%   |
| Intel Wireless 3165                                            | 66        | 1.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 57        | 1.55%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 53        | 1.44%   |
| Intel Wireless 8260                                            | 48        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 47        | 1.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 45        | 1.22%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 44        | 1.19%   |
| Intel Wireless 7260                                            | 41        | 1.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 35        | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 30        | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 29        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 29        | 0.79%   |
| Ralink MT7601U Wireless Adapter                                | 24        | 0.65%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 24        | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 23        | 0.62%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 22        | 0.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 20        | 0.54%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 20        | 0.54%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 19        | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 2165      | 70.16%  |
| Intel                            | 373       | 12.09%  |
| Qualcomm Atheros                 | 122       | 3.95%   |
| Xiaomi                           | 77        | 2.5%    |
| Broadcom                         | 54        | 1.75%   |
| Samsung Electronics              | 53        | 1.72%   |
| OPPO Electronics                 | 45        | 1.46%   |
| Marvell Technology Group         | 31        | 1%      |
| Qualcomm                         | 25        | 0.81%   |
| ASIX Electronics                 | 21        | 0.68%   |
| Broadcom Limited                 | 12        | 0.39%   |
| OnePlus Technology (Shenzhen)    | 11        | 0.36%   |
| MediaTek                         | 11        | 0.36%   |
| Huawei Technologies              | 11        | 0.36%   |
| Motorola PCS                     | 10        | 0.32%   |
| Google                           | 10        | 0.32%   |
| ICS Advent                       | 8         | 0.26%   |
| DisplayLink                      | 8         | 0.26%   |
| TP-Link                          | 6         | 0.19%   |
| JMicron Technology               | 6         | 0.19%   |
| HMD Global                       | 4         | 0.13%   |
| Nvidia                           | 3         | 0.1%    |
| Lenovo                           | 3         | 0.1%    |
| Foxconn / Hon Hai                | 3         | 0.1%    |
| ASUSTek Computer                 | 3         | 0.1%    |
| vivo                             | 2         | 0.06%   |
| NTmore                           | 2         | 0.06%   |
| Attansic Technology              | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.03%   |
| VIA Technologies                 | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| LeEco                            | 1         | 0.03%   |
| Apple                            | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 1511      | 48.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 578       | 18.66%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 61        | 1.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 52        | 1.68%   |
| OPPO SM8350-IDP _SN:361A1B3C                                                   | 40        | 1.29%   |
| Intel Ethernet Connection (4) I219-LM                                          | 39        | 1.26%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 38        | 1.23%   |
| Intel Ethernet Connection I219-LM                                              | 35        | 1.13%   |
| Intel Ethernet Connection (4) I219-V                                           | 34        | 1.1%    |
| Realtek Killer E2600 GbE Controller                                            | 32        | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 29        | 0.94%   |
| Intel Ethernet Connection I218-LM                                              | 28        | 0.9%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 25        | 0.81%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 23        | 0.74%   |
| Qualcomm Redmi 9T                                                              | 22        | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                                          | 21        | 0.68%   |
| Intel 82577LM Gigabit Network Connection                                       | 18        | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 18        | 0.58%   |
| Intel Ethernet Connection I217-LM                                              | 17        | 0.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 16        | 0.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 16        | 0.52%   |
| Intel Ethernet Connection (6) I219-LM                                          | 15        | 0.48%   |
| Intel Ethernet Connection (10) I219-V                                          | 15        | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 15        | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 14        | 0.45%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 14        | 0.45%   |
| Intel Ethernet Connection (6) I219-V                                           | 13        | 0.42%   |
| Realtek RTL8125 2.5GbE Controller                                              | 11        | 0.36%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 11        | 0.36%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 11        | 0.36%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 11        | 0.36%   |
| OnePlus (Shenzhen) Android                                                     | 11        | 0.36%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 11        | 0.36%   |
| Motorola PCS moto g52                                                          | 10        | 0.32%   |
| Intel Ethernet Connection (16) I219-V                                          | 10        | 0.32%   |
| Intel Ethernet Connection (7) I219-LM                                          | 9         | 0.29%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 9         | 0.29%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 8         | 0.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 0.26%   |
| MediaTek File-CD Gadget                                                        | 8         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3530      | 55.14%  |
| Ethernet | 2844      | 44.42%  |
| Unknown  | 18        | 0.28%   |
| Modem    | 10        | 0.16%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3052      | 85.06%  |
| Ethernet | 535       | 14.91%  |
| Unknown  | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2676      | 75%     |
| 1     | 866       | 24.27%  |
| 0     | 18        | 0.5%    |
| 3     | 8         | 0.22%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2814      | 77.39%  |
| Yes  | 822       | 22.61%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1361      | 42.62%  |
| Realtek Semiconductor           | 522       | 16.35%  |
| Qualcomm Atheros Communications | 476       | 14.91%  |
| IMC Networks                    | 183       | 5.73%   |
| Broadcom                        | 164       | 5.14%   |
| Lite-On Technology              | 141       | 4.42%   |
| Foxconn / Hon Hai               | 110       | 3.45%   |
| Ralink                          | 57        | 1.79%   |
| Dell                            | 38        | 1.19%   |
| Apple                           | 28        | 0.88%   |
| Cambridge Silicon Radio         | 23        | 0.72%   |
| Hewlett-Packard                 | 18        | 0.56%   |
| Toshiba                         | 10        | 0.31%   |
| MediaTek                        | 10        | 0.31%   |
| Foxconn International           | 10        | 0.31%   |
| Realtek                         | 8         | 0.25%   |
| Ralink Technology               | 7         | 0.22%   |
| TP-Link                         | 6         | 0.19%   |
| ASUSTek Computer                | 6         | 0.19%   |
| Opticis                         | 5         | 0.16%   |
| USI                             | 3         | 0.09%   |
| Chicony Electronics             | 2         | 0.06%   |
| SINO WEALTH                     | 1         | 0.03%   |
| Micro Star International        | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Alps Electric                   | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 429       | 13.44%  |
| Realtek Bluetooth Radio                                                             | 359       | 11.24%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 317       | 9.93%   |
| Intel AX201 Bluetooth                                                               | 314       | 9.83%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 284       | 8.89%   |
| Intel AX200 Bluetooth                                                               | 141       | 4.42%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 129       | 4.04%   |
| Intel Bluetooth Device                                                              | 81        | 2.54%   |
| IMC Networks Bluetooth Radio                                                        | 64        | 2%      |
| IMC Networks Wireless_Device                                                        | 62        | 1.94%   |
| Ralink RT3290 Bluetooth                                                             | 57        | 1.79%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 57        | 1.79%   |
| IMC Networks Bluetooth Device                                                       | 54        | 1.69%   |
| Lite-On Bluetooth Device                                                            | 50        | 1.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 49        | 1.53%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 44        | 1.38%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 43        | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 38        | 1.19%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 31        | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 30        | 0.94%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 27        | 0.85%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 26        | 0.81%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 25        | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 23        | 0.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 23        | 0.72%   |
| Realtek RTL8723B Bluetooth                                                          | 17        | 0.53%   |
| Lite-On Wireless_Device                                                             | 17        | 0.53%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 17        | 0.53%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 17        | 0.53%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 16        | 0.5%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 15        | 0.47%   |
| Apple Bluetooth USB Host Controller                                                 | 15        | 0.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 14        | 0.44%   |
| Dell Wireless 365 Bluetooth                                                         | 13        | 0.41%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 12        | 0.38%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 12        | 0.38%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 12        | 0.38%   |
| Qualcomm Atheros Bluetooth                                                          | 11        | 0.34%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 11        | 0.34%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 10        | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2852      | 68.62%  |
| AMD                              | 734       | 17.66%  |
| Nvidia                           | 462       | 11.12%  |
| C-Media Electronics              | 21        | 0.51%   |
| GN Netcom                        | 11        | 0.26%   |
| Realtek Semiconductor            | 9         | 0.22%   |
| JMTek                            | 6         | 0.14%   |
| ASUSTek Computer                 | 5         | 0.12%   |
| Plantronics                      | 4         | 0.1%    |
| Generalplus Technology           | 4         | 0.1%    |
| SteelSeries ApS                  | 3         | 0.07%   |
| Sennheiser Communications        | 3         | 0.07%   |
| Logitech                         | 3         | 0.07%   |
| Lenovo                           | 3         | 0.07%   |
| YSTEK Technology                 | 2         | 0.05%   |
| Texas Instruments                | 2         | 0.05%   |
| Tenx Technology                  | 2         | 0.05%   |
| KTMicro                          | 2         | 0.05%   |
| DSEA A/S                         | 2         | 0.05%   |
| Apple                            | 2         | 0.05%   |
| Yamaha                           | 1         | 0.02%   |
| XMOS                             | 1         | 0.02%   |
| Vault                            | 1         | 0.02%   |
| Synaptics                        | 1         | 0.02%   |
| Silicon Integrated Systems [SiS] | 1         | 0.02%   |
| Shenzhen Rapoo Technology        | 1         | 0.02%   |
| Samson Technologies              | 1         | 0.02%   |
| Razer USA                        | 1         | 0.02%   |
| Panasonic (Matsushita)           | 1         | 0.02%   |
| OPPO Electronics                 | 1         | 0.02%   |
| Microsoft                        | 1         | 0.02%   |
| Kingston Technology              | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| Focusrite-Novation               | 1         | 0.02%   |
| FiiO Electronics Technology      | 1         | 0.02%   |
| Creative Technology              | 1         | 0.02%   |
| Corsair                          | 1         | 0.02%   |
| CMX Systems                      | 1         | 0.02%   |
| BR23                             | 1         | 0.02%   |
| bestechnic                       | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 654       | 12.7%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 504       | 9.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 242       | 4.7%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 242       | 4.7%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 219       | 4.25%   |
| Intel 8 Series HD Audio Controller                                                                | 199       | 3.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 197       | 3.83%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 184       | 3.57%   |
| Intel Cannon Lake PCH cAVS                                                                        | 166       | 3.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 166       | 3.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 163       | 3.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 155       | 3.01%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 154       | 2.99%   |
| Intel Broadwell-U Audio Controller                                                                | 148       | 2.87%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 147       | 2.85%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 109       | 2.12%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 107       | 2.08%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 102       | 1.98%   |
| AMD FCH Azalia Controller                                                                         | 93        | 1.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 83        | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 75        | 1.46%   |
| AMD High Definition Audio Controller                                                              | 67        | 1.3%    |
| Intel Comet Lake PCH cAVS                                                                         | 65        | 1.26%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 64        | 1.24%   |
| Nvidia Audio device                                                                               | 59        | 1.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 48        | 0.93%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 42        | 0.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 40        | 0.78%   |
| Intel CM238 HD Audio Controller                                                                   | 38        | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 31        | 0.6%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 27        | 0.52%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 25        | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 23        | 0.45%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 23        | 0.45%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 21        | 0.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 20        | 0.39%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 20        | 0.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 19        | 0.37%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 18        | 0.35%   |
| AMD Trinity HDMI Audio Controller                                                                 | 18        | 0.35%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 778       | 30.17%  |
| SK hynix            | 678       | 26.29%  |
| Micron Technology   | 368       | 14.27%  |
| Kingston            | 204       | 7.91%   |
| Crucial             | 153       | 5.93%   |
| Ramaxel Technology  | 100       | 3.88%   |
| A-DATA Technology   | 84        | 3.26%   |
| Unknown             | 62        | 2.4%    |
| Transcend           | 35        | 1.36%   |
| CSX                 | 25        | 0.97%   |
| Elpida              | 22        | 0.85%   |
| Nanya Technology    | 18        | 0.7%    |
| Corsair             | 11        | 0.43%   |
| Unknown             | 6         | 0.23%   |
| G.Skill             | 5         | 0.19%   |
| Unknown (ABCD)      | 3         | 0.12%   |
| Unknown (0x0CDC)    | 2         | 0.08%   |
| Silicon Power       | 2         | 0.08%   |
| Gold Key            | 2         | 0.08%   |
| Avant               | 2         | 0.08%   |
| ASint Technology    | 2         | 0.08%   |
| ZION                | 1         | 0.04%   |
| Unknown (0x1007)    | 1         | 0.04%   |
| Unknown (0x0CAB)    | 1         | 0.04%   |
| Unknown (0x0080)    | 1         | 0.04%   |
| Unknown (09D5)      | 1         | 0.04%   |
| Unknown (07F7)      | 1         | 0.04%   |
| Team                | 1         | 0.04%   |
| Strontium           | 1         | 0.04%   |
| SHARETRONIC         | 1         | 0.04%   |
| Qumo                | 1         | 0.04%   |
| Qimonda             | 1         | 0.04%   |
| OM Nanotech         | 1         | 0.04%   |
| Lexar Co Limited    | 1         | 0.04%   |
| Kllisre             | 1         | 0.04%   |
| ff                  | 1         | 0.04%   |
| Apacer              | 1         | 0.04%   |
| 4ea5                | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                       | Notebooks | Percent |
|-------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s    | 67        | 2.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 61        | 2.25%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s      | 58        | 2.14%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s       | 47        | 1.73%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s      | 42        | 1.55%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s      | 40        | 1.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 39        | 1.44%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 39        | 1.44%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 35        | 1.29%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 35        | 1.29%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 34        | 1.26%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s        | 33        | 1.22%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 32        | 1.18%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s        | 31        | 1.14%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s      | 30        | 1.11%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s       | 30        | 1.11%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 29        | 1.07%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s       | 29        | 1.07%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 28        | 1.03%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s    | 26        | 0.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s       | 24        | 0.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s | 24        | 0.89%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s        | 23        | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s       | 22        | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 22        | 0.81%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s    | 22        | 0.81%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s       | 22        | 0.81%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s       | 20        | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 17        | 0.63%   |
| Crucial RAM CB8GS2400.C8ET 8GB SODIMM DDR4 2667MT/s         | 17        | 0.63%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s   | 16        | 0.59%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s        | 16        | 0.59%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 15        | 0.55%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s      | 15        | 0.55%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s       | 14        | 0.52%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s       | 14        | 0.52%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s   | 13        | 0.48%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s       | 13        | 0.48%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 13        | 0.48%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s       | 13        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1348      | 64.9%   |
| DDR3    | 495       | 23.83%  |
| LPDDR4  | 93        | 4.48%   |
| DDR2    | 30        | 1.44%   |
| SDRAM   | 28        | 1.35%   |
| DDR5    | 28        | 1.35%   |
| LPDDR3  | 27        | 1.3%    |
| LPDDR5  | 23        | 1.11%   |
| Unknown | 4         | 0.19%   |
| DDR     | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1891      | 91.53%  |
| Row Of Chips | 168       | 8.13%   |
| Unknown      | 3         | 0.15%   |
| DIMM         | 2         | 0.1%    |
| Chip         | 2         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1136      | 49.35%  |
| 4096  | 700       | 30.41%  |
| 16384 | 246       | 10.69%  |
| 2048  | 168       | 7.3%    |
| 32768 | 27        | 1.17%   |
| 1024  | 23        | 1%      |
| 512   | 2         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 648       | 28.62%  |
| 3200    | 583       | 25.75%  |
| 1600    | 390       | 17.23%  |
| 2400    | 187       | 8.26%   |
| 2133    | 73        | 3.22%   |
| 3266    | 67        | 2.96%   |
| 1334    | 63        | 2.78%   |
| 1333    | 52        | 2.3%    |
| 4267    | 30        | 1.33%   |
| 4800    | 26        | 1.15%   |
| 6400    | 22        | 0.97%   |
| 4199    | 20        | 0.88%   |
| 1067    | 15        | 0.66%   |
| 667     | 15        | 0.66%   |
| 975     | 14        | 0.62%   |
| Unknown | 14        | 0.62%   |
| 1867    | 12        | 0.53%   |
| 800     | 9         | 0.4%    |
| 2048    | 6         | 0.27%   |
| 4266    | 4         | 0.18%   |
| 3733    | 4         | 0.18%   |
| 8400    | 3         | 0.13%   |
| 5600    | 2         | 0.09%   |
| 8533    | 1         | 0.04%   |
| 5200    | 1         | 0.04%   |
| 2800    | 1         | 0.04%   |
| 1639    | 1         | 0.04%   |
| 533     | 1         | 0.04%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 8         | 44.44%  |
| Canon              | 5         | 27.78%  |
| Seiko Epson        | 2         | 11.11%  |
| STMicroelectronics | 1         | 5.56%   |
| Ricoh              | 1         | 5.56%   |
| Brother Industries | 1         | 5.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP LaserJet 1020                        | 2         | 11.11%  |
| HP Ink Tank 310 series                  | 2         | 11.11%  |
| HP DeskJet 1110 series                  | 2         | 11.11%  |
| Canon LBP2900                           | 2         | 11.11%  |
| STMicroelectronics USB Printing Support | 1         | 5.56%   |
| Seiko Epson L360 Series                 | 1         | 5.56%   |
| Seiko Epson L132 Series                 | 1         | 5.56%   |
| Ricoh SP 112SU                          | 1         | 5.56%   |
| HP DeskJet 2600 series                  | 1         | 5.56%   |
| HP DeskJet 2130 series                  | 1         | 5.56%   |
| Canon PIXMA MP190                       | 1         | 5.56%   |
| Canon MF4800 Series                     | 1         | 5.56%   |
| Canon G2000 series                      | 1         | 5.56%   |
| Brother HL-L2320D series                | 1         | 5.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 110 | 2         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 631       | 18.85%  |
| IMC Networks                           | 511       | 15.26%  |
| Realtek Semiconductor                  | 343       | 10.24%  |
| Microdia                               | 339       | 10.13%  |
| Quanta                                 | 244       | 7.29%   |
| Sunplus Innovation Technology          | 206       | 6.15%   |
| Bison Electronics                      | 174       | 5.2%    |
| Cheng Uei Precision Industry (Foxlink) | 163       | 4.87%   |
| Suyin                                  | 129       | 3.85%   |
| Syntek                                 | 119       | 3.55%   |
| Luxvisions Innotech Limited            | 91        | 2.72%   |
| Acer                                   | 68        | 2.03%   |
| Lite-On Technology                     | 60        | 1.79%   |
| Sonix Technology                       | 41        | 1.22%   |
| Alcor Micro                            | 30        | 0.9%    |
| Apple                                  | 25        | 0.75%   |
| Silicon Motion                         | 22        | 0.66%   |
| Samsung Electronics                    | 21        | 0.63%   |
| Ricoh                                  | 15        | 0.45%   |
| Logitech                               | 15        | 0.45%   |
| Importek                               | 13        | 0.39%   |
| Primax Electronics                     | 10        | 0.3%    |
| OmniVision Technologies                | 9         | 0.27%   |
| SunplusIT                              | 7         | 0.21%   |
| Z-Star Microelectronics                | 6         | 0.18%   |
| Lenovo                                 | 6         | 0.18%   |
| 8SSC20F27114V1SR0BK1X4S                | 6         | 0.18%   |
| Intel                                  | 5         | 0.15%   |
| Pixart Imaging                         | 4         | 0.12%   |
| MSD                                    | 4         | 0.12%   |
| vivo                                   | 3         | 0.09%   |
| OPPO Electronics                       | 3         | 0.09%   |
| Unknown                                | 2         | 0.06%   |
| ShineTech                              | 2         | 0.06%   |
| ShineOptics                            | 2         | 0.06%   |
| Holitech                               | 2         | 0.06%   |
| Hewlett-Packard                        | 2         | 0.06%   |
| Foxconn / Hon Hai                      | 2         | 0.06%   |
| Spreadtrum Communications              | 1         | 0.03%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.03%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                  | 180       | 5.37%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 178       | 5.31%   |
| Realtek Integrated_Webcam_HD                                   | 145       | 4.33%   |
| IMC Networks Integrated Camera                                 | 138       | 4.12%   |
| Chicony Integrated Camera                                      | 136       | 4.06%   |
| Sunplus Integrated_Webcam_HD                                   | 100       | 2.99%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 90        | 2.69%   |
| Chicony HP TrueVision HD Camera                                | 68        | 2.03%   |
| Syntek Integrated Camera                                       | 63        | 1.88%   |
| Realtek Integrated Webcam                                      | 61        | 1.82%   |
| Chicony HP TrueVision HD                                       | 61        | 1.82%   |
| Quanta HP TrueVision HD Camera                                 | 52        | 1.55%   |
| Bison Integrated Camera                                        | 52        | 1.55%   |
| Chicony HD WebCam                                              | 48        | 1.43%   |
| Chicony EasyCamera                                             | 48        | 1.43%   |
| Quanta HD User Facing                                          | 47        | 1.4%    |
| Suyin HP Truevision HD                                         | 45        | 1.34%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 41        | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD        | 35        | 1.04%   |
| Chicony HD User Facing                                         | 34        | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 34        | 1.01%   |
| Syntek EasyCamera                                              | 33        | 0.99%   |
| Sonix USB2.0 HD UVC WebCam                                     | 32        | 0.96%   |
| Bison EasyCamera                                               | 32        | 0.96%   |
| Quanta HP Wide Vision HD Camera                                | 31        | 0.93%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera           | 31        | 0.93%   |
| Quanta HD Webcam                                               | 29        | 0.87%   |
| Lite-On Integrated Camera                                      | 29        | 0.87%   |
| IMC Networks HP TrueVision HD Camera                           | 29        | 0.87%   |
| Bison Lenovo EasyCamera                                        | 29        | 0.87%   |
| Quanta ACER HD User Facing                                     | 27        | 0.81%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 27        | 0.81%   |
| Suyin Integrated_Webcam_HD                                     | 25        | 0.75%   |
| Microdia Integrated Webcam                                     | 24        | 0.72%   |
| Chicony HP Wide Vision HD Camera                               | 24        | 0.72%   |
| Acer SunplusIT Integrated Camera                               | 24        | 0.72%   |
| Realtek EasyCamera                                             | 23        | 0.69%   |
| Sunplus XiaoMi USB 2.0 Webcam                                  | 21        | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 21        | 0.63%   |
| Chicony Integrated Camera (1280x720@30)                        | 20        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 193       | 32.38%  |
| Shenzhen Goodix Technology         | 120       | 20.13%  |
| Synaptics                          | 111       | 18.62%  |
| Elan Microelectronics              | 98        | 16.44%  |
| LighTuning Technology              | 23        | 3.86%   |
| Realtek USB2.0 Finger Print Bridge | 21        | 3.52%   |
| AuthenTec                          | 12        | 2.01%   |
| Upek                               | 11        | 1.85%   |
| Focal-systems.Corp                 | 6         | 1.01%   |
| STMicroelectronics                 | 1         | 0.17%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 77        | 12.92%  |
| Elan ELAN:ARM-M4                                                           | 65        | 10.91%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 55        | 9.23%   |
| Shenzhen Goodix Fingerprint Reader                                         | 37        | 6.21%   |
| Elan ELAN:Fingerprint                                                      | 33        | 5.54%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 4.7%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 25        | 4.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 23        | 3.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 23        | 3.86%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 21        | 3.52%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 3.36%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 16        | 2.68%   |
| Synaptics WBDI                                                             | 14        | 2.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 2.18%   |
| Synaptics  WBDI                                                            | 13        | 2.18%   |
| Validity Sensors VFS Fingerprint sensor                                    | 12        | 2.01%   |
| Validity Sensors VFS491                                                    | 11        | 1.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 1.68%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 1.34%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.01%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.01%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.01%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.01%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.01%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 1.01%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 6         | 1.01%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 0.84%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 0.84%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 0.67%   |
| Synaptics UWP WBDI                                                         | 4         | 0.67%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 0.67%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 0.5%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.34%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.34%   |
| Synaptics TouchPad                                                         | 2         | 0.34%   |
| AuthenTec AES2810                                                          | 2         | 0.34%   |
| AuthenTec AES1600                                                          | 2         | 0.34%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.17%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.17%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 71        | 65.14%  |
| Alcor Micro           | 21        | 19.27%  |
| Upek                  | 8         | 7.34%   |
| O2 Micro              | 4         | 3.67%   |
| Lenovo                | 3         | 2.75%   |
| Yubico.com            | 1         | 0.92%   |
| Gemalto (was Gemplus) | 1         | 0.92%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 25        | 22.73%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 21        | 19.09%  |
| Broadcom 5880                                                                | 20        | 18.18%  |
| Broadcom 58200                                                               | 14        | 12.73%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 13        | 11.82%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 8         | 7.27%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 2.73%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.73%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.91%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.91%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.91%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2295      | 62.64%  |
| 1     | 1147      | 31.3%   |
| 2     | 183       | 4.99%   |
| 3     | 26        | 0.71%   |
| 5     | 5         | 0.14%   |
| 4     | 5         | 0.14%   |
| 9     | 2         | 0.05%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 591       | 36.98%  |
| Graphics card            | 371       | 23.22%  |
| Net/wireless             | 194       | 12.14%  |
| Chipcard                 | 102       | 6.38%   |
| Multimedia controller    | 89        | 5.57%   |
| Bluetooth                | 89        | 5.57%   |
| Camera                   | 66        | 4.13%   |
| Communication controller | 33        | 2.07%   |
| Net/ethernet             | 17        | 1.06%   |
| Storage                  | 16        | 1%      |
| Sound                    | 16        | 1%      |
| Card reader              | 5         | 0.31%   |
| Network                  | 4         | 0.25%   |
| Modem                    | 4         | 0.25%   |
| Storage/nvme             | 1         | 0.06%   |

