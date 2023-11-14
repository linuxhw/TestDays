Xubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Xubuntu.

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

Total: 3498

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | G505 20240                  | [ef019ff242](https://linux-hardware.org/?probe=ef019ff242) | Nov 06, 2023 |
| MECHREVO      | Code 01 Series PF5NU1G      | [767c3ff7fa](https://linux-hardware.org/?probe=767c3ff7fa) | Nov 05, 2023 |
| Dell          | Inspiron 7501               | [0926c7cdad](https://linux-hardware.org/?probe=0926c7cdad) | Nov 05, 2023 |
| HP            | Presario C500 (GF849EA#A... | [a4965dff09](https://linux-hardware.org/?probe=a4965dff09) | Nov 04, 2023 |
| Thomson       | N14C4WH64                   | [51c94bc00f](https://linux-hardware.org/?probe=51c94bc00f) | Nov 03, 2023 |
| Acer          | Predator PH717-71           | [a72ab29450](https://linux-hardware.org/?probe=a72ab29450) | Nov 02, 2023 |
| HP            | Presario CQ57               | [4874030c75](https://linux-hardware.org/?probe=4874030c75) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [a2a8295797](https://linux-hardware.org/?probe=a2a8295797) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [0d49a75fe1](https://linux-hardware.org/?probe=0d49a75fe1) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [cbe947aefc](https://linux-hardware.org/?probe=cbe947aefc) | Nov 01, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [cd9e941307](https://linux-hardware.org/?probe=cd9e941307) | Nov 01, 2023 |
| Lenovo        | IdeaPad S300 9803           | [543dfc0b4e](https://linux-hardware.org/?probe=543dfc0b4e) | Oct 31, 2023 |
| HP            | Presario C500 (GF849EA#A... | [580f4bdb18](https://linux-hardware.org/?probe=580f4bdb18) | Oct 31, 2023 |
| AMI           | Intel                       | [98d35ad708](https://linux-hardware.org/?probe=98d35ad708) | Oct 31, 2023 |
| ASUSTek       | K53E                        | [8b7c83e9d7](https://linux-hardware.org/?probe=8b7c83e9d7) | Oct 31, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [6273e445bd](https://linux-hardware.org/?probe=6273e445bd) | Oct 30, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a718d2e0ba](https://linux-hardware.org/?probe=a718d2e0ba) | Oct 28, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [c866e0068b](https://linux-hardware.org/?probe=c866e0068b) | Oct 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [6a8554304e](https://linux-hardware.org/?probe=6a8554304e) | Oct 27, 2023 |
| Dell          | Inspiron 1501               | [2c88e089bb](https://linux-hardware.org/?probe=2c88e089bb) | Oct 27, 2023 |
| Lenovo        | ThinkPad T61 64607EU        | [413cefff03](https://linux-hardware.org/?probe=413cefff03) | Oct 26, 2023 |
| HP            | Presario CQ57               | [a3f31b427e](https://linux-hardware.org/?probe=a3f31b427e) | Oct 26, 2023 |
| Acer          | Aspire 5740                 | [78702b9deb](https://linux-hardware.org/?probe=78702b9deb) | Oct 23, 2023 |
| Dell          | Latitude 3490               | [174ee1b12e](https://linux-hardware.org/?probe=174ee1b12e) | Oct 20, 2023 |
| Lenovo        | ThinkPad T61 64607EU        | [7be90734f6](https://linux-hardware.org/?probe=7be90734f6) | Oct 19, 2023 |
| HUAWEI        | RLEF-XX                     | [4a5c5417b7](https://linux-hardware.org/?probe=4a5c5417b7) | Oct 17, 2023 |
| Lenovo        | 15ARE05 81W4                | [dcb09acd04](https://linux-hardware.org/?probe=dcb09acd04) | Oct 17, 2023 |
| HP            | 250 G8 Notebook PC          | [949b939768](https://linux-hardware.org/?probe=949b939768) | Oct 16, 2023 |
| Acer          | Aspire A317-51K             | [b342c56fc5](https://linux-hardware.org/?probe=b342c56fc5) | Oct 15, 2023 |
| Dell          | Latitude 7330               | [8632b84be8](https://linux-hardware.org/?probe=8632b84be8) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | [edb8f551bf](https://linux-hardware.org/?probe=edb8f551bf) | Oct 14, 2023 |
| HP            | Laptop 15-dw0xxx            | [b7a193296f](https://linux-hardware.org/?probe=b7a193296f) | Oct 14, 2023 |
| Dynabook      | B65/ER                      | [2bda5e79a4](https://linux-hardware.org/?probe=2bda5e79a4) | Oct 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [41ca042a36](https://linux-hardware.org/?probe=41ca042a36) | Oct 14, 2023 |
| Dynabook      | B65/ER                      | [4bc1c4e1b6](https://linux-hardware.org/?probe=4bc1c4e1b6) | Oct 14, 2023 |
| Lenovo        | ThinkPad T430u 3352A83      | [c5a829d842](https://linux-hardware.org/?probe=c5a829d842) | Oct 14, 2023 |
| Apple         | MacBook8,1                  | [1a8e527488](https://linux-hardware.org/?probe=1a8e527488) | Oct 13, 2023 |
| HP            | EliteBook 830 G8 Noteboo... | [ef43db2db3](https://linux-hardware.org/?probe=ef43db2db3) | Oct 12, 2023 |
| Dell          | Latitude 5411               | [48ecb46d24](https://linux-hardware.org/?probe=48ecb46d24) | Oct 09, 2023 |
| Dell          | MXG061                      | [61763acf36](https://linux-hardware.org/?probe=61763acf36) | Oct 08, 2023 |
| Dell          | MXG061                      | [93939082fa](https://linux-hardware.org/?probe=93939082fa) | Oct 08, 2023 |
| MSI           | GP65 Leopard 10SDK          | [6b02c3ce0f](https://linux-hardware.org/?probe=6b02c3ce0f) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [3e5383da88](https://linux-hardware.org/?probe=3e5383da88) | Oct 08, 2023 |
| HP            | Pavilion g4                 | [cab160aff3](https://linux-hardware.org/?probe=cab160aff3) | Oct 08, 2023 |
| Fujitsu Si... | LIFEBOOK T4215              | [392481b855](https://linux-hardware.org/?probe=392481b855) | Oct 04, 2023 |
| ASUSTek       | ROG Strix G814JU_G814JU     | [45be832065](https://linux-hardware.org/?probe=45be832065) | Oct 04, 2023 |
| ASUSTek       | ROG Strix G814JU_G814JU     | [2dc93ff736](https://linux-hardware.org/?probe=2dc93ff736) | Oct 04, 2023 |
| Toshiba       | Satellite C55-C             | [e9ce3eada7](https://linux-hardware.org/?probe=e9ce3eada7) | Oct 02, 2023 |
| Google        | Swanky                      | [599959ccbe](https://linux-hardware.org/?probe=599959ccbe) | Sep 28, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [39fd38bc98](https://linux-hardware.org/?probe=39fd38bc98) | Sep 28, 2023 |
| ASUSTek       | N550JV                      | [ac27d821ae](https://linux-hardware.org/?probe=ac27d821ae) | Sep 27, 2023 |
| Fujitsu       | LIFEBOOK E734               | [61f61b1b63](https://linux-hardware.org/?probe=61f61b1b63) | Sep 25, 2023 |
| Fujitsu       | LIFEBOOK E734               | [ffb5ff9359](https://linux-hardware.org/?probe=ffb5ff9359) | Sep 25, 2023 |
| Toshiba       | Satellite C50D-A-10E        | [46f0ec000d](https://linux-hardware.org/?probe=46f0ec000d) | Sep 24, 2023 |
| Google        | Magpie                      | [3da6f69ed3](https://linux-hardware.org/?probe=3da6f69ed3) | Sep 24, 2023 |
| MSI           | GS75 Stealth 10SGS          | [9a310dd76b](https://linux-hardware.org/?probe=9a310dd76b) | Sep 24, 2023 |
| Dell          | XPS 15 9570                 | [fe5f9ad018](https://linux-hardware.org/?probe=fe5f9ad018) | Sep 23, 2023 |
| ASUSTek       | X510UQR                     | [364ee59aef](https://linux-hardware.org/?probe=364ee59aef) | Sep 23, 2023 |
| Dell          | Latitude D500               | [1861582ebd](https://linux-hardware.org/?probe=1861582ebd) | Sep 21, 2023 |
| Dell          | Latitude D500               | [19ccfd47c6](https://linux-hardware.org/?probe=19ccfd47c6) | Sep 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a6fd72ec9a](https://linux-hardware.org/?probe=a6fd72ec9a) | Sep 20, 2023 |
| Lenovo        | ThinkPad T430 2349BG6       | [dbd8f7715f](https://linux-hardware.org/?probe=dbd8f7715f) | Sep 19, 2023 |
| Apple         | MacBookPro5,4               | [f2d4f47a8e](https://linux-hardware.org/?probe=f2d4f47a8e) | Sep 18, 2023 |
| Dell          | Latitude 3520               | [c74d2293dd](https://linux-hardware.org/?probe=c74d2293dd) | Sep 18, 2023 |
| Acer          | Aspire E5-473G              | [936a48fb5a](https://linux-hardware.org/?probe=936a48fb5a) | Sep 16, 2023 |
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
| Google        | Rabbid                      | [c55be85343](https://linux-hardware.org/?probe=c55be85343) | Sep 09, 2023 |
| Lenovo        | ThinkPad X250 20CLA1YJUK    | [a068fec56f](https://linux-hardware.org/?probe=a068fec56f) | Sep 09, 2023 |
| Dell          | XPS 13 9305                 | [b3756f752a](https://linux-hardware.org/?probe=b3756f752a) | Sep 08, 2023 |
| Medion        | Akoya P2213T                | [2464869ce2](https://linux-hardware.org/?probe=2464869ce2) | Sep 06, 2023 |
| Acer          | Aspire 5349                 | [62f941ff29](https://linux-hardware.org/?probe=62f941ff29) | Sep 03, 2023 |
| HP            | ZBook 17 G3                 | [43c2d13a44](https://linux-hardware.org/?probe=43c2d13a44) | Aug 31, 2023 |
| HP            | EliteBook 820 G3            | [5ef4c889a4](https://linux-hardware.org/?probe=5ef4c889a4) | Aug 31, 2023 |
| Dell          | Latitude E5510              | [61f6df7426](https://linux-hardware.org/?probe=61f6df7426) | Aug 29, 2023 |
| HP            | Pavilion 17                 | [ba077d7ea1](https://linux-hardware.org/?probe=ba077d7ea1) | Aug 29, 2023 |
| Dell          | XPS 15 9500                 | [74ad31c9de](https://linux-hardware.org/?probe=74ad31c9de) | Aug 29, 2023 |
| Apple         | MacBookPro7,1               | [f520b2dd72](https://linux-hardware.org/?probe=f520b2dd72) | Aug 28, 2023 |
| ASUSTek       | ROG Strix G733PY_G733PY     | [b886de0613](https://linux-hardware.org/?probe=b886de0613) | Aug 28, 2023 |
| Google        | Banjo                       | [fcac9f460e](https://linux-hardware.org/?probe=fcac9f460e) | Aug 28, 2023 |
| HP            | Pavilion 17                 | [1d04c114d6](https://linux-hardware.org/?probe=1d04c114d6) | Aug 26, 2023 |
| Toshiba       | Satellite C55D-B            | [b7dce1f6e0](https://linux-hardware.org/?probe=b7dce1f6e0) | Aug 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [add8b61fa2](https://linux-hardware.org/?probe=add8b61fa2) | Aug 24, 2023 |
| Lenovo        | ThinkPad T460s 20F9003VM... | [e6e076d380](https://linux-hardware.org/?probe=e6e076d380) | Aug 23, 2023 |
| Acer          | AOD255                      | [06c6346db1](https://linux-hardware.org/?probe=06c6346db1) | Aug 23, 2023 |
| Acer          | TMP255-M                    | [4d5632e2d0](https://linux-hardware.org/?probe=4d5632e2d0) | Aug 22, 2023 |
| GPU Compan... | GWTN156-5                   | [22efc40cfd](https://linux-hardware.org/?probe=22efc40cfd) | Aug 21, 2023 |
| HP            | Presario CQ42               | [183f035603](https://linux-hardware.org/?probe=183f035603) | Aug 20, 2023 |
| Lenovo        | G50-70 20351                | [a8a0c22567](https://linux-hardware.org/?probe=a8a0c22567) | Aug 20, 2023 |
| HP            | 250 G4 Notebook PC          | [ea6fdc81ab](https://linux-hardware.org/?probe=ea6fdc81ab) | Aug 18, 2023 |
| Acer          | Aspire E1-571G              | [6aec4cb61e](https://linux-hardware.org/?probe=6aec4cb61e) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f626ffa833](https://linux-hardware.org/?probe=f626ffa833) | Aug 17, 2023 |
| Sony          | VGN-SR19VN                  | [013756c475](https://linux-hardware.org/?probe=013756c475) | Aug 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [48af3e541c](https://linux-hardware.org/?probe=48af3e541c) | Aug 16, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [5b482b674c](https://linux-hardware.org/?probe=5b482b674c) | Aug 16, 2023 |
| MSI           | U90/U100                    | [e8ae0fbcfb](https://linux-hardware.org/?probe=e8ae0fbcfb) | Aug 14, 2023 |
| Lenovo        | ThinkPad X250 20CM001RMC    | [618a7e3e29](https://linux-hardware.org/?probe=618a7e3e29) | Aug 14, 2023 |
| Lenovo        | B50-50 80S2                 | [6c897e0c63](https://linux-hardware.org/?probe=6c897e0c63) | Aug 14, 2023 |
| Daten Tecn... | DT02-M4                     | [39acd7fbd5](https://linux-hardware.org/?probe=39acd7fbd5) | Aug 13, 2023 |
| Lenovo        | IdeaPad Y570 0862           | [0ea140ff49](https://linux-hardware.org/?probe=0ea140ff49) | Aug 12, 2023 |
| Dell          | Latitude 3540               | [496e3ab340](https://linux-hardware.org/?probe=496e3ab340) | Aug 10, 2023 |
| HP            | Laptop 17-cp0xxx            | [c5a255abcb](https://linux-hardware.org/?probe=c5a255abcb) | Aug 10, 2023 |
| Unknown       | Unknown                     | [5f186cbc4d](https://linux-hardware.org/?probe=5f186cbc4d) | Aug 09, 2023 |
| ASUSTek       | X541UVK                     | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Acer          | Aspire 5732Z                | [5a0ee0b4c0](https://linux-hardware.org/?probe=5a0ee0b4c0) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | [cc5ec06f60](https://linux-hardware.org/?probe=cc5ec06f60) | Aug 08, 2023 |
| Acer          | Aspire A515-54G             | [14e4cbffd4](https://linux-hardware.org/?probe=14e4cbffd4) | Aug 08, 2023 |
| Dell          | Latitude 5411               | [2d69739196](https://linux-hardware.org/?probe=2d69739196) | Aug 07, 2023 |
| Lenovo        | G500 20236                  | [88a569c8ee](https://linux-hardware.org/?probe=88a569c8ee) | Aug 03, 2023 |
| Acer          | Aspire A517-52              | [aa9fd10def](https://linux-hardware.org/?probe=aa9fd10def) | Aug 01, 2023 |
| Acer          | AOD255                      | [bdaffcb2ef](https://linux-hardware.org/?probe=bdaffcb2ef) | Jul 31, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [67fbb84480](https://linux-hardware.org/?probe=67fbb84480) | Jul 31, 2023 |
| SiComputer    | NL40_50CU                   | [95afbe5674](https://linux-hardware.org/?probe=95afbe5674) | Jul 30, 2023 |
| Acer          | Aspire A517-52              | [1df8f3a3ed](https://linux-hardware.org/?probe=1df8f3a3ed) | Jul 29, 2023 |
| Medion        | Akoya P2213T                | [740da3bf14](https://linux-hardware.org/?probe=740da3bf14) | Jul 29, 2023 |
| Acer          | AOD255                      | [53c73b6ad3](https://linux-hardware.org/?probe=53c73b6ad3) | Jul 29, 2023 |
| HP            | ProBook 4525s               | [f1f6309860](https://linux-hardware.org/?probe=f1f6309860) | Jul 29, 2023 |
| Gateway       | NV57H                       | [efc311477f](https://linux-hardware.org/?probe=efc311477f) | Jul 28, 2023 |
| Samsung       | N250P/N145P                 | [6b6e675a4c](https://linux-hardware.org/?probe=6b6e675a4c) | Jul 28, 2023 |
| Acer          | Extensa 2510                | [b276a715eb](https://linux-hardware.org/?probe=b276a715eb) | Jul 27, 2023 |
| Acer          | AOD255                      | [4f96dbf750](https://linux-hardware.org/?probe=4f96dbf750) | Jul 25, 2023 |
| Acer          | AOD255                      | [3543f0800e](https://linux-hardware.org/?probe=3543f0800e) | Jul 24, 2023 |
| MSI           | MEGA BOOK GX620             | [184ec8dfc2](https://linux-hardware.org/?probe=184ec8dfc2) | Jul 22, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [ff6179199d](https://linux-hardware.org/?probe=ff6179199d) | Jul 22, 2023 |
| HP            | ProBook 445 14 inch G9 N... | [1c28b8d159](https://linux-hardware.org/?probe=1c28b8d159) | Jul 22, 2023 |
| MSI           | PR601/VR603                 | [b982476d84](https://linux-hardware.org/?probe=b982476d84) | Jul 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [38856f8131](https://linux-hardware.org/?probe=38856f8131) | Jul 21, 2023 |
| HP            | Laptop 15s-fq2xxx           | [977443386e](https://linux-hardware.org/?probe=977443386e) | Jul 21, 2023 |
| Itautec       | Infoway w7535               | [bde95c0c99](https://linux-hardware.org/?probe=bde95c0c99) | Jul 21, 2023 |
| Thomson       | N15C8BK2T                   | [2e04333da5](https://linux-hardware.org/?probe=2e04333da5) | Jul 19, 2023 |
| Dell          | Latitude 5590               | [93857a3b66](https://linux-hardware.org/?probe=93857a3b66) | Jul 18, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | [f0f2c5a6a7](https://linux-hardware.org/?probe=f0f2c5a6a7) | Jul 17, 2023 |
| TUXEDO        | N85_N87HCHNHZ               | [6070a533c5](https://linux-hardware.org/?probe=6070a533c5) | Jul 17, 2023 |
| MSI           | GF65 Thin 10SER             | [27966135e2](https://linux-hardware.org/?probe=27966135e2) | Jul 16, 2023 |
| Dell          | Inspiron 1501               | [a79d62db7c](https://linux-hardware.org/?probe=a79d62db7c) | Jul 16, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [c9a443767b](https://linux-hardware.org/?probe=c9a443767b) | Jul 16, 2023 |
| MSI           | Modern 15 A10RBS            | [fde24c2a13](https://linux-hardware.org/?probe=fde24c2a13) | Jul 15, 2023 |
| Lenovo        | G50-70 20351                | [d18c64af74](https://linux-hardware.org/?probe=d18c64af74) | Jul 14, 2023 |
| GPU Compan... | GWNC21524                   | [e3e2452c10](https://linux-hardware.org/?probe=e3e2452c10) | Jul 14, 2023 |
| Lenovo        | ThinkPad T480 20L6S01Q3U    | [f6a1f94437](https://linux-hardware.org/?probe=f6a1f94437) | Jul 13, 2023 |
| HP            | ProBook 4525s               | [6bae89bb98](https://linux-hardware.org/?probe=6bae89bb98) | Jul 13, 2023 |
| HP            | Laptop 15s-fq2xxx           | [5aacfb69aa](https://linux-hardware.org/?probe=5aacfb69aa) | Jul 12, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [d4bc86a90a](https://linux-hardware.org/?probe=d4bc86a90a) | Jul 12, 2023 |
| Lenovo        | ThinkPad T460s 20FAS42W0... | [add1dac3cb](https://linux-hardware.org/?probe=add1dac3cb) | Jul 11, 2023 |
| HP            | ProBook 11 G2               | [db2ec8adc8](https://linux-hardware.org/?probe=db2ec8adc8) | Jul 08, 2023 |
| Acer          | Aspire A315-54              | [4aba66ddfb](https://linux-hardware.org/?probe=4aba66ddfb) | Jul 07, 2023 |
| Olidata       | Stainer 8050                | [beb3c029a6](https://linux-hardware.org/?probe=beb3c029a6) | Jul 07, 2023 |
| Dell          | Latitude 3540               | [4ebbd2913f](https://linux-hardware.org/?probe=4ebbd2913f) | Jul 06, 2023 |
| HP            | Compaq Presario CQ60        | [983745a0d2](https://linux-hardware.org/?probe=983745a0d2) | Jul 03, 2023 |
| HP            | Compaq Presario CQ60        | [a5bd493e91](https://linux-hardware.org/?probe=a5bd493e91) | Jul 03, 2023 |
| Google        | Snappy                      | [683d8bf80a](https://linux-hardware.org/?probe=683d8bf80a) | Jul 02, 2023 |
| Google        | Snappy                      | [d3502a53cc](https://linux-hardware.org/?probe=d3502a53cc) | Jul 02, 2023 |
| HP            | Pavilion 17                 | [e6daccb5b9](https://linux-hardware.org/?probe=e6daccb5b9) | Jul 02, 2023 |
| Acer          | Aspire A517-52              | [7c14851b62](https://linux-hardware.org/?probe=7c14851b62) | Jul 02, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [f252a559f2](https://linux-hardware.org/?probe=f252a559f2) | Jul 02, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [b9d71582c0](https://linux-hardware.org/?probe=b9d71582c0) | Jul 01, 2023 |
| MSI           | GF63 Thin 11UC              | [5270a5ddc7](https://linux-hardware.org/?probe=5270a5ddc7) | Jul 01, 2023 |
| Dynabook      | B65/ER                      | [8f6f243e98](https://linux-hardware.org/?probe=8f6f243e98) | Jul 01, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [3f2c5d0eb2](https://linux-hardware.org/?probe=3f2c5d0eb2) | Jul 01, 2023 |
| Acer          | Aspire A517-52              | [79f2cae4d6](https://linux-hardware.org/?probe=79f2cae4d6) | Jun 30, 2023 |
| Google        | Fleex                       | [7e3eb2d4f9](https://linux-hardware.org/?probe=7e3eb2d4f9) | Jun 30, 2023 |
| HP            | Unknown                     | [0f4ae63ce0](https://linux-hardware.org/?probe=0f4ae63ce0) | Jun 30, 2023 |
| Acer          | Aspire A517-52              | [06d27800c2](https://linux-hardware.org/?probe=06d27800c2) | Jun 29, 2023 |
| Apple         | MacBookPro7,1               | [5a82f91882](https://linux-hardware.org/?probe=5a82f91882) | Jun 28, 2023 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [ff919014cd](https://linux-hardware.org/?probe=ff919014cd) | Jun 28, 2023 |
| HP            | Unknown                     | [d681765bb7](https://linux-hardware.org/?probe=d681765bb7) | Jun 26, 2023 |
| Dell          | Inspiron MM061              | [8152698df7](https://linux-hardware.org/?probe=8152698df7) | Jun 25, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [338b2e7db3](https://linux-hardware.org/?probe=338b2e7db3) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Dell          | Latitude E6410              | [7d1989fd84](https://linux-hardware.org/?probe=7d1989fd84) | Jun 24, 2023 |
| Dell          | Inspiron N4030              | [89116ab6be](https://linux-hardware.org/?probe=89116ab6be) | Jun 24, 2023 |
| Alienware     | 18                          | [047bc74541](https://linux-hardware.org/?probe=047bc74541) | Jun 24, 2023 |
| ASUSTek       | N53SV                       | [0908f99494](https://linux-hardware.org/?probe=0908f99494) | Jun 23, 2023 |
| ASUSTek       | N53SV                       | [1999834725](https://linux-hardware.org/?probe=1999834725) | Jun 23, 2023 |
| Google        | Link                        | [b8284753ca](https://linux-hardware.org/?probe=b8284753ca) | Jun 22, 2023 |
| HP            | Unknown                     | [4f27a83f9e](https://linux-hardware.org/?probe=4f27a83f9e) | Jun 21, 2023 |
| TUXEDO        | P65xRP                      | [cfefc9c13a](https://linux-hardware.org/?probe=cfefc9c13a) | Jun 20, 2023 |
| Dell          | Inspiron 5415               | [ade4d4c90c](https://linux-hardware.org/?probe=ade4d4c90c) | Jun 19, 2023 |
| Acer          | Aspire 5600                 | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| GPU Compan... | GWNC21524                   | [5a31ac8b21](https://linux-hardware.org/?probe=5a31ac8b21) | Jun 15, 2023 |
| HP            | Unknown                     | [00c49ad567](https://linux-hardware.org/?probe=00c49ad567) | Jun 14, 2023 |
| Samsung       | 760XDA                      | [f0decf4dbe](https://linux-hardware.org/?probe=f0decf4dbe) | Jun 14, 2023 |
| Dell          | Latitude E5270              | [49f184b9e9](https://linux-hardware.org/?probe=49f184b9e9) | Jun 13, 2023 |
| GPU Compan... | GWTN156-5                   | [b0afd2fa7b](https://linux-hardware.org/?probe=b0afd2fa7b) | Jun 13, 2023 |
| Dell          | Latitude 5411               | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| HP            | EliteBook 640 14 inch G9... | [69f20a331c](https://linux-hardware.org/?probe=69f20a331c) | Jun 12, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [1cfac1228c](https://linux-hardware.org/?probe=1cfac1228c) | Jun 10, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9200        | [427db0e78b](https://linux-hardware.org/?probe=427db0e78b) | Jun 10, 2023 |
| Toshiba       | Satellite C650              | [162f690841](https://linux-hardware.org/?probe=162f690841) | Jun 09, 2023 |
| Acer          | AO722                       | [a57b6cf2ff](https://linux-hardware.org/?probe=a57b6cf2ff) | Jun 08, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [2f5adf59a3](https://linux-hardware.org/?probe=2f5adf59a3) | Jun 07, 2023 |
| Dell          | Vostro 15 3510              | [b661a14644](https://linux-hardware.org/?probe=b661a14644) | Jun 07, 2023 |
| Acer          | AO722                       | [8840b1284b](https://linux-hardware.org/?probe=8840b1284b) | Jun 06, 2023 |
| Dell          | Precision 5510              | [9888f3aedd](https://linux-hardware.org/?probe=9888f3aedd) | Jun 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [46751741ef](https://linux-hardware.org/?probe=46751741ef) | Jun 05, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| Lenovo        | V560                        | [b2564e07cc](https://linux-hardware.org/?probe=b2564e07cc) | Jun 03, 2023 |
| SK hynix      | HyBook                      | [c25f19e040](https://linux-hardware.org/?probe=c25f19e040) | Jun 03, 2023 |
| HP            | Laptop 14s-dq0xxx           | [0017659aa2](https://linux-hardware.org/?probe=0017659aa2) | Jun 01, 2023 |
| Dell          | Latitude 7390               | [caa2968187](https://linux-hardware.org/?probe=caa2968187) | May 30, 2023 |
| Unknown       | Unknown                     | [9390923473](https://linux-hardware.org/?probe=9390923473) | May 30, 2023 |
| Chuwi         | CoreBook X                  | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| Acer          | Aspire E5-772G              | [ae0b46c29f](https://linux-hardware.org/?probe=ae0b46c29f) | May 28, 2023 |
| Unknown       | Unknown                     | [9051961e40](https://linux-hardware.org/?probe=9051961e40) | May 28, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3715c09ad3](https://linux-hardware.org/?probe=3715c09ad3) | May 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [df5ea78282](https://linux-hardware.org/?probe=df5ea78282) | May 25, 2023 |
| Dell          | Latitude 7390               | [21653cfe83](https://linux-hardware.org/?probe=21653cfe83) | May 25, 2023 |
| Toshiba       | Satellite L300              | [10adda3362](https://linux-hardware.org/?probe=10adda3362) | May 25, 2023 |
| Samsung       | 730QCJ/730QCR               | [7788147663](https://linux-hardware.org/?probe=7788147663) | May 24, 2023 |
| Dell          | Inspiron 15-3552            | [b2ade78a38](https://linux-hardware.org/?probe=b2ade78a38) | May 24, 2023 |
| Lenovo        | ThinkPad W500 40626NG       | [9466f83af8](https://linux-hardware.org/?probe=9466f83af8) | May 22, 2023 |
| Dell          | Latitude E4200              | [f352cc3ee4](https://linux-hardware.org/?probe=f352cc3ee4) | May 22, 2023 |
| Dell          | Vostro 5620                 | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [bfaa8e099f](https://linux-hardware.org/?probe=bfaa8e099f) | May 21, 2023 |
| Dell          | G3 3500                     | [cbe9c2f010](https://linux-hardware.org/?probe=cbe9c2f010) | May 21, 2023 |
| Google        | Snappy                      | [d13d8adaf4](https://linux-hardware.org/?probe=d13d8adaf4) | May 17, 2023 |
| Acer          | TravelMate P215-41-G2       | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| Lenovo        | ThinkPad T61 7661V3L        | [5714171d2a](https://linux-hardware.org/?probe=5714171d2a) | May 14, 2023 |
| Acer          | Aspire V5-552G              | [4384294484](https://linux-hardware.org/?probe=4384294484) | May 14, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [7e178a2a32](https://linux-hardware.org/?probe=7e178a2a32) | May 13, 2023 |
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
| GPU Compan... | GWTC116-2                   | [a915e84a9a](https://linux-hardware.org/?probe=a915e84a9a) | May 08, 2023 |
| Google        | Auron_Yuna                  | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| HP            | Pavilion dv6                | [a4425e0654](https://linux-hardware.org/?probe=a4425e0654) | May 07, 2023 |
| Dell          | Inspiron 15-3567            | [fccfcd375f](https://linux-hardware.org/?probe=fccfcd375f) | May 06, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [c693555567](https://linux-hardware.org/?probe=c693555567) | May 05, 2023 |
| HP            | ENVY 4                      | [20395a1739](https://linux-hardware.org/?probe=20395a1739) | May 04, 2023 |
| MSI           | Modern 15 A5M               | [d8b2bfb82c](https://linux-hardware.org/?probe=d8b2bfb82c) | May 03, 2023 |
| Lenovo        | ThinkPad X201 3680MG1       | [3e433a7cfa](https://linux-hardware.org/?probe=3e433a7cfa) | May 03, 2023 |
| HP            | 15                          | [17817f5320](https://linux-hardware.org/?probe=17817f5320) | May 02, 2023 |
| Dell          | Latitude E7270              | [62c1cdc600](https://linux-hardware.org/?probe=62c1cdc600) | May 02, 2023 |
| Dell          | Latitude E7270              | [96e1a00bae](https://linux-hardware.org/?probe=96e1a00bae) | May 02, 2023 |
| Toshiba       | EQUIUM P200                 | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Acer          | Peppy                       | [dcac703c46](https://linux-hardware.org/?probe=dcac703c46) | Apr 30, 2023 |
| Acer          | Extensa 5620                | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| Sony          | VPCZ13M9E                   | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [95d59e1bc3](https://linux-hardware.org/?probe=95d59e1bc3) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [dfd3d8a5c5](https://linux-hardware.org/?probe=dfd3d8a5c5) | Apr 27, 2023 |
| MSI           | GP65 Leopard 10SDK          | [fc66ccccde](https://linux-hardware.org/?probe=fc66ccccde) | Apr 27, 2023 |
| Lenovo        | ThinkPad P50 20EN0013US     | [09f98983fd](https://linux-hardware.org/?probe=09f98983fd) | Apr 27, 2023 |
| SGIN          | M15                         | [ac5d947f22](https://linux-hardware.org/?probe=ac5d947f22) | Apr 27, 2023 |
| Dell          | Vostro 1520                 | [ef4bb434d9](https://linux-hardware.org/?probe=ef4bb434d9) | Apr 26, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [6b73c4cb65](https://linux-hardware.org/?probe=6b73c4cb65) | Apr 24, 2023 |
| Lenovo        | ThinkPad T420 4236PA8       | [f45e2448aa](https://linux-hardware.org/?probe=f45e2448aa) | Apr 24, 2023 |
| HP            | ProBook 11 G2               | [43f6a6180a](https://linux-hardware.org/?probe=43f6a6180a) | Apr 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [76c4edb7f3](https://linux-hardware.org/?probe=76c4edb7f3) | Apr 23, 2023 |
| Dell          | XPS 13 9333                 | [0fedfa2911](https://linux-hardware.org/?probe=0fedfa2911) | Apr 22, 2023 |
| GPU Compan... | GWTN156-5                   | [4611a1d998](https://linux-hardware.org/?probe=4611a1d998) | Apr 22, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C50... | [77cfc9d5b2](https://linux-hardware.org/?probe=77cfc9d5b2) | Apr 22, 2023 |
| Acer          | Aspire E1-571G              | [e062ca363c](https://linux-hardware.org/?probe=e062ca363c) | Apr 20, 2023 |
| HP            | ProBook 650 G3              | [704778a577](https://linux-hardware.org/?probe=704778a577) | Apr 19, 2023 |
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
| Fujitsu       | LIFEBOOK U759               | [08e8eb7cea](https://linux-hardware.org/?probe=08e8eb7cea) | Apr 05, 2023 |
| ASUSTek       | X58C                        | [ff580ffa57](https://linux-hardware.org/?probe=ff580ffa57) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [2ac5f02bb5](https://linux-hardware.org/?probe=2ac5f02bb5) | Apr 05, 2023 |
| ASUSTek       | X58C                        | [ae9888c407](https://linux-hardware.org/?probe=ae9888c407) | Apr 05, 2023 |
| Apple         | MacBookPro8,1               | [c80b7018f6](https://linux-hardware.org/?probe=c80b7018f6) | Apr 05, 2023 |
| Dell          | Latitude E6400              | [5aa68e620c](https://linux-hardware.org/?probe=5aa68e620c) | Apr 04, 2023 |
| Acer          | NU-SF314-42-R3S0            | [6f56806ef1](https://linux-hardware.org/?probe=6f56806ef1) | Apr 04, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [86de0a83c3](https://linux-hardware.org/?probe=86de0a83c3) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [3a225208fd](https://linux-hardware.org/?probe=3a225208fd) | Apr 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [2a881cc01e](https://linux-hardware.org/?probe=2a881cc01e) | Apr 01, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [81c43aeb0d](https://linux-hardware.org/?probe=81c43aeb0d) | Mar 30, 2023 |
| Medion        | S321X                       | [4c02136dda](https://linux-hardware.org/?probe=4c02136dda) | Mar 30, 2023 |
| Gateway       | LT27                        | [4697cead5f](https://linux-hardware.org/?probe=4697cead5f) | Mar 28, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [a7ff24abc4](https://linux-hardware.org/?probe=a7ff24abc4) | Mar 26, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [8d5a135264](https://linux-hardware.org/?probe=8d5a135264) | Mar 26, 2023 |
| Samsung       | RV408/RV508                 | [5f5efa7edc](https://linux-hardware.org/?probe=5f5efa7edc) | Mar 25, 2023 |
| Samsung       | RV408/RV508                 | [cce3fdd054](https://linux-hardware.org/?probe=cce3fdd054) | Mar 25, 2023 |
| HP            | EliteBook 6930p             | [da0d90d69f](https://linux-hardware.org/?probe=da0d90d69f) | Mar 25, 2023 |
| Unknown       | Unknown                     | [fb97269a4d](https://linux-hardware.org/?probe=fb97269a4d) | Mar 24, 2023 |
| Gigabyte      | AERO 15WV8                  | [379c88860a](https://linux-hardware.org/?probe=379c88860a) | Mar 23, 2023 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [f97f90f7ce](https://linux-hardware.org/?probe=f97f90f7ce) | Mar 22, 2023 |
| TrekStor      | Notebook Slim S130          | [6c3a6e7e53](https://linux-hardware.org/?probe=6c3a6e7e53) | Mar 22, 2023 |
| Gateway       | EC14 Series                 | [fdeb2e4e3b](https://linux-hardware.org/?probe=fdeb2e4e3b) | Mar 22, 2023 |
| Getac         | F110G3                      | [792ac98040](https://linux-hardware.org/?probe=792ac98040) | Mar 22, 2023 |
| HP            | EliteBook 725 G2            | [5112f86dde](https://linux-hardware.org/?probe=5112f86dde) | Mar 21, 2023 |
| Lenovo        | ThinkPad T530 2429LT7       | [ebb127610b](https://linux-hardware.org/?probe=ebb127610b) | Mar 20, 2023 |
| Chuwi         | CoreBook X                  | [fd4d05d961](https://linux-hardware.org/?probe=fd4d05d961) | Mar 20, 2023 |
| Gateway       | EC14 Series                 | [c6ea9d7f10](https://linux-hardware.org/?probe=c6ea9d7f10) | Mar 18, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [a174d9ea53](https://linux-hardware.org/?probe=a174d9ea53) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [182bd8cca1](https://linux-hardware.org/?probe=182bd8cca1) | Mar 16, 2023 |
| Lenovo        | ThinkPad E15 20RES05U00     | [7047c529ef](https://linux-hardware.org/?probe=7047c529ef) | Mar 13, 2023 |
| Google        | Kefka                       | [58abcf00e9](https://linux-hardware.org/?probe=58abcf00e9) | Mar 12, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [728697bff3](https://linux-hardware.org/?probe=728697bff3) | Mar 11, 2023 |
| Lenovo        | G50-45 80E3                 | [e2b7d998d8](https://linux-hardware.org/?probe=e2b7d998d8) | Mar 11, 2023 |
| Lenovo        | ThinkPad T510 4384VJZ       | [d9c87b4795](https://linux-hardware.org/?probe=d9c87b4795) | Mar 11, 2023 |
| Apple         | MacBookPro1,1               | [105d39532f](https://linux-hardware.org/?probe=105d39532f) | Mar 10, 2023 |
| Toshiba       | Satellite L300              | [a35bb278ba](https://linux-hardware.org/?probe=a35bb278ba) | Mar 09, 2023 |
| Toshiba       | Satellite L300              | [13418c9605](https://linux-hardware.org/?probe=13418c9605) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | [2d093cc3ef](https://linux-hardware.org/?probe=2d093cc3ef) | Mar 08, 2023 |
| GPU Compan... | GWTN156-5                   | [57d690358f](https://linux-hardware.org/?probe=57d690358f) | Mar 08, 2023 |
| HP            | Pavilion x2 Detachable      | [04ef76ee4a](https://linux-hardware.org/?probe=04ef76ee4a) | Mar 07, 2023 |
| Toshiba       | Satellite C55D-B            | [963b41587c](https://linux-hardware.org/?probe=963b41587c) | Mar 07, 2023 |
| Acer          | Aspire ES1-572              | [a3dbc9b45e](https://linux-hardware.org/?probe=a3dbc9b45e) | Mar 07, 2023 |
| Toshiba       | Satellite L775              | [75a1948a64](https://linux-hardware.org/?probe=75a1948a64) | Mar 07, 2023 |
| Lenovo        | G50-45 80E3                 | [ade979391f](https://linux-hardware.org/?probe=ade979391f) | Mar 07, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [9404cddcdf](https://linux-hardware.org/?probe=9404cddcdf) | Mar 07, 2023 |
| HP            | Compaq Presario C700        | [fe1c136403](https://linux-hardware.org/?probe=fe1c136403) | Mar 06, 2023 |
| HP            | Compaq Presario C700        | [0b29805ec8](https://linux-hardware.org/?probe=0b29805ec8) | Mar 06, 2023 |
| Microtech     | ebookPro                    | [cac30f03b1](https://linux-hardware.org/?probe=cac30f03b1) | Mar 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [64c40ef1a4](https://linux-hardware.org/?probe=64c40ef1a4) | Mar 06, 2023 |
| Acer          | Aspire A315-43              | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| Acer          | Aspire 5740                 | [de0d12baa4](https://linux-hardware.org/?probe=de0d12baa4) | Feb 27, 2023 |
| HP            | 655                         | [e6b694526e](https://linux-hardware.org/?probe=e6b694526e) | Feb 26, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [3f35f45bf0](https://linux-hardware.org/?probe=3f35f45bf0) | Feb 26, 2023 |
| Alienware     | 17 R4                       | [bfeccbf9f3](https://linux-hardware.org/?probe=bfeccbf9f3) | Feb 25, 2023 |
| HP            | EliteBook 820 G3            | [75a0fcca48](https://linux-hardware.org/?probe=75a0fcca48) | Feb 25, 2023 |
| HONOR         | BMH-WCX9                    | [634b80ac90](https://linux-hardware.org/?probe=634b80ac90) | Feb 24, 2023 |
| Dell          | Latitude E5470              | [d7c8a049c4](https://linux-hardware.org/?probe=d7c8a049c4) | Feb 24, 2023 |
| Dell          | Studio 1450                 | [c26228f66f](https://linux-hardware.org/?probe=c26228f66f) | Feb 22, 2023 |
| Lenovo        | ThinkPad X131e 3367AH5      | [3c1cec4c1c](https://linux-hardware.org/?probe=3c1cec4c1c) | Feb 22, 2023 |
| Acer          | Aspire 7736                 | [479496a645](https://linux-hardware.org/?probe=479496a645) | Feb 21, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [751f76b561](https://linux-hardware.org/?probe=751f76b561) | Feb 21, 2023 |
| HP            | Pavilion 15                 | [c33178dcdc](https://linux-hardware.org/?probe=c33178dcdc) | Feb 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [7ac4bb7d51](https://linux-hardware.org/?probe=7ac4bb7d51) | Feb 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [19e03ac7b2](https://linux-hardware.org/?probe=19e03ac7b2) | Feb 20, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [4a9dcac308](https://linux-hardware.org/?probe=4a9dcac308) | Feb 19, 2023 |
| Lenovo        | IdeaPad S12 20021,2959      | [d808827823](https://linux-hardware.org/?probe=d808827823) | Feb 19, 2023 |
| Sony          | VPCEA3S1E                   | [45d0b9a823](https://linux-hardware.org/?probe=45d0b9a823) | Feb 18, 2023 |
| Sony          | VPCZ13M9E                   | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| HP            | Pavilion g6                 | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [0b622220d7](https://linux-hardware.org/?probe=0b622220d7) | Feb 15, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | [d576d16c25](https://linux-hardware.org/?probe=d576d16c25) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | [2334fc688f](https://linux-hardware.org/?probe=2334fc688f) | Feb 14, 2023 |
| Fujitsu Si... | STYLISTIC ST5112            | [e2f49b2fe4](https://linux-hardware.org/?probe=e2f49b2fe4) | Feb 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [25dbf25c62](https://linux-hardware.org/?probe=25dbf25c62) | Feb 14, 2023 |
| HP            | Compaq nc6400 (RM741PA#A... | [d556bf453d](https://linux-hardware.org/?probe=d556bf453d) | Feb 13, 2023 |
| Toshiba       | Satellite Pro R50-B         | [0634db3367](https://linux-hardware.org/?probe=0634db3367) | Feb 13, 2023 |
| Dell          | Inspiron 5490               | [f840248d22](https://linux-hardware.org/?probe=f840248d22) | Feb 13, 2023 |
| Sony          | VPCX11Z6R                   | [ad87a45a26](https://linux-hardware.org/?probe=ad87a45a26) | Feb 12, 2023 |
| Packard Be... | DOT S                       | [1f57142ffd](https://linux-hardware.org/?probe=1f57142ffd) | Feb 12, 2023 |
| Dell          | Latitude E5450              | [693f8c9c36](https://linux-hardware.org/?probe=693f8c9c36) | Feb 11, 2023 |
| HP            | Compaq Presario A900        | [d3c4a9e1e6](https://linux-hardware.org/?probe=d3c4a9e1e6) | Feb 09, 2023 |
| Lenovo        | ThinkPad T430s 23562Z3      | [7338d8375a](https://linux-hardware.org/?probe=7338d8375a) | Feb 09, 2023 |
| Acer          | Extensa 5635ZG              | [dd22b216a9](https://linux-hardware.org/?probe=dd22b216a9) | Feb 08, 2023 |
| HONOR         | NMH-WCX9                    | [d5bb6335d4](https://linux-hardware.org/?probe=d5bb6335d4) | Feb 08, 2023 |
| Acer          | Aspire E5-572G              | [f44e9ce856](https://linux-hardware.org/?probe=f44e9ce856) | Feb 08, 2023 |
| Lenovo        | ThinkPad T440p 20AN006NU... | [e3bd76eeaf](https://linux-hardware.org/?probe=e3bd76eeaf) | Feb 07, 2023 |
| Dell          | Latitude D430               | [0c1ad39f32](https://linux-hardware.org/?probe=0c1ad39f32) | Feb 06, 2023 |
| Insyde        | CherryTrail                 | [cb02cfc77c](https://linux-hardware.org/?probe=cb02cfc77c) | Feb 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S6C... | [262dfe3aa9](https://linux-hardware.org/?probe=262dfe3aa9) | Feb 05, 2023 |
| Intel         | Unknown                     | [f12482330f](https://linux-hardware.org/?probe=f12482330f) | Feb 05, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | [a645368e82](https://linux-hardware.org/?probe=a645368e82) | Feb 04, 2023 |
| HP            | 250 G7 Notebook PC          | [9c9aa5e0e0](https://linux-hardware.org/?probe=9c9aa5e0e0) | Feb 03, 2023 |
| HP            | 240 G3                      | [43e56d3ae5](https://linux-hardware.org/?probe=43e56d3ae5) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [ccf7f4d126](https://linux-hardware.org/?probe=ccf7f4d126) | Feb 03, 2023 |
| HP            | Compaq Presario CQ60        | [c6d48c9847](https://linux-hardware.org/?probe=c6d48c9847) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [fafb999b1a](https://linux-hardware.org/?probe=fafb999b1a) | Feb 03, 2023 |
| HP            | 250 G7 Notebook PC          | [50076364b8](https://linux-hardware.org/?probe=50076364b8) | Feb 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [0211cbb448](https://linux-hardware.org/?probe=0211cbb448) | Feb 03, 2023 |
| HUAWEI        | NBD-WXX9                    | [17b77b89e5](https://linux-hardware.org/?probe=17b77b89e5) | Feb 03, 2023 |
| ECS           | SF20PA2                     | [30df19ca2e](https://linux-hardware.org/?probe=30df19ca2e) | Feb 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | Latitude D630               | [d8ac695aa3](https://linux-hardware.org/?probe=d8ac695aa3) | Jan 31, 2023 |
| HP            | 240 G8 Notebook PC          | [00a3607d18](https://linux-hardware.org/?probe=00a3607d18) | Jan 30, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [c93d5da3f1](https://linux-hardware.org/?probe=c93d5da3f1) | Jan 28, 2023 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [f409b1df0b](https://linux-hardware.org/?probe=f409b1df0b) | Jan 27, 2023 |
| Philco        | 14E                         | [1c069ed627](https://linux-hardware.org/?probe=1c069ed627) | Jan 27, 2023 |
| Philco        | 14E                         | [cfb283e599](https://linux-hardware.org/?probe=cfb283e599) | Jan 27, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [cf42b2f763](https://linux-hardware.org/?probe=cf42b2f763) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| ASUSTek       | X541UVK                     | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| Lenovo        | E41-25 81FS                 | [6de2ea7d90](https://linux-hardware.org/?probe=6de2ea7d90) | Jan 26, 2023 |
| Packard Be... | EasyNote TK87               | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad T430u 3353A11      | [34e69693d1](https://linux-hardware.org/?probe=34e69693d1) | Jan 25, 2023 |
| Acer          | Aspire 5920G                | [89a2c7dc0f](https://linux-hardware.org/?probe=89a2c7dc0f) | Jan 24, 2023 |
| Dell          | Inspiron 3541               | [12d8081c29](https://linux-hardware.org/?probe=12d8081c29) | Jan 23, 2023 |
| Notebook      | W65_67SZ                    | [74d788dccb](https://linux-hardware.org/?probe=74d788dccb) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | [8d876754f3](https://linux-hardware.org/?probe=8d876754f3) | Jan 23, 2023 |
| Apple         | MacBook4,1                  | [f1f61785e5](https://linux-hardware.org/?probe=f1f61785e5) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S4BY00    | [873bf3c874](https://linux-hardware.org/?probe=873bf3c874) | Jan 22, 2023 |
| Lenovo        | ThinkPad E480 20KNCTO1WW    | [68ff3c02cb](https://linux-hardware.org/?probe=68ff3c02cb) | Jan 22, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [82c74e5cca](https://linux-hardware.org/?probe=82c74e5cca) | Jan 21, 2023 |
| Acer          | Aspire 1640                 | [fb70812654](https://linux-hardware.org/?probe=fb70812654) | Jan 21, 2023 |
| ASUSTek       | N53SN                       | [bc8c82ca9a](https://linux-hardware.org/?probe=bc8c82ca9a) | Jan 21, 2023 |
| Dell          | Inspiron 5391               | [050e28c342](https://linux-hardware.org/?probe=050e28c342) | Jan 20, 2023 |
| Dell          | Venue 11 Pro 7139           | [6c3528d4c0](https://linux-hardware.org/?probe=6c3528d4c0) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [76ab21d17b](https://linux-hardware.org/?probe=76ab21d17b) | Jan 20, 2023 |
| HP            | Stream Laptop 11-ah0XX      | [6c83597890](https://linux-hardware.org/?probe=6c83597890) | Jan 19, 2023 |
| Dell          | Inspiron N5110              | [fd8b8416ea](https://linux-hardware.org/?probe=fd8b8416ea) | Jan 19, 2023 |
| Acer          | Aspire A517-51G             | [80712a04ec](https://linux-hardware.org/?probe=80712a04ec) | Jan 18, 2023 |
| Dell          | Latitude E6440              | [f2b34c7c46](https://linux-hardware.org/?probe=f2b34c7c46) | Jan 17, 2023 |
| Dell          | Inspiron N4010              | [7d03111ac0](https://linux-hardware.org/?probe=7d03111ac0) | Jan 16, 2023 |
| ASUSTek       | UX305CA                     | [b831308d6c](https://linux-hardware.org/?probe=b831308d6c) | Jan 16, 2023 |
| Dell          | Latitude E6420              | [3594f88292](https://linux-hardware.org/?probe=3594f88292) | Jan 15, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [251a926c19](https://linux-hardware.org/?probe=251a926c19) | Jan 14, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | [558f3d0d93](https://linux-hardware.org/?probe=558f3d0d93) | Jan 14, 2023 |
| ASUSTek       | A7K                         | [1303f158ab](https://linux-hardware.org/?probe=1303f158ab) | Jan 13, 2023 |
| Notebook      | NJx0MU                      | [b3711a9adc](https://linux-hardware.org/?probe=b3711a9adc) | Jan 13, 2023 |
| Sony          | VPCEB3L9E                   | [5a7ea474fd](https://linux-hardware.org/?probe=5a7ea474fd) | Jan 11, 2023 |
| ASUSTek       | X555YI                      | [4968e51e0b](https://linux-hardware.org/?probe=4968e51e0b) | Jan 10, 2023 |
| Acer          | Aspire E5-771               | [dc397ff7f7](https://linux-hardware.org/?probe=dc397ff7f7) | Jan 09, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | [2f9ff5256a](https://linux-hardware.org/?probe=2f9ff5256a) | Jan 08, 2023 |
| HP            | Pavilion dv2000 (RX554LA... | [b952438f2c](https://linux-hardware.org/?probe=b952438f2c) | Jan 08, 2023 |
| Toshiba       | NB205                       | [3d6ba0d0b3](https://linux-hardware.org/?probe=3d6ba0d0b3) | Jan 07, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [daca90b2bb](https://linux-hardware.org/?probe=daca90b2bb) | Jan 05, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [74bacb92f5](https://linux-hardware.org/?probe=74bacb92f5) | Jan 05, 2023 |
| Dell          | Latitude 5590               | [f32e1efdef](https://linux-hardware.org/?probe=f32e1efdef) | Jan 05, 2023 |
| Samsung       | R530/R730                   | [dd26df5f4f](https://linux-hardware.org/?probe=dd26df5f4f) | Jan 05, 2023 |
| Dell          | Latitude E6420              | [0ac727d853](https://linux-hardware.org/?probe=0ac727d853) | Jan 03, 2023 |
| Dell          | Inspiron 5423               | [14aa07b144](https://linux-hardware.org/?probe=14aa07b144) | Jan 02, 2023 |
| Dell          | Inspiron 5423               | [0c30f220cb](https://linux-hardware.org/?probe=0c30f220cb) | Jan 02, 2023 |
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
| Unknown       | OA Q-ONE BRAND_V2.0         | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [af18889189](https://linux-hardware.org/?probe=af18889189) | Dec 23, 2022 |
| ASUSTek       | G60JX                       | [5e9b0bb890](https://linux-hardware.org/?probe=5e9b0bb890) | Dec 23, 2022 |
| Clevo         | P170EM                      | [3c8b8bd784](https://linux-hardware.org/?probe=3c8b8bd784) | Dec 22, 2022 |
| ASUSTek       | X555LF                      | [bed000b293](https://linux-hardware.org/?probe=bed000b293) | Dec 22, 2022 |
| Acer          | Aspire A114-31              | [850c0c4a65](https://linux-hardware.org/?probe=850c0c4a65) | Dec 22, 2022 |
| ASUSTek       | 1215P                       | [a39ca1c22f](https://linux-hardware.org/?probe=a39ca1c22f) | Dec 21, 2022 |
| ASUSTek       | 1215P                       | [ed3dc80f1b](https://linux-hardware.org/?probe=ed3dc80f1b) | Dec 21, 2022 |
| Dell          | Latitude E5450              | [652099945b](https://linux-hardware.org/?probe=652099945b) | Dec 21, 2022 |
| HP            | Pavilion dv7                | [075b40bb9e](https://linux-hardware.org/?probe=075b40bb9e) | Dec 21, 2022 |
| Google        | Auron_Yuna                  | [827696b95a](https://linux-hardware.org/?probe=827696b95a) | Dec 21, 2022 |
| Acer          | Aspire 7730ZG               | [bf9325456e](https://linux-hardware.org/?probe=bf9325456e) | Dec 20, 2022 |
| Dell          | Latitude E6430              | [643c90d5e1](https://linux-hardware.org/?probe=643c90d5e1) | Dec 20, 2022 |
| Dell          | Latitude E6430              | [ba280c7787](https://linux-hardware.org/?probe=ba280c7787) | Dec 20, 2022 |
| Lenovo        | ThinkPad Edge E545 20B20... | [0293f9b7c3](https://linux-hardware.org/?probe=0293f9b7c3) | Dec 20, 2022 |
| Sony          | VPCS12V9E                   | [a353c5ef57](https://linux-hardware.org/?probe=a353c5ef57) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [224bdb435d](https://linux-hardware.org/?probe=224bdb435d) | Dec 19, 2022 |
| ASUSTek       | K75VJ                       | [a1b40660b5](https://linux-hardware.org/?probe=a1b40660b5) | Dec 18, 2022 |
| Acer          | Aspire A317-51K             | [b02c6dccc2](https://linux-hardware.org/?probe=b02c6dccc2) | Dec 17, 2022 |
| Toshiba       | Satellite M70               | [9415a97254](https://linux-hardware.org/?probe=9415a97254) | Dec 16, 2022 |
| HUAWEI        | HVY-WXX9                    | [5c6f8cd52d](https://linux-hardware.org/?probe=5c6f8cd52d) | Dec 16, 2022 |
| Toshiba       | Satellite M70               | [79506873c1](https://linux-hardware.org/?probe=79506873c1) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | [87603a034e](https://linux-hardware.org/?probe=87603a034e) | Dec 15, 2022 |
| ECS           | CMPC                        | [53d853228f](https://linux-hardware.org/?probe=53d853228f) | Dec 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [a9505fa3e4](https://linux-hardware.org/?probe=a9505fa3e4) | Dec 12, 2022 |
| HP            | Pavilion Laptop 15-cc5xx    | [0cc39aa03c](https://linux-hardware.org/?probe=0cc39aa03c) | Dec 12, 2022 |
| HP            | 350 G1                      | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Fusion5       | Lapbook T90B                | [73a67d82fd](https://linux-hardware.org/?probe=73a67d82fd) | Dec 10, 2022 |
| HP            | 250 G5 Notebook PC          | [aca71547f1](https://linux-hardware.org/?probe=aca71547f1) | Dec 08, 2022 |
| Acer          | Aspire 5935                 | [01da97dae6](https://linux-hardware.org/?probe=01da97dae6) | Dec 07, 2022 |
| ASUSTek       | UX31E                       | [e0de9de530](https://linux-hardware.org/?probe=e0de9de530) | Dec 07, 2022 |
| Acer          | Aspire 5935                 | [44895b82f9](https://linux-hardware.org/?probe=44895b82f9) | Dec 05, 2022 |
| ASUSTek       | K53SC                       | [57e7bb2427](https://linux-hardware.org/?probe=57e7bb2427) | Dec 05, 2022 |
| Apple         | MacBookPro8,1               | [af40c4e286](https://linux-hardware.org/?probe=af40c4e286) | Dec 03, 2022 |
| Dell          | XPS 15 9560                 | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| ASUSTek       | K53SC                       | [6d21dd6cea](https://linux-hardware.org/?probe=6d21dd6cea) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [89e340c4ec](https://linux-hardware.org/?probe=89e340c4ec) | Nov 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [762b81c49e](https://linux-hardware.org/?probe=762b81c49e) | Nov 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [01543655e9](https://linux-hardware.org/?probe=01543655e9) | Nov 29, 2022 |
| Lenovo        | G50-80 80E5                 | [1387bf11ea](https://linux-hardware.org/?probe=1387bf11ea) | Nov 28, 2022 |
| Google        | Akemi                       | [89c466ffd4](https://linux-hardware.org/?probe=89c466ffd4) | Nov 28, 2022 |
| HP            | 255 G8 Notebook PC          | [97cf5008bb](https://linux-hardware.org/?probe=97cf5008bb) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| ASUSTek       | 1002HA                      | [15d5eb998d](https://linux-hardware.org/?probe=15d5eb998d) | Nov 26, 2022 |
| Dell          | Latitude D610               | [437f7630fd](https://linux-hardware.org/?probe=437f7630fd) | Nov 26, 2022 |
| HUAWEI        | BOM-WXX9                    | [59a39475dd](https://linux-hardware.org/?probe=59a39475dd) | Nov 26, 2022 |
| ASUSTek       | 1015CX                      | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [bc3563401b](https://linux-hardware.org/?probe=bc3563401b) | Nov 26, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [46ec8527f5](https://linux-hardware.org/?probe=46ec8527f5) | Nov 25, 2022 |
| Positivo      | Mobile                      | [609b7ff8c9](https://linux-hardware.org/?probe=609b7ff8c9) | Nov 22, 2022 |
| Positivo      | Mobile                      | [5e1d512269](https://linux-hardware.org/?probe=5e1d512269) | Nov 22, 2022 |
| Unknown       | Unknown                     | [c119fbb804](https://linux-hardware.org/?probe=c119fbb804) | Nov 22, 2022 |
| HP            | 8540w                       | [3712bfe3cb](https://linux-hardware.org/?probe=3712bfe3cb) | Nov 21, 2022 |
| Lenovo        | ThinkPad L380 20M6S4E000    | [4f65299a92](https://linux-hardware.org/?probe=4f65299a92) | Nov 20, 2022 |
| Sony          | VPCEH25EN                   | [d9136e5b75](https://linux-hardware.org/?probe=d9136e5b75) | Nov 20, 2022 |
| Dell          | Latitude 5490               | [70b8fb5e89](https://linux-hardware.org/?probe=70b8fb5e89) | Nov 18, 2022 |
| HP            | 245 G8 Notebook PC          | [4d4f9a0e10](https://linux-hardware.org/?probe=4d4f9a0e10) | Nov 17, 2022 |
| Acer          | Aspire A315-21              | [288b53c471](https://linux-hardware.org/?probe=288b53c471) | Nov 16, 2022 |
| Acer          | Aspire A315-21              | [23ec67e81b](https://linux-hardware.org/?probe=23ec67e81b) | Nov 16, 2022 |
| ASUSTek       | K53U                        | [e947ac0aab](https://linux-hardware.org/?probe=e947ac0aab) | Nov 14, 2022 |
| HP            | ProBook 6450b               | [ee3a2a2ef8](https://linux-hardware.org/?probe=ee3a2a2ef8) | Nov 14, 2022 |
| HP            | ProBook 640 G4              | [c120112085](https://linux-hardware.org/?probe=c120112085) | Nov 13, 2022 |
| HP            | Laptop 17-cp0xxx            | [a5575e0c9d](https://linux-hardware.org/?probe=a5575e0c9d) | Nov 12, 2022 |
| HP            | Laptop 17-cp0xxx            | [2e6b12e93d](https://linux-hardware.org/?probe=2e6b12e93d) | Nov 12, 2022 |
| HP            | Pavilion g6                 | [dc20b80b34](https://linux-hardware.org/?probe=dc20b80b34) | Nov 12, 2022 |
| HP            | EliteBook 840 G3            | [161b81845e](https://linux-hardware.org/?probe=161b81845e) | Nov 11, 2022 |
| Lenovo        | ThinkPad T450s 20BWS33U0... | [ce3e5599ad](https://linux-hardware.org/?probe=ce3e5599ad) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [9fa4176934](https://linux-hardware.org/?probe=9fa4176934) | Nov 09, 2022 |
| Lenovo        | IdeaPad 110-17ACL 80UM      | [0a1efcf166](https://linux-hardware.org/?probe=0a1efcf166) | Nov 08, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [a39cc50a9a](https://linux-hardware.org/?probe=a39cc50a9a) | Nov 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN0033R... | [7ca892ad44](https://linux-hardware.org/?probe=7ca892ad44) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | [0eef83e969](https://linux-hardware.org/?probe=0eef83e969) | Nov 06, 2022 |
| Lenovo        | ThinkPad Edge E431 6277C... | [3268b6af5f](https://linux-hardware.org/?probe=3268b6af5f) | Nov 06, 2022 |
| HP            | EliteBook Folio 1040 G1     | [f2d6eec645](https://linux-hardware.org/?probe=f2d6eec645) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [f1117abc19](https://linux-hardware.org/?probe=f1117abc19) | Nov 05, 2022 |
| Lenovo        | ThinkPad P51 20HH0014IX     | [e519495581](https://linux-hardware.org/?probe=e519495581) | Nov 04, 2022 |
| Dell          | Inspiron 15-3567            | [dab31889f1](https://linux-hardware.org/?probe=dab31889f1) | Nov 04, 2022 |
| Apple         | MacBookAir6,2               | [fa6ec2e89c](https://linux-hardware.org/?probe=fa6ec2e89c) | Nov 03, 2022 |
| Dell          | Inspiron 7501               | [3eae1f74ca](https://linux-hardware.org/?probe=3eae1f74ca) | Nov 03, 2022 |
| Dell          | Precision M6400             | [b98b318067](https://linux-hardware.org/?probe=b98b318067) | Nov 02, 2022 |
| Acer          | Aspire one 1-431            | [09aeb9ec38](https://linux-hardware.org/?probe=09aeb9ec38) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [411f4cbf40](https://linux-hardware.org/?probe=411f4cbf40) | Oct 30, 2022 |
| Lenovo        | ThinkPad W530 2438CTO       | [1915c9d3b0](https://linux-hardware.org/?probe=1915c9d3b0) | Oct 28, 2022 |
| Dell          | Inspiron 5490               | [bbea359211](https://linux-hardware.org/?probe=bbea359211) | Oct 28, 2022 |
| Dell          | Latitude E6510              | [2cb824b444](https://linux-hardware.org/?probe=2cb824b444) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [73d5bfb13a](https://linux-hardware.org/?probe=73d5bfb13a) | Oct 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7290786792](https://linux-hardware.org/?probe=7290786792) | Oct 26, 2022 |
| Dell          | Latitude E6510              | [ddb0a31443](https://linux-hardware.org/?probe=ddb0a31443) | Oct 26, 2022 |
| Dell          | Inspiron 3421               | [6ebaad0374](https://linux-hardware.org/?probe=6ebaad0374) | Oct 25, 2022 |
| Lenovo        | ThinkPad T460 20FMS08H00    | [13422369f7](https://linux-hardware.org/?probe=13422369f7) | Oct 25, 2022 |
| ASUSTek       | X555YI                      | [5d6562117a](https://linux-hardware.org/?probe=5d6562117a) | Oct 25, 2022 |
| Dell          | Inspiron N5030              | [dbc717a299](https://linux-hardware.org/?probe=dbc717a299) | Oct 25, 2022 |
| Dell          | Inspiron 3421               | [d10106fb33](https://linux-hardware.org/?probe=d10106fb33) | Oct 24, 2022 |
| Apple         | MacBookPro6,2               | [927bfd543c](https://linux-hardware.org/?probe=927bfd543c) | Oct 24, 2022 |
| Toshiba       | Satellite C75D-B            | [3e39042f59](https://linux-hardware.org/?probe=3e39042f59) | Oct 23, 2022 |
| Toshiba       | Satellite C75D-B            | [b7412d4350](https://linux-hardware.org/?probe=b7412d4350) | Oct 23, 2022 |
| HP            | 15                          | [2831771472](https://linux-hardware.org/?probe=2831771472) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [66418dda52](https://linux-hardware.org/?probe=66418dda52) | Oct 22, 2022 |
| ASUSTek       | N551ZU                      | [090ebd8eee](https://linux-hardware.org/?probe=090ebd8eee) | Oct 20, 2022 |
| Acer          | Predator PH517-61           | [6f191c90c1](https://linux-hardware.org/?probe=6f191c90c1) | Oct 20, 2022 |
| Acer          | Aspire ES1-331              | [f5ace96d5d](https://linux-hardware.org/?probe=f5ace96d5d) | Oct 19, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [4de39d4a1c](https://linux-hardware.org/?probe=4de39d4a1c) | Oct 19, 2022 |
| HP            | Pavilion Notebook           | [e09755f495](https://linux-hardware.org/?probe=e09755f495) | Oct 18, 2022 |
| Dell          | 500                         | [91b78b800a](https://linux-hardware.org/?probe=91b78b800a) | Oct 17, 2022 |
| Dell          | Latitude E5270              | [6f07cdee36](https://linux-hardware.org/?probe=6f07cdee36) | Oct 17, 2022 |
| Samsung       | NC10                        | [1ea93f5095](https://linux-hardware.org/?probe=1ea93f5095) | Oct 16, 2022 |
| MSI           | GS40 6QE Phantom            | [76a55aa9f5](https://linux-hardware.org/?probe=76a55aa9f5) | Oct 14, 2022 |
| Lenovo        | ThinkPad T490 20N20046US    | [a698e6de4d](https://linux-hardware.org/?probe=a698e6de4d) | Oct 13, 2022 |
| eMachines     | eME528                      | [502802d50d](https://linux-hardware.org/?probe=502802d50d) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | Stream Notebook PC 13       | [173cd34bf9](https://linux-hardware.org/?probe=173cd34bf9) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [eee260b733](https://linux-hardware.org/?probe=eee260b733) | Oct 12, 2022 |
| Dell          | Latitude E5470              | [3bbb87ee1b](https://linux-hardware.org/?probe=3bbb87ee1b) | Oct 12, 2022 |
| Unknown       | Unknown                     | [a098b893f4](https://linux-hardware.org/?probe=a098b893f4) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| Lenovo        | ThinkPad L520 5017AL3       | [2e43bb8a31](https://linux-hardware.org/?probe=2e43bb8a31) | Oct 10, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [65039e3fdd](https://linux-hardware.org/?probe=65039e3fdd) | Oct 09, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [1be1f8f36e](https://linux-hardware.org/?probe=1be1f8f36e) | Oct 09, 2022 |
| HP            | 255 G1                      | [fc9f63bfb6](https://linux-hardware.org/?probe=fc9f63bfb6) | Oct 08, 2022 |
| ASUSTek       | K50ID                       | [05e82f0dd5](https://linux-hardware.org/?probe=05e82f0dd5) | Oct 08, 2022 |
| GPU Compan... | GWTN116-3                   | [caf9a63020](https://linux-hardware.org/?probe=caf9a63020) | Oct 08, 2022 |
| Acer          | Aspire 5739G                | [9a380f66ea](https://linux-hardware.org/?probe=9a380f66ea) | Oct 08, 2022 |
| Lenovo        | ThinkPad T410 2537AF8       | [06dd00b171](https://linux-hardware.org/?probe=06dd00b171) | Oct 08, 2022 |
| Dell          | Latitude 5411               | [4bb05d639f](https://linux-hardware.org/?probe=4bb05d639f) | Oct 08, 2022 |
| Lenovo        | ThinkPad T460s 20FAS30L0... | [ea6a5c970c](https://linux-hardware.org/?probe=ea6a5c970c) | Oct 07, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [b67d9b67e4](https://linux-hardware.org/?probe=b67d9b67e4) | Oct 06, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [20fb15fcbf](https://linux-hardware.org/?probe=20fb15fcbf) | Oct 06, 2022 |
| GPU Compan... | GWTN116-3                   | [b838d87a4b](https://linux-hardware.org/?probe=b838d87a4b) | Oct 05, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e52b51f87](https://linux-hardware.org/?probe=0e52b51f87) | Oct 05, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dd6693ffa9](https://linux-hardware.org/?probe=dd6693ffa9) | Oct 05, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [986b3c962e](https://linux-hardware.org/?probe=986b3c962e) | Oct 04, 2022 |
| Dell          | Precision 7560              | [877583cc90](https://linux-hardware.org/?probe=877583cc90) | Oct 04, 2022 |
| Dell          | Inspiron 3521               | [50615f4621](https://linux-hardware.org/?probe=50615f4621) | Oct 04, 2022 |
| Acer          | Extensa 5230                | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Dell          | Inspiron 7520               | [8125b49bea](https://linux-hardware.org/?probe=8125b49bea) | Oct 03, 2022 |
| Dell          | 500                         | [83c01aa11f](https://linux-hardware.org/?probe=83c01aa11f) | Oct 01, 2022 |
| Lenovo        | B70-80 80MR                 | [69aec9e100](https://linux-hardware.org/?probe=69aec9e100) | Oct 01, 2022 |
| HP            | Notebook                    | [fec2594d37](https://linux-hardware.org/?probe=fec2594d37) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| Acer          | Aspire A315-55G             | [77605e313d](https://linux-hardware.org/?probe=77605e313d) | Oct 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [025a55eab7](https://linux-hardware.org/?probe=025a55eab7) | Sep 30, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [875b1df312](https://linux-hardware.org/?probe=875b1df312) | Sep 30, 2022 |
| Sony          | SVE1512C6EB                 | [c47a3a5bd7](https://linux-hardware.org/?probe=c47a3a5bd7) | Sep 30, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| Dell          | Latitude 5420               | [36ddd1d6d7](https://linux-hardware.org/?probe=36ddd1d6d7) | Sep 30, 2022 |
| Lenovo        | IdeaPad N585 20179          | [dcdafbbd9b](https://linux-hardware.org/?probe=dcdafbbd9b) | Sep 28, 2022 |
| HP            | Pavilion dv7                | [5479c35130](https://linux-hardware.org/?probe=5479c35130) | Sep 28, 2022 |
| Lenovo        | IdeaPad N585 20179          | [0a8aed635a](https://linux-hardware.org/?probe=0a8aed635a) | Sep 28, 2022 |
| Toshiba       | Satellite Pro R50-C         | [834ef0ec59](https://linux-hardware.org/?probe=834ef0ec59) | Sep 27, 2022 |
| Toshiba       | Satellite Pro R50-C         | [564d385b61](https://linux-hardware.org/?probe=564d385b61) | Sep 27, 2022 |
| Toshiba       | Satellite C650              | [c7920c2e68](https://linux-hardware.org/?probe=c7920c2e68) | Sep 24, 2022 |
| Packard Be... | EasyNote MH45               | [c312580997](https://linux-hardware.org/?probe=c312580997) | Sep 24, 2022 |
| Unknown       | Unknown                     | [63b1596d63](https://linux-hardware.org/?probe=63b1596d63) | Sep 24, 2022 |
| Toshiba       | Satellite C55D-B            | [5b2029b4d3](https://linux-hardware.org/?probe=5b2029b4d3) | Sep 24, 2022 |
| Toshiba       | Satellite A300              | [3f6203e550](https://linux-hardware.org/?probe=3f6203e550) | Sep 24, 2022 |
| Tactus        | GeoBook 140                 | [7d8700d0e1](https://linux-hardware.org/?probe=7d8700d0e1) | Sep 23, 2022 |
| Dell          | Latitude 5411               | [018a9c569a](https://linux-hardware.org/?probe=018a9c569a) | Sep 23, 2022 |
| HP            | EliteBook 840 G3            | [c3a88ed62d](https://linux-hardware.org/?probe=c3a88ed62d) | Sep 22, 2022 |
| Lenovo        | ThinkPad P51s 20HCS00F00    | [5f0dc19f55](https://linux-hardware.org/?probe=5f0dc19f55) | Sep 22, 2022 |
| Lenovo        | ThinkPad T61 7659AB7        | [aa07f9c271](https://linux-hardware.org/?probe=aa07f9c271) | Sep 20, 2022 |
| Lenovo        | ThinkPad T61p 6457A24       | [d98e9a64bd](https://linux-hardware.org/?probe=d98e9a64bd) | Sep 20, 2022 |
| HP            | ProBook 450 G2              | [73c35ad64a](https://linux-hardware.org/?probe=73c35ad64a) | Sep 20, 2022 |
| Dell          | Precision 7750              | [ced8b5a7b2](https://linux-hardware.org/?probe=ced8b5a7b2) | Sep 19, 2022 |
| Lenovo        | ThinkPad X220 42918F6       | [69dda668fc](https://linux-hardware.org/?probe=69dda668fc) | Sep 18, 2022 |
| Acer          | Swift SF314-511             | [914d532c78](https://linux-hardware.org/?probe=914d532c78) | Sep 17, 2022 |
| Dell          | Latitude 7490               | [ce54bcd741](https://linux-hardware.org/?probe=ce54bcd741) | Sep 15, 2022 |
| Dell          | Inspiron 3576               | [02023473b8](https://linux-hardware.org/?probe=02023473b8) | Sep 15, 2022 |
| HP            | Laptop 15-ef1xxx            | [dd55f6960d](https://linux-hardware.org/?probe=dd55f6960d) | Sep 15, 2022 |
| Dell          | Precision 5540              | [229337f709](https://linux-hardware.org/?probe=229337f709) | Sep 13, 2022 |
| HP            | 1000                        | [65024f3d7a](https://linux-hardware.org/?probe=65024f3d7a) | Sep 13, 2022 |
| Dell          | Inspiron 3537               | [afd2b6555e](https://linux-hardware.org/?probe=afd2b6555e) | Sep 12, 2022 |
| ASUSTek       | X453SA                      | [1446eda5e9](https://linux-hardware.org/?probe=1446eda5e9) | Sep 12, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| Dell          | Latitude 9520               | [04188fb6c2](https://linux-hardware.org/?probe=04188fb6c2) | Sep 06, 2022 |
| ASUSTek       | K55VD                       | [c1ca471555](https://linux-hardware.org/?probe=c1ca471555) | Sep 06, 2022 |
| Panasonic     | CF-D1DVA06F3                | [e3cc43135a](https://linux-hardware.org/?probe=e3cc43135a) | Sep 05, 2022 |
| HP            | 255 G7 Notebook PC          | [dd775ffe8f](https://linux-hardware.org/?probe=dd775ffe8f) | Sep 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [1bd6f2ba6f](https://linux-hardware.org/?probe=1bd6f2ba6f) | Sep 04, 2022 |
| Google        | Kip                         | [e92d971d5e](https://linux-hardware.org/?probe=e92d971d5e) | Sep 04, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [059bb72ff2](https://linux-hardware.org/?probe=059bb72ff2) | Sep 03, 2022 |
| Google        | Reks                        | [d88eecb32d](https://linux-hardware.org/?probe=d88eecb32d) | Sep 03, 2022 |
| HP            | EliteBook 2570p             | [506f9da93b](https://linux-hardware.org/?probe=506f9da93b) | Sep 03, 2022 |
| Apple         | MacBookPro16,1              | [8add31fdfe](https://linux-hardware.org/?probe=8add31fdfe) | Sep 02, 2022 |
| Acer          | Aspire A315-31              | [21d3a4bd56](https://linux-hardware.org/?probe=21d3a4bd56) | Sep 02, 2022 |
| Dell          | Latitude E5530 non-vPro     | [7e839a0ef4](https://linux-hardware.org/?probe=7e839a0ef4) | Aug 30, 2022 |
| Acer          | Aspire E5-771G              | [76803c2532](https://linux-hardware.org/?probe=76803c2532) | Aug 30, 2022 |
| Sony          | VPCSB1V9R                   | [b54e74887f](https://linux-hardware.org/?probe=b54e74887f) | Aug 29, 2022 |
| Acer          | Aspire E5-771G              | [52cc79c6d9](https://linux-hardware.org/?probe=52cc79c6d9) | Aug 29, 2022 |
| Dell          | Inspiron N5010              | [b9953ab67e](https://linux-hardware.org/?probe=b9953ab67e) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [f725a87544](https://linux-hardware.org/?probe=f725a87544) | Aug 27, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [d71f12bede](https://linux-hardware.org/?probe=d71f12bede) | Aug 27, 2022 |
| Lenovo        | V340-17IWL 81RG             | [8a689fc0fd](https://linux-hardware.org/?probe=8a689fc0fd) | Aug 27, 2022 |
| Dell          | XPS 13 9380                 | [5bb7561235](https://linux-hardware.org/?probe=5bb7561235) | Aug 25, 2022 |
| Lenovo        | ThinkPad P70 20ERCTO1WW     | [d269aaa456](https://linux-hardware.org/?probe=d269aaa456) | Aug 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [92be7f3368](https://linux-hardware.org/?probe=92be7f3368) | Aug 24, 2022 |
| Acer          | Aspire 5740                 | [5652f2c73d](https://linux-hardware.org/?probe=5652f2c73d) | Aug 24, 2022 |
| Lenovo        | 14w 81MQ000JUS              | [1ff769c6ef](https://linux-hardware.org/?probe=1ff769c6ef) | Aug 23, 2022 |
| Acer          | Unknown                     | [c35afdde00](https://linux-hardware.org/?probe=c35afdde00) | Aug 21, 2022 |
| Lenovo        | ThinkPad X220 4291V1C       | [8ab56e33c4](https://linux-hardware.org/?probe=8ab56e33c4) | Aug 21, 2022 |
| Lenovo        | ThinkPad T480 20L5000BGE    | [dd53f23249](https://linux-hardware.org/?probe=dd53f23249) | Aug 20, 2022 |
| HP            | EliteBook 8540p             | [cdd3dd9925](https://linux-hardware.org/?probe=cdd3dd9925) | Aug 19, 2022 |
| Packard Be... | EasyNote TJ66               | [96c3144e93](https://linux-hardware.org/?probe=96c3144e93) | Aug 19, 2022 |
| ASUSTek       | K53TA                       | [db6525efb3](https://linux-hardware.org/?probe=db6525efb3) | Aug 15, 2022 |
| ASUSTek       | K84C                        | [c19b238bcf](https://linux-hardware.org/?probe=c19b238bcf) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20FAS0Q90... | [644c7518e9](https://linux-hardware.org/?probe=644c7518e9) | Aug 14, 2022 |
| ASUSTek       | X101CH                      | [174bc50211](https://linux-hardware.org/?probe=174bc50211) | Aug 14, 2022 |
| Panasonic     | CF-31XEUAXMF                | [914e54f984](https://linux-hardware.org/?probe=914e54f984) | Aug 13, 2022 |
| Toshiba       | PT10F                       | [08b7dc52a2](https://linux-hardware.org/?probe=08b7dc52a2) | Aug 12, 2022 |
| Mediacom      | SmartBook 14 FullHD - SB... | [5bb07e1a28](https://linux-hardware.org/?probe=5bb07e1a28) | Aug 11, 2022 |
| Dell          | System XPS L502X            | [1453afc507](https://linux-hardware.org/?probe=1453afc507) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| ASUSTek       | K53SC                       | [15522c32d7](https://linux-hardware.org/?probe=15522c32d7) | Aug 06, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| Render        | NOTEBOOK Revision A         | [90a540652f](https://linux-hardware.org/?probe=90a540652f) | Aug 06, 2022 |
| ASUSTek       | 1015CX                      | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [eeff2bac06](https://linux-hardware.org/?probe=eeff2bac06) | Aug 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [32a99db93e](https://linux-hardware.org/?probe=32a99db93e) | Aug 04, 2022 |
| Acer          | Aspire V3-551G              | [8b0237ee5e](https://linux-hardware.org/?probe=8b0237ee5e) | Aug 03, 2022 |
| Lenovo        | ThinkPad T430 23501K1       | [fdd30ffa23](https://linux-hardware.org/?probe=fdd30ffa23) | Aug 03, 2022 |
| Acer          | Aspire V3-551G              | [4b8ed45c90](https://linux-hardware.org/?probe=4b8ed45c90) | Aug 03, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [8aa899fe67](https://linux-hardware.org/?probe=8aa899fe67) | Aug 02, 2022 |
| GMKtec        | NucBox5                     | [5023bc1773](https://linux-hardware.org/?probe=5023bc1773) | Aug 02, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [e512f0884d](https://linux-hardware.org/?probe=e512f0884d) | Aug 01, 2022 |
| Dell          | Inspiron 5748               | [9113ee6d54](https://linux-hardware.org/?probe=9113ee6d54) | Aug 01, 2022 |
| Unknown       | Unknown                     | [50153bd9ff](https://linux-hardware.org/?probe=50153bd9ff) | Aug 01, 2022 |
| HP            | Pavilion dv2600             | [87651d6efc](https://linux-hardware.org/?probe=87651d6efc) | Jul 31, 2022 |
| Unknown       | Unknown                     | [aa0c007709](https://linux-hardware.org/?probe=aa0c007709) | Jul 31, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [745f6815cb](https://linux-hardware.org/?probe=745f6815cb) | Jul 30, 2022 |
| Alienware     | 17 R4                       | [ae2cd7095b](https://linux-hardware.org/?probe=ae2cd7095b) | Jul 29, 2022 |
| Dell          | Vostro 3700                 | [0a4b552d69](https://linux-hardware.org/?probe=0a4b552d69) | Jul 28, 2022 |
| Samsung       | R59P/R60P/R61P              | [d435057109](https://linux-hardware.org/?probe=d435057109) | Jul 28, 2022 |
| Schenker      | WORK (Early 2021)           | [8666cc396a](https://linux-hardware.org/?probe=8666cc396a) | Jul 28, 2022 |
| ASUSTek       | X450CP                      | [dceda2fe9d](https://linux-hardware.org/?probe=dceda2fe9d) | Jul 27, 2022 |
| LG Electro... | LE50-5BC6H1                 | [010123b7d5](https://linux-hardware.org/?probe=010123b7d5) | Jul 26, 2022 |
| Lenovo        | G50-30 80G0                 | [c380d02bbf](https://linux-hardware.org/?probe=c380d02bbf) | Jul 25, 2022 |
| Apple         | MacBookPro12,1              | [4db419918b](https://linux-hardware.org/?probe=4db419918b) | Jul 25, 2022 |
| Toshiba       | NB205                       | [2dd373f150](https://linux-hardware.org/?probe=2dd373f150) | Jul 23, 2022 |
| ASUSTek       | N56VZ                       | [3813cc04d1](https://linux-hardware.org/?probe=3813cc04d1) | Jul 22, 2022 |
| Dell          | Inspiron N5030              | [3ae520c245](https://linux-hardware.org/?probe=3ae520c245) | Jul 22, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| MSI           | U-100 Ver.001               | [b5b7407958](https://linux-hardware.org/?probe=b5b7407958) | Jul 20, 2022 |
| MSI           | U-100 Ver.001               | [819488216f](https://linux-hardware.org/?probe=819488216f) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [75b4088788](https://linux-hardware.org/?probe=75b4088788) | Jul 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [3c2afd2b5e](https://linux-hardware.org/?probe=3c2afd2b5e) | Jul 20, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [2a10c24690](https://linux-hardware.org/?probe=2a10c24690) | Jul 20, 2022 |
| ASUSTek       | FX503VM                     | [47c70e3628](https://linux-hardware.org/?probe=47c70e3628) | Jul 19, 2022 |
| Dell          | Latitude D430               | [7ae462d6f7](https://linux-hardware.org/?probe=7ae462d6f7) | Jul 18, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [117f9a585b](https://linux-hardware.org/?probe=117f9a585b) | Jul 17, 2022 |
| ASUSTek       | U30Jc                       | [3a6a0ec169](https://linux-hardware.org/?probe=3a6a0ec169) | Jul 17, 2022 |
| Lenovo        | ThinkPad W540 20BG001CMN    | [e408c1236c](https://linux-hardware.org/?probe=e408c1236c) | Jul 17, 2022 |
| Acer          | Aspire E1-532               | [13d38a6632](https://linux-hardware.org/?probe=13d38a6632) | Jul 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a6ae556389](https://linux-hardware.org/?probe=a6ae556389) | Jul 16, 2022 |
| Samsung       | R59P/R60P/R61P              | [4773de66cf](https://linux-hardware.org/?probe=4773de66cf) | Jul 15, 2022 |
| ASUSTek       | K53SC                       | [dd45175b9d](https://linux-hardware.org/?probe=dd45175b9d) | Jul 15, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [daf43ce57a](https://linux-hardware.org/?probe=daf43ce57a) | Jul 13, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [4a587952db](https://linux-hardware.org/?probe=4a587952db) | Jul 13, 2022 |
| Apple         | MacBookPro15,3              | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| ASUSTek       | X453MA                      | [da05c4539d](https://linux-hardware.org/?probe=da05c4539d) | Jul 11, 2022 |
| MSI           | GF63 Thin 9RCX              | [f2f3db370a](https://linux-hardware.org/?probe=f2f3db370a) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | [17b90f7a4b](https://linux-hardware.org/?probe=17b90f7a4b) | Jul 10, 2022 |
| HP            | Laptop 14-bw0xx             | [3b8444274b](https://linux-hardware.org/?probe=3b8444274b) | Jul 10, 2022 |
| Lenovo        | ThinkPad W540 20BG001KGE    | [434091ba07](https://linux-hardware.org/?probe=434091ba07) | Jul 10, 2022 |
| Toshiba       | NB205                       | [f4046cb02f](https://linux-hardware.org/?probe=f4046cb02f) | Jul 10, 2022 |
| Acer          | Aspire E5-521               | [7becd2f2df](https://linux-hardware.org/?probe=7becd2f2df) | Jul 10, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [b2d4e91300](https://linux-hardware.org/?probe=b2d4e91300) | Jul 07, 2022 |
| HP            | Notebook                    | [0c64a91465](https://linux-hardware.org/?probe=0c64a91465) | Jul 07, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | [5cff36844a](https://linux-hardware.org/?probe=5cff36844a) | Jul 07, 2022 |
| Lenovo        | G50-70 20351                | [68efa303fa](https://linux-hardware.org/?probe=68efa303fa) | Jul 07, 2022 |
| Chuwi         | FreeBook                    | [3e0b057e38](https://linux-hardware.org/?probe=3e0b057e38) | Jul 07, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [e5bf9b72d0](https://linux-hardware.org/?probe=e5bf9b72d0) | Jul 07, 2022 |
| Acer          | Aspire E5-571               | [2225f70ee7](https://linux-hardware.org/?probe=2225f70ee7) | Jul 06, 2022 |
| Dell          | Inspiron 5593               | [542470182e](https://linux-hardware.org/?probe=542470182e) | Jul 05, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [51b138f349](https://linux-hardware.org/?probe=51b138f349) | Jul 04, 2022 |
| Lenovo        | V330-15IKB 81AX             | [2f915d68e5](https://linux-hardware.org/?probe=2f915d68e5) | Jul 04, 2022 |
| ASUSTek       | K53SC                       | [ef75149636](https://linux-hardware.org/?probe=ef75149636) | Jul 03, 2022 |
| Samsung       | 370E4K                      | [a6512c1606](https://linux-hardware.org/?probe=a6512c1606) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [72289b7641](https://linux-hardware.org/?probe=72289b7641) | Jul 03, 2022 |
| HP            | Mini 210-1100               | [aaa9b86216](https://linux-hardware.org/?probe=aaa9b86216) | Jul 02, 2022 |
| Dell          | 500                         | [040e3cb12c](https://linux-hardware.org/?probe=040e3cb12c) | Jun 30, 2022 |
| HP            | EliteBook 840 G3            | [9ce5b9c45c](https://linux-hardware.org/?probe=9ce5b9c45c) | Jun 30, 2022 |
| Acer          | Aspire E5-521               | [f532d90f38](https://linux-hardware.org/?probe=f532d90f38) | Jun 29, 2022 |
| Standard      | Unknown                     | [1a94acbc05](https://linux-hardware.org/?probe=1a94acbc05) | Jun 29, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [e08493100f](https://linux-hardware.org/?probe=e08493100f) | Jun 29, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DK      | [2fa204d33e](https://linux-hardware.org/?probe=2fa204d33e) | Jun 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [bd4018ed46](https://linux-hardware.org/?probe=bd4018ed46) | Jun 29, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [372d361276](https://linux-hardware.org/?probe=372d361276) | Jun 28, 2022 |
| ASUSTek       | X551MA                      | [9bdb2a5577](https://linux-hardware.org/?probe=9bdb2a5577) | Jun 28, 2022 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [ac9a35e85e](https://linux-hardware.org/?probe=ac9a35e85e) | Jun 27, 2022 |
| HP            | Laptop 15-ef1xxx            | [d0200625ac](https://linux-hardware.org/?probe=d0200625ac) | Jun 27, 2022 |
| Dell          | Inspiron 15-3567            | [e6d22a4d34](https://linux-hardware.org/?probe=e6d22a4d34) | Jun 27, 2022 |
| Standard      | Unknown                     | [93ac825a25](https://linux-hardware.org/?probe=93ac825a25) | Jun 27, 2022 |
| Apple         | MacBookPro1,1               | [feddac03b9](https://linux-hardware.org/?probe=feddac03b9) | Jun 26, 2022 |
| Lenovo        | ThinkPad T420s 417152U      | [cc52ed5e41](https://linux-hardware.org/?probe=cc52ed5e41) | Jun 26, 2022 |
| HP            | Pavilion dv5                | [4009a4fd8c](https://linux-hardware.org/?probe=4009a4fd8c) | Jun 24, 2022 |
| HP            | Laptop 15-ef1xxx            | [1d18aab349](https://linux-hardware.org/?probe=1d18aab349) | Jun 23, 2022 |
| Dell          | Inspiron 5570               | [4a61f83195](https://linux-hardware.org/?probe=4a61f83195) | Jun 23, 2022 |
| MSI           | Modern 15 A5M               | [b648b81eca](https://linux-hardware.org/?probe=b648b81eca) | Jun 23, 2022 |
| Apple         | MacBookPro14,1              | [e9d8c28a34](https://linux-hardware.org/?probe=e9d8c28a34) | Jun 22, 2022 |
| Alienware     | 17 R4                       | [74b66aebc5](https://linux-hardware.org/?probe=74b66aebc5) | Jun 21, 2022 |
| Dell          | Inspiron 15-3567            | [9538654245](https://linux-hardware.org/?probe=9538654245) | Jun 21, 2022 |
| HP            | 15                          | [61e6eddc93](https://linux-hardware.org/?probe=61e6eddc93) | Jun 20, 2022 |
| Google        | Kindred                     | [c12b15c596](https://linux-hardware.org/?probe=c12b15c596) | Jun 17, 2022 |
| Acer          | Aspire 7720                 | [3f098cc493](https://linux-hardware.org/?probe=3f098cc493) | Jun 15, 2022 |
| Dynabook      | TECRA A50-J                 | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| Sony          | VPCSB1V9R                   | [c1490b2a1c](https://linux-hardware.org/?probe=c1490b2a1c) | Jun 14, 2022 |
| HP            | ProBook 445 G7              | [f41d413820](https://linux-hardware.org/?probe=f41d413820) | Jun 13, 2022 |
| Lenovo        | ThinkPad T530 23923MG       | [cf21c4e831](https://linux-hardware.org/?probe=cf21c4e831) | Jun 12, 2022 |
| HP            | 255 G7 Notebook PC          | [0ebaae147d](https://linux-hardware.org/?probe=0ebaae147d) | Jun 12, 2022 |
| GPU Compan... | GWTN141-4                   | [ba579cb383](https://linux-hardware.org/?probe=ba579cb383) | Jun 11, 2022 |
| Matsushita... | CF-W5LWEZZBM                | [380c6df037](https://linux-hardware.org/?probe=380c6df037) | Jun 11, 2022 |
| Packard Be... | EasyNote TK11BZ             | [f9c69ea1c6](https://linux-hardware.org/?probe=f9c69ea1c6) | Jun 11, 2022 |
| Lenovo        | G505 20240                  | [0b0d5e5252](https://linux-hardware.org/?probe=0b0d5e5252) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [565722f81e](https://linux-hardware.org/?probe=565722f81e) | Jun 09, 2022 |
| Lenovo        | ThinkPad X200 7459V2R       | [c36b6d8e2c](https://linux-hardware.org/?probe=c36b6d8e2c) | Jun 09, 2022 |
| GPU Compan... | GWTN116-3                   | [bd0f56a43c](https://linux-hardware.org/?probe=bd0f56a43c) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Acer          | Aspire 7720                 | [640b757bc8](https://linux-hardware.org/?probe=640b757bc8) | Jun 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [674cab9d61](https://linux-hardware.org/?probe=674cab9d61) | Jun 08, 2022 |
| Lenovo        | ThinkPad L380 20M6S4J400    | [dc1bcd1532](https://linux-hardware.org/?probe=dc1bcd1532) | Jun 08, 2022 |
| Acer          | Aspire E5-573               | [bb17805ada](https://linux-hardware.org/?probe=bb17805ada) | Jun 08, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [77a5e1c6f9](https://linux-hardware.org/?probe=77a5e1c6f9) | Jun 08, 2022 |
| Acer          | Aspire 7720                 | [ac4362743a](https://linux-hardware.org/?probe=ac4362743a) | Jun 07, 2022 |
| AMI           | Intel                       | [79b1f29bc4](https://linux-hardware.org/?probe=79b1f29bc4) | Jun 07, 2022 |
| AMI           | Intel                       | [d7746ec6d5](https://linux-hardware.org/?probe=d7746ec6d5) | Jun 07, 2022 |
| Lenovo        | ThinkPad T440s 20AQ009DG... | [c4250d2ee2](https://linux-hardware.org/?probe=c4250d2ee2) | Jun 07, 2022 |
| Fujitsu       | LIFEBOOK U772               | [8dcf195f94](https://linux-hardware.org/?probe=8dcf195f94) | Jun 07, 2022 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [3ee16e0227](https://linux-hardware.org/?probe=3ee16e0227) | Jun 07, 2022 |
| Digma         | EVE 15 C413 ES5059EW        | [26eb7d39e1](https://linux-hardware.org/?probe=26eb7d39e1) | Jun 06, 2022 |
| HP            | Pavilion g7                 | [b31de17368](https://linux-hardware.org/?probe=b31de17368) | Jun 06, 2022 |
| MSI           | PR601/VR603                 | [9763977184](https://linux-hardware.org/?probe=9763977184) | Jun 05, 2022 |
| Chuwi         | GemiBook Pro                | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| Dell          | Inspiron N4010              | [49e472d67e](https://linux-hardware.org/?probe=49e472d67e) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [dfe3e4b66b](https://linux-hardware.org/?probe=dfe3e4b66b) | Jun 02, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [d620bac2cb](https://linux-hardware.org/?probe=d620bac2cb) | Jun 02, 2022 |
| Dell          | Latitude D820               | [8c2336469f](https://linux-hardware.org/?probe=8c2336469f) | Jun 01, 2022 |
| Acer          | Aspire 5740                 | [db6d025d69](https://linux-hardware.org/?probe=db6d025d69) | Jun 01, 2022 |
| Lenovo        | ThinkPad L13 20R4S4WG00     | [14100804b6](https://linux-hardware.org/?probe=14100804b6) | May 31, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [e46a1497d8](https://linux-hardware.org/?probe=e46a1497d8) | May 31, 2022 |
| Dell          | Latitude 5511               | [bc6fd9e79d](https://linux-hardware.org/?probe=bc6fd9e79d) | May 30, 2022 |
| Medion        | E15407                      | [6e457b6abb](https://linux-hardware.org/?probe=6e457b6abb) | May 29, 2022 |
| Medion        | E15407                      | [a0d6c795e7](https://linux-hardware.org/?probe=a0d6c795e7) | May 29, 2022 |
| TUXEDO        | N14xWU                      | [c20d682e14](https://linux-hardware.org/?probe=c20d682e14) | May 29, 2022 |
| TUXEDO        | N14xWU                      | [8711ac9989](https://linux-hardware.org/?probe=8711ac9989) | May 26, 2022 |
| Acer          | Aspire 5740                 | [2c541b20f6](https://linux-hardware.org/?probe=2c541b20f6) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| HP            | Mini 5103                   | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| ASUSTek       | X510UA                      | [51d57b9e53](https://linux-hardware.org/?probe=51d57b9e53) | May 22, 2022 |
| Sony          | VGN-NS21S_S                 | [0c972ad98b](https://linux-hardware.org/?probe=0c972ad98b) | May 21, 2022 |
| HP            | Pavilion dv6000 (RR374EA... | [926749e311](https://linux-hardware.org/?probe=926749e311) | May 21, 2022 |
| Google        | Snappy                      | [c88d27b24a](https://linux-hardware.org/?probe=c88d27b24a) | May 20, 2022 |
| Google        | Snappy                      | [9fc85cd49a](https://linux-hardware.org/?probe=9fc85cd49a) | May 20, 2022 |
| Google        | Snappy                      | [cb9e7730ad](https://linux-hardware.org/?probe=cb9e7730ad) | May 20, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [baed2325d7](https://linux-hardware.org/?probe=baed2325d7) | May 20, 2022 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [086fceea4f](https://linux-hardware.org/?probe=086fceea4f) | May 19, 2022 |
| Lenovo        | ThinkPad E580 20KS001JGE    | [724c06c08c](https://linux-hardware.org/?probe=724c06c08c) | May 19, 2022 |
| Lenovo        | ThinkPad T410 2516CTO       | [e4150ff93b](https://linux-hardware.org/?probe=e4150ff93b) | May 19, 2022 |
| IBM           | ThinkPad T43 2668F5G        | [af59841e31](https://linux-hardware.org/?probe=af59841e31) | May 18, 2022 |
| Dell          | Latitude D610               | [2e945626d4](https://linux-hardware.org/?probe=2e945626d4) | May 17, 2022 |
| Dell          | Latitude D610               | [9ee1df5d0e](https://linux-hardware.org/?probe=9ee1df5d0e) | May 17, 2022 |
| Dell          | Latitude E6410              | [ae757ea3a4](https://linux-hardware.org/?probe=ae757ea3a4) | May 16, 2022 |
| ASUSTek       | UL30A                       | [c121dd37ba](https://linux-hardware.org/?probe=c121dd37ba) | May 16, 2022 |
| ASUSTek       | X101CH                      | [544536b2d8](https://linux-hardware.org/?probe=544536b2d8) | May 16, 2022 |
| ASUSTek       | X101CH                      | [fbcf200ed5](https://linux-hardware.org/?probe=fbcf200ed5) | May 16, 2022 |
| HP            | Mini 110-1100               | [b93ac7c302](https://linux-hardware.org/?probe=b93ac7c302) | May 16, 2022 |
| HP            | Mini 110-1100               | [4a5f85e53d](https://linux-hardware.org/?probe=4a5f85e53d) | May 16, 2022 |
| Dell          | Latitude 5580               | [c2f15d647a](https://linux-hardware.org/?probe=c2f15d647a) | May 15, 2022 |
| Google        | Droid                       | [e938864c93](https://linux-hardware.org/?probe=e938864c93) | May 15, 2022 |
| Lenovo        | ThinkPad X200s 74664SJ      | [65728fda7a](https://linux-hardware.org/?probe=65728fda7a) | May 14, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [a3b1829dec](https://linux-hardware.org/?probe=a3b1829dec) | May 13, 2022 |
| AMI           | Cherry Trail CR             | [62744ba7e3](https://linux-hardware.org/?probe=62744ba7e3) | May 12, 2022 |
| ASUSTek       | A7K                         | [29ca1c7e33](https://linux-hardware.org/?probe=29ca1c7e33) | May 11, 2022 |
| Dell          | Latitude E6410              | [a14c28c93f](https://linux-hardware.org/?probe=a14c28c93f) | May 11, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [bb4a27a023](https://linux-hardware.org/?probe=bb4a27a023) | May 10, 2022 |
| Dell          | Latitude 7400               | [a0600c38f3](https://linux-hardware.org/?probe=a0600c38f3) | May 09, 2022 |
| Unknown       | Unknown                     | [f802e84b8e](https://linux-hardware.org/?probe=f802e84b8e) | May 08, 2022 |
| Lenovo        | ThinkPad X240 20AMS6FF00    | [3e3da41a35](https://linux-hardware.org/?probe=3e3da41a35) | May 08, 2022 |
| Dell          | Latitude E6410              | [361bcaa4cc](https://linux-hardware.org/?probe=361bcaa4cc) | May 07, 2022 |
| Dell          | Inspiron 7501               | [a8a1e1e3a2](https://linux-hardware.org/?probe=a8a1e1e3a2) | May 07, 2022 |
| HP            | Compaq 6820s                | [1ba74fc299](https://linux-hardware.org/?probe=1ba74fc299) | May 07, 2022 |
| HP            | Compaq 6820s                | [5b027deec0](https://linux-hardware.org/?probe=5b027deec0) | May 07, 2022 |
| Toshiba       | Satellite C70D-B            | [fa4a4b7ffc](https://linux-hardware.org/?probe=fa4a4b7ffc) | May 06, 2022 |
| Acer          | Aspire 5740                 | [e754b48e71](https://linux-hardware.org/?probe=e754b48e71) | May 06, 2022 |
| Dell          | Latitude 7420               | [384325350c](https://linux-hardware.org/?probe=384325350c) | May 05, 2022 |
| Google        | Auron_Yuna                  | [795d9af5a7](https://linux-hardware.org/?probe=795d9af5a7) | May 05, 2022 |
| Dell          | XPS M1530                   | [760cae00c1](https://linux-hardware.org/?probe=760cae00c1) | May 03, 2022 |
| ASUSTek       | K53SC                       | [1533323fbf](https://linux-hardware.org/?probe=1533323fbf) | May 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [981f468940](https://linux-hardware.org/?probe=981f468940) | May 02, 2022 |
| Acer          | Aspire 5740                 | [6e1a9ce167](https://linux-hardware.org/?probe=6e1a9ce167) | May 01, 2022 |
| Razer         | Blade Stealth 13 Late 20... | [ba8fa66c1c](https://linux-hardware.org/?probe=ba8fa66c1c) | May 01, 2022 |
| Acer          | Aspire 5740                 | [f9e5dd9719](https://linux-hardware.org/?probe=f9e5dd9719) | May 01, 2022 |
| Dell          | XPS M1530                   | [757d1b099e](https://linux-hardware.org/?probe=757d1b099e) | Apr 30, 2022 |
| ASUSTek       | T100HAN                     | [5ee200cfbe](https://linux-hardware.org/?probe=5ee200cfbe) | Apr 30, 2022 |
| ASUSTek       | K53SC                       | [f2605ba739](https://linux-hardware.org/?probe=f2605ba739) | Apr 29, 2022 |
| Acer          | Aspire ES1-311              | [aa4612575b](https://linux-hardware.org/?probe=aa4612575b) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| Dell          | Inspiron 3135               | [6ca6980f06](https://linux-hardware.org/?probe=6ca6980f06) | Apr 28, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [fc0cea6830](https://linux-hardware.org/?probe=fc0cea6830) | Apr 27, 2022 |
| Acer          | Aspire ES1-512              | [f0ed67e309](https://linux-hardware.org/?probe=f0ed67e309) | Apr 26, 2022 |
| Dell          | Latitude 7480               | [7e85baf2f4](https://linux-hardware.org/?probe=7e85baf2f4) | Apr 26, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [bd286b124a](https://linux-hardware.org/?probe=bd286b124a) | Apr 25, 2022 |
| HP            | 255 G8 Notebook PC          | [c16cb4e0d6](https://linux-hardware.org/?probe=c16cb4e0d6) | Apr 24, 2022 |
| Lenovo        | ThinkPad T440 20B7A0S200    | [0ef99a6615](https://linux-hardware.org/?probe=0ef99a6615) | Apr 24, 2022 |
| ASUSTek       | 1215N                       | [93ad513620](https://linux-hardware.org/?probe=93ad513620) | Apr 24, 2022 |
| Lenovo        | B590 20206                  | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| Lenovo        | ThinkPad T470s 20HF004MM... | [69a5e98a04](https://linux-hardware.org/?probe=69a5e98a04) | Apr 22, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [3e1029ed36](https://linux-hardware.org/?probe=3e1029ed36) | Apr 22, 2022 |
| Dell          | XPS M1530                   | [f22a6a2c55](https://linux-hardware.org/?probe=f22a6a2c55) | Apr 21, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e87dfd05bc](https://linux-hardware.org/?probe=e87dfd05bc) | Apr 20, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [fae46ae55c](https://linux-hardware.org/?probe=fae46ae55c) | Apr 20, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [d277143404](https://linux-hardware.org/?probe=d277143404) | Apr 20, 2022 |
| HP            | 255 G8 Notebook PC          | [d88db86125](https://linux-hardware.org/?probe=d88db86125) | Apr 20, 2022 |
| Dell          | XPS M1530                   | [60d3e4f97f](https://linux-hardware.org/?probe=60d3e4f97f) | Apr 20, 2022 |
| HP            | Compaq 6730s                | [4902d2bf25](https://linux-hardware.org/?probe=4902d2bf25) | Apr 16, 2022 |
| Positivo B... | VJC141F11X-B0111L           | [5ea499eca7](https://linux-hardware.org/?probe=5ea499eca7) | Apr 16, 2022 |
| Dell          | Latitude E6540              | [94fbc5408f](https://linux-hardware.org/?probe=94fbc5408f) | Apr 15, 2022 |
| HP            | Compaq 6730s                | [755dcc7629](https://linux-hardware.org/?probe=755dcc7629) | Apr 15, 2022 |
| Lenovo        | ThinkPad X280 20KE001MMX    | [fb0da9def7](https://linux-hardware.org/?probe=fb0da9def7) | Apr 15, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [554040d7b4](https://linux-hardware.org/?probe=554040d7b4) | Apr 14, 2022 |
| Lenovo        | ThinkPad P53 20QNS01C00     | [b320a8cca8](https://linux-hardware.org/?probe=b320a8cca8) | Apr 14, 2022 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [1f9cb1427a](https://linux-hardware.org/?probe=1f9cb1427a) | Apr 13, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PI... | [53c7e12994](https://linux-hardware.org/?probe=53c7e12994) | Apr 13, 2022 |
| Dynabook      | TECRA X40-F                 | [6d6f37f70e](https://linux-hardware.org/?probe=6d6f37f70e) | Apr 13, 2022 |
| Dell          | Precision 7550              | [624c231f19](https://linux-hardware.org/?probe=624c231f19) | Apr 13, 2022 |
| Lenovo        | IdeaPad Y550 4186           | [0ba7d3b80a](https://linux-hardware.org/?probe=0ba7d3b80a) | Apr 13, 2022 |
| HP            | Laptop 15-bw0xx             | [1c15e67e64](https://linux-hardware.org/?probe=1c15e67e64) | Apr 11, 2022 |
| Dell          | OptiPlex 9020               | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | K53SC                       | [8b6bb16303](https://linux-hardware.org/?probe=8b6bb16303) | Apr 08, 2022 |
| Toshiba       | NB505                       | [55f9f70b0b](https://linux-hardware.org/?probe=55f9f70b0b) | Apr 08, 2022 |
| HP            | ENVY Sleekbook 6 PC         | [2e5d15f716](https://linux-hardware.org/?probe=2e5d15f716) | Apr 08, 2022 |
| HP            | Laptop 15s-fq2xxx           | [b073554afc](https://linux-hardware.org/?probe=b073554afc) | Apr 08, 2022 |
| Dell          | Latitude 5521               | [ce1e3c5551](https://linux-hardware.org/?probe=ce1e3c5551) | Apr 07, 2022 |
| Dell          | MXG061                      | [3ff1cc3367](https://linux-hardware.org/?probe=3ff1cc3367) | Apr 07, 2022 |
| Dell          | Inspiron 11-3162            | [8c348f2f1a](https://linux-hardware.org/?probe=8c348f2f1a) | Apr 07, 2022 |
| HP            | Pavilion dv6500             | [2f18112668](https://linux-hardware.org/?probe=2f18112668) | Apr 04, 2022 |
| Wortmann      | M7x0S                       | [364f9cbe89](https://linux-hardware.org/?probe=364f9cbe89) | Apr 03, 2022 |
| MSI           | GX70 3CC                    | [0b706f83d3](https://linux-hardware.org/?probe=0b706f83d3) | Apr 02, 2022 |
| HP            | Pavilion 15                 | [98be421e4c](https://linux-hardware.org/?probe=98be421e4c) | Apr 02, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c3dcb61dd5](https://linux-hardware.org/?probe=c3dcb61dd5) | Apr 02, 2022 |
| HP            | Laptop 15-ef2xxx            | [a245ae2e74](https://linux-hardware.org/?probe=a245ae2e74) | Mar 29, 2022 |
| Acer          | Aspire one                  | [2b0b231b1a](https://linux-hardware.org/?probe=2b0b231b1a) | Mar 29, 2022 |
| Medion        | Crawler E25                 | [6093396d8a](https://linux-hardware.org/?probe=6093396d8a) | Mar 28, 2022 |
| Dell          | Studio 1450                 | [1b7df0163d](https://linux-hardware.org/?probe=1b7df0163d) | Mar 28, 2022 |
| ASUSTek       | K55VD                       | [5c65461fe1](https://linux-hardware.org/?probe=5c65461fe1) | Mar 28, 2022 |
| Dell          | Vostro 3458                 | [a3cb323822](https://linux-hardware.org/?probe=a3cb323822) | Mar 27, 2022 |
| Dell          | Vostro 3458                 | [9e9df1f902](https://linux-hardware.org/?probe=9e9df1f902) | Mar 27, 2022 |
| Toshiba       | NB505                       | [cab0ce252d](https://linux-hardware.org/?probe=cab0ce252d) | Mar 27, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [5b371c14a6](https://linux-hardware.org/?probe=5b371c14a6) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | [2e6f1e1946](https://linux-hardware.org/?probe=2e6f1e1946) | Mar 25, 2022 |
| GPU Compan... | GWTC116-2                   | [897adf54cc](https://linux-hardware.org/?probe=897adf54cc) | Mar 24, 2022 |
| HP            | Stream 11 Pro G2 Noteboo... | [879788ce4f](https://linux-hardware.org/?probe=879788ce4f) | Mar 24, 2022 |
| ASUSTek       | U31SD                       | [00cff36d3f](https://linux-hardware.org/?probe=00cff36d3f) | Mar 24, 2022 |
| Dell          | Latitude E6400              | [49b4e17d7a](https://linux-hardware.org/?probe=49b4e17d7a) | Mar 22, 2022 |
| ASUSTek       | X501A                       | [5c8c010850](https://linux-hardware.org/?probe=5c8c010850) | Mar 22, 2022 |
| Dell          | Latitude 5510               | [d83be08c5d](https://linux-hardware.org/?probe=d83be08c5d) | Mar 21, 2022 |
| HP            | ZBook 15                    | [303748aa9e](https://linux-hardware.org/?probe=303748aa9e) | Mar 21, 2022 |
| HUAWEI        | KPL-W0X                     | [fbe7d7c6b0](https://linux-hardware.org/?probe=fbe7d7c6b0) | Mar 21, 2022 |
| Dell          | Latitude 7490               | [0799e0955b](https://linux-hardware.org/?probe=0799e0955b) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E6430              | [6503f89ca1](https://linux-hardware.org/?probe=6503f89ca1) | Mar 20, 2022 |
| Samsung       | R510/P510                   | [5ec1b197a4](https://linux-hardware.org/?probe=5ec1b197a4) | Mar 19, 2022 |
| Samsung       | R530/R730/R540              | [17c8c47d7b](https://linux-hardware.org/?probe=17c8c47d7b) | Mar 18, 2022 |
| ASUSTek       | U31SD                       | [63c0093cea](https://linux-hardware.org/?probe=63c0093cea) | Mar 18, 2022 |
| HP            | ZBook 15                    | [c5d326781a](https://linux-hardware.org/?probe=c5d326781a) | Mar 17, 2022 |
| Packard Be... | EasyNote TM85               | [ec7dd9aba3](https://linux-hardware.org/?probe=ec7dd9aba3) | Mar 17, 2022 |
| Toshiba       | NB205                       | [ffef19b228](https://linux-hardware.org/?probe=ffef19b228) | Mar 17, 2022 |
| Acer          | Nitro AN515-42              | [97ebb0ca74](https://linux-hardware.org/?probe=97ebb0ca74) | Mar 16, 2022 |
| Teclast       | F15 Plus                    | [9d3b8151f2](https://linux-hardware.org/?probe=9d3b8151f2) | Mar 16, 2022 |
| Acer          | Aspire 5935                 | [69cae65bf4](https://linux-hardware.org/?probe=69cae65bf4) | Mar 16, 2022 |
| Acer          | Aspire 5935                 | [67a1970f50](https://linux-hardware.org/?probe=67a1970f50) | Mar 16, 2022 |
| Dell          | Inspiron 7437               | [83eed6eaef](https://linux-hardware.org/?probe=83eed6eaef) | Mar 14, 2022 |
| Fujitsu Si... | AMILO Xi 3650               | [6f416ff93b](https://linux-hardware.org/?probe=6f416ff93b) | Mar 13, 2022 |
| HP            | Pavilion dv7                | [7cc5311803](https://linux-hardware.org/?probe=7cc5311803) | Mar 13, 2022 |
| HP            | EliteBook 2540p             | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| Dell          | Inspiron 7520               | [2e4bdb96fa](https://linux-hardware.org/?probe=2e4bdb96fa) | Mar 10, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [4f65353f3e](https://linux-hardware.org/?probe=4f65353f3e) | Mar 10, 2022 |
| Acer          | TP-SW5-012-16UW             | [1558c31a17](https://linux-hardware.org/?probe=1558c31a17) | Mar 09, 2022 |
| Dell          | Latitude E6400              | [bcacefe427](https://linux-hardware.org/?probe=bcacefe427) | Mar 08, 2022 |
| Packard Be... | EasyNote TM85               | [10c87bed94](https://linux-hardware.org/?probe=10c87bed94) | Mar 07, 2022 |
| Packard Be... | EasyNote TM85               | [2b3ba9a762](https://linux-hardware.org/?probe=2b3ba9a762) | Mar 07, 2022 |
| Dell          | Latitude E6400              | [4e626b238b](https://linux-hardware.org/?probe=4e626b238b) | Mar 07, 2022 |
| Acer          | Aspire VN7-572              | [952fd83515](https://linux-hardware.org/?probe=952fd83515) | Mar 06, 2022 |
| HP            | Pavilion dv7                | [97b2a4a508](https://linux-hardware.org/?probe=97b2a4a508) | Mar 05, 2022 |
| ASUSTek       | X555LAB                     | [80be8910f4](https://linux-hardware.org/?probe=80be8910f4) | Mar 05, 2022 |
| ASUSTek       | X450CC                      | [835313a116](https://linux-hardware.org/?probe=835313a116) | Mar 03, 2022 |
| HP            | Pavilion dv7                | [b32286ecad](https://linux-hardware.org/?probe=b32286ecad) | Mar 03, 2022 |
| Lenovo        | B590 20208                  | [4a4fd37e32](https://linux-hardware.org/?probe=4a4fd37e32) | Mar 02, 2022 |
| HP            | Notebook PC                 | [2297e2813f](https://linux-hardware.org/?probe=2297e2813f) | Mar 02, 2022 |
| HP            | Pavilion dv7                | [d3a9235dcb](https://linux-hardware.org/?probe=d3a9235dcb) | Mar 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [4fe25f775d](https://linux-hardware.org/?probe=4fe25f775d) | Mar 01, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | [d88405b0dc](https://linux-hardware.org/?probe=d88405b0dc) | Mar 01, 2022 |
| Lenovo        | ThinkPad X270 20HNS0LW00    | [c781fc668f](https://linux-hardware.org/?probe=c781fc668f) | Mar 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1b5df98df2](https://linux-hardware.org/?probe=1b5df98df2) | Feb 28, 2022 |
| VIT           | P3400                       | [6075d8d8b2](https://linux-hardware.org/?probe=6075d8d8b2) | Feb 28, 2022 |
| Medion        | E16402                      | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Lenovo        | ThinkPad T510 4384VJM       | [19e8d8425e](https://linux-hardware.org/?probe=19e8d8425e) | Feb 26, 2022 |
| HP            | EliteBook 8560p             | [d440e21050](https://linux-hardware.org/?probe=d440e21050) | Feb 26, 2022 |
| Lenovo        | Unknown                     | [8a5df3c23e](https://linux-hardware.org/?probe=8a5df3c23e) | Feb 25, 2022 |
| HP            | 15                          | [fa8d20b53f](https://linux-hardware.org/?probe=fa8d20b53f) | Feb 23, 2022 |
| Dell          | Vostro V130                 | [75b7360134](https://linux-hardware.org/?probe=75b7360134) | Feb 22, 2022 |
| Dell          | Precision 3561              | [d46fbe1d5f](https://linux-hardware.org/?probe=d46fbe1d5f) | Feb 21, 2022 |
| Lenovo        | ThinkPad T410 2522W6G       | [d2b007cb44](https://linux-hardware.org/?probe=d2b007cb44) | Feb 20, 2022 |
| Gateway       | M-6307                      | [7cda83b770](https://linux-hardware.org/?probe=7cda83b770) | Feb 20, 2022 |
| ASUSTek       | X542URR                     | [ee334867a0](https://linux-hardware.org/?probe=ee334867a0) | Feb 19, 2022 |
| Dell          | Inspiron 5593               | [f4bce4423f](https://linux-hardware.org/?probe=f4bce4423f) | Feb 19, 2022 |
| ASUSTek       | A2D                         | [6fbba6195d](https://linux-hardware.org/?probe=6fbba6195d) | Feb 17, 2022 |
| Lenovo        | ThinkPad R500 2716A54       | [9aa87e9270](https://linux-hardware.org/?probe=9aa87e9270) | Feb 17, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [354434e81d](https://linux-hardware.org/?probe=354434e81d) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | [475df3f2af](https://linux-hardware.org/?probe=475df3f2af) | Feb 16, 2022 |
| Dell          | Inspiron 1764               | [177f5aac6c](https://linux-hardware.org/?probe=177f5aac6c) | Feb 16, 2022 |
| Sony          | VPCEB3E1E                   | [a0be8de519](https://linux-hardware.org/?probe=a0be8de519) | Feb 13, 2022 |
| HP            | Stream Notebook PC 13       | [33d5b7046b](https://linux-hardware.org/?probe=33d5b7046b) | Feb 13, 2022 |
| Samsung       | 900X1B                      | [c609dfc310](https://linux-hardware.org/?probe=c609dfc310) | Feb 13, 2022 |
| HP            | ProBook 655 G1              | [1c6a5c6e55](https://linux-hardware.org/?probe=1c6a5c6e55) | Feb 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [935de1698b](https://linux-hardware.org/?probe=935de1698b) | Feb 08, 2022 |
| HP            | ProBook 650 G3              | [54a5c321be](https://linux-hardware.org/?probe=54a5c321be) | Feb 08, 2022 |
| Acer          | TravelMate 8172             | [76e402e3d6](https://linux-hardware.org/?probe=76e402e3d6) | Feb 07, 2022 |
| Lenovo        | ThinkPad W510 431963G       | [a2e027fa38](https://linux-hardware.org/?probe=a2e027fa38) | Feb 07, 2022 |
| ASUSTek       | K73SV                       | [d02cd235da](https://linux-hardware.org/?probe=d02cd235da) | Feb 06, 2022 |
| Acer          | Aspire 5100                 | [191eb6224a](https://linux-hardware.org/?probe=191eb6224a) | Feb 06, 2022 |
| IBM           | ThinkPad T43 2668BU7        | [2586bf5e87](https://linux-hardware.org/?probe=2586bf5e87) | Feb 06, 2022 |
| Lenovo        | ThinkPad L480 20LS001AMD    | [801aa8fb1e](https://linux-hardware.org/?probe=801aa8fb1e) | Feb 05, 2022 |
| HP            | EliteBook 8530p             | [a2fc96b3dc](https://linux-hardware.org/?probe=a2fc96b3dc) | Feb 05, 2022 |
| Dell          | Latitude E5450              | [84845ef09c](https://linux-hardware.org/?probe=84845ef09c) | Feb 04, 2022 |
| HP            | Pavilion 17                 | [f0d4a99870](https://linux-hardware.org/?probe=f0d4a99870) | Feb 04, 2022 |
| Dell          | Latitude E5450              | [fc7d07dba8](https://linux-hardware.org/?probe=fc7d07dba8) | Feb 04, 2022 |
| HP            | Compaq nc6320 (RH374EA#A... | [9359d0a8af](https://linux-hardware.org/?probe=9359d0a8af) | Feb 04, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [44efd2d456](https://linux-hardware.org/?probe=44efd2d456) | Feb 03, 2022 |
| Lenovo        | ThinkPad Edge 0301FAG       | [2e33681926](https://linux-hardware.org/?probe=2e33681926) | Feb 03, 2022 |
| Fujitsu       | LIFEBOOK E734               | [28280d252b](https://linux-hardware.org/?probe=28280d252b) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [bba0be98c7](https://linux-hardware.org/?probe=bba0be98c7) | Feb 01, 2022 |
| HP            | EliteBook 725 G2            | [d49dd26324](https://linux-hardware.org/?probe=d49dd26324) | Feb 01, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [460a295f83](https://linux-hardware.org/?probe=460a295f83) | Jan 30, 2022 |
| Gateway       | MT6831                      | [36947a389a](https://linux-hardware.org/?probe=36947a389a) | Jan 30, 2022 |
| HP            | EliteBook 745 G3            | [20e43b8b53](https://linux-hardware.org/?probe=20e43b8b53) | Jan 29, 2022 |
| Acer          | AOD257                      | [4d8476adb1](https://linux-hardware.org/?probe=4d8476adb1) | Jan 29, 2022 |
| ASUSTek       | TP500LA                     | [e18b673cd3](https://linux-hardware.org/?probe=e18b673cd3) | Jan 28, 2022 |
| Dell          | Latitude E6510              | [a571bdc501](https://linux-hardware.org/?probe=a571bdc501) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | [c969e228f3](https://linux-hardware.org/?probe=c969e228f3) | Jan 28, 2022 |
| Dell          | Studio 1450                 | [9c2bf5854d](https://linux-hardware.org/?probe=9c2bf5854d) | Jan 28, 2022 |
| Fujitsu       | LIFEBOOK E734               | [3e66e21a1e](https://linux-hardware.org/?probe=3e66e21a1e) | Jan 28, 2022 |
| Dell          | Latitude D630               | [8a0a5b89dd](https://linux-hardware.org/?probe=8a0a5b89dd) | Jan 27, 2022 |
| Dell          | Latitude D630               | [321264426f](https://linux-hardware.org/?probe=321264426f) | Jan 26, 2022 |
| ASUSTek       | N56VZ                       | [6f1b0cf9e0](https://linux-hardware.org/?probe=6f1b0cf9e0) | Jan 26, 2022 |
| HP            | G42                         | [3d3f5f2d07](https://linux-hardware.org/?probe=3d3f5f2d07) | Jan 25, 2022 |
| HP            | ENVY Laptop 17-ch1xxx       | [e932911cde](https://linux-hardware.org/?probe=e932911cde) | Jan 25, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | [a97c44b274](https://linux-hardware.org/?probe=a97c44b274) | Jan 25, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Xubuntu 20.04        | 1031      | 43.28%  |
| Xubuntu 18.04        | 603       | 25.31%  |
| Xubuntu 22.04        | 342       | 14.36%  |
| Xubuntu 19.10        | 110       | 4.62%   |
| Xubuntu 21.10        | 57        | 2.39%   |
| Xubuntu 16.04        | 48        | 2.02%   |
| Xubuntu 21.04        | 42        | 1.76%   |
| Xubuntu 20.10        | 42        | 1.76%   |
| Xubuntu 23.04        | 34        | 1.43%   |
| Xubuntu 22.10        | 30        | 1.26%   |
| Xubuntu 19.04        | 13        | 0.55%   |
| Xubuntu 23.10        | 6         | 0.25%   |
| Xubuntu 18.10        | 6         | 0.25%   |
| Xubuntu 17.10        | 6         | 0.25%   |
| Xubuntu              | 4         | 0.17%   |
| Xubuntu 14.04        | 3         | 0.13%   |
| Xubuntu 2023.2       | 2         | 0.08%   |
| Xubuntu 17.04        | 2         | 0.08%   |
| Xubuntu 2023.1-beta5 | 1         | 0.04%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Xubuntu | 2313      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Notebooks | Percent |
|---------------------|-----------|---------|
| 5.4.0-42-generic    | 87        | 3.23%   |
| 5.3.0-46-generic    | 41        | 1.52%   |
| 5.11.0-27-generic   | 39        | 1.45%   |
| 5.4.0-58-generic    | 34        | 1.26%   |
| 5.4.0-47-generic    | 31        | 1.15%   |
| 5.4.0-52-generic    | 30        | 1.11%   |
| 5.4.0-29-generic    | 30        | 1.11%   |
| 5.4.0-48-generic    | 28        | 1.04%   |
| 5.4.0-65-generic    | 27        | 1%      |
| 5.3.0-40-generic    | 27        | 1%      |
| 5.15.0-56-generic   | 27        | 1%      |
| 5.3.0-42-generic    | 26        | 0.96%   |
| 5.4.0-54-generic    | 25        | 0.93%   |
| 5.3.0-51-generic    | 22        | 0.82%   |
| 5.4.0-31-generic    | 21        | 0.78%   |
| 5.0.0-37-generic    | 21        | 0.78%   |
| 5.4.0-40-generic    | 20        | 0.74%   |
| 5.15.0-58-generic   | 20        | 0.74%   |
| 5.3.0-28-generic    | 19        | 0.7%    |
| 5.15.0-52-generic   | 19        | 0.7%    |
| 5.15.0-47-generic   | 19        | 0.7%    |
| 4.15.0-99-generic   | 19        | 0.7%    |
| 5.4.0-42-lowlatency | 18        | 0.67%   |
| 5.3.0-53-generic    | 18        | 0.67%   |
| 5.15.0-48-generic   | 18        | 0.67%   |
| 5.4.0-89-generic    | 17        | 0.63%   |
| 5.4.0-66-generic    | 17        | 0.63%   |
| 5.4.0-26-generic    | 17        | 0.63%   |
| 5.4.0-67-generic    | 16        | 0.59%   |
| 5.4.0-53-generic    | 16        | 0.59%   |
| 5.4.0-37-generic    | 16        | 0.59%   |
| 5.13.0-39-generic   | 16        | 0.59%   |
| 5.13.0-30-generic   | 16        | 0.59%   |
| 6.2.0-26-generic    | 15        | 0.56%   |
| 5.8.0-53-generic    | 15        | 0.56%   |
| 5.8.0-43-generic    | 15        | 0.56%   |
| 5.4.0-56-generic    | 15        | 0.56%   |
| 5.4.0-72-generic    | 14        | 0.52%   |
| 5.4.0-60-generic    | 14        | 0.52%   |
| 5.4.0-33-generic    | 14        | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 834       | 34.34%  |
| 5.15.0  | 276       | 11.36%  |
| 5.3.0   | 258       | 10.62%  |
| 4.15.0  | 248       | 10.21%  |
| 5.11.0  | 167       | 6.88%   |
| 5.13.0  | 133       | 5.48%   |
| 5.8.0   | 132       | 5.43%   |
| 5.19.0  | 86        | 3.54%   |
| 6.2.0   | 71        | 2.92%   |
| 5.0.0   | 57        | 2.35%   |
| 4.4.0   | 26        | 1.07%   |
| 4.18.0  | 14        | 0.58%   |
| 5.17.0  | 10        | 0.41%   |
| 4.13.0  | 7         | 0.29%   |
| 6.5.0   | 6         | 0.25%   |
| 5.10.0  | 5         | 0.21%   |
| 6.1.0   | 4         | 0.16%   |
| 5.14.0  | 4         | 0.16%   |
| 5.6.0   | 3         | 0.12%   |
| 5.4.217 | 3         | 0.12%   |
| 5.18.0  | 3         | 0.12%   |
| 6.0.9   | 2         | 0.08%   |
| 6.0.0   | 2         | 0.08%   |
| 5.6.19  | 2         | 0.08%   |
| 5.5.19  | 2         | 0.08%   |
| 5.11.11 | 2         | 0.08%   |
| 4.8.0   | 2         | 0.08%   |
| 4.4.254 | 2         | 0.08%   |
| 4.11.0  | 2         | 0.08%   |
| 4.10.0  | 2         | 0.08%   |
| 6.5.1   | 1         | 0.04%   |
| 6.4.2   | 1         | 0.04%   |
| 6.4.15  | 1         | 0.04%   |
| 6.4.0   | 1         | 0.04%   |
| 6.3.2   | 1         | 0.04%   |
| 6.2.2   | 1         | 0.04%   |
| 6.1.6   | 1         | 0.04%   |
| 6.0.7   | 1         | 0.04%   |
| 5.9.8   | 1         | 0.04%   |
| 5.9.6   | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 841       | 34.64%  |
| 5.15    | 279       | 11.49%  |
| 5.3     | 260       | 10.71%  |
| 4.15    | 248       | 10.21%  |
| 5.11    | 173       | 7.13%   |
| 5.13    | 134       | 5.52%   |
| 5.8     | 133       | 5.48%   |
| 5.19    | 88        | 3.62%   |
| 6.2     | 72        | 2.97%   |
| 5.0     | 58        | 2.39%   |
| 4.4     | 28        | 1.15%   |
| 4.18    | 14        | 0.58%   |
| 5.17    | 11        | 0.45%   |
| 5.10    | 11        | 0.45%   |
| 5.14    | 8         | 0.33%   |
| 6.5     | 7         | 0.29%   |
| 5.6     | 7         | 0.29%   |
| 4.13    | 7         | 0.29%   |
| 6.1     | 5         | 0.21%   |
| 6.0     | 5         | 0.21%   |
| 5.7     | 5         | 0.21%   |
| 4.19    | 5         | 0.21%   |
| 5.9     | 4         | 0.16%   |
| 5.12    | 4         | 0.16%   |
| 6.4     | 3         | 0.12%   |
| 5.18    | 3         | 0.12%   |
| 5.5     | 2         | 0.08%   |
| 5.16    | 2         | 0.08%   |
| 4.8     | 2         | 0.08%   |
| 4.11    | 2         | 0.08%   |
| 4.10    | 2         | 0.08%   |
| 6.3     | 1         | 0.04%   |
| 4.20    | 1         | 0.04%   |
| 4.14    | 1         | 0.04%   |
| 4.12    | 1         | 0.04%   |
| 3.13    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1973      | 85.19%  |
| i686   | 343       | 14.81%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 2238      | 96.59%  |
| GNOME           | 54        | 2.33%   |
| i3              | 8         | 0.35%   |
| KDE5            | 4         | 0.17%   |
| Unity           | 3         | 0.13%   |
| Unicorn:XFCE    | 2         | 0.09%   |
| Cinnamon        | 2         | 0.09%   |
| xmonad          | 1         | 0.04%   |
| MATE            | 1         | 0.04%   |
| ICEWM           | 1         | 0.04%   |
| GNUstep         | 1         | 0.04%   |
| GNOME Flashback | 1         | 0.04%   |
| awesome         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2284      | 98.7%   |
| Tty     | 15        | 0.65%   |
| Wayland | 14        | 0.61%   |
| Unknown | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1136      | 47.61%  |
| LightDM | 890       | 37.3%   |
| TDM     | 284       | 11.9%   |
| GDM3    | 39        | 1.63%   |
| GDM     | 22        | 0.92%   |
| SDDM    | 11        | 0.46%   |
| SLiM    | 2         | 0.08%   |
| XDM     | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 787       | 33.91%  |
| de_DE   | 237       | 10.21%  |
| fr_FR   | 202       | 8.7%    |
| it_IT   | 176       | 7.58%   |
| pt_BR   | 111       | 4.78%   |
| ru_RU   | 95        | 4.09%   |
| en_GB   | 94        | 4.05%   |
| C       | 81        | 3.49%   |
| es_ES   | 68        | 2.93%   |
| Unknown | 43        | 1.85%   |
| pl_PL   | 40        | 1.72%   |
| en_CA   | 35        | 1.51%   |
| en_AU   | 30        | 1.29%   |
| cs_CZ   | 24        | 1.03%   |
| hu_HU   | 20        | 0.86%   |
| en_IN   | 19        | 0.82%   |
| es_AR   | 18        | 0.78%   |
| nl_NL   | 17        | 0.73%   |
| es_MX   | 15        | 0.65%   |
| ja_JP   | 14        | 0.6%    |
| pt_PT   | 11        | 0.47%   |
| tr_TR   | 10        | 0.43%   |
| ru_UA   | 10        | 0.43%   |
| el_GR   | 10        | 0.43%   |
| fr_BE   | 9         | 0.39%   |
| fi_FI   | 9         | 0.39%   |
| sk_SK   | 8         | 0.34%   |
| es_CO   | 8         | 0.34%   |
| en_ZA   | 8         | 0.34%   |
| sv_SE   | 7         | 0.3%    |
| de_CH   | 7         | 0.3%    |
| zh_CN   | 6         | 0.26%   |
| nl_BE   | 6         | 0.26%   |
| es_VE   | 5         | 0.22%   |
| es_CL   | 5         | 0.22%   |
| de_AT   | 5         | 0.22%   |
| ca_ES   | 5         | 0.22%   |
| bg_BG   | 5         | 0.22%   |
| uk_UA   | 4         | 0.17%   |
| nb_NO   | 4         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1420      | 60.89%  |
| EFI  | 912       | 39.11%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2081      | 89.24%  |
| Overlay | 105       | 4.5%    |
| Tmpfs   | 60        | 2.57%   |
| Btrfs   | 38        | 1.63%   |
| Zfs     | 21        | 0.9%    |
| Unknown | 12        | 0.51%   |
| Xfs     | 6         | 0.26%   |
| Ext3    | 4         | 0.17%   |
| Ext2    | 4         | 0.17%   |
| Ufs     | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1366      | 58.13%  |
| GPT     | 690       | 29.36%  |
| MBR     | 294       | 12.51%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2074      | 87.99%  |
| Yes       | 283       | 12.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1632      | 69.68%  |
| Yes       | 710       | 30.32%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 465       | 20.1%   |
| Lenovo              | 418       | 18.07%  |
| Dell                | 306       | 13.23%  |
| ASUSTek Computer    | 255       | 11.02%  |
| Acer                | 230       | 9.94%   |
| Toshiba             | 103       | 4.45%   |
| Samsung Electronics | 59        | 2.55%   |
| Sony                | 50        | 2.16%   |
| Apple               | 43        | 1.86%   |
| MSI                 | 38        | 1.64%   |
| Fujitsu Siemens     | 27        | 1.17%   |
| Medion              | 26        | 1.12%   |
| Google              | 26        | 1.12%   |
| Packard Bell        | 19        | 0.82%   |
| Notebook            | 17        | 0.73%   |
| Fujitsu             | 16        | 0.69%   |
| Clevo               | 15        | 0.65%   |
| HUAWEI              | 13        | 0.56%   |
| Unknown             | 13        | 0.56%   |
| Positivo            | 10        | 0.43%   |
| GPU Company         | 9         | 0.39%   |
| Gateway             | 9         | 0.39%   |
| Intel               | 8         | 0.35%   |
| IBM                 | 7         | 0.3%    |
| TUXEDO              | 6         | 0.26%   |
| LG Electronics      | 5         | 0.22%   |
| eMachines           | 5         | 0.22%   |
| Dynabook            | 5         | 0.22%   |
| Alienware           | 5         | 0.22%   |
| Schenker            | 4         | 0.17%   |
| Itautec             | 4         | 0.17%   |
| AMI                 | 4         | 0.17%   |
| Semp Toshiba        | 3         | 0.13%   |
| OEM                 | 3         | 0.13%   |
| Gigabyte Technology | 3         | 0.13%   |
| Dixonsxp            | 3         | 0.13%   |
| Chuwi               | 3         | 0.13%   |
| Thomson             | 2         | 0.09%   |
| System76            | 2         | 0.09%   |
| Razer               | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 33        | 1.43%   |
| HP Pavilion dv6                        | 18        | 0.78%   |
| HP Notebook                            | 17        | 0.73%   |
| Dell Latitude D630                     | 11        | 0.48%   |
| HP Pavilion 15                         | 10        | 0.43%   |
| HP 15                                  | 10        | 0.43%   |
| Dell Latitude E6430                    | 9         | 0.39%   |
| HP Pavilion g6                         | 7         | 0.3%    |
| HP Pavilion dv7                        | 7         | 0.3%    |
| HP Pavilion dv6500                     | 7         | 0.3%    |
| ASUS VivoBook_ASUSLaptop X571LH_K571LH | 6         | 0.26%   |
| HP Pavilion 17                         | 5         | 0.22%   |
| HP EliteBook 840 G3                    | 5         | 0.22%   |
| Dell Latitude E6520                    | 5         | 0.22%   |
| Dell Latitude E6400                    | 5         | 0.22%   |
| Dell Inspiron 15-3567                  | 5         | 0.22%   |
| ASUS 1005HA                            | 5         | 0.22%   |
| Acer Aspire one                        | 5         | 0.22%   |
| Acer AO751h                            | 5         | 0.22%   |
| Positivo Mobile                        | 4         | 0.17%   |
| HP Pavilion g7                         | 4         | 0.17%   |
| HP Laptop 15-bw0xx                     | 4         | 0.17%   |
| HP G62                                 | 4         | 0.17%   |
| HP G42                                 | 4         | 0.17%   |
| HP EliteBook 8560p                     | 4         | 0.17%   |
| HP EliteBook 820 G3                    | 4         | 0.17%   |
| HP Compaq Presario C700                | 4         | 0.17%   |
| HP Compaq 6730s                        | 4         | 0.17%   |
| HP 255 G7 Notebook PC                  | 4         | 0.17%   |
| Google Snappy                          | 4         | 0.17%   |
| Dell Studio 1535                       | 4         | 0.17%   |
| Dell Latitude E6420                    | 4         | 0.17%   |
| Dell Latitude E6410                    | 4         | 0.17%   |
| Dell Latitude E6330                    | 4         | 0.17%   |
| Dell Inspiron 7520                     | 4         | 0.17%   |
| Dell Inspiron 1545                     | 4         | 0.17%   |
| Dell Inspiron 1525                     | 4         | 0.17%   |
| ASUS X553MA                            | 4         | 0.17%   |
| ASUS T100HAN                           | 4         | 0.17%   |
| ASUS K53SC                             | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 253       | 10.94%  |
| Acer Aspire              | 152       | 6.57%   |
| Dell Latitude            | 131       | 5.66%   |
| HP Pavilion              | 111       | 4.8%    |
| Dell Inspiron            | 99        | 4.28%   |
| Toshiba Satellite        | 87        | 3.76%   |
| Lenovo IdeaPad           | 76        | 3.29%   |
| HP EliteBook             | 59        | 2.55%   |
| HP Compaq                | 48        | 2.08%   |
| HP ProBook               | 46        | 1.99%   |
| HP Laptop                | 43        | 1.86%   |
| ASUS VivoBook            | 38        | 1.64%   |
| Unknown                  | 33        | 1.43%   |
| Dell XPS                 | 21        | 0.91%   |
| Dell Vostro              | 20        | 0.86%   |
| HP Notebook              | 18        | 0.78%   |
| Acer Extensa             | 18        | 0.78%   |
| Fujitsu Siemens AMILO    | 15        | 0.65%   |
| Dell Precision           | 15        | 0.65%   |
| Packard Bell EasyNote    | 14        | 0.61%   |
| Fujitsu LIFEBOOK         | 14        | 0.61%   |
| HP Presario              | 13        | 0.56%   |
| HP Mini                  | 11        | 0.48%   |
| HP 255                   | 11        | 0.48%   |
| HP 15                    | 11        | 0.48%   |
| Acer TravelMate          | 11        | 0.48%   |
| HP Stream                | 10        | 0.43%   |
| HP 250                   | 10        | 0.43%   |
| HP ZBook                 | 9         | 0.39%   |
| ASUS ASUS                | 9         | 0.39%   |
| HP ENVY                  | 8         | 0.35%   |
| ASUS ROG                 | 8         | 0.35%   |
| Acer Swift               | 8         | 0.35%   |
| Dell Studio              | 7         | 0.3%    |
| Acer Nitro               | 7         | 0.3%    |
| Toshiba PORTEGE          | 6         | 0.26%   |
| Lenovo ThinkBook         | 6         | 0.26%   |
| IBM ThinkPad             | 6         | 0.26%   |
| Fujitsu Siemens ESPRIMO  | 6         | 0.26%   |
| Fujitsu Siemens LIFEBOOK | 5         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 200       | 8.65%   |
| 2012    | 193       | 8.34%   |
| 2008    | 182       | 7.87%   |
| 2010    | 179       | 7.74%   |
| 2007    | 160       | 6.92%   |
| 2013    | 155       | 6.7%    |
| 2019    | 140       | 6.05%   |
| 2009    | 132       | 5.71%   |
| 2020    | 128       | 5.53%   |
| 2014    | 119       | 5.14%   |
| 2018    | 113       | 4.89%   |
| 2017    | 112       | 4.84%   |
| 2021    | 108       | 4.67%   |
| 2016    | 103       | 4.45%   |
| 2015    | 97        | 4.19%   |
| 2006    | 84        | 3.63%   |
| 2022    | 44        | 1.9%    |
| 2005    | 35        | 1.51%   |
| 2023    | 11        | 0.48%   |
| 2003    | 8         | 0.35%   |
| 2004    | 7         | 0.3%    |
| Unknown | 2         | 0.09%   |
| 2002    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2313      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2153      | 92.48%  |
| Enabled  | 175       | 7.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2285      | 98.79%  |
| Yes  | 28        | 1.21%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Notebooks | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 684       | 29.27%  |
| 4.01-8.0        | 509       | 21.78%  |
| 1.01-2.0        | 312       | 13.35%  |
| 8.01-16.0       | 261       | 11.17%  |
| 16.01-24.0      | 219       | 9.37%   |
| 0.51-1.0        | 113       | 4.84%   |
| 2.01-3.0        | 100       | 4.28%   |
| 32.01-64.0      | 90        | 3.85%   |
| 64.01-256.0     | 22        | 0.94%   |
| 24.01-32.0      | 19        | 0.81%   |
| 0.01-0.5        | 7         | 0.3%    |
| More than 256.0 | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1035      | 41.04%  |
| 0.51-1.0   | 515       | 20.42%  |
| 2.01-3.0   | 477       | 18.91%  |
| 4.01-8.0   | 193       | 7.65%   |
| 3.01-4.0   | 164       | 6.5%    |
| 0.01-0.5   | 74        | 2.93%   |
| 8.01-16.0  | 53        | 2.1%    |
| 16.01-24.0 | 8         | 0.32%   |
| 24.01-32.0 | 2         | 0.08%   |
| Unknown    | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1785      | 75.96%  |
| 2      | 471       | 20.04%  |
| 3      | 56        | 2.38%   |
| 0      | 28        | 1.19%   |
| 4      | 7         | 0.3%    |
| 5      | 2         | 0.09%   |
| 7      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1179      | 50.84%  |
| Yes       | 1140      | 49.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2004      | 86.53%  |
| No        | 312       | 13.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2255      | 97.32%  |
| No        | 62        | 2.68%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1452      | 62.02%  |
| No        | 889       | 37.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 329       | 14.12%  |
| Germany      | 296       | 12.7%   |
| France       | 224       | 9.61%   |
| Italy        | 193       | 8.28%   |
| Brazil       | 132       | 5.67%   |
| Russia       | 131       | 5.62%   |
| UK           | 93        | 3.99%   |
| Spain        | 81        | 3.48%   |
| Canada       | 72        | 3.09%   |
| Poland       | 51        | 2.19%   |
| Netherlands  | 51        | 2.19%   |
| Czechia      | 38        | 1.63%   |
| Australia    | 36        | 1.55%   |
| Mexico       | 31        | 1.33%   |
| Ukraine      | 30        | 1.29%   |
| Belgium      | 30        | 1.29%   |
| India        | 28        | 1.2%    |
| Argentina    | 25        | 1.07%   |
| Portugal     | 24        | 1.03%   |
| Finland      | 22        | 0.94%   |
| Hungary      | 21        | 0.9%    |
| Greece       | 21        | 0.9%    |
| Sweden       | 20        | 0.86%   |
| Indonesia    | 19        | 0.82%   |
| Turkey       | 17        | 0.73%   |
| Japan        | 17        | 0.73%   |
| Bulgaria     | 16        | 0.69%   |
| Romania      | 15        | 0.64%   |
| Austria      | 15        | 0.64%   |
| Switzerland  | 12        | 0.52%   |
| Slovakia     | 12        | 0.52%   |
| Norway       | 11        | 0.47%   |
| Iran         | 11        | 0.47%   |
| Denmark      | 11        | 0.47%   |
| Colombia     | 11        | 0.47%   |
| Chile        | 10        | 0.43%   |
| Belarus      | 9         | 0.39%   |
| Israel       | 8         | 0.34%   |
| Venezuela    | 7         | 0.3%    |
| South Africa | 7         | 0.3%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 35        | 1.42%   |
| Moscow            | 29        | 1.18%   |
| Berlin            | 27        | 1.1%    |
| Rome              | 25        | 1.02%   |
| Milan             | 24        | 0.98%   |
| Warsaw            | 19        | 0.77%   |
| St Petersburg     | 19        | 0.77%   |
| Athens            | 19        | 0.77%   |
| Québec           | 17        | 0.69%   |
| Prague            | 15        | 0.61%   |
| Munich            | 15        | 0.61%   |
| Sao Paulo         | 13        | 0.53%   |
| Madrid            | 12        | 0.49%   |
| Hamburg           | 12        | 0.49%   |
| Amsterdam         | 12        | 0.49%   |
| Helsinki          | 11        | 0.45%   |
| Budapest          | 11        | 0.45%   |
| Barcelona         | 11        | 0.45%   |
| Kyiv              | 10        | 0.41%   |
| Sydney            | 9         | 0.37%   |
| Rio de Janeiro    | 9         | 0.37%   |
| Turin             | 8         | 0.33%   |
| Stuttgart         | 8         | 0.33%   |
| Melbourne         | 8         | 0.33%   |
| Leipzig           | 8         | 0.33%   |
| Karlsruhe         | 8         | 0.33%   |
| Genoa             | 8         | 0.33%   |
| Frankfurt am Main | 8         | 0.33%   |
| Bucharest         | 8         | 0.33%   |
| Ankara            | 8         | 0.33%   |
| Yokohama          | 7         | 0.28%   |
| Vienna            | 7         | 0.28%   |
| Tehran            | 7         | 0.28%   |
| Sofia             | 7         | 0.28%   |
| Lisbon            | 7         | 0.28%   |
| Uppsala           | 6         | 0.24%   |
| Toronto           | 6         | 0.24%   |
| Seattle           | 6         | 0.24%   |
| Samara            | 6         | 0.24%   |
| Rostov-on-Don     | 6         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 400       | 487    | 14.71%  |
| Samsung Electronics | 377       | 460    | 13.87%  |
| WDC                 | 340       | 420    | 12.5%   |
| Toshiba             | 244       | 278    | 8.97%   |
| Unknown             | 191       | 248    | 7.02%   |
| Hitachi             | 168       | 197    | 6.18%   |
| Kingston            | 111       | 143    | 4.08%   |
| SanDisk             | 104       | 123    | 3.82%   |
| HGST                | 83        | 96     | 3.05%   |
| SK hynix            | 74        | 94     | 2.72%   |
| Crucial             | 63        | 74     | 2.32%   |
| Fujitsu             | 61        | 77     | 2.24%   |
| Intel               | 59        | 78     | 2.17%   |
| Micron Technology   | 40        | 45     | 1.47%   |
| A-DATA Technology   | 34        | 48     | 1.25%   |
| China               | 29        | 31     | 1.07%   |
| KIOXIA              | 16        | 18     | 0.59%   |
| Transcend           | 15        | 16     | 0.55%   |
| Apple               | 15        | 23     | 0.55%   |
| LITEON              | 14        | 16     | 0.51%   |
| PNY                 | 13        | 15     | 0.48%   |
| LITEONIT            | 13        | 16     | 0.48%   |
| Unknown             | 13        | 14     | 0.48%   |
| SPCC                | 12        | 14     | 0.44%   |
| Phison              | 12        | 16     | 0.44%   |
| OCZ                 | 12        | 13     | 0.44%   |
| Intenso             | 12        | 12     | 0.44%   |
| JMicron Technology  | 9         | 8      | 0.33%   |
| KingSpec            | 8         | 10     | 0.29%   |
| Apacer              | 8         | 10     | 0.29%   |
| Patriot             | 7         | 7      | 0.26%   |
| Netac               | 7         | 11     | 0.26%   |
| KingDian            | 7         | 9      | 0.26%   |
| Silicon Motion      | 6         | 6      | 0.22%   |
| IBM/Hitachi         | 6         | 6      | 0.22%   |
| HUAWEI              | 5         | 5      | 0.18%   |
| Hewlett-Packard     | 5         | 5      | 0.18%   |
| USB3.0              | 4         | 5      | 0.15%   |
| Smartbuy            | 4         | 4      | 0.15%   |
| Pioneer             | 4         | 4      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 45        | 1.61%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 30        | 1.07%   |
| Seagate ST500LT012-1DG142 500GB     | 27        | 0.96%   |
| Toshiba MQ01ABF050 500GB            | 26        | 0.93%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 23        | 0.82%   |
| Toshiba MQ01ABD100 1TB              | 22        | 0.79%   |
| Seagate ST1000LM035-1RK172 1TB      | 22        | 0.79%   |
| Kingston SA400S37480G 480GB SSD     | 22        | 0.79%   |
| Unknown MMC Card  64GB              | 20        | 0.71%   |
| Seagate ST9320325AS 320GB           | 19        | 0.68%   |
| HGST HTS541010A9E680 1TB            | 19        | 0.68%   |
| Seagate ST9500325AS 500GB           | 18        | 0.64%   |
| HGST HTS721010A9E630 1TB            | 18        | 0.64%   |
| Kingston SA400S37240G 240GB SSD     | 17        | 0.61%   |
| Unknown MMC Card  128GB             | 16        | 0.57%   |
| Seagate ST500LT012-9WS142 500GB     | 16        | 0.57%   |
| Samsung SSD 850 EVO 250GB           | 16        | 0.57%   |
| Unknown MMC Card  16GB              | 14        | 0.5%    |
| Toshiba MQ04ABF100 1TB              | 14        | 0.5%    |
| WDC WD10JPVX-22JC3T0 1TB            | 13        | 0.46%   |
| Samsung SSD 860 EVO 500GB           | 13        | 0.46%   |
| Samsung SSD 850 EVO 500GB           | 13        | 0.46%   |
| Kingston SA400S37120G 120GB SSD     | 13        | 0.46%   |
| Unknown                             | 13        | 0.46%   |
| WDC WD1600BEVT-22ZCT0 160GB         | 12        | 0.43%   |
| Crucial CT240BX500SSD1 240GB        | 12        | 0.43%   |
| SK hynix NVMe SSD Drive 256GB       | 11        | 0.39%   |
| Seagate ST9250315AS 250GB           | 11        | 0.39%   |
| Seagate ST9160310AS 160GB           | 11        | 0.39%   |
| HGST HTS725050A7E630 500GB          | 11        | 0.39%   |
| HGST HTS545050A7E680 500GB          | 11        | 0.39%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 10        | 0.36%   |
| Unknown SD/MMC/MS PRO 16GB          | 10        | 0.36%   |
| Seagate ST1000LM048-2E7172 1TB      | 10        | 0.36%   |
| Seagate Expansion 1TB               | 10        | 0.36%   |
| Samsung NVMe SSD Drive 512GB        | 10        | 0.36%   |
| Samsung HM321HI 320GB               | 10        | 0.36%   |
| Hitachi HTS543232A7A384 320GB       | 10        | 0.36%   |
| HGST HTS545050A7E380 500GB          | 10        | 0.36%   |
| Crucial CT500MX500SSD1 500GB        | 10        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 394       | 478    | 31.22%  |
| WDC                 | 262       | 330    | 20.76%  |
| Toshiba             | 200       | 231    | 15.85%  |
| Hitachi             | 168       | 197    | 13.31%  |
| HGST                | 83        | 96     | 6.58%   |
| Samsung Electronics | 59        | 68     | 4.68%   |
| Fujitsu             | 59        | 75     | 4.68%   |
| Unknown             | 10        | 12     | 0.79%   |
| IBM/Hitachi         | 6         | 6      | 0.48%   |
| USB3.0              | 4         | 5      | 0.32%   |
| SSK                 | 3         | 3      | 0.24%   |
| Pioneer             | 3         | 3      | 0.24%   |
| HGST HTS            | 2         | 2      | 0.16%   |
| External            | 2         | 2      | 0.16%   |
| ASMT                | 2         | 4      | 0.16%   |
| Intenso             | 1         | 1      | 0.08%   |
| CLOVER              | 1         | 1      | 0.08%   |
| Apricorn            | 1         | 2      | 0.08%   |
| ACASIS              | 1         | 1      | 0.08%   |
| Unknown             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 192       | 243    | 23.7%   |
| Kingston            | 98        | 128    | 12.1%   |
| SanDisk             | 70        | 86     | 8.64%   |
| Crucial             | 60        | 71     | 7.41%   |
| A-DATA Technology   | 30        | 44     | 3.7%    |
| China               | 29        | 31     | 3.58%   |
| WDC                 | 27        | 28     | 3.33%   |
| Micron Technology   | 25        | 27     | 3.09%   |
| Intel               | 23        | 32     | 2.84%   |
| Toshiba             | 20        | 21     | 2.47%   |
| SK hynix            | 19        | 20     | 2.35%   |
| Transcend           | 15        | 15     | 1.85%   |
| LITEON              | 14        | 16     | 1.73%   |
| PNY                 | 13        | 15     | 1.6%    |
| LITEONIT            | 13        | 16     | 1.6%    |
| SPCC                | 12        | 14     | 1.48%   |
| OCZ                 | 12        | 13     | 1.48%   |
| Intenso             | 11        | 11     | 1.36%   |
| Apple               | 9         | 13     | 1.11%   |
| Patriot             | 7         | 7      | 0.86%   |
| KingSpec            | 7         | 9      | 0.86%   |
| KingDian            | 7         | 9      | 0.86%   |
| Apacer              | 7         | 9      | 0.86%   |
| Unknown             | 5         | 6      | 0.62%   |
| Netac               | 5         | 9      | 0.62%   |
| Smartbuy            | 4         | 4      | 0.49%   |
| Hewlett-Packard     | 4         | 5      | 0.49%   |
| TO Exter            | 3         | 3      | 0.37%   |
| Plextor             | 3         | 9      | 0.37%   |
| GOODRAM             | 3         | 3      | 0.37%   |
| Drevo               | 3         | 3      | 0.37%   |
| Dogfish             | 3         | 6      | 0.37%   |
| Zheino              | 2         | 2      | 0.25%   |
| Team                | 2         | 7      | 0.25%   |
| TCSUNBOW            | 2         | 2      | 0.25%   |
| SSSTC               | 2         | 2      | 0.25%   |
| Mushkin             | 2         | 2      | 0.25%   |
| INNOVATION IT       | 2         | 2      | 0.25%   |
| Gigabyte Technology | 2         | 4      | 0.25%   |
| FORESEE             | 2         | 5      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1225      | 1518   | 46.74%  |
| SSD     | 750       | 1002   | 28.62%  |
| NVMe    | 422       | 512    | 16.1%   |
| MMC     | 191       | 245    | 7.29%   |
| Unknown | 33        | 36     | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1828      | 2438   | 72.05%  |
| NVMe | 417       | 505    | 16.44%  |
| MMC  | 191       | 245    | 7.53%   |
| SAS  | 101       | 125    | 3.98%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1499      | 1936   | 76.25%  |
| 0.51-1.0   | 412       | 510    | 20.96%  |
| 1.01-2.0   | 44        | 53     | 2.24%   |
| 3.01-4.0   | 7         | 12     | 0.36%   |
| 4.01-10.0  | 2         | 7      | 0.1%    |
| 2.01-3.0   | 1         | 1      | 0.05%   |
| 0          | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 820       | 34.24%  |
| 251-500        | 621       | 25.93%  |
| 501-1000       | 290       | 12.11%  |
| 51-100         | 233       | 9.73%   |
| 21-50          | 165       | 6.89%   |
| 1-20           | 119       | 4.97%   |
| 1001-2000      | 91        | 3.8%    |
| 2001-3000      | 22        | 0.92%   |
| More than 3000 | 21        | 0.88%   |
| Unknown        | 13        | 0.54%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1118      | 44.92%  |
| 21-50          | 459       | 18.44%  |
| 101-250        | 319       | 12.82%  |
| 51-100         | 292       | 11.73%  |
| 251-500        | 152       | 6.11%   |
| 501-1000       | 96        | 3.86%   |
| 1001-2000      | 29        | 1.17%   |
| Unknown        | 13        | 0.52%   |
| 2001-3000      | 6         | 0.24%   |
| More than 3000 | 5         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB | 8         | 8      | 4.82%   |
| Seagate ST9500325AS 500GB          | 6         | 8      | 3.61%   |
| Toshiba MQ01ABD100 1TB             | 5         | 6      | 3.01%   |
| Seagate ST500LT012-9WS142 500GB    | 5         | 5      | 3.01%   |
| Seagate ST500LT012-1DG142 500GB    | 3         | 3      | 1.81%   |
| HGST HTS545050A7E680 500GB         | 3         | 3      | 1.81%   |
| HGST HTS541010A9E680 1TB           | 3         | 3      | 1.81%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 2         | 2      | 1.2%    |
| WDC WD10JPVX-22JC3T0 1TB           | 2         | 3      | 1.2%    |
| Toshiba MK5065GSXN 500GB           | 2         | 4      | 1.2%    |
| Seagate ST9500423AS 500GB          | 2         | 2      | 1.2%    |
| Seagate ST9320325AS 320GB          | 2         | 2      | 1.2%    |
| Seagate ST320LT007-9ZV142 320GB    | 2         | 2      | 1.2%    |
| Samsung Electronics HM321HI 320GB  | 2         | 2      | 1.2%    |
| Hitachi HTS725050A9A364 500GB      | 2         | 3      | 1.2%    |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 1.2%    |
| Hitachi HTS543232A7A384 320GB      | 2         | 3      | 1.2%    |
| Hitachi HTS543216L9A300 160GB      | 2         | 2      | 1.2%    |
| Fujitsu MHZ2160BJ FFS G2 160GB     | 2         | 3      | 1.2%    |
| WDC WDS480G2G0A-00JH30 480GB SSD   | 1         | 1      | 0.6%    |
| WDC WD7500BPVT-80HXZT3 752GB       | 1         | 2      | 0.6%    |
| WDC WD7500BPVT-24HXZT1 752GB       | 1         | 2      | 0.6%    |
| WDC WD7500BPKX-00HPJT0 752GB       | 1         | 1      | 0.6%    |
| WDC WD5000BEVT-60ZAT1 500GB        | 1         | 1      | 0.6%    |
| WDC WD5000BEKT-75KA9T0 500GB       | 1         | 1      | 0.6%    |
| WDC WD3200BPVT-80ZEST0 320GB       | 1         | 1      | 0.6%    |
| WDC WD3200BPVT-35ZEST0 320GB       | 1         | 1      | 0.6%    |
| WDC WD3200BEVT-60ZCT1 320GB        | 1         | 1      | 0.6%    |
| WDC WD3200BEKT-75PVMT0 320GB       | 1         | 1      | 0.6%    |
| WDC WD3200BEKT-60PVMT0 320GB       | 1         | 1      | 0.6%    |
| WDC WD1600BJKT-75F4T0 160GB        | 1         | 1      | 0.6%    |
| WDC WD1200BEVS-60UST0 120GB        | 1         | 1      | 0.6%    |
| WDC WD10SPCX-24HWST1 1TB           | 1         | 1      | 0.6%    |
| WDC WD10JPVT-08A1YT2 1TB           | 1         | 1      | 0.6%    |
| Toshiba MQ04ABF100 1TB             | 1         | 1      | 0.6%    |
| Toshiba MQ01ACF050 500GB           | 1         | 1      | 0.6%    |
| Toshiba MQ01ABD050 500GB           | 1         | 1      | 0.6%    |
| Toshiba MQ01ABD032 320GB           | 1         | 1      | 0.6%    |
| Toshiba MK7575GSX 752GB            | 1         | 1      | 0.6%    |
| Toshiba MK7559GSXP 752GB           | 1         | 2      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 48     | 26.51%  |
| Toshiba             | 22        | 27     | 13.25%  |
| WDC                 | 19        | 22     | 11.45%  |
| Hitachi             | 19        | 21     | 11.45%  |
| Samsung Electronics | 10        | 10     | 6.02%   |
| HGST                | 8         | 9      | 4.82%   |
| Fujitsu             | 8         | 9      | 4.82%   |
| SK hynix            | 4         | 5      | 2.41%   |
| SanDisk             | 4         | 4      | 2.41%   |
| Kingston            | 4         | 6      | 2.41%   |
| Micron Technology   | 3         | 3      | 1.81%   |
| Intel               | 3         | 3      | 1.81%   |
| OCZ                 | 2         | 2      | 1.2%    |
| LITEON              | 2         | 2      | 1.2%    |
| A-DATA Technology   | 2         | 3      | 1.2%    |
| SSSTC               | 1         | 1      | 0.6%    |
| Netac               | 1         | 1      | 0.6%    |
| Neo Forza           | 1         | 1      | 0.6%    |
| Mushkin             | 1         | 1      | 0.6%    |
| LDLC                | 1         | 1      | 0.6%    |
| KingDian            | 1         | 3      | 0.6%    |
| JMicron Technology  | 1         | 1      | 0.6%    |
| Drevo               | 1         | 1      | 0.6%    |
| Crucial             | 1         | 1      | 0.6%    |
| China               | 1         | 1      | 0.6%    |
| Apple               | 1         | 1      | 0.6%    |
| Unknown             | 1         | 1      | 0.6%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 48     | 35.2%   |
| Toshiba             | 22        | 27     | 17.6%   |
| Hitachi             | 19        | 21     | 15.2%   |
| WDC                 | 18        | 21     | 14.4%   |
| HGST                | 8         | 9      | 6.4%    |
| Fujitsu             | 8         | 9      | 6.4%    |
| Samsung Electronics | 6         | 6      | 4.8%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 125       | 141    | 75.3%   |
| SSD  | 38        | 44     | 22.89%  |
| NVMe | 3         | 3      | 1.81%   |

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
| Detected | 1561      | 2249   | 64.91%  |
| Works    | 681       | 876    | 28.32%  |
| Malfunc  | 163       | 188    | 6.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1674      | 68.33%  |
| AMD                              | 290       | 11.84%  |
| Samsung Electronics              | 138       | 5.63%   |
| SanDisk                          | 82        | 3.35%   |
| SK hynix                         | 49        | 2%      |
| Nvidia                           | 34        | 1.39%   |
| Silicon Integrated Systems [SiS] | 32        | 1.31%   |
| Toshiba America Info Systems     | 23        | 0.94%   |
| KIOXIA                           | 18        | 0.73%   |
| Kingston Technology Company      | 18        | 0.73%   |
| Phison Electronics               | 14        | 0.57%   |
| Micron Technology                | 14        | 0.57%   |
| VIA Technologies                 | 13        | 0.53%   |
| Silicon Motion                   | 8         | 0.33%   |
| Apple                            | 6         | 0.24%   |
| Micron/Crucial Technology        | 5         | 0.2%    |
| ULi Electronics                  | 4         | 0.16%   |
| Realtek Semiconductor            | 4         | 0.16%   |
| Lenovo                           | 4         | 0.16%   |
| JMicron Technology               | 4         | 0.16%   |
| Union Memory (Shenzhen)          | 3         | 0.12%   |
| Silicon Image                    | 3         | 0.12%   |
| ADATA Technology                 | 3         | 0.12%   |
| Seagate Technology               | 2         | 0.08%   |
| Lite-On Technology               | 2         | 0.08%   |
| Netac Technology                 | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| Hosin Global Electronics         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 197       | 7.02%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 175       | 6.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 129       | 4.59%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 128       | 4.56%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 127       | 4.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 125       | 4.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 107       | 3.81%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 101       | 3.6%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 81        | 2.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 71        | 2.53%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 66        | 2.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 60        | 2.14%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 55        | 1.96%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 55        | 1.96%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 54        | 1.92%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 50        | 1.78%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 48        | 1.71%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 44        | 1.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 41        | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 40        | 1.42%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 38        | 1.35%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 36        | 1.28%   |
| Intel Volume Management Device NVMe RAID Controller                              | 33        | 1.18%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 33        | 1.18%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 31        | 1.1%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 30        | 1.07%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 29        | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 24        | 0.85%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 23        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 23        | 0.82%   |
| AMD IXP SB4x0 IDE Controller                                                     | 22        | 0.78%   |
| AMD SB600 Non-Raid-5 SATA                                                        | 20        | 0.71%   |
| AMD SB600 IDE                                                                    | 20        | 0.71%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 18        | 0.64%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 17        | 0.61%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 17        | 0.61%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 16        | 0.57%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 16        | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 16        | 0.57%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 16        | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1623      | 60.97%  |
| IDE  | 487       | 18.29%  |
| NVMe | 411       | 15.44%  |
| RAID | 141       | 5.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1937      | 83.74%  |
| AMD          | 374       | 16.17%  |
| CentaurHauls | 2         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz           | 30        | 1.3%    |
| Intel Core i5-3320M CPU @ 2.60GHz       | 23        | 0.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 22        | 0.95%   |
| Intel Celeron CPU N3060 @ 1.60GHz       | 22        | 0.95%   |
| Intel Atom CPU N450 @ 1.66GHz           | 22        | 0.95%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 22        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 21        | 0.91%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 21        | 0.91%   |
| Intel Celeron CPU N2840 @ 2.16GHz       | 21        | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 20        | 0.86%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 20        | 0.86%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz    | 19        | 0.82%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz    | 19        | 0.82%   |
| Intel Core i7-2670QM CPU @ 2.20GHz      | 18        | 0.78%   |
| Intel Core i3 CPU M 370 @ 2.40GHz       | 18        | 0.78%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 17        | 0.73%   |
| Intel Core i5 CPU M 520 @ 2.40GHz       | 17        | 0.73%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz    | 17        | 0.73%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 16        | 0.69%   |
| Intel Celeron CPU N3350 @ 1.10GHz       | 16        | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 15        | 0.65%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 15        | 0.65%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 15        | 0.65%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 15        | 0.65%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 15        | 0.65%   |
| Intel Core i7-3630QM CPU @ 2.40GHz      | 14        | 0.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz      | 14        | 0.6%    |
| Intel Core i5-2410M CPU @ 2.30GHz       | 14        | 0.6%    |
| Intel Core i5-10210U CPU @ 1.60GHz      | 14        | 0.6%    |
| Intel Core i3-6006U CPU @ 2.00GHz       | 14        | 0.6%    |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz    | 14        | 0.6%    |
| Intel Celeron N4020 CPU @ 1.10GHz       | 14        | 0.6%    |
| Intel Celeron CPU N3050 @ 1.60GHz       | 14        | 0.6%    |
| Intel Atom CPU N455 @ 1.66GHz           | 14        | 0.6%    |
| Intel Pentium M processor 1.73GHz       | 13        | 0.56%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz  | 13        | 0.56%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 13        | 0.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz       | 13        | 0.56%   |
| Intel Core i3 CPU M 380 @ 2.53GHz       | 13        | 0.56%   |
| Intel Core 2 Duo CPU T7100 @ 1.80GHz    | 13        | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 437       | 18.87%  |
| Intel Core i7           | 344       | 14.85%  |
| Intel Core 2 Duo        | 209       | 9.02%   |
| Intel Celeron           | 196       | 8.46%   |
| Intel Core i3           | 180       | 7.77%   |
| Intel Atom              | 145       | 6.26%   |
| Other                   | 92        | 3.97%   |
| Intel Pentium           | 68        | 2.94%   |
| Intel Genuine           | 56        | 2.42%   |
| AMD Ryzen 5             | 49        | 2.12%   |
| Intel Pentium Dual-Core | 42        | 1.81%   |
| Intel Pentium Dual      | 42        | 1.81%   |
| AMD Ryzen 7             | 39        | 1.68%   |
| Intel Core 2            | 35        | 1.51%   |
| Intel Pentium M         | 29        | 1.25%   |
| AMD A8                  | 29        | 1.25%   |
| AMD E1                  | 27        | 1.17%   |
| Intel Celeron M         | 25        | 1.08%   |
| AMD A6                  | 25        | 1.08%   |
| AMD Turion 64 X2 Mobile | 20        | 0.86%   |
| AMD A4                  | 19        | 0.82%   |
| AMD E                   | 16        | 0.69%   |
| AMD Ryzen 7 PRO         | 15        | 0.65%   |
| AMD E2                  | 15        | 0.65%   |
| AMD Turion 64 Mobile    | 11        | 0.47%   |
| AMD Ryzen 3             | 11        | 0.47%   |
| Intel Pentium Silver    | 9         | 0.39%   |
| AMD Athlon              | 9         | 0.39%   |
| AMD Mobile Sempron      | 8         | 0.35%   |
| Intel Pentium 4         | 7         | 0.3%    |
| Intel Core Duo          | 7         | 0.3%    |
| Intel Celeron Dual-Core | 7         | 0.3%    |
| AMD Athlon 64 X2        | 7         | 0.3%    |
| AMD A10                 | 7         | 0.3%    |
| AMD Ryzen 9             | 6         | 0.26%   |
| AMD C-60                | 6         | 0.26%   |
| Intel Core i9           | 5         | 0.22%   |
| AMD Athlon II           | 5         | 0.22%   |
| AMD Sempron             | 4         | 0.17%   |
| AMD Ryzen 5 PRO         | 4         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1395      | 60.26%  |
| 4      | 523       | 22.59%  |
| 1      | 229       | 9.89%   |
| 6      | 87        | 3.76%   |
| 8      | 62        | 2.68%   |
| 12     | 7         | 0.3%    |
| 10     | 7         | 0.3%    |
| 14     | 3         | 0.13%   |
| 16     | 2         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2313      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1303      | 56.33%  |
| 1      | 1010      | 43.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2145      | 92.7%   |
| 32-bit         | 169       | 7.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 436       | 18.44%  |
| 0x206a7    | 158       | 6.68%   |
| 0x306a9    | 142       | 6%      |
| 0x6fd      | 109       | 4.61%   |
| 0x1067a    | 108       | 4.57%   |
| 0x20655    | 77        | 3.26%   |
| 0x40651    | 64        | 2.71%   |
| 0x406e3    | 55        | 2.33%   |
| 0x10676    | 51        | 2.16%   |
| 0x30678    | 47        | 1.99%   |
| 0x106ca    | 46        | 1.95%   |
| 0x806ea    | 45        | 1.9%    |
| 0x806ec    | 43        | 1.82%   |
| 0x306c3    | 43        | 1.82%   |
| 0x806c1    | 42        | 1.78%   |
| 0x406c4    | 42        | 1.78%   |
| 0x306d4    | 41        | 1.73%   |
| 0x106c2    | 41        | 1.73%   |
| 0x20652    | 39        | 1.65%   |
| 0x806e9    | 36        | 1.52%   |
| 0x906ea    | 34        | 1.44%   |
| 0x6e8      | 34        | 1.44%   |
| 0x6d8      | 34        | 1.44%   |
| 0x6f6      | 31        | 1.31%   |
| 0x05000119 | 29        | 1.23%   |
| 0x406c3    | 25        | 1.06%   |
| 0x07030105 | 25        | 1.06%   |
| 0xa0652    | 24        | 1.01%   |
| 0x6ec      | 24        | 1.01%   |
| 0x6fb      | 23        | 0.97%   |
| 0x706a1    | 19        | 0.8%    |
| 0x0700010f | 19        | 0.8%    |
| 0x10661    | 17        | 0.72%   |
| 0x08108102 | 17        | 0.72%   |
| 0x08108109 | 16        | 0.68%   |
| 0x906e9    | 15        | 0.63%   |
| 0x706e5    | 15        | 0.63%   |
| 0x706a8    | 15        | 0.63%   |
| 0x08608103 | 15        | 0.63%   |
| 0x03000027 | 14        | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 250       | 10.79%  |
| Core             | 198       | 8.55%   |
| Penryn           | 182       | 7.86%   |
| SandyBridge      | 180       | 7.77%   |
| IvyBridge        | 163       | 7.04%   |
| Westmere         | 137       | 5.92%   |
| Haswell          | 129       | 5.57%   |
| Silvermont       | 128       | 5.53%   |
| Bonnell          | 111       | 4.79%   |
| P6               | 100       | 4.32%   |
| Skylake          | 89        | 3.84%   |
| TigerLake        | 54        | 2.33%   |
| K8 Hammer        | 53        | 2.29%   |
| Broadwell        | 53        | 2.29%   |
| Goldmont plus    | 44        | 1.9%    |
| Bobcat           | 42        | 1.81%   |
| Unknown          | 38        | 1.64%   |
| Zen+             | 37        | 1.6%    |
| CometLake        | 35        | 1.51%   |
| Puma             | 34        | 1.47%   |
| Zen 2            | 33        | 1.42%   |
| Excavator        | 29        | 1.25%   |
| IceLake          | 28        | 1.21%   |
| Jaguar           | 23        | 0.99%   |
| Zen 3            | 22        | 0.95%   |
| Goldmont         | 21        | 0.91%   |
| K10 Llano        | 15        | 0.65%   |
| Zen              | 14        | 0.6%    |
| Piledriver       | 13        | 0.56%   |
| K10              | 13        | 0.56%   |
| K8 & K10 hybrid  | 12        | 0.52%   |
| Alderlake Hybrid | 11        | 0.47%   |
| NetBurst         | 10        | 0.43%   |
| Steamroller      | 5         | 0.22%   |
| Nehalem          | 5         | 0.22%   |
| Tremont          | 3         | 0.13%   |
| K6               | 2         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1656      | 61.15%  |
| AMD                              | 532       | 19.65%  |
| Nvidia                           | 485       | 17.91%  |
| Silicon Integrated Systems [SiS] | 21        | 0.78%   |
| VIA Technologies                 | 12        | 0.44%   |
| S3 Graphics                      | 1         | 0.04%   |
| ASPEED Technology                | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 166       | 5.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 153       | 5.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 125       | 4.29%   |
| Intel Core Processor Integrated Graphics Controller                                      | 102       | 3.5%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 92        | 3.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 86        | 2.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 86        | 2.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 75        | 2.57%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 74        | 2.54%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 63        | 2.16%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 59        | 2.02%   |
| Intel UHD Graphics 620                                                                   | 54        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 54        | 1.85%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 49        | 1.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 1.61%   |
| Intel HD Graphics 620                                                                    | 47        | 1.61%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 46        | 1.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 43        | 1.47%   |
| Intel HD Graphics 5500                                                                   | 42        | 1.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 38        | 1.3%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 36        | 1.23%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 33        | 1.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 32        | 1.1%    |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 32        | 1.1%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 1.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 30        | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 26        | 0.89%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 0.72%   |
| Intel HD Graphics 500                                                                    | 21        | 0.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 21        | 0.72%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 0.69%   |
| AMD Lucienne                                                                             | 19        | 0.65%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 18        | 0.62%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 17        | 0.58%   |
| Intel HD Graphics 630                                                                    | 17        | 0.58%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 17        | 0.58%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 15        | 0.51%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.51%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 15        | 0.51%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 15        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1275      | 55.1%   |
| 1 x AMD         | 400       | 17.29%  |
| Intel + Nvidia  | 289       | 12.49%  |
| 1 x Nvidia      | 172       | 7.43%   |
| Intel + AMD     | 79        | 3.41%   |
| 2 x AMD         | 29        | 1.25%   |
| AMD + Nvidia    | 24        | 1.04%   |
| 1 x SiS         | 21        | 0.91%   |
| 1 x VIA         | 12        | 0.52%   |
| Other           | 10        | 0.43%   |
| 2 x Intel       | 1         | 0.04%   |
| 1 x S3 Graphics | 1         | 0.04%   |
| Nvidia + ASPEED | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2018      | 86.76%  |
| Proprietary | 226       | 9.72%   |
| Unknown     | 82        | 3.53%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1376      | 58.78%  |
| 0.01-0.5   | 473       | 20.21%  |
| 1.01-2.0   | 227       | 9.7%    |
| 0.51-1.0   | 137       | 5.85%   |
| 3.01-4.0   | 87        | 3.72%   |
| 5.01-6.0   | 22        | 0.94%   |
| 7.01-8.0   | 10        | 0.43%   |
| 2.01-3.0   | 5         | 0.21%   |
| 8.01-16.0  | 3         | 0.13%   |
| 16.01-24.0 | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 469       | 19.4%   |
| LG Display              | 371       | 15.34%  |
| Samsung Electronics     | 328       | 13.56%  |
| Chimei Innolux          | 243       | 10.05%  |
| BOE                     | 234       | 9.68%   |
| Chi Mei Optoelectronics | 98        | 4.05%   |
| LG Philips              | 74        | 3.06%   |
| Lenovo                  | 73        | 3.02%   |
| Dell                    | 42        | 1.74%   |
| Apple                   | 42        | 1.74%   |
| Goldstar                | 36        | 1.49%   |
| HannStar                | 34        | 1.41%   |
| Sharp                   | 31        | 1.28%   |
| InfoVision              | 29        | 1.2%    |
| CPT                     | 23        | 0.95%   |
| Acer                    | 21        | 0.87%   |
| PANDA                   | 19        | 0.79%   |
| BenQ                    | 18        | 0.74%   |
| Philips                 | 17        | 0.7%    |
| Hewlett-Packard         | 16        | 0.66%   |
| Ancor Communications    | 14        | 0.58%   |
| Sony                    | 13        | 0.54%   |
| ViewSonic               | 11        | 0.45%   |
| Toshiba                 | 11        | 0.45%   |
| Quanta Display          | 11        | 0.45%   |
| CSO                     | 9         | 0.37%   |
| AOC                     | 9         | 0.37%   |
| Iiyama                  | 8         | 0.33%   |
| Seiko/Epson             | 7         | 0.29%   |
| InnoLux Display         | 7         | 0.29%   |
| Panasonic               | 5         | 0.21%   |
| Nvidia                  | 5         | 0.21%   |
| LPL                     | 5         | 0.21%   |
| Vizio                   | 4         | 0.17%   |
| LGD                     | 4         | 0.17%   |
| IBM                     | 4         | 0.17%   |
| Fujitsu Siemens         | 4         | 0.17%   |
| SLD                     | 3         | 0.12%   |
| Lenovo Group Limited    | 3         | 0.12%   |
| KDC                     | 3         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 27        | 1.11%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 21        | 0.86%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 20        | 0.82%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 17        | 0.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 16        | 0.66%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 13        | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 13        | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.49%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 12        | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 0.45%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 10        | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 10        | 0.41%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.41%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 10        | 0.41%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 10        | 0.41%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 9         | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 9         | 0.37%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 9         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 8         | 0.33%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 8         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch            | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 8         | 0.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 8         | 0.33%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                   | 8         | 0.33%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 7         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch     | 7         | 0.29%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 7         | 0.29%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 7         | 0.29%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 7         | 0.29%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 7         | 0.29%   |
| AU Optronics LCD Monitor AUO205C 1366x768 256x144mm 11.6-inch            | 7         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.25%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 6         | 0.25%   |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 6         | 0.25%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 6         | 0.25%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 6         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 821       | 35.22%  |
| 1920x1080 (FHD)    | 684       | 29.34%  |
| 1280x800 (WXGA)    | 258       | 11.07%  |
| 1600x900 (HD+)     | 144       | 6.18%   |
| 1440x900 (WXGA+)   | 81        | 3.47%   |
| 1024x600           | 70        | 3%      |
| 3840x2160 (4K)     | 55        | 2.36%   |
| 1920x1200 (WUXGA)  | 41        | 1.76%   |
| 1680x1050 (WSXGA+) | 33        | 1.42%   |
| 2560x1440 (QHD)    | 24        | 1.03%   |
| 1280x1024 (SXGA)   | 22        | 0.94%   |
| 1024x768 (XGA)     | 20        | 0.86%   |
| 2560x1600          | 9         | 0.39%   |
| 1360x768           | 7         | 0.3%    |
| 1920x540           | 5         | 0.21%   |
| 1400x1050          | 5         | 0.21%   |
| 3840x1080          | 4         | 0.17%   |
| 3200x1800 (QHD+)   | 4         | 0.17%   |
| 2880x1800          | 4         | 0.17%   |
| 2160x1440          | 4         | 0.17%   |
| Unknown            | 4         | 0.17%   |
| 3840x2400          | 3         | 0.13%   |
| 2560x1080          | 3         | 0.13%   |
| 2288x1287          | 3         | 0.13%   |
| 3440x1440          | 2         | 0.09%   |
| 2304x1440          | 2         | 0.09%   |
| 1600x1200          | 2         | 0.09%   |
| 800x480            | 1         | 0.04%   |
| 3840x1600          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3600x1080          | 1         | 0.04%   |
| 3120x1050          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 2560x1700          | 1         | 0.04%   |
| 2520x1680          | 1         | 0.04%   |
| 2240x1400          | 1         | 0.04%   |
| 1920x515           | 1         | 0.04%   |
| 1920x1280          | 1         | 0.04%   |
| 1680x945           | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 994       | 41.04%  |
| 14      | 323       | 13.34%  |
| 13      | 267       | 11.02%  |
| 17      | 207       | 8.55%   |
| 12      | 80        | 3.3%    |
| 10      | 73        | 3.01%   |
| 11      | 71        | 2.93%   |
| 24      | 60        | 2.48%   |
| 21      | 52        | 2.15%   |
| 27      | 51        | 2.11%   |
| Unknown | 47        | 1.94%   |
| 23      | 41        | 1.69%   |
| 18      | 27        | 1.11%   |
| 16      | 20        | 0.83%   |
| 19      | 18        | 0.74%   |
| 22      | 12        | 0.5%    |
| 54      | 11        | 0.45%   |
| 31      | 9         | 0.37%   |
| 20      | 8         | 0.33%   |
| 40      | 5         | 0.21%   |
| 34      | 5         | 0.21%   |
| 84      | 4         | 0.17%   |
| 32      | 4         | 0.17%   |
| 8       | 4         | 0.17%   |
| 72      | 3         | 0.12%   |
| 37      | 3         | 0.12%   |
| 26      | 3         | 0.12%   |
| 25      | 3         | 0.12%   |
| 86      | 2         | 0.08%   |
| 52      | 2         | 0.08%   |
| 48      | 2         | 0.08%   |
| 42      | 2         | 0.08%   |
| 74      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 57      | 1         | 0.04%   |
| 49      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 39      | 1         | 0.04%   |
| 38      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1440      | 59.85%  |
| 201-300     | 354       | 14.71%  |
| 351-400     | 250       | 10.39%  |
| 501-600     | 146       | 6.07%   |
| 401-500     | 97        | 4.03%   |
| Unknown     | 47        | 1.95%   |
| 1001-1500   | 22        | 0.91%   |
| 601-700     | 17        | 0.71%   |
| 801-900     | 10        | 0.42%   |
| 701-800     | 9         | 0.37%   |
| 1501-2000   | 8         | 0.33%   |
| 101-200     | 4         | 0.17%   |
| 901-1000    | 2         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1686      | 76.29%  |
| 16/10   | 407       | 18.42%  |
| Unknown | 36        | 1.63%   |
| 4/3     | 27        | 1.22%   |
| 5/4     | 20        | 0.9%    |
| 3/2     | 18        | 0.81%   |
| 21/9    | 6         | 0.27%   |
| 6/5     | 2         | 0.09%   |
| 32/9    | 2         | 0.09%   |
| 0.56    | 2         | 0.09%   |
| 3.73    | 1         | 0.05%   |
| 3.20    | 1         | 0.05%   |
| 1.00    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 991       | 40.98%  |
| 81-90          | 483       | 19.98%  |
| 121-130        | 158       | 6.53%   |
| 201-250        | 131       | 5.42%   |
| 71-80          | 91        | 3.76%   |
| 61-70          | 78        | 3.23%   |
| 41-50          | 73        | 3.02%   |
| 51-60          | 71        | 2.94%   |
| 301-350        | 52        | 2.15%   |
| 151-200        | 50        | 2.07%   |
| Unknown        | 47        | 1.94%   |
| 131-140        | 46        | 1.9%    |
| 141-150        | 28        | 1.16%   |
| More than 1000 | 26        | 1.08%   |
| 91-100         | 22        | 0.91%   |
| 351-500        | 19        | 0.79%   |
| 251-300        | 18        | 0.74%   |
| 501-1000       | 16        | 0.66%   |
| 111-120        | 14        | 0.58%   |
| 1-40           | 4         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 944       | 39.78%  |
| 121-160       | 730       | 30.76%  |
| 51-100        | 497       | 20.94%  |
| 161-240       | 98        | 4.13%   |
| Unknown       | 47        | 1.98%   |
| More than 240 | 29        | 1.22%   |
| 1-50          | 28        | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1980      | 83.86%  |
| 2     | 284       | 12.03%  |
| 0     | 75        | 3.18%   |
| 3     | 20        | 0.85%   |
| 4     | 2         | 0.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1132      | 29.73%  |
| Intel                             | 1063      | 27.91%  |
| Qualcomm Atheros                  | 633       | 16.62%  |
| Broadcom                          | 341       | 8.95%   |
| Marvell Technology Group          | 110       | 2.89%   |
| Broadcom Limited                  | 90        | 2.36%   |
| Ralink                            | 50        | 1.31%   |
| TP-Link                           | 31        | 0.81%   |
| Silicon Integrated Systems [SiS]  | 29        | 0.76%   |
| Ralink Technology                 | 28        | 0.74%   |
| Nvidia                            | 27        | 0.71%   |
| MediaTek                          | 25        | 0.66%   |
| Samsung Electronics               | 24        | 0.63%   |
| JMicron Technology                | 21        | 0.55%   |
| Sierra Wireless                   | 17        | 0.45%   |
| Ericsson Business Mobile Networks | 16        | 0.42%   |
| Huawei Technologies               | 15        | 0.39%   |
| Attansic Technology               | 15        | 0.39%   |
| VIA Technologies                  | 11        | 0.29%   |
| Dell                              | 10        | 0.26%   |
| Xiaomi                            | 8         | 0.21%   |
| Qualcomm Atheros Communications   | 8         | 0.21%   |
| ASIX Electronics                  | 8         | 0.21%   |
| Qualcomm                          | 7         | 0.18%   |
| AMD                               | 7         | 0.18%   |
| Lenovo                            | 6         | 0.16%   |
| Fibocom                           | 6         | 0.16%   |
| DisplayLink                       | 5         | 0.13%   |
| D-Link System                     | 5         | 0.13%   |
| ZyDAS                             | 4         | 0.11%   |
| ULi Electronics                   | 4         | 0.11%   |
| Motorola PCS                      | 4         | 0.11%   |
| Hewlett-Packard                   | 4         | 0.11%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.08%   |
| Toshiba                           | 3         | 0.08%   |
| Edimax Technology                 | 3         | 0.08%   |
| ASUSTek Computer                  | 3         | 0.08%   |
| Spreadtrum Communications         | 2         | 0.05%   |
| Sitecom Europe                    | 2         | 0.05%   |
| OPPO Electronics                  | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 585       | 12.72%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 286       | 6.22%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 114       | 2.48%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 100       | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 98        | 2.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 88        | 1.91%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 82        | 1.78%   |
| Intel Wireless 7260                                                     | 73        | 1.59%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 72        | 1.57%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 68        | 1.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 65        | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 63        | 1.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 55        | 1.2%    |
| Intel Wireless 8265 / 8275                                              | 55        | 1.2%    |
| Intel Wireless 7265                                                     | 55        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 52        | 1.13%   |
| Intel Wi-Fi 6 AX200                                                     | 52        | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 50        | 1.09%   |
| Intel Wireless 8260                                                     | 47        | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 41        | 0.89%   |
| Intel Wi-Fi 6 AX201                                                     | 36        | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 35        | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 35        | 0.76%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 34        | 0.74%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 34        | 0.74%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 34        | 0.74%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 32        | 0.7%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 31        | 0.67%   |
| Intel Centrino Advanced-N 6200                                          | 31        | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 31        | 0.67%   |
| Intel Wireless 3165                                                     | 30        | 0.65%   |
| Intel 82577LM Gigabit Network Connection                                | 30        | 0.65%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 29        | 0.63%   |
| Intel Ethernet Connection I219-LM                                       | 29        | 0.63%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 29        | 0.63%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 29        | 0.63%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 28        | 0.61%   |
| Intel 82567LM Gigabit Network Connection                                | 28        | 0.61%   |
| Intel Centrino Ultimate-N 6300                                          | 26        | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 24        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1004      | 41.78%  |
| Qualcomm Atheros                      | 546       | 22.72%  |
| Realtek Semiconductor                 | 361       | 15.02%  |
| Broadcom                              | 238       | 9.9%    |
| Ralink                                | 50        | 2.08%   |
| Broadcom Limited                      | 48        | 2%      |
| Ralink Technology                     | 28        | 1.17%   |
| TP-Link                               | 26        | 1.08%   |
| MediaTek                              | 22        | 0.92%   |
| Sierra Wireless                       | 17        | 0.71%   |
| Qualcomm Atheros Communications       | 8         | 0.33%   |
| Qualcomm                              | 7         | 0.29%   |
| Fibocom                               | 6         | 0.25%   |
| Dell                                  | 6         | 0.25%   |
| D-Link System                         | 5         | 0.21%   |
| ZyDAS                                 | 4         | 0.17%   |
| Ericsson Business Mobile Networks     | 3         | 0.12%   |
| Edimax Technology                     | 3         | 0.12%   |
| Sitecom Europe                        | 2         | 0.08%   |
| NetGear                               | 2         | 0.08%   |
| Linksys                               | 2         | 0.08%   |
| Hewlett-Packard                       | 2         | 0.08%   |
| D-Link                                | 2         | 0.08%   |
| ASUSTek Computer                      | 2         | 0.08%   |
| Winbond Electronics                   | 1         | 0.04%   |
| TRENDnet                              | 1         | 0.04%   |
| Toshiba                               | 1         | 0.04%   |
| Texas Instruments                     | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| BUFFALO                               | 1         | 0.04%   |
| Belkin Components                     | 1         | 0.04%   |
| AVM                                   | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 114       | 4.69%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 100       | 4.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 88        | 3.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 82        | 3.37%   |
| Intel Wireless 7260                                                           | 73        | 3%      |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 72        | 2.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 68        | 2.8%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 65        | 2.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 63        | 2.59%   |
| Intel Wireless 8265 / 8275                                                    | 55        | 2.26%   |
| Intel Wireless 7265                                                           | 55        | 2.26%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 52        | 2.14%   |
| Intel Wi-Fi 6 AX200                                                           | 52        | 2.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 50        | 2.06%   |
| Intel Wireless 8260                                                           | 47        | 1.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 41        | 1.69%   |
| Intel Wi-Fi 6 AX201                                                           | 36        | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 35        | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 35        | 1.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 34        | 1.4%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 34        | 1.4%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 32        | 1.32%   |
| Intel Centrino Advanced-N 6200                                                | 31        | 1.28%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 31        | 1.28%   |
| Intel Wireless 3165                                                           | 30        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 29        | 1.19%   |
| Intel Comet Lake PCH CNVi WiFi                                                | 29        | 1.19%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 28        | 1.15%   |
| Intel Centrino Ultimate-N 6300                                                | 26        | 1.07%   |
| Intel WiFi Link 5100                                                          | 24        | 0.99%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 24        | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 22        | 0.9%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 22        | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 22        | 0.9%    |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 20        | 0.82%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 20        | 0.82%   |
| Intel Centrino Advanced-N 6235                                                | 19        | 0.78%   |
| Intel Wireless-AC 9260                                                        | 18        | 0.74%   |
| Intel Wireless 3160                                                           | 18        | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 17        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 975       | 46.94%  |
| Intel                            | 445       | 21.43%  |
| Qualcomm Atheros                 | 173       | 8.33%   |
| Broadcom                         | 141       | 6.79%   |
| Marvell Technology Group         | 110       | 5.3%    |
| Broadcom Limited                 | 43        | 2.07%   |
| Silicon Integrated Systems [SiS] | 27        | 1.3%    |
| Nvidia                           | 26        | 1.25%   |
| Samsung Electronics              | 23        | 1.11%   |
| JMicron Technology               | 21        | 1.01%   |
| Attansic Technology              | 15        | 0.72%   |
| VIA Technologies                 | 11        | 0.53%   |
| Xiaomi                           | 8         | 0.39%   |
| Huawei Technologies              | 8         | 0.39%   |
| ASIX Electronics                 | 8         | 0.39%   |
| Lenovo                           | 6         | 0.29%   |
| TP-Link                          | 5         | 0.24%   |
| DisplayLink                      | 5         | 0.24%   |
| MediaTek                         | 4         | 0.19%   |
| Motorola PCS                     | 3         | 0.14%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.1%    |
| Spreadtrum Communications        | 2         | 0.1%    |
| OPPO Electronics                 | 2         | 0.1%    |
| LG Electronics                   | 2         | 0.1%    |
| Hewlett-Packard                  | 2         | 0.1%    |
| Apple                            | 2         | 0.1%    |
| ULi Electronics                  | 1         | 0.05%   |
| National Semiconductor           | 1         | 0.05%   |
| Microchip Technology             | 1         | 0.05%   |
| ICS Advent                       | 1         | 0.05%   |
| HTC (High Tech Computer)         | 1         | 0.05%   |
| Foxconn / Hon Hai                | 1         | 0.05%   |
| ASUSTek Computer                 | 1         | 0.05%   |
| Aquantia                         | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 585       | 28.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 286       | 13.72%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 98        | 4.7%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 55        | 2.64%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 34        | 1.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 31        | 1.49%   |
| Intel 82577LM Gigabit Network Connection                                       | 30        | 1.44%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 29        | 1.39%   |
| Intel Ethernet Connection I219-LM                                              | 29        | 1.39%   |
| Intel 82567LM Gigabit Network Connection                                       | 28        | 1.34%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 24        | 1.15%   |
| Intel Ethernet Connection I217-LM                                              | 23        | 1.1%    |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 22        | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                                          | 21        | 1.01%   |
| Intel 82566MM Gigabit Network Connection                                       | 20        | 0.96%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 19        | 0.91%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 19        | 0.91%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 18        | 0.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 17        | 0.82%   |
| Intel Ethernet Connection I218-LM                                              | 17        | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 16        | 0.77%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 15        | 0.72%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 15        | 0.72%   |
| Intel PRO/100 VE Network Connection                                            | 15        | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                                          | 15        | 0.72%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 15        | 0.72%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 14        | 0.67%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 12        | 0.58%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 12        | 0.58%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 12        | 0.58%   |
| Intel Ethernet Connection (10) I219-V                                          | 12        | 0.58%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 12        | 0.58%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 12        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 12        | 0.58%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 11        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 11        | 0.53%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 11        | 0.53%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 11        | 0.53%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 11        | 0.53%   |
| Intel Ethernet Connection (4) I219-V                                           | 11        | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2255      | 51.97%  |
| Ethernet | 2001      | 46.12%  |
| Modem    | 82        | 1.89%   |
| Unknown  | 1         | 0.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1899      | 78.18%  |
| Ethernet | 530       | 21.82%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1863      | 80.3%   |
| 1     | 395       | 17.03%  |
| 0     | 53        | 2.28%   |
| 3     | 9         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1970      | 83.69%  |
| Yes  | 384       | 16.31%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 567       | 38.65%  |
| Broadcom                        | 149       | 10.16%  |
| Realtek Semiconductor           | 146       | 9.95%   |
| Qualcomm Atheros Communications | 142       | 9.68%   |
| Foxconn / Hon Hai               | 63        | 4.29%   |
| Lite-On Technology              | 61        | 4.16%   |
| Dell                            | 55        | 3.75%   |
| IMC Networks                    | 53        | 3.61%   |
| Hewlett-Packard                 | 51        | 3.48%   |
| Apple                           | 36        | 2.45%   |
| Cambridge Silicon Radio         | 34        | 2.32%   |
| Toshiba                         | 21        | 1.43%   |
| ASUSTek Computer                | 17        | 1.16%   |
| Ralink                          | 16        | 1.09%   |
| Alps Electric                   | 14        | 0.95%   |
| Realtek                         | 8         | 0.55%   |
| Foxconn International           | 7         | 0.48%   |
| Ralink Technology               | 6         | 0.41%   |
| MediaTek                        | 4         | 0.27%   |
| Chicony Electronics             | 4         | 0.27%   |
| Taiyo Yuden                     | 3         | 0.2%    |
| Qcom                            | 2         | 0.14%   |
| Micro Star International        | 2         | 0.14%   |
| Integrated System Solution      | 2         | 0.14%   |
| USI                             | 1         | 0.07%   |
| Syntek                          | 1         | 0.07%   |
| Edimax Technology               | 1         | 0.07%   |
| Askey Computer                  | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 262       | 17.84%  |
| Realtek Bluetooth Radio                                                             | 91        | 6.19%   |
| Intel AX201 Bluetooth                                                               | 86        | 5.85%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 69        | 4.7%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 58        | 3.95%   |
| Intel AX200 Bluetooth                                                               | 50        | 3.4%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 39        | 2.65%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 35        | 2.38%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 34        | 2.31%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 32        | 2.18%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 27        | 1.84%   |
| Intel Bluetooth Device                                                              | 26        | 1.77%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 24        | 1.63%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 23        | 1.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 21        | 1.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 21        | 1.43%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 19        | 1.29%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 17        | 1.16%   |
| Ralink RT3290 Bluetooth                                                             | 16        | 1.09%   |
| IMC Networks Bluetooth Device                                                       | 16        | 1.09%   |
| Apple Bluetooth Host Controller                                                     | 16        | 1.09%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 1.02%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 15        | 1.02%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 15        | 1.02%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 15        | 1.02%   |
| Lite-On Bluetooth Device                                                            | 14        | 0.95%   |
| Broadcom BCM2045 Bluetooth                                                          | 14        | 0.95%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 13        | 0.88%   |
| Dell DW375 Bluetooth Module                                                         | 13        | 0.88%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 12        | 0.82%   |
| Intel AX210 Bluetooth                                                               | 12        | 0.82%   |
| IMC Networks Bluetooth Radio                                                        | 12        | 0.82%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 12        | 0.82%   |
| Toshiba Integrated Bluetooth HCI                                                    | 11        | 0.75%   |
| Realtek RTL8723B Bluetooth                                                          | 11        | 0.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 11        | 0.75%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 11        | 0.75%   |
| Apple Bluetooth HCI                                                                 | 11        | 0.75%   |
| Dell Wireless 360 Bluetooth                                                         | 10        | 0.68%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 10        | 0.68%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1835      | 68.86%  |
| AMD                              | 411       | 15.42%  |
| Nvidia                           | 239       | 8.97%   |
| Silicon Integrated Systems [SiS] | 32        | 1.2%    |
| C-Media Electronics              | 22        | 0.83%   |
| VIA Technologies                 | 13        | 0.49%   |
| Logitech                         | 12        | 0.45%   |
| GN Netcom                        | 9         | 0.34%   |
| Lenovo                           | 7         | 0.26%   |
| Plantronics                      | 6         | 0.23%   |
| Texas Instruments                | 5         | 0.19%   |
| Realtek Semiconductor            | 5         | 0.19%   |
| Generalplus Technology           | 5         | 0.19%   |
| ULi Electronics                  | 4         | 0.15%   |
| M-Audio                          | 4         | 0.15%   |
| JMTek                            | 4         | 0.15%   |
| Focusrite-Novation               | 4         | 0.15%   |
| Textech International            | 3         | 0.11%   |
| ASUSTek Computer                 | 3         | 0.11%   |
| Sennheiser Communications        | 2         | 0.08%   |
| BEHRINGER International          | 2         | 0.08%   |
| Avid Technology                  | 2         | 0.08%   |
| Audio-Technica                   | 2         | 0.08%   |
| Apple                            | 2         | 0.08%   |
| ZOOM                             | 1         | 0.04%   |
| XMOS                             | 1         | 0.04%   |
| Tenx Technology                  | 1         | 0.04%   |
| TEAC                             | 1         | 0.04%   |
| TC Electronic                    | 1         | 0.04%   |
| Syntek                           | 1         | 0.04%   |
| Roland                           | 1         | 0.04%   |
| RODE Microphones                 | 1         | 0.04%   |
| QinHeng Electronics              | 1         | 0.04%   |
| PreSonus Audio Electronics       | 1         | 0.04%   |
| Numark                           | 1         | 0.04%   |
| Native Instruments               | 1         | 0.04%   |
| Microsoft                        | 1         | 0.04%   |
| Microchip Technology             | 1         | 0.04%   |
| KORG                             | 1         | 0.04%   |
| Kingston Technology              | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 204       | 6.51%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 182       | 5.81%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 178       | 5.68%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 161       | 5.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 142       | 4.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 139       | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 139       | 4.44%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 126       | 4.02%   |
| AMD FCH Azalia Controller                                                                         | 108       | 3.45%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 76        | 2.43%   |
| Intel 8 Series HD Audio Controller                                                                | 76        | 2.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 68        | 2.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 67        | 2.14%   |
| AMD Kabini HDMI/DP Audio                                                                          | 65        | 2.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 54        | 1.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 53        | 1.69%   |
| Intel Broadwell-U Audio Controller                                                                | 53        | 1.69%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 53        | 1.69%   |
| Intel Cannon Lake PCH cAVS                                                                        | 51        | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 51        | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 47        | 1.5%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 46        | 1.47%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 44        | 1.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 44        | 1.4%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 37        | 1.18%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 35        | 1.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 34        | 1.08%   |
| AMD Wrestler HDMI Audio                                                                           | 33        | 1.05%   |
| Intel Comet Lake PCH cAVS                                                                         | 32        | 1.02%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 28        | 0.89%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 22        | 0.7%    |
| Nvidia High Definition Audio Controller                                                           | 21        | 0.67%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 21        | 0.67%   |
| Intel CM238 HD Audio Controller                                                                   | 21        | 0.67%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 21        | 0.67%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 21        | 0.67%   |
| AMD High Definition Audio Controller                                                              | 21        | 0.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 18        | 0.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 0.57%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 16        | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 352       | 27.08%  |
| SK hynix                                         | 264       | 20.31%  |
| Unknown                                          | 171       | 13.15%  |
| Micron Technology                                | 127       | 9.77%   |
| Kingston                                         | 111       | 8.54%   |
| Crucial                                          | 55        | 4.23%   |
| Elpida                                           | 31        | 2.38%   |
| Ramaxel Technology                               | 30        | 2.31%   |
| Unknown (ABCD)                                   | 28        | 2.15%   |
| A-DATA Technology                                | 18        | 1.38%   |
| Nanya Technology                                 | 17        | 1.31%   |
| Smart                                            | 14        | 1.08%   |
| Corsair                                          | 14        | 1.08%   |
| G.Skill                                          | 11        | 0.85%   |
| GOODRAM                                          | 6         | 0.46%   |
| Transcend                                        | 4         | 0.31%   |
| 48spaces                                         | 4         | 0.31%   |
| fef5                                             | 3         | 0.23%   |
| Unknown                                          | 3         | 0.23%   |
| Unifosa                                          | 2         | 0.15%   |
| Teikon                                           | 2         | 0.15%   |
| Team                                             | 2         | 0.15%   |
| Super Talent                                     | 2         | 0.15%   |
| Qimonda                                          | 2         | 0.15%   |
| High Bridge                                      | 2         | 0.15%   |
| Avant                                            | 2         | 0.15%   |
| Apacer                                           | 2         | 0.15%   |
| V-GeN                                            | 1         | 0.08%   |
| V-Color                                          | 1         | 0.08%   |
| Unknown (7F7F7F7F7F7F6B00)                       | 1         | 0.08%   |
| Unknown (0x36345431323830323145444C335342322020) | 1         | 0.08%   |
| Unknown (0x0043415455000000)                     | 1         | 0.08%   |
| Timetec                                          | 1         | 0.08%   |
| Smart Brazil                                     | 1         | 0.08%   |
| SHARETRONIC                                      | 1         | 0.08%   |
| Patriot                                          | 1         | 0.08%   |
| Neo Forza                                        | 1         | 0.08%   |
| Memox                                            | 1         | 0.08%   |
| Lexar                                            | 1         | 0.08%   |
| Foxline                                          | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 27        | 1.95%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 1.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 18        | 1.3%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 1.23%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 1.08%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 15        | 1.08%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 15        | 1.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 15        | 1.08%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 14        | 1.01%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 12        | 0.87%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 12        | 0.87%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.79%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.72%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 10        | 0.72%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 10        | 0.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.72%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 9         | 0.65%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 9         | 0.65%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.65%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 9         | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 8         | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 8         | 0.58%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 8         | 0.58%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.58%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 8         | 0.58%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 7         | 0.5%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 7         | 0.5%    |
| Unknown RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 6         | 0.43%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 6         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 6         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 6         | 0.43%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.43%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 6         | 0.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.43%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 6         | 0.43%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.43%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 6         | 0.43%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 445       | 39.59%  |
| DDR4    | 394       | 35.05%  |
| DDR2    | 119       | 10.59%  |
| LPDDR4  | 63        | 5.6%    |
| SDRAM   | 33        | 2.94%   |
| LPDDR3  | 28        | 2.49%   |
| Unknown | 13        | 1.16%   |
| DDR     | 11        | 0.98%   |
| DRAM    | 7         | 0.62%   |
| DDR5    | 6         | 0.53%   |
| LPDDR5  | 5         | 0.44%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1018      | 91.71%  |
| Row Of Chips | 66        | 5.95%   |
| Chip         | 11        | 0.99%   |
| Unknown      | 9         | 0.81%   |
| DIMM         | 6         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 8192    | 376       | 30.62%  |
| 4096    | 359       | 29.23%  |
| 2048    | 246       | 20.03%  |
| 16384   | 132       | 10.75%  |
| 1024    | 78        | 6.35%   |
| 32768   | 28        | 2.28%   |
| 512     | 6         | 0.49%   |
| 1536    | 1         | 0.08%   |
| 256     | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 286       | 24.16%  |
| 2667    | 196       | 16.55%  |
| 3200    | 154       | 13.01%  |
| 2400    | 83        | 7.01%   |
| 667     | 76        | 6.42%   |
| 1334    | 68        | 5.74%   |
| 1333    | 58        | 4.9%    |
| 2133    | 40        | 3.38%   |
| Unknown | 40        | 3.38%   |
| 800     | 24        | 2.03%   |
| 4199    | 21        | 1.77%   |
| 1067    | 19        | 1.6%    |
| 4267    | 15        | 1.27%   |
| 3266    | 15        | 1.27%   |
| 1066    | 12        | 1.01%   |
| 533     | 12        | 1.01%   |
| 2048    | 10        | 0.84%   |
| 1867    | 10        | 0.84%   |
| 975     | 10        | 0.84%   |
| 4800    | 7         | 0.59%   |
| 4266    | 4         | 0.34%   |
| 333     | 4         | 0.34%   |
| 6400    | 3         | 0.25%   |
| 3733    | 3         | 0.25%   |
| 1866    | 3         | 0.25%   |
| 400     | 2         | 0.17%   |
| 8400    | 1         | 0.08%   |
| 7467    | 1         | 0.08%   |
| 5500    | 1         | 0.08%   |
| 2933    | 1         | 0.08%   |
| 2134    | 1         | 0.08%   |
| 1800    | 1         | 0.08%   |
| 1776    | 1         | 0.08%   |
| 266     | 1         | 0.08%   |
| 133     | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 9         | 36%     |
| Canon                 | 7         | 28%     |
| Brother Industries    | 3         | 12%     |
| Prolific Technology   | 2         | 8%      |
| Xiaomi                | 1         | 4%      |
| Seiko Epson           | 1         | 4%      |
| Lexmark International | 1         | 4%      |
| Kyocera               | 1         | 4%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port   | 2         | 7.69%   |
| Xiaomi MiMouse 2                | 1         | 3.85%   |
| Seiko Epson L360 Series         | 1         | 3.85%   |
| Lexmark International E360d     | 1         | 3.85%   |
| Kyocera Mita FS-920             | 1         | 3.85%   |
| HP PSC 750xi                    | 1         | 3.85%   |
| HP OfficeJet Reflash            | 1         | 3.85%   |
| HP LaserJet P1005               | 1         | 3.85%   |
| HP LaserJet 1320                | 1         | 3.85%   |
| HP LaserJet 1020                | 1         | 3.85%   |
| HP LaserJet 1018                | 1         | 3.85%   |
| HP LaserJet 1015                | 1         | 3.85%   |
| HP LaserJet 1012                | 1         | 3.85%   |
| HP DeskJet F2100 Printer series | 1         | 3.85%   |
| HP DeskJet 3700 series          | 1         | 3.85%   |
| Canon TS5100 series             | 1         | 3.85%   |
| Canon TS3300 series             | 1         | 3.85%   |
| Canon TS3100 series             | 1         | 3.85%   |
| Canon PIXMA MX320 series        | 1         | 3.85%   |
| Canon MF3200 series             | 1         | 3.85%   |
| Canon LBP6230/6240              | 1         | 3.85%   |
| Canon LBP6000                   | 1         | 3.85%   |
| Brother MFC-L2710DW series      | 1         | 3.85%   |
| Brother HL-L2320D series        | 1         | 3.85%   |
| Brother HL-2140 series          | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 71.43%  |
| Seiko Epson     | 1         | 14.29%  |
| Hewlett-Packard | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 1         | 14.29%  |
| HP ScanJet 3570c                                 | 1         | 14.29%  |
| Canon CanoScan N650U/N656U                       | 1         | 14.29%  |
| Canon CanoScan LIDE 25                           | 1         | 14.29%  |
| Canon CanoScan LiDE 220                          | 1         | 14.29%  |
| Canon CanoScan LiDE 100                          | 1         | 14.29%  |
| Canon CanoScan 4400F                             | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 526       | 28.07%  |
| Microdia                               | 150       | 8%      |
| IMC Networks                           | 141       | 7.52%   |
| Realtek Semiconductor                  | 127       | 6.78%   |
| Suyin                                  | 120       | 6.4%    |
| Bison Electronics                      | 109       | 5.82%   |
| Sunplus Innovation Technology          | 93        | 4.96%   |
| Quanta                                 | 74        | 3.95%   |
| Cheng Uei Precision Industry (Foxlink) | 70        | 3.74%   |
| Silicon Motion                         | 44        | 2.35%   |
| Alcor Micro                            | 42        | 2.24%   |
| Ricoh                                  | 41        | 2.19%   |
| Lite-On Technology                     | 38        | 2.03%   |
| Syntek                                 | 37        | 1.97%   |
| Apple                                  | 34        | 1.81%   |
| Acer                                   | 32        | 1.71%   |
| Logitech                               | 20        | 1.07%   |
| Samsung Electronics                    | 18        | 0.96%   |
| Lenovo                                 | 17        | 0.91%   |
| ALi                                    | 17        | 0.91%   |
| Luxvisions Innotech Limited            | 16        | 0.85%   |
| Z-Star Microelectronics                | 14        | 0.75%   |
| Primax Electronics                     | 10        | 0.53%   |
| Importek                               | 10        | 0.53%   |
| icSpring                               | 8         | 0.43%   |
| Sonix Technology                       | 7         | 0.37%   |
| DigiTech                               | 7         | 0.37%   |
| OmniVision Technologies                | 6         | 0.32%   |
| GEMBIRD                                | 4         | 0.21%   |
| USB Camera CS                          | 3         | 0.16%   |
| 8SSC21D67422V1SR28902JL                | 3         | 0.16%   |
| Y Media                                | 2         | 0.11%   |
| Unknown                                | 2         | 0.11%   |
| SunplusIT                              | 2         | 0.11%   |
| Sunplus Technology                     | 2         | 0.11%   |
| Microsoft                              | 2         | 0.11%   |
| MacroSilicon                           | 2         | 0.11%   |
| Genesys Logic                          | 2         | 0.11%   |
| Cubeternet                             | 2         | 0.11%   |
| YGTek                                  | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 84        | 4.47%   |
| Microdia Integrated_Webcam_HD                    | 38        | 2.02%   |
| Chicony HD Webcam                                | 32        | 1.7%    |
| Realtek Integrated_Webcam_HD                     | 31        | 1.65%   |
| IMC Networks USB2.0 HD UVC WebCam                | 28        | 1.49%   |
| Sunplus Integrated_Webcam_HD                     | 25        | 1.33%   |
| Chicony USB 2.0 Camera                           | 25        | 1.33%   |
| Chicony TOSHIBA Web Camera - HD                  | 24        | 1.28%   |
| IMC Networks Integrated Camera                   | 22        | 1.17%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 19        | 1.01%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 19        | 1.01%   |
| Bison Integrated Camera                          | 19        | 1.01%   |
| Lite-On Integrated Camera                        | 18        | 0.96%   |
| Chicony Lenovo EasyCamera                        | 18        | 0.96%   |
| Chicony HP Truevision HD                         | 18        | 0.96%   |
| Alcor Micro USB 2.0 Camera                       | 18        | 0.96%   |
| Suyin HP TrueVision HD                           | 17        | 0.9%    |
| Samsung Galaxy series, misc. (MTP mode)          | 17        | 0.9%    |
| Bison HD Webcam                                  | 17        | 0.9%    |
| Microdia Sonix USB 2.0 Camera                    | 16        | 0.85%   |
| Bison Lenovo EasyCamera                          | 16        | 0.85%   |
| Sunplus HD WebCam                                | 15        | 0.8%    |
| Microdia Integrated Webcam                       | 15        | 0.8%    |
| Chicony USB2.0 VGA UVC WebCam                    | 15        | 0.8%    |
| Suyin Acer CrystalEye Webcam                     | 14        | 0.74%   |
| IMC Networks UVC VGA Webcam                      | 14        | 0.74%   |
| Chicony HP HD Camera                             | 14        | 0.74%   |
| Bison SunplusIT Integrated Camera                | 14        | 0.74%   |
| Quanta HP Webcam                                 | 13        | 0.69%   |
| Chicony HP Truevision HD camera                  | 13        | 0.69%   |
| Syntek Lenovo EasyCamera                         | 12        | 0.64%   |
| Realtek USB Camera                               | 12        | 0.64%   |
| Chicony USB2.0 Camera                            | 12        | 0.64%   |
| Realtek Lenovo EasyCamera                        | 11        | 0.59%   |
| Quanta VGA WebCam                                | 11        | 0.59%   |
| Quanta HP TrueVision HD Camera                   | 11        | 0.59%   |
| Quanta HD User Facing                            | 11        | 0.59%   |
| Lite-On HP HD Camera                             | 11        | 0.59%   |
| Chicony WebCam                                   | 11        | 0.59%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                  | 11        | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 130       | 36.62%  |
| Synaptics                          | 63        | 17.75%  |
| AuthenTec                          | 56        | 15.77%  |
| Upek                               | 34        | 9.58%   |
| Shenzhen Goodix Technology         | 25        | 7.04%   |
| STMicroelectronics                 | 21        | 5.92%   |
| LighTuning Technology              | 13        | 3.66%   |
| Elan Microelectronics              | 10        | 2.82%   |
| Samsung Electronics                | 1         | 0.28%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.28%   |
| Focal-systems.Corp                 | 1         | 0.28%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 30        | 8.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 30        | 8.45%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 29        | 8.17%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 24        | 6.76%   |
| STMicroelectronics Fingerprint Reader                                      | 21        | 5.92%   |
| Shenzhen Goodix  Fingerprint Device                                        | 19        | 5.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 4.79%   |
| AuthenTec AES2810                                                          | 15        | 4.23%   |
| Validity Sensors Fingerprint scanner                                       | 13        | 3.66%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 3.1%    |
| Validity Sensors VFS491                                                    | 11        | 3.1%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 11        | 3.1%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 2.54%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 2.54%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 8         | 2.25%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 2.25%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 1.97%   |
| AuthenTec AES1600                                                          | 7         | 1.97%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 1.41%   |
| Elan ELAN:Fingerprint                                                      | 5         | 1.41%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.41%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.13%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.13%   |
| Synaptics UWP WBDI Device                                                  | 4         | 1.13%   |
| Synaptics  WBDI                                                            | 4         | 1.13%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 1.13%   |
| LighTuning Fingerprint Reader                                              | 4         | 1.13%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 1.13%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 0.85%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.85%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 0.56%   |
| Synaptics WBDI Device                                                      | 2         | 0.56%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.56%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 0.56%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.56%   |
| Unknown                                                                    | 2         | 0.56%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.28%   |
| Synaptics TouchPad                                                         | 1         | 0.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Broadcom                 | 73        | 36.87%  |
| Alcor Micro              | 54        | 27.27%  |
| O2 Micro                 | 30        | 15.15%  |
| Upek                     | 17        | 8.59%   |
| Lenovo                   | 16        | 8.08%   |
| Yubico.com               | 1         | 0.51%   |
| Reiner SCT Kartensysteme | 1         | 0.51%   |
| OmniKey                  | 1         | 0.51%   |
| Gemalto (was Gemplus)    | 1         | 0.51%   |
| Clay Logic               | 1         | 0.51%   |
| C3PO                     | 1         | 0.51%   |
| Aktiv                    | 1         | 0.51%   |
| Advanced Card Systems    | 1         | 0.51%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 54        | 27.27%  |
| Broadcom BCM5880 Secure Applications Processor                               | 33        | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 23        | 11.62%  |
| Broadcom 5880                                                                | 18        | 9.09%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 8.59%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 8.08%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 5.56%   |
| Broadcom 58200                                                               | 10        | 5.05%   |
| O2 Micro Oz776 SmartCard Reader                                              | 7         | 3.54%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.51%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.51%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.51%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.51%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.51%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.51%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.51%   |
| Aktiv Rutoken lite                                                           | 1         | 0.51%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.51%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1484      | 63.2%   |
| 1     | 668       | 28.45%  |
| 2     | 163       | 6.94%   |
| 3     | 23        | 0.98%   |
| 4     | 6         | 0.26%   |
| 10    | 1         | 0.04%   |
| 8     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |
| 5     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 352       | 32.81%  |
| Graphics card            | 223       | 20.78%  |
| Chipcard                 | 189       | 17.61%  |
| Net/wireless             | 83        | 7.74%   |
| Modem                    | 45        | 4.19%   |
| Camera                   | 36        | 3.36%   |
| Bluetooth                | 27        | 2.52%   |
| Storage                  | 25        | 2.33%   |
| Communication controller | 20        | 1.86%   |
| Card reader              | 19        | 1.77%   |
| Flash memory             | 16        | 1.49%   |
| Multimedia controller    | 14        | 1.3%    |
| Sound                    | 8         | 0.75%   |
| Network                  | 5         | 0.47%   |
| Net/ethernet             | 5         | 0.47%   |
| Unassigned class         | 2         | 0.19%   |
| Dvb card                 | 2         | 0.19%   |
| Storage/ide              | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |

