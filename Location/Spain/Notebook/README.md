Linux in Spain - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

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

Total: 4422

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Pavilion Laptop 14-dv1xx... | [72899a615b](https://linux-hardware.org/?probe=72899a615b) | Aug 12, 2023 |
| Intel Clie... | LAPQC71A                    | [c87bff1d43](https://linux-hardware.org/?probe=c87bff1d43) | Aug 11, 2023 |
| MSI           | Creator Z16 A11UET          | [7883e9a69d](https://linux-hardware.org/?probe=7883e9a69d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [c083cb5f2f](https://linux-hardware.org/?probe=c083cb5f2f) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| ASUSTek       | 1005PE                      | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| PC Special... | NH5xAx                      | [891b5ec398](https://linux-hardware.org/?probe=891b5ec398) | Aug 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [8b57037d50](https://linux-hardware.org/?probe=8b57037d50) | Aug 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [afa02e4c02](https://linux-hardware.org/?probe=afa02e4c02) | Aug 09, 2023 |
| Dell          | Latitude 5520               | [478f0a6a07](https://linux-hardware.org/?probe=478f0a6a07) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [a8fc44190a](https://linux-hardware.org/?probe=a8fc44190a) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [766e35e920](https://linux-hardware.org/?probe=766e35e920) | Aug 09, 2023 |
| Acer          | Ferrari One 200             | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| MSI           | Creator Z16 A11UET          | [ea05388cf5](https://linux-hardware.org/?probe=ea05388cf5) | Aug 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b73a01acaf](https://linux-hardware.org/?probe=b73a01acaf) | Aug 07, 2023 |
| SGIN          | laptop                      | [d80389ea87](https://linux-hardware.org/?probe=d80389ea87) | Aug 07, 2023 |
| HP            | 255 G3                      | [d4e6fedb82](https://linux-hardware.org/?probe=d4e6fedb82) | Aug 07, 2023 |
| HP            | 255 G3                      | [0861b2330b](https://linux-hardware.org/?probe=0861b2330b) | Aug 07, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [77840c201a](https://linux-hardware.org/?probe=77840c201a) | Aug 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [804851c490](https://linux-hardware.org/?probe=804851c490) | Aug 07, 2023 |
| Acer          | Aspire V5-121               | [4b8b0f132d](https://linux-hardware.org/?probe=4b8b0f132d) | Aug 07, 2023 |
| Notebook      | NS5x_NS7xPU                 | [d71ac9524e](https://linux-hardware.org/?probe=d71ac9524e) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [56c7715a6d](https://linux-hardware.org/?probe=56c7715a6d) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [6a9e7cc3e2](https://linux-hardware.org/?probe=6a9e7cc3e2) | Aug 06, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [74c80ca51b](https://linux-hardware.org/?probe=74c80ca51b) | Aug 06, 2023 |
| ASUSTek       | R2H                         | [a2972dc454](https://linux-hardware.org/?probe=a2972dc454) | Aug 06, 2023 |
| ASUSTek       | R2H                         | [c32b5889aa](https://linux-hardware.org/?probe=c32b5889aa) | Aug 06, 2023 |
| Acer          | Aspire A315-59              | [fc1d6007aa](https://linux-hardware.org/?probe=fc1d6007aa) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | [deff4c99b6](https://linux-hardware.org/?probe=deff4c99b6) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1d6bf926f6](https://linux-hardware.org/?probe=1d6bf926f6) | Aug 05, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [e815f65a97](https://linux-hardware.org/?probe=e815f65a97) | Aug 05, 2023 |
| Sony          | VGN-NS11S_S                 | [8ad31bd20c](https://linux-hardware.org/?probe=8ad31bd20c) | Aug 05, 2023 |
| Chuwi         | GemiBook Pro                | [87ecdcb4bd](https://linux-hardware.org/?probe=87ecdcb4bd) | Aug 04, 2023 |
| Toshiba       | PORTEGE R700                | [f0df061bb2](https://linux-hardware.org/?probe=f0df061bb2) | Aug 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ee147b0313](https://linux-hardware.org/?probe=ee147b0313) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7f601fe313](https://linux-hardware.org/?probe=7f601fe313) | Aug 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | [f495796fe8](https://linux-hardware.org/?probe=f495796fe8) | Aug 03, 2023 |
| Acer          | Aspire M3-581G              | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Chuwi         | GemiBook Pro                | [eb2554dce9](https://linux-hardware.org/?probe=eb2554dce9) | Aug 02, 2023 |
| MSI           | Modern 15 A10M              | [bab451a11e](https://linux-hardware.org/?probe=bab451a11e) | Aug 02, 2023 |
| Sony          | VPCSB2L1R                   | [582f50ea25](https://linux-hardware.org/?probe=582f50ea25) | Aug 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [839698eb4c](https://linux-hardware.org/?probe=839698eb4c) | Aug 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8e7e80c44e](https://linux-hardware.org/?probe=8e7e80c44e) | Aug 01, 2023 |
| HP            | Laptop 15-db0xxx            | [2d7cbca56b](https://linux-hardware.org/?probe=2d7cbca56b) | Aug 01, 2023 |
| Chuwi         | GemiBook Pro                | [be8a59432a](https://linux-hardware.org/?probe=be8a59432a) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [2dcefa3349](https://linux-hardware.org/?probe=2dcefa3349) | Aug 01, 2023 |
| Valve         | Jupiter                     | [6ea9f908cb](https://linux-hardware.org/?probe=6ea9f908cb) | Aug 01, 2023 |
| Acer          | Aspire E5-573G              | [7e3e1a7ee9](https://linux-hardware.org/?probe=7e3e1a7ee9) | Jul 31, 2023 |
| SHENZHEN Y... | A8S PRO                     | [829a4178a5](https://linux-hardware.org/?probe=829a4178a5) | Jul 30, 2023 |
| Panasonic     | CFMX4-1                     | [925f36396d](https://linux-hardware.org/?probe=925f36396d) | Jul 30, 2023 |
| VANT          | MOOVE15_2023                | [6943d341c4](https://linux-hardware.org/?probe=6943d341c4) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [ce140941bc](https://linux-hardware.org/?probe=ce140941bc) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [19850c3ad1](https://linux-hardware.org/?probe=19850c3ad1) | Jul 29, 2023 |
| SHENZHEN Y... | A8S PRO                     | [08a6feda0e](https://linux-hardware.org/?probe=08a6feda0e) | Jul 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [7595472fb4](https://linux-hardware.org/?probe=7595472fb4) | Jul 28, 2023 |
| HP            | g14                         | [39d4ce09a1](https://linux-hardware.org/?probe=39d4ce09a1) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [61321e569d](https://linux-hardware.org/?probe=61321e569d) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4bd819d37b](https://linux-hardware.org/?probe=4bd819d37b) | Jul 28, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [0a1ef2aa5b](https://linux-hardware.org/?probe=0a1ef2aa5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d4914d5e5d](https://linux-hardware.org/?probe=d4914d5e5d) | Jul 27, 2023 |
| Samsung       | 700T                        | [a6c83540ad](https://linux-hardware.org/?probe=a6c83540ad) | Jul 27, 2023 |
| Acer          | Extensa 2510                | [b276a715eb](https://linux-hardware.org/?probe=b276a715eb) | Jul 27, 2023 |
| Acer          | Aspire V3-571G              | [88f60930be](https://linux-hardware.org/?probe=88f60930be) | Jul 26, 2023 |
| Samsung       | 700T                        | [881cb15d92](https://linux-hardware.org/?probe=881cb15d92) | Jul 25, 2023 |
| Acer          | Extensa 2530                | [6691e96edf](https://linux-hardware.org/?probe=6691e96edf) | Jul 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | [0e7e712860](https://linux-hardware.org/?probe=0e7e712860) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| Medion        | E15301                      | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| AMI           | Cherry Trail CR             | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| Packard Be... | EasyNote SL65               | [f66a4415f3](https://linux-hardware.org/?probe=f66a4415f3) | Jul 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe0c696d47](https://linux-hardware.org/?probe=fe0c696d47) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [b541d17031](https://linux-hardware.org/?probe=b541d17031) | Jul 21, 2023 |
| Dell          | XPS 15 7590                 | [714d6a38d3](https://linux-hardware.org/?probe=714d6a38d3) | Jul 20, 2023 |
| Dell          | XPS 15 7590                 | [f7edcc8364](https://linux-hardware.org/?probe=f7edcc8364) | Jul 20, 2023 |
| Lenovo        | Z50-70 20354                | [f92f9065bc](https://linux-hardware.org/?probe=f92f9065bc) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ec673415b4](https://linux-hardware.org/?probe=ec673415b4) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| Apple         | MacBookPro16,1              | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [dc76c90236](https://linux-hardware.org/?probe=dc76c90236) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [fdbbd2b641](https://linux-hardware.org/?probe=fdbbd2b641) | Jul 18, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b0c8aaef19](https://linux-hardware.org/?probe=b0c8aaef19) | Jul 16, 2023 |
| HP            | Laptop 15s-fq1xxx           | [10e24627b0](https://linux-hardware.org/?probe=10e24627b0) | Jul 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [5e43c9d869](https://linux-hardware.org/?probe=5e43c9d869) | Jul 15, 2023 |
| HP            | Laptop 15-bw0xx             | [56448b6dd8](https://linux-hardware.org/?probe=56448b6dd8) | Jul 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [bcf8e9f2c3](https://linux-hardware.org/?probe=bcf8e9f2c3) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f1bbc61bb6](https://linux-hardware.org/?probe=f1bbc61bb6) | Jul 14, 2023 |
| Dell          | XPS 15 7590                 | [28b21d099f](https://linux-hardware.org/?probe=28b21d099f) | Jul 14, 2023 |
| Acer          | TravelMate P246-MG          | [62348fa6ed](https://linux-hardware.org/?probe=62348fa6ed) | Jul 13, 2023 |
| Acer          | Aspire 5749                 | [fc6d20a364](https://linux-hardware.org/?probe=fc6d20a364) | Jul 13, 2023 |
| Chuwi         | GemiBook Pro                | [f73994358d](https://linux-hardware.org/?probe=f73994358d) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [d7c5b64bcb](https://linux-hardware.org/?probe=d7c5b64bcb) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | [e40c69408d](https://linux-hardware.org/?probe=e40c69408d) | Jul 11, 2023 |
| Dell          | Latitude 7275               | [0647894f7f](https://linux-hardware.org/?probe=0647894f7f) | Jul 11, 2023 |
| ASUSTek       | X555LAB                     | [464293fd0e](https://linux-hardware.org/?probe=464293fd0e) | Jul 11, 2023 |
| Clevo         | M550SE/M660SE               | [65697a4412](https://linux-hardware.org/?probe=65697a4412) | Jul 10, 2023 |
| Acer          | Extensa 5635Z               | [4967fbddb9](https://linux-hardware.org/?probe=4967fbddb9) | Jul 10, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [4ee2490bde](https://linux-hardware.org/?probe=4ee2490bde) | Jul 10, 2023 |
| Dell          | Latitude E5420              | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Notebook      | V1x0PNPx                    | [5a37402681](https://linux-hardware.org/?probe=5a37402681) | Jul 09, 2023 |
| Apple         | MacBookPro14,1              | [62bbadc762](https://linux-hardware.org/?probe=62bbadc762) | Jul 08, 2023 |
| Valve         | Jupiter                     | [7fc70add85](https://linux-hardware.org/?probe=7fc70add85) | Jul 08, 2023 |
| Acer          | Nitro AN515-46              | [010208e38d](https://linux-hardware.org/?probe=010208e38d) | Jul 08, 2023 |
| Valve         | Jupiter                     | [fd3d1bc540](https://linux-hardware.org/?probe=fd3d1bc540) | Jul 08, 2023 |
| Apple         | MacBookPro12,1              | [8877b51b89](https://linux-hardware.org/?probe=8877b51b89) | Jul 08, 2023 |
| Lenovo        | G580 2189                   | [a783ca495d](https://linux-hardware.org/?probe=a783ca495d) | Jul 06, 2023 |
| Acer          | Aspire 5749                 | [c4bea06a7d](https://linux-hardware.org/?probe=c4bea06a7d) | Jul 06, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [f603fed65f](https://linux-hardware.org/?probe=f603fed65f) | Jul 05, 2023 |
| Apple         | MacBookPro8,1               | [d25474786c](https://linux-hardware.org/?probe=d25474786c) | Jul 05, 2023 |
| Acer          | TravelMate P246-MG          | [e1e4548a49](https://linux-hardware.org/?probe=e1e4548a49) | Jul 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [8121ccc8a9](https://linux-hardware.org/?probe=8121ccc8a9) | Jul 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [656b411052](https://linux-hardware.org/?probe=656b411052) | Jul 05, 2023 |
| Medion        | X782X                       | [7369e18cc2](https://linux-hardware.org/?probe=7369e18cc2) | Jul 05, 2023 |
| HP            | Pavilion dv5                | [8064b5c083](https://linux-hardware.org/?probe=8064b5c083) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [54a88e79d1](https://linux-hardware.org/?probe=54a88e79d1) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c3098317a7](https://linux-hardware.org/?probe=c3098317a7) | Jul 04, 2023 |
| Lenovo        | G580 2189                   | [4c68104591](https://linux-hardware.org/?probe=4c68104591) | Jul 03, 2023 |
| Dell          | Latitude 5520               | [acb3fdea1b](https://linux-hardware.org/?probe=acb3fdea1b) | Jul 03, 2023 |
| Dell          | Latitude 5520               | [4bbef448c9](https://linux-hardware.org/?probe=4bbef448c9) | Jul 03, 2023 |
| HP            | ENVY m6                     | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [5daabbcd55](https://linux-hardware.org/?probe=5daabbcd55) | Jul 02, 2023 |
| Valve         | Jupiter                     | [7863106765](https://linux-hardware.org/?probe=7863106765) | Jul 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1eb1ecf3a9](https://linux-hardware.org/?probe=1eb1ecf3a9) | Jul 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [f78c4a1930](https://linux-hardware.org/?probe=f78c4a1930) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [27c53e1152](https://linux-hardware.org/?probe=27c53e1152) | Jul 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c1051d3ef0](https://linux-hardware.org/?probe=c1051d3ef0) | Jul 01, 2023 |
| Apple         | MacBookAir9,1               | [d5e55f9e7d](https://linux-hardware.org/?probe=d5e55f9e7d) | Jul 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [546fe2b3ab](https://linux-hardware.org/?probe=546fe2b3ab) | Jul 01, 2023 |
| Apple         | MacBookAir9,1               | [bd5c030739](https://linux-hardware.org/?probe=bd5c030739) | Jun 30, 2023 |
| Apple         | MacBookAir9,1               | [ce486a5063](https://linux-hardware.org/?probe=ce486a5063) | Jun 30, 2023 |
| MSI           | Modern 14 B5M               | [cb0eb574da](https://linux-hardware.org/?probe=cb0eb574da) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [1bb728e7dd](https://linux-hardware.org/?probe=1bb728e7dd) | Jun 29, 2023 |
| ASUSTek       | X541UAK                     | [83d0d28a2a](https://linux-hardware.org/?probe=83d0d28a2a) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [d1ade76136](https://linux-hardware.org/?probe=d1ade76136) | Jun 29, 2023 |
| Chuwi         | GemiBook                    | [90f0de1460](https://linux-hardware.org/?probe=90f0de1460) | Jun 28, 2023 |
| Acer          | Nitro AN515-54              | [b30ff15571](https://linux-hardware.org/?probe=b30ff15571) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [5922b4d31f](https://linux-hardware.org/?probe=5922b4d31f) | Jun 27, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| MSI           | Prestige 14H B12UCX         | [abf425c8d7](https://linux-hardware.org/?probe=abf425c8d7) | Jun 26, 2023 |
| Acer          | TravelMate 6493             | [490906b996](https://linux-hardware.org/?probe=490906b996) | Jun 25, 2023 |
| Dell          | Inspiron MM061              | [8152698df7](https://linux-hardware.org/?probe=8152698df7) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [f14b9f6ce5](https://linux-hardware.org/?probe=f14b9f6ce5) | Jun 25, 2023 |
| HUAWEI        | HKD-WXX                     | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | Compaq 610                  | [f312ec5ede](https://linux-hardware.org/?probe=f312ec5ede) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [6c3a0a7fe0](https://linux-hardware.org/?probe=6c3a0a7fe0) | Jun 23, 2023 |
| Dell          | XPS 9320                    | [2dcfa6718b](https://linux-hardware.org/?probe=2dcfa6718b) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [69dfee1765](https://linux-hardware.org/?probe=69dfee1765) | Jun 22, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| HP            | ENVY m6                     | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| win elemen... | MoreFine S500+              | [32b221a438](https://linux-hardware.org/?probe=32b221a438) | Jun 20, 2023 |
| Dell          | Latitude 7430               | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| Samsung       | RF510/RF410/RF710           | [6131e6746c](https://linux-hardware.org/?probe=6131e6746c) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2b32ca2d11](https://linux-hardware.org/?probe=2b32ca2d11) | Jun 18, 2023 |
| Toshiba       | NB510                       | [a66bda9742](https://linux-hardware.org/?probe=a66bda9742) | Jun 18, 2023 |
| HP            | Pavilion Notebook           | [5d417b3d76](https://linux-hardware.org/?probe=5d417b3d76) | Jun 18, 2023 |
| Samsung       | RV415/RV515/E3415           | [b17c80df83](https://linux-hardware.org/?probe=b17c80df83) | Jun 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| MSI           | Modern 14 B5M               | [21bd3b8234](https://linux-hardware.org/?probe=21bd3b8234) | Jun 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [3ea85763dc](https://linux-hardware.org/?probe=3ea85763dc) | Jun 16, 2023 |
| HP            | G62                         | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [2c6d49788f](https://linux-hardware.org/?probe=2c6d49788f) | Jun 16, 2023 |
| Valve         | Jupiter                     | [28dc5a83fe](https://linux-hardware.org/?probe=28dc5a83fe) | Jun 16, 2023 |
| Beelink       | Gemini X                    | [f95615a561](https://linux-hardware.org/?probe=f95615a561) | Jun 15, 2023 |
| Beelink       | Gemini X                    | [3f69d07a3e](https://linux-hardware.org/?probe=3f69d07a3e) | Jun 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [b9eac1e0b6](https://linux-hardware.org/?probe=b9eac1e0b6) | Jun 15, 2023 |
| HP            | Notebook                    | [dc40bd89f8](https://linux-hardware.org/?probe=dc40bd89f8) | Jun 15, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [542a1217bd](https://linux-hardware.org/?probe=542a1217bd) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [0b717c2785](https://linux-hardware.org/?probe=0b717c2785) | Jun 13, 2023 |
| HP            | ENVY m6                     | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | Stealth 15M B12UE           | [aabb8192ee](https://linux-hardware.org/?probe=aabb8192ee) | Jun 12, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [7b48584062](https://linux-hardware.org/?probe=7b48584062) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [e6079c9659](https://linux-hardware.org/?probe=e6079c9659) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [5a7c331645](https://linux-hardware.org/?probe=5a7c331645) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | G580 2189                   | [eac7ae2f7a](https://linux-hardware.org/?probe=eac7ae2f7a) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [0d419f2c9d](https://linux-hardware.org/?probe=0d419f2c9d) | Jun 11, 2023 |
| Valve         | Jupiter                     | [c7e458735d](https://linux-hardware.org/?probe=c7e458735d) | Jun 11, 2023 |
| Valve         | Jupiter                     | [3e31827529](https://linux-hardware.org/?probe=3e31827529) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [afc5d143fe](https://linux-hardware.org/?probe=afc5d143fe) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| Lenovo        | ThinkPad T450 20BU000BIX    | [d82c175e3e](https://linux-hardware.org/?probe=d82c175e3e) | Jun 10, 2023 |
| Beelink       | Gemini X                    | [adcb5e774d](https://linux-hardware.org/?probe=adcb5e774d) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| Dell          | Latitude E5500              | [41ad12c465](https://linux-hardware.org/?probe=41ad12c465) | Jun 10, 2023 |
| Apple         | MacBookPro5,5               | [1b3630b25a](https://linux-hardware.org/?probe=1b3630b25a) | Jun 10, 2023 |
| Apple         | MacBookPro11,4              | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| MSI           | GE66 Raider 10UE            | [38a5122d9c](https://linux-hardware.org/?probe=38a5122d9c) | Jun 08, 2023 |
| Micro Comp... | NUCXI7                      | [3b930f4e22](https://linux-hardware.org/?probe=3b930f4e22) | Jun 08, 2023 |
| Beelink       | Gemini X                    | [49aca69972](https://linux-hardware.org/?probe=49aca69972) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | [ff2ebbb0ae](https://linux-hardware.org/?probe=ff2ebbb0ae) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [265c19be27](https://linux-hardware.org/?probe=265c19be27) | Jun 07, 2023 |
| MSI           | GT72 2QE                    | [211494a051](https://linux-hardware.org/?probe=211494a051) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | [acae4ee06e](https://linux-hardware.org/?probe=acae4ee06e) | Jun 06, 2023 |
| MSI           | Modern 14 C12M              | [a5d1a0e656](https://linux-hardware.org/?probe=a5d1a0e656) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| Acer          | Aspire E1-572P              | [a90316cac7](https://linux-hardware.org/?probe=a90316cac7) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [04fdc3c3b8](https://linux-hardware.org/?probe=04fdc3c3b8) | Jun 03, 2023 |
| Valve         | Jupiter                     | [8c33873318](https://linux-hardware.org/?probe=8c33873318) | Jun 03, 2023 |
| MSI           | Prestige 16 A12UD           | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| Notebook      | NL40_50CU                   | [47b838db36](https://linux-hardware.org/?probe=47b838db36) | Jun 02, 2023 |
| Notebook      | N141CU                      | [4af09bd0c3](https://linux-hardware.org/?probe=4af09bd0c3) | Jun 02, 2023 |
| Valve         | Jupiter                     | [762287e555](https://linux-hardware.org/?probe=762287e555) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c9e1edde25](https://linux-hardware.org/?probe=c9e1edde25) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Lenovo        | ThinkPad T530 2392AHG       | [05c41c8464](https://linux-hardware.org/?probe=05c41c8464) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| Lenovo        | G580 2189                   | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| MSI           | Modern 14 B4MW              | [2c4acbbad3](https://linux-hardware.org/?probe=2c4acbbad3) | May 31, 2023 |
| Acer          | Nitro AN515-54              | [7c031081c5](https://linux-hardware.org/?probe=7c031081c5) | May 31, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [5e96e1c54e](https://linux-hardware.org/?probe=5e96e1c54e) | May 31, 2023 |
| Chuwi         | HeroBook Air                | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e9830d0123](https://linux-hardware.org/?probe=e9830d0123) | May 29, 2023 |
| Lenovo        | V145-15AST 81MT             | [bf9c082ee0](https://linux-hardware.org/?probe=bf9c082ee0) | May 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [dc2b5e538f](https://linux-hardware.org/?probe=dc2b5e538f) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | [9605e313ac](https://linux-hardware.org/?probe=9605e313ac) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | [0a8ae92c13](https://linux-hardware.org/?probe=0a8ae92c13) | May 27, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [f7f07e78d5](https://linux-hardware.org/?probe=f7f07e78d5) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [89b7c17d00](https://linux-hardware.org/?probe=89b7c17d00) | May 26, 2023 |
| MSI           | Alpha 15 A3DDK              | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Acer          | TravelMate 5720             | [1066a7a5c5](https://linux-hardware.org/?probe=1066a7a5c5) | May 25, 2023 |
| HP            | Laptop 15s-fq4xxx           | [810c2ac411](https://linux-hardware.org/?probe=810c2ac411) | May 24, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [428a152134](https://linux-hardware.org/?probe=428a152134) | May 23, 2023 |
| Notebook      | W54_55SU1,SUW               | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [77f092da32](https://linux-hardware.org/?probe=77f092da32) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| Acer          | Extensa 5635Z               | [dcff2c30c6](https://linux-hardware.org/?probe=dcff2c30c6) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | [895bca272b](https://linux-hardware.org/?probe=895bca272b) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [21f52b0bc9](https://linux-hardware.org/?probe=21f52b0bc9) | May 22, 2023 |
| MSI           | Stealth 15M B12UE           | [4051f4b27d](https://linux-hardware.org/?probe=4051f4b27d) | May 22, 2023 |
| Dell          | Inspiron 5770               | [4c16a00ef6](https://linux-hardware.org/?probe=4c16a00ef6) | May 22, 2023 |
| Acer          | Aspire E5-575G              | [d27d5d547e](https://linux-hardware.org/?probe=d27d5d547e) | May 21, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [a6b4b230da](https://linux-hardware.org/?probe=a6b4b230da) | May 21, 2023 |
| Lenovo        | G580 2189                   | [8e7dbefb51](https://linux-hardware.org/?probe=8e7dbefb51) | May 21, 2023 |
| Apple         | MacBookPro8,1               | [43c5b0db78](https://linux-hardware.org/?probe=43c5b0db78) | May 20, 2023 |
| Apple         | MacBookAir7,2               | [7687732509](https://linux-hardware.org/?probe=7687732509) | May 20, 2023 |
| HP            | 350 G1                      | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [e464ddd1b6](https://linux-hardware.org/?probe=e464ddd1b6) | May 20, 2023 |
| Chuwi         | GemiBook Pro                | [a8553d6ad6](https://linux-hardware.org/?probe=a8553d6ad6) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [7f2ca00e36](https://linux-hardware.org/?probe=7f2ca00e36) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [161776168b](https://linux-hardware.org/?probe=161776168b) | May 18, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d4fc64a451](https://linux-hardware.org/?probe=d4fc64a451) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| ASUSTek       | TP300LA                     | [e2e6bc0209](https://linux-hardware.org/?probe=e2e6bc0209) | May 17, 2023 |
| MSI           | Stealth 15M B12UE           | [8517139acb](https://linux-hardware.org/?probe=8517139acb) | May 16, 2023 |
| AZW           | GT-R                        | [e156c5b105](https://linux-hardware.org/?probe=e156c5b105) | May 16, 2023 |
| HP            | 630                         | [3527caae6f](https://linux-hardware.org/?probe=3527caae6f) | May 16, 2023 |
| HP            | 630                         | [f34f960671](https://linux-hardware.org/?probe=f34f960671) | May 16, 2023 |
| ASUSTek       | X541UJ                      | [923f447e90](https://linux-hardware.org/?probe=923f447e90) | May 15, 2023 |
| Acer          | TravelMate P215-41-G2       | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| HP            | Presario CQ61               | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | [d697ec6804](https://linux-hardware.org/?probe=d697ec6804) | May 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [8d819952c9](https://linux-hardware.org/?probe=8d819952c9) | May 14, 2023 |
| HP            | 630                         | [40e895a75a](https://linux-hardware.org/?probe=40e895a75a) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [dc1c717240](https://linux-hardware.org/?probe=dc1c717240) | May 13, 2023 |
| ASUSTek       | X551CA                      | [df0583682c](https://linux-hardware.org/?probe=df0583682c) | May 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [9dda4f6b83](https://linux-hardware.org/?probe=9dda4f6b83) | May 13, 2023 |
| Valve         | Jupiter                     | [02275a9849](https://linux-hardware.org/?probe=02275a9849) | May 13, 2023 |
| Apple         | MacBookPro11,4              | [576d66cba7](https://linux-hardware.org/?probe=576d66cba7) | May 12, 2023 |
| HP            | Pavilion Sleekbook 15       | [db2c740451](https://linux-hardware.org/?probe=db2c740451) | May 12, 2023 |
| Valve         | Jupiter                     | [4b2b4bf799](https://linux-hardware.org/?probe=4b2b4bf799) | May 12, 2023 |
| Valve         | Jupiter                     | [e89eb08b8d](https://linux-hardware.org/?probe=e89eb08b8d) | May 11, 2023 |
| Acer          | Aspire 5253G                | [c5cae82cf1](https://linux-hardware.org/?probe=c5cae82cf1) | May 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [30d9e5ca7d](https://linux-hardware.org/?probe=30d9e5ca7d) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| Dell          | XPS 15 9560                 | [62abfc3d83](https://linux-hardware.org/?probe=62abfc3d83) | May 11, 2023 |
| Dell          | XPS 15 9560                 | [4c714fc6ea](https://linux-hardware.org/?probe=4c714fc6ea) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Toshiba       | TECRA M10                   | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| Samsung       | X420/X520                   | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [2e58ce6bd7](https://linux-hardware.org/?probe=2e58ce6bd7) | May 10, 2023 |
| HP            | Compaq Mini CQ10-500        | [4b9087625d](https://linux-hardware.org/?probe=4b9087625d) | May 09, 2023 |
| HP            | 630                         | [69a6753dab](https://linux-hardware.org/?probe=69a6753dab) | May 09, 2023 |
| HP            | 630                         | [d729f66fa2](https://linux-hardware.org/?probe=d729f66fa2) | May 09, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| eMachines     | eME728                      | [031e24359e](https://linux-hardware.org/?probe=031e24359e) | May 06, 2023 |
| HP            | 630                         | [20d6860e43](https://linux-hardware.org/?probe=20d6860e43) | May 05, 2023 |
| HP            | 630                         | [57d5ffbec9](https://linux-hardware.org/?probe=57d5ffbec9) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Acer          | Nitro AN515-55              | [6264cfc1e6](https://linux-hardware.org/?probe=6264cfc1e6) | May 04, 2023 |
| Gigabyte      | G5 KD                       | [15f1eb707f](https://linux-hardware.org/?probe=15f1eb707f) | May 04, 2023 |
| MSI           | Stealth 15M B12UE           | [9e3dbb15ed](https://linux-hardware.org/?probe=9e3dbb15ed) | May 04, 2023 |
| Acer          | Aspire 5732Z                | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
| Notebook      | W54_55SU1,SUW               | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [2509256cea](https://linux-hardware.org/?probe=2509256cea) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [3e7b117db0](https://linux-hardware.org/?probe=3e7b117db0) | May 03, 2023 |
| Acer          | TravelMate 5720             | [ad56dc6f51](https://linux-hardware.org/?probe=ad56dc6f51) | May 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [f2c18c96df](https://linux-hardware.org/?probe=f2c18c96df) | May 02, 2023 |
| Lenovo        | V15-ADA 82C7                | [b11670d60d](https://linux-hardware.org/?probe=b11670d60d) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Toshiba       | Satellite L50-B             | [fb815bb11c](https://linux-hardware.org/?probe=fb815bb11c) | May 02, 2023 |
| Toshiba       | Satellite L755              | [20fdcbe744](https://linux-hardware.org/?probe=20fdcbe744) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [000c0450b9](https://linux-hardware.org/?probe=000c0450b9) | May 02, 2023 |
| HP            | 240 G6 Notebook PC          | [3ca97c367a](https://linux-hardware.org/?probe=3ca97c367a) | May 01, 2023 |
| Acer          | Aspire A315-21              | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| Dell          | Inspiron 7548               | [15fe439a9a](https://linux-hardware.org/?probe=15fe439a9a) | Apr 30, 2023 |
| ASUSTek       | X555QG                      | [5263b174b2](https://linux-hardware.org/?probe=5263b174b2) | Apr 30, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| MSI           | GF63 Thin 9SC               | [f6a250b3e2](https://linux-hardware.org/?probe=f6a250b3e2) | Apr 29, 2023 |
| MSI           | Modern 14 A10M              | [22ad1f6bfb](https://linux-hardware.org/?probe=22ad1f6bfb) | Apr 29, 2023 |
| Chuwi         | HeroBook Air                | [123f6df9f8](https://linux-hardware.org/?probe=123f6df9f8) | Apr 29, 2023 |
| Sony          | VPCZ13M9E                   | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| ASUSTek       | X555QG                      | [b33f41d3c3](https://linux-hardware.org/?probe=b33f41d3c3) | Apr 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [61151daf36](https://linux-hardware.org/?probe=61151daf36) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [a72fdebd89](https://linux-hardware.org/?probe=a72fdebd89) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | [ca70475f8a](https://linux-hardware.org/?probe=ca70475f8a) | Apr 28, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [beca0f768b](https://linux-hardware.org/?probe=beca0f768b) | Apr 27, 2023 |
| Gigabyte      | G5 GD                       | [d09d6fb712](https://linux-hardware.org/?probe=d09d6fb712) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [0e403fcd17](https://linux-hardware.org/?probe=0e403fcd17) | Apr 27, 2023 |
| Valve         | Jupiter                     | [72f64e795a](https://linux-hardware.org/?probe=72f64e795a) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [018ade4782](https://linux-hardware.org/?probe=018ade4782) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [de95ac0857](https://linux-hardware.org/?probe=de95ac0857) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [07906a30e3](https://linux-hardware.org/?probe=07906a30e3) | Apr 26, 2023 |
| MSI           | Stealth 15M B12UE           | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [8a88263cea](https://linux-hardware.org/?probe=8a88263cea) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [2f7f2efd4f](https://linux-hardware.org/?probe=2f7f2efd4f) | Apr 26, 2023 |
| MSI           | Modern 14 A10M              | [dc3595e3cc](https://linux-hardware.org/?probe=dc3595e3cc) | Apr 25, 2023 |
| HP            | Compaq 15                   | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| INSYS         | PT1-140C                    | [902536abce](https://linux-hardware.org/?probe=902536abce) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [b1c3492700](https://linux-hardware.org/?probe=b1c3492700) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [db8e950d12](https://linux-hardware.org/?probe=db8e950d12) | Apr 24, 2023 |
| Acer          | Aspire E1-571G              | [0e2671ee2e](https://linux-hardware.org/?probe=0e2671ee2e) | Apr 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e682d7b9dd](https://linux-hardware.org/?probe=e682d7b9dd) | Apr 22, 2023 |
| HP            | Notebook                    | [1d975dfc4f](https://linux-hardware.org/?probe=1d975dfc4f) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [694966dbd7](https://linux-hardware.org/?probe=694966dbd7) | Apr 22, 2023 |
| Toshiba       | Satellite L50-C             | [11f0485b1a](https://linux-hardware.org/?probe=11f0485b1a) | Apr 21, 2023 |
| Toshiba       | Satellite L50-C             | [969bbe5df0](https://linux-hardware.org/?probe=969bbe5df0) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| MSI           | Stealth 15M B12UE           | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| Lenovo        | ThinkPad T420 4180FP9       | [655c151267](https://linux-hardware.org/?probe=655c151267) | Apr 20, 2023 |
| Acer          | TravelMate B115-M           | [178dbe3693](https://linux-hardware.org/?probe=178dbe3693) | Apr 19, 2023 |
| MSI           | Bravo 15 B5DD               | [433c482314](https://linux-hardware.org/?probe=433c482314) | Apr 19, 2023 |
| Acer          | TravelMate B115-M           | [973070ca0e](https://linux-hardware.org/?probe=973070ca0e) | Apr 19, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Toshiba       | Satellite L500              | [0896195ea4](https://linux-hardware.org/?probe=0896195ea4) | Apr 18, 2023 |
| Toshiba       | Satellite L500              | [7105145a87](https://linux-hardware.org/?probe=7105145a87) | Apr 18, 2023 |
| MSI           | Prestige 15 A12UC           | [0f4c1e1ac3](https://linux-hardware.org/?probe=0f4c1e1ac3) | Apr 18, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [e9278fb49b](https://linux-hardware.org/?probe=e9278fb49b) | Apr 18, 2023 |
| MSI           | PS42 Modern 8RC             | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [879e47fc04](https://linux-hardware.org/?probe=879e47fc04) | Apr 17, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [8b6a2af9ce](https://linux-hardware.org/?probe=8b6a2af9ce) | Apr 16, 2023 |
| Medion        | E15415                      | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| HUAWEI        | MRC-WX0                     | [5b446c43f3](https://linux-hardware.org/?probe=5b446c43f3) | Apr 15, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| Dell          | Inspiron 5759               | [f3bbb04052](https://linux-hardware.org/?probe=f3bbb04052) | Apr 15, 2023 |
| Dell          | Precision 5560              | [b6d20ef4bf](https://linux-hardware.org/?probe=b6d20ef4bf) | Apr 14, 2023 |
| Dell          | Precision 5560              | [b76f840bd9](https://linux-hardware.org/?probe=b76f840bd9) | Apr 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| Lenovo        | ThinkPad T410 2537NY6       | [977014ae11](https://linux-hardware.org/?probe=977014ae11) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | [a9b7cf3c18](https://linux-hardware.org/?probe=a9b7cf3c18) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | [b2259951b5](https://linux-hardware.org/?probe=b2259951b5) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [af4ccb91b1](https://linux-hardware.org/?probe=af4ccb91b1) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | [d914c2a179](https://linux-hardware.org/?probe=d914c2a179) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | [5b861c968e](https://linux-hardware.org/?probe=5b861c968e) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| Valve         | Jupiter                     | [8fdb71aed1](https://linux-hardware.org/?probe=8fdb71aed1) | Apr 12, 2023 |
| Dell          | XPS 15 9520                 | [5b01d0eda1](https://linux-hardware.org/?probe=5b01d0eda1) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [27688332ee](https://linux-hardware.org/?probe=27688332ee) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Acer          | Aspire E1-571G              | [45a3503764](https://linux-hardware.org/?probe=45a3503764) | Apr 11, 2023 |
| HP            | Laptop 15-bw0xx             | [0cef536369](https://linux-hardware.org/?probe=0cef536369) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ac983c99b9](https://linux-hardware.org/?probe=ac983c99b9) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a2dcc97485](https://linux-hardware.org/?probe=a2dcc97485) | Apr 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | [eab5adc4e6](https://linux-hardware.org/?probe=eab5adc4e6) | Apr 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [7033d674d8](https://linux-hardware.org/?probe=7033d674d8) | Apr 09, 2023 |
| HP            | Pavilion dv6                | [10eeff8916](https://linux-hardware.org/?probe=10eeff8916) | Apr 08, 2023 |
| ASUSTek       | X540LA                      | [38299d8248](https://linux-hardware.org/?probe=38299d8248) | Apr 08, 2023 |
| Dell          | Latitude E5550              | [b0e2c2e0d5](https://linux-hardware.org/?probe=b0e2c2e0d5) | Apr 07, 2023 |
| Gigabyte      | G5 GD                       | [d492c2eca8](https://linux-hardware.org/?probe=d492c2eca8) | Apr 06, 2023 |
| Dell          | Latitude E7250              | [e5fe0c7962](https://linux-hardware.org/?probe=e5fe0c7962) | Apr 06, 2023 |
| HP            | Compaq Presario CQ70        | [11cd73fbce](https://linux-hardware.org/?probe=11cd73fbce) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | [705d5f2396](https://linux-hardware.org/?probe=705d5f2396) | Apr 05, 2023 |
| Dell          | Latitude E4200              | [6dae8e5ff4](https://linux-hardware.org/?probe=6dae8e5ff4) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [80bd0aed09](https://linux-hardware.org/?probe=80bd0aed09) | Apr 05, 2023 |
| ASUSTek       | X58C                        | [ff580ffa57](https://linux-hardware.org/?probe=ff580ffa57) | Apr 05, 2023 |
| ASUSTek       | X58C                        | [ae9888c407](https://linux-hardware.org/?probe=ae9888c407) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d006e94e8f](https://linux-hardware.org/?probe=d006e94e8f) | Apr 04, 2023 |
| Valve         | Jupiter                     | [70eb6c0ec1](https://linux-hardware.org/?probe=70eb6c0ec1) | Apr 04, 2023 |
| Timi          | RedmiBook 16                | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [89d4ef9333](https://linux-hardware.org/?probe=89d4ef9333) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | [f7f0d77f00](https://linux-hardware.org/?probe=f7f0d77f00) | Apr 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Google        | Snappy                      | [6ca49159d2](https://linux-hardware.org/?probe=6ca49159d2) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | [41b51a471d](https://linux-hardware.org/?probe=41b51a471d) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | [fc4116204b](https://linux-hardware.org/?probe=fc4116204b) | Apr 01, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [6ab0a0226d](https://linux-hardware.org/?probe=6ab0a0226d) | Apr 01, 2023 |
| Intel         | Kabylake Platform           | [2b0fd79264](https://linux-hardware.org/?probe=2b0fd79264) | Mar 31, 2023 |
| Acer          | Aspire E5-571               | [45887eb5f3](https://linux-hardware.org/?probe=45887eb5f3) | Mar 31, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [59b2b4e152](https://linux-hardware.org/?probe=59b2b4e152) | Mar 31, 2023 |
| MSI           | Modern 15 A5M               | [2a00bed043](https://linux-hardware.org/?probe=2a00bed043) | Mar 31, 2023 |
| ASUSTek       | X551MA                      | [5ea823d079](https://linux-hardware.org/?probe=5ea823d079) | Mar 31, 2023 |
| Apple         | MacBookPro9,2               | [8c60cf0ec1](https://linux-hardware.org/?probe=8c60cf0ec1) | Mar 31, 2023 |
| Dell          | G15 5515                    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [faa3d2b7ad](https://linux-hardware.org/?probe=faa3d2b7ad) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| ASUSTek       | K53SD                       | [81710aaa51](https://linux-hardware.org/?probe=81710aaa51) | Mar 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [3836173aad](https://linux-hardware.org/?probe=3836173aad) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [46a8636dfd](https://linux-hardware.org/?probe=46a8636dfd) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| ASUSTek       | N550JX                      | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| TEKNOSERVI... | NJ5x_NJ7xLU                 | [2a0feae3f9](https://linux-hardware.org/?probe=2a0feae3f9) | Mar 28, 2023 |
| Notebook      | L140CU                      | [98b71e9790](https://linux-hardware.org/?probe=98b71e9790) | Mar 28, 2023 |
| Dell          | Precision 5540              | [f9e20de07f](https://linux-hardware.org/?probe=f9e20de07f) | Mar 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | [574bb4272c](https://linux-hardware.org/?probe=574bb4272c) | Mar 27, 2023 |
| Dell          | Precision 3571              | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [bddc9116d1](https://linux-hardware.org/?probe=bddc9116d1) | Mar 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [6a8962feba](https://linux-hardware.org/?probe=6a8962feba) | Mar 27, 2023 |
| Samsung       | N150P/N210P/N220P           | [70d943698c](https://linux-hardware.org/?probe=70d943698c) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ca83615d40](https://linux-hardware.org/?probe=ca83615d40) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | [285462b197](https://linux-hardware.org/?probe=285462b197) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | [fc40632056](https://linux-hardware.org/?probe=fc40632056) | Mar 26, 2023 |
| Dell          | G15 5515                    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | [68017924d7](https://linux-hardware.org/?probe=68017924d7) | Mar 26, 2023 |
| HUAWEI        | BOD-WXX9                    | [bee83a6b50](https://linux-hardware.org/?probe=bee83a6b50) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [8a6705ba5a](https://linux-hardware.org/?probe=8a6705ba5a) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d1427e69b3](https://linux-hardware.org/?probe=d1427e69b3) | Mar 26, 2023 |
| Notebook      | NL40_50CU                   | [4870d52d1e](https://linux-hardware.org/?probe=4870d52d1e) | Mar 25, 2023 |
| Gigabyte      | AERO 15 XD                  | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [05b2003fc0](https://linux-hardware.org/?probe=05b2003fc0) | Mar 25, 2023 |
| MSI           | PE62 7RD                    | [de18d40d94](https://linux-hardware.org/?probe=de18d40d94) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| HP            | 255 G7 Notebook PC          | [2097578b64](https://linux-hardware.org/?probe=2097578b64) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [548c06032b](https://linux-hardware.org/?probe=548c06032b) | Mar 24, 2023 |
| ASUSTek       | K52Jr                       | [a88997ecfd](https://linux-hardware.org/?probe=a88997ecfd) | Mar 24, 2023 |
| Dell          | G15 5515                    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| HP            | 2000                        | [9820715e60](https://linux-hardware.org/?probe=9820715e60) | Mar 24, 2023 |
| ASUSTek       | GL752VW                     | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | [4054877ef0](https://linux-hardware.org/?probe=4054877ef0) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | [da37222f12](https://linux-hardware.org/?probe=da37222f12) | Mar 24, 2023 |
| HP            | 2000                        | [87ba6d3696](https://linux-hardware.org/?probe=87ba6d3696) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e4a3f70cbf](https://linux-hardware.org/?probe=e4a3f70cbf) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d55de052b1](https://linux-hardware.org/?probe=d55de052b1) | Mar 23, 2023 |
| Lenovo        | G500 20236                  | [8688a57db6](https://linux-hardware.org/?probe=8688a57db6) | Mar 22, 2023 |
| Packard Be... | EasyNote LJ75               | [1a3b095372](https://linux-hardware.org/?probe=1a3b095372) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| Dell          | G3 3579                     | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Acer          | Aspire ES1-512              | [901b9b1b6b](https://linux-hardware.org/?probe=901b9b1b6b) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| HP            | 250 G4                      | [46e0314fb1](https://linux-hardware.org/?probe=46e0314fb1) | Mar 20, 2023 |
| MSI           | Pulse GL66 12UEK            | [9790d0bb28](https://linux-hardware.org/?probe=9790d0bb28) | Mar 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [77b7fd07a4](https://linux-hardware.org/?probe=77b7fd07a4) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [5c0e12ebd0](https://linux-hardware.org/?probe=5c0e12ebd0) | Mar 19, 2023 |
| Acer          | Aspire E1-532               | [ed3693c1c8](https://linux-hardware.org/?probe=ed3693c1c8) | Mar 18, 2023 |
| Chuwi         | HeroBook Air                | [e9d0a5dd9a](https://linux-hardware.org/?probe=e9d0a5dd9a) | Mar 18, 2023 |
| Chuwi         | GemiBook Pro                | [7bd3a3e64c](https://linux-hardware.org/?probe=7bd3a3e64c) | Mar 18, 2023 |
| HP            | 250 G8 Notebook PC          | [aade64a567](https://linux-hardware.org/?probe=aade64a567) | Mar 18, 2023 |
| Chuwi         | HeroBook                    | [7a70fa6c57](https://linux-hardware.org/?probe=7a70fa6c57) | Mar 17, 2023 |
| MSI           | GF63 Thin 9SC               | [88dcbd2740](https://linux-hardware.org/?probe=88dcbd2740) | Mar 17, 2023 |
| Apple         | MacBook8,1                  | [a3ef4e5a56](https://linux-hardware.org/?probe=a3ef4e5a56) | Mar 16, 2023 |
| Valve         | Jupiter                     | [0a2038deed](https://linux-hardware.org/?probe=0a2038deed) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [428ea81050](https://linux-hardware.org/?probe=428ea81050) | Mar 15, 2023 |
| Acer          | Aspire E5-573G              | [a24986d87d](https://linux-hardware.org/?probe=a24986d87d) | Mar 15, 2023 |
| HP            | Mini 210-1000               | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| MSI           | Katana GF66 12UC            | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Intel         | powered classmate PC        | [891664a0ae](https://linux-hardware.org/?probe=891664a0ae) | Mar 14, 2023 |
| Dell          | Inspiron 14 5410            | [54ff309c3d](https://linux-hardware.org/?probe=54ff309c3d) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| Chuwi         | GemiBook Pro                | [f30cf91b1c](https://linux-hardware.org/?probe=f30cf91b1c) | Mar 13, 2023 |
| Valve         | Jupiter                     | [95598d1841](https://linux-hardware.org/?probe=95598d1841) | Mar 13, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | [a421f89675](https://linux-hardware.org/?probe=a421f89675) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | [4708653fb3](https://linux-hardware.org/?probe=4708653fb3) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | [1a37e14422](https://linux-hardware.org/?probe=1a37e14422) | Mar 11, 2023 |
| Toshiba       | Satellite Pro L300          | [7c5e811612](https://linux-hardware.org/?probe=7c5e811612) | Mar 11, 2023 |
| Valve         | Jupiter                     | [07f6e9ed10](https://linux-hardware.org/?probe=07f6e9ed10) | Mar 10, 2023 |
| Dynabook      | Satellite Pro C50-G         | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| MSI           | GL75 Leopard 10SEK          | [9fdc1bd5c4](https://linux-hardware.org/?probe=9fdc1bd5c4) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Dell          | Latitude E5420              | [9b346e0658](https://linux-hardware.org/?probe=9b346e0658) | Mar 10, 2023 |
| Acer          | Aspire 5750G                | [b4af1eb2cb](https://linux-hardware.org/?probe=b4af1eb2cb) | Mar 10, 2023 |
| Acer          | Aspire M3-581G              | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| Dell          | Latitude E6540              | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Chuwi         | GemiBook Pro                | [23a97367b7](https://linux-hardware.org/?probe=23a97367b7) | Mar 09, 2023 |
| Intel         | powered classmate PC        | [c25d03cf3f](https://linux-hardware.org/?probe=c25d03cf3f) | Mar 09, 2023 |
| Intel         | powered classmate PC        | [8c62787a5b](https://linux-hardware.org/?probe=8c62787a5b) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fd15fc475a](https://linux-hardware.org/?probe=fd15fc475a) | Mar 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [0e054a9861](https://linux-hardware.org/?probe=0e054a9861) | Mar 08, 2023 |
| HP            | Pavilion g6                 | [35f93de82d](https://linux-hardware.org/?probe=35f93de82d) | Mar 08, 2023 |
| ASUSTek       | K53SC                       | [bd182b6d80](https://linux-hardware.org/?probe=bd182b6d80) | Mar 08, 2023 |
| Sony          | SVF1521B1EW                 | [5b5a9dbc40](https://linux-hardware.org/?probe=5b5a9dbc40) | Mar 08, 2023 |
| Acer          | Aspire 5740                 | [37c0c0602c](https://linux-hardware.org/?probe=37c0c0602c) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| Notebook      | N2x0WU                      | [4948392f03](https://linux-hardware.org/?probe=4948392f03) | Mar 06, 2023 |
| Fujitsu Si... | STYLISTIC ST6012            | [0d9314f673](https://linux-hardware.org/?probe=0d9314f673) | Mar 06, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| Intel         | powered classmate PC        | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| Chuwi         | HeroBook Air                | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Lenovo        | ThinkPad E490 20N8002ASP    | [9b91ef4633](https://linux-hardware.org/?probe=9b91ef4633) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| Acer          | TravelMate 5720             | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3a2e77122d](https://linux-hardware.org/?probe=3a2e77122d) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Dell          | G5 5590                     | [75f2235434](https://linux-hardware.org/?probe=75f2235434) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| Apple         | MacBookPro6,2               | [3696f0b49e](https://linux-hardware.org/?probe=3696f0b49e) | Feb 27, 2023 |
| HP            | 250 G7 Notebook PC          | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Notebook                    | [06dba3c8b3](https://linux-hardware.org/?probe=06dba3c8b3) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [02608a8288](https://linux-hardware.org/?probe=02608a8288) | Feb 25, 2023 |
| HP            | EliteBook Folio 9470m       | [8cc1fdf5b4](https://linux-hardware.org/?probe=8cc1fdf5b4) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Acer          | AOD255                      | [f5f5ed9b36](https://linux-hardware.org/?probe=f5f5ed9b36) | Feb 24, 2023 |
| Acer          | Aspire S3                   | [9d0301c490](https://linux-hardware.org/?probe=9d0301c490) | Feb 24, 2023 |
| Valve         | Jupiter                     | [08585b6c97](https://linux-hardware.org/?probe=08585b6c97) | Feb 24, 2023 |
| Lenovo        | ThinkPad X201 3680U6V       | [abcf384939](https://linux-hardware.org/?probe=abcf384939) | Feb 23, 2023 |
| Acer          | AOD255                      | [b4ccf00506](https://linux-hardware.org/?probe=b4ccf00506) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| HP            | Compaq 6720s                | [48cbefb8f6](https://linux-hardware.org/?probe=48cbefb8f6) | Feb 23, 2023 |
| HP            | Compaq 6720s                | [0dac92bb9d](https://linux-hardware.org/?probe=0dac92bb9d) | Feb 23, 2023 |
| HP            | Pavilion 15                 | [48439104ea](https://linux-hardware.org/?probe=48439104ea) | Feb 23, 2023 |
| Gigabyte      | G5 KD                       | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| Sony          | SVF1521N6EW                 | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Acer          | Swift SF514-54T             | [ebbff689ba](https://linux-hardware.org/?probe=ebbff689ba) | Feb 22, 2023 |
| Acer          | TravelMate P256-MG          | [4dbdb229c5](https://linux-hardware.org/?probe=4dbdb229c5) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [50f5c21eeb](https://linux-hardware.org/?probe=50f5c21eeb) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Toshiba       | PORTEGE Z30-A               | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Unknown       | Unknown                     | [e48cf758d0](https://linux-hardware.org/?probe=e48cf758d0) | Feb 19, 2023 |
| Dell          | XPS M1530                   | [c2f2509941](https://linux-hardware.org/?probe=c2f2509941) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [84d8598da2](https://linux-hardware.org/?probe=84d8598da2) | Feb 18, 2023 |
| Sony          | VPCZ13M9E                   | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Chuwi         | GemiBook Pro                | [af76238a5c](https://linux-hardware.org/?probe=af76238a5c) | Feb 17, 2023 |
| Unknown       | Unknown                     | [8cdf723a7d](https://linux-hardware.org/?probe=8cdf723a7d) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| HP            | G61                         | [52bb3c7afb](https://linux-hardware.org/?probe=52bb3c7afb) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| ASUSTek       | GL553VD                     | [97f3fd27fa](https://linux-hardware.org/?probe=97f3fd27fa) | Feb 16, 2023 |
| Acer          | Aspire V3-372               | [bde68b3ed7](https://linux-hardware.org/?probe=bde68b3ed7) | Feb 16, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [abc91903be](https://linux-hardware.org/?probe=abc91903be) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| Lenovo        | ThinkPad T510 43147VG       | [16b032ccc3](https://linux-hardware.org/?probe=16b032ccc3) | Feb 16, 2023 |
| Acer          | Aspire ES1-512              | [a21a70af4c](https://linux-hardware.org/?probe=a21a70af4c) | Feb 15, 2023 |
| Unknown       | Unknown                     | [7fd524ac5b](https://linux-hardware.org/?probe=7fd524ac5b) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| Acer          | Extensa 5230                | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | [fcf87be002](https://linux-hardware.org/?probe=fcf87be002) | Feb 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [a4f13f23ce](https://linux-hardware.org/?probe=a4f13f23ce) | Feb 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [9368822d6a](https://linux-hardware.org/?probe=9368822d6a) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| Gigabyte      | RC14UD                      | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Acer          | Extensa 5220                | [87682be3fd](https://linux-hardware.org/?probe=87682be3fd) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b84a7339e](https://linux-hardware.org/?probe=9b84a7339e) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [20428fc0ed](https://linux-hardware.org/?probe=20428fc0ed) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Google        | Droid                       | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Acer          | Extensa 5230                | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [96dfdd671c](https://linux-hardware.org/?probe=96dfdd671c) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| MSI           | Prestige 15 A12UD           | [9688180ef7](https://linux-hardware.org/?probe=9688180ef7) | Feb 11, 2023 |
| Dell          | Latitude 5290 2-in-1        | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | [c56001eede](https://linux-hardware.org/?probe=c56001eede) | Feb 10, 2023 |
| HP            | Pavilion 15                 | [408fd874e7](https://linux-hardware.org/?probe=408fd874e7) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Acer          | Aspire A515-51              | [d68fb933eb](https://linux-hardware.org/?probe=d68fb933eb) | Feb 09, 2023 |
| Lenovo        | ThinkPad P53s 20N6CTO1WW    | [6b74ce317f](https://linux-hardware.org/?probe=6b74ce317f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| Acer          | Aspire E5-573G              | [8400619736](https://linux-hardware.org/?probe=8400619736) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| Unknown       | Unknown                     | [b541173c03](https://linux-hardware.org/?probe=b541173c03) | Feb 09, 2023 |
| Samsung       | R530/R730                   | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Lenovo        | B50-70 80EU                 | [637336f0d0](https://linux-hardware.org/?probe=637336f0d0) | Feb 07, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [3b6bf45c6b](https://linux-hardware.org/?probe=3b6bf45c6b) | Feb 07, 2023 |
| Unknown       | Unknown                     | [556a341257](https://linux-hardware.org/?probe=556a341257) | Feb 06, 2023 |
| Acer          | Aspire ES1-512              | [75b3a6b384](https://linux-hardware.org/?probe=75b3a6b384) | Feb 06, 2023 |
| MSI           | Stealth 15M B12UE           | [44de7ac1aa](https://linux-hardware.org/?probe=44de7ac1aa) | Feb 06, 2023 |
| SLIMBOOK      | Essential15L                | [e2af97d5d3](https://linux-hardware.org/?probe=e2af97d5d3) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [97421f92a6](https://linux-hardware.org/?probe=97421f92a6) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [a0fea9707e](https://linux-hardware.org/?probe=a0fea9707e) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| WinPAD 110... | I102A                       | [0619bb5a8d](https://linux-hardware.org/?probe=0619bb5a8d) | Feb 04, 2023 |
| Teclast       | F7S                         | [d4384ca831](https://linux-hardware.org/?probe=d4384ca831) | Feb 04, 2023 |
| Lenovo        | ThinkPad X250 20CLS2GD00    | [b80bfcae04](https://linux-hardware.org/?probe=b80bfcae04) | Feb 04, 2023 |
| HP            | Pavilion dv6700             | [d3755b3636](https://linux-hardware.org/?probe=d3755b3636) | Feb 04, 2023 |
| MSI           | Stealth 15M B12UE           | [c0434c976e](https://linux-hardware.org/?probe=c0434c976e) | Feb 04, 2023 |
| Acer          | Aspire ES1-512              | [278fbf008f](https://linux-hardware.org/?probe=278fbf008f) | Feb 03, 2023 |
| Valve         | Jupiter                     | [75208bbb30](https://linux-hardware.org/?probe=75208bbb30) | Feb 03, 2023 |
| Acer          | Aspire A315-58              | [32563eeffc](https://linux-hardware.org/?probe=32563eeffc) | Feb 03, 2023 |
| Unknown       | Unknown                     | [8a95ab4f06](https://linux-hardware.org/?probe=8a95ab4f06) | Feb 03, 2023 |
| Acer          | AOD255                      | [1b65896663](https://linux-hardware.org/?probe=1b65896663) | Feb 03, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [50d19e4206](https://linux-hardware.org/?probe=50d19e4206) | Feb 03, 2023 |
| MSI           | Stealth 15M B12UE           | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| Apple         | MacBookPro11,1              | [44f90bc9ab](https://linux-hardware.org/?probe=44f90bc9ab) | Feb 01, 2023 |
| HP            | Presario CQ57               | [0e34caefa3](https://linux-hardware.org/?probe=0e34caefa3) | Feb 01, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Fujitsu       | LIFEBOOK AH532              | [cf200b9cf1](https://linux-hardware.org/?probe=cf200b9cf1) | Jan 30, 2023 |
| MSI           | GF75 Thin 10UE              | [1177ccc150](https://linux-hardware.org/?probe=1177ccc150) | Jan 30, 2023 |
| Toshiba       | PORTEGE X30-E               | [01f74415b0](https://linux-hardware.org/?probe=01f74415b0) | Jan 30, 2023 |
| HP            | G62                         | [166ddbe627](https://linux-hardware.org/?probe=166ddbe627) | Jan 29, 2023 |
| HP            | ProBook 5320m               | [b8fc81e61c](https://linux-hardware.org/?probe=b8fc81e61c) | Jan 29, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T420 4236PN3       | [3b5c51e8b8](https://linux-hardware.org/?probe=3b5c51e8b8) | Jan 29, 2023 |
| Intel         | powered classmate PC        | [a3e602934b](https://linux-hardware.org/?probe=a3e602934b) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd07a46c6a](https://linux-hardware.org/?probe=dd07a46c6a) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [086e08a04b](https://linux-hardware.org/?probe=086e08a04b) | Jan 29, 2023 |
| ASUSTek       | X555LD                      | [3a3e1fafdf](https://linux-hardware.org/?probe=3a3e1fafdf) | Jan 28, 2023 |
| Valve         | Jupiter                     | [4a823b2eef](https://linux-hardware.org/?probe=4a823b2eef) | Jan 28, 2023 |
| ASUSTek       | ProArt StudioBook H7600H... | [8e9b78c0e8](https://linux-hardware.org/?probe=8e9b78c0e8) | Jan 28, 2023 |
| ASUSTek       | X751LB                      | [54094ae0a7](https://linux-hardware.org/?probe=54094ae0a7) | Jan 28, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4a82904f14](https://linux-hardware.org/?probe=4a82904f14) | Jan 28, 2023 |
| Samsung       | R520/R522/R620              | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Notebook      | N13_N140ZU                  | [94396ecebc](https://linux-hardware.org/?probe=94396ecebc) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| MSI           | Stealth 15M B12UE           | [463c397bb0](https://linux-hardware.org/?probe=463c397bb0) | Jan 26, 2023 |
| ASUSTek       | K55VD                       | [b2b19ec3f1](https://linux-hardware.org/?probe=b2b19ec3f1) | Jan 26, 2023 |
| MSI           | Stealth 15M B12UE           | [ff3fd2b8f1](https://linux-hardware.org/?probe=ff3fd2b8f1) | Jan 26, 2023 |
| Packard Be... | EasyNote TS44HR             | [2902a743da](https://linux-hardware.org/?probe=2902a743da) | Jan 26, 2023 |
| MSI           | Raider GE76 12UHS           | [95138f2861](https://linux-hardware.org/?probe=95138f2861) | Jan 26, 2023 |
| Acer          | Nitro AN515-52              | [6f06d51c7a](https://linux-hardware.org/?probe=6f06d51c7a) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| HP            | Pavilion g6                 | [a247cbd6d4](https://linux-hardware.org/?probe=a247cbd6d4) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [07d5199d1c](https://linux-hardware.org/?probe=07d5199d1c) | Jan 25, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [a1a1be6b56](https://linux-hardware.org/?probe=a1a1be6b56) | Jan 24, 2023 |
| Acer          | Aspire 5920G                | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Samsung       | 305V4A/305V5A               | [0f78cdd47e](https://linux-hardware.org/?probe=0f78cdd47e) | Jan 23, 2023 |
| Chuwi         | GemiBook Pro                | [3c2d563718](https://linux-hardware.org/?probe=3c2d563718) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | Laptop 15-da1xxx            | [8e4b1011d8](https://linux-hardware.org/?probe=8e4b1011d8) | Jan 22, 2023 |
| Qilive        | QW2214SP                    | [2dba516c91](https://linux-hardware.org/?probe=2dba516c91) | Jan 22, 2023 |
| Clevo         | W150ER                      | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| MSI           | Stealth 15M B12UE           | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | [00d43f76e1](https://linux-hardware.org/?probe=00d43f76e1) | Jan 21, 2023 |
| Acer          | Aspire E1-530               | [af5f0b7f58](https://linux-hardware.org/?probe=af5f0b7f58) | Jan 21, 2023 |
| HP            | Victus by Laptop 16-e1xx... | [65919b95b4](https://linux-hardware.org/?probe=65919b95b4) | Jan 20, 2023 |
| Toshiba       | NB520                       | [0252e3bec1](https://linux-hardware.org/?probe=0252e3bec1) | Jan 20, 2023 |
| HP            | Stream Notebook PC 11       | [be652213f6](https://linux-hardware.org/?probe=be652213f6) | Jan 19, 2023 |
| HP            | Stream Notebook PC 11       | [f92fcd0382](https://linux-hardware.org/?probe=f92fcd0382) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Dell          | Latitude 5410               | [da523f9f4c](https://linux-hardware.org/?probe=da523f9f4c) | Jan 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [0d3da58e45](https://linux-hardware.org/?probe=0d3da58e45) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a81a940d33](https://linux-hardware.org/?probe=a81a940d33) | Jan 17, 2023 |
| Dell          | Latitude 7490               | [390dc07426](https://linux-hardware.org/?probe=390dc07426) | Jan 17, 2023 |
| ASUSTek       | 1018P                       | [45cdf08df5](https://linux-hardware.org/?probe=45cdf08df5) | Jan 16, 2023 |
| HP            | EliteBook 840 G6            | [5a622c4769](https://linux-hardware.org/?probe=5a622c4769) | Jan 16, 2023 |
| MSI           | GE66 Raider 10SF            | [55f5300c59](https://linux-hardware.org/?probe=55f5300c59) | Jan 16, 2023 |
| Acer          | Aspire 5742G                | [5cda575387](https://linux-hardware.org/?probe=5cda575387) | Jan 16, 2023 |
| HUAWEI        | BOD-WXX9                    | [c854a01151](https://linux-hardware.org/?probe=c854a01151) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | [b0abb21613](https://linux-hardware.org/?probe=b0abb21613) | Jan 16, 2023 |
| Apple         | MacBookPro9,2               | [623477fd9e](https://linux-hardware.org/?probe=623477fd9e) | Jan 16, 2023 |
| HP            | Victus by Laptop 16-d0xx... | [a8ab10ee00](https://linux-hardware.org/?probe=a8ab10ee00) | Jan 16, 2023 |
| ASUSTek       | K55DR                       | [0dde03d33e](https://linux-hardware.org/?probe=0dde03d33e) | Jan 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a38eb750aa](https://linux-hardware.org/?probe=a38eb750aa) | Jan 16, 2023 |
| Sony          | VGN-AR51J                   | [ff9806f1ac](https://linux-hardware.org/?probe=ff9806f1ac) | Jan 15, 2023 |
| Dell          | Latitude E5550              | [ccbb0c484f](https://linux-hardware.org/?probe=ccbb0c484f) | Jan 15, 2023 |
| Dell          | Latitude E5550              | [28471496b4](https://linux-hardware.org/?probe=28471496b4) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | [9816c00c67](https://linux-hardware.org/?probe=9816c00c67) | Jan 15, 2023 |
| HP            | Presario CQ57               | [f223ceb77a](https://linux-hardware.org/?probe=f223ceb77a) | Jan 15, 2023 |
| ASUSTek       | K53SC                       | [812b55536d](https://linux-hardware.org/?probe=812b55536d) | Jan 15, 2023 |
| Apple         | MacBookAir6,2               | [2931eab7f7](https://linux-hardware.org/?probe=2931eab7f7) | Jan 15, 2023 |
| Chuwi         | GemiBook Pro                | [37d6076330](https://linux-hardware.org/?probe=37d6076330) | Jan 15, 2023 |
| MSI           | Stealth GS77 12UHS          | [0dba4d0126](https://linux-hardware.org/?probe=0dba4d0126) | Jan 14, 2023 |
| Lenovo        | B51-80 80LM                 | [0c5b712b3e](https://linux-hardware.org/?probe=0c5b712b3e) | Jan 14, 2023 |
| MSI           | Stealth GS77 12UHS          | [6a6636d3ba](https://linux-hardware.org/?probe=6a6636d3ba) | Jan 14, 2023 |
| eMachines     | E725                        | [048d832cef](https://linux-hardware.org/?probe=048d832cef) | Jan 13, 2023 |
| MSI           | Katana GF66 11UC            | [39b5188695](https://linux-hardware.org/?probe=39b5188695) | Jan 12, 2023 |
| HP            | Mini 110-3100               | [e6f11256b8](https://linux-hardware.org/?probe=e6f11256b8) | Jan 12, 2023 |
| Samsung       | RF510/RF410/RF710           | [9d63c96c7a](https://linux-hardware.org/?probe=9d63c96c7a) | Jan 12, 2023 |
| Acer          | Aspire A315-56              | [6ea0b8eab9](https://linux-hardware.org/?probe=6ea0b8eab9) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| ALLDOCUBE     | i1405C                      | [0713c94107](https://linux-hardware.org/?probe=0713c94107) | Jan 11, 2023 |
| Dell          | Inspiron 15-3552            | [e4ca0a9947](https://linux-hardware.org/?probe=e4ca0a9947) | Jan 11, 2023 |
| ASUSTek       | X541UV                      | [41358ca49b](https://linux-hardware.org/?probe=41358ca49b) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| Toshiba       | Satellite Pro NB10-A-12Q    | [f0c82d2046](https://linux-hardware.org/?probe=f0c82d2046) | Jan 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [5076e36526](https://linux-hardware.org/?probe=5076e36526) | Jan 11, 2023 |
| Acer          | Aspire 5253G                | [930e997f3a](https://linux-hardware.org/?probe=930e997f3a) | Jan 11, 2023 |
| ASUSTek       | K53U                        | [c7c4beb8cb](https://linux-hardware.org/?probe=c7c4beb8cb) | Jan 10, 2023 |
| Sony          | VPCCW1S1E                   | [5cc5248e94](https://linux-hardware.org/?probe=5cc5248e94) | Jan 10, 2023 |
| HP            | Notebook                    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| MSI           | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [be6a0a28e1](https://linux-hardware.org/?probe=be6a0a28e1) | Jan 10, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [62ddf88d2d](https://linux-hardware.org/?probe=62ddf88d2d) | Jan 10, 2023 |
| MSI           | Modern 14 B10RBSW           | [3dea4fbc97](https://linux-hardware.org/?probe=3dea4fbc97) | Jan 10, 2023 |
| Acer          | Aspire E1-531G              | [2476cc24c1](https://linux-hardware.org/?probe=2476cc24c1) | Jan 10, 2023 |
| ASUSTek       | K53SC                       | [002a8bdf0c](https://linux-hardware.org/?probe=002a8bdf0c) | Jan 09, 2023 |
| Acer          | Aspire E5-551G              | [dc659db065](https://linux-hardware.org/?probe=dc659db065) | Jan 09, 2023 |
| ASUSTek       | K54L                        | [5c67103146](https://linux-hardware.org/?probe=5c67103146) | Jan 09, 2023 |
| Lenovo        | G480 20150                  | [31f01e01fe](https://linux-hardware.org/?probe=31f01e01fe) | Jan 09, 2023 |
| HP            | 255 G7 Notebook PC          | [532f3544a2](https://linux-hardware.org/?probe=532f3544a2) | Jan 09, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [ad39556257](https://linux-hardware.org/?probe=ad39556257) | Jan 09, 2023 |
| Dell          | Studio 1558                 | [0e01a19694](https://linux-hardware.org/?probe=0e01a19694) | Jan 09, 2023 |
| HP            | OMEN by Laptop              | [84aa790d17](https://linux-hardware.org/?probe=84aa790d17) | Jan 09, 2023 |
| MSI           | Bravo 17 A4DDK              | [cf73810d98](https://linux-hardware.org/?probe=cf73810d98) | Jan 08, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [6af51bc93d](https://linux-hardware.org/?probe=6af51bc93d) | Jan 08, 2023 |
| Dynabook      | Satellite Pro C50-G         | [978b828ce6](https://linux-hardware.org/?probe=978b828ce6) | Jan 08, 2023 |
| ASUSTek       | X540YA                      | [b7021632b6](https://linux-hardware.org/?probe=b7021632b6) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [333358164d](https://linux-hardware.org/?probe=333358164d) | Jan 08, 2023 |
| MSI           | Stealth 15M B12UE           | [c272167e6a](https://linux-hardware.org/?probe=c272167e6a) | Jan 08, 2023 |
| Acer          | TravelMate P256-MG          | [e090a2b61c](https://linux-hardware.org/?probe=e090a2b61c) | Jan 07, 2023 |
| ASUSTek       | K53U                        | [46610b735e](https://linux-hardware.org/?probe=46610b735e) | Jan 07, 2023 |
| Google        | Candy                       | [1b955d9847](https://linux-hardware.org/?probe=1b955d9847) | Jan 07, 2023 |
| Chuwi         | HeroBook Air                | [58434d2c3c](https://linux-hardware.org/?probe=58434d2c3c) | Jan 06, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6e3d10ba74](https://linux-hardware.org/?probe=6e3d10ba74) | Jan 06, 2023 |
| Apple         | MacBookPro4,1               | [9fd9040304](https://linux-hardware.org/?probe=9fd9040304) | Jan 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [31f9cd0972](https://linux-hardware.org/?probe=31f9cd0972) | Jan 05, 2023 |
| MSI           | Stealth 15M B12UE           | [9e01a37071](https://linux-hardware.org/?probe=9e01a37071) | Jan 04, 2023 |
| Chuwi         | GemiBook Pro                | [2ede2771be](https://linux-hardware.org/?probe=2ede2771be) | Jan 03, 2023 |
| HP            | 250 G2                      | [430425dd1c](https://linux-hardware.org/?probe=430425dd1c) | Jan 03, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [9ba40bc6b5](https://linux-hardware.org/?probe=9ba40bc6b5) | Jan 03, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Chuwi         | GemiBook Pro                | [893d1002f6](https://linux-hardware.org/?probe=893d1002f6) | Jan 02, 2023 |
| Samsung       | RF510/RF410/RF710           | [3da2c535f7](https://linux-hardware.org/?probe=3da2c535f7) | Jan 02, 2023 |
| Lenovo        | ThinkPad X220 4291QZ1       | [31a0bdb593](https://linux-hardware.org/?probe=31a0bdb593) | Jan 02, 2023 |
| ASUSTek       | X550VX                      | [e83ccf9576](https://linux-hardware.org/?probe=e83ccf9576) | Jan 01, 2023 |
| Samsung       | RF510/RF410/RF710           | [220854be2e](https://linux-hardware.org/?probe=220854be2e) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | [5ada77ec03](https://linux-hardware.org/?probe=5ada77ec03) | Jan 01, 2023 |
| Lenovo        | ThinkBook 13s G4 IAP 21A... | [817985e5bf](https://linux-hardware.org/?probe=817985e5bf) | Jan 01, 2023 |
| ASUSTek       | K53SC                       | [25912a6795](https://linux-hardware.org/?probe=25912a6795) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| MSI           | Stealth 15M B12UE           | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| HP            | 250 G8 Notebook PC          | [6b8db26ab8](https://linux-hardware.org/?probe=6b8db26ab8) | Dec 30, 2022 |
| Dell          | Latitude 9420               | [3c43afbd50](https://linux-hardware.org/?probe=3c43afbd50) | Dec 29, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [8e201646a8](https://linux-hardware.org/?probe=8e201646a8) | Dec 29, 2022 |
| HP            | ZBook 15 G2                 | [6d1ae8a0c9](https://linux-hardware.org/?probe=6d1ae8a0c9) | Dec 29, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2ea31ca86e](https://linux-hardware.org/?probe=2ea31ca86e) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| HP            | Mini 100e                   | [dd184e04ad](https://linux-hardware.org/?probe=dd184e04ad) | Dec 28, 2022 |
| Gigabyte      | AERO 17 XE5                 | [979483f168](https://linux-hardware.org/?probe=979483f168) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| Valve         | Jupiter                     | [15cbe24d03](https://linux-hardware.org/?probe=15cbe24d03) | Dec 28, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [d579ff34ee](https://linux-hardware.org/?probe=d579ff34ee) | Dec 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [9dec6385d7](https://linux-hardware.org/?probe=9dec6385d7) | Dec 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d702a6b606](https://linux-hardware.org/?probe=d702a6b606) | Dec 27, 2022 |
| Acer          | Aspire 7741                 | [5ef8e01957](https://linux-hardware.org/?probe=5ef8e01957) | Dec 27, 2022 |
| MSI           | MS-7A34                     | [4668f06370](https://linux-hardware.org/?probe=4668f06370) | Dec 26, 2022 |
| HP            | Mini 100e                   | [bf749ac406](https://linux-hardware.org/?probe=bf749ac406) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | [9b26454313](https://linux-hardware.org/?probe=9b26454313) | Dec 26, 2022 |
| Dynabook      | Satellite Pro C50-J         | [ee842c64a3](https://linux-hardware.org/?probe=ee842c64a3) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| Acer          | Aspire 5732Z                | [96bc08bcbd](https://linux-hardware.org/?probe=96bc08bcbd) | Dec 26, 2022 |
| ASUSTek       | K55VD                       | [52df2ba00b](https://linux-hardware.org/?probe=52df2ba00b) | Dec 25, 2022 |
| Chuwi         | HeroBook Air                | [1f96a04f20](https://linux-hardware.org/?probe=1f96a04f20) | Dec 25, 2022 |
| ASUSTek       | ROG Strix G713IC_G713IC     | [72fa60782d](https://linux-hardware.org/?probe=72fa60782d) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [419580e899](https://linux-hardware.org/?probe=419580e899) | Dec 24, 2022 |
| MSI           | Stealth 15M B12UE           | [a8e294154b](https://linux-hardware.org/?probe=a8e294154b) | Dec 24, 2022 |
| ASUSTek       | K52JT                       | [915e35ba2b](https://linux-hardware.org/?probe=915e35ba2b) | Dec 24, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [2c6f47974f](https://linux-hardware.org/?probe=2c6f47974f) | Dec 23, 2022 |
| Valve         | Jupiter                     | [fc52b9e656](https://linux-hardware.org/?probe=fc52b9e656) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Acer          | Predator PH315-54           | [84bdb8f2eb](https://linux-hardware.org/?probe=84bdb8f2eb) | Dec 23, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [c47eaa75b3](https://linux-hardware.org/?probe=c47eaa75b3) | Dec 23, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [791ace450e](https://linux-hardware.org/?probe=791ace450e) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2505eabeaf](https://linux-hardware.org/?probe=2505eabeaf) | Dec 22, 2022 |
| MSI           | Stealth 15M B12UE           | [65d1cc61ba](https://linux-hardware.org/?probe=65d1cc61ba) | Dec 22, 2022 |
| Acer          | Aspire A315-54              | [c603811f9a](https://linux-hardware.org/?probe=c603811f9a) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | B590 62743PG                | [622f5d6e45](https://linux-hardware.org/?probe=622f5d6e45) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [6f7a27c8c5](https://linux-hardware.org/?probe=6f7a27c8c5) | Dec 21, 2022 |
| MSI           | Stealth 15M B12UE           | [ce6c271622](https://linux-hardware.org/?probe=ce6c271622) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| Acer          | Aspire E5-575G              | [56a3b5ff2b](https://linux-hardware.org/?probe=56a3b5ff2b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d2e0ceb9a5](https://linux-hardware.org/?probe=d2e0ceb9a5) | Dec 20, 2022 |
| Acer          | Predator PH315-54           | [c291063360](https://linux-hardware.org/?probe=c291063360) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| MSI           | GE62 6QD                    | [20d959e778](https://linux-hardware.org/?probe=20d959e778) | Dec 19, 2022 |
| Dell          | Latitude E5420              | [c9a7b379e6](https://linux-hardware.org/?probe=c9a7b379e6) | Dec 19, 2022 |
| Toshiba       | Satellite L10W-B-101        | [94e7515168](https://linux-hardware.org/?probe=94e7515168) | Dec 19, 2022 |
| ASUSTek       | X556UJ                      | [256957850d](https://linux-hardware.org/?probe=256957850d) | Dec 19, 2022 |
| Alienware     | x17 R1                      | [a5ff52a7ce](https://linux-hardware.org/?probe=a5ff52a7ce) | Dec 19, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [ab3b4786ea](https://linux-hardware.org/?probe=ab3b4786ea) | Dec 19, 2022 |
| MSI           | PS42 8RB                    | [42422af633](https://linux-hardware.org/?probe=42422af633) | Dec 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c94cd1a926](https://linux-hardware.org/?probe=c94cd1a926) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| HUAWEI        | KLVL-WXXW                   | [1deb35f268](https://linux-hardware.org/?probe=1deb35f268) | Dec 17, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [be60ec8881](https://linux-hardware.org/?probe=be60ec8881) | Dec 17, 2022 |
| Valve         | Jupiter                     | [4a37142af9](https://linux-hardware.org/?probe=4a37142af9) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [35d2e25287](https://linux-hardware.org/?probe=35d2e25287) | Dec 15, 2022 |
| HP            | EliteBook 850 G1            | [d923d3def3](https://linux-hardware.org/?probe=d923d3def3) | Dec 14, 2022 |
| ASUSTek       | X550VX                      | [0ee46688fb](https://linux-hardware.org/?probe=0ee46688fb) | Dec 14, 2022 |
| MSI           | GF63 Thin 9SC               | [e8dcf65234](https://linux-hardware.org/?probe=e8dcf65234) | Dec 14, 2022 |
| Dell          | Vostro 14 5410              | [d858d468cc](https://linux-hardware.org/?probe=d858d468cc) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [f62b69abcb](https://linux-hardware.org/?probe=f62b69abcb) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Dell          | XPS 15 9550                 | [61905b4fac](https://linux-hardware.org/?probe=61905b4fac) | Dec 13, 2022 |
| Acer          | Nitro AN515-58              | [9c13949220](https://linux-hardware.org/?probe=9c13949220) | Dec 13, 2022 |
| Dell          | Inspiron 3493               | [8ee8a5a64c](https://linux-hardware.org/?probe=8ee8a5a64c) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | Notebook                    | [07b9e8995f](https://linux-hardware.org/?probe=07b9e8995f) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [d262eae22d](https://linux-hardware.org/?probe=d262eae22d) | Dec 12, 2022 |
| Unknown       | Unknown                     | [a6efa9c8ab](https://linux-hardware.org/?probe=a6efa9c8ab) | Dec 12, 2022 |
| Unknown       | Unknown                     | [b9b1bab552](https://linux-hardware.org/?probe=b9b1bab552) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| MSI           | Modern 14 A10RB             | [849203accb](https://linux-hardware.org/?probe=849203accb) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [fd0700b7ae](https://linux-hardware.org/?probe=fd0700b7ae) | Dec 12, 2022 |
| ASUSTek       | K55VD                       | [f74382c966](https://linux-hardware.org/?probe=f74382c966) | Dec 12, 2022 |
| HP            | Laptop 15-bw0xx             | [1d2ea30fb2](https://linux-hardware.org/?probe=1d2ea30fb2) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| HP            | 620                         | [65ef44647a](https://linux-hardware.org/?probe=65ef44647a) | Dec 11, 2022 |
| Lenovo        | G710                        | [e1c54d8bc8](https://linux-hardware.org/?probe=e1c54d8bc8) | Dec 10, 2022 |
| Lenovo        | G710                        | [b2231f4343](https://linux-hardware.org/?probe=b2231f4343) | Dec 10, 2022 |
| Valve         | Jupiter                     | [e8e7f4358d](https://linux-hardware.org/?probe=e8e7f4358d) | Dec 10, 2022 |
| HP            | ProBook 650 G2              | [ad7c0195e5](https://linux-hardware.org/?probe=ad7c0195e5) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d7b8344d86](https://linux-hardware.org/?probe=d7b8344d86) | Dec 09, 2022 |
| Dell          | Latitude E6500              | [291fbde8c4](https://linux-hardware.org/?probe=291fbde8c4) | Dec 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9122edaf0a](https://linux-hardware.org/?probe=9122edaf0a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [659b20c9b8](https://linux-hardware.org/?probe=659b20c9b8) | Dec 06, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | [3327de3dc5](https://linux-hardware.org/?probe=3327de3dc5) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440s 20ARS2A50... | [082e17aab7](https://linux-hardware.org/?probe=082e17aab7) | Dec 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [302b36a67e](https://linux-hardware.org/?probe=302b36a67e) | Dec 05, 2022 |
| Toshiba       | PORTEGE M800                | [baf04ad2b3](https://linux-hardware.org/?probe=baf04ad2b3) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [d69f4daaa6](https://linux-hardware.org/?probe=d69f4daaa6) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | [5ae5166847](https://linux-hardware.org/?probe=5ae5166847) | Dec 05, 2022 |
| MSI           | GF63 Thin 9SC               | [1a52a1c699](https://linux-hardware.org/?probe=1a52a1c699) | Dec 05, 2022 |
| Valve         | Jupiter                     | [a1975d14f5](https://linux-hardware.org/?probe=a1975d14f5) | Dec 04, 2022 |
| Acer          | Aspire E5-573               | [30f8bd2ae9](https://linux-hardware.org/?probe=30f8bd2ae9) | Dec 04, 2022 |
| MSI           | GE72 6QD                    | [257a807435](https://linux-hardware.org/?probe=257a807435) | Dec 04, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d64272e554](https://linux-hardware.org/?probe=d64272e554) | Dec 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c544d40ecb](https://linux-hardware.org/?probe=c544d40ecb) | Dec 02, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [2cf7f9ab67](https://linux-hardware.org/?probe=2cf7f9ab67) | Dec 01, 2022 |
| ASUSTek       | K55VD                       | [149d517fa5](https://linux-hardware.org/?probe=149d517fa5) | Dec 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0aa3ec7616](https://linux-hardware.org/?probe=0aa3ec7616) | Nov 30, 2022 |
| Acer          | Aspire A315-34              | [6bf371252b](https://linux-hardware.org/?probe=6bf371252b) | Nov 30, 2022 |
| ASUSTek       | UX550VD                     | [a3f2aafbf1](https://linux-hardware.org/?probe=a3f2aafbf1) | Nov 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [b4aeee5799](https://linux-hardware.org/?probe=b4aeee5799) | Nov 30, 2022 |
| HP            | EliteBook 860 16 inch G9... | [dda393ca54](https://linux-hardware.org/?probe=dda393ca54) | Nov 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [944ace565b](https://linux-hardware.org/?probe=944ace565b) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [19b00c186f](https://linux-hardware.org/?probe=19b00c186f) | Nov 30, 2022 |
| HP            | Laptop 15s-fq4xxx           | [18ec3bc77e](https://linux-hardware.org/?probe=18ec3bc77e) | Nov 30, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | [3f19147b70](https://linux-hardware.org/?probe=3f19147b70) | Nov 29, 2022 |
| Acer          | Aspire A315-34              | [56bb76fb28](https://linux-hardware.org/?probe=56bb76fb28) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| HUAWEI        | CREM-WXX9                   | [ddad96715a](https://linux-hardware.org/?probe=ddad96715a) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| HP            | Notebook                    | [79929c5c49](https://linux-hardware.org/?probe=79929c5c49) | Nov 29, 2022 |
| HP            | ProBook 450 G5              | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | [d5f03d47ba](https://linux-hardware.org/?probe=d5f03d47ba) | Nov 28, 2022 |
| Acer          | Aspire 5742G                | [e0701bc81d](https://linux-hardware.org/?probe=e0701bc81d) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | [8bd9aae635](https://linux-hardware.org/?probe=8bd9aae635) | Nov 28, 2022 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [c95bbb16de](https://linux-hardware.org/?probe=c95bbb16de) | Nov 28, 2022 |
| PC Special... | NH5xAx                      | [3be194cb8a](https://linux-hardware.org/?probe=3be194cb8a) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [d62cc93587](https://linux-hardware.org/?probe=d62cc93587) | Nov 28, 2022 |
| ASUSTek       | X555LAB                     | [8d8fc0d4d4](https://linux-hardware.org/?probe=8d8fc0d4d4) | Nov 28, 2022 |
| ASUSTek       | X555YA                      | [0e9bb436b5](https://linux-hardware.org/?probe=0e9bb436b5) | Nov 27, 2022 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [76087ad674](https://linux-hardware.org/?probe=76087ad674) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [419b7f448b](https://linux-hardware.org/?probe=419b7f448b) | Nov 26, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5bd5bcabdb](https://linux-hardware.org/?probe=5bd5bcabdb) | Nov 26, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | [4393448090](https://linux-hardware.org/?probe=4393448090) | Nov 25, 2022 |
| HP            | ProBook 430 G3              | [0fa29b61e3](https://linux-hardware.org/?probe=0fa29b61e3) | Nov 24, 2022 |
| ASUSTek       | 1001PX                      | [9626b2b4c5](https://linux-hardware.org/?probe=9626b2b4c5) | Nov 24, 2022 |
| Apple         | MacBookAir6,2               | [1f43ba0436](https://linux-hardware.org/?probe=1f43ba0436) | Nov 24, 2022 |
| Lenovo        | ThinkPad T420 4180GH5       | [8dba4b2123](https://linux-hardware.org/?probe=8dba4b2123) | Nov 23, 2022 |
| MSI           | Modern 14 A10M              | [0545f4e38b](https://linux-hardware.org/?probe=0545f4e38b) | Nov 23, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [df91e2d404](https://linux-hardware.org/?probe=df91e2d404) | Nov 23, 2022 |
| Apple         | MacBook5,1                  | [f2ecb3f4a8](https://linux-hardware.org/?probe=f2ecb3f4a8) | Nov 22, 2022 |
| Acer          | Aspire A715-74G             | [347af27c05](https://linux-hardware.org/?probe=347af27c05) | Nov 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [437c6e491d](https://linux-hardware.org/?probe=437c6e491d) | Nov 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8bd0cdff15](https://linux-hardware.org/?probe=8bd0cdff15) | Nov 19, 2022 |
| HP            | EliteBook 840 G1            | [45a5881e61](https://linux-hardware.org/?probe=45a5881e61) | Nov 19, 2022 |
| Apple         | MacBook5,1                  | [9311687e42](https://linux-hardware.org/?probe=9311687e42) | Nov 19, 2022 |
| Toshiba       | Satellite P50-B-10Z         | [c5413ac393](https://linux-hardware.org/?probe=c5413ac393) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b39151a5a7](https://linux-hardware.org/?probe=b39151a5a7) | Nov 19, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [b0babeaa2b](https://linux-hardware.org/?probe=b0babeaa2b) | Nov 19, 2022 |
| Acer          | Extensa 5220                | [0bf5f727ac](https://linux-hardware.org/?probe=0bf5f727ac) | Nov 19, 2022 |
| Acer          | Aspire E1-572G              | [36c1e37d05](https://linux-hardware.org/?probe=36c1e37d05) | Nov 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea12bf4774](https://linux-hardware.org/?probe=ea12bf4774) | Nov 18, 2022 |
| HP            | Elite x2 1012 G1            | [ef366c64fe](https://linux-hardware.org/?probe=ef366c64fe) | Nov 18, 2022 |
| Samsung       | R610                        | [b6c7aa2939](https://linux-hardware.org/?probe=b6c7aa2939) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| Apple         | MacBookPro14,1              | [248fcb5f13](https://linux-hardware.org/?probe=248fcb5f13) | Nov 17, 2022 |
| Acer          | Extensa 5220                | [8e9441be64](https://linux-hardware.org/?probe=8e9441be64) | Nov 17, 2022 |
| Toshiba       | Satellite L10W-B-101        | [544ad40774](https://linux-hardware.org/?probe=544ad40774) | Nov 16, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [5ea39eac4c](https://linux-hardware.org/?probe=5ea39eac4c) | Nov 16, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [be72c5d9db](https://linux-hardware.org/?probe=be72c5d9db) | Nov 16, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [c38c6ddff6](https://linux-hardware.org/?probe=c38c6ddff6) | Nov 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [b139741f4f](https://linux-hardware.org/?probe=b139741f4f) | Nov 15, 2022 |
| Dell          | Latitude E5470              | [ae3d91be5a](https://linux-hardware.org/?probe=ae3d91be5a) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [ee5852d273](https://linux-hardware.org/?probe=ee5852d273) | Nov 15, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [1604955bcb](https://linux-hardware.org/?probe=1604955bcb) | Nov 15, 2022 |
| ALURIN        | PR1-M146                    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [722455f99d](https://linux-hardware.org/?probe=722455f99d) | Nov 14, 2022 |
| Lenovo        | V14-ADA 82C6                | [7971c5cda7](https://linux-hardware.org/?probe=7971c5cda7) | Nov 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [465bc481e2](https://linux-hardware.org/?probe=465bc481e2) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| MSI           | GF63 8RD                    | [0ca4cc20c5](https://linux-hardware.org/?probe=0ca4cc20c5) | Nov 13, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [be61d3792c](https://linux-hardware.org/?probe=be61d3792c) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| Dell          | G3 3579                     | [a2e410da57](https://linux-hardware.org/?probe=a2e410da57) | Nov 12, 2022 |
| Dell          | XPS 13 9343                 | [fed6627c3e](https://linux-hardware.org/?probe=fed6627c3e) | Nov 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [76609a3bd3](https://linux-hardware.org/?probe=76609a3bd3) | Nov 12, 2022 |
| HP            | Pavilion 15                 | [f6125d7605](https://linux-hardware.org/?probe=f6125d7605) | Nov 11, 2022 |
| HP            | Pavilion 15                 | [a598e64905](https://linux-hardware.org/?probe=a598e64905) | Nov 11, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| LG Electro... | 16Z90Q-G.AD78B              | [e5129b607e](https://linux-hardware.org/?probe=e5129b607e) | Nov 09, 2022 |
| HP            | Pavilion g7                 | [3a18145808](https://linux-hardware.org/?probe=3a18145808) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [94746f0b72](https://linux-hardware.org/?probe=94746f0b72) | Nov 09, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [61bf21f7dd](https://linux-hardware.org/?probe=61bf21f7dd) | Nov 09, 2022 |
| Valve         | Jupiter                     | [3e3e947f9e](https://linux-hardware.org/?probe=3e3e947f9e) | Nov 08, 2022 |
| HUAWEI        | BOD-WXX9                    | [c36ab935b5](https://linux-hardware.org/?probe=c36ab935b5) | Nov 08, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [bbb94242ec](https://linux-hardware.org/?probe=bbb94242ec) | Nov 07, 2022 |
| HP            | ZBook Studio 15.6 inch G... | [000b225d22](https://linux-hardware.org/?probe=000b225d22) | Nov 07, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 396       | 12.33%  |
| Ubuntu 18.04       | 256       | 7.97%   |
| Ubuntu 22.04       | 172       | 5.35%   |
| Debian 11          | 136       | 4.23%   |
| OpenMandriva 4.2   | 84        | 2.62%   |
| Zorin 16           | 72        | 2.24%   |
| KDE neon 20.04     | 63        | 1.96%   |
| OpenMandriva 4.3   | 61        | 1.9%    |
| Linux Mint 20.3    | 45        | 1.4%    |
| Arch               | 41        | 1.28%   |
| Arch Rolling       | 40        | 1.25%   |
| Xubuntu 20.04      | 39        | 1.21%   |
| Ubuntu 20.10       | 39        | 1.21%   |
| Manjaro            | 39        | 1.21%   |
| OpenMandriva 23.01 | 38        | 1.18%   |
| Linux Mint 21.1    | 37        | 1.15%   |
| Linux Mint 19.3    | 37        | 1.15%   |
| Debian 10          | 36        | 1.12%   |
| Ubuntu 19.10       | 34        | 1.06%   |
| Pop!_OS 22.04      | 33        | 1.03%   |
| Ubuntu 21.04       | 32        | 1%      |
| Ubuntu 19.04       | 32        | 1%      |
| Linux Mint 20.1    | 32        | 1%      |
| Linux Mint 20      | 30        | 0.93%   |
| Kubuntu 20.04      | 30        | 0.93%   |
| Fedora 37          | 30        | 0.93%   |
| Fedora 36          | 30        | 0.93%   |
| Ubuntu 21.10       | 29        | 0.9%    |
| Xubuntu 18.04      | 28        | 0.87%   |
| Ubuntu 22.10       | 28        | 0.87%   |
| Zorin 15           | 27        | 0.84%   |
| Linux Mint 20.2    | 27        | 0.84%   |
| Linux Mint 21      | 26        | 0.81%   |
| Fedora 35          | 25        | 0.78%   |
| Fedora 34          | 24        | 0.75%   |
| Fedora 33          | 24        | 0.75%   |
| OpenMandriva 23.03 | 23        | 0.72%   |
| ROSA R10           | 22        | 0.68%   |
| Ubuntu 18.10       | 21        | 0.65%   |
| Pop!_OS 20.04      | 21        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1029      | 33.74%  |
| Linux Mint    | 255       | 8.36%   |
| Debian        | 217       | 7.11%   |
| OpenMandriva  | 211       | 6.92%   |
| Fedora        | 165       | 5.41%   |
| Zorin         | 102       | 3.34%   |
| Manjaro       | 102       | 3.34%   |
| Endless       | 100       | 3.28%   |
| Pop!_OS       | 86        | 2.82%   |
| KDE neon      | 81        | 2.66%   |
| Xubuntu       | 80        | 2.62%   |
| Arch          | 80        | 2.62%   |
| Kubuntu       | 71        | 2.33%   |
| ROSA          | 56        | 1.84%   |
| Ubuntu MATE   | 33        | 1.08%   |
| Kali          | 31        | 1.02%   |
| Elementary    | 31        | 1.02%   |
| SteamOS       | 29        | 0.95%   |
| openSUSE      | 28        | 0.92%   |
| ArcoLinux     | 25        | 0.82%   |
| Ubuntu Unity  | 23        | 0.75%   |
| Gentoo        | 18        | 0.59%   |
| Lubuntu       | 17        | 0.56%   |
| BlackPanther  | 16        | 0.52%   |
| Parrot        | 14        | 0.46%   |
| LMDE          | 14        | 0.46%   |
| Nobara        | 13        | 0.43%   |
| EndeavourOS   | 13        | 0.43%   |
| Ubuntu Budgie | 8         | 0.26%   |
| MX            | 8         | 0.26%   |
| Clear Linux   | 7         | 0.23%   |
| Garuda Linux  | 5         | 0.16%   |
| Deepin        | 5         | 0.16%   |
| CentOS        | 5         | 0.16%   |
| RHEL          | 4         | 0.13%   |
| BunsenLabs    | 4         | 0.13%   |
| Ubuntu Studio | 3         | 0.1%    |
| Solus         | 3         | 0.1%    |
| Reborn OS     | 3         | 0.1%    |
| Q4OS          | 3         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 82        | 2.34%   |
| 5.16.7-desktop-1omv4003  | 60        | 1.71%   |
| 5.4.0-42-generic         | 48        | 1.37%   |
| 5.15.0-56-generic        | 36        | 1.03%   |
| 6.1.1-desktop-1omv2290   | 35        | 1%      |
| 5.10.0-8-amd64           | 34        | 0.97%   |
| 5.4.0-58-generic         | 33        | 0.94%   |
| 5.15.0-52-generic        | 32        | 0.91%   |
| 5.3.0-28-generic         | 31        | 0.89%   |
| 5.4.0-54-generic         | 27        | 0.77%   |
| 5.4.0-52-generic         | 26        | 0.74%   |
| 5.4.0-26-generic         | 26        | 0.74%   |
| 5.10.0-18-amd64          | 26        | 0.74%   |
| 5.15.0-58-generic        | 24        | 0.69%   |
| 6.2.6-desktop-1omv2390   | 23        | 0.66%   |
| 5.15.0-53-generic        | 22        | 0.63%   |
| 5.11.0-27-generic        | 22        | 0.63%   |
| 5.0.0-37-generic         | 22        | 0.63%   |
| 5.3.0-46-generic         | 21        | 0.6%    |
| 5.3.0-40-generic         | 21        | 0.6%    |
| 5.15.0-48-generic        | 21        | 0.6%    |
| 5.4.0-65-generic         | 20        | 0.57%   |
| 5.4.0-48-generic         | 20        | 0.57%   |
| 5.19.0-35-generic        | 19        | 0.54%   |
| 5.11.0-43-generic        | 19        | 0.54%   |
| 5.11.0-41-generic        | 19        | 0.54%   |
| 5.4.0-72-generic         | 18        | 0.51%   |
| 5.4.0-40-generic         | 18        | 0.51%   |
| 5.13.0-valve36-1-neptune | 18        | 0.51%   |
| 5.0.0-32-generic         | 18        | 0.51%   |
| 5.8.0-44-generic         | 17        | 0.49%   |
| 5.4.0-19-generic         | 16        | 0.46%   |
| 5.3.0-45-generic         | 16        | 0.46%   |
| 5.8.0-14-generic         | 15        | 0.43%   |
| 5.4.0-53-generic         | 15        | 0.43%   |
| 5.4.0-29-generic         | 15        | 0.43%   |
| 5.15.0-47-generic        | 15        | 0.43%   |
| 5.13.0-28-generic        | 15        | 0.43%   |
| 5.8.0-43-generic         | 14        | 0.4%    |
| 5.4.0-91-generic         | 14        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 544       | 16.43%  |
| 5.15.0  | 304       | 9.18%   |
| 4.15.0  | 205       | 6.19%   |
| 5.11.0  | 168       | 5.07%   |
| 5.10.0  | 158       | 4.77%   |
| 5.3.0   | 153       | 4.62%   |
| 5.8.0   | 150       | 4.53%   |
| 5.13.0  | 143       | 4.32%   |
| 5.19.0  | 119       | 3.59%   |
| 5.0.0   | 109       | 3.29%   |
| 5.10.14 | 83        | 2.51%   |
| 4.18.0  | 71        | 2.14%   |
| 5.16.7  | 64        | 1.93%   |
| 4.19.0  | 42        | 1.27%   |
| 6.1.1   | 41        | 1.24%   |
| 6.2.6   | 36        | 1.09%   |
| 6.1.0   | 33        | 1%      |
| 6.2.0   | 23        | 0.69%   |
| 6.0.0   | 16        | 0.48%   |
| 5.14.0  | 16        | 0.48%   |
| 4.9.60  | 15        | 0.45%   |
| 6.0.12  | 13        | 0.39%   |
| 5.18.0  | 13        | 0.39%   |
| 4.4.0   | 13        | 0.39%   |
| 4.18.16 | 13        | 0.39%   |
| 6.1.11  | 11        | 0.33%   |
| 5.9.16  | 10        | 0.3%    |
| 5.17.5  | 9         | 0.27%   |
| 6.1.12  | 8         | 0.24%   |
| 5.16.0  | 8         | 0.24%   |
| 6.0.10  | 7         | 0.21%   |
| 5.3.18  | 7         | 0.21%   |
| 5.17.1  | 7         | 0.21%   |
| 5.13.12 | 7         | 0.21%   |
| 5.11.12 | 7         | 0.21%   |
| 6.4.7   | 6         | 0.18%   |
| 6.3.1   | 6         | 0.18%   |
| 6.2.12  | 6         | 0.18%   |
| 6.0.6   | 6         | 0.18%   |
| 5.9.0   | 6         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 577       | 17.68%  |
| 5.15    | 363       | 11.12%  |
| 5.10    | 280       | 8.58%   |
| 4.15    | 205       | 6.28%   |
| 5.11    | 196       | 6%      |
| 5.8     | 176       | 5.39%   |
| 5.3     | 168       | 5.15%   |
| 5.13    | 163       | 4.99%   |
| 5.19    | 152       | 4.66%   |
| 6.1     | 126       | 3.86%   |
| 5.0     | 111       | 3.4%    |
| 5.16    | 101       | 3.09%   |
| 6.2     | 96        | 2.94%   |
| 4.18    | 84        | 2.57%   |
| 6.0     | 59        | 1.81%   |
| 4.19    | 50        | 1.53%   |
| 5.14    | 45        | 1.38%   |
| 4.9     | 39        | 1.19%   |
| 5.18    | 37        | 1.13%   |
| 5.17    | 30        | 0.92%   |
| 5.9     | 29        | 0.89%   |
| 6.3     | 27        | 0.83%   |
| 5.6     | 25        | 0.77%   |
| 5.7     | 24        | 0.74%   |
| 5.12    | 23        | 0.7%    |
| 6.4     | 21        | 0.64%   |
| 5.5     | 14        | 0.43%   |
| 4.4     | 14        | 0.43%   |
| 4.16    | 5         | 0.15%   |
| 5.2     | 4         | 0.12%   |
| 4.1     | 4         | 0.12%   |
| 3.10    | 4         | 0.12%   |
| 5.1     | 3         | 0.09%   |
| 4.20    | 3         | 0.09%   |
| 4.13    | 3         | 0.09%   |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 3.16    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2820      | 95.69%  |
| i686   | 127       | 4.31%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1358      | 44.02%  |
| KDE5             | 537       | 17.41%  |
| Unknown          | 338       | 10.96%  |
| XFCE             | 252       | 8.17%   |
| X-Cinnamon       | 195       | 6.32%   |
| MATE             | 87        | 2.82%   |
| KDE              | 76        | 2.46%   |
| Cinnamon         | 33        | 1.07%   |
| Pantheon         | 30        | 0.97%   |
| LXQt             | 25        | 0.81%   |
| Unity            | 22        | 0.71%   |
| KDE4             | 22        | 0.71%   |
| i3               | 20        | 0.65%   |
| LXDE             | 15        | 0.49%   |
| Budgie           | 14        | 0.45%   |
| GNOME Flashback  | 12        | 0.39%   |
| Deepin           | 9         | 0.29%   |
| openbox          | 6         | 0.19%   |
| GNOME Classic    | 5         | 0.16%   |
| bspwm            | 5         | 0.16%   |
| lightdm-xsession | 4         | 0.13%   |
| Dwm              | 4         | 0.13%   |
| LeftWM           | 2         | 0.06%   |
| icewm            | 2         | 0.06%   |
| xmonad           | 1         | 0.03%   |
| trinity          | 1         | 0.03%   |
| sway             | 1         | 0.03%   |
| river            | 1         | 0.03%   |
| qtile            | 1         | 0.03%   |
| Lubuntu          | 1         | 0.03%   |
| i3-with-shmlog   | 1         | 0.03%   |
| Hyprland         | 1         | 0.03%   |
| enlightenment    | 1         | 0.03%   |
| Cutefish         | 1         | 0.03%   |
| BunsenLabs       | 1         | 0.03%   |
| awesome          | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2344      | 77.16%  |
| Wayland | 481       | 15.83%  |
| Unknown | 192       | 6.32%   |
| Tty     | 21        | 0.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1524      | 49.87%  |
| SDDM    | 446       | 14.59%  |
| GDM     | 372       | 12.17%  |
| GDM3    | 318       | 10.41%  |
| LightDM | 266       | 8.7%    |
| TDM     | 90        | 2.95%   |
| KDM     | 24        | 0.79%   |
| XDM     | 7         | 0.23%   |
| SLiM    | 3         | 0.1%    |
| Ly      | 3         | 0.1%    |
| SLIMSKI | 1         | 0.03%   |
| LY-DM   | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| es_ES          | 1752      | 57.86%  |
| en_US          | 575       | 18.99%  |
| Unknown        | 342       | 11.29%  |
| ca_ES          | 113       | 3.73%   |
| en_GB          | 73        | 2.41%   |
| C              | 28        | 0.92%   |
| de_DE          | 21        | 0.69%   |
| gl_ES          | 13        | 0.43%   |
| eu_ES          | 12        | 0.4%    |
| ru_RU          | 10        | 0.33%   |
| it_IT          | 10        | 0.33%   |
| fr_FR          | 10        | 0.33%   |
| an_ES          | 9         | 0.3%    |
| es_MX          | 6         | 0.2%    |
| es_AR          | 6         | 0.2%    |
| pt_BR          | 5         | 0.17%   |
| en_AG          | 5         | 0.17%   |
| ca_AD          | 4         | 0.13%   |
| pl_PL          | 3         | 0.1%    |
| fr_BE          | 3         | 0.1%    |
| en_IE          | 3         | 0.1%    |
| POSIX          | 2         | 0.07%   |
| nl_NL          | 2         | 0.07%   |
| es_US          | 2         | 0.07%   |
| es_BO          | 2         | 0.07%   |
| de_CH          | 2         | 0.07%   |
| de_AT          | 2         | 0.07%   |
| sp_SP          | 1         | 0.03%   |
| ro_RO          | 1         | 0.03%   |
| nb_NO          | 1         | 0.03%   |
| fr_CH          | 1         | 0.03%   |
| et_EE          | 1         | 0.03%   |
| es_VE          | 1         | 0.03%   |
| es_PE          | 1         | 0.03%   |
| en_NZ          | 1         | 0.03%   |
| en_HK          | 1         | 0.03%   |
| en_CA          | 1         | 0.03%   |
| en_AU          | 1         | 0.03%   |
| ca_ES@valencia | 1         | 0.03%   |
| C.UTF8         | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1616      | 53.71%  |
| BIOS | 1393      | 46.29%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2330      | 76.9%   |
| Btrfs   | 236       | 7.79%   |
| Overlay | 222       | 7.33%   |
| Unknown | 111       | 3.66%   |
| Tmpfs   | 56        | 1.85%   |
| Xfs     | 37        | 1.22%   |
| Zfs     | 18        | 0.59%   |
| Ext2    | 10        | 0.33%   |
| Ext3    | 4         | 0.13%   |
| Aufs    | 3         | 0.1%    |
| Jfs     | 2         | 0.07%   |
| F2fs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1608      | 53.32%  |
| GPT     | 1099      | 36.44%  |
| MBR     | 309       | 10.25%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2661      | 88.67%  |
| Yes       | 340       | 11.33%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2081      | 69.44%  |
| Yes       | 916       | 30.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 543       | 18.43%  |
| Lenovo              | 500       | 16.97%  |
| ASUSTek Computer    | 440       | 14.94%  |
| Acer                | 295       | 10.01%  |
| Dell                | 235       | 7.98%   |
| MSI                 | 188       | 6.38%   |
| Toshiba             | 114       | 3.87%   |
| Apple               | 77        | 2.61%   |
| HUAWEI              | 52        | 1.77%   |
| Sony                | 44        | 1.49%   |
| Packard Bell        | 36        | 1.22%   |
| Chuwi               | 35        | 1.19%   |
| Notebook            | 34        | 1.15%   |
| Samsung Electronics | 33        | 1.12%   |
| Unknown             | 31        | 1.05%   |
| Valve               | 29        | 0.98%   |
| SLIMBOOK            | 26        | 0.88%   |
| LG Electronics      | 20        | 0.68%   |
| Medion              | 16        | 0.54%   |
| Fujitsu             | 13        | 0.44%   |
| Timi                | 12        | 0.41%   |
| Fujitsu Siemens     | 12        | 0.41%   |
| Gigabyte Technology | 11        | 0.37%   |
| eMachines           | 11        | 0.37%   |
| Clevo               | 9         | 0.31%   |
| Teclast             | 8         | 0.27%   |
| Intel               | 8         | 0.27%   |
| Dynabook            | 8         | 0.27%   |
| Google              | 5         | 0.17%   |
| Razer               | 4         | 0.14%   |
| PC Specialist       | 4         | 0.14%   |
| HONOR               | 4         | 0.14%   |
| VANT                | 3         | 0.1%    |
| Thomson             | 3         | 0.1%    |
| Qilive              | 3         | 0.1%    |
| IBM                 | 3         | 0.1%    |
| Compal              | 3         | 0.1%    |
| Beelink             | 3         | 0.1%    |
| AMI                 | 3         | 0.1%    |
| Alienware           | 3         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 50        | 1.7%    |
| Valve Jupiter                              | 29        | 0.98%   |
| HP Pavilion g6                             | 22        | 0.75%   |
| HP Pavilion dv6                            | 20        | 0.68%   |
| HP Notebook                                | 20        | 0.68%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.61%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 17        | 0.58%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.51%   |
| HUAWEI BOHK-WAX9X                          | 12        | 0.41%   |
| HP G62                                     | 12        | 0.41%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 10        | 0.34%   |
| HP Pavilion 15                             | 10        | 0.34%   |
| HP Laptop 15-da0xxx                        | 10        | 0.34%   |
| Dell XPS 13 7390                           | 10        | 0.34%   |
| Chuwi GemiBook Pro                         | 10        | 0.34%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.31%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.27%   |
| HP Laptop 15s-fq1xxx                       | 8         | 0.27%   |
| HP Laptop 15-bw0xx                         | 8         | 0.27%   |
| ASUS X555LAB                               | 8         | 0.27%   |
| ASUS X550VX                                | 8         | 0.27%   |
| ASUS X540NA                                | 8         | 0.27%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.27%   |
| Acer TravelMate 5720                       | 8         | 0.27%   |
| Acer Aspire 5750G                          | 8         | 0.27%   |
| MSI Modern 14 A10M                         | 7         | 0.24%   |
| Lenovo Y520-15IKBN 80WK                    | 7         | 0.24%   |
| Lenovo Legion 5 15ACH6H 82JU               | 7         | 0.24%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.24%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 7         | 0.24%   |
| Lenovo G50-70 20351                        | 7         | 0.24%   |
| HUAWEI NBLK-WAX9X                          | 7         | 0.24%   |
| HP Victus by Laptop 16-e0xxx               | 7         | 0.24%   |
| HP ProBook 450 G8 Notebook PC              | 7         | 0.24%   |
| HP Pavilion Notebook                       | 7         | 0.24%   |
| HP Pavilion dv7                            | 7         | 0.24%   |
| HP OMEN by Laptop                          | 7         | 0.24%   |
| HP Laptop 15-db0xxx                        | 7         | 0.24%   |
| HP Laptop 15-bs0xx                         | 7         | 0.24%   |
| Dell XPS 13 9370                           | 7         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 209       | 7.09%   |
| Lenovo ThinkPad       | 193       | 6.55%   |
| Lenovo IdeaPad        | 144       | 4.89%   |
| HP Pavilion           | 131       | 4.45%   |
| Dell Latitude         | 96        | 3.26%   |
| Toshiba Satellite     | 88        | 2.99%   |
| ASUS VivoBook         | 85        | 2.89%   |
| HP Laptop             | 77        | 2.61%   |
| HP EliteBook          | 60        | 2.04%   |
| Dell XPS              | 57        | 1.93%   |
| Unknown               | 50        | 1.7%    |
| HP Compaq             | 40        | 1.36%   |
| HP ProBook            | 39        | 1.32%   |
| Dell Inspiron         | 39        | 1.32%   |
| ASUS ZenBook          | 37        | 1.26%   |
| ASUS ROG              | 35        | 1.19%   |
| Packard Bell EasyNote | 33        | 1.12%   |
| HP 250                | 32        | 1.09%   |
| Valve Jupiter         | 29        | 0.98%   |
| MSI Prestige          | 29        | 0.98%   |
| MSI Modern            | 28        | 0.95%   |
| Lenovo Legion         | 27        | 0.92%   |
| Acer TravelMate       | 25        | 0.85%   |
| HP OMEN               | 24        | 0.81%   |
| Acer Extensa          | 21        | 0.71%   |
| HP Notebook           | 20        | 0.68%   |
| ASUS ASUS             | 18        | 0.61%   |
| Lenovo ThinkBook      | 17        | 0.58%   |
| ASUS TUF              | 16        | 0.54%   |
| HP ENVY               | 15        | 0.51%   |
| Chuwi GemiBook        | 15        | 0.51%   |
| Lenovo Yoga           | 14        | 0.48%   |
| HP Victus             | 14        | 0.48%   |
| HUAWEI BOHK-WAX9X     | 12        | 0.41%   |
| HP G62                | 12        | 0.41%   |
| HP 255                | 12        | 0.41%   |
| Fujitsu LIFEBOOK      | 12        | 0.41%   |
| Dell Vostro           | 12        | 0.41%   |
| Toshiba PORTEGE       | 11        | 0.37%   |
| Apple MacBookPro11    | 11        | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 295       | 10.01%  |
| 2018    | 293       | 9.95%   |
| 2020    | 271       | 9.2%    |
| 2021    | 258       | 8.76%   |
| 2014    | 193       | 6.55%   |
| 2015    | 185       | 6.28%   |
| 2011    | 179       | 6.08%   |
| 2017    | 172       | 5.84%   |
| 2010    | 149       | 5.06%   |
| 2013    | 145       | 4.92%   |
| 2012    | 143       | 4.85%   |
| 2008    | 141       | 4.79%   |
| 2009    | 124       | 4.21%   |
| 2022    | 123       | 4.18%   |
| 2016    | 122       | 4.14%   |
| 2007    | 90        | 3.05%   |
| 2006    | 31        | 1.05%   |
| 2005    | 10        | 0.34%   |
| 2023    | 9         | 0.31%   |
| 2004    | 5         | 0.17%   |
| 2003    | 3         | 0.1%    |
| Unknown | 3         | 0.1%    |
| 2002    | 1         | 0.03%   |
| 2001    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2946      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2699      | 91%     |
| Enabled  | 267       | 9%      |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2938      | 99.73%  |
| Yes  | 8         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 773       | 25.9%   |
| 3.01-4.0    | 652       | 21.85%  |
| 8.01-16.0   | 557       | 18.67%  |
| 16.01-24.0  | 533       | 17.86%  |
| 32.01-64.0  | 187       | 6.27%   |
| 1.01-2.0    | 142       | 4.76%   |
| 2.01-3.0    | 55        | 1.84%   |
| 0.51-1.0    | 48        | 1.61%   |
| 64.01-256.0 | 18        | 0.6%    |
| 24.01-32.0  | 17        | 0.57%   |
| 0.01-0.5    | 2         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1200      | 36.83%  |
| 2.01-3.0   | 866       | 26.58%  |
| 4.01-8.0   | 414       | 12.71%  |
| 3.01-4.0   | 374       | 11.48%  |
| 0.51-1.0   | 253       | 7.77%   |
| 8.01-16.0  | 111       | 3.41%   |
| 0.01-0.5   | 29        | 0.89%   |
| 16.01-24.0 | 7         | 0.21%   |
| 24.01-32.0 | 3         | 0.09%   |
| 32.01-64.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2264      | 75.47%  |
| 2      | 630       | 21%     |
| 3      | 71        | 2.37%   |
| 0      | 26        | 0.87%   |
| 4      | 6         | 0.2%    |
| 5      | 3         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1936      | 65.38%  |
| Yes       | 1025      | 34.62%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2350      | 79.31%  |
| No        | 613       | 20.69%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2885      | 97.93%  |
| No        | 61        | 2.07%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2201      | 74.11%  |
| No        | 769       | 25.89%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 2946      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 511       | 15.89%  |
| Barcelona                  | 354       | 11.01%  |
| Seville                    | 117       | 3.64%   |
| Valencia                   | 103       | 3.2%    |
| Zaragoza                   | 52        | 1.62%   |
| Granada                    | 49        | 1.52%   |
| Málaga                    | 44        | 1.37%   |
| Alcobendas                 | 42        | 1.31%   |
| Palma                      | 36        | 1.12%   |
| Valladolid                 | 32        | 1%      |
| Vigo                       | 31        | 0.96%   |
| Sabadell                   | 31        | 0.96%   |
| Bilbao                     | 27        | 0.84%   |
| Pamplona                   | 24        | 0.75%   |
| Córdoba                   | 24        | 0.75%   |
| Las Palmas de Gran Canaria | 23        | 0.72%   |
| Alicante                   | 23        | 0.72%   |
| Alcalá de Henares         | 23        | 0.72%   |
| Santiago de Compostela     | 22        | 0.68%   |
| Donostia / San Sebastian   | 22        | 0.68%   |
| Oviedo                     | 21        | 0.65%   |
| A Coruña                  | 20        | 0.62%   |
| Murcia                     | 19        | 0.59%   |
| León                      | 17        | 0.53%   |
| Burgos                     | 17        | 0.53%   |
| Mostoles                   | 16        | 0.5%    |
| Gijón                     | 16        | 0.5%    |
| Salamanca                  | 14        | 0.44%   |
| Reus                       | 14        | 0.44%   |
| Barakaldo                  | 14        | 0.44%   |
| Vitoria-Gasteiz            | 13        | 0.4%    |
| Ourense                    | 12        | 0.37%   |
| Getxo                      | 12        | 0.37%   |
| Almería                   | 12        | 0.37%   |
| Tarragona                  | 11        | 0.34%   |
| Santander                  | 11        | 0.34%   |
| Dos Hermanas               | 11        | 0.34%   |
| Cartagena                  | 11        | 0.34%   |
| Badalona                   | 11        | 0.34%   |
| Alcorcón                  | 11        | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 508       | 627    | 14.17%  |
| WDC                         | 381       | 471    | 10.63%  |
| Seagate                     | 364       | 432    | 10.16%  |
| Kingston                    | 364       | 459    | 10.16%  |
| Toshiba                     | 297       | 370    | 8.29%   |
| SanDisk                     | 238       | 310    | 6.64%   |
| Unknown                     | 178       | 235    | 4.97%   |
| SK hynix                    | 156       | 189    | 4.35%   |
| Hitachi                     | 128       | 151    | 3.57%   |
| Micron Technology           | 119       | 153    | 3.32%   |
| Intel                       | 119       | 163    | 3.32%   |
| HGST                        | 106       | 129    | 2.96%   |
| Crucial                     | 104       | 129    | 2.9%    |
| KIOXIA                      | 35        | 44     | 0.98%   |
| China                       | 35        | 52     | 0.98%   |
| Fujitsu                     | 33        | 37     | 0.92%   |
| Apple                       | 32        | 40     | 0.89%   |
| Phison                      | 31        | 33     | 0.86%   |
| Kingston Technology Company | 23        | 31     | 0.64%   |
| Phison Electronics          | 22        | 25     | 0.61%   |
| Netac                       | 18        | 29     | 0.5%    |
| Micron/Crucial Technology   | 18        | 20     | 0.5%    |
| LITEON                      | 16        | 17     | 0.45%   |
| KingSpec                    | 15        | 20     | 0.42%   |
| A-DATA Technology           | 13        | 15     | 0.36%   |
| JMicron Technology          | 12        | 12     | 0.33%   |
| Transcend                   | 9         | 15     | 0.25%   |
| PNY                         | 8         | 14     | 0.22%   |
| OCZ                         | 8         | 9      | 0.22%   |
| FORESEE                     | 8         | 12     | 0.22%   |
| Unknown                     | 8         | 8      | 0.22%   |
| USB30                       | 7         | 8      | 0.2%    |
| Teclast                     | 7         | 7      | 0.2%    |
| Silicon Motion              | 7         | 7      | 0.2%    |
| Emtec                       | 7         | 7      | 0.2%    |
| Patriot                     | 6         | 7      | 0.17%   |
| LITEONIT                    | 6         | 7      | 0.17%   |
| TCSUNBOW                    | 5         | 5      | 0.14%   |
| O2 Micro                    | 5         | 5      | 0.14%   |
| KingDian                    | 5         | 5      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 131       | 3.54%   |
| Kingston SA400S37480G 480GB SSD                     | 52        | 1.41%   |
| Seagate ST500LT012-1DG142 500GB                     | 43        | 1.16%   |
| Unknown MMC Card  32GB                              | 37        | 1%      |
| Seagate ST1000LM035-1RK172 1TB                      | 35        | 0.95%   |
| HGST HTS721010A9E630 1TB                            | 35        | 0.95%   |
| Unknown MMC Card  64GB                              | 34        | 0.92%   |
| Toshiba MQ01ABD100 1TB                              | 34        | 0.92%   |
| SK hynix NVMe SSD Drive 512GB                       | 34        | 0.92%   |
| Seagate ST9500325AS 500GB                           | 32        | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 32        | 0.87%   |
| Toshiba MQ01ABF050 500GB                            | 31        | 0.84%   |
| Samsung NVMe SSD Drive 512GB                        | 31        | 0.84%   |
| Toshiba MQ04ABF100 1TB                              | 28        | 0.76%   |
| SanDisk NVMe SSD Drive 512GB                        | 27        | 0.73%   |
| Toshiba MQ01ABD050 500GB                            | 22        | 0.59%   |
| Samsung SSD 850 EVO 250GB                           | 22        | 0.59%   |
| Samsung NVMe SSD Drive 256GB                        | 22        | 0.59%   |
| Unknown MMC Card  128GB                             | 21        | 0.57%   |
| SanDisk SSD PLUS 480GB                              | 21        | 0.57%   |
| Kingston SUV400S37240G 240GB SSD                    | 21        | 0.57%   |
| Kingston SA400S37120G 120GB SSD                     | 21        | 0.57%   |
| Intel NVMe SSD Drive 512GB                          | 21        | 0.57%   |
| HGST HTS545050A7E680 500GB                          | 21        | 0.57%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 20        | 0.54%   |
| Samsung SSD 860 EVO 500GB                           | 19        | 0.51%   |
| Kingston RBUSC180DS37256GJ 256GB SSD                | 19        | 0.51%   |
| HGST HTS541010A9E680 1TB                            | 18        | 0.49%   |
| SanDisk NVMe SSD Drive 256GB                        | 17        | 0.46%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 17        | 0.46%   |
| Samsung SSD 850 EVO 500GB                           | 16        | 0.43%   |
| Crucial CT500MX500SSD1 500GB                        | 16        | 0.43%   |
| Seagate ST1000LM049-2GH172 1TB                      | 15        | 0.41%   |
| Seagate Expansion 1TB                               | 15        | 0.41%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB   | 15        | 0.41%   |
| Kingston SA400S37960G 960GB SSD                     | 15        | 0.41%   |
| Micron NVMe SSD Drive 512GB                         | 13        | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 12        | 0.32%   |
| WDC WD3200BEVT-22ZCT0 320GB                         | 11        | 0.3%    |
| SK hynix NVMe SSD Drive 256GB                       | 11        | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 360       | 428    | 31.86%  |
| WDC                 | 244       | 292    | 21.59%  |
| Toshiba             | 195       | 237    | 17.26%  |
| Hitachi             | 128       | 151    | 11.33%  |
| HGST                | 106       | 129    | 9.38%   |
| Fujitsu             | 33        | 37     | 2.92%   |
| Samsung Electronics | 30        | 31     | 2.65%   |
| Unknown             | 8         | 11     | 0.71%   |
| JMicron Technology  | 7         | 7      | 0.62%   |
| Apple               | 4         | 4      | 0.35%   |
| USB3.0              | 3         | 3      | 0.27%   |
| ASMT                | 3         | 3      | 0.27%   |
| SSK                 | 2         | 2      | 0.18%   |
| USB                 | 1         | 1      | 0.09%   |
| PHD 3.0             | 1         | 1      | 0.09%   |
| OEM                 | 1         | 1      | 0.09%   |
| Maxone              | 1         | 1      | 0.09%   |
| LaCie               | 1         | 1      | 0.09%   |
| Inateck             | 1         | 1      | 0.09%   |
| IBM                 | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 314       | 398    | 27.35%  |
| Samsung Electronics | 194       | 240    | 16.9%   |
| SanDisk             | 119       | 146    | 10.37%  |
| Crucial             | 95        | 118    | 8.28%   |
| Toshiba             | 48        | 59     | 4.18%   |
| WDC                 | 44        | 59     | 3.83%   |
| SK hynix            | 37        | 40     | 3.22%   |
| China               | 35        | 52     | 3.05%   |
| Micron Technology   | 32        | 42     | 2.79%   |
| Intel               | 22        | 35     | 1.92%   |
| Netac               | 18        | 29     | 1.57%   |
| Apple               | 17        | 19     | 1.48%   |
| LITEON              | 15        | 15     | 1.31%   |
| KingSpec            | 15        | 20     | 1.31%   |
| A-DATA Technology   | 11        | 13     | 0.96%   |
| Transcend           | 8         | 14     | 0.7%    |
| OCZ                 | 8         | 9      | 0.7%    |
| FORESEE             | 8         | 12     | 0.7%    |
| USB30               | 7         | 8      | 0.61%   |
| Teclast             | 7         | 7      | 0.61%   |
| PNY                 | 6         | 12     | 0.52%   |
| LITEONIT            | 6         | 7      | 0.52%   |
| Emtec               | 6         | 6      | 0.52%   |
| Patriot             | 5         | 6      | 0.44%   |
| KingDian            | 4         | 4      | 0.35%   |
| Intenso             | 4         | 8      | 0.35%   |
| Corsair             | 4         | 5      | 0.35%   |
| Unknown             | 3         | 3      | 0.26%   |
| TCSUNBOW            | 3         | 3      | 0.26%   |
| KIOXIA-EXCERIA      | 3         | 4      | 0.26%   |
| Drevo               | 3         | 3      | 0.26%   |
| Dogfish             | 3         | 3      | 0.26%   |
| BAITITON            | 3         | 5      | 0.26%   |
| Unknown             | 3         | 3      | 0.26%   |
| ShanDianZhe         | 2         | 2      | 0.17%   |
| Plextor             | 2         | 3      | 0.17%   |
| Phison              | 2         | 2      | 0.17%   |
| Lexar               | 2         | 2      | 0.17%   |
| Yeyian              | 1         | 1      | 0.09%   |
| W800S               | 1         | 2      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1098      | 1342   | 32.06%  |
| SSD     | 1075      | 1459   | 31.39%  |
| NVMe    | 1040      | 1388   | 30.36%  |
| MMC     | 174       | 229    | 5.08%   |
| Unknown | 38        | 43     | 1.11%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1916      | 2705   | 58.95%  |
| NVMe | 1038      | 1383   | 31.94%  |
| MMC  | 174       | 229    | 5.35%   |
| SAS  | 122       | 144    | 3.75%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1552      | 2093   | 73.24%  |
| 0.51-1.0   | 521       | 649    | 24.59%  |
| 1.01-2.0   | 37        | 48     | 1.75%   |
| 3.01-4.0   | 5         | 6      | 0.24%   |
| 4.01-10.0  | 3         | 4      | 0.14%   |
| 2.01-3.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 956       | 30.91%  |
| 251-500        | 872       | 28.19%  |
| 501-1000       | 385       | 12.45%  |
| 1-20           | 226       | 7.31%   |
| 51-100         | 225       | 7.27%   |
| 1001-2000      | 147       | 4.75%   |
| 21-50          | 142       | 4.59%   |
| Unknown        | 64        | 2.07%   |
| 2001-3000      | 40        | 1.29%   |
| More than 3000 | 36        | 1.16%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1319      | 40.7%   |
| 21-50          | 612       | 18.88%  |
| 101-250        | 452       | 13.95%  |
| 51-100         | 376       | 11.6%   |
| 251-500        | 243       | 7.5%    |
| 501-1000       | 121       | 3.73%   |
| Unknown        | 64        | 1.97%   |
| 1001-2000      | 32        | 0.99%   |
| More than 3000 | 10        | 0.31%   |
| 2001-3000      | 10        | 0.31%   |
| 0              | 2         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 7         | 8      | 3.83%   |
| SanDisk SSD PLUS 480GB             | 6         | 7      | 3.28%   |
| HGST HTS545050A7E680 500GB         | 6         | 8      | 3.28%   |
| Seagate ST500LT012-1DG142 500GB    | 5         | 5      | 2.73%   |
| Seagate ST9500420AS 500GB          | 4         | 4      | 2.19%   |
| Seagate ST9250827AS 250GB          | 4         | 4      | 2.19%   |
| Seagate ST1000LM035-1RK172 1TB     | 4         | 4      | 2.19%   |
| Hitachi HTS545050A7E380 500GB      | 4         | 4      | 2.19%   |
| HGST HTS721010A9E630 1TB           | 4         | 4      | 2.19%   |
| China G521N256GB SSD               | 4         | 5      | 2.19%   |
| Seagate ST500LM021-1KJ152 500GB    | 3         | 3      | 1.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 3      | 1.64%   |
| Kingston SA400S37480G 480GB SSD    | 3         | 3      | 1.64%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 1.64%   |
| WDC WD5000BPVT-60HXZT3 500GB       | 2         | 2      | 1.09%   |
| Toshiba Q300. 240GB SSD            | 2         | 2      | 1.09%   |
| Toshiba MQ01ABD100 1TB             | 2         | 2      | 1.09%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 1.09%   |
| Toshiba MK5076GSX 500GB            | 2         | 2      | 1.09%   |
| Seagate ST9500420ASG 500GB         | 2         | 2      | 1.09%   |
| Seagate ST320LT012-9WS14C 320GB    | 2         | 2      | 1.09%   |
| Kingston SV300S37A120G 120GB SSD   | 2         | 2      | 1.09%   |
| Intel SSDSC2BF180A5H SED 180GB     | 2         | 2      | 1.09%   |
| Hitachi HTS723232A7A364 320GB      | 2         | 2      | 1.09%   |
| Hitachi HTS547550A9E384 500GB      | 2         | 2      | 1.09%   |
| Hitachi HTS545050B9A300 500GB      | 2         | 2      | 1.09%   |
| Hitachi HTS543232L9A300 320GB      | 2         | 3      | 1.09%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 2      | 1.09%   |
| HGST HTS545050A7E380 500GB         | 2         | 2      | 1.09%   |
| Fujitsu MHZ2250BH G2 250GB         | 2         | 2      | 1.09%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 1      | 0.55%   |
| WDC WD7500BPVT-60HXZT1 752GB       | 1         | 1      | 0.55%   |
| WDC WD6400BEVT-22A0RT0 640GB       | 1         | 1      | 0.55%   |
| WDC WD5000BEVT-22ZAT0 500GB        | 1         | 1      | 0.55%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 1      | 0.55%   |
| WDC WD3200BEVT-00A0RT0 320GB       | 1         | 1      | 0.55%   |
| WDC WD3200BEKT-60V5T1 320GB        | 1         | 1      | 0.55%   |
| WDC WD3200BEKT-60F3T1 320GB        | 1         | 2      | 0.55%   |
| WDC WD2500BEVS-60UST0 250GB        | 1         | 1      | 0.55%   |
| WDC WD2500BEVS-22UST0 250GB        | 1         | 1      | 0.55%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 50     | 26.23%  |
| Hitachi             | 24        | 26     | 13.11%  |
| Toshiba             | 23        | 25     | 12.57%  |
| WDC                 | 17        | 18     | 9.29%   |
| HGST                | 17        | 20     | 9.29%   |
| Samsung Electronics | 11        | 11     | 6.01%   |
| SanDisk             | 7         | 8      | 3.83%   |
| Kingston            | 7         | 8      | 3.83%   |
| Intel               | 6         | 6      | 3.28%   |
| Fujitsu             | 5         | 5      | 2.73%   |
| China               | 5         | 6      | 2.73%   |
| SK hynix            | 4         | 4      | 2.19%   |
| Crucial             | 4         | 6      | 2.19%   |
| Micron Technology   | 3         | 4      | 1.64%   |
| OCZ                 | 1         | 1      | 0.55%   |
| IBM                 | 1         | 1      | 0.55%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 50     | 35.56%  |
| Hitachi             | 24        | 26     | 17.78%  |
| Toshiba             | 18        | 20     | 13.33%  |
| HGST                | 17        | 20     | 12.59%  |
| WDC                 | 16        | 17     | 11.85%  |
| Samsung Electronics | 6         | 6      | 4.44%   |
| Fujitsu             | 5         | 5      | 3.7%    |
| IBM                 | 1         | 1      | 0.74%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 133       | 145    | 73.89%  |
| SSD  | 41        | 48     | 22.78%  |
| NVMe | 6         | 6      | 3.33%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1811      | 2792   | 58.04%  |
| Works    | 1130      | 1469   | 36.22%  |
| Malfunc  | 178       | 199    | 5.71%   |
| Failed   | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2023      | 59.1%   |
| AMD                              | 329       | 9.61%   |
| Samsung Electronics              | 315       | 9.2%    |
| SanDisk                          | 205       | 5.99%   |
| SK hynix                         | 113       | 3.3%    |
| Micron Technology                | 87        | 2.54%   |
| Kingston Technology Company      | 71        | 2.07%   |
| Phison Electronics               | 56        | 1.64%   |
| Toshiba America Info Systems     | 55        | 1.61%   |
| KIOXIA                           | 40        | 1.17%   |
| Nvidia                           | 27        | 0.79%   |
| Micron/Crucial Technology        | 24        | 0.7%    |
| Silicon Integrated Systems [SiS] | 14        | 0.41%   |
| Silicon Motion                   | 10        | 0.29%   |
| Apple                            | 10        | 0.29%   |
| VIA Technologies                 | 7         | 0.2%    |
| Union Memory (Shenzhen)          | 6         | 0.18%   |
| O2 Micro                         | 5         | 0.15%   |
| JMicron Technology               | 5         | 0.15%   |
| Solid State Storage Technology   | 4         | 0.12%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.09%   |
| Marvell Technology Group         | 2         | 0.06%   |
| Lite-On Technology               | 2         | 0.06%   |
| Lenovo                           | 2         | 0.06%   |
| ADATA Technology                 | 2         | 0.06%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| Silicon Image                    | 1         | 0.03%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Netac Technology                 | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 280       | 7.56%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 222       | 5.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 148       | 3.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 144       | 3.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 144       | 3.89%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 136       | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 135       | 3.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 116       | 3.13%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 100       | 2.7%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 91        | 2.46%   |
| Intel Volume Management Device NVMe RAID Controller                            | 86        | 2.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 84        | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 77        | 2.08%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 76        | 2.05%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 75        | 2.02%   |
| Samsung NVMe SSD Controller 980                                                | 72        | 1.94%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 70        | 1.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 68        | 1.83%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 61        | 1.65%   |
| Intel SSD 660P Series                                                          | 56        | 1.51%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 48        | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 41        | 1.11%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 40        | 1.08%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 40        | 1.08%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 39        | 1.05%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 37        | 1%      |
| Intel Tiger Lake-LP SATA Controller                                            | 37        | 1%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 35        | 0.94%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 33        | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 30        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 29        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                          | 29        | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 29        | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 28        | 0.76%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 28        | 0.76%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 27        | 0.73%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 27        | 0.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 0.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 26        | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 26        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2037      | 57.01%  |
| NVMe | 1047      | 29.3%   |
| IDE  | 252       | 7.05%   |
| RAID | 237       | 6.63%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2416      | 82.01%  |
| AMD          | 529       | 17.96%  |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 61        | 2.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 56        | 1.9%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 50        | 1.7%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 50        | 1.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 48        | 1.63%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 47        | 1.59%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 45        | 1.53%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 1.39%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 39        | 1.32%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 38        | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 37        | 1.26%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 37        | 1.26%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 35        | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 32        | 1.09%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 31        | 1.05%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 30        | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 1.02%   |
| AMD Custom APU 0405                           | 29        | 0.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 27        | 0.92%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 26        | 0.88%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 25        | 0.85%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 25        | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 24        | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 24        | 0.81%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 23        | 0.78%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 21        | 0.71%   |
| Intel 12th Gen Core i7-12700H                 | 21        | 0.71%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 20        | 0.68%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 19        | 0.64%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 19        | 0.64%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 19        | 0.64%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 18        | 0.61%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 18        | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 0.61%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.61%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.61%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 18        | 0.61%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 17        | 0.58%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 17        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 678       | 23.01%  |
| Intel Core i5           | 572       | 19.41%  |
| Other                   | 300       | 10.18%  |
| Intel Celeron           | 220       | 7.47%   |
| Intel Core i3           | 216       | 7.33%   |
| Intel Core 2 Duo        | 174       | 5.9%    |
| AMD Ryzen 7             | 146       | 4.95%   |
| AMD Ryzen 5             | 114       | 3.87%   |
| Intel Atom              | 104       | 3.53%   |
| Intel Pentium Dual-Core | 41        | 1.39%   |
| Intel Pentium           | 38        | 1.29%   |
| Intel Pentium Dual      | 31        | 1.05%   |
| AMD A4                  | 29        | 0.98%   |
| AMD A6                  | 28        | 0.95%   |
| Intel Core 2            | 26        | 0.88%   |
| Intel Genuine           | 23        | 0.78%   |
| AMD E1                  | 22        | 0.75%   |
| AMD A8                  | 18        | 0.61%   |
| AMD E                   | 14        | 0.48%   |
| AMD Ryzen 9             | 13        | 0.44%   |
| AMD Ryzen 3             | 12        | 0.41%   |
| AMD Ryzen 7 PRO         | 11        | 0.37%   |
| Intel Pentium M         | 9         | 0.31%   |
| Intel Core i9           | 9         | 0.31%   |
| Intel Celeron M         | 9         | 0.31%   |
| AMD Athlon              | 9         | 0.31%   |
| AMD A10                 | 9         | 0.31%   |
| Intel Core m3           | 5         | 0.17%   |
| AMD Turion 64 X2 Mobile | 5         | 0.17%   |
| Intel Pentium 4         | 4         | 0.14%   |
| AMD Turion II Dual-Core | 4         | 0.14%   |
| AMD FX                  | 4         | 0.14%   |
| AMD Athlon II           | 4         | 0.14%   |
| Intel Core m5           | 3         | 0.1%    |
| AMD Turion 64 Mobile    | 3         | 0.1%    |
| AMD Athlon X2           | 3         | 0.1%    |
| AMD A12                 | 3         | 0.1%    |
| Intel Xeon              | 2         | 0.07%   |
| Intel Pentium Silver    | 2         | 0.07%   |
| Intel Core M            | 2         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1441      | 48.85%  |
| 4       | 924       | 31.32%  |
| 6       | 213       | 7.22%   |
| 8       | 187       | 6.34%   |
| 1       | 120       | 4.07%   |
| 14      | 32        | 1.08%   |
| 10      | 15        | 0.51%   |
| 12      | 13        | 0.44%   |
| Unknown | 4         | 0.14%   |
| 24      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2945      | 99.97%  |
| 2      | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2091      | 70.91%  |
| 1       | 854       | 28.96%  |
| Unknown | 4         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2836      | 95.78%  |
| 32-bit         | 57        | 1.93%   |
| Unknown        | 54        | 1.82%   |
| 64-bit         | 14        | 0.47%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 663       | 21.7%   |
| 0x206a7    | 140       | 4.58%   |
| 0x306a9    | 119       | 3.89%   |
| 0x806c1    | 108       | 3.53%   |
| 0x806ea    | 100       | 3.27%   |
| 0x40651    | 100       | 3.27%   |
| 0x906ea    | 97        | 3.17%   |
| 0x806ec    | 92        | 3.01%   |
| 0x1067a    | 85        | 2.78%   |
| 0x406e3    | 81        | 2.65%   |
| 0x6fd      | 78        | 2.55%   |
| 0x806e9    | 77        | 2.52%   |
| 0x20655    | 77        | 2.52%   |
| 0x306d4    | 71        | 2.32%   |
| 0x306c3    | 61        | 2%      |
| 0x30678    | 52        | 1.7%    |
| 0x08108109 | 50        | 1.64%   |
| 0x0a50000c | 46        | 1.51%   |
| 0xa0652    | 42        | 1.37%   |
| 0x10676    | 41        | 1.34%   |
| 0x706e5    | 40        | 1.31%   |
| 0x06006705 | 37        | 1.21%   |
| 0x20652    | 36        | 1.18%   |
| 0x706a1    | 35        | 1.15%   |
| 0x506e3    | 35        | 1.15%   |
| 0x906a3    | 31        | 1.01%   |
| 0x106ca    | 31        | 1.01%   |
| 0x906e9    | 29        | 0.95%   |
| 0x08108102 | 29        | 0.95%   |
| 0x806eb    | 27        | 0.88%   |
| 0x08600106 | 27        | 0.88%   |
| 0x706a8    | 26        | 0.85%   |
| 0x506c9    | 25        | 0.82%   |
| 0x406c4    | 25        | 0.82%   |
| 0x806d1    | 24        | 0.79%   |
| 0x406c3    | 22        | 0.72%   |
| 0x08600104 | 21        | 0.69%   |
| 0x6f6      | 20        | 0.65%   |
| 0x08608103 | 20        | 0.65%   |
| 0x106c2    | 19        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 530       | 17.98%  |
| Haswell          | 220       | 7.47%   |
| SandyBridge      | 171       | 5.8%    |
| Penryn           | 159       | 5.4%    |
| TigerLake        | 151       | 5.12%   |
| Core             | 149       | 5.06%   |
| Skylake          | 141       | 4.78%   |
| IvyBridge        | 135       | 4.58%   |
| Westmere         | 127       | 4.31%   |
| Silvermont       | 118       | 4%      |
| Unknown          | 105       | 3.56%   |
| Broadwell        | 94        | 3.19%   |
| Zen+             | 91        | 3.09%   |
| Zen 2            | 79        | 2.68%   |
| Goldmont plus    | 77        | 2.61%   |
| Zen 3            | 71        | 2.41%   |
| Icelake          | 64        | 2.17%   |
| Bonnell          | 64        | 2.17%   |
| Excavator        | 63        | 2.14%   |
| CometLake        | 62        | 2.1%    |
| Alderlake Hybrid | 41        | 1.39%   |
| Goldmont         | 31        | 1.05%   |
| P6               | 28        | 0.95%   |
| Puma             | 27        | 0.92%   |
| Zen              | 26        | 0.88%   |
| Jaguar           | 24        | 0.81%   |
| Bobcat           | 23        | 0.78%   |
| K8 Hammer        | 16        | 0.54%   |
| K10              | 15        | 0.51%   |
| Tremont          | 11        | 0.37%   |
| Nehalem          | 9         | 0.31%   |
| Piledriver       | 8         | 0.27%   |
| Steamroller      | 5         | 0.17%   |
| NetBurst         | 5         | 0.17%   |
| K10 Llano        | 4         | 0.14%   |
| K8 & K10 hybrid  | 3         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2155      | 57.16%  |
| Nvidia                           | 875       | 23.21%  |
| AMD                              | 724       | 19.2%   |
| Silicon Integrated Systems [SiS] | 9         | 0.24%   |
| VIA Technologies                 | 7         | 0.19%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 155       | 3.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 144       | 3.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 130       | 3.33%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 130       | 3.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 123       | 3.15%   |
| Intel UHD Graphics 620                                                                   | 111       | 2.84%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 99        | 2.54%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 97        | 2.48%   |
| Intel HD Graphics 620                                                                    | 88        | 2.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 86        | 2.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 85        | 2.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 83        | 2.13%   |
| Intel HD Graphics 5500                                                                   | 78        | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 78        | 2%      |
| AMD Renoir                                                                               | 76        | 1.95%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 75        | 1.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 66        | 1.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 64        | 1.64%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 64        | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 63        | 1.61%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 52        | 1.33%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 52        | 1.33%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 52        | 1.33%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 50        | 1.28%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 48        | 1.23%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 47        | 1.2%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 44        | 1.13%   |
| Intel HD Graphics 530                                                                    | 44        | 1.13%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 43        | 1.1%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 38        | 0.97%   |
| Intel HD Graphics 630                                                                    | 35        | 0.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 34        | 0.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 32        | 0.82%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 31        | 0.79%   |
| AMD Lucienne                                                                             | 31        | 0.79%   |
| Intel HD Graphics 500                                                                    | 29        | 0.74%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 29        | 0.74%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 28        | 0.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 27        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1418      | 47.99%  |
| Intel + Nvidia | 630       | 21.32%  |
| 1 x AMD        | 488       | 16.51%  |
| 1 x Nvidia     | 151       | 5.11%   |
| Intel + AMD    | 96        | 3.25%   |
| AMD + Nvidia   | 94        | 3.18%   |
| 2 x AMD        | 45        | 1.52%   |
| 2 x Intel      | 10        | 0.34%   |
| 1 x SiS        | 9         | 0.3%    |
| 1 x VIA        | 7         | 0.24%   |
| 2 x Nvidia     | 4         | 0.14%   |
| Other          | 3         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2480      | 83.11%  |
| Proprietary | 409       | 13.71%  |
| Unknown     | 95        | 3.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1865      | 61.65%  |
| 0.01-0.5   | 384       | 12.69%  |
| 1.01-2.0   | 341       | 11.27%  |
| 3.01-4.0   | 195       | 6.45%   |
| 0.51-1.0   | 163       | 5.39%   |
| 5.01-6.0   | 41        | 1.36%   |
| 7.01-8.0   | 29        | 0.96%   |
| 2.01-3.0   | 4         | 0.13%   |
| 8.01-16.0  | 3         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 563       | 17.07%  |
| Chimei Innolux          | 516       | 15.65%  |
| LG Display              | 440       | 13.34%  |
| BOE                     | 400       | 12.13%  |
| Samsung Electronics     | 308       | 9.34%   |
| Chi Mei Optoelectronics | 91        | 2.76%   |
| Sharp                   | 90        | 2.73%   |
| Goldstar                | 86        | 2.61%   |
| Dell                    | 81        | 2.46%   |
| Apple                   | 76        | 2.3%    |
| PANDA                   | 69        | 2.09%   |
| Hewlett-Packard         | 67        | 2.03%   |
| BenQ                    | 50        | 1.52%   |
| Lenovo                  | 45        | 1.36%   |
| LG Philips              | 44        | 1.33%   |
| Philips                 | 29        | 0.88%   |
| Acer                    | 29        | 0.88%   |
| AOC                     | 24        | 0.73%   |
| Ancor Communications    | 24        | 0.73%   |
| HannStar                | 21        | 0.64%   |
| Valve                   | 20        | 0.61%   |
| Sony                    | 19        | 0.58%   |
| InfoVision              | 18        | 0.55%   |
| ASUSTek Computer        | 16        | 0.49%   |
| CPT                     | 15        | 0.45%   |
| CSO                     | 12        | 0.36%   |
| Quanta Display          | 8         | 0.24%   |
| ViewSonic               | 7         | 0.21%   |
| TMX                     | 7         | 0.21%   |
| MSI                     | 7         | 0.21%   |
| Analogix                | 7         | 0.21%   |
| Unknown                 | 6         | 0.18%   |
| Mi                      | 6         | 0.18%   |
| Seiko/Epson             | 5         | 0.15%   |
| Panasonic               | 5         | 0.15%   |
| NEC Computers           | 4         | 0.12%   |
| AGO                     | 4         | 0.12%   |
| Toshiba                 | 3         | 0.09%   |
| MStar                   | 3         | 0.09%   |
| Iiyama                  | 3         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 66        | 1.98%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 39        | 1.17%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 32        | 0.96%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 31        | 0.93%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 31        | 0.93%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 22        | 0.66%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.63%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 20        | 0.6%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 20        | 0.6%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 18        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 18        | 0.54%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.54%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.51%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 16        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 16        | 0.48%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 16        | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 15        | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 15        | 0.45%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 15        | 0.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 15        | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 14        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 14        | 0.42%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 13        | 0.39%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 13        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 13        | 0.39%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 13        | 0.39%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.39%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 13        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 12        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.36%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 12        | 0.36%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 11        | 0.33%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 11        | 0.33%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 11        | 0.33%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 11        | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 11        | 0.33%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 10        | 0.3%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 10        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch         | 10        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1254      | 40.9%   |
| 1366x768 (WXGA)    | 988       | 32.22%  |
| 1280x800 (WXGA)    | 170       | 5.54%   |
| 3840x2160 (4K)     | 90        | 2.94%   |
| 1600x900 (HD+)     | 79        | 2.58%   |
| 2560x1440 (QHD)    | 64        | 2.09%   |
| 1440x900 (WXGA+)   | 64        | 2.09%   |
| 1024x600           | 44        | 1.44%   |
| 1920x1200 (WUXGA)  | 40        | 1.3%    |
| 2560x1600          | 32        | 1.04%   |
| 1280x1024 (SXGA)   | 32        | 1.04%   |
| 2160x1440          | 27        | 0.88%   |
| 1680x1050 (WSXGA+) | 27        | 0.88%   |
| 800x1280           | 26        | 0.85%   |
| 2880x1800          | 18        | 0.59%   |
| 3440x1440          | 16        | 0.52%   |
| 2560x1080          | 14        | 0.46%   |
| 3200x1800 (QHD+)   | 8         | 0.26%   |
| 1024x768 (XGA)     | 8         | 0.26%   |
| 1360x768           | 7         | 0.23%   |
| 3840x2400          | 6         | 0.2%    |
| Unknown            | 5         | 0.16%   |
| 3072x1920          | 3         | 0.1%    |
| 2520x1680          | 3         | 0.1%    |
| 2288x1287          | 3         | 0.1%    |
| 1920x540           | 3         | 0.1%    |
| 1920x1280          | 3         | 0.1%    |
| 1600x1200          | 3         | 0.1%    |
| 1400x1050          | 3         | 0.1%    |
| 1280x768           | 3         | 0.1%    |
| 3840x1600          | 2         | 0.07%   |
| 3840x1080          | 2         | 0.07%   |
| 3456x2160          | 2         | 0.07%   |
| 3200x2000          | 2         | 0.07%   |
| 2304x1440          | 2         | 0.07%   |
| 5760x1080          | 1         | 0.03%   |
| 3200x1080          | 1         | 0.03%   |
| 3000x2000          | 1         | 0.03%   |
| 2880x1920          | 1         | 0.03%   |
| 2736x1824          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1589      | 48.17%  |
| 13      | 374       | 11.34%  |
| 14      | 276       | 8.37%   |
| 17      | 179       | 5.43%   |
| 24      | 117       | 3.55%   |
| 27      | 100       | 3.03%   |
| 21      | 89        | 2.7%    |
| 23      | 86        | 2.61%   |
| 12      | 63        | 1.91%   |
| 16      | 53        | 1.61%   |
| 11      | 53        | 1.61%   |
| 10      | 51        | 1.55%   |
| Unknown | 38        | 1.15%   |
| 34      | 30        | 0.91%   |
| 31      | 28        | 0.85%   |
| 19      | 24        | 0.73%   |
| 7       | 20        | 0.61%   |
| 18      | 17        | 0.52%   |
| 84      | 16        | 0.48%   |
| 20      | 14        | 0.42%   |
| 22      | 9         | 0.27%   |
| 72      | 8         | 0.24%   |
| 25      | 8         | 0.24%   |
| 54      | 7         | 0.21%   |
| 40      | 7         | 0.21%   |
| 3       | 7         | 0.21%   |
| 26      | 5         | 0.15%   |
| 52      | 4         | 0.12%   |
| 46      | 3         | 0.09%   |
| 38      | 3         | 0.09%   |
| 32      | 3         | 0.09%   |
| 8       | 3         | 0.09%   |
| 142     | 2         | 0.06%   |
| 37      | 2         | 0.06%   |
| 35      | 2         | 0.06%   |
| 65      | 1         | 0.03%   |
| 57      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |
| 47      | 1         | 0.03%   |
| 42      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2022      | 61.91%  |
| 201-300        | 394       | 12.06%  |
| 501-600        | 290       | 8.88%   |
| 351-400        | 226       | 6.92%   |
| 401-500        | 138       | 4.23%   |
| Unknown        | 38        | 1.16%   |
| 601-700        | 36        | 1.1%    |
| 701-800        | 33        | 1.01%   |
| 1-100          | 27        | 0.83%   |
| 1501-2000      | 24        | 0.73%   |
| 1001-1500      | 18        | 0.55%   |
| 801-900        | 14        | 0.43%   |
| 101-200        | 3         | 0.09%   |
| More than 2000 | 2         | 0.06%   |
| 901-1000       | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2346      | 80.98%  |
| 16/10   | 365       | 12.6%   |
| 3/2     | 44        | 1.52%   |
| 21/9    | 32        | 1.1%    |
| 5/4     | 31        | 1.07%   |
| Unknown | 29        | 1%      |
| 0.67    | 20        | 0.69%   |
| 4/3     | 17        | 0.59%   |
| 6/5     | 7         | 0.24%   |
| 1.00    | 2         | 0.07%   |
| 32/9    | 1         | 0.03%   |
| 1.03    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1604      | 48.77%  |
| 81-90          | 476       | 14.47%  |
| 201-250        | 251       | 7.63%   |
| 71-80          | 169       | 5.14%   |
| 121-130        | 128       | 3.89%   |
| 301-350        | 102       | 3.1%    |
| 351-500        | 62        | 1.89%   |
| 151-200        | 61        | 1.85%   |
| 61-70          | 59        | 1.79%   |
| 51-60          | 53        | 1.61%   |
| 41-50          | 51        | 1.55%   |
| More than 1000 | 40        | 1.22%   |
| Unknown        | 38        | 1.16%   |
| 131-140        | 36        | 1.09%   |
| 141-150        | 32        | 0.97%   |
| 251-300        | 31        | 0.94%   |
| 1-40           | 30        | 0.91%   |
| 111-120        | 30        | 0.91%   |
| 501-1000       | 18        | 0.55%   |
| 91-100         | 18        | 0.55%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1166      | 36.19%  |
| 101-120       | 1042      | 32.34%  |
| 51-100        | 631       | 19.58%  |
| 161-240       | 232       | 7.2%    |
| More than 240 | 74        | 2.3%    |
| 1-50          | 39        | 1.21%   |
| Unknown       | 38        | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2367      | 78.27%  |
| 2     | 483       | 15.97%  |
| 0     | 103       | 3.41%   |
| 3     | 65        | 2.15%   |
| 4     | 5         | 0.17%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1650      | 34.69%  |
| Intel                             | 1392      | 29.27%  |
| Qualcomm Atheros                  | 727       | 15.29%  |
| Broadcom                          | 359       | 7.55%   |
| Broadcom Limited                  | 79        | 1.66%   |
| Marvell Technology Group          | 74        | 1.56%   |
| MediaTek                          | 64        | 1.35%   |
| TP-Link                           | 50        | 1.05%   |
| Ralink                            | 47        | 0.99%   |
| Ralink Technology                 | 36        | 0.76%   |
| ASIX Electronics                  | 29        | 0.61%   |
| Xiaomi                            | 22        | 0.46%   |
| Nvidia                            | 20        | 0.42%   |
| Samsung Electronics               | 18        | 0.38%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.29%   |
| Lenovo                            | 14        | 0.29%   |
| JMicron Technology                | 14        | 0.29%   |
| Dell                              | 14        | 0.29%   |
| Ericsson Business Mobile Networks | 13        | 0.27%   |
| Hewlett-Packard                   | 12        | 0.25%   |
| Sierra Wireless                   | 10        | 0.21%   |
| Qualcomm                          | 10        | 0.21%   |
| DisplayLink                       | 10        | 0.21%   |
| Qualcomm Atheros Communications   | 9         | 0.19%   |
| Huawei Technologies               | 7         | 0.15%   |
| D-Link                            | 7         | 0.15%   |
| VIA Technologies                  | 6         | 0.13%   |
| ASUSTek Computer                  | 5         | 0.11%   |
| LSI                               | 4         | 0.08%   |
| Edimax Technology                 | 4         | 0.08%   |
| Attansic Technology               | 4         | 0.08%   |
| Toshiba                           | 3         | 0.06%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.04%   |
| NetGear                           | 2         | 0.04%   |
| Google                            | 2         | 0.04%   |
| Fibocom                           | 2         | 0.04%   |
| D-Link System                     | 2         | 0.04%   |
| Arduino SA                        | 2         | 0.04%   |
| Accton Technology                 | 2         | 0.04%   |
| T & A Mobile Phones               | 1         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 937       | 16.77%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 287       | 5.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 134       | 2.4%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 129       | 2.31%   |
| Intel Wi-Fi 6 AX200                                                     | 124       | 2.22%   |
| Intel Wi-Fi 6 AX201                                                     | 112       | 2%      |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 109       | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 104       | 1.86%   |
| Intel Wireless 8265 / 8275                                              | 103       | 1.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 102       | 1.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 101       | 1.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 86        | 1.54%   |
| Intel Wireless 7265                                                     | 82        | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 79        | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 68        | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 63        | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 1.13%   |
| Intel Wireless 7260                                                     | 63        | 1.13%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 59        | 1.06%   |
| Intel Wireless 3165                                                     | 57        | 1.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 55        | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 55        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 53        | 0.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 51        | 0.91%   |
| Intel WiFi Link 5100                                                    | 47        | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 46        | 0.82%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 43        | 0.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 42        | 0.75%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 40        | 0.72%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 0.7%    |
| Intel Wireless 8260                                                     | 37        | 0.66%   |
| Intel Wireless 3160                                                     | 37        | 0.66%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 36        | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 0.64%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 34        | 0.61%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 33        | 0.59%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 29        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 29        | 0.52%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 28        | 0.5%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1345      | 43.91%  |
| Qualcomm Atheros                  | 610       | 19.92%  |
| Realtek Semiconductor             | 565       | 18.45%  |
| Broadcom                          | 243       | 7.93%   |
| MediaTek                          | 61        | 1.99%   |
| Broadcom Limited                  | 54        | 1.76%   |
| Ralink                            | 47        | 1.53%   |
| Ralink Technology                 | 36        | 1.18%   |
| TP-Link                           | 34        | 1.11%   |
| Sierra Wireless                   | 10        | 0.33%   |
| Qualcomm Atheros Communications   | 9         | 0.29%   |
| Dell                              | 8         | 0.26%   |
| D-Link                            | 7         | 0.23%   |
| ASUSTek Computer                  | 5         | 0.16%   |
| Qualcomm                          | 4         | 0.13%   |
| Hewlett-Packard                   | 4         | 0.13%   |
| Ericsson Business Mobile Networks | 4         | 0.13%   |
| Edimax Technology                 | 4         | 0.13%   |
| NetGear                           | 2         | 0.07%   |
| Fibocom                           | 2         | 0.07%   |
| D-Link System                     | 2         | 0.07%   |
| Accton Technology                 | 2         | 0.07%   |
| Sitecom Europe                    | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| Gemtek                            | 1         | 0.03%   |
| Belkin Components                 | 1         | 0.03%   |
| AirTies Wireless Networks         | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 134       | 4.35%   |
| Intel Wi-Fi 6 AX200                                                     | 124       | 4.03%   |
| Intel Wi-Fi 6 AX201                                                     | 112       | 3.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 109       | 3.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 104       | 3.38%   |
| Intel Wireless 8265 / 8275                                              | 103       | 3.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 102       | 3.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 101       | 3.28%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 86        | 2.79%   |
| Intel Wireless 7265                                                     | 82        | 2.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 79        | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 68        | 2.21%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 63        | 2.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 63        | 2.05%   |
| Intel Wireless 7260                                                     | 63        | 2.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 59        | 1.92%   |
| Intel Wireless 3165                                                     | 57        | 1.85%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 55        | 1.79%   |
| Broadcom BCM43142 802.11b/g/n                                           | 53        | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 51        | 1.66%   |
| Intel WiFi Link 5100                                                    | 47        | 1.53%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 46        | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 43        | 1.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 42        | 1.36%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 40        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                          | 39        | 1.27%   |
| Intel Wireless 8260                                                     | 37        | 1.2%    |
| Intel Wireless 3160                                                     | 37        | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 36        | 1.17%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 36        | 1.17%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 29        | 0.94%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 28        | 0.91%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 0.91%   |
| Intel Centrino Advanced-N 6200                                          | 28        | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 27        | 0.88%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 25        | 0.81%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 25        | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 24        | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 24        | 0.78%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 22        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1401      | 57.82%  |
| Intel                                  | 373       | 15.39%  |
| Qualcomm Atheros                       | 196       | 8.09%   |
| Broadcom                               | 160       | 6.6%    |
| Marvell Technology Group               | 74        | 3.05%   |
| ASIX Electronics                       | 29        | 1.2%    |
| Broadcom Limited                       | 27        | 1.11%   |
| Xiaomi                                 | 22        | 0.91%   |
| Nvidia                                 | 20        | 0.83%   |
| TP-Link                                | 17        | 0.7%    |
| Silicon Integrated Systems [SiS]       | 14        | 0.58%   |
| Lenovo                                 | 14        | 0.58%   |
| JMicron Technology                     | 14        | 0.58%   |
| Samsung Electronics                    | 11        | 0.45%   |
| DisplayLink                            | 10        | 0.41%   |
| VIA Technologies                       | 6         | 0.25%   |
| Qualcomm                               | 6         | 0.25%   |
| LSI                                    | 4         | 0.17%   |
| Hewlett-Packard                        | 4         | 0.17%   |
| Attansic Technology                    | 4         | 0.17%   |
| MediaTek                               | 3         | 0.12%   |
| Huawei Technologies                    | 3         | 0.12%   |
| Google                                 | 2         | 0.08%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| OPPO Electronics                       | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| National Semiconductor                 | 1         | 0.04%   |
| Microchip Technology                   | 1         | 0.04%   |
| Davicom Semiconductor                  | 1         | 0.04%   |
| Apple                                  | 1         | 0.04%   |
| ADMtek                                 | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 937       | 38.17%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 287       | 11.69%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 129       | 5.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 55        | 2.24%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 34        | 1.38%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 33        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29        | 1.18%   |
| ASIX AX88179 Gigabit Ethernet                                     | 27        | 1.1%    |
| Intel 82577LM Gigabit Network Connection                          | 26        | 1.06%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 25        | 1.02%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 23        | 0.94%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                             | 22        | 0.9%    |
| Intel Ethernet Connection (3) I218-LM                             | 22        | 0.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 20        | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 18        | 0.73%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 18        | 0.73%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 17        | 0.69%   |
| Intel Ethernet Connection (13) I219-V                             | 17        | 0.69%   |
| Intel 82567LM Gigabit Network Connection                          | 17        | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 16        | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 16        | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 16        | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 15        | 0.61%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.61%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.61%   |
| Nvidia MCP79 Ethernet                                             | 15        | 0.61%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 14        | 0.57%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 14        | 0.57%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 12        | 0.49%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 0.49%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.49%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 0.49%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.49%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 11        | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2885      | 54.59%  |
| Ethernet | 2347      | 44.41%  |
| Modem    | 49        | 0.93%   |
| Unknown  | 4         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2349      | 75.29%  |
| Ethernet | 771       | 24.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2105      | 71.4%   |
| 1     | 767       | 26.02%  |
| 0     | 61        | 2.07%   |
| 3     | 14        | 0.47%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2845      | 95.82%  |
| Yes  | 124       | 4.18%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1022      | 45.99%  |
| Realtek Semiconductor           | 273       | 12.29%  |
| IMC Networks                    | 177       | 7.97%   |
| Qualcomm Atheros Communications | 146       | 6.57%   |
| Lite-On Technology              | 101       | 4.55%   |
| Foxconn / Hon Hai               | 100       | 4.5%    |
| Broadcom                        | 94        | 4.23%   |
| Apple                           | 66        | 2.97%   |
| Realtek                         | 42        | 1.89%   |
| Toshiba                         | 39        | 1.76%   |
| Cambridge Silicon Radio         | 38        | 1.71%   |
| Dell                            | 28        | 1.26%   |
| Hewlett-Packard                 | 24        | 1.08%   |
| Ralink                          | 19        | 0.86%   |
| ASUSTek Computer                | 17        | 0.77%   |
| Alps Electric                   | 14        | 0.63%   |
| Foxconn International           | 9         | 0.41%   |
| Ralink Technology               | 4         | 0.18%   |
| Taiyo Yuden                     | 2         | 0.09%   |
| MediaTek                        | 2         | 0.09%   |
| Askey Computer                  | 2         | 0.09%   |
| ISSC                            | 1         | 0.05%   |
| Chicony Electronics             | 1         | 0.05%   |
| Actions                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 373       | 16.79%  |
| Intel AX201 Bluetooth                               | 216       | 9.72%   |
| Realtek Bluetooth Radio                             | 185       | 8.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 185       | 8.33%   |
| Intel AX200 Bluetooth                               | 122       | 5.49%   |
| IMC Networks Bluetooth Radio                        | 92        | 4.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 60        | 2.7%    |
| Realtek  Bluetooth 4.2 Adapter                      | 54        | 2.43%   |
| IMC Networks Bluetooth Device                       | 42        | 1.89%   |
| Foxconn / Hon Hai Bluetooth Device                  | 41        | 1.85%   |
| Apple Bluetooth Host Controller                     | 40        | 1.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 38        | 1.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 33        | 1.49%   |
| Realtek 802.11ac WLAN Adapter                       | 32        | 1.44%   |
| Intel Bluetooth Device                              | 30        | 1.35%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 29        | 1.31%   |
| IMC Networks Wireless_Device                        | 27        | 1.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 26        | 1.17%   |
| Lite-On Atheros AR3012 Bluetooth                    | 26        | 1.17%   |
| Lite-On Bluetooth Device                            | 25        | 1.13%   |
| Intel AX210 Bluetooth                               | 24        | 1.08%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 0.95%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 0.95%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 0.86%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 18        | 0.81%   |
| Apple Bluetooth USB Host Controller                 | 17        | 0.77%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 15        | 0.68%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 15        | 0.68%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.63%   |
| HP Broadcom 2070 Bluetooth Combo                    | 12        | 0.54%   |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.5%    |
| Realtek RTL8723B Bluetooth                          | 11        | 0.5%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 0.5%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 11        | 0.5%    |
| Realtek RTL8821A Bluetooth                          | 10        | 0.45%   |
| Realtek Bluetooth Radio                             | 10        | 0.45%   |
| Broadcom BCM2045 Bluetooth                          | 10        | 0.45%   |
| Foxconn International BCM43142A0 Bluetooth module   | 9         | 0.41%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2327      | 65.16%  |
| AMD                                  | 619       | 17.33%  |
| Nvidia                               | 415       | 11.62%  |
| C-Media Electronics                  | 24        | 0.67%   |
| Logitech                             | 19        | 0.53%   |
| Lenovo                               | 15        | 0.42%   |
| Silicon Integrated Systems [SiS]     | 14        | 0.39%   |
| Plantronics                          | 11        | 0.31%   |
| GN Netcom                            | 11        | 0.31%   |
| VIA Technologies                     | 7         | 0.2%    |
| Realtek Semiconductor                | 7         | 0.2%    |
| JMTek                                | 7         | 0.2%    |
| Texas Instruments                    | 6         | 0.17%   |
| Kingston Technology                  | 5         | 0.14%   |
| Generalplus Technology               | 5         | 0.14%   |
| ASUSTek Computer                     | 5         | 0.14%   |
| Apple                                | 5         | 0.14%   |
| SteelSeries ApS                      | 4         | 0.11%   |
| Corsair                              | 4         | 0.11%   |
| BEHRINGER International              | 4         | 0.11%   |
| Sennheiser Communications            | 3         | 0.08%   |
| Hewlett-Packard                      | 3         | 0.08%   |
| Creative Technology                  | 3         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.06%   |
| Sony                                 | 2         | 0.06%   |
| No brand                             | 2         | 0.06%   |
| Huawei Technologies                  | 2         | 0.06%   |
| Guillemot                            | 2         | 0.06%   |
| Conexant Systems                     | 2         | 0.06%   |
| CMX Systems                          | 2         | 0.06%   |
| Blue Microphones                     | 2         | 0.06%   |
| Alesis                               | 2         | 0.06%   |
| Vestax                               | 1         | 0.03%   |
| Veho                                 | 1         | 0.03%   |
| Trust                                | 1         | 0.03%   |
| ThrustMaster                         | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |
| Signalpath International             | 1         | 0.03%   |
| Samsung Electronics                  | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 303       | 7.03%   |
| Intel Sunrise Point-LP HD Audio                                            | 301       | 6.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 164       | 3.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 154       | 3.57%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 151       | 3.5%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 142       | 3.29%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 137       | 3.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 136       | 3.15%   |
| Intel Haswell-ULT HD Audio Controller                                      | 131       | 3.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 131       | 3.04%   |
| Intel 8 Series HD Audio Controller                                         | 131       | 3.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 108       | 2.5%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 101       | 2.34%   |
| Intel Comet Lake PCH-LP cAVS                                               | 94        | 2.18%   |
| Intel Broadwell-U Audio Controller                                         | 94        | 2.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 93        | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 89        | 2.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 89        | 2.06%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 77        | 1.79%   |
| AMD FCH Azalia Controller                                                  | 76        | 1.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 75        | 1.74%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 67        | 1.55%   |
| AMD Kabini HDMI/DP Audio                                                   | 62        | 1.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 62        | 1.44%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 59        | 1.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 54        | 1.25%   |
| Intel Comet Lake PCH cAVS                                                  | 53        | 1.23%   |
| AMD High Definition Audio Controller                                       | 52        | 1.21%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 51        | 1.18%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 46        | 1.07%   |
| Nvidia GA106 High Definition Audio Controller                              | 44        | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 43        | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 40        | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 40        | 0.93%   |
| Intel CM238 HD Audio Controller                                            | 38        | 0.88%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 38        | 0.88%   |
| Nvidia GP107GL High Definition Audio Controller                            | 37        | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                              | 32        | 0.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 31        | 0.72%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 30        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 547       | 30.29%  |
| SK hynix                                         | 383       | 21.21%  |
| Micron Technology                                | 230       | 12.74%  |
| Kingston                                         | 167       | 9.25%   |
| Unknown                                          | 136       | 7.53%   |
| Crucial                                          | 93        | 5.15%   |
| Ramaxel Technology                               | 60        | 3.32%   |
| Elpida                                           | 29        | 1.61%   |
| Unknown (ABCD)                                   | 26        | 1.44%   |
| A-DATA Technology                                | 21        | 1.16%   |
| Corsair                                          | 18        | 1%      |
| Nanya Technology                                 | 17        | 0.94%   |
| G.Skill                                          | 11        | 0.61%   |
| Silicon Power                                    | 10        | 0.55%   |
| Unknown                                          | 8         | 0.44%   |
| GOODRAM                                          | 6         | 0.33%   |
| Transcend                                        | 5         | 0.28%   |
| Wilk                                             | 3         | 0.17%   |
| Apacer                                           | 3         | 0.17%   |
| Toshiba                                          | 2         | 0.11%   |
| Timetec                                          | 2         | 0.11%   |
| SHARETRONIC                                      | 2         | 0.11%   |
| Patriot                                          | 2         | 0.11%   |
| KomputerBay                                      | 2         | 0.11%   |
| ChangXin Memory                                  | 2         | 0.11%   |
| Avant                                            | 2         | 0.11%   |
| Unknown (0x202020202020202020202020202020202020) | 1         | 0.06%   |
| Unifosa                                          | 1         | 0.06%   |
| Team                                             | 1         | 0.06%   |
| Qimonda                                          | 1         | 0.06%   |
| PUSKILL                                          | 1         | 0.06%   |
| PNY                                              | 1         | 0.06%   |
| Patriot Memory (PDP Systems)                     | 1         | 0.06%   |
| Netlist                                          | 1         | 0.06%   |
| Netac                                            | 1         | 0.06%   |
| Neo Forza                                        | 1         | 0.06%   |
| Micron/Elpida                                    | 1         | 0.06%   |
| Kllisre                                          | 1         | 0.06%   |
| Kembona                                          | 1         | 0.06%   |
| ff                                               | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 32        | 1.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 31        | 1.64%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 26        | 1.38%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 23        | 1.22%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 22        | 1.17%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 22        | 1.17%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 20        | 1.06%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 20        | 1.06%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 18        | 0.95%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.95%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 0.9%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 0.9%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 0.9%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 16        | 0.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 16        | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 0.79%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 15        | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 0.74%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 14        | 0.74%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.74%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.69%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 12        | 0.64%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 12        | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.64%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 12        | 0.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 0.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.64%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.58%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.58%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.58%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.58%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 10        | 0.53%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.53%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.53%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.53%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 10        | 0.53%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 10        | 0.53%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 10        | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 10        | 0.53%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 10        | 0.53%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 756       | 49.19%  |
| DDR3    | 459       | 29.86%  |
| DDR2    | 93        | 6.05%   |
| LPDDR4  | 84        | 5.47%   |
| LPDDR3  | 53        | 3.45%   |
| SDRAM   | 35        | 2.28%   |
| DDR5    | 23        | 1.5%    |
| Unknown | 11        | 0.72%   |
| LPDDR5  | 9         | 0.59%   |
| DDR     | 8         | 0.52%   |
| DRAM    | 6         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1368      | 88.32%  |
| Row Of Chips | 161       | 10.39%  |
| DIMM         | 10        | 0.65%   |
| Chip         | 8         | 0.52%   |
| Unknown      | 2         | 0.13%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 678       | 40.55%  |
| 4096  | 443       | 26.5%   |
| 16384 | 258       | 15.43%  |
| 2048  | 190       | 11.36%  |
| 1024  | 63        | 3.77%   |
| 32768 | 31        | 1.85%   |
| 512   | 5         | 0.3%    |
| 256   | 3         | 0.18%   |
| 3072  | 1         | 0.06%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 342       | 20.7%   |
| 3200    | 328       | 19.85%  |
| 1600    | 308       | 18.64%  |
| 2400    | 113       | 6.84%   |
| 1334    | 77        | 4.66%   |
| 2133    | 73        | 4.42%   |
| 667     | 66        | 4%      |
| 1333    | 55        | 3.33%   |
| Unknown | 41        | 2.48%   |
| 8400    | 32        | 1.94%   |
| 4267    | 30        | 1.82%   |
| 1067    | 26        | 1.57%   |
| 4800    | 24        | 1.45%   |
| 1867    | 18        | 1.09%   |
| 800     | 18        | 1.09%   |
| 3266    | 17        | 1.03%   |
| 2048    | 13        | 0.79%   |
| 533     | 12        | 0.73%   |
| 4199    | 11        | 0.67%   |
| 6400    | 10        | 0.61%   |
| 1066    | 8         | 0.48%   |
| 4266    | 7         | 0.42%   |
| 975     | 6         | 0.36%   |
| 3733    | 3         | 0.18%   |
| 2933    | 2         | 0.12%   |
| 1639    | 2         | 0.12%   |
| 1200    | 2         | 0.12%   |
| 5600    | 1         | 0.06%   |
| 3600    | 1         | 0.06%   |
| 3000    | 1         | 0.06%   |
| 1866    | 1         | 0.06%   |
| 1776    | 1         | 0.06%   |
| 666     | 1         | 0.06%   |
| 333     | 1         | 0.06%   |
| 266     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 14        | 51.85%  |
| Brother Industries | 5         | 18.52%  |
| Seiko Epson        | 4         | 14.81%  |
| Canon              | 4         | 14.81%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Canon PIXMA MG2500 Series          | 3         | 11.11%  |
| Seiko Epson XP-230 Series          | 1         | 3.7%    |
| Seiko Epson Printer                | 1         | 3.7%    |
| Seiko Epson L555 Series            | 1         | 3.7%    |
| Seiko Epson ET-2700 Series         | 1         | 3.7%    |
| HP PSC 1500 series                 | 1         | 3.7%    |
| HP Printing Support                | 1         | 3.7%    |
| HP Officejet 7110 series           | 1         | 3.7%    |
| HP LaserJet Professional P 1102w   | 1         | 3.7%    |
| HP LaserJet Pro M404-M405          | 1         | 3.7%    |
| HP LaserJet M14-M17                | 1         | 3.7%    |
| HP LaserJet 1320                   | 1         | 3.7%    |
| HP LaserJet 1020                   | 1         | 3.7%    |
| HP LaserJet 1018                   | 1         | 3.7%    |
| HP LaserJet 1000                   | 1         | 3.7%    |
| HP DeskJet F300 series             | 1         | 3.7%    |
| HP DeskJet F2492 All-in-One        | 1         | 3.7%    |
| HP DeskJet 2620 All-in-One Printer | 1         | 3.7%    |
| HP Deskjet 2050 J510               | 1         | 3.7%    |
| Canon TS3100 series                | 1         | 3.7%    |
| Brother MFC-J5330DW                | 1         | 3.7%    |
| Brother HL-L3270CDW series         | 1         | 3.7%    |
| Brother HL-2030 Laser Printer      | 1         | 3.7%    |
| Brother HL-1210W series            | 1         | 3.7%    |
| Brother DCP-L2520DW                | 1         | 3.7%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP ScanJet 4300c              | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30 | 1         | 33.33%  |
| Canon CanoScan LiDE 210       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 652       | 25.78%  |
| IMC Networks                           | 314       | 12.42%  |
| Bison Electronics                      | 166       | 6.56%   |
| Microdia                               | 165       | 6.52%   |
| Realtek Semiconductor                  | 161       | 6.37%   |
| Quanta                                 | 139       | 5.5%    |
| Suyin                                  | 123       | 4.86%   |
| Sunplus Innovation Technology          | 107       | 4.23%   |
| Acer                                   | 104       | 4.11%   |
| Cheng Uei Precision Industry (Foxlink) | 98        | 3.88%   |
| Syntek                                 | 76        | 3.01%   |
| Alcor Micro                            | 47        | 1.86%   |
| Apple                                  | 42        | 1.66%   |
| Lite-On Technology                     | 40        | 1.58%   |
| Luxvisions Innotech Limited            | 38        | 1.5%    |
| Ricoh                                  | 33        | 1.3%    |
| Logitech                               | 26        | 1.03%   |
| Silicon Motion                         | 24        | 0.95%   |
| Sonix Technology                       | 18        | 0.71%   |
| Samsung Electronics                    | 13        | 0.51%   |
| icSpring                               | 11        | 0.43%   |
| Lenovo                                 | 10        | 0.4%    |
| Importek                               | 10        | 0.4%    |
| Z-Star Microelectronics                | 9         | 0.36%   |
| ALi                                    | 9         | 0.36%   |
| GEMBIRD                                | 8         | 0.32%   |
| Sunplus Technology                     | 7         | 0.28%   |
| Intel                                  | 7         | 0.28%   |
| DigiTech                               | 7         | 0.28%   |
| Primax Electronics                     | 6         | 0.24%   |
| OmniVision Technologies                | 5         | 0.2%    |
| KYE Systems (Mouse Systems)            | 5         | 0.2%    |
| Genesys Logic                          | 5         | 0.2%    |
| ARC International                      | 4         | 0.16%   |
| Trust                                  | 3         | 0.12%   |
| Generalplus Technology                 | 3         | 0.12%   |
| Novatek Microelectronics               | 2         | 0.08%   |
| Microsoft                              | 2         | 0.08%   |
| Creative Technology                    | 2         | 0.08%   |
| 2M UVC CAMERA                          | 2         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 83        | 3.27%   |
| Chicony HD Webcam                                       | 74        | 2.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 69        | 2.72%   |
| Chicony Integrated Camera                               | 69        | 2.72%   |
| Microdia Integrated_Webcam_HD                           | 66        | 2.6%    |
| IMC Networks Integrated Camera                          | 51        | 2.01%   |
| Chicony USB2.0 VGA UVC WebCam                           | 42        | 1.65%   |
| Bison Integrated Camera                                 | 39        | 1.54%   |
| Sunplus HD WebCam                                       | 35        | 1.38%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 33        | 1.3%    |
| Quanta HP TrueVision HD Camera                          | 33        | 1.3%    |
| Acer HD Webcam                                          | 32        | 1.26%   |
| Realtek USB Camera                                      | 31        | 1.22%   |
| Realtek Integrated_Webcam_HD                            | 30        | 1.18%   |
| Bison HD Webcam                                         | 30        | 1.18%   |
| Syntek Integrated Camera                                | 27        | 1.06%   |
| Chicony TOSHIBA Web Camera - HD                         | 27        | 1.06%   |
| Chicony USB 2.0 Camera                                  | 26        | 1.02%   |
| Chicony EasyCamera                                      | 26        | 1.02%   |
| Chicony USB2.0 Camera                                   | 23        | 0.91%   |
| Chicony USB2.0 HD UVC WebCam                            | 20        | 0.79%   |
| Acer Integrated Camera                                  | 20        | 0.79%   |
| Syntek EasyCamera                                       | 19        | 0.75%   |
| IMC Networks ov9734_azurewave_camera                    | 19        | 0.75%   |
| Chicony HP Truevision HD camera                         | 19        | 0.75%   |
| Syntek Lenovo EasyCamera                                | 18        | 0.71%   |
| Lite-On Integrated Camera                               | 18        | 0.71%   |
| Chicony VGA Webcam                                      | 18        | 0.71%   |
| Chicony Integrated Camera (1280x720@30)                 | 18        | 0.71%   |
| Chicony HP Truevision HD                                | 18        | 0.71%   |
| Apple Built-in iSight                                   | 18        | 0.71%   |
| Realtek Lenovo EasyCamera                               | 17        | 0.67%   |
| Quanta HP Wide Vision HD Camera                         | 17        | 0.67%   |
| Microdia Webcam Vitade AF                               | 17        | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 17        | 0.67%   |
| Alcor Micro Asus Integrated Webcam                      | 17        | 0.67%   |
| Sunplus Integrated_Webcam_HD                            | 16        | 0.63%   |
| Sonix USB2.0 HD UVC WebCam                              | 16        | 0.63%   |
| Chicony HP HD Camera                                    | 16        | 0.63%   |
| Apple FaceTime HD Camera                                | 16        | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 112       | 28%     |
| Validity Sensors                   | 91        | 22.75%  |
| Shenzhen Goodix Technology         | 73        | 18.25%  |
| Elan Microelectronics              | 39        | 9.75%   |
| AuthenTec                          | 39        | 9.75%   |
| Upek                               | 27        | 6.75%   |
| LighTuning Technology              | 11        | 2.75%   |
| STMicroelectronics                 | 7         | 1.75%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 58        | 14.5%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 37        | 9.25%   |
| Elan ELAN:Fingerprint                                                      | 34        | 8.5%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 32        | 8%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 5.5%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 4.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 3.75%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 12        | 3%      |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 3%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 2.75%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 2%      |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2%      |
| AuthenTec AES1600                                                          | 8         | 2%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.75%   |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.75%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.5%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.5%    |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.5%    |
| Validity Sensors VFS491                                                    | 5         | 1.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.25%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.25%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1.25%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.25%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.25%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.25%   |
| AuthenTec AES2810                                                          | 5         | 1.25%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 1.25%   |
| Synaptics UWP WBDI Device                                                  | 4         | 1%      |
| Synaptics  WBDI                                                            | 4         | 1%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1%      |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 1%      |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.75%   |
| Synaptics UWP WBDI                                                         | 3         | 0.75%   |
| Synaptics Fingerprint reader [HP G6]                                       | 3         | 0.75%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.75%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.5%    |
| Synaptics WBDI                                                             | 2         | 0.5%    |
| LighTuning Fingerprint Reader                                              | 2         | 0.5%    |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 60        | 35.29%  |
| Broadcom              | 56        | 32.94%  |
| O2 Micro              | 24        | 14.12%  |
| Lenovo                | 10        | 5.88%   |
| Upek                  | 4         | 2.35%   |
| Cherry                | 4         | 2.35%   |
| C3PO                  | 4         | 2.35%   |
| Realtek Semiconductor | 3         | 1.76%   |
| Gemalto (was Gemplus) | 2         | 1.18%   |
| In Focus Systems      | 1         | 0.59%   |
| Chicony Electronics   | 1         | 0.59%   |
| Advanced Card Systems | 1         | 0.59%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 60        | 35.29%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 13.53%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 11.76%  |
| Broadcom 5880                                                                | 16        | 9.41%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 5.88%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 5.88%   |
| Broadcom 58200                                                               | 9         | 5.29%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.35%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.76%   |
| Cherry SmartTerminal XX1X                                                    | 3         | 1.76%   |
| C3PO LTC31v2                                                                 | 3         | 1.76%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.18%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.59%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.59%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.59%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.59%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.59%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.59%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1935      | 63.86%  |
| 1     | 845       | 27.89%  |
| 2     | 204       | 6.73%   |
| 3     | 30        | 0.99%   |
| 4     | 9         | 0.3%    |
| 5     | 5         | 0.17%   |
| 8     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 391       | 28.96%  |
| Graphics card            | 334       | 24.74%  |
| Net/wireless             | 177       | 13.11%  |
| Chipcard                 | 148       | 10.96%  |
| Multimedia controller    | 85        | 6.3%    |
| Camera                   | 51        | 3.78%   |
| Bluetooth                | 35        | 2.59%   |
| Storage                  | 29        | 2.15%   |
| Communication controller | 24        | 1.78%   |
| Card reader              | 18        | 1.33%   |
| Sound                    | 14        | 1.04%   |
| Net/ethernet             | 13        | 0.96%   |
| Flash memory             | 11        | 0.81%   |
| Modem                    | 9         | 0.67%   |
| Network                  | 7         | 0.52%   |
| Dvb card                 | 4         | 0.3%    |

