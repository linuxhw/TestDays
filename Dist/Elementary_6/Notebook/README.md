Elementary 6 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Elementary 6.

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

Total: 170

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| LG Electro... | P1-JSUVT                    | [b0e2f9e53c](https://linux-hardware.org/?probe=b0e2f9e53c) | Mar 27, 2022 |
| Dell          | XPS 15 9500                 | [ac78806c22](https://linux-hardware.org/?probe=ac78806c22) | Jan 30, 2022 |
| Dell          | XPS 15 9500                 | [657fbc0f6d](https://linux-hardware.org/?probe=657fbc0f6d) | Jan 30, 2022 |
| ASUSTek       | GL502VS                     | [feb64c0933](https://linux-hardware.org/?probe=feb64c0933) | Jan 12, 2022 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [7ba01d7327](https://linux-hardware.org/?probe=7ba01d7327) | Jan 07, 2022 |
| Dell          | Inspiron N5110              | [172b005a76](https://linux-hardware.org/?probe=172b005a76) | Jan 07, 2022 |
| Dell          | Inspiron N5110              | [a0a13869ab](https://linux-hardware.org/?probe=a0a13869ab) | Jan 05, 2022 |
| Acer          | Aspire XXXX                 | [d52d9dc2bd](https://linux-hardware.org/?probe=d52d9dc2bd) | Jan 04, 2022 |
| Acer          | Aspire XXXX                 | [b5d8962bbc](https://linux-hardware.org/?probe=b5d8962bbc) | Jan 04, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [5627f53d66](https://linux-hardware.org/?probe=5627f53d66) | Dec 17, 2021 |
| Dell          | Inspiron 1764               | [a8abf45979](https://linux-hardware.org/?probe=a8abf45979) | Dec 13, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [8280287583](https://linux-hardware.org/?probe=8280287583) | Dec 12, 2021 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [6f114c2528](https://linux-hardware.org/?probe=6f114c2528) | Dec 12, 2021 |
| Dell          | XPS 15 9510                 | [da1818e0c5](https://linux-hardware.org/?probe=da1818e0c5) | Dec 12, 2021 |
| Dell          | XPS 15 9570                 | [40b1d83a44](https://linux-hardware.org/?probe=40b1d83a44) | Dec 11, 2021 |
| Star Labs     | StarBook                    | [e9414e6bc4](https://linux-hardware.org/?probe=e9414e6bc4) | Dec 09, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [31e281d91b](https://linux-hardware.org/?probe=31e281d91b) | Dec 09, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [d6be9fac19](https://linux-hardware.org/?probe=d6be9fac19) | Dec 09, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [d32c954439](https://linux-hardware.org/?probe=d32c954439) | Dec 09, 2021 |
| Google        | Cyan                        | [f49c895086](https://linux-hardware.org/?probe=f49c895086) | Dec 08, 2021 |
| Dell          | Latitude E5420              | [e9fdf365b6](https://linux-hardware.org/?probe=e9fdf365b6) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [ed493cd76f](https://linux-hardware.org/?probe=ed493cd76f) | Dec 05, 2021 |
| HUAWEI        | MACHD-WXX9                  | [970669192e](https://linux-hardware.org/?probe=970669192e) | Dec 05, 2021 |
| HP            | G62                         | [6e055d5b6b](https://linux-hardware.org/?probe=6e055d5b6b) | Dec 05, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9143857ca7](https://linux-hardware.org/?probe=9143857ca7) | Dec 05, 2021 |
| ASUSTek       | FX503VD                     | [6b5bd7a6d3](https://linux-hardware.org/?probe=6b5bd7a6d3) | Dec 05, 2021 |
| Packard Be... | EasyNote LS11HR             | [d58c199fda](https://linux-hardware.org/?probe=d58c199fda) | Dec 04, 2021 |
| HP            | ZBook 15 G5                 | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| Lenovo        | ThinkPad T410s 292494G      | [f43363fde0](https://linux-hardware.org/?probe=f43363fde0) | Dec 03, 2021 |
| HP            | EliteBook 820 G2            | [03bb5ecc6a](https://linux-hardware.org/?probe=03bb5ecc6a) | Dec 03, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [68fffd46cf](https://linux-hardware.org/?probe=68fffd46cf) | Dec 01, 2021 |
| Acer          | Aspire 5750G                | [0131556200](https://linux-hardware.org/?probe=0131556200) | Dec 01, 2021 |
| Samsung       | 550XDA                      | [30c24b17f4](https://linux-hardware.org/?probe=30c24b17f4) | Dec 01, 2021 |
| HP            | EliteBook 2760p             | [d13f27ae75](https://linux-hardware.org/?probe=d13f27ae75) | Nov 30, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [5052f33272](https://linux-hardware.org/?probe=5052f33272) | Nov 30, 2021 |
| Google        | Kip                         | [958c198a17](https://linux-hardware.org/?probe=958c198a17) | Nov 29, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [26cba9b931](https://linux-hardware.org/?probe=26cba9b931) | Nov 29, 2021 |
| Toshiba       | Satellite L750              | [0a4f8ff5f1](https://linux-hardware.org/?probe=0a4f8ff5f1) | Nov 28, 2021 |
| HP            | Laptop 15s-fq0xxx           | [8b1d090289](https://linux-hardware.org/?probe=8b1d090289) | Nov 28, 2021 |
| HP            | Pavilion dm4                | [e2c582f687](https://linux-hardware.org/?probe=e2c582f687) | Nov 28, 2021 |
| HP            | ProBook 4540s               | [b6762448da](https://linux-hardware.org/?probe=b6762448da) | Nov 28, 2021 |
| Notebook      | L140CU                      | [59021b2a31](https://linux-hardware.org/?probe=59021b2a31) | Nov 27, 2021 |
| Toshiba       | Satellite L840              | [6c29b0fc8d](https://linux-hardware.org/?probe=6c29b0fc8d) | Nov 27, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [c8a72fc7e2](https://linux-hardware.org/?probe=c8a72fc7e2) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | [0004bab911](https://linux-hardware.org/?probe=0004bab911) | Nov 26, 2021 |
| HP            | EliteBook Folio 1040 G3     | [2ef4f4f273](https://linux-hardware.org/?probe=2ef4f4f273) | Nov 26, 2021 |
| Dell          | Inspiron 15-3573            | [04dc1956ff](https://linux-hardware.org/?probe=04dc1956ff) | Nov 26, 2021 |
| Lenovo        | ThinkPad SL400 2743A37      | [cd408c48d0](https://linux-hardware.org/?probe=cd408c48d0) | Nov 25, 2021 |
| Lenovo        | ThinkPad X140e 20BLS0040... | [94b3c73b50](https://linux-hardware.org/?probe=94b3c73b50) | Nov 25, 2021 |
| Apple         | MacBookPro11,2              | [07931c8e7b](https://linux-hardware.org/?probe=07931c8e7b) | Nov 24, 2021 |
| Dell          | System Inspiron N7110       | [fe6a145b19](https://linux-hardware.org/?probe=fe6a145b19) | Nov 24, 2021 |
| Medion        | E7218                       | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [1bfd5fb612](https://linux-hardware.org/?probe=1bfd5fb612) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| Apple         | MacBookPro12,1              | [4f694a8ba3](https://linux-hardware.org/?probe=4f694a8ba3) | Nov 23, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [945f4c9b1d](https://linux-hardware.org/?probe=945f4c9b1d) | Nov 22, 2021 |
| MSI           | GF72 7RE                    | [8e48a382b9](https://linux-hardware.org/?probe=8e48a382b9) | Nov 21, 2021 |
| Alienware     | 17                          | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Dell          | Vostro 3300                 | [04fc886be3](https://linux-hardware.org/?probe=04fc886be3) | Nov 20, 2021 |
| HP            | ProBook 4730s               | [ffaa64e329](https://linux-hardware.org/?probe=ffaa64e329) | Nov 19, 2021 |
| Schenker      | X170KM-G                    | [79bb8af2a1](https://linux-hardware.org/?probe=79bb8af2a1) | Nov 19, 2021 |
| HP            | Laptop 15-dy2xxx            | [e49d63158f](https://linux-hardware.org/?probe=e49d63158f) | Nov 19, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [38d8d7827f](https://linux-hardware.org/?probe=38d8d7827f) | Nov 18, 2021 |
| HP            | Compaq 6710b (GB893EA#AB... | [47a6a7a44f](https://linux-hardware.org/?probe=47a6a7a44f) | Nov 17, 2021 |
| Unknown       | Unknown                     | [7027abd4e6](https://linux-hardware.org/?probe=7027abd4e6) | Nov 17, 2021 |
| Acer          | Aspire 5733Z                | [324f0d898e](https://linux-hardware.org/?probe=324f0d898e) | Nov 16, 2021 |
| Acer          | Aspire ES1-571              | [60fef7922d](https://linux-hardware.org/?probe=60fef7922d) | Nov 16, 2021 |
| Dell          | XPS 15 9570                 | [74e99a032e](https://linux-hardware.org/?probe=74e99a032e) | Nov 15, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [58edd5c8e6](https://linux-hardware.org/?probe=58edd5c8e6) | Nov 14, 2021 |
| Lenovo        | ThinkPad T460s 20F90042M... | [76ba8c7144](https://linux-hardware.org/?probe=76ba8c7144) | Nov 13, 2021 |
| Sony          | SVE15115EN                  | [03cbf5ac5a](https://linux-hardware.org/?probe=03cbf5ac5a) | Nov 11, 2021 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [e43a236a2c](https://linux-hardware.org/?probe=e43a236a2c) | Nov 06, 2021 |
| Quanta        | TW9/SW9                     | [86643edf2a](https://linux-hardware.org/?probe=86643edf2a) | Nov 06, 2021 |
| ASUSTek       | E502SA                      | [28d4f5e427](https://linux-hardware.org/?probe=28d4f5e427) | Nov 04, 2021 |
| HCL Infosy... | HCL ME LAPTOP               | [0db069b4f1](https://linux-hardware.org/?probe=0db069b4f1) | Nov 01, 2021 |
| Fujitsu       | LIFEBOOK U747               | [2b68c16c68](https://linux-hardware.org/?probe=2b68c16c68) | Nov 01, 2021 |
| Dell          | Latitude E6410              | [ba51fc9216](https://linux-hardware.org/?probe=ba51fc9216) | Oct 30, 2021 |
| Lenovo        | ThinkPad X230 23259L3       | [801c1d8af3](https://linux-hardware.org/?probe=801c1d8af3) | Oct 27, 2021 |
| MSI           | Modern 14 B4MW              | [a904daf48d](https://linux-hardware.org/?probe=a904daf48d) | Oct 26, 2021 |
| HP            | ProBook 6460b               | [18f27d1f5c](https://linux-hardware.org/?probe=18f27d1f5c) | Oct 25, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5c95c74b6c](https://linux-hardware.org/?probe=5c95c74b6c) | Oct 21, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f48a449c7a](https://linux-hardware.org/?probe=f48a449c7a) | Oct 21, 2021 |
| Apple         | MacBookAir7,2               | [4ce4f8ba78](https://linux-hardware.org/?probe=4ce4f8ba78) | Oct 20, 2021 |
| Google        | Setzer                      | [e9536ccbfb](https://linux-hardware.org/?probe=e9536ccbfb) | Oct 19, 2021 |
| Google        | Setzer                      | [3ba49636ef](https://linux-hardware.org/?probe=3ba49636ef) | Oct 19, 2021 |
| Apple         | MacBookAir7,2               | [370b129f3f](https://linux-hardware.org/?probe=370b129f3f) | Oct 16, 2021 |
| Lenovo        | ThinkPad E470 20H10052IG    | [1342d4ce00](https://linux-hardware.org/?probe=1342d4ce00) | Oct 15, 2021 |
| HP            | Pavilion dv6500             | [dd3c7ef3e7](https://linux-hardware.org/?probe=dd3c7ef3e7) | Oct 14, 2021 |
| HP            | Pavilion dv6500             | [c1c77cf91a](https://linux-hardware.org/?probe=c1c77cf91a) | Oct 14, 2021 |
| Acer          | Aspire ES1-311              | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [66f91918dc](https://linux-hardware.org/?probe=66f91918dc) | Oct 12, 2021 |
| Apple         | MacBookAir6,1               | [87403edfc9](https://linux-hardware.org/?probe=87403edfc9) | Oct 11, 2021 |
| ASUSTek       | 1215B                       | [7b3bf2ca14](https://linux-hardware.org/?probe=7b3bf2ca14) | Oct 11, 2021 |
| HP            | EliteBook 8440p             | [e5071e6c43](https://linux-hardware.org/?probe=e5071e6c43) | Oct 10, 2021 |
| HP            | ProBook 4530s               | [0a725a0b81](https://linux-hardware.org/?probe=0a725a0b81) | Oct 07, 2021 |
| Apple         | MacBookPro7,1               | [644b3b5b60](https://linux-hardware.org/?probe=644b3b5b60) | Oct 04, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [32c58fa2f6](https://linux-hardware.org/?probe=32c58fa2f6) | Sep 30, 2021 |
| Dell          | XPS 13 9350                 | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c28700cfda](https://linux-hardware.org/?probe=c28700cfda) | Sep 26, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [fbcf277174](https://linux-hardware.org/?probe=fbcf277174) | Sep 26, 2021 |
| Lenovo        | G50-45 80E3                 | [59224ec754](https://linux-hardware.org/?probe=59224ec754) | Sep 26, 2021 |
| Apple         | MacBookPro10,2              | [25c8a26c00](https://linux-hardware.org/?probe=25c8a26c00) | Sep 24, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [c1b8f22fa6](https://linux-hardware.org/?probe=c1b8f22fa6) | Sep 22, 2021 |
| Dell          | Precision M4800             | [736b482dc3](https://linux-hardware.org/?probe=736b482dc3) | Sep 22, 2021 |
| eMachines     | G525                        | [8e8d037369](https://linux-hardware.org/?probe=8e8d037369) | Sep 21, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [9d25d0c5c7](https://linux-hardware.org/?probe=9d25d0c5c7) | Sep 21, 2021 |
| Lenovo        | ThinkPad W700 2758MVG       | [66c8ecbaa1](https://linux-hardware.org/?probe=66c8ecbaa1) | Sep 20, 2021 |
| Dell          | XPS 13 9350                 | [b01438543e](https://linux-hardware.org/?probe=b01438543e) | Sep 20, 2021 |
| Apple         | MacBookPro10,2              | [0e44f5011a](https://linux-hardware.org/?probe=0e44f5011a) | Sep 20, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3448B... | [2bec640695](https://linux-hardware.org/?probe=2bec640695) | Sep 20, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d2511347b4](https://linux-hardware.org/?probe=d2511347b4) | Sep 19, 2021 |
| HP            | ENVY 15                     | [ba9a8e1d7a](https://linux-hardware.org/?probe=ba9a8e1d7a) | Sep 19, 2021 |
| Lenovo        | V330-15IKB 81AX             | [9d10bffde2](https://linux-hardware.org/?probe=9d10bffde2) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | [15981e12f3](https://linux-hardware.org/?probe=15981e12f3) | Sep 18, 2021 |
| Lenovo        | ThinkPad X250 20CLS32H00    | [bcdb4d552d](https://linux-hardware.org/?probe=bcdb4d552d) | Sep 18, 2021 |
| HP            | ENVY 15                     | [d2d607895f](https://linux-hardware.org/?probe=d2d607895f) | Sep 18, 2021 |
| Alienware     | 17                          | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Acer          | Aspire V3-572G              | [addf12cb05](https://linux-hardware.org/?probe=addf12cb05) | Sep 16, 2021 |
| TUXEDO        | InfinityBook S 14 Gen6      | [0c206818b9](https://linux-hardware.org/?probe=0c206818b9) | Sep 15, 2021 |
| Acer          | Aspire VX5-591G             | [c7d5407b29](https://linux-hardware.org/?probe=c7d5407b29) | Sep 15, 2021 |
| Dell          | Latitude E7440              | [fc9f25eecb](https://linux-hardware.org/?probe=fc9f25eecb) | Sep 14, 2021 |
| Toshiba       | Satellite P100              | [bc5b605920](https://linux-hardware.org/?probe=bc5b605920) | Sep 13, 2021 |
| HP            | Pavilion Notebook           | [591ba7a77c](https://linux-hardware.org/?probe=591ba7a77c) | Sep 12, 2021 |
| Dell          | Inspiron 3583               | [49b4db94c6](https://linux-hardware.org/?probe=49b4db94c6) | Sep 12, 2021 |
| ASUSTek       | UX303LA                     | [1a67d956de](https://linux-hardware.org/?probe=1a67d956de) | Sep 11, 2021 |
| HP            | Pavilion Notebook           | [f373a049e2](https://linux-hardware.org/?probe=f373a049e2) | Sep 10, 2021 |
| HP            | Pavilion Notebook           | [6e97abfd44](https://linux-hardware.org/?probe=6e97abfd44) | Sep 09, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [7b3432fcf6](https://linux-hardware.org/?probe=7b3432fcf6) | Sep 08, 2021 |
| HP            | Laptop 14-dq1xxx            | [0614925ee7](https://linux-hardware.org/?probe=0614925ee7) | Sep 08, 2021 |
| Gateway       | NV54 Series                 | [fcf57528ed](https://linux-hardware.org/?probe=fcf57528ed) | Sep 08, 2021 |
| Sony          | Serie VJC14                 | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo        | V330-15IKB 81AX             | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| HP            | Laptop 15-bs1xx             | [91ecd39f66](https://linux-hardware.org/?probe=91ecd39f66) | Sep 05, 2021 |
| Medion        | Akoya THE TOUCH 10          | [d49d62a2f5](https://linux-hardware.org/?probe=d49d62a2f5) | Sep 04, 2021 |
| Apple         | MacBookPro8,1               | [da332ba09e](https://linux-hardware.org/?probe=da332ba09e) | Sep 01, 2021 |
| HP            | EliteBook Folio 9470m       | [adbb6a690a](https://linux-hardware.org/?probe=adbb6a690a) | Sep 01, 2021 |
| Dell          | Latitude 3580               | [2befbbba9e](https://linux-hardware.org/?probe=2befbbba9e) | Aug 31, 2021 |
| HP            | Pavilion g6                 | [7dba3c201c](https://linux-hardware.org/?probe=7dba3c201c) | Aug 31, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [48c720456a](https://linux-hardware.org/?probe=48c720456a) | Aug 30, 2021 |
| HP            | ProBook 4320s               | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| eMachines     | G525                        | [d64e29475f](https://linux-hardware.org/?probe=d64e29475f) | Aug 29, 2021 |
| Lenovo        | ThinkPad X201 3249CTO       | [0a9bdb4827](https://linux-hardware.org/?probe=0a9bdb4827) | Aug 27, 2021 |
| Acer          | Aspire A515-51G             | [df0d3e8ac4](https://linux-hardware.org/?probe=df0d3e8ac4) | Aug 26, 2021 |
| HP            | Laptop 15-bs0xx             | [fae546f5cb](https://linux-hardware.org/?probe=fae546f5cb) | Aug 20, 2021 |
| Apple         | MacBookPro9,1               | [e9bec90506](https://linux-hardware.org/?probe=e9bec90506) | Aug 19, 2021 |
| Acer          | Aspire F5-573G              | [9d7628068c](https://linux-hardware.org/?probe=9d7628068c) | Aug 19, 2021 |
| Dell          | System XPS L321X            | [34d7fb6cbb](https://linux-hardware.org/?probe=34d7fb6cbb) | Aug 18, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [f30480d463](https://linux-hardware.org/?probe=f30480d463) | Aug 17, 2021 |
| HP            | Notebook                    | [a3058005e3](https://linux-hardware.org/?probe=a3058005e3) | Aug 16, 2021 |
| HP            | Notebook                    | [7800ef9623](https://linux-hardware.org/?probe=7800ef9623) | Aug 16, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [fa6c69671f](https://linux-hardware.org/?probe=fa6c69671f) | Aug 16, 2021 |
| Apple         | MacBookPro9,1               | [a6b2c12401](https://linux-hardware.org/?probe=a6b2c12401) | Aug 14, 2021 |
| Dell          | Precision 5760              | [824e5e7dad](https://linux-hardware.org/?probe=824e5e7dad) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | [dcfc87a32f](https://linux-hardware.org/?probe=dcfc87a32f) | Aug 14, 2021 |
| Acer          | Aspire A514-54              | [e354646c04](https://linux-hardware.org/?probe=e354646c04) | Aug 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4e6f050b43](https://linux-hardware.org/?probe=4e6f050b43) | Aug 10, 2021 |
| Toshiba       | Satellite L500              | [76a8d2c20a](https://linux-hardware.org/?probe=76a8d2c20a) | Jul 29, 2021 |
| Google        | Cave                        | [e2617f0c2d](https://linux-hardware.org/?probe=e2617f0c2d) | Jul 25, 2021 |
| Toshiba       | Satellite L500              | [7124417642](https://linux-hardware.org/?probe=7124417642) | Jul 22, 2021 |
| HP            | Stream Laptop 14-cb1xxx     | [0447155931](https://linux-hardware.org/?probe=0447155931) | Jul 02, 2021 |
| Acer          | Swift SF314-55G             | [c371b46cbe](https://linux-hardware.org/?probe=c371b46cbe) | Jun 30, 2021 |
| Acer          | Swift SF315-41              | [8df5e13fc0](https://linux-hardware.org/?probe=8df5e13fc0) | Jun 18, 2021 |
| Acer          | Swift SF314-55G             | [4e5cf8aa1e](https://linux-hardware.org/?probe=4e5cf8aa1e) | Jun 13, 2021 |
| Acer          | ConceptD CN315-71P          | [5ecea84320](https://linux-hardware.org/?probe=5ecea84320) | May 15, 2021 |
| Apple         | MacBookPro8,2               | [e87a073ae8](https://linux-hardware.org/?probe=e87a073ae8) | Mar 18, 2021 |
| HP            | EliteBook 840 G3            | [1e31858e51](https://linux-hardware.org/?probe=1e31858e51) | Mar 09, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.11.0-40-generic     | 29        | 19.86%  |
| 5.11.0-27-generic     | 27        | 18.49%  |
| 5.11.0-41-generic     | 23        | 15.75%  |
| 5.11.0-38-generic     | 19        | 13.01%  |
| 5.11.0-37-generic     | 16        | 10.96%  |
| 5.11.0-34-generic     | 11        | 7.53%   |
| 5.11.0-25-generic     | 10        | 6.85%   |
| 5.8.0-55-generic      | 2         | 1.37%   |
| 5.11.0-36-generic     | 2         | 1.37%   |
| 5.8.0-63-generic      | 1         | 0.68%   |
| 5.8.0-53-generic      | 1         | 0.68%   |
| 5.8.0-50-generic      | 1         | 0.68%   |
| 5.8.0-44-generic      | 1         | 0.68%   |
| 5.4.0-91-generic      | 1         | 0.68%   |
| 5.14.7-xanmod1-cacule | 1         | 0.68%   |
| 5.11.0-051100-generic | 1         | 0.68%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 133       | 94.33%  |
| 5.8.0   | 6         | 4.26%   |
| 5.4.0   | 1         | 0.71%   |
| 5.14.7  | 1         | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 133       | 94.33%  |
| 5.8     | 6         | 4.26%   |
| 5.4     | 1         | 0.71%   |
| 5.14    | 1         | 0.71%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 141       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| Pantheon   | 128       | 90.78%  |
| Unknown    | 9         | 6.38%   |
| X-Cinnamon | 2         | 1.42%   |
| GNOME      | 2         | 1.42%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| X11  | 141       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 107       | 75.89%  |
| LightDM | 27        | 19.15%  |
| TDM     | 4         | 2.84%   |
| GDM     | 3         | 2.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 72        | 51.06%  |
| de_DE | 12        | 8.51%   |
| es_ES | 10        | 7.09%   |
| fr_FR | 6         | 4.26%   |
| pt_BR | 5         | 3.55%   |
| ru_RU | 4         | 2.84%   |
| en_GB | 4         | 2.84%   |
| en_CA | 4         | 2.84%   |
| pl_PL | 3         | 2.13%   |
| it_IT | 3         | 2.13%   |
| cs_CZ | 3         | 2.13%   |
| zh_CN | 2         | 1.42%   |
| tr_TR | 2         | 1.42%   |
| en_AU | 2         | 1.42%   |
| vi_VN | 1         | 0.71%   |
| ro_RO | 1         | 0.71%   |
| nl_NL | 1         | 0.71%   |
| id_ID | 1         | 0.71%   |
| hu_HU | 1         | 0.71%   |
| gl_ES | 1         | 0.71%   |
| fi_FI | 1         | 0.71%   |
| de_CH | 1         | 0.71%   |
| da_DK | 1         | 0.71%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 84        | 59.15%  |
| BIOS | 58        | 40.85%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 135       | 95.74%  |
| Overlay | 5         | 3.55%   |
| Btrfs   | 1         | 0.71%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 114       | 80.85%  |
| GPT     | 19        | 13.48%  |
| MBR     | 8         | 5.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 134       | 95.04%  |
| Yes       | 7         | 4.96%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 127       | 90.07%  |
| Yes       | 14        | 9.93%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 31        | 21.99%  |
| Lenovo                  | 26        | 18.44%  |
| Dell                    | 19        | 13.48%  |
| Acer                    | 13        | 9.22%   |
| Apple                   | 12        | 8.51%   |
| ASUSTek Computer        | 9         | 6.38%   |
| Toshiba                 | 4         | 2.84%   |
| HUAWEI                  | 3         | 2.13%   |
| Google                  | 3         | 2.13%   |
| TUXEDO                  | 2         | 1.42%   |
| Sony                    | 2         | 1.42%   |
| MSI                     | 2         | 1.42%   |
| Medion                  | 2         | 1.42%   |
| Star Labs               | 1         | 0.71%   |
| Schenker                | 1         | 0.71%   |
| Samsung Electronics     | 1         | 0.71%   |
| Quanta                  | 1         | 0.71%   |
| Packard Bell            | 1         | 0.71%   |
| Notebook                | 1         | 0.71%   |
| LG Electronics          | 1         | 0.71%   |
| HCL Infosystems Limited | 1         | 0.71%   |
| Gateway                 | 1         | 0.71%   |
| Fujitsu                 | 1         | 0.71%   |
| eMachines               | 1         | 0.71%   |
| Alienware               | 1         | 0.71%   |
| Unknown                 | 1         | 0.71%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo Yoga 300-11IBR 80M1           | 2         | 1.42%   |
| HP Pavilion Notebook                 | 2         | 1.42%   |
| Dell XPS 13 9350                     | 2         | 1.42%   |
| Dell Inspiron N5110                  | 2         | 1.42%   |
| Apple MacBookPro9,1                  | 2         | 1.42%   |
| Apple MacBookPro10,2                 | 2         | 1.42%   |
| Apple MacBookAir7,2                  | 2         | 1.42%   |
| TUXEDO Pulse 15 Gen1                 | 1         | 0.71%   |
| TUXEDO InfinityBook S 14 Gen6        | 1         | 0.71%   |
| Toshiba Satellite P100               | 1         | 0.71%   |
| Toshiba Satellite L840               | 1         | 0.71%   |
| Toshiba Satellite L750               | 1         | 0.71%   |
| Toshiba Satellite L500               | 1         | 0.71%   |
| Star Labs StarBook                   | 1         | 0.71%   |
| Sony SVE15115EN                      | 1         | 0.71%   |
| Sony Serie VJC14                     | 1         | 0.71%   |
| Schenker X170KM-G                    | 1         | 0.71%   |
| Samsung 550XDA                       | 1         | 0.71%   |
| Quanta TW9/SW9                       | 1         | 0.71%   |
| Packard Bell EasyNote LS11HR         | 1         | 0.71%   |
| Notebook L140CU                      | 1         | 0.71%   |
| MSI Modern 14 B4MW                   | 1         | 0.71%   |
| MSI GF72 7RE                         | 1         | 0.71%   |
| Medion E7218                         | 1         | 0.71%   |
| Medion Akoya THE TOUCH 10            | 1         | 0.71%   |
| LG P1-JSUVT                          | 1         | 0.71%   |
| Lenovo V330-15IKB 81AX               | 1         | 0.71%   |
| Lenovo ThinkPad X250 20CLS32H00      | 1         | 0.71%   |
| Lenovo ThinkPad X230 23259L3         | 1         | 0.71%   |
| Lenovo ThinkPad X201 Tablet 311396G  | 1         | 0.71%   |
| Lenovo ThinkPad X201 3249CTO         | 1         | 0.71%   |
| Lenovo ThinkPad X140e 20BLS00400     | 1         | 0.71%   |
| Lenovo ThinkPad X1 Carbon 3448B86    | 1         | 0.71%   |
| Lenovo ThinkPad W700 2758MVG         | 1         | 0.71%   |
| Lenovo ThinkPad T470 20HD004AUS      | 1         | 0.71%   |
| Lenovo ThinkPad T460s 20F9CTO1WW     | 1         | 0.71%   |
| Lenovo ThinkPad T460s 20F90042MS     | 1         | 0.71%   |
| Lenovo ThinkPad T430 2342A19         | 1         | 0.71%   |
| Lenovo ThinkPad T410s 292494G        | 1         | 0.71%   |
| Lenovo ThinkPad T14 Gen 1 20UES5SR00 | 1         | 0.71%   |
| Lenovo ThinkPad SL400 2743A37        | 1         | 0.71%   |
| Lenovo ThinkPad E470 20H10052IG      | 1         | 0.71%   |
| Lenovo ThinkPad E14 Gen 3 20Y7006XMX | 1         | 0.71%   |
| Lenovo IdeaPad S145-15AST 81N3       | 1         | 0.71%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5     | 1         | 0.71%   |
| Lenovo IdeaPad 5 14ARE05 81YM        | 1         | 0.71%   |
| Lenovo IdeaPad 330-15IKB 81FE        | 1         | 0.71%   |
| Lenovo IdeaPad 320S-14IKB 81BN       | 1         | 0.71%   |
| Lenovo IdeaPad 120S-14IAP 81A5       | 1         | 0.71%   |
| Lenovo G50-45 80E3                   | 1         | 0.71%   |
| HUAWEI NBLB-WAX9N                    | 1         | 0.71%   |
| HUAWEI MACHD-WXX9                    | 1         | 0.71%   |
| HUAWEI BOHK-WAX9X                    | 1         | 0.71%   |
| HP ZBook 15 G5                       | 1         | 0.71%   |
| HP Stream Laptop 14-cb1xxx           | 1         | 0.71%   |
| HP ProBook 6460b                     | 1         | 0.71%   |
| HP ProBook 4730s                     | 1         | 0.71%   |
| HP ProBook 4540s                     | 1         | 0.71%   |
| HP ProBook 4530s                     | 1         | 0.71%   |
| HP ProBook 450 G8 Notebook PC        | 1         | 0.71%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Lenovo ThinkPad             | 16        | 11.35%  |
| Acer Aspire                 | 10        | 7.09%   |
| HP Pavilion                 | 7         | 4.96%   |
| Lenovo IdeaPad              | 6         | 4.26%   |
| HP ProBook                  | 6         | 4.26%   |
| HP Laptop                   | 6         | 4.26%   |
| HP EliteBook                | 6         | 4.26%   |
| Dell XPS                    | 5         | 3.55%   |
| Dell Inspiron               | 5         | 3.55%   |
| Toshiba Satellite           | 4         | 2.84%   |
| Dell Latitude               | 4         | 2.84%   |
| Lenovo Yoga                 | 2         | 1.42%   |
| Dell System                 | 2         | 1.42%   |
| Dell Precision              | 2         | 1.42%   |
| Apple MacBookPro9           | 2         | 1.42%   |
| Apple MacBookPro8           | 2         | 1.42%   |
| Apple MacBookPro10          | 2         | 1.42%   |
| Apple MacBookAir7           | 2         | 1.42%   |
| Acer Swift                  | 2         | 1.42%   |
| TUXEDO Pulse                | 1         | 0.71%   |
| TUXEDO InfinityBook         | 1         | 0.71%   |
| Star Labs StarBook          | 1         | 0.71%   |
| Sony SVE15115EN             | 1         | 0.71%   |
| Sony Serie                  | 1         | 0.71%   |
| Schenker X170KM-G           | 1         | 0.71%   |
| Samsung 550XDA              | 1         | 0.71%   |
| Quanta TW9                  | 1         | 0.71%   |
| Packard Bell EasyNote       | 1         | 0.71%   |
| Notebook L140CU             | 1         | 0.71%   |
| MSI Modern                  | 1         | 0.71%   |
| MSI GF72                    | 1         | 0.71%   |
| Medion E7218                | 1         | 0.71%   |
| Medion Akoya                | 1         | 0.71%   |
| LG P1-JSUVT                 | 1         | 0.71%   |
| Lenovo V330-15IKB           | 1         | 0.71%   |
| Lenovo G50-45               | 1         | 0.71%   |
| HUAWEI NBLB-WAX9N           | 1         | 0.71%   |
| HUAWEI MACHD-WXX9           | 1         | 0.71%   |
| HUAWEI BOHK-WAX9X           | 1         | 0.71%   |
| HP ZBook                    | 1         | 0.71%   |
| HP Stream                   | 1         | 0.71%   |
| HP Notebook                 | 1         | 0.71%   |
| HP G62                      | 1         | 0.71%   |
| HP ENVY                     | 1         | 0.71%   |
| HP Compaq                   | 1         | 0.71%   |
| HCL Infosystems Limited HCL | 1         | 0.71%   |
| Google Setzer               | 1         | 0.71%   |
| Google Kip                  | 1         | 0.71%   |
| Google Cyan                 | 1         | 0.71%   |
| Gateway NV54                | 1         | 0.71%   |
| Fujitsu LIFEBOOK            | 1         | 0.71%   |
| eMachines G525              | 1         | 0.71%   |
| Dell Vostro                 | 1         | 0.71%   |
| ASUS ZenBook                | 1         | 0.71%   |
| ASUS VivoBook               | 1         | 0.71%   |
| ASUS UX303LA                | 1         | 0.71%   |
| ASUS ROG                    | 1         | 0.71%   |
| ASUS GL502VS                | 1         | 0.71%   |
| ASUS FX503VD                | 1         | 0.71%   |
| ASUS E502SA                 | 1         | 0.71%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 17        | 12.06%  |
| 2020    | 15        | 10.64%  |
| 2021    | 13        | 9.22%   |
| 2017    | 12        | 8.51%   |
| 2016    | 12        | 8.51%   |
| 2010    | 12        | 8.51%   |
| 2018    | 11        | 7.8%    |
| 2012    | 11        | 7.8%    |
| 2019    | 9         | 6.38%   |
| 2015    | 9         | 6.38%   |
| 2014    | 8         | 5.67%   |
| 2009    | 5         | 3.55%   |
| 2013    | 2         | 1.42%   |
| 2007    | 2         | 1.42%   |
| 2008    | 1         | 0.71%   |
| 2006    | 1         | 0.71%   |
| Unknown | 1         | 0.71%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 141       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 114       | 80.85%  |
| Enabled  | 27        | 19.15%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 137       | 97.16%  |
| Yes  | 4         | 2.84%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 44        | 31.21%  |
| 3.01-4.0   | 33        | 23.4%   |
| 8.01-16.0  | 24        | 17.02%  |
| 16.01-24.0 | 22        | 15.6%   |
| 32.01-64.0 | 7         | 4.96%   |
| 1.01-2.0   | 7         | 4.96%   |
| 24.01-32.0 | 3         | 2.13%   |
| 2.01-3.0   | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 62        | 42.18%  |
| 2.01-3.0 | 43        | 29.25%  |
| 4.01-8.0 | 21        | 14.29%  |
| 3.01-4.0 | 19        | 12.93%  |
| 0.51-1.0 | 2         | 1.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 109       | 76.76%  |
| 2      | 29        | 20.42%  |
| 4      | 2         | 1.41%   |
| 5      | 1         | 0.7%    |
| 3      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 98        | 69.5%   |
| Yes       | 43        | 30.5%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 77.3%   |
| No        | 32        | 22.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 140       | 99.29%  |
| No        | 1         | 0.71%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 85.21%  |
| No        | 21        | 14.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 20        | 14.18%  |
| India              | 13        | 9.22%   |
| Germany            | 12        | 8.51%   |
| UK                 | 7         | 4.96%   |
| France             | 7         | 4.96%   |
| Russia             | 6         | 4.26%   |
| Canada             | 6         | 4.26%   |
| Brazil             | 6         | 4.26%   |
| Netherlands        | 4         | 2.84%   |
| Argentina          | 4         | 2.84%   |
| Sweden             | 3         | 2.13%   |
| Poland             | 3         | 2.13%   |
| Italy              | 3         | 2.13%   |
| Indonesia          | 3         | 2.13%   |
| Denmark            | 3         | 2.13%   |
| Czechia            | 3         | 2.13%   |
| Australia          | 3         | 2.13%   |
| Vietnam            | 2         | 1.42%   |
| Turkey             | 2         | 1.42%   |
| Romania            | 2         | 1.42%   |
| Paraguay           | 2         | 1.42%   |
| Mexico             | 2         | 1.42%   |
| Guatemala          | 2         | 1.42%   |
| Finland            | 2         | 1.42%   |
| Uruguay            | 1         | 0.71%   |
| Thailand           | 1         | 0.71%   |
| Spain              | 1         | 0.71%   |
| Slovenia           | 1         | 0.71%   |
| Serbia             | 1         | 0.71%   |
| Philippines        | 1         | 0.71%   |
| Myanmar            | 1         | 0.71%   |
| Morocco            | 1         | 0.71%   |
| Malaysia           | 1         | 0.71%   |
| Latvia             | 1         | 0.71%   |
| Kazakhstan         | 1         | 0.71%   |
| Japan              | 1         | 0.71%   |
| Ireland            | 1         | 0.71%   |
| Hungary            | 1         | 0.71%   |
| Guyana             | 1         | 0.71%   |
| Estonia            | 1         | 0.71%   |
| Dominican Republic | 1         | 0.71%   |
| China              | 1         | 0.71%   |
| Chile              | 1         | 0.71%   |
| Belgium            | 1         | 0.71%   |
| Austria            | 1         | 0.71%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Vernon                | 3         | 2.08%   |
| Moscow                | 3         | 2.08%   |
| Warsaw                | 2         | 1.39%   |
| Perth                 | 2         | 1.39%   |
| Paris                 | 2         | 1.39%   |
| Kolkata               | 2         | 1.39%   |
| Guatemala City        | 2         | 1.39%   |
| Coimbatore            | 2         | 1.39%   |
| Buenos Aires          | 2         | 1.39%   |
| Zonguldak             | 1         | 0.69%   |
| Woodbridge            | 1         | 0.69%   |
| Walsrode              | 1         | 0.69%   |
| Wakefield             | 1         | 0.69%   |
| Villeurbanne          | 1         | 0.69%   |
| Vienna                | 1         | 0.69%   |
| Victoria              | 1         | 0.69%   |
| Vertaizon             | 1         | 0.69%   |
| Valladolid            | 1         | 0.69%   |
| Vălenii Șomcutei    | 1         | 0.69%   |
| Turku                 | 1         | 0.69%   |
| Turin                 | 1         | 0.69%   |
| Toledo                | 1         | 0.69%   |
| The Hague             | 1         | 0.69%   |
| Temecula              | 1         | 0.69%   |
| Tallinn               | 1         | 0.69%   |
| Taganrog              | 1         | 0.69%   |
| Surabaya              | 1         | 0.69%   |
| Stockport             | 1         | 0.69%   |
| Stockholm             | 1         | 0.69%   |
| Stevenage             | 1         | 0.69%   |
| Skanderborg           | 1         | 0.69%   |
| Sinop                 | 1         | 0.69%   |
| Setagaya-ku           | 1         | 0.69%   |
| Sedlec                | 1         | 0.69%   |
| SÃ£o Pedro          | 1         | 0.69%   |
| Sassnitz              | 1         | 0.69%   |
| Sao Paulo             | 1         | 0.69%   |
| Sao Joaquim da Barra  | 1         | 0.69%   |
| Sao Bernardo do Campo | 1         | 0.69%   |
| Santo Domingo Este    | 1         | 0.69%   |
| Santo André          | 1         | 0.69%   |
| Santiago              | 1         | 0.69%   |
| Santa Monica          | 1         | 0.69%   |
| San Lorenzo           | 1         | 0.69%   |
| San Jose              | 1         | 0.69%   |
| San Antonio           | 1         | 0.69%   |
| Salach                | 1         | 0.69%   |
| Sakai                 | 1         | 0.69%   |
| Rzeszów              | 1         | 0.69%   |
| Rostov-on-Don         | 1         | 0.69%   |
| Rekem                 | 1         | 0.69%   |
| Reading               | 1         | 0.69%   |
| Queretaro             | 1         | 0.69%   |
| Pskov                 | 1         | 0.69%   |
| Prague                | 1         | 0.69%   |
| Pompano Beach         | 1         | 0.69%   |
| Patiala               | 1         | 0.69%   |
| Oyten                 | 1         | 0.69%   |
| Ostrov                | 1         | 0.69%   |
| Nyborg                | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 29        | 32     | 17.16%  |
| Samsung Electronics       | 27        | 29     | 15.98%  |
| Seagate                   | 15        | 17     | 8.88%   |
| Toshiba                   | 12        | 12     | 7.1%    |
| Sandisk                   | 12        | 14     | 7.1%    |
| Unknown                   | 10        | 11     | 5.92%   |
| Crucial                   | 7         | 7      | 4.14%   |
| Micron Technology         | 6         | 6      | 3.55%   |
| HGST                      | 6         | 6      | 3.55%   |
| Apple                     | 6         | 6      | 3.55%   |
| Kingston                  | 5         | 7      | 2.96%   |
| Hitachi                   | 5         | 5      | 2.96%   |
| SK Hynix                  | 3         | 4      | 1.78%   |
| Intel                     | 3         | 3      | 1.78%   |
| Silicon Motion            | 2         | 2      | 1.18%   |
| LITEONIT                  | 2         | 2      | 1.18%   |
| LITEON                    | 2         | 2      | 1.18%   |
| Gigabyte Technology       | 2         | 2      | 1.18%   |
| Union Memory              | 1         | 1      | 0.59%   |
| Star Drive                | 1         | 1      | 0.59%   |
| Phison                    | 1         | 1      | 0.59%   |
| Patriot                   | 1         | 1      | 0.59%   |
| Netac                     | 1         | 1      | 0.59%   |
| Micron/Crucial Technology | 1         | 1      | 0.59%   |
| Mercury                   | 1         | 1      | 0.59%   |
| LS                        | 1         | 1      | 0.59%   |
| KIOXIA                    | 1         | 1      | 0.59%   |
| HUAWEI                    | 1         | 1      | 0.59%   |
| Hewlett-Packard           | 1         | 1      | 0.59%   |
| Fujitsu                   | 1         | 1      | 0.59%   |
| CLOVER                    | 1         | 1      | 0.59%   |
| China                     | 1         | 1      | 0.59%   |
| A-DATA Technology         | 1         | 2      | 0.59%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 256GB                     | 5         | 2.91%   |
| Sandisk NVMe SSD Drive 512GB                     | 4         | 2.33%   |
| Samsung NVMe SSD Drive 512GB                     | 4         | 2.33%   |
| WDC WD5000LPVX-22V0TT0 500GB                     | 3         | 1.74%   |
| WDC WD10JPVX-22JC3T0 1TB                         | 3         | 1.74%   |
| Unknown MMC Card  128GB                          | 3         | 1.74%   |
| Toshiba MQ01ABD100V -63 1TB                      | 3         | 1.74%   |
| Seagate ST1000LM035-1RK172 1TB                   | 3         | 1.74%   |
| Kingston SA400S37240G 240GB SSD                  | 3         | 1.74%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                 | 2         | 1.16%   |
| WDC WD10SPZX-21Z10T0 1TB                         | 2         | 1.16%   |
| Unknown MMC Card  32GB                           | 2         | 1.16%   |
| Unknown MMC Card  16GB                           | 2         | 1.16%   |
| Toshiba MK6475GSX 640GB                          | 2         | 1.16%   |
| SK Hynix NVMe SSD Drive 512GB                    | 2         | 1.16%   |
| Seagate ST500LT012-1DG142 500GB                  | 2         | 1.16%   |
| Seagate ST2000LX001-1RG174 2TB                   | 2         | 1.16%   |
| Sandisk NVMe SSD Drive 256GB                     | 2         | 1.16%   |
| Samsung SSD 860 EVO 250GB                        | 2         | 1.16%   |
| HGST HTS541010A9E680 1TB                         | 2         | 1.16%   |
| Crucial CT240BX500SSD1 240GB                     | 2         | 1.16%   |
| Apple SSD SD128E 121GB                           | 2         | 1.16%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                 | 1         | 0.58%   |
| WDC WDS200T2B0B-00YS70 2TB SSD                   | 1         | 0.58%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                 | 1         | 0.58%   |
| WDC WD6400BEVT-22A0RT0 640GB                     | 1         | 0.58%   |
| WDC WD5000LPLX-08ZNTT0 500GB                     | 1         | 0.58%   |
| WDC WD5000BPVT-75HXZT1 500GB                     | 1         | 0.58%   |
| WDC WD5000BPVT-22HXZT3 500GB                     | 1         | 0.58%   |
| WDC WD5000BPVT-22HXZT1 500GB                     | 1         | 0.58%   |
| WDC WD5000BPVT-00HXZT1 500GB                     | 1         | 0.58%   |
| WDC WD5000BPKT-75PK4T0 500GB                     | 1         | 0.58%   |
| WDC WD3200BEVT-75A23T0 320GB                     | 1         | 0.58%   |
| WDC WD2500BEKT-75A25T0 250GB                     | 1         | 0.58%   |
| WDC WD20SPZX-21UA7T0 2TB                         | 1         | 0.58%   |
| WDC WD10SPZX-35Z10T0 1TB                         | 1         | 0.58%   |
| WDC WD10SPZX-24Z10T0 1TB                         | 1         | 0.58%   |
| WDC WD10SPZX-22Z10T1 1TB                         | 1         | 0.58%   |
| WDC WD10JPVX-60JC3T1 1TB                         | 1         | 0.58%   |
| WDC PC SN720 SDAPNTW-256G-1014 256GB             | 1         | 0.58%   |
| WDC PC SN720 SDAPNTW-256G-1006 256GB             | 1         | 0.58%   |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB             | 1         | 0.58%   |
| WDC PC SN520 SDAPNUW-512G-1014 512GB             | 1         | 0.58%   |
| Unknown xD/SD/M.S.                               | 1         | 0.58%   |
| Unknown TA2964  64GB                             | 1         | 0.58%   |
| Unknown MMC Card  64GB                           | 1         | 0.58%   |
| Union Memory RTOTJ256VGD2MYX 256GB               | 1         | 0.58%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 0.58%   |
| Toshiba MK5065GSXF 500GB                         | 1         | 0.58%   |
| Toshiba MK3275GSX 320GB                          | 1         | 0.58%   |
| Toshiba MK3259GSXP 320GB                         | 1         | 0.58%   |
| Toshiba MK2533GSG 250GB                          | 1         | 0.58%   |
| Toshiba MK1676GSX 160GB                          | 1         | 0.58%   |
| Toshiba MK1665GSX 160GB                          | 1         | 0.58%   |
| Star Drive PCIe SSD 480GB                        | 1         | 0.58%   |
| SK Hynix SKHynix_HFS512GDE9X084N 512GB           | 1         | 0.58%   |
| Silicon Motion SSD_M.2_PCI_NVME_1TB_InnovationIT | 1         | 0.58%   |
| Silicon Motion NVMe SSD Drive 120GB              | 1         | 0.58%   |
| Seagate ST9320325AS 320GB                        | 1         | 0.58%   |
| Seagate ST9250315AS 250GB                        | 1         | 0.58%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 23     | 34.92%  |
| Seagate             | 15        | 17     | 23.81%  |
| Toshiba             | 12        | 12     | 19.05%  |
| HGST                | 6         | 6      | 9.52%   |
| Hitachi             | 5         | 5      | 7.94%   |
| Samsung Electronics | 2         | 2      | 3.17%   |
| Fujitsu             | 1         | 1      | 1.59%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 10        | 11     | 18.52%  |
| Crucial             | 7         | 7      | 12.96%  |
| Apple               | 6         | 6      | 11.11%  |
| WDC                 | 5         | 5      | 9.26%   |
| SanDisk             | 5         | 6      | 9.26%   |
| Kingston            | 4         | 6      | 7.41%   |
| Micron Technology   | 3         | 3      | 5.56%   |
| LITEONIT            | 2         | 2      | 3.7%    |
| LITEON              | 2         | 2      | 3.7%    |
| Intel               | 2         | 2      | 3.7%    |
| Patriot             | 1         | 1      | 1.85%   |
| Netac               | 1         | 1      | 1.85%   |
| Mercury             | 1         | 1      | 1.85%   |
| LS                  | 1         | 1      | 1.85%   |
| Hewlett-Packard     | 1         | 1      | 1.85%   |
| Gigabyte Technology | 1         | 1      | 1.85%   |
| China               | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 2      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 62        | 66     | 38.04%  |
| SSD     | 50        | 59     | 30.67%  |
| NVMe    | 38        | 44     | 23.31%  |
| MMC     | 9         | 10     | 5.52%   |
| Unknown | 4         | 4      | 2.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 105       | 127    | 68.18%  |
| NVMe | 38        | 44     | 24.68%  |
| MMC  | 9         | 10     | 5.84%   |
| SAS  | 2         | 2      | 1.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 73        | 86     | 66.36%  |
| 0.51-1.0   | 32        | 33     | 29.09%  |
| 1.01-2.0   | 5         | 6      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 61        | 42.66%  |
| 251-500    | 38        | 26.57%  |
| 501-1000   | 19        | 13.29%  |
| 51-100     | 12        | 8.39%   |
| 1001-2000  | 5         | 3.5%    |
| 1-20       | 4         | 2.8%    |
| 21-50      | 3         | 2.1%    |
| 2001-3000  | 1         | 0.7%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 80        | 56.74%  |
| 21-50     | 30        | 21.28%  |
| 51-100    | 16        | 11.35%  |
| 101-250   | 9         | 6.38%   |
| 251-500   | 2         | 1.42%   |
| 1001-2000 | 2         | 1.42%   |
| 501-1000  | 2         | 1.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD5000BPKT-75PK4T0 500GB      | 1         | 1      | 25%     |
| Toshiba MK3259GSXP 320GB          | 1         | 1      | 25%     |
| Seagate ST320LT020-9YG142 320GB   | 1         | 1      | 25%     |
| SanDisk SD7SB3Q256G1002 256GB SSD | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 25%     |
| Toshiba | 1         | 1      | 25%     |
| Seagate | 1         | 1      | 25%     |
| SanDisk | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 75%     |
| SSD  | 1         | 1      | 25%     |

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
| Detected | 115       | 151    | 80.42%  |
| Works    | 24        | 28     | 16.78%  |
| Malfunc  | 4         | 4      | 2.8%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 107       | 65.24%  |
| Samsung Electronics         | 19        | 11.59%  |
| Sandisk                     | 12        | 7.32%   |
| AMD                         | 11        | 6.71%   |
| SK Hynix                    | 3         | 1.83%   |
| Phison Electronics          | 3         | 1.83%   |
| Micron Technology           | 3         | 1.83%   |
| Silicon Motion              | 2         | 1.22%   |
| Nvidia                      | 1         | 0.61%   |
| Micron/Crucial Technology   | 1         | 0.61%   |
| KIOXIA                      | 1         | 0.61%   |
| Kingston Technology Company | 1         | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 14        | 8.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 14        | 8.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 5.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 10        | 5.85%   |
| AMD FCH SATA Controller [AHCI mode]                                                    | 9         | 5.26%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 7         | 4.09%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 6         | 3.51%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 6         | 3.51%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 4         | 2.34%   |
| Samsung NVMe SSD Controller SM951/PM951                                                | 4         | 2.34%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 4         | 2.34%   |
| SK Hynix Gold P31 SSD                                                                  | 3         | 1.75%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 3         | 1.75%   |
| Samsung NVMe SSD Controller 980                                                        | 3         | 1.75%   |
| Samsung Electronics SATA controller                                                    | 3         | 1.75%   |
| Micron Non-Volatile memory controller                                                  | 3         | 1.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 3         | 1.75%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 3         | 1.75%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 3         | 1.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 3         | 1.75%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 3         | 1.75%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 3         | 1.75%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 3         | 1.75%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 1.75%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.75%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 2         | 1.17%   |
| Sandisk Non-Volatile memory controller                                                 | 2         | 1.17%   |
| Phison E12 NVMe Controller                                                             | 2         | 1.17%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                        | 2         | 1.17%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 1.17%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 2         | 1.17%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 2         | 1.17%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 2         | 1.17%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 1         | 0.58%   |
| Silicon Motion Non-Volatile memory controller                                          | 1         | 0.58%   |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                             | 1         | 0.58%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 1         | 0.58%   |
| Samsung Apple PCIe SSD                                                                 | 1         | 0.58%   |
| Phison PS5013 E13 NVMe Controller                                                      | 1         | 0.58%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 1         | 0.58%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                        | 1         | 0.58%   |
| KIOXIA Non-Volatile memory controller                                                  | 1         | 0.58%   |
| Kingston Company Company Non-Volatile memory controller                                | 1         | 0.58%   |
| Intel SSD 660P Series                                                                  | 1         | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 1         | 0.58%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 1         | 0.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 1         | 0.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 1         | 0.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 1         | 0.58%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 1         | 0.58%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 1         | 0.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 1         | 0.58%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 1         | 0.58%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 1         | 0.58%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 1         | 0.58%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                   | 1         | 0.58%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 1         | 0.58%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 1         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 100       | 60.98%  |
| NVMe | 38        | 23.17%  |
| RAID | 16        | 9.76%   |
| IDE  | 10        | 6.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 125       | 88.65%  |
| AMD    | 16        | 11.35%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-6200U CPU @ 2.30GHz           | 6         | 4.26%   |
| Intel Core i3-2310M CPU @ 2.10GHz           | 5         | 3.55%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 2.84%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 2.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 2.13%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 3         | 2.13%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 3         | 2.13%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz    | 2         | 1.42%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 1.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 2         | 1.42%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz          | 2         | 1.42%   |
| Intel Core i7-3520M CPU @ 2.90GHz           | 2         | 1.42%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.42%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.42%   |
| Intel Core i5-5250U CPU @ 1.60GHz           | 2         | 1.42%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 2         | 1.42%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.42%   |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 2         | 1.42%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 2         | 1.42%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.42%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.42%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.42%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 2         | 1.42%   |
| Intel Xeon W-11855M CPU @ 3.20GHz           | 1         | 0.71%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 1         | 0.71%   |
| Intel Pentium CPU N4200 @ 1.10GHz           | 1         | 0.71%   |
| Intel Pentium CPU N3700 @ 1.60GHz           | 1         | 0.71%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 1         | 0.71%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 1         | 0.71%   |
| Intel Pentium CPU B950 @ 2.10GHz            | 1         | 0.71%   |
| Intel Pentium CPU 6405U @ 2.40GHz           | 1         | 0.71%   |
| Intel Pentium 3556U @ 1.70GHz               | 1         | 0.71%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.71%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 1         | 0.71%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 1         | 0.71%   |
| Intel Core i7-7600U CPU @ 2.80GHz           | 1         | 0.71%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 1         | 0.71%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 1         | 0.71%   |
| Intel Core i7-5557U CPU @ 3.10GHz           | 1         | 0.71%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 1         | 0.71%   |
| Intel Core i7-4850HQ CPU @ 2.30GHz          | 1         | 0.71%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.71%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 1         | 0.71%   |
| Intel Core i7-3720QM CPU @ 2.60GHz          | 1         | 0.71%   |
| Intel Core i7-3687U CPU @ 2.10GHz           | 1         | 0.71%   |
| Intel Core i7-3667U CPU @ 2.00GHz           | 1         | 0.71%   |
| Intel Core i7-3615QM CPU @ 2.30GHz          | 1         | 0.71%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.71%   |
| Intel Core i7-2637M CPU @ 1.70GHz           | 1         | 0.71%   |
| Intel Core i7-2635QM CPU @ 2.00GHz          | 1         | 0.71%   |
| Intel Core i7 CPU L 640 @ 2.13GHz           | 1         | 0.71%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 1         | 0.71%   |
| Intel Core i5-7300U CPU @ 2.60GHz           | 1         | 0.71%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz          | 1         | 0.71%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 1         | 0.71%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 1         | 0.71%   |
| Intel Core i5-4260U CPU @ 1.40GHz           | 1         | 0.71%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 1         | 0.71%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 1         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 37        | 26.24%  |
| Intel Core i7           | 30        | 21.28%  |
| Intel Core i3           | 16        | 11.35%  |
| Other                   | 11        | 7.8%    |
| Intel Celeron           | 10        | 7.09%   |
| Intel Pentium           | 8         | 5.67%   |
| AMD Ryzen 5             | 7         | 4.96%   |
| Intel Core 2 Duo        | 5         | 3.55%   |
| Intel Pentium Silver    | 2         | 1.42%   |
| Intel Pentium Dual-Core | 2         | 1.42%   |
| Intel Core 2            | 2         | 1.42%   |
| AMD Ryzen 7             | 2         | 1.42%   |
| Intel Xeon              | 1         | 0.71%   |
| Intel Celeron M         | 1         | 0.71%   |
| AMD Ryzen 7 PRO         | 1         | 0.71%   |
| AMD Ryzen 5 PRO         | 1         | 0.71%   |
| AMD Phenom II           | 1         | 0.71%   |
| AMD C-60                | 1         | 0.71%   |
| AMD A8                  | 1         | 0.71%   |
| AMD A6                  | 1         | 0.71%   |
| AMD A4                  | 1         | 0.71%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 84        | 59.57%  |
| 4      | 42        | 29.79%  |
| 6      | 11        | 7.8%    |
| 8      | 3         | 2.13%   |
| 1      | 1         | 0.71%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 141       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 104       | 73.76%  |
| 1      | 37        | 26.24%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 141       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 17        | 11.89%  |
| Unknown    | 14        | 9.79%   |
| 0x806c1    | 9         | 6.29%   |
| 0x306a9    | 9         | 6.29%   |
| 0x406e3    | 8         | 5.59%   |
| 0x20655    | 7         | 4.9%    |
| 0x306d4    | 6         | 4.2%    |
| 0x806ea    | 5         | 3.5%    |
| 0x40651    | 5         | 3.5%    |
| 0x1067a    | 5         | 3.5%    |
| 0x906e9    | 4         | 2.8%    |
| 0x806e9    | 4         | 2.8%    |
| 0x20652    | 4         | 2.8%    |
| 0x806ec    | 3         | 2.1%    |
| 0x406c4    | 3         | 2.1%    |
| 0x306c3    | 3         | 2.1%    |
| 0x30678    | 3         | 2.1%    |
| 0xa0652    | 2         | 1.4%    |
| 0x806eb    | 2         | 1.4%    |
| 0x706a8    | 2         | 1.4%    |
| 0x706a1    | 2         | 1.4%    |
| 0x6fb      | 2         | 1.4%    |
| 0x406c3    | 2         | 1.4%    |
| 0xa0671    | 1         | 0.7%    |
| 0x806d1    | 1         | 0.7%    |
| 0x706e5    | 1         | 0.7%    |
| 0x6fd      | 1         | 0.7%    |
| 0x6fa      | 1         | 0.7%    |
| 0x6f6      | 1         | 0.7%    |
| 0x506e3    | 1         | 0.7%    |
| 0x506c9    | 1         | 0.7%    |
| 0x40661    | 1         | 0.7%    |
| 0x0a50000c | 1         | 0.7%    |
| 0x08608103 | 1         | 0.7%    |
| 0x08600106 | 1         | 0.7%    |
| 0x08600104 | 1         | 0.7%    |
| 0x08600103 | 1         | 0.7%    |
| 0x08108109 | 1         | 0.7%    |
| 0x08101016 | 1         | 0.7%    |
| 0x08101007 | 1         | 0.7%    |
| 0x07030105 | 1         | 0.7%    |
| 0x07000110 | 1         | 0.7%    |
| 0x06006705 | 1         | 0.7%    |
| 0x05000119 | 1         | 0.7%    |
| 0x010000c8 | 1         | 0.7%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 21        | 14.89%  |
| SandyBridge   | 19        | 13.48%  |
| Westmere      | 11        | 7.8%    |
| Skylake       | 11        | 7.8%    |
| TigerLake     | 9         | 6.38%   |
| Silvermont    | 9         | 6.38%   |
| IvyBridge     | 9         | 6.38%   |
| Haswell       | 9         | 6.38%   |
| Broadwell     | 6         | 4.26%   |
| Penryn        | 5         | 3.55%   |
| Core          | 5         | 3.55%   |
| Zen 2         | 4         | 2.84%   |
| Goldmont plus | 4         | 2.84%   |
| Icelake       | 3         | 2.13%   |
| Zen+          | 2         | 1.42%   |
| Zen 3         | 2         | 1.42%   |
| Zen           | 2         | 1.42%   |
| CometLake     | 2         | 1.42%   |
| Unknown       | 2         | 1.42%   |
| Puma          | 1         | 0.71%   |
| K10           | 1         | 0.71%   |
| Jaguar        | 1         | 0.71%   |
| Goldmont      | 1         | 0.71%   |
| Excavator     | 1         | 0.71%   |
| Bobcat        | 1         | 0.71%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 116       | 67.44%  |
| Nvidia | 32        | 18.6%   |
| AMD    | 24        | 13.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 9.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 6.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 5.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 9         | 5.11%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 7         | 3.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 3.41%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.84%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.84%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 2.27%   |
| Intel HD Graphics 630                                                                    | 4         | 2.27%   |
| Intel HD Graphics 620                                                                    | 4         | 2.27%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 2.27%   |
| AMD Renoir                                                                               | 4         | 2.27%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.7%    |
| Intel HD Graphics 5500                                                                   | 3         | 1.7%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 1.7%    |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 1.14%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 1.14%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 1.14%   |
| Nvidia GK107M [GeForce GT 650M Mac Edition]                                              | 2         | 1.14%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 2         | 1.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 2         | 1.14%   |
| Intel Tiger Lake UHD Graphics                                                            | 2         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 1.14%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 1.14%   |
| Intel HD Graphics 6000                                                                   | 2         | 1.14%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 1.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 1.14%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 1.14%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 2         | 1.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 2         | 1.14%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 1.14%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 2         | 1.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 2         | 1.14%   |
| AMD Cezanne                                                                              | 2         | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.57%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 1         | 0.57%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.57%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 1         | 0.57%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 1         | 0.57%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 1         | 0.57%   |
| Nvidia GM108M [GeForce 930M]                                                             | 1         | 0.57%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 0.57%   |
| Nvidia GM108M [GeForce 840M]                                                             | 1         | 0.57%   |
| Nvidia GM107 [GeForce 940MX]                                                             | 1         | 0.57%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.57%   |
| Nvidia GK107GLM [Quadro K1100M]                                                          | 1         | 0.57%   |
| Nvidia GK106M [GeForce GTX 770M]                                                         | 1         | 0.57%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 1         | 0.57%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 1         | 0.57%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 1         | 0.57%   |
| Nvidia GA104GLM [RTX A3000 Mobile]                                                       | 1         | 0.57%   |
| Nvidia G94GLM [Quadro FX 2700M]                                                          | 1         | 0.57%   |
| Nvidia G73M [GeForce Go 7600]                                                            | 1         | 0.57%   |
| Intel VGA compatible controller                                                          | 1         | 0.57%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 1         | 0.57%   |
| Intel Iris Plus Graphics G4 (Ice Lake)                                                   | 1         | 0.57%   |
| Intel Iris Graphics 6100                                                                 | 1         | 0.57%   |
| Intel Crystal Well Integrated Graphics Controller                                        | 1         | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 86        | 60.99%  |
| Intel + Nvidia | 25        | 17.73%  |
| 1 x AMD        | 16        | 11.35%  |
| 1 x Nvidia     | 6         | 4.26%   |
| Intel + AMD    | 5         | 3.55%   |
| 2 x AMD        | 2         | 1.42%   |
| AMD + Nvidia   | 1         | 0.71%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 125       | 88.03%  |
| Proprietary | 14        | 9.86%   |
| Unknown     | 3         | 2.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 103       | 72.54%  |
| 0.01-0.5   | 13        | 9.15%   |
| 1.01-2.0   | 10        | 7.04%   |
| 0.51-1.0   | 9         | 6.34%   |
| 3.01-4.0   | 5         | 3.52%   |
| 7.01-8.0   | 1         | 0.7%    |
| 2.01-3.0   | 1         | 0.7%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 17.11%  |
| Chimei Innolux          | 24        | 15.79%  |
| LG Display              | 23        | 15.13%  |
| BOE                     | 18        | 11.84%  |
| Samsung Electronics     | 12        | 7.89%   |
| Apple                   | 12        | 7.89%   |
| Lenovo                  | 7         | 4.61%   |
| Sharp                   | 5         | 3.29%   |
| Chi Mei Optoelectronics | 4         | 2.63%   |
| CPT                     | 3         | 1.97%   |
| Dell                    | 2         | 1.32%   |
| CSO                     | 2         | 1.32%   |
| AOC                     | 2         | 1.32%   |
| Vizio                   | 1         | 0.66%   |
| ViewSonic               | 1         | 0.66%   |
| Toshiba                 | 1         | 0.66%   |
| Seiko/Epson             | 1         | 0.66%   |
| PANDA                   | 1         | 0.66%   |
| Panasonic               | 1         | 0.66%   |
| LGD                     | 1         | 0.66%   |
| LG Philips              | 1         | 0.66%   |
| HannStar                | 1         | 0.66%   |
| Goldstar                | 1         | 0.66%   |
| BenQ                    | 1         | 0.66%   |
| Ancor Communications    | 1         | 0.66%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 3.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 2.61%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 2         | 1.31%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 2         | 1.31%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 1.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 1.31%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 2         | 1.31%   |
| Apple Color LCD APPA014 2560x1600 286x179mm 13.3-inch                    | 2         | 1.31%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                     | 2         | 1.31%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 2         | 1.31%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                     | 2         | 1.31%   |
| Vizio L37 HD VIZ1300 1366x768 820x460mm 37.0-inch                        | 1         | 0.65%   |
| ViewSonic VA2445 SERIES VSC712E 1920x1080 521x293mm 23.5-inch            | 1         | 0.65%   |
| Toshiba TV TSB0206 1920x1080 886x498mm 40.0-inch                         | 1         | 0.65%   |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch                  | 1         | 0.65%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                  | 1         | 0.65%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                  | 1         | 0.65%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                  | 1         | 0.65%   |
| Sharp LCD Monitor SHP1420 1920x1080 294x165mm 13.3-inch                  | 1         | 0.65%   |
| Seiko/Epson LCD Monitor 1920x1080                                        | 1         | 0.65%   |
| Samsung Electronics S27D850 SAM0BC8 2560x1440 598x336mm 27.0-inch        | 1         | 0.65%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 480x270mm 21.7-inch        | 1         | 0.65%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch        | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC364D 1600x900 382x214mm 17.2-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 309x174mm 14.0-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SEC3041 1366x768 353x198mm 15.9-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch     | 1         | 0.65%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 1         | 0.65%   |
| Samsung Electronics C27F591 SAM0D36 1920x1080 600x340mm 27.2-inch        | 1         | 0.65%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 1         | 0.65%   |
| Panasonic VVX16T029D00 MEI96A2 2880x1620 344x193mm 15.5-inch             | 1         | 0.65%   |
| LGD LCD Monitor 1920x1080                                                | 1         | 0.65%   |
| LG Philips LCD Monitor LPLCD00 1680x1050 331x207mm 15.4-inch             | 1         | 0.65%   |
| LG Display LP156WH2-TLE1 LGDCF01 1366x768 344x194mm 15.5-inch            | 1         | 0.65%   |
| LG Display LP140WH2-TLA1 LGD0201 1366x768 310x174mm 14.0-inch            | 1         | 0.65%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD06AD 2560x1600 286x179mm 13.3-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD0599 1920x1080 309x174mm 14.0-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD057A 1920x1080 309x174mm 14.0-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD04FF 1920x1080 309x174mm 14.0-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD048A 1920x1080 276x156mm 12.5-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD0382 1600x900 309x174mm 14.0-inch              | 1         | 0.65%   |
| LG Display LCD Monitor LGD033C 1366x768 309x174mm 14.0-inch              | 1         | 0.65%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch              | 1         | 0.65%   |
| LG Display LCD Monitor LGD032C 1920x1080 344x194mm 15.5-inch             | 1         | 0.65%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 1         | 0.65%   |
| LG Display LCD Monitor LGD02E1 1600x900 382x215mm 17.3-inch              | 1         | 0.65%   |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch              | 1         | 0.65%   |
| LG Display LCD Monitor LGD027B 1600x900 382x215mm 17.3-inch              | 1         | 0.65%   |
| LG Display LCD Monitor LGD022C 1366x768 294x166mm 13.3-inch              | 1         | 0.65%   |
| Lenovo LEN T27h-20 LEN61EC 2560x1440 597x336mm 27.0-inch                 | 1         | 0.65%   |
| Lenovo LEN L28u-30 LEN65FA 3840x2160 621x341mm 27.9-inch                 | 1         | 0.65%   |
| Lenovo LCD Monitor LEN4067 1920x1200 367x230mm 17.1-inch                 | 1         | 0.65%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 52        | 35.86%  |
| 1920x1080 (FHD)    | 51        | 35.17%  |
| 1600x900 (HD+)     | 9         | 6.21%   |
| 1280x800 (WXGA)    | 8         | 5.52%   |
| 2560x1600          | 5         | 3.45%   |
| 1440x900 (WXGA+)   | 5         | 3.45%   |
| 3840x2160 (4K)     | 4         | 2.76%   |
| 2560x1440 (QHD)    | 3         | 2.07%   |
| 1920x1200 (WUXGA)  | 3         | 2.07%   |
| 1680x1050 (WSXGA+) | 2         | 1.38%   |
| 3840x2400          | 1         | 0.69%   |
| 3000x2000          | 1         | 0.69%   |
| 2880x1800          | 1         | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 61        | 40.4%   |
| 13      | 28        | 18.54%  |
| 14      | 19        | 12.58%  |
| 17      | 10        | 6.62%   |
| 27      | 8         | 5.3%    |
| 12      | 7         | 4.64%   |
| 11      | 6         | 3.97%   |
| 21      | 4         | 2.65%   |
| 23      | 2         | 1.32%   |
| Unknown | 2         | 1.32%   |
| 74      | 1         | 0.66%   |
| 37      | 1         | 0.66%   |
| 16      | 1         | 0.66%   |
| 10      | 1         | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 91        | 60.67%  |
| 201-300     | 30        | 20%     |
| 351-400     | 12        | 8%      |
| 501-600     | 6         | 4%      |
| 401-500     | 4         | 2.67%   |
| 601-700     | 3         | 2%      |
| Unknown     | 2         | 1.33%   |
| 801-900     | 1         | 0.67%   |
| 1501-2000   | 1         | 0.67%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 110       | 79.14%  |
| 16/10   | 24        | 17.27%  |
| 3/2     | 3         | 2.16%   |
| Unknown | 2         | 1.44%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 61        | 40.4%   |
| 81-90          | 35        | 23.18%  |
| 71-80          | 12        | 7.95%   |
| 301-350        | 8         | 5.3%    |
| 121-130        | 8         | 5.3%    |
| 61-70          | 7         | 4.64%   |
| 51-60          | 6         | 3.97%   |
| 201-250        | 5         | 3.31%   |
| 131-140        | 2         | 1.32%   |
| Unknown        | 2         | 1.32%   |
| More than 1000 | 1         | 0.66%   |
| 41-50          | 1         | 0.66%   |
| 151-200        | 1         | 0.66%   |
| 111-120        | 1         | 0.66%   |
| 501-1000       | 1         | 0.66%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 65        | 44.52%  |
| 101-120       | 54        | 36.99%  |
| 161-240       | 10        | 6.85%   |
| 51-100        | 9         | 6.16%   |
| More than 240 | 4         | 2.74%   |
| 1-50          | 2         | 1.37%   |
| Unknown       | 2         | 1.37%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 124       | 87.94%  |
| 2     | 10        | 7.09%   |
| 3     | 4         | 2.84%   |
| 0     | 3         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 75        | 32.61%  |
| Intel                             | 69        | 30%     |
| Qualcomm Atheros                  | 28        | 12.17%  |
| Broadcom                          | 25        | 10.87%  |
| Broadcom Limited                  | 8         | 3.48%   |
| TP-Link                           | 3         | 1.3%    |
| Sierra Wireless                   | 2         | 0.87%   |
| Ralink Technology                 | 2         | 0.87%   |
| Ralink                            | 2         | 0.87%   |
| MediaTek                          | 2         | 0.87%   |
| Hewlett-Packard                   | 2         | 0.87%   |
| Xiaomi                            | 1         | 0.43%   |
| Samsung Electronics               | 1         | 0.43%   |
| Qualcomm                          | 1         | 0.43%   |
| OPPO Electronics                  | 1         | 0.43%   |
| NEC Computers                     | 1         | 0.43%   |
| LSI                               | 1         | 0.43%   |
| Linksys                           | 1         | 0.43%   |
| Huawei Technologies               | 1         | 0.43%   |
| Google                            | 1         | 0.43%   |
| Ericsson Business Mobile Networks | 1         | 0.43%   |
| DisplayLink                       | 1         | 0.43%   |
| Attansic Technology               | 1         | 0.43%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 15.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 4.41%   |
| Intel Wi-Fi 6 AX200                                               | 9         | 3.31%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 2.21%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 2.21%   |
| Intel Wireless 8260                                               | 6         | 2.21%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 2.21%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 2.21%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5         | 1.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.84%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 4         | 1.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.47%   |
| Intel Wireless 7265                                               | 4         | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 4         | 1.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.47%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 4         | 1.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                       | 3         | 1.1%    |
| Intel Wireless 8265 / 8275                                        | 3         | 1.1%    |
| Intel Wireless 7260                                               | 3         | 1.1%    |
| Intel Wireless 3160                                               | 3         | 1.1%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 3         | 1.1%    |
| Intel Centrino Wireless-N 2230                                    | 3         | 1.1%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 3         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                     | 3         | 1.1%    |
| TP-Link 802.11ac WLAN Adapter                                     | 2         | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.74%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 2         | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 2         | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.74%   |
| Intel Wireless 3165                                               | 2         | 0.74%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.74%   |
| Intel Ethernet Connection I219-V                                  | 2         | 0.74%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.74%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.74%   |
| Intel Centrino Advanced-N 6200                                    | 2         | 0.74%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.74%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.74%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.74%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.37%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 1         | 0.37%   |
| Sierra Wireless EM7455                                            | 1         | 0.37%   |
| Sierra Wireless EM7305 Modem                                      | 1         | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 1         | 0.37%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 1         | 0.37%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.37%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.37%   |
| Realtek 802.11ac NIC                                              | 1         | 0.37%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.37%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.37%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 42.76%  |
| Realtek Semiconductor | 25        | 16.45%  |
| Qualcomm Atheros      | 24        | 15.79%  |
| Broadcom              | 22        | 14.47%  |
| Broadcom Limited      | 6         | 3.95%   |
| TP-Link               | 3         | 1.97%   |
| Sierra Wireless       | 2         | 1.32%   |
| Ralink Technology     | 2         | 1.32%   |
| Ralink                | 2         | 1.32%   |
| MEDIATEK              | 1         | 0.66%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 9         | 5.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 3.95%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 3.95%   |
| Intel Wireless 8260                                            | 6         | 3.95%   |
| Intel Wi-Fi 6 AX201                                            | 6         | 3.95%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 3.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.29%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 5         | 3.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 4         | 2.63%   |
| Intel Wireless 7265                                            | 4         | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 4         | 2.63%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 3         | 1.97%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.97%   |
| Intel Wireless 7260                                            | 3         | 1.97%   |
| Intel Wireless 3160                                            | 3         | 1.97%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 1.97%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 1.97%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 1.97%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 1.97%   |
| TP-Link 802.11ac WLAN Adapter                                  | 2         | 1.32%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.32%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 2         | 1.32%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 2         | 1.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 1.32%   |
| Intel Wireless 3165                                            | 2         | 1.32%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 2         | 1.32%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.32%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.32%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 1.32%   |
| Intel Centrino Advanced-N 6200                                 | 2         | 1.32%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.32%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.66%   |
| Sierra Wireless EM7455                                         | 1         | 0.66%   |
| Sierra Wireless EM7305 Modem                                   | 1         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 0.66%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 1         | 0.66%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.66%   |
| Realtek 802.11ac NIC                                           | 1         | 0.66%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.66%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.66%   |
| Ralink RT2800 802.11n PCI                                      | 1         | 0.66%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 0.66%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.66%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 1         | 0.66%   |
| Intel Ultimate N WiFi Link 5300                                | 1         | 0.66%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 1         | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 1         | 0.66%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 1         | 0.66%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.66%   |
| Intel Centrino Advanced-N 6235                                 | 1         | 0.66%   |
| Intel Centrino Advanced-N 6230 [Rainbow Peak]                  | 1         | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 1         | 0.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 1         | 0.66%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 0.66%   |
| Broadcom Limited BCM43228 802.11a/b/g/n                        | 1         | 0.66%   |
| Broadcom Limited BCM4311 802.11b/g WLAN                        | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 59        | 51.75%  |
| Intel                 | 23        | 20.18%  |
| Broadcom              | 11        | 9.65%   |
| Qualcomm Atheros      | 9         | 7.89%   |
| Broadcom Limited      | 2         | 1.75%   |
| Xiaomi                | 1         | 0.88%   |
| Samsung Electronics   | 1         | 0.88%   |
| Qualcomm              | 1         | 0.88%   |
| OPPO Electronics      | 1         | 0.88%   |
| MediaTek              | 1         | 0.88%   |
| LSI                   | 1         | 0.88%   |
| Linksys               | 1         | 0.88%   |
| Google                | 1         | 0.88%   |
| DisplayLink           | 1         | 0.88%   |
| Attansic Technology   | 1         | 0.88%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 41        | 35.65%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 12        | 10.43%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 4.35%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 4.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 3.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 3.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 3.48%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.74%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.74%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 1.74%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 1.74%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.87%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.87%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.87%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.87%   |
| Qualcomm Redmi Note 9S                                            | 1         | 0.87%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.87%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.87%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.87%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.87%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1         | 0.87%   |
| OPPO realme X50 5G                                                | 1         | 0.87%   |
| MediaTek Vodafone Smart N10                                       | 1         | 0.87%   |
| LSI ET-131x PCI-E Ethernet Controller                             | 1         | 0.87%   |
| Linksys Gigabit Ethernet Adapter                                  | 1         | 0.87%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.87%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.87%   |
| Intel Ethernet Connection I217-LM                                 | 1         | 0.87%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.87%   |
| Intel 82567LM Gigabit Network Connection                          | 1         | 0.87%   |
| Google Nexus/Pixel Device (tether)                                | 1         | 0.87%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 1         | 0.87%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.87%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 1         | 0.87%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1         | 0.87%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.87%   |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe          | 1         | 0.87%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express    | 1         | 0.87%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 1         | 0.87%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 140       | 55.34%  |
| Ethernet | 108       | 42.69%  |
| Modem    | 4         | 1.58%   |
| Unknown  | 1         | 0.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 119       | 85%     |
| Ethernet | 21        | 15%     |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 98        | 69.5%   |
| 1     | 41        | 29.08%  |
| 3     | 2         | 1.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 105       | 74.47%  |
| Yes  | 36        | 25.53%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 42.5%   |
| Realtek Semiconductor           | 14        | 11.67%  |
| Qualcomm Atheros Communications | 12        | 10%     |
| Apple                           | 12        | 10%     |
| Broadcom                        | 11        | 9.17%   |
| Lite-On Technology              | 5         | 4.17%   |
| Foxconn / Hon Hai               | 4         | 3.33%   |
| IMC Networks                    | 3         | 2.5%    |
| Dell                            | 2         | 1.67%   |
| Toshiba                         | 1         | 0.83%   |
| Realtek                         | 1         | 0.83%   |
| Ralink                          | 1         | 0.83%   |
| Qcom                            | 1         | 0.83%   |
| Hewlett-Packard                 | 1         | 0.83%   |
| Cambridge Silicon Radio         | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 22        | 18.33%  |
| Intel AX201 Bluetooth                               | 10        | 8.33%   |
| Intel AX200 Bluetooth                               | 9         | 7.5%    |
| Realtek Bluetooth Radio                             | 8         | 6.67%   |
| Apple Bluetooth Host Controller                     | 7         | 5.83%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 4.17%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 4.17%   |
| Apple Bluetooth USB Host Controller                 | 5         | 4.17%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.33%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 3.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 4         | 3.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 2.5%    |
| IMC Networks Bluetooth Radio                        | 2         | 1.67%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 1.67%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 2         | 1.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 1.67%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.83%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.83%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.83%   |
| Realtek Bluetooth Radio                             | 1         | 0.83%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.83%   |
| Qcom Broadcom Bluetooth USB                         | 1         | 0.83%   |
| Lite-On Wireless_Device                             | 1         | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.83%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.83%   |
| Lite-On Bluetooth Device                            | 1         | 0.83%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.83%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.83%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.83%   |
| IMC Networks BCM20702A0                             | 1         | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.83%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.83%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.83%   |
| Dell DW375 Bluetooth Module                         | 1         | 0.83%   |
| Dell Broadcom BCM20702A0 Bluetooth                  | 1         | 0.83%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.83%   |
| Broadcom HP Portable Valentine                      | 1         | 0.83%   |
| Broadcom BCM20702A0                                 | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 124       | 74.7%   |
| AMD                    | 19        | 11.45%  |
| Nvidia                 | 17        | 10.24%  |
| TEAC                   | 1         | 0.6%    |
| Logitech               | 1         | 0.6%    |
| JMTek                  | 1         | 0.6%    |
| GN Netcom              | 1         | 0.6%    |
| Generalplus Technology | 1         | 0.6%    |
| Corsair                | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 9.69%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 8.67%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 11        | 5.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 11        | 5.61%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 5.61%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 4.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 3.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 3.06%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 3.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 3.06%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 2.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 2.55%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 2.55%   |
| Intel CM238 HD Audio Controller                                                                   | 4         | 2.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 2.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 2.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.53%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 1.53%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 1.53%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.53%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 1.53%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.53%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 1.02%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 1.02%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 1.02%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 2         | 1.02%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 1.02%   |
| Intel Comet Lake PCH cAVS                                                                         | 2         | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 2         | 1.02%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.02%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.02%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 1.02%   |
| AMD FCH Azalia Controller                                                                         | 2         | 1.02%   |
| TEAC TASCAM iXR                                                                                   | 1         | 0.51%   |
| Nvidia stereo controller                                                                          | 1         | 0.51%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.51%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 1         | 0.51%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.51%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 1         | 0.51%   |
| Nvidia Audio device                                                                               | 1         | 0.51%   |
| Logitech H600 [Wireless Headset]                                                                  | 1         | 0.51%   |
| JMTek audio controller                                                                            | 1         | 0.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.51%   |
| Intel Crystal Well HD Audio Controller                                                            | 1         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 1         | 0.51%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.51%   |
| GN Netcom Jabra Link 380                                                                          | 1         | 0.51%   |
| Generalplus Technology Usb Audio Device                                                           | 1         | 0.51%   |
| Corsair Slipstream Multi-Device Receiver                                                          | 1         | 0.51%   |
| AMD Wrestler HDMI Audio                                                                           | 1         | 0.51%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 1         | 0.51%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.51%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.51%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.51%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.51%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 1         | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 31.37%  |
| SK Hynix            | 10        | 19.61%  |
| Micron Technology   | 8         | 15.69%  |
| Kingston            | 5         | 9.8%    |
| Unknown             | 2         | 3.92%   |
| Ramaxel Technology  | 2         | 3.92%   |
| Crucial             | 2         | 3.92%   |
| Toshiba             | 1         | 1.96%   |
| Qimonda             | 1         | 1.96%   |
| Kllisre             | 1         | 1.96%   |
| GSkill              | 1         | 1.96%   |
| A-DATA Technology   | 1         | 1.96%   |
| Unknown             | 1         | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s         | 3         | 5.66%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s        | 2         | 3.77%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s         | 2         | 3.77%   |
| Unknown RAM Module 4096MB Chip DDR4 2133MT/s                  | 1         | 1.89%   |
| Unknown RAM Module 1024MB SODIMM LPDDR4 2400MT/s              | 1         | 1.89%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s            | 1         | 1.89%   |
| Toshiba RAM 64T128020EDL2.5C2 4GB SODIMM 1066MT/s             | 1         | 1.89%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s        | 1         | 1.89%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s        | 1         | 1.89%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s        | 1         | 1.89%   |
| SK Hynix RAM HMAA2GS6CJR8N-XN 16384MB SODIMM DDR4 3200MT/s    | 1         | 1.89%   |
| SK Hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s        | 1         | 1.89%   |
| SK Hynix RAM HMA82GS6MFR8N-TF 16GB SODIMM DDR4 2133MT/s       | 1         | 1.89%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s        | 1         | 1.89%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s        | 1         | 1.89%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2133MT/s                | 1         | 1.89%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s         | 1         | 1.89%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s         | 1         | 1.89%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s      | 1         | 1.89%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s         | 1         | 1.89%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s         | 1         | 1.89%   |
| Samsung RAM M471B2873FHS-CF8 1024MB SODIMM DDR3 1067MT/s      | 1         | 1.89%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s        | 1         | 1.89%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s        | 1         | 1.89%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s   | 1         | 1.89%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s         | 1         | 1.89%   |
| Samsung RAM M4 70T5663EH3-CF7 2GB SODIMM DDR2 975MT/s         | 1         | 1.89%   |
| Ramaxel RAM RMT3170EF68F9W1600 4GB SODIMM DDR3 1600MT/s       | 1         | 1.89%   |
| Ramaxel RAM RMSA3310NA86H9F-2666 4GB SODIMM DDR4 2667MT/s     | 1         | 1.89%   |
| Qimonda RAM 64T256020EDL2.5C2 2GB SODIMM DDR2 2048MT/s        | 1         | 1.89%   |
| Micron RAM MT41K256M16LY 2GB SODIMM DDR3 1600MT/s             | 1         | 1.89%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                 | 1         | 1.89%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                 | 1         | 1.89%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s          | 1         | 1.89%   |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s    | 1         | 1.89%   |
| Micron RAM 4ATF51264HZ-2G6E3 4GB SODIMM DDR4 2667MT/s         | 1         | 1.89%   |
| Micron RAM 16JSF25664HZ-1G4F1 2GB SODIMM 1334MT/s             | 1         | 1.89%   |
| Micron RAM 16ATF2G64HZ-3G2J1 16GB SODIMM DDR4 3200MT/s        | 1         | 1.89%   |
| Kllisre RAM KRE-D3S1600M/8G 8192MB SODIMM DDR3 1600MT/s       | 1         | 1.89%   |
| Kingston RAM KHX2666C15S4/8G 8GB SODIMM DDR4 2667MT/s         | 1         | 1.89%   |
| Kingston RAM HP16D3LS1KBG/8G 8192MB SODIMM DDR3 1600MT/s      | 1         | 1.89%   |
| Kingston RAM ACR16D3LS1KFG/8G 8GB SODIMM DDR3 1600MT/s        | 1         | 1.89%   |
| Kingston RAM 9905700-070.A01G 16GB SODIMM DDR4 2667MT/s       | 1         | 1.89%   |
| Kingston RAM 9905700-026.A00G 8192MB SODIMM DDR4 2667MT/s     | 1         | 1.89%   |
| GSkill RAM F4-3200C22-8GRS 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.89%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s    | 1         | 1.89%   |
| Crucial RAM CT16G4SFD824A.C16FDD 16384MB SODIMM DDR4 2400MT/s | 1         | 1.89%   |
| A-DATA RAM AM1U16BC4P2-B19N 4GB SODIMM DDR3 1600MT/s          | 1         | 1.89%   |
| Unknown                                                       | 1         | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 20        | 51.28%  |
| DDR3   | 14        | 35.9%   |
| SDRAM  | 2         | 5.13%   |
| LPDDR4 | 2         | 5.13%   |
| DDR2   | 1         | 2.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 37        | 90.24%  |
| Row Of Chips | 2         | 4.88%   |
| Chip         | 2         | 4.88%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 15        | 31.91%  |
| 4096  | 14        | 29.79%  |
| 2048  | 9         | 19.15%  |
| 16384 | 7         | 14.89%  |
| 1024  | 2         | 4.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 1600  | 12        | 27.91%  |
| 2667  | 11        | 25.58%  |
| 3200  | 8         | 18.6%   |
| 2400  | 3         | 6.98%   |
| 2133  | 3         | 6.98%   |
| 4267  | 1         | 2.33%   |
| 4199  | 1         | 2.33%   |
| 2048  | 1         | 2.33%   |
| 1334  | 1         | 2.33%   |
| 1067  | 1         | 2.33%   |
| 1066  | 1         | 2.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 1         | 50%     |
| Brother Industries | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP Deskjet F4500 series | 1         | 50%     |
| Brother MFC-T800W       | 1         | 50%     |

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
| Chicony Electronics                    | 34        | 29.06%  |
| Realtek Semiconductor                  | 11        | 9.4%    |
| Microdia                               | 10        | 8.55%   |
| Apple                                  | 9         | 7.69%   |
| Acer                                   | 9         | 7.69%   |
| Quanta                                 | 8         | 6.84%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 5.98%   |
| Suyin                                  | 6         | 5.13%   |
| Sunplus Innovation Technology          | 5         | 4.27%   |
| Lenovo                                 | 4         | 3.42%   |
| IMC Networks                           | 3         | 2.56%   |
| Syntek                                 | 2         | 1.71%   |
| Luxvisions Innotech Limited            | 2         | 1.71%   |
| Lite-On Technology                     | 2         | 1.71%   |
| USB Camera                             | 1         | 0.85%   |
| Primax Electronics                     | 1         | 0.85%   |
| Logitech                               | 1         | 0.85%   |
| Importek                               | 1         | 0.85%   |
| 2M UVC CAMERA                          | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 8         | 6.84%   |
| Chicony HD WebCam                                   | 4         | 3.42%   |
| Apple FaceTime HD Camera                            | 4         | 3.42%   |
| Realtek Integrated_Webcam_HD                        | 3         | 2.56%   |
| Realtek HD WebCam                                   | 3         | 2.56%   |
| Quanta HP TrueVision HD Camera                      | 3         | 2.56%   |
| Chicony HP Truevision HD                            | 3         | 2.56%   |
| Chicony HP HD Webcam [Fixed]                        | 3         | 2.56%   |
| Acer Lenovo EasyCamera                              | 3         | 2.56%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 1.71%   |
| Suyin 1.3M HD WebCam                                | 2         | 1.71%   |
| Sunplus Laptop_Integrated_Webcam_HD                 | 2         | 1.71%   |
| Realtek USB2.0-Camera                               | 2         | 1.71%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 1.71%   |
| Microdia Integrated_Webcam_HD                       | 2         | 1.71%   |
| Lite-On Integrated Camera                           | 2         | 1.71%   |
| Lenovo Integrated Webcam                            | 2         | 1.71%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 2         | 1.71%   |
| Chicony USB2.0 Camera                               | 2         | 1.71%   |
| Chicony HP TrueVision HD Camera                     | 2         | 1.71%   |
| Apple iPhone 5/5C/5S/6/SE                           | 2         | 1.71%   |
| Apple FaceTime HD Camera (Built-in)                 | 2         | 1.71%   |
| USB Camera USB Camera                               | 1         | 0.85%   |
| Syntek Integrated Camera                            | 1         | 0.85%   |
| Syntek EasyCamera                                   | 1         | 0.85%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.85%   |
| Suyin Asus Integrated Webcam                        | 1         | 0.85%   |
| Sunplus Laptop_Integrated_Webcam_1.3M               | 1         | 0.85%   |
| Sunplus Laptop Integrated WebCam HD                 | 1         | 0.85%   |
| Sunplus 1.3M HD WebCam                              | 1         | 0.85%   |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.85%   |
| Realtek Integrated Webcam                           | 1         | 0.85%   |
| Realtek Integrated Camera                           | 1         | 0.85%   |
| Quanta ov9734_techfront_camera                      | 1         | 0.85%   |
| Quanta HP Webcam                                    | 1         | 0.85%   |
| Quanta HP TrueVision HD Webcam                      | 1         | 0.85%   |
| Quanta HD User Facing                               | 1         | 0.85%   |
| Quanta HD Camera                                    | 1         | 0.85%   |
| Primax Villem                                       | 1         | 0.85%   |
| Microdia Webcam Vitade AF                           | 1         | 0.85%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam      | 1         | 0.85%   |
| Microdia Laptop_Integrated_Webcam_FHD               | 1         | 0.85%   |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 0.85%   |
| Microdia Integrated Webcam                          | 1         | 0.85%   |
| Microdia AUKEY PCâW1                           | 1         | 0.85%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.85%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 0.85%   |
| Logitech HD Pro Webcam C920                         | 1         | 0.85%   |
| Lenovo Integrated Webcam [R5U877]                   | 1         | 0.85%   |
| Lenovo CNF7237&CNF7238                              | 1         | 0.85%   |
| Importek Webcam HD                                  | 1         | 0.85%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 0.85%   |
| Chicony VGA Webcam                                  | 1         | 0.85%   |
| Chicony USB 2.0 Camera                              | 1         | 0.85%   |
| Chicony TOSHIBA Web Camera - HD                     | 1         | 0.85%   |
| Chicony Integrated HP HD Webcam                     | 1         | 0.85%   |
| Chicony HP Wide Vision HD                           | 1         | 0.85%   |
| Chicony HP Webcam                                   | 1         | 0.85%   |
| Chicony HP Integrated Webcam                        | 1         | 0.85%   |
| Chicony HP HD Webcam                                | 1         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 42.42%  |
| Synaptics                  | 4         | 12.12%  |
| Upek                       | 3         | 9.09%   |
| Shenzhen Goodix Technology | 3         | 9.09%   |
| LighTuning Technology      | 3         | 9.09%   |
| AuthenTec                  | 3         | 9.09%   |
| STMicroelectronics         | 1         | 3.03%   |
| Focal-systems.Corp         | 1         | 3.03%   |
| Elan Microelectronics      | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 9.09%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 9.09%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 9.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 6.06%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 6.06%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 6.06%   |
| Shenzhen Goodix  FingerPrint Device                                        | 2         | 6.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 3.03%   |
| Validity Sensors VFS491                                                    | 1         | 3.03%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 3.03%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.03%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 3.03%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 3.03%   |
| Synaptics  WBDI                                                            | 1         | 3.03%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1         | 3.03%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 3.03%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 3.03%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 3.03%   |
| Elan ELAN:ARM-M4                                                           | 1         | 3.03%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 3.03%   |
| AuthenTec AES2810                                                          | 1         | 3.03%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 3.03%   |
| Unknown                                                                    | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 40%     |
| Alcor Micro | 2         | 40%     |
| Upek        | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 40%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 82        | 58.16%  |
| 1     | 47        | 33.33%  |
| 2     | 11        | 7.8%    |
| 3     | 1         | 0.71%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 33        | 44.59%  |
| Graphics card         | 11        | 14.86%  |
| Net/wireless          | 10        | 13.51%  |
| Multimedia controller | 8         | 10.81%  |
| Chipcard              | 5         | 6.76%   |
| Sound                 | 2         | 2.7%    |
| Net/ethernet          | 2         | 2.7%    |
| Storage               | 1         | 1.35%   |
| Camera                | 1         | 1.35%   |
| Bluetooth             | 1         | 1.35%   |

