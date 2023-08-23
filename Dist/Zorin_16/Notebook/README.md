Zorin 16 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 16.

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

Total: 2741

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 840 G7 Noteboo... | [5ba59f878a](https://linux-hardware.org/?probe=5ba59f878a) | Aug 12, 2023 |
| Acer          | One Z1402                   | [9fd6a2d41b](https://linux-hardware.org/?probe=9fd6a2d41b) | Aug 12, 2023 |
| Unknown       | Unknown                     | [b68d99fd89](https://linux-hardware.org/?probe=b68d99fd89) | Aug 11, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [48a0f64b34](https://linux-hardware.org/?probe=48a0f64b34) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| HP            | 350 G2                      | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [cde80ecaf6](https://linux-hardware.org/?probe=cde80ecaf6) | Aug 10, 2023 |
| HP            | ProBook 450 G6              | [c205f19d5e](https://linux-hardware.org/?probe=c205f19d5e) | Aug 09, 2023 |
| HP            | 350 G2                      | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| HP            | Presario CQ56               | [cf373b9083](https://linux-hardware.org/?probe=cf373b9083) | Aug 09, 2023 |
| HP            | Laptop 14-dk1xxx            | [7c59be984f](https://linux-hardware.org/?probe=7c59be984f) | Aug 09, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [03a4763a96](https://linux-hardware.org/?probe=03a4763a96) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c90663d505](https://linux-hardware.org/?probe=c90663d505) | Aug 08, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87ee840e89](https://linux-hardware.org/?probe=87ee840e89) | Aug 07, 2023 |
| LG Electro... | 14Z90N-V.AA78B              | [af79c7f5f5](https://linux-hardware.org/?probe=af79c7f5f5) | Aug 07, 2023 |
| Apple         | MacBookPro14,1              | [72a4a0eed2](https://linux-hardware.org/?probe=72a4a0eed2) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c40308638c](https://linux-hardware.org/?probe=c40308638c) | Aug 05, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [8b6db0bfbb](https://linux-hardware.org/?probe=8b6db0bfbb) | Aug 05, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| HP            | EliteBook 8440p             | [5f0be846f0](https://linux-hardware.org/?probe=5f0be846f0) | Aug 05, 2023 |
| Dell          | Venue 11 Pro 7140           | [7188a418fc](https://linux-hardware.org/?probe=7188a418fc) | Aug 05, 2023 |
| HP            | EliteBook 8460p             | [db336dcf75](https://linux-hardware.org/?probe=db336dcf75) | Aug 05, 2023 |
| Itautec       | Infoway                     | [1708f5baae](https://linux-hardware.org/?probe=1708f5baae) | Aug 04, 2023 |
| GPD           | G1621-02                    | [d7361e9896](https://linux-hardware.org/?probe=d7361e9896) | Aug 04, 2023 |
| Apple         | MacBook8,1                  | [cf6d77d650](https://linux-hardware.org/?probe=cf6d77d650) | Aug 04, 2023 |
| Dell          | Latitude 7490               | [955c961132](https://linux-hardware.org/?probe=955c961132) | Aug 04, 2023 |
| Apple         | MacBookPro8,1               | [61cb65a2e9](https://linux-hardware.org/?probe=61cb65a2e9) | Aug 04, 2023 |
| Dell          | Inspiron 3531               | [f011e5c6cf](https://linux-hardware.org/?probe=f011e5c6cf) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Acer          | Aspire M3-581G              | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [37fe1d55f8](https://linux-hardware.org/?probe=37fe1d55f8) | Aug 02, 2023 |
| HP            | Pavilion dv7                | [bd9bc8e7a6](https://linux-hardware.org/?probe=bd9bc8e7a6) | Aug 02, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [ee5b34b232](https://linux-hardware.org/?probe=ee5b34b232) | Aug 02, 2023 |
| ASUSTek       | K54C                        | [f4fcf79e7e](https://linux-hardware.org/?probe=f4fcf79e7e) | Aug 02, 2023 |
| Dell          | Inspiron 5577               | [1204832e26](https://linux-hardware.org/?probe=1204832e26) | Aug 01, 2023 |
| Dell          | Inspiron 5577               | [219723a17d](https://linux-hardware.org/?probe=219723a17d) | Aug 01, 2023 |
| Dell          | Latitude E5470              | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [957e1805d3](https://linux-hardware.org/?probe=957e1805d3) | Aug 01, 2023 |
| HP            | Stream Laptop 14-cb1XX      | [a522e7336c](https://linux-hardware.org/?probe=a522e7336c) | Aug 01, 2023 |
| MSI           | GE72MVR 7RG                 | [d935650def](https://linux-hardware.org/?probe=d935650def) | Jul 31, 2023 |
| Dell          | Inspiron 3421               | [d1651e3e43](https://linux-hardware.org/?probe=d1651e3e43) | Jul 31, 2023 |
| Chuwi         | GemiBook Pro                | [d4efd6692b](https://linux-hardware.org/?probe=d4efd6692b) | Jul 30, 2023 |
| Apple         | MacBookPro4,1               | [eedbe7eb59](https://linux-hardware.org/?probe=eedbe7eb59) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [1a77aeef9d](https://linux-hardware.org/?probe=1a77aeef9d) | Jul 30, 2023 |
| Apple         | MacBookAir5,2               | [a6e35103c8](https://linux-hardware.org/?probe=a6e35103c8) | Jul 30, 2023 |
| Sony          | VPCF13Z1E                   | [e52969e6a8](https://linux-hardware.org/?probe=e52969e6a8) | Jul 30, 2023 |
| MSI           | GS73VR 7RF                  | [9df7170f38](https://linux-hardware.org/?probe=9df7170f38) | Jul 29, 2023 |
| HP            | Pavilion dv4                | [47e9cba85c](https://linux-hardware.org/?probe=47e9cba85c) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| ASUSTek       | K53U                        | [c1b84117db](https://linux-hardware.org/?probe=c1b84117db) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [dfe51162d1](https://linux-hardware.org/?probe=dfe51162d1) | Jul 29, 2023 |
| HP            | Pavilion g7                 | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| HP            | ZBook 15 G5                 | [8996d2d4fd](https://linux-hardware.org/?probe=8996d2d4fd) | Jul 28, 2023 |
| Google        | Edgar                       | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| ASUSTek       | K50IJ                       | [7e30723b3b](https://linux-hardware.org/?probe=7e30723b3b) | Jul 28, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9e892612ab](https://linux-hardware.org/?probe=9e892612ab) | Jul 28, 2023 |
| HP            | EliteBook 8560p             | [b7ce548e5b](https://linux-hardware.org/?probe=b7ce548e5b) | Jul 27, 2023 |
| Sony          | VPCF13Z1E                   | [5022f7359c](https://linux-hardware.org/?probe=5022f7359c) | Jul 26, 2023 |
| Apple         | MacBookPro12,1              | [45bc8cd978](https://linux-hardware.org/?probe=45bc8cd978) | Jul 26, 2023 |
| Sony          | VPCF13Z1E                   | [f5290b8791](https://linux-hardware.org/?probe=f5290b8791) | Jul 25, 2023 |
| Sony          | VPCF13Z1E                   | [99aacf2d95](https://linux-hardware.org/?probe=99aacf2d95) | Jul 25, 2023 |
| Acer          | TravelMate B113             | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| Toshiba       | QOSMIO X770                 | [7eda84257a](https://linux-hardware.org/?probe=7eda84257a) | Jul 25, 2023 |
| Dell          | Inspiron 3721               | [a0874e626b](https://linux-hardware.org/?probe=a0874e626b) | Jul 24, 2023 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [c16c981a88](https://linux-hardware.org/?probe=c16c981a88) | Jul 24, 2023 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [8ca6d932b3](https://linux-hardware.org/?probe=8ca6d932b3) | Jul 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [35d95135f4](https://linux-hardware.org/?probe=35d95135f4) | Jul 23, 2023 |
| HP            | ProBook 640 G1              | [de254aad44](https://linux-hardware.org/?probe=de254aad44) | Jul 23, 2023 |
| Microtech     | ebookPro                    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| Dell          | Latitude E6400              | [77a598aa4d](https://linux-hardware.org/?probe=77a598aa4d) | Jul 23, 2023 |
| Acer          | AO756                       | [23e3fc369f](https://linux-hardware.org/?probe=23e3fc369f) | Jul 23, 2023 |
| Apple         | MacBookAir7,2               | [c271fa70b8](https://linux-hardware.org/?probe=c271fa70b8) | Jul 23, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [19356a725e](https://linux-hardware.org/?probe=19356a725e) | Jul 22, 2023 |
| HP            | Pavilion dv4                | [4854c4b18c](https://linux-hardware.org/?probe=4854c4b18c) | Jul 22, 2023 |
| HP            | EliteBook 820 G4            | [3051483589](https://linux-hardware.org/?probe=3051483589) | Jul 22, 2023 |
| Medion        | E15301                      | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| Acer          | Nitro AN515-44              | [306d51185f](https://linux-hardware.org/?probe=306d51185f) | Jul 21, 2023 |
| AMI           | Cherry Trail CR             | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| HP            | EliteBook 820 G4            | [c85c21d42e](https://linux-hardware.org/?probe=c85c21d42e) | Jul 21, 2023 |
| Dell          | Latitude E6440              | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Dell          | Latitude 3520               | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| HP            | 15                          | [36b4035b57](https://linux-hardware.org/?probe=36b4035b57) | Jul 20, 2023 |
| Dell          | Inspiron 3501               | [71f9656ab2](https://linux-hardware.org/?probe=71f9656ab2) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [854bbb5dee](https://linux-hardware.org/?probe=854bbb5dee) | Jul 19, 2023 |
| HP            | 15                          | [0eeb522bec](https://linux-hardware.org/?probe=0eeb522bec) | Jul 19, 2023 |
| HP            | EliteBook 2570p             | [205b94b373](https://linux-hardware.org/?probe=205b94b373) | Jul 19, 2023 |
| Sony          | VPCEE23FX                   | [2cb9bf9d50](https://linux-hardware.org/?probe=2cb9bf9d50) | Jul 18, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [9be017a8a3](https://linux-hardware.org/?probe=9be017a8a3) | Jul 16, 2023 |
| Dell          | Inspiron 3421               | [71c4faf60f](https://linux-hardware.org/?probe=71c4faf60f) | Jul 16, 2023 |
| Dell          | Inspiron 5537               | [428df654fb](https://linux-hardware.org/?probe=428df654fb) | Jul 16, 2023 |
| Dell          | Inspiron 3531               | [0e7f83761f](https://linux-hardware.org/?probe=0e7f83761f) | Jul 15, 2023 |
| Dell          | Inspiron 3531               | [d73dcbb938](https://linux-hardware.org/?probe=d73dcbb938) | Jul 15, 2023 |
| Dell          | Latitude E4300              | [a9e8fb7884](https://linux-hardware.org/?probe=a9e8fb7884) | Jul 15, 2023 |
| Unknown       | SLR-0308                    | [8626e36716](https://linux-hardware.org/?probe=8626e36716) | Jul 15, 2023 |
| Alienware     | M11xR3                      | [9397339221](https://linux-hardware.org/?probe=9397339221) | Jul 14, 2023 |
| HUAWEI        | RLEF-XX                     | [23793e7d9c](https://linux-hardware.org/?probe=23793e7d9c) | Jul 14, 2023 |
| HP            | 15                          | [215a87518e](https://linux-hardware.org/?probe=215a87518e) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [34fe8ff1ad](https://linux-hardware.org/?probe=34fe8ff1ad) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [a3d301a82a](https://linux-hardware.org/?probe=a3d301a82a) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| HP            | Pavilion dv7                | [b2e0e73adc](https://linux-hardware.org/?probe=b2e0e73adc) | Jul 13, 2023 |
| Apple         | MacBookAir7,2               | [81f693b5b0](https://linux-hardware.org/?probe=81f693b5b0) | Jul 12, 2023 |
| Dell          | Inspiron 3421               | [d347a1b82e](https://linux-hardware.org/?probe=d347a1b82e) | Jul 12, 2023 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [bae54aa498](https://linux-hardware.org/?probe=bae54aa498) | Jul 12, 2023 |
| Dell          | Inspiron 3501               | [7190b16550](https://linux-hardware.org/?probe=7190b16550) | Jul 12, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [052461ef4d](https://linux-hardware.org/?probe=052461ef4d) | Jul 11, 2023 |
| HP            | Compaq 2510p                | [a7cb1d43fb](https://linux-hardware.org/?probe=a7cb1d43fb) | Jul 11, 2023 |
| HP            | Pavilion g4                 | [6e76f09416](https://linux-hardware.org/?probe=6e76f09416) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ecc4006807](https://linux-hardware.org/?probe=ecc4006807) | Jul 11, 2023 |
| HP            | ProBook 450 G6              | [8e5774c497](https://linux-hardware.org/?probe=8e5774c497) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [2c690e981a](https://linux-hardware.org/?probe=2c690e981a) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [732d09609d](https://linux-hardware.org/?probe=732d09609d) | Jul 10, 2023 |
| HP            | EliteBook 840 G5            | [08770a11c6](https://linux-hardware.org/?probe=08770a11c6) | Jul 10, 2023 |
| HP            | Compaq 2510p                | [98d500c68c](https://linux-hardware.org/?probe=98d500c68c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [621eaf410c](https://linux-hardware.org/?probe=621eaf410c) | Jul 10, 2023 |
| Lenovo        | ThinkPad Yoga 260 20FES3... | [3631291aa8](https://linux-hardware.org/?probe=3631291aa8) | Jul 10, 2023 |
| HP            | Notebook                    | [7d4bc75f38](https://linux-hardware.org/?probe=7d4bc75f38) | Jul 09, 2023 |
| ASUSTek       | K54C                        | [3f0ca5ad18](https://linux-hardware.org/?probe=3f0ca5ad18) | Jul 09, 2023 |
| HP            | Laptop 15-dy1xxx            | [938e9efd55](https://linux-hardware.org/?probe=938e9efd55) | Jul 09, 2023 |
| Unknown       | SLR-0308                    | [d5b0d30e8d](https://linux-hardware.org/?probe=d5b0d30e8d) | Jul 09, 2023 |
| Apple         | MacBookPro11,2              | [e6693c16ff](https://linux-hardware.org/?probe=e6693c16ff) | Jul 09, 2023 |
| Dell          | Latitude E5470              | [e04195b0f7](https://linux-hardware.org/?probe=e04195b0f7) | Jul 08, 2023 |
| OTVOC         | N1                          | [1b4d619110](https://linux-hardware.org/?probe=1b4d619110) | Jul 07, 2023 |
| Lenovo        | ThinkPad X220 4286CTO       | [7b62ed78d1](https://linux-hardware.org/?probe=7b62ed78d1) | Jul 07, 2023 |
| Toshiba       | Satellite L670              | [fdc3192779](https://linux-hardware.org/?probe=fdc3192779) | Jul 06, 2023 |
| Lenovo        | Legion Y7000P-1060 81LF     | [203ffa97b4](https://linux-hardware.org/?probe=203ffa97b4) | Jul 06, 2023 |
| Toshiba       | Satellite L670              | [1db76edeb5](https://linux-hardware.org/?probe=1db76edeb5) | Jul 06, 2023 |
| Dell          | XPS 13 9370                 | [854ca6ff4f](https://linux-hardware.org/?probe=854ca6ff4f) | Jul 06, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [774ebec1d8](https://linux-hardware.org/?probe=774ebec1d8) | Jul 05, 2023 |
| HP            | EliteBook 820 G4            | [58ced183c2](https://linux-hardware.org/?probe=58ced183c2) | Jul 04, 2023 |
| Acer          | Nitro AN515-44              | [d3aeb3e580](https://linux-hardware.org/?probe=d3aeb3e580) | Jul 03, 2023 |
| Digibras      | NH4CU03                     | [c073941827](https://linux-hardware.org/?probe=c073941827) | Jul 03, 2023 |
| OTVOC         | N1                          | [833ed0c86b](https://linux-hardware.org/?probe=833ed0c86b) | Jul 02, 2023 |
| HP            | ENVY m6                     | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Compaq 6830s                | [9a777f4318](https://linux-hardware.org/?probe=9a777f4318) | Jul 01, 2023 |
| Dell          | Latitude E6400              | [c8f88ff5b6](https://linux-hardware.org/?probe=c8f88ff5b6) | Jun 30, 2023 |
| Acer          | Aspire 5738                 | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [9d6748ef56](https://linux-hardware.org/?probe=9d6748ef56) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| Dell          | Latitude E6400              | [0f9255924f](https://linux-hardware.org/?probe=0f9255924f) | Jun 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [64433a8783](https://linux-hardware.org/?probe=64433a8783) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [663ce69f30](https://linux-hardware.org/?probe=663ce69f30) | Jun 27, 2023 |
| HP            | Laptop 14-ck0xxx            | [73eab89788](https://linux-hardware.org/?probe=73eab89788) | Jun 27, 2023 |
| Lenovo        | V110-15IKB 80TH             | [e6b9f96475](https://linux-hardware.org/?probe=e6b9f96475) | Jun 27, 2023 |
| HP            | Pavilion dv6700             | [182bf6e4a7](https://linux-hardware.org/?probe=182bf6e4a7) | Jun 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DA50... | [b756e54029](https://linux-hardware.org/?probe=b756e54029) | Jun 27, 2023 |
| Dell          | Latitude 3189               | [ad7c98c905](https://linux-hardware.org/?probe=ad7c98c905) | Jun 26, 2023 |
| Dell          | Latitude 3189               | [8547503af5](https://linux-hardware.org/?probe=8547503af5) | Jun 25, 2023 |
| Dell          | Latitude 3189               | [3f44430a36](https://linux-hardware.org/?probe=3f44430a36) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Apple         | MacBookPro11,2              | [2d7e4f3505](https://linux-hardware.org/?probe=2d7e4f3505) | Jun 24, 2023 |
| Acer          | Aspire 5738                 | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| Dell          | Latitude E6400              | [74be208929](https://linux-hardware.org/?probe=74be208929) | Jun 24, 2023 |
| Acer          | AOD270                      | [af596f2c11](https://linux-hardware.org/?probe=af596f2c11) | Jun 24, 2023 |
| Acer          | AOD270                      | [d3204f80d5](https://linux-hardware.org/?probe=d3204f80d5) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | EliteBook 8560p             | [177d2fe509](https://linux-hardware.org/?probe=177d2fe509) | Jun 22, 2023 |
| Google        | Kefka                       | [2580ed90ee](https://linux-hardware.org/?probe=2580ed90ee) | Jun 22, 2023 |
| Apple         | MacBookAir7,2               | [ae8c13c6fd](https://linux-hardware.org/?probe=ae8c13c6fd) | Jun 22, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [3d558ea9aa](https://linux-hardware.org/?probe=3d558ea9aa) | Jun 21, 2023 |
| Dell          | Vostro 5481                 | [b28f58f09e](https://linux-hardware.org/?probe=b28f58f09e) | Jun 20, 2023 |
| HP            | ENVY m6                     | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| Dell          | Inspiron 5558               | [72ef7ff0aa](https://linux-hardware.org/?probe=72ef7ff0aa) | Jun 20, 2023 |
| Dell          | G7 7588                     | [946a645897](https://linux-hardware.org/?probe=946a645897) | Jun 20, 2023 |
| Sony          | VPCCA15FX                   | [ed7dba1a4c](https://linux-hardware.org/?probe=ed7dba1a4c) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [bc371b62c9](https://linux-hardware.org/?probe=bc371b62c9) | Jun 19, 2023 |
| Sony          | VPCCA15FX                   | [c5660d0020](https://linux-hardware.org/?probe=c5660d0020) | Jun 19, 2023 |
| Dell          | Vostro 1520                 | [8086cf1231](https://linux-hardware.org/?probe=8086cf1231) | Jun 19, 2023 |
| Lenovo        | ThinkPad T440 20B7S0VA05    | [307c8a76ab](https://linux-hardware.org/?probe=307c8a76ab) | Jun 19, 2023 |
| GPU Compan... | GWNC21524                   | [46bd956cbf](https://linux-hardware.org/?probe=46bd956cbf) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [7546cac791](https://linux-hardware.org/?probe=7546cac791) | Jun 19, 2023 |
| HP            | EliteBook 840 G3            | [e1fc794bc5](https://linux-hardware.org/?probe=e1fc794bc5) | Jun 18, 2023 |
| ASUSTek       | VivoBook S13 X330FA_S330... | [b816a11527](https://linux-hardware.org/?probe=b816a11527) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [bb6859a141](https://linux-hardware.org/?probe=bb6859a141) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [1d158627b0](https://linux-hardware.org/?probe=1d158627b0) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [5c2378adc5](https://linux-hardware.org/?probe=5c2378adc5) | Jun 17, 2023 |
| Dell          | Latitude 7370               | [44dba24aed](https://linux-hardware.org/?probe=44dba24aed) | Jun 17, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [3614dc460e](https://linux-hardware.org/?probe=3614dc460e) | Jun 17, 2023 |
| HP            | Laptop 14-bw0xx             | [f38253d79c](https://linux-hardware.org/?probe=f38253d79c) | Jun 17, 2023 |
| Haier         | Y11B                        | [0c2abeea6e](https://linux-hardware.org/?probe=0c2abeea6e) | Jun 17, 2023 |
| HP            | ProBook 650 G5              | [9c53e4cd72](https://linux-hardware.org/?probe=9c53e4cd72) | Jun 17, 2023 |
| HP            | G62                         | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Acer          | Aspire V5-571P              | [2adeb26f8a](https://linux-hardware.org/?probe=2adeb26f8a) | Jun 15, 2023 |
| Dell          | Venue 11 Pro 5130           | [e1bb6b17b8](https://linux-hardware.org/?probe=e1bb6b17b8) | Jun 14, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [9fe9d9f03f](https://linux-hardware.org/?probe=9fe9d9f03f) | Jun 13, 2023 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b737ce6557](https://linux-hardware.org/?probe=b737ce6557) | Jun 13, 2023 |
| HP            | ENVY m6                     | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | GL62M 7RDX                  | [d1fb646d9a](https://linux-hardware.org/?probe=d1fb646d9a) | Jun 11, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9cb593e9e1](https://linux-hardware.org/?probe=9cb593e9e1) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [1af7e59490](https://linux-hardware.org/?probe=1af7e59490) | Jun 11, 2023 |
| ASUSTek       | U43Jc                       | [15e8e27585](https://linux-hardware.org/?probe=15e8e27585) | Jun 11, 2023 |
| Samsung       | N150/N210/N220              | [977d645961](https://linux-hardware.org/?probe=977d645961) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| Google        | Pirika                      | [67fce0a645](https://linux-hardware.org/?probe=67fce0a645) | Jun 10, 2023 |
| Dell          | Precision 7520              | [c52fb2f851](https://linux-hardware.org/?probe=c52fb2f851) | Jun 10, 2023 |
| HP            | Pavilion Notebook           | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| HP            | Pavilion Laptop 14-ec1xx... | [de4c183b01](https://linux-hardware.org/?probe=de4c183b01) | Jun 06, 2023 |
| Samsung       | 300E5M/300E5L               | [e066300eac](https://linux-hardware.org/?probe=e066300eac) | Jun 06, 2023 |
| Acer          | Aspire 5736Z                | [a98deb1f54](https://linux-hardware.org/?probe=a98deb1f54) | Jun 06, 2023 |
| Apple         | MacBookPro8,1               | [8308d5da16](https://linux-hardware.org/?probe=8308d5da16) | Jun 05, 2023 |
| Apple         | MacBookPro8,1               | [2f8dbb707f](https://linux-hardware.org/?probe=2f8dbb707f) | Jun 05, 2023 |
| HP            | OMEN by Laptop              | [e3b8e1a109](https://linux-hardware.org/?probe=e3b8e1a109) | Jun 04, 2023 |
| Dell          | Latitude E5250              | [e85c6a09d1](https://linux-hardware.org/?probe=e85c6a09d1) | Jun 04, 2023 |
| Toshiba       | IS 1412                     | [b1b0369688](https://linux-hardware.org/?probe=b1b0369688) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BUS0LW02    | [27f6e7df80](https://linux-hardware.org/?probe=27f6e7df80) | Jun 04, 2023 |
| HP            | Stream Laptop 14-cb0XX      | [83967c7908](https://linux-hardware.org/?probe=83967c7908) | Jun 04, 2023 |
| HP            | ProBook 450 G2              | [55f28b41b4](https://linux-hardware.org/?probe=55f28b41b4) | Jun 03, 2023 |
| Toshiba       | IS 1412                     | [6ea1bc7e6a](https://linux-hardware.org/?probe=6ea1bc7e6a) | Jun 03, 2023 |
| IPASON        | P3                          | [bd9e0660a4](https://linux-hardware.org/?probe=bd9e0660a4) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Toshiba       | Satellite L650              | [63eb6978fa](https://linux-hardware.org/?probe=63eb6978fa) | Jun 01, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | [a7af6cac2c](https://linux-hardware.org/?probe=a7af6cac2c) | Jun 01, 2023 |
| HP            | Pavilion dv6500             | [0198d67a15](https://linux-hardware.org/?probe=0198d67a15) | May 31, 2023 |
| Sony          | SVF14214CXW                 | [51568ce56e](https://linux-hardware.org/?probe=51568ce56e) | May 30, 2023 |
| Dell          | Latitude 3480               | [56d1834385](https://linux-hardware.org/?probe=56d1834385) | May 30, 2023 |
| Sony          | SVF14214CXW                 | [6cf7c2d7f2](https://linux-hardware.org/?probe=6cf7c2d7f2) | May 30, 2023 |
| Dell          | Inspiron 5748               | [08b61d608c](https://linux-hardware.org/?probe=08b61d608c) | May 30, 2023 |
| ASUSTek       | U43Jc                       | [db28d8f731](https://linux-hardware.org/?probe=db28d8f731) | May 28, 2023 |
| ASUSTek       | U43Jc                       | [36bd3a5288](https://linux-hardware.org/?probe=36bd3a5288) | May 28, 2023 |
| Lenovo        | ThinkPad E490 20N8A01YGI    | [c46cf56eb1](https://linux-hardware.org/?probe=c46cf56eb1) | May 27, 2023 |
| Lenovo        | B50-70 80EU                 | [8c51cdf4ef](https://linux-hardware.org/?probe=8c51cdf4ef) | May 27, 2023 |
| HP            | Pavilion dv6                | [9f96328490](https://linux-hardware.org/?probe=9f96328490) | May 27, 2023 |
| Acer          | Aspire ES1-523              | [681fbd4a1f](https://linux-hardware.org/?probe=681fbd4a1f) | May 27, 2023 |
| Toshiba       | TECRA M10                   | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| HP            | ProBook 4740s               | [457a56d75c](https://linux-hardware.org/?probe=457a56d75c) | May 26, 2023 |
| ASUSTek       | G50VT                       | [6e4a2588b1](https://linux-hardware.org/?probe=6e4a2588b1) | May 26, 2023 |
| Google        | Lars                        | [25cc6549c3](https://linux-hardware.org/?probe=25cc6549c3) | May 25, 2023 |
| HP            | ProBook 6440b               | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| Apple         | MacBookAir4,1               | [d25345cb25](https://linux-hardware.org/?probe=d25345cb25) | May 25, 2023 |
| HP            | Pavilion g6                 | [f6fbdf57b5](https://linux-hardware.org/?probe=f6fbdf57b5) | May 24, 2023 |
| HP            | Pavilion Notebook 15-bc5... | [933989a15b](https://linux-hardware.org/?probe=933989a15b) | May 24, 2023 |
| HP            | Stream Notebook             | [74d40533fc](https://linux-hardware.org/?probe=74d40533fc) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [8c7d3913b8](https://linux-hardware.org/?probe=8c7d3913b8) | May 24, 2023 |
| Apple         | MacBookPro7,1               | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| Apple         | MacBookPro7,1               | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [08746538f6](https://linux-hardware.org/?probe=08746538f6) | May 23, 2023 |
| Dell          | Latitude E5450              | [642802d511](https://linux-hardware.org/?probe=642802d511) | May 23, 2023 |
| Dell          | Inspiron 1501               | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| HP            | Pavilion g6                 | [4d0edc38d5](https://linux-hardware.org/?probe=4d0edc38d5) | May 23, 2023 |
| Packard Be... | EasyNote MH35               | [ea7710b373](https://linux-hardware.org/?probe=ea7710b373) | May 22, 2023 |
| Acer          | Aspire A515-56              | [dfb369a8d2](https://linux-hardware.org/?probe=dfb369a8d2) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [81477cd76f](https://linux-hardware.org/?probe=81477cd76f) | May 22, 2023 |
| HP            | EliteBook Folio G1          | [73d4310fa2](https://linux-hardware.org/?probe=73d4310fa2) | May 22, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [6bef224193](https://linux-hardware.org/?probe=6bef224193) | May 20, 2023 |
| Apple         | MacBookAir7,2               | [d11ecdffaf](https://linux-hardware.org/?probe=d11ecdffaf) | May 20, 2023 |
| Dell          | Latitude E7450              | [b76cb7567c](https://linux-hardware.org/?probe=b76cb7567c) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [aae519e65d](https://linux-hardware.org/?probe=aae519e65d) | May 19, 2023 |
| Tactus        | GeoBook 140                 | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0608bc6ac3](https://linux-hardware.org/?probe=0608bc6ac3) | May 18, 2023 |
| Philco        | PHN14C                      | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Acer          | Aspire A514-55              | [e096b3a75c](https://linux-hardware.org/?probe=e096b3a75c) | May 18, 2023 |
| Apple         | MacBookAir7,2               | [cadb0eb363](https://linux-hardware.org/?probe=cadb0eb363) | May 17, 2023 |
| Apple         | MacBookAir7,2               | [cd3c24c6a2](https://linux-hardware.org/?probe=cd3c24c6a2) | May 17, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [e18deba45b](https://linux-hardware.org/?probe=e18deba45b) | May 17, 2023 |
| Framework     | Laptop                      | [b8739c141d](https://linux-hardware.org/?probe=b8739c141d) | May 16, 2023 |
| Dell          | XPS 17 9700                 | [7b95691784](https://linux-hardware.org/?probe=7b95691784) | May 15, 2023 |
| Samsung       | N150/N210/N220              | [3f18889439](https://linux-hardware.org/?probe=3f18889439) | May 15, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [03c67bbed5](https://linux-hardware.org/?probe=03c67bbed5) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | [496f6048ec](https://linux-hardware.org/?probe=496f6048ec) | May 15, 2023 |
| Apple         | MacBookPro10,1              | [d27a3510ed](https://linux-hardware.org/?probe=d27a3510ed) | May 14, 2023 |
| HP            | Presario CQ61               | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Google        | Bluebird                    | [c10880ed1b](https://linux-hardware.org/?probe=c10880ed1b) | May 14, 2023 |
| Acer          | Aspire E5-574               | [89fbcb7903](https://linux-hardware.org/?probe=89fbcb7903) | May 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [83e208da09](https://linux-hardware.org/?probe=83e208da09) | May 14, 2023 |
| Lenovo        | IdeaPad Z470                | [2b11351f94](https://linux-hardware.org/?probe=2b11351f94) | May 14, 2023 |
| Dell          | Latitude 3340               | [59d83d9cef](https://linux-hardware.org/?probe=59d83d9cef) | May 14, 2023 |
| SKIKK         | Niflheim 17 II              | [ce9c27f16f](https://linux-hardware.org/?probe=ce9c27f16f) | May 14, 2023 |
| Chuwi         | GemiBook XPro               | [53b6692944](https://linux-hardware.org/?probe=53b6692944) | May 13, 2023 |
| Chuwi         | GemiBook XPro               | [297921aabf](https://linux-hardware.org/?probe=297921aabf) | May 13, 2023 |
| Acer          | Aspire E1-570               | [135675c3ad](https://linux-hardware.org/?probe=135675c3ad) | May 13, 2023 |
| Google        | Kled                        | [f4e834ff36](https://linux-hardware.org/?probe=f4e834ff36) | May 12, 2023 |
| Dell          | Precision M2800             | [571407d9a3](https://linux-hardware.org/?probe=571407d9a3) | May 12, 2023 |
| Chuwi         | GemiBook XPro               | [e13fe43842](https://linux-hardware.org/?probe=e13fe43842) | May 12, 2023 |
| HP            | ProBook 4535s               | [0d2f9561ce](https://linux-hardware.org/?probe=0d2f9561ce) | May 12, 2023 |
| HP            | EliteBook 820 G4            | [34bd8e2402](https://linux-hardware.org/?probe=34bd8e2402) | May 12, 2023 |
| HP            | OMEN by Laptop              | [5a1484127d](https://linux-hardware.org/?probe=5a1484127d) | May 12, 2023 |
| Apple         | MacBookPro10,1              | [381ca3ca78](https://linux-hardware.org/?probe=381ca3ca78) | May 11, 2023 |
| HP            | OMEN by Laptop              | [2c8128a196](https://linux-hardware.org/?probe=2c8128a196) | May 11, 2023 |
| HP            | EliteBook 820 G4            | [a7327f2e2e](https://linux-hardware.org/?probe=a7327f2e2e) | May 11, 2023 |
| HP            | EliteBook 745 G3            | [256ad0c4d8](https://linux-hardware.org/?probe=256ad0c4d8) | May 11, 2023 |
| Acer          | Aspire A315-23              | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Toshiba       | TECRA M10                   | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| HP            | Pavilion dv7                | [794d198929](https://linux-hardware.org/?probe=794d198929) | May 10, 2023 |
| ASUSTek       | GL702VI                     | [3598875ef3](https://linux-hardware.org/?probe=3598875ef3) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [372fa59e86](https://linux-hardware.org/?probe=372fa59e86) | May 09, 2023 |
| HP            | EliteBook 840 G4            | [9ac068efc7](https://linux-hardware.org/?probe=9ac068efc7) | May 09, 2023 |
| Dell          | Latitude E6520              | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | Laptop 15                   | [20a0a03b80](https://linux-hardware.org/?probe=20a0a03b80) | May 08, 2023 |
| Acer          | Aspire E5-574               | [d48affb6b2](https://linux-hardware.org/?probe=d48affb6b2) | May 08, 2023 |
| HP            | 655                         | [be3dec1f65](https://linux-hardware.org/?probe=be3dec1f65) | May 08, 2023 |
| Positivo      | S14CT01                     | [63a129c031](https://linux-hardware.org/?probe=63a129c031) | May 08, 2023 |
| Dell          | Latitude 5520               | [4d8ef45cbc](https://linux-hardware.org/?probe=4d8ef45cbc) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [0304fddec7](https://linux-hardware.org/?probe=0304fddec7) | May 07, 2023 |
| SKIKK         | Niflheim 17 II              | [2a30823af1](https://linux-hardware.org/?probe=2a30823af1) | May 07, 2023 |
| Fujitsu Si... | AMILO PRO V3515             | [a6da9a31d7](https://linux-hardware.org/?probe=a6da9a31d7) | May 06, 2023 |
| Dell          | Inspiron 3501               | [b7bf9f8683](https://linux-hardware.org/?probe=b7bf9f8683) | May 06, 2023 |
| HP            | ProBook 6570b               | [480e352bf8](https://linux-hardware.org/?probe=480e352bf8) | May 05, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9a0649d500](https://linux-hardware.org/?probe=9a0649d500) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [d8582f94de](https://linux-hardware.org/?probe=d8582f94de) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [4ac4356e10](https://linux-hardware.org/?probe=4ac4356e10) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [37fd24fab6](https://linux-hardware.org/?probe=37fd24fab6) | May 05, 2023 |
| Lenovo        | ThinkPad T520 4242A25       | [6290e7f2fb](https://linux-hardware.org/?probe=6290e7f2fb) | May 05, 2023 |
| Unknown       | X133                        | [b38ee0b3cc](https://linux-hardware.org/?probe=b38ee0b3cc) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [cf49833602](https://linux-hardware.org/?probe=cf49833602) | May 04, 2023 |
| HP            | EliteBook 8470p             | [9684be9c3a](https://linux-hardware.org/?probe=9684be9c3a) | May 04, 2023 |
| Unknown       | E450                        | [a3261aab47](https://linux-hardware.org/?probe=a3261aab47) | May 04, 2023 |
| Dell          | XPS 15 9560                 | [15160b0649](https://linux-hardware.org/?probe=15160b0649) | May 04, 2023 |
| KUU           | Andes II                    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Acer          | Aspire E1-570               | [bf515886ac](https://linux-hardware.org/?probe=bf515886ac) | May 03, 2023 |
| Acer          | Aspire V5-531               | [d8c61ad691](https://linux-hardware.org/?probe=d8c61ad691) | May 02, 2023 |
| Dell          | Latitude E6540              | [e6f334c91c](https://linux-hardware.org/?probe=e6f334c91c) | May 01, 2023 |
| Acer          | Aspire A315-21              | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| ASUSTek       | K53U                        | [0745a61353](https://linux-hardware.org/?probe=0745a61353) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| Lenovo        | IdeaPad 320-17IKB 80XM      | [e316615297](https://linux-hardware.org/?probe=e316615297) | May 01, 2023 |
| Acer          | Aspire E5-574               | [bcd38374a3](https://linux-hardware.org/?probe=bcd38374a3) | May 01, 2023 |
| HP            | Pavilion dv7                | [68b51fde68](https://linux-hardware.org/?probe=68b51fde68) | Apr 30, 2023 |
| Positivo      | S14CT01                     | [b11ef938e1](https://linux-hardware.org/?probe=b11ef938e1) | Apr 29, 2023 |
| Toshiba       | Satellite C650D             | [472dedd62a](https://linux-hardware.org/?probe=472dedd62a) | Apr 29, 2023 |
| Sony          | VPCF215FX                   | [49c7606269](https://linux-hardware.org/?probe=49c7606269) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [58b09d7887](https://linux-hardware.org/?probe=58b09d7887) | Apr 29, 2023 |
| Apple         | MacBook6,1                  | [7d91fe30f7](https://linux-hardware.org/?probe=7d91fe30f7) | Apr 29, 2023 |
| Positivo      | S14CT01                     | [58988f4876](https://linux-hardware.org/?probe=58988f4876) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e908fdb73d](https://linux-hardware.org/?probe=e908fdb73d) | Apr 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [a984eefe43](https://linux-hardware.org/?probe=a984eefe43) | Apr 28, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d9010fa8d0](https://linux-hardware.org/?probe=d9010fa8d0) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| HP            | Laptop 14-em0xxx            | [8d06549ae0](https://linux-hardware.org/?probe=8d06549ae0) | Apr 28, 2023 |
| Lenovo        | IdeaPad Y470                | [58c809428e](https://linux-hardware.org/?probe=58c809428e) | Apr 28, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [f1290d4846](https://linux-hardware.org/?probe=f1290d4846) | Apr 28, 2023 |
| Dell          | Vostro 1510                 | [71c860d51c](https://linux-hardware.org/?probe=71c860d51c) | Apr 26, 2023 |
| Medion        | E2215T MD60198              | [390ccbba6f](https://linux-hardware.org/?probe=390ccbba6f) | Apr 26, 2023 |
| Acer          | Aspire A515-57              | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Lenovo        | 3000 N200 0769A97           | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [c40de2e155](https://linux-hardware.org/?probe=c40de2e155) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [7abd61de30](https://linux-hardware.org/?probe=7abd61de30) | Apr 25, 2023 |
| HP            | EliteBook 2730p             | [51c0fadfdb](https://linux-hardware.org/?probe=51c0fadfdb) | Apr 25, 2023 |
| Lenovo        | ThinkPad T430 2347GU8       | [927c9a0377](https://linux-hardware.org/?probe=927c9a0377) | Apr 25, 2023 |
| Toshiba       | Satellite C45-A             | [7720195dfe](https://linux-hardware.org/?probe=7720195dfe) | Apr 24, 2023 |
| Dell          | Inspiron 5565               | [6622474d4b](https://linux-hardware.org/?probe=6622474d4b) | Apr 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [60d1d4aec8](https://linux-hardware.org/?probe=60d1d4aec8) | Apr 24, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [c087d6cbae](https://linux-hardware.org/?probe=c087d6cbae) | Apr 24, 2023 |
| Dell          | XPS 15 9530                 | [d9429d7e06](https://linux-hardware.org/?probe=d9429d7e06) | Apr 23, 2023 |
| Lenovo        | ThinkPad T440s 20ARS1BH0... | [b76462c15b](https://linux-hardware.org/?probe=b76462c15b) | Apr 23, 2023 |
| MSI           | GP62 7RD                    | [277bb2d2e3](https://linux-hardware.org/?probe=277bb2d2e3) | Apr 23, 2023 |
| Acer          | AOD270                      | [d7d653d3d6](https://linux-hardware.org/?probe=d7d653d3d6) | Apr 23, 2023 |
| HP            | Laptop 14-em0xxx            | [55ea4ded18](https://linux-hardware.org/?probe=55ea4ded18) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [ca0be4b423](https://linux-hardware.org/?probe=ca0be4b423) | Apr 22, 2023 |
| Lenovo        | B590 62743NG                | [74e38a8db9](https://linux-hardware.org/?probe=74e38a8db9) | Apr 22, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | [e472034313](https://linux-hardware.org/?probe=e472034313) | Apr 21, 2023 |
| AIERXUAN      | XIAOXUAN Pro                | [e500ddd5d9](https://linux-hardware.org/?probe=e500ddd5d9) | Apr 21, 2023 |
| Dell          | Inspiron 3531               | [6222a9aa08](https://linux-hardware.org/?probe=6222a9aa08) | Apr 21, 2023 |
| MSI           | GS73VR 7RF                  | [2eb85cc7fe](https://linux-hardware.org/?probe=2eb85cc7fe) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7d380bf016](https://linux-hardware.org/?probe=7d380bf016) | Apr 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [7029b5ee48](https://linux-hardware.org/?probe=7029b5ee48) | Apr 20, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | [9093d27c30](https://linux-hardware.org/?probe=9093d27c30) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [069a675d2a](https://linux-hardware.org/?probe=069a675d2a) | Apr 19, 2023 |
| Dell          | XPS 15 9530                 | [bb0be3d9e3](https://linux-hardware.org/?probe=bb0be3d9e3) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [e58c3ad9d7](https://linux-hardware.org/?probe=e58c3ad9d7) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [1548cc4309](https://linux-hardware.org/?probe=1548cc4309) | Apr 19, 2023 |
| Notebook      | NL40_50CU                   | [85c7be8d12](https://linux-hardware.org/?probe=85c7be8d12) | Apr 19, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | [7da02a75b5](https://linux-hardware.org/?probe=7da02a75b5) | Apr 18, 2023 |
| Acer          | Aspire E5-574               | [2f60207985](https://linux-hardware.org/?probe=2f60207985) | Apr 17, 2023 |
| Lenovo        | Yoga 2 13 20344             | [895f57e6d5](https://linux-hardware.org/?probe=895f57e6d5) | Apr 17, 2023 |
| Dell          | Vostro 3580                 | [b7d9953b54](https://linux-hardware.org/?probe=b7d9953b54) | Apr 16, 2023 |
| Lenovo        | Y50-70 20378                | [f146ce9da7](https://linux-hardware.org/?probe=f146ce9da7) | Apr 16, 2023 |
| Apple         | MacBookPro5,3               | [ea8d83a743](https://linux-hardware.org/?probe=ea8d83a743) | Apr 16, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1DU01    | [3fc78b3451](https://linux-hardware.org/?probe=3fc78b3451) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [a56688fd70](https://linux-hardware.org/?probe=a56688fd70) | Apr 16, 2023 |
| HONOR         | BBR-WAX9                    | [798405022f](https://linux-hardware.org/?probe=798405022f) | Apr 16, 2023 |
| AZW           | SEi                         | [a382976bf2](https://linux-hardware.org/?probe=a382976bf2) | Apr 15, 2023 |
| AZW           | SEi                         | [980b83cf5e](https://linux-hardware.org/?probe=980b83cf5e) | Apr 15, 2023 |
| Acer          | Aspire V3-772               | [2b6f0394d7](https://linux-hardware.org/?probe=2b6f0394d7) | Apr 15, 2023 |
| Acer          | Aspire ES1-731G             | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [ba3d9dd7e7](https://linux-hardware.org/?probe=ba3d9dd7e7) | Apr 15, 2023 |
| HP            | Pavilion Power Laptop 15... | [b66c208e18](https://linux-hardware.org/?probe=b66c208e18) | Apr 15, 2023 |
| Apple         | MacBookPro14,1              | [2ca7c3fccc](https://linux-hardware.org/?probe=2ca7c3fccc) | Apr 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [a4c5130b84](https://linux-hardware.org/?probe=a4c5130b84) | Apr 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e122e8dab8](https://linux-hardware.org/?probe=e122e8dab8) | Apr 15, 2023 |
| Positivo      | Q4128C-S                    | [8dc2eb7738](https://linux-hardware.org/?probe=8dc2eb7738) | Apr 14, 2023 |
| HP            | EliteBook 830 G6            | [75ce029800](https://linux-hardware.org/?probe=75ce029800) | Apr 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [9e6cfba525](https://linux-hardware.org/?probe=9e6cfba525) | Apr 13, 2023 |
| Acer          | Aspire E5-771G              | [504d600530](https://linux-hardware.org/?probe=504d600530) | Apr 13, 2023 |
| HP            | Compaq Presario F700        | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Dell          | Inspiron 1545               | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| Acer          | Aspire 5742G                | [878333e620](https://linux-hardware.org/?probe=878333e620) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [b504683b39](https://linux-hardware.org/?probe=b504683b39) | Apr 12, 2023 |
| Acer          | Aspire A315-56              | [8b8d053221](https://linux-hardware.org/?probe=8b8d053221) | Apr 12, 2023 |
| Toshiba       | Satellite C650D             | [fb8b24d111](https://linux-hardware.org/?probe=fb8b24d111) | Apr 12, 2023 |
| Apple         | MacBookPro14,2              | [1bc09aed8a](https://linux-hardware.org/?probe=1bc09aed8a) | Apr 10, 2023 |
| Dell          | XPS 13 9343                 | [f847287142](https://linux-hardware.org/?probe=f847287142) | Apr 09, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [8b461d224b](https://linux-hardware.org/?probe=8b461d224b) | Apr 06, 2023 |
| HP            | ProBook 4540s               | [02754e47f3](https://linux-hardware.org/?probe=02754e47f3) | Apr 05, 2023 |
| Acer          | Aspire 5742G                | [5363e4031e](https://linux-hardware.org/?probe=5363e4031e) | Apr 05, 2023 |
| HP            | Notebook                    | [4ac4839ccd](https://linux-hardware.org/?probe=4ac4839ccd) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | [5a864191a9](https://linux-hardware.org/?probe=5a864191a9) | Apr 05, 2023 |
| HP            | EliteBook 8460p             | [bb24498044](https://linux-hardware.org/?probe=bb24498044) | Apr 05, 2023 |
| Google        | Cyan                        | [f02aa2a210](https://linux-hardware.org/?probe=f02aa2a210) | Apr 04, 2023 |
| Toshiba       | Satellite C650              | [190547d5cd](https://linux-hardware.org/?probe=190547d5cd) | Apr 03, 2023 |
| Dell          | Latitude E6430              | [5c205ea646](https://linux-hardware.org/?probe=5c205ea646) | Apr 03, 2023 |
| Fujitsu       | LIFEBOOK T935               | [1cc4178b9a](https://linux-hardware.org/?probe=1cc4178b9a) | Apr 02, 2023 |
| Apple         | MacBookPro11,2              | [f78d5a9d04](https://linux-hardware.org/?probe=f78d5a9d04) | Apr 02, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [45086032e1](https://linux-hardware.org/?probe=45086032e1) | Apr 02, 2023 |
| Notebook      | NJ50GU                      | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| Lenovo        | V570 1066EDG                | [8a8a256b79](https://linux-hardware.org/?probe=8a8a256b79) | Apr 02, 2023 |
| Monster       | HUMA H4 V5.2                | [fdd74dbc8c](https://linux-hardware.org/?probe=fdd74dbc8c) | Apr 02, 2023 |
| Dell          | Vostro 1520                 | [2132a3308c](https://linux-hardware.org/?probe=2132a3308c) | Apr 01, 2023 |
| Lenovo        | ThinkPad T410 2518P9G       | [4f74fa6cd2](https://linux-hardware.org/?probe=4f74fa6cd2) | Apr 01, 2023 |
| ASUSTek       | T100TA                      | [1f0b0c32ca](https://linux-hardware.org/?probe=1f0b0c32ca) | Apr 01, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [af258dcd36](https://linux-hardware.org/?probe=af258dcd36) | Mar 31, 2023 |
| ASUSTek       | X450LD                      | [1ca0cdc1e8](https://linux-hardware.org/?probe=1ca0cdc1e8) | Mar 31, 2023 |
| Positivo      | S14SL01                     | [e1c79f71b7](https://linux-hardware.org/?probe=e1c79f71b7) | Mar 30, 2023 |
| HP            | kip                         | [fe84eac39e](https://linux-hardware.org/?probe=fe84eac39e) | Mar 30, 2023 |
| Positivo      | Q232A                       | [2282c5ce96](https://linux-hardware.org/?probe=2282c5ce96) | Mar 30, 2023 |
| Positivo      | Q232A                       | [98e6b249af](https://linux-hardware.org/?probe=98e6b249af) | Mar 29, 2023 |
| Dell          | Precision M4500             | [cf7e033a17](https://linux-hardware.org/?probe=cf7e033a17) | Mar 29, 2023 |
| Dell          | Latitude 7430               | [fdef205301](https://linux-hardware.org/?probe=fdef205301) | Mar 29, 2023 |
| Dell          | Latitude 3590               | [9b5971401c](https://linux-hardware.org/?probe=9b5971401c) | Mar 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [ebf2728d28](https://linux-hardware.org/?probe=ebf2728d28) | Mar 29, 2023 |
| Apple         | MacBookPro11,2              | [422e4056ea](https://linux-hardware.org/?probe=422e4056ea) | Mar 28, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [90fa9585c9](https://linux-hardware.org/?probe=90fa9585c9) | Mar 28, 2023 |
| Acer          | Swift SF314-511             | [ccef379a7f](https://linux-hardware.org/?probe=ccef379a7f) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Packard Be... | EasyNote TE11HC             | [dd242e4ae3](https://linux-hardware.org/?probe=dd242e4ae3) | Mar 27, 2023 |
| Dell          | Inspiron 5555               | [cf226d028d](https://linux-hardware.org/?probe=cf226d028d) | Mar 27, 2023 |
| Lenovo        | ThinkPad Edge E530c 3366... | [b4787579d2](https://linux-hardware.org/?probe=b4787579d2) | Mar 25, 2023 |
| HP            | Compaq 6730s                | [ca30390612](https://linux-hardware.org/?probe=ca30390612) | Mar 25, 2023 |
| WEIPAI        | S15                         | [e6a15d7fa9](https://linux-hardware.org/?probe=e6a15d7fa9) | Mar 25, 2023 |
| HP            | Stream Notebook             | [b1ae4b8667](https://linux-hardware.org/?probe=b1ae4b8667) | Mar 25, 2023 |
| ASUSTek       | G53SX                       | [ab9ed0121f](https://linux-hardware.org/?probe=ab9ed0121f) | Mar 25, 2023 |
| Dell          | Latitude E5510              | [8a9a1eec2c](https://linux-hardware.org/?probe=8a9a1eec2c) | Mar 24, 2023 |
| Framework     | Laptop                      | [4e1bd28ce3](https://linux-hardware.org/?probe=4e1bd28ce3) | Mar 24, 2023 |
| Acer          | Aspire A315-59              | [628d2ea05c](https://linux-hardware.org/?probe=628d2ea05c) | Mar 24, 2023 |
| Dell          | Inspiron 5555               | [efab305a00](https://linux-hardware.org/?probe=efab305a00) | Mar 24, 2023 |
| Dell          | Inspiron 3721               | [e992b8f3a0](https://linux-hardware.org/?probe=e992b8f3a0) | Mar 23, 2023 |
| HP            | Pavilion 15                 | [32a0c3ec32](https://linux-hardware.org/?probe=32a0c3ec32) | Mar 23, 2023 |
| HP            | Pavilion dv6                | [625fff449a](https://linux-hardware.org/?probe=625fff449a) | Mar 23, 2023 |
| Dell          | Latitude E7240              | [a3e408033c](https://linux-hardware.org/?probe=a3e408033c) | Mar 21, 2023 |
| ASUSTek       | G53SX                       | [a6c90e3ad8](https://linux-hardware.org/?probe=a6c90e3ad8) | Mar 21, 2023 |
| Dell          | Inspiron 5405               | [bb59d0b5e9](https://linux-hardware.org/?probe=bb59d0b5e9) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| Dell          | Inspiron 5423               | [70f51cbfcb](https://linux-hardware.org/?probe=70f51cbfcb) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| Microtech     | CoreBook                    | [d50c0297a6](https://linux-hardware.org/?probe=d50c0297a6) | Mar 19, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [5c59b55c2a](https://linux-hardware.org/?probe=5c59b55c2a) | Mar 19, 2023 |
| Lenovo        | ThinkPad T420 4180RK8       | [752373923e](https://linux-hardware.org/?probe=752373923e) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [ee8b155a83](https://linux-hardware.org/?probe=ee8b155a83) | Mar 18, 2023 |
| Dell          | Inspiron 3721               | [c7b5ea67bb](https://linux-hardware.org/?probe=c7b5ea67bb) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [07dc0a0959](https://linux-hardware.org/?probe=07dc0a0959) | Mar 18, 2023 |
| ASUSTek       | K52Jc                       | [f61ec5ce9f](https://linux-hardware.org/?probe=f61ec5ce9f) | Mar 18, 2023 |
| ASUSTek       | G53SX                       | [901e03fa6e](https://linux-hardware.org/?probe=901e03fa6e) | Mar 17, 2023 |
| ASUSTek       | G53SX                       | [a012da47e9](https://linux-hardware.org/?probe=a012da47e9) | Mar 17, 2023 |
| HP            | Pavilion dm1                | [8707341105](https://linux-hardware.org/?probe=8707341105) | Mar 16, 2023 |
| Alienware     | 15 R3                       | [c1f4b90efb](https://linux-hardware.org/?probe=c1f4b90efb) | Mar 16, 2023 |
| Dell          | Vostro 1520                 | [a029e62352](https://linux-hardware.org/?probe=a029e62352) | Mar 16, 2023 |
| Lenovo        | Yoga 2 13 20344             | [06dd580c2e](https://linux-hardware.org/?probe=06dd580c2e) | Mar 16, 2023 |
| Google        | Babymega                    | [beead110bb](https://linux-hardware.org/?probe=beead110bb) | Mar 16, 2023 |
| Google        | Babymega                    | [0a45acf149](https://linux-hardware.org/?probe=0a45acf149) | Mar 16, 2023 |
| Acer          | Aspire 5736Z                | [d9e1bb3da7](https://linux-hardware.org/?probe=d9e1bb3da7) | Mar 16, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [f5175006b7](https://linux-hardware.org/?probe=f5175006b7) | Mar 15, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [9565625dc4](https://linux-hardware.org/?probe=9565625dc4) | Mar 15, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [f6a3a68640](https://linux-hardware.org/?probe=f6a3a68640) | Mar 14, 2023 |
| HP            | EliteBook 840 G1            | [cbb20e87cb](https://linux-hardware.org/?probe=cbb20e87cb) | Mar 14, 2023 |
| ASUSTek       | U36SD                       | [74e2dfbbc6](https://linux-hardware.org/?probe=74e2dfbbc6) | Mar 14, 2023 |
| Dell          | Inspiron 5423               | [4987f344f2](https://linux-hardware.org/?probe=4987f344f2) | Mar 14, 2023 |
| Google        | Celes                       | [4fd0271747](https://linux-hardware.org/?probe=4fd0271747) | Mar 13, 2023 |
| MSI           | GF63 Thin 11UC              | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| HP            | Pavilion dv6                | [9d5d0051ea](https://linux-hardware.org/?probe=9d5d0051ea) | Mar 13, 2023 |
| HP            | Pavilion 15                 | [d5eb709e13](https://linux-hardware.org/?probe=d5eb709e13) | Mar 12, 2023 |
| Toshiba       | PORTEGE X30-D               | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [d777dadd73](https://linux-hardware.org/?probe=d777dadd73) | Mar 12, 2023 |
| Novatech      | 15.6 nSpire Laptop          | [f5814aa2e6](https://linux-hardware.org/?probe=f5814aa2e6) | Mar 12, 2023 |
| Lenovo        | ThinkPad X270 20HMS1KL0C    | [f27bb76a32](https://linux-hardware.org/?probe=f27bb76a32) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [fd63e92774](https://linux-hardware.org/?probe=fd63e92774) | Mar 12, 2023 |
| Apple         | MacBookPro9,2               | [6a0426cb65](https://linux-hardware.org/?probe=6a0426cb65) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| HP            | Pavilion dv6                | [fca49aa86c](https://linux-hardware.org/?probe=fca49aa86c) | Mar 11, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [daad1ee8d5](https://linux-hardware.org/?probe=daad1ee8d5) | Mar 11, 2023 |
| HP            | ZBook 17 G2                 | [4b9462a4ff](https://linux-hardware.org/?probe=4b9462a4ff) | Mar 11, 2023 |
| ASUSTek       | T100TAM                     | [1d647e564b](https://linux-hardware.org/?probe=1d647e564b) | Mar 10, 2023 |
| Medion        | Akoya E1318T                | [8b24b109ec](https://linux-hardware.org/?probe=8b24b109ec) | Mar 10, 2023 |
| Acer          | Aspire V3-772               | [6648af3696](https://linux-hardware.org/?probe=6648af3696) | Mar 10, 2023 |
| Lenovo        | G50-45 80E3                 | [807d1626b4](https://linux-hardware.org/?probe=807d1626b4) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | [3b0a7cfbf0](https://linux-hardware.org/?probe=3b0a7cfbf0) | Mar 10, 2023 |
| Toshiba       | Satellite L855              | [08bfa4188e](https://linux-hardware.org/?probe=08bfa4188e) | Mar 10, 2023 |
| HP            | ProBook 4530s               | [e9c9dd943e](https://linux-hardware.org/?probe=e9c9dd943e) | Mar 10, 2023 |
| Dell          | Precision M6700             | [7a02d78344](https://linux-hardware.org/?probe=7a02d78344) | Mar 10, 2023 |
| HP            | ZBook 17 G2                 | [565c8963d4](https://linux-hardware.org/?probe=565c8963d4) | Mar 10, 2023 |
| Lenovo        | ThinkPad T430 2349HNU       | [99d5f17b22](https://linux-hardware.org/?probe=99d5f17b22) | Mar 09, 2023 |
| Acer          | Aspire M3-581G              | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| HP            | Pavilion TS 15              | [5c0b7a773e](https://linux-hardware.org/?probe=5c0b7a773e) | Mar 09, 2023 |
| Dell          | Latitude 3180               | [07a18f8eb1](https://linux-hardware.org/?probe=07a18f8eb1) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [9acfcb9b4f](https://linux-hardware.org/?probe=9acfcb9b4f) | Mar 09, 2023 |
| ASUSTek       | X550CL                      | [21f11cf791](https://linux-hardware.org/?probe=21f11cf791) | Mar 09, 2023 |
| Multilaser    | PC130                       | [37212994df](https://linux-hardware.org/?probe=37212994df) | Mar 09, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0T500     | [e6fd8c46b0](https://linux-hardware.org/?probe=e6fd8c46b0) | Mar 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [d01b6ad50c](https://linux-hardware.org/?probe=d01b6ad50c) | Mar 08, 2023 |
| Dell          | Latitude E4310              | [8dbe3e01fa](https://linux-hardware.org/?probe=8dbe3e01fa) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| Google        | Candy                       | [e74102ff2c](https://linux-hardware.org/?probe=e74102ff2c) | Mar 07, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [3f1ebc8271](https://linux-hardware.org/?probe=3f1ebc8271) | Mar 07, 2023 |
| Google        | Lillipup                    | [33350c987b](https://linux-hardware.org/?probe=33350c987b) | Mar 07, 2023 |
| Packard Be... | EasyNote TM82               | [33de288525](https://linux-hardware.org/?probe=33de288525) | Mar 07, 2023 |
| YJKC          | vBOOK Plus RVP7             | [acdf0dca1d](https://linux-hardware.org/?probe=acdf0dca1d) | Mar 06, 2023 |
| Google        | Lillipup                    | [214481f959](https://linux-hardware.org/?probe=214481f959) | Mar 06, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [df192a1871](https://linux-hardware.org/?probe=df192a1871) | Mar 05, 2023 |
| Clevo         | W251EFQ/W270EFQ             | [12c8945329](https://linux-hardware.org/?probe=12c8945329) | Mar 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [657175938b](https://linux-hardware.org/?probe=657175938b) | Mar 05, 2023 |
| Timi          | TM1701                      | [4faac58613](https://linux-hardware.org/?probe=4faac58613) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | [3e60e33df2](https://linux-hardware.org/?probe=3e60e33df2) | Mar 04, 2023 |
| ASUSTek       | X550CL                      | [c16eae7537](https://linux-hardware.org/?probe=c16eae7537) | Mar 04, 2023 |
| HP            | EliteBook 8570p             | [767045c44e](https://linux-hardware.org/?probe=767045c44e) | Mar 03, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [1237954f03](https://linux-hardware.org/?probe=1237954f03) | Mar 03, 2023 |
| ASUSTek       | UX331UA                     | [310d69ff6f](https://linux-hardware.org/?probe=310d69ff6f) | Mar 03, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | [a3b6a280c1](https://linux-hardware.org/?probe=a3b6a280c1) | Mar 02, 2023 |
| HP            | Notebook                    | [453811c44a](https://linux-hardware.org/?probe=453811c44a) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| ASUSTek       | UX331UA                     | [52c7446693](https://linux-hardware.org/?probe=52c7446693) | Mar 02, 2023 |
| Lenovo        | ThinkPad X230 2333BR3       | [7b17e49d0f](https://linux-hardware.org/?probe=7b17e49d0f) | Mar 02, 2023 |
| ASUSTek       | X200MA                      | [95b0a4d944](https://linux-hardware.org/?probe=95b0a4d944) | Mar 02, 2023 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [e9b7ee04ec](https://linux-hardware.org/?probe=e9b7ee04ec) | Mar 01, 2023 |
| Toshiba       | Satellite S55t-B            | [69734289ba](https://linux-hardware.org/?probe=69734289ba) | Mar 01, 2023 |
| MSI           | Raider GE66 12UHS           | [3fcfdd9fba](https://linux-hardware.org/?probe=3fcfdd9fba) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c698fc199a](https://linux-hardware.org/?probe=c698fc199a) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [7478549a38](https://linux-hardware.org/?probe=7478549a38) | Feb 28, 2023 |
| Dell          | Latitude E6440              | [80131cd2a4](https://linux-hardware.org/?probe=80131cd2a4) | Feb 28, 2023 |
| Dell          | Inspiron 3793               | [d7b51f6048](https://linux-hardware.org/?probe=d7b51f6048) | Feb 27, 2023 |
| HP            | Pavilion dv7                | [d5da5f62b8](https://linux-hardware.org/?probe=d5da5f62b8) | Feb 27, 2023 |
| Acer          | TravelMate B113             | [31691f9681](https://linux-hardware.org/?probe=31691f9681) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [42acb38635](https://linux-hardware.org/?probe=42acb38635) | Feb 27, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [e8c76a33fe](https://linux-hardware.org/?probe=e8c76a33fe) | Feb 27, 2023 |
| Dell          | Vostro 1540                 | [8f09ea4351](https://linux-hardware.org/?probe=8f09ea4351) | Feb 27, 2023 |
| HP            | ENVY m7 Notebook            | [14374fbcc8](https://linux-hardware.org/?probe=14374fbcc8) | Feb 27, 2023 |
| Lenovo        | V570 1066EDG                | [deb326cc4b](https://linux-hardware.org/?probe=deb326cc4b) | Feb 26, 2023 |
| Lenovo        | V570 1066EDG                | [cc220b6122](https://linux-hardware.org/?probe=cc220b6122) | Feb 26, 2023 |
| HP            | 620                         | [e3bf80caf7](https://linux-hardware.org/?probe=e3bf80caf7) | Feb 25, 2023 |
| Dell          | Latitude E6440              | [a4139e4774](https://linux-hardware.org/?probe=a4139e4774) | Feb 25, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [eca93ca661](https://linux-hardware.org/?probe=eca93ca661) | Feb 25, 2023 |
| HP            | Laptop 15-dy2xxx            | [7f88a11698](https://linux-hardware.org/?probe=7f88a11698) | Feb 25, 2023 |
| Digibras      | NH4CU03                     | [85ea6dded1](https://linux-hardware.org/?probe=85ea6dded1) | Feb 24, 2023 |
| Digibras      | NH4CU03                     | [1fb9cfd7d4](https://linux-hardware.org/?probe=1fb9cfd7d4) | Feb 24, 2023 |
| HP            | Laptop 14-ck0xxx            | [bafb67390c](https://linux-hardware.org/?probe=bafb67390c) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Apple         | MacBookPro12,1              | [3b27d3609f](https://linux-hardware.org/?probe=3b27d3609f) | Feb 24, 2023 |
| HP            | ProBook 4545s               | [0f56422e2d](https://linux-hardware.org/?probe=0f56422e2d) | Feb 24, 2023 |
| ASUSTek       | T100TAF                     | [4fce660f2d](https://linux-hardware.org/?probe=4fce660f2d) | Feb 23, 2023 |
| Dell          | Latitude 7480               | [fd80b301db](https://linux-hardware.org/?probe=fd80b301db) | Feb 23, 2023 |
| Lenovo        | G500 20236                  | [294c5c45e6](https://linux-hardware.org/?probe=294c5c45e6) | Feb 23, 2023 |
| DERE          | V14                         | [bb2d40e676](https://linux-hardware.org/?probe=bb2d40e676) | Feb 22, 2023 |
| Teclast       | F7                          | [3f5fdc3aa9](https://linux-hardware.org/?probe=3f5fdc3aa9) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [5d32bc7f7c](https://linux-hardware.org/?probe=5d32bc7f7c) | Feb 21, 2023 |
| HP            | Laptop 15-dy2xxx            | [a00e724475](https://linux-hardware.org/?probe=a00e724475) | Feb 21, 2023 |
| Dell          | System XPS L502X            | [7352f47bb0](https://linux-hardware.org/?probe=7352f47bb0) | Feb 20, 2023 |
| Apple         | MacBookAir7,1               | [5002433b97](https://linux-hardware.org/?probe=5002433b97) | Feb 20, 2023 |
| HP            | 620                         | [c3dae62545](https://linux-hardware.org/?probe=c3dae62545) | Feb 20, 2023 |
| Toshiba       | PORTEGE Z30-A               | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Dell          | Inspiron N4050              | [115fa87a77](https://linux-hardware.org/?probe=115fa87a77) | Feb 20, 2023 |
| Dell          | Latitude E5440              | [10b94a411c](https://linux-hardware.org/?probe=10b94a411c) | Feb 20, 2023 |
| HP            | Laptop 15s-dr0xxx           | [6733a448f9](https://linux-hardware.org/?probe=6733a448f9) | Feb 20, 2023 |
| Packard Be... | EasyNote TS11HR             | [d20a6e81f8](https://linux-hardware.org/?probe=d20a6e81f8) | Feb 19, 2023 |
| Toshiba       | Satellite L50-B             | [3c53a60245](https://linux-hardware.org/?probe=3c53a60245) | Feb 19, 2023 |
| Lenovo        | ThinkPad T460 20FN003LMZ    | [1752223e74](https://linux-hardware.org/?probe=1752223e74) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | [752cdf5b2b](https://linux-hardware.org/?probe=752cdf5b2b) | Feb 19, 2023 |
| Multilaser    | PC130                       | [3526846c1f](https://linux-hardware.org/?probe=3526846c1f) | Feb 19, 2023 |
| Dell          | Inspiron N4050              | [16350a9c3b](https://linux-hardware.org/?probe=16350a9c3b) | Feb 19, 2023 |
| Lenovo        | ThinkPad T570 20H90002MZ    | [6694311da2](https://linux-hardware.org/?probe=6694311da2) | Feb 19, 2023 |
| Lenovo        | ThinkPad T550 20CK003LMZ    | [e3b00dc0f6](https://linux-hardware.org/?probe=e3b00dc0f6) | Feb 18, 2023 |
| HP            | Unknown                     | [3fea6a053b](https://linux-hardware.org/?probe=3fea6a053b) | Feb 18, 2023 |
| Lenovo        | ThinkPad T560 20FJS24T00    | [91a1aa0a0d](https://linux-hardware.org/?probe=91a1aa0a0d) | Feb 18, 2023 |
| Lenovo        | ThinkPad X260 20F600A2MZ    | [bba1f53762](https://linux-hardware.org/?probe=bba1f53762) | Feb 18, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [215ae5796f](https://linux-hardware.org/?probe=215ae5796f) | Feb 18, 2023 |
| Dell          | Inspiron 14 Plus 7420       | [59387e9081](https://linux-hardware.org/?probe=59387e9081) | Feb 18, 2023 |
| Medion        | E7220                       | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| Acer          | Aspire 5738                 | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| ASUSTek       | X450LD                      | [b4fb1ddc5a](https://linux-hardware.org/?probe=b4fb1ddc5a) | Feb 17, 2023 |
| Google        | Robo                        | [303c72db93](https://linux-hardware.org/?probe=303c72db93) | Feb 17, 2023 |
| HP            | Laptop 15-bs1xx             | [88d9514231](https://linux-hardware.org/?probe=88d9514231) | Feb 17, 2023 |
| Dell          | Inspiron 3793               | [b997f44969](https://linux-hardware.org/?probe=b997f44969) | Feb 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [8043264215](https://linux-hardware.org/?probe=8043264215) | Feb 16, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [c08ad0f295](https://linux-hardware.org/?probe=c08ad0f295) | Feb 16, 2023 |
| HP            | ENVY TS Sleekbook 4         | [1189701feb](https://linux-hardware.org/?probe=1189701feb) | Feb 15, 2023 |
| Acer          | Extensa 5230                | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Dell          | Latitude 3320               | [fecee449d4](https://linux-hardware.org/?probe=fecee449d4) | Feb 15, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [6c1c0027b1](https://linux-hardware.org/?probe=6c1c0027b1) | Feb 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c2d957f650](https://linux-hardware.org/?probe=c2d957f650) | Feb 15, 2023 |
| Dell          | System XPS L502X            | [2ea016be2a](https://linux-hardware.org/?probe=2ea016be2a) | Feb 14, 2023 |
| Apple         | MacBook2,1                  | [915e87767b](https://linux-hardware.org/?probe=915e87767b) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [03123ee601](https://linux-hardware.org/?probe=03123ee601) | Feb 14, 2023 |
| Samsung       | 700T1C                      | [66c15f037d](https://linux-hardware.org/?probe=66c15f037d) | Feb 14, 2023 |
| Samsung       | 700T1C                      | [9e154ea3a4](https://linux-hardware.org/?probe=9e154ea3a4) | Feb 14, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [d1edc30dac](https://linux-hardware.org/?probe=d1edc30dac) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| HP            | Compaq 6730b (NB034ET#UU... | [baa5f72e80](https://linux-hardware.org/?probe=baa5f72e80) | Feb 12, 2023 |
| HP            | Notebook                    | [a17adfd867](https://linux-hardware.org/?probe=a17adfd867) | Feb 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6f7c0f381e](https://linux-hardware.org/?probe=6f7c0f381e) | Feb 12, 2023 |
| HP            | Laptop 15-dy2xxx            | [131d5052d1](https://linux-hardware.org/?probe=131d5052d1) | Feb 11, 2023 |
| Dell          | Inspiron 16 5625            | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| Dell          | Vostro 1520                 | [698006ab18](https://linux-hardware.org/?probe=698006ab18) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [518f413d2f](https://linux-hardware.org/?probe=518f413d2f) | Feb 11, 2023 |
| Lenovo        | ThinkPad L480 20LS001AMX    | [a24d7423c4](https://linux-hardware.org/?probe=a24d7423c4) | Feb 11, 2023 |
| Dell          | Latitude E6400              | [8c489c529a](https://linux-hardware.org/?probe=8c489c529a) | Feb 11, 2023 |
| Acer          | TravelMate P253             | [8947050124](https://linux-hardware.org/?probe=8947050124) | Feb 11, 2023 |
| HONOR         | HLYL-WXX9                   | [9d916e8e03](https://linux-hardware.org/?probe=9d916e8e03) | Feb 10, 2023 |
| Acer          | Aspire 5720                 | [9b71ff828e](https://linux-hardware.org/?probe=9b71ff828e) | Feb 10, 2023 |
| HP            | Pavilion Laptop 14-ce0xx... | [49b463f14c](https://linux-hardware.org/?probe=49b463f14c) | Feb 10, 2023 |
| Acer          | Predator G3-571             | [50fe192ea1](https://linux-hardware.org/?probe=50fe192ea1) | Feb 10, 2023 |
| Lenovo        | Yoga 500-14ACL 80NA         | [3bdbc623a8](https://linux-hardware.org/?probe=3bdbc623a8) | Feb 10, 2023 |
| Lenovo        | IdeaPad 3 15ABA7 82RN       | [8513e7eb92](https://linux-hardware.org/?probe=8513e7eb92) | Feb 09, 2023 |
| Positivo      | Smash2                      | [1948e9489d](https://linux-hardware.org/?probe=1948e9489d) | Feb 09, 2023 |
| Positivo      | Smash2                      | [47760ee46f](https://linux-hardware.org/?probe=47760ee46f) | Feb 09, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [5c9ca6cd47](https://linux-hardware.org/?probe=5c9ca6cd47) | Feb 09, 2023 |
| HP            | Pavilion dv7                | [6b7ba3365e](https://linux-hardware.org/?probe=6b7ba3365e) | Feb 08, 2023 |
| Acer          | Aspire 5755G                | [0d0c6fe86c](https://linux-hardware.org/?probe=0d0c6fe86c) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| Lenovo        | V570 1066EDG                | [f963048c4c](https://linux-hardware.org/?probe=f963048c4c) | Feb 08, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [e32b918f95](https://linux-hardware.org/?probe=e32b918f95) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [ae78404854](https://linux-hardware.org/?probe=ae78404854) | Feb 07, 2023 |
| Lenovo        | ThinkPad Edge E430 62715... | [b2c3e0fa85](https://linux-hardware.org/?probe=b2c3e0fa85) | Feb 07, 2023 |
| Multilaser    | UB23X LINUX                 | [d630a4eeff](https://linux-hardware.org/?probe=d630a4eeff) | Feb 07, 2023 |
| Lenovo        | V570 1066EDG                | [e3ffc73e43](https://linux-hardware.org/?probe=e3ffc73e43) | Feb 06, 2023 |
| Acer          | Okinawa                     | [eab799e6dc](https://linux-hardware.org/?probe=eab799e6dc) | Feb 06, 2023 |
| Sony          | VGN-Z31XN_B                 | [d7795277f3](https://linux-hardware.org/?probe=d7795277f3) | Feb 06, 2023 |
| Multilaser    | MLSH1H LINUX                | [0e47e3afd8](https://linux-hardware.org/?probe=0e47e3afd8) | Feb 06, 2023 |
| MSI           | GF63 Thin 11UC              | [a57b142e05](https://linux-hardware.org/?probe=a57b142e05) | Feb 06, 2023 |
| Intel         | Unknown                     | [a1044e362f](https://linux-hardware.org/?probe=a1044e362f) | Feb 06, 2023 |
| Sony          | VPCEG36FX                   | [d760d9e79b](https://linux-hardware.org/?probe=d760d9e79b) | Feb 06, 2023 |
| Acer          | TravelMate P253             | [050d7b5d68](https://linux-hardware.org/?probe=050d7b5d68) | Feb 06, 2023 |
| Lenovo        | ThinkPad T420 4236KU9       | [f536be92d0](https://linux-hardware.org/?probe=f536be92d0) | Feb 06, 2023 |
| Lenovo        | V570 1066EDG                | [00714979fe](https://linux-hardware.org/?probe=00714979fe) | Feb 06, 2023 |
| Acer          | One S1002                   | [2d98ceddca](https://linux-hardware.org/?probe=2d98ceddca) | Feb 05, 2023 |
| Insyde        | CherryTrail                 | [b3ad379bdc](https://linux-hardware.org/?probe=b3ad379bdc) | Feb 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [d33be0bc3f](https://linux-hardware.org/?probe=d33be0bc3f) | Feb 05, 2023 |
| Apple         | MacBookPro5,3               | [e8b8e1b8e5](https://linux-hardware.org/?probe=e8b8e1b8e5) | Feb 04, 2023 |
| Apple         | MacBookPro5,3               | [0f57b84fe7](https://linux-hardware.org/?probe=0f57b84fe7) | Feb 04, 2023 |
| Lenovo        | 14w 81MQ00AVCL              | [bd59f68ce8](https://linux-hardware.org/?probe=bd59f68ce8) | Feb 03, 2023 |
| Dell          | Latitude D630               | [aa435d7701](https://linux-hardware.org/?probe=aa435d7701) | Feb 03, 2023 |
| Dell          | Latitude D630               | [b191402036](https://linux-hardware.org/?probe=b191402036) | Feb 03, 2023 |
| Acer          | Aspire A517-51G             | [7555fafa98](https://linux-hardware.org/?probe=7555fafa98) | Feb 03, 2023 |
| Dell          | Inspiron 5537               | [5bfa4ad142](https://linux-hardware.org/?probe=5bfa4ad142) | Feb 02, 2023 |
| Intel         | Unknown                     | [ba5bda9424](https://linux-hardware.org/?probe=ba5bda9424) | Feb 02, 2023 |
| Sony          | VGN-Z31XN_B                 | [324ab7fbd3](https://linux-hardware.org/?probe=324ab7fbd3) | Feb 02, 2023 |
| HUAWEI        | KLVL-WXXW                   | [741a1b90bd](https://linux-hardware.org/?probe=741a1b90bd) | Feb 02, 2023 |
| MSI           | GF63 Thin 11UC              | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [95e019beb2](https://linux-hardware.org/?probe=95e019beb2) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [b2c18d04be](https://linux-hardware.org/?probe=b2c18d04be) | Feb 01, 2023 |
| Dell          | Latitude 7490               | [050126f7f7](https://linux-hardware.org/?probe=050126f7f7) | Feb 01, 2023 |
| MSI           | Raider GE66 12UHS           | [75e83dae8b](https://linux-hardware.org/?probe=75e83dae8b) | Feb 01, 2023 |
| Dell          | Vostro 1520                 | [3fab7107b7](https://linux-hardware.org/?probe=3fab7107b7) | Feb 01, 2023 |
| Acer          | Aspire A315-53              | [d221bc6b8d](https://linux-hardware.org/?probe=d221bc6b8d) | Feb 01, 2023 |
| Dell          | Latitude E6540              | [156a047a82](https://linux-hardware.org/?probe=156a047a82) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | [a663152b7c](https://linux-hardware.org/?probe=a663152b7c) | Jan 31, 2023 |
| Dell          | Vostro 3700                 | [ae3838cc5d](https://linux-hardware.org/?probe=ae3838cc5d) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [1b083e5b64](https://linux-hardware.org/?probe=1b083e5b64) | Jan 31, 2023 |
| HP            | Compaq 6730s                | [ced2899d20](https://linux-hardware.org/?probe=ced2899d20) | Jan 31, 2023 |
| HP            | Pavilion Notebook           | [912213d849](https://linux-hardware.org/?probe=912213d849) | Jan 30, 2023 |
| HP            | Pavilion Notebook           | [456415a23e](https://linux-hardware.org/?probe=456415a23e) | Jan 30, 2023 |
| Dell          | Latitude E6520              | [f042c5966b](https://linux-hardware.org/?probe=f042c5966b) | Jan 30, 2023 |
| HP            | EliteBook 840 G5            | [7b2b210afd](https://linux-hardware.org/?probe=7b2b210afd) | Jan 30, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1F20... | [39b709296b](https://linux-hardware.org/?probe=39b709296b) | Jan 30, 2023 |
| Dell          | Inspiron 5770               | [b5612c2501](https://linux-hardware.org/?probe=b5612c2501) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [47438e081a](https://linux-hardware.org/?probe=47438e081a) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| Dell          | Precision 5530              | [92399ea8dc](https://linux-hardware.org/?probe=92399ea8dc) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [621aca8707](https://linux-hardware.org/?probe=621aca8707) | Jan 29, 2023 |
| Lenovo        | IdeaPad Y560                | [55fe252b4e](https://linux-hardware.org/?probe=55fe252b4e) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | [62b104b3d2](https://linux-hardware.org/?probe=62b104b3d2) | Jan 29, 2023 |
| Toshiba       | QOSMIO X770                 | [b7cf9bee5c](https://linux-hardware.org/?probe=b7cf9bee5c) | Jan 28, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| Acer          | Swift SF314-511             | [eeaf26e835](https://linux-hardware.org/?probe=eeaf26e835) | Jan 28, 2023 |
| Dell          | Precision 5530              | [a9a54c5b7f](https://linux-hardware.org/?probe=a9a54c5b7f) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a6f188ab67](https://linux-hardware.org/?probe=a6f188ab67) | Jan 28, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [57e0449f0f](https://linux-hardware.org/?probe=57e0449f0f) | Jan 28, 2023 |
| Dell          | Vostro 1520                 | [b2eb47268c](https://linux-hardware.org/?probe=b2eb47268c) | Jan 27, 2023 |
| Dell          | Vostro 1520                 | [6a8408404e](https://linux-hardware.org/?probe=6a8408404e) | Jan 27, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [8bd062dd40](https://linux-hardware.org/?probe=8bd062dd40) | Jan 27, 2023 |
| Dell          | Latitude E7470              | [4245585e75](https://linux-hardware.org/?probe=4245585e75) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| Apple         | MacBook8,1                  | [02cd28549c](https://linux-hardware.org/?probe=02cd28549c) | Jan 27, 2023 |
| HP            | Notebook                    | [4c632128bf](https://linux-hardware.org/?probe=4c632128bf) | Jan 26, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [de7bee1cd6](https://linux-hardware.org/?probe=de7bee1cd6) | Jan 26, 2023 |
| Alienware     | M11xR3                      | [634b7f8eb0](https://linux-hardware.org/?probe=634b7f8eb0) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| HP            | 625                         | [06c4fa5119](https://linux-hardware.org/?probe=06c4fa5119) | Jan 25, 2023 |
| Google        | Blorb                       | [adae28c837](https://linux-hardware.org/?probe=adae28c837) | Jan 25, 2023 |
| HP            | EliteBook Folio 9470m       | [5dfd026f77](https://linux-hardware.org/?probe=5dfd026f77) | Jan 25, 2023 |
| Lenovo        | Z51-70 80K6                 | [c083024afa](https://linux-hardware.org/?probe=c083024afa) | Jan 25, 2023 |
| Sony          | SVE1513C5E                  | [48ee443aef](https://linux-hardware.org/?probe=48ee443aef) | Jan 25, 2023 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [61d7aa3ef9](https://linux-hardware.org/?probe=61d7aa3ef9) | Jan 25, 2023 |
| Google        | Kip                         | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [da316254bb](https://linux-hardware.org/?probe=da316254bb) | Jan 24, 2023 |
| HP            | Laptop 15-dy2xxx            | [af9518a90a](https://linux-hardware.org/?probe=af9518a90a) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [db73b82761](https://linux-hardware.org/?probe=db73b82761) | Jan 24, 2023 |
| Dell          | Latitude E7470              | [6fd520f670](https://linux-hardware.org/?probe=6fd520f670) | Jan 23, 2023 |
| Acer          | Aspire SW5-012              | [247455614c](https://linux-hardware.org/?probe=247455614c) | Jan 23, 2023 |
| HP            | ProBook 440 G5              | [788d350490](https://linux-hardware.org/?probe=788d350490) | Jan 23, 2023 |
| Dell          | Latitude E7470              | [525bcdd915](https://linux-hardware.org/?probe=525bcdd915) | Jan 23, 2023 |
| ASUSTek       | T300CHI                     | [bc020f2d3e](https://linux-hardware.org/?probe=bc020f2d3e) | Jan 23, 2023 |
| Acer          | Aspire A315-59              | [20b73bd156](https://linux-hardware.org/?probe=20b73bd156) | Jan 23, 2023 |
| Lenovo        | E51-80 80QB                 | [37073c4323](https://linux-hardware.org/?probe=37073c4323) | Jan 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6d5ca0b2e3](https://linux-hardware.org/?probe=6d5ca0b2e3) | Jan 22, 2023 |
| Packard Be... | EasyNote TE69KB             | [8363dc95c3](https://linux-hardware.org/?probe=8363dc95c3) | Jan 22, 2023 |
| Dell          | Precision M6800             | [a6beff01de](https://linux-hardware.org/?probe=a6beff01de) | Jan 22, 2023 |
| HP            | 625                         | [838d72399b](https://linux-hardware.org/?probe=838d72399b) | Jan 22, 2023 |
| Lenovo        | V110-15IAP 80TG             | [1707a21fed](https://linux-hardware.org/?probe=1707a21fed) | Jan 22, 2023 |
| Itautec       | Infoway w7430               | [b33318e6e0](https://linux-hardware.org/?probe=b33318e6e0) | Jan 22, 2023 |
| HP            | 625                         | [9a8a243973](https://linux-hardware.org/?probe=9a8a243973) | Jan 21, 2023 |
| I-Life Dig... | ZED AIR 2 SABMS             | [aa8fbd29c9](https://linux-hardware.org/?probe=aa8fbd29c9) | Jan 21, 2023 |
| Dell          | Inspiron 1525               | [548d331968](https://linux-hardware.org/?probe=548d331968) | Jan 21, 2023 |
| ASUSTek       | X453MA                      | [94b155d9c2](https://linux-hardware.org/?probe=94b155d9c2) | Jan 21, 2023 |
| Chuwi         | GemiBook Pro                | [f52614c5aa](https://linux-hardware.org/?probe=f52614c5aa) | Jan 21, 2023 |
| Timi          | Mi Notebook Pro             | [1db1382f0b](https://linux-hardware.org/?probe=1db1382f0b) | Jan 21, 2023 |
| Lenovo        | G560 20042                  | [9c78155cfe](https://linux-hardware.org/?probe=9c78155cfe) | Jan 20, 2023 |
| Lenovo        | G560 20042                  | [61e3ee0517](https://linux-hardware.org/?probe=61e3ee0517) | Jan 20, 2023 |
| ASUSTek       | G74Sx                       | [f3af245bf8](https://linux-hardware.org/?probe=f3af245bf8) | Jan 20, 2023 |
| Acer          | Aspire A317-33              | [b7147af4f6](https://linux-hardware.org/?probe=b7147af4f6) | Jan 20, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d7344938fb](https://linux-hardware.org/?probe=d7344938fb) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [9b3bbccece](https://linux-hardware.org/?probe=9b3bbccece) | Jan 19, 2023 |
| Lenovo        | Z51-70 80K6                 | [90746298fc](https://linux-hardware.org/?probe=90746298fc) | Jan 19, 2023 |
| HP            | ProBook 4740s               | [3392f975ec](https://linux-hardware.org/?probe=3392f975ec) | Jan 19, 2023 |
| Acer          | Aspire E5-774G              | [f3ab78c392](https://linux-hardware.org/?probe=f3ab78c392) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | [4908236396](https://linux-hardware.org/?probe=4908236396) | Jan 19, 2023 |
| Lenovo        | B51-80 80LM                 | [9e17ffeecc](https://linux-hardware.org/?probe=9e17ffeecc) | Jan 19, 2023 |
| Lenovo        | V110-15IAP 80TG             | [cfe9a9d924](https://linux-hardware.org/?probe=cfe9a9d924) | Jan 18, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [7be5d0d09b](https://linux-hardware.org/?probe=7be5d0d09b) | Jan 18, 2023 |
| HP            | 15                          | [cebe1b150e](https://linux-hardware.org/?probe=cebe1b150e) | Jan 18, 2023 |
| Packard Be... | EasyNote TM82               | [49ae8de234](https://linux-hardware.org/?probe=49ae8de234) | Jan 18, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [6f91cb09e7](https://linux-hardware.org/?probe=6f91cb09e7) | Jan 18, 2023 |
| Google        | Kip                         | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | Pavilion dv7                | [2efb4b16de](https://linux-hardware.org/?probe=2efb4b16de) | Jan 17, 2023 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [5ebc1885c3](https://linux-hardware.org/?probe=5ebc1885c3) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [e9e902c625](https://linux-hardware.org/?probe=e9e902c625) | Jan 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [00ebda8ae9](https://linux-hardware.org/?probe=00ebda8ae9) | Jan 17, 2023 |
| Lenovo        | IdeaPad 310-15ABR 80ST      | [473ae331ec](https://linux-hardware.org/?probe=473ae331ec) | Jan 16, 2023 |
| Wortmann      | Mobile 1524                 | [17fc7e2f75](https://linux-hardware.org/?probe=17fc7e2f75) | Jan 16, 2023 |
| Lenovo        | G560 0679                   | [26e16a5898](https://linux-hardware.org/?probe=26e16a5898) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [df8d69926f](https://linux-hardware.org/?probe=df8d69926f) | Jan 15, 2023 |
| Dell          | Inspiron 7437               | [0670d91eb0](https://linux-hardware.org/?probe=0670d91eb0) | Jan 15, 2023 |
| Apple         | MacBookPro5,5               | [2f2fec82c8](https://linux-hardware.org/?probe=2f2fec82c8) | Jan 15, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [331b5e3efa](https://linux-hardware.org/?probe=331b5e3efa) | Jan 14, 2023 |
| ASUSTek       | K75VM                       | [6cd0e1793b](https://linux-hardware.org/?probe=6cd0e1793b) | Jan 14, 2023 |
| Lenovo        | IdeaPadFlex 15D 20334       | [19531b68b1](https://linux-hardware.org/?probe=19531b68b1) | Jan 14, 2023 |
| HP            | EliteBook 745 G5            | [941c62872e](https://linux-hardware.org/?probe=941c62872e) | Jan 14, 2023 |
| HP            | ZBook 17 G3                 | [6c53f137fd](https://linux-hardware.org/?probe=6c53f137fd) | Jan 14, 2023 |
| HP            | Presario F500 (GF795EA#A... | [588148e349](https://linux-hardware.org/?probe=588148e349) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [8a4bbb603e](https://linux-hardware.org/?probe=8a4bbb603e) | Jan 14, 2023 |
| Sony          | SVE1513U1ESI                | [d1c4a0dc83](https://linux-hardware.org/?probe=d1c4a0dc83) | Jan 14, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [ddf679df3a](https://linux-hardware.org/?probe=ddf679df3a) | Jan 14, 2023 |
| Acer          | Swift SF314-511             | [baa87ed4e0](https://linux-hardware.org/?probe=baa87ed4e0) | Jan 13, 2023 |
| Acer          | Swift SF314-511             | [cb94045e18](https://linux-hardware.org/?probe=cb94045e18) | Jan 13, 2023 |
| Fujitsu       | FARQ02010                   | [5d3f5fcee2](https://linux-hardware.org/?probe=5d3f5fcee2) | Jan 13, 2023 |
| ASUSTek       | K93SV                       | [250b4a09a0](https://linux-hardware.org/?probe=250b4a09a0) | Jan 13, 2023 |
| Kiano         | Elegance 13.3               | [2e77ce51b9](https://linux-hardware.org/?probe=2e77ce51b9) | Jan 13, 2023 |
| HP            | Laptop 14-bw0xx             | [0092ec8702](https://linux-hardware.org/?probe=0092ec8702) | Jan 12, 2023 |
| Acer          | Aspire 2920                 | [0766ea34c6](https://linux-hardware.org/?probe=0766ea34c6) | Jan 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [fb5857252b](https://linux-hardware.org/?probe=fb5857252b) | Jan 12, 2023 |
| Samsung       | R520/R522/R620              | [78eb96d148](https://linux-hardware.org/?probe=78eb96d148) | Jan 11, 2023 |
| Samsung       | R520/R522/R620              | [9dfcb68d9a](https://linux-hardware.org/?probe=9dfcb68d9a) | Jan 11, 2023 |
| HP            | Notebook                    | [8df5d522da](https://linux-hardware.org/?probe=8df5d522da) | Jan 10, 2023 |
| HP            | Notebook                    | [c58dde8021](https://linux-hardware.org/?probe=c58dde8021) | Jan 10, 2023 |
| Dell          | Inspiron 3583               | [cb037b984e](https://linux-hardware.org/?probe=cb037b984e) | Jan 10, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [04a9deb0c1](https://linux-hardware.org/?probe=04a9deb0c1) | Jan 10, 2023 |
| Dell          | Inspiron 15-3567            | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| HP            | Pavilion dv6                | [852e84ccaa](https://linux-hardware.org/?probe=852e84ccaa) | Jan 09, 2023 |
| Dell          | Latitude E6510              | [28cceb82e3](https://linux-hardware.org/?probe=28cceb82e3) | Jan 09, 2023 |
| Acer          | Aspire A315-53              | [a8f14a8a8e](https://linux-hardware.org/?probe=a8f14a8a8e) | Jan 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [5bd32eb6f6](https://linux-hardware.org/?probe=5bd32eb6f6) | Jan 08, 2023 |
| ASUSTek       | X555LF                      | [0ff44cdd4f](https://linux-hardware.org/?probe=0ff44cdd4f) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [88ba7d805e](https://linux-hardware.org/?probe=88ba7d805e) | Jan 08, 2023 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | [b5b4c3f6ef](https://linux-hardware.org/?probe=b5b4c3f6ef) | Jan 08, 2023 |
| MSI           | CR62 6M                     | [942ca0f3b3](https://linux-hardware.org/?probe=942ca0f3b3) | Jan 07, 2023 |
| Dell          | Inspiron 5559               | [4c680e9948](https://linux-hardware.org/?probe=4c680e9948) | Jan 07, 2023 |
| HP            | Laptop 17-cp1xxx            | [d699356fd1](https://linux-hardware.org/?probe=d699356fd1) | Jan 07, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | [6148bc3313](https://linux-hardware.org/?probe=6148bc3313) | Jan 06, 2023 |
| Multilaser    | PC024                       | [006690ac84](https://linux-hardware.org/?probe=006690ac84) | Jan 06, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | [1afcc520de](https://linux-hardware.org/?probe=1afcc520de) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [9b828358df](https://linux-hardware.org/?probe=9b828358df) | Jan 05, 2023 |
| Lenovo        | V14-IIL 82C4                | [7cf92f3f43](https://linux-hardware.org/?probe=7cf92f3f43) | Jan 05, 2023 |
| Multilaser    | PC024                       | [8d9a2a1304](https://linux-hardware.org/?probe=8d9a2a1304) | Jan 05, 2023 |
| Dell          | Precision M90               | [b622160555](https://linux-hardware.org/?probe=b622160555) | Jan 05, 2023 |
| HP            | ProBook 4540s               | [6e2638a12e](https://linux-hardware.org/?probe=6e2638a12e) | Jan 04, 2023 |
| Toshiba       | Satellite C50D-B            | [e4bc0d4130](https://linux-hardware.org/?probe=e4bc0d4130) | Jan 04, 2023 |
| Acer          | Aspire V3-772G              | [4ec59dca55](https://linux-hardware.org/?probe=4ec59dca55) | Jan 04, 2023 |
| Sony          | VPCEB3L1E                   | [e8ac8a5d95](https://linux-hardware.org/?probe=e8ac8a5d95) | Jan 04, 2023 |
| Lenovo        | Z51-70 80K6                 | [7fff20462c](https://linux-hardware.org/?probe=7fff20462c) | Jan 03, 2023 |
| HP            | EliteBook Folio 9470m       | [309e449325](https://linux-hardware.org/?probe=309e449325) | Jan 03, 2023 |
| HP            | Pavilion dv7                | [574f62a8ad](https://linux-hardware.org/?probe=574f62a8ad) | Jan 03, 2023 |
| Apple         | MacBookPro12,1              | [ce3dc1998f](https://linux-hardware.org/?probe=ce3dc1998f) | Jan 02, 2023 |
| HP            | EliteBook 2570p             | [fcf5d132a5](https://linux-hardware.org/?probe=fcf5d132a5) | Jan 02, 2023 |
| Acer          | Aspire 4310                 | [e179184ea3](https://linux-hardware.org/?probe=e179184ea3) | Jan 02, 2023 |
| Dell          | Latitude E5440              | [d8b08abf08](https://linux-hardware.org/?probe=d8b08abf08) | Jan 02, 2023 |
| HP            | Pavilion dv6                | [d735200dcf](https://linux-hardware.org/?probe=d735200dcf) | Jan 01, 2023 |
| HP            | EliteBook 850 G3            | [64c803c589](https://linux-hardware.org/?probe=64c803c589) | Jan 01, 2023 |
| Toshiba       | Satellite C50-B             | [b1007671e3](https://linux-hardware.org/?probe=b1007671e3) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [91741e63eb](https://linux-hardware.org/?probe=91741e63eb) | Jan 01, 2023 |
| HP            | EliteBook 2760p             | [6ac462efda](https://linux-hardware.org/?probe=6ac462efda) | Jan 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [0360bb01d0](https://linux-hardware.org/?probe=0360bb01d0) | Jan 01, 2023 |
| Dell          | Latitude E5500              | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9220da7abb](https://linux-hardware.org/?probe=9220da7abb) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| Dell          | Latitude E6540              | [e0e5f33e60](https://linux-hardware.org/?probe=e0e5f33e60) | Dec 30, 2022 |
| ASUSTek       | X540YA                      | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| Toshiba       | Satellite C870-1C2          | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Dell          | Latitude 7490               | [0c49efe5e1](https://linux-hardware.org/?probe=0c49efe5e1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Unknown       | Unknown                     | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| MSI           | GF63 Thin 10SC              | [71c1ee486e](https://linux-hardware.org/?probe=71c1ee486e) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [052cdcd8bb](https://linux-hardware.org/?probe=052cdcd8bb) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [940218d084](https://linux-hardware.org/?probe=940218d084) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [047823ffbc](https://linux-hardware.org/?probe=047823ffbc) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [1ba51900a6](https://linux-hardware.org/?probe=1ba51900a6) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| Sony          | VGN-NR32M_S                 | [6ad0da2e88](https://linux-hardware.org/?probe=6ad0da2e88) | Dec 25, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [e968a4fe6d](https://linux-hardware.org/?probe=e968a4fe6d) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [2415ad5980](https://linux-hardware.org/?probe=2415ad5980) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| HP            | Pavilion dv7                | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| HP            | Pavilion g7                 | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| Lenovo        | G500 20236                  | [3e8fb581f0](https://linux-hardware.org/?probe=3e8fb581f0) | Dec 23, 2022 |
| ASUSTek       | G75VX                       | [bb9724d53f](https://linux-hardware.org/?probe=bb9724d53f) | Dec 23, 2022 |
| Dell          | Latitude E4310              | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| HP            | 15 Notebook PC              | [79aabf81c4](https://linux-hardware.org/?probe=79aabf81c4) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| Toshiba       | Satellite L855              | [3caae1ba3b](https://linux-hardware.org/?probe=3caae1ba3b) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Dell          | Inspiron 3583               | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| Sony          | VJZ13A                      | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Dell          | Latitude E4310              | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| MSI           | GS73VR 7RF                  | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| GPD           | G1619-04                    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [b1bd890ed0](https://linux-hardware.org/?probe=b1bd890ed0) | Dec 19, 2022 |
| HP            | ProBook 640 G1              | [cf1ccbf76a](https://linux-hardware.org/?probe=cf1ccbf76a) | Dec 19, 2022 |
| Dell          | Studio XPS 1645             | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| Dell          | Inspiron 7537               | [7064963568](https://linux-hardware.org/?probe=7064963568) | Dec 18, 2022 |
| ASUSTek       | S500CA                      | [55cf134a8b](https://linux-hardware.org/?probe=55cf134a8b) | Dec 18, 2022 |
| HP            | Laptop 15s-fq2xxx           | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| GPU Compan... | GWTC116-2                   | [e64e0ee27a](https://linux-hardware.org/?probe=e64e0ee27a) | Dec 17, 2022 |
| Fusion5       | C60Bv2-128GB                | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| HP            | Compaq 6910p (RM231UT#AB... | [4653b4877b](https://linux-hardware.org/?probe=4653b4877b) | Dec 17, 2022 |
| HP            | 250 G1                      | [07f20cc1ec](https://linux-hardware.org/?probe=07f20cc1ec) | Dec 17, 2022 |
| Jumper        | EZbook                      | [010f6841e5](https://linux-hardware.org/?probe=010f6841e5) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Jumper        | EZbook                      | [bbae74f641](https://linux-hardware.org/?probe=bbae74f641) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| Lenovo        | V130-15IGM 81HL             | [255499abee](https://linux-hardware.org/?probe=255499abee) | Dec 17, 2022 |
| Toshiba       | Satellite P500              | [58163fa1d7](https://linux-hardware.org/?probe=58163fa1d7) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| Google        | Blorb                       | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| Machcreato... | 14                          | [8b69842953](https://linux-hardware.org/?probe=8b69842953) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Lenovo        | ThinkPad T460 20FMS2AN00    | [7db77c4fcd](https://linux-hardware.org/?probe=7db77c4fcd) | Dec 14, 2022 |
| HP            | Pavilion dv7                | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| HP            | Laptop 17-bs0xx             | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| GPU Compan... | GWTC116-2                   | [09b233d518](https://linux-hardware.org/?probe=09b233d518) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Apple         | MacBook4,1                  | [45ad14cbc2](https://linux-hardware.org/?probe=45ad14cbc2) | Dec 12, 2022 |
| Apple         | MacBookPro8,1               | [bc16110ca8](https://linux-hardware.org/?probe=bc16110ca8) | Dec 12, 2022 |
| Toshiba       | Satellite C870-1C2          | [477bcdd546](https://linux-hardware.org/?probe=477bcdd546) | Dec 12, 2022 |
| Alienware     | 18                          | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Sony          | VGN-NR32M_S                 | [f37234d095](https://linux-hardware.org/?probe=f37234d095) | Dec 10, 2022 |
| ASUSTek       | X751SA                      | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | [097b783ae5](https://linux-hardware.org/?probe=097b783ae5) | Dec 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [0f4312c32e](https://linux-hardware.org/?probe=0f4312c32e) | Dec 10, 2022 |
| Dell          | Latitude E7240              | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| HP            | Laptop 14-bw0xx             | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Apple         | MacBookAir5,2               | [30bbadcb93](https://linux-hardware.org/?probe=30bbadcb93) | Dec 09, 2022 |
| Dell          | Inspiron 5566               | [3a1ec09d8a](https://linux-hardware.org/?probe=3a1ec09d8a) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| Dell          | Latitude 7490               | [6021de66f0](https://linux-hardware.org/?probe=6021de66f0) | Dec 07, 2022 |
| HP            | ProBook 640 G1              | [1c99985945](https://linux-hardware.org/?probe=1c99985945) | Dec 07, 2022 |
| Dell          | Studio 1558                 | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| Dell          | Latitude 7490               | [2b29482df2](https://linux-hardware.org/?probe=2b29482df2) | Dec 06, 2022 |
| Dell          | Inspiron 5558               | [f8e7b50548](https://linux-hardware.org/?probe=f8e7b50548) | Dec 06, 2022 |
| Apple         | MacBookAir5,2               | [a4029fd324](https://linux-hardware.org/?probe=a4029fd324) | Dec 06, 2022 |
| Toshiba       | Satellite L855              | [a28616ab1b](https://linux-hardware.org/?probe=a28616ab1b) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Dell          | XPS 13 9370                 | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [9775fe7147](https://linux-hardware.org/?probe=9775fe7147) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| HP            | Pavilion dv7                | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [2ee93ad61d](https://linux-hardware.org/?probe=2ee93ad61d) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [d5ba349e44](https://linux-hardware.org/?probe=d5ba349e44) | Dec 04, 2022 |
| Dell          | Latitude E6540              | [9a547affad](https://linux-hardware.org/?probe=9a547affad) | Dec 04, 2022 |
| Toshiba       | Satellite C870-1C2          | [0e270ccc80](https://linux-hardware.org/?probe=0e270ccc80) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| HP            | Pavilion dv7                | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Dell          | Latitude 5490               | [e74106a982](https://linux-hardware.org/?probe=e74106a982) | Dec 03, 2022 |
| Dell          | Latitude 5490               | [26e6a987d0](https://linux-hardware.org/?probe=26e6a987d0) | Dec 03, 2022 |
| HP            | Pavilion g4                 | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| HP            | EliteBook 830 G5            | [d42891d37b](https://linux-hardware.org/?probe=d42891d37b) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| Acer          | Aspire V5-121               | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| Sony          | VPCEB1M1E                   | [988c78f70d](https://linux-hardware.org/?probe=988c78f70d) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| Dell          | Latitude E5520              | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| Dell          | Studio 1558                 | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| MSI           | GE75 Raider 10SE            | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| Dell          | Latitude E6540              | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| Dell          | System XPS L502X            | [bd45da46bc](https://linux-hardware.org/?probe=bd45da46bc) | Nov 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNP           | [3dd83d6d9d](https://linux-hardware.org/?probe=3dd83d6d9d) | Nov 27, 2022 |
| Dell          | XPS 15 9560                 | [47782768eb](https://linux-hardware.org/?probe=47782768eb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| HP            | Pavilion g6                 | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [c26e52327e](https://linux-hardware.org/?probe=c26e52327e) | Nov 26, 2022 |
| Dell          | Latitude E6540              | [543ca1307c](https://linux-hardware.org/?probe=543ca1307c) | Nov 26, 2022 |
| ASUSTek       | X202E                       | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Toshiba       | Satellite C50D-B            | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [1ed724b75e](https://linux-hardware.org/?probe=1ed724b75e) | Nov 25, 2022 |
| HP            | ENVY m6                     | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| Dell          | XPS 15 9510                 | [2c7485441f](https://linux-hardware.org/?probe=2c7485441f) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| Samsung       | 600B4B/600B5B               | [6cbdda4e27](https://linux-hardware.org/?probe=6cbdda4e27) | Nov 24, 2022 |
| Thomson       | GEN17V3C8WH256              | [7b1a510e2e](https://linux-hardware.org/?probe=7b1a510e2e) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| Toshiba       | Satellite S55t-B            | [4b01021314](https://linux-hardware.org/?probe=4b01021314) | Nov 24, 2022 |
| HP            | Notebook                    | [d65b0a06fe](https://linux-hardware.org/?probe=d65b0a06fe) | Nov 24, 2022 |
| HP            | Notebook                    | [54b351457e](https://linux-hardware.org/?probe=54b351457e) | Nov 24, 2022 |
| HP            | 15                          | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | IdeaPad U400 09932JU        | [cb5d9871d0](https://linux-hardware.org/?probe=cb5d9871d0) | Nov 22, 2022 |
| Apple         | MacBookPro5,4               | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| Apple         | MacBookPro8,1               | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Framework     | Laptop                      | [6cc495c0d9](https://linux-hardware.org/?probe=6cc495c0d9) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [77dcd3bef6](https://linux-hardware.org/?probe=77dcd3bef6) | Nov 19, 2022 |
| GPU Compan... | GWTN156-2BK                 | [a7c034bd91](https://linux-hardware.org/?probe=a7c034bd91) | Nov 19, 2022 |
| Dell          | Latitude E6540              | [4148292f4d](https://linux-hardware.org/?probe=4148292f4d) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [0185c349b9](https://linux-hardware.org/?probe=0185c349b9) | Nov 18, 2022 |
| HP            | 14                          | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [6992e11b21](https://linux-hardware.org/?probe=6992e11b21) | Nov 18, 2022 |
| Dell          | Latitude E6540              | [31752fdaa8](https://linux-hardware.org/?probe=31752fdaa8) | Nov 18, 2022 |
| HP            | 14                          | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| Unknown       | Unknown                     | [ef7af01d47](https://linux-hardware.org/?probe=ef7af01d47) | Nov 18, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.15.0-56-generic | 133       | 6.42%   |
| 5.11.0-38-generic | 101       | 4.87%   |
| 5.15.0-52-generic | 93        | 4.49%   |
| 5.11.0-27-generic | 93        | 4.49%   |
| 5.15.0-58-generic | 89        | 4.29%   |
| 5.15.0-46-generic | 89        | 4.29%   |
| 5.13.0-30-generic | 74        | 3.57%   |
| 5.11.0-37-generic | 67        | 3.23%   |
| 5.11.0-40-generic | 65        | 3.14%   |
| 5.15.0-69-generic | 63        | 3.04%   |
| 5.15.0-67-generic | 63        | 3.04%   |
| 5.11.0-41-generic | 63        | 3.04%   |
| 5.13.0-39-generic | 60        | 2.89%   |
| 5.11.0-34-generic | 57        | 2.75%   |
| 5.11.0-43-generic | 56        | 2.7%    |
| 5.15.0-60-generic | 55        | 2.65%   |
| 5.15.0-76-generic | 52        | 2.51%   |
| 5.15.0-71-generic | 51        | 2.46%   |
| 5.15.0-48-generic | 51        | 2.46%   |
| 5.13.0-44-generic | 48        | 2.32%   |
| 5.13.0-40-generic | 46        | 2.22%   |
| 5.15.0-53-generic | 43        | 2.07%   |
| 5.15.0-78-generic | 42        | 2.03%   |
| 5.13.0-35-generic | 40        | 1.93%   |
| 5.13.0-28-generic | 37        | 1.78%   |
| 5.15.0-41-generic | 35        | 1.69%   |
| 5.15.0-73-generic | 34        | 1.64%   |
| 5.15.0-72-generic | 31        | 1.5%    |
| 5.13.0-52-generic | 31        | 1.5%    |
| 5.13.0-27-generic | 28        | 1.35%   |
| 5.11.0-46-generic | 26        | 1.25%   |
| 5.13.0-41-generic | 25        | 1.21%   |
| 5.11.0-36-generic | 22        | 1.06%   |
| 5.15.0-43-generic | 21        | 1.01%   |
| 5.15.0-75-generic | 20        | 0.96%   |
| 5.13.0-51-generic | 20        | 0.96%   |
| 5.15.0-57-generic | 18        | 0.87%   |
| 5.11.0-44-generic | 18        | 0.87%   |
| 5.13.0-37-generic | 15        | 0.72%   |
| 5.13.0-48-generic | 13        | 0.63%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 886       | 46.71%  |
| 5.11.0  | 549       | 28.94%  |
| 5.13.0  | 406       | 21.4%   |
| 5.8.0   | 23        | 1.21%   |
| 5.14.0  | 8         | 0.42%   |
| 5.18.15 | 2         | 0.11%   |
| 5.16.0  | 2         | 0.11%   |
| 5.10.0  | 2         | 0.11%   |
| 6.3.2   | 1         | 0.05%   |
| 6.3.1   | 1         | 0.05%   |
| 6.2.16  | 1         | 0.05%   |
| 6.2.14  | 1         | 0.05%   |
| 6.0.9   | 1         | 0.05%   |
| 6.0.19  | 1         | 0.05%   |
| 6.0.0   | 1         | 0.05%   |
| 5.4.180 | 1         | 0.05%   |
| 5.4.0   | 1         | 0.05%   |
| 5.19.9  | 1         | 0.05%   |
| 5.19.14 | 1         | 0.05%   |
| 5.19.12 | 1         | 0.05%   |
| 5.19.1  | 1         | 0.05%   |
| 5.19.0  | 1         | 0.05%   |
| 5.18.6  | 1         | 0.05%   |
| 5.16.12 | 1         | 0.05%   |
| 5.15.49 | 1         | 0.05%   |
| 5.15.24 | 1         | 0.05%   |
| 5.13.18 | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 888       | 46.81%  |
| 5.11    | 549       | 28.94%  |
| 5.13    | 407       | 21.45%  |
| 5.8     | 23        | 1.21%   |
| 5.14    | 8         | 0.42%   |
| 5.19    | 5         | 0.26%   |
| 6.0     | 3         | 0.16%   |
| 5.18    | 3         | 0.16%   |
| 5.16    | 3         | 0.16%   |
| 6.3     | 2         | 0.11%   |
| 6.2     | 2         | 0.11%   |
| 5.4     | 2         | 0.11%   |
| 5.10    | 2         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1812      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 1537      | 84.17%  |
| XFCE       | 262       | 14.35%  |
| Unknown    | 14        | 0.77%   |
| X-Cinnamon | 3         | 0.16%   |
| KDE5       | 3         | 0.16%   |
| i3         | 2         | 0.11%   |
| Budgie     | 2         | 0.11%   |
| LXDE       | 1         | 0.05%   |
| KDE        | 1         | 0.05%   |
| Cinnamon   | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1781      | 97.7%   |
| Wayland | 36        | 1.97%   |
| Unknown | 5         | 0.27%   |
| Tty     | 1         | 0.05%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1363      | 74.24%  |
| GDM     | 209       | 11.38%  |
| GDM3    | 186       | 10.13%  |
| LightDM | 75        | 4.08%   |
| SDDM    | 2         | 0.11%   |
| LXDM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 693       | 38.01%  |
| de_DE | 162       | 8.89%   |
| en_GB | 122       | 6.69%   |
| pt_BR | 105       | 5.76%   |
| fr_FR | 71        | 3.89%   |
| it_IT | 66        | 3.62%   |
| es_ES | 66        | 3.62%   |
| en_IN | 58        | 3.18%   |
| en_CA | 51        | 2.8%    |
| pl_PL | 44        | 2.41%   |
| en_AU | 30        | 1.65%   |
| es_MX | 29        | 1.59%   |
| nl_NL | 28        | 1.54%   |
| ru_RU | 23        | 1.26%   |
| en_ZA | 21        | 1.15%   |
| pt_PT | 20        | 1.1%    |
| cs_CZ | 17        | 0.93%   |
| sv_SE | 15        | 0.82%   |
| fr_BE | 13        | 0.71%   |
| de_CH | 13        | 0.71%   |
| tr_TR | 12        | 0.66%   |
| es_AR | 11        | 0.6%    |
| de_AT | 11        | 0.6%    |
| hu_HU | 10        | 0.55%   |
| en_NZ | 10        | 0.55%   |
| es_CL | 9         | 0.49%   |
| nl_BE | 8         | 0.44%   |
| ja_JP | 6         | 0.33%   |
| es_CO | 6         | 0.33%   |
| hr_HR | 5         | 0.27%   |
| es_CR | 5         | 0.27%   |
| en_PH | 5         | 0.27%   |
| el_GR | 5         | 0.27%   |
| ar_EG | 5         | 0.27%   |
| en_IE | 4         | 0.22%   |
| bg_BG | 4         | 0.22%   |
| sr_RS | 3         | 0.16%   |
| ru_UA | 3         | 0.16%   |
| ro_RO | 3         | 0.16%   |
| nb_NO | 3         | 0.16%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1096      | 59.83%  |
| BIOS | 736       | 40.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1701      | 93.36%  |
| Tmpfs   | 34        | 1.87%   |
| Overlay | 33        | 1.81%   |
| Zfs     | 30        | 1.65%   |
| Btrfs   | 17        | 0.93%   |
| Xfs     | 4         | 0.22%   |
| Ext2    | 2         | 0.11%   |
| Ext3    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1471      | 80.08%  |
| GPT     | 292       | 15.9%   |
| MBR     | 74        | 4.03%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1771      | 97.41%  |
| Yes       | 47        | 2.59%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1645      | 90.43%  |
| Yes       | 174       | 9.57%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 393       | 21.69%  |
| Lenovo              | 315       | 17.38%  |
| Dell                | 284       | 15.67%  |
| ASUSTek Computer    | 189       | 10.43%  |
| Acer                | 137       | 7.56%   |
| Toshiba             | 76        | 4.19%   |
| Apple               | 59        | 3.26%   |
| MSI                 | 32        | 1.77%   |
| Samsung Electronics | 31        | 1.71%   |
| Sony                | 27        | 1.49%   |
| Google              | 26        | 1.43%   |
| Unknown             | 18        | 0.99%   |
| Packard Bell        | 17        | 0.94%   |
| HUAWEI              | 14        | 0.77%   |
| Positivo            | 12        | 0.66%   |
| Chuwi               | 10        | 0.55%   |
| Notebook            | 8         | 0.44%   |
| Medion              | 8         | 0.44%   |
| Fujitsu             | 8         | 0.44%   |
| Alienware           | 7         | 0.39%   |
| Multilaser          | 6         | 0.33%   |
| GPU Company         | 6         | 0.33%   |
| LG Electronics      | 5         | 0.28%   |
| Fujitsu Siemens     | 5         | 0.28%   |
| Thomson             | 4         | 0.22%   |
| Razer               | 4         | 0.22%   |
| Microtech           | 4         | 0.22%   |
| Jumper              | 4         | 0.22%   |
| Framework           | 4         | 0.22%   |
| Digibras            | 4         | 0.22%   |
| AMI                 | 4         | 0.22%   |
| Itautec             | 3         | 0.17%   |
| Insyde              | 3         | 0.17%   |
| Gateway             | 3         | 0.17%   |
| TUXEDO              | 2         | 0.11%   |
| Timi                | 2         | 0.11%   |
| Star Labs           | 2         | 0.11%   |
| Semp Toshiba        | 2         | 0.11%   |
| Panasonic           | 2         | 0.11%   |
| Mediacom            | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 27        | 1.49%   |
| HP Notebook                  | 21        | 1.16%   |
| HP Pavilion Notebook         | 14        | 0.77%   |
| HP 15                        | 10        | 0.55%   |
| HP Pavilion dv7              | 8         | 0.44%   |
| HP Pavilion dv6              | 8         | 0.44%   |
| HP Pavilion 15               | 8         | 0.44%   |
| Apple MacBookPro8,1          | 8         | 0.44%   |
| Dell Latitude E6540          | 6         | 0.33%   |
| HP ProBook 640 G1            | 5         | 0.28%   |
| HP Pavilion g6               | 5         | 0.28%   |
| Dell Latitude E6520          | 5         | 0.28%   |
| Dell Inspiron 15-3567        | 5         | 0.28%   |
| Apple MacBookPro12,1         | 5         | 0.28%   |
| Toshiba Satellite C660       | 4         | 0.22%   |
| Toshiba Satellite C55-C      | 4         | 0.22%   |
| Lenovo IdeaPad 3 15ALC6 82KU | 4         | 0.22%   |
| HP Victus by Laptop 16-e0xxx | 4         | 0.22%   |
| HP Stream Notebook           | 4         | 0.22%   |
| HP Stream Laptop 14-ax0XX    | 4         | 0.22%   |
| HP Pavilion g7               | 4         | 0.22%   |
| HP Laptop 15-db0xxx          | 4         | 0.22%   |
| HP Laptop 15-bw0xx           | 4         | 0.22%   |
| HP EliteBook 8460p           | 4         | 0.22%   |
| HP EliteBook 840 G1          | 4         | 0.22%   |
| HP EliteBook 2570p           | 4         | 0.22%   |
| GPU Company GWTC116-2        | 4         | 0.22%   |
| Framework Laptop             | 4         | 0.22%   |
| Digibras NH4CU03             | 4         | 0.22%   |
| Dell Studio 1558             | 4         | 0.22%   |
| Dell Latitude E7440          | 4         | 0.22%   |
| Dell Latitude E6430          | 4         | 0.22%   |
| Dell Latitude E6400          | 4         | 0.22%   |
| Dell Latitude E5500          | 4         | 0.22%   |
| Dell Latitude E5470          | 4         | 0.22%   |
| Dell Latitude 7490           | 4         | 0.22%   |
| Dell Inspiron 5537           | 4         | 0.22%   |
| Dell Inspiron 3542           | 4         | 0.22%   |
| Dell Inspiron 3521           | 4         | 0.22%   |
| Dell Inspiron 1545           | 4         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 124       | 6.84%   |
| Dell Latitude         | 113       | 6.24%   |
| Lenovo IdeaPad        | 103       | 5.68%   |
| Acer Aspire           | 97        | 5.35%   |
| HP Pavilion           | 95        | 5.24%   |
| Dell Inspiron         | 95        | 5.24%   |
| Toshiba Satellite     | 61        | 3.37%   |
| HP EliteBook          | 59        | 3.26%   |
| HP ProBook            | 46        | 2.54%   |
| HP Laptop             | 39        | 2.15%   |
| ASUS VivoBook         | 35        | 1.93%   |
| Unknown               | 27        | 1.49%   |
| HP Notebook           | 21        | 1.16%   |
| Dell Vostro           | 21        | 1.16%   |
| Dell XPS              | 19        | 1.05%   |
| HP Stream             | 18        | 0.99%   |
| HP Compaq             | 18        | 0.99%   |
| Packard Bell EasyNote | 15        | 0.83%   |
| HP ENVY               | 15        | 0.83%   |
| Dell Precision        | 15        | 0.83%   |
| HP 15                 | 12        | 0.66%   |
| ASUS ZenBook          | 12        | 0.66%   |
| ASUS ROG              | 12        | 0.66%   |
| Lenovo Yoga           | 11        | 0.61%   |
| HP OMEN               | 11        | 0.61%   |
| ASUS ASUS             | 10        | 0.55%   |
| Apple MacBookPro8     | 10        | 0.55%   |
| Lenovo Legion         | 8         | 0.44%   |
| Dell Studio           | 8         | 0.44%   |
| Lenovo ThinkBook      | 7         | 0.39%   |
| HP ZBook              | 7         | 0.39%   |
| HP 255                | 7         | 0.39%   |
| Apple MacBookPro11    | 7         | 0.39%   |
| Acer Swift            | 7         | 0.39%   |
| Toshiba PORTEGE       | 6         | 0.33%   |
| Fujitsu LIFEBOOK      | 6         | 0.33%   |
| Toshiba TECRA         | 5         | 0.28%   |
| HP Presario           | 5         | 0.28%   |
| Chuwi HeroBook        | 5         | 0.28%   |
| Chuwi GemiBook        | 5         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2012 | 165       | 9.11%   |
| 2011 | 164       | 9.05%   |
| 2021 | 155       | 8.55%   |
| 2013 | 149       | 8.22%   |
| 2020 | 134       | 7.4%    |
| 2019 | 127       | 7.01%   |
| 2018 | 120       | 6.62%   |
| 2014 | 120       | 6.62%   |
| 2017 | 114       | 6.29%   |
| 2010 | 110       | 6.07%   |
| 2015 | 108       | 5.96%   |
| 2016 | 101       | 5.57%   |
| 2008 | 84        | 4.64%   |
| 2009 | 54        | 2.98%   |
| 2022 | 45        | 2.48%   |
| 2007 | 40        | 2.21%   |
| 2023 | 13        | 0.72%   |
| 2006 | 9         | 0.5%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1812      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1539      | 84.19%  |
| Enabled  | 289       | 15.81%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1782      | 98.34%  |
| Yes  | 30        | 1.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 616       | 33.83%  |
| 3.01-4.0    | 506       | 27.79%  |
| 8.01-16.0   | 242       | 13.29%  |
| 16.01-24.0  | 224       | 12.3%   |
| 1.01-2.0    | 109       | 5.99%   |
| 32.01-64.0  | 72        | 3.95%   |
| 2.01-3.0    | 27        | 1.48%   |
| 64.01-256.0 | 12        | 0.66%   |
| 24.01-32.0  | 9         | 0.49%   |
| 0.51-1.0    | 4         | 0.22%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 808       | 41.06%  |
| 2.01-3.0   | 647       | 32.88%  |
| 3.01-4.0   | 266       | 13.52%  |
| 4.01-8.0   | 176       | 8.94%   |
| 0.51-1.0   | 44        | 2.24%   |
| 8.01-16.0  | 24        | 1.22%   |
| 24.01-32.0 | 2         | 0.1%    |
| 16.01-24.0 | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1400      | 76%     |
| 2      | 387       | 21.01%  |
| 3      | 38        | 2.06%   |
| 4      | 7         | 0.38%   |
| 0      | 7         | 0.38%   |
| 5      | 2         | 0.11%   |
| 8      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1056      | 58.02%  |
| Yes       | 764       | 41.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1399      | 77%     |
| No        | 418       | 23%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1746      | 96.36%  |
| No        | 66        | 3.64%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1301      | 71.02%  |
| No        | 531       | 28.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 388       | 21.35%  |
| Germany      | 177       | 9.74%   |
| Brazil       | 120       | 6.6%    |
| UK           | 105       | 5.78%   |
| Spain        | 72        | 3.96%   |
| Italy        | 67        | 3.69%   |
| France       | 64        | 3.52%   |
| Canada       | 64        | 3.52%   |
| India        | 61        | 3.36%   |
| Netherlands  | 48        | 2.64%   |
| Mexico       | 42        | 2.31%   |
| Poland       | 39        | 2.15%   |
| Australia    | 29        | 1.6%    |
| Russia       | 26        | 1.43%   |
| South Africa | 25        | 1.38%   |
| Belgium      | 25        | 1.38%   |
| Austria      | 25        | 1.38%   |
| Portugal     | 24        | 1.32%   |
| Sweden       | 23        | 1.27%   |
| Switzerland  | 21        | 1.16%   |
| Turkey       | 20        | 1.1%    |
| Czechia      | 19        | 1.05%   |
| Romania      | 17        | 0.94%   |
| Argentina    | 17        | 0.94%   |
| Norway       | 13        | 0.72%   |
| Japan        | 12        | 0.66%   |
| Indonesia    | 12        | 0.66%   |
| Hungary      | 12        | 0.66%   |
| Greece       | 12        | 0.66%   |
| Colombia     | 11        | 0.61%   |
| New Zealand  | 10        | 0.55%   |
| Chile        | 10        | 0.55%   |
| Egypt        | 9         | 0.5%    |
| Finland      | 8         | 0.44%   |
| Bulgaria     | 8         | 0.44%   |
| Ireland      | 7         | 0.39%   |
| Croatia      | 7         | 0.39%   |
| Philippines  | 6         | 0.33%   |
| Nigeria      | 6         | 0.33%   |
| Kenya        | 6         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Berlin            | 14        | 0.74%   |
| Madrid            | 13        | 0.68%   |
| Vienna            | 12        | 0.63%   |
| New York          | 12        | 0.63%   |
| Sao Paulo         | 11        | 0.58%   |
| Rome              | 11        | 0.58%   |
| Munich            | 11        | 0.58%   |
| Sydney            | 10        | 0.53%   |
| Athens            | 10        | 0.53%   |
| Paris             | 9         | 0.47%   |
| Moscow            | 8         | 0.42%   |
| Montreal          | 8         | 0.42%   |
| Johannesburg      | 8         | 0.42%   |
| Hamburg           | 8         | 0.42%   |
| Amsterdam         | 8         | 0.42%   |
| Widnau            | 7         | 0.37%   |
| Toronto           | 7         | 0.37%   |
| Rio de Janeiro    | 7         | 0.37%   |
| London            | 7         | 0.37%   |
| Glasgow           | 7         | 0.37%   |
| Delhi             | 7         | 0.37%   |
| Bogotá           | 7         | 0.37%   |
| Barcelona         | 7         | 0.37%   |
| Valencia          | 6         | 0.32%   |
| Stockholm         | 6         | 0.32%   |
| Seattle           | 6         | 0.32%   |
| Mexico City       | 6         | 0.32%   |
| Melbourne         | 6         | 0.32%   |
| Krakow            | 6         | 0.32%   |
| Kolkata           | 6         | 0.32%   |
| Jakarta           | 6         | 0.32%   |
| Istanbul          | 6         | 0.32%   |
| Frankfurt am Main | 6         | 0.32%   |
| Denver            | 6         | 0.32%   |
| Dallas            | 6         | 0.32%   |
| Bengaluru         | 6         | 0.32%   |
| Austin            | 6         | 0.32%   |
| Zagreb            | 5         | 0.26%   |
| Stuttgart         | 5         | 0.26%   |
| Nairobi           | 5         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 268       | 358    | 12.41%  |
| Seagate                     | 250       | 309    | 11.57%  |
| WDC                         | 231       | 281    | 10.69%  |
| Unknown                     | 203       | 271    | 9.4%    |
| Toshiba                     | 185       | 208    | 8.56%   |
| SanDisk                     | 149       | 173    | 6.9%    |
| Kingston                    | 102       | 127    | 4.72%   |
| Crucial                     | 76        | 93     | 3.52%   |
| Intel                       | 63        | 80     | 2.92%   |
| HGST                        | 62        | 73     | 2.87%   |
| SK hynix                    | 60        | 69     | 2.78%   |
| Hitachi                     | 54        | 66     | 2.5%    |
| Micron Technology           | 50        | 59     | 2.31%   |
| A-DATA Technology           | 31        | 36     | 1.44%   |
| China                       | 28        | 38     | 1.3%    |
| Apple                       | 27        | 33     | 1.25%   |
| KIOXIA                      | 21        | 24     | 0.97%   |
| Intenso                     | 18        | 19     | 0.83%   |
| SPCC                        | 17        | 22     | 0.79%   |
| Netac                       | 16        | 16     | 0.74%   |
| Unknown                     | 15        | 17     | 0.69%   |
| PNY                         | 13        | 15     | 0.6%    |
| Fujitsu                     | 12        | 13     | 0.56%   |
| LITEONIT                    | 11        | 13     | 0.51%   |
| LITEON                      | 11        | 13     | 0.51%   |
| GOODRAM                     | 10        | 11     | 0.46%   |
| Phison                      | 9         | 10     | 0.42%   |
| Patriot                     | 9         | 11     | 0.42%   |
| Transcend                   | 8         | 10     | 0.37%   |
| Silicon Motion              | 8         | 8      | 0.37%   |
| Team                        | 6         | 7      | 0.28%   |
| JMicron Technology          | 6         | 7      | 0.28%   |
| SABRENT                     | 5         | 6      | 0.23%   |
| Phison Electronics          | 5         | 5      | 0.23%   |
| OCZ                         | 5         | 6      | 0.23%   |
| Lite-On                     | 5         | 7      | 0.23%   |
| Lexar                       | 4         | 4      | 0.19%   |
| Kingston Technology Company | 4         | 4      | 0.19%   |
| KingSpec                    | 4         | 4      | 0.19%   |
| ASMT                        | 4         | 4      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 69        | 3.06%   |
| Unknown MMC Card  64GB                              | 55        | 2.44%   |
| Seagate ST1000LM035-1RK172 1TB                      | 35        | 1.55%   |
| Toshiba MQ01ABD100 1TB                              | 29        | 1.28%   |
| Unknown MMC Card  128GB                             | 26        | 1.15%   |
| Kingston SA400S37240G 240GB SSD                     | 25        | 1.11%   |
| Toshiba MQ01ABF050 500GB                            | 24        | 1.06%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 23        | 1.02%   |
| Toshiba MQ04ABF100 1TB                              | 21        | 0.93%   |
| Seagate ST500LT012-1DG142 500GB                     | 21        | 0.93%   |
| SanDisk NVMe SSD Drive 256GB                        | 19        | 0.84%   |
| Kingston SA400S37480G 480GB SSD                     | 19        | 0.84%   |
| Unknown MMC Card  16GB                              | 18        | 0.8%    |
| Samsung NVMe SSD Drive 512GB                        | 18        | 0.8%    |
| Kingston SA400S37120G 120GB SSD                     | 16        | 0.71%   |
| HGST HTS721010A9E630 1TB                            | 15        | 0.66%   |
| Unknown                                             | 15        | 0.66%   |
| Seagate ST9500325AS 500GB                           | 14        | 0.62%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 14        | 0.62%   |
| Crucial CT500MX500SSD1 500GB                        | 13        | 0.58%   |
| Crucial CT240BX500SSD1 240GB                        | 13        | 0.58%   |
| Samsung NVMe SSD Drive 256GB                        | 12        | 0.53%   |
| Intel NVMe SSD Drive 512GB                          | 12        | 0.53%   |
| HGST HTS541010A9E680 1TB                            | 12        | 0.53%   |
| Unknown SD/MMC/MS PRO 128GB                         | 11        | 0.49%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 11        | 0.49%   |
| Seagate Expansion 1TB                               | 11        | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                        | 11        | 0.49%   |
| Samsung SSD 850 EVO 500GB                           | 11        | 0.49%   |
| Samsung SSD 860 EVO 500GB                           | 10        | 0.44%   |
| HGST HTS725050A7E630 500GB                          | 10        | 0.44%   |
| Samsung SSD 870 EVO 1TB                             | 9         | 0.4%    |
| SK hynix NVMe SSD Drive 256GB                       | 8         | 0.35%   |
| Seagate ST9500420AS 500GB                           | 8         | 0.35%   |
| Samsung SSD 860 EVO 250GB                           | 8         | 0.35%   |
| Netac SSD 128GB                                     | 8         | 0.35%   |
| Crucial CT480BX500SSD1 480GB                        | 8         | 0.35%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 7         | 0.31%   |
| SanDisk X400 M.2 2280 256GB SSD                     | 7         | 0.31%   |
| SanDisk SSD PLUS 480GB                              | 7         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 247       | 305    | 33.11%  |
| WDC                 | 184       | 221    | 24.66%  |
| Toshiba             | 145       | 159    | 19.44%  |
| HGST                | 62        | 73     | 8.31%   |
| Hitachi             | 54        | 66     | 7.24%   |
| Samsung Electronics | 14        | 14     | 1.88%   |
| Fujitsu             | 12        | 13     | 1.61%   |
| Unknown             | 11        | 13     | 1.47%   |
| JMicron Technology  | 5         | 6      | 0.67%   |
| ASMT                | 4         | 4      | 0.54%   |
| Apple               | 3         | 3      | 0.4%    |
| USB3.0              | 1         | 1      | 0.13%   |
| SSK                 | 1         | 1      | 0.13%   |
| SABRENT             | 1         | 1      | 0.13%   |
| KESU                | 1         | 1      | 0.13%   |
| Intenso             | 1         | 1      | 0.13%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 142       | 192    | 18.93%  |
| Kingston            | 89        | 113    | 11.87%  |
| SanDisk             | 78        | 91     | 10.4%   |
| Crucial             | 74        | 89     | 9.87%   |
| WDC                 | 29        | 38     | 3.87%   |
| China               | 27        | 37     | 3.6%    |
| A-DATA Technology   | 26        | 31     | 3.47%   |
| Toshiba             | 25        | 28     | 3.33%   |
| Intel               | 22        | 27     | 2.93%   |
| Micron Technology   | 20        | 23     | 2.67%   |
| Apple               | 20        | 24     | 2.67%   |
| SPCC                | 16        | 21     | 2.13%   |
| SK hynix            | 16        | 16     | 2.13%   |
| Netac               | 16        | 16     | 2.13%   |
| PNY                 | 13        | 15     | 1.73%   |
| Intenso             | 12        | 12     | 1.6%    |
| LITEONIT            | 11        | 13     | 1.47%   |
| LITEON              | 11        | 13     | 1.47%   |
| Patriot             | 9         | 11     | 1.2%    |
| GOODRAM             | 9         | 10     | 1.2%    |
| Transcend           | 8         | 10     | 1.07%   |
| Team                | 6         | 7      | 0.8%    |
| OCZ                 | 5         | 6      | 0.67%   |
| Unknown             | 5         | 7      | 0.67%   |
| KingSpec            | 4         | 4      | 0.53%   |
| Plextor             | 3         | 3      | 0.4%    |
| Mushkin             | 3         | 3      | 0.4%    |
| Lexar               | 3         | 3      | 0.4%    |
| Hewlett-Packard     | 3         | 3      | 0.4%    |
| BHT                 | 3         | 4      | 0.4%    |
| Verbatim            | 2         | 2      | 0.27%   |
| Teclast             | 2         | 2      | 0.27%   |
| HS-SSD-E100         | 2         | 2      | 0.27%   |
| Gigabyte Technology | 2         | 2      | 0.27%   |
| Apacer              | 2         | 2      | 0.27%   |
| ZOTAC               | 1         | 1      | 0.13%   |
| Wibtek              | 1         | 1      | 0.13%   |
| Vaseky              | 1         | 2      | 0.13%   |
| TO Exter            | 1         | 1      | 0.13%   |
| T-CREATE            | 1         | 1      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 728       | 882    | 34.78%  |
| SSD     | 721       | 917    | 34.45%  |
| NVMe    | 410       | 533    | 19.59%  |
| MMC     | 206       | 271    | 9.84%   |
| Unknown | 28        | 31     | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1335      | 1746   | 66.25%  |
| NVMe | 408       | 528    | 20.25%  |
| MMC  | 206       | 271    | 10.22%  |
| SAS  | 66        | 89     | 3.28%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 997       | 1256   | 69.82%  |
| 0.51-1.0   | 392       | 487    | 27.45%  |
| 1.01-2.0   | 32        | 44     | 2.24%   |
| 4.01-10.0  | 4         | 6      | 0.28%   |
| 3.01-4.0   | 3         | 6      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 653       | 35.07%  |
| 251-500        | 488       | 26.21%  |
| 501-1000       | 259       | 13.91%  |
| 51-100         | 173       | 9.29%   |
| 21-50          | 124       | 6.66%   |
| 1001-2000      | 61        | 3.28%   |
| 1-20           | 43        | 2.31%   |
| Unknown        | 23        | 1.24%   |
| More than 3000 | 19        | 1.02%   |
| 2001-3000      | 19        | 1.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 810       | 41.69%  |
| 21-50          | 558       | 28.72%  |
| 51-100         | 227       | 11.68%  |
| 101-250        | 192       | 9.88%   |
| 251-500        | 76        | 3.91%   |
| 501-1000       | 38        | 1.96%   |
| Unknown        | 23        | 1.18%   |
| 1001-2000      | 9         | 0.46%   |
| More than 3000 | 7         | 0.36%   |
| 2001-3000      | 3         | 0.15%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB                          | 2         | 2      | 3.85%   |
| Toshiba MQ01ABD100 1TB                           | 2         | 2      | 3.85%   |
| SK hynix BC711 HFM512GD3JX013N 512GB             | 2         | 2      | 3.85%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 2      | 3.85%   |
| HGST HTS545050A7E380 500GB                       | 2         | 3      | 3.85%   |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 1      | 1.92%   |
| WDC WD5000LPVX-75V0TT0 500GB                     | 1         | 1      | 1.92%   |
| WDC WD5000BEVT-24A0RT0 500GB                     | 1         | 1      | 1.92%   |
| WDC WD1200BEVS-60UST0 120GB                      | 1         | 1      | 1.92%   |
| WDC WD10SPZX-75Z10T2 1TB                         | 1         | 1      | 1.92%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 1         | 1      | 1.92%   |
| WDC WD10JPVT-55A1YT0 1TB                         | 1         | 1      | 1.92%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD             | 1         | 1      | 1.92%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD         | 1         | 1      | 1.92%   |
| Toshiba MQ01ABF050 500GB                         | 1         | 1      | 1.92%   |
| Toshiba MQ01ABD075 752GB                         | 1         | 1      | 1.92%   |
| Teclast 128GB NS550-2242 SSD                     | 1         | 1      | 1.92%   |
| Seagate ST9500420AS 500GB                        | 1         | 1      | 1.92%   |
| Seagate ST9500325AS 500GB                        | 1         | 1      | 1.92%   |
| Seagate ST9320310AS 320GB                        | 1         | 1      | 1.92%   |
| Seagate ST9250315AS 250GB                        | 1         | 1      | 1.92%   |
| Seagate ST9200420ASG 200GB                       | 1         | 1      | 1.92%   |
| Seagate ST9160411ASG 160GB                       | 1         | 1      | 1.92%   |
| Seagate ST500LT012-9WS142 500GB                  | 1         | 1      | 1.92%   |
| Seagate ST500LM000-SSHD-8GB                      | 1         | 1      | 1.92%   |
| Seagate ST320LT007-9ZV142 320GB                  | 1         | 1      | 1.92%   |
| Seagate ST1000LX015-1U7172 1TB                   | 1         | 1      | 1.92%   |
| Seagate ST1000LM048-2E7172 1TB                   | 1         | 1      | 1.92%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 1.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 1.92%   |
| Samsung Electronics MZHPV256HDGL-00000 256GB SSD | 1         | 1      | 1.92%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD    | 1         | 1      | 1.92%   |
| Samsung Electronics HM160JI 160GB                | 1         | 1      | 1.92%   |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD            | 1         | 1      | 1.92%   |
| Kingston SUV400S37240G 240GB SSD                 | 1         | 1      | 1.92%   |
| Kingston SA400S37120G 120GB SSD                  | 1         | 1      | 1.92%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD           | 1         | 1      | 1.92%   |
| Hitachi HTS725032A9A364 320GB                    | 1         | 1      | 1.92%   |
| Hitachi HTS547575A9E384 752GB                    | 1         | 1      | 1.92%   |
| Hitachi HTS542516K9SA00 160GB                    | 1         | 1      | 1.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 28.85%  |
| Toshiba             | 8         | 8      | 15.38%  |
| WDC                 | 7         | 7      | 13.46%  |
| HGST                | 6         | 7      | 11.54%  |
| Samsung Electronics | 3         | 3      | 5.77%   |
| Kingston            | 3         | 3      | 5.77%   |
| Hitachi             | 3         | 3      | 5.77%   |
| SK hynix            | 2         | 2      | 3.85%   |
| Teclast             | 1         | 1      | 1.92%   |
| LITEONIT            | 1         | 1      | 1.92%   |
| Hewlett-Packard     | 1         | 1      | 1.92%   |
| Drevo               | 1         | 1      | 1.92%   |
| Unknown             | 1         | 1      | 1.92%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 15        | 15     | 39.47%  |
| WDC                 | 7         | 7      | 18.42%  |
| Toshiba             | 6         | 6      | 15.79%  |
| HGST                | 6         | 7      | 15.79%  |
| Hitachi             | 3         | 3      | 7.89%   |
| Samsung Electronics | 1         | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 39     | 73.08%  |
| SSD  | 12        | 12     | 23.08%  |
| NVMe | 2         | 2      | 3.85%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1576      | 2299   | 84.73%  |
| Works    | 230       | 279    | 12.37%  |
| Malfunc  | 51        | 53     | 2.74%   |
| Failed   | 2         | 2      | 0.11%   |
| Fixed    | 1         | 1      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1302      | 66.16%  |
| AMD                              | 227       | 11.53%  |
| Samsung Electronics              | 136       | 6.91%   |
| SanDisk                          | 78        | 3.96%   |
| SK hynix                         | 43        | 2.18%   |
| Micron Technology                | 31        | 1.58%   |
| KIOXIA                           | 21        | 1.07%   |
| Nvidia                           | 17        | 0.86%   |
| Kingston Technology Company      | 17        | 0.86%   |
| Toshiba America Info Systems     | 16        | 0.81%   |
| Phison Electronics               | 14        | 0.71%   |
| Silicon Motion                   | 10        | 0.51%   |
| ADATA Technology                 | 8         | 0.41%   |
| Micron/Crucial Technology        | 6         | 0.3%    |
| Lite-On Technology               | 5         | 0.25%   |
| Union Memory (Shenzhen)          | 4         | 0.2%    |
| Marvell Technology Group         | 4         | 0.2%    |
| ASMedia Technology               | 4         | 0.2%    |
| VIA Technologies                 | 3         | 0.15%   |
| Silicon Integrated Systems [SiS] | 3         | 0.15%   |
| Realtek Semiconductor            | 3         | 0.15%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.15%   |
| Apple                            | 3         | 0.15%   |
| Yangtze Memory Technologies      | 2         | 0.1%    |
| Solid State Storage Technology   | 2         | 0.1%    |
| Lenovo                           | 2         | 0.1%    |
| Silicon Image                    | 1         | 0.05%   |
| Seagate Technology               | 1         | 0.05%   |
| INNOGRIT                         | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 195       | 9.19%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 169       | 7.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 127       | 5.98%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 119       | 5.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 117       | 5.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 80        | 3.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 69        | 3.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 68        | 3.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 57        | 2.68%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 50        | 2.36%   |
| Intel Volume Management Device NVMe RAID Controller                              | 50        | 2.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 47        | 2.21%   |
| Samsung NVMe SSD Controller 980                                                  | 43        | 2.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 42        | 1.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 38        | 1.79%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 37        | 1.74%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 34        | 1.6%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 31        | 1.46%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 29        | 1.37%   |
| Intel Tiger Lake-LP SATA Controller                                              | 28        | 1.32%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 28        | 1.32%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 24        | 1.13%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 23        | 1.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 23        | 1.08%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 20        | 0.94%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 20        | 0.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 19        | 0.89%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 18        | 0.85%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 17        | 0.8%    |
| Intel Comet Lake SATA AHCI Controller                                            | 17        | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 15        | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 15        | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 14        | 0.66%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 14        | 0.66%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 13        | 0.61%   |
| Intel SSD 660P Series                                                            | 13        | 0.61%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 12        | 0.57%   |
| SK hynix BC511 NVMe SSD                                                          | 10        | 0.47%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 10        | 0.47%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 10        | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1342      | 65.43%  |
| NVMe | 409       | 19.94%  |
| RAID | 174       | 8.48%   |
| IDE  | 126       | 6.14%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1523      | 84.05%  |
| AMD    | 289       | 15.95%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 26        | 1.43%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 26        | 1.43%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 25        | 1.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 25        | 1.38%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 23        | 1.27%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 21        | 1.16%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 20        | 1.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 19        | 1.05%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 19        | 1.05%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 18        | 0.99%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 18        | 0.99%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 18        | 0.99%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 18        | 0.99%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 17        | 0.94%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 17        | 0.94%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 17        | 0.94%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 16        | 0.88%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 15        | 0.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 14        | 0.77%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.77%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 14        | 0.77%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 14        | 0.77%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.72%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 13        | 0.72%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 13        | 0.72%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 13        | 0.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 13        | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 12        | 0.66%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.66%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 12        | 0.66%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 11        | 0.61%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 11        | 0.61%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 11        | 0.61%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 11        | 0.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 0.55%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 10        | 0.55%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 10        | 0.55%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 454       | 25.04%  |
| Intel Core i7                        | 297       | 16.38%  |
| Intel Core i3                        | 185       | 10.2%   |
| Intel Celeron                        | 169       | 9.32%   |
| Intel Core 2 Duo                     | 112       | 6.18%   |
| Other                                | 109       | 6.01%   |
| Intel Atom                           | 68        | 3.75%   |
| Intel Pentium                        | 65        | 3.59%   |
| AMD Ryzen 5                          | 58        | 3.2%    |
| AMD Ryzen 7                          | 44        | 2.43%   |
| AMD A6                               | 26        | 1.43%   |
| AMD A4                               | 26        | 1.43%   |
| AMD A8                               | 18        | 0.99%   |
| AMD A10                              | 17        | 0.94%   |
| Intel Pentium Dual-Core              | 16        | 0.88%   |
| Intel Pentium Dual                   | 12        | 0.66%   |
| AMD Ryzen 3                          | 11        | 0.61%   |
| AMD E1                               | 11        | 0.61%   |
| Intel Core M                         | 10        | 0.55%   |
| Intel Pentium Silver                 | 9         | 0.5%    |
| Intel Core 2                         | 9         | 0.5%    |
| AMD E                                | 9         | 0.5%    |
| AMD Turion 64 X2 Mobile              | 8         | 0.44%   |
| AMD Ryzen 9                          | 6         | 0.33%   |
| AMD Athlon II                        | 6         | 0.33%   |
| Intel Core m5                        | 5         | 0.28%   |
| AMD E2                               | 5         | 0.28%   |
| Intel Pentium Gold                   | 4         | 0.22%   |
| AMD Ryzen 7 PRO                      | 4         | 0.22%   |
| AMD Athlon                           | 4         | 0.22%   |
| Intel Genuine                        | 3         | 0.17%   |
| Intel Celeron Dual-Core              | 3         | 0.17%   |
| Intel Core i9                        | 2         | 0.11%   |
| Intel Celeron M                      | 2         | 0.11%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.11%   |
| AMD Sempron                          | 2         | 0.11%   |
| AMD FX                               | 2         | 0.11%   |
| AMD Athlon II Neo                    | 2         | 0.11%   |
| Intel Xeon                           | 1         | 0.06%   |
| Intel Core m7                        | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1110      | 61.22%  |
| 4      | 536       | 29.56%  |
| 6      | 72        | 3.97%   |
| 8      | 62        | 3.42%   |
| 1      | 20        | 1.1%    |
| 10     | 6         | 0.33%   |
| 14     | 4         | 0.22%   |
| 24     | 1         | 0.06%   |
| 16     | 1         | 0.06%   |
| 3      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1812      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1188      | 65.56%  |
| 1      | 624       | 34.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1812      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 159       | 8.66%   |
| 0x306a9    | 154       | 8.38%   |
| Unknown    | 117       | 6.37%   |
| 0x40651    | 90        | 4.9%    |
| 0x1067a    | 73        | 3.97%   |
| 0x306d4    | 72        | 3.92%   |
| 0x20655    | 69        | 3.76%   |
| 0x406e3    | 68        | 3.7%    |
| 0x806c1    | 65        | 3.54%   |
| 0x30678    | 58        | 3.16%   |
| 0x806e9    | 51        | 2.78%   |
| 0x806ec    | 47        | 2.56%   |
| 0x806ea    | 47        | 2.56%   |
| 0x306c3    | 47        | 2.56%   |
| 0x406c4    | 45        | 2.45%   |
| 0x706a8    | 36        | 1.96%   |
| 0x906ea    | 32        | 1.74%   |
| 0x706e5    | 32        | 1.74%   |
| 0x6fd      | 32        | 1.74%   |
| 0x506c9    | 31        | 1.69%   |
| 0x10676    | 28        | 1.52%   |
| 0x20652    | 27        | 1.47%   |
| 0x906e9    | 26        | 1.42%   |
| 0x406c3    | 26        | 1.42%   |
| 0x08108109 | 21        | 1.14%   |
| 0x07030105 | 21        | 1.14%   |
| 0x0a50000c | 20        | 1.09%   |
| 0xa0652    | 19        | 1.03%   |
| 0x06006705 | 18        | 0.98%   |
| 0x08108102 | 16        | 0.87%   |
| 0x706a1    | 13        | 0.71%   |
| 0x08608103 | 13        | 0.71%   |
| 0x0700010f | 13        | 0.71%   |
| 0x506e3    | 12        | 0.65%   |
| 0x08600106 | 12        | 0.65%   |
| 0x05000119 | 12        | 0.65%   |
| 0x6fb      | 11        | 0.6%    |
| 0x06006704 | 11        | 0.6%    |
| 0x03000027 | 11        | 0.6%    |
| 0x010000c8 | 11        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 232       | 12.8%   |
| SandyBridge      | 164       | 9.05%   |
| IvyBridge        | 160       | 8.83%   |
| Haswell          | 148       | 8.17%   |
| Silvermont       | 138       | 7.62%   |
| Penryn           | 101       | 5.57%   |
| Westmere         | 98        | 5.41%   |
| Skylake          | 83        | 4.58%   |
| TigerLake        | 74        | 4.08%   |
| Broadwell        | 72        | 3.97%   |
| Core             | 60        | 3.31%   |
| Goldmont plus    | 52        | 2.87%   |
| IceLake          | 44        | 2.43%   |
| Excavator        | 42        | 2.32%   |
| Zen+             | 40        | 2.21%   |
| Goldmont         | 33        | 1.82%   |
| Zen 3            | 31        | 1.71%   |
| Puma             | 31        | 1.71%   |
| Unknown          | 30        | 1.66%   |
| Zen 2            | 28        | 1.55%   |
| CometLake        | 23        | 1.27%   |
| Jaguar           | 16        | 0.88%   |
| Bobcat           | 15        | 0.83%   |
| K10              | 13        | 0.72%   |
| Piledriver       | 12        | 0.66%   |
| K10 Llano        | 12        | 0.66%   |
| Nehalem          | 10        | 0.55%   |
| K8 Hammer        | 10        | 0.55%   |
| Alderlake Hybrid | 10        | 0.55%   |
| Bonnell          | 8         | 0.44%   |
| Zen              | 7         | 0.39%   |
| Tremont          | 7         | 0.39%   |
| K8 & K10 hybrid  | 5         | 0.28%   |
| Steamroller      | 3         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1374      | 63.32%  |
| AMD                              | 401       | 18.48%  |
| Nvidia                           | 390       | 17.97%  |
| Silicon Integrated Systems [SiS] | 3         | 0.14%   |
| VIA Technologies                 | 2         | 0.09%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 152       | 6.79%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 146       | 6.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 92        | 4.11%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 72        | 3.22%   |
| Intel Core Processor Integrated Graphics Controller                                      | 70        | 3.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 66        | 2.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 60        | 2.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 58        | 2.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 58        | 2.59%   |
| Intel HD Graphics 620                                                                    | 52        | 2.32%   |
| Intel UHD Graphics 620                                                                   | 47        | 2.1%    |
| Intel HD Graphics 5500                                                                   | 47        | 2.1%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 46        | 2.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 43        | 1.92%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 41        | 1.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 31        | 1.38%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 31        | 1.38%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 30        | 1.34%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 28        | 1.25%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 28        | 1.25%   |
| AMD Renoir                                                                               | 28        | 1.25%   |
| Intel HD Graphics 500                                                                    | 27        | 1.21%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 26        | 1.16%   |
| Intel HD Graphics 630                                                                    | 25        | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 24        | 1.07%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 20        | 0.89%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 19        | 0.85%   |
| AMD Lucienne                                                                             | 19        | 0.85%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 19        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 18        | 0.8%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 18        | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 18        | 0.8%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 16        | 0.71%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 15        | 0.67%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 15        | 0.67%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 13        | 0.58%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 12        | 0.54%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 0.54%   |
| Intel HD Graphics 530                                                                    | 12        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1044      | 57.52%  |
| 1 x AMD        | 270       | 14.88%  |
| Intel + Nvidia | 255       | 14.05%  |
| 1 x Nvidia     | 102       | 5.62%   |
| Intel + AMD    | 71        | 3.91%   |
| AMD + Nvidia   | 31        | 1.71%   |
| 2 x AMD        | 30        | 1.65%   |
| Other          | 5         | 0.28%   |
| 1 x SiS        | 3         | 0.17%   |
| 2 x Nvidia     | 2         | 0.11%   |
| 1 x VIA        | 2         | 0.11%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1589      | 87.36%  |
| Proprietary | 205       | 11.27%  |
| Unknown     | 25        | 1.37%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1238      | 67.36%  |
| 0.01-0.5   | 236       | 12.84%  |
| 1.01-2.0   | 148       | 8.05%   |
| 0.51-1.0   | 122       | 6.64%   |
| 3.01-4.0   | 50        | 2.72%   |
| 5.01-6.0   | 18        | 0.98%   |
| 7.01-8.0   | 14        | 0.76%   |
| 2.01-3.0   | 11        | 0.6%    |
| 8.01-16.0  | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 365       | 19.05%  |
| Chimei Innolux          | 286       | 14.93%  |
| BOE                     | 269       | 14.04%  |
| LG Display              | 263       | 13.73%  |
| Samsung Electronics     | 222       | 11.59%  |
| Chi Mei Optoelectronics | 61        | 3.18%   |
| Apple                   | 58        | 3.03%   |
| Sharp                   | 36        | 1.88%   |
| Goldstar                | 32        | 1.67%   |
| Dell                    | 32        | 1.67%   |
| Lenovo                  | 31        | 1.62%   |
| LG Philips              | 28        | 1.46%   |
| PANDA                   | 25        | 1.3%    |
| InfoVision              | 17        | 0.89%   |
| Hewlett-Packard         | 13        | 0.68%   |
| CPT                     | 11        | 0.57%   |
| Acer                    | 11        | 0.57%   |
| Philips                 | 10        | 0.52%   |
| BenQ                    | 9         | 0.47%   |
| Vizio                   | 8         | 0.42%   |
| Sony                    | 7         | 0.37%   |
| Ancor Communications    | 7         | 0.37%   |
| LGD                     | 6         | 0.31%   |
| AOC                     | 6         | 0.31%   |
| InnoLux Display         | 5         | 0.26%   |
| HannStar                | 5         | 0.26%   |
| BOE Technology Group    | 5         | 0.26%   |
| ASUSTek Computer        | 5         | 0.26%   |
| Toshiba                 | 4         | 0.21%   |
| SLD                     | 4         | 0.21%   |
| Panasonic               | 4         | 0.21%   |
| KDC                     | 4         | 0.21%   |
| Unknown                 | 4         | 0.21%   |
| TMX                     | 3         | 0.16%   |
| Iiyama                  | 3         | 0.16%   |
| VIE                     | 2         | 0.1%    |
| SANYO                   | 2         | 0.1%    |
| Quanta Display          | 2         | 0.1%    |
| MSI                     | 2         | 0.1%    |
| JDI                     | 2         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 20        | 1.04%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 16        | 0.83%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 14        | 0.73%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 14        | 0.73%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 13        | 0.67%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 13        | 0.67%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 13        | 0.67%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 11        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 11        | 0.57%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 11        | 0.57%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.47%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 9         | 0.47%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.47%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 9         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 8         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 8         | 0.41%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 8         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 7         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 7         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 7         | 0.36%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 7         | 0.36%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 7         | 0.36%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 6         | 0.31%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch                 | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 6         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 6         | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 6         | 0.31%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch            | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 6         | 0.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch            | 6         | 0.31%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 5         | 0.26%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.26%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 5         | 0.26%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 5         | 0.26%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 5         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 5         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 774       | 41.75%  |
| 1920x1080 (FHD)    | 597       | 32.2%   |
| 1600x900 (HD+)     | 117       | 6.31%   |
| 1280x800 (WXGA)    | 98        | 5.29%   |
| 3840x2160 (4K)     | 43        | 2.32%   |
| 1440x900 (WXGA+)   | 42        | 2.27%   |
| 2560x1600          | 19        | 1.02%   |
| 2560x1440 (QHD)    | 19        | 1.02%   |
| 1920x1200 (WUXGA)  | 16        | 0.86%   |
| 1680x1050 (WSXGA+) | 13        | 0.7%    |
| 1280x1024 (SXGA)   | 11        | 0.59%   |
| 2880x1800          | 10        | 0.54%   |
| 2560x1080          | 9         | 0.49%   |
| 2160x1440          | 9         | 0.49%   |
| 3200x1800 (QHD+)   | 8         | 0.43%   |
| 2256x1504          | 8         | 0.43%   |
| 1360x768           | 8         | 0.43%   |
| Unknown            | 7         | 0.38%   |
| 3840x2400          | 5         | 0.27%   |
| 3440x1440          | 5         | 0.27%   |
| 1920x540           | 5         | 0.27%   |
| 1024x600           | 4         | 0.22%   |
| 3840x1080          | 3         | 0.16%   |
| 1920x515           | 3         | 0.16%   |
| 5760x1080          | 2         | 0.11%   |
| 2880x1920          | 2         | 0.11%   |
| 2304x1440          | 2         | 0.11%   |
| 1280x720 (HD)      | 2         | 0.11%   |
| 4480x1600          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |
| 3600x1080          | 1         | 0.05%   |
| 3072x1920          | 1         | 0.05%   |
| 3000x2000          | 1         | 0.05%   |
| 2880x1620          | 1         | 0.05%   |
| 2288x1287          | 1         | 0.05%   |
| 2240x1400          | 1         | 0.05%   |
| 1920x1280          | 1         | 0.05%   |
| 1680x945           | 1         | 0.05%   |
| 1600x2560          | 1         | 0.05%   |
| 1600x1200          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 817       | 42.82%  |
| 13      | 284       | 14.88%  |
| 14      | 223       | 11.69%  |
| 17      | 155       | 8.12%   |
| 11      | 81        | 4.25%   |
| 12      | 58        | 3.04%   |
| Unknown | 37        | 1.94%   |
| 27      | 36        | 1.89%   |
| 24      | 32        | 1.68%   |
| 23      | 23        | 1.21%   |
| 18      | 22        | 1.15%   |
| 16      | 18        | 0.94%   |
| 34      | 16        | 0.84%   |
| 21      | 16        | 0.84%   |
| 31      | 13        | 0.68%   |
| 19      | 10        | 0.52%   |
| 10      | 9         | 0.47%   |
| 22      | 6         | 0.31%   |
| 20      | 6         | 0.31%   |
| 54      | 5         | 0.26%   |
| 40      | 5         | 0.26%   |
| 26      | 4         | 0.21%   |
| 84      | 3         | 0.16%   |
| 72      | 3         | 0.16%   |
| 32      | 3         | 0.16%   |
| 25      | 3         | 0.16%   |
| 52      | 2         | 0.1%    |
| 49      | 2         | 0.1%    |
| 47      | 2         | 0.1%    |
| 37      | 2         | 0.1%    |
| 8       | 2         | 0.1%    |
| 74      | 1         | 0.05%   |
| 65      | 1         | 0.05%   |
| 64      | 1         | 0.05%   |
| 58      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 46      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |
| 39      | 1         | 0.05%   |
| 36      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1178      | 61.97%  |
| 201-300     | 279       | 14.68%  |
| 351-400     | 187       | 9.84%   |
| 501-600     | 89        | 4.68%   |
| 401-500     | 58        | 3.05%   |
| Unknown     | 37        | 1.95%   |
| 701-800     | 20        | 1.05%   |
| 601-700     | 19        | 1%      |
| 1001-1500   | 16        | 0.84%   |
| 801-900     | 8         | 0.42%   |
| 1501-2000   | 7         | 0.37%   |
| 101-200     | 2         | 0.11%   |
| 901-1000    | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1476      | 83.86%  |
| 16/10   | 198       | 11.25%  |
| Unknown | 26        | 1.48%   |
| 3/2     | 24        | 1.36%   |
| 21/9    | 15        | 0.85%   |
| 5/4     | 9         | 0.51%   |
| 4/3     | 5         | 0.28%   |
| 3.73    | 3         | 0.17%   |
| 32/9    | 2         | 0.11%   |
| 0.62    | 2         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 816       | 42.79%  |
| 81-90          | 420       | 22.02%  |
| 121-130        | 128       | 6.71%   |
| 71-80          | 87        | 4.56%   |
| 51-60          | 81        | 4.25%   |
| 201-250        | 68        | 3.57%   |
| 61-70          | 56        | 2.94%   |
| 301-350        | 39        | 2.05%   |
| Unknown        | 37        | 1.94%   |
| 351-500        | 32        | 1.68%   |
| 141-150        | 26        | 1.36%   |
| 151-200        | 24        | 1.26%   |
| More than 1000 | 20        | 1.05%   |
| 131-140        | 20        | 1.05%   |
| 111-120        | 15        | 0.79%   |
| 501-1000       | 14        | 0.73%   |
| 41-50          | 9         | 0.47%   |
| 91-100         | 7         | 0.37%   |
| 251-300        | 6         | 0.31%   |
| 1-40           | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 776       | 41.23%  |
| 121-160       | 632       | 33.58%  |
| 51-100        | 264       | 14.03%  |
| 161-240       | 109       | 5.79%   |
| Unknown       | 37        | 1.97%   |
| More than 240 | 36        | 1.91%   |
| 1-50          | 28        | 1.49%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1593      | 86.53%  |
| 2     | 210       | 11.41%  |
| 0     | 22        | 1.2%    |
| 3     | 13        | 0.71%   |
| 4     | 2         | 0.11%   |
| 5     | 1         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 911       | 32.09%  |
| Intel                             | 807       | 28.43%  |
| Qualcomm Atheros                  | 459       | 16.17%  |
| Broadcom                          | 253       | 8.91%   |
| Broadcom Limited                  | 79        | 2.78%   |
| Ralink                            | 36        | 1.27%   |
| Marvell Technology Group          | 35        | 1.23%   |
| MediaTek                          | 26        | 0.92%   |
| TP-Link                           | 20        | 0.7%    |
| Dell                              | 20        | 0.7%    |
| ASIX Electronics                  | 18        | 0.63%   |
| Samsung Electronics               | 15        | 0.53%   |
| Nvidia                            | 15        | 0.53%   |
| Ralink Technology                 | 13        | 0.46%   |
| Hewlett-Packard                   | 11        | 0.39%   |
| JMicron Technology                | 10        | 0.35%   |
| DisplayLink                       | 10        | 0.35%   |
| Xiaomi                            | 9         | 0.32%   |
| Sierra Wireless                   | 8         | 0.28%   |
| Huawei Technologies               | 7         | 0.25%   |
| Qualcomm                          | 6         | 0.21%   |
| NetGear                           | 6         | 0.21%   |
| OPPO Electronics                  | 5         | 0.18%   |
| Ericsson Business Mobile Networks | 5         | 0.18%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.14%   |
| Edimax Technology                 | 4         | 0.14%   |
| Silicon Integrated Systems [SiS]  | 3         | 0.11%   |
| Qualcomm Atheros Communications   | 3         | 0.11%   |
| Google                            | 3         | 0.11%   |
| D-Link System                     | 3         | 0.11%   |
| ASUSTek Computer                  | 3         | 0.11%   |
| VIA Technologies                  | 2         | 0.07%   |
| T & A Mobile Phones               | 2         | 0.07%   |
| Motorola PCS                      | 2         | 0.07%   |
| Linksys                           | 2         | 0.07%   |
| Lenovo                            | 2         | 0.07%   |
| ZyXEL Communications              | 1         | 0.04%   |
| ZyDAS                             | 1         | 0.04%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.04%   |
| U-Blox                            | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 494       | 14.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 220       | 6.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 96        | 2.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 80        | 2.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 72        | 2.14%   |
| Intel Wireless 7260                                               | 72        | 2.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 68        | 2.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 65        | 1.93%   |
| Intel Wireless 7265                                               | 62        | 1.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 53        | 1.58%   |
| Intel Wireless 8265 / 8275                                        | 49        | 1.46%   |
| Broadcom BCM43142 802.11b/g/n                                     | 49        | 1.46%   |
| Intel Wi-Fi 6 AX201                                               | 47        | 1.4%    |
| Intel Wi-Fi 6 AX200                                               | 45        | 1.34%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 44        | 1.31%   |
| Intel Wireless 8260                                               | 43        | 1.28%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 42        | 1.25%   |
| Intel Wireless 3165                                               | 36        | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 35        | 1.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 34        | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 31        | 0.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 28        | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 26        | 0.77%   |
| Intel WiFi Link 5100                                              | 26        | 0.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25        | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 25        | 0.74%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.68%   |
| Intel Centrino Ultimate-N 6300                                    | 23        | 0.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 22        | 0.65%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 0.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.62%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 20        | 0.59%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 20        | 0.59%   |
| Intel Wireless 3160                                               | 19        | 0.56%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 18        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.54%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 17        | 0.51%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                         | 17        | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 775       | 41.98%  |
| Qualcomm Atheros                | 387       | 20.96%  |
| Realtek Semiconductor           | 299       | 16.2%   |
| Broadcom                        | 202       | 10.94%  |
| Broadcom Limited                | 51        | 2.76%   |
| Ralink                          | 36        | 1.95%   |
| MediaTek                        | 23        | 1.25%   |
| TP-Link                         | 13        | 0.7%    |
| Ralink Technology               | 13        | 0.7%    |
| Dell                            | 9         | 0.49%   |
| Sierra Wireless                 | 8         | 0.43%   |
| NetGear                         | 6         | 0.33%   |
| Edimax Technology               | 4         | 0.22%   |
| Qualcomm Atheros Communications | 3         | 0.16%   |
| D-Link System                   | 3         | 0.16%   |
| Linksys                         | 2         | 0.11%   |
| ASUSTek Computer                | 2         | 0.11%   |
| ZyXEL Communications            | 1         | 0.05%   |
| ZyDAS                           | 1         | 0.05%   |
| TRENDnet                        | 1         | 0.05%   |
| Qualcomm                        | 1         | 0.05%   |
| Mercucys                        | 1         | 0.05%   |
| Hewlett-Packard                 | 1         | 0.05%   |
| Fibocom                         | 1         | 0.05%   |
| D-Link                          | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |
| Askey Computer                  | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 96        | 5.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 72        | 3.86%   |
| Intel Wireless 7260                                            | 72        | 3.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 68        | 3.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 65        | 3.49%   |
| Intel Wireless 7265                                            | 62        | 3.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 53        | 2.84%   |
| Intel Wireless 8265 / 8275                                     | 49        | 2.63%   |
| Broadcom BCM43142 802.11b/g/n                                  | 49        | 2.63%   |
| Intel Wi-Fi 6 AX201                                            | 47        | 2.52%   |
| Intel Wi-Fi 6 AX200                                            | 45        | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 44        | 2.36%   |
| Intel Wireless 8260                                            | 43        | 2.31%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 42        | 2.25%   |
| Intel Wireless 3165                                            | 36        | 1.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 35        | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 31        | 1.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 28        | 1.5%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 26        | 1.39%   |
| Intel WiFi Link 5100                                           | 26        | 1.39%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 25        | 1.34%   |
| Intel Centrino Ultimate-N 6300                                 | 23        | 1.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23        | 1.23%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 22        | 1.18%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 20        | 1.07%   |
| Intel Wireless 3160                                            | 19        | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 18        | 0.97%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 17        | 0.91%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 17        | 0.91%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 16        | 0.86%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 16        | 0.86%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16        | 0.86%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 16        | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 16        | 0.86%   |
| Intel Centrino Advanced-N 6235                                 | 16        | 0.86%   |
| Intel Centrino Advanced-N 6200                                 | 16        | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 15        | 0.8%    |
| Realtek 802.11n WLAN Adapter                                   | 15        | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 15        | 0.8%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 15        | 0.8%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 771       | 53.1%   |
| Intel                            | 291       | 20.04%  |
| Qualcomm Atheros                 | 117       | 8.06%   |
| Broadcom                         | 84        | 5.79%   |
| Marvell Technology Group         | 35        | 2.41%   |
| Broadcom Limited                 | 30        | 2.07%   |
| ASIX Electronics                 | 18        | 1.24%   |
| Nvidia                           | 15        | 1.03%   |
| Samsung Electronics              | 10        | 0.69%   |
| JMicron Technology               | 10        | 0.69%   |
| DisplayLink                      | 10        | 0.69%   |
| Xiaomi                           | 9         | 0.62%   |
| TP-Link                          | 7         | 0.48%   |
| Qualcomm                         | 5         | 0.34%   |
| OPPO Electronics                 | 5         | 0.34%   |
| Huawei Technologies              | 5         | 0.34%   |
| Silicon Integrated Systems [SiS] | 3         | 0.21%   |
| MediaTek                         | 3         | 0.21%   |
| Hewlett-Packard                  | 3         | 0.21%   |
| Google                           | 3         | 0.21%   |
| VIA Technologies                 | 2         | 0.14%   |
| OnePlus Technology (Shenzhen)    | 2         | 0.14%   |
| Lenovo                           | 2         | 0.14%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.07%   |
| Tenda                            | 1         | 0.07%   |
| T & A Mobile Phones              | 1         | 0.07%   |
| Novatel Wireless                 | 1         | 0.07%   |
| Motorola PCS                     | 1         | 0.07%   |
| Motorola BCS                     | 1         | 0.07%   |
| LG Electronics                   | 1         | 0.07%   |
| ICS Advent                       | 1         | 0.07%   |
| HTC (High Tech Computer)         | 1         | 0.07%   |
| HMD Global                       | 1         | 0.07%   |
| GoPro                            | 1         | 0.07%   |
| ASUSTek Computer                 | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 494       | 33.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 220       | 15.08%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 80        | 5.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 34        | 2.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25        | 1.71%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 1.58%   |
| Intel Ethernet Connection I217-LM                                 | 22        | 1.51%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 1.44%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 1.37%   |
| Intel 82577LM Gigabit Network Connection                          | 20        | 1.37%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 1.23%   |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 1.1%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 15        | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 15        | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 14        | 0.96%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 13        | 0.89%   |
| Intel Ethernet Connection I219-V                                  | 13        | 0.89%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 12        | 0.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 11        | 0.75%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 11        | 0.75%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 10        | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.69%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 10        | 0.69%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 10        | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.62%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.62%   |
| Intel 82566MM Gigabit Network Connection                          | 9         | 0.62%   |
| Nvidia MCP79 Ethernet                                             | 8         | 0.55%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 8         | 0.55%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 7         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.41%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 6         | 0.41%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 6         | 0.41%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 6         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.34%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 5         | 0.34%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 5         | 0.34%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 5         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1747      | 54.95%  |
| Ethernet | 1393      | 43.82%  |
| Modem    | 33        | 1.04%   |
| Unknown  | 6         | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1491      | 79.86%  |
| Ethernet | 375       | 20.09%  |
| Unknown  | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1283      | 70.73%  |
| 1     | 438       | 24.15%  |
| 0     | 85        | 4.69%   |
| 3     | 8         | 0.44%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1272      | 69.09%  |
| Yes  | 569       | 30.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 549       | 41.69%  |
| Qualcomm Atheros Communications | 156       | 11.85%  |
| Realtek Semiconductor           | 151       | 11.47%  |
| Broadcom                        | 88        | 6.68%   |
| IMC Networks                    | 68        | 5.16%   |
| Apple                           | 52        | 3.95%   |
| Foxconn / Hon Hai               | 47        | 3.57%   |
| Lite-On Technology              | 45        | 3.42%   |
| Dell                            | 33        | 2.51%   |
| Hewlett-Packard                 | 31        | 2.35%   |
| Toshiba                         | 24        | 1.82%   |
| Cambridge Silicon Radio         | 20        | 1.52%   |
| Ralink                          | 16        | 1.21%   |
| ASUSTek Computer                | 10        | 0.76%   |
| Realtek                         | 6         | 0.46%   |
| Foxconn International           | 6         | 0.46%   |
| Alps Electric                   | 5         | 0.38%   |
| Integrated System Solution      | 2         | 0.15%   |
| Askey Computer                  | 2         | 0.15%   |
| Ralink Technology               | 1         | 0.08%   |
| Qcom                            | 1         | 0.08%   |
| MediaTek                        | 1         | 0.08%   |
| Chicony Electronics             | 1         | 0.08%   |
| Belkin Components               | 1         | 0.08%   |
| Unknown                         | 1         | 0.08%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 268       | 20.32%  |
| Realtek Bluetooth Radio                             | 97        | 7.35%   |
| Intel AX201 Bluetooth                               | 82        | 6.22%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 78        | 5.91%   |
| Qualcomm Atheros  Bluetooth Device                  | 68        | 5.16%   |
| Intel AX200 Bluetooth                               | 43        | 3.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 39        | 2.96%   |
| Apple Bluetooth Host Controller                     | 33        | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 27        | 2.05%   |
| IMC Networks Bluetooth Device                       | 25        | 1.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 23        | 1.74%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 21        | 1.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 20        | 1.52%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 20        | 1.52%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 18        | 1.36%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 17        | 1.29%   |
| IMC Networks Bluetooth Radio                        | 17        | 1.29%   |
| Ralink RT3290 Bluetooth                             | 16        | 1.21%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 1.21%   |
| Lite-On Atheros AR3012 Bluetooth                    | 16        | 1.21%   |
| Intel AX210 Bluetooth                               | 16        | 1.21%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 1.14%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 14        | 1.06%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 13        | 0.99%   |
| IMC Networks Wireless_Device                        | 13        | 0.99%   |
| HP Broadcom 2070 Bluetooth Combo                    | 13        | 0.99%   |
| Dell DW375 Bluetooth Module                         | 13        | 0.99%   |
| Broadcom BCM2045B (BDC-2.1)                         | 12        | 0.91%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 0.76%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 9         | 0.68%   |
| Toshiba Bluetooth Device                            | 8         | 0.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 8         | 0.61%   |
| Apple Bluetooth USB Host Controller                 | 8         | 0.61%   |
| Realtek RTL8723B Bluetooth                          | 7         | 0.53%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 7         | 0.53%   |
| Dell BCM20702A0 Bluetooth Module                    | 7         | 0.53%   |
| Broadcom HP Portable SoftSailing                    | 7         | 0.53%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 7         | 0.53%   |
| Realtek 802.11ac WLAN Adapter                       | 6         | 0.45%   |
| Lite-On Bluetooth Device                            | 6         | 0.45%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1449      | 69.43%  |
| AMD                                  | 338       | 16.2%   |
| Nvidia                               | 236       | 11.31%  |
| Realtek Semiconductor                | 5         | 0.24%   |
| Generalplus Technology               | 5         | 0.24%   |
| Lenovo                               | 4         | 0.19%   |
| C-Media Electronics                  | 4         | 0.19%   |
| SteelSeries ApS                      | 3         | 0.14%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.14%   |
| Logitech                             | 3         | 0.14%   |
| JMTek                                | 3         | 0.14%   |
| VIA Technologies                     | 2         | 0.1%    |
| Tenx Technology                      | 2         | 0.1%    |
| PreSonus Audio Electronics           | 2         | 0.1%    |
| Plantronics                          | 2         | 0.1%    |
| FUXIN                                | 2         | 0.1%    |
| Focusrite-Novation                   | 2         | 0.1%    |
| Corsair                              | 2         | 0.1%    |
| XMOS                                 | 1         | 0.05%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.05%   |
| Texas Instruments                    | 1         | 0.05%   |
| Sony                                 | 1         | 0.05%   |
| Sennheiser Communications            | 1         | 0.05%   |
| SAVITECH                             | 1         | 0.05%   |
| Roland                               | 1         | 0.05%   |
| Razer USA                            | 1         | 0.05%   |
| Kingston Technology                  | 1         | 0.05%   |
| GN Netcom                            | 1         | 0.05%   |
| FiiO Electronics Technology          | 1         | 0.05%   |
| DSEA A/S                             | 1         | 0.05%   |
| Dell                                 | 1         | 0.05%   |
| Creative Technology                  | 1         | 0.05%   |
| Conexant Systems                     | 1         | 0.05%   |
| CMX Systems                          | 1         | 0.05%   |
| BEHRINGER International              | 1         | 0.05%   |
| ASUSTek Computer                     | 1         | 0.05%   |
| Antelope Audio                       | 1         | 0.05%   |
| Unknown                              | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 192       | 7.53%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 177       | 6.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 132       | 5.18%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 127       | 4.98%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 108       | 4.24%   |
| Intel 8 Series HD Audio Controller                                                                | 93        | 3.65%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 89        | 3.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 87        | 3.41%   |
| AMD FCH Azalia Controller                                                                         | 81        | 3.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 74        | 2.9%    |
| Intel Broadwell-U Audio Controller                                                                | 72        | 2.82%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 71        | 2.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 64        | 2.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 59        | 2.31%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 55        | 2.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 52        | 2.04%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 47        | 1.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 46        | 1.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 42        | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 41        | 1.61%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 40        | 1.57%   |
| Intel Cannon Lake PCH cAVS                                                                        | 38        | 1.49%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 34        | 1.33%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 34        | 1.33%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 33        | 1.29%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 33        | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 32        | 1.26%   |
| AMD High Definition Audio Controller                                                              | 30        | 1.18%   |
| Intel CM238 HD Audio Controller                                                                   | 29        | 1.14%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 28        | 1.1%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 27        | 1.06%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 27        | 1.06%   |
| Intel Comet Lake PCH cAVS                                                                         | 22        | 0.86%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 18        | 0.71%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 16        | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 15        | 0.59%   |
| Nvidia High Definition Audio Controller                                                           | 15        | 0.59%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 15        | 0.59%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 13        | 0.51%   |
| AMD Wrestler HDMI Audio                                                                           | 12        | 0.47%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 127       | 27.08%  |
| SK hynix               | 104       | 22.17%  |
| Micron Technology      | 63        | 13.43%  |
| Kingston               | 29        | 6.18%   |
| Unknown                | 28        | 5.97%   |
| Unknown (ABCD)         | 18        | 3.84%   |
| Crucial                | 17        | 3.62%   |
| Elpida                 | 11        | 2.35%   |
| A-DATA Technology      | 11        | 2.35%   |
| Ramaxel Technology     | 9         | 1.92%   |
| Smart                  | 5         | 1.07%   |
| Nanya Technology       | 4         | 0.85%   |
| Timetec                | 3         | 0.64%   |
| Unknown                | 3         | 0.64%   |
| Teikon                 | 2         | 0.43%   |
| Patriot                | 2         | 0.43%   |
| G.Skill                | 2         | 0.43%   |
| ff                     | 2         | 0.43%   |
| fef5                   | 2         | 0.43%   |
| Corsair                | 2         | 0.43%   |
| 4ea5                   | 2         | 0.43%   |
| Unknown (08B5)         | 1         | 0.21%   |
| Unknown (07F7)         | 1         | 0.21%   |
| Unknown (000080B30080) | 1         | 0.21%   |
| Transcend              | 1         | 0.21%   |
| Team                   | 1         | 0.21%   |
| Strontium              | 1         | 0.21%   |
| Smart Brazil           | 1         | 0.21%   |
| Silicon Power          | 1         | 0.21%   |
| SHARETRONIC            | 1         | 0.21%   |
| Qimonda                | 1         | 0.21%   |
| PUSKILL                | 1         | 0.21%   |
| ProMos/Mosel Vitelic   | 1         | 0.21%   |
| PNY                    | 1         | 0.21%   |
| Netlist                | 1         | 0.21%   |
| Kllisre                | 1         | 0.21%   |
| Kingmax                | 1         | 0.21%   |
| GSkill                 | 1         | 0.21%   |
| Essencore              | 1         | 0.21%   |
| CSX                    | 1         | 0.21%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 16        | 3.24%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 1.42%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 1.42%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 1.21%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 1.21%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.21%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.21%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 5         | 1.01%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.01%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.01%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.81%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.81%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.81%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.81%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 4         | 0.81%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.81%   |
| Samsung RAM M471A1G44BB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 0.81%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.81%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.81%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 3         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 3         | 0.61%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR 975MT/s             | 3         | 0.61%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 3         | 0.61%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.61%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.61%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.61%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.61%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.61%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.61%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.61%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.61%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.61%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.61%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.61%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s            | 3         | 0.61%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 0.61%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.61%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 3         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 162       | 41.01%  |
| DDR3    | 146       | 36.96%  |
| LPDDR4  | 36        | 9.11%   |
| DDR2    | 18        | 4.56%   |
| LPDDR3  | 17        | 4.3%    |
| SDRAM   | 9         | 2.28%   |
| Unknown | 3         | 0.76%   |
| LPDDR5  | 2         | 0.51%   |
| DDR5    | 2         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 337       | 85.32%  |
| Row Of Chips | 41        | 10.38%  |
| Unknown      | 7         | 1.77%   |
| DIMM         | 6         | 1.52%   |
| Chip         | 4         | 1.01%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 166       | 37.56%  |
| 4096  | 144       | 32.58%  |
| 2048  | 72        | 16.29%  |
| 16384 | 39        | 8.82%   |
| 1024  | 15        | 3.39%   |
| 32768 | 5         | 1.13%   |
| 512   | 1         | 0.23%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 97        | 22.56%  |
| 3200    | 73        | 16.98%  |
| 2667    | 69        | 16.05%  |
| 2400    | 48        | 11.16%  |
| 1334    | 25        | 5.81%   |
| 2133    | 16        | 3.72%   |
| 1333    | 14        | 3.26%   |
| 4267    | 11        | 2.56%   |
| 667     | 11        | 2.56%   |
| Unknown | 8         | 1.86%   |
| 3266    | 7         | 1.63%   |
| 2048    | 7         | 1.63%   |
| 1867    | 7         | 1.63%   |
| 1066    | 7         | 1.63%   |
| 800     | 6         | 1.4%    |
| 1067    | 4         | 0.93%   |
| 975     | 4         | 0.93%   |
| 8400    | 3         | 0.7%    |
| 6400    | 3         | 0.7%    |
| 4800    | 2         | 0.47%   |
| 4199    | 2         | 0.47%   |
| 4266    | 1         | 0.23%   |
| 3733    | 1         | 0.23%   |
| 2933    | 1         | 0.23%   |
| 1866    | 1         | 0.23%   |
| 666     | 1         | 0.23%   |
| 533     | 1         | 0.23%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 42.86%  |
| Seiko Epson           | 3         | 21.43%  |
| Canon                 | 2         | 14.29%  |
| Zebra                 | 1         | 7.14%   |
| Samsung Electronics   | 1         | 7.14%   |
| Lexmark International | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| HP ENVY Photo 6200 series         | 2         | 14.29%  |
| Zebra ZP 450 Printer              | 1         | 7.14%   |
| Seiko Epson L3250 Series          | 1         | 7.14%   |
| Seiko Epson L3110 Series          | 1         | 7.14%   |
| Seiko Epson AcuLaser C1700        | 1         | 7.14%   |
| Samsung M2020 Series              | 1         | 7.14%   |
| Lexmark International 2400 series | 1         | 7.14%   |
| HP LaserJet 1200                  | 1         | 7.14%   |
| HP LaserJet 1000                  | 1         | 7.14%   |
| HP DeskJet 2300 series            | 1         | 7.14%   |
| HP DeskJet 1110 series            | 1         | 7.14%   |
| Canon TS3100 series               | 1         | 7.14%   |
| Canon PIXMA MG3000 series         | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 50%     |
| Canon       | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 50%     |
| Canon CanoScan LiDE 90                      | 1         | 25%     |
| Canon CanoScan LIDE 25                      | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 369       | 23.62%  |
| Microdia                               | 147       | 9.41%   |
| Realtek Semiconductor                  | 143       | 9.15%   |
| IMC Networks                           | 131       | 8.39%   |
| Sunplus Innovation Technology          | 93        | 5.95%   |
| Cheng Uei Precision Industry (Foxlink) | 77        | 4.93%   |
| Bison Electronics                      | 75        | 4.8%    |
| Quanta                                 | 74        | 4.74%   |
| Suyin                                  | 63        | 4.03%   |
| Syntek                                 | 46        | 2.94%   |
| Apple                                  | 46        | 2.94%   |
| Acer                                   | 38        | 2.43%   |
| Silicon Motion                         | 31        | 1.98%   |
| Lite-On Technology                     | 28        | 1.79%   |
| Alcor Micro                            | 27        | 1.73%   |
| Luxvisions Innotech Limited            | 18        | 1.15%   |
| Ricoh                                  | 17        | 1.09%   |
| Logitech                               | 14        | 0.9%    |
| icSpring                               | 14        | 0.9%    |
| Primax Electronics                     | 12        | 0.77%   |
| Sonix Technology                       | 11        | 0.7%    |
| Samsung Electronics                    | 8         | 0.51%   |
| ALi                                    | 8         | 0.51%   |
| SunplusIT                              | 7         | 0.45%   |
| Lenovo                                 | 7         | 0.45%   |
| Z-Star Microelectronics                | 6         | 0.38%   |
| Importek                               | 5         | 0.32%   |
| GEMBIRD                                | 5         | 0.32%   |
| Y Media                                | 4         | 0.26%   |
| Sunplus Technology                     | 3         | 0.19%   |
| OmniVision Technologies                | 3         | 0.19%   |
| Genesys Logic                          | 3         | 0.19%   |
| ARC International                      | 3         | 0.19%   |
| Tripath Technology                     | 2         | 0.13%   |
| Intel                                  | 2         | 0.13%   |
| Generalplus Technology                 | 2         | 0.13%   |
| YGTek                                  | 1         | 0.06%   |
| Xiaomi                                 | 1         | 0.06%   |
| vivo                                   | 1         | 0.06%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 59        | 3.76%   |
| Microdia Integrated_Webcam_HD                       | 39        | 2.49%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 34        | 2.17%   |
| Chicony HD WebCam                                   | 29        | 1.85%   |
| Syntek Integrated Camera                            | 28        | 1.79%   |
| Microdia Integrated Webcam                          | 26        | 1.66%   |
| Chicony HP Truevision HD                            | 25        | 1.59%   |
| Realtek Integrated_Webcam_HD                        | 23        | 1.47%   |
| Realtek USB Camera                                  | 22        | 1.4%    |
| Chicony TOSHIBA Web Camera - HD                     | 21        | 1.34%   |
| IMC Networks Integrated Camera                      | 20        | 1.28%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 19        | 1.21%   |
| Sunplus HD WebCam                                   | 18        | 1.15%   |
| Sunplus Integrated_Webcam_HD                        | 16        | 1.02%   |
| Acer Integrated Camera                              | 16        | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 15        | 0.96%   |
| Bison Integrated Camera                             | 15        | 0.96%   |
| Realtek Integrated Webcam                           | 14        | 0.89%   |
| icSpring camera                                     | 14        | 0.89%   |
| Apple FaceTime HD Camera                            | 14        | 0.89%   |
| Realtek HP Truevision HD                            | 13        | 0.83%   |
| Lite-On HP HD Camera                                | 13        | 0.83%   |
| Chicony Lenovo EasyCamera                           | 13        | 0.83%   |
| Chicony HP TrueVision HD Camera                     | 13        | 0.83%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 13        | 0.83%   |
| Chicony HP HD Camera                                | 12        | 0.77%   |
| Alcor Micro USB 2.0 Camera                          | 12        | 0.77%   |
| Quanta HP Wide Vision HD Camera                     | 11        | 0.7%    |
| Chicony VGA WebCam                                  | 11        | 0.7%    |
| Acer Lenovo EasyCamera                              | 11        | 0.7%    |
| Realtek Lenovo EasyCamera                           | 10        | 0.64%   |
| Realtek Integrated Webcam HD                        | 10        | 0.64%   |
| Quanta HP TrueVision HD Camera                      | 10        | 0.64%   |
| Quanta HD User Facing                               | 10        | 0.64%   |
| Microdia Webcam Vitade AF                           | 10        | 0.64%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 10        | 0.64%   |
| Chicony USB2.0 VGA UVC WebCam                       | 10        | 0.64%   |
| Chicony HP HD Webcam                                | 10        | 0.64%   |
| Chicony EasyCamera                                  | 10        | 0.64%   |
| Bison Lenovo EasyCamera                             | 10        | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 117       | 45.35%  |
| Shenzhen Goodix Technology         | 33        | 12.79%  |
| AuthenTec                          | 29        | 11.24%  |
| Synaptics                          | 28        | 10.85%  |
| Upek                               | 21        | 8.14%   |
| Elan Microelectronics              | 14        | 5.43%   |
| STMicroelectronics                 | 6         | 2.33%   |
| LighTuning Technology              | 6         | 2.33%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.78%   |
| Samsung Electronics                | 1         | 0.39%   |
| Focal-systems.Corp                 | 1         | 0.39%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 9.3%    |
| Shenzhen Goodix  FingerPrint Device                                        | 24        | 9.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 20        | 7.75%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 5.81%   |
| Validity Sensors VFS491                                                    | 14        | 5.43%   |
| Validity Sensors Fingerprint scanner                                       | 11        | 4.26%   |
| AuthenTec AES2810                                                          | 11        | 4.26%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 3.88%   |
| Elan ELAN:ARM-M4                                                           | 10        | 3.88%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 3.49%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 7         | 2.71%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 2.71%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 2.71%   |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 2.71%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 6         | 2.33%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 2.33%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 2.33%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.94%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 5         | 1.94%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 1.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.55%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.55%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.55%   |
| AuthenTec AES1600                                                          | 4         | 1.55%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 3         | 1.16%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.16%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 1.16%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.78%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.78%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 0.78%   |
| Synaptics WBDI                                                             | 2         | 0.78%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.78%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 0.78%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.78%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.39%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.39%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.39%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.39%   |
| Synaptics  WBDI                                                            | 1         | 0.39%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.39%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 67        | 58.26%  |
| Alcor Micro                       | 18        | 15.65%  |
| O2 Micro                          | 12        | 10.43%  |
| Lenovo                            | 6         | 5.22%   |
| Upek                              | 5         | 4.35%   |
| Yubico.com                        | 2         | 1.74%   |
| VASCO Data Security International | 1         | 0.87%   |
| SCM Microsystems                  | 1         | 0.87%   |
| Realtek Semiconductor             | 1         | 0.87%   |
| OmniKey                           | 1         | 0.87%   |
| Fujitsu Siemens Computers         | 1         | 0.87%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 29        | 25.22%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 15.65%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 17        | 14.78%  |
| Broadcom 5880                                                                | 16        | 13.91%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 9.57%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 5.22%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 4.35%   |
| Broadcom 58200                                                               | 3         | 2.61%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.74%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.74%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.87%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.87%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.87%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.87%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.87%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.87%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1232      | 66.92%  |
| 1     | 477       | 25.91%  |
| 2     | 122       | 6.63%   |
| 3     | 10        | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 252       | 34.71%  |
| Graphics card            | 120       | 16.53%  |
| Chipcard                 | 108       | 14.88%  |
| Multimedia controller    | 84        | 11.57%  |
| Net/wireless             | 76        | 10.47%  |
| Storage                  | 24        | 3.31%   |
| Bluetooth                | 20        | 2.75%   |
| Sound                    | 6         | 0.83%   |
| Communication controller | 6         | 0.83%   |
| Camera                   | 6         | 0.83%   |
| Net/ethernet             | 5         | 0.69%   |
| Card reader              | 4         | 0.55%   |
| Network                  | 3         | 0.41%   |
| Modem                    | 3         | 0.41%   |
| Storage/nvme             | 2         | 0.28%   |
| Storage/ide              | 2         | 0.28%   |
| Flash memory             | 2         | 0.28%   |
| Dvb card                 | 2         | 0.28%   |
| Unclassified device      | 1         | 0.14%   |

