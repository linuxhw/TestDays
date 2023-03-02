Pop!_OS 22.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

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

Total: 1738

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | Zenbook UX5401ZA_UX5401Z... | [5aad25779a](https://linux-hardware.org/?probe=5aad25779a) | Feb 28, 2023 |
| Acer          | Aspire A515-57              | [6c511739eb](https://linux-hardware.org/?probe=6c511739eb) | Feb 28, 2023 |
| Lenovo        | ThinkPad X270 20HN001RUS    | [ff84200b75](https://linux-hardware.org/?probe=ff84200b75) | Feb 28, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | [88745e1f03](https://linux-hardware.org/?probe=88745e1f03) | Feb 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [357c1abb1d](https://linux-hardware.org/?probe=357c1abb1d) | Feb 27, 2023 |
| Razer         | Blade 15 Base Model (Ear... | [425567e8f3](https://linux-hardware.org/?probe=425567e8f3) | Feb 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | [bd62e34a09](https://linux-hardware.org/?probe=bd62e34a09) | Feb 27, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | [82a40f1881](https://linux-hardware.org/?probe=82a40f1881) | Feb 27, 2023 |
| Acer          | Aspire A515-56              | [97e3001416](https://linux-hardware.org/?probe=97e3001416) | Feb 26, 2023 |
| Dell          | XPS 13 7390                 | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Acer          | Nitro AN515-58              | [1c93095718](https://linux-hardware.org/?probe=1c93095718) | Feb 26, 2023 |
| Sony          | VPCZ12V9R                   | [3014067c24](https://linux-hardware.org/?probe=3014067c24) | Feb 26, 2023 |
| GPU Compan... | GWTN141-10                  | [1550bec17e](https://linux-hardware.org/?probe=1550bec17e) | Feb 25, 2023 |
| GPU Compan... | GWTN141-10                  | [aa535b0731](https://linux-hardware.org/?probe=aa535b0731) | Feb 25, 2023 |
| Dell          | G7 7588                     | [82f1398a69](https://linux-hardware.org/?probe=82f1398a69) | Feb 25, 2023 |
| Alienware     | 15 R3                       | [72543030d5](https://linux-hardware.org/?probe=72543030d5) | Feb 25, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [42b9d60137](https://linux-hardware.org/?probe=42b9d60137) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b5f840e593](https://linux-hardware.org/?probe=b5f840e593) | Feb 25, 2023 |
| System76      | Galago Pro                  | [3e4391562b](https://linux-hardware.org/?probe=3e4391562b) | Feb 25, 2023 |
| Packard Be... | EasyNote TS11HR             | [0a63352761](https://linux-hardware.org/?probe=0a63352761) | Feb 25, 2023 |
| Dell          | XPS 15 9500                 | [96e6c2c201](https://linux-hardware.org/?probe=96e6c2c201) | Feb 25, 2023 |
| Dell          | Latitude 3310               | [d989647d9d](https://linux-hardware.org/?probe=d989647d9d) | Feb 25, 2023 |
| Acer          | Aspire A515-56              | [517a6211c9](https://linux-hardware.org/?probe=517a6211c9) | Feb 24, 2023 |
| HP            | ProBook 450 G1              | [f7c4b009f1](https://linux-hardware.org/?probe=f7c4b009f1) | Feb 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [297c37ec04](https://linux-hardware.org/?probe=297c37ec04) | Feb 24, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [2f561a23c3](https://linux-hardware.org/?probe=2f561a23c3) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [041c57ebe6](https://linux-hardware.org/?probe=041c57ebe6) | Feb 24, 2023 |
| Apple         | MacBookPro9,2               | [c591acd5d6](https://linux-hardware.org/?probe=c591acd5d6) | Feb 24, 2023 |
| Dell          | Inspiron 5423               | [7cf47f3118](https://linux-hardware.org/?probe=7cf47f3118) | Feb 23, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [00591dc764](https://linux-hardware.org/?probe=00591dc764) | Feb 23, 2023 |
| Lenovo        | ThinkPad T430s 2356CU8      | [bb0d8e868d](https://linux-hardware.org/?probe=bb0d8e868d) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| System76      | Gazelle                     | [609f452af9](https://linux-hardware.org/?probe=609f452af9) | Feb 23, 2023 |
| ONE-NETBOO... | ONE XPLAYER 1002-C          | [33a4731a5e](https://linux-hardware.org/?probe=33a4731a5e) | Feb 23, 2023 |
| Dell          | Latitude E7240              | [7f8278ff44](https://linux-hardware.org/?probe=7f8278ff44) | Feb 23, 2023 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [34016a67d9](https://linux-hardware.org/?probe=34016a67d9) | Feb 22, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [312937f0d0](https://linux-hardware.org/?probe=312937f0d0) | Feb 22, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | [6ab727e8c0](https://linux-hardware.org/?probe=6ab727e8c0) | Feb 22, 2023 |
| Apple         | MacBookPro11,4              | [c4eab564b3](https://linux-hardware.org/?probe=c4eab564b3) | Feb 22, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [af2d2bd596](https://linux-hardware.org/?probe=af2d2bd596) | Feb 21, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [41b4e0957f](https://linux-hardware.org/?probe=41b4e0957f) | Feb 21, 2023 |
| HP            | EliteBook Folio 1040 G2     | [265018acd3](https://linux-hardware.org/?probe=265018acd3) | Feb 21, 2023 |
| Apple         | MacBookPro16,1              | [a5cff07fd8](https://linux-hardware.org/?probe=a5cff07fd8) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [022527aa4c](https://linux-hardware.org/?probe=022527aa4c) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [3b1afb00a2](https://linux-hardware.org/?probe=3b1afb00a2) | Feb 21, 2023 |
| Dell          | G15 5525                    | [63bd2ac7b9](https://linux-hardware.org/?probe=63bd2ac7b9) | Feb 21, 2023 |
| Acer          | Swift SF114-34              | [e9f5a9d293](https://linux-hardware.org/?probe=e9f5a9d293) | Feb 21, 2023 |
| Dell          | Precision M4800             | [b8e31b63ce](https://linux-hardware.org/?probe=b8e31b63ce) | Feb 20, 2023 |
| HP            | Laptop 14s-fq0xxx           | [0bc03f3b39](https://linux-hardware.org/?probe=0bc03f3b39) | Feb 20, 2023 |
| HP            | ProBook 450 G1              | [b5e8826f8c](https://linux-hardware.org/?probe=b5e8826f8c) | Feb 20, 2023 |
| Dell          | XPS 15 7590                 | [297b06716d](https://linux-hardware.org/?probe=297b06716d) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [d4fdbbf1ba](https://linux-hardware.org/?probe=d4fdbbf1ba) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [a11d164d69](https://linux-hardware.org/?probe=a11d164d69) | Feb 19, 2023 |
| Apple         | MacBook4,1                  | [2011c2060b](https://linux-hardware.org/?probe=2011c2060b) | Feb 19, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [cc0e711862](https://linux-hardware.org/?probe=cc0e711862) | Feb 18, 2023 |
| HP            | 240 G6 Notebook PC          | [fc39dde214](https://linux-hardware.org/?probe=fc39dde214) | Feb 18, 2023 |
| Dell          | Latitude E7240              | [461873da2d](https://linux-hardware.org/?probe=461873da2d) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [5cc4ff8271](https://linux-hardware.org/?probe=5cc4ff8271) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [75f9e575b3](https://linux-hardware.org/?probe=75f9e575b3) | Feb 18, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [f120e182a1](https://linux-hardware.org/?probe=f120e182a1) | Feb 17, 2023 |
| HUAWEI        | BOD-WXX9                    | [a56a788adf](https://linux-hardware.org/?probe=a56a788adf) | Feb 17, 2023 |
| HP            | EliteBook 830 G5            | [7ef47e7131](https://linux-hardware.org/?probe=7ef47e7131) | Feb 17, 2023 |
| HONOR         | NBR-WAX9                    | [b16ea0055d](https://linux-hardware.org/?probe=b16ea0055d) | Feb 17, 2023 |
| Dell          | Latitude E4200              | [18868db8a1](https://linux-hardware.org/?probe=18868db8a1) | Feb 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [91c566ccc9](https://linux-hardware.org/?probe=91c566ccc9) | Feb 16, 2023 |
| Apple         | MacBookPro9,2               | [e67f600749](https://linux-hardware.org/?probe=e67f600749) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C7C... | [2b0904349a](https://linux-hardware.org/?probe=2b0904349a) | Feb 16, 2023 |
| Lenovo        | G50-80 80E5                 | [64c385ee36](https://linux-hardware.org/?probe=64c385ee36) | Feb 16, 2023 |
| OriginPC      | Voyager a1600               | [9608c5afd5](https://linux-hardware.org/?probe=9608c5afd5) | Feb 16, 2023 |
| Google        | Blorb                       | [286353731c](https://linux-hardware.org/?probe=286353731c) | Feb 16, 2023 |
| Lenovo        | ThinkPad T530 2392AQU       | [1b89c43b58](https://linux-hardware.org/?probe=1b89c43b58) | Feb 16, 2023 |
| HP            | EliteBook 850 G2            | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [74a61dff13](https://linux-hardware.org/?probe=74a61dff13) | Feb 15, 2023 |
| Apple         | MacBookPro12,1              | [bdb6e585b0](https://linux-hardware.org/?probe=bdb6e585b0) | Feb 15, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | [5c4a26ada0](https://linux-hardware.org/?probe=5c4a26ada0) | Feb 14, 2023 |
| Dell          | Precision M3800             | [98b54858cb](https://linux-hardware.org/?probe=98b54858cb) | Feb 14, 2023 |
| Dell          | Inspiron 15 3511            | [1028ef9686](https://linux-hardware.org/?probe=1028ef9686) | Feb 14, 2023 |
| MSI           | Prestige 14Evo A11M         | [abeebd4312](https://linux-hardware.org/?probe=abeebd4312) | Feb 13, 2023 |
| Sony          | VPCEG27FM                   | [748a67669f](https://linux-hardware.org/?probe=748a67669f) | Feb 13, 2023 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | [a6af7624cd](https://linux-hardware.org/?probe=a6af7624cd) | Feb 13, 2023 |
| Samsung       | 730U3E/740U3E               | [91ac69dfa1](https://linux-hardware.org/?probe=91ac69dfa1) | Feb 13, 2023 |
| Lenovo        | ThinkPad T410 2522G76       | [b15d4051cd](https://linux-hardware.org/?probe=b15d4051cd) | Feb 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [d38212ee96](https://linux-hardware.org/?probe=d38212ee96) | Feb 13, 2023 |
| Apple         | MacBookPro11,2              | [2314b98760](https://linux-hardware.org/?probe=2314b98760) | Feb 12, 2023 |
| Apple         | MacBookPro12,1              | [139b92595a](https://linux-hardware.org/?probe=139b92595a) | Feb 12, 2023 |
| Haier         | GG1500A                     | [4c4598157f](https://linux-hardware.org/?probe=4c4598157f) | Feb 12, 2023 |
| Dell          | Latitude XT2                | [9b98bf4722](https://linux-hardware.org/?probe=9b98bf4722) | Feb 12, 2023 |
| Dell          | Precision M4700             | [1a44cb5ef9](https://linux-hardware.org/?probe=1a44cb5ef9) | Feb 11, 2023 |
| Apple         | MacBookPro11,1              | [fb407bfc13](https://linux-hardware.org/?probe=fb407bfc13) | Feb 11, 2023 |
| Lenovo        | ThinkPad T470s 20HFCT01W... | [322a9d340e](https://linux-hardware.org/?probe=322a9d340e) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | [ab07f075d8](https://linux-hardware.org/?probe=ab07f075d8) | Feb 11, 2023 |
| Apple         | MacBook8,1                  | [2f1c5b90a8](https://linux-hardware.org/?probe=2f1c5b90a8) | Feb 11, 2023 |
| Lenovo        | G50-45 80E3                 | [24cb179c5a](https://linux-hardware.org/?probe=24cb179c5a) | Feb 11, 2023 |
| MSI           | GF63 Thin 9RCX              | [9cbcfdd748](https://linux-hardware.org/?probe=9cbcfdd748) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | G15 5520                    | [121b06f3cc](https://linux-hardware.org/?probe=121b06f3cc) | Feb 10, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [d0cc5f80fc](https://linux-hardware.org/?probe=d0cc5f80fc) | Feb 09, 2023 |
| HP            | EliteBook 840 G5            | [39dbdb0fa9](https://linux-hardware.org/?probe=39dbdb0fa9) | Feb 09, 2023 |
| Lenovo        | ThinkPad T450 20BUA0PNUK    | [8837c33007](https://linux-hardware.org/?probe=8837c33007) | Feb 09, 2023 |
| Dell          | Venue 11 Pro 7130 MS        | [74dd2176ff](https://linux-hardware.org/?probe=74dd2176ff) | Feb 09, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | [93afe9ddeb](https://linux-hardware.org/?probe=93afe9ddeb) | Feb 09, 2023 |
| Dell          | Inspiron 3576               | [a025641dfc](https://linux-hardware.org/?probe=a025641dfc) | Feb 09, 2023 |
| Acer          | Aspire A315-59              | [edc6b0a3af](https://linux-hardware.org/?probe=edc6b0a3af) | Feb 09, 2023 |
| Dell          | XPS 13 9360                 | [db7e89340f](https://linux-hardware.org/?probe=db7e89340f) | Feb 09, 2023 |
| System76      | Lemur Pro                   | [94cf78a9d9](https://linux-hardware.org/?probe=94cf78a9d9) | Feb 08, 2023 |
| Dell          | G15 5520                    | [7f4d36cea1](https://linux-hardware.org/?probe=7f4d36cea1) | Feb 08, 2023 |
| HP            | EliteBook 830 G5            | [5554154df2](https://linux-hardware.org/?probe=5554154df2) | Feb 07, 2023 |
| Dell          | System XPS L702X            | [cdbc3578d0](https://linux-hardware.org/?probe=cdbc3578d0) | Feb 07, 2023 |
| Alienware     | m15 R7                      | [254ab40fcf](https://linux-hardware.org/?probe=254ab40fcf) | Feb 07, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [f6c24b1ea8](https://linux-hardware.org/?probe=f6c24b1ea8) | Feb 07, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [50af8c9fe6](https://linux-hardware.org/?probe=50af8c9fe6) | Feb 06, 2023 |
| ASUSTek       | UX430UNR                    | [96d7a1938a](https://linux-hardware.org/?probe=96d7a1938a) | Feb 06, 2023 |
| Acer          | Swift SF114-34              | [28aad1fae5](https://linux-hardware.org/?probe=28aad1fae5) | Feb 06, 2023 |
| ASUSTek       | X751LD                      | [12d5592082](https://linux-hardware.org/?probe=12d5592082) | Feb 06, 2023 |
| Notebook      | NJ50_70CU                   | [c0c9951f8d](https://linux-hardware.org/?probe=c0c9951f8d) | Feb 05, 2023 |
| Dell          | Latitude 7380               | [7b9d4ef8b4](https://linux-hardware.org/?probe=7b9d4ef8b4) | Feb 05, 2023 |
| Acer          | Swift SF114-34              | [ea8a0e0617](https://linux-hardware.org/?probe=ea8a0e0617) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [5c2bd1284d](https://linux-hardware.org/?probe=5c2bd1284d) | Feb 05, 2023 |
| Alienware     | 17 R5                       | [7f5f8bdb1f](https://linux-hardware.org/?probe=7f5f8bdb1f) | Feb 05, 2023 |
| Fujitsu       | LIFEBOOK T902               | [9c92a1772d](https://linux-hardware.org/?probe=9c92a1772d) | Feb 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d95f28d447](https://linux-hardware.org/?probe=d95f28d447) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | [a705eb3101](https://linux-hardware.org/?probe=a705eb3101) | Feb 05, 2023 |
| Apple         | MacBookPro5,4               | [7a80b2d6d7](https://linux-hardware.org/?probe=7a80b2d6d7) | Feb 05, 2023 |
| Lenovo        | ThinkPad E580 20KSCTO1WW    | [e5e8537cef](https://linux-hardware.org/?probe=e5e8537cef) | Feb 05, 2023 |
| HP            | Laptop 15-bw0xx             | [0cb9ba3cf9](https://linux-hardware.org/?probe=0cb9ba3cf9) | Feb 05, 2023 |
| ASUSTek       | X751LD                      | [13948b75ae](https://linux-hardware.org/?probe=13948b75ae) | Feb 05, 2023 |
| VANT          | MOOVE3-14                   | [b5ac9ebd7c](https://linux-hardware.org/?probe=b5ac9ebd7c) | Feb 05, 2023 |
| HP            | Notebook                    | [0ad701667d](https://linux-hardware.org/?probe=0ad701667d) | Feb 05, 2023 |
| HP            | Notebook                    | [37f601798c](https://linux-hardware.org/?probe=37f601798c) | Feb 05, 2023 |
| Dell          | G15 5515                    | [7418ca82c1](https://linux-hardware.org/?probe=7418ca82c1) | Feb 04, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [fd2b67e6ab](https://linux-hardware.org/?probe=fd2b67e6ab) | Feb 04, 2023 |
| Dell          | Latitude 3520               | [ce594f431c](https://linux-hardware.org/?probe=ce594f431c) | Feb 04, 2023 |
| Acer          | Aspire A515-51G             | [149465f225](https://linux-hardware.org/?probe=149465f225) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [448d3800ac](https://linux-hardware.org/?probe=448d3800ac) | Feb 04, 2023 |
| Toshiba       | Satellite C855-233          | [8fc7835588](https://linux-hardware.org/?probe=8fc7835588) | Feb 04, 2023 |
| Lenovo        | ThinkPad P50 20EN0017US     | [43c5ab14ec](https://linux-hardware.org/?probe=43c5ab14ec) | Feb 03, 2023 |
| Dell          | Latitude E7240              | [da54499919](https://linux-hardware.org/?probe=da54499919) | Feb 03, 2023 |
| Haier         | GG1500A                     | [b54ce000d3](https://linux-hardware.org/?probe=b54ce000d3) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [98ad1bcab4](https://linux-hardware.org/?probe=98ad1bcab4) | Feb 03, 2023 |
| Star Labs     | StarBook                    | [5fe174bdd1](https://linux-hardware.org/?probe=5fe174bdd1) | Feb 03, 2023 |
| Acer          | Aspire A315-59              | [704c6e370c](https://linux-hardware.org/?probe=704c6e370c) | Feb 03, 2023 |
| Timi          | RedmiBook Pro 15S           | [8a1c423c67](https://linux-hardware.org/?probe=8a1c423c67) | Feb 03, 2023 |
| Apple         | MacBookPro8,1               | [c441c159c1](https://linux-hardware.org/?probe=c441c159c1) | Feb 03, 2023 |
| HP            | Laptop 15-db1xxx            | [8944f22b68](https://linux-hardware.org/?probe=8944f22b68) | Feb 02, 2023 |
| Acer          | Swift SF114-32              | [96b48bebd2](https://linux-hardware.org/?probe=96b48bebd2) | Feb 02, 2023 |
| Dell          | Inspiron 3584               | [4bfcbe7c13](https://linux-hardware.org/?probe=4bfcbe7c13) | Feb 02, 2023 |
| Dell          | Precision 3571              | [8ee8f6f768](https://linux-hardware.org/?probe=8ee8f6f768) | Feb 02, 2023 |
| Dell          | Precision 3571              | [9453f26568](https://linux-hardware.org/?probe=9453f26568) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [8db619716a](https://linux-hardware.org/?probe=8db619716a) | Feb 02, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [7019bd88e0](https://linux-hardware.org/?probe=7019bd88e0) | Feb 01, 2023 |
| HP            | Pavilion 15                 | [946fec8f7d](https://linux-hardware.org/?probe=946fec8f7d) | Feb 01, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [6294616fc6](https://linux-hardware.org/?probe=6294616fc6) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| Timi          | Mi NoteBook Ultra           | [d897ec0114](https://linux-hardware.org/?probe=d897ec0114) | Feb 01, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [c4869ecf2c](https://linux-hardware.org/?probe=c4869ecf2c) | Feb 01, 2023 |
| Acer          | Predator PH517-61           | [b16ddc31d8](https://linux-hardware.org/?probe=b16ddc31d8) | Feb 01, 2023 |
| Dell          | Latitude E7240              | [fe655eca77](https://linux-hardware.org/?probe=fe655eca77) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [3803fd2405](https://linux-hardware.org/?probe=3803fd2405) | Jan 31, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [db8bdbd72b](https://linux-hardware.org/?probe=db8bdbd72b) | Jan 31, 2023 |
| Dell          | Inspiron 7400               | [a6b124fd34](https://linux-hardware.org/?probe=a6b124fd34) | Jan 31, 2023 |
| Apple         | MacBookPro12,1              | [228ab40738](https://linux-hardware.org/?probe=228ab40738) | Jan 31, 2023 |
| HP            | Notebook                    | [82d58b21c4](https://linux-hardware.org/?probe=82d58b21c4) | Jan 31, 2023 |
| HP            | ZBook Studio G3             | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| HP            | ENVY Laptop 13-ah0xxx       | [7636aeaacc](https://linux-hardware.org/?probe=7636aeaacc) | Jan 31, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [230b38f8e6](https://linux-hardware.org/?probe=230b38f8e6) | Jan 31, 2023 |
| Acer          | Swift SF114-32              | [82d317899e](https://linux-hardware.org/?probe=82d317899e) | Jan 31, 2023 |
| Dell          | XPS 15 9500                 | [6a0af9dbcb](https://linux-hardware.org/?probe=6a0af9dbcb) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [2474b4641c](https://linux-hardware.org/?probe=2474b4641c) | Jan 30, 2023 |
| GPU Compan... | GWTN141-10                  | [f012d6d71c](https://linux-hardware.org/?probe=f012d6d71c) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [d4aec33c44](https://linux-hardware.org/?probe=d4aec33c44) | Jan 30, 2023 |
| ASUSTek       | UX310UQK                    | [58e7588538](https://linux-hardware.org/?probe=58e7588538) | Jan 30, 2023 |
| Acer          | Swift SF114-32              | [1228d6d0f7](https://linux-hardware.org/?probe=1228d6d0f7) | Jan 30, 2023 |
| Dell          | G15 5511                    | [36214ba4de](https://linux-hardware.org/?probe=36214ba4de) | Jan 30, 2023 |
| Dell          | Latitude E7240              | [a1f713f6e3](https://linux-hardware.org/?probe=a1f713f6e3) | Jan 30, 2023 |
| Avell High... | B11 MOB                     | [dd9d29ddc7](https://linux-hardware.org/?probe=dd9d29ddc7) | Jan 30, 2023 |
| Acer          | Aspire A515-45              | [42405a6a0c](https://linux-hardware.org/?probe=42405a6a0c) | Jan 30, 2023 |
| HP            | Pavilion dv6                | [0966ae419c](https://linux-hardware.org/?probe=0966ae419c) | Jan 30, 2023 |
| ASUSTek       | X555LD                      | [b70d834fe5](https://linux-hardware.org/?probe=b70d834fe5) | Jan 29, 2023 |
| Dell          | G15 5515                    | [1be125c3cd](https://linux-hardware.org/?probe=1be125c3cd) | Jan 29, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [ff3381fe1a](https://linux-hardware.org/?probe=ff3381fe1a) | Jan 28, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [c6770f3828](https://linux-hardware.org/?probe=c6770f3828) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| ASUSTek       | ET2321I                     | [dbb162975e](https://linux-hardware.org/?probe=dbb162975e) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | [549b690251](https://linux-hardware.org/?probe=549b690251) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| MSI           | Vector GP76 12UHSO          | [cbbd1d3e3e](https://linux-hardware.org/?probe=cbbd1d3e3e) | Jan 28, 2023 |
| Dell          | XPS 13 9305                 | [684b829dbb](https://linux-hardware.org/?probe=684b829dbb) | Jan 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ce2955973a](https://linux-hardware.org/?probe=ce2955973a) | Jan 27, 2023 |
| System76      | Lemur Pro                   | [40c5731c48](https://linux-hardware.org/?probe=40c5731c48) | Jan 27, 2023 |
| Clevo         | W150HNM/W170HN              | [63709a14ca](https://linux-hardware.org/?probe=63709a14ca) | Jan 27, 2023 |
| Dell          | Latitude E7240              | [d88cdedff3](https://linux-hardware.org/?probe=d88cdedff3) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [df04ffbd50](https://linux-hardware.org/?probe=df04ffbd50) | Jan 26, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [b2ffc58bb1](https://linux-hardware.org/?probe=b2ffc58bb1) | Jan 26, 2023 |
| Dell          | G3 3590                     | [8a7e4e4db0](https://linux-hardware.org/?probe=8a7e4e4db0) | Jan 26, 2023 |
| System76      | Lemur Pro                   | [097cd4c9f8](https://linux-hardware.org/?probe=097cd4c9f8) | Jan 26, 2023 |
| Gigabyte      | A5 K1                       | [e0771eb5f6](https://linux-hardware.org/?probe=e0771eb5f6) | Jan 25, 2023 |
| HP            | ProBook 6550b               | [c7983e417c](https://linux-hardware.org/?probe=c7983e417c) | Jan 25, 2023 |
| Timi          | RedmiBook Pro 15S           | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [bc56140257](https://linux-hardware.org/?probe=bc56140257) | Jan 25, 2023 |
| Gigabyte      | A5 K1                       | [d5e00555ca](https://linux-hardware.org/?probe=d5e00555ca) | Jan 25, 2023 |
| Dell          | Inspiron 13-7353            | [5ebcba8c52](https://linux-hardware.org/?probe=5ebcba8c52) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [2d488752b6](https://linux-hardware.org/?probe=2d488752b6) | Jan 25, 2023 |
| Dell          | System Inspiron N7110       | [935a295b28](https://linux-hardware.org/?probe=935a295b28) | Jan 25, 2023 |
| ASUSTek       | N551JW                      | [9694a30eff](https://linux-hardware.org/?probe=9694a30eff) | Jan 25, 2023 |
| Dell          | Latitude E7240              | [9d44efa2f9](https://linux-hardware.org/?probe=9d44efa2f9) | Jan 24, 2023 |
| Acer          | Swift SFA16-41              | [1c05334105](https://linux-hardware.org/?probe=1c05334105) | Jan 24, 2023 |
| LG Electro... | 17Z90Q-K.AAC7U1             | [73a0023203](https://linux-hardware.org/?probe=73a0023203) | Jan 24, 2023 |
| Google        | Link                        | [5c44e38153](https://linux-hardware.org/?probe=5c44e38153) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [f6e09cc9fb](https://linux-hardware.org/?probe=f6e09cc9fb) | Jan 23, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [306e6ae925](https://linux-hardware.org/?probe=306e6ae925) | Jan 23, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [821e7b4330](https://linux-hardware.org/?probe=821e7b4330) | Jan 22, 2023 |
| Purism        | Librem 15 v3                | [fcb1d44df6](https://linux-hardware.org/?probe=fcb1d44df6) | Jan 22, 2023 |
| Dell          | Latitude E5470              | [1a2810f035](https://linux-hardware.org/?probe=1a2810f035) | Jan 22, 2023 |
| HP            | Notebook                    | [57bf6826ef](https://linux-hardware.org/?probe=57bf6826ef) | Jan 22, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | [0729d0a10f](https://linux-hardware.org/?probe=0729d0a10f) | Jan 22, 2023 |
| Dell          | XPS 13 9350                 | [223ab1f016](https://linux-hardware.org/?probe=223ab1f016) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [9b3b21f5b7](https://linux-hardware.org/?probe=9b3b21f5b7) | Jan 21, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [22d9f43ef5](https://linux-hardware.org/?probe=22d9f43ef5) | Jan 21, 2023 |
| Razer x La... | TensorBook (late 2021)      | [9062d4274f](https://linux-hardware.org/?probe=9062d4274f) | Jan 21, 2023 |
| Dell          | Latitude 5300               | [e8c4218110](https://linux-hardware.org/?probe=e8c4218110) | Jan 21, 2023 |
| Lenovo        | ThinkPad T530 23943J8       | [1da6722b35](https://linux-hardware.org/?probe=1da6722b35) | Jan 21, 2023 |
| Dell          | Inspiron 5505               | [9a17165647](https://linux-hardware.org/?probe=9a17165647) | Jan 20, 2023 |
| Dell          | Inspiron 5505               | [e1003a85c9](https://linux-hardware.org/?probe=e1003a85c9) | Jan 20, 2023 |
| ASUSTek       | X442URR                     | [6104ee1f65](https://linux-hardware.org/?probe=6104ee1f65) | Jan 20, 2023 |
| Dell          | Latitude E7240              | [a4e01b187f](https://linux-hardware.org/?probe=a4e01b187f) | Jan 20, 2023 |
| HP            | Laptop 15-bw0xx             | [0bf7ea6726](https://linux-hardware.org/?probe=0bf7ea6726) | Jan 20, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [c1169d55de](https://linux-hardware.org/?probe=c1169d55de) | Jan 19, 2023 |
| Dell          | Latitude E7240              | [475187029d](https://linux-hardware.org/?probe=475187029d) | Jan 19, 2023 |
| ASUSTek       | ROG Strix G512LU_G512LU     | [edc36777f0](https://linux-hardware.org/?probe=edc36777f0) | Jan 19, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [b318baed4f](https://linux-hardware.org/?probe=b318baed4f) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| Razer         | Blade                       | [b3f154ac11](https://linux-hardware.org/?probe=b3f154ac11) | Jan 19, 2023 |
| Dell          | G5 5590                     | [01888c3049](https://linux-hardware.org/?probe=01888c3049) | Jan 19, 2023 |
| Dell          | Latitude E6540              | [440b0eec1c](https://linux-hardware.org/?probe=440b0eec1c) | Jan 18, 2023 |
| MSI           | Alpha 15 A3DDK              | [832ee11e43](https://linux-hardware.org/?probe=832ee11e43) | Jan 18, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [81d4385a14](https://linux-hardware.org/?probe=81d4385a14) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | [933f67b6b5](https://linux-hardware.org/?probe=933f67b6b5) | Jan 18, 2023 |
| Dell          | Precision 7670              | [5c70243651](https://linux-hardware.org/?probe=5c70243651) | Jan 18, 2023 |
| Lenovo        | ThinkPad T560 20FH001QUS    | [48a56bd8c2](https://linux-hardware.org/?probe=48a56bd8c2) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [ac28c1fba4](https://linux-hardware.org/?probe=ac28c1fba4) | Jan 18, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | [45e2d0fb2d](https://linux-hardware.org/?probe=45e2d0fb2d) | Jan 18, 2023 |
| Dell          | Latitude E5440              | [eb945eac4e](https://linux-hardware.org/?probe=eb945eac4e) | Jan 18, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [8bf0f8c8fe](https://linux-hardware.org/?probe=8bf0f8c8fe) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [18d3c84771](https://linux-hardware.org/?probe=18d3c84771) | Jan 17, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | [bd0bc47120](https://linux-hardware.org/?probe=bd0bc47120) | Jan 17, 2023 |
| Framework     | Laptop                      | [e94774a411](https://linux-hardware.org/?probe=e94774a411) | Jan 17, 2023 |
| Acer          | Aspire 5625G                | [244d8473fc](https://linux-hardware.org/?probe=244d8473fc) | Jan 16, 2023 |
| Dell          | Latitude E7240              | [dc47f005d6](https://linux-hardware.org/?probe=dc47f005d6) | Jan 16, 2023 |
| Lenovo        | IdeaPad Y570 0862           | [8c43e56714](https://linux-hardware.org/?probe=8c43e56714) | Jan 16, 2023 |
| Chuwi         | GemiBook Pro                | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| System76      | Lemur Pro                   | [fde9d32359](https://linux-hardware.org/?probe=fde9d32359) | Jan 16, 2023 |
| Apple         | MacBook8,1                  | [64b089dfb7](https://linux-hardware.org/?probe=64b089dfb7) | Jan 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [db57593b81](https://linux-hardware.org/?probe=db57593b81) | Jan 14, 2023 |
| MSI           | Bravo 15 B5DD               | [ffb8653d34](https://linux-hardware.org/?probe=ffb8653d34) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [76f54ae84c](https://linux-hardware.org/?probe=76f54ae84c) | Jan 14, 2023 |
| Dell          | Precision 3571              | [c71e32c6ea](https://linux-hardware.org/?probe=c71e32c6ea) | Jan 14, 2023 |
| Acer          | Predator PT315-52           | [149941b52c](https://linux-hardware.org/?probe=149941b52c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [9eed89d744](https://linux-hardware.org/?probe=9eed89d744) | Jan 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [d10834c7df](https://linux-hardware.org/?probe=d10834c7df) | Jan 14, 2023 |
| System76      | Oryx Pro                    | [da1374fa1c](https://linux-hardware.org/?probe=da1374fa1c) | Jan 14, 2023 |
| Dell          | Latitude E7240              | [ed7ff7569c](https://linux-hardware.org/?probe=ed7ff7569c) | Jan 14, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | [2860788f11](https://linux-hardware.org/?probe=2860788f11) | Jan 14, 2023 |
| HONOR         | NMH-WCX9                    | [10a9c33aed](https://linux-hardware.org/?probe=10a9c33aed) | Jan 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [362d8c4594](https://linux-hardware.org/?probe=362d8c4594) | Jan 13, 2023 |
| Dell          | Latitude 5300               | [148745c883](https://linux-hardware.org/?probe=148745c883) | Jan 13, 2023 |
| HP            | EliteBook 8570w             | [84035db95c](https://linux-hardware.org/?probe=84035db95c) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | [96a079dbf8](https://linux-hardware.org/?probe=96a079dbf8) | Jan 13, 2023 |
| Lenovo        | ThinkPad T500 2081CTO       | [53b39e47e9](https://linux-hardware.org/?probe=53b39e47e9) | Jan 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS2BM00    | [afefa18c04](https://linux-hardware.org/?probe=afefa18c04) | Jan 12, 2023 |
| HP            | Dev One Notebook PC         | [f7304c0af2](https://linux-hardware.org/?probe=f7304c0af2) | Jan 12, 2023 |
| Samsung       | 270E5J/2570EJ               | [22f9a03d68](https://linux-hardware.org/?probe=22f9a03d68) | Jan 12, 2023 |
| HP            | EliteBook 840 G5            | [a62af2c5a8](https://linux-hardware.org/?probe=a62af2c5a8) | Jan 11, 2023 |
| Dell          | Latitude E7240              | [93d832d08f](https://linux-hardware.org/?probe=93d832d08f) | Jan 11, 2023 |
| Lenovo        | IdeaPad Y570 20091          | [3538dd1b8a](https://linux-hardware.org/?probe=3538dd1b8a) | Jan 11, 2023 |
| Acer          | TravelMate P245-M           | [1722e41c8d](https://linux-hardware.org/?probe=1722e41c8d) | Jan 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [0f1f6b2662](https://linux-hardware.org/?probe=0f1f6b2662) | Jan 11, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a2363c6939](https://linux-hardware.org/?probe=a2363c6939) | Jan 11, 2023 |
| Acer          | Swift SF314-56              | [456445a93c](https://linux-hardware.org/?probe=456445a93c) | Jan 10, 2023 |
| Dell          | Latitude E7240              | [83a785903b](https://linux-hardware.org/?probe=83a785903b) | Jan 10, 2023 |
| HP            | EliteBook 840 G5            | [0eb6418a53](https://linux-hardware.org/?probe=0eb6418a53) | Jan 10, 2023 |
| HP            | OMEN by Laptop              | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| Razer x La... | TensorBook (late 2021)      | [d798473e75](https://linux-hardware.org/?probe=d798473e75) | Jan 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [e384aea51e](https://linux-hardware.org/?probe=e384aea51e) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [1829eed17a](https://linux-hardware.org/?probe=1829eed17a) | Jan 09, 2023 |
| Dell          | Latitude E7240              | [c191d76ac2](https://linux-hardware.org/?probe=c191d76ac2) | Jan 09, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [07cc23f1cd](https://linux-hardware.org/?probe=07cc23f1cd) | Jan 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [d784655474](https://linux-hardware.org/?probe=d784655474) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [7e17526b20](https://linux-hardware.org/?probe=7e17526b20) | Jan 08, 2023 |
| Notebook      | PCX0DX                      | [698649c9ae](https://linux-hardware.org/?probe=698649c9ae) | Jan 08, 2023 |
| Dell          | Latitude E7240              | [c7cf2afdd9](https://linux-hardware.org/?probe=c7cf2afdd9) | Jan 07, 2023 |
| HP            | ENVY dv6                    | [2a01900cb1](https://linux-hardware.org/?probe=2a01900cb1) | Jan 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [f191d63ace](https://linux-hardware.org/?probe=f191d63ace) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [7018e90a09](https://linux-hardware.org/?probe=7018e90a09) | Jan 07, 2023 |
| System76      | Bonobo WS                   | [afb9abd3c6](https://linux-hardware.org/?probe=afb9abd3c6) | Jan 07, 2023 |
| Dell          | Latitude E7240              | [d4dc080444](https://linux-hardware.org/?probe=d4dc080444) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [ab9f1d1812](https://linux-hardware.org/?probe=ab9f1d1812) | Jan 07, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [bf425a41f8](https://linux-hardware.org/?probe=bf425a41f8) | Jan 07, 2023 |
| Lenovo        | G580 20157                  | [63bc1e725c](https://linux-hardware.org/?probe=63bc1e725c) | Jan 07, 2023 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [43f6676d9d](https://linux-hardware.org/?probe=43f6676d9d) | Jan 06, 2023 |
| Dell          | Latitude 7520               | [f4f253a52b](https://linux-hardware.org/?probe=f4f253a52b) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [67f40c78ec](https://linux-hardware.org/?probe=67f40c78ec) | Jan 06, 2023 |
| Apple         | MacBookPro12,1              | [58f2e834d8](https://linux-hardware.org/?probe=58f2e834d8) | Jan 06, 2023 |
| Dell          | Precision M4700             | [414d8c4701](https://linux-hardware.org/?probe=414d8c4701) | Jan 06, 2023 |
| Dell          | Latitude E7240              | [b00208bba7](https://linux-hardware.org/?probe=b00208bba7) | Jan 06, 2023 |
| Dell          | Latitude E7240              | [6eae9dc932](https://linux-hardware.org/?probe=6eae9dc932) | Jan 05, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [7acb37a2f5](https://linux-hardware.org/?probe=7acb37a2f5) | Jan 05, 2023 |
| HP            | ZBook Power 15.6 inch G8... | [28eb8d09fa](https://linux-hardware.org/?probe=28eb8d09fa) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | [4f54cd1f61](https://linux-hardware.org/?probe=4f54cd1f61) | Jan 05, 2023 |
| Acer          | Aspire 7745G                | [0393900e99](https://linux-hardware.org/?probe=0393900e99) | Jan 05, 2023 |
| System76      | Gazelle                     | [b603d1ecc7](https://linux-hardware.org/?probe=b603d1ecc7) | Jan 04, 2023 |
| HP            | EliteBook 840 G3            | [8f42c7bc8c](https://linux-hardware.org/?probe=8f42c7bc8c) | Jan 04, 2023 |
| Datto         | Unknown                     | [e8c9c2e91f](https://linux-hardware.org/?probe=e8c9c2e91f) | Jan 04, 2023 |
| Dell          | XPS 13 9300                 | [7b1ce41c16](https://linux-hardware.org/?probe=7b1ce41c16) | Jan 03, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [f6d1d35842](https://linux-hardware.org/?probe=f6d1d35842) | Jan 02, 2023 |
| Panasonic     | FZ55-1                      | [b09d64c936](https://linux-hardware.org/?probe=b09d64c936) | Jan 02, 2023 |
| Fujitsu       | FMVNS6C3                    | [49d8591166](https://linux-hardware.org/?probe=49d8591166) | Jan 02, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [1490ccc480](https://linux-hardware.org/?probe=1490ccc480) | Jan 02, 2023 |
| Dell          | Latitude E7240              | [ccf48432e0](https://linux-hardware.org/?probe=ccf48432e0) | Jan 02, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | [5e52308407](https://linux-hardware.org/?probe=5e52308407) | Jan 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [d841c27fe1](https://linux-hardware.org/?probe=d841c27fe1) | Jan 02, 2023 |
| ASUSTek       | UX310UQK                    | [79baf6f82a](https://linux-hardware.org/?probe=79baf6f82a) | Jan 01, 2023 |
| Dell          | Latitude E7270              | [09f72d101d](https://linux-hardware.org/?probe=09f72d101d) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [28342f1b5c](https://linux-hardware.org/?probe=28342f1b5c) | Jan 01, 2023 |
| HP            | ZBook 15 G3                 | [a53517f382](https://linux-hardware.org/?probe=a53517f382) | Jan 01, 2023 |
| Dell          | XPS 9320                    | [4ef3eb6975](https://linux-hardware.org/?probe=4ef3eb6975) | Jan 01, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [9f2441851f](https://linux-hardware.org/?probe=9f2441851f) | Dec 31, 2022 |
| HP            | EliteBook 8740w (WH274UT... | [e42d4e66a0](https://linux-hardware.org/?probe=e42d4e66a0) | Dec 31, 2022 |
| MSI           | GE60 2OC\2OE                | [c307379c36](https://linux-hardware.org/?probe=c307379c36) | Dec 30, 2022 |
| Dell          | G3 3500                     | [6be65a4ee5](https://linux-hardware.org/?probe=6be65a4ee5) | Dec 30, 2022 |
| Lenovo        | Z50-70 20354                | [29984f68c6](https://linux-hardware.org/?probe=29984f68c6) | Dec 30, 2022 |
| Apple         | MacBookPro7,1               | [db4379ed1e](https://linux-hardware.org/?probe=db4379ed1e) | Dec 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [3f1ca6740d](https://linux-hardware.org/?probe=3f1ca6740d) | Dec 30, 2022 |
| Dell          | Latitude E7240              | [5f83c8f4ad](https://linux-hardware.org/?probe=5f83c8f4ad) | Dec 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [d048930c78](https://linux-hardware.org/?probe=d048930c78) | Dec 30, 2022 |
| Dell          | G5 5590                     | [dada63bf04](https://linux-hardware.org/?probe=dada63bf04) | Dec 30, 2022 |
| HP            | Pavilion 15                 | [956866bbdd](https://linux-hardware.org/?probe=956866bbdd) | Dec 29, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [aa2aad674b](https://linux-hardware.org/?probe=aa2aad674b) | Dec 29, 2022 |
| Lenovo        | ThinkPad W510 4389W14       | [c83a9ac8a9](https://linux-hardware.org/?probe=c83a9ac8a9) | Dec 29, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [467a749806](https://linux-hardware.org/?probe=467a749806) | Dec 29, 2022 |
| System76      | Lemur Pro                   | [0a61e4fe8d](https://linux-hardware.org/?probe=0a61e4fe8d) | Dec 29, 2022 |
| HP            | ENVY dv7                    | [97e029af78](https://linux-hardware.org/?probe=97e029af78) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [2bd4899c8a](https://linux-hardware.org/?probe=2bd4899c8a) | Dec 29, 2022 |
| Apple         | MacBookPro14,1              | [919cfc2c9c](https://linux-hardware.org/?probe=919cfc2c9c) | Dec 29, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [f2ea0a18c8](https://linux-hardware.org/?probe=f2ea0a18c8) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2e62e57e1c](https://linux-hardware.org/?probe=2e62e57e1c) | Dec 28, 2022 |
| ASUSTek       | P453UA                      | [0bf89f0f8f](https://linux-hardware.org/?probe=0bf89f0f8f) | Dec 28, 2022 |
| Lenovo        | Y50-70 20378                | [fe7926d39a](https://linux-hardware.org/?probe=fe7926d39a) | Dec 28, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [c844147ffd](https://linux-hardware.org/?probe=c844147ffd) | Dec 28, 2022 |
| Alienware     | M11x R2                     | [a0da72bec0](https://linux-hardware.org/?probe=a0da72bec0) | Dec 28, 2022 |
| Dell          | Inspiron 5505               | [ba2d75cfa7](https://linux-hardware.org/?probe=ba2d75cfa7) | Dec 28, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [9cc79e51c0](https://linux-hardware.org/?probe=9cc79e51c0) | Dec 28, 2022 |
| HUAWEI        | HVY-WXX9                    | [069f0917d6](https://linux-hardware.org/?probe=069f0917d6) | Dec 28, 2022 |
| Apple         | MacBookPro8,2               | [e4255e8ed7](https://linux-hardware.org/?probe=e4255e8ed7) | Dec 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [6a2f859c67](https://linux-hardware.org/?probe=6a2f859c67) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [470c8d54ba](https://linux-hardware.org/?probe=470c8d54ba) | Dec 27, 2022 |
| Apple         | MacBookPro8,2               | [c62b37d15c](https://linux-hardware.org/?probe=c62b37d15c) | Dec 27, 2022 |
| Acer          | Aspire A515-57              | [c0a659dbb1](https://linux-hardware.org/?probe=c0a659dbb1) | Dec 27, 2022 |
| Dell          | XPS 15 9500                 | [d1d8257c05](https://linux-hardware.org/?probe=d1d8257c05) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| HP            | Pavilion dv6                | [d759125511](https://linux-hardware.org/?probe=d759125511) | Dec 26, 2022 |
| Acer          | Swift SF314-511             | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| Apple         | MacBookPro14,1              | [eb6c6ee49e](https://linux-hardware.org/?probe=eb6c6ee49e) | Dec 26, 2022 |
| ASUSTek       | N550JV                      | [748284a21e](https://linux-hardware.org/?probe=748284a21e) | Dec 26, 2022 |
| Dell          | XPS 13 9360                 | [bddcc1503f](https://linux-hardware.org/?probe=bddcc1503f) | Dec 26, 2022 |
| Acer          | Aspire A114-32              | [593969da1f](https://linux-hardware.org/?probe=593969da1f) | Dec 26, 2022 |
| Avell High... | C62 MOB                     | [658f34e70d](https://linux-hardware.org/?probe=658f34e70d) | Dec 26, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [46687a6be3](https://linux-hardware.org/?probe=46687a6be3) | Dec 26, 2022 |
| Sony          | VGN-FW21E                   | [e5eb6c865f](https://linux-hardware.org/?probe=e5eb6c865f) | Dec 25, 2022 |
| GPD           | G1621-02                    | [10a7e912f8](https://linux-hardware.org/?probe=10a7e912f8) | Dec 25, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [576fb3852f](https://linux-hardware.org/?probe=576fb3852f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| HP            | 255 G8 Notebook PC          | [3f72d88324](https://linux-hardware.org/?probe=3f72d88324) | Dec 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [de111c3be5](https://linux-hardware.org/?probe=de111c3be5) | Dec 24, 2022 |
| HP            | EliteBook 865 16 inch G9... | [857cb922f9](https://linux-hardware.org/?probe=857cb922f9) | Dec 24, 2022 |
| Dell          | Latitude E7470              | [8e6bdc1809](https://linux-hardware.org/?probe=8e6bdc1809) | Dec 24, 2022 |
| System76      | Pangolin                    | [2ee273cbcf](https://linux-hardware.org/?probe=2ee273cbcf) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [214b2a3235](https://linux-hardware.org/?probe=214b2a3235) | Dec 23, 2022 |
| HP            | Laptop 14s-dk0xxx           | [53aa474cf5](https://linux-hardware.org/?probe=53aa474cf5) | Dec 23, 2022 |
| Timi          | TM1703                      | [5e25655f36](https://linux-hardware.org/?probe=5e25655f36) | Dec 23, 2022 |
| Toshiba       | Satellite Pro C50-A-1MX     | [78487975ce](https://linux-hardware.org/?probe=78487975ce) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [918223cece](https://linux-hardware.org/?probe=918223cece) | Dec 23, 2022 |
| Medion        | X6816                       | [bafbf1ea90](https://linux-hardware.org/?probe=bafbf1ea90) | Dec 23, 2022 |
| Medion        | X6816                       | [ac9627e5d4](https://linux-hardware.org/?probe=ac9627e5d4) | Dec 23, 2022 |
| Dell          | Latitude E7240              | [7bd2309063](https://linux-hardware.org/?probe=7bd2309063) | Dec 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d7b8ef01e2](https://linux-hardware.org/?probe=d7b8ef01e2) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [db7dc4fa25](https://linux-hardware.org/?probe=db7dc4fa25) | Dec 22, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [e8ac233c29](https://linux-hardware.org/?probe=e8ac233c29) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [341becfd8a](https://linux-hardware.org/?probe=341becfd8a) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [ad4be7f0fa](https://linux-hardware.org/?probe=ad4be7f0fa) | Dec 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [a70ba97a7a](https://linux-hardware.org/?probe=a70ba97a7a) | Dec 22, 2022 |
| ASUSTek       | K53SJ                       | [e60df2d8ba](https://linux-hardware.org/?probe=e60df2d8ba) | Dec 22, 2022 |
| Acer          | Swift SF314-512             | [505ab3f60a](https://linux-hardware.org/?probe=505ab3f60a) | Dec 22, 2022 |
| Dell          | Latitude E7240              | [d81efafde1](https://linux-hardware.org/?probe=d81efafde1) | Dec 22, 2022 |
| System76      | Lemur Pro                   | [ed549bfe74](https://linux-hardware.org/?probe=ed549bfe74) | Dec 21, 2022 |
| System76      | Lemur Pro                   | [30be17e71c](https://linux-hardware.org/?probe=30be17e71c) | Dec 21, 2022 |
| Dell          | Precision 3520              | [1763494294](https://linux-hardware.org/?probe=1763494294) | Dec 21, 2022 |
| ASUSTek       | Strix 15 GL503GE            | [0377cc3170](https://linux-hardware.org/?probe=0377cc3170) | Dec 21, 2022 |
| Dell          | Latitude E7240              | [545294a23a](https://linux-hardware.org/?probe=545294a23a) | Dec 21, 2022 |
| Apple         | MacBookPro12,1              | [debd2eb829](https://linux-hardware.org/?probe=debd2eb829) | Dec 21, 2022 |
| Dell          | Inspiron 5515               | [b0df20f3d1](https://linux-hardware.org/?probe=b0df20f3d1) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7d5914dcb2](https://linux-hardware.org/?probe=7d5914dcb2) | Dec 21, 2022 |
| Dell          | Latitude E7240              | [a368a7be00](https://linux-hardware.org/?probe=a368a7be00) | Dec 21, 2022 |
| ASUSTek       | VivoBook S14 X411UF         | [894f0ab5df](https://linux-hardware.org/?probe=894f0ab5df) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | [d5a877b2c6](https://linux-hardware.org/?probe=d5a877b2c6) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [b7999f8a61](https://linux-hardware.org/?probe=b7999f8a61) | Dec 20, 2022 |
| Acer          | Aspire A315-23G             | [04b9163920](https://linux-hardware.org/?probe=04b9163920) | Dec 19, 2022 |
| Lenovo        | IdeaPad Z410 20292          | [e46710b0cf](https://linux-hardware.org/?probe=e46710b0cf) | Dec 19, 2022 |
| Dell          | Inspiron 7572               | [418178c3ca](https://linux-hardware.org/?probe=418178c3ca) | Dec 19, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1QX0... | [76771fa0aa](https://linux-hardware.org/?probe=76771fa0aa) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | [b34ce3474d](https://linux-hardware.org/?probe=b34ce3474d) | Dec 19, 2022 |
| System76      | Gazelle                     | [da46fb926a](https://linux-hardware.org/?probe=da46fb926a) | Dec 19, 2022 |
| Dell          | Inspiron 15-3567            | [f58039213b](https://linux-hardware.org/?probe=f58039213b) | Dec 18, 2022 |
| GPU Compan... | GWNR71517                   | [e680612eb4](https://linux-hardware.org/?probe=e680612eb4) | Dec 18, 2022 |
| Lenovo        | ThinkPad Edge E430 62718... | [92fede3d5a](https://linux-hardware.org/?probe=92fede3d5a) | Dec 18, 2022 |
| Avell High... | B.ON                        | [9661ece374](https://linux-hardware.org/?probe=9661ece374) | Dec 17, 2022 |
| Dell          | XPS 15 9510                 | [1641d91910](https://linux-hardware.org/?probe=1641d91910) | Dec 17, 2022 |
| Dell          | Inspiron 5458               | [8ed4687f2f](https://linux-hardware.org/?probe=8ed4687f2f) | Dec 16, 2022 |
| System76      | Gazelle                     | [b5ef8cec53](https://linux-hardware.org/?probe=b5ef8cec53) | Dec 16, 2022 |
| Acer          | Aspire V5-571G              | [575a61802b](https://linux-hardware.org/?probe=575a61802b) | Dec 16, 2022 |
| Dell          | Latitude 3310               | [4066d1434e](https://linux-hardware.org/?probe=4066d1434e) | Dec 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [544e464dab](https://linux-hardware.org/?probe=544e464dab) | Dec 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [18d67ba2ab](https://linux-hardware.org/?probe=18d67ba2ab) | Dec 15, 2022 |
| ALLDOCUBE     | i1405C                      | [10d8101488](https://linux-hardware.org/?probe=10d8101488) | Dec 15, 2022 |
| Fujitsu       | FMVNS6C3                    | [d7a6961431](https://linux-hardware.org/?probe=d7a6961431) | Dec 15, 2022 |
| Apple         | MacBookPro10,1              | [a22dd35e04](https://linux-hardware.org/?probe=a22dd35e04) | Dec 14, 2022 |
| Apple         | MacBookPro11,3              | [d0c2bf600a](https://linux-hardware.org/?probe=d0c2bf600a) | Dec 14, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [d623f983cd](https://linux-hardware.org/?probe=d623f983cd) | Dec 13, 2022 |
| Lenovo        | G505 20240                  | [e6777c2fbc](https://linux-hardware.org/?probe=e6777c2fbc) | Dec 13, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [b08795ce45](https://linux-hardware.org/?probe=b08795ce45) | Dec 13, 2022 |
| Lenovo        | ThinkPad T530 23943J8       | [e5d69d9f81](https://linux-hardware.org/?probe=e5d69d9f81) | Dec 13, 2022 |
| Apple         | MacBookPro9,2               | [2981da7231](https://linux-hardware.org/?probe=2981da7231) | Dec 12, 2022 |
| MSI           | Summit E16Flip A12UCT       | [1db3976bb5](https://linux-hardware.org/?probe=1db3976bb5) | Dec 12, 2022 |
| Toshiba       | Satellite C55-C             | [777b365c04](https://linux-hardware.org/?probe=777b365c04) | Dec 12, 2022 |
| System76      | Gazelle                     | [8498636db6](https://linux-hardware.org/?probe=8498636db6) | Dec 12, 2022 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [d438f3f50a](https://linux-hardware.org/?probe=d438f3f50a) | Dec 12, 2022 |
| Apple         | MacBookPro13,3              | [10b29f88c5](https://linux-hardware.org/?probe=10b29f88c5) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| ASUSTek       | K56CB                       | [94b056f1f4](https://linux-hardware.org/?probe=94b056f1f4) | Dec 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E4C... | [7ffd00681b](https://linux-hardware.org/?probe=7ffd00681b) | Dec 12, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6de2a0ad33](https://linux-hardware.org/?probe=6de2a0ad33) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [4b0492b053](https://linux-hardware.org/?probe=4b0492b053) | Dec 11, 2022 |
| Dell          | Latitude E7240              | [d6dddd9632](https://linux-hardware.org/?probe=d6dddd9632) | Dec 11, 2022 |
| Acer          | Aspire A515-44G             | [b85a211b25](https://linux-hardware.org/?probe=b85a211b25) | Dec 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [ca7d835a38](https://linux-hardware.org/?probe=ca7d835a38) | Dec 11, 2022 |
| System76      | Gazelle                     | [8b0297b19e](https://linux-hardware.org/?probe=8b0297b19e) | Dec 11, 2022 |
| Lenovo        | G470 20078                  | [65264ef208](https://linux-hardware.org/?probe=65264ef208) | Dec 11, 2022 |
| Fujitsu       | FMVNS6C3                    | [2cdacbc923](https://linux-hardware.org/?probe=2cdacbc923) | Dec 11, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [040652df3d](https://linux-hardware.org/?probe=040652df3d) | Dec 10, 2022 |
| Lenovo        | G470 20078                  | [ea75ebf831](https://linux-hardware.org/?probe=ea75ebf831) | Dec 09, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2dc32e31b3](https://linux-hardware.org/?probe=2dc32e31b3) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [e8fe4392be](https://linux-hardware.org/?probe=e8fe4392be) | Dec 09, 2022 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | [cf32d7158c](https://linux-hardware.org/?probe=cf32d7158c) | Dec 09, 2022 |
| GPU Compan... | GWNR71517                   | [ef20df1d4f](https://linux-hardware.org/?probe=ef20df1d4f) | Dec 09, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [8ce314db56](https://linux-hardware.org/?probe=8ce314db56) | Dec 08, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [858f06f0e5](https://linux-hardware.org/?probe=858f06f0e5) | Dec 08, 2022 |
| Acer          | TravelMate P214-41-G2       | [cb52e49fa2](https://linux-hardware.org/?probe=cb52e49fa2) | Dec 08, 2022 |
| Dell          | G15 5515                    | [861bd0cabf](https://linux-hardware.org/?probe=861bd0cabf) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [ca25d43c56](https://linux-hardware.org/?probe=ca25d43c56) | Dec 08, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [104e0e02d1](https://linux-hardware.org/?probe=104e0e02d1) | Dec 08, 2022 |
| LG Electro... | 16Z90P-K.AA78A1             | [1646f1763d](https://linux-hardware.org/?probe=1646f1763d) | Dec 08, 2022 |
| Avell High... | A62 LIV                     | [a4f96694c4](https://linux-hardware.org/?probe=a4f96694c4) | Dec 07, 2022 |
| Acer          | Aspire A515-45              | [7eebb7f601](https://linux-hardware.org/?probe=7eebb7f601) | Dec 07, 2022 |
| Dell          | Latitude E7240              | [632cda6ecd](https://linux-hardware.org/?probe=632cda6ecd) | Dec 07, 2022 |
| HP            | ENVY 17                     | [a19d90a89f](https://linux-hardware.org/?probe=a19d90a89f) | Dec 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b5f311cc8f](https://linux-hardware.org/?probe=b5f311cc8f) | Dec 07, 2022 |
| Dell          | Inspiron 1750               | [e369c14198](https://linux-hardware.org/?probe=e369c14198) | Dec 07, 2022 |
| Lenovo        | IdeaPad Y560                | [64abd8c6fe](https://linux-hardware.org/?probe=64abd8c6fe) | Dec 06, 2022 |
| Fujitsu       | FMVNS6C3                    | [5b60c9dfd0](https://linux-hardware.org/?probe=5b60c9dfd0) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [05f4b7d7cf](https://linux-hardware.org/?probe=05f4b7d7cf) | Dec 06, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [86cd634760](https://linux-hardware.org/?probe=86cd634760) | Dec 06, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1200... | [6f0ceb7a46](https://linux-hardware.org/?probe=6f0ceb7a46) | Dec 05, 2022 |
| Dell          | G5 5505                     | [f19a76c344](https://linux-hardware.org/?probe=f19a76c344) | Dec 05, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [1798adf382](https://linux-hardware.org/?probe=1798adf382) | Dec 05, 2022 |
| ASUSTek       | UL50VT                      | [ff4edb7010](https://linux-hardware.org/?probe=ff4edb7010) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [f602f6c0bc](https://linux-hardware.org/?probe=f602f6c0bc) | Dec 05, 2022 |
| HP            | ProBook 6450b               | [de39c86a4c](https://linux-hardware.org/?probe=de39c86a4c) | Dec 05, 2022 |
| System76      | Gazelle                     | [deb2c9b6c9](https://linux-hardware.org/?probe=deb2c9b6c9) | Dec 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [7687bdc111](https://linux-hardware.org/?probe=7687bdc111) | Dec 04, 2022 |
| Acer          | Nitro AN515-54              | [33f26cca4f](https://linux-hardware.org/?probe=33f26cca4f) | Dec 04, 2022 |
| HP            | Notebook                    | [610cea9ebc](https://linux-hardware.org/?probe=610cea9ebc) | Dec 04, 2022 |
| Dell          | Latitude E7240              | [6f34110d45](https://linux-hardware.org/?probe=6f34110d45) | Dec 04, 2022 |
| Unknown       | Unknown                     | [54c6593c53](https://linux-hardware.org/?probe=54c6593c53) | Dec 03, 2022 |
| Unknown       | Unknown                     | [7668b4d9a2](https://linux-hardware.org/?probe=7668b4d9a2) | Dec 03, 2022 |
| HP            | EliteBook 820 G3            | [6913ec89c8](https://linux-hardware.org/?probe=6913ec89c8) | Dec 03, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4f36906529](https://linux-hardware.org/?probe=4f36906529) | Dec 02, 2022 |
| HP            | ProBook 450 G7 HP NOTEBO... | [2fe5c76c3c](https://linux-hardware.org/?probe=2fe5c76c3c) | Dec 02, 2022 |
| HP            | Notebook                    | [4184c8fa06](https://linux-hardware.org/?probe=4184c8fa06) | Dec 02, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [9c5bc7ca10](https://linux-hardware.org/?probe=9c5bc7ca10) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [562e1f4b92](https://linux-hardware.org/?probe=562e1f4b92) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c8ef49d294](https://linux-hardware.org/?probe=c8ef49d294) | Dec 01, 2022 |
| HP            | Pavilion dv7                | [aa6cdce8f8](https://linux-hardware.org/?probe=aa6cdce8f8) | Dec 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [62ae8cb7dc](https://linux-hardware.org/?probe=62ae8cb7dc) | Dec 01, 2022 |
| Dell          | Inspiron 13-5378            | [9d25b2f6e0](https://linux-hardware.org/?probe=9d25b2f6e0) | Dec 01, 2022 |
| Dell          | XPS 13 9310                 | [aadf1c39a0](https://linux-hardware.org/?probe=aadf1c39a0) | Dec 01, 2022 |
| Google        | Cyan                        | [4aa7125981](https://linux-hardware.org/?probe=4aa7125981) | Nov 30, 2022 |
| HP            | ZBook 14 G2                 | [b2bba919b2](https://linux-hardware.org/?probe=b2bba919b2) | Nov 30, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [66b6e49eb5](https://linux-hardware.org/?probe=66b6e49eb5) | Nov 30, 2022 |
| Acer          | Nitro AN515-43              | [b315e85bda](https://linux-hardware.org/?probe=b315e85bda) | Nov 30, 2022 |
| MSI           | Modern 14 B5M               | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| Lenovo        | IdeaPad S145-15API 81V7     | [53ee9a8fb9](https://linux-hardware.org/?probe=53ee9a8fb9) | Nov 30, 2022 |
| HP            | Laptop 14-dq1xxx            | [b12534f13d](https://linux-hardware.org/?probe=b12534f13d) | Nov 30, 2022 |
| Dell          | Latitude E7240              | [8b0b984870](https://linux-hardware.org/?probe=8b0b984870) | Nov 29, 2022 |
| HP            | ProBook 450 G8              | [eec30c7857](https://linux-hardware.org/?probe=eec30c7857) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [e9932df850](https://linux-hardware.org/?probe=e9932df850) | Nov 29, 2022 |
| HUAWEI        | NBD-WXX9                    | [179ff76e75](https://linux-hardware.org/?probe=179ff76e75) | Nov 29, 2022 |
| HP            | Pavilion dv7                | [1ba2fdd19b](https://linux-hardware.org/?probe=1ba2fdd19b) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [bb417133ee](https://linux-hardware.org/?probe=bb417133ee) | Nov 29, 2022 |
| HP            | Compaq nc6320 (GB940ES#A... | [ddb2f42bcc](https://linux-hardware.org/?probe=ddb2f42bcc) | Nov 29, 2022 |
| Dell          | Latitude 5411               | [122facad78](https://linux-hardware.org/?probe=122facad78) | Nov 28, 2022 |
| HP            | Pavilion dv7                | [db7897d2fc](https://linux-hardware.org/?probe=db7897d2fc) | Nov 28, 2022 |
| Apple         | MacBookPro10,1              | [c0c2f77cdb](https://linux-hardware.org/?probe=c0c2f77cdb) | Nov 28, 2022 |
| Lenovo        | IdeaPad Y560                | [4918810cd1](https://linux-hardware.org/?probe=4918810cd1) | Nov 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [16705fe86c](https://linux-hardware.org/?probe=16705fe86c) | Nov 28, 2022 |
| Dell          | Inspiron 15 5510            | [5ec5306c0f](https://linux-hardware.org/?probe=5ec5306c0f) | Nov 28, 2022 |
| Clevo         | W55xEU                      | [5ed799ba64](https://linux-hardware.org/?probe=5ed799ba64) | Nov 28, 2022 |
| MSI           | GP72 7RDX                   | [648eb6d88a](https://linux-hardware.org/?probe=648eb6d88a) | Nov 28, 2022 |
| Acer          | Aspire A515-57              | [984e01118e](https://linux-hardware.org/?probe=984e01118e) | Nov 28, 2022 |
| HP            | Laptop 14-fq1xxx            | [7837242848](https://linux-hardware.org/?probe=7837242848) | Nov 27, 2022 |
| Toshiba       | Satellite L775D             | [bf6fc6fd49](https://linux-hardware.org/?probe=bf6fc6fd49) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [f3536b80de](https://linux-hardware.org/?probe=f3536b80de) | Nov 27, 2022 |
| Dell          | Latitude E6230              | [dbaae2beb7](https://linux-hardware.org/?probe=dbaae2beb7) | Nov 27, 2022 |
| Apple         | MacBookPro6,2               | [409c3edc19](https://linux-hardware.org/?probe=409c3edc19) | Nov 27, 2022 |
| Alienware     | 17                          | [08ebf1e9a2](https://linux-hardware.org/?probe=08ebf1e9a2) | Nov 27, 2022 |
| HP            | Laptop 14-fq1xxx            | [49dc64dc76](https://linux-hardware.org/?probe=49dc64dc76) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [935c9528be](https://linux-hardware.org/?probe=935c9528be) | Nov 26, 2022 |
| Dell          | Inspiron 3521               | [015854e59a](https://linux-hardware.org/?probe=015854e59a) | Nov 26, 2022 |
| HP            | ZBook 15                    | [2ff5969ae6](https://linux-hardware.org/?probe=2ff5969ae6) | Nov 26, 2022 |
| HP            | ZBook 15                    | [55e4fb5ba0](https://linux-hardware.org/?probe=55e4fb5ba0) | Nov 26, 2022 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [e784cdc15d](https://linux-hardware.org/?probe=e784cdc15d) | Nov 26, 2022 |
| Gigabyte      | AORUS 5 SE                  | [d9e1ceb3c1](https://linux-hardware.org/?probe=d9e1ceb3c1) | Nov 26, 2022 |
| HUAWEI        | MRGF-XX                     | [f60090b407](https://linux-hardware.org/?probe=f60090b407) | Nov 26, 2022 |
| Apple         | MacBookPro7,1               | [8268fc2c12](https://linux-hardware.org/?probe=8268fc2c12) | Nov 26, 2022 |
| HP            | ProBook 450 G5              | [9a8373739a](https://linux-hardware.org/?probe=9a8373739a) | Nov 26, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [32ab0a36a4](https://linux-hardware.org/?probe=32ab0a36a4) | Nov 25, 2022 |
| Acer          | Aspire A315-54              | [b7269b7617](https://linux-hardware.org/?probe=b7269b7617) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [770e9d413e](https://linux-hardware.org/?probe=770e9d413e) | Nov 24, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f0bebe7a20](https://linux-hardware.org/?probe=f0bebe7a20) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ce5a80936d](https://linux-hardware.org/?probe=ce5a80936d) | Nov 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [dce6415c9e](https://linux-hardware.org/?probe=dce6415c9e) | Nov 23, 2022 |
| Lenovo        | IdeaPad Y560                | [154702cbc6](https://linux-hardware.org/?probe=154702cbc6) | Nov 23, 2022 |
| Dell          | XPS 15 7590                 | [2355853fda](https://linux-hardware.org/?probe=2355853fda) | Nov 23, 2022 |
| HP            | G62                         | [754a471519](https://linux-hardware.org/?probe=754a471519) | Nov 23, 2022 |
| ASUSTek       | Strix GL504GW_GL504GW       | [f06e160e11](https://linux-hardware.org/?probe=f06e160e11) | Nov 23, 2022 |
| Dell          | Latitude E7470              | [03725ebee3](https://linux-hardware.org/?probe=03725ebee3) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [4692ce22fb](https://linux-hardware.org/?probe=4692ce22fb) | Nov 22, 2022 |
| Acer          | Aspire A515-57              | [cb82f6d418](https://linux-hardware.org/?probe=cb82f6d418) | Nov 22, 2022 |
| Dell          | Latitude E6540              | [9a3ff03cbb](https://linux-hardware.org/?probe=9a3ff03cbb) | Nov 22, 2022 |
| Gigabyte      | AORUS 5 SE                  | [c88614e7f3](https://linux-hardware.org/?probe=c88614e7f3) | Nov 22, 2022 |
| MSI           | Katana GF76 11UG            | [e29dda268c](https://linux-hardware.org/?probe=e29dda268c) | Nov 21, 2022 |
| MSI           | Katana GF76 11UG            | [9627a23b1f](https://linux-hardware.org/?probe=9627a23b1f) | Nov 21, 2022 |
| Acer          | Aspire A515-45              | [b0b972f8ef](https://linux-hardware.org/?probe=b0b972f8ef) | Nov 21, 2022 |
| Dell          | Precision 7670              | [93f14c8b55](https://linux-hardware.org/?probe=93f14c8b55) | Nov 21, 2022 |
| Alienware     | 17                          | [16b37ce649](https://linux-hardware.org/?probe=16b37ce649) | Nov 21, 2022 |
| Acer          | Swift SF314-42              | [5ec428f8b3](https://linux-hardware.org/?probe=5ec428f8b3) | Nov 21, 2022 |
| Unknown       | Unknown                     | [5a06cde126](https://linux-hardware.org/?probe=5a06cde126) | Nov 20, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | [6355251bd6](https://linux-hardware.org/?probe=6355251bd6) | Nov 20, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [18f301f8c5](https://linux-hardware.org/?probe=18f301f8c5) | Nov 20, 2022 |
| Dell          | Vostro 3458                 | [9f05e54f99](https://linux-hardware.org/?probe=9f05e54f99) | Nov 20, 2022 |
| Lenovo        | Legion 5 15ARH7H 82RD       | [cba7abe277](https://linux-hardware.org/?probe=cba7abe277) | Nov 20, 2022 |
| Lenovo        | ThinkPad E490 20N8000RUK    | [6eb57e34de](https://linux-hardware.org/?probe=6eb57e34de) | Nov 20, 2022 |
| Apple         | MacBookPro11,2              | [03447c1967](https://linux-hardware.org/?probe=03447c1967) | Nov 20, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [d4bb2f3867](https://linux-hardware.org/?probe=d4bb2f3867) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [37145c9282](https://linux-hardware.org/?probe=37145c9282) | Nov 19, 2022 |
| HP            | ProBook 6450b               | [10c8ec5d4c](https://linux-hardware.org/?probe=10c8ec5d4c) | Nov 19, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [41ffb4e75f](https://linux-hardware.org/?probe=41ffb4e75f) | Nov 19, 2022 |
| Dell          | XPS 13 9360                 | [250885e79f](https://linux-hardware.org/?probe=250885e79f) | Nov 19, 2022 |
| Valve         | Jupiter                     | [afdcde154a](https://linux-hardware.org/?probe=afdcde154a) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [ceac47decc](https://linux-hardware.org/?probe=ceac47decc) | Nov 18, 2022 |
| HP            | ProBook 450 G6              | [5abeec1752](https://linux-hardware.org/?probe=5abeec1752) | Nov 18, 2022 |
| Dell          | Precision M4400             | [715efc61ae](https://linux-hardware.org/?probe=715efc61ae) | Nov 18, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [95b46d1513](https://linux-hardware.org/?probe=95b46d1513) | Nov 18, 2022 |
| Lenovo        | ThinkPad T480 20L50004UK    | [8f4df3bbda](https://linux-hardware.org/?probe=8f4df3bbda) | Nov 18, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | [dee1a4e29e](https://linux-hardware.org/?probe=dee1a4e29e) | Nov 17, 2022 |
| Lenovo        | ThinkPad T550 20CJS18S00    | [ba94994594](https://linux-hardware.org/?probe=ba94994594) | Nov 17, 2022 |
| Dell          | G15 5515                    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Toshiba       | Satellite L500              | [5579ea8656](https://linux-hardware.org/?probe=5579ea8656) | Nov 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [5c49c7037b](https://linux-hardware.org/?probe=5c49c7037b) | Nov 16, 2022 |
| Razer x La... | TensorBook (late 2021)      | [b7fff356a7](https://linux-hardware.org/?probe=b7fff356a7) | Nov 16, 2022 |
| HP            | ZBook 14 G2                 | [8ce9402aad](https://linux-hardware.org/?probe=8ce9402aad) | Nov 16, 2022 |
| Acer          | Aspire V3-575G              | [9044e30d53](https://linux-hardware.org/?probe=9044e30d53) | Nov 16, 2022 |
| Acer          | Aspire A114-32              | [5a76aee400](https://linux-hardware.org/?probe=5a76aee400) | Nov 16, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [1f2e05b205](https://linux-hardware.org/?probe=1f2e05b205) | Nov 15, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [809e86d562](https://linux-hardware.org/?probe=809e86d562) | Nov 15, 2022 |
| Acer          | Swift SF314-43              | [bc5218c5da](https://linux-hardware.org/?probe=bc5218c5da) | Nov 15, 2022 |
| OEGStone      | NOTCHA-322                  | [a5f28e095e](https://linux-hardware.org/?probe=a5f28e095e) | Nov 15, 2022 |
| System76      | Oryx Pro                    | [3ea0d459e1](https://linux-hardware.org/?probe=3ea0d459e1) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [426dec8739](https://linux-hardware.org/?probe=426dec8739) | Nov 15, 2022 |
| Lenovo        | ThinkPad T450 20BVA02TCD    | [f55f35c2fe](https://linux-hardware.org/?probe=f55f35c2fe) | Nov 15, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [31cf057099](https://linux-hardware.org/?probe=31cf057099) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [0d39dde901](https://linux-hardware.org/?probe=0d39dde901) | Nov 14, 2022 |
| Dell          | Inspiron 7560               | [45474958e5](https://linux-hardware.org/?probe=45474958e5) | Nov 14, 2022 |
| Dell          | Inspiron 15 3511            | [43214de971](https://linux-hardware.org/?probe=43214de971) | Nov 13, 2022 |
| Timi          | TM1613                      | [d038ff5636](https://linux-hardware.org/?probe=d038ff5636) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | [25b89592e0](https://linux-hardware.org/?probe=25b89592e0) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | [1e4f22395f](https://linux-hardware.org/?probe=1e4f22395f) | Nov 13, 2022 |
| GPU Compan... | GWTN141-10                  | [7325cce71f](https://linux-hardware.org/?probe=7325cce71f) | Nov 13, 2022 |
| MSI           | GL73 9SC                    | [86b0a359fa](https://linux-hardware.org/?probe=86b0a359fa) | Nov 13, 2022 |
| Apple         | MacBookPro10,1              | [d433817b4f](https://linux-hardware.org/?probe=d433817b4f) | Nov 13, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3e75f5aa87](https://linux-hardware.org/?probe=3e75f5aa87) | Nov 12, 2022 |
| Dell          | Latitude E7270              | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Apple         | MacBookAir6,2               | [c6b54c443e](https://linux-hardware.org/?probe=c6b54c443e) | Nov 12, 2022 |
| Google        | Shyvana                     | [2df69a0782](https://linux-hardware.org/?probe=2df69a0782) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [aec286073d](https://linux-hardware.org/?probe=aec286073d) | Nov 12, 2022 |
| Acer          | Aspire A114-32              | [3884507df6](https://linux-hardware.org/?probe=3884507df6) | Nov 11, 2022 |
| Dell          | Precision M4700             | [4fc304d429](https://linux-hardware.org/?probe=4fc304d429) | Nov 11, 2022 |
| HP            | EliteBook 840 G1            | [4ed347e186](https://linux-hardware.org/?probe=4ed347e186) | Nov 11, 2022 |
| System76      | Lemur Pro                   | [7df985e36a](https://linux-hardware.org/?probe=7df985e36a) | Nov 10, 2022 |
| Acer          | Aspire A114-32              | [a06fb78621](https://linux-hardware.org/?probe=a06fb78621) | Nov 10, 2022 |
| HP            | EliteBook 840 G5            | [e281a0277b](https://linux-hardware.org/?probe=e281a0277b) | Nov 10, 2022 |
| HP            | EliteBook 840 G3            | [6d00ba40be](https://linux-hardware.org/?probe=6d00ba40be) | Nov 10, 2022 |
| MSI           | MS-1688                     | [d8c76d2264](https://linux-hardware.org/?probe=d8c76d2264) | Nov 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [234729e8b5](https://linux-hardware.org/?probe=234729e8b5) | Nov 08, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [9979d8a6b6](https://linux-hardware.org/?probe=9979d8a6b6) | Nov 08, 2022 |
| Apple         | MacBookAir7,2               | [c4afe62f3b](https://linux-hardware.org/?probe=c4afe62f3b) | Nov 08, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [1918990398](https://linux-hardware.org/?probe=1918990398) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [44e88f2879](https://linux-hardware.org/?probe=44e88f2879) | Nov 07, 2022 |
| HP            | ENVY NOTEBOOK PC            | [ba3abf3883](https://linux-hardware.org/?probe=ba3abf3883) | Nov 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [61756efe8c](https://linux-hardware.org/?probe=61756efe8c) | Nov 07, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [ca4bb217ab](https://linux-hardware.org/?probe=ca4bb217ab) | Nov 07, 2022 |
| Dell          | Latitude E7240              | [2db569e056](https://linux-hardware.org/?probe=2db569e056) | Nov 06, 2022 |
| Dell          | Inspiron 1525               | [f28061e4da](https://linux-hardware.org/?probe=f28061e4da) | Nov 06, 2022 |
| Dell          | G7 7700                     | [ba3a89822a](https://linux-hardware.org/?probe=ba3a89822a) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [2a2464e0a3](https://linux-hardware.org/?probe=2a2464e0a3) | Nov 06, 2022 |
| Wortmann      | TERRA_MOBILE_1542           | [eded2f5469](https://linux-hardware.org/?probe=eded2f5469) | Nov 06, 2022 |
| Acer          | Swift SF314-42              | [c4c5bd2515](https://linux-hardware.org/?probe=c4c5bd2515) | Nov 06, 2022 |
| Lenovo        | IdeaPad S540-15IWL D 81N... | [1f4a1244b3](https://linux-hardware.org/?probe=1f4a1244b3) | Nov 06, 2022 |
| HP            | 15 Notebook PC              | [ba76e04444](https://linux-hardware.org/?probe=ba76e04444) | Nov 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [1cc6297ab8](https://linux-hardware.org/?probe=1cc6297ab8) | Nov 06, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [82048cfa4a](https://linux-hardware.org/?probe=82048cfa4a) | Nov 06, 2022 |
| Acer          | Aspire 5520                 | [6e6b76588b](https://linux-hardware.org/?probe=6e6b76588b) | Nov 06, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [d10e0ce942](https://linux-hardware.org/?probe=d10e0ce942) | Nov 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a26a719002](https://linux-hardware.org/?probe=a26a719002) | Nov 05, 2022 |
| HP            | ENVY NOTEBOOK PC            | [b0600fe299](https://linux-hardware.org/?probe=b0600fe299) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2eb5db395b](https://linux-hardware.org/?probe=2eb5db395b) | Nov 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f078009dc8](https://linux-hardware.org/?probe=f078009dc8) | Nov 05, 2022 |
| MSI           | Modern 14 B11SB             | [61543eb00f](https://linux-hardware.org/?probe=61543eb00f) | Nov 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5881bdde3a](https://linux-hardware.org/?probe=5881bdde3a) | Nov 04, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [58989ea140](https://linux-hardware.org/?probe=58989ea140) | Nov 04, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [578d48ac0c](https://linux-hardware.org/?probe=578d48ac0c) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | [17157970ee](https://linux-hardware.org/?probe=17157970ee) | Nov 04, 2022 |
| Toshiba       | Satellite L350              | [7479ad8a79](https://linux-hardware.org/?probe=7479ad8a79) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [0622b6fa8f](https://linux-hardware.org/?probe=0622b6fa8f) | Nov 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS16P00     | [bec7082d7a](https://linux-hardware.org/?probe=bec7082d7a) | Nov 04, 2022 |
| HUAWEI        | KLVL-WXX9                   | [de163caae3](https://linux-hardware.org/?probe=de163caae3) | Nov 04, 2022 |
| Apple         | MacBookPro10,1              | [fa19e49b0a](https://linux-hardware.org/?probe=fa19e49b0a) | Nov 04, 2022 |
| Dell          | Inspiron 3442               | [9fec26118c](https://linux-hardware.org/?probe=9fec26118c) | Nov 04, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [d63435720c](https://linux-hardware.org/?probe=d63435720c) | Nov 04, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2a... | [c868e47483](https://linux-hardware.org/?probe=c868e47483) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [f391e8dce8](https://linux-hardware.org/?probe=f391e8dce8) | Nov 03, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [a43927efff](https://linux-hardware.org/?probe=a43927efff) | Nov 03, 2022 |
| Dell          | Precision 14 5470           | [dab29b7f5b](https://linux-hardware.org/?probe=dab29b7f5b) | Nov 03, 2022 |
| Acer          | Aspire A114-32              | [2394d00673](https://linux-hardware.org/?probe=2394d00673) | Nov 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [39e7abb29a](https://linux-hardware.org/?probe=39e7abb29a) | Nov 03, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [d9de10d93e](https://linux-hardware.org/?probe=d9de10d93e) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | [036ff9e51f](https://linux-hardware.org/?probe=036ff9e51f) | Nov 02, 2022 |
| Acer          | Aspire A114-32              | [d5d1583252](https://linux-hardware.org/?probe=d5d1583252) | Nov 02, 2022 |
| Apple         | MacBookPro9,2               | [0f40b36846](https://linux-hardware.org/?probe=0f40b36846) | Nov 02, 2022 |
| PC Special... | Elimina Iv 15               | [f462ba9c43](https://linux-hardware.org/?probe=f462ba9c43) | Nov 02, 2022 |
| Fujitsu       | LIFEBOOK A532               | [d4af3b0745](https://linux-hardware.org/?probe=d4af3b0745) | Nov 01, 2022 |
| Intel Clie... | CMCN1CC                     | [719731b244](https://linux-hardware.org/?probe=719731b244) | Nov 01, 2022 |
| Dell          | Latitude E7240              | [effafc033d](https://linux-hardware.org/?probe=effafc033d) | Nov 01, 2022 |
| Apple         | MacBookPro12,1              | [e08326bc94](https://linux-hardware.org/?probe=e08326bc94) | Nov 01, 2022 |
| Dell          | G5 5587                     | [a4e32e9eb8](https://linux-hardware.org/?probe=a4e32e9eb8) | Nov 01, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81JM     | [da8fec7ac4](https://linux-hardware.org/?probe=da8fec7ac4) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6db184e152](https://linux-hardware.org/?probe=6db184e152) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [60cfb7dcc6](https://linux-hardware.org/?probe=60cfb7dcc6) | Nov 01, 2022 |
| Dell          | Latitude E7240              | [d8ae1a7195](https://linux-hardware.org/?probe=d8ae1a7195) | Nov 01, 2022 |
| Dell          | XPS 13 9310                 | [d284b1709a](https://linux-hardware.org/?probe=d284b1709a) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [325516bbce](https://linux-hardware.org/?probe=325516bbce) | Oct 31, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [740d19ba42](https://linux-hardware.org/?probe=740d19ba42) | Oct 31, 2022 |
| Lenovo        | ThinkPad T495 20NKS01Y00    | [c6a13e1ab3](https://linux-hardware.org/?probe=c6a13e1ab3) | Oct 31, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [b4fedd7c20](https://linux-hardware.org/?probe=b4fedd7c20) | Oct 31, 2022 |
| Dell          | Precision M6700             | [e5952f6f57](https://linux-hardware.org/?probe=e5952f6f57) | Oct 31, 2022 |
| HP            | ENVY NOTEBOOK PC            | [f2893aaedf](https://linux-hardware.org/?probe=f2893aaedf) | Oct 31, 2022 |
| Apple         | MacBookPro11,3              | [64d1c159aa](https://linux-hardware.org/?probe=64d1c159aa) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [424aaaf5bd](https://linux-hardware.org/?probe=424aaaf5bd) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| GPU Compan... | GWTN141-10                  | [189fca8ab3](https://linux-hardware.org/?probe=189fca8ab3) | Oct 30, 2022 |
| Tactus        | GeoBook 140                 | [71f32a229a](https://linux-hardware.org/?probe=71f32a229a) | Oct 30, 2022 |
| HP            | Pavilion dv7                | [6ff9a469f7](https://linux-hardware.org/?probe=6ff9a469f7) | Oct 30, 2022 |
| Apple         | MacBookPro3,1               | [27a5553057](https://linux-hardware.org/?probe=27a5553057) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [8f48ae7586](https://linux-hardware.org/?probe=8f48ae7586) | Oct 29, 2022 |
| MSI           | GE60 0NC\0ND                | [79bd38da8f](https://linux-hardware.org/?probe=79bd38da8f) | Oct 29, 2022 |
| Samsung       | 800G5M/800G5W               | [d688233d28](https://linux-hardware.org/?probe=d688233d28) | Oct 29, 2022 |
| MSI           | GF63 Thin 11UD              | [8f1f41f3b0](https://linux-hardware.org/?probe=8f1f41f3b0) | Oct 29, 2022 |
| Acer          | Aspire E5-571G              | [cc0f34a2fa](https://linux-hardware.org/?probe=cc0f34a2fa) | Oct 29, 2022 |
| MSI           | Prestige 15 A12UC           | [3d4c4364f1](https://linux-hardware.org/?probe=3d4c4364f1) | Oct 28, 2022 |
| Notebook      | NV4xPZ                      | [86e7370778](https://linux-hardware.org/?probe=86e7370778) | Oct 28, 2022 |
| HP            | Laptop 15s-eq2xxx           | [9dcb685f5e](https://linux-hardware.org/?probe=9dcb685f5e) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [df9ef8c115](https://linux-hardware.org/?probe=df9ef8c115) | Oct 28, 2022 |
| Apple         | MacBookPro5,3               | [4fa08c7d6f](https://linux-hardware.org/?probe=4fa08c7d6f) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3e6896ee0a](https://linux-hardware.org/?probe=3e6896ee0a) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [2fdc53f0f3](https://linux-hardware.org/?probe=2fdc53f0f3) | Oct 28, 2022 |
| Acer          | Aspire E5-575G              | [04d54cb9c8](https://linux-hardware.org/?probe=04d54cb9c8) | Oct 28, 2022 |
| Dell          | Precision 5530              | [bb4d35f452](https://linux-hardware.org/?probe=bb4d35f452) | Oct 28, 2022 |
| Dell          | XPS 15 9520                 | [d04e962e56](https://linux-hardware.org/?probe=d04e962e56) | Oct 28, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0957761dea](https://linux-hardware.org/?probe=0957761dea) | Oct 28, 2022 |
| Lenovo        | Legion Y540-15IRH 81RJ      | [a90eba59e8](https://linux-hardware.org/?probe=a90eba59e8) | Oct 28, 2022 |
| HP            | Laptop 15-db0xxx            | [b82aebb005](https://linux-hardware.org/?probe=b82aebb005) | Oct 28, 2022 |
| Samsung       | 950XDB/951XDB/950XDY        | [f27c4e1041](https://linux-hardware.org/?probe=f27c4e1041) | Oct 27, 2022 |
| System76      | Oryx Pro                    | [ff42b6e74a](https://linux-hardware.org/?probe=ff42b6e74a) | Oct 27, 2022 |
| Novatech      | NLx0MU                      | [41c5d984a0](https://linux-hardware.org/?probe=41c5d984a0) | Oct 27, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [e7db99be75](https://linux-hardware.org/?probe=e7db99be75) | Oct 27, 2022 |
| Apple         | MacBookAir6,2               | [cca0d420fe](https://linux-hardware.org/?probe=cca0d420fe) | Oct 27, 2022 |
| HP            | Laptop 15-dy2xxx            | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| MSI           | GF63 Thin 11UD              | [9f7121381b](https://linux-hardware.org/?probe=9f7121381b) | Oct 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ada4cec1b7](https://linux-hardware.org/?probe=ada4cec1b7) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [022cfe6707](https://linux-hardware.org/?probe=022cfe6707) | Oct 26, 2022 |
| Acer          | Aspire A515-52              | [81371581d1](https://linux-hardware.org/?probe=81371581d1) | Oct 26, 2022 |
| Gigabyte      | AERO 15 Classic-SA          | [7977a48aca](https://linux-hardware.org/?probe=7977a48aca) | Oct 26, 2022 |
| Dell          | XPS 15 9520                 | [1ede815931](https://linux-hardware.org/?probe=1ede815931) | Oct 26, 2022 |
| Acer          | Nitro AN515-58              | [9deeea3723](https://linux-hardware.org/?probe=9deeea3723) | Oct 26, 2022 |
| MSI           | GF63 Thin 11UD              | [2b6b8d3854](https://linux-hardware.org/?probe=2b6b8d3854) | Oct 26, 2022 |
| Apple         | MacBookAir7,2               | [892c5e2cda](https://linux-hardware.org/?probe=892c5e2cda) | Oct 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [b98bd6b361](https://linux-hardware.org/?probe=b98bd6b361) | Oct 26, 2022 |
| Lenovo        | ThinkPad X260 20F600A4MD    | [50cce404c7](https://linux-hardware.org/?probe=50cce404c7) | Oct 25, 2022 |
| Avell High... | A62 LIV                     | [673f411692](https://linux-hardware.org/?probe=673f411692) | Oct 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | [3375318388](https://linux-hardware.org/?probe=3375318388) | Oct 25, 2022 |
| Dell          | XPS 15 7590                 | [7f9028d036](https://linux-hardware.org/?probe=7f9028d036) | Oct 25, 2022 |
| Toshiba       | Satellite Pro S500          | [a26efdcfb5](https://linux-hardware.org/?probe=a26efdcfb5) | Oct 25, 2022 |
| HP            | ZBook 15                    | [b2d2352668](https://linux-hardware.org/?probe=b2d2352668) | Oct 25, 2022 |
| HP            | EliteBook 820 G2            | [b31fec75e1](https://linux-hardware.org/?probe=b31fec75e1) | Oct 25, 2022 |
| Dell          | G15 5511                    | [0f47c64bab](https://linux-hardware.org/?probe=0f47c64bab) | Oct 25, 2022 |
| Acer          | Nitro AN515-58              | [d03f6896eb](https://linux-hardware.org/?probe=d03f6896eb) | Oct 25, 2022 |
| Dell          | Latitude E7240              | [6966cfc71f](https://linux-hardware.org/?probe=6966cfc71f) | Oct 25, 2022 |
| MSI           | Prestige 14Evo A11M         | [7c4edd1a6d](https://linux-hardware.org/?probe=7c4edd1a6d) | Oct 24, 2022 |
| Dell          | XPS 15 9570                 | [d76c41ef1b](https://linux-hardware.org/?probe=d76c41ef1b) | Oct 24, 2022 |
| Dell          | Inspiron 16 7610            | [47a3e2b5f6](https://linux-hardware.org/?probe=47a3e2b5f6) | Oct 24, 2022 |
| HP            | Laptop 15s-fq0xxx           | [2510215a0b](https://linux-hardware.org/?probe=2510215a0b) | Oct 24, 2022 |
| Apple         | MacBookAir6,2               | [c271de3628](https://linux-hardware.org/?probe=c271de3628) | Oct 24, 2022 |
| System76      | Gazelle                     | [77686d0854](https://linux-hardware.org/?probe=77686d0854) | Oct 24, 2022 |
| HP            | Laptop 15s-gy0xxx           | [d1219c1387](https://linux-hardware.org/?probe=d1219c1387) | Oct 23, 2022 |
| Razer         | Blade 15 (2022) - RZ09-0... | [c70d6b90b6](https://linux-hardware.org/?probe=c70d6b90b6) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [bd25fa1073](https://linux-hardware.org/?probe=bd25fa1073) | Oct 23, 2022 |
| Apple         | MacBookAir6,2               | [edd13bcc76](https://linux-hardware.org/?probe=edd13bcc76) | Oct 23, 2022 |
| Apple         | MacBookPro10,1              | [9380dfc8b7](https://linux-hardware.org/?probe=9380dfc8b7) | Oct 23, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [4884be1a24](https://linux-hardware.org/?probe=4884be1a24) | Oct 22, 2022 |
| Dell          | Inspiron 3576               | [426ddc8fdb](https://linux-hardware.org/?probe=426ddc8fdb) | Oct 22, 2022 |
| Lenovo        | G50-30 80G0                 | [32a9b1de4f](https://linux-hardware.org/?probe=32a9b1de4f) | Oct 22, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [079a05485d](https://linux-hardware.org/?probe=079a05485d) | Oct 22, 2022 |
| System76      | Oryx Pro                    | [7de5d55c99](https://linux-hardware.org/?probe=7de5d55c99) | Oct 22, 2022 |
| Intel         | Montevina CRB               | [11cb344c52](https://linux-hardware.org/?probe=11cb344c52) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [ed692d6080](https://linux-hardware.org/?probe=ed692d6080) | Oct 21, 2022 |
| Razer x La... | TensorBook (late 2021)      | [27cae45787](https://linux-hardware.org/?probe=27cae45787) | Oct 20, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [504036a2f6](https://linux-hardware.org/?probe=504036a2f6) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [ddee1b5408](https://linux-hardware.org/?probe=ddee1b5408) | Oct 20, 2022 |
| System76      | Lemur Pro                   | [df61411c9d](https://linux-hardware.org/?probe=df61411c9d) | Oct 20, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c14937070e](https://linux-hardware.org/?probe=c14937070e) | Oct 19, 2022 |
| Dell          | Inspiron 3583               | [a8170f7786](https://linux-hardware.org/?probe=a8170f7786) | Oct 19, 2022 |
| MSI           | GF63 Thin 11UD              | [ca39605260](https://linux-hardware.org/?probe=ca39605260) | Oct 18, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [08327d561d](https://linux-hardware.org/?probe=08327d561d) | Oct 18, 2022 |
| Apple         | MacBookPro5,4               | [2a51555c53](https://linux-hardware.org/?probe=2a51555c53) | Oct 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [ed64a103f1](https://linux-hardware.org/?probe=ed64a103f1) | Oct 18, 2022 |
| HP            | Laptop 15-dy0xxx            | [2d1482e433](https://linux-hardware.org/?probe=2d1482e433) | Oct 18, 2022 |
| System76      | Lemur Pro                   | [53226822f5](https://linux-hardware.org/?probe=53226822f5) | Oct 18, 2022 |
| MSI           | GF63 Thin 11UD              | [d522208941](https://linux-hardware.org/?probe=d522208941) | Oct 17, 2022 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [40771441a2](https://linux-hardware.org/?probe=40771441a2) | Oct 17, 2022 |
| Lenovo        | Legion Y740-17IRH 81UG      | [67aec6ad33](https://linux-hardware.org/?probe=67aec6ad33) | Oct 17, 2022 |
| MSI           | GP72VR 7RF                  | [86a4902866](https://linux-hardware.org/?probe=86a4902866) | Oct 17, 2022 |
| Dell          | Latitude E6430s             | [ca202dddd6](https://linux-hardware.org/?probe=ca202dddd6) | Oct 17, 2022 |
| Acer          | Aspire E5-553G              | [bab2e8dad2](https://linux-hardware.org/?probe=bab2e8dad2) | Oct 17, 2022 |
| HP            | G62                         | [839b09744e](https://linux-hardware.org/?probe=839b09744e) | Oct 17, 2022 |
| Dell          | Vostro 15-3568              | [b7ea5640c2](https://linux-hardware.org/?probe=b7ea5640c2) | Oct 17, 2022 |
| HP            | ENVY 17                     | [ab25d54223](https://linux-hardware.org/?probe=ab25d54223) | Oct 16, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [502f19e8b3](https://linux-hardware.org/?probe=502f19e8b3) | Oct 16, 2022 |
| HP            | Pavilion g6                 | [2729d4b101](https://linux-hardware.org/?probe=2729d4b101) | Oct 14, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [2ba7e8c424](https://linux-hardware.org/?probe=2ba7e8c424) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [128cccafa6](https://linux-hardware.org/?probe=128cccafa6) | Oct 14, 2022 |
| HP            | Pavilion g6                 | [4fbce46637](https://linux-hardware.org/?probe=4fbce46637) | Oct 14, 2022 |
| System76      | Galago Pro                  | [ec92c5a918](https://linux-hardware.org/?probe=ec92c5a918) | Oct 14, 2022 |
| KELYX ARGE... | KL9120                      | [a14b57c22c](https://linux-hardware.org/?probe=a14b57c22c) | Oct 14, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [e2db064195](https://linux-hardware.org/?probe=e2db064195) | Oct 13, 2022 |
| Google        | Kefka                       | [4775b995dd](https://linux-hardware.org/?probe=4775b995dd) | Oct 13, 2022 |
| System76      | Lemur Pro                   | [ec569ddc8f](https://linux-hardware.org/?probe=ec569ddc8f) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | [3c11d61a58](https://linux-hardware.org/?probe=3c11d61a58) | Oct 13, 2022 |
| MSI           | Katana GF76 11UD            | [236e24530f](https://linux-hardware.org/?probe=236e24530f) | Oct 12, 2022 |
| Dell          | Precision M6700             | [4c867e9075](https://linux-hardware.org/?probe=4c867e9075) | Oct 12, 2022 |
| Acer          | Aspire 5740                 | [273721cef2](https://linux-hardware.org/?probe=273721cef2) | Oct 12, 2022 |
| Razer         | Blade                       | [c7386df23f](https://linux-hardware.org/?probe=c7386df23f) | Oct 12, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [2d102e0f1e](https://linux-hardware.org/?probe=2d102e0f1e) | Oct 12, 2022 |
| HP            | Pavilion 15                 | [8b93ec27f4](https://linux-hardware.org/?probe=8b93ec27f4) | Oct 12, 2022 |
| GPU Compan... | GWTN141-10                  | [1feb5d7501](https://linux-hardware.org/?probe=1feb5d7501) | Oct 12, 2022 |
| Alienware     | 15 R3                       | [bfdbf12cbb](https://linux-hardware.org/?probe=bfdbf12cbb) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | [93ca81946a](https://linux-hardware.org/?probe=93ca81946a) | Oct 11, 2022 |
| Acer          | Aspire A715-75G             | [921c4a26d1](https://linux-hardware.org/?probe=921c4a26d1) | Oct 11, 2022 |
| KELYX ARGE... | KL9120                      | [477851891a](https://linux-hardware.org/?probe=477851891a) | Oct 11, 2022 |
| MSI           | MS-7A34                     | [9850074c97](https://linux-hardware.org/?probe=9850074c97) | Oct 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [f4a46537c2](https://linux-hardware.org/?probe=f4a46537c2) | Oct 10, 2022 |
| Gigabyte      | P34V7                       | [c1423fce9e](https://linux-hardware.org/?probe=c1423fce9e) | Oct 10, 2022 |
| System76      | Galago Pro                  | [28e36afa26](https://linux-hardware.org/?probe=28e36afa26) | Oct 10, 2022 |
| Dell          | Latitude 5501               | [9051fd0e00](https://linux-hardware.org/?probe=9051fd0e00) | Oct 09, 2022 |
| Dell          | Latitude 5501               | [3396ccdbab](https://linux-hardware.org/?probe=3396ccdbab) | Oct 09, 2022 |
| HP            | Laptop 15-bw0xx             | [7231761ea1](https://linux-hardware.org/?probe=7231761ea1) | Oct 09, 2022 |
| MSI           | GV62 8RD                    | [8902a355f4](https://linux-hardware.org/?probe=8902a355f4) | Oct 09, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | [1f013f181d](https://linux-hardware.org/?probe=1f013f181d) | Oct 09, 2022 |
| Sony          | VPCEB46FG                   | [71e2273974](https://linux-hardware.org/?probe=71e2273974) | Oct 08, 2022 |
| HP            | ProBook 640 G3              | [03112f2830](https://linux-hardware.org/?probe=03112f2830) | Oct 08, 2022 |
| Dell          | Inspiron 5458               | [d6742b3ec0](https://linux-hardware.org/?probe=d6742b3ec0) | Oct 08, 2022 |
| ASUSTek       | G752VS                      | [df98c91ed6](https://linux-hardware.org/?probe=df98c91ed6) | Oct 08, 2022 |
| Lenovo        | V155-15API 81V5             | [c08e4bed15](https://linux-hardware.org/?probe=c08e4bed15) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Sony          | VPCEH3LFX                   | [fbb59e09fc](https://linux-hardware.org/?probe=fbb59e09fc) | Oct 07, 2022 |
| Alienware     | 17 R4                       | [cac06d6050](https://linux-hardware.org/?probe=cac06d6050) | Oct 07, 2022 |
| Positivo      | Mobile                      | [f26e597436](https://linux-hardware.org/?probe=f26e597436) | Oct 06, 2022 |
| MSI           | GP66 Leopard 10UG           | [c2082a042d](https://linux-hardware.org/?probe=c2082a042d) | Oct 06, 2022 |
| Acer          | Aspire 5520                 | [05e6a5cb26](https://linux-hardware.org/?probe=05e6a5cb26) | Oct 06, 2022 |
| Lenovo        | IdeaPad Y560                | [15e2c8994f](https://linux-hardware.org/?probe=15e2c8994f) | Oct 06, 2022 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [fa7e7d106e](https://linux-hardware.org/?probe=fa7e7d106e) | Oct 06, 2022 |
| Dell          | Vostro 15-3568              | [ed969ece24](https://linux-hardware.org/?probe=ed969ece24) | Oct 05, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [72163c289e](https://linux-hardware.org/?probe=72163c289e) | Oct 05, 2022 |
| Valve         | Jupiter                     | [2fda8270f0](https://linux-hardware.org/?probe=2fda8270f0) | Oct 05, 2022 |
| Acer          | Aspire A315-21              | [48901aff3f](https://linux-hardware.org/?probe=48901aff3f) | Oct 04, 2022 |
| Lenovo        | Z51-70 80K6                 | [736ded7422](https://linux-hardware.org/?probe=736ded7422) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [0a41ea4b4c](https://linux-hardware.org/?probe=0a41ea4b4c) | Oct 04, 2022 |
| HP            | EliteBook 1040 G4           | [8a19b834c8](https://linux-hardware.org/?probe=8a19b834c8) | Oct 04, 2022 |
| MSI           | GF63 Thin 11UD              | [b8237b1bd7](https://linux-hardware.org/?probe=b8237b1bd7) | Oct 04, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [eb1ee8ad1f](https://linux-hardware.org/?probe=eb1ee8ad1f) | Oct 04, 2022 |
| System76      | Lemur Pro                   | [8842585a92](https://linux-hardware.org/?probe=8842585a92) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| Dell          | Latitude E6420              | [652b18aabe](https://linux-hardware.org/?probe=652b18aabe) | Oct 03, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [1e0190a274](https://linux-hardware.org/?probe=1e0190a274) | Oct 03, 2022 |
| Google        | Banon                       | [269a819905](https://linux-hardware.org/?probe=269a819905) | Oct 03, 2022 |
| Fujitsu       | LIFEBOOK T5010              | [2637a452d0](https://linux-hardware.org/?probe=2637a452d0) | Oct 03, 2022 |
| Samsung       | 550XDA                      | [418d32112e](https://linux-hardware.org/?probe=418d32112e) | Oct 03, 2022 |
| Lenovo        | Flex 2-14 20404             | [b3a9474c83](https://linux-hardware.org/?probe=b3a9474c83) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [0382d1ec36](https://linux-hardware.org/?probe=0382d1ec36) | Oct 02, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Dell          | XPS L421X                   | [aedcc42b0a](https://linux-hardware.org/?probe=aedcc42b0a) | Oct 02, 2022 |
| Apple         | MacBookPro5,2               | [b0a6dc4162](https://linux-hardware.org/?probe=b0a6dc4162) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | [b5c516677a](https://linux-hardware.org/?probe=b5c516677a) | Oct 02, 2022 |
| Acer          | Aspire ES1-522              | [86e57e249a](https://linux-hardware.org/?probe=86e57e249a) | Oct 02, 2022 |
| Alienware     | 15 R3                       | [28e4e84fb1](https://linux-hardware.org/?probe=28e4e84fb1) | Oct 02, 2022 |
| Lenovo        | Yoga 510-14ISK 80S7         | [8731307ce6](https://linux-hardware.org/?probe=8731307ce6) | Oct 02, 2022 |
| ASUSTek       | GL502VM                     | [1d1616405d](https://linux-hardware.org/?probe=1d1616405d) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [32dba0444e](https://linux-hardware.org/?probe=32dba0444e) | Oct 02, 2022 |
| Apple         | MacBook7,1                  | [49595ef8f4](https://linux-hardware.org/?probe=49595ef8f4) | Oct 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [46d6046fce](https://linux-hardware.org/?probe=46d6046fce) | Oct 02, 2022 |
| Micro Elec... | Element                     | [9cee0f76c1](https://linux-hardware.org/?probe=9cee0f76c1) | Oct 02, 2022 |
| Apple         | MacBookPro5,5               | [42113dd7e3](https://linux-hardware.org/?probe=42113dd7e3) | Oct 01, 2022 |
| HUAWEI        | HN-WX9X                     | [4168f641b5](https://linux-hardware.org/?probe=4168f641b5) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| Dell          | Latitude E5530 non-vPro     | [b2d146f923](https://linux-hardware.org/?probe=b2d146f923) | Oct 01, 2022 |
| HP            | Pavilion                    | [124e8b760a](https://linux-hardware.org/?probe=124e8b760a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3595e90895](https://linux-hardware.org/?probe=3595e90895) | Oct 01, 2022 |
| System76      | Darter Pro                  | [2829e72506](https://linux-hardware.org/?probe=2829e72506) | Oct 01, 2022 |
| System76      | Darter Pro                  | [c142cf370a](https://linux-hardware.org/?probe=c142cf370a) | Oct 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [29648b493a](https://linux-hardware.org/?probe=29648b493a) | Oct 01, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DCCT... | [bde2b36c88](https://linux-hardware.org/?probe=bde2b36c88) | Oct 01, 2022 |
| Lenovo        | ThinkPad T480 20L5001FUS    | [a7e0da7aa4](https://linux-hardware.org/?probe=a7e0da7aa4) | Sep 30, 2022 |
| Dell          | Latitude 5400               | [66a5bc26f0](https://linux-hardware.org/?probe=66a5bc26f0) | Sep 30, 2022 |
| Apple         | MacBookPro14,3              | [3ccd7ea5d6](https://linux-hardware.org/?probe=3ccd7ea5d6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | [81653ba834](https://linux-hardware.org/?probe=81653ba834) | Sep 30, 2022 |
| HUAWEI        | VLT-WX0                     | [1669dae0a6](https://linux-hardware.org/?probe=1669dae0a6) | Sep 30, 2022 |
| Fujitsu       | LIFEBOOK A6210              | [d31b97630d](https://linux-hardware.org/?probe=d31b97630d) | Sep 29, 2022 |
| Dell          | Latitude 5400               | [4536a4b473](https://linux-hardware.org/?probe=4536a4b473) | Sep 29, 2022 |
| Dell          | Latitude 5400               | [972e4ab3fa](https://linux-hardware.org/?probe=972e4ab3fa) | Sep 29, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | [d06b40ddf1](https://linux-hardware.org/?probe=d06b40ddf1) | Sep 29, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [f758c22d98](https://linux-hardware.org/?probe=f758c22d98) | Sep 28, 2022 |
| Lenovo        | ThinkPad X220 4286PJ2       | [2d0c850c3a](https://linux-hardware.org/?probe=2d0c850c3a) | Sep 28, 2022 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | [b08fc47990](https://linux-hardware.org/?probe=b08fc47990) | Sep 28, 2022 |
| Lenovo        | G510 20238                  | [46cba6613f](https://linux-hardware.org/?probe=46cba6613f) | Sep 28, 2022 |
| Dell          | Latitude E7450              | [daeb4afb69](https://linux-hardware.org/?probe=daeb4afb69) | Sep 28, 2022 |
| Apple         | MacBookPro9,2               | [5ce350f38b](https://linux-hardware.org/?probe=5ce350f38b) | Sep 28, 2022 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [a3c4032d28](https://linux-hardware.org/?probe=a3c4032d28) | Sep 27, 2022 |
| Gigabyte      | P34V7                       | [27b9651432](https://linux-hardware.org/?probe=27b9651432) | Sep 27, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | [99b6a53bd2](https://linux-hardware.org/?probe=99b6a53bd2) | Sep 27, 2022 |
| ASUSTek       | GL702VSK                    | [3b69ddb263](https://linux-hardware.org/?probe=3b69ddb263) | Sep 27, 2022 |
| Acer          | Nitro AN515-45              | [8579eba471](https://linux-hardware.org/?probe=8579eba471) | Sep 26, 2022 |
| ASUSTek       | GL702VSK                    | [e91056ceab](https://linux-hardware.org/?probe=e91056ceab) | Sep 26, 2022 |
| Dell          | Inspiron N5110              | [eff6424aa4](https://linux-hardware.org/?probe=eff6424aa4) | Sep 26, 2022 |
| System76      | Galago Pro                  | [6b2de473b7](https://linux-hardware.org/?probe=6b2de473b7) | Sep 26, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [1b4db0c30c](https://linux-hardware.org/?probe=1b4db0c30c) | Sep 26, 2022 |
| ASUSTek       | K52N                        | [8d7b00011f](https://linux-hardware.org/?probe=8d7b00011f) | Sep 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [acbd9cc9af](https://linux-hardware.org/?probe=acbd9cc9af) | Sep 25, 2022 |
| Acer          | Aspire V5-573G              | [50792d0ac6](https://linux-hardware.org/?probe=50792d0ac6) | Sep 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [27d8d35004](https://linux-hardware.org/?probe=27d8d35004) | Sep 25, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [e9de38d8eb](https://linux-hardware.org/?probe=e9de38d8eb) | Sep 25, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [5c39bdf4ab](https://linux-hardware.org/?probe=5c39bdf4ab) | Sep 24, 2022 |
| Razer         | Blade 15 Base Model (Ear... | [029c059963](https://linux-hardware.org/?probe=029c059963) | Sep 24, 2022 |
| HP            | Laptop 15s-eq1xxx           | [2bc6e102ef](https://linux-hardware.org/?probe=2bc6e102ef) | Sep 24, 2022 |
| MSI           | GF63 Thin 11UD              | [fac56b0962](https://linux-hardware.org/?probe=fac56b0962) | Sep 24, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [214a55ad3e](https://linux-hardware.org/?probe=214a55ad3e) | Sep 24, 2022 |
| Apple         | MacBookPro9,2               | [86b6d46191](https://linux-hardware.org/?probe=86b6d46191) | Sep 24, 2022 |
| MSI           | Prestige 14Evo A11M         | [609225524a](https://linux-hardware.org/?probe=609225524a) | Sep 23, 2022 |
| System76      | Darter Pro                  | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [7910fab01e](https://linux-hardware.org/?probe=7910fab01e) | Sep 22, 2022 |
| System76      | Darter Pro                  | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Dell          | Inspiron 5520               | [032bbec1e3](https://linux-hardware.org/?probe=032bbec1e3) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3c93753c6c](https://linux-hardware.org/?probe=3c93753c6c) | Sep 22, 2022 |
| Dell          | Latitude 3490               | [de749eeeb8](https://linux-hardware.org/?probe=de749eeeb8) | Sep 21, 2022 |
| Dell          | Precision 3561              | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Nitro AN715-51              | [36fb85e6cb](https://linux-hardware.org/?probe=36fb85e6cb) | Sep 21, 2022 |
| Dell          | Latitude 7490               | [b8c3a5519a](https://linux-hardware.org/?probe=b8c3a5519a) | Sep 21, 2022 |
| Dell          | XPS 13 9370                 | [facc4c1755](https://linux-hardware.org/?probe=facc4c1755) | Sep 21, 2022 |
| Acer          | Aspire A515-54              | [8116705a81](https://linux-hardware.org/?probe=8116705a81) | Sep 21, 2022 |
| Dell          | Vostro 3500                 | [7fa417e9a6](https://linux-hardware.org/?probe=7fa417e9a6) | Sep 21, 2022 |
| Apple         | MacBookAir6,2               | [7fc6799a48](https://linux-hardware.org/?probe=7fc6799a48) | Sep 21, 2022 |
| Dell          | Inspiron 5577               | [c6f4124e49](https://linux-hardware.org/?probe=c6f4124e49) | Sep 21, 2022 |
| Lenovo        | ThinkPad E490 20N8005JMH    | [8e78f3c776](https://linux-hardware.org/?probe=8e78f3c776) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| HP            | ProBook 455 G8 Notebook ... | [b1df3aa03f](https://linux-hardware.org/?probe=b1df3aa03f) | Sep 20, 2022 |
| Itronix       | GD8200                      | [d9f515b935](https://linux-hardware.org/?probe=d9f515b935) | Sep 20, 2022 |
| Lenovo        | Legion 5-15ACH6H 82JU       | [1f48647e32](https://linux-hardware.org/?probe=1f48647e32) | Sep 20, 2022 |
| GPU Compan... | GWTN141-10                  | [6d43012457](https://linux-hardware.org/?probe=6d43012457) | Sep 20, 2022 |
| HONOR         | NMH-WCX9                    | [dd2687098a](https://linux-hardware.org/?probe=dd2687098a) | Sep 19, 2022 |
| ASUSTek       | GL502VSK                    | [a6dc9b627f](https://linux-hardware.org/?probe=a6dc9b627f) | Sep 19, 2022 |
| HONOR         | NMH-WCX9                    | [060f3bd895](https://linux-hardware.org/?probe=060f3bd895) | Sep 19, 2022 |
| Apple         | MacBookPro10,2              | [ecc3b7e71d](https://linux-hardware.org/?probe=ecc3b7e71d) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| HP            | OMEN by Laptop 15z-en100    | [47b0aed151](https://linux-hardware.org/?probe=47b0aed151) | Sep 19, 2022 |
| Framework     | Laptop                      | [8dbbe54af9](https://linux-hardware.org/?probe=8dbbe54af9) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | [37b4da9922](https://linux-hardware.org/?probe=37b4da9922) | Sep 18, 2022 |
| Gateway       | NV55C                       | [e00587af22](https://linux-hardware.org/?probe=e00587af22) | Sep 18, 2022 |
| Dell          | Latitude E7470              | [ceed7544ab](https://linux-hardware.org/?probe=ceed7544ab) | Sep 18, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [f40cc0db8a](https://linux-hardware.org/?probe=f40cc0db8a) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [1ad10d3c4b](https://linux-hardware.org/?probe=1ad10d3c4b) | Sep 18, 2022 |
| Dell          | Precision 5530              | [8fc00af945](https://linux-hardware.org/?probe=8fc00af945) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50da0a8acf](https://linux-hardware.org/?probe=50da0a8acf) | Sep 18, 2022 |
| MSI           | Sword 15 A11UD              | [e749154c3d](https://linux-hardware.org/?probe=e749154c3d) | Sep 18, 2022 |
| Dell          | Latitude E6330              | [5a1085f939](https://linux-hardware.org/?probe=5a1085f939) | Sep 18, 2022 |
| ASUSTek       | S550CA                      | [a403b2a79d](https://linux-hardware.org/?probe=a403b2a79d) | Sep 17, 2022 |
| MSI           | Prestige 15 A12UC           | [48437ccf94](https://linux-hardware.org/?probe=48437ccf94) | Sep 17, 2022 |
| OriginPC      | NT17-PRO                    | [962138caa9](https://linux-hardware.org/?probe=962138caa9) | Sep 17, 2022 |
| System76      | Darter Pro                  | [5d1e0ddc1a](https://linux-hardware.org/?probe=5d1e0ddc1a) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [7099830d0a](https://linux-hardware.org/?probe=7099830d0a) | Sep 16, 2022 |
| Dell          | Inspiron 5547               | [d66cbae64b](https://linux-hardware.org/?probe=d66cbae64b) | Sep 16, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [4dd83a1b80](https://linux-hardware.org/?probe=4dd83a1b80) | Sep 16, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [b0e6601fbf](https://linux-hardware.org/?probe=b0e6601fbf) | Sep 16, 2022 |
| ASUSTek       | N550LF                      | [73f2edfe65](https://linux-hardware.org/?probe=73f2edfe65) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [9cc24963d4](https://linux-hardware.org/?probe=9cc24963d4) | Sep 16, 2022 |
| Apple         | MacBookPro5,4               | [6d28bb81ce](https://linux-hardware.org/?probe=6d28bb81ce) | Sep 16, 2022 |
| Toshiba       | Satellite C55t-C            | [9c45d5a042](https://linux-hardware.org/?probe=9c45d5a042) | Sep 16, 2022 |
| Dell          | XPS 13 9380                 | [6d94f648e4](https://linux-hardware.org/?probe=6d94f648e4) | Sep 16, 2022 |
| GPD           | MicroPC                     | [dadac68a23](https://linux-hardware.org/?probe=dadac68a23) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3196144640](https://linux-hardware.org/?probe=3196144640) | Sep 15, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [d39fd89ab8](https://linux-hardware.org/?probe=d39fd89ab8) | Sep 15, 2022 |
| Dell          | Precision 3561              | [b61765a085](https://linux-hardware.org/?probe=b61765a085) | Sep 15, 2022 |
| Fujitsu       | LIFEBOOK A512               | [2d33f80fbd](https://linux-hardware.org/?probe=2d33f80fbd) | Sep 15, 2022 |
| Dell          | Latitude 3420               | [5c00a1875c](https://linux-hardware.org/?probe=5c00a1875c) | Sep 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ed284e43fb](https://linux-hardware.org/?probe=ed284e43fb) | Sep 14, 2022 |
| Dell          | XPS 13 9360                 | [750bf03293](https://linux-hardware.org/?probe=750bf03293) | Sep 14, 2022 |
| MSI           | Katana GF66 12UE            | [955b9787eb](https://linux-hardware.org/?probe=955b9787eb) | Sep 14, 2022 |
| ASUSTek       | X555LN                      | [64b85307ec](https://linux-hardware.org/?probe=64b85307ec) | Sep 14, 2022 |
| ASUSTek       | X405UA                      | [3b098addea](https://linux-hardware.org/?probe=3b098addea) | Sep 14, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [aa0553a310](https://linux-hardware.org/?probe=aa0553a310) | Sep 13, 2022 |
| Lenovo        | ThinkBook 13x ITG 20WJ      | [2e6e759434](https://linux-hardware.org/?probe=2e6e759434) | Sep 13, 2022 |
| Lenovo        | Flex 2-14 20404             | [a27c60fbde](https://linux-hardware.org/?probe=a27c60fbde) | Sep 13, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [81b9b18da4](https://linux-hardware.org/?probe=81b9b18da4) | Sep 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [b502b7938d](https://linux-hardware.org/?probe=b502b7938d) | Sep 13, 2022 |
| Dell          | Studio 1555                 | [0d0f3de3b4](https://linux-hardware.org/?probe=0d0f3de3b4) | Sep 12, 2022 |
| Apple         | MacBook5,1                  | [8bdaf4361b](https://linux-hardware.org/?probe=8bdaf4361b) | Sep 12, 2022 |
| Lenovo        | ThinkPad P53 MFG_IN_GO     | [0c3d0800eb](https://linux-hardware.org/?probe=0c3d0800eb) | Sep 12, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [e1d128b56a](https://linux-hardware.org/?probe=e1d128b56a) | Sep 12, 2022 |
| ASUSTek       | ROG STRIX Z590-E GAMING ... | [1889334e1f](https://linux-hardware.org/?probe=1889334e1f) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [f9add8f93d](https://linux-hardware.org/?probe=f9add8f93d) | Sep 11, 2022 |
| MSI           | Modern 15 A11M              | [931f4d2ca7](https://linux-hardware.org/?probe=931f4d2ca7) | Sep 11, 2022 |
| Acer          | Aspire A315-42G             | [34964d8e2d](https://linux-hardware.org/?probe=34964d8e2d) | Sep 11, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| MSI           | Modern 15 A11M              | [4f1849370d](https://linux-hardware.org/?probe=4f1849370d) | Sep 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [f19e04efc1](https://linux-hardware.org/?probe=f19e04efc1) | Sep 10, 2022 |
| System76      | Oryx Pro                    | [d84de42ab6](https://linux-hardware.org/?probe=d84de42ab6) | Sep 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | [c0adc468b3](https://linux-hardware.org/?probe=c0adc468b3) | Sep 10, 2022 |
| Dell          | Inspiron 16 5625            | [5ae1f0d923](https://linux-hardware.org/?probe=5ae1f0d923) | Sep 10, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [6c1c4c8712](https://linux-hardware.org/?probe=6c1c4c8712) | Sep 10, 2022 |
| HP            | Dev One Notebook PC         | [bb72f0c2f4](https://linux-hardware.org/?probe=bb72f0c2f4) | Sep 10, 2022 |
| Dell          | Vostro 3550                 | [2e9e331465](https://linux-hardware.org/?probe=2e9e331465) | Sep 10, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [5811e17863](https://linux-hardware.org/?probe=5811e17863) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4d3543d03f](https://linux-hardware.org/?probe=4d3543d03f) | Sep 09, 2022 |
| System76      | Galago Pro                  | [8d52d900f2](https://linux-hardware.org/?probe=8d52d900f2) | Sep 09, 2022 |
| Dell          | Inspiron 5457               | [e44e9d3a85](https://linux-hardware.org/?probe=e44e9d3a85) | Sep 08, 2022 |
| AZW           | SEi                         | [d3531738fa](https://linux-hardware.org/?probe=d3531738fa) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [6108c677a2](https://linux-hardware.org/?probe=6108c677a2) | Sep 08, 2022 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [0f8da1f0c8](https://linux-hardware.org/?probe=0f8da1f0c8) | Sep 08, 2022 |
| Dell          | Latitude 5420               | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [09e8283762](https://linux-hardware.org/?probe=09e8283762) | Sep 08, 2022 |
| HP            | 245 G6                      | [054d226709](https://linux-hardware.org/?probe=054d226709) | Sep 07, 2022 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [e73c83b5c7](https://linux-hardware.org/?probe=e73c83b5c7) | Sep 07, 2022 |
| HP            | EliteBook 840 G6            | [132a8e025a](https://linux-hardware.org/?probe=132a8e025a) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [af2641c077](https://linux-hardware.org/?probe=af2641c077) | Sep 07, 2022 |
| Acer          | Aspire S3                   | [cb62300974](https://linux-hardware.org/?probe=cb62300974) | Sep 07, 2022 |
| Lenovo        | ThinkPad T470s 20HGA039U... | [43c002ad40](https://linux-hardware.org/?probe=43c002ad40) | Sep 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11b9de78b5](https://linux-hardware.org/?probe=11b9de78b5) | Sep 06, 2022 |
| Lenovo        | ThinkPad T480s 20L8SC160... | [b860019cf4](https://linux-hardware.org/?probe=b860019cf4) | Sep 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | [40d6a47565](https://linux-hardware.org/?probe=40d6a47565) | Sep 05, 2022 |
| Clevo         | P65_P67SE                   | [9a38027b73](https://linux-hardware.org/?probe=9a38027b73) | Sep 05, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [cb787086fa](https://linux-hardware.org/?probe=cb787086fa) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [61e1164988](https://linux-hardware.org/?probe=61e1164988) | Sep 04, 2022 |
| Dell          | XPS 15 9500                 | [ea5f9662d7](https://linux-hardware.org/?probe=ea5f9662d7) | Sep 04, 2022 |
| Dell          | Inspiron 3576               | [8f5998a9e4](https://linux-hardware.org/?probe=8f5998a9e4) | Sep 04, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                              | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| 5.19.0-76051900-generic              | 270       | 20.06%  |
| 6.0.12-76060006-generic              | 233       | 17.31%  |
| 5.17.5-76051705-generic              | 227       | 16.86%  |
| 6.0.6-76060006-generic               | 161       | 11.96%  |
| 5.18.10-76051810-generic             | 117       | 8.69%   |
| 5.17.15-76051715-generic             | 104       | 7.73%   |
| 5.16.19-76051619-generic             | 70        | 5.2%    |
| 6.0.2-76060002-generic               | 59        | 4.38%   |
| 6.1.11-76060111-generic              | 24        | 1.78%   |
| 6.0.3-76060003-generic               | 23        | 1.71%   |
| 5.19.16-76051916-generic             | 21        | 1.56%   |
| 6.1.0-1006-oem                       | 2         | 0.15%   |
| 5.17.5-051705-generic                | 2         | 0.15%   |
| 5.16.15-76051615-generic             | 2         | 0.15%   |
| 6.1.9-060109-generic                 | 1         | 0.07%   |
| 6.1.8-060108-generic                 | 1         | 0.07%   |
| 6.1.7-060107-generic                 | 1         | 0.07%   |
| 6.1.14-x64v2-xanmod1                 | 1         | 0.07%   |
| 6.1.0-2.1-liquorix-amd64             | 1         | 0.07%   |
| 6.0.9-x64v1-xanmod1                  | 1         | 0.07%   |
| 6.0.9-060009-generic                 | 1         | 0.07%   |
| 6.0.2-x64v2-xanmod1                  | 1         | 0.07%   |
| 6.0.0-060000rc1daily20220820-generic | 1         | 0.07%   |
| 6.0.0-060000-generic                 | 1         | 0.07%   |
| 5.19.4-xanmod1                       | 1         | 0.07%   |
| 5.19.3-051903-generic                | 1         | 0.07%   |
| 5.19.14-xanmod1                      | 1         | 0.07%   |
| 5.19.12-xanmod1                      | 1         | 0.07%   |
| 5.19.0-rc1+                          | 1         | 0.07%   |
| 5.19.0-051900-generic                | 1         | 0.07%   |
| 5.18.6-xanmod1                       | 1         | 0.07%   |
| 5.18.4-xanmod1                       | 1         | 0.07%   |
| 5.18.16-xanmod1                      | 1         | 0.07%   |
| 5.18.0-051800rc1-generic             | 1         | 0.07%   |
| 5.17.7-051707-generic                | 1         | 0.07%   |
| 5.17.6-051706-generic                | 1         | 0.07%   |
| 5.17.5-tkg-bmq                       | 1         | 0.07%   |
| 5.17.2-xanmod1                       | 1         | 0.07%   |
| 5.17.0-1020-oem                      | 1         | 0.07%   |
| 5.17.0-051700-generic                | 1         | 0.07%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.19.0  | 272       | 20.22%  |
| 6.0.12  | 233       | 17.32%  |
| 5.17.5  | 230       | 17.1%   |
| 6.0.6   | 161       | 11.97%  |
| 5.18.10 | 117       | 8.7%    |
| 5.17.15 | 104       | 7.73%   |
| 5.16.19 | 70        | 5.2%    |
| 6.0.2   | 60        | 4.46%   |
| 6.1.11  | 24        | 1.78%   |
| 6.0.3   | 23        | 1.71%   |
| 5.19.16 | 21        | 1.56%   |
| 6.1.0   | 2         | 0.15%   |
| 6.0.9   | 2         | 0.15%   |
| 6.0.0   | 2         | 0.15%   |
| 5.17.0  | 2         | 0.15%   |
| 5.16.15 | 2         | 0.15%   |
| 5.15.0  | 2         | 0.15%   |
| 6.1.9   | 1         | 0.07%   |
| 6.1.8   | 1         | 0.07%   |
| 6.1.7   | 1         | 0.07%   |
| 6.1.14  | 1         | 0.07%   |
| 5.19.4  | 1         | 0.07%   |
| 5.19.3  | 1         | 0.07%   |
| 5.19.14 | 1         | 0.07%   |
| 5.19.12 | 1         | 0.07%   |
| 5.18.6  | 1         | 0.07%   |
| 5.18.4  | 1         | 0.07%   |
| 5.18.16 | 1         | 0.07%   |
| 5.18.0  | 1         | 0.07%   |
| 5.17.7  | 1         | 0.07%   |
| 5.17.6  | 1         | 0.07%   |
| 5.17.2  | 1         | 0.07%   |
| 5.16.11 | 1         | 0.07%   |
| 5.15.87 | 1         | 0.07%   |
| 5.15.65 | 1         | 0.07%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 465       | 35.2%   |
| 5.17    | 333       | 25.21%  |
| 5.19    | 295       | 22.33%  |
| 5.18    | 121       | 9.16%   |
| 5.16    | 73        | 5.53%   |
| 6.1     | 30        | 2.27%   |
| 5.15    | 4         | 0.3%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1249      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1224      | 97.84%  |
| KDE5            | 12        | 0.96%   |
| Unknown         | 7         | 0.56%   |
| X-Cinnamon      | 3         | 0.24%   |
| GNOME Flashback | 2         | 0.16%   |
| XFCE            | 1         | 0.08%   |
| Unity           | 1         | 0.08%   |
| LXQt            | 1         | 0.08%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1191      | 94.9%   |
| Wayland | 56        | 4.46%   |
| Unknown | 6         | 0.48%   |
| Tty     | 2         | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 908       | 72.18%  |
| GDM3    | 345       | 27.42%  |
| GDM     | 4         | 0.32%   |
| SDDM    | 1         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 756       | 60.29%  |
| en_GB   | 85        | 6.78%   |
| pt_BR   | 72        | 5.74%   |
| de_DE   | 48        | 3.83%   |
| it_IT   | 36        | 2.87%   |
| en_AU   | 28        | 2.23%   |
| C       | 28        | 2.23%   |
| fr_FR   | 21        | 1.67%   |
| es_ES   | 19        | 1.52%   |
| ru_RU   | 15        | 1.2%    |
| en_CA   | 15        | 1.2%    |
| pl_PL   | 10        | 0.8%    |
| nb_NO   | 10        | 0.8%    |
| sv_SE   | 9         | 0.72%   |
| en_IE   | 9         | 0.72%   |
| en_NZ   | 8         | 0.64%   |
| es_MX   | 6         | 0.48%   |
| en_IN   | 6         | 0.48%   |
| Unknown | 6         | 0.48%   |
| pt_PT   | 5         | 0.4%    |
| nl_NL   | 5         | 0.4%    |
| fr_CA   | 5         | 0.4%    |
| fi_FI   | 5         | 0.4%    |
| es_AR   | 5         | 0.4%    |
| de_CH   | 5         | 0.4%    |
| tr_TR   | 3         | 0.24%   |
| es_CO   | 3         | 0.24%   |
| es_CL   | 3         | 0.24%   |
| en_ZA   | 3         | 0.24%   |
| fr_CH   | 2         | 0.16%   |
| en_SG   | 2         | 0.16%   |
| en_DK   | 2         | 0.16%   |
| da_DK   | 2         | 0.16%   |
| cs_CZ   | 2         | 0.16%   |
| sr_RS   | 1         | 0.08%   |
| ro_RO   | 1         | 0.08%   |
| lv_LV   | 1         | 0.08%   |
| ja_JP   | 1         | 0.08%   |
| hr_HR   | 1         | 0.08%   |
| fr_BE   | 1         | 0.08%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 924       | 73.57%  |
| EFI  | 332       | 26.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1180      | 94.25%  |
| Btrfs   | 49        | 3.91%   |
| Overlay | 18        | 1.44%   |
| Xfs     | 4         | 0.32%   |
| Zfs     | 1         | 0.08%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 901       | 71.62%  |
| GPT     | 334       | 26.55%  |
| MBR     | 23        | 1.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1217      | 97.2%   |
| Yes       | 35        | 2.8%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1137      | 90.67%  |
| Yes       | 117       | 9.33%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 249       | 19.94%  |
| Dell                   | 215       | 17.21%  |
| Hewlett-Packard        | 159       | 12.73%  |
| ASUSTek Computer       | 159       | 12.73%  |
| Acer                   | 93        | 7.45%   |
| Apple                  | 85        | 6.81%   |
| MSI                    | 45        | 3.6%    |
| System76               | 43        | 3.44%   |
| Toshiba                | 24        | 1.92%   |
| Samsung Electronics    | 20        | 1.6%    |
| HUAWEI                 | 18        | 1.44%   |
| Google                 | 10        | 0.8%    |
| Fujitsu                | 9         | 0.72%   |
| Alienware              | 9         | 0.72%   |
| GPU Company            | 8         | 0.64%   |
| Sony                   | 7         | 0.56%   |
| Notebook               | 7         | 0.56%   |
| Timi                   | 6         | 0.48%   |
| Gigabyte Technology    | 6         | 0.48%   |
| Framework              | 6         | 0.48%   |
| Razer                  | 5         | 0.4%    |
| Avell High Performance | 5         | 0.4%    |
| HONOR                  | 4         | 0.32%   |
| TUXEDO                 | 3         | 0.24%   |
| PC Specialist          | 3         | 0.24%   |
| LG Electronics         | 3         | 0.24%   |
| Clevo                  | 3         | 0.24%   |
| Unknown                | 3         | 0.24%   |
| Valve                  | 2         | 0.16%   |
| Positivo               | 2         | 0.16%   |
| Panasonic              | 2         | 0.16%   |
| OriginPC               | 2         | 0.16%   |
| Medion                 | 2         | 0.16%   |
| GPD                    | 2         | 0.16%   |
| Wortmann AG            | 1         | 0.08%   |
| VANT                   | 1         | 0.08%   |
| Tactus                 | 1         | 0.08%   |
| Star Labs              | 1         | 0.08%   |
| Semp Toshiba           | 1         | 0.08%   |
| Schenker               | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| System76 Oryx Pro                   | 13        | 1.04%   |
| System76 Lemur Pro                  | 12        | 0.96%   |
| System76 Gazelle                    | 7         | 0.56%   |
| Apple MacBookPro9,2                 | 7         | 0.56%   |
| Apple MacBookPro12,1                | 7         | 0.56%   |
| Apple MacBookAir7,2                 | 7         | 0.56%   |
| Apple MacBookAir6,2                 | 7         | 0.56%   |
| Unknown                             | 7         | 0.56%   |
| Lenovo IdeaPad S145-15API 81V7      | 6         | 0.48%   |
| Dell XPS 15 9520                    | 6         | 0.48%   |
| Dell XPS 13 9360                    | 5         | 0.4%    |
| Dell Latitude E7240                 | 5         | 0.4%    |
| Apple MacBookPro7,1                 | 5         | 0.4%    |
| Acer Aspire A515-45                 | 5         | 0.4%    |
| System76 Galago Pro                 | 4         | 0.32%   |
| Lenovo Legion 5 15ACH6H 82JU        | 4         | 0.32%   |
| HP Pavilion 15                      | 4         | 0.32%   |
| HP Notebook                         | 4         | 0.32%   |
| HP Dev One Notebook PC              | 4         | 0.32%   |
| Framework Laptop                    | 4         | 0.32%   |
| Dell XPS 13 9310                    | 4         | 0.32%   |
| Dell XPS 13 9305                    | 4         | 0.32%   |
| Dell Latitude E7270                 | 4         | 0.32%   |
| Dell Latitude E6540                 | 4         | 0.32%   |
| Apple MacBookPro11,3                | 4         | 0.32%   |
| System76 Darter Pro                 | 3         | 0.24%   |
| MSI Prestige 15 A10SC               | 3         | 0.24%   |
| Lenovo Legion Y530-15ICH 81FV       | 3         | 0.24%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN    | 3         | 0.24%   |
| Lenovo IdeaPad 330-15IKB 81FE       | 3         | 0.24%   |
| Lenovo IdeaPad 3 15ALC6 82MF        | 3         | 0.24%   |
| HP Pavilion Notebook                | 3         | 0.24%   |
| HP Pavilion Gaming Laptop 15-dk0xxx | 3         | 0.24%   |
| HP Pavilion dv6                     | 3         | 0.24%   |
| HP OMEN Laptop 15-en0xxx            | 3         | 0.24%   |
| HP Laptop 15s-eq2xxx                | 3         | 0.24%   |
| HP EliteBook 840 G5                 | 3         | 0.24%   |
| HP 15 Notebook PC                   | 3         | 0.24%   |
| GPU Company GWTN141-10              | 3         | 0.24%   |
| GPU Company GWTC116-2               | 3         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 112       | 8.97%   |
| Lenovo IdeaPad     | 62        | 4.96%   |
| Acer Aspire        | 60        | 4.8%    |
| Dell Inspiron      | 57        | 4.56%   |
| Dell Latitude      | 52        | 4.16%   |
| Dell XPS           | 46        | 3.68%   |
| HP Pavilion        | 33        | 2.64%   |
| Lenovo Legion      | 31        | 2.48%   |
| ASUS VivoBook      | 30        | 2.4%    |
| ASUS ROG           | 29        | 2.32%   |
| HP EliteBook       | 28        | 2.24%   |
| HP Laptop          | 27        | 2.16%   |
| Dell Precision     | 23        | 1.84%   |
| Toshiba Satellite  | 21        | 1.68%   |
| HP ProBook         | 21        | 1.68%   |
| ASUS ASUS          | 18        | 1.44%   |
| Acer Swift         | 15        | 1.2%    |
| System76 Oryx      | 13        | 1.04%   |
| Dell Vostro        | 13        | 1.04%   |
| System76 Lemur     | 12        | 0.96%   |
| ASUS Zenbook       | 12        | 0.96%   |
| Apple MacBookPro11 | 12        | 0.96%   |
| HP ZBook           | 11        | 0.88%   |
| Lenovo ThinkBook   | 10        | 0.8%    |
| Acer Nitro         | 10        | 0.8%    |
| HP OMEN            | 9         | 0.72%   |
| HP ENVY            | 9         | 0.72%   |
| Dell G15           | 8         | 0.64%   |
| Apple MacBookPro9  | 8         | 0.64%   |
| System76 Gazelle   | 7         | 0.56%   |
| Fujitsu LIFEBOOK   | 7         | 0.56%   |
| Apple MacBookPro5  | 7         | 0.56%   |
| Apple MacBookPro12 | 7         | 0.56%   |
| Apple MacBookAir7  | 7         | 0.56%   |
| Apple MacBookAir6  | 7         | 0.56%   |
| Unknown            | 7         | 0.56%   |
| MSI Prestige       | 6         | 0.48%   |
| Framework Laptop   | 6         | 0.48%   |
| System76 Galago    | 5         | 0.4%    |
| Razer Blade        | 5         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 225       | 18.01%  |
| 2020 | 149       | 11.93%  |
| 2022 | 126       | 10.09%  |
| 2019 | 115       | 9.21%   |
| 2018 | 95        | 7.61%   |
| 2013 | 78        | 6.24%   |
| 2016 | 76        | 6.08%   |
| 2012 | 68        | 5.44%   |
| 2015 | 66        | 5.28%   |
| 2017 | 60        | 4.8%    |
| 2011 | 51        | 4.08%   |
| 2014 | 48        | 3.84%   |
| 2010 | 39        | 3.12%   |
| 2009 | 34        | 2.72%   |
| 2008 | 13        | 1.04%   |
| 2007 | 5         | 0.4%    |
| 2023 | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1249      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1249      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1206      | 96.56%  |
| Yes  | 43        | 3.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 362       | 28.8%   |
| 16.01-24.0  | 315       | 25.06%  |
| 8.01-16.0   | 234       | 18.62%  |
| 3.01-4.0    | 147       | 11.69%  |
| 32.01-64.0  | 136       | 10.82%  |
| 64.01-256.0 | 32        | 2.55%   |
| 24.01-32.0  | 23        | 1.83%   |
| 2.01-3.0    | 5         | 0.4%    |
| 1.01-2.0    | 3         | 0.24%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 443       | 33.48%  |
| 4.01-8.0   | 331       | 25.02%  |
| 3.01-4.0   | 298       | 22.52%  |
| 1.01-2.0   | 149       | 11.26%  |
| 8.01-16.0  | 88        | 6.65%   |
| 16.01-24.0 | 12        | 0.91%   |
| 24.01-32.0 | 2         | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 911       | 72.53%  |
| 2      | 302       | 24.04%  |
| 3      | 34        | 2.71%   |
| 0      | 4         | 0.32%   |
| 4      | 3         | 0.24%   |
| 7      | 1         | 0.08%   |
| 5      | 1         | 0.08%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 978       | 78.18%  |
| Yes       | 273       | 21.82%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 935       | 74.68%  |
| No        | 317       | 25.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1229      | 98.4%   |
| No        | 20        | 1.6%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1074      | 85.65%  |
| No        | 180       | 14.35%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 327       | 26.04%  |
| Brazil      | 109       | 8.68%   |
| Germany     | 75        | 5.97%   |
| Italy       | 61        | 4.86%   |
| India       | 56        | 4.46%   |
| UK          | 55        | 4.38%   |
| Canada      | 46        | 3.66%   |
| France      | 35        | 2.79%   |
| Australia   | 34        | 2.71%   |
| Russia      | 28        | 2.23%   |
| Spain       | 22        | 1.75%   |
| Norway      | 22        | 1.75%   |
| Sweden      | 20        | 1.59%   |
| Netherlands | 20        | 1.59%   |
| Poland      | 16        | 1.27%   |
| Mexico      | 16        | 1.27%   |
| Portugal    | 14        | 1.11%   |
| New Zealand | 14        | 1.11%   |
| Turkey      | 13        | 1.04%   |
| Switzerland | 13        | 1.04%   |
| Romania     | 12        | 0.96%   |
| Greece      | 12        | 0.96%   |
| Argentina   | 12        | 0.96%   |
| Thailand    | 11        | 0.88%   |
| Philippines | 11        | 0.88%   |
| Finland     | 10        | 0.8%    |
| Belgium     | 10        | 0.8%    |
| Indonesia   | 9         | 0.72%   |
| Ireland     | 8         | 0.64%   |
| Chile       | 8         | 0.64%   |
| Bulgaria    | 8         | 0.64%   |
| Serbia      | 7         | 0.56%   |
| Hungary     | 7         | 0.56%   |
| Denmark     | 7         | 0.56%   |
| Colombia    | 7         | 0.56%   |
| Austria     | 7         | 0.56%   |
| Egypt       | 6         | 0.48%   |
| Singapore   | 5         | 0.4%    |
| Georgia     | 5         | 0.4%    |
| Czechia     | 5         | 0.4%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Milan          | 12        | 0.93%   |
| Brisbane       | 11        | 0.85%   |
| Oslo           | 10        | 0.78%   |
| Istanbul       | 10        | 0.78%   |
| Berlin         | 10        | 0.78%   |
| Melbourne      | 9         | 0.7%    |
| Bengaluru      | 9         | 0.7%    |
| Rome           | 8         | 0.62%   |
| Moscow         | 8         | 0.62%   |
| London         | 8         | 0.62%   |
| Sao Paulo      | 7         | 0.54%   |
| Rio de Janeiro | 7         | 0.54%   |
| Helsinki       | 7         | 0.54%   |
| Auckland       | 7         | 0.54%   |
| Sydney         | 6         | 0.47%   |
| St Petersburg  | 6         | 0.47%   |
| Mumbai         | 6         | 0.47%   |
| Minneapolis    | 6         | 0.47%   |
| Chicago        | 6         | 0.47%   |
| Calgary        | 6         | 0.47%   |
| Zurich         | 5         | 0.39%   |
| Warsaw         | 5         | 0.39%   |
| Sofia          | 5         | 0.39%   |
| Singapore      | 5         | 0.39%   |
| Lisbon         | 5         | 0.39%   |
| Edmonton       | 5         | 0.39%   |
| Denver         | 5         | 0.39%   |
| Dallas         | 5         | 0.39%   |
| Budapest       | 5         | 0.39%   |
| Bucharest      | 5         | 0.39%   |
| Belgrade       | 5         | 0.39%   |
| Vienna         | 4         | 0.31%   |
| Toronto        | 4         | 0.31%   |
| Stockholm      | 4         | 0.31%   |
| Seattle        | 4         | 0.31%   |
| San Jose       | 4         | 0.31%   |
| San Diego      | 4         | 0.31%   |
| Pune           | 4         | 0.31%   |
| Paris          | 4         | 0.31%   |
| New York       | 4         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 310       | 386    | 19.65%  |
| WDC                            | 144       | 159    | 9.13%   |
| SanDisk                        | 131       | 161    | 8.3%    |
| Seagate                        | 112       | 128    | 7.1%    |
| SK hynix                       | 89        | 102    | 5.64%   |
| Toshiba                        | 86        | 98     | 5.45%   |
| Kingston                       | 75        | 86     | 4.75%   |
| Micron Technology              | 59        | 65     | 3.74%   |
| Unknown                        | 58        | 70     | 3.68%   |
| Crucial                        | 55        | 57     | 3.49%   |
| Intel                          | 54        | 63     | 3.42%   |
| Apple                          | 47        | 51     | 2.98%   |
| HGST                           | 38        | 40     | 2.41%   |
| Phison                         | 21        | 23     | 1.33%   |
| KIOXIA                         | 21        | 22     | 1.33%   |
| A-DATA Technology              | 20        | 23     | 1.27%   |
| Hitachi                        | 17        | 20     | 1.08%   |
| PNY                            | 16        | 22     | 1.01%   |
| Micron/Crucial Technology      | 14        | 16     | 0.89%   |
| Silicon Motion                 | 12        | 13     | 0.76%   |
| China                          | 12        | 13     | 0.76%   |
| Phison Electronics             | 10        | 12     | 0.63%   |
| LITEON                         | 10        | 11     | 0.63%   |
| KingSpec                       | 9         | 10     | 0.57%   |
| Union Memory (Shenzhen)        | 8         | 10     | 0.51%   |
| Netac                          | 8         | 8      | 0.51%   |
| LITEONIT                       | 8         | 10     | 0.51%   |
| Intenso                        | 8         | 8      | 0.51%   |
| Unknown                        | 7         | 8      | 0.44%   |
| Kingston Technology Company    | 6         | 6      | 0.38%   |
| SPCC                           | 5         | 5      | 0.32%   |
| ADATA Technology               | 5         | 5      | 0.32%   |
| Team                           | 4         | 4      | 0.25%   |
| Solid State Storage Technology | 4         | 4      | 0.25%   |
| Patriot                        | 4         | 4      | 0.25%   |
| W800S                          | 3         | 6      | 0.19%   |
| Transcend                      | 3         | 4      | 0.19%   |
| SSSTC                          | 3         | 3      | 0.19%   |
| Solid State Storage            | 3         | 3      | 0.19%   |
| MyDigitalSSD                   | 3         | 3      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB  | 29        | 1.75%   |
| Kingston SA400S37240G 240GB SSD                      | 23        | 1.39%   |
| Seagate ST1000LM035-1RK172 1TB                       | 21        | 1.27%   |
| Samsung NVMe SSD Drive 512GB                         | 17        | 1.03%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 512GB  | 16        | 0.97%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 960GB | 16        | 0.97%   |
| SK hynix NVMe SSD Drive 512GB                        | 14        | 0.85%   |
| Crucial CT240BX500SSD1 240GB                         | 14        | 0.85%   |
| HGST HTS721010A9E630 1TB                             | 13        | 0.79%   |
| Toshiba MQ01ABD100 1TB                               | 12        | 0.73%   |
| SanDisk NVMe SSD Drive 1TB                           | 12        | 0.73%   |
| Unknown MMC Card  64GB                               | 11        | 0.66%   |
| Toshiba MQ04ABF100 1TB                               | 10        | 0.6%    |
| Seagate ST1000LM049-2GH172 1TB                       | 10        | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 10        | 0.6%    |
| Sandisk WD Blue SN550 NVMe SSD 1TB                   | 10        | 0.6%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB     | 10        | 0.6%    |
| SanDisk NVMe SSD Drive 512GB                         | 10        | 0.6%    |
| Samsung NVMe SSD Drive 1TB                           | 10        | 0.6%    |
| Kingston SA400S37480G 480GB SSD                      | 10        | 0.6%    |
| WDC WD10SPZX-24Z10 1TB                               | 9         | 0.54%   |
| SK hynix NVMe SSD Drive 1024GB                       | 9         | 0.54%   |
| SanDisk NVMe SSD Drive 256GB                         | 9         | 0.54%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB               | 9         | 0.54%   |
| Samsung NVMe SSD Drive 500GB                         | 9         | 0.54%   |
| Intel SSD 660P Series 1024GB                         | 9         | 0.54%   |
| Unknown MMC Card  32GB                               | 8         | 0.48%   |
| Unknown MMC Card  128GB                              | 8         | 0.48%   |
| Samsung SSD 850 EVO 500GB                            | 8         | 0.48%   |
| Samsung NVMe SSD Drive 2TB                           | 8         | 0.48%   |
| Samsung NVMe SSD Drive 1024GB                        | 8         | 0.48%   |
| Intel SSDPEKNW010T8 1TB                              | 8         | 0.48%   |
| Apple SSD SM0128G 121GB                              | 8         | 0.48%   |
| Samsung SSD 970 EVO Plus 1TB                         | 7         | 0.42%   |
| Samsung SSD 870 EVO 500GB                            | 7         | 0.42%   |
| Samsung SSD 860 EVO 500GB                            | 7         | 0.42%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                  | 7         | 0.42%   |
| Micron NVMe SSD Drive 512GB                          | 7         | 0.42%   |
| Kingston SA400S37120G 120GB SSD                      | 7         | 0.42%   |
| Kingston NVMe SSD Drive 512GB                        | 7         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 109       | 125    | 34.38%  |
| WDC                 | 82        | 91     | 25.87%  |
| Toshiba             | 48        | 55     | 15.14%  |
| HGST                | 38        | 40     | 11.99%  |
| Hitachi             | 17        | 20     | 5.36%   |
| Unknown             | 6         | 6      | 1.89%   |
| Samsung Electronics | 4         | 4      | 1.26%   |
| Fujitsu             | 3         | 3      | 0.95%   |
| Apple               | 3         | 4      | 0.95%   |
| JMicron Technology  | 2         | 2      | 0.63%   |
| Intenso             | 2         | 2      | 0.63%   |
| USB3.0              | 1         | 1      | 0.32%   |
| HGST HDN            | 1         | 1      | 0.32%   |
| Asm                 | 1         | 1      | 0.32%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 96        | 120    | 20.34%  |
| Kingston            | 55        | 60     | 11.65%  |
| SanDisk             | 49        | 58     | 10.38%  |
| Crucial             | 49        | 51     | 10.38%  |
| Apple               | 36        | 38     | 7.63%   |
| WDC                 | 26        | 30     | 5.51%   |
| PNY                 | 15        | 21     | 3.18%   |
| China               | 12        | 13     | 2.54%   |
| Toshiba             | 11        | 11     | 2.33%   |
| SK hynix            | 10        | 11     | 2.12%   |
| Micron Technology   | 9         | 9      | 1.91%   |
| LITEON              | 9         | 10     | 1.91%   |
| KingSpec            | 9         | 10     | 1.91%   |
| LITEONIT            | 8         | 10     | 1.69%   |
| Intel               | 8         | 8      | 1.69%   |
| A-DATA Technology   | 7         | 9      | 1.48%   |
| Netac               | 6         | 6      | 1.27%   |
| Intenso             | 5         | 5      | 1.06%   |
| Patriot             | 4         | 4      | 0.85%   |
| Transcend           | 3         | 4      | 0.64%   |
| SPCC                | 3         | 3      | 0.64%   |
| MyDigitalSSD        | 3         | 3      | 0.64%   |
| KingDian            | 2         | 2      | 0.42%   |
| Apacer              | 2         | 6      | 0.42%   |
| Unknown             | 2         | 2      | 0.42%   |
| W800S               | 1         | 1      | 0.21%   |
| TwinMOS             | 1         | 1      | 0.21%   |
| TrekStor            | 1         | 1      | 0.21%   |
| Teutons             | 1         | 1      | 0.21%   |
| SATAFIRM            | 1         | 1      | 0.21%   |
| Ramaxel Technology  | 1         | 1      | 0.21%   |
| Radeon              | 1         | 1      | 0.21%   |
| PUSKILL             | 1         | 1      | 0.21%   |
| PNY USB             | 1         | 1      | 0.21%   |
| Phison              | 1         | 1      | 0.21%   |
| OWC                 | 1         | 1      | 0.21%   |
| OCZ                 | 1         | 1      | 0.21%   |
| Lexar               | 1         | 1      | 0.21%   |
| Leven               | 1         | 1      | 0.21%   |
| LDLC                | 1         | 1      | 0.21%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 654       | 844    | 44.25%  |
| SSD     | 443       | 537    | 29.97%  |
| HDD     | 306       | 355    | 20.7%   |
| MMC     | 53        | 59     | 3.59%   |
| Unknown | 22        | 31     | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 663       | 853    | 46.43%  |
| NVMe | 653       | 842    | 45.73%  |
| SAS  | 59        | 72     | 4.13%   |
| MMC  | 53        | 59     | 3.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 471       | 584    | 63.73%  |
| 0.51-1.0   | 239       | 267    | 32.34%  |
| 1.01-2.0   | 21        | 28     | 2.84%   |
| 3.01-4.0   | 4         | 4      | 0.54%   |
| 4.01-10.0  | 4         | 9      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 411       | 32.44%  |
| 251-500        | 371       | 29.28%  |
| 501-1000       | 263       | 20.76%  |
| 1001-2000      | 89        | 7.02%   |
| 51-100         | 43        | 3.39%   |
| 1-20           | 26        | 2.05%   |
| 21-50          | 21        | 1.66%   |
| 2001-3000      | 21        | 1.66%   |
| More than 3000 | 16        | 1.26%   |
| Unknown        | 6         | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 427       | 32.55%  |
| 21-50          | 311       | 23.7%   |
| 101-250        | 204       | 15.55%  |
| 51-100         | 180       | 13.72%  |
| 251-500        | 110       | 8.38%   |
| 501-1000       | 55        | 4.19%   |
| 1001-2000      | 11        | 0.84%   |
| Unknown        | 6         | 0.46%   |
| More than 3000 | 5         | 0.38%   |
| 2001-3000      | 3         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 2      | 6.9%    |
| HGST HTS725050A7E630 500GB                          | 2         | 3      | 6.9%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 1         | 1      | 3.45%   |
| WDC WD3200BEKT-60PVMT0 320GB                        | 1         | 1      | 3.45%   |
| WDC WD10SPZX-22Z10T0 1TB                            | 1         | 1      | 3.45%   |
| WDC WD10JPVX-60JC3T1 1TB                            | 1         | 1      | 3.45%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB                | 1         | 1      | 3.45%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 1      | 3.45%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD            | 1         | 1      | 3.45%   |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 3.45%   |
| Toshiba MQ01ACF050 500GB                            | 1         | 1      | 3.45%   |
| Team TM8FP4004T 4TB                                 | 1         | 1      | 3.45%   |
| SK hynix PC711 HFS001TDE9X073N 1TB                  | 1         | 1      | 3.45%   |
| SK hynix HFS512G39TND-N210A 512GB SSD               | 1         | 1      | 3.45%   |
| SK hynix BC501 NVMe Solid State Drive 512GB         | 1         | 1      | 3.45%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 3.45%   |
| Seagate ST500LM030-2E717D 500GB                     | 1         | 1      | 3.45%   |
| Seagate ST1000LX015-1U7172 1TB                      | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 870 EVO 500GB               | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 850 EVO 500GB               | 1         | 1      | 3.45%   |
| Micron Technology MTFDDAK256MAY-1AH1ZABHA 256GB SSD | 1         | 1      | 3.45%   |
| Lexar 1TB SSD                                       | 1         | 1      | 3.45%   |
| Leven JAJS600M256C 256GB                            | 1         | 1      | 3.45%   |
| Hitachi HTS545050A7E380 500GB                       | 1         | 3      | 3.45%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 3.45%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 3.45%   |
| A-DATA Technology IM2P33F3 NVMe 512GB               | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 17.24%  |
| Seagate             | 5         | 5      | 17.24%  |
| Toshiba             | 4         | 4      | 13.79%  |
| HGST                | 4         | 5      | 13.79%  |
| SK hynix            | 3         | 3      | 10.34%  |
| Samsung Electronics | 2         | 2      | 6.9%    |
| Team                | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| Lexar               | 1         | 1      | 3.45%   |
| Leven               | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 3      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 33.33%  |
| HGST    | 4         | 5      | 26.67%  |
| WDC     | 3         | 3      | 20%     |
| Toshiba | 2         | 2      | 13.33%  |
| Hitachi | 1         | 3      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 15        | 18     | 51.72%  |
| SSD  | 8         | 8      | 27.59%  |
| NVMe | 6         | 6      | 20.69%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HM321HI 320GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 938       | 1348   | 71.17%  |
| Works    | 350       | 445    | 26.56%  |
| Malfunc  | 29        | 32     | 2.2%    |
| Failed   | 1         | 1      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 747       | 46%     |
| Samsung Electronics            | 240       | 14.78%  |
| AMD                            | 162       | 9.98%   |
| SanDisk                        | 114       | 7.02%   |
| SK hynix                       | 79        | 4.86%   |
| Micron Technology              | 49        | 3.02%   |
| Phison Electronics             | 34        | 2.09%   |
| Toshiba America Info Systems   | 27        | 1.66%   |
| Kingston Technology Company    | 25        | 1.54%   |
| Nvidia                         | 21        | 1.29%   |
| KIOXIA                         | 21        | 1.29%   |
| Micron/Crucial Technology      | 19        | 1.17%   |
| ADATA Technology               | 18        | 1.11%   |
| Silicon Motion                 | 14        | 0.86%   |
| Union Memory (Shenzhen)        | 10        | 0.62%   |
| Solid State Storage Technology | 10        | 0.62%   |
| Marvell Technology Group       | 8         | 0.49%   |
| Apple                          | 8         | 0.49%   |
| Shenzhen Longsys Electronics   | 5         | 0.31%   |
| Realtek Semiconductor          | 4         | 0.25%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.12%   |
| INNOGRIT                       | 2         | 0.12%   |
| Yangtze Memory Technologies    | 1         | 0.06%   |
| Seagate Technology             | 1         | 0.06%   |
| O2 Micro                       | 1         | 0.06%   |
| Netac Technology               | 1         | 0.06%   |
| Lite-On Technology             | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 156       | 9.14%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 94        | 5.51%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 85        | 4.98%   |
| Intel Volume Management Device NVMe RAID Controller                            | 72        | 4.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 67        | 3.93%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 66        | 3.87%   |
| Micron Non-Volatile memory controller                                          | 49        | 2.87%   |
| Samsung NVMe SSD Controller 980                                                | 48        | 2.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 48        | 2.81%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 47        | 2.75%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 43        | 2.52%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 43        | 2.52%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 41        | 2.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 33        | 1.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 32        | 1.87%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 31        | 1.82%   |
| SanDisk Non-Volatile memory controller                                         | 30        | 1.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 29        | 1.7%    |
| Intel SSD 660P Series                                                          | 25        | 1.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 25        | 1.46%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 24        | 1.41%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 23        | 1.35%   |
| Intel Tiger Lake-LP SATA Controller                                            | 21        | 1.23%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 21        | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 20        | 1.17%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 19        | 1.11%   |
| Samsung Electronics SATA controller                                            | 17        | 1%      |
| Phison E12 NVMe Controller                                                     | 17        | 1%      |
| Intel Comet Lake SATA AHCI Controller                                          | 17        | 1%      |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 17        | 1%      |
| Kingston Company Company Non-Volatile memory controller                        | 16        | 0.94%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 15        | 0.88%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 14        | 0.82%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 13        | 0.76%   |
| Intel Non-Volatile memory controller                                           | 13        | 0.76%   |
| SK hynix Non-Volatile memory controller                                        | 12        | 0.7%    |
| Nvidia MCP79 AHCI Controller                                                   | 12        | 0.7%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 12        | 0.7%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 11        | 0.64%   |
| Phison PS5013 E13 NVMe Controller                                              | 11        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 797       | 49.14%  |
| NVMe | 649       | 40.01%  |
| RAID | 144       | 8.88%   |
| IDE  | 32        | 1.97%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 965       | 77.26%  |
| AMD    | 284       | 22.74%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 33        | 2.64%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 29        | 2.32%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 29        | 2.32%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 22        | 1.76%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 21        | 1.68%   |
| Intel 12th Gen Core i7-12700H                 | 21        | 1.68%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 20        | 1.6%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 20        | 1.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 18        | 1.44%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 18        | 1.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 17        | 1.36%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 17        | 1.36%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 17        | 1.36%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 1.12%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 1.12%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 1.12%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 14        | 1.12%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 13        | 1.04%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.96%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.88%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 11        | 0.88%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 11        | 0.88%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 11        | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 10        | 0.8%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 10        | 0.8%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.72%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 9         | 0.72%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 9         | 0.72%   |
| Intel 12th Gen Core i7-1260P                  | 9         | 0.72%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 9         | 0.72%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 9         | 0.72%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.64%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 8         | 0.64%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.64%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 8         | 0.64%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 8         | 0.64%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 8         | 0.64%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 8         | 0.64%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 7         | 0.56%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 7         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 310       | 24.82%  |
| Intel Core i5           | 279       | 22.34%  |
| Other                   | 204       | 16.33%  |
| AMD Ryzen 7             | 95        | 7.61%   |
| AMD Ryzen 5             | 79        | 6.33%   |
| Intel Core i3           | 63        | 5.04%   |
| Intel Core 2 Duo        | 42        | 3.36%   |
| Intel Celeron           | 36        | 2.88%   |
| AMD Ryzen 9             | 20        | 1.6%    |
| AMD Ryzen 7 PRO         | 14        | 1.12%   |
| AMD Ryzen 3             | 13        | 1.04%   |
| Intel Pentium           | 11        | 0.88%   |
| AMD A10                 | 11        | 0.88%   |
| AMD A8                  | 10        | 0.8%    |
| AMD A6                  | 9         | 0.72%   |
| Intel Core i9           | 7         | 0.56%   |
| AMD Ryzen 5 PRO         | 7         | 0.56%   |
| Intel Pentium Dual-Core | 5         | 0.4%    |
| Intel Xeon              | 4         | 0.32%   |
| AMD A4                  | 4         | 0.32%   |
| Intel Pentium Silver    | 3         | 0.24%   |
| Intel Genuine           | 2         | 0.16%   |
| Intel Core M            | 2         | 0.16%   |
| AMD Ryzen 3 PRO         | 2         | 0.16%   |
| AMD Phenom II           | 2         | 0.16%   |
| AMD E1                  | 2         | 0.16%   |
| AMD Athlon              | 2         | 0.16%   |
| Intel Pentium Gold      | 1         | 0.08%   |
| Intel Core m3           | 1         | 0.08%   |
| Intel Core 2 Quad       | 1         | 0.08%   |
| Intel Core 2            | 1         | 0.08%   |
| Intel Atom              | 1         | 0.08%   |
| AMD Turion II           | 1         | 0.08%   |
| AMD Turion 64 X2 Mobile | 1         | 0.08%   |
| AMD E2                  | 1         | 0.08%   |
| AMD E                   | 1         | 0.08%   |
| AMD Athlon X2           | 1         | 0.08%   |
| AMD A12                 | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 442       | 35.39%  |
| 4      | 433       | 34.67%  |
| 8      | 167       | 13.37%  |
| 6      | 136       | 10.89%  |
| 14     | 35        | 2.8%    |
| 12     | 17        | 1.36%   |
| 10     | 13        | 1.04%   |
| 1      | 4         | 0.32%   |
| 16     | 1         | 0.08%   |
| 3      | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1249      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1086      | 86.88%  |
| 1      | 164       | 13.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1249      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 890       | 70.36%  |
| 0x806c1    | 33        | 2.61%   |
| 0x0a50000c | 27        | 2.13%   |
| 0x806d1    | 22        | 1.74%   |
| 0x906a3    | 21        | 1.66%   |
| 0x806ec    | 19        | 1.5%    |
| 0x806ea    | 19        | 1.5%    |
| 0xa0652    | 18        | 1.42%   |
| 0x906ea    | 16        | 1.26%   |
| 0x306a9    | 16        | 1.26%   |
| 0x406e3    | 11        | 0.87%   |
| 0x08608103 | 11        | 0.87%   |
| 0x08600106 | 11        | 0.87%   |
| 0x806e9    | 10        | 0.79%   |
| 0x40651    | 10        | 0.79%   |
| 0x906a4    | 8         | 0.63%   |
| 0x306d4    | 8         | 0.63%   |
| 0x1067a    | 8         | 0.63%   |
| 0x0a404101 | 8         | 0.63%   |
| 0x08600104 | 8         | 0.63%   |
| 0x906e9    | 7         | 0.55%   |
| 0x706e5    | 7         | 0.55%   |
| 0x506e3    | 7         | 0.55%   |
| 0x306c3    | 7         | 0.55%   |
| 0x206a7    | 7         | 0.55%   |
| 0x08108109 | 7         | 0.55%   |
| 0x806eb    | 5         | 0.4%    |
| 0x0a404102 | 5         | 0.4%    |
| 0x706a8    | 4         | 0.32%   |
| 0x0a50000d | 4         | 0.32%   |
| 0x906c0    | 3         | 0.24%   |
| 0x806c2    | 3         | 0.24%   |
| 0x08608102 | 3         | 0.24%   |
| 0x08600103 | 3         | 0.24%   |
| 0x08108102 | 3         | 0.24%   |
| 0xa0660    | 2         | 0.16%   |
| 0x0810100b | 2         | 0.16%   |
| 0x07030105 | 2         | 0.16%   |
| 0x906ed    | 1         | 0.08%   |
| 0x706a1    | 1         | 0.08%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 237       | 18.94%  |
| Unknown          | 125       | 9.99%   |
| Haswell          | 104       | 8.31%   |
| TigerLake        | 91        | 7.27%   |
| Zen 3            | 72        | 5.76%   |
| IvyBridge        | 69        | 5.52%   |
| SandyBridge      | 64        | 5.12%   |
| Skylake          | 56        | 4.48%   |
| Broadwell        | 51        | 4.08%   |
| CometLake        | 49        | 3.92%   |
| Zen 2            | 47        | 3.76%   |
| Zen+             | 45        | 3.6%    |
| Penryn           | 45        | 3.6%    |
| Icelake          | 39        | 3.12%   |
| Westmere         | 31        | 2.48%   |
| Alderlake Hybrid | 26        | 2.08%   |
| Goldmont plus    | 16        | 1.28%   |
| Silvermont       | 14        | 1.12%   |
| Excavator        | 14        | 1.12%   |
| Puma             | 12        | 0.96%   |
| Zen              | 10        | 0.8%    |
| Piledriver       | 9         | 0.72%   |
| K10 Llano        | 5         | 0.4%    |
| Core             | 5         | 0.4%    |
| Tremont          | 3         | 0.24%   |
| K10              | 3         | 0.24%   |
| Steamroller      | 2         | 0.16%   |
| Nehalem          | 2         | 0.16%   |
| K8 Hammer        | 2         | 0.16%   |
| Jaguar           | 1         | 0.08%   |
| Goldmont         | 1         | 0.08%   |
| Bobcat           | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 885       | 53.15%  |
| Nvidia | 447       | 26.85%  |
| AMD    | 333       | 20%     |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                 | Notebooks | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 85        | 4.99%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 64        | 3.76%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 61        | 3.58%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 59        | 3.47%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 54        | 3.17%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 52        | 3.06%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 51        | 3%      |
| Intel UHD Graphics 620                                                                | 48        | 2.82%   |
| AMD Renoir                                                                            | 47        | 2.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 45        | 2.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 39        | 2.29%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 37        | 2.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 37        | 2.17%   |
| Intel HD Graphics 620                                                                 | 37        | 2.17%   |
| AMD Lucienne                                                                          | 36        | 2.12%   |
| Intel HD Graphics 5500                                                                | 35        | 2.06%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 34        | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 34        | 2%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 32        | 1.88%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 27        | 1.59%   |
| Intel Core Processor Integrated Graphics Controller                                   | 25        | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 25        | 1.47%   |
| AMD Rembrandt [Radeon 680M]                                                           | 23        | 1.35%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 22        | 1.29%   |
| Intel HD Graphics 630                                                                 | 21        | 1.23%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 19        | 1.12%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 17        | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 17        | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 16        | 0.94%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                       | 16        | 0.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 15        | 0.88%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                            | 14        | 0.82%   |
| Intel HD Graphics 530                                                                 | 14        | 0.82%   |
| Nvidia TU117M                                                                         | 13        | 0.76%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 13        | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                | 13        | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 13        | 0.76%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 11        | 0.65%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                   | 11        | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 10        | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 555       | 44.26%  |
| Intel + Nvidia     | 291       | 23.21%  |
| 1 x AMD            | 190       | 15.15%  |
| AMD + Nvidia       | 80        | 6.38%   |
| 1 x Nvidia         | 69        | 5.5%    |
| Intel + AMD        | 37        | 2.95%   |
| 2 x AMD            | 26        | 2.07%   |
| 2 x Nvidia         | 3         | 0.24%   |
| Intel + 2 x Nvidia | 2         | 0.16%   |
| Other              | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 885       | 70.46%  |
| Proprietary | 353       | 28.11%  |
| Unknown     | 18        | 1.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1088      | 86.14%  |
| 0.01-0.5   | 52        | 4.12%   |
| 1.01-2.0   | 31        | 2.45%   |
| 3.01-4.0   | 28        | 2.22%   |
| 5.01-6.0   | 24        | 1.9%    |
| 7.01-8.0   | 21        | 1.66%   |
| 0.51-1.0   | 12        | 0.95%   |
| 8.01-16.0  | 4         | 0.32%   |
| 2.01-3.0   | 3         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 285       | 19.11%  |
| BOE                     | 219       | 14.69%  |
| Chimei Innolux          | 207       | 13.88%  |
| LG Display              | 187       | 12.54%  |
| Samsung Electronics     | 115       | 7.71%   |
| Apple                   | 70        | 4.69%   |
| Dell                    | 49        | 3.29%   |
| Goldstar                | 48        | 3.22%   |
| Sharp                   | 45        | 3.02%   |
| PANDA                   | 43        | 2.88%   |
| Lenovo                  | 22        | 1.48%   |
| Acer                    | 19        | 1.27%   |
| InfoVision              | 16        | 1.07%   |
| CSO                     | 16        | 1.07%   |
| Hewlett-Packard         | 13        | 0.87%   |
| Philips                 | 12        | 0.8%    |
| Chi Mei Optoelectronics | 12        | 0.8%    |
| ASUSTek Computer        | 12        | 0.8%    |
| AOC                     | 11        | 0.74%   |
| BenQ                    | 8         | 0.54%   |
| TMX                     | 7         | 0.47%   |
| Ancor Communications    | 7         | 0.47%   |
| ViewSonic               | 5         | 0.34%   |
| Sony                    | 4         | 0.27%   |
| Panasonic               | 4         | 0.27%   |
| MSI                     | 4         | 0.27%   |
| Vizio                   | 3         | 0.2%    |
| Iiyama                  | 3         | 0.2%    |
| Vestel Elektronik       | 2         | 0.13%   |
| Unknown                 | 2         | 0.13%   |
| Toshiba                 | 2         | 0.13%   |
| TCL                     | 2         | 0.13%   |
| JDI                     | 2         | 0.13%   |
| HKC                     | 2         | 0.13%   |
| Hitachi                 | 2         | 0.13%   |
| Denver                  | 2         | 0.13%   |
| DENON                   | 2         | 0.13%   |
| ___                     | 1         | 0.07%   |
| Valve                   | 1         | 0.07%   |
| STA                     | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 15        | 0.99%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 14        | 0.93%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 13        | 0.86%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 13        | 0.86%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 10        | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 10        | 0.66%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 10        | 0.66%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 9         | 0.6%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.6%    |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch      | 8         | 0.53%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 8         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 7         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 7         | 0.46%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 7         | 0.46%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.4%    |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 6         | 0.4%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x194mm 15.5-inch        | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 6         | 0.4%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch         | 6         | 0.4%    |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 5         | 0.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.33%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 5         | 0.33%   |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                 | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch        | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 5         | 0.33%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 5         | 0.33%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 4         | 0.26%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 4         | 0.26%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch               | 4         | 0.26%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch  | 4         | 0.26%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 4         | 0.26%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 4         | 0.26%   |
| Samsung Electronics LCD Monitor SDC414D 3456x2160 336x210mm 15.6-inch | 4         | 0.26%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch               | 4         | 0.26%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 4         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 680       | 48.54%  |
| 1366x768 (WXGA)    | 288       | 20.56%  |
| 3840x2160 (4K)     | 64        | 4.57%   |
| 2560x1440 (QHD)    | 58        | 4.14%   |
| 1600x900 (HD+)     | 51        | 3.64%   |
| 1920x1200 (WUXGA)  | 43        | 3.07%   |
| 2560x1600          | 39        | 2.78%   |
| 1440x900 (WXGA+)   | 27        | 1.93%   |
| 2880x1800          | 26        | 1.86%   |
| 1280x800 (WXGA)    | 24        | 1.71%   |
| 3440x1440          | 14        | 1%      |
| 3840x2400          | 10        | 0.71%   |
| 2560x1080          | 10        | 0.71%   |
| 2256x1504          | 6         | 0.43%   |
| 2160x1440          | 6         | 0.43%   |
| 1280x1024 (SXGA)   | 6         | 0.43%   |
| 3200x1800 (QHD+)   | 5         | 0.36%   |
| 3456x2160          | 4         | 0.29%   |
| 3200x2000          | 4         | 0.29%   |
| 1680x1050 (WSXGA+) | 4         | 0.29%   |
| 1360x768           | 4         | 0.29%   |
| 1920x540           | 3         | 0.21%   |
| 800x1280           | 2         | 0.14%   |
| 3840x1100          | 2         | 0.14%   |
| 3840x1080          | 2         | 0.14%   |
| 3072x1920          | 2         | 0.14%   |
| 3000x2000          | 2         | 0.14%   |
| 2304x1440          | 2         | 0.14%   |
| 1920x1280          | 2         | 0.14%   |
| 1280x720 (HD)      | 2         | 0.14%   |
| 3840x1200          | 1         | 0.07%   |
| 3120x2080          | 1         | 0.07%   |
| 2560x1700          | 1         | 0.07%   |
| 1920x515           | 1         | 0.07%   |
| 1600x2560          | 1         | 0.07%   |
| 1600x1200          | 1         | 0.07%   |
| 1400x1050          | 1         | 0.07%   |
| 1280x1080          | 1         | 0.07%   |
| Unknown            | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 605       | 40.5%   |
| 13      | 254       | 17%     |
| 14      | 161       | 10.78%  |
| 17      | 95        | 6.36%   |
| 27      | 56        | 3.75%   |
| 24      | 47        | 3.15%   |
| 23      | 43        | 2.88%   |
| 16      | 36        | 2.41%   |
| 12      | 33        | 2.21%   |
| 21      | 25        | 1.67%   |
| 34      | 21        | 1.41%   |
| 31      | 21        | 1.41%   |
| 11      | 13        | 0.87%   |
| 19      | 11        | 0.74%   |
| Unknown | 10        | 0.67%   |
| 32      | 8         | 0.54%   |
| 84      | 7         | 0.47%   |
| 18      | 7         | 0.47%   |
| 72      | 5         | 0.33%   |
| 35      | 4         | 0.27%   |
| 22      | 4         | 0.27%   |
| 20      | 4         | 0.27%   |
| 48      | 3         | 0.2%    |
| 40      | 3         | 0.2%    |
| 54      | 2         | 0.13%   |
| 49      | 2         | 0.13%   |
| 29      | 2         | 0.13%   |
| 28      | 2         | 0.13%   |
| 60      | 1         | 0.07%   |
| 57      | 1         | 0.07%   |
| 47      | 1         | 0.07%   |
| 43      | 1         | 0.07%   |
| 37      | 1         | 0.07%   |
| 33      | 1         | 0.07%   |
| 26      | 1         | 0.07%   |
| 25      | 1         | 0.07%   |
| 8       | 1         | 0.07%   |
| 7       | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 914       | 61.84%  |
| 201-300     | 175       | 11.84%  |
| 501-600     | 129       | 8.73%   |
| 351-400     | 109       | 7.37%   |
| 401-500     | 46        | 3.11%   |
| 601-700     | 33        | 2.23%   |
| 701-800     | 30        | 2.03%   |
| 1501-2000   | 12        | 0.81%   |
| 1001-1500   | 10        | 0.68%   |
| Unknown     | 10        | 0.68%   |
| 801-900     | 8         | 0.54%   |
| 101-200     | 1         | 0.07%   |
| 1-100       | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1044      | 80.37%  |
| 16/10   | 186       | 14.32%  |
| 21/9    | 26        | 2%      |
| 3/2     | 20        | 1.54%   |
| 5/4     | 7         | 0.54%   |
| 32/9    | 3         | 0.23%   |
| Unknown | 3         | 0.23%   |
| 4/3     | 2         | 0.15%   |
| 3.40    | 2         | 0.15%   |
| 3.73    | 1         | 0.08%   |
| 3.20    | 1         | 0.08%   |
| 0.67    | 1         | 0.08%   |
| 0.63    | 1         | 0.08%   |
| 0.62    | 1         | 0.08%   |
| 0.56    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 606       | 40.64%  |
| 81-90          | 324       | 21.73%  |
| 201-250        | 96        | 6.44%   |
| 71-80          | 87        | 5.84%   |
| 121-130        | 86        | 5.77%   |
| 351-500        | 56        | 3.76%   |
| 301-350        | 56        | 3.76%   |
| 111-120        | 33        | 2.21%   |
| 61-70          | 31        | 2.08%   |
| 151-200        | 22        | 1.48%   |
| More than 1000 | 19        | 1.27%   |
| 251-300        | 18        | 1.21%   |
| 51-60          | 15        | 1.01%   |
| 141-150        | 10        | 0.67%   |
| Unknown        | 10        | 0.67%   |
| 501-1000       | 8         | 0.54%   |
| 131-140        | 7         | 0.47%   |
| 91-100         | 5         | 0.34%   |
| 1-40           | 2         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 664       | 45.51%  |
| 101-120       | 352       | 24.13%  |
| 51-100        | 195       | 13.37%  |
| 161-240       | 158       | 10.83%  |
| More than 240 | 64        | 4.39%   |
| 1-50          | 16        | 1.1%    |
| Unknown       | 10        | 0.69%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 972       | 76.84%  |
| 2     | 224       | 17.71%  |
| 3     | 36        | 2.85%   |
| 0     | 31        | 2.45%   |
| 4     | 2         | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 673       | 34.21%  |
| Intel                                 | 671       | 34.11%  |
| Qualcomm Atheros                      | 236       | 12%     |
| Broadcom                              | 115       | 5.85%   |
| MediaTek                              | 60        | 3.05%   |
| Broadcom Limited                      | 50        | 2.54%   |
| ASIX Electronics                      | 21        | 1.07%   |
| TP-Link                               | 13        | 0.66%   |
| Nvidia                                | 13        | 0.66%   |
| Marvell Technology Group              | 13        | 0.66%   |
| Samsung Electronics                   | 12        | 0.61%   |
| DisplayLink                           | 10        | 0.51%   |
| Dell                                  | 9         | 0.46%   |
| Qualcomm                              | 8         | 0.41%   |
| Ralink                                | 6         | 0.31%   |
| Xiaomi                                | 5         | 0.25%   |
| Ralink Technology                     | 5         | 0.25%   |
| Lenovo                                | 5         | 0.25%   |
| Sierra Wireless                       | 4         | 0.2%    |
| OnePlus Technology (Shenzhen)         | 4         | 0.2%    |
| NetGear                               | 4         | 0.2%    |
| JMicron Technology                    | 4         | 0.2%    |
| Hewlett-Packard                       | 4         | 0.2%    |
| OPPO                                  | 2         | 0.1%    |
| Motorola PCS                          | 2         | 0.1%    |
| Huawei Technologies                   | 2         | 0.1%    |
| Ericsson Business Mobile Networks     | 2         | 0.1%    |
| D-Link                                | 2         | 0.1%    |
| ASUSTek Computer                      | 2         | 0.1%    |
| Apple                                 | 2         | 0.1%    |
| U-Blox                                | 1         | 0.05%   |
| Shenzhen Goodix Technology            | 1         | 0.05%   |
| Qualcomm Atheros Communications       | 1         | 0.05%   |
| Google                                | 1         | 0.05%   |
| Fibocom                               | 1         | 0.05%   |
| Arduino SA                            | 1         | 0.05%   |
| Accton Technology                     | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 430       | 18.57%  |
| Intel Wi-Fi 6 AX200                                               | 86        | 3.71%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 74        | 3.2%    |
| Intel Wi-Fi 6 AX201                                               | 66        | 2.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 2.76%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 55        | 2.38%   |
| Intel Wireless 8265 / 8275                                        | 53        | 2.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 47        | 2.03%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 40        | 1.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 38        | 1.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 38        | 1.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 38        | 1.64%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 36        | 1.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 34        | 1.47%   |
| Intel Wireless 7265                                               | 34        | 1.47%   |
| Intel Wireless 8260                                               | 32        | 1.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 1.38%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 31        | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 29        | 1.25%   |
| Intel Wireless 7260                                               | 29        | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 26        | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 24        | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 0.99%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 22        | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 21        | 0.91%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 21        | 0.91%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 20        | 0.86%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 0.78%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 18        | 0.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 16        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                     | 16        | 0.69%   |
| Intel Wireless-AC 9260                                            | 15        | 0.65%   |
| Realtek Realtek Network controller                                | 14        | 0.6%    |
| Intel Ethernet Connection I217-LM                                 | 14        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.6%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 14        | 0.6%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 13        | 0.56%   |
| Intel Centrino Advanced-N 6235                                    | 13        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 650       | 50.27%  |
| Qualcomm Atheros                      | 204       | 15.78%  |
| Realtek Semiconductor                 | 190       | 14.69%  |
| Broadcom                              | 100       | 7.73%   |
| MediaTek                              | 51        | 3.94%   |
| Broadcom Limited                      | 42        | 3.25%   |
| TP-Link                               | 10        | 0.77%   |
| Dell                                  | 9         | 0.7%    |
| Qualcomm                              | 8         | 0.62%   |
| Ralink                                | 6         | 0.46%   |
| Ralink Technology                     | 5         | 0.39%   |
| Sierra Wireless                       | 4         | 0.31%   |
| NetGear                               | 4         | 0.31%   |
| Hewlett-Packard                       | 2         | 0.15%   |
| D-Link                                | 2         | 0.15%   |
| Qualcomm Atheros Communications       | 1         | 0.08%   |
| Fibocom                               | 1         | 0.08%   |
| ASUSTek Computer                      | 1         | 0.08%   |
| Arduino SA                            | 1         | 0.08%   |
| Accton Technology                     | 1         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.08%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 86        | 6.61%   |
| Intel Wi-Fi 6 AX201                                            | 66        | 5.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 55        | 4.23%   |
| Intel Wireless 8265 / 8275                                     | 53        | 4.07%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 47        | 3.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 38        | 2.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 38        | 2.92%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 38        | 2.92%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 36        | 2.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 34        | 2.61%   |
| Intel Wireless 7265                                            | 34        | 2.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 32        | 2.46%   |
| Intel Wireless 8260                                            | 32        | 2.46%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 31        | 2.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 29        | 2.23%   |
| Intel Wireless 7260                                            | 29        | 2.23%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 26        | 2%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 24        | 1.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 23        | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 22        | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 21        | 1.61%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 21        | 1.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 20        | 1.54%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 18        | 1.38%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 16        | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                  | 16        | 1.23%   |
| Intel Wireless-AC 9260                                         | 15        | 1.15%   |
| Realtek Realtek Network controller                             | 14        | 1.08%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 14        | 1.08%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 13        | 1%      |
| Intel Centrino Advanced-N 6235                                 | 13        | 1%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 11        | 0.85%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 11        | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 9         | 0.69%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 9         | 0.69%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 0.61%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8         | 0.61%   |
| MediaTek WLAN controller                                       | 8         | 0.61%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 8         | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 8         | 0.61%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 591       | 59.82%  |
| Intel                         | 188       | 19.03%  |
| Qualcomm Atheros              | 54        | 5.47%   |
| Broadcom                      | 39        | 3.95%   |
| ASIX Electronics              | 21        | 2.13%   |
| Nvidia                        | 13        | 1.32%   |
| Marvell Technology Group      | 13        | 1.32%   |
| Samsung Electronics           | 12        | 1.21%   |
| DisplayLink                   | 10        | 1.01%   |
| MediaTek                      | 8         | 0.81%   |
| Broadcom Limited              | 8         | 0.81%   |
| Xiaomi                        | 5         | 0.51%   |
| Lenovo                        | 5         | 0.51%   |
| OnePlus Technology (Shenzhen) | 4         | 0.4%    |
| JMicron Technology            | 4         | 0.4%    |
| TP-Link                       | 3         | 0.3%    |
| OPPO                          | 2         | 0.2%    |
| Motorola PCS                  | 2         | 0.2%    |
| Apple                         | 2         | 0.2%    |
| Huawei Technologies           | 1         | 0.1%    |
| Hewlett-Packard               | 1         | 0.1%    |
| Google                        | 1         | 0.1%    |
| ASUSTek Computer              | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 430       | 42.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 74        | 7.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 64        | 6.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 32        | 3.18%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 1.79%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 1.79%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 1.79%   |
| Intel Ethernet Connection I217-LM                                 | 14        | 1.39%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 1.39%   |
| Intel Ethernet Connection I219-LM                                 | 12        | 1.19%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 12        | 1.19%   |
| Nvidia MCP79 Ethernet                                             | 11        | 1.09%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 1%      |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 0.9%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 8         | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 8         | 0.8%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 8         | 0.8%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 0.7%    |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.7%    |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.7%    |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.7%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 7         | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.6%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 6         | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.5%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.5%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 5         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.5%    |
| Intel Ethernet Controller I225-V                                  | 5         | 0.5%    |
| Intel Ethernet Connection I219-V                                  | 5         | 0.5%    |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.5%    |
| Intel Ethernet Connection (6) I219-LM                             | 5         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.5%    |
| Intel Ethernet Connection (16) I219-V                             | 5         | 0.5%    |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.5%    |
| Intel 82577LC Gigabit Network Connection                          | 5         | 0.5%    |
| DisplayLink Dell Universal Dock D6000                             | 5         | 0.5%    |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 5         | 0.5%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 4         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1229      | 56.69%  |
| Ethernet | 930       | 42.9%   |
| Modem    | 6         | 0.28%   |
| Unknown  | 3         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1048      | 79.57%  |
| Ethernet | 269       | 20.43%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 839       | 67.17%  |
| 1     | 391       | 31.31%  |
| 0     | 10        | 0.8%    |
| 3     | 9         | 0.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 890       | 70.58%  |
| Yes  | 371       | 29.42%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 572       | 53.11%  |
| Realtek Semiconductor           | 97        | 9.01%   |
| Qualcomm Atheros Communications | 95        | 8.82%   |
| Apple                           | 75        | 6.96%   |
| IMC Networks                    | 68        | 6.31%   |
| Foxconn / Hon Hai               | 44        | 4.09%   |
| Lite-On Technology              | 38        | 3.53%   |
| Broadcom                        | 30        | 2.79%   |
| Dell                            | 10        | 0.93%   |
| Toshiba                         | 8         | 0.74%   |
| Cambridge Silicon Radio         | 8         | 0.74%   |
| Realtek                         | 7         | 0.65%   |
| Hewlett-Packard                 | 6         | 0.56%   |
| Opticis                         | 3         | 0.28%   |
| Foxconn International           | 3         | 0.28%   |
| Unknown                         | 2         | 0.19%   |
| Taiyo Yuden                     | 2         | 0.19%   |
| Ralink                          | 2         | 0.19%   |
| USI                             | 1         | 0.09%   |
| Ralink Technology               | 1         | 0.09%   |
| Micro Star International        | 1         | 0.09%   |
| MediaTek                        | 1         | 0.09%   |
| Fujitsu                         | 1         | 0.09%   |
| ASUSTek Computer                | 1         | 0.09%   |
| Actions                         | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 155       | 14.38%  |
| Intel AX201 Bluetooth                               | 150       | 13.91%  |
| Intel AX200 Bluetooth                               | 84        | 7.79%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 78        | 7.24%   |
| Realtek Bluetooth Radio                             | 67        | 6.22%   |
| Qualcomm Atheros  Bluetooth Device                  | 54        | 5.01%   |
| Apple Bluetooth Host Controller                     | 39        | 3.62%   |
| Intel Bluetooth Device                              | 38        | 3.53%   |
| Apple Bluetooth USB Host Controller                 | 30        | 2.78%   |
| IMC Networks Wireless_Device                        | 27        | 2.5%    |
| Realtek  Bluetooth 4.2 Adapter                      | 23        | 2.13%   |
| Intel AX210 Bluetooth                               | 23        | 2.13%   |
| Foxconn / Hon Hai Wireless_Device                   | 19        | 1.76%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 16        | 1.48%   |
| IMC Networks Bluetooth Radio                        | 15        | 1.39%   |
| Foxconn / Hon Hai Bluetooth Device                  | 15        | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 14        | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 1.3%    |
| IMC Networks Bluetooth Device                       | 13        | 1.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.93%   |
| Lite-On Wireless_Device                             | 10        | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.74%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 0.74%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 7         | 0.65%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 0.65%   |
| Lite-On Bluetooth Device                            | 7         | 0.65%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 0.65%   |
| Realtek 802.11ac WLAN Adapter                       | 6         | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 5         | 0.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.46%   |
| IMC Networks Bluetooth USB Host Controller          | 5         | 0.46%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 5         | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.46%   |
| Broadcom BCM20702A0                                 | 4         | 0.37%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.37%   |
| Apple Bluetooth HCI                                 | 4         | 0.37%   |
| Toshiba BCM43142A0                                  | 3         | 0.28%   |
| Opticis Bluetooth Radio                             | 3         | 0.28%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 3         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 943       | 57.4%   |
| AMD                                  | 303       | 18.44%  |
| Nvidia                               | 281       | 17.1%   |
| C-Media Electronics                  | 13        | 0.79%   |
| Logitech                             | 11        | 0.67%   |
| GN Netcom                            | 9         | 0.55%   |
| Realtek Semiconductor                | 8         | 0.49%   |
| Hewlett-Packard                      | 7         | 0.43%   |
| Lenovo                               | 6         | 0.37%   |
| Kingston Technology                  | 6         | 0.37%   |
| Generalplus Technology               | 5         | 0.3%    |
| Apple                                | 5         | 0.3%    |
| Texas Instruments                    | 4         | 0.24%   |
| SteelSeries ApS                      | 4         | 0.24%   |
| Sony                                 | 4         | 0.24%   |
| JMTek                                | 4         | 0.24%   |
| Razer USA                            | 3         | 0.18%   |
| Focusrite-Novation                   | 3         | 0.18%   |
| ASUSTek Computer                     | 3         | 0.18%   |
| Plantronics                          | 2         | 0.12%   |
| DSEA A/S                             | 2         | 0.12%   |
| Corsair                              | 2         | 0.12%   |
| Turtle Beach                         | 1         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.06%   |
| TerraTec Electronic                  | 1         | 0.06%   |
| Sennheiser Communications            | 1         | 0.06%   |
| Samson Technologies                  | 1         | 0.06%   |
| Reloop                               | 1         | 0.06%   |
| Pioneer DJ                           | 1         | 0.06%   |
| No brand                             | 1         | 0.06%   |
| Midiplus                             | 1         | 0.06%   |
| iConnectivity                        | 1         | 0.06%   |
| FiiO Electronics Technology          | 1         | 0.06%   |
| CMX Systems                          | 1         | 0.06%   |
| Audio-Technica                       | 1         | 0.06%   |
| Astro Gaming                         | 1         | 0.06%   |
| Antlion Audio                        | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 225       | 11.08%  |
| Intel Sunrise Point-LP HD Audio                                            | 128       | 6.3%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 124       | 6.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 91        | 4.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 79        | 3.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 64        | 3.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 58        | 2.86%   |
| Intel Haswell-ULT HD Audio Controller                                      | 55        | 2.71%   |
| Intel 8 Series HD Audio Controller                                         | 54        | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 54        | 2.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 51        | 2.51%   |
| Intel Broadwell-U Audio Controller                                         | 51        | 2.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 49        | 2.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 48        | 2.36%   |
| Intel Comet Lake PCH cAVS                                                  | 44        | 2.17%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 41        | 2.02%   |
| Nvidia GA106 High Definition Audio Controller                              | 37        | 1.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 35        | 1.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 33        | 1.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 33        | 1.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 33        | 1.62%   |
| Nvidia Audio device                                                        | 31        | 1.53%   |
| Intel Comet Lake PCH-LP cAVS                                               | 30        | 1.48%   |
| Nvidia GA104 High Definition Audio Controller                              | 29        | 1.43%   |
| AMD FCH Azalia Controller                                                  | 29        | 1.43%   |
| Nvidia TU106 High Definition Audio Controller                              | 27        | 1.33%   |
| Intel CM238 HD Audio Controller                                            | 27        | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 21        | 1.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19        | 0.94%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 19        | 0.94%   |
| AMD Kabini HDMI/DP Audio                                                   | 18        | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 17        | 0.84%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 16        | 0.79%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 16        | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                            | 14        | 0.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 14        | 0.69%   |
| Nvidia MCP79 High Definition Audio                                         | 13        | 0.64%   |
| Nvidia GP106 High Definition Audio Controller                              | 13        | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 11        | 0.54%   |
| Nvidia GP104 High Definition Audio Controller                              | 10        | 0.49%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 144       | 31.24%  |
| SK hynix            | 105       | 22.78%  |
| Micron Technology   | 70        | 15.18%  |
| Kingston            | 26        | 5.64%   |
| Crucial             | 22        | 4.77%   |
| Unknown             | 13        | 2.82%   |
| Unknown             | 10        | 2.17%   |
| Neo Forza           | 7         | 1.52%   |
| A-DATA Technology   | 7         | 1.52%   |
| Smart               | 6         | 1.3%    |
| Goldkey             | 6         | 1.3%    |
| Team                | 5         | 1.08%   |
| G.Skill             | 4         | 0.87%   |
| Ramaxel Technology  | 3         | 0.65%   |
| PNY                 | 3         | 0.65%   |
| Nanya Technology    | 3         | 0.65%   |
| GSkill              | 3         | 0.65%   |
| Elpida              | 3         | 0.65%   |
| Corsair             | 3         | 0.65%   |
| Unknown (ABCD)      | 2         | 0.43%   |
| Smart Brazil        | 2         | 0.43%   |
| Gold Key            | 2         | 0.43%   |
| Avant               | 2         | 0.43%   |
| Unknown (8A02)      | 1         | 0.22%   |
| Unknown (09B6)      | 1         | 0.22%   |
| Unknown (09A4)      | 1         | 0.22%   |
| Transcend           | 1         | 0.22%   |
| Timetec             | 1         | 0.22%   |
| Teikon              | 1         | 0.22%   |
| Kllisre             | 1         | 0.22%   |
| CSX                 | 1         | 0.22%   |
| ChangXin Memory     | 1         | 0.22%   |
| Apacer              | 1         | 0.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 10        | 2.07%   |
| Unknown                                                             | 10        | 2.07%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s           | 8         | 1.65%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 8         | 1.65%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 7         | 1.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 7         | 1.45%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s               | 6         | 1.24%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 6         | 1.24%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s                | 6         | 1.24%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 1.03%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 5         | 1.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 5         | 1.03%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 5         | 1.03%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s             | 5         | 1.03%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 5         | 1.03%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 4         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 4         | 0.83%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s              | 4         | 0.83%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 4         | 0.83%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 4         | 0.83%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 4         | 0.83%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.83%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 0.83%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 0.83%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 0.83%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 4         | 0.83%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 4         | 0.83%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 4         | 0.83%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 3         | 0.62%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 3         | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 0.62%   |
| SK hynix RAM H9CCNNNBJTALAR-NVD 4096MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.62%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                        | 3         | 0.62%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.62%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 3         | 0.62%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 3         | 0.62%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s         | 3         | 0.62%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 3         | 0.62%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 3         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 249       | 63.68%  |
| DDR3   | 63        | 16.11%  |
| LPDDR4 | 29        | 7.42%   |
| DDR5   | 17        | 4.35%   |
| LPDDR3 | 15        | 3.84%   |
| LPDDR5 | 12        | 3.07%   |
| SDRAM  | 3         | 0.77%   |
| DDR2   | 3         | 0.77%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 329       | 82.04%  |
| Row Of Chips | 70        | 17.46%  |
| Chip         | 2         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 195       | 46.1%   |
| 4096  | 96        | 22.7%   |
| 16384 | 77        | 18.2%   |
| 2048  | 26        | 6.15%   |
| 32768 | 25        | 5.91%   |
| 1024  | 4         | 0.95%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 146       | 34.76%  |
| 2667  | 83        | 19.76%  |
| 1600  | 42        | 10%     |
| 2400  | 27        | 6.43%   |
| 2133  | 22        | 5.24%   |
| 4267  | 18        | 4.29%   |
| 4800  | 17        | 4.05%   |
| 6400  | 12        | 2.86%   |
| 1334  | 7         | 1.67%   |
| 1333  | 7         | 1.67%   |
| 8400  | 6         | 1.43%   |
| 1067  | 6         | 1.43%   |
| 3266  | 5         | 1.19%   |
| 1867  | 5         | 1.19%   |
| 4266  | 4         | 0.95%   |
| 3733  | 3         | 0.71%   |
| 800   | 3         | 0.71%   |
| 2933  | 2         | 0.48%   |
| 2048  | 2         | 0.48%   |
| 4199  | 1         | 0.24%   |
| 1200  | 1         | 0.24%   |
| 1066  | 1         | 0.24%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 3         | 37.5%   |
| Canon              | 2         | 25%     |
| Xerox              | 1         | 12.5%   |
| ICS Advent         | 1         | 12.5%   |
| Brother Industries | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Xerox B215                      | 1         | 12.5%   |
| ICS Advent Parallel Adapter     | 1         | 12.5%   |
| HP OfficeJet 3830 series        | 1         | 12.5%   |
| HP Ink Tank Wireless 410 series | 1         | 12.5%   |
| HP Color LaserJet CP2025dn      | 1         | 12.5%   |
| Canon PIXMA MX920 Series        | 1         | 12.5%   |
| Canon E400 series               | 1         | 12.5%   |
| Brother HL-L2370DW series       | 1         | 12.5%   |

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
| Chicony Electronics                    | 251       | 22.25%  |
| Acer                                   | 135       | 11.97%  |
| IMC Networks                           | 118       | 10.46%  |
| Microdia                               | 116       | 10.28%  |
| Realtek Semiconductor                  | 91        | 8.07%   |
| Quanta                                 | 72        | 6.38%   |
| Sunplus Innovation Technology          | 53        | 4.7%    |
| Apple                                  | 52        | 4.61%   |
| Cheng Uei Precision Industry (Foxlink) | 35        | 3.1%    |
| Syntek                                 | 26        | 2.3%    |
| Luxvisions Innotech Limited            | 26        | 2.3%    |
| Lite-On Technology                     | 23        | 2.04%   |
| Suyin                                  | 22        | 1.95%   |
| Logitech                               | 15        | 1.33%   |
| Sonix Technology                       | 14        | 1.24%   |
| Silicon Motion                         | 12        | 1.06%   |
| SunplusIT                              | 8         | 0.71%   |
| Samsung Electronics                    | 7         | 0.62%   |
| Z-Star Microelectronics                | 5         | 0.44%   |
| Ricoh                                  | 4         | 0.35%   |
| Microsoft                              | 4         | 0.35%   |
| Alcor Micro                            | 4         | 0.35%   |
| Razer USA                              | 3         | 0.27%   |
| Primax Electronics                     | 3         | 0.27%   |
| Generalplus Technology                 | 3         | 0.27%   |
| DLEQNA19IFK6G2                         | 3         | 0.27%   |
| SJ-180517-N                            | 2         | 0.18%   |
| Lenovo                                 | 2         | 0.18%   |
| HRY                                    | 2         | 0.18%   |
| Unknown                                | 1         | 0.09%   |
| Trust                                  | 1         | 0.09%   |
| Tobii Technology AB                    | 1         | 0.09%   |
| Pixart Imaging                         | 1         | 0.09%   |
| Oculus VR                              | 1         | 0.09%   |
| MacroSilicon                           | 1         | 0.09%   |
| LG Electronics                         | 1         | 0.09%   |
| KYE Systems (Mouse Systems)            | 1         | 0.09%   |
| Intel                                  | 1         | 0.09%   |
| Importek                               | 1         | 0.09%   |
| icSpring                               | 1         | 0.09%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 60        | 5.29%   |
| Chicony Integrated Camera                        | 54        | 4.76%   |
| IMC Networks USB2.0 HD UVC WebCam                | 43        | 3.79%   |
| Realtek Integrated_Webcam_HD                     | 39        | 3.44%   |
| IMC Networks Integrated Camera                   | 29        | 2.56%   |
| Chicony HD Webcam                                | 27        | 2.38%   |
| Acer BisonCam,NB Pro                             | 27        | 2.38%   |
| Acer Integrated Camera                           | 26        | 2.29%   |
| Chicony USB2.0 Camera                            | 23        | 2.03%   |
| Syntek Integrated Camera                         | 21        | 1.85%   |
| Acer HD Webcam                                   | 21        | 1.85%   |
| Quanta HD User Facing                            | 18        | 1.59%   |
| Apple Built-in iSight                            | 17        | 1.5%    |
| Sunplus Integrated_Webcam_HD                     | 16        | 1.41%   |
| Apple iPhone 5/5C/5S/6/SE                        | 14        | 1.23%   |
| Chicony HD User Facing                           | 13        | 1.15%   |
| Apple FaceTime HD Camera                         | 13        | 1.15%   |
| Microdia Integrated Webcam                       | 12        | 1.06%   |
| Sonix USB2.0 HD UVC WebCam                       | 11        | 0.97%   |
| Luxvisions Innotech Limited HP HD Camera         | 11        | 0.97%   |
| Chicony USB2.0 VGA UVC WebCam                    | 11        | 0.97%   |
| Quanta HP HD Camera                              | 10        | 0.88%   |
| Lite-On Integrated Camera                        | 9         | 0.79%   |
| Chicony TOSHIBA Web Camera - HD                  | 9         | 0.79%   |
| Chicony Integrated Camera (1280x720@30)          | 9         | 0.79%   |
| Chicony HP HD Camera                             | 9         | 0.79%   |
| Acer SunplusIT Integrated Camera                 | 9         | 0.79%   |
| Acer Lenovo EasyCamera                           | 9         | 0.79%   |
| Realtek Integrated Webcam                        | 8         | 0.71%   |
| Microdia Integrated Webcam HD                    | 8         | 0.71%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 8         | 0.71%   |
| Chicony HP TrueVision HD Camera                  | 8         | 0.71%   |
| Samsung Galaxy A5 (MTP)                          | 7         | 0.62%   |
| Quanta HP TrueVision HD Camera                   | 7         | 0.62%   |
| Quanta ACER HD User Facing                       | 7         | 0.62%   |
| Chicony USB 2.0 Camera                           | 7         | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera | 7         | 0.62%   |
| Acer BisonCam, NB Pro                            | 7         | 0.62%   |
| Suyin 1.3M HD WebCam                             | 6         | 0.53%   |
| Realtek USB2.0 HD UVC WebCam                     | 6         | 0.53%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 75        | 35.05%  |
| Validity Sensors                   | 55        | 25.7%   |
| Shenzhen Goodix Technology         | 42        | 19.63%  |
| LighTuning Technology              | 10        | 4.67%   |
| Elan Microelectronics              | 10        | 4.67%   |
| Upek                               | 8         | 3.74%   |
| AuthenTec                          | 6         | 2.8%    |
| Realtek USB2.0 Finger Print Bridge | 3         | 1.4%    |
| Focal-systems.Corp                 | 3         | 1.4%    |
| HOLTEK                             | 2         | 0.93%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 26        | 12.15%  |
| Shenzhen Goodix  Fingerprint Device                                        | 22        | 10.28%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 9.81%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 6.54%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 11        | 5.14%   |
| Shenzhen Goodix FingerPrint                                                | 11        | 5.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 4.67%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 4.21%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 3.27%   |
| Elan ELAN:ARM-M4                                                           | 7         | 3.27%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 2.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 2.8%    |
| Synaptics WBDI Device                                                      | 5         | 2.34%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 2.34%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.87%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.87%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.87%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 1.87%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 1.4%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.4%    |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 1.4%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.4%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 3         | 1.4%    |
| Elan ELAN:Fingerprint                                                      | 3         | 1.4%    |
| Validity Sensors VFS491                                                    | 2         | 0.93%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.93%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.93%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.93%   |
| HOLTEK FocalTech Fingerprint Device                                        | 2         | 0.93%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 0.93%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.93%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.47%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.47%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.47%   |
| Synaptics  WBDI                                                            | 1         | 0.47%   |
| AuthenTec AES2810                                                          | 1         | 0.47%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 42        | 52.5%   |
| Alcor Micro | 22        | 27.5%   |
| O2 Micro    | 6         | 7.5%    |
| Upek        | 4         | 5%      |
| Lenovo      | 4         | 5%      |
| OmniKey     | 1         | 1.25%   |
| Clay Logic  | 1         | 1.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 22        | 27.5%   |
| Broadcom 5880                                                                | 13        | 16.25%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 12.5%   |
| Broadcom 58200                                                               | 10        | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 11.25%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 6.25%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5%      |
| Lenovo Integrated Smart Card Reader                                          | 4         | 5%      |
| OmniKey CardMan 4321                                                         | 1         | 1.25%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.25%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 761       | 60.25%  |
| 1     | 399       | 31.59%  |
| 2     | 86        | 6.81%   |
| 3     | 16        | 1.27%   |
| 4     | 1         | 0.08%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 204       | 33.72%  |
| Multimedia controller    | 108       | 17.85%  |
| Chipcard                 | 75        | 12.4%   |
| Graphics card            | 65        | 10.74%  |
| Net/wireless             | 60        | 9.92%   |
| Bluetooth                | 28        | 4.63%   |
| Camera                   | 23        | 3.8%    |
| Sound                    | 8         | 1.32%   |
| Storage                  | 6         | 0.99%   |
| Network                  | 6         | 0.99%   |
| Net/ethernet             | 6         | 0.99%   |
| Communication controller | 5         | 0.83%   |
| Card reader              | 5         | 0.83%   |
| Modem                    | 4         | 0.66%   |
| Storage/ide              | 2         | 0.33%   |

