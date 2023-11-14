Xubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Xubuntu 22.04.

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

Total: 445

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | G505 20240                  | [ef019ff242](https://linux-hardware.org/?probe=ef019ff242) | Nov 06, 2023 |
| AMI           | Intel                       | [98d35ad708](https://linux-hardware.org/?probe=98d35ad708) | Oct 31, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [6273e445bd](https://linux-hardware.org/?probe=6273e445bd) | Oct 30, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a718d2e0ba](https://linux-hardware.org/?probe=a718d2e0ba) | Oct 28, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [c866e0068b](https://linux-hardware.org/?probe=c866e0068b) | Oct 28, 2023 |
| Lenovo        | ThinkPad T61 64607EU        | [413cefff03](https://linux-hardware.org/?probe=413cefff03) | Oct 26, 2023 |
| Acer          | Aspire 5740                 | [78702b9deb](https://linux-hardware.org/?probe=78702b9deb) | Oct 23, 2023 |
| Dell          | Latitude 3490               | [174ee1b12e](https://linux-hardware.org/?probe=174ee1b12e) | Oct 20, 2023 |
| HP            | 250 G8 Notebook PC          | [949b939768](https://linux-hardware.org/?probe=949b939768) | Oct 16, 2023 |
| Acer          | Aspire A317-51K             | [b342c56fc5](https://linux-hardware.org/?probe=b342c56fc5) | Oct 15, 2023 |
| Dell          | Latitude 7330               | [8632b84be8](https://linux-hardware.org/?probe=8632b84be8) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | [edb8f551bf](https://linux-hardware.org/?probe=edb8f551bf) | Oct 14, 2023 |
| HP            | Laptop 15-dw0xxx            | [b7a193296f](https://linux-hardware.org/?probe=b7a193296f) | Oct 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [41ca042a36](https://linux-hardware.org/?probe=41ca042a36) | Oct 14, 2023 |
| Lenovo        | ThinkPad T430u 3352A83      | [c5a829d842](https://linux-hardware.org/?probe=c5a829d842) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | [1a8e527488](https://linux-hardware.org/?probe=1a8e527488) | Oct 13, 2023 |
| Dell          | Latitude 5411               | [48ecb46d24](https://linux-hardware.org/?probe=48ecb46d24) | Oct 09, 2023 |
| MSI           | GP65 Leopard 10SDK          | [6b02c3ce0f](https://linux-hardware.org/?probe=6b02c3ce0f) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [3e5383da88](https://linux-hardware.org/?probe=3e5383da88) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [cab160aff3](https://linux-hardware.org/?probe=cab160aff3) | Oct 08, 2023 |
| Fujitsu Si... | LIFEBOOK T4215              | [392481b855](https://linux-hardware.org/?probe=392481b855) | Oct 04, 2023 |
| Fujitsu       | LIFEBOOK E734               | [61f61b1b63](https://linux-hardware.org/?probe=61f61b1b63) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK E734               | [ffb5ff9359](https://linux-hardware.org/?probe=ffb5ff9359) | Sep 25, 2023 |
| Toshiba       | Satellite C50D-A-10E        | [46f0ec000d](https://linux-hardware.org/?probe=46f0ec000d) | Sep 24, 2023 |
| Dell          | XPS 15 9570                 | [fe5f9ad018](https://linux-hardware.org/?probe=fe5f9ad018) | Sep 23, 2023 |
| ASUSTek       | X510UQR                     | [364ee59aef](https://linux-hardware.org/?probe=364ee59aef) | Sep 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a6fd72ec9a](https://linux-hardware.org/?probe=a6fd72ec9a) | Sep 20, 2023 |
| Lenovo        | ThinkPad T430 2349BG6       | [dbd8f7715f](https://linux-hardware.org/?probe=dbd8f7715f) | Sep 19, 2023 |
| Apple         | MacBookPro5,4               | [f2d4f47a8e](https://linux-hardware.org/?probe=f2d4f47a8e) | Sep 18, 2023 |
| Dell          | Latitude 3520               | [c74d2293dd](https://linux-hardware.org/?probe=c74d2293dd) | Sep 18, 2023 |
| Lenovo        | ThinkPad T450 20BVA01QHV    | [4f0a2bdfdc](https://linux-hardware.org/?probe=4f0a2bdfdc) | Sep 15, 2023 |
| ASUSTek       | K72Dr                       | [46edd6eb72](https://linux-hardware.org/?probe=46edd6eb72) | Sep 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [cf69e328c4](https://linux-hardware.org/?probe=cf69e328c4) | Sep 14, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [b6a4327a8b](https://linux-hardware.org/?probe=b6a4327a8b) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [a51361ebb2](https://linux-hardware.org/?probe=a51361ebb2) | Sep 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [00cbde2fb9](https://linux-hardware.org/?probe=00cbde2fb9) | Sep 12, 2023 |
| Medion        | Akoya P2213T                | [7d201de7d6](https://linux-hardware.org/?probe=7d201de7d6) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5b93cd5b36](https://linux-hardware.org/?probe=5b93cd5b36) | Sep 11, 2023 |
| Dell          | Vostro 3501                 | [7caa16d219](https://linux-hardware.org/?probe=7caa16d219) | Sep 11, 2023 |
| Olivetti      | OLIBOOK PX5-XXXAES          | [70225c18e1](https://linux-hardware.org/?probe=70225c18e1) | Sep 10, 2023 |
| Lenovo        | ThinkPad X250 20CLA1YJUK    | [a068fec56f](https://linux-hardware.org/?probe=a068fec56f) | Sep 09, 2023 |
| Dell          | XPS 13 9305                 | [b3756f752a](https://linux-hardware.org/?probe=b3756f752a) | Sep 08, 2023 |
| Medion        | Akoya P2213T                | [2464869ce2](https://linux-hardware.org/?probe=2464869ce2) | Sep 06, 2023 |
| HP            | EliteBook 820 G3            | [5ef4c889a4](https://linux-hardware.org/?probe=5ef4c889a4) | Aug 31, 2023 |
| Dell          | Latitude E5510              | [61f6df7426](https://linux-hardware.org/?probe=61f6df7426) | Aug 29, 2023 |
| HP            | Pavilion 17                 | [ba077d7ea1](https://linux-hardware.org/?probe=ba077d7ea1) | Aug 29, 2023 |
| Dell          | XPS 15 9500                 | [74ad31c9de](https://linux-hardware.org/?probe=74ad31c9de) | Aug 29, 2023 |
| Apple         | MacBookPro7,1               | [f520b2dd72](https://linux-hardware.org/?probe=f520b2dd72) | Aug 28, 2023 |
| ASUSTek       | ROG Strix G733PY_G733PY     | [b886de0613](https://linux-hardware.org/?probe=b886de0613) | Aug 28, 2023 |
| HP            | Pavilion 17                 | [1d04c114d6](https://linux-hardware.org/?probe=1d04c114d6) | Aug 26, 2023 |
| Toshiba       | Satellite C55D-B            | [b7dce1f6e0](https://linux-hardware.org/?probe=b7dce1f6e0) | Aug 25, 2023 |
| Lenovo        | ThinkPad T460s 20F9003VM... | [e6e076d380](https://linux-hardware.org/?probe=e6e076d380) | Aug 23, 2023 |
| Acer          | TMP255-M                    | [4d5632e2d0](https://linux-hardware.org/?probe=4d5632e2d0) | Aug 22, 2023 |
| GPU Compan... | GWTN156-5                   | [22efc40cfd](https://linux-hardware.org/?probe=22efc40cfd) | Aug 21, 2023 |
| HP            | Presario CQ42               | [183f035603](https://linux-hardware.org/?probe=183f035603) | Aug 20, 2023 |
| Lenovo        | G50-70 20351                | [a8a0c22567](https://linux-hardware.org/?probe=a8a0c22567) | Aug 20, 2023 |
| HP            | 250 G4 Notebook PC          | [ea6fdc81ab](https://linux-hardware.org/?probe=ea6fdc81ab) | Aug 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f626ffa833](https://linux-hardware.org/?probe=f626ffa833) | Aug 17, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [48af3e541c](https://linux-hardware.org/?probe=48af3e541c) | Aug 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [5b482b674c](https://linux-hardware.org/?probe=5b482b674c) | Aug 16, 2023 |
| Lenovo        | ThinkPad X250 20CM001RMC    | [618a7e3e29](https://linux-hardware.org/?probe=618a7e3e29) | Aug 14, 2023 |
| Lenovo        | B50-50 80S2                 | [6c897e0c63](https://linux-hardware.org/?probe=6c897e0c63) | Aug 14, 2023 |
| Lenovo        | IdeaPad Y570 0862           | [0ea140ff49](https://linux-hardware.org/?probe=0ea140ff49) | Aug 12, 2023 |
| Dell          | Latitude 3540               | [496e3ab340](https://linux-hardware.org/?probe=496e3ab340) | Aug 10, 2023 |
| HP            | Laptop 17-cp0xxx            | [c5a255abcb](https://linux-hardware.org/?probe=c5a255abcb) | Aug 10, 2023 |
| ASUSTek       | X541UVK                     | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Acer          | Aspire 5732Z                | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | [cc5ec06f60](https://linux-hardware.org/?probe=cc5ec06f60) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | [14e4cbffd4](https://linux-hardware.org/?probe=14e4cbffd4) | Aug 08, 2023 |
| Dell          | Latitude 5411               | [2d69739196](https://linux-hardware.org/?probe=2d69739196) | Aug 07, 2023 |
| Acer          | Aspire A517-52              | [aa9fd10def](https://linux-hardware.org/?probe=aa9fd10def) | Aug 01, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [67fbb84480](https://linux-hardware.org/?probe=67fbb84480) | Jul 31, 2023 |
| Acer          | Aspire A517-52              | [1df8f3a3ed](https://linux-hardware.org/?probe=1df8f3a3ed) | Jul 29, 2023 |
| Medion        | Akoya P2213T                | [740da3bf14](https://linux-hardware.org/?probe=740da3bf14) | Jul 29, 2023 |
| Gateway       | NV57H                       | [efc311477f](https://linux-hardware.org/?probe=efc311477f) | Jul 28, 2023 |
| Samsung       | N250P/N145P                 | [6b6e675a4c](https://linux-hardware.org/?probe=6b6e675a4c) | Jul 28, 2023 |
| Acer          | Extensa 2510                | [b276a715eb](https://linux-hardware.org/?probe=b276a715eb) | Jul 27, 2023 |
| Acer          | AOD255                      | [4f96dbf750](https://linux-hardware.org/?probe=4f96dbf750) | Jul 25, 2023 |
| Acer          | AOD255                      | [3543f0800e](https://linux-hardware.org/?probe=3543f0800e) | Jul 24, 2023 |
| MSI           | MEGA BOOK GX620             | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [38856f8131](https://linux-hardware.org/?probe=38856f8131) | Jul 21, 2023 |
| HP            | Laptop 15s-fq2xxx           | [977443386e](https://linux-hardware.org/?probe=977443386e) | Jul 21, 2023 |
| Itautec       | Infoway w7535               | [bde95c0c99](https://linux-hardware.org/?probe=bde95c0c99) | Jul 21, 2023 |
| Thomson       | N15C8BK2T                   | [2e04333da5](https://linux-hardware.org/?probe=2e04333da5) | Jul 19, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [c9a443767b](https://linux-hardware.org/?probe=c9a443767b) | Jul 16, 2023 |
| MSI           | Modern 15 A10RBS            | [fde24c2a13](https://linux-hardware.org/?probe=fde24c2a13) | Jul 15, 2023 |
| Lenovo        | G50-70 20351                | [d18c64af74](https://linux-hardware.org/?probe=d18c64af74) | Jul 14, 2023 |
| GPU Compan... | GWNC21524                   | [e3e2452c10](https://linux-hardware.org/?probe=e3e2452c10) | Jul 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| HP            | Laptop 15s-fq2xxx           | [5aacfb69aa](https://linux-hardware.org/?probe=5aacfb69aa) | Jul 12, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [d4bc86a90a](https://linux-hardware.org/?probe=d4bc86a90a) | Jul 12, 2023 |
| HP            | ProBook 11 G2               | [db2ec8adc8](https://linux-hardware.org/?probe=db2ec8adc8) | Jul 08, 2023 |
| Acer          | Aspire A315-54              | [4aba66ddfb](https://linux-hardware.org/?probe=4aba66ddfb) | Jul 07, 2023 |
| Dell          | Latitude 3540               | [4ebbd2913f](https://linux-hardware.org/?probe=4ebbd2913f) | Jul 06, 2023 |
| HP            | Compaq Presario CQ60        | [983745a0d2](https://linux-hardware.org/?probe=983745a0d2) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | [a5bd493e91](https://linux-hardware.org/?probe=a5bd493e91) | Jul 03, 2023 |
| Google        | Snappy                      | [683d8bf80a](https://linux-hardware.org/?probe=683d8bf80a) | Jul 02, 2023 |
| Google        | Snappy                      | [d3502a53cc](https://linux-hardware.org/?probe=d3502a53cc) | Jul 02, 2023 |
| HP            | Pavilion 17                 | [e6daccb5b9](https://linux-hardware.org/?probe=e6daccb5b9) | Jul 02, 2023 |
| Acer          | Aspire A517-52              | [7c14851b62](https://linux-hardware.org/?probe=7c14851b62) | Jul 02, 2023 |
| MSI           | GF63 Thin 11UC              | [5270a5ddc7](https://linux-hardware.org/?probe=5270a5ddc7) | Jul 01, 2023 |
| Dynabook      | B65/ER                      | [8f6f243e98](https://linux-hardware.org/?probe=8f6f243e98) | Jul 01, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| Acer          | Aspire A517-52              | [79f2cae4d6](https://linux-hardware.org/?probe=79f2cae4d6) | Jun 30, 2023 |
| Google        | Fleex                       | [7e3eb2d4f9](https://linux-hardware.org/?probe=7e3eb2d4f9) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | [06d27800c2](https://linux-hardware.org/?probe=06d27800c2) | Jun 29, 2023 |
| Apple         | MacBookPro7,1               | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [338b2e7db3](https://linux-hardware.org/?probe=338b2e7db3) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Dell          | Latitude E6410              | [7d1989fd84](https://linux-hardware.org/?probe=7d1989fd84) | Jun 24, 2023 |
| Dell          | Inspiron 5415               | [ade4d4c90c](https://linux-hardware.org/?probe=ade4d4c90c) | Jun 19, 2023 |
| Acer          | Aspire 5600                 | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| GPU Compan... | GWNC21524                   | [5a31ac8b21](https://linux-hardware.org/?probe=5a31ac8b21) | Jun 15, 2023 |
| Samsung       | 760XDA                      | [f0decf4dbe](https://linux-hardware.org/?probe=f0decf4dbe) | Jun 14, 2023 |
| GPU Compan... | GWTN156-5                   | [b0afd2fa7b](https://linux-hardware.org/?probe=b0afd2fa7b) | Jun 13, 2023 |
| Dell          | Latitude 5411               | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| HP            | EliteBook 640 14 inch G9... | [69f20a331c](https://linux-hardware.org/?probe=69f20a331c) | Jun 12, 2023 |
| Toshiba       | Satellite C650              | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [2f5adf59a3](https://linux-hardware.org/?probe=2f5adf59a3) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Dell          | Precision 5510              | [9888f3aedd](https://linux-hardware.org/?probe=9888f3aedd) | Jun 06, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| HP            | Laptop 14s-dq0xxx           | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| Unknown       | Unknown                     | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Chuwi         | CoreBook X                  | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| Unknown       | Unknown                     | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Dell          | Inspiron 15-3552            | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| Dell          | Latitude E4200              | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| Dell          | Vostro 5620                 | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Google        | Snappy                      | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [0b0b5e02cc](https://linux-hardware.org/?probe=0b0b5e02cc) | May 13, 2023 |
| Fujitsu       | LIFEBOOK P702               | [b1460b51ac](https://linux-hardware.org/?probe=b1460b51ac) | May 12, 2023 |
| HP            | ProBook 640 G1              | [23cff0250a](https://linux-hardware.org/?probe=23cff0250a) | May 12, 2023 |
| Dell          | Vostro 5620                 | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7b53d1c3dc](https://linux-hardware.org/?probe=7b53d1c3dc) | May 11, 2023 |
| Dell          | Latitude E4310              | [84d1a3fda9](https://linux-hardware.org/?probe=84d1a3fda9) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Google        | Edgar                       | [372d5c177f](https://linux-hardware.org/?probe=372d5c177f) | May 10, 2023 |
| Gigabyte      | A7 K1                       | [1c37df2d10](https://linux-hardware.org/?probe=1c37df2d10) | May 09, 2023 |
| Google        | Snappy                      | [52836871bb](https://linux-hardware.org/?probe=52836871bb) | May 09, 2023 |
| Google        | Snappy                      | [a026aff306](https://linux-hardware.org/?probe=a026aff306) | May 09, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [0f322b6e3f](https://linux-hardware.org/?probe=0f322b6e3f) | May 08, 2023 |
| Google        | Auron_Yuna                  | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| HP            | Pavilion dv6                | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| Dell          | Inspiron 15-3567            | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [c693555567](https://linux-hardware.org/?probe=c693555567) | May 05, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| HP            | 15                          | [17817f5320](https://linux-hardware.org/?probe=17817f5320) | May 02, 2023 |
| Toshiba       | EQUIUM P200                 | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| SGIN          | M15                         | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Dell          | Vostro 1520                 | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| Dell          | XPS 13 9333                 | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| GPU Compan... | GWTN156-5                   | [4611a1d998](https://linux-hardware.org/?probe=4611a1d998) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| HP            | ProBook 11 G2               | [222f45e8c6](https://linux-hardware.org/?probe=222f45e8c6) | Apr 18, 2023 |
| HP            | Pavilion g6                 | [4c6934e946](https://linux-hardware.org/?probe=4c6934e946) | Apr 17, 2023 |
| HP            | Pavilion g6                 | [5fc4a56d59](https://linux-hardware.org/?probe=5fc4a56d59) | Apr 17, 2023 |
| HP            | Laptop 17-cp2xxx            | [b901ff7e98](https://linux-hardware.org/?probe=b901ff7e98) | Apr 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [7f4ed3cfde](https://linux-hardware.org/?probe=7f4ed3cfde) | Apr 13, 2023 |
| Lenovo        | ThinkPad X200s 74664SJ      | [54088fa2e9](https://linux-hardware.org/?probe=54088fa2e9) | Apr 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Toshiba       | Satellite L750D             | [d510eabb78](https://linux-hardware.org/?probe=d510eabb78) | Apr 08, 2023 |
| Toshiba       | Satellite L750D             | [3c8c0e7455](https://linux-hardware.org/?probe=3c8c0e7455) | Apr 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [93cb5f66a1](https://linux-hardware.org/?probe=93cb5f66a1) | Apr 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [2ac5f02bb5](https://linux-hardware.org/?probe=2ac5f02bb5) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Dell          | Latitude E6400              | [5aa68e620c](https://linux-hardware.org/?probe=5aa68e620c) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Medion        | S321X                       | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| HP            | EliteBook 6930p             | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| Unknown       | Unknown                     | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| Gateway       | EC14 Series                 | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| Gateway       | EC14 Series                 | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| Google        | Kefka                       | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| GPU Compan... | GWTN156-5                   | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| Toshiba       | Satellite C55D-B            | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| Acer          | Aspire A315-43              | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| Acer          | Aspire 5740                 | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| HP            | 655                         | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| HP            | EliteBook 820 G3            | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| Dell          | Studio 1450                 | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| HP            | Pavilion 15                 | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Sony          | VPCEA3S1E                   | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| HP            | Pavilion g6                 | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Dell          | Latitude E5450              | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| Acer          | Extensa 5635ZG              | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| HP            | 250 G7 Notebook PC          | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| HP            | 240 G3                      | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Acer          | Aspire 5920G                | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Notebook      | W65_67SZ                    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Dell          | Venue 11 Pro 7139           | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| ASUSTek       | UX305CA                     | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Notebook      | NJx0MU                      | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| ASUSTek       | X555YI                      | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| HP            | Laptop 17-bs0xx             | [f1494f113b](https://linux-hardware.org/?probe=f1494f113b) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [79d4fe0592](https://linux-hardware.org/?probe=79d4fe0592) | Jan 01, 2023 |
| Acer          | Aspire ES1-131              | [aeb6ecee74](https://linux-hardware.org/?probe=aeb6ecee74) | Jan 01, 2023 |
| Dell          | Latitude E5440              | [9578ad1ea3](https://linux-hardware.org/?probe=9578ad1ea3) | Dec 31, 2022 |
| HP            | Pavilion 17                 | [4a8c3f4014](https://linux-hardware.org/?probe=4a8c3f4014) | Dec 29, 2022 |
| Acer          | Nitro AN515-55              | [79f628b951](https://linux-hardware.org/?probe=79f628b951) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [15ec0001c5](https://linux-hardware.org/?probe=15ec0001c5) | Dec 29, 2022 |
| HP            | Pavilion 15                 | [e84551a6eb](https://linux-hardware.org/?probe=e84551a6eb) | Dec 29, 2022 |
| HP            | Compaq Presario C700        | [20a055c383](https://linux-hardware.org/?probe=20a055c383) | Dec 29, 2022 |
| Lenovo        | ThinkPad X230 23252S4       | [667dcc287e](https://linux-hardware.org/?probe=667dcc287e) | Dec 28, 2022 |
| HP            | Compaq Presario C700        | [a4d55d44ed](https://linux-hardware.org/?probe=a4d55d44ed) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| Toshiba       | Satellite C650              | [89b85889f9](https://linux-hardware.org/?probe=89b85889f9) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | [3bf8001e85](https://linux-hardware.org/?probe=3bf8001e85) | Dec 24, 2022 |
| HP            | Laptop 15-bw0xx             | [8a5bfa5e66](https://linux-hardware.org/?probe=8a5bfa5e66) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| ASUSTek       | X555LF                      | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| Dell          | Latitude E5450              | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| Sony          | VPCS12V9E                   | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| HUAWEI        | HVY-WXX9                    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| Fusion5       | Lapbook T90B                | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| ASUSTek       | UX31E                       | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| Lenovo        | G50-80 80E5                 | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| Sony          | VPCEH25EN                   | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| HP            | 245 G8 Notebook PC          | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| HP            | ProBook 6450b               | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Precision M6400             | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Dell          | Inspiron 5490               | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Inspiron 3421               | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| HP            | 15                          | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Unknown       | Unknown                     | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| GPU Compan... | GWTN116-3                   | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Lenovo        | B70-80 80MR                 | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Toshiba       | Satellite C650              | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Tactus        | GeoBook 140                 | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Dell          | Latitude 7490               | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| Dell          | Precision 5540              | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Dell          | Inspiron N5010              | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| Dell          | XPS 13 9380                 | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| HP            | EliteBook 8540p             | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| ASUSTek       | K53TA                       | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Toshiba       | PT10F                       | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Acer          | Aspire V3-551G              | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| GMKtec        | NucBox5                     | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Schenker      | WORK (Early 2021)           | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| Lenovo        | G50-30 80G0                 | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| Acer          | Aspire E1-532               | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| ASUSTek       | X453MA                      | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| Samsung       | 370E4K                      | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| HP            | EliteBook 840 G3            | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| Standard      | Unknown                     | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| HP            | ProBook 445 G7              | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| GPU Compan... | GWTN141-4                   | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| AMI           | Intel                       | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| Chuwi         | GemiBook Pro                | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Latitude D820               | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| HP            | Mini 5103                   | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| Google        | Snappy                      | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| ASUSTek       | UL30A                       | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| Google        | Droid                       | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Unknown       | Unknown                     | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| Dell          | Inspiron 7501               | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| Dell          | Latitude 7420               | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Dell          | XPS M1530                   | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| Dell          | XPS M1530                   | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| Acer          | Aspire ES1-512              | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| HP            | 255 G8 Notebook PC          | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.15.0-56-generic    | 23        | 6.2%    |
| 5.15.0-47-generic    | 19        | 5.12%   |
| 5.15.0-58-generic    | 17        | 4.58%   |
| 5.15.0-52-generic    | 16        | 4.31%   |
| 5.15.0-48-generic    | 16        | 4.31%   |
| 6.2.0-26-generic     | 13        | 3.5%    |
| 5.15.0-60-generic    | 13        | 3.5%    |
| 5.15.0-25-generic    | 13        | 3.5%    |
| 6.2.0-32-generic     | 11        | 2.96%   |
| 5.15.0-67-generic    | 10        | 2.7%    |
| 5.19.0-45-generic    | 9         | 2.43%   |
| 5.19.0-38-generic    | 9         | 2.43%   |
| 5.15.0-71-generic    | 9         | 2.43%   |
| 5.19.0-46-generic    | 8         | 2.16%   |
| 5.19.0-41-generic    | 8         | 2.16%   |
| 5.15.0-46-generic    | 8         | 2.16%   |
| 5.19.0-35-generic    | 7         | 1.89%   |
| 5.15.0-78-generic    | 7         | 1.89%   |
| 5.15.0-53-generic    | 7         | 1.89%   |
| 5.15.0-27-generic    | 7         | 1.89%   |
| 5.15.0-76-generic    | 6         | 1.62%   |
| 5.15.0-57-generic    | 6         | 1.62%   |
| 5.15.0-39-generic    | 6         | 1.62%   |
| 5.19.0-43-generic    | 5         | 1.35%   |
| 5.15.0-69-generic    | 5         | 1.35%   |
| 5.15.0-50-generic    | 5         | 1.35%   |
| 5.15.0-43-generic    | 5         | 1.35%   |
| 5.15.0-40-generic    | 5         | 1.35%   |
| 5.15.0-35-generic    | 5         | 1.35%   |
| 6.2.0-34-generic     | 4         | 1.08%   |
| 5.19.0-50-generic    | 4         | 1.08%   |
| 5.19.0-42-generic    | 4         | 1.08%   |
| 5.19.0-32-generic    | 4         | 1.08%   |
| 5.15.0-71-lowlatency | 4         | 1.08%   |
| 5.15.0-41-generic    | 4         | 1.08%   |
| 6.2.0-35-generic     | 3         | 0.81%   |
| 6.2.0-33-generic     | 3         | 0.81%   |
| 5.17.0-1020-oem      | 3         | 0.81%   |
| 5.15.0-79-generic    | 3         | 0.81%   |
| 5.15.0-70-generic    | 3         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.0   | 225       | 64.66%  |
| 5.19.0   | 58        | 16.67%  |
| 6.2.0    | 38        | 10.92%  |
| 5.17.0   | 9         | 2.59%   |
| 6.1.0    | 4         | 1.15%   |
| 6.0.0    | 2         | 0.57%   |
| 6.4.15   | 1         | 0.29%   |
| 6.4.0    | 1         | 0.29%   |
| 6.1.6    | 1         | 0.29%   |
| 6.0.9    | 1         | 0.29%   |
| 6.0.7    | 1         | 0.29%   |
| 5.4.0    | 1         | 0.29%   |
| 5.19.5   | 1         | 0.29%   |
| 5.19.17  | 1         | 0.29%   |
| 5.18.0   | 1         | 0.29%   |
| 5.17.3   | 1         | 0.29%   |
| 5.13.0   | 1         | 0.29%   |
| 4.19.241 | 1         | 0.29%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 225       | 64.66%  |
| 5.19    | 60        | 17.24%  |
| 6.2     | 38        | 10.92%  |
| 5.17    | 10        | 2.87%   |
| 6.1     | 5         | 1.44%   |
| 6.0     | 4         | 1.15%   |
| 6.4     | 2         | 0.57%   |
| 5.4     | 1         | 0.29%   |
| 5.18    | 1         | 0.29%   |
| 5.13    | 1         | 0.29%   |
| 4.19    | 1         | 0.29%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 342       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 334       | 97.66%  |
| GNOME | 8         | 2.34%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 329       | 96.2%   |
| Wayland | 8         | 2.34%   |
| Tty     | 5         | 1.46%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 301       | 88.01%  |
| GDM3    | 20        | 5.85%   |
| Unknown | 16        | 4.68%   |
| SDDM    | 3         | 0.88%   |
| SLiM    | 2         | 0.58%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 143       | 41.81%  |
| de_DE | 39        | 11.4%   |
| fr_FR | 37        | 10.82%  |
| it_IT | 21        | 6.14%   |
| en_GB | 18        | 5.26%   |
| pt_BR | 9         | 2.63%   |
| ru_RU | 8         | 2.34%   |
| es_ES | 7         | 2.05%   |
| en_CA | 7         | 2.05%   |
| pl_PL | 5         | 1.46%   |
| en_IN | 5         | 1.46%   |
| en_AU | 5         | 1.46%   |
| cs_CZ | 4         | 1.17%   |
| nl_NL | 3         | 0.88%   |
| hu_HU | 3         | 0.88%   |
| C     | 3         | 0.88%   |
| tr_TR | 2         | 0.58%   |
| ja_JP | 2         | 0.58%   |
| es_MX | 2         | 0.58%   |
| zh_TW | 1         | 0.29%   |
| zh_CN | 1         | 0.29%   |
| ru_UA | 1         | 0.29%   |
| ro_RO | 1         | 0.29%   |
| pt_PT | 1         | 0.29%   |
| nl_BE | 1         | 0.29%   |
| lt_LT | 1         | 0.29%   |
| fr_BE | 1         | 0.29%   |
| es_VE | 1         | 0.29%   |
| es_UY | 1         | 0.29%   |
| es_CO | 1         | 0.29%   |
| es_CL | 1         | 0.29%   |
| en_IL | 1         | 0.29%   |
| en_IE | 1         | 0.29%   |
| en_HK | 1         | 0.29%   |
| el_GR | 1         | 0.29%   |
| de_CH | 1         | 0.29%   |
| de_AT | 1         | 0.29%   |
| bg_BG | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 188       | 54.34%  |
| BIOS | 158       | 45.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 289       | 82.81%  |
| Tmpfs   | 32        | 9.17%   |
| Zfs     | 10        | 2.87%   |
| Overlay | 10        | 2.87%   |
| Btrfs   | 7         | 2.01%   |
| Xfs     | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 262       | 75.29%  |
| MBR     | 47        | 13.51%  |
| Unknown | 39        | 11.21%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 318       | 91.38%  |
| Yes       | 30        | 8.62%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 248       | 72.51%  |
| Yes       | 94        | 27.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 79        | 23.1%   |
| Hewlett-Packard     | 62        | 18.13%  |
| Dell                | 47        | 13.74%  |
| ASUSTek Computer    | 33        | 9.65%   |
| Acer                | 29        | 8.48%   |
| Google              | 13        | 3.8%    |
| Toshiba             | 8         | 2.34%   |
| Apple               | 7         | 2.05%   |
| Samsung Electronics | 6         | 1.75%   |
| MSI                 | 5         | 1.46%   |
| GPU Company         | 5         | 1.46%   |
| Sony                | 4         | 1.17%   |
| HUAWEI              | 4         | 1.17%   |
| Unknown             | 4         | 1.17%   |
| Notebook            | 2         | 0.58%   |
| Medion              | 2         | 0.58%   |
| HONOR               | 2         | 0.58%   |
| Gigabyte Technology | 2         | 0.58%   |
| Gateway             | 2         | 0.58%   |
| Fujitsu Siemens     | 2         | 0.58%   |
| Fujitsu             | 2         | 0.58%   |
| Chuwi               | 2         | 0.58%   |
| AMI                 | 2         | 0.58%   |
| Thomson             | 1         | 0.29%   |
| Tactus              | 1         | 0.29%   |
| Standard            | 1         | 0.29%   |
| SGIN                | 1         | 0.29%   |
| Schenker            | 1         | 0.29%   |
| Panasonic           | 1         | 0.29%   |
| Packard Bell        | 1         | 0.29%   |
| Olivetti            | 1         | 0.29%   |
| Mediacom            | 1         | 0.29%   |
| Itautec             | 1         | 0.29%   |
| HIGRADED            | 1         | 0.29%   |
| Getac               | 1         | 0.29%   |
| Fusion5             | 1         | 0.29%   |
| ECS                 | 1         | 0.29%   |
| Dynabook            | 1         | 0.29%   |
| Digma               | 1         | 0.29%   |
| Daten Tecnologia    | 1         | 0.29%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 5         | 1.46%   |
| HP EliteBook 840 G3                      | 4         | 1.17%   |
| Google Snappy                            | 4         | 1.17%   |
| HP Pavilion 17                           | 3         | 0.88%   |
| HP Laptop 15s-fq2xxx                     | 3         | 0.88%   |
| Lenovo ThinkPad P50 20EN0013US           | 2         | 0.58%   |
| Lenovo IdeaPad 5 15ABA7 82SG             | 2         | 0.58%   |
| HUAWEI BOHK-WAX9X                        | 2         | 0.58%   |
| HP Pavilion Notebook                     | 2         | 0.58%   |
| HP Pavilion g6                           | 2         | 0.58%   |
| HP Pavilion 15                           | 2         | 0.58%   |
| HP EliteBook 820 G3                      | 2         | 0.58%   |
| HP 255 G8 Notebook PC                    | 2         | 0.58%   |
| GPU Company GWTN116-3                    | 2         | 0.58%   |
| Google Auron_Yuna                        | 2         | 0.58%   |
| Dell XPS 13 9305                         | 2         | 0.58%   |
| Dell Latitude E5450                      | 2         | 0.58%   |
| Dell Latitude 5411                       | 2         | 0.58%   |
| ASUS ASUS TUF Gaming A15 FA507RE_FA507RE | 2         | 0.58%   |
| Apple MacBookPro8,1                      | 2         | 0.58%   |
| Apple MacBookPro7,1                      | 2         | 0.58%   |
| AMI Intel                                | 2         | 0.58%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.29%   |
| Toshiba Satellite Pro R50-B              | 1         | 0.29%   |
| Toshiba Satellite L750D                  | 1         | 0.29%   |
| Toshiba Satellite C650                   | 1         | 0.29%   |
| Toshiba Satellite C55D-B                 | 1         | 0.29%   |
| Toshiba Satellite C50D-A-10E             | 1         | 0.29%   |
| Toshiba PT10F                            | 1         | 0.29%   |
| Toshiba EQUIUM P200                      | 1         | 0.29%   |
| Thomson N15C8BK2T                        | 1         | 0.29%   |
| Tactus GeoBook 140                       | 1         | 0.29%   |
| Sony VPCS12V9E                           | 1         | 0.29%   |
| Sony VPCEH25EN                           | 1         | 0.29%   |
| Sony VPCEA3S1E                           | 1         | 0.29%   |
| Sony SVE1512C6EB                         | 1         | 0.29%   |
| SGIN M15                                 | 1         | 0.29%   |
| Schenker WORK (Early 2021)               | 1         | 0.29%   |
| Samsung RV410/RV510/S3510/E3510          | 1         | 0.29%   |
| Samsung N250P/N145P                      | 1         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 49        | 14.33%  |
| Acer Aspire              | 22        | 6.43%   |
| Dell Latitude            | 21        | 6.14%   |
| HP Pavilion              | 17        | 4.97%   |
| Lenovo IdeaPad           | 14        | 4.09%   |
| HP EliteBook             | 12        | 3.51%   |
| HP Laptop                | 9         | 2.63%   |
| Dell Inspiron            | 9         | 2.63%   |
| Dell XPS                 | 7         | 2.05%   |
| ASUS VivoBook            | 7         | 2.05%   |
| Toshiba Satellite        | 6         | 1.75%   |
| Unknown                  | 5         | 1.46%   |
| HP ProBook               | 4         | 1.17%   |
| Google Snappy            | 4         | 1.17%   |
| Dell Vostro              | 4         | 1.17%   |
| Dell Precision           | 4         | 1.17%   |
| ASUS ASUS                | 4         | 1.17%   |
| Lenovo ThinkBook         | 3         | 0.88%   |
| HP Stream                | 3         | 0.88%   |
| HP Compaq                | 3         | 0.88%   |
| HP 255                   | 3         | 0.88%   |
| HP 250                   | 3         | 0.88%   |
| ASUS ROG                 | 3         | 0.88%   |
| MSI GF63                 | 2         | 0.58%   |
| Lenovo V15               | 2         | 0.58%   |
| HUAWEI BOHK-WAX9X        | 2         | 0.58%   |
| GPU Company GWTN116-3    | 2         | 0.58%   |
| Google Auron             | 2         | 0.58%   |
| Fujitsu Siemens LIFEBOOK | 2         | 0.58%   |
| Fujitsu LIFEBOOK         | 2         | 0.58%   |
| ASUS ZenBook             | 2         | 0.58%   |
| Apple MacBookPro8        | 2         | 0.58%   |
| Apple MacBookPro7        | 2         | 0.58%   |
| AMI Intel                | 2         | 0.58%   |
| Acer Extensa             | 2         | 0.58%   |
| Toshiba PT10F            | 1         | 0.29%   |
| Toshiba EQUIUM           | 1         | 0.29%   |
| Thomson N15C8BK2T        | 1         | 0.29%   |
| Tactus GeoBook           | 1         | 0.29%   |
| Sony VPCS12V9E           | 1         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 41        | 11.99%  |
| 2020 | 36        | 10.53%  |
| 2022 | 28        | 8.19%   |
| 2015 | 24        | 7.02%   |
| 2011 | 22        | 6.43%   |
| 2016 | 20        | 5.85%   |
| 2014 | 20        | 5.85%   |
| 2013 | 20        | 5.85%   |
| 2019 | 18        | 5.26%   |
| 2017 | 18        | 5.26%   |
| 2012 | 18        | 5.26%   |
| 2010 | 16        | 4.68%   |
| 2009 | 15        | 4.39%   |
| 2018 | 14        | 4.09%   |
| 2008 | 11        | 3.22%   |
| 2007 | 9         | 2.63%   |
| 2023 | 8         | 2.34%   |
| 2006 | 4         | 1.17%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 342       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 312       | 90.43%  |
| Enabled  | 33        | 9.57%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 329       | 96.2%   |
| Yes  | 13        | 3.8%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 101       | 29.53%  |
| 4.01-8.0    | 100       | 29.24%  |
| 8.01-16.0   | 47        | 13.74%  |
| 16.01-24.0  | 39        | 11.4%   |
| 32.01-64.0  | 20        | 5.85%   |
| 1.01-2.0    | 14        | 4.09%   |
| 64.01-256.0 | 9         | 2.63%   |
| 2.01-3.0    | 6         | 1.75%   |
| 24.01-32.0  | 5         | 1.46%   |
| 0.51-1.0    | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 150       | 42.02%  |
| 2.01-3.0   | 99        | 27.73%  |
| 4.01-8.0   | 33        | 9.24%   |
| 3.01-4.0   | 31        | 8.68%   |
| 0.51-1.0   | 27        | 7.56%   |
| 8.01-16.0  | 13        | 3.64%   |
| 16.01-24.0 | 3         | 0.84%   |
| 24.01-32.0 | 1         | 0.28%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 272       | 79.53%  |
| 2      | 61        | 17.84%  |
| 3      | 5         | 1.46%   |
| 4      | 2         | 0.58%   |
| 0      | 2         | 0.58%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 221       | 64.62%  |
| Yes       | 121       | 35.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 260       | 76.02%  |
| No        | 82        | 23.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 338       | 98.83%  |
| No        | 4         | 1.17%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 269       | 78.65%  |
| No        | 73        | 21.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 52        | 15.16%  |
| Germany      | 48        | 13.99%  |
| France       | 43        | 12.54%  |
| Italy        | 23        | 6.71%   |
| UK           | 17        | 4.96%   |
| Brazil       | 13        | 3.79%   |
| Russia       | 11        | 3.21%   |
| Poland       | 10        | 2.92%   |
| Czechia      | 9         | 2.62%   |
| Netherlands  | 8         | 2.33%   |
| India        | 8         | 2.33%   |
| Spain        | 7         | 2.04%   |
| Canada       | 7         | 2.04%   |
| Sweden       | 6         | 1.75%   |
| Mexico       | 6         | 1.75%   |
| Australia    | 5         | 1.46%   |
| Austria      | 4         | 1.17%   |
| Vietnam      | 3         | 0.87%   |
| Switzerland  | 3         | 0.87%   |
| Malaysia     | 3         | 0.87%   |
| Japan        | 3         | 0.87%   |
| Israel       | 3         | 0.87%   |
| Iran         | 3         | 0.87%   |
| Hungary      | 3         | 0.87%   |
| Greece       | 3         | 0.87%   |
| Denmark      | 3         | 0.87%   |
| Belgium      | 3         | 0.87%   |
| Belarus      | 3         | 0.87%   |
| Venezuela    | 2         | 0.58%   |
| Turkey       | 2         | 0.58%   |
| South Korea  | 2         | 0.58%   |
| Indonesia    | 2         | 0.58%   |
| Cuba         | 2         | 0.58%   |
| Colombia     | 2         | 0.58%   |
| Argentina    | 2         | 0.58%   |
| Uruguay      | 1         | 0.29%   |
| Ukraine      | 1         | 0.29%   |
| Slovenia     | 1         | 0.29%   |
| Sint Maarten | 1         | 0.29%   |
| Romania      | 1         | 0.29%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Warsaw           | 6         | 1.7%    |
| Paris            | 5         | 1.42%   |
| Munich           | 5         | 1.42%   |
| Prague           | 4         | 1.14%   |
| Milan            | 4         | 1.14%   |
| Melbourne        | 4         | 1.14%   |
| Uppsala          | 3         | 0.85%   |
| St Petersburg    | 3         | 0.85%   |
| North Hills      | 3         | 0.85%   |
| Moscow           | 3         | 0.85%   |
| Kuala Lumpur     | 3         | 0.85%   |
| Hamburg          | 3         | 0.85%   |
| Copenhagen       | 3         | 0.85%   |
| Bordeaux         | 3         | 0.85%   |
| Athens           | 3         | 0.85%   |
| York             | 2         | 0.57%   |
| Stuttgart        | 2         | 0.57%   |
| Springfield      | 2         | 0.57%   |
| Rome             | 2         | 0.57%   |
| Rochester        | 2         | 0.57%   |
| Rho              | 2         | 0.57%   |
| Puebla City      | 2         | 0.57%   |
| Palmyra          | 2         | 0.57%   |
| Oklahoma City    | 2         | 0.57%   |
| Oberhausen       | 2         | 0.57%   |
| Nykvarn          | 2         | 0.57%   |
| Mumbai           | 2         | 0.57%   |
| Minsk            | 2         | 0.57%   |
| Mexico City      | 2         | 0.57%   |
| London           | 2         | 0.57%   |
| Lincoln          | 2         | 0.57%   |
| Leipzig          | 2         | 0.57%   |
| Juiz de Fora     | 2         | 0.57%   |
| Indianapolis     | 2         | 0.57%   |
| Ho Chi Minh City | 2         | 0.57%   |
| Havana           | 2         | 0.57%   |
| Hanover          | 2         | 0.57%   |
| Farmington       | 2         | 0.57%   |
| Budapest         | 2         | 0.57%   |
| Brest            | 2         | 0.57%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 68        | 74     | 17.26%  |
| WDC                         | 39        | 45     | 9.9%    |
| Unknown                     | 38        | 47     | 9.64%   |
| Seagate                     | 35        | 41     | 8.88%   |
| Kingston                    | 22        | 24     | 5.58%   |
| SanDisk                     | 21        | 24     | 5.33%   |
| SK hynix                    | 20        | 25     | 5.08%   |
| Hitachi                     | 15        | 15     | 3.81%   |
| Toshiba                     | 13        | 13     | 3.3%    |
| Intel                       | 11        | 12     | 2.79%   |
| Crucial                     | 11        | 11     | 2.79%   |
| Micron Technology           | 10        | 13     | 2.54%   |
| HGST                        | 7         | 8      | 1.78%   |
| A-DATA Technology           | 7         | 12     | 1.78%   |
| SPCC                        | 5         | 5      | 1.27%   |
| PNY                         | 5         | 5      | 1.27%   |
| Phison                      | 5         | 5      | 1.27%   |
| Fujitsu                     | 4         | 4      | 1.02%   |
| China                       | 4         | 5      | 1.02%   |
| Transcend                   | 3         | 4      | 0.76%   |
| Netac                       | 3         | 3      | 0.76%   |
| LITEON                      | 3         | 3      | 0.76%   |
| KIOXIA                      | 3         | 3      | 0.76%   |
| Kingston Technology Company | 3         | 4      | 0.76%   |
| Unknown                     | 3         | 3      | 0.76%   |
| TO Exter                    | 2         | 2      | 0.51%   |
| Silicon Motion              | 2         | 2      | 0.51%   |
| Lenovo                      | 2         | 2      | 0.51%   |
| FORESEE                     | 2         | 5      | 0.51%   |
| Apple                       | 2         | 4      | 0.51%   |
| Apacer                      | 2         | 2      | 0.51%   |
| XrayDisk                    | 1         | 1      | 0.25%   |
| USB3.0                      | 1         | 2      | 0.25%   |
| UMIS                        | 1         | 1      | 0.25%   |
| Team                        | 1         | 4      | 0.25%   |
| SSSTC                       | 1         | 1      | 0.25%   |
| SSD0240S                    | 1         | 1      | 0.25%   |
| ShiJi                       | 1         | 2      | 0.25%   |
| Realtek Semiconductor       | 1         | 2      | 0.25%   |
| Realtek                     | 1         | 1      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                          | 6         | 1.48%   |
| Seagate ST500LT012-1DG142 500GB                 | 5         | 1.23%   |
| Seagate ST1000LM048-2E7172 1TB                  | 4         | 0.99%   |
| Unknown SD/MMC/MS PRO 16GB                      | 3         | 0.74%   |
| Unknown MMC Card  128GB                         | 3         | 0.74%   |
| Toshiba MQ04ABF100 1TB                          | 3         | 0.74%   |
| Toshiba MQ01ABF050 500GB                        | 3         | 0.74%   |
| Seagate ST1000LM024 HN-M101MBB 1TB              | 3         | 0.74%   |
| Samsung SSD 870 QVO 4TB                         | 3         | 0.74%   |
| Samsung SSD 860 EVO 500GB                       | 3         | 0.74%   |
| Samsung SSD 850 EVO 500GB                       | 3         | 0.74%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB          | 3         | 0.74%   |
| Kingston SA400S37480G 480GB SSD                 | 3         | 0.74%   |
| Intel SSDPEKNU512GZ 512GB                       | 3         | 0.74%   |
| HGST HTS541010A9E680 1TB                        | 3         | 0.74%   |
| Unknown                                         | 3         | 0.74%   |
| WDC WDS250G2B0A 250GB SSD                       | 2         | 0.49%   |
| WDC WD3200BEVT-22ZCT0 320GB                     | 2         | 0.49%   |
| WDC WD10JPCX-24UE4T0 1TB                        | 2         | 0.49%   |
| WDC PC SN530 SDBPNPZ-512G-1036 512GB            | 2         | 0.49%   |
| Unknown SA08G  8GB                              | 2         | 0.49%   |
| Unknown MMC64G  64GB                            | 2         | 0.49%   |
| Unknown DF4016  16GB                            | 2         | 0.49%   |
| TO Exter nal USB 3.0 2TB                        | 2         | 0.49%   |
| SPCC Solid State Disk 512GB                     | 2         | 0.49%   |
| Seagate ST500LT012-9WS142 500GB                 | 2         | 0.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB             | 2         | 0.49%   |
| Seagate ST500LM000-1EJ162 500GB                 | 2         | 0.49%   |
| Seagate ST1000LM035-1RK172 1TB                  | 2         | 0.49%   |
| Seagate ST1000LM014-1EJ164 1TB                  | 2         | 0.49%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB | 2         | 0.49%   |
| SanDisk DF4032  32GB                            | 2         | 0.49%   |
| Samsung SSD 980 PRO 2TB                         | 2         | 0.49%   |
| Samsung SSD 980 500GB                           | 2         | 0.49%   |
| Samsung SSD 870 EVO 500GB                       | 2         | 0.49%   |
| Samsung SSD 850 EVO 250GB                       | 2         | 0.49%   |
| Samsung MZALQ512HALU-000L2 512GB                | 2         | 0.49%   |
| PNY CS900 120GB SSD                             | 2         | 0.49%   |
| Phison 311CD0512GB                              | 2         | 0.49%   |
| Micron MTFDKCD512TFK 512GB                      | 2         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 41     | 34.31%  |
| WDC                 | 23        | 28     | 22.55%  |
| Hitachi             | 15        | 15     | 14.71%  |
| Toshiba             | 12        | 12     | 11.76%  |
| HGST                | 7         | 8      | 6.86%   |
| Fujitsu             | 4         | 4      | 3.92%   |
| Unknown             | 3         | 4      | 2.94%   |
| Samsung Electronics | 2         | 2      | 1.96%   |
| USB3.0              | 1         | 2      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 36     | 23.13%  |
| Kingston            | 18        | 19     | 13.43%  |
| SanDisk             | 11        | 14     | 8.21%   |
| Crucial             | 9         | 9      | 6.72%   |
| A-DATA Technology   | 7         | 12     | 5.22%   |
| WDC                 | 6         | 6      | 4.48%   |
| SPCC                | 5         | 5      | 3.73%   |
| PNY                 | 5         | 5      | 3.73%   |
| Micron Technology   | 5         | 6      | 3.73%   |
| China               | 4         | 5      | 2.99%   |
| Transcend           | 3         | 3      | 2.24%   |
| LITEON              | 3         | 3      | 2.24%   |
| TO Exter            | 2         | 2      | 1.49%   |
| SK hynix            | 2         | 2      | 1.49%   |
| Netac               | 2         | 2      | 1.49%   |
| Intel               | 2         | 2      | 1.49%   |
| FORESEE             | 2         | 5      | 1.49%   |
| Apacer              | 2         | 2      | 1.49%   |
| Team                | 1         | 4      | 0.75%   |
| SSSTC               | 1         | 1      | 0.75%   |
| ShiJi               | 1         | 1      | 0.75%   |
| Patriot             | 1         | 1      | 0.75%   |
| LITEONIT            | 1         | 1      | 0.75%   |
| KingSpec            | 1         | 1      | 0.75%   |
| KingDian            | 1         | 1      | 0.75%   |
| Kimtigo             | 1         | 1      | 0.75%   |
| Intenso             | 1         | 1      | 0.75%   |
| INNOVATION IT       | 1         | 1      | 0.75%   |
| EVM                 | 1         | 1      | 0.75%   |
| BHT                 | 1         | 1      | 0.75%   |
| ASMT                | 1         | 4      | 0.75%   |
| addlink             | 1         | 1      | 0.75%   |
| Unknown             | 1         | 1      | 0.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 123       | 159    | 32.2%   |
| NVMe    | 116       | 130    | 30.37%  |
| HDD     | 99        | 116    | 25.92%  |
| MMC     | 40        | 49     | 10.47%  |
| Unknown | 4         | 4      | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 209       | 260    | 55.15%  |
| NVMe | 114       | 128    | 30.08%  |
| MMC  | 40        | 49     | 10.55%  |
| SAS  | 16        | 21     | 4.22%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 161       | 189    | 70%     |
| 0.51-1.0   | 55        | 70     | 23.91%  |
| 1.01-2.0   | 11        | 13     | 4.78%   |
| 3.01-4.0   | 3         | 3      | 1.3%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 104       | 29.89%  |
| 251-500        | 102       | 29.31%  |
| 501-1000       | 43        | 12.36%  |
| 51-100         | 29        | 8.33%   |
| 1-20           | 24        | 6.9%    |
| 21-50          | 20        | 5.75%   |
| 1001-2000      | 15        | 4.31%   |
| More than 3000 | 8         | 2.3%    |
| 2001-3000      | 2         | 0.57%   |
| Unknown        | 1         | 0.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 134       | 37.54%  |
| 21-50          | 78        | 21.85%  |
| 101-250        | 56        | 15.69%  |
| 51-100         | 46        | 12.89%  |
| 251-500        | 18        | 5.04%   |
| 501-1000       | 16        | 4.48%   |
| 1001-2000      | 6         | 1.68%   |
| More than 3000 | 1         | 0.28%   |
| 2001-3000      | 1         | 0.28%   |
| Unknown        | 1         | 0.28%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB                  | 2         | 2      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 2      | 4.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 2         | 2      | 4.76%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                 | 1         | 1      | 2.38%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 2.38%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 2.38%   |
| Toshiba MK1246GSX 120GB                          | 1         | 1      | 2.38%   |
| SSSTC CVB-8D128-HP 128GB                         | 1         | 1      | 2.38%   |
| Seagate ST9500325ASG 500GB                       | 1         | 1      | 2.38%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 2.38%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 2.38%   |
| Seagate ST1000LM 035-1RK172 1TB                  | 1         | 1      | 2.38%   |
| SanDisk SSD PLUS 480GB                           | 1         | 1      | 2.38%   |
| SanDisk SSD PLUS 240GB                           | 1         | 1      | 2.38%   |
| Samsung Electronics SSD PM810 FDE 2.5 128GB      | 1         | 1      | 2.38%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD | 1         | 1      | 2.38%   |
| Samsung Electronics HM160HC 160GB                | 1         | 1      | 2.38%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD   | 1         | 1      | 2.38%   |
| LITEON LCH-512V2S 512GB SSD                      | 1         | 1      | 2.38%   |
| LITEON CV8-8E128-HP 128GB SSD                    | 1         | 1      | 2.38%   |
| Kingston SNS4151S332GD 32GB SSD                  | 1         | 2      | 2.38%   |
| Kingston SNS4151S316GD 16GB SSD                  | 1         | 1      | 2.38%   |
| Kingston OM8S1S3128K-AH 128GB SSD                | 1         | 1      | 2.38%   |
| JMicron Technology Generic 256GB                 | 1         | 1      | 2.38%   |
| Intel SSDSCKKF240H6L 240GB                       | 1         | 1      | 2.38%   |
| Hitachi HTS725050A9A364 500GB                    | 1         | 1      | 2.38%   |
| Hitachi HTS545032A7E380 320GB                    | 1         | 1      | 2.38%   |
| Hitachi HTS545025B9SA02 250GB                    | 1         | 1      | 2.38%   |
| Hitachi HTS543216L9A300 160GB                    | 1         | 1      | 2.38%   |
| Hitachi HTS543212L9A300 120GB                    | 1         | 1      | 2.38%   |
| Hitachi HTS541680J9SA00 80GB                     | 1         | 1      | 2.38%   |
| Hitachi HTS541080G9SA00 80GB                     | 1         | 1      | 2.38%   |
| HGST HTS725050A7E630 500GB                       | 1         | 1      | 2.38%   |
| HGST HTS541010A9E680 1TB                         | 1         | 1      | 2.38%   |
| Fujitsu MHZ2250BH G2 250GB                       | 1         | 1      | 2.38%   |
| Fujitsu MHZ2160BJ FFS G2 160GB                   | 1         | 1      | 2.38%   |
| Fujitsu MHY2160BH 160GB                          | 1         | 1      | 2.38%   |
| Fujitsu MHW2060BH 64GB                           | 1         | 1      | 2.38%   |
| Unknown                                          | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 23.81%  |
| Hitachi             | 7         | 7      | 16.67%  |
| Fujitsu             | 4         | 4      | 9.52%   |
| Samsung Electronics | 3         | 3      | 7.14%   |
| Kingston            | 3         | 4      | 7.14%   |
| WDC                 | 2         | 2      | 4.76%   |
| Toshiba             | 2         | 2      | 4.76%   |
| SanDisk             | 2         | 2      | 4.76%   |
| LITEON              | 2         | 2      | 4.76%   |
| HGST                | 2         | 2      | 4.76%   |
| SSSTC               | 1         | 1      | 2.38%   |
| Micron Technology   | 1         | 1      | 2.38%   |
| JMicron Technology  | 1         | 1      | 2.38%   |
| Intel               | 1         | 1      | 2.38%   |
| Unknown             | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 37.04%  |
| Hitachi             | 7         | 7      | 25.93%  |
| Fujitsu             | 4         | 4      | 14.81%  |
| Toshiba             | 2         | 2      | 7.41%   |
| HGST                | 2         | 2      | 7.41%   |
| WDC                 | 1         | 1      | 3.7%    |
| Samsung Electronics | 1         | 1      | 3.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 27     | 64.29%  |
| SSD  | 14        | 15     | 33.33%  |
| NVMe | 1         | 1      | 2.38%   |

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
| Works    | 183       | 210    | 50.14%  |
| Detected | 141       | 205    | 38.63%  |
| Malfunc  | 41        | 43     | 11.23%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 223       | 58.38%  |
| AMD                          | 50        | 13.09%  |
| Samsung Electronics          | 36        | 9.42%   |
| SanDisk                      | 18        | 4.71%   |
| SK hynix                     | 17        | 4.45%   |
| Kingston Technology Company  | 8         | 2.09%   |
| Phison Electronics           | 5         | 1.31%   |
| Micron Technology            | 4         | 1.05%   |
| Silicon Motion               | 3         | 0.79%   |
| Nvidia                       | 3         | 0.79%   |
| Micron/Crucial Technology    | 3         | 0.79%   |
| KIOXIA                       | 3         | 0.79%   |
| Lenovo                       | 2         | 0.52%   |
| Apple                        | 2         | 0.52%   |
| Union Memory (Shenzhen)      | 1         | 0.26%   |
| Toshiba America Info Systems | 1         | 0.26%   |
| Realtek Semiconductor        | 1         | 0.26%   |
| Netac Technology             | 1         | 0.26%   |
| Hosin Global Electronics     | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 44        | 10.76%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 24        | 5.87%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 19        | 4.65%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 16        | 3.91%   |
| Intel Volume Management Device NVMe RAID Controller                              | 15        | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 14        | 3.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 13        | 3.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 13        | 3.18%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 12        | 2.93%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 10        | 2.44%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 8         | 1.96%   |
| Intel Tiger Lake-LP SATA Controller                                              | 8         | 1.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 8         | 1.96%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 1.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 1.71%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 6         | 1.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 1.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 1.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 1.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 1.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 5         | 1.22%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 1.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 5         | 1.22%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 5         | 1.22%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 4         | 0.98%   |
| Intel SSD 660P Series                                                            | 4         | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.98%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.98%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 0.98%   |
| SK hynix PC611 NVMe Solid State Drive                                            | 3         | 0.73%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 3         | 0.73%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 3         | 0.73%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 3         | 0.73%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 3         | 0.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 3         | 0.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 3         | 0.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 3         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 243       | 60.3%   |
| NVMe | 114       | 28.29%  |
| RAID | 25        | 6.2%    |
| IDE  | 21        | 5.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 271       | 79.24%  |
| AMD    | 71        | 20.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 9         | 2.63%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 8         | 2.34%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 7         | 2.05%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 7         | 2.05%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 6         | 1.75%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 1.75%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 5         | 1.46%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 5         | 1.46%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 5         | 1.46%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 1.17%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 1.17%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 1.17%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 4         | 1.17%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 1.17%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 4         | 1.17%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 4         | 1.17%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 1.17%   |
| Intel 12th Gen Core i7-1260P                | 4         | 1.17%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 4         | 1.17%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 0.88%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 3         | 0.88%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 0.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 0.88%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz        | 3         | 0.88%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 3         | 0.88%   |
| Intel Celeron 3205U @ 1.50GHz               | 3         | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 3         | 0.88%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 3         | 0.88%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics  | 3         | 0.88%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 3         | 0.88%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 2         | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 2         | 0.58%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.58%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 2         | 0.58%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 0.58%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 2         | 0.58%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 2         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 71        | 20.76%  |
| Intel Celeron           | 49        | 14.33%  |
| Other                   | 38        | 11.11%  |
| Intel Core i7           | 38        | 11.11%  |
| Intel Core i3           | 24        | 7.02%   |
| Intel Core 2 Duo        | 18        | 5.26%   |
| AMD Ryzen 5             | 15        | 4.39%   |
| AMD Ryzen 7             | 14        | 4.09%   |
| AMD A4                  | 7         | 2.05%   |
| Intel Core 2            | 6         | 1.75%   |
| Intel Atom              | 6         | 1.75%   |
| AMD A6                  | 6         | 1.75%   |
| Intel Pentium           | 5         | 1.46%   |
| AMD A8                  | 5         | 1.46%   |
| Intel Pentium Dual-Core | 3         | 0.88%   |
| Intel Pentium Dual      | 3         | 0.88%   |
| Intel Genuine           | 3         | 0.88%   |
| AMD Ryzen 9             | 3         | 0.88%   |
| AMD Ryzen 5 PRO         | 3         | 0.88%   |
| AMD Ryzen 3             | 3         | 0.88%   |
| AMD E1                  | 3         | 0.88%   |
| Intel Pentium Silver    | 2         | 0.58%   |
| AMD Ryzen 7 PRO         | 2         | 0.58%   |
| AMD E2                  | 2         | 0.58%   |
| AMD A10                 | 2         | 0.58%   |
| Intel Xeon              | 1         | 0.29%   |
| Intel Core m3           | 1         | 0.29%   |
| Intel Core M            | 1         | 0.29%   |
| Intel Core i9           | 1         | 0.29%   |
| Intel Core 2 Extreme    | 1         | 0.29%   |
| Intel Celeron Dual-Core | 1         | 0.29%   |
| AMD V120                | 1         | 0.29%   |
| AMD FX                  | 1         | 0.29%   |
| AMD E                   | 1         | 0.29%   |
| AMD Athlon II           | 1         | 0.29%   |
| AMD Athlon              | 1         | 0.29%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 192       | 56.14%  |
| 4      | 88        | 25.73%  |
| 6      | 24        | 7.02%   |
| 8      | 21        | 6.14%   |
| 10     | 6         | 1.75%   |
| 12     | 5         | 1.46%   |
| 1      | 5         | 1.46%   |
| 16     | 1         | 0.29%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 342       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 219       | 64.04%  |
| 1      | 123       | 35.96%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 342       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 133       | 38.11%  |
| 0x806c1    | 18        | 5.16%   |
| 0x406e3    | 12        | 3.44%   |
| 0x08608103 | 9         | 2.58%   |
| 0x706a8    | 8         | 2.29%   |
| 0x306d4    | 8         | 2.29%   |
| 0x1067a    | 8         | 2.29%   |
| 0x306a9    | 7         | 2.01%   |
| 0x20655    | 7         | 2.01%   |
| 0x806ec    | 6         | 1.72%   |
| 0x506c9    | 6         | 1.72%   |
| 0x30678    | 6         | 1.72%   |
| 0x806ea    | 5         | 1.43%   |
| 0x6fd      | 5         | 1.43%   |
| 0x406c4    | 5         | 1.43%   |
| 0x206a7    | 5         | 1.43%   |
| 0x07030105 | 5         | 1.43%   |
| 0xa0652    | 4         | 1.15%   |
| 0x906ea    | 4         | 1.15%   |
| 0x806e9    | 4         | 1.15%   |
| 0x6f6      | 4         | 1.15%   |
| 0x406c3    | 4         | 1.15%   |
| 0x40651    | 4         | 1.15%   |
| 0x06006705 | 4         | 1.15%   |
| 0x906a3    | 3         | 0.86%   |
| 0x806d1    | 3         | 0.86%   |
| 0x6fb      | 3         | 0.86%   |
| 0x506e3    | 3         | 0.86%   |
| 0x10676    | 3         | 0.86%   |
| 0x0a50000c | 3         | 0.86%   |
| 0x08108109 | 3         | 0.86%   |
| 0x05000119 | 3         | 0.86%   |
| 0x906a4    | 2         | 0.57%   |
| 0x706a1    | 2         | 0.57%   |
| 0x506ca    | 2         | 0.57%   |
| 0x306c3    | 2         | 0.57%   |
| 0x20652    | 2         | 0.57%   |
| 0x0a50000d | 2         | 0.57%   |
| 0x08a00006 | 2         | 0.57%   |
| 0x08608102 | 2         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 10.2%   |
| Unknown          | 25        | 7.29%   |
| Skylake          | 23        | 6.71%   |
| TigerLake        | 22        | 6.41%   |
| Silvermont       | 22        | 6.41%   |
| Penryn           | 21        | 6.12%   |
| SandyBridge      | 18        | 5.25%   |
| IvyBridge        | 16        | 4.66%   |
| Westmere         | 15        | 4.37%   |
| Haswell          | 15        | 4.37%   |
| Core             | 15        | 4.37%   |
| Broadwell        | 15        | 4.37%   |
| Goldmont plus    | 14        | 4.08%   |
| Goldmont         | 10        | 2.92%   |
| Zen 3            | 9         | 2.62%   |
| Puma             | 8         | 2.33%   |
| Zen 2            | 7         | 2.04%   |
| Excavator        | 7         | 2.04%   |
| CometLake        | 7         | 2.04%   |
| Alderlake Hybrid | 7         | 2.04%   |
| Zen+             | 6         | 1.75%   |
| Icelake          | 6         | 1.75%   |
| Bobcat           | 4         | 1.17%   |
| K10 Llano        | 3         | 0.87%   |
| Bonnell          | 3         | 0.87%   |
| Steamroller      | 2         | 0.58%   |
| Piledriver       | 2         | 0.58%   |
| K10              | 2         | 0.58%   |
| Jaguar           | 2         | 0.58%   |
| Tremont          | 1         | 0.29%   |
| Nehalem          | 1         | 0.29%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 247       | 61.75%  |
| AMD    | 82        | 20.5%   |
| Nvidia | 71        | 17.75%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 18        | 4.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 17        | 4.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 4.09%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 16        | 3.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 3.85%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 12        | 2.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 2.88%   |
| AMD Lucienne                                                                             | 12        | 2.88%   |
| Intel HD Graphics 5500                                                                   | 11        | 2.64%   |
| Intel HD Graphics 500                                                                    | 10        | 2.4%    |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.16%   |
| Intel HD Graphics 620                                                                    | 8         | 1.92%   |
| Intel UHD Graphics 620                                                                   | 7         | 1.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 1.68%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 7         | 1.68%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.44%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.44%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.2%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.2%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 5         | 1.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.2%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.2%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.2%    |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 1.2%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 0.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 0.96%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 4         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 4         | 0.96%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 4         | 0.96%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 0.96%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 4         | 0.96%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 4         | 0.96%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.72%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 0.72%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.72%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 0.72%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 195       | 57.02%  |
| 1 x AMD        | 59        | 17.25%  |
| Intel + Nvidia | 42        | 12.28%  |
| 1 x Nvidia     | 19        | 5.56%   |
| AMD + Nvidia   | 10        | 2.92%   |
| 2 x AMD        | 7         | 2.05%   |
| Intel + AMD    | 6         | 1.75%   |
| Other          | 4         | 1.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 307       | 88.99%  |
| Proprietary | 32        | 9.28%   |
| Unknown     | 6         | 1.74%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 254       | 73.84%  |
| 0.01-0.5   | 47        | 13.66%  |
| 0.51-1.0   | 17        | 4.94%   |
| 1.01-2.0   | 14        | 4.07%   |
| 3.01-4.0   | 9         | 2.62%   |
| 7.01-8.0   | 1         | 0.29%   |
| 5.01-6.0   | 1         | 0.29%   |
| 8.01-16.0  | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 83        | 22.02%  |
| LG Display              | 61        | 16.18%  |
| BOE                     | 58        | 15.38%  |
| Chimei Innolux          | 44        | 11.67%  |
| Samsung Electronics     | 31        | 8.22%   |
| Dell                    | 14        | 3.71%   |
| Chi Mei Optoelectronics | 8         | 2.12%   |
| PANDA                   | 7         | 1.86%   |
| Lenovo                  | 7         | 1.86%   |
| Goldstar                | 6         | 1.59%   |
| Apple                   | 6         | 1.59%   |
| Sharp                   | 5         | 1.33%   |
| LG Philips              | 5         | 1.33%   |
| InfoVision              | 5         | 1.33%   |
| Philips                 | 4         | 1.06%   |
| BenQ                    | 3         | 0.8%    |
| Vizio                   | 2         | 0.53%   |
| ViewSonic               | 2         | 0.53%   |
| Sony                    | 2         | 0.53%   |
| KDC                     | 2         | 0.53%   |
| Iiyama                  | 2         | 0.53%   |
| Hewlett-Packard         | 2         | 0.53%   |
| CSO                     | 2         | 0.53%   |
| Acer                    | 2         | 0.53%   |
| Toshiba                 | 1         | 0.27%   |
| TMX                     | 1         | 0.27%   |
| Sceptre Tech            | 1         | 0.27%   |
| SANSUI                  | 1         | 0.27%   |
| SAC                     | 1         | 0.27%   |
| Quanta Display          | 1         | 0.27%   |
| Panasonic               | 1         | 0.27%   |
| Olevia                  | 1         | 0.27%   |
| IBM                     | 1         | 0.27%   |
| HannStar                | 1         | 0.27%   |
| GreenWood               | 1         | 0.27%   |
| CPT                     | 1         | 0.27%   |
| AOC                     | 1         | 0.27%   |
| ADI                     | 1         | 0.27%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 1.06%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 1.06%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.06%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.79%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.79%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.79%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.79%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 3         | 0.79%   |
| Sony Nvidia Defaul t Flat Panel SNY05FA 1366x768 309x174mm 14.0-inch     | 2         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.53%   |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 2         | 0.53%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch             | 2         | 0.53%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 2         | 0.53%   |
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 0.53%   |
| LG Display LCD Monitor LGD045E 1366x768 309x174mm 14.0-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.53%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.53%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch              | 2         | 0.53%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 2         | 0.53%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.53%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch         | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x194mm 15.5-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch         | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 2         | 0.53%   |
| BOE LCD Monitor BOE092E 1920x1080 310x173mm 14.0-inch                    | 2         | 0.53%   |
| BOE LCD Monitor BOE08C2 1920x1080 344x194mm 15.5-inch                    | 2         | 0.53%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.53%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 2         | 0.53%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.53%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO229E 1600x900 382x214mm 17.2-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO219E 1600x900 382x214mm 17.2-inch            | 2         | 0.53%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 145       | 40.62%  |
| 1366x768 (WXGA)    | 112       | 31.37%  |
| 1600x900 (HD+)     | 25        | 7%      |
| 1280x800 (WXGA)    | 18        | 5.04%   |
| 3840x2160 (4K)     | 11        | 3.08%   |
| 1920x1200 (WUXGA)  | 11        | 3.08%   |
| 1440x900 (WXGA+)   | 7         | 1.96%   |
| 2560x1440 (QHD)    | 5         | 1.4%    |
| 1680x1050 (WSXGA+) | 3         | 0.84%   |
| 1024x600           | 3         | 0.84%   |
| 2560x1600          | 2         | 0.56%   |
| 2160x1440          | 2         | 0.56%   |
| 1024x768 (XGA)     | 2         | 0.56%   |
| 3840x2400          | 1         | 0.28%   |
| 3840x1600          | 1         | 0.28%   |
| 3440x1440          | 1         | 0.28%   |
| 2880x1800          | 1         | 0.28%   |
| 2560x1080          | 1         | 0.28%   |
| 2304x1440          | 1         | 0.28%   |
| 2240x1400          | 1         | 0.28%   |
| 1920x515           | 1         | 0.28%   |
| 1366x912           | 1         | 0.28%   |
| 1360x768           | 1         | 0.28%   |
| 1280x1024 (SXGA)   | 1         | 0.28%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 150       | 39.79%  |
| 14      | 62        | 16.45%  |
| 13      | 48        | 12.73%  |
| 17      | 29        | 7.69%   |
| 12      | 14        | 3.71%   |
| 11      | 13        | 3.45%   |
| 27      | 12        | 3.18%   |
| 24      | 9         | 2.39%   |
| 23      | 8         | 2.12%   |
| 21      | 6         | 1.59%   |
| 16      | 6         | 1.59%   |
| Unknown | 4         | 1.06%   |
| 10      | 3         | 0.8%    |
| 34      | 2         | 0.53%   |
| 31      | 2         | 0.53%   |
| 18      | 2         | 0.53%   |
| 86      | 1         | 0.27%   |
| 42      | 1         | 0.27%   |
| 37      | 1         | 0.27%   |
| 32      | 1         | 0.27%   |
| 26      | 1         | 0.27%   |
| 20      | 1         | 0.27%   |
| 19      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 240       | 64.17%  |
| 201-300     | 51        | 13.64%  |
| 351-400     | 32        | 8.56%   |
| 501-600     | 27        | 7.22%   |
| 401-500     | 10        | 2.67%   |
| 601-700     | 4         | 1.07%   |
| Unknown     | 4         | 1.07%   |
| 701-800     | 3         | 0.8%    |
| 801-900     | 1         | 0.27%   |
| 1001-1500   | 1         | 0.27%   |
| 901-1000    | 1         | 0.27%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 286       | 83.38%  |
| 16/10   | 43        | 12.54%  |
| 3/2     | 5         | 1.46%   |
| 21/9    | 3         | 0.87%   |
| 4/3     | 2         | 0.58%   |
| 6/5     | 1         | 0.29%   |
| 3.73    | 1         | 0.29%   |
| 0.56    | 1         | 0.29%   |
| Unknown | 1         | 0.29%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 149       | 39.63%  |
| 81-90          | 94        | 25%     |
| 121-130        | 23        | 6.12%   |
| 201-250        | 20        | 5.32%   |
| 71-80          | 16        | 4.26%   |
| 61-70          | 13        | 3.46%   |
| 51-60          | 13        | 3.46%   |
| 301-350        | 12        | 3.19%   |
| 131-140        | 7         | 1.86%   |
| 351-500        | 5         | 1.33%   |
| 151-200        | 5         | 1.33%   |
| 111-120        | 4         | 1.06%   |
| Unknown        | 4         | 1.06%   |
| 41-50          | 3         | 0.8%    |
| 251-300        | 2         | 0.53%   |
| 501-1000       | 2         | 0.53%   |
| 91-100         | 2         | 0.53%   |
| More than 1000 | 1         | 0.27%   |
| 141-150        | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 161       | 43.51%  |
| 101-120       | 123       | 33.24%  |
| 51-100        | 52        | 14.05%  |
| 161-240       | 25        | 6.76%   |
| More than 240 | 4         | 1.08%   |
| Unknown       | 4         | 1.08%   |
| 1-50          | 1         | 0.27%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 290       | 84.3%   |
| 2     | 45        | 13.08%  |
| 0     | 5         | 1.45%   |
| 3     | 4         | 1.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 181       | 35.08%  |
| Realtek Semiconductor             | 176       | 34.11%  |
| Qualcomm Atheros                  | 61        | 11.82%  |
| Broadcom                          | 33        | 6.4%    |
| MediaTek                          | 10        | 1.94%   |
| Marvell Technology Group          | 7         | 1.36%   |
| Sierra Wireless                   | 5         | 0.97%   |
| Qualcomm                          | 5         | 0.97%   |
| Broadcom Limited                  | 5         | 0.97%   |
| Dell                              | 4         | 0.78%   |
| TP-Link                           | 3         | 0.58%   |
| Samsung Electronics               | 3         | 0.58%   |
| Ralink Technology                 | 2         | 0.39%   |
| Ralink                            | 2         | 0.39%   |
| Huawei Technologies               | 2         | 0.39%   |
| Hewlett-Packard                   | 2         | 0.39%   |
| Ericsson Business Mobile Networks | 2         | 0.39%   |
| Xiaomi                            | 1         | 0.19%   |
| Qualcomm Atheros Communications   | 1         | 0.19%   |
| OPPO Electronics                  | 1         | 0.19%   |
| Nvidia                            | 1         | 0.19%   |
| Microchip Technology              | 1         | 0.19%   |
| LG Electronics                    | 1         | 0.19%   |
| JMicron Technology                | 1         | 0.19%   |
| DisplayLink                       | 1         | 0.19%   |
| D-Link                            | 1         | 0.19%   |
| BUFFALO                           | 1         | 0.19%   |
| Attansic Technology               | 1         | 0.19%   |
| ASIX Electronics                  | 1         | 0.19%   |
| Apple                             | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 96        | 14.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 33        | 5.15%   |
| Intel Wireless 8260                                               | 18        | 2.81%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 16        | 2.5%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 15        | 2.34%   |
| Intel Wireless 7265                                               | 14        | 2.18%   |
| Intel Wi-Fi 6 AX200                                               | 13        | 2.03%   |
| Intel Wireless 7260                                               | 12        | 1.87%   |
| Intel Wi-Fi 6 AX201                                               | 12        | 1.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 10        | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 1.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 10        | 1.56%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 9         | 1.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 8         | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                     | 8         | 1.25%   |
| Intel Wireless 8265 / 8275                                        | 7         | 1.09%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 7         | 1.09%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 1.09%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 6         | 0.94%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 0.94%   |
| Intel Wireless 3165                                               | 6         | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 0.94%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 6         | 0.94%   |
| Intel Centrino Advanced-N 6200                                    | 6         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 0.94%   |
| Realtek 802.11n WLAN Adapter                                      | 5         | 0.78%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.78%   |
| Intel Wireless 3160                                               | 5         | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 5         | 0.78%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 5         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 0.78%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 4         | 0.62%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 4         | 0.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.62%   |
| Intel Ultimate N WiFi Link 5300                                   | 4         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 178       | 49.72%  |
| Realtek Semiconductor           | 69        | 19.27%  |
| Qualcomm Atheros                | 55        | 15.36%  |
| Broadcom                        | 23        | 6.42%   |
| MediaTek                        | 10        | 2.79%   |
| Sierra Wireless                 | 5         | 1.4%    |
| Qualcomm                        | 5         | 1.4%    |
| TP-Link                         | 2         | 0.56%   |
| Ralink Technology               | 2         | 0.56%   |
| Ralink                          | 2         | 0.56%   |
| Dell                            | 2         | 0.56%   |
| Broadcom Limited                | 2         | 0.56%   |
| Qualcomm Atheros Communications | 1         | 0.28%   |
| D-Link                          | 1         | 0.28%   |
| BUFFALO                         | 1         | 0.28%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 18        | 4.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 16        | 4.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 15        | 4.1%    |
| Intel Wireless 7265                                            | 14        | 3.83%   |
| Intel Wi-Fi 6 AX200                                            | 13        | 3.55%   |
| Intel Wireless 7260                                            | 12        | 3.28%   |
| Intel Wi-Fi 6 AX201                                            | 12        | 3.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 3.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 2.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 10        | 2.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 10        | 2.73%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 2.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.46%   |
| Broadcom BCM43142 802.11b/g/n                                  | 8         | 2.19%   |
| Intel Wireless 8265 / 8275                                     | 7         | 1.91%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 7         | 1.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 1.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 7         | 1.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 6         | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.64%   |
| Intel Wireless 3165                                            | 6         | 1.64%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 6         | 1.64%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 1.64%   |
| Realtek 802.11n WLAN Adapter                                   | 5         | 1.37%   |
| Intel Wireless 3160                                            | 5         | 1.37%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 5         | 1.37%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 5         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 1.37%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 4         | 1.09%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 1.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.09%   |
| Intel Ultimate N WiFi Link 5300                                | 4         | 1.09%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.09%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 1.09%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 1.09%   |
| Sierra Wireless EM7455                                         | 3         | 0.82%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 0.82%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.82%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 142       | 52.79%  |
| Intel                    | 71        | 26.39%  |
| Qualcomm Atheros         | 14        | 5.2%    |
| Broadcom                 | 14        | 5.2%    |
| Marvell Technology Group | 7         | 2.6%    |
| Samsung Electronics      | 3         | 1.12%   |
| Broadcom Limited         | 3         | 1.12%   |
| Huawei Technologies      | 2         | 0.74%   |
| Hewlett-Packard          | 2         | 0.74%   |
| Xiaomi                   | 1         | 0.37%   |
| TP-Link                  | 1         | 0.37%   |
| OPPO Electronics         | 1         | 0.37%   |
| Nvidia                   | 1         | 0.37%   |
| Microchip Technology     | 1         | 0.37%   |
| LG Electronics           | 1         | 0.37%   |
| JMicron Technology       | 1         | 0.37%   |
| DisplayLink              | 1         | 0.37%   |
| Attansic Technology      | 1         | 0.37%   |
| ASIX Electronics         | 1         | 0.37%   |
| Apple                    | 1         | 0.37%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 96        | 35.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 33        | 12.18%  |
| Intel Ethernet Connection I219-LM                                              | 10        | 3.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 3.32%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 9         | 3.32%   |
| Intel 82577LM Gigabit Network Connection                                       | 6         | 2.21%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 5         | 1.85%   |
| Intel Ethernet Connection (3) I218-LM                                          | 4         | 1.48%   |
| Intel Ethernet Connection (16) I219-V                                          | 4         | 1.48%   |
| Intel 82567LM Gigabit Network Connection                                       | 4         | 1.48%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 3         | 1.11%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 3         | 1.11%   |
| Intel Ethernet Connection I219-V                                               | 3         | 1.11%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.11%   |
| Intel Ethernet Connection (13) I219-V                                          | 3         | 1.11%   |
| Intel 82566MM Gigabit Network Connection                                       | 3         | 1.11%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.11%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 0.74%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.74%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.74%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.74%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.74%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.74%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.74%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.74%   |
| Huawei ALP-AL00                                                                | 2         | 0.74%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 0.74%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 0.74%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.37%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 1         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 338       | 56.15%  |
| Ethernet | 260       | 43.19%  |
| Modem    | 4         | 0.66%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 300       | 83.8%   |
| Ethernet | 58        | 16.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 243       | 71.05%  |
| 1     | 89        | 26.02%  |
| 0     | 10        | 2.92%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 230       | 66.47%  |
| Yes  | 116       | 33.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 126       | 46.67%  |
| Realtek Semiconductor           | 40        | 14.81%  |
| Broadcom                        | 20        | 7.41%   |
| Qualcomm Atheros Communications | 16        | 5.93%   |
| Foxconn / Hon Hai               | 14        | 5.19%   |
| Lite-On Technology              | 13        | 4.81%   |
| IMC Networks                    | 11        | 4.07%   |
| Apple                           | 5         | 1.85%   |
| Realtek                         | 4         | 1.48%   |
| Hewlett-Packard                 | 4         | 1.48%   |
| Dell                            | 4         | 1.48%   |
| Foxconn International           | 2         | 0.74%   |
| Cambridge Silicon Radio         | 2         | 0.74%   |
| ASUSTek Computer                | 2         | 0.74%   |
| USI                             | 1         | 0.37%   |
| Toshiba                         | 1         | 0.37%   |
| Taiyo Yuden                     | 1         | 0.37%   |
| Ralink                          | 1         | 0.37%   |
| Micro Star International        | 1         | 0.37%   |
| Chicony Electronics             | 1         | 0.37%   |
| Alps Electric                   | 1         | 0.37%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 60        | 22.14%  |
| Realtek Bluetooth Radio                                                             | 30        | 11.07%  |
| Intel AX201 Bluetooth                                                               | 22        | 8.12%   |
| Intel AX200 Bluetooth                                                               | 12        | 4.43%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 11        | 4.06%   |
| Intel Bluetooth Device                                                              | 9         | 3.32%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 2.21%   |
| Intel AX210 Bluetooth                                                               | 6         | 2.21%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 2.21%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 1.85%   |
| Apple Bluetooth Host Controller                                                     | 5         | 1.85%   |
| Realtek Bluetooth Radio                                                             | 4         | 1.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 1.48%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 1.48%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.48%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 1.48%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.48%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 1.11%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 1.11%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.11%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.11%   |
| IMC Networks Wireless_Device                                                        | 3         | 1.11%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 1.11%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 1.11%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 1.11%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.11%   |
| Lite-On Wireless_Device                                                             | 2         | 0.74%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.74%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.74%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.74%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.74%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.74%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 0.74%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.74%   |
| Broadcom BCM20702A0                                                                 | 2         | 0.74%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.74%   |
| USI Bluetooth Device                                                                | 1         | 0.37%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.37%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                                             | 1         | 0.37%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 265       | 67.26%  |
| AMD                     | 73        | 18.53%  |
| Nvidia                  | 31        | 7.87%   |
| C-Media Electronics     | 4         | 1.02%   |
| Texas Instruments       | 3         | 0.76%   |
| JMTek                   | 2         | 0.51%   |
| GN Netcom               | 2         | 0.51%   |
| Generalplus Technology  | 2         | 0.51%   |
| ASUSTek Computer        | 2         | 0.51%   |
| Textech International   | 1         | 0.25%   |
| Tenx Technology         | 1         | 0.25%   |
| Realtek Semiconductor   | 1         | 0.25%   |
| Microchip Technology    | 1         | 0.25%   |
| M-Audio                 | 1         | 0.25%   |
| Lenovo                  | 1         | 0.25%   |
| HiBy                    | 1         | 0.25%   |
| DCMT Technology         | 1         | 0.25%   |
| Conexant Systems        | 1         | 0.25%   |
| BEHRINGER International | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 36        | 7.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 34        | 6.97%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 26        | 5.33%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 22        | 4.51%   |
| AMD FCH Azalia Controller                                                                         | 20        | 4.1%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 3.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 18        | 3.69%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 3.28%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 15        | 3.07%   |
| Intel Broadwell-U Audio Controller                                                                | 15        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 3.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 2.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 2.66%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 2.46%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 10        | 2.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 2.05%   |
| Intel 8 Series HD Audio Controller                                                                | 10        | 2.05%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 1.84%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 9         | 1.84%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 1.84%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 7         | 1.43%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 1.23%   |
| Nvidia Audio device                                                                               | 5         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.02%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 5         | 1.02%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.02%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.02%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.02%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.82%   |
| Intel Cannon Lake PCH cAVS                                                                        | 4         | 0.82%   |
| AMD Wrestler HDMI Audio                                                                           | 4         | 0.82%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 4         | 0.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.82%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.61%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.61%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.61%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 87        | 28.62%  |
| SK hynix                   | 60        | 19.74%  |
| Unknown                    | 36        | 11.84%  |
| Micron Technology          | 30        | 9.87%   |
| Kingston                   | 22        | 7.24%   |
| Crucial                    | 19        | 6.25%   |
| Unknown (ABCD)             | 11        | 3.62%   |
| Ramaxel Technology         | 6         | 1.97%   |
| Smart                      | 4         | 1.32%   |
| Nanya Technology           | 3         | 0.99%   |
| G.Skill                    | 3         | 0.99%   |
| fef5                       | 3         | 0.99%   |
| Corsair                    | 3         | 0.99%   |
| A-DATA Technology          | 3         | 0.99%   |
| Transcend                  | 2         | 0.66%   |
| Elpida                     | 2         | 0.66%   |
| V-Color                    | 1         | 0.33%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.33%   |
| Unifosa                    | 1         | 0.33%   |
| Qimonda                    | 1         | 0.33%   |
| Foxline                    | 1         | 0.33%   |
| Essencore                  | 1         | 0.33%   |
| Daten Tecnologia           | 1         | 0.33%   |
| Avant                      | 1         | 0.33%   |
| 48spaces                   | 1         | 0.33%   |
| Unknown                    | 1         | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 11        | 3.43%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.87%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 1.56%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 5         | 1.56%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 1.56%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 4         | 1.25%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 4         | 1.25%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.25%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.25%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.25%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 1.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.25%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.93%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.93%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 3         | 0.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 0.93%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 3         | 0.93%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 3         | 0.93%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.93%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.93%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.93%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.93%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.93%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB 2400MT/s                         | 3         | 0.93%   |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                            | 3         | 0.93%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.62%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                      | 2         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR2 333MT/s                       | 2         | 0.62%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.62%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                     | 2         | 0.62%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s          | 2         | 0.62%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.62%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.62%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16384MB SODIMM DDR4 3200MT/s       | 2         | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.62%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 0.62%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.62%   |
| SK hynix RAM HCNNNCPMMLXR-NEE 2GB Row Of Chips LPDDR4 4267MT/s   | 2         | 0.62%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 104       | 40.15%  |
| DDR3    | 82        | 31.66%  |
| LPDDR4  | 27        | 10.42%  |
| DDR2    | 20        | 7.72%   |
| SDRAM   | 7         | 2.7%    |
| LPDDR5  | 5         | 1.93%   |
| LPDDR3  | 5         | 1.93%   |
| DDR5    | 4         | 1.54%   |
| Unknown | 4         | 1.54%   |
| DDR     | 1         | 0.39%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 223       | 86.1%   |
| Row Of Chips | 26        | 10.04%  |
| Unknown      | 6         | 2.32%   |
| Chip         | 4         | 1.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 91        | 32.27%  |
| 4096  | 76        | 26.95%  |
| 2048  | 51        | 18.09%  |
| 16384 | 39        | 13.83%  |
| 1024  | 14        | 4.96%   |
| 32768 | 9         | 3.19%   |
| 1536  | 1         | 0.35%   |
| 512   | 1         | 0.35%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 62        | 23.13%  |
| 1600    | 56        | 20.9%   |
| 2667    | 29        | 10.82%  |
| 2400    | 22        | 8.21%   |
| 2133    | 14        | 5.22%   |
| 1334    | 12        | 4.48%   |
| 667     | 12        | 4.48%   |
| 4267    | 7         | 2.61%   |
| 1333    | 6         | 2.24%   |
| 1067    | 6         | 2.24%   |
| 4199    | 5         | 1.87%   |
| 4800    | 4         | 1.49%   |
| 3266    | 4         | 1.49%   |
| Unknown | 4         | 1.49%   |
| 6400    | 3         | 1.12%   |
| 800     | 3         | 1.12%   |
| 4266    | 2         | 0.75%   |
| 2048    | 2         | 0.75%   |
| 1867    | 2         | 0.75%   |
| 1066    | 2         | 0.75%   |
| 975     | 2         | 0.75%   |
| 533     | 2         | 0.75%   |
| 333     | 2         | 0.75%   |
| 7467    | 1         | 0.37%   |
| 5500    | 1         | 0.37%   |
| 3733    | 1         | 0.37%   |
| 2134    | 1         | 0.37%   |
| 1776    | 1         | 0.37%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Xiaomi | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Xiaomi MiMouse 2 | 1         | 100%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                | Notebooks | Percent |
|----------------------|-----------|---------|
| Canon CanoScan 4400F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 82        | 26.11%  |
| IMC Networks                           | 25        | 7.96%   |
| Microdia                               | 24        | 7.64%   |
| Realtek Semiconductor                  | 23        | 7.32%   |
| Quanta                                 | 23        | 7.32%   |
| Sunplus Innovation Technology          | 19        | 6.05%   |
| Cheng Uei Precision Industry (Foxlink) | 19        | 6.05%   |
| Suyin                                  | 14        | 4.46%   |
| Bison Electronics                      | 13        | 4.14%   |
| Syntek                                 | 6         | 1.91%   |
| Luxvisions Innotech Limited            | 6         | 1.91%   |
| Lite-On Technology                     | 6         | 1.91%   |
| Logitech                               | 5         | 1.59%   |
| Acer                                   | 5         | 1.59%   |
| Silicon Motion                         | 4         | 1.27%   |
| Apple                                  | 4         | 1.27%   |
| Z-Star Microelectronics                | 3         | 0.96%   |
| Sonix Technology                       | 3         | 0.96%   |
| Ricoh                                  | 3         | 0.96%   |
| Lenovo                                 | 3         | 0.96%   |
| icSpring                               | 3         | 0.96%   |
| Alcor Micro                            | 3         | 0.96%   |
| USB Camera CS                          | 2         | 0.64%   |
| SunplusIT                              | 2         | 0.64%   |
| Samsung Electronics                    | 2         | 0.64%   |
| 8SSC21D67422V1SR28902JL                | 2         | 0.64%   |
| Xiongmai                               | 1         | 0.32%   |
| ValueHD                                | 1         | 0.32%   |
| Primax Electronics                     | 1         | 0.32%   |
| OYT Tech                               | 1         | 0.32%   |
| OmniVision Technologies                | 1         | 0.32%   |
| MacroSilicon                           | 1         | 0.32%   |
| Importek                               | 1         | 0.32%   |
| DigiTech                               | 1         | 0.32%   |
| Alpha Imaging Technology               | 1         | 0.32%   |
| Unknown                                | 1         | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 27        | 8.57%   |
| Microdia Integrated_Webcam_HD                       | 10        | 3.17%   |
| Sunplus Integrated_Webcam_HD                        | 8         | 2.54%   |
| Quanta HD User Facing                               | 7         | 2.22%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 7         | 2.22%   |
| Chicony HD Webcam                                   | 6         | 1.9%    |
| Chicony TOSHIBA Web Camera - HD                     | 5         | 1.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 5         | 1.59%   |
| Syntek Integrated Camera                            | 4         | 1.27%   |
| Realtek Integrated_Webcam_HD                        | 4         | 1.27%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 1.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 4         | 1.27%   |
| IMC Networks Integrated Camera                      | 4         | 1.27%   |
| Chicony HP Truevision HD camera                     | 4         | 1.27%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 4         | 1.27%   |
| Bison Integrated Camera                             | 4         | 1.27%   |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 0.95%   |
| Sunplus Integrated_Webcam_FHD                       | 3         | 0.95%   |
| Realtek Lenovo EasyCamera                           | 3         | 0.95%   |
| Realtek Acer 640 x 480 laptop camera                | 3         | 0.95%   |
| Quanta HP Webcam                                    | 3         | 0.95%   |
| Quanta HP TrueVision HD Camera                      | 3         | 0.95%   |
| Lite-On Integrated Camera                           | 3         | 0.95%   |
| IMC Networks ov9734_azurewave_camera                | 3         | 0.95%   |
| icSpring camera                                     | 3         | 0.95%   |
| Chicony USB2.0 Camera                               | 3         | 0.95%   |
| Chicony HP Truevision HD                            | 3         | 0.95%   |
| Chicony EasyCamera                                  | 3         | 0.95%   |
| Bison SunplusIT Integrated Camera                   | 3         | 0.95%   |
| Bison Lenovo EasyCamera                             | 3         | 0.95%   |
| Apple Built-in iSight                               | 3         | 0.95%   |
| USB Camera CS USB Camera CS                         | 2         | 0.63%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 0.63%   |
| Realtek USB2.0-Camera                               | 2         | 0.63%   |
| Realtek USB Camera                                  | 2         | 0.63%   |
| Realtek Integrated_Webcam_FHD                       | 2         | 0.63%   |
| Realtek HP Truevision HD                            | 2         | 0.63%   |
| Realtek HD WebCam                                   | 2         | 0.63%   |
| Quanta VGA WebCam                                   | 2         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 19        | 33.33%  |
| Shenzhen Goodix Technology         | 11        | 19.3%   |
| Upek                               | 8         | 14.04%  |
| Synaptics                          | 7         | 12.28%  |
| Elan Microelectronics              | 4         | 7.02%   |
| STMicroelectronics                 | 3         | 5.26%   |
| AuthenTec                          | 3         | 5.26%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.75%   |
| Focal-systems.Corp                 | 1         | 1.75%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 10        | 17.54%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 7         | 12.28%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 7         | 12.28%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 4         | 7.02%   |
| Validity Sensors Synaptics WBDI                                 | 3         | 5.26%   |
| STMicroelectronics Fingerprint Reader                           | 3         | 5.26%   |
| Elan ELAN:ARM-M4                                                | 3         | 5.26%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 3.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 3.51%   |
| Synaptics UWP WBDI Device                                       | 2         | 3.51%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 3.51%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 2         | 3.51%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 1         | 1.75%   |
| Upek TCS5B Fingerprint sensor                                   | 1         | 1.75%   |
| Synaptics  WBDI                                                 | 1         | 1.75%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.75%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 1.75%   |
| Shenzhen Goodix FingerPrint                                     | 1         | 1.75%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.75%   |
| Focal-systems.Corp FT9201Fingerprint.                           | 1         | 1.75%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.75%   |
| AuthenTec AES2810                                               | 1         | 1.75%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 14        | 42.42%  |
| Alcor Micro | 13        | 39.39%  |
| O2 Micro    | 3         | 9.09%   |
| Lenovo      | 3         | 9.09%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 39.39%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 15.15%  |
| Broadcom 58200                                                               | 4         | 12.12%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 9.09%   |
| Broadcom 5880                                                                | 3         | 9.09%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 6.06%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.06%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 3.03%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 225       | 65.03%  |
| 1     | 95        | 27.46%  |
| 2     | 22        | 6.36%   |
| 3     | 4         | 1.16%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 54        | 36.99%  |
| Chipcard                 | 32        | 21.92%  |
| Graphics card            | 19        | 13.01%  |
| Camera                   | 13        | 8.9%    |
| Net/wireless             | 9         | 6.16%   |
| Bluetooth                | 5         | 3.42%   |
| Card reader              | 4         | 2.74%   |
| Network                  | 3         | 2.05%   |
| Storage                  | 2         | 1.37%   |
| Multimedia controller    | 2         | 1.37%   |
| Communication controller | 2         | 1.37%   |
| Net/ethernet             | 1         | 0.68%   |

