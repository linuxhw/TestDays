Linux in Russia - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Russia.

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

Total: 19322

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | V15-IGL 82C3                | [78ecb1b882](https://linux-hardware.org/?probe=78ecb1b882) | Sep 07, 2023 |
| Timi          | Redmi Book Pro 14S          | [b2776d8282](https://linux-hardware.org/?probe=b2776d8282) | Sep 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9911fc5254](https://linux-hardware.org/?probe=9911fc5254) | Sep 07, 2023 |
| Valve         | Jupiter                     | [83b9205283](https://linux-hardware.org/?probe=83b9205283) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [3c6e29c3c3](https://linux-hardware.org/?probe=3c6e29c3c3) | Sep 06, 2023 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | [b2ba03726a](https://linux-hardware.org/?probe=b2ba03726a) | Sep 06, 2023 |
| realme        | RMNBXXXX                    | [6783f1d181](https://linux-hardware.org/?probe=6783f1d181) | Sep 06, 2023 |
| HP            | Pavilion dv6                | [08d38c1680](https://linux-hardware.org/?probe=08d38c1680) | Sep 06, 2023 |
| HUAWEI        | NBD-WXX9                    | [29e1f84537](https://linux-hardware.org/?probe=29e1f84537) | Sep 06, 2023 |
| MSI           | GE70 2PE                    | [19dddb0418](https://linux-hardware.org/?probe=19dddb0418) | Sep 06, 2023 |
| realme        | RMNBXXXX                    | [9370483c5f](https://linux-hardware.org/?probe=9370483c5f) | Sep 06, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [32c34f0aa2](https://linux-hardware.org/?probe=32c34f0aa2) | Sep 06, 2023 |
| Maibenben     | MaiBook M                   | [c3a39bc1f1](https://linux-hardware.org/?probe=c3a39bc1f1) | Sep 06, 2023 |
| ASUSTek       | X75VC                       | [ba211ae5ca](https://linux-hardware.org/?probe=ba211ae5ca) | Sep 06, 2023 |
| Clevo         | NL41MU2                     | [c309162d11](https://linux-hardware.org/?probe=c309162d11) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [50ecc5159c](https://linux-hardware.org/?probe=50ecc5159c) | Sep 06, 2023 |
| ASUSTek       | X542UQ                      | [b34e0e7866](https://linux-hardware.org/?probe=b34e0e7866) | Sep 06, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e8caa63849](https://linux-hardware.org/?probe=e8caa63849) | Sep 06, 2023 |
| ASUSTek       | N76VJ                       | [382d892ff6](https://linux-hardware.org/?probe=382d892ff6) | Sep 05, 2023 |
| Acer          | Nitro AN515-46              | [bbbba2bc47](https://linux-hardware.org/?probe=bbbba2bc47) | Sep 05, 2023 |
| Unknown       | Unknown                     | [9b4d95cf35](https://linux-hardware.org/?probe=9b4d95cf35) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7d6ff14b38](https://linux-hardware.org/?probe=7d6ff14b38) | Sep 05, 2023 |
| HP            | Pavilion Notebook           | [b8dd9b8f96](https://linux-hardware.org/?probe=b8dd9b8f96) | Sep 05, 2023 |
| Dell          | G5 5590                     | [40098c0a79](https://linux-hardware.org/?probe=40098c0a79) | Sep 05, 2023 |
| Dell          | G5 5590                     | [1af9fd689a](https://linux-hardware.org/?probe=1af9fd689a) | Sep 05, 2023 |
| HP            | EliteBook 840 G4            | [28d5496080](https://linux-hardware.org/?probe=28d5496080) | Sep 04, 2023 |
| ASUSTek       | X75VC                       | [0830aad0cc](https://linux-hardware.org/?probe=0830aad0cc) | Sep 04, 2023 |
| Toshiba       | Satellite A200              | [439b7547a5](https://linux-hardware.org/?probe=439b7547a5) | Sep 04, 2023 |
| Acer          | Aspire 3690                 | [503b015d34](https://linux-hardware.org/?probe=503b015d34) | Sep 04, 2023 |
| ASUSTek       | N76VB                       | [246d3b2d0a](https://linux-hardware.org/?probe=246d3b2d0a) | Sep 04, 2023 |
| HP            | Laptop 15s-fq2xxx           | [2135954523](https://linux-hardware.org/?probe=2135954523) | Sep 04, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [ee6914ebdf](https://linux-hardware.org/?probe=ee6914ebdf) | Sep 04, 2023 |
| Maibenben     | MaiBook M                   | [7189994067](https://linux-hardware.org/?probe=7189994067) | Sep 04, 2023 |
| HP            | EliteBook 845 14 inch G1... | [8a4af58adc](https://linux-hardware.org/?probe=8a4af58adc) | Sep 04, 2023 |
| MSI           | Prestige 14Evo A12M         | [68bea64ed6](https://linux-hardware.org/?probe=68bea64ed6) | Sep 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [8320743af2](https://linux-hardware.org/?probe=8320743af2) | Sep 04, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [18d1abc9ca](https://linux-hardware.org/?probe=18d1abc9ca) | Sep 04, 2023 |
| Lenovo        | B460e                       | [7134698bfb](https://linux-hardware.org/?probe=7134698bfb) | Sep 03, 2023 |
| ASUSTek       | X507UB                      | [e74c3ad568](https://linux-hardware.org/?probe=e74c3ad568) | Sep 03, 2023 |
| Apple         | MacBookAir6,2               | [94da12d8d8](https://linux-hardware.org/?probe=94da12d8d8) | Sep 03, 2023 |
| HUAWEI        | FRD-WX9                     | [5831652a84](https://linux-hardware.org/?probe=5831652a84) | Sep 03, 2023 |
| ASUSTek       | 1015BX                      | [7abcd39073](https://linux-hardware.org/?probe=7abcd39073) | Sep 03, 2023 |
| Lenovo        | ThinkPad T410 25188PG       | [603479bd64](https://linux-hardware.org/?probe=603479bd64) | Sep 03, 2023 |
| HP            | ENVY m6                     | [0a810c8663](https://linux-hardware.org/?probe=0a810c8663) | Sep 03, 2023 |
| Acer          | Nitro AN515-46              | [ebfb4ddd3e](https://linux-hardware.org/?probe=ebfb4ddd3e) | Sep 03, 2023 |
| Sony          | VPCEL1E1R                   | [64dec0f73c](https://linux-hardware.org/?probe=64dec0f73c) | Sep 03, 2023 |
| Sony          | VPCEL1E1R                   | [4a55a9ce8d](https://linux-hardware.org/?probe=4a55a9ce8d) | Sep 03, 2023 |
| HP            | Laptop 15-rb0xx             | [0f08b5b0ad](https://linux-hardware.org/?probe=0f08b5b0ad) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | [78c449e398](https://linux-hardware.org/?probe=78c449e398) | Sep 03, 2023 |
| Lenovo        | ThinkPad X230 23252SG       | [7f25cc995d](https://linux-hardware.org/?probe=7f25cc995d) | Sep 03, 2023 |
| Lenovo        | B590 20206                  | [3e11cfff1b](https://linux-hardware.org/?probe=3e11cfff1b) | Sep 02, 2023 |
| MSI           | GT60 2QE                    | [234502653b](https://linux-hardware.org/?probe=234502653b) | Sep 02, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [3969affef8](https://linux-hardware.org/?probe=3969affef8) | Sep 02, 2023 |
| HP            | ProBook 430 G5              | [1785af95b8](https://linux-hardware.org/?probe=1785af95b8) | Sep 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [c5db2939ee](https://linux-hardware.org/?probe=c5db2939ee) | Sep 02, 2023 |
| Irbis         | NB133                       | [62f2194b9a](https://linux-hardware.org/?probe=62f2194b9a) | Sep 02, 2023 |
| HONOR         | HYM-WXX                     | [1af7f717b0](https://linux-hardware.org/?probe=1af7f717b0) | Sep 02, 2023 |
| ASUSTek       | N750JV                      | [f23cf01c1c](https://linux-hardware.org/?probe=f23cf01c1c) | Sep 02, 2023 |
| Lenovo        | G505 20240                  | [ea15ab596a](https://linux-hardware.org/?probe=ea15ab596a) | Sep 02, 2023 |
| HP            | 630                         | [a1f0efde46](https://linux-hardware.org/?probe=a1f0efde46) | Sep 02, 2023 |
| Dell          | Inspiron 3793               | [fb0900afbb](https://linux-hardware.org/?probe=fb0900afbb) | Sep 02, 2023 |
| Valve         | Jupiter                     | [8e59296a5c](https://linux-hardware.org/?probe=8e59296a5c) | Sep 02, 2023 |
| Prestigio     | Multipad Visconte V         | [3c60fe1d14](https://linux-hardware.org/?probe=3c60fe1d14) | Sep 01, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [d646fdb00d](https://linux-hardware.org/?probe=d646fdb00d) | Sep 01, 2023 |
| eMachines     | eME442                      | [7b765f910c](https://linux-hardware.org/?probe=7b765f910c) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | [b38cdf7987](https://linux-hardware.org/?probe=b38cdf7987) | Sep 01, 2023 |
| Gigabyte      | G5 KF                       | [3eef6bf0d1](https://linux-hardware.org/?probe=3eef6bf0d1) | Sep 01, 2023 |
| Packard Be... | EasyNote TE11HC             | [2a11f6be15](https://linux-hardware.org/?probe=2a11f6be15) | Sep 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [42547fa1b3](https://linux-hardware.org/?probe=42547fa1b3) | Sep 01, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [edd00c35fd](https://linux-hardware.org/?probe=edd00c35fd) | Sep 01, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [1e7179e4f0](https://linux-hardware.org/?probe=1e7179e4f0) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | [e9f211faf1](https://linux-hardware.org/?probe=e9f211faf1) | Sep 01, 2023 |
| HONOR         | HYM-WXX                     | [b1a3900bdd](https://linux-hardware.org/?probe=b1a3900bdd) | Sep 01, 2023 |
| ASUSTek       | W7S                         | [6865435d79](https://linux-hardware.org/?probe=6865435d79) | Aug 31, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L2402CYA... | [9881dd3268](https://linux-hardware.org/?probe=9881dd3268) | Aug 31, 2023 |
| ASUSTek       | X550CC                      | [0265cb5d01](https://linux-hardware.org/?probe=0265cb5d01) | Aug 31, 2023 |
| HP            | Notebook                    | [0d55f397ff](https://linux-hardware.org/?probe=0d55f397ff) | Aug 31, 2023 |
| Lenovo        | Z50-70 20354                | [305133ce29](https://linux-hardware.org/?probe=305133ce29) | Aug 31, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [7c560dfe57](https://linux-hardware.org/?probe=7c560dfe57) | Aug 31, 2023 |
| HUAWEI        | KLVF-XX                     | [747a685cc1](https://linux-hardware.org/?probe=747a685cc1) | Aug 30, 2023 |
| HUAWEI        | BOM-WXX9                    | [ea587f2b2e](https://linux-hardware.org/?probe=ea587f2b2e) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ef1b605965](https://linux-hardware.org/?probe=ef1b605965) | Aug 30, 2023 |
| ASUSTek       | K52Je                       | [27136611ed](https://linux-hardware.org/?probe=27136611ed) | Aug 30, 2023 |
| Infinix       | INBOOK X2 GEN11             | [b196e48c97](https://linux-hardware.org/?probe=b196e48c97) | Aug 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [0842215d23](https://linux-hardware.org/?probe=0842215d23) | Aug 30, 2023 |
| HP            | Laptop 17-ca1xxx            | [a7b83b57e0](https://linux-hardware.org/?probe=a7b83b57e0) | Aug 30, 2023 |
| Acer          | Nitro AN515-52              | [efee17a022](https://linux-hardware.org/?probe=efee17a022) | Aug 30, 2023 |
| HP            | Laptop 17-ca1xxx            | [d7860c1c92](https://linux-hardware.org/?probe=d7860c1c92) | Aug 30, 2023 |
| Acer          | TravelMate P259-MG          | [dc9b122d90](https://linux-hardware.org/?probe=dc9b122d90) | Aug 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [98d2e58ba6](https://linux-hardware.org/?probe=98d2e58ba6) | Aug 30, 2023 |
| HP            | ENVY Notebook               | [eda6f43e59](https://linux-hardware.org/?probe=eda6f43e59) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | [c9a61f810d](https://linux-hardware.org/?probe=c9a61f810d) | Aug 30, 2023 |
| Acer          | Aspire A515-57              | [d6fded6169](https://linux-hardware.org/?probe=d6fded6169) | Aug 30, 2023 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | [7b3b082c14](https://linux-hardware.org/?probe=7b3b082c14) | Aug 30, 2023 |
| Digma         | EVE 11 C421Y ES1067EW       | [22e88dc9a5](https://linux-hardware.org/?probe=22e88dc9a5) | Aug 29, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3405     | [95aa09fab6](https://linux-hardware.org/?probe=95aa09fab6) | Aug 29, 2023 |
| HP            | Pavilion dv7                | [2d5e628923](https://linux-hardware.org/?probe=2d5e628923) | Aug 29, 2023 |
| Clevo         | NL41MU2                     | [9bd0b91866](https://linux-hardware.org/?probe=9bd0b91866) | Aug 29, 2023 |
| Timi          | A34S                        | [eb6a3c2430](https://linux-hardware.org/?probe=eb6a3c2430) | Aug 29, 2023 |
| HP            | ProBook 430 G4 NOTEBOOK ... | [6ee102c046](https://linux-hardware.org/?probe=6ee102c046) | Aug 28, 2023 |
| Apple         | MacBook7,1                  | [c823f63fd6](https://linux-hardware.org/?probe=c823f63fd6) | Aug 28, 2023 |
| Apple         | MacBookPro11,3              | [a102cdc504](https://linux-hardware.org/?probe=a102cdc504) | Aug 28, 2023 |
| Dell          | Inspiron 3558               | [7c1198413a](https://linux-hardware.org/?probe=7c1198413a) | Aug 28, 2023 |
| ICL           | S1511 G1R                   | [421df1df8d](https://linux-hardware.org/?probe=421df1df8d) | Aug 28, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a3a1e805b2](https://linux-hardware.org/?probe=a3a1e805b2) | Aug 27, 2023 |
| ASUSTek       | K42DY                       | [5a9171654b](https://linux-hardware.org/?probe=5a9171654b) | Aug 27, 2023 |
| Infinix       | INBOOK X2 GEN11             | [d8f8a287e6](https://linux-hardware.org/?probe=d8f8a287e6) | Aug 27, 2023 |
| ASUSTek       | X553SA                      | [ca9ccf934d](https://linux-hardware.org/?probe=ca9ccf934d) | Aug 27, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [173b99bf55](https://linux-hardware.org/?probe=173b99bf55) | Aug 27, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [8f85c500ec](https://linux-hardware.org/?probe=8f85c500ec) | Aug 27, 2023 |
| ASUSTek       | K55VD                       | [eadc869c4b](https://linux-hardware.org/?probe=eadc869c4b) | Aug 27, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [4e5f7a05c6](https://linux-hardware.org/?probe=4e5f7a05c6) | Aug 26, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [72e8fd41af](https://linux-hardware.org/?probe=72e8fd41af) | Aug 26, 2023 |
| Acer          | Aspire E5-573G              | [75836d26df](https://linux-hardware.org/?probe=75836d26df) | Aug 26, 2023 |
| Acer          | Aspire A515-45G             | [c0480c060a](https://linux-hardware.org/?probe=c0480c060a) | Aug 26, 2023 |
| HP            | ProBook 430 G1              | [aa3b7fe20f](https://linux-hardware.org/?probe=aa3b7fe20f) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [95548b426e](https://linux-hardware.org/?probe=95548b426e) | Aug 26, 2023 |
| HUAWEI        | BOD-WXX9                    | [8f033793a9](https://linux-hardware.org/?probe=8f033793a9) | Aug 26, 2023 |
| HUAWEI        | BOD-WXX9                    | [0e107ac9bb](https://linux-hardware.org/?probe=0e107ac9bb) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [6bd0ecde29](https://linux-hardware.org/?probe=6bd0ecde29) | Aug 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [a305956d47](https://linux-hardware.org/?probe=a305956d47) | Aug 26, 2023 |
| MSI           | GL73 8RC                    | [5ca33a6111](https://linux-hardware.org/?probe=5ca33a6111) | Aug 26, 2023 |
| HP            | 240 G8 Notebook PC          | [088ef87d1b](https://linux-hardware.org/?probe=088ef87d1b) | Aug 26, 2023 |
| Lenovo        | IdeaPad Z480                | [e0989b8f9e](https://linux-hardware.org/?probe=e0989b8f9e) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [aa3de32445](https://linux-hardware.org/?probe=aa3de32445) | Aug 25, 2023 |
| ASUSTek       | K54HR                       | [5f24b13b35](https://linux-hardware.org/?probe=5f24b13b35) | Aug 25, 2023 |
| Lenovo        | 3000 G530 4151/200          | [a5812138d3](https://linux-hardware.org/?probe=a5812138d3) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [3ce0d3817d](https://linux-hardware.org/?probe=3ce0d3817d) | Aug 25, 2023 |
| HP            | ProBook 430 G5              | [2f5a204e94](https://linux-hardware.org/?probe=2f5a204e94) | Aug 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [add8b61fa2](https://linux-hardware.org/?probe=add8b61fa2) | Aug 24, 2023 |
| HP            | 635                         | [4c35f9ca58](https://linux-hardware.org/?probe=4c35f9ca58) | Aug 24, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [298355e334](https://linux-hardware.org/?probe=298355e334) | Aug 24, 2023 |
| Lenovo        | ThinkPad Edge E120 3043A... | [14d6dcc28e](https://linux-hardware.org/?probe=14d6dcc28e) | Aug 24, 2023 |
| Lenovo        | G500 20236                  | [4ec7353bd2](https://linux-hardware.org/?probe=4ec7353bd2) | Aug 24, 2023 |
| Digma         | Pro Fortis M DN15P7-ADXW... | [8b2a8a66d0](https://linux-hardware.org/?probe=8b2a8a66d0) | Aug 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [9938e1fbcc](https://linux-hardware.org/?probe=9938e1fbcc) | Aug 24, 2023 |
| HP            | EliteBook 830 G5            | [15c7624753](https://linux-hardware.org/?probe=15c7624753) | Aug 23, 2023 |
| Acer          | Aspire ES1-311              | [93f204808e](https://linux-hardware.org/?probe=93f204808e) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [061ecf9479](https://linux-hardware.org/?probe=061ecf9479) | Aug 23, 2023 |
| HP            | Pavilion 15                 | [0228bd6d42](https://linux-hardware.org/?probe=0228bd6d42) | Aug 23, 2023 |
| Digma         | Pro Fortis M DN15P7-ADXW... | [400fb89d1d](https://linux-hardware.org/?probe=400fb89d1d) | Aug 23, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [01beb6bf37](https://linux-hardware.org/?probe=01beb6bf37) | Aug 23, 2023 |
| ANCOMP        | LearnMate A15-501           | [f886cf8a23](https://linux-hardware.org/?probe=f886cf8a23) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [08801db21d](https://linux-hardware.org/?probe=08801db21d) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [9b3cf2a525](https://linux-hardware.org/?probe=9b3cf2a525) | Aug 23, 2023 |
| ASUSTek       | X507UB                      | [6c8e9739d4](https://linux-hardware.org/?probe=6c8e9739d4) | Aug 23, 2023 |
| Yadro Clie... | KVADRA LE15T                | [985b61f2b2](https://linux-hardware.org/?probe=985b61f2b2) | Aug 23, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e3c7a7a5b3](https://linux-hardware.org/?probe=e3c7a7a5b3) | Aug 22, 2023 |
| Infinix       | INBOOK X2                   | [297d07a2e3](https://linux-hardware.org/?probe=297d07a2e3) | Aug 22, 2023 |
| COLORFUL      | X15 XS 22                   | [2e8aa13f76](https://linux-hardware.org/?probe=2e8aa13f76) | Aug 22, 2023 |
| HUAWEI        | BOM-WXX9                    | [10a345d2ef](https://linux-hardware.org/?probe=10a345d2ef) | Aug 22, 2023 |
| Valve         | Jupiter                     | [a83e32b89c](https://linux-hardware.org/?probe=a83e32b89c) | Aug 22, 2023 |
| HP            | Laptop 15-dw3xxx            | [6ca5d6cce7](https://linux-hardware.org/?probe=6ca5d6cce7) | Aug 22, 2023 |
| Lenovo        | B590 20206                  | [d3b3052832](https://linux-hardware.org/?probe=d3b3052832) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | [39dbb86112](https://linux-hardware.org/?probe=39dbb86112) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | [2d616412f1](https://linux-hardware.org/?probe=2d616412f1) | Aug 22, 2023 |
| Acer          | Aspire ES1-512              | [cb2839d263](https://linux-hardware.org/?probe=cb2839d263) | Aug 22, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [af048c393b](https://linux-hardware.org/?probe=af048c393b) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [60c353baa1](https://linux-hardware.org/?probe=60c353baa1) | Aug 22, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [7687b9e74a](https://linux-hardware.org/?probe=7687b9e74a) | Aug 22, 2023 |
| Irbis         | NB123                       | [6bfbd824c3](https://linux-hardware.org/?probe=6bfbd824c3) | Aug 22, 2023 |
| MSI           | Modern 14 C12M              | [86efcd3eb7](https://linux-hardware.org/?probe=86efcd3eb7) | Aug 21, 2023 |
| HONOR         | NMH-WDX9                    | [edc1d99b63](https://linux-hardware.org/?probe=edc1d99b63) | Aug 21, 2023 |
| HUAWEI        | BOM-WXX9                    | [3bea77516f](https://linux-hardware.org/?probe=3bea77516f) | Aug 21, 2023 |
| Sony          | VPCEH2J9R                   | [a919beee79](https://linux-hardware.org/?probe=a919beee79) | Aug 21, 2023 |
| HP            | EliteBook 835 13 inch G9... | [f973c9678d](https://linux-hardware.org/?probe=f973c9678d) | Aug 20, 2023 |
| Lenovo        | Legion R9000P2021H 82JQ     | [30f233a018](https://linux-hardware.org/?probe=30f233a018) | Aug 20, 2023 |
| HONOR         | BBR-WAX9                    | [1d013fbf4b](https://linux-hardware.org/?probe=1d013fbf4b) | Aug 20, 2023 |
| HP            | Pavilion Notebook           | [bc9275cc73](https://linux-hardware.org/?probe=bc9275cc73) | Aug 20, 2023 |
| Dell          | Inspiron 11-3157            | [eae8586474](https://linux-hardware.org/?probe=eae8586474) | Aug 20, 2023 |
| HP            | Laptop 17-by1xxx            | [658e65bba8](https://linux-hardware.org/?probe=658e65bba8) | Aug 20, 2023 |
| ROMBICA       | myBook Eclipse              | [01efda8d0a](https://linux-hardware.org/?probe=01efda8d0a) | Aug 20, 2023 |
| HUAWEI        | KLVD-WXX9                   | [8d8d50eabc](https://linux-hardware.org/?probe=8d8d50eabc) | Aug 20, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [b0580e41dc](https://linux-hardware.org/?probe=b0580e41dc) | Aug 20, 2023 |
| HUAWEI        | BOD-WXX9                    | [a3dc3ffc3b](https://linux-hardware.org/?probe=a3dc3ffc3b) | Aug 20, 2023 |
| Infomash      | RoverBook                   | [a105ac22d7](https://linux-hardware.org/?probe=a105ac22d7) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [34f09bffb0](https://linux-hardware.org/?probe=34f09bffb0) | Aug 20, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [8838204e5f](https://linux-hardware.org/?probe=8838204e5f) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [398280327e](https://linux-hardware.org/?probe=398280327e) | Aug 19, 2023 |
| HP            | Pavilion 17                 | [c6a4bc6b75](https://linux-hardware.org/?probe=c6a4bc6b75) | Aug 19, 2023 |
| HUAWEI        | BOD-WXX9                    | [dc1060bc0d](https://linux-hardware.org/?probe=dc1060bc0d) | Aug 19, 2023 |
| HUAWEI        | BOD-WXX9                    | [74c4c66eba](https://linux-hardware.org/?probe=74c4c66eba) | Aug 19, 2023 |
| Notebook      | WA50SRQ                     | [615e7be12b](https://linux-hardware.org/?probe=615e7be12b) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [36417c2601](https://linux-hardware.org/?probe=36417c2601) | Aug 19, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | [ed572b9b04](https://linux-hardware.org/?probe=ed572b9b04) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [81dd9b9a7a](https://linux-hardware.org/?probe=81dd9b9a7a) | Aug 19, 2023 |
| HP            | 630                         | [ad9f585249](https://linux-hardware.org/?probe=ad9f585249) | Aug 19, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [651f263a9d](https://linux-hardware.org/?probe=651f263a9d) | Aug 19, 2023 |
| HUAWEI        | NBM-WXX9                    | [ac85dd7bb4](https://linux-hardware.org/?probe=ac85dd7bb4) | Aug 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [6a0b53d7c1](https://linux-hardware.org/?probe=6a0b53d7c1) | Aug 18, 2023 |
| Notebook      | WA50SRQ                     | [5970fa0344](https://linux-hardware.org/?probe=5970fa0344) | Aug 18, 2023 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [12c6ae9006](https://linux-hardware.org/?probe=12c6ae9006) | Aug 18, 2023 |
| ANCOMP        | LearnMate A15-501           | [cf541ae2bd](https://linux-hardware.org/?probe=cf541ae2bd) | Aug 18, 2023 |
| HP            | Pavilion 15                 | [83dfd08b75](https://linux-hardware.org/?probe=83dfd08b75) | Aug 18, 2023 |
| MSI           | MS-1057                     | [081ae63942](https://linux-hardware.org/?probe=081ae63942) | Aug 18, 2023 |
| MSI           | MS-1057                     | [615f03f3b8](https://linux-hardware.org/?probe=615f03f3b8) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [417f4d6d5b](https://linux-hardware.org/?probe=417f4d6d5b) | Aug 17, 2023 |
| HP            | Pavilion g6                 | [085d83c79a](https://linux-hardware.org/?probe=085d83c79a) | Aug 17, 2023 |
| HUAWEI        | NBD-WXX9                    | [3a7f4ca491](https://linux-hardware.org/?probe=3a7f4ca491) | Aug 17, 2023 |
| HUAWEI        | BOM-WXX9                    | [e2078f93dd](https://linux-hardware.org/?probe=e2078f93dd) | Aug 17, 2023 |
| Positivo      | N6440                       | [66e9ee4711](https://linux-hardware.org/?probe=66e9ee4711) | Aug 17, 2023 |
| Sony          | VGN-NW2SRF_S                | [93a310f950](https://linux-hardware.org/?probe=93a310f950) | Aug 17, 2023 |
| Positivo      | N6440                       | [3516f8d728](https://linux-hardware.org/?probe=3516f8d728) | Aug 17, 2023 |
| Acer          | Aspire E5-575G              | [1bca67f78b](https://linux-hardware.org/?probe=1bca67f78b) | Aug 17, 2023 |
| Lenovo        | ThinkPad X220 4291MW5       | [adf4aceec8](https://linux-hardware.org/?probe=adf4aceec8) | Aug 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [cfe21994b6](https://linux-hardware.org/?probe=cfe21994b6) | Aug 17, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | [98629bd8c4](https://linux-hardware.org/?probe=98629bd8c4) | Aug 17, 2023 |
| MSI           | GF75 Thin 9SCSR             | [365fe49e34](https://linux-hardware.org/?probe=365fe49e34) | Aug 17, 2023 |
| Packard Be... | EasyNote TE11HC             | [f69a3b4363](https://linux-hardware.org/?probe=f69a3b4363) | Aug 17, 2023 |
| HP            | Laptop 15-bs1xx             | [8933be3bc7](https://linux-hardware.org/?probe=8933be3bc7) | Aug 16, 2023 |
| Packard Be... | EasyNote TS11HR             | [fb77a4db86](https://linux-hardware.org/?probe=fb77a4db86) | Aug 16, 2023 |
| Acer          | Aspire E5-575G              | [131eb14e26](https://linux-hardware.org/?probe=131eb14e26) | Aug 16, 2023 |
| Packard Be... | EasyNote TE11HC             | [af4abf9f1d](https://linux-hardware.org/?probe=af4abf9f1d) | Aug 16, 2023 |
| ASUSTek       | X541NA                      | [8e3f72e46d](https://linux-hardware.org/?probe=8e3f72e46d) | Aug 16, 2023 |
| Timi          | A35S                        | [7f78fd50bd](https://linux-hardware.org/?probe=7f78fd50bd) | Aug 16, 2023 |
| Acer          | Aspire A315-56              | [ea88be85a3](https://linux-hardware.org/?probe=ea88be85a3) | Aug 16, 2023 |
| A-DATA Tec... | XENIA 14                    | [59faf4a458](https://linux-hardware.org/?probe=59faf4a458) | Aug 15, 2023 |
| A-DATA Tec... | XENIA 14                    | [537cce8a8e](https://linux-hardware.org/?probe=537cce8a8e) | Aug 15, 2023 |
| MSI           | X460/X460DX                 | [2e5d1c9b46](https://linux-hardware.org/?probe=2e5d1c9b46) | Aug 15, 2023 |
| Acer          | Aspire A315-21G             | [b74079b9cd](https://linux-hardware.org/?probe=b74079b9cd) | Aug 15, 2023 |
| Lenovo        | ThinkPad X390 20Q1A005CD    | [c299d4ad92](https://linux-hardware.org/?probe=c299d4ad92) | Aug 15, 2023 |
| Lenovo        | G580 20157                  | [3156a63d06](https://linux-hardware.org/?probe=3156a63d06) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [6c933602ca](https://linux-hardware.org/?probe=6c933602ca) | Aug 15, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [3750dc2cb1](https://linux-hardware.org/?probe=3750dc2cb1) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [618b4d5598](https://linux-hardware.org/?probe=618b4d5598) | Aug 15, 2023 |
| Fujitsu Si... | AMILO Li 2727               | [fd38ce192c](https://linux-hardware.org/?probe=fd38ce192c) | Aug 15, 2023 |
| Dell          | Studio 1735                 | [ff082d7af8](https://linux-hardware.org/?probe=ff082d7af8) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [52bd9574d8](https://linux-hardware.org/?probe=52bd9574d8) | Aug 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [85ce620e44](https://linux-hardware.org/?probe=85ce620e44) | Aug 14, 2023 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | [4062060fba](https://linux-hardware.org/?probe=4062060fba) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [74eb1759e1](https://linux-hardware.org/?probe=74eb1759e1) | Aug 14, 2023 |
| Acer          | Aspire V3-571G              | [1d96e3b473](https://linux-hardware.org/?probe=1d96e3b473) | Aug 13, 2023 |
| Dell          | Inspiron 3542               | [ae586a02aa](https://linux-hardware.org/?probe=ae586a02aa) | Aug 13, 2023 |
| Acer          | Swift SF314-43              | [e0b2f87734](https://linux-hardware.org/?probe=e0b2f87734) | Aug 13, 2023 |
| Maibenben     | MaiBook X series            | [823d437123](https://linux-hardware.org/?probe=823d437123) | Aug 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [307eb30c27](https://linux-hardware.org/?probe=307eb30c27) | Aug 13, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | [f709dd85f7](https://linux-hardware.org/?probe=f709dd85f7) | Aug 13, 2023 |
| HONOR         | NMH-WCX9                    | [788c2c9e31](https://linux-hardware.org/?probe=788c2c9e31) | Aug 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7d7349fef7](https://linux-hardware.org/?probe=7d7349fef7) | Aug 12, 2023 |
| Irbis         | NB264                       | [ed38bccd6d](https://linux-hardware.org/?probe=ed38bccd6d) | Aug 12, 2023 |
| ASUSTek       | K53TK                       | [db9f130ade](https://linux-hardware.org/?probe=db9f130ade) | Aug 12, 2023 |
| Acer          | Aspire E1-571G              | [ca51aaad9f](https://linux-hardware.org/?probe=ca51aaad9f) | Aug 12, 2023 |
| ASUSTek       | T200TA                      | [affc999457](https://linux-hardware.org/?probe=affc999457) | Aug 12, 2023 |
| ASUSTek       | T200TA                      | [24d6504b2c](https://linux-hardware.org/?probe=24d6504b2c) | Aug 12, 2023 |
| Apple         | MacBookAir7,2               | [b80181bc47](https://linux-hardware.org/?probe=b80181bc47) | Aug 12, 2023 |
| HP            | ENVY Notebook               | [24c2810def](https://linux-hardware.org/?probe=24c2810def) | Aug 12, 2023 |
| Lenovo        | PIQY0                       | [0149927d91](https://linux-hardware.org/?probe=0149927d91) | Aug 11, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [377a0e25aa](https://linux-hardware.org/?probe=377a0e25aa) | Aug 11, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [c2d9d3160b](https://linux-hardware.org/?probe=c2d9d3160b) | Aug 11, 2023 |
| MSI           | Sword 17 A11UD              | [8ad81394c8](https://linux-hardware.org/?probe=8ad81394c8) | Aug 11, 2023 |
| HP            | ENVY Notebook               | [6327abde35](https://linux-hardware.org/?probe=6327abde35) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [a4a009cd79](https://linux-hardware.org/?probe=a4a009cd79) | Aug 11, 2023 |
| HP            | Pavilion 15                 | [0f7859844f](https://linux-hardware.org/?probe=0f7859844f) | Aug 11, 2023 |
| Acer          | Extensa 2511G               | [536699834a](https://linux-hardware.org/?probe=536699834a) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | [c9b1265a23](https://linux-hardware.org/?probe=c9b1265a23) | Aug 11, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7d63566e0a](https://linux-hardware.org/?probe=7d63566e0a) | Aug 11, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [29065a56ee](https://linux-hardware.org/?probe=29065a56ee) | Aug 11, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [46ae462027](https://linux-hardware.org/?probe=46ae462027) | Aug 11, 2023 |
| Fujitsu Si... | AMILO Li 2727               | [1dc2c421f8](https://linux-hardware.org/?probe=1dc2c421f8) | Aug 11, 2023 |
| HP            | Pavilion 15                 | [3de983a470](https://linux-hardware.org/?probe=3de983a470) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [80f2f711d8](https://linux-hardware.org/?probe=80f2f711d8) | Aug 10, 2023 |
| Toshiba       | Satellite C660              | [26597d8a51](https://linux-hardware.org/?probe=26597d8a51) | Aug 10, 2023 |
| Acer          | Extensa 5630                | [1cc3eaf69a](https://linux-hardware.org/?probe=1cc3eaf69a) | Aug 10, 2023 |
| Acer          | Aspire V3-571G              | [6c4354fa1c](https://linux-hardware.org/?probe=6c4354fa1c) | Aug 10, 2023 |
| HP            | ENVY Notebook               | [9e8624aa8d](https://linux-hardware.org/?probe=9e8624aa8d) | Aug 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [204b2fa0a0](https://linux-hardware.org/?probe=204b2fa0a0) | Aug 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [70765ac17b](https://linux-hardware.org/?probe=70765ac17b) | Aug 09, 2023 |
| HP            | Pavilion 15                 | [8636764a35](https://linux-hardware.org/?probe=8636764a35) | Aug 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f28e4b71d6](https://linux-hardware.org/?probe=f28e4b71d6) | Aug 09, 2023 |
| Chuwi         | GemiBook Pro                | [3702186068](https://linux-hardware.org/?probe=3702186068) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | [77f61b77f5](https://linux-hardware.org/?probe=77f61b77f5) | Aug 08, 2023 |
| ASUSTek       | X501U                       | [1cd218236c](https://linux-hardware.org/?probe=1cd218236c) | Aug 08, 2023 |
| ARDOR GAMI... | V15x_V17xPNKPNJPNH          | [fa4f74161f](https://linux-hardware.org/?probe=fa4f74161f) | Aug 08, 2023 |
| HUAWEI        | BOHB-WAX9                   | [42303ab8af](https://linux-hardware.org/?probe=42303ab8af) | Aug 08, 2023 |
| Dell          | Precision M4700             | [95ac580b0d](https://linux-hardware.org/?probe=95ac580b0d) | Aug 08, 2023 |
| HP            | ENVY Notebook               | [9c6d8ac7f9](https://linux-hardware.org/?probe=9c6d8ac7f9) | Aug 08, 2023 |
| Dell          | Latitude 5511               | [e9ea435e85](https://linux-hardware.org/?probe=e9ea435e85) | Aug 08, 2023 |
| Acer          | Extensa 215-51K             | [27a26187b9](https://linux-hardware.org/?probe=27a26187b9) | Aug 08, 2023 |
| HP            | Presario CQ58               | [07f5cdfaa8](https://linux-hardware.org/?probe=07f5cdfaa8) | Aug 08, 2023 |
| Acer          | Aspire E5-573G              | [305061b67e](https://linux-hardware.org/?probe=305061b67e) | Aug 08, 2023 |
| Samsung       | R528/R728                   | [cc6458fab9](https://linux-hardware.org/?probe=cc6458fab9) | Aug 08, 2023 |
| Jumper        | QCYL-200                    | [24da6190dc](https://linux-hardware.org/?probe=24da6190dc) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [36b0caba9e](https://linux-hardware.org/?probe=36b0caba9e) | Aug 07, 2023 |
| Acer          | Aspire A315-42G             | [eff926e4a9](https://linux-hardware.org/?probe=eff926e4a9) | Aug 07, 2023 |
| Echips Imp... | NQ15E                       | [7d5e97a545](https://linux-hardware.org/?probe=7d5e97a545) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [36c52dfe36](https://linux-hardware.org/?probe=36c52dfe36) | Aug 07, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [be823adc05](https://linux-hardware.org/?probe=be823adc05) | Aug 07, 2023 |
| ASUSTek       | X751NV                      | [ff33d23814](https://linux-hardware.org/?probe=ff33d23814) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [bd036e1e65](https://linux-hardware.org/?probe=bd036e1e65) | Aug 07, 2023 |
| Dell          | XPS 15 9500                 | [dbefafc94d](https://linux-hardware.org/?probe=dbefafc94d) | Aug 07, 2023 |
| Dell          | Inspiron N5110              | [52c9bb6c33](https://linux-hardware.org/?probe=52c9bb6c33) | Aug 06, 2023 |
| ASUSTek       | UX32VD                      | [298a3261a0](https://linux-hardware.org/?probe=298a3261a0) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [2771828543](https://linux-hardware.org/?probe=2771828543) | Aug 06, 2023 |
| Timi          | TM1701                      | [2fc0a44940](https://linux-hardware.org/?probe=2fc0a44940) | Aug 06, 2023 |
| ASUSTek       | X550CC                      | [0a99f6f654](https://linux-hardware.org/?probe=0a99f6f654) | Aug 06, 2023 |
| TECNO         | MEGABOOK T1                 | [ced0647d42](https://linux-hardware.org/?probe=ced0647d42) | Aug 06, 2023 |
| ASUSTek       | X550CC                      | [23298de8c1](https://linux-hardware.org/?probe=23298de8c1) | Aug 06, 2023 |
| Valve         | Jupiter                     | [6bf7b7dc2b](https://linux-hardware.org/?probe=6bf7b7dc2b) | Aug 05, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [efe021e3b5](https://linux-hardware.org/?probe=efe021e3b5) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [5f516e849d](https://linux-hardware.org/?probe=5f516e849d) | Aug 05, 2023 |
| Chuwi         | CoreBook XPro               | [776bcc618a](https://linux-hardware.org/?probe=776bcc618a) | Aug 05, 2023 |
| ASUSTek       | N53SV                       | [2c4db62652](https://linux-hardware.org/?probe=2c4db62652) | Aug 05, 2023 |
| Acer          | Aspire A715-72G             | [c95d1a55cd](https://linux-hardware.org/?probe=c95d1a55cd) | Aug 05, 2023 |
| MSI           | GE70 0NC                    | [c9fd935b80](https://linux-hardware.org/?probe=c9fd935b80) | Aug 05, 2023 |
| HP            | EliteBook 830 G5            | [d4ebcfaf3d](https://linux-hardware.org/?probe=d4ebcfaf3d) | Aug 05, 2023 |
| HP            | EliteBook 830 G5            | [cf67e6a006](https://linux-hardware.org/?probe=cf67e6a006) | Aug 05, 2023 |
| ASUSTek       | 1215N                       | [35853f5b92](https://linux-hardware.org/?probe=35853f5b92) | Aug 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7abc08a315](https://linux-hardware.org/?probe=7abc08a315) | Aug 04, 2023 |
| Dell          | Vostro 5515                 | [bd17eec0e3](https://linux-hardware.org/?probe=bd17eec0e3) | Aug 04, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [59dda0e2b7](https://linux-hardware.org/?probe=59dda0e2b7) | Aug 04, 2023 |
| Dell          | Latitude E6510              | [b32213c71d](https://linux-hardware.org/?probe=b32213c71d) | Aug 03, 2023 |
| Samsung       | 305U1A                      | [f65d34a8fb](https://linux-hardware.org/?probe=f65d34a8fb) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2b8f90f79d](https://linux-hardware.org/?probe=2b8f90f79d) | Aug 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7d96f87e00](https://linux-hardware.org/?probe=7d96f87e00) | Aug 03, 2023 |
| Notebook      | W54_W94_W955TU,-T,-C        | [1f1f14320c](https://linux-hardware.org/?probe=1f1f14320c) | Aug 03, 2023 |
| Panasonic     | CF-31WBLAXLM                | [580b017d88](https://linux-hardware.org/?probe=580b017d88) | Aug 03, 2023 |
| MSI           | Prestige 14Evo A12M         | [c9e4b6dd90](https://linux-hardware.org/?probe=c9e4b6dd90) | Aug 03, 2023 |
| MSI           | Modern 14 C12M              | [aa352b05aa](https://linux-hardware.org/?probe=aa352b05aa) | Aug 03, 2023 |
| ASUSTek       | 1015BX                      | [4770dbfc22](https://linux-hardware.org/?probe=4770dbfc22) | Aug 02, 2023 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a1f99c3e4d](https://linux-hardware.org/?probe=a1f99c3e4d) | Aug 02, 2023 |
| Acer          | Aspire A715-71G             | [fabe23f1a8](https://linux-hardware.org/?probe=fabe23f1a8) | Aug 02, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [28ff7ce482](https://linux-hardware.org/?probe=28ff7ce482) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [e3f2347cf7](https://linux-hardware.org/?probe=e3f2347cf7) | Aug 02, 2023 |
| Sony          | VPCSB1V9R                   | [8d809c3877](https://linux-hardware.org/?probe=8d809c3877) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2f4ed3cb1f](https://linux-hardware.org/?probe=2f4ed3cb1f) | Aug 02, 2023 |
| Unknown       | Unknown                     | [41ff18df05](https://linux-hardware.org/?probe=41ff18df05) | Aug 02, 2023 |
| Unknown       | Unknown                     | [eb3d428d41](https://linux-hardware.org/?probe=eb3d428d41) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [4a6b173235](https://linux-hardware.org/?probe=4a6b173235) | Aug 01, 2023 |
| Acer          | Aspire A315-23              | [ef1917aa93](https://linux-hardware.org/?probe=ef1917aa93) | Aug 01, 2023 |
| Dell          | Vostro 3500                 | [266d25478e](https://linux-hardware.org/?probe=266d25478e) | Aug 01, 2023 |
| Acer          | Aspire A315-23              | [9164151f28](https://linux-hardware.org/?probe=9164151f28) | Aug 01, 2023 |
| Dell          | Inspiron 5567               | [d252fa93be](https://linux-hardware.org/?probe=d252fa93be) | Aug 01, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [1e963cc76b](https://linux-hardware.org/?probe=1e963cc76b) | Aug 01, 2023 |
| Teclast       | Tbolt 10 DG                 | [cd75496056](https://linux-hardware.org/?probe=cd75496056) | Aug 01, 2023 |
| Acer          | Aspire A715-71G             | [7f3c7327b7](https://linux-hardware.org/?probe=7f3c7327b7) | Aug 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [f7be9307b1](https://linux-hardware.org/?probe=f7be9307b1) | Jul 31, 2023 |
| Toshiba       | Satellite C870-D7K          | [9e8acac201](https://linux-hardware.org/?probe=9e8acac201) | Jul 31, 2023 |
| Acer          | Aspire V3-551G              | [a90eeb2fa3](https://linux-hardware.org/?probe=a90eeb2fa3) | Jul 31, 2023 |
| Dell          | G15 5511                    | [278d65cdc0](https://linux-hardware.org/?probe=278d65cdc0) | Jul 31, 2023 |
| Lenovo        | G580 20150                  | [81ab0317ab](https://linux-hardware.org/?probe=81ab0317ab) | Jul 31, 2023 |
| ASUSTek       | X411UA                      | [9ceaa9062e](https://linux-hardware.org/?probe=9ceaa9062e) | Jul 31, 2023 |
| Dell          | G15 5511                    | [e4570caa8f](https://linux-hardware.org/?probe=e4570caa8f) | Jul 31, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [c42c13e7be](https://linux-hardware.org/?probe=c42c13e7be) | Jul 31, 2023 |
| Samsung       | 300V3A/300V4A/300V5A        | [a757cca527](https://linux-hardware.org/?probe=a757cca527) | Jul 31, 2023 |
| ASUSTek       | F3Se                        | [e5f8a806ea](https://linux-hardware.org/?probe=e5f8a806ea) | Jul 31, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [8a2a5c6265](https://linux-hardware.org/?probe=8a2a5c6265) | Jul 30, 2023 |
| Acer          | Aspire A315-56              | [522c7e4381](https://linux-hardware.org/?probe=522c7e4381) | Jul 30, 2023 |
| Acer          | Aspire E5-573G              | [14307e0b7e](https://linux-hardware.org/?probe=14307e0b7e) | Jul 30, 2023 |
| HUAWEI        | BOM-WXX9                    | [583bc42f4e](https://linux-hardware.org/?probe=583bc42f4e) | Jul 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [71379f70f2](https://linux-hardware.org/?probe=71379f70f2) | Jul 30, 2023 |
| Unknown       | Unknown                     | [b5f5ef27a8](https://linux-hardware.org/?probe=b5f5ef27a8) | Jul 30, 2023 |
| HP            | Pavilion dv6                | [2046d205d6](https://linux-hardware.org/?probe=2046d205d6) | Jul 30, 2023 |
| Dell          | Vostro A860                 | [0148ba9cdc](https://linux-hardware.org/?probe=0148ba9cdc) | Jul 30, 2023 |
| HP            | 250 G7 Notebook PC          | [cefd14313d](https://linux-hardware.org/?probe=cefd14313d) | Jul 30, 2023 |
| HP            | Pavilion dv7                | [cdf06f1680](https://linux-hardware.org/?probe=cdf06f1680) | Jul 30, 2023 |
| HONOR         | NBR-WAX9                    | [b69caa0c17](https://linux-hardware.org/?probe=b69caa0c17) | Jul 29, 2023 |
| HONOR         | NBR-WAX9                    | [d7434fdb2a](https://linux-hardware.org/?probe=d7434fdb2a) | Jul 29, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [c3523b3823](https://linux-hardware.org/?probe=c3523b3823) | Jul 29, 2023 |
| Sony          | SVS13A1Z9RN                 | [533b3018ea](https://linux-hardware.org/?probe=533b3018ea) | Jul 29, 2023 |
| Lenovo        | Unknown                     | [d43f4e6715](https://linux-hardware.org/?probe=d43f4e6715) | Jul 29, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [ea4fee91b6](https://linux-hardware.org/?probe=ea4fee91b6) | Jul 28, 2023 |
| ASUSTek       | X411UA                      | [0126e6254a](https://linux-hardware.org/?probe=0126e6254a) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cb17388b8c](https://linux-hardware.org/?probe=cb17388b8c) | Jul 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [03b716e2bf](https://linux-hardware.org/?probe=03b716e2bf) | Jul 28, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | [b24aea2d95](https://linux-hardware.org/?probe=b24aea2d95) | Jul 28, 2023 |
| Acer          | Aspire A517-53              | [41c9602cac](https://linux-hardware.org/?probe=41c9602cac) | Jul 28, 2023 |
| Acer          | Aspire A315-21G             | [0a4e1c4510](https://linux-hardware.org/?probe=0a4e1c4510) | Jul 28, 2023 |
| Acer          | Extensa 215-32              | [18d32a6c36](https://linux-hardware.org/?probe=18d32a6c36) | Jul 27, 2023 |
| Lenovo        | ThinkPad E490 20N80029RT    | [69cf27eaae](https://linux-hardware.org/?probe=69cf27eaae) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [1b3e699a2a](https://linux-hardware.org/?probe=1b3e699a2a) | Jul 27, 2023 |
| Dell          | Inspiron 1520               | [a119f99239](https://linux-hardware.org/?probe=a119f99239) | Jul 27, 2023 |
| Valve         | Jupiter                     | [7ca21b7b46](https://linux-hardware.org/?probe=7ca21b7b46) | Jul 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b8b95820c1](https://linux-hardware.org/?probe=b8b95820c1) | Jul 26, 2023 |
| HP            | Laptop 14s-dq0xxx           | [dc484f95af](https://linux-hardware.org/?probe=dc484f95af) | Jul 26, 2023 |
| HUAWEI        | BOD-WXX9                    | [52358f6567](https://linux-hardware.org/?probe=52358f6567) | Jul 26, 2023 |
| HP            | Laptop 14s-dq0xxx           | [8a0b28f729](https://linux-hardware.org/?probe=8a0b28f729) | Jul 26, 2023 |
| HUAWEI        | NBM-WXX9                    | [30cb22d368](https://linux-hardware.org/?probe=30cb22d368) | Jul 26, 2023 |
| Sony          | VPCSB1V9R                   | [12b5777cff](https://linux-hardware.org/?probe=12b5777cff) | Jul 26, 2023 |
| HUAWEI        | NBM-WXX9                    | [b28bc4ba91](https://linux-hardware.org/?probe=b28bc4ba91) | Jul 25, 2023 |
| ASUSTek       | X550CC                      | [15d4d04323](https://linux-hardware.org/?probe=15d4d04323) | Jul 25, 2023 |
| Acer          | Aspire 5742G                | [dd2b862a0c](https://linux-hardware.org/?probe=dd2b862a0c) | Jul 25, 2023 |
| Dell          | Vostro A860                 | [8932ae1e87](https://linux-hardware.org/?probe=8932ae1e87) | Jul 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [bd31324aeb](https://linux-hardware.org/?probe=bd31324aeb) | Jul 25, 2023 |
| ASUSTek       | X550CC                      | [9b0d43ec8f](https://linux-hardware.org/?probe=9b0d43ec8f) | Jul 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [58ac4a2c1b](https://linux-hardware.org/?probe=58ac4a2c1b) | Jul 25, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [c4d5317061](https://linux-hardware.org/?probe=c4d5317061) | Jul 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [5262229deb](https://linux-hardware.org/?probe=5262229deb) | Jul 25, 2023 |
| Notebook      | W510LU                      | [c770b71a6b](https://linux-hardware.org/?probe=c770b71a6b) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ad266cd914](https://linux-hardware.org/?probe=ad266cd914) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [a15d078adf](https://linux-hardware.org/?probe=a15d078adf) | Jul 24, 2023 |
| INSYS         | IP1-XN23                    | [4212432f00](https://linux-hardware.org/?probe=4212432f00) | Jul 24, 2023 |
| Gigabyte      | G5 KE                       | [4837040c2a](https://linux-hardware.org/?probe=4837040c2a) | Jul 24, 2023 |
| ASUSTek       | Zenbook UX535QE_UM535QE     | [cb7e913e03](https://linux-hardware.org/?probe=cb7e913e03) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [7bd82402c7](https://linux-hardware.org/?probe=7bd82402c7) | Jul 24, 2023 |
| Unknown       | Unknown                     | [1f64a4762c](https://linux-hardware.org/?probe=1f64a4762c) | Jul 24, 2023 |
| Timi          | Redmi G 2022                | [2a01d75ab6](https://linux-hardware.org/?probe=2a01d75ab6) | Jul 24, 2023 |
| Acer          | Swift SF114-34              | [eef65c51cf](https://linux-hardware.org/?probe=eef65c51cf) | Jul 24, 2023 |
| Acer          | Nitro AN515-46              | [a2d73523d4](https://linux-hardware.org/?probe=a2d73523d4) | Jul 24, 2023 |
| Unknown       | Toshiba AC100 / Dynabook... | [c7dd142af9](https://linux-hardware.org/?probe=c7dd142af9) | Jul 24, 2023 |
| Acer          | Nitro AN515-54              | [696b36cfb3](https://linux-hardware.org/?probe=696b36cfb3) | Jul 24, 2023 |
| Valve         | Jupiter                     | [cdf83d0eb8](https://linux-hardware.org/?probe=cdf83d0eb8) | Jul 24, 2023 |
| Samsung       | R780                        | [5f994aa483](https://linux-hardware.org/?probe=5f994aa483) | Jul 24, 2023 |
| Dell          | System Inspiron 17 7000 ... | [d4af5c7529](https://linux-hardware.org/?probe=d4af5c7529) | Jul 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [db7d7ddd9c](https://linux-hardware.org/?probe=db7d7ddd9c) | Jul 23, 2023 |
| Lenovo        | ThinkPad P50 20EQS2A500     | [d25f59d64d](https://linux-hardware.org/?probe=d25f59d64d) | Jul 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [3c35f3e9b5](https://linux-hardware.org/?probe=3c35f3e9b5) | Jul 23, 2023 |
| Maibenben     | MaiBook M                   | [7b591c93bb](https://linux-hardware.org/?probe=7b591c93bb) | Jul 23, 2023 |
| Acer          | Aspire V3-571G              | [0581ed028d](https://linux-hardware.org/?probe=0581ed028d) | Jul 23, 2023 |
| Lenovo        | IdeaPad Yoga 2-13 594202... | [66db18067c](https://linux-hardware.org/?probe=66db18067c) | Jul 23, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [383118634e](https://linux-hardware.org/?probe=383118634e) | Jul 23, 2023 |
| Maibenben     | MaiBook M                   | [09beccd6f9](https://linux-hardware.org/?probe=09beccd6f9) | Jul 23, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [a14a1b8379](https://linux-hardware.org/?probe=a14a1b8379) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [4222b801a9](https://linux-hardware.org/?probe=4222b801a9) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [ddb8dbe4e4](https://linux-hardware.org/?probe=ddb8dbe4e4) | Jul 23, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [82242fa0a6](https://linux-hardware.org/?probe=82242fa0a6) | Jul 23, 2023 |
| ASUSTek       | X751LD                      | [de2e3a3ebb](https://linux-hardware.org/?probe=de2e3a3ebb) | Jul 23, 2023 |
| Lenovo        | B590 20206                  | [95e16f79ed](https://linux-hardware.org/?probe=95e16f79ed) | Jul 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [46218bae31](https://linux-hardware.org/?probe=46218bae31) | Jul 23, 2023 |
| Lenovo        | V14-IIL 82C4                | [b2870ce6ad](https://linux-hardware.org/?probe=b2870ce6ad) | Jul 22, 2023 |
| Lenovo        | Legion 5 15IMH6 82NL        | [f12c3b23e5](https://linux-hardware.org/?probe=f12c3b23e5) | Jul 22, 2023 |
| Infinix       | INBOOK X2 GEN11             | [2b3d4271bf](https://linux-hardware.org/?probe=2b3d4271bf) | Jul 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CGS... | [7a3abd2e4d](https://linux-hardware.org/?probe=7a3abd2e4d) | Jul 22, 2023 |
| ASUSTek       | S551LN                      | [c716419bfb](https://linux-hardware.org/?probe=c716419bfb) | Jul 22, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20HE... | [e6320dd4ae](https://linux-hardware.org/?probe=e6320dd4ae) | Jul 22, 2023 |
| Lenovo        | B590 20208                  | [41f2b0b599](https://linux-hardware.org/?probe=41f2b0b599) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | [b2f5443fc2](https://linux-hardware.org/?probe=b2f5443fc2) | Jul 21, 2023 |
| Lenovo        | ThinkPad X390 20SDA018CD    | [3161baf648](https://linux-hardware.org/?probe=3161baf648) | Jul 21, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [568ab8dd45](https://linux-hardware.org/?probe=568ab8dd45) | Jul 21, 2023 |
| ASUSTek       | X55A                        | [6818ec7338](https://linux-hardware.org/?probe=6818ec7338) | Jul 21, 2023 |
| HUAWEI        | BOD-WXX9                    | [e98c83ea9b](https://linux-hardware.org/?probe=e98c83ea9b) | Jul 21, 2023 |
| Lenovo        | G505 20240                  | [c9c45ceeaf](https://linux-hardware.org/?probe=c9c45ceeaf) | Jul 21, 2023 |
| HUAWEI        | BOD-WXX9                    | [c0d9daee63](https://linux-hardware.org/?probe=c0d9daee63) | Jul 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7930c61fb6](https://linux-hardware.org/?probe=7930c61fb6) | Jul 21, 2023 |
| Acer          | Aspire 5610                 | [aa66524b51](https://linux-hardware.org/?probe=aa66524b51) | Jul 21, 2023 |
| Unknown       | Unknown                     | [139780d2a0](https://linux-hardware.org/?probe=139780d2a0) | Jul 21, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [de2decf47b](https://linux-hardware.org/?probe=de2decf47b) | Jul 20, 2023 |
| HUAWEI        | BOD-WXX9                    | [10c841c8ae](https://linux-hardware.org/?probe=10c841c8ae) | Jul 20, 2023 |
| F-Plus Mob... | FLAPTOP r                   | [f21f00d216](https://linux-hardware.org/?probe=f21f00d216) | Jul 20, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [cb2cdb1a94](https://linux-hardware.org/?probe=cb2cdb1a94) | Jul 20, 2023 |
| Samsung       | R530/R730                   | [0af014c11b](https://linux-hardware.org/?probe=0af014c11b) | Jul 20, 2023 |
| MSI           | GS73 Stealth 8RE            | [8fdb7e6e4e](https://linux-hardware.org/?probe=8fdb7e6e4e) | Jul 20, 2023 |
| HP            | ProBook 440 G4              | [5fbf587eba](https://linux-hardware.org/?probe=5fbf587eba) | Jul 19, 2023 |
| Acer          | AOD260                      | [e3854aa993](https://linux-hardware.org/?probe=e3854aa993) | Jul 19, 2023 |
| MSI           | Sword 17 A11UD              | [fd2864f7e1](https://linux-hardware.org/?probe=fd2864f7e1) | Jul 19, 2023 |
| Chuwi         | CoreBook                    | [816be37c03](https://linux-hardware.org/?probe=816be37c03) | Jul 19, 2023 |
| Toshiba       | QOSMIO G30                  | [520eb05b29](https://linux-hardware.org/?probe=520eb05b29) | Jul 19, 2023 |
| HP            | Notebook                    | [92bc221e2c](https://linux-hardware.org/?probe=92bc221e2c) | Jul 19, 2023 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [39035af050](https://linux-hardware.org/?probe=39035af050) | Jul 19, 2023 |
| Acer          | Extensa 215-22              | [fc3dadd5bc](https://linux-hardware.org/?probe=fc3dadd5bc) | Jul 19, 2023 |
| Apple         | MacBookPro5,5               | [b5b8d4fce2](https://linux-hardware.org/?probe=b5b8d4fce2) | Jul 19, 2023 |
| Lenovo        | B590 20208                  | [5f2fbf2720](https://linux-hardware.org/?probe=5f2fbf2720) | Jul 19, 2023 |
| ASUSTek       | K40IN                       | [ad25a9b9a2](https://linux-hardware.org/?probe=ad25a9b9a2) | Jul 19, 2023 |
| ASUSTek       | X550CL                      | [15f6e3e7e0](https://linux-hardware.org/?probe=15f6e3e7e0) | Jul 19, 2023 |
| HP            | EliteBook 8570p             | [8e456f1108](https://linux-hardware.org/?probe=8e456f1108) | Jul 18, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [f81b2bedb9](https://linux-hardware.org/?probe=f81b2bedb9) | Jul 18, 2023 |
| Lenovo        | IdeaPad S10-2 20027         | [ea5513d981](https://linux-hardware.org/?probe=ea5513d981) | Jul 18, 2023 |
| HP            | Compaq nx7400 (EY587ES#A... | [15ba20b136](https://linux-hardware.org/?probe=15ba20b136) | Jul 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [8ce3a9560a](https://linux-hardware.org/?probe=8ce3a9560a) | Jul 18, 2023 |
| MSI           | GF63 Thin 11UC              | [3ef8cdcacb](https://linux-hardware.org/?probe=3ef8cdcacb) | Jul 18, 2023 |
| Apple         | MacBookAir6,2               | [fe575143d6](https://linux-hardware.org/?probe=fe575143d6) | Jul 18, 2023 |
| MSI           | GS73 Stealth 8RE            | [83f9ea8fc6](https://linux-hardware.org/?probe=83f9ea8fc6) | Jul 18, 2023 |
| HP            | 17-ak041ur                  | [5881affa24](https://linux-hardware.org/?probe=5881affa24) | Jul 18, 2023 |
| Acer          | Extensa 2519                | [59550c139a](https://linux-hardware.org/?probe=59550c139a) | Jul 18, 2023 |
| Lenovo        | ThinkPad E480 20KN005CRT    | [722170f1f3](https://linux-hardware.org/?probe=722170f1f3) | Jul 17, 2023 |
| HP            | EliteBook 830 G5            | [42eb1edbb6](https://linux-hardware.org/?probe=42eb1edbb6) | Jul 17, 2023 |
| HONOR         | BBR-WAX9                    | [b098dc2f61](https://linux-hardware.org/?probe=b098dc2f61) | Jul 17, 2023 |
| MSI           | GF63 Thin 11UC              | [f4fc84ba4b](https://linux-hardware.org/?probe=f4fc84ba4b) | Jul 17, 2023 |
| MSI           | GF63 Thin 11UC              | [9e330138e8](https://linux-hardware.org/?probe=9e330138e8) | Jul 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [73cb939cd2](https://linux-hardware.org/?probe=73cb939cd2) | Jul 17, 2023 |
| HP            | ProBook 440 G7              | [48cf81576d](https://linux-hardware.org/?probe=48cf81576d) | Jul 17, 2023 |
| Dell          | Vostro 3400                 | [ee71316b5e](https://linux-hardware.org/?probe=ee71316b5e) | Jul 17, 2023 |
| Gigabyte      | G5 ME                       | [eaefa9c2c6](https://linux-hardware.org/?probe=eaefa9c2c6) | Jul 17, 2023 |
| Pegatron      | A24                         | [2423e38b38](https://linux-hardware.org/?probe=2423e38b38) | Jul 17, 2023 |
| Lenovo        | ThinkPad X390 20Q1S67S00    | [be43004463](https://linux-hardware.org/?probe=be43004463) | Jul 17, 2023 |
| Valve         | Jupiter                     | [d5af3b1fe2](https://linux-hardware.org/?probe=d5af3b1fe2) | Jul 17, 2023 |
| Dell          | Latitude 5490               | [3938a20867](https://linux-hardware.org/?probe=3938a20867) | Jul 16, 2023 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [65e4fb1356](https://linux-hardware.org/?probe=65e4fb1356) | Jul 16, 2023 |
| HP            | Pavilion g7                 | [55b3650fc4](https://linux-hardware.org/?probe=55b3650fc4) | Jul 16, 2023 |
| Digma         | EVE 15 C413 ES5059EW        | [8898bab875](https://linux-hardware.org/?probe=8898bab875) | Jul 16, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [497e6c5432](https://linux-hardware.org/?probe=497e6c5432) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [6b4e2c6a3e](https://linux-hardware.org/?probe=6b4e2c6a3e) | Jul 16, 2023 |
| Digma         | EVE 15 C413 ES5059EW        | [c3f684db9d](https://linux-hardware.org/?probe=c3f684db9d) | Jul 16, 2023 |
| Unknown       | X133                        | [9ddb375619](https://linux-hardware.org/?probe=9ddb375619) | Jul 15, 2023 |
| Quanta        | SWH                         | [b7b21e5a7e](https://linux-hardware.org/?probe=b7b21e5a7e) | Jul 15, 2023 |
| Lenovo        | B590 20208                  | [47ef0bfa06](https://linux-hardware.org/?probe=47ef0bfa06) | Jul 15, 2023 |
| Maibenben     | MaiBook M                   | [44a9f08c5e](https://linux-hardware.org/?probe=44a9f08c5e) | Jul 15, 2023 |
| Acer          | Aspire V5-571G              | [e49b457f5b](https://linux-hardware.org/?probe=e49b457f5b) | Jul 15, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [a24026d3c6](https://linux-hardware.org/?probe=a24026d3c6) | Jul 14, 2023 |
| Lenovo        | G570 20079                  | [942a140f96](https://linux-hardware.org/?probe=942a140f96) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d3c3cdb439](https://linux-hardware.org/?probe=d3c3cdb439) | Jul 14, 2023 |
| Acer          | Aspire V5-571G              | [e606ef8f63](https://linux-hardware.org/?probe=e606ef8f63) | Jul 14, 2023 |
| Lenovo        | Legion R9000K2021H 82N6     | [4c8fc2482e](https://linux-hardware.org/?probe=4c8fc2482e) | Jul 14, 2023 |
| Lenovo        | V14-IIL 82C4                | [42aba63af0](https://linux-hardware.org/?probe=42aba63af0) | Jul 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [793289bc48](https://linux-hardware.org/?probe=793289bc48) | Jul 13, 2023 |
| ASUSTek       | N56VZ                       | [af989434ae](https://linux-hardware.org/?probe=af989434ae) | Jul 13, 2023 |
| Dell          | Inspiron 3721               | [bc68686efe](https://linux-hardware.org/?probe=bc68686efe) | Jul 13, 2023 |
| Valve         | Jupiter                     | [14f7ea4a48](https://linux-hardware.org/?probe=14f7ea4a48) | Jul 13, 2023 |
| HP            | ENVY dv7                    | [f9022b116c](https://linux-hardware.org/?probe=f9022b116c) | Jul 13, 2023 |
| MSI           | Alpha 15 A4DEK              | [9a192c4a0b](https://linux-hardware.org/?probe=9a192c4a0b) | Jul 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [2b7aba4c76](https://linux-hardware.org/?probe=2b7aba4c76) | Jul 13, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [23e018569e](https://linux-hardware.org/?probe=23e018569e) | Jul 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [d5ff5f9f79](https://linux-hardware.org/?probe=d5ff5f9f79) | Jul 13, 2023 |
| ASUSTek       | K40IN                       | [882334cade](https://linux-hardware.org/?probe=882334cade) | Jul 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0V30... | [174cb234d5](https://linux-hardware.org/?probe=174cb234d5) | Jul 12, 2023 |
| Acer          | TravelMate B118-M           | [97e1dc01ce](https://linux-hardware.org/?probe=97e1dc01ce) | Jul 12, 2023 |
| Intel Clie... | LAPBC710                    | [c957ebba28](https://linux-hardware.org/?probe=c957ebba28) | Jul 12, 2023 |
| HP            | Laptop 17-ak0xx             | [19b530567f](https://linux-hardware.org/?probe=19b530567f) | Jul 12, 2023 |
| MSI           | Alpha 15 A4DEK              | [cbae5fed49](https://linux-hardware.org/?probe=cbae5fed49) | Jul 12, 2023 |
| Acer          | Aspire 5820TG               | [86cfbf79ce](https://linux-hardware.org/?probe=86cfbf79ce) | Jul 12, 2023 |
| MSI           | FX603                       | [a2c598f9eb](https://linux-hardware.org/?probe=a2c598f9eb) | Jul 12, 2023 |
| Samsung       | R780                        | [b83bd7a46e](https://linux-hardware.org/?probe=b83bd7a46e) | Jul 12, 2023 |
| ASUSTek       | K53SM                       | [7aac135bc0](https://linux-hardware.org/?probe=7aac135bc0) | Jul 11, 2023 |
| MSI           | Katana GF76 11UD            | [dc3e50c4e3](https://linux-hardware.org/?probe=dc3e50c4e3) | Jul 11, 2023 |
| HP            | Compaq 2510p                | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| ASUSTek       | K53SV                       | [3a7ff2690e](https://linux-hardware.org/?probe=3a7ff2690e) | Jul 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [390b1ec39e](https://linux-hardware.org/?probe=390b1ec39e) | Jul 11, 2023 |
| HP            | Notebook                    | [eb64e08d64](https://linux-hardware.org/?probe=eb64e08d64) | Jul 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [443e3f909c](https://linux-hardware.org/?probe=443e3f909c) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [fc0d49b8b1](https://linux-hardware.org/?probe=fc0d49b8b1) | Jul 11, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [b073050c46](https://linux-hardware.org/?probe=b073050c46) | Jul 11, 2023 |
| Dell          | Precision M4700             | [7dc84c10b5](https://linux-hardware.org/?probe=7dc84c10b5) | Jul 11, 2023 |
| Acer          | Swift SF114-34              | [aef11f1cde](https://linux-hardware.org/?probe=aef11f1cde) | Jul 11, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [11b9751db7](https://linux-hardware.org/?probe=11b9751db7) | Jul 10, 2023 |
| HP            | Compaq 2510p                | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| ASUSTek       | G73Jh                       | [60e43d39b2](https://linux-hardware.org/?probe=60e43d39b2) | Jul 10, 2023 |
| HP            | EliteBook 745 G2            | [572e346587](https://linux-hardware.org/?probe=572e346587) | Jul 10, 2023 |
| HUAWEI        | BOD-WXX9                    | [e157c2b1d6](https://linux-hardware.org/?probe=e157c2b1d6) | Jul 10, 2023 |
| HP            | Pavilion 17                 | [e181859893](https://linux-hardware.org/?probe=e181859893) | Jul 09, 2023 |
| HP            | Pavilion 17                 | [3824925c02](https://linux-hardware.org/?probe=3824925c02) | Jul 09, 2023 |
| HONOR         | HLYL-WXX9                   | [874777047d](https://linux-hardware.org/?probe=874777047d) | Jul 09, 2023 |
| MSI           | Modern 14 B11MOU            | [c2e76ab704](https://linux-hardware.org/?probe=c2e76ab704) | Jul 09, 2023 |
| Dell          | Inspiron 3583               | [3f5ae451c0](https://linux-hardware.org/?probe=3f5ae451c0) | Jul 09, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [214dd1ad57](https://linux-hardware.org/?probe=214dd1ad57) | Jul 09, 2023 |
| Acer          | Extensa 2519                | [1aa67ff6d3](https://linux-hardware.org/?probe=1aa67ff6d3) | Jul 09, 2023 |
| Lenovo        | ThinkPad P50 20EQS2A500     | [d053bea459](https://linux-hardware.org/?probe=d053bea459) | Jul 09, 2023 |
| HP            | Notebook                    | [9944e4c37d](https://linux-hardware.org/?probe=9944e4c37d) | Jul 09, 2023 |
| Timi          | Redmi G 2022                | [30e96afcdd](https://linux-hardware.org/?probe=30e96afcdd) | Jul 08, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [2eb50b690c](https://linux-hardware.org/?probe=2eb50b690c) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [b01bdb1bd6](https://linux-hardware.org/?probe=b01bdb1bd6) | Jul 08, 2023 |
| Acer          | Extensa 5630                | [8ba8120911](https://linux-hardware.org/?probe=8ba8120911) | Jul 08, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [cdff301d1a](https://linux-hardware.org/?probe=cdff301d1a) | Jul 08, 2023 |
| ASUSTek       | UX550VE                     | [b782a00935](https://linux-hardware.org/?probe=b782a00935) | Jul 08, 2023 |
| HP            | EliteBook 840 G4            | [cc006abf72](https://linux-hardware.org/?probe=cc006abf72) | Jul 08, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [6f3284cac3](https://linux-hardware.org/?probe=6f3284cac3) | Jul 07, 2023 |
| TECNO         | MEGABOOK T1                 | [63737caadb](https://linux-hardware.org/?probe=63737caadb) | Jul 07, 2023 |
| HP            | ProBook 430 G1              | [abb4e75faa](https://linux-hardware.org/?probe=abb4e75faa) | Jul 07, 2023 |
| Lenovo        | B50-70 20384                | [8a0a97b362](https://linux-hardware.org/?probe=8a0a97b362) | Jul 07, 2023 |
| Dell          | Inspiron 15-3552            | [2584019194](https://linux-hardware.org/?probe=2584019194) | Jul 06, 2023 |
| MSI           | Katana GF76 11UD            | [c3a26fb815](https://linux-hardware.org/?probe=c3a26fb815) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [d4c8c30176](https://linux-hardware.org/?probe=d4c8c30176) | Jul 06, 2023 |
| Toshiba       | Satellite P200D             | [609a275664](https://linux-hardware.org/?probe=609a275664) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | [95d2ae1051](https://linux-hardware.org/?probe=95d2ae1051) | Jul 06, 2023 |
| HONOR         | BOHK-WAX9X                  | [4f6d2375a3](https://linux-hardware.org/?probe=4f6d2375a3) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [d9dc7d5425](https://linux-hardware.org/?probe=d9dc7d5425) | Jul 06, 2023 |
| Nokia         | N900                        | [7728c85b90](https://linux-hardware.org/?probe=7728c85b90) | Jul 06, 2023 |
| HP            | 630                         | [d1836d596c](https://linux-hardware.org/?probe=d1836d596c) | Jul 06, 2023 |
| MSI           | Modern 15 A11SBU            | [1d46fd852c](https://linux-hardware.org/?probe=1d46fd852c) | Jul 06, 2023 |
| Intel Clie... | LAPBC710                    | [fd97a27365](https://linux-hardware.org/?probe=fd97a27365) | Jul 06, 2023 |
| Acer          | Predator PT515-51           | [9971e8a3da](https://linux-hardware.org/?probe=9971e8a3da) | Jul 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [d55667dbf0](https://linux-hardware.org/?probe=d55667dbf0) | Jul 05, 2023 |
| HONOR         | HYM-WXX                     | [d164a02f42](https://linux-hardware.org/?probe=d164a02f42) | Jul 05, 2023 |
| HP            | Laptop 15s-eq0xxx           | [02df64cd7b](https://linux-hardware.org/?probe=02df64cd7b) | Jul 05, 2023 |
| MSI           | Summit E13FlipEvo A13MT     | [ec1d2fbdad](https://linux-hardware.org/?probe=ec1d2fbdad) | Jul 04, 2023 |
| Lenovo        | Legion R9000K2021H 82N6     | [a968f4b15c](https://linux-hardware.org/?probe=a968f4b15c) | Jul 04, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c387c4fbf1](https://linux-hardware.org/?probe=c387c4fbf1) | Jul 04, 2023 |
| Dell          | Latitude E6510              | [1f9e94e1cf](https://linux-hardware.org/?probe=1f9e94e1cf) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f876739c27](https://linux-hardware.org/?probe=f876739c27) | Jul 04, 2023 |
| Timi          | Redmi G 2022                | [cd2b7e13ce](https://linux-hardware.org/?probe=cd2b7e13ce) | Jul 04, 2023 |
| ICL           | Si1407                      | [c4c9d43042](https://linux-hardware.org/?probe=c4c9d43042) | Jul 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | [2e4a653435](https://linux-hardware.org/?probe=2e4a653435) | Jul 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [d47bc7229c](https://linux-hardware.org/?probe=d47bc7229c) | Jul 04, 2023 |
| Graviton      | N15I-T                      | [b457883ad3](https://linux-hardware.org/?probe=b457883ad3) | Jul 04, 2023 |
| Timi          | Redmi G 2022                | [a6c12e95a6](https://linux-hardware.org/?probe=a6c12e95a6) | Jul 04, 2023 |
| MSI           | FX603                       | [8b0664bd4e](https://linux-hardware.org/?probe=8b0664bd4e) | Jul 04, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [dfd88b9f78](https://linux-hardware.org/?probe=dfd88b9f78) | Jul 04, 2023 |
| TECNO         | MEGABOOK T1                 | [484f3282fa](https://linux-hardware.org/?probe=484f3282fa) | Jul 04, 2023 |
| Acer          | Nitro AN515-46              | [b45f18bac2](https://linux-hardware.org/?probe=b45f18bac2) | Jul 04, 2023 |
| Infinix       | INBOOK X2 GEN11             | [62e1543492](https://linux-hardware.org/?probe=62e1543492) | Jul 04, 2023 |
| rombica       | myBook Eclipse              | [c8f641ef96](https://linux-hardware.org/?probe=c8f641ef96) | Jul 04, 2023 |
| Lenovo        | ThinkPad P50 20EQS2A500     | [8231312f5c](https://linux-hardware.org/?probe=8231312f5c) | Jul 04, 2023 |
| Acer          | Aspire E5-771G              | [39716dd662](https://linux-hardware.org/?probe=39716dd662) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | [90b6b19a97](https://linux-hardware.org/?probe=90b6b19a97) | Jul 03, 2023 |
| HP            | EliteBook 830 G5            | [72f7ad0022](https://linux-hardware.org/?probe=72f7ad0022) | Jul 03, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f9e366002e](https://linux-hardware.org/?probe=f9e366002e) | Jul 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [1af3478d1a](https://linux-hardware.org/?probe=1af3478d1a) | Jul 03, 2023 |
| ASUSTek       | 1015BX                      | [c4bc43a932](https://linux-hardware.org/?probe=c4bc43a932) | Jul 03, 2023 |
| HP            | Laptop 15s-eq0xxx           | [ee60bb65df](https://linux-hardware.org/?probe=ee60bb65df) | Jul 03, 2023 |
| Graviton      | N15I-T                      | [305390c16e](https://linux-hardware.org/?probe=305390c16e) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [73146ccba2](https://linux-hardware.org/?probe=73146ccba2) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [6ca874df22](https://linux-hardware.org/?probe=6ca874df22) | Jul 03, 2023 |
| MSI           | ER710                       | [aa6325e66e](https://linux-hardware.org/?probe=aa6325e66e) | Jul 03, 2023 |
| HP            | Notebook                    | [8399533d47](https://linux-hardware.org/?probe=8399533d47) | Jul 03, 2023 |
| Dell          | Latitude E6510              | [bc2c3c520a](https://linux-hardware.org/?probe=bc2c3c520a) | Jul 02, 2023 |
| Haier         | i1500SD                     | [1a118c855a](https://linux-hardware.org/?probe=1a118c855a) | Jul 02, 2023 |
| HP            | EliteBook 8460p             | [40b92fc7ba](https://linux-hardware.org/?probe=40b92fc7ba) | Jul 02, 2023 |
| HP            | 250 G1                      | [25559429ca](https://linux-hardware.org/?probe=25559429ca) | Jul 02, 2023 |
| Prestigio     | Smartbook PSB116A           | [ff56870120](https://linux-hardware.org/?probe=ff56870120) | Jul 02, 2023 |
| HP            | OMEN by Laptop              | [6ad6d2e8c6](https://linux-hardware.org/?probe=6ad6d2e8c6) | Jul 02, 2023 |
| HP            | Laptop 15s-eq1xxx           | [a3df72826f](https://linux-hardware.org/?probe=a3df72826f) | Jul 02, 2023 |
| Dell          | Inspiron N5110              | [d49ddcbcf1](https://linux-hardware.org/?probe=d49ddcbcf1) | Jul 01, 2023 |
| Aquarius      | NS685U R11                  | [e310cace05](https://linux-hardware.org/?probe=e310cace05) | Jul 01, 2023 |
| Aquarius      | NS685U R11                  | [2e0aca71ba](https://linux-hardware.org/?probe=2e0aca71ba) | Jul 01, 2023 |
| rombica       | myBook Eclipse              | [f42493341a](https://linux-hardware.org/?probe=f42493341a) | Jul 01, 2023 |
| rombica       | myBook Eclipse              | [19d5480b96](https://linux-hardware.org/?probe=19d5480b96) | Jul 01, 2023 |
| HUAWEI        | BOM-WXX9                    | [13c1e56ca9](https://linux-hardware.org/?probe=13c1e56ca9) | Jul 01, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [b5d1a7e115](https://linux-hardware.org/?probe=b5d1a7e115) | Jun 30, 2023 |
| Acer          | Aspire A315-23              | [434ba90999](https://linux-hardware.org/?probe=434ba90999) | Jun 30, 2023 |
| HP            | Laptop 17-by3xxx            | [8bfe14749f](https://linux-hardware.org/?probe=8bfe14749f) | Jun 30, 2023 |
| Lenovo        | ThinkPad E490 20N80017RT    | [a2a1011725](https://linux-hardware.org/?probe=a2a1011725) | Jun 30, 2023 |
| Maibenben     | MaiBook X series            | [5e11bea093](https://linux-hardware.org/?probe=5e11bea093) | Jun 30, 2023 |
| Chuwi         | CoreBook XPro               | [501d899938](https://linux-hardware.org/?probe=501d899938) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [05cb990f84](https://linux-hardware.org/?probe=05cb990f84) | Jun 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [4677625b04](https://linux-hardware.org/?probe=4677625b04) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [5dd37cbc97](https://linux-hardware.org/?probe=5dd37cbc97) | Jun 30, 2023 |
| ASUSTek       | ME176C                      | [2f2e7076e1](https://linux-hardware.org/?probe=2f2e7076e1) | Jun 30, 2023 |
| ASUSTek       | K52F                        | [98e9b448c7](https://linux-hardware.org/?probe=98e9b448c7) | Jun 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [b98433fa84](https://linux-hardware.org/?probe=b98433fa84) | Jun 29, 2023 |
| Dell          | Studio 1558                 | [66e76ea87d](https://linux-hardware.org/?probe=66e76ea87d) | Jun 29, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [f3cb4dc749](https://linux-hardware.org/?probe=f3cb4dc749) | Jun 29, 2023 |
| Acer          | Aspire E5-531G              | [a6eaac367e](https://linux-hardware.org/?probe=a6eaac367e) | Jun 29, 2023 |
| Lenovo        | G50-80 80L0                 | [9979e7a733](https://linux-hardware.org/?probe=9979e7a733) | Jun 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [1c349accca](https://linux-hardware.org/?probe=1c349accca) | Jun 29, 2023 |
| Acer          | Aspire V3-571G              | [9d4c4f5506](https://linux-hardware.org/?probe=9d4c4f5506) | Jun 29, 2023 |
| eMachines     | eME728                      | [37dc0ef617](https://linux-hardware.org/?probe=37dc0ef617) | Jun 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [076e14da35](https://linux-hardware.org/?probe=076e14da35) | Jun 29, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [61930889dc](https://linux-hardware.org/?probe=61930889dc) | Jun 29, 2023 |
| HP            | Pavilion g6                 | [b16b0ced2f](https://linux-hardware.org/?probe=b16b0ced2f) | Jun 28, 2023 |
| HP            | Notebook                    | [d5ab0810e6](https://linux-hardware.org/?probe=d5ab0810e6) | Jun 28, 2023 |
| HP            | Notebook                    | [2b5ac7b339](https://linux-hardware.org/?probe=2b5ac7b339) | Jun 28, 2023 |
| Dell          | Inspiron 15-3552            | [6197072395](https://linux-hardware.org/?probe=6197072395) | Jun 28, 2023 |
| Unknown       | Unknown                     | [0ea4bcb3df](https://linux-hardware.org/?probe=0ea4bcb3df) | Jun 28, 2023 |
| Aquarius      | NS585                       | [52a07593c9](https://linux-hardware.org/?probe=52a07593c9) | Jun 28, 2023 |
| Aquarius      | NS585                       | [b2f86e98f9](https://linux-hardware.org/?probe=b2f86e98f9) | Jun 28, 2023 |
| Lenovo        | ThinkPad P17 Gen 1 20SN0... | [5ea6336cb5](https://linux-hardware.org/?probe=5ea6336cb5) | Jun 28, 2023 |
| Acer          | Aspire A315-23              | [36f9eb51e6](https://linux-hardware.org/?probe=36f9eb51e6) | Jun 28, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | [1d6bf708ce](https://linux-hardware.org/?probe=1d6bf708ce) | Jun 28, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [ab4772fd2e](https://linux-hardware.org/?probe=ab4772fd2e) | Jun 28, 2023 |
| MSI           | GL65 Leopard 10SCSR         | [165a76b787](https://linux-hardware.org/?probe=165a76b787) | Jun 27, 2023 |
| Acer          | Extensa 2519                | [1a8a4ee11e](https://linux-hardware.org/?probe=1a8a4ee11e) | Jun 27, 2023 |
| Clevo         | NL41MU2                     | [d7e51d1ddb](https://linux-hardware.org/?probe=d7e51d1ddb) | Jun 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5336cd4400](https://linux-hardware.org/?probe=5336cd4400) | Jun 27, 2023 |
| 3Logic Gro... | Graviton N15i               | [1f7adfe250](https://linux-hardware.org/?probe=1f7adfe250) | Jun 27, 2023 |
| Lenovo        | ThinkPad SL410 2842RN9      | [37157ab2f7](https://linux-hardware.org/?probe=37157ab2f7) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | [dc32791d25](https://linux-hardware.org/?probe=dc32791d25) | Jun 27, 2023 |
| MSI           | Katana GF66 11SC            | [adf7a275be](https://linux-hardware.org/?probe=adf7a275be) | Jun 27, 2023 |
| Dell          | Inspiron N5110              | [ec28913b4e](https://linux-hardware.org/?probe=ec28913b4e) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| 3Logic Gro... | APM Graviton A15i-K2        | [6371ce9a45](https://linux-hardware.org/?probe=6371ce9a45) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [cde6a94b92](https://linux-hardware.org/?probe=cde6a94b92) | Jun 26, 2023 |
| Acer          | Nitro AN515-45              | [674acd96a8](https://linux-hardware.org/?probe=674acd96a8) | Jun 26, 2023 |
| Clevo         | NL41MU2                     | [91bb626fa8](https://linux-hardware.org/?probe=91bb626fa8) | Jun 26, 2023 |
| Lenovo        | G780 20138                  | [41cdbe05fe](https://linux-hardware.org/?probe=41cdbe05fe) | Jun 26, 2023 |
| Aquarius      | NS585                       | [25af22ec30](https://linux-hardware.org/?probe=25af22ec30) | Jun 26, 2023 |
| Aquarius      | NS585                       | [8e957a70f0](https://linux-hardware.org/?probe=8e957a70f0) | Jun 26, 2023 |
| HUAWEI        | BOM-WXX9                    | [2e9bc10188](https://linux-hardware.org/?probe=2e9bc10188) | Jun 26, 2023 |
| Aquarius      | NS585                       | [bb09ae1f8d](https://linux-hardware.org/?probe=bb09ae1f8d) | Jun 26, 2023 |
| Unknown       | Unknown                     | [9c8513ff31](https://linux-hardware.org/?probe=9c8513ff31) | Jun 25, 2023 |
| HP            | Pavilion Notebook           | [eb68fc38b0](https://linux-hardware.org/?probe=eb68fc38b0) | Jun 25, 2023 |
| HASEE Comp... | PB50_70DFx,DDx              | [3690bcb661](https://linux-hardware.org/?probe=3690bcb661) | Jun 25, 2023 |
| ASUSTek       | X540NA                      | [6a01ca36af](https://linux-hardware.org/?probe=6a01ca36af) | Jun 25, 2023 |
| ASUSTek       | X540NA                      | [b5996a0d85](https://linux-hardware.org/?probe=b5996a0d85) | Jun 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [cee2bb11dc](https://linux-hardware.org/?probe=cee2bb11dc) | Jun 25, 2023 |
| ASUSTek       | M51Vr                       | [16404e70f6](https://linux-hardware.org/?probe=16404e70f6) | Jun 25, 2023 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [a5d8941505](https://linux-hardware.org/?probe=a5d8941505) | Jun 25, 2023 |
| HONOR         | BMH-WCX9                    | [f40cb826de](https://linux-hardware.org/?probe=f40cb826de) | Jun 25, 2023 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [6398806c80](https://linux-hardware.org/?probe=6398806c80) | Jun 25, 2023 |
| Haier         | i1510SD                     | [f464f11210](https://linux-hardware.org/?probe=f464f11210) | Jun 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [3a045583a7](https://linux-hardware.org/?probe=3a045583a7) | Jun 25, 2023 |
| Acer          | Aspire A517-51              | [7f4ad14efb](https://linux-hardware.org/?probe=7f4ad14efb) | Jun 25, 2023 |
| Lenovo        | G580                        | [daa41583f5](https://linux-hardware.org/?probe=daa41583f5) | Jun 25, 2023 |
| Dell          | Inspiron N5110              | [0a3cfef2ce](https://linux-hardware.org/?probe=0a3cfef2ce) | Jun 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [39719594b9](https://linux-hardware.org/?probe=39719594b9) | Jun 24, 2023 |
| eMachines     | E725                        | [91c6056aff](https://linux-hardware.org/?probe=91c6056aff) | Jun 24, 2023 |
| Dell          | Inspiron 1720               | [60c2ef3b92](https://linux-hardware.org/?probe=60c2ef3b92) | Jun 24, 2023 |
| Lenovo        | ThinkPad X120e 0611AN2      | [a8420bc87d](https://linux-hardware.org/?probe=a8420bc87d) | Jun 24, 2023 |
| Timi          | RedmiBook Pro 14S           | [3910260d34](https://linux-hardware.org/?probe=3910260d34) | Jun 24, 2023 |
| Toshiba       | Satellite U300              | [2abf629721](https://linux-hardware.org/?probe=2abf629721) | Jun 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [e44e80fc33](https://linux-hardware.org/?probe=e44e80fc33) | Jun 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b6bc214e79](https://linux-hardware.org/?probe=b6bc214e79) | Jun 23, 2023 |
| HP            | 530 Notebook PC(KP479AA#... | [0c639de47d](https://linux-hardware.org/?probe=0c639de47d) | Jun 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [bb559685e3](https://linux-hardware.org/?probe=bb559685e3) | Jun 23, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [610b99a65b](https://linux-hardware.org/?probe=610b99a65b) | Jun 23, 2023 |
| Lenovo        | Legion Y540-15IRH Laptop... | [3f7008d282](https://linux-hardware.org/?probe=3f7008d282) | Jun 22, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [e8e25f684e](https://linux-hardware.org/?probe=e8e25f684e) | Jun 22, 2023 |
| Acer          | Aspire ES1-571              | [db93ddfd03](https://linux-hardware.org/?probe=db93ddfd03) | Jun 22, 2023 |
| Timi          | RedmiBook Pro 14S           | [f46c865218](https://linux-hardware.org/?probe=f46c865218) | Jun 22, 2023 |
| Lenovo        | B590 20206                  | [17fb06c810](https://linux-hardware.org/?probe=17fb06c810) | Jun 21, 2023 |
| Packard Be... | EasyNote TE69CX             | [d72fa50a56](https://linux-hardware.org/?probe=d72fa50a56) | Jun 21, 2023 |
| HP            | Unknown                     | [f7a4bc57b0](https://linux-hardware.org/?probe=f7a4bc57b0) | Jun 21, 2023 |
| Lenovo        | B50-70 20384                | [03450fe3f0](https://linux-hardware.org/?probe=03450fe3f0) | Jun 21, 2023 |
| Quanta        | TWH                         | [5d04c17be4](https://linux-hardware.org/?probe=5d04c17be4) | Jun 21, 2023 |
| Intel Clie... | LAPBC710                    | [6c97bec6f0](https://linux-hardware.org/?probe=6c97bec6f0) | Jun 21, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [dc5a63aacc](https://linux-hardware.org/?probe=dc5a63aacc) | Jun 20, 2023 |
| Acer          | Nitro AN515-45              | [b34b0bc6e5](https://linux-hardware.org/?probe=b34b0bc6e5) | Jun 20, 2023 |
| Lenovo        | K14 Gen 1 21CSS16E00        | [d60f0418a5](https://linux-hardware.org/?probe=d60f0418a5) | Jun 20, 2023 |
| HP            | Laptop 15-bw0xx             | [2e2c8b4c64](https://linux-hardware.org/?probe=2e2c8b4c64) | Jun 20, 2023 |
| ASUSTek       | K53SC                       | [1dee87098f](https://linux-hardware.org/?probe=1dee87098f) | Jun 20, 2023 |
| MSI           | Modern 14 B4MW              | [11edb8696f](https://linux-hardware.org/?probe=11edb8696f) | Jun 20, 2023 |
| MSI           | Modern 14 B4MW              | [2df6a58651](https://linux-hardware.org/?probe=2df6a58651) | Jun 20, 2023 |
| ASUSTek       | 1011CX                      | [0fa6b0b3dc](https://linux-hardware.org/?probe=0fa6b0b3dc) | Jun 19, 2023 |
| Acer          | Extensa 5630                | [b3abbec1ca](https://linux-hardware.org/?probe=b3abbec1ca) | Jun 19, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [2ac629a3ac](https://linux-hardware.org/?probe=2ac629a3ac) | Jun 19, 2023 |
| MSI           | GT70 2OC/2OD                | [adee2af879](https://linux-hardware.org/?probe=adee2af879) | Jun 19, 2023 |
| Apple         | MacBookPro7,1               | [0d56b62a99](https://linux-hardware.org/?probe=0d56b62a99) | Jun 19, 2023 |
| ASUSTek       | X200LA                      | [28ba5d9a3a](https://linux-hardware.org/?probe=28ba5d9a3a) | Jun 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [ce819ae3d3](https://linux-hardware.org/?probe=ce819ae3d3) | Jun 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [f3cbbb121e](https://linux-hardware.org/?probe=f3cbbb121e) | Jun 18, 2023 |
| ASUSTek       | X200LA                      | [5aca48b9ca](https://linux-hardware.org/?probe=5aca48b9ca) | Jun 18, 2023 |
| Aquarius      | NS483                       | [dd5daf7f12](https://linux-hardware.org/?probe=dd5daf7f12) | Jun 18, 2023 |
| HP            | Laptop 15-bw0xx             | [a161ef52b4](https://linux-hardware.org/?probe=a161ef52b4) | Jun 18, 2023 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [945376fe33](https://linux-hardware.org/?probe=945376fe33) | Jun 17, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [6b85997420](https://linux-hardware.org/?probe=6b85997420) | Jun 17, 2023 |
| MSI           | GX60 1AC                    | [64c48d22a7](https://linux-hardware.org/?probe=64c48d22a7) | Jun 17, 2023 |
| HP            | 630                         | [493010a411](https://linux-hardware.org/?probe=493010a411) | Jun 16, 2023 |
| HP            | Pavilion dv6                | [7e699d65f7](https://linux-hardware.org/?probe=7e699d65f7) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | [896d66d33f](https://linux-hardware.org/?probe=896d66d33f) | Jun 16, 2023 |
| Dell          | Latitude 3420               | [a0074970bf](https://linux-hardware.org/?probe=a0074970bf) | Jun 16, 2023 |
| TECNO         | MEGABOOK T1                 | [b26c331bfc](https://linux-hardware.org/?probe=b26c331bfc) | Jun 16, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | [06ce0448f5](https://linux-hardware.org/?probe=06ce0448f5) | Jun 16, 2023 |
| WeiBu         | OEM                         | [349908e6d0](https://linux-hardware.org/?probe=349908e6d0) | Jun 16, 2023 |
| ASUSTek       | X555LN                      | [1e46ee1872](https://linux-hardware.org/?probe=1e46ee1872) | Jun 16, 2023 |
| HP            | Laptop 15-bw0xx             | [baa9231329](https://linux-hardware.org/?probe=baa9231329) | Jun 15, 2023 |
| HONOR         | NMH-WCX9                    | [39b295867e](https://linux-hardware.org/?probe=39b295867e) | Jun 15, 2023 |
| HP            | EliteBook 845 14 inch G9... | [1360220387](https://linux-hardware.org/?probe=1360220387) | Jun 15, 2023 |
| HP            | EliteBook 845 14 inch G9... | [5ce34d4e94](https://linux-hardware.org/?probe=5ce34d4e94) | Jun 15, 2023 |
| HP            | EliteBook 845 14 inch G9... | [92482439de](https://linux-hardware.org/?probe=92482439de) | Jun 15, 2023 |
| HP            | ENVY Notebook               | [ee7a2ae915](https://linux-hardware.org/?probe=ee7a2ae915) | Jun 15, 2023 |
| HP            | ENVY Notebook               | [29828fefe2](https://linux-hardware.org/?probe=29828fefe2) | Jun 15, 2023 |
| HUAWEI        | HVY-WXX9                    | [8649d41483](https://linux-hardware.org/?probe=8649d41483) | Jun 15, 2023 |
| Unknown       | Unknown                     | [3a944bbbd5](https://linux-hardware.org/?probe=3a944bbbd5) | Jun 15, 2023 |
| Unknown       | Unknown                     | [581aba0aa2](https://linux-hardware.org/?probe=581aba0aa2) | Jun 15, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [ff2a2aeca0](https://linux-hardware.org/?probe=ff2a2aeca0) | Jun 15, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [fe83d43137](https://linux-hardware.org/?probe=fe83d43137) | Jun 15, 2023 |
| HONOR         | NMH-WCX9                    | [8515730b56](https://linux-hardware.org/?probe=8515730b56) | Jun 15, 2023 |
| Valve         | Jupiter                     | [dcf3ae5611](https://linux-hardware.org/?probe=dcf3ae5611) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [eba8248dae](https://linux-hardware.org/?probe=eba8248dae) | Jun 14, 2023 |
| Acer          | Aspire S3-391               | [0547c7bf3a](https://linux-hardware.org/?probe=0547c7bf3a) | Jun 14, 2023 |
| HONOR         | BBR-WAX9                    | [b980e4f162](https://linux-hardware.org/?probe=b980e4f162) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [6ef7b87ef5](https://linux-hardware.org/?probe=6ef7b87ef5) | Jun 14, 2023 |
| HP            | ProBook 430 G1              | [b972bb9890](https://linux-hardware.org/?probe=b972bb9890) | Jun 14, 2023 |
| MSI           | Katana GF66 12UE            | [49026cdaf3](https://linux-hardware.org/?probe=49026cdaf3) | Jun 14, 2023 |
| Toshiba       | Satellite L30               | [0b240892de](https://linux-hardware.org/?probe=0b240892de) | Jun 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | [5659761c9c](https://linux-hardware.org/?probe=5659761c9c) | Jun 14, 2023 |
| HP            | ProBook 455 G8 Notebook ... | [57b3c23d43](https://linux-hardware.org/?probe=57b3c23d43) | Jun 14, 2023 |
| Irbis         | NB123                       | [f6dae4c3c4](https://linux-hardware.org/?probe=f6dae4c3c4) | Jun 14, 2023 |
| Dell          | Inspiron 1501               | [456a49b146](https://linux-hardware.org/?probe=456a49b146) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [ee5c72c283](https://linux-hardware.org/?probe=ee5c72c283) | Jun 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [db48a7b38d](https://linux-hardware.org/?probe=db48a7b38d) | Jun 13, 2023 |
| HP            | Laptop 15s-eq1xxx           | [680fe3ebbf](https://linux-hardware.org/?probe=680fe3ebbf) | Jun 13, 2023 |
| HUAWEI        | HKF-WXX                     | [ad88913ce4](https://linux-hardware.org/?probe=ad88913ce4) | Jun 13, 2023 |
| Dell          | 500                         | [b220c5553e](https://linux-hardware.org/?probe=b220c5553e) | Jun 12, 2023 |
| Apple         | MacBookPro9,2               | [4a879a147e](https://linux-hardware.org/?probe=4a879a147e) | Jun 12, 2023 |
| Dell          | Inspiron N5110              | [dcae82c86f](https://linux-hardware.org/?probe=dcae82c86f) | Jun 12, 2023 |
| MSI           | Prestige 14Evo A12M         | [3e121c01dd](https://linux-hardware.org/?probe=3e121c01dd) | Jun 12, 2023 |
| Acer          | Extensa 5220                | [3f547b15a3](https://linux-hardware.org/?probe=3f547b15a3) | Jun 12, 2023 |
| ASUSTek       | X551CAP                     | [4076a43510](https://linux-hardware.org/?probe=4076a43510) | Jun 12, 2023 |
| Lenovo        | IdeaPad S10-2 20027         | [cd1619a50d](https://linux-hardware.org/?probe=cd1619a50d) | Jun 11, 2023 |
| Acer          | Aspire 5920G                | [2a5625ca4c](https://linux-hardware.org/?probe=2a5625ca4c) | Jun 11, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [4ecff82426](https://linux-hardware.org/?probe=4ecff82426) | Jun 11, 2023 |
| ASUSTek       | X75VC                       | [77cb4dfd02](https://linux-hardware.org/?probe=77cb4dfd02) | Jun 11, 2023 |
| Samsung       | P29/28/26                   | [d7e9b6f2f3](https://linux-hardware.org/?probe=d7e9b6f2f3) | Jun 11, 2023 |
| ASUSTek       | ZenBook UX334FAC_UX334FA    | [ba762c6d80](https://linux-hardware.org/?probe=ba762c6d80) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [8b88702b69](https://linux-hardware.org/?probe=8b88702b69) | Jun 11, 2023 |
| HP            | ProBook 470 G0              | [d3fdf73c3e](https://linux-hardware.org/?probe=d3fdf73c3e) | Jun 10, 2023 |
| Acer          | Aspire A517-51              | [01cfb1c93f](https://linux-hardware.org/?probe=01cfb1c93f) | Jun 10, 2023 |
| Samsung       | P29/28/26                   | [6040d56961](https://linux-hardware.org/?probe=6040d56961) | Jun 10, 2023 |
| WeiBu         | OEM                         | [49bd40f956](https://linux-hardware.org/?probe=49bd40f956) | Jun 10, 2023 |
| HUAWEI        | NBD-WXX9                    | [61c1703e67](https://linux-hardware.org/?probe=61c1703e67) | Jun 10, 2023 |
| HUAWEI        | NBD-WXX9                    | [321ad38786](https://linux-hardware.org/?probe=321ad38786) | Jun 10, 2023 |
| MACHENIKE     | F117-7P                     | [78ad896b83](https://linux-hardware.org/?probe=78ad896b83) | Jun 10, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2b4f40f41b](https://linux-hardware.org/?probe=2b4f40f41b) | Jun 09, 2023 |
| Dell          | Inspiron N5110              | [62d37454d3](https://linux-hardware.org/?probe=62d37454d3) | Jun 09, 2023 |
| Dell          | Latitude 5480               | [5b3fb0b4f8](https://linux-hardware.org/?probe=5b3fb0b4f8) | Jun 09, 2023 |
| Acer          | Aspire 5750G                | [69227c0908](https://linux-hardware.org/?probe=69227c0908) | Jun 09, 2023 |
| HUAWEI        | BOHB-WAX9                   | [aa0b439e8d](https://linux-hardware.org/?probe=aa0b439e8d) | Jun 09, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [e246e70bb6](https://linux-hardware.org/?probe=e246e70bb6) | Jun 09, 2023 |
| Acer          | Aspire A517-53              | [c14dcffa32](https://linux-hardware.org/?probe=c14dcffa32) | Jun 08, 2023 |
| Lenovo        | Unknown                     | [1842b75de0](https://linux-hardware.org/?probe=1842b75de0) | Jun 08, 2023 |
| Dell          | Vostro 1015                 | [dcd4a1ad41](https://linux-hardware.org/?probe=dcd4a1ad41) | Jun 08, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [13b0e73872](https://linux-hardware.org/?probe=13b0e73872) | Jun 08, 2023 |
| INFERIT       | Silver                      | [f6b3fc6762](https://linux-hardware.org/?probe=f6b3fc6762) | Jun 08, 2023 |
| Dell          | Inspiron 3558               | [87b5fd28c2](https://linux-hardware.org/?probe=87b5fd28c2) | Jun 08, 2023 |
| MSI           | GE60 2PL                    | [e1d118e2d2](https://linux-hardware.org/?probe=e1d118e2d2) | Jun 08, 2023 |
| HP            | G62                         | [fb9522ceac](https://linux-hardware.org/?probe=fb9522ceac) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | [c85cff4000](https://linux-hardware.org/?probe=c85cff4000) | Jun 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [292625f2da](https://linux-hardware.org/?probe=292625f2da) | Jun 08, 2023 |
| Sony          | VPCEH2E1R                   | [97e5366810](https://linux-hardware.org/?probe=97e5366810) | Jun 08, 2023 |
| Lenovo        | B590 20208                  | [102b3706f4](https://linux-hardware.org/?probe=102b3706f4) | Jun 08, 2023 |
| Machcreato... | 14                          | [d889b02b13](https://linux-hardware.org/?probe=d889b02b13) | Jun 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [6d434209eb](https://linux-hardware.org/?probe=6d434209eb) | Jun 07, 2023 |
| Maibenben     | MaiBook X series            | [5ca7ad5fb0](https://linux-hardware.org/?probe=5ca7ad5fb0) | Jun 07, 2023 |
| ASUSTek       | X205TA                      | [4c56663011](https://linux-hardware.org/?probe=4c56663011) | Jun 07, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [6e2a67c010](https://linux-hardware.org/?probe=6e2a67c010) | Jun 07, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [2e0b21f8d4](https://linux-hardware.org/?probe=2e0b21f8d4) | Jun 07, 2023 |
| HP            | Laptop 15s-eq1xxx           | [db91b1b71c](https://linux-hardware.org/?probe=db91b1b71c) | Jun 07, 2023 |
| Acer          | AOD257                      | [1b75b86659](https://linux-hardware.org/?probe=1b75b86659) | Jun 06, 2023 |
| HP            | Laptop 15s-eq1xxx           | [d2c05f91c4](https://linux-hardware.org/?probe=d2c05f91c4) | Jun 06, 2023 |
| Packard Be... | EasyNote TE69KB             | [d6f404ae63](https://linux-hardware.org/?probe=d6f404ae63) | Jun 06, 2023 |
| Machcreato... | 14                          | [f0a27a9f97](https://linux-hardware.org/?probe=f0a27a9f97) | Jun 06, 2023 |
| HP            | Pavilion 15                 | [d75a894e8c](https://linux-hardware.org/?probe=d75a894e8c) | Jun 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [be9987ca28](https://linux-hardware.org/?probe=be9987ca28) | Jun 06, 2023 |
| Dell          | G5 5587                     | [909f234c06](https://linux-hardware.org/?probe=909f234c06) | Jun 06, 2023 |
| Lenovo        | G70-70 80HW                 | [0d46480e90](https://linux-hardware.org/?probe=0d46480e90) | Jun 06, 2023 |
| Acer          | Swift SF314-511             | [60bf4b0442](https://linux-hardware.org/?probe=60bf4b0442) | Jun 05, 2023 |
| MSI           | Delta 15 A5EFK              | [d55fa44834](https://linux-hardware.org/?probe=d55fa44834) | Jun 05, 2023 |
| realme        | CloudProXXXX                | [22cced9066](https://linux-hardware.org/?probe=22cced9066) | Jun 05, 2023 |
| Aquarius      | NS585                       | [b3f11e4a53](https://linux-hardware.org/?probe=b3f11e4a53) | Jun 05, 2023 |
| HP            | EliteBook 2560p             | [3ed00534ed](https://linux-hardware.org/?probe=3ed00534ed) | Jun 05, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [2e429d02d1](https://linux-hardware.org/?probe=2e429d02d1) | Jun 05, 2023 |
| HP            | Mini 210-1000               | [96f41af422](https://linux-hardware.org/?probe=96f41af422) | Jun 05, 2023 |
| Samsung       | N102                        | [c3e402b50d](https://linux-hardware.org/?probe=c3e402b50d) | Jun 04, 2023 |
| HP            | Pavilion 15                 | [944c353c44](https://linux-hardware.org/?probe=944c353c44) | Jun 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [dfb8881ffe](https://linux-hardware.org/?probe=dfb8881ffe) | Jun 04, 2023 |
| Apple         | MacBookPro11,1              | [4192000802](https://linux-hardware.org/?probe=4192000802) | Jun 04, 2023 |
| Samsung       | 305V4A/305V5A/3415VA        | [a0f9cde008](https://linux-hardware.org/?probe=a0f9cde008) | Jun 04, 2023 |
| Apple         | MacBookPro11,1              | [168fa7f541](https://linux-hardware.org/?probe=168fa7f541) | Jun 04, 2023 |
| Lenovo        | V560                        | [b2564e07cc](https://linux-hardware.org/?probe=b2564e07cc) | Jun 03, 2023 |
| Valve         | Jupiter                     | [fdfee4fc99](https://linux-hardware.org/?probe=fdfee4fc99) | Jun 03, 2023 |
| Maibenben     | MaiBook M                   | [b5d7957b55](https://linux-hardware.org/?probe=b5d7957b55) | Jun 03, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [5d6b08920f](https://linux-hardware.org/?probe=5d6b08920f) | Jun 03, 2023 |
| Valve         | Jupiter                     | [cf26028872](https://linux-hardware.org/?probe=cf26028872) | Jun 03, 2023 |
| Acer          | Aspire S3                   | [23c1a32b88](https://linux-hardware.org/?probe=23c1a32b88) | Jun 03, 2023 |
| Samsung       | N102                        | [b21ddf3fea](https://linux-hardware.org/?probe=b21ddf3fea) | Jun 03, 2023 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | [88c3440ff2](https://linux-hardware.org/?probe=88c3440ff2) | Jun 03, 2023 |
| Dell          | Inspiron 1525               | [3160e89723](https://linux-hardware.org/?probe=3160e89723) | Jun 03, 2023 |
| ASUSTek       | X556UQ                      | [088518df2b](https://linux-hardware.org/?probe=088518df2b) | Jun 02, 2023 |
| HUAWEI        | BOD-WXX9                    | [532dea434a](https://linux-hardware.org/?probe=532dea434a) | Jun 02, 2023 |
| HP            | ENVY Notebook               | [e7f4c63499](https://linux-hardware.org/?probe=e7f4c63499) | Jun 02, 2023 |
| DEXP          | Aquilon C15                 | [763c923576](https://linux-hardware.org/?probe=763c923576) | Jun 02, 2023 |
| Aquarius      | NS585                       | [6f93385917](https://linux-hardware.org/?probe=6f93385917) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [6ae18b11ab](https://linux-hardware.org/?probe=6ae18b11ab) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [05a99cf128](https://linux-hardware.org/?probe=05a99cf128) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [963b30ca7f](https://linux-hardware.org/?probe=963b30ca7f) | Jun 02, 2023 |
| Aquarius      | NS585                       | [091267ec3a](https://linux-hardware.org/?probe=091267ec3a) | Jun 02, 2023 |
| Aquarius      | NS585                       | [7534819f94](https://linux-hardware.org/?probe=7534819f94) | Jun 02, 2023 |
| Lenovo        | S40-70 80GQ                 | [9a3fbc7388](https://linux-hardware.org/?probe=9a3fbc7388) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [23e94c534e](https://linux-hardware.org/?probe=23e94c534e) | Jun 01, 2023 |
| HP            | EliteBook 840 G6            | [81ec1cc134](https://linux-hardware.org/?probe=81ec1cc134) | Jun 01, 2023 |
| Timi          | RedmiBook Pro 15S           | [1708ebae47](https://linux-hardware.org/?probe=1708ebae47) | Jun 01, 2023 |
| Aquarius      | NS585                       | [ffa7425b95](https://linux-hardware.org/?probe=ffa7425b95) | Jun 01, 2023 |
| MSI           | GF63 Thin 11SC              | [8f8afcc010](https://linux-hardware.org/?probe=8f8afcc010) | Jun 01, 2023 |
| Aquarius      | NS585                       | [fafcbbe90e](https://linux-hardware.org/?probe=fafcbbe90e) | Jun 01, 2023 |
| Dell          | Latitude 5490               | [34dde30b90](https://linux-hardware.org/?probe=34dde30b90) | Jun 01, 2023 |
| ASUSTek       | X550CC                      | [d75bfc397f](https://linux-hardware.org/?probe=d75bfc397f) | Jun 01, 2023 |
| Timi          | TM1801                      | [aa1db210df](https://linux-hardware.org/?probe=aa1db210df) | Jun 01, 2023 |
| Lenovo        | K14 Gen 1 21CSS16E00        | [9c95ad4263](https://linux-hardware.org/?probe=9c95ad4263) | May 31, 2023 |
| Acer          | Aspire 4810T                | [3058ac9018](https://linux-hardware.org/?probe=3058ac9018) | May 31, 2023 |
| Apple         | MacBookPro16,1              | [717c7884c8](https://linux-hardware.org/?probe=717c7884c8) | May 31, 2023 |
| Acer          | Aspire ES1-523              | [d68236f41d](https://linux-hardware.org/?probe=d68236f41d) | May 31, 2023 |
| Dell          | Latitude 5411               | [8583aa2091](https://linux-hardware.org/?probe=8583aa2091) | May 31, 2023 |
| HP            | EliteBook 840 G3            | [384ebf87a3](https://linux-hardware.org/?probe=384ebf87a3) | May 31, 2023 |
| HP            | Laptop 15-gw0xxx            | [ebc3d97429](https://linux-hardware.org/?probe=ebc3d97429) | May 30, 2023 |
| HP            | Laptop 15-gw0xxx            | [97382e45f8](https://linux-hardware.org/?probe=97382e45f8) | May 30, 2023 |
| HP            | Laptop 17-ca0xxx            | [3222c41173](https://linux-hardware.org/?probe=3222c41173) | May 30, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [d20ebd68c0](https://linux-hardware.org/?probe=d20ebd68c0) | May 30, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [85a2504037](https://linux-hardware.org/?probe=85a2504037) | May 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | [7ab8c72481](https://linux-hardware.org/?probe=7ab8c72481) | May 30, 2023 |
| ICL           | RAYbook Si1407              | [5956bb96ff](https://linux-hardware.org/?probe=5956bb96ff) | May 30, 2023 |
| Acer          | Swift SF114-34              | [3722c76b10](https://linux-hardware.org/?probe=3722c76b10) | May 30, 2023 |
| Lenovo        | G570 20079                  | [4843789a62](https://linux-hardware.org/?probe=4843789a62) | May 30, 2023 |
| HP            | ProBook 440 G7              | [9da720226e](https://linux-hardware.org/?probe=9da720226e) | May 30, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c0e9edd453](https://linux-hardware.org/?probe=c0e9edd453) | May 30, 2023 |
| MSI           | GE60 2PC                    | [48c124853f](https://linux-hardware.org/?probe=48c124853f) | May 30, 2023 |
| ASUSTek       | X550WA                      | [864236b0c9](https://linux-hardware.org/?probe=864236b0c9) | May 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [3933dfe4f0](https://linux-hardware.org/?probe=3933dfe4f0) | May 29, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [a786eb985d](https://linux-hardware.org/?probe=a786eb985d) | May 29, 2023 |
| ASUSTek       | GL553VD                     | [a1f825f4e5](https://linux-hardware.org/?probe=a1f825f4e5) | May 29, 2023 |
| HP            | ProBook 440 G6              | [35d14ed328](https://linux-hardware.org/?probe=35d14ed328) | May 29, 2023 |
| HP            | ProBook 440 G6              | [36a3563566](https://linux-hardware.org/?probe=36a3563566) | May 29, 2023 |
| ICL-KME CS    | RAYbook                     | [9e976ffc1a](https://linux-hardware.org/?probe=9e976ffc1a) | May 29, 2023 |
| HP            | Laptop 17-ca0xxx            | [4b53ed4ede](https://linux-hardware.org/?probe=4b53ed4ede) | May 29, 2023 |
| Acer          | Swift SF114-34              | [b7be0bf5ad](https://linux-hardware.org/?probe=b7be0bf5ad) | May 29, 2023 |
| HONOR         | BBR-WAX9                    | [e57b9850f8](https://linux-hardware.org/?probe=e57b9850f8) | May 28, 2023 |
| Acer          | Aspire V3-571G              | [d3afe375cf](https://linux-hardware.org/?probe=d3afe375cf) | May 28, 2023 |
| Maibenben     | MaiBook M                   | [fa3f4694ba](https://linux-hardware.org/?probe=fa3f4694ba) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [86876e9715](https://linux-hardware.org/?probe=86876e9715) | May 28, 2023 |
| HIPER Tech... | HIPER WORKBOOK              | [8283b1247f](https://linux-hardware.org/?probe=8283b1247f) | May 28, 2023 |
| LTD Delovo... | EVE 14 C414                 | [d52f6c1303](https://linux-hardware.org/?probe=d52f6c1303) | May 28, 2023 |
| Unknown       | Unknown                     | [b294c91e3a](https://linux-hardware.org/?probe=b294c91e3a) | May 28, 2023 |
| Lenovo        | IdeaPad Z570 1024CPU        | [eb1c70f7af](https://linux-hardware.org/?probe=eb1c70f7af) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | [fb534d212e](https://linux-hardware.org/?probe=fb534d212e) | May 28, 2023 |
| MSI           | Katana GF76 12UGSO          | [6b753016ff](https://linux-hardware.org/?probe=6b753016ff) | May 28, 2023 |
| ASUSTek       | ROG Strix G634JY_G634JY     | [026cf06ce5](https://linux-hardware.org/?probe=026cf06ce5) | May 27, 2023 |
| HP            | Laptop 15s-fq5xxx           | [c6309fc374](https://linux-hardware.org/?probe=c6309fc374) | May 27, 2023 |
| Infinix       | INBOOK X2                   | [1f8b536f4f](https://linux-hardware.org/?probe=1f8b536f4f) | May 27, 2023 |
| Acer          | Aspire A517-51G             | [bfc89878ce](https://linux-hardware.org/?probe=bfc89878ce) | May 27, 2023 |
| Aquarius      | NS585                       | [a87c8d46b6](https://linux-hardware.org/?probe=a87c8d46b6) | May 27, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [4662e37743](https://linux-hardware.org/?probe=4662e37743) | May 26, 2023 |
| Samsung       | N130                        | [bd37239d10](https://linux-hardware.org/?probe=bd37239d10) | May 26, 2023 |
| Timi          | TM1701                      | [94105aa58f](https://linux-hardware.org/?probe=94105aa58f) | May 26, 2023 |
| eMachines     | eME644G                     | [cde4d7b461](https://linux-hardware.org/?probe=cde4d7b461) | May 26, 2023 |
| eMachines     | E725                        | [a4be8012a8](https://linux-hardware.org/?probe=a4be8012a8) | May 26, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [d3ac4866d3](https://linux-hardware.org/?probe=d3ac4866d3) | May 26, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | [67b6a5e731](https://linux-hardware.org/?probe=67b6a5e731) | May 26, 2023 |
| ASUSTek       | G50VT                       | [6e4a2588b1](https://linux-hardware.org/?probe=6e4a2588b1) | May 26, 2023 |
| Acer          | Aspire V3-551               | [9d609ccd4a](https://linux-hardware.org/?probe=9d609ccd4a) | May 26, 2023 |
| Infinix       | INBOOK X2                   | [925318e521](https://linux-hardware.org/?probe=925318e521) | May 26, 2023 |
| Intel Clie... | LAPBC710                    | [7ed6d7079c](https://linux-hardware.org/?probe=7ed6d7079c) | May 26, 2023 |
| Unknown       | Unknown                     | [b63a3cbd7b](https://linux-hardware.org/?probe=b63a3cbd7b) | May 25, 2023 |
| Unknown       | Unknown                     | [3db7516231](https://linux-hardware.org/?probe=3db7516231) | May 25, 2023 |
| ASUSTek       | X502CA                      | [7b19816353](https://linux-hardware.org/?probe=7b19816353) | May 25, 2023 |
| HP            | ProBook 4535s               | [bf141ba124](https://linux-hardware.org/?probe=bf141ba124) | May 25, 2023 |
| eMachines     | eME644G                     | [bc740da95e](https://linux-hardware.org/?probe=bc740da95e) | May 25, 2023 |
| Aquarius      | NS685U R11                  | [8e0050a63d](https://linux-hardware.org/?probe=8e0050a63d) | May 25, 2023 |
| Aquarius      | NS685U R11                  | [17191f57d3](https://linux-hardware.org/?probe=17191f57d3) | May 25, 2023 |
| Clevo         | NL41MU2                     | [41f9a8d4b1](https://linux-hardware.org/?probe=41f9a8d4b1) | May 25, 2023 |
| ASUSTek       | GL553VD                     | [51dbf3c463](https://linux-hardware.org/?probe=51dbf3c463) | May 25, 2023 |
| Acer          | Aspire A515-45G             | [99bcbfbb2a](https://linux-hardware.org/?probe=99bcbfbb2a) | May 25, 2023 |
| Aquarius      | NS585                       | [82a0d45251](https://linux-hardware.org/?probe=82a0d45251) | May 25, 2023 |
| HONOR         | HYM-WXX                     | [00a5e48ef4](https://linux-hardware.org/?probe=00a5e48ef4) | May 25, 2023 |
| Acer          | Aspire 7750G                | [589639a63f](https://linux-hardware.org/?probe=589639a63f) | May 25, 2023 |
| Timi          | TM1701                      | [c883337466](https://linux-hardware.org/?probe=c883337466) | May 24, 2023 |
| Acer          | Aspire E5-573G              | [c6cc5e2a20](https://linux-hardware.org/?probe=c6cc5e2a20) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [fb5edbbd6b](https://linux-hardware.org/?probe=fb5edbbd6b) | May 24, 2023 |
| Acer          | Extensa 5630                | [00e8bb4d6a](https://linux-hardware.org/?probe=00e8bb4d6a) | May 24, 2023 |
| HUAWEI        | BOD-WXX9                    | [9486b7ca4f](https://linux-hardware.org/?probe=9486b7ca4f) | May 24, 2023 |
| Samsung       | R710                        | [a2c199b3cd](https://linux-hardware.org/?probe=a2c199b3cd) | May 24, 2023 |
| Packard Be... | DOT S                       | [a49bbc7aa2](https://linux-hardware.org/?probe=a49bbc7aa2) | May 24, 2023 |
| DEXP          | Aquilon C14                 | [357a7caaf8](https://linux-hardware.org/?probe=357a7caaf8) | May 24, 2023 |
| DEXP          | Aquilon C14                 | [cd3dc35687](https://linux-hardware.org/?probe=cd3dc35687) | May 24, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [a03284052b](https://linux-hardware.org/?probe=a03284052b) | May 24, 2023 |
| ASUSTek       | UL30A                       | [d7ab3b0ed3](https://linux-hardware.org/?probe=d7ab3b0ed3) | May 24, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [dd1104fc5a](https://linux-hardware.org/?probe=dd1104fc5a) | May 23, 2023 |
| Unknown       | Unknown                     | [6680332a54](https://linux-hardware.org/?probe=6680332a54) | May 23, 2023 |
| HUAWEI        | CREF-XX                     | [39ff25bc94](https://linux-hardware.org/?probe=39ff25bc94) | May 23, 2023 |
| ASUSTek       | N53SM                       | [95301f4dea](https://linux-hardware.org/?probe=95301f4dea) | May 23, 2023 |
| Dell          | Inspiron N5110              | [a410c18f8c](https://linux-hardware.org/?probe=a410c18f8c) | May 23, 2023 |
| ASUSTek       | ET2321I                     | [829fe9b078](https://linux-hardware.org/?probe=829fe9b078) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [374ccaecd9](https://linux-hardware.org/?probe=374ccaecd9) | May 22, 2023 |
| Acer          | Nitro AN515-46              | [702a597b36](https://linux-hardware.org/?probe=702a597b36) | May 22, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6ca579ee78](https://linux-hardware.org/?probe=6ca579ee78) | May 22, 2023 |
| HP            | EliteBook 8440p             | [3ad250d762](https://linux-hardware.org/?probe=3ad250d762) | May 22, 2023 |
| Acer          | Nitro AN515-45              | [179e48239b](https://linux-hardware.org/?probe=179e48239b) | May 22, 2023 |
| Valve         | Jupiter                     | [0a03a5a40a](https://linux-hardware.org/?probe=0a03a5a40a) | May 22, 2023 |
| ASUSTek       | X550CC                      | [8226c82b49](https://linux-hardware.org/?probe=8226c82b49) | May 21, 2023 |
| ASUSTek       | X550CC                      | [6a8e6201be](https://linux-hardware.org/?probe=6a8e6201be) | May 21, 2023 |
| Lenovo        | Unknown                     | [1288108e10](https://linux-hardware.org/?probe=1288108e10) | May 21, 2023 |
| Unknown       | X133                        | [52cd0be8f5](https://linux-hardware.org/?probe=52cd0be8f5) | May 21, 2023 |
| HP            | Laptop 17-by3xxx            | [7f15c1b9e3](https://linux-hardware.org/?probe=7f15c1b9e3) | May 21, 2023 |
| Dell          | Inspiron N5110              | [279141fa2a](https://linux-hardware.org/?probe=279141fa2a) | May 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [47ab72fc6c](https://linux-hardware.org/?probe=47ab72fc6c) | May 20, 2023 |
| HASEE Comp... | V1x0PNPx                    | [ce5f16dcfe](https://linux-hardware.org/?probe=ce5f16dcfe) | May 20, 2023 |
| Dell          | Inspiron 3542               | [166b73ef05](https://linux-hardware.org/?probe=166b73ef05) | May 20, 2023 |
| ASUSTek       | K53SC                       | [d2ddb09cc1](https://linux-hardware.org/?probe=d2ddb09cc1) | May 20, 2023 |
| Apple         | MacBookPro9,2               | [ac3d3ea87c](https://linux-hardware.org/?probe=ac3d3ea87c) | May 19, 2023 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [a51baad28a](https://linux-hardware.org/?probe=a51baad28a) | May 19, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2402CBA... | [13d783ec86](https://linux-hardware.org/?probe=13d783ec86) | May 19, 2023 |
| Valve         | Jupiter                     | [7d600a9c24](https://linux-hardware.org/?probe=7d600a9c24) | May 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [39fa0ce7e9](https://linux-hardware.org/?probe=39fa0ce7e9) | May 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [d51c5680e8](https://linux-hardware.org/?probe=d51c5680e8) | May 19, 2023 |
| HP            | Laptop 17-ca0xxx            | [c1f8fc5eed](https://linux-hardware.org/?probe=c1f8fc5eed) | May 19, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [7f35aa414f](https://linux-hardware.org/?probe=7f35aa414f) | May 18, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [08df098150](https://linux-hardware.org/?probe=08df098150) | May 18, 2023 |
| HP            | Laptop 15-bs1xx             | [0517273b27](https://linux-hardware.org/?probe=0517273b27) | May 18, 2023 |
| Aquarius      | NS585                       | [dc2b351b40](https://linux-hardware.org/?probe=dc2b351b40) | May 18, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [fdb0fb3d9c](https://linux-hardware.org/?probe=fdb0fb3d9c) | May 18, 2023 |
| HONOR         | HLYL-WXX9                   | [01a49c336d](https://linux-hardware.org/?probe=01a49c336d) | May 18, 2023 |
| HP            | Laptop 17-ca0xxx            | [f93ee0d717](https://linux-hardware.org/?probe=f93ee0d717) | May 17, 2023 |
| Aquarius      | NS685U R11                  | [23e33588a8](https://linux-hardware.org/?probe=23e33588a8) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAS... | [2df1a28c50](https://linux-hardware.org/?probe=2df1a28c50) | May 17, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21BAA... | [5e4e802b87](https://linux-hardware.org/?probe=5e4e802b87) | May 17, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | [429d4451c9](https://linux-hardware.org/?probe=429d4451c9) | May 16, 2023 |
| ASUSTek       | K53TA                       | [9700522405](https://linux-hardware.org/?probe=9700522405) | May 16, 2023 |
| HP            | ENVY dv6                    | [2490803f28](https://linux-hardware.org/?probe=2490803f28) | May 16, 2023 |
| Digma         | EVE 11 C422 ES1068EW        | [21255b70aa](https://linux-hardware.org/?probe=21255b70aa) | May 16, 2023 |
| Acer          | AOD257                      | [421fde4e9b](https://linux-hardware.org/?probe=421fde4e9b) | May 16, 2023 |
| Samsung       | R780                        | [5862ae2996](https://linux-hardware.org/?probe=5862ae2996) | May 16, 2023 |
| Samsung       | R780                        | [1fc01590bb](https://linux-hardware.org/?probe=1fc01590bb) | May 16, 2023 |
| ASUSTek       | X550CC                      | [cce2c46f1e](https://linux-hardware.org/?probe=cce2c46f1e) | May 16, 2023 |
| ASUSTek       | K53TA                       | [57a36429fe](https://linux-hardware.org/?probe=57a36429fe) | May 15, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [2b6c863711](https://linux-hardware.org/?probe=2b6c863711) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [2ffc331e90](https://linux-hardware.org/?probe=2ffc331e90) | May 15, 2023 |
| Samsung       | R428/P428                   | [1d93335f58](https://linux-hardware.org/?probe=1d93335f58) | May 15, 2023 |
| Toshiba       | Satellite L755              | [ec59045a15](https://linux-hardware.org/?probe=ec59045a15) | May 15, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [acd8d0441a](https://linux-hardware.org/?probe=acd8d0441a) | May 15, 2023 |
| ASUSTek       | GL703VD                     | [6de826cbe5](https://linux-hardware.org/?probe=6de826cbe5) | May 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [f8f9a6dc69](https://linux-hardware.org/?probe=f8f9a6dc69) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7661V3L        | [5714171d2a](https://linux-hardware.org/?probe=5714171d2a) | May 14, 2023 |
| Acer          | Aspire V5-552G              | [4384294484](https://linux-hardware.org/?probe=4384294484) | May 14, 2023 |
| HP            | ProBook 6560b               | [e8f24791d1](https://linux-hardware.org/?probe=e8f24791d1) | May 14, 2023 |
| Acer          | TravelMate B113             | [b6a4ef5336](https://linux-hardware.org/?probe=b6a4ef5336) | May 14, 2023 |
| Acer          | TravelMate B113             | [c2e9fe6581](https://linux-hardware.org/?probe=c2e9fe6581) | May 14, 2023 |
| MSI           | GL62 6QF                    | [6ae5c650f3](https://linux-hardware.org/?probe=6ae5c650f3) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [72eaf980ad](https://linux-hardware.org/?probe=72eaf980ad) | May 14, 2023 |
| Unknown       | Unknown                     | [077df36551](https://linux-hardware.org/?probe=077df36551) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [ba47df6545](https://linux-hardware.org/?probe=ba47df6545) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [0b6c34eefa](https://linux-hardware.org/?probe=0b6c34eefa) | May 14, 2023 |
| Dell          | Inspiron 3520               | [675fc0ce85](https://linux-hardware.org/?probe=675fc0ce85) | May 14, 2023 |
| Irbis         | NB64                        | [a3dc2d6133](https://linux-hardware.org/?probe=a3dc2d6133) | May 13, 2023 |
| Irbis         | NB64                        | [369617cbf6](https://linux-hardware.org/?probe=369617cbf6) | May 13, 2023 |
| HP            | Laptop 15-bw0xx             | [10ee4f50b6](https://linux-hardware.org/?probe=10ee4f50b6) | May 13, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [7e178a2a32](https://linux-hardware.org/?probe=7e178a2a32) | May 13, 2023 |
| Apple         | MacBookPro8,1               | [cd0c59d678](https://linux-hardware.org/?probe=cd0c59d678) | May 13, 2023 |
| Packard Be... | EasyNote TK85               | [3d4b4e176a](https://linux-hardware.org/?probe=3d4b4e176a) | May 13, 2023 |
| Samsung       | R425/R525                   | [a7719ea5d3](https://linux-hardware.org/?probe=a7719ea5d3) | May 13, 2023 |
| HP            | Pavilion g6                 | [a86469b33f](https://linux-hardware.org/?probe=a86469b33f) | May 12, 2023 |
| HUAWEI        | CREM-WXX9                   | [b1b041ac47](https://linux-hardware.org/?probe=b1b041ac47) | May 12, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [29e584b980](https://linux-hardware.org/?probe=29e584b980) | May 12, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [22673e3f0c](https://linux-hardware.org/?probe=22673e3f0c) | May 12, 2023 |
| ASUSTek       | M51Sn                       | [94a426384a](https://linux-hardware.org/?probe=94a426384a) | May 12, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [2a93dcb797](https://linux-hardware.org/?probe=2a93dcb797) | May 12, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Russia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| ROSA R10         | 1494      | 10.5%   |
| ROSA R11         | 1444      | 10.14%  |
| ROSA R8.1        | 1042      | 7.32%   |
| ROSA R8          | 919       | 6.46%   |
| ROSA R9          | 846       | 5.94%   |
| ROSA R11.1       | 788       | 5.54%   |
| ROSA 12.2        | 782       | 5.49%   |
| Ubuntu 20.04     | 487       | 3.42%   |
| ROSA 12.3        | 353       | 2.48%   |
| ROSA 12.4        | 286       | 2.01%   |
| Debian 11        | 278       | 1.95%   |
| Ubuntu 18.04     | 256       | 1.8%    |
| Ubuntu 22.04     | 241       | 1.69%   |
| OpenMandriva 4.2 | 160       | 1.12%   |
| Arch Rolling     | 148       | 1.04%   |
| ROSA 12.1        | 116       | 0.81%   |
| KDE neon 20.04   | 104       | 0.73%   |
| Fedora 37        | 104       | 0.73%   |
| OpenMandriva 4.3 | 102       | 0.72%   |
| Arch             | 98        | 0.69%   |
| Manjaro          | 93        | 0.65%   |
| Fedora 36        | 93        | 0.65%   |
| Linux Mint 19.3  | 85        | 0.6%    |
| Debian 12        | 77        | 0.54%   |
| Fedora 38        | 75        | 0.53%   |
| Linux Mint 20.3  | 72        | 0.51%   |
| Fedora 35        | 71        | 0.5%    |
| Linux Mint 20.1  | 69        | 0.48%   |
| Kubuntu 20.04    | 63        | 0.44%   |
| Debian 10        | 60        | 0.42%   |
| Linux Mint 20    | 59        | 0.41%   |
| Linux Mint 19.1  | 59        | 0.41%   |
| Linux Mint 18.3  | 59        | 0.41%   |
| Fedora 34        | 57        | 0.4%    |
| ROSA 12          | 56        | 0.39%   |
| Linux Mint 19.2  | 55        | 0.39%   |
| Kometa P10       | 54        | 0.38%   |
| ALT Linux 10.1   | 54        | 0.38%   |
| Ubuntu 21.10     | 52        | 0.37%   |
| Linux Mint 21.1  | 50        | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| ROSA          | 6989      | 55.14%  |
| Ubuntu        | 1266      | 9.99%   |
| Linux Mint    | 646       | 5.1%    |
| Fedora        | 472       | 3.72%   |
| Debian        | 429       | 3.38%   |
| OpenMandriva  | 382       | 3.01%   |
| Manjaro       | 351       | 2.77%   |
| Arch          | 235       | 1.85%   |
| ALT Linux     | 232       | 1.83%   |
| Endless       | 216       | 1.7%    |
| Kubuntu       | 159       | 1.25%   |
| KDE neon      | 142       | 1.12%   |
| Xubuntu       | 125       | 0.99%   |
| Red OS        | 104       | 0.82%   |
| Pop!_OS       | 99        | 0.78%   |
| Kali          | 71        | 0.56%   |
| Elementary    | 64        | 0.5%    |
| Gentoo        | 63        | 0.5%    |
| openSUSE      | 53        | 0.42%   |
| Lubuntu       | 47        | 0.37%   |
| RED           | 46        | 0.36%   |
| LMDE          | 40        | 0.32%   |
| Zorin         | 38        | 0.3%    |
| Ubuntu MATE   | 33        | 0.26%   |
| Clear Linux   | 32        | 0.25%   |
| SteamOS       | 29        | 0.23%   |
| ArcoLinux     | 28        | 0.22%   |
| Ubuntu Unity  | 27        | 0.21%   |
| EndeavourOS   | 20        | 0.16%   |
| Astra Linux   | 15        | 0.12%   |
| Artix         | 15        | 0.12%   |
| Ubuntu Budgie | 13        | 0.1%    |
| Parrot        | 13        | 0.1%    |
| MX            | 13        | 0.1%    |
| CentOS        | 13        | 0.1%    |
| RELS          | 11        | 0.09%   |
| Void Linux    | 10        | 0.08%   |
| Devuan        | 9         | 0.07%   |
| Calculate     | 9         | 0.07%   |
| RELD          | 7         | 0.06%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 5.10.74-generic-2rosa2021.1-x86_64  | 665       | 4.35%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 621       | 4.06%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 621       | 4.06%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 586       | 3.83%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 349       | 2.28%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 278       | 1.82%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 275       | 1.8%    |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 236       | 1.54%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 218       | 1.42%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 200       | 1.31%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 194       | 1.27%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 175       | 1.14%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 175       | 1.14%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 174       | 1.14%   |
| 4.15.0-desktop-45.1rosa-i586        | 174       | 1.14%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 169       | 1.1%    |
| 5.10.14-desktop-1omv4002            | 155       | 1.01%   |
| 5.4.32-generic-2rosa-x86_64         | 147       | 0.96%   |
| 5.10.118-generic-2rosa2021.1-x86_64 | 147       | 0.96%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 147       | 0.96%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 146       | 0.95%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 138       | 0.9%    |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 138       | 0.9%    |
| 5.4.83-generic-2rosa-x86_64         | 136       | 0.89%   |
| 5.15.75-generic-1rosa2021.1-x86_64  | 120       | 0.78%   |
| 5.10.0-7-amd64                      | 110       | 0.72%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 107       | 0.7%    |
| 4.1.38-nrj-desktop-2rosa-i586       | 106       | 0.69%   |
| 5.15.79-generic-1rosa2021.1-x86_64  | 97        | 0.63%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 96        | 0.63%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 96        | 0.63%   |
| 5.16.7-desktop-1omv4003             | 91        | 0.59%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 90        | 0.59%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 78        | 0.51%   |
| 5.4.0-42-generic                    | 71        | 0.46%   |
| 6.1.38-generic-1rosa2021.1-x86_64   | 70        | 0.46%   |
| 4.15.0-desktop-60.7rosa-x86_64      | 69        | 0.45%   |
| 5.4.32-generic-2rosa-i586           | 62        | 0.41%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 59        | 0.39%   |
| 5.15.0-56-generic                   | 58        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 1893      | 12.77%  |
| 4.9.60   | 821       | 5.54%   |
| 4.9.20   | 763       | 5.15%   |
| 5.4.0    | 717       | 4.84%   |
| 5.10.74  | 698       | 4.71%   |
| 4.1.34   | 497       | 3.35%   |
| 5.15.0   | 417       | 2.81%   |
| 4.1.38   | 394       | 2.66%   |
| 4.9.9    | 374       | 2.52%   |
| 4.9.124  | 357       | 2.41%   |
| 5.10.0   | 329       | 2.22%   |
| 4.1.25   | 327       | 2.21%   |
| 5.3.0    | 251       | 1.69%   |
| 4.9.41   | 235       | 1.59%   |
| 4.9.76   | 230       | 1.55%   |
| 5.4.32   | 209       | 1.41%   |
| 5.11.0   | 209       | 1.41%   |
| 4.9.155  | 207       | 1.4%    |
| 5.13.0   | 206       | 1.39%   |
| 5.8.0    | 204       | 1.38%   |
| 6.1.20   | 201       | 1.36%   |
| 5.4.83   | 182       | 1.23%   |
| 5.0.0    | 170       | 1.15%   |
| 5.19.0   | 161       | 1.09%   |
| 5.10.14  | 158       | 1.07%   |
| 5.10.118 | 154       | 1.04%   |
| 5.15.75  | 149       | 1%      |
| 4.9.95   | 124       | 0.84%   |
| 6.1.0    | 107       | 0.72%   |
| 5.15.79  | 101       | 0.68%   |
| 4.18.0   | 95        | 0.64%   |
| 5.16.7   | 93        | 0.63%   |
| 4.13.0   | 93        | 0.63%   |
| 4.9.111  | 81        | 0.55%   |
| 6.1.38   | 79        | 0.53%   |
| 6.2.0    | 77        | 0.52%   |
| 4.19.0   | 73        | 0.49%   |
| 6.2.6    | 65        | 0.44%   |
| 4.9.87   | 58        | 0.39%   |
| 6.1.1    | 45        | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 2898      | 20.75%  |
| 4.15    | 1908      | 13.66%  |
| 5.10    | 1633      | 11.69%  |
| 5.4     | 1239      | 8.87%   |
| 4.1     | 1200      | 8.59%   |
| 5.15    | 1031      | 7.38%   |
| 6.1     | 543       | 3.89%   |
| 5.3     | 291       | 2.08%   |
| 5.11    | 277       | 1.98%   |
| 5.13    | 266       | 1.9%    |
| 5.8     | 264       | 1.89%   |
| 6.2     | 221       | 1.58%   |
| 5.19    | 221       | 1.58%   |
| 5.0     | 178       | 1.27%   |
| 5.16    | 168       | 1.2%    |
| 6.0     | 145       | 1.04%   |
| 5.17    | 130       | 0.93%   |
| 5.18    | 118       | 0.84%   |
| 4.19    | 114       | 0.82%   |
| 4.18    | 110       | 0.79%   |
| 4.13    | 109       | 0.78%   |
| 5.14    | 99        | 0.71%   |
| 6.4     | 97        | 0.69%   |
| 5.6     | 88        | 0.63%   |
| 6.3     | 71        | 0.51%   |
| 5.9     | 69        | 0.49%   |
| 5.7     | 50        | 0.36%   |
| 4.4     | 50        | 0.36%   |
| 4.16    | 50        | 0.36%   |
| 5.12    | 48        | 0.34%   |
| 5.5     | 41        | 0.29%   |
| 4.8     | 37        | 0.26%   |
| 4.10    | 35        | 0.25%   |
| 3.14    | 20        | 0.14%   |
| 4.14    | 19        | 0.14%   |
| 5.2     | 18        | 0.13%   |
| 3.10    | 16        | 0.11%   |
| 4.17    | 14        | 0.1%    |
| 4.12    | 13        | 0.09%   |
| 5.1     | 12        | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 10771     | 86.4%   |
| i686    | 1688      | 13.54%  |
| armv7l  | 6         | 0.05%   |
| ppc     | 1         | 0.01%   |
| aarch64 | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| KDE4               | 4160      | 31.5%   |
| KDE5               | 3414      | 25.85%  |
| GNOME              | 2559      | 19.38%  |
| Unknown            | 738       | 5.59%   |
| XFCE               | 524       | 3.97%   |
| LXQt               | 458       | 3.47%   |
| MATE               | 361       | 2.73%   |
| X-Cinnamon         | 293       | 2.22%   |
| Cinnamon           | 253       | 1.92%   |
| KDE                | 166       | 1.26%   |
| Pantheon           | 61        | 0.46%   |
| i3                 | 41        | 0.31%   |
| LXDE               | 34        | 0.26%   |
| Unity              | 27        | 0.2%    |
| Budgie             | 26        | 0.2%    |
| GNOME Flashback    | 18        | 0.14%   |
| sway               | 13        | 0.1%    |
| fly                | 10        | 0.08%   |
| Deepin             | 8         | 0.06%   |
| awesome            | 6         | 0.05%   |
| Trinity            | 4         | 0.03%   |
| icewm              | 4         | 0.03%   |
| fluxbox            | 4         | 0.03%   |
| DWM                | 4         | 0.03%   |
| bspwm              | 4         | 0.03%   |
| openbox            | 3         | 0.02%   |
| GNOME Classic      | 3         | 0.02%   |
| xmonad             | 2         | 0.02%   |
| Hyprland           | 2         | 0.02%   |
| qtile              | 1         | 0.01%   |
| pantheon-non-gnome | 1         | 0.01%   |
| none+i3            | 1         | 0.01%   |
| Lumina             | 1         | 0.01%   |
| Lubuntu            | 1         | 0.01%   |
| lightdm-xsession   | 1         | 0.01%   |
| Enlightenment      | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| X11         | 9996      | 78.75%  |
| Wayland     | 2179      | 17.17%  |
| Unknown     | 427       | 3.36%   |
| Tty         | 90        | 0.71%   |
| Web         | 1         | 0.01%   |
| Unspecified | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDM     | 4179      | 31.73%  |
| SDDM    | 3482      | 26.44%  |
| Unknown | 2245      | 17.05%  |
| GDM     | 1586      | 12.04%  |
| LightDM | 740       | 5.62%   |
| GDM3    | 440       | 3.34%   |
| TDM     | 433       | 3.29%   |
| MDM     | 21        | 0.16%   |
| XDM     | 17        | 0.13%   |
| SLiM    | 9         | 0.07%   |
| FLY-DM  | 5         | 0.04%   |
| NODM    | 3         | 0.02%   |
| Ly      | 3         | 0.02%   |
| LXDM    | 3         | 0.02%   |
| GREETD  | 3         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 5817      | 45.4%   |
| ru_RU       | 5388      | 42.05%  |
| en_US       | 1397      | 10.9%   |
| C           | 74        | 0.58%   |
| en_GB       | 55        | 0.43%   |
| ru_RU.UTF_8 | 19        | 0.15%   |
| ru_UA       | 9         | 0.07%   |
| POSIX       | 5         | 0.04%   |
| en_AG       | 5         | 0.04%   |
| zh_CN       | 4         | 0.03%   |
| C.UTF8      | 4         | 0.03%   |
| en_DK       | 3         | 0.02%   |
| en_CA       | 3         | 0.02%   |
| de_DE       | 3         | 0.02%   |
| ba_RU       | 3         | 0.02%   |
| uk_UA       | 2         | 0.02%   |
| tr_TR       | 2         | 0.02%   |
| pt_BR       | 2         | 0.02%   |
| it_IT       | 2         | 0.02%   |
| fr_FR       | 2         | 0.02%   |
| es_ES       | 2         | 0.02%   |
| cv_RU       | 2         | 0.02%   |
| tt_RU       | 1         | 0.01%   |
| ru_RU.UTF8  | 1         | 0.01%   |
| ru_RU.utf-8 | 1         | 0.01%   |
| myv_RU      | 1         | 0.01%   |
| ja_JP       | 1         | 0.01%   |
| en_NZ       | 1         | 0.01%   |
| en_IL       | 1         | 0.01%   |
| en_GB.utf-8 | 1         | 0.01%   |
| en_AU       | 1         | 0.01%   |
| en-US       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 7109      | 56.48%  |
| EFI  | 5477      | 43.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 7824      | 60.12%  |
| Unknown  | 3579      | 27.5%   |
| Btrfs    | 821       | 6.31%   |
| Overlay  | 564       | 4.33%   |
| Xfs      | 65        | 0.5%    |
| Tmpfs    | 54        | 0.41%   |
| Zfs      | 27        | 0.21%   |
| Ext3     | 21        | 0.16%   |
| Ext2     | 20        | 0.15%   |
| Aufs     | 17        | 0.13%   |
| F2fs     | 12        | 0.09%   |
| Rootfs   | 3         | 0.02%   |
| Reiserfs | 3         | 0.02%   |
| XXXXXXX  | 1         | 0.01%   |
| XXXXX    | 1         | 0.01%   |
| Ufs      | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 4720      | 36.32%  |
| GPT     | 4640      | 35.7%   |
| Unknown | 3636      | 27.98%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 11218     | 88.34%  |
| Yes       | 1480      | 11.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 9211      | 71.96%  |
| Yes       | 3589      | 28.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 2241      | 18.17%  |
| ASUSTek Computer    | 2180      | 17.67%  |
| Hewlett-Packard     | 1772      | 14.36%  |
| Acer                | 1680      | 13.62%  |
| Dell                | 860       | 6.97%   |
| Samsung Electronics | 666       | 5.4%    |
| MSI                 | 321       | 2.6%    |
| Toshiba             | 299       | 2.42%   |
| Sony                | 272       | 2.2%    |
| HUAWEI              | 237       | 1.92%   |
| Packard Bell        | 179       | 1.45%   |
| eMachines           | 119       | 0.96%   |
| Clevo               | 107       | 0.87%   |
| Unknown             | 107       | 0.87%   |
| Timi                | 101       | 0.82%   |
| Apple               | 100       | 0.81%   |
| Aquarius            | 82        | 0.66%   |
| Notebook            | 78        | 0.63%   |
| Pegatron            | 62        | 0.5%    |
| HONOR               | 56        | 0.45%   |
| Digma               | 48        | 0.39%   |
| Fujitsu Siemens     | 46        | 0.37%   |
| Fujitsu             | 39        | 0.32%   |
| DNS                 | 39        | 0.32%   |
| Irbis               | 36        | 0.29%   |
| Intel               | 36        | 0.29%   |
| DEXP                | 32        | 0.26%   |
| Quanta              | 31        | 0.25%   |
| Valve               | 30        | 0.24%   |
| Prestigio           | 29        | 0.24%   |
| ICL                 | 29        | 0.24%   |
| Maibenben           | 28        | 0.23%   |
| Chuwi               | 25        | 0.2%    |
| Gigabyte Technology | 21        | 0.17%   |
| Haier               | 19        | 0.15%   |
| 3Logic Group        | 17        | 0.14%   |
| Insyde              | 13        | 0.11%   |
| Infinix             | 13        | 0.11%   |
| Panasonic           | 12        | 0.1%    |
| Infomash            | 11        | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 183       | 1.48%   |
| HP Pavilion g6                             | 126       | 1.02%   |
| HP Pavilion dv6                            | 82        | 0.66%   |
| HP Notebook                                | 82        | 0.66%   |
| HP Laptop 15-bw0xx                         | 76        | 0.62%   |
| Acer Aspire V3-571G                        | 63        | 0.51%   |
| Lenovo G570 20079                          | 54        | 0.44%   |
| Aquarius NS585                             | 50        | 0.41%   |
| Lenovo B570e HuronRiver Platform           | 47        | 0.38%   |
| Lenovo B590 20206                          | 46        | 0.37%   |
| HP Pavilion dv7                            | 42        | 0.34%   |
| Packard Bell EasyNote TE11HC               | 40        | 0.32%   |
| HP Pavilion 15                             | 40        | 0.32%   |
| Lenovo B590 20208                          | 38        | 0.31%   |
| Clevo NL41MU2                              | 37        | 0.3%    |
| Lenovo G50-45 80E3                         | 36        | 0.29%   |
| HUAWEI NBLK-WAX9X                          | 35        | 0.28%   |
| Lenovo G500 20236                          | 34        | 0.28%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 33        | 0.27%   |
| Dell Inspiron N5110                        | 33        | 0.27%   |
| Toshiba Satellite C660                     | 32        | 0.26%   |
| Lenovo G50-30 80G0                         | 32        | 0.26%   |
| HP Pavilion g7                             | 32        | 0.26%   |
| ASUS X550CC                                | 32        | 0.26%   |
| Lenovo B560                                | 31        | 0.25%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 31        | 0.25%   |
| Valve Jupiter                              | 30        | 0.24%   |
| Lenovo G580 20150                          | 30        | 0.24%   |
| ASUS K50IJ                                 | 30        | 0.24%   |
| Acer Aspire 5750G                          | 30        | 0.24%   |
| Samsung 355V4C/356V4C/3445VC/3545VC        | 29        | 0.24%   |
| Lenovo G580 20157                          | 29        | 0.24%   |
| Acer Aspire E1-571G                        | 29        | 0.24%   |
| Acer Aspire 5742G                          | 28        | 0.23%   |
| Samsung 300E4C/300E5C/300E7C               | 27        | 0.22%   |
| Dell Inspiron 3521                         | 26        | 0.21%   |
| Acer Extensa 2519                          | 26        | 0.21%   |
| HP Pavilion Notebook                       | 25        | 0.2%    |
| Dell Inspiron 3542                         | 25        | 0.2%    |
| Lenovo IdeaPad 110-15ACL 80TJ              | 24        | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1149      | 9.31%   |
| Lenovo IdeaPad        | 659       | 5.34%   |
| HP Pavilion           | 509       | 4.13%   |
| Lenovo ThinkPad       | 498       | 4.04%   |
| Dell Inspiron         | 424       | 3.44%   |
| ASUS VivoBook         | 325       | 2.63%   |
| HP Laptop             | 306       | 2.48%   |
| Toshiba Satellite     | 278       | 2.25%   |
| HP ProBook            | 264       | 2.14%   |
| Unknown               | 183       | 1.48%   |
| Dell Latitude         | 171       | 1.39%   |
| Acer Extensa          | 158       | 1.28%   |
| Packard Bell EasyNote | 156       | 1.26%   |
| Dell Vostro           | 117       | 0.95%   |
| HP Compaq             | 100       | 0.81%   |
| HP EliteBook          | 95        | 0.77%   |
| Acer TravelMate       | 90        | 0.73%   |
| Lenovo B590           | 84        | 0.68%   |
| HP Notebook           | 83        | 0.67%   |
| Lenovo G580           | 80        | 0.65%   |
| Lenovo ThinkBook      | 74        | 0.6%    |
| Acer Nitro            | 62        | 0.5%    |
| HP 250                | 57        | 0.46%   |
| Lenovo G570           | 55        | 0.45%   |
| Acer Swift            | 55        | 0.45%   |
| Lenovo Legion         | 52        | 0.42%   |
| Aquarius NS585        | 50        | 0.41%   |
| ASUS ZenBook          | 49        | 0.4%    |
| HP ENVY               | 48        | 0.39%   |
| ASUS ROG              | 48        | 0.39%   |
| Lenovo B570e          | 47        | 0.38%   |
| ASUS ASUS             | 46        | 0.37%   |
| Samsung 355V4C        | 45        | 0.36%   |
| Samsung 300V3A        | 45        | 0.36%   |
| Dell XPS              | 45        | 0.36%   |
| Notebook W65          | 41        | 0.33%   |
| HP 255                | 39        | 0.32%   |
| Lenovo G50-45         | 38        | 0.31%   |
| Fujitsu LIFEBOOK      | 38        | 0.31%   |
| ASUS TUF              | 38        | 0.31%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 1519      | 12.31%  |
| 2012    | 1404      | 11.38%  |
| 2010    | 1023      | 8.29%   |
| 2013    | 873       | 7.08%   |
| 2019    | 824       | 6.68%   |
| 2018    | 695       | 5.63%   |
| 2021    | 686       | 5.56%   |
| 2017    | 662       | 5.37%   |
| 2020    | 658       | 5.33%   |
| 2009    | 625       | 5.07%   |
| 2008    | 609       | 4.94%   |
| 2014    | 592       | 4.8%    |
| 2015    | 518       | 4.2%    |
| 2016    | 506       | 4.1%    |
| 2007    | 463       | 3.75%   |
| 2022    | 373       | 3.02%   |
| 2006    | 201       | 1.63%   |
| 2005    | 52        | 0.42%   |
| 2023    | 25        | 0.2%    |
| Unknown | 14        | 0.11%   |
| 2004    | 11        | 0.09%   |
| 2003    | 2         | 0.02%   |
| 2001    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 12336     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 11800     | 95.12%  |
| Enabled  | 605       | 4.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12319     | 99.86%  |
| Yes  | 17        | 0.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 3528      | 27.84%  |
| 4.01-8.0    | 3464      | 27.33%  |
| 8.01-16.0   | 1780      | 14.05%  |
| 1.01-2.0    | 1468      | 11.58%  |
| 16.01-24.0  | 1034      | 8.16%   |
| 2.01-3.0    | 794       | 6.27%   |
| 0.51-1.0    | 268       | 2.11%   |
| 32.01-64.0  | 237       | 1.87%   |
| 24.01-32.0  | 62        | 0.49%   |
| 64.01-256.0 | 21        | 0.17%   |
| 0.01-0.5    | 14        | 0.11%   |
| Unknown     | 3         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 5310      | 38.18%  |
| 0.51-1.0   | 4002      | 28.78%  |
| 2.01-3.0   | 2136      | 15.36%  |
| 3.01-4.0   | 966       | 6.95%   |
| 4.01-8.0   | 928       | 6.67%   |
| 0.01-0.5   | 304       | 2.19%   |
| 8.01-16.0  | 225       | 1.62%   |
| 16.01-24.0 | 14        | 0.1%    |
| 24.01-32.0 | 10        | 0.07%   |
| Unknown    | 10        | 0.07%   |
| 32.01-64.0 | 2         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 9747      | 76.81%  |
| 2       | 2569      | 20.24%  |
| 3       | 264       | 2.08%   |
| 0       | 88        | 0.69%   |
| 4       | 15        | 0.12%   |
| 5       | 6         | 0.05%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6841      | 54.74%  |
| Yes       | 5657      | 45.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 10558     | 85.42%  |
| No        | 1802      | 14.58%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 12110     | 98.06%  |
| No        | 240       | 1.94%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 8853      | 70.74%  |
| No        | 3661      | 29.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 12336     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 2752      | 20.71%  |
| St Petersburg    | 1206      | 9.07%   |
| Novosibirsk      | 399       | 3%      |
| Krasnodar        | 398       | 2.99%   |
| Voronezh         | 358       | 2.69%   |
| Yekaterinburg    | 341       | 2.57%   |
| Pecherskoye      | 337       | 2.54%   |
| Nizhniy Novgorod | 260       | 1.96%   |
| Samara           | 242       | 1.82%   |
| Perm             | 222       | 1.67%   |
| Chelyabinsk      | 210       | 1.58%   |
| Rostov-on-Don    | 197       | 1.48%   |
| Kazan’         | 165       | 1.24%   |
| Krasnoyarsk      | 151       | 1.14%   |
| Saratov          | 145       | 1.09%   |
| Ufa              | 142       | 1.07%   |
| Omsk             | 120       | 0.9%    |
| Khabarovsk       | 114       | 0.86%   |
| Tyumen           | 109       | 0.82%   |
| Vladivostok      | 107       | 0.81%   |
| Volgograd        | 106       | 0.8%    |
| Barnaul          | 102       | 0.77%   |
| Irkutsk          | 97        | 0.73%   |
| Yaroslavl        | 92        | 0.69%   |
| Kaliningrad      | 92        | 0.69%   |
| Stavropol        | 83        | 0.62%   |
| Kirov            | 80        | 0.6%    |
| Tula             | 77        | 0.58%   |
| Ryazan           | 73        | 0.55%   |
| Tomsk            | 71        | 0.53%   |
| Ulyanovsk        | 70        | 0.53%   |
| Belgorod         | 70        | 0.53%   |
| Surgut           | 69        | 0.52%   |
| Kemerovo         | 69        | 0.52%   |
| Tver             | 68        | 0.51%   |
| Ivanovo          | 60        | 0.45%   |
| Penza            | 58        | 0.44%   |
| Izhevsk          | 57        | 0.43%   |
| Kaluga           | 56        | 0.42%   |
| Astrakhan        | 56        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2677      | 3586   | 17.65%  |
| Seagate             | 2257      | 2958   | 14.88%  |
| Toshiba             | 1451      | 1863   | 9.57%   |
| Samsung Electronics | 1440      | 1925   | 9.49%   |
| Hitachi             | 966       | 1262   | 6.37%   |
| Kingston            | 765       | 944    | 5.04%   |
| Unknown             | 617       | 793    | 4.07%   |
| HGST                | 558       | 780    | 3.68%   |
| SanDisk             | 481       | 620    | 3.17%   |
| SK hynix            | 411       | 528    | 2.71%   |
| Intel               | 350       | 450    | 2.31%   |
| A-DATA Technology   | 270       | 448    | 1.78%   |
| China               | 238       | 309    | 1.57%   |
| Micron Technology   | 188       | 240    | 1.24%   |
| Fujitsu             | 144       | 172    | 0.95%   |
| SPCC                | 133       | 192    | 0.88%   |
| Crucial             | 129       | 161    | 0.85%   |
| KIOXIA              | 114       | 138    | 0.75%   |
| Apacer              | 108       | 129    | 0.71%   |
| Smartbuy            | 99        | 114    | 0.65%   |
| OCZ                 | 89        | 105    | 0.59%   |
| Transcend           | 86        | 110    | 0.57%   |
| Plextor             | 85        | 108    | 0.56%   |
| KingSpec            | 85        | 105    | 0.56%   |
| HUAWEI              | 71        | 79     | 0.47%   |
| Phison              | 64        | 70     | 0.42%   |
| Netac               | 58        | 74     | 0.38%   |
| Silicon Motion      | 54        | 66     | 0.36%   |
| Apple               | 49        | 61     | 0.32%   |
| AMD                 | 49        | 56     | 0.32%   |
| Unknown             | 48        | 52     | 0.32%   |
| Patriot             | 47        | 54     | 0.31%   |
| BIWIN               | 46        | 47     | 0.3%    |
| Phison Electronics  | 44        | 50     | 0.29%   |
| JMicron Technology  | 40        | 41     | 0.26%   |
| GOODRAM             | 38        | 42     | 0.25%   |
| Gigabyte Technology | 34        | 39     | 0.22%   |
| KingDian            | 31        | 44     | 0.2%    |
| Corsair             | 31        | 39     | 0.2%    |
| LITEON              | 28        | 34     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB               | 267       | 1.72%   |
| Seagate ST500LT012-1DG142 500GB        | 258       | 1.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 252       | 1.62%   |
| Seagate ST9500325AS 500GB              | 205       | 1.32%   |
| Seagate ST1000LM035-1RK172 1TB         | 182       | 1.17%   |
| Seagate ST9320325AS 320GB              | 165       | 1.06%   |
| HGST HTS545050A7E680 500GB             | 151       | 0.97%   |
| Toshiba MQ01ABD100 1TB                 | 133       | 0.85%   |
| Toshiba MQ04ABF100 1TB                 | 118       | 0.76%   |
| Hitachi HTS543232A7A384 320GB          | 105       | 0.67%   |
| Seagate ST500LT012-9WS142 500GB        | 104       | 0.67%   |
| Kingston SA400S37240G 240GB SSD        | 98        | 0.63%   |
| Seagate ST9250315AS 250GB              | 95        | 0.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 94        | 0.6%    |
| HGST HTS545050A7E380 500GB             | 94        | 0.6%    |
| Kingston SA400S37120G 120GB SSD        | 92        | 0.59%   |
| Seagate ST320LT020-9YG142 320GB        | 91        | 0.58%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 90        | 0.58%   |
| Hitachi HTS547550A9E384 500GB          | 87        | 0.56%   |
| Hitachi HTS545025B9A300 250GB          | 86        | 0.55%   |
| HGST HTS541010A9E680 1TB               | 85        | 0.55%   |
| HGST HTS721010A9E630 1TB               | 81        | 0.52%   |
| WDC WD3200BPVT-22JJ5T0 320GB           | 79        | 0.51%   |
| WDC WD10JPVX-22JC3T0 1TB               | 78        | 0.5%    |
| Hitachi HTS547575A9E384 752GB          | 78        | 0.5%    |
| WDC WD5000LPCX-21VHAT0 500GB           | 74        | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 73        | 0.47%   |
| Kingston SV300S37A120G 120GB SSD       | 72        | 0.46%   |
| WDC WD5000LPCX-24VHAT0 500GB           | 69        | 0.44%   |
| Toshiba MQ01ABD050 500GB               | 61        | 0.39%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 60        | 0.39%   |
| Toshiba MQ01ABD075 752GB               | 59        | 0.38%   |
| Samsung HM321HI 320GB                  | 56        | 0.36%   |
| Samsung SSD 860 EVO 250GB              | 55        | 0.35%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB | 55        | 0.35%   |
| A-DATA SU800 512GB SSD                 | 55        | 0.35%   |
| Hitachi HTS545050A7E380 500GB          | 53        | 0.34%   |
| Hitachi HTS545032B9A300 320GB          | 53        | 0.34%   |
| WDC WD1600BEVT-22ZCT0 160GB            | 52        | 0.33%   |
| Unknown MMC Card  32GB                 | 51        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 2244      | 2939   | 29.15%  |
| WDC                 | 2208      | 2967   | 28.68%  |
| Toshiba             | 1277      | 1639   | 16.59%  |
| Hitachi             | 966       | 1262   | 12.55%  |
| HGST                | 558       | 780    | 7.25%   |
| Samsung Electronics | 237       | 283    | 3.08%   |
| Fujitsu             | 143       | 171    | 1.86%   |
| Unknown             | 22        | 29     | 0.29%   |
| External            | 9         | 11     | 0.12%   |
| IBM/Hitachi         | 6         | 6      | 0.08%   |
| Apple               | 5         | 5      | 0.06%   |
| USB                 | 3         | 3      | 0.04%   |
| HGST HTS            | 3         | 3      | 0.04%   |
| QNAP                | 2         | 6      | 0.03%   |
| KESU                | 2         | 2      | 0.03%   |
| ZALMAN              | 1         | 1      | 0.01%   |
| WD MediaMax         | 1         | 2      | 0.01%   |
| USB3.0              | 1         | 1      | 0.01%   |
| SILICONMOTION       | 1         | 1      | 0.01%   |
| PHD 3.0             | 1         | 1      | 0.01%   |
| OEM                 | 1         | 2      | 0.01%   |
| MARSHAL             | 1         | 1      | 0.01%   |
| JMicron Technology  | 1         | 1      | 0.01%   |
| Initio              | 1         | 1      | 0.01%   |
| IBM                 | 1         | 1      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| ACASIS              | 1         | 1      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 605       | 745    | 15%     |
| Samsung Electronics | 583       | 781    | 14.46%  |
| SanDisk             | 275       | 367    | 6.82%   |
| WDC                 | 272       | 322    | 6.75%   |
| China               | 237       | 308    | 5.88%   |
| A-DATA Technology   | 233       | 398    | 5.78%   |
| SPCC                | 127       | 186    | 3.15%   |
| Crucial             | 122       | 151    | 3.03%   |
| Intel               | 118       | 153    | 2.93%   |
| Smartbuy            | 96        | 111    | 2.38%   |
| Apacer              | 93        | 112    | 2.31%   |
| OCZ                 | 89        | 105    | 2.21%   |
| Plextor             | 85        | 108    | 2.11%   |
| KingSpec            | 85        | 105    | 2.11%   |
| SK hynix            | 84        | 104    | 2.08%   |
| Transcend           | 83        | 104    | 2.06%   |
| Toshiba             | 71        | 91     | 1.76%   |
| Micron Technology   | 61        | 91     | 1.51%   |
| Patriot             | 47        | 54     | 1.17%   |
| AMD                 | 47        | 53     | 1.17%   |
| Netac               | 42        | 53     | 1.04%   |
| GOODRAM             | 38        | 42     | 0.94%   |
| Apple               | 36        | 42     | 0.89%   |
| KingDian            | 30        | 43     | 0.74%   |
| Corsair             | 29        | 37     | 0.72%   |
| JMicron Technology  | 26        | 27     | 0.64%   |
| LITEON              | 24        | 30     | 0.6%    |
| LITEONIT            | 21        | 35     | 0.52%   |
| Unknown             | 19        | 21     | 0.47%   |
| XrayDisk            | 18        | 24     | 0.45%   |
| Gigabyte Technology | 16        | 19     | 0.4%    |
| Londisk             | 13        | 16     | 0.32%   |
| KingFast            | 13        | 15     | 0.32%   |
| TO Exter            | 12        | 15     | 0.3%    |
| Kingmax             | 12        | 24     | 0.3%    |
| Hewlett-Packard     | 12        | 20     | 0.3%    |
| Team                | 10        | 14     | 0.25%   |
| Zheino              | 9         | 11     | 0.22%   |
| ShiJi               | 9         | 10     | 0.22%   |
| FORESEE             | 8         | 8      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 7403      | 10121  | 51.06%  |
| SSD     | 3772      | 5238   | 26.01%  |
| NVMe    | 2503      | 3361   | 17.26%  |
| MMC     | 630       | 827    | 4.34%   |
| Unknown | 192       | 209    | 1.32%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 9915      | 15164  | 74.04%  |
| NVMe | 2501      | 3354   | 18.68%  |
| MMC  | 630       | 827    | 4.7%    |
| SAS  | 345       | 411    | 2.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 8204      | 11829  | 76.82%  |
| 0.51-1.0   | 2341      | 3347   | 21.92%  |
| 1.01-2.0   | 122       | 164    | 1.14%   |
| 3.01-4.0   | 5         | 12     | 0.05%   |
| 4.01-10.0  | 5         | 5      | 0.05%   |
| 2.01-3.0   | 1         | 1      | 0.01%   |
| 0          | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 3985      | 29.54%  |
| 251-500        | 3542      | 26.25%  |
| 1-20           | 1489      | 11.04%  |
| 501-1000       | 1453      | 10.77%  |
| 51-100         | 1212      | 8.98%   |
| 21-50          | 931       | 6.9%    |
| 1001-2000      | 452       | 3.35%   |
| Unknown        | 292       | 2.16%   |
| 2001-3000      | 88        | 0.65%   |
| More than 3000 | 47        | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 7793      | 56.52%  |
| 21-50          | 1923      | 13.95%  |
| 101-250        | 1340      | 9.72%   |
| 51-100         | 1263      | 9.16%   |
| 251-500        | 725       | 5.26%   |
| 501-1000       | 329       | 2.39%   |
| Unknown        | 292       | 2.12%   |
| 1001-2000      | 93        | 0.67%   |
| 2001-3000      | 18        | 0.13%   |
| More than 3000 | 12        | 0.09%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB           | 141       | 194    | 4.58%   |
| Seagate ST500LT012-9WS142 500GB     | 94        | 112    | 3.06%   |
| Seagate ST9320325AS 320GB           | 90        | 115    | 2.93%   |
| HGST HTS545050A7E680 500GB          | 73        | 110    | 2.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 72        | 89     | 2.34%   |
| Seagate ST500LT012-1DG142 500GB     | 67        | 82     | 2.18%   |
| Seagate ST9250315AS 250GB           | 66        | 82     | 2.15%   |
| Seagate ST320LT020-9YG142 320GB     | 56        | 81     | 1.82%   |
| HGST HTS545050A7E380 500GB          | 47        | 75     | 1.53%   |
| Hitachi HTS545025B9A300 250GB       | 43        | 52     | 1.4%    |
| Hitachi HTS543232A7A384 320GB       | 42        | 48     | 1.37%   |
| Seagate ST320LT012-9WS14C 320GB     | 38        | 51     | 1.24%   |
| Hitachi HTS547550A9E384 500GB       | 35        | 48     | 1.14%   |
| Hitachi HTS547575A9E384 752GB       | 34        | 47     | 1.11%   |
| Toshiba MQ01ABF050 500GB            | 32        | 45     | 1.04%   |
| Toshiba MQ01ABD050 500GB            | 30        | 37     | 0.98%   |
| Hitachi HTS541612J9SA00 120GB       | 29        | 39     | 0.94%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 26        | 30     | 0.85%   |
| Hitachi HTS541680J9SA00 80GB        | 26        | 30     | 0.85%   |
| Toshiba MK3265GSX 320GB             | 24        | 30     | 0.78%   |
| Seagate ST9500420AS 500GB           | 24        | 37     | 0.78%   |
| Samsung Electronics HM160HI 160GB   | 23        | 25     | 0.75%   |
| Hitachi HTS545032B9A300 320GB       | 23        | 29     | 0.75%   |
| HGST HTS541010A9E680 1TB            | 23        | 37     | 0.75%   |
| Hitachi HTS545050A7E380 500GB       | 21        | 31     | 0.68%   |
| Toshiba MQ01ABD100 1TB              | 20        | 28     | 0.65%   |
| Hitachi HTS545050B9A300 500GB       | 20        | 27     | 0.65%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 19        | 25     | 0.62%   |
| Hitachi HTS542512K9SA00 120GB       | 19        | 24     | 0.62%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 18        | 21     | 0.59%   |
| Samsung Electronics HM321HI 320GB   | 18        | 23     | 0.59%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 17        | 20     | 0.55%   |
| WDC WD2500BEVT-22A23T0 208GB        | 16        | 19     | 0.52%   |
| Hitachi HTS542516K9SA00 160GB       | 16        | 28     | 0.52%   |
| Toshiba MQ01ABD075 752GB            | 15        | 20     | 0.49%   |
| Toshiba MK3259GSXP 320GB            | 15        | 25     | 0.49%   |
| Seagate ST9160821AS 160GB           | 15        | 17     | 0.49%   |
| Samsung Electronics HM250HI 250GB   | 15        | 17     | 0.49%   |
| Hitachi HTS542525K9SA00 250GB       | 15        | 21     | 0.49%   |
| Seagate ST9250827AS 250GB           | 14        | 16     | 0.46%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 925       | 1180   | 30.25%  |
| Hitachi                      | 517       | 657    | 16.91%  |
| WDC                          | 486       | 637    | 15.89%  |
| Toshiba                      | 434       | 566    | 14.19%  |
| HGST                         | 186       | 280    | 6.08%   |
| Samsung Electronics          | 124       | 145    | 4.05%   |
| Kingston                     | 48        | 59     | 1.57%   |
| Fujitsu                      | 45        | 61     | 1.47%   |
| SanDisk                      | 43        | 52     | 1.41%   |
| SK hynix                     | 27        | 35     | 0.88%   |
| Intel                        | 25        | 37     | 0.82%   |
| A-DATA Technology            | 20        | 27     | 0.65%   |
| China                        | 17        | 23     | 0.56%   |
| OCZ                          | 16        | 16     | 0.52%   |
| KingSpec                     | 13        | 15     | 0.43%   |
| SPCC                         | 12        | 13     | 0.39%   |
| LITEON                       | 11        | 12     | 0.36%   |
| Crucial                      | 10        | 13     | 0.33%   |
| Plextor                      | 9         | 11     | 0.29%   |
| Micron Technology            | 8         | 14     | 0.26%   |
| Corsair                      | 8         | 8      | 0.26%   |
| LITEONIT                     | 7         | 13     | 0.23%   |
| AMD                          | 6         | 8      | 0.2%    |
| Netac                        | 5         | 6      | 0.16%   |
| IBM/Hitachi                  | 5         | 5      | 0.16%   |
| Apple                        | 4         | 4      | 0.13%   |
| Transcend                    | 3         | 3      | 0.1%    |
| SSSTC                        | 3         | 4      | 0.1%    |
| Smartbuy                     | 3         | 3      | 0.1%    |
| Kingmax                      | 3         | 3      | 0.1%    |
| KingDian                     | 3         | 6      | 0.1%    |
| Unknown                      | 3         | 4      | 0.1%    |
| Team                         | 2         | 3      | 0.07%   |
| OCZ-VERTEX3                  | 2         | 2      | 0.07%   |
| Mushkin                      | 2         | 2      | 0.07%   |
| HGST HTS                     | 2         | 2      | 0.07%   |
| Zheino                       | 1         | 1      | 0.03%   |
| XrayDisk                     | 1         | 1      | 0.03%   |
| Unknown                      | 1         | 1      | 0.03%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 925       | 1180   | 34.55%  |
| Hitachi             | 517       | 657    | 19.31%  |
| WDC                 | 461       | 612    | 17.22%  |
| Toshiba             | 430       | 562    | 16.06%  |
| HGST                | 186       | 280    | 6.95%   |
| Samsung Electronics | 104       | 124    | 3.88%   |
| Fujitsu             | 45        | 61     | 1.68%   |
| IBM/Hitachi         | 5         | 5      | 0.19%   |
| HGST HTS            | 2         | 2      | 0.07%   |
| MARSHAL             | 1         | 1      | 0.04%   |
| External            | 1         | 1      | 0.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 2639      | 3485   | 87.47%  |
| SSD  | 358       | 445    | 11.87%  |
| NVMe | 20        | 23     | 0.66%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD1600BEVT-22ZCT0 160GB        | 4         | 5      | 4.26%   |
| Seagate ST9500325AS 500GB          | 4         | 4      | 4.26%   |
| Samsung Electronics HM321HI 320GB  | 4         | 5      | 4.26%   |
| HGST HTS721010A9E630 1TB           | 4         | 5      | 4.26%   |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 3.19%   |
| Seagate ST9320325AS 320GB          | 3         | 3      | 3.19%   |
| Hitachi HTS547550A9E384 500GB      | 3         | 3      | 3.19%   |
| HGST HTS545050A7E680 500GB         | 3         | 3      | 3.19%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 2         | 2      | 2.13%   |
| WDC WD1600BEVS-22RST0 160GB        | 2         | 2      | 2.13%   |
| Toshiba MQ01ABD050 500GB           | 2         | 2      | 2.13%   |
| Toshiba MK6465GSX 640GB            | 2         | 2      | 2.13%   |
| Toshiba MK3259GSXP 320GB           | 2         | 2      | 2.13%   |
| Seagate ST500LT012-1DG142 500GB    | 2         | 2      | 2.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 2.13%   |
| Samsung Electronics HM160HI 160GB  | 2         | 2      | 2.13%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 3      | 2.13%   |
| Hitachi HTS543225A7A384 250GB      | 2         | 3      | 2.13%   |
| HGST HTS541010A9E680 1TB           | 2         | 2      | 2.13%   |
| WDC WD800BEVS-22RST0 80GB          | 1         | 1      | 1.06%   |
| WDC WD7500BPVT-22HXZT3 752GB       | 1         | 1      | 1.06%   |
| WDC WD7500BPVT-22HXZT1 752GB       | 1         | 1      | 1.06%   |
| WDC WD5000M22K-24Z1LT0-SSHD-16GB   | 1         | 1      | 1.06%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BPVT-80HXZT1 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BPVT-24HXZT3 500GB       | 1         | 1      | 1.06%   |
| WDC WD5000BEVT-35ZAT0 500GB        | 1         | 1      | 1.06%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 1      | 1.06%   |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 1.06%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 1         | 1      | 1.06%   |
| WDC WD3200BEVS-0 320GB             | 1         | 1      | 1.06%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-35A23T0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-24A23T0 250GB       | 1         | 1      | 1.06%   |
| WDC WD2500BEVT-22ZCT0 250GB        | 1         | 1      | 1.06%   |
| WDC WD1600BEVT-75ZCT2 160GB        | 1         | 1      | 1.06%   |
| WDC WD1200BEVS-07LAT0 120GB        | 1         | 1      | 1.06%   |
| WDC WD10JPVX-22JC3T0 1TB           | 1         | 1      | 1.06%   |
| Toshiba MK8037GSX 80GB             | 1         | 1      | 1.06%   |
| Toshiba MK8025GAL 80GB             | 1         | 2      | 1.06%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 27        | 28     | 28.72%  |
| Toshiba             | 16        | 18     | 17.02%  |
| Seagate             | 16        | 18     | 17.02%  |
| Samsung Electronics | 13        | 14     | 13.83%  |
| HGST                | 11        | 13     | 11.7%   |
| Hitachi             | 9         | 11     | 9.57%   |
| Fujitsu             | 1         | 1      | 1.06%   |
| Apple               | 1         | 2      | 1.06%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 7434      | 11187  | 54.74%  |
| Detected | 3078      | 4510   | 22.67%  |
| Malfunc  | 2973      | 3953   | 21.89%  |
| Failed   | 94        | 105    | 0.69%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 8765      | 64.05%  |
| AMD                                     | 2210      | 16.15%  |
| Samsung Electronics                     | 673       | 4.92%   |
| SanDisk                                 | 387       | 2.83%   |
| SK hynix                                | 312       | 2.28%   |
| Kingston Technology Company             | 172       | 1.26%   |
| Phison Electronics                      | 154       | 1.13%   |
| Micron Technology                       | 127       | 0.93%   |
| Nvidia                                  | 124       | 0.91%   |
| KIOXIA                                  | 124       | 0.91%   |
| Toshiba America Info Systems            | 109       | 0.8%    |
| Silicon Integrated Systems [SiS]        | 76        | 0.56%   |
| Silicon Motion                          | 72        | 0.53%   |
| Union Memory (Shenzhen)                 | 59        | 0.43%   |
| Solid State Storage Technology          | 44        | 0.32%   |
| INNOGRIT                                | 40        | 0.29%   |
| ADATA Technology                        | 39        | 0.28%   |
| JMicron Technology                      | 34        | 0.25%   |
| Shenzhen Longsys Electronics            | 31        | 0.23%   |
| Realtek Semiconductor                   | 30        | 0.22%   |
| VIA Technologies                        | 12        | 0.09%   |
| Netac Technology                        | 11        | 0.08%   |
| Micron/Crucial Technology               | 11        | 0.08%   |
| Yangtze Memory Technologies             | 10        | 0.07%   |
| Lite-On Technology                      | 7         | 0.05%   |
| Apple                                   | 7         | 0.05%   |
| O2 Micro                                | 6         | 0.04%   |
| MAXIO Technology (Hangzhou)             | 6         | 0.04%   |
| Lenovo                                  | 6         | 0.04%   |
| ASMedia Technology                      | 5         | 0.04%   |
| Shenzhen Shichuangyi Electronics        | 4         | 0.03%   |
| Marvell Technology Group                | 3         | 0.02%   |
| Unknown                                 | 3         | 0.02%   |
| Zhaoxin                                 | 2         | 0.01%   |
| Silicon Image                           | 2         | 0.01%   |
| Seagate Technology                      | 2         | 0.01%   |
| Jiangsu Huacun Elec.                    | 2         | 0.01%   |
| ULi Electronics                         | 1         | 0.01%   |
| Transcend                               | 1         | 0.01%   |
| Shenzhen Unionmemory Information System | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 1522      | 10.09%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 1379      | 9.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 958       | 6.35%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 677       | 4.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 540       | 3.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 521       | 3.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 436       | 2.89%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 409       | 2.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 390       | 2.59%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 336       | 2.23%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 333       | 2.21%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 314       | 2.08%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 278       | 1.84%   |
| Samsung NVMe SSD Controller 980                                                  | 262       | 1.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 257       | 1.7%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 239       | 1.59%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 203       | 1.35%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 188       | 1.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 183       | 1.21%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 180       | 1.19%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 171       | 1.13%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 160       | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                            | 159       | 1.05%   |
| Intel Tiger Lake-LP SATA Controller                                              | 147       | 0.97%   |
| Intel Volume Management Device NVMe RAID Controller                              | 135       | 0.9%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 126       | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 124       | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 119       | 0.79%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 118       | 0.78%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 118       | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 116       | 0.77%   |
| AMD SB600 IDE                                                                    | 115       | 0.76%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 111       | 0.74%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 109       | 0.72%   |
| Phison PS5013 E13 NVMe Controller                                                | 107       | 0.71%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 105       | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 102       | 0.68%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 100       | 0.66%   |
| Intel SSD 660P Series                                                            | 99        | 0.66%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 96        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 9820      | 68.1%   |
| NVMe | 2523      | 17.5%   |
| IDE  | 1599      | 11.09%  |
| RAID | 479       | 3.32%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 9580      | 77.64%  |
| AMD          | 2744      | 22.24%  |
| ARM          | 6         | 0.05%   |
| CentaurHauls | 5         | 0.04%   |
| Unknown      | 3         | 0.02%   |
| PowerBook5,6 | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-3210M CPU @ 2.50GHz             | 164       | 1.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 157       | 1.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 152       | 1.23%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 150       | 1.21%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 144       | 1.16%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 139       | 1.12%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 132       | 1.07%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 126       | 1.02%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 123       | 0.99%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 117       | 0.95%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 112       | 0.91%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 112       | 0.91%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 105       | 0.85%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 104       | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 103       | 0.83%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 103       | 0.83%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 102       | 0.82%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 98        | 0.79%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 94        | 0.76%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 94        | 0.76%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 91        | 0.74%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 89        | 0.72%   |
| AMD E-450 APU with Radeon HD Graphics         | 87        | 0.7%    |
| Intel Atom CPU N455 @ 1.66GHz                 | 84        | 0.68%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 83        | 0.67%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 81        | 0.65%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 80        | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 78        | 0.63%   |
| AMD A10-4600M APU with Radeon HD Graphics     | 76        | 0.61%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 74        | 0.6%    |
| Intel Core i3-3120M CPU @ 2.50GHz             | 74        | 0.6%    |
| Intel Core i5-8300H CPU @ 2.30GHz             | 72        | 0.58%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 71        | 0.57%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 69        | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 66        | 0.53%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 65        | 0.53%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 65        | 0.53%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 65        | 0.53%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 64        | 0.52%   |
| Intel Atom CPU N570 @ 1.66GHz                 | 64        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 2331      | 18.85%  |
| Intel Core i3                  | 1571      | 12.7%   |
| Intel Core i7                  | 1193      | 9.65%   |
| Intel Celeron                  | 916       | 7.41%   |
| Intel Pentium                  | 858       | 6.94%   |
| Intel Atom                     | 723       | 5.85%   |
| Intel Core 2 Duo               | 649       | 5.25%   |
| Other                          | 576       | 4.66%   |
| AMD Ryzen 5                    | 508       | 4.11%   |
| AMD Ryzen 7                    | 273       | 2.21%   |
| AMD A6                         | 251       | 2.03%   |
| Intel Pentium Dual-Core        | 208       | 1.68%   |
| AMD A4                         | 173       | 1.4%    |
| AMD A8                         | 168       | 1.36%   |
| AMD A10                        | 159       | 1.29%   |
| AMD E                          | 153       | 1.24%   |
| AMD Ryzen 3                    | 133       | 1.08%   |
| AMD E1                         | 120       | 0.97%   |
| Intel Genuine                  | 107       | 0.87%   |
| AMD E2                         | 100       | 0.81%   |
| Intel Pentium Dual             | 99        | 0.8%    |
| Intel Core 2                   | 99        | 0.8%    |
| Intel Celeron M                | 77        | 0.62%   |
| Intel Celeron Dual-Core        | 76        | 0.61%   |
| Intel Pentium Silver           | 73        | 0.59%   |
| AMD Phenom II                  | 73        | 0.59%   |
| AMD Turion 64 X2 Mobile        | 70        | 0.57%   |
| Intel Pentium M                | 58        | 0.47%   |
| AMD Athlon                     | 46        | 0.37%   |
| AMD C-60                       | 37        | 0.3%    |
| AMD Athlon II                  | 35        | 0.28%   |
| AMD Ryzen 9                    | 34        | 0.27%   |
| AMD Athlon 64 X2               | 29        | 0.23%   |
| AMD Athlon X2                  | 27        | 0.22%   |
| AMD Turion II Dual-Core        | 25        | 0.2%    |
| AMD Ryzen 7 PRO                | 25        | 0.2%    |
| AMD Turion X2 Dual-Core Mobile | 24        | 0.19%   |
| AMD C-50                       | 22        | 0.18%   |
| Intel Core Duo                 | 21        | 0.17%   |
| AMD Athlon II Dual-Core        | 20        | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 7364      | 59.33%  |
| 4       | 3084      | 24.85%  |
| 1       | 721       | 5.81%   |
| 6       | 496       | 4%      |
| 8       | 338       | 2.72%   |
| Unknown | 287       | 2.31%   |
| 12      | 39        | 0.31%   |
| 14      | 29        | 0.23%   |
| 10      | 26        | 0.21%   |
| 3       | 25        | 0.2%    |
| 192     | 1         | 0.01%   |
| 24      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 12322     | 99.82%  |
| Unknown | 15        | 0.12%   |
| 2       | 5         | 0.04%   |
| 4       | 2         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 7198      | 57.9%   |
| 1       | 4946      | 39.78%  |
| Unknown | 287       | 2.31%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 11841     | 95.83%  |
| 32-bit         | 382       | 3.09%   |
| Unknown        | 131       | 1.06%   |
| 64-bit         | 2         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1415      | 11.21%  |
| 0x206a7    | 1327      | 10.51%  |
| 0x306a9    | 1065      | 8.43%   |
| 0x1067a    | 488       | 3.87%   |
| 0x20655    | 466       | 3.69%   |
| 0x6fd      | 345       | 2.73%   |
| 0x806ec    | 323       | 2.56%   |
| 0x106ca    | 314       | 2.49%   |
| 0x40651    | 313       | 2.48%   |
| 0x806ea    | 291       | 2.3%    |
| 0x30678    | 273       | 2.16%   |
| 0x806c1    | 253       | 2%      |
| 0x406e3    | 245       | 1.94%   |
| 0x306c3    | 244       | 1.93%   |
| 0x806e9    | 220       | 1.74%   |
| 0x906ea    | 197       | 1.56%   |
| 0x306d4    | 182       | 1.44%   |
| 0x08108109 | 182       | 1.44%   |
| 0x406c4    | 177       | 1.4%    |
| 0x06001119 | 177       | 1.4%    |
| 0x05000119 | 171       | 1.35%   |
| 0x10676    | 162       | 1.28%   |
| 0x07030105 | 155       | 1.23%   |
| 0x20652    | 151       | 1.2%    |
| 0x06006705 | 147       | 1.16%   |
| 0x03000027 | 143       | 1.13%   |
| 0x0a50000c | 139       | 1.1%    |
| 0x010000c8 | 134       | 1.06%   |
| 0x30661    | 123       | 0.97%   |
| 0x08108102 | 123       | 0.97%   |
| 0x106c2    | 118       | 0.93%   |
| 0x406c3    | 110       | 0.87%   |
| 0x10661    | 106       | 0.84%   |
| 0x08608103 | 104       | 0.82%   |
| 0x506c9    | 100       | 0.79%   |
| 0x706a1    | 98        | 0.78%   |
| 0x08600106 | 98        | 0.78%   |
| 0x706e5    | 97        | 0.77%   |
| 0x6e8      | 82        | 0.65%   |
| 0x906e9    | 80        | 0.63%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1442      | 11.66%  |
| SandyBridge      | 1409      | 11.4%   |
| IvyBridge        | 1143      | 9.24%   |
| Penryn           | 669       | 5.41%   |
| Core             | 655       | 5.3%    |
| Westmere         | 649       | 5.25%   |
| Haswell          | 629       | 5.09%   |
| Silvermont       | 620       | 5.01%   |
| Bonnell          | 539       | 4.36%   |
| Unknown          | 368       | 2.98%   |
| TigerLake        | 334       | 2.7%    |
| Skylake          | 327       | 2.64%   |
| Zen+             | 323       | 2.61%   |
| Excavator        | 285       | 2.31%   |
| Bobcat           | 261       | 2.11%   |
| Zen 2            | 237       | 1.92%   |
| Piledriver       | 215       | 1.74%   |
| Broadwell        | 204       | 1.65%   |
| Puma             | 201       | 1.63%   |
| Zen 3            | 198       | 1.6%    |
| K10              | 196       | 1.59%   |
| P6               | 187       | 1.51%   |
| Goldmont plus    | 183       | 1.48%   |
| K10 Llano        | 166       | 1.34%   |
| K8 Hammer        | 152       | 1.23%   |
| IceLake          | 152       | 1.23%   |
| Goldmont         | 126       | 1.02%   |
| CometLake        | 100       | 0.81%   |
| Jaguar           | 97        | 0.78%   |
| Alderlake Hybrid | 87        | 0.7%    |
| Zen              | 71        | 0.57%   |
| K8 & K10 hybrid  | 70        | 0.57%   |
| Nehalem          | 26        | 0.21%   |
| Tremont          | 23        | 0.19%   |
| Steamroller      | 15        | 0.12%   |
| NetBurst         | 5         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 8267      | 52.08%  |
| AMD                              | 3922      | 24.71%  |
| Nvidia                           | 3639      | 22.92%  |
| Silicon Integrated Systems [SiS] | 33        | 0.21%   |
| VIA Technologies                 | 9         | 0.06%   |
| Zhaoxin                          | 2         | 0.01%   |
| ATI Technologies                 | 2         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1267      | 7.46%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1110      | 6.54%   |
| Intel Core Processor Integrated Graphics Controller                                      | 359       | 2.11%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 354       | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 349       | 2.05%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 335       | 1.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 334       | 1.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 316       | 1.86%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 316       | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 304       | 1.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 259       | 1.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 258       | 1.52%   |
| Intel UHD Graphics 620                                                                   | 249       | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 246       | 1.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 246       | 1.45%   |
| Intel HD Graphics 620                                                                    | 237       | 1.4%    |
| AMD Renoir                                                                               | 234       | 1.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 233       | 1.37%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 233       | 1.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 226       | 1.33%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 220       | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 217       | 1.28%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 214       | 1.26%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 213       | 1.25%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 195       | 1.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 173       | 1.02%   |
| Intel HD Graphics 5500                                                                   | 166       | 0.98%   |
| AMD Lucienne                                                                             | 164       | 0.97%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 157       | 0.92%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 157       | 0.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 148       | 0.87%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 126       | 0.74%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 124       | 0.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 121       | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 118       | 0.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 117       | 0.69%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 116       | 0.68%   |
| Nvidia GM108M [GeForce 840M]                                                             | 108       | 0.64%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 107       | 0.63%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 105       | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 4925      | 39.78%  |
| Intel + Nvidia     | 2762      | 22.31%  |
| 1 x AMD            | 2516      | 20.32%  |
| 1 x Nvidia         | 683       | 5.52%   |
| 2 x AMD            | 632       | 5.1%    |
| Intel + AMD        | 586       | 4.73%   |
| AMD + Nvidia       | 195       | 1.57%   |
| 1 x SiS            | 33        | 0.27%   |
| Other              | 18        | 0.15%   |
| 2 x Intel          | 16        | 0.13%   |
| 1 x VIA            | 9         | 0.07%   |
| 2 x Nvidia         | 3         | 0.02%   |
| 1 x Zhaoxin        | 2         | 0.02%   |
| Intel + 2 x Nvidia | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 10902     | 86.49%  |
| Proprietary | 1111      | 8.81%   |
| Unknown     | 592       | 4.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4648      | 36.15%  |
| 1.01-2.0   | 3363      | 26.15%  |
| 0.01-0.5   | 3038      | 23.63%  |
| 0.51-1.0   | 966       | 7.51%   |
| 3.01-4.0   | 716       | 5.57%   |
| 5.01-6.0   | 74        | 0.58%   |
| 7.01-8.0   | 26        | 0.2%    |
| 2.01-3.0   | 21        | 0.16%   |
| 8.01-16.0  | 7         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 2585      | 20.54%  |
| LG Display              | 1894      | 15.05%  |
| Samsung Electronics     | 1661      | 13.2%   |
| BOE                     | 1563      | 12.42%  |
| Chimei Innolux          | 1494      | 11.87%  |
| Chi Mei Optoelectronics | 836       | 6.64%   |
| LG Philips              | 231       | 1.84%   |
| Lenovo                  | 205       | 1.63%   |
| HannStar                | 186       | 1.48%   |
| PANDA                   | 163       | 1.3%    |
| Dell                    | 129       | 1.03%   |
| Goldstar                | 128       | 1.02%   |
| InfoVision              | 119       | 0.95%   |
| CPT                     | 117       | 0.93%   |
| Apple                   | 107       | 0.85%   |
| Sharp                   | 104       | 0.83%   |
| BenQ                    | 101       | 0.8%    |
| Acer                    | 93        | 0.74%   |
| Philips                 | 79        | 0.63%   |
| AOC                     | 66        | 0.52%   |
| Sony                    | 65        | 0.52%   |
| Hewlett-Packard         | 53        | 0.42%   |
| Ancor Communications    | 45        | 0.36%   |
| ViewSonic               | 42        | 0.33%   |
| CSO                     | 40        | 0.32%   |
| TMX                     | 37        | 0.29%   |
| InnoLux Display         | 34        | 0.27%   |
| Iiyama                  | 34        | 0.27%   |
| Toshiba                 | 28        | 0.22%   |
| Quanta Display          | 27        | 0.21%   |
| Valve                   | 25        | 0.2%    |
| NEC Computers           | 24        | 0.19%   |
| Unknown                 | 14        | 0.11%   |
| Panasonic               | 13        | 0.1%    |
| HKC                     | 13        | 0.1%    |
| ASUSTek Computer        | 12        | 0.1%    |
| Nvidia                  | 11        | 0.09%   |
| Mi                      | 11        | 0.09%   |
| HUAWEI                  | 11        | 0.09%   |
| S2-Tek                  | 8         | 0.06%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 233       | 1.84%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 208       | 1.64%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 178       | 1.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 160       | 1.26%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 157       | 1.24%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 110       | 0.87%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch      | 106       | 0.84%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 103       | 0.81%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 95        | 0.75%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 95        | 0.75%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 94        | 0.74%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch      | 86        | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 82        | 0.65%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 77        | 0.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 75        | 0.59%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 75        | 0.59%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 74        | 0.58%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 74        | 0.58%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 69        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 68        | 0.54%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 65        | 0.51%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 65        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 63        | 0.5%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 61        | 0.48%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch             | 60        | 0.47%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 58        | 0.46%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 57        | 0.45%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                     | 57        | 0.45%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 54        | 0.43%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 54        | 0.43%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 53        | 0.42%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch              | 50        | 0.39%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 50        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 50        | 0.39%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 50        | 0.39%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 49        | 0.39%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 45        | 0.36%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 45        | 0.36%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 44        | 0.35%   |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch               | 43        | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 5019      | 41.01%  |
| 1920x1080 (FHD)    | 3873      | 31.64%  |
| 1600x900 (HD+)     | 801       | 6.54%   |
| 1280x800 (WXGA)    | 799       | 6.53%   |
| 1024x600           | 392       | 3.2%    |
| 1440x900 (WXGA+)   | 192       | 1.57%   |
| 3840x2160 (4K)     | 182       | 1.49%   |
| 1920x1200 (WUXGA)  | 137       | 1.12%   |
| 2560x1440 (QHD)    | 132       | 1.08%   |
| 1280x1024 (SXGA)   | 122       | 1%      |
| 1680x1050 (WSXGA+) | 86        | 0.7%    |
| 2560x1600          | 81        | 0.66%   |
| 2160x1440          | 62        | 0.51%   |
| 2880x1800          | 36        | 0.29%   |
| 1024x768 (XGA)     | 36        | 0.29%   |
| 800x1280           | 29        | 0.24%   |
| 3440x1440          | 20        | 0.16%   |
| 1360x768           | 20        | 0.16%   |
| 1280x720 (HD)      | 20        | 0.16%   |
| 3200x2000          | 19        | 0.16%   |
| 2288x1287          | 19        | 0.16%   |
| 2560x1080          | 18        | 0.15%   |
| 1680x945           | 14        | 0.11%   |
| 2520x1680          | 13        | 0.11%   |
| 3000x2000          | 12        | 0.1%    |
| 1400x1050          | 10        | 0.08%   |
| 3840x2400          | 9         | 0.07%   |
| 1920x540           | 8         | 0.07%   |
| 3200x1800 (QHD+)   | 7         | 0.06%   |
| 2240x1400          | 7         | 0.06%   |
| 1600x1200          | 7         | 0.06%   |
| 3456x2160          | 6         | 0.05%   |
| 2880x1620          | 6         | 0.05%   |
| Unknown            | 6         | 0.05%   |
| 1024x576           | 5         | 0.04%   |
| 2256x1504          | 4         | 0.03%   |
| 3120x2080          | 3         | 0.02%   |
| 2736x1824          | 3         | 0.02%   |
| 3840x1080          | 2         | 0.02%   |
| 1920x515           | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 7035      | 55.95%  |
| 17      | 1113      | 8.85%   |
| 13      | 1056      | 8.4%    |
| 14      | 1030      | 8.19%   |
| 10      | 400       | 3.18%   |
| 11      | 259       | 2.06%   |
| 24      | 218       | 1.73%   |
| 12      | 216       | 1.72%   |
| 23      | 184       | 1.46%   |
| 21      | 162       | 1.29%   |
| 27      | 158       | 1.26%   |
| 16      | 136       | 1.08%   |
| 19      | 95        | 0.76%   |
| 18      | 83        | 0.66%   |
| Unknown | 54        | 0.43%   |
| 31      | 40        | 0.32%   |
| 34      | 37        | 0.29%   |
| 20      | 37        | 0.29%   |
| 22      | 32        | 0.25%   |
| 7       | 25        | 0.2%    |
| 8       | 23        | 0.18%   |
| 40      | 21        | 0.17%   |
| 32      | 21        | 0.17%   |
| 26      | 18        | 0.14%   |
| 52      | 16        | 0.13%   |
| 54      | 15        | 0.12%   |
| 72      | 12        | 0.1%    |
| 142     | 9         | 0.07%   |
| 42      | 9         | 0.07%   |
| 84      | 8         | 0.06%   |
| 25      | 7         | 0.06%   |
| 28      | 5         | 0.04%   |
| 48      | 4         | 0.03%   |
| 46      | 4         | 0.03%   |
| 3       | 4         | 0.03%   |
| 50      | 3         | 0.02%   |
| 36      | 3         | 0.02%   |
| 9       | 3         | 0.02%   |
| 65      | 2         | 0.02%   |
| 37      | 2         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 8473      | 67.76%  |
| 201-300        | 1456      | 11.64%  |
| 351-400        | 1337      | 10.69%  |
| 501-600        | 555       | 4.44%   |
| 401-500        | 343       | 2.74%   |
| 701-800        | 62        | 0.5%    |
| 601-700        | 57        | 0.46%   |
| Unknown        | 54        | 0.43%   |
| 1001-1500      | 47        | 0.38%   |
| 1-100          | 29        | 0.23%   |
| 801-900        | 24        | 0.19%   |
| 101-200        | 23        | 0.18%   |
| 1501-2000      | 22        | 0.18%   |
| 901-1000       | 13        | 0.1%    |
| More than 2000 | 10        | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 10026     | 84.75%  |
| 16/10   | 1375      | 11.62%  |
| 3/2     | 124       | 1.05%   |
| 5/4     | 112       | 0.95%   |
| 4/3     | 80        | 0.68%   |
| 21/9    | 42        | 0.36%   |
| 0.67    | 25        | 0.21%   |
| Unknown | 24        | 0.2%    |
| 6/5     | 9         | 0.08%   |
| 1.00    | 9         | 0.08%   |
| 3.73    | 2         | 0.02%   |
| 3.40    | 1         | 0.01%   |
| 1.96    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 7044      | 56.03%  |
| 81-90          | 1616      | 12.85%  |
| 121-130        | 867       | 6.9%    |
| 201-250        | 507       | 4.03%   |
| 71-80          | 457       | 3.64%   |
| 41-50          | 403       | 3.21%   |
| 51-60          | 260       | 2.07%   |
| 131-140        | 200       | 1.59%   |
| 61-70          | 197       | 1.57%   |
| 151-200        | 175       | 1.39%   |
| 301-350        | 172       | 1.37%   |
| 141-150        | 122       | 0.97%   |
| 351-500        | 107       | 0.85%   |
| 91-100         | 91        | 0.72%   |
| More than 1000 | 74        | 0.59%   |
| 111-120        | 73        | 0.58%   |
| 251-300        | 59        | 0.47%   |
| Unknown        | 54        | 0.43%   |
| 1-40           | 52        | 0.41%   |
| 501-1000       | 42        | 0.33%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 5470      | 44.06%  |
| 121-160       | 3879      | 31.25%  |
| 51-100        | 2267      | 18.26%  |
| 161-240       | 512       | 4.12%   |
| More than 240 | 148       | 1.19%   |
| 1-50          | 84        | 0.68%   |
| Unknown       | 54        | 0.43%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 11074     | 88.2%   |
| 2     | 1048      | 8.35%   |
| 0     | 377       | 3%      |
| 3     | 56        | 0.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 7215      | 34.9%   |
| Qualcomm Atheros                       | 4875      | 23.58%  |
| Intel                                  | 3776      | 18.26%  |
| Broadcom                               | 1880      | 9.09%   |
| Marvell Technology Group               | 479       | 2.32%   |
| Broadcom Limited                       | 454       | 2.2%    |
| Ralink                                 | 351       | 1.7%    |
| MediaTek                               | 243       | 1.18%   |
| Huawei Technologies                    | 219       | 1.06%   |
| JMicron Technology                     | 117       | 0.57%   |
| Attansic Technology                    | 112       | 0.54%   |
| Xiaomi                                 | 98        | 0.47%   |
| TP-Link                                | 90        | 0.44%   |
| Ralink Technology                      | 80        | 0.39%   |
| Nvidia                                 | 67        | 0.32%   |
| Qualcomm                               | 50        | 0.24%   |
| Silicon Integrated Systems [SiS]       | 49        | 0.24%   |
| Samsung Electronics                    | 48        | 0.23%   |
| ZTE WCDMA Technologies MSM             | 38        | 0.18%   |
| ASIX Electronics                       | 35        | 0.17%   |
| D-Link                                 | 32        | 0.15%   |
| ASUSTek Computer                       | 29        | 0.14%   |
| Qualcomm Atheros Communications        | 25        | 0.12%   |
| Hewlett-Packard                        | 24        | 0.12%   |
| Ericsson Business Mobile Networks      | 24        | 0.12%   |
| Sierra Wireless                        | 23        | 0.11%   |
| Gemtek                                 | 20        | 0.1%    |
| Lenovo                                 | 19        | 0.09%   |
| Dell                                   | 18        | 0.09%   |
| Vimtron Electronics                    | 14        | 0.07%   |
| Fibocom                                | 12        | 0.06%   |
| OPPO Electronics                       | 11        | 0.05%   |
| VIA Technologies                       | 8         | 0.04%   |
| HTC (High Tech Computer)               | 7         | 0.03%   |
| HMD Global                             | 7         | 0.03%   |
| D-Link System                          | 7         | 0.03%   |
| Apple                                  | 7         | 0.03%   |
| T & A Mobile Phones                    | 6         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 6         | 0.03%   |
| ICS Advent                             | 6         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 4319      | 18.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 1671      | 7.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1416      | 5.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 788       | 3.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 633       | 2.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 579       | 2.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 510       | 2.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 410       | 1.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 362       | 1.52%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 360       | 1.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 348       | 1.46%   |
| Broadcom BCM43142 802.11b/g/n                                           | 311       | 1.3%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 278       | 1.17%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 274       | 1.15%   |
| Intel Wi-Fi 6 AX201                                                     | 268       | 1.12%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 245       | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 222       | 0.93%   |
| Intel Wireless 8265 / 8275                                              | 215       | 0.9%    |
| Intel Wi-Fi 6 AX200                                                     | 202       | 0.85%   |
| Intel Wireless 7265                                                     | 199       | 0.83%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 198       | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 193       | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 192       | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 190       | 0.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 179       | 0.75%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 162       | 0.68%   |
| Intel WiFi Link 5100                                                    | 154       | 0.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 145       | 0.61%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 144       | 0.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 143       | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 139       | 0.58%   |
| Intel Wireless 3165                                                     | 136       | 0.57%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 136       | 0.57%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 135       | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 130       | 0.54%   |
| Intel Wireless 7260                                                     | 130       | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 126       | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 126       | 0.53%   |
| Intel Centrino Wireless-N 130                                           | 125       | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 122       | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Qualcomm Atheros                  | 4210      | 33.75%  |
| Intel                             | 3641      | 29.19%  |
| Realtek Semiconductor             | 2161      | 17.32%  |
| Broadcom                          | 1342      | 10.76%  |
| Ralink                            | 351       | 2.81%   |
| Broadcom Limited                  | 247       | 1.98%   |
| MediaTek                          | 203       | 1.63%   |
| Ralink Technology                 | 80        | 0.64%   |
| TP-Link                           | 58        | 0.46%   |
| ASUSTek Computer                  | 27        | 0.22%   |
| Qualcomm                          | 26        | 0.21%   |
| Qualcomm Atheros Communications   | 25        | 0.2%    |
| Sierra Wireless                   | 23        | 0.18%   |
| D-Link                            | 16        | 0.13%   |
| Fibocom                           | 12        | 0.1%    |
| Dell                              | 9         | 0.07%   |
| D-Link System                     | 7         | 0.06%   |
| Tenda                             | 4         | 0.03%   |
| Micro Star International          | 4         | 0.03%   |
| Ericsson Business Mobile Networks | 4         | 0.03%   |
| Xiaomi                            | 3         | 0.02%   |
| Mercucys                          | 3         | 0.02%   |
| Hewlett-Packard                   | 3         | 0.02%   |
| Edimax Technology                 | 3         | 0.02%   |
| ZyXEL Communications              | 2         | 0.02%   |
| Fujitsu Siemens Computers         | 2         | 0.02%   |
| Wacom                             | 1         | 0.01%   |
| Quectel Wireless Solutions        | 1         | 0.01%   |
| Qcom                              | 1         | 0.01%   |
| NetGear                           | 1         | 0.01%   |
| Microsoft                         | 1         | 0.01%   |
| Linksys                           | 1         | 0.01%   |
| ASUSTek Computer (wrong ID)       | 1         | 0.01%   |
| Askey Computer                    | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1416      | 11.26%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 788       | 6.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 633       | 5.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 579       | 4.61%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 510       | 4.06%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 410       | 3.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 362       | 2.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 360       | 2.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 348       | 2.77%   |
| Broadcom BCM43142 802.11b/g/n                                           | 311       | 2.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 278       | 2.21%   |
| Intel Wi-Fi 6 AX201                                                     | 268       | 2.13%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 222       | 1.77%   |
| Intel Wireless 8265 / 8275                                              | 215       | 1.71%   |
| Intel Wi-Fi 6 AX200                                                     | 202       | 1.61%   |
| Intel Wireless 7265                                                     | 199       | 1.58%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 193       | 1.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 192       | 1.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 190       | 1.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 179       | 1.42%   |
| Intel WiFi Link 5100                                                    | 154       | 1.23%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 144       | 1.15%   |
| Intel Wireless 3165                                                     | 136       | 1.08%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 136       | 1.08%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 135       | 1.07%   |
| Intel Wireless 7260                                                     | 130       | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 126       | 1%      |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 126       | 1%      |
| Intel Centrino Wireless-N 130                                           | 125       | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 112       | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 108       | 0.86%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 99        | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 99        | 0.79%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 91        | 0.72%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 89        | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 86        | 0.68%   |
| Intel Centrino Wireless-N 2230                                          | 85        | 0.68%   |
| Intel WiMAX/WiFi Link 5150                                              | 83        | 0.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 80        | 0.64%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 79        | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 6340      | 57.84%  |
| Qualcomm Atheros                       | 1429      | 13.04%  |
| Intel                                  | 883       | 8.06%   |
| Broadcom                               | 715       | 6.52%   |
| Marvell Technology Group               | 479       | 4.37%   |
| Broadcom Limited                       | 217       | 1.98%   |
| JMicron Technology                     | 117       | 1.07%   |
| Attansic Technology                    | 112       | 1.02%   |
| Xiaomi                                 | 95        | 0.87%   |
| Huawei Technologies                    | 71        | 0.65%   |
| Nvidia                                 | 66        | 0.6%    |
| Silicon Integrated Systems [SiS]       | 48        | 0.44%   |
| Samsung Electronics                    | 48        | 0.44%   |
| ZTE WCDMA Technologies MSM             | 38        | 0.35%   |
| MediaTek                               | 38        | 0.35%   |
| ASIX Electronics                       | 35        | 0.32%   |
| TP-Link                                | 32        | 0.29%   |
| Qualcomm                               | 24        | 0.22%   |
| Gemtek                                 | 20        | 0.18%   |
| Lenovo                                 | 19        | 0.17%   |
| D-Link                                 | 16        | 0.15%   |
| Vimtron Electronics                    | 14        | 0.13%   |
| OPPO Electronics                       | 11        | 0.1%    |
| VIA Technologies                       | 8         | 0.07%   |
| Hewlett-Packard                        | 8         | 0.07%   |
| HTC (High Tech Computer)               | 7         | 0.06%   |
| HMD Global                             | 7         | 0.06%   |
| Apple                                  | 7         | 0.06%   |
| ICS Advent                             | 6         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 5         | 0.05%   |
| NTmore                                 | 5         | 0.05%   |
| DisplayLink                            | 5         | 0.05%   |
| T & A Mobile Phones                    | 4         | 0.04%   |
| GCT Semiconductor                      | 4         | 0.04%   |
| LG Electronics                         | 3         | 0.03%   |
| Google                                 | 3         | 0.03%   |
| ASUSTek Computer                       | 3         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.02%   |
| Motorola PCS                           | 2         | 0.02%   |
| LeEco                                  | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 4319      | 39.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 1671      | 15.18%  |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 274       | 2.49%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 245       | 2.23%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 198       | 1.8%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 162       | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 145       | 1.32%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 143       | 1.3%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 139       | 1.26%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 130       | 1.18%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 122       | 1.11%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 122       | 1.11%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 116       | 1.05%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 112       | 1.02%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 107       | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 105       | 0.95%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 97        | 0.88%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 82        | 0.75%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 81        | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 78        | 0.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 74        | 0.67%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 69        | 0.63%   |
| Intel Ethernet Connection (13) I219-V                                          | 68        | 0.62%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 67        | 0.61%   |
| Intel Ethernet Connection (6) I219-V                                           | 65        | 0.59%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 64        | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 63        | 0.57%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 59        | 0.54%   |
| Intel WiMAX Connection 2400m                                                   | 55        | 0.5%    |
| Intel 82577LM Gigabit Network Connection                                       | 55        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 49        | 0.45%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 49        | 0.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 47        | 0.43%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 46        | 0.42%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 44        | 0.4%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 41        | 0.37%   |
| Intel Ethernet Connection (4) I219-V                                           | 39        | 0.35%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 37        | 0.34%   |
| Intel Ethernet Connection (10) I219-V                                          | 37        | 0.34%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 37        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 12106     | 52.85%  |
| Ethernet | 10528     | 45.96%  |
| Modem    | 263       | 1.15%   |
| Unknown  | 11        | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 9885      | 77.6%   |
| Ethernet | 2849      | 22.37%  |
| Modem    | 4         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 10021     | 81.09%  |
| 1     | 2059      | 16.66%  |
| 0     | 256       | 2.07%   |
| 3     | 22        | 0.18%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 12126     | 97.77%  |
| Yes  | 276       | 2.23%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2484      | 27.78%  |
| Qualcomm Atheros Communications | 1218      | 13.62%  |
| Realtek Semiconductor           | 1131      | 12.65%  |
| IMC Networks                    | 757       | 8.46%   |
| Lite-On Technology              | 639       | 7.15%   |
| Broadcom                        | 631       | 7.06%   |
| Foxconn / Hon Hai               | 561       | 6.27%   |
| Ralink                          | 193       | 2.16%   |
| ASUSTek Computer                | 189       | 2.11%   |
| Foxconn International           | 154       | 1.72%   |
| Toshiba                         | 153       | 1.71%   |
| Realtek                         | 148       | 1.65%   |
| Hewlett-Packard                 | 127       | 1.42%   |
| Cambridge Silicon Radio         | 125       | 1.4%    |
| Dell                            | 113       | 1.26%   |
| Apple                           | 93        | 1.04%   |
| Alps Electric                   | 65        | 0.73%   |
| Ralink Technology               | 38        | 0.42%   |
| MediaTek                        | 29        | 0.32%   |
| Opticis                         | 28        | 0.31%   |
| Chicony Electronics             | 23        | 0.26%   |
| Micro Star International        | 12        | 0.13%   |
| Askey Computer                  | 7         | 0.08%   |
| USI                             | 6         | 0.07%   |
| Taiyo Yuden                     | 5         | 0.06%   |
| TP-Link                         | 3         | 0.03%   |
| Integrated System Solution      | 3         | 0.03%   |
| Samsung Electronics             | 2         | 0.02%   |
| Qcom                            | 2         | 0.02%   |
| Syntek                          | 1         | 0.01%   |
| ISSC                            | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| Unknown                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 783       | 8.75%   |
| Realtek Bluetooth Radio                                                             | 724       | 8.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 507       | 5.67%   |
| Intel AX201 Bluetooth                                                               | 474       | 5.3%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 368       | 4.11%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 364       | 4.07%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 284       | 3.17%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 257       | 2.87%   |
| IMC Networks Bluetooth Radio                                                        | 237       | 2.65%   |
| Intel AX200 Bluetooth                                                               | 202       | 2.26%   |
| Ralink RT3290 Bluetooth                                                             | 193       | 2.16%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 190       | 2.12%   |
| IMC Networks Bluetooth Device                                                       | 174       | 1.94%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 165       | 1.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 161       | 1.8%    |
| Foxconn International BCM43142A0 Bluetooth module                                   | 152       | 1.7%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 151       | 1.69%   |
| Lite-On Bluetooth Device                                                            | 147       | 1.64%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 147       | 1.64%   |
| Intel Bluetooth Device                                                              | 146       | 1.63%   |
| Realtek 802.11ac WLAN Adapter                                                       | 142       | 1.59%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 139       | 1.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 125       | 1.4%    |
| Broadcom BCM2070 Bluetooth Device                                                   | 107       | 1.2%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 107       | 1.2%    |
| Broadcom BCM2045 Bluetooth                                                          | 81        | 0.91%   |
| Qualcomm Atheros Bluetooth                                                          | 73        | 0.82%   |
| IMC Networks Wireless_Device                                                        | 72        | 0.8%    |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 71        | 0.79%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 64        | 0.72%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 64        | 0.72%   |
| Broadcom HP Portable Valentine                                                      | 62        | 0.69%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 59        | 0.66%   |
| Toshiba Integrated Bluetooth HCI                                                    | 58        | 0.65%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 58        | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 58        | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 56        | 0.63%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 54        | 0.6%    |
| ASUS BT-270 Bluetooth Adapter                                                       | 54        | 0.6%    |
| ASUS BT-253 Bluetooth Adapter                                                       | 54        | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 9193      | 65.06%  |
| AMD                                          | 3235      | 22.89%  |
| Nvidia                                       | 1227      | 8.68%   |
| C-Media Electronics                          | 96        | 0.68%   |
| Silicon Integrated Systems [SiS]             | 76        | 0.54%   |
| Logitech                                     | 25        | 0.18%   |
| Creative Technology                          | 23        | 0.16%   |
| Realtek Semiconductor                        | 20        | 0.14%   |
| JMTek                                        | 19        | 0.13%   |
| Generalplus Technology                       | 15        | 0.11%   |
| Lenovo                                       | 14        | 0.1%    |
| Texas Instruments                            | 13        | 0.09%   |
| VIA Technologies                             | 12        | 0.08%   |
| Plantronics                                  | 10        | 0.07%   |
| GN Netcom                                    | 9         | 0.06%   |
| ASUSTek Computer                             | 8         | 0.06%   |
| Sennheiser Communications                    | 7         | 0.05%   |
| Promethean Limited                           | 7         | 0.05%   |
| Samson Technologies                          | 6         | 0.04%   |
| Focusrite-Novation                           | 6         | 0.04%   |
| Yamaha                                       | 5         | 0.04%   |
| SteelSeries ApS                              | 5         | 0.04%   |
| A4Tech                                       | 5         | 0.04%   |
| Thesycon Systemsoftware & Consulting         | 4         | 0.03%   |
| Razer USA                                    | 4         | 0.03%   |
| Hewlett-Packard                              | 4         | 0.03%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.02%   |
| SAVITECH                                     | 3         | 0.02%   |
| Nordic Semiconductor ASA                     | 3         | 0.02%   |
| GYROCOM C&C                                  | 3         | 0.02%   |
| Apple                                        | 3         | 0.02%   |
| Zhaoxin                                      | 2         | 0.01%   |
| XMOS                                         | 2         | 0.01%   |
| TTGK Technology                              | 2         | 0.01%   |
| Sony                                         | 2         | 0.01%   |
| Samsung Electronics                          | 2         | 0.01%   |
| Roland                                       | 2         | 0.01%   |
| Microsoft                                    | 2         | 0.01%   |
| M-Audio                                      | 2         | 0.01%   |
| Kingston Technology                          | 2         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1517      | 8.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1029      | 5.94%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 961       | 5.55%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 831       | 4.8%    |
| AMD FCH Azalia Controller                                                                         | 762       | 4.4%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 735       | 4.25%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 672       | 3.88%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 601       | 3.47%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 600       | 3.47%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 518       | 2.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 439       | 2.54%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 369       | 2.13%   |
| AMD Kabini HDMI/DP Audio                                                                          | 361       | 2.09%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 350       | 2.02%   |
| Intel 8 Series HD Audio Controller                                                                | 350       | 2.02%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 334       | 1.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 292       | 1.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 287       | 1.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 281       | 1.62%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 275       | 1.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 261       | 1.51%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 251       | 1.45%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 236       | 1.36%   |
| AMD High Definition Audio Controller                                                              | 233       | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 228       | 1.32%   |
| AMD Wrestler HDMI Audio                                                                           | 226       | 1.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 218       | 1.26%   |
| AMD Trinity HDMI Audio Controller                                                                 | 217       | 1.25%   |
| Intel Broadwell-U Audio Controller                                                                | 204       | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 201       | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 182       | 1.05%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 170       | 0.98%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 166       | 0.96%   |
| Nvidia High Definition Audio Controller                                                           | 141       | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 139       | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 130       | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 126       | 0.73%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 112       | 0.65%   |
| Intel CM238 HD Audio Controller                                                                   | 101       | 0.58%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 99        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 2914      | 23.43%  |
| SK hynix                     | 2367      | 19.03%  |
| Unknown                      | 1541      | 12.39%  |
| Kingston                     | 1380      | 11.1%   |
| Micron Technology            | 1066      | 8.57%   |
| Elpida                       | 477       | 3.84%   |
| Nanya Technology             | 384       | 3.09%   |
| Ramaxel Technology           | 356       | 2.86%   |
| Crucial                      | 335       | 2.69%   |
| A-DATA Technology            | 331       | 2.66%   |
| AMD                          | 156       | 1.25%   |
| ASint Technology             | 127       | 1.02%   |
| Unknown (ABCD)               | 104       | 0.84%   |
| Patriot                      | 100       | 0.8%    |
| Corsair                      | 94        | 0.76%   |
| Goldkey                      | 78        | 0.63%   |
| 48spaces                     | 77        | 0.62%   |
| SHARETRONIC                  | 53        | 0.43%   |
| Foxline                      | 47        | 0.38%   |
| Transcend                    | 37        | 0.3%    |
| Apacer                       | 36        | 0.29%   |
| ACPI Digital                 | 36        | 0.29%   |
| GOODRAM                      | 34        | 0.27%   |
| Unknown                      | 34        | 0.27%   |
| Qimonda                      | 28        | 0.23%   |
| Kllisre                      | 26        | 0.21%   |
| Unifosa                      | 23        | 0.18%   |
| Qumo                         | 19        | 0.15%   |
| Toshiba                      | 16        | 0.13%   |
| ChangXin Memory              | 14        | 0.11%   |
| Silicon Power                | 13        | 0.1%    |
| Kingmax                      | 8         | 0.06%   |
| Kingmax Semiconductor        | 7         | 0.06%   |
| Unknown (8AD6)               | 4         | 0.03%   |
| Ankowall                     | 4         | 0.03%   |
| Unknown (08AE)               | 3         | 0.02%   |
| SGS/Thomson                  | 3         | 0.02%   |
| Patriot Memory (PDP Systems) | 3         | 0.02%   |
| MLLSE                        | 3         | 0.02%   |
| KingTiger                    | 3         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 227       | 1.69%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 154       | 1.14%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s                  | 146       | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                     | 144       | 1.07%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                     | 137       | 1.02%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 136       | 1.01%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s                     | 129       | 0.96%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 124       | 0.92%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                             | 122       | 0.91%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 111       | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                     | 109       | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                     | 104       | 0.77%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 98        | 0.73%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                     | 96        | 0.71%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                     | 95        | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s          | 93        | 0.69%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                     | 93        | 0.69%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 91        | 0.68%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                             | 89        | 0.66%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                    | 87        | 0.65%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                     | 83        | 0.62%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                         | 77        | 0.57%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 76        | 0.57%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 72        | 0.54%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                     | 71        | 0.53%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                     | 71        | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 66        | 0.49%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                    | 64        | 0.48%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                      | 64        | 0.48%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s                     | 60        | 0.45%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 60        | 0.45%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                             | 59        | 0.44%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 59        | 0.44%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s                    | 59        | 0.44%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 58        | 0.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 56        | 0.42%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s                    | 55        | 0.41%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                     | 55        | 0.41%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                    | 54        | 0.4%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                                | 53        | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 5286      | 50.74%  |
| DDR4    | 2665      | 25.58%  |
| DDR2    | 1127      | 10.82%  |
| SDRAM   | 520       | 4.99%   |
| LPDDR4  | 306       | 2.94%   |
| Unknown | 135       | 1.3%    |
| DDR     | 132       | 1.27%   |
| DRAM    | 100       | 0.96%   |
| LPDDR3  | 85        | 0.82%   |
| LPDDR5  | 34        | 0.33%   |
| DDR5    | 26        | 0.25%   |
| SRAM    | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 9605      | 94.02%  |
| Row Of Chips | 487       | 4.77%   |
| DIMM         | 92        | 0.9%    |
| Chip         | 24        | 0.23%   |
| Unknown      | 8         | 0.08%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 4307      | 35.78%  |
| 2048    | 3197      | 26.56%  |
| 8192    | 2735      | 22.72%  |
| 1024    | 1053      | 8.75%   |
| 16384   | 483       | 4.01%   |
| 512     | 138       | 1.15%   |
| 32768   | 97        | 0.81%   |
| 256     | 16        | 0.13%   |
| 12288   | 5         | 0.04%   |
| Unknown | 5         | 0.04%   |
| 1536    | 3         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 3195      | 27.57%  |
| 1334    | 1336      | 11.53%  |
| 2667    | 1276      | 11.01%  |
| 3200    | 1059      | 9.14%   |
| 1333    | 837       | 7.22%   |
| 667     | 689       | 5.95%   |
| Unknown | 648       | 5.59%   |
| 2400    | 535       | 4.62%   |
| 4199    | 285       | 2.46%   |
| 800     | 265       | 2.29%   |
| 1067    | 256       | 2.21%   |
| 2133    | 240       | 2.07%   |
| 533     | 157       | 1.35%   |
| 3266    | 144       | 1.24%   |
| 2048    | 108       | 0.93%   |
| 1066    | 104       | 0.9%    |
| 975     | 66        | 0.57%   |
| 1867    | 59        | 0.51%   |
| 4267    | 49        | 0.42%   |
| 333     | 47        | 0.41%   |
| 6400    | 34        | 0.29%   |
| 3733    | 29        | 0.25%   |
| 4800    | 27        | 0.23%   |
| 400     | 26        | 0.22%   |
| 1639    | 22        | 0.19%   |
| 4266    | 20        | 0.17%   |
| 1866    | 20        | 0.17%   |
| 8400    | 16        | 0.14%   |
| 2933    | 9         | 0.08%   |
| 200     | 4         | 0.03%   |
| 65535   | 3         | 0.03%   |
| 2666    | 3         | 0.03%   |
| 1776    | 3         | 0.03%   |
| 266     | 3         | 0.03%   |
| 100     | 3         | 0.03%   |
| 1       | 3         | 0.03%   |
| 2800    | 2         | 0.02%   |
| 2267    | 2         | 0.02%   |
| 5600    | 1         | 0.01%   |
| 1596    | 1         | 0.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 66        | 27.85%  |
| Canon                  | 46        | 19.41%  |
| Samsung Electronics    | 38        | 16.03%  |
| Seiko Epson            | 21        | 8.86%   |
| Brother Industries     | 17        | 7.17%   |
| Xerox                  | 13        | 5.49%   |
| Panasonic (Matsushita) | 12        | 5.06%   |
| Ricoh                  | 9         | 3.8%    |
| Pantum                 | 6         | 2.53%   |
| Kyocera                | 3         | 1.27%   |
| Xiaomi                 | 2         | 0.84%   |
| Prolific Technology    | 1         | 0.42%   |
| NXP Semiconductors     | 1         | 0.42%   |
| Lexmark International  | 1         | 0.42%   |
| iDPRT                  | 1         | 0.42%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                             | 9         | 3.78%   |
| Samsung SCX-4200 series                                      | 6         | 2.52%   |
| Samsung SCX-3400 Series                                      | 6         | 2.52%   |
| Panasonic (Matsushita) KX-MB1500RU                           | 6         | 2.52%   |
| HP LaserJet P1102                                            | 6         | 2.52%   |
| Samsung SCX-3200 Series                                      | 5         | 2.1%    |
| Panasonic (Matsushita) KX-MB2030 Multifunction Laser Printer | 5         | 2.1%    |
| Xerox B205                                                   | 4         | 1.68%   |
| Samsung ML-1210 Printer                                      | 4         | 1.68%   |
| Samsung M2020 Series                                         | 4         | 1.68%   |
| HP LaserJet 1200                                             | 4         | 1.68%   |
| Canon PIXMA MG2500 Series                                    | 4         | 1.68%   |
| Canon LBP6020                                                | 4         | 1.68%   |
| Brother HL-1110 series                                       | 4         | 1.68%   |
| Seiko Epson L210 Series                                      | 3         | 1.26%   |
| Seiko Epson L200 Series                                      | 3         | 1.26%   |
| Samsung ML-1640 Series Laser Printer                         | 3         | 1.26%   |
| HP LaserJet P1005                                            | 3         | 1.26%   |
| HP LaserJet 1018                                             | 3         | 1.26%   |
| HP DeskJet 2300 series                                       | 3         | 1.26%   |
| Canon MF4010 series                                          | 3         | 1.26%   |
| Canon LBP7010C/7018C                                         | 3         | 1.26%   |
| Canon LBP3010/LBP3018/LBP3050                                | 3         | 1.26%   |
| Canon LaserShot LBP-1120 Printer                             | 3         | 1.26%   |
| Canon G1000 series                                           | 3         | 1.26%   |
| Brother HL-L2300D series                                     | 3         | 1.26%   |
| Xiaomi MiMouse 2                                             | 2         | 0.84%   |
| Xerox Phaser 3020                                            | 2         | 0.84%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                        | 2         | 0.84%   |
| Seiko Epson Printer                                          | 2         | 0.84%   |
| Seiko Epson L132 Series                                      | 2         | 0.84%   |
| Seiko Epson L120 Series                                      | 2         | 0.84%   |
| Samsung ML-1865                                              | 2         | 0.84%   |
| Samsung M2070 Series                                         | 2         | 0.84%   |
| Ricoh SP 150SUw                                              | 2         | 0.84%   |
| Pantum P2200 series                                          | 2         | 0.84%   |
| Pantum M6500 series                                          | 2         | 0.84%   |
| Kyocera FS-1120MFP                                           | 2         | 0.84%   |
| HP LaserJet Professional P1102w                              | 2         | 0.84%   |
| HP LaserJet 1320                                             | 2         | 0.84%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Seiko Epson                 | 14        | 32.56%  |
| Canon                       | 10        | 23.26%  |
| Hewlett-Packard             | 8         | 18.6%   |
| Mustek Systems              | 5         | 11.63%  |
| Ultima Electronics          | 2         | 4.65%   |
| KYE Systems (Mouse Systems) | 2         | 4.65%   |
| Acer Peripherals (now BenQ) | 2         | 4.65%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 5         | 11.63%  |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 2         | 4.65%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 2         | 4.65%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 2         | 4.65%   |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 4.65%   |
| HP ScanJet 3770                                                                       | 2         | 4.65%   |
| HP ScanJet 2400c                                                                      | 2         | 4.65%   |
| HP Scanjet 200                                                                        | 2         | 4.65%   |
| Canon CanoScan LIDE 25                                                                | 2         | 4.65%   |
| Canon CanoScan LiDE 120                                                               | 2         | 4.65%   |
| Canon CanoScan LiDE 110                                                               | 2         | 4.65%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 2.33%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 1         | 2.33%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 2.33%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 1         | 2.33%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 1         | 2.33%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 2.33%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 1         | 2.33%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 1         | 2.33%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4                                          | 1         | 2.33%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE                                   | 1         | 2.33%   |
| HP ScanJet G4010                                                                      | 1         | 2.33%   |
| HP Scanjet 300                                                                        | 1         | 2.33%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 1         | 2.33%   |
| Canon CanoScan LiDE 70                                                                | 1         | 2.33%   |
| Canon CanoScan LiDE 220                                                               | 1         | 2.33%   |
| Canon CanoScan 4400F                                                                  | 1         | 2.33%   |
| Acer Peripherals (now BenQ) Benq 5150/5250                                            | 1         | 2.33%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 1         | 2.33%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2739      | 25.26%  |
| IMC Networks                           | 1333      | 12.29%  |
| Bison Electronics                      | 768       | 7.08%   |
| Realtek Semiconductor                  | 733       | 6.76%   |
| Suyin                                  | 650       | 5.99%   |
| Microdia                               | 558       | 5.15%   |
| Sunplus Innovation Technology          | 517       | 4.77%   |
| Quanta                                 | 479       | 4.42%   |
| Silicon Motion                         | 413       | 3.81%   |
| Cheng Uei Precision Industry (Foxlink) | 393       | 3.62%   |
| Syntek                                 | 329       | 3.03%   |
| Alcor Micro                            | 293       | 2.7%    |
| Acer                                   | 273       | 2.52%   |
| Z-Star Microelectronics                | 163       | 1.5%    |
| Lite-On Technology                     | 125       | 1.15%   |
| Ricoh                                  | 119       | 1.1%    |
| Luxvisions Innotech Limited            | 112       | 1.03%   |
| Apple                                  | 112       | 1.03%   |
| ALi                                    | 107       | 0.99%   |
| DigiTech                               | 85        | 0.78%   |
| Logitech                               | 64        | 0.59%   |
| Sonix Technology                       | 50        | 0.46%   |
| Lenovo                                 | 41        | 0.38%   |
| SunplusIT                              | 37        | 0.34%   |
| Samsung Electronics                    | 37        | 0.34%   |
| Primax Electronics                     | 34        | 0.31%   |
| icSpring                               | 30        | 0.28%   |
| Y Media                                | 23        | 0.21%   |
| Importek                               | 22        | 0.2%    |
| Sunplus Technology                     | 18        | 0.17%   |
| Unknown                                | 17        | 0.16%   |
| OmniVision Technologies                | 15        | 0.14%   |
| GEMBIRD                                | 15        | 0.14%   |
| USB Camera CS                          | 14        | 0.13%   |
| Image Processor                        | 9         | 0.08%   |
| Genesys Logic                          | 9         | 0.08%   |
| Pixart Imaging                         | 7         | 0.06%   |
| Nebraska Furniture Mart                | 6         | 0.06%   |
| Shine-optics                           | 5         | 0.05%   |
| Microsoft                              | 5         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony HD WebCam                                | 286       | 2.63%   |
| Chicony Integrated Camera                        | 263       | 2.42%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 252       | 2.32%   |
| Chicony Lenovo EasyCamera                        | 226       | 2.08%   |
| IMC Networks USB2.0 HD UVC WebCam                | 203       | 1.87%   |
| Bison Lenovo Integrated Webcam                   | 191       | 1.76%   |
| Sunplus HD WebCam                                | 173       | 1.59%   |
| Microdia Integrated_Webcam_HD                    | 159       | 1.46%   |
| IMC Networks Integrated Camera                   | 153       | 1.41%   |
| IMC Networks UVC VGA Webcam                      | 142       | 1.31%   |
| Chicony USB2.0 HD UVC WebCam                     | 140       | 1.29%   |
| Chicony USB 2.0 Camera                           | 124       | 1.14%   |
| Bison BisonCam, NB Pro                           | 121       | 1.11%   |
| Bison Integrated Camera                          | 117       | 1.08%   |
| Realtek Integrated_Webcam_HD                     | 113       | 1.04%   |
| Chicony HP Webcam                                | 106       | 0.98%   |
| Chicony VGA Webcam                               | 105       | 0.97%   |
| IMC Networks HD Camera                           | 103       | 0.95%   |
| Syntek Integrated Camera                         | 99        | 0.91%   |
| Realtek Lenovo EasyCamera                        | 99        | 0.91%   |
| Quanta VGA WebCam                                | 96        | 0.88%   |
| Chicony USB2.0 VGA UVC WebCam                    | 92        | 0.85%   |
| Alcor Micro Asus Integrated Webcam               | 88        | 0.81%   |
| Silicon Motion WebCam SC-0311139N                | 85        | 0.78%   |
| IMC Networks Integrated Webcam                   | 80        | 0.74%   |
| Syntek Lenovo EasyCamera                         | 79        | 0.73%   |
| Realtek USB Camera                               | 79        | 0.73%   |
| Suyin Acer/HP Integrated Webcam [CN0314]         | 77        | 0.71%   |
| DigiTech USB 2.0 PC Camera                       | 77        | 0.71%   |
| Chicony 2.0M UVC Webcam / CNF7129                | 77        | 0.71%   |
| Chicony HP TrueVision HD                         | 76        | 0.7%    |
| Sunplus Integrated_Webcam_HD                     | 75        | 0.69%   |
| Acer Lenovo EasyCamera                           | 75        | 0.69%   |
| ALi Gateway Webcam                               | 72        | 0.66%   |
| Alcor Micro USB 2.0 PC cam                       | 71        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 70        | 0.64%   |
| Bison Lenovo EasyCamera                          | 67        | 0.62%   |
| Silicon Motion WebCam SCB-1100N                  | 65        | 0.6%    |
| Chicony EasyCamera                               | 65        | 0.6%    |
| Sunplus Asus Webcam                              | 63        | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 452       | 31.04%  |
| Shenzhen Goodix Technology         | 295       | 20.26%  |
| Synaptics                          | 205       | 14.08%  |
| AuthenTec                          | 138       | 9.48%   |
| Upek                               | 111       | 7.62%   |
| Elan Microelectronics              | 98        | 6.73%   |
| LighTuning Technology              | 96        | 6.59%   |
| STMicroelectronics                 | 35        | 2.4%    |
| Realtek USB2.0 Finger Print Bridge | 13        | 0.89%   |
| Focal-systems.Corp                 | 11        | 0.76%   |
| Samsung Electronics                | 1         | 0.07%   |
| GDMicroelectronics                 | 1         | 0.07%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 240       | 16.48%  |
| Validity Sensors Fingerprint scanner                                       | 103       | 7.07%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 93        | 6.39%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 89        | 6.11%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 74        | 5.08%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 66        | 4.53%   |
| Elan ELAN:Fingerprint                                                      | 51        | 3.5%    |
| Shenzhen Goodix Fingerprint Reader                                         | 47        | 3.23%   |
| LighTuning Fingerprint Reader                                              | 45        | 3.09%   |
| AuthenTec AES1600                                                          | 42        | 2.88%   |
| STMicroelectronics Fingerprint Reader                                      | 35        | 2.4%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 34        | 2.34%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 33        | 2.27%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 33        | 2.27%   |
| Elan ELAN:ARM-M4                                                           | 30        | 2.06%   |
| Validity Sensors VFS491                                                    | 28        | 1.92%   |
| AuthenTec AES2810                                                          | 28        | 1.92%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 26        | 1.79%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 26        | 1.79%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 23        | 1.58%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 22        | 1.51%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 20        | 1.37%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 1.3%    |
| Upek TCS5B Fingerprint sensor                                              | 18        | 1.24%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 18        | 1.24%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 16        | 1.1%    |
| Synaptics Fingerprint reader [HP G6]                                       | 16        | 1.1%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 15        | 1.03%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 0.96%   |
| Elan WBF Fingerprint Sensor                                                | 14        | 0.96%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 13        | 0.89%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 12        | 0.82%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 12        | 0.82%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 0.76%   |
| Synaptics  WBDI                                                            | 11        | 0.76%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 11        | 0.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 10        | 0.69%   |
| Synaptics UWP WBDI Device                                                  | 10        | 0.69%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 0.62%   |
| Shenzhen Goodix FingerPrint                                                | 8         | 0.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 102       | 37.36%  |
| Broadcom                  | 88        | 32.23%  |
| Upek                      | 26        | 9.52%   |
| O2 Micro                  | 21        | 7.69%   |
| Lenovo                    | 16        | 5.86%   |
| Yubico.com                | 5         | 1.83%   |
| Gemalto (was Gemplus)     | 4         | 1.47%   |
| Aladdin Knowledge Systems | 4         | 1.47%   |
| Aladdin R.D.              | 3         | 1.1%    |
| Aktiv                     | 3         | 1.1%    |
| Microchip Technology      | 1         | 0.37%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 100       | 36.63%  |
| Broadcom BCM5880 Secure Applications Processor                               | 34        | 12.45%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 9.52%   |
| Broadcom 5880                                                                | 19        | 6.96%   |
| Broadcom 58200                                                               | 19        | 6.96%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 6.59%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 5.86%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 16        | 5.86%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 5         | 1.83%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 1.47%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 1.1%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.1%    |
| Aladdin R.D. JaCarta                                                         | 3         | 1.1%    |
| Aktiv Rutoken lite                                                           | 3         | 1.1%    |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.37%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.37%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.37%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.37%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 8524      | 66.5%   |
| 1     | 3403      | 26.55%  |
| 2     | 747       | 5.83%   |
| 3     | 117       | 0.91%   |
| 4     | 19        | 0.15%   |
| 5     | 6         | 0.05%   |
| 6     | 2         | 0.02%   |
| 7     | 1         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1848      | 37.41%  |
| Fingerprint reader       | 1449      | 29.33%  |
| Net/wireless             | 452       | 9.15%   |
| Bluetooth                | 264       | 5.34%   |
| Multimedia controller    | 248       | 5.02%   |
| Chipcard                 | 236       | 4.78%   |
| Camera                   | 129       | 2.61%   |
| Communication controller | 83        | 1.68%   |
| Flash memory             | 65        | 1.32%   |
| Storage                  | 64        | 1.3%    |
| Card reader              | 28        | 0.57%   |
| Sound                    | 22        | 0.45%   |
| Net/ethernet             | 16        | 0.32%   |
| Modem                    | 13        | 0.26%   |
| Network                  | 7         | 0.14%   |
| Dvb card                 | 6         | 0.12%   |
| Storage/ide              | 4         | 0.08%   |
| Firewire controller      | 2         | 0.04%   |
| Wireless                 | 1         | 0.02%   |
| Unclassified device      | 1         | 0.02%   |
| Tv card                  | 1         | 0.02%   |
| Storage/raid             | 1         | 0.02%   |

