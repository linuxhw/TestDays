Kubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Kubuntu.

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

Total: 2781

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A515-57              | [4a1b8f3f21](https://linux-hardware.org/?probe=4a1b8f3f21) | Apr 01, 2023 |
| Gigabyte      | A7 K1                       | [e5e7751054](https://linux-hardware.org/?probe=e5e7751054) | Mar 31, 2023 |
| Chuwi         | CoreBook XPro               | [85ad17d246](https://linux-hardware.org/?probe=85ad17d246) | Mar 31, 2023 |
| Intel         | Whiskey Platform            | [36b9d4d898](https://linux-hardware.org/?probe=36b9d4d898) | Mar 31, 2023 |
| Dell          | Vostro 15-3568              | [3636f7f999](https://linux-hardware.org/?probe=3636f7f999) | Mar 30, 2023 |
| Motion Com... | J3600                       | [0980fe0a37](https://linux-hardware.org/?probe=0980fe0a37) | Mar 30, 2023 |
| Intel         | Whiskey Platform            | [a96edb2321](https://linux-hardware.org/?probe=a96edb2321) | Mar 30, 2023 |
| HP            | Laptop 15-ef2xxx            | [278ed0e013](https://linux-hardware.org/?probe=278ed0e013) | Mar 30, 2023 |
| Gigabyte      | AERO 15-X9                  | [49f246c5e7](https://linux-hardware.org/?probe=49f246c5e7) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| Apple         | MacBookPro8,1               | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| MSI           | Modern 15 A5M               | [84092aca44](https://linux-hardware.org/?probe=84092aca44) | Mar 27, 2023 |
| HP            | EliteBook 8460p             | [ccae23c5a7](https://linux-hardware.org/?probe=ccae23c5a7) | Mar 27, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| Dell          | Inspiron 15-3567            | [ffb310e799](https://linux-hardware.org/?probe=ffb310e799) | Mar 26, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [369363c3a9](https://linux-hardware.org/?probe=369363c3a9) | Mar 26, 2023 |
| HUAWEI        | HN-WX9X                     | [cdc4b03fe2](https://linux-hardware.org/?probe=cdc4b03fe2) | Mar 26, 2023 |
| HP            | Laptop 15-ef2xxx            | [2246abad85](https://linux-hardware.org/?probe=2246abad85) | Mar 25, 2023 |
| Digibras      | NH4CU03                     | [4262f0e159](https://linux-hardware.org/?probe=4262f0e159) | Mar 25, 2023 |
| Intel         | Whiskey Platform            | [e90c029740](https://linux-hardware.org/?probe=e90c029740) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | [a0bba69c40](https://linux-hardware.org/?probe=a0bba69c40) | Mar 25, 2023 |
| Dell          | Inspiron 7400               | [98d0daa764](https://linux-hardware.org/?probe=98d0daa764) | Mar 25, 2023 |
| Dell          | Latitude E6420              | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| Carbon Sys... | Iridium 14                  | [e7f9195a1d](https://linux-hardware.org/?probe=e7f9195a1d) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c114580013](https://linux-hardware.org/?probe=c114580013) | Mar 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1f256fa102](https://linux-hardware.org/?probe=1f256fa102) | Mar 24, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c7ec617422](https://linux-hardware.org/?probe=c7ec617422) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | [63fafca0ac](https://linux-hardware.org/?probe=63fafca0ac) | Mar 24, 2023 |
| HONOR         | BBR-WAX9                    | [2d8268e40f](https://linux-hardware.org/?probe=2d8268e40f) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | [16b93bfe5d](https://linux-hardware.org/?probe=16b93bfe5d) | Mar 24, 2023 |
| Dell          | Latitude 5420               | [42d5b573c4](https://linux-hardware.org/?probe=42d5b573c4) | Mar 24, 2023 |
| Dell          | Latitude E7470              | [ca8a2d9579](https://linux-hardware.org/?probe=ca8a2d9579) | Mar 24, 2023 |
| HP            | Laptop 15-ef2xxx            | [9b048b064d](https://linux-hardware.org/?probe=9b048b064d) | Mar 24, 2023 |
| Dell          | Vostro 5620                 | [529a2febf7](https://linux-hardware.org/?probe=529a2febf7) | Mar 23, 2023 |
| Notebook      | NV4xPZ                      | [74d70a3568](https://linux-hardware.org/?probe=74d70a3568) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | [631968d54b](https://linux-hardware.org/?probe=631968d54b) | Mar 23, 2023 |
| HP            | ZBook 15 G6                 | [61dcde6523](https://linux-hardware.org/?probe=61dcde6523) | Mar 22, 2023 |
| Dell          | Latitude E7470              | [9595c39422](https://linux-hardware.org/?probe=9595c39422) | Mar 22, 2023 |
| Sony          | VGN-NW270F                  | [48080babd0](https://linux-hardware.org/?probe=48080babd0) | Mar 22, 2023 |
| MSI           | GE70 2PE                    | [5e68fcc30d](https://linux-hardware.org/?probe=5e68fcc30d) | Mar 22, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | [ae63ffa582](https://linux-hardware.org/?probe=ae63ffa582) | Mar 21, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2da4187f91](https://linux-hardware.org/?probe=2da4187f91) | Mar 21, 2023 |
| HP            | ProBook 640 G4              | [2787c4bf42](https://linux-hardware.org/?probe=2787c4bf42) | Mar 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [83fbe3a3d6](https://linux-hardware.org/?probe=83fbe3a3d6) | Mar 20, 2023 |
| ASUSTek       | T300CHI                     | [371961ad53](https://linux-hardware.org/?probe=371961ad53) | Mar 19, 2023 |
| Acer          | Nitro AN517-41              | [5e5fd3788e](https://linux-hardware.org/?probe=5e5fd3788e) | Mar 19, 2023 |
| Avell High... | C62 MOB                     | [7eaededaac](https://linux-hardware.org/?probe=7eaededaac) | Mar 18, 2023 |
| Carbon Sys... | Iridium 14                  | [c70e1d7e98](https://linux-hardware.org/?probe=c70e1d7e98) | Mar 18, 2023 |
| HP            | ZBook 15 G6                 | [5a429f93a7](https://linux-hardware.org/?probe=5a429f93a7) | Mar 18, 2023 |
| Clevo         | W340EU                      | [b90ad98b0a](https://linux-hardware.org/?probe=b90ad98b0a) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [786fded1ce](https://linux-hardware.org/?probe=786fded1ce) | Mar 17, 2023 |
| Clevo         | W340EU                      | [240779648a](https://linux-hardware.org/?probe=240779648a) | Mar 17, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [1ed7ccd033](https://linux-hardware.org/?probe=1ed7ccd033) | Mar 16, 2023 |
| Dell          | Inspiron 13 5310            | [697914b165](https://linux-hardware.org/?probe=697914b165) | Mar 16, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [69f39892c4](https://linux-hardware.org/?probe=69f39892c4) | Mar 15, 2023 |
| Dell          | Inspiron 5575               | [0ace5375f4](https://linux-hardware.org/?probe=0ace5375f4) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Lenovo        | ThinkPad X390 20Q0000SMX    | [8fff8ca97d](https://linux-hardware.org/?probe=8fff8ca97d) | Mar 15, 2023 |
| Lenovo        | ThinkPad E480 20KNA01HIG    | [c8054d1090](https://linux-hardware.org/?probe=c8054d1090) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | ZBook 15                    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [b5ef4ae548](https://linux-hardware.org/?probe=b5ef4ae548) | Mar 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [21fc92246e](https://linux-hardware.org/?probe=21fc92246e) | Mar 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [3c4e911c6d](https://linux-hardware.org/?probe=3c4e911c6d) | Mar 13, 2023 |
| HUAWEI        | HVY-WXX9                    | [e79cdeaf10](https://linux-hardware.org/?probe=e79cdeaf10) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| Acer          | Aspire A715-74G             | [57000f8a86](https://linux-hardware.org/?probe=57000f8a86) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [456057e6af](https://linux-hardware.org/?probe=456057e6af) | Mar 13, 2023 |
| Dell          | XPS 15 9570                 | [7ee93079fb](https://linux-hardware.org/?probe=7ee93079fb) | Mar 13, 2023 |
| Toshiba       | Satellite L515              | [11116a9517](https://linux-hardware.org/?probe=11116a9517) | Mar 13, 2023 |
| ASUSTek       | K55VJ                       | [6a0673f946](https://linux-hardware.org/?probe=6a0673f946) | Mar 13, 2023 |
| Dell          | Latitude E6420              | [6fe2914b41](https://linux-hardware.org/?probe=6fe2914b41) | Mar 12, 2023 |
| Acer          | Nitro AN515-55              | [60bc8c1ef5](https://linux-hardware.org/?probe=60bc8c1ef5) | Mar 12, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [4ee87a1213](https://linux-hardware.org/?probe=4ee87a1213) | Mar 12, 2023 |
| ASUSTek       | K55VJ                       | [d550e765ac](https://linux-hardware.org/?probe=d550e765ac) | Mar 12, 2023 |
| Toshiba       | Satellite L515              | [f2ffca7459](https://linux-hardware.org/?probe=f2ffca7459) | Mar 12, 2023 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | [bcbf6544cd](https://linux-hardware.org/?probe=bcbf6544cd) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK E734               | [9f02108ada](https://linux-hardware.org/?probe=9f02108ada) | Mar 09, 2023 |
| Fujitsu       | LIFEBOOK E734               | [5a0eb5bfed](https://linux-hardware.org/?probe=5a0eb5bfed) | Mar 09, 2023 |
| ASUSTek       | K55VJ                       | [2750a8a462](https://linux-hardware.org/?probe=2750a8a462) | Mar 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [b7fd2dfa30](https://linux-hardware.org/?probe=b7fd2dfa30) | Mar 09, 2023 |
| Dell          | Inspiron 15-3565            | [a71845e346](https://linux-hardware.org/?probe=a71845e346) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [2b74ad2ed1](https://linux-hardware.org/?probe=2b74ad2ed1) | Mar 08, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e777d1af00](https://linux-hardware.org/?probe=e777d1af00) | Mar 08, 2023 |
| Maibenben     | JinMai6 series              | [ace44d9872](https://linux-hardware.org/?probe=ace44d9872) | Mar 08, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [d3cd7ae3e8](https://linux-hardware.org/?probe=d3cd7ae3e8) | Mar 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [b48c76be97](https://linux-hardware.org/?probe=b48c76be97) | Mar 07, 2023 |
| HP            | ENVY TS 17                  | [c915d51f5e](https://linux-hardware.org/?probe=c915d51f5e) | Mar 07, 2023 |
| Datto         | 1000                        | [9df2913c36](https://linux-hardware.org/?probe=9df2913c36) | Mar 07, 2023 |
| Dell          | Inspiron 15-3567            | [2f8d0ff7f5](https://linux-hardware.org/?probe=2f8d0ff7f5) | Mar 06, 2023 |
| ASUSTek       | K52JT                       | [802fe86b5c](https://linux-hardware.org/?probe=802fe86b5c) | Mar 06, 2023 |
| Alienware     | x14                         | [a1665c85ab](https://linux-hardware.org/?probe=a1665c85ab) | Mar 06, 2023 |
| Alienware     | x14                         | [8f12fe3ee5](https://linux-hardware.org/?probe=8f12fe3ee5) | Mar 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [6db57d4d9f](https://linux-hardware.org/?probe=6db57d4d9f) | Mar 05, 2023 |
| HUAWEI        | HVY-WXX9                    | [28dbdcfbb7](https://linux-hardware.org/?probe=28dbdcfbb7) | Mar 05, 2023 |
| Dell          | Latitude E6420              | [569d016799](https://linux-hardware.org/?probe=569d016799) | Mar 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2311f1da09](https://linux-hardware.org/?probe=2311f1da09) | Mar 05, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [63e9a399f8](https://linux-hardware.org/?probe=63e9a399f8) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| HP            | Pavilion 11 x360 PC         | [a7860ee046](https://linux-hardware.org/?probe=a7860ee046) | Mar 04, 2023 |
| Dell          | XPS 13 9310                 | [c654c1809d](https://linux-hardware.org/?probe=c654c1809d) | Mar 04, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5a15c4c2b0](https://linux-hardware.org/?probe=5a15c4c2b0) | Mar 03, 2023 |
| Digibras      | NH4CU03                     | [a5939aa47c](https://linux-hardware.org/?probe=a5939aa47c) | Mar 03, 2023 |
| Dell          | Latitude 5420               | [b763e54ded](https://linux-hardware.org/?probe=b763e54ded) | Mar 03, 2023 |
| HP            | Pavilion 11 x360 PC         | [82847b3b1f](https://linux-hardware.org/?probe=82847b3b1f) | Mar 02, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [cc8c299b5d](https://linux-hardware.org/?probe=cc8c299b5d) | Mar 01, 2023 |
| Dell          | XPS 15 9520                 | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [41439f6b61](https://linux-hardware.org/?probe=41439f6b61) | Feb 28, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ad20f98122](https://linux-hardware.org/?probe=ad20f98122) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [b410d220e6](https://linux-hardware.org/?probe=b410d220e6) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| HP            | G62                         | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [0b9491b3a0](https://linux-hardware.org/?probe=0b9491b3a0) | Feb 25, 2023 |
| System76      | Gazelle                     | [64fcb063eb](https://linux-hardware.org/?probe=64fcb063eb) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| MSI           | GE75 Raider 9SE             | [6d0782da8e](https://linux-hardware.org/?probe=6d0782da8e) | Feb 24, 2023 |
| Dell          | System Inspiron N7110       | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| Dell          | Inspiron 7400               | [0d286f12f4](https://linux-hardware.org/?probe=0d286f12f4) | Feb 21, 2023 |
| GPU Compan... | GWTC116-2                   | [5fa20b737f](https://linux-hardware.org/?probe=5fa20b737f) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Apple         | MacBookAir3,1               | [1e0de945b7](https://linux-hardware.org/?probe=1e0de945b7) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [7e5327c1ed](https://linux-hardware.org/?probe=7e5327c1ed) | Feb 19, 2023 |
| HP            | ProBook 4730s               | [99232fe32d](https://linux-hardware.org/?probe=99232fe32d) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| HP            | Victus by Laptop 16z-e10... | [a48460122c](https://linux-hardware.org/?probe=a48460122c) | Feb 19, 2023 |
| Acer          | Aspire A515-46              | [46a8b61785](https://linux-hardware.org/?probe=46a8b61785) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| Alienware     | 17 R2                       | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Acer          | Aspire A717-71G             | [488a80bcda](https://linux-hardware.org/?probe=488a80bcda) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a16c82308f](https://linux-hardware.org/?probe=a16c82308f) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| Dell          | G15 5515                    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [043e92c2ee](https://linux-hardware.org/?probe=043e92c2ee) | Feb 15, 2023 |
| HP            | Pavilion 11 x360 PC         | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Dell          | Inspiron 7400               | [4cc741a70a](https://linux-hardware.org/?probe=4cc741a70a) | Feb 13, 2023 |
| Acer          | Swift SF314-512             | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| HP            | ProBook 6470b               | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [920b8786c6](https://linux-hardware.org/?probe=920b8786c6) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [50163cfc72](https://linux-hardware.org/?probe=50163cfc72) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | [566c6a5316](https://linux-hardware.org/?probe=566c6a5316) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | [a833fa9a0c](https://linux-hardware.org/?probe=a833fa9a0c) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| Google        | Blooguard                   | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| HP            | Notebook                    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| HP            | Notebook                    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| HP            | Notebook                    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| HP            | Laptop 15-da2xxx            | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | XPS 17 9720                 | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Acer          | Nitro AN515-45              | [bb420e8f71](https://linux-hardware.org/?probe=bb420e8f71) | Feb 05, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ce7bdb0a98](https://linux-hardware.org/?probe=ce7bdb0a98) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| HP            | G60                         | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Lenovo        | IdeaPad U310 Touch          | [6fd17687a4](https://linux-hardware.org/?probe=6fd17687a4) | Feb 04, 2023 |
| Acer          | Nitro AN515-55              | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Chuwi         | Hi10 Go                     | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [690d45db9f](https://linux-hardware.org/?probe=690d45db9f) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Dell          | Inspiron 5570               | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Medion        | E15410                      | [24135c324e](https://linux-hardware.org/?probe=24135c324e) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| HP            | Notebook                    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| Google        | Lillipup                    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | GS66 Stealth 10SE           | [bf112866e3](https://linux-hardware.org/?probe=bf112866e3) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Acer          | Nitro AN517-41              | [ecb7c49d2e](https://linux-hardware.org/?probe=ecb7c49d2e) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Dell          | Precision 7730              | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| Dell          | Inspiron 5593               | [36db3e5d78](https://linux-hardware.org/?probe=36db3e5d78) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [b265f91d10](https://linux-hardware.org/?probe=b265f91d10) | Jan 27, 2023 |
| HP            | Laptop 15-da0xxx            | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| ASUSTek       | GL503VD                     | [f4095c61ff](https://linux-hardware.org/?probe=f4095c61ff) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Medion        | E15410                      | [5ba9ffd6a8](https://linux-hardware.org/?probe=5ba9ffd6a8) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| Dell          | Latitude 5491               | [37746d7f71](https://linux-hardware.org/?probe=37746d7f71) | Jan 24, 2023 |
| Medion        | E15410                      | [f7e27f2ba9](https://linux-hardware.org/?probe=f7e27f2ba9) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [4f83721cab](https://linux-hardware.org/?probe=4f83721cab) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [9e12a145fd](https://linux-hardware.org/?probe=9e12a145fd) | Jan 23, 2023 |
| HP            | ProBook 6470b               | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [df35617170](https://linux-hardware.org/?probe=df35617170) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | ProBook 6570b               | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Dell          | Vostro 1014                 | [f7ff3312f2](https://linux-hardware.org/?probe=f7ff3312f2) | Jan 21, 2023 |
| Acer          | TravelMate B118-M           | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | [724939f0cf](https://linux-hardware.org/?probe=724939f0cf) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| HP            | Laptop 15-ef2xxx            | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Sony          | SVE1513B4E                  | [cbd9f98f30](https://linux-hardware.org/?probe=cbd9f98f30) | Jan 20, 2023 |
| Dell          | G3 3779                     | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| HP            | Laptop 15-ef2xxx            | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| HP            | Notebook                    | [1c935be3b1](https://linux-hardware.org/?probe=1c935be3b1) | Jan 18, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| HP            | Laptop 17-by3xxx            | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Acer          | Swift SF113-31              | [de76cee99a](https://linux-hardware.org/?probe=de76cee99a) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| Notebook      | W35xSS_370SS                | [2337667e0f](https://linux-hardware.org/?probe=2337667e0f) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3a97589bc9](https://linux-hardware.org/?probe=3a97589bc9) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ed648f1f72](https://linux-hardware.org/?probe=ed648f1f72) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| MSI           | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | [b9df733a47](https://linux-hardware.org/?probe=b9df733a47) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | [75209e7521](https://linux-hardware.org/?probe=75209e7521) | Jan 10, 2023 |
| HP            | ProBook 6570b               | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [5d3f8e9948](https://linux-hardware.org/?probe=5d3f8e9948) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| Dell          | Inspiron 5570               | [4ebc1e97c5](https://linux-hardware.org/?probe=4ebc1e97c5) | Jan 07, 2023 |
| Dell          | Inspiron 5570               | [86b0308f38](https://linux-hardware.org/?probe=86b0308f38) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| Acer          | Swift SF314-71              | [21ebb26df9](https://linux-hardware.org/?probe=21ebb26df9) | Jan 05, 2023 |
| HP            | 250 G4 Notebook PC          | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Acer          | Aspire M5-583P              | [1182d7305d](https://linux-hardware.org/?probe=1182d7305d) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| Unknown       | Unknown                     | [7a85f424f5](https://linux-hardware.org/?probe=7a85f424f5) | Jan 03, 2023 |
| HUAWEI        | NBLL-WXX9                   | [7e5acbf050](https://linux-hardware.org/?probe=7e5acbf050) | Jan 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [059e72c9a0](https://linux-hardware.org/?probe=059e72c9a0) | Jan 03, 2023 |
| MSI           | Raider GE76 12UGS           | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [d8d521b964](https://linux-hardware.org/?probe=d8d521b964) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| Dell          | Inspiron 5515               | [27a4df28b2](https://linux-hardware.org/?probe=27a4df28b2) | Jan 03, 2023 |
| MSI           | Alpha 17 B5EEK              | [a5881c627c](https://linux-hardware.org/?probe=a5881c627c) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [ccebb5dd27](https://linux-hardware.org/?probe=ccebb5dd27) | Jan 02, 2023 |
| HP            | ENVY TS 15                  | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| MSI           | Prestige 14 A10RAS          | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0fb41a5066](https://linux-hardware.org/?probe=0fb41a5066) | Jan 02, 2023 |
| MSI           | Raider GE67HX 12UGS         | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| HP            | Notebook                    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Notebook      | P17SM                       | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| Apple         | MacBookPro14,3              | [fdd6af96b3](https://linux-hardware.org/?probe=fdd6af96b3) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| Acer          | Aspire 5742G                | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| HP            | Beats 15                    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Dell          | Inspiron 5775               | [cfb1c3fcd6](https://linux-hardware.org/?probe=cfb1c3fcd6) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Acer          | Aspire A517-53              | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0413176ecc](https://linux-hardware.org/?probe=0413176ecc) | Dec 25, 2022 |
| HP            | EliteBook Folio 1040 G3     | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Samsung       | 550P5C/550P7C               | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| HP            | Pavilion dv7                | [5e5eb2c983](https://linux-hardware.org/?probe=5e5eb2c983) | Dec 22, 2022 |
| SGIN          | laptop                      | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| HP            | Laptop 17-by3xxx            | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [60a56500f1](https://linux-hardware.org/?probe=60a56500f1) | Dec 18, 2022 |
| Dell          | Precision 5540              | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc473cc90f](https://linux-hardware.org/?probe=fc473cc90f) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [89166d1da4](https://linux-hardware.org/?probe=89166d1da4) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [d8d72f23e6](https://linux-hardware.org/?probe=d8d72f23e6) | Dec 14, 2022 |
| Apple         | MacBookPro14,2              | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Lenovo        | ThinkPad T61 7665VJM        | [f1ff113e65](https://linux-hardware.org/?probe=f1ff113e65) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c18a20ec35](https://linux-hardware.org/?probe=c18a20ec35) | Dec 13, 2022 |
| Acer          | Nitro AN517-54              | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Acer          | Aspire A515-44              | [965817e5f0](https://linux-hardware.org/?probe=965817e5f0) | Dec 11, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [48e21506f4](https://linux-hardware.org/?probe=48e21506f4) | Dec 11, 2022 |
| HP            | Pavilion g7                 | [94cc8be22c](https://linux-hardware.org/?probe=94cc8be22c) | Dec 11, 2022 |
| Acer          | Predator PH317-52           | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d28d2da00b](https://linux-hardware.org/?probe=d28d2da00b) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| Lenovo        | ThinkPad T420 4236PZ0       | [603c3b47a9](https://linux-hardware.org/?probe=603c3b47a9) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Monster       | TULPAR T7 V21.6             | [1fb4eaf6d4](https://linux-hardware.org/?probe=1fb4eaf6d4) | Dec 06, 2022 |
| HP            | Beats 15                    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| HP            | 550                         | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| Dell          | Inspiron 7577               | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| HUAWEI        | CREM-WXX9                   | [535444f416](https://linux-hardware.org/?probe=535444f416) | Dec 05, 2022 |
| Monster       | TULPAR T7 V21.6             | [8c2ed08d33](https://linux-hardware.org/?probe=8c2ed08d33) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| HP            | ProBook 430 G2              | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41824c584f](https://linux-hardware.org/?probe=41824c584f) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Google        | Kled                        | [06c52b65d2](https://linux-hardware.org/?probe=06c52b65d2) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | ProBook 450 G2              | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| Haier         | A1420EM                     | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Razer         | Blade Stealth               | [e182c3c739](https://linux-hardware.org/?probe=e182c3c739) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8f17b6a915](https://linux-hardware.org/?probe=8f17b6a915) | Nov 29, 2022 |
| Dell          | G3 3779                     | [3e85396dae](https://linux-hardware.org/?probe=3e85396dae) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Dell          | G3 3779                     | [2def46f37c](https://linux-hardware.org/?probe=2def46f37c) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Toshiba       | Satellite C670D-126         | [6c2fc84bf2](https://linux-hardware.org/?probe=6c2fc84bf2) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| GPD           | G1621-02                    | [d6b679024c](https://linux-hardware.org/?probe=d6b679024c) | Nov 26, 2022 |
| Dell          | Latitude E6440              | [348f786878](https://linux-hardware.org/?probe=348f786878) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [a4512e8a71](https://linux-hardware.org/?probe=a4512e8a71) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Dell          | Latitude 5410               | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| HP            | Unknown                     | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| Acer          | Aspire ES1-711G             | [8852f94b38](https://linux-hardware.org/?probe=8852f94b38) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Acer          | Nitro AN517-51              | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [36bc4b545f](https://linux-hardware.org/?probe=36bc4b545f) | Nov 19, 2022 |
| Toshiba       | Satellite C670D-126         | [17e464f802](https://linux-hardware.org/?probe=17e464f802) | Nov 19, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [6e0f255eeb](https://linux-hardware.org/?probe=6e0f255eeb) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| Dell          | Inspiron 1545               | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [cc20cc9828](https://linux-hardware.org/?probe=cc20cc9828) | Nov 16, 2022 |
| Dell          | Inspiron 1545               | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [e7152e6cb3](https://linux-hardware.org/?probe=e7152e6cb3) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [a30ec58d99](https://linux-hardware.org/?probe=a30ec58d99) | Nov 16, 2022 |
| Dell          | Latitude E7250              | [907a7245b4](https://linux-hardware.org/?probe=907a7245b4) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Acer          | Aspire V3-571G              | [ea0093a1f6](https://linux-hardware.org/?probe=ea0093a1f6) | Nov 15, 2022 |
| Dell          | Inspiron 3480               | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| Dell          | Precision 7510              | [111903e578](https://linux-hardware.org/?probe=111903e578) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Lenovo        | ThinkPad T430 2349P25       | [ba76ce6af6](https://linux-hardware.org/?probe=ba76ce6af6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Google        | Celes                       | [4b15e527d5](https://linux-hardware.org/?probe=4b15e527d5) | Nov 12, 2022 |
| Google        | Celes                       | [68323b0e01](https://linux-hardware.org/?probe=68323b0e01) | Nov 12, 2022 |
| Lenovo        | V14-IIL 82C4                | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d020fa04fe](https://linux-hardware.org/?probe=d020fa04fe) | Nov 11, 2022 |
| Dell          | Latitude 12 Rugged Extre... | [d5b955a7b3](https://linux-hardware.org/?probe=d5b955a7b3) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [a13f6196b6](https://linux-hardware.org/?probe=a13f6196b6) | Nov 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [ffa33ab238](https://linux-hardware.org/?probe=ffa33ab238) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [eaed1093a4](https://linux-hardware.org/?probe=eaed1093a4) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| HP            | Laptop 17-ca2xxx            | [a31e9f30cc](https://linux-hardware.org/?probe=a31e9f30cc) | Nov 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [a72c604f03](https://linux-hardware.org/?probe=a72c604f03) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [8ba7f1aa17](https://linux-hardware.org/?probe=8ba7f1aa17) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Acer          | Aspire 5750                 | [83a24172bd](https://linux-hardware.org/?probe=83a24172bd) | Nov 06, 2022 |
| HP            | 250 G7 Notebook PC          | [d29197ed66](https://linux-hardware.org/?probe=d29197ed66) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| Sony          | VGN-FW21E                   | [8be58df3e0](https://linux-hardware.org/?probe=8be58df3e0) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | 250 G7 Notebook PC          | [e5684c9b19](https://linux-hardware.org/?probe=e5684c9b19) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| HP            | Pavilion 17                 | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| Dell          | Latitude 3420               | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Dell          | Latitude E6320              | [b66269072e](https://linux-hardware.org/?probe=b66269072e) | Nov 02, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| Notebook      | P65_P67SE                   | [9b99df1e15](https://linux-hardware.org/?probe=9b99df1e15) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| HP            | Laptop 15-da2xxx            | [ea7591794a](https://linux-hardware.org/?probe=ea7591794a) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| Acer          | Aspire 5732Z                | [df73e0ca67](https://linux-hardware.org/?probe=df73e0ca67) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cfa027a9e2](https://linux-hardware.org/?probe=cfa027a9e2) | Oct 28, 2022 |
| Dell          | Latitude 5521               | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | Laptop 15-da2xxx            | [071938b19a](https://linux-hardware.org/?probe=071938b19a) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Dell          | Inspiron 5515               | [74ad4c8c59](https://linux-hardware.org/?probe=74ad4c8c59) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| Acer          | Aspire E5-571               | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| ASUSTek       | N751JK                      | [f6f0ff5048](https://linux-hardware.org/?probe=f6f0ff5048) | Oct 25, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [94fa6196b8](https://linux-hardware.org/?probe=94fa6196b8) | Oct 25, 2022 |
| Acer          | Aspire 5750                 | [20df7ad008](https://linux-hardware.org/?probe=20df7ad008) | Oct 25, 2022 |
| Dell          | Vostro 15 5501              | [3338297022](https://linux-hardware.org/?probe=3338297022) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| HP            | 470 G8 Notebook PC          | [1cae6fb5ac](https://linux-hardware.org/?probe=1cae6fb5ac) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | [4c3e8196af](https://linux-hardware.org/?probe=4c3e8196af) | Oct 24, 2022 |
| Acer          | Nitro AN517-51              | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| HP            | Laptop 15-da2xxx            | [a9de489f26](https://linux-hardware.org/?probe=a9de489f26) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Haier         | A1420EM                     | [62ce3535b2](https://linux-hardware.org/?probe=62ce3535b2) | Oct 19, 2022 |
| Haier         | A1420EM                     | [a50bc27e31](https://linux-hardware.org/?probe=a50bc27e31) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| HP            | ProBook 450 G5              | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| ASUSTek       | X455LD                      | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Latitude E6420              | [f39e0305c5](https://linux-hardware.org/?probe=f39e0305c5) | Oct 13, 2022 |
| Dell          | Precision M6700             | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [2813d441b5](https://linux-hardware.org/?probe=2813d441b5) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [4039ed6d6f](https://linux-hardware.org/?probe=4039ed6d6f) | Oct 13, 2022 |
| GPU Compan... | GWTC116-2                   | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [7a11da121e](https://linux-hardware.org/?probe=7a11da121e) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| HP            | Compaq 15                   | [bba22531ad](https://linux-hardware.org/?probe=bba22531ad) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| HP            | Compaq 15                   | [0f48335990](https://linux-hardware.org/?probe=0f48335990) | Oct 05, 2022 |
| Intel         | W7645                       | [4f76b8b5ad](https://linux-hardware.org/?probe=4f76b8b5ad) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [76709f5d09](https://linux-hardware.org/?probe=76709f5d09) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| Apple         | MacBookPro9,1               | [08db9e8d75](https://linux-hardware.org/?probe=08db9e8d75) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| ASUSTek       | N56VZ                       | [2b78a7c7f1](https://linux-hardware.org/?probe=2b78a7c7f1) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [4b198e87aa](https://linux-hardware.org/?probe=4b198e87aa) | Sep 28, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ec59847e5b](https://linux-hardware.org/?probe=ec59847e5b) | Sep 27, 2022 |
| HP            | ZBook 15 G6                 | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| ASUSTek       | K93SV                       | [541a21ceb8](https://linux-hardware.org/?probe=541a21ceb8) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| Dell          | Latitude E5400              | [09be905a45](https://linux-hardware.org/?probe=09be905a45) | Sep 24, 2022 |
| HUAWEI        | BOHB-WAX9                   | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| HP            | Pavilion 14                 | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| Lenovo        | G50-45 80E3                 | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| HP            | 255 G8 Notebook PC          | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| Dell          | Inspiron 7559               | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Google        | Blooglet                    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Acer          | Aspire S3-391               | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Dell          | Latitude 7430               | [4fdf1a303c](https://linux-hardware.org/?probe=4fdf1a303c) | Sep 15, 2022 |
| Google        | Treeya                      | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | [b899f1b7da](https://linux-hardware.org/?probe=b899f1b7da) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | [99be4451df](https://linux-hardware.org/?probe=99be4451df) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| Dell          | G15 5511                    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| Dell          | Latitude 7430               | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Acer          | Predator G3-571             | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [0efc3cb183](https://linux-hardware.org/?probe=0efc3cb183) | Sep 07, 2022 |
| Dell          | Precision M4800             | [280ca4dce2](https://linux-hardware.org/?probe=280ca4dce2) | Sep 07, 2022 |
| Dell          | Precision M4800             | [9d494c5486](https://linux-hardware.org/?probe=9d494c5486) | Sep 07, 2022 |
| HP            | 255 G8 Notebook PC          | [5c53e30fe6](https://linux-hardware.org/?probe=5c53e30fe6) | Sep 06, 2022 |
| Samsung       | 270E5G/270E5U               | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [d496e01f0e](https://linux-hardware.org/?probe=d496e01f0e) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| HP            | Notebook                    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| ASUSTek       | UX51VZA                     | [e93c1732ec](https://linux-hardware.org/?probe=e93c1732ec) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| Dell          | Latitude 9420               | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Dell          | Latitude E6400              | [8517e82248](https://linux-hardware.org/?probe=8517e82248) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| HP            | ProBook 4540s               | [f082a7566a](https://linux-hardware.org/?probe=f082a7566a) | Aug 24, 2022 |
| HP            | ProBook 4540s               | [de08e9b296](https://linux-hardware.org/?probe=de08e9b296) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Acer          | Nitro AN515-57              | [bdc4179004](https://linux-hardware.org/?probe=bdc4179004) | Aug 21, 2022 |
| HP            | ProBook 6570b               | [eba0cd02ec](https://linux-hardware.org/?probe=eba0cd02ec) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| Dell          | G3 3779                     | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| MSI           | GF75 Thin 10SCXR            | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Apple         | MacBookPro11,1              | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| HP            | ProBook 6570b               | [b490a791c0](https://linux-hardware.org/?probe=b490a791c0) | Aug 15, 2022 |
| Dell          | Precision 3571              | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [30820abfa2](https://linux-hardware.org/?probe=30820abfa2) | Aug 14, 2022 |
| HP            | ZBook 15 G4                 | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| Dell          | Latitude 5590               | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Timi          | TM1709                      | [26b592f734](https://linux-hardware.org/?probe=26b592f734) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | ProBook 6570b               | [0acbdaf806](https://linux-hardware.org/?probe=0acbdaf806) | Aug 10, 2022 |
| Shanghai Z... | ZXE CRB                     | [9ac3c0b157](https://linux-hardware.org/?probe=9ac3c0b157) | Aug 09, 2022 |
| HP            | EliteBook 8470p             | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Lenovo        | V15-ADA 82C7                | [5b7d298ca6](https://linux-hardware.org/?probe=5b7d298ca6) | Aug 08, 2022 |
| Dell          | Latitude 5420               | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| HP            | ProBook 455 G7              | [b2e805c687](https://linux-hardware.org/?probe=b2e805c687) | Aug 07, 2022 |
| Dell          | XPS 15 9520                 | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| Dell          | Precision 7530              | [40854a027f](https://linux-hardware.org/?probe=40854a027f) | Aug 05, 2022 |
| HP            | EliteBook 8470p             | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Dell          | Latitude 5590               | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| VIT           | P2402                       | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | [3a73f1ffdd](https://linux-hardware.org/?probe=3a73f1ffdd) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Apple         | MacBookPro11,1              | [9814fa3bca](https://linux-hardware.org/?probe=9814fa3bca) | Aug 03, 2022 |
| ASUSTek       | X540SA                      | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| VIT           | P2402                       | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| Intel         | Unknown                     | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [b99b5ef83f](https://linux-hardware.org/?probe=b99b5ef83f) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [3898ce2b5f](https://linux-hardware.org/?probe=3898ce2b5f) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| HP            | EliteBook 840 G6            | [1a2713a2b0](https://linux-hardware.org/?probe=1a2713a2b0) | Jul 31, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [5dcf2bfdbd](https://linux-hardware.org/?probe=5dcf2bfdbd) | Jul 30, 2022 |
| Dell          | Latitude 5590               | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Dell          | Inspiron 15-3567            | [3e40b1abe6](https://linux-hardware.org/?probe=3e40b1abe6) | Jul 27, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Unknown       | Unknown                     | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| Lenovo        | G50-45 80E3                 | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| Lenovo        | ThinkPad E570 20H5006TFR    | [1a1220dc79](https://linux-hardware.org/?probe=1a1220dc79) | Jul 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| HP            | Laptop 17-cn0xxx            | [02a5205d57](https://linux-hardware.org/?probe=02a5205d57) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| Dell          | Latitude E5520              | [e04cdad7b7](https://linux-hardware.org/?probe=e04cdad7b7) | Jul 11, 2022 |
| HP            | EliteBook 840 G5            | [392310b916](https://linux-hardware.org/?probe=392310b916) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| Lenovo        | IdeaPad Y430 2781           | [b8960364cb](https://linux-hardware.org/?probe=b8960364cb) | Jul 10, 2022 |
| Toshiba       | TECRA S11                   | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | [435e7998bd](https://linux-hardware.org/?probe=435e7998bd) | Jul 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| HP            | G42                         | [4a57fd54c6](https://linux-hardware.org/?probe=4a57fd54c6) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| Chuwi         | CoreBook X                  | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| Lenovo        | G50-45 80E3                 | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| HP            | 620                         | [cc970fdd77](https://linux-hardware.org/?probe=cc970fdd77) | Jul 02, 2022 |
| Lenovo        | ThinkPad T420 4180M8P       | [8a94c5bc15](https://linux-hardware.org/?probe=8a94c5bc15) | Jul 02, 2022 |
| Dell          | Latitude 7530               | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HP            | EliteBook 840 G1            | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| Jumper        | EZpad                       | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| HP            | EliteBook 840 G6            | [faaa7b9c81](https://linux-hardware.org/?probe=faaa7b9c81) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Haier         | A1420EM                     | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| GPU Compan... | GWTC116-2                   | [183f3e59fb](https://linux-hardware.org/?probe=183f3e59fb) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| Acer          | Nitro AN515-57              | [10d0c2a6ea](https://linux-hardware.org/?probe=10d0c2a6ea) | Jun 24, 2022 |
| Dell          | Latitude XT3                | [87377f03e2](https://linux-hardware.org/?probe=87377f03e2) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| HP            | EliteBook 820 G1            | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| Dell          | Latitude 5590               | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Clevo         | Modified by dsanke          | [b88e7a22fe](https://linux-hardware.org/?probe=b88e7a22fe) | Jun 22, 2022 |
| Lenovo        | V130-15IGM 81HL             | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Dell          | Precision 5540              | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| ASUSTek       | GR8                         | [90afe7bdd7](https://linux-hardware.org/?probe=90afe7bdd7) | Jun 20, 2022 |
| Apple         | MacBookPro15,2              | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| Toshiba       | Satellite L655              | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| Packard Be... | H17HV                       | [daa945363e](https://linux-hardware.org/?probe=daa945363e) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| Apple         | MacBookPro5,3               | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bf18000c3c](https://linux-hardware.org/?probe=bf18000c3c) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| Acer          | Aspire E1-570G              | [060b0319ff](https://linux-hardware.org/?probe=060b0319ff) | Jun 15, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| HP            | 620                         | [fe1a420f17](https://linux-hardware.org/?probe=fe1a420f17) | Jun 13, 2022 |
| HP            | EliteBook 2570p             | [8b6f8e8952](https://linux-hardware.org/?probe=8b6f8e8952) | Jun 13, 2022 |
| Jumper        | EZpad                       | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 1428               | [e47c98983f](https://linux-hardware.org/?probe=e47c98983f) | Jun 13, 2022 |
| HP            | EliteBook 8460p             | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| Dell          | Inspiron 3521               | [13a04a66d8](https://linux-hardware.org/?probe=13a04a66d8) | Jun 12, 2022 |
| Dell          | Inspiron 15-3567            | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| HP            | Pavilion dv7                | [7f7678265b](https://linux-hardware.org/?probe=7f7678265b) | Jun 11, 2022 |
| HP            | Pavilion dv7                | [c8d1e1be32](https://linux-hardware.org/?probe=c8d1e1be32) | Jun 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [011acdab42](https://linux-hardware.org/?probe=011acdab42) | Jun 09, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [c751dcffff](https://linux-hardware.org/?probe=c751dcffff) | Jun 09, 2022 |
| HP            | Pavilion dv6                | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| System76      | Kudu Professional           | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [54a2c4fa94](https://linux-hardware.org/?probe=54a2c4fa94) | Jun 08, 2022 |
| HP            | 620                         | [1adcb99573](https://linux-hardware.org/?probe=1adcb99573) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [42aaad44bc](https://linux-hardware.org/?probe=42aaad44bc) | Jun 06, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| Toshiba       | Satellite C75D-A            | [a5aee20b56](https://linux-hardware.org/?probe=a5aee20b56) | Jun 06, 2022 |
| Positivo      | Q464C                       | [e00b91e529](https://linux-hardware.org/?probe=e00b91e529) | Jun 06, 2022 |
| Dell          | Latitude 5590               | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| HP            | ProBook 650 G2              | [a580e923a7](https://linux-hardware.org/?probe=a580e923a7) | Jun 03, 2022 |
| Dell          | Latitude E5470              | [e858488f6f](https://linux-hardware.org/?probe=e858488f6f) | Jun 03, 2022 |
| MSI           | CX61 2PC                    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| HP            | ProBook 650 G2              | [27063b3b3a](https://linux-hardware.org/?probe=27063b3b3a) | Jun 03, 2022 |
| Dell          | Latitude 7420               | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| ASUSTek       | TX201LA                     | [ba677dadab](https://linux-hardware.org/?probe=ba677dadab) | Jun 01, 2022 |
| Toshiba       | Satellite L50-A-1D6         | [0436371728](https://linux-hardware.org/?probe=0436371728) | Jun 01, 2022 |
| Toshiba       | Satellite L50-A-1D6         | [20d1a7e37b](https://linux-hardware.org/?probe=20d1a7e37b) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [2861999420](https://linux-hardware.org/?probe=2861999420) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [103bb197fa](https://linux-hardware.org/?probe=103bb197fa) | Jun 01, 2022 |
| Dell          | G7 7588                     | [3e41b876c2](https://linux-hardware.org/?probe=3e41b876c2) | May 31, 2022 |
| Dell          | Vostro 5481                 | [5fd6fe3593](https://linux-hardware.org/?probe=5fd6fe3593) | May 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| Google        | Coral                       | [c517ad03c1](https://linux-hardware.org/?probe=c517ad03c1) | May 30, 2022 |
| Dell          | Precision 7710              | [f24e29d104](https://linux-hardware.org/?probe=f24e29d104) | May 30, 2022 |
| Dell          | Precision 7710              | [1bae5a0bf0](https://linux-hardware.org/?probe=1bae5a0bf0) | May 30, 2022 |
| ASUSTek       | X540LA                      | [57e0b15d17](https://linux-hardware.org/?probe=57e0b15d17) | May 30, 2022 |
| HP            | Pavilion g4                 | [39cdebfff4](https://linux-hardware.org/?probe=39cdebfff4) | May 29, 2022 |
| Medion        | S6445 MD61489               | [a933286b06](https://linux-hardware.org/?probe=a933286b06) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| HUAWEI        | CREM-WXX9                   | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Acer          | Aspire M5-581TG             | [c6ffc6271c](https://linux-hardware.org/?probe=c6ffc6271c) | May 23, 2022 |
| HP            | 15                          | [a61f6dd1eb](https://linux-hardware.org/?probe=a61f6dd1eb) | May 23, 2022 |
| Acer          | Aspire A515-55              | [52dce4d0c3](https://linux-hardware.org/?probe=52dce4d0c3) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | [06ec4e94a2](https://linux-hardware.org/?probe=06ec4e94a2) | May 22, 2022 |
| Acer          | Aspire E5-573               | [dce8b618f8](https://linux-hardware.org/?probe=dce8b618f8) | May 22, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [8266843e53](https://linux-hardware.org/?probe=8266843e53) | May 19, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Dell          | Inspiron 5593               | [e08308603a](https://linux-hardware.org/?probe=e08308603a) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Acer          | Aspire A515-55              | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Acer          | Predator PH315-53           | [eb5d08e402](https://linux-hardware.org/?probe=eb5d08e402) | May 18, 2022 |
| Lenovo        | G780 20138                  | [ee6e90c751](https://linux-hardware.org/?probe=ee6e90c751) | May 17, 2022 |
| HP            | ProBook 6470b               | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| HP            | Unknown                     | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| HP            | ProBook 6570b               | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Apple         | MacBookPro13,2              | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| HUAWEI        | CREM-WXX9                   | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [2ba7ecdb55](https://linux-hardware.org/?probe=2ba7ecdb55) | May 10, 2022 |
| Dell          | Latitude E6540              | [a5bb9f2b58](https://linux-hardware.org/?probe=a5bb9f2b58) | May 10, 2022 |
| HP            | ProBook 470 G1              | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| Dell          | XPS 13 9370                 | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite C650D             | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| HP            | ProBook 470 G1              | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| HP            | ProBook 6470b               | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [ef836a5eca](https://linux-hardware.org/?probe=ef836a5eca) | May 06, 2022 |
| Acer          | Nitro AN515-45              | [aefe7a52e0](https://linux-hardware.org/?probe=aefe7a52e0) | May 06, 2022 |
| Apple         | MacBookPro11,2              | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | 2000                        | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| HP            | ProBook 6450b               | [0c23a5cbc2](https://linux-hardware.org/?probe=0c23a5cbc2) | May 04, 2022 |
| HP            | Pavilion dv7                | [978f98cef3](https://linux-hardware.org/?probe=978f98cef3) | May 04, 2022 |
| Alienware     | 17                          | [1a4cd056f8](https://linux-hardware.org/?probe=1a4cd056f8) | May 04, 2022 |
| Toshiba       | Satellite C650D             | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e126640b3b](https://linux-hardware.org/?probe=e126640b3b) | May 03, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | [b303038c87](https://linux-hardware.org/?probe=b303038c87) | May 01, 2022 |
| Lenovo        | ThinkPad X201 3680AC2       | [5c4515d51e](https://linux-hardware.org/?probe=5c4515d51e) | May 01, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| Lenovo        | Z50-75 80EC                 | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [9f7923bcd2](https://linux-hardware.org/?probe=9f7923bcd2) | Apr 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [12a0105da3](https://linux-hardware.org/?probe=12a0105da3) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-57              | [3206e0f075](https://linux-hardware.org/?probe=3206e0f075) | Apr 27, 2022 |
| Unknown       | Unknown                     | [e77a313003](https://linux-hardware.org/?probe=e77a313003) | Apr 27, 2022 |
| HP            | 250 G5 Notebook PC          | [e4ecdec958](https://linux-hardware.org/?probe=e4ecdec958) | Apr 27, 2022 |
| Acer          | Aspire A515-55              | [fa33f58948](https://linux-hardware.org/?probe=fa33f58948) | Apr 27, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| HP            | ENVY 17                     | [c33b35becc](https://linux-hardware.org/?probe=c33b35becc) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [e466d79804](https://linux-hardware.org/?probe=e466d79804) | Apr 26, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [89debf3e0e](https://linux-hardware.org/?probe=89debf3e0e) | Apr 25, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| Dell          | Studio 1558                 | [b31435ef0c](https://linux-hardware.org/?probe=b31435ef0c) | Apr 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [9877ddeaf6](https://linux-hardware.org/?probe=9877ddeaf6) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [99e25e855e](https://linux-hardware.org/?probe=99e25e855e) | Apr 23, 2022 |
| Acer          | Swift SF314-43              | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| Acer          | Nitro AN515-57              | [848b9d8f5c](https://linux-hardware.org/?probe=848b9d8f5c) | Apr 22, 2022 |
| Acer          | Nitro AN515-57              | [da630d58cf](https://linux-hardware.org/?probe=da630d58cf) | Apr 22, 2022 |
| TUXEDO        | Aura 15 Gen1                | [8ee6cabf43](https://linux-hardware.org/?probe=8ee6cabf43) | Apr 22, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [28690580aa](https://linux-hardware.org/?probe=28690580aa) | Apr 22, 2022 |
| Dynabook      | PORTEGE X30L-J              | [5894fd3a34](https://linux-hardware.org/?probe=5894fd3a34) | Apr 21, 2022 |
| ASUSTek       | G550JK                      | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Positivo      | W940TU                      | [4d03effd28](https://linux-hardware.org/?probe=4d03effd28) | Apr 20, 2022 |
| Positivo      | W940TU                      | [971493b883](https://linux-hardware.org/?probe=971493b883) | Apr 20, 2022 |
| Dell          | Latitude XT3                | [6db9585e20](https://linux-hardware.org/?probe=6db9585e20) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| Dell          | XPS 15 7590                 | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Dell          | Inspiron 15-3567            | [f8e7d70919](https://linux-hardware.org/?probe=f8e7d70919) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | [4ed718df3e](https://linux-hardware.org/?probe=4ed718df3e) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | [402c31b107](https://linux-hardware.org/?probe=402c31b107) | Apr 18, 2022 |
| ASUSTek       | S551LB                      | [bb1d6d3623](https://linux-hardware.org/?probe=bb1d6d3623) | Apr 17, 2022 |
| Shanghai Z... | ZXE CRB                     | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| Dell          | Latitude XT3                | [c4d7d751b7](https://linux-hardware.org/?probe=c4d7d751b7) | Apr 17, 2022 |
| Dell          | Latitude 7410               | [da82f8bba8](https://linux-hardware.org/?probe=da82f8bba8) | Apr 15, 2022 |
| Lenovo        | G40-45 80E1                 | [840ffde0c4](https://linux-hardware.org/?probe=840ffde0c4) | Apr 15, 2022 |
| Dell          | Latitude XT3                | [ce6c2e43a0](https://linux-hardware.org/?probe=ce6c2e43a0) | Apr 15, 2022 |
| Dell          | Latitude E6540              | [2ee68b5f38](https://linux-hardware.org/?probe=2ee68b5f38) | Apr 14, 2022 |
| Framework     | Laptop                      | [6846ee88e0](https://linux-hardware.org/?probe=6846ee88e0) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [45b8eba74c](https://linux-hardware.org/?probe=45b8eba74c) | Apr 14, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [3e09de906e](https://linux-hardware.org/?probe=3e09de906e) | Apr 14, 2022 |
| Lenovo        | ThinkPad T420 41786UU       | [2211278055](https://linux-hardware.org/?probe=2211278055) | Apr 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [4434290159](https://linux-hardware.org/?probe=4434290159) | Apr 14, 2022 |
| Lenovo        | ThinkPad P51 20HH000AUS     | [b7365a4abd](https://linux-hardware.org/?probe=b7365a4abd) | Apr 14, 2022 |
| Samsung       | R425D/R525D                 | [bd5a2f5943](https://linux-hardware.org/?probe=bd5a2f5943) | Apr 14, 2022 |
| Dell          | XPS 13 9300                 | [a21bd26d1e](https://linux-hardware.org/?probe=a21bd26d1e) | Apr 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | [8888d86504](https://linux-hardware.org/?probe=8888d86504) | Apr 13, 2022 |
| Lenovo        | IdeaPad 710S Plus Touch-... | [f4578ea652](https://linux-hardware.org/?probe=f4578ea652) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [744144c472](https://linux-hardware.org/?probe=744144c472) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [479b8d48fc](https://linux-hardware.org/?probe=479b8d48fc) | Apr 13, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | [74191e7ffb](https://linux-hardware.org/?probe=74191e7ffb) | Apr 13, 2022 |
| Toshiba       | Satellite P70-B             | [6c01bb2cc3](https://linux-hardware.org/?probe=6c01bb2cc3) | Apr 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| Dell          | Latitude 5591               | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| Dell          | Latitude 7400               | [2c32d69a57](https://linux-hardware.org/?probe=2c32d69a57) | Apr 13, 2022 |
| HP            | Pavilion g6                 | [44035cfa83](https://linux-hardware.org/?probe=44035cfa83) | Apr 13, 2022 |
| Dell          | Precision 5520              | [eb5bfc87ed](https://linux-hardware.org/?probe=eb5bfc87ed) | Apr 12, 2022 |
| Lenovo        | ThinkPad T430 2349T2A       | [344710cc3a](https://linux-hardware.org/?probe=344710cc3a) | Apr 12, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 738       | 36.43%  |
| Kubuntu 22.04   | 418       | 20.63%  |
| Kubuntu 21.10   | 151       | 7.45%   |
| Kubuntu 22.10   | 147       | 7.26%   |
| Kubuntu 20.10   | 141       | 6.96%   |
| Kubuntu 21.04   | 126       | 6.22%   |
| Kubuntu 19.10   | 105       | 5.18%   |
| Kubuntu 18.04   | 102       | 5.03%   |
| Kubuntu 11      | 45        | 2.22%   |
| Kubuntu 11.1    | 18        | 0.89%   |
| Kubuntu 19.04   | 9         | 0.44%   |
| Kubuntu 23.04   | 7         | 0.35%   |
| Kubuntu 2.0     | 4         | 0.2%    |
| Kubuntu 16.04   | 4         | 0.2%    |
| Kubuntu 18.10   | 3         | 0.15%   |
| Kubuntu         | 3         | 0.15%   |
| Kubuntu 14.04   | 2         | 0.1%    |
| Kubuntu 20.08.3 | 1         | 0.05%   |
| Kubuntu 17.10   | 1         | 0.05%   |
| Kubuntu 17.04   | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Kubuntu | 1951      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 55        | 2.49%   |
| 5.15.0-52-generic | 51        | 2.31%   |
| 5.15.0-56-generic | 43        | 1.94%   |
| 5.19.0-35-generic | 38        | 1.72%   |
| 5.4.0-52-generic  | 35        | 1.58%   |
| 5.13.0-39-generic | 35        | 1.58%   |
| 5.4.0-48-generic  | 34        | 1.54%   |
| 5.15.0-48-generic | 30        | 1.36%   |
| 5.19.0-26-generic | 28        | 1.27%   |
| 5.15.0-58-generic | 28        | 1.27%   |
| 5.4.0-58-generic  | 27        | 1.22%   |
| 5.13.0-28-generic | 27        | 1.22%   |
| 5.15.0-46-generic | 26        | 1.18%   |
| 5.13.0-30-generic | 26        | 1.18%   |
| 5.19.0-23-generic | 25        | 1.13%   |
| 5.11.0-25-generic | 25        | 1.13%   |
| 5.4.0-40-generic  | 24        | 1.08%   |
| 5.15.0-53-generic | 23        | 1.04%   |
| 5.3.0-40-generic  | 22        | 0.99%   |
| 5.19.0-31-generic | 22        | 0.99%   |
| 5.15.0-60-generic | 21        | 0.95%   |
| 5.15.0-47-generic | 21        | 0.95%   |
| 5.15.0-43-generic | 21        | 0.95%   |
| 5.11.0-37-generic | 21        | 0.95%   |
| 5.15.0-41-generic | 20        | 0.9%    |
| 5.4.0-47-generic  | 19        | 0.86%   |
| 5.4.0-29-generic  | 19        | 0.86%   |
| 5.13.0-22-generic | 19        | 0.86%   |
| 5.4.0-37-generic  | 18        | 0.81%   |
| 5.13.0-27-generic | 18        | 0.81%   |
| 5.4.0-65-generic  | 17        | 0.77%   |
| 5.3.0-42-generic  | 17        | 0.77%   |
| 5.13.0-40-generic | 17        | 0.77%   |
| 5.11.0-38-generic | 17        | 0.77%   |
| 5.8.0-63-generic  | 16        | 0.72%   |
| 5.8.0-48-generic  | 16        | 0.72%   |
| 5.8.0-44-generic  | 16        | 0.72%   |
| 5.15.0-50-generic | 16        | 0.72%   |
| 5.13.0-44-generic | 16        | 0.72%   |
| 5.13.0-35-generic | 16        | 0.72%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 478       | 23.14%  |
| 5.15.0  | 410       | 19.85%  |
| 5.13.0  | 259       | 12.54%  |
| 5.8.0   | 220       | 10.65%  |
| 5.11.0  | 185       | 8.95%   |
| 5.19.0  | 157       | 7.6%    |
| 5.3.0   | 129       | 6.24%   |
| 4.15.0  | 38        | 1.84%   |
| 5.0.0   | 17        | 0.82%   |
| 5.10.0  | 13        | 0.63%   |
| 5.17.0  | 10        | 0.48%   |
| 5.6.0   | 7         | 0.34%   |
| 5.14.0  | 7         | 0.34%   |
| 6.0.0   | 6         | 0.29%   |
| 6.1.0   | 5         | 0.24%   |
| 6.0.9   | 4         | 0.19%   |
| 5.7.0   | 4         | 0.19%   |
| 4.4.0   | 4         | 0.19%   |
| 4.18.0  | 4         | 0.19%   |
| 5.12.0  | 3         | 0.15%   |
| 6.2.2   | 2         | 0.1%    |
| 6.2.0   | 2         | 0.1%    |
| 6.1.8   | 2         | 0.1%    |
| 6.1.12  | 2         | 0.1%    |
| 6.0.7   | 2         | 0.1%    |
| 5.9.10  | 2         | 0.1%    |
| 5.9.0   | 2         | 0.1%    |
| 5.19.5  | 2         | 0.1%    |
| 5.18.10 | 2         | 0.1%    |
| 5.15.5  | 2         | 0.1%    |
| 5.15.34 | 2         | 0.1%    |
| 5.13.1  | 2         | 0.1%    |
| 5.12.8  | 2         | 0.1%    |
| 4.10.0  | 2         | 0.1%    |
| 6.2.8   | 1         | 0.05%   |
| 6.2.5   | 1         | 0.05%   |
| 6.1.9   | 1         | 0.05%   |
| 6.1.7   | 1         | 0.05%   |
| 6.1.6   | 1         | 0.05%   |
| 6.1.5   | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 481       | 23.33%  |
| 5.15    | 420       | 20.37%  |
| 5.13    | 265       | 12.85%  |
| 5.8     | 228       | 11.06%  |
| 5.11    | 189       | 9.17%   |
| 5.19    | 161       | 7.81%   |
| 5.3     | 130       | 6.3%    |
| 4.15    | 38        | 1.84%   |
| 5.10    | 17        | 0.82%   |
| 5.0     | 17        | 0.82%   |
| 6.1     | 14        | 0.68%   |
| 6.0     | 13        | 0.63%   |
| 5.17    | 13        | 0.63%   |
| 5.14    | 13        | 0.63%   |
| 5.12    | 9         | 0.44%   |
| 5.6     | 8         | 0.39%   |
| 5.9     | 7         | 0.34%   |
| 6.2     | 6         | 0.29%   |
| 5.7     | 6         | 0.29%   |
| 5.18    | 5         | 0.24%   |
| 5.16    | 5         | 0.24%   |
| 4.18    | 5         | 0.24%   |
| 4.4     | 4         | 0.19%   |
| 5.5     | 3         | 0.15%   |
| 4.10    | 2         | 0.1%    |
| 5.1     | 1         | 0.05%   |
| 4.17    | 1         | 0.05%   |
| 4.13    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1948      | 99.85%  |
| i686   | 3         | 0.15%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 1469      | 74.04%  |
| KDE        | 486       | 24.5%   |
| GNOME      | 11        | 0.55%   |
| Cinnamon   | 4         | 0.2%    |
| MATE       | 3         | 0.15%   |
| Budgie     | 3         | 0.15%   |
| KDE4       | 2         | 0.1%    |
| XFCE       | 1         | 0.05%   |
| X-Cinnamon | 1         | 0.05%   |
| LXQt       | 1         | 0.05%   |
| i3         | 1         | 0.05%   |
| GNUstep    | 1         | 0.05%   |
| Unknown    | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1873      | 95.22%  |
| Wayland | 79        | 4.02%   |
| Tty     | 15        | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 1181      | 59.59%  |
| Unknown | 671       | 33.85%  |
| GDM     | 59        | 2.98%   |
| GDM3    | 33        | 1.66%   |
| LightDM | 25        | 1.26%   |
| TDM     | 11        | 0.55%   |
| SLiM    | 1         | 0.05%   |
| LXDM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 827       | 42.02%  |
| de_DE   | 145       | 7.37%   |
| ru_RU   | 104       | 5.28%   |
| pt_BR   | 95        | 4.83%   |
| it_IT   | 87        | 4.42%   |
| fr_FR   | 83        | 4.22%   |
| en_GB   | 80        | 4.07%   |
| en_IN   | 52        | 2.64%   |
| en_CA   | 46        | 2.34%   |
| es_ES   | 44        | 2.24%   |
| Unknown | 43        | 2.18%   |
| pl_PL   | 34        | 1.73%   |
| en_AU   | 29        | 1.47%   |
| C       | 18        | 0.91%   |
| es_MX   | 16        | 0.81%   |
| hu_HU   | 15        | 0.76%   |
| ru_UA   | 14        | 0.71%   |
| cs_CZ   | 13        | 0.66%   |
| tr_TR   | 12        | 0.61%   |
| en_ZA   | 12        | 0.61%   |
| nl_NL   | 10        | 0.51%   |
| en_NZ   | 10        | 0.51%   |
| zh_CN   | 8         | 0.41%   |
| es_AR   | 7         | 0.36%   |
| en_IE   | 7         | 0.36%   |
| de_CH   | 7         | 0.36%   |
| sv_SE   | 6         | 0.3%    |
| pt_PT   | 6         | 0.3%    |
| fr_BE   | 6         | 0.3%    |
| es_CO   | 6         | 0.3%    |
| es_CL   | 6         | 0.3%    |
| ca_ES   | 6         | 0.3%    |
| sk_SK   | 5         | 0.25%   |
| fr_CH   | 5         | 0.25%   |
| es_VE   | 5         | 0.25%   |
| en_SG   | 5         | 0.25%   |
| de_AT   | 5         | 0.25%   |
| ro_RO   | 4         | 0.2%    |
| nl_BE   | 4         | 0.2%    |
| en_PH   | 4         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1217      | 61.4%   |
| BIOS | 765       | 38.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1804      | 92.04%  |
| Btrfs   | 71        | 3.62%   |
| Overlay | 51        | 2.6%    |
| Xfs     | 13        | 0.66%   |
| Zfs     | 10        | 0.51%   |
| Unknown | 6         | 0.31%   |
| Ext2    | 3         | 0.15%   |
| Ext3    | 2         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 1029      | 52.07%  |
| Unknown | 790       | 39.98%  |
| MBR     | 157       | 7.95%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1766      | 90.06%  |
| Yes       | 195       | 9.94%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1212      | 61.71%  |
| Yes       | 752       | 38.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 443       | 22.71%  |
| Dell                   | 365       | 18.71%  |
| Hewlett-Packard        | 343       | 17.58%  |
| ASUSTek Computer       | 191       | 9.79%   |
| Acer                   | 147       | 7.53%   |
| MSI                    | 56        | 2.87%   |
| Samsung Electronics    | 38        | 1.95%   |
| HUAWEI                 | 38        | 1.95%   |
| Apple                  | 26        | 1.33%   |
| Toshiba                | 25        | 1.28%   |
| Notebook               | 22        | 1.13%   |
| Sony                   | 20        | 1.03%   |
| TUXEDO                 | 19        | 0.97%   |
| Google                 | 15        | 0.77%   |
| Unknown                | 14        | 0.72%   |
| Timi                   | 13        | 0.67%   |
| Alienware              | 11        | 0.56%   |
| Positivo               | 10        | 0.51%   |
| Gigabyte Technology    | 10        | 0.51%   |
| System76               | 7         | 0.36%   |
| Chuwi                  | 7         | 0.36%   |
| PC Specialist          | 6         | 0.31%   |
| Medion                 | 6         | 0.31%   |
| Intel                  | 6         | 0.31%   |
| GPU Company            | 6         | 0.31%   |
| Fujitsu                | 6         | 0.31%   |
| Razer                  | 5         | 0.26%   |
| Panasonic              | 5         | 0.26%   |
| Packard Bell           | 5         | 0.26%   |
| LG Electronics         | 5         | 0.26%   |
| Schenker               | 4         | 0.21%   |
| HONOR                  | 4         | 0.21%   |
| Framework              | 4         | 0.21%   |
| Avell High Performance | 4         | 0.21%   |
| Haier                  | 3         | 0.15%   |
| Fujitsu Siemens        | 3         | 0.15%   |
| Digma                  | 3         | 0.15%   |
| Clevo                  | 3         | 0.15%   |
| Standard               | 2         | 0.1%    |
| SLIMBOOK               | 2         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 25        | 1.28%   |
| HP Notebook                     | 10        | 0.51%   |
| HP Pavilion g6                  | 9         | 0.46%   |
| HP Pavilion dv6                 | 9         | 0.46%   |
| Dell XPS 15 9560                | 9         | 0.46%   |
| HUAWEI NBLK-WAX9X               | 8         | 0.41%   |
| HP Pavilion dv7                 | 7         | 0.36%   |
| Dell XPS 15 9570                | 7         | 0.36%   |
| HP Pavilion 15                  | 6         | 0.31%   |
| HP EliteBook 840 G5             | 6         | 0.31%   |
| HP EliteBook 840 G3             | 6         | 0.31%   |
| HP EliteBook 840 G6             | 5         | 0.26%   |
| GPU Company GWTC116-2           | 5         | 0.26%   |
| Dell XPS 15 7590                | 5         | 0.26%   |
| Dell XPS 13 9310                | 5         | 0.26%   |
| Dell Latitude E6540             | 5         | 0.26%   |
| Dell Latitude 5480              | 5         | 0.26%   |
| Dell Inspiron 5570              | 5         | 0.26%   |
| Dell Inspiron 15-3567           | 5         | 0.26%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 4         | 0.21%   |
| Lenovo Legion Y530-15ICH 81FV   | 4         | 0.21%   |
| Lenovo IdeaPad S145-15API 81V7  | 4         | 0.21%   |
| Lenovo IdeaPad 5 15ARE05 81YQ   | 4         | 0.21%   |
| Lenovo IdeaPad 330-15IKB 81DE   | 4         | 0.21%   |
| Lenovo G50-70 20351             | 4         | 0.21%   |
| HUAWEI KLVL-WXX9                | 4         | 0.21%   |
| HUAWEI HVY-WXX9                 | 4         | 0.21%   |
| HUAWEI CREM-WXX9                | 4         | 0.21%   |
| HP ProBook 6470b                | 4         | 0.21%   |
| HP Laptop 15s-eq0xxx            | 4         | 0.21%   |
| HP Laptop 15-da0xxx             | 4         | 0.21%   |
| HP EliteBook 845 G7 Notebook PC | 4         | 0.21%   |
| HP 255 G8 Notebook PC           | 4         | 0.21%   |
| HP 2000                         | 4         | 0.21%   |
| HP 15                           | 4         | 0.21%   |
| Dell XPS 17 9700                | 4         | 0.21%   |
| Dell XPS 15 9500                | 4         | 0.21%   |
| Dell Vostro 5481                | 4         | 0.21%   |
| Dell Latitude E6420             | 4         | 0.21%   |
| Dell Latitude 7480              | 4         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 233       | 11.94%  |
| Dell Latitude       | 125       | 6.41%   |
| Dell Inspiron       | 92        | 4.72%   |
| Lenovo IdeaPad      | 91        | 4.66%   |
| Acer Aspire         | 91        | 4.66%   |
| HP Pavilion         | 80        | 4.1%    |
| Dell XPS            | 62        | 3.18%   |
| HP ProBook          | 58        | 2.97%   |
| HP Laptop           | 52        | 2.67%   |
| HP EliteBook        | 52        | 2.67%   |
| ASUS VivoBook       | 42        | 2.15%   |
| Dell Precision      | 32        | 1.64%   |
| Dell Vostro         | 26        | 1.33%   |
| Unknown             | 25        | 1.28%   |
| Lenovo Legion       | 23        | 1.18%   |
| Acer Nitro          | 23        | 1.18%   |
| Toshiba Satellite   | 21        | 1.08%   |
| Lenovo ThinkBook    | 21        | 1.08%   |
| ASUS ASUS           | 17        | 0.87%   |
| Acer Swift          | 17        | 0.87%   |
| HP ENVY             | 14        | 0.72%   |
| ASUS Zenbook        | 14        | 0.72%   |
| ASUS ROG            | 13        | 0.67%   |
| HP ZBook            | 11        | 0.56%   |
| HP Notebook         | 10        | 0.51%   |
| ASUS TUF            | 10        | 0.51%   |
| Dell G3             | 9         | 0.46%   |
| HUAWEI NBLK-WAX9X   | 8         | 0.41%   |
| HP 255              | 8         | 0.41%   |
| HP 250              | 8         | 0.41%   |
| MSI Prestige        | 7         | 0.36%   |
| Lenovo Yoga         | 7         | 0.36%   |
| HP OMEN             | 6         | 0.31%   |
| HP 15               | 6         | 0.31%   |
| Dell System         | 6         | 0.31%   |
| Acer Predator       | 6         | 0.31%   |
| TUXEDO InfinityBook | 5         | 0.26%   |
| Razer Blade         | 5         | 0.26%   |
| MSI Modern          | 5         | 0.26%   |
| HP Compaq           | 5         | 0.26%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 271       | 13.89%  |
| 2020 | 263       | 13.48%  |
| 2021 | 209       | 10.71%  |
| 2018 | 182       | 9.33%   |
| 2017 | 136       | 6.97%   |
| 2012 | 131       | 6.71%   |
| 2011 | 125       | 6.41%   |
| 2013 | 123       | 6.3%    |
| 2014 | 121       | 6.2%    |
| 2016 | 96        | 4.92%   |
| 2022 | 73        | 3.74%   |
| 2015 | 72        | 3.69%   |
| 2008 | 55        | 2.82%   |
| 2010 | 49        | 2.51%   |
| 2009 | 27        | 1.38%   |
| 2007 | 15        | 0.77%   |
| 2023 | 3         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1951      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1736      | 88.12%  |
| Enabled  | 234       | 11.88%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1930      | 98.92%  |
| Yes  | 21        | 1.08%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 568       | 28.96%  |
| 16.01-24.0  | 456       | 23.25%  |
| 8.01-16.0   | 370       | 18.87%  |
| 3.01-4.0    | 274       | 13.97%  |
| 32.01-64.0  | 181       | 9.23%   |
| 1.01-2.0    | 39        | 1.99%   |
| 64.01-256.0 | 32        | 1.63%   |
| 24.01-32.0  | 27        | 1.38%   |
| 2.01-3.0    | 14        | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 569       | 27.1%   |
| 1.01-2.0   | 501       | 23.86%  |
| 4.01-8.0   | 460       | 21.9%   |
| 3.01-4.0   | 359       | 17.1%   |
| 8.01-16.0  | 147       | 7%      |
| 0.51-1.0   | 43        | 2.05%   |
| 16.01-24.0 | 15        | 0.71%   |
| 24.01-32.0 | 4         | 0.19%   |
| 32.01-64.0 | 2         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1375      | 69.51%  |
| 2      | 516       | 26.09%  |
| 3      | 61        | 3.08%   |
| 4      | 16        | 0.81%   |
| 0      | 8         | 0.4%    |
| 6      | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1434      | 73.2%   |
| Yes       | 525       | 26.8%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1532      | 78.36%  |
| No        | 423       | 21.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1933      | 99.08%  |
| No        | 18        | 0.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1641      | 83.51%  |
| No        | 324       | 16.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 318       | 16.27%  |
| Germany      | 202       | 10.34%  |
| Russia       | 141       | 7.22%   |
| Brazil       | 122       | 6.24%   |
| France       | 116       | 5.94%   |
| Italy        | 113       | 5.78%   |
| UK           | 74        | 3.79%   |
| Spain        | 65        | 3.33%   |
| India        | 52        | 2.66%   |
| Poland       | 49        | 2.51%   |
| Canada       | 49        | 2.51%   |
| Netherlands  | 41        | 2.1%    |
| Ukraine      | 36        | 1.84%   |
| Mexico       | 33        | 1.69%   |
| Australia    | 28        | 1.43%   |
| Hungary      | 24        | 1.23%   |
| Belgium      | 24        | 1.23%   |
| Switzerland  | 23        | 1.18%   |
| Indonesia    | 23        | 1.18%   |
| Czechia      | 22        | 1.13%   |
| Turkey       | 19        | 0.97%   |
| Romania      | 15        | 0.77%   |
| Bulgaria     | 15        | 0.77%   |
| South Africa | 14        | 0.72%   |
| Slovenia     | 13        | 0.67%   |
| China        | 13        | 0.67%   |
| Sweden       | 12        | 0.61%   |
| Slovakia     | 12        | 0.61%   |
| Denmark      | 12        | 0.61%   |
| Belarus      | 12        | 0.61%   |
| Austria      | 12        | 0.61%   |
| Portugal     | 11        | 0.56%   |
| Ireland      | 11        | 0.56%   |
| Greece       | 11        | 0.56%   |
| Argentina    | 11        | 0.56%   |
| New Zealand  | 9         | 0.46%   |
| Iran         | 9         | 0.46%   |
| Finland      | 9         | 0.46%   |
| Croatia      | 9         | 0.46%   |
| Colombia     | 9         | 0.46%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 43        | 2.1%    |
| Berlin            | 23        | 1.12%   |
| Milan             | 20        | 0.98%   |
| St Petersburg     | 18        | 0.88%   |
| Paris             | 16        | 0.78%   |
| Madrid            | 16        | 0.78%   |
| Warsaw            | 13        | 0.64%   |
| Sao Paulo         | 12        | 0.59%   |
| Rome              | 12        | 0.59%   |
| Hamburg           | 12        | 0.59%   |
| Cologne           | 12        | 0.59%   |
| Budapest          | 12        | 0.59%   |
| Zurich            | 11        | 0.54%   |
| Sofia             | 11        | 0.54%   |
| Minsk             | 11        | 0.54%   |
| Jakarta           | 10        | 0.49%   |
| Kyiv              | 9         | 0.44%   |
| Frankfurt am Main | 9         | 0.44%   |
| Amsterdam         | 9         | 0.44%   |
| Vienna            | 8         | 0.39%   |
| Rio de Janeiro    | 8         | 0.39%   |
| Prague            | 8         | 0.39%   |
| Bengaluru         | 8         | 0.39%   |
| Sydney            | 7         | 0.34%   |
| Phoenix           | 7         | 0.34%   |
| Los Angeles       | 7         | 0.34%   |
| Dublin            | 7         | 0.34%   |
| Birmingham        | 7         | 0.34%   |
| Wroclaw           | 6         | 0.29%   |
| Singapore         | 6         | 0.29%   |
| Seattle           | 6         | 0.29%   |
| Munich            | 6         | 0.29%   |
| Montreal          | 6         | 0.29%   |
| Melbourne         | 6         | 0.29%   |
| Marseille         | 6         | 0.29%   |
| Dallas            | 6         | 0.29%   |
| Chennai           | 6         | 0.29%   |
| Cape Town         | 6         | 0.29%   |
| Bucharest         | 6         | 0.29%   |
| Bratislava        | 6         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 485       | 639    | 19.28%  |
| WDC                            | 284       | 344    | 11.29%  |
| Seagate                        | 228       | 278    | 9.06%   |
| Toshiba                        | 176       | 217    | 7%      |
| Kingston                       | 152       | 172    | 6.04%   |
| SanDisk                        | 147       | 181    | 5.84%   |
| Unknown                        | 120       | 148    | 4.77%   |
| SK hynix                       | 113       | 137    | 4.49%   |
| Intel                          | 105       | 134    | 4.17%   |
| Crucial                        | 96        | 114    | 3.82%   |
| HGST                           | 67        | 76     | 2.66%   |
| Micron Technology              | 63        | 68     | 2.5%    |
| Hitachi                        | 41        | 44     | 1.63%   |
| KIOXIA                         | 39        | 43     | 1.55%   |
| A-DATA Technology              | 39        | 40     | 1.55%   |
| Apple                          | 21        | 25     | 0.83%   |
| LITEON                         | 19        | 20     | 0.76%   |
| China                          | 18        | 24     | 0.72%   |
| SPCC                           | 15        | 16     | 0.6%    |
| Silicon Motion                 | 13        | 16     | 0.52%   |
| PNY                            | 12        | 12     | 0.48%   |
| Phison                         | 12        | 12     | 0.48%   |
| Unknown                        | 12        | 13     | 0.48%   |
| Transcend                      | 10        | 10     | 0.4%    |
| LITEONIT                       | 9         | 11     | 0.36%   |
| Intenso                        | 9         | 10     | 0.36%   |
| SSSTC                          | 7         | 7      | 0.28%   |
| Micron/Crucial Technology      | 7         | 10     | 0.28%   |
| JMicron Technology             | 7         | 8      | 0.28%   |
| Apacer                         | 7         | 7      | 0.28%   |
| Phison Electronics             | 6         | 6      | 0.24%   |
| KingSpec                       | 6         | 6      | 0.24%   |
| GOODRAM                        | 6         | 6      | 0.24%   |
| Corsair                        | 6         | 6      | 0.24%   |
| Union Memory                   | 5         | 5      | 0.2%    |
| UMIS                           | 5         | 5      | 0.2%    |
| Solid State Storage Technology | 5         | 9      | 0.2%    |
| SABRENT                        | 5         | 8      | 0.2%    |
| Patriot                        | 5         | 5      | 0.2%    |
| Netac                          | 5         | 5      | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 35        | 1.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 25        | 0.95%   |
| Samsung SSD 860 EVO 500GB           | 25        | 0.95%   |
| HGST HTS721010A9E630 1TB            | 24        | 0.91%   |
| Toshiba MQ04ABF100 1TB              | 23        | 0.88%   |
| Toshiba MQ01ABD100 1TB              | 23        | 0.88%   |
| Unknown MMC Card  32GB              | 21        | 0.8%    |
| Samsung NVMe SSD Drive 512GB        | 21        | 0.8%    |
| Kingston SA400S37240G 240GB SSD     | 19        | 0.72%   |
| Unknown MMC Card  64GB              | 18        | 0.69%   |
| Seagate ST500LT012-1DG142 500GB     | 15        | 0.57%   |
| Samsung SSD 850 EVO 500GB           | 15        | 0.57%   |
| Samsung SSD 850 EVO 250GB           | 14        | 0.53%   |
| Samsung NVMe SSD Drive 1TB          | 14        | 0.53%   |
| Kingston SA400S37480G 480GB SSD     | 14        | 0.53%   |
| SanDisk NVMe SSD Drive 512GB        | 13        | 0.5%    |
| SanDisk NVMe SSD Drive 256GB        | 13        | 0.5%    |
| Samsung SSD 970 EVO Plus 500GB      | 13        | 0.5%    |
| Samsung SSD 860 EVO M.2 500GB       | 13        | 0.5%    |
| WDC WD10SPZX-21Z10T0 1TB            | 12        | 0.46%   |
| SK hynix NVMe SSD Drive 512GB       | 12        | 0.46%   |
| Seagate ST2000LM007-1R8174 2TB      | 12        | 0.46%   |
| Intel SSDPEKNW512G8 512GB           | 12        | 0.46%   |
| Unknown                             | 12        | 0.46%   |
| Unknown MMC Card  128GB             | 11        | 0.42%   |
| Toshiba MQ01ABF050 500GB            | 11        | 0.42%   |
| SanDisk SSD PLUS 240GB              | 11        | 0.42%   |
| Samsung SSD 860 EVO 1TB             | 11        | 0.42%   |
| KIOXIA KBG40ZNS512G NVMe 512GB      | 11        | 0.42%   |
| Crucial CT500MX500SSD1 500GB        | 11        | 0.42%   |
| Crucial CT1000MX500SSD1 1TB         | 11        | 0.42%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 10        | 0.38%   |
| Kingston SV300S37A120G 120GB SSD    | 10        | 0.38%   |
| HGST HTS541010A9E680 1TB            | 10        | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 9         | 0.34%   |
| WDC WD10SPZX-24Z10 1TB              | 9         | 0.34%   |
| Seagate ST1000LM048-2E7172 1TB      | 9         | 0.34%   |
| Samsung SSD 970 EVO Plus 1TB        | 9         | 0.34%   |
| WDC WD10SPZX-60Z10T0 1TB            | 8         | 0.3%    |
| Seagate ST1000LX015-1U7172 1TB      | 8         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 225       | 274    | 36.06%  |
| WDC                 | 154       | 181    | 24.68%  |
| Toshiba             | 100       | 123    | 16.03%  |
| HGST                | 66        | 75     | 10.58%  |
| Hitachi             | 41        | 44     | 6.57%   |
| Samsung Electronics | 12        | 15     | 1.92%   |
| Unknown             | 5         | 7      | 0.8%    |
| SABRENT             | 5         | 8      | 0.8%    |
| Fujitsu             | 5         | 7      | 0.8%    |
| Apple               | 4         | 4      | 0.64%   |
| ASMT                | 2         | 3      | 0.32%   |
| USB3.0              | 1         | 1      | 0.16%   |
| KESU                | 1         | 1      | 0.16%   |
| JMicron Technology  | 1         | 1      | 0.16%   |
| ipTIME              | 1         | 1      | 0.16%   |
| HGST HTS            | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 229       | 304    | 27.56%  |
| Kingston            | 100       | 113    | 12.03%  |
| SanDisk             | 91        | 110    | 10.95%  |
| Crucial             | 81        | 99     | 9.75%   |
| WDC                 | 40        | 57     | 4.81%   |
| A-DATA Technology   | 22        | 22     | 2.65%   |
| Intel               | 21        | 24     | 2.53%   |
| Toshiba             | 20        | 30     | 2.41%   |
| SK hynix            | 17        | 17     | 2.05%   |
| China               | 17        | 23     | 2.05%   |
| Micron Technology   | 16        | 17     | 1.93%   |
| LITEON              | 14        | 14     | 1.68%   |
| SPCC                | 12        | 13     | 1.44%   |
| PNY                 | 10        | 10     | 1.2%    |
| Transcend           | 9         | 9      | 1.08%   |
| LITEONIT            | 9         | 11     | 1.08%   |
| Apple               | 9         | 9      | 1.08%   |
| Intenso             | 7         | 8      | 0.84%   |
| Apacer              | 7         | 7      | 0.84%   |
| KingSpec            | 6         | 6      | 0.72%   |
| GOODRAM             | 6         | 6      | 0.72%   |
| Patriot             | 5         | 5      | 0.6%    |
| Dogfish             | 5         | 5      | 0.6%    |
| Netac               | 4         | 4      | 0.48%   |
| JMicron Technology  | 4         | 4      | 0.48%   |
| Emtec               | 4         | 4      | 0.48%   |
| Corsair             | 4         | 4      | 0.48%   |
| Zheino              | 3         | 5      | 0.36%   |
| TO Exter            | 3         | 3      | 0.36%   |
| Team                | 3         | 3      | 0.36%   |
| Verbatim            | 2         | 3      | 0.24%   |
| Smart               | 2         | 2      | 0.24%   |
| RZX                 | 2         | 3      | 0.24%   |
| Plextor             | 2         | 2      | 0.24%   |
| Mushkin             | 2         | 2      | 0.24%   |
| Lexar               | 2         | 2      | 0.24%   |
| FORESEE             | 2         | 2      | 0.24%   |
| Drevo               | 2         | 2      | 0.24%   |
| BHT                 | 2         | 3      | 0.24%   |
| Unknown             | 2         | 2      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 877       | 1110   | 36.68%  |
| SSD     | 757       | 1008   | 31.66%  |
| HDD     | 607       | 746    | 25.39%  |
| MMC     | 123       | 149    | 5.14%   |
| Unknown | 27        | 31     | 1.13%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1178      | 1687   | 52.24%  |
| NVMe | 876       | 1106   | 38.85%  |
| MMC  | 123       | 149    | 5.45%   |
| SAS  | 78        | 102    | 3.46%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 820       | 1080   | 60.74%  |
| 0.51-1.0   | 451       | 574    | 33.41%  |
| 1.01-2.0   | 71        | 88     | 5.26%   |
| 3.01-4.0   | 4         | 8      | 0.3%    |
| 4.01-10.0  | 4         | 4      | 0.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 581       | 28.92%  |
| 101-250        | 578       | 28.77%  |
| 501-1000       | 373       | 18.57%  |
| 1001-2000      | 160       | 7.96%   |
| 51-100         | 119       | 5.92%   |
| 21-50          | 56        | 2.79%   |
| 1-20           | 56        | 2.79%   |
| More than 3000 | 39        | 1.94%   |
| 2001-3000      | 38        | 1.89%   |
| Unknown        | 9         | 0.45%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 531       | 25.49%  |
| 101-250        | 411       | 19.73%  |
| 21-50          | 365       | 17.52%  |
| 51-100         | 296       | 14.21%  |
| 251-500        | 256       | 12.29%  |
| 501-1000       | 138       | 6.63%   |
| 1001-2000      | 52        | 2.5%    |
| More than 3000 | 16        | 0.77%   |
| 2001-3000      | 9         | 0.43%   |
| Unknown        | 9         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 5         | 11     | 3.52%   |
| HGST HTS721010A9E630 1TB                 | 5         | 6      | 3.52%   |
| Toshiba MQ04ABF100 1TB                   | 3         | 3      | 2.11%   |
| Toshiba MQ01ABD100 1TB                   | 3         | 5      | 2.11%   |
| Seagate ST500LT012-9WS142 500GB          | 3         | 3      | 2.11%   |
| Seagate ST1000LM048-2E7172 1TB           | 3         | 3      | 2.11%   |
| Seagate ST1000LM035-1RK172 1TB           | 3         | 3      | 2.11%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 3      | 2.11%   |
| Hitachi HTS547564A9E384 640GB            | 3         | 3      | 2.11%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 2.11%   |
| SK hynix SC401 SATA 512GB SSD            | 2         | 2      | 1.41%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.41%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.41%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.41%   |
| Seagate ST2000LM007-1R8174 2TB           | 2         | 2      | 1.41%   |
| SanDisk SSD PLUS 240GB                   | 2         | 2      | 1.41%   |
| Hitachi HTS547575A9E384 752GB            | 2         | 2      | 1.41%   |
| Hitachi HTS545050B9A300 500GB            | 2         | 2      | 1.41%   |
| HGST HTS541010A9E680 1TB                 | 2         | 2      | 1.41%   |
| Crucial CT500P1SSD8 500GB                | 2         | 2      | 1.41%   |
| Zheino CHN mSATA02M 256 256GB SSD        | 1         | 2      | 0.7%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD         | 1         | 1      | 0.7%    |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.7%    |
| WDC WD6400BEVT-00A0RT0 640GB             | 1         | 1      | 0.7%    |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.7%    |
| WDC WD5000LPVX-55V0TT0 500GB             | 1         | 1      | 0.7%    |
| WDC WD5000LPVT-24G33T1 500GB             | 1         | 1      | 0.7%    |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1      | 0.7%    |
| WDC WD5000LPLX-00ZNTT0 500GB             | 1         | 1      | 0.7%    |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.7%    |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.7%    |
| WDC PC SN520 SDAPMUW-512G-1001 512GB     | 1         | 1      | 0.7%    |
| VISIPRO SSD 256GB                        | 1         | 1      | 0.7%    |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.7%    |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.7%    |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.7%    |
| Toshiba MQ01ABD075 752GB                 | 1         | 2      | 0.7%    |
| Toshiba MK7575GSX 752GB                  | 1         | 1      | 0.7%    |
| Toshiba MK7559GSXP 752GB                 | 1         | 2      | 0.7%    |
| Toshiba MK6476GSX 640GB                  | 1         | 1      | 0.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 22.54%  |
| Toshiba             | 20        | 24     | 14.08%  |
| Hitachi             | 12        | 12     | 8.45%   |
| HGST                | 12        | 13     | 8.45%   |
| WDC                 | 11        | 11     | 7.75%   |
| Samsung Electronics | 10        | 11     | 7.04%   |
| Crucial             | 9         | 10     | 6.34%   |
| SK hynix            | 8         | 8      | 5.63%   |
| SanDisk             | 6         | 6      | 4.23%   |
| Kingston            | 6         | 6      | 4.23%   |
| A-DATA Technology   | 5         | 5      | 3.52%   |
| Micron Technology   | 3         | 3      | 2.11%   |
| Zheino              | 1         | 2      | 0.7%    |
| VISIPRO             | 1         | 1      | 0.7%    |
| R580                | 1         | 1      | 0.7%    |
| Mushkin             | 1         | 1      | 0.7%    |
| LITEONIT            | 1         | 1      | 0.7%    |
| Drevo               | 1         | 1      | 0.7%    |
| BAITITON            | 1         | 3      | 0.7%    |
| ASENNO              | 1         | 1      | 0.7%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 38.1%   |
| Toshiba             | 17        | 21     | 20.24%  |
| Hitachi             | 12        | 12     | 14.29%  |
| HGST                | 12        | 13     | 14.29%  |
| WDC                 | 9         | 9      | 10.71%  |
| Samsung Electronics | 2         | 2      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 83        | 97     | 59.29%  |
| SSD  | 43        | 49     | 30.71%  |
| NVMe | 14        | 14     | 10%     |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB | 1         | 1      | 33.33%  |
| Intel SSDSC2KB960G8 960GB | 1         | 1      | 33.33%  |
| Acer SSD FA100 256GB      | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 33.33%  |
| Intel   | 1         | 1      | 33.33%  |
| Acer    | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1048      | 1439   | 49.43%  |
| Detected | 930       | 1442   | 43.87%  |
| Malfunc  | 139       | 160    | 6.56%   |
| Failed   | 3         | 3      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1335      | 54.56%  |
| Samsung Electronics              | 264       | 10.79%  |
| AMD                              | 247       | 10.09%  |
| SanDisk                          | 151       | 6.17%   |
| SK hynix                         | 96        | 3.92%   |
| Toshiba America Info Systems     | 63        | 2.57%   |
| Kingston Technology Company      | 54        | 2.21%   |
| Micron Technology                | 47        | 1.92%   |
| KIOXIA                           | 36        | 1.47%   |
| Phison Electronics               | 22        | 0.9%    |
| Micron/Crucial Technology        | 22        | 0.9%    |
| ADATA Technology                 | 21        | 0.86%   |
| Silicon Motion                   | 18        | 0.74%   |
| Solid State Storage Technology   | 13        | 0.53%   |
| Union Memory (Shenzhen)          | 12        | 0.49%   |
| Realtek Semiconductor            | 11        | 0.45%   |
| Lite-On Technology               | 8         | 0.33%   |
| Apple                            | 6         | 0.25%   |
| Nvidia                           | 4         | 0.16%   |
| Lenovo                           | 4         | 0.16%   |
| Marvell Technology Group         | 3         | 0.12%   |
| Zhaoxin                          | 1         | 0.04%   |
| Yangtze Memory Technologies      | 1         | 0.04%   |
| VIA Technologies                 | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Shenzhen Longsys Electronics     | 1         | 0.04%   |
| Netac Technology                 | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| ASMedia Technology               | 1         | 0.04%   |
| Unknown                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 231       | 8.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 161       | 6.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 146       | 5.63%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 139       | 5.36%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 134       | 5.17%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 92        | 3.55%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 89        | 3.43%   |
| Intel Volume Management Device NVMe RAID Controller                            | 81        | 3.12%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 75        | 2.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 73        | 2.81%   |
| Samsung NVMe SSD Controller 980                                                | 59        | 2.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 51        | 1.97%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 50        | 1.93%   |
| Micron NVMe Storage Controller                                                 | 47        | 1.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 46        | 1.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 45        | 1.73%   |
| Intel SSD 660P Series                                                          | 43        | 1.66%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 42        | 1.62%   |
| Intel Comet Lake SATA AHCI Controller                                          | 36        | 1.39%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 34        | 1.31%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 32        | 1.23%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 31        | 1.2%    |
| Intel Tiger Lake-LP SATA Controller                                            | 31        | 1.2%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 29        | 1.12%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 27        | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 27        | 1.04%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 26        | 1%      |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 24        | 0.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 22        | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 21        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 21        | 0.81%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 21        | 0.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 20        | 0.77%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 18        | 0.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 18        | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 18        | 0.69%   |
| SK hynix Non-Volatile memory controller                                        | 16        | 0.62%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 16        | 0.62%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 15        | 0.58%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 15        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1343      | 53.78%  |
| NVMe | 875       | 35.04%  |
| RAID | 219       | 8.77%   |
| IDE  | 60        | 2.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1565      | 80.22%  |
| AMD          | 385       | 19.73%  |
| CentaurHauls | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 46        | 2.36%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 38        | 1.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 38        | 1.95%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 38        | 1.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 36        | 1.85%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 36        | 1.85%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 33        | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 32        | 1.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 32        | 1.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 31        | 1.59%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 29        | 1.49%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 29        | 1.49%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 29        | 1.49%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 28        | 1.44%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 1.33%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 1.28%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 1.28%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 24        | 1.23%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 20        | 1.03%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 19        | 0.97%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 17        | 0.87%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 17        | 0.87%   |
| Intel 12th Gen Core i7-12700H                 | 17        | 0.87%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.82%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 16        | 0.82%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 16        | 0.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 15        | 0.77%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 15        | 0.77%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 14        | 0.72%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 14        | 0.72%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 13        | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 13        | 0.67%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 13        | 0.67%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.67%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 13        | 0.67%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 12        | 0.62%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 12        | 0.62%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.62%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 0.62%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 12        | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 549       | 28.14%  |
| Intel Core i5           | 487       | 24.96%  |
| Other                   | 186       | 9.53%   |
| AMD Ryzen 7             | 115       | 5.89%   |
| Intel Core i3           | 108       | 5.54%   |
| AMD Ryzen 5             | 106       | 5.43%   |
| Intel Celeron           | 85        | 4.36%   |
| Intel Core 2 Duo        | 47        | 2.41%   |
| Intel Pentium           | 28        | 1.44%   |
| AMD A6                  | 23        | 1.18%   |
| AMD Ryzen 3             | 20        | 1.03%   |
| AMD Ryzen 7 PRO         | 17        | 0.87%   |
| AMD Ryzen 9             | 15        | 0.77%   |
| Intel Pentium Dual-Core | 14        | 0.72%   |
| Intel Core i9           | 14        | 0.72%   |
| AMD A10                 | 14        | 0.72%   |
| Intel Atom              | 13        | 0.67%   |
| Intel Pentium Silver    | 11        | 0.56%   |
| AMD A8                  | 10        | 0.51%   |
| AMD Ryzen 5 PRO         | 9         | 0.46%   |
| Intel Genuine           | 7         | 0.36%   |
| AMD E1                  | 7         | 0.36%   |
| AMD E                   | 7         | 0.36%   |
| AMD E2                  | 6         | 0.31%   |
| AMD A4                  | 6         | 0.31%   |
| Intel Pentium Dual      | 5         | 0.26%   |
| Intel Core m3           | 5         | 0.26%   |
| Intel Celeron Dual-Core | 5         | 0.26%   |
| AMD FX                  | 5         | 0.26%   |
| Intel Core 2            | 3         | 0.15%   |
| AMD Athlon              | 3         | 0.15%   |
| AMD A12                 | 3         | 0.15%   |
| Intel Xeon              | 2         | 0.1%    |
| AMD C-50                | 2         | 0.1%    |
| AMD Athlon II           | 2         | 0.1%    |
| Intel Pentium Gold      | 1         | 0.05%   |
| Intel Core M            | 1         | 0.05%   |
| Intel Core 2 Quad       | 1         | 0.05%   |
| AMD Z                   | 1         | 0.05%   |
| AMD Turion II           | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 796       | 40.78%  |
| 4      | 741       | 37.96%  |
| 6      | 207       | 10.6%   |
| 8      | 153       | 7.84%   |
| 14     | 23        | 1.18%   |
| 1      | 13        | 0.67%   |
| 12     | 9         | 0.46%   |
| 10     | 8         | 0.41%   |
| 16     | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1951      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1611      | 82.45%  |
| 1      | 343       | 17.55%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1951      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 476       | 23.79%  |
| 0x306a9    | 108       | 5.4%    |
| 0x206a7    | 94        | 4.7%    |
| 0x906ea    | 88        | 4.4%    |
| 0x806ec    | 87        | 4.35%   |
| 0x806c1    | 79        | 3.95%   |
| 0x806ea    | 74        | 3.7%    |
| 0x40651    | 71        | 3.55%   |
| 0x306c3    | 59        | 2.95%   |
| 0x806e9    | 58        | 2.9%    |
| 0x406e3    | 52        | 2.6%    |
| 0x306d4    | 42        | 2.1%    |
| 0x08108109 | 37        | 1.85%   |
| 0x08600106 | 36        | 1.8%    |
| 0x906e9    | 35        | 1.75%   |
| 0x1067a    | 35        | 1.75%   |
| 0xa0652    | 34        | 1.7%    |
| 0x0a50000c | 34        | 1.7%    |
| 0x08108102 | 33        | 1.65%   |
| 0x706e5    | 29        | 1.45%   |
| 0x906a3    | 27        | 1.35%   |
| 0x806eb    | 26        | 1.3%    |
| 0x506e3    | 23        | 1.15%   |
| 0x08608103 | 20        | 1%      |
| 0x706a1    | 19        | 0.95%   |
| 0x20655    | 19        | 0.95%   |
| 0x806d1    | 18        | 0.9%    |
| 0x706a8    | 18        | 0.9%    |
| 0x406c4    | 17        | 0.85%   |
| 0x08600104 | 15        | 0.75%   |
| 0x906ed    | 14        | 0.7%    |
| 0x30678    | 14        | 0.7%    |
| 0x07030105 | 13        | 0.65%   |
| 0x6fd      | 12        | 0.6%    |
| 0x08600103 | 12        | 0.6%    |
| 0x03000027 | 12        | 0.6%    |
| 0x20652    | 11        | 0.55%   |
| 0x06006705 | 10        | 0.5%    |
| 0x506c9    | 8         | 0.4%    |
| 0x10676    | 8         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 482       | 24.69%  |
| Haswell          | 168       | 8.61%   |
| IvyBridge        | 146       | 7.48%   |
| SandyBridge      | 118       | 6.05%   |
| TigerLake        | 114       | 5.84%   |
| Skylake          | 92        | 4.71%   |
| Zen 2            | 84        | 4.3%    |
| Zen+             | 81        | 4.15%   |
| Unknown          | 63        | 3.23%   |
| Zen 3            | 60        | 3.07%   |
| Penryn           | 58        | 2.97%   |
| Icelake          | 54        | 2.77%   |
| CometLake        | 52        | 2.66%   |
| Broadwell        | 51        | 2.61%   |
| Goldmont plus    | 50        | 2.56%   |
| Silvermont       | 43        | 2.2%    |
| Westmere         | 41        | 2.1%    |
| Alderlake Hybrid | 33        | 1.69%   |
| Excavator        | 30        | 1.54%   |
| Core             | 28        | 1.43%   |
| Zen              | 18        | 0.92%   |
| Puma             | 17        | 0.87%   |
| K10 Llano        | 13        | 0.67%   |
| Bobcat           | 12        | 0.61%   |
| Goldmont         | 10        | 0.51%   |
| Piledriver       | 8         | 0.41%   |
| Jaguar           | 8         | 0.41%   |
| Steamroller      | 4         | 0.2%    |
| Nehalem          | 4         | 0.2%    |
| K10              | 4         | 0.2%    |
| Bonnell          | 3         | 0.15%   |
| K8 & K10 hybrid  | 2         | 0.1%    |
| Tremont          | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1467      | 56.47%  |
| Nvidia                           | 631       | 24.29%  |
| AMD                              | 497       | 19.13%  |
| Zhaoxin                          | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| ATI Technologies                 | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 133       | 5%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 117       | 4.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 110       | 4.14%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 105       | 3.95%   |
| Intel UHD Graphics 620                                                                   | 85        | 3.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 84        | 3.16%   |
| AMD Renoir                                                                               | 83        | 3.12%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 80        | 3.01%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 78        | 2.93%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 77        | 2.89%   |
| Intel HD Graphics 620                                                                    | 71        | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 60        | 2.26%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 59        | 2.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 51        | 1.92%   |
| Intel HD Graphics 5500                                                                   | 48        | 1.8%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 46        | 1.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 45        | 1.69%   |
| Intel HD Graphics 630                                                                    | 40        | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 40        | 1.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 36        | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 36        | 1.35%   |
| AMD Lucienne                                                                             | 32        | 1.2%    |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 29        | 1.09%   |
| Intel HD Graphics 530                                                                    | 26        | 0.98%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 25        | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 0.86%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 0.86%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 21        | 0.79%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 21        | 0.79%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 20        | 0.75%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 20        | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 20        | 0.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 19        | 0.71%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 18        | 0.68%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 17        | 0.64%   |
| Intel Iris Plus Graphics G7                                                              | 17        | 0.64%   |
| Nvidia GP108M [GeForce MX150]                                                            | 16        | 0.6%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 15        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 879       | 44.96%  |
| Intel + Nvidia | 498       | 25.47%  |
| 1 x AMD        | 308       | 15.75%  |
| Intel + AMD    | 88        | 4.5%    |
| 1 x Nvidia     | 73        | 3.73%   |
| AMD + Nvidia   | 58        | 2.97%   |
| 2 x AMD        | 44        | 2.25%   |
| Other          | 2         | 0.1%    |
| 2 x Nvidia     | 2         | 0.1%    |
| 2 x Intel      | 1         | 0.05%   |
| 1 x Zhaoxin    | 1         | 0.05%   |
| 1 x SiS        | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1528      | 77.37%  |
| Proprietary | 416       | 21.06%  |
| Unknown     | 31        | 1.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1259      | 63.04%  |
| 1.01-2.0   | 230       | 11.52%  |
| 0.01-0.5   | 205       | 10.27%  |
| 3.01-4.0   | 124       | 6.21%   |
| 0.51-1.0   | 102       | 5.11%   |
| 5.01-6.0   | 37        | 1.85%   |
| 7.01-8.0   | 26        | 1.3%    |
| 2.01-3.0   | 12        | 0.6%    |
| 8.01-16.0  | 2         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 413       | 17.66%  |
| LG Display              | 334       | 14.28%  |
| BOE                     | 331       | 14.15%  |
| Chimei Innolux          | 323       | 13.81%  |
| Samsung Electronics     | 219       | 9.36%   |
| Sharp                   | 96        | 4.1%    |
| Dell                    | 83        | 3.55%   |
| Goldstar                | 63        | 2.69%   |
| Lenovo                  | 45        | 1.92%   |
| PANDA                   | 40        | 1.71%   |
| Chi Mei Optoelectronics | 38        | 1.62%   |
| Hewlett-Packard         | 33        | 1.41%   |
| Acer                    | 30        | 1.28%   |
| Apple                   | 29        | 1.24%   |
| Philips                 | 26        | 1.11%   |
| BenQ                    | 21        | 0.9%    |
| InfoVision              | 20        | 0.86%   |
| Ancor Communications    | 20        | 0.86%   |
| AOC                     | 17        | 0.73%   |
| ASUSTek Computer        | 12        | 0.51%   |
| ViewSonic               | 11        | 0.47%   |
| CSO                     | 11        | 0.47%   |
| Iiyama                  | 9         | 0.38%   |
| Toshiba                 | 6         | 0.26%   |
| Panasonic               | 6         | 0.26%   |
| LG Philips              | 6         | 0.26%   |
| Sceptre Tech            | 5         | 0.21%   |
| CPT                     | 5         | 0.21%   |
| Sony                    | 4         | 0.17%   |
| Seiko/Epson             | 4         | 0.17%   |
| NEC Computers           | 4         | 0.17%   |
| MSI                     | 4         | 0.17%   |
| HannStar                | 4         | 0.17%   |
| Vizio                   | 3         | 0.13%   |
| Vestel Elektronik       | 3         | 0.13%   |
| Unknown                 | 3         | 0.13%   |
| SLD                     | 3         | 0.13%   |
| LGD                     | 3         | 0.13%   |
| HKC                     | 3         | 0.13%   |
| MiTAC                   | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 20        | 0.84%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 19        | 0.8%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 18        | 0.76%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 18        | 0.76%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 14        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 14        | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 14        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 12        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 12        | 0.51%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 11        | 0.46%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 10        | 0.42%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 10        | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 9         | 0.38%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 8         | 0.34%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 8         | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 8         | 0.34%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 8         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 8         | 0.34%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 8         | 0.34%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 8         | 0.34%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch     | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 7         | 0.3%    |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 7         | 0.3%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 6         | 0.25%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                   | 6         | 0.25%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 6         | 0.25%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch              | 6         | 0.25%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 6         | 0.25%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch          | 6         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 6         | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 6         | 0.25%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 6         | 0.25%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 6         | 0.25%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                     | 6         | 0.25%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 6         | 0.25%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                     | 6         | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 6         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1064      | 49.15%  |
| 1366x768 (WXGA)    | 517       | 23.88%  |
| 1600x900 (HD+)     | 109       | 5.03%   |
| 3840x2160 (4K)     | 105       | 4.85%   |
| 2560x1440 (QHD)    | 84        | 3.88%   |
| 1920x1200 (WUXGA)  | 43        | 1.99%   |
| 1280x800 (WXGA)    | 36        | 1.66%   |
| 1440x900 (WXGA+)   | 21        | 0.97%   |
| 2560x1600          | 20        | 0.92%   |
| 2880x1800          | 19        | 0.88%   |
| 3840x2400          | 16        | 0.74%   |
| 2160x1440          | 14        | 0.65%   |
| 1680x1050 (WSXGA+) | 14        | 0.65%   |
| 3440x1440          | 13        | 0.6%    |
| 2560x1080          | 13        | 0.6%    |
| 1280x1024 (SXGA)   | 13        | 0.6%    |
| 1360x768           | 8         | 0.37%   |
| 3200x1800 (QHD+)   | 7         | 0.32%   |
| 3840x1080          | 5         | 0.23%   |
| 2256x1504          | 5         | 0.23%   |
| 2520x1680          | 4         | 0.18%   |
| 2240x1400          | 4         | 0.18%   |
| Unknown            | 4         | 0.18%   |
| 3456x2160          | 3         | 0.14%   |
| 1600x1200          | 3         | 0.14%   |
| 1024x768 (XGA)     | 3         | 0.14%   |
| 3072x1920          | 2         | 0.09%   |
| 1920x540           | 2         | 0.09%   |
| 1920x1280          | 2         | 0.09%   |
| 1024x600           | 2         | 0.09%   |
| 5760x2160          | 1         | 0.05%   |
| 3840x1100          | 1         | 0.05%   |
| 3000x2000          | 1         | 0.05%   |
| 3000x1920          | 1         | 0.05%   |
| 2560x1700          | 1         | 0.05%   |
| 2288x1287          | 1         | 0.05%   |
| 2160x1350          | 1         | 0.05%   |
| 1680x945           | 1         | 0.05%   |
| 1280x720 (HD)      | 1         | 0.05%   |
| 1080x1920          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 953       | 40.61%  |
| 13      | 297       | 12.65%  |
| 14      | 281       | 11.97%  |
| 17      | 202       | 8.61%   |
| 27      | 102       | 4.35%   |
| 24      | 85        | 3.62%   |
| 23      | 76        | 3.24%   |
| 21      | 58        | 2.47%   |
| 12      | 39        | 1.66%   |
| 11      | 39        | 1.66%   |
| 16      | 35        | 1.49%   |
| 34      | 24        | 1.02%   |
| Unknown | 23        | 0.98%   |
| 31      | 19        | 0.81%   |
| 18      | 16        | 0.68%   |
| 20      | 13        | 0.55%   |
| 19      | 10        | 0.43%   |
| 84      | 8         | 0.34%   |
| 32      | 7         | 0.3%    |
| 22      | 7         | 0.3%    |
| 25      | 6         | 0.26%   |
| 72      | 5         | 0.21%   |
| 40      | 5         | 0.21%   |
| 54      | 4         | 0.17%   |
| 47      | 3         | 0.13%   |
| 42      | 3         | 0.13%   |
| 26      | 3         | 0.13%   |
| 10      | 3         | 0.13%   |
| 49      | 2         | 0.09%   |
| 48      | 2         | 0.09%   |
| 46      | 2         | 0.09%   |
| 78      | 1         | 0.04%   |
| 74      | 1         | 0.04%   |
| 65      | 1         | 0.04%   |
| 63      | 1         | 0.04%   |
| 61      | 1         | 0.04%   |
| 60      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 52      | 1         | 0.04%   |
| 39      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1388      | 59.93%  |
| 501-600     | 243       | 10.49%  |
| 351-400     | 237       | 10.23%  |
| 201-300     | 218       | 9.41%   |
| 401-500     | 100       | 4.32%   |
| 701-800     | 31        | 1.34%   |
| 601-700     | 30        | 1.3%    |
| Unknown     | 23        | 0.99%   |
| 1001-1500   | 19        | 0.82%   |
| 1501-2000   | 15        | 0.65%   |
| 801-900     | 7         | 0.3%    |
| 901-1000    | 3         | 0.13%   |
| 101-200     | 1         | 0.04%   |
| 1-100       | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1718      | 86.29%  |
| 16/10   | 178       | 8.94%   |
| 3/2     | 30        | 1.51%   |
| 21/9    | 26        | 1.31%   |
| Unknown | 15        | 0.75%   |
| 5/4     | 11        | 0.55%   |
| 4/3     | 7         | 0.35%   |
| 32/9    | 3         | 0.15%   |
| 3.40    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 957       | 41.02%  |
| 81-90          | 461       | 19.76%  |
| 201-250        | 177       | 7.59%   |
| 121-130        | 176       | 7.54%   |
| 71-80          | 119       | 5.1%    |
| 301-350        | 106       | 4.54%   |
| 351-500        | 48        | 2.06%   |
| 51-60          | 40        | 1.71%   |
| 151-200        | 40        | 1.71%   |
| 61-70          | 35        | 1.5%    |
| 251-300        | 30        | 1.29%   |
| More than 1000 | 26        | 1.11%   |
| 111-120        | 24        | 1.03%   |
| Unknown        | 23        | 0.99%   |
| 141-150        | 19        | 0.81%   |
| 131-140        | 19        | 0.81%   |
| 501-1000       | 19        | 0.81%   |
| 91-100         | 9         | 0.39%   |
| 41-50          | 3         | 0.13%   |
| 1-40           | 2         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1031      | 45.02%  |
| 101-120       | 589       | 25.72%  |
| 51-100        | 349       | 15.24%  |
| 161-240       | 171       | 7.47%   |
| More than 240 | 98        | 4.28%   |
| 1-50          | 29        | 1.27%   |
| Unknown       | 23        | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1517      | 76.04%  |
| 2     | 385       | 19.3%   |
| 3     | 53        | 2.66%   |
| 0     | 33        | 1.65%   |
| 4     | 7         | 0.35%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1111      | 35.85%  |
| Realtek Semiconductor             | 1110      | 35.82%  |
| Qualcomm Atheros                  | 401       | 12.94%  |
| Broadcom                          | 151       | 4.87%   |
| MediaTek                          | 63        | 2.03%   |
| Broadcom Limited                  | 26        | 0.84%   |
| Ralink                            | 23        | 0.74%   |
| Marvell Technology Group          | 20        | 0.65%   |
| ASIX Electronics                  | 15        | 0.48%   |
| TP-Link                           | 14        | 0.45%   |
| Sierra Wireless                   | 12        | 0.39%   |
| DisplayLink                       | 12        | 0.39%   |
| Samsung Electronics               | 11        | 0.35%   |
| Ralink Technology                 | 11        | 0.35%   |
| Qualcomm                          | 11        | 0.35%   |
| Lenovo                            | 10        | 0.32%   |
| Ericsson Business Mobile Networks | 10        | 0.32%   |
| Dell                              | 10        | 0.32%   |
| Huawei Technologies               | 9         | 0.29%   |
| Xiaomi                            | 7         | 0.23%   |
| JMicron Technology                | 7         | 0.23%   |
| D-Link                            | 5         | 0.16%   |
| Apple                             | 5         | 0.16%   |
| Hewlett-Packard                   | 4         | 0.13%   |
| T & A Mobile Phones               | 3         | 0.1%    |
| Qualcomm Atheros Communications   | 3         | 0.1%    |
| Nvidia                            | 3         | 0.1%    |
| NetGear                           | 3         | 0.1%    |
| Motorola PCS                      | 3         | 0.1%    |
| Google                            | 3         | 0.1%    |
| Fibocom                           | 3         | 0.1%    |
| ZyDAS                             | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| Wacom                             | 1         | 0.03%   |
| Toshiba                           | 1         | 0.03%   |
| Texas Instruments                 | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.03%   |
| Shenzhen Goodix Technology        | 1         | 0.03%   |
| SEGGER                            | 1         | 0.03%   |
| NIIMBOT                           | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 701       | 18.99%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 152       | 4.12%   |
| Intel Wi-Fi 6 AX200                                               | 132       | 3.58%   |
| Intel Wireless 8265 / 8275                                        | 94        | 2.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 93        | 2.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 80        | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 79        | 2.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 78        | 2.11%   |
| Intel Wi-Fi 6 AX201                                               | 78        | 2.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 77        | 2.09%   |
| Intel Wireless 7260                                               | 75        | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 67        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 65        | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 58        | 1.57%   |
| Intel Wireless 7265                                               | 57        | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 53        | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 52        | 1.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 52        | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 47        | 1.27%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 41        | 1.11%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 40        | 1.08%   |
| Intel Wireless 8260                                               | 38        | 1.03%   |
| Intel Wireless 3165                                               | 35        | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 34        | 0.92%   |
| Intel Ethernet Connection (4) I219-LM                             | 33        | 0.89%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 33        | 0.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 31        | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 31        | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 24        | 0.65%   |
| Intel Wireless 3160                                               | 23        | 0.62%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 21        | 0.57%   |
| Intel Wireless-AC 9260                                            | 21        | 0.57%   |
| Intel Ethernet Connection I217-LM                                 | 21        | 0.57%   |
| Broadcom BCM43142 802.11b/g/n                                     | 21        | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 19        | 0.51%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 19        | 0.51%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 18        | 0.49%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1061      | 52.66%  |
| Qualcomm Atheros                      | 336       | 16.67%  |
| Realtek Semiconductor                 | 324       | 16.08%  |
| Broadcom                              | 114       | 5.66%   |
| MediaTek                              | 61        | 3.03%   |
| Ralink                                | 23        | 1.14%   |
| Broadcom Limited                      | 23        | 1.14%   |
| Sierra Wireless                       | 12        | 0.6%    |
| TP-Link                               | 11        | 0.55%   |
| Ralink Technology                     | 11        | 0.55%   |
| Qualcomm                              | 8         | 0.4%    |
| Dell                                  | 5         | 0.25%   |
| D-Link                                | 5         | 0.25%   |
| Qualcomm Atheros Communications       | 3         | 0.15%   |
| NetGear                               | 3         | 0.15%   |
| Fibocom                               | 3         | 0.15%   |
| ZyDAS                                 | 2         | 0.1%    |
| Wacom                                 | 1         | 0.05%   |
| Texas Instruments                     | 1         | 0.05%   |
| Linksys                               | 1         | 0.05%   |
| Hewlett-Packard                       | 1         | 0.05%   |
| Edimax Technology                     | 1         | 0.05%   |
| D-Link System                         | 1         | 0.05%   |
| Belkin Components                     | 1         | 0.05%   |
| AVM                                   | 1         | 0.05%   |
| ASUSTek Computer                      | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 132       | 6.5%    |
| Intel Wireless 8265 / 8275                                     | 94        | 4.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 80        | 3.94%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 78        | 3.84%   |
| Intel Wi-Fi 6 AX201                                            | 78        | 3.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 77        | 3.79%   |
| Intel Wireless 7260                                            | 75        | 3.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 67        | 3.3%    |
| Intel Cannon Lake PCH CNVi WiFi                                | 65        | 3.2%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 58        | 2.86%   |
| Intel Wireless 7265                                            | 57        | 2.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 53        | 2.61%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 52        | 2.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 52        | 2.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 47        | 2.32%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 41        | 2.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 40        | 1.97%   |
| Intel Wireless 8260                                            | 38        | 1.87%   |
| Intel Wireless 3165                                            | 35        | 1.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 34        | 1.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 33        | 1.63%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 31        | 1.53%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 31        | 1.53%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 24        | 1.18%   |
| Intel Wireless 3160                                            | 23        | 1.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 21        | 1.03%   |
| Intel Wireless-AC 9260                                         | 21        | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                  | 21        | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 19        | 0.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 19        | 0.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 18        | 0.89%   |
| Intel Centrino Advanced-N 6235                                 | 18        | 0.89%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 17        | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 17        | 0.84%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 16        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16        | 0.79%   |
| Intel Centrino Ultimate-N 6300                                 | 13        | 0.64%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 13        | 0.64%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 12        | 0.59%   |
| Realtek 802.11n WLAN Adapter                                   | 12        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 974       | 60.72%  |
| Intel                            | 368       | 22.94%  |
| Qualcomm Atheros                 | 94        | 5.86%   |
| Broadcom                         | 48        | 2.99%   |
| Marvell Technology Group         | 20        | 1.25%   |
| ASIX Electronics                 | 15        | 0.94%   |
| DisplayLink                      | 12        | 0.75%   |
| Samsung Electronics              | 11        | 0.69%   |
| Lenovo                           | 10        | 0.62%   |
| Xiaomi                           | 7         | 0.44%   |
| JMicron Technology               | 7         | 0.44%   |
| Huawei Technologies              | 6         | 0.37%   |
| Apple                            | 5         | 0.31%   |
| Broadcom Limited                 | 4         | 0.25%   |
| TP-Link                          | 3         | 0.19%   |
| T & A Mobile Phones              | 3         | 0.19%   |
| Qualcomm                         | 3         | 0.19%   |
| Nvidia                           | 3         | 0.19%   |
| Google                           | 3         | 0.19%   |
| Motorola PCS                     | 2         | 0.12%   |
| MediaTek                         | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| HMD Global                       | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 701       | 42.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 152       | 9.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 93        | 5.69%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 79        | 4.83%   |
| Intel Ethernet Connection (4) I219-LM                             | 33        | 2.02%   |
| Intel Ethernet Connection (7) I219-LM                             | 24        | 1.47%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 21        | 1.29%   |
| Intel Ethernet Connection I219-LM                                 | 18        | 1.1%    |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 0.98%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 15        | 0.92%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.92%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.92%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 0.92%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.86%   |
| Intel Ethernet Connection (6) I219-V                              | 14        | 0.86%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.8%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 12        | 0.73%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.73%   |
| Intel Ethernet Connection (10) I219-V                             | 12        | 0.73%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.67%   |
| Intel Ethernet Connection (13) I219-V                             | 11        | 0.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 10        | 0.61%   |
| Intel Ethernet Connection I219-V                                  | 10        | 0.61%   |
| Intel 82567LM Gigabit Network Connection                          | 10        | 0.61%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 8         | 0.49%   |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.43%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7         | 0.43%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6         | 0.37%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.37%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 6         | 0.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6         | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.31%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 5         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1932      | 55.36%  |
| Ethernet | 1531      | 43.87%  |
| Modem    | 24        | 0.69%   |
| Unknown  | 3         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1627      | 77.96%  |
| Ethernet | 459       | 21.99%  |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1412      | 72.37%  |
| 1     | 489       | 25.06%  |
| 0     | 35        | 1.79%   |
| 3     | 15        | 0.77%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1622      | 82.34%  |
| Yes  | 348       | 17.66%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 878       | 53.02%  |
| Realtek Semiconductor           | 178       | 10.75%  |
| Qualcomm Atheros Communications | 160       | 9.66%   |
| IMC Networks                    | 81        | 4.89%   |
| Broadcom                        | 80        | 4.83%   |
| Lite-On Technology              | 72        | 4.35%   |
| Foxconn / Hon Hai               | 59        | 3.56%   |
| Dell                            | 31        | 1.87%   |
| Realtek                         | 24        | 1.45%   |
| Apple                           | 19        | 1.15%   |
| Hewlett-Packard                 | 13        | 0.79%   |
| Cambridge Silicon Radio         | 13        | 0.79%   |
| Toshiba                         | 10        | 0.6%    |
| Ralink                          | 10        | 0.6%    |
| Foxconn International           | 7         | 0.42%   |
| Ralink Technology               | 5         | 0.3%    |
| ASUSTek Computer                | 4         | 0.24%   |
| Alps Electric                   | 4         | 0.24%   |
| Taiyo Yuden                     | 2         | 0.12%   |
| Smart Modular Technologies      | 2         | 0.12%   |
| TP-Link                         | 1         | 0.06%   |
| SINO WEALTH                     | 1         | 0.06%   |
| MediaTek                        | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 311       | 18.76%  |
| Intel AX201 Bluetooth                               | 186       | 11.22%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 141       | 8.5%    |
| Intel AX200 Bluetooth                               | 128       | 7.72%   |
| Realtek Bluetooth Radio                             | 103       | 6.21%   |
| Qualcomm Atheros  Bluetooth Device                  | 87        | 5.25%   |
| Realtek  Bluetooth 4.2 Adapter                      | 54        | 3.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 26        | 1.57%   |
| Lite-On Bluetooth Device                            | 26        | 1.57%   |
| IMC Networks Bluetooth Radio                        | 26        | 1.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 25        | 1.51%   |
| Realtek Bluetooth Radio                             | 24        | 1.45%   |
| Intel Bluetooth Device                              | 22        | 1.33%   |
| IMC Networks Wireless_Device                        | 21        | 1.27%   |
| Foxconn / Hon Hai Wireless_Device                   | 21        | 1.27%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 1.21%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 1.15%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 1.09%   |
| Intel AX210 Bluetooth                               | 16        | 0.97%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 0.9%    |
| Lite-On Wireless_Device                             | 14        | 0.84%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.84%   |
| IMC Networks Bluetooth Device                       | 14        | 0.84%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 0.78%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 0.72%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.66%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.66%   |
| Apple Bluetooth Host Controller                     | 11        | 0.66%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.54%   |
| Broadcom HP Portable SoftSailing                    | 9         | 0.54%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 8         | 0.48%   |
| Dell DW375 Bluetooth Module                         | 8         | 0.48%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.42%   |
| IMC Networks Bluetooth USB Host Controller          | 7         | 0.42%   |
| Foxconn International BCM43142A0 Bluetooth module   | 7         | 0.42%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 6         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1551      | 62.84%  |
| AMD                              | 420       | 17.02%  |
| Nvidia                           | 317       | 12.84%  |
| Realtek Semiconductor            | 22        | 0.89%   |
| GN Netcom                        | 17        | 0.69%   |
| C-Media Electronics              | 16        | 0.65%   |
| Logitech                         | 14        | 0.57%   |
| Plantronics                      | 9         | 0.36%   |
| Lenovo                           | 9         | 0.36%   |
| Hewlett-Packard                  | 8         | 0.32%   |
| Texas Instruments                | 6         | 0.24%   |
| Generalplus Technology           | 6         | 0.24%   |
| Razer USA                        | 5         | 0.2%    |
| JMTek                            | 5         | 0.2%    |
| Creative Technology              | 5         | 0.2%    |
| Sony                             | 4         | 0.16%   |
| Dell                             | 4         | 0.16%   |
| Focusrite-Novation               | 3         | 0.12%   |
| CMX Systems                      | 3         | 0.12%   |
| ZOOM                             | 2         | 0.08%   |
| Microsoft                        | 2         | 0.08%   |
| Kingston Technology              | 2         | 0.08%   |
| GYROCOM C&C                      | 2         | 0.08%   |
| Google                           | 2         | 0.08%   |
| Corsair                          | 2         | 0.08%   |
| Conexant Systems                 | 2         | 0.08%   |
| Blue Microphones                 | 2         | 0.08%   |
| Apple                            | 2         | 0.08%   |
| Zhaoxin                          | 1         | 0.04%   |
| YZ Technology                    | 1         | 0.04%   |
| Winbond Electronics              | 1         | 0.04%   |
| Trust                            | 1         | 0.04%   |
| TerraTec Electronic              | 1         | 0.04%   |
| SteelSeries ApS                  | 1         | 0.04%   |
| Silicon Motion                   | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Sennheiser Communications        | 1         | 0.04%   |
| RODE Microphones                 | 1         | 0.04%   |
| QinHeng Electronics              | 1         | 0.04%   |
| Princeton Technology             | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 278       | 9.18%   |
| Intel Sunrise Point-LP HD Audio                                            | 231       | 7.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 162       | 5.35%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 146       | 4.82%   |
| Intel Cannon Lake PCH cAVS                                                 | 129       | 4.26%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 114       | 3.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 102       | 3.37%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 94        | 3.1%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 88        | 2.91%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 79        | 2.61%   |
| Intel Haswell-ULT HD Audio Controller                                      | 79        | 2.61%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 79        | 2.61%   |
| Intel 8 Series HD Audio Controller                                         | 79        | 2.61%   |
| Intel Comet Lake PCH-LP cAVS                                               | 65        | 2.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 56        | 1.85%   |
| AMD FCH Azalia Controller                                                  | 53        | 1.75%   |
| Intel Broadwell-U Audio Controller                                         | 51        | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 50        | 1.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 50        | 1.65%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 48        | 1.58%   |
| Intel Comet Lake PCH cAVS                                                  | 48        | 1.58%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 45        | 1.49%   |
| Intel CM238 HD Audio Controller                                            | 40        | 1.32%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 40        | 1.32%   |
| AMD Kabini HDMI/DP Audio                                                   | 40        | 1.32%   |
| Nvidia GP107GL High Definition Audio Controller                            | 37        | 1.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 36        | 1.19%   |
| Nvidia TU106 High Definition Audio Controller                              | 33        | 1.09%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 31        | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 29        | 0.96%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 25        | 0.83%   |
| Nvidia GF108 High Definition Audio Controller                              | 23        | 0.76%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 23        | 0.76%   |
| Nvidia GA104 High Definition Audio Controller                              | 22        | 0.73%   |
| Realtek Semiconductor USB Audio                                            | 21        | 0.69%   |
| Nvidia TU116 High Definition Audio Controller                              | 20        | 0.66%   |
| Nvidia GP106 High Definition Audio Controller                              | 19        | 0.63%   |
| Nvidia GA106 High Definition Audio Controller                              | 19        | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 19        | 0.63%   |
| Nvidia GK107 HDMI Audio Controller                                         | 16        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 461       | 29.36%  |
| SK hynix            | 328       | 20.89%  |
| Micron Technology   | 204       | 12.99%  |
| Kingston            | 153       | 9.75%   |
| Crucial             | 96        | 6.11%   |
| Unknown             | 58        | 3.69%   |
| A-DATA Technology   | 37        | 2.36%   |
| Ramaxel Technology  | 35        | 2.23%   |
| Elpida              | 28        | 1.78%   |
| Unknown (ABCD)      | 26        | 1.66%   |
| Nanya Technology    | 21        | 1.34%   |
| Corsair             | 19        | 1.21%   |
| Smart               | 10        | 0.64%   |
| Unknown             | 10        | 0.64%   |
| Transcend           | 9         | 0.57%   |
| G.Skill             | 8         | 0.51%   |
| Wilk                | 5         | 0.32%   |
| Smart Brazil        | 5         | 0.32%   |
| Teikon              | 4         | 0.25%   |
| Team                | 4         | 0.25%   |
| GOODRAM             | 4         | 0.25%   |
| Apacer              | 4         | 0.25%   |
| Silicon Power       | 3         | 0.19%   |
| SHARETRONIC         | 3         | 0.19%   |
| Goldkey             | 3         | 0.19%   |
| ASint Technology    | 3         | 0.19%   |
| CSX                 | 2         | 0.13%   |
| AMD                 | 2         | 0.13%   |
| V-GeN               | 1         | 0.06%   |
| V-Color             | 1         | 0.06%   |
| Unknown (8AD6)      | 1         | 0.06%   |
| Unknown (8A02)      | 1         | 0.06%   |
| Unknown (08AE)      | 1         | 0.06%   |
| Super Talent        | 1         | 0.06%   |
| Shenzhen Zhongteng  | 1         | 0.06%   |
| Shenzhen WODPOSIT   | 1         | 0.06%   |
| Reboto              | 1         | 0.06%   |
| Qimonda             | 1         | 0.06%   |
| PUSKILL             | 1         | 0.06%   |
| Patriot             | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 1.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 23        | 1.39%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 1.39%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 22        | 1.33%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 20        | 1.21%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 18        | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 1.03%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 0.97%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 15        | 0.91%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.85%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 14        | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.85%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.79%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 13        | 0.79%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 13        | 0.79%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 13        | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 12        | 0.73%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.67%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 11        | 0.67%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.67%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.67%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 11        | 0.67%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.67%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 11        | 0.67%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.67%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.6%    |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.6%    |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 10        | 0.6%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.6%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 10        | 0.6%    |
| Unknown                                                          | 10        | 0.6%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 9         | 0.54%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.48%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.48%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.48%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 8         | 0.48%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 8         | 0.48%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.48%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 8         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 780       | 59.91%  |
| DDR3    | 349       | 26.8%   |
| LPDDR4  | 68        | 5.22%   |
| LPDDR3  | 40        | 3.07%   |
| DDR2    | 19        | 1.46%   |
| DDR5    | 18        | 1.38%   |
| SDRAM   | 13        | 1%      |
| LPDDR5  | 9         | 0.69%   |
| Unknown | 5         | 0.38%   |
| DDR     | 1         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1164      | 88.45%  |
| Row Of Chips | 128       | 9.73%   |
| Chip         | 11        | 0.84%   |
| Unknown      | 7         | 0.53%   |
| DIMM         | 6         | 0.46%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 650       | 45.58%  |
| 4096  | 390       | 27.35%  |
| 16384 | 245       | 17.18%  |
| 2048  | 89        | 6.24%   |
| 32768 | 39        | 2.73%   |
| 1024  | 13        | 0.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 375       | 26.65%  |
| 3200    | 295       | 20.97%  |
| 1600    | 261       | 18.55%  |
| 2400    | 139       | 9.88%   |
| 2133    | 65        | 4.62%   |
| 1334    | 54        | 3.84%   |
| 1333    | 41        | 2.91%   |
| 4267    | 25        | 1.78%   |
| 4800    | 18        | 1.28%   |
| 1867    | 18        | 1.28%   |
| 3266    | 17        | 1.21%   |
| 8400    | 12        | 0.85%   |
| 667     | 11        | 0.78%   |
| 1067    | 10        | 0.71%   |
| Unknown | 10        | 0.71%   |
| 6400    | 9         | 0.64%   |
| 4199    | 9         | 0.64%   |
| 800     | 9         | 0.64%   |
| 4266    | 7         | 0.5%    |
| 2048    | 4         | 0.28%   |
| 1066    | 3         | 0.21%   |
| 975     | 3         | 0.21%   |
| 3000    | 2         | 0.14%   |
| 2933    | 2         | 0.14%   |
| 1866    | 2         | 0.14%   |
| 2666    | 1         | 0.07%   |
| 2000    | 1         | 0.07%   |
| 1776    | 1         | 0.07%   |
| 1200    | 1         | 0.07%   |
| 666     | 1         | 0.07%   |
| 533     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 23.53%  |
| Brother Industries  | 4         | 23.53%  |
| Samsung Electronics | 3         | 17.65%  |
| Canon               | 3         | 17.65%  |
| Seiko Epson         | 2         | 11.76%  |
| Xerox               | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Xerox Phaser 6500DN                             | 1         | 5.88%   |
| Seiko Epson L3110 Series                        | 1         | 5.88%   |
| Seiko Epson ET-2700 Series                      | 1         | 5.88%   |
| Samsung Xerox Phaser 3117 Laser Printer         | 1         | 5.88%   |
| Samsung SCX-3200 Series                         | 1         | 5.88%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 5.88%   |
| HP LaserJet Professional P 1102w                | 1         | 5.88%   |
| HP LaserJet 1020                                | 1         | 5.88%   |
| HP DeskJet F300 series                          | 1         | 5.88%   |
| HP DeskJet 2300 series                          | 1         | 5.88%   |
| Canon PIXMA MP250                               | 1         | 5.88%   |
| Canon MF4800 Series                             | 1         | 5.88%   |
| Canon iP2600 series                             | 1         | 5.88%   |
| Brother MFC-J4340DW                             | 1         | 5.88%   |
| Brother HL-L2390DW                              | 1         | 5.88%   |
| Brother HL-5450DN series                        | 1         | 5.88%   |
| Brother HL-2230 series                          | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 401       | 21.66%  |
| IMC Networks                           | 212       | 11.45%  |
| Microdia                               | 179       | 9.67%   |
| Realtek Semiconductor                  | 157       | 8.48%   |
| Acer                                   | 154       | 8.32%   |
| Quanta                                 | 121       | 6.54%   |
| Sunplus Innovation Technology          | 105       | 5.67%   |
| Cheng Uei Precision Industry (Foxlink) | 85        | 4.59%   |
| Suyin                                  | 45        | 2.43%   |
| Syntek                                 | 40        | 2.16%   |
| Lite-On Technology                     | 39        | 2.11%   |
| Silicon Motion                         | 38        | 2.05%   |
| Logitech                               | 32        | 1.73%   |
| Luxvisions Innotech Limited            | 31        | 1.67%   |
| Bison Electronics                      | 26        | 1.4%    |
| Apple                                  | 25        | 1.35%   |
| Alcor Micro                            | 19        | 1.03%   |
| Ricoh                                  | 15        | 0.81%   |
| Samsung Electronics                    | 13        | 0.7%    |
| Lenovo                                 | 11        | 0.59%   |
| Sonix Technology                       | 10        | 0.54%   |
| Y Media                                | 6         | 0.32%   |
| SunplusIT                              | 6         | 0.32%   |
| Sunplus Technology                     | 5         | 0.27%   |
| Importek                               | 5         | 0.27%   |
| USB Camera                             | 4         | 0.22%   |
| Microsoft                              | 4         | 0.22%   |
| Generalplus Technology                 | 4         | 0.22%   |
| Z-Star Microelectronics                | 3         | 0.16%   |
| ShineTech                              | 3         | 0.16%   |
| Intel                                  | 3         | 0.16%   |
| Genesys Logic                          | 3         | 0.16%   |
| USB Camera CS                          | 2         | 0.11%   |
| Primax Electronics                     | 2         | 0.11%   |
| Novatek Microelectronics               | 2         | 0.11%   |
| MacroSilicon                           | 2         | 0.11%   |
| LG Electronics                         | 2         | 0.11%   |
| Google                                 | 2         | 0.11%   |
| GEMBIRD                                | 2         | 0.11%   |
| DigiTech                               | 2         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 92        | 4.94%   |
| Microdia Integrated_Webcam_HD                                              | 87        | 4.67%   |
| IMC Networks Integrated Camera                                             | 65        | 3.49%   |
| Realtek Integrated_Webcam_HD                                               | 64        | 3.43%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 63        | 3.38%   |
| Sunplus Integrated_Webcam_HD                                               | 52        | 2.79%   |
| Chicony HD Webcam                                                          | 42        | 2.25%   |
| Acer Integrated Camera                                                     | 40        | 2.15%   |
| Chicony USB2.0 Camera                                                      | 30        | 1.61%   |
| Syntek Integrated Camera                                                   | 27        | 1.45%   |
| Quanta HD User Facing                                                      | 25        | 1.34%   |
| Chicony HP HD Camera                                                       | 24        | 1.29%   |
| Acer HD Webcam                                                             | 23        | 1.23%   |
| Chicony HD User Facing                                                     | 22        | 1.18%   |
| Acer Lenovo EasyCamera                                                     | 22        | 1.18%   |
| Microdia Integrated Webcam                                                 | 21        | 1.13%   |
| Quanta HP TrueVision HD Camera                                             | 18        | 0.97%   |
| Quanta HP HD Camera                                                        | 16        | 0.86%   |
| Lite-On Integrated Camera                                                  | 16        | 0.86%   |
| Chicony Integrated Camera (1280x720@30)                                    | 16        | 0.86%   |
| Samsung Galaxy A5 (MTP)                                                    | 13        | 0.7%    |
| Realtek Integrated Webcam                                                  | 13        | 0.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 13        | 0.7%    |
| IMC Networks HD Camera                                                     | 13        | 0.7%    |
| Chicony HP Wide Vision HD Camera                                           | 13        | 0.7%    |
| Chicony HP Truevision HD                                                   | 13        | 0.7%    |
| Bison Integrated Camera                                                    | 13        | 0.7%    |
| Quanta HD Webcam                                                           | 12        | 0.64%   |
| Acer BisonCam,NB Pro                                                       | 12        | 0.64%   |
| Acer BisonCam, NB Pro                                                      | 12        | 0.64%   |
| Microdia Webcam Vitade AF                                                  | 11        | 0.59%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 11        | 0.59%   |
| Chicony HP Truevision HD camera                                            | 11        | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 11        | 0.59%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                            | 11        | 0.59%   |
| Sunplus HD WebCam                                                          | 10        | 0.54%   |
| Realtek USB Camera                                                         | 10        | 0.54%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 10        | 0.54%   |
| Logitech HD Pro Webcam C920                                                | 10        | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 10        | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 118       | 28.16%  |
| Validity Sensors                   | 113       | 26.97%  |
| Shenzhen Goodix Technology         | 87        | 20.76%  |
| Elan Microelectronics              | 35        | 8.35%   |
| Upek                               | 21        | 5.01%   |
| AuthenTec                          | 19        | 4.53%   |
| LighTuning Technology              | 17        | 4.06%   |
| STMicroelectronics                 | 5         | 1.19%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.48%   |
| Focal-systems.Corp                 | 2         | 0.48%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 53        | 12.65%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 47        | 11.22%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 5.01%   |
| Elan ELAN:Fingerprint                                                      | 21        | 5.01%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 20        | 4.77%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 4.53%   |
| Shenzhen Goodix Fingerprint Reader                                         | 18        | 4.3%    |
| Shenzhen Goodix FingerPrint                                                | 16        | 3.82%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 3.1%    |
| Elan ELAN:ARM-M4                                                           | 13        | 3.1%    |
| Validity Sensors Synaptics WBDI                                            | 11        | 2.63%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 2.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 11        | 2.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 10        | 2.39%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.15%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 9         | 2.15%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.15%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 2.15%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.67%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 7         | 1.67%   |
| Synaptics UWP WBDI                                                         | 7         | 1.67%   |
| AuthenTec AES2810                                                          | 7         | 1.67%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 1.43%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.19%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.19%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.19%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.19%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.19%   |
| Unknown                                                                    | 5         | 1.19%   |
| Validity Sensors VFS491                                                    | 4         | 0.95%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 0.95%   |
| Synaptics  WBDI                                                            | 3         | 0.72%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.72%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.48%   |
| Synaptics WBDI Device                                                      | 2         | 0.48%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.48%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.48%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.48%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.48%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.24%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 85        | 47.22%  |
| Alcor Micro               | 51        | 28.33%  |
| Upek                      | 13        | 7.22%   |
| O2 Micro                  | 8         | 4.44%   |
| Lenovo                    | 7         | 3.89%   |
| Yubico.com                | 2         | 1.11%   |
| Realtek Semiconductor     | 2         | 1.11%   |
| Clay Logic                | 2         | 1.11%   |
| Advanced Card Systems     | 2         | 1.11%   |
| Watchdata                 | 1         | 0.56%   |
| SCM Microsystems          | 1         | 0.56%   |
| In Focus Systems          | 1         | 0.56%   |
| Giesecke & Devrient       | 1         | 0.56%   |
| Fujitsu Siemens Computers | 1         | 0.56%   |
| Chicony Electronics       | 1         | 0.56%   |
| BIT4ID                    | 1         | 0.56%   |
| Aladdin Knowledge Systems | 1         | 0.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 51        | 28.33%  |
| Broadcom 5880                                                                | 24        | 13.33%  |
| Broadcom 58200                                                               | 23        | 12.78%  |
| Broadcom BCM5880 Secure Applications Processor                               | 22        | 12.22%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 7.78%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 13        | 7.22%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 4.44%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 3.89%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.11%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.11%   |
| Clay Logic Nitrokey Pro                                                      | 2         | 1.11%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.11%   |
| Advanced Card Systems ACR39U                                                 | 2         | 1.11%   |
| Watchdata USB Key                                                            | 1         | 0.56%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.56%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.56%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.56%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.56%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.56%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.56%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1168      | 58.58%  |
| 1     | 657       | 32.95%  |
| 2     | 148       | 7.42%   |
| 3     | 10        | 0.5%    |
| 4     | 5         | 0.25%   |
| 7     | 3         | 0.15%   |
| 6     | 2         | 0.1%    |
| 9     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 411       | 40.73%  |
| Graphics card            | 170       | 16.85%  |
| Chipcard                 | 163       | 16.15%  |
| Net/wireless             | 86        | 8.52%   |
| Camera                   | 41        | 4.06%   |
| Multimedia controller    | 33        | 3.27%   |
| Bluetooth                | 27        | 2.68%   |
| Sound                    | 17        | 1.68%   |
| Storage                  | 15        | 1.49%   |
| Card reader              | 15        | 1.49%   |
| Communication controller | 14        | 1.39%   |
| Net/ethernet             | 7         | 0.69%   |
| Network                  | 5         | 0.5%    |
| Modem                    | 4         | 0.4%    |
| Firewire controller      | 1         | 0.1%    |

