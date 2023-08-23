Ubuntu 23.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 23.04.

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

Total: 783

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 13 5310            | [d42fa686e5](https://linux-hardware.org/?probe=d42fa686e5) | Aug 12, 2023 |
| Dell          | Inspiron 13 5310            | [45509c2727](https://linux-hardware.org/?probe=45509c2727) | Aug 12, 2023 |
| Dell          | XPS 15 9560                 | [756901f27f](https://linux-hardware.org/?probe=756901f27f) | Aug 12, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [8abafe1b65](https://linux-hardware.org/?probe=8abafe1b65) | Aug 12, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [5892469c5b](https://linux-hardware.org/?probe=5892469c5b) | Aug 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [53196a01fa](https://linux-hardware.org/?probe=53196a01fa) | Aug 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [f8c24a1b02](https://linux-hardware.org/?probe=f8c24a1b02) | Aug 11, 2023 |
| ASUSTek       | K55A                        | [bf260cea2c](https://linux-hardware.org/?probe=bf260cea2c) | Aug 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [b21e9793a5](https://linux-hardware.org/?probe=b21e9793a5) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [fadee3e38d](https://linux-hardware.org/?probe=fadee3e38d) | Aug 11, 2023 |
| Dell          | Precision 5530              | [f74dac5dcf](https://linux-hardware.org/?probe=f74dac5dcf) | Aug 11, 2023 |
| Dell          | Latitude 5400               | [1ec248c607](https://linux-hardware.org/?probe=1ec248c607) | Aug 10, 2023 |
| Lenovo        | ThinkPad Edge 03193VG       | [abb370836a](https://linux-hardware.org/?probe=abb370836a) | Aug 10, 2023 |
| Avell         | A70 ION                     | [6ab02a34e4](https://linux-hardware.org/?probe=6ab02a34e4) | Aug 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | [89e3ef8e6c](https://linux-hardware.org/?probe=89e3ef8e6c) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4180X06       | [77e54b4b97](https://linux-hardware.org/?probe=77e54b4b97) | Aug 10, 2023 |
| Lenovo        | ThinkPad T420 4180X06       | [ba950eb9e1](https://linux-hardware.org/?probe=ba950eb9e1) | Aug 10, 2023 |
| Google        | Snappy                      | [73ecdd5048](https://linux-hardware.org/?probe=73ecdd5048) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [92fda27219](https://linux-hardware.org/?probe=92fda27219) | Aug 10, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [3bd085d1a5](https://linux-hardware.org/?probe=3bd085d1a5) | Aug 10, 2023 |
| Lenovo        | ThinkPad T430 2347AT2       | [a874870955](https://linux-hardware.org/?probe=a874870955) | Aug 09, 2023 |
| Acer          | Aspire A317-53              | [de8d362cb8](https://linux-hardware.org/?probe=de8d362cb8) | Aug 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [194ec12831](https://linux-hardware.org/?probe=194ec12831) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | [abf7479cb8](https://linux-hardware.org/?probe=abf7479cb8) | Aug 09, 2023 |
| Acer          | Aspire V3-112P              | [e6305472c5](https://linux-hardware.org/?probe=e6305472c5) | Aug 09, 2023 |
| Dell          | Latitude 3350               | [77100b2ef6](https://linux-hardware.org/?probe=77100b2ef6) | Aug 09, 2023 |
| Dell          | Latitude 5400               | [773e9320a8](https://linux-hardware.org/?probe=773e9320a8) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | [f3ee04187f](https://linux-hardware.org/?probe=f3ee04187f) | Aug 09, 2023 |
| Acer          | Aspire 4820TG               | [49a63e5cc4](https://linux-hardware.org/?probe=49a63e5cc4) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | [60a28c22c7](https://linux-hardware.org/?probe=60a28c22c7) | Aug 08, 2023 |
| HP            | EliteBook 840 G6            | [9f044dbe9e](https://linux-hardware.org/?probe=9f044dbe9e) | Aug 08, 2023 |
| HP            | ProBook 455 G7              | [bd9f67ee72](https://linux-hardware.org/?probe=bd9f67ee72) | Aug 07, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3ec4223487](https://linux-hardware.org/?probe=3ec4223487) | Aug 07, 2023 |
| Dell          | Latitude 7300               | [932f04033c](https://linux-hardware.org/?probe=932f04033c) | Aug 07, 2023 |
| Dell          | XPS 15 9500                 | [dbefafc94d](https://linux-hardware.org/?probe=dbefafc94d) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [ce02da2586](https://linux-hardware.org/?probe=ce02da2586) | Aug 07, 2023 |
| Acer          | Nitro AN517-52              | [d24385ceb8](https://linux-hardware.org/?probe=d24385ceb8) | Aug 07, 2023 |
| Timi          | TM1607                      | [c545853106](https://linux-hardware.org/?probe=c545853106) | Aug 07, 2023 |
| HP            | EliteBook 840 G6            | [9f230de889](https://linux-hardware.org/?probe=9f230de889) | Aug 07, 2023 |
| HP            | ProBook 450 G2              | [de0ce7c424](https://linux-hardware.org/?probe=de0ce7c424) | Aug 06, 2023 |
| HP            | ProBook 640 G2              | [8dae611904](https://linux-hardware.org/?probe=8dae611904) | Aug 06, 2023 |
| ASUSTek       | K54L                        | [3ce0c0b7b2](https://linux-hardware.org/?probe=3ce0c0b7b2) | Aug 06, 2023 |
| HP            | EliteBook 840 G1            | [8a0a837f0b](https://linux-hardware.org/?probe=8a0a837f0b) | Aug 06, 2023 |
| ASUSTek       | K54L                        | [b28f27325f](https://linux-hardware.org/?probe=b28f27325f) | Aug 06, 2023 |
| Acer          | Aspire A515-56              | [dfe905b869](https://linux-hardware.org/?probe=dfe905b869) | Aug 06, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [4bd753037a](https://linux-hardware.org/?probe=4bd753037a) | Aug 06, 2023 |
| Dell          | Inspiron 15 5510            | [88f7813621](https://linux-hardware.org/?probe=88f7813621) | Aug 06, 2023 |
| HP            | EliteBook 840 G1            | [cc48d8c23e](https://linux-hardware.org/?probe=cc48d8c23e) | Aug 06, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 82BU      | [52b9918d42](https://linux-hardware.org/?probe=52b9918d42) | Aug 06, 2023 |
| Unknown       | Unknown                     | [9431f6f4e8](https://linux-hardware.org/?probe=9431f6f4e8) | Aug 06, 2023 |
| Dell          | Latitude 5590               | [83d389e795](https://linux-hardware.org/?probe=83d389e795) | Aug 06, 2023 |
| Dell          | Latitude 5400               | [e788e3a534](https://linux-hardware.org/?probe=e788e3a534) | Aug 05, 2023 |
| Dell          | Latitude E6420              | [3636e69adb](https://linux-hardware.org/?probe=3636e69adb) | Aug 05, 2023 |
| ASUSTek       | K52Je                       | [34fa8887dd](https://linux-hardware.org/?probe=34fa8887dd) | Aug 05, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [24dc4f34a2](https://linux-hardware.org/?probe=24dc4f34a2) | Aug 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [779c23fe06](https://linux-hardware.org/?probe=779c23fe06) | Aug 05, 2023 |
| Lenovo        | ThinkPad X131e 33671S2      | [3f83b5efac](https://linux-hardware.org/?probe=3f83b5efac) | Aug 05, 2023 |
| MSI           | GF75 Thin 10SCXR            | [21d2f0b558](https://linux-hardware.org/?probe=21d2f0b558) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [364aa911cf](https://linux-hardware.org/?probe=364aa911cf) | Aug 05, 2023 |
| Apple         | MacBookPro14,1              | [08f78bf99a](https://linux-hardware.org/?probe=08f78bf99a) | Aug 05, 2023 |
| HP            | EliteBook 8740w             | [b30001b3fe](https://linux-hardware.org/?probe=b30001b3fe) | Aug 05, 2023 |
| HP            | ZBook Studio G3             | [3f7f45a94e](https://linux-hardware.org/?probe=3f7f45a94e) | Aug 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f7354ee466](https://linux-hardware.org/?probe=f7354ee466) | Aug 04, 2023 |
| Apple         | MacBookAir7,2               | [e21469f818](https://linux-hardware.org/?probe=e21469f818) | Aug 04, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [8a2dafef83](https://linux-hardware.org/?probe=8a2dafef83) | Aug 04, 2023 |
| HP            | Laptop 14s-dq2xxx           | [8aad3290a7](https://linux-hardware.org/?probe=8aad3290a7) | Aug 03, 2023 |
| Apple         | MacBookAir7,2               | [89c0c5c135](https://linux-hardware.org/?probe=89c0c5c135) | Aug 03, 2023 |
| HP            | ZBook Studio G3             | [69b35fdf25](https://linux-hardware.org/?probe=69b35fdf25) | Aug 03, 2023 |
| Shanghai Z... | ZXE CRB                     | [2d4fc6f4ce](https://linux-hardware.org/?probe=2d4fc6f4ce) | Aug 03, 2023 |
| Dell          | Latitude 5490               | [e93c786075](https://linux-hardware.org/?probe=e93c786075) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | [38f33f3878](https://linux-hardware.org/?probe=38f33f3878) | Aug 03, 2023 |
| Samsung       | 930X2K/931X2K               | [5985901bef](https://linux-hardware.org/?probe=5985901bef) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | [49a27fb8fb](https://linux-hardware.org/?probe=49a27fb8fb) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | [e2d58e4a51](https://linux-hardware.org/?probe=e2d58e4a51) | Aug 03, 2023 |
| HP            | Notebook                    | [0e8585ef71](https://linux-hardware.org/?probe=0e8585ef71) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [5f2529e42b](https://linux-hardware.org/?probe=5f2529e42b) | Aug 02, 2023 |
| Panasonic     | CF-SX1WEVHR                 | [4d0d3b78e7](https://linux-hardware.org/?probe=4d0d3b78e7) | Aug 02, 2023 |
| Unknown       | Unknown                     | [41ff18df05](https://linux-hardware.org/?probe=41ff18df05) | Aug 02, 2023 |
| Unknown       | Unknown                     | [eb3d428d41](https://linux-hardware.org/?probe=eb3d428d41) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [cbc721a89f](https://linux-hardware.org/?probe=cbc721a89f) | Aug 01, 2023 |
| HP            | Unknown                     | [f7ffb3c085](https://linux-hardware.org/?probe=f7ffb3c085) | Aug 01, 2023 |
| Acer          | Aspire E5-573G              | [7e3e1a7ee9](https://linux-hardware.org/?probe=7e3e1a7ee9) | Jul 31, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [ff6816b285](https://linux-hardware.org/?probe=ff6816b285) | Jul 31, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [71379f70f2](https://linux-hardware.org/?probe=71379f70f2) | Jul 30, 2023 |
| Dell          | Latitude E6510              | [f8ebba29c6](https://linux-hardware.org/?probe=f8ebba29c6) | Jul 30, 2023 |
| HP            | ProBook 4540s               | [0fae07b574](https://linux-hardware.org/?probe=0fae07b574) | Jul 30, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [579d4eebb8](https://linux-hardware.org/?probe=579d4eebb8) | Jul 29, 2023 |
| Dell          | Precision 5510              | [56b4073d3f](https://linux-hardware.org/?probe=56b4073d3f) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0180... | [cde4989301](https://linux-hardware.org/?probe=cde4989301) | Jul 28, 2023 |
| Apple         | MacBookAir7,2               | [3e7b8ae52e](https://linux-hardware.org/?probe=3e7b8ae52e) | Jul 28, 2023 |
| HP            | ZBook Studio G3             | [68618d14ef](https://linux-hardware.org/?probe=68618d14ef) | Jul 28, 2023 |
| Dell          | Vostro 15 3515              | [08990a8da3](https://linux-hardware.org/?probe=08990a8da3) | Jul 28, 2023 |
| HUAWEI        | BOM-WXX9                    | [1e0ad64e6f](https://linux-hardware.org/?probe=1e0ad64e6f) | Jul 27, 2023 |
| Toshiba       | PORTEGE X30-E               | [c610464fb5](https://linux-hardware.org/?probe=c610464fb5) | Jul 27, 2023 |
| Apple         | MacBookPro8,1               | [d54574b3f8](https://linux-hardware.org/?probe=d54574b3f8) | Jul 27, 2023 |
| HP            | Laptop 14s-fq1xxx           | [84ab2faa6f](https://linux-hardware.org/?probe=84ab2faa6f) | Jul 27, 2023 |
| HUAWEI        | BOHB-WAX9                   | [44647ce47e](https://linux-hardware.org/?probe=44647ce47e) | Jul 26, 2023 |
| Apple         | MacBookPro8,1               | [d0d94c9be7](https://linux-hardware.org/?probe=d0d94c9be7) | Jul 26, 2023 |
| Acer          | Nitro AN17-41               | [7909f8c5f3](https://linux-hardware.org/?probe=7909f8c5f3) | Jul 26, 2023 |
| Dell          | XPS 15 9530                 | [d6855eabe2](https://linux-hardware.org/?probe=d6855eabe2) | Jul 26, 2023 |
| HP            | Pavilion dv6                | [1ed1c25f7e](https://linux-hardware.org/?probe=1ed1c25f7e) | Jul 26, 2023 |
| HP            | ProBook 450 G2              | [18eceddda0](https://linux-hardware.org/?probe=18eceddda0) | Jul 26, 2023 |
| HP            | ProBook 4540s               | [f41d6c4f4b](https://linux-hardware.org/?probe=f41d6c4f4b) | Jul 26, 2023 |
| Sony          | VPCSB1V9R                   | [12b5777cff](https://linux-hardware.org/?probe=12b5777cff) | Jul 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [802ba60219](https://linux-hardware.org/?probe=802ba60219) | Jul 25, 2023 |
| Apple         | MacBookPro9,2               | [af0355313e](https://linux-hardware.org/?probe=af0355313e) | Jul 25, 2023 |
| HP            | Laptop 17-cp0xxx            | [f8720bbd07](https://linux-hardware.org/?probe=f8720bbd07) | Jul 25, 2023 |
| Lenovo        | B590 62743QG                | [d8bd2493ec](https://linux-hardware.org/?probe=d8bd2493ec) | Jul 25, 2023 |
| MSI           | WF66 11UJ                   | [305e24e26d](https://linux-hardware.org/?probe=305e24e26d) | Jul 25, 2023 |
| HP            | ProBook 4540s               | [5c4b165cea](https://linux-hardware.org/?probe=5c4b165cea) | Jul 25, 2023 |
| HP            | ProBook 4540s               | [4ad8be01ca](https://linux-hardware.org/?probe=4ad8be01ca) | Jul 25, 2023 |
| Dell          | Latitude 5420               | [c286ff883f](https://linux-hardware.org/?probe=c286ff883f) | Jul 24, 2023 |
| HP            | EliteBook 840 G3            | [72a17a2b8f](https://linux-hardware.org/?probe=72a17a2b8f) | Jul 24, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [02cae62d32](https://linux-hardware.org/?probe=02cae62d32) | Jul 24, 2023 |
| Google        | Treeya                      | [808e203694](https://linux-hardware.org/?probe=808e203694) | Jul 24, 2023 |
| Google        | Treeya                      | [db2b782253](https://linux-hardware.org/?probe=db2b782253) | Jul 24, 2023 |
| Dell          | Inspiron 3543               | [3fd49d8f38](https://linux-hardware.org/?probe=3fd49d8f38) | Jul 24, 2023 |
| Lenovo        | ThinkPad P50 20EQS2A500     | [d25f59d64d](https://linux-hardware.org/?probe=d25f59d64d) | Jul 23, 2023 |
| ASUSTek       | X45U                        | [53a411cd41](https://linux-hardware.org/?probe=53a411cd41) | Jul 23, 2023 |
| Google        | Lillipup                    | [3915bca457](https://linux-hardware.org/?probe=3915bca457) | Jul 23, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [383118634e](https://linux-hardware.org/?probe=383118634e) | Jul 23, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0XV0... | [4a5ded3dcc](https://linux-hardware.org/?probe=4a5ded3dcc) | Jul 23, 2023 |
| Lenovo        | ThinkPad P53 20QN004BCA     | [04a2ed4bd2](https://linux-hardware.org/?probe=04a2ed4bd2) | Jul 23, 2023 |
| MSI           | Cyborg 15 A12VF             | [62efe51727](https://linux-hardware.org/?probe=62efe51727) | Jul 23, 2023 |
| Dell          | Latitude 3500               | [fcfa320897](https://linux-hardware.org/?probe=fcfa320897) | Jul 23, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [1ee910fc1c](https://linux-hardware.org/?probe=1ee910fc1c) | Jul 22, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [d02b0e9f74](https://linux-hardware.org/?probe=d02b0e9f74) | Jul 22, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [808ae8a334](https://linux-hardware.org/?probe=808ae8a334) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [ca2f317f1a](https://linux-hardware.org/?probe=ca2f317f1a) | Jul 22, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [9f14acd318](https://linux-hardware.org/?probe=9f14acd318) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | [fee4019ae0](https://linux-hardware.org/?probe=fee4019ae0) | Jul 22, 2023 |
| Acer          | Aspire A514-53              | [b754fb3410](https://linux-hardware.org/?probe=b754fb3410) | Jul 21, 2023 |
| Dell          | XPS 9315                    | [f97422b64b](https://linux-hardware.org/?probe=f97422b64b) | Jul 21, 2023 |
| ASUSTek       | B53E                        | [08012052d5](https://linux-hardware.org/?probe=08012052d5) | Jul 21, 2023 |
| Acer          | Aspire E5-553               | [1321d9a034](https://linux-hardware.org/?probe=1321d9a034) | Jul 21, 2023 |
| Acer          | Aspire E5-553               | [7ef01e963d](https://linux-hardware.org/?probe=7ef01e963d) | Jul 21, 2023 |
| HP            | Laptop 14-fq0xxx            | [ce5f140a90](https://linux-hardware.org/?probe=ce5f140a90) | Jul 21, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [e9a58d14e7](https://linux-hardware.org/?probe=e9a58d14e7) | Jul 20, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [64b51936ea](https://linux-hardware.org/?probe=64b51936ea) | Jul 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [903099ae11](https://linux-hardware.org/?probe=903099ae11) | Jul 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [26a2238069](https://linux-hardware.org/?probe=26a2238069) | Jul 19, 2023 |
| Lenovo        | ThinkPad E560 20EV000YUK    | [0e89144534](https://linux-hardware.org/?probe=0e89144534) | Jul 19, 2023 |
| Fujitsu       | LIFEBOOK A544               | [5643f29431](https://linux-hardware.org/?probe=5643f29431) | Jul 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [a646f5d0fb](https://linux-hardware.org/?probe=a646f5d0fb) | Jul 19, 2023 |
| Apple         | MacBookPro5,5               | [b5b8d4fce2](https://linux-hardware.org/?probe=b5b8d4fce2) | Jul 19, 2023 |
| Acer          | Nitro AN17-41               | [81c4c542a9](https://linux-hardware.org/?probe=81c4c542a9) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [dac4434339](https://linux-hardware.org/?probe=dac4434339) | Jul 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | [631e54097b](https://linux-hardware.org/?probe=631e54097b) | Jul 18, 2023 |
| HP            | EliteBook 745 G5            | [7b7cf50cba](https://linux-hardware.org/?probe=7b7cf50cba) | Jul 18, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [dc76c90236](https://linux-hardware.org/?probe=dc76c90236) | Jul 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 4 21H30... | [192f8de028](https://linux-hardware.org/?probe=192f8de028) | Jul 18, 2023 |
| Dell          | Latitude 7480               | [83caa544f7](https://linux-hardware.org/?probe=83caa544f7) | Jul 18, 2023 |
| Dell          | Latitude 7480               | [526e020c94](https://linux-hardware.org/?probe=526e020c94) | Jul 18, 2023 |
| Dell          | Latitude 3500               | [bd6b4ea554](https://linux-hardware.org/?probe=bd6b4ea554) | Jul 18, 2023 |
| ASUSTek       | X756UQ                      | [be24f941c7](https://linux-hardware.org/?probe=be24f941c7) | Jul 17, 2023 |
| Google        | Lick                        | [be8f8d1fd5](https://linux-hardware.org/?probe=be8f8d1fd5) | Jul 17, 2023 |
| Dell          | Inspiron 5521               | [16715e16b9](https://linux-hardware.org/?probe=16715e16b9) | Jul 17, 2023 |
| Dell          | Latitude 7420               | [acf0339a4c](https://linux-hardware.org/?probe=acf0339a4c) | Jul 17, 2023 |
| Dell          | Latitude E7470              | [a3b762c162](https://linux-hardware.org/?probe=a3b762c162) | Jul 17, 2023 |
| Dell          | Latitude E7470              | [69531585c0](https://linux-hardware.org/?probe=69531585c0) | Jul 17, 2023 |
| Google        | Lick                        | [177ed7483f](https://linux-hardware.org/?probe=177ed7483f) | Jul 16, 2023 |
| Dell          | G5 5587                     | [fc861c593a](https://linux-hardware.org/?probe=fc861c593a) | Jul 16, 2023 |
| Apple         | MacBookAir6,2               | [0059901b85](https://linux-hardware.org/?probe=0059901b85) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [45c881b739](https://linux-hardware.org/?probe=45c881b739) | Jul 16, 2023 |
| Dell          | Inspiron 3442               | [4767e5dc31](https://linux-hardware.org/?probe=4767e5dc31) | Jul 15, 2023 |
| Gigabyte      | P65                         | [b46e8302f7](https://linux-hardware.org/?probe=b46e8302f7) | Jul 15, 2023 |
| Acer          | Aspire A315-51              | [938e7cd384](https://linux-hardware.org/?probe=938e7cd384) | Jul 15, 2023 |
| Samsung       | 300E5K/300E5Q               | [92bd2944cb](https://linux-hardware.org/?probe=92bd2944cb) | Jul 15, 2023 |
| Lenovo        | ThinkPad X250 20CL00DHBR    | [dd92f9ce05](https://linux-hardware.org/?probe=dd92f9ce05) | Jul 14, 2023 |
| Alienware     | m15 R7                      | [99e796a389](https://linux-hardware.org/?probe=99e796a389) | Jul 14, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [ea96a066b6](https://linux-hardware.org/?probe=ea96a066b6) | Jul 14, 2023 |
| Lenovo        | G50-70 20351                | [b8481d7a4c](https://linux-hardware.org/?probe=b8481d7a4c) | Jul 14, 2023 |
| Alienware     | m15 R7                      | [e80cfeb390](https://linux-hardware.org/?probe=e80cfeb390) | Jul 14, 2023 |
| Notebook      | N150ZU                      | [61be22ac36](https://linux-hardware.org/?probe=61be22ac36) | Jul 14, 2023 |
| Apple         | MacBookAir6,2               | [5932f3d2eb](https://linux-hardware.org/?probe=5932f3d2eb) | Jul 14, 2023 |
| HP            | ENVY 15                     | [d69bc2702c](https://linux-hardware.org/?probe=d69bc2702c) | Jul 14, 2023 |
| Dell          | Latitude 7480               | [b0ce3265f2](https://linux-hardware.org/?probe=b0ce3265f2) | Jul 14, 2023 |
| Lenovo        | ThinkPad Edge E535 3260C... | [9ff1a61e2a](https://linux-hardware.org/?probe=9ff1a61e2a) | Jul 14, 2023 |
| HP            | Laptop 17-bs1xx             | [26a95caa91](https://linux-hardware.org/?probe=26a95caa91) | Jul 14, 2023 |
| Unknown       | Unknown                     | [a67315ae3e](https://linux-hardware.org/?probe=a67315ae3e) | Jul 13, 2023 |
| Acer          | Swift SF314-71              | [95a7d172c2](https://linux-hardware.org/?probe=95a7d172c2) | Jul 13, 2023 |
| Acer          | Swift SF314-71              | [876eb35009](https://linux-hardware.org/?probe=876eb35009) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | [69bd0f2129](https://linux-hardware.org/?probe=69bd0f2129) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | [20225a0680](https://linux-hardware.org/?probe=20225a0680) | Jul 13, 2023 |
| Acer          | Aspire 4820TG               | [a93793ae9c](https://linux-hardware.org/?probe=a93793ae9c) | Jul 13, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | [1412ecd811](https://linux-hardware.org/?probe=1412ecd811) | Jul 13, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | [49657bd961](https://linux-hardware.org/?probe=49657bd961) | Jul 13, 2023 |
| HUAWEI        | CREM-WXX9                   | [d5ff5f9f79](https://linux-hardware.org/?probe=d5ff5f9f79) | Jul 13, 2023 |
| Positivo      | A14CR6A                     | [7ad49c61bd](https://linux-hardware.org/?probe=7ad49c61bd) | Jul 13, 2023 |
| HP            | Notebook                    | [adbdafe73d](https://linux-hardware.org/?probe=adbdafe73d) | Jul 13, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0V30... | [174cb234d5](https://linux-hardware.org/?probe=174cb234d5) | Jul 12, 2023 |
| HUAWEI        | RLEF-XX                     | [8974860f56](https://linux-hardware.org/?probe=8974860f56) | Jul 12, 2023 |
| Intel Clie... | LAPBC710                    | [c957ebba28](https://linux-hardware.org/?probe=c957ebba28) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [e594307388](https://linux-hardware.org/?probe=e594307388) | Jul 12, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [706f24ffe5](https://linux-hardware.org/?probe=706f24ffe5) | Jul 12, 2023 |
| Lenovo        | ThinkPad X230 2324DP1       | [5b139ff19a](https://linux-hardware.org/?probe=5b139ff19a) | Jul 12, 2023 |
| Samsung       | 950XED                      | [2f8f9d9277](https://linux-hardware.org/?probe=2f8f9d9277) | Jul 12, 2023 |
| Lenovo        | ThinkPad W500 4063JR4       | [e40458ffe3](https://linux-hardware.org/?probe=e40458ffe3) | Jul 12, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [90466d16ca](https://linux-hardware.org/?probe=90466d16ca) | Jul 11, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [5a1636d8ce](https://linux-hardware.org/?probe=5a1636d8ce) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [0fbc8ca097](https://linux-hardware.org/?probe=0fbc8ca097) | Jul 11, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [fddbab0cf6](https://linux-hardware.org/?probe=fddbab0cf6) | Jul 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [443e3f909c](https://linux-hardware.org/?probe=443e3f909c) | Jul 11, 2023 |
| Acer          | Aspire A715-71G             | [cd76343b6e](https://linux-hardware.org/?probe=cd76343b6e) | Jul 11, 2023 |
| Lenovo        | ThinkPad T550 20CK000GCA    | [52f242e136](https://linux-hardware.org/?probe=52f242e136) | Jul 10, 2023 |
| Dell          | Latitude 3580               | [b1bfa37b93](https://linux-hardware.org/?probe=b1bfa37b93) | Jul 10, 2023 |
| Dell          | XPS 15 9530                 | [f60d21d84f](https://linux-hardware.org/?probe=f60d21d84f) | Jul 10, 2023 |
| Acer          | ConceptD CN315-71P          | [a211dd78de](https://linux-hardware.org/?probe=a211dd78de) | Jul 09, 2023 |
| Dell          | Inspiron 3521               | [49c5ec535d](https://linux-hardware.org/?probe=49c5ec535d) | Jul 09, 2023 |
| Acer          | Aspire 4720Z                | [312486a5b7](https://linux-hardware.org/?probe=312486a5b7) | Jul 09, 2023 |
| ASUSTek       | Zenbook UX3404VA_UX3404V... | [e9410cf823](https://linux-hardware.org/?probe=e9410cf823) | Jul 09, 2023 |
| Lenovo        | ThinkPad P50 20EQS2A500     | [d053bea459](https://linux-hardware.org/?probe=d053bea459) | Jul 09, 2023 |
| Acer          | Nitro AN515-46              | [010208e38d](https://linux-hardware.org/?probe=010208e38d) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [b01bdb1bd6](https://linux-hardware.org/?probe=b01bdb1bd6) | Jul 08, 2023 |
| HP            | 14                          | [71d49b008d](https://linux-hardware.org/?probe=71d49b008d) | Jul 08, 2023 |
| HP            | 14                          | [ba511c29ac](https://linux-hardware.org/?probe=ba511c29ac) | Jul 08, 2023 |
| Dell          | Latitude 5290 2-in-1        | [61e7b20b21](https://linux-hardware.org/?probe=61e7b20b21) | Jul 08, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [31d5e724ba](https://linux-hardware.org/?probe=31d5e724ba) | Jul 07, 2023 |
| HP            | ZBook Studio G3             | [790145611f](https://linux-hardware.org/?probe=790145611f) | Jul 07, 2023 |
| Samsung       | 930X2K/931X2K               | [fd0d25039d](https://linux-hardware.org/?probe=fd0d25039d) | Jul 07, 2023 |
| Samsung       | 930X2K/931X2K               | [294e57d915](https://linux-hardware.org/?probe=294e57d915) | Jul 07, 2023 |
| Notebook      | NJx0PU                      | [29ebf426d1](https://linux-hardware.org/?probe=29ebf426d1) | Jul 06, 2023 |
| Toshiba       | PORTEGE X30-E               | [d68e9cd764](https://linux-hardware.org/?probe=d68e9cd764) | Jul 06, 2023 |
| HP            | Laptop 15-fc0xxx            | [a0183085b8](https://linux-hardware.org/?probe=a0183085b8) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [265dc6c0e9](https://linux-hardware.org/?probe=265dc6c0e9) | Jul 06, 2023 |
| HUAWEI        | HVY-WXX9                    | [8d64c46d1d](https://linux-hardware.org/?probe=8d64c46d1d) | Jul 06, 2023 |
| Sony          | VPCEA1AGG                   | [edbc1fff31](https://linux-hardware.org/?probe=edbc1fff31) | Jul 05, 2023 |
| HP            | EliteBook 755 G5            | [356eae0e07](https://linux-hardware.org/?probe=356eae0e07) | Jul 05, 2023 |
| Acer          | Predator G9-591             | [3c20dda613](https://linux-hardware.org/?probe=3c20dda613) | Jul 05, 2023 |
| Dell          | Latitude 5480               | [ac446902dd](https://linux-hardware.org/?probe=ac446902dd) | Jul 05, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [8e16561151](https://linux-hardware.org/?probe=8e16561151) | Jul 05, 2023 |
| HP            | 650                         | [a3077996ad](https://linux-hardware.org/?probe=a3077996ad) | Jul 05, 2023 |
| Dell          | Latitude 3500               | [2ab8fe06f8](https://linux-hardware.org/?probe=2ab8fe06f8) | Jul 05, 2023 |
| Apple         | MacBook8,1                  | [d27490cbe0](https://linux-hardware.org/?probe=d27490cbe0) | Jul 04, 2023 |
| Lenovo        | ThinkPad X250 20CL00DHBR    | [e8f0daea94](https://linux-hardware.org/?probe=e8f0daea94) | Jul 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [d47bc7229c](https://linux-hardware.org/?probe=d47bc7229c) | Jul 04, 2023 |
| Acer          | Aspire 4820TG               | [69e40b4481](https://linux-hardware.org/?probe=69e40b4481) | Jul 04, 2023 |
| MSI           | GF63 Thin 11UC              | [86c82575ec](https://linux-hardware.org/?probe=86c82575ec) | Jul 04, 2023 |
| Acer          | Aspire E5-771G              | [39716dd662](https://linux-hardware.org/?probe=39716dd662) | Jul 03, 2023 |
| Samsung       | 950XED                      | [e81ef31b14](https://linux-hardware.org/?probe=e81ef31b14) | Jul 03, 2023 |
| Lenovo        | Yoga 900-13ISK 80MK         | [75a8750d34](https://linux-hardware.org/?probe=75a8750d34) | Jul 03, 2023 |
| HP            | Laptop 15-da0xxx            | [4e2a9c1363](https://linux-hardware.org/?probe=4e2a9c1363) | Jul 03, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [275acaaa00](https://linux-hardware.org/?probe=275acaaa00) | Jul 03, 2023 |
| Dell          | Latitude 3500               | [4f287ac318](https://linux-hardware.org/?probe=4f287ac318) | Jul 03, 2023 |
| Acer          | Aspire A315-21              | [eaeac1cc79](https://linux-hardware.org/?probe=eaeac1cc79) | Jul 03, 2023 |
| Sony          | VPCEA1AGG                   | [de28a65daa](https://linux-hardware.org/?probe=de28a65daa) | Jul 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [51d003ae6a](https://linux-hardware.org/?probe=51d003ae6a) | Jul 02, 2023 |
| Lenovo        | G50-70 20351                | [033ce7c13d](https://linux-hardware.org/?probe=033ce7c13d) | Jul 02, 2023 |
| Dell          | XPS 17 9710                 | [8f6145f929](https://linux-hardware.org/?probe=8f6145f929) | Jul 02, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | [d703fd9378](https://linux-hardware.org/?probe=d703fd9378) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 20RBCTO1WW     | [3271b3b559](https://linux-hardware.org/?probe=3271b3b559) | Jul 02, 2023 |
| HP            | OMEN by Laptop              | [6ad6d2e8c6](https://linux-hardware.org/?probe=6ad6d2e8c6) | Jul 02, 2023 |
| Gigabyte      | Q2532N                      | [4560685060](https://linux-hardware.org/?probe=4560685060) | Jul 02, 2023 |
| HP            | 245 G6 Notebook PC          | [48195d85f8](https://linux-hardware.org/?probe=48195d85f8) | Jul 02, 2023 |
| Acer          | Aspire A315-21              | [079e6d2d51](https://linux-hardware.org/?probe=079e6d2d51) | Jul 02, 2023 |
| Samsung       | 300E5K/300E5Q               | [5248df0795](https://linux-hardware.org/?probe=5248df0795) | Jul 01, 2023 |
| Acer          | Aspire A315-21              | [079de94ff1](https://linux-hardware.org/?probe=079de94ff1) | Jul 01, 2023 |
| Dell          | Latitude E6410              | [675794fe6e](https://linux-hardware.org/?probe=675794fe6e) | Jul 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [c66f880677](https://linux-hardware.org/?probe=c66f880677) | Jul 01, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [a1a9486fc8](https://linux-hardware.org/?probe=a1a9486fc8) | Jul 01, 2023 |
| Dell          | Latitude 7390               | [ef05796af7](https://linux-hardware.org/?probe=ef05796af7) | Jul 01, 2023 |
| Timi          | TM1701                      | [5dee3c6b81](https://linux-hardware.org/?probe=5dee3c6b81) | Jul 01, 2023 |
| Dell          | Latitude 7390               | [ea8982e574](https://linux-hardware.org/?probe=ea8982e574) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | [88b4565c0b](https://linux-hardware.org/?probe=88b4565c0b) | Jul 01, 2023 |
| HP            | Pavilion TS 11              | [7e1b98b585](https://linux-hardware.org/?probe=7e1b98b585) | Jul 01, 2023 |
| HP            | 245 G6 Notebook PC          | [189320a2cf](https://linux-hardware.org/?probe=189320a2cf) | Jul 01, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [b5d1a7e115](https://linux-hardware.org/?probe=b5d1a7e115) | Jun 30, 2023 |
| Lenovo        | ThinkPad T430 2347AT2       | [951adb91cd](https://linux-hardware.org/?probe=951adb91cd) | Jun 30, 2023 |
| HP            | ProBook 650 G5              | [99a03772fb](https://linux-hardware.org/?probe=99a03772fb) | Jun 30, 2023 |
| HP            | Laptop 17-cp2xxx            | [2012cd2c37](https://linux-hardware.org/?probe=2012cd2c37) | Jun 30, 2023 |
| HP            | 245 G6 Notebook PC          | [22a896d74b](https://linux-hardware.org/?probe=22a896d74b) | Jun 30, 2023 |
| Dell          | Latitude 5440               | [7868400967](https://linux-hardware.org/?probe=7868400967) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [1e4c2cf905](https://linux-hardware.org/?probe=1e4c2cf905) | Jun 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [b98433fa84](https://linux-hardware.org/?probe=b98433fa84) | Jun 29, 2023 |
| Acer          | NC-A515-51G-59DM            | [a521f2cc60](https://linux-hardware.org/?probe=a521f2cc60) | Jun 29, 2023 |
| Intel         | Whiskey Platform            | [1caca06d89](https://linux-hardware.org/?probe=1caca06d89) | Jun 29, 2023 |
| ASUSTek       | K56CB                       | [952909bc80](https://linux-hardware.org/?probe=952909bc80) | Jun 29, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [61930889dc](https://linux-hardware.org/?probe=61930889dc) | Jun 29, 2023 |
| Unknown       | Unknown                     | [d358089f32](https://linux-hardware.org/?probe=d358089f32) | Jun 29, 2023 |
| HP            | Laptop 17-cp2xxx            | [f1a1aa76e2](https://linux-hardware.org/?probe=f1a1aa76e2) | Jun 29, 2023 |
| Sony          | SVE17137CXB                 | [ed6f82dc16](https://linux-hardware.org/?probe=ed6f82dc16) | Jun 29, 2023 |
| Acer          | Nitro AN515-55              | [a41ff8c573](https://linux-hardware.org/?probe=a41ff8c573) | Jun 29, 2023 |
| Lenovo        | ThinkPad X240 20AL00C7MD    | [5c5334f633](https://linux-hardware.org/?probe=5c5334f633) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | [3c4acbf380](https://linux-hardware.org/?probe=3c4acbf380) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ff560998d8](https://linux-hardware.org/?probe=ff560998d8) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [7017964456](https://linux-hardware.org/?probe=7017964456) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | [8ae62960d8](https://linux-hardware.org/?probe=8ae62960d8) | Jun 28, 2023 |
| Acer          | Nitro AN515-54              | [b30ff15571](https://linux-hardware.org/?probe=b30ff15571) | Jun 28, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [90a10ed8ed](https://linux-hardware.org/?probe=90a10ed8ed) | Jun 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [4e40b350ca](https://linux-hardware.org/?probe=4e40b350ca) | Jun 28, 2023 |
| Lenovo        | XiaoXinPro 16 ARP8 83AS     | [1d6bf708ce](https://linux-hardware.org/?probe=1d6bf708ce) | Jun 28, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [8ef6f6f24a](https://linux-hardware.org/?probe=8ef6f6f24a) | Jun 27, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [d4c9f8de35](https://linux-hardware.org/?probe=d4c9f8de35) | Jun 27, 2023 |
| HP            | ENVY 15                     | [0d46d829d2](https://linux-hardware.org/?probe=0d46d829d2) | Jun 27, 2023 |
| HP            | ENVY 15                     | [189cf01c37](https://linux-hardware.org/?probe=189cf01c37) | Jun 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7497c404d4](https://linux-hardware.org/?probe=7497c404d4) | Jun 27, 2023 |
| Daten Tecn... | ESTELAR                     | [0052df6a90](https://linux-hardware.org/?probe=0052df6a90) | Jun 27, 2023 |
| Daten Tecn... | ESTELAR                     | [d5f99bced6](https://linux-hardware.org/?probe=d5f99bced6) | Jun 26, 2023 |
| HUAWEI        | BOM-WXX9                    | [2e9bc10188](https://linux-hardware.org/?probe=2e9bc10188) | Jun 26, 2023 |
| Gateway       | NV57H                       | [a49db45595](https://linux-hardware.org/?probe=a49db45595) | Jun 26, 2023 |
| Gateway       | NV57H                       | [ee84597590](https://linux-hardware.org/?probe=ee84597590) | Jun 26, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | [70a6547925](https://linux-hardware.org/?probe=70a6547925) | Jun 26, 2023 |
| Star Labs     | LabTop                      | [87a0d9dc09](https://linux-hardware.org/?probe=87a0d9dc09) | Jun 26, 2023 |
| Acer          | TravelMate 6493             | [490906b996](https://linux-hardware.org/?probe=490906b996) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [286826f3b2](https://linux-hardware.org/?probe=286826f3b2) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b15f68a294](https://linux-hardware.org/?probe=b15f68a294) | Jun 25, 2023 |
| Acer          | Nitro AN517-54              | [9a87719748](https://linux-hardware.org/?probe=9a87719748) | Jun 25, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [9f1f9757a2](https://linux-hardware.org/?probe=9f1f9757a2) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [223911e8f0](https://linux-hardware.org/?probe=223911e8f0) | Jun 25, 2023 |
| Lenovo        | ThinkPad T460s 20F90036U... | [1809b4709e](https://linux-hardware.org/?probe=1809b4709e) | Jun 25, 2023 |
| HP            | EliteBook 840 G4            | [2e20ab8996](https://linux-hardware.org/?probe=2e20ab8996) | Jun 25, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [7d8f0212e9](https://linux-hardware.org/?probe=7d8f0212e9) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | [ade3806ebb](https://linux-hardware.org/?probe=ade3806ebb) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 15ABA7 82SG       | [8a22a7fba4](https://linux-hardware.org/?probe=8a22a7fba4) | Jun 24, 2023 |
| Notebook      | NLxxPUx                     | [b82cc440a0](https://linux-hardware.org/?probe=b82cc440a0) | Jun 24, 2023 |
| Dell          | G5 5590                     | [6d6974b0eb](https://linux-hardware.org/?probe=6d6974b0eb) | Jun 24, 2023 |
| HP            | ENVY 15                     | [3918cca1e5](https://linux-hardware.org/?probe=3918cca1e5) | Jun 23, 2023 |
| Acer          | Swift SFE16-42              | [9afa4fb174](https://linux-hardware.org/?probe=9afa4fb174) | Jun 22, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [44050251e9](https://linux-hardware.org/?probe=44050251e9) | Jun 22, 2023 |
| Positivo      | Mobile                      | [f9a55866f0](https://linux-hardware.org/?probe=f9a55866f0) | Jun 22, 2023 |
| Positivo      | Mobile                      | [25df2e5abc](https://linux-hardware.org/?probe=25df2e5abc) | Jun 22, 2023 |
| Acer          | Aspire E5-575G              | [0fb6c61a2b](https://linux-hardware.org/?probe=0fb6c61a2b) | Jun 21, 2023 |
| Acer          | Aspire A515-53G             | [430cfefc6a](https://linux-hardware.org/?probe=430cfefc6a) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | [f96a1a3552](https://linux-hardware.org/?probe=f96a1a3552) | Jun 21, 2023 |
| Toshiba       | Satellite Pro C70-B         | [52c4c32098](https://linux-hardware.org/?probe=52c4c32098) | Jun 21, 2023 |
| HP            | EliteBook 830 G6            | [7a29f3d086](https://linux-hardware.org/?probe=7a29f3d086) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [513165d4f6](https://linux-hardware.org/?probe=513165d4f6) | Jun 20, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [b51dda105a](https://linux-hardware.org/?probe=b51dda105a) | Jun 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [bff08fbf94](https://linux-hardware.org/?probe=bff08fbf94) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [15e75e17fc](https://linux-hardware.org/?probe=15e75e17fc) | Jun 20, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [6dea148dd7](https://linux-hardware.org/?probe=6dea148dd7) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [91f85b5bb5](https://linux-hardware.org/?probe=91f85b5bb5) | Jun 19, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [93f576698e](https://linux-hardware.org/?probe=93f576698e) | Jun 19, 2023 |
| HP            | Laptop 15-rb0xx             | [067eeb10e5](https://linux-hardware.org/?probe=067eeb10e5) | Jun 19, 2023 |
| HP            | Notebook                    | [6df5e3f6ff](https://linux-hardware.org/?probe=6df5e3f6ff) | Jun 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [948225d98e](https://linux-hardware.org/?probe=948225d98e) | Jun 18, 2023 |
| Toshiba       | Satellite-L845              | [cfe5a81354](https://linux-hardware.org/?probe=cfe5a81354) | Jun 18, 2023 |
| ASUSTek       | X555LJ                      | [a4bea0f3e3](https://linux-hardware.org/?probe=a4bea0f3e3) | Jun 18, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [8bf2dd01d7](https://linux-hardware.org/?probe=8bf2dd01d7) | Jun 18, 2023 |
| Panasonic     | CF-54-2                     | [48b7e4f212](https://linux-hardware.org/?probe=48b7e4f212) | Jun 18, 2023 |
| HP            | Pavilion dv6                | [f47b055767](https://linux-hardware.org/?probe=f47b055767) | Jun 18, 2023 |
| HUAWEI        | MACHC-WAX9                  | [8f32e75d6e](https://linux-hardware.org/?probe=8f32e75d6e) | Jun 18, 2023 |
| Medion        | S15449                      | [9ee17b411b](https://linux-hardware.org/?probe=9ee17b411b) | Jun 17, 2023 |
| HP            | ENVY 15                     | [10a4cb8865](https://linux-hardware.org/?probe=10a4cb8865) | Jun 17, 2023 |
| Acer          | Aspire A715-71G             | [0ef00ccccc](https://linux-hardware.org/?probe=0ef00ccccc) | Jun 16, 2023 |
| Toshiba       | Satellite C870-199          | [cc18b4ff53](https://linux-hardware.org/?probe=cc18b4ff53) | Jun 16, 2023 |
| MSI           | GF63 Thin 10SC              | [cd928f7cc4](https://linux-hardware.org/?probe=cd928f7cc4) | Jun 16, 2023 |
| MSI           | GF63 Thin 10SC              | [3204bd2215](https://linux-hardware.org/?probe=3204bd2215) | Jun 16, 2023 |
| Packard Be... | EasyNote TK87               | [eeb1bdc4d1](https://linux-hardware.org/?probe=eeb1bdc4d1) | Jun 15, 2023 |
| Packard Be... | EasyNote TK87               | [3ba89fb405](https://linux-hardware.org/?probe=3ba89fb405) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [fe65868ffe](https://linux-hardware.org/?probe=fe65868ffe) | Jun 15, 2023 |
| MSI           | Stealth GS77 12UE           | [48df655e45](https://linux-hardware.org/?probe=48df655e45) | Jun 15, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [e9aeb26aeb](https://linux-hardware.org/?probe=e9aeb26aeb) | Jun 14, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | [f675b70f23](https://linux-hardware.org/?probe=f675b70f23) | Jun 14, 2023 |
| Dell          | XPS 15 9510                 | [9a8a71741e](https://linux-hardware.org/?probe=9a8a71741e) | Jun 14, 2023 |
| Sony          | SVS1312J3EW                 | [6668ed0dbe](https://linux-hardware.org/?probe=6668ed0dbe) | Jun 14, 2023 |
| PC Special... | P65_P67RGRERA               | [49773a4767](https://linux-hardware.org/?probe=49773a4767) | Jun 14, 2023 |
| ASUSTek       | N73SV                       | [b3b70ef13b](https://linux-hardware.org/?probe=b3b70ef13b) | Jun 14, 2023 |
| Toshiba       | PORTEGE X30-D               | [9f26d41d53](https://linux-hardware.org/?probe=9f26d41d53) | Jun 14, 2023 |
| Samsung       | 670Z5E                      | [20f84530c7](https://linux-hardware.org/?probe=20f84530c7) | Jun 14, 2023 |
| Acer          | Nitro AN517-54              | [d0187875be](https://linux-hardware.org/?probe=d0187875be) | Jun 13, 2023 |
| Dell          | Vostro 3420                 | [1ede32fb28](https://linux-hardware.org/?probe=1ede32fb28) | Jun 13, 2023 |
| Dell          | Inspiron 13-7359            | [3ddafcad45](https://linux-hardware.org/?probe=3ddafcad45) | Jun 13, 2023 |
| Alienware     | m15 R7                      | [c4a2634a83](https://linux-hardware.org/?probe=c4a2634a83) | Jun 13, 2023 |
| Alienware     | m15 R7                      | [7b53840b8b](https://linux-hardware.org/?probe=7b53840b8b) | Jun 13, 2023 |
| Apple         | MacBookPro5,5               | [b303846ade](https://linux-hardware.org/?probe=b303846ade) | Jun 13, 2023 |
| Toshiba       | Satellite P755              | [3b0c830987](https://linux-hardware.org/?probe=3b0c830987) | Jun 13, 2023 |
| Dell          | Latitude E7250              | [cc9fc2bace](https://linux-hardware.org/?probe=cc9fc2bace) | Jun 13, 2023 |
| Dell          | 500                         | [b220c5553e](https://linux-hardware.org/?probe=b220c5553e) | Jun 12, 2023 |
| MSI           | Stealth 15M B12UE           | [aabb8192ee](https://linux-hardware.org/?probe=aabb8192ee) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | [b31d9c8e55](https://linux-hardware.org/?probe=b31d9c8e55) | Jun 12, 2023 |
| HUAWEI        | KLVL-WXX9                   | [235239b42b](https://linux-hardware.org/?probe=235239b42b) | Jun 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [d2c4574d58](https://linux-hardware.org/?probe=d2c4574d58) | Jun 11, 2023 |
| ASUSTek       | G750JM                      | [da1f33a87b](https://linux-hardware.org/?probe=da1f33a87b) | Jun 11, 2023 |
| Dell          | Latitude 7480               | [03b8f5a162](https://linux-hardware.org/?probe=03b8f5a162) | Jun 11, 2023 |
| Dell          | Precision 5570              | [32975fdf08](https://linux-hardware.org/?probe=32975fdf08) | Jun 11, 2023 |
| ASUSTek       | GX501VIK                    | [e54a895262](https://linux-hardware.org/?probe=e54a895262) | Jun 11, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | [3d3375df75](https://linux-hardware.org/?probe=3d3375df75) | Jun 10, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [65a47406b0](https://linux-hardware.org/?probe=65a47406b0) | Jun 10, 2023 |
| Lenovo        | ThinkPad T470p 20J7S0XV0... | [b2f7d876c7](https://linux-hardware.org/?probe=b2f7d876c7) | Jun 10, 2023 |
| MSI           | Prestige 13Evo A13M         | [3feb3bce01](https://linux-hardware.org/?probe=3feb3bce01) | Jun 10, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [4b6aa9a912](https://linux-hardware.org/?probe=4b6aa9a912) | Jun 10, 2023 |
| Dell          | Latitude E5500              | [41ad12c465](https://linux-hardware.org/?probe=41ad12c465) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [246facab73](https://linux-hardware.org/?probe=246facab73) | Jun 10, 2023 |
| Sony          | VPCF120FD                   | [47f02bd498](https://linux-hardware.org/?probe=47f02bd498) | Jun 10, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [233dac6c68](https://linux-hardware.org/?probe=233dac6c68) | Jun 09, 2023 |
| Dell          | XPS 9320                    | [c9f26e18c2](https://linux-hardware.org/?probe=c9f26e18c2) | Jun 09, 2023 |
| Dell          | Inspiron 15-5568            | [19b686b7d7](https://linux-hardware.org/?probe=19b686b7d7) | Jun 09, 2023 |
| HP            | Laptop 15s-fq2xxx           | [09ba95bf3b](https://linux-hardware.org/?probe=09ba95bf3b) | Jun 08, 2023 |
| ASUSTek       | X455LA                      | [583596672d](https://linux-hardware.org/?probe=583596672d) | Jun 08, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [8fa2e2acc9](https://linux-hardware.org/?probe=8fa2e2acc9) | Jun 08, 2023 |
| Dell          | Inspiron 5379               | [b161b2177a](https://linux-hardware.org/?probe=b161b2177a) | Jun 08, 2023 |
| Gigabyte      | P2542                       | [12a2415432](https://linux-hardware.org/?probe=12a2415432) | Jun 08, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [ea8584cbda](https://linux-hardware.org/?probe=ea8584cbda) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | [76ca69b8cc](https://linux-hardware.org/?probe=76ca69b8cc) | Jun 07, 2023 |
| Acer          | Aspire E5-553               | [3932ac5190](https://linux-hardware.org/?probe=3932ac5190) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | [ff2ebbb0ae](https://linux-hardware.org/?probe=ff2ebbb0ae) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [265c19be27](https://linux-hardware.org/?probe=265c19be27) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [b0435761df](https://linux-hardware.org/?probe=b0435761df) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | [a76212cc40](https://linux-hardware.org/?probe=a76212cc40) | Jun 07, 2023 |
| HP            | Laptop 15s-fq2xxx           | [9d0aa12b81](https://linux-hardware.org/?probe=9d0aa12b81) | Jun 06, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [e56988bf8e](https://linux-hardware.org/?probe=e56988bf8e) | Jun 06, 2023 |
| Dell          | Latitude 7480               | [61c800a3b4](https://linux-hardware.org/?probe=61c800a3b4) | Jun 06, 2023 |
| Notebook      | P65xHP                      | [bf35e218d7](https://linux-hardware.org/?probe=bf35e218d7) | Jun 06, 2023 |
| Toshiba       | PORTEGE X30-D               | [262ee566e1](https://linux-hardware.org/?probe=262ee566e1) | Jun 06, 2023 |
| HP            | EliteBook 840 G6            | [0763f751ac](https://linux-hardware.org/?probe=0763f751ac) | Jun 05, 2023 |
| Notebook      | P65xHP                      | [51834b893c](https://linux-hardware.org/?probe=51834b893c) | Jun 05, 2023 |
| Toshiba       | Satellite Pro C70-B         | [d4bc6d6c8c](https://linux-hardware.org/?probe=d4bc6d6c8c) | Jun 04, 2023 |
| Sony          | VPCEH2H4E                   | [793e883d0c](https://linux-hardware.org/?probe=793e883d0c) | Jun 04, 2023 |
| Dell          | Inspiron 3442               | [5c1f2cc0d3](https://linux-hardware.org/?probe=5c1f2cc0d3) | Jun 04, 2023 |
| Acer          | Swift SF314-43              | [969354604a](https://linux-hardware.org/?probe=969354604a) | Jun 04, 2023 |
| Dell          | Latitude E5520              | [7e2d1fdd22](https://linux-hardware.org/?probe=7e2d1fdd22) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | [f39742476c](https://linux-hardware.org/?probe=f39742476c) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | [efa49bf468](https://linux-hardware.org/?probe=efa49bf468) | Jun 04, 2023 |
| Dell          | Latitude E5510              | [353a2174af](https://linux-hardware.org/?probe=353a2174af) | Jun 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [6d8d7f6384](https://linux-hardware.org/?probe=6d8d7f6384) | Jun 04, 2023 |
| Lenovo        | ThinkPad P72 20MBCTO1WW     | [4f62d33d84](https://linux-hardware.org/?probe=4f62d33d84) | Jun 04, 2023 |
| ASUSTek       | K52Je                       | [0190eef08c](https://linux-hardware.org/?probe=0190eef08c) | Jun 03, 2023 |
| Dell          | Latitude E6420              | [069b512b91](https://linux-hardware.org/?probe=069b512b91) | Jun 03, 2023 |
| Lenovo        | ThinkPad T420 4236WQD       | [69a63f31e1](https://linux-hardware.org/?probe=69a63f31e1) | Jun 03, 2023 |
| HP            | ENVY 17                     | [79fd438f05](https://linux-hardware.org/?probe=79fd438f05) | Jun 03, 2023 |
| Dell          | Latitude 5491               | [6a8a7e6188](https://linux-hardware.org/?probe=6a8a7e6188) | Jun 03, 2023 |
| Acer          | Aspire 7750G                | [160d4525c6](https://linux-hardware.org/?probe=160d4525c6) | Jun 02, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [fa4bd41f4b](https://linux-hardware.org/?probe=fa4bd41f4b) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [959b76650d](https://linux-hardware.org/?probe=959b76650d) | Jun 02, 2023 |
| Acer          | Aspire ES1-523              | [a080a07f52](https://linux-hardware.org/?probe=a080a07f52) | Jun 02, 2023 |
| Acer          | Aspire 7750G                | [e94cab5008](https://linux-hardware.org/?probe=e94cab5008) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1aea71b6c0](https://linux-hardware.org/?probe=1aea71b6c0) | Jun 02, 2023 |
| Unknown       | Unknown                     | [655398fc94](https://linux-hardware.org/?probe=655398fc94) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [1bdb74a8ba](https://linux-hardware.org/?probe=1bdb74a8ba) | Jun 02, 2023 |
| HP            | ProBook 6450b               | [d3d4e45f9d](https://linux-hardware.org/?probe=d3d4e45f9d) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [f66667b7fb](https://linux-hardware.org/?probe=f66667b7fb) | Jun 01, 2023 |
| Dell          | XPS 15 9570                 | [6d7803788d](https://linux-hardware.org/?probe=6d7803788d) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | [8a69d6c123](https://linux-hardware.org/?probe=8a69d6c123) | Jun 01, 2023 |
| Dell          | Vostro 15 3515              | [ecfe7565f4](https://linux-hardware.org/?probe=ecfe7565f4) | Jun 01, 2023 |
| HP            | EliteBook 2560p             | [e822eb4072](https://linux-hardware.org/?probe=e822eb4072) | Jun 01, 2023 |
| ASUSTek       | K53SK                       | [9b376cdd45](https://linux-hardware.org/?probe=9b376cdd45) | Jun 01, 2023 |
| HP            | Pavilion Notebook           | [3fb05bfb0b](https://linux-hardware.org/?probe=3fb05bfb0b) | May 31, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [560680687c](https://linux-hardware.org/?probe=560680687c) | May 31, 2023 |
| Lenovo        | ThinkPad T480 20L6S7PE0G    | [239faf8c55](https://linux-hardware.org/?probe=239faf8c55) | May 31, 2023 |
| HONOR         | BBR-WAX9                    | [8630cfad52](https://linux-hardware.org/?probe=8630cfad52) | May 31, 2023 |
| Acer          | Nitro AN515-54              | [7c031081c5](https://linux-hardware.org/?probe=7c031081c5) | May 31, 2023 |
| Acer          | Swift SF314-512             | [a8c97baf10](https://linux-hardware.org/?probe=a8c97baf10) | May 31, 2023 |
| ASUSTek       | ROG Strix G513RS_G513RS     | [69b1782cce](https://linux-hardware.org/?probe=69b1782cce) | May 31, 2023 |
| ASUSTek       | K53SK                       | [bfd926c8da](https://linux-hardware.org/?probe=bfd926c8da) | May 30, 2023 |
| VALE          | Notebook Classic C140       | [cdc6168586](https://linux-hardware.org/?probe=cdc6168586) | May 30, 2023 |
| Gigabyte      | P2542                       | [b1064cae7a](https://linux-hardware.org/?probe=b1064cae7a) | May 30, 2023 |
| Dell          | Inspiron 15-3567            | [e51e0ef0da](https://linux-hardware.org/?probe=e51e0ef0da) | May 30, 2023 |
| Gigabyte      | P2542                       | [7cded000f2](https://linux-hardware.org/?probe=7cded000f2) | May 30, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [8002face48](https://linux-hardware.org/?probe=8002face48) | May 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [cddd43859b](https://linux-hardware.org/?probe=cddd43859b) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [46f455ce35](https://linux-hardware.org/?probe=46f455ce35) | May 30, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [1e0fbe86da](https://linux-hardware.org/?probe=1e0fbe86da) | May 29, 2023 |
| Alienware     | x15 R1                      | [19e9b8e338](https://linux-hardware.org/?probe=19e9b8e338) | May 29, 2023 |
| HONOR         | BBR-WAX9                    | [e57b9850f8](https://linux-hardware.org/?probe=e57b9850f8) | May 28, 2023 |
| ALLDOCUBE     | i1405C                      | [7e4475ef13](https://linux-hardware.org/?probe=7e4475ef13) | May 28, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [c2408a1885](https://linux-hardware.org/?probe=c2408a1885) | May 28, 2023 |
| Apple         | MacBookPro10,2              | [34d96aa1df](https://linux-hardware.org/?probe=34d96aa1df) | May 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | [c7afdbbd76](https://linux-hardware.org/?probe=c7afdbbd76) | May 28, 2023 |
| AVITA         | NE14A2                      | [89c5edafbc](https://linux-hardware.org/?probe=89c5edafbc) | May 28, 2023 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | [618a907425](https://linux-hardware.org/?probe=618a907425) | May 27, 2023 |
| Dell          | Vostro 15 3515              | [2fadb86df4](https://linux-hardware.org/?probe=2fadb86df4) | May 27, 2023 |
| Dell          | Latitude 5440               | [9ed4f0e7ac](https://linux-hardware.org/?probe=9ed4f0e7ac) | May 27, 2023 |
| Dell          | Latitude 5480               | [c7566d1ab9](https://linux-hardware.org/?probe=c7566d1ab9) | May 27, 2023 |
| Dell          | Latitude 5480               | [5327e82af6](https://linux-hardware.org/?probe=5327e82af6) | May 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [57b9304725](https://linux-hardware.org/?probe=57b9304725) | May 27, 2023 |
| Acer          | Aspire A315-22              | [18a13174aa](https://linux-hardware.org/?probe=18a13174aa) | May 27, 2023 |
| Dell          | Latitude 7480               | [2c74ec8198](https://linux-hardware.org/?probe=2c74ec8198) | May 27, 2023 |
| Toshiba       | Satellite Pro C70-B         | [3058a75499](https://linux-hardware.org/?probe=3058a75499) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [433b367e58](https://linux-hardware.org/?probe=433b367e58) | May 26, 2023 |
| Acer          | Aspire A515-52G             | [ac85063e46](https://linux-hardware.org/?probe=ac85063e46) | May 26, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [b8bb801b93](https://linux-hardware.org/?probe=b8bb801b93) | May 26, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [a8c4cf6158](https://linux-hardware.org/?probe=a8c4cf6158) | May 26, 2023 |
| Acer          | Predator PT316-51s          | [0242988287](https://linux-hardware.org/?probe=0242988287) | May 26, 2023 |
| HP            | ENVY Laptop 13-ah0503na     | [cdf2d7b4b4](https://linux-hardware.org/?probe=cdf2d7b4b4) | May 25, 2023 |
| Timi          | Xiaomi NoteBook Pro         | [0316f8d274](https://linux-hardware.org/?probe=0316f8d274) | May 25, 2023 |
| Lenovo        | ThinkPad T580 20LAS62M07    | [48ad025649](https://linux-hardware.org/?probe=48ad025649) | May 25, 2023 |
| Google        | Akali 360                   | [2a4bbc5d81](https://linux-hardware.org/?probe=2a4bbc5d81) | May 25, 2023 |
| Acer          | Aspire A715-51G             | [53cbfa6255](https://linux-hardware.org/?probe=53cbfa6255) | May 25, 2023 |
| Toshiba       | Satellite Pro C650          | [50fc04b16c](https://linux-hardware.org/?probe=50fc04b16c) | May 25, 2023 |
| Mediacom      | SMARTBOOK ONE               | [ad010a6b3e](https://linux-hardware.org/?probe=ad010a6b3e) | May 25, 2023 |
| HP            | ZBook Studio G3             | [a7274d19af](https://linux-hardware.org/?probe=a7274d19af) | May 24, 2023 |
| Dell          | Latitude 7390               | [999bb94a31](https://linux-hardware.org/?probe=999bb94a31) | May 24, 2023 |
| HUAWEI        | BOD-WXX9                    | [9486b7ca4f](https://linux-hardware.org/?probe=9486b7ca4f) | May 24, 2023 |
| HP            | Laptop 15s-fq4xxx           | [810c2ac411](https://linux-hardware.org/?probe=810c2ac411) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [4c512786cc](https://linux-hardware.org/?probe=4c512786cc) | May 24, 2023 |
| Dell          | XPS 15 9500                 | [da0b980bc3](https://linux-hardware.org/?probe=da0b980bc3) | May 24, 2023 |
| Allview       | Allbook H                   | [8b0c0a3436](https://linux-hardware.org/?probe=8b0c0a3436) | May 24, 2023 |
| Dell          | Precision 3571              | [3806fcdb9c](https://linux-hardware.org/?probe=3806fcdb9c) | May 24, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | [306ecade71](https://linux-hardware.org/?probe=306ecade71) | May 24, 2023 |
| Dell          | Inspiron 5720               | [c9eaabeb95](https://linux-hardware.org/?probe=c9eaabeb95) | May 24, 2023 |
| HP            | Pavilion dv5                | [2906e3ff3b](https://linux-hardware.org/?probe=2906e3ff3b) | May 24, 2023 |
| HP            | 15                          | [b62229cac1](https://linux-hardware.org/?probe=b62229cac1) | May 24, 2023 |
| HUAWEI        | KLVD-WXX9                   | [4c3c861f80](https://linux-hardware.org/?probe=4c3c861f80) | May 23, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [77f092da32](https://linux-hardware.org/?probe=77f092da32) | May 23, 2023 |
| Dell          | Inspiron 1525               | [a92437f5aa](https://linux-hardware.org/?probe=a92437f5aa) | May 23, 2023 |
| ASUSTek       | X751MA                      | [674b64f381](https://linux-hardware.org/?probe=674b64f381) | May 23, 2023 |
| HP            | Laptop 14s-fq1xxx           | [73d0ff64b6](https://linux-hardware.org/?probe=73d0ff64b6) | May 23, 2023 |
| Acer          | Aspire E5-553               | [3740264eb0](https://linux-hardware.org/?probe=3740264eb0) | May 23, 2023 |
| HP            | 250 G6 Notebook PC          | [431f2db1fc](https://linux-hardware.org/?probe=431f2db1fc) | May 23, 2023 |
| HP            | Laptop 14-dq2xxx            | [fe7d1e1f90](https://linux-hardware.org/?probe=fe7d1e1f90) | May 22, 2023 |
| Dell          | Inspiron 1525               | [2afda2396c](https://linux-hardware.org/?probe=2afda2396c) | May 22, 2023 |
| Acer          | Nitro AN515-46              | [702a597b36](https://linux-hardware.org/?probe=702a597b36) | May 22, 2023 |
| Acer          | Swift SF514-56T             | [81a0e002b7](https://linux-hardware.org/?probe=81a0e002b7) | May 22, 2023 |
| Dell          | Latitude 3420               | [d598f2634f](https://linux-hardware.org/?probe=d598f2634f) | May 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS1GQ00    | [1ea9bac322](https://linux-hardware.org/?probe=1ea9bac322) | May 22, 2023 |
| MSI           | Stealth 15M B12UE           | [4051f4b27d](https://linux-hardware.org/?probe=4051f4b27d) | May 22, 2023 |
| HUAWEI        | NBM-WXX9                    | [e3ea42dd02](https://linux-hardware.org/?probe=e3ea42dd02) | May 22, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | [55a289b426](https://linux-hardware.org/?probe=55a289b426) | May 21, 2023 |
| Apple         | MacBookPro14,2              | [d29f7a36f9](https://linux-hardware.org/?probe=d29f7a36f9) | May 21, 2023 |
| Dell          | Latitude E6530              | [7c04efc558](https://linux-hardware.org/?probe=7c04efc558) | May 21, 2023 |
| Dell          | Inspiron 3542               | [166b73ef05](https://linux-hardware.org/?probe=166b73ef05) | May 20, 2023 |
| HP            | Pavilion dv6                | [17ac43247a](https://linux-hardware.org/?probe=17ac43247a) | May 20, 2023 |
| Unknown       | Unknown                     | [c7157cc723](https://linux-hardware.org/?probe=c7157cc723) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [de162ff16c](https://linux-hardware.org/?probe=de162ff16c) | May 20, 2023 |
| Acer          | Nitro AN517-54              | [105fb43fc1](https://linux-hardware.org/?probe=105fb43fc1) | May 20, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [42ab4c7e67](https://linux-hardware.org/?probe=42ab4c7e67) | May 20, 2023 |
| MSI           | VR601                       | [7f9381407d](https://linux-hardware.org/?probe=7f9381407d) | May 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5bac34a5f5](https://linux-hardware.org/?probe=5bac34a5f5) | May 19, 2023 |
| Dell          | Inspiron 3442               | [a8bb37c78e](https://linux-hardware.org/?probe=a8bb37c78e) | May 19, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [9475bc847b](https://linux-hardware.org/?probe=9475bc847b) | May 19, 2023 |
| HP            | Pavilion dv6                | [4fb1281981](https://linux-hardware.org/?probe=4fb1281981) | May 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [7af74c5864](https://linux-hardware.org/?probe=7af74c5864) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [161776168b](https://linux-hardware.org/?probe=161776168b) | May 18, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [e17fc662cc](https://linux-hardware.org/?probe=e17fc662cc) | May 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [b5d454d4ec](https://linux-hardware.org/?probe=b5d454d4ec) | May 18, 2023 |
| Lenovo        | ThinkPad T550 20CJS1XB00    | [d1569df0f6](https://linux-hardware.org/?probe=d1569df0f6) | May 18, 2023 |
| HP            | Laptop 14-dq0xxx            | [1923d74fbc](https://linux-hardware.org/?probe=1923d74fbc) | May 18, 2023 |
| Dell          | Precision 5570              | [c9e52e6e8c](https://linux-hardware.org/?probe=c9e52e6e8c) | May 18, 2023 |
| MSI           | GF63 Thin 11SC              | [89e05e4477](https://linux-hardware.org/?probe=89e05e4477) | May 17, 2023 |
| Dell          | Latitude E6530              | [e6064ac95c](https://linux-hardware.org/?probe=e6064ac95c) | May 17, 2023 |
| Lenovo        | ThinkPad T480 20L50005GE    | [58b895e713](https://linux-hardware.org/?probe=58b895e713) | May 16, 2023 |
| Toshiba       | IS 1413G                    | [df01be5efd](https://linux-hardware.org/?probe=df01be5efd) | May 16, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ba609eb1e6](https://linux-hardware.org/?probe=ba609eb1e6) | May 15, 2023 |
| VALE          | Notebook Classic C140       | [656e811dfb](https://linux-hardware.org/?probe=656e811dfb) | May 14, 2023 |
| Acer          | Aspire A717-72G             | [1ab0673015](https://linux-hardware.org/?probe=1ab0673015) | May 14, 2023 |
| Acer          | Aspire A717-72G             | [62a46acc18](https://linux-hardware.org/?probe=62a46acc18) | May 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [b08b887e1a](https://linux-hardware.org/?probe=b08b887e1a) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | [020d4612bd](https://linux-hardware.org/?probe=020d4612bd) | May 14, 2023 |
| HP            | Notebook                    | [decd46d3ed](https://linux-hardware.org/?probe=decd46d3ed) | May 14, 2023 |
| HP            | Laptop 14-dq2xxx            | [274fbdb43e](https://linux-hardware.org/?probe=274fbdb43e) | May 14, 2023 |
| Toshiba       | IS 1413G                    | [821d79dc3f](https://linux-hardware.org/?probe=821d79dc3f) | May 14, 2023 |
| MSI           | GS75 Stealth 10SFS          | [a2116b61ea](https://linux-hardware.org/?probe=a2116b61ea) | May 14, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [803f9dba3c](https://linux-hardware.org/?probe=803f9dba3c) | May 13, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [09eb36df64](https://linux-hardware.org/?probe=09eb36df64) | May 13, 2023 |
| Dell          | Inspiron 7520               | [d06731c12e](https://linux-hardware.org/?probe=d06731c12e) | May 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5768cd981e](https://linux-hardware.org/?probe=5768cd981e) | May 13, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [66bff684b7](https://linux-hardware.org/?probe=66bff684b7) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | [14eae60f4f](https://linux-hardware.org/?probe=14eae60f4f) | May 13, 2023 |
| Samsung       | 930X2K/931X2K               | [7ac717a41d](https://linux-hardware.org/?probe=7ac717a41d) | May 13, 2023 |
| Samsung       | 960XFH                      | [6d6b4a9c5e](https://linux-hardware.org/?probe=6d6b4a9c5e) | May 12, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | [795e44d159](https://linux-hardware.org/?probe=795e44d159) | May 12, 2023 |
| ASUSTek       | X555LJ                      | [f39ba53533](https://linux-hardware.org/?probe=f39ba53533) | May 12, 2023 |
| HP            | Stream Notebook             | [5ed3be74da](https://linux-hardware.org/?probe=5ed3be74da) | May 12, 2023 |
| Apple         | MacBookPro11,2              | [ceea346358](https://linux-hardware.org/?probe=ceea346358) | May 12, 2023 |
| Apple         | MacBookPro11,4              | [576d66cba7](https://linux-hardware.org/?probe=576d66cba7) | May 12, 2023 |
| Unknown       | Unknown                     | [8375f52559](https://linux-hardware.org/?probe=8375f52559) | May 12, 2023 |
| HP            | EliteBook 840 G6            | [80158c51fb](https://linux-hardware.org/?probe=80158c51fb) | May 12, 2023 |
| Dell          | Vostro 3500                 | [81f86e6678](https://linux-hardware.org/?probe=81f86e6678) | May 11, 2023 |
| Rombica       | myBook Zenith               | [f7438f1448](https://linux-hardware.org/?probe=f7438f1448) | May 11, 2023 |
| Apple         | MacBookPro9,2               | [ecb43775d1](https://linux-hardware.org/?probe=ecb43775d1) | May 11, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [f9c1eb381f](https://linux-hardware.org/?probe=f9c1eb381f) | May 11, 2023 |
| Unknown       | Unknown                     | [3fbabd3df0](https://linux-hardware.org/?probe=3fbabd3df0) | May 11, 2023 |
| Dell          | Latitude 5490               | [2cba18ddec](https://linux-hardware.org/?probe=2cba18ddec) | May 11, 2023 |
| Lenovo        | Yoga 7 14IRL8 82YL          | [ae2fd3b0ae](https://linux-hardware.org/?probe=ae2fd3b0ae) | May 11, 2023 |
| MSI           | Stealth 14Studio A13VE      | [86f43bbff1](https://linux-hardware.org/?probe=86f43bbff1) | May 10, 2023 |
| Acer          | Aspire 3935                 | [39cbd19b39](https://linux-hardware.org/?probe=39cbd19b39) | May 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [2e58ce6bd7](https://linux-hardware.org/?probe=2e58ce6bd7) | May 10, 2023 |
| Unknown       | Unknown                     | [87e3ae6f24](https://linux-hardware.org/?probe=87e3ae6f24) | May 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [727163d7b9](https://linux-hardware.org/?probe=727163d7b9) | May 09, 2023 |
| Dell          | XPS 13 9380                 | [af31929040](https://linux-hardware.org/?probe=af31929040) | May 09, 2023 |
| Medion        | E6234                       | [6c3bd7d77f](https://linux-hardware.org/?probe=6c3bd7d77f) | May 08, 2023 |
| Toshiba       | Satellite L650              | [ba32d27df1](https://linux-hardware.org/?probe=ba32d27df1) | May 08, 2023 |
| HP            | 625                         | [956346de67](https://linux-hardware.org/?probe=956346de67) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0628913a60](https://linux-hardware.org/?probe=0628913a60) | May 08, 2023 |
| Lenovo        | ThinkPad T460 20FMS1JA00    | [db609197b4](https://linux-hardware.org/?probe=db609197b4) | May 08, 2023 |
| Acer          | Swift SFA16-41              | [7934eebd9b](https://linux-hardware.org/?probe=7934eebd9b) | May 08, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [f23fb5cca0](https://linux-hardware.org/?probe=f23fb5cca0) | May 08, 2023 |
| HP            | Meep                        | [4b99a0c5f8](https://linux-hardware.org/?probe=4b99a0c5f8) | May 08, 2023 |
| Apple         | MacBookPro9,2               | [a8d45ac430](https://linux-hardware.org/?probe=a8d45ac430) | May 07, 2023 |
| Toshiba       | IS 1413G                    | [c437a16a33](https://linux-hardware.org/?probe=c437a16a33) | May 07, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [a312f0545f](https://linux-hardware.org/?probe=a312f0545f) | May 07, 2023 |
| HP            | EliteBook 850 G3            | [9a068c66d5](https://linux-hardware.org/?probe=9a068c66d5) | May 07, 2023 |
| Medion        | E6234                       | [5afe99ed93](https://linux-hardware.org/?probe=5afe99ed93) | May 07, 2023 |
| HP            | Meep                        | [46a81f105c](https://linux-hardware.org/?probe=46a81f105c) | May 07, 2023 |
| Dell          | XPS 13 9380                 | [b4e9bb9147](https://linux-hardware.org/?probe=b4e9bb9147) | May 07, 2023 |
| ASUSTek       | X555LJ                      | [febe8d60fc](https://linux-hardware.org/?probe=febe8d60fc) | May 07, 2023 |
| ASUSTek       | X555LJ                      | [2e25cad4b3](https://linux-hardware.org/?probe=2e25cad4b3) | May 07, 2023 |
| Razer         | Blade                       | [d90bda8f52](https://linux-hardware.org/?probe=d90bda8f52) | May 07, 2023 |
| Dell          | Latitude 5290               | [255da608b8](https://linux-hardware.org/?probe=255da608b8) | May 07, 2023 |
| Dell          | XPS 13 9343                 | [5e91733408](https://linux-hardware.org/?probe=5e91733408) | May 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [9355511511](https://linux-hardware.org/?probe=9355511511) | May 07, 2023 |
| Dell          | Inspiron 5521               | [d5f70fc2eb](https://linux-hardware.org/?probe=d5f70fc2eb) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [50b503ae3e](https://linux-hardware.org/?probe=50b503ae3e) | May 07, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [64bbfa416b](https://linux-hardware.org/?probe=64bbfa416b) | May 07, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [abc9ce4fa4](https://linux-hardware.org/?probe=abc9ce4fa4) | May 06, 2023 |
| Dell          | Latitude E6410              | [535fd92f64](https://linux-hardware.org/?probe=535fd92f64) | May 06, 2023 |
| Dell          | Latitude E4200              | [af2baa1787](https://linux-hardware.org/?probe=af2baa1787) | May 06, 2023 |
| Acer          | Aspire 5810T                | [d4b401ef3f](https://linux-hardware.org/?probe=d4b401ef3f) | May 06, 2023 |
| Dell          | Vostro 3360                 | [13a1e30b53](https://linux-hardware.org/?probe=13a1e30b53) | May 06, 2023 |
| Dell          | Precision 7740              | [4cd3b0701e](https://linux-hardware.org/?probe=4cd3b0701e) | May 06, 2023 |
| Acer          | Aspire 5810T                | [ecdd99c704](https://linux-hardware.org/?probe=ecdd99c704) | May 05, 2023 |
| HP            | Pavilion g6                 | [9e469df99e](https://linux-hardware.org/?probe=9e469df99e) | May 05, 2023 |
| Toshiba       | PORTEGE Z30t-A              | [18cc14eee0](https://linux-hardware.org/?probe=18cc14eee0) | May 05, 2023 |
| Shanghai Z... | ZXE CRB                     | [d63ef842c1](https://linux-hardware.org/?probe=d63ef842c1) | May 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b9cfd37540](https://linux-hardware.org/?probe=b9cfd37540) | May 05, 2023 |
| Google        | Meep                        | [1e5e0e6673](https://linux-hardware.org/?probe=1e5e0e6673) | May 04, 2023 |
| Dell          | XPS 13 9300                 | [8864ce10e7](https://linux-hardware.org/?probe=8864ce10e7) | May 03, 2023 |
| Dell          | XPS 13 9300                 | [8ef1ddf82a](https://linux-hardware.org/?probe=8ef1ddf82a) | May 03, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | [bb924b0c19](https://linux-hardware.org/?probe=bb924b0c19) | May 03, 2023 |
| MSI           | Katana GF66 12UE            | [799a951714](https://linux-hardware.org/?probe=799a951714) | May 03, 2023 |
| Lenovo        | G500s 20245                 | [560b69d616](https://linux-hardware.org/?probe=560b69d616) | May 03, 2023 |
| Toshiba       | IS 1413G                    | [81a4d2ac8b](https://linux-hardware.org/?probe=81a4d2ac8b) | May 03, 2023 |
| Acer          | Aspire E1-571               | [46ecc78df6](https://linux-hardware.org/?probe=46ecc78df6) | May 02, 2023 |
| HP            | EliteBook Folio G1          | [a31ef5e00e](https://linux-hardware.org/?probe=a31ef5e00e) | May 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5101f4e19d](https://linux-hardware.org/?probe=5101f4e19d) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [000c0450b9](https://linux-hardware.org/?probe=000c0450b9) | May 02, 2023 |
| HP            | Notebook                    | [749fa6a38e](https://linux-hardware.org/?probe=749fa6a38e) | May 02, 2023 |
| Acer          | Nitro AN515-44              | [e26aee893f](https://linux-hardware.org/?probe=e26aee893f) | May 01, 2023 |
| HUAWEI        | BOHB-WAX9                   | [3a9a2590e3](https://linux-hardware.org/?probe=3a9a2590e3) | May 01, 2023 |
| HP            | ProBook 430 G4              | [3c422c5e96](https://linux-hardware.org/?probe=3c422c5e96) | May 01, 2023 |
| Acer          | Aspire E1-571               | [7b4e78233a](https://linux-hardware.org/?probe=7b4e78233a) | May 01, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [3be920565f](https://linux-hardware.org/?probe=3be920565f) | May 01, 2023 |
| Medion        | E16402                      | [cff2f785ad](https://linux-hardware.org/?probe=cff2f785ad) | May 01, 2023 |
| Dell          | Latitude E6400              | [33b7764234](https://linux-hardware.org/?probe=33b7764234) | May 01, 2023 |
| Lenovo        | ThinkPad X260 20F5002NAU    | [7fcb72c132](https://linux-hardware.org/?probe=7fcb72c132) | May 01, 2023 |
| HP            | EliteBook 840 G3            | [c490c44357](https://linux-hardware.org/?probe=c490c44357) | May 01, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [4bec088d90](https://linux-hardware.org/?probe=4bec088d90) | Apr 30, 2023 |
| Dell          | XPS 15 9500                 | [93fef964a7](https://linux-hardware.org/?probe=93fef964a7) | Apr 30, 2023 |
| Samsung       | 950XED                      | [41f620de17](https://linux-hardware.org/?probe=41f620de17) | Apr 30, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [1714bffa0e](https://linux-hardware.org/?probe=1714bffa0e) | Apr 30, 2023 |
| Acer          | Peppy                       | [4caf11594a](https://linux-hardware.org/?probe=4caf11594a) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [7a86bdd993](https://linux-hardware.org/?probe=7a86bdd993) | Apr 30, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6206b317f2](https://linux-hardware.org/?probe=6206b317f2) | Apr 30, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [da5f050510](https://linux-hardware.org/?probe=da5f050510) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [1e65b46a12](https://linux-hardware.org/?probe=1e65b46a12) | Apr 29, 2023 |
| ASUSTek       | X751MA                      | [c952010dbb](https://linux-hardware.org/?probe=c952010dbb) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | [6a102a2c37](https://linux-hardware.org/?probe=6a102a2c37) | Apr 29, 2023 |
| Dell          | Inspiron N5110              | [04da6f1db9](https://linux-hardware.org/?probe=04da6f1db9) | Apr 29, 2023 |
| MSI           | Modern 14 A10M              | [22ad1f6bfb](https://linux-hardware.org/?probe=22ad1f6bfb) | Apr 29, 2023 |
| Acer          | Aspire E5-553               | [ff448e32c3](https://linux-hardware.org/?probe=ff448e32c3) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [4490476bd2](https://linux-hardware.org/?probe=4490476bd2) | Apr 29, 2023 |
| Samsung       | 930X2K/931X2K               | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| Acer          | Aspire E5-575G              | [004e0007e4](https://linux-hardware.org/?probe=004e0007e4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T420 4238AB4       | [3f6a89023c](https://linux-hardware.org/?probe=3f6a89023c) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [216a4b9b67](https://linux-hardware.org/?probe=216a4b9b67) | Apr 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [6736f3d911](https://linux-hardware.org/?probe=6736f3d911) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [a808e47839](https://linux-hardware.org/?probe=a808e47839) | Apr 28, 2023 |
| Lenovo        | G50-70 20351                | [67ae1efc54](https://linux-hardware.org/?probe=67ae1efc54) | Apr 28, 2023 |
| Lenovo        | Legion Y7000 81FW           | [b1e6130b77](https://linux-hardware.org/?probe=b1e6130b77) | Apr 28, 2023 |
| Acer          | Swift SF314-512             | [2ba1bab0fe](https://linux-hardware.org/?probe=2ba1bab0fe) | Apr 28, 2023 |
| MSI           | Katana GF66 12UGS           | [3607ee704e](https://linux-hardware.org/?probe=3607ee704e) | Apr 28, 2023 |
| Dell          | XPS 15 9570                 | [3479673283](https://linux-hardware.org/?probe=3479673283) | Apr 28, 2023 |
| Acer          | ConceptD CN315-71P          | [3cc902ff5c](https://linux-hardware.org/?probe=3cc902ff5c) | Apr 28, 2023 |
| Dell          | Latitude E5470              | [caac023f65](https://linux-hardware.org/?probe=caac023f65) | Apr 27, 2023 |
| Valve         | Jupiter                     | [f65ece2859](https://linux-hardware.org/?probe=f65ece2859) | Apr 27, 2023 |
| ASUSTek       | X751MA                      | [eb9967626a](https://linux-hardware.org/?probe=eb9967626a) | Apr 27, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [404ec697ac](https://linux-hardware.org/?probe=404ec697ac) | Apr 27, 2023 |
| Dell          | Inspiron 5567               | [012329ee1f](https://linux-hardware.org/?probe=012329ee1f) | Apr 27, 2023 |
| MSI           | PE60 6QE                    | [1a5ae975ee](https://linux-hardware.org/?probe=1a5ae975ee) | Apr 27, 2023 |
| Acer          | Aspire 5742G                | [a1391b4372](https://linux-hardware.org/?probe=a1391b4372) | Apr 27, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [f0a2365878](https://linux-hardware.org/?probe=f0a2365878) | Apr 27, 2023 |
| Dell          | Inspiron 5558               | [9f3b8c952d](https://linux-hardware.org/?probe=9f3b8c952d) | Apr 27, 2023 |
| Acer          | Aspire E1-571               | [c95605ef8e](https://linux-hardware.org/?probe=c95605ef8e) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [d49ace71b4](https://linux-hardware.org/?probe=d49ace71b4) | Apr 27, 2023 |
| Dell          | Latitude 5520               | [bec614b168](https://linux-hardware.org/?probe=bec614b168) | Apr 26, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [7ca1ebbe7f](https://linux-hardware.org/?probe=7ca1ebbe7f) | Apr 26, 2023 |
| Dell          | Latitude 7420               | [513e0f8b18](https://linux-hardware.org/?probe=513e0f8b18) | Apr 26, 2023 |
| ASUSTek       | X541SA                      | [362ede5435](https://linux-hardware.org/?probe=362ede5435) | Apr 26, 2023 |
| Acer          | Swift SF313-53              | [b487229ea2](https://linux-hardware.org/?probe=b487229ea2) | Apr 25, 2023 |
| MSI           | Modern 14 A10M              | [dc3595e3cc](https://linux-hardware.org/?probe=dc3595e3cc) | Apr 25, 2023 |
| HP            | 240 G8                      | [ab322ed08e](https://linux-hardware.org/?probe=ab322ed08e) | Apr 25, 2023 |
| HP            | 240 G8                      | [8cf9892fe9](https://linux-hardware.org/?probe=8cf9892fe9) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e7b20d71b7](https://linux-hardware.org/?probe=e7b20d71b7) | Apr 25, 2023 |
| Lenovo        | V15 G2 IJL 82QY             | [2732f4b096](https://linux-hardware.org/?probe=2732f4b096) | Apr 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [7d3b6ba1a3](https://linux-hardware.org/?probe=7d3b6ba1a3) | Apr 25, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [93b15a590f](https://linux-hardware.org/?probe=93b15a590f) | Apr 25, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [5fb905227b](https://linux-hardware.org/?probe=5fb905227b) | Apr 25, 2023 |
| Dell          | XPS 13 9310                 | [65ccee11a0](https://linux-hardware.org/?probe=65ccee11a0) | Apr 24, 2023 |
| ICL           | RAYbook Si1512              | [4e960cbe90](https://linux-hardware.org/?probe=4e960cbe90) | Apr 24, 2023 |
| ASUSTek       | GL752VW                     | [26c754e5f0](https://linux-hardware.org/?probe=26c754e5f0) | Apr 24, 2023 |
| Dell          | XPS 13 9310                 | [070d7e791f](https://linux-hardware.org/?probe=070d7e791f) | Apr 24, 2023 |
| Acer          | Aspire 5742G                | [84679bc442](https://linux-hardware.org/?probe=84679bc442) | Apr 24, 2023 |
| Lenovo        | ThinkPad A285 20MXS0NJ00    | [f155ad2bf4](https://linux-hardware.org/?probe=f155ad2bf4) | Apr 24, 2023 |
| ASUSTek       | GL752VW                     | [216aaf8fff](https://linux-hardware.org/?probe=216aaf8fff) | Apr 24, 2023 |
| Gateway       | NV55C                       | [3c560a28cf](https://linux-hardware.org/?probe=3c560a28cf) | Apr 24, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [2e7585d261](https://linux-hardware.org/?probe=2e7585d261) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [59c225df6e](https://linux-hardware.org/?probe=59c225df6e) | Apr 24, 2023 |
| Lenovo        | 20RD001FHV                  | [782ded0435](https://linux-hardware.org/?probe=782ded0435) | Apr 24, 2023 |
| Samsung       | 950XED                      | [6226147e11](https://linux-hardware.org/?probe=6226147e11) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [b1c3492700](https://linux-hardware.org/?probe=b1c3492700) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [db8e950d12](https://linux-hardware.org/?probe=db8e950d12) | Apr 24, 2023 |
| Acer          | Aspire A515-47              | [35a591e26a](https://linux-hardware.org/?probe=35a591e26a) | Apr 24, 2023 |
| Apple         | MacBookPro9,2               | [c820da6570](https://linux-hardware.org/?probe=c820da6570) | Apr 24, 2023 |
| Shanghai Z... | ZXE CRB                     | [298d51ae78](https://linux-hardware.org/?probe=298d51ae78) | Apr 24, 2023 |
| Dell          | Latitude E5470              | [bc1dca3c78](https://linux-hardware.org/?probe=bc1dca3c78) | Apr 24, 2023 |
| HP            | ZBook 17 G5                 | [c1d71592a4](https://linux-hardware.org/?probe=c1d71592a4) | Apr 24, 2023 |
| Acer          | Aspire A317-53              | [c47ec3530e](https://linux-hardware.org/?probe=c47ec3530e) | Apr 24, 2023 |
| Dell          | G5 5590                     | [eef3722c35](https://linux-hardware.org/?probe=eef3722c35) | Apr 23, 2023 |
| HP            | ZBook 17 G5                 | [ce9fd79431](https://linux-hardware.org/?probe=ce9fd79431) | Apr 23, 2023 |
| Dell          | Precision M4400             | [0c367cbf45](https://linux-hardware.org/?probe=0c367cbf45) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4286A44       | [6b6e909d11](https://linux-hardware.org/?probe=6b6e909d11) | Apr 23, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [641374c815](https://linux-hardware.org/?probe=641374c815) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [aa01246f8b](https://linux-hardware.org/?probe=aa01246f8b) | Apr 23, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [90b7213592](https://linux-hardware.org/?probe=90b7213592) | Apr 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [620334c0fc](https://linux-hardware.org/?probe=620334c0fc) | Apr 23, 2023 |
| Dell          | Latitude E6420              | [475a16531a](https://linux-hardware.org/?probe=475a16531a) | Apr 22, 2023 |
| Dell          | Precision M4400             | [291a0de9a8](https://linux-hardware.org/?probe=291a0de9a8) | Apr 22, 2023 |
| Acer          | Nitro AN515-58              | [60251e08f5](https://linux-hardware.org/?probe=60251e08f5) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [ce5e9aad85](https://linux-hardware.org/?probe=ce5e9aad85) | Apr 22, 2023 |
| Acer          | Aspire 7750G                | [afdab44276](https://linux-hardware.org/?probe=afdab44276) | Apr 22, 2023 |
| Acer          | Aspire 7750G                | [1f6e58080a](https://linux-hardware.org/?probe=1f6e58080a) | Apr 22, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [0f5a55a8d1](https://linux-hardware.org/?probe=0f5a55a8d1) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | [63cafebe06](https://linux-hardware.org/?probe=63cafebe06) | Apr 21, 2023 |
| ASUSTek       | N53SN                       | [7c0a7d4494](https://linux-hardware.org/?probe=7c0a7d4494) | Apr 21, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [2a5d9adcd4](https://linux-hardware.org/?probe=2a5d9adcd4) | Apr 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [85fa6bf3d5](https://linux-hardware.org/?probe=85fa6bf3d5) | Apr 21, 2023 |
| Dell          | Latitude E6420              | [5e3466ce98](https://linux-hardware.org/?probe=5e3466ce98) | Apr 21, 2023 |
| Apple         | MacBookAir7,2               | [d34d10b1ad](https://linux-hardware.org/?probe=d34d10b1ad) | Apr 20, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [05321d1ddd](https://linux-hardware.org/?probe=05321d1ddd) | Apr 20, 2023 |
| Dell          | Inspiron 3501               | [e09f00bead](https://linux-hardware.org/?probe=e09f00bead) | Apr 20, 2023 |
| HP            | Pavilion g4                 | [96a0210940](https://linux-hardware.org/?probe=96a0210940) | Apr 20, 2023 |
| Apple         | MacBookAir7,2               | [b54a612e76](https://linux-hardware.org/?probe=b54a612e76) | Apr 20, 2023 |
| Crusaders ... | CS14D01                     | [b25acea9f7](https://linux-hardware.org/?probe=b25acea9f7) | Apr 19, 2023 |
| Dell          | Vostro 15 7510              | [d9e766f446](https://linux-hardware.org/?probe=d9e766f446) | Apr 16, 2023 |
| HUAWEI        | BOM-WXX9                    | [04eead074d](https://linux-hardware.org/?probe=04eead074d) | Apr 14, 2023 |
| HUAWEI        | HLY-WX9XX                   | [d0742654bb](https://linux-hardware.org/?probe=d0742654bb) | Apr 14, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [df35f6916a](https://linux-hardware.org/?probe=df35f6916a) | Apr 14, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | [0c4578a674](https://linux-hardware.org/?probe=0c4578a674) | Apr 14, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [6b481f17c2](https://linux-hardware.org/?probe=6b481f17c2) | Apr 13, 2023 |
| HUAWEI        | BOM-WXX9                    | [c56952417d](https://linux-hardware.org/?probe=c56952417d) | Apr 11, 2023 |
| Toshiba       | IS 1413G                    | [be9d1636a7](https://linux-hardware.org/?probe=be9d1636a7) | Apr 09, 2023 |
| Acer          | Swift SF314-55G             | [e15eaec4c0](https://linux-hardware.org/?probe=e15eaec4c0) | Apr 07, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | [29f00590fb](https://linux-hardware.org/?probe=29f00590fb) | Apr 05, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [a1dceb9ce7](https://linux-hardware.org/?probe=a1dceb9ce7) | Apr 04, 2023 |
| Google        | Akemi                       | [14e5c7b93b](https://linux-hardware.org/?probe=14e5c7b93b) | Apr 04, 2023 |
| HUAWEI        | CREM-WXX9                   | [dd3c0ff2e5](https://linux-hardware.org/?probe=dd3c0ff2e5) | Apr 03, 2023 |
| Samsung       | 767XCL                      | [b5a44d9194](https://linux-hardware.org/?probe=b5a44d9194) | Apr 03, 2023 |
| Dell          | Inspiron 5458               | [38b9db2538](https://linux-hardware.org/?probe=38b9db2538) | Apr 01, 2023 |
| Samsung       | 767XCL                      | [a3167908c0](https://linux-hardware.org/?probe=a3167908c0) | Apr 01, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [13e8d4f50b](https://linux-hardware.org/?probe=13e8d4f50b) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b56e2a41ed](https://linux-hardware.org/?probe=b56e2a41ed) | Mar 31, 2023 |
| Shanghai Z... | ZXE CRB                     | [aafbb2815f](https://linux-hardware.org/?probe=aafbb2815f) | Mar 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4f2d3a2402](https://linux-hardware.org/?probe=4f2d3a2402) | Mar 25, 2023 |
| Shanghai Z... | ZXE CRB                     | [7f98044a04](https://linux-hardware.org/?probe=7f98044a04) | Mar 24, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [8c5fde8c1e](https://linux-hardware.org/?probe=8c5fde8c1e) | Mar 22, 2023 |
| Dell          | Latitude 7520               | [09c8e699d3](https://linux-hardware.org/?probe=09c8e699d3) | Mar 16, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [66094e937a](https://linux-hardware.org/?probe=66094e937a) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | [49130084c4](https://linux-hardware.org/?probe=49130084c4) | Mar 11, 2023 |
| Shanghai Z... | ZXE CRB                     | [a6091bc2e2](https://linux-hardware.org/?probe=a6091bc2e2) | Mar 11, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [89e2fd827d](https://linux-hardware.org/?probe=89e2fd827d) | Mar 05, 2023 |
| Shanghai Z... | ZXE CRB                     | [bb68a61939](https://linux-hardware.org/?probe=bb68a61939) | Mar 05, 2023 |
| Lenovo        | E51-80 80QB                 | [824ece168f](https://linux-hardware.org/?probe=824ece168f) | Mar 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [525be1bcbe](https://linux-hardware.org/?probe=525be1bcbe) | Mar 02, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [830a8a94e2](https://linux-hardware.org/?probe=830a8a94e2) | Mar 02, 2023 |
| Lenovo        | ThinkPad T431s 20AA0016G... | [0bf8c9ca74](https://linux-hardware.org/?probe=0bf8c9ca74) | Mar 02, 2023 |
| Toshiba       | IS 1413G                    | [05ad6c694b](https://linux-hardware.org/?probe=05ad6c694b) | Mar 01, 2023 |
| HP            | Laptop 17-by3xxx            | [5beb40c486](https://linux-hardware.org/?probe=5beb40c486) | Feb 28, 2023 |
| Samsung       | 370E4K                      | [aba5535c2a](https://linux-hardware.org/?probe=aba5535c2a) | Feb 28, 2023 |
| Toshiba       | IS 1413G                    | [c361aabb21](https://linux-hardware.org/?probe=c361aabb21) | Feb 27, 2023 |
| Toshiba       | IS 1413G                    | [17338cbd01](https://linux-hardware.org/?probe=17338cbd01) | Feb 27, 2023 |
| Apple         | MacBookPro10,1              | [816a4eb27e](https://linux-hardware.org/?probe=816a4eb27e) | Feb 26, 2023 |
| HP            | EliteBook 840 G2            | [33dc8202e9](https://linux-hardware.org/?probe=33dc8202e9) | Feb 25, 2023 |
| HUAWEI        | CREM-WXX9                   | [643d79fd46](https://linux-hardware.org/?probe=643d79fd46) | Feb 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [ba0144c710](https://linux-hardware.org/?probe=ba0144c710) | Feb 20, 2023 |
| Apple         | MacBookPro13,3              | [628feb8b19](https://linux-hardware.org/?probe=628feb8b19) | Feb 13, 2023 |
| Apple         | MacBookPro13,3              | [2f591ee9e3](https://linux-hardware.org/?probe=2f591ee9e3) | Feb 13, 2023 |
| Timi          | RedmiBook 15                | [6dffda8f11](https://linux-hardware.org/?probe=6dffda8f11) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Acer          | Aspire V5-552G              | [2750863407](https://linux-hardware.org/?probe=2750863407) | Feb 02, 2023 |
| HP            | ProBook 6560b               | [a9eba68b79](https://linux-hardware.org/?probe=a9eba68b79) | Jan 14, 2023 |
| Samsung       | SBB-DA                      | [a4c6b4f454](https://linux-hardware.org/?probe=a4c6b4f454) | Jan 07, 2023 |
| MSI           | Raider GE67HX 12UGS         | [28822be06e](https://linux-hardware.org/?probe=28822be06e) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [e1ae2ba145](https://linux-hardware.org/?probe=e1ae2ba145) | Dec 24, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d1342c521a](https://linux-hardware.org/?probe=d1342c521a) | Dec 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5c0099832f](https://linux-hardware.org/?probe=5c0099832f) | Dec 15, 2022 |
| Lenovo        | B50-70 20384                | [82edcc6c08](https://linux-hardware.org/?probe=82edcc6c08) | Dec 15, 2022 |
| HUAWEI        | HVY-WXX9                    | [6f8c8644e2](https://linux-hardware.org/?probe=6f8c8644e2) | Dec 10, 2022 |
| HUAWEI        | CREM-WXX9                   | [33f7ac03f4](https://linux-hardware.org/?probe=33f7ac03f4) | Nov 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| Apple         | MacBookPro9,2               | [e87a096d85](https://linux-hardware.org/?probe=e87a096d85) | Nov 27, 2022 |
| Apple         | MacBookPro9,2               | [9e465f741d](https://linux-hardware.org/?probe=9e465f741d) | Nov 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_23.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.0-20-generic        | 285       | 47.82%  |
| 6.2.0-26-generic        | 57        | 9.56%   |
| 6.2.0-25-generic        | 53        | 8.89%   |
| 6.2.0-24-generic        | 53        | 8.89%   |
| 6.2.0-23-generic        | 44        | 7.38%   |
| 5.19.0-21-generic       | 15        | 2.52%   |
| 6.2.0-18-generic        | 11        | 1.85%   |
| 6.4.0-060400-generic    | 7         | 1.17%   |
| 5.19.0-46-generic       | 6         | 1.01%   |
| 5.19.0-41-generic       | 6         | 1.01%   |
| 6.2.0-27-generic        | 5         | 0.84%   |
| 6.1.0-16-generic        | 5         | 0.84%   |
| 6.2.9-060209-generic    | 3         | 0.5%    |
| 5.19.0-31-generic       | 3         | 0.5%    |
| 6.3.5-060305-generic    | 2         | 0.34%   |
| 6.3.2-060302-generic    | 2         | 0.34%   |
| 6.2.0-19-generic        | 2         | 0.34%   |
| 6.2.0-1003-lowlatency   | 2         | 0.34%   |
| 5.19.0-40-generic       | 2         | 0.34%   |
| 5.19.0-28-generic       | 2         | 0.34%   |
| 6.4.8-tkg-cfs           | 1         | 0.17%   |
| 6.4.8-060408-generic    | 1         | 0.17%   |
| 6.4.6-060406-generic    | 1         | 0.17%   |
| 6.4.5-x64v3-xanmod1     | 1         | 0.17%   |
| 6.4.2-tkg-cfs           | 1         | 0.17%   |
| 6.3.8-x64v4-xanmod1     | 1         | 0.17%   |
| 6.3.4-060304-generic    | 1         | 0.17%   |
| 6.3.1-x64v3-xanmod1     | 1         | 0.17%   |
| 6.3.0-rc7               | 1         | 0.17%   |
| 6.3.0-060300rc7-generic | 1         | 0.17%   |
| 6.3.0-060300-generic    | 1         | 0.17%   |
| 6.3.0+                  | 1         | 0.17%   |
| 6.2.6-060206-generic    | 1         | 0.17%   |
| 6.2.12-060212-generic   | 1         | 0.17%   |
| 6.2.11-060211-generic   | 1         | 0.17%   |
| 6.2.0-1008-lowlatency   | 1         | 0.17%   |
| 6.2.0-1005-lowlatency   | 1         | 0.17%   |
| 6.2.0-060200-generic    | 1         | 0.17%   |
| 6.1.0-daily-20221223    | 1         | 0.17%   |
| 6.0.9-060009-generic    | 1         | 0.17%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.0   | 496       | 85.96%  |
| 5.19.0  | 40        | 6.93%   |
| 6.4.0   | 7         | 1.21%   |
| 6.1.0   | 6         | 1.04%   |
| 6.3.0   | 4         | 0.69%   |
| 6.2.9   | 3         | 0.52%   |
| 5.14.0  | 3         | 0.52%   |
| 6.4.8   | 2         | 0.35%   |
| 6.3.5   | 2         | 0.35%   |
| 6.3.2   | 2         | 0.35%   |
| 6.4.6   | 1         | 0.17%   |
| 6.4.5   | 1         | 0.17%   |
| 6.4.2   | 1         | 0.17%   |
| 6.3.8   | 1         | 0.17%   |
| 6.3.4   | 1         | 0.17%   |
| 6.3.1   | 1         | 0.17%   |
| 6.2.6   | 1         | 0.17%   |
| 6.2.12  | 1         | 0.17%   |
| 6.2.11  | 1         | 0.17%   |
| 6.0.9   | 1         | 0.17%   |
| 5.15.0  | 1         | 0.17%   |
| 5.11.0  | 1         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 502       | 87.3%   |
| 5.19    | 40        | 6.96%   |
| 6.3     | 11        | 1.91%   |
| 6.4     | 10        | 1.74%   |
| 6.1     | 6         | 1.04%   |
| 5.14    | 3         | 0.52%   |
| 6.0     | 1         | 0.17%   |
| 5.15    | 1         | 0.17%   |
| 5.11    | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 569       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 557       | 97.72%  |
| X-Cinnamon      | 7         | 1.23%   |
| Unknown         | 4         | 0.7%    |
| sway            | 1         | 0.18%   |
| GNOME Flashback | 1         | 0.18%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 381       | 66.15%  |
| X11     | 187       | 32.47%  |
| Unknown | 6         | 1.04%   |
| Tty     | 2         | 0.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 508       | 89.12%  |
| Unknown | 51        | 8.95%   |
| LightDM | 9         | 1.58%   |
| GREETD  | 1         | 0.18%   |
| GDM     | 1         | 0.18%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 260       | 45.53%  |
| de_DE   | 53        | 9.28%   |
| fr_FR   | 29        | 5.08%   |
| es_ES   | 26        | 4.55%   |
| C       | 25        | 4.38%   |
| pt_BR   | 23        | 4.03%   |
| ru_RU   | 22        | 3.85%   |
| en_GB   | 16        | 2.8%    |
| it_IT   | 15        | 2.63%   |
| pl_PL   | 11        | 1.93%   |
| en_AU   | 10        | 1.75%   |
| en_CA   | 7         | 1.23%   |
| nl_NL   | 6         | 1.05%   |
| en_IN   | 6         | 1.05%   |
| es_MX   | 5         | 0.88%   |
| hu_HU   | 4         | 0.7%    |
| cs_CZ   | 4         | 0.7%    |
| bg_BG   | 4         | 0.7%    |
| Unknown | 4         | 0.7%    |
| en_ZA   | 3         | 0.53%   |
| el_GR   | 3         | 0.53%   |
| zh_CN   | 2         | 0.35%   |
| sv_SE   | 2         | 0.35%   |
| nb_NO   | 2         | 0.35%   |
| ja_JP   | 2         | 0.35%   |
| fr_CA   | 2         | 0.35%   |
| fi_FI   | 2         | 0.35%   |
| de_CH   | 2         | 0.35%   |
| de_AT   | 2         | 0.35%   |
| da_DK   | 2         | 0.35%   |
| ca_ES   | 2         | 0.35%   |
| tr_TR   | 1         | 0.18%   |
| th_TH   | 1         | 0.18%   |
| sr_RS   | 1         | 0.18%   |
| ro_RO   | 1         | 0.18%   |
| pt_PT   | 1         | 0.18%   |
| ko_KR   | 1         | 0.18%   |
| hr_HR   | 1         | 0.18%   |
| fa_IR   | 1         | 0.18%   |
| et_EE   | 1         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 326       | 56.99%  |
| EFI  | 246       | 43.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Tmpfs   | 281       | 49.21%  |
| Ext4    | 266       | 46.58%  |
| Overlay | 15        | 2.63%   |
| Btrfs   | 6         | 1.05%   |
| Zfs     | 2         | 0.35%   |
| Xfs     | 1         | 0.18%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 500       | 87.72%  |
| Unknown | 45        | 7.89%   |
| MBR     | 25        | 4.39%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 522       | 91.58%  |
| Yes       | 48        | 8.42%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 364       | 63.41%  |
| Yes       | 210       | 36.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 118       | 20.74%  |
| Dell                           | 95        | 16.7%   |
| Hewlett-Packard                | 89        | 15.64%  |
| ASUSTek Computer               | 61        | 10.72%  |
| Acer                           | 52        | 9.14%   |
| HUAWEI                         | 21        | 3.69%   |
| Apple                          | 21        | 3.69%   |
| MSI                            | 19        | 3.34%   |
| Toshiba                        | 10        | 1.76%   |
| Samsung Electronics            | 10        | 1.76%   |
| Google                         | 7         | 1.23%   |
| Unknown                        | 7         | 1.23%   |
| Timi                           | 6         | 1.05%   |
| Sony                           | 6         | 1.05%   |
| Notebook                       | 5         | 0.88%   |
| Shanghai Zhaoxin Semiconductor | 3         | 0.53%   |
| Razer                          | 3         | 0.53%   |
| Medion                         | 3         | 0.53%   |
| Gigabyte Technology            | 3         | 0.53%   |
| Alienware                      | 3         | 0.53%   |
| Positivo                       | 2         | 0.35%   |
| Panasonic                      | 2         | 0.35%   |
| Packard Bell                   | 2         | 0.35%   |
| HONOR                          | 2         | 0.35%   |
| Gateway                        | 2         | 0.35%   |
| VALE                           | 1         | 0.18%   |
| Star Labs                      | 1         | 0.18%   |
| Semp Toshiba                   | 1         | 0.18%   |
| Rombica                        | 1         | 0.18%   |
| PC Specialist                  | 1         | 0.18%   |
| Olivetti                       | 1         | 0.18%   |
| Mediacom                       | 1         | 0.18%   |
| Intel Client Systems           | 1         | 0.18%   |
| Intel                          | 1         | 0.18%   |
| ICL                            | 1         | 0.18%   |
| Fujitsu                        | 1         | 0.18%   |
| Daten Tecnologia               | 1         | 0.18%   |
| Crusaders Corporate (Pty)      | 1         | 0.18%   |
| AVITA                          | 1         | 0.18%   |
| Avell                          | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 8         | 1.41%   |
| Dell Latitude 7480               | 5         | 0.88%   |
| HUAWEI BOM-WXX9                  | 4         | 0.7%    |
| HP Notebook                      | 4         | 0.7%    |
| HP EliteBook 840 G6              | 4         | 0.7%    |
| Apple MacBookPro9,2              | 4         | 0.7%    |
| Apple MacBookAir7,2              | 4         | 0.7%    |
| Shanghai Zhaoxin ZXE CRB         | 3         | 0.53%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7 | 3         | 0.53%   |
| Lenovo G50-70 20351              | 3         | 0.53%   |
| HUAWEI BOHB-WAX9                 | 3         | 0.53%   |
| Dell XPS 15 9500                 | 3         | 0.53%   |
| Dell Inspiron 3442               | 3         | 0.53%   |
| ASUS Zenbook UM5302TA_UM5302TA   | 3         | 0.53%   |
| Acer Swift SF314-512             | 3         | 0.53%   |
| Toshiba Satellite Pro C70-B      | 2         | 0.35%   |
| Timi Redmi Book Pro 14 2022      | 2         | 0.35%   |
| MSI Stealth 15M B12UE            | 2         | 0.35%   |
| MSI Modern 14 A10M               | 2         | 0.35%   |
| Lenovo IdeaPad 5 15ITL05 82FG    | 2         | 0.35%   |
| Lenovo IdeaPad 5 15ARE05 81YQ    | 2         | 0.35%   |
| HUAWEI KLVD-WXX9                 | 2         | 0.35%   |
| HUAWEI HVY-WXX9                  | 2         | 0.35%   |
| HUAWEI CREM-WXX9                 | 2         | 0.35%   |
| HUAWEI BOD-WXX9                  | 2         | 0.35%   |
| HONOR BBR-WAX9                   | 2         | 0.35%   |
| HP ZBook Studio G3               | 2         | 0.35%   |
| HP Pavilion Notebook             | 2         | 0.35%   |
| HP Pavilion dv6                  | 2         | 0.35%   |
| HP Meep                          | 2         | 0.35%   |
| HP Laptop 15s-eq2xxx             | 2         | 0.35%   |
| HP Laptop 14s-fq1xxx             | 2         | 0.35%   |
| HP Laptop 14-dq2xxx              | 2         | 0.35%   |
| HP EliteBook 840 G3              | 2         | 0.35%   |
| Dell XPS 15 9570                 | 2         | 0.35%   |
| Dell Precision 5570              | 2         | 0.35%   |
| Dell Latitude E6420              | 2         | 0.35%   |
| Dell Latitude E5470              | 2         | 0.35%   |
| Dell Latitude 7420               | 2         | 0.35%   |
| Dell Latitude 7390               | 2         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 68        | 11.95%  |
| Dell Latitude         | 42        | 7.38%   |
| Acer Aspire           | 27        | 4.75%   |
| Lenovo IdeaPad        | 24        | 4.22%   |
| Dell Inspiron         | 22        | 3.87%   |
| ASUS VivoBook         | 22        | 3.87%   |
| HP EliteBook          | 19        | 3.34%   |
| HP Laptop             | 18        | 3.16%   |
| HP Pavilion           | 16        | 2.81%   |
| Dell XPS              | 16        | 2.81%   |
| HP ProBook            | 10        | 1.76%   |
| Acer Swift            | 10        | 1.76%   |
| Acer Nitro            | 10        | 1.76%   |
| ASUS Zenbook          | 9         | 1.58%   |
| Unknown               | 8         | 1.41%   |
| Dell Precision        | 7         | 1.23%   |
| Toshiba Satellite     | 6         | 1.05%   |
| Lenovo Legion         | 6         | 1.05%   |
| ASUS ASUS             | 6         | 1.05%   |
| MSI Stealth           | 4         | 0.7%    |
| Lenovo Yoga           | 4         | 0.7%    |
| Lenovo ThinkBook      | 4         | 0.7%    |
| HUAWEI BOM-WXX9       | 4         | 0.7%    |
| HP ZBook              | 4         | 0.7%    |
| HP Notebook           | 4         | 0.7%    |
| Dell Vostro           | 4         | 0.7%    |
| Apple MacBookPro9     | 4         | 0.7%    |
| Apple MacBookAir7     | 4         | 0.7%    |
| Toshiba PORTEGE       | 3         | 0.53%   |
| Shanghai Zhaoxin ZXE  | 3         | 0.53%   |
| Razer Blade           | 3         | 0.53%   |
| MSI GF63              | 3         | 0.53%   |
| Lenovo G50-70         | 3         | 0.53%   |
| HUAWEI BOHB-WAX9      | 3         | 0.53%   |
| HP ENVY               | 3         | 0.53%   |
| Dell G5               | 3         | 0.53%   |
| Apple MacBookPro14    | 3         | 0.53%   |
| Timi Redmi            | 2         | 0.35%   |
| Packard Bell EasyNote | 2         | 0.35%   |
| MSI Modern            | 2         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 94        | 16.52%  |
| 2022    | 70        | 12.3%   |
| 2020    | 59        | 10.37%  |
| 2019    | 45        | 7.91%   |
| 2016    | 38        | 6.68%   |
| 2017    | 33        | 5.8%    |
| 2023    | 30        | 5.27%   |
| 2018    | 30        | 5.27%   |
| 2011    | 30        | 5.27%   |
| 2012    | 29        | 5.1%    |
| 2015    | 27        | 4.75%   |
| 2014    | 25        | 4.39%   |
| 2013    | 20        | 3.51%   |
| 2010    | 19        | 3.34%   |
| 2009    | 9         | 1.58%   |
| 2008    | 8         | 1.41%   |
| 2007    | 2         | 0.35%   |
| Unknown | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 569       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 498       | 87.37%  |
| Enabled  | 72        | 12.63%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 560       | 98.42%  |
| Yes  | 9         | 1.58%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 171       | 30.05%  |
| 16.01-24.0  | 116       | 20.39%  |
| 8.01-16.0   | 109       | 19.16%  |
| 3.01-4.0    | 82        | 14.41%  |
| 32.01-64.0  | 59        | 10.37%  |
| 24.01-32.0  | 17        | 2.99%   |
| 64.01-256.0 | 10        | 1.76%   |
| 1.01-2.0    | 5         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 195       | 33.11%  |
| 1.01-2.0   | 138       | 23.43%  |
| 4.01-8.0   | 127       | 21.56%  |
| 3.01-4.0   | 103       | 17.49%  |
| 8.01-16.0  | 21        | 3.57%   |
| 16.01-24.0 | 3         | 0.51%   |
| 32.01-64.0 | 1         | 0.17%   |
| 24.01-32.0 | 1         | 0.17%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 435       | 76.05%  |
| 2      | 123       | 21.5%   |
| 3      | 10        | 1.75%   |
| 4      | 2         | 0.35%   |
| 0      | 2         | 0.35%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 441       | 77.5%   |
| Yes       | 128       | 22.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 386       | 67.84%  |
| No        | 183       | 32.16%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 562       | 98.77%  |
| No        | 7         | 1.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 494       | 86.51%  |
| No        | 77        | 13.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 80        | 14.04%  |
| Germany      | 60        | 10.53%  |
| Brazil       | 35        | 6.14%   |
| Russia       | 34        | 5.96%   |
| France       | 33        | 5.79%   |
| Italy        | 29        | 5.09%   |
| UK           | 19        | 3.33%   |
| Spain        | 19        | 3.33%   |
| India        | 16        | 2.81%   |
| Australia    | 15        | 2.63%   |
| Canada       | 14        | 2.46%   |
| Netherlands  | 13        | 2.28%   |
| Poland       | 12        | 2.11%   |
| Norway       | 12        | 2.11%   |
| Mexico       | 11        | 1.93%   |
| Romania      | 9         | 1.58%   |
| Turkey       | 7         | 1.23%   |
| Switzerland  | 7         | 1.23%   |
| Czechia      | 7         | 1.23%   |
| Belgium      | 7         | 1.23%   |
| Sweden       | 6         | 1.05%   |
| Chile        | 6         | 1.05%   |
| Portugal     | 5         | 0.88%   |
| Indonesia    | 5         | 0.88%   |
| China        | 5         | 0.88%   |
| South Africa | 4         | 0.7%    |
| Kenya        | 4         | 0.7%    |
| Japan        | 4         | 0.7%    |
| Hungary      | 4         | 0.7%    |
| Greece       | 4         | 0.7%    |
| Finland      | 4         | 0.7%    |
| Colombia     | 4         | 0.7%    |
| Bulgaria     | 4         | 0.7%    |
| Belarus      | 4         | 0.7%    |
| Austria      | 4         | 0.7%    |
| Vietnam      | 3         | 0.53%   |
| Serbia       | 3         | 0.53%   |
| Qatar        | 3         | 0.53%   |
| Malaysia     | 3         | 0.53%   |
| Israel       | 3         | 0.53%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 10        | 1.72%   |
| Berlin            | 8         | 1.37%   |
| Sao Paulo         | 7         | 1.2%    |
| Oslo              | 7         | 1.2%    |
| Barcelona         | 6         | 1.03%   |
| St Petersburg     | 5         | 0.86%   |
| Atlanta           | 5         | 0.86%   |
| Santiago          | 4         | 0.69%   |
| Nairobi           | 4         | 0.69%   |
| Milan             | 4         | 0.69%   |
| Melbourne         | 4         | 0.69%   |
| Denver            | 4         | 0.69%   |
| Zurich            | 3         | 0.52%   |
| Warsaw            | 3         | 0.52%   |
| Toronto           | 3         | 0.52%   |
| Sofia             | 3         | 0.52%   |
| Rio de Janeiro    | 3         | 0.52%   |
| Prague            | 3         | 0.52%   |
| Paris             | 3         | 0.52%   |
| Oshawa            | 3         | 0.52%   |
| Munich            | 3         | 0.52%   |
| Mumbai            | 3         | 0.52%   |
| Montreal          | 3         | 0.52%   |
| Milano            | 3         | 0.52%   |
| Madrid            | 3         | 0.52%   |
| Helsinki          | 3         | 0.52%   |
| Frankfurt am Main | 3         | 0.52%   |
| Doha              | 3         | 0.52%   |
| Cologne           | 3         | 0.52%   |
| Brussels          | 3         | 0.52%   |
| Antalya           | 3         | 0.52%   |
| Adelaide          | 3         | 0.52%   |
| Valencia          | 2         | 0.34%   |
| Ulyanovsk         | 2         | 0.34%   |
| Turin             | 2         | 0.34%   |
| Tokyo             | 2         | 0.34%   |
| Tel Aviv          | 2         | 0.34%   |
| Stockholm         | 2         | 0.34%   |
| Sarajevo          | 2         | 0.34%   |
| Santo André      | 2         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 122       | 140    | 17.63%  |
| WDC                            | 55        | 62     | 7.95%   |
| SanDisk                        | 52        | 58     | 7.51%   |
| SK hynix                       | 44        | 48     | 6.36%   |
| Seagate                        | 44        | 50     | 6.36%   |
| Kingston                       | 40        | 45     | 5.78%   |
| Micron Technology              | 36        | 40     | 5.2%    |
| Unknown                        | 29        | 32     | 4.19%   |
| Toshiba                        | 29        | 31     | 4.19%   |
| Intel                          | 27        | 31     | 3.9%    |
| KIOXIA                         | 21        | 21     | 3.03%   |
| Crucial                        | 21        | 23     | 3.03%   |
| Apple                          | 14        | 17     | 2.02%   |
| Phison Electronics             | 13        | 16     | 1.88%   |
| China                          | 12        | 12     | 1.73%   |
| HGST                           | 9         | 11     | 1.3%    |
| Hitachi                        | 8         | 8      | 1.16%   |
| Kingston Technology Company    | 7         | 7      | 1.01%   |
| Phison                         | 6         | 6      | 0.87%   |
| Unknown                        | 6         | 7      | 0.87%   |
| Silicon Motion                 | 5         | 5      | 0.72%   |
| LITEONIT                       | 5         | 6      | 0.72%   |
| Intenso                        | 4         | 6      | 0.58%   |
| ADATA Technology               | 4         | 4      | 0.58%   |
| A-DATA Technology              | 4         | 4      | 0.58%   |
| Union Memory (Shenzhen)        | 3         | 3      | 0.43%   |
| Team                           | 3         | 3      | 0.43%   |
| Netac                          | 3         | 3      | 0.43%   |
| LITEON                         | 3         | 6      | 0.43%   |
| Lexar                          | 3         | 3      | 0.43%   |
| GOODRAM                        | 3         | 3      | 0.43%   |
| YMTC                           | 2         | 2      | 0.29%   |
| Union Memory                   | 2         | 2      | 0.29%   |
| Transcend                      | 2         | 2      | 0.29%   |
| SSSTC                          | 2         | 2      | 0.29%   |
| SPCC                           | 2         | 2      | 0.29%   |
| Solid State Storage Technology | 2         | 2      | 0.29%   |
| Realtek Semiconductor          | 2         | 2      | 0.29%   |
| PNY                            | 2         | 2      | 0.29%   |
| Patriot                        | 2         | 2      | 0.29%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 17        | 2.4%    |
| Kingston SA400S37240G 240GB SSD                       | 11        | 1.56%   |
| Seagate ST1000LM035-1RK172 1TB                        | 10        | 1.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 10        | 1.41%   |
| Unknown MMC Card  64GB                                | 7         | 0.99%   |
| SanDisk NVMe SSD Drive 512GB                          | 7         | 0.99%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                         | 6         | 0.85%   |
| Kingston SA400S37480G 480GB SSD                       | 6         | 0.85%   |
| Unknown                                               | 6         | 0.85%   |
| Unknown MMC Card  32GB                                | 5         | 0.71%   |
| Toshiba MQ01ABF050 500GB                              | 5         | 0.71%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 5         | 0.71%   |
| Sandisk WD Blue SN550 NVMe SSD 250GB                  | 5         | 0.71%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 5         | 0.71%   |
| Phison E12 NVMe Controller 2TB                        | 5         | 0.71%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB               | 5         | 0.71%   |
| Intel SSDPEKNU512GZ 512GB                             | 5         | 0.71%   |
| HGST HTS721010A9E630 1TB                              | 5         | 0.71%   |
| Unknown MMC Card  128GB                               | 4         | 0.57%   |
| Toshiba XG6 NVMe SSD Controller 512GB                 | 4         | 0.57%   |
| Seagate ST1000LM049-2GH172 1TB                        | 4         | 0.57%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 4         | 0.57%   |
| Samsung SSD 870 EVO 500GB                             | 4         | 0.57%   |
| Samsung SSD 850 EVO 250GB                             | 4         | 0.57%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB   | 4         | 0.57%   |
| KIOXIA KBG40ZNV512G 512GB                             | 4         | 0.57%   |
| Crucial CT500MX500SSD1 500GB                          | 4         | 0.57%   |
| WDC PC SN730 SDBPNTY-512G-1101 512GB                  | 3         | 0.42%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB                  | 3         | 0.42%   |
| Unknown SD/MMC/MS PRO 128GB                           | 3         | 0.42%   |
| Unknown MMC Card  16GB                                | 3         | 0.42%   |
| Toshiba MQ04ABF100 1TB                                | 3         | 0.42%   |
| SK hynix HFS256G39TND-N210A 256GB SSD                 | 3         | 0.42%   |
| SK hynix HFM512GD3JX013N 512GB                        | 3         | 0.42%   |
| SK hynix BC511 512GB                                  | 3         | 0.42%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 500GB | 3         | 0.42%   |
| Seagate ST500LT012-1DG142 500GB                       | 3         | 0.42%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD                   | 3         | 0.42%   |
| SanDisk NVMe SSD Drive 1TB                            | 3         | 0.42%   |
| Samsung SSD 870 EVO 1TB                               | 3         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 48     | 36.84%  |
| WDC                 | 26        | 29     | 22.81%  |
| Toshiba             | 18        | 20     | 15.79%  |
| HGST                | 9         | 11     | 7.89%   |
| Hitachi             | 8         | 8      | 7.02%   |
| Unknown             | 3         | 3      | 2.63%   |
| Samsung Electronics | 3         | 3      | 2.63%   |
| HGST HTS            | 2         | 2      | 1.75%   |
| JMicron Technology  | 1         | 1      | 0.88%   |
| Fujitsu             | 1         | 1      | 0.88%   |
| Apple               | 1         | 1      | 0.88%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 44        | 49     | 19.82%  |
| Kingston            | 31        | 36     | 13.96%  |
| Crucial             | 18        | 20     | 8.11%   |
| SanDisk             | 16        | 16     | 7.21%   |
| WDC                 | 13        | 16     | 5.86%   |
| China               | 12        | 12     | 5.41%   |
| SK hynix            | 9         | 9      | 4.05%   |
| Apple               | 8         | 8      | 3.6%    |
| Micron Technology   | 7         | 7      | 3.15%   |
| Intel               | 6         | 7      | 2.7%    |
| LITEONIT            | 5         | 6      | 2.25%   |
| A-DATA Technology   | 4         | 4      | 1.8%    |
| Unknown             | 4         | 4      | 1.8%    |
| Team                | 3         | 3      | 1.35%   |
| Netac               | 3         | 3      | 1.35%   |
| LITEON              | 3         | 6      | 1.35%   |
| Lexar               | 3         | 3      | 1.35%   |
| Intenso             | 3         | 4      | 1.35%   |
| Toshiba             | 2         | 2      | 0.9%    |
| SPCC                | 2         | 2      | 0.9%    |
| PNY                 | 2         | 2      | 0.9%    |
| Patriot             | 2         | 2      | 0.9%    |
| Kingchuxing         | 2         | 2      | 0.9%    |
| GOODRAM             | 2         | 2      | 0.9%    |
| Gigabyte Technology | 2         | 2      | 0.9%    |
| XrayDisk            | 1         | 1      | 0.45%   |
| WDC WDS2            | 1         | 1      | 0.45%   |
| Transcend           | 1         | 1      | 0.45%   |
| Smartbuy            | 1         | 1      | 0.45%   |
| S3+                 | 1         | 1      | 0.45%   |
| Plextor             | 1         | 1      | 0.45%   |
| Pioneer             | 1         | 1      | 0.45%   |
| OWC                 | 1         | 1      | 0.45%   |
| ORTIAL              | 1         | 1      | 0.45%   |
| NT-512              | 1         | 1      | 0.45%   |
| KINGBANK            | 1         | 1      | 0.45%   |
| INTEL SS            | 1         | 2      | 0.45%   |
| GLOWAY              | 1         | 1      | 0.45%   |
| FORESEE             | 1         | 1      | 0.45%   |
| EVM                 | 1         | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 301       | 357    | 45.95%  |
| SSD     | 204       | 244    | 31.15%  |
| HDD     | 114       | 127    | 17.4%   |
| MMC     | 27        | 31     | 4.12%   |
| Unknown | 9         | 11     | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 301       | 356    | 47.25%  |
| SATA | 283       | 353    | 44.43%  |
| MMC  | 27        | 31     | 4.24%   |
| SAS  | 26        | 30     | 4.08%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 215       | 260    | 67.19%  |
| 0.51-1.0   | 90        | 94     | 28.13%  |
| 1.01-2.0   | 10        | 12     | 3.13%   |
| 4.01-10.0  | 3         | 3      | 0.94%   |
| 3.01-4.0   | 2         | 2      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 186       | 31.9%   |
| 101-250        | 177       | 30.36%  |
| 501-1000       | 89        | 15.27%  |
| 1-20           | 32        | 5.49%   |
| 51-100         | 31        | 5.32%   |
| 1001-2000      | 24        | 4.12%   |
| 21-50          | 23        | 3.95%   |
| More than 3000 | 10        | 1.72%   |
| 2001-3000      | 7         | 1.2%    |
| Unknown        | 4         | 0.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 203       | 34.64%  |
| 21-50          | 159       | 27.13%  |
| 101-250        | 77        | 13.14%  |
| 51-100         | 68        | 11.6%   |
| 251-500        | 43        | 7.34%   |
| 501-1000       | 18        | 3.07%   |
| 1001-2000      | 9         | 1.54%   |
| Unknown        | 4         | 0.68%   |
| 2001-3000      | 3         | 0.51%   |
| More than 3000 | 2         | 0.34%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB                 | 1         | 1      | 7.14%   |
| WDC WD Green M.2 2280 240GB SSD          | 1         | 1      | 7.14%   |
| Toshiba MK5065GSXF 500GB                 | 1         | 1      | 7.14%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1      | 7.14%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 1         | 1      | 7.14%   |
| SanDisk SDSSDX120GG25 120GB              | 1         | 1      | 7.14%   |
| LITEONIT LCT-256M3S-41 7mm 256GB FDE SSD | 1         | 1      | 7.14%   |
| Hitachi HTS723225A7A365 OPAL 250GB       | 1         | 1      | 7.14%   |
| Hitachi HTS547564A9E384 640GB            | 1         | 1      | 7.14%   |
| HGST HTS721010A9E630 1TB                 | 1         | 1      | 7.14%   |
| HGST HTS541010A9E680 1TB                 | 1         | 1      | 7.14%   |
| Fujitsu MHW2160BH 160GB                  | 1         | 1      | 7.14%   |
| Crucial CT525MX300SSD4 528GB             | 1         | 1      | 7.14%   |
| Unknown                                  | 1         | 1      | 7.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 2         | 2      | 14.29%  |
| Seagate  | 2         | 2      | 14.29%  |
| Hitachi  | 2         | 2      | 14.29%  |
| HGST     | 2         | 2      | 14.29%  |
| Toshiba  | 1         | 1      | 7.14%   |
| SanDisk  | 1         | 1      | 7.14%   |
| LITEONIT | 1         | 1      | 7.14%   |
| Fujitsu  | 1         | 1      | 7.14%   |
| Crucial  | 1         | 1      | 7.14%   |
| Unknown  | 1         | 1      | 7.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 22.22%  |
| Hitachi | 2         | 2      | 22.22%  |
| HGST    | 2         | 2      | 22.22%  |
| WDC     | 1         | 1      | 11.11%  |
| Toshiba | 1         | 1      | 11.11%  |
| Fujitsu | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 64.29%  |
| SSD  | 5         | 5      | 35.71%  |

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
| Detected | 361       | 514    | 61.92%  |
| Works    | 208       | 242    | 35.68%  |
| Malfunc  | 14        | 14     | 2.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 368       | 50.76%  |
| Samsung Electronics                     | 83        | 11.45%  |
| SanDisk                                 | 52        | 7.17%   |
| AMD                                     | 46        | 6.34%   |
| SK hynix                                | 35        | 4.83%   |
| Micron Technology                       | 29        | 4%      |
| Phison Electronics                      | 21        | 2.9%    |
| KIOXIA                                  | 19        | 2.62%   |
| Kingston Technology Company             | 14        | 1.93%   |
| Toshiba America Info Systems            | 11        | 1.52%   |
| Union Memory (Shenzhen)                 | 5         | 0.69%   |
| Solid State Storage Technology          | 5         | 0.69%   |
| Silicon Motion                          | 5         | 0.69%   |
| Micron/Crucial Technology               | 5         | 0.69%   |
| ADATA Technology                        | 5         | 0.69%   |
| Apple                                   | 4         | 0.55%   |
| Zhaoxin                                 | 3         | 0.41%   |
| Yangtze Memory Technologies             | 2         | 0.28%   |
| Shenzhen Longsys Electronics            | 2         | 0.28%   |
| Realtek Semiconductor                   | 2         | 0.28%   |
| Nvidia                                  | 2         | 0.28%   |
| Transcend                               | 1         | 0.14%   |
| Solidigm                                | 1         | 0.14%   |
| Shenzhen Unionmemory Information System | 1         | 0.14%   |
| MAXIO Technology (Hangzhou)             | 1         | 0.14%   |
| Marvell Technology Group                | 1         | 0.14%   |
| Lenovo                                  | 1         | 0.14%   |
| ASMedia Technology                      | 1         | 0.14%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                            | 54        | 7.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 44        | 5.76%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 44        | 5.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 36        | 4.71%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 29        | 3.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 27        | 3.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 27        | 3.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 22        | 2.88%   |
| Samsung NVMe SSD Controller 980                                                | 19        | 2.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 18        | 2.36%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 18        | 2.36%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 16        | 2.09%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 14        | 1.83%   |
| Intel Tiger Lake-LP SATA Controller                                            | 13        | 1.7%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 11        | 1.44%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 11        | 1.44%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 11        | 1.44%   |
| Intel Comet Lake SATA AHCI Controller                                          | 11        | 1.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 11        | 1.44%   |
| Phison PS5013 E13 NVMe Controller                                              | 10        | 1.31%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 10        | 1.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 10        | 1.31%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 1.18%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 1.18%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 8         | 1.05%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 7         | 0.92%   |
| KIOXIA NVMe SSD Controller BG5 (DRAM-less)                                     | 7         | 0.92%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 7         | 0.92%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 7         | 0.92%   |
| SK hynix BC511 NVMe SSD                                                        | 6         | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 6         | 0.79%   |
| Phison E12 NVMe Controller                                                     | 6         | 0.79%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 6         | 0.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 0.79%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 0.79%   |
| SK hynix PC601 NVMe Solid State Drive                                          | 5         | 0.65%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 5         | 0.65%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 5         | 0.65%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 5         | 0.65%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 5         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 334       | 45.44%  |
| NVMe | 299       | 40.68%  |
| RAID | 92        | 12.52%  |
| IDE  | 10        | 1.36%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 455       | 79.96%  |
| AMD          | 111       | 19.51%  |
| CentaurHauls | 3         | 0.53%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-6300U CPU @ 2.40GHz       | 10        | 1.76%   |
| Intel 12th Gen Core i7-12700H           | 10        | 1.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 10        | 1.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 10        | 1.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 9         | 1.58%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 9         | 1.58%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 9         | 1.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 8         | 1.41%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 7         | 1.23%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 7         | 1.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 7         | 1.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 7         | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 7         | 1.23%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 7         | 1.23%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz | 7         | 1.23%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 7         | 1.23%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 6         | 1.05%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 6         | 1.05%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 6         | 1.05%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 6         | 1.05%   |
| Intel 12th Gen Core i7-1260P            | 6         | 1.05%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 5         | 0.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 5         | 0.88%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 5         | 0.88%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 5         | 0.88%   |
| Intel Core i5-4210U CPU @ 1.70GHz       | 5         | 0.88%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 5         | 0.88%   |
| Intel 12th Gen Core i5-1240P            | 5         | 0.88%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 5         | 0.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 5         | 0.88%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 5         | 0.88%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 5         | 0.88%   |
| Intel Core i7-4600U CPU @ 2.10GHz       | 4         | 0.7%    |
| Intel Core i7-2630QM CPU @ 2.00GHz      | 4         | 0.7%    |
| Intel Core i5-8365U CPU @ 1.60GHz       | 4         | 0.7%    |
| Intel Core i5-3230M CPU @ 2.60GHz       | 4         | 0.7%    |
| Intel Core i5-2520M CPU @ 2.50GHz       | 4         | 0.7%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz      | 4         | 0.7%    |
| Intel Core i3-5005U CPU @ 2.00GHz       | 4         | 0.7%    |
| Intel Core i3-3110M CPU @ 2.40GHz       | 4         | 0.7%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 139       | 24.43%  |
| Other                   | 117       | 20.56%  |
| Intel Core i7           | 104       | 18.28%  |
| AMD Ryzen 7             | 44        | 7.73%   |
| Intel Core i3           | 40        | 7.03%   |
| AMD Ryzen 5             | 26        | 4.57%   |
| Intel Celeron           | 23        | 4.04%   |
| Intel Core 2 Duo        | 15        | 2.64%   |
| Intel Pentium           | 8         | 1.41%   |
| AMD Ryzen 9             | 8         | 1.41%   |
| AMD Ryzen 5 PRO         | 6         | 1.05%   |
| AMD Ryzen 7 PRO         | 5         | 0.88%   |
| AMD Ryzen 3             | 4         | 0.7%    |
| AMD E2                  | 4         | 0.7%    |
| AMD A4                  | 4         | 0.7%    |
| Intel Pentium Silver    | 3         | 0.53%   |
| Intel Core i9           | 3         | 0.53%   |
| AMD A8                  | 3         | 0.53%   |
| Intel Pentium Dual      | 2         | 0.35%   |
| Intel Core M            | 2         | 0.35%   |
| AMD A10                 | 2         | 0.35%   |
| Intel Xeon              | 1         | 0.18%   |
| Intel Pentium Dual-Core | 1         | 0.18%   |
| Intel Core m7           | 1         | 0.18%   |
| Intel Core m3           | 1         | 0.18%   |
| AMD Athlon II           | 1         | 0.18%   |
| AMD Athlon              | 1         | 0.18%   |
| AMD A6                  | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 234       | 41.05%  |
| 4      | 164       | 28.77%  |
| 8      | 67        | 11.75%  |
| 6      | 49        | 8.6%    |
| 14     | 23        | 4.04%   |
| 12     | 14        | 2.46%   |
| 10     | 12        | 2.11%   |
| 16     | 3         | 0.53%   |
| 1      | 2         | 0.35%   |
| 24     | 1         | 0.18%   |
| 5      | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 569       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 470       | 82.6%   |
| 1      | 99        | 17.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 569       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 497       | 87.04%  |
| 0x08608103 | 9         | 1.58%   |
| 0x0a50000c | 8         | 1.4%    |
| 0x0a404102 | 7         | 1.23%   |
| 0x0a50000d | 6         | 1.05%   |
| 0x08600106 | 6         | 1.05%   |
| 0x0a404101 | 5         | 0.88%   |
| 0x906a3    | 3         | 0.53%   |
| 0x806ec    | 3         | 0.53%   |
| 0x306a9    | 2         | 0.35%   |
| 0x0a704101 | 2         | 0.35%   |
| 0x08a00006 | 2         | 0.35%   |
| 0x08608104 | 2         | 0.35%   |
| 0x08608102 | 2         | 0.35%   |
| 0x08600109 | 2         | 0.35%   |
| 0x08101016 | 2         | 0.35%   |
| 0x906ea    | 1         | 0.18%   |
| 0x806c1    | 1         | 0.18%   |
| 0x506e3    | 1         | 0.18%   |
| 0x406e3    | 1         | 0.18%   |
| 0x306d4    | 1         | 0.18%   |
| 0x0a601203 | 1         | 0.18%   |
| 0x08600103 | 1         | 0.18%   |
| 0x08108109 | 1         | 0.18%   |
| 0x08108102 | 1         | 0.18%   |
| 0x0810100b | 1         | 0.18%   |
| 0x07030105 | 1         | 0.18%   |
| 0x06006704 | 1         | 0.18%   |
| 0x06006113 | 1         | 0.18%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 107       | 18.77%  |
| Unknown          | 72        | 12.63%  |
| TigerLake        | 48        | 8.42%   |
| Alderlake Hybrid | 39        | 6.84%   |
| Skylake          | 36        | 6.32%   |
| IvyBridge        | 36        | 6.32%   |
| SandyBridge      | 32        | 5.61%   |
| Haswell          | 27        | 4.74%   |
| Zen 3            | 25        | 4.39%   |
| Broadwell        | 24        | 4.21%   |
| Zen 2            | 18        | 3.16%   |
| Westmere         | 15        | 2.63%   |
| Goldmont plus    | 15        | 2.63%   |
| Penryn           | 13        | 2.28%   |
| CometLake        | 12        | 2.11%   |
| Zen+             | 7         | 1.23%   |
| Silvermont       | 7         | 1.23%   |
| IceLake          | 7         | 1.23%   |
| Excavator        | 7         | 1.23%   |
| Core             | 5         | 0.88%   |
| Goldmont         | 4         | 0.7%    |
| Zen              | 3         | 0.53%   |
| Puma             | 3         | 0.53%   |
| Piledriver       | 2         | 0.35%   |
| Steamroller      | 1         | 0.18%   |
| Nehalem          | 1         | 0.18%   |
| K10 Llano        | 1         | 0.18%   |
| K10              | 1         | 0.18%   |
| Jaguar           | 1         | 0.18%   |
| Bobcat           | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 432       | 58.62%  |
| Nvidia  | 159       | 21.57%  |
| AMD     | 143       | 19.4%   |
| Zhaoxin | 3         | 0.41%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 36        | 4.85%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 34        | 4.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 30        | 4.04%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 28        | 3.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 24        | 3.23%   |
| Intel HD Graphics 620                                                                 | 21        | 2.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 19        | 2.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 19        | 2.56%   |
| AMD Lucienne                                                                          | 19        | 2.56%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 18        | 2.42%   |
| Intel HD Graphics 5500                                                                | 18        | 2.42%   |
| AMD Renoir                                                                            | 18        | 2.42%   |
| AMD Rembrandt [Radeon 680M]                                                           | 17        | 2.29%   |
| Intel UHD Graphics 620                                                                | 16        | 2.15%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 16        | 2.15%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 15        | 2.02%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 14        | 1.88%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                | 12        | 1.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 12        | 1.62%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 11        | 1.48%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 11        | 1.48%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 10        | 1.35%   |
| Intel Core Processor Integrated Graphics Controller                                   | 10        | 1.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 10        | 1.35%   |
| AMD Barcelo                                                                           | 10        | 1.35%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 9         | 1.21%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 8         | 1.08%   |
| Intel HD Graphics 630                                                                 | 8         | 1.08%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 7         | 0.94%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 6         | 0.81%   |
| Intel HD Graphics 530                                                                 | 6         | 0.81%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 6         | 0.81%   |
| Nvidia GP108M [GeForce MX150]                                                         | 5         | 0.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 5         | 0.67%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                 | 5         | 0.67%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 5         | 0.67%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 5         | 0.67%   |
| Nvidia TU117M                                                                         | 4         | 0.54%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 4         | 0.54%   |
| Nvidia GM107GLM [Quadro M1000M]                                                       | 4         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 280       | 49.12%  |
| Intel + Nvidia | 125       | 21.93%  |
| 1 x AMD        | 99        | 17.37%  |
| Intel + AMD    | 23        | 4.04%   |
| AMD + Nvidia   | 20        | 3.51%   |
| 1 x Nvidia     | 14        | 2.46%   |
| 1 x Zhaoxin    | 3         | 0.53%   |
| Other          | 2         | 0.35%   |
| 2 x Intel      | 2         | 0.35%   |
| 2 x AMD        | 2         | 0.35%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 457       | 80.32%  |
| Proprietary | 95        | 16.7%   |
| Unknown     | 17        | 2.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 479       | 83.6%   |
| 0.01-0.5   | 42        | 7.33%   |
| 1.01-2.0   | 27        | 4.71%   |
| 0.51-1.0   | 11        | 1.92%   |
| 3.01-4.0   | 9         | 1.57%   |
| 5.01-6.0   | 3         | 0.52%   |
| 7.01-8.0   | 1         | 0.17%   |
| 8.01-16.0  | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 135       | 20.09%  |
| BOE                     | 102       | 15.18%  |
| Chimei Innolux          | 88        | 13.1%   |
| LG Display              | 72        | 10.71%  |
| Samsung Electronics     | 66        | 9.82%   |
| Sharp                   | 22        | 3.27%   |
| Goldstar                | 20        | 2.98%   |
| Apple                   | 20        | 2.98%   |
| Dell                    | 15        | 2.23%   |
| PANDA                   | 14        | 2.08%   |
| CSO                     | 14        | 2.08%   |
| Hewlett-Packard         | 12        | 1.79%   |
| InfoVision              | 8         | 1.19%   |
| Lenovo                  | 7         | 1.04%   |
| Sony                    | 6         | 0.89%   |
| BenQ                    | 6         | 0.89%   |
| Ancor Communications    | 6         | 0.89%   |
| Acer                    | 6         | 0.89%   |
| Chi Mei Optoelectronics | 5         | 0.74%   |
| Philips                 | 4         | 0.6%    |
| AOC                     | 4         | 0.6%    |
| ViewSonic               | 3         | 0.45%   |
| Iiyama                  | 3         | 0.45%   |
| Denver                  | 3         | 0.45%   |
| ASUSTek Computer        | 3         | 0.45%   |
| Unknown                 | 2         | 0.3%    |
| Panasonic               | 2         | 0.3%    |
| MSI                     | 2         | 0.3%    |
| LG Philips              | 2         | 0.3%    |
| WST                     | 1         | 0.15%   |
| Wacom                   | 1         | 0.15%   |
| Vestel Elektronik       | 1         | 0.15%   |
| Unknown (XXX)           | 1         | 0.15%   |
| Tianma XM               | 1         | 0.15%   |
| Seiki                   | 1         | 0.15%   |
| Sceptre Tech            | 1         | 0.15%   |
| ONN                     | 1         | 0.15%   |
| NEC Computers           | 1         | 0.15%   |
| MStar                   | 1         | 0.15%   |
| Mi                      | 1         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 11        | 1.63%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 7         | 1.04%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 6         | 0.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 6         | 0.89%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch        | 6         | 0.89%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 4         | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.59%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.59%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch       | 4         | 0.59%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                 | 4         | 0.59%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 4         | 0.59%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.59%   |
| AU Optronics LCD Monitor AUO5799 1920x1080 344x194mm 15.5-inch        | 4         | 0.59%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 4         | 0.59%   |
| Samsung Electronics LCD Monitor SDC4172 2880x1800 289x186mm 13.5-inch | 3         | 0.44%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.44%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch           | 3         | 0.44%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                 | 3         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 3         | 0.44%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 3         | 0.44%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                 | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO333D 1920x1080 309x174mm 14.0-inch        | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.44%   |
| AU Optronics LCD Monitor AUO0BA2 2560x1440 309x174mm 14.0-inch        | 3         | 0.44%   |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 3         | 0.44%   |
| Sony TV SNY4502 1920x1080                                             | 2         | 0.3%    |
| Sony LCD SNY06FA 1600x900 291x164mm 13.2-inch                         | 2         | 0.3%    |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch               | 2         | 0.3%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 2         | 0.3%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.3%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4852 1920x1080 344x194mm 15.5-inch | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 2         | 0.3%    |
| Samsung Electronics LCD Monitor SDC416B 3840x2400 344x215mm 16.0-inch | 2         | 0.3%    |
| PANDA LCD Monitor NCP004F 1920x1080 309x174mm 14.0-inch               | 2         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 287       | 45.85%  |
| 1366x768 (WXGA)    | 140       | 22.36%  |
| 3840x2160 (4K)     | 28        | 4.47%   |
| 2560x1440 (QHD)    | 24        | 3.83%   |
| 1600x900 (HD+)     | 22        | 3.51%   |
| 2880x1800          | 20        | 3.19%   |
| 2560x1600          | 17        | 2.72%   |
| 1920x1200 (WUXGA)  | 17        | 2.72%   |
| 1280x800 (WXGA)    | 14        | 2.24%   |
| 3440x1440          | 10        | 1.6%    |
| 1440x900 (WXGA+)   | 8         | 1.28%   |
| 3840x2400          | 7         | 1.12%   |
| 1280x1024 (SXGA)   | 5         | 0.8%    |
| 2560x1080          | 3         | 0.48%   |
| 2240x1400          | 3         | 0.48%   |
| 2160x1440          | 3         | 0.48%   |
| 1680x1050 (WSXGA+) | 3         | 0.48%   |
| 3456x2160          | 2         | 0.32%   |
| 3200x1800 (QHD+)   | 2         | 0.32%   |
| 2520x1680          | 2         | 0.32%   |
| 2256x1504          | 2         | 0.32%   |
| 3840x1600          | 1         | 0.16%   |
| 3072x1920          | 1         | 0.16%   |
| 3000x2000          | 1         | 0.16%   |
| 2880x1620          | 1         | 0.16%   |
| 2304x1440          | 1         | 0.16%   |
| 1920x540           | 1         | 0.16%   |
| 1920x1280          | 1         | 0.16%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 247       | 36.76%  |
| 13      | 108       | 16.07%  |
| 14      | 99        | 14.73%  |
| 17      | 46        | 6.85%   |
| 27      | 26        | 3.87%   |
| 16      | 20        | 2.98%   |
| 23      | 16        | 2.38%   |
| 12      | 16        | 2.38%   |
| 24      | 13        | 1.93%   |
| 21      | 13        | 1.93%   |
| 11      | 11        | 1.64%   |
| 34      | 10        | 1.49%   |
| 72      | 5         | 0.74%   |
| Unknown | 5         | 0.74%   |
| 31      | 4         | 0.6%    |
| 22      | 4         | 0.6%    |
| 20      | 4         | 0.6%    |
| 35      | 3         | 0.45%   |
| 25      | 3         | 0.45%   |
| 84      | 2         | 0.3%    |
| 54      | 2         | 0.3%    |
| 40      | 2         | 0.3%    |
| 19      | 2         | 0.3%    |
| 18      | 2         | 0.3%    |
| 58      | 1         | 0.15%   |
| 52      | 1         | 0.15%   |
| 49      | 1         | 0.15%   |
| 42      | 1         | 0.15%   |
| 37      | 1         | 0.15%   |
| 32      | 1         | 0.15%   |
| 28      | 1         | 0.15%   |
| 26      | 1         | 0.15%   |
| 8       | 1         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 399       | 60%     |
| 201-300     | 91        | 13.68%  |
| 501-600     | 56        | 8.42%   |
| 351-400     | 55        | 8.27%   |
| 401-500     | 22        | 3.31%   |
| 701-800     | 11        | 1.65%   |
| 1501-2000   | 7         | 1.05%   |
| 801-900     | 6         | 0.9%    |
| 601-700     | 6         | 0.9%    |
| 1001-1500   | 5         | 0.75%   |
| Unknown     | 5         | 0.75%   |
| 101-200     | 1         | 0.15%   |
| 901-1000    | 1         | 0.15%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 456       | 78.49%  |
| 16/10   | 92        | 15.83%  |
| 21/9    | 14        | 2.41%   |
| 3/2     | 9         | 1.55%   |
| 5/4     | 5         | 0.86%   |
| Unknown | 2         | 0.34%   |
| 6/5     | 1         | 0.17%   |
| 32/9    | 1         | 0.17%   |
| 0.62    | 1         | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 247       | 36.76%  |
| 81-90          | 165       | 24.55%  |
| 71-80          | 40        | 5.95%   |
| 201-250        | 40        | 5.95%   |
| 121-130        | 40        | 5.95%   |
| 301-350        | 27        | 4.02%   |
| 351-500        | 19        | 2.83%   |
| 111-120        | 19        | 2.83%   |
| 61-70          | 15        | 2.23%   |
| More than 1000 | 12        | 1.79%   |
| 51-60          | 11        | 1.64%   |
| 151-200        | 9         | 1.34%   |
| 251-300        | 7         | 1.04%   |
| Unknown        | 5         | 0.74%   |
| 141-150        | 4         | 0.6%    |
| 131-140        | 4         | 0.6%    |
| 501-1000       | 4         | 0.6%    |
| 91-100         | 3         | 0.45%   |
| 1-40           | 1         | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 281       | 42.9%   |
| 101-120       | 163       | 24.89%  |
| 161-240       | 82        | 12.52%  |
| 51-100        | 80        | 12.21%  |
| More than 240 | 36        | 5.5%    |
| 1-50          | 8         | 1.22%   |
| Unknown       | 5         | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 442       | 77.14%  |
| 2     | 98        | 17.1%   |
| 0     | 19        | 3.32%   |
| 3     | 13        | 2.27%   |
| 4     | 1         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 322       | 37.14%  |
| Realtek Semiconductor             | 281       | 32.41%  |
| Qualcomm Atheros                  | 81        | 9.34%   |
| Broadcom                          | 42        | 4.84%   |
| MediaTek                          | 34        | 3.92%   |
| Broadcom Limited                  | 13        | 1.5%    |
| TP-Link                           | 11        | 1.27%   |
| ASIX Electronics                  | 9         | 1.04%   |
| DisplayLink                       | 8         | 0.92%   |
| Lenovo                            | 7         | 0.81%   |
| Xiaomi                            | 5         | 0.58%   |
| Sierra Wireless                   | 5         | 0.58%   |
| Ralink                            | 5         | 0.58%   |
| Marvell Technology Group          | 5         | 0.58%   |
| Dell                              | 4         | 0.46%   |
| Ralink Technology                 | 3         | 0.35%   |
| JMicron Technology                | 3         | 0.35%   |
| Hewlett-Packard                   | 3         | 0.35%   |
| Qualcomm                          | 2         | 0.23%   |
| Nvidia                            | 2         | 0.23%   |
| Huawei Technologies               | 2         | 0.23%   |
| Google                            | 2         | 0.23%   |
| Ericsson Business Mobile Networks | 2         | 0.23%   |
| Vimtron Electronics               | 1         | 0.12%   |
| U-Blox                            | 1         | 0.12%   |
| TRENDnet                          | 1         | 0.12%   |
| Tenda                             | 1         | 0.12%   |
| Samsung Electronics               | 1         | 0.12%   |
| Quectel Wireless Solutions        | 1         | 0.12%   |
| OPPO Electronics                  | 1         | 0.12%   |
| Motorola PCS                      | 1         | 0.12%   |
| MosChip Semiconductor             | 1         | 0.12%   |
| ICS Advent                        | 1         | 0.12%   |
| Flipper Devices                   | 1         | 0.12%   |
| Edimax Technology                 | 1         | 0.12%   |
| D-Link System                     | 1         | 0.12%   |
| D-Link                            | 1         | 0.12%   |
| ASUSTek Computer                  | 1         | 0.12%   |
| Apple                             | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 145       | 14.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37        | 3.6%    |
| Intel Wi-Fi 6 AX201                                               | 37        | 3.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 34        | 3.31%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 2.53%   |
| Intel Wireless 8265 / 8275                                        | 26        | 2.53%   |
| Intel Wi-Fi 6 AX200                                               | 26        | 2.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 25        | 2.43%   |
| Intel Wireless 8260                                               | 24        | 2.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 18        | 1.75%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 17        | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 17        | 1.66%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 1.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 15        | 1.46%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 15        | 1.46%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 1.46%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 14        | 1.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 14        | 1.36%   |
| Intel Wireless 7265                                               | 14        | 1.36%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 1.36%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 12        | 1.17%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 12        | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 11        | 1.07%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 11        | 1.07%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 10        | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 10        | 0.97%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 9         | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 8         | 0.78%   |
| Intel Wireless 7260                                               | 7         | 0.68%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 7         | 0.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 0.58%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 5         | 0.49%   |
| Intel Wireless 3165                                               | 5         | 0.49%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.49%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 313       | 52.87%  |
| Realtek Semiconductor      | 97        | 16.39%  |
| Qualcomm Atheros           | 73        | 12.33%  |
| Broadcom                   | 35        | 5.91%   |
| MediaTek                   | 32        | 5.41%   |
| TP-Link                    | 10        | 1.69%   |
| Broadcom Limited           | 9         | 1.52%   |
| Sierra Wireless            | 5         | 0.84%   |
| Ralink                     | 5         | 0.84%   |
| Ralink Technology          | 3         | 0.51%   |
| Qualcomm                   | 2         | 0.34%   |
| Dell                       | 2         | 0.34%   |
| TRENDnet                   | 1         | 0.17%   |
| Quectel Wireless Solutions | 1         | 0.17%   |
| Edimax Technology          | 1         | 0.17%   |
| D-Link System              | 1         | 0.17%   |
| D-Link                     | 1         | 0.17%   |
| ASUSTek Computer           | 1         | 0.17%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 37        | 6.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 34        | 5.7%    |
| Intel Wireless 8265 / 8275                                     | 26        | 4.36%   |
| Intel Wi-Fi 6 AX200                                            | 26        | 4.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 25        | 4.19%   |
| Intel Wireless 8260                                            | 24        | 4.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 18        | 3.02%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 17        | 2.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 17        | 2.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 15        | 2.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 15        | 2.51%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 14        | 2.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 14        | 2.35%   |
| Intel Wireless 7265                                            | 14        | 2.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 2.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 2.01%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 12        | 2.01%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 11        | 1.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 11        | 1.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 1.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 10        | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 9         | 1.51%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 1.34%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8         | 1.34%   |
| Intel Wireless 7260                                            | 7         | 1.17%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 7         | 1.17%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 1.01%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 5         | 0.84%   |
| Intel Wireless 3165                                            | 5         | 0.84%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 0.84%   |
| Intel Centrino Wireless-N 2230                                 | 5         | 0.84%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 0.84%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 5         | 0.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 0.84%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 0.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.67%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.67%   |
| Intel Wireless-AC 9260                                         | 4         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 227       | 54.31%  |
| Intel                    | 102       | 24.4%   |
| Qualcomm Atheros         | 16        | 3.83%   |
| Broadcom                 | 13        | 3.11%   |
| ASIX Electronics         | 9         | 2.15%   |
| DisplayLink              | 8         | 1.91%   |
| Lenovo                   | 7         | 1.67%   |
| Xiaomi                   | 5         | 1.2%    |
| Marvell Technology Group | 5         | 1.2%    |
| Broadcom Limited         | 5         | 1.2%    |
| JMicron Technology       | 3         | 0.72%   |
| TP-Link                  | 2         | 0.48%   |
| Nvidia                   | 2         | 0.48%   |
| MediaTek                 | 2         | 0.48%   |
| Google                   | 2         | 0.48%   |
| Vimtron Electronics      | 1         | 0.24%   |
| Tenda                    | 1         | 0.24%   |
| Samsung Electronics      | 1         | 0.24%   |
| OPPO Electronics         | 1         | 0.24%   |
| Motorola PCS             | 1         | 0.24%   |
| MosChip Semiconductor    | 1         | 0.24%   |
| ICS Advent               | 1         | 0.24%   |
| Huawei Technologies      | 1         | 0.24%   |
| Hewlett-Packard          | 1         | 0.24%   |
| Apple                    | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 145       | 34.44%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37        | 8.79%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 26        | 6.18%   |
| Intel Ethernet Connection (4) I219-LM                             | 16        | 3.8%    |
| Intel Ethernet Connection I219-LM                                 | 15        | 3.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 3.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 10        | 2.38%   |
| ASIX AX88179 Gigabit Ethernet                                     | 9         | 2.14%   |
| Intel Ethernet Connection (6) I219-V                              | 5         | 1.19%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.19%   |
| Intel 82567LM Gigabit Network Connection                          | 5         | 1.19%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 1.19%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 4         | 0.95%   |
| Realtek Killer E3000 2.5GbE Controller                            | 4         | 0.95%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.95%   |
| Intel Ethernet Connection I218-LM                                 | 4         | 0.95%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.95%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.71%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.71%   |
| Lenovo USB-C Dock Ethernet                                        | 3         | 0.71%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.71%   |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.71%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 3         | 0.71%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.71%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.48%   |
| Realtek PCIe GbE Family Controller                                | 2         | 0.48%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 2         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.48%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.48%   |
| MediaTek Titan pocket                                             | 2         | 0.48%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 0.48%   |
| Intel Ethernet Controller I219-LM                                 | 2         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.48%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 0.48%   |
| Intel Ethernet Connection (13) I219-LM                            | 2         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 562       | 58.73%  |
| Ethernet | 386       | 40.33%  |
| Modem    | 8         | 0.84%   |
| Unknown  | 1         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 476       | 80.68%  |
| Ethernet | 114       | 19.32%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 332       | 58.25%  |
| 1     | 230       | 40.35%  |
| 3     | 5         | 0.88%   |
| 0     | 3         | 0.53%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 395       | 68.94%  |
| Yes  | 178       | 31.06%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 270       | 54%     |
| Realtek Semiconductor           | 54        | 10.8%   |
| Qualcomm Atheros Communications | 36        | 7.2%    |
| Foxconn / Hon Hai               | 26        | 5.2%    |
| IMC Networks                    | 23        | 4.6%    |
| Broadcom                        | 17        | 3.4%    |
| Lite-On Technology              | 16        | 3.2%    |
| Apple                           | 16        | 3.2%    |
| Realtek                         | 12        | 2.4%    |
| Cambridge Silicon Radio         | 6         | 1.2%    |
| Dell                            | 4         | 0.8%    |
| Ralink                          | 3         | 0.6%    |
| Hewlett-Packard                 | 3         | 0.6%    |
| ASUSTek Computer                | 3         | 0.6%    |
| Toshiba                         | 2         | 0.4%    |
| Opticis                         | 2         | 0.4%    |
| USI                             | 1         | 0.2%    |
| TP-Link                         | 1         | 0.2%    |
| Ralink Technology               | 1         | 0.2%    |
| Fujitsu                         | 1         | 0.2%    |
| Edimax Technology               | 1         | 0.2%    |
| Chicony Electronics             | 1         | 0.2%    |
| Actions                         | 1         | 0.2%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 74        | 14.8%   |
| Intel AX201 Bluetooth                                                               | 74        | 14.8%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 42        | 8.4%    |
| Realtek Bluetooth Radio                                                             | 41        | 8.2%    |
| Intel Bluetooth Device                                                              | 34        | 6.8%    |
| Intel AX200 Bluetooth                                                               | 24        | 4.8%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 16        | 3.2%    |
| IMC Networks Wireless_Device                                                        | 13        | 2.6%    |
| Foxconn / Hon Hai Wireless_Device                                                   | 12        | 2.4%    |
| Realtek 802.11ac WLAN Adapter                                                       | 11        | 2.2%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 9         | 1.8%    |
| Apple Bluetooth USB Host Controller                                                 | 9         | 1.8%    |
| IMC Networks Bluetooth Radio                                                        | 8         | 1.6%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 7         | 1.4%    |
| Apple Bluetooth Host Controller                                                     | 7         | 1.4%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 6         | 1.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 1.2%    |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 5         | 1%      |
| Lite-On Bluetooth Device                                                            | 5         | 1%      |
| Intel AX210 Bluetooth                                                               | 5         | 1%      |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 5         | 1%      |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 1%      |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 0.8%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 0.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 0.8%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 4         | 0.8%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 4         | 0.8%    |
| Ralink RT3290 Bluetooth                                                             | 3         | 0.6%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 0.6%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 0.6%    |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.4%    |
| Opticis Bluetooth Radio                                                             | 2         | 0.4%    |
| Lite-On Wireless_Device                                                             | 2         | 0.4%    |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.4%    |
| Broadcom HP Portable Valentine                                                      | 2         | 0.4%    |
| ASUS ASUS USB-BT500                                                                 | 2         | 0.4%    |
| USI Bluetooth Device                                                                | 1         | 0.2%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 452       | 62.34%  |
| AMD                                          | 122       | 16.83%  |
| Nvidia                                       | 93        | 12.83%  |
| Realtek Semiconductor                        | 8         | 1.1%    |
| C-Media Electronics                          | 8         | 1.1%    |
| Lenovo                                       | 7         | 0.97%   |
| GN Netcom                                    | 7         | 0.97%   |
| Zhaoxin                                      | 3         | 0.41%   |
| VIA Technologies                             | 2         | 0.28%   |
| Razer USA                                    | 2         | 0.28%   |
| Plantronics                                  | 2         | 0.28%   |
| Generalplus Technology                       | 2         | 0.28%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.14%   |
| Texas Instruments                            | 1         | 0.14%   |
| Superlux digit                               | 1         | 0.14%   |
| Sennheiser Communications                    | 1         | 0.14%   |
| Scarlett                                     | 1         | 0.14%   |
| Native Instruments                           | 1         | 0.14%   |
| Microsoft                                    | 1         | 0.14%   |
| M-Audio                                      | 1         | 0.14%   |
| Kingston Technology                          | 1         | 0.14%   |
| Jieli Technology                             | 1         | 0.14%   |
| Huawei Technologies                          | 1         | 0.14%   |
| FUXIN                                        | 1         | 0.14%   |
| Focusrite-Novation                           | 1         | 0.14%   |
| DSEA A/S                                     | 1         | 0.14%   |
| Corsair                                      | 1         | 0.14%   |
| BEHRINGER International                      | 1         | 0.14%   |
| Antlion Audio                                | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 85        | 9.73%   |
| Intel Sunrise Point-LP HD Audio                                            | 69        | 7.89%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 58        | 6.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 48        | 5.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 39        | 4.46%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 37        | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 29        | 3.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 24        | 2.75%   |
| Intel Broadwell-U Audio Controller                                         | 24        | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 20        | 2.29%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 20        | 2.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 19        | 2.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 2.17%   |
| Intel 8 Series HD Audio Controller                                         | 19        | 2.17%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 1.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 15        | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 15        | 1.72%   |
| Nvidia GA106 High Definition Audio Controller                              | 14        | 1.6%    |
| Nvidia Audio device                                                        | 14        | 1.6%    |
| Intel Raptor Lake-P/U/H cAVS                                               | 13        | 1.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 12        | 1.37%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 11        | 1.26%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 1.26%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 10        | 1.14%   |
| Intel CM238 HD Audio Controller                                            | 10        | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 9         | 1.03%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 1.03%   |
| AMD FCH Azalia Controller                                                  | 9         | 1.03%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 8         | 0.92%   |
| Realtek Semiconductor USB Audio                                            | 7         | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                              | 7         | 0.8%    |
| Nvidia GA104 High Definition Audio Controller                              | 7         | 0.8%    |
| Nvidia GP107GL High Definition Audio Controller                            | 6         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 6         | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                   | 6         | 0.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 6         | 0.69%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 0.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 5         | 0.57%   |
| AMD High Definition Audio Controller                                       | 5         | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 89        | 26.1%   |
| SK hynix            | 76        | 22.29%  |
| Micron Technology   | 59        | 17.3%   |
| Kingston            | 26        | 7.62%   |
| Crucial             | 17        | 4.99%   |
| Unknown             | 11        | 3.23%   |
| A-DATA Technology   | 8         | 2.35%   |
| Smart               | 7         | 2.05%   |
| Ramaxel Technology  | 7         | 2.05%   |
| Unknown (ABCD)      | 6         | 1.76%   |
| Elpida              | 5         | 1.47%   |
| Transcend           | 3         | 0.88%   |
| Timetec             | 3         | 0.88%   |
| Shenzhen WODPOSIT   | 3         | 0.88%   |
| GOODRAM             | 2         | 0.59%   |
| Corsair             | 2         | 0.59%   |
| Unknown             | 2         | 0.59%   |
| Unknown (0x0CDC)    | 1         | 0.29%   |
| Teikon              | 1         | 0.29%   |
| Saikano             | 1         | 0.29%   |
| PUSKILL             | 1         | 0.29%   |
| PNY                 | 1         | 0.29%   |
| Patriot             | 1         | 0.29%   |
| Nanya Technology    | 1         | 0.29%   |
| Kingmax             | 1         | 0.29%   |
| KINGBANK            | 1         | 0.29%   |
| Gold Key            | 1         | 0.29%   |
| G.Skill             | 1         | 0.29%   |
| fef5                | 1         | 0.29%   |
| ChangXin Memory     | 1         | 0.29%   |
| ASint Technology    | 1         | 0.29%   |
| AMD                 | 1         | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 7         | 1.95%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 6         | 1.67%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.11%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 1.11%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.11%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.11%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.11%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 4         | 1.11%   |
| Samsung RAM K3LKBKB@BM-MGCP 2GB Row Of Chips LPDDR5 6400MT/s     | 4         | 1.11%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 1.11%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 3         | 0.84%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.84%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips 6400MT/s        | 3         | 0.84%   |
| Shenzhen WODPOSIT RAM Module 8GB SODIMM DDR4 2666MT/s            | 3         | 0.84%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.84%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.84%   |
| Samsung RAM K3LKBKB0BM-MGCP 4GB SODIMM LPDDR5 6400MT/s           | 3         | 0.84%   |
| Micron RAM MT40A512M16LY-075:E 4GB SODIMM DDR4 3200MT/s          | 3         | 0.84%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.84%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.84%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 3         | 0.84%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.56%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.56%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.56%   |
| Transcend RAM JM3200HSE-32G 32GB SODIMM DDR4 3200MT/s            | 2         | 0.56%   |
| Timetec RAM S8G-1600 8GB SODIMM DDR3 1600MT/s                    | 2         | 0.56%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s            | 2         | 0.56%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 2         | 0.56%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 2         | 0.56%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.56%   |
| SK hynix RAM HMCG66MEBSA092N 8GB SODIMM DDR5 4800MT/s            | 2         | 0.56%   |
| SK hynix RAM HMCG66AGBSA095N 8GB SODIMM DDR5 5600MT/s            | 2         | 0.56%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.56%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 2         | 0.56%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.56%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 2         | 0.56%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.56%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 148       | 49.83%  |
| DDR3    | 61        | 20.54%  |
| LPDDR5  | 26        | 8.75%   |
| LPDDR4  | 24        | 8.08%   |
| DDR5    | 20        | 6.73%   |
| LPDDR3  | 10        | 3.37%   |
| DDR2    | 4         | 1.35%   |
| SDRAM   | 3         | 1.01%   |
| Unknown | 1         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 241       | 80.33%  |
| Row Of Chips | 52        | 17.33%  |
| Chip         | 4         | 1.33%   |
| Unknown      | 3         | 1%      |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 151       | 46.46%  |
| 4096  | 83        | 25.54%  |
| 16384 | 57        | 17.54%  |
| 2048  | 19        | 5.85%   |
| 32768 | 10        | 3.08%   |
| 1024  | 4         | 1.23%   |
| 1536  | 1         | 0.31%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 86        | 27.13%  |
| 1600    | 53        | 16.72%  |
| 2667    | 47        | 14.83%  |
| 6400    | 24        | 7.57%   |
| 2400    | 21        | 6.62%   |
| 4800    | 17        | 5.36%   |
| 4267    | 13        | 4.1%    |
| 2133    | 13        | 4.1%    |
| 1333    | 6         | 1.89%   |
| 1334    | 5         | 1.58%   |
| 1867    | 4         | 1.26%   |
| 5600    | 3         | 0.95%   |
| 2666    | 3         | 0.95%   |
| 8400    | 2         | 0.63%   |
| 5500    | 2         | 0.63%   |
| 3733    | 2         | 0.63%   |
| 3266    | 2         | 0.63%   |
| 2048    | 2         | 0.63%   |
| 667     | 2         | 0.63%   |
| Unknown | 2         | 0.63%   |
| 5200    | 1         | 0.32%   |
| 4266    | 1         | 0.32%   |
| 4199    | 1         | 0.32%   |
| 2933    | 1         | 0.32%   |
| 1067    | 1         | 0.32%   |
| 975     | 1         | 0.32%   |
| 800     | 1         | 0.32%   |
| 533     | 1         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 50%     |
| Samsung Electronics | 1         | 16.67%  |
| Canon               | 1         | 16.67%  |
| Brother Industries  | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Samsung ML-216x Series Laser Printer | 1         | 16.67%  |
| HP LaserJet Pro M201dw               | 1         | 16.67%  |
| HP LaserJet P2015 series             | 1         | 16.67%  |
| HP DeskJet 4100 series               | 1         | 16.67%  |
| Canon TS3100 series                  | 1         | 16.67%  |
| Brother HL-2250DN Laser Printer      | 1         | 16.67%  |

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
| Canon CanoScan 8800F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 118       | 23%     |
| IMC Networks                           | 58        | 11.31%  |
| Microdia                               | 52        | 10.14%  |
| Realtek Semiconductor                  | 48        | 9.36%   |
| Quanta                                 | 43        | 8.38%   |
| Bison Electronics                      | 26        | 5.07%   |
| Sunplus Innovation Technology          | 23        | 4.48%   |
| Luxvisions Innotech Limited            | 22        | 4.29%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 2.73%   |
| Apple                                  | 14        | 2.73%   |
| Lite-On Technology                     | 12        | 2.34%   |
| Acer                                   | 12        | 2.34%   |
| Sonix Technology                       | 11        | 2.14%   |
| Syntek                                 | 7         | 1.36%   |
| Alcor Micro                            | 7         | 1.36%   |
| Suyin                                  | 6         | 1.17%   |
| Silicon Motion                         | 5         | 0.97%   |
| Logitech                               | 5         | 0.97%   |
| Importek                               | 5         | 0.97%   |
| SunplusIT                              | 3         | 0.58%   |
| ShineTech                              | 3         | 0.58%   |
| icSpring                               | 3         | 0.58%   |
| Shine-optics                           | 2         | 0.39%   |
| Samsung Electronics                    | 2         | 0.39%   |
| Microsoft                              | 2         | 0.39%   |
| Lenovo                                 | 2         | 0.39%   |
| Sunplus Technology                     | 1         | 0.19%   |
| SHENZHEN AONI ELECTRONIC               | 1         | 0.19%   |
| Ricoh                                  | 1         | 0.19%   |
| Pixart Imaging                         | 1         | 0.19%   |
| Google                                 | 1         | 0.19%   |
| Foxconn / Hon Hai                      | 1         | 0.19%   |
| BKX-FAY-220407                         | 1         | 0.19%   |
| ALi                                    | 1         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony integrated camera                            | 39        | 7.51%   |
| Microdia Integrated_Webcam_HD                        | 29        | 5.59%   |
| IMC Networks Integrated Camera                       | 19        | 3.66%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 18        | 3.47%   |
| Realtek Integrated_Webcam_HD                         | 15        | 2.89%   |
| Chicony HP HD Camera                                 | 15        | 2.89%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 10        | 1.93%   |
| Realtek USB Camera                                   | 8         | 1.54%   |
| Chicony HP Truevision HD                             | 8         | 1.54%   |
| Chicony HD WebCam                                    | 8         | 1.54%   |
| Quanta ov9734_techfront_camera                       | 7         | 1.35%   |
| Chicony HD User Facing                               | 7         | 1.35%   |
| Bison Integrated Camera                              | 7         | 1.35%   |
| Sunplus Integrated_Webcam_HD                         | 6         | 1.16%   |
| Sonix USB2.0 HD UVC WebCam                           | 6         | 1.16%   |
| Quanta HD User Facing                                | 6         | 1.16%   |
| Lite-On Integrated Camera                            | 6         | 1.16%   |
| Syntek Integrated Camera                             | 5         | 0.96%   |
| Sonix USB2.0 FHD UVC WebCam                          | 5         | 0.96%   |
| Quanta HD Camera                                     | 5         | 0.96%   |
| IMC Networks HD Camera                               | 5         | 0.96%   |
| Apple FaceTime HD Camera                             | 5         | 0.96%   |
| Realtek Integrated Webcam_HD                         | 4         | 0.77%   |
| Realtek Integrated Webcam HD                         | 4         | 0.77%   |
| Quanta HP TrueVision HD Camera                       | 4         | 0.77%   |
| Quanta HP HD Camera                                  | 4         | 0.77%   |
| Quanta HD Webcam                                     | 4         | 0.77%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 4         | 0.77%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 4         | 0.77%   |
| Chicony TOSHIBA Web Camera - HD                      | 4         | 0.77%   |
| Chicony HP Wide Vision HD Camera                     | 4         | 0.77%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera     | 4         | 0.77%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 4         | 0.77%   |
| Acer BisonCam,NB Pro                                 | 4         | 0.77%   |
| Sunplus Integrated_Webcam_FHD                        | 3         | 0.58%   |
| Sunplus HD WebCam                                    | 3         | 0.58%   |
| Quanta ACER HD User Facing                           | 3         | 0.58%   |
| Quanta Acer FHD User Facing                          | 3         | 0.58%   |
| Microdia Webcam Vitade AF                            | 3         | 0.58%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 3         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 37        | 29.84%  |
| Shenzhen Goodix Technology         | 34        | 27.42%  |
| Synaptics                          | 26        | 20.97%  |
| Elan Microelectronics              | 13        | 10.48%  |
| Upek                               | 4         | 3.23%   |
| LighTuning Technology              | 4         | 3.23%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.42%   |
| AuthenTec                          | 2         | 1.61%   |
| Focal-systems.Corp                 | 1         | 0.81%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 28        | 22.58%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 7.26%   |
| Elan ELAN:ARM-M4                                                           | 8         | 6.45%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 4.84%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.84%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 4.84%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 4.03%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 4.03%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 4.03%   |
| Elan ELAN:Fingerprint                                                      | 5         | 4.03%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 3.23%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 3.23%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 2.42%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 2.42%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.61%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.61%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.61%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.61%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.61%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.81%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.81%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.81%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.81%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.81%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.81%   |
| Synaptics WBDI                                                             | 1         | 0.81%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.81%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.81%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.81%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.81%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.81%   |
| AuthenTec AES2810                                                          | 1         | 0.81%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.81%   |
| Unknown                                                                    | 1         | 0.81%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 25        | 60.98%  |
| Alcor Micro           | 11        | 26.83%  |
| Upek                  | 3         | 7.32%   |
| Hewlett-Packard       | 1         | 2.44%   |
| Advanced Card Systems | 1         | 2.44%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                                                | 11        | 26.83%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 26.83%  |
| Broadcom 58200                                                               | 7         | 17.07%  |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 14.63%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 7.32%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 2.44%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.44%   |
| Advanced Card Systems ACR122U                                                | 1         | 2.44%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 298       | 51.83%  |
| 1     | 212       | 36.87%  |
| 2     | 51        | 8.87%   |
| 3     | 9         | 1.57%   |
| 4     | 4         | 0.7%    |
| 10    | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 125       | 36.76%  |
| Graphics card            | 75        | 22.06%  |
| Chipcard                 | 39        | 11.47%  |
| Camera                   | 27        | 7.94%   |
| Net/wireless             | 24        | 7.06%   |
| Multimedia controller    | 23        | 6.76%   |
| Sound                    | 6         | 1.76%   |
| Storage                  | 5         | 1.47%   |
| Bluetooth                | 5         | 1.47%   |
| Net/ethernet             | 3         | 0.88%   |
| Card reader              | 3         | 0.88%   |
| Communication controller | 2         | 0.59%   |
| Unassigned class         | 1         | 0.29%   |
| Network                  | 1         | 0.29%   |
| Modem                    | 1         | 0.29%   |

