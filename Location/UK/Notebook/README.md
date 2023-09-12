Linux in UK - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Linux in UK.

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

Total: 5846

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop X515... | [4fd02051b6](https://linux-hardware.org/?probe=4fd02051b6) | Sep 07, 2023 |
| Unknown       | Unknown                     | [16cb5e0d5b](https://linux-hardware.org/?probe=16cb5e0d5b) | Sep 06, 2023 |
| eMachines     | eM350                       | [fae8f9e3f1](https://linux-hardware.org/?probe=fae8f9e3f1) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 20MD0014UK      | [428c816118](https://linux-hardware.org/?probe=428c816118) | Sep 06, 2023 |
| Lenovo        | ThinkPad T480 20L6S1FU00    | [f24dc99222](https://linux-hardware.org/?probe=f24dc99222) | Sep 06, 2023 |
| Sony          | SVF1521A7EB                 | [8b130feb09](https://linux-hardware.org/?probe=8b130feb09) | Sep 06, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [57764e02db](https://linux-hardware.org/?probe=57764e02db) | Sep 06, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [8b44f9cbdc](https://linux-hardware.org/?probe=8b44f9cbdc) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [f50ce96f55](https://linux-hardware.org/?probe=f50ce96f55) | Sep 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [cd1be324d4](https://linux-hardware.org/?probe=cd1be324d4) | Sep 05, 2023 |
| Dynabook      | Satellite Pro L50-G-193     | [6ab6bec7be](https://linux-hardware.org/?probe=6ab6bec7be) | Sep 05, 2023 |
| Notebook      | NL5xNU                      | [306dab3d42](https://linux-hardware.org/?probe=306dab3d42) | Sep 05, 2023 |
| HUAWEI        | NBD-WXX9                    | [005ebd39ce](https://linux-hardware.org/?probe=005ebd39ce) | Sep 05, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [2dff249b45](https://linux-hardware.org/?probe=2dff249b45) | Sep 04, 2023 |
| HP            | Compaq 6730b (NN204ET#AB... | [7165368bfe](https://linux-hardware.org/?probe=7165368bfe) | Sep 04, 2023 |
| Dell          | Inspiron 5770               | [1f2c94fe31](https://linux-hardware.org/?probe=1f2c94fe31) | Sep 03, 2023 |
| Dell          | XPS 17 9700                 | [e758c8955e](https://linux-hardware.org/?probe=e758c8955e) | Sep 03, 2023 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | [515a81a0d1](https://linux-hardware.org/?probe=515a81a0d1) | Sep 03, 2023 |
| Dell          | G15 5511                    | [e6afc56020](https://linux-hardware.org/?probe=e6afc56020) | Sep 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS24300    | [a28d4357d8](https://linux-hardware.org/?probe=a28d4357d8) | Sep 03, 2023 |
| Dell          | Latitude E6410              | [23f9814b2b](https://linux-hardware.org/?probe=23f9814b2b) | Sep 03, 2023 |
| Dell          | Studio 1735                 | [88cf1723e0](https://linux-hardware.org/?probe=88cf1723e0) | Sep 03, 2023 |
| Framework     | Laptop                      | [d153316fdd](https://linux-hardware.org/?probe=d153316fdd) | Sep 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [024e3beca4](https://linux-hardware.org/?probe=024e3beca4) | Sep 03, 2023 |
| Timi          | TM1613                      | [6acee9a858](https://linux-hardware.org/?probe=6acee9a858) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0f8242693](https://linux-hardware.org/?probe=e0f8242693) | Sep 02, 2023 |
| Dell          | Vostro 3590                 | [9a914c816e](https://linux-hardware.org/?probe=9a914c816e) | Sep 01, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [2433535726](https://linux-hardware.org/?probe=2433535726) | Sep 01, 2023 |
| ASUSTek       | UX305CA                     | [2220cac066](https://linux-hardware.org/?probe=2220cac066) | Sep 01, 2023 |
| HUAWEI        | MACH-WX9                    | [6f761aa23b](https://linux-hardware.org/?probe=6f761aa23b) | Aug 31, 2023 |
| Dell          | XPS 15 9560                 | [cef6754cd9](https://linux-hardware.org/?probe=cef6754cd9) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | [aad9baafe2](https://linux-hardware.org/?probe=aad9baafe2) | Aug 31, 2023 |
| HP            | Pavilion Notebook           | [86b1c6ecfa](https://linux-hardware.org/?probe=86b1c6ecfa) | Aug 30, 2023 |
| ASUSTek       | S500CA                      | [60d87bd79b](https://linux-hardware.org/?probe=60d87bd79b) | Aug 30, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [18f51f883e](https://linux-hardware.org/?probe=18f51f883e) | Aug 30, 2023 |
| Lenovo        | ThinkPad X200 7459BN8       | [38c0341384](https://linux-hardware.org/?probe=38c0341384) | Aug 30, 2023 |
| Dell          | XPS 15 9560                 | [a31df2b8fe](https://linux-hardware.org/?probe=a31df2b8fe) | Aug 30, 2023 |
| Dell          | Latitude 5290               | [0b4debc293](https://linux-hardware.org/?probe=0b4debc293) | Aug 30, 2023 |
| Lenovo        | G500 20236                  | [93f309e8ad](https://linux-hardware.org/?probe=93f309e8ad) | Aug 29, 2023 |
| Acer          | Aspire 5720                 | [36403a156e](https://linux-hardware.org/?probe=36403a156e) | Aug 29, 2023 |
| Dell          | Latitude 3190               | [7d8714663f](https://linux-hardware.org/?probe=7d8714663f) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [704a62ef33](https://linux-hardware.org/?probe=704a62ef33) | Aug 29, 2023 |
| Framework     | Laptop (13th Gen Intel C... | [beb1174dde](https://linux-hardware.org/?probe=beb1174dde) | Aug 29, 2023 |
| Dell          | XPS 15 9500                 | [74ad31c9de](https://linux-hardware.org/?probe=74ad31c9de) | Aug 29, 2023 |
| Acer          | Aspire V5-471               | [c5d2dabe27](https://linux-hardware.org/?probe=c5d2dabe27) | Aug 28, 2023 |
| Toshiba       | Satellite C55D-A-14W        | [9f725ce1a7](https://linux-hardware.org/?probe=9f725ce1a7) | Aug 28, 2023 |
| Apple         | MacBookPro5,1               | [62464b6b0d](https://linux-hardware.org/?probe=62464b6b0d) | Aug 28, 2023 |
| Toshiba       | Satellite C55D-A-14W        | [c091e0bc8b](https://linux-hardware.org/?probe=c091e0bc8b) | Aug 28, 2023 |
| Dell          | Latitude E7240              | [1eab9b5f8d](https://linux-hardware.org/?probe=1eab9b5f8d) | Aug 28, 2023 |
| Valve         | Jupiter                     | [8a68ffe7b0](https://linux-hardware.org/?probe=8a68ffe7b0) | Aug 28, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [4c01a3be17](https://linux-hardware.org/?probe=4c01a3be17) | Aug 28, 2023 |
| Dell          | Latitude 7480               | [95f7cd5046](https://linux-hardware.org/?probe=95f7cd5046) | Aug 27, 2023 |
| Lenovo        | ThinkPad P51s W10DG 20JY... | [783bbb68e6](https://linux-hardware.org/?probe=783bbb68e6) | Aug 27, 2023 |
| Dell          | Latitude E6420              | [1e2c15f171](https://linux-hardware.org/?probe=1e2c15f171) | Aug 27, 2023 |
| Lenovo        | ThinkPad T460 20FMS05K05    | [747e8d4f6a](https://linux-hardware.org/?probe=747e8d4f6a) | Aug 27, 2023 |
| Dell          | Studio 1737                 | [8e668fe167](https://linux-hardware.org/?probe=8e668fe167) | Aug 27, 2023 |
| ZOOSTORM      | 7200-9062A                  | [5ee843d3d1](https://linux-hardware.org/?probe=5ee843d3d1) | Aug 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7e9c9debdf](https://linux-hardware.org/?probe=7e9c9debdf) | Aug 26, 2023 |
| Dell          | Precision M6800             | [6aa5f8e441](https://linux-hardware.org/?probe=6aa5f8e441) | Aug 26, 2023 |
| Acer          | Aspire V5-571               | [033994cebf](https://linux-hardware.org/?probe=033994cebf) | Aug 26, 2023 |
| Acer          | Aspire A515-56              | [53b787dc90](https://linux-hardware.org/?probe=53b787dc90) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [83695164cc](https://linux-hardware.org/?probe=83695164cc) | Aug 26, 2023 |
| Unknown       | Unknown                     | [dc1c907cda](https://linux-hardware.org/?probe=dc1c907cda) | Aug 26, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [ee4e04964c](https://linux-hardware.org/?probe=ee4e04964c) | Aug 26, 2023 |
| Acer          | Aspire V3-571               | [376d5e8a22](https://linux-hardware.org/?probe=376d5e8a22) | Aug 25, 2023 |
| HUAWEI        | MACHR-WX9                   | [a8c4ca7aee](https://linux-hardware.org/?probe=a8c4ca7aee) | Aug 25, 2023 |
| Packard Be... | EasyNote TJ66               | [010fe56f65](https://linux-hardware.org/?probe=010fe56f65) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [7355715562](https://linux-hardware.org/?probe=7355715562) | Aug 25, 2023 |
| Notebook      | NL5xNU                      | [116561b889](https://linux-hardware.org/?probe=116561b889) | Aug 25, 2023 |
| Lenovo        | ThinkPad T430 2349KAG       | [f2348b8eee](https://linux-hardware.org/?probe=f2348b8eee) | Aug 25, 2023 |
| PC Special... | Ionico 16                   | [78125c34b4](https://linux-hardware.org/?probe=78125c34b4) | Aug 25, 2023 |
| Sony          | SVF15A1M2ES                 | [b352453232](https://linux-hardware.org/?probe=b352453232) | Aug 24, 2023 |
| Google        | Eldrid                      | [e451d840cf](https://linux-hardware.org/?probe=e451d840cf) | Aug 24, 2023 |
| Valve         | Jupiter                     | [98dce455d0](https://linux-hardware.org/?probe=98dce455d0) | Aug 24, 2023 |
| HP            | Laptop 17-cn0xxx            | [5b5a4fa5d9](https://linux-hardware.org/?probe=5b5a4fa5d9) | Aug 23, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [adda6295fb](https://linux-hardware.org/?probe=adda6295fb) | Aug 23, 2023 |
| Acer          | AOD255                      | [06c6346db1](https://linux-hardware.org/?probe=06c6346db1) | Aug 23, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 PRO ARP23P     | [0005c7836c](https://linux-hardware.org/?probe=0005c7836c) | Aug 22, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2RV0... | [e8d2c8e1d5](https://linux-hardware.org/?probe=e8d2c8e1d5) | Aug 22, 2023 |
| Acer          | Swift SF314-512             | [fce52ede18](https://linux-hardware.org/?probe=fce52ede18) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [f35c644052](https://linux-hardware.org/?probe=f35c644052) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [4f4bed768e](https://linux-hardware.org/?probe=4f4bed768e) | Aug 22, 2023 |
| Acer          | Swift SF314-512             | [9cd3fa37a0](https://linux-hardware.org/?probe=9cd3fa37a0) | Aug 21, 2023 |
| Lenovo        | Z70-80 80FG                 | [bb5a7dc0d8](https://linux-hardware.org/?probe=bb5a7dc0d8) | Aug 21, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [62cddb0954](https://linux-hardware.org/?probe=62cddb0954) | Aug 21, 2023 |
| Medion        | Akoya THE TOUCH 10          | [c121ae9a76](https://linux-hardware.org/?probe=c121ae9a76) | Aug 21, 2023 |
| Apple         | MacBookPro14,1              | [dc96aa9cee](https://linux-hardware.org/?probe=dc96aa9cee) | Aug 19, 2023 |
| Dell          | XPS 15 9550                 | [3b3ae781c6](https://linux-hardware.org/?probe=3b3ae781c6) | Aug 19, 2023 |
| Acer          | Aspire A515-56              | [97a87f1178](https://linux-hardware.org/?probe=97a87f1178) | Aug 19, 2023 |
| Lenovo        | ThinkPad T450 20BUS5W000    | [cb1eebf517](https://linux-hardware.org/?probe=cb1eebf517) | Aug 19, 2023 |
| Lenovo        | ThinkPad T450 20BUS5W000    | [87d16e9431](https://linux-hardware.org/?probe=87d16e9431) | Aug 19, 2023 |
| Timi          | RedmiBook Pro 14S           | [323664ecb8](https://linux-hardware.org/?probe=323664ecb8) | Aug 18, 2023 |
| Acer          | Swift SF514-52T             | [9cd2857c01](https://linux-hardware.org/?probe=9cd2857c01) | Aug 18, 2023 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | [c9e9e56ddd](https://linux-hardware.org/?probe=c9e9e56ddd) | Aug 18, 2023 |
| Lenovo        | Flex 2-15 20405             | [77942ee5db](https://linux-hardware.org/?probe=77942ee5db) | Aug 18, 2023 |
| Dell          | XPS 15 9530                 | [ace741b68a](https://linux-hardware.org/?probe=ace741b68a) | Aug 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c647987aaf](https://linux-hardware.org/?probe=c647987aaf) | Aug 16, 2023 |
| Dell          | Inspiron 7370               | [2676762739](https://linux-hardware.org/?probe=2676762739) | Aug 16, 2023 |
| Acer          | Aspire V5-571               | [bb39a5a125](https://linux-hardware.org/?probe=bb39a5a125) | Aug 15, 2023 |
| MSI           | GP62 6QF                    | [d9455cbed8](https://linux-hardware.org/?probe=d9455cbed8) | Aug 15, 2023 |
| Sony          | VPCEH3N6E                   | [884688ddbf](https://linux-hardware.org/?probe=884688ddbf) | Aug 15, 2023 |
| Samsung       | 755XDA                      | [3be32e2365](https://linux-hardware.org/?probe=3be32e2365) | Aug 15, 2023 |
| Lenovo        | ThinkPad T510 43842RG       | [9b2f268192](https://linux-hardware.org/?probe=9b2f268192) | Aug 15, 2023 |
| Google        | Bobba360                    | [e2ae1afdcc](https://linux-hardware.org/?probe=e2ae1afdcc) | Aug 14, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [fe4612b027](https://linux-hardware.org/?probe=fe4612b027) | Aug 14, 2023 |
| Google        | Bobba360                    | [f211501fde](https://linux-hardware.org/?probe=f211501fde) | Aug 14, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c822a4c96f](https://linux-hardware.org/?probe=c822a4c96f) | Aug 13, 2023 |
| ASUSTek       | GL552VW                     | [9db2ba151b](https://linux-hardware.org/?probe=9db2ba151b) | Aug 13, 2023 |
| Dell          | XPS 15 9560                 | [2461c78ff0](https://linux-hardware.org/?probe=2461c78ff0) | Aug 13, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [cd8b4a2836](https://linux-hardware.org/?probe=cd8b4a2836) | Aug 13, 2023 |
| HP            | Pavilion dv5                | [78530d4418](https://linux-hardware.org/?probe=78530d4418) | Aug 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS3320C    | [51f9e0c482](https://linux-hardware.org/?probe=51f9e0c482) | Aug 13, 2023 |
| Toshiba       | Satellite C50D-A-13G        | [e1a3542078](https://linux-hardware.org/?probe=e1a3542078) | Aug 12, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [411b9f412c](https://linux-hardware.org/?probe=411b9f412c) | Aug 12, 2023 |
| Timi          | RedmiBook Pro 15S           | [20559d710a](https://linux-hardware.org/?probe=20559d710a) | Aug 12, 2023 |
| Acer          | Aspire A317-53              | [17dacd99a6](https://linux-hardware.org/?probe=17dacd99a6) | Aug 12, 2023 |
| HP            | Pavilion dv5                | [41c7682f98](https://linux-hardware.org/?probe=41c7682f98) | Aug 11, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [abaa0512b0](https://linux-hardware.org/?probe=abaa0512b0) | Aug 11, 2023 |
| HP            | Pavilion dv5                | [a8f62e42dc](https://linux-hardware.org/?probe=a8f62e42dc) | Aug 11, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [83a0a8a2aa](https://linux-hardware.org/?probe=83a0a8a2aa) | Aug 11, 2023 |
| Lenovo        | IdeaPad 3 14ITL05 81X7      | [f062831bd7](https://linux-hardware.org/?probe=f062831bd7) | Aug 11, 2023 |
| HP            | Laptop 15s-eq2xxx           | [e45562b838](https://linux-hardware.org/?probe=e45562b838) | Aug 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [24629e2553](https://linux-hardware.org/?probe=24629e2553) | Aug 10, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [6f422f386f](https://linux-hardware.org/?probe=6f422f386f) | Aug 10, 2023 |
| Gigabyte      | AERO 15-WA                  | [bd9f5d0f39](https://linux-hardware.org/?probe=bd9f5d0f39) | Aug 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | [c87b299407](https://linux-hardware.org/?probe=c87b299407) | Aug 10, 2023 |
| Acer          | Aspire A317-53              | [5a2d81b438](https://linux-hardware.org/?probe=5a2d81b438) | Aug 09, 2023 |
| Samsung       | N150P/N210P/N220P           | [459b9f31b9](https://linux-hardware.org/?probe=459b9f31b9) | Aug 09, 2023 |
| Dell          | Inspiron 7537               | [61093a9af1](https://linux-hardware.org/?probe=61093a9af1) | Aug 08, 2023 |
| Dell          | Latitude D630               | [a57bb7cde1](https://linux-hardware.org/?probe=a57bb7cde1) | Aug 08, 2023 |
| Apple         | MacBookPro8,1               | [6165a2d50e](https://linux-hardware.org/?probe=6165a2d50e) | Aug 08, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [6738a625d8](https://linux-hardware.org/?probe=6738a625d8) | Aug 08, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [66488bdd81](https://linux-hardware.org/?probe=66488bdd81) | Aug 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5babb790d3](https://linux-hardware.org/?probe=5babb790d3) | Aug 08, 2023 |
| Acer          | Aspire 1825PTZ              | [553d2539fa](https://linux-hardware.org/?probe=553d2539fa) | Aug 07, 2023 |
| Acer          | Aspire A515-56              | [84b0c88b0a](https://linux-hardware.org/?probe=84b0c88b0a) | Aug 07, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [de8e0fbde8](https://linux-hardware.org/?probe=de8e0fbde8) | Aug 07, 2023 |
| HP            | Laptop 15-da0xxx            | [0cb4da66e3](https://linux-hardware.org/?probe=0cb4da66e3) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [b4b049b997](https://linux-hardware.org/?probe=b4b049b997) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8633bc5aa5](https://linux-hardware.org/?probe=8633bc5aa5) | Aug 07, 2023 |
| Dell          | Latitude 5411               | [2d69739196](https://linux-hardware.org/?probe=2d69739196) | Aug 07, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | [3e9ce860b6](https://linux-hardware.org/?probe=3e9ce860b6) | Aug 07, 2023 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [053d461635](https://linux-hardware.org/?probe=053d461635) | Aug 06, 2023 |
| Unknown       | Unknown                     | [691c44286e](https://linux-hardware.org/?probe=691c44286e) | Aug 06, 2023 |
| Acer          | Aspire A515-56              | [dfe905b869](https://linux-hardware.org/?probe=dfe905b869) | Aug 06, 2023 |
| Acer          | Aspire A317-53              | [5bb0feab0c](https://linux-hardware.org/?probe=5bb0feab0c) | Aug 06, 2023 |
| Dell          | Latitude 5590               | [83d389e795](https://linux-hardware.org/?probe=83d389e795) | Aug 06, 2023 |
| Dell          | Venue 8 Pro 5855            | [146fa40942](https://linux-hardware.org/?probe=146fa40942) | Aug 05, 2023 |
| Lenovo        | 100w Gen 3 82HY             | [3feb7899d2](https://linux-hardware.org/?probe=3feb7899d2) | Aug 05, 2023 |
| GPD           | G1621-02                    | [7e37b7bbee](https://linux-hardware.org/?probe=7e37b7bbee) | Aug 04, 2023 |
| HP            | 470 G7 Notebook PC          | [7e4a9b4618](https://linux-hardware.org/?probe=7e4a9b4618) | Aug 04, 2023 |
| GPD           | G1621-02                    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [a9072f3117](https://linux-hardware.org/?probe=a9072f3117) | Aug 04, 2023 |
| HP            | 255 G3                      | [c8b3db6b0b](https://linux-hardware.org/?probe=c8b3db6b0b) | Aug 03, 2023 |
| Acer          | Aspire 7750G                | [71f5ef03f9](https://linux-hardware.org/?probe=71f5ef03f9) | Aug 03, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6C... | [a97312771e](https://linux-hardware.org/?probe=a97312771e) | Aug 03, 2023 |
| Valve         | Jupiter                     | [f928feaff9](https://linux-hardware.org/?probe=f928feaff9) | Aug 02, 2023 |
| Toshiba       | Satellite C660              | [5e74aca4e7](https://linux-hardware.org/?probe=5e74aca4e7) | Aug 02, 2023 |
| HP            | Pavilion 15                 | [c66316cd62](https://linux-hardware.org/?probe=c66316cd62) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Acer          | Aspire A317-53              | [3f1af34e1b](https://linux-hardware.org/?probe=3f1af34e1b) | Aug 01, 2023 |
| HP            | Pavilion 15                 | [1ad3dc2f1b](https://linux-hardware.org/?probe=1ad3dc2f1b) | Aug 01, 2023 |
| Lenovo        | Flex 2-14 20404             | [dd24507513](https://linux-hardware.org/?probe=dd24507513) | Jul 31, 2023 |
| HP            | ProBook 4740s               | [d0aae87145](https://linux-hardware.org/?probe=d0aae87145) | Jul 31, 2023 |
| HP            | ProBook 4740s               | [985ee4b495](https://linux-hardware.org/?probe=985ee4b495) | Jul 30, 2023 |
| HP            | ProBook 430 G3              | [a42e1c787e](https://linux-hardware.org/?probe=a42e1c787e) | Jul 30, 2023 |
| Valve         | Jupiter                     | [82e4fa2fbc](https://linux-hardware.org/?probe=82e4fa2fbc) | Jul 30, 2023 |
| HP            | ENVY Notebook               | [3e13681e00](https://linux-hardware.org/?probe=3e13681e00) | Jul 29, 2023 |
| HP            | 470 17 inch G9 Notebook ... | [dbcda8f4d0](https://linux-hardware.org/?probe=dbcda8f4d0) | Jul 29, 2023 |
| Razer         | Blade                       | [6c3ef3aa59](https://linux-hardware.org/?probe=6c3ef3aa59) | Jul 29, 2023 |
| Dell          | Latitude E6420              | [a70852def5](https://linux-hardware.org/?probe=a70852def5) | Jul 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1N700    | [3486243fd6](https://linux-hardware.org/?probe=3486243fd6) | Jul 29, 2023 |
| Unknown       | Unknown                     | [73836c0a75](https://linux-hardware.org/?probe=73836c0a75) | Jul 29, 2023 |
| Dell          | XPS 9320                    | [4000df5584](https://linux-hardware.org/?probe=4000df5584) | Jul 29, 2023 |
| Valve         | Jupiter                     | [ff714f1791](https://linux-hardware.org/?probe=ff714f1791) | Jul 28, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [ba7c69f7e0](https://linux-hardware.org/?probe=ba7c69f7e0) | Jul 28, 2023 |
| Apple         | MacBookPro12,1              | [bc3cb3cbfd](https://linux-hardware.org/?probe=bc3cb3cbfd) | Jul 28, 2023 |
| Dell          | Latitude 3410               | [449e4c62f3](https://linux-hardware.org/?probe=449e4c62f3) | Jul 28, 2023 |
| Dell          | XPS 13 9380                 | [b784cbe3ab](https://linux-hardware.org/?probe=b784cbe3ab) | Jul 28, 2023 |
| Dell          | Inspiron 13-5378            | [cd318f6b75](https://linux-hardware.org/?probe=cd318f6b75) | Jul 27, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e08f65110d](https://linux-hardware.org/?probe=e08f65110d) | Jul 27, 2023 |
| Acer          | Aspire A515-56              | [7c716b6ab0](https://linux-hardware.org/?probe=7c716b6ab0) | Jul 27, 2023 |
| HP            | Laptop 14s-fq1xxx           | [84ab2faa6f](https://linux-hardware.org/?probe=84ab2faa6f) | Jul 27, 2023 |
| PC Special... | Ionico 16                   | [5c91300246](https://linux-hardware.org/?probe=5c91300246) | Jul 26, 2023 |
| Dell          | Inspiron 13-5378            | [fd43074149](https://linux-hardware.org/?probe=fd43074149) | Jul 26, 2023 |
| Valve         | Jupiter                     | [1adda13639](https://linux-hardware.org/?probe=1adda13639) | Jul 26, 2023 |
| HP            | Laptop 14s-fq1xxx           | [ee10ac6c06](https://linux-hardware.org/?probe=ee10ac6c06) | Jul 26, 2023 |
| HP            | Notebook                    | [beef8e7fce](https://linux-hardware.org/?probe=beef8e7fce) | Jul 25, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [3b05aaff82](https://linux-hardware.org/?probe=3b05aaff82) | Jul 25, 2023 |
| Dell          | Latitude 5530               | [cccd0bf0b8](https://linux-hardware.org/?probe=cccd0bf0b8) | Jul 25, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [6fc7661aae](https://linux-hardware.org/?probe=6fc7661aae) | Jul 25, 2023 |
| MSI           | Katana GF66 11UG            | [bd45023e8e](https://linux-hardware.org/?probe=bd45023e8e) | Jul 25, 2023 |
| Acer          | Swift SFE16-43              | [ada40722ae](https://linux-hardware.org/?probe=ada40722ae) | Jul 25, 2023 |
| Dell          | Vostro 1500                 | [c57ac4da0a](https://linux-hardware.org/?probe=c57ac4da0a) | Jul 25, 2023 |
| HP            | EliteBook 8470p             | [834378c125](https://linux-hardware.org/?probe=834378c125) | Jul 25, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [e46d04faa8](https://linux-hardware.org/?probe=e46d04faa8) | Jul 25, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [0b7f69aaf6](https://linux-hardware.org/?probe=0b7f69aaf6) | Jul 25, 2023 |
| Chuwi         | CoreBook Pro                | [21ab3832ea](https://linux-hardware.org/?probe=21ab3832ea) | Jul 24, 2023 |
| Dell          | Inspiron 5570               | [3d08e59ce3](https://linux-hardware.org/?probe=3d08e59ce3) | Jul 24, 2023 |
| Dell          | Latitude 2110               | [05a7868709](https://linux-hardware.org/?probe=05a7868709) | Jul 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8b89c63576](https://linux-hardware.org/?probe=8b89c63576) | Jul 24, 2023 |
| Gigabyte      | P17FR5                      | [817b78d77b](https://linux-hardware.org/?probe=817b78d77b) | Jul 23, 2023 |
| PC Special... | Standard                    | [992aec5bb8](https://linux-hardware.org/?probe=992aec5bb8) | Jul 23, 2023 |
| HP            | Notebook                    | [4746f66332](https://linux-hardware.org/?probe=4746f66332) | Jul 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [ff5e295a5d](https://linux-hardware.org/?probe=ff5e295a5d) | Jul 23, 2023 |
| HP            | 255 G6 Notebook PC          | [5c5147b82d](https://linux-hardware.org/?probe=5c5147b82d) | Jul 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS1N700    | [e42f9111c6](https://linux-hardware.org/?probe=e42f9111c6) | Jul 23, 2023 |
| Dell          | XPS 15 9570                 | [9a62fe1979](https://linux-hardware.org/?probe=9a62fe1979) | Jul 22, 2023 |
| Valve         | Jupiter                     | [0e8e6ce1ae](https://linux-hardware.org/?probe=0e8e6ce1ae) | Jul 22, 2023 |
| Valve         | Jupiter                     | [fa8db9f24a](https://linux-hardware.org/?probe=fa8db9f24a) | Jul 22, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [c06811057a](https://linux-hardware.org/?probe=c06811057a) | Jul 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e948334857](https://linux-hardware.org/?probe=e948334857) | Jul 22, 2023 |
| Dell          | System XPS L702X            | [21f1d68bc1](https://linux-hardware.org/?probe=21f1d68bc1) | Jul 21, 2023 |
| Apple         | MacBookAir7,1               | [e82f5072df](https://linux-hardware.org/?probe=e82f5072df) | Jul 20, 2023 |
| Dell          | Vostro 1500                 | [0c4f8fe4d2](https://linux-hardware.org/?probe=0c4f8fe4d2) | Jul 20, 2023 |
| Acer          | Aspire A317-53              | [d8e84157ab](https://linux-hardware.org/?probe=d8e84157ab) | Jul 20, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e0b92a00b5](https://linux-hardware.org/?probe=e0b92a00b5) | Jul 19, 2023 |
| Dell          | Inspiron N5110              | [140474e198](https://linux-hardware.org/?probe=140474e198) | Jul 19, 2023 |
| Lenovo        | ThinkPad E560 20EV000YUK    | [0e89144534](https://linux-hardware.org/?probe=0e89144534) | Jul 19, 2023 |
| Dell          | XPS 15 9570                 | [e6cf0622b0](https://linux-hardware.org/?probe=e6cf0622b0) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [a4584a139f](https://linux-hardware.org/?probe=a4584a139f) | Jul 19, 2023 |
| HP            | Laptop 15-dw0xxx            | [ba24f3bb61](https://linux-hardware.org/?probe=ba24f3bb61) | Jul 18, 2023 |
| Valve         | Jupiter                     | [3abdfed88b](https://linux-hardware.org/?probe=3abdfed88b) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [f5dc246f7c](https://linux-hardware.org/?probe=f5dc246f7c) | Jul 18, 2023 |
| HP            | ENVY Laptop 17-cr0xxx       | [abec03689c](https://linux-hardware.org/?probe=abec03689c) | Jul 18, 2023 |
| Valve         | Jupiter                     | [4beb3117df](https://linux-hardware.org/?probe=4beb3117df) | Jul 18, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [a448a20876](https://linux-hardware.org/?probe=a448a20876) | Jul 17, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [958f57fd27](https://linux-hardware.org/?probe=958f57fd27) | Jul 17, 2023 |
| Sony          | VGN-S3HP                    | [6e2c92c447](https://linux-hardware.org/?probe=6e2c92c447) | Jul 17, 2023 |
| Dell          | Precision M6800             | [8ddd80db6c](https://linux-hardware.org/?probe=8ddd80db6c) | Jul 17, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [3a7fbf07fa](https://linux-hardware.org/?probe=3a7fbf07fa) | Jul 17, 2023 |
| Dell          | Inspiron 1501               | [a79d62db7c](https://linux-hardware.org/?probe=a79d62db7c) | Jul 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | [ec4db25eb9](https://linux-hardware.org/?probe=ec4db25eb9) | Jul 16, 2023 |
| Acer          | Aspire A317-53              | [9dd235116d](https://linux-hardware.org/?probe=9dd235116d) | Jul 16, 2023 |
| Dell          | G5 5587                     | [fc861c593a](https://linux-hardware.org/?probe=fc861c593a) | Jul 16, 2023 |
| Acer          | Predator PH315-52           | [8231c1b7c0](https://linux-hardware.org/?probe=8231c1b7c0) | Jul 16, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [8977d2e0a3](https://linux-hardware.org/?probe=8977d2e0a3) | Jul 16, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [35f3837811](https://linux-hardware.org/?probe=35f3837811) | Jul 16, 2023 |
| Dell          | Latitude E4300              | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Acer          | Aspire A315-32              | [7044de848c](https://linux-hardware.org/?probe=7044de848c) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | [bcd1c01ad6](https://linux-hardware.org/?probe=bcd1c01ad6) | Jul 15, 2023 |
| Lenovo        | G580 20150                  | [390008fe3c](https://linux-hardware.org/?probe=390008fe3c) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| HP            | Pavilion 15                 | [95f81cdf21](https://linux-hardware.org/?probe=95f81cdf21) | Jul 15, 2023 |
| Dell          | G15 5510                    | [28b7a732f2](https://linux-hardware.org/?probe=28b7a732f2) | Jul 15, 2023 |
| Lenovo        | ThinkPad T530 2429HD6       | [1c48702f3c](https://linux-hardware.org/?probe=1c48702f3c) | Jul 14, 2023 |
| Dell          | XPS 13 9300                 | [ca425f6c38](https://linux-hardware.org/?probe=ca425f6c38) | Jul 14, 2023 |
| Lenovo        | ThinkPad X220 4290FC1       | [d6c0ccb8f1](https://linux-hardware.org/?probe=d6c0ccb8f1) | Jul 14, 2023 |
| Notebook      | N150ZU                      | [61be22ac36](https://linux-hardware.org/?probe=61be22ac36) | Jul 14, 2023 |
| Dell          | Inspiron 15 3520            | [163766c886](https://linux-hardware.org/?probe=163766c886) | Jul 14, 2023 |
| Acer          | Swift SF313-52              | [3b393fc916](https://linux-hardware.org/?probe=3b393fc916) | Jul 14, 2023 |
| Google        | Droid                       | [9b77a9ba04](https://linux-hardware.org/?probe=9b77a9ba04) | Jul 14, 2023 |
| Lenovo        | ThinkPad X230 2325FG0       | [4df76c784c](https://linux-hardware.org/?probe=4df76c784c) | Jul 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | [4b9cba03ac](https://linux-hardware.org/?probe=4b9cba03ac) | Jul 13, 2023 |
| Dell          | XPS 17 9730                 | [b074a1deb3](https://linux-hardware.org/?probe=b074a1deb3) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS50T0Q    | [0d5f86f700](https://linux-hardware.org/?probe=0d5f86f700) | Jul 13, 2023 |
| MSI           | GT70 2PE                    | [9e49d96293](https://linux-hardware.org/?probe=9e49d96293) | Jul 13, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [dd2c7b0c60](https://linux-hardware.org/?probe=dd2c7b0c60) | Jul 12, 2023 |
| Google        | Lillipup                    | [b7b430e7b4](https://linux-hardware.org/?probe=b7b430e7b4) | Jul 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [15067533b3](https://linux-hardware.org/?probe=15067533b3) | Jul 12, 2023 |
| HP            | EliteBook Folio 1040 G3     | [95c073864d](https://linux-hardware.org/?probe=95c073864d) | Jul 12, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [ad18a95d12](https://linux-hardware.org/?probe=ad18a95d12) | Jul 12, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [9479004a7e](https://linux-hardware.org/?probe=9479004a7e) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | [ad75f0a6e0](https://linux-hardware.org/?probe=ad75f0a6e0) | Jul 12, 2023 |
| Dell          | XPS 15 9530                 | [d78fb6bdd4](https://linux-hardware.org/?probe=d78fb6bdd4) | Jul 12, 2023 |
| HP            | 630                         | [671710637c](https://linux-hardware.org/?probe=671710637c) | Jul 11, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [90466d16ca](https://linux-hardware.org/?probe=90466d16ca) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [08bbd89b8c](https://linux-hardware.org/?probe=08bbd89b8c) | Jul 11, 2023 |
| Lenovo        | ThinkPad A285 20MXS0JR14    | [23b123605f](https://linux-hardware.org/?probe=23b123605f) | Jul 11, 2023 |
| Sony          | SVP1321M2EB                 | [e767bbc26b](https://linux-hardware.org/?probe=e767bbc26b) | Jul 11, 2023 |
| Sony          | VPCZ214GX                   | [d63fc5c563](https://linux-hardware.org/?probe=d63fc5c563) | Jul 11, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [56de408d31](https://linux-hardware.org/?probe=56de408d31) | Jul 10, 2023 |
| Valve         | Jupiter                     | [5d55bf223d](https://linux-hardware.org/?probe=5d55bf223d) | Jul 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [96ca518dc6](https://linux-hardware.org/?probe=96ca518dc6) | Jul 09, 2023 |
| ASUSTek       | K54C                        | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| Apple         | MacBookPro10,1              | [43ec3cf70b](https://linux-hardware.org/?probe=43ec3cf70b) | Jul 09, 2023 |
| Dell          | XPS 15 9530                 | [513a03f793](https://linux-hardware.org/?probe=513a03f793) | Jul 08, 2023 |
| Apple         | MacBookPro10,1              | [ef7acb569d](https://linux-hardware.org/?probe=ef7acb569d) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [ffde5244e6](https://linux-hardware.org/?probe=ffde5244e6) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | [2e2541c7a6](https://linux-hardware.org/?probe=2e2541c7a6) | Jul 08, 2023 |
| Apple         | MacBookPro13,1              | [3a64eabd9b](https://linux-hardware.org/?probe=3a64eabd9b) | Jul 08, 2023 |
| Acer          | Aspire A315-54              | [4aba66ddfb](https://linux-hardware.org/?probe=4aba66ddfb) | Jul 07, 2023 |
| Lenovo        | Flex 2-14 20404             | [93f50211c2](https://linux-hardware.org/?probe=93f50211c2) | Jul 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [03f454349c](https://linux-hardware.org/?probe=03f454349c) | Jul 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [e17ab8bbe7](https://linux-hardware.org/?probe=e17ab8bbe7) | Jul 06, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [bdc65d0c9f](https://linux-hardware.org/?probe=bdc65d0c9f) | Jul 05, 2023 |
| Lenovo        | ThinkPad T400 6474W7T       | [56144d66ac](https://linux-hardware.org/?probe=56144d66ac) | Jul 05, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [bb0e10ceef](https://linux-hardware.org/?probe=bb0e10ceef) | Jul 05, 2023 |
| MSI           | GF75 Thin 9SC               | [b180548e9c](https://linux-hardware.org/?probe=b180548e9c) | Jul 05, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [d5b720740f](https://linux-hardware.org/?probe=d5b720740f) | Jul 04, 2023 |
| Valve         | Jupiter                     | [8b40767026](https://linux-hardware.org/?probe=8b40767026) | Jul 04, 2023 |
| HP            | Compaq 6910p (GR670ET#UU... | [1ca7da939f](https://linux-hardware.org/?probe=1ca7da939f) | Jul 02, 2023 |
| HP            | EliteBook 2540p             | [d69b1af76b](https://linux-hardware.org/?probe=d69b1af76b) | Jul 02, 2023 |
| Apple         | MacBookPro12,1              | [f89bdd4374](https://linux-hardware.org/?probe=f89bdd4374) | Jul 02, 2023 |
| HP            | EliteBook 8440p             | [9c8f32ac20](https://linux-hardware.org/?probe=9c8f32ac20) | Jul 02, 2023 |
| HP            | EliteBook 8440p             | [6c32038385](https://linux-hardware.org/?probe=6c32038385) | Jul 02, 2023 |
| Dell          | G3 3779                     | [bcae1c7195](https://linux-hardware.org/?probe=bcae1c7195) | Jul 02, 2023 |
| Teclast       | F15Plus 2                   | [29b2c807e6](https://linux-hardware.org/?probe=29b2c807e6) | Jul 01, 2023 |
| Alienware     | m16 R1 AMD                  | [291c477bd0](https://linux-hardware.org/?probe=291c477bd0) | Jul 01, 2023 |
| HP            | Stream Notebook PC 11       | [c1e18957a4](https://linux-hardware.org/?probe=c1e18957a4) | Jul 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [e9f511bc00](https://linux-hardware.org/?probe=e9f511bc00) | Jul 01, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [8f38634e0e](https://linux-hardware.org/?probe=8f38634e0e) | Jul 01, 2023 |
| lapbook       | S15 PRO                     | [06ae615fd1](https://linux-hardware.org/?probe=06ae615fd1) | Jul 01, 2023 |
| Toshiba       | Satellite Pro L650          | [d8da913f23](https://linux-hardware.org/?probe=d8da913f23) | Jul 01, 2023 |
| Teclast       | F15Plus 2                   | [4593b411f0](https://linux-hardware.org/?probe=4593b411f0) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-cs1xx... | [6c8a67be9e](https://linux-hardware.org/?probe=6c8a67be9e) | Jun 30, 2023 |
| Valve         | Jupiter                     | [89d751f07f](https://linux-hardware.org/?probe=89d751f07f) | Jun 30, 2023 |
| HP            | Unknown                     | [0f4ae63ce0](https://linux-hardware.org/?probe=0f4ae63ce0) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | [703ae4bd0b](https://linux-hardware.org/?probe=703ae4bd0b) | Jun 30, 2023 |
| HP            | Laptop 15-da0xxx            | [bf3c982248](https://linux-hardware.org/?probe=bf3c982248) | Jun 30, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d058f48980](https://linux-hardware.org/?probe=d058f48980) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [93e0628fbe](https://linux-hardware.org/?probe=93e0628fbe) | Jun 29, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [791bfd25bf](https://linux-hardware.org/?probe=791bfd25bf) | Jun 29, 2023 |
| Google        | Reef                        | [221e64e148](https://linux-hardware.org/?probe=221e64e148) | Jun 29, 2023 |
| HP            | ProBook 450 G2              | [2b47aff042](https://linux-hardware.org/?probe=2b47aff042) | Jun 28, 2023 |
| Lenovo        | ThinkPad X240 20AL007LUK    | [ee0761a131](https://linux-hardware.org/?probe=ee0761a131) | Jun 28, 2023 |
| Lenovo        | Z70-80 80FG                 | [d4b8002633](https://linux-hardware.org/?probe=d4b8002633) | Jun 28, 2023 |
| HP            | ProBook 450 G2              | [dc758ef355](https://linux-hardware.org/?probe=dc758ef355) | Jun 28, 2023 |
| MSI           | GE70 2PL                    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [9128946047](https://linux-hardware.org/?probe=9128946047) | Jun 27, 2023 |
| HP            | EliteBook 8440p             | [3d2a2196ae](https://linux-hardware.org/?probe=3d2a2196ae) | Jun 27, 2023 |
| Valve         | Jupiter                     | [f6d3a1e787](https://linux-hardware.org/?probe=f6d3a1e787) | Jun 27, 2023 |
| Dell          | Precision M6800             | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | [5e6365efcf](https://linux-hardware.org/?probe=5e6365efcf) | Jun 27, 2023 |
| Acer          | Aspire A317-53              | [88baca047c](https://linux-hardware.org/?probe=88baca047c) | Jun 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [699aa2d6e1](https://linux-hardware.org/?probe=699aa2d6e1) | Jun 26, 2023 |
| Apple         | MacBook4,1                  | [fe27e643ac](https://linux-hardware.org/?probe=fe27e643ac) | Jun 26, 2023 |
| HP            | Unknown                     | [d681765bb7](https://linux-hardware.org/?probe=d681765bb7) | Jun 26, 2023 |
| Dell          | Precision M6800             | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| Acer          | Aspire A317-53              | [1fe3acdf83](https://linux-hardware.org/?probe=1fe3acdf83) | Jun 25, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [75f62d2200](https://linux-hardware.org/?probe=75f62d2200) | Jun 24, 2023 |
| Toshiba       | Satellite C650              | [54ef5b6567](https://linux-hardware.org/?probe=54ef5b6567) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [3cc7c77a76](https://linux-hardware.org/?probe=3cc7c77a76) | Jun 23, 2023 |
| HP            | 8470p EliteBook             | [da3719515b](https://linux-hardware.org/?probe=da3719515b) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [b5576af3f8](https://linux-hardware.org/?probe=b5576af3f8) | Jun 23, 2023 |
| Lenovo        | Flex 2-14 20404             | [911336b572](https://linux-hardware.org/?probe=911336b572) | Jun 23, 2023 |
| ASUSTek       | TP550LA                     | [7728203a8a](https://linux-hardware.org/?probe=7728203a8a) | Jun 22, 2023 |
| ASUSTek       | TP550LA                     | [fed72172d2](https://linux-hardware.org/?probe=fed72172d2) | Jun 22, 2023 |
| Medion        | Erazer P6661 MD60303        | [22fb03fe41](https://linux-hardware.org/?probe=22fb03fe41) | Jun 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | [f1e506486c](https://linux-hardware.org/?probe=f1e506486c) | Jun 21, 2023 |
| Acer          | Aspire 5742Z                | [d1513c944e](https://linux-hardware.org/?probe=d1513c944e) | Jun 21, 2023 |
| HP            | Unknown                     | [4f27a83f9e](https://linux-hardware.org/?probe=4f27a83f9e) | Jun 21, 2023 |
| Dell          | Latitude E7450              | [4760bb7306](https://linux-hardware.org/?probe=4760bb7306) | Jun 20, 2023 |
| Dell          | XPS 13 9380                 | [fa33088329](https://linux-hardware.org/?probe=fa33088329) | Jun 20, 2023 |
| Alienware     | 17 R3                       | [45613f348f](https://linux-hardware.org/?probe=45613f348f) | Jun 20, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [53b1d3f262](https://linux-hardware.org/?probe=53b1d3f262) | Jun 20, 2023 |
| Dell          | Latitude 7390               | [98d09ed56c](https://linux-hardware.org/?probe=98d09ed56c) | Jun 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [9726121d1b](https://linux-hardware.org/?probe=9726121d1b) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [c5c0838f41](https://linux-hardware.org/?probe=c5c0838f41) | Jun 18, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [e6e1708182](https://linux-hardware.org/?probe=e6e1708182) | Jun 18, 2023 |
| HP            | EliteBook 840 14 inch G9... | [0875b8b413](https://linux-hardware.org/?probe=0875b8b413) | Jun 18, 2023 |
| Dell          | Latitude 5430               | [1797038bf6](https://linux-hardware.org/?probe=1797038bf6) | Jun 17, 2023 |
| HP            | ENVY m6                     | [2776e20c0a](https://linux-hardware.org/?probe=2776e20c0a) | Jun 17, 2023 |
| HP            | Laptop 14s-fq1xxx           | [1b0dd608b2](https://linux-hardware.org/?probe=1b0dd608b2) | Jun 16, 2023 |
| GEO           | GEOBOOK 2E                  | [9ab9fe3052](https://linux-hardware.org/?probe=9ab9fe3052) | Jun 16, 2023 |
| HUAWEI        | NBD-WXX9                    | [b9bf7ea3c2](https://linux-hardware.org/?probe=b9bf7ea3c2) | Jun 16, 2023 |
| Acer          | Aspire ES1-522              | [25f52202b2](https://linux-hardware.org/?probe=25f52202b2) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [89ac5ef04b](https://linux-hardware.org/?probe=89ac5ef04b) | Jun 15, 2023 |
| HUAWEI        | NBD-WXX9                    | [b55662cc58](https://linux-hardware.org/?probe=b55662cc58) | Jun 15, 2023 |
| Apple         | MacBookPro12,1              | [b8d24f1cc8](https://linux-hardware.org/?probe=b8d24f1cc8) | Jun 15, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [3dd5692b24](https://linux-hardware.org/?probe=3dd5692b24) | Jun 15, 2023 |
| HP            | Unknown                     | [00c49ad567](https://linux-hardware.org/?probe=00c49ad567) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [9b67ef406b](https://linux-hardware.org/?probe=9b67ef406b) | Jun 14, 2023 |
| Google        | Ampton                      | [294fa26d20](https://linux-hardware.org/?probe=294fa26d20) | Jun 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [b1eabf98f6](https://linux-hardware.org/?probe=b1eabf98f6) | Jun 14, 2023 |
| PC Special... | P65_P67RGRERA               | [49773a4767](https://linux-hardware.org/?probe=49773a4767) | Jun 14, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [448deb90fa](https://linux-hardware.org/?probe=448deb90fa) | Jun 14, 2023 |
| Dell          | Inspiron 5548               | [e7f84bdb10](https://linux-hardware.org/?probe=e7f84bdb10) | Jun 14, 2023 |
| Dell          | Inspiron 5548               | [7b3593a797](https://linux-hardware.org/?probe=7b3593a797) | Jun 13, 2023 |
| Lenovo        | IdeaPad Y580                | [699cb9ac1e](https://linux-hardware.org/?probe=699cb9ac1e) | Jun 13, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [6dadff138b](https://linux-hardware.org/?probe=6dadff138b) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Dell          | Vostro 3550                 | [3d8862fe69](https://linux-hardware.org/?probe=3d8862fe69) | Jun 13, 2023 |
| Dell          | Latitude 5411               | [c0292655dd](https://linux-hardware.org/?probe=c0292655dd) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [f47c4b27fe](https://linux-hardware.org/?probe=f47c4b27fe) | Jun 13, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [40d06bae85](https://linux-hardware.org/?probe=40d06bae85) | Jun 12, 2023 |
| HP            | EliteBook 840 G5            | [331ac1da01](https://linux-hardware.org/?probe=331ac1da01) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | [4c5907abd5](https://linux-hardware.org/?probe=4c5907abd5) | Jun 12, 2023 |
| Timi          | RedmiBook Pro 14            | [7b2e093b24](https://linux-hardware.org/?probe=7b2e093b24) | Jun 12, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [0b42de0b42](https://linux-hardware.org/?probe=0b42de0b42) | Jun 12, 2023 |
| Dell          | Inspiron 3501               | [8e9562dd9a](https://linux-hardware.org/?probe=8e9562dd9a) | Jun 11, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [5286f937d8](https://linux-hardware.org/?probe=5286f937d8) | Jun 11, 2023 |
| Valve         | Jupiter                     | [b7ffc34483](https://linux-hardware.org/?probe=b7ffc34483) | Jun 11, 2023 |
| Acer          | Aspire F5-571               | [e54e3157fc](https://linux-hardware.org/?probe=e54e3157fc) | Jun 11, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | [777f28f9e8](https://linux-hardware.org/?probe=777f28f9e8) | Jun 11, 2023 |
| Acer          | Aspire A317-53              | [36f0bbcb6d](https://linux-hardware.org/?probe=36f0bbcb6d) | Jun 11, 2023 |
| HP            | Pavilion g6                 | [7eda1ce433](https://linux-hardware.org/?probe=7eda1ce433) | Jun 11, 2023 |
| HP            | Pavilion g6                 | [4fcc967374](https://linux-hardware.org/?probe=4fcc967374) | Jun 11, 2023 |
| Lenovo        | ThinkPad W500 4058CTO       | [4b6aa9a912](https://linux-hardware.org/?probe=4b6aa9a912) | Jun 10, 2023 |
| HP            | ProBook 4510s               | [43a29ea83e](https://linux-hardware.org/?probe=43a29ea83e) | Jun 09, 2023 |
| Dell          | XPS 13 9333                 | [88020aee75](https://linux-hardware.org/?probe=88020aee75) | Jun 09, 2023 |
| Dell          | Inspiron 3583               | [adcb3b193a](https://linux-hardware.org/?probe=adcb3b193a) | Jun 09, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [50c36acc0d](https://linux-hardware.org/?probe=50c36acc0d) | Jun 09, 2023 |
| Lenovo        | Z50-70 20354                | [28a5b69096](https://linux-hardware.org/?probe=28a5b69096) | Jun 08, 2023 |
| PC Special... | Initia Ii 15                | [36a16c2890](https://linux-hardware.org/?probe=36a16c2890) | Jun 08, 2023 |
| HONOR         | NBR-WAX9                    | [697f2b18e8](https://linux-hardware.org/?probe=697f2b18e8) | Jun 08, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [4614addc21](https://linux-hardware.org/?probe=4614addc21) | Jun 08, 2023 |
| Acer          | Aspire A317-53              | [62418abec4](https://linux-hardware.org/?probe=62418abec4) | Jun 08, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | [340054cdd5](https://linux-hardware.org/?probe=340054cdd5) | Jun 08, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [73fa9d854f](https://linux-hardware.org/?probe=73fa9d854f) | Jun 07, 2023 |
| Dell          | XPS 9320                    | [ff5fc17acc](https://linux-hardware.org/?probe=ff5fc17acc) | Jun 07, 2023 |
| Valve         | Jupiter                     | [27771c5ea8](https://linux-hardware.org/?probe=27771c5ea8) | Jun 07, 2023 |
| Lenovo        | ThinkPad X61 7674GS3        | [629a290a98](https://linux-hardware.org/?probe=629a290a98) | Jun 07, 2023 |
| Sony          | VPCEH3N6E                   | [788ddd35a8](https://linux-hardware.org/?probe=788ddd35a8) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e4335c33f6](https://linux-hardware.org/?probe=e4335c33f6) | Jun 06, 2023 |
| Valve         | Jupiter                     | [99a7a5bd6e](https://linux-hardware.org/?probe=99a7a5bd6e) | Jun 06, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [413ef09459](https://linux-hardware.org/?probe=413ef09459) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | [78459738e9](https://linux-hardware.org/?probe=78459738e9) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [b969b91080](https://linux-hardware.org/?probe=b969b91080) | Jun 05, 2023 |
| Acer          | Aspire A317-53              | [693fdb51d3](https://linux-hardware.org/?probe=693fdb51d3) | Jun 05, 2023 |
| Dell          | Latitude E5250              | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Apple         | MacBookPro8,1               | [e3f89d1faa](https://linux-hardware.org/?probe=e3f89d1faa) | Jun 04, 2023 |
| MSI           | Katana GF66 11UG            | [d50f02e996](https://linux-hardware.org/?probe=d50f02e996) | Jun 04, 2023 |
| HP            | Compaq Presario CQ60        | [5716ed966d](https://linux-hardware.org/?probe=5716ed966d) | Jun 04, 2023 |
| HP            | Compaq Presario CQ60        | [a3d127e3ba](https://linux-hardware.org/?probe=a3d127e3ba) | Jun 04, 2023 |
| Dell          | Latitude E5520              | [7e2d1fdd22](https://linux-hardware.org/?probe=7e2d1fdd22) | Jun 04, 2023 |
| Apple         | MacBookPro12,1              | [fc6e3f084f](https://linux-hardware.org/?probe=fc6e3f084f) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | [f39742476c](https://linux-hardware.org/?probe=f39742476c) | Jun 04, 2023 |
| Acer          | Swift SF314-512             | [efa49bf468](https://linux-hardware.org/?probe=efa49bf468) | Jun 04, 2023 |
| Dell          | Latitude 5420               | [9085f3c8f7](https://linux-hardware.org/?probe=9085f3c8f7) | Jun 04, 2023 |
| Apple         | MacBookPro12,1              | [a9c6f5e0e6](https://linux-hardware.org/?probe=a9c6f5e0e6) | Jun 04, 2023 |
| HP            | Notebook                    | [45553d6493](https://linux-hardware.org/?probe=45553d6493) | Jun 04, 2023 |
| Acer          | Aspire A317-53              | [406fc17c32](https://linux-hardware.org/?probe=406fc17c32) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| Fujitsu Si... | LIFEBOOK S7110              | [9161ac00ce](https://linux-hardware.org/?probe=9161ac00ce) | Jun 04, 2023 |
| HP            | Pavilion 15                 | [dc8f67bb03](https://linux-hardware.org/?probe=dc8f67bb03) | Jun 03, 2023 |
| Apple         | MacBookPro8,1               | [7bdff81d7d](https://linux-hardware.org/?probe=7bdff81d7d) | Jun 03, 2023 |
| Valve         | Jupiter                     | [e7409e91d9](https://linux-hardware.org/?probe=e7409e91d9) | Jun 03, 2023 |
| Sony          | SVF1521A1EW                 | [4e3fe0308e](https://linux-hardware.org/?probe=4e3fe0308e) | Jun 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [1b82c0c3c8](https://linux-hardware.org/?probe=1b82c0c3c8) | Jun 02, 2023 |
| Lenovo        | ThinkPad X61 7674GS3        | [194299200c](https://linux-hardware.org/?probe=194299200c) | Jun 01, 2023 |
| Toshiba       | Satellite C50-B             | [1a6c37d8f7](https://linux-hardware.org/?probe=1a6c37d8f7) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | [f3dc10c852](https://linux-hardware.org/?probe=f3dc10c852) | Jun 01, 2023 |
| Toshiba       | TECRA Z40t-C                | [1d128e6153](https://linux-hardware.org/?probe=1d128e6153) | Jun 01, 2023 |
| HP            | EliteBook 2560p             | [e822eb4072](https://linux-hardware.org/?probe=e822eb4072) | Jun 01, 2023 |
| Dell          | Inspiron 5558               | [5f63504f03](https://linux-hardware.org/?probe=5f63504f03) | May 31, 2023 |
| Dell          | Inspiron 5593               | [ac6f421fef](https://linux-hardware.org/?probe=ac6f421fef) | May 31, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [8092b65afc](https://linux-hardware.org/?probe=8092b65afc) | May 31, 2023 |
| Acer          | Aspire ES1-512              | [3c6e8b6acd](https://linux-hardware.org/?probe=3c6e8b6acd) | May 29, 2023 |
| Acer          | Aspire A317-53              | [bca463af6d](https://linux-hardware.org/?probe=bca463af6d) | May 28, 2023 |
| Valve         | Jupiter                     | [66bff91fdb](https://linux-hardware.org/?probe=66bff91fdb) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| Acer          | Aspire E5-575               | [cdc924595c](https://linux-hardware.org/?probe=cdc924595c) | May 28, 2023 |
| Dell          | Latitude D630               | [ead768adbd](https://linux-hardware.org/?probe=ead768adbd) | May 27, 2023 |
| ASUSTek       | X550CA                      | [3ad8935a92](https://linux-hardware.org/?probe=3ad8935a92) | May 27, 2023 |
| Apple         | MacBookPro15,4              | [9ee2d1266b](https://linux-hardware.org/?probe=9ee2d1266b) | May 27, 2023 |
| Dell          | Inspiron 3505               | [ce0ecf0cce](https://linux-hardware.org/?probe=ce0ecf0cce) | May 27, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JU... | [0696598319](https://linux-hardware.org/?probe=0696598319) | May 26, 2023 |
| HP            | ENVY Laptop 13-ah0503na     | [cdf2d7b4b4](https://linux-hardware.org/?probe=cdf2d7b4b4) | May 25, 2023 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [a88cd7c5a6](https://linux-hardware.org/?probe=a88cd7c5a6) | May 25, 2023 |
| Dell          | XPS 15 9560                 | [7389c979b6](https://linux-hardware.org/?probe=7389c979b6) | May 25, 2023 |
| Dell          | Latitude 5521               | [b33afe1463](https://linux-hardware.org/?probe=b33afe1463) | May 25, 2023 |
| Dell          | Latitude 5290 2-in-1        | [6607361205](https://linux-hardware.org/?probe=6607361205) | May 25, 2023 |
| Dell          | Latitude 5290 2-in-1        | [4bbba2e730](https://linux-hardware.org/?probe=4bbba2e730) | May 25, 2023 |
| Dell          | Latitude 7390               | [999bb94a31](https://linux-hardware.org/?probe=999bb94a31) | May 24, 2023 |
| Lenovo        | ThinkPad T431s 20ACA01V0... | [253f7d5359](https://linux-hardware.org/?probe=253f7d5359) | May 24, 2023 |
| Lenovo        | ThinkPad W530 24472BG       | [6431c2bb45](https://linux-hardware.org/?probe=6431c2bb45) | May 24, 2023 |
| Lenovo        | ThinkPad T470s 20HGS4RU0... | [ac8df81694](https://linux-hardware.org/?probe=ac8df81694) | May 23, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [2cf9c98869](https://linux-hardware.org/?probe=2cf9c98869) | May 23, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D2C... | [4da667cc7e](https://linux-hardware.org/?probe=4da667cc7e) | May 23, 2023 |
| HP            | Notebook                    | [6e7c128799](https://linux-hardware.org/?probe=6e7c128799) | May 23, 2023 |
| Lenovo        | ThinkPad L440 20AS001CUK    | [8d253e2d7e](https://linux-hardware.org/?probe=8d253e2d7e) | May 22, 2023 |
| Acer          | Aspire A317-53              | [185b65bf34](https://linux-hardware.org/?probe=185b65bf34) | May 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [5e89fe1dc9](https://linux-hardware.org/?probe=5e89fe1dc9) | May 22, 2023 |
| Unknown       | Unknown                     | [2b3ef0afc4](https://linux-hardware.org/?probe=2b3ef0afc4) | May 22, 2023 |
| Valve         | Jupiter                     | [c7f1f9d62a](https://linux-hardware.org/?probe=c7f1f9d62a) | May 22, 2023 |
| HP            | Pavilion 15                 | [548626d011](https://linux-hardware.org/?probe=548626d011) | May 21, 2023 |
| HP            | Pavilion 15                 | [05f3c4f274](https://linux-hardware.org/?probe=05f3c4f274) | May 21, 2023 |
| Apple         | MacBook4,1                  | [d404dc5e03](https://linux-hardware.org/?probe=d404dc5e03) | May 21, 2023 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | [5a30bf445a](https://linux-hardware.org/?probe=5a30bf445a) | May 21, 2023 |
| ASUSTek       | X705UDR                     | [e1f2bf110a](https://linux-hardware.org/?probe=e1f2bf110a) | May 20, 2023 |
| Dell          | Latitude 7280               | [9b98a88e3d](https://linux-hardware.org/?probe=9b98a88e3d) | May 19, 2023 |
| Apple         | MacBookPro15,2              | [d52cf51575](https://linux-hardware.org/?probe=d52cf51575) | May 19, 2023 |
| Eii           | WSA116                      | [cff66832fd](https://linux-hardware.org/?probe=cff66832fd) | May 19, 2023 |
| Lenovo        | ThinkPad X240 20AMA21D00    | [a692a56bc0](https://linux-hardware.org/?probe=a692a56bc0) | May 19, 2023 |
| Advent        | Roma                        | [f6ca4c331a](https://linux-hardware.org/?probe=f6ca4c331a) | May 19, 2023 |
| Dell          | XPS 15 9550                 | [c2f9737977](https://linux-hardware.org/?probe=c2f9737977) | May 19, 2023 |
| Entroware     | Kratos                      | [ecf875b8e5](https://linux-hardware.org/?probe=ecf875b8e5) | May 18, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [7c4f12c4ed](https://linux-hardware.org/?probe=7c4f12c4ed) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Toshiba       | Satellite Pro C50-A-1E6     | [3c8dcfcf15](https://linux-hardware.org/?probe=3c8dcfcf15) | May 18, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [ba813a3367](https://linux-hardware.org/?probe=ba813a3367) | May 18, 2023 |
| Acer          | Aspire A514-55              | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| Apple         | MacBookPro11,1              | [d23967583a](https://linux-hardware.org/?probe=d23967583a) | May 18, 2023 |
| HP            | EliteBook 8770w             | [d4884bd764](https://linux-hardware.org/?probe=d4884bd764) | May 17, 2023 |
| HP            | Laptop 15s-fq4xxx           | [c6d11a2f8e](https://linux-hardware.org/?probe=c6d11a2f8e) | May 17, 2023 |
| Google        | Samus                       | [d627862e56](https://linux-hardware.org/?probe=d627862e56) | May 16, 2023 |
| eMachines     | E625                        | [8638b2b8c8](https://linux-hardware.org/?probe=8638b2b8c8) | May 15, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | [1bf9f3a0df](https://linux-hardware.org/?probe=1bf9f3a0df) | May 15, 2023 |
| Acer          | Extensa 215-52              | [83f139d228](https://linux-hardware.org/?probe=83f139d228) | May 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | [98ebdcd589](https://linux-hardware.org/?probe=98ebdcd589) | May 15, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [4b1b35b4ec](https://linux-hardware.org/?probe=4b1b35b4ec) | May 15, 2023 |
| Dell          | Inspiron 5405               | [9d3ae56a5e](https://linux-hardware.org/?probe=9d3ae56a5e) | May 15, 2023 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cd0a78ce39](https://linux-hardware.org/?probe=cd0a78ce39) | May 14, 2023 |
| Lenovo        | ThinkPad T480 20L6A0XKUK    | [8921a6d64e](https://linux-hardware.org/?probe=8921a6d64e) | May 14, 2023 |
| Valve         | Jupiter                     | [6df9aa02d5](https://linux-hardware.org/?probe=6df9aa02d5) | May 14, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [162219b0fe](https://linux-hardware.org/?probe=162219b0fe) | May 14, 2023 |
| ASUSTek       | X510UQR                     | [2062004d5f](https://linux-hardware.org/?probe=2062004d5f) | May 14, 2023 |
| HP            | Pavilion dv6                | [46e74189f2](https://linux-hardware.org/?probe=46e74189f2) | May 13, 2023 |
| PC Special... | P65_67RSRP                  | [892b6d56c8](https://linux-hardware.org/?probe=892b6d56c8) | May 13, 2023 |
| Dell          | G7 7700                     | [6568ba5b4d](https://linux-hardware.org/?probe=6568ba5b4d) | May 13, 2023 |
| ASUSTek       | X580VD                      | [971b7bfcd1](https://linux-hardware.org/?probe=971b7bfcd1) | May 12, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [8bad0045f6](https://linux-hardware.org/?probe=8bad0045f6) | May 12, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [78e2c8b948](https://linux-hardware.org/?probe=78e2c8b948) | May 12, 2023 |
| Valve         | Jupiter                     | [01ee28074b](https://linux-hardware.org/?probe=01ee28074b) | May 12, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [f9c1eb381f](https://linux-hardware.org/?probe=f9c1eb381f) | May 11, 2023 |
| Toshiba       | Satellite C75-A             | [5be756cc91](https://linux-hardware.org/?probe=5be756cc91) | May 11, 2023 |
| Acer          | Swift SFX14-51G             | [e18646482f](https://linux-hardware.org/?probe=e18646482f) | May 11, 2023 |
| Dell          | Latitude 7390               | [ab2ea4f7a0](https://linux-hardware.org/?probe=ab2ea4f7a0) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [a7155be531](https://linux-hardware.org/?probe=a7155be531) | May 11, 2023 |
| HP            | Pavilion dv7                | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| Acer          | Aspire E3-111               | [1060697095](https://linux-hardware.org/?probe=1060697095) | May 10, 2023 |
| Lenovo        | ThinkPad T450s 20BWS34A0... | [775c2839fa](https://linux-hardware.org/?probe=775c2839fa) | May 10, 2023 |
| Dell          | Latitude 5420               | [2f3519c123](https://linux-hardware.org/?probe=2f3519c123) | May 09, 2023 |
| Sony          | SVT1312B4E                  | [dc0f581bc3](https://linux-hardware.org/?probe=dc0f581bc3) | May 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0628913a60](https://linux-hardware.org/?probe=0628913a60) | May 08, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [6e086ec096](https://linux-hardware.org/?probe=6e086ec096) | May 07, 2023 |
| Google        | Auron_Yuna                  | [cbd0938f3c](https://linux-hardware.org/?probe=cbd0938f3c) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | [30bd232e19](https://linux-hardware.org/?probe=30bd232e19) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | [923397bc88](https://linux-hardware.org/?probe=923397bc88) | May 07, 2023 |
| Lenovo        | V110-15IKB 80TH             | [a908ca11db](https://linux-hardware.org/?probe=a908ca11db) | May 07, 2023 |
| HP            | x2 210                      | [f60c4cb29b](https://linux-hardware.org/?probe=f60c4cb29b) | May 07, 2023 |
| HP            | x2 210                      | [f7a174063f](https://linux-hardware.org/?probe=f7a174063f) | May 07, 2023 |
| HP            | x2 210                      | [b3c5b71d27](https://linux-hardware.org/?probe=b3c5b71d27) | May 07, 2023 |
| Dell          | Latitude E7440              | [e49cf2551c](https://linux-hardware.org/?probe=e49cf2551c) | May 07, 2023 |
| Lenovo        | G50-80 80L0                 | [af42781d8a](https://linux-hardware.org/?probe=af42781d8a) | May 06, 2023 |
| Dell          | Studio 1749                 | [43eb37cfd7](https://linux-hardware.org/?probe=43eb37cfd7) | May 06, 2023 |
| Dell          | Latitude E4200              | [af2baa1787](https://linux-hardware.org/?probe=af2baa1787) | May 06, 2023 |
| Google        | Samus                       | [aed9bd140f](https://linux-hardware.org/?probe=aed9bd140f) | May 06, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [a7ef6c976c](https://linux-hardware.org/?probe=a7ef6c976c) | May 06, 2023 |
| Dell          | XPS 15 9560                 | [644110c9b9](https://linux-hardware.org/?probe=644110c9b9) | May 06, 2023 |
| MSI           | GS43VR 7RE                  | [4eb5973faa](https://linux-hardware.org/?probe=4eb5973faa) | May 06, 2023 |
| HP            | Laptop 17-ca1xxx            | [5c506f94e0](https://linux-hardware.org/?probe=5c506f94e0) | May 05, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | [db330cab38](https://linux-hardware.org/?probe=db330cab38) | May 05, 2023 |
| Dell          | Inspiron 3505               | [8e19b0629d](https://linux-hardware.org/?probe=8e19b0629d) | May 05, 2023 |
| Dell          | Latitude 5400               | [f7f8025263](https://linux-hardware.org/?probe=f7f8025263) | May 05, 2023 |
| Medion        | Akoya E1317T                | [e8eb05a52a](https://linux-hardware.org/?probe=e8eb05a52a) | May 05, 2023 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [624e1c3f06](https://linux-hardware.org/?probe=624e1c3f06) | May 05, 2023 |
| Acer          | Extensa 215-52              | [d4d069aa0c](https://linux-hardware.org/?probe=d4d069aa0c) | May 04, 2023 |
| Google        | Samus                       | [a7dfa29233](https://linux-hardware.org/?probe=a7dfa29233) | May 04, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [c20844716d](https://linux-hardware.org/?probe=c20844716d) | May 03, 2023 |
| HP            | EliteBook 840 G3            | [f87b1ac774](https://linux-hardware.org/?probe=f87b1ac774) | May 03, 2023 |
| HP            | EliteBook 840 G3            | [d8b268f8f7](https://linux-hardware.org/?probe=d8b268f8f7) | May 03, 2023 |
| MSI           | CX62 6QD                    | [9c6b781beb](https://linux-hardware.org/?probe=9c6b781beb) | May 02, 2023 |
| Valve         | Jupiter                     | [388caab99a](https://linux-hardware.org/?probe=388caab99a) | May 02, 2023 |
| Acer          | Aspire A317-53              | [612ab58d3f](https://linux-hardware.org/?probe=612ab58d3f) | May 02, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [26bb61d72f](https://linux-hardware.org/?probe=26bb61d72f) | May 02, 2023 |
| Toshiba       | PORTEGE Z30-A               | [ccc620956f](https://linux-hardware.org/?probe=ccc620956f) | May 02, 2023 |
| Advent        | Roma                        | [ec7568545d](https://linux-hardware.org/?probe=ec7568545d) | May 02, 2023 |
| ASUSTek       | X401A1                      | [2a7d35cc4e](https://linux-hardware.org/?probe=2a7d35cc4e) | May 01, 2023 |
| HP            | ProBook 430 G4              | [3c422c5e96](https://linux-hardware.org/?probe=3c422c5e96) | May 01, 2023 |
| lapbook       | S15 PRO                     | [d4b7c4a4db](https://linux-hardware.org/?probe=d4b7c4a4db) | May 01, 2023 |
| Dell          | Precision 5530              | [c8878b0f0f](https://linux-hardware.org/?probe=c8878b0f0f) | May 01, 2023 |
| HP            | EliteBook 8470p             | [f75b4a9457](https://linux-hardware.org/?probe=f75b4a9457) | May 01, 2023 |
| Toshiba       | EQUIUM P200                 | [812a164a8a](https://linux-hardware.org/?probe=812a164a8a) | Apr 30, 2023 |
| Lenovo        | ThinkPad X230 2325V1K       | [d630569df9](https://linux-hardware.org/?probe=d630569df9) | Apr 30, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [dff6f75899](https://linux-hardware.org/?probe=dff6f75899) | Apr 30, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [da5f050510](https://linux-hardware.org/?probe=da5f050510) | Apr 29, 2023 |
| Lenovo        | ThinkPad E580 20KS001JUK    | [1e65b46a12](https://linux-hardware.org/?probe=1e65b46a12) | Apr 29, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f2ad30321e](https://linux-hardware.org/?probe=f2ad30321e) | Apr 29, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [58bb30861d](https://linux-hardware.org/?probe=58bb30861d) | Apr 29, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [e70d66b3ba](https://linux-hardware.org/?probe=e70d66b3ba) | Apr 29, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [d364cb5ac7](https://linux-hardware.org/?probe=d364cb5ac7) | Apr 28, 2023 |
| HP            | ENVY Notebook               | [89e8149d6e](https://linux-hardware.org/?probe=89e8149d6e) | Apr 28, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [2dc65d8f07](https://linux-hardware.org/?probe=2dc65d8f07) | Apr 28, 2023 |
| Dell          | XPS 13 9350                 | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [6569669912](https://linux-hardware.org/?probe=6569669912) | Apr 28, 2023 |
| Dell          | Latitude E7450              | [6afa2ff009](https://linux-hardware.org/?probe=6afa2ff009) | Apr 28, 2023 |
| Valve         | Jupiter                     | [0958caf898](https://linux-hardware.org/?probe=0958caf898) | Apr 27, 2023 |
| Lenovo        | Legion 7-16-ITHg6 82K6      | [2baf2cbc85](https://linux-hardware.org/?probe=2baf2cbc85) | Apr 27, 2023 |
| Lenovo        | ThinkPad X230 2325O32       | [b38ef1a717](https://linux-hardware.org/?probe=b38ef1a717) | Apr 27, 2023 |
| Acer          | Nitro AN515-57              | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [e35780d356](https://linux-hardware.org/?probe=e35780d356) | Apr 26, 2023 |
| Acer          | Aspire A514-54              | [19ca73662f](https://linux-hardware.org/?probe=19ca73662f) | Apr 25, 2023 |
| Google        | Sasuke                      | [7615a1b1e5](https://linux-hardware.org/?probe=7615a1b1e5) | Apr 25, 2023 |
| Dell          | XPS 13 9380                 | [290a99fee9](https://linux-hardware.org/?probe=290a99fee9) | Apr 25, 2023 |
| HP            | ProBook 640 G1              | [9306db1f90](https://linux-hardware.org/?probe=9306db1f90) | Apr 25, 2023 |
| Dell          | Latitude XT2                | [62df7dc069](https://linux-hardware.org/?probe=62df7dc069) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Apple         | MacBookPro5,5               | [de825a326c](https://linux-hardware.org/?probe=de825a326c) | Apr 24, 2023 |
| Acer          | Aspire A317-53              | [c47ec3530e](https://linux-hardware.org/?probe=c47ec3530e) | Apr 24, 2023 |
| HP            | Stream Notebook PC 13       | [455c6b5e28](https://linux-hardware.org/?probe=455c6b5e28) | Apr 23, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [982ca9079d](https://linux-hardware.org/?probe=982ca9079d) | Apr 23, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [25e942e55c](https://linux-hardware.org/?probe=25e942e55c) | Apr 22, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [fd2ad16b59](https://linux-hardware.org/?probe=fd2ad16b59) | Apr 22, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [936e6fc768](https://linux-hardware.org/?probe=936e6fc768) | Apr 22, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e0763f0f69](https://linux-hardware.org/?probe=e0763f0f69) | Apr 22, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [a02462f614](https://linux-hardware.org/?probe=a02462f614) | Apr 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [dfbfce9d2e](https://linux-hardware.org/?probe=dfbfce9d2e) | Apr 21, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [66f95f2851](https://linux-hardware.org/?probe=66f95f2851) | Apr 21, 2023 |
| Google        | Swanky                      | [92156daf53](https://linux-hardware.org/?probe=92156daf53) | Apr 21, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [2afe988f2e](https://linux-hardware.org/?probe=2afe988f2e) | Apr 20, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [f8f6ec2123](https://linux-hardware.org/?probe=f8f6ec2123) | Apr 20, 2023 |
| ASUSTek       | X550CA                      | [cb5f73ff63](https://linux-hardware.org/?probe=cb5f73ff63) | Apr 20, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | [1ba852f185](https://linux-hardware.org/?probe=1ba852f185) | Apr 20, 2023 |
| Dell          | Inspiron 1545               | [68a7470480](https://linux-hardware.org/?probe=68a7470480) | Apr 19, 2023 |
| HP            | ProBook 4540s               | [1bf512ee24](https://linux-hardware.org/?probe=1bf512ee24) | Apr 19, 2023 |
| Toshiba       | Satellite Pro C850-1HE      | [48d3d92f3d](https://linux-hardware.org/?probe=48d3d92f3d) | Apr 19, 2023 |
| Dell          | Vostro 5471                 | [5cbbc95995](https://linux-hardware.org/?probe=5cbbc95995) | Apr 19, 2023 |
| Dell          | G5 5590                     | [c7334114be](https://linux-hardware.org/?probe=c7334114be) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| HP            | Laptop 15-da1xxx            | [c7a5aadd85](https://linux-hardware.org/?probe=c7a5aadd85) | Apr 18, 2023 |
| LG Electro... | 17Z90Q-K.AA78A1             | [594a7fa16b](https://linux-hardware.org/?probe=594a7fa16b) | Apr 18, 2023 |
| Sony          | SVF1521Q1EW                 | [4be523b9a9](https://linux-hardware.org/?probe=4be523b9a9) | Apr 18, 2023 |
| ASUSTek       | X550LD                      | [5c07d2203c](https://linux-hardware.org/?probe=5c07d2203c) | Apr 17, 2023 |
| Sony          | SVE1711C5E                  | [e4fbd8fca9](https://linux-hardware.org/?probe=e4fbd8fca9) | Apr 17, 2023 |
| Dell          | XPS 17 9700                 | [3ad1ee8197](https://linux-hardware.org/?probe=3ad1ee8197) | Apr 16, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [2092251807](https://linux-hardware.org/?probe=2092251807) | Apr 16, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9b05d61f11](https://linux-hardware.org/?probe=9b05d61f11) | Apr 16, 2023 |
| HP            | ProBook 450 G1              | [000e6c6702](https://linux-hardware.org/?probe=000e6c6702) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| HP            | 250 G4 Notebook PC          | [08036de728](https://linux-hardware.org/?probe=08036de728) | Apr 15, 2023 |
| Lenovo        | IdeaPad 1 14ADA05 82GW      | [2e860ef402](https://linux-hardware.org/?probe=2e860ef402) | Apr 15, 2023 |
| Acer          | Aspire A317-53              | [11b817e884](https://linux-hardware.org/?probe=11b817e884) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | Pavilion g6                 | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [19fc60d2a5](https://linux-hardware.org/?probe=19fc60d2a5) | Apr 14, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [f5940f5ed5](https://linux-hardware.org/?probe=f5940f5ed5) | Apr 14, 2023 |
| Dell          | XPS 15 7590                 | [f3248c9bca](https://linux-hardware.org/?probe=f3248c9bca) | Apr 14, 2023 |
| Clevo         | W760T/M740T/M760T           | [0dfaa8f0e8](https://linux-hardware.org/?probe=0dfaa8f0e8) | Apr 14, 2023 |
| Unknown       | Unknown                     | [7bd7802e04](https://linux-hardware.org/?probe=7bd7802e04) | Apr 14, 2023 |
| HUAWEI        | MRG-WXX                     | [56c255e5f0](https://linux-hardware.org/?probe=56c255e5f0) | Apr 14, 2023 |
| Lenovo        | Flex 2-14 20404             | [c76a516113](https://linux-hardware.org/?probe=c76a516113) | Apr 14, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [bd9c1c1e6d](https://linux-hardware.org/?probe=bd9c1c1e6d) | Apr 14, 2023 |
| HP            | Notebook                    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Unknown       | Unknown                     | [cfe1766d1a](https://linux-hardware.org/?probe=cfe1766d1a) | Apr 13, 2023 |
| Unknown       | Unknown                     | [7ff7c0642f](https://linux-hardware.org/?probe=7ff7c0642f) | Apr 13, 2023 |
| Acer          | Aspire A315-51              | [c3962286cb](https://linux-hardware.org/?probe=c3962286cb) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [aa571700ad](https://linux-hardware.org/?probe=aa571700ad) | Apr 13, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | [9ac01d9237](https://linux-hardware.org/?probe=9ac01d9237) | Apr 13, 2023 |
| Apple         | MacBookPro5,5               | [401c4d8143](https://linux-hardware.org/?probe=401c4d8143) | Apr 12, 2023 |
| Sony          | SVE1711C5E                  | [07c6f843fb](https://linux-hardware.org/?probe=07c6f843fb) | Apr 12, 2023 |
| Toshiba       | Satellite C660              | [551fabbc17](https://linux-hardware.org/?probe=551fabbc17) | Apr 12, 2023 |
| Dell          | XPS 13 9305                 | [48b143cc2f](https://linux-hardware.org/?probe=48b143cc2f) | Apr 12, 2023 |
| Google        | Gnawty                      | [ddb0fea339](https://linux-hardware.org/?probe=ddb0fea339) | Apr 12, 2023 |
| Dell          | Latitude E5450              | [f98cdf4da0](https://linux-hardware.org/?probe=f98cdf4da0) | Apr 11, 2023 |
| Dell          | Latitude E5450              | [7bf04cdb7d](https://linux-hardware.org/?probe=7bf04cdb7d) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | [8297ce2712](https://linux-hardware.org/?probe=8297ce2712) | Apr 11, 2023 |
| MSI           | Stealth 14Studio A13VF      | [e3fc8c8f43](https://linux-hardware.org/?probe=e3fc8c8f43) | Apr 11, 2023 |
| Gigabyte      | MMLP3AP-00                  | [6fd82ceaec](https://linux-hardware.org/?probe=6fd82ceaec) | Apr 09, 2023 |
| lapbook       | S15 PRO                     | [5a039fc6fb](https://linux-hardware.org/?probe=5a039fc6fb) | Apr 09, 2023 |
| Lenovo        | ThinkPad T61 7661WQQ        | [8def87668b](https://linux-hardware.org/?probe=8def87668b) | Apr 09, 2023 |
| HP            | EliteBook 2560p             | [bc5cbcd2cb](https://linux-hardware.org/?probe=bc5cbcd2cb) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L50000UK    | [9f2644807d](https://linux-hardware.org/?probe=9f2644807d) | Apr 09, 2023 |
| Dell          | Inspiron 7570               | [2bac711aba](https://linux-hardware.org/?probe=2bac711aba) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | [7dc7e5e5c3](https://linux-hardware.org/?probe=7dc7e5e5c3) | Apr 09, 2023 |
| Acer          | Aspire A317-53              | [b1c4404d58](https://linux-hardware.org/?probe=b1c4404d58) | Apr 09, 2023 |
| Google        | Ampton                      | [e3945d7727](https://linux-hardware.org/?probe=e3945d7727) | Apr 08, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [14a3d5f4be](https://linux-hardware.org/?probe=14a3d5f4be) | Apr 08, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [5cf4615347](https://linux-hardware.org/?probe=5cf4615347) | Apr 08, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [aab830c5dd](https://linux-hardware.org/?probe=aab830c5dd) | Apr 07, 2023 |
| Google        | Bluebird                    | [6ab22238ac](https://linux-hardware.org/?probe=6ab22238ac) | Apr 07, 2023 |
| Apple         | MacBookPro13,3              | [77c6d48d6b](https://linux-hardware.org/?probe=77c6d48d6b) | Apr 06, 2023 |
| HP            | Laptop 15-db0xxx            | [e05bffcc8a](https://linux-hardware.org/?probe=e05bffcc8a) | Apr 06, 2023 |
| Apple         | MacBookPro14,1              | [e2b1578d42](https://linux-hardware.org/?probe=e2b1578d42) | Apr 06, 2023 |
| Apple         | MacBookPro14,1              | [2cd7831b58](https://linux-hardware.org/?probe=2cd7831b58) | Apr 06, 2023 |
| Google        | Bard                        | [cc1d159d0c](https://linux-hardware.org/?probe=cc1d159d0c) | Apr 05, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [8bf7c8a569](https://linux-hardware.org/?probe=8bf7c8a569) | Apr 05, 2023 |
| Dell          | Latitude E5550              | [5527315153](https://linux-hardware.org/?probe=5527315153) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [5549de9c5c](https://linux-hardware.org/?probe=5549de9c5c) | Apr 05, 2023 |
| Dell          | Latitude 5320               | [69e3bad969](https://linux-hardware.org/?probe=69e3bad969) | Apr 05, 2023 |
| Dell          | Latitude 5480               | [40ec4e3ec9](https://linux-hardware.org/?probe=40ec4e3ec9) | Apr 04, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [4e7cae1fde](https://linux-hardware.org/?probe=4e7cae1fde) | Apr 04, 2023 |
| Lenovo        | IdeaPad 330S-15AST 81F9     | [d79463ea93](https://linux-hardware.org/?probe=d79463ea93) | Apr 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [1af0b7675b](https://linux-hardware.org/?probe=1af0b7675b) | Apr 04, 2023 |
| Dell          | Studio 1558                 | [e9b75d657d](https://linux-hardware.org/?probe=e9b75d657d) | Apr 04, 2023 |
| Lenovo        | Brazos                      | [6415cb26c2](https://linux-hardware.org/?probe=6415cb26c2) | Apr 03, 2023 |
| Toshiba       | Satellite C650              | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d7f3280e60](https://linux-hardware.org/?probe=d7f3280e60) | Apr 03, 2023 |
| Advent        | Roma                        | [e1bd64e5b5](https://linux-hardware.org/?probe=e1bd64e5b5) | Apr 03, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [65cee818b6](https://linux-hardware.org/?probe=65cee818b6) | Apr 02, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [36c7cf7a43](https://linux-hardware.org/?probe=36c7cf7a43) | Apr 02, 2023 |
| Lenovo        | ThinkPad P51 W10DG 20MNS... | [c7791aac7c](https://linux-hardware.org/?probe=c7791aac7c) | Apr 02, 2023 |
| Lenovo        | ThinkPad T460p 20FXS08N0... | [ffcf174547](https://linux-hardware.org/?probe=ffcf174547) | Apr 02, 2023 |
| Lenovo        | Legion 5P 15ARH05H 82GU     | [3ec9fed32b](https://linux-hardware.org/?probe=3ec9fed32b) | Apr 02, 2023 |
| Apple         | MacBook4,1                  | [dda3791c20](https://linux-hardware.org/?probe=dda3791c20) | Apr 01, 2023 |
| Eii           | WSA116                      | [00bf1c190b](https://linux-hardware.org/?probe=00bf1c190b) | Apr 01, 2023 |
| ASUSTek       | U6Sg                        | [4fc2057b02](https://linux-hardware.org/?probe=4fc2057b02) | Apr 01, 2023 |
| ASUSTek       | U6Sg                        | [c97f807bb0](https://linux-hardware.org/?probe=c97f807bb0) | Apr 01, 2023 |
| HP            | Notebook                    | [348d80772f](https://linux-hardware.org/?probe=348d80772f) | Apr 01, 2023 |
| Acer          | Aspire A715-41G             | [cea0d2797d](https://linux-hardware.org/?probe=cea0d2797d) | Apr 01, 2023 |
| Samsung       | R530/R730/R540              | [714ed0f007](https://linux-hardware.org/?probe=714ed0f007) | Apr 01, 2023 |
| Acer          | Nitro AN517-54              | [82d28ac7c0](https://linux-hardware.org/?probe=82d28ac7c0) | Apr 01, 2023 |
| Valve         | Jupiter                     | [2628ea9d8e](https://linux-hardware.org/?probe=2628ea9d8e) | Apr 01, 2023 |
| Novatech      | NL40_50CU                   | [caaa544589](https://linux-hardware.org/?probe=caaa544589) | Apr 01, 2023 |
| Valve         | Jupiter                     | [d5e7a881e6](https://linux-hardware.org/?probe=d5e7a881e6) | Mar 31, 2023 |
| Valve         | Jupiter                     | [5b3718d617](https://linux-hardware.org/?probe=5b3718d617) | Mar 31, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [fe51f2c62f](https://linux-hardware.org/?probe=fe51f2c62f) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [31d333ecc9](https://linux-hardware.org/?probe=31d333ecc9) | Mar 30, 2023 |
| PC Special... | P65_67RSRP                  | [889f3e8521](https://linux-hardware.org/?probe=889f3e8521) | Mar 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [492d575f31](https://linux-hardware.org/?probe=492d575f31) | Mar 30, 2023 |
| Lenovo        | ThinkPad T400 6475J92       | [1d3c812668](https://linux-hardware.org/?probe=1d3c812668) | Mar 30, 2023 |
| OEGStone      | W54_55SU1,SUW               | [a771622660](https://linux-hardware.org/?probe=a771622660) | Mar 29, 2023 |
| OEGStone      | W54_55SU1,SUW               | [1e0c5a90c9](https://linux-hardware.org/?probe=1e0c5a90c9) | Mar 29, 2023 |
| HP            | Laptop 14-bs0xx             | [53504486d2](https://linux-hardware.org/?probe=53504486d2) | Mar 29, 2023 |
| HP            | Laptop 15s-fq4xxx           | [029fa06a9a](https://linux-hardware.org/?probe=029fa06a9a) | Mar 29, 2023 |
| Dell          | Inspiron 5767               | [1c80487906](https://linux-hardware.org/?probe=1c80487906) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [3f3b04c185](https://linux-hardware.org/?probe=3f3b04c185) | Mar 29, 2023 |
| Lenovo        | ThinkPad T460p 20HYSJKDO... | [1d24c2743f](https://linux-hardware.org/?probe=1d24c2743f) | Mar 29, 2023 |
| Valve         | Jupiter                     | [a63f5d9198](https://linux-hardware.org/?probe=a63f5d9198) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Dell          | Inspiron N5110              | [2b09d1f769](https://linux-hardware.org/?probe=2b09d1f769) | Mar 28, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [f511f8bcb1](https://linux-hardware.org/?probe=f511f8bcb1) | Mar 28, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [384f58a6b1](https://linux-hardware.org/?probe=384f58a6b1) | Mar 27, 2023 |
| Dell          | Latitude 7280               | [409cf549eb](https://linux-hardware.org/?probe=409cf549eb) | Mar 27, 2023 |
| Dell          | XPS 15 7590                 | [aeec5e2588](https://linux-hardware.org/?probe=aeec5e2588) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [22e7978cc8](https://linux-hardware.org/?probe=22e7978cc8) | Mar 26, 2023 |
| LG Electro... | 17Z90P-K.AA78A1             | [f889f2ddf5](https://linux-hardware.org/?probe=f889f2ddf5) | Mar 26, 2023 |
| Dell          | Inspiron N5110              | [8fde777c54](https://linux-hardware.org/?probe=8fde777c54) | Mar 26, 2023 |
| Acer          | Nitro AN515-55              | [36d5ba7071](https://linux-hardware.org/?probe=36d5ba7071) | Mar 26, 2023 |
| LG Electro... | 16Z90Q-K.AA78A1             | [009542d035](https://linux-hardware.org/?probe=009542d035) | Mar 26, 2023 |
| HP            | Spectre Laptop 13-af0xx     | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| Samsung       | R530/R730/R540              | [7e37be5b8c](https://linux-hardware.org/?probe=7e37be5b8c) | Mar 25, 2023 |
| HP            | Pavilion Laptop 14-ce3xx... | [1ea635d2a0](https://linux-hardware.org/?probe=1ea635d2a0) | Mar 25, 2023 |
| HP            | Stream Notebook             | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| Dell          | Latitude E6420              | [2613e5a6ef](https://linux-hardware.org/?probe=2613e5a6ef) | Mar 25, 2023 |
| HUAWEI        | NBD-WXX9                    | [7eb3d40bd8](https://linux-hardware.org/?probe=7eb3d40bd8) | Mar 25, 2023 |
| Apple         | MacBook4,1                  | [7ade2b1d1a](https://linux-hardware.org/?probe=7ade2b1d1a) | Mar 24, 2023 |
| Dell          | Precision 3510              | [2ea0671f5d](https://linux-hardware.org/?probe=2ea0671f5d) | Mar 24, 2023 |
| ASUSTek       | ROG Strix G513IE_G513IE     | [bc6baa37ef](https://linux-hardware.org/?probe=bc6baa37ef) | Mar 24, 2023 |
| HP            | Pavilion 15                 | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| Notebook      | W510LU                      | [076125acc3](https://linux-hardware.org/?probe=076125acc3) | Mar 23, 2023 |
| Sony          | SVF1521Q1EW                 | [10d078d9e2](https://linux-hardware.org/?probe=10d078d9e2) | Mar 22, 2023 |
| Valve         | Jupiter                     | [8fc3d21cf8](https://linux-hardware.org/?probe=8fc3d21cf8) | Mar 22, 2023 |
| Dell          | XPS 13 9380                 | [9bfb72d26a](https://linux-hardware.org/?probe=9bfb72d26a) | Mar 21, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [1400f9afc9](https://linux-hardware.org/?probe=1400f9afc9) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | [9c3ac61461](https://linux-hardware.org/?probe=9c3ac61461) | Mar 20, 2023 |
| HP            | ProBook 645 G4              | [10431e8027](https://linux-hardware.org/?probe=10431e8027) | Mar 20, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Fujitsu Si... | AMILO Xi 3670               | [bb018988d6](https://linux-hardware.org/?probe=bb018988d6) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [c9c86f1e79](https://linux-hardware.org/?probe=c9c86f1e79) | Mar 20, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [29a6e93a49](https://linux-hardware.org/?probe=29a6e93a49) | Mar 20, 2023 |
| Dell          | Latitude 5290 2-in-1        | [1840c57073](https://linux-hardware.org/?probe=1840c57073) | Mar 20, 2023 |
| Valve         | Jupiter                     | [8b7918d34b](https://linux-hardware.org/?probe=8b7918d34b) | Mar 20, 2023 |
| Sony          | VPCEH3N6E                   | [9de8a9a50a](https://linux-hardware.org/?probe=9de8a9a50a) | Mar 20, 2023 |
| Notebook      | PCx0Dx                      | [cd5adbbfc0](https://linux-hardware.org/?probe=cd5adbbfc0) | Mar 19, 2023 |
| Notebook      | N150ZU                      | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| Notebook      | PCx0Dx                      | [63a8165aff](https://linux-hardware.org/?probe=63a8165aff) | Mar 19, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | [f60325ef42](https://linux-hardware.org/?probe=f60325ef42) | Mar 19, 2023 |
| Dell          | Inspiron 15 7510            | [f7aebbae36](https://linux-hardware.org/?probe=f7aebbae36) | Mar 18, 2023 |
| Unknown       | Unknown                     | [e10e576833](https://linux-hardware.org/?probe=e10e576833) | Mar 18, 2023 |
| Unknown       | Unknown                     | [a791424f94](https://linux-hardware.org/?probe=a791424f94) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [49df72f291](https://linux-hardware.org/?probe=49df72f291) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [1f939ee045](https://linux-hardware.org/?probe=1f939ee045) | Mar 18, 2023 |
| Lenovo        | ThinkPad T410 2522AC1       | [5e6e5276e3](https://linux-hardware.org/?probe=5e6e5276e3) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | [9c677b7a7b](https://linux-hardware.org/?probe=9c677b7a7b) | Mar 18, 2023 |
| Sony          | VPCEH3N6E                   | [703cc66d3e](https://linux-hardware.org/?probe=703cc66d3e) | Mar 18, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d58b6cfe61](https://linux-hardware.org/?probe=d58b6cfe61) | Mar 18, 2023 |
| Dell          | Latitude 3410               | [8c71ef60d0](https://linux-hardware.org/?probe=8c71ef60d0) | Mar 18, 2023 |
| Lenovo        | V580c 20160                 | [b7f2837ccd](https://linux-hardware.org/?probe=b7f2837ccd) | Mar 17, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| Dell          | Inspiron 3542               | [63dba9dd56](https://linux-hardware.org/?probe=63dba9dd56) | Mar 17, 2023 |
| ASUSTek       | X555LAB                     | [18bf88d413](https://linux-hardware.org/?probe=18bf88d413) | Mar 17, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [e4eb6f31af](https://linux-hardware.org/?probe=e4eb6f31af) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| Toshiba       | Satellite L50-C             | [2193d33376](https://linux-hardware.org/?probe=2193d33376) | Mar 16, 2023 |
| Sony          | SVF1521Q1EW                 | [8ab2befd31](https://linux-hardware.org/?probe=8ab2befd31) | Mar 16, 2023 |
| Google        | Babymega                    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| PC Special... | P65_67RSRP                  | [71a45943c1](https://linux-hardware.org/?probe=71a45943c1) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [907581c9cc](https://linux-hardware.org/?probe=907581c9cc) | Mar 16, 2023 |
| HP            | Laptop 15-da0xxx            | [ccd15bcfae](https://linux-hardware.org/?probe=ccd15bcfae) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | [c6c5f88e4b](https://linux-hardware.org/?probe=c6c5f88e4b) | Mar 15, 2023 |
| Lenovo        | ThinkPad E560 20EV0010UK    | [3c632e35c3](https://linux-hardware.org/?probe=3c632e35c3) | Mar 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [fbbcc2d2c5](https://linux-hardware.org/?probe=fbbcc2d2c5) | Mar 15, 2023 |
| Toshiba       | QOSMIO X70-A                | [f85336fbca](https://linux-hardware.org/?probe=f85336fbca) | Mar 15, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [0ee987e184](https://linux-hardware.org/?probe=0ee987e184) | Mar 15, 2023 |
| Timi          | RedmiBook 14                | [ff5feda02c](https://linux-hardware.org/?probe=ff5feda02c) | Mar 14, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [0b9501dcc9](https://linux-hardware.org/?probe=0b9501dcc9) | Mar 14, 2023 |
| HP            | ProBook 645 G4              | [e2f98f4fd2](https://linux-hardware.org/?probe=e2f98f4fd2) | Mar 14, 2023 |
| TUXEDO        | Aura 15 Gen1                | [9331f6026e](https://linux-hardware.org/?probe=9331f6026e) | Mar 14, 2023 |
| TUXEDO        | InfinityBook S 15 Gen6      | [7e90a81e0b](https://linux-hardware.org/?probe=7e90a81e0b) | Mar 14, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [d23ddde885](https://linux-hardware.org/?probe=d23ddde885) | Mar 14, 2023 |
| Valve         | Jupiter                     | [1ad8d706ff](https://linux-hardware.org/?probe=1ad8d706ff) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | [08924a17f9](https://linux-hardware.org/?probe=08924a17f9) | Mar 14, 2023 |
| ASUSTek       | X551CA                      | [ba5c82bc14](https://linux-hardware.org/?probe=ba5c82bc14) | Mar 14, 2023 |
| Lenovo        | ThinkPad SL 2746N8G         | [2124288941](https://linux-hardware.org/?probe=2124288941) | Mar 13, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [007f595264](https://linux-hardware.org/?probe=007f595264) | Mar 13, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [fdb6080ba5](https://linux-hardware.org/?probe=fdb6080ba5) | Mar 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | [ca456dde7d](https://linux-hardware.org/?probe=ca456dde7d) | Mar 13, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [9841e70d67](https://linux-hardware.org/?probe=9841e70d67) | Mar 13, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [4c890ba150](https://linux-hardware.org/?probe=4c890ba150) | Mar 13, 2023 |
| HP            | Pavilion 15                 | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| OEGStone      | W240EU/W250EUQ/W270EUQ      | [45ea3c4094](https://linux-hardware.org/?probe=45ea3c4094) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| HP            | Laptop 14-ck0xxx            | [2be528d875](https://linux-hardware.org/?probe=2be528d875) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Acer          | Aspire 5920                 | [f6c972404c](https://linux-hardware.org/?probe=f6c972404c) | Mar 12, 2023 |
| Dell          | Latitude E6530              | [50a26c019d](https://linux-hardware.org/?probe=50a26c019d) | Mar 11, 2023 |
| Google        | Ampton                      | [641b7d64fc](https://linux-hardware.org/?probe=641b7d64fc) | Mar 10, 2023 |
| Dell          | Inspiron 1750               | [354cdf8592](https://linux-hardware.org/?probe=354cdf8592) | Mar 10, 2023 |
| Valve         | Jupiter                     | [d4cc4ff572](https://linux-hardware.org/?probe=d4cc4ff572) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | [661125aac2](https://linux-hardware.org/?probe=661125aac2) | Mar 10, 2023 |
| Unknown       | Unknown                     | [cd382356be](https://linux-hardware.org/?probe=cd382356be) | Mar 10, 2023 |
| HP            | ProBook 430 G4              | [9c3d2e652a](https://linux-hardware.org/?probe=9c3d2e652a) | Mar 09, 2023 |
| HP            | Laptop 14-cm0xxx            | [d35d11c64e](https://linux-hardware.org/?probe=d35d11c64e) | Mar 09, 2023 |
| Dell          | Latitude 7285               | [dfc4961010](https://linux-hardware.org/?probe=dfc4961010) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [026c39773a](https://linux-hardware.org/?probe=026c39773a) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Dell          | XPS 15 9530                 | [d7129009b0](https://linux-hardware.org/?probe=d7129009b0) | Mar 09, 2023 |
| Google        | Cave                        | [37d6d413b7](https://linux-hardware.org/?probe=37d6d413b7) | Mar 09, 2023 |
| Razer         | Blade 15 Advanced Model ... | [46fa9eab7d](https://linux-hardware.org/?probe=46fa9eab7d) | Mar 08, 2023 |
| Entroware     | Apollo                      | [d1576010b3](https://linux-hardware.org/?probe=d1576010b3) | Mar 08, 2023 |
| Valve         | Jupiter                     | [1851a5388e](https://linux-hardware.org/?probe=1851a5388e) | Mar 08, 2023 |
| Acer          | Swift SFX14-51G             | [54d0c16597](https://linux-hardware.org/?probe=54d0c16597) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| HUAWEI        | KLVD-WXX9                   | [1209c224e1](https://linux-hardware.org/?probe=1209c224e1) | Mar 06, 2023 |
| HONOR         | HYM-WXX                     | [f9f277d226](https://linux-hardware.org/?probe=f9f277d226) | Mar 06, 2023 |
| Acer          | Predator PH315-55           | [8465c0241c](https://linux-hardware.org/?probe=8465c0241c) | Mar 06, 2023 |
| Valve         | Jupiter                     | [f6c973a00f](https://linux-hardware.org/?probe=f6c973a00f) | Mar 06, 2023 |
| Dell          | Inspiron 15 3525            | [cc3e080ded](https://linux-hardware.org/?probe=cc3e080ded) | Mar 06, 2023 |
| Valve         | Jupiter                     | [73eb839f5b](https://linux-hardware.org/?probe=73eb839f5b) | Mar 06, 2023 |
| Alienware     | Area-51m R2                 | [5726561947](https://linux-hardware.org/?probe=5726561947) | Mar 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | [f6863db7ca](https://linux-hardware.org/?probe=f6863db7ca) | Mar 05, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [c777bd0be1](https://linux-hardware.org/?probe=c777bd0be1) | Mar 05, 2023 |
| Toshiba       | Satellite C660              | [d1ada89fd6](https://linux-hardware.org/?probe=d1ada89fd6) | Mar 04, 2023 |
| MSI           | GS70 2QE                    | [3c8e62e276](https://linux-hardware.org/?probe=3c8e62e276) | Mar 04, 2023 |
| Acer          | Aspire A515-47              | [3b1c7f5e26](https://linux-hardware.org/?probe=3b1c7f5e26) | Mar 04, 2023 |
| MSI           | GS70 2QE                    | [5c059744df](https://linux-hardware.org/?probe=5c059744df) | Mar 04, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | [89de1a18fe](https://linux-hardware.org/?probe=89de1a18fe) | Mar 04, 2023 |
| Lenovo        | ThinkPad T420 4236Q23       | [2aa5383e7e](https://linux-hardware.org/?probe=2aa5383e7e) | Mar 04, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [3e484b7bac](https://linux-hardware.org/?probe=3e484b7bac) | Mar 04, 2023 |
| Dell          | XPS 17 9700                 | [8a4cc5192e](https://linux-hardware.org/?probe=8a4cc5192e) | Mar 04, 2023 |
| Apple         | MacBookPro9,1               | [6553b59bfe](https://linux-hardware.org/?probe=6553b59bfe) | Mar 03, 2023 |
| Dell          | XPS 15 9560                 | [11572533c2](https://linux-hardware.org/?probe=11572533c2) | Mar 03, 2023 |
| Sony          | SVF1521Q1EW                 | [3c74542aad](https://linux-hardware.org/?probe=3c74542aad) | Mar 02, 2023 |
| Sony          | SVF1521Q1EW                 | [7b7db7c319](https://linux-hardware.org/?probe=7b7db7c319) | Mar 02, 2023 |
| Samsung       | 3570R/370R/470R/450R/510... | [2629f1915d](https://linux-hardware.org/?probe=2629f1915d) | Mar 02, 2023 |
| Dell          | Latitude E6410              | [3b99fd709e](https://linux-hardware.org/?probe=3b99fd709e) | Mar 02, 2023 |
| Valve         | Jupiter                     | [83cbea47d9](https://linux-hardware.org/?probe=83cbea47d9) | Mar 02, 2023 |
| Acer          | Aspire A315-32              | [5203ce8a41](https://linux-hardware.org/?probe=5203ce8a41) | Mar 02, 2023 |
| HUAWEI        | NBD-WXX9                    | [9036fa2ef1](https://linux-hardware.org/?probe=9036fa2ef1) | Mar 02, 2023 |
| Dell          | Latitude E7250              | [970d46cc83](https://linux-hardware.org/?probe=970d46cc83) | Mar 01, 2023 |
| HUAWEI        | KLVD-WXX9                   | [8c878d99a1](https://linux-hardware.org/?probe=8c878d99a1) | Mar 01, 2023 |
| Acer          | Predator PH517-61           | [2d1ec6c994](https://linux-hardware.org/?probe=2d1ec6c994) | Mar 01, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [eca37862f3](https://linux-hardware.org/?probe=eca37862f3) | Mar 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [1025a9748f](https://linux-hardware.org/?probe=1025a9748f) | Mar 01, 2023 |
| Acer          | Aspire 5733                 | [b1744130eb](https://linux-hardware.org/?probe=b1744130eb) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| Alienware     | 15 R2                       | [f242145858](https://linux-hardware.org/?probe=f242145858) | Feb 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| Acer          | Aspire V3-371               | [bbc0d58ef1](https://linux-hardware.org/?probe=bbc0d58ef1) | Feb 28, 2023 |
| Dell          | Latitude D630               | [5175558c99](https://linux-hardware.org/?probe=5175558c99) | Feb 28, 2023 |
| Dell          | Latitude E6440              | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| AZW           | SEi                         | [6d0814dc9f](https://linux-hardware.org/?probe=6d0814dc9f) | Feb 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| Panasonic     | CF-31WEUEEBE                | [40782ba0a7](https://linux-hardware.org/?probe=40782ba0a7) | Feb 26, 2023 |
| HP            | Pavilion g6                 | [556c1057a8](https://linux-hardware.org/?probe=556c1057a8) | Feb 26, 2023 |
| Dell          | Inspiron 3542               | [64f304d41e](https://linux-hardware.org/?probe=64f304d41e) | Feb 25, 2023 |
| HP            | G62                         | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [42b9d60137](https://linux-hardware.org/?probe=42b9d60137) | Feb 25, 2023 |
| Dell          | Latitude E6440              | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| MSI           | Modern 14 B10MW             | [4f9e90413b](https://linux-hardware.org/?probe=4f9e90413b) | Feb 25, 2023 |
| Lenovo        | IdeaPad Z580                | [cf2ff6c04b](https://linux-hardware.org/?probe=cf2ff6c04b) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [5cde621e0a](https://linux-hardware.org/?probe=5cde621e0a) | Feb 24, 2023 |
| Valve         | Jupiter                     | [df96e94417](https://linux-hardware.org/?probe=df96e94417) | Feb 24, 2023 |
| Toshiba       | Satellite C850-1GF          | [f568855409](https://linux-hardware.org/?probe=f568855409) | Feb 24, 2023 |
| Valve         | Jupiter                     | [8679998ec0](https://linux-hardware.org/?probe=8679998ec0) | Feb 23, 2023 |
| PC Special... | PD5x_7xPNP_PNN_PNT          | [cd71ec0b21](https://linux-hardware.org/?probe=cd71ec0b21) | Feb 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [f92ac89547](https://linux-hardware.org/?probe=f92ac89547) | Feb 23, 2023 |
| Lenovo        | V15-ADA 82C7                | [d19ee09dd3](https://linux-hardware.org/?probe=d19ee09dd3) | Feb 23, 2023 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [2c74210fed](https://linux-hardware.org/?probe=2c74210fed) | Feb 23, 2023 |
| Dell          | Inspiron 5565               | [d88dce11ff](https://linux-hardware.org/?probe=d88dce11ff) | Feb 22, 2023 |
| Lenovo        | ThinkPad X230 2325EJ0       | [3a2c22e22b](https://linux-hardware.org/?probe=3a2c22e22b) | Feb 22, 2023 |
| Lenovo        | ThinkPad T430s 23551M9      | [91b6a109b4](https://linux-hardware.org/?probe=91b6a109b4) | Feb 22, 2023 |
| Lenovo        | ThinkPad X230 2325EJ0       | [06c8604990](https://linux-hardware.org/?probe=06c8604990) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| Google        | Droid                       | [e576f650b7](https://linux-hardware.org/?probe=e576f650b7) | Feb 22, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [c51d4ef82a](https://linux-hardware.org/?probe=c51d4ef82a) | Feb 20, 2023 |
| HP            | Laptop 14s-fq0xxx           | [0bc03f3b39](https://linux-hardware.org/?probe=0bc03f3b39) | Feb 20, 2023 |
| Dell          | XPS 13 7390                 | [542077cc42](https://linux-hardware.org/?probe=542077cc42) | Feb 20, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | [c79a8f48f9](https://linux-hardware.org/?probe=c79a8f48f9) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | [2ccbfb422e](https://linux-hardware.org/?probe=2ccbfb422e) | Feb 20, 2023 |
| HUAWEI        | MateBook X                  | [cae415dee6](https://linux-hardware.org/?probe=cae415dee6) | Feb 20, 2023 |
| HUAWEI        | MateBook X                  | [6fed527c1b](https://linux-hardware.org/?probe=6fed527c1b) | Feb 20, 2023 |
| HP            | Pavilion g6                 | [f3552f5183](https://linux-hardware.org/?probe=f3552f5183) | Feb 19, 2023 |
| Lenovo        | ThinkPad E555 20DH000TUK    | [b2d5c9de8b](https://linux-hardware.org/?probe=b2d5c9de8b) | Feb 19, 2023 |
| HP            | 250 G6 Notebook PC          | [c32182253e](https://linux-hardware.org/?probe=c32182253e) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G731GU_G731GU     | [03952a6c01](https://linux-hardware.org/?probe=03952a6c01) | Feb 18, 2023 |
| Apple         | MacBookPro5,5               | [595103a203](https://linux-hardware.org/?probe=595103a203) | Feb 18, 2023 |
| PC Special... | NJ50_70CU                   | [68dd853397](https://linux-hardware.org/?probe=68dd853397) | Feb 17, 2023 |
| Lenovo        | IdeaPad 5 14IAL7 82SD       | [cd5e470881](https://linux-hardware.org/?probe=cd5e470881) | Feb 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0cd82bf0c0](https://linux-hardware.org/?probe=0cd82bf0c0) | Feb 17, 2023 |
| Dell          | Latitude E5450              | [cd7e5d61f2](https://linux-hardware.org/?probe=cd7e5d61f2) | Feb 17, 2023 |
| Dell          | Latitude E6410              | [58d4c40618](https://linux-hardware.org/?probe=58d4c40618) | Feb 17, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3042108dae](https://linux-hardware.org/?probe=3042108dae) | Feb 16, 2023 |
| Sony          | SVF1521Q1EW                 | [62503d2494](https://linux-hardware.org/?probe=62503d2494) | Feb 16, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [cec962a8f4](https://linux-hardware.org/?probe=cec962a8f4) | Feb 16, 2023 |
| HP            | Stream Notebook PC 14       | [ba59b583d2](https://linux-hardware.org/?probe=ba59b583d2) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [043e92c2ee](https://linux-hardware.org/?probe=043e92c2ee) | Feb 15, 2023 |
| Apple         | MacBookPro10,2              | [178ef8e028](https://linux-hardware.org/?probe=178ef8e028) | Feb 15, 2023 |
| HP            | Notebook                    | [88703a5913](https://linux-hardware.org/?probe=88703a5913) | Feb 15, 2023 |
| Apple         | MacBookPro10,2              | [6650047151](https://linux-hardware.org/?probe=6650047151) | Feb 15, 2023 |
| Linx          | LINX1010B                   | [5ca377461f](https://linux-hardware.org/?probe=5ca377461f) | Feb 14, 2023 |
| Unknown       | T3 MRD                      | [df134a8199](https://linux-hardware.org/?probe=df134a8199) | Feb 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9faf4ce80](https://linux-hardware.org/?probe=e9faf4ce80) | Feb 14, 2023 |
| Valve         | Jupiter                     | [e362a7551c](https://linux-hardware.org/?probe=e362a7551c) | Feb 14, 2023 |
| Acer          | TravelMate P215-52          | [b4ac56b67d](https://linux-hardware.org/?probe=b4ac56b67d) | Feb 13, 2023 |
| Dell          | XPS 15 9520                 | [1263022267](https://linux-hardware.org/?probe=1263022267) | Feb 13, 2023 |
| Apple         | MacBook4,1                  | [dfb5b14f25](https://linux-hardware.org/?probe=dfb5b14f25) | Feb 13, 2023 |
| Dell          | Latitude E6530              | [c79c336ef7](https://linux-hardware.org/?probe=c79c336ef7) | Feb 13, 2023 |
| Acer          | Aspire 5349                 | [8407710a28](https://linux-hardware.org/?probe=8407710a28) | Feb 12, 2023 |
| HUAWEI        | NBD-WXX9                    | [c8caa92db3](https://linux-hardware.org/?probe=c8caa92db3) | Feb 11, 2023 |
| Toshiba       | Satellite Pro C850-10N      | [d45ac3e79c](https://linux-hardware.org/?probe=d45ac3e79c) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| Acer          | Swift SF314-43              | [60fed002e2](https://linux-hardware.org/?probe=60fed002e2) | Feb 11, 2023 |
| Acer          | TravelMate P253             | [8947050124](https://linux-hardware.org/?probe=8947050124) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | [ddde9bf34e](https://linux-hardware.org/?probe=ddde9bf34e) | Feb 10, 2023 |
| Dell          | Precision M4700             | [74f62c6131](https://linux-hardware.org/?probe=74f62c6131) | Feb 10, 2023 |
| Dell          | Precision M4700             | [797b766595](https://linux-hardware.org/?probe=797b766595) | Feb 10, 2023 |
| ASUSTek       | GL552VW                     | [c9ed530a00](https://linux-hardware.org/?probe=c9ed530a00) | Feb 10, 2023 |
| Novatech      | NL40_50CU                   | [cca307c7db](https://linux-hardware.org/?probe=cca307c7db) | Feb 10, 2023 |
| Lenovo        | ThinkPad T450 20BUA0PNUK    | [8837c33007](https://linux-hardware.org/?probe=8837c33007) | Feb 09, 2023 |
| HP            | EliteBook Folio 1040 G3     | [3209372a9d](https://linux-hardware.org/?probe=3209372a9d) | Feb 09, 2023 |
| Dell          | Latitude 5511               | [05e11b64d6](https://linux-hardware.org/?probe=05e11b64d6) | Feb 09, 2023 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [c9dd7aae2e](https://linux-hardware.org/?probe=c9dd7aae2e) | Feb 08, 2023 |
| Dell          | Latitude E6330              | [291e0fd64f](https://linux-hardware.org/?probe=291e0fd64f) | Feb 08, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [a1c831925b](https://linux-hardware.org/?probe=a1c831925b) | Feb 08, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | [86c4416049](https://linux-hardware.org/?probe=86c4416049) | Feb 08, 2023 |
| HP            | EliteBook Folio 1040 G3     | [fa77bac136](https://linux-hardware.org/?probe=fa77bac136) | Feb 08, 2023 |
| HP            | EliteBook 745 G2            | [35cb1bce53](https://linux-hardware.org/?probe=35cb1bce53) | Feb 08, 2023 |
| HP            | Laptop 14-cm0xxx            | [5dfc3e2280](https://linux-hardware.org/?probe=5dfc3e2280) | Feb 08, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | [e39c3cefa0](https://linux-hardware.org/?probe=e39c3cefa0) | Feb 08, 2023 |
| HP            | EliteBook 745 G2            | [ce120b023c](https://linux-hardware.org/?probe=ce120b023c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [e32b918f95](https://linux-hardware.org/?probe=e32b918f95) | Feb 07, 2023 |
| HUAWEI        | NBD-WXX9                    | [2bb967f6b3](https://linux-hardware.org/?probe=2bb967f6b3) | Feb 07, 2023 |
| Dell          | Latitude 5330               | [30cd96be4d](https://linux-hardware.org/?probe=30cd96be4d) | Feb 07, 2023 |
| Lenovo        | ThinkPad T430 2349UXH       | [aea2246107](https://linux-hardware.org/?probe=aea2246107) | Feb 06, 2023 |
| Lenovo        | ThinkPad T430 2349UXH       | [24d1d2fa52](https://linux-hardware.org/?probe=24d1d2fa52) | Feb 06, 2023 |
| Google        | Samus                       | [0817ec0be1](https://linux-hardware.org/?probe=0817ec0be1) | Feb 06, 2023 |
| Acer          | Aspire E5-571               | [a50f302f00](https://linux-hardware.org/?probe=a50f302f00) | Feb 06, 2023 |
| Acer          | TravelMate P253             | [050d7b5d68](https://linux-hardware.org/?probe=050d7b5d68) | Feb 06, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f536be92d0](https://linux-hardware.org/?probe=f536be92d0) | Feb 06, 2023 |
| Dell          | Inspiron 5593               | [6c09a62b19](https://linux-hardware.org/?probe=6c09a62b19) | Feb 06, 2023 |
| HP            | EliteBook Folio 1040 G3     | [67d2b1fd55](https://linux-hardware.org/?probe=67d2b1fd55) | Feb 05, 2023 |
| HP            | Notebook                    | [0ad701667d](https://linux-hardware.org/?probe=0ad701667d) | Feb 05, 2023 |
| HP            | Notebook                    | [37f601798c](https://linux-hardware.org/?probe=37f601798c) | Feb 05, 2023 |
| Apple         | MacBookPro13,1              | [76cf23841d](https://linux-hardware.org/?probe=76cf23841d) | Feb 05, 2023 |
| Acer          | Aspire ES1-531              | [4d2872e685](https://linux-hardware.org/?probe=4d2872e685) | Feb 04, 2023 |
| GEO           | GeoBook 240                 | [861adcda52](https://linux-hardware.org/?probe=861adcda52) | Feb 04, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | [cee7b3fa93](https://linux-hardware.org/?probe=cee7b3fa93) | Feb 04, 2023 |
| GEO           | GeoBook 140                 | [a91fdaa5da](https://linux-hardware.org/?probe=a91fdaa5da) | Feb 04, 2023 |
| Lenovo        | ThinkPad X280 20KEA0VCUK    | [48d07b6859](https://linux-hardware.org/?probe=48d07b6859) | Feb 04, 2023 |
| Dell          | XPS 13 9380                 | [495ff876cf](https://linux-hardware.org/?probe=495ff876cf) | Feb 03, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [e23aca8e4b](https://linux-hardware.org/?probe=e23aca8e4b) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [98ad1bcab4](https://linux-hardware.org/?probe=98ad1bcab4) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [5fe174bdd1](https://linux-hardware.org/?probe=5fe174bdd1) | Feb 03, 2023 |
| MSI           | GS66 Stealth 10SF           | [1d3a68b4a0](https://linux-hardware.org/?probe=1d3a68b4a0) | Feb 03, 2023 |
| Lenovo        | B50-30 80ES                 | [3fb480c029](https://linux-hardware.org/?probe=3fb480c029) | Feb 03, 2023 |
| Dell          | Latitude 5420               | [019540839e](https://linux-hardware.org/?probe=019540839e) | Feb 03, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [f544702336](https://linux-hardware.org/?probe=f544702336) | Feb 03, 2023 |
| HP            | Laptop 15-da0xxx            | [21227757d0](https://linux-hardware.org/?probe=21227757d0) | Feb 02, 2023 |
| Toshiba       | Satellite L50D-B            | [457faa2485](https://linux-hardware.org/?probe=457faa2485) | Feb 02, 2023 |
| Notebook      | NL5xNU                      | [8bec95eb42](https://linux-hardware.org/?probe=8bec95eb42) | Feb 02, 2023 |
| Alienware     | M14xR2                      | [d7e3d61744](https://linux-hardware.org/?probe=d7e3d61744) | Feb 02, 2023 |
| Acer          | Aspire 5349                 | [edf1e65f78](https://linux-hardware.org/?probe=edf1e65f78) | Feb 02, 2023 |
| Acer          | Aspire one 1-132            | [d66a972aa9](https://linux-hardware.org/?probe=d66a972aa9) | Feb 02, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000U... | [d7a5b537d9](https://linux-hardware.org/?probe=d7a5b537d9) | Feb 01, 2023 |
| HP            | Sona                        | [36a3d72172](https://linux-hardware.org/?probe=36a3d72172) | Jan 31, 2023 |
| Lenovo        | Yoga 3 14 80JH              | [6c66b66a78](https://linux-hardware.org/?probe=6c66b66a78) | Jan 30, 2023 |
| Valve         | Jupiter                     | [9568a6f43d](https://linux-hardware.org/?probe=9568a6f43d) | Jan 30, 2023 |
| Acer          | Aspire A515-52              | [51fa3ff577](https://linux-hardware.org/?probe=51fa3ff577) | Jan 30, 2023 |
| HP            | Laptop 14-cm0xxx            | [9b93652159](https://linux-hardware.org/?probe=9b93652159) | Jan 29, 2023 |
| Valve         | Jupiter                     | [91ef57c9e5](https://linux-hardware.org/?probe=91ef57c9e5) | Jan 29, 2023 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | [3912652a13](https://linux-hardware.org/?probe=3912652a13) | Jan 29, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | [41d33a9029](https://linux-hardware.org/?probe=41d33a9029) | Jan 29, 2023 |
| Dell          | Latitude E6530              | [87bca9f2a4](https://linux-hardware.org/?probe=87bca9f2a4) | Jan 29, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ed1ce46901](https://linux-hardware.org/?probe=ed1ce46901) | Jan 28, 2023 |
| Dell          | Inspiron 14-3452            | [baf61affa2](https://linux-hardware.org/?probe=baf61affa2) | Jan 28, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [c4877a8bc3](https://linux-hardware.org/?probe=c4877a8bc3) | Jan 28, 2023 |
| Apple         | MacBookAir7,2               | [b5f0169944](https://linux-hardware.org/?probe=b5f0169944) | Jan 28, 2023 |
| HP            | ENVY Laptop 17-cg0xxx       | [ab3f84f96b](https://linux-hardware.org/?probe=ab3f84f96b) | Jan 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0245809d6a](https://linux-hardware.org/?probe=0245809d6a) | Jan 28, 2023 |
| Notebook      | P17SM-A                     | [609a89ca14](https://linux-hardware.org/?probe=609a89ca14) | Jan 27, 2023 |
| HP            | EliteBook 8530w             | [f395c475c9](https://linux-hardware.org/?probe=f395c475c9) | Jan 27, 2023 |
| Lenovo        | ThinkPad T530 24292DG       | [e171a529b9](https://linux-hardware.org/?probe=e171a529b9) | Jan 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5f1e1e4d00](https://linux-hardware.org/?probe=5f1e1e4d00) | Jan 27, 2023 |
| Dell          | Inspiron 15 3521            | [41f89081ff](https://linux-hardware.org/?probe=41f89081ff) | Jan 26, 2023 |
| Acer          | Aspire ES1-411              | [110767fd86](https://linux-hardware.org/?probe=110767fd86) | Jan 26, 2023 |
| MSI           | Katana GF66 11UE            | [aead8d4d18](https://linux-hardware.org/?probe=aead8d4d18) | Jan 26, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | [de8222900d](https://linux-hardware.org/?probe=de8222900d) | Jan 26, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0Q... | [cdd3eb5723](https://linux-hardware.org/?probe=cdd3eb5723) | Jan 26, 2023 |
| Notebook      | P17SM-A                     | [6ed204eca5](https://linux-hardware.org/?probe=6ed204eca5) | Jan 26, 2023 |
| Google        | Careena                     | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | [6faa58b4a1](https://linux-hardware.org/?probe=6faa58b4a1) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | [f437e45107](https://linux-hardware.org/?probe=f437e45107) | Jan 26, 2023 |
| Lenovo        | Yoga 2 11 20332             | [9dfb8ac7b0](https://linux-hardware.org/?probe=9dfb8ac7b0) | Jan 25, 2023 |
| OEGStone      | C4100/C5100                 | [4365b7b231](https://linux-hardware.org/?probe=4365b7b231) | Jan 25, 2023 |
| Dell          | Latitude 5520               | [662284824b](https://linux-hardware.org/?probe=662284824b) | Jan 24, 2023 |
| HP            | EliteBook 745 G2            | [0d073c35f4](https://linux-hardware.org/?probe=0d073c35f4) | Jan 24, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/UK/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 548       | 12.97%  |
| Ubuntu 18.04       | 278       | 6.58%   |
| Ubuntu 22.04       | 233       | 5.52%   |
| Zorin 16           | 110       | 2.6%    |
| OpenMandriva 4.3   | 84        | 1.99%   |
| Pop!_OS 22.04      | 82        | 1.94%   |
| Debian 11          | 74        | 1.75%   |
| Arch Rolling       | 74        | 1.75%   |
| Linux Mint 19.3    | 68        | 1.61%   |
| Ubuntu 19.04       | 62        | 1.47%   |
| OpenMandriva 4.2   | 60        | 1.42%   |
| Manjaro            | 60        | 1.42%   |
| Linux Mint 20.3    | 58        | 1.37%   |
| Pop!_OS 20.04      | 55        | 1.3%    |
| Linux Mint 21.1    | 55        | 1.3%    |
| Linux Mint 20.2    | 54        | 1.28%   |
| Arch               | 54        | 1.28%   |
| Ubuntu 20.10       | 53        | 1.25%   |
| Zorin 15           | 52        | 1.23%   |
| KDE neon 20.04     | 52        | 1.23%   |
| Ubuntu 21.10       | 51        | 1.21%   |
| Linux Mint 20.1    | 50        | 1.18%   |
| ArcoLinux Rolling  | 50        | 1.18%   |
| Ubuntu 19.10       | 49        | 1.16%   |
| Pop!_OS 21.04      | 45        | 1.07%   |
| Ubuntu 21.04       | 44        | 1.04%   |
| OpenMandriva 23.01 | 44        | 1.04%   |
| Fedora 38          | 43        | 1.02%   |
| OpenMandriva 23.03 | 40        | 0.95%   |
| Xubuntu 20.04      | 39        | 0.92%   |
| Linux Mint 20      | 36        | 0.85%   |
| Pop!_OS 20.10      | 34        | 0.8%    |
| Fedora 37          | 34        | 0.8%    |
| Pop!_OS 21.10      | 33        | 0.78%   |
| Fedora 35          | 33        | 0.78%   |
| Fedora 34          | 33        | 0.78%   |
| Fedora 36          | 32        | 0.76%   |
| Ubuntu 18.10       | 31        | 0.73%   |
| Linux Mint 21      | 30        | 0.71%   |
| BlackPanther 18.1  | 29        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1356      | 33.68%  |
| Linux Mint    | 370       | 9.19%   |
| OpenMandriva  | 258       | 6.41%   |
| Fedora        | 252       | 6.26%   |
| Pop!_OS       | 233       | 5.79%   |
| Zorin         | 170       | 4.22%   |
| Manjaro       | 133       | 3.3%    |
| Debian        | 126       | 3.13%   |
| Arch          | 126       | 3.13%   |
| Kubuntu       | 92        | 2.29%   |
| SteamOS       | 89        | 2.21%   |
| Xubuntu       | 87        | 2.16%   |
| KDE neon      | 76        | 1.89%   |
| ArcoLinux     | 54        | 1.34%   |
| Elementary    | 47        | 1.17%   |
| Lubuntu       | 40        | 0.99%   |
| ROSA          | 37        | 0.92%   |
| Ubuntu MATE   | 36        | 0.89%   |
| openSUSE      | 33        | 0.82%   |
| BlackPanther  | 30        | 0.75%   |
| Ubuntu Unity  | 29        | 0.72%   |
| Gentoo        | 29        | 0.72%   |
| Endless       | 28        | 0.7%    |
| Kali          | 27        | 0.67%   |
| EndeavourOS   | 20        | 0.5%    |
| LMDE          | 19        | 0.47%   |
| Garuda Linux  | 19        | 0.47%   |
| Clear Linux   | 19        | 0.47%   |
| MX            | 18        | 0.45%   |
| Ubuntu Budgie | 16        | 0.4%    |
| Parrot        | 15        | 0.37%   |
| Peppermint    | 12        | 0.3%    |
| CentOS        | 11        | 0.27%   |
| Nobara        | 8         | 0.2%    |
| RHEL          | 7         | 0.17%   |
| NixOS         | 7         | 0.17%   |
| Q4OS          | 5         | 0.12%   |
| PureOS        | 5         | 0.12%   |
| Artix         | 5         | 0.12%   |
| Alpine        | 5         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 79        | 1.7%    |
| 5.4.0-42-generic         | 77        | 1.66%   |
| 5.10.14-desktop-1omv4002 | 57        | 1.23%   |
| 5.15.0-56-generic        | 48        | 1.03%   |
| 5.13.0-valve36-1-neptune | 41        | 0.88%   |
| 6.2.6-desktop-1omv2390   | 40        | 0.86%   |
| 5.4.0-48-generic         | 40        | 0.86%   |
| 5.4.0-52-generic         | 39        | 0.84%   |
| 6.1.1-desktop-1omv2290   | 38        | 0.82%   |
| 5.15.0-52-generic        | 38        | 0.82%   |
| 5.15.0-58-generic        | 37        | 0.8%    |
| 5.4.0-29-generic         | 35        | 0.75%   |
| 5.3.0-40-generic         | 35        | 0.75%   |
| 5.11.0-27-generic        | 34        | 0.73%   |
| 5.4.0-26-generic         | 33        | 0.71%   |
| 5.3.0-28-generic         | 33        | 0.71%   |
| 5.15.0-46-generic        | 33        | 0.71%   |
| 5.4.0-58-generic         | 30        | 0.64%   |
| 5.4.0-40-generic         | 29        | 0.62%   |
| 5.0.0-32-generic         | 29        | 0.62%   |
| 5.11.0-38-generic        | 28        | 0.6%    |
| 5.8.0-43-generic         | 25        | 0.54%   |
| 5.3.0-42-generic         | 25        | 0.54%   |
| 5.19.0-35-generic        | 25        | 0.54%   |
| 5.4.0-91-generic         | 24        | 0.52%   |
| 5.11.0-37-generic        | 24        | 0.52%   |
| 5.11.0-25-generic        | 24        | 0.52%   |
| 5.4.0-65-generic         | 23        | 0.49%   |
| 5.4.0-7634-generic       | 22        | 0.47%   |
| 5.4.0-33-generic         | 22        | 0.47%   |
| 5.13.0-7614-generic      | 22        | 0.47%   |
| 5.13.0-28-generic        | 22        | 0.47%   |
| 5.0.0-37-generic         | 22        | 0.47%   |
| 4.18.16-desktop-1bP      | 22        | 0.47%   |
| 6.2.0-26-generic         | 21        | 0.45%   |
| 5.8.0-50-generic         | 21        | 0.45%   |
| 5.8.0-44-generic         | 21        | 0.45%   |
| 5.4.0-56-generic         | 21        | 0.45%   |
| 5.4.0-54-generic         | 21        | 0.45%   |
| 5.3.0-46-generic         | 21        | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 733       | 16.85%  |
| 5.15.0  | 398       | 9.15%   |
| 5.13.0  | 270       | 6.21%   |
| 5.11.0  | 243       | 5.59%   |
| 5.8.0   | 233       | 5.36%   |
| 5.3.0   | 204       | 4.69%   |
| 4.15.0  | 203       | 4.67%   |
| 5.19.0  | 157       | 3.61%   |
| 5.0.0   | 137       | 3.15%   |
| 5.10.0  | 100       | 2.3%    |
| 4.18.0  | 92        | 2.12%   |
| 5.16.7  | 79        | 1.82%   |
| 6.2.0   | 64        | 1.47%   |
| 6.2.6   | 63        | 1.45%   |
| 5.10.14 | 57        | 1.31%   |
| 6.1.1   | 39        | 0.9%    |
| 6.1.0   | 32        | 0.74%   |
| 4.19.0  | 30        | 0.69%   |
| 4.18.16 | 23        | 0.53%   |
| 6.4.11  | 16        | 0.37%   |
| 5.17.5  | 16        | 0.37%   |
| 5.14.0  | 16        | 0.37%   |
| 6.0.6   | 15        | 0.34%   |
| 6.0.0   | 15        | 0.34%   |
| 6.2.9   | 12        | 0.28%   |
| 4.9.60  | 12        | 0.28%   |
| 6.3.5   | 11        | 0.25%   |
| 6.0.12  | 11        | 0.25%   |
| 5.17.1  | 11        | 0.25%   |
| 5.16.0  | 11        | 0.25%   |
| 5.9.16  | 10        | 0.23%   |
| 5.15.12 | 10        | 0.23%   |
| 4.4.0   | 10        | 0.23%   |
| 6.4.6   | 9         | 0.21%   |
| 5.18.10 | 9         | 0.21%   |
| 6.4.12  | 8         | 0.18%   |
| 5.9.0   | 8         | 0.18%   |
| 5.6.14  | 8         | 0.18%   |
| 5.3.18  | 8         | 0.18%   |
| 5.16.15 | 8         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 769       | 17.85%  |
| 5.15    | 487       | 11.3%   |
| 5.13    | 310       | 7.19%   |
| 5.8     | 278       | 6.45%   |
| 5.11    | 267       | 6.2%    |
| 5.3     | 228       | 5.29%   |
| 5.10    | 206       | 4.78%   |
| 4.15    | 204       | 4.73%   |
| 5.19    | 198       | 4.6%    |
| 6.2     | 173       | 4.01%   |
| 5.16    | 145       | 3.37%   |
| 5.0     | 144       | 3.34%   |
| 6.1     | 137       | 3.18%   |
| 4.18    | 117       | 2.72%   |
| 6.0     | 78        | 1.81%   |
| 6.4     | 66        | 1.53%   |
| 5.17    | 57        | 1.32%   |
| 6.3     | 53        | 1.23%   |
| 5.14    | 53        | 1.23%   |
| 5.9     | 46        | 1.07%   |
| 4.19    | 46        | 1.07%   |
| 5.12    | 42        | 0.97%   |
| 5.6     | 38        | 0.88%   |
| 4.9     | 33        | 0.77%   |
| 5.18    | 32        | 0.74%   |
| 5.7     | 30        | 0.7%    |
| 5.5     | 19        | 0.44%   |
| 5.2     | 11        | 0.26%   |
| 4.4     | 11        | 0.26%   |
| 5.1     | 8         | 0.19%   |
| 3.10    | 4         | 0.09%   |
| 4.20    | 3         | 0.07%   |
| 4.16    | 3         | 0.07%   |
| 4.14    | 3         | 0.07%   |
| 4.8     | 2         | 0.05%   |
| 4.12    | 2         | 0.05%   |
| 4.1     | 2         | 0.05%   |
| 4.6     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |
| 4.13    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3769      | 96.99%  |
| i686    | 116       | 2.99%   |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1813      | 44.75%  |
| KDE5             | 717       | 17.7%   |
| Unknown          | 419       | 10.34%  |
| X-Cinnamon       | 301       | 7.43%   |
| XFCE             | 289       | 7.13%   |
| MATE             | 111       | 2.74%   |
| KDE              | 85        | 2.1%    |
| Pantheon         | 44        | 1.09%   |
| LXQt             | 41        | 1.01%   |
| Cinnamon         | 41        | 1.01%   |
| Unity            | 31        | 0.77%   |
| LXDE             | 26        | 0.64%   |
| Budgie           | 23        | 0.57%   |
| i3               | 22        | 0.54%   |
| GNOME Flashback  | 16        | 0.39%   |
| KDE4             | 14        | 0.35%   |
| sway             | 9         | 0.22%   |
| qtile            | 6         | 0.15%   |
| GNOME Classic    | 6         | 0.15%   |
| awesome          | 5         | 0.12%   |
| Hyprland         | 4         | 0.1%    |
| bspwm            | 4         | 0.1%    |
| trinity          | 3         | 0.07%   |
| openbox          | 3         | 0.07%   |
| Deepin           | 3         | 0.07%   |
| xmonad           | 2         | 0.05%   |
| i3-with-shmlog   | 2         | 0.05%   |
| DWM              | 2         | 0.05%   |
| chadwm           | 2         | 0.05%   |
| mwm              | 1         | 0.02%   |
| lightdm-xsession | 1         | 0.02%   |
| Hypr             | 1         | 0.02%   |
| GNUstep          | 1         | 0.02%   |
| Enlightenment    | 1         | 0.02%   |
| Cutefish         | 1         | 0.02%   |
| BunsenLabs       | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 3036      | 76.15%  |
| Wayland | 680       | 17.06%  |
| Unknown | 229       | 5.74%   |
| Tty     | 42        | 1.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2117      | 52.39%  |
| SDDM    | 575       | 14.23%  |
| GDM     | 441       | 10.91%  |
| GDM3    | 419       | 10.37%  |
| LightDM | 354       | 8.76%   |
| TDM     | 101       | 2.5%    |
| KDM     | 15        | 0.37%   |
| XDM     | 5         | 0.12%   |
| LXDM    | 5         | 0.12%   |
| Ly      | 4         | 0.1%    |
| SLiM    | 1         | 0.02%   |
| NODM    | 1         | 0.02%   |
| LY-DM   | 1         | 0.02%   |
| GREETD  | 1         | 0.02%   |
| CDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| en_GB          | 2861      | 71.83%  |
| en_US          | 514       | 12.9%   |
| Unknown        | 413       | 10.37%  |
| C              | 53        | 1.33%   |
| pl_PL          | 41        | 1.03%   |
| de_DE          | 10        | 0.25%   |
| fr_FR          | 9         | 0.23%   |
| it_IT          | 7         | 0.18%   |
| en_AU          | 7         | 0.18%   |
| ru_RU          | 6         | 0.15%   |
| POSIX          | 6         | 0.15%   |
| es_ES          | 6         | 0.15%   |
| en_CA          | 6         | 0.15%   |
| en_IN          | 5         | 0.13%   |
| en_IE          | 5         | 0.13%   |
| cs_CZ          | 5         | 0.13%   |
| hu_HU          | 4         | 0.1%    |
| zh_CN          | 3         | 0.08%   |
| ro_RO          | 3         | 0.08%   |
| sk_SK          | 2         | 0.05%   |
| pt_PT          | 2         | 0.05%   |
| pt_BR          | 2         | 0.05%   |
| uk_UA          | 1         | 0.03%   |
| tr_TR          | 1         | 0.03%   |
| nl_BE          | 1         | 0.03%   |
| en_IL          | 1         | 0.03%   |
| en_HK          | 1         | 0.03%   |
| en_GG          | 1         | 0.03%   |
| en_GB.utf-8    | 1         | 0.03%   |
| en_GB.iso88591 | 1         | 0.03%   |
| en_AG          | 1         | 0.03%   |
| enGB           | 1         | 0.03%   |
| da_DK          | 1         | 0.03%   |
| C.UTF8         | 1         | 0.03%   |
| bg_BG          | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2025      | 51.15%  |
| BIOS | 1934      | 48.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3019      | 75.59%  |
| Btrfs   | 416       | 10.42%  |
| Overlay | 275       | 6.89%   |
| Unknown | 112       | 2.8%    |
| Tmpfs   | 75        | 1.88%   |
| Xfs     | 47        | 1.18%   |
| Zfs     | 31        | 0.78%   |
| Ext2    | 9         | 0.23%   |
| F2fs    | 6         | 0.15%   |
| Ext3    | 3         | 0.08%   |
| Aufs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2226      | 55.9%   |
| GPT     | 1402      | 35.21%  |
| MBR     | 354       | 8.89%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3526      | 89.31%  |
| Yes       | 422       | 10.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2984      | 75.74%  |
| Yes       | 956       | 24.26%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 766       | 19.73%  |
| Dell                | 757       | 19.5%   |
| Hewlett-Packard     | 632       | 16.28%  |
| Acer                | 286       | 7.37%   |
| ASUSTek Computer    | 276       | 7.11%   |
| Toshiba             | 170       | 4.38%   |
| Apple               | 120       | 3.09%   |
| Valve               | 91        | 2.34%   |
| Samsung Electronics | 76        | 1.96%   |
| Sony                | 64        | 1.65%   |
| MSI                 | 63        | 1.62%   |
| PC Specialist       | 46        | 1.18%   |
| Google              | 46        | 1.18%   |
| HUAWEI              | 45        | 1.16%   |
| Notebook            | 32        | 0.82%   |
| Unknown             | 31        | 0.8%    |
| Razer               | 20        | 0.52%   |
| Star Labs           | 19        | 0.49%   |
| Fujitsu             | 19        | 0.49%   |
| Alienware           | 19        | 0.49%   |
| Packard Bell        | 18        | 0.46%   |
| Fujitsu Siemens     | 14        | 0.36%   |
| Entroware           | 14        | 0.36%   |
| Dixonsxp            | 14        | 0.36%   |
| TUXEDO              | 13        | 0.33%   |
| GEO                 | 12        | 0.31%   |
| LG Electronics      | 11        | 0.28%   |
| Clevo               | 11        | 0.28%   |
| Linx                | 9         | 0.23%   |
| Gigabyte Technology | 9         | 0.23%   |
| Advent              | 9         | 0.23%   |
| Timi                | 8         | 0.21%   |
| Jumper              | 8         | 0.21%   |
| eMachines           | 8         | 0.21%   |
| Panasonic           | 7         | 0.18%   |
| OEGStone            | 7         | 0.18%   |
| Medion              | 7         | 0.18%   |
| Intel               | 7         | 0.18%   |
| Framework           | 7         | 0.18%   |
| Novatech            | 6         | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Valve Jupiter           | 91        | 2.34%   |
| Unknown                 | 53        | 1.37%   |
| HP Pavilion g6          | 25        | 0.64%   |
| HP Notebook             | 21        | 0.54%   |
| HP Pavilion 15          | 20        | 0.52%   |
| HP Pavilion Notebook    | 17        | 0.44%   |
| Dell XPS 15 7590        | 16        | 0.41%   |
| Dell XPS 15 9560        | 15        | 0.39%   |
| Dell Inspiron 1545      | 15        | 0.39%   |
| Dell XPS 15 9570        | 14        | 0.36%   |
| Dell XPS 13 9380        | 14        | 0.36%   |
| Dell XPS 13 9370        | 13        | 0.33%   |
| Dell Latitude E6400     | 13        | 0.33%   |
| Dell XPS 13 9360        | 12        | 0.31%   |
| Dell Latitude E6410     | 12        | 0.31%   |
| Apple MacBookPro12,1    | 12        | 0.31%   |
| Toshiba Satellite C660  | 11        | 0.28%   |
| Lenovo V145-15AST 81MT  | 11        | 0.28%   |
| Dell XPS 13 7390        | 11        | 0.28%   |
| Dell Latitude E7240     | 11        | 0.28%   |
| HP Pavilion dv6         | 10        | 0.26%   |
| HP Laptop 15-da0xxx     | 10        | 0.26%   |
| Dell XPS 15 9550        | 10        | 0.26%   |
| Dell XPS 15 9510        | 10        | 0.26%   |
| Dell Latitude E7450     | 10        | 0.26%   |
| Apple MacBookPro9,2     | 10        | 0.26%   |
| Acer Aspire ES1-531     | 10        | 0.26%   |
| Lenovo Z50-75 80EC      | 9         | 0.23%   |
| HP Laptop 15-bw0xx      | 9         | 0.23%   |
| HP 15                   | 9         | 0.23%   |
| Dell XPS 13 9310        | 9         | 0.23%   |
| Dell XPS 13 9305        | 9         | 0.23%   |
| Dell Latitude E7440     | 9         | 0.23%   |
| Dell Latitude E6420     | 9         | 0.23%   |
| Apple MacBookPro5,5     | 9         | 0.23%   |
| Dell XPS 15 9500        | 8         | 0.21%   |
| Dell Inspiron 5570      | 8         | 0.21%   |
| Toshiba Satellite C50-B | 7         | 0.18%   |
| Star Labs LabTop        | 7         | 0.18%   |
| Razer Blade             | 7         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 435       | 11.21%  |
| Dell Latitude         | 264       | 6.8%    |
| Acer Aspire           | 205       | 5.28%   |
| Dell Inspiron         | 196       | 5.05%   |
| Dell XPS              | 176       | 4.53%   |
| Toshiba Satellite     | 148       | 3.81%   |
| Lenovo IdeaPad        | 143       | 3.68%   |
| HP Pavilion           | 140       | 3.61%   |
| HP EliteBook          | 105       | 2.7%    |
| Valve Jupiter         | 91        | 2.34%   |
| HP Laptop             | 69        | 1.78%   |
| HP ProBook            | 65        | 1.67%   |
| ASUS VivoBook         | 64        | 1.65%   |
| Unknown               | 53        | 1.37%   |
| Dell Precision        | 43        | 1.11%   |
| HP ENVY               | 34        | 0.88%   |
| HP Compaq             | 31        | 0.8%    |
| Lenovo Legion         | 29        | 0.75%   |
| Acer Swift            | 29        | 0.75%   |
| HP Stream             | 28        | 0.72%   |
| ASUS Zenbook          | 26        | 0.67%   |
| Dell Vostro           | 25        | 0.64%   |
| ASUS ROG              | 24        | 0.62%   |
| Lenovo Yoga           | 21        | 0.54%   |
| HP Notebook           | 21        | 0.54%   |
| Razer Blade           | 20        | 0.52%   |
| Lenovo ThinkBook      | 20        | 0.52%   |
| HP ZBook              | 19        | 0.49%   |
| HP 255                | 18        | 0.46%   |
| Packard Bell EasyNote | 17        | 0.44%   |
| HP Presario           | 17        | 0.44%   |
| Fujitsu LIFEBOOK      | 16        | 0.41%   |
| ASUS ASUS             | 16        | 0.41%   |
| Acer Nitro            | 16        | 0.41%   |
| HP OMEN               | 14        | 0.36%   |
| Dell System           | 13        | 0.33%   |
| Apple MacBookPro9     | 13        | 0.33%   |
| Apple MacBookPro5     | 12        | 0.31%   |
| Apple MacBookPro12    | 12        | 0.31%   |
| Lenovo V145-15AST     | 11        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 346       | 8.91%   |
| 2019    | 331       | 8.53%   |
| 2020    | 307       | 7.91%   |
| 2012    | 292       | 7.52%   |
| 2021    | 271       | 6.98%   |
| 2013    | 271       | 6.98%   |
| 2011    | 254       | 6.54%   |
| 2017    | 249       | 6.41%   |
| 2015    | 240       | 6.18%   |
| 2016    | 223       | 5.74%   |
| 2014    | 222       | 5.72%   |
| 2022    | 204       | 5.26%   |
| 2010    | 188       | 4.84%   |
| 2008    | 166       | 4.28%   |
| 2009    | 142       | 3.66%   |
| 2007    | 93        | 2.4%    |
| 2006    | 39        | 1%      |
| 2023    | 28        | 0.72%   |
| 2005    | 8         | 0.21%   |
| Unknown | 6         | 0.15%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3882      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3489      | 89.03%  |
| Enabled  | 430       | 10.97%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3815      | 98.27%  |
| Yes  | 67        | 1.73%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1125      | 28.57%  |
| 3.01-4.0    | 777       | 19.73%  |
| 16.01-24.0  | 722       | 18.33%  |
| 8.01-16.0   | 648       | 16.46%  |
| 32.01-64.0  | 244       | 6.2%    |
| 1.01-2.0    | 220       | 5.59%   |
| 2.01-3.0    | 91        | 2.31%   |
| 64.01-256.0 | 42        | 1.07%   |
| 24.01-32.0  | 37        | 0.94%   |
| 0.51-1.0    | 31        | 0.79%   |
| 0.01-0.5    | 1         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1616      | 37.65%  |
| 2.01-3.0   | 1074      | 25.02%  |
| 4.01-8.0   | 589       | 13.72%  |
| 3.01-4.0   | 536       | 12.49%  |
| 0.51-1.0   | 276       | 6.43%   |
| 8.01-16.0  | 137       | 3.19%   |
| 0.01-0.5   | 37        | 0.86%   |
| 16.01-24.0 | 17        | 0.4%    |
| 24.01-32.0 | 7         | 0.16%   |
| 32.01-64.0 | 2         | 0.05%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2871      | 72.35%  |
| 2      | 926       | 23.34%  |
| 3      | 104       | 2.62%   |
| 0      | 36        | 0.91%   |
| 4      | 21        | 0.53%   |
| 5      | 4         | 0.1%    |
| 7      | 3         | 0.08%   |
| 9      | 1         | 0.03%   |
| 8      | 1         | 0.03%   |
| 6      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2517      | 64.52%  |
| Yes       | 1384      | 35.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2976      | 76.41%  |
| No        | 919       | 23.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3827      | 98.53%  |
| No        | 57        | 1.47%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3031      | 77.32%  |
| No        | 889       | 22.68%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UK      | 3882      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| London              | 263       | 6.14%   |
| Manchester          | 83        | 1.94%   |
| Birmingham          | 79        | 1.84%   |
| Glasgow             | 70        | 1.63%   |
| Edinburgh           | 67        | 1.56%   |
| Bristol             | 54        | 1.26%   |
| Leeds               | 51        | 1.19%   |
| Liverpool           | 47        | 1.1%    |
| Sheffield           | 46        | 1.07%   |
| Nottingham          | 46        | 1.07%   |
| Islington           | 43        | 1%      |
| Reading             | 38        | 0.89%   |
| Cambridge           | 36        | 0.84%   |
| Norwich             | 33        | 0.77%   |
| Coventry            | 33        | 0.77%   |
| Leicester           | 30        | 0.7%    |
| Oxford              | 29        | 0.68%   |
| Aberdeen            | 28        | 0.65%   |
| Southampton         | 27        | 0.63%   |
| Croydon             | 27        | 0.63%   |
| Milton Keynes       | 25        | 0.58%   |
| Cardiff             | 25        | 0.58%   |
| Bradford            | 23        | 0.54%   |
| York                | 22        | 0.51%   |
| Plymouth            | 22        | 0.51%   |
| Gloucester          | 22        | 0.51%   |
| Brighton            | 22        | 0.51%   |
| Chesterfield        | 21        | 0.49%   |
| Bolton              | 21        | 0.49%   |
| Swindon             | 20        | 0.47%   |
| Newcastle upon Tyne | 20        | 0.47%   |
| Kensington          | 20        | 0.47%   |
| Hackney             | 20        | 0.47%   |
| Wigan               | 19        | 0.44%   |
| Harrow              | 19        | 0.44%   |
| Colchester          | 19        | 0.44%   |
| Wolverhampton       | 18        | 0.42%   |
| Walsall             | 18        | 0.42%   |
| Derby               | 18        | 0.42%   |
| Bromley             | 18        | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 750       | 998    | 15.71%  |
| Seagate                     | 463       | 632    | 9.7%    |
| WDC                         | 461       | 589    | 9.66%   |
| Unknown                     | 424       | 553    | 8.88%   |
| Toshiba                     | 414       | 509    | 8.67%   |
| SanDisk                     | 297       | 367    | 6.22%   |
| Crucial                     | 202       | 278    | 4.23%   |
| SK hynix                    | 201       | 235    | 4.21%   |
| Kingston                    | 187       | 230    | 3.92%   |
| Hitachi                     | 174       | 206    | 3.64%   |
| Intel                       | 141       | 166    | 2.95%   |
| HGST                        | 121       | 176    | 2.53%   |
| Micron Technology           | 97        | 116    | 2.03%   |
| Apple                       | 58        | 75     | 1.21%   |
| KIOXIA                      | 50        | 61     | 1.05%   |
| Phison                      | 44        | 52     | 0.92%   |
| China                       | 40        | 58     | 0.84%   |
| Phison Electronics          | 38        | 44     | 0.8%    |
| A-DATA Technology           | 37        | 44     | 0.78%   |
| LITEON                      | 35        | 44     | 0.73%   |
| PNY                         | 31        | 37     | 0.65%   |
| Fujitsu                     | 30        | 37     | 0.63%   |
| Unknown                     | 28        | 32     | 0.59%   |
| Transcend                   | 27        | 34     | 0.57%   |
| LITEONIT                    | 24        | 30     | 0.5%    |
| Micron/Crucial Technology   | 23        | 24     | 0.48%   |
| Silicon Motion              | 22        | 26     | 0.46%   |
| Kingston Technology Company | 21        | 23     | 0.44%   |
| O2 Micro                    | 14        | 15     | 0.29%   |
| Integral                    | 14        | 15     | 0.29%   |
| OCZ                         | 12        | 13     | 0.25%   |
| Lenovo                      | 12        | 13     | 0.25%   |
| SPCC                        | 10        | 16     | 0.21%   |
| JMicron Technology          | 9         | 14     | 0.19%   |
| Corsair                     | 9         | 13     | 0.19%   |
| Team                        | 8         | 9      | 0.17%   |
| SABRENT                     | 8         | 8      | 0.17%   |
| Realtek                     | 8         | 8      | 0.17%   |
| TCSUNBOW                    | 7         | 11     | 0.15%   |
| Patriot                     | 7         | 12     | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 95        | 1.9%    |
| Seagate ST1000LM035-1RK172 1TB                      | 62        | 1.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 53        | 1.06%   |
| Toshiba MQ01ABD100 1TB                              | 50        | 1%      |
| Unknown MMC Card  64GB                              | 48        | 0.96%   |
| Unknown MMC Card  128GB                             | 39        | 0.78%   |
| Samsung NVMe SSD Drive 512GB                        | 37        | 0.74%   |
| Toshiba MQ01ABF050 500GB                            | 33        | 0.66%   |
| Unknown MMC Card  512GB                             | 31        | 0.62%   |
| HGST HTS721010A9E630 1TB                            | 31        | 0.62%   |
| Unknown MMC Card  16GB                              | 30        | 0.6%    |
| HGST HTS541010A9E680 1TB                            | 30        | 0.6%    |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 29        | 0.58%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 29        | 0.58%   |
| Samsung SSD 850 EVO 500GB                           | 28        | 0.56%   |
| Unknown                                             | 28        | 0.56%   |
| Kingston SA400S37240G 240GB SSD                     | 26        | 0.52%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD                 | 25        | 0.5%    |
| Samsung SSD 860 EVO 500GB                           | 25        | 0.5%    |
| Crucial CT500MX500SSD1 500GB                        | 25        | 0.5%    |
| Samsung SSD 850 EVO 250GB                           | 24        | 0.48%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 24        | 0.48%   |
| Kingston SA400S37120G 120GB SSD                     | 24        | 0.48%   |
| SanDisk NVMe SSD Drive 512GB                        | 22        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 22        | 0.44%   |
| Unknown SD/MMC/MS PRO 1GB                           | 21        | 0.42%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 21        | 0.42%   |
| Samsung SSD 970 EVO Plus 1TB                        | 21        | 0.42%   |
| Toshiba MQ04ABF100 1TB                              | 20        | 0.4%    |
| Seagate ST500LT012-1DG142 500GB                     | 20        | 0.4%    |
| Samsung NVMe SSD Drive 1024GB                       | 20        | 0.4%    |
| Kingston SA400S37480G 480GB SSD                     | 20        | 0.4%    |
| Seagate ST9500325AS 500GB                           | 19        | 0.38%   |
| SK hynix NVMe SSD Drive 512GB                       | 18        | 0.36%   |
| Crucial CT250MX500SSD1 250GB                        | 18        | 0.36%   |
| Crucial CT240BX500SSD1 240GB                        | 18        | 0.36%   |
| Toshiba NVMe SSD Drive 512GB                        | 17        | 0.34%   |
| SanDisk NVMe SSD Drive 256GB                        | 17        | 0.34%   |
| Samsung NVMe SSD Drive 1TB                          | 17        | 0.34%   |
| Seagate Expansion 2TB                               | 16        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 449       | 611    | 31.73%  |
| WDC                 | 275       | 350    | 19.43%  |
| Toshiba             | 267       | 319    | 18.87%  |
| Hitachi             | 174       | 206    | 12.3%   |
| HGST                | 121       | 176    | 8.55%   |
| Samsung Electronics | 45        | 50     | 3.18%   |
| Fujitsu             | 30        | 37     | 2.12%   |
| Unknown             | 21        | 24     | 1.48%   |
| SABRENT             | 7         | 7      | 0.49%   |
| Apple               | 7         | 7      | 0.49%   |
| SSK                 | 3         | 4      | 0.21%   |
| Initio              | 2         | 2      | 0.14%   |
| IBM/Hitachi         | 2         | 2      | 0.14%   |
| ASMT                | 2         | 25     | 0.14%   |
| USB3.0              | 1         | 1      | 0.07%   |
| PHD 3.0             | 1         | 1      | 0.07%   |
| Maxone              | 1         | 1      | 0.07%   |
| LaCie               | 1         | 1      | 0.07%   |
| JMicron Technology  | 1         | 4      | 0.07%   |
| Intenso             | 1         | 1      | 0.07%   |
| HGST HTS            | 1         | 1      | 0.07%   |
| Generic-            | 1         | 1      | 0.07%   |
| External            | 1         | 1      | 0.07%   |
| ASMedia             | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 332       | 451    | 21.83%  |
| Crucial             | 186       | 259    | 12.23%  |
| SanDisk             | 170       | 207    | 11.18%  |
| Kingston            | 147       | 177    | 9.66%   |
| WDC                 | 85        | 120    | 5.59%   |
| Intel               | 53        | 57     | 3.48%   |
| Micron Technology   | 45        | 53     | 2.96%   |
| SK hynix            | 42        | 52     | 2.76%   |
| Toshiba             | 38        | 51     | 2.5%    |
| China               | 38        | 53     | 2.5%    |
| LITEON              | 33        | 42     | 2.17%   |
| Apple               | 33        | 42     | 2.17%   |
| PNY                 | 30        | 35     | 1.97%   |
| A-DATA Technology   | 28        | 33     | 1.84%   |
| Transcend           | 27        | 34     | 1.78%   |
| LITEONIT            | 24        | 30     | 1.58%   |
| Integral            | 14        | 15     | 0.92%   |
| OCZ                 | 12        | 13     | 0.79%   |
| SPCC                | 9         | 14     | 0.59%   |
| Seagate             | 9         | 9      | 0.59%   |
| Unknown             | 7         | 7      | 0.46%   |
| Team                | 7         | 8      | 0.46%   |
| Patriot             | 7         | 12     | 0.46%   |
| TCSUNBOW            | 6         | 10     | 0.39%   |
| Star                | 6         | 7      | 0.39%   |
| Netac               | 6         | 9      | 0.39%   |
| Drevo               | 6         | 9      | 0.39%   |
| Corsair             | 6         | 10     | 0.39%   |
| BHT                 | 6         | 9      | 0.39%   |
| Gigabyte Technology | 5         | 5      | 0.33%   |
| ORTIAL              | 4         | 4      | 0.26%   |
| Lexar               | 4         | 5      | 0.26%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.26%   |
| BIWIN               | 4         | 4      | 0.26%   |
| ZTC                 | 3         | 6      | 0.2%    |
| Zheino              | 3         | 5      | 0.2%    |
| Vaseky              | 3         | 4      | 0.2%    |
| TO Exter            | 3         | 3      | 0.2%    |
| ShiJi               | 3         | 3      | 0.2%    |
| Plextor             | 3         | 4      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1382      | 1964   | 30.58%  |
| HDD     | 1368      | 1833   | 30.27%  |
| NVMe    | 1296      | 1696   | 28.68%  |
| MMC     | 424       | 551    | 9.38%   |
| Unknown | 49        | 61     | 1.08%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2523      | 3647   | 57.48%  |
| NVMe | 1293      | 1687   | 29.46%  |
| MMC  | 424       | 551    | 9.66%   |
| SAS  | 149       | 220    | 3.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1897      | 2593   | 68.53%  |
| 0.51-1.0   | 735       | 994    | 26.55%  |
| 1.01-2.0   | 116       | 161    | 4.19%   |
| 3.01-4.0   | 11        | 34     | 0.4%    |
| 4.01-10.0  | 8         | 14     | 0.29%   |
| 2.01-3.0   | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1222      | 29.82%  |
| 251-500        | 952       | 23.23%  |
| 501-1000       | 607       | 14.81%  |
| 1-20           | 319       | 7.78%   |
| 51-100         | 292       | 7.13%   |
| 21-50          | 245       | 5.98%   |
| 1001-2000      | 221       | 5.39%   |
| Unknown        | 108       | 2.64%   |
| More than 3000 | 78        | 1.9%    |
| 2001-3000      | 54        | 1.32%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1810      | 42.66%  |
| 21-50          | 794       | 18.71%  |
| 101-250        | 531       | 12.51%  |
| 51-100         | 480       | 11.31%  |
| 251-500        | 287       | 6.76%   |
| 501-1000       | 142       | 3.35%   |
| Unknown        | 108       | 2.55%   |
| 1001-2000      | 58        | 1.37%   |
| More than 3000 | 17        | 0.4%    |
| 2001-3000      | 15        | 0.35%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                 | 6         | 6      | 3.13%   |
| HGST HTS725050A7E630 500GB                     | 6         | 9      | 3.13%   |
| Seagate ST9500325AS 500GB                      | 5         | 9      | 2.6%    |
| Hitachi HTS547575A9E384 752GB                  | 5         | 7      | 2.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 4         | 5      | 2.08%   |
| Toshiba MK1656GSY 160GB                        | 3         | 3      | 1.56%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 3      | 1.56%   |
| Intel SSDSC2BF180A5L 180GB                     | 3         | 3      | 1.56%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 1.56%   |
| WDC WD2500BEVT-80A23T0 250GB                   | 2         | 5      | 1.04%   |
| Toshiba MK3256GSY 320GB                        | 2         | 3      | 1.04%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 1.04%   |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 3      | 1.04%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 1.04%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 2      | 1.04%   |
| LITEON CS1-SP32-11 M.2 2242 32GB SSD           | 2         | 2      | 1.04%   |
| Hitachi HTS547564A9E384 640GB                  | 2         | 2      | 1.04%   |
| Hitachi HTS545050A7E380 500GB                  | 2         | 2      | 1.04%   |
| Hitachi HTS545032B9A302 320GB                  | 2         | 3      | 1.04%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 1.04%   |
| Hitachi HTS545025B9A300 250GB                  | 2         | 2      | 1.04%   |
| Hitachi HTS543216L9A300 160GB                  | 2         | 2      | 1.04%   |
| Hitachi HTS542512K9SA00 120GB                  | 2         | 2      | 1.04%   |
| Hitachi HTS541680J9SA00 80GB                   | 2         | 2      | 1.04%   |
| HGST HTS721010A9E630 1TB                       | 2         | 2      | 1.04%   |
| Drevo X1 SSD 64GB                              | 2         | 2      | 1.04%   |
| Crucial CT525MX300SSD4 528GB                   | 2         | 2      | 1.04%   |
| Zheino CHN mSATA02M 256 256GB SSD              | 1         | 2      | 0.52%   |
| WDC WD7500BPVT-60HXZT3 752GB                   | 1         | 1      | 0.52%   |
| WDC WD5000BPVT-55HXZT3 500GB                   | 1         | 1      | 0.52%   |
| WDC WD5000BEVT-75A0RT0 500GB                   | 1         | 1      | 0.52%   |
| WDC WD5000BEVT-60A0RT0 500GB                   | 1         | 2      | 0.52%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 0.52%   |
| WDC WD5000BEKT-75KA9T0 500GB                   | 1         | 1      | 0.52%   |
| WDC WD3200LPCX-24C6HT0 320GB                   | 1         | 1      | 0.52%   |
| WDC WD3200BEKT-75PVMT0 320GB                   | 1         | 1      | 0.52%   |
| WDC WD3200BEKT-60PVMT0 320GB                   | 1         | 1      | 0.52%   |
| WDC WD2500BEVT-75A23T0 250GB                   | 1         | 1      | 0.52%   |
| WDC WD2500BEVT-60A23T0 250GB                   | 1         | 1      | 0.52%   |
| WDC WD2500BEKT-60PVMT0 250GB                   | 1         | 1      | 0.52%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 54     | 24.61%  |
| Hitachi             | 33        | 36     | 17.28%  |
| Toshiba             | 22        | 23     | 11.52%  |
| HGST                | 15        | 18     | 7.85%   |
| WDC                 | 14        | 19     | 7.33%   |
| Samsung Electronics | 10        | 11     | 5.24%   |
| Crucial             | 10        | 10     | 5.24%   |
| Intel               | 7         | 7      | 3.66%   |
| Kingston            | 5         | 6      | 2.62%   |
| SanDisk             | 4         | 4      | 2.09%   |
| Fujitsu             | 4         | 4      | 2.09%   |
| Micron Technology   | 3         | 3      | 1.57%   |
| LITEON              | 3         | 3      | 1.57%   |
| SK hynix            | 2         | 2      | 1.05%   |
| Drevo               | 2         | 2      | 1.05%   |
| A-DATA Technology   | 2         | 2      | 1.05%   |
| Zheino              | 1         | 2      | 0.52%   |
| Team                | 1         | 1      | 0.52%   |
| OCZ                 | 1         | 1      | 0.52%   |
| LITEONIT            | 1         | 1      | 0.52%   |
| Corsair             | 1         | 1      | 0.52%   |
| China               | 1         | 1      | 0.52%   |
| BAITITON            | 1         | 1      | 0.52%   |
| 2-Power             | 1         | 1      | 0.52%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 54     | 34.56%  |
| Hitachi             | 33        | 36     | 24.26%  |
| Toshiba             | 20        | 21     | 14.71%  |
| HGST                | 15        | 18     | 11.03%  |
| WDC                 | 13        | 18     | 9.56%   |
| Samsung Electronics | 4         | 4      | 2.94%   |
| Fujitsu             | 4         | 4      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 135       | 155    | 71.05%  |
| SSD  | 52        | 55     | 27.37%  |
| NVMe | 3         | 3      | 1.58%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Union Memory (Shenzhen) RPFTJ128PDD2EWX 128GB | 1         | 1      | 33.33%  |
| Toshiba THNSN5512GPUK NVMe 512GB              | 1         | 2      | 33.33%  |
| Toshiba MQ01ABD100 1TB                        | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Notebooks | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Toshiba                 | 2         | 3      | 66.67%  |
| Union Memory (Shenzhen) | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2552      | 4075   | 62.6%   |
| Works    | 1335      | 1813   | 32.74%  |
| Malfunc  | 187       | 213    | 4.59%   |
| Failed   | 3         | 4      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2626      | 58.91%  |
| AMD                              | 438       | 9.83%   |
| Samsung Electronics              | 430       | 9.65%   |
| SanDisk                          | 217       | 4.87%   |
| SK hynix                         | 155       | 3.48%   |
| Toshiba America Info Systems     | 116       | 2.6%    |
| Phison Electronics               | 90        | 2.02%   |
| Kingston Technology Company      | 61        | 1.37%   |
| Micron Technology                | 54        | 1.21%   |
| KIOXIA                           | 49        | 1.1%    |
| Nvidia                           | 37        | 0.83%   |
| Micron/Crucial Technology        | 37        | 0.83%   |
| Silicon Motion                   | 24        | 0.54%   |
| Apple                            | 16        | 0.36%   |
| O2 Micro                         | 14        | 0.31%   |
| ADATA Technology                 | 14        | 0.31%   |
| Silicon Integrated Systems [SiS] | 12        | 0.27%   |
| Lenovo                           | 11        | 0.25%   |
| Solid State Storage Technology   | 10        | 0.22%   |
| Union Memory (Shenzhen)          | 7         | 0.16%   |
| Shenzhen Longsys Electronics     | 5         | 0.11%   |
| Marvell Technology Group         | 5         | 0.11%   |
| Lite-On Technology               | 5         | 0.11%   |
| VIA Technologies                 | 4         | 0.09%   |
| Yangtze Memory Technologies      | 3         | 0.07%   |
| Realtek Semiconductor            | 3         | 0.07%   |
| JMicron Technology               | 3         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| Biwin Storage Technology         | 2         | 0.04%   |
| ASMedia Technology               | 2         | 0.04%   |
| Silicon Image                    | 1         | 0.02%   |
| Seagate Technology               | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| INNOGRIT                         | 1         | 0.02%   |
| Enmotus                          | 1         | 0.02%   |
| Unknown                          | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 370       | 7.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 296       | 6.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 257       | 5.37%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 254       | 5.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 200       | 4.18%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 188       | 3.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 167       | 3.49%   |
| Intel Volume Management Device NVMe RAID Controller                              | 127       | 2.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 127       | 2.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 116       | 2.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 114       | 2.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 89        | 1.86%   |
| Samsung NVMe SSD Controller 980                                                  | 86        | 1.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 81        | 1.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 76        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 76        | 1.59%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 71        | 1.48%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 64        | 1.34%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 58        | 1.21%   |
| Intel Comet Lake SATA AHCI Controller                                            | 54        | 1.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 53        | 1.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 50        | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 49        | 1.02%   |
| Phison PS5013 E13 NVMe Controller                                                | 49        | 1.02%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 49        | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 48        | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 46        | 0.96%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 45        | 0.94%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 44        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 42        | 0.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 40        | 0.84%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 38        | 0.79%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 37        | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 37        | 0.77%   |
| Intel Tiger Lake-LP SATA Controller                                              | 35        | 0.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 34        | 0.71%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 30        | 0.63%   |
| Intel SSD 660P Series                                                            | 28        | 0.58%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 27        | 0.56%   |
| Phison E12 NVMe Controller                                                       | 26        | 0.54%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2579      | 56.25%  |
| NVMe | 1306      | 28.48%  |
| RAID | 394       | 8.59%   |
| IDE  | 306       | 6.67%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3199      | 82.41%  |
| AMD    | 682       | 17.57%  |
| ARM    | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 91        | 2.34%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 58        | 1.49%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 53        | 1.36%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 51        | 1.31%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 50        | 1.29%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 48        | 1.24%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 45        | 1.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 45        | 1.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 45        | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 44        | 1.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 41        | 1.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 40        | 1.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 39        | 1%      |
| Intel Core i5-8265U CPU @ 1.60GHz             | 39        | 1%      |
| Intel Core i5-3210M CPU @ 2.50GHz             | 39        | 1%      |
| Intel Core i5-2520M CPU @ 2.50GHz             | 38        | 0.98%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 37        | 0.95%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 37        | 0.95%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 37        | 0.95%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 37        | 0.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 36        | 0.93%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 32        | 0.82%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 32        | 0.82%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 29        | 0.75%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 28        | 0.72%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.72%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 28        | 0.72%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 27        | 0.69%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 26        | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 23        | 0.59%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 23        | 0.59%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 22        | 0.57%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 21        | 0.54%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 21        | 0.54%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 21        | 0.54%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.54%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 20        | 0.51%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 20        | 0.51%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 20        | 0.51%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 20        | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 922       | 23.74%  |
| Intel Core i7           | 851       | 21.91%  |
| Other                   | 383       | 9.86%   |
| Intel Celeron           | 270       | 6.95%   |
| Intel Core i3           | 263       | 6.77%   |
| Intel Core 2 Duo        | 204       | 5.25%   |
| Intel Pentium           | 109       | 2.81%   |
| AMD Ryzen 7             | 109       | 2.81%   |
| AMD Ryzen 5             | 107       | 2.75%   |
| Intel Atom              | 79        | 2.03%   |
| AMD A6                  | 60        | 1.54%   |
| AMD A8                  | 41        | 1.06%   |
| Intel Pentium Dual-Core | 37        | 0.95%   |
| Intel Core 2            | 31        | 0.8%    |
| AMD Ryzen 3             | 31        | 0.8%    |
| Intel Pentium Dual      | 27        | 0.7%    |
| AMD A4                  | 27        | 0.7%    |
| Intel Genuine           | 25        | 0.64%   |
| AMD Ryzen 9             | 25        | 0.64%   |
| Intel Core i9           | 21        | 0.54%   |
| Intel Celeron Dual-Core | 20        | 0.51%   |
| AMD E1                  | 20        | 0.51%   |
| AMD A10                 | 17        | 0.44%   |
| AMD E                   | 16        | 0.41%   |
| Intel Pentium Silver    | 15        | 0.39%   |
| Intel Celeron M         | 14        | 0.36%   |
| AMD Ryzen 7 PRO         | 14        | 0.36%   |
| AMD E2                  | 14        | 0.36%   |
| Intel Pentium M         | 10        | 0.26%   |
| AMD Athlon              | 9         | 0.23%   |
| AMD Turion 64 X2 Mobile | 8         | 0.21%   |
| AMD FX                  | 7         | 0.18%   |
| AMD Athlon X2           | 7         | 0.18%   |
| AMD Athlon II           | 7         | 0.18%   |
| AMD Turion 64 Mobile    | 6         | 0.15%   |
| Intel Pentium Gold      | 5         | 0.13%   |
| Intel Core m3           | 5         | 0.13%   |
| Intel Core M            | 5         | 0.13%   |
| AMD Ryzen 5 PRO         | 5         | 0.13%   |
| AMD Phenom II           | 5         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2076      | 53.46%  |
| 4      | 1216      | 31.32%  |
| 6      | 212       | 5.46%   |
| 8      | 196       | 5.05%   |
| 1      | 105       | 2.7%    |
| 14     | 31        | 0.8%    |
| 12     | 25        | 0.64%   |
| 10     | 19        | 0.49%   |
| 3      | 2         | 0.05%   |
| 16     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3881      | 99.97%  |
| 2      | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2747      | 70.71%  |
| 1      | 1138      | 29.29%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3780      | 97.07%  |
| Unknown        | 58        | 1.49%   |
| 32-bit         | 56        | 1.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1134      | 28.15%  |
| 0x306a9    | 229       | 5.69%   |
| 0x206a7    | 204       | 5.06%   |
| 0x1067a    | 153       | 3.8%    |
| 0x806ec    | 121       | 3%      |
| 0x806ea    | 118       | 2.93%   |
| 0x40651    | 117       | 2.9%    |
| 0x406e3    | 111       | 2.76%   |
| 0x806e9    | 106       | 2.63%   |
| 0x306d4    | 104       | 2.58%   |
| 0x20655    | 95        | 2.36%   |
| 0x806c1    | 91        | 2.26%   |
| 0x906ea    | 87        | 2.16%   |
| 0x6fd      | 69        | 1.71%   |
| 0x406c4    | 65        | 1.61%   |
| 0x306c3    | 64        | 1.59%   |
| 0x30678    | 61        | 1.51%   |
| 0xa0652    | 48        | 1.19%   |
| 0x906e9    | 48        | 1.19%   |
| 0x506e3    | 44        | 1.09%   |
| 0x506c9    | 44        | 1.09%   |
| 0x06006705 | 41        | 1.02%   |
| 0x08108109 | 38        | 0.94%   |
| 0x706e5    | 37        | 0.92%   |
| 0x0a50000c | 36        | 0.89%   |
| 0x08108102 | 36        | 0.89%   |
| 0x406c3    | 33        | 0.82%   |
| 0x20652    | 32        | 0.79%   |
| 0x10676    | 32        | 0.79%   |
| 0x806d1    | 31        | 0.77%   |
| 0x906a3    | 30        | 0.74%   |
| 0x07030105 | 30        | 0.74%   |
| 0x706a1    | 28        | 0.7%    |
| 0x6f6      | 25        | 0.62%   |
| 0x08600106 | 22        | 0.55%   |
| 0x06006704 | 22        | 0.55%   |
| 0x806eb    | 21        | 0.52%   |
| 0x05000119 | 20        | 0.5%    |
| 0x08600104 | 19        | 0.47%   |
| 0x906ed    | 16        | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 699       | 17.99%  |
| IvyBridge        | 291       | 7.49%   |
| SandyBridge      | 263       | 6.77%   |
| Haswell          | 261       | 6.72%   |
| Penryn           | 214       | 5.51%   |
| Skylake          | 210       | 5.4%    |
| Silvermont       | 200       | 5.15%   |
| Unknown          | 182       | 4.68%   |
| Westmere         | 161       | 4.14%   |
| Core             | 150       | 3.86%   |
| TigerLake        | 146       | 3.76%   |
| Broadwell        | 145       | 3.73%   |
| Zen+             | 92        | 2.37%   |
| IceLake          | 87        | 2.24%   |
| Excavator        | 82        | 2.11%   |
| CometLake        | 75        | 1.93%   |
| Zen 2            | 70        | 1.8%    |
| Goldmont plus    | 63        | 1.62%   |
| Zen 3            | 56        | 1.44%   |
| Alderlake Hybrid | 56        | 1.44%   |
| Puma             | 55        | 1.42%   |
| Goldmont         | 52        | 1.34%   |
| P6               | 40        | 1.03%   |
| Zen              | 37        | 0.95%   |
| Bobcat           | 35        | 0.9%    |
| Bonnell          | 31        | 0.8%    |
| Jaguar           | 22        | 0.57%   |
| K10              | 21        | 0.54%   |
| Piledriver       | 20        | 0.51%   |
| K8 Hammer        | 20        | 0.51%   |
| Steamroller      | 14        | 0.36%   |
| K8 & K10 hybrid  | 13        | 0.33%   |
| Nehalem          | 11        | 0.28%   |
| K10 Llano        | 6         | 0.15%   |
| Tremont          | 4         | 0.1%    |
| NetBurst         | 2         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2948      | 63.18%  |
| Nvidia                           | 892       | 19.12%  |
| AMD                              | 809       | 17.34%  |
| Silicon Integrated Systems [SiS] | 12        | 0.26%   |
| VIA Technologies                 | 4         | 0.09%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 276       | 5.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 249       | 5.17%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 172       | 3.57%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 153       | 3.18%   |
| Intel UHD Graphics 620                                                                   | 144       | 2.99%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 134       | 2.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 131       | 2.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 129       | 2.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 128       | 2.66%   |
| Intel HD Graphics 620                                                                    | 119       | 2.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 115       | 2.39%   |
| Intel HD Graphics 5500                                                                   | 109       | 2.26%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 98        | 2.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 98        | 2.03%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 96        | 1.99%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 91        | 1.89%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 89        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 85        | 1.76%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 69        | 1.43%   |
| AMD Renoir                                                                               | 65        | 1.35%   |
| Intel HD Graphics 630                                                                    | 62        | 1.29%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 61        | 1.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 57        | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 57        | 1.18%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 53        | 1.1%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 52        | 1.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 48        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 47        | 0.98%   |
| Intel HD Graphics 530                                                                    | 47        | 0.98%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 44        | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 43        | 0.89%   |
| Intel HD Graphics 500                                                                    | 42        | 0.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 42        | 0.87%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 40        | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 36        | 0.75%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 35        | 0.73%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 33        | 0.69%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 31        | 0.64%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 31        | 0.64%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 30        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2208      | 56.67%  |
| Intel + Nvidia           | 640       | 16.43%  |
| 1 x AMD                  | 639       | 16.4%   |
| 1 x Nvidia               | 192       | 4.93%   |
| Intel + AMD              | 82        | 2.1%    |
| AMD + Nvidia             | 55        | 1.41%   |
| 2 x AMD                  | 33        | 0.85%   |
| 2 x Intel                | 18        | 0.46%   |
| 1 x SiS                  | 12        | 0.31%   |
| Other                    | 8         | 0.21%   |
| 1 x VIA                  | 4         | 0.1%    |
| 2 x Nvidia               | 3         | 0.08%   |
| Intel + 2 x Nvidia       | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 3380      | 86.03%  |
| Proprietary | 465       | 11.84%  |
| Unknown     | 84        | 2.14%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2760      | 69.36%  |
| 0.01-0.5   | 450       | 11.31%  |
| 1.01-2.0   | 320       | 8.04%   |
| 3.01-4.0   | 177       | 4.45%   |
| 0.51-1.0   | 155       | 3.9%    |
| 5.01-6.0   | 63        | 1.58%   |
| 7.01-8.0   | 36        | 0.9%    |
| 2.01-3.0   | 9         | 0.23%   |
| 8.01-16.0  | 9         | 0.23%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 802       | 18.91%  |
| LG Display              | 647       | 15.25%  |
| Chimei Innolux          | 520       | 12.26%  |
| BOE                     | 476       | 11.22%  |
| Samsung Electronics     | 449       | 10.58%  |
| Sharp                   | 196       | 4.62%   |
| Apple                   | 124       | 2.92%   |
| Dell                    | 101       | 2.38%   |
| Lenovo                  | 95        | 2.24%   |
| Chi Mei Optoelectronics | 82        | 1.93%   |
| PANDA                   | 63        | 1.49%   |
| Goldstar                | 60        | 1.41%   |
| LG Philips              | 48        | 1.13%   |
| Valve                   | 47        | 1.11%   |
| Acer                    | 45        | 1.06%   |
| Hewlett-Packard         | 44        | 1.04%   |
| InfoVision              | 35        | 0.83%   |
| BenQ                    | 33        | 0.78%   |
| Iiyama                  | 32        | 0.75%   |
| AOC                     | 31        | 0.73%   |
| Analogix                | 26        | 0.61%   |
| Philips                 | 22        | 0.52%   |
| Ancor Communications    | 21        | 0.5%    |
| CSO                     | 20        | 0.47%   |
| Panasonic               | 18        | 0.42%   |
| Sony                    | 15        | 0.35%   |
| ViewSonic               | 13        | 0.31%   |
| Toshiba                 | 13        | 0.31%   |
| LGD                     | 13        | 0.31%   |
| InnoLux Display         | 12        | 0.28%   |
| HannStar                | 10        | 0.24%   |
| Vestel Elektronik       | 9         | 0.21%   |
| CPT                     | 7         | 0.17%   |
| ASUSTek Computer        | 7         | 0.17%   |
| Seiko/Epson             | 6         | 0.14%   |
| Quanta Display          | 6         | 0.14%   |
| Unknown                 | 5         | 0.12%   |
| JDI                     | 5         | 0.12%   |
| TMX                     | 4         | 0.09%   |
| NEC Computers           | 4         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 47        | 1.1%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 43        | 1%      |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 35        | 0.82%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 32        | 0.75%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 30        | 0.7%    |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 30        | 0.7%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 29        | 0.68%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 26        | 0.61%   |
| Analogix ANX7530 U ANX7539 800x1280                                      | 26        | 0.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 22        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 22        | 0.51%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 21        | 0.49%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 18        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 16        | 0.37%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 16        | 0.37%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 16        | 0.37%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 15        | 0.35%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 15        | 0.35%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 14        | 0.33%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 14        | 0.33%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 14        | 0.33%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 13        | 0.3%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 13        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 13        | 0.3%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 13        | 0.3%    |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                  | 12        | 0.28%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 12        | 0.28%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.28%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 11        | 0.26%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch      | 11        | 0.26%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 11        | 0.26%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 11        | 0.26%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 11        | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 11        | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1530      | 37.84%  |
| 1366x768 (WXGA)    | 1246      | 30.82%  |
| 1280x800 (WXGA)    | 210       | 5.19%   |
| 3840x2160 (4K)     | 184       | 4.55%   |
| 1600x900 (HD+)     | 157       | 3.88%   |
| 2560x1440 (QHD)    | 120       | 2.97%   |
| 1440x900 (WXGA+)   | 79        | 1.95%   |
| 1920x1200 (WUXGA)  | 75        | 1.86%   |
| 800x1280           | 70        | 1.73%   |
| 2560x1600          | 55        | 1.36%   |
| 2880x1800          | 34        | 0.84%   |
| 3840x2400          | 33        | 0.82%   |
| 1680x1050 (WSXGA+) | 31        | 0.77%   |
| 3440x1440          | 25        | 0.62%   |
| 3200x1800 (QHD+)   | 22        | 0.54%   |
| 1024x600           | 20        | 0.49%   |
| 1280x1024 (SXGA)   | 19        | 0.47%   |
| 2160x1440          | 13        | 0.32%   |
| 2560x1080          | 11        | 0.27%   |
| Unknown            | 10        | 0.25%   |
| 2256x1504          | 9         | 0.22%   |
| 1360x768           | 9         | 0.22%   |
| 1920x540           | 7         | 0.17%   |
| 3456x2160          | 6         | 0.15%   |
| 3072x1920          | 6         | 0.15%   |
| 1024x768 (XGA)     | 6         | 0.15%   |
| 2560x1700          | 5         | 0.12%   |
| 1680x945           | 5         | 0.12%   |
| 3000x2000          | 4         | 0.1%    |
| 3840x1080          | 3         | 0.07%   |
| 2880x1920          | 3         | 0.07%   |
| 1920x1280          | 3         | 0.07%   |
| 1280x768           | 3         | 0.07%   |
| 3200x2000          | 2         | 0.05%   |
| 2520x1680          | 2         | 0.05%   |
| 2288x1287          | 2         | 0.05%   |
| 2240x1400          | 2         | 0.05%   |
| 2160x1350          | 2         | 0.05%   |
| 1360x765           | 2         | 0.05%   |
| 8960x2160          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1715      | 40.54%  |
| 13      | 666       | 15.74%  |
| 14      | 426       | 10.07%  |
| 17      | 270       | 6.38%   |
| 12      | 189       | 4.47%   |
| 11      | 120       | 2.84%   |
| 27      | 119       | 2.81%   |
| 24      | 99        | 2.34%   |
| 23      | 76        | 1.8%    |
| 21      | 73        | 1.73%   |
| Unknown | 61        | 1.44%   |
| 7       | 47        | 1.11%   |
| 16      | 45        | 1.06%   |
| 31      | 43        | 1.02%   |
| 34      | 32        | 0.76%   |
| 10      | 32        | 0.76%   |
| 18      | 29        | 0.69%   |
| 3       | 26        | 0.61%   |
| 84      | 22        | 0.52%   |
| 19      | 18        | 0.43%   |
| 25      | 14        | 0.33%   |
| 22      | 13        | 0.31%   |
| 26      | 12        | 0.28%   |
| 72      | 10        | 0.24%   |
| 20      | 8         | 0.19%   |
| 54      | 7         | 0.17%   |
| 40      | 7         | 0.17%   |
| 8       | 7         | 0.17%   |
| 48      | 6         | 0.14%   |
| 32      | 5         | 0.12%   |
| 65      | 4         | 0.09%   |
| 50      | 3         | 0.07%   |
| 35      | 3         | 0.07%   |
| 33      | 3         | 0.07%   |
| 28      | 3         | 0.07%   |
| 142     | 2         | 0.05%   |
| 49      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 39      | 2         | 0.05%   |
| 99      | 1         | 0.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2402      | 57.08%  |
| 201-300        | 730       | 17.35%  |
| 351-400        | 343       | 8.15%   |
| 501-600        | 294       | 6.99%   |
| 401-500        | 125       | 2.97%   |
| 1-100          | 70        | 1.66%   |
| Unknown        | 61        | 1.45%   |
| 601-700        | 58        | 1.38%   |
| 701-800        | 40        | 0.95%   |
| 1501-2000      | 34        | 0.81%   |
| 1001-1500      | 26        | 0.62%   |
| 801-900        | 12        | 0.29%   |
| 101-200        | 7         | 0.17%   |
| More than 2000 | 3         | 0.07%   |
| 901-1000       | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3076      | 80.1%   |
| 16/10   | 507       | 13.2%   |
| Unknown | 55        | 1.43%   |
| 3/2     | 50        | 1.3%    |
| 0.67    | 47        | 1.22%   |
| 21/9    | 38        | 0.99%   |
| 6/5     | 29        | 0.76%   |
| 5/4     | 16        | 0.42%   |
| 4/3     | 13        | 0.34%   |
| 32/9    | 3         | 0.08%   |
| 1.00    | 3         | 0.08%   |
| 0.62    | 2         | 0.05%   |
| 3.40    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1710      | 40.5%   |
| 81-90          | 777       | 18.4%   |
| 71-80          | 314       | 7.44%   |
| 121-130        | 222       | 5.26%   |
| 201-250        | 217       | 5.14%   |
| 61-70          | 181       | 4.29%   |
| 301-350        | 129       | 3.06%   |
| 51-60          | 122       | 2.89%   |
| 351-500        | 88        | 2.08%   |
| 1-40           | 77        | 1.82%   |
| Unknown        | 61        | 1.44%   |
| More than 1000 | 58        | 1.37%   |
| 131-140        | 46        | 1.09%   |
| 111-120        | 46        | 1.09%   |
| 151-200        | 43        | 1.02%   |
| 251-300        | 40        | 0.95%   |
| 41-50          | 31        | 0.73%   |
| 141-150        | 30        | 0.71%   |
| 501-1000       | 17        | 0.4%    |
| 91-100         | 13        | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1586      | 37.99%  |
| 101-120       | 1254      | 30.04%  |
| 51-100        | 591       | 14.16%  |
| 161-240       | 425       | 10.18%  |
| More than 240 | 213       | 5.1%    |
| Unknown       | 61        | 1.46%   |
| 1-50          | 45        | 1.08%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3301      | 83.59%  |
| 2     | 515       | 13.04%  |
| 0     | 82        | 2.08%   |
| 3     | 46        | 1.16%   |
| 4     | 4         | 0.1%    |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2120      | 35.19%  |
| Realtek Semiconductor             | 1842      | 30.58%  |
| Qualcomm Atheros                  | 817       | 13.56%  |
| Broadcom                          | 447       | 7.42%   |
| Broadcom Limited                  | 102       | 1.69%   |
| Marvell Technology Group          | 90        | 1.49%   |
| MediaTek                          | 53        | 0.88%   |
| Ralink Technology                 | 52        | 0.86%   |
| Ralink                            | 45        | 0.75%   |
| TP-Link                           | 44        | 0.73%   |
| Ericsson Business Mobile Networks | 41        | 0.68%   |
| Dell                              | 34        | 0.56%   |
| ASIX Electronics                  | 31        | 0.51%   |
| Nvidia                            | 27        | 0.45%   |
| DisplayLink                       | 26        | 0.43%   |
| Lenovo                            | 25        | 0.42%   |
| Qualcomm                          | 24        | 0.4%    |
| Samsung Electronics               | 21        | 0.35%   |
| Hewlett-Packard                   | 19        | 0.32%   |
| Sierra Wireless                   | 15        | 0.25%   |
| Huawei Technologies               | 12        | 0.2%    |
| Silicon Integrated Systems [SiS]  | 11        | 0.18%   |
| JMicron Technology                | 11        | 0.18%   |
| NetGear                           | 8         | 0.13%   |
| Edimax Technology                 | 8         | 0.13%   |
| Qualcomm Atheros Communications   | 6         | 0.1%    |
| Google                            | 6         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 5         | 0.08%   |
| Micro Star International          | 5         | 0.08%   |
| ICS Advent                        | 5         | 0.08%   |
| Belkin Components                 | 5         | 0.08%   |
| Attansic Technology               | 5         | 0.08%   |
| ASUSTek Computer                  | 5         | 0.08%   |
| Apple                             | 5         | 0.08%   |
| VIA Technologies                  | 4         | 0.07%   |
| Fibocom                           | 4         | 0.07%   |
| Xiaomi                            | 3         | 0.05%   |
| OPPO Electronics                  | 3         | 0.05%   |
| Motorola PCS                      | 3         | 0.05%   |
| AMD                               | 3         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 987       | 13.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 389       | 5.33%   |
| Intel Wi-Fi 6 AX200                                                     | 181       | 2.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 167       | 2.29%   |
| Intel Wireless 8265 / 8275                                              | 164       | 2.25%   |
| Intel Wireless 7265                                                     | 149       | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 147       | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 142       | 1.95%   |
| Intel Wireless 7260                                                     | 141       | 1.93%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 137       | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 133       | 1.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 123       | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 121       | 1.66%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 113       | 1.55%   |
| Intel Wireless 8260                                                     | 101       | 1.38%   |
| Intel Wi-Fi 6 AX201                                                     | 96        | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 90        | 1.23%   |
| Intel Wireless 3165                                                     | 87        | 1.19%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 84        | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 75        | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                           | 69        | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 68        | 0.93%   |
| Intel 82577LM Gigabit Network Connection                                | 67        | 0.92%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 0.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 65        | 0.89%   |
| Intel Ethernet Connection I218-LM                                       | 62        | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                                   | 62        | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 59        | 0.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 55        | 0.75%   |
| Intel Wireless 3160                                                     | 53        | 0.73%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 49        | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 48        | 0.66%   |
| Intel Wireless-AC 9260                                                  | 48        | 0.66%   |
| Intel WiFi Link 5100                                                    | 47        | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 47        | 0.64%   |
| Intel Centrino Ultimate-N 6300                                          | 46        | 0.63%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 45        | 0.62%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 44        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                                   | 44        | 0.6%    |
| Intel Ethernet Connection I219-LM                                       | 43        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2034      | 49.98%  |
| Qualcomm Atheros                  | 707       | 17.37%  |
| Realtek Semiconductor             | 616       | 15.14%  |
| Broadcom                          | 341       | 8.38%   |
| Broadcom Limited                  | 79        | 1.94%   |
| Ralink Technology                 | 52        | 1.28%   |
| MediaTek                          | 48        | 1.18%   |
| Ralink                            | 45        | 1.11%   |
| TP-Link                           | 37        | 0.91%   |
| Dell                              | 18        | 0.44%   |
| Sierra Wireless                   | 15        | 0.37%   |
| Qualcomm                          | 13        | 0.32%   |
| NetGear                           | 8         | 0.2%    |
| Ericsson Business Mobile Networks | 8         | 0.2%    |
| Edimax Technology                 | 8         | 0.2%    |
| Qualcomm Atheros Communications   | 6         | 0.15%   |
| Micro Star International          | 5         | 0.12%   |
| Belkin Components                 | 5         | 0.12%   |
| Fibocom                           | 4         | 0.1%    |
| ASUSTek Computer                  | 4         | 0.1%    |
| Wacom                             | 2         | 0.05%   |
| Hewlett-Packard                   | 2         | 0.05%   |
| D-Link                            | 2         | 0.05%   |
| ZyDAS                             | 1         | 0.02%   |
| Senao                             | 1         | 0.02%   |
| Qualcomm Technologies             | 1         | 0.02%   |
| Microsoft                         | 1         | 0.02%   |
| Marvell Technology Group          | 1         | 0.02%   |
| Linksys                           | 1         | 0.02%   |
| InProComm                         | 1         | 0.02%   |
| Fujitsu Siemens Computers         | 1         | 0.02%   |
| Askey Computer                    | 1         | 0.02%   |
| Apple                             | 1         | 0.02%   |
| 3Com                              | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 181       | 4.42%   |
| Intel Wireless 8265 / 8275                                              | 164       | 4.01%   |
| Intel Wireless 7265                                                     | 149       | 3.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 147       | 3.59%   |
| Intel Wireless 7260                                                     | 141       | 3.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 137       | 3.35%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 133       | 3.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 123       | 3.01%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 121       | 2.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 113       | 2.76%   |
| Intel Wireless 8260                                                     | 101       | 2.47%   |
| Intel Wi-Fi 6 AX201                                                     | 96        | 2.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 90        | 2.2%    |
| Intel Wireless 3165                                                     | 87        | 2.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 84        | 2.05%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 75        | 1.83%   |
| Broadcom BCM43142 802.11b/g/n                                           | 69        | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 68        | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 65        | 1.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 59        | 1.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 55        | 1.34%   |
| Intel Wireless 3160                                                     | 53        | 1.29%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 49        | 1.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 48        | 1.17%   |
| Intel Wireless-AC 9260                                                  | 48        | 1.17%   |
| Intel WiFi Link 5100                                                    | 47        | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 47        | 1.15%   |
| Intel Centrino Ultimate-N 6300                                          | 46        | 1.12%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 45        | 1.1%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 44        | 1.08%   |
| Intel Centrino Advanced-N 6200                                          | 42        | 1.03%   |
| Intel Centrino Advanced-N 6235                                          | 40        | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 38        | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 38        | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 33        | 0.81%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 32        | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 31        | 0.76%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 31        | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 29        | 0.71%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1580      | 51.35%  |
| Intel                            | 773       | 25.12%  |
| Qualcomm Atheros                 | 203       | 6.6%    |
| Broadcom                         | 173       | 5.62%   |
| Marvell Technology Group         | 89        | 2.89%   |
| ASIX Electronics                 | 31        | 1.01%   |
| Nvidia                           | 27        | 0.88%   |
| DisplayLink                      | 26        | 0.84%   |
| Broadcom Limited                 | 26        | 0.84%   |
| Lenovo                           | 22        | 0.71%   |
| Samsung Electronics              | 21        | 0.68%   |
| Qualcomm                         | 11        | 0.36%   |
| JMicron Technology               | 11        | 0.36%   |
| Silicon Integrated Systems [SiS] | 10        | 0.32%   |
| Huawei Technologies              | 10        | 0.32%   |
| TP-Link                          | 7         | 0.23%   |
| Google                           | 6         | 0.19%   |
| OnePlus Technology (Shenzhen)    | 5         | 0.16%   |
| ICS Advent                       | 5         | 0.16%   |
| Attansic Technology              | 5         | 0.16%   |
| VIA Technologies                 | 4         | 0.13%   |
| MediaTek                         | 4         | 0.13%   |
| Hewlett-Packard                  | 4         | 0.13%   |
| Apple                            | 4         | 0.13%   |
| Xiaomi                           | 3         | 0.1%    |
| OPPO Electronics                 | 3         | 0.1%    |
| Motorola PCS                     | 3         | 0.1%    |
| ZTE WCDMA Technologies MSM       | 2         | 0.06%   |
| Microchip Technology             | 2         | 0.06%   |
| HTC (High Tech Computer)         | 2         | 0.06%   |
| T & A Mobile Phones              | 1         | 0.03%   |
| Research In Motion               | 1         | 0.03%   |
| Linksys                          | 1         | 0.03%   |
| ASUSTek Computer                 | 1         | 0.03%   |
| Aquantia                         | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 987       | 31.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 389       | 12.52%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 167       | 5.37%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 142       | 4.57%   |
| Intel 82577LM Gigabit Network Connection                          | 67        | 2.16%   |
| Intel Ethernet Connection I218-LM                                 | 62        | 1.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 62        | 1.99%   |
| Intel Ethernet Connection (3) I218-LM                             | 44        | 1.42%   |
| Intel Ethernet Connection I219-LM                                 | 43        | 1.38%   |
| Intel 82567LM Gigabit Network Connection                          | 41        | 1.32%   |
| Intel Ethernet Connection I217-LM                                 | 37        | 1.19%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 36        | 1.16%   |
| Intel Ethernet Connection (4) I219-V                              | 32        | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29        | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 28        | 0.9%    |
| Intel Ethernet Connection I219-V                                  | 26        | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25        | 0.8%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 24        | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.77%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 19        | 0.61%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 17        | 0.55%   |
| Realtek RTL8125 2.5GbE Controller                                 | 17        | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 17        | 0.55%   |
| Nvidia MCP79 Ethernet                                             | 17        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 17        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 16        | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 15        | 0.48%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.48%   |
| Intel 82566MM Gigabit Network Connection                          | 15        | 0.48%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 15        | 0.48%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14        | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 13        | 0.42%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 13        | 0.42%   |
| Realtek Killer E3000 2.5GbE Controller                            | 12        | 0.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12        | 0.39%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 12        | 0.39%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 11        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3826      | 55.5%   |
| Ethernet | 2972      | 43.11%  |
| Modem    | 90        | 1.31%   |
| Unknown  | 6         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3299      | 80.94%  |
| Ethernet | 777       | 19.06%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2698      | 69.43%  |
| 1     | 1112      | 28.62%  |
| 0     | 58        | 1.49%   |
| 3     | 17        | 0.44%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3419      | 86.6%   |
| Yes  | 529       | 13.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1496      | 48.87%  |
| Qualcomm Atheros Communications | 271       | 8.85%   |
| Realtek Semiconductor           | 252       | 8.23%   |
| Broadcom                        | 205       | 6.7%    |
| IMC Networks                    | 191       | 6.24%   |
| Foxconn / Hon Hai               | 106       | 3.46%   |
| Apple                           | 103       | 3.36%   |
| Lite-On Technology              | 97        | 3.17%   |
| Dell                            | 72        | 2.35%   |
| Cambridge Silicon Radio         | 64        | 2.09%   |
| Toshiba                         | 57        | 1.86%   |
| Hewlett-Packard                 | 43        | 1.4%    |
| Realtek                         | 22        | 0.72%   |
| Alps Electric                   | 19        | 0.62%   |
| Foxconn International           | 14        | 0.46%   |
| Ralink                          | 9         | 0.29%   |
| ASUSTek Computer                | 8         | 0.26%   |
| Ralink Technology               | 6         | 0.2%    |
| Askey Computer                  | 6         | 0.2%    |
| Taiyo Yuden                     | 5         | 0.16%   |
| USI                             | 4         | 0.13%   |
| Belkin Components               | 4         | 0.13%   |
| TP-Link                         | 1         | 0.03%   |
| Sitecom Europe                  | 1         | 0.03%   |
| Opticis                         | 1         | 0.03%   |
| Integrated System Solution      | 1         | 0.03%   |
| Fujitsu                         | 1         | 0.03%   |
| Edimax Technology               | 1         | 0.03%   |
| Unknown                         | 1         | 0.03%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 658       | 21.48%  |
| Intel AX201 Bluetooth                               | 251       | 8.19%   |
| Intel AX200 Bluetooth                               | 177       | 5.78%   |
| Realtek Bluetooth Radio                             | 162       | 5.29%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 156       | 5.09%   |
| IMC Networks Bluetooth Radio                        | 126       | 4.11%   |
| Qualcomm Atheros  Bluetooth Device                  | 103       | 3.36%   |
| Intel Bluetooth Device                              | 85        | 2.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 71        | 2.32%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 69        | 2.25%   |
| Apple Bluetooth Host Controller                     | 67        | 2.19%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 64        | 2.09%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 61        | 1.99%   |
| Foxconn / Hon Hai Bluetooth Device                  | 55        | 1.8%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 52        | 1.7%    |
| Broadcom BCM2045B (BDC-2.1)                         | 42        | 1.37%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 40        | 1.31%   |
| Intel AX210 Bluetooth                               | 40        | 1.31%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 1.27%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 30        | 0.98%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 29        | 0.95%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 26        | 0.85%   |
| Dell DW375 Bluetooth Module                         | 26        | 0.85%   |
| Apple Bluetooth USB Host Controller                 | 26        | 0.85%   |
| IMC Networks Wireless_Device                        | 24        | 0.78%   |
| IMC Networks Bluetooth Device                       | 22        | 0.72%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 22        | 0.72%   |
| Lite-On Bluetooth Device                            | 20        | 0.65%   |
| Toshiba Bluetooth Device                            | 19        | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 19        | 0.62%   |
| Dell BCM20702A0 Bluetooth Module                    | 19        | 0.62%   |
| Realtek 802.11ac WLAN Adapter                       | 18        | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                    | 16        | 0.52%   |
| Broadcom HP Portable SoftSailing                    | 16        | 0.52%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.46%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 14        | 0.46%   |
| Toshiba Atheros AR3012 Bluetooth                    | 12        | 0.39%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.39%   |
| Realtek RTL8821A Bluetooth                          | 11        | 0.36%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 10        | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3111      | 67.44%  |
| AMD                              | 735       | 15.93%  |
| Nvidia                           | 478       | 10.36%  |
| C-Media Electronics              | 36        | 0.78%   |
| Realtek Semiconductor            | 26        | 0.56%   |
| GN Netcom                        | 20        | 0.43%   |
| Plantronics                      | 18        | 0.39%   |
| Lenovo                           | 18        | 0.39%   |
| Texas Instruments                | 13        | 0.28%   |
| Silicon Integrated Systems [SiS] | 12        | 0.26%   |
| Apple                            | 11        | 0.24%   |
| Logitech                         | 9         | 0.2%    |
| JMTek                            | 9         | 0.2%    |
| Creative Technology              | 8         | 0.17%   |
| ASUSTek Computer                 | 7         | 0.15%   |
| Hewlett-Packard                  | 5         | 0.11%   |
| Corsair                          | 5         | 0.11%   |
| Conexant Systems                 | 5         | 0.11%   |
| VIA Technologies                 | 4         | 0.09%   |
| SteelSeries ApS                  | 4         | 0.09%   |
| RODE Microphones                 | 4         | 0.09%   |
| Kingston Technology              | 4         | 0.09%   |
| Generalplus Technology           | 4         | 0.09%   |
| Focusrite-Novation               | 4         | 0.09%   |
| Blue Microphones                 | 4         | 0.09%   |
| Yamaha                           | 3         | 0.07%   |
| XMOS                             | 3         | 0.07%   |
| Sony                             | 3         | 0.07%   |
| Sennheiser Communications        | 3         | 0.07%   |
| Razer USA                        | 3         | 0.07%   |
| PreSonus Audio Electronics       | 3         | 0.07%   |
| Google                           | 3         | 0.07%   |
| Dell                             | 3         | 0.07%   |
| Samsung Electronics              | 2         | 0.04%   |
| M-Audio                          | 2         | 0.04%   |
| GYROCOM C&C                      | 2         | 0.04%   |
| AudioQuest                       | 2         | 0.04%   |
| AKAI Professional M.I.           | 2         | 0.04%   |
| Trust                            | 1         | 0.02%   |
| Toshiba                          | 1         | 0.02%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 434       | 7.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 340       | 6.15%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 296       | 5.35%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 212       | 3.83%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 208       | 3.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 172       | 3.11%   |
| Intel 8 Series HD Audio Controller                                                                | 155       | 2.8%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 154       | 2.78%   |
| Intel Cannon Lake PCH cAVS                                                                        | 147       | 2.66%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 146       | 2.64%   |
| Intel Broadwell-U Audio Controller                                                                | 145       | 2.62%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 139       | 2.51%   |
| AMD FCH Azalia Controller                                                                         | 134       | 2.42%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 129       | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 120       | 2.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 107       | 1.93%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 107       | 1.93%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 106       | 1.92%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 96        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 90        | 1.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 90        | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 87        | 1.57%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 84        | 1.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 80        | 1.45%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 79        | 1.43%   |
| Intel Comet Lake PCH cAVS                                                                         | 69        | 1.25%   |
| Intel CM238 HD Audio Controller                                                                   | 69        | 1.25%   |
| AMD High Definition Audio Controller                                                              | 69        | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 67        | 1.21%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 66        | 1.19%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 63        | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 58        | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 58        | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 53        | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 52        | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 47        | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 46        | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 41        | 0.74%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 39        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 37        | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 600       | 26.91%  |
| SK hynix            | 541       | 24.26%  |
| Micron Technology   | 297       | 13.32%  |
| Crucial             | 182       | 8.16%   |
| Unknown             | 155       | 6.95%   |
| Kingston            | 151       | 6.77%   |
| Corsair             | 52        | 2.33%   |
| Ramaxel Technology  | 48        | 2.15%   |
| Elpida              | 36        | 1.61%   |
| Nanya Technology    | 34        | 1.52%   |
| A-DATA Technology   | 25        | 1.12%   |
| Unknown (ABCD)      | 20        | 0.9%    |
| Unknown             | 14        | 0.63%   |
| Toshiba             | 6         | 0.27%   |
| Qimonda             | 5         | 0.22%   |
| GSkill              | 4         | 0.18%   |
| GOODRAM             | 4         | 0.18%   |
| 4ea5                | 4         | 0.18%   |
| Transcend           | 3         | 0.13%   |
| Patriot             | 3         | 0.13%   |
| ff                  | 3         | 0.13%   |
| Essencore           | 3         | 0.13%   |
| ASint Technology    | 3         | 0.13%   |
| Apacer              | 3         | 0.13%   |
| A Force             | 3         | 0.13%   |
| Timetec             | 2         | 0.09%   |
| Team                | 2         | 0.09%   |
| SHARETRONIC         | 2         | 0.09%   |
| Neo Forza           | 2         | 0.09%   |
| Innodisk            | 2         | 0.09%   |
| G.Skill             | 2         | 0.09%   |
| fef5                | 2         | 0.09%   |
| V-Color             | 1         | 0.04%   |
| Unknown (F301)      | 1         | 0.04%   |
| Unknown (CB83)      | 1         | 0.04%   |
| Unknown (0B38)      | 1         | 0.04%   |
| Smart               | 1         | 0.04%   |
| OnBoard             | 1         | 0.04%   |
| Miron               | 1         | 0.04%   |
| Memox               | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 47        | 1.98%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 27        | 1.14%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 1.05%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 1.05%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 24        | 1.01%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 24        | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.97%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 23        | 0.97%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.93%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.89%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 20        | 0.84%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 19        | 0.8%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.8%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.8%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 0.76%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 16        | 0.68%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 15        | 0.63%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 0.59%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.59%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 14        | 0.59%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.59%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 14        | 0.59%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 0.59%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.59%   |
| Unknown                                                          | 14        | 0.59%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 13        | 0.55%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 13        | 0.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.55%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.55%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 13        | 0.55%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 0.51%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 12        | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 11        | 0.46%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 10        | 0.42%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.42%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.42%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.42%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 10        | 0.42%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 9         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 836       | 43.63%  |
| DDR3    | 636       | 33.19%  |
| LPDDR4  | 110       | 5.74%   |
| DDR2    | 106       | 5.53%   |
| LPDDR3  | 98        | 5.11%   |
| SDRAM   | 53        | 2.77%   |
| DDR5    | 29        | 1.51%   |
| LPDDR5  | 16        | 0.84%   |
| Unknown | 14        | 0.73%   |
| DDR     | 10        | 0.52%   |
| DRAM    | 8         | 0.42%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1645      | 86.53%  |
| Row Of Chips | 204       | 10.73%  |
| Unknown      | 24        | 1.26%   |
| Chip         | 19        | 1%      |
| DIMM         | 9         | 0.47%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 813       | 38.83%  |
| 4096  | 598       | 28.56%  |
| 2048  | 273       | 13.04%  |
| 16384 | 262       | 12.51%  |
| 1024  | 83        | 3.96%   |
| 32768 | 53        | 2.53%   |
| 512   | 11        | 0.53%   |
| 256   | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 456       | 22.18%  |
| 2667    | 410       | 19.94%  |
| 3200    | 302       | 14.69%  |
| 2400    | 151       | 7.34%   |
| 2133    | 115       | 5.59%   |
| 1334    | 91        | 4.43%   |
| 1333    | 64        | 3.11%   |
| 667     | 57        | 2.77%   |
| 1867    | 48        | 2.33%   |
| 4267    | 46        | 2.24%   |
| Unknown | 42        | 2.04%   |
| 1067    | 38        | 1.85%   |
| 4800    | 28        | 1.36%   |
| 800     | 26        | 1.26%   |
| 4199    | 25        | 1.22%   |
| 3266    | 24        | 1.17%   |
| 2048    | 21        | 1.02%   |
| 1066    | 18        | 0.88%   |
| 6400    | 17        | 0.83%   |
| 4266    | 14        | 0.68%   |
| 975     | 11        | 0.54%   |
| 533     | 9         | 0.44%   |
| 1866    | 8         | 0.39%   |
| 3733    | 6         | 0.29%   |
| 8400    | 5         | 0.24%   |
| 3000    | 3         | 0.15%   |
| 1639    | 3         | 0.15%   |
| 400     | 3         | 0.15%   |
| 333     | 3         | 0.15%   |
| 5600    | 2         | 0.1%    |
| 1776    | 2         | 0.1%    |
| 933     | 2         | 0.1%    |
| 2933    | 1         | 0.05%   |
| 1777    | 1         | 0.05%   |
| 1596    | 1         | 0.05%   |
| 1200    | 1         | 0.05%   |
| 666     | 1         | 0.05%   |
| 100     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Canon                 | 10        | 33.33%  |
| Hewlett-Packard       | 6         | 20%     |
| Samsung Electronics   | 3         | 10%     |
| Lexmark International | 3         | 10%     |
| Brother Industries    | 3         | 10%     |
| Prolific Technology   | 2         | 6.67%   |
| STMicroelectronics    | 1         | 3.33%   |
| Seiko Epson           | 1         | 3.33%   |
| Kyocera               | 1         | 3.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon PIXMA MG3600 Series                                 | 3         | 9.68%   |
| Prolific PL2305 Parallel Port                             | 2         | 6.45%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.23%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 3.23%   |
| Samsung CLX-6260 Series                                   | 1         | 3.23%   |
| Samsung CLP-300 Series                                    | 1         | 3.23%   |
| Samsung C43x Series                                       | 1         | 3.23%   |
| Lexmark International MS610de                             | 1         | 3.23%   |
| Lexmark International C544                                | 1         | 3.23%   |
| Lexmark International 640 Series                          | 1         | 3.23%   |
| Kyocera FS-1041                                           | 1         | 3.23%   |
| HP Officejet 4630 series                                  | 1         | 3.23%   |
| HP LaserJet P2015 series                                  | 1         | 3.23%   |
| HP LaserJet 1010                                          | 1         | 3.23%   |
| HP ENVY Photo 6200 series                                 | 1         | 3.23%   |
| HP ENVY 4520 series                                       | 1         | 3.23%   |
| HP Deskjet 2540 series                                    | 1         | 3.23%   |
| Canon SELPHY CP400                                        | 1         | 3.23%   |
| Canon PIXMA MX490 Series                                  | 1         | 3.23%   |
| Canon PIXMA MG2500 Series                                 | 1         | 3.23%   |
| Canon MF4360-4390                                         | 1         | 3.23%   |
| Canon LiDE 400                                            | 1         | 3.23%   |
| Canon iX6500 series                                       | 1         | 3.23%   |
| Canon iP4800 series                                       | 1         | 3.23%   |
| Canon CanoScan LiDE 300                                   | 1         | 3.23%   |
| Brother PT-9500PC                                         | 1         | 3.23%   |
| Brother DCP-L3510CDW                                      | 1         | 3.23%   |
| Brother DCP-7025 Printer                                  | 1         | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 5         | 62.5%   |
| Seiko Epson     | 2         | 25%     |
| Hewlett-Packard | 1         | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                     | 2         | 25%     |
| Seiko Epson Scanner                         | 1         | 12.5%   |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 12.5%   |
| HP ScanJet 5300c/5370c                      | 1         | 12.5%   |
| Canon CanoScan LiDE 600F                    | 1         | 12.5%   |
| Canon CanoScan LiDE 220                     | 1         | 12.5%   |
| Canon CanoScan LiDE 200                     | 1         | 12.5%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 853       | 25.58%  |
| Microdia                               | 374       | 11.22%  |
| IMC Networks                           | 291       | 8.73%   |
| Realtek Semiconductor                  | 285       | 8.55%   |
| Bison Electronics                      | 194       | 5.82%   |
| Sunplus Innovation Technology          | 183       | 5.49%   |
| Cheng Uei Precision Industry (Foxlink) | 135       | 4.05%   |
| Quanta                                 | 132       | 3.96%   |
| Suyin                                  | 107       | 3.21%   |
| Lite-On Technology                     | 91        | 2.73%   |
| Apple                                  | 82        | 2.46%   |
| Syntek                                 | 75        | 2.25%   |
| Silicon Motion                         | 61        | 1.83%   |
| Acer                                   | 51        | 1.53%   |
| Logitech                               | 50        | 1.5%    |
| Alcor Micro                            | 49        | 1.47%   |
| Ricoh                                  | 45        | 1.35%   |
| Lenovo                                 | 40        | 1.2%    |
| Luxvisions Innotech Limited            | 34        | 1.02%   |
| Samsung Electronics                    | 18        | 0.54%   |
| Z-Star Microelectronics                | 15        | 0.45%   |
| Sonix Technology                       | 15        | 0.45%   |
| ALi                                    | 15        | 0.45%   |
| Primax Electronics                     | 13        | 0.39%   |
| Microsoft                              | 12        | 0.36%   |
| SunplusIT                              | 7         | 0.21%   |
| Sunplus Technology                     | 7         | 0.21%   |
| Importek                               | 7         | 0.21%   |
| OmniVision Technologies                | 6         | 0.18%   |
| Intel                                  | 6         | 0.18%   |
| Generalplus Technology                 | 6         | 0.18%   |
| DigiTech                               | 6         | 0.18%   |
| GEMBIRD                                | 5         | 0.15%   |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.12%   |
| ARC International                      | 4         | 0.12%   |
| Razer USA                              | 3         | 0.09%   |
| MacroSilicon                           | 3         | 0.09%   |
| Google                                 | 3         | 0.09%   |
| Genesys Logic                          | 3         | 0.09%   |
| Foxconn / Hon Hai                      | 3         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 189       | 5.63%   |
| Chicony Integrated Camera                               | 151       | 4.5%    |
| Realtek Integrated_Webcam_HD                            | 100       | 2.98%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 85        | 2.53%   |
| IMC Networks Integrated Camera                          | 78        | 2.32%   |
| Sunplus Integrated_Webcam_HD                            | 66        | 1.97%   |
| Chicony HD WebCam                                       | 63        | 1.88%   |
| Chicony TOSHIBA Web Camera - HD                         | 51        | 1.52%   |
| Bison Integrated Camera                                 | 41        | 1.22%   |
| Chicony USB2.0 Camera                                   | 40        | 1.19%   |
| Microdia Integrated Webcam                              | 38        | 1.13%   |
| Chicony HP TrueVision HD Camera                         | 35        | 1.04%   |
| Lite-On Integrated Camera                               | 34        | 1.01%   |
| Syntek Integrated Camera                                | 30        | 0.89%   |
| Chicony USB 2.0 Camera                                  | 30        | 0.89%   |
| Apple Built-in iSight                                   | 30        | 0.89%   |
| Chicony HP HD Camera                                    | 29        | 0.86%   |
| Bison BisonCam,NB Pro                                   | 28        | 0.83%   |
| Chicony HP Truevision HD                                | 27        | 0.8%    |
| Quanta HD User Facing                                   | 26        | 0.77%   |
| Chicony EasyCamera                                      | 26        | 0.77%   |
| Bison SunplusIT Integrated Camera                       | 26        | 0.77%   |
| Chicony VGA Webcam                                      | 25        | 0.74%   |
| Syntek Lenovo EasyCamera                                | 24        | 0.72%   |
| Realtek USB Camera                                      | 24        | 0.72%   |
| Chicony Integrated Camera (1280x720@30)                 | 24        | 0.72%   |
| Apple FaceTime HD Camera                                | 24        | 0.72%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 20        | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 20        | 0.6%    |
| Alcor Micro USB 2.0 PC cam                              | 20        | 0.6%    |
| Lenovo Integrated Webcam [R5U877]                       | 19        | 0.57%   |
| Chicony HP Wide Vision HD Camera                        | 19        | 0.57%   |
| Chicony CNF9055 Toshiba Webcam                          | 19        | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 19        | 0.57%   |
| Sunplus HD WebCam                                       | 18        | 0.54%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 18        | 0.54%   |
| Chicony HD User Facing                                  | 18        | 0.54%   |
| Suyin HP Truevision HD                                  | 17        | 0.51%   |
| Realtek Integrated Webcam HD                            | 17        | 0.51%   |
| Realtek Integrated Webcam                               | 17        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 218       | 33.44%  |
| Synaptics                          | 156       | 23.93%  |
| Shenzhen Goodix Technology         | 103       | 15.8%   |
| AuthenTec                          | 52        | 7.98%   |
| Upek                               | 51        | 7.82%   |
| LighTuning Technology              | 31        | 4.75%   |
| Elan Microelectronics              | 22        | 3.37%   |
| STMicroelectronics                 | 14        | 2.15%   |
| Samsung Electronics                | 2         | 0.31%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.31%   |
| Focal-systems.Corp                 | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 57        | 8.74%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 49        | 7.52%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 43        | 6.6%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 38        | 5.83%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 5.83%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 27        | 4.14%   |
| Shenzhen Goodix FingerPrint                                                | 26        | 3.99%   |
| Validity Sensors Synaptics WBDI                                            | 21        | 3.22%   |
| Shenzhen Goodix Fingerprint Reader                                         | 20        | 3.07%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.76%   |
| Validity Sensors VFS491                                                    | 17        | 2.61%   |
| AuthenTec AES2810                                                          | 15        | 2.3%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 2.3%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 2.15%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 2.15%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 2.15%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 14        | 2.15%   |
| Synaptics UWP WBDI                                                         | 13        | 1.99%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 1.99%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.69%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 11        | 1.69%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 1.53%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 1.53%   |
| Elan ELAN:Fingerprint                                                      | 10        | 1.53%   |
| Unknown                                                                    | 10        | 1.53%   |
| Elan ELAN:ARM-M4                                                           | 9         | 1.38%   |
| Synaptics WBDI Device                                                      | 8         | 1.23%   |
| Synaptics UWP WBDI Device                                                  | 8         | 1.23%   |
| Synaptics  WBDI                                                            | 8         | 1.23%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 1.23%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.07%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 6         | 0.92%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 0.92%   |
| AuthenTec AES1600                                                          | 6         | 0.92%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.77%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.77%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.77%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.61%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 0.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 177       | 52.68%  |
| Alcor Micro           | 73        | 21.73%  |
| Upek                  | 28        | 8.33%   |
| Lenovo                | 24        | 7.14%   |
| O2 Micro              | 23        | 6.85%   |
| Gemalto (was Gemplus) | 4         | 1.19%   |
| SCM Microsystems      | 3         | 0.89%   |
| Purism, SPC           | 1         | 0.3%    |
| Clay Logic            | 1         | 0.3%    |
| Chicony Electronics   | 1         | 0.3%    |
| Cherry                | 1         | 0.3%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 72        | 21.43%  |
| Broadcom BCM5880 Secure Applications Processor                               | 71        | 21.13%  |
| Broadcom 5880                                                                | 44        | 13.1%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 34        | 10.12%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 28        | 8.33%   |
| Broadcom 58200                                                               | 26        | 7.74%   |
| Lenovo Integrated Smart Card Reader                                          | 23        | 6.85%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 18        | 5.36%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.49%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.89%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.6%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.6%    |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.3%    |
| Purism, SPC Librem Key                                                       | 1         | 0.3%    |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.3%    |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.3%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.3%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.3%    |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.3%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2489      | 62.68%  |
| 1     | 1134      | 28.56%  |
| 2     | 296       | 7.45%   |
| 3     | 41        | 1.03%   |
| 4     | 5         | 0.13%   |
| 5     | 3         | 0.08%   |
| 8     | 1         | 0.03%   |
| 7     | 1         | 0.03%   |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 634       | 34.42%  |
| Graphics card            | 334       | 18.13%  |
| Chipcard                 | 308       | 16.72%  |
| Net/wireless             | 205       | 11.13%  |
| Multimedia controller    | 102       | 5.54%   |
| Communication controller | 42        | 2.28%   |
| Storage                  | 40        | 2.17%   |
| Camera                   | 38        | 2.06%   |
| Bluetooth                | 37        | 2.01%   |
| Sound                    | 22        | 1.19%   |
| Card reader              | 20        | 1.09%   |
| Net/ethernet             | 17        | 0.92%   |
| Modem                    | 16        | 0.87%   |
| Network                  | 8         | 0.43%   |
| Flash memory             | 8         | 0.43%   |
| Firewire controller      | 4         | 0.22%   |
| Storage/nvme             | 3         | 0.16%   |
| Unassigned class         | 2         | 0.11%   |
| Storage/ide              | 2         | 0.11%   |

