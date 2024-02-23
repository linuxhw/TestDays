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

Total: 506

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| MSI           | Modern 15 A10M              | [22f3c2e58e](https://linux-hardware.org/?probe=22f3c2e58e) | Feb 02, 2024 |
| Acer          | NC-F5-771G-72XY             | [2f4c6fbadb](https://linux-hardware.org/?probe=2f4c6fbadb) | Feb 02, 2024 |
| Apple         | MacBookPro5,4               | [c22226fe6f](https://linux-hardware.org/?probe=c22226fe6f) | Feb 01, 2024 |
| HP            | EliteBook 840 G1            | [920b1ecb34](https://linux-hardware.org/?probe=920b1ecb34) | Jan 31, 2024 |
| Dell          | Inspiron 1525               | [ad26dae776](https://linux-hardware.org/?probe=ad26dae776) | Jan 30, 2024 |
| Dell          | Inspiron 1525               | [bc4394a85f](https://linux-hardware.org/?probe=bc4394a85f) | Jan 30, 2024 |
| HP            | EliteBook 860 16 inch G1... | [737d54004b](https://linux-hardware.org/?probe=737d54004b) | Jan 29, 2024 |
| ASUSTek       | X205TA                      | [83899dcb83](https://linux-hardware.org/?probe=83899dcb83) | Jan 27, 2024 |
| Lenovo        | ThinkPad T400 6474AW6       | [0ddfcaf599](https://linux-hardware.org/?probe=0ddfcaf599) | Jan 27, 2024 |
| Acer          | Aspire A315-58              | [c85674acbd](https://linux-hardware.org/?probe=c85674acbd) | Jan 26, 2024 |
| PC Special... | NH5x_7xDPx                  | [0f28a5d513](https://linux-hardware.org/?probe=0f28a5d513) | Jan 26, 2024 |
| Apple         | MacBook5,1                  | [51346a4084](https://linux-hardware.org/?probe=51346a4084) | Jan 25, 2024 |
| Dell          | Latitude 7340               | [880054b099](https://linux-hardware.org/?probe=880054b099) | Jan 25, 2024 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [5a5ec0016f](https://linux-hardware.org/?probe=5a5ec0016f) | Jan 24, 2024 |
| Dell          | Inspiron 5567               | [dc061193f2](https://linux-hardware.org/?probe=dc061193f2) | Jan 22, 2024 |
| MSI           | GF63 Thin 11UC              | [b6fa224856](https://linux-hardware.org/?probe=b6fa224856) | Jan 21, 2024 |
| MSI           | GF63 Thin 11UC              | [6d2801d1d8](https://linux-hardware.org/?probe=6d2801d1d8) | Jan 14, 2024 |
| Lenovo        | G500 20236                  | [5dacf75c7d](https://linux-hardware.org/?probe=5dacf75c7d) | Jan 12, 2024 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [ce397f675e](https://linux-hardware.org/?probe=ce397f675e) | Jan 10, 2024 |
| Dell          | Inspiron 14-3452            | [0e47261be0](https://linux-hardware.org/?probe=0e47261be0) | Jan 09, 2024 |
| Dell          | Inspiron 14-3452            | [1834cfc875](https://linux-hardware.org/?probe=1834cfc875) | Jan 09, 2024 |
| Apple         | MacBook5,2                  | [2ed16f6a80](https://linux-hardware.org/?probe=2ed16f6a80) | Jan 07, 2024 |
| Lenovo        | IdeaPad 510S-13ISK 80SJ     | [90fe273da6](https://linux-hardware.org/?probe=90fe273da6) | Jan 06, 2024 |
| Acer          | Aspire A517-52              | [610817c6c9](https://linux-hardware.org/?probe=610817c6c9) | Jan 05, 2024 |
| HP            | Pavilion dv7                | [dc31f854de](https://linux-hardware.org/?probe=dc31f854de) | Jan 04, 2024 |
| Dell          | Latitude 7390               | [8c74383dab](https://linux-hardware.org/?probe=8c74383dab) | Dec 27, 2023 |
| Dell          | Latitude 7390               | [889337bb1c](https://linux-hardware.org/?probe=889337bb1c) | Dec 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [38b1c283b4](https://linux-hardware.org/?probe=38b1c283b4) | Dec 26, 2023 |
| eMachines     | E527                        | [cf5b096be7](https://linux-hardware.org/?probe=cf5b096be7) | Dec 22, 2023 |
| Lenovo        | Yoga 2 11 20332             | [16a8e6f875](https://linux-hardware.org/?probe=16a8e6f875) | Dec 21, 2023 |
| Sony          | VGN-NW270F                  | [eee640a54d](https://linux-hardware.org/?probe=eee640a54d) | Dec 20, 2023 |
| HP            | Pavilion dv6                | [4cc379dfbd](https://linux-hardware.org/?probe=4cc379dfbd) | Dec 19, 2023 |
| HP            | Notebook                    | [31d6fc4280](https://linux-hardware.org/?probe=31d6fc4280) | Dec 19, 2023 |
| ASUSTek       | X541UVK                     | [a6ae535887](https://linux-hardware.org/?probe=a6ae535887) | Dec 18, 2023 |
| MSI           | GF63 Thin 11UC              | [06556bd61a](https://linux-hardware.org/?probe=06556bd61a) | Dec 17, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | [ce0e0e1bc1](https://linux-hardware.org/?probe=ce0e0e1bc1) | Dec 17, 2023 |
| Apple         | MacBookPro8,1               | [f0ed04c975](https://linux-hardware.org/?probe=f0ed04c975) | Dec 16, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [6a2633018c](https://linux-hardware.org/?probe=6a2633018c) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [e7ca2f3a6e](https://linux-hardware.org/?probe=e7ca2f3a6e) | Dec 14, 2023 |
| Toshiba       | Satellite Pro C660          | [63cf57fa53](https://linux-hardware.org/?probe=63cf57fa53) | Dec 12, 2023 |
| Dell          | Inspiron 7591               | [10a266d0ff](https://linux-hardware.org/?probe=10a266d0ff) | Dec 12, 2023 |
| Lenovo        | ThinkPad T530 2429W1E       | [02a4811e8d](https://linux-hardware.org/?probe=02a4811e8d) | Dec 10, 2023 |
| Dell          | Inspiron 7591               | [7907f73ee0](https://linux-hardware.org/?probe=7907f73ee0) | Dec 09, 2023 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [beaa75c727](https://linux-hardware.org/?probe=beaa75c727) | Dec 06, 2023 |
| ASUSTek       | ASUSLaptop_Q540VJ           | [0c680c33ec](https://linux-hardware.org/?probe=0c680c33ec) | Dec 05, 2023 |
| Dell          | Latitude 7370               | [30fc1de681](https://linux-hardware.org/?probe=30fc1de681) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [203357a4dd](https://linux-hardware.org/?probe=203357a4dd) | Dec 03, 2023 |
| Dell          | Latitude 7370               | [356b2e9e31](https://linux-hardware.org/?probe=356b2e9e31) | Nov 30, 2023 |
| HP            | ProBook 450 G1              | [7c7825a9c9](https://linux-hardware.org/?probe=7c7825a9c9) | Nov 30, 2023 |
| Lenovo        | ThinkPad T440p 20AN0069U... | [8edef55308](https://linux-hardware.org/?probe=8edef55308) | Nov 24, 2023 |
| HP            | EliteBook 725 G2            | [b6cfe558cb](https://linux-hardware.org/?probe=b6cfe558cb) | Nov 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2b84d65d1a](https://linux-hardware.org/?probe=2b84d65d1a) | Nov 20, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | [d5ccc9cfc9](https://linux-hardware.org/?probe=d5ccc9cfc9) | Nov 20, 2023 |
| Thomson       | N15C8BK2T                   | [e5a62b2035](https://linux-hardware.org/?probe=e5a62b2035) | Nov 18, 2023 |
| Lenovo        | IdeaPad N585 20179          | [b8bca4e3cd](https://linux-hardware.org/?probe=b8bca4e3cd) | Nov 18, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [6806c7c828](https://linux-hardware.org/?probe=6806c7c828) | Nov 15, 2023 |
| Lenovo        | IdeaPad S300 9803           | [21f7433934](https://linux-hardware.org/?probe=21f7433934) | Nov 15, 2023 |
| Lenovo        | ThinkPad X250 20CLS2P703    | [b15506a2b9](https://linux-hardware.org/?probe=b15506a2b9) | Nov 14, 2023 |
| Dell          | Latitude E5420              | [dc67f70b3b](https://linux-hardware.org/?probe=dc67f70b3b) | Nov 13, 2023 |
| Acer          | Aspire 5740                 | [7deb21f5d9](https://linux-hardware.org/?probe=7deb21f5d9) | Nov 13, 2023 |
| Apple         | MacBookAir4,2               | [aefe53a7b6](https://linux-hardware.org/?probe=aefe53a7b6) | Nov 13, 2023 |
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

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 5.15.0-56-generic    | 23        | 5.4%    |
| 5.15.0-47-generic    | 19        | 4.46%   |
| 6.2.0-26-generic     | 17        | 3.99%   |
| 5.15.0-58-generic    | 17        | 3.99%   |
| 5.15.0-52-generic    | 16        | 3.76%   |
| 5.15.0-48-generic    | 16        | 3.76%   |
| 5.15.0-25-generic    | 14        | 3.29%   |
| 5.15.0-60-generic    | 13        | 3.05%   |
| 6.2.0-32-generic     | 11        | 2.58%   |
| 6.2.0-39-generic     | 10        | 2.35%   |
| 5.15.0-71-generic    | 10        | 2.35%   |
| 5.15.0-67-generic    | 10        | 2.35%   |
| 5.19.0-45-generic    | 9         | 2.11%   |
| 5.19.0-38-generic    | 9         | 2.11%   |
| 5.19.0-46-generic    | 8         | 1.88%   |
| 5.19.0-41-generic    | 8         | 1.88%   |
| 5.15.0-46-generic    | 8         | 1.88%   |
| 6.2.0-37-generic     | 7         | 1.64%   |
| 6.2.0-36-generic     | 7         | 1.64%   |
| 5.19.0-35-generic    | 7         | 1.64%   |
| 5.15.0-78-generic    | 7         | 1.64%   |
| 5.15.0-53-generic    | 7         | 1.64%   |
| 5.15.0-27-generic    | 7         | 1.64%   |
| 5.15.0-91-generic    | 6         | 1.41%   |
| 5.15.0-76-generic    | 6         | 1.41%   |
| 5.15.0-57-generic    | 6         | 1.41%   |
| 5.15.0-39-generic    | 6         | 1.41%   |
| 5.19.0-43-generic    | 5         | 1.17%   |
| 5.15.0-69-generic    | 5         | 1.17%   |
| 5.15.0-50-generic    | 5         | 1.17%   |
| 5.15.0-43-generic    | 5         | 1.17%   |
| 5.15.0-40-generic    | 5         | 1.17%   |
| 5.15.0-35-generic    | 5         | 1.17%   |
| 6.5.0-15-generic     | 4         | 0.94%   |
| 6.2.0-34-generic     | 4         | 0.94%   |
| 5.19.0-50-generic    | 4         | 0.94%   |
| 5.19.0-42-generic    | 4         | 0.94%   |
| 5.19.0-32-generic    | 4         | 0.94%   |
| 5.15.0-71-lowlatency | 4         | 0.94%   |
| 5.15.0-41-generic    | 4         | 0.94%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.0   | 237       | 59.4%   |
| 6.2.0    | 65        | 16.29%  |
| 5.19.0   | 58        | 14.54%  |
| 6.5.0    | 9         | 2.26%   |
| 5.17.0   | 9         | 2.26%   |
| 6.1.0    | 6         | 1.5%    |
| 6.0.0    | 2         | 0.5%    |
| 6.4.15   | 1         | 0.25%   |
| 6.4.0    | 1         | 0.25%   |
| 6.1.6    | 1         | 0.25%   |
| 6.0.9    | 1         | 0.25%   |
| 6.0.7    | 1         | 0.25%   |
| 5.4.0    | 1         | 0.25%   |
| 5.19.5   | 1         | 0.25%   |
| 5.19.17  | 1         | 0.25%   |
| 5.18.0   | 1         | 0.25%   |
| 5.17.3   | 1         | 0.25%   |
| 5.13.0   | 1         | 0.25%   |
| 4.19.241 | 1         | 0.25%   |
| 4.15.13  | 1         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 237       | 59.4%   |
| 6.2     | 65        | 16.29%  |
| 5.19    | 60        | 15.04%  |
| 5.17    | 10        | 2.51%   |
| 6.5     | 9         | 2.26%   |
| 6.1     | 7         | 1.75%   |
| 6.0     | 4         | 1%      |
| 6.4     | 2         | 0.5%    |
| 5.4     | 1         | 0.25%   |
| 5.18    | 1         | 0.25%   |
| 5.13    | 1         | 0.25%   |
| 4.19    | 1         | 0.25%   |
| 4.15    | 1         | 0.25%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 389       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| XFCE  | 381       | 97.94%  |
| GNOME | 8         | 2.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 376       | 96.66%  |
| Wayland | 8         | 2.06%   |
| Tty     | 5         | 1.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 339       | 87.15%  |
| GDM3    | 23        | 5.91%   |
| Unknown | 21        | 5.4%    |
| SDDM    | 4         | 1.03%   |
| SLiM    | 2         | 0.51%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 160       | 41.13%  |
| fr_FR | 51        | 13.11%  |
| de_DE | 43        | 11.05%  |
| it_IT | 23        | 5.91%   |
| en_GB | 19        | 4.88%   |
| ru_RU | 9         | 2.31%   |
| pt_BR | 9         | 2.31%   |
| es_ES | 8         | 2.06%   |
| en_CA | 8         | 2.06%   |
| pl_PL | 5         | 1.29%   |
| en_IN | 5         | 1.29%   |
| en_AU | 5         | 1.29%   |
| C     | 5         | 1.29%   |
| cs_CZ | 4         | 1.03%   |
| nl_NL | 3         | 0.77%   |
| hu_HU | 3         | 0.77%   |
| es_CL | 3         | 0.77%   |
| tr_TR | 2         | 0.51%   |
| ro_RO | 2         | 0.51%   |
| ja_JP | 2         | 0.51%   |
| es_MX | 2         | 0.51%   |
| zh_TW | 1         | 0.26%   |
| zh_CN | 1         | 0.26%   |
| ru_UA | 1         | 0.26%   |
| pt_PT | 1         | 0.26%   |
| nl_BE | 1         | 0.26%   |
| lt_LT | 1         | 0.26%   |
| fr_BE | 1         | 0.26%   |
| es_VE | 1         | 0.26%   |
| es_UY | 1         | 0.26%   |
| es_CO | 1         | 0.26%   |
| en_IL | 1         | 0.26%   |
| en_IE | 1         | 0.26%   |
| en_HK | 1         | 0.26%   |
| el_GR | 1         | 0.26%   |
| de_IT | 1         | 0.26%   |
| de_CH | 1         | 0.26%   |
| de_AT | 1         | 0.26%   |
| bg_BG | 1         | 0.26%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 214       | 54.45%  |
| BIOS | 179       | 45.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 322       | 80.7%   |
| Tmpfs   | 44        | 11.03%  |
| Overlay | 14        | 3.51%   |
| Zfs     | 10        | 2.51%   |
| Btrfs   | 7         | 1.75%   |
| Xfs     | 1         | 0.25%   |
| Ext3    | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 295       | 74.68%  |
| MBR     | 56        | 14.18%  |
| Unknown | 44        | 11.14%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 359       | 90.89%  |
| Yes       | 36        | 9.11%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 277       | 71.21%  |
| Yes       | 112       | 28.79%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 94        | 24.16%  |
| Hewlett-Packard     | 68        | 17.48%  |
| Dell                | 55        | 14.14%  |
| ASUSTek Computer    | 39        | 10.03%  |
| Acer                | 31        | 7.97%   |
| Google              | 13        | 3.34%   |
| Apple               | 12        | 3.08%   |
| Toshiba             | 9         | 2.31%   |
| Samsung Electronics | 6         | 1.54%   |
| MSI                 | 6         | 1.54%   |
| Sony                | 5         | 1.29%   |
| GPU Company         | 5         | 1.29%   |
| HUAWEI              | 4         | 1.03%   |
| Unknown             | 4         | 1.03%   |
| Notebook            | 2         | 0.51%   |
| Medion              | 2         | 0.51%   |
| HONOR               | 2         | 0.51%   |
| Gigabyte Technology | 2         | 0.51%   |
| Gateway             | 2         | 0.51%   |
| Fujitsu Siemens     | 2         | 0.51%   |
| Fujitsu             | 2         | 0.51%   |
| Chuwi               | 2         | 0.51%   |
| AMI                 | 2         | 0.51%   |
| Thomson             | 1         | 0.26%   |
| Tactus              | 1         | 0.26%   |
| Standard            | 1         | 0.26%   |
| SGIN                | 1         | 0.26%   |
| Schenker            | 1         | 0.26%   |
| PC Specialist       | 1         | 0.26%   |
| Panasonic           | 1         | 0.26%   |
| Packard Bell        | 1         | 0.26%   |
| Olivetti            | 1         | 0.26%   |
| Mediacom            | 1         | 0.26%   |
| Itautec             | 1         | 0.26%   |
| HIGRADED            | 1         | 0.26%   |
| Getac               | 1         | 0.26%   |
| Fusion5             | 1         | 0.26%   |
| eMachines           | 1         | 0.26%   |
| ECS                 | 1         | 0.26%   |
| Dynabook            | 1         | 0.26%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 5         | 1.29%   |
| HP EliteBook 840 G3                      | 4         | 1.03%   |
| Google Snappy                            | 4         | 1.03%   |
| HP Pavilion 17                           | 3         | 0.77%   |
| HP Laptop 15s-fq2xxx                     | 3         | 0.77%   |
| Apple MacBookPro8,1                      | 3         | 0.77%   |
| Lenovo ThinkPad P50 20EN0013US           | 2         | 0.51%   |
| Lenovo IdeaPad 5 15ABA7 82SG             | 2         | 0.51%   |
| HUAWEI BOHK-WAX9X                        | 2         | 0.51%   |
| HP Pavilion Notebook                     | 2         | 0.51%   |
| HP Pavilion g6                           | 2         | 0.51%   |
| HP Pavilion dv7                          | 2         | 0.51%   |
| HP Pavilion dv6                          | 2         | 0.51%   |
| HP Pavilion 15                           | 2         | 0.51%   |
| HP EliteBook 820 G3                      | 2         | 0.51%   |
| HP 255 G8 Notebook PC                    | 2         | 0.51%   |
| GPU Company GWTN116-3                    | 2         | 0.51%   |
| Google Auron_Yuna                        | 2         | 0.51%   |
| Dell XPS 13 9305                         | 2         | 0.51%   |
| Dell Latitude E5450                      | 2         | 0.51%   |
| Dell Latitude 5411                       | 2         | 0.51%   |
| ASUS X541UVK                             | 2         | 0.51%   |
| ASUS ASUS TUF Gaming A15 FA507RE_FA507RE | 2         | 0.51%   |
| Apple MacBookPro7,1                      | 2         | 0.51%   |
| Apple MacBookPro5,4                      | 2         | 0.51%   |
| AMI Intel                                | 2         | 0.51%   |
| Toshiba Satellite Pro R50-C              | 1         | 0.26%   |
| Toshiba Satellite Pro R50-B              | 1         | 0.26%   |
| Toshiba Satellite Pro C660               | 1         | 0.26%   |
| Toshiba Satellite L750D                  | 1         | 0.26%   |
| Toshiba Satellite C650                   | 1         | 0.26%   |
| Toshiba Satellite C55D-B                 | 1         | 0.26%   |
| Toshiba Satellite C50D-A-10E             | 1         | 0.26%   |
| Toshiba PT10F                            | 1         | 0.26%   |
| Toshiba EQUIUM P200                      | 1         | 0.26%   |
| Thomson N15C8BK2T                        | 1         | 0.26%   |
| Tactus GeoBook 140                       | 1         | 0.26%   |
| Sony VPCS12V9E                           | 1         | 0.26%   |
| Sony VPCEH25EN                           | 1         | 0.26%   |
| Sony VPCEA3S1E                           | 1         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Lenovo ThinkPad          | 56        | 14.4%   |
| Dell Latitude            | 25        | 6.43%   |
| Acer Aspire              | 23        | 5.91%   |
| Lenovo IdeaPad           | 19        | 4.88%   |
| HP Pavilion              | 19        | 4.88%   |
| HP EliteBook             | 14        | 3.6%    |
| Dell Inspiron            | 13        | 3.34%   |
| HP Laptop                | 9         | 2.31%   |
| ASUS VivoBook            | 9         | 2.31%   |
| Toshiba Satellite        | 7         | 1.8%    |
| Dell XPS                 | 7         | 1.8%    |
| HP ProBook               | 5         | 1.29%   |
| Unknown                  | 5         | 1.29%   |
| Google Snappy            | 4         | 1.03%   |
| Dell Vostro              | 4         | 1.03%   |
| Dell Precision           | 4         | 1.03%   |
| ASUS ROG                 | 4         | 1.03%   |
| ASUS ASUS                | 4         | 1.03%   |
| Lenovo ThinkBook         | 3         | 0.77%   |
| HP Stream                | 3         | 0.77%   |
| HP Compaq                | 3         | 0.77%   |
| HP 255                   | 3         | 0.77%   |
| HP 250                   | 3         | 0.77%   |
| Apple MacBookPro8        | 3         | 0.77%   |
| MSI Modern               | 2         | 0.51%   |
| MSI GF63                 | 2         | 0.51%   |
| Lenovo Yoga              | 2         | 0.51%   |
| Lenovo V15               | 2         | 0.51%   |
| HUAWEI BOHK-WAX9X        | 2         | 0.51%   |
| HP ZBook                 | 2         | 0.51%   |
| GPU Company GWTN116-3    | 2         | 0.51%   |
| Google Auron             | 2         | 0.51%   |
| Fujitsu Siemens LIFEBOOK | 2         | 0.51%   |
| Fujitsu LIFEBOOK         | 2         | 0.51%   |
| ASUS ZenBook             | 2         | 0.51%   |
| ASUS X541UVK             | 2         | 0.51%   |
| Apple MacBookPro7        | 2         | 0.51%   |
| Apple MacBookPro5        | 2         | 0.51%   |
| Apple MacBook5           | 2         | 0.51%   |
| AMI Intel                | 2         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 45        | 11.57%  |
| 2020 | 38        | 9.77%   |
| 2022 | 31        | 7.97%   |
| 2015 | 26        | 6.68%   |
| 2013 | 25        | 6.43%   |
| 2011 | 24        | 6.17%   |
| 2017 | 22        | 5.66%   |
| 2016 | 22        | 5.66%   |
| 2012 | 22        | 5.66%   |
| 2019 | 21        | 5.4%    |
| 2014 | 20        | 5.14%   |
| 2010 | 18        | 4.63%   |
| 2009 | 18        | 4.63%   |
| 2008 | 17        | 4.37%   |
| 2018 | 14        | 3.6%    |
| 2023 | 13        | 3.34%   |
| 2007 | 9         | 2.31%   |
| 2006 | 4         | 1.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 389       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 353       | 89.82%  |
| Enabled  | 40        | 10.18%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 376       | 96.66%  |
| Yes  | 13        | 3.34%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 116       | 29.82%  |
| 4.01-8.0    | 108       | 27.76%  |
| 8.01-16.0   | 55        | 14.14%  |
| 16.01-24.0  | 46        | 11.83%  |
| 32.01-64.0  | 23        | 5.91%   |
| 1.01-2.0    | 17        | 4.37%   |
| 64.01-256.0 | 10        | 2.57%   |
| 2.01-3.0    | 7         | 1.8%    |
| 24.01-32.0  | 6         | 1.54%   |
| 0.51-1.0    | 1         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 170       | 41.56%  |
| 2.01-3.0   | 114       | 27.87%  |
| 4.01-8.0   | 39        | 9.54%   |
| 3.01-4.0   | 37        | 9.05%   |
| 0.51-1.0   | 28        | 6.85%   |
| 8.01-16.0  | 17        | 4.16%   |
| 16.01-24.0 | 3         | 0.73%   |
| 24.01-32.0 | 1         | 0.24%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 310       | 79.49%  |
| 2      | 71        | 18.21%  |
| 3      | 5         | 1.28%   |
| 4      | 2         | 0.51%   |
| 0      | 2         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 251       | 64.52%  |
| Yes       | 138       | 35.48%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 294       | 75.58%  |
| No        | 95        | 24.42%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 385       | 98.97%  |
| No        | 4         | 1.03%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 307       | 78.92%  |
| No        | 82        | 21.08%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 58        | 14.87%  |
| France      | 57        | 14.62%  |
| Germany     | 54        | 13.85%  |
| Italy       | 26        | 6.67%   |
| UK          | 18        | 4.62%   |
| Russia      | 13        | 3.33%   |
| Brazil      | 13        | 3.33%   |
| Poland      | 10        | 2.56%   |
| Netherlands | 9         | 2.31%   |
| Czechia     | 9         | 2.31%   |
| Spain       | 8         | 2.05%   |
| India       | 8         | 2.05%   |
| Canada      | 8         | 2.05%   |
| Sweden      | 6         | 1.54%   |
| Mexico      | 6         | 1.54%   |
| Austria     | 5         | 1.28%   |
| Australia   | 5         | 1.28%   |
| Switzerland | 4         | 1.03%   |
| Japan       | 4         | 1.03%   |
| Iran        | 4         | 1.03%   |
| Belgium     | 4         | 1.03%   |
| Vietnam     | 3         | 0.77%   |
| Malaysia    | 3         | 0.77%   |
| Israel      | 3         | 0.77%   |
| Hungary     | 3         | 0.77%   |
| Greece      | 3         | 0.77%   |
| Denmark     | 3         | 0.77%   |
| Colombia    | 3         | 0.77%   |
| Chile       | 3         | 0.77%   |
| Belarus     | 3         | 0.77%   |
| Argentina   | 3         | 0.77%   |
| Venezuela   | 2         | 0.51%   |
| Turkey      | 2         | 0.51%   |
| South Korea | 2         | 0.51%   |
| Romania     | 2         | 0.51%   |
| Indonesia   | 2         | 0.51%   |
| Cuba        | 2         | 0.51%   |
| Uruguay     | 1         | 0.26%   |
| Ukraine     | 1         | 0.26%   |
| Slovenia    | 1         | 0.26%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Warsaw        | 6         | 1.49%   |
| Paris         | 5         | 1.24%   |
| Munich        | 5         | 1.24%   |
| St Petersburg | 4         | 1%      |
| Prague        | 4         | 1%      |
| Milan         | 4         | 1%      |
| Melbourne     | 4         | 1%      |
| Berlin        | 4         | 1%      |
| Uppsala       | 3         | 0.75%   |
| Toulouse      | 3         | 0.75%   |
| Stuttgart     | 3         | 0.75%   |
| North Hills   | 3         | 0.75%   |
| Moscow        | 3         | 0.75%   |
| Kuala Lumpur  | 3         | 0.75%   |
| Hamburg       | 3         | 0.75%   |
| Copenhagen    | 3         | 0.75%   |
| Burgnac       | 3         | 0.75%   |
| Bordeaux      | 3         | 0.75%   |
| Athens        | 3         | 0.75%   |
| York          | 2         | 0.5%    |
| Valenciennes  | 2         | 0.5%    |
| Tehran        | 2         | 0.5%    |
| Springfield   | 2         | 0.5%    |
| Soave         | 2         | 0.5%    |
| Santiago      | 2         | 0.5%    |
| Rome          | 2         | 0.5%    |
| Rochester     | 2         | 0.5%    |
| Rho           | 2         | 0.5%    |
| Puebla City   | 2         | 0.5%    |
| Palmyra       | 2         | 0.5%    |
| Oklahoma City | 2         | 0.5%    |
| Oberhausen    | 2         | 0.5%    |
| Nykvarn       | 2         | 0.5%    |
| Mumbai        | 2         | 0.5%    |
| Minsk         | 2         | 0.5%    |
| Minneapolis   | 2         | 0.5%    |
| Mexico City   | 2         | 0.5%    |
| Los Angeles   | 2         | 0.5%    |
| London        | 2         | 0.5%    |
| Lincoln       | 2         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 81        | 93     | 18.12%  |
| WDC                         | 44        | 52     | 9.84%   |
| Unknown                     | 41        | 50     | 9.17%   |
| Seagate                     | 38        | 45     | 8.5%    |
| Sandisk                     | 24        | 28     | 5.37%   |
| Kingston                    | 24        | 26     | 5.37%   |
| SK hynix                    | 23        | 28     | 5.15%   |
| Hitachi                     | 17        | 17     | 3.8%    |
| Toshiba                     | 15        | 16     | 3.36%   |
| Micron Technology           | 13        | 17     | 2.91%   |
| Intel                       | 13        | 14     | 2.91%   |
| Crucial                     | 12        | 12     | 2.68%   |
| A-DATA Technology           | 8         | 14     | 1.79%   |
| HGST                        | 7         | 8      | 1.57%   |
| China                       | 6         | 8      | 1.34%   |
| SPCC                        | 5         | 5      | 1.12%   |
| PNY                         | 5         | 5      | 1.12%   |
| Phison                      | 5         | 5      | 1.12%   |
| Fujitsu                     | 5         | 5      | 1.12%   |
| KIOXIA                      | 4         | 4      | 0.89%   |
| Transcend                   | 3         | 4      | 0.67%   |
| Netac                       | 3         | 3      | 0.67%   |
| LITEON                      | 3         | 3      | 0.67%   |
| Kingston Technology Company | 3         | 4      | 0.67%   |
| Apple                       | 3         | 5      | 0.67%   |
| Unknown                     | 3         | 3      | 0.67%   |
| USB3.0                      | 2         | 3      | 0.45%   |
| TO Exter                    | 2         | 2      | 0.45%   |
| Team                        | 2         | 5      | 0.45%   |
| Silicon Motion              | 2         | 2      | 0.45%   |
| Lenovo                      | 2         | 2      | 0.45%   |
| KingDian                    | 2         | 2      | 0.45%   |
| Intenso                     | 2         | 2      | 0.45%   |
| FORESEE                     | 2         | 5      | 0.45%   |
| Apacer                      | 2         | 2      | 0.45%   |
| XrayDisk                    | 1         | 1      | 0.22%   |
| UMIS                        | 1         | 1      | 0.22%   |
| SSSTC                       | 1         | 1      | 0.22%   |
| SSD0240S                    | 1         | 1      | 0.22%   |
| ShiJi                       | 1         | 2      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                            | 6         | 1.3%    |
| Seagate ST500LT012-1DG142 500GB                   | 5         | 1.08%   |
| Samsung SSD 860 EVO 500GB                         | 5         | 1.08%   |
| Seagate ST1000LM048-2E7172 1TB                    | 4         | 0.87%   |
| Intel SSDPEKNU512GZ 512GB                         | 4         | 0.87%   |
| Unknown SD/MMC/MS PRO 256GB                       | 3         | 0.65%   |
| Unknown MMC Card  128GB                           | 3         | 0.65%   |
| Toshiba MQ04ABF100 1TB                            | 3         | 0.65%   |
| Toshiba MQ01ABF050 500GB                          | 3         | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB                    | 3         | 0.65%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 3         | 0.65%   |
| Samsung SSD 870 QVO 4TB                           | 3         | 0.65%   |
| Samsung SSD 850 EVO 500GB                         | 3         | 0.65%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB            | 3         | 0.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 3         | 0.65%   |
| Kingston SA400S37480G 480GB SSD                   | 3         | 0.65%   |
| Kingston SA400S37240G 240GB SSD                   | 3         | 0.65%   |
| HGST HTS541010A9E680 1TB                          | 3         | 0.65%   |
| A-DATA SU650 240GB SSD                            | 3         | 0.65%   |
| Unknown                                           | 3         | 0.65%   |
| WDC WDS250G2B0A 250GB SSD                         | 2         | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 2         | 0.43%   |
| WDC WD3200BEVT-22ZCT0 320GB                       | 2         | 0.43%   |
| WDC WD10JPCX-24UE4T0 1TB                          | 2         | 0.43%   |
| WDC PC SN530 SDBPNPZ-512G-1036 512GB              | 2         | 0.43%   |
| USB3.0 Super Speed 500GB SSD                      | 2         | 0.43%   |
| Unknown SA08G  8GB                                | 2         | 0.43%   |
| Unknown MMC64G  64GB                              | 2         | 0.43%   |
| Unknown DF4016  16GB                              | 2         | 0.43%   |
| TO Exter nal USB 3.0 512GB                        | 2         | 0.43%   |
| SPCC Solid State Disk 512GB                       | 2         | 0.43%   |
| SK hynix PC611 NVMe 1TB                           | 2         | 0.43%   |
| Seagate ST500LT012-9WS142 500GB                   | 2         | 0.43%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 2         | 0.43%   |
| Seagate ST500LM000-1EJ162 500GB                   | 2         | 0.43%   |
| Seagate ST1000LM014-1EJ164 1TB                    | 2         | 0.43%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB   | 2         | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                      | 2         | 0.43%   |
| SanDisk DF4032  32GB                              | 2         | 0.43%   |
| Samsung SSD 980 PRO 2TB                           | 2         | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 45     | 33.04%  |
| WDC                 | 26        | 31     | 22.61%  |
| Hitachi             | 17        | 17     | 14.78%  |
| Toshiba             | 12        | 12     | 10.43%  |
| HGST                | 7         | 8      | 6.09%   |
| Fujitsu             | 5         | 5      | 4.35%   |
| Samsung Electronics | 4         | 4      | 3.48%   |
| Unknown             | 3         | 4      | 2.61%   |
| TO Exter            | 2         | 2      | 1.74%   |
| JMicron Technology  | 1         | 1      | 0.87%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 36        | 45     | 23.68%  |
| Kingston            | 19        | 20     | 12.5%   |
| SanDisk             | 12        | 16     | 7.89%   |
| Crucial             | 10        | 10     | 6.58%   |
| A-DATA Technology   | 8         | 14     | 5.26%   |
| WDC                 | 7         | 7      | 4.61%   |
| Micron Technology   | 6         | 7      | 3.95%   |
| China               | 6         | 8      | 3.95%   |
| SPCC                | 5         | 5      | 3.29%   |
| PNY                 | 5         | 5      | 3.29%   |
| Transcend           | 3         | 3      | 1.97%   |
| SK hynix            | 3         | 3      | 1.97%   |
| LITEON              | 3         | 3      | 1.97%   |
| USB3.0              | 2         | 3      | 1.32%   |
| Netac               | 2         | 2      | 1.32%   |
| KingDian            | 2         | 2      | 1.32%   |
| Intenso             | 2         | 2      | 1.32%   |
| Intel               | 2         | 2      | 1.32%   |
| FORESEE             | 2         | 5      | 1.32%   |
| Apacer              | 2         | 2      | 1.32%   |
| Toshiba             | 1         | 1      | 0.66%   |
| Team                | 1         | 4      | 0.66%   |
| SSSTC               | 1         | 1      | 0.66%   |
| ShiJi               | 1         | 1      | 0.66%   |
| Patriot             | 1         | 1      | 0.66%   |
| LITEONIT            | 1         | 1      | 0.66%   |
| KingSpec            | 1         | 1      | 0.66%   |
| Kimtigo             | 1         | 1      | 0.66%   |
| INNOVATION IT       | 1         | 1      | 0.66%   |
| EVM                 | 1         | 1      | 0.66%   |
| BHT                 | 1         | 1      | 0.66%   |
| ASMT                | 1         | 4      | 0.66%   |
| Apple               | 1         | 1      | 0.66%   |
| addlink             | 1         | 1      | 0.66%   |
| Unknown             | 1         | 1      | 0.66%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 140       | 185    | 32.33%  |
| NVMe    | 135       | 155    | 31.18%  |
| HDD     | 111       | 129    | 25.64%  |
| MMC     | 43        | 52     | 9.93%   |
| Unknown | 4         | 4      | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 234       | 297    | 54.67%  |
| NVMe | 134       | 154    | 31.31%  |
| MMC  | 43        | 52     | 10.05%  |
| SAS  | 17        | 22     | 3.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 184       | 221    | 71.6%   |
| 0.51-1.0   | 61        | 75     | 23.74%  |
| 1.01-2.0   | 7         | 13     | 2.72%   |
| 3.01-4.0   | 4         | 4      | 1.56%   |
| 4.01-10.0  | 1         | 1      | 0.39%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 116       | 29.29%  |
| 101-250        | 116       | 29.29%  |
| 501-1000       | 52        | 13.13%  |
| 51-100         | 33        | 8.33%   |
| 1-20           | 28        | 7.07%   |
| 21-50          | 21        | 5.3%    |
| 1001-2000      | 18        | 4.55%   |
| More than 3000 | 9         | 2.27%   |
| 2001-3000      | 2         | 0.51%   |
| Unknown        | 1         | 0.25%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 151       | 36.83%  |
| 21-50          | 91        | 22.2%   |
| 101-250        | 64        | 15.61%  |
| 51-100         | 49        | 11.95%  |
| 251-500        | 25        | 6.1%    |
| 501-1000       | 21        | 5.12%   |
| 1001-2000      | 6         | 1.46%   |
| More than 3000 | 1         | 0.24%   |
| 2001-3000      | 1         | 0.24%   |
| Unknown        | 1         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB                     | 2         | 2      | 4.35%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 2      | 4.35%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 2      | 4.35%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                    | 1         | 1      | 2.17%   |
| WDC WD5000LPVT-08G33T1 500GB                        | 1         | 1      | 2.17%   |
| WDC WD1200BEVS-60UST0 120GB                         | 1         | 1      | 2.17%   |
| Toshiba MK5065GSXN 500GB                            | 1         | 1      | 2.17%   |
| Toshiba MK1246GSX 120GB                             | 1         | 1      | 2.17%   |
| SSSTC CVB-8D128-HP 128GB                            | 1         | 1      | 2.17%   |
| Seagate ST9500325ASG 500GB                          | 1         | 1      | 2.17%   |
| Seagate ST9500325AS 500GB                           | 1         | 1      | 2.17%   |
| Seagate ST320LT007-9ZV142 320GB                     | 1         | 1      | 2.17%   |
| Seagate ST1000LM 035-1RK172 1TB                     | 1         | 1      | 2.17%   |
| SanDisk SSD PLUS 480GB                              | 1         | 1      | 2.17%   |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 2.17%   |
| Samsung Electronics SSD PM810 FDE 2.5 128GB         | 1         | 1      | 2.17%   |
| Samsung Electronics MZNLH128HBHQ-000H1 128GB SSD    | 1         | 1      | 2.17%   |
| Samsung Electronics HM160HC 160GB                   | 1         | 1      | 2.17%   |
| Micron Technology MTFDDAK512TBN-1AR1ZABHA 512GB SSD | 1         | 1      | 2.17%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD      | 1         | 1      | 2.17%   |
| LITEON LCH-512V2S 512GB SSD                         | 1         | 1      | 2.17%   |
| LITEON CV8-8E128-HP 128GB SSD                       | 1         | 1      | 2.17%   |
| Kingston SNS4151S332GD 32GB SSD                     | 1         | 2      | 2.17%   |
| Kingston SNS4151S316GD 16GB SSD                     | 1         | 1      | 2.17%   |
| Kingston OM8S1S3128K-AH 128GB SSD                   | 1         | 1      | 2.17%   |
| JMicron Technology Generic 8GB                      | 1         | 1      | 2.17%   |
| Intenso SSD Sata III 250GB                          | 1         | 1      | 2.17%   |
| Intel SSDSCKKF240H6L 240GB                          | 1         | 1      | 2.17%   |
| Hitachi HTS725050A9A364 500GB                       | 1         | 1      | 2.17%   |
| Hitachi HTS545032A7E380 320GB                       | 1         | 1      | 2.17%   |
| Hitachi HTS545025B9SA02 250GB                       | 1         | 1      | 2.17%   |
| Hitachi HTS543216L9A300 160GB                       | 1         | 1      | 2.17%   |
| Hitachi HTS543212L9A300 120GB                       | 1         | 1      | 2.17%   |
| Hitachi HTS541680J9SA00 80GB                        | 1         | 1      | 2.17%   |
| Hitachi HTS541080G9SA00 80GB                        | 1         | 1      | 2.17%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 2.17%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 2.17%   |
| Fujitsu MHZ2250BH G2 250GB                          | 1         | 1      | 2.17%   |
| Fujitsu MHZ2160BJ FFS G2 160GB                      | 1         | 1      | 2.17%   |
| Fujitsu MHY2160BH 160GB                             | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 21.74%  |
| Hitachi             | 7         | 7      | 15.22%  |
| Fujitsu             | 4         | 4      | 8.7%    |
| WDC                 | 3         | 3      | 6.52%   |
| Samsung Electronics | 3         | 3      | 6.52%   |
| Kingston            | 3         | 4      | 6.52%   |
| Toshiba             | 2         | 2      | 4.35%   |
| SanDisk             | 2         | 2      | 4.35%   |
| Micron Technology   | 2         | 2      | 4.35%   |
| LITEON              | 2         | 2      | 4.35%   |
| HGST                | 2         | 2      | 4.35%   |
| SSSTC               | 1         | 1      | 2.17%   |
| JMicron Technology  | 1         | 1      | 2.17%   |
| Intenso             | 1         | 1      | 2.17%   |
| Intel               | 1         | 1      | 2.17%   |
| Apple               | 1         | 1      | 2.17%   |
| Unknown             | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 34.48%  |
| Hitachi             | 7         | 7      | 24.14%  |
| Fujitsu             | 4         | 4      | 13.79%  |
| WDC                 | 2         | 2      | 6.9%    |
| Toshiba             | 2         | 2      | 6.9%    |
| HGST                | 2         | 2      | 6.9%    |
| Samsung Electronics | 1         | 1      | 3.45%   |
| JMicron Technology  | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 29     | 62.22%  |
| SSD  | 17        | 18     | 37.78%  |

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
| Works    | 209       | 244    | 50.61%  |
| Detected | 159       | 234    | 38.5%   |
| Malfunc  | 45        | 47     | 10.9%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 253       | 58.43%  |
| AMD                          | 50        | 11.55%  |
| Samsung Electronics          | 42        | 9.7%    |
| SanDisk                      | 21        | 4.85%   |
| SK hynix                     | 19        | 4.39%   |
| Kingston Technology Company  | 9         | 2.08%   |
| Nvidia                       | 6         | 1.39%   |
| Micron Technology            | 6         | 1.39%   |
| Phison Electronics           | 5         | 1.15%   |
| KIOXIA                       | 4         | 0.92%   |
| Silicon Motion               | 3         | 0.69%   |
| Micron/Crucial Technology    | 3         | 0.69%   |
| Toshiba America Info Systems | 2         | 0.46%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.46%   |
| Lenovo                       | 2         | 0.46%   |
| Apple                        | 2         | 0.46%   |
| Union Memory (Shenzhen)      | 1         | 0.23%   |
| Realtek Semiconductor        | 1         | 0.23%   |
| Netac Technology             | 1         | 0.23%   |
| Hosin Global Electronics     | 1         | 0.23%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 44        | 9.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 28        | 6.01%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 22        | 4.72%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 19        | 4.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 18        | 3.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 17        | 3.65%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 16        | 3.43%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 14        | 3%      |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 12        | 2.58%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 11        | 2.36%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 2.15%   |
| Intel Tiger Lake-LP SATA Controller                                              | 10        | 2.15%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 2.15%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 9         | 1.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 8         | 1.72%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 1.72%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 8         | 1.72%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 7         | 1.5%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 7         | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 7         | 1.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 1.5%    |
| Intel SSD 670p Series [Keystone Harbor]                                          | 6         | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 6         | 1.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 6         | 1.29%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 6         | 1.29%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 6         | 1.29%   |
| SK hynix PC611 NVMe Solid State Drive                                            | 5         | 1.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 5         | 1.07%   |
| Intel Comet Lake SATA AHCI Controller                                            | 5         | 1.07%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 1.07%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 4         | 0.86%   |
| Nvidia MCP79 AHCI Controller                                                     | 4         | 0.86%   |
| Intel SSD 660P Series                                                            | 4         | 0.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 4         | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 0.86%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 0.86%   |
| SK hynix PC401 NVMe Solid State Drive 256GB                                      | 3         | 0.64%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                    | 3         | 0.64%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                              | 3         | 0.64%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 3         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 274       | 59.57%  |
| NVMe | 134       | 29.13%  |
| RAID | 29        | 6.3%    |
| IDE  | 23        | 5%      |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 314       | 80.72%  |
| AMD    | 75        | 19.28%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 9         | 2.31%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 8         | 2.06%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 8         | 2.06%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 7         | 1.8%    |
| Intel Celeron N4020 CPU @ 1.10GHz           | 7         | 1.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz           | 6         | 1.54%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 6         | 1.54%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 6         | 1.54%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 6         | 1.54%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 5         | 1.29%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 5         | 1.29%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 5         | 1.29%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 4         | 1.03%   |
| Intel Core i5-6200U CPU @ 2.30GHz           | 4         | 1.03%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 4         | 1.03%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 4         | 1.03%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 4         | 1.03%   |
| Intel Celeron CPU N3450 @ 1.10GHz           | 4         | 1.03%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 4         | 1.03%   |
| Intel 12th Gen Core i7-1260P                | 4         | 1.03%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 4         | 1.03%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 3         | 0.77%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 0.77%   |
| Intel Core i7-6600U CPU @ 2.60GHz           | 3         | 0.77%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 3         | 0.77%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 3         | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 0.77%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 3         | 0.77%   |
| Intel Core 2 Duo CPU P8800 @ 2.66GHz        | 3         | 0.77%   |
| Intel Core 2 CPU T7200 @ 2.00GHz            | 3         | 0.77%   |
| Intel Celeron 3205U @ 1.50GHz               | 3         | 0.77%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 3         | 0.77%   |
| AMD Ryzen 7 4800H with Radeon Graphics      | 3         | 0.77%   |
| AMD Ryzen 5 PRO 5650U with Radeon Graphics  | 3         | 0.77%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics | 3         | 0.77%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz    | 2         | 0.51%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 2         | 0.51%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 2         | 0.51%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 2         | 0.51%   |
| Intel Core i7-5600U CPU @ 2.60GHz           | 2         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 80        | 20.57%  |
| Intel Celeron           | 53        | 13.62%  |
| Intel Core i7           | 47        | 12.08%  |
| Other                   | 46        | 11.83%  |
| Intel Core i3           | 28        | 7.2%    |
| Intel Core 2 Duo        | 25        | 6.43%   |
| AMD Ryzen 5             | 16        | 4.11%   |
| AMD Ryzen 7             | 14        | 3.6%    |
| Intel Atom              | 7         | 1.8%    |
| AMD A4                  | 7         | 1.8%    |
| Intel Core 2            | 6         | 1.54%   |
| AMD A6                  | 6         | 1.54%   |
| Intel Pentium           | 5         | 1.29%   |
| AMD A8                  | 5         | 1.29%   |
| AMD Ryzen 9             | 4         | 1.03%   |
| AMD Ryzen 3             | 4         | 1.03%   |
| Intel Pentium Dual-Core | 3         | 0.77%   |
| Intel Pentium Dual      | 3         | 0.77%   |
| Intel Genuine           | 3         | 0.77%   |
| AMD Ryzen 7 PRO         | 3         | 0.77%   |
| AMD Ryzen 5 PRO         | 3         | 0.77%   |
| AMD E1                  | 3         | 0.77%   |
| Intel Pentium Silver    | 2         | 0.51%   |
| AMD E2                  | 2         | 0.51%   |
| AMD A10                 | 2         | 0.51%   |
| Intel Xeon              | 1         | 0.26%   |
| Intel Core m7           | 1         | 0.26%   |
| Intel Core m3           | 1         | 0.26%   |
| Intel Core M            | 1         | 0.26%   |
| Intel Core i9           | 1         | 0.26%   |
| Intel Core 2 Extreme    | 1         | 0.26%   |
| Intel Celeron Dual-Core | 1         | 0.26%   |
| AMD V120                | 1         | 0.26%   |
| AMD FX                  | 1         | 0.26%   |
| AMD E                   | 1         | 0.26%   |
| AMD Athlon II           | 1         | 0.26%   |
| AMD Athlon              | 1         | 0.26%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 215       | 55.27%  |
| 4      | 98        | 25.19%  |
| 6      | 27        | 6.94%   |
| 8      | 23        | 5.91%   |
| 10     | 8         | 2.06%   |
| 1      | 7         | 1.8%    |
| 12     | 5         | 1.29%   |
| 16     | 3         | 0.77%   |
| 14     | 3         | 0.77%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 389       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 254       | 65.3%   |
| 1      | 135       | 34.7%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 389       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 170       | 42.82%  |
| 0x806c1    | 18        | 4.53%   |
| 0x406e3    | 12        | 3.02%   |
| 0x08608103 | 9         | 2.27%   |
| 0x706a8    | 8         | 2.02%   |
| 0x306d4    | 8         | 2.02%   |
| 0x1067a    | 8         | 2.02%   |
| 0x806ec    | 7         | 1.76%   |
| 0x306a9    | 7         | 1.76%   |
| 0x206a7    | 7         | 1.76%   |
| 0x20655    | 7         | 1.76%   |
| 0x506c9    | 6         | 1.51%   |
| 0x30678    | 6         | 1.51%   |
| 0xa0652    | 5         | 1.26%   |
| 0x906ea    | 5         | 1.26%   |
| 0x806ea    | 5         | 1.26%   |
| 0x806e9    | 5         | 1.26%   |
| 0x6fd      | 5         | 1.26%   |
| 0x406c4    | 5         | 1.26%   |
| 0x406c3    | 5         | 1.26%   |
| 0x07030105 | 5         | 1.26%   |
| 0x6f6      | 4         | 1.01%   |
| 0x40651    | 4         | 1.01%   |
| 0x08108109 | 4         | 1.01%   |
| 0x06006705 | 4         | 1.01%   |
| 0x906a3    | 3         | 0.76%   |
| 0x806d1    | 3         | 0.76%   |
| 0x6fb      | 3         | 0.76%   |
| 0x506e3    | 3         | 0.76%   |
| 0x10676    | 3         | 0.76%   |
| 0x0a50000c | 3         | 0.76%   |
| 0x08600106 | 3         | 0.76%   |
| 0x05000119 | 3         | 0.76%   |
| 0x906a4    | 2         | 0.5%    |
| 0x706a1    | 2         | 0.5%    |
| 0x506ca    | 2         | 0.5%    |
| 0x306c3    | 2         | 0.5%    |
| 0x20652    | 2         | 0.5%    |
| 0x0a601203 | 2         | 0.5%    |
| 0x0a50000d | 2         | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 42        | 10.74%  |
| Penryn           | 28        | 7.16%   |
| Unknown          | 27        | 6.91%   |
| Skylake          | 25        | 6.39%   |
| Silvermont       | 25        | 6.39%   |
| TigerLake        | 24        | 6.14%   |
| SandyBridge      | 24        | 6.14%   |
| IvyBridge        | 18        | 4.6%    |
| Haswell          | 18        | 4.6%    |
| Core             | 16        | 4.09%   |
| Broadwell        | 16        | 4.09%   |
| Westmere         | 15        | 3.84%   |
| Goldmont plus    | 14        | 3.58%   |
| Alderlake Hybrid | 13        | 3.32%   |
| Goldmont         | 10        | 2.56%   |
| Zen 3            | 9         | 2.3%    |
| CometLake        | 9         | 2.3%    |
| Zen 2            | 8         | 2.05%   |
| Puma             | 8         | 2.05%   |
| IceLake          | 8         | 2.05%   |
| Zen+             | 7         | 1.79%   |
| Excavator        | 7         | 1.79%   |
| Bobcat           | 4         | 1.02%   |
| K10 Llano        | 3         | 0.77%   |
| Bonnell          | 3         | 0.77%   |
| Steamroller      | 2         | 0.51%   |
| Piledriver       | 2         | 0.51%   |
| K10              | 2         | 0.51%   |
| Jaguar           | 2         | 0.51%   |
| Tremont          | 1         | 0.26%   |
| Nehalem          | 1         | 0.26%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 287       | 62.26%  |
| AMD    | 90        | 19.52%  |
| Nvidia | 84        | 18.22%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 4.81%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 20        | 4.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 18        | 3.77%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 3.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 17        | 3.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 3.35%   |
| Intel HD Graphics 5500                                                                   | 12        | 2.51%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 12        | 2.51%   |
| AMD Lucienne                                                                             | 12        | 2.51%   |
| Intel HD Graphics 620                                                                    | 11        | 2.3%    |
| Intel HD Graphics 500                                                                    | 10        | 2.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 10        | 2.09%   |
| Intel Core Processor Integrated Graphics Controller                                      | 10        | 2.09%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 9         | 1.88%   |
| Intel UHD Graphics 620                                                                   | 8         | 1.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.67%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 1.67%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 8         | 1.67%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 1.46%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 1.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 1.05%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.05%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 5         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.05%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 1.05%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 5         | 1.05%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 5         | 1.05%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.05%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 1.05%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 4         | 0.84%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 0.84%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 4         | 0.84%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 4         | 0.84%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 4         | 0.84%   |
| Nvidia TU117M [GeForce MX450]                                                            | 3         | 0.63%   |
| Nvidia GM107GLM [Quadro M1000M]                                                          | 3         | 0.63%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 3         | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 222       | 57.07%  |
| 1 x AMD        | 62        | 15.94%  |
| Intel + Nvidia | 51        | 13.11%  |
| 1 x Nvidia     | 22        | 5.66%   |
| AMD + Nvidia   | 11        | 2.83%   |
| Intel + AMD    | 10        | 2.57%   |
| 2 x AMD        | 7         | 1.8%    |
| Other          | 4         | 1.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 347       | 88.52%  |
| Proprietary | 38        | 9.69%   |
| Unknown     | 7         | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 290       | 74.17%  |
| 0.01-0.5   | 51        | 13.04%  |
| 0.51-1.0   | 20        | 5.12%   |
| 1.01-2.0   | 15        | 3.84%   |
| 3.01-4.0   | 10        | 2.56%   |
| 5.01-6.0   | 3         | 0.77%   |
| 7.01-8.0   | 1         | 0.26%   |
| 8.01-16.0  | 1         | 0.26%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 93        | 21.53%  |
| BOE                     | 68        | 15.74%  |
| LG Display              | 67        | 15.51%  |
| Chimei Innolux          | 48        | 11.11%  |
| Samsung Electronics     | 37        | 8.56%   |
| Dell                    | 16        | 3.7%    |
| Apple                   | 11        | 2.55%   |
| PANDA                   | 8         | 1.85%   |
| Lenovo                  | 8         | 1.85%   |
| Chi Mei Optoelectronics | 8         | 1.85%   |
| InfoVision              | 7         | 1.62%   |
| Goldstar                | 7         | 1.62%   |
| Sharp                   | 6         | 1.39%   |
| LG Philips              | 5         | 1.16%   |
| Philips                 | 4         | 0.93%   |
| Hewlett-Packard         | 3         | 0.69%   |
| BenQ                    | 3         | 0.69%   |
| Acer                    | 3         | 0.69%   |
| Vizio                   | 2         | 0.46%   |
| ViewSonic               | 2         | 0.46%   |
| Sony                    | 2         | 0.46%   |
| KDC                     | 2         | 0.46%   |
| Iiyama                  | 2         | 0.46%   |
| CSO                     | 2         | 0.46%   |
| CPT                     | 2         | 0.46%   |
| Toshiba                 | 1         | 0.23%   |
| TMX                     | 1         | 0.23%   |
| SNC                     | 1         | 0.23%   |
| Sceptre Tech            | 1         | 0.23%   |
| SANSUI                  | 1         | 0.23%   |
| SAC                     | 1         | 0.23%   |
| Quanta Display          | 1         | 0.23%   |
| Panasonic               | 1         | 0.23%   |
| Olevia                  | 1         | 0.23%   |
| IBM                     | 1         | 0.23%   |
| HUAWEI                  | 1         | 0.23%   |
| HannStar                | 1         | 0.23%   |
| GreenWood               | 1         | 0.23%   |
| DPL                     | 1         | 0.23%   |
| AOC                     | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.15%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 4         | 0.92%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 4         | 0.92%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 4         | 0.92%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 0.69%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.69%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 3         | 0.69%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 0.69%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                     | 3         | 0.69%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.69%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                    | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 2         | 0.46%   |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD059D 1920x1080 309x174mm 14.0-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD0514 1920x1080 309x174mm 14.0-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.46%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.46%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch              | 2         | 0.46%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 2         | 0.46%   |
| Lenovo LCD Monitor LEN4011 1280x800 261x163mm 12.1-inch                  | 2         | 0.46%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch          | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN153C 1920x1080 344x193mm 15.5-inch         | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 2         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1139 1366x768 256x144mm 11.6-inch          | 2         | 0.46%   |
| BOE NE173QHM-NZ2 BOE0B69 2560x1440 381x214mm 17.2-inch                   | 2         | 0.46%   |
| BOE LCD Monitor BOE092E 1920x1080 310x173mm 14.0-inch                    | 2         | 0.46%   |
| BOE LCD Monitor BOE08C2 1920x1080 344x194mm 15.5-inch                    | 2         | 0.46%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.46%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 2         | 0.46%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.46%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 2         | 0.46%   |
| AU Optronics LCD Monitor AUOD291 1920x1200 301x188mm 14.0-inch           | 2         | 0.46%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 2         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 164       | 40.1%   |
| 1366x768 (WXGA)    | 124       | 30.32%  |
| 1600x900 (HD+)     | 28        | 6.85%   |
| 1280x800 (WXGA)    | 23        | 5.62%   |
| 1920x1200 (WUXGA)  | 14        | 3.42%   |
| 3840x2160 (4K)     | 12        | 2.93%   |
| 1440x900 (WXGA+)   | 9         | 2.2%    |
| 2560x1440 (QHD)    | 8         | 1.96%   |
| 1680x1050 (WSXGA+) | 4         | 0.98%   |
| 1024x600           | 3         | 0.73%   |
| 2560x1600          | 2         | 0.49%   |
| 2160x1440          | 2         | 0.49%   |
| 1024x768 (XGA)     | 2         | 0.49%   |
| 3840x2400          | 1         | 0.24%   |
| 3840x1600          | 1         | 0.24%   |
| 3440x1440          | 1         | 0.24%   |
| 3200x1800 (QHD+)   | 1         | 0.24%   |
| 2880x1800          | 1         | 0.24%   |
| 2880x1620          | 1         | 0.24%   |
| 2560x1080          | 1         | 0.24%   |
| 2304x1440          | 1         | 0.24%   |
| 2240x1400          | 1         | 0.24%   |
| 1920x540           | 1         | 0.24%   |
| 1920x515           | 1         | 0.24%   |
| 1366x912           | 1         | 0.24%   |
| 1360x768           | 1         | 0.24%   |
| 1280x1024 (SXGA)   | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 172       | 39.81%  |
| 14      | 68        | 15.74%  |
| 13      | 58        | 13.43%  |
| 17      | 33        | 7.64%   |
| 27      | 14        | 3.24%   |
| 12      | 14        | 3.24%   |
| 11      | 14        | 3.24%   |
| 24      | 11        | 2.55%   |
| 23      | 10        | 2.31%   |
| 21      | 7         | 1.62%   |
| 16      | 7         | 1.62%   |
| Unknown | 6         | 1.39%   |
| 10      | 3         | 0.69%   |
| 34      | 2         | 0.46%   |
| 31      | 2         | 0.46%   |
| 18      | 2         | 0.46%   |
| 86      | 1         | 0.23%   |
| 84      | 1         | 0.23%   |
| 42      | 1         | 0.23%   |
| 37      | 1         | 0.23%   |
| 32      | 1         | 0.23%   |
| 26      | 1         | 0.23%   |
| 22      | 1         | 0.23%   |
| 20      | 1         | 0.23%   |
| 19      | 1         | 0.23%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 270       | 63.08%  |
| 201-300     | 61        | 14.25%  |
| 351-400     | 36        | 8.41%   |
| 501-600     | 32        | 7.48%   |
| 401-500     | 12        | 2.8%    |
| Unknown     | 6         | 1.4%    |
| 601-700     | 4         | 0.93%   |
| 701-800     | 3         | 0.7%    |
| 801-900     | 1         | 0.23%   |
| 1501-2000   | 1         | 0.23%   |
| 1001-1500   | 1         | 0.23%   |
| 901-1000    | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 322       | 82.35%  |
| 16/10   | 54        | 13.81%  |
| 3/2     | 5         | 1.28%   |
| 21/9    | 3         | 0.77%   |
| 4/3     | 2         | 0.51%   |
| 6/5     | 1         | 0.26%   |
| 32/9    | 1         | 0.26%   |
| 3.73    | 1         | 0.26%   |
| 0.56    | 1         | 0.26%   |
| Unknown | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 171       | 39.68%  |
| 81-90          | 103       | 23.9%   |
| 121-130        | 27        | 6.26%   |
| 201-250        | 26        | 6.03%   |
| 71-80          | 23        | 5.34%   |
| 51-60          | 14        | 3.25%   |
| 301-350        | 14        | 3.25%   |
| 61-70          | 13        | 3.02%   |
| 131-140        | 7         | 1.62%   |
| Unknown        | 6         | 1.39%   |
| 351-500        | 5         | 1.16%   |
| 151-200        | 5         | 1.16%   |
| 111-120        | 5         | 1.16%   |
| 41-50          | 3         | 0.7%    |
| More than 1000 | 2         | 0.46%   |
| 251-300        | 2         | 0.46%   |
| 501-1000       | 2         | 0.46%   |
| 91-100         | 2         | 0.46%   |
| 141-150        | 1         | 0.23%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 180       | 42.45%  |
| 101-120       | 143       | 33.73%  |
| 51-100        | 59        | 13.92%  |
| 161-240       | 30        | 7.08%   |
| Unknown       | 6         | 1.42%   |
| More than 240 | 5         | 1.18%   |
| 1-50          | 1         | 0.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 327       | 83.63%  |
| 2     | 52        | 13.3%   |
| 3     | 6         | 1.53%   |
| 0     | 6         | 1.53%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 202       | 34.12%  |
| Realtek Semiconductor             | 197       | 33.28%  |
| Qualcomm Atheros                  | 68        | 11.49%  |
| Broadcom                          | 43        | 7.26%   |
| MediaTek                          | 13        | 2.2%    |
| Marvell Technology Group          | 9         | 1.52%   |
| Broadcom Limited                  | 6         | 1.01%   |
| TP-Link                           | 5         | 0.84%   |
| Sierra Wireless                   | 5         | 0.84%   |
| Qualcomm                          | 5         | 0.84%   |
| Samsung Electronics               | 4         | 0.68%   |
| Nvidia                            | 4         | 0.68%   |
| Dell                              | 4         | 0.68%   |
| Ralink                            | 3         | 0.51%   |
| Ericsson Business Mobile Networks | 3         | 0.51%   |
| Ralink Technology                 | 2         | 0.34%   |
| Huawei Technologies               | 2         | 0.34%   |
| Hewlett-Packard                   | 2         | 0.34%   |
| Xiaomi                            | 1         | 0.17%   |
| SEGGER                            | 1         | 0.17%   |
| Qualcomm Atheros Communications   | 1         | 0.17%   |
| OPPO Electronics                  | 1         | 0.17%   |
| NetGear                           | 1         | 0.17%   |
| Microchip Technology              | 1         | 0.17%   |
| LG Electronics                    | 1         | 0.17%   |
| Lenovo                            | 1         | 0.17%   |
| JMicron Technology                | 1         | 0.17%   |
| DisplayLink                       | 1         | 0.17%   |
| D-Link                            | 1         | 0.17%   |
| BUFFALO                           | 1         | 0.17%   |
| Attansic Technology               | 1         | 0.17%   |
| ASIX Electronics                  | 1         | 0.17%   |
| Apple                             | 1         | 0.17%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 105       | 14.4%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 37        | 5.08%   |
| Intel Wireless 8260                                                    | 19        | 2.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 17        | 2.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 16        | 2.19%   |
| Intel Wi-Fi 6 AX200                                                    | 16        | 2.19%   |
| Intel Wireless 7265                                                    | 15        | 2.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 14        | 1.92%   |
| Intel Wireless 7260                                                    | 14        | 1.92%   |
| Intel Wi-Fi 6 AX201                                                    | 13        | 1.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 12        | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 11        | 1.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 11        | 1.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 11        | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 10        | 1.37%   |
| Intel Ethernet Connection I219-LM                                      | 10        | 1.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 10        | 1.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 1.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 1.23%   |
| Broadcom BCM43142 802.11b/g/n                                          | 9         | 1.23%   |
| Intel Wireless 8265 / 8275                                             | 8         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 8         | 1.1%    |
| Intel Wireless 3165                                                    | 7         | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 7         | 0.96%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 7         | 0.96%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 7         | 0.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 7         | 0.96%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 6         | 0.82%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 0.82%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 6         | 0.82%   |
| Intel Centrino Advanced-N 6200                                         | 6         | 0.82%   |
| Intel 82577LM Gigabit Network Connection                               | 6         | 0.82%   |
| Realtek 802.11n WLAN Adapter                                           | 5         | 0.69%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.69%   |
| Intel Wireless 3160                                                    | 5         | 0.69%   |
| Intel Raptor Lake PCH CNVi WiFi                                        | 5         | 0.69%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection          | 5         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                                  | 5         | 0.69%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                           | 5         | 0.69%   |
| Intel 82567LM Gigabit Network Connection                               | 5         | 0.69%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 200       | 49.02%  |
| Realtek Semiconductor           | 74        | 18.14%  |
| Qualcomm Atheros                | 62        | 15.2%   |
| Broadcom                        | 33        | 8.09%   |
| MediaTek                        | 12        | 2.94%   |
| Sierra Wireless                 | 5         | 1.23%   |
| Qualcomm                        | 5         | 1.23%   |
| TP-Link                         | 4         | 0.98%   |
| Ralink                          | 3         | 0.74%   |
| Ralink Technology               | 2         | 0.49%   |
| Dell                            | 2         | 0.49%   |
| Broadcom Limited                | 2         | 0.49%   |
| Qualcomm Atheros Communications | 1         | 0.25%   |
| NetGear                         | 1         | 0.25%   |
| D-Link                          | 1         | 0.25%   |
| BUFFALO                         | 1         | 0.25%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wireless 8260                                            | 19        | 4.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 17        | 4.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 16        | 3.84%   |
| Intel Wi-Fi 6 AX200                                            | 16        | 3.84%   |
| Intel Wireless 7265                                            | 15        | 3.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 14        | 3.36%   |
| Intel Wireless 7260                                            | 14        | 3.36%   |
| Intel Wi-Fi 6 AX201                                            | 13        | 3.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12        | 2.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 11        | 2.64%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 11        | 2.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 10        | 2.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 10        | 2.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 9         | 2.16%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 2.16%   |
| Intel Wireless 8265 / 8275                                     | 8         | 1.92%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 8         | 1.92%   |
| Intel Wireless 3165                                            | 7         | 1.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 7         | 1.68%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 7         | 1.68%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 7         | 1.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 1.68%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 6         | 1.44%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.44%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 6         | 1.44%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 1.44%   |
| Realtek 802.11n WLAN Adapter                                   | 5         | 1.2%    |
| Intel Wireless 3160                                            | 5         | 1.2%    |
| Intel Raptor Lake PCH CNVi WiFi                                | 5         | 1.2%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 5         | 1.2%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 5         | 1.2%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 4         | 0.96%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 4         | 0.96%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 0.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4         | 0.96%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 4         | 0.96%   |
| Intel Ultimate N WiFi Link 5300                                | 4         | 0.96%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 4         | 0.96%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 0.96%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 158       | 51.97%  |
| Intel                    | 78        | 25.66%  |
| Qualcomm Atheros         | 16        | 5.26%   |
| Broadcom                 | 15        | 4.93%   |
| Marvell Technology Group | 9         | 2.96%   |
| Samsung Electronics      | 4         | 1.32%   |
| Nvidia                   | 4         | 1.32%   |
| Broadcom Limited         | 4         | 1.32%   |
| Huawei Technologies      | 2         | 0.66%   |
| Hewlett-Packard          | 2         | 0.66%   |
| Xiaomi                   | 1         | 0.33%   |
| TP-Link                  | 1         | 0.33%   |
| OPPO Electronics         | 1         | 0.33%   |
| Microchip Technology     | 1         | 0.33%   |
| MediaTek                 | 1         | 0.33%   |
| LG Electronics           | 1         | 0.33%   |
| Lenovo                   | 1         | 0.33%   |
| JMicron Technology       | 1         | 0.33%   |
| DisplayLink              | 1         | 0.33%   |
| Attansic Technology      | 1         | 0.33%   |
| ASIX Electronics         | 1         | 0.33%   |
| Apple                    | 1         | 0.33%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 105       | 34.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 37        | 12.09%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 11        | 3.59%   |
| Intel Ethernet Connection I219-LM                                              | 10        | 3.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 10        | 3.27%   |
| Intel 82577LM Gigabit Network Connection                                       | 6         | 1.96%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 5         | 1.63%   |
| Intel Ethernet Connection (3) I218-LM                                          | 5         | 1.63%   |
| Intel 82567LM Gigabit Network Connection                                       | 5         | 1.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 4         | 1.31%   |
| Nvidia MCP79 Ethernet                                                          | 4         | 1.31%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 4         | 1.31%   |
| Intel Ethernet Connection (4) I219-LM                                          | 4         | 1.31%   |
| Intel Ethernet Connection (16) I219-V                                          | 4         | 1.31%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 3         | 0.98%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 0.98%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 3         | 0.98%   |
| Intel Ethernet Connection I219-V                                               | 3         | 0.98%   |
| Intel Ethernet Connection I217-LM                                              | 3         | 0.98%   |
| Intel Ethernet Connection (13) I219-V                                          | 3         | 0.98%   |
| Intel 82566MM Gigabit Network Connection                                       | 3         | 0.98%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 0.98%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 0.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 2         | 0.65%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.65%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 2         | 0.65%   |
| Intel Ethernet Connection I218-LM                                              | 2         | 0.65%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.65%   |
| Intel Ethernet Connection (11) I219-LM                                         | 2         | 0.65%   |
| Huawei STG-LX1                                                                 | 2         | 0.65%   |
| HP lt4120 Snapdragon X5 LTE                                                    | 2         | 0.65%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 2         | 0.65%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 2         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1         | 0.33%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 1         | 0.33%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.33%   |
| Realtek Killer E2600 GbE Controller                                            | 1         | 0.33%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 385       | 56.2%   |
| Ethernet | 294       | 42.92%  |
| Modem    | 6         | 0.88%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 341       | 84.2%   |
| Ethernet | 64        | 15.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 273       | 70.18%  |
| 1     | 103       | 26.48%  |
| 0     | 12        | 3.08%   |
| 3     | 1         | 0.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 262       | 66.5%   |
| Yes  | 132       | 33.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 143       | 46.43%  |
| Realtek Semiconductor           | 43        | 13.96%  |
| Broadcom                        | 21        | 6.82%   |
| Qualcomm Atheros Communications | 19        | 6.17%   |
| Foxconn / Hon Hai               | 15        | 4.87%   |
| Lite-On Technology              | 14        | 4.55%   |
| IMC Networks                    | 13        | 4.22%   |
| Apple                           | 10        | 3.25%   |
| Dell                            | 5         | 1.62%   |
| Realtek                         | 4         | 1.3%    |
| Hewlett-Packard                 | 4         | 1.3%    |
| Foxconn International           | 3         | 0.97%   |
| Cambridge Silicon Radio         | 3         | 0.97%   |
| ASUSTek Computer                | 2         | 0.65%   |
| USI                             | 1         | 0.32%   |
| Toshiba                         | 1         | 0.32%   |
| Taiyo Yuden                     | 1         | 0.32%   |
| Ralink Technology               | 1         | 0.32%   |
| Ralink                          | 1         | 0.32%   |
| Micro Star International        | 1         | 0.32%   |
| MediaTek                        | 1         | 0.32%   |
| Chicony Electronics             | 1         | 0.32%   |
| Alps Electric                   | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 65        | 21.04%  |
| Realtek Bluetooth Radio                                                             | 33        | 10.68%  |
| Intel AX201 Bluetooth                                                               | 23        | 7.44%   |
| Intel Bluetooth Device                                                              | 14        | 4.53%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 14        | 4.53%   |
| Intel AX200 Bluetooth                                                               | 14        | 4.53%   |
| Apple Bluetooth Host Controller                                                     | 8         | 2.59%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 7         | 2.27%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 1.94%   |
| Intel AX210 Bluetooth                                                               | 6         | 1.94%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.94%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1.62%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.62%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 1.62%   |
| Realtek Bluetooth Radio                                                             | 4         | 1.29%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 1.29%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 4         | 1.29%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 1.29%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 1.29%   |
| Realtek RTL8723B Bluetooth                                                          | 3         | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.97%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.97%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 0.97%   |
| IMC Networks Wireless_Device                                                        | 3         | 0.97%   |
| IMC Networks Bluetooth Device                                                       | 3         | 0.97%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 3         | 0.97%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 3         | 0.97%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.97%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 3         | 0.97%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 3         | 0.97%   |
| Lite-On Wireless_Device                                                             | 2         | 0.65%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 2         | 0.65%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.65%   |
| Broadcom BCM20702A0                                                                 | 2         | 0.65%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.65%   |
| USI Bluetooth Device                                                                | 1         | 0.32%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.32%   |
| Taiyo Yuden Bluetooth Device (V2.0+EDR)                                             | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel                   | 304       | 66.96%  |
| AMD                     | 78        | 17.18%  |
| Nvidia                  | 42        | 9.25%   |
| C-Media Electronics     | 4         | 0.88%   |
| Texas Instruments       | 3         | 0.66%   |
| Logitech                | 3         | 0.66%   |
| JMTek                   | 2         | 0.44%   |
| GN Netcom               | 2         | 0.44%   |
| Generalplus Technology  | 2         | 0.44%   |
| ASUSTek Computer        | 2         | 0.44%   |
| Textech International   | 1         | 0.22%   |
| Tenx Technology         | 1         | 0.22%   |
| Realtek Semiconductor   | 1         | 0.22%   |
| Microchip Technology    | 1         | 0.22%   |
| M-Audio                 | 1         | 0.22%   |
| Lenovo                  | 1         | 0.22%   |
| KTMicro                 | 1         | 0.22%   |
| HiBy                    | 1         | 0.22%   |
| Hewlett-Packard         | 1         | 0.22%   |
| GYROCOM C&C             | 1         | 0.22%   |
| Conexant Systems        | 1         | 0.22%   |
| BEHRINGER International | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 40        | 7.21%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 40        | 7.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 27        | 4.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 24        | 4.32%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 22        | 3.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 22        | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 20        | 3.6%    |
| AMD FCH Azalia Controller                                                                         | 20        | 3.6%    |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 16        | 2.88%   |
| Intel Broadwell-U Audio Controller                                                                | 16        | 2.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 2.88%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 14        | 2.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 14        | 2.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 12        | 2.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 11        | 1.98%   |
| Intel 8 Series HD Audio Controller                                                                | 11        | 1.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 1.8%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 10        | 1.8%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 1.8%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 1.62%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.62%   |
| Intel Comet Lake PCH cAVS                                                                         | 9         | 1.62%   |
| Nvidia Audio device                                                                               | 8         | 1.44%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 7         | 1.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.26%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 1.26%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 6         | 1.08%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.08%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.08%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.9%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.9%    |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 5         | 0.9%    |
| AMD High Definition Audio Controller                                                              | 5         | 0.9%    |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.72%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 4         | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.72%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 4         | 0.72%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 4         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Samsung Electronics        | 99        | 28.78%  |
| SK hynix                   | 72        | 20.93%  |
| Unknown                    | 39        | 11.34%  |
| Micron Technology          | 35        | 10.17%  |
| Kingston                   | 22        | 6.4%    |
| Crucial                    | 22        | 6.4%    |
| Unknown (ABCD)             | 11        | 3.2%    |
| Ramaxel Technology         | 8         | 2.33%   |
| Smart                      | 4         | 1.16%   |
| Nanya Technology           | 4         | 1.16%   |
| Corsair                    | 4         | 1.16%   |
| G.Skill                    | 3         | 0.87%   |
| fef5                       | 3         | 0.87%   |
| A-DATA Technology          | 3         | 0.87%   |
| Transcend                  | 2         | 0.58%   |
| Elpida                     | 2         | 0.58%   |
| Unknown                    | 2         | 0.58%   |
| V-Color                    | 1         | 0.29%   |
| Unknown (7F7F7F7F7F7F6B00) | 1         | 0.29%   |
| Unifosa                    | 1         | 0.29%   |
| Qimonda                    | 1         | 0.29%   |
| Foxline                    | 1         | 0.29%   |
| Essencore                  | 1         | 0.29%   |
| Daten Tecnologia           | 1         | 0.29%   |
| Avant                      | 1         | 0.29%   |
| 48spaces                   | 1         | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 11        | 3.01%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 6         | 1.64%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 6         | 1.64%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 5         | 1.37%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 5         | 1.37%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 5         | 1.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 5         | 1.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 5         | 1.37%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                           | 4         | 1.09%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                          | 4         | 1.09%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 4         | 1.09%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 4         | 1.09%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 4         | 1.09%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 4         | 1.09%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 4         | 1.09%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 4         | 1.09%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 4         | 1.09%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 3         | 0.82%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 3         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.82%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 3         | 0.82%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 0.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 0.82%   |
| Samsung RAM K4F8E304HB-MGCJ 1GB LPDDR4 2400MT/s                     | 3         | 0.82%   |
| Micron RAM Module 2GB SODIMM DDR3 1333MT/s                          | 3         | 0.82%   |
| fef5 RAM K4F8E304HB-MGCJ 1GB 2400MT/s                               | 3         | 0.82%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 2         | 0.55%   |
| Unknown RAM Module 4GB SODIMM DDR4 2667MT/s                         | 2         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                         | 2         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2 333MT/s                          | 2         | 0.55%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 2         | 0.55%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                        | 2         | 0.55%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 2         | 0.55%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                        | 2         | 0.55%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s             | 2         | 0.55%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s              | 2         | 0.55%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 2         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 115       | 38.98%  |
| DDR3    | 98        | 33.22%  |
| LPDDR4  | 27        | 9.15%   |
| DDR2    | 21        | 7.12%   |
| SDRAM   | 8         | 2.71%   |
| DDR5    | 8         | 2.71%   |
| LPDDR5  | 7         | 2.37%   |
| LPDDR3  | 5         | 1.69%   |
| Unknown | 5         | 1.69%   |
| DDR     | 1         | 0.34%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 257       | 86.82%  |
| Row Of Chips | 29        | 9.8%    |
| Unknown      | 6         | 2.03%   |
| Chip         | 4         | 1.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 104       | 32.5%   |
| 4096  | 85        | 26.56%  |
| 2048  | 59        | 18.44%  |
| 16384 | 44        | 13.75%  |
| 1024  | 16        | 5%      |
| 32768 | 10        | 3.13%   |
| 1536  | 1         | 0.31%   |
| 512   | 1         | 0.31%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 68        | 22.15%  |
| 1600    | 64        | 20.85%  |
| 2667    | 34        | 11.07%  |
| 2400    | 22        | 7.17%   |
| 2133    | 15        | 4.89%   |
| 1334    | 14        | 4.56%   |
| 667     | 12        | 3.91%   |
| 1333    | 11        | 3.58%   |
| 1067    | 8         | 2.61%   |
| 4800    | 7         | 2.28%   |
| 4267    | 7         | 2.28%   |
| 6400    | 5         | 1.63%   |
| 4199    | 5         | 1.63%   |
| Unknown | 5         | 1.63%   |
| 3266    | 4         | 1.3%    |
| 800     | 4         | 1.3%    |
| 2048    | 3         | 0.98%   |
| 4266    | 2         | 0.65%   |
| 1867    | 2         | 0.65%   |
| 1066    | 2         | 0.65%   |
| 975     | 2         | 0.65%   |
| 533     | 2         | 0.65%   |
| 333     | 2         | 0.65%   |
| 7467    | 1         | 0.33%   |
| 5600    | 1         | 0.33%   |
| 5500    | 1         | 0.33%   |
| 3733    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |
| 2134    | 1         | 0.33%   |
| 1776    | 1         | 0.33%   |

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
| Chicony Electronics                    | 92        | 25.84%  |
| IMC Networks                           | 31        | 8.71%   |
| Realtek Semiconductor                  | 27        | 7.58%   |
| Microdia                               | 25        | 7.02%   |
| Quanta                                 | 24        | 6.74%   |
| Sunplus Innovation Technology          | 22        | 6.18%   |
| Cheng Uei Precision Industry (Foxlink) | 19        | 5.34%   |
| Suyin                                  | 14        | 3.93%   |
| Bison Electronics                      | 14        | 3.93%   |
| Acer                                   | 9         | 2.53%   |
| Syntek                                 | 8         | 2.25%   |
| Lite-On Technology                     | 8         | 2.25%   |
| Apple                                  | 8         | 2.25%   |
| Luxvisions Innotech Limited            | 7         | 1.97%   |
| Logitech                               | 6         | 1.69%   |
| Sonix Technology                       | 5         | 1.4%    |
| Silicon Motion                         | 4         | 1.12%   |
| Z-Star Microelectronics                | 3         | 0.84%   |
| USB Camera                             | 3         | 0.84%   |
| Ricoh                                  | 3         | 0.84%   |
| Lenovo                                 | 3         | 0.84%   |
| Alcor Micro                            | 3         | 0.84%   |
| USB Camera CS                          | 2         | 0.56%   |
| SunplusIT                              | 2         | 0.56%   |
| Samsung Electronics                    | 2         | 0.56%   |
| 8SSC21D67422V1SR3AV5KW1                | 2         | 0.56%   |
| Xiongmai                               | 1         | 0.28%   |
| ValueHD                                | 1         | 0.28%   |
| Primax Electronics                     | 1         | 0.28%   |
| OYT Tech                               | 1         | 0.28%   |
| OmniVision Technologies                | 1         | 0.28%   |
| MacroSilicon                           | 1         | 0.28%   |
| Importek                               | 1         | 0.28%   |
| DigiTech                               | 1         | 0.28%   |
| Alpha Imaging Technology               | 1         | 0.28%   |
| Unknown                                | 1         | 0.28%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 30        | 8.4%    |
| Microdia Integrated_Webcam_HD                       | 11        | 3.08%   |
| Sunplus Integrated_Webcam_HD                        | 9         | 2.52%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 9         | 2.52%   |
| Quanta HD User Facing                               | 8         | 2.24%   |
| Chicony HD WebCam                                   | 8         | 2.24%   |
| Realtek Integrated_Webcam_HD                        | 7         | 1.96%   |
| IMC Networks Integrated Camera                      | 6         | 1.68%   |
| Syntek Integrated Camera                            | 5         | 1.4%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 5         | 1.4%    |
| Chicony TOSHIBA Web Camera - HD                     | 5         | 1.4%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 5         | 1.4%    |
| Apple Built-in iSight                               | 5         | 1.4%    |
| Realtek USB Camera                                  | 4         | 1.12%   |
| Realtek Lenovo EasyCamera                           | 4         | 1.12%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 4         | 1.12%   |
| Lite-On Integrated Camera                           | 4         | 1.12%   |
| Chicony HP Truevision HD camera                     | 4         | 1.12%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 4         | 1.12%   |
| Bison Integrated Camera                             | 4         | 1.12%   |
| USB Camera USB Camera                               | 3         | 0.84%   |
| Suyin HP TrueVision HD Integrated Webcam            | 3         | 0.84%   |
| Sunplus Integrated_Webcam_FHD                       | 3         | 0.84%   |
| Realtek Acer 640 x 480 laptop camera                | 3         | 0.84%   |
| Quanta HP Webcam                                    | 3         | 0.84%   |
| Quanta HP TrueVision HD Camera                      | 3         | 0.84%   |
| IMC Networks ov9734_azurewave_camera                | 3         | 0.84%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 0.84%   |
| Chicony USB2.0 Camera                               | 3         | 0.84%   |
| Chicony HP TrueVision HD                            | 3         | 0.84%   |
| Chicony EasyCamera                                  | 3         | 0.84%   |
| Bison Lenovo EasyCamera                             | 3         | 0.84%   |
| Acer SunplusIT Integrated Camera                    | 3         | 0.84%   |
| USB Camera CS USB Camera CS                         | 2         | 0.56%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 2         | 0.56%   |
| Sonix USB2.0 HD UVC WebCam                          | 2         | 0.56%   |
| Sonix USB2.0 FHD UVC WebCam                         | 2         | 0.56%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 0.56%   |
| Realtek Integrated_Webcam_FHD                       | 2         | 0.56%   |
| Realtek HP Truevision HD                            | 2         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 22        | 34.92%  |
| Shenzhen Goodix Technology         | 11        | 17.46%  |
| Synaptics                          | 9         | 14.29%  |
| Upek                               | 8         | 12.7%   |
| Elan Microelectronics              | 4         | 6.35%   |
| STMicroelectronics                 | 3         | 4.76%   |
| AuthenTec                          | 3         | 4.76%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 3.17%   |
| Focal-systems.Corp                 | 1         | 1.59%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                             | 10        | 15.87%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 7         | 11.11%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 7         | 11.11%  |
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 7.94%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 3         | 4.76%   |
| Validity Sensors Synaptics WBDI                                 | 3         | 4.76%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 3         | 4.76%   |
| STMicroelectronics Fingerprint Reader                           | 3         | 4.76%   |
| Elan ELAN:ARM-M4                                                | 3         | 4.76%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 3.17%   |
| Synaptics UWP WBDI Device                                       | 2         | 3.17%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 3.17%   |
| AuthenTec AES2501 Fingerprint Sensor                            | 2         | 3.17%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 1         | 1.59%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.59%   |
| Upek TCS5B Fingerprint sensor                                   | 1         | 1.59%   |
| Synaptics  WBDI                                                 | 1         | 1.59%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 1.59%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 1.59%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint        | 1         | 1.59%   |
| Shenzhen Goodix FingerPrint                                     | 1         | 1.59%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                       | 1         | 1.59%   |
| Elan ELAN:Fingerprint                                           | 1         | 1.59%   |
| AuthenTec AES2810                                               | 1         | 1.59%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 16        | 44.44%  |
| Alcor Micro | 13        | 36.11%  |
| Lenovo      | 4         | 11.11%  |
| O2 Micro    | 3         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 36.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 13.89%  |
| Broadcom 58200                                                               | 5         | 13.89%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 11.11%  |
| Broadcom 5880                                                                | 4         | 11.11%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 5.56%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 2.78%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 255       | 64.56%  |
| 1     | 109       | 27.59%  |
| 2     | 27        | 6.84%   |
| 3     | 4         | 1.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 60        | 35.29%  |
| Chipcard                 | 34        | 20%     |
| Graphics card            | 26        | 15.29%  |
| Camera                   | 16        | 9.41%   |
| Net/wireless             | 11        | 6.47%   |
| Bluetooth                | 7         | 4.12%   |
| Card reader              | 5         | 2.94%   |
| Storage                  | 3         | 1.76%   |
| Network                  | 3         | 1.76%   |
| Multimedia controller    | 2         | 1.18%   |
| Communication controller | 2         | 1.18%   |
| Net/ethernet             | 1         | 0.59%   |

