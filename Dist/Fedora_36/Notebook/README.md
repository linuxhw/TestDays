Fedora 36 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 36.

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

Total: 999

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 5490               | [3ef6519b6d](https://linux-hardware.org/?probe=3ef6519b6d) | Sep 01, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [e4a4630b4e](https://linux-hardware.org/?probe=e4a4630b4e) | Sep 01, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [5ad5d3809b](https://linux-hardware.org/?probe=5ad5d3809b) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [b6b7c6dc62](https://linux-hardware.org/?probe=b6b7c6dc62) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [6b3c188071](https://linux-hardware.org/?probe=6b3c188071) | Sep 01, 2022 |
| Dell          | Inspiron 13 5310            | [b0d6660da8](https://linux-hardware.org/?probe=b0d6660da8) | Sep 01, 2022 |
| Dell          | Inspiron 3542               | [945ec7d987](https://linux-hardware.org/?probe=945ec7d987) | Sep 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [c86e73aed6](https://linux-hardware.org/?probe=c86e73aed6) | Sep 01, 2022 |
| ASUSTek       | X541UJ                      | [0cd33aa36a](https://linux-hardware.org/?probe=0cd33aa36a) | Aug 31, 2022 |
| Dell          | Latitude 7430               | [8876fb0448](https://linux-hardware.org/?probe=8876fb0448) | Aug 31, 2022 |
| Eluktronic... | MAG-15 2070                 | [d7fb373622](https://linux-hardware.org/?probe=d7fb373622) | Aug 31, 2022 |
| Dell          | Latitude E5570              | [91513d0ee3](https://linux-hardware.org/?probe=91513d0ee3) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | [b9d306c31b](https://linux-hardware.org/?probe=b9d306c31b) | Aug 31, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [c2d66050b5](https://linux-hardware.org/?probe=c2d66050b5) | Aug 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [71cd60f1b9](https://linux-hardware.org/?probe=71cd60f1b9) | Aug 30, 2022 |
| HP            | Laptop 15s-eq2xxx           | [d927e47d1f](https://linux-hardware.org/?probe=d927e47d1f) | Aug 30, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [30457b898c](https://linux-hardware.org/?probe=30457b898c) | Aug 30, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [7399a32997](https://linux-hardware.org/?probe=7399a32997) | Aug 30, 2022 |
| HP            | 255 G8 Notebook PC          | [c96e8a8254](https://linux-hardware.org/?probe=c96e8a8254) | Aug 30, 2022 |
| Dell          | G3 3579                     | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| HP            | Laptop 14-fq1xxx            | [8ea91d6b4b](https://linux-hardware.org/?probe=8ea91d6b4b) | Aug 30, 2022 |
| HP            | 250 G7 Notebook PC          | [96a56c7cb9](https://linux-hardware.org/?probe=96a56c7cb9) | Aug 30, 2022 |
| Dell          | Inspiron 15 5510            | [346eda373e](https://linux-hardware.org/?probe=346eda373e) | Aug 29, 2022 |
| Dell          | Inspiron 15 5510            | [ecdb2875da](https://linux-hardware.org/?probe=ecdb2875da) | Aug 29, 2022 |
| Dell          | Inspiron 5721               | [d483434965](https://linux-hardware.org/?probe=d483434965) | Aug 29, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [473daa5ce3](https://linux-hardware.org/?probe=473daa5ce3) | Aug 29, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c407e3a17c](https://linux-hardware.org/?probe=c407e3a17c) | Aug 29, 2022 |
| MSI           | Prestige 14Evo A11MO        | [22cf60f50b](https://linux-hardware.org/?probe=22cf60f50b) | Aug 29, 2022 |
| Infinix       | INBOOK X2                   | [02ae752ba2](https://linux-hardware.org/?probe=02ae752ba2) | Aug 29, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [f921aef61e](https://linux-hardware.org/?probe=f921aef61e) | Aug 29, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | [d82227c6d3](https://linux-hardware.org/?probe=d82227c6d3) | Aug 29, 2022 |
| Dell          | Precision 5750              | [2ee41b471e](https://linux-hardware.org/?probe=2ee41b471e) | Aug 28, 2022 |
| HUAWEI        | KLVL-WXXW                   | [829a45ed6f](https://linux-hardware.org/?probe=829a45ed6f) | Aug 28, 2022 |
| Google        | Eve                         | [4c83027c9a](https://linux-hardware.org/?probe=4c83027c9a) | Aug 28, 2022 |
| Dell          | Precision 5750              | [af9992756f](https://linux-hardware.org/?probe=af9992756f) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [589154a65e](https://linux-hardware.org/?probe=589154a65e) | Aug 28, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [8d17bfec23](https://linux-hardware.org/?probe=8d17bfec23) | Aug 28, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [af00be0ff8](https://linux-hardware.org/?probe=af00be0ff8) | Aug 28, 2022 |
| HP            | ProBook 650 G1              | [7738c266d6](https://linux-hardware.org/?probe=7738c266d6) | Aug 28, 2022 |
| Apple         | MacBookPro8,1               | [5efa863ca3](https://linux-hardware.org/?probe=5efa863ca3) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | [64cefbec58](https://linux-hardware.org/?probe=64cefbec58) | Aug 28, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [70b2e9f836](https://linux-hardware.org/?probe=70b2e9f836) | Aug 27, 2022 |
| Dell          | Inspiron 3442               | [46a68b981e](https://linux-hardware.org/?probe=46a68b981e) | Aug 27, 2022 |
| Apple         | MacBookAir6,2               | [0454b1e087](https://linux-hardware.org/?probe=0454b1e087) | Aug 27, 2022 |
| Acidanther... | MacBookPro12,1              | [9e48c5e245](https://linux-hardware.org/?probe=9e48c5e245) | Aug 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [559d6f0e42](https://linux-hardware.org/?probe=559d6f0e42) | Aug 27, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [f4dd9de519](https://linux-hardware.org/?probe=f4dd9de519) | Aug 27, 2022 |
| Acer          | Nitro AN515-57              | [8d314e1557](https://linux-hardware.org/?probe=8d314e1557) | Aug 27, 2022 |
| Lenovo        | G50-45 80E3                 | [be9921e0e0](https://linux-hardware.org/?probe=be9921e0e0) | Aug 27, 2022 |
| HP            | EliteBook 840 G5            | [7bd19ce9a1](https://linux-hardware.org/?probe=7bd19ce9a1) | Aug 27, 2022 |
| Exo           | Smart Serie L               | [5cbaef571b](https://linux-hardware.org/?probe=5cbaef571b) | Aug 27, 2022 |
| Acer          | Aspire VN7-592G             | [cec4df79eb](https://linux-hardware.org/?probe=cec4df79eb) | Aug 26, 2022 |
| HP            | ProBook 4530s               | [be1270c998](https://linux-hardware.org/?probe=be1270c998) | Aug 26, 2022 |
| ASUSTek       | X541NA                      | [4755f121e3](https://linux-hardware.org/?probe=4755f121e3) | Aug 26, 2022 |
| Lenovo        | ThinkPad T490 20N2005VMX    | [264a4fd9a7](https://linux-hardware.org/?probe=264a4fd9a7) | Aug 26, 2022 |
| Dell          | Inspiron 3593               | [c3ae4b86ac](https://linux-hardware.org/?probe=c3ae4b86ac) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| HP            | ENVY Laptop 13-aq1xxx       | [095ecf5f87](https://linux-hardware.org/?probe=095ecf5f87) | Aug 25, 2022 |
| MSI           | Modern 14 A10RAS            | [af216b7b4a](https://linux-hardware.org/?probe=af216b7b4a) | Aug 25, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [2b52864870](https://linux-hardware.org/?probe=2b52864870) | Aug 25, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [9f3be0c9b5](https://linux-hardware.org/?probe=9f3be0c9b5) | Aug 25, 2022 |
| HP            | Pavilion dv6                | [7fd7791035](https://linux-hardware.org/?probe=7fd7791035) | Aug 24, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [4378f177a8](https://linux-hardware.org/?probe=4378f177a8) | Aug 24, 2022 |
| HP            | Laptop 15s-fq2xxx           | [f8213e35a4](https://linux-hardware.org/?probe=f8213e35a4) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | [f9090c46a9](https://linux-hardware.org/?probe=f9090c46a9) | Aug 24, 2022 |
| GPU Compan... | GWTC116-2                   | [ac93dd480f](https://linux-hardware.org/?probe=ac93dd480f) | Aug 24, 2022 |
| ASUSTek       | T100HAN                     | [9438c7bb11](https://linux-hardware.org/?probe=9438c7bb11) | Aug 23, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [1e79d17c85](https://linux-hardware.org/?probe=1e79d17c85) | Aug 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | [efc85efba2](https://linux-hardware.org/?probe=efc85efba2) | Aug 23, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [33c24103bf](https://linux-hardware.org/?probe=33c24103bf) | Aug 23, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | [1b1c9cb460](https://linux-hardware.org/?probe=1b1c9cb460) | Aug 23, 2022 |
| Lenovo        | ThinkPad T470 20HDCTO1WW    | [2e88f854f8](https://linux-hardware.org/?probe=2e88f854f8) | Aug 23, 2022 |
| Dell          | Inspiron 5567               | [7b0f03259b](https://linux-hardware.org/?probe=7b0f03259b) | Aug 23, 2022 |
| Dell          | XPS L421X                   | [80a474140e](https://linux-hardware.org/?probe=80a474140e) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [a6726b8439](https://linux-hardware.org/?probe=a6726b8439) | Aug 22, 2022 |
| Aquarius      | Cmp NS765                   | [991487a61b](https://linux-hardware.org/?probe=991487a61b) | Aug 22, 2022 |
| Apple         | MacBook9,1                  | [aff9259c2c](https://linux-hardware.org/?probe=aff9259c2c) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | [f25926e1fa](https://linux-hardware.org/?probe=f25926e1fa) | Aug 22, 2022 |
| Apple         | MacBookPro5,5               | [784c6d89a6](https://linux-hardware.org/?probe=784c6d89a6) | Aug 22, 2022 |
| Apple         | MacBookPro11,2              | [9856ca2463](https://linux-hardware.org/?probe=9856ca2463) | Aug 21, 2022 |
| Acer          | TravelMate P215-52G         | [1d36fcbc9f](https://linux-hardware.org/?probe=1d36fcbc9f) | Aug 21, 2022 |
| HP            | Compaq 15                   | [c2bdac6148](https://linux-hardware.org/?probe=c2bdac6148) | Aug 21, 2022 |
| Acer          | Aspire E1-522               | [f4f0162d9a](https://linux-hardware.org/?probe=f4f0162d9a) | Aug 21, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [98b92cfe3a](https://linux-hardware.org/?probe=98b92cfe3a) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [390e67b458](https://linux-hardware.org/?probe=390e67b458) | Aug 21, 2022 |
| Acer          | Popcorn                     | [1c3d0d6b87](https://linux-hardware.org/?probe=1c3d0d6b87) | Aug 21, 2022 |
| HUAWEI        | EMD-WXX                     | [1ee66f2c65](https://linux-hardware.org/?probe=1ee66f2c65) | Aug 20, 2022 |
| HP            | ENVY Notebook               | [7d790e2b4d](https://linux-hardware.org/?probe=7d790e2b4d) | Aug 20, 2022 |
| HONOR         | NBD-WXX9                    | [1fdf41de8b](https://linux-hardware.org/?probe=1fdf41de8b) | Aug 20, 2022 |
| Dell          | Latitude E6430              | [c7a98ce916](https://linux-hardware.org/?probe=c7a98ce916) | Aug 20, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZE... | [8dd3a87210](https://linux-hardware.org/?probe=8dd3a87210) | Aug 20, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [93c259f492](https://linux-hardware.org/?probe=93c259f492) | Aug 20, 2022 |
| ASUSTek       | Zephyrus S GX531GX_GX531... | [0041774402](https://linux-hardware.org/?probe=0041774402) | Aug 20, 2022 |
| HP            | ProBook 655 G1              | [e37e59a165](https://linux-hardware.org/?probe=e37e59a165) | Aug 20, 2022 |
| Dell          | Inspiron M5010              | [266f9fc41d](https://linux-hardware.org/?probe=266f9fc41d) | Aug 19, 2022 |
| Fujitsu       | LIFEBOOK UH552              | [ad8ec93f74](https://linux-hardware.org/?probe=ad8ec93f74) | Aug 19, 2022 |
| Dell          | Inspiron 5490               | [98f795ee5f](https://linux-hardware.org/?probe=98f795ee5f) | Aug 19, 2022 |
| HUAWEI        | EMD-WXX                     | [9c4217c76b](https://linux-hardware.org/?probe=9c4217c76b) | Aug 19, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [81be616c6b](https://linux-hardware.org/?probe=81be616c6b) | Aug 19, 2022 |
| Apple         | MacBook6,1                  | [f7703b1b38](https://linux-hardware.org/?probe=f7703b1b38) | Aug 19, 2022 |
| ASUSTek       | K45A                        | [b007d7ae1d](https://linux-hardware.org/?probe=b007d7ae1d) | Aug 18, 2022 |
| Lenovo        | ThinkPad E520 1143CWG       | [bc6f3f891a](https://linux-hardware.org/?probe=bc6f3f891a) | Aug 18, 2022 |
| HP            | ProBook 450 G5              | [68697e720d](https://linux-hardware.org/?probe=68697e720d) | Aug 18, 2022 |
| Acidanther... | MacBookPro12,1              | [6afa5c842e](https://linux-hardware.org/?probe=6afa5c842e) | Aug 18, 2022 |
| Acer          | Aspire A515-45              | [9e48793165](https://linux-hardware.org/?probe=9e48793165) | Aug 18, 2022 |
| Acer          | Aspire E5-573               | [1815c3a2f2](https://linux-hardware.org/?probe=1815c3a2f2) | Aug 17, 2022 |
| Lenovo        | ThinkPad X240 20ALA0AHRT    | [cfc3d5853c](https://linux-hardware.org/?probe=cfc3d5853c) | Aug 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7f3311afd4](https://linux-hardware.org/?probe=7f3311afd4) | Aug 17, 2022 |
| ASUSTek       | K45A                        | [cbbc0ff58a](https://linux-hardware.org/?probe=cbbc0ff58a) | Aug 17, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [8aea7a68ee](https://linux-hardware.org/?probe=8aea7a68ee) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f1d6bc684c](https://linux-hardware.org/?probe=f1d6bc684c) | Aug 17, 2022 |
| MSI           | Modern 14 B11SBL            | [ad56f2a352](https://linux-hardware.org/?probe=ad56f2a352) | Aug 17, 2022 |
| Lenovo        | ThinkPad T480s 20L70044A... | [f90559618b](https://linux-hardware.org/?probe=f90559618b) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [26f646cca0](https://linux-hardware.org/?probe=26f646cca0) | Aug 17, 2022 |
| Eluktronic... | MAX-17                      | [b0aec6f095](https://linux-hardware.org/?probe=b0aec6f095) | Aug 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [3b35e8e9da](https://linux-hardware.org/?probe=3b35e8e9da) | Aug 17, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [78ff8418f9](https://linux-hardware.org/?probe=78ff8418f9) | Aug 17, 2022 |
| MSI           | Delta 15 A5EFK              | [4b165c8f79](https://linux-hardware.org/?probe=4b165c8f79) | Aug 17, 2022 |
| HP            | EliteBook 8460p             | [98b5311ef6](https://linux-hardware.org/?probe=98b5311ef6) | Aug 17, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [0793e37f62](https://linux-hardware.org/?probe=0793e37f62) | Aug 17, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1b12b01004](https://linux-hardware.org/?probe=1b12b01004) | Aug 16, 2022 |
| Acer          | Aspire A715-42G             | [fbeff3bff5](https://linux-hardware.org/?probe=fbeff3bff5) | Aug 16, 2022 |
| MSI           | GT72S 6QE                   | [20121e68c8](https://linux-hardware.org/?probe=20121e68c8) | Aug 16, 2022 |
| Acer          | Aspire E5-573               | [d3bd05f20b](https://linux-hardware.org/?probe=d3bd05f20b) | Aug 16, 2022 |
| HP            | Laptop 17-by0xxx            | [59db95ffee](https://linux-hardware.org/?probe=59db95ffee) | Aug 16, 2022 |
| ASUSTek       | X453MA                      | [2b63761318](https://linux-hardware.org/?probe=2b63761318) | Aug 16, 2022 |
| Lenovo        | ThinkBook Plus 20TG         | [1f39fbc5a8](https://linux-hardware.org/?probe=1f39fbc5a8) | Aug 16, 2022 |
| Panasonic     | CFMX4-1                     | [01074aea14](https://linux-hardware.org/?probe=01074aea14) | Aug 16, 2022 |
| ASUSTek       | X453MA                      | [fa2c1b6a14](https://linux-hardware.org/?probe=fa2c1b6a14) | Aug 15, 2022 |
| HP            | Pavilion TS 15              | [22194522c7](https://linux-hardware.org/?probe=22194522c7) | Aug 15, 2022 |
| Acer          | Aspire A515-51G             | [9ee5f23f82](https://linux-hardware.org/?probe=9ee5f23f82) | Aug 15, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [d9f8a6ea69](https://linux-hardware.org/?probe=d9f8a6ea69) | Aug 15, 2022 |
| Apple         | MacBookPro10,1              | [c4738a316c](https://linux-hardware.org/?probe=c4738a316c) | Aug 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [d333f2698e](https://linux-hardware.org/?probe=d333f2698e) | Aug 15, 2022 |
| Notebook      | N15_17RD                    | [eef224fc6b](https://linux-hardware.org/?probe=eef224fc6b) | Aug 15, 2022 |
| Lenovo        | V110-15ISK 80TL             | [757de6f4df](https://linux-hardware.org/?probe=757de6f4df) | Aug 15, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [4f73fd7cf8](https://linux-hardware.org/?probe=4f73fd7cf8) | Aug 15, 2022 |
| Avell High... | A70 HYB                     | [c0e0f2d0a4](https://linux-hardware.org/?probe=c0e0f2d0a4) | Aug 15, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [e09e349f03](https://linux-hardware.org/?probe=e09e349f03) | Aug 15, 2022 |
| Sony          | VPCS131FM                   | [22e32938e6](https://linux-hardware.org/?probe=22e32938e6) | Aug 14, 2022 |
| Toshiba       | TECRA R940                  | [f7a6618519](https://linux-hardware.org/?probe=f7a6618519) | Aug 14, 2022 |
| Dell          | XPS 15 9500                 | [08ef9ef965](https://linux-hardware.org/?probe=08ef9ef965) | Aug 14, 2022 |
| Lenovo        | ThinkPad T430 2349V4B       | [0f919e20c7](https://linux-hardware.org/?probe=0f919e20c7) | Aug 14, 2022 |
| UNOWHY        | Y13G010S4EI                 | [b7352cd745](https://linux-hardware.org/?probe=b7352cd745) | Aug 14, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [7209cc1bd4](https://linux-hardware.org/?probe=7209cc1bd4) | Aug 14, 2022 |
| Dell          | XPS 15 9550                 | [ad3ad84c75](https://linux-hardware.org/?probe=ad3ad84c75) | Aug 14, 2022 |
| Apple         | MacBookPro5,5               | [76483c9f78](https://linux-hardware.org/?probe=76483c9f78) | Aug 14, 2022 |
| AXDIA Inte... | WINPAD V10                  | [a44a9b065b](https://linux-hardware.org/?probe=a44a9b065b) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [a533aea5e5](https://linux-hardware.org/?probe=a533aea5e5) | Aug 14, 2022 |
| Dell          | Inspiron 13 5320            | [cee0d5a717](https://linux-hardware.org/?probe=cee0d5a717) | Aug 14, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [d5862f21f5](https://linux-hardware.org/?probe=d5862f21f5) | Aug 14, 2022 |
| Unknown       | Unknown                     | [dbf529a586](https://linux-hardware.org/?probe=dbf529a586) | Aug 14, 2022 |
| HP            | ENVY Laptop 17-ch0xxx       | [ca9974d27e](https://linux-hardware.org/?probe=ca9974d27e) | Aug 14, 2022 |
| Acer          | Aspire E5-521               | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| HP            | 14                          | [92172385ef](https://linux-hardware.org/?probe=92172385ef) | Aug 13, 2022 |
| Dell          | G3 3590                     | [fbe948e194](https://linux-hardware.org/?probe=fbe948e194) | Aug 13, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [7af785fc65](https://linux-hardware.org/?probe=7af785fc65) | Aug 13, 2022 |
| Dell          | XPS 15 9510                 | [3cb2744dbe](https://linux-hardware.org/?probe=3cb2744dbe) | Aug 12, 2022 |
| HP            | ProBook 6570b               | [d67ec558d4](https://linux-hardware.org/?probe=d67ec558d4) | Aug 12, 2022 |
| HP            | ProBook 440 G7              | [ee57cf772f](https://linux-hardware.org/?probe=ee57cf772f) | Aug 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [a7cdb45aa6](https://linux-hardware.org/?probe=a7cdb45aa6) | Aug 12, 2022 |
| MSI           | MS-16F1                     | [0a28da4f53](https://linux-hardware.org/?probe=0a28da4f53) | Aug 12, 2022 |
| HP            | Pavilion 17                 | [25a07691ec](https://linux-hardware.org/?probe=25a07691ec) | Aug 12, 2022 |
| Sony          | SVT15115CXS                 | [f7915ecf99](https://linux-hardware.org/?probe=f7915ecf99) | Aug 12, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [1604d7a824](https://linux-hardware.org/?probe=1604d7a824) | Aug 11, 2022 |
| Dell          | Latitude E6420              | [bd610e8bd8](https://linux-hardware.org/?probe=bd610e8bd8) | Aug 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [26b1a32b84](https://linux-hardware.org/?probe=26b1a32b84) | Aug 11, 2022 |
| Acer          | Predator PH317-53           | [8578e9a77a](https://linux-hardware.org/?probe=8578e9a77a) | Aug 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [05042a439b](https://linux-hardware.org/?probe=05042a439b) | Aug 11, 2022 |
| AZW           | SEi                         | [fb26f11a19](https://linux-hardware.org/?probe=fb26f11a19) | Aug 11, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [15488377fb](https://linux-hardware.org/?probe=15488377fb) | Aug 10, 2022 |
| Dell          | XPS 13 7390                 | [149d92cd3e](https://linux-hardware.org/?probe=149d92cd3e) | Aug 10, 2022 |
| HP            | EliteBook 8460p             | [fe464db60d](https://linux-hardware.org/?probe=fe464db60d) | Aug 10, 2022 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [4c3d230572](https://linux-hardware.org/?probe=4c3d230572) | Aug 10, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [5484873fd7](https://linux-hardware.org/?probe=5484873fd7) | Aug 10, 2022 |
| Lenovo        | Z40-70 20366                | [2378dda760](https://linux-hardware.org/?probe=2378dda760) | Aug 10, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | [21044cebb3](https://linux-hardware.org/?probe=21044cebb3) | Aug 10, 2022 |
| HUAWEI        | MACH-WX9                    | [18f9226bc0](https://linux-hardware.org/?probe=18f9226bc0) | Aug 09, 2022 |
| Timi          | TM1701                      | [676fc52004](https://linux-hardware.org/?probe=676fc52004) | Aug 09, 2022 |
| MSI           | Prestige 15 A10SC           | [9471547f71](https://linux-hardware.org/?probe=9471547f71) | Aug 09, 2022 |
| HUAWEI        | CREM-WXX9                   | [1a95dd7974](https://linux-hardware.org/?probe=1a95dd7974) | Aug 09, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [1c9cd79646](https://linux-hardware.org/?probe=1c9cd79646) | Aug 09, 2022 |
| ASUSTek       | UX430UAR                    | [e11856fcbc](https://linux-hardware.org/?probe=e11856fcbc) | Aug 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [dee5c21fb7](https://linux-hardware.org/?probe=dee5c21fb7) | Aug 09, 2022 |
| Dell          | Precision 5510              | [02dd64eff3](https://linux-hardware.org/?probe=02dd64eff3) | Aug 08, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [9855f862c2](https://linux-hardware.org/?probe=9855f862c2) | Aug 08, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e0403fe18f](https://linux-hardware.org/?probe=e0403fe18f) | Aug 08, 2022 |
| Lenovo        | ThinkPad X270 20HMS2R900    | [30a447f95c](https://linux-hardware.org/?probe=30a447f95c) | Aug 07, 2022 |
| HP            | Laptop 15-da0xxx            | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| Alienware     | x17 R2                      | [4e7fe87198](https://linux-hardware.org/?probe=4e7fe87198) | Aug 07, 2022 |
| Acer          | Aspire 7741                 | [bc1daa0005](https://linux-hardware.org/?probe=bc1daa0005) | Aug 07, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [9d837de022](https://linux-hardware.org/?probe=9d837de022) | Aug 07, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [438f5cce2a](https://linux-hardware.org/?probe=438f5cce2a) | Aug 07, 2022 |
| Toshiba       | Satellite Pro L300D         | [b3ed30ac52](https://linux-hardware.org/?probe=b3ed30ac52) | Aug 07, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [699bd44c36](https://linux-hardware.org/?probe=699bd44c36) | Aug 07, 2022 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [572cb48d3c](https://linux-hardware.org/?probe=572cb48d3c) | Aug 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7dc1825a38](https://linux-hardware.org/?probe=7dc1825a38) | Aug 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [0a6068ab6b](https://linux-hardware.org/?probe=0a6068ab6b) | Aug 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8f7a78b973](https://linux-hardware.org/?probe=8f7a78b973) | Aug 06, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [2eb53b5701](https://linux-hardware.org/?probe=2eb53b5701) | Aug 06, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [157da4bcd2](https://linux-hardware.org/?probe=157da4bcd2) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| HP            | Laptop 17-by4xxx            | [7867c6d24c](https://linux-hardware.org/?probe=7867c6d24c) | Aug 05, 2022 |
| Acer          | Aspire 7741                 | [eae703cf6f](https://linux-hardware.org/?probe=eae703cf6f) | Aug 05, 2022 |
| Acer          | Aspire A515-51              | [6c5e2de730](https://linux-hardware.org/?probe=6c5e2de730) | Aug 05, 2022 |
| HP            | ZBook 15 G3                 | [d59939b336](https://linux-hardware.org/?probe=d59939b336) | Aug 05, 2022 |
| Acer          | Aspire V3-572               | [dadff5cef8](https://linux-hardware.org/?probe=dadff5cef8) | Aug 05, 2022 |
| Gateway       | NE56R                       | [44de22f108](https://linux-hardware.org/?probe=44de22f108) | Aug 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34604... | [ec2efe1636](https://linux-hardware.org/?probe=ec2efe1636) | Aug 04, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [503200514f](https://linux-hardware.org/?probe=503200514f) | Aug 04, 2022 |
| MSI           | Modern 14 A10M              | [f8a0b1d6e6](https://linux-hardware.org/?probe=f8a0b1d6e6) | Aug 04, 2022 |
| HP            | Snappy                      | [d5e91bd56c](https://linux-hardware.org/?probe=d5e91bd56c) | Aug 04, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [fcef4276cb](https://linux-hardware.org/?probe=fcef4276cb) | Aug 03, 2022 |
| Gateway       | NV55C                       | [cc3c8d23e4](https://linux-hardware.org/?probe=cc3c8d23e4) | Aug 03, 2022 |
| HP            | Snappy                      | [0a73175862](https://linux-hardware.org/?probe=0a73175862) | Aug 03, 2022 |
| HP            | Laptop 17-by4xxx            | [711cf515aa](https://linux-hardware.org/?probe=711cf515aa) | Aug 03, 2022 |
| ASUSTek       | GL552VW                     | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Dell          | Inspiron 3521               | [b947e19278](https://linux-hardware.org/?probe=b947e19278) | Aug 02, 2022 |
| HP            | ProBook 650 G8 Notebook ... | [1b11fecca3](https://linux-hardware.org/?probe=1b11fecca3) | Aug 02, 2022 |
| Lenovo        | ThinkPad X220 4290KJ6       | [ef5ee2a01e](https://linux-hardware.org/?probe=ef5ee2a01e) | Aug 02, 2022 |
| HP            | Laptop 17-cp0xxx            | [492d014205](https://linux-hardware.org/?probe=492d014205) | Aug 02, 2022 |
| Dell          | Inspiron 5580               | [49d857e7bf](https://linux-hardware.org/?probe=49d857e7bf) | Aug 02, 2022 |
| Notebook      | NS50_70MU                   | [35cb4f8526](https://linux-hardware.org/?probe=35cb4f8526) | Aug 02, 2022 |
| Lenovo        | ThinkPad T430 2347AP9       | [b4d00ecb36](https://linux-hardware.org/?probe=b4d00ecb36) | Aug 02, 2022 |
| LG Electro... | 14Z990-V.AR52A2             | [6a1b44dfe0](https://linux-hardware.org/?probe=6a1b44dfe0) | Aug 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 8... | [a67d881d6f](https://linux-hardware.org/?probe=a67d881d6f) | Aug 02, 2022 |
| HP            | ProBook 4540s               | [c96c493e64](https://linux-hardware.org/?probe=c96c493e64) | Aug 02, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [2abfab93cb](https://linux-hardware.org/?probe=2abfab93cb) | Aug 02, 2022 |
| ASUSTek       | X750JN                      | [b321cd29a8](https://linux-hardware.org/?probe=b321cd29a8) | Aug 02, 2022 |
| Dell          | Precision 5530              | [a5177f0edb](https://linux-hardware.org/?probe=a5177f0edb) | Aug 02, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [3a496f366f](https://linux-hardware.org/?probe=3a496f366f) | Aug 01, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [16a3f81537](https://linux-hardware.org/?probe=16a3f81537) | Aug 01, 2022 |
| Dell          | Latitude D620               | [f378606941](https://linux-hardware.org/?probe=f378606941) | Aug 01, 2022 |
| HONOR         | NBR-WAX9                    | [e9fcbc7798](https://linux-hardware.org/?probe=e9fcbc7798) | Aug 01, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [c79c2bd215](https://linux-hardware.org/?probe=c79c2bd215) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [d1ae6a188c](https://linux-hardware.org/?probe=d1ae6a188c) | Jul 31, 2022 |
| HP            | Laptop 15s-eq0xxx           | [bce4496b78](https://linux-hardware.org/?probe=bce4496b78) | Jul 31, 2022 |
| HP            | Laptop 15s-eq2xxx           | [fc1b36d062](https://linux-hardware.org/?probe=fc1b36d062) | Jul 31, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [0f38b878b5](https://linux-hardware.org/?probe=0f38b878b5) | Jul 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [4b9354d287](https://linux-hardware.org/?probe=4b9354d287) | Jul 31, 2022 |
| HP            | Pavilion g6                 | [5867423d27](https://linux-hardware.org/?probe=5867423d27) | Jul 31, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [b8daa2d973](https://linux-hardware.org/?probe=b8daa2d973) | Jul 30, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [85208906cd](https://linux-hardware.org/?probe=85208906cd) | Jul 30, 2022 |
| HP            | EliteBook 8570w             | [1876d4e53d](https://linux-hardware.org/?probe=1876d4e53d) | Jul 30, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [8a472804e4](https://linux-hardware.org/?probe=8a472804e4) | Jul 30, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0359549c36](https://linux-hardware.org/?probe=0359549c36) | Jul 30, 2022 |
| Dell          | Inspiron M5010              | [bd4cf45b33](https://linux-hardware.org/?probe=bd4cf45b33) | Jul 30, 2022 |
| Acer          | Aspire A715-41G             | [3881e3998f](https://linux-hardware.org/?probe=3881e3998f) | Jul 30, 2022 |
| Acer          | Nitro AN515-55              | [b279b1558f](https://linux-hardware.org/?probe=b279b1558f) | Jul 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [320bc76144](https://linux-hardware.org/?probe=320bc76144) | Jul 30, 2022 |
| Dell          | Latitude E6520              | [0a7e1cdcaf](https://linux-hardware.org/?probe=0a7e1cdcaf) | Jul 30, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [e5e5cc4bbc](https://linux-hardware.org/?probe=e5e5cc4bbc) | Jul 29, 2022 |
| HP            | Victus by Gaming Laptop ... | [8d729c2a6b](https://linux-hardware.org/?probe=8d729c2a6b) | Jul 29, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [cd5aa49da7](https://linux-hardware.org/?probe=cd5aa49da7) | Jul 29, 2022 |
| Lenovo        | Yoga S740-14IIL 81RM        | [a308d89f1f](https://linux-hardware.org/?probe=a308d89f1f) | Jul 29, 2022 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [486ef751f0](https://linux-hardware.org/?probe=486ef751f0) | Jul 29, 2022 |
| Dell          | XPS 15 9560                 | [40ba0a0b07](https://linux-hardware.org/?probe=40ba0a0b07) | Jul 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [3986399fe4](https://linux-hardware.org/?probe=3986399fe4) | Jul 29, 2022 |
| Lenovo        | ThinkPad X240 20AMS28505    | [f159c45adf](https://linux-hardware.org/?probe=f159c45adf) | Jul 29, 2022 |
| Dell          | Inspiron 7460               | [9f3420ac40](https://linux-hardware.org/?probe=9f3420ac40) | Jul 29, 2022 |
| HUAWEI        | WRT-WX9                     | [ed09406e6c](https://linux-hardware.org/?probe=ed09406e6c) | Jul 28, 2022 |
| HP            | EliteBook 820 G3            | [a96c616d62](https://linux-hardware.org/?probe=a96c616d62) | Jul 28, 2022 |
| HP            | 348 G4                      | [034e49f6dc](https://linux-hardware.org/?probe=034e49f6dc) | Jul 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [238fa8aa34](https://linux-hardware.org/?probe=238fa8aa34) | Jul 28, 2022 |
| Acer          | Aspire A515-45              | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [066e5eb95d](https://linux-hardware.org/?probe=066e5eb95d) | Jul 28, 2022 |
| ASUSTek       | X750JN                      | [58fe3e4ae8](https://linux-hardware.org/?probe=58fe3e4ae8) | Jul 28, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [1bc8715e4e](https://linux-hardware.org/?probe=1bc8715e4e) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c68abe4e1a](https://linux-hardware.org/?probe=c68abe4e1a) | Jul 27, 2022 |
| Clevo         | M570TU                      | [b1f3c16be7](https://linux-hardware.org/?probe=b1f3c16be7) | Jul 27, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [e3fff7dcf4](https://linux-hardware.org/?probe=e3fff7dcf4) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [c1ab099582](https://linux-hardware.org/?probe=c1ab099582) | Jul 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f7d226a34a](https://linux-hardware.org/?probe=f7d226a34a) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [b690b57222](https://linux-hardware.org/?probe=b690b57222) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | [af6e67c798](https://linux-hardware.org/?probe=af6e67c798) | Jul 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [2773e9510b](https://linux-hardware.org/?probe=2773e9510b) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [90b6fd9754](https://linux-hardware.org/?probe=90b6fd9754) | Jul 27, 2022 |
| HP            | Laptop 15s-eq2xxx           | [1af666a847](https://linux-hardware.org/?probe=1af666a847) | Jul 27, 2022 |
| ASUSTek       | X750JN                      | [a4f3fc8ddd](https://linux-hardware.org/?probe=a4f3fc8ddd) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [c2fc2235eb](https://linux-hardware.org/?probe=c2fc2235eb) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [f18835e5a1](https://linux-hardware.org/?probe=f18835e5a1) | Jul 27, 2022 |
| HP            | Notebook                    | [f85df4e2d5](https://linux-hardware.org/?probe=f85df4e2d5) | Jul 26, 2022 |
| Dell          | Latitude E6520              | [b7436c1d3d](https://linux-hardware.org/?probe=b7436c1d3d) | Jul 26, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [0c145b1409](https://linux-hardware.org/?probe=0c145b1409) | Jul 25, 2022 |
| Dell          | Latitude 7320               | [83301910d0](https://linux-hardware.org/?probe=83301910d0) | Jul 25, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [52d58f31bb](https://linux-hardware.org/?probe=52d58f31bb) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [d3ac2d72dd](https://linux-hardware.org/?probe=d3ac2d72dd) | Jul 25, 2022 |
| ASUSTek       | K55VJ                       | [7c0ae7deec](https://linux-hardware.org/?probe=7c0ae7deec) | Jul 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [2db0d89beb](https://linux-hardware.org/?probe=2db0d89beb) | Jul 25, 2022 |
| Dell          | Latitude E6520              | [0675bbd9d0](https://linux-hardware.org/?probe=0675bbd9d0) | Jul 25, 2022 |
| Aquarius      | Cmp NS765                   | [9c9200701e](https://linux-hardware.org/?probe=9c9200701e) | Jul 24, 2022 |
| Dell          | Latitude E5420              | [b298e3bffa](https://linux-hardware.org/?probe=b298e3bffa) | Jul 24, 2022 |
| HP            | Notebook                    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| Dell          | Latitude E6520              | [b5d9fa066a](https://linux-hardware.org/?probe=b5d9fa066a) | Jul 24, 2022 |
| Lenovo        | ThinkPad T590 20N5S4R800    | [60dd75eca9](https://linux-hardware.org/?probe=60dd75eca9) | Jul 24, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [3721b1c82a](https://linux-hardware.org/?probe=3721b1c82a) | Jul 24, 2022 |
| Apple         | MacBookPro9,2               | [99ee81b243](https://linux-hardware.org/?probe=99ee81b243) | Jul 23, 2022 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [b16e17a798](https://linux-hardware.org/?probe=b16e17a798) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [ce6a0d666e](https://linux-hardware.org/?probe=ce6a0d666e) | Jul 23, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | [1c50bea602](https://linux-hardware.org/?probe=1c50bea602) | Jul 23, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [e06aafac8c](https://linux-hardware.org/?probe=e06aafac8c) | Jul 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [6a1cb48f15](https://linux-hardware.org/?probe=6a1cb48f15) | Jul 23, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1077085bf6](https://linux-hardware.org/?probe=1077085bf6) | Jul 23, 2022 |
| Lenovo        | 81FV                        | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| Dell          | Latitude E7440              | [d5ca3d7f7e](https://linux-hardware.org/?probe=d5ca3d7f7e) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [55f1eaa96c](https://linux-hardware.org/?probe=55f1eaa96c) | Jul 22, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5670dc3033](https://linux-hardware.org/?probe=5670dc3033) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S02D0... | [090cc78b83](https://linux-hardware.org/?probe=090cc78b83) | Jul 22, 2022 |
| Lenovo        | ThinkPad T430 2349DN4       | [fa8f2adca9](https://linux-hardware.org/?probe=fa8f2adca9) | Jul 22, 2022 |
| ASUSTek       | X750JN                      | [6bf181ed49](https://linux-hardware.org/?probe=6bf181ed49) | Jul 22, 2022 |
| Acer          | Aspire V3-572               | [5938905628](https://linux-hardware.org/?probe=5938905628) | Jul 22, 2022 |
| Samsung       | 550XBE/350XBE               | [b23cfb57cf](https://linux-hardware.org/?probe=b23cfb57cf) | Jul 21, 2022 |
| HP            | 240 G4                      | [449fb8b8f8](https://linux-hardware.org/?probe=449fb8b8f8) | Jul 21, 2022 |
| Dell          | XPS 15 9520                 | [51ddccaf88](https://linux-hardware.org/?probe=51ddccaf88) | Jul 21, 2022 |
| ASUSTek       | X541NA                      | [51aefa0464](https://linux-hardware.org/?probe=51aefa0464) | Jul 21, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| HP            | Laptop 17-by0xxx            | [afa7d8ba6c](https://linux-hardware.org/?probe=afa7d8ba6c) | Jul 21, 2022 |
| ASUSTek       | X541UVK                     | [a34ee52169](https://linux-hardware.org/?probe=a34ee52169) | Jul 21, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c1204438f8](https://linux-hardware.org/?probe=c1204438f8) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [ea200c839f](https://linux-hardware.org/?probe=ea200c839f) | Jul 20, 2022 |
| HP            | EliteBook 850 G5            | [0ffa75c50b](https://linux-hardware.org/?probe=0ffa75c50b) | Jul 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3c346ed8da](https://linux-hardware.org/?probe=3c346ed8da) | Jul 20, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [4cde663cf9](https://linux-hardware.org/?probe=4cde663cf9) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [effe49f996](https://linux-hardware.org/?probe=effe49f996) | Jul 20, 2022 |
| GPU Compan... | GWNR51416                   | [8d18b6813f](https://linux-hardware.org/?probe=8d18b6813f) | Jul 20, 2022 |
| Dell          | G3 3590                     | [920eed9524](https://linux-hardware.org/?probe=920eed9524) | Jul 19, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [944ba71eef](https://linux-hardware.org/?probe=944ba71eef) | Jul 19, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [56e3efd7bc](https://linux-hardware.org/?probe=56e3efd7bc) | Jul 19, 2022 |
| HP            | Notebook                    | [79c0f60f74](https://linux-hardware.org/?probe=79c0f60f74) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [ac6aba12f5](https://linux-hardware.org/?probe=ac6aba12f5) | Jul 19, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [7f4f42a3f7](https://linux-hardware.org/?probe=7f4f42a3f7) | Jul 19, 2022 |
| HP            | EliteBook 8570w             | [6b8bf59f68](https://linux-hardware.org/?probe=6b8bf59f68) | Jul 19, 2022 |
| Lenovo        | IdeaPad U430 Touch 20270    | [2c43b01e55](https://linux-hardware.org/?probe=2c43b01e55) | Jul 18, 2022 |
| Dell          | Latitude E6230              | [a66cad27e9](https://linux-hardware.org/?probe=a66cad27e9) | Jul 18, 2022 |
| Dell          | Latitude E7470              | [709a460528](https://linux-hardware.org/?probe=709a460528) | Jul 18, 2022 |
| MSI           | MS-14Y1                     | [782beac866](https://linux-hardware.org/?probe=782beac866) | Jul 18, 2022 |
| Google        | Kohaku                      | [2f21de3ff6](https://linux-hardware.org/?probe=2f21de3ff6) | Jul 18, 2022 |
| Pegatron      | D15K                        | [7f8fa03161](https://linux-hardware.org/?probe=7f8fa03161) | Jul 17, 2022 |
| Framework     | Laptop                      | [84d20eb09a](https://linux-hardware.org/?probe=84d20eb09a) | Jul 17, 2022 |
| Framework     | Laptop                      | [0489cc39db](https://linux-hardware.org/?probe=0489cc39db) | Jul 17, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [df94c841af](https://linux-hardware.org/?probe=df94c841af) | Jul 17, 2022 |
| Dell          | Inspiron 5515               | [502c19838a](https://linux-hardware.org/?probe=502c19838a) | Jul 17, 2022 |
| Unknown       | Unknown                     | [251f348fe5](https://linux-hardware.org/?probe=251f348fe5) | Jul 17, 2022 |
| ASUSTek       | X541NA                      | [3caa5cc13d](https://linux-hardware.org/?probe=3caa5cc13d) | Jul 17, 2022 |
| Dell          | Latitude E5440              | [c8e68471c1](https://linux-hardware.org/?probe=c8e68471c1) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| HP            | 250 G5                      | [979d1aea6f](https://linux-hardware.org/?probe=979d1aea6f) | Jul 16, 2022 |
| Lenovo        | ThinkPad T420 4236C92       | [40d837716b](https://linux-hardware.org/?probe=40d837716b) | Jul 16, 2022 |
| Alienware     | x17 R1                      | [9fc2d6416d](https://linux-hardware.org/?probe=9fc2d6416d) | Jul 16, 2022 |
| System76      | Bonobo Extreme              | [6c7f545300](https://linux-hardware.org/?probe=6c7f545300) | Jul 16, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | [18d1378620](https://linux-hardware.org/?probe=18d1378620) | Jul 16, 2022 |
| Dell          | XPS 13 7390                 | [eff723b9f2](https://linux-hardware.org/?probe=eff723b9f2) | Jul 16, 2022 |
| Acer          | Aspire V3-572               | [48dd04e4c8](https://linux-hardware.org/?probe=48dd04e4c8) | Jul 16, 2022 |
| Acer          | Aspire V3-572               | [3378b0fc15](https://linux-hardware.org/?probe=3378b0fc15) | Jul 16, 2022 |
| Toshiba       | Satellite L505D             | [1d7b1ed7c8](https://linux-hardware.org/?probe=1d7b1ed7c8) | Jul 15, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [42de47cdc1](https://linux-hardware.org/?probe=42de47cdc1) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [dd43fd4b04](https://linux-hardware.org/?probe=dd43fd4b04) | Jul 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S0EK00    | [9ca58ddce1](https://linux-hardware.org/?probe=9ca58ddce1) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [329ce2f7f8](https://linux-hardware.org/?probe=329ce2f7f8) | Jul 15, 2022 |
| Dell          | G3 3590                     | [86835e6c2b](https://linux-hardware.org/?probe=86835e6c2b) | Jul 15, 2022 |
| ASUSTek       | X541NA                      | [b9476b6cf9](https://linux-hardware.org/?probe=b9476b6cf9) | Jul 15, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [7812a0737e](https://linux-hardware.org/?probe=7812a0737e) | Jul 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea97effc52](https://linux-hardware.org/?probe=ea97effc52) | Jul 14, 2022 |
| Dell          | Inspiron M5010              | [56be64f444](https://linux-hardware.org/?probe=56be64f444) | Jul 14, 2022 |
| ASUSTek       | GL702ZC                     | [755f571a3e](https://linux-hardware.org/?probe=755f571a3e) | Jul 14, 2022 |
| Lenovo        | G400s VILG1                 | [fbaf6e2d8f](https://linux-hardware.org/?probe=fbaf6e2d8f) | Jul 13, 2022 |
| Lenovo        | G400s VILG1                 | [33853365fd](https://linux-hardware.org/?probe=33853365fd) | Jul 13, 2022 |
| Gigabyte      | AERO 17 KC                  | [b6398b12e2](https://linux-hardware.org/?probe=b6398b12e2) | Jul 13, 2022 |
| Lenovo        | ThinkPad P50 20EQA05JCL     | [43f5b3c05d](https://linux-hardware.org/?probe=43f5b3c05d) | Jul 13, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [f91143bc89](https://linux-hardware.org/?probe=f91143bc89) | Jul 13, 2022 |
| GPD           | G1621-02                    | [25da86e752](https://linux-hardware.org/?probe=25da86e752) | Jul 13, 2022 |
| Sony          | SVF1531V8CW                 | [bebf2fb162](https://linux-hardware.org/?probe=bebf2fb162) | Jul 13, 2022 |
| Dell          | Inspiron 5559               | [a687046e06](https://linux-hardware.org/?probe=a687046e06) | Jul 13, 2022 |
| Dell          | Inspiron 5559               | [c4b25937a7](https://linux-hardware.org/?probe=c4b25937a7) | Jul 13, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [de328d9562](https://linux-hardware.org/?probe=de328d9562) | Jul 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [f422c77bb1](https://linux-hardware.org/?probe=f422c77bb1) | Jul 12, 2022 |
| Lenovo        | ThinkPad T490s 20NYS0LY0... | [882680a962](https://linux-hardware.org/?probe=882680a962) | Jul 12, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [eb883a57f4](https://linux-hardware.org/?probe=eb883a57f4) | Jul 12, 2022 |
| HP            | Sona                        | [504fddb8e9](https://linux-hardware.org/?probe=504fddb8e9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [ea08980c33](https://linux-hardware.org/?probe=ea08980c33) | Jul 11, 2022 |
| VALE          | Notebook Classic C140       | [d6cc520dbe](https://linux-hardware.org/?probe=d6cc520dbe) | Jul 11, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [6b29072d9e](https://linux-hardware.org/?probe=6b29072d9e) | Jul 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ce42b6cb75](https://linux-hardware.org/?probe=ce42b6cb75) | Jul 11, 2022 |
| HP            | ProBook 6570b               | [5796920cf8](https://linux-hardware.org/?probe=5796920cf8) | Jul 11, 2022 |
| Lenovo        | IdeaPad 3 14IIL05 81WD      | [c1ed74053e](https://linux-hardware.org/?probe=c1ed74053e) | Jul 11, 2022 |
| Framework     | Laptop                      | [a13ef2beee](https://linux-hardware.org/?probe=a13ef2beee) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [a379e2a103](https://linux-hardware.org/?probe=a379e2a103) | Jul 11, 2022 |
| HP            | ProBook 6570b               | [4b10924d6a](https://linux-hardware.org/?probe=4b10924d6a) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | [753cc1d311](https://linux-hardware.org/?probe=753cc1d311) | Jul 10, 2022 |
| Panasonic     | FZG1-3                      | [01d4651376](https://linux-hardware.org/?probe=01d4651376) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| Dell          | Inspiron 3558               | [14cacca8ad](https://linux-hardware.org/?probe=14cacca8ad) | Jul 09, 2022 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [269ebd1a4d](https://linux-hardware.org/?probe=269ebd1a4d) | Jul 09, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [8270068517](https://linux-hardware.org/?probe=8270068517) | Jul 09, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [36151ae5c3](https://linux-hardware.org/?probe=36151ae5c3) | Jul 09, 2022 |
| MSI           | Bravo 17 A4DDK              | [9f9d1cac61](https://linux-hardware.org/?probe=9f9d1cac61) | Jul 09, 2022 |
| Dell          | Vostro 3590                 | [7195de93ae](https://linux-hardware.org/?probe=7195de93ae) | Jul 09, 2022 |
| HP            | Laptop 17z-cp000            | [f6f0740c36](https://linux-hardware.org/?probe=f6f0740c36) | Jul 09, 2022 |
| HP            | ProBook 6570b               | [b90b75215d](https://linux-hardware.org/?probe=b90b75215d) | Jul 09, 2022 |
| Acer          | Predator PH315-53           | [b6c6516360](https://linux-hardware.org/?probe=b6c6516360) | Jul 09, 2022 |
| Dell          | Latitude 3400               | [6a36fb9dd9](https://linux-hardware.org/?probe=6a36fb9dd9) | Jul 09, 2022 |
| HP            | EliteBook 8470p             | [c048bb9697](https://linux-hardware.org/?probe=c048bb9697) | Jul 09, 2022 |
| MSI           | GF63 Thin 8RCS              | [886728c1b6](https://linux-hardware.org/?probe=886728c1b6) | Jul 08, 2022 |
| Lenovo        | V14-ADA 82C6                | [e72ccdd0c6](https://linux-hardware.org/?probe=e72ccdd0c6) | Jul 08, 2022 |
| ASUSTek       | X550CC                      | [a57dba854b](https://linux-hardware.org/?probe=a57dba854b) | Jul 08, 2022 |
| Notebook      | NH55RGQ                     | [37de891a60](https://linux-hardware.org/?probe=37de891a60) | Jul 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cd5635c63c](https://linux-hardware.org/?probe=cd5635c63c) | Jul 08, 2022 |
| HP            | Pavilion g6                 | [30085f92b1](https://linux-hardware.org/?probe=30085f92b1) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [a64c483143](https://linux-hardware.org/?probe=a64c483143) | Jul 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [84f475721b](https://linux-hardware.org/?probe=84f475721b) | Jul 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [447ba923ac](https://linux-hardware.org/?probe=447ba923ac) | Jul 08, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [75f67b342a](https://linux-hardware.org/?probe=75f67b342a) | Jul 08, 2022 |
| Acer          | Predator PH315-53           | [69b6f2bdad](https://linux-hardware.org/?probe=69b6f2bdad) | Jul 08, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e850b43a12](https://linux-hardware.org/?probe=e850b43a12) | Jul 07, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [39e56d90b1](https://linux-hardware.org/?probe=39e56d90b1) | Jul 07, 2022 |
| Acer          | Nitro AN515-55              | [85845c3282](https://linux-hardware.org/?probe=85845c3282) | Jul 07, 2022 |
| ASUSTek       | X555DG                      | [b7a2c97bf2](https://linux-hardware.org/?probe=b7a2c97bf2) | Jul 07, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e1f5b40789](https://linux-hardware.org/?probe=e1f5b40789) | Jul 07, 2022 |
| Lenovo        | ThinkPad T500 2242CTO       | [106199561c](https://linux-hardware.org/?probe=106199561c) | Jul 07, 2022 |
| Dell          | XPS 17 9710                 | [81b2d3fa4f](https://linux-hardware.org/?probe=81b2d3fa4f) | Jul 06, 2022 |
| Toshiba       | Satellite L505D             | [cf5fedc6e5](https://linux-hardware.org/?probe=cf5fedc6e5) | Jul 06, 2022 |
| HP            | ProBook 450 G2              | [aeb16eb1eb](https://linux-hardware.org/?probe=aeb16eb1eb) | Jul 06, 2022 |
| Lenovo        | ThinkPad L380 20M5000FUS    | [9c6ab1a171](https://linux-hardware.org/?probe=9c6ab1a171) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [c75201835c](https://linux-hardware.org/?probe=c75201835c) | Jul 06, 2022 |
| Dell          | Inspiron 16 5625            | [dcbe63005c](https://linux-hardware.org/?probe=dcbe63005c) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [c8b9e41a50](https://linux-hardware.org/?probe=c8b9e41a50) | Jul 06, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dcd03a28be](https://linux-hardware.org/?probe=dcd03a28be) | Jul 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [454fed051a](https://linux-hardware.org/?probe=454fed051a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [5afb466a35](https://linux-hardware.org/?probe=5afb466a35) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [162080ffcf](https://linux-hardware.org/?probe=162080ffcf) | Jul 06, 2022 |
| Acer          | Aspire V3-572               | [4df173f8f2](https://linux-hardware.org/?probe=4df173f8f2) | Jul 06, 2022 |
| Acer          | Aspire V3-572               | [8dbec85d36](https://linux-hardware.org/?probe=8dbec85d36) | Jul 06, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [a3c85d395b](https://linux-hardware.org/?probe=a3c85d395b) | Jul 05, 2022 |
| System76      | Oryx Pro                    | [338a8ed5ab](https://linux-hardware.org/?probe=338a8ed5ab) | Jul 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [4009adaca2](https://linux-hardware.org/?probe=4009adaca2) | Jul 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [4826df34b3](https://linux-hardware.org/?probe=4826df34b3) | Jul 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0d03afb249](https://linux-hardware.org/?probe=0d03afb249) | Jul 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4d4cd5bae0](https://linux-hardware.org/?probe=4d4cd5bae0) | Jul 05, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [2cbcdfe2db](https://linux-hardware.org/?probe=2cbcdfe2db) | Jul 05, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [7f64f81a29](https://linux-hardware.org/?probe=7f64f81a29) | Jul 04, 2022 |
| HP            | ProBook 645 G3              | [5c37a32531](https://linux-hardware.org/?probe=5c37a32531) | Jul 04, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [7bb2a0b59a](https://linux-hardware.org/?probe=7bb2a0b59a) | Jul 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [59a1c1c8b1](https://linux-hardware.org/?probe=59a1c1c8b1) | Jul 04, 2022 |
| Chuwi         | GemiBook                    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [9e9a46d8ec](https://linux-hardware.org/?probe=9e9a46d8ec) | Jul 04, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [2ed808bbcc](https://linux-hardware.org/?probe=2ed808bbcc) | Jul 04, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [5a6c158296](https://linux-hardware.org/?probe=5a6c158296) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | [4cebce6bab](https://linux-hardware.org/?probe=4cebce6bab) | Jul 04, 2022 |
| ASUSTek       | TP501UB                     | [6ee62813e8](https://linux-hardware.org/?probe=6ee62813e8) | Jul 04, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [d2dd306cb4](https://linux-hardware.org/?probe=d2dd306cb4) | Jul 04, 2022 |
| HP            | Notebook                    | [b9eb2e4cdd](https://linux-hardware.org/?probe=b9eb2e4cdd) | Jul 04, 2022 |
| HP            | 255 G8 Notebook PC          | [af74b651d5](https://linux-hardware.org/?probe=af74b651d5) | Jul 04, 2022 |
| HP            | EliteBook 8470p             | [4600681149](https://linux-hardware.org/?probe=4600681149) | Jul 03, 2022 |
| HP            | EliteBook 8470p             | [85c5a62101](https://linux-hardware.org/?probe=85c5a62101) | Jul 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [d0e94cff94](https://linux-hardware.org/?probe=d0e94cff94) | Jul 03, 2022 |
| HP            | EliteBook 840 G1            | [9705c40e85](https://linux-hardware.org/?probe=9705c40e85) | Jul 03, 2022 |
| Apple         | MacBookPro5,1               | [ac53d2f956](https://linux-hardware.org/?probe=ac53d2f956) | Jul 02, 2022 |
| Dell          | XPS 13 9350                 | [0c8bcdbcb1](https://linux-hardware.org/?probe=0c8bcdbcb1) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480s 20L7004NM... | [716bd7e41f](https://linux-hardware.org/?probe=716bd7e41f) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | [576f59ec1b](https://linux-hardware.org/?probe=576f59ec1b) | Jul 02, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | [4d9cb098c8](https://linux-hardware.org/?probe=4d9cb098c8) | Jul 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S2EQ00    | [1b45ef7d10](https://linux-hardware.org/?probe=1b45ef7d10) | Jul 01, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [16413aeb23](https://linux-hardware.org/?probe=16413aeb23) | Jul 01, 2022 |
| HP            | Laptop 14s-cf2xxx           | [8da2258fea](https://linux-hardware.org/?probe=8da2258fea) | Jul 01, 2022 |
| Dell          | Inspiron M5010              | [14b9aa33d2](https://linux-hardware.org/?probe=14b9aa33d2) | Jul 01, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [2671f4ffe2](https://linux-hardware.org/?probe=2671f4ffe2) | Jul 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [c9d0d64896](https://linux-hardware.org/?probe=c9d0d64896) | Jul 01, 2022 |
| Framework     | Laptop                      | [1089f37daf](https://linux-hardware.org/?probe=1089f37daf) | Jul 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS2292S    | [cf313915ab](https://linux-hardware.org/?probe=cf313915ab) | Jun 30, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [3af286a188](https://linux-hardware.org/?probe=3af286a188) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [cd488e4f64](https://linux-hardware.org/?probe=cd488e4f64) | Jun 30, 2022 |
| HP            | EliteBook 8470p             | [52dfa0a4ee](https://linux-hardware.org/?probe=52dfa0a4ee) | Jun 30, 2022 |
| Acer          | Aspire A315-55G             | [e6d7a2a642](https://linux-hardware.org/?probe=e6d7a2a642) | Jun 30, 2022 |
| HP            | Laptop 15-da0xxx            | [9c512247ff](https://linux-hardware.org/?probe=9c512247ff) | Jun 30, 2022 |
| Lenovo        | ThinkPad T410 2518A37       | [4e15b37546](https://linux-hardware.org/?probe=4e15b37546) | Jun 30, 2022 |
| Dell          | Inspiron 3543               | [1f9d3b4a6c](https://linux-hardware.org/?probe=1f9d3b4a6c) | Jun 29, 2022 |
| HP            | Laptop 15s-eq2xxx           | [5acbf09f01](https://linux-hardware.org/?probe=5acbf09f01) | Jun 29, 2022 |
| ASUSTek       | UX302LA                     | [6092e85ae8](https://linux-hardware.org/?probe=6092e85ae8) | Jun 29, 2022 |
| Getac         | B300-X                      | [eb752b6c15](https://linux-hardware.org/?probe=eb752b6c15) | Jun 29, 2022 |
| HUAWEI        | BOD-WXX9                    | [9c3e14320e](https://linux-hardware.org/?probe=9c3e14320e) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [43c87260b2](https://linux-hardware.org/?probe=43c87260b2) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Alienware     | 17                          | [715b5b0dce](https://linux-hardware.org/?probe=715b5b0dce) | Jun 29, 2022 |
| Apple         | MacBookAir6,1               | [c3172fd9cf](https://linux-hardware.org/?probe=c3172fd9cf) | Jun 28, 2022 |
| Dell          | Precision M6800             | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| Dell          | Latitude 5511               | [c361c37273](https://linux-hardware.org/?probe=c361c37273) | Jun 28, 2022 |
| ASUSTek       | X750JN                      | [4ba4d14a1a](https://linux-hardware.org/?probe=4ba4d14a1a) | Jun 28, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [d240efa39f](https://linux-hardware.org/?probe=d240efa39f) | Jun 28, 2022 |
| Apple         | MacBookPro12,1              | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Toshiba       | Satellite C855-12R          | [e94a109546](https://linux-hardware.org/?probe=e94a109546) | Jun 28, 2022 |
| Dell          | Inspiron N5110              | [239e8c86c0](https://linux-hardware.org/?probe=239e8c86c0) | Jun 28, 2022 |
| Dell          | Latitude E6520              | [f688527838](https://linux-hardware.org/?probe=f688527838) | Jun 27, 2022 |
| Gigabyte      | RC14UD                      | [d2b55252d8](https://linux-hardware.org/?probe=d2b55252d8) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1c4ace32a2](https://linux-hardware.org/?probe=1c4ace32a2) | Jun 27, 2022 |
| Apple         | MacBookPro5,1               | [1e14793557](https://linux-hardware.org/?probe=1e14793557) | Jun 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [3a651b23fb](https://linux-hardware.org/?probe=3a651b23fb) | Jun 26, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [de3ca4e422](https://linux-hardware.org/?probe=de3ca4e422) | Jun 26, 2022 |
| Acer          | Swift SF114-32              | [25e6653354](https://linux-hardware.org/?probe=25e6653354) | Jun 26, 2022 |
| MSI           | GF63 Thin 9SCXR             | [db6195eed2](https://linux-hardware.org/?probe=db6195eed2) | Jun 26, 2022 |
| Timi          | A35S                        | [606e376264](https://linux-hardware.org/?probe=606e376264) | Jun 26, 2022 |
| Dell          | Latitude 7300               | [a7939aeb9e](https://linux-hardware.org/?probe=a7939aeb9e) | Jun 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [400eaba39f](https://linux-hardware.org/?probe=400eaba39f) | Jun 26, 2022 |
| HP            | Compaq CQ58                 | [5948b56a82](https://linux-hardware.org/?probe=5948b56a82) | Jun 25, 2022 |
| Dell          | XPS 13 9310                 | [fa3d29c80b](https://linux-hardware.org/?probe=fa3d29c80b) | Jun 25, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [81a9b9847d](https://linux-hardware.org/?probe=81a9b9847d) | Jun 25, 2022 |
| Dell          | Inspiron 5437               | [e206b319a2](https://linux-hardware.org/?probe=e206b319a2) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| HP            | Pavilion g6                 | [d2e82f01d9](https://linux-hardware.org/?probe=d2e82f01d9) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| HP            | OMEN Notebook PC 15         | [66f845b63e](https://linux-hardware.org/?probe=66f845b63e) | Jun 25, 2022 |
| Unknown       | Unknown                     | [6e62883390](https://linux-hardware.org/?probe=6e62883390) | Jun 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [66283ad8cd](https://linux-hardware.org/?probe=66283ad8cd) | Jun 24, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [3b78b34416](https://linux-hardware.org/?probe=3b78b34416) | Jun 24, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [58ab145788](https://linux-hardware.org/?probe=58ab145788) | Jun 24, 2022 |
| HP            | Laptop 15-ef2xxx            | [3e16709617](https://linux-hardware.org/?probe=3e16709617) | Jun 24, 2022 |
| Packard Be... | EasyNote TE69HW             | [d292d79bbe](https://linux-hardware.org/?probe=d292d79bbe) | Jun 24, 2022 |
| Lenovo        | ThinkPad T520 4243VE1       | [7fcfec26eb](https://linux-hardware.org/?probe=7fcfec26eb) | Jun 24, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [2c0b9c6402](https://linux-hardware.org/?probe=2c0b9c6402) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [bb8541d805](https://linux-hardware.org/?probe=bb8541d805) | Jun 24, 2022 |
| Acer          | Nitro AN515-54              | [afce38a95a](https://linux-hardware.org/?probe=afce38a95a) | Jun 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d4b96de9b6](https://linux-hardware.org/?probe=d4b96de9b6) | Jun 24, 2022 |
| Dell          | Precision 5550              | [0811e8c956](https://linux-hardware.org/?probe=0811e8c956) | Jun 23, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [ac634d8aa9](https://linux-hardware.org/?probe=ac634d8aa9) | Jun 23, 2022 |
| Dell          | Precision 5550              | [0ae65f654e](https://linux-hardware.org/?probe=0ae65f654e) | Jun 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [926d4055f7](https://linux-hardware.org/?probe=926d4055f7) | Jun 23, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [223e43004a](https://linux-hardware.org/?probe=223e43004a) | Jun 23, 2022 |
| HP            | 250 G7 Notebook PC          | [6ec1b55ac0](https://linux-hardware.org/?probe=6ec1b55ac0) | Jun 23, 2022 |
| Lenovo        | G510 20238                  | [1b382e0eb0](https://linux-hardware.org/?probe=1b382e0eb0) | Jun 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [5dd91493a8](https://linux-hardware.org/?probe=5dd91493a8) | Jun 23, 2022 |
| ASUSTek       | K46CB                       | [65344cb089](https://linux-hardware.org/?probe=65344cb089) | Jun 23, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [f002062377](https://linux-hardware.org/?probe=f002062377) | Jun 22, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [1967dad271](https://linux-hardware.org/?probe=1967dad271) | Jun 22, 2022 |
| Positivo      | VJF155F11UAR                | [77c5ca4f1e](https://linux-hardware.org/?probe=77c5ca4f1e) | Jun 22, 2022 |
| Acer          | NC-E5-774G-75TJ             | [55fce68116](https://linux-hardware.org/?probe=55fce68116) | Jun 22, 2022 |
| HP            | ZBook 17 G4                 | [bf03eb0fa7](https://linux-hardware.org/?probe=bf03eb0fa7) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK U745               | [0fffb61902](https://linux-hardware.org/?probe=0fffb61902) | Jun 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [dda5fb9c20](https://linux-hardware.org/?probe=dda5fb9c20) | Jun 21, 2022 |
| HUAWEI        | MACH-WX9                    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| HP            | EliteBook 830 G6            | [7c7d9af667](https://linux-hardware.org/?probe=7c7d9af667) | Jun 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [ae54449547](https://linux-hardware.org/?probe=ae54449547) | Jun 21, 2022 |
| GEO           | GeoBook 240                 | [f08637137c](https://linux-hardware.org/?probe=f08637137c) | Jun 21, 2022 |
| Dell          | XPS 13 9380                 | [dc134b17e9](https://linux-hardware.org/?probe=dc134b17e9) | Jun 21, 2022 |
| HP            | ProBook 440 G6              | [eeeee7321e](https://linux-hardware.org/?probe=eeeee7321e) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [27623895a1](https://linux-hardware.org/?probe=27623895a1) | Jun 20, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012G... | [92638f1b46](https://linux-hardware.org/?probe=92638f1b46) | Jun 20, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [52aa806063](https://linux-hardware.org/?probe=52aa806063) | Jun 20, 2022 |
| Panasonic     | CFSV9-1                     | [4b7dd23ccd](https://linux-hardware.org/?probe=4b7dd23ccd) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [666e91f182](https://linux-hardware.org/?probe=666e91f182) | Jun 20, 2022 |
| Dell          | XPS 15 9520                 | [ec6f5cce04](https://linux-hardware.org/?probe=ec6f5cce04) | Jun 20, 2022 |
| Google        | Droid                       | [5a175a2a78](https://linux-hardware.org/?probe=5a175a2a78) | Jun 20, 2022 |
| Apple         | MacBookPro12,1              | [5d9f65fbc9](https://linux-hardware.org/?probe=5d9f65fbc9) | Jun 20, 2022 |
| HP            | EliteBook 865 16 inch G9... | [9a543a0273](https://linux-hardware.org/?probe=9a543a0273) | Jun 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [bbb3795dc2](https://linux-hardware.org/?probe=bbb3795dc2) | Jun 20, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [9cf3c1f84c](https://linux-hardware.org/?probe=9cf3c1f84c) | Jun 19, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | [df2017f7d5](https://linux-hardware.org/?probe=df2017f7d5) | Jun 19, 2022 |
| Micro Elec... | MG-VCP17I-3070              | [e09cfb9236](https://linux-hardware.org/?probe=e09cfb9236) | Jun 19, 2022 |
| HP            | Pavilion dv7                | [ab34fbb528](https://linux-hardware.org/?probe=ab34fbb528) | Jun 19, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [3c8a4e8226](https://linux-hardware.org/?probe=3c8a4e8226) | Jun 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a71adbf68f](https://linux-hardware.org/?probe=a71adbf68f) | Jun 18, 2022 |
| HP            | ProBook 470 G5              | [b070339877](https://linux-hardware.org/?probe=b070339877) | Jun 18, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [4a1a0294d8](https://linux-hardware.org/?probe=4a1a0294d8) | Jun 18, 2022 |
| Dell          | Precision 3571              | [9d6985b0f0](https://linux-hardware.org/?probe=9d6985b0f0) | Jun 18, 2022 |
| Dell          | Precision 3571              | [285846e1a4](https://linux-hardware.org/?probe=285846e1a4) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [91af0ec6df](https://linux-hardware.org/?probe=91af0ec6df) | Jun 18, 2022 |
| Acer          | Swift SF314-43              | [a6116d2e8c](https://linux-hardware.org/?probe=a6116d2e8c) | Jun 18, 2022 |
| ASUSTek       | TUF Gaming FX505DY_TUF50... | [df304b4da1](https://linux-hardware.org/?probe=df304b4da1) | Jun 17, 2022 |
| Acer          | Swift SF314-43              | [674addd96b](https://linux-hardware.org/?probe=674addd96b) | Jun 17, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [e0b7e5c636](https://linux-hardware.org/?probe=e0b7e5c636) | Jun 17, 2022 |
| Dell          | XPS 13 7390                 | [9cbdc324b7](https://linux-hardware.org/?probe=9cbdc324b7) | Jun 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [cb6bf6ab7c](https://linux-hardware.org/?probe=cb6bf6ab7c) | Jun 17, 2022 |
| Sony          | SVE15128CNB                 | [029a230c77](https://linux-hardware.org/?probe=029a230c77) | Jun 17, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [2a28e582b5](https://linux-hardware.org/?probe=2a28e582b5) | Jun 17, 2022 |
| Acer          | Aspire E5-476G              | [df4b512aa8](https://linux-hardware.org/?probe=df4b512aa8) | Jun 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [a7431ef0c5](https://linux-hardware.org/?probe=a7431ef0c5) | Jun 17, 2022 |
| Samsung       | 500R5M/500R5W/501R5M        | [91f1df8a58](https://linux-hardware.org/?probe=91f1df8a58) | Jun 17, 2022 |
| Acer          | Predator PH315-53           | [7e65c001a5](https://linux-hardware.org/?probe=7e65c001a5) | Jun 17, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [e4d5856a72](https://linux-hardware.org/?probe=e4d5856a72) | Jun 16, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4e53a55031](https://linux-hardware.org/?probe=4e53a55031) | Jun 16, 2022 |
| Dell          | XPS 13 7390                 | [7dbb9f4adf](https://linux-hardware.org/?probe=7dbb9f4adf) | Jun 16, 2022 |
| Micro Elec... | MG-VCP17I-3070              | [c6d123b5ec](https://linux-hardware.org/?probe=c6d123b5ec) | Jun 16, 2022 |
| Micro Elec... | MG-VCP17I-3070              | [d28d429121](https://linux-hardware.org/?probe=d28d429121) | Jun 16, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [7d8683dfac](https://linux-hardware.org/?probe=7d8683dfac) | Jun 16, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [f83da947b8](https://linux-hardware.org/?probe=f83da947b8) | Jun 16, 2022 |
| Itautec       | Infoway w7430               | [776d876064](https://linux-hardware.org/?probe=776d876064) | Jun 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [388285efe8](https://linux-hardware.org/?probe=388285efe8) | Jun 15, 2022 |
| HP            | Laptop 17-cp0xxx            | [6b73227c17](https://linux-hardware.org/?probe=6b73227c17) | Jun 15, 2022 |
| Acer          | Predator PH315-53           | [155af690bd](https://linux-hardware.org/?probe=155af690bd) | Jun 15, 2022 |
| Dell          | XPS 15 9520                 | [bdd4ec2ef9](https://linux-hardware.org/?probe=bdd4ec2ef9) | Jun 15, 2022 |
| Dell          | XPS 15 9520                 | [03140c6f93](https://linux-hardware.org/?probe=03140c6f93) | Jun 15, 2022 |
| HP            | Laptop 17-cp0xxx            | [6f25a1e394](https://linux-hardware.org/?probe=6f25a1e394) | Jun 15, 2022 |
| Dell          | Inspiron 7472               | [788b7856ca](https://linux-hardware.org/?probe=788b7856ca) | Jun 15, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [76fd9cba2e](https://linux-hardware.org/?probe=76fd9cba2e) | Jun 15, 2022 |
| Dell          | Precision 3551              | [3499839fd0](https://linux-hardware.org/?probe=3499839fd0) | Jun 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b6f26fecef](https://linux-hardware.org/?probe=b6f26fecef) | Jun 14, 2022 |
| HP            | Notebook                    | [390f55db2e](https://linux-hardware.org/?probe=390f55db2e) | Jun 14, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Dell          | XPS 15 9510                 | [61104911ed](https://linux-hardware.org/?probe=61104911ed) | Jun 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [b10e894950](https://linux-hardware.org/?probe=b10e894950) | Jun 14, 2022 |
| Timi          | Redmi Book Pro 15 2022      | [b3259c0af4](https://linux-hardware.org/?probe=b3259c0af4) | Jun 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [35cbb5ff8b](https://linux-hardware.org/?probe=35cbb5ff8b) | Jun 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e2385e525c](https://linux-hardware.org/?probe=e2385e525c) | Jun 14, 2022 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [605cab3041](https://linux-hardware.org/?probe=605cab3041) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | [cf08ff4333](https://linux-hardware.org/?probe=cf08ff4333) | Jun 14, 2022 |
| HP            | Pavilion Notebook           | [4b4bd76de7](https://linux-hardware.org/?probe=4b4bd76de7) | Jun 14, 2022 |
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [2b87adfa9f](https://linux-hardware.org/?probe=2b87adfa9f) | Jun 13, 2022 |
| HP            | Pavilion g6                 | [20bd05081e](https://linux-hardware.org/?probe=20bd05081e) | Jun 13, 2022 |
| HP            | Pavilion g6                 | [d147676849](https://linux-hardware.org/?probe=d147676849) | Jun 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [b8b4869fa1](https://linux-hardware.org/?probe=b8b4869fa1) | Jun 13, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [221099208b](https://linux-hardware.org/?probe=221099208b) | Jun 13, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [0a985a9f53](https://linux-hardware.org/?probe=0a985a9f53) | Jun 13, 2022 |
| Lenovo        | Y50-70 20378                | [6153f90073](https://linux-hardware.org/?probe=6153f90073) | Jun 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [17d6efccfa](https://linux-hardware.org/?probe=17d6efccfa) | Jun 12, 2022 |
| Acer          | Aspire E5-573G              | [967ef390e0](https://linux-hardware.org/?probe=967ef390e0) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [dbe7d6b6bf](https://linux-hardware.org/?probe=dbe7d6b6bf) | Jun 12, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [554002fe47](https://linux-hardware.org/?probe=554002fe47) | Jun 12, 2022 |
| HP            | Laptop 15s-fq3xxx           | [6acd8f6081](https://linux-hardware.org/?probe=6acd8f6081) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | [b791797ef3](https://linux-hardware.org/?probe=b791797ef3) | Jun 12, 2022 |
| Acer          | Aspire R7-371T              | [d573a80e21](https://linux-hardware.org/?probe=d573a80e21) | Jun 12, 2022 |
| Apple         | MacBookPro6,2               | [a677849f96](https://linux-hardware.org/?probe=a677849f96) | Jun 12, 2022 |
| ASUSTek       | X750JN                      | [6748bf6f1e](https://linux-hardware.org/?probe=6748bf6f1e) | Jun 11, 2022 |
| HP            | ProBook 650 G1              | [8f468e1fc9](https://linux-hardware.org/?probe=8f468e1fc9) | Jun 11, 2022 |
| Lenovo        | ThinkPad T420 4180BE1       | [a3c2ffc8e0](https://linux-hardware.org/?probe=a3c2ffc8e0) | Jun 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [3c8959c8dc](https://linux-hardware.org/?probe=3c8959c8dc) | Jun 11, 2022 |
| HP            | Laptop 17-bs1xx             | [aa23e1d53e](https://linux-hardware.org/?probe=aa23e1d53e) | Jun 11, 2022 |
| HUAWEI        | WRT-WX9                     | [13dcf888fe](https://linux-hardware.org/?probe=13dcf888fe) | Jun 10, 2022 |
| Acer          | Swift SF114-32              | [63f76026b7](https://linux-hardware.org/?probe=63f76026b7) | Jun 10, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [1967d32245](https://linux-hardware.org/?probe=1967d32245) | Jun 10, 2022 |
| Dell          | XPS 15 9570                 | [f37ad0aba6](https://linux-hardware.org/?probe=f37ad0aba6) | Jun 10, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [14e32dc3cb](https://linux-hardware.org/?probe=14e32dc3cb) | Jun 10, 2022 |
| HP            | Laptop 14s-fq0xxx           | [0a77925edb](https://linux-hardware.org/?probe=0a77925edb) | Jun 10, 2022 |
| Lenovo        | ThinkPad P50 20EQS3B30R     | [c97b8918a0](https://linux-hardware.org/?probe=c97b8918a0) | Jun 10, 2022 |
| HP            | ZBook 15                    | [540fada7d4](https://linux-hardware.org/?probe=540fada7d4) | Jun 09, 2022 |
| HP            | ZBook 15                    | [5e3ff70430](https://linux-hardware.org/?probe=5e3ff70430) | Jun 09, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [158a18f6d1](https://linux-hardware.org/?probe=158a18f6d1) | Jun 09, 2022 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [321a2df7db](https://linux-hardware.org/?probe=321a2df7db) | Jun 09, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | [e934effe87](https://linux-hardware.org/?probe=e934effe87) | Jun 09, 2022 |
| HP            | ENVY dv7                    | [f7401e6566](https://linux-hardware.org/?probe=f7401e6566) | Jun 09, 2022 |
| Toshiba       | Satellite C50-A             | [1f5918622d](https://linux-hardware.org/?probe=1f5918622d) | Jun 08, 2022 |
| Toshiba       | Satellite C50-A             | [20a629adc2](https://linux-hardware.org/?probe=20a629adc2) | Jun 08, 2022 |
| HUAWEI        | KLVL-WXX9                   | [4ce4c3ad20](https://linux-hardware.org/?probe=4ce4c3ad20) | Jun 08, 2022 |
| Lenovo        | ThinkPad T400 6475AJ1       | [3ef905b44a](https://linux-hardware.org/?probe=3ef905b44a) | Jun 08, 2022 |
| VIT           | M2420                       | [8152d4c61b](https://linux-hardware.org/?probe=8152d4c61b) | Jun 08, 2022 |
| VIT           | M2420                       | [d09de8cbd7](https://linux-hardware.org/?probe=d09de8cbd7) | Jun 07, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [73823d7212](https://linux-hardware.org/?probe=73823d7212) | Jun 07, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [1a79b3a2ab](https://linux-hardware.org/?probe=1a79b3a2ab) | Jun 07, 2022 |
| HP            | 250 G7 Notebook PC          | [c45207e9ed](https://linux-hardware.org/?probe=c45207e9ed) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [14a3f31e7d](https://linux-hardware.org/?probe=14a3f31e7d) | Jun 07, 2022 |
| HP            | 250 G7 Notebook PC          | [fa7cd44609](https://linux-hardware.org/?probe=fa7cd44609) | Jun 07, 2022 |
| Apple         | MacBook4,1                  | [c8e7bd54a3](https://linux-hardware.org/?probe=c8e7bd54a3) | Jun 07, 2022 |
| Dell          | Inspiron 3542               | [8fcf9a9913](https://linux-hardware.org/?probe=8fcf9a9913) | Jun 07, 2022 |
| HP            | Laptop 15-dy0xxx            | [e2a9ba60e2](https://linux-hardware.org/?probe=e2a9ba60e2) | Jun 07, 2022 |
| Unknown       | Unknown                     | [6c562bbebb](https://linux-hardware.org/?probe=6c562bbebb) | Jun 06, 2022 |
| Apple         | MacBookPro14,3              | [0d56225d08](https://linux-hardware.org/?probe=0d56225d08) | Jun 06, 2022 |
| Lenovo        | IdeaPad 330-17IKB 81DM      | [5f55cd1869](https://linux-hardware.org/?probe=5f55cd1869) | Jun 06, 2022 |
| HP            | EliteBook 8740w             | [178b330cc1](https://linux-hardware.org/?probe=178b330cc1) | Jun 06, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [bec76e5f74](https://linux-hardware.org/?probe=bec76e5f74) | Jun 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [0732a60437](https://linux-hardware.org/?probe=0732a60437) | Jun 06, 2022 |
| HP            | 250 G5                      | [1cbf1a1c53](https://linux-hardware.org/?probe=1cbf1a1c53) | Jun 06, 2022 |
| Lenovo        | 81WE                        | [31217f3c4a](https://linux-hardware.org/?probe=31217f3c4a) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | [e7e658bc95](https://linux-hardware.org/?probe=e7e658bc95) | Jun 06, 2022 |
| Dell          | XPS 13 9370                 | [568a879289](https://linux-hardware.org/?probe=568a879289) | Jun 06, 2022 |
| Lenovo        | G580 2689PWG                | [e51b9086bd](https://linux-hardware.org/?probe=e51b9086bd) | Jun 06, 2022 |
| HP            | 250 G5                      | [7cbd2a6796](https://linux-hardware.org/?probe=7cbd2a6796) | Jun 06, 2022 |
| HP            | 250 G5                      | [6668b9ad94](https://linux-hardware.org/?probe=6668b9ad94) | Jun 06, 2022 |
| Apple         | MacBookAir5,1               | [f9ac66019f](https://linux-hardware.org/?probe=f9ac66019f) | Jun 06, 2022 |
| Apple         | MacBookPro14,3              | [8fbfe75f53](https://linux-hardware.org/?probe=8fbfe75f53) | Jun 06, 2022 |
| Lenovo        | ThinkPad T420 4177CTO       | [fe28db8adc](https://linux-hardware.org/?probe=fe28db8adc) | Jun 06, 2022 |
| HP            | EliteBook 2560p             | [9cd1c3d383](https://linux-hardware.org/?probe=9cd1c3d383) | Jun 05, 2022 |
| Apple         | MacBookPro10,1              | [9e49a2cbac](https://linux-hardware.org/?probe=9e49a2cbac) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7084316e82](https://linux-hardware.org/?probe=7084316e82) | Jun 05, 2022 |
| Acer          | Aspire R3-131T              | [f1becc237d](https://linux-hardware.org/?probe=f1becc237d) | Jun 05, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [155a8dd1a5](https://linux-hardware.org/?probe=155a8dd1a5) | Jun 05, 2022 |
| Dell          | Latitude 7490               | [feb1fc06d4](https://linux-hardware.org/?probe=feb1fc06d4) | Jun 05, 2022 |
| ASUSTek       | X541NA                      | [0c40d3f3d2](https://linux-hardware.org/?probe=0c40d3f3d2) | Jun 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [84d72b2b06](https://linux-hardware.org/?probe=84d72b2b06) | Jun 05, 2022 |
| HP            | ProBook 650 G1              | [be6fcc008b](https://linux-hardware.org/?probe=be6fcc008b) | Jun 04, 2022 |
| Acer          | Aspire E5-573G              | [31de2e546e](https://linux-hardware.org/?probe=31de2e546e) | Jun 04, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [41862e04b8](https://linux-hardware.org/?probe=41862e04b8) | Jun 03, 2022 |
| Dell          | Precision 5540              | [641aabe445](https://linux-hardware.org/?probe=641aabe445) | Jun 03, 2022 |
| Notebook      | NL40_50CU                   | [df0357703d](https://linux-hardware.org/?probe=df0357703d) | Jun 03, 2022 |
| Dell          | XPS 15 9560                 | [38de8409ef](https://linux-hardware.org/?probe=38de8409ef) | Jun 02, 2022 |
| Framework     | Laptop                      | [625917cfcd](https://linux-hardware.org/?probe=625917cfcd) | Jun 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3aa4194ab3](https://linux-hardware.org/?probe=3aa4194ab3) | Jun 02, 2022 |
| Lenovo        | IdeaPad L340-17IWL 81M0     | [b5bb3c0725](https://linux-hardware.org/?probe=b5bb3c0725) | Jun 02, 2022 |
| ASUSTek       | N82JV                       | [623436f0c3](https://linux-hardware.org/?probe=623436f0c3) | Jun 02, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [ff63d0c19b](https://linux-hardware.org/?probe=ff63d0c19b) | Jun 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [978a80c358](https://linux-hardware.org/?probe=978a80c358) | Jun 02, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | [d81154a7e1](https://linux-hardware.org/?probe=d81154a7e1) | Jun 02, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [ad66932f23](https://linux-hardware.org/?probe=ad66932f23) | Jun 02, 2022 |
| Dell          | Inspiron 3531               | [c2d9f4b84b](https://linux-hardware.org/?probe=c2d9f4b84b) | Jun 02, 2022 |
| HUAWEI        | MACH-WX9                    | [70ad46aa8e](https://linux-hardware.org/?probe=70ad46aa8e) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | [38fb3963cd](https://linux-hardware.org/?probe=38fb3963cd) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | [6f5f1c9373](https://linux-hardware.org/?probe=6f5f1c9373) | Jun 01, 2022 |
| Lenovo        | Edge 15 80K9                | [5c8bb97759](https://linux-hardware.org/?probe=5c8bb97759) | Jun 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [ae39e96b1a](https://linux-hardware.org/?probe=ae39e96b1a) | Jun 01, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0f84f94a6a](https://linux-hardware.org/?probe=0f84f94a6a) | Jun 01, 2022 |
| HP            | EliteBook 2560p             | [af6a91d3c7](https://linux-hardware.org/?probe=af6a91d3c7) | Jun 01, 2022 |
| Dell          | Inspiron 5415               | [942b343fff](https://linux-hardware.org/?probe=942b343fff) | Jun 01, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [1e6ab0f183](https://linux-hardware.org/?probe=1e6ab0f183) | May 31, 2022 |
| ASUSTek       | X541NA                      | [3d32754542](https://linux-hardware.org/?probe=3d32754542) | May 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [dc3ee2e520](https://linux-hardware.org/?probe=dc3ee2e520) | May 31, 2022 |
| Lenovo        | Edge 15 80K9                | [9bbdfc95bb](https://linux-hardware.org/?probe=9bbdfc95bb) | May 31, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [956299505f](https://linux-hardware.org/?probe=956299505f) | May 31, 2022 |
| HP            | Pavilion Laptop 14-dv0xx... | [9b53c4df9d](https://linux-hardware.org/?probe=9b53c4df9d) | May 31, 2022 |
| ASUSTek       | N501VW                      | [2f8215fb0a](https://linux-hardware.org/?probe=2f8215fb0a) | May 31, 2022 |
| HP            | EliteBook 840 G3            | [92acbd4c3f](https://linux-hardware.org/?probe=92acbd4c3f) | May 31, 2022 |
| Apple         | MacBookPro8,3               | [38f4cc4c5a](https://linux-hardware.org/?probe=38f4cc4c5a) | May 31, 2022 |
| Dell          | XPS 15 9520                 | [4d4c32223e](https://linux-hardware.org/?probe=4d4c32223e) | May 31, 2022 |
| Dell          | Inspiron 5547               | [066f6369b2](https://linux-hardware.org/?probe=066f6369b2) | May 31, 2022 |
| HP            | 255 G1                      | [86f7198193](https://linux-hardware.org/?probe=86f7198193) | May 31, 2022 |
| Lenovo        | ThinkPad E595 20NF001PTX    | [cf41cc78f7](https://linux-hardware.org/?probe=cf41cc78f7) | May 30, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [5a813419eb](https://linux-hardware.org/?probe=5a813419eb) | May 30, 2022 |
| Lenovo        | Edge 15 80K9                | [586a31368f](https://linux-hardware.org/?probe=586a31368f) | May 30, 2022 |
| Google        | Droid                       | [35e3edeab3](https://linux-hardware.org/?probe=35e3edeab3) | May 30, 2022 |
| Framework     | Laptop                      | [f1c2a80b70](https://linux-hardware.org/?probe=f1c2a80b70) | May 30, 2022 |
| Lenovo        | ThinkPad X240 20AM0040BR    | [e0ff07b590](https://linux-hardware.org/?probe=e0ff07b590) | May 30, 2022 |
| IT Channel... | PA70Hx                      | [091ad22c2d](https://linux-hardware.org/?probe=091ad22c2d) | May 30, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [378e6ca9c6](https://linux-hardware.org/?probe=378e6ca9c6) | May 30, 2022 |
| Dell          | XPS 15 9520                 | [eee1a317b6](https://linux-hardware.org/?probe=eee1a317b6) | May 30, 2022 |
| MSI           | GE60 2PE                    | [1e15d749ee](https://linux-hardware.org/?probe=1e15d749ee) | May 30, 2022 |
| ASUSTek       | X541NA                      | [c1fd0c2d4f](https://linux-hardware.org/?probe=c1fd0c2d4f) | May 30, 2022 |
| MSI           | GE60 2PE                    | [b52762040d](https://linux-hardware.org/?probe=b52762040d) | May 30, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [15fb1b0353](https://linux-hardware.org/?probe=15fb1b0353) | May 30, 2022 |
| Dell          | Inspiron 7472               | [7d8d96d851](https://linux-hardware.org/?probe=7d8d96d851) | May 29, 2022 |
| ASUSTek       | UX51VZA                     | [c7c6e27cae](https://linux-hardware.org/?probe=c7c6e27cae) | May 29, 2022 |
| Dell          | Latitude E7470              | [159516aefb](https://linux-hardware.org/?probe=159516aefb) | May 29, 2022 |
| Acer          | Aspire E5-573G              | [bd9b967f9b](https://linux-hardware.org/?probe=bd9b967f9b) | May 29, 2022 |
| Dell          | XPS 15 9520                 | [75d345243e](https://linux-hardware.org/?probe=75d345243e) | May 29, 2022 |
| Notebook      | P65_P67SG                   | [a2aecd5cd3](https://linux-hardware.org/?probe=a2aecd5cd3) | May 29, 2022 |
| MSI           | GE60 2PE                    | [84d5af4ebe](https://linux-hardware.org/?probe=84d5af4ebe) | May 29, 2022 |
| MSI           | GE60 2PE                    | [c8d325a744](https://linux-hardware.org/?probe=c8d325a744) | May 29, 2022 |
| HP            | Pavilion 17                 | [077be5d10b](https://linux-hardware.org/?probe=077be5d10b) | May 28, 2022 |
| Dell          | Precision 7710              | [befe390051](https://linux-hardware.org/?probe=befe390051) | May 28, 2022 |
| Dell          | Vostro 5515                 | [ae8649e10b](https://linux-hardware.org/?probe=ae8649e10b) | May 28, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [4c4689f4b7](https://linux-hardware.org/?probe=4c4689f4b7) | May 28, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [df2d7a274d](https://linux-hardware.org/?probe=df2d7a274d) | May 28, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | [da2a67f904](https://linux-hardware.org/?probe=da2a67f904) | May 28, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [8d120a2350](https://linux-hardware.org/?probe=8d120a2350) | May 28, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [af42d8d0b4](https://linux-hardware.org/?probe=af42d8d0b4) | May 27, 2022 |
| Timi          | A35S                        | [8a1bee3210](https://linux-hardware.org/?probe=8a1bee3210) | May 27, 2022 |
| Dell          | XPS 15 9570                 | [93d1ebbb72](https://linux-hardware.org/?probe=93d1ebbb72) | May 27, 2022 |
| Login Info... | LOG-QAL30                   | [5643c9fb9b](https://linux-hardware.org/?probe=5643c9fb9b) | May 27, 2022 |
| Login Info... | LOG-QAL30                   | [644f3a8dbc](https://linux-hardware.org/?probe=644f3a8dbc) | May 27, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [983144763a](https://linux-hardware.org/?probe=983144763a) | May 27, 2022 |
| Lenovo        | 14w 81MQS02H00              | [e31087bfa9](https://linux-hardware.org/?probe=e31087bfa9) | May 27, 2022 |
| Dell          | Inspiron 7460               | [3171915433](https://linux-hardware.org/?probe=3171915433) | May 27, 2022 |
| Sony          | VPCEE3S1E                   | [f3c7988996](https://linux-hardware.org/?probe=f3c7988996) | May 27, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS3... | [88aabea122](https://linux-hardware.org/?probe=88aabea122) | May 27, 2022 |
| ASUSTek       | UX51VZA                     | [5507c9109e](https://linux-hardware.org/?probe=5507c9109e) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [9b4287fa8b](https://linux-hardware.org/?probe=9b4287fa8b) | May 26, 2022 |
| HP            | Pavilion TS 14              | [b7b3d504e2](https://linux-hardware.org/?probe=b7b3d504e2) | May 26, 2022 |
| Dell          | Inspiron 5502               | [90ee31b219](https://linux-hardware.org/?probe=90ee31b219) | May 26, 2022 |
| Dell          | XPS 13 7390                 | [4aa126f1e7](https://linux-hardware.org/?probe=4aa126f1e7) | May 26, 2022 |
| Dell          | Inspiron 3543               | [bf6cb72634](https://linux-hardware.org/?probe=bf6cb72634) | May 26, 2022 |
| HUAWEI        | HN-WX9X                     | [ebb7ce2605](https://linux-hardware.org/?probe=ebb7ce2605) | May 26, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ad9da27671](https://linux-hardware.org/?probe=ad9da27671) | May 26, 2022 |
| Samsung       | 550XDA                      | [807781d70e](https://linux-hardware.org/?probe=807781d70e) | May 26, 2022 |
| Acer          | Aspire E5-573G              | [6f5b6d8d03](https://linux-hardware.org/?probe=6f5b6d8d03) | May 25, 2022 |
| ASUSTek       | GL502VMK                    | [dfca615a89](https://linux-hardware.org/?probe=dfca615a89) | May 25, 2022 |
| HP            | Notebook                    | [05e785c8c2](https://linux-hardware.org/?probe=05e785c8c2) | May 25, 2022 |
| HP            | Notebook                    | [17ca21b3a4](https://linux-hardware.org/?probe=17ca21b3a4) | May 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [dcbaf5defc](https://linux-hardware.org/?probe=dcbaf5defc) | May 25, 2022 |
| HP            | Unknown                     | [c6b346ecc6](https://linux-hardware.org/?probe=c6b346ecc6) | May 25, 2022 |
| Lenovo        | ThinkPad W540 20BHS04B00    | [376f43287f](https://linux-hardware.org/?probe=376f43287f) | May 25, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [93c67e62e7](https://linux-hardware.org/?probe=93c67e62e7) | May 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [00baf8a2ff](https://linux-hardware.org/?probe=00baf8a2ff) | May 24, 2022 |
| ROCK Pi       | Unknown                     | [aa891c0178](https://linux-hardware.org/?probe=aa891c0178) | May 24, 2022 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [24c2ad0798](https://linux-hardware.org/?probe=24c2ad0798) | May 24, 2022 |
| Dell          | Precision 3561              | [71657d24c1](https://linux-hardware.org/?probe=71657d24c1) | May 24, 2022 |
| Dell          | Precision 3561              | [385a286d0d](https://linux-hardware.org/?probe=385a286d0d) | May 24, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [eccd990241](https://linux-hardware.org/?probe=eccd990241) | May 24, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1b061ef293](https://linux-hardware.org/?probe=1b061ef293) | May 24, 2022 |
| Lenovo        | ThinkPad W540 20BHS04B00    | [8d62205131](https://linux-hardware.org/?probe=8d62205131) | May 23, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1RS0... | [174f6e2270](https://linux-hardware.org/?probe=174f6e2270) | May 23, 2022 |
| ASUSTek       | X550CL                      | [49ebd9e68d](https://linux-hardware.org/?probe=49ebd9e68d) | May 23, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [377330c2b5](https://linux-hardware.org/?probe=377330c2b5) | May 23, 2022 |
| Dell          | Vostro 5490                 | [413a708e81](https://linux-hardware.org/?probe=413a708e81) | May 23, 2022 |
| Gigabyte      | P34V5                       | [6fa844b91e](https://linux-hardware.org/?probe=6fa844b91e) | May 23, 2022 |
| Gigabyte      | P34V5                       | [3ad8e4b239](https://linux-hardware.org/?probe=3ad8e4b239) | May 23, 2022 |
| Dell          | XPS 13 9310                 | [a76a3417d7](https://linux-hardware.org/?probe=a76a3417d7) | May 23, 2022 |
| Toshiba       | Unknown                     | [56ac954440](https://linux-hardware.org/?probe=56ac954440) | May 23, 2022 |
| Lenovo        | ThinkPad X230 2325AC7       | [bf82ad1cc3](https://linux-hardware.org/?probe=bf82ad1cc3) | May 23, 2022 |
| Sony          | VPCSA2Z9R                   | [5697622de7](https://linux-hardware.org/?probe=5697622de7) | May 22, 2022 |
| Lenovo        | ThinkPad X270 20HMS1QT0E    | [f17079bdce](https://linux-hardware.org/?probe=f17079bdce) | May 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [bdb9536c9c](https://linux-hardware.org/?probe=bdb9536c9c) | May 22, 2022 |
| Acer          | Swift SF514-52T             | [d49880e4c2](https://linux-hardware.org/?probe=d49880e4c2) | May 22, 2022 |
| Acer          | Swift SF514-52T             | [40d5ca6bab](https://linux-hardware.org/?probe=40d5ca6bab) | May 22, 2022 |
| HP            | 15-dc1018ur                 | [aceb1a1011](https://linux-hardware.org/?probe=aceb1a1011) | May 22, 2022 |
| Dell          | Inspiron 5567               | [afca2e1045](https://linux-hardware.org/?probe=afca2e1045) | May 22, 2022 |
| Lenovo        | ThinkPad W520 42763JF       | [2b87bae835](https://linux-hardware.org/?probe=2b87bae835) | May 22, 2022 |
| HP            | ProBook 470 G5              | [4be19d46e1](https://linux-hardware.org/?probe=4be19d46e1) | May 21, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [a44f38fd50](https://linux-hardware.org/?probe=a44f38fd50) | May 21, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [1c2288918d](https://linux-hardware.org/?probe=1c2288918d) | May 21, 2022 |
| HP            | Unknown                     | [2277c14d4d](https://linux-hardware.org/?probe=2277c14d4d) | May 21, 2022 |
| Dell          | XPS 13 9310                 | [06943bb7f1](https://linux-hardware.org/?probe=06943bb7f1) | May 21, 2022 |
| Acer          | Swift SF314-54              | [478550abf1](https://linux-hardware.org/?probe=478550abf1) | May 21, 2022 |
| Dell          | Latitude 5490               | [450756ee49](https://linux-hardware.org/?probe=450756ee49) | May 21, 2022 |
| HP            | Laptop 15s-eq1xxx           | [702e495c23](https://linux-hardware.org/?probe=702e495c23) | May 21, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [cc0b92bd45](https://linux-hardware.org/?probe=cc0b92bd45) | May 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [d5b9f1fd4a](https://linux-hardware.org/?probe=d5b9f1fd4a) | May 20, 2022 |
| HP            | Pavilion g4                 | [b29455a037](https://linux-hardware.org/?probe=b29455a037) | May 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [567c91351f](https://linux-hardware.org/?probe=567c91351f) | May 20, 2022 |
| HP            | Pavilion g4                 | [001f7d91d2](https://linux-hardware.org/?probe=001f7d91d2) | May 20, 2022 |
| Acer          | Aspire 8940G                | [f6f8622b30](https://linux-hardware.org/?probe=f6f8622b30) | May 20, 2022 |
| Google        | Glimmer                     | [78c39ceda9](https://linux-hardware.org/?probe=78c39ceda9) | May 20, 2022 |
| Dell          | Inspiron 5459               | [ea99252046](https://linux-hardware.org/?probe=ea99252046) | May 20, 2022 |
| Samsung       | 550XDA                      | [1f77e9f8f6](https://linux-hardware.org/?probe=1f77e9f8f6) | May 19, 2022 |
| Samsung       | 550XDA                      | [8c31783747](https://linux-hardware.org/?probe=8c31783747) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [e8df231af7](https://linux-hardware.org/?probe=e8df231af7) | May 19, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [711e483bb9](https://linux-hardware.org/?probe=711e483bb9) | May 19, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| eMachines     | E525                        | [2c397d4229](https://linux-hardware.org/?probe=2c397d4229) | May 19, 2022 |
| eMachines     | E525                        | [7a1e439150](https://linux-hardware.org/?probe=7a1e439150) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [0e0fc0905a](https://linux-hardware.org/?probe=0e0fc0905a) | May 19, 2022 |
| SKIKK         | GREEN 4                     | [f58c4904f7](https://linux-hardware.org/?probe=f58c4904f7) | May 19, 2022 |
| Toshiba       | Satellite U940              | [249374be01](https://linux-hardware.org/?probe=249374be01) | May 19, 2022 |
| Apple         | MacBookPro8,1               | [94d2bd3233](https://linux-hardware.org/?probe=94d2bd3233) | May 19, 2022 |
| Lenovo        | ThinkPad P52 20MAS3X200     | [7f0fc0c72e](https://linux-hardware.org/?probe=7f0fc0c72e) | May 19, 2022 |
| Lenovo        | ThinkPad P50 20EQS1DD00     | [819420bd66](https://linux-hardware.org/?probe=819420bd66) | May 19, 2022 |
| Lenovo        | ThinkPad P50 20EQS1DD00     | [479ab8b5d7](https://linux-hardware.org/?probe=479ab8b5d7) | May 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [592a32a1af](https://linux-hardware.org/?probe=592a32a1af) | May 18, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [e83ddc569f](https://linux-hardware.org/?probe=e83ddc569f) | May 18, 2022 |
| Dell          | XPS 13 7390                 | [98752f9fb4](https://linux-hardware.org/?probe=98752f9fb4) | May 18, 2022 |
| Dell          | Latitude E6420              | [0f06571934](https://linux-hardware.org/?probe=0f06571934) | May 18, 2022 |
| ASUSTek       | X556URK                     | [b217fd2c65](https://linux-hardware.org/?probe=b217fd2c65) | May 18, 2022 |
| Apple         | MacBookAir7,2               | [a46fea4edb](https://linux-hardware.org/?probe=a46fea4edb) | May 18, 2022 |
| Samsung       | 270E5G/270E5U               | [8d8783e43f](https://linux-hardware.org/?probe=8d8783e43f) | May 18, 2022 |
| Samsung       | 270E5G/270E5U               | [6e01c5c9f5](https://linux-hardware.org/?probe=6e01c5c9f5) | May 18, 2022 |
| Lenovo        | IdeaPad Y500 20193          | [a3931c5e60](https://linux-hardware.org/?probe=a3931c5e60) | May 17, 2022 |
| HP            | Laptop 15s-eq2xxx           | [9e7bf270db](https://linux-hardware.org/?probe=9e7bf270db) | May 17, 2022 |
| Dell          | Latitude E6230              | [1afeba4362](https://linux-hardware.org/?probe=1afeba4362) | May 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [f86ea538c8](https://linux-hardware.org/?probe=f86ea538c8) | May 17, 2022 |
| Dell          | Latitude 5520               | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [331099a3da](https://linux-hardware.org/?probe=331099a3da) | May 17, 2022 |
| Lenovo        | IdeaPad Slim 7 14ITL05 8... | [2179a16a87](https://linux-hardware.org/?probe=2179a16a87) | May 17, 2022 |
| Notebook      | N8xEJEK                     | [5c2c66e8f5](https://linux-hardware.org/?probe=5c2c66e8f5) | May 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [61c1716210](https://linux-hardware.org/?probe=61c1716210) | May 16, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [e99a8117ba](https://linux-hardware.org/?probe=e99a8117ba) | May 16, 2022 |
| Dell          | XPS 13 9350                 | [cf7f597752](https://linux-hardware.org/?probe=cf7f597752) | May 16, 2022 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [06afc33451](https://linux-hardware.org/?probe=06afc33451) | May 16, 2022 |
| Lenovo        | ThinkPad T440p 20AW000KU... | [66fc91a0d0](https://linux-hardware.org/?probe=66fc91a0d0) | May 16, 2022 |
| Dell          | XPS 15 7590                 | [7f7463682a](https://linux-hardware.org/?probe=7f7463682a) | May 16, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [1661f9e71d](https://linux-hardware.org/?probe=1661f9e71d) | May 16, 2022 |
| Acer          | Nitro AN515-45              | [2dac9974af](https://linux-hardware.org/?probe=2dac9974af) | May 16, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [ee54db9f9e](https://linux-hardware.org/?probe=ee54db9f9e) | May 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [a15788c695](https://linux-hardware.org/?probe=a15788c695) | May 15, 2022 |
| HP            | 250 G7 Notebook PC          | [4e824e7eac](https://linux-hardware.org/?probe=4e824e7eac) | May 15, 2022 |
| Positivo      | H14BU08                     | [ba7d402358](https://linux-hardware.org/?probe=ba7d402358) | May 15, 2022 |
| Lenovo        | V14-IIL 82C4                | [b95acee640](https://linux-hardware.org/?probe=b95acee640) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [a442279a0b](https://linux-hardware.org/?probe=a442279a0b) | May 15, 2022 |
| Acer          | Swift SF515-51T             | [3e3380c801](https://linux-hardware.org/?probe=3e3380c801) | May 15, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [6c635e0f3d](https://linux-hardware.org/?probe=6c635e0f3d) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [88c0d2c252](https://linux-hardware.org/?probe=88c0d2c252) | May 15, 2022 |
| Acer          | AO532h                      | [6055013560](https://linux-hardware.org/?probe=6055013560) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6adb7e22c5](https://linux-hardware.org/?probe=6adb7e22c5) | May 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [8c71a3bd1b](https://linux-hardware.org/?probe=8c71a3bd1b) | May 13, 2022 |
| HP            | EliteBook 8470p             | [2c8d1eec1e](https://linux-hardware.org/?probe=2c8d1eec1e) | May 13, 2022 |
| TUXEDO        | Pulse 14 Gen1               | [31d9027f23](https://linux-hardware.org/?probe=31d9027f23) | May 13, 2022 |
| HP            | EliteBook 8470p             | [074043a5ca](https://linux-hardware.org/?probe=074043a5ca) | May 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [ffbf67b890](https://linux-hardware.org/?probe=ffbf67b890) | May 12, 2022 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [deb6fa57ef](https://linux-hardware.org/?probe=deb6fa57ef) | May 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [7aaffeda48](https://linux-hardware.org/?probe=7aaffeda48) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [fc7562c140](https://linux-hardware.org/?probe=fc7562c140) | May 12, 2022 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [810fda94b1](https://linux-hardware.org/?probe=810fda94b1) | May 12, 2022 |
| Dell          | Latitude 5420               | [ac04d4cb5b](https://linux-hardware.org/?probe=ac04d4cb5b) | May 12, 2022 |
| ICL           | Unknown                     | [cfb2a7c82f](https://linux-hardware.org/?probe=cfb2a7c82f) | May 12, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [9baa4a9f57](https://linux-hardware.org/?probe=9baa4a9f57) | May 12, 2022 |
| Dell          | XPS 15 9500                 | [da0e4e32b4](https://linux-hardware.org/?probe=da0e4e32b4) | May 12, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [bbf4ef2a08](https://linux-hardware.org/?probe=bbf4ef2a08) | May 11, 2022 |
| Lenovo        | ThinkPad X395 20NL0007US    | [aea9571086](https://linux-hardware.org/?probe=aea9571086) | May 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [b0951956fa](https://linux-hardware.org/?probe=b0951956fa) | May 11, 2022 |
| Lenovo        | ThinkPad T480 20L6S5M40M    | [f2213829f0](https://linux-hardware.org/?probe=f2213829f0) | May 11, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [607c0a2833](https://linux-hardware.org/?probe=607c0a2833) | May 11, 2022 |
| Lenovo        | ThinkPad E570 20H5CTO1WW    | [a22c347eaf](https://linux-hardware.org/?probe=a22c347eaf) | May 11, 2022 |
| Lenovo        | ThinkPad T590 20N5S2NC0N    | [61327f1e21](https://linux-hardware.org/?probe=61327f1e21) | May 11, 2022 |
| Positivo      | C41TB                       | [2df08b295b](https://linux-hardware.org/?probe=2df08b295b) | May 11, 2022 |
| Lenovo        | Z50-70 20354                | [7dd92b7a41](https://linux-hardware.org/?probe=7dd92b7a41) | May 11, 2022 |
| Positivo      | C41TB                       | [164d3a45c4](https://linux-hardware.org/?probe=164d3a45c4) | May 11, 2022 |
| Lenovo        | B40-70 80F30017BR           | [352c705bf3](https://linux-hardware.org/?probe=352c705bf3) | May 11, 2022 |
| Lenovo        | B40-70 80F30017BR           | [cb100c3884](https://linux-hardware.org/?probe=cb100c3884) | May 11, 2022 |
| Dell          | Inspiron 3542               | [9762e9155b](https://linux-hardware.org/?probe=9762e9155b) | May 11, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | [6cacb1c49c](https://linux-hardware.org/?probe=6cacb1c49c) | May 11, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [a8c09f53de](https://linux-hardware.org/?probe=a8c09f53de) | May 10, 2022 |
| Acer          | Swift SF314-54              | [cc3411e0b4](https://linux-hardware.org/?probe=cc3411e0b4) | May 10, 2022 |
| Dell          | XPS 13 7390                 | [a5630f81ad](https://linux-hardware.org/?probe=a5630f81ad) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [03fc6852e2](https://linux-hardware.org/?probe=03fc6852e2) | May 10, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [20eb5bfb9f](https://linux-hardware.org/?probe=20eb5bfb9f) | May 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [2c069935d3](https://linux-hardware.org/?probe=2c069935d3) | May 10, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [a0dd43509d](https://linux-hardware.org/?probe=a0dd43509d) | May 09, 2022 |
| Standard      | Unknown                     | [3d9f8907fd](https://linux-hardware.org/?probe=3d9f8907fd) | May 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ef9c4b3841](https://linux-hardware.org/?probe=ef9c4b3841) | May 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [86acc529d3](https://linux-hardware.org/?probe=86acc529d3) | May 09, 2022 |
| LG Electro... | 16Z90P-K.AAS9U1             | [26536e15bf](https://linux-hardware.org/?probe=26536e15bf) | May 09, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [11cb46c902](https://linux-hardware.org/?probe=11cb46c902) | May 08, 2022 |
| Acer          | Aspire ES1-531              | [a7927b8b27](https://linux-hardware.org/?probe=a7927b8b27) | May 08, 2022 |
| ASUSTek       | N76VZ                       | [f1e06f5c2f](https://linux-hardware.org/?probe=f1e06f5c2f) | May 08, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [7894bd4591](https://linux-hardware.org/?probe=7894bd4591) | May 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [8fda480b12](https://linux-hardware.org/?probe=8fda480b12) | May 06, 2022 |
| Dell          | Precision 3520              | [2d5c4aa671](https://linux-hardware.org/?probe=2d5c4aa671) | May 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | [f255a41930](https://linux-hardware.org/?probe=f255a41930) | May 05, 2022 |
| Toshiba       | IS 1413G                    | [8ca57528af](https://linux-hardware.org/?probe=8ca57528af) | May 04, 2022 |
| Toshiba       | IS 1413G                    | [3bc61ca207](https://linux-hardware.org/?probe=3bc61ca207) | May 04, 2022 |
| HP            | Laptop 15s-eq2xxx           | [8fbc520a1b](https://linux-hardware.org/?probe=8fbc520a1b) | May 03, 2022 |
| ASUSTek       | N76VZ                       | [b9c2a28ba0](https://linux-hardware.org/?probe=b9c2a28ba0) | May 03, 2022 |
| HP            | Laptop 15s-eq1xxx           | [7636de5c44](https://linux-hardware.org/?probe=7636de5c44) | May 02, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [72f6ebfc11](https://linux-hardware.org/?probe=72f6ebfc11) | May 01, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [0205c9da07](https://linux-hardware.org/?probe=0205c9da07) | May 01, 2022 |
| Dell          | XPS 13 9310                 | [03b461596c](https://linux-hardware.org/?probe=03b461596c) | May 01, 2022 |
| Dell          | XPS 15 9570                 | [133b6670de](https://linux-hardware.org/?probe=133b6670de) | May 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [428509b262](https://linux-hardware.org/?probe=428509b262) | May 01, 2022 |
| Toshiba       | IS 1413G                    | [6d0ad0b8f2](https://linux-hardware.org/?probe=6d0ad0b8f2) | May 01, 2022 |
| HP            | Laptop 14-dq2xxx            | [6cefd4f4de](https://linux-hardware.org/?probe=6cefd4f4de) | May 01, 2022 |
| ASUSTek       | G75VX                       | [fb58cab830](https://linux-hardware.org/?probe=fb58cab830) | Apr 30, 2022 |
| HP            | ZBook Firefly 15 inch G8... | [6cdff366fa](https://linux-hardware.org/?probe=6cdff366fa) | Apr 28, 2022 |
| MSI           | Stealth GS66 12UGS          | [bf36d72c14](https://linux-hardware.org/?probe=bf36d72c14) | Apr 26, 2022 |
| Acer          | Nitro AN515-43              | [99527fd065](https://linux-hardware.org/?probe=99527fd065) | Apr 26, 2022 |
| MSI           | Stealth GS66 12UGS          | [273526bab2](https://linux-hardware.org/?probe=273526bab2) | Apr 26, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [620718bb9e](https://linux-hardware.org/?probe=620718bb9e) | Apr 26, 2022 |
| Acer          | Aspire A515-45              | [128cdc0a61](https://linux-hardware.org/?probe=128cdc0a61) | Apr 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [0d3c8ed904](https://linux-hardware.org/?probe=0d3c8ed904) | Apr 25, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [b4577b2374](https://linux-hardware.org/?probe=b4577b2374) | Apr 25, 2022 |
| Dell          | Latitude 7280               | [7ad22b030d](https://linux-hardware.org/?probe=7ad22b030d) | Apr 24, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | [762843e768](https://linux-hardware.org/?probe=762843e768) | Apr 23, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2HP0... | [11ec4d291b](https://linux-hardware.org/?probe=11ec4d291b) | Apr 23, 2022 |
| Dell          | Latitude E7450              | [5ce1623306](https://linux-hardware.org/?probe=5ce1623306) | Apr 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [b6a457c33a](https://linux-hardware.org/?probe=b6a457c33a) | Apr 21, 2022 |
| Wiltronic     | iVIEW i896QW                | [34e1873984](https://linux-hardware.org/?probe=34e1873984) | Apr 21, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [9e1d98199a](https://linux-hardware.org/?probe=9e1d98199a) | Apr 18, 2022 |
| Lenovo        | ThinkPad W530 2463A49       | [202b5d34a1](https://linux-hardware.org/?probe=202b5d34a1) | Apr 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [81b837dc13](https://linux-hardware.org/?probe=81b837dc13) | Apr 18, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [b895187681](https://linux-hardware.org/?probe=b895187681) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [6f75f679f9](https://linux-hardware.org/?probe=6f75f679f9) | Apr 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [5bff5642ba](https://linux-hardware.org/?probe=5bff5642ba) | Apr 15, 2022 |
| Toshiba       | Satellite U840              | [9468123a43](https://linux-hardware.org/?probe=9468123a43) | Apr 15, 2022 |
| Dell          | Studio 1537                 | [56c84908d2](https://linux-hardware.org/?probe=56c84908d2) | Apr 15, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [7436528d4f](https://linux-hardware.org/?probe=7436528d4f) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | [719a1712f2](https://linux-hardware.org/?probe=719a1712f2) | Apr 14, 2022 |
| Dell          | Inspiron 3505               | [5781ceb5ca](https://linux-hardware.org/?probe=5781ceb5ca) | Apr 14, 2022 |
| Dell          | Inspiron 5548               | [77a3c1a7ce](https://linux-hardware.org/?probe=77a3c1a7ce) | Apr 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [9dd2675f34](https://linux-hardware.org/?probe=9dd2675f34) | Apr 14, 2022 |
| Dell          | XPS 13 9370                 | [0175e41474](https://linux-hardware.org/?probe=0175e41474) | Apr 14, 2022 |
| Dell          | XPS 13 9305                 | [48c7781b77](https://linux-hardware.org/?probe=48c7781b77) | Apr 14, 2022 |
| Dell          | Precision 7540              | [2aff9a81ff](https://linux-hardware.org/?probe=2aff9a81ff) | Apr 13, 2022 |
| Toshiba       | Satellite U840              | [c6fe138c8f](https://linux-hardware.org/?probe=c6fe138c8f) | Apr 13, 2022 |
| HP            | Laptop 15-dw3xxx            | [95cff2fbb1](https://linux-hardware.org/?probe=95cff2fbb1) | Apr 13, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [c3d7c67155](https://linux-hardware.org/?probe=c3d7c67155) | Apr 12, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [73bb0eeab0](https://linux-hardware.org/?probe=73bb0eeab0) | Apr 12, 2022 |
| Intel         | W7650                       | [4bd778e810](https://linux-hardware.org/?probe=4bd778e810) | Apr 11, 2022 |
| MSI           | GS66 Stealth 10UH           | [5589b339ed](https://linux-hardware.org/?probe=5589b339ed) | Apr 11, 2022 |
| Dell          | Studio 1537                 | [048fceac96](https://linux-hardware.org/?probe=048fceac96) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5a60603c45](https://linux-hardware.org/?probe=5a60603c45) | Apr 11, 2022 |
| HP            | Pavilion 15                 | [c913cb5a4a](https://linux-hardware.org/?probe=c913cb5a4a) | Apr 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ff93a4d2f5](https://linux-hardware.org/?probe=ff93a4d2f5) | Apr 08, 2022 |
| Lenovo        | ThinkPad T495 20NJ000XIX    | [f00fb05977](https://linux-hardware.org/?probe=f00fb05977) | Apr 07, 2022 |
| MSI           | GS66 Stealth 10UH           | [bd6f031bc8](https://linux-hardware.org/?probe=bd6f031bc8) | Apr 06, 2022 |
| Acer          | Swift SF114-32              | [3947799e36](https://linux-hardware.org/?probe=3947799e36) | Apr 05, 2022 |
| MSI           | Prestige 14Evo A11M         | [29b43c3e27](https://linux-hardware.org/?probe=29b43c3e27) | Apr 05, 2022 |
| Acer          | Swift SF314-41              | [564cfd1f31](https://linux-hardware.org/?probe=564cfd1f31) | Apr 04, 2022 |
| Acer          | Aspire A515-45              | [eb69a7978b](https://linux-hardware.org/?probe=eb69a7978b) | Apr 04, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Chuwi         | Hi10 Go                     | [cfa6610288](https://linux-hardware.org/?probe=cfa6610288) | Apr 04, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [8c1841d2d0](https://linux-hardware.org/?probe=8c1841d2d0) | Apr 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5eef69398a](https://linux-hardware.org/?probe=5eef69398a) | Apr 03, 2022 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | [ba4863a7bb](https://linux-hardware.org/?probe=ba4863a7bb) | Apr 02, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [cd942b0305](https://linux-hardware.org/?probe=cd942b0305) | Apr 02, 2022 |
| Dell          | Inspiron 5548               | [9e35cab29a](https://linux-hardware.org/?probe=9e35cab29a) | Apr 02, 2022 |
| Dell          | XPS 13 9333                 | [f4fb42182f](https://linux-hardware.org/?probe=f4fb42182f) | Apr 01, 2022 |
| Lenovo        | ThinkPad L13 Gen 2 20VJS... | [4c0c1422e7](https://linux-hardware.org/?probe=4c0c1422e7) | Mar 31, 2022 |
| Lenovo        | ThinkPad X260 20F5S0HK1J    | [a83d3cbe5f](https://linux-hardware.org/?probe=a83d3cbe5f) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [cc95f0e3ab](https://linux-hardware.org/?probe=cc95f0e3ab) | Mar 31, 2022 |
| VALE          | Notebook Slim S132          | [138a4f1d68](https://linux-hardware.org/?probe=138a4f1d68) | Mar 31, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20STS... | [05c02cbe41](https://linux-hardware.org/?probe=05c02cbe41) | Mar 31, 2022 |
| Avell High... | B.ON                        | [697fc1d4ec](https://linux-hardware.org/?probe=697fc1d4ec) | Mar 29, 2022 |
| Framework     | Laptop                      | [a22656afee](https://linux-hardware.org/?probe=a22656afee) | Mar 28, 2022 |
| Dell          | XPS 17 9710                 | [461d175c44](https://linux-hardware.org/?probe=461d175c44) | Mar 28, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [16ac712c84](https://linux-hardware.org/?probe=16ac712c84) | Mar 24, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [917a6b65a8](https://linux-hardware.org/?probe=917a6b65a8) | Mar 10, 2022 |
| Sony          | VGN-FW21E                   | [930ce5581f](https://linux-hardware.org/?probe=930ce5581f) | Feb 25, 2022 |
| Unknown       | Unknown                     | [033354ee53](https://linux-hardware.org/?probe=033354ee53) | Jan 02, 2022 |
| Unknown       | Unknown                     | [ea795a97e1](https://linux-hardware.org/?probe=ea795a97e1) | Dec 26, 2021 |
| Unknown       | Unknown                     | [2b26e185d0](https://linux-hardware.org/?probe=2b26e185d0) | Dec 06, 2021 |
| Positivo      | CHT12CP                     | [53054c8f7a](https://linux-hardware.org/?probe=53054c8f7a) | Nov 20, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [1734da4566](https://linux-hardware.org/?probe=1734da4566) | Nov 13, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [2da0673527](https://linux-hardware.org/?probe=2da0673527) | Nov 01, 2021 |
| Notebook      | PCx0Dx                      | [b1a527acdc](https://linux-hardware.org/?probe=b1a527acdc) | Oct 11, 2021 |
| Notebook      | PCx0Dx                      | [90d4556fdf](https://linux-hardware.org/?probe=90d4556fdf) | Oct 11, 2021 |
| Unknown       | Unknown                     | [af4bbffabf](https://linux-hardware.org/?probe=af4bbffabf) | Sep 27, 2021 |
| Unknown       | Unknown                     | [81fd834473](https://linux-hardware.org/?probe=81fd834473) | Sep 26, 2021 |
| HP            | ProBook 4740s               | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| 5.17.5-300.fc36.x86_64                                        | 65        | 8.25%   |
| 5.18.13-200.fc36.x86_64                                       | 62        | 7.87%   |
| 5.18.11-200.fc36.x86_64                                       | 51        | 6.47%   |
| 5.17.11-300.fc36.x86_64                                       | 46        | 5.84%   |
| 5.18.16-200.fc36.x86_64                                       | 45        | 5.71%   |
| 5.17.6-300.fc36.x86_64                                        | 43        | 5.46%   |
| 5.18.5-200.fc36.x86_64                                        | 39        | 4.95%   |
| 5.17.13-300.fc36.x86_64                                       | 36        | 4.57%   |
| 5.18.17-200.fc36.x86_64                                       | 35        | 4.44%   |
| 5.17.8-300.fc36.x86_64                                        | 29        | 3.68%   |
| 5.18.9-200.fc36.x86_64                                        | 28        | 3.55%   |
| 5.17.12-300.fc36.x86_64                                       | 27        | 3.43%   |
| 5.18.6-200.fc36.x86_64                                        | 26        | 3.3%    |
| 5.17.7-300.fc36.x86_64                                        | 24        | 3.05%   |
| 5.18.7-200.fc36.x86_64                                        | 23        | 2.92%   |
| 5.18.10-200.fc36.x86_64                                       | 21        | 2.66%   |
| 5.17.9-300.fc36.x86_64                                        | 21        | 2.66%   |
| 5.18.18-200.fc36.x86_64                                       | 20        | 2.54%   |
| 5.18.19-200.fc36.x86_64                                       | 19        | 2.41%   |
| 5.19.4-200.fc36.x86_64                                        | 16        | 2.03%   |
| 5.17.1-300.fc36.x86_64                                        | 16        | 2.03%   |
| 5.17.3-302.fc36.x86_64                                        | 14        | 1.78%   |
| 5.17.2-300.fc36.x86_64                                        | 13        | 1.65%   |
| 5.17.0-0.rc7.116.fc36.x86_64                                  | 12        | 1.52%   |
| 5.18.15-200.fc36.x86_64                                       | 5         | 0.63%   |
| 5.17.14-300.fc36.x86_64                                       | 5         | 0.63%   |
| 5.18.5-201.fsync.fc36.x86_64                                  | 3         | 0.38%   |
| 5.18.1-200.fc36.x86_64                                        | 3         | 0.38%   |
| 5.17.0-300.fc36.x86_64                                        | 3         | 0.38%   |
| 5.18.10-201.fsync.fc36.x86_64                                 | 2         | 0.25%   |
| 5.17.5-301.fsync.fc36.x86_64                                  | 2         | 0.25%   |
| 5.17.0-0.rc5.102.fc36.x86_64                                  | 2         | 0.25%   |
| 5.19.4-250.vanilla.1.fc36.x86_64                              | 1         | 0.13%   |
| 5.19.2-300.fc36.x86_64                                        | 1         | 0.13%   |
| 5.19.1-xm1.0e20220803.fc36.x86_64                             | 1         | 0.13%   |
| 5.19.1-325.vanilla.1.fc36.x86_64                              | 1         | 0.13%   |
| 5.19.1-300.fc36.x86_64                                        | 1         | 0.13%   |
| 5.19.0-xm2.0.fc36.x86_64                                      | 1         | 0.13%   |
| 5.19.0-xm1.0e20220803.fc36.x86_64                             | 1         | 0.13%   |
| 5.18.8-200.fc36.x86_64                                        | 1         | 0.13%   |
| 5.18.5-250.vanilla.1.fc36.x86_64                              | 1         | 0.13%   |
| 5.18.4-xm1.0.fc36.x86_64                                      | 1         | 0.13%   |
| 5.18.4-125.vanilla.1.fc36.x86_64                              | 1         | 0.13%   |
| 5.18.2-200.fc36.x86_64                                        | 1         | 0.13%   |
| 5.18.18-201.fsync.fc36.x86_64                                 | 1         | 0.13%   |
| 5.18.18-200.rog.fc36.x86_64                                   | 1         | 0.13%   |
| 5.18.18-200.local.fc36.x86_64                                 | 1         | 0.13%   |
| 5.18.16-602.inttf.fc36.x86_64                                 | 1         | 0.13%   |
| 5.18.10-250.vanilla.1.fc36.x86_64                             | 1         | 0.13%   |
| 5.18.0-0.rc3.220422.d569e86915b7f2f.31.vanilla.1.fc36.x86_64  | 1         | 0.13%   |
| 5.17.7-301.fsync.fc36.x86_64                                  | 1         | 0.13%   |
| 5.17.4-300.fc36.x86_64                                        | 1         | 0.13%   |
| 5.17.3-301.fsync.fc36.x86_64                                  | 1         | 0.13%   |
| 5.16.9-200.rog.fc35.x86_64                                    | 1         | 0.13%   |
| 5.16.9-200.fc35.x86_64                                        | 1         | 0.13%   |
| 5.16.16-200.fc35.x86_64                                       | 1         | 0.13%   |
| 5.16.0-0.rc7.20211231git4f3d93c6eaff.52.vanilla.1.fc36.x86_64 | 1         | 0.13%   |
| 5.15.0-60.fc36.x86_64                                         | 1         | 0.13%   |
| 5.15.0-0.rc7.20211028git1fc596a56b33.56.fc36.x86_64           | 1         | 0.13%   |
| 5.15.0-0.rc4.20211008git1da38549dd64.36.fc36.x86_64           | 1         | 0.13%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.17.5  | 67        | 8.5%    |
| 5.18.13 | 62        | 7.87%   |
| 5.18.11 | 51        | 6.47%   |
| 5.18.16 | 46        | 5.84%   |
| 5.17.11 | 46        | 5.84%   |
| 5.18.5  | 43        | 5.46%   |
| 5.17.6  | 43        | 5.46%   |
| 5.17.13 | 36        | 4.57%   |
| 5.18.17 | 35        | 4.44%   |
| 5.17.8  | 29        | 3.68%   |
| 5.18.9  | 28        | 3.55%   |
| 5.17.12 | 27        | 3.43%   |
| 5.18.6  | 26        | 3.3%    |
| 5.17.7  | 25        | 3.17%   |
| 5.18.10 | 24        | 3.05%   |
| 5.18.7  | 23        | 2.92%   |
| 5.18.18 | 23        | 2.92%   |
| 5.17.9  | 21        | 2.66%   |
| 5.18.19 | 19        | 2.41%   |
| 5.19.4  | 17        | 2.16%   |
| 5.17.0  | 17        | 2.16%   |
| 5.17.1  | 16        | 2.03%   |
| 5.17.3  | 15        | 1.9%    |
| 5.17.2  | 13        | 1.65%   |
| 5.18.15 | 5         | 0.63%   |
| 5.17.14 | 5         | 0.63%   |
| 5.15.0  | 5         | 0.63%   |
| 5.19.1  | 3         | 0.38%   |
| 5.18.1  | 3         | 0.38%   |
| 5.19.0  | 2         | 0.25%   |
| 5.18.4  | 2         | 0.25%   |
| 5.16.9  | 2         | 0.25%   |
| 5.19.2  | 1         | 0.13%   |
| 5.18.8  | 1         | 0.13%   |
| 5.18.2  | 1         | 0.13%   |
| 5.18.0  | 1         | 0.13%   |
| 5.17.4  | 1         | 0.13%   |
| 5.16.16 | 1         | 0.13%   |
| 5.16.0  | 1         | 0.13%   |
| 5.14.14 | 1         | 0.13%   |
| 5.14.10 | 1         | 0.13%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.18    | 372       | 49.21%  |
| 5.17    | 350       | 46.3%   |
| 5.19    | 23        | 3.04%   |
| 5.15    | 5         | 0.66%   |
| 5.16    | 4         | 0.53%   |
| 5.14    | 2         | 0.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 730       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 576       | 78.37%  |
| KDE5          | 101       | 13.74%  |
| Unknown       | 18        | 2.45%   |
| XFCE          | 10        | 1.36%   |
| X-Cinnamon    | 8         | 1.09%   |
| i3            | 6         | 0.82%   |
| Cinnamon      | 4         | 0.54%   |
| MATE          | 3         | 0.41%   |
| LXQt          | 2         | 0.27%   |
| awesome       | 2         | 0.27%   |
| sway          | 1         | 0.14%   |
| openbox       | 1         | 0.14%   |
| GNOME Classic | 1         | 0.14%   |
| Deepin        | 1         | 0.14%   |
| bspwm         | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 564       | 76.42%  |
| X11     | 161       | 21.82%  |
| Unknown | 10        | 1.36%   |
| Tty     | 3         | 0.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 378       | 51.57%  |
| GDM     | 270       | 36.83%  |
| SDDM    | 52        | 7.09%   |
| LightDM | 32        | 4.37%   |
| Ly      | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 416       | 56.91%  |
| ru_RU   | 49        | 6.7%    |
| en_GB   | 35        | 4.79%   |
| pt_BR   | 32        | 4.38%   |
| de_DE   | 28        | 3.83%   |
| fr_FR   | 17        | 2.33%   |
| pl_PL   | 16        | 2.19%   |
| it_IT   | 14        | 1.92%   |
| en_AU   | 14        | 1.92%   |
| es_MX   | 10        | 1.37%   |
| en_IN   | 10        | 1.37%   |
| es_ES   | 8         | 1.09%   |
| es_CL   | 6         | 0.82%   |
| en_CA   | 5         | 0.68%   |
| tr_TR   | 4         | 0.55%   |
| pt_PT   | 4         | 0.55%   |
| nl_NL   | 4         | 0.55%   |
| de_AT   | 4         | 0.55%   |
| sv_SE   | 3         | 0.41%   |
| ru_UA   | 3         | 0.41%   |
| hu_HU   | 3         | 0.41%   |
| es_AR   | 3         | 0.41%   |
| en_NZ   | 3         | 0.41%   |
| cs_CZ   | 3         | 0.41%   |
| nl_BE   | 2         | 0.27%   |
| hr_HR   | 2         | 0.27%   |
| fr_BE   | 2         | 0.27%   |
| en_ZA   | 2         | 0.27%   |
| en_IL   | 2         | 0.27%   |
| de_CH   | 2         | 0.27%   |
| da_DK   | 2         | 0.27%   |
| Unknown | 2         | 0.27%   |
| zh_CN   | 1         | 0.14%   |
| sr_RS   | 1         | 0.14%   |
| nb_NO   | 1         | 0.14%   |
| id_ID   | 1         | 0.14%   |
| gl_ES   | 1         | 0.14%   |
| ga_IE   | 1         | 0.14%   |
| fr_CA   | 1         | 0.14%   |
| es_VE   | 1         | 0.14%   |
| es_UY   | 1         | 0.14%   |
| es_SV   | 1         | 0.14%   |
| es_GT   | 1         | 0.14%   |
| es_EC   | 1         | 0.14%   |
| es_CO   | 1         | 0.14%   |
| es_BO   | 1         | 0.14%   |
| en_PH   | 1         | 0.14%   |
| en_NL   | 1         | 0.14%   |
| en_IE   | 1         | 0.14%   |
| en_DK   | 1         | 0.14%   |
| el_GR   | 1         | 0.14%   |
| ca_ES   | 1         | 0.14%   |
| ba_RU   | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 622       | 84.86%  |
| BIOS | 111       | 15.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 593       | 81.23%  |
| Ext4    | 126       | 17.26%  |
| Xfs     | 8         | 1.1%    |
| F2fs    | 2         | 0.27%   |
| Unknown | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 386       | 52.59%  |
| GPT     | 317       | 43.19%  |
| MBR     | 31        | 4.22%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 658       | 90.01%  |
| Yes       | 73        | 9.99%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 580       | 79.23%  |
| Yes       | 152       | 20.77%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 221       | 30.27%  |
| Hewlett-Packard        | 125       | 17.12%  |
| Dell                   | 103       | 14.11%  |
| ASUSTek Computer       | 79        | 10.82%  |
| Acer                   | 40        | 5.48%   |
| Apple                  | 21        | 2.88%   |
| MSI                    | 20        | 2.74%   |
| HUAWEI                 | 13        | 1.78%   |
| Toshiba                | 8         | 1.1%    |
| Sony                   | 7         | 0.96%   |
| Samsung Electronics    | 7         | 0.96%   |
| Notebook               | 7         | 0.96%   |
| Framework              | 6         | 0.82%   |
| Timi                   | 5         | 0.68%   |
| Unknown                | 5         | 0.68%   |
| Positivo               | 4         | 0.55%   |
| Gigabyte Technology    | 4         | 0.55%   |
| Panasonic              | 3         | 0.41%   |
| GPU Company            | 3         | 0.41%   |
| Google                 | 3         | 0.41%   |
| Alienware              | 3         | 0.41%   |
| VALE                   | 2         | 0.27%   |
| System76               | 2         | 0.27%   |
| LG Electronics         | 2         | 0.27%   |
| HONOR                  | 2         | 0.27%   |
| Gateway                | 2         | 0.27%   |
| Fujitsu                | 2         | 0.27%   |
| Chuwi                  | 2         | 0.27%   |
| Avell High Performance | 2         | 0.27%   |
| Wiltronic              | 1         | 0.14%   |
| VIT                    | 1         | 0.14%   |
| UNOWHY                 | 1         | 0.14%   |
| TUXEDO                 | 1         | 0.14%   |
| Standard               | 1         | 0.14%   |
| SLIMBOOK               | 1         | 0.14%   |
| SKIKK                  | 1         | 0.14%   |
| ROCK Pi                | 1         | 0.14%   |
| Pegatron               | 1         | 0.14%   |
| Packard Bell           | 1         | 0.14%   |
| Micro Electronics      | 1         | 0.14%   |
| Login Informatica      | 1         | 0.14%   |
| Itautec                | 1         | 0.14%   |
| IT Channel Pty         | 1         | 0.14%   |
| Infinix                | 1         | 0.14%   |
| ICL                    | 1         | 0.14%   |
| GPD                    | 1         | 0.14%   |
| Getac                  | 1         | 0.14%   |
| GEO                    | 1         | 0.14%   |
| Exo                    | 1         | 0.14%   |
| eMachines              | 1         | 0.14%   |
| Eluktronics            | 1         | 0.14%   |
| Clevo                  | 1         | 0.14%   |
| AZW                    | 1         | 0.14%   |
| AXDIA International    | 1         | 0.14%   |
| Aquarius               | 1         | 0.14%   |
| Acidanthera            | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown                                | 11        | 1.51%   |
| Framework Laptop                       | 6         | 0.82%   |
| HP Notebook                            | 5         | 0.68%   |
| Lenovo ThinkBook 15 G2 ITL 20VE        | 4         | 0.55%   |
| Lenovo IdeaPad 5 15ARE05 81YQ          | 4         | 0.55%   |
| Lenovo IdeaPad 3 15ITL6 82H8           | 4         | 0.55%   |
| HP Pavilion g6                         | 4         | 0.55%   |
| HP EliteBook 8470p                     | 4         | 0.55%   |
| Lenovo ThinkBook 16p Gen 2 20YM        | 3         | 0.41%   |
| Lenovo ThinkBook 14 G3 ACL 21A2        | 3         | 0.41%   |
| Lenovo IdeaPad S340-14API 81NB         | 3         | 0.41%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY   | 3         | 0.41%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7       | 3         | 0.41%   |
| Lenovo IdeaPad 5 14ARE05 81YM          | 3         | 0.41%   |
| HP Pavilion Laptop 15-cs0xxx           | 3         | 0.41%   |
| HP Pavilion Aero Laptop 13-be0xxx      | 3         | 0.41%   |
| Dell XPS 15 9570                       | 3         | 0.41%   |
| Dell XPS 13 9310                       | 3         | 0.41%   |
| ASUS ROG Zephyrus G14 GA402RJ_GA402RJ  | 3         | 0.41%   |
| ASUS ROG Strix G513QY_G513QY           | 3         | 0.41%   |
| Timi Redmi Book Pro 15 2022            | 2         | 0.27%   |
| Timi A35S                              | 2         | 0.27%   |
| Samsung 550XDA                         | 2         | 0.27%   |
| MSI Modern 14 A10RAS                   | 2         | 0.27%   |
| Lenovo IdeaPad 530S-14IKB 81EU         | 2         | 0.27%   |
| Lenovo IdeaPad 5 14ALC05 82LM          | 2         | 0.27%   |
| Lenovo IdeaPad 3 15ARE05 81W4          | 2         | 0.27%   |
| HUAWEI MACH-WX9                        | 2         | 0.27%   |
| HUAWEI KLVL-WXXW                       | 2         | 0.27%   |
| HUAWEI KLVL-WXX9                       | 2         | 0.27%   |
| HP ZBook Fury 15 G7 Mobile Workstation | 2         | 0.27%   |
| HP ZBook 17 G5                         | 2         | 0.27%   |
| HP ProBook 650 G1                      | 2         | 0.27%   |
| HP ProBook 470 G5                      | 2         | 0.27%   |
| HP Pavilion Laptop 15-cw1xxx           | 2         | 0.27%   |
| HP Pavilion 17                         | 2         | 0.27%   |
| HP Laptop 17-cp0xxx                    | 2         | 0.27%   |
| HP Laptop 15s-fq2xxx                   | 2         | 0.27%   |
| HP Laptop 15-da0xxx                    | 2         | 0.27%   |
| HP EliteBook 8460p                     | 2         | 0.27%   |
| HP 250 G7 Notebook PC                  | 2         | 0.27%   |
| GPU Company GWNR51416                  | 2         | 0.27%   |
| Dell XPS 17 9710                       | 2         | 0.27%   |
| Dell XPS 15 9560                       | 2         | 0.27%   |
| Dell XPS 15 9520                       | 2         | 0.27%   |
| Dell XPS 15 9510                       | 2         | 0.27%   |
| Dell XPS 15 9500                       | 2         | 0.27%   |
| Dell XPS 13 9370                       | 2         | 0.27%   |
| Dell XPS 13 9350                       | 2         | 0.27%   |
| Dell XPS 13 7390                       | 2         | 0.27%   |
| Dell Latitude E7470                    | 2         | 0.27%   |
| Dell Latitude E6520                    | 2         | 0.27%   |
| Dell Latitude E6420                    | 2         | 0.27%   |
| Dell Latitude E6230                    | 2         | 0.27%   |
| Dell Inspiron 7472                     | 2         | 0.27%   |
| Dell Inspiron 7460                     | 2         | 0.27%   |
| Dell Inspiron 5567                     | 2         | 0.27%   |
| Dell Inspiron 3542                     | 2         | 0.27%   |
| Dell G3 3590                           | 2         | 0.27%   |
| ASUS X541NA                            | 2         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 110       | 15.07%  |
| Lenovo IdeaPad        | 67        | 9.18%   |
| Dell Inspiron         | 32        | 4.38%   |
| HP Pavilion           | 28        | 3.84%   |
| Dell XPS              | 27        | 3.7%    |
| Dell Latitude         | 25        | 3.42%   |
| ASUS ROG              | 23        | 3.15%   |
| HP Laptop             | 21        | 2.88%   |
| Acer Aspire           | 21        | 2.88%   |
| HP ProBook            | 18        | 2.47%   |
| HP EliteBook          | 16        | 2.19%   |
| Lenovo ThinkBook      | 14        | 1.92%   |
| ASUS VivoBook         | 14        | 1.92%   |
| Dell Precision        | 12        | 1.64%   |
| Unknown               | 11        | 1.51%   |
| HP ZBook              | 10        | 1.37%   |
| Lenovo Legion         | 8         | 1.1%    |
| ASUS ASUS             | 7         | 0.96%   |
| Acer Swift            | 7         | 0.96%   |
| Toshiba Satellite     | 6         | 0.82%   |
| HP ENVY               | 6         | 0.82%   |
| Framework Laptop      | 6         | 0.82%   |
| Acer Nitro            | 6         | 0.82%   |
| MSI Modern            | 5         | 0.68%   |
| Lenovo Yoga           | 5         | 0.68%   |
| HP Notebook           | 5         | 0.68%   |
| ASUS Zenbook          | 4         | 0.55%   |
| ASUS TUF              | 4         | 0.55%   |
| MSI Prestige          | 3         | 0.41%   |
| HP OMEN               | 3         | 0.41%   |
| HP 250                | 3         | 0.41%   |
| Dell Vostro           | 3         | 0.41%   |
| Dell G3               | 3         | 0.41%   |
| Apple MacBookPro8     | 3         | 0.41%   |
| Apple MacBookPro5     | 3         | 0.41%   |
| VALE Notebook         | 2         | 0.27%   |
| Timi Redmi            | 2         | 0.27%   |
| Timi A35S             | 2         | 0.27%   |
| Samsung 550XDA        | 2         | 0.27%   |
| MSI GF63              | 2         | 0.27%   |
| HUAWEI MACH-WX9       | 2         | 0.27%   |
| HUAWEI KLVL-WXXW      | 2         | 0.27%   |
| HUAWEI KLVL-WXX9      | 2         | 0.27%   |
| HP Victus             | 2         | 0.27%   |
| HP Compaq             | 2         | 0.27%   |
| HP 255                | 2         | 0.27%   |
| GPU Company GWNR51416 | 2         | 0.27%   |
| Fujitsu LIFEBOOK      | 2         | 0.27%   |
| ASUS Zephyrus         | 2         | 0.27%   |
| ASUS X541NA           | 2         | 0.27%   |
| Apple MacBookPro12    | 2         | 0.27%   |
| Apple MacBookPro10    | 2         | 0.27%   |
| Apple MacBookAir6     | 2         | 0.27%   |
| Alienware x17         | 2         | 0.27%   |
| Acer Predator         | 2         | 0.27%   |
| Wiltronic iVIEW       | 1         | 0.14%   |
| VIT M2420             | 1         | 0.14%   |
| UNOWHY Y13G010S4EI    | 1         | 0.14%   |
| TUXEDO Pulse          | 1         | 0.14%   |
| Toshiba TECRA         | 1         | 0.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 156       | 21.37%  |
| 2020 | 118       | 16.16%  |
| 2019 | 74        | 10.14%  |
| 2018 | 69        | 9.45%   |
| 2015 | 39        | 5.34%   |
| 2017 | 38        | 5.21%   |
| 2013 | 38        | 5.21%   |
| 2012 | 36        | 4.93%   |
| 2022 | 35        | 4.79%   |
| 2011 | 35        | 4.79%   |
| 2016 | 34        | 4.66%   |
| 2014 | 30        | 4.11%   |
| 2010 | 10        | 1.37%   |
| 2009 | 9         | 1.23%   |
| 2008 | 8         | 1.1%    |
| 2006 | 1         | 0.14%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 730       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 571       | 78.01%  |
| Enabled  | 161       | 21.99%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 725       | 99.32%  |
| Yes  | 5         | 0.68%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 234       | 31.97%  |
| 8.01-16.0   | 159       | 21.72%  |
| 16.01-24.0  | 144       | 19.67%  |
| 32.01-64.0  | 90        | 12.3%   |
| 3.01-4.0    | 64        | 8.74%   |
| 64.01-256.0 | 17        | 2.32%   |
| 24.01-32.0  | 12        | 1.64%   |
| 1.01-2.0    | 11        | 1.5%    |
| 2.01-3.0    | 1         | 0.14%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 229       | 29.93%  |
| 2.01-3.0   | 208       | 27.19%  |
| 3.01-4.0   | 194       | 25.36%  |
| 1.01-2.0   | 84        | 10.98%  |
| 8.01-16.0  | 42        | 5.49%   |
| 0.51-1.0   | 4         | 0.52%   |
| 24.01-32.0 | 2         | 0.26%   |
| 16.01-24.0 | 2         | 0.26%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 540       | 73.57%  |
| 2      | 168       | 22.89%  |
| 3      | 21        | 2.86%   |
| 4      | 3         | 0.41%   |
| 5      | 1         | 0.14%   |
| 0      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 585       | 80.14%  |
| Yes       | 145       | 19.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 509       | 69.73%  |
| No        | 221       | 30.27%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 719       | 98.49%  |
| No        | 11        | 1.51%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 642       | 87.59%  |
| No        | 91        | 12.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Notebooks | Percent |
|--------------------|-----------|---------|
| USA                | 143       | 19.46%  |
| Russia             | 60        | 8.16%   |
| Germany            | 45        | 6.12%   |
| Brazil             | 44        | 5.99%   |
| India              | 35        | 4.76%   |
| Italy              | 29        | 3.95%   |
| Poland             | 26        | 3.54%   |
| Netherlands        | 21        | 2.86%   |
| Mexico             | 21        | 2.86%   |
| France             | 21        | 2.86%   |
| UK                 | 19        | 2.59%   |
| Australia          | 18        | 2.45%   |
| Turkey             | 16        | 2.18%   |
| Spain              | 14        | 1.9%    |
| Indonesia          | 14        | 1.9%    |
| Belgium            | 10        | 1.36%   |
| Argentina          | 10        | 1.36%   |
| Canada             | 9         | 1.22%   |
| Sweden             | 7         | 0.95%   |
| Portugal           | 7         | 0.95%   |
| Chile              | 7         | 0.95%   |
| Austria            | 7         | 0.95%   |
| Switzerland        | 6         | 0.82%   |
| Romania            | 6         | 0.82%   |
| Hungary            | 6         | 0.82%   |
| Czechia            | 6         | 0.82%   |
| Norway             | 5         | 0.68%   |
| Ireland            | 5         | 0.68%   |
| Denmark            | 5         | 0.68%   |
| Croatia            | 5         | 0.68%   |
| Ukraine            | 4         | 0.54%   |
| Taiwan             | 4         | 0.54%   |
| Philippines        | 4         | 0.54%   |
| Japan              | 4         | 0.54%   |
| Israel             | 4         | 0.54%   |
| Egypt              | 4         | 0.54%   |
| Colombia           | 4         | 0.54%   |
| Bulgaria           | 4         | 0.54%   |
| Belarus            | 4         | 0.54%   |
| South Africa       | 3         | 0.41%   |
| Slovakia           | 3         | 0.41%   |
| Singapore          | 3         | 0.41%   |
| Moldova            | 3         | 0.41%   |
| Kenya              | 3         | 0.41%   |
| Venezuela          | 2         | 0.27%   |
| Uzbekistan         | 2         | 0.27%   |
| Uruguay            | 2         | 0.27%   |
| New Zealand        | 2         | 0.27%   |
| Nepal              | 2         | 0.27%   |
| Lithuania          | 2         | 0.27%   |
| Lebanon            | 2         | 0.27%   |
| Kazakhstan         | 2         | 0.27%   |
| Iran               | 2         | 0.27%   |
| Iceland            | 2         | 0.27%   |
| Hong Kong          | 2         | 0.27%   |
| Guatemala          | 2         | 0.27%   |
| Finland            | 2         | 0.27%   |
| Estonia            | 2         | 0.27%   |
| El Salvador        | 2         | 0.27%   |
| Dominican Republic | 2         | 0.27%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Moscow             | 15        | 1.99%   |
| St Petersburg      | 14        | 1.85%   |
| Warsaw             | 8         | 1.06%   |
| Sao Paulo          | 8         | 1.06%   |
| Melbourne          | 8         | 1.06%   |
| Istanbul           | 8         | 1.06%   |
| Munich             | 6         | 0.79%   |
| Mexico City        | 5         | 0.66%   |
| Kolkata            | 5         | 0.66%   |
| Budapest           | 5         | 0.66%   |
| Berlin             | 5         | 0.66%   |
| Bengaluru          | 5         | 0.66%   |
| Sofia              | 4         | 0.53%   |
| Santiago           | 4         | 0.53%   |
| Rome               | 4         | 0.53%   |
| Prague             | 4         | 0.53%   |
| Paris              | 4         | 0.53%   |
| Oslo               | 4         | 0.53%   |
| New York           | 4         | 0.53%   |
| Mundelein          | 4         | 0.53%   |
| Minsk              | 4         | 0.53%   |
| Amsterdam          | 4         | 0.53%   |
| Zurich             | 3         | 0.4%    |
| Zagreb             | 3         | 0.4%    |
| Vienna             | 3         | 0.4%    |
| Surabaya           | 3         | 0.4%    |
| Stockholm          | 3         | 0.4%    |
| Southampton        | 3         | 0.4%    |
| Singapore          | 3         | 0.4%    |
| Nairobi            | 3         | 0.4%    |
| Jakarta            | 3         | 0.4%    |
| Izmir              | 3         | 0.4%    |
| Guadalajara        | 3         | 0.4%    |
| Dublin             | 3         | 0.4%    |
| Denver             | 3         | 0.4%    |
| Copenhagen         | 3         | 0.4%    |
| Chennai            | 3         | 0.4%    |
| Cairo              | 3         | 0.4%    |
| Bursa              | 3         | 0.4%    |
| Buenos Aires       | 3         | 0.4%    |
| Bogotá            | 3         | 0.4%    |
| Bogor              | 3         | 0.4%    |
| Yaroslavl          | 2         | 0.26%   |
| Volgograd          | 2         | 0.26%   |
| Vilnius            | 2         | 0.26%   |
| Vijayawada         | 2         | 0.26%   |
| Tyumen             | 2         | 0.26%   |
| Tokyo              | 2         | 0.26%   |
| Tashkent           | 2         | 0.26%   |
| Tallinn            | 2         | 0.26%   |
| Sydney             | 2         | 0.26%   |
| Springboro         | 2         | 0.26%   |
| Seattle            | 2         | 0.26%   |
| Santo Domingo Este | 2         | 0.26%   |
| San Diego          | 2         | 0.26%   |
| Samara             | 2         | 0.26%   |
| Salvador           | 2         | 0.26%   |
| Rotterdam          | 2         | 0.26%   |
| Rostov-on-Don      | 2         | 0.26%   |
| Rosario            | 2         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 186       | 220    | 20.33%  |
| WDC                            | 87        | 97     | 9.51%   |
| Seagate                        | 68        | 71     | 7.43%   |
| SanDisk                        | 65        | 73     | 7.1%    |
| SK hynix                       | 52        | 57     | 5.68%   |
| Toshiba                        | 45        | 50     | 4.92%   |
| Unknown                        | 43        | 52     | 4.7%    |
| Kingston                       | 39        | 43     | 4.26%   |
| Micron Technology              | 38        | 43     | 4.15%   |
| Intel                          | 37        | 47     | 4.04%   |
| Crucial                        | 27        | 29     | 2.95%   |
| KIOXIA                         | 21        | 27     | 2.3%    |
| HGST                           | 15        | 16     | 1.64%   |
| A-DATA Technology              | 14        | 15     | 1.53%   |
| Phison                         | 13        | 13     | 1.42%   |
| Apple                          | 11        | 12     | 1.2%    |
| Silicon Motion                 | 10        | 10     | 1.09%   |
| Hitachi                        | 9         | 9      | 0.98%   |
| Unknown                        | 8         | 8      | 0.87%   |
| SSSTC                          | 7         | 7      | 0.77%   |
| LITEON                         | 7         | 7      | 0.77%   |
| PNY                            | 6         | 7      | 0.66%   |
| XPG                            | 5         | 9      | 0.55%   |
| UMIS                           | 5         | 6      | 0.55%   |
| China                          | 5         | 6      | 0.55%   |
| SABRENT                        | 4         | 4      | 0.44%   |
| Patriot                        | 4         | 5      | 0.44%   |
| Netac                          | 4         | 4      | 0.44%   |
| Lenovo                         | 4         | 5      | 0.44%   |
| Intenso                        | 4         | 4      | 0.44%   |
| Union Memory (Shenzhen)        | 3         | 3      | 0.33%   |
| Transcend                      | 3         | 3      | 0.33%   |
| Solid State Storage Technology | 3         | 3      | 0.33%   |
| Lexar                          | 3         | 3      | 0.33%   |
| Fujitsu                        | 3         | 3      | 0.33%   |
| Team                           | 2         | 2      | 0.22%   |
| LITEONIT                       | 2         | 2      | 0.22%   |
| Lite-On                        | 2         | 2      | 0.22%   |
| KingFast                       | 2         | 3      | 0.22%   |
| JMicron Technology             | 2         | 2      | 0.22%   |
| GOODRAM                        | 2         | 4      | 0.22%   |
| Gigabyte Technology            | 2         | 3      | 0.22%   |
| GALAX                          | 2         | 2      | 0.22%   |
| ADATA Technology               | 2         | 2      | 0.22%   |
| Win Memory                     | 1         | 1      | 0.11%   |
| WDC WDS2                       | 1         | 1      | 0.11%   |
| Vaseky                         | 1         | 1      | 0.11%   |
| USB3.0                         | 1         | 1      | 0.11%   |
| Teclast                        | 1         | 1      | 0.11%   |
| T-FORCE                        | 1         | 1      | 0.11%   |
| StoreJet                       | 1         | 1      | 0.11%   |
| SPCC                           | 1         | 1      | 0.11%   |
| ROG                            | 1         | 1      | 0.11%   |
| Realtek Semiconductor          | 1         | 1      | 0.11%   |
| RCESSD                         | 1         | 1      | 0.11%   |
| Phison Electronics             | 1         | 1      | 0.11%   |
| Origin                         | 1         | 1      | 0.11%   |
| OCZ-VERTEX3                    | 1         | 1      | 0.11%   |
| OCZ                            | 1         | 1      | 0.11%   |
| new                            | 1         | 1      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| SanDisk NVMe SSD Drive 512GB              | 20        | 2.11%   |
| Samsung NVMe SSD Drive 512GB              | 18        | 1.9%    |
| Samsung NVMe SSD Drive 256GB              | 16        | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB            | 13        | 1.37%   |
| Samsung SM963 2.5" NVMe PCIe SSD 1024GB   | 13        | 1.37%   |
| Intel NVMe SSD Drive 512GB                | 13        | 1.37%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 12        | 1.27%   |
| Samsung NVMe SSD Drive 1TB                | 12        | 1.27%   |
| SK hynix NVMe SSD Drive 512GB             | 10        | 1.05%   |
| SanDisk NVMe SSD Drive 1024GB             | 9         | 0.95%   |
| HGST HTS721010A9E630 1TB                  | 9         | 0.95%   |
| Unknown MMC Card  64GB                    | 8         | 0.84%   |
| Samsung NVMe SSD Drive 500GB              | 8         | 0.84%   |
| Micron NVMe SSD Drive 512GB               | 8         | 0.84%   |
| Unknown                                   | 8         | 0.84%   |
| Toshiba NVMe SSD Drive 512GB              | 7         | 0.74%   |
| Toshiba MQ01ABD100 1TB                    | 7         | 0.74%   |
| SK hynix NVMe SSD Drive 256GB             | 7         | 0.74%   |
| KIOXIA NVMe SSD Drive 512GB               | 7         | 0.74%   |
| Unknown MMC Card  32GB                    | 6         | 0.63%   |
| SK hynix NVMe SSD Drive 1024GB            | 6         | 0.63%   |
| Samsung MZALQ512HALU-000L2 512GB          | 6         | 0.63%   |
| Kingston SA400S37240G 240GB SSD           | 6         | 0.63%   |
| Unknown MMC Card  128GB                   | 5         | 0.53%   |
| Toshiba MQ04ABF100 1TB                    | 5         | 0.53%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD       | 5         | 0.53%   |
| Silicon Motion NVMe SSD Drive 256GB       | 5         | 0.53%   |
| Samsung SSD 860 EVO 500GB                 | 5         | 0.53%   |
| Samsung SSD 860 EVO 250GB                 | 5         | 0.53%   |
| Samsung NVMe SSD Drive 2TB                | 5         | 0.53%   |
| Samsung MZVLB1T0HBLR-000L7 1TB            | 5         | 0.53%   |
| Micron NVMe SSD Drive 1024GB              | 5         | 0.53%   |
| Crucial CT1000MX500SSD1 1TB               | 5         | 0.53%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 4         | 0.42%   |
| Seagate ST500LT012-1DG142 500GB           | 4         | 0.42%   |
| Seagate ST1000LM049-2GH172 1TB            | 4         | 0.42%   |
| Seagate ST1000LM048-2E7172 1TB            | 4         | 0.42%   |
| SanDisk SSD PLUS 480GB                    | 4         | 0.42%   |
| SanDisk NVMe SSD Drive 256GB              | 4         | 0.42%   |
| SanDisk NVMe SSD Drive 1TB                | 4         | 0.42%   |
| Samsung SSD 980 PRO 1TB                   | 4         | 0.42%   |
| Samsung MZALQ512HBLU-00BL2 512GB          | 4         | 0.42%   |
| SABRENT Disk 480GB                        | 4         | 0.42%   |
| Kingston NVMe SSD Drive 512GB             | 4         | 0.42%   |
| Kingston NVMe SSD Drive 1TB               | 4         | 0.42%   |
| Crucial CT500MX500SSD1 500GB              | 4         | 0.42%   |
| Crucial CT480BX500SSD1 480GB              | 4         | 0.42%   |
| WDC WDBNCE0010PNC 1TB SSD                 | 3         | 0.32%   |
| WDC WD10SPZX-24Z10 1TB                    | 3         | 0.32%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB        | 3         | 0.32%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB      | 3         | 0.32%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB      | 3         | 0.32%   |
| Unknown DA4064  64GB                      | 3         | 0.32%   |
| Toshiba KXG6AZNV512G 512GB                | 3         | 0.32%   |
| SSSTC CL1-4D256 256GB                     | 3         | 0.32%   |
| Solid State Storage NVMe SSD Drive 256GB  | 3         | 0.32%   |
| SK hynix SKHynix_HFM512GDHTNI-87A0B 512GB | 3         | 0.32%   |
| Seagate ST500LM012 HN-M500MBB 500GB       | 3         | 0.32%   |
| Seagate Expansion 500GB                   | 3         | 0.32%   |
| Samsung SSD 860 QVO 1TB                   | 3         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 65        | 68     | 41.4%   |
| WDC      | 34        | 40     | 21.66%  |
| Toshiba  | 21        | 23     | 13.38%  |
| HGST     | 15        | 16     | 9.55%   |
| Hitachi  | 9         | 9      | 5.73%   |
| SABRENT  | 4         | 4      | 2.55%   |
| Fujitsu  | 3         | 3      | 1.91%   |
| Unknown  | 2         | 3      | 1.27%   |
| Apple    | 2         | 2      | 1.27%   |
| USB3.0   | 1         | 1      | 0.64%   |
| IB-AC703 | 1         | 1      | 0.64%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 61        | 68     | 24.5%   |
| SanDisk             | 24        | 27     | 9.64%   |
| Crucial             | 24        | 26     | 9.64%   |
| Kingston            | 22        | 25     | 8.84%   |
| WDC                 | 11        | 13     | 4.42%   |
| Micron Technology   | 10        | 10     | 4.02%   |
| Intel               | 8         | 8      | 3.21%   |
| Apple               | 8         | 8      | 3.21%   |
| A-DATA Technology   | 7         | 8      | 2.81%   |
| LITEON              | 6         | 6      | 2.41%   |
| PNY                 | 5         | 5      | 2.01%   |
| Patriot             | 4         | 5      | 1.61%   |
| Netac               | 4         | 4      | 1.61%   |
| Intenso             | 4         | 4      | 1.61%   |
| China               | 4         | 5      | 1.61%   |
| Transcend           | 3         | 3      | 1.2%    |
| SK hynix            | 3         | 3      | 1.2%    |
| Lexar               | 3         | 3      | 1.2%    |
| Unknown             | 3         | 3      | 1.2%    |
| Seagate             | 2         | 2      | 0.8%    |
| LITEONIT            | 2         | 2      | 0.8%    |
| GOODRAM             | 2         | 4      | 0.8%    |
| Gigabyte Technology | 2         | 3      | 0.8%    |
| GALAX               | 2         | 2      | 0.8%    |
| Win Memory          | 1         | 1      | 0.4%    |
| WDC WDS2            | 1         | 1      | 0.4%    |
| Vaseky              | 1         | 1      | 0.4%    |
| Teclast             | 1         | 1      | 0.4%    |
| Team                | 1         | 1      | 0.4%    |
| StoreJet            | 1         | 1      | 0.4%    |
| Origin              | 1         | 1      | 0.4%    |
| OCZ-VERTEX3         | 1         | 1      | 0.4%    |
| OCZ                 | 1         | 1      | 0.4%    |
| Mushkin             | 1         | 1      | 0.4%    |
| Maxtor              | 1         | 1      | 0.4%    |
| Leven               | 1         | 1      | 0.4%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.4%    |
| KingFast            | 1         | 2      | 0.4%    |
| JMicron Technology  | 1         | 1      | 0.4%    |
| INTEL SS            | 1         | 1      | 0.4%    |
| HPE                 | 1         | 1      | 0.4%    |
| GLOWAY              | 1         | 1      | 0.4%    |
| EZCOOL              | 1         | 1      | 0.4%    |
| EAGET               | 1         | 1      | 0.4%    |
| Dogfish             | 1         | 1      | 0.4%    |
| Corsair             | 1         | 2      | 0.4%    |
| Apacer              | 1         | 1      | 0.4%    |
| AMD                 | 1         | 1      | 0.4%    |
| ADATA SU            | 1         | 1      | 0.4%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 429       | 521    | 49.65%  |
| SSD     | 224       | 274    | 25.93%  |
| HDD     | 154       | 170    | 17.82%  |
| MMC     | 42        | 52     | 4.86%   |
| Unknown | 15        | 16     | 1.74%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 429       | 521    | 50.71%  |
| SATA | 339       | 421    | 40.07%  |
| MMC  | 42        | 52     | 4.96%   |
| SAS  | 36        | 39     | 4.26%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 239       | 279    | 61.13%  |
| 0.51-1.0   | 131       | 141    | 33.5%   |
| 1.01-2.0   | 18        | 21     | 4.6%    |
| 4.01-10.0  | 3         | 3      | 0.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 162       | 21.83%  |
| 251-500        | 153       | 20.62%  |
| 101-250        | 104       | 14.02%  |
| 1-20           | 101       | 13.61%  |
| 1001-2000      | 90        | 12.13%  |
| Unknown        | 59        | 7.95%   |
| 51-100         | 30        | 4.04%   |
| More than 3000 | 19        | 2.56%   |
| 2001-3000      | 14        | 1.89%   |
| 21-50          | 10        | 1.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 262       | 34.61%  |
| 21-50          | 128       | 16.91%  |
| 101-250        | 90        | 11.89%  |
| 51-100         | 89        | 11.76%  |
| 251-500        | 75        | 9.91%   |
| Unknown        | 59        | 7.79%   |
| 501-1000       | 45        | 5.94%   |
| 1001-2000      | 6         | 0.79%   |
| More than 3000 | 2         | 0.26%   |
| 2001-3000      | 1         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB           | 3         | 3      | 10.34%  |
| HGST HTS721010A9E630 1TB                     | 2         | 2      | 6.9%    |
| WDC WD5000LPCX-24C6HT0 500GB                 | 1         | 1      | 3.45%   |
| WDC WD5000LPCX-00VHAT0 500GB                 | 1         | 1      | 3.45%   |
| Toshiba MK5055GSX 500GB                      | 1         | 1      | 3.45%   |
| Seagate ST9320325AS 320GB                    | 1         | 1      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 3.45%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 3.45%   |
| Seagate ST500LM012 HN-M500MBB 500GB          | 1         | 1      | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB               | 1         | 1      | 3.45%   |
| SanDisk SD6SB1M128G1022 128GB SSD            | 1         | 1      | 3.45%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD          | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 980 PRO 500GB        | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 870 EVO 500GB        | 1         | 2      | 3.45%   |
| Samsung Electronics SSD 840 Series 250GB     | 1         | 1      | 3.45%   |
| Origin Inception TLC830 Pro Series 256GB SSD | 1         | 1      | 3.45%   |
| OCZ-VERTEX3 MI 120GB SSD                     | 1         | 1      | 3.45%   |
| Micron Technology 1100 SATA 256GB SSD        | 1         | 1      | 3.45%   |
| LITEONIT LCS-128M6S-HP 128GB SSD             | 1         | 1      | 3.45%   |
| Lenovo LENSE20512GMSP34MEAT2TA 512GB         | 1         | 1      | 3.45%   |
| Kingston SHFS37A120G 120GB SSD               | 1         | 1      | 3.45%   |
| Hitachi HTS727550A9E364 500GB                | 1         | 1      | 3.45%   |
| Hitachi HTS547575A9E384 752GB                | 1         | 1      | 3.45%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 3.45%   |
| Fujitsu MJA2500BH G1 500GB                   | 1         | 1      | 3.45%   |
| Crucial CT1050MX300SSD1 1050GB               | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8         | 8      | 27.59%  |
| Samsung Electronics | 3         | 4      | 10.34%  |
| Hitachi             | 3         | 3      | 10.34%  |
| WDC                 | 2         | 2      | 6.9%    |
| SanDisk             | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| Toshiba             | 1         | 1      | 3.45%   |
| Origin              | 1         | 1      | 3.45%   |
| OCZ-VERTEX3         | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| LITEONIT            | 1         | 1      | 3.45%   |
| Lenovo              | 1         | 1      | 3.45%   |
| Kingston            | 1         | 1      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 47.06%  |
| Hitachi | 3         | 3      | 17.65%  |
| WDC     | 2         | 2      | 11.76%  |
| HGST    | 2         | 2      | 11.76%  |
| Toshiba | 1         | 1      | 5.88%   |
| Fujitsu | 1         | 1      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 17        | 17     | 58.62%  |
| SSD  | 10        | 11     | 34.48%  |
| NVMe | 2         | 2      | 6.9%    |

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
| Detected | 429       | 610    | 55.64%  |
| Works    | 314       | 393    | 40.73%  |
| Malfunc  | 28        | 30     | 3.63%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 422       | 44.99%  |
| Samsung Electronics            | 133       | 14.18%  |
| AMD                            | 87        | 9.28%   |
| SanDisk                        | 79        | 8.42%   |
| SK hynix                       | 48        | 5.12%   |
| Toshiba America Info Systems   | 30        | 3.2%    |
| Micron Technology              | 27        | 2.88%   |
| Kingston Technology Company    | 17        | 1.81%   |
| Phison Electronics             | 16        | 1.71%   |
| KIOXIA                         | 15        | 1.6%    |
| ADATA Technology               | 14        | 1.49%   |
| Silicon Motion                 | 11        | 1.17%   |
| Solid State Storage Technology | 9         | 0.96%   |
| Union Memory (Shenzhen)        | 7         | 0.75%   |
| Nvidia                         | 4         | 0.43%   |
| Micron/Crucial Technology      | 4         | 0.43%   |
| Lenovo                         | 4         | 0.43%   |
| Marvell Technology Group       | 3         | 0.32%   |
| Lite-On Technology             | 3         | 0.32%   |
| Unknown                        | 1         | 0.11%   |
| Realtek Semiconductor          | 1         | 0.11%   |
| Biwin Storage Technology       | 1         | 0.11%   |
| Apple                          | 1         | 0.11%   |
| Unknown                        | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 82        | 8.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 56        | 5.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 56        | 5.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 46        | 4.7%    |
| Intel Volume Management Device NVMe RAID Controller                              | 44        | 4.5%    |
| Samsung NVMe SSD Controller 980                                                  | 39        | 3.99%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 38        | 3.89%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 30        | 3.07%   |
| Micron Non-Volatile memory controller                                            | 27        | 2.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 27        | 2.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 25        | 2.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 23        | 2.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 22        | 2.25%   |
| SanDisk Non-Volatile memory controller                                           | 19        | 1.94%   |
| SK hynix Gold P31 SSD                                                            | 18        | 1.84%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 17        | 1.74%   |
| Intel Tiger Lake-LP SATA Controller                                              | 16        | 1.64%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 15        | 1.53%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 15        | 1.53%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 14        | 1.43%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 14        | 1.43%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 13        | 1.33%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 13        | 1.33%   |
| Intel Non-Volatile memory controller                                             | 13        | 1.33%   |
| SK hynix BC511                                                                   | 11        | 1.12%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 11        | 1.12%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 11        | 1.12%   |
| Intel Comet Lake SATA AHCI Controller                                            | 11        | 1.12%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 11        | 1.12%   |
| Solid State Storage Non-Volatile memory controller                               | 9         | 0.92%   |
| Intel SSD 660P Series                                                            | 9         | 0.92%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 0.92%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 8         | 0.82%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 7         | 0.72%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 7         | 0.72%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 7         | 0.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 0.72%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                      | 7         | 0.72%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 6         | 0.61%   |
| SanDisk PC SN520 NVMe SSD                                                        | 6         | 0.61%   |
| Phison E12 NVMe Controller                                                       | 6         | 0.61%   |
| ADATA Non-Volatile memory controller                                             | 6         | 0.61%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 5         | 0.51%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 5         | 0.51%   |
| SK hynix Non-Volatile memory controller                                          | 5         | 0.51%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 5         | 0.51%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 5         | 0.51%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 5         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5         | 0.51%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 0.51%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 5         | 0.51%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                       | 4         | 0.41%   |
| Samsung Electronics SATA controller                                              | 4         | 0.41%   |
| Phison PS5013 E13 NVMe Controller                                                | 4         | 0.41%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 0.41%   |
| Lenovo Non-Volatile memory controller                                            | 4         | 0.41%   |
| Kingston Company Company Non-Volatile memory controller                          | 4         | 0.41%   |
| Kingston Company A2000 NVMe SSD                                                  | 4         | 0.41%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 3         | 0.31%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.31%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 427       | 45.23%  |
| SATA | 424       | 44.92%  |
| RAID | 83        | 8.79%   |
| IDE  | 10        | 1.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 543       | 74.38%  |
| AMD     | 186       | 25.48%  |
| Unknown | 1         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 28        | 3.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 21        | 2.88%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 19        | 2.6%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 19        | 2.6%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 17        | 2.33%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 16        | 2.19%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 13        | 1.78%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 12        | 1.64%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 1.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 1.37%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 1.37%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 1.37%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 10        | 1.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 9         | 1.23%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 9         | 1.23%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 9         | 1.23%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 8         | 1.1%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 1.1%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 1.1%    |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 1.1%    |
| Intel Core i7-10850H CPU @ 2.70GHz            | 7         | 0.96%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.96%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.96%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 6         | 0.82%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 6         | 0.82%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.82%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 6         | 0.82%   |
| AMD Ryzen 5 5600U with Radeon Graphics        | 6         | 0.82%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 6         | 0.82%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 5         | 0.68%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 5         | 0.68%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.68%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 5         | 0.68%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 5         | 0.68%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 0.68%   |
| AMD Ryzen 9 6900HS with Radeon Graphics       | 5         | 0.68%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 5         | 0.68%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 5         | 0.68%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 0.68%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 5         | 0.68%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 4         | 0.55%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 4         | 0.55%   |
| Intel Core i7-4500U CPU @ 1.80GHz             | 4         | 0.55%   |
| Intel Core i7-10870H CPU @ 2.20GHz            | 4         | 0.55%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 4         | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.55%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 4         | 0.55%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 4         | 0.55%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 0.55%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 4         | 0.55%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 4         | 0.55%   |
| Intel Atom CPU Z3735F @ 1.33GHz               | 4         | 0.55%   |
| Intel 12th Gen Core i7-12700H                 | 4         | 0.55%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 4         | 0.55%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 4         | 0.55%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 0.55%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 3         | 0.41%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 3         | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 188       | 25.75%  |
| Intel Core i5                  | 162       | 22.19%  |
| Other                          | 98        | 13.42%  |
| AMD Ryzen 5                    | 62        | 8.49%   |
| AMD Ryzen 7                    | 51        | 6.99%   |
| Intel Core i3                  | 36        | 4.93%   |
| Intel Celeron                  | 23        | 3.15%   |
| AMD Ryzen 9                    | 21        | 2.88%   |
| AMD Ryzen 7 PRO                | 14        | 1.92%   |
| Intel Core 2 Duo               | 10        | 1.37%   |
| AMD Ryzen 3                    | 9         | 1.23%   |
| AMD A10                        | 9         | 1.23%   |
| Intel Pentium                  | 8         | 1.1%    |
| Intel Atom                     | 8         | 1.1%    |
| Intel Pentium Silver           | 4         | 0.55%   |
| Intel Core i9                  | 4         | 0.55%   |
| AMD A8                         | 3         | 0.41%   |
| AMD A6                         | 3         | 0.41%   |
| AMD Ryzen 5 PRO                | 2         | 0.27%   |
| AMD E1                         | 2         | 0.27%   |
| AMD A4                         | 2         | 0.27%   |
| Intel Xeon                     | 1         | 0.14%   |
| Intel Pentium Dual-Core        | 1         | 0.14%   |
| Intel Core m5                  | 1         | 0.14%   |
| Intel Core 2                   | 1         | 0.14%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.14%   |
| AMD Turion 64 X2 Mobile        | 1         | 0.14%   |
| AMD PRO A8                     | 1         | 0.14%   |
| AMD Phenom II                  | 1         | 0.14%   |
| AMD Athlon II Dual-Core        | 1         | 0.14%   |
| AMD Athlon II                  | 1         | 0.14%   |
| AMD Athlon                     | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 293       | 40.14%  |
| 2      | 238       | 32.6%   |
| 8      | 96        | 13.15%  |
| 6      | 86        | 11.78%  |
| 14     | 10        | 1.37%   |
| 12     | 2         | 0.27%   |
| 10     | 2         | 0.27%   |
| 1      | 2         | 0.27%   |
| 3      | 1         | 0.14%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 730       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 642       | 87.82%  |
| 1      | 89        | 12.18%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 730       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 66        | 9.02%   |
| 0x806ea    | 45        | 6.15%   |
| 0x306a9    | 45        | 6.15%   |
| 0x0a50000c | 37        | 5.05%   |
| 0x806ec    | 36        | 4.92%   |
| 0x206a7    | 34        | 4.64%   |
| 0x906ea    | 30        | 4.1%    |
| 0x40651    | 30        | 4.1%    |
| 0xa0652    | 29        | 3.96%   |
| 0x806e9    | 26        | 3.55%   |
| Unknown    | 26        | 3.55%   |
| 0x08108109 | 24        | 3.28%   |
| 0x08608103 | 22        | 3.01%   |
| 0x08600106 | 21        | 2.87%   |
| 0x406e3    | 20        | 2.73%   |
| 0x306d4    | 19        | 2.6%    |
| 0x506e3    | 16        | 2.19%   |
| 0x306c3    | 14        | 1.91%   |
| 0x906a3    | 12        | 1.64%   |
| 0x08108102 | 12        | 1.64%   |
| 0x906e9    | 9         | 1.23%   |
| 0x806d1    | 9         | 1.23%   |
| 0x706e5    | 9         | 1.23%   |
| 0x0a404101 | 9         | 1.23%   |
| 0x706a8    | 8         | 1.09%   |
| 0x08600104 | 8         | 1.09%   |
| 0x806eb    | 7         | 0.96%   |
| 0x30678    | 7         | 0.96%   |
| 0x20655    | 7         | 0.96%   |
| 0x1067a    | 7         | 0.96%   |
| 0x08608102 | 7         | 0.96%   |
| 0x506c9    | 6         | 0.82%   |
| 0x806c2    | 5         | 0.68%   |
| 0x08600103 | 5         | 0.68%   |
| 0x706a1    | 4         | 0.55%   |
| 0x406c4    | 4         | 0.55%   |
| 0x0600611a | 4         | 0.55%   |
| 0x906ed    | 3         | 0.41%   |
| 0x906c0    | 3         | 0.41%   |
| 0x406c3    | 3         | 0.41%   |
| 0x106e5    | 3         | 0.41%   |
| 0x10676    | 3         | 0.41%   |
| 0x0a50000b | 3         | 0.41%   |
| 0x0a404102 | 3         | 0.41%   |
| 0xa0660    | 2         | 0.27%   |
| 0x20652    | 2         | 0.27%   |
| 0x0810100b | 2         | 0.27%   |
| 0x07030105 | 2         | 0.27%   |
| 0x0700010b | 2         | 0.27%   |
| 0x06001116 | 2         | 0.27%   |
| 0x010000c8 | 2         | 0.27%   |
| 0x906a4    | 1         | 0.14%   |
| 0x6f2      | 1         | 0.14%   |
| 0x40661    | 1         | 0.14%   |
| 0x106ca    | 1         | 0.14%   |
| 0x08200103 | 1         | 0.14%   |
| 0x08101016 | 1         | 0.14%   |
| 0x08001137 | 1         | 0.14%   |
| 0x07030104 | 1         | 0.14%   |
| 0x0700010f | 1         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 164       | 22.47%  |
| TigerLake        | 73        | 10%     |
| IvyBridge        | 46        | 6.3%    |
| Haswell          | 45        | 6.16%   |
| Unknown          | 43        | 5.89%   |
| Zen 3            | 42        | 5.75%   |
| Skylake          | 38        | 5.21%   |
| Zen+             | 36        | 4.93%   |
| Zen 2            | 36        | 4.93%   |
| SandyBridge      | 34        | 4.66%   |
| CometLake        | 32        | 4.38%   |
| Broadwell        | 19        | 2.6%    |
| IceLake          | 18        | 2.47%   |
| Silvermont       | 14        | 1.92%   |
| Alderlake Hybrid | 13        | 1.78%   |
| Goldmont plus    | 12        | 1.64%   |
| Penryn           | 11        | 1.51%   |
| Westmere         | 10        | 1.37%   |
| Excavator        | 8         | 1.1%    |
| Goldmont         | 6         | 0.82%   |
| Zen              | 5         | 0.68%   |
| Piledriver       | 4         | 0.55%   |
| Tremont          | 3         | 0.41%   |
| Puma             | 3         | 0.41%   |
| Nehalem          | 3         | 0.41%   |
| K10              | 3         | 0.41%   |
| Jaguar           | 3         | 0.41%   |
| K8 Hammer        | 1         | 0.14%   |
| K8 & K10 hybrid  | 1         | 0.14%   |
| K10 Llano        | 1         | 0.14%   |
| Core             | 1         | 0.14%   |
| Bonnell          | 1         | 0.14%   |
| Bobcat           | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 510       | 52.69%  |
| Nvidia | 243       | 25.1%   |
| AMD    | 215       | 22.21%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 69        | 6.96%   |
| Intel UHD Graphics 620                                                                   | 47        | 4.74%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 40        | 4.04%   |
| AMD Cezanne                                                                              | 40        | 4.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 37        | 3.73%   |
| AMD Renoir                                                                               | 36        | 3.63%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 31        | 3.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 30        | 3.03%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 29        | 2.93%   |
| AMD Lucienne                                                                             | 29        | 2.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 28        | 2.83%   |
| Intel HD Graphics 620                                                                    | 25        | 2.52%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 2.52%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 20        | 2.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 20        | 2.02%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 1.82%   |
| Intel HD Graphics 5500                                                                   | 16        | 1.61%   |
| Intel HD Graphics 530                                                                    | 14        | 1.41%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.31%   |
| AMD Rembrandt [Radeon 680M]                                                              | 13        | 1.31%   |
| Nvidia GP108M [GeForce MX150]                                                            | 12        | 1.21%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 12        | 1.21%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 10        | 1.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.91%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 9         | 0.91%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 9         | 0.91%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 0.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 0.81%   |
| Nvidia TU117M                                                                            | 7         | 0.71%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 7         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 7         | 0.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 0.71%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 0.71%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.71%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 6         | 0.61%   |
| Nvidia GP108M [GeForce MX250]                                                            | 6         | 0.61%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 6         | 0.61%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 6         | 0.61%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.5%    |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 0.5%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.5%    |
| Nvidia GA104M [GeForce RTX 3080 Mobile / Max-Q 8GB/16GB]                                 | 5         | 0.5%    |
| Intel HD Graphics 630                                                                    | 5         | 0.5%    |
| Intel HD Graphics 500                                                                    | 5         | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.4%    |
| Nvidia GM108M [GeForce MX130]                                                            | 4         | 0.4%    |
| Nvidia GM107M [GeForce GTX 860M]                                                         | 4         | 0.4%    |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 4         | 0.4%    |
| Nvidia C79 [GeForce 9400M]                                                               | 4         | 0.4%    |
| Intel Tiger Lake UHD Graphics                                                            | 4         | 0.4%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 4         | 0.4%    |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 4         | 0.4%    |
| Nvidia TU117GLM [Quadro T500 Mobile]                                                     | 3         | 0.3%    |
| Nvidia GP108M [GeForce MX230]                                                            | 3         | 0.3%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 0.3%    |
| Nvidia GM108M [GeForce 930MX]                                                            | 3         | 0.3%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 3         | 0.3%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 307       | 42.05%  |
| Intel + Nvidia | 179       | 24.52%  |
| 1 x AMD        | 138       | 18.9%   |
| AMD + Nvidia   | 35        | 4.79%   |
| 1 x Nvidia     | 27        | 3.7%    |
| Intel + AMD    | 22        | 3.01%   |
| 2 x AMD        | 20        | 2.74%   |
| Other          | 1         | 0.14%   |
| 2 x Nvidia     | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 621       | 84.72%  |
| Proprietary | 107       | 14.6%   |
| Unknown     | 5         | 0.68%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 396       | 53.95%  |
| 1.01-2.0   | 120       | 16.35%  |
| 0.01-0.5   | 104       | 14.17%  |
| 3.01-4.0   | 53        | 7.22%   |
| 0.51-1.0   | 34        | 4.63%   |
| 5.01-6.0   | 10        | 1.36%   |
| 7.01-8.0   | 9         | 1.23%   |
| 2.01-3.0   | 4         | 0.54%   |
| 8.01-16.0  | 4         | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 178       | 20.34%  |
| BOE                     | 147       | 16.8%   |
| LG Display              | 114       | 13.03%  |
| Chimei Innolux          | 108       | 12.34%  |
| Samsung Electronics     | 50        | 5.71%   |
| Sharp                   | 32        | 3.66%   |
| Dell                    | 32        | 3.66%   |
| Goldstar                | 30        | 3.43%   |
| Apple                   | 22        | 2.51%   |
| CSO                     | 18        | 2.06%   |
| PANDA                   | 17        | 1.94%   |
| Lenovo                  | 15        | 1.71%   |
| Philips                 | 12        | 1.37%   |
| Hewlett-Packard         | 11        | 1.26%   |
| InfoVision              | 10        | 1.14%   |
| Chi Mei Optoelectronics | 10        | 1.14%   |
| TMX                     | 7         | 0.8%    |
| BenQ                    | 7         | 0.8%    |
| Acer                    | 7         | 0.8%    |
| ViewSonic               | 5         | 0.57%   |
| Ancor Communications    | 5         | 0.57%   |
| Vizio                   | 3         | 0.34%   |
| MSI                     | 3         | 0.34%   |
| JDI                     | 3         | 0.34%   |
| Iiyama                  | 3         | 0.34%   |
| AOC                     | 3         | 0.34%   |
| Toshiba                 | 2         | 0.23%   |
| SKY                     | 2         | 0.23%   |
| KDC                     | 2         | 0.23%   |
| ASUSTek Computer        | 2         | 0.23%   |
| YCT                     | 1         | 0.11%   |
| VIE                     | 1         | 0.11%   |
| Sceptre Tech            | 1         | 0.11%   |
| Pixio                   | 1         | 0.11%   |
| Pioneer                 | 1         | 0.11%   |
| ONN                     | 1         | 0.11%   |
| LG Philips              | 1         | 0.11%   |
| Insignia                | 1         | 0.11%   |
| HKC                     | 1         | 0.11%   |
| HJC                     | 1         | 0.11%   |
| HannStar                | 1         | 0.11%   |
| Fujitsu Siemens         | 1         | 0.11%   |
| Eizo                    | 1         | 0.11%   |
| Aosiman                 | 1         | 0.11%   |
| Unknown                 | 1         | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 10        | 1.12%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 7         | 0.79%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 7         | 0.79%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 6         | 0.67%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                     | 6         | 0.67%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                     | 6         | 0.67%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 6         | 0.67%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 6         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 5         | 0.56%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                     | 5         | 0.56%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 5         | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 5         | 0.56%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 5         | 0.56%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch            | 5         | 0.56%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                   | 4         | 0.45%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 4         | 0.45%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch               | 4         | 0.45%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1540 2560x1440 344x193mm 15.5-inch          | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch          | 4         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 4         | 0.45%   |
| BOE LCD Monitor BOE0A1D 2560x1600 302x189mm 14.0-inch                     | 4         | 0.45%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch            | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 4         | 0.45%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch            | 4         | 0.45%   |
| TMX TL156MDMP11-0 TMX1560 3200x2000 336x210mm 15.6-inch                   | 3         | 0.34%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch                   | 3         | 0.34%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                   | 3         | 0.34%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 3         | 0.34%   |
| LG Display LCD Monitor LGD056D 1920x1080 382x215mm 17.3-inch              | 3         | 0.34%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch               | 3         | 0.34%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch               | 3         | 0.34%   |
| CSO LCD Monitor CSO1603 2560x1600 344x215mm 16.0-inch                     | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15C2 1920x1080 344x194mm 15.5-inch          | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch          | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14C8 1920x1080 309x173mm 13.9-inch          | 3         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch           | 3         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 3         | 0.34%   |
| BOE LCD Monitor BOE09D3 1920x1080 344x194mm 15.5-inch                     | 3         | 0.34%   |
| BOE LCD Monitor BOE0931 2240x1400 302x189mm 14.0-inch                     | 3         | 0.34%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                     | 3         | 0.34%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 3         | 0.34%   |
| AU Optronics LCD Monitor AUOE48D 1920x1080 344x194mm 15.5-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO6496 1920x1200 286x178mm 13.3-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO5A2D 1920x1080 293x165mm 13.2-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO229E 1600x900 382x214mm 17.2-inch             | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch             | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch             | 3         | 0.34%   |
| AU Optronics LCD Monitor AUO103C 1366x768 309x173mm 13.9-inch             | 3         | 0.34%   |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch                 | 2         | 0.22%   |
| SKY TV-monitor SKY0104 1920x1080 885x498mm 40.0-inch                      | 2         | 0.22%   |
| Sharp LQ173M1JW04 SHP14E1 1920x1080 382x215mm 17.3-inch                   | 2         | 0.22%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                   | 2         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 433       | 52.87%  |
| 1366x768 (WXGA)    | 142       | 17.34%  |
| 3840x2160 (4K)     | 42        | 5.13%   |
| 2560x1440 (QHD)    | 33        | 4.03%   |
| 1920x1200 (WUXGA)  | 31        | 3.79%   |
| 1600x900 (HD+)     | 30        | 3.66%   |
| 2560x1600          | 15        | 1.83%   |
| 1280x800 (WXGA)    | 11        | 1.34%   |
| 2880x1800          | 9         | 1.1%    |
| 3440x1440          | 8         | 0.98%   |
| 3840x2400          | 7         | 0.85%   |
| 2160x1440          | 7         | 0.85%   |
| 1440x900 (WXGA+)   | 7         | 0.85%   |
| 1280x1024 (SXGA)   | 7         | 0.85%   |
| 2560x1080          | 6         | 0.73%   |
| 2256x1504          | 6         | 0.73%   |
| 3456x2160          | 5         | 0.61%   |
| 3200x2000          | 3         | 0.37%   |
| 2240x1400          | 3         | 0.37%   |
| 3000x2000          | 2         | 0.24%   |
| 2520x1680          | 2         | 0.24%   |
| 3840x1600          | 1         | 0.12%   |
| 3200x1800 (QHD+)   | 1         | 0.12%   |
| 3072x1920          | 1         | 0.12%   |
| 2400x1600          | 1         | 0.12%   |
| 2304x1440          | 1         | 0.12%   |
| 1920x550           | 1         | 0.12%   |
| 1680x1050 (WSXGA+) | 1         | 0.12%   |
| 1360x768           | 1         | 0.12%   |
| 1024x768 (XGA)     | 1         | 0.12%   |
| 1024x600           | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 330       | 37.54%  |
| 14      | 150       | 17.06%  |
| 13      | 136       | 15.47%  |
| 17      | 53        | 6.03%   |
| 27      | 41        | 4.66%   |
| 24      | 30        | 3.41%   |
| 21      | 21        | 2.39%   |
| 12      | 21        | 2.39%   |
| 23      | 19        | 2.16%   |
| 16      | 15        | 1.71%   |
| 34      | 13        | 1.48%   |
| 31      | 12        | 1.37%   |
| 11      | 7         | 0.8%    |
| 19      | 5         | 0.57%   |
| 18      | 5         | 0.57%   |
| 84      | 4         | 0.46%   |
| 40      | 3         | 0.34%   |
| 20      | 2         | 0.23%   |
| 10      | 2         | 0.23%   |
| Unknown | 2         | 0.23%   |
| 69      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 37      | 1         | 0.11%   |
| 32      | 1         | 0.11%   |
| 29      | 1         | 0.11%   |
| 26      | 1         | 0.11%   |
| 25      | 1         | 0.11%   |
| 22      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 553       | 63.56%  |
| 201-300     | 99        | 11.38%  |
| 501-600     | 85        | 9.77%   |
| 351-400     | 60        | 6.9%    |
| 401-500     | 32        | 3.68%   |
| 601-700     | 15        | 1.72%   |
| 701-800     | 13        | 1.49%   |
| 801-900     | 6         | 0.69%   |
| 1501-2000   | 5         | 0.57%   |
| Unknown     | 2         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 624       | 81.57%  |
| 16/10   | 98        | 12.81%  |
| 3/2     | 18        | 2.35%   |
| 21/9    | 15        | 1.96%   |
| 5/4     | 6         | 0.78%   |
| 4/3     | 2         | 0.26%   |
| 32/9    | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 332       | 37.81%  |
| 81-90          | 232       | 26.42%  |
| 71-80          | 52        | 5.92%   |
| 201-250        | 52        | 5.92%   |
| 121-130        | 47        | 5.35%   |
| 301-350        | 43        | 4.9%    |
| 351-500        | 24        | 2.73%   |
| 61-70          | 20        | 2.28%   |
| 251-300        | 17        | 1.94%   |
| 111-120        | 13        | 1.48%   |
| 151-200        | 11        | 1.25%   |
| 141-150        | 8         | 0.91%   |
| 51-60          | 7         | 0.8%    |
| More than 1000 | 5         | 0.57%   |
| 501-1000       | 5         | 0.57%   |
| 131-140        | 4         | 0.46%   |
| 41-50          | 2         | 0.23%   |
| 91-100         | 2         | 0.23%   |
| Unknown        | 2         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 427       | 49.59%  |
| 101-120       | 171       | 19.86%  |
| 161-240       | 107       | 12.43%  |
| 51-100        | 107       | 12.43%  |
| More than 240 | 46        | 5.34%   |
| Unknown       | 2         | 0.23%   |
| 1-50          | 1         | 0.12%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 576       | 77.84%  |
| 2     | 136       | 18.38%  |
| 3     | 12        | 1.62%   |
| 0     | 11        | 1.49%   |
| 4     | 4         | 0.54%   |
| 5     | 1         | 0.14%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 412       | 38.08%  |
| Realtek Semiconductor             | 381       | 35.21%  |
| Qualcomm Atheros                  | 110       | 10.17%  |
| Broadcom                          | 47        | 4.34%   |
| MediaTek                          | 36        | 3.33%   |
| Broadcom Limited                  | 13        | 1.2%    |
| Sierra Wireless                   | 8         | 0.74%   |
| TP-Link                           | 7         | 0.65%   |
| Lenovo                            | 7         | 0.65%   |
| Ralink Technology                 | 5         | 0.46%   |
| Ralink                            | 5         | 0.46%   |
| Qualcomm                          | 5         | 0.46%   |
| Nvidia                            | 4         | 0.37%   |
| Ericsson Business Mobile Networks | 4         | 0.37%   |
| ASIX Electronics                  | 4         | 0.37%   |
| Samsung Electronics               | 3         | 0.28%   |
| Hewlett-Packard                   | 3         | 0.28%   |
| Xiaomi                            | 2         | 0.18%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.18%   |
| Marvell Technology Group          | 2         | 0.18%   |
| Huawei Technologies               | 2         | 0.18%   |
| Fibocom                           | 2         | 0.18%   |
| DisplayLink                       | 2         | 0.18%   |
| Dell                              | 2         | 0.18%   |
| D-Link                            | 2         | 0.18%   |
| Belkin Components                 | 2         | 0.18%   |
| T & A Mobile Phones               | 1         | 0.09%   |
| Realtek                           | 1         | 0.09%   |
| OPPO Electronics                  | 1         | 0.09%   |
| MicroPython                       | 1         | 0.09%   |
| Linksys                           | 1         | 0.09%   |
| Google                            | 1         | 0.09%   |
| Edimax Technology                 | 1         | 0.09%   |
| D-Link System                     | 1         | 0.09%   |
| ASUSTek Computer                  | 1         | 0.09%   |
| Adafruit                          | 1         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 218       | 16.6%   |
| Intel Wi-Fi 6 AX201                                               | 55        | 4.19%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 53        | 4.04%   |
| Intel Wi-Fi 6 AX200                                               | 49        | 3.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 3.05%   |
| Intel Wireless 8265 / 8275                                        | 38        | 2.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 32        | 2.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 2.21%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 29        | 2.21%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 28        | 2.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 26        | 1.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 25        | 1.9%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 24        | 1.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 20        | 1.52%   |
| Intel Wireless 7265                                               | 19        | 1.45%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 19        | 1.45%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 18        | 1.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 17        | 1.29%   |
| Intel Wireless 8260                                               | 16        | 1.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 15        | 1.14%   |
| Intel Wireless 7260                                               | 15        | 1.14%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 14        | 1.07%   |
| Intel Centrino Ultimate-N 6300                                    | 14        | 1.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 13        | 0.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 13        | 0.99%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 0.84%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 11        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 0.76%   |
| Intel Wireless-AC 9260                                            | 10        | 0.76%   |
| Intel Wireless 3165                                               | 10        | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 10        | 0.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.61%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 8         | 0.61%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 0.61%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 0.61%   |
| Intel Wireless 3160                                               | 7         | 0.53%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 0.53%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 7         | 0.53%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 7         | 0.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 6         | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.46%   |
| Intel Ethernet Connection (10) I219-V                             | 6         | 0.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6         | 0.46%   |
| Broadcom BCM43142 802.11b/g/n                                     | 6         | 0.46%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 5         | 0.38%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 5         | 0.38%   |
| MediaTek WLAN controller                                          | 5         | 0.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 5         | 0.38%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.38%   |
| Intel Centrino Advanced-N 6235                                    | 5         | 0.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 5         | 0.38%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.3%    |
| Realtek 802.11n WLAN Adapter                                      | 4         | 0.3%    |
| Realtek 802.11ac NIC                                              | 4         | 0.3%    |
| Nvidia MCP79 Ethernet                                             | 4         | 0.3%    |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.3%    |
| Intel Centrino Wireless-N 2230                                    | 4         | 0.3%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 397       | 52.65%  |
| Realtek Semiconductor | 135       | 17.9%   |
| Qualcomm Atheros      | 100       | 13.26%  |
| Broadcom              | 40        | 5.31%   |
| MediaTek              | 35        | 4.64%   |
| Broadcom Limited      | 11        | 1.46%   |
| Sierra Wireless       | 7         | 0.93%   |
| TP-Link               | 5         | 0.66%   |
| Ralink Technology     | 5         | 0.66%   |
| Ralink                | 5         | 0.66%   |
| Qualcomm              | 4         | 0.53%   |
| Fibocom               | 2         | 0.27%   |
| Belkin Components     | 2         | 0.27%   |
| Realtek               | 1         | 0.13%   |
| Linksys               | 1         | 0.13%   |
| Edimax Technology     | 1         | 0.13%   |
| D-Link System         | 1         | 0.13%   |
| D-Link                | 1         | 0.13%   |
| ASUSTek Computer      | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 55        | 7.28%   |
| Intel Wi-Fi 6 AX200                                            | 49        | 6.48%   |
| Intel Wireless 8265 / 8275                                     | 38        | 5.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 32        | 4.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 29        | 3.84%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 28        | 3.7%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 26        | 3.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 25        | 3.31%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 24        | 3.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 20        | 2.65%   |
| Intel Wireless 7265                                            | 19        | 2.51%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 19        | 2.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 18        | 2.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 17        | 2.25%   |
| Intel Wireless 8260                                            | 16        | 2.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 15        | 1.98%   |
| Intel Wireless 7260                                            | 15        | 1.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 14        | 1.85%   |
| Intel Centrino Ultimate-N 6300                                 | 14        | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 13        | 1.72%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 13        | 1.72%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 1.32%   |
| Intel Wireless-AC 9260                                         | 10        | 1.32%   |
| Intel Wireless 3165                                            | 10        | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 1.32%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 8         | 1.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8         | 1.06%   |
| Intel Wireless 3160                                            | 7         | 0.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 0.93%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 7         | 0.93%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 6         | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 0.79%   |
| Broadcom BCM43142 802.11b/g/n                                  | 6         | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 5         | 0.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 5         | 0.66%   |
| MediaTek WLAN controller                                       | 5         | 0.66%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 5         | 0.66%   |
| Intel Centrino Advanced-N 6235                                 | 5         | 0.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 0.66%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 0.53%   |
| Realtek 802.11ac NIC                                           | 4         | 0.53%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 0.53%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 4         | 0.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 0.53%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 4         | 0.53%   |
| Sierra Wireless EM7455                                         | 3         | 0.4%    |
| Sierra Wireless EM7305 Modem                                   | 3         | 0.4%    |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.4%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.4%    |
| Realtek Realtek Network controller                             | 3         | 0.4%    |
| Intel WiFi Link 5100                                           | 3         | 0.4%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 3         | 0.4%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 3         | 0.4%    |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 3         | 0.4%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.4%    |
| TP-Link TL-WN722N v2                                           | 2         | 0.26%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 0.26%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 322       | 60.41%  |
| Intel                         | 138       | 25.89%  |
| Qualcomm Atheros              | 21        | 3.94%   |
| Broadcom                      | 13        | 2.44%   |
| Lenovo                        | 7         | 1.31%   |
| Nvidia                        | 4         | 0.75%   |
| ASIX Electronics              | 4         | 0.75%   |
| TP-Link                       | 3         | 0.56%   |
| Samsung Electronics           | 3         | 0.56%   |
| Xiaomi                        | 2         | 0.38%   |
| Marvell Technology Group      | 2         | 0.38%   |
| DisplayLink                   | 2         | 0.38%   |
| Broadcom Limited              | 2         | 0.38%   |
| T & A Mobile Phones           | 1         | 0.19%   |
| Sierra Wireless               | 1         | 0.19%   |
| Qualcomm                      | 1         | 0.19%   |
| OPPO Electronics              | 1         | 0.19%   |
| OnePlus Technology (Shenzhen) | 1         | 0.19%   |
| MediaTek                      | 1         | 0.19%   |
| Huawei Technologies           | 1         | 0.19%   |
| Hewlett-Packard               | 1         | 0.19%   |
| Google                        | 1         | 0.19%   |
| D-Link                        | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 218       | 40%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 53        | 9.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 7.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 29        | 5.32%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 2.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 2.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 9         | 1.65%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.47%   |
| Intel Ethernet Connection (13) I219-V                             | 8         | 1.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 7         | 1.28%   |
| Intel Ethernet Connection I219-LM                                 | 6         | 1.1%    |
| Intel Ethernet Connection (10) I219-V                             | 6         | 1.1%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.92%   |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.92%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.73%   |
| Nvidia MCP79 Ethernet                                             | 4         | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.73%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.73%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.73%   |
| ASIX AX88179 Gigabit Ethernet                                     | 4         | 0.73%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 3         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 0.55%   |
| Realtek Killer E3000 2.5GbE Controller                            | 3         | 0.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.55%   |
| Lenovo ThinkPad Lan                                               | 3         | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.55%   |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.55%   |
| Intel Ethernet Connection (13) I219-LM                            | 3         | 0.55%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 3         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 2         | 0.37%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.37%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 2         | 0.37%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 2         | 0.37%   |
| Intel WiMAX Connection 2400m                                      | 2         | 0.37%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.37%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.37%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.37%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.37%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.37%   |
| Intel Ethernet Connection (10) I219-LM                            | 2         | 0.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.37%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 1         | 0.18%   |
| Sierra Wireless EM7345 4G LTE                                     | 1         | 0.18%   |
| Realtek Realtek Ethernet controller                               | 1         | 0.18%   |
| Qualcomm Nokia X100                                               | 1         | 0.18%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.18%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.18%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.18%   |
| OPPO 9R                                                           | 1         | 0.18%   |
| OnePlus (Shenzhen) OnePlus                                        | 1         | 0.18%   |
| MediaTek Infinix HOT 9                                            | 1         | 0.18%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.18%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.18%   |
| Lenovo USB-C Hub                                                  | 1         | 0.18%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 720       | 58.02%  |
| Ethernet | 509       | 41.02%  |
| Modem    | 11        | 0.89%   |
| Unknown  | 1         | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 637       | 82.3%   |
| Ethernet | 137       | 17.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 445       | 60.96%  |
| 1     | 259       | 35.48%  |
| 0     | 14        | 1.92%   |
| 3     | 12        | 1.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 554       | 75.37%  |
| Yes  | 181       | 24.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 339       | 52.48%  |
| Realtek Semiconductor           | 86        | 13.31%  |
| Qualcomm Atheros Communications | 58        | 8.98%   |
| IMC Networks                    | 33        | 5.11%   |
| Broadcom                        | 30        | 4.64%   |
| Foxconn / Hon Hai               | 28        | 4.33%   |
| Apple                           | 19        | 2.94%   |
| Lite-On Technology              | 18        | 2.79%   |
| Realtek                         | 7         | 1.08%   |
| Cambridge Silicon Radio         | 6         | 0.93%   |
| Ralink                          | 5         | 0.77%   |
| Hewlett-Packard                 | 4         | 0.62%   |
| Dell                            | 4         | 0.62%   |
| Toshiba                         | 3         | 0.46%   |
| Opticis                         | 2         | 0.31%   |
| ASUSTek Computer                | 2         | 0.31%   |
| USI                             | 1         | 0.15%   |
| Qcom                            | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 102       | 15.79%  |
| Intel AX201 Bluetooth                                                               | 87        | 13.47%  |
| Realtek Bluetooth Radio                                                             | 59        | 9.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 52        | 8.05%   |
| Intel AX200 Bluetooth                                                               | 48        | 7.43%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 28        | 4.33%   |
| Intel AX210 Bluetooth                                                               | 18        | 2.79%   |
| IMC Networks Wireless_Device                                                        | 16        | 2.48%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 14        | 2.17%   |
| Apple Bluetooth Host Controller                                                     | 13        | 2.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 12        | 1.86%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 12        | 1.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 9         | 1.39%   |
| Intel Bluetooth Device                                                              | 9         | 1.39%   |
| IMC Networks Bluetooth Radio                                                        | 9         | 1.39%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 8         | 1.24%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 7         | 1.08%   |
| Realtek Bluetooth Radio                                                             | 7         | 1.08%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 7         | 1.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 6         | 0.93%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 0.93%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 0.93%   |
| Ralink RT3290 Bluetooth                                                             | 5         | 0.77%   |
| Lite-On Wireless_Device                                                             | 5         | 0.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 0.77%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 5         | 0.77%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 5         | 0.77%   |
| Broadcom HP Portable SoftSailing                                                    | 5         | 0.77%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 4         | 0.62%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 0.62%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.62%   |
| Apple Bluetooth USB Host Controller                                                 | 4         | 0.62%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 0.46%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.46%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 3         | 0.46%   |
| Broadcom HP Portable Bumble Bee                                                     | 3         | 0.46%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 0.46%   |
| Qualcomm Atheros Bluetooth                                                          | 2         | 0.31%   |
| Opticis Bluetooth Radio                                                             | 2         | 0.31%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.31%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.31%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.31%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.31%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 2         | 0.31%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 0.31%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 0.31%   |
| Broadcom BCM2045A0                                                                  | 2         | 0.31%   |
| USI Bluetooth Device                                                                | 1         | 0.15%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.15%   |
| Toshiba Bluetooth USB Host Controller                                               | 1         | 0.15%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.15%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.15%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.15%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.15%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.15%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.15%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.15%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.15%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.15%   |
| Foxconn / Hon Hai BT                                                                | 1         | 0.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 532       | 57.2%   |
| AMD                         | 194       | 20.86%  |
| Nvidia                      | 131       | 14.09%  |
| Lenovo                      | 7         | 0.75%   |
| Hewlett-Packard             | 7         | 0.75%   |
| C-Media Electronics         | 7         | 0.75%   |
| Realtek Semiconductor       | 6         | 0.65%   |
| GN Netcom                   | 6         | 0.65%   |
| Plantronics                 | 5         | 0.54%   |
| Conexant Systems            | 3         | 0.32%   |
| XMOS                        | 2         | 0.22%   |
| Texas Instruments           | 2         | 0.22%   |
| Sony                        | 2         | 0.22%   |
| Samson Technologies         | 2         | 0.22%   |
| No brand                    | 2         | 0.22%   |
| Logitech                    | 2         | 0.22%   |
| Focusrite-Novation          | 2         | 0.22%   |
| Creative Technology         | 2         | 0.22%   |
| Sennheiser Communications   | 1         | 0.11%   |
| Samsung Electronics         | 1         | 0.11%   |
| RODE Microphones            | 1         | 0.11%   |
| Razer USA                   | 1         | 0.11%   |
| PreSonus Audio Electronics  | 1         | 0.11%   |
| Generalplus Technology      | 1         | 0.11%   |
| FiiO Electronics Technology | 1         | 0.11%   |
| fifinemicrophone.com        | 1         | 0.11%   |
| FIFINE Microphones          | 1         | 0.11%   |
| Corsair                     | 1         | 0.11%   |
| Cooler Master               | 1         | 0.11%   |
| BR25                        | 1         | 0.11%   |
| bestechnic                  | 1         | 0.11%   |
| BEHRINGER International     | 1         | 0.11%   |
| Apple                       | 1         | 0.11%   |
| AOKEO                       | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 155       | 13.29%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 96        | 8.23%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 92        | 7.89%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 73        | 6.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 53        | 4.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 39        | 3.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 34        | 2.92%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 30        | 2.57%   |
| Intel 8 Series HD Audio Controller                                                                | 30        | 2.57%   |
| Intel Comet Lake PCH cAVS                                                                         | 29        | 2.49%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 27        | 2.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 27        | 2.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 22        | 1.89%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 20        | 1.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 19        | 1.63%   |
| Intel Broadwell-U Audio Controller                                                                | 19        | 1.63%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 18        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 17        | 1.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 1.29%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 14        | 1.2%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 13        | 1.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                                          | 13        | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 1.03%   |
| AMD FCH Azalia Controller                                                                         | 12        | 1.03%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 11        | 0.94%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 0.86%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 10        | 0.86%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 9         | 0.77%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 8         | 0.69%   |
| Intel CM238 HD Audio Controller                                                                   | 8         | 0.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 0.69%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 0.6%    |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.6%    |
| Hewlett-Packard USB Audio                                                                         | 7         | 0.6%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                                           | 7         | 0.6%    |
| Realtek Semiconductor USB Audio                                                                   | 6         | 0.51%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 0.51%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 6         | 0.51%   |
| Nvidia Audio device                                                                               | 6         | 0.51%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 0.51%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 0.51%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 5         | 0.43%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 0.43%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.34%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 4         | 0.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.34%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 0.34%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 0.34%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.26%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.26%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.26%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.26%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 3         | 0.26%   |
| Intel Jasper Lake HD Audio                                                                        | 3         | 0.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.26%   |
| C-Media Electronics USB Audio Device                                                              | 3         | 0.26%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3         | 0.26%   |
| Sony DualShock 4 [CUH-ZCT2x]                                                                      | 2         | 0.17%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 126       | 29.23%  |
| SK hynix                                         | 94        | 21.81%  |
| Micron Technology                                | 68        | 15.78%  |
| Crucial                                          | 27        | 6.26%   |
| Kingston                                         | 26        | 6.03%   |
| Unknown                                          | 18        | 4.18%   |
| Ramaxel Technology                               | 12        | 2.78%   |
| A-DATA Technology                                | 9         | 2.09%   |
| Unknown (ABCD)                                   | 8         | 1.86%   |
| Unknown                                          | 6         | 1.39%   |
| Nanya Technology                                 | 5         | 1.16%   |
| Team                                             | 4         | 0.93%   |
| Smart                                            | 4         | 0.93%   |
| G.Skill                                          | 4         | 0.93%   |
| Patriot                                          | 3         | 0.7%    |
| Elpida                                           | 3         | 0.7%    |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.23%   |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.23%   |
| Smart Brazil                                     | 1         | 0.23%   |
| Silicon Power                                    | 1         | 0.23%   |
| Sesame                                           | 1         | 0.23%   |
| Qimonda                                          | 1         | 0.23%   |
| PNY                                              | 1         | 0.23%   |
| Neo Forza                                        | 1         | 0.23%   |
| Kllisre                                          | 1         | 0.23%   |
| Hikvision                                        | 1         | 0.23%   |
| Goldkey                                          | 1         | 0.23%   |
| Corsair                                          | 1         | 0.23%   |
| ChangXin Memory                                  | 1         | 0.23%   |
| Atermiter                                        | 1         | 0.23%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 11        | 2.43%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 8         | 1.77%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 8         | 1.77%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 6         | 1.32%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 6         | 1.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 6         | 1.32%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 1.32%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 6         | 1.32%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 6         | 1.32%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 6         | 1.32%   |
| Unknown                                                             | 6         | 1.32%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 5         | 1.1%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 1.1%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 4         | 0.88%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 4         | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 4         | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.88%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.88%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.88%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 4         | 0.88%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 3         | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.66%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 0.66%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.66%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 3         | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 0.66%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 3         | 0.66%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 3         | 0.66%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 3         | 0.66%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 3         | 0.66%   |
| Micron RAM 4ATF1G64HZ-3G2B1 8GB Row Of Chips DDR4 3200MT/s          | 3         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.44%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 2         | 0.44%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 2         | 0.44%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 2         | 0.44%   |
| Smart RAM SF4641G8CK8IEHLSBG 8192MB SODIMM DDR4 2667MT/s            | 2         | 0.44%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                        | 2         | 0.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.44%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s             | 2         | 0.44%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.44%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB Row Of Chips DDR4 3200MT/s     | 2         | 0.44%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 2         | 0.44%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.44%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 2         | 0.44%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s      | 2         | 0.44%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s          | 2         | 0.44%   |
| SK hynix RAM H9CCNNNBJTALAR-NUD 4GB Row Of Chips LPDDR3 1867MT/s    | 2         | 0.44%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s          | 2         | 0.44%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                        | 2         | 0.44%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.44%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.44%   |
| Samsung RAM M471B1G73BH0-CK0 8GB SODIMM DDR3 1600MT/s               | 2         | 0.44%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 2         | 0.44%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 2         | 0.44%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s              | 2         | 0.44%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s        | 2         | 0.44%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s           | 2         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 202       | 56.27%  |
| DDR3    | 88        | 24.51%  |
| LPDDR4  | 33        | 9.19%   |
| LPDDR3  | 16        | 4.46%   |
| Unknown | 9         | 2.51%   |
| LPDDR5  | 5         | 1.39%   |
| DDR5    | 3         | 0.84%   |
| DDR2    | 2         | 0.56%   |
| DDR     | 1         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 302       | 80.53%  |
| Row Of Chips | 65        | 17.33%  |
| Chip         | 5         | 1.33%   |
| Unknown      | 2         | 0.53%   |
| DIMM         | 1         | 0.27%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 155       | 39.74%  |
| 4096  | 133       | 34.1%   |
| 16384 | 54        | 13.85%  |
| 2048  | 26        | 6.67%   |
| 32768 | 18        | 4.62%   |
| 1024  | 3         | 0.77%   |
| 3072  | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 111       | 29.13%  |
| 2667    | 75        | 19.69%  |
| 1600    | 68        | 17.85%  |
| 2400    | 27        | 7.09%   |
| 2133    | 17        | 4.46%   |
| 4267    | 14        | 3.67%   |
| 1333    | 11        | 2.89%   |
| 3266    | 8         | 2.1%    |
| 1867    | 8         | 2.1%    |
| 6400    | 7         | 1.84%   |
| 4800    | 7         | 1.84%   |
| 1334    | 6         | 1.57%   |
| 1067    | 6         | 1.57%   |
| Unknown | 4         | 1.05%   |
| 8400    | 3         | 0.79%   |
| 4266    | 3         | 0.79%   |
| 3733    | 2         | 0.52%   |
| 1200    | 1         | 0.26%   |
| 1066    | 1         | 0.26%   |
| 667     | 1         | 0.26%   |
| 533     | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Notebooks | Percent |
|---------------------------|-----------|---------|
| Canon TR150 series        | 1         | 50%     |
| Canon PIXMA MG3500 Series | 1         | 50%     |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 210 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 164       | 23.84%  |
| IMC Networks                           | 99        | 14.39%  |
| Acer                                   | 62        | 9.01%   |
| Microdia                               | 60        | 8.72%   |
| Realtek Semiconductor                  | 50        | 7.27%   |
| Quanta                                 | 42        | 6.1%    |
| Cheng Uei Precision Industry (Foxlink) | 34        | 4.94%   |
| Syntek                                 | 27        | 3.92%   |
| Sunplus Innovation Technology          | 27        | 3.92%   |
| Luxvisions Innotech Limited            | 19        | 2.76%   |
| Apple                                  | 17        | 2.47%   |
| Lite-On Technology                     | 16        | 2.33%   |
| Logitech                               | 11        | 1.6%    |
| Suyin                                  | 9         | 1.31%   |
| Ricoh                                  | 8         | 1.16%   |
| Silicon Motion                         | 6         | 0.87%   |
| Primax Electronics                     | 6         | 0.87%   |
| Samsung Electronics                    | 5         | 0.73%   |
| Alcor Micro                            | 5         | 0.73%   |
| SunplusIT                              | 4         | 0.58%   |
| Sonix Technology                       | 2         | 0.29%   |
| icSpring                               | 2         | 0.29%   |
| Z-Star Microelectronics                | 1         | 0.15%   |
| Xiaomi                                 | 1         | 0.15%   |
| ShineTech                              | 1         | 0.15%   |
| OPPO Electronics                       | 1         | 0.15%   |
| Lenovo                                 | 1         | 0.15%   |
| KYE Systems (Mouse Systems)            | 1         | 0.15%   |
| Intel                                  | 1         | 0.15%   |
| Importek                               | 1         | 0.15%   |
| Hewlett-Packard                        | 1         | 0.15%   |
| Google                                 | 1         | 0.15%   |
| Generalplus Technology                 | 1         | 0.15%   |
| BKX-210918                             | 1         | 0.15%   |
| ARC International                      | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 58        | 8.37%   |
| IMC Networks Integrated Camera                                             | 45        | 6.49%   |
| Microdia Integrated_Webcam_HD                                              | 38        | 5.48%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 29        | 4.18%   |
| Realtek Integrated_Webcam_HD                                               | 22        | 3.17%   |
| Syntek Integrated Camera                                                   | 20        | 2.89%   |
| Acer Integrated Camera                                                     | 19        | 2.74%   |
| Chicony HD Webcam                                                          | 18        | 2.6%    |
| Quanta HD User Facing                                                      | 12        | 1.73%   |
| Chicony Integrated Camera (1280x720@30)                                    | 12        | 1.73%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 11        | 1.59%   |
| Chicony HP Truevision HD camera                                            | 9         | 1.3%    |
| Quanta HP HD Camera                                                        | 8         | 1.15%   |
| Lite-On Integrated Camera                                                  | 8         | 1.15%   |
| Chicony HP Wide Vision HD Camera                                           | 8         | 1.15%   |
| Acer HD Webcam                                                             | 8         | 1.15%   |
| Sunplus Integrated_Webcam_HD                                               | 7         | 1.01%   |
| Quanta HP TrueVision HD Camera                                             | 7         | 1.01%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 7         | 1.01%   |
| Acer Lenovo EasyCamera                                                     | 7         | 1.01%   |
| Primax HP HD Webcam [Fixed]                                                | 6         | 0.87%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                           | 6         | 0.87%   |
| Sunplus HD WebCam                                                          | 5         | 0.72%   |
| Samsung Galaxy series, misc. (MTP mode)                                    | 5         | 0.72%   |
| Chicony USB2.0 HD UVC WebCam                                               | 5         | 0.72%   |
| Chicony USB 2.0 Camera                                                     | 5         | 0.72%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 5         | 0.72%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                              | 5         | 0.72%   |
| Apple Built-in iSight                                                      | 5         | 0.72%   |
| Alcor Micro USB 2.0 Camera                                                 | 5         | 0.72%   |
| Acer BisonCam, NB Pro                                                      | 5         | 0.72%   |
| Syntek EasyCamera                                                          | 4         | 0.58%   |
| Realtek Integrated Webcam                                                  | 4         | 0.58%   |
| Microdia Webcam Vitade AF                                                  | 4         | 0.58%   |
| Lite-On HP HD Camera                                                       | 4         | 0.58%   |
| IMC Networks HD Camera                                                     | 4         | 0.58%   |
| Chicony USB2.0 Camera                                                      | 4         | 0.58%   |
| Chicony EasyCamera                                                         | 4         | 0.58%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD                    | 4         | 0.58%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 4         | 0.58%   |
| Apple FaceTime HD Camera                                                   | 4         | 0.58%   |
| Acer HD Camera                                                             | 4         | 0.58%   |
| Syntek Lenovo EasyCamera                                                   | 3         | 0.43%   |
| Sunplus Laptop Integrated WebCam HD                                        | 3         | 0.43%   |
| Sunplus Integrated_Webcam_FHD                                              | 3         | 0.43%   |
| Ricoh Laptop_Integrated_Webcam_FHD                                         | 3         | 0.43%   |
| Quanta HP Wide Vision HD Camera                                            | 3         | 0.43%   |
| Quanta HP Webcam                                                           | 3         | 0.43%   |
| Quanta HD Webcam                                                           | 3         | 0.43%   |
| Luxvisions Innotech Limited Integrated Camera                              | 3         | 0.43%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                       | 3         | 0.43%   |
| Lite-On HP Wide Vision HD Camera                                           | 3         | 0.43%   |
| Chicony HP Webcam                                                          | 3         | 0.43%   |
| Chicony HP HD Camera                                                       | 3         | 0.43%   |
| Chicony HD User Facing                                                     | 3         | 0.43%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 3         | 0.43%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 3         | 0.43%   |
| Apple FaceTime HD Camera (Built-in)                                        | 3         | 0.43%   |
| Acer USB HD Webcam                                                         | 3         | 0.43%   |
| Acer SunplusIT Integrated Camera                                           | 3         | 0.43%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 66        | 35.87%  |
| Validity Sensors           | 46        | 25%     |
| Shenzhen Goodix Technology | 39        | 21.2%   |
| LighTuning Technology      | 9         | 4.89%   |
| Elan Microelectronics      | 9         | 4.89%   |
| Upek                       | 7         | 3.8%    |
| AuthenTec                  | 4         | 2.17%   |
| Focal-systems.Corp         | 3         | 1.63%   |
| Dell                       | 1         | 0.54%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 32        | 17.39%  |
| Shenzhen Goodix  FingerPrint Device                                        | 24        | 13.04%  |
| Unknown                                                                    | 14        | 7.61%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 6.52%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 10        | 5.43%   |
| Shenzhen Goodix Fingerprint Reader                                         | 8         | 4.35%   |
| Validity Sensors VFS491                                                    | 7         | 3.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 3.8%    |
| Shenzhen Goodix FingerPrint                                                | 7         | 3.8%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 2.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 2.72%   |
| Elan ELAN:ARM-M4                                                           | 5         | 2.72%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 2.17%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 2.17%   |
| Elan ELAN:Fingerprint                                                      | 4         | 2.17%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 1.63%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.63%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 1.63%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 1.09%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.09%   |
| Synaptics WBDI Device                                                      | 2         | 1.09%   |
| Synaptics  WBDI                                                            | 2         | 1.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.09%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 0.54%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.54%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.54%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.54%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.54%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.54%   |
| Dell MS819 Wired Mouse With Fingerprint Reader                             | 1         | 0.54%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.54%   |
| AuthenTec AES2810                                                          | 1         | 0.54%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.54%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 27        | 48.21%  |
| Broadcom                   | 20        | 35.71%  |
| Upek                       | 3         | 5.36%   |
| O2 Micro                   | 2         | 3.57%   |
| OmniKey                    | 1         | 1.79%   |
| Lenovo                     | 1         | 1.79%   |
| Gemalto (was Gemplus)      | 1         | 1.79%   |
| Athena Smartcard Solutions | 1         | 1.79%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 26        | 46.43%  |
| Broadcom 58200                                                               | 7         | 12.5%   |
| Broadcom 5880                                                                | 6         | 10.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 7.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 3         | 5.36%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 5.36%   |
| OmniKey CardMan 1021                                                         | 1         | 1.79%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.79%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 1.79%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 1.79%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.79%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 1.79%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 1.79%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 408       | 55.21%  |
| 1     | 272       | 36.81%  |
| 2     | 49        | 6.63%   |
| 3     | 9         | 1.22%   |
| 8     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 181       | 46.41%  |
| Graphics card         | 85        | 21.79%  |
| Multimedia controller | 37        | 9.49%   |
| Net/wireless          | 23        | 5.9%    |
| Camera                | 20        | 5.13%   |
| Bluetooth             | 11        | 2.82%   |
| Chipcard              | 10        | 2.56%   |
| Card reader           | 8         | 2.05%   |
| Storage               | 5         | 1.28%   |
| Network               | 3         | 0.77%   |
| Net/ethernet          | 3         | 0.77%   |
| Sound                 | 2         | 0.51%   |
| Modem                 | 2         | 0.51%   |

