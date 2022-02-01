Fedora 35 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 35.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Precision 5530              | [3bb85a7897](https://linux-hardware.org/?probe=3bb85a7897) | Jan 31, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [b7796bb104](https://linux-hardware.org/?probe=b7796bb104) | Jan 31, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [8efcb72970](https://linux-hardware.org/?probe=8efcb72970) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [316ea97198](https://linux-hardware.org/?probe=316ea97198) | Jan 31, 2022 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [940c2e990d](https://linux-hardware.org/?probe=940c2e990d) | Jan 31, 2022 |
| Lenovo        | IdeaPad Z500 20202          | [ebe757d792](https://linux-hardware.org/?probe=ebe757d792) | Jan 30, 2022 |
| Dell          | Latitude 7490               | [d3a6ac321f](https://linux-hardware.org/?probe=d3a6ac321f) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N2000LFR    | [0c7293a8ec](https://linux-hardware.org/?probe=0c7293a8ec) | Jan 30, 2022 |
| Lenovo        | ThinkPad T420 4180F65       | [23a97a1da0](https://linux-hardware.org/?probe=23a97a1da0) | Jan 30, 2022 |
| Apple         | MacBookPro14,1              | [88eae6cdfb](https://linux-hardware.org/?probe=88eae6cdfb) | Jan 30, 2022 |
| Apple         | MacBookPro14,1              | [d8040d8fc4](https://linux-hardware.org/?probe=d8040d8fc4) | Jan 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c1494af863](https://linux-hardware.org/?probe=c1494af863) | Jan 30, 2022 |
| Lenovo        | ThinkPad T490 20N20009RT    | [538c4fb88c](https://linux-hardware.org/?probe=538c4fb88c) | Jan 30, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | [209156e57d](https://linux-hardware.org/?probe=209156e57d) | Jan 29, 2022 |
| Lenovo        | ThinkPad E570 20H500B4MH    | [2f9a17c907](https://linux-hardware.org/?probe=2f9a17c907) | Jan 29, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [e06431af49](https://linux-hardware.org/?probe=e06431af49) | Jan 29, 2022 |
| Apple         | MacBookAir6,2               | [2440be23b6](https://linux-hardware.org/?probe=2440be23b6) | Jan 29, 2022 |
| HP            | ZBook 17 G2                 | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4a98af8b6c](https://linux-hardware.org/?probe=4a98af8b6c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 100-14IBD 80RK      | [e6af97e09c](https://linux-hardware.org/?probe=e6af97e09c) | Jan 29, 2022 |
| Dell          | Latitude 5511               | [94f621a74b](https://linux-hardware.org/?probe=94f621a74b) | Jan 29, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [3d321c7afd](https://linux-hardware.org/?probe=3d321c7afd) | Jan 28, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [dd9909e9f4](https://linux-hardware.org/?probe=dd9909e9f4) | Jan 28, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [c573633ba7](https://linux-hardware.org/?probe=c573633ba7) | Jan 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [bab2021d07](https://linux-hardware.org/?probe=bab2021d07) | Jan 28, 2022 |
| ASUSTek       | X510UNR                     | [64f7ad2ba1](https://linux-hardware.org/?probe=64f7ad2ba1) | Jan 27, 2022 |
| Toshiba       | Satellite C660              | [8609aaadb3](https://linux-hardware.org/?probe=8609aaadb3) | Jan 27, 2022 |
| Apple         | MacBookPro9,2               | [d112bf0361](https://linux-hardware.org/?probe=d112bf0361) | Jan 27, 2022 |
| Mediacom      | GTZS                        | [10a0d977b0](https://linux-hardware.org/?probe=10a0d977b0) | Jan 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f7633506c3](https://linux-hardware.org/?probe=f7633506c3) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b930fcaa84](https://linux-hardware.org/?probe=b930fcaa84) | Jan 26, 2022 |
| Dell          | XPS 13 7390                 | [95d6e59e28](https://linux-hardware.org/?probe=95d6e59e28) | Jan 26, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [738074142b](https://linux-hardware.org/?probe=738074142b) | Jan 26, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [1bd39d2b68](https://linux-hardware.org/?probe=1bd39d2b68) | Jan 26, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [9613005856](https://linux-hardware.org/?probe=9613005856) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [36a39bf7eb](https://linux-hardware.org/?probe=36a39bf7eb) | Jan 26, 2022 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | [9d12ae4f9a](https://linux-hardware.org/?probe=9d12ae4f9a) | Jan 26, 2022 |
| Acer          | Nitro AN515-52              | [e9f06efa7a](https://linux-hardware.org/?probe=e9f06efa7a) | Jan 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [041c78217d](https://linux-hardware.org/?probe=041c78217d) | Jan 26, 2022 |
| Dell          | Precision 5510              | [511eeac9a0](https://linux-hardware.org/?probe=511eeac9a0) | Jan 25, 2022 |
| Dell          | Latitude E7470              | [c47b0efb73](https://linux-hardware.org/?probe=c47b0efb73) | Jan 25, 2022 |
| HUAWEI        | KLVL-WXX9                   | [5846d2031f](https://linux-hardware.org/?probe=5846d2031f) | Jan 25, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [c7fbcbcd07](https://linux-hardware.org/?probe=c7fbcbcd07) | Jan 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [f36cdb65e7](https://linux-hardware.org/?probe=f36cdb65e7) | Jan 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [e9c2ec480a](https://linux-hardware.org/?probe=e9c2ec480a) | Jan 24, 2022 |
| Acer          | Nitro AN515-45              | [34568da477](https://linux-hardware.org/?probe=34568da477) | Jan 23, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [d6ea0ad749](https://linux-hardware.org/?probe=d6ea0ad749) | Jan 23, 2022 |
| Acer          | Nitro AN515-45              | [1cb9ebbbd4](https://linux-hardware.org/?probe=1cb9ebbbd4) | Jan 23, 2022 |
| HP            | Laptop 15s-eq2xxx           | [e10bf3d056](https://linux-hardware.org/?probe=e10bf3d056) | Jan 23, 2022 |
| SCHNEIDER     | SCL141CTP                   | [ff14e3fa97](https://linux-hardware.org/?probe=ff14e3fa97) | Jan 23, 2022 |
| Apple         | MacBookPro14,1              | [783456509a](https://linux-hardware.org/?probe=783456509a) | Jan 22, 2022 |
| HP            | ProBook 470 G5              | [6610c7d6e1](https://linux-hardware.org/?probe=6610c7d6e1) | Jan 22, 2022 |
| Dell          | Inspiron N5110              | [3253470667](https://linux-hardware.org/?probe=3253470667) | Jan 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [427ce82d40](https://linux-hardware.org/?probe=427ce82d40) | Jan 22, 2022 |
| Acer          | Aspire ES1-111M             | [02368f5bb1](https://linux-hardware.org/?probe=02368f5bb1) | Jan 22, 2022 |
| HP            | ENVY Laptop 15-ep0xxx       | [2c0f007811](https://linux-hardware.org/?probe=2c0f007811) | Jan 22, 2022 |
| HP            | EliteBook 840 G3            | [4ef203e4a1](https://linux-hardware.org/?probe=4ef203e4a1) | Jan 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [636e98e6e5](https://linux-hardware.org/?probe=636e98e6e5) | Jan 21, 2022 |
| Dell          | XPS 13 9350                 | [485c5e0968](https://linux-hardware.org/?probe=485c5e0968) | Jan 21, 2022 |
| Notebook      | NH55RGQ                     | [92e8102b7d](https://linux-hardware.org/?probe=92e8102b7d) | Jan 21, 2022 |
| Dell          | Latitude E6530              | [bf71e70abb](https://linux-hardware.org/?probe=bf71e70abb) | Jan 21, 2022 |
| Dell          | Inspiron 7591               | [2f1c294587](https://linux-hardware.org/?probe=2f1c294587) | Jan 21, 2022 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [c63c055197](https://linux-hardware.org/?probe=c63c055197) | Jan 21, 2022 |
| HP            | Laptop 15s-fq2xxx           | [172a8a48ad](https://linux-hardware.org/?probe=172a8a48ad) | Jan 21, 2022 |
| Acer          | Aspire A315-41G             | [03a8c77758](https://linux-hardware.org/?probe=03a8c77758) | Jan 20, 2022 |
| Acer          | Aspire A315-41G             | [df698a1427](https://linux-hardware.org/?probe=df698a1427) | Jan 20, 2022 |
| Lenovo        | B490 37722QP                | [6b32b6b8ef](https://linux-hardware.org/?probe=6b32b6b8ef) | Jan 20, 2022 |
| HP            | Compaq 6710b (RM405UT#AB... | [0ae4377d83](https://linux-hardware.org/?probe=0ae4377d83) | Jan 19, 2022 |
| Acer          | Aspire E5-573G              | [30829ce42e](https://linux-hardware.org/?probe=30829ce42e) | Jan 19, 2022 |
| HP            | Compaq 6710b (RM405UT#AB... | [1a128aada0](https://linux-hardware.org/?probe=1a128aada0) | Jan 19, 2022 |
| Positivo      | H14BU08                     | [8fb0d7e730](https://linux-hardware.org/?probe=8fb0d7e730) | Jan 19, 2022 |
| Acer          | Swift SF314-42              | [a2e70fe7b1](https://linux-hardware.org/?probe=a2e70fe7b1) | Jan 19, 2022 |
| HP            | Pavilion Notebook           | [533f74b810](https://linux-hardware.org/?probe=533f74b810) | Jan 19, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [2407b5f5bb](https://linux-hardware.org/?probe=2407b5f5bb) | Jan 19, 2022 |
| Dell          | Latitude E6530              | [8559d4a5b0](https://linux-hardware.org/?probe=8559d4a5b0) | Jan 19, 2022 |
| Lenovo        | B490 37722QP                | [3113fb2078](https://linux-hardware.org/?probe=3113fb2078) | Jan 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS1S800    | [a168ef0aa5](https://linux-hardware.org/?probe=a168ef0aa5) | Jan 18, 2022 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [738f12d2e4](https://linux-hardware.org/?probe=738f12d2e4) | Jan 17, 2022 |
| Acer          | Predator PH315-51           | [d6edc6139f](https://linux-hardware.org/?probe=d6edc6139f) | Jan 17, 2022 |
| Jumper        | EZbook                      | [6c949f1929](https://linux-hardware.org/?probe=6c949f1929) | Jan 17, 2022 |
| HP            | ProBook 650 G1              | [8d78cc6770](https://linux-hardware.org/?probe=8d78cc6770) | Jan 16, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| Notebook      | NS50MU                      | [8527a3e637](https://linux-hardware.org/?probe=8527a3e637) | Jan 16, 2022 |
| Lenovo        | ThinkPad T410 2522PT3       | [a61f1b9d56](https://linux-hardware.org/?probe=a61f1b9d56) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | [0c41cd2cd0](https://linux-hardware.org/?probe=0c41cd2cd0) | Jan 16, 2022 |
| HP            | Pavilion 11 x360 PC         | [750744f996](https://linux-hardware.org/?probe=750744f996) | Jan 16, 2022 |
| Acer          | Swift SF114-34              | [2098bc3881](https://linux-hardware.org/?probe=2098bc3881) | Jan 16, 2022 |
| HP            | ProBook 650 G1              | [829a2b8221](https://linux-hardware.org/?probe=829a2b8221) | Jan 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [779202413e](https://linux-hardware.org/?probe=779202413e) | Jan 15, 2022 |
| Dell          | Latitude 5480               | [6e363cb43c](https://linux-hardware.org/?probe=6e363cb43c) | Jan 15, 2022 |
| HP            | 15                          | [65d1bd3651](https://linux-hardware.org/?probe=65d1bd3651) | Jan 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [350fb6b638](https://linux-hardware.org/?probe=350fb6b638) | Jan 14, 2022 |
| Dell          | XPS 13 9310                 | [f695de13bf](https://linux-hardware.org/?probe=f695de13bf) | Jan 14, 2022 |
| Dell          | Inspiron M5010              | [21dddfe6a8](https://linux-hardware.org/?probe=21dddfe6a8) | Jan 14, 2022 |
| Apple         | MacBookPro11,3              | [0fbef723d5](https://linux-hardware.org/?probe=0fbef723d5) | Jan 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b2ac4f1622](https://linux-hardware.org/?probe=b2ac4f1622) | Jan 13, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [ee8a872afd](https://linux-hardware.org/?probe=ee8a872afd) | Jan 13, 2022 |
| Lenovo        | ThinkPad T440p 20AWS2CH0... | [7f440733c2](https://linux-hardware.org/?probe=7f440733c2) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | [e9f23e9f5f](https://linux-hardware.org/?probe=e9f23e9f5f) | Jan 13, 2022 |
| Apple         | MacBook6,1                  | [85d81f357a](https://linux-hardware.org/?probe=85d81f357a) | Jan 13, 2022 |
| Lenovo        | ThinkPad T430u 3351CTO      | [41f9777fcf](https://linux-hardware.org/?probe=41f9777fcf) | Jan 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [45d63385d2](https://linux-hardware.org/?probe=45d63385d2) | Jan 12, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [9fa645342b](https://linux-hardware.org/?probe=9fa645342b) | Jan 12, 2022 |
| Lenovo        | ThinkPad E15 20RD0015PG     | [008fd40914](https://linux-hardware.org/?probe=008fd40914) | Jan 11, 2022 |
| Dell          | XPS 13 7390                 | [10dea3ac81](https://linux-hardware.org/?probe=10dea3ac81) | Jan 11, 2022 |
| Lenovo        | IdeaPad Y470 20090          | [29ff376953](https://linux-hardware.org/?probe=29ff376953) | Jan 11, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [34bf588c0b](https://linux-hardware.org/?probe=34bf588c0b) | Jan 11, 2022 |
| Dell          | Venue 10 Pro 5055           | [22d084e747](https://linux-hardware.org/?probe=22d084e747) | Jan 11, 2022 |
| Lenovo        | IdeaPad S540-15IWL          | [63c5a7136b](https://linux-hardware.org/?probe=63c5a7136b) | Jan 11, 2022 |
| HP            | EliteBook 820 G1            | [37dd78dd6e](https://linux-hardware.org/?probe=37dd78dd6e) | Jan 11, 2022 |
| Lenovo        | ThinkPad T530 239265U       | [5aba32fde1](https://linux-hardware.org/?probe=5aba32fde1) | Jan 11, 2022 |
| Toshiba       | Satellite L855              | [5668d7e463](https://linux-hardware.org/?probe=5668d7e463) | Jan 10, 2022 |
| Toshiba       | Satellite L855              | [f14ba2d184](https://linux-hardware.org/?probe=f14ba2d184) | Jan 10, 2022 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | [b6b9155c53](https://linux-hardware.org/?probe=b6b9155c53) | Jan 10, 2022 |
| HP            | ZBook Fury 15 G7 Mobile ... | [62bf8bc805](https://linux-hardware.org/?probe=62bf8bc805) | Jan 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [72db511d09](https://linux-hardware.org/?probe=72db511d09) | Jan 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | [2fa4c0880f](https://linux-hardware.org/?probe=2fa4c0880f) | Jan 09, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [6b6c84515a](https://linux-hardware.org/?probe=6b6c84515a) | Jan 09, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | [b9812a839e](https://linux-hardware.org/?probe=b9812a839e) | Jan 09, 2022 |
| Toshiba       | Satellite C55-A-1NU         | [208f411c99](https://linux-hardware.org/?probe=208f411c99) | Jan 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [dc436bb38c](https://linux-hardware.org/?probe=dc436bb38c) | Jan 08, 2022 |
| Dell          | XPS 13 9310                 | [e0dfa537f4](https://linux-hardware.org/?probe=e0dfa537f4) | Jan 08, 2022 |
| Notebook      | P15SM                       | [3b7c794008](https://linux-hardware.org/?probe=3b7c794008) | Jan 08, 2022 |
| Dell          | Precision 3551              | [73d2d759ba](https://linux-hardware.org/?probe=73d2d759ba) | Jan 07, 2022 |
| Dell          | XPS 13 9310                 | [aa1ce4d9ca](https://linux-hardware.org/?probe=aa1ce4d9ca) | Jan 07, 2022 |
| Dell          | Precision 5510              | [7a763a42bb](https://linux-hardware.org/?probe=7a763a42bb) | Jan 07, 2022 |
| Toshiba       | Satellite L755              | [df6cc34c45](https://linux-hardware.org/?probe=df6cc34c45) | Jan 07, 2022 |
| Razer         | Book 13 - RZ09-0357         | [148a68191d](https://linux-hardware.org/?probe=148a68191d) | Jan 06, 2022 |
| Apple         | MacBookPro14,1              | [a37ac164fb](https://linux-hardware.org/?probe=a37ac164fb) | Jan 06, 2022 |
| Apple         | MacBookPro14,1              | [51930e8d89](https://linux-hardware.org/?probe=51930e8d89) | Jan 06, 2022 |
| HUAWEI        | MACHD-WXX9                  | [6c5e2e7851](https://linux-hardware.org/?probe=6c5e2e7851) | Jan 06, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [cafe68988e](https://linux-hardware.org/?probe=cafe68988e) | Jan 06, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [8d8227634a](https://linux-hardware.org/?probe=8d8227634a) | Jan 06, 2022 |
| Panasonic     | CF-195FYCALM                | [19ad0002e5](https://linux-hardware.org/?probe=19ad0002e5) | Jan 06, 2022 |
| HP            | Laptop 15s-eq2xxx           | [527c2f975b](https://linux-hardware.org/?probe=527c2f975b) | Jan 05, 2022 |
| Samsung       | 550XDA                      | [1bdf544285](https://linux-hardware.org/?probe=1bdf544285) | Jan 05, 2022 |
| Lenovo        | ThinkPad T490 20N3S2NJ00    | [e9170a81fe](https://linux-hardware.org/?probe=e9170a81fe) | Jan 05, 2022 |
| Dell          | Latitude E6520              | [f9c32b0bee](https://linux-hardware.org/?probe=f9c32b0bee) | Jan 05, 2022 |
| Dell          | Latitude E7440              | [c8811522dd](https://linux-hardware.org/?probe=c8811522dd) | Jan 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [270443c029](https://linux-hardware.org/?probe=270443c029) | Jan 05, 2022 |
| Sony          | VPCEB3PGX                   | [b97121f86e](https://linux-hardware.org/?probe=b97121f86e) | Jan 05, 2022 |
| Sony          | VPCEB3PGX                   | [9fa953475a](https://linux-hardware.org/?probe=9fa953475a) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | [3a0d2d3754](https://linux-hardware.org/?probe=3a0d2d3754) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | [4516e6113b](https://linux-hardware.org/?probe=4516e6113b) | Jan 05, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8d492fa1d4](https://linux-hardware.org/?probe=8d492fa1d4) | Jan 05, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [56a85d54e4](https://linux-hardware.org/?probe=56a85d54e4) | Jan 04, 2022 |
| Dell          | Latitude E5550              | [8956b15ec8](https://linux-hardware.org/?probe=8956b15ec8) | Jan 04, 2022 |
| Acer          | Swift SF114-34              | [3d15bf4d48](https://linux-hardware.org/?probe=3d15bf4d48) | Jan 04, 2022 |
| Acer          | Extensa 2540                | [c3587d4c57](https://linux-hardware.org/?probe=c3587d4c57) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | [9ac42b2131](https://linux-hardware.org/?probe=9ac42b2131) | Jan 04, 2022 |
| Acer          | Extensa 2540                | [0a39d6fe8c](https://linux-hardware.org/?probe=0a39d6fe8c) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | [e8bc9392ff](https://linux-hardware.org/?probe=e8bc9392ff) | Jan 04, 2022 |
| Dell          | Latitude 3470               | [9e4742c283](https://linux-hardware.org/?probe=9e4742c283) | Jan 04, 2022 |
| Dell          | Inspiron 7591               | [4044cf11d2](https://linux-hardware.org/?probe=4044cf11d2) | Jan 04, 2022 |
| Dell          | Inspiron 5402               | [3cae008c9d](https://linux-hardware.org/?probe=3cae008c9d) | Jan 04, 2022 |
| Lenovo        | Yoga 2 Pro 20266            | [d5e7352413](https://linux-hardware.org/?probe=d5e7352413) | Jan 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7f5e49e07a](https://linux-hardware.org/?probe=7f5e49e07a) | Jan 04, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [8cd52a2f8f](https://linux-hardware.org/?probe=8cd52a2f8f) | Jan 03, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [3953d7ae46](https://linux-hardware.org/?probe=3953d7ae46) | Jan 03, 2022 |
| Dell          | XPS 15 7590                 | [b661a2cdf0](https://linux-hardware.org/?probe=b661a2cdf0) | Jan 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [60514a96e4](https://linux-hardware.org/?probe=60514a96e4) | Jan 02, 2022 |
| ASUSTek       | X542URR                     | [8af11eb0f1](https://linux-hardware.org/?probe=8af11eb0f1) | Jan 02, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [0692c6e121](https://linux-hardware.org/?probe=0692c6e121) | Jan 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | [3bfe8cb49e](https://linux-hardware.org/?probe=3bfe8cb49e) | Jan 01, 2022 |
| Dell          | Latitude E5570              | [34af93663b](https://linux-hardware.org/?probe=34af93663b) | Dec 31, 2021 |
| Google        | Coral                       | [23a0352176](https://linux-hardware.org/?probe=23a0352176) | Dec 31, 2021 |
| ASUSTek       | TP300LD                     | [13e63153f1](https://linux-hardware.org/?probe=13e63153f1) | Dec 31, 2021 |
| Dell          | XPS 13 9380                 | [cd66e486be](https://linux-hardware.org/?probe=cd66e486be) | Dec 31, 2021 |
| Apple         | MacBookPro8,2               | [298d5a0323](https://linux-hardware.org/?probe=298d5a0323) | Dec 31, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9d60e196d4](https://linux-hardware.org/?probe=9d60e196d4) | Dec 31, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | [c6dbec8e70](https://linux-hardware.org/?probe=c6dbec8e70) | Dec 31, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [c1eeaec01b](https://linux-hardware.org/?probe=c1eeaec01b) | Dec 30, 2021 |
| Google        | Chell                       | [9a2a4a03ed](https://linux-hardware.org/?probe=9a2a4a03ed) | Dec 30, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [afb7fa66f5](https://linux-hardware.org/?probe=afb7fa66f5) | Dec 30, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [bfd79da0e0](https://linux-hardware.org/?probe=bfd79da0e0) | Dec 30, 2021 |
| Dell          | Inspiron 3521               | [af800e1071](https://linux-hardware.org/?probe=af800e1071) | Dec 29, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | [c3497fe5bd](https://linux-hardware.org/?probe=c3497fe5bd) | Dec 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [4dfe6a5b8c](https://linux-hardware.org/?probe=4dfe6a5b8c) | Dec 29, 2021 |
| Dell          | Inspiron 7559               | [12ba9454e7](https://linux-hardware.org/?probe=12ba9454e7) | Dec 29, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [c539559392](https://linux-hardware.org/?probe=c539559392) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | [9ba0058839](https://linux-hardware.org/?probe=9ba0058839) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | [dbcf70aced](https://linux-hardware.org/?probe=dbcf70aced) | Dec 29, 2021 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [41b463b6c4](https://linux-hardware.org/?probe=41b463b6c4) | Dec 28, 2021 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [433a512192](https://linux-hardware.org/?probe=433a512192) | Dec 28, 2021 |
| Lenovo        | ThinkPad E480 20KN001QPB    | [0615d7a112](https://linux-hardware.org/?probe=0615d7a112) | Dec 28, 2021 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [bea75ed7d5](https://linux-hardware.org/?probe=bea75ed7d5) | Dec 27, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [cc15a65a54](https://linux-hardware.org/?probe=cc15a65a54) | Dec 27, 2021 |
| Toshiba       | Satellite L12-C-104         | [fae8f8e1f9](https://linux-hardware.org/?probe=fae8f8e1f9) | Dec 27, 2021 |
| HUAWEI        | HVY-WXX9                    | [23460afe38](https://linux-hardware.org/?probe=23460afe38) | Dec 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [23db048750](https://linux-hardware.org/?probe=23db048750) | Dec 27, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [707835b4ff](https://linux-hardware.org/?probe=707835b4ff) | Dec 27, 2021 |
| HP            | Laptop 15s-eq0xxx           | [f255947b6f](https://linux-hardware.org/?probe=f255947b6f) | Dec 27, 2021 |
| Dell          | XPS 13 7390                 | [572bbe8d7b](https://linux-hardware.org/?probe=572bbe8d7b) | Dec 27, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [86651ee07a](https://linux-hardware.org/?probe=86651ee07a) | Dec 26, 2021 |
| Lenovo        | Ducati 5 82ES               | [61dd257cc7](https://linux-hardware.org/?probe=61dd257cc7) | Dec 26, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [56c0a83ab8](https://linux-hardware.org/?probe=56c0a83ab8) | Dec 26, 2021 |
| MSI           | Alpha 15 B5EEK              | [e076af5bf8](https://linux-hardware.org/?probe=e076af5bf8) | Dec 26, 2021 |
| HP            | 2000                        | [e3408eb743](https://linux-hardware.org/?probe=e3408eb743) | Dec 26, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1e8ce2ec6d](https://linux-hardware.org/?probe=1e8ce2ec6d) | Dec 25, 2021 |
| Dell          | Inspiron 5558               | [58e49e7f72](https://linux-hardware.org/?probe=58e49e7f72) | Dec 25, 2021 |
| Dell          | Latitude 7410               | [71a96bfc8f](https://linux-hardware.org/?probe=71a96bfc8f) | Dec 25, 2021 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [6fe369b6b7](https://linux-hardware.org/?probe=6fe369b6b7) | Dec 25, 2021 |
| Cube          | i18-L                       | [6770cf2a44](https://linux-hardware.org/?probe=6770cf2a44) | Dec 24, 2021 |
| Lenovo        | V470 439627U                | [7c44d560dc](https://linux-hardware.org/?probe=7c44d560dc) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [a02655b4b8](https://linux-hardware.org/?probe=a02655b4b8) | Dec 24, 2021 |
| HP            | EliteBook 2570p             | [6e08796257](https://linux-hardware.org/?probe=6e08796257) | Dec 24, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [44dd4eee41](https://linux-hardware.org/?probe=44dd4eee41) | Dec 24, 2021 |
| HP            | Laptop 14-dk1xxx            | [ab7902b875](https://linux-hardware.org/?probe=ab7902b875) | Dec 24, 2021 |
| LDLC          | Mercure MH                  | [ff094fa4f3](https://linux-hardware.org/?probe=ff094fa4f3) | Dec 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS2B000    | [abba53c091](https://linux-hardware.org/?probe=abba53c091) | Dec 23, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1962ddfdb4](https://linux-hardware.org/?probe=1962ddfdb4) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| HP            | 250 G1                      | [da8e31b740](https://linux-hardware.org/?probe=da8e31b740) | Dec 23, 2021 |
| Dell          | Inspiron 5447               | [83331a9c7c](https://linux-hardware.org/?probe=83331a9c7c) | Dec 22, 2021 |
| Acer          | Aspire A315-41              | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| Apple         | MacBookPro11,3              | [1975ee2fc0](https://linux-hardware.org/?probe=1975ee2fc0) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Apple         | MacBookPro7,1               | [5994dbd498](https://linux-hardware.org/?probe=5994dbd498) | Dec 21, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Notebook      | NH5x_NH7xHP                 | [0408aca941](https://linux-hardware.org/?probe=0408aca941) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | [e82554da93](https://linux-hardware.org/?probe=e82554da93) | Dec 21, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [7fc27f5255](https://linux-hardware.org/?probe=7fc27f5255) | Dec 21, 2021 |
| Apple         | MacBookPro7,1               | [5f47284626](https://linux-hardware.org/?probe=5f47284626) | Dec 21, 2021 |
| Apple         | MacBookPro14,1              | [022cabd3f2](https://linux-hardware.org/?probe=022cabd3f2) | Dec 21, 2021 |
| HP            | Laptop 15s-eq2xxx           | [8cd9d762c9](https://linux-hardware.org/?probe=8cd9d762c9) | Dec 20, 2021 |
| HP            | Pavilion 15                 | [7248fa574f](https://linux-hardware.org/?probe=7248fa574f) | Dec 20, 2021 |
| Notebook      | N24_25JU                    | [8ac7d4890e](https://linux-hardware.org/?probe=8ac7d4890e) | Dec 20, 2021 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [ddb3571ec6](https://linux-hardware.org/?probe=ddb3571ec6) | Dec 20, 2021 |
| HP            | Laptop 15s-eq2xxx           | [bb28c266ec](https://linux-hardware.org/?probe=bb28c266ec) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | [d335e16395](https://linux-hardware.org/?probe=d335e16395) | Dec 19, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [9c38b95aa0](https://linux-hardware.org/?probe=9c38b95aa0) | Dec 19, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | [e380536aac](https://linux-hardware.org/?probe=e380536aac) | Dec 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [87399b5e8b](https://linux-hardware.org/?probe=87399b5e8b) | Dec 19, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [ffd979b53f](https://linux-hardware.org/?probe=ffd979b53f) | Dec 19, 2021 |
| HUAWEI        | HVY-WXX9                    | [85e3feaeba](https://linux-hardware.org/?probe=85e3feaeba) | Dec 19, 2021 |
| Lenovo        | ThinkPad E580 20KS001EMX    | [366aae1cd6](https://linux-hardware.org/?probe=366aae1cd6) | Dec 18, 2021 |
| Acer          | Nitro AN515-53              | [a9affc8e28](https://linux-hardware.org/?probe=a9affc8e28) | Dec 18, 2021 |
| Dell          | Precision 5540              | [14a6857b99](https://linux-hardware.org/?probe=14a6857b99) | Dec 18, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [cda7a2c35c](https://linux-hardware.org/?probe=cda7a2c35c) | Dec 17, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [6bf6c57117](https://linux-hardware.org/?probe=6bf6c57117) | Dec 17, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [1bac69aa61](https://linux-hardware.org/?probe=1bac69aa61) | Dec 17, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [e985e04d6d](https://linux-hardware.org/?probe=e985e04d6d) | Dec 17, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [6deb57beb2](https://linux-hardware.org/?probe=6deb57beb2) | Dec 17, 2021 |
| Dell          | XPS 15 9500                 | [98e451612c](https://linux-hardware.org/?probe=98e451612c) | Dec 17, 2021 |
| AVITA         | NS14A1US                    | [e20bf09217](https://linux-hardware.org/?probe=e20bf09217) | Dec 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | [290b1d081b](https://linux-hardware.org/?probe=290b1d081b) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | [aba6548652](https://linux-hardware.org/?probe=aba6548652) | Dec 16, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [30a4a58c5d](https://linux-hardware.org/?probe=30a4a58c5d) | Dec 16, 2021 |
| Dell          | XPS 15 9500                 | [4d52a02213](https://linux-hardware.org/?probe=4d52a02213) | Dec 16, 2021 |
| Dell          | XPS 17 9700                 | [ff779fe08f](https://linux-hardware.org/?probe=ff779fe08f) | Dec 16, 2021 |
| MSI           | GL63 9SC                    | [ed637c5d15](https://linux-hardware.org/?probe=ed637c5d15) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [39491139d5](https://linux-hardware.org/?probe=39491139d5) | Dec 15, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [615d071a26](https://linux-hardware.org/?probe=615d071a26) | Dec 15, 2021 |
| HP            | Pavilion dv7                | [0e0f0e3c23](https://linux-hardware.org/?probe=0e0f0e3c23) | Dec 15, 2021 |
| Dell          | Latitude 5500               | [5b9479065e](https://linux-hardware.org/?probe=5b9479065e) | Dec 15, 2021 |
| Lenovo        | ThinkPad E14 20RA007TUE     | [3edd54970c](https://linux-hardware.org/?probe=3edd54970c) | Dec 15, 2021 |
| ASUSTek       | K43U                        | [d7df2cd94e](https://linux-hardware.org/?probe=d7df2cd94e) | Dec 15, 2021 |
| Acer          | Swift SF314-43              | [2cabe8184b](https://linux-hardware.org/?probe=2cabe8184b) | Dec 15, 2021 |
| HP            | ENVY Pro 4-b000 Ultraboo... | [20259384ac](https://linux-hardware.org/?probe=20259384ac) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [4290797f32](https://linux-hardware.org/?probe=4290797f32) | Dec 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [fb79be9e00](https://linux-hardware.org/?probe=fb79be9e00) | Dec 14, 2021 |
| Dell          | Inspiron 15 5510            | [dd29feeb10](https://linux-hardware.org/?probe=dd29feeb10) | Dec 14, 2021 |
| Dell          | Latitude 7300               | [23f38f8a7d](https://linux-hardware.org/?probe=23f38f8a7d) | Dec 14, 2021 |
| Acer          | Aspire A515-55              | [8d121836c9](https://linux-hardware.org/?probe=8d121836c9) | Dec 14, 2021 |
| Dell          | Latitude 7490               | [ae8a45bc5a](https://linux-hardware.org/?probe=ae8a45bc5a) | Dec 14, 2021 |
| Dell          | Inspiron 16 7610            | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Acer          | Swift SF314-43              | [fd53be96e6](https://linux-hardware.org/?probe=fd53be96e6) | Dec 13, 2021 |
| Notebook      | NH5xAx                      | [fcd36c9b82](https://linux-hardware.org/?probe=fcd36c9b82) | Dec 13, 2021 |
| Dell          | Vostro 5402                 | [2074bdb7a5](https://linux-hardware.org/?probe=2074bdb7a5) | Dec 13, 2021 |
| MSI           | Modern 14 B5M               | [5274b5a06c](https://linux-hardware.org/?probe=5274b5a06c) | Dec 13, 2021 |
| Avell High... | A70 LIV                     | [3930fc87b1](https://linux-hardware.org/?probe=3930fc87b1) | Dec 12, 2021 |
| Acer          | Aspire A315-31              | [24c8e29d95](https://linux-hardware.org/?probe=24c8e29d95) | Dec 12, 2021 |
| Dell          | Latitude 7290               | [8a2ecfe430](https://linux-hardware.org/?probe=8a2ecfe430) | Dec 12, 2021 |
| Acer          | Nitro AN515-45              | [5975d86599](https://linux-hardware.org/?probe=5975d86599) | Dec 12, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [1846fa72b5](https://linux-hardware.org/?probe=1846fa72b5) | Dec 12, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1H60... | [ffb1c97626](https://linux-hardware.org/?probe=ffb1c97626) | Dec 12, 2021 |
| Dell          | Inspiron 5515               | [901f720089](https://linux-hardware.org/?probe=901f720089) | Dec 11, 2021 |
| Dell          | Inspiron 5515               | [7c0553b250](https://linux-hardware.org/?probe=7c0553b250) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [54058ac7e2](https://linux-hardware.org/?probe=54058ac7e2) | Dec 11, 2021 |
| HP            | Pavilion Power Laptop 15... | [6d5c35bf9f](https://linux-hardware.org/?probe=6d5c35bf9f) | Dec 11, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [584be17bec](https://linux-hardware.org/?probe=584be17bec) | Dec 11, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [4fba952635](https://linux-hardware.org/?probe=4fba952635) | Dec 11, 2021 |
| HP            | ZBook 15 G2                 | [d7faa88624](https://linux-hardware.org/?probe=d7faa88624) | Dec 11, 2021 |
| Dell          | Latitude 7300               | [2bb3c232b6](https://linux-hardware.org/?probe=2bb3c232b6) | Dec 11, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3030cb05b9](https://linux-hardware.org/?probe=3030cb05b9) | Dec 11, 2021 |
| Fujitsu       | LIFEBOOK U7411              | [65bc5c1c5b](https://linux-hardware.org/?probe=65bc5c1c5b) | Dec 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f3d37d4574](https://linux-hardware.org/?probe=f3d37d4574) | Dec 10, 2021 |
| Dell          | Inspiron 13 5310            | [7a721d2c05](https://linux-hardware.org/?probe=7a721d2c05) | Dec 10, 2021 |
| Dell          | Vostro 3400                 | [bcb885e52b](https://linux-hardware.org/?probe=bcb885e52b) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [4fe4d7393e](https://linux-hardware.org/?probe=4fe4d7393e) | Dec 10, 2021 |
| Acer          | Swift SFX14-41G             | [a81ed5c974](https://linux-hardware.org/?probe=a81ed5c974) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [181607bac3](https://linux-hardware.org/?probe=181607bac3) | Dec 10, 2021 |
| Lenovo        | ThinkPad L14 Gen 2 20X10... | [c1de54b513](https://linux-hardware.org/?probe=c1de54b513) | Dec 10, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [4ba265c070](https://linux-hardware.org/?probe=4ba265c070) | Dec 10, 2021 |
| Lenovo        | G570 20079                  | [439a97ec9b](https://linux-hardware.org/?probe=439a97ec9b) | Dec 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [195283a93a](https://linux-hardware.org/?probe=195283a93a) | Dec 09, 2021 |
| Dell          | XPS 13 9305                 | [60e57ae6dd](https://linux-hardware.org/?probe=60e57ae6dd) | Dec 09, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | [73645a62d6](https://linux-hardware.org/?probe=73645a62d6) | Dec 09, 2021 |
| HP            | Laptop 15s-eq2xxx           | [b673a5f067](https://linux-hardware.org/?probe=b673a5f067) | Dec 08, 2021 |
| TUXEDO        | InfinityBook S 15 Gen6      | [3880c485fb](https://linux-hardware.org/?probe=3880c485fb) | Dec 08, 2021 |
| Apple         | MacBookPro12,1              | [fcfdb2cedc](https://linux-hardware.org/?probe=fcfdb2cedc) | Dec 08, 2021 |
| Sony          | SVE1711Z1RB                 | [adb25167ea](https://linux-hardware.org/?probe=adb25167ea) | Dec 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | [9c98446833](https://linux-hardware.org/?probe=9c98446833) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [ad406a6f63](https://linux-hardware.org/?probe=ad406a6f63) | Dec 07, 2021 |
| Notebook      | NH5xAx                      | [801df46937](https://linux-hardware.org/?probe=801df46937) | Dec 07, 2021 |
| HP            | 15 Notebook PC              | [0523a58e8a](https://linux-hardware.org/?probe=0523a58e8a) | Dec 07, 2021 |
| Lenovo        | ThinkPad X230 23255E4       | [3f2487b1a6](https://linux-hardware.org/?probe=3f2487b1a6) | Dec 07, 2021 |
| Lenovo        | G570 20079                  | [a6722f2ff3](https://linux-hardware.org/?probe=a6722f2ff3) | Dec 07, 2021 |
| Sony          | SVE1713S1RW                 | [41775b7503](https://linux-hardware.org/?probe=41775b7503) | Dec 07, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [8b704c0d3f](https://linux-hardware.org/?probe=8b704c0d3f) | Dec 06, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [b5a282abf6](https://linux-hardware.org/?probe=b5a282abf6) | Dec 06, 2021 |
| Apple         | MacBookPro9,2               | [4fc7bc5515](https://linux-hardware.org/?probe=4fc7bc5515) | Dec 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [42fe75c227](https://linux-hardware.org/?probe=42fe75c227) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | [0dc0958719](https://linux-hardware.org/?probe=0dc0958719) | Dec 06, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e18de7567f](https://linux-hardware.org/?probe=e18de7567f) | Dec 06, 2021 |
| Lenovo        | ThinkPad T460p 20FXS0550... | [40640fd92f](https://linux-hardware.org/?probe=40640fd92f) | Dec 06, 2021 |
| Framework     | Laptop                      | [64dc54fbc6](https://linux-hardware.org/?probe=64dc54fbc6) | Dec 06, 2021 |
| Acer          | Nitro AN515-45              | [8641f9b078](https://linux-hardware.org/?probe=8641f9b078) | Dec 05, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | [50d1714228](https://linux-hardware.org/?probe=50d1714228) | Dec 05, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [e2d660554f](https://linux-hardware.org/?probe=e2d660554f) | Dec 05, 2021 |
| Dell          | Inspiron 5405               | [91806303e6](https://linux-hardware.org/?probe=91806303e6) | Dec 05, 2021 |
| Dell          | Latitude E6530              | [de5ad42b2f](https://linux-hardware.org/?probe=de5ad42b2f) | Dec 04, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c91db7e021](https://linux-hardware.org/?probe=c91db7e021) | Dec 04, 2021 |
| Lenovo        | ThinkPad T490s 20NX000DR... | [15e8e28073](https://linux-hardware.org/?probe=15e8e28073) | Dec 04, 2021 |
| Acer          | Aspire E5-571G              | [b006a547c8](https://linux-hardware.org/?probe=b006a547c8) | Dec 04, 2021 |
| HP            | ProBook 470 G5              | [1cfd3aadd8](https://linux-hardware.org/?probe=1cfd3aadd8) | Dec 04, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [be3c6c3e84](https://linux-hardware.org/?probe=be3c6c3e84) | Dec 04, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [826435e568](https://linux-hardware.org/?probe=826435e568) | Dec 04, 2021 |
| Lenovo        | ThinkPad W520 42763JF       | [23d42021b2](https://linux-hardware.org/?probe=23d42021b2) | Dec 04, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [6239b4eda5](https://linux-hardware.org/?probe=6239b4eda5) | Dec 04, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [f90f047538](https://linux-hardware.org/?probe=f90f047538) | Dec 03, 2021 |
| Toshiba       | Satellite C70-A-K2W         | [8e46f67032](https://linux-hardware.org/?probe=8e46f67032) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | [775ec45ab8](https://linux-hardware.org/?probe=775ec45ab8) | Dec 03, 2021 |
| Lenovo        | ThinkPad X230 23257R2       | [b783f0a79d](https://linux-hardware.org/?probe=b783f0a79d) | Dec 03, 2021 |
| Gigabyte      | AERO 15 KB                  | [a7d3041cd2](https://linux-hardware.org/?probe=a7d3041cd2) | Dec 03, 2021 |
| HP            | Laptop 15s-eq2xxx           | [f53047cd0d](https://linux-hardware.org/?probe=f53047cd0d) | Dec 02, 2021 |
| Notebook      | NH55RGQ                     | [4189e1f255](https://linux-hardware.org/?probe=4189e1f255) | Dec 02, 2021 |
| Lenovo        | V15-ADA 82C7                | [5ade9a0569](https://linux-hardware.org/?probe=5ade9a0569) | Dec 02, 2021 |
| Lenovo        | ThinkPad L390 20NSS43600    | [e9aae12812](https://linux-hardware.org/?probe=e9aae12812) | Dec 02, 2021 |
| Acer          | Nitro AN515-55              | [d5c6c6edee](https://linux-hardware.org/?probe=d5c6c6edee) | Dec 01, 2021 |
| HP            | Laptop 15s-fq2xxx           | [94b9d8b093](https://linux-hardware.org/?probe=94b9d8b093) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | [240ca54dfb](https://linux-hardware.org/?probe=240ca54dfb) | Dec 01, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8cebf41624](https://linux-hardware.org/?probe=8cebf41624) | Dec 01, 2021 |
| HP            | Laptop 15s-eq1xxx           | [9b11575394](https://linux-hardware.org/?probe=9b11575394) | Dec 01, 2021 |
| HP            | ProBook 470 G5              | [610709bb66](https://linux-hardware.org/?probe=610709bb66) | Nov 30, 2021 |
| Acer          | Aspire E5-571G              | [f940ae414d](https://linux-hardware.org/?probe=f940ae414d) | Nov 30, 2021 |
| Dell          | Inspiron 7460               | [0a6feb58e7](https://linux-hardware.org/?probe=0a6feb58e7) | Nov 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [b2d55bd445](https://linux-hardware.org/?probe=b2d55bd445) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [23ae32af07](https://linux-hardware.org/?probe=23ae32af07) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [074ec973ae](https://linux-hardware.org/?probe=074ec973ae) | Nov 30, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [80bbba47f6](https://linux-hardware.org/?probe=80bbba47f6) | Nov 29, 2021 |
| Acer          | Aspire E5-571G              | [95cb3fe8b3](https://linux-hardware.org/?probe=95cb3fe8b3) | Nov 29, 2021 |
| Acer          | Predator G9-793             | [b9dc27ddac](https://linux-hardware.org/?probe=b9dc27ddac) | Nov 29, 2021 |
| Dell          | G5 5590                     | [e569e56450](https://linux-hardware.org/?probe=e569e56450) | Nov 29, 2021 |
| HP            | Laptop 15s-fq2xxx           | [959af2b8dd](https://linux-hardware.org/?probe=959af2b8dd) | Nov 29, 2021 |
| Acer          | Swift SF113-31              | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Notebook      | NB50TL                      | [15a716161c](https://linux-hardware.org/?probe=15a716161c) | Nov 28, 2021 |
| HP            | ProBook 470 G5              | [b75e21b247](https://linux-hardware.org/?probe=b75e21b247) | Nov 28, 2021 |
| Dell          | Inspiron 5558               | [b003366a2c](https://linux-hardware.org/?probe=b003366a2c) | Nov 28, 2021 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [8e5c4cc27b](https://linux-hardware.org/?probe=8e5c4cc27b) | Nov 28, 2021 |
| Apple         | MacBookPro7,1               | [6a4ed949e9](https://linux-hardware.org/?probe=6a4ed949e9) | Nov 28, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [0852350348](https://linux-hardware.org/?probe=0852350348) | Nov 28, 2021 |
| Dell          | Latitude 7420               | [7a96812e39](https://linux-hardware.org/?probe=7a96812e39) | Nov 28, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [eabdd46893](https://linux-hardware.org/?probe=eabdd46893) | Nov 28, 2021 |
| Lenovo        | G40-45 80E1                 | [b3cdb202fc](https://linux-hardware.org/?probe=b3cdb202fc) | Nov 28, 2021 |
| HP            | Laptop 15s-fq2xxx           | [d559f82ee3](https://linux-hardware.org/?probe=d559f82ee3) | Nov 28, 2021 |
| Dell          | XPS 13 7390                 | [783b49e383](https://linux-hardware.org/?probe=783b49e383) | Nov 28, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | [67f32be00d](https://linux-hardware.org/?probe=67f32be00d) | Nov 27, 2021 |
| Lenovo        | ThinkPad E480 20KNS0E200    | [968f938b4e](https://linux-hardware.org/?probe=968f938b4e) | Nov 27, 2021 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | [08612b7f88](https://linux-hardware.org/?probe=08612b7f88) | Nov 27, 2021 |
| Lenovo        | ThinkPad E15 20RD003JRT     | [ef8336f76a](https://linux-hardware.org/?probe=ef8336f76a) | Nov 26, 2021 |
| Dell          | Precision 5550              | [41caa6a4a0](https://linux-hardware.org/?probe=41caa6a4a0) | Nov 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [6056117cca](https://linux-hardware.org/?probe=6056117cca) | Nov 26, 2021 |
| ASUSTek       | K54C                        | [2604de426e](https://linux-hardware.org/?probe=2604de426e) | Nov 26, 2021 |
| Acer          | AP714-51T                   | [3fe9bcf889](https://linux-hardware.org/?probe=3fe9bcf889) | Nov 26, 2021 |
| Acer          | AP714-51T                   | [406001fc85](https://linux-hardware.org/?probe=406001fc85) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [c207f61d91](https://linux-hardware.org/?probe=c207f61d91) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [96c90ad6c9](https://linux-hardware.org/?probe=96c90ad6c9) | Nov 26, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [039dbf659a](https://linux-hardware.org/?probe=039dbf659a) | Nov 26, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [a000027ce6](https://linux-hardware.org/?probe=a000027ce6) | Nov 26, 2021 |
| Lenovo        | ThinkPad P1 Gen 2 20QT00... | [b9c1906f2b](https://linux-hardware.org/?probe=b9c1906f2b) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [366fe373c9](https://linux-hardware.org/?probe=366fe373c9) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | [beff046f56](https://linux-hardware.org/?probe=beff046f56) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXXW                   | [2a96a2a7af](https://linux-hardware.org/?probe=2a96a2a7af) | Nov 25, 2021 |
| Sony          | VPCF131FM                   | [f0ba5e0db2](https://linux-hardware.org/?probe=f0ba5e0db2) | Nov 25, 2021 |
| HUAWEI        | KLVL-WXX9                   | [3352efa5cd](https://linux-hardware.org/?probe=3352efa5cd) | Nov 25, 2021 |
| Dell          | Latitude E5470              | [1e35555998](https://linux-hardware.org/?probe=1e35555998) | Nov 24, 2021 |
| Dell          | XPS 13 9300                 | [a91462bd5a](https://linux-hardware.org/?probe=a91462bd5a) | Nov 24, 2021 |
| HP            | EliteBook 735 G5            | [d80b574cb4](https://linux-hardware.org/?probe=d80b574cb4) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b6bfa4b827](https://linux-hardware.org/?probe=b6bfa4b827) | Nov 24, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [44bf6f6d6f](https://linux-hardware.org/?probe=44bf6f6d6f) | Nov 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [3c3fbf498a](https://linux-hardware.org/?probe=3c3fbf498a) | Nov 23, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | [5be975dd37](https://linux-hardware.org/?probe=5be975dd37) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | [d29d6c2f61](https://linux-hardware.org/?probe=d29d6c2f61) | Nov 23, 2021 |
| Lenovo        | B40-70 80F30006BR           | [6e361a8715](https://linux-hardware.org/?probe=6e361a8715) | Nov 23, 2021 |
| Acer          | Nitro AN515-54              | [b58b567113](https://linux-hardware.org/?probe=b58b567113) | Nov 22, 2021 |
| Apple         | MacBookPro11,4              | [7b9225653f](https://linux-hardware.org/?probe=7b9225653f) | Nov 22, 2021 |
| HP            | ENVY Laptop 14-eb0xxx       | [365b3888e6](https://linux-hardware.org/?probe=365b3888e6) | Nov 22, 2021 |
| Fujitsu       | LIFEBOOK U747               | [ece0600e5d](https://linux-hardware.org/?probe=ece0600e5d) | Nov 22, 2021 |
| Apple         | MacBookPro7,1               | [c686d7d85c](https://linux-hardware.org/?probe=c686d7d85c) | Nov 22, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [f13b0fb2b9](https://linux-hardware.org/?probe=f13b0fb2b9) | Nov 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | [a20fe0f647](https://linux-hardware.org/?probe=a20fe0f647) | Nov 21, 2021 |
| Lenovo        | ThinkPad T400 6474B84       | [f779165258](https://linux-hardware.org/?probe=f779165258) | Nov 21, 2021 |
| Dell          | Latitude E5570              | [8cf8db7a89](https://linux-hardware.org/?probe=8cf8db7a89) | Nov 21, 2021 |
| Google        | Relm                        | [92e569bf1e](https://linux-hardware.org/?probe=92e569bf1e) | Nov 21, 2021 |
| HP            | Pavilion 17                 | [2d69072cdf](https://linux-hardware.org/?probe=2d69072cdf) | Nov 20, 2021 |
| Dell          | Latitude 5490               | [cbe23836bf](https://linux-hardware.org/?probe=cbe23836bf) | Nov 20, 2021 |
| Dell          | Latitude E7440              | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [8dfec492a4](https://linux-hardware.org/?probe=8dfec492a4) | Nov 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [78341a1a16](https://linux-hardware.org/?probe=78341a1a16) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [31cebd4e96](https://linux-hardware.org/?probe=31cebd4e96) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | [0be43eb710](https://linux-hardware.org/?probe=0be43eb710) | Nov 19, 2021 |
| Acer          | Swift SF514-51              | [07e73dc8ab](https://linux-hardware.org/?probe=07e73dc8ab) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [a524ba65b5](https://linux-hardware.org/?probe=a524ba65b5) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [7e7b7d381e](https://linux-hardware.org/?probe=7e7b7d381e) | Nov 19, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [d0aea280e7](https://linux-hardware.org/?probe=d0aea280e7) | Nov 19, 2021 |
| Dell          | Inspiron 3593               | [0e670dc090](https://linux-hardware.org/?probe=0e670dc090) | Nov 19, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d7a5775f61](https://linux-hardware.org/?probe=d7a5775f61) | Nov 19, 2021 |
| Notebook      | NH55RGQ                     | [d111fd1549](https://linux-hardware.org/?probe=d111fd1549) | Nov 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [01a15306b9](https://linux-hardware.org/?probe=01a15306b9) | Nov 19, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [709cd419bc](https://linux-hardware.org/?probe=709cd419bc) | Nov 19, 2021 |
| ASUSTek       | X750JN                      | [bb6f44b058](https://linux-hardware.org/?probe=bb6f44b058) | Nov 19, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [f5a721bf24](https://linux-hardware.org/?probe=f5a721bf24) | Nov 19, 2021 |
| Dell          | Precision 5510              | [1d46cced08](https://linux-hardware.org/?probe=1d46cced08) | Nov 19, 2021 |
| HP            | Laptop 14s-fq0xxx           | [f9b7bdfef8](https://linux-hardware.org/?probe=f9b7bdfef8) | Nov 19, 2021 |
| Dell          | Inspiron 7572               | [0953d49db6](https://linux-hardware.org/?probe=0953d49db6) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [dc150f9fba](https://linux-hardware.org/?probe=dc150f9fba) | Nov 18, 2021 |
| HP            | EliteBook 840 G3            | [9e8fd0520d](https://linux-hardware.org/?probe=9e8fd0520d) | Nov 18, 2021 |
| Lenovo        | Legion R9000P2021H 82JQ     | [7734a8d28c](https://linux-hardware.org/?probe=7734a8d28c) | Nov 18, 2021 |
| Acer          | Swift SF314-43              | [46c44d537a](https://linux-hardware.org/?probe=46c44d537a) | Nov 18, 2021 |
| HP            | Pavilion Notebook           | [01f7a4c33d](https://linux-hardware.org/?probe=01f7a4c33d) | Nov 18, 2021 |
| Acer          | Swift SF314-42              | [05020e1e61](https://linux-hardware.org/?probe=05020e1e61) | Nov 18, 2021 |
| Toshiba       | Satellite C855-12R          | [dbde83db50](https://linux-hardware.org/?probe=dbde83db50) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [427ee1a6de](https://linux-hardware.org/?probe=427ee1a6de) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | [585419cd38](https://linux-hardware.org/?probe=585419cd38) | Nov 17, 2021 |
| Login Info... | LOG-QAL30                   | [9dff5423c9](https://linux-hardware.org/?probe=9dff5423c9) | Nov 17, 2021 |
| Dell          | Latitude E7270              | [70a4c30534](https://linux-hardware.org/?probe=70a4c30534) | Nov 17, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [6196137046](https://linux-hardware.org/?probe=6196137046) | Nov 17, 2021 |
| HP            | Pavilion 15                 | [d6caf6dd12](https://linux-hardware.org/?probe=d6caf6dd12) | Nov 17, 2021 |
| Toshiba       | Satellite C855-12R          | [eefe2dc8be](https://linux-hardware.org/?probe=eefe2dc8be) | Nov 17, 2021 |
| HP            | Pavilion 15                 | [581a56e963](https://linux-hardware.org/?probe=581a56e963) | Nov 17, 2021 |
| HP            | ENVY Laptop 15t-ep000       | [02c2ed5954](https://linux-hardware.org/?probe=02c2ed5954) | Nov 16, 2021 |
| HP            | Laptop 15s-eq2xxx           | [ec73e73572](https://linux-hardware.org/?probe=ec73e73572) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | [c4763ca2a5](https://linux-hardware.org/?probe=c4763ca2a5) | Nov 16, 2021 |
| Acer          | Swift SF314-43              | [db85b885ae](https://linux-hardware.org/?probe=db85b885ae) | Nov 16, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [6b1f5ce8b7](https://linux-hardware.org/?probe=6b1f5ce8b7) | Nov 16, 2021 |
| ASUSTek       | S551LN                      | [53b3fced16](https://linux-hardware.org/?probe=53b3fced16) | Nov 16, 2021 |
| Toshiba       | Satellite C855-12R          | [ccf125eb47](https://linux-hardware.org/?probe=ccf125eb47) | Nov 16, 2021 |
| MSI           | Modern 15 A11M              | [6398858488](https://linux-hardware.org/?probe=6398858488) | Nov 16, 2021 |
| Notebook      | NH55RGQ                     | [b3cb30c28d](https://linux-hardware.org/?probe=b3cb30c28d) | Nov 16, 2021 |
| Razer         | Blade 15 Advanced Model ... | [1119a0805e](https://linux-hardware.org/?probe=1119a0805e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | [dbaa27643e](https://linux-hardware.org/?probe=dbaa27643e) | Nov 16, 2021 |
| Acer          | Aspire E1-572               | [aad4a92e0e](https://linux-hardware.org/?probe=aad4a92e0e) | Nov 16, 2021 |
| Apple         | MacBookPro6,2               | [75e80e1ea8](https://linux-hardware.org/?probe=75e80e1ea8) | Nov 15, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [06f896ff98](https://linux-hardware.org/?probe=06f896ff98) | Nov 15, 2021 |
| Acer          | Aspire A715-71G             | [dd0bfcd823](https://linux-hardware.org/?probe=dd0bfcd823) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [ea6139e86c](https://linux-hardware.org/?probe=ea6139e86c) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [90e882710c](https://linux-hardware.org/?probe=90e882710c) | Nov 15, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | [516e448510](https://linux-hardware.org/?probe=516e448510) | Nov 14, 2021 |
| MSI           | Modern 15 A11M              | [8b02ecc2b6](https://linux-hardware.org/?probe=8b02ecc2b6) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | [70b84217bd](https://linux-hardware.org/?probe=70b84217bd) | Nov 14, 2021 |
| Dell          | Precision 3541              | [a21fd45ac3](https://linux-hardware.org/?probe=a21fd45ac3) | Nov 14, 2021 |
| ASUSTek       | ZenBook UX433FA_UX433FA     | [54bb479f64](https://linux-hardware.org/?probe=54bb479f64) | Nov 14, 2021 |
| SiComputer    | Nauta 01W PRO               | [d88aea84ef](https://linux-hardware.org/?probe=d88aea84ef) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| Apple         | MacBookPro6,2               | [a778aba19c](https://linux-hardware.org/?probe=a778aba19c) | Nov 14, 2021 |
| Dell          | Vostro 3460                 | [3a6a636384](https://linux-hardware.org/?probe=3a6a636384) | Nov 14, 2021 |
| Dell          | Latitude 5511               | [dc7c10f4e2](https://linux-hardware.org/?probe=dc7c10f4e2) | Nov 13, 2021 |
| Dell          | Latitude 5511               | [b0ca679bc5](https://linux-hardware.org/?probe=b0ca679bc5) | Nov 13, 2021 |
| HP            | ProBook 430 G1              | [68633b9bf5](https://linux-hardware.org/?probe=68633b9bf5) | Nov 13, 2021 |
| MSI           | Delta 15 A5EFK              | [bc348014b5](https://linux-hardware.org/?probe=bc348014b5) | Nov 13, 2021 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [3cfeff5a7f](https://linux-hardware.org/?probe=3cfeff5a7f) | Nov 13, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [9e8eab1073](https://linux-hardware.org/?probe=9e8eab1073) | Nov 13, 2021 |
| Lenovo        | Legion R7000P2021H 82JU     | [19ffbfb846](https://linux-hardware.org/?probe=19ffbfb846) | Nov 13, 2021 |
| Dell          | Inspiron 14-3467            | [ebe54808c2](https://linux-hardware.org/?probe=ebe54808c2) | Nov 13, 2021 |
| Apple         | MacBookPro10,2              | [5cbec68d6e](https://linux-hardware.org/?probe=5cbec68d6e) | Nov 13, 2021 |
| Positivo      | V142N_4G                    | [6afdf02b96](https://linux-hardware.org/?probe=6afdf02b96) | Nov 13, 2021 |
| Acer          | Swift SFX14-41G             | [04e988d138](https://linux-hardware.org/?probe=04e988d138) | Nov 13, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [85929a9a18](https://linux-hardware.org/?probe=85929a9a18) | Nov 12, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [3a33eaa4c0](https://linux-hardware.org/?probe=3a33eaa4c0) | Nov 12, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [3bbda8b194](https://linux-hardware.org/?probe=3bbda8b194) | Nov 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| Dell          | Precision 5510              | [80bbc48bce](https://linux-hardware.org/?probe=80bbc48bce) | Nov 12, 2021 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | [a7998fa53a](https://linux-hardware.org/?probe=a7998fa53a) | Nov 11, 2021 |
| System76      | Oryx Pro                    | [77cf902290](https://linux-hardware.org/?probe=77cf902290) | Nov 11, 2021 |
| Apple         | MacBookPro9,2               | [61afe68685](https://linux-hardware.org/?probe=61afe68685) | Nov 11, 2021 |
| Dell          | Latitude E7440              | [e907f0bbf1](https://linux-hardware.org/?probe=e907f0bbf1) | Nov 11, 2021 |
| ASUSTek       | X202EV                      | [ff0732f245](https://linux-hardware.org/?probe=ff0732f245) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [7df8bf1476](https://linux-hardware.org/?probe=7df8bf1476) | Nov 11, 2021 |
| HP            | EliteBook 850 G5            | [1def8c2d0b](https://linux-hardware.org/?probe=1def8c2d0b) | Nov 11, 2021 |
| Dell          | XPS 13 7390                 | [f5ceaaf6fe](https://linux-hardware.org/?probe=f5ceaaf6fe) | Nov 11, 2021 |
| Apple         | MacBookAir6,1               | [588c351d40](https://linux-hardware.org/?probe=588c351d40) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [ac9d7f968f](https://linux-hardware.org/?probe=ac9d7f968f) | Nov 10, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| Acer          | Nitro AN515-55              | [d4f75f503d](https://linux-hardware.org/?probe=d4f75f503d) | Nov 10, 2021 |
| ASUSTek       | T102HA                      | [d648620b1a](https://linux-hardware.org/?probe=d648620b1a) | Nov 10, 2021 |
| LG Electro... | 14Z90P-G.AR53A              | [a1fb8771db](https://linux-hardware.org/?probe=a1fb8771db) | Nov 10, 2021 |
| HP            | ProBook 430 G1              | [99ece77400](https://linux-hardware.org/?probe=99ece77400) | Nov 10, 2021 |
| HUAWEI        | KPL-W0X                     | [807e59f1e3](https://linux-hardware.org/?probe=807e59f1e3) | Nov 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [5a2fa34576](https://linux-hardware.org/?probe=5a2fa34576) | Nov 10, 2021 |
| HP            | Laptop 15s-fq2xxx           | [c8fb558bb7](https://linux-hardware.org/?probe=c8fb558bb7) | Nov 09, 2021 |
| Lenovo        | ThinkPad X260 20F5S0E000    | [2321968d02](https://linux-hardware.org/?probe=2321968d02) | Nov 09, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [81605538eb](https://linux-hardware.org/?probe=81605538eb) | Nov 09, 2021 |
| MSI           | GL62M 7RDX                  | [3538358a06](https://linux-hardware.org/?probe=3538358a06) | Nov 09, 2021 |
| HUAWEI        | HLYL-WXX9                   | [1c63b3b4ce](https://linux-hardware.org/?probe=1c63b3b4ce) | Nov 09, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | [cb4e2271c0](https://linux-hardware.org/?probe=cb4e2271c0) | Nov 09, 2021 |
| Toshiba       | NB255                       | [3c30b0d7ad](https://linux-hardware.org/?probe=3c30b0d7ad) | Nov 09, 2021 |
| HP            | Notebook                    | [e254c5c947](https://linux-hardware.org/?probe=e254c5c947) | Nov 08, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | [5f5424fe84](https://linux-hardware.org/?probe=5f5424fe84) | Nov 08, 2021 |
| Lenovo        | ThinkPad E590 20NB005GMH    | [146b572cd0](https://linux-hardware.org/?probe=146b572cd0) | Nov 08, 2021 |
| Lenovo        | IdeaPad Z510 20287          | [0812e26e5a](https://linux-hardware.org/?probe=0812e26e5a) | Nov 08, 2021 |
| Dell          | XPS 13 9360                 | [8988b7e735](https://linux-hardware.org/?probe=8988b7e735) | Nov 08, 2021 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [b996ce8823](https://linux-hardware.org/?probe=b996ce8823) | Nov 07, 2021 |
| Lenovo        | Ducati 5 82ES               | [6269149643](https://linux-hardware.org/?probe=6269149643) | Nov 07, 2021 |
| HP            | Pavilion Laptop 15-ck0xx    | [b4d29007be](https://linux-hardware.org/?probe=b4d29007be) | Nov 07, 2021 |
| Dell          | Latitude E7440              | [b2560457a5](https://linux-hardware.org/?probe=b2560457a5) | Nov 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [af116b7c35](https://linux-hardware.org/?probe=af116b7c35) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [ced169a0b1](https://linux-hardware.org/?probe=ced169a0b1) | Nov 06, 2021 |
| Apple         | MacBookPro6,2               | [bde89fd503](https://linux-hardware.org/?probe=bde89fd503) | Nov 06, 2021 |
| HP            | ProBook 455 G1              | [44a11d66ac](https://linux-hardware.org/?probe=44a11d66ac) | Nov 06, 2021 |
| HP            | 250 G1                      | [1c52b861c7](https://linux-hardware.org/?probe=1c52b861c7) | Nov 06, 2021 |
| Lenovo        | ThinkPad E14 20RA001XIX     | [98d8c0fbdb](https://linux-hardware.org/?probe=98d8c0fbdb) | Nov 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [bb1201e75c](https://linux-hardware.org/?probe=bb1201e75c) | Nov 06, 2021 |
| HP            | EliteBook 2570p             | [dc62969834](https://linux-hardware.org/?probe=dc62969834) | Nov 05, 2021 |
| Notebook      | W65_W67RZ                   | [153b2a920d](https://linux-hardware.org/?probe=153b2a920d) | Nov 05, 2021 |
| HONOR         | NBD-WXX9                    | [1030fbbff6](https://linux-hardware.org/?probe=1030fbbff6) | Nov 05, 2021 |
| Unknown       | Unknown                     | [c78a5c81b2](https://linux-hardware.org/?probe=c78a5c81b2) | Nov 05, 2021 |
| HP            | ZBook 14u G5                | [ec192642ba](https://linux-hardware.org/?probe=ec192642ba) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [8e06f2617d](https://linux-hardware.org/?probe=8e06f2617d) | Nov 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [1a2dda8941](https://linux-hardware.org/?probe=1a2dda8941) | Nov 05, 2021 |
| HP            | Laptop 15s-eq2xxx           | [04d4fca603](https://linux-hardware.org/?probe=04d4fca603) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | [f29c3d7003](https://linux-hardware.org/?probe=f29c3d7003) | Nov 04, 2021 |
| HP            | ProBook 430 G5              | [a795236afd](https://linux-hardware.org/?probe=a795236afd) | Nov 04, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [cd291857e2](https://linux-hardware.org/?probe=cd291857e2) | Nov 04, 2021 |
| Lenovo        | ThinkPad T460 20FNCTO1WW    | [6ee78bd50a](https://linux-hardware.org/?probe=6ee78bd50a) | Nov 04, 2021 |
| Lenovo        | ThinkPad X270 20HN0013UK    | [8454cff91f](https://linux-hardware.org/?probe=8454cff91f) | Nov 04, 2021 |
| Dell          | Studio 1537                 | [d040c159b8](https://linux-hardware.org/?probe=d040c159b8) | Nov 04, 2021 |
| HP            | ProBook 430 G3              | [1d421060d7](https://linux-hardware.org/?probe=1d421060d7) | Nov 03, 2021 |
| Dell          | Precision 5510              | [eb702ce1e6](https://linux-hardware.org/?probe=eb702ce1e6) | Nov 03, 2021 |
| Dell          | Inspiron 5502               | [c68c3a5c3b](https://linux-hardware.org/?probe=c68c3a5c3b) | Nov 03, 2021 |
| Lenovo        | ThinkPad E15 20RD0011GE     | [10bd49d9c0](https://linux-hardware.org/?probe=10bd49d9c0) | Nov 03, 2021 |
| Dell          | Latitude 5590               | [5bc1ed5978](https://linux-hardware.org/?probe=5bc1ed5978) | Nov 03, 2021 |
| Lenovo        | ThinkPad T420 4236DK9       | [84e39e6c94](https://linux-hardware.org/?probe=84e39e6c94) | Nov 03, 2021 |
| System76      | Pangolin                    | [1eb0a48a30](https://linux-hardware.org/?probe=1eb0a48a30) | Nov 03, 2021 |
| HP            | Laptop 14-dq2xxx            | [f30e20e67b](https://linux-hardware.org/?probe=f30e20e67b) | Nov 03, 2021 |
| Dell          | XPS 15 9570                 | [8e3c5b2ef0](https://linux-hardware.org/?probe=8e3c5b2ef0) | Nov 03, 2021 |
| Lenovo        | ThinkPad X395 20NL0005US    | [b65f4d5ba3](https://linux-hardware.org/?probe=b65f4d5ba3) | Nov 03, 2021 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [8c19662b7e](https://linux-hardware.org/?probe=8c19662b7e) | Nov 03, 2021 |
| Toshiba       | TECRA Z50-A                 | [4aae9bdc03](https://linux-hardware.org/?probe=4aae9bdc03) | Nov 03, 2021 |
| Dell          | XPS 13 9370                 | [458d3682a5](https://linux-hardware.org/?probe=458d3682a5) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [7205a2ab55](https://linux-hardware.org/?probe=7205a2ab55) | Nov 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [54b32173dd](https://linux-hardware.org/?probe=54b32173dd) | Nov 03, 2021 |
| Dell          | XPS 13 7390                 | [40df244ae9](https://linux-hardware.org/?probe=40df244ae9) | Nov 02, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | [eeb181f50b](https://linux-hardware.org/?probe=eeb181f50b) | Oct 30, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1310b8abf4](https://linux-hardware.org/?probe=1310b8abf4) | Oct 30, 2021 |
| Framework     | Laptop                      | [04db6c2222](https://linux-hardware.org/?probe=04db6c2222) | Oct 29, 2021 |
| Acer          | Aspire F5-573G              | [1be6c8dc87](https://linux-hardware.org/?probe=1be6c8dc87) | Oct 29, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [f8024b89d4](https://linux-hardware.org/?probe=f8024b89d4) | Oct 28, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [e9a8fb1275](https://linux-hardware.org/?probe=e9a8fb1275) | Oct 27, 2021 |
| BESSTAR Te... | X400                        | [9cfc0bb300](https://linux-hardware.org/?probe=9cfc0bb300) | Oct 27, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | [d3720f9145](https://linux-hardware.org/?probe=d3720f9145) | Oct 25, 2021 |
| Alienware     | Area-51m R2                 | [c3f94d8599](https://linux-hardware.org/?probe=c3f94d8599) | Oct 24, 2021 |
| HP            | ProBook 470 G5              | [725627d16b](https://linux-hardware.org/?probe=725627d16b) | Oct 23, 2021 |
| HP            | EliteBook 8560w             | [98bd384a42](https://linux-hardware.org/?probe=98bd384a42) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [91fc910cf6](https://linux-hardware.org/?probe=91fc910cf6) | Oct 23, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1c91bc1deb](https://linux-hardware.org/?probe=1c91bc1deb) | Oct 23, 2021 |
| Lenovo        | ThinkPad T480 20L5000BMX    | [21b13fb067](https://linux-hardware.org/?probe=21b13fb067) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [9932dd3c21](https://linux-hardware.org/?probe=9932dd3c21) | Oct 21, 2021 |
| Lenovo        | ThinkPad T490 20N3S6VU00    | [a99866abc1](https://linux-hardware.org/?probe=a99866abc1) | Oct 21, 2021 |
| Acer          | Swift SF114-32              | [faa49a332b](https://linux-hardware.org/?probe=faa49a332b) | Oct 20, 2021 |
| HP            | EliteBook 820 G1            | [278ec34902](https://linux-hardware.org/?probe=278ec34902) | Oct 19, 2021 |
| Lenovo        | ThinkPad T460 20FMS1R01K    | [4dbc231901](https://linux-hardware.org/?probe=4dbc231901) | Oct 18, 2021 |
| GPU Compan... | GWTN156-1                   | [3cb0b09b48](https://linux-hardware.org/?probe=3cb0b09b48) | Oct 17, 2021 |
| HP            | Laptop 14-df0xxx            | [ac488ba246](https://linux-hardware.org/?probe=ac488ba246) | Oct 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [362e1d3b99](https://linux-hardware.org/?probe=362e1d3b99) | Oct 15, 2021 |
| Dell          | Precision 5550              | [15a0f61f84](https://linux-hardware.org/?probe=15a0f61f84) | Oct 14, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4bb5ac9410](https://linux-hardware.org/?probe=4bb5ac9410) | Oct 12, 2021 |
| HP            | OMEN Laptop 15-ek0xxx       | [d4acf59f3b](https://linux-hardware.org/?probe=d4acf59f3b) | Oct 11, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b4efb9e18](https://linux-hardware.org/?probe=5b4efb9e18) | Oct 10, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | [fd09df16d9](https://linux-hardware.org/?probe=fd09df16d9) | Oct 10, 2021 |
| HP            | ProBook 450 G3              | [2eeb05ff03](https://linux-hardware.org/?probe=2eeb05ff03) | Oct 09, 2021 |
| HP            | ENVY Laptop 15t-ep000       | [f9b69ffa3d](https://linux-hardware.org/?probe=f9b69ffa3d) | Oct 08, 2021 |
| Dell          | Inspiron 5505               | [d136f5d8f7](https://linux-hardware.org/?probe=d136f5d8f7) | Oct 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [26c62915e0](https://linux-hardware.org/?probe=26c62915e0) | Oct 07, 2021 |
| ASUSTek       | VivoBook S15 X530UA         | [146866c629](https://linux-hardware.org/?probe=146866c629) | Oct 06, 2021 |
| Apple         | MacBookPro5,5               | [db435ab99c](https://linux-hardware.org/?probe=db435ab99c) | Oct 03, 2021 |
| Lenovo        | G580 20150                  | [08adba2c54](https://linux-hardware.org/?probe=08adba2c54) | Oct 02, 2021 |
| HUAWEI        | EUL-WX9                     | [dfc5c12fbf](https://linux-hardware.org/?probe=dfc5c12fbf) | Oct 01, 2021 |
| Lenovo        | G580 20150                  | [1dbb7762f6](https://linux-hardware.org/?probe=1dbb7762f6) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | [e64aeb5fa4](https://linux-hardware.org/?probe=e64aeb5fa4) | Oct 01, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [17c2d08e41](https://linux-hardware.org/?probe=17c2d08e41) | Oct 01, 2021 |
| HP            | EliteBook 840 G5            | [28bfae31ee](https://linux-hardware.org/?probe=28bfae31ee) | Oct 01, 2021 |
| Dell          | Studio 1537                 | [aae900457c](https://linux-hardware.org/?probe=aae900457c) | Oct 01, 2021 |
| Framework     | Laptop                      | [95576917c8](https://linux-hardware.org/?probe=95576917c8) | Sep 29, 2021 |
| Notebook      | N2x0WU                      | [410a2dab96](https://linux-hardware.org/?probe=410a2dab96) | Sep 28, 2021 |
| Lenovo        | IdeaPad C340-14API 81N6     | [82e0f76133](https://linux-hardware.org/?probe=82e0f76133) | Sep 25, 2021 |
| Lenovo        | ThinkPad E480 20KNS0MC00    | [ba847bc0c4](https://linux-hardware.org/?probe=ba847bc0c4) | Sep 23, 2021 |
| Apple         | MacBook6,1                  | [4fbbe3d05b](https://linux-hardware.org/?probe=4fbbe3d05b) | Sep 19, 2021 |
| HP            | G42                         | [0e9914c9cc](https://linux-hardware.org/?probe=0e9914c9cc) | Sep 18, 2021 |
| HP            | ZBook 15u G5                | [a5331a4d5e](https://linux-hardware.org/?probe=a5331a4d5e) | Sep 15, 2021 |
| Dell          | XPS 17 9700                 | [ebac1c499f](https://linux-hardware.org/?probe=ebac1c499f) | Sep 15, 2021 |
| ASUSTek       | G71V                        | [7904b934a4](https://linux-hardware.org/?probe=7904b934a4) | Sep 09, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [2b21ef140a](https://linux-hardware.org/?probe=2b21ef140a) | Sep 05, 2021 |
| Lenovo        | ThinkPad P51s 20HBCTO1WW    | [e2f22f9f40](https://linux-hardware.org/?probe=e2f22f9f40) | Aug 27, 2021 |
| Dell          | Latitude E5470              | [ac04ecb1e5](https://linux-hardware.org/?probe=ac04ecb1e5) | Aug 22, 2021 |
| Dell          | XPS 15 9550                 | [0a28b37020](https://linux-hardware.org/?probe=0a28b37020) | Aug 15, 2021 |
| Acer          | Aspire A315-42              | [4a54197130](https://linux-hardware.org/?probe=4a54197130) | Aug 15, 2021 |
| Acer          | Aspire ES1-572              | [06ddc49173](https://linux-hardware.org/?probe=06ddc49173) | Aug 13, 2021 |
| Dell          | XPS 15 9570                 | [f20e1ba8fe](https://linux-hardware.org/?probe=f20e1ba8fe) | Aug 13, 2021 |
| Dell          | XPS 13 9380                 | [1c3776f221](https://linux-hardware.org/?probe=1c3776f221) | Aug 13, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [ab00a7e359](https://linux-hardware.org/?probe=ab00a7e359) | Aug 13, 2021 |
| Notebook      | P377SM-A                    | [be5397dd67](https://linux-hardware.org/?probe=be5397dd67) | Aug 05, 2021 |
| HUAWEI        | KLVL-WXX9                   | [d677af1f50](https://linux-hardware.org/?probe=d677af1f50) | Aug 02, 2021 |
| HUAWEI        | KLVL-WXX9                   | [66c25f9637](https://linux-hardware.org/?probe=66c25f9637) | Jul 10, 2021 |
| Notebook      | P377SM-A                    | [bf37a519fa](https://linux-hardware.org/?probe=bf37a519fa) | May 17, 2021 |
| Notebook      | P377SM-A                    | [0834d4df8b](https://linux-hardware.org/?probe=0834d4df8b) | May 16, 2021 |
| Lenovo        | ThinkPad W541 20EF000UMN    | [f366b44668](https://linux-hardware.org/?probe=f366b44668) | Apr 11, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [31475604b7](https://linux-hardware.org/?probe=31475604b7) | Mar 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [151d163eb9](https://linux-hardware.org/?probe=151d163eb9) | Mar 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [4b33f82ac0](https://linux-hardware.org/?probe=4b33f82ac0) | Mar 06, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                       | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| 5.14.16-301.fc35.x86_64                                       | 45        | 9.05%   |
| 5.15.6-200.fc35.x86_64                                        | 42        | 8.45%   |
| 5.15.12-200.fc35.x86_64                                       | 39        | 7.85%   |
| 5.14.18-300.fc35.x86_64                                       | 38        | 7.65%   |
| 5.14.10-300.fc35.x86_64                                       | 34        | 6.84%   |
| 5.14.17-301.fc35.x86_64                                       | 28        | 5.63%   |
| 5.15.11-200.fc35.x86_64                                       | 25        | 5.03%   |
| 5.15.16-200.fc35.x86_64                                       | 22        | 4.43%   |
| 5.15.10-200.fc35.x86_64                                       | 21        | 4.23%   |
| 5.14.14-300.fc35.x86_64                                       | 21        | 4.23%   |
| 5.15.14-200.fc35.x86_64                                       | 16        | 3.22%   |
| 5.15.13-200.fc35.x86_64                                       | 16        | 3.22%   |
| 5.15.8-200.fc35.x86_64                                        | 15        | 3.02%   |
| 5.15.4-201.fc35.x86_64                                        | 15        | 3.02%   |
| 5.15.5-200.fc35.x86_64                                        | 14        | 2.82%   |
| 5.14.15-300.fc35.x86_64                                       | 13        | 2.62%   |
| 5.15.7-200.fc35.x86_64                                        | 12        | 2.41%   |
| 5.14.9-300.fc35.x86_64                                        | 9         | 1.81%   |
| 5.14.0-60.fc35.x86_64                                         | 7         | 1.41%   |
| 5.15.15-200.fc35.x86_64                                       | 6         | 1.21%   |
| 5.14.11-300.fc35.x86_64                                       | 5         | 1.01%   |
| 5.14.0-0.rc5.42.fc35.x86_64                                   | 5         | 1.01%   |
| 5.15.17-200.fc35.x86_64                                       | 3         | 0.6%    |
| 5.14.7-300.fc35.x86_64                                        | 3         | 0.6%    |
| 5.14.12-300.fc35.x86_64                                       | 3         | 0.6%    |
| 5.15.6-200.rog.fc35.x86_64                                    | 2         | 0.4%    |
| 5.14.3-300.fc35.x86_64                                        | 2         | 0.4%    |
| 5.11.12-300.fc34.x86_64                                       | 2         | 0.4%    |
| 5.16.2-200.fc35.x86_64                                        | 1         | 0.2%    |
| 5.16.1-xm1.0.fc35.x86_64                                      | 1         | 0.2%    |
| 5.16.0-0.rc7.20211231git4f3d93c6eaff.52.vanilla.1.fc35.x86_64 | 1         | 0.2%    |
| 5.16.0-0.rc5.35.vanilla.1.fc35.x86_64                         | 1         | 0.2%    |
| 5.15.8_tkg_pds                                                | 1         | 0.2%    |
| 5.15.8-200.rog.fc35.x86_64                                    | 1         | 0.2%    |
| 5.15.6-250.vanilla.1.fc35.x86_64                              | 1         | 0.2%    |
| 5.15.5-xm1tt.0.fc35.x86_64                                    | 1         | 0.2%    |
| 5.15.2-225.vanilla.1.fc35.x86_64                              | 1         | 0.2%    |
| 5.15.15-200.rog.fc35.x86_64                                   | 1         | 0.2%    |
| 5.15.13-lqx1.0.fc35.x86_64                                    | 1         | 0.2%    |
| 5.15.13-250.vanilla.1.fc35.x86_64                             | 1         | 0.2%    |
| 5.15.12-250.vanilla.1.fc35.x86_64                             | 1         | 0.2%    |
| 5.15.11-250.vanilla.1.fc35.x86_64                             | 1         | 0.2%    |
| 5.14.8-xm1cacule.0.fc35.x86_64                                | 1         | 0.2%    |
| 5.14.6-300.fc35.x86_64                                        | 1         | 0.2%    |
| 5.14.5-300.fc35.x86_64                                        | 1         | 0.2%    |
| 5.14.16-201.fc34.x86_64                                       | 1         | 0.2%    |
| 5.14.15-300.rog.fc35.x86_64                                   | 1         | 0.2%    |
| 5.14.1-300.fc35.x86_64                                        | 1         | 0.2%    |
| 5.14.0-0.rc6.46.fc35.x86_64                                   | 1         | 0.2%    |
| 5.14.0-0.rc4.20210804gitd5ad8ec3cfb5.36.fc35.x86_64           | 1         | 0.2%    |
| 5.14.0-0.rc3.20210728git4010a528219e.32.fc35.x86_64           | 1         | 0.2%    |
| 5.14.0-0.rc0.20210701gitdbe69e433722.6.fc35.x86_64            | 1         | 0.2%    |
| 5.13.9-200.fc34.x86_64                                        | 1         | 0.2%    |
| 5.13.4-200.fc34.x86_64                                        | 1         | 0.2%    |
| 5.13.19-200.fc35.x86_64                                       | 1         | 0.2%    |
| 5.13.19-200.fc34.x86_64                                       | 1         | 0.2%    |
| 5.13.0-0.rc1.20210513gitc06a2ba62fc4.15.fc35.x86_64           | 1         | 0.2%    |
| 5.12.8-300.fc34.x86_64                                        | 1         | 0.2%    |
| 5.12.0-0.rc6.20210408git454859c552da.186.fc35.x86_64          | 1         | 0.2%    |
| 5.12.0-0.rc1.162.fc35.x86_64                                  | 1         | 0.2%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.16 | 46        | 9.27%   |
| 5.15.6  | 45        | 9.07%   |
| 5.15.12 | 40        | 8.06%   |
| 5.14.18 | 38        | 7.66%   |
| 5.14.10 | 34        | 6.85%   |
| 5.14.17 | 28        | 5.65%   |
| 5.15.11 | 26        | 5.24%   |
| 5.15.16 | 22        | 4.44%   |
| 5.15.10 | 21        | 4.23%   |
| 5.14.14 | 21        | 4.23%   |
| 5.15.13 | 18        | 3.63%   |
| 5.15.8  | 17        | 3.43%   |
| 5.15.14 | 16        | 3.23%   |
| 5.15.5  | 15        | 3.02%   |
| 5.15.4  | 15        | 3.02%   |
| 5.14.0  | 15        | 3.02%   |
| 5.14.15 | 14        | 2.82%   |
| 5.15.7  | 12        | 2.42%   |
| 5.14.9  | 9         | 1.81%   |
| 5.15.15 | 7         | 1.41%   |
| 5.14.11 | 5         | 1.01%   |
| 5.15.17 | 3         | 0.6%    |
| 5.14.7  | 3         | 0.6%    |
| 5.14.12 | 3         | 0.6%    |
| 5.16.0  | 2         | 0.4%    |
| 5.14.3  | 2         | 0.4%    |
| 5.13.19 | 2         | 0.4%    |
| 5.12.0  | 2         | 0.4%    |
| 5.11.12 | 2         | 0.4%    |
| 5.16.2  | 1         | 0.2%    |
| 5.16.1  | 1         | 0.2%    |
| 5.15.2  | 1         | 0.2%    |
| 5.14.8  | 1         | 0.2%    |
| 5.14.6  | 1         | 0.2%    |
| 5.14.5  | 1         | 0.2%    |
| 5.14.1  | 1         | 0.2%    |
| 5.13.9  | 1         | 0.2%    |
| 5.13.4  | 1         | 0.2%    |
| 5.13.0  | 1         | 0.2%    |
| 5.12.8  | 1         | 0.2%    |
| 5.10.93 | 1         | 0.2%    |
| 5.10.23 | 1         | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 245       | 51.26%  |
| 5.14    | 217       | 45.4%   |
| 5.13    | 5         | 1.05%   |
| 5.16    | 4         | 0.84%   |
| 5.12    | 3         | 0.63%   |
| 5.11    | 2         | 0.42%   |
| 5.10    | 2         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 457       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 360       | 77.92%  |
| KDE5            | 43        | 9.31%   |
| Unknown         | 17        | 3.68%   |
| MATE            | 10        | 2.16%   |
| X-Cinnamon      | 8         | 1.73%   |
| Cinnamon        | 7         | 1.52%   |
| XFCE            | 4         | 0.87%   |
| sway            | 3         | 0.65%   |
| Pantheon        | 2         | 0.43%   |
| openbox         | 1         | 0.22%   |
| LXDE            | 1         | 0.22%   |
| KDE             | 1         | 0.22%   |
| i3              | 1         | 0.22%   |
| GNOME Flashback | 1         | 0.22%   |
| GNOME Classic   | 1         | 0.22%   |
| fluxbox         | 1         | 0.22%   |
| bspwm           | 1         | 0.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 317       | 68.61%  |
| X11     | 130       | 28.14%  |
| Unknown | 9         | 1.95%   |
| Tty     | 6         | 1.3%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 219       | 47.51%  |
| GDM     | 186       | 40.35%  |
| LightDM | 31        | 6.72%   |
| SDDM    | 23        | 4.99%   |
| XDM     | 1         | 0.22%   |
| LXDM    | 1         | 0.22%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 252       | 54.78%  |
| en_GB   | 45        | 9.78%   |
| ru_RU   | 22        | 4.78%   |
| pt_BR   | 21        | 4.57%   |
| fr_FR   | 14        | 3.04%   |
| it_IT   | 13        | 2.83%   |
| de_DE   | 11        | 2.39%   |
| pl_PL   | 9         | 1.96%   |
| en_CA   | 8         | 1.74%   |
| en_AU   | 7         | 1.52%   |
| es_ES   | 6         | 1.3%    |
| sv_SE   | 4         | 0.87%   |
| nl_NL   | 3         | 0.65%   |
| fr_CA   | 3         | 0.65%   |
| es_MX   | 3         | 0.65%   |
| es_AR   | 3         | 0.65%   |
| cs_CZ   | 3         | 0.65%   |
| C       | 3         | 0.65%   |
| zh_CN   | 2         | 0.43%   |
| uk_UA   | 2         | 0.43%   |
| pt_PT   | 2         | 0.43%   |
| nb_NO   | 2         | 0.43%   |
| es_CO   | 2         | 0.43%   |
| es_CL   | 2         | 0.43%   |
| en_NZ   | 2         | 0.43%   |
| en_IN   | 2         | 0.43%   |
| tr_TR   | 1         | 0.22%   |
| szl_PL  | 1         | 0.22%   |
| ru_UA   | 1         | 0.22%   |
| nl_BE   | 1         | 0.22%   |
| ga_IE   | 1         | 0.22%   |
| fi_FI   | 1         | 0.22%   |
| es_PE   | 1         | 0.22%   |
| es_GT   | 1         | 0.22%   |
| en_ZA   | 1         | 0.22%   |
| en_IL   | 1         | 0.22%   |
| de_CH   | 1         | 0.22%   |
| de_AT   | 1         | 0.22%   |
| da_DK   | 1         | 0.22%   |
| Unknown | 1         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 389       | 84.57%  |
| BIOS | 71        | 15.43%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 337       | 73.42%  |
| Ext4    | 107       | 23.31%  |
| Xfs     | 12        | 2.61%   |
| Overlay | 2         | 0.44%   |
| Unknown | 1         | 0.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 221       | 47.84%  |
| GPT     | 214       | 46.32%  |
| MBR     | 27        | 5.84%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 411       | 89.15%  |
| Yes       | 50        | 10.85%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 380       | 82.61%  |
| Yes       | 80        | 17.39%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 148       | 32.39%  |
| Dell                   | 83        | 18.16%  |
| Hewlett-Packard        | 59        | 12.91%  |
| ASUSTek Computer       | 34        | 7.44%   |
| Acer                   | 32        | 7%      |
| Apple                  | 20        | 4.38%   |
| HUAWEI                 | 13        | 2.84%   |
| Notebook               | 11        | 2.41%   |
| Toshiba                | 9         | 1.97%   |
| MSI                    | 7         | 1.53%   |
| Sony                   | 4         | 0.88%   |
| Positivo               | 3         | 0.66%   |
| Google                 | 3         | 0.66%   |
| Framework              | 3         | 0.66%   |
| System76               | 2         | 0.44%   |
| Samsung Electronics    | 2         | 0.44%   |
| Razer                  | 2         | 0.44%   |
| Fujitsu                | 2         | 0.44%   |
| TUXEDO                 | 1         | 0.22%   |
| SiComputer             | 1         | 0.22%   |
| SCHNEIDER              | 1         | 0.22%   |
| Positivo Bahia - VAIO  | 1         | 0.22%   |
| Panasonic              | 1         | 0.22%   |
| Mediacom               | 1         | 0.22%   |
| Login Informatica      | 1         | 0.22%   |
| LG Electronics         | 1         | 0.22%   |
| LDLC                   | 1         | 0.22%   |
| HONOR                  | 1         | 0.22%   |
| Hampoo                 | 1         | 0.22%   |
| GPU Company            | 1         | 0.22%   |
| Gigabyte Technology    | 1         | 0.22%   |
| Fujitsu Siemens        | 1         | 0.22%   |
| Cube                   | 1         | 0.22%   |
| BESSTAR Tech           | 1         | 0.22%   |
| AVITA                  | 1         | 0.22%   |
| Avell High Performance | 1         | 0.22%   |
| Alienware              | 1         | 0.22%   |
| Unknown                | 1         | 0.22%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell Latitude E7440                        | 4         | 0.88%   |
| Lenovo IdeaPad 530S-14IKB 81EU             | 3         | 0.66%   |
| Lenovo IdeaPad 3 14ALC6 82KT               | 3         | 0.66%   |
| HUAWEI KLVL-WXX9                           | 3         | 0.66%   |
| Framework Laptop                           | 3         | 0.66%   |
| Dell XPS 17 9700                           | 3         | 0.66%   |
| Dell XPS 13 7390                           | 3         | 0.66%   |
| Dell Precision 5510                        | 3         | 0.66%   |
| ASUS ROG Strix G513QY_G513QY               | 3         | 0.66%   |
| Apple MacBookPro9,2                        | 3         | 0.66%   |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.44%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 2         | 0.44%   |
| Lenovo ThinkPad P1 Gen 3 20TJS53A00        | 2         | 0.44%   |
| Lenovo ThinkPad E14 Gen 3 20Y7CTO1WW       | 2         | 0.44%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 2         | 0.44%   |
| Lenovo IdeaPad 320-15ISK 80XH              | 2         | 0.44%   |
| HUAWEI HVY-WXX9                            | 2         | 0.44%   |
| HP ProBook 470 G5                          | 2         | 0.44%   |
| HP Pavilion Notebook                       | 2         | 0.44%   |
| HP Pavilion Gaming Laptop 15-ec0xxx        | 2         | 0.44%   |
| HP Laptop 15s-fq2xxx                       | 2         | 0.44%   |
| Dell XPS 15 9570                           | 2         | 0.44%   |
| Dell XPS 13 9380                           | 2         | 0.44%   |
| Dell XPS 13 9310                           | 2         | 0.44%   |
| Dell Latitude E6530                        | 2         | 0.44%   |
| Dell Latitude E5570                        | 2         | 0.44%   |
| Dell Latitude E5470                        | 2         | 0.44%   |
| Dell Latitude 7490                         | 2         | 0.44%   |
| Dell Latitude 7300                         | 2         | 0.44%   |
| Dell Latitude 5511                         | 2         | 0.44%   |
| Dell Inspiron 7591                         | 2         | 0.44%   |
| Dell Inspiron 5558                         | 2         | 0.44%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA    | 2         | 0.44%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 2         | 0.44%   |
| Apple MacBookPro7,1                        | 2         | 0.44%   |
| Apple MacBookPro6,2                        | 2         | 0.44%   |
| Apple MacBookPro14,1                       | 2         | 0.44%   |
| Apple MacBookPro11,3                       | 2         | 0.44%   |
| Apple MacBook6,1                           | 2         | 0.44%   |
| Acer Swift SF314-43                        | 2         | 0.44%   |
| Acer Swift SF314-42                        | 2         | 0.44%   |
| Acer Swift SF114-34                        | 2         | 0.44%   |
| Acer Nitro AN515-55                        | 2         | 0.44%   |
| TUXEDO InfinityBook S 15 Gen6              | 1         | 0.22%   |
| Toshiba TECRA Z50-A                        | 1         | 0.22%   |
| Toshiba Satellite L855                     | 1         | 0.22%   |
| Toshiba Satellite L755                     | 1         | 0.22%   |
| Toshiba Satellite L12-C-104                | 1         | 0.22%   |
| Toshiba Satellite C855-12R                 | 1         | 0.22%   |
| Toshiba Satellite C70-A-K2W                | 1         | 0.22%   |
| Toshiba Satellite C660                     | 1         | 0.22%   |
| Toshiba Satellite C55-A-1NU                | 1         | 0.22%   |
| Toshiba NB255                              | 1         | 0.22%   |
| System76 Pangolin                          | 1         | 0.22%   |
| System76 Oryx Pro                          | 1         | 0.22%   |
| Sony VPCF131FM                             | 1         | 0.22%   |
| Sony VPCEB3PGX                             | 1         | 0.22%   |
| Sony SVE1713S1RW                           | 1         | 0.22%   |
| Sony SVE1711Z1RB                           | 1         | 0.22%   |
| SiComputer Nauta 01W PRO                   | 1         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Lenovo ThinkPad                         | 91        | 19.91%  |
| Lenovo IdeaPad                          | 32        | 7%      |
| Dell Latitude                           | 28        | 6.13%   |
| Dell Inspiron                           | 21        | 4.6%    |
| Dell XPS                                | 20        | 4.38%   |
| HP Pavilion                             | 14        | 3.06%   |
| Acer Aspire                             | 12        | 2.63%   |
| Acer Swift                              | 10        | 2.19%   |
| HP ProBook                              | 9         | 1.97%   |
| HP Laptop                               | 9         | 1.97%   |
| ASUS ROG                                | 9         | 1.97%   |
| Lenovo ThinkBook                        | 8         | 1.75%   |
| HP EliteBook                            | 8         | 1.75%   |
| Dell Precision                          | 8         | 1.75%   |
| ASUS VivoBook                           | 8         | 1.75%   |
| Toshiba Satellite                       | 7         | 1.53%   |
| Acer Nitro                              | 6         | 1.31%   |
| Lenovo Legion                           | 5         | 1.09%   |
| HP ZBook                                | 5         | 1.09%   |
| HP ENVY                                 | 5         | 1.09%   |
| ASUS ASUS                               | 5         | 1.09%   |
| Lenovo Yoga                             | 4         | 0.88%   |
| HUAWEI KLVL-WXX9                        | 3         | 0.66%   |
| Framework Laptop                        | 3         | 0.66%   |
| Dell Vostro                             | 3         | 0.66%   |
| Apple MacBookPro9                       | 3         | 0.66%   |
| Apple MacBookPro11                      | 3         | 0.66%   |
| Notebook NH5x                           | 2         | 0.44%   |
| MSI Modern                              | 2         | 0.44%   |
| HUAWEI HVY-WXX9                         | 2         | 0.44%   |
| HP OMEN                                 | 2         | 0.44%   |
| HP 15                                   | 2         | 0.44%   |
| Fujitsu LIFEBOOK                        | 2         | 0.44%   |
| ASUS ZenBook                            | 2         | 0.44%   |
| Apple MacBookPro7                       | 2         | 0.44%   |
| Apple MacBookPro6                       | 2         | 0.44%   |
| Apple MacBookPro14                      | 2         | 0.44%   |
| Apple MacBookAir6                       | 2         | 0.44%   |
| Apple MacBook6                          | 2         | 0.44%   |
| Acer Predator                           | 2         | 0.44%   |
| TUXEDO InfinityBook                     | 1         | 0.22%   |
| Toshiba TECRA                           | 1         | 0.22%   |
| Toshiba NB255                           | 1         | 0.22%   |
| System76 Pangolin                       | 1         | 0.22%   |
| System76 Oryx                           | 1         | 0.22%   |
| Sony VPCF131FM                          | 1         | 0.22%   |
| Sony VPCEB3PGX                          | 1         | 0.22%   |
| Sony SVE1713S1RW                        | 1         | 0.22%   |
| Sony SVE1711Z1RB                        | 1         | 0.22%   |
| SiComputer Nauta                        | 1         | 0.22%   |
| SCHNEIDER SCL141CTP                     | 1         | 0.22%   |
| Samsung RV411                           | 1         | 0.22%   |
| Samsung RV410                           | 1         | 0.22%   |
| Razer Book                              | 1         | 0.22%   |
| Razer Blade                             | 1         | 0.22%   |
| Positivo VJF155F11UAR                   | 1         | 0.22%   |
| Positivo V142N                          | 1         | 0.22%   |
| Positivo H14BU08                        | 1         | 0.22%   |
| Positivo Bahia - VAIO VJFE53F11X-XXXXXX | 1         | 0.22%   |
| Panasonic CF-195FYCALM                  | 1         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 92        | 20.13%  |
| 2021 | 72        | 15.75%  |
| 2019 | 58        | 12.69%  |
| 2018 | 53        | 11.6%   |
| 2016 | 33        | 7.22%   |
| 2017 | 32        | 7%      |
| 2013 | 23        | 5.03%   |
| 2015 | 19        | 4.16%   |
| 2012 | 19        | 4.16%   |
| 2014 | 18        | 3.94%   |
| 2011 | 15        | 3.28%   |
| 2010 | 13        | 2.84%   |
| 2008 | 5         | 1.09%   |
| 2009 | 4         | 0.88%   |
| 2007 | 1         | 0.22%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 457       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 358       | 78%     |
| Enabled  | 101       | 22%     |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 454       | 99.34%  |
| Yes  | 3         | 0.66%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 141       | 30.79%  |
| 16.01-24.0  | 114       | 24.89%  |
| 8.01-16.0   | 88        | 19.21%  |
| 32.01-64.0  | 55        | 12.01%  |
| 3.01-4.0    | 38        | 8.3%    |
| 64.01-256.0 | 8         | 1.75%   |
| 24.01-32.0  | 6         | 1.31%   |
| 1.01-2.0    | 6         | 1.31%   |
| 2.01-3.0    | 2         | 0.44%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 138       | 28.28%  |
| 2.01-3.0   | 135       | 27.66%  |
| 3.01-4.0   | 113       | 23.16%  |
| 1.01-2.0   | 63        | 12.91%  |
| 8.01-16.0  | 33        | 6.76%   |
| 16.01-24.0 | 3         | 0.61%   |
| 0.51-1.0   | 2         | 0.41%   |
| 24.01-32.0 | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 339       | 74.02%  |
| 2      | 99        | 21.62%  |
| 3      | 13        | 2.84%   |
| 0      | 3         | 0.66%   |
| 5      | 2         | 0.44%   |
| 6      | 1         | 0.22%   |
| 4      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 380       | 83.15%  |
| Yes       | 77        | 16.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 323       | 70.37%  |
| No        | 136       | 29.63%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 453       | 99.12%  |
| No        | 4         | 0.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 386       | 83.73%  |
| No        | 75        | 16.27%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| USA                   | 69        | 15.03%  |
| Russia                | 39        | 8.5%    |
| Brazil                | 32        | 6.97%   |
| Italy                 | 25        | 5.45%   |
| Germany               | 23        | 5.01%   |
| UK                    | 19        | 4.14%   |
| France                | 18        | 3.92%   |
| Canada                | 18        | 3.92%   |
| Poland                | 14        | 3.05%   |
| India                 | 12        | 2.61%   |
| Spain                 | 11        | 2.4%    |
| Netherlands           | 11        | 2.4%    |
| Czechia               | 9         | 1.96%   |
| Sweden                | 8         | 1.74%   |
| Norway                | 8         | 1.74%   |
| Austria               | 8         | 1.74%   |
| Portugal              | 7         | 1.53%   |
| Mexico                | 7         | 1.53%   |
| Belgium               | 7         | 1.53%   |
| Australia             | 7         | 1.53%   |
| Ukraine               | 6         | 1.31%   |
| Turkey                | 6         | 1.31%   |
| Indonesia             | 6         | 1.31%   |
| Greece                | 5         | 1.09%   |
| Denmark               | 5         | 1.09%   |
| Belarus               | 5         | 1.09%   |
| Switzerland           | 4         | 0.87%   |
| Romania               | 4         | 0.87%   |
| Finland               | 4         | 0.87%   |
| China                 | 4         | 0.87%   |
| Argentina             | 4         | 0.87%   |
| South Africa          | 3         | 0.65%   |
| Israel                | 3         | 0.65%   |
| Hungary               | 3         | 0.65%   |
| Georgia               | 3         | 0.65%   |
| Colombia              | 3         | 0.65%   |
| Venezuela             | 2         | 0.44%   |
| Saudi Arabia          | 2         | 0.44%   |
| New Zealand           | 2         | 0.44%   |
| Kazakhstan            | 2         | 0.44%   |
| Ireland               | 2         | 0.44%   |
| Iran                  | 2         | 0.44%   |
| Cyprus                | 2         | 0.44%   |
| Chile                 | 2         | 0.44%   |
| Algeria               | 2         | 0.44%   |
| Trinidad and Tobago   | 1         | 0.22%   |
| Taiwan                | 1         | 0.22%   |
| Slovenia              | 1         | 0.22%   |
| Singapore             | 1         | 0.22%   |
| Serbia                | 1         | 0.22%   |
| Philippines           | 1         | 0.22%   |
| Peru                  | 1         | 0.22%   |
| Palestinian Territory | 1         | 0.22%   |
| Palestine             | 1         | 0.22%   |
| Pakistan              | 1         | 0.22%   |
| Nigeria               | 1         | 0.22%   |
| Malaysia              | 1         | 0.22%   |
| Latvia                | 1         | 0.22%   |
| Kenya                 | 1         | 0.22%   |
| Japan                 | 1         | 0.22%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Moscow             | 17        | 3.62%   |
| Milan              | 7         | 1.49%   |
| S??o Paulo         | 6         | 1.28%   |
| Montreal           | 6         | 1.28%   |
| Istanbul           | 6         | 1.28%   |
| Vienna             | 5         | 1.06%   |
| St Petersburg      | 5         | 1.06%   |
| Madrid             | 5         | 1.06%   |
| Warsaw             | 4         | 0.85%   |
| Prague             | 4         | 0.85%   |
| Minsk              | 4         | 0.85%   |
| Helsinki           | 4         | 0.85%   |
| Zurich             | 3         | 0.64%   |
| Yekaterinburg      | 3         | 0.64%   |
| W?¶rgl             | 3         | 0.64%   |
| Sydney             | 3         | 0.64%   |
| Rotterdam          | 3         | 0.64%   |
| Rome               | 3         | 0.64%   |
| Nizhniy Novgorod   | 3         | 0.64%   |
| New Delhi          | 3         | 0.64%   |
| Kyiv               | 3         | 0.64%   |
| K'alak'i T'bilisi  | 3         | 0.64%   |
| Jakarta            | 3         | 0.64%   |
| East Longmeadow    | 3         | 0.64%   |
| Coimbatore         | 3         | 0.64%   |
| Chicago            | 3         | 0.64%   |
| Bucharest          | 3         | 0.64%   |
| Berlin             | 3         | 0.64%   |
| Athens             | 3         | 0.64%   |
| Ufa                | 2         | 0.43%   |
| Shenzhen           | 2         | 0.43%   |
| Seattle            | 2         | 0.43%   |
| Royse              | 2         | 0.43%   |
| Rio de Janeiro     | 2         | 0.43%   |
| Porto Alegre       | 2         | 0.43%   |
| Paris              | 2         | 0.43%   |
| Oslo               | 2         | 0.43%   |
| Olympia            | 2         | 0.43%   |
| Noyelles-sous-Lens | 2         | 0.43%   |
| Nova Russas        | 2         | 0.43%   |
| Munich             | 2         | 0.43%   |
| Mumbai             | 2         | 0.43%   |
| Mexico City        | 2         | 0.43%   |
| Mangawhai          | 2         | 0.43%   |
| Madison            | 2         | 0.43%   |
| Lubbock            | 2         | 0.43%   |
| Lodz               | 2         | 0.43%   |
| Lisbon             | 2         | 0.43%   |
| Lawrenceville      | 2         | 0.43%   |
| Krakow             | 2         | 0.43%   |
| Haifa              | 2         | 0.43%   |
| Fortaleza          | 2         | 0.43%   |
| Edmonton           | 2         | 0.43%   |
| Caracas            | 2         | 0.43%   |
| Buenos Aires       | 2         | 0.43%   |
| Brno               | 2         | 0.43%   |
| Bolzano            | 2         | 0.43%   |
| Belo Horizonte     | 2         | 0.43%   |
| Amsterdam          | 2         | 0.43%   |
| Zulte              | 1         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 130       | 170    | 22.89%  |
| WDC                          | 64        | 66     | 11.27%  |
| Toshiba                      | 42        | 43     | 7.39%   |
| Sandisk                      | 39        | 50     | 6.87%   |
| SK Hynix                     | 37        | 45     | 6.51%   |
| Seagate                      | 31        | 39     | 5.46%   |
| Unknown                      | 27        | 29     | 4.75%   |
| Kingston                     | 27        | 28     | 4.75%   |
| Intel                        | 26        | 30     | 4.58%   |
| Micron Technology            | 23        | 27     | 4.05%   |
| KIOXIA                       | 12        | 17     | 2.11%   |
| Crucial                      | 11        | 12     | 1.94%   |
| HGST                         | 10        | 10     | 1.76%   |
| Apple                        | 9         | 10     | 1.58%   |
| Transcend                    | 6         | 6      | 1.06%   |
| Phison                       | 6         | 6      | 1.06%   |
| LITEON                       | 6         | 6      | 1.06%   |
| A-DATA Technology            | 5         | 5      | 0.88%   |
| Corsair                      | 4         | 4      | 0.7%    |
| Silicon Motion               | 3         | 3      | 0.53%   |
| PLEXTOR                      | 3         | 3      | 0.53%   |
| Lexar                        | 3         | 3      | 0.53%   |
| China                        | 3         | 3      | 0.53%   |
| Unknown                      | 3         | 3      | 0.53%   |
| XPG                          | 2         | 2      | 0.35%   |
| PNY                          | 2         | 3      | 0.35%   |
| Patriot                      | 2         | 2      | 0.35%   |
| Mushkin                      | 2         | 2      | 0.35%   |
| LITEONIT                     | 2         | 2      | 0.35%   |
| HPE                          | 2         | 2      | 0.35%   |
| Hitachi                      | 2         | 2      | 0.35%   |
| ADATA Technology             | 2         | 2      | 0.35%   |
| YMTC                         | 1         | 1      | 0.18%   |
| WDC WDS                      | 1         | 1      | 0.18%   |
| USB3.1                       | 1         | 1      | 0.18%   |
| Union Memory (Shenzhen)      | 1         | 1      | 0.18%   |
| TO Exter                     | 1         | 1      | 0.18%   |
| Team                         | 1         | 1      | 0.18%   |
| TCSUNBOW                     | 1         | 1      | 0.18%   |
| SSSTC                        | 1         | 1      | 0.18%   |
| SSK                          | 1         | 1      | 0.18%   |
| SPCC                         | 1         | 1      | 0.18%   |
| Realtek Semiconductor        | 1         | 1      | 0.18%   |
| MX                           | 1         | 1      | 0.18%   |
| Mass                         | 1         | 1      | 0.18%   |
| LDLC                         | 1         | 1      | 0.18%   |
| LaCie                        | 1         | 2      | 0.18%   |
| Hewlett-Packard              | 1         | 1      | 0.18%   |
| Gigabyte Technology          | 1         | 1      | 0.18%   |
| FORESEE                      | 1         | 1      | 0.18%   |
| BIWIN                        | 1         | 1      | 0.18%   |
| Beijing Starblaze Technology | 1         | 1      | 0.18%   |
| ASMT                         | 1         | 1      | 0.18%   |
| AMicro                       | 1         | 1      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB            | 18        | 3.02%   |
| SK Hynix NVMe SSD Drive 512GB           | 8         | 1.34%   |
| Sandisk NVMe SSD Drive 256GB            | 8         | 1.34%   |
| Samsung NVMe SSD Drive 256GB            | 7         | 1.17%   |
| Unknown MMC Card  64GB                  | 6         | 1.01%   |
| Sandisk NVMe SSD Drive 512GB            | 6         | 1.01%   |
| Samsung NVMe SSD Drive 500GB            | 6         | 1.01%   |
| Kingston SA400S37480G 480GB SSD         | 6         | 1.01%   |
| WDC PC SN730 SDBQNTY-256G-1001 256GB    | 5         | 0.84%   |
| Samsung SSD 970 EVO Plus 1TB            | 5         | 0.84%   |
| Samsung NVMe SSD Drive 1024GB           | 5         | 0.84%   |
| Intel NVMe SSD Drive 512GB              | 5         | 0.84%   |
| Toshiba NVMe SSD Drive 512GB            | 4         | 0.67%   |
| SK Hynix NVMe SSD Drive 256GB           | 4         | 0.67%   |
| Seagate ST1000LM048-2E7172 1TB          | 4         | 0.67%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 4         | 0.67%   |
| Seagate ST1000LM014-1EJ164 1TB          | 4         | 0.67%   |
| Sandisk NVMe SSD Drive 500GB            | 4         | 0.67%   |
| Samsung SSD 850 EVO 250GB               | 4         | 0.67%   |
| Samsung NVMe SSD Drive 2TB              | 4         | 0.67%   |
| Kingston SA400S37120G 120GB SSD         | 4         | 0.67%   |
| HGST HTS721010A9E630 1TB                | 4         | 0.67%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.5%    |
| Unknown MMC Card  32GB                  | 3         | 0.5%    |
| Toshiba MQ04ABF100 1TB                  | 3         | 0.5%    |
| Toshiba KXG6AZNV256G 256GB              | 3         | 0.5%    |
| Toshiba KBG30ZMS128G 128GB NVMe SSD     | 3         | 0.5%    |
| SK Hynix BC711 NVMe 512GB               | 3         | 0.5%    |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 0.5%    |
| Sandisk NVMe SSD Drive 1TB              | 3         | 0.5%    |
| Samsung SSD 980 PRO 500GB               | 3         | 0.5%    |
| Samsung SSD 970 EVO Plus 2TB            | 3         | 0.5%    |
| Samsung SSD 860 EVO 500GB               | 3         | 0.5%    |
| Samsung SSD 860 EVO 2TB                 | 3         | 0.5%    |
| Samsung SSD 860 EVO 250GB               | 3         | 0.5%    |
| Samsung NVMe SSD Drive 1TB              | 3         | 0.5%    |
| Samsung MZVLB1T0HBLR-000L7 1TB          | 3         | 0.5%    |
| Phison 311CD0512GB                      | 3         | 0.5%    |
| KIOXIA NVMe SSD Drive 512GB             | 3         | 0.5%    |
| HGST HTS725050A7E630 500GB              | 3         | 0.5%    |
| Unknown                                 | 3         | 0.5%    |
| WDC WDS500G2B0B-00YS70 500GB SSD        | 2         | 0.34%   |
| WDC WD5000LPLX-08ZNTT0 500GB            | 2         | 0.34%   |
| WDC WD3200BPVT-22JJ5T0 320GB            | 2         | 0.34%   |
| WDC WD16 00BEVT-60ZCT 160GB             | 2         | 0.34%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB    | 2         | 0.34%   |
| WDC PC SN720 SDAQNTW-512G-1001 512GB    | 2         | 0.34%   |
| WDC PC SN530 SDBPMPZ-256G-1101 256GB    | 2         | 0.34%   |
| Unknown USB DISK 3.2 1TB                | 2         | 0.34%   |
| Unknown SD128  128GB                    | 2         | 0.34%   |
| Unknown MMC Card  8GB                   | 2         | 0.34%   |
| Unknown MMC Card  128GB                 | 2         | 0.34%   |
| Transcend TS120GMTS420S 120GB SSD       | 2         | 0.34%   |
| Toshiba MQ01ABF050 500GB                | 2         | 0.34%   |
| Toshiba MQ01ABD100 1TB                  | 2         | 0.34%   |
| Toshiba MQ01ABD075 752GB                | 2         | 0.34%   |
| Toshiba MK5061GSYN 500GB                | 2         | 0.34%   |
| Toshiba KXG6AZNV512G 512GB              | 2         | 0.34%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD | 2         | 0.34%   |
| SK Hynix PC401 NVMe 512GB               | 2         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 31        | 39     | 32.63%  |
| WDC                 | 30        | 30     | 31.58%  |
| Toshiba             | 18        | 19     | 18.95%  |
| HGST                | 10        | 10     | 10.53%  |
| Hitachi             | 2         | 2      | 2.11%   |
| TO Exter            | 1         | 1      | 1.05%   |
| Samsung Electronics | 1         | 1      | 1.05%   |
| LaCie               | 1         | 2      | 1.05%   |
| Apple               | 1         | 1      | 1.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 45        | 59     | 27.61%  |
| Kingston            | 17        | 17     | 10.43%  |
| SanDisk             | 15        | 21     | 9.2%    |
| Crucial             | 10        | 11     | 6.13%   |
| WDC                 | 8         | 8      | 4.91%   |
| Intel               | 8         | 8      | 4.91%   |
| Micron Technology   | 6         | 7      | 3.68%   |
| Apple               | 6         | 6      | 3.68%   |
| Transcend           | 5         | 5      | 3.07%   |
| Toshiba             | 5         | 5      | 3.07%   |
| LITEON              | 4         | 4      | 2.45%   |
| SK Hynix            | 3         | 3      | 1.84%   |
| China               | 3         | 3      | 1.84%   |
| A-DATA Technology   | 3         | 3      | 1.84%   |
| PNY                 | 2         | 3      | 1.23%   |
| PLEXTOR             | 2         | 2      | 1.23%   |
| Patriot             | 2         | 2      | 1.23%   |
| Mushkin             | 2         | 2      | 1.23%   |
| LITEONIT            | 2         | 2      | 1.23%   |
| Lexar               | 2         | 2      | 1.23%   |
| Corsair             | 2         | 2      | 1.23%   |
| WDC WDS             | 1         | 1      | 0.61%   |
| Unknown             | 1         | 1      | 0.61%   |
| TCSUNBOW            | 1         | 1      | 0.61%   |
| SPCC                | 1         | 1      | 0.61%   |
| MX                  | 1         | 1      | 0.61%   |
| HPE                 | 1         | 1      | 0.61%   |
| Hewlett-Packard     | 1         | 1      | 0.61%   |
| Gigabyte Technology | 1         | 1      | 0.61%   |
| FORESEE             | 1         | 1      | 0.61%   |
| BIWIN               | 1         | 1      | 0.61%   |
| ASMT                | 1         | 1      | 0.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 263       | 329    | 48.52%  |
| SSD     | 153       | 186    | 28.23%  |
| HDD     | 91        | 105    | 16.79%  |
| MMC     | 26        | 28     | 4.8%    |
| Unknown | 9         | 10     | 1.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 263       | 329    | 50.67%  |
| SATA | 211       | 277    | 40.66%  |
| MMC  | 26        | 28     | 5.01%   |
| SAS  | 19        | 24     | 3.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 160       | 182    | 65.31%  |
| 0.51-1.0   | 69        | 86     | 28.16%  |
| 1.01-2.0   | 15        | 22     | 6.12%   |
| 3.01-4.0   | 1         | 1      | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 88        | 19.13%  |
| 501-1000       | 85        | 18.48%  |
| 1-20           | 82        | 17.83%  |
| 101-250        | 74        | 16.09%  |
| Unknown        | 50        | 10.87%  |
| 1001-2000      | 41        | 8.91%   |
| 51-100         | 17        | 3.7%    |
| More than 3000 | 9         | 1.96%   |
| 21-50          | 8         | 1.74%   |
| 2001-3000      | 6         | 1.3%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 159       | 33.69%  |
| 21-50          | 75        | 15.89%  |
| 101-250        | 71        | 15.04%  |
| 51-100         | 50        | 10.59%  |
| Unknown        | 50        | 10.59%  |
| 251-500        | 35        | 7.42%   |
| 501-1000       | 21        | 4.45%   |
| 1001-2000      | 10        | 2.12%   |
| More than 3000 | 1         | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 4      | 12.5%   |
| WDC WD1600BEVT-24A23T0 160GB                        | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 6.25%   |
| Toshiba MQ01ABD050V 500GB                           | 1         | 1      | 6.25%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD             | 1         | 1      | 6.25%   |
| SK Hynix HFS128G39TND-N210A 128GB SSD               | 1         | 1      | 6.25%   |
| Samsung Electronics MZNLH256HAJD-000H1 256GB SSD    | 1         | 1      | 6.25%   |
| PLEXTOR PX-256M8PeG 256GB                           | 1         | 1      | 6.25%   |
| Micron Technology MTFDDAK256MAY-1AH12ABHA 256GB SSD | 1         | 2      | 6.25%   |
| LITEON CV3-CE256 256GB SSD                          | 1         | 1      | 6.25%   |
| Hitachi HTS545025B9SA02 250GB                       | 1         | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 6.25%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 6.25%   |
| Crucial CT1050MX300SSD1 1050GB                      | 1         | 1      | 6.25%   |
| Crucial CT1000P1SSD8 1TB                            | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 3         | 3      | 18.75%  |
| Seagate             | 2         | 4      | 12.5%   |
| HGST                | 2         | 2      | 12.5%   |
| Crucial             | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| SK Hynix            | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| PLEXTOR             | 1         | 1      | 6.25%   |
| Micron Technology   | 1         | 2      | 6.25%   |
| LITEON              | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 2      | 25%     |
| Seagate | 2         | 4      | 25%     |
| HGST    | 2         | 2      | 25%     |
| WDC     | 1         | 1      | 12.5%   |
| Hitachi | 1         | 1      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 8         | 10     | 50%     |
| SSD  | 6         | 7      | 37.5%   |
| NVMe | 2         | 2      | 12.5%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Notebooks | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB | 1         | 1      | 100%    |

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
| Detected | 244       | 350    | 49.8%   |
| Works    | 229       | 288    | 46.73%  |
| Malfunc  | 16        | 19     | 3.27%   |
| Failed   | 1         | 1      | 0.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 264       | 45.83%  |
| Samsung Electronics            | 89        | 15.45%  |
| AMD                            | 49        | 8.51%   |
| Sandisk                        | 48        | 8.33%   |
| SK Hynix                       | 34        | 5.9%    |
| Toshiba America Info Systems   | 21        | 3.65%   |
| Micron Technology              | 17        | 2.95%   |
| Kingston Technology Company    | 10        | 1.74%   |
| KIOXIA                         | 9         | 1.56%   |
| Phison Electronics             | 7         | 1.22%   |
| Silicon Motion                 | 5         | 0.87%   |
| Nvidia                         | 5         | 0.87%   |
| ADATA Technology               | 5         | 0.87%   |
| Lite-On Technology             | 3         | 0.52%   |
| Realtek Semiconductor          | 2         | 0.35%   |
| Marvell Technology Group       | 2         | 0.35%   |
| Yangtze Memory Technologies    | 1         | 0.17%   |
| Union Memory (Shenzhen)        | 1         | 0.17%   |
| Solid State Storage Technology | 1         | 0.17%   |
| Micron/Crucial Technology      | 1         | 0.17%   |
| Beijing Starblaze Technology   | 1         | 0.17%   |
| Apple                          | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 53        | 8.88%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 46        | 7.71%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 45        | 7.54%   |
| Samsung NVMe SSD Controller 980                                                  | 23        | 3.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 23        | 3.85%   |
| Intel Volume Management Device NVMe RAID Controller                              | 21        | 3.52%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 20        | 3.35%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 18        | 3.02%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 18        | 3.02%   |
| Micron Non-Volatile memory controller                                            | 17        | 2.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 15        | 2.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 15        | 2.51%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 15        | 2.51%   |
| SK Hynix Gold P31 SSD                                                            | 14        | 2.35%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 12        | 2.01%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 11        | 1.84%   |
| Sandisk Non-Volatile memory controller                                           | 10        | 1.68%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 9         | 1.51%   |
| KIOXIA Non-Volatile memory controller                                            | 9         | 1.51%   |
| Intel SSD 660P Series                                                            | 9         | 1.51%   |
| SK Hynix Non-Volatile memory controller                                          | 8         | 1.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 8         | 1.34%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 7         | 1.17%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 1.17%   |
| Intel Comet Lake SATA AHCI Controller                                            | 7         | 1.17%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 6         | 1.01%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                      | 5         | 0.84%   |
| SK Hynix BC511                                                                   | 5         | 0.84%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 0.84%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 5         | 0.84%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 5         | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 5         | 0.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 5         | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 5         | 0.84%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 4         | 0.67%   |
| Sandisk PC SN520 NVMe SSD                                                        | 4         | 0.67%   |
| Phison PS5013 E13 NVMe Controller                                                | 4         | 0.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 4         | 0.67%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 4         | 0.67%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.5%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 0.5%    |
| Sandisk WD PC SN810 / Black SN850 NVMe SSD                                       | 3         | 0.5%    |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.5%    |
| Phison E12 NVMe Controller                                                       | 3         | 0.5%    |
| Nvidia MCP79 AHCI Controller                                                     | 3         | 0.5%    |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 0.5%    |
| Intel Non-Volatile memory controller                                             | 3         | 0.5%    |
| ADATA Non-Volatile memory controller                                             | 3         | 0.5%    |
| SK Hynix BC501 NVMe Solid State Drive                                            | 2         | 0.34%   |
| Samsung Electronics SATA controller                                              | 2         | 0.34%   |
| Samsung Apple PCIe SSD                                                           | 2         | 0.34%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                         | 2         | 0.34%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                       | 2         | 0.34%   |
| Lite-On Lite-On Non-Volatile memory controller                                   | 2         | 0.34%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.34%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 2         | 0.34%   |
| Kingston Company A2000 NVMe SSD                                                  | 2         | 0.34%   |
| Intel SATA Controller [RAID mode]                                                | 2         | 0.34%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.34%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 2         | 0.34%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 271       | 46.64%  |
| NVMe | 261       | 44.92%  |
| RAID | 43        | 7.4%    |
| IDE  | 6         | 1.03%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 366       | 80.09%  |
| AMD    | 91        | 19.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 3.94%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 3.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 12        | 2.63%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 2.19%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 10        | 2.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 10        | 2.19%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 2.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 1.97%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 8         | 1.75%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 1.53%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 7         | 1.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 1.53%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 1.53%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.31%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 6         | 1.31%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 6         | 1.31%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 6         | 1.31%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 6         | 1.31%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 6         | 1.31%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 5         | 1.09%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 5         | 1.09%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 1.09%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 1.09%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 5         | 1.09%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 1.09%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 5         | 1.09%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 0.88%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 4         | 0.88%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.88%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.88%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 0.88%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 4         | 0.88%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 4         | 0.88%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 4         | 0.88%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 4         | 0.88%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.88%   |
| Intel Core i7-9850H CPU @ 2.60GHz             | 3         | 0.66%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 3         | 0.66%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 3         | 0.66%   |
| Intel Core i7-3520M CPU @ 2.90GHz             | 3         | 0.66%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.66%   |
| Intel Core i5-6440HQ CPU @ 2.60GHz            | 3         | 0.66%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 3         | 0.66%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 0.66%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 0.66%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 3         | 0.66%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 0.66%   |
| Intel 11th Gen Core i7-11370H @ 3.30GHz       | 3         | 0.66%   |
| AMD Ryzen 9 5900HS with Radeon Graphics       | 3         | 0.66%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 3         | 0.66%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.66%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 2         | 0.44%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 2         | 0.44%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 2         | 0.44%   |
| Intel Core i9-10885H CPU @ 2.40GHz            | 2         | 0.44%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 2         | 0.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.44%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.44%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 147       | 32.17%  |
| Intel Core i5           | 98        | 21.44%  |
| Other                   | 48        | 10.5%   |
| AMD Ryzen 5             | 32        | 7%      |
| Intel Core i3           | 31        | 6.78%   |
| AMD Ryzen 7             | 24        | 5.25%   |
| Intel Celeron           | 11        | 2.41%   |
| Intel Core 2 Duo        | 10        | 2.19%   |
| AMD Ryzen 9             | 10        | 2.19%   |
| AMD Ryzen 7 PRO         | 6         | 1.31%   |
| Intel Pentium Silver    | 5         | 1.09%   |
| Intel Atom              | 5         | 1.09%   |
| AMD Ryzen 3             | 5         | 1.09%   |
| Intel Pentium           | 4         | 0.88%   |
| Intel Core i9           | 4         | 0.88%   |
| AMD Ryzen 5 PRO         | 2         | 0.44%   |
| AMD A6                  | 2         | 0.44%   |
| Intel Pentium Dual-Core | 1         | 0.22%   |
| Intel Pentium Dual      | 1         | 0.22%   |
| Intel Core m7           | 1         | 0.22%   |
| Intel Core m3           | 1         | 0.22%   |
| AMD PRO A10             | 1         | 0.22%   |
| AMD E1                  | 1         | 0.22%   |
| AMD E                   | 1         | 0.22%   |
| AMD C-60                | 1         | 0.22%   |
| AMD Athlon II           | 1         | 0.22%   |
| AMD Athlon              | 1         | 0.22%   |
| AMD A8                  | 1         | 0.22%   |
| AMD A4                  | 1         | 0.22%   |
| AMD A10                 | 1         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 205       | 44.86%  |
| 2      | 149       | 32.6%   |
| 6      | 55        | 12.04%  |
| 8      | 44        | 9.63%   |
| 1      | 2         | 0.44%   |
| 12     | 1         | 0.22%   |
| 10     | 1         | 0.22%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 457       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 391       | 85.56%  |
| 1      | 66        | 14.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 457       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806c1    | 42        | 9.13%   |
| 0x806ec    | 37        | 8.04%   |
| 0x806ea    | 30        | 6.52%   |
| 0x406e3    | 22        | 4.78%   |
| 0x306a9    | 22        | 4.78%   |
| 0xa0652    | 21        | 4.57%   |
| 0x806e9    | 20        | 4.35%   |
| Unknown    | 20        | 4.35%   |
| 0x906ea    | 19        | 4.13%   |
| 0x40651    | 18        | 3.91%   |
| 0x206a7    | 16        | 3.48%   |
| 0x08600106 | 16        | 3.48%   |
| 0x0a50000c | 15        | 3.26%   |
| 0x306c3    | 12        | 2.61%   |
| 0x706e5    | 11        | 2.39%   |
| 0x08608103 | 11        | 2.39%   |
| 0x08600104 | 11        | 2.39%   |
| 0x08108109 | 10        | 2.17%   |
| 0x506e3    | 9         | 1.96%   |
| 0x306d4    | 9         | 1.96%   |
| 0x1067a    | 7         | 1.52%   |
| 0x08608102 | 7         | 1.52%   |
| 0x906ed    | 6         | 1.3%    |
| 0x506c9    | 6         | 1.3%    |
| 0x706a8    | 5         | 1.09%   |
| 0x806eb    | 4         | 0.87%   |
| 0x20655    | 4         | 0.87%   |
| 0x906e9    | 3         | 0.65%   |
| 0x406c4    | 3         | 0.65%   |
| 0x40661    | 3         | 0.65%   |
| 0x10676    | 3         | 0.65%   |
| 0x06001119 | 3         | 0.65%   |
| 0x906c0    | 2         | 0.43%   |
| 0x806d1    | 2         | 0.43%   |
| 0x806c2    | 2         | 0.43%   |
| 0x406c3    | 2         | 0.43%   |
| 0x30678    | 2         | 0.43%   |
| 0x20652    | 2         | 0.43%   |
| 0x08108102 | 2         | 0.43%   |
| 0x0810100b | 2         | 0.43%   |
| 0x0700010b | 2         | 0.43%   |
| 0xa0660    | 1         | 0.22%   |
| 0xa0655    | 1         | 0.22%   |
| 0x906eb    | 1         | 0.22%   |
| 0x706a1    | 1         | 0.22%   |
| 0x6fd      | 1         | 0.22%   |
| 0x6fa      | 1         | 0.22%   |
| 0x106ca    | 1         | 0.22%   |
| 0x08701013 | 1         | 0.22%   |
| 0x08600102 | 1         | 0.22%   |
| 0x08200103 | 1         | 0.22%   |
| 0x08101016 | 1         | 0.22%   |
| 0x08101007 | 1         | 0.22%   |
| 0x07030105 | 1         | 0.22%   |
| 0x0600611a | 1         | 0.22%   |
| 0x0500010d | 1         | 0.22%   |
| 0x05000101 | 1         | 0.22%   |
| 0x010000c8 | 1         | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 124       | 27.13%  |
| TigerLake     | 44        | 9.63%   |
| Skylake       | 34        | 7.44%   |
| Haswell       | 34        | 7.44%   |
| Zen 2         | 29        | 6.35%   |
| IvyBridge     | 24        | 5.25%   |
| CometLake     | 24        | 5.25%   |
| Unknown       | 19        | 4.16%   |
| SandyBridge   | 17        | 3.72%   |
| Zen 3         | 16        | 3.5%    |
| Zen+          | 13        | 2.84%   |
| IceLake       | 13        | 2.84%   |
| Penryn        | 10        | 2.19%   |
| Broadwell     | 9         | 1.97%   |
| Silvermont    | 8         | 1.75%   |
| Westmere      | 7         | 1.53%   |
| Goldmont plus | 6         | 1.31%   |
| Goldmont      | 6         | 1.31%   |
| Zen           | 5         | 1.09%   |
| Piledriver    | 3         | 0.66%   |
| Tremont       | 2         | 0.44%   |
| Jaguar        | 2         | 0.44%   |
| Core          | 2         | 0.44%   |
| Bobcat        | 2         | 0.44%   |
| Puma          | 1         | 0.22%   |
| K10           | 1         | 0.22%   |
| Excavator     | 1         | 0.22%   |
| Bonnell       | 1         | 0.22%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 344       | 57.82%  |
| Nvidia | 146       | 24.54%  |
| AMD    | 105       | 17.65%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 39        | 6.44%   |
| Intel UHD Graphics 620                                                                   | 32        | 5.28%   |
| AMD Renoir                                                                               | 28        | 4.62%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 25        | 4.13%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 22        | 3.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 22        | 3.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 21        | 3.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 20        | 3.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 20        | 3.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 3.14%   |
| AMD Lucienne                                                                             | 18        | 2.97%   |
| Intel HD Graphics 620                                                                    | 16        | 2.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 2.31%   |
| AMD Cezanne                                                                              | 14        | 2.31%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12        | 1.98%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 11        | 1.82%   |
| Intel HD Graphics 530                                                                    | 10        | 1.65%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 10        | 1.65%   |
| Intel HD Graphics 5500                                                                   | 8         | 1.32%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 1.16%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 7         | 1.16%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 6         | 0.99%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.99%   |
| Nvidia GP108M [GeForce MX250]                                                            | 6         | 0.99%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.83%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.83%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 0.83%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 4         | 0.66%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 4         | 0.66%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 4         | 0.66%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.66%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 0.66%   |
| Intel HD Graphics 500                                                                    | 4         | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.66%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT / 6800M]                                             | 4         | 0.66%   |
| Nvidia GP108M [GeForce MX330]                                                            | 3         | 0.5%    |
| Nvidia GM108M [GeForce 930MX]                                                            | 3         | 0.5%    |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.5%    |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.5%    |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 0.5%    |
| Nvidia GK208BM [GeForce 920M]                                                            | 3         | 0.5%    |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 0.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 0.5%    |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.5%    |
| Intel HD Graphics 630                                                                    | 3         | 0.5%    |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3         | 0.5%    |
| Nvidia TU117M [GeForce MX450]                                                            | 2         | 0.33%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile / Max-Q Refresh]                                  | 2         | 0.33%   |
| Nvidia TU106M [GeForce RTX 2060 Max-Q]                                                   | 2         | 0.33%   |
| Nvidia TU104M [GeForce RTX 2080 SUPER Mobile / Max-Q]                                    | 2         | 0.33%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.33%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.33%   |
| Nvidia GP107GLM [Quadro P620]                                                            | 2         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 222       | 48.58%  |
| Intel + Nvidia | 110       | 24.07%  |
| 1 x AMD        | 69        | 15.1%   |
| 1 x Nvidia     | 21        | 4.6%    |
| AMD + Nvidia   | 15        | 3.28%   |
| Intel + AMD    | 11        | 2.41%   |
| 2 x AMD        | 9         | 1.97%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 391       | 84.82%  |
| Proprietary | 68        | 14.75%  |
| Unknown     | 2         | 0.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 290       | 62.91%  |
| 1.01-2.0   | 57        | 12.36%  |
| 0.01-0.5   | 56        | 12.15%  |
| 3.01-4.0   | 24        | 5.21%   |
| 0.51-1.0   | 18        | 3.9%    |
| 7.01-8.0   | 5         | 1.08%   |
| 5.01-6.0   | 5         | 1.08%   |
| 8.01-16.0  | 4         | 0.87%   |
| 2.01-3.0   | 2         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 97        | 17.41%  |
| Chimei Innolux          | 84        | 15.08%  |
| LG Display              | 79        | 14.18%  |
| BOE                     | 79        | 14.18%  |
| Samsung Electronics     | 32        | 5.75%   |
| Sharp                   | 25        | 4.49%   |
| Dell                    | 24        | 4.31%   |
| Apple                   | 19        | 3.41%   |
| Lenovo                  | 16        | 2.87%   |
| Goldstar                | 11        | 1.97%   |
| Philips                 | 10        | 1.8%    |
| PANDA                   | 8         | 1.44%   |
| InfoVision              | 8         | 1.44%   |
| Hewlett-Packard         | 8         | 1.44%   |
| BenQ                    | 8         | 1.44%   |
| CSO                     | 7         | 1.26%   |
| AOC                     | 7         | 1.26%   |
| Acer                    | 5         | 0.9%    |
| TMX                     | 4         | 0.72%   |
| Iiyama                  | 4         | 0.72%   |
| Chi Mei Optoelectronics | 4         | 0.72%   |
| ASUSTek Computer        | 3         | 0.54%   |
| ViewSonic               | 2         | 0.36%   |
| JRY                     | 2         | 0.36%   |
| Ancor Communications    | 2         | 0.36%   |
| TIANMA XM               | 1         | 0.18%   |
| Sony                    | 1         | 0.18%   |
| Panasonic               | 1         | 0.18%   |
| MSI                     | 1         | 0.18%   |
| JDI                     | 1         | 0.18%   |
| InnoLux Display         | 1         | 0.18%   |
| HUAWEI                  | 1         | 0.18%   |
| Hitachi                 | 1         | 0.18%   |
| Gigabyte Technology     | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 10        | 1.76%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 5         | 0.88%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 4         | 0.7%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 4         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 4         | 0.7%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 4         | 0.7%    |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch     | 4         | 0.7%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 4         | 0.7%    |
| BOE LCD Monitor BOE0853 1920x1080 344x194mm 15.5-inch                | 4         | 0.7%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 4         | 0.7%    |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 4         | 0.7%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 4         | 0.7%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 3         | 0.53%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 3         | 0.53%   |
| LG Display LCD Monitor LGD062C 1920x1080 309x174mm 14.0-inch         | 3         | 0.53%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch         | 3         | 0.53%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 3         | 0.53%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 3         | 0.53%   |
| Goldstar LG FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch            | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch     | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch     | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 3         | 0.53%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 3         | 0.53%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 3         | 0.53%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 3         | 0.53%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 3         | 0.53%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 3         | 0.53%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                 | 3         | 0.53%   |
| TMX TL156VDXP01 TMX1560 1920x1080 344x194mm 15.5-inch                | 2         | 0.35%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch              | 2         | 0.35%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch              | 2         | 0.35%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch              | 2         | 0.35%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch              | 2         | 0.35%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 2         | 0.35%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 2         | 0.35%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch              | 2         | 0.35%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 2         | 0.35%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch              | 2         | 0.35%   |
| LG Display LCD Monitor LGD0625 1920x1080 344x194mm 15.5-inch         | 2         | 0.35%   |
| LG Display LCD Monitor LGD061A 1920x1080 344x194mm 15.5-inch         | 2         | 0.35%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch         | 2         | 0.35%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch         | 2         | 0.35%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 2         | 0.35%   |
| LG Display LCD Monitor LGD04B1 1366x768 310x174mm 14.0-inch          | 2         | 0.35%   |
| LG Display LCD Monitor LGD03CD 1366x768 277x156mm 12.5-inch          | 2         | 0.35%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch          | 2         | 0.35%   |
| LG Display LCD Monitor LGD02E2 1600x900 310x174mm 14.0-inch          | 2         | 0.35%   |
| LG Display LCD Monitor LGD028E 1366x768 310x174mm 14.0-inch          | 2         | 0.35%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch             | 2         | 0.35%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch              | 2         | 0.35%   |
| InfoVision LCD Monitor IVO057C 1366x768 310x170mm 13.9-inch          | 2         | 0.35%   |
| Dell U2412M DELA079 1920x1200 518x324mm 24.1-inch                    | 2         | 0.35%   |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                    | 2         | 0.35%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                    | 2         | 0.35%   |
| CSO LCD Monitor CSO1303 2160x1350 280x175mm 13.0-inch                | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1604 1920x1080 355x199mm 16.0-inch     | 2         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 2         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 282       | 54.55%  |
| 1366x768 (WXGA)    | 86        | 16.63%  |
| 3840x2160 (4K)     | 30        | 5.8%    |
| 2560x1440 (QHD)    | 28        | 5.42%   |
| 1920x1200 (WUXGA)  | 16        | 3.09%   |
| 2560x1600          | 9         | 1.74%   |
| 1600x900 (HD+)     | 9         | 1.74%   |
| 1280x800 (WXGA)    | 9         | 1.74%   |
| 1440x900 (WXGA+)   | 7         | 1.35%   |
| 3440x1440          | 6         | 1.16%   |
| 2880x1800          | 5         | 0.97%   |
| 3840x2400          | 4         | 0.77%   |
| 2160x1440          | 4         | 0.77%   |
| 2256x1504          | 3         | 0.58%   |
| 1680x1050 (WSXGA+) | 3         | 0.58%   |
| 3200x2000          | 2         | 0.39%   |
| 3200x1800 (QHD+)   | 2         | 0.39%   |
| 3000x2000          | 2         | 0.39%   |
| 2560x1080          | 2         | 0.39%   |
| 2160x1350          | 2         | 0.39%   |
| 1280x1024 (SXGA)   | 2         | 0.39%   |
| 3840x2560          | 1         | 0.19%   |
| 3072x1920          | 1         | 0.19%   |
| 2240x1400          | 1         | 0.19%   |
| 1024x600           | 1         | 0.19%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 193       | 34.28%  |
| 13     | 104       | 18.47%  |
| 14     | 92        | 16.34%  |
| 27     | 31        | 5.51%   |
| 24     | 26        | 4.62%   |
| 17     | 23        | 4.09%   |
| 23     | 17        | 3.02%   |
| 21     | 16        | 2.84%   |
| 12     | 14        | 2.49%   |
| 16     | 9         | 1.6%    |
| 11     | 8         | 1.42%   |
| 34     | 7         | 1.24%   |
| 31     | 5         | 0.89%   |
| 40     | 3         | 0.53%   |
| 19     | 3         | 0.53%   |
| 22     | 2         | 0.36%   |
| 10     | 2         | 0.36%   |
| 84     | 1         | 0.18%   |
| 43     | 1         | 0.18%   |
| 35     | 1         | 0.18%   |
| 29     | 1         | 0.18%   |
| 28     | 1         | 0.18%   |
| 26     | 1         | 0.18%   |
| 25     | 1         | 0.18%   |
| 18     | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 340       | 61.04%  |
| 201-300     | 75        | 13.46%  |
| 501-600     | 67        | 12.03%  |
| 351-400     | 30        | 5.39%   |
| 401-500     | 21        | 3.77%   |
| 601-700     | 11        | 1.97%   |
| 701-800     | 7         | 1.26%   |
| 801-900     | 4         | 0.72%   |
| 1501-2000   | 1         | 0.18%   |
| 901-1000    | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 393       | 82.74%  |
| 16/10 | 62        | 13.05%  |
| 3/2   | 10        | 2.11%   |
| 21/9  | 8         | 1.68%   |
| 5/4   | 2         | 0.42%   |

Monitor Area
------------

Area in inchÂ²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inchÂ² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 196       | 34.88%  |
| 81-90          | 157       | 27.94%  |
| 201-250        | 48        | 8.54%   |
| 71-80          | 39        | 6.94%   |
| 301-350        | 32        | 5.69%   |
| 121-130        | 23        | 4.09%   |
| 351-500        | 15        | 2.67%   |
| 61-70          | 14        | 2.49%   |
| 251-300        | 10        | 1.78%   |
| 51-60          | 8         | 1.42%   |
| 151-200        | 6         | 1.07%   |
| 111-120        | 6         | 1.07%   |
| 501-1000       | 4         | 0.71%   |
| 41-50          | 2         | 0.36%   |
| More than 1000 | 1         | 0.18%   |
| 141-150        | 1         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 275       | 50.55%  |
| 101-120       | 106       | 19.49%  |
| 51-100        | 71        | 13.05%  |
| 161-240       | 68        | 12.5%   |
| More than 240 | 24        | 4.41%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 346       | 75.05%  |
| 2     | 93        | 20.17%  |
| 3     | 15        | 3.25%   |
| 0     | 7         | 1.52%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 293       | 43.09%  |
| Realtek Semiconductor             | 214       | 31.47%  |
| Qualcomm Atheros                  | 60        | 8.82%   |
| Broadcom                          | 26        | 3.82%   |
| MEDIATEK                          | 18        | 2.65%   |
| Lenovo                            | 10        | 1.47%   |
| Broadcom Limited                  | 6         | 0.88%   |
| TP-Link                           | 5         | 0.74%   |
| Ralink                            | 5         | 0.74%   |
| Dell                              | 5         | 0.74%   |
| Sierra Wireless                   | 4         | 0.59%   |
| Qualcomm                          | 4         | 0.59%   |
| DisplayLink                       | 4         | 0.59%   |
| Ralink Technology                 | 3         | 0.44%   |
| Nvidia                            | 3         | 0.44%   |
| Marvell Technology Group          | 3         | 0.44%   |
| Xiaomi                            | 2         | 0.29%   |
| Linksys                           | 2         | 0.29%   |
| Fibocom                           | 2         | 0.29%   |
| Spreadtrum Communications         | 1         | 0.15%   |
| Shenzhen Goodix Technology        | 1         | 0.15%   |
| Samsung Electronics               | 1         | 0.15%   |
| Qualcomm Atheros Communications   | 1         | 0.15%   |
| OPPO Electronics                  | 1         | 0.15%   |
| NetGear                           | 1         | 0.15%   |
| Hewlett-Packard                   | 1         | 0.15%   |
| Ericsson Business Mobile Networks | 1         | 0.15%   |
| D-Link                            | 1         | 0.15%   |
| Cypress Semiconductor             | 1         | 0.15%   |
| ASIX Electronics                  | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 130       | 15.55%  |
| Intel Wi-Fi 6 AX200                                               | 42        | 5.02%   |
| Intel Wi-Fi 6 AX201                                               | 32        | 3.83%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 31        | 3.71%   |
| Intel Wireless 8265 / 8275                                        | 25        | 2.99%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 22        | 2.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 20        | 2.39%   |
| Intel Wireless 8260                                               | 19        | 2.27%   |
| Intel Wireless 7260                                               | 19        | 2.27%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 19        | 2.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 18        | 2.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 16        | 1.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 15        | 1.79%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter     | 13        | 1.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 13        | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 11        | 1.32%   |
| Intel Wireless 7265                                               | 10        | 1.2%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 10        | 1.2%    |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 1.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10        | 1.2%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.08%   |
| Intel Wireless 3165                                               | 9         | 1.08%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 1.08%   |
| Intel Ethernet Connection I218-LM                                 | 9         | 1.08%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 9         | 1.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.08%   |
| Intel Wireless-AC 9260                                            | 8         | 0.96%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 7         | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 7         | 0.84%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 6         | 0.72%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 0.72%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 6         | 0.72%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 5         | 0.6%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 0.6%    |
| Intel Ethernet Connection I217-LM                                 | 5         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                             | 5         | 0.6%    |
| Broadcom BCM4331 802.11a/b/g/n                                    | 5         | 0.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.48%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.48%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.48%   |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.48%   |
| Intel Ethernet Connection (2) I219-LM                             | 4         | 0.48%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 0.48%   |
| Intel Ethernet Connection (10) I219-LM                            | 4         | 0.48%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                      | 4         | 0.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 0.48%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 4         | 0.48%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.36%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]       | 3         | 0.36%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.36%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.36%   |
| Intel Ethernet Connection (11) I219-LM                            | 3         | 0.36%   |
| Intel Ethernet Connection (10) I219-V                             | 3         | 0.36%   |
| Dell DW5811e Snapdragon???„?? X7 LTE                              | 3         | 0.36%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 288       | 60.25%  |
| Realtek Semiconductor           | 62        | 12.97%  |
| Qualcomm Atheros                | 55        | 11.51%  |
| Broadcom                        | 23        | 4.81%   |
| MEDIATEK                        | 17        | 3.56%   |
| Ralink                          | 5         | 1.05%   |
| Sierra Wireless                 | 4         | 0.84%   |
| Dell                            | 4         | 0.84%   |
| Broadcom Limited                | 4         | 0.84%   |
| TP-Link                         | 3         | 0.63%   |
| Ralink Technology               | 3         | 0.63%   |
| Qualcomm                        | 3         | 0.63%   |
| Fibocom                         | 2         | 0.42%   |
| Qualcomm Atheros Communications | 1         | 0.21%   |
| NetGear                         | 1         | 0.21%   |
| Linksys                         | 1         | 0.21%   |
| Hewlett-Packard                 | 1         | 0.21%   |
| D-Link                          | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 42        | 8.75%   |
| Intel Wi-Fi 6 AX201                                            | 32        | 6.67%   |
| Intel Wireless 8265 / 8275                                     | 25        | 5.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 20        | 4.17%   |
| Intel Wireless 8260                                            | 19        | 3.96%   |
| Intel Wireless 7260                                            | 19        | 3.96%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 19        | 3.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 18        | 3.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 16        | 3.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 15        | 3.13%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter  | 13        | 2.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 2.29%   |
| Intel Wireless 7265                                            | 10        | 2.08%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 10        | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10        | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 1.88%   |
| Intel Wireless 3165                                            | 9         | 1.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 1.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 1.88%   |
| Intel Wireless-AC 9260                                         | 8         | 1.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 7         | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 6         | 1.25%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 1.25%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 6         | 1.25%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 1.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 0.83%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 0.83%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 4         | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 0.63%   |
| Qualcomm QCA6390 Wireless Network Adapter [AX500-DBS (2x2)]    | 3         | 0.63%   |
| Dell DW5811e Snapdragon???„?? X7 LTE                           | 3         | 0.63%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 3         | 0.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 0.63%   |
| TP-Link 802.11ac NIC                                           | 2         | 0.42%   |
| Sierra Wireless EM7305                                         | 2         | 0.42%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.42%   |
| Realtek 802.11ac NIC                                           | 2         | 0.42%   |
| MEDIATEK Network controller                                    | 2         | 0.42%   |
| MEDIATEK MT7630e 802.11bgn Wireless Network Adapter            | 2         | 0.42%   |
| Intel Wireless 3160                                            | 2         | 0.42%   |
| Intel Wi-Fi 6 AX201 160MHz                                     | 2         | 0.42%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 2         | 0.42%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.42%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 0.42%   |
| Fibocom L830-EB-00 LTE WWAN Modem                              | 2         | 0.42%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 0.42%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 2         | 0.42%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 2         | 0.42%   |
| Broadcom BCM4350 802.11ac Wireless Network Adapter             | 2         | 0.42%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.21%   |
| Sierra Wireless EM7455                                         | 1         | 0.21%   |
| Sierra Wireless EM7345 4G LTE                                  | 1         | 0.21%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.21%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter            | 1         | 0.21%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.21%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.21%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Realtek Semiconductor     | 184       | 53.8%   |
| Intel                     | 100       | 29.24%  |
| Qualcomm Atheros          | 12        | 3.51%   |
| Broadcom                  | 12        | 3.51%   |
| Lenovo                    | 10        | 2.92%   |
| DisplayLink               | 4         | 1.17%   |
| Nvidia                    | 3         | 0.88%   |
| Marvell Technology Group  | 3         | 0.88%   |
| Xiaomi                    | 2         | 0.58%   |
| TP-Link                   | 2         | 0.58%   |
| Broadcom Limited          | 2         | 0.58%   |
| Spreadtrum Communications | 1         | 0.29%   |
| Samsung Electronics       | 1         | 0.29%   |
| Qualcomm                  | 1         | 0.29%   |
| OPPO Electronics          | 1         | 0.29%   |
| MediaTek                  | 1         | 0.29%   |
| Linksys                   | 1         | 0.29%   |
| Cypress Semiconductor     | 1         | 0.29%   |
| ASIX Electronics          | 1         | 0.29%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 130       | 36.83%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 31        | 8.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 22        | 6.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 13        | 3.68%   |
| Intel Ethernet Connection (4) I219-LM                                          | 10        | 2.83%   |
| Intel Ethernet Connection I219-LM                                              | 9         | 2.55%   |
| Intel Ethernet Connection I218-LM                                              | 9         | 2.55%   |
| Intel Ethernet Connection (6) I219-V                                           | 7         | 1.98%   |
| Intel Ethernet Connection (4) I219-V                                           | 7         | 1.98%   |
| Lenovo ThinkPad TBT 3 Dock                                                     | 5         | 1.42%   |
| Intel Ethernet Connection I217-LM                                              | 5         | 1.42%   |
| Intel Ethernet Connection (7) I219-LM                                          | 5         | 1.42%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 4         | 1.13%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 4         | 1.13%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 4         | 1.13%   |
| Intel Ethernet Connection (6) I219-LM                                          | 4         | 1.13%   |
| Intel Ethernet Connection (2) I219-LM                                          | 4         | 1.13%   |
| Intel Ethernet Connection (13) I219-V                                          | 4         | 1.13%   |
| Intel Ethernet Connection (10) I219-LM                                         | 4         | 1.13%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 4         | 1.13%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 4         | 1.13%   |
| Nvidia MCP79 Ethernet                                                          | 3         | 0.85%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.85%   |
| Intel Ethernet Connection (11) I219-LM                                         | 3         | 0.85%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.85%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 2         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 2         | 0.57%   |
| Lenovo USB-C Dock Ethernet                                                     | 2         | 0.57%   |
| Lenovo ThinkPad TBT3 LAN                                                       | 2         | 0.57%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.57%   |
| Intel Ethernet Connection (13) I219-LM                                         | 2         | 0.57%   |
| DisplayLink Dell Universal Dock D6000                                          | 2         | 0.57%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.28%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.28%   |
| TP-Link USB 10/100 LAN                                                         | 1         | 0.28%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.28%   |
| Spreadtrum Nokia C30                                                           | 1         | 0.28%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.28%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.28%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1         | 0.28%   |
| Qualcomm U673C                                                                 | 1         | 0.28%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.28%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.28%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.28%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.28%   |
| OPPO RMX3381                                                                   | 1         | 0.28%   |
| MediaTek Infinix HOT 10T                                                       | 1         | 0.28%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.28%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 1         | 0.28%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.28%   |
| Linksys Gigabit Ethernet Adapter                                               | 1         | 0.28%   |
| Lenovo RTL8153 Gigabit Ethernet [ThinkPad OneLink Pro Dock]                    | 1         | 0.28%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.28%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.28%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.28%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.28%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.28%   |
| Intel 82567LM Gigabit Network Connection                                       | 1         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 453       | 58.23%  |
| Ethernet | 322       | 41.39%  |
| Modem    | 2         | 0.26%   |
| Unknown  | 1         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 422       | 67.74%  |
| Ethernet | 201       | 32.26%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 284       | 62.01%  |
| 1     | 163       | 35.59%  |
| 0     | 6         | 1.31%   |
| 3     | 5         | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 346       | 75.05%  |
| Yes  | 115       | 24.95%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 240       | 61.38%  |
| Realtek Semiconductor           | 37        | 9.46%   |
| Qualcomm Atheros Communications | 22        | 5.63%   |
| Apple                           | 18        | 4.6%    |
| IMC Networks                    | 15        | 3.84%   |
| Lite-On Technology              | 13        | 3.32%   |
| Foxconn / Hon Hai               | 13        | 3.32%   |
| Realtek                         | 7         | 1.79%   |
| Broadcom                        | 7         | 1.79%   |
| Cambridge Silicon Radio         | 5         | 1.28%   |
| Ralink                          | 4         | 1.02%   |
| Dell                            | 3         | 0.77%   |
| ASUSTek Computer                | 3         | 0.77%   |
| MediaTek                        | 2         | 0.51%   |
| Hewlett-Packard                 | 1         | 0.26%   |
| Foxconn International           | 1         | 0.26%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 145       | 37.08%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 37        | 9.46%   |
| Intel Bluetooth wireless interface                                                  | 36        | 9.21%   |
| Realtek Bluetooth Radio                                                             | 24        | 6.14%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 13        | 3.32%   |
| Apple Bluetooth Host Controller                                                     | 13        | 3.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 8         | 2.05%   |
| Realtek Bluetooth Radio                                                             | 7         | 1.79%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 6         | 1.53%   |
| IMC Networks Wireless_Device                                                        | 6         | 1.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 5         | 1.28%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 1.28%   |
| Intel AX210 Bluetooth                                                               | 5         | 1.28%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.28%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 5         | 1.28%   |
| Apple Bluetooth USB Host Controller                                                 | 5         | 1.28%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 1.02%   |
| Lite-On Wireless_Device                                                             | 4         | 1.02%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 1.02%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.77%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 0.77%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 0.77%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 3         | 0.77%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.51%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.51%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 0.51%   |
| MediaTek Wireless_Device                                                            | 2         | 0.51%   |
| Lite-On Bluetooth Device                                                            | 2         | 0.51%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.51%   |
| IMC Networks Bluetooth Device                                                       | 2         | 0.51%   |
| Foxconn / Hon Hai BT                                                                | 2         | 0.51%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.51%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.26%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.26%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.26%   |
| IMC Networks Bluetooth                                                              | 1         | 0.26%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.26%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.26%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 1         | 0.26%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.26%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.26%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.26%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.26%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.26%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.26%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 1         | 0.26%   |
| Broadcom BCM2035 Bluetooth dongle                                                   | 1         | 0.26%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.26%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.26%   |
| ASUS ASUS USB-BT500                                                                 | 1         | 0.26%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 357       | 59.9%   |
| AMD                       | 96        | 16.11%  |
| Nvidia                    | 80        | 13.42%  |
| C-Media Electronics       | 11        | 1.85%   |
| Lenovo                    | 10        | 1.68%   |
| GN Netcom                 | 7         | 1.17%   |
| Realtek Semiconductor     | 4         | 0.67%   |
| Plantronics               | 3         | 0.5%    |
| Kingston Technology       | 3         | 0.5%    |
| Hewlett-Packard           | 3         | 0.5%    |
| Creative Technology       | 3         | 0.5%    |
| SteelSeries ApS           | 2         | 0.34%   |
| CMX Systems               | 2         | 0.34%   |
| XMOS                      | 1         | 0.17%   |
| Texas Instruments         | 1         | 0.17%   |
| Sony                      | 1         | 0.17%   |
| Sennheiser Communications | 1         | 0.17%   |
| SAVITECH                  | 1         | 0.17%   |
| Razer USA                 | 1         | 0.17%   |
| Micronas                  | 1         | 0.17%   |
| Logitech                  | 1         | 0.17%   |
| JMTek                     | 1         | 0.17%   |
| HECATE G2 GAMING HEADSET  | 1         | 0.17%   |
| GYROCOM C&C               | 1         | 0.17%   |
| Fujitsu                   | 1         | 0.17%   |
| FIFINE Microphones        | 1         | 0.17%   |
| Conexant Systems          | 1         | 0.17%   |
| Arturia                   | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 76        | 10.63%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 75        | 10.49%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 54        | 7.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 44        | 6.15%   |
| Intel Cannon Lake PCH cAVS                                                                        | 27        | 3.78%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 26        | 3.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 23        | 3.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 22        | 3.08%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 21        | 2.94%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 2.66%   |
| Intel 8 Series HD Audio Controller                                                                | 19        | 2.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 16        | 2.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 15        | 2.1%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 2.1%    |
| Nvidia Audio device                                                                               | 14        | 1.96%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 11        | 1.54%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 1.54%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 1.4%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 1.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 1.26%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 1.26%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 8         | 1.12%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 7         | 0.98%   |
| AMD FCH Azalia Controller                                                                         | 7         | 0.98%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 0.84%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 0.84%   |
| Lenovo ThinkPad Thunderbolt 3 Dock USB Audio                                                      | 5         | 0.7%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 5         | 0.7%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 5         | 0.7%    |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                                         | 5         | 0.7%    |
| Realtek Semiconductor USB Audio                                                                   | 4         | 0.56%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.56%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 0.56%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.42%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.42%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.42%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 3         | 0.42%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.42%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.42%   |
| Hewlett-Packard USB Audio                                                                         | 3         | 0.42%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 3         | 0.42%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.42%   |
| SteelSeries ApS SteelSeries Arctis 7                                                              | 2         | 0.28%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.28%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.28%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.28%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.28%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.28%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.28%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.28%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 2         | 0.28%   |
| Lenovo ThinkPad Thunderbolt 3 Dock Audio                                                          | 2         | 0.28%   |
| Intel Jasper Lake HD Audio                                                                        | 2         | 0.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.28%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.28%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.28%   |
| GN Netcom Jabra Link 370                                                                          | 2         | 0.28%   |
| GN Netcom Jabra Evolve 65                                                                         | 2         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 102       | 34.69%  |
| SK Hynix            | 59        | 20.07%  |
| Micron Technology   | 45        | 15.31%  |
| Kingston            | 25        | 8.5%    |
| Crucial             | 20        | 6.8%    |
| Unknown             | 15        | 5.1%    |
| A-DATA Technology   | 4         | 1.36%   |
| Team                | 3         | 1.02%   |
| Ramaxel Technology  | 3         | 1.02%   |
| Elpida              | 3         | 1.02%   |
| SMART Brazil        | 2         | 0.68%   |
| Corsair             | 2         | 0.68%   |
| Avant               | 2         | 0.68%   |
| Unknown (ABCD)      | 1         | 0.34%   |
| Transcend           | 1         | 0.34%   |
| Smart               | 1         | 0.34%   |
| Qimonda             | 1         | 0.34%   |
| PUSKILL             | 1         | 0.34%   |
| Nanya Technology    | 1         | 0.34%   |
| Miron               | 1         | 0.34%   |
| GOODRAM             | 1         | 0.34%   |
| Goldkey             | 1         | 0.34%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 8         | 2.55%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 2.23%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 6         | 1.91%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 5         | 1.59%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 1.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.59%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 1.59%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 4         | 1.27%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 4         | 1.27%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 1.27%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.27%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.27%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 4         | 1.27%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.96%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.96%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 0.96%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.96%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.96%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 3         | 0.96%   |
| Samsung RAM M471A1K43EB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.96%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.96%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.96%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.96%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s    | 3         | 0.96%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.64%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.64%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 2         | 0.64%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.64%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 2         | 0.64%   |
| SK Hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.64%   |
| SK Hynix RAM HMA82GS6JJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 2         | 0.64%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s        | 2         | 0.64%   |
| Samsung RAM U6E3S4AA-MGCR 1024MB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.64%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s              | 2         | 0.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.64%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 2667MT/s         | 2         | 0.64%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 2         | 0.64%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 2         | 0.64%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 2         | 0.64%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.64%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 0.64%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 2         | 0.64%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s          | 2         | 0.64%   |
| Micron RAM 53E512M32D2NP-046 1GB Row Of Chips LPDDR4 4267MT/s    | 2         | 0.64%   |
| Crucial RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.64%   |
| Crucial RAM Module 4GB SODIMM DDR3 1067MT/s                      | 2         | 0.64%   |
| Crucial RAM CT51264BF160BJ.C8F 4GB SODIMM DDR3 1600MT/s          | 2         | 0.64%   |
| Crucial RAM CT16G4SFRA32A.M16FRS 16GB SODIMM DDR4 3200MT/s       | 2         | 0.64%   |
| Crucial RAM CT16G4SFD8266.C16FD1 16384MB SODIMM DDR4 2667MT/s    | 2         | 0.64%   |
| Crucial RAM CT16G4SFD824A.C16FE 16384MB SODIMM DDR4 2400MT/s     | 2         | 0.64%   |
| Unknown RAM Module 8GB SODIMM LPDDR4 4266MT/s                    | 1         | 0.32%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 8GB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 1         | 0.32%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.32%   |
| Unknown RAM Module 4GB SODIMM 1066MT/s                           | 1         | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 151       | 59.92%  |
| DDR3    | 57        | 22.62%  |
| LPDDR4  | 22        | 8.73%   |
| LPDDR3  | 16        | 6.35%   |
| DDR2    | 4         | 1.59%   |
| SDRAM   | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 209       | 79.77%  |
| Row Of Chips | 47        | 17.94%  |
| Chip         | 4         | 1.53%   |
| DIMM         | 1         | 0.38%   |
| Unknown      | 1         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 122       | 45.35%  |
| 4096  | 73        | 27.14%  |
| 16384 | 50        | 18.59%  |
| 2048  | 14        | 5.2%    |
| 32768 | 8         | 2.97%   |
| 1024  | 2         | 0.74%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 69        | 26.04%  |
| 2667    | 62        | 23.4%   |
| 1600    | 40        | 15.09%  |
| 2133    | 20        | 7.55%   |
| 2400    | 19        | 7.17%   |
| 4267    | 13        | 4.91%   |
| 1867    | 6         | 2.26%   |
| 3266    | 5         | 1.89%   |
| 1333    | 5         | 1.89%   |
| 1067    | 5         | 1.89%   |
| 4266    | 4         | 1.51%   |
| 3733    | 3         | 1.13%   |
| 1334    | 3         | 1.13%   |
| 1066    | 3         | 1.13%   |
| 667     | 3         | 1.13%   |
| 2933    | 2         | 0.75%   |
| 4199    | 1         | 0.38%   |
| 800     | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 2         | 40%     |
| Prolific Technology | 1         | 20%     |
| Hewlett-Packard     | 1         | 20%     |
| Canon               | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Samsung SCX-3200 Series         | 1         | 20%     |
| Samsung CLX-6260 Series         | 1         | 20%     |
| Prolific PL2305 Parallel Port   | 1         | 20%     |
| HP LaserJet 400 colorMFP M475dw | 1         | 20%     |
| Canon TR8500 series             | 1         | 20%     |

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
| Chicony Electronics                    | 103       | 23.36%  |
| IMC Networks                           | 52        | 11.79%  |
| Acer                                   | 49        | 11.11%  |
| Microdia                               | 42        | 9.52%   |
| Realtek Semiconductor                  | 35        | 7.94%   |
| Quanta                                 | 33        | 7.48%   |
| Sunplus Innovation Technology          | 18        | 4.08%   |
| Logitech                               | 17        | 3.85%   |
| Cheng Uei Precision Industry (Foxlink) | 16        | 3.63%   |
| Syntek                                 | 14        | 3.17%   |
| Apple                                  | 12        | 2.72%   |
| Lite-On Technology                     | 11        | 2.49%   |
| Suyin                                  | 9         | 2.04%   |
| Samsung Electronics                    | 5         | 1.13%   |
| Luxvisions Innotech Limited            | 5         | 1.13%   |
| Silicon Motion                         | 3         | 0.68%   |
| Ricoh                                  | 2         | 0.45%   |
| USB2.0 Webcamera                       | 1         | 0.23%   |
| Tobii Technology AB                    | 1         | 0.23%   |
| Razer USA                              | 1         | 0.23%   |
| Pixart Imaging                         | 1         | 0.23%   |
| Microsoft                              | 1         | 0.23%   |
| Lenovo                                 | 1         | 0.23%   |
| Importek                               | 1         | 0.23%   |
| Generalplus Technology                 | 1         | 0.23%   |
| DLUPCA1UIFL9ZS                         | 1         | 0.23%   |
| DJJHFA1BIEW726                         | 1         | 0.23%   |
| Creative Technology                    | 1         | 0.23%   |
| ARC International                      | 1         | 0.23%   |
| ANYKA                                  | 1         | 0.23%   |
| Alcor Micro                            | 1         | 0.23%   |
| 8SSC20F27114V1SR0BM1TEX                | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 41        | 9.26%   |
| Microdia Integrated_Webcam_HD                                   | 30        | 6.77%   |
| IMC Networks Integrated Camera                                  | 25        | 5.64%   |
| Acer Integrated Camera                                          | 22        | 4.97%   |
| Realtek Integrated_Webcam_HD                                    | 17        | 3.84%   |
| Quanta HD User Facing                                           | 13        | 2.93%   |
| Syntek Integrated Camera                                        | 11        | 2.48%   |
| Sunplus Integrated_Webcam_HD                                    | 9         | 2.03%   |
| Microdia Integrated Webcam                                      | 8         | 1.81%   |
| Chicony HD WebCam                                               | 8         | 1.81%   |
| Quanta HP TrueVision HD Camera                                  | 7         | 1.58%   |
| Apple Built-in iSight                                           | 7         | 1.58%   |
| Logitech Webcam C270                                            | 6         | 1.35%   |
| Logitech HD Pro Webcam C920                                     | 6         | 1.35%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 6         | 1.35%   |
| Chicony Integrated Camera (1280x720@30)                         | 6         | 1.35%   |
| Acer SunplusIT Integrated Camera                                | 6         | 1.35%   |
| Samsung Galaxy A5 (MTP)                                         | 5         | 1.13%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 5         | 1.13%   |
| IMC Networks HD Camera                                          | 5         | 1.13%   |
| Chicony USB2.0 Camera                                           | 5         | 1.13%   |
| Realtek Integrated Webcam HD                                    | 4         | 0.9%    |
| Logitech C922 Pro Stream Webcam                                 | 4         | 0.9%    |
| Lite-On HP HD Camera                                            | 4         | 0.9%    |
| Chicony USB 2.0 Camera                                          | 4         | 0.9%    |
| Chicony HP HD Camera                                            | 4         | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HD Camera                | 4         | 0.9%    |
| Apple FaceTime HD Camera                                        | 4         | 0.9%    |
| Acer BisonCam,NB Pro                                            | 4         | 0.9%    |
| Acer BisonCam, NB Pro                                           | 4         | 0.9%    |
| Syntek EasyCamera                                               | 3         | 0.68%   |
| Suyin HP TrueVision HD Integrated Webcam                        | 3         | 0.68%   |
| Quanta VGA WebCam                                               | 3         | 0.68%   |
| Lite-On Integrated Camera                                       | 3         | 0.68%   |
| Chicony USB2.0 HD UVC WebCam                                    | 3         | 0.68%   |
| Chicony Lenovo EasyCamera                                       | 3         | 0.68%   |
| Chicony EasyCamera                                              | 3         | 0.68%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 3         | 0.68%   |
| Acer ThinkPad Integrated Camera                                 | 3         | 0.68%   |
| Acer HD Webcam                                                  | 3         | 0.68%   |
| Suyin Integrated_Webcam_HD                                      | 2         | 0.45%   |
| Sunplus FHD Camera Microphone                                   | 2         | 0.45%   |
| Realtek USB Camera                                              | 2         | 0.45%   |
| Realtek Lenovo EasyCamera                                       | 2         | 0.45%   |
| Realtek Laptop Camera                                           | 2         | 0.45%   |
| Realtek HD WebCam                                               | 2         | 0.45%   |
| Quanta HP Wide Vision HD Camera                                 | 2         | 0.45%   |
| Quanta HP HD Camera                                             | 2         | 0.45%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 2         | 0.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 2         | 0.45%   |
| Lite-On HP HD Webcam                                            | 2         | 0.45%   |
| IMC Networks VGA UVC WebCam                                     | 2         | 0.45%   |
| IMC Networks ov9734_azurewave_camera                            | 2         | 0.45%   |
| IMC Networks HP TrueVision HD Camera                            | 2         | 0.45%   |
| Chicony VGA WebCam                                              | 2         | 0.45%   |
| Chicony TOSHIBA Web Camera - HD                                 | 2         | 0.45%   |
| Chicony Lenovo Integrated Camera (0.3MP)                        | 2         | 0.45%   |
| Chicony HP Wide Vision HD Camera                                | 2         | 0.45%   |
| Chicony HP Truevision HD                                        | 2         | 0.45%   |
| Chicony HP HD Webcam                                            | 2         | 0.45%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 45        | 37.82%  |
| Validity Sensors           | 31        | 26.05%  |
| Shenzhen Goodix Technology | 29        | 24.37%  |
| Upek                       | 5         | 4.2%    |
| LighTuning Technology      | 4         | 3.36%   |
| Elan Microelectronics      | 4         | 3.36%   |
| AuthenTec                  | 1         | 0.84%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 27        | 22.69%  |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 15.13%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 7.56%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 5.88%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 5.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 4.2%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 5         | 4.2%    |
| Unknown                                                                    | 5         | 4.2%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 3.36%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 3.36%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 3.36%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.52%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 2.52%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.68%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.68%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.68%   |
| Validity Sensors VFS491                                                    | 1         | 0.84%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.84%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.84%   |
| Synaptics WBDI Device                                                      | 1         | 0.84%   |
| Synaptics  WBDI                                                            | 1         | 0.84%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.84%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 20        | 46.51%  |
| Broadcom    | 17        | 39.53%  |
| Lenovo      | 3         | 6.98%   |
| Upek        | 2         | 4.65%   |
| O2 Micro    | 1         | 2.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 46.51%  |
| Broadcom 5880                                                                | 6         | 13.95%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 11.63%  |
| Broadcom 58200                                                               | 5         | 11.63%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.98%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.65%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 258       | 55.6%   |
| 1     | 162       | 34.91%  |
| 2     | 34        | 7.33%   |
| 3     | 7         | 1.51%   |
| 4     | 2         | 0.43%   |
| 5     | 1         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 118       | 46.27%  |
| Graphics card         | 53        | 20.78%  |
| Multimedia controller | 28        | 10.98%  |
| Net/wireless          | 22        | 8.63%   |
| Camera                | 11        | 4.31%   |
| Chipcard              | 8         | 3.14%   |
| Bluetooth             | 7         | 2.75%   |
| Card reader           | 4         | 1.57%   |
| Storage               | 1         | 0.39%   |
| Sound                 | 1         | 0.39%   |
| Network               | 1         | 0.39%   |
| Net/ethernet          | 1         | 0.39%   |

