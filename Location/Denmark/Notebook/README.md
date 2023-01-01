Linux in Denmark - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Denmark.

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

Total: 645

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Notebook      | P17SM                       | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Apple         | MacBookPro10,2              | [a01c19a34d](https://linux-hardware.org/?probe=a01c19a34d) | Dec 29, 2022 |
| GPD           | WIN2                        | [d7d31b67d0](https://linux-hardware.org/?probe=d7d31b67d0) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| ASUSTek       | X75A1                       | [5a5ee8db71](https://linux-hardware.org/?probe=5a5ee8db71) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [196d570869](https://linux-hardware.org/?probe=196d570869) | Dec 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [6cc10dd6de](https://linux-hardware.org/?probe=6cc10dd6de) | Dec 25, 2022 |
| Valve         | Jupiter                     | [5c07d82410](https://linux-hardware.org/?probe=5c07d82410) | Dec 23, 2022 |
| MSI           | GP65 Leopard 9SE            | [7b980fbd8f](https://linux-hardware.org/?probe=7b980fbd8f) | Dec 21, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [97d8552a67](https://linux-hardware.org/?probe=97d8552a67) | Dec 21, 2022 |
| Medion        | P7621                       | [eced009b2a](https://linux-hardware.org/?probe=eced009b2a) | Dec 20, 2022 |
| Lenovo        | ThinkPad W510 4318CTO       | [215feb2d5e](https://linux-hardware.org/?probe=215feb2d5e) | Dec 20, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [95aca2679a](https://linux-hardware.org/?probe=95aca2679a) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [be36edb132](https://linux-hardware.org/?probe=be36edb132) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [491b8d0b8f](https://linux-hardware.org/?probe=491b8d0b8f) | Dec 11, 2022 |
| Lenovo        | ThinkPad Z61m 94503HG       | [4131ed9268](https://linux-hardware.org/?probe=4131ed9268) | Dec 11, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [4686ea3469](https://linux-hardware.org/?probe=4686ea3469) | Dec 11, 2022 |
| Lenovo        | ThinkPad T520 4243W19       | [86064a54c0](https://linux-hardware.org/?probe=86064a54c0) | Dec 10, 2022 |
| Dell          | XPS 13 9370                 | [e5291ae74e](https://linux-hardware.org/?probe=e5291ae74e) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7a802a74b7](https://linux-hardware.org/?probe=7a802a74b7) | Dec 04, 2022 |
| Acer          | Aspire E5-575G              | [dddc2b5f29](https://linux-hardware.org/?probe=dddc2b5f29) | Dec 03, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Standard      | Unknown                     | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [687d4d78a4](https://linux-hardware.org/?probe=687d4d78a4) | Nov 29, 2022 |
| Dell          | Inspiron 15 3520            | [7c53fcc73b](https://linux-hardware.org/?probe=7c53fcc73b) | Nov 24, 2022 |
| Lenovo        | ThinkPad X250 20CLS21F00    | [dee6d2a740](https://linux-hardware.org/?probe=dee6d2a740) | Nov 23, 2022 |
| Lenovo        | ThinkPad T460 20FN004CMD    | [1b7140151d](https://linux-hardware.org/?probe=1b7140151d) | Nov 20, 2022 |
| Acer          | Aspire 5810T                | [2c671f2494](https://linux-hardware.org/?probe=2c671f2494) | Nov 18, 2022 |
| Timi          | TM1607                      | [a93d1611bb](https://linux-hardware.org/?probe=a93d1611bb) | Nov 18, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [7352c1f1ed](https://linux-hardware.org/?probe=7352c1f1ed) | Nov 17, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6af7c2ad85](https://linux-hardware.org/?probe=6af7c2ad85) | Nov 15, 2022 |
| Acer          | Aspire E5-553               | [4c031f5f3b](https://linux-hardware.org/?probe=4c031f5f3b) | Nov 15, 2022 |
| Apple         | MacBookPro5,5               | [a35952fc68](https://linux-hardware.org/?probe=a35952fc68) | Nov 14, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [270045ffa3](https://linux-hardware.org/?probe=270045ffa3) | Nov 11, 2022 |
| Komplett      | LAPQC71B                    | [b5ee8960c6](https://linux-hardware.org/?probe=b5ee8960c6) | Nov 11, 2022 |
| MSI           | GV62 8RC                    | [859227b2bb](https://linux-hardware.org/?probe=859227b2bb) | Nov 10, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [a62bf9ed3b](https://linux-hardware.org/?probe=a62bf9ed3b) | Nov 08, 2022 |
| HP            | Notebook                    | [0868a7d110](https://linux-hardware.org/?probe=0868a7d110) | Nov 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS3CF0... | [2c52a84e7c](https://linux-hardware.org/?probe=2c52a84e7c) | Nov 06, 2022 |
| ASUSTek       | N55SF                       | [02af74ebb6](https://linux-hardware.org/?probe=02af74ebb6) | Nov 02, 2022 |
| Dell          | Latitude 5280               | [368f237efe](https://linux-hardware.org/?probe=368f237efe) | Oct 28, 2022 |
| Unknown       | Unknown                     | [fcffee84e4](https://linux-hardware.org/?probe=fcffee84e4) | Oct 27, 2022 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [3b9a4fb8f4](https://linux-hardware.org/?probe=3b9a4fb8f4) | Oct 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [251892471f](https://linux-hardware.org/?probe=251892471f) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [e21d202e50](https://linux-hardware.org/?probe=e21d202e50) | Oct 22, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [35d4f4cf0e](https://linux-hardware.org/?probe=35d4f4cf0e) | Oct 20, 2022 |
| Acer          | Aspire E5-551               | [9d281c015c](https://linux-hardware.org/?probe=9d281c015c) | Oct 11, 2022 |
| Acer          | Aspire E5-551               | [6c351b94ff](https://linux-hardware.org/?probe=6c351b94ff) | Oct 11, 2022 |
| Dell          | XPS 13 9370                 | [17f73f4f28](https://linux-hardware.org/?probe=17f73f4f28) | Oct 09, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [d7379a41e9](https://linux-hardware.org/?probe=d7379a41e9) | Oct 08, 2022 |
| Lenovo        | Z50-75 80EC                 | [e3f9c7a4f1](https://linux-hardware.org/?probe=e3f9c7a4f1) | Oct 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [f913d9cde2](https://linux-hardware.org/?probe=f913d9cde2) | Oct 04, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| Unknown       | Unknown                     | [b9486c47c1](https://linux-hardware.org/?probe=b9486c47c1) | Oct 01, 2022 |
| Dell          | XPS 15 9570                 | [0d466bc2f7](https://linux-hardware.org/?probe=0d466bc2f7) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | [87c9436154](https://linux-hardware.org/?probe=87c9436154) | Sep 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d3047f6963](https://linux-hardware.org/?probe=d3047f6963) | Sep 30, 2022 |
| Apple         | MacBookPro9,2               | [6ea648bc51](https://linux-hardware.org/?probe=6ea648bc51) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [67040d9a5e](https://linux-hardware.org/?probe=67040d9a5e) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [0be5b29760](https://linux-hardware.org/?probe=0be5b29760) | Sep 21, 2022 |
| Acer          | Aspire E5-553               | [5db637f345](https://linux-hardware.org/?probe=5db637f345) | Sep 19, 2022 |
| Acer          | Aspire E5-553               | [f0bbe89fe8](https://linux-hardware.org/?probe=f0bbe89fe8) | Sep 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [82fc38716c](https://linux-hardware.org/?probe=82fc38716c) | Sep 19, 2022 |
| Dell          | XPS 13 9360                 | [af2f12093c](https://linux-hardware.org/?probe=af2f12093c) | Sep 17, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [224ecd9fa7](https://linux-hardware.org/?probe=224ecd9fa7) | Sep 13, 2022 |
| Valve         | Jupiter                     | [17ddfcd578](https://linux-hardware.org/?probe=17ddfcd578) | Sep 11, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [865455aae7](https://linux-hardware.org/?probe=865455aae7) | Sep 05, 2022 |
| Acer          | Aspire E5-553               | [de2cfb43d7](https://linux-hardware.org/?probe=de2cfb43d7) | Sep 03, 2022 |
| Apple         | MacBookPro9,2               | [3662302886](https://linux-hardware.org/?probe=3662302886) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| HP            | ProBook 6550b               | [662065bfe2](https://linux-hardware.org/?probe=662065bfe2) | Aug 29, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Lenovo        | B50-50 80S2                 | [45f5a72c59](https://linux-hardware.org/?probe=45f5a72c59) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [115ca42bb8](https://linux-hardware.org/?probe=115ca42bb8) | Aug 24, 2022 |
| Acer          | Swift SF114-33              | [0ab380f8ac](https://linux-hardware.org/?probe=0ab380f8ac) | Aug 23, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Dell          | XPS 13 9370                 | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [1d97fa15fb](https://linux-hardware.org/?probe=1d97fa15fb) | Aug 08, 2022 |
| Acer          | Aspire M3-581TG             | [5c73e4c75b](https://linux-hardware.org/?probe=5c73e4c75b) | Aug 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [41189cd175](https://linux-hardware.org/?probe=41189cd175) | Aug 03, 2022 |
| Notebook      | NS50_70MU                   | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [e6ccfdf23c](https://linux-hardware.org/?probe=e6ccfdf23c) | Jul 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [83e5824a05](https://linux-hardware.org/?probe=83e5824a05) | Jul 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [03839f9fef](https://linux-hardware.org/?probe=03839f9fef) | Jul 17, 2022 |
| HP            | Laptop 15-gw0xxx            | [a7f15d1696](https://linux-hardware.org/?probe=a7f15d1696) | Jul 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [4d9388058d](https://linux-hardware.org/?probe=4d9388058d) | Jul 12, 2022 |
| Acer          | Aspire E5-553               | [e7cdc97a90](https://linux-hardware.org/?probe=e7cdc97a90) | Jul 11, 2022 |
| Dell          | Latitude 7490               | [b456bca385](https://linux-hardware.org/?probe=b456bca385) | Jul 06, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [0e23c1fc2b](https://linux-hardware.org/?probe=0e23c1fc2b) | Jul 02, 2022 |
| Lenovo        | ThinkPad T530 24295L4       | [1bdf25550e](https://linux-hardware.org/?probe=1bdf25550e) | Jun 29, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [6dfa236f76](https://linux-hardware.org/?probe=6dfa236f76) | Jun 18, 2022 |
| Notebook      | PB50_70DFx,DDx              | [21206dd6bf](https://linux-hardware.org/?probe=21206dd6bf) | Jun 14, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [527587d2b9](https://linux-hardware.org/?probe=527587d2b9) | Jun 14, 2022 |
| Lenovo        | ThinkPad T550 20CK003HMD    | [ea8155f580](https://linux-hardware.org/?probe=ea8155f580) | Jun 14, 2022 |
| Dell          | Latitude E7440              | [6bbb1944af](https://linux-hardware.org/?probe=6bbb1944af) | Jun 12, 2022 |
| Google        | Babytiger                   | [18f6f97122](https://linux-hardware.org/?probe=18f6f97122) | Jun 12, 2022 |
| HP            | EliteBook 2560p             | [5f1e0dfee7](https://linux-hardware.org/?probe=5f1e0dfee7) | Jun 09, 2022 |
| HP            | EliteBook 8570p             | [bd545aec1b](https://linux-hardware.org/?probe=bd545aec1b) | Jun 09, 2022 |
| Acer          | Aspire ES1-523              | [242fc61e3a](https://linux-hardware.org/?probe=242fc61e3a) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | [b9a30cba65](https://linux-hardware.org/?probe=b9a30cba65) | Jun 08, 2022 |
| Acer          | Aspire 5732Z                | [3c14a5bf10](https://linux-hardware.org/?probe=3c14a5bf10) | Jun 08, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [0b2aab3dc7](https://linux-hardware.org/?probe=0b2aab3dc7) | Jun 04, 2022 |
| Lenovo        | V330-14ARR 81B1             | [dad2acbf49](https://linux-hardware.org/?probe=dad2acbf49) | Jun 02, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| HP            | ProBook 6450b               | [8c35a4c278](https://linux-hardware.org/?probe=8c35a4c278) | May 26, 2022 |
| Dell          | Latitude E7440              | [975715a96b](https://linux-hardware.org/?probe=975715a96b) | May 26, 2022 |
| HP            | ProBook 6450b               | [863987eb13](https://linux-hardware.org/?probe=863987eb13) | May 26, 2022 |
| HP            | ProBook 650 G1              | [d3f5e5aa45](https://linux-hardware.org/?probe=d3f5e5aa45) | May 22, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [62486fe8d6](https://linux-hardware.org/?probe=62486fe8d6) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [f0f481f187](https://linux-hardware.org/?probe=f0f481f187) | May 21, 2022 |
| SLIMBOOK      | PROX14-10                   | [b0d5e9b290](https://linux-hardware.org/?probe=b0d5e9b290) | May 19, 2022 |
| Dell          | XPS 13 9370                 | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [6efbcdabfc](https://linux-hardware.org/?probe=6efbcdabfc) | May 17, 2022 |
| Lenovo        | ThinkPad T480 20L6S14Y01    | [d3f3fff089](https://linux-hardware.org/?probe=d3f3fff089) | May 16, 2022 |
| Dell          | Precision 5750              | [11e888b7d9](https://linux-hardware.org/?probe=11e888b7d9) | May 10, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [591d3fa922](https://linux-hardware.org/?probe=591d3fa922) | May 07, 2022 |
| Packard Be... | EasyNote TE69BM             | [ed538d5b79](https://linux-hardware.org/?probe=ed538d5b79) | May 07, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [ac5b1123ad](https://linux-hardware.org/?probe=ac5b1123ad) | Apr 30, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [8694f28b60](https://linux-hardware.org/?probe=8694f28b60) | Apr 25, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [0cd6fe25ec](https://linux-hardware.org/?probe=0cd6fe25ec) | Apr 22, 2022 |
| Acer          | Aspire E5-553               | [1c736596fa](https://linux-hardware.org/?probe=1c736596fa) | Apr 21, 2022 |
| Lenovo        | B575e 36852EG               | [8f5e5f427a](https://linux-hardware.org/?probe=8f5e5f427a) | Apr 18, 2022 |
| Lenovo        | B575e 36852EG               | [4731516b58](https://linux-hardware.org/?probe=4731516b58) | Apr 18, 2022 |
| Lenovo        | ThinkPad T440 20B7S1EV00    | [b035e7ae3e](https://linux-hardware.org/?probe=b035e7ae3e) | Apr 16, 2022 |
| HP            | EliteBook 820 G3            | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| MSI           | GF63 Thin 10SC              | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Acer          | Aspire V5-573G              | [2b608bcde8](https://linux-hardware.org/?probe=2b608bcde8) | Apr 04, 2022 |
| Lenovo        | ThinkPad X390 20Q0002LMX    | [22aaabe433](https://linux-hardware.org/?probe=22aaabe433) | Apr 03, 2022 |
| HP            | Laptop 14-dk1xxx            | [0ba5fd01fa](https://linux-hardware.org/?probe=0ba5fd01fa) | Mar 30, 2022 |
| HP            | Laptop 15-bw0xx             | [b9a21aea35](https://linux-hardware.org/?probe=b9a21aea35) | Mar 29, 2022 |
| Lenovo        | E31-80 80MX                 | [8dc93e34e9](https://linux-hardware.org/?probe=8dc93e34e9) | Mar 25, 2022 |
| HP            | Pavilion Notebook           | [3bf42ed5a6](https://linux-hardware.org/?probe=3bf42ed5a6) | Mar 24, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [72da14a2b2](https://linux-hardware.org/?probe=72da14a2b2) | Mar 23, 2022 |
| MSI           | Modern 15 A5M               | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| Apple         | MacBookPro11,5              | [abc4597fe1](https://linux-hardware.org/?probe=abc4597fe1) | Mar 18, 2022 |
| Notebook      | P65xHP                      | [3222aab43a](https://linux-hardware.org/?probe=3222aab43a) | Mar 16, 2022 |
| Acer          | Aspire 3830T                | [bad3a5c2d7](https://linux-hardware.org/?probe=bad3a5c2d7) | Mar 15, 2022 |
| HP            | EliteBook 850 G5            | [ab88a095ac](https://linux-hardware.org/?probe=ab88a095ac) | Mar 10, 2022 |
| Dell          | Latitude E6410              | [d4fa7879a4](https://linux-hardware.org/?probe=d4fa7879a4) | Mar 09, 2022 |
| Dell          | Precision M4800             | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Acer          | Swift SF314-42              | [e7d10ddac0](https://linux-hardware.org/?probe=e7d10ddac0) | Mar 04, 2022 |
| Dell          | Latitude E6410              | [6748e5a7aa](https://linux-hardware.org/?probe=6748e5a7aa) | Feb 27, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [30879c05cc](https://linux-hardware.org/?probe=30879c05cc) | Feb 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [505e1dc8cc](https://linux-hardware.org/?probe=505e1dc8cc) | Feb 21, 2022 |
| Lenovo        | ThinkPad L530 24812SG       | [6eb3e0ed53](https://linux-hardware.org/?probe=6eb3e0ed53) | Feb 19, 2022 |
| HP            | Pavilion g6                 | [3971fd709d](https://linux-hardware.org/?probe=3971fd709d) | Feb 13, 2022 |
| Acer          | Aspire E5-575               | [3e75911df8](https://linux-hardware.org/?probe=3e75911df8) | Feb 12, 2022 |
| Apple         | MacBookPro7,1               | [b059819620](https://linux-hardware.org/?probe=b059819620) | Feb 11, 2022 |
| Apple         | MacBookPro7,1               | [87f4740598](https://linux-hardware.org/?probe=87f4740598) | Feb 11, 2022 |
| Toshiba       | Satellite L40               | [ba6d18935b](https://linux-hardware.org/?probe=ba6d18935b) | Feb 08, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [23c6243856](https://linux-hardware.org/?probe=23c6243856) | Feb 05, 2022 |
| Medion        | P7612                       | [e1c076ee06](https://linux-hardware.org/?probe=e1c076ee06) | Feb 03, 2022 |
| HP            | Compaq Presario CQ71        | [436407f045](https://linux-hardware.org/?probe=436407f045) | Feb 01, 2022 |
| Lenovo        | B50-50 80S2                 | [7602963c65](https://linux-hardware.org/?probe=7602963c65) | Feb 01, 2022 |
| Dell          | Latitude E6540              | [fe6720f0de](https://linux-hardware.org/?probe=fe6720f0de) | Jan 30, 2022 |
| Dell          | Latitude E6540              | [7c972de545](https://linux-hardware.org/?probe=7c972de545) | Jan 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [478d5281bd](https://linux-hardware.org/?probe=478d5281bd) | Jan 29, 2022 |
| HP            | Pavilion dv7                | [e6ec9b5f6a](https://linux-hardware.org/?probe=e6ec9b5f6a) | Jan 26, 2022 |
| Medion        | P7612                       | [50be4d531e](https://linux-hardware.org/?probe=50be4d531e) | Jan 25, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [298ddd1139](https://linux-hardware.org/?probe=298ddd1139) | Jan 24, 2022 |
| HP            | EliteBook 840 G3            | [82cce77f87](https://linux-hardware.org/?probe=82cce77f87) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| DukaPC        | Notebook                    | [21b4827b4b](https://linux-hardware.org/?probe=21b4827b4b) | Jan 21, 2022 |
| Acer          | Aspire F5-572G              | [221a91f679](https://linux-hardware.org/?probe=221a91f679) | Jan 19, 2022 |
| Lenovo        | ThinkPad E595 20NFCTO1WW    | [80906dc02b](https://linux-hardware.org/?probe=80906dc02b) | Jan 19, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [cc39f1fd96](https://linux-hardware.org/?probe=cc39f1fd96) | Jan 18, 2022 |
| IBM           | ThinkPad T40 237342G        | [2c96b391e2](https://linux-hardware.org/?probe=2c96b391e2) | Jan 16, 2022 |
| IBM           | ThinkPad T40 237342G        | [5c4e8748ef](https://linux-hardware.org/?probe=5c4e8748ef) | Jan 16, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [4ebb815948](https://linux-hardware.org/?probe=4ebb815948) | Jan 15, 2022 |
| HP            | Pavilion g7                 | [6efd331acf](https://linux-hardware.org/?probe=6efd331acf) | Jan 14, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [4cefa23802](https://linux-hardware.org/?probe=4cefa23802) | Jan 14, 2022 |
| Acer          | Aspire E5-553               | [149c0538ca](https://linux-hardware.org/?probe=149c0538ca) | Jan 13, 2022 |
| Lenovo        | M30-70 80H8                 | [2f61d772a4](https://linux-hardware.org/?probe=2f61d772a4) | Jan 12, 2022 |
| Lenovo        | Y50-70 20378                | [ab93bc517a](https://linux-hardware.org/?probe=ab93bc517a) | Jan 12, 2022 |
| Razer         | Blade                       | [afad6aaa95](https://linux-hardware.org/?probe=afad6aaa95) | Jan 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1f327abc43](https://linux-hardware.org/?probe=1f327abc43) | Jan 05, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [53a3989606](https://linux-hardware.org/?probe=53a3989606) | Jan 03, 2022 |
| Acer          | Aspire V5-573G              | [a7e3940936](https://linux-hardware.org/?probe=a7e3940936) | Jan 02, 2022 |
| Dell          | Inspiron 7720               | [4e1ebc00ff](https://linux-hardware.org/?probe=4e1ebc00ff) | Jan 02, 2022 |
| Apple         | MacBookAir7,2               | [6246bb8ef6](https://linux-hardware.org/?probe=6246bb8ef6) | Dec 31, 2021 |
| Lenovo        | V330-14ARR 81B1             | [290d6b4ad5](https://linux-hardware.org/?probe=290d6b4ad5) | Dec 29, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [13f35d1d12](https://linux-hardware.org/?probe=13f35d1d12) | Dec 26, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [369d18645c](https://linux-hardware.org/?probe=369d18645c) | Dec 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [e68ec90909](https://linux-hardware.org/?probe=e68ec90909) | Dec 24, 2021 |
| Medion        | P6630                       | [de245dfdb6](https://linux-hardware.org/?probe=de245dfdb6) | Dec 23, 2021 |
| Notebook      | N24_25JU                    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| Quanta        | MW1/HW1                     | [06bcb3603d](https://linux-hardware.org/?probe=06bcb3603d) | Dec 17, 2021 |
| ASUSTek       | K53SV                       | [be7844ea44](https://linux-hardware.org/?probe=be7844ea44) | Dec 17, 2021 |
| Lenovo        | ThinkPad T460s 20FAS05Q0... | [3a4b9beb1d](https://linux-hardware.org/?probe=3a4b9beb1d) | Dec 12, 2021 |
| Toshiba       | Satellite P850              | [bfc37f531a](https://linux-hardware.org/?probe=bfc37f531a) | Dec 11, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| Lenovo        | ThinkPad T470s 20HF004UM... | [e7144e5f86](https://linux-hardware.org/?probe=e7144e5f86) | Dec 09, 2021 |
| Fujitsu Si... | LIFEBOOK E8420              | [7ff3493cfe](https://linux-hardware.org/?probe=7ff3493cfe) | Dec 08, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| DukaPC        | Notebook                    | [cfb399153a](https://linux-hardware.org/?probe=cfb399153a) | Dec 01, 2021 |
| Razer         | Blade Stealth               | [54acf9844b](https://linux-hardware.org/?probe=54acf9844b) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [c224ffa45a](https://linux-hardware.org/?probe=c224ffa45a) | Nov 23, 2021 |
| Toshiba       | Satellite U300              | [827ec6ed62](https://linux-hardware.org/?probe=827ec6ed62) | Nov 21, 2021 |
| Dell          | Inspiron 7572               | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| HUAWEI        | KLVL-WXX9                   | [c80aeaf7b0](https://linux-hardware.org/?probe=c80aeaf7b0) | Nov 17, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [52eef25506](https://linux-hardware.org/?probe=52eef25506) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [7252f23e5f](https://linux-hardware.org/?probe=7252f23e5f) | Nov 15, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [1a20afde4b](https://linux-hardware.org/?probe=1a20afde4b) | Nov 15, 2021 |
| Acer          | Aspire 5810T                | [c41d1671bc](https://linux-hardware.org/?probe=c41d1671bc) | Nov 14, 2021 |
| Lenovo        | ThinkPad R61 8935W7T        | [bef030b1ef](https://linux-hardware.org/?probe=bef030b1ef) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [e03bf03f1d](https://linux-hardware.org/?probe=e03bf03f1d) | Nov 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [1def6bd5d8](https://linux-hardware.org/?probe=1def6bd5d8) | Nov 10, 2021 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [d2a33ad9d9](https://linux-hardware.org/?probe=d2a33ad9d9) | Nov 07, 2021 |
| HP            | Pavilion g7                 | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Apple         | MacBookPro14,1              | [68ebc1af79](https://linux-hardware.org/?probe=68ebc1af79) | Oct 28, 2021 |
| Lenovo        | ThinkPad T430s 23561R0      | [bef1593d06](https://linux-hardware.org/?probe=bef1593d06) | Oct 22, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [14d159c564](https://linux-hardware.org/?probe=14d159c564) | Oct 20, 2021 |
| Unknown       | Unknown                     | [a6e5e7b6ef](https://linux-hardware.org/?probe=a6e5e7b6ef) | Oct 18, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [a7fa6a8110](https://linux-hardware.org/?probe=a7fa6a8110) | Oct 14, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [df32df0b62](https://linux-hardware.org/?probe=df32df0b62) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [c7239a1379](https://linux-hardware.org/?probe=c7239a1379) | Oct 13, 2021 |
| Toshiba       | Satellite P55W-C            | [f16be2ec1b](https://linux-hardware.org/?probe=f16be2ec1b) | Oct 13, 2021 |
| HP            | Pavilion g7                 | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| Acer          | Aspire A315-41              | [3d5d3ddf84](https://linux-hardware.org/?probe=3d5d3ddf84) | Oct 09, 2021 |
| Lenovo        | ThinkPad X201T 3113CC7      | [47f63d40d5](https://linux-hardware.org/?probe=47f63d40d5) | Oct 09, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [93c695e5ba](https://linux-hardware.org/?probe=93c695e5ba) | Oct 08, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | [85a242883c](https://linux-hardware.org/?probe=85a242883c) | Oct 05, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [56ce2c44cb](https://linux-hardware.org/?probe=56ce2c44cb) | Oct 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [4d0eb4ccf2](https://linux-hardware.org/?probe=4d0eb4ccf2) | Oct 04, 2021 |
| Lenovo        | V330-14ARR 81B1             | [c8a0e5de69](https://linux-hardware.org/?probe=c8a0e5de69) | Oct 04, 2021 |
| HUAWEI        | EUL-WX9                     | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| Lenovo        | ThinkPad X260 20F5S31G00    | [575dd64064](https://linux-hardware.org/?probe=575dd64064) | Oct 01, 2021 |
| HP            | Pavilion dv7                | [31b035faec](https://linux-hardware.org/?probe=31b035faec) | Sep 28, 2021 |
| Acer          | Aspire 5810T                | [be3f4d5a01](https://linux-hardware.org/?probe=be3f4d5a01) | Sep 26, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [edfae5b796](https://linux-hardware.org/?probe=edfae5b796) | Sep 25, 2021 |
| HUAWEI        | MACHC-WAX9                  | [e2fc9d2585](https://linux-hardware.org/?probe=e2fc9d2585) | Sep 23, 2021 |
| Dell          | XPS 13 9370                 | [5df047615c](https://linux-hardware.org/?probe=5df047615c) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | [d7ccece3d4](https://linux-hardware.org/?probe=d7ccece3d4) | Sep 22, 2021 |
| HP            | ProBook 650 G1              | [466841a201](https://linux-hardware.org/?probe=466841a201) | Sep 22, 2021 |
| HP            | ZBook 15                    | [206882306c](https://linux-hardware.org/?probe=206882306c) | Sep 20, 2021 |
| Lenovo        | V130-15IKB 81HN             | [f427b869d9](https://linux-hardware.org/?probe=f427b869d9) | Sep 17, 2021 |
| Lenovo        | ThinkPad X220 4291WAY       | [ca0ab89977](https://linux-hardware.org/?probe=ca0ab89977) | Sep 16, 2021 |
| Lenovo        | ThinkPad W541 20EFS01B09    | [8dd2c7497e](https://linux-hardware.org/?probe=8dd2c7497e) | Sep 13, 2021 |
| Dell          | Inspiron 3583               | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| HP            | Pavilion dv7                | [2fd3b811f6](https://linux-hardware.org/?probe=2fd3b811f6) | Sep 12, 2021 |
| Dell          | XPS 15 9510                 | [1b80533734](https://linux-hardware.org/?probe=1b80533734) | Sep 11, 2021 |
| Dell          | XPS 15 9510                 | [4befd2306c](https://linux-hardware.org/?probe=4befd2306c) | Sep 11, 2021 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5cf3ed1411](https://linux-hardware.org/?probe=5cf3ed1411) | Aug 31, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | [70585e2360](https://linux-hardware.org/?probe=70585e2360) | Aug 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [9c0457479f](https://linux-hardware.org/?probe=9c0457479f) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [23b7937411](https://linux-hardware.org/?probe=23b7937411) | Aug 29, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [9382443dc7](https://linux-hardware.org/?probe=9382443dc7) | Aug 27, 2021 |
| Google        | Relm                        | [12475037ed](https://linux-hardware.org/?probe=12475037ed) | Aug 27, 2021 |
| Google        | Relm                        | [36e7a1d7a1](https://linux-hardware.org/?probe=36e7a1d7a1) | Aug 26, 2021 |
| HP            | ProBook 650 G1              | [61f6289d2c](https://linux-hardware.org/?probe=61f6289d2c) | Aug 26, 2021 |
| Lenovo        | ThinkPad X230 2325AN3       | [d6b5ef49af](https://linux-hardware.org/?probe=d6b5ef49af) | Aug 24, 2021 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [900b0ce643](https://linux-hardware.org/?probe=900b0ce643) | Aug 24, 2021 |
| HP            | ZBook 15 G6                 | [93ec0ceb52](https://linux-hardware.org/?probe=93ec0ceb52) | Aug 23, 2021 |
| Lenovo        | ThinkPad E595 20NF001HMX    | [8e75269d33](https://linux-hardware.org/?probe=8e75269d33) | Aug 20, 2021 |
| Lenovo        | G550 2958                   | [5207c5584c](https://linux-hardware.org/?probe=5207c5584c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | [b7b363db20](https://linux-hardware.org/?probe=b7b363db20) | Aug 15, 2021 |
| HP            | ProBook 445 G7              | [e42e169a72](https://linux-hardware.org/?probe=e42e169a72) | Aug 15, 2021 |
| HP            | Notebook                    | [be1a21a391](https://linux-hardware.org/?probe=be1a21a391) | Aug 14, 2021 |
| GPD           | P2 MAX                      | [78f79b2790](https://linux-hardware.org/?probe=78f79b2790) | Jul 31, 2021 |
| ASUSTek       | GL702VM                     | [bb9d228646](https://linux-hardware.org/?probe=bb9d228646) | Jul 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [a02dac8dff](https://linux-hardware.org/?probe=a02dac8dff) | Jul 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | [e52365f866](https://linux-hardware.org/?probe=e52365f866) | Jul 21, 2021 |
| Lenovo        | ThinkPad X240 20AMS4P300    | [704fb2e1d1](https://linux-hardware.org/?probe=704fb2e1d1) | Jul 21, 2021 |
| Dell          | Latitude 7370               | [b10d4c18f2](https://linux-hardware.org/?probe=b10d4c18f2) | Jul 19, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | [7a03dbd869](https://linux-hardware.org/?probe=7a03dbd869) | Jul 17, 2021 |
| Lenovo        | ThinkPad T460s 20F9003UM... | [ce58f3f770](https://linux-hardware.org/?probe=ce58f3f770) | Jul 16, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [a56195f1f1](https://linux-hardware.org/?probe=a56195f1f1) | Jul 13, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [440841d04a](https://linux-hardware.org/?probe=440841d04a) | Jul 12, 2021 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [3b106f1da0](https://linux-hardware.org/?probe=3b106f1da0) | Jul 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [f8872c9e84](https://linux-hardware.org/?probe=f8872c9e84) | Jul 05, 2021 |
| AMI           | Cherry Trail CR             | [4e6f9ccc6c](https://linux-hardware.org/?probe=4e6f9ccc6c) | Jul 05, 2021 |
| DukaPC        | Notebook                    | [6d87054512](https://linux-hardware.org/?probe=6d87054512) | Jul 02, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| Timi          | TM1703                      | [bd3756811d](https://linux-hardware.org/?probe=bd3756811d) | Jun 26, 2021 |
| DukaPC        | Notebook                    | [c29d208cdf](https://linux-hardware.org/?probe=c29d208cdf) | Jun 24, 2021 |
| Lenovo        | ThinkPad T420 4236Y19       | [48927432b4](https://linux-hardware.org/?probe=48927432b4) | Jun 20, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d8ad69d368](https://linux-hardware.org/?probe=d8ad69d368) | Jun 15, 2021 |
| Lenovo        | ThinkPad T440s 20ARS0Y70... | [5e57af6782](https://linux-hardware.org/?probe=5e57af6782) | Jun 11, 2021 |
| Lenovo        | ThinkPad T420 4236PFG       | [fa5abfccf8](https://linux-hardware.org/?probe=fa5abfccf8) | Jun 04, 2021 |
| HP            | Compaq Presario CQ71        | [d4deb2b08d](https://linux-hardware.org/?probe=d4deb2b08d) | Jun 01, 2021 |
| Dell          | Latitude E6520              | [d1d0976880](https://linux-hardware.org/?probe=d1d0976880) | May 31, 2021 |
| Lenovo        | ThinkPad T400 647358G       | [b4f44d7932](https://linux-hardware.org/?probe=b4f44d7932) | May 29, 2021 |
| Toshiba       | Satellite C660              | [58d3740c30](https://linux-hardware.org/?probe=58d3740c30) | May 28, 2021 |
| Acer          | Aspire E5-553               | [70037bddcb](https://linux-hardware.org/?probe=70037bddcb) | May 27, 2021 |
| LAMINA        | T-1012B NORD                | [71e70e946a](https://linux-hardware.org/?probe=71e70e946a) | May 25, 2021 |
| LAMINA        | T-1012B NORD                | [9dc2932064](https://linux-hardware.org/?probe=9dc2932064) | May 24, 2021 |
| ASUSTek       | X553SA                      | [c470382d2a](https://linux-hardware.org/?probe=c470382d2a) | May 24, 2021 |
| ASUSTek       | X553SA                      | [31d6a914fd](https://linux-hardware.org/?probe=31d6a914fd) | May 24, 2021 |
| Acer          | Aspire E5-511               | [9edec55620](https://linux-hardware.org/?probe=9edec55620) | May 23, 2021 |
| Acer          | Aspire E5-511               | [e20c93a2c1](https://linux-hardware.org/?probe=e20c93a2c1) | May 23, 2021 |
| Lenovo        | ThinkPad X240 20AMS5FJ00    | [a9e4c7793b](https://linux-hardware.org/?probe=a9e4c7793b) | May 18, 2021 |
| eMachines     | E725                        | [329f8f580e](https://linux-hardware.org/?probe=329f8f580e) | May 14, 2021 |
| ASUSTek       | K95VM                       | [58d4ed3c2b](https://linux-hardware.org/?probe=58d4ed3c2b) | May 10, 2021 |
| HP            | 15                          | [a13c097d59](https://linux-hardware.org/?probe=a13c097d59) | May 09, 2021 |
| HP            | 15                          | [c3cdcdab60](https://linux-hardware.org/?probe=c3cdcdab60) | May 09, 2021 |
| Alienware     | 17 R2                       | [a8470edc65](https://linux-hardware.org/?probe=a8470edc65) | May 06, 2021 |
| ASUSTek       | G74Sx                       | [73c1eaa647](https://linux-hardware.org/?probe=73c1eaa647) | Apr 29, 2021 |
| Lenovo        | ThinkPad T520 4243PC2       | [915d41f361](https://linux-hardware.org/?probe=915d41f361) | Apr 29, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [e259d34a4c](https://linux-hardware.org/?probe=e259d34a4c) | Apr 28, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | [e2f8b2beda](https://linux-hardware.org/?probe=e2f8b2beda) | Apr 25, 2021 |
| Lenovo        | ThinkPad T530 24295L4       | [684f1471b1](https://linux-hardware.org/?probe=684f1471b1) | Apr 23, 2021 |
| Lenovo        | E31-80 80MX                 | [8aedfd9f4c](https://linux-hardware.org/?probe=8aedfd9f4c) | Apr 21, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [bd14a696eb](https://linux-hardware.org/?probe=bd14a696eb) | Apr 20, 2021 |
| Lenovo        | ThinkPad T520 42434YG       | [8e0b4ee3a1](https://linux-hardware.org/?probe=8e0b4ee3a1) | Apr 17, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | [49e1959064](https://linux-hardware.org/?probe=49e1959064) | Apr 16, 2021 |
| Lenovo        | ThinkPad X220 4291SVC       | [b2853266e8](https://linux-hardware.org/?probe=b2853266e8) | Apr 15, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [4b127c0ba4](https://linux-hardware.org/?probe=4b127c0ba4) | Apr 11, 2021 |
| HP            | Laptop 15-da1xxx            | [a844e710cc](https://linux-hardware.org/?probe=a844e710cc) | Apr 09, 2021 |
| Lenovo        | ThinkPad T60 20076RG        | [aa3ea77acf](https://linux-hardware.org/?probe=aa3ea77acf) | Apr 08, 2021 |
| HP            | G72                         | [2ab4eb5fcd](https://linux-hardware.org/?probe=2ab4eb5fcd) | Apr 05, 2021 |
| ASUSTek       | K95VM                       | [81a01884d2](https://linux-hardware.org/?probe=81a01884d2) | Mar 24, 2021 |
| Lenovo        | ThinkPad W520 4284Y54       | [8d564e495b](https://linux-hardware.org/?probe=8d564e495b) | Mar 23, 2021 |
| Toshiba       | Satellite L350D             | [b083513b72](https://linux-hardware.org/?probe=b083513b72) | Mar 23, 2021 |
| Acer          | Aspire E5-553               | [0c21dc1b96](https://linux-hardware.org/?probe=0c21dc1b96) | Mar 19, 2021 |
| HP            | Pavilion dm1                | [438cf03315](https://linux-hardware.org/?probe=438cf03315) | Mar 18, 2021 |
| Lenovo        | Yoga 700-14ISK 80QD         | [7e7a4bc992](https://linux-hardware.org/?probe=7e7a4bc992) | Mar 18, 2021 |
| Lenovo        | ThinkPad T480s 20L8S4T80... | [1b8a078a19](https://linux-hardware.org/?probe=1b8a078a19) | Mar 16, 2021 |
| HP            | EliteBook 830 G5            | [248eb896a0](https://linux-hardware.org/?probe=248eb896a0) | Mar 15, 2021 |
| HP            | Compaq Presario CQ60        | [e4613a6f75](https://linux-hardware.org/?probe=e4613a6f75) | Mar 15, 2021 |
| Dell          | Latitude E5250              | [22067e0909](https://linux-hardware.org/?probe=22067e0909) | Mar 13, 2021 |
| Dell          | Latitude E5250              | [df9d913f0f](https://linux-hardware.org/?probe=df9d913f0f) | Mar 13, 2021 |
| HP            | Pavilion dv9700             | [f55ec4dd18](https://linux-hardware.org/?probe=f55ec4dd18) | Mar 11, 2021 |
| Dell          | XPS 13 9370                 | [865e070587](https://linux-hardware.org/?probe=865e070587) | Mar 10, 2021 |
| Dell          | Latitude E5250              | [78f0a24d9a](https://linux-hardware.org/?probe=78f0a24d9a) | Mar 07, 2021 |
| Acer          | Aspire E5-575G              | [18240d24d8](https://linux-hardware.org/?probe=18240d24d8) | Mar 06, 2021 |
| Toshiba       | Satellite L350D             | [ef8a29af20](https://linux-hardware.org/?probe=ef8a29af20) | Mar 05, 2021 |
| Acer          | Aspire E5-553               | [74e6da0017](https://linux-hardware.org/?probe=74e6da0017) | Feb 27, 2021 |
| HP            | 630                         | [6803747e34](https://linux-hardware.org/?probe=6803747e34) | Feb 22, 2021 |
| HP            | 630                         | [8b04fe81aa](https://linux-hardware.org/?probe=8b04fe81aa) | Feb 22, 2021 |
| Lenovo        | ThinkPad T61 7661W1D        | [6db91fdd34](https://linux-hardware.org/?probe=6db91fdd34) | Feb 17, 2021 |
| Lenovo        | 3000 G530 444622G           | [3ef99e25df](https://linux-hardware.org/?probe=3ef99e25df) | Feb 16, 2021 |
| Lenovo        | ThinkPad X240 20AMA2AE00    | [2730f6215a](https://linux-hardware.org/?probe=2730f6215a) | Feb 12, 2021 |
| Dell          | XPS 13 9360                 | [564f71d6f3](https://linux-hardware.org/?probe=564f71d6f3) | Feb 10, 2021 |
| Acer          | Aspire E5-553               | [ab7532985d](https://linux-hardware.org/?probe=ab7532985d) | Feb 05, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [ed806c00b2](https://linux-hardware.org/?probe=ed806c00b2) | Feb 04, 2021 |
| HP            | EliteBook 2560p             | [f741035d0d](https://linux-hardware.org/?probe=f741035d0d) | Feb 02, 2021 |
| HP            | EliteBook 840 G5            | [19ef5f3adb](https://linux-hardware.org/?probe=19ef5f3adb) | Jan 29, 2021 |
| Dell          | Latitude E7440              | [ee2c17a895](https://linux-hardware.org/?probe=ee2c17a895) | Jan 26, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [964b7c1b1f](https://linux-hardware.org/?probe=964b7c1b1f) | Jan 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [82da77953a](https://linux-hardware.org/?probe=82da77953a) | Jan 19, 2021 |
| Dell          | Latitude 5500               | [d7e06bd87b](https://linux-hardware.org/?probe=d7e06bd87b) | Jan 18, 2021 |
| Dell          | Latitude 5500               | [f40a2d50bc](https://linux-hardware.org/?probe=f40a2d50bc) | Jan 16, 2021 |
| Quanta        | MW1/HW1                     | [ebab0a47f8](https://linux-hardware.org/?probe=ebab0a47f8) | Jan 16, 2021 |
| Lenovo        | ThinkPad P52 20M9001GMX     | [ffdee2c6e0](https://linux-hardware.org/?probe=ffdee2c6e0) | Jan 11, 2021 |
| Dell          | XPS 13 9300                 | [229b46a693](https://linux-hardware.org/?probe=229b46a693) | Jan 10, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [fa963386d8](https://linux-hardware.org/?probe=fa963386d8) | Jan 07, 2021 |
| Toshiba       | Satellite L40               | [bd26bbbe43](https://linux-hardware.org/?probe=bd26bbbe43) | Jan 06, 2021 |
| Lenovo        | G570 4334                   | [c643363b80](https://linux-hardware.org/?probe=c643363b80) | Jan 03, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2ed1a3283e](https://linux-hardware.org/?probe=2ed1a3283e) | Jan 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [c0c38c5aee](https://linux-hardware.org/?probe=c0c38c5aee) | Dec 30, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [65fe7eb049](https://linux-hardware.org/?probe=65fe7eb049) | Dec 30, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [c3f9fc25d4](https://linux-hardware.org/?probe=c3f9fc25d4) | Dec 29, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [dbc2669fc0](https://linux-hardware.org/?probe=dbc2669fc0) | Dec 28, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [f514e54057](https://linux-hardware.org/?probe=f514e54057) | Dec 28, 2020 |
| ASUSTek       | PU401LAC                    | [c5bf49eabf](https://linux-hardware.org/?probe=c5bf49eabf) | Dec 26, 2020 |
| HP            | EliteBook 850 G5            | [ce2a32dd24](https://linux-hardware.org/?probe=ce2a32dd24) | Dec 22, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3e419467e2](https://linux-hardware.org/?probe=3e419467e2) | Dec 22, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [87c08ecbb6](https://linux-hardware.org/?probe=87c08ecbb6) | Dec 22, 2020 |
| Notebook      | W54_55SU1,SUW               | [52e86fd2a9](https://linux-hardware.org/?probe=52e86fd2a9) | Dec 20, 2020 |
| Lenovo        | ThinkPad T490s 20NX001PM... | [af7d2d4eb5](https://linux-hardware.org/?probe=af7d2d4eb5) | Dec 20, 2020 |
| HP            | EliteBook 845 G7 Noteboo... | [14a84d3948](https://linux-hardware.org/?probe=14a84d3948) | Dec 20, 2020 |
| Lenovo        | ThinkPad T520 4243W54       | [15862aca5c](https://linux-hardware.org/?probe=15862aca5c) | Dec 20, 2020 |
| Lenovo        | ThinkPad X260 20F5S31G00    | [01b87f6602](https://linux-hardware.org/?probe=01b87f6602) | Dec 18, 2020 |
| Lenovo        | Unknown                     | [92b19a0db9](https://linux-hardware.org/?probe=92b19a0db9) | Dec 18, 2020 |
| Dell          | Latitude E7270              | [bac2c2820f](https://linux-hardware.org/?probe=bac2c2820f) | Dec 17, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [5dfa78d268](https://linux-hardware.org/?probe=5dfa78d268) | Dec 15, 2020 |
| HP            | ProBook 650 G5              | [56c46edc3f](https://linux-hardware.org/?probe=56c46edc3f) | Dec 13, 2020 |
| HP            | ProBook 650 G5              | [a035f76fcb](https://linux-hardware.org/?probe=a035f76fcb) | Dec 12, 2020 |
| Acer          | Extensa 2519                | [17bdd3b68f](https://linux-hardware.org/?probe=17bdd3b68f) | Dec 10, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [e9f3972862](https://linux-hardware.org/?probe=e9f3972862) | Dec 04, 2020 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [f98c566bb6](https://linux-hardware.org/?probe=f98c566bb6) | Dec 03, 2020 |
| Lenovo        | ThinkPad X220 4291SVC       | [ff051ee214](https://linux-hardware.org/?probe=ff051ee214) | Dec 01, 2020 |
| Dell          | Latitude E6540              | [5a0fbaa262](https://linux-hardware.org/?probe=5a0fbaa262) | Nov 28, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [8b31225bd7](https://linux-hardware.org/?probe=8b31225bd7) | Nov 27, 2020 |
| Apple         | MacBookPro7,1               | [ad6bb1f253](https://linux-hardware.org/?probe=ad6bb1f253) | Nov 24, 2020 |
| Lenovo        | ThinkPad P52 20M9001MMD     | [72ba2ae6cb](https://linux-hardware.org/?probe=72ba2ae6cb) | Nov 19, 2020 |
| Acer          | Aspire V3-575G              | [56c2638b77](https://linux-hardware.org/?probe=56c2638b77) | Nov 18, 2020 |
| Dell          | System XPS L321X            | [3fb9a4373c](https://linux-hardware.org/?probe=3fb9a4373c) | Nov 18, 2020 |
| Lenovo        | ThinkPad T530 24292VG       | [3460614c7f](https://linux-hardware.org/?probe=3460614c7f) | Nov 15, 2020 |
| Lenovo        | ThinkPad W541 20EFS01B09    | [ee5da1d9b0](https://linux-hardware.org/?probe=ee5da1d9b0) | Nov 10, 2020 |
| Lenovo        | ThinkPad X301 2776LEG       | [2c4aa61663](https://linux-hardware.org/?probe=2c4aa61663) | Nov 09, 2020 |
| Dell          | XPS 13 9370                 | [b75b281fee](https://linux-hardware.org/?probe=b75b281fee) | Nov 08, 2020 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [de9ea1422c](https://linux-hardware.org/?probe=de9ea1422c) | Nov 08, 2020 |
| HP            | Pavilion Notebook           | [1698bf3366](https://linux-hardware.org/?probe=1698bf3366) | Nov 07, 2020 |
| HP            | EliteBook 820 G3            | [e34831e959](https://linux-hardware.org/?probe=e34831e959) | Nov 07, 2020 |
| Dell          | XPS 15 9570                 | [bb40872a6b](https://linux-hardware.org/?probe=bb40872a6b) | Nov 05, 2020 |
| HP            | ProBook 4720s               | [acb46376ad](https://linux-hardware.org/?probe=acb46376ad) | Nov 04, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [d65f8070e0](https://linux-hardware.org/?probe=d65f8070e0) | Nov 03, 2020 |
| HP            | Compaq 8510p                | [587f5db4a7](https://linux-hardware.org/?probe=587f5db4a7) | Nov 02, 2020 |
| Dell          | XPS 15 9560                 | [5e06a37540](https://linux-hardware.org/?probe=5e06a37540) | Nov 01, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [1213098826](https://linux-hardware.org/?probe=1213098826) | Oct 30, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [de02478ef0](https://linux-hardware.org/?probe=de02478ef0) | Oct 29, 2020 |
| Lenovo        | E31-80 80MX                 | [d56dacea36](https://linux-hardware.org/?probe=d56dacea36) | Oct 29, 2020 |
| Razer         | Blade                       | [7aef75c2c6](https://linux-hardware.org/?probe=7aef75c2c6) | Oct 28, 2020 |
| Dell          | Vostro 3558                 | [eda9a94c60](https://linux-hardware.org/?probe=eda9a94c60) | Oct 28, 2020 |
| Acer          | Nitro AN515-53              | [08235cd1ad](https://linux-hardware.org/?probe=08235cd1ad) | Oct 25, 2020 |
| Acer          | Nitro AN515-53              | [80a32fe04b](https://linux-hardware.org/?probe=80a32fe04b) | Oct 24, 2020 |
| Dell          | Vostro 3558                 | [e22529c904](https://linux-hardware.org/?probe=e22529c904) | Oct 23, 2020 |
| Apple         | MacBookPro5,5               | [b7c6f0c157](https://linux-hardware.org/?probe=b7c6f0c157) | Oct 22, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [cbd374b1d9](https://linux-hardware.org/?probe=cbd374b1d9) | Oct 22, 2020 |
| Toshiba       | Satellite L40               | [3d02e46571](https://linux-hardware.org/?probe=3d02e46571) | Oct 22, 2020 |
| HP            | EliteBook 850 G5            | [1a2d14ded4](https://linux-hardware.org/?probe=1a2d14ded4) | Oct 20, 2020 |
| HP            | Pavilion dv6                | [6fd2a79436](https://linux-hardware.org/?probe=6fd2a79436) | Oct 18, 2020 |
| Toshiba       | Satellite P50-A-11J         | [720f19d566](https://linux-hardware.org/?probe=720f19d566) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | [20453e8620](https://linux-hardware.org/?probe=20453e8620) | Oct 10, 2020 |
| Acer          | Aspire V5-573               | [eee8f03871](https://linux-hardware.org/?probe=eee8f03871) | Oct 10, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [4ffeac234f](https://linux-hardware.org/?probe=4ffeac234f) | Oct 09, 2020 |
| Acer          | Nitro AN515-53              | [fe2889ef02](https://linux-hardware.org/?probe=fe2889ef02) | Oct 08, 2020 |
| Lenovo        | ThinkPad T430s 23564H3      | [bea20b3463](https://linux-hardware.org/?probe=bea20b3463) | Oct 04, 2020 |
| Acer          | Aspire 7551                 | [0524a7f258](https://linux-hardware.org/?probe=0524a7f258) | Oct 04, 2020 |
| Acer          | Aspire VN7-792G             | [908eea39dd](https://linux-hardware.org/?probe=908eea39dd) | Oct 04, 2020 |
| Acer          | Nitro AN515-53              | [a1d00d9bc3](https://linux-hardware.org/?probe=a1d00d9bc3) | Oct 03, 2020 |
| Acer          | Nitro AN515-53              | [be2aafbbae](https://linux-hardware.org/?probe=be2aafbbae) | Oct 03, 2020 |
| HP            | ProBook 650 G2              | [f04b6dbdc5](https://linux-hardware.org/?probe=f04b6dbdc5) | Oct 02, 2020 |
| HP            | ProBook 650 G2              | [7b826236e8](https://linux-hardware.org/?probe=7b826236e8) | Oct 02, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | [9a69eca48e](https://linux-hardware.org/?probe=9a69eca48e) | Oct 01, 2020 |
| Acer          | AOD270                      | [4d7f40e97b](https://linux-hardware.org/?probe=4d7f40e97b) | Sep 30, 2020 |
| Lenovo        | 3000 N200 0769B6G           | [7e9967fb0e](https://linux-hardware.org/?probe=7e9967fb0e) | Sep 30, 2020 |
| Lenovo        | ThinkPad P51 20HH001QMD     | [3b51f51354](https://linux-hardware.org/?probe=3b51f51354) | Sep 29, 2020 |
| Notebook      | W54_55SU1,SUW               | [8616e28654](https://linux-hardware.org/?probe=8616e28654) | Sep 29, 2020 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [a3846db026](https://linux-hardware.org/?probe=a3846db026) | Sep 26, 2020 |
| Lenovo        | G710 20252                  | [6d3ef693db](https://linux-hardware.org/?probe=6d3ef693db) | Sep 23, 2020 |
| HP            | Pavilion Sleekbook 15       | [d5217dd737](https://linux-hardware.org/?probe=d5217dd737) | Sep 20, 2020 |
| Google        | Liara                       | [e6434b38e5](https://linux-hardware.org/?probe=e6434b38e5) | Sep 16, 2020 |
| HP            | 620                         | [3cd40bde20](https://linux-hardware.org/?probe=3cd40bde20) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | [1f2fba4e2e](https://linux-hardware.org/?probe=1f2fba4e2e) | Sep 11, 2020 |
| MSI           | PS42 8RB                    | [46f7d12d9e](https://linux-hardware.org/?probe=46f7d12d9e) | Sep 11, 2020 |
| HP            | EliteBook 850 G5            | [826772015a](https://linux-hardware.org/?probe=826772015a) | Sep 09, 2020 |
| LG Electro... | 17Z90N-V.AA77G              | [eaeb99f180](https://linux-hardware.org/?probe=eaeb99f180) | Sep 06, 2020 |
| Apple         | MacBookPro10,1              | [3d676f563d](https://linux-hardware.org/?probe=3d676f563d) | Sep 06, 2020 |
| Lenovo        | ThinkPad X230 2325W3J       | [b076277c46](https://linux-hardware.org/?probe=b076277c46) | Sep 05, 2020 |
| Lenovo        | ThinkPad X240 20AMS39B00    | [b2f7ace5e9](https://linux-hardware.org/?probe=b2f7ace5e9) | Sep 05, 2020 |
| Notebook      | W35xSTQ_370ST               | [69960189a7](https://linux-hardware.org/?probe=69960189a7) | Sep 04, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | [392b8d8877](https://linux-hardware.org/?probe=392b8d8877) | Sep 04, 2020 |
| Lenovo        | V110-15IAP 80TG             | [74a552046a](https://linux-hardware.org/?probe=74a552046a) | Sep 02, 2020 |
| Toshiba       | Satellite L755D             | [e3aa57d80d](https://linux-hardware.org/?probe=e3aa57d80d) | Aug 30, 2020 |
| HP            | 620                         | [2abb876aa3](https://linux-hardware.org/?probe=2abb876aa3) | Aug 27, 2020 |
| Purism        | Librem 13 v2                | [23cd34d2f6](https://linux-hardware.org/?probe=23cd34d2f6) | Aug 27, 2020 |
| HP            | Pavilion dm1                | [39154c83b0](https://linux-hardware.org/?probe=39154c83b0) | Aug 27, 2020 |
| Acer          | NC-SF314-51-56Y4            | [0627a672e7](https://linux-hardware.org/?probe=0627a672e7) | Aug 27, 2020 |
| Lenovo        | Unknown                     | [74313d4eb1](https://linux-hardware.org/?probe=74313d4eb1) | Aug 24, 2020 |
| Lenovo        | ThinkPad P50s 20FLS02200    | [68d5ec0716](https://linux-hardware.org/?probe=68d5ec0716) | Aug 24, 2020 |
| HP            | ProBook 650 G2              | [4a91b4b21f](https://linux-hardware.org/?probe=4a91b4b21f) | Aug 18, 2020 |
| Razer         | Blade                       | [b8e7f44d4a](https://linux-hardware.org/?probe=b8e7f44d4a) | Aug 17, 2020 |
| HP            | EliteBook 820 G3            | [0d1ad99429](https://linux-hardware.org/?probe=0d1ad99429) | Aug 13, 2020 |
| Toshiba       | Satellite L40               | [33ec17e21b](https://linux-hardware.org/?probe=33ec17e21b) | Aug 13, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | [8e3eee2d07](https://linux-hardware.org/?probe=8e3eee2d07) | Aug 06, 2020 |
| Lenovo        | ThinkPad P53 20QN002VMX     | [6b9f38754c](https://linux-hardware.org/?probe=6b9f38754c) | Aug 06, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [72a1412fb1](https://linux-hardware.org/?probe=72a1412fb1) | Aug 04, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [133bc3dd52](https://linux-hardware.org/?probe=133bc3dd52) | Aug 04, 2020 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [6d4445f122](https://linux-hardware.org/?probe=6d4445f122) | Aug 02, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [c535bd5654](https://linux-hardware.org/?probe=c535bd5654) | Jul 29, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [fa42e14984](https://linux-hardware.org/?probe=fa42e14984) | Jul 28, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [e748a3510c](https://linux-hardware.org/?probe=e748a3510c) | Jul 27, 2020 |
| Lenovo        | IdeaPad Y550 20017          | [3122f02f2c](https://linux-hardware.org/?probe=3122f02f2c) | Jul 23, 2020 |
| Packard Be... | EasyNote LJ73               | [b7cb387fea](https://linux-hardware.org/?probe=b7cb387fea) | Jul 21, 2020 |
| Dell          | Latitude E6420              | [e9238dcfff](https://linux-hardware.org/?probe=e9238dcfff) | Jul 19, 2020 |
| Dell          | Latitude E6420              | [231cadfc4a](https://linux-hardware.org/?probe=231cadfc4a) | Jul 19, 2020 |
| Toshiba       | Satellite L755D             | [a0cdb2f0bf](https://linux-hardware.org/?probe=a0cdb2f0bf) | Jul 12, 2020 |
| Toshiba       | Satellite L755D             | [f4ab460d93](https://linux-hardware.org/?probe=f4ab460d93) | Jul 12, 2020 |
| Dell          | Latitude 7480               | [c265940ec9](https://linux-hardware.org/?probe=c265940ec9) | Jul 11, 2020 |
| Apple         | MacBookPro6,1               | [432c9e6acf](https://linux-hardware.org/?probe=432c9e6acf) | Jul 05, 2020 |
| Apple         | MacBookPro14,1              | [b1b965bcfa](https://linux-hardware.org/?probe=b1b965bcfa) | Jul 03, 2020 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [26dfef89d5](https://linux-hardware.org/?probe=26dfef89d5) | Jun 30, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [3f43b86780](https://linux-hardware.org/?probe=3f43b86780) | Jun 29, 2020 |
| Fujitsu       | LIFEBOOK U938               | [445cfe436d](https://linux-hardware.org/?probe=445cfe436d) | Jun 28, 2020 |
| ASUSTek       | K56CB                       | [bbdd76a080](https://linux-hardware.org/?probe=bbdd76a080) | Jun 21, 2020 |
| Fujitsu       | LIFEBOOK U938               | [6fab40c5c2](https://linux-hardware.org/?probe=6fab40c5c2) | Jun 20, 2020 |
| Acer          | Mantasta                    | [fae9194978](https://linux-hardware.org/?probe=fae9194978) | Jun 19, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | [12d9fce39b](https://linux-hardware.org/?probe=12d9fce39b) | Jun 18, 2020 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [8307e528e0](https://linux-hardware.org/?probe=8307e528e0) | Jun 17, 2020 |
| HP            | Pavilion 15                 | [6d0c4b8b4f](https://linux-hardware.org/?probe=6d0c4b8b4f) | Jun 16, 2020 |
| Lenovo        | ThinkPad W540 20BG001BMD    | [c9de665933](https://linux-hardware.org/?probe=c9de665933) | Jun 14, 2020 |
| Dell          | Latitude 7480               | [f1120b6914](https://linux-hardware.org/?probe=f1120b6914) | Jun 14, 2020 |
| Dell          | XPS 15 9560                 | [68f8b211cb](https://linux-hardware.org/?probe=68f8b211cb) | Jun 13, 2020 |
| Dell          | XPS 15 9560                 | [5e9c9bd030](https://linux-hardware.org/?probe=5e9c9bd030) | Jun 13, 2020 |
| Razer         | Blade                       | [5ed51b12b4](https://linux-hardware.org/?probe=5ed51b12b4) | Jun 12, 2020 |
| HP            | SpectreXT Pro 13-b000 PC    | [6e1571661e](https://linux-hardware.org/?probe=6e1571661e) | Jun 12, 2020 |
| Lenovo        | ThinkPad W520 4284Y19       | [ac2ade7339](https://linux-hardware.org/?probe=ac2ade7339) | Jun 07, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [1431224dcf](https://linux-hardware.org/?probe=1431224dcf) | Jun 03, 2020 |
| Dell          | XPS 15 7590                 | [386ef00203](https://linux-hardware.org/?probe=386ef00203) | May 25, 2020 |
| Dell          | XPS 15 7590                 | [544670327d](https://linux-hardware.org/?probe=544670327d) | May 21, 2020 |
| Acer          | TravelMate 6592             | [9bb4619272](https://linux-hardware.org/?probe=9bb4619272) | May 17, 2020 |
| Acer          | TravelMate 6592             | [e4e54de319](https://linux-hardware.org/?probe=e4e54de319) | May 17, 2020 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [788a18932c](https://linux-hardware.org/?probe=788a18932c) | May 16, 2020 |
| Acer          | Swift SF514-52T             | [93ede38f81](https://linux-hardware.org/?probe=93ede38f81) | May 16, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [b47983a36a](https://linux-hardware.org/?probe=b47983a36a) | May 13, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [5fbd9385df](https://linux-hardware.org/?probe=5fbd9385df) | May 13, 2020 |
| Lenovo        | ThinkPad T410 2522WPH       | [236d1e64eb](https://linux-hardware.org/?probe=236d1e64eb) | May 10, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a54bb2200a](https://linux-hardware.org/?probe=a54bb2200a) | May 06, 2020 |
| HP            | 255 G7 Notebook PC          | [0a904bfe70](https://linux-hardware.org/?probe=0a904bfe70) | May 05, 2020 |
| TUXEDO        | Unknown                     | [3f23947dd8](https://linux-hardware.org/?probe=3f23947dd8) | May 04, 2020 |
| HP            | 255 G7 Notebook PC          | [b85ac004b3](https://linux-hardware.org/?probe=b85ac004b3) | May 04, 2020 |
| Lenovo        | ThinkPad T480s 20L8S5U50... | [d295ec1834](https://linux-hardware.org/?probe=d295ec1834) | May 03, 2020 |
| Dell          | Latitude E7450              | [0f14ff60e1](https://linux-hardware.org/?probe=0f14ff60e1) | May 02, 2020 |
| HP            | EliteBook 840 G1            | [9c6700839f](https://linux-hardware.org/?probe=9c6700839f) | May 01, 2020 |
| Lenovo        | IdeaPad U430p 20269         | [689865b9bf](https://linux-hardware.org/?probe=689865b9bf) | Apr 30, 2020 |
| Acer          | Aspire A715-72G             | [db52ab416a](https://linux-hardware.org/?probe=db52ab416a) | Apr 29, 2020 |
| HP            | EliteBook 840 G1            | [b77a2c1bdc](https://linux-hardware.org/?probe=b77a2c1bdc) | Apr 27, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | [2ea2bebae7](https://linux-hardware.org/?probe=2ea2bebae7) | Apr 25, 2020 |
| Lenovo        | ThinkPad T470p 20J7S0MS0... | [47ae6712b9](https://linux-hardware.org/?probe=47ae6712b9) | Apr 25, 2020 |
| HP            | Unknown                     | [7da32c9344](https://linux-hardware.org/?probe=7da32c9344) | Apr 21, 2020 |
| Dell          | Latitude E5510              | [a70ec059cf](https://linux-hardware.org/?probe=a70ec059cf) | Apr 13, 2020 |
| HP            | Pavilion dv9700             | [6096eebeb4](https://linux-hardware.org/?probe=6096eebeb4) | Apr 11, 2020 |
| Apple         | MacBookPro5,5               | [9f7081cc76](https://linux-hardware.org/?probe=9f7081cc76) | Apr 04, 2020 |
| Lenovo        | B50-10 80QR                 | [587fb80750](https://linux-hardware.org/?probe=587fb80750) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | [bfb0ade0c7](https://linux-hardware.org/?probe=bfb0ade0c7) | Apr 01, 2020 |
| Dixonsxp      | Unknown                     | [26154d1d2c](https://linux-hardware.org/?probe=26154d1d2c) | Apr 01, 2020 |
| ASUSTek       | N76VB                       | [a771ac7748](https://linux-hardware.org/?probe=a771ac7748) | Mar 24, 2020 |
| ASUSTek       | Strix 15 GL503GE            | [069d575f4a](https://linux-hardware.org/?probe=069d575f4a) | Mar 21, 2020 |
| HP            | Pavilion dv7                | [64000a6ec8](https://linux-hardware.org/?probe=64000a6ec8) | Mar 19, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [69559fb5ce](https://linux-hardware.org/?probe=69559fb5ce) | Mar 18, 2020 |
| Toshiba       | Satellite C670D-10C         | [bdcd7e9b36](https://linux-hardware.org/?probe=bdcd7e9b36) | Mar 17, 2020 |
| Toshiba       | Satellite C670D-10C         | [ab2ea68be0](https://linux-hardware.org/?probe=ab2ea68be0) | Mar 17, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [86e1d115b9](https://linux-hardware.org/?probe=86e1d115b9) | Mar 15, 2020 |
| HP            | ProBook 4720s               | [a32d5c092c](https://linux-hardware.org/?probe=a32d5c092c) | Mar 15, 2020 |
| Toshiba       | Satellite L40               | [467c320928](https://linux-hardware.org/?probe=467c320928) | Mar 11, 2020 |
| Lenovo        | ThinkPad Edge E530 3259C... | [7e0acb9bed](https://linux-hardware.org/?probe=7e0acb9bed) | Mar 06, 2020 |
| HP            | ProBook 4720s               | [823553cfbd](https://linux-hardware.org/?probe=823553cfbd) | Mar 03, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [de25ec2891](https://linux-hardware.org/?probe=de25ec2891) | Feb 28, 2020 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [b333f7015a](https://linux-hardware.org/?probe=b333f7015a) | Feb 28, 2020 |
| HP            | ZBook 14u G5                | [03871e6b83](https://linux-hardware.org/?probe=03871e6b83) | Feb 25, 2020 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [0937d2a588](https://linux-hardware.org/?probe=0937d2a588) | Feb 20, 2020 |
| Dell          | Inspiron 3542               | [5e00c1766c](https://linux-hardware.org/?probe=5e00c1766c) | Feb 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [7f8aef2f6b](https://linux-hardware.org/?probe=7f8aef2f6b) | Feb 19, 2020 |
| MSI           | MS-1738                     | [0cbf139f1d](https://linux-hardware.org/?probe=0cbf139f1d) | Feb 11, 2020 |
| Lenovo        | ThinkPad T490s 20NX000EM... | [7773f702ab](https://linux-hardware.org/?probe=7773f702ab) | Feb 10, 2020 |
| ASUSTek       | UX331UA                     | [62bdf0c233](https://linux-hardware.org/?probe=62bdf0c233) | Feb 10, 2020 |
| HP            | EliteBook 850 G5            | [fc9101307a](https://linux-hardware.org/?probe=fc9101307a) | Feb 07, 2020 |
| Dell          | Precision 7530              | [bb59dc45d2](https://linux-hardware.org/?probe=bb59dc45d2) | Feb 06, 2020 |
| MSI           | MS-1738                     | [1f7c3ccb75](https://linux-hardware.org/?probe=1f7c3ccb75) | Jan 29, 2020 |
| Lenovo        | IdeaPad Y500 9541           | [1435e47012](https://linux-hardware.org/?probe=1435e47012) | Jan 27, 2020 |
| ASUSTek       | X555UJ                      | [261f8ada0a](https://linux-hardware.org/?probe=261f8ada0a) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | [44ad91d4da](https://linux-hardware.org/?probe=44ad91d4da) | Jan 24, 2020 |
| Dell          | Latitude 5590               | [206a367d42](https://linux-hardware.org/?probe=206a367d42) | Jan 24, 2020 |
| HP            | EliteBook 850 G5            | [bcc6422548](https://linux-hardware.org/?probe=bcc6422548) | Jan 18, 2020 |
| Samsung       | N150/N210/N220              | [91718b856a](https://linux-hardware.org/?probe=91718b856a) | Jan 16, 2020 |
| HP            | EliteBook 840 G6            | [79936056dd](https://linux-hardware.org/?probe=79936056dd) | Jan 16, 2020 |
| HP            | Laptop 15-bw0xx             | [2aff706ca4](https://linux-hardware.org/?probe=2aff706ca4) | Jan 15, 2020 |
| Lenovo        | ThinkPad T430s 2356W1L      | [42b6186198](https://linux-hardware.org/?probe=42b6186198) | Jan 13, 2020 |
| HP            | ProBook 4710s               | [d6124de12a](https://linux-hardware.org/?probe=d6124de12a) | Jan 01, 2020 |
| HP            | ProBook 4710s               | [7eb0b2437d](https://linux-hardware.org/?probe=7eb0b2437d) | Jan 01, 2020 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [14015a6cde](https://linux-hardware.org/?probe=14015a6cde) | Dec 24, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [c7b13e4ba2](https://linux-hardware.org/?probe=c7b13e4ba2) | Dec 23, 2019 |
| Dell          | Inspiron 1545               | [adaa5b6d54](https://linux-hardware.org/?probe=adaa5b6d54) | Dec 10, 2019 |
| Lenovo        | ThinkPad P51 20HH001RMD     | [7ab81dbd28](https://linux-hardware.org/?probe=7ab81dbd28) | Nov 30, 2019 |
| HP            | Pavilion dv6                | [fdc46ce1cd](https://linux-hardware.org/?probe=fdc46ce1cd) | Nov 26, 2019 |
| Lenovo        | ThinkPad S5-S540 20B3005... | [e84f3912be](https://linux-hardware.org/?probe=e84f3912be) | Nov 10, 2019 |
| eMachines     | E725                        | [599a7f6c54](https://linux-hardware.org/?probe=599a7f6c54) | Nov 03, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [9607f525a8](https://linux-hardware.org/?probe=9607f525a8) | Oct 29, 2019 |
| Apple         | MacBookPro9,2               | [99702307ab](https://linux-hardware.org/?probe=99702307ab) | Oct 21, 2019 |
| HP            | OMEN by Laptop              | [90ef6677b7](https://linux-hardware.org/?probe=90ef6677b7) | Oct 15, 2019 |
| Dell          | XPS 15 9570                 | [6cdbd762c1](https://linux-hardware.org/?probe=6cdbd762c1) | Oct 13, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [acd2d7dfad](https://linux-hardware.org/?probe=acd2d7dfad) | Oct 12, 2019 |
| Lenovo        | IdeaPad S130-14IGM 81J2     | [98855b1409](https://linux-hardware.org/?probe=98855b1409) | Oct 09, 2019 |
| Lenovo        | ThinkPad E480 20KN001NMX    | [4f055c0cf5](https://linux-hardware.org/?probe=4f055c0cf5) | Oct 08, 2019 |
| Dell          | Latitude 7480               | [b6627cc113](https://linux-hardware.org/?probe=b6627cc113) | Oct 08, 2019 |
| Lenovo        | ThinkPad P51 20HH001RMD     | [14671c29e5](https://linux-hardware.org/?probe=14671c29e5) | Oct 07, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [402c3e5e59](https://linux-hardware.org/?probe=402c3e5e59) | Oct 05, 2019 |
| Acer          | Aspire ES1-311              | [d9d6c865ef](https://linux-hardware.org/?probe=d9d6c865ef) | Sep 26, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [98ed6c18c5](https://linux-hardware.org/?probe=98ed6c18c5) | Sep 21, 2019 |
| Lenovo        | IdeaPad U430p 20269         | [fd17c2893e](https://linux-hardware.org/?probe=fd17c2893e) | Sep 19, 2019 |
| HP            | EliteBook 850 G5            | [b355ce68ad](https://linux-hardware.org/?probe=b355ce68ad) | Sep 15, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [01545dc8fb](https://linux-hardware.org/?probe=01545dc8fb) | Sep 11, 2019 |
| HP            | EliteBook 850 G5            | [f0c27f436e](https://linux-hardware.org/?probe=f0c27f436e) | Sep 10, 2019 |
| HP            | Pavilion dv2                | [b9b30ae45c](https://linux-hardware.org/?probe=b9b30ae45c) | Sep 10, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [121e1a0f7a](https://linux-hardware.org/?probe=121e1a0f7a) | Aug 27, 2019 |
| Samsung       | 940X3G/930X3G               | [73a88e2c94](https://linux-hardware.org/?probe=73a88e2c94) | Aug 23, 2019 |
| Dell          | XPS 15 9570                 | [85fc7259b6](https://linux-hardware.org/?probe=85fc7259b6) | Aug 15, 2019 |
| Fujitsu       | LIFEBOOK U772               | [0f7c7fe35a](https://linux-hardware.org/?probe=0f7c7fe35a) | Aug 15, 2019 |
| HP            | Pavilion x2 Detachable      | [923cbd5735](https://linux-hardware.org/?probe=923cbd5735) | Aug 06, 2019 |
| Lenovo        | IdeaPad Y700-14ISK 80NU     | [0aaee3cc4f](https://linux-hardware.org/?probe=0aaee3cc4f) | Aug 02, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [61e8e08336](https://linux-hardware.org/?probe=61e8e08336) | Jul 31, 2019 |
| Lenovo        | ThinkPad T430s 2356W1L      | [41e069ab47](https://linux-hardware.org/?probe=41e069ab47) | Jul 31, 2019 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [3e47232411](https://linux-hardware.org/?probe=3e47232411) | Jul 26, 2019 |
| Dell          | Latitude E7470              | [90e9f8dfad](https://linux-hardware.org/?probe=90e9f8dfad) | Jul 26, 2019 |
| Lenovo        | ThinkPad S430 33642NG       | [7c0cd24986](https://linux-hardware.org/?probe=7c0cd24986) | Jul 25, 2019 |
| HP            | Pavilion dv9700             | [bfebe8555b](https://linux-hardware.org/?probe=bfebe8555b) | Jul 25, 2019 |
| HP            | Compaq CQ58                 | [0c02dfd17b](https://linux-hardware.org/?probe=0c02dfd17b) | Jul 21, 2019 |
| HP            | Compaq nx7400 (RU429ET#A... | [37b1d8aa7d](https://linux-hardware.org/?probe=37b1d8aa7d) | Jul 19, 2019 |
| Lenovo        | G580 2189                   | [f3d7e4e13d](https://linux-hardware.org/?probe=f3d7e4e13d) | Jul 19, 2019 |
| Lenovo        | G580 2189                   | [a75a2e9dae](https://linux-hardware.org/?probe=a75a2e9dae) | Jul 19, 2019 |
| HP            | Pavilion dv7                | [dda054b15d](https://linux-hardware.org/?probe=dda054b15d) | Jul 15, 2019 |
| ASUSTek       | 900                         | [db34e96f60](https://linux-hardware.org/?probe=db34e96f60) | Jul 06, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [5bc72880ea](https://linux-hardware.org/?probe=5bc72880ea) | Jun 15, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [25522cad27](https://linux-hardware.org/?probe=25522cad27) | Jun 13, 2019 |
| HP            | EliteBook 8740w (SK430UP... | [4ed2a6de0d](https://linux-hardware.org/?probe=4ed2a6de0d) | Jun 08, 2019 |
| Acer          | Nitro AN515-42              | [5d176e185c](https://linux-hardware.org/?probe=5d176e185c) | Jun 06, 2019 |
| Lenovo        | ThinkPad T510 4384VZB       | [945dd2aedf](https://linux-hardware.org/?probe=945dd2aedf) | Jun 04, 2019 |
| ASUSTek       | X55SV                       | [4137ac8f54](https://linux-hardware.org/?probe=4137ac8f54) | May 31, 2019 |
| HP            | EliteBook 8440p             | [e1a6c35a36](https://linux-hardware.org/?probe=e1a6c35a36) | May 27, 2019 |
| HP            | EliteBook 8440p             | [cfcb01f30c](https://linux-hardware.org/?probe=cfcb01f30c) | May 27, 2019 |
| HP            | EliteBook 8760w             | [13780fae80](https://linux-hardware.org/?probe=13780fae80) | May 25, 2019 |
| HP            | EliteBook 8760w             | [93d7fd3de9](https://linux-hardware.org/?probe=93d7fd3de9) | May 25, 2019 |
| ASUSTek       | UX331UA                     | [5b86d530bf](https://linux-hardware.org/?probe=5b86d530bf) | May 07, 2019 |
| MSI           | GV62 8RE                    | [4c00b9e457](https://linux-hardware.org/?probe=4c00b9e457) | May 05, 2019 |
| Lenovo        | Unknown                     | [fd7bf6fb44](https://linux-hardware.org/?probe=fd7bf6fb44) | May 04, 2019 |
| Lenovo        | Unknown                     | [abcb8328f0](https://linux-hardware.org/?probe=abcb8328f0) | May 03, 2019 |
| ASUSTek       | UX331UA                     | [4e74668f09](https://linux-hardware.org/?probe=4e74668f09) | Apr 30, 2019 |
| AMI           | Cherry Trail CR             | [c2adff61c1](https://linux-hardware.org/?probe=c2adff61c1) | Apr 16, 2019 |
| ASUSTek       | X550JX                      | [961517bceb](https://linux-hardware.org/?probe=961517bceb) | Apr 08, 2019 |
| Acer          | TravelMate 5720             | [3c724ba732](https://linux-hardware.org/?probe=3c724ba732) | Apr 03, 2019 |
| Acer          | TravelMate 5720             | [19a257005b](https://linux-hardware.org/?probe=19a257005b) | Apr 02, 2019 |
| Lenovo        | ThinkPad W500 406333G       | [16f12d3bc8](https://linux-hardware.org/?probe=16f12d3bc8) | Apr 01, 2019 |
| Lenovo        | ThinkPad W500 406333G       | [28142e5518](https://linux-hardware.org/?probe=28142e5518) | Apr 01, 2019 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [e8fd67417e](https://linux-hardware.org/?probe=e8fd67417e) | Mar 29, 2019 |
| ASUSTek       | S551LN                      | [2c007f8b6c](https://linux-hardware.org/?probe=2c007f8b6c) | Mar 23, 2019 |
| Lenovo        | ThinkPad X201 3680HC3       | [6f637899c4](https://linux-hardware.org/?probe=6f637899c4) | Mar 12, 2019 |
| HP            | Laptop 14-ck0xxx            | [620383c937](https://linux-hardware.org/?probe=620383c937) | Mar 07, 2019 |
| Acer          | Aspire 7220                 | [918907fa0a](https://linux-hardware.org/?probe=918907fa0a) | Mar 06, 2019 |
| ASUSTek       | N750JK                      | [29d535d30f](https://linux-hardware.org/?probe=29d535d30f) | Feb 15, 2019 |
| ASUSTek       | N750JK                      | [0a21e6bf0f](https://linux-hardware.org/?probe=0a21e6bf0f) | Feb 13, 2019 |
| Lenovo        | ThinkPad X201 3680HC3       | [f5cf28dd23](https://linux-hardware.org/?probe=f5cf28dd23) | Jan 25, 2019 |
| ASUSTek       | N750JK                      | [e706aadaf7](https://linux-hardware.org/?probe=e706aadaf7) | Jan 16, 2019 |
| ASUSTek       | N750JK                      | [8e8a651043](https://linux-hardware.org/?probe=8e8a651043) | Jan 12, 2019 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [d87952f0b8](https://linux-hardware.org/?probe=d87952f0b8) | Dec 20, 2018 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [7f746478de](https://linux-hardware.org/?probe=7f746478de) | Dec 20, 2018 |
| Lenovo        | ThinkPad T530 24295XG       | [65d4845db2](https://linux-hardware.org/?probe=65d4845db2) | Dec 10, 2018 |
| Lenovo        | ThinkPad T570 20H9001EGE    | [904c160172](https://linux-hardware.org/?probe=904c160172) | Nov 25, 2018 |
| Lenovo        | ThinkPad T570 20H9001EGE    | [e71b0059ee](https://linux-hardware.org/?probe=e71b0059ee) | Nov 25, 2018 |
| Lenovo        | ThinkPad T530 24292UG       | [dc38e86871](https://linux-hardware.org/?probe=dc38e86871) | Jun 29, 2018 |
| Lenovo        | ThinkPad T530 24292UG       | [f521f460e8](https://linux-hardware.org/?probe=f521f460e8) | Jun 29, 2018 |
| Acer          | Aspire ES1-111M             | [782a0a4926](https://linux-hardware.org/?probe=782a0a4926) | Mar 25, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Denmark/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 83        | 17.08%  |
| Ubuntu 18.04       | 48        | 9.88%   |
| Ubuntu 22.04       | 23        | 4.73%   |
| Ubuntu 21.10       | 15        | 3.09%   |
| OpenMandriva 4.2   | 12        | 2.47%   |
| Fedora 34          | 12        | 2.47%   |
| Arch               | 11        | 2.26%   |
| Manjaro            | 9         | 1.85%   |
| Ubuntu 19.04       | 8         | 1.65%   |
| Pop!_OS 20.04      | 8         | 1.65%   |
| Fedora 36          | 8         | 1.65%   |
| Arch Rolling       | 8         | 1.65%   |
| Zorin 15           | 7         | 1.44%   |
| Pop!_OS 22.04      | 7         | 1.44%   |
| Pop!_OS 21.04      | 7         | 1.44%   |
| Linux Mint 20.3    | 7         | 1.44%   |
| Fedora 32          | 7         | 1.44%   |
| Debian 11          | 7         | 1.44%   |
| Debian 10          | 7         | 1.44%   |
| Ubuntu 20.10       | 6         | 1.23%   |
| Pop!_OS 21.10      | 6         | 1.23%   |
| Linux Mint 20.2    | 6         | 1.23%   |
| Linux Mint 20.1    | 6         | 1.23%   |
| KDE neon 20.04     | 6         | 1.23%   |
| Fedora 33          | 6         | 1.23%   |
| Xubuntu 20.04      | 5         | 1.03%   |
| Ubuntu 19.10       | 5         | 1.03%   |
| Ubuntu 18.10       | 5         | 1.03%   |
| OpenMandriva 4.3   | 5         | 1.03%   |
| Linux Mint 21      | 5         | 1.03%   |
| Linux Mint 20      | 5         | 1.03%   |
| Fedora 35          | 5         | 1.03%   |
| Ubuntu 21.04       | 4         | 0.82%   |
| Pop!_OS 20.10      | 4         | 0.82%   |
| Linux Mint 19.2    | 4         | 0.82%   |
| Kubuntu 20.04      | 4         | 0.82%   |
| Fedora 31          | 4         | 0.82%   |
| Void Linux Rolling | 3         | 0.62%   |
| Ubuntu Unity 18.04 | 3         | 0.62%   |
| Linux Mint 19.3    | 3         | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Ubuntu       | 183       | 40.4%   |
| Linux Mint   | 38        | 8.39%   |
| Fedora       | 37        | 8.17%   |
| Pop!_OS      | 31        | 6.84%   |
| OpenMandriva | 19        | 4.19%   |
| Manjaro      | 19        | 4.19%   |
| Arch         | 18        | 3.97%   |
| Debian       | 15        | 3.31%   |
| Kubuntu      | 11        | 2.43%   |
| Zorin        | 10        | 2.21%   |
| Xubuntu      | 8         | 1.77%   |
| KDE neon     | 8         | 1.77%   |
| Ubuntu Unity | 5         | 1.1%    |
| ROSA         | 5         | 1.1%    |
| Void Linux   | 4         | 0.88%   |
| EndeavourOS  | 4         | 0.88%   |
| Elementary   | 4         | 0.88%   |
| ArcoLinux    | 4         | 0.88%   |
| Ubuntu MATE  | 3         | 0.66%   |
| Parrot       | 3         | 0.66%   |
| LMDE         | 3         | 0.66%   |
| Garuda Linux | 3         | 0.66%   |
| Clear Linux  | 3         | 0.66%   |
| SteamOS      | 2         | 0.44%   |
| openSUSE     | 2         | 0.44%   |
| Kali         | 2         | 0.44%   |
| TUXEDO OS    | 1         | 0.22%   |
| NixOS        | 1         | 0.22%   |
| Lubuntu      | 1         | 0.22%   |
| LinuxFX      | 1         | 0.22%   |
| Gentoo       | 1         | 0.22%   |
| GalliumOS    | 1         | 0.22%   |
| Endless      | 1         | 0.22%   |
| BlackPanther | 1         | 0.22%   |
| antiX        | 1         | 0.22%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 14        | 2.63%   |
| 5.10.14-desktop-1omv4002 | 12        | 2.25%   |
| 5.15.0-56-generic        | 7         | 1.31%   |
| 5.4.0-52-generic         | 6         | 1.13%   |
| 5.4.0-48-generic         | 6         | 1.13%   |
| 5.4.0-26-generic         | 6         | 1.13%   |
| 5.16.7-desktop-1omv4003  | 6         | 1.13%   |
| 5.4.0-7634-generic       | 5         | 0.94%   |
| 5.4.0-47-generic         | 5         | 0.94%   |
| 5.15.0-53-generic        | 5         | 0.94%   |
| 5.4.0-58-generic         | 4         | 0.75%   |
| 5.4.0-40-generic         | 4         | 0.75%   |
| 5.3.0-40-generic         | 4         | 0.75%   |
| 5.19.0-76051900-generic  | 4         | 0.75%   |
| 5.15.0-52-generic        | 4         | 0.75%   |
| 5.11.0-41-generic        | 4         | 0.75%   |
| 5.11.0-40-generic        | 4         | 0.75%   |
| 5.11.0-27-generic        | 4         | 0.75%   |
| 5.0.0-23-generic         | 4         | 0.75%   |
| 4.15.0-55-generic        | 4         | 0.75%   |
| 5.8.15-301.fc33.x86_64   | 3         | 0.56%   |
| 5.8.0-59-generic         | 3         | 0.56%   |
| 5.8.0-50-generic         | 3         | 0.56%   |
| 5.8.0-45-generic         | 3         | 0.56%   |
| 5.8.0-29-generic         | 3         | 0.56%   |
| 5.4.0-96-generic         | 3         | 0.56%   |
| 5.4.0-91-generic         | 3         | 0.56%   |
| 5.4.0-81-generic         | 3         | 0.56%   |
| 5.4.0-77-generic         | 3         | 0.56%   |
| 5.4.0-62-generic         | 3         | 0.56%   |
| 5.4.0-54-generic         | 3         | 0.56%   |
| 5.4.0-29-generic         | 3         | 0.56%   |
| 5.3.0-28-generic         | 3         | 0.56%   |
| 5.15.0-46-generic        | 3         | 0.56%   |
| 5.15.0-43-generic        | 3         | 0.56%   |
| 5.15.0-40-generic        | 3         | 0.56%   |
| 5.15.0-27-generic        | 3         | 0.56%   |
| 5.13.12-200.fc34.x86_64  | 3         | 0.56%   |
| 5.11.0-7620-generic      | 3         | 0.56%   |
| 5.11.0-46-generic        | 3         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 92        | 18.4%   |
| 5.15.0  | 36        | 7.2%    |
| 4.15.0  | 35        | 7%      |
| 5.11.0  | 34        | 6.8%    |
| 5.8.0   | 28        | 5.6%    |
| 5.13.0  | 24        | 4.8%    |
| 5.3.0   | 18        | 3.6%    |
| 5.0.0   | 17        | 3.4%    |
| 4.18.0  | 13        | 2.6%    |
| 5.10.14 | 12        | 2.4%    |
| 5.10.0  | 9         | 1.8%    |
| 5.19.0  | 7         | 1.4%    |
| 4.19.0  | 7         | 1.4%    |
| 5.16.7  | 6         | 1.2%    |
| 5.7.15  | 4         | 0.8%    |
| 6.0.10  | 3         | 0.6%    |
| 5.9.0   | 3         | 0.6%    |
| 5.8.15  | 3         | 0.6%    |
| 5.4.18  | 3         | 0.6%    |
| 5.19.13 | 3         | 0.6%    |
| 5.16.0  | 3         | 0.6%    |
| 5.14.0  | 3         | 0.6%    |
| 5.13.12 | 3         | 0.6%    |
| 6.1.1   | 2         | 0.4%    |
| 6.0.6   | 2         | 0.4%    |
| 6.0.0   | 2         | 0.4%    |
| 5.9.16  | 2         | 0.4%    |
| 5.9.14  | 2         | 0.4%    |
| 5.8.16  | 2         | 0.4%    |
| 5.8.11  | 2         | 0.4%    |
| 5.6.7   | 2         | 0.4%    |
| 5.4.8   | 2         | 0.4%    |
| 5.18.11 | 2         | 0.4%    |
| 5.17.5  | 2         | 0.4%    |
| 5.16.18 | 2         | 0.4%    |
| 5.16.12 | 2         | 0.4%    |
| 5.16.11 | 2         | 0.4%    |
| 5.15.6  | 2         | 0.4%    |
| 5.15.46 | 2         | 0.4%    |
| 5.15.16 | 2         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 100       | 20.2%   |
| 5.15    | 55        | 11.11%  |
| 5.8     | 39        | 7.88%   |
| 5.11    | 38        | 7.68%   |
| 4.15    | 35        | 7.07%   |
| 5.13    | 29        | 5.86%   |
| 5.10    | 27        | 5.45%   |
| 5.16    | 19        | 3.84%   |
| 5.3     | 18        | 3.64%   |
| 5.19    | 18        | 3.64%   |
| 5.0     | 18        | 3.64%   |
| 4.18    | 14        | 2.83%   |
| 5.14    | 12        | 2.42%   |
| 6.0     | 10        | 2.02%   |
| 5.9     | 9         | 1.82%   |
| 4.19    | 8         | 1.62%   |
| 5.18    | 7         | 1.41%   |
| 5.7     | 6         | 1.21%   |
| 5.6     | 6         | 1.21%   |
| 5.17    | 6         | 1.21%   |
| 5.12    | 5         | 1.01%   |
| 5.1     | 3         | 0.61%   |
| 6.1     | 2         | 0.4%    |
| 4.9     | 2         | 0.4%    |
| 4.4     | 2         | 0.4%    |
| 4.14    | 2         | 0.4%    |
| 5.2     | 1         | 0.2%    |
| 4.16    | 1         | 0.2%    |
| 4.13    | 1         | 0.2%    |
| 4.10    | 1         | 0.2%    |
| Unknown | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 418       | 95.65%  |
| i686   | 19        | 4.35%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 227       | 49.46%  |
| Unknown         | 69        | 15.03%  |
| KDE5            | 65        | 14.16%  |
| X-Cinnamon      | 29        | 6.32%   |
| XFCE            | 25        | 5.45%   |
| KDE             | 12        | 2.61%   |
| MATE            | 10        | 2.18%   |
| Unity           | 5         | 1.09%   |
| i3              | 4         | 0.87%   |
| Pantheon        | 3         | 0.65%   |
| LXQt            | 2         | 0.44%   |
| Cinnamon        | 2         | 0.44%   |
| sway            | 1         | 0.22%   |
| qtile-default   | 1         | 0.22%   |
| LeftWM          | 1         | 0.22%   |
| icewm           | 1         | 0.22%   |
| GNOME Flashback | 1         | 0.22%   |
| awesome         | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 334       | 73.09%  |
| Wayland | 83        | 18.16%  |
| Unknown | 35        | 7.66%   |
| Tty     | 5         | 1.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 257       | 57.11%  |
| GDM     | 63        | 14%     |
| GDM3    | 50        | 11.11%  |
| SDDM    | 47        | 10.44%  |
| LightDM | 19        | 4.22%   |
| TDM     | 12        | 2.67%   |
| Ly      | 1         | 0.22%   |
| GREETD  | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 152       | 33.55%  |
| da_DK   | 135       | 29.8%   |
| Unknown | 62        | 13.69%  |
| en_DK   | 58        | 12.8%   |
| en_GB   | 22        | 4.86%   |
| de_DE   | 10        | 2.21%   |
| C       | 5         | 1.1%    |
| pl_PL   | 2         | 0.44%   |
| en_AG   | 2         | 0.44%   |
| pt_BR   | 1         | 0.22%   |
| it_IT   | 1         | 0.22%   |
| is_IS   | 1         | 0.22%   |
| fr_FR   | 1         | 0.22%   |
| en_CA   | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 224       | 50.45%  |
| EFI  | 220       | 49.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 352       | 79.1%   |
| Btrfs   | 46        | 10.34%  |
| Overlay | 20        | 4.49%   |
| Unknown | 20        | 4.49%   |
| Zfs     | 4         | 0.9%    |
| Ext2    | 3         | 0.67%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 280       | 62.78%  |
| GPT     | 132       | 29.6%   |
| MBR     | 34        | 7.62%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 395       | 89.16%  |
| Yes       | 48        | 10.84%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 347       | 78.51%  |
| Yes       | 95        | 21.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 155       | 35.55%  |
| Hewlett-Packard     | 77        | 17.66%  |
| Dell                | 42        | 9.63%   |
| ASUSTek Computer    | 41        | 9.4%    |
| Acer                | 33        | 7.57%   |
| Apple               | 15        | 3.44%   |
| Toshiba             | 10        | 2.29%   |
| Notebook            | 9         | 2.06%   |
| MSI                 | 8         | 1.83%   |
| HUAWEI              | 4         | 0.92%   |
| Samsung Electronics | 3         | 0.69%   |
| Medion              | 3         | 0.69%   |
| Google              | 3         | 0.69%   |
| Valve               | 2         | 0.46%   |
| TUXEDO              | 2         | 0.46%   |
| Timi                | 2         | 0.46%   |
| Razer               | 2         | 0.46%   |
| Quanta              | 2         | 0.46%   |
| Packard Bell        | 2         | 0.46%   |
| GPD                 | 2         | 0.46%   |
| Fujitsu             | 2         | 0.46%   |
| eMachines           | 2         | 0.46%   |
| AMI                 | 2         | 0.46%   |
| Unknown             | 2         | 0.46%   |
| Standard            | 1         | 0.23%   |
| SLIMBOOK            | 1         | 0.23%   |
| Purism              | 1         | 0.23%   |
| LG Electronics      | 1         | 0.23%   |
| LAMINA              | 1         | 0.23%   |
| Komplett            | 1         | 0.23%   |
| IBM                 | 1         | 0.23%   |
| Fujitsu Siemens     | 1         | 0.23%   |
| DukaPC              | 1         | 0.23%   |
| Dixonsxp            | 1         | 0.23%   |
| Alienware           | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 9         | 2.06%   |
| HP Pavilion dv7                       | 4         | 0.92%   |
| Dell XPS 15 9570                      | 4         | 0.92%   |
| HP EliteBook 820 G3                   | 3         | 0.69%   |
| Dell XPS 13 9370                      | 3         | 0.69%   |
| ASUS ROG Zephyrus G14 GA402RK_GA402RK | 3         | 0.69%   |
| Apple MacBookPro5,5                   | 3         | 0.69%   |
| Valve Jupiter                         | 2         | 0.46%   |
| Toshiba Satellite L40                 | 2         | 0.46%   |
| Quanta MW1/HW1                        | 2         | 0.46%   |
| Notebook W54_55SU1,SUW                | 2         | 0.46%   |
| Lenovo ThinkPad T530 24295L4          | 2         | 0.46%   |
| Lenovo IdeaPad S130-14IGM 81J2        | 2         | 0.46%   |
| Lenovo IdeaPad 310-15IKB 80TV         | 2         | 0.46%   |
| Lenovo E31-80 80MX                    | 2         | 0.46%   |
| HP ProBook 650 G1                     | 2         | 0.46%   |
| HP Pavilion Notebook                  | 2         | 0.46%   |
| HP Pavilion g7                        | 2         | 0.46%   |
| HP Pavilion 15                        | 2         | 0.46%   |
| HP Notebook                           | 2         | 0.46%   |
| HP Laptop 15s-eq2xxx                  | 2         | 0.46%   |
| HP Laptop 15-bw0xx                    | 2         | 0.46%   |
| HP EliteBook 845 G7 Notebook PC       | 2         | 0.46%   |
| HP EliteBook 840 G1                   | 2         | 0.46%   |
| HP Compaq Presario CQ71               | 2         | 0.46%   |
| eMachines E725                        | 2         | 0.46%   |
| Dell XPS 15 9560                      | 2         | 0.46%   |
| Dell Latitude E7440                   | 2         | 0.46%   |
| Dell Latitude 7480                    | 2         | 0.46%   |
| Apple MacBookPro9,2                   | 2         | 0.46%   |
| Apple MacBookPro7,1                   | 2         | 0.46%   |
| Apple MacBookPro14,1                  | 2         | 0.46%   |
| Acer Aspire E5-575G                   | 2         | 0.46%   |
| TUXEDO Pulse 15 Gen1                  | 1         | 0.23%   |
| Toshiba Satellite U300                | 1         | 0.23%   |
| Toshiba Satellite P850                | 1         | 0.23%   |
| Toshiba Satellite P55W-C              | 1         | 0.23%   |
| Toshiba Satellite P50-A-11J           | 1         | 0.23%   |
| Toshiba Satellite L755D               | 1         | 0.23%   |
| Toshiba Satellite L350D               | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 110       | 25.23%  |
| Acer Aspire           | 23        | 5.28%   |
| HP Pavilion           | 19        | 4.36%   |
| HP EliteBook          | 19        | 4.36%   |
| Dell Latitude         | 18        | 4.13%   |
| Lenovo IdeaPad        | 15        | 3.44%   |
| Dell XPS              | 13        | 2.98%   |
| Toshiba Satellite     | 10        | 2.29%   |
| HP ProBook            | 10        | 2.29%   |
| ASUS ROG              | 10        | 2.29%   |
| Unknown               | 9         | 2.06%   |
| HP Laptop             | 8         | 1.83%   |
| HP Compaq             | 6         | 1.38%   |
| Dell Inspiron         | 6         | 1.38%   |
| ASUS ZenBook          | 5         | 1.15%   |
| ASUS VivoBook         | 4         | 0.92%   |
| Lenovo Yoga           | 3         | 0.69%   |
| Lenovo ThinkBook      | 3         | 0.69%   |
| Lenovo Legion         | 3         | 0.69%   |
| HP ZBook              | 3         | 0.69%   |
| Dell Precision        | 3         | 0.69%   |
| Apple MacBookPro5     | 3         | 0.69%   |
| Acer Swift            | 3         | 0.69%   |
| Valve Jupiter         | 2         | 0.46%   |
| Razer Blade           | 2         | 0.46%   |
| Quanta MW1            | 2         | 0.46%   |
| Packard Bell EasyNote | 2         | 0.46%   |
| Notebook W54          | 2         | 0.46%   |
| MSI GV62              | 2         | 0.46%   |
| Lenovo E31-80         | 2         | 0.46%   |
| Lenovo 3000           | 2         | 0.46%   |
| HP OMEN               | 2         | 0.46%   |
| HP Notebook           | 2         | 0.46%   |
| Fujitsu LIFEBOOK      | 2         | 0.46%   |
| eMachines E725        | 2         | 0.46%   |
| ASUS TUF              | 2         | 0.46%   |
| ASUS ASUS             | 2         | 0.46%   |
| Apple MacBookPro9     | 2         | 0.46%   |
| Apple MacBookPro7     | 2         | 0.46%   |
| Apple MacBookPro14    | 2         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 42        | 9.63%   |
| 2019    | 39        | 8.94%   |
| 2013    | 34        | 7.8%    |
| 2020    | 33        | 7.57%   |
| 2017    | 32        | 7.34%   |
| 2015    | 32        | 7.34%   |
| 2021    | 31        | 7.11%   |
| 2016    | 31        | 7.11%   |
| 2012    | 31        | 7.11%   |
| 2011    | 29        | 6.65%   |
| 2009    | 21        | 4.82%   |
| 2014    | 19        | 4.36%   |
| 2010    | 18        | 4.13%   |
| 2008    | 13        | 2.98%   |
| 2007    | 13        | 2.98%   |
| 2022    | 11        | 2.52%   |
| 2006    | 5         | 1.15%   |
| 2003    | 1         | 0.23%   |
| Unknown | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 436       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 394       | 89.55%  |
| Enabled  | 46        | 10.45%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 432       | 99.08%  |
| Yes  | 4         | 0.92%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 131       | 29.37%  |
| 8.01-16.0   | 94        | 21.08%  |
| 16.01-24.0  | 76        | 17.04%  |
| 3.01-4.0    | 69        | 15.47%  |
| 32.01-64.0  | 34        | 7.62%   |
| 1.01-2.0    | 15        | 3.36%   |
| 2.01-3.0    | 10        | 2.24%   |
| 24.01-32.0  | 8         | 1.79%   |
| 64.01-256.0 | 7         | 1.57%   |
| 0.51-1.0    | 1         | 0.22%   |
| 0.01-0.5    | 1         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 155       | 31.83%  |
| 2.01-3.0   | 136       | 27.93%  |
| 4.01-8.0   | 80        | 16.43%  |
| 3.01-4.0   | 71        | 14.58%  |
| 0.51-1.0   | 24        | 4.93%   |
| 8.01-16.0  | 13        | 2.67%   |
| 0.01-0.5   | 5         | 1.03%   |
| 16.01-24.0 | 2         | 0.41%   |
| 32.01-64.0 | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 348       | 78.56%  |
| 2      | 82        | 18.51%  |
| 3      | 10        | 2.26%   |
| 0      | 3         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 294       | 66.67%  |
| Yes       | 147       | 33.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 372       | 84.74%  |
| No        | 67        | 15.26%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 431       | 98.85%  |
| No        | 5         | 1.15%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 368       | 82.33%  |
| No        | 79        | 17.67%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Denmark | 436       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Copenhagen            | 101       | 21.91%  |
| Odense                | 34        | 7.38%   |
| Frederiksberg         | 31        | 6.72%   |
| Bronshoj              | 15        | 3.25%   |
| Aarhus                | 15        | 3.25%   |
| Silkeborg             | 11        | 2.39%   |
| Holstebro             | 9         | 1.95%   |
| Aalborg               | 9         | 1.95%   |
| Norresundby           | 8         | 1.74%   |
| Kongens Lyngby        | 8         | 1.74%   |
| Glostrup Municipality | 8         | 1.74%   |
| Valby                 | 7         | 1.52%   |
| Esbjerg               | 7         | 1.52%   |
| Slagelse              | 6         | 1.3%    |
| Roskilde              | 6         | 1.3%    |
| Naestved              | 6         | 1.3%    |
| Gentofte Municipality | 6         | 1.3%    |
| Aabenraa              | 6         | 1.3%    |
| Skanderborg           | 5         | 1.08%   |
| Nyborg                | 5         | 1.08%   |
| Kastrup               | 5         | 1.08%   |
| Hvidovre              | 5         | 1.08%   |
| Horsens               | 5         | 1.08%   |
| Vanlose               | 4         | 0.87%   |
| Thisted               | 4         | 0.87%   |
| Sindal                | 4         | 0.87%   |
| Risskov               | 4         | 0.87%   |
| Herlev                | 4         | 0.87%   |
| Elsinore              | 4         | 0.87%   |
| Vejle                 | 3         | 0.65%   |
| Vaerlose              | 3         | 0.65%   |
| Taastrup              | 3         | 0.65%   |
| Skive                 | 3         | 0.65%   |
| Rønne                | 3         | 0.65%   |
| Holte                 | 3         | 0.65%   |
| Hojbjerg              | 3         | 0.65%   |
| Hadsund               | 3         | 0.65%   |
| Viborg                | 2         | 0.43%   |
| Svendborg             | 2         | 0.43%   |
| Randers               | 2         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 128       | 178    | 25.15%  |
| WDC                         | 56        | 71     | 11%     |
| Seagate                     | 38        | 44     | 7.47%   |
| Toshiba                     | 37        | 51     | 7.27%   |
| Kingston                    | 37        | 49     | 7.27%   |
| SK hynix                    | 35        | 49     | 6.88%   |
| Hitachi                     | 22        | 26     | 4.32%   |
| Unknown                     | 21        | 24     | 4.13%   |
| SanDisk                     | 21        | 28     | 4.13%   |
| Intel                       | 19        | 22     | 3.73%   |
| Micron Technology           | 15        | 18     | 2.95%   |
| HGST                        | 11        | 16     | 2.16%   |
| LITEON                      | 10        | 17     | 1.96%   |
| PNY                         | 8         | 8      | 1.57%   |
| Apple                       | 7         | 9      | 1.38%   |
| Intenso                     | 6         | 8      | 1.18%   |
| LITEONIT                    | 4         | 5      | 0.79%   |
| OCZ                         | 3         | 3      | 0.59%   |
| Lenovo                      | 3         | 4      | 0.59%   |
| KIOXIA                      | 3         | 4      | 0.59%   |
| Crucial                     | 3         | 3      | 0.59%   |
| A-DATA Technology           | 3         | 3      | 0.59%   |
| Fujitsu                     | 2         | 3      | 0.39%   |
| China                       | 2         | 2      | 0.39%   |
| XPG                         | 1         | 1      | 0.2%    |
| USB3.0                      | 1         | 1      | 0.2%    |
| Transcend                   | 1         | 1      | 0.2%    |
| Solid State Storage         | 1         | 1      | 0.2%    |
| Silicon Motion              | 1         | 1      | 0.2%    |
| Phison Electronics          | 1         | 1      | 0.2%    |
| Phison                      | 1         | 2      | 0.2%    |
| Kingston Technology Company | 1         | 1      | 0.2%    |
| KingFast                    | 1         | 1      | 0.2%    |
| Kingchuxing                 | 1         | 1      | 0.2%    |
| Hewlett-Packard             | 1         | 1      | 0.2%    |
| Dogfish                     | 1         | 1      | 0.2%    |
| ASUS-PHISON                 | 1         | 1      | 0.2%    |
| Apricorn                    | 1         | 2      | 0.2%    |
| ADATA Technology            | 1         | 1      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 10        | 1.87%   |
| Samsung SSD 850 EVO 500GB                           | 9         | 1.68%   |
| Samsung SSD 850 EVO 250GB                           | 8         | 1.5%    |
| Toshiba NVMe SSD Drive 512GB                        | 6         | 1.12%   |
| Samsung NVMe SSD Drive 512GB                        | 6         | 1.12%   |
| Kingston SA400S37480G 480GB SSD                     | 6         | 1.12%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 1.12%   |
| SK hynix NVMe SSD Drive 512GB                       | 5         | 0.93%   |
| Samsung NVMe SSD Drive 1024GB                       | 5         | 0.93%   |
| Unknown MMC Card  32GB                              | 4         | 0.75%   |
| Toshiba NVMe SSD Drive 256GB                        | 4         | 0.75%   |
| SK hynix HFS256G39TND-N210A 256GB SSD               | 4         | 0.75%   |
| Samsung SSD 860 EVO 500GB                           | 4         | 0.75%   |
| Samsung MZVLB512HAJQ-000L7 512GB                    | 4         | 0.75%   |
| PNY CS900 120GB SSD                                 | 4         | 0.75%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 3         | 0.56%   |
| WDC WD2500BEVT-60ZCT1 250GB                         | 3         | 0.56%   |
| WDC WD10JPVX-75JC3T0 1TB                            | 3         | 0.56%   |
| Unknown MMC Card  64GB                              | 3         | 0.56%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB              | 3         | 0.56%   |
| SK hynix NVMe SSD Drive 256GB                       | 3         | 0.56%   |
| Seagate ST2000LM015-2E8174 2TB                      | 3         | 0.56%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB                        | 3         | 0.56%   |
| Samsung SSD 860 EVO 1TB                             | 3         | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 0.56%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 3         | 0.56%   |
| Micron NVMe SSD Drive 512GB                         | 3         | 0.56%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 0.56%   |
| Kingston SA400S37120G 120GB SSD                     | 3         | 0.56%   |
| Intel NVMe SSD Drive 512GB                          | 3         | 0.56%   |
| HGST HTS545050A7E380 500GB                          | 3         | 0.56%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 2         | 0.37%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 2         | 0.37%   |
| WDC WDS100T2G0A-00JH30 1TB SSD                      | 2         | 0.37%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 2         | 0.37%   |
| WDC WD5000BEVT-22ZAT0 500GB                         | 2         | 0.37%   |
| WDC WD2500BEVS-60UST0 250GB                         | 2         | 0.37%   |
| WDC WD10SPCX-24HWST1 1TB                            | 2         | 0.37%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                | 2         | 0.37%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 37        | 43     | 30.83%  |
| WDC      | 32        | 42     | 26.67%  |
| Hitachi  | 22        | 26     | 18.33%  |
| Toshiba  | 13        | 14     | 10.83%  |
| HGST     | 11        | 16     | 9.17%   |
| Fujitsu  | 2         | 3      | 1.67%   |
| USB3.0   | 1         | 1      | 0.83%   |
| Apricorn | 1         | 2      | 0.83%   |
| Apple    | 1         | 2      | 0.83%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 70        | 92     | 35.53%  |
| Kingston            | 32        | 43     | 16.24%  |
| SanDisk             | 12        | 15     | 6.09%   |
| WDC                 | 11        | 14     | 5.58%   |
| Toshiba             | 9         | 11     | 4.57%   |
| LITEON              | 9         | 16     | 4.57%   |
| SK hynix            | 8         | 10     | 4.06%   |
| PNY                 | 8         | 8      | 4.06%   |
| Micron Technology   | 6         | 6      | 3.05%   |
| Intenso             | 5         | 7      | 2.54%   |
| Apple               | 5         | 5      | 2.54%   |
| LITEONIT            | 4         | 5      | 2.03%   |
| Intel               | 4         | 5      | 2.03%   |
| OCZ                 | 3         | 3      | 1.52%   |
| A-DATA Technology   | 3         | 3      | 1.52%   |
| Crucial             | 2         | 2      | 1.02%   |
| China               | 2         | 2      | 1.02%   |
| KingFast            | 1         | 1      | 0.51%   |
| Kingchuxing         | 1         | 1      | 0.51%   |
| Dogfish             | 1         | 1      | 0.51%   |
| ASUS-PHISON         | 1         | 1      | 0.51%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 188       | 251    | 38.6%   |
| NVMe    | 161       | 234    | 33.06%  |
| HDD     | 113       | 149    | 23.2%   |
| MMC     | 23        | 26     | 4.72%   |
| Unknown | 2         | 2      | 0.41%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 280       | 391    | 59.07%  |
| NVMe | 161       | 234    | 33.97%  |
| MMC  | 23        | 26     | 4.85%   |
| SAS  | 10        | 11     | 2.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 219       | 304    | 72.76%  |
| 0.51-1.0   | 65        | 75     | 21.59%  |
| 1.01-2.0   | 12        | 16     | 3.99%   |
| 3.01-4.0   | 3         | 3      | 1%      |
| 4.01-10.0  | 2         | 2      | 0.66%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 145       | 31.32%  |
| 251-500        | 102       | 22.03%  |
| 501-1000       | 68        | 14.69%  |
| 51-100         | 34        | 7.34%   |
| 1-20           | 33        | 7.13%   |
| 1001-2000      | 26        | 5.62%   |
| Unknown        | 21        | 4.54%   |
| 21-50          | 16        | 3.46%   |
| 2001-3000      | 10        | 2.16%   |
| More than 3000 | 8         | 1.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 195       | 40.71%  |
| 21-50          | 79        | 16.49%  |
| 101-250        | 60        | 12.53%  |
| 51-100         | 54        | 11.27%  |
| 251-500        | 39        | 8.14%   |
| 501-1000       | 21        | 4.38%   |
| Unknown        | 21        | 4.38%   |
| 1001-2000      | 7         | 1.46%   |
| 2001-3000      | 2         | 0.42%   |
| More than 3000 | 1         | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 13.33%  |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 6.67%   |
| WDC WD5000BPVT-80HXZT3 500GB          | 1         | 1      | 6.67%   |
| WDC WD5000BEVT-35ZAT0 500GB           | 1         | 1      | 6.67%   |
| Toshiba THNSNF128GCSS 128GB SSD       | 1         | 1      | 6.67%   |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 6.67%   |
| Toshiba KSG60ZSE256G SATA 256GB SSD   | 1         | 1      | 6.67%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 6.67%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 6.67%   |
| Micron Technology 1100 SATA 512GB SSD | 1         | 1      | 6.67%   |
| Kingston SA400S37480G 480GB SSD       | 1         | 1      | 6.67%   |
| HGST HTS545050A7E380 500GB            | 1         | 1      | 6.67%   |
| HGST HTS541010A9E680 1TB              | 1         | 1      | 6.67%   |
| Apple HDD HTS547550A9E384 500GB       | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 4         | 4      | 26.67%  |
| WDC               | 3         | 3      | 20%     |
| Toshiba           | 3         | 3      | 20%     |
| HGST              | 2         | 2      | 13.33%  |
| Micron Technology | 1         | 1      | 6.67%   |
| Kingston          | 1         | 1      | 6.67%   |
| Apple             | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 4         | 4      | 40%     |
| WDC     | 2         | 2      | 20%     |
| HGST    | 2         | 2      | 20%     |
| Toshiba | 1         | 1      | 10%     |
| Apple   | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 10        | 10     | 66.67%  |
| SSD  | 5         | 5      | 33.33%  |

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
| Detected | 303       | 468    | 66.3%   |
| Works    | 139       | 179    | 30.42%  |
| Malfunc  | 15        | 15     | 3.28%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 280       | 57.14%  |
| Samsung Electronics              | 65        | 13.27%  |
| AMD                              | 41        | 8.37%   |
| SK hynix                         | 26        | 5.31%   |
| SanDisk                          | 20        | 4.08%   |
| Toshiba America Info Systems     | 16        | 3.27%   |
| Micron Technology                | 10        | 2.04%   |
| Nvidia                           | 8         | 1.63%   |
| Kingston Technology Company      | 5         | 1.02%   |
| Silicon Motion                   | 4         | 0.82%   |
| Lenovo                           | 3         | 0.61%   |
| Phison Electronics               | 2         | 0.41%   |
| KIOXIA                           | 2         | 0.41%   |
| ADATA Technology                 | 2         | 0.41%   |
| Solid State Storage Technology   | 1         | 0.2%    |
| Silicon Integrated Systems [SiS] | 1         | 0.2%    |
| Lite-On Technology               | 1         | 0.2%    |
| JMicron Technology               | 1         | 0.2%    |
| ASMedia Technology               | 1         | 0.2%    |
| Apple                            | 1         | 0.2%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 42        | 7.94%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 37        | 6.99%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 6.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 29        | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 27        | 5.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 23        | 4.35%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 3.59%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 18        | 3.4%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 17        | 3.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16        | 3.02%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 12        | 2.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 11        | 2.08%   |
| Micron Non-Volatile memory controller                                          | 10        | 1.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 10        | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 10        | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 10        | 1.89%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 8         | 1.51%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 8         | 1.51%   |
| SK hynix Non-Volatile memory controller                                        | 7         | 1.32%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 1.32%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 5         | 0.95%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 5         | 0.95%   |
| Samsung NVMe SSD Controller 980                                                | 5         | 0.95%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 0.95%   |
| Intel SSD 660P Series                                                          | 5         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 5         | 0.95%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 4         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 0.76%   |
| Intel Non-Volatile memory controller                                           | 4         | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 4         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                  | 4         | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 4         | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 4         | 0.76%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 0.57%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 3         | 0.57%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 3         | 0.57%   |
| SanDisk PC SN520 NVMe SSD                                                      | 3         | 0.57%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 0.57%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 286       | 56.63%  |
| NVMe | 162       | 32.08%  |
| IDE  | 35        | 6.93%   |
| RAID | 22        | 4.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 355       | 81.42%  |
| AMD    | 81        | 18.58%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 13        | 2.98%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 10        | 2.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 8         | 1.83%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 7         | 1.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 6         | 1.38%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 6         | 1.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 6         | 1.38%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 6         | 1.38%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 6         | 1.38%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 6         | 1.38%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 6         | 1.38%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 6         | 1.38%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 5         | 1.15%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 5         | 1.15%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 5         | 1.15%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 5         | 1.15%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 1.15%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 4         | 0.92%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 4         | 0.92%   |
| Intel Core i7-8650U CPU @ 1.90GHz           | 4         | 0.92%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 4         | 0.92%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 4         | 0.92%   |
| Intel Core i7-3610QM CPU @ 2.30GHz          | 4         | 0.92%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 4         | 0.92%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 4         | 0.92%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 4         | 0.92%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 4         | 0.92%   |
| Intel Core i5 CPU M 450 @ 2.40GHz           | 4         | 0.92%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 4         | 0.92%   |
| AMD Ryzen 9 5900HS with Radeon Graphics     | 4         | 0.92%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 4         | 0.92%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 3         | 0.69%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 3         | 0.69%   |
| Intel Core i7-4600U CPU @ 2.10GHz           | 3         | 0.69%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 3         | 0.69%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 3         | 0.69%   |
| Intel Core i7-2630QM CPU @ 2.00GHz          | 3         | 0.69%   |
| Intel Core i7-10875H CPU @ 2.30GHz          | 3         | 0.69%   |
| Intel Core i5-8350U CPU @ 1.70GHz           | 3         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 124       | 28.44%  |
| Intel Core i5                  | 123       | 28.21%  |
| Intel Core 2 Duo               | 22        | 5.05%   |
| Intel Core i3                  | 18        | 4.13%   |
| AMD Ryzen 7                    | 17        | 3.9%    |
| Other                          | 16        | 3.67%   |
| Intel Celeron                  | 15        | 3.44%   |
| AMD Ryzen 5                    | 11        | 2.52%   |
| AMD Ryzen 7 PRO                | 10        | 2.29%   |
| AMD Ryzen 9                    | 8         | 1.83%   |
| Intel Pentium Dual-Core        | 7         | 1.61%   |
| Intel Pentium                  | 7         | 1.61%   |
| Intel Atom                     | 6         | 1.38%   |
| Intel Core i9                  | 5         | 1.15%   |
| AMD A8                         | 4         | 0.92%   |
| AMD A6                         | 4         | 0.92%   |
| Intel Pentium M                | 3         | 0.69%   |
| Intel Pentium Silver           | 2         | 0.46%   |
| Intel Pentium Dual             | 2         | 0.46%   |
| Intel Genuine                  | 2         | 0.46%   |
| Intel Core m3                  | 2         | 0.46%   |
| Intel Core 2                   | 2         | 0.46%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.46%   |
| AMD Ryzen 5 PRO                | 2         | 0.46%   |
| AMD Ryzen 3                    | 2         | 0.46%   |
| AMD E1                         | 2         | 0.46%   |
| AMD E                          | 2         | 0.46%   |
| AMD Athlon                     | 2         | 0.46%   |
| AMD A4                         | 2         | 0.46%   |
| AMD A10                        | 2         | 0.46%   |
| Intel Core m7                  | 1         | 0.23%   |
| Intel Celeron M                | 1         | 0.23%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.23%   |
| AMD FX                         | 1         | 0.23%   |
| AMD E2                         | 1         | 0.23%   |
| AMD Athlon X2                  | 1         | 0.23%   |
| AMD Athlon Neo                 | 1         | 0.23%   |
| AMD Athlon II Neo              | 1         | 0.23%   |
| AMD Athlon II Dual-Core        | 1         | 0.23%   |
| AMD Athlon II                  | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 218       | 50%     |
| 4      | 136       | 31.19%  |
| 8      | 40        | 9.17%   |
| 6      | 27        | 6.19%   |
| 1      | 13        | 2.98%   |
| 14     | 1         | 0.23%   |
| 12     | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 436       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 334       | 76.61%  |
| 1      | 102       | 23.39%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 420       | 95.89%  |
| Unknown        | 13        | 2.97%   |
| 32-bit         | 5         | 1.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 101       | 22.44%  |
| 0x40651    | 24        | 5.33%   |
| 0x206a7    | 24        | 5.33%   |
| 0x406e3    | 23        | 5.11%   |
| 0x306a9    | 23        | 5.11%   |
| 0x1067a    | 19        | 4.22%   |
| 0x806e9    | 17        | 3.78%   |
| 0x806ea    | 16        | 3.56%   |
| 0x306c3    | 16        | 3.56%   |
| 0x906ea    | 15        | 3.33%   |
| 0x806ec    | 14        | 3.11%   |
| 0x20655    | 11        | 2.44%   |
| 0x906e9    | 8         | 1.78%   |
| 0x0a50000c | 8         | 1.78%   |
| 0x08600106 | 7         | 1.56%   |
| 0x906ed    | 6         | 1.33%   |
| 0x806eb    | 6         | 1.33%   |
| 0x20652    | 6         | 1.33%   |
| 0x08600104 | 6         | 1.33%   |
| 0x806c1    | 5         | 1.11%   |
| 0x706e5    | 5         | 1.11%   |
| 0x08108102 | 5         | 1.11%   |
| 0x6fd      | 4         | 0.89%   |
| 0x506e3    | 4         | 0.89%   |
| 0x406c3    | 4         | 0.89%   |
| 0x306d4    | 4         | 0.89%   |
| 0x30678    | 4         | 0.89%   |
| 0x10676    | 4         | 0.89%   |
| 0x07030105 | 4         | 0.89%   |
| 0x6d8      | 3         | 0.67%   |
| 0x08608103 | 3         | 0.67%   |
| 0x0810100b | 3         | 0.67%   |
| 0xa0652    | 2         | 0.44%   |
| 0x706a1    | 2         | 0.44%   |
| 0x6fb      | 2         | 0.44%   |
| 0x6fa      | 2         | 0.44%   |
| 0x6f6      | 2         | 0.44%   |
| 0x506c9    | 2         | 0.44%   |
| 0x406c4    | 2         | 0.44%   |
| 0x40661    | 2         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 102       | 23.39%  |
| Haswell          | 45        | 10.32%  |
| Skylake          | 35        | 8.03%   |
| SandyBridge      | 32        | 7.34%   |
| IvyBridge        | 29        | 6.65%   |
| Penryn           | 26        | 5.96%   |
| Westmere         | 17        | 3.9%    |
| Zen 2            | 15        | 3.44%   |
| Unknown          | 14        | 3.21%   |
| Zen 3            | 13        | 2.98%   |
| Silvermont       | 12        | 2.75%   |
| Core             | 12        | 2.75%   |
| Zen+             | 10        | 2.29%   |
| TigerLake        | 8         | 1.83%   |
| Broadwell        | 8         | 1.83%   |
| Icelake          | 6         | 1.38%   |
| Excavator        | 6         | 1.38%   |
| CometLake        | 6         | 1.38%   |
| Puma             | 5         | 1.15%   |
| P6               | 5         | 1.15%   |
| Bobcat           | 4         | 0.92%   |
| Zen              | 3         | 0.69%   |
| K8 Hammer        | 3         | 0.69%   |
| K8 & K10 hybrid  | 3         | 0.69%   |
| K10              | 3         | 0.69%   |
| Goldmont plus    | 3         | 0.69%   |
| Steamroller      | 2         | 0.46%   |
| Goldmont         | 2         | 0.46%   |
| Bonnell          | 2         | 0.46%   |
| Alderlake Hybrid | 2         | 0.46%   |
| Piledriver       | 1         | 0.23%   |
| Nehalem          | 1         | 0.23%   |
| K10 Llano        | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 316       | 56.83%  |
| Nvidia                           | 136       | 24.46%  |
| AMD                              | 103       | 18.53%  |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 30        | 5.22%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 28        | 4.87%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 27        | 4.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 25        | 4.35%   |
| Intel UHD Graphics 620                                                                   | 24        | 4.17%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 23        | 4%      |
| Intel HD Graphics 620                                                                    | 16        | 2.78%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 2.78%   |
| AMD Renoir                                                                               | 15        | 2.61%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 14        | 2.43%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 14        | 2.43%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 13        | 2.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 10        | 1.74%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 1.39%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 1.39%   |
| Intel HD Graphics 630                                                                    | 8         | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.39%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 1.22%   |
| Nvidia GP108M [GeForce MX150]                                                            | 6         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 1.04%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 1.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 6         | 1.04%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.87%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 0.87%   |
| AMD Rembrandt [Radeon 680M]                                                              | 5         | 0.87%   |
| AMD Lucienne                                                                             | 5         | 0.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.7%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 4         | 0.7%    |
| Intel HD Graphics 530                                                                    | 4         | 0.7%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.7%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 0.7%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.7%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.7%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.52%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 3         | 0.52%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 208       | 47.71%  |
| Intel + Nvidia | 92        | 21.1%   |
| 1 x AMD        | 64        | 14.68%  |
| 1 x Nvidia     | 31        | 7.11%   |
| Intel + AMD    | 15        | 3.44%   |
| 2 x AMD        | 12        | 2.75%   |
| AMD + Nvidia   | 12        | 2.75%   |
| Other          | 1         | 0.23%   |
| 1 x SiS        | 1         | 0.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 364       | 82.54%  |
| Proprietary | 67        | 15.19%  |
| Unknown     | 10        | 2.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 268       | 60.5%   |
| 0.01-0.5   | 62        | 14%     |
| 1.01-2.0   | 54        | 12.19%  |
| 3.01-4.0   | 23        | 5.19%   |
| 0.51-1.0   | 23        | 5.19%   |
| 5.01-6.0   | 8         | 1.81%   |
| 7.01-8.0   | 3         | 0.68%   |
| 2.01-3.0   | 2         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 109       | 21.37%  |
| LG Display              | 73        | 14.31%  |
| Chimei Innolux          | 56        | 10.98%  |
| Samsung Electronics     | 49        | 9.61%   |
| BOE                     | 49        | 9.61%   |
| Lenovo                  | 30        | 5.88%   |
| Dell                    | 20        | 3.92%   |
| Sharp                   | 18        | 3.53%   |
| Apple                   | 15        | 2.94%   |
| Chi Mei Optoelectronics | 10        | 1.96%   |
| Philips                 | 8         | 1.57%   |
| PANDA                   | 8         | 1.57%   |
| Hewlett-Packard         | 7         | 1.37%   |
| Goldstar                | 5         | 0.98%   |
| AOC                     | 5         | 0.98%   |
| InfoVision              | 4         | 0.78%   |
| ASUSTek Computer        | 4         | 0.78%   |
| Sony                    | 3         | 0.59%   |
| LG Philips              | 3         | 0.59%   |
| BenQ                    | 3         | 0.59%   |
| TMX                     | 2         | 0.39%   |
| Seiko/Epson             | 2         | 0.39%   |
| Panasonic               | 2         | 0.39%   |
| Packard Bell            | 2         | 0.39%   |
| LGD                     | 2         | 0.39%   |
| CSO                     | 2         | 0.39%   |
| CPT                     | 2         | 0.39%   |
| ViewSonic               | 1         | 0.2%    |
| Vestel Elektronik       | 1         | 0.2%    |
| Valve                   | 1         | 0.2%    |
| Tianma XM               | 1         | 0.2%    |
| RTK                     | 1         | 0.2%    |
| PVT                     | 1         | 0.2%    |
| MSI                     | 1         | 0.2%    |
| JDI                     | 1         | 0.2%    |
| IBM                     | 1         | 0.2%    |
| HKC                     | 1         | 0.2%    |
| Haier                   | 1         | 0.2%    |
| Fujitsu Siemens         | 1         | 0.2%    |
| DENON                   | 1         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 7         | 1.34%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 6         | 1.15%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.96%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 4         | 0.77%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 4         | 0.77%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 4         | 0.77%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 4         | 0.77%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 4         | 0.77%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 3         | 0.57%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                 | 3         | 0.57%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 0.57%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch         | 3         | 0.57%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 3         | 0.57%   |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch                    | 3         | 0.57%   |
| BOE LCD Monitor BOE0691 1920x1080 280x165mm 12.8-inch                    | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch           | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO109E 1600x900 382x214mm 17.2-inch            | 3         | 0.57%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 3         | 0.57%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                  | 2         | 0.38%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 2         | 0.38%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 2         | 0.38%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch                  | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3641 1280x800 331x207mm 15.4-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch     | 2         | 0.38%   |
| Samsung Electronics LCD Monitor SDC4A42 1366x768 309x174mm 14.0-inch     | 2         | 0.38%   |
| LG Display LCD Monitor LGD05E5 1920x1080 340x190mm 15.3-inch             | 2         | 0.38%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch             | 2         | 0.38%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.38%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch              | 2         | 0.38%   |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch              | 2         | 0.38%   |
| LG Display LCD Monitor LGD0226 1600x900 382x215mm 17.3-inch              | 2         | 0.38%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x193mm 15.5-inch                  | 2         | 0.38%   |
| Lenovo LCD Monitor LEN4050 1280x800 331x207mm 15.4-inch                  | 2         | 0.38%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.38%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch             | 2         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 214       | 44.12%  |
| 1366x768 (WXGA)    | 91        | 18.76%  |
| 3840x2160 (4K)     | 36        | 7.42%   |
| 1600x900 (HD+)     | 36        | 7.42%   |
| 2560x1440 (QHD)    | 22        | 4.54%   |
| 1280x800 (WXGA)    | 18        | 3.71%   |
| 1920x1200 (WUXGA)  | 12        | 2.47%   |
| 1680x1050 (WSXGA+) | 9         | 1.86%   |
| 1440x900 (WXGA+)   | 8         | 1.65%   |
| 2560x1600          | 7         | 1.44%   |
| 2880x1800          | 6         | 1.24%   |
| 3440x1440          | 4         | 0.82%   |
| 1400x1050          | 3         | 0.62%   |
| 800x1280           | 2         | 0.41%   |
| 3840x2400          | 2         | 0.41%   |
| 3200x1800 (QHD+)   | 2         | 0.41%   |
| 3000x2000          | 2         | 0.41%   |
| 1280x1024 (SXGA)   | 2         | 0.41%   |
| 1024x600           | 2         | 0.41%   |
| 3840x1600          | 1         | 0.21%   |
| 3840x1100          | 1         | 0.21%   |
| 3840x1080          | 1         | 0.21%   |
| 2160x1440          | 1         | 0.21%   |
| 1920x540           | 1         | 0.21%   |
| 1360x768           | 1         | 0.21%   |
| Unknown            | 1         | 0.21%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 189       | 36.84%  |
| 14      | 77        | 15.01%  |
| 13      | 74        | 14.42%  |
| 17      | 38        | 7.41%   |
| 27      | 24        | 4.68%   |
| 12      | 23        | 4.48%   |
| 24      | 19        | 3.7%    |
| Unknown | 11        | 2.14%   |
| 23      | 10        | 1.95%   |
| 31      | 8         | 1.56%   |
| 84      | 5         | 0.97%   |
| 22      | 5         | 0.97%   |
| 34      | 4         | 0.78%   |
| 11      | 4         | 0.78%   |
| 21      | 3         | 0.58%   |
| 18      | 3         | 0.58%   |
| 10      | 3         | 0.58%   |
| 72      | 2         | 0.39%   |
| 25      | 2         | 0.39%   |
| 19      | 2         | 0.39%   |
| 16      | 2         | 0.39%   |
| 65      | 1         | 0.19%   |
| 57      | 1         | 0.19%   |
| 37      | 1         | 0.19%   |
| 29      | 1         | 0.19%   |
| 7       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 296       | 58.5%   |
| 201-300     | 67        | 13.24%  |
| 501-600     | 46        | 9.09%   |
| 351-400     | 46        | 9.09%   |
| 601-700     | 14        | 2.77%   |
| 401-500     | 11        | 2.17%   |
| Unknown     | 11        | 2.17%   |
| 1501-2000   | 7         | 1.38%   |
| 701-800     | 4         | 0.79%   |
| 1001-1500   | 2         | 0.4%    |
| 801-900     | 1         | 0.2%    |
| 1-100       | 1         | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 360       | 79.65%  |
| 16/10   | 65        | 14.38%  |
| Unknown | 8         | 1.77%   |
| 3/2     | 6         | 1.33%   |
| 21/9    | 5         | 1.11%   |
| 4/3     | 3         | 0.66%   |
| 5/4     | 2         | 0.44%   |
| 3.40    | 1         | 0.22%   |
| 0.67    | 1         | 0.22%   |
| 0.62    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 189       | 37.06%  |
| 81-90          | 121       | 23.73%  |
| 71-80          | 31        | 6.08%   |
| 121-130        | 29        | 5.69%   |
| 201-250        | 25        | 4.9%    |
| 301-350        | 24        | 4.71%   |
| 61-70          | 20        | 3.92%   |
| 351-500        | 12        | 2.35%   |
| 251-300        | 12        | 2.35%   |
| Unknown        | 11        | 2.16%   |
| More than 1000 | 9         | 1.76%   |
| 131-140        | 8         | 1.57%   |
| 51-60          | 5         | 0.98%   |
| 141-150        | 4         | 0.78%   |
| 41-50          | 3         | 0.59%   |
| 151-200        | 2         | 0.39%   |
| 91-100         | 2         | 0.39%   |
| 1-40           | 1         | 0.2%    |
| 111-120        | 1         | 0.2%    |
| 501-1000       | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 226       | 45.29%  |
| 101-120       | 124       | 24.85%  |
| 51-100        | 68        | 13.63%  |
| 161-240       | 41        | 8.22%   |
| More than 240 | 25        | 5.01%   |
| Unknown       | 11        | 2.2%    |
| 1-50          | 4         | 0.8%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 358       | 79.56%  |
| 2     | 72        | 16%     |
| 3     | 10        | 2.22%   |
| 0     | 8         | 1.78%   |
| 4     | 2         | 0.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 268       | 38.9%   |
| Realtek Semiconductor             | 193       | 28.01%  |
| Qualcomm Atheros                  | 84        | 12.19%  |
| Broadcom                          | 38        | 5.52%   |
| Sierra Wireless                   | 12        | 1.74%   |
| MediaTek                          | 12        | 1.74%   |
| Lenovo                            | 12        | 1.74%   |
| Broadcom Limited                  | 11        | 1.6%    |
| Ericsson Business Mobile Networks | 9         | 1.31%   |
| Ralink                            | 7         | 1.02%   |
| Nvidia                            | 6         | 0.87%   |
| Marvell Technology Group          | 5         | 0.73%   |
| Ralink Technology                 | 3         | 0.44%   |
| Qualcomm                          | 3         | 0.44%   |
| Dell                              | 3         | 0.44%   |
| ASIX Electronics                  | 3         | 0.44%   |
| Samsung Electronics               | 2         | 0.29%   |
| NetGear                           | 2         | 0.29%   |
| DisplayLink                       | 2         | 0.29%   |
| ZyXEL Communications              | 1         | 0.15%   |
| Xiaomi                            | 1         | 0.15%   |
| TP-Link                           | 1         | 0.15%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.15%   |
| Philips (or NXP)                  | 1         | 0.15%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.15%   |
| Linksys                           | 1         | 0.15%   |
| ICS Advent                        | 1         | 0.15%   |
| Huawei Technologies               | 1         | 0.15%   |
| Hewlett-Packard                   | 1         | 0.15%   |
| Google                            | 1         | 0.15%   |
| Fibocom                           | 1         | 0.15%   |
| D-Link System                     | 1         | 0.15%   |
| ASUSTek Computer                  | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 124       | 14.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 32        | 3.69%   |
| Intel Wi-Fi 6 AX200                                                     | 29        | 3.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 28        | 3.23%   |
| Intel Wireless 8265 / 8275                                              | 27        | 3.11%   |
| Intel Wireless 7260                                                     | 27        | 3.11%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 24        | 2.77%   |
| Intel Wireless 8260                                                     | 19        | 2.19%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 18        | 2.08%   |
| Intel Wireless 7265                                                     | 16        | 1.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 15        | 1.73%   |
| Intel Ethernet Connection (4) I219-LM                                   | 14        | 1.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 1.5%    |
| Intel Ethernet Connection I218-LM                                       | 12        | 1.38%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 1.27%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 1.15%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.04%   |
| Intel Ethernet Connection I219-LM                                       | 9         | 1.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 0.92%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 0.92%   |
| Intel Ethernet Connection I219-V                                        | 8         | 0.92%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                                | 8         | 0.92%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 0.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 0.81%   |
| Intel Centrino Ultimate-N 6300                                          | 7         | 0.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 0.81%   |
| Sierra Wireless EM7455                                                  | 6         | 0.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 0.69%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 0.69%   |
| Intel Ethernet Connection I217-LM                                       | 6         | 0.69%   |
| Intel Ethernet Connection (4) I219-V                                    | 6         | 0.69%   |
| Sierra Wireless EM7345 4G LTE                                           | 5         | 0.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 0.58%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.58%   |
| Intel Wireless-AC 9260                                                  | 5         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 261       | 57.11%  |
| Qualcomm Atheros      | 68        | 14.88%  |
| Realtek Semiconductor | 48        | 10.5%   |
| Broadcom              | 27        | 5.91%   |
| Sierra Wireless       | 12        | 2.63%   |
| MediaTek              | 12        | 2.63%   |
| Ralink                | 7         | 1.53%   |
| Broadcom Limited      | 7         | 1.53%   |
| Ralink Technology     | 3         | 0.66%   |
| Qualcomm              | 2         | 0.44%   |
| NetGear               | 2         | 0.44%   |
| Dell                  | 2         | 0.44%   |
| ZyXEL Communications  | 1         | 0.22%   |
| TP-Link               | 1         | 0.22%   |
| Philips (or NXP)      | 1         | 0.22%   |
| Fibocom               | 1         | 0.22%   |
| D-Link System         | 1         | 0.22%   |
| ASUSTek Computer      | 1         | 0.22%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 29        | 6.35%   |
| Intel Wireless 8265 / 8275                                              | 27        | 5.91%   |
| Intel Wireless 7260                                                     | 27        | 5.91%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 24        | 5.25%   |
| Intel Wireless 8260                                                     | 19        | 4.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 18        | 3.94%   |
| Intel Wireless 7265                                                     | 16        | 3.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 13        | 2.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 11        | 2.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 10        | 2.19%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 9         | 1.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 9         | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 1.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 1.75%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 1.75%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 1.75%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 7         | 1.53%   |
| Intel Centrino Ultimate-N 6300                                          | 7         | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 7         | 1.53%   |
| Sierra Wireless EM7455                                                  | 6         | 1.31%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 6         | 1.31%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 1.31%   |
| Sierra Wireless EM7345 4G LTE                                           | 5         | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 5         | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 1.09%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 1.09%   |
| Intel Wireless-AC 9260                                                  | 5         | 1.09%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 5         | 1.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 5         | 1.09%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 1.09%   |
| Intel Centrino Advanced-N 6200                                          | 5         | 1.09%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 5         | 1.09%   |
| Intel Wireless 3165                                                     | 4         | 0.88%   |
| Intel Wireless 3160                                                     | 4         | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 4         | 0.88%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.88%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 177       | 44.92%  |
| Intel                            | 137       | 34.77%  |
| Qualcomm Atheros                 | 23        | 5.84%   |
| Broadcom                         | 17        | 4.31%   |
| Lenovo                           | 12        | 3.05%   |
| Nvidia                           | 6         | 1.52%   |
| Marvell Technology Group         | 5         | 1.27%   |
| Broadcom Limited                 | 4         | 1.02%   |
| ASIX Electronics                 | 3         | 0.76%   |
| Samsung Electronics              | 2         | 0.51%   |
| DisplayLink                      | 2         | 0.51%   |
| Xiaomi                           | 1         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.25%   |
| Qualcomm                         | 1         | 0.25%   |
| Linksys                          | 1         | 0.25%   |
| ICS Advent                       | 1         | 0.25%   |
| Google                           | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 124       | 31.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 32        | 8.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 28        | 7.07%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 3.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 14        | 3.54%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 3.03%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 2.27%   |
| Intel Ethernet Connection I219-V                                  | 8         | 2.02%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 2.02%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.52%   |
| Intel Ethernet Connection (4) I219-V                              | 6         | 1.52%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 1.26%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4         | 1.01%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 1.01%   |
| Lenovo USB-C Dock Ethernet                                        | 4         | 1.01%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 1.01%   |
| Intel Ethernet Connection (10) I219-V                             | 4         | 1.01%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 0.76%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.76%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 3         | 0.76%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.76%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.76%   |
| Intel Ethernet Connection (13) I219-V                             | 3         | 0.76%   |
| Intel 82567LM Gigabit Network Connection                          | 3         | 0.76%   |
| Intel 82566MM Gigabit Network Connection                          | 3         | 0.76%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.76%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.76%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.51%   |
| Realtek Realtek Ethernet controller                               | 2         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.51%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.51%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.51%   |
| Lenovo ThinkPad Lan                                               | 2         | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.51%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 431       | 52.75%  |
| Ethernet | 372       | 45.53%  |
| Modem    | 13        | 1.59%   |
| Unknown  | 1         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 362       | 77.19%  |
| Ethernet | 107       | 22.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 341       | 78.03%  |
| 1     | 86        | 19.68%  |
| 3     | 6         | 1.37%   |
| 0     | 4         | 0.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 418       | 95.65%  |
| Yes  | 19        | 4.35%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 194       | 52.15%  |
| Broadcom                        | 38        | 10.22%  |
| Realtek Semiconductor           | 26        | 6.99%   |
| Qualcomm Atheros Communications | 21        | 5.65%   |
| Lite-On Technology              | 18        | 4.84%   |
| IMC Networks                    | 17        | 4.57%   |
| Foxconn / Hon Hai               | 15        | 4.03%   |
| Apple                           | 13        | 3.49%   |
| Hewlett-Packard                 | 9         | 2.42%   |
| Cambridge Silicon Radio         | 4         | 1.08%   |
| Dell                            | 3         | 0.81%   |
| Realtek                         | 2         | 0.54%   |
| Ralink Technology               | 2         | 0.54%   |
| Ralink                          | 2         | 0.54%   |
| ASUSTek Computer                | 2         | 0.54%   |
| USI                             | 1         | 0.27%   |
| Toshiba                         | 1         | 0.27%   |
| Taiyo Yuden                     | 1         | 0.27%   |
| MediaTek                        | 1         | 0.27%   |
| D-Link System                   | 1         | 0.27%   |
| Chicony Electronics             | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 102       | 27.42%  |
| Intel AX200 Bluetooth                               | 28        | 7.53%   |
| Intel AX201 Bluetooth                               | 22        | 5.91%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 5.11%   |
| Realtek Bluetooth Radio                             | 16        | 4.3%    |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 4.3%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 10        | 2.69%   |
| Apple Bluetooth Host Controller                     | 10        | 2.69%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 2.15%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 8         | 2.15%   |
| IMC Networks Wireless_Device                        | 8         | 2.15%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 2.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 1.61%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 1.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 6         | 1.61%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 1.34%   |
| Lite-On Bluetooth Device                            | 4         | 1.08%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.08%   |
| Intel AX210 Bluetooth                               | 4         | 1.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 1.08%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 4         | 1.08%   |
| Realtek RTL8723B Bluetooth                          | 3         | 0.81%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 0.81%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 0.81%   |
| Dell DW375 Bluetooth Module                         | 3         | 0.81%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.81%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.81%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.54%   |
| Realtek Bluetooth Radio                             | 2         | 0.54%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.54%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.54%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 2         | 0.54%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.54%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 0.54%   |
| USI Bluetooth Device                                | 1         | 0.27%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.27%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)             | 1         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 342       | 62.87%  |
| AMD                              | 85        | 15.63%  |
| Nvidia                           | 77        | 14.15%  |
| Lenovo                           | 10        | 1.84%   |
| GN Netcom                        | 6         | 1.1%    |
| Plantronics                      | 3         | 0.55%   |
| Hewlett-Packard                  | 3         | 0.55%   |
| Realtek Semiconductor            | 2         | 0.37%   |
| Razer USA                        | 2         | 0.37%   |
| Kingston Technology              | 2         | 0.37%   |
| VIA Technologies                 | 1         | 0.18%   |
| Texas Instruments                | 1         | 0.18%   |
| Silicon Integrated Systems [SiS] | 1         | 0.18%   |
| Sennheiser Communications        | 1         | 0.18%   |
| Samson Technologies              | 1         | 0.18%   |
| RODE Microphones                 | 1         | 0.18%   |
| NAD Electronics                  | 1         | 0.18%   |
| DSEA A/S                         | 1         | 0.18%   |
| Creative Technology              | 1         | 0.18%   |
| C-Media Electronics              | 1         | 0.18%   |
| Blue Microphones                 | 1         | 0.18%   |
| Afatech                          | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 75        | 11.21%  |
| AMD Family 17h/19h HD Audio Controller                                     | 51        | 7.62%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 32        | 4.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 32        | 4.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 28        | 4.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 25        | 3.74%   |
| Intel Cannon Lake PCH cAVS                                                 | 25        | 3.74%   |
| Intel 8 Series HD Audio Controller                                         | 25        | 3.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 20        | 2.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 20        | 2.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 18        | 2.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 16        | 2.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 14        | 2.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 12        | 1.79%   |
| AMD FCH Azalia Controller                                                  | 11        | 1.64%   |
| Intel CM238 HD Audio Controller                                            | 10        | 1.49%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 9         | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 1.2%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                               | 8         | 1.2%    |
| Intel Broadwell-U Audio Controller                                         | 8         | 1.2%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 8         | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                              | 7         | 1.05%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7         | 1.05%   |
| AMD Kabini HDMI/DP Audio                                                   | 7         | 1.05%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 0.75%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                              | 5         | 0.75%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 5         | 0.75%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 0.75%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 0.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 5         | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 0.6%    |
| Nvidia High Definition Audio Controller                                    | 4         | 0.6%    |
| Nvidia GT216 HDMI Audio Controller                                         | 4         | 0.6%    |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                  | 4         | 0.6%    |
| AMD High Definition Audio Controller                                       | 4         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 74        | 31.36%  |
| SK hynix            | 61        | 25.85%  |
| Micron Technology   | 32        | 13.56%  |
| Kingston            | 25        | 10.59%  |
| Unknown             | 15        | 6.36%   |
| Crucial             | 7         | 2.97%   |
| Elpida              | 5         | 2.12%   |
| Nanya Technology    | 3         | 1.27%   |
| Corsair             | 3         | 1.27%   |
| A-DATA Technology   | 3         | 1.27%   |
| Ramaxel Technology  | 2         | 0.85%   |
| Transcend           | 1         | 0.42%   |
| G.Skill             | 1         | 0.42%   |
| fef5                | 1         | 0.42%   |
| Avant               | 1         | 0.42%   |
| Apacer              | 1         | 0.42%   |
| Unknown             | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 3.2%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 2.4%    |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 4         | 1.6%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.6%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.6%    |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 4         | 1.6%    |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 1.2%    |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 3         | 1.2%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 1.2%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 1.2%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 3         | 1.2%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.2%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.2%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.8%    |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 2         | 0.8%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 2         | 0.8%    |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.8%    |
| SK hynix RAM HMA851S6AFR6N-UH 2GB SODIMM LPDDR4 2667MT/s         | 2         | 0.8%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.8%    |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.8%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 2         | 0.8%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.8%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.8%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 0.8%    |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 0.8%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.8%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.8%    |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.8%    |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.8%    |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Micron RAM 4ATS1G64HZ-2G3A1 8GB SODIMM DDR4 2400MT/s             | 2         | 0.8%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.8%    |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s           | 2         | 0.8%    |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 98        | 48.51%  |
| DDR3    | 66        | 32.67%  |
| LPDDR3  | 16        | 7.92%   |
| DDR2    | 9         | 4.46%   |
| LPDDR4  | 7         | 3.47%   |
| Unknown | 2         | 0.99%   |
| SDRAM   | 1         | 0.5%    |
| LPDDR5  | 1         | 0.5%    |
| DRAM    | 1         | 0.5%    |
| DDR     | 1         | 0.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 177       | 87.19%  |
| Row Of Chips | 18        | 8.87%   |
| Chip         | 4         | 1.97%   |
| Unknown      | 3         | 1.48%   |
| DIMM         | 1         | 0.49%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 96        | 44.44%  |
| 4096  | 50        | 23.15%  |
| 16384 | 39        | 18.06%  |
| 2048  | 22        | 10.19%  |
| 32768 | 5         | 2.31%   |
| 1024  | 2         | 0.93%   |
| 512   | 2         | 0.93%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 51        | 23.61%  |
| 2667    | 49        | 22.69%  |
| 3200    | 31        | 14.35%  |
| 2133    | 22        | 10.19%  |
| 2400    | 12        | 5.56%   |
| 1334    | 11        | 5.09%   |
| 1333    | 8         | 3.7%    |
| 1867    | 7         | 3.24%   |
| 667     | 7         | 3.24%   |
| Unknown | 4         | 1.85%   |
| 4266    | 3         | 1.39%   |
| 1067    | 3         | 1.39%   |
| 4267    | 2         | 0.93%   |
| 2933    | 2         | 0.93%   |
| 8400    | 1         | 0.46%   |
| 4199    | 1         | 0.46%   |
| 3266    | 1         | 0.46%   |
| 800     | 1         | 0.46%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Canon              | 2         | 50%     |
| Hewlett-Packard    | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP DeskJet 3700 series   | 1         | 25%     |
| Canon PIXMA MX370 Series | 1         | 25%     |
| Canon PIXMA MP280        | 1         | 25%     |
| Brother HL-1210W series  | 1         | 25%     |

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
| Chicony Electronics                    | 118       | 30.89%  |
| Acer                                   | 50        | 13.09%  |
| IMC Networks                           | 38        | 9.95%   |
| Realtek Semiconductor                  | 30        | 7.85%   |
| Microdia                               | 18        | 4.71%   |
| Quanta                                 | 16        | 4.19%   |
| Lite-On Technology                     | 16        | 4.19%   |
| Suyin                                  | 15        | 3.93%   |
| Sunplus Innovation Technology          | 14        | 3.66%   |
| Cheng Uei Precision Industry (Foxlink) | 13        | 3.4%    |
| Apple                                  | 10        | 2.62%   |
| Logitech                               | 9         | 2.36%   |
| Syntek                                 | 8         | 2.09%   |
| Lenovo                                 | 5         | 1.31%   |
| Silicon Motion                         | 4         | 1.05%   |
| Samsung Electronics                    | 3         | 0.79%   |
| DJJHFA1BIF5595                         | 3         | 0.79%   |
| Primax Electronics                     | 2         | 0.52%   |
| Alcor Micro                            | 2         | 0.52%   |
| Z-Star Microelectronics                | 1         | 0.26%   |
| Sonix Technology                       | 1         | 0.26%   |
| Ricoh                                  | 1         | 0.26%   |
| MacroSilicon                           | 1         | 0.26%   |
| Luxvisions Innotech Limited            | 1         | 0.26%   |
| Genesys Logic                          | 1         | 0.26%   |
| GEMBIRD                                | 1         | 0.26%   |
| ALi                                    | 1         | 0.26%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 32        | 8.33%   |
| Realtek Integrated_Webcam_HD             | 15        | 3.91%   |
| IMC Networks Integrated Camera           | 15        | 3.91%   |
| Acer Integrated Camera                   | 15        | 3.91%   |
| Chicony HD Webcam                        | 14        | 3.65%   |
| IMC Networks USB2.0 HD UVC WebCam        | 10        | 2.6%    |
| Microdia Integrated_Webcam_HD            | 9         | 2.34%   |
| Lite-On Integrated Camera                | 9         | 2.34%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 8         | 2.08%   |
| Chicony HP HD Camera                     | 6         | 1.56%   |
| Apple Built-in iSight                    | 6         | 1.56%   |
| Acer Lenovo EasyCamera                   | 6         | 1.56%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 5         | 1.3%    |
| Acer SunplusIT Integrated Camera         | 5         | 1.3%    |
| Syntek Lenovo EasyCamera                 | 4         | 1.04%   |
| Quanta USB2.0 HD UVC WebCam              | 4         | 1.04%   |
| Chicony USB 2.0 Camera                   | 4         | 1.04%   |
| Chicony Integrated Camera (1280x720@30)  | 4         | 1.04%   |
| Chicony HP Truevision HD                 | 4         | 1.04%   |
| Acer HD Webcam                           | 4         | 1.04%   |
| Acer EasyCamera                          | 4         | 1.04%   |
| Sunplus Laptop Integrated WebCam HD      | 3         | 0.78%   |
| Sunplus Integrated_Webcam_HD             | 3         | 0.78%   |
| Samsung Galaxy A5 (MTP)                  | 3         | 0.78%   |
| Quanta HP Webcam                         | 3         | 0.78%   |
| Quanta HD Webcam                         | 3         | 0.78%   |
| Microdia USB 2.0 Camera                  | 3         | 0.78%   |
| Microdia Integrated Webcam               | 3         | 0.78%   |
| Lite-On HP HD Webcam                     | 3         | 0.78%   |
| Lenovo Integrated Webcam                 | 3         | 0.78%   |
| IMC Networks USB2.0 HD IR UVC WebCam     | 3         | 0.78%   |
| IMC Networks USB Camera                  | 3         | 0.78%   |
| DJJHFA1BIF5595 HP HD Camera              | 3         | 0.78%   |
| Chicony USB2.0 Camera                    | 3         | 0.78%   |
| Chicony Lenovo EasyCamera                | 3         | 0.78%   |
| Chicony Integrated Camera [ThinkPad]     | 3         | 0.78%   |
| Acer ThinkPad P50 Integrated Camera      | 3         | 0.78%   |
| Acer SunplusIT INC. Integrated Camera    | 3         | 0.78%   |
| Acer Lenovo Integrated Webcam            | 3         | 0.78%   |
| Syntek Integrated Camera                 | 2         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 46        | 38.66%  |
| Synaptics                  | 35        | 29.41%  |
| Upek                       | 13        | 10.92%  |
| Shenzhen Goodix Technology | 9         | 7.56%   |
| AuthenTec                  | 9         | 7.56%   |
| Elan Microelectronics      | 4         | 3.36%   |
| STMicroelectronics         | 2         | 1.68%   |
| LighTuning Technology      | 1         | 0.84%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 20.17%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 13        | 10.92%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 10.08%  |
| Validity Sensors Synaptics WBDI                                            | 8         | 6.72%   |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 5.04%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 4.2%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.36%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.36%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.36%   |
| AuthenTec AES2810                                                          | 4         | 3.36%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 4         | 3.36%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 2.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.68%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.68%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.68%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.68%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.68%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.68%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 1.68%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.68%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.68%   |
| Unknown                                                                    | 2         | 1.68%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.84%   |
| Validity Sensors VFS491                                                    | 1         | 0.84%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.84%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.84%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.84%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.84%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.84%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.84%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 37        | 61.67%  |
| Broadcom    | 15        | 25%     |
| Upek        | 6         | 10%     |
| Lenovo      | 2         | 3.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 37        | 61.67%  |
| Broadcom 5880                                                                | 7         | 11.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 8.33%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 3.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 3.33%   |
| Broadcom 58200                                                               | 1         | 1.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 234       | 52.23%  |
| 1     | 155       | 34.6%   |
| 2     | 47        | 10.49%  |
| 3     | 8         | 1.79%   |
| 4     | 2         | 0.45%   |
| 10    | 1         | 0.22%   |
| 6     | 1         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 118       | 41.55%  |
| Chipcard                 | 56        | 19.72%  |
| Graphics card            | 41        | 14.44%  |
| Net/wireless             | 17        | 5.99%   |
| Multimedia controller    | 17        | 5.99%   |
| Card reader              | 9         | 3.17%   |
| Camera                   | 6         | 2.11%   |
| Communication controller | 5         | 1.76%   |
| Storage                  | 4         | 1.41%   |
| Net/ethernet             | 4         | 1.41%   |
| Bluetooth                | 4         | 1.41%   |
| Sound                    | 2         | 0.7%    |
| Modem                    | 1         | 0.35%   |

