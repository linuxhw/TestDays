Linux in Vietnam - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Vietnam.

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

Total: 683

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Precision M4800             | [7c360180e7](https://linux-hardware.org/?probe=7c360180e7) | Jan 04, 2025 |
| HP            | Laptop 15s-du1xxx           | [5029ac1a06](https://linux-hardware.org/?probe=5029ac1a06) | Jan 01, 2025 |
| Dell          | Precision M4800             | [4e3bd9cbb4](https://linux-hardware.org/?probe=4e3bd9cbb4) | Jan 01, 2025 |
| Dell          | Precision 7540              | [314c747e45](https://linux-hardware.org/?probe=314c747e45) | Dec 28, 2024 |
| Dell          | Precision 7540              | [4535a9d79b](https://linux-hardware.org/?probe=4535a9d79b) | Dec 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [0971785105](https://linux-hardware.org/?probe=0971785105) | Dec 26, 2024 |
| Dell          | Latitude E5550              | [2512980572](https://linux-hardware.org/?probe=2512980572) | Dec 25, 2024 |
| Apple         | MacBookAir7,2               | [c02f6f4421](https://linux-hardware.org/?probe=c02f6f4421) | Dec 23, 2024 |
| Lenovo        | ThinkPad T430 2349A17       | [467d5bf559](https://linux-hardware.org/?probe=467d5bf559) | Dec 22, 2024 |
| Dell          | Latitude 7390               | [d446a06dc6](https://linux-hardware.org/?probe=d446a06dc6) | Dec 18, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21ML0... | [063c4b21a8](https://linux-hardware.org/?probe=063c4b21a8) | Dec 16, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [5d556ab3f4](https://linux-hardware.org/?probe=5d556ab3f4) | Dec 16, 2024 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [eb47c05bbb](https://linux-hardware.org/?probe=eb47c05bbb) | Dec 15, 2024 |
| Dell          | Latitude 7390               | [7c762c0713](https://linux-hardware.org/?probe=7c762c0713) | Dec 13, 2024 |
| HP            | EliteBook 2560p             | [8638d65417](https://linux-hardware.org/?probe=8638d65417) | Dec 12, 2024 |
| HP            | ProBook 450 G3              | [e39b84b016](https://linux-hardware.org/?probe=e39b84b016) | Dec 11, 2024 |
| Lenovo        | ThinkPad T430 2349A17       | [704c8bef39](https://linux-hardware.org/?probe=704c8bef39) | Dec 05, 2024 |
| Dell          | Inspiron 3443               | [73ce4e96f5](https://linux-hardware.org/?probe=73ce4e96f5) | Dec 01, 2024 |
| Dell          | Inspiron 3442               | [8354433195](https://linux-hardware.org/?probe=8354433195) | Dec 01, 2024 |
| HP            | ProBook 450 G3              | [f3ade75c2d](https://linux-hardware.org/?probe=f3ade75c2d) | Nov 30, 2024 |
| Lenovo        | ThinkPad P53 20QN002LUS     | [c4bb47dc8d](https://linux-hardware.org/?probe=c4bb47dc8d) | Nov 30, 2024 |
| Lenovo        | IdeaPad Slim 5 14AHP9 83... | [f2e869dbea](https://linux-hardware.org/?probe=f2e869dbea) | Nov 27, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21ML0... | [59205e96b5](https://linux-hardware.org/?probe=59205e96b5) | Nov 25, 2024 |
| Lenovo        | ThinkPad P50 20EQA0HFJP     | [c9a5d2852f](https://linux-hardware.org/?probe=c9a5d2852f) | Nov 25, 2024 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [75382d8ea9](https://linux-hardware.org/?probe=75382d8ea9) | Nov 22, 2024 |
| Dell          | Vostro 3500                 | [48169a4553](https://linux-hardware.org/?probe=48169a4553) | Nov 17, 2024 |
| HP            | EliteBook 840 14 inch G1... | [333961be54](https://linux-hardware.org/?probe=333961be54) | Nov 14, 2024 |
| HUAWEI        | KLVL-WXXW                   | [42c31d1a6b](https://linux-hardware.org/?probe=42c31d1a6b) | Nov 13, 2024 |
| HUAWEI        | KLVL-WXXW                   | [57bdc97b57](https://linux-hardware.org/?probe=57bdc97b57) | Nov 12, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [780ff233ce](https://linux-hardware.org/?probe=780ff233ce) | Nov 09, 2024 |
| Lenovo        | ThinkPad X230 23243MU       | [b9aa89f4af](https://linux-hardware.org/?probe=b9aa89f4af) | Nov 09, 2024 |
| Dell          | Vostro 3560                 | [b832b01843](https://linux-hardware.org/?probe=b832b01843) | Nov 07, 2024 |
| HUAWEI        | BOD-WXX9                    | [5d7f9f6298](https://linux-hardware.org/?probe=5d7f9f6298) | Nov 06, 2024 |
| HP            | ProBook 450 G3              | [43e8b9cd73](https://linux-hardware.org/?probe=43e8b9cd73) | Oct 30, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [1d73e46912](https://linux-hardware.org/?probe=1d73e46912) | Oct 27, 2024 |
| Lenovo        | ThinkPad P50 20EQA0HFJP     | [de0dff32ba](https://linux-hardware.org/?probe=de0dff32ba) | Oct 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [0d286dd3ac](https://linux-hardware.org/?probe=0d286dd3ac) | Oct 22, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [758143fbc9](https://linux-hardware.org/?probe=758143fbc9) | Oct 21, 2024 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [998331b0b5](https://linux-hardware.org/?probe=998331b0b5) | Oct 16, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | [de44b9af7c](https://linux-hardware.org/?probe=de44b9af7c) | Oct 15, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [bb0bf00fc4](https://linux-hardware.org/?probe=bb0bf00fc4) | Oct 12, 2024 |
| Dell          | Vostro 3578                 | [d523995b93](https://linux-hardware.org/?probe=d523995b93) | Oct 12, 2024 |
| Dell          | Latitude E5450              | [c7bea876cf](https://linux-hardware.org/?probe=c7bea876cf) | Oct 12, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [0df50eaff2](https://linux-hardware.org/?probe=0df50eaff2) | Oct 12, 2024 |
| Dell          | Precision 5530              | [19bfbd7cdb](https://linux-hardware.org/?probe=19bfbd7cdb) | Oct 09, 2024 |
| Apple         | MacBookPro12,1              | [78f8401511](https://linux-hardware.org/?probe=78f8401511) | Oct 07, 2024 |
| Apple         | MacBookPro12,1              | [b54ffcadc5](https://linux-hardware.org/?probe=b54ffcadc5) | Oct 06, 2024 |
| HP            | ProBook 440 G7              | [0b63cd25e3](https://linux-hardware.org/?probe=0b63cd25e3) | Sep 27, 2024 |
| Acer          | Aspire A715-41G             | [28630e6b4e](https://linux-hardware.org/?probe=28630e6b4e) | Sep 26, 2024 |
| Lenovo        | ThinkPad T460s 20F9003CU... | [839431acb4](https://linux-hardware.org/?probe=839431acb4) | Sep 23, 2024 |
| HP            | ProBook 450 G3              | [ceef2c6eb0](https://linux-hardware.org/?probe=ceef2c6eb0) | Sep 21, 2024 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [7a41c29a03](https://linux-hardware.org/?probe=7a41c29a03) | Sep 21, 2024 |
| HP            | ZBook Power 16 inch G11 ... | [07a4fb8d0d](https://linux-hardware.org/?probe=07a4fb8d0d) | Sep 20, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [c4777b62e2](https://linux-hardware.org/?probe=c4777b62e2) | Sep 19, 2024 |
| Dell          | Latitude 7390               | [90063dd1b7](https://linux-hardware.org/?probe=90063dd1b7) | Sep 18, 2024 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [4b8c75fca8](https://linux-hardware.org/?probe=4b8c75fca8) | Sep 17, 2024 |
| Dell          | Latitude 7390               | [738fbe7846](https://linux-hardware.org/?probe=738fbe7846) | Sep 11, 2024 |
| Dell          | G5 5500                     | [047302a678](https://linux-hardware.org/?probe=047302a678) | Sep 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [2a1feab9bf](https://linux-hardware.org/?probe=2a1feab9bf) | Sep 08, 2024 |
| Dell          | Latitude E6420              | [31212512fd](https://linux-hardware.org/?probe=31212512fd) | Sep 01, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [acc91bcc92](https://linux-hardware.org/?probe=acc91bcc92) | Aug 30, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [c3e7f8694f](https://linux-hardware.org/?probe=c3e7f8694f) | Aug 28, 2024 |
| Dell          | Inspiron 16 Plus 7630       | [ba17ccfdcf](https://linux-hardware.org/?probe=ba17ccfdcf) | Aug 27, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f8c21d6744](https://linux-hardware.org/?probe=f8c21d6744) | Aug 26, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [1bc687932f](https://linux-hardware.org/?probe=1bc687932f) | Aug 23, 2024 |
| Lenovo        | Legion 5 Pro 16IAH7 82S0    | [d8dd107aff](https://linux-hardware.org/?probe=d8dd107aff) | Aug 22, 2024 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [ada714905a](https://linux-hardware.org/?probe=ada714905a) | Aug 19, 2024 |
| HP            | ProBook 450 G3              | [8728a5c10a](https://linux-hardware.org/?probe=8728a5c10a) | Aug 17, 2024 |
| Dell          | Vostro 3500                 | [647b4d4e05](https://linux-hardware.org/?probe=647b4d4e05) | Aug 14, 2024 |
| Acer          | Aspire A715-72G             | [ee80d11d07](https://linux-hardware.org/?probe=ee80d11d07) | Aug 12, 2024 |
| Dell          | Latitude 7480               | [29eb3942e4](https://linux-hardware.org/?probe=29eb3942e4) | Aug 11, 2024 |
| Acer          | Nitro AN515-57              | [c118336b8d](https://linux-hardware.org/?probe=c118336b8d) | Aug 08, 2024 |
| ASUSTek       | X455LA                      | [37e0171c30](https://linux-hardware.org/?probe=37e0171c30) | Aug 07, 2024 |
| Apple         | MacBookPro12,1              | [ae01578889](https://linux-hardware.org/?probe=ae01578889) | Aug 06, 2024 |
| Chuwi         | CoreBook X                  | [bcdc21a44e](https://linux-hardware.org/?probe=bcdc21a44e) | Aug 05, 2024 |
| HP            | Stream Laptop 11-ah0XX      | [d996c69b4e](https://linux-hardware.org/?probe=d996c69b4e) | Jul 30, 2024 |
| Dell          | Vostro 3578                 | [c7238c32a7](https://linux-hardware.org/?probe=c7238c32a7) | Jul 29, 2024 |
| Acer          | Nitro AN16-41               | [c59c94dc80](https://linux-hardware.org/?probe=c59c94dc80) | Jul 28, 2024 |
| Dell          | Vostro 5468                 | [6f51e95a13](https://linux-hardware.org/?probe=6f51e95a13) | Jul 26, 2024 |
| HP            | ProBook 440 G7              | [aafd504745](https://linux-hardware.org/?probe=aafd504745) | Jul 24, 2024 |
| Acer          | Nitro AN16-41               | [9d6e1306ec](https://linux-hardware.org/?probe=9d6e1306ec) | Jul 23, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d7fcdc7953](https://linux-hardware.org/?probe=d7fcdc7953) | Jul 16, 2024 |
| Dell          | Vostro 15-3568              | [1542766bdd](https://linux-hardware.org/?probe=1542766bdd) | Jul 15, 2024 |
| Dell          | Latitude 7390               | [ddb7685bf1](https://linux-hardware.org/?probe=ddb7685bf1) | Jul 12, 2024 |
| OrangePi      | NEO-01                      | [bf07a0e349](https://linux-hardware.org/?probe=bf07a0e349) | Jul 12, 2024 |
| HP            | ProBook 450 G3              | [8cabf59fdb](https://linux-hardware.org/?probe=8cabf59fdb) | Jul 12, 2024 |
| HP            | ProBook 450 G3              | [1c31a4cfc4](https://linux-hardware.org/?probe=1c31a4cfc4) | Jul 11, 2024 |
| HP            | Laptop 14s-fq1xxx           | [a7dd8bc9c0](https://linux-hardware.org/?probe=a7dd8bc9c0) | Jul 10, 2024 |
| HP            | EliteBook 645 14 inch G9... | [1102b424c6](https://linux-hardware.org/?probe=1102b424c6) | Jul 08, 2024 |
| HP            | EliteBook 645 14 inch G9... | [395d619b53](https://linux-hardware.org/?probe=395d619b53) | Jul 08, 2024 |
| HP            | ProBook 450 G3              | [4dcce43f80](https://linux-hardware.org/?probe=4dcce43f80) | Jul 02, 2024 |
| MSI           | Creator M16 A12UC           | [4b9de6f7b6](https://linux-hardware.org/?probe=4b9de6f7b6) | Jun 30, 2024 |
| HUAWEI        | BOM-WXX9                    | [f9cbea829f](https://linux-hardware.org/?probe=f9cbea829f) | Jun 24, 2024 |
| OrangePi      | NEO-01                      | [da69fb6377](https://linux-hardware.org/?probe=da69fb6377) | Jun 23, 2024 |
| HUAWEI        | BOM-WXX9                    | [49737ebb77](https://linux-hardware.org/?probe=49737ebb77) | Jun 22, 2024 |
| HP            | Pavilion dv7                | [d2bf7bbc79](https://linux-hardware.org/?probe=d2bf7bbc79) | Jun 21, 2024 |
| OrangePi      | NEO-01                      | [4341aee209](https://linux-hardware.org/?probe=4341aee209) | Jun 19, 2024 |
| Lenovo        | ThinkPad P50 20EQA0HFJP     | [25a9a5fbab](https://linux-hardware.org/?probe=25a9a5fbab) | Jun 11, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [9a70731554](https://linux-hardware.org/?probe=9a70731554) | Jun 10, 2024 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [c948245a1e](https://linux-hardware.org/?probe=c948245a1e) | Jun 08, 2024 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [56f86f1288](https://linux-hardware.org/?probe=56f86f1288) | Jun 08, 2024 |
| Sony          | SVE14132CVB                 | [1d1b0f6b07](https://linux-hardware.org/?probe=1d1b0f6b07) | Jun 07, 2024 |
| MSI           | Modern 15 A5M               | [a2da3535f1](https://linux-hardware.org/?probe=a2da3535f1) | Jun 06, 2024 |
| HP            | ProBook 450 G3              | [2c5b454002](https://linux-hardware.org/?probe=2c5b454002) | Jun 04, 2024 |
| Acer          | Nitro AN515-45              | [b57a2d7747](https://linux-hardware.org/?probe=b57a2d7747) | Jun 04, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [b08f59e8eb](https://linux-hardware.org/?probe=b08f59e8eb) | Jun 02, 2024 |
| Alienware     | M17xR4                      | [a5147b08e6](https://linux-hardware.org/?probe=a5147b08e6) | May 26, 2024 |
| HP            | EliteBook 1030 G1           | [2dc4e838a9](https://linux-hardware.org/?probe=2dc4e838a9) | May 25, 2024 |
| Acer          | Aspire A315-59              | [73f9290f9b](https://linux-hardware.org/?probe=73f9290f9b) | May 22, 2024 |
| MSI           | Katana GF76 12UE            | [c9597611ab](https://linux-hardware.org/?probe=c9597611ab) | May 19, 2024 |
| Apple         | MacBookAir6,2               | [829e0a0d70](https://linux-hardware.org/?probe=829e0a0d70) | May 16, 2024 |
| MSI           | Katana GF76 12UE            | [4ddec0f62b](https://linux-hardware.org/?probe=4ddec0f62b) | May 15, 2024 |
| Lenovo        | ThinkPad T470 20HD000VUS    | [1453bbda09](https://linux-hardware.org/?probe=1453bbda09) | May 15, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [15d30912cf](https://linux-hardware.org/?probe=15d30912cf) | May 13, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a5031a990b](https://linux-hardware.org/?probe=a5031a990b) | May 10, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1400CBA... | [3a81cd6b2e](https://linux-hardware.org/?probe=3a81cd6b2e) | May 09, 2024 |
| MASSCOM VI... | L133                        | [12b6c6b515](https://linux-hardware.org/?probe=12b6c6b515) | May 06, 2024 |
| Acer          | Aspire A715-41G             | [b24efb4449](https://linux-hardware.org/?probe=b24efb4449) | May 06, 2024 |
| Acer          | Aspire A715-41G             | [aa9c440102](https://linux-hardware.org/?probe=aa9c440102) | May 01, 2024 |
| Dell          | G7 7588                     | [9745a22fe0](https://linux-hardware.org/?probe=9745a22fe0) | Apr 28, 2024 |
| Dell          | Latitude E5450              | [575668e003](https://linux-hardware.org/?probe=575668e003) | Apr 26, 2024 |
| MSI           | Modern 15 A5M               | [3e1d481314](https://linux-hardware.org/?probe=3e1d481314) | Apr 26, 2024 |
| Apple         | MacBookPro11,3              | [81b0d669d9](https://linux-hardware.org/?probe=81b0d669d9) | Apr 26, 2024 |
| HP            | Compaq 6520s                | [235863713b](https://linux-hardware.org/?probe=235863713b) | Apr 25, 2024 |
| HP            | EliteBook 845 14 inch G1... | [cf3db9398d](https://linux-hardware.org/?probe=cf3db9398d) | Apr 22, 2024 |
| HP            | EliteBook 845 14 inch G1... | [6eeb53e317](https://linux-hardware.org/?probe=6eeb53e317) | Apr 22, 2024 |
| Apple         | MacBookAir7,2               | [50f7cbb79a](https://linux-hardware.org/?probe=50f7cbb79a) | Apr 19, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [a2fb569143](https://linux-hardware.org/?probe=a2fb569143) | Apr 19, 2024 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [b70a3e9c9f](https://linux-hardware.org/?probe=b70a3e9c9f) | Apr 19, 2024 |
| HP            | 240 G8 Notebook PC          | [13af7544f2](https://linux-hardware.org/?probe=13af7544f2) | Apr 17, 2024 |
| Dell          | G7 7588                     | [06f5f64e59](https://linux-hardware.org/?probe=06f5f64e59) | Apr 14, 2024 |
| Dell          | Latitude E5570              | [91db6ada79](https://linux-hardware.org/?probe=91db6ada79) | Apr 13, 2024 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [c595905fcb](https://linux-hardware.org/?probe=c595905fcb) | Apr 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [05372f86e5](https://linux-hardware.org/?probe=05372f86e5) | Apr 10, 2024 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [8b430e632f](https://linux-hardware.org/?probe=8b430e632f) | Apr 09, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [bf43ad7ffe](https://linux-hardware.org/?probe=bf43ad7ffe) | Apr 08, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [25dc9ad19d](https://linux-hardware.org/?probe=25dc9ad19d) | Apr 08, 2024 |
| Dell          | G7 7588                     | [8753ea1302](https://linux-hardware.org/?probe=8753ea1302) | Apr 05, 2024 |
| Lenovo        | Legion Pro 5 16IRX9 83DF    | [5457b4ef4c](https://linux-hardware.org/?probe=5457b4ef4c) | Mar 27, 2024 |
| Lenovo        | ThinkPad T480 20L6S0HG00    | [f80e544ce6](https://linux-hardware.org/?probe=f80e544ce6) | Mar 22, 2024 |
| Lenovo        | XiaoXinPro 14 AHP9 83D3     | [468b8047e4](https://linux-hardware.org/?probe=468b8047e4) | Mar 15, 2024 |
| Apple         | MacBookAir6,2               | [7cddb85911](https://linux-hardware.org/?probe=7cddb85911) | Mar 14, 2024 |
| Gigabyte      | G5 GD                       | [58ac2082b9](https://linux-hardware.org/?probe=58ac2082b9) | Mar 11, 2024 |
| HP            | Pavilion Laptop 15-cs0xx... | [22f1633f40](https://linux-hardware.org/?probe=22f1633f40) | Mar 09, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | [b68f17fbdf](https://linux-hardware.org/?probe=b68f17fbdf) | Mar 02, 2024 |
| MSI           | Modern 14 B11SBU            | [5a5e7d82d7](https://linux-hardware.org/?probe=5a5e7d82d7) | Feb 29, 2024 |
| MSI           | Modern 14 B5M               | [565e6c2d46](https://linux-hardware.org/?probe=565e6c2d46) | Feb 29, 2024 |
| Apple         | MacBookPro13,3              | [f6a0a37d75](https://linux-hardware.org/?probe=f6a0a37d75) | Feb 20, 2024 |
| Gigabyte      | G5 KD                       | [0743c222ba](https://linux-hardware.org/?probe=0743c222ba) | Feb 20, 2024 |
| Apple         | MacBookPro11,3              | [ae67d4e82a](https://linux-hardware.org/?probe=ae67d4e82a) | Feb 19, 2024 |
| HP            | ProBook 450 G1              | [ba02f5d2ae](https://linux-hardware.org/?probe=ba02f5d2ae) | Feb 18, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [111c375a02](https://linux-hardware.org/?probe=111c375a02) | Feb 17, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [2fc996bace](https://linux-hardware.org/?probe=2fc996bace) | Feb 17, 2024 |
| Acer          | Nitro AN515-55              | [5b9d9efd21](https://linux-hardware.org/?probe=5b9d9efd21) | Feb 17, 2024 |
| Dell          | Inspiron 3576               | [740a10ea1f](https://linux-hardware.org/?probe=740a10ea1f) | Feb 15, 2024 |
| OrangePi      | NEO-01                      | [9999d229d6](https://linux-hardware.org/?probe=9999d229d6) | Feb 09, 2024 |
| MSI           | GF63 Thin 11UC              | [8dbe3ddfaa](https://linux-hardware.org/?probe=8dbe3ddfaa) | Feb 08, 2024 |
| MSI           | GF63 Thin 10SC              | [0e9a586cf0](https://linux-hardware.org/?probe=0e9a586cf0) | Feb 06, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | [5cbf6ef1b5](https://linux-hardware.org/?probe=5cbf6ef1b5) | Feb 06, 2024 |
| Lenovo        | XiaoXinPro-13ARE 2020 82... | [33ad82eafa](https://linux-hardware.org/?probe=33ad82eafa) | Feb 05, 2024 |
| MSI           | Modern 15 A5M               | [e591b9e544](https://linux-hardware.org/?probe=e591b9e544) | Feb 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6acefbaadc](https://linux-hardware.org/?probe=6acefbaadc) | Feb 01, 2024 |
| MSI           | Creator M16 A12UC           | [804a70b7f5](https://linux-hardware.org/?probe=804a70b7f5) | Jan 31, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | [ed474939eb](https://linux-hardware.org/?probe=ed474939eb) | Jan 31, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | [021f108e72](https://linux-hardware.org/?probe=021f108e72) | Jan 31, 2024 |
| Google        | Elemi                       | [f767c4fdbb](https://linux-hardware.org/?probe=f767c4fdbb) | Jan 28, 2024 |
| COM1          | NBINF-O5-4R7R6              | [95df5c3aa3](https://linux-hardware.org/?probe=95df5c3aa3) | Jan 21, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [1284a92c36](https://linux-hardware.org/?probe=1284a92c36) | Jan 16, 2024 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [052a070a11](https://linux-hardware.org/?probe=052a070a11) | Jan 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1291da44c0](https://linux-hardware.org/?probe=1291da44c0) | Jan 14, 2024 |
| Lenovo        | ThinkBook 14 G5+ ARP 21H... | [78a77e24d1](https://linux-hardware.org/?probe=78a77e24d1) | Jan 14, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [a7a7b48aa9](https://linux-hardware.org/?probe=a7a7b48aa9) | Jan 13, 2024 |
| HP            | 245 14 inch G9 Notebook ... | [f23bf42f04](https://linux-hardware.org/?probe=f23bf42f04) | Jan 08, 2024 |
| Google        | Jinlon                      | [1d3ce76cf8](https://linux-hardware.org/?probe=1d3ce76cf8) | Jan 08, 2024 |
| Acer          | Nitro AN515-57              | [cd2d137285](https://linux-hardware.org/?probe=cd2d137285) | Jan 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [3274a6e444](https://linux-hardware.org/?probe=3274a6e444) | Jan 05, 2024 |
| Apple         | MacBookAir7,2               | [04de30dc4d](https://linux-hardware.org/?probe=04de30dc4d) | Jan 03, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | [389ae3afc8](https://linux-hardware.org/?probe=389ae3afc8) | Jan 02, 2024 |
| Dell          | Inspiron 15 7000 Gaming     | [9eff3f535e](https://linux-hardware.org/?probe=9eff3f535e) | Dec 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a4efec2a2c](https://linux-hardware.org/?probe=a4efec2a2c) | Dec 19, 2023 |
| ASUSTek       | K45VD                       | [527a669776](https://linux-hardware.org/?probe=527a669776) | Dec 12, 2023 |
| Acer          | Nitro AN515-58              | [34df3b2497](https://linux-hardware.org/?probe=34df3b2497) | Dec 02, 2023 |
| Dell          | Inspiron 1440               | [08b87da5fd](https://linux-hardware.org/?probe=08b87da5fd) | Nov 30, 2023 |
| Dell          | Inspiron 1440               | [7c28444086](https://linux-hardware.org/?probe=7c28444086) | Nov 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [30bce064eb](https://linux-hardware.org/?probe=30bce064eb) | Nov 27, 2023 |
| ASUSTek       | GL552VX                     | [42271c5724](https://linux-hardware.org/?probe=42271c5724) | Nov 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | [95b888d2b1](https://linux-hardware.org/?probe=95b888d2b1) | Nov 24, 2023 |
| HP            | ProBook 440 G7              | [dbbf51e4c5](https://linux-hardware.org/?probe=dbbf51e4c5) | Nov 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [95a4f9ff42](https://linux-hardware.org/?probe=95a4f9ff42) | Nov 14, 2023 |
| HP            | EliteBook 845 14 inch G1... | [dfbaeb29c5](https://linux-hardware.org/?probe=dfbaeb29c5) | Nov 11, 2023 |
| Google        | Phaser360                   | [dbd0db9b7e](https://linux-hardware.org/?probe=dbd0db9b7e) | Nov 05, 2023 |
| HUAWEI        | RLEF-XX                     | [21b415bccc](https://linux-hardware.org/?probe=21b415bccc) | Nov 05, 2023 |
| HUAWEI        | RLEF-XX                     | [e87403e608](https://linux-hardware.org/?probe=e87403e608) | Nov 02, 2023 |
| Acer          | Aspire A715-41G             | [664191098d](https://linux-hardware.org/?probe=664191098d) | Nov 02, 2023 |
| Acer          | Aspire A715-41G             | [63fa5e90b2](https://linux-hardware.org/?probe=63fa5e90b2) | Nov 01, 2023 |
| Dell          | Latitude E5450              | [64e3601d4c](https://linux-hardware.org/?probe=64e3601d4c) | Oct 29, 2023 |
| Dell          | Latitude E5450              | [aebf2cd9fb](https://linux-hardware.org/?probe=aebf2cd9fb) | Oct 29, 2023 |
| Lenovo        | ThinkPad T15g Gen 2i 20Y... | [dcd6988b7a](https://linux-hardware.org/?probe=dcd6988b7a) | Oct 28, 2023 |
| Acer          | Aspire E5-571               | [681e404df8](https://linux-hardware.org/?probe=681e404df8) | Oct 28, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | [8764daeeab](https://linux-hardware.org/?probe=8764daeeab) | Oct 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [4f06b99b2e](https://linux-hardware.org/?probe=4f06b99b2e) | Oct 23, 2023 |
| Dell          | Latitude E6440              | [9db156fcaf](https://linux-hardware.org/?probe=9db156fcaf) | Oct 22, 2023 |
| HP            | Compaq 6520s                | [d010b05039](https://linux-hardware.org/?probe=d010b05039) | Oct 22, 2023 |
| HP            | 15                          | [c85c40dbc8](https://linux-hardware.org/?probe=c85c40dbc8) | Oct 21, 2023 |
| HP            | 15                          | [95e8953601](https://linux-hardware.org/?probe=95e8953601) | Oct 21, 2023 |
| MSI           | Crosshair 15 B12UEZ         | [746189a3d8](https://linux-hardware.org/?probe=746189a3d8) | Oct 20, 2023 |
| Dell          | Latitude 7330               | [8632b84be8](https://linux-hardware.org/?probe=8632b84be8) | Oct 14, 2023 |
| HP            | Notebook                    | [fb39ee7d9d](https://linux-hardware.org/?probe=fb39ee7d9d) | Oct 13, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [47ba0bddd0](https://linux-hardware.org/?probe=47ba0bddd0) | Oct 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [29c7192a14](https://linux-hardware.org/?probe=29c7192a14) | Oct 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | [a08bbfa9e1](https://linux-hardware.org/?probe=a08bbfa9e1) | Oct 07, 2023 |
| Apple         | MacBookPro13,3              | [171a2ad768](https://linux-hardware.org/?probe=171a2ad768) | Oct 04, 2023 |
| MSI           | Modern 14 B5M               | [65ae20098f](https://linux-hardware.org/?probe=65ae20098f) | Oct 03, 2023 |
| Samsung       | 940XGK                      | [63aededb0c](https://linux-hardware.org/?probe=63aededb0c) | Oct 03, 2023 |
| Samsung       | 940XGK                      | [805cef3023](https://linux-hardware.org/?probe=805cef3023) | Oct 03, 2023 |
| Dell          | Inspiron 5583               | [c16bd909f3](https://linux-hardware.org/?probe=c16bd909f3) | Oct 02, 2023 |
| Sony          | SVF1421PSGB                 | [11d6cad851](https://linux-hardware.org/?probe=11d6cad851) | Oct 02, 2023 |
| Sony          | SVF1421PSGB                 | [84a0c8ea9b](https://linux-hardware.org/?probe=84a0c8ea9b) | Oct 01, 2023 |
| Dell          | Latitude E5450              | [76401b3ca2](https://linux-hardware.org/?probe=76401b3ca2) | Oct 01, 2023 |
| ASUSTek       | X541UAK                     | [b063bf9f1e](https://linux-hardware.org/?probe=b063bf9f1e) | Sep 24, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [2d1e14cb66](https://linux-hardware.org/?probe=2d1e14cb66) | Sep 23, 2023 |
| Dell          | Precision 7520              | [99e70bdd81](https://linux-hardware.org/?probe=99e70bdd81) | Sep 19, 2023 |
| Dell          | Precision 7520              | [89f1a6a0a5](https://linux-hardware.org/?probe=89f1a6a0a5) | Sep 18, 2023 |
| Dell          | Precision M6800             | [4bf05e9eae](https://linux-hardware.org/?probe=4bf05e9eae) | Sep 17, 2023 |
| ASUSTek       | ASUSPRO P5440FA_P5440FA     | [b7c1a0a0a0](https://linux-hardware.org/?probe=b7c1a0a0a0) | Sep 16, 2023 |
| ASUSTek       | UX305FA                     | [e4ade39a1c](https://linux-hardware.org/?probe=e4ade39a1c) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [d1d5edf95c](https://linux-hardware.org/?probe=d1d5edf95c) | Sep 12, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [75ca1d0c52](https://linux-hardware.org/?probe=75ca1d0c52) | Sep 10, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [5b22cd283b](https://linux-hardware.org/?probe=5b22cd283b) | Sep 08, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [155023d91f](https://linux-hardware.org/?probe=155023d91f) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [b652970974](https://linux-hardware.org/?probe=b652970974) | Sep 01, 2023 |
| Dell          | Vostro 1450                 | [1aad0f5aa3](https://linux-hardware.org/?probe=1aad0f5aa3) | Aug 26, 2023 |
| Dell          | Latitude 7480               | [50bcada7d4](https://linux-hardware.org/?probe=50bcada7d4) | Aug 23, 2023 |
| HP            | Laptop 15-dy1xxx            | [e00521ec88](https://linux-hardware.org/?probe=e00521ec88) | Aug 22, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [882234a7b8](https://linux-hardware.org/?probe=882234a7b8) | Aug 22, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [d6df464cc7](https://linux-hardware.org/?probe=d6df464cc7) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | [471f5f6132](https://linux-hardware.org/?probe=471f5f6132) | Aug 20, 2023 |
| HP            | 2000                        | [650a9a885c](https://linux-hardware.org/?probe=650a9a885c) | Aug 19, 2023 |
| Valve         | Jupiter                     | [f52ceb7ab6](https://linux-hardware.org/?probe=f52ceb7ab6) | Aug 15, 2023 |
| Acer          | Nitro AN515-57              | [ad8a62ee1d](https://linux-hardware.org/?probe=ad8a62ee1d) | Aug 14, 2023 |
| Acer          | Aspire V5-471G              | [1955354749](https://linux-hardware.org/?probe=1955354749) | Aug 11, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [d97ae334a3](https://linux-hardware.org/?probe=d97ae334a3) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [b065632006](https://linux-hardware.org/?probe=b065632006) | Aug 08, 2023 |
| Timi          | RedmiBook Pro 15S           | [576241bbd4](https://linux-hardware.org/?probe=576241bbd4) | Aug 06, 2023 |
| HP            | Laptop 15-dy1xxx            | [6dbeaa5f27](https://linux-hardware.org/?probe=6dbeaa5f27) | Aug 04, 2023 |
| Dell          | System XPS L322X            | [dbe168d1a1](https://linux-hardware.org/?probe=dbe168d1a1) | Aug 02, 2023 |
| Alienware     | 13 R3                       | [845dfcc74f](https://linux-hardware.org/?probe=845dfcc74f) | Jul 27, 2023 |
| Valve         | Jupiter                     | [ece0a7a538](https://linux-hardware.org/?probe=ece0a7a538) | Jul 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d3e22fde36](https://linux-hardware.org/?probe=d3e22fde36) | Jul 25, 2023 |
| Lenovo        | ThinkPad T420 4180EP2       | [298fe52a60](https://linux-hardware.org/?probe=298fe52a60) | Jul 25, 2023 |
| Apple         | MacBookPro13,3              | [ae23c3b0d3](https://linux-hardware.org/?probe=ae23c3b0d3) | Jul 24, 2023 |
| Lenovo        | ThinkPad T420 4180EP2       | [4ec1a5c6fe](https://linux-hardware.org/?probe=4ec1a5c6fe) | Jul 22, 2023 |
| HP            | 245 G8 Notebook PC          | [788fc0bfc9](https://linux-hardware.org/?probe=788fc0bfc9) | Jul 21, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [fe9e1671cc](https://linux-hardware.org/?probe=fe9e1671cc) | Jul 20, 2023 |
| Dell          | Latitude 5580               | [6efcf73621](https://linux-hardware.org/?probe=6efcf73621) | Jul 19, 2023 |
| Dell          | Latitude 5580               | [16f62b67d3](https://linux-hardware.org/?probe=16f62b67d3) | Jul 17, 2023 |
| itel Mobil... | SPIRIT 1                    | [36c3d3f6a8](https://linux-hardware.org/?probe=36c3d3f6a8) | Jul 16, 2023 |
| ASUSTek       | K53SV                       | [851a3a00cf](https://linux-hardware.org/?probe=851a3a00cf) | Jul 05, 2023 |
| Dell          | Latitude 6430U              | [0ffe35561e](https://linux-hardware.org/?probe=0ffe35561e) | Jul 04, 2023 |
| Dell          | Latitude 6430U              | [2cd1962ee4](https://linux-hardware.org/?probe=2cd1962ee4) | Jul 03, 2023 |
| Apple         | MacBookPro12,1              | [6cc649e9ba](https://linux-hardware.org/?probe=6cc649e9ba) | Jun 29, 2023 |
| Lenovo        | ThinkPad T15g Gen1 20URC... | [e4c7449911](https://linux-hardware.org/?probe=e4c7449911) | Jun 27, 2023 |
| Acer          | Aspire A715-41G             | [66cc56555d](https://linux-hardware.org/?probe=66cc56555d) | Jun 15, 2023 |
| Acer          | Aspire A715-41G             | [7082d05ede](https://linux-hardware.org/?probe=7082d05ede) | Jun 12, 2023 |
| HP            | EliteBook 2560p             | [1b491bcfeb](https://linux-hardware.org/?probe=1b491bcfeb) | Jun 07, 2023 |
| HP            | EliteBook 2560p             | [f1060e2b5d](https://linux-hardware.org/?probe=f1060e2b5d) | Jun 07, 2023 |
| MSI           | Modern 14 B5M               | [da21766a5c](https://linux-hardware.org/?probe=da21766a5c) | Jun 04, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U7C... | [8c16cec2e8](https://linux-hardware.org/?probe=8c16cec2e8) | Jun 01, 2023 |
| Chuwi         | CoreBook X                  | [f9a2c23bfa](https://linux-hardware.org/?probe=f9a2c23bfa) | May 30, 2023 |
| Dell          | XPS 15 9560                 | [d0a6a8e29e](https://linux-hardware.org/?probe=d0a6a8e29e) | May 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [b9c98caaf4](https://linux-hardware.org/?probe=b9c98caaf4) | May 13, 2023 |
| Dell          | G15 5520                    | [81024f3df4](https://linux-hardware.org/?probe=81024f3df4) | May 08, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [4ad69aea88](https://linux-hardware.org/?probe=4ad69aea88) | May 05, 2023 |
| HUAWEI        | BOM-WXX9                    | [7a7021d420](https://linux-hardware.org/?probe=7a7021d420) | May 04, 2023 |
| MSI           | GV62 7RE                    | [1b048994c9](https://linux-hardware.org/?probe=1b048994c9) | May 04, 2023 |
| Acer          | Nitro AN515-44              | [e26aee893f](https://linux-hardware.org/?probe=e26aee893f) | May 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [21d008c7d8](https://linux-hardware.org/?probe=21d008c7d8) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [49557b8214](https://linux-hardware.org/?probe=49557b8214) | Apr 29, 2023 |
| Dell          | Latitude 7390               | [c24cc9ab68](https://linux-hardware.org/?probe=c24cc9ab68) | Apr 29, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [eeef579322](https://linux-hardware.org/?probe=eeef579322) | Apr 28, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [af72838c03](https://linux-hardware.org/?probe=af72838c03) | Apr 21, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [85fa6bf3d5](https://linux-hardware.org/?probe=85fa6bf3d5) | Apr 21, 2023 |
| Acer          | Nitro AN517-55              | [82931a3c45](https://linux-hardware.org/?probe=82931a3c45) | Apr 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S8XJ0... | [6406153cbf](https://linux-hardware.org/?probe=6406153cbf) | Apr 12, 2023 |
| ASUSTek       | TP500LAG                    | [ae048d3165](https://linux-hardware.org/?probe=ae048d3165) | Apr 12, 2023 |
| HUAWEI        | BOM-WXX9                    | [c56952417d](https://linux-hardware.org/?probe=c56952417d) | Apr 11, 2023 |
| ASUSTek       | TP500LAG                    | [b67954cc59](https://linux-hardware.org/?probe=b67954cc59) | Apr 10, 2023 |
| Dell          | Latitude E6440              | [8153a28710](https://linux-hardware.org/?probe=8153a28710) | Apr 09, 2023 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [320195c782](https://linux-hardware.org/?probe=320195c782) | Apr 06, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [3d59062866](https://linux-hardware.org/?probe=3d59062866) | Apr 06, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | [81400b8912](https://linux-hardware.org/?probe=81400b8912) | Apr 04, 2023 |
| MSI           | GV62 7RE                    | [5d441311f4](https://linux-hardware.org/?probe=5d441311f4) | Apr 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | [9ba99b597e](https://linux-hardware.org/?probe=9ba99b597e) | Apr 03, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | [40489044a0](https://linux-hardware.org/?probe=40489044a0) | Mar 31, 2023 |
| Lenovo        | ThinkPad T430 2349A17       | [1b3629b77e](https://linux-hardware.org/?probe=1b3629b77e) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [e09dc41124](https://linux-hardware.org/?probe=e09dc41124) | Mar 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [23e4353a34](https://linux-hardware.org/?probe=23e4353a34) | Mar 22, 2023 |
| Chuwi         | CoreBook X                  | [fd4d05d961](https://linux-hardware.org/?probe=fd4d05d961) | Mar 20, 2023 |
| Acer          | Aspire A715-42G             | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Dell          | Latitude 7290               | [576b8aa32a](https://linux-hardware.org/?probe=576b8aa32a) | Mar 13, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [315750ea63](https://linux-hardware.org/?probe=315750ea63) | Mar 11, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [c45a0f2220](https://linux-hardware.org/?probe=c45a0f2220) | Mar 11, 2023 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [e4164a80cd](https://linux-hardware.org/?probe=e4164a80cd) | Mar 09, 2023 |
| Acer          | Nitro AN515-58              | [d8d83e3bb3](https://linux-hardware.org/?probe=d8d83e3bb3) | Mar 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [3cec8a7abc](https://linux-hardware.org/?probe=3cec8a7abc) | Mar 03, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [219f16372b](https://linux-hardware.org/?probe=219f16372b) | Mar 03, 2023 |
| Samsung       | 930XDA                      | [684b448b3a](https://linux-hardware.org/?probe=684b448b3a) | Mar 03, 2023 |
| Dell          | Latitude E6510              | [80edceafbc](https://linux-hardware.org/?probe=80edceafbc) | Mar 03, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [4ead3fc236](https://linux-hardware.org/?probe=4ead3fc236) | Mar 03, 2023 |
| Dell          | Latitude 3400               | [2936e7f368](https://linux-hardware.org/?probe=2936e7f368) | Feb 28, 2023 |
| Dell          | Precision M4600             | [901a8de667](https://linux-hardware.org/?probe=901a8de667) | Feb 24, 2023 |
| Dell          | Precision M4600             | [2bdbf753b0](https://linux-hardware.org/?probe=2bdbf753b0) | Feb 21, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [12bb4f91ae](https://linux-hardware.org/?probe=12bb4f91ae) | Feb 20, 2023 |
| HP            | ZBook Firefly 14 inch G9... | [a4404180b7](https://linux-hardware.org/?probe=a4404180b7) | Feb 20, 2023 |
| HP            | 245 G8 Notebook PC          | [1236b5c48f](https://linux-hardware.org/?probe=1236b5c48f) | Feb 19, 2023 |
| HP            | 245 G8 Notebook PC          | [c48e458030](https://linux-hardware.org/?probe=c48e458030) | Feb 16, 2023 |
| Dell          | Inspiron 3558               | [420ccdfca6](https://linux-hardware.org/?probe=420ccdfca6) | Feb 07, 2023 |
| Apple         | MacBookPro11,4              | [cfcea0a331](https://linux-hardware.org/?probe=cfcea0a331) | Feb 05, 2023 |
| MSI           | Modern 14 B11SBU            | [50538fe8fd](https://linux-hardware.org/?probe=50538fe8fd) | Feb 05, 2023 |
| Dell          | Inspiron 3585               | [8da4ffdd5c](https://linux-hardware.org/?probe=8da4ffdd5c) | Feb 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [b660fd4859](https://linux-hardware.org/?probe=b660fd4859) | Feb 03, 2023 |
| Timi          | RedmiBook Pro 15S           | [8a1c423c67](https://linux-hardware.org/?probe=8a1c423c67) | Feb 03, 2023 |
| Acer          | Aspire A715-42G             | [a169951063](https://linux-hardware.org/?probe=a169951063) | Feb 02, 2023 |
| Acer          | Aspire A715-42G             | [45890fca78](https://linux-hardware.org/?probe=45890fca78) | Feb 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S3PV00    | [08f4e80cb9](https://linux-hardware.org/?probe=08f4e80cb9) | Feb 02, 2023 |
| Timi          | RedmiBook Pro 15S           | [4629dc82aa](https://linux-hardware.org/?probe=4629dc82aa) | Jan 25, 2023 |
| Acer          | Aspire A715-42G             | [206359e4ad](https://linux-hardware.org/?probe=206359e4ad) | Jan 08, 2023 |
| Acer          | Aspire A715-42G             | [eed9db8255](https://linux-hardware.org/?probe=eed9db8255) | Jan 08, 2023 |
| Lenovo        | ThinkPad T470s 20HF0015U... | [1ece644fe1](https://linux-hardware.org/?probe=1ece644fe1) | Jan 04, 2023 |
| Dell          | Precision 3560              | [8cb8a3f5cf](https://linux-hardware.org/?probe=8cb8a3f5cf) | Jan 04, 2023 |
| Anbernic      | Win600                      | [db576ded28](https://linux-hardware.org/?probe=db576ded28) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c82ebf8b80](https://linux-hardware.org/?probe=c82ebf8b80) | Dec 26, 2022 |
| Anbernic      | Win600                      | [f7759a13d8](https://linux-hardware.org/?probe=f7759a13d8) | Dec 25, 2022 |
| Dell          | Latitude E6440              | [3b6ac9ce59](https://linux-hardware.org/?probe=3b6ac9ce59) | Dec 19, 2022 |
| Lenovo        | ThinkPad T470s 20HF0015U... | [3fd30db5e1](https://linux-hardware.org/?probe=3fd30db5e1) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [f82368713d](https://linux-hardware.org/?probe=f82368713d) | Dec 17, 2022 |
| Dell          | Inspiron 5502               | [66635e6315](https://linux-hardware.org/?probe=66635e6315) | Dec 16, 2022 |
| HP            | 350 G1                      | [c15f80a386](https://linux-hardware.org/?probe=c15f80a386) | Dec 12, 2022 |
| Dell          | Latitude E7240              | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| Dell          | Latitude 7390               | [9278bcc6a2](https://linux-hardware.org/?probe=9278bcc6a2) | Nov 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [33113bb27d](https://linux-hardware.org/?probe=33113bb27d) | Nov 17, 2022 |
| Dell          | Vostro 5490                 | [b19387a8f3](https://linux-hardware.org/?probe=b19387a8f3) | Nov 16, 2022 |
| Apple         | MacBookPro11,4              | [91268b9919](https://linux-hardware.org/?probe=91268b9919) | Nov 16, 2022 |
| Dell          | Latitude E6530              | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [4b0ce24e6e](https://linux-hardware.org/?probe=4b0ce24e6e) | Nov 11, 2022 |
| Google        | Drallion                    | [7cb5922896](https://linux-hardware.org/?probe=7cb5922896) | Nov 10, 2022 |
| Dell          | G15 5511                    | [8a3246caed](https://linux-hardware.org/?probe=8a3246caed) | Nov 10, 2022 |
| Lenovo        | ThinkBook 14 G4+ ARA 21D... | [86f71fb0e6](https://linux-hardware.org/?probe=86f71fb0e6) | Nov 10, 2022 |
| Dell          | Latitude E5430 non-vPro     | [70a0354dba](https://linux-hardware.org/?probe=70a0354dba) | Oct 30, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| Acer          | Aspire 4739Z                | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| Dell          | Inspiron 13 5310            | [128725bb4d](https://linux-hardware.org/?probe=128725bb4d) | Oct 04, 2022 |
| Dell          | Latitude E7240              | [84ce32d994](https://linux-hardware.org/?probe=84ce32d994) | Oct 03, 2022 |
| Dell          | Vostro 3500                 | [396f61d294](https://linux-hardware.org/?probe=396f61d294) | Oct 03, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | [403aa5af3e](https://linux-hardware.org/?probe=403aa5af3e) | Oct 01, 2022 |
| Dell          | Vostro 5568                 | [44bf0dbbce](https://linux-hardware.org/?probe=44bf0dbbce) | Oct 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [a31db51878](https://linux-hardware.org/?probe=a31db51878) | Sep 26, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [68d36ec742](https://linux-hardware.org/?probe=68d36ec742) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [2f16f0177f](https://linux-hardware.org/?probe=2f16f0177f) | Sep 21, 2022 |
| Lenovo        | ThinkPad T430 2349A17       | [ba2eadfd53](https://linux-hardware.org/?probe=ba2eadfd53) | Sep 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Lenovo        | ThinkPad T450s 20BX005GU... | [5c41d03119](https://linux-hardware.org/?probe=5c41d03119) | Sep 15, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [c07c5b31f6](https://linux-hardware.org/?probe=c07c5b31f6) | Sep 13, 2022 |
| Dell          | XPS 17 9710                 | [4b728bc447](https://linux-hardware.org/?probe=4b728bc447) | Sep 12, 2022 |
| Acer          | Aspire E5-575               | [8b1a8497c7](https://linux-hardware.org/?probe=8b1a8497c7) | Aug 21, 2022 |
| Dell          | Latitude E5540              | [7d8a8607f8](https://linux-hardware.org/?probe=7d8a8607f8) | Aug 13, 2022 |
| ASUSTek       | GL552VX                     | [16c1976ac6](https://linux-hardware.org/?probe=16c1976ac6) | Aug 12, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | [aa4b21b3a7](https://linux-hardware.org/?probe=aa4b21b3a7) | Aug 12, 2022 |
| Lenovo        | ThinkPad P50 20EQS4QM00     | [9779cc7396](https://linux-hardware.org/?probe=9779cc7396) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU... | [688ae71abc](https://linux-hardware.org/?probe=688ae71abc) | Aug 12, 2022 |
| ASUSTek       | K55A                        | [fb75627e6c](https://linux-hardware.org/?probe=fb75627e6c) | Aug 10, 2022 |
| Dell          | G3 3500                     | [69f594bb80](https://linux-hardware.org/?probe=69f594bb80) | Aug 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [a4e02af6d9](https://linux-hardware.org/?probe=a4e02af6d9) | Aug 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [d9c5b6d4c5](https://linux-hardware.org/?probe=d9c5b6d4c5) | Aug 02, 2022 |
| Toshiba       | dynabook Satellite B35/R    | [4600fb0c71](https://linux-hardware.org/?probe=4600fb0c71) | Jul 31, 2022 |
| HP            | EliteBook 8470p             | [2171abfd3d](https://linux-hardware.org/?probe=2171abfd3d) | Jul 30, 2022 |
| Chuwi         | GemiBook Pro                | [ff08461db4](https://linux-hardware.org/?probe=ff08461db4) | Jul 07, 2022 |
| TENKU         | SB14                        | [cbe2900f4f](https://linux-hardware.org/?probe=cbe2900f4f) | Jul 02, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [cacc2464af](https://linux-hardware.org/?probe=cacc2464af) | Jun 23, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [6eb841aab1](https://linux-hardware.org/?probe=6eb841aab1) | Jun 21, 2022 |
| Acer          | Aspire 5738                 | [58b312c382](https://linux-hardware.org/?probe=58b312c382) | Jun 09, 2022 |
| Chuwi         | GemiBook Pro                | [7bd963dd56](https://linux-hardware.org/?probe=7bd963dd56) | Jun 09, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | [a8c7fc9c3a](https://linux-hardware.org/?probe=a8c7fc9c3a) | Jun 07, 2022 |
| Chuwi         | GemiBook Pro                | [e8dd7b95a6](https://linux-hardware.org/?probe=e8dd7b95a6) | Jun 03, 2022 |
| MSI           | Bravo 15 B5DD               | [4ae400000f](https://linux-hardware.org/?probe=4ae400000f) | Jun 01, 2022 |
| Lenovo        | ThinkPad T580 20L9S14S00    | [63bc3a2ce5](https://linux-hardware.org/?probe=63bc3a2ce5) | May 27, 2022 |
| Acer          | Aspire A315-57G             | [d0400f8d02](https://linux-hardware.org/?probe=d0400f8d02) | May 26, 2022 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [9df127ec26](https://linux-hardware.org/?probe=9df127ec26) | May 24, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bb2ffeb78a](https://linux-hardware.org/?probe=bb2ffeb78a) | May 04, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bb73f6aa37](https://linux-hardware.org/?probe=bb73f6aa37) | May 04, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [51625474b7](https://linux-hardware.org/?probe=51625474b7) | Apr 30, 2022 |
| ASUSTek       | E402SA                      | [4c5cbe705d](https://linux-hardware.org/?probe=4c5cbe705d) | Apr 27, 2022 |
| Dell          | Inspiron 3537               | [2fcc2371d9](https://linux-hardware.org/?probe=2fcc2371d9) | Apr 25, 2022 |
| MSI           | GF63 8RD                    | [287e344d0e](https://linux-hardware.org/?probe=287e344d0e) | Apr 16, 2022 |
| HP            | EliteBook 840 G5            | [7499dbd303](https://linux-hardware.org/?probe=7499dbd303) | Apr 15, 2022 |
| Dell          | System Vostro 3450          | [78750d86f5](https://linux-hardware.org/?probe=78750d86f5) | Mar 19, 2022 |
| Dell          | Vostro 3400                 | [5dcc8e2cee](https://linux-hardware.org/?probe=5dcc8e2cee) | Mar 14, 2022 |
| Dell          | Latitude E5540              | [0948114af7](https://linux-hardware.org/?probe=0948114af7) | Mar 03, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [6b0f448d7b](https://linux-hardware.org/?probe=6b0f448d7b) | Feb 24, 2022 |
| Dell          | System XPS L702X            | [e1d4821ec2](https://linux-hardware.org/?probe=e1d4821ec2) | Feb 19, 2022 |
| Dell          | Inspiron N4050              | [0619812e27](https://linux-hardware.org/?probe=0619812e27) | Feb 11, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [4834a3fe2e](https://linux-hardware.org/?probe=4834a3fe2e) | Feb 09, 2022 |
| Dell          | G3 3500                     | [9001ccacbc](https://linux-hardware.org/?probe=9001ccacbc) | Feb 09, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [2621c151ec](https://linux-hardware.org/?probe=2621c151ec) | Feb 01, 2022 |
| Dell          | Vostro 3578                 | [a95dfa8bc8](https://linux-hardware.org/?probe=a95dfa8bc8) | Jan 26, 2022 |
| Lenovo        | ThinkPad T480 20L5001DUS    | [872bc057f0](https://linux-hardware.org/?probe=872bc057f0) | Jan 10, 2022 |
| HP            | EliteBook 840 G2            | [5588a84fcf](https://linux-hardware.org/?probe=5588a84fcf) | Jan 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [d65648c445](https://linux-hardware.org/?probe=d65648c445) | Jan 09, 2022 |
| HP            | EliteBook 840 G2            | [3b97b65258](https://linux-hardware.org/?probe=3b97b65258) | Jan 08, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [65c9a87d51](https://linux-hardware.org/?probe=65c9a87d51) | Jan 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [48cfc7d185](https://linux-hardware.org/?probe=48cfc7d185) | Dec 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [b64750f465](https://linux-hardware.org/?probe=b64750f465) | Dec 26, 2021 |
| Dell          | XPS 15 9500                 | [717b9f1dd0](https://linux-hardware.org/?probe=717b9f1dd0) | Dec 16, 2021 |
| Apple         | MacBookPro9,2               | [21d85302a2](https://linux-hardware.org/?probe=21d85302a2) | Dec 05, 2021 |
| Dell          | Vostro 3500                 | [903f3e93ee](https://linux-hardware.org/?probe=903f3e93ee) | Dec 03, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [70c63b2fb6](https://linux-hardware.org/?probe=70c63b2fb6) | Dec 02, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [c5d4bf5c62](https://linux-hardware.org/?probe=c5d4bf5c62) | Dec 02, 2021 |
| Dell          | Vostro 3500                 | [7a8a79d813](https://linux-hardware.org/?probe=7a8a79d813) | Dec 02, 2021 |
| Timi          | A35S                        | [dbb600147d](https://linux-hardware.org/?probe=dbb600147d) | Nov 30, 2021 |
| HP            | Laptop 15s-du1xxx           | [d4cf81aaa5](https://linux-hardware.org/?probe=d4cf81aaa5) | Nov 23, 2021 |
| HP            | Laptop 15s-du1xxx           | [0368cfb8e2](https://linux-hardware.org/?probe=0368cfb8e2) | Nov 23, 2021 |
| Dell          | XPS 15 9500                 | [10455f4980](https://linux-hardware.org/?probe=10455f4980) | Nov 23, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [17781cb457](https://linux-hardware.org/?probe=17781cb457) | Nov 20, 2021 |
| ASUSTek       | X550LD                      | [f4a646d1f8](https://linux-hardware.org/?probe=f4a646d1f8) | Nov 18, 2021 |
| HP            | EliteBook 840 G5            | [5471ce2e2f](https://linux-hardware.org/?probe=5471ce2e2f) | Nov 16, 2021 |
| HP            | EliteBook 8470p             | [96b971a0ed](https://linux-hardware.org/?probe=96b971a0ed) | Nov 08, 2021 |
| Dell          | Inspiron 5420               | [a471ac5d59](https://linux-hardware.org/?probe=a471ac5d59) | Nov 07, 2021 |
| Dell          | Vostro 3478                 | [f88e5eec69](https://linux-hardware.org/?probe=f88e5eec69) | Nov 05, 2021 |
| Dell          | Vostro 3478                 | [8174188077](https://linux-hardware.org/?probe=8174188077) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [f9bc7efe7b](https://linux-hardware.org/?probe=f9bc7efe7b) | Nov 05, 2021 |
| ASUSTek       | K45A                        | [096deec12d](https://linux-hardware.org/?probe=096deec12d) | Nov 05, 2021 |
| Dell          | Precision 7510              | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [5158fb179d](https://linux-hardware.org/?probe=5158fb179d) | Nov 02, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [3296f4587d](https://linux-hardware.org/?probe=3296f4587d) | Nov 02, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6a546c5681](https://linux-hardware.org/?probe=6a546c5681) | Oct 23, 2021 |
| HP            | ZBook Firefly 14 inch G8... | [603ccdfb84](https://linux-hardware.org/?probe=603ccdfb84) | Oct 19, 2021 |
| Dell          | Precision 7510              | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| HP            | Notebook                    | [6ac2c09585](https://linux-hardware.org/?probe=6ac2c09585) | Oct 09, 2021 |
| HP            | Laptop 15-bs1xx             | [c9fd6887d4](https://linux-hardware.org/?probe=c9fd6887d4) | Oct 06, 2021 |
| Acer          | Predator PH315-51           | [fb9a605481](https://linux-hardware.org/?probe=fb9a605481) | Oct 05, 2021 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [b1fb3d4e88](https://linux-hardware.org/?probe=b1fb3d4e88) | Oct 04, 2021 |
| Dell          | Latitude E7440              | [fe4153e816](https://linux-hardware.org/?probe=fe4153e816) | Oct 04, 2021 |
| HP            | EliteBook Folio 9470m       | [101371762b](https://linux-hardware.org/?probe=101371762b) | Oct 01, 2021 |
| Dell          | XPS 13 9350                 | [c1dc59d33f](https://linux-hardware.org/?probe=c1dc59d33f) | Sep 29, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [52fe5aa259](https://linux-hardware.org/?probe=52fe5aa259) | Sep 29, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [d8cde7951e](https://linux-hardware.org/?probe=d8cde7951e) | Sep 29, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [db7c214214](https://linux-hardware.org/?probe=db7c214214) | Sep 28, 2021 |
| Dell          | Latitude 3520               | [2fb41f5f08](https://linux-hardware.org/?probe=2fb41f5f08) | Sep 24, 2021 |
| HP            | 15                          | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Sony          | SVE14A15FGW                 | [f1049f7db1](https://linux-hardware.org/?probe=f1049f7db1) | Sep 21, 2021 |
| Panasonic     | CFSX4-1                     | [d474bc1b91](https://linux-hardware.org/?probe=d474bc1b91) | Sep 03, 2021 |
| Panasonic     | CFSX4-1                     | [bee71431a0](https://linux-hardware.org/?probe=bee71431a0) | Sep 03, 2021 |
| HP            | Laptop 15s-fq2xxx           | [87b688768a](https://linux-hardware.org/?probe=87b688768a) | Sep 02, 2021 |
| LG Electro... | 17U70N-R.AAS7U1             | [fd3572c46a](https://linux-hardware.org/?probe=fd3572c46a) | Aug 19, 2021 |
| MSI           | GF62 7RD                    | [5a35b145a9](https://linux-hardware.org/?probe=5a35b145a9) | Aug 19, 2021 |
| MSI           | GE66 Raider 11UH            | [df3d4bfff1](https://linux-hardware.org/?probe=df3d4bfff1) | Aug 18, 2021 |
| MSI           | GE66 Raider 11UH            | [dde539e1b1](https://linux-hardware.org/?probe=dde539e1b1) | Aug 18, 2021 |
| HP            | ProBook 4430s               | [0235e3c344](https://linux-hardware.org/?probe=0235e3c344) | Aug 18, 2021 |
| HP            | EliteBook 745 G6            | [d3ed4611f3](https://linux-hardware.org/?probe=d3ed4611f3) | Aug 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [f77c5c4c48](https://linux-hardware.org/?probe=f77c5c4c48) | Aug 10, 2021 |
| Dell          | Inspiron 5502               | [57bf64ac4b](https://linux-hardware.org/?probe=57bf64ac4b) | Aug 09, 2021 |
| Dell          | Inspiron 5502               | [955889f7c8](https://linux-hardware.org/?probe=955889f7c8) | Aug 08, 2021 |
| Dell          | Vostro 15-3568              | [5f68a1fdaa](https://linux-hardware.org/?probe=5f68a1fdaa) | Aug 07, 2021 |
| Acer          | Aspire E5-572G              | [76e0c19c46](https://linux-hardware.org/?probe=76e0c19c46) | Aug 02, 2021 |
| Dell          | Vostro 15-3568              | [94aa730eda](https://linux-hardware.org/?probe=94aa730eda) | Jul 23, 2021 |
| Dell          | Vostro 5568                 | [f6fc2c1a8c](https://linux-hardware.org/?probe=f6fc2c1a8c) | Jul 19, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [aa5fadb321](https://linux-hardware.org/?probe=aa5fadb321) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [dcc22fa273](https://linux-hardware.org/?probe=dcc22fa273) | Jul 13, 2021 |
| Dell          | Vostro 15-3568              | [3d6d3007cf](https://linux-hardware.org/?probe=3d6d3007cf) | Jul 10, 2021 |
| Dell          | Vostro 15-3568              | [66d001f315](https://linux-hardware.org/?probe=66d001f315) | Jul 09, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | [e6cb486cfd](https://linux-hardware.org/?probe=e6cb486cfd) | Jul 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4XX0... | [58ad5d25b9](https://linux-hardware.org/?probe=58ad5d25b9) | Jul 07, 2021 |
| Dell          | Latitude E6410              | [9a4002aa3d](https://linux-hardware.org/?probe=9a4002aa3d) | Jul 07, 2021 |
| HP            | Compaq 510                  | [cd27b78fea](https://linux-hardware.org/?probe=cd27b78fea) | Jul 04, 2021 |
| Dell          | Vostro 5568                 | [bec8a61ff4](https://linux-hardware.org/?probe=bec8a61ff4) | Jul 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3fb422fa2e](https://linux-hardware.org/?probe=3fb422fa2e) | Jun 27, 2021 |
| ASUSTek       | K46CA                       | [85b912e99c](https://linux-hardware.org/?probe=85b912e99c) | Jun 22, 2021 |
| Acer          | Aspire 4315                 | [ac56c24f68](https://linux-hardware.org/?probe=ac56c24f68) | Jun 15, 2021 |
| Acer          | Aspire 4315                 | [4527ee70c7](https://linux-hardware.org/?probe=4527ee70c7) | Jun 13, 2021 |
| Lenovo        | ThinkPad L520 5015A76       | [84b62cbde9](https://linux-hardware.org/?probe=84b62cbde9) | Jun 10, 2021 |
| Dell          | Vostro 15-3568              | [de3596a9a3](https://linux-hardware.org/?probe=de3596a9a3) | Jun 05, 2021 |
| Dell          | Latitude 7420               | [f417016cf6](https://linux-hardware.org/?probe=f417016cf6) | Jun 04, 2021 |
| Lenovo        | V130-14IKB 81HQ             | [8995f3c1ad](https://linux-hardware.org/?probe=8995f3c1ad) | Jun 01, 2021 |
| Lenovo        | Z40-70 20366                | [b1b8196f26](https://linux-hardware.org/?probe=b1b8196f26) | May 31, 2021 |
| Lenovo        | ThinkPad X250 20CLCTO1WW    | [a5d677976f](https://linux-hardware.org/?probe=a5d677976f) | May 29, 2021 |
| Acer          | Swift SF314-59              | [b70a62225d](https://linux-hardware.org/?probe=b70a62225d) | May 22, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [ddfb904938](https://linux-hardware.org/?probe=ddfb904938) | May 19, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [35324d2388](https://linux-hardware.org/?probe=35324d2388) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1abefab68f](https://linux-hardware.org/?probe=1abefab68f) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [c4ea8f1bab](https://linux-hardware.org/?probe=c4ea8f1bab) | May 19, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [2ce7106efb](https://linux-hardware.org/?probe=2ce7106efb) | May 15, 2021 |
| HP            | ProBook 450 G4              | [b8108b310a](https://linux-hardware.org/?probe=b8108b310a) | May 13, 2021 |
| HP            | ProBook 450 G4              | [c596247722](https://linux-hardware.org/?probe=c596247722) | May 13, 2021 |
| Dell          | Inspiron 3443               | [c84fc5c646](https://linux-hardware.org/?probe=c84fc5c646) | May 12, 2021 |
| Acer          | Predator G9-793             | [90b04b667a](https://linux-hardware.org/?probe=90b04b667a) | May 03, 2021 |
| HP            | Pavilion 15                 | [1ddb966308](https://linux-hardware.org/?probe=1ddb966308) | Apr 28, 2021 |
| Sony          | VPCCW13FX                   | [82e9a1f82a](https://linux-hardware.org/?probe=82e9a1f82a) | Apr 25, 2021 |
| Dell          | Precision 3520              | [fc2d295c0e](https://linux-hardware.org/?probe=fc2d295c0e) | Apr 24, 2021 |
| HP            | ProBook 445 G7              | [76defcf2f7](https://linux-hardware.org/?probe=76defcf2f7) | Apr 22, 2021 |
| MSI           | Prestige 15 A11SCX          | [007ae7cca0](https://linux-hardware.org/?probe=007ae7cca0) | Apr 18, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [07736896f9](https://linux-hardware.org/?probe=07736896f9) | Apr 18, 2021 |
| HP            | Unknown                     | [2465109965](https://linux-hardware.org/?probe=2465109965) | Apr 13, 2021 |
| Lenovo        | IdeaPadFlex 14 20308        | [698d0ca8cc](https://linux-hardware.org/?probe=698d0ca8cc) | Apr 08, 2021 |
| Dell          | G3 3579                     | [d5d191947e](https://linux-hardware.org/?probe=d5d191947e) | Apr 06, 2021 |
| Dell          | G3 3579                     | [07fd740efe](https://linux-hardware.org/?probe=07fd740efe) | Apr 06, 2021 |
| Chuwi         | LapBook SE                  | [0e9a03cc48](https://linux-hardware.org/?probe=0e9a03cc48) | Apr 06, 2021 |
| MSI           | Prestige 15 A11SCX          | [d20d2b755f](https://linux-hardware.org/?probe=d20d2b755f) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | [e8c59a070a](https://linux-hardware.org/?probe=e8c59a070a) | Apr 04, 2021 |
| Toshiba       | Satellite E45-B             | [b9324b1b4d](https://linux-hardware.org/?probe=b9324b1b4d) | Apr 04, 2021 |
| Gigabyte      | AERO 15-X9                  | [0984402bad](https://linux-hardware.org/?probe=0984402bad) | Apr 03, 2021 |
| Gigabyte      | AERO 15-X9                  | [eba80415c0](https://linux-hardware.org/?probe=eba80415c0) | Apr 03, 2021 |
| MSI           | GS40 6QE Phantom            | [adbf080ab7](https://linux-hardware.org/?probe=adbf080ab7) | Mar 27, 2021 |
| HP            | ProBook 440 G7              | [12fd74ecdc](https://linux-hardware.org/?probe=12fd74ecdc) | Mar 26, 2021 |
| Acer          | Aspire A315-42              | [43f33bc8e0](https://linux-hardware.org/?probe=43f33bc8e0) | Mar 21, 2021 |
| Acer          | Aspire A315-42              | [c377f57ac8](https://linux-hardware.org/?probe=c377f57ac8) | Mar 21, 2021 |
| Dell          | XPS 15 9500                 | [cac842cdbb](https://linux-hardware.org/?probe=cac842cdbb) | Mar 20, 2021 |
| Dell          | Inspiron 3537               | [66ce284547](https://linux-hardware.org/?probe=66ce284547) | Mar 14, 2021 |
| Dell          | Vostro 3460                 | [a8e1128b26](https://linux-hardware.org/?probe=a8e1128b26) | Mar 13, 2021 |
| Dell          | Inspiron 3537               | [f85fc12bff](https://linux-hardware.org/?probe=f85fc12bff) | Mar 09, 2021 |
| ASUSTek       | X202E                       | [cc089d4ddb](https://linux-hardware.org/?probe=cc089d4ddb) | Mar 08, 2021 |
| Dell          | XPS 15 9500                 | [647b5fbb43](https://linux-hardware.org/?probe=647b5fbb43) | Mar 06, 2021 |
| Acer          | Aspire A515-53              | [637c3ebf75](https://linux-hardware.org/?probe=637c3ebf75) | Feb 28, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [05ad71d3d8](https://linux-hardware.org/?probe=05ad71d3d8) | Feb 24, 2021 |
| Gateway       | LT40                        | [90ae93da93](https://linux-hardware.org/?probe=90ae93da93) | Feb 24, 2021 |
| Gateway       | LT40                        | [98f2ce8032](https://linux-hardware.org/?probe=98f2ce8032) | Feb 24, 2021 |
| Acer          | Aspire E5-572G              | [4a441fe0c9](https://linux-hardware.org/?probe=4a441fe0c9) | Feb 21, 2021 |
| Acer          | Aspire A315-42              | [bfb791c2fb](https://linux-hardware.org/?probe=bfb791c2fb) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | [87b755412e](https://linux-hardware.org/?probe=87b755412e) | Feb 19, 2021 |
| Sony          | VGN-NW270F                  | [8d0bcb0740](https://linux-hardware.org/?probe=8d0bcb0740) | Feb 19, 2021 |
| Dell          | Inspiron 5570               | [a79c837a9b](https://linux-hardware.org/?probe=a79c837a9b) | Feb 16, 2021 |
| Dell          | Inspiron 5570               | [5cb0f77327](https://linux-hardware.org/?probe=5cb0f77327) | Feb 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [0c70deaac1](https://linux-hardware.org/?probe=0c70deaac1) | Feb 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [0441228ba8](https://linux-hardware.org/?probe=0441228ba8) | Feb 07, 2021 |
| Dell          | Latitude E7450              | [94b0fc1fc8](https://linux-hardware.org/?probe=94b0fc1fc8) | Feb 06, 2021 |
| Acer          | Swift SF315-52              | [b2b00b4390](https://linux-hardware.org/?probe=b2b00b4390) | Jan 30, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [d7f2ee4a81](https://linux-hardware.org/?probe=d7f2ee4a81) | Jan 25, 2021 |
| Toshiba       | Satellite L840              | [82f5ebd486](https://linux-hardware.org/?probe=82f5ebd486) | Jan 18, 2021 |
| ASUSTek       | X550CC                      | [6eaddc8157](https://linux-hardware.org/?probe=6eaddc8157) | Dec 21, 2020 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [fb16534a29](https://linux-hardware.org/?probe=fb16534a29) | Dec 17, 2020 |
| Sony          | VGN-NW270F                  | [d8989e5c40](https://linux-hardware.org/?probe=d8989e5c40) | Dec 16, 2020 |
| Apple         | MacBookPro11,4              | [e880800d6f](https://linux-hardware.org/?probe=e880800d6f) | Dec 13, 2020 |
| Dell          | G3 3579                     | [99724b8bd6](https://linux-hardware.org/?probe=99724b8bd6) | Dec 12, 2020 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [fa10ea29e8](https://linux-hardware.org/?probe=fa10ea29e8) | Dec 11, 2020 |
| Acer          | Predator PH315-51           | [c9539f5932](https://linux-hardware.org/?probe=c9539f5932) | Dec 09, 2020 |
| HP            | EliteBook 840 G2            | [ea2bf23a76](https://linux-hardware.org/?probe=ea2bf23a76) | Dec 03, 2020 |
| HP            | Compaq Presario CQ45        | [2a4ce919e5](https://linux-hardware.org/?probe=2a4ce919e5) | Dec 03, 2020 |
| Acer          | Aspire V5-431P              | [831f0df544](https://linux-hardware.org/?probe=831f0df544) | Dec 03, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | [4e39668b71](https://linux-hardware.org/?probe=4e39668b71) | Dec 02, 2020 |
| Lenovo        | ThinkPad T430 2349A17       | [dbff453f7e](https://linux-hardware.org/?probe=dbff453f7e) | Dec 02, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [80f3a03fc2](https://linux-hardware.org/?probe=80f3a03fc2) | Nov 22, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | [471b375bb8](https://linux-hardware.org/?probe=471b375bb8) | Nov 22, 2020 |
| HP            | ENVY Laptop 13-ba0xxx       | [32692a5980](https://linux-hardware.org/?probe=32692a5980) | Nov 18, 2020 |
| HP            | Pavilion Laptop 15-cs3xx... | [4019b6c1ff](https://linux-hardware.org/?probe=4019b6c1ff) | Nov 16, 2020 |
| Dell          | XPS 15 9570                 | [7fb140838e](https://linux-hardware.org/?probe=7fb140838e) | Nov 12, 2020 |
| Dell          | XPS 15 9570                 | [ac263c6ad6](https://linux-hardware.org/?probe=ac263c6ad6) | Nov 10, 2020 |
| HP            | Compaq Presario CQ45        | [f2a745943a](https://linux-hardware.org/?probe=f2a745943a) | Nov 04, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [bfa10fd887](https://linux-hardware.org/?probe=bfa10fd887) | Nov 04, 2020 |
| Dell          | Latitude 7490               | [8f0ec25c05](https://linux-hardware.org/?probe=8f0ec25c05) | Oct 29, 2020 |
| Dell          | Latitude E6530              | [1a16aeb4dd](https://linux-hardware.org/?probe=1a16aeb4dd) | Oct 28, 2020 |
| HP            | EliteBook 840 G2            | [070dae158a](https://linux-hardware.org/?probe=070dae158a) | Oct 24, 2020 |
| Toshiba       | Satellite L840              | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | [fa061b6d7e](https://linux-hardware.org/?probe=fa061b6d7e) | Oct 13, 2020 |
| ASUSTek       | ASUSPRO P1440UA             | [dc9b667685](https://linux-hardware.org/?probe=dc9b667685) | Oct 13, 2020 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [9bf6f0ba43](https://linux-hardware.org/?probe=9bf6f0ba43) | Oct 09, 2020 |
| HP            | EliteBook 840 G5            | [125dd87b84](https://linux-hardware.org/?probe=125dd87b84) | Oct 03, 2020 |
| Acer          | Aspire E5-575G              | [204ef3a0f3](https://linux-hardware.org/?probe=204ef3a0f3) | Oct 02, 2020 |
| Lenovo        | ThinkPad T420 4236C95       | [8cf52f76c0](https://linux-hardware.org/?probe=8cf52f76c0) | Oct 02, 2020 |
| HP            | ProBook 440 G5              | [6753d2054d](https://linux-hardware.org/?probe=6753d2054d) | Oct 01, 2020 |
| HP            | ProBook 440 G5              | [6c568247ff](https://linux-hardware.org/?probe=6c568247ff) | Oct 01, 2020 |
| ASUSTek       | X411UA                      | [15bcec7549](https://linux-hardware.org/?probe=15bcec7549) | Sep 28, 2020 |
| Dell          | Vostro 3578                 | [5ff5b89d5e](https://linux-hardware.org/?probe=5ff5b89d5e) | Sep 22, 2020 |
| Dell          | Inspiron 5559               | [3a8b43fc2f](https://linux-hardware.org/?probe=3a8b43fc2f) | Sep 16, 2020 |
| ASUSTek       | X411UA                      | [8adea7b2b3](https://linux-hardware.org/?probe=8adea7b2b3) | Sep 15, 2020 |
| Dell          | Vostro 1450                 | [444ddb1aa9](https://linux-hardware.org/?probe=444ddb1aa9) | Sep 15, 2020 |
| Dell          | Precision 3520              | [e8f520c4fa](https://linux-hardware.org/?probe=e8f520c4fa) | Sep 09, 2020 |
| MASSCOM VI... | L133                        | [b356f018b2](https://linux-hardware.org/?probe=b356f018b2) | Sep 09, 2020 |
| HP            | ProBook 440 G6              | [11a8a7e166](https://linux-hardware.org/?probe=11a8a7e166) | Sep 07, 2020 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [42cdde5346](https://linux-hardware.org/?probe=42cdde5346) | Sep 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [6b4eeecb26](https://linux-hardware.org/?probe=6b4eeecb26) | Sep 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [a9ced30680](https://linux-hardware.org/?probe=a9ced30680) | Aug 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [17c4f51c75](https://linux-hardware.org/?probe=17c4f51c75) | Aug 29, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [08d8dc8d6e](https://linux-hardware.org/?probe=08d8dc8d6e) | Aug 28, 2020 |
| Lenovo        | ThinkPad L430 2465CTO       | [e5371d9b58](https://linux-hardware.org/?probe=e5371d9b58) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ff005e6d9](https://linux-hardware.org/?probe=4ff005e6d9) | Aug 21, 2020 |
| Lenovo        | ThinkPad T580 20L9001MUS    | [92c940e8c2](https://linux-hardware.org/?probe=92c940e8c2) | Aug 21, 2020 |
| Dell          | Inspiron 3537               | [e7702e2ce8](https://linux-hardware.org/?probe=e7702e2ce8) | Aug 20, 2020 |
| Dell          | G3 3579                     | [8e341b94ae](https://linux-hardware.org/?probe=8e341b94ae) | Aug 18, 2020 |
| Dell          | G3 3579                     | [9a1078144d](https://linux-hardware.org/?probe=9a1078144d) | Aug 18, 2020 |
| HP            | EliteBook 840 G5            | [52f08d8242](https://linux-hardware.org/?probe=52f08d8242) | Aug 12, 2020 |
| Lenovo        | ThinkPad E480 20KN005GVA    | [f77c6858ad](https://linux-hardware.org/?probe=f77c6858ad) | Jul 24, 2020 |
| HP            | EliteBook 840 G5            | [a58d188243](https://linux-hardware.org/?probe=a58d188243) | Jul 19, 2020 |
| Dell          | XPS 15 9570                 | [ab4eff4438](https://linux-hardware.org/?probe=ab4eff4438) | Jul 16, 2020 |
| Dell          | Latitude E5470              | [777b8955c3](https://linux-hardware.org/?probe=777b8955c3) | Jul 12, 2020 |
| Apple         | MacBookPro8,1               | [d0dff5e971](https://linux-hardware.org/?probe=d0dff5e971) | Jul 09, 2020 |
| Dell          | Vostro 3590                 | [4f8fb0d621](https://linux-hardware.org/?probe=4f8fb0d621) | Jul 09, 2020 |
| Dell          | XPS 15 9570                 | [4e1f771d23](https://linux-hardware.org/?probe=4e1f771d23) | Jun 29, 2020 |
| Dell          | Vostro 3460                 | [2338ae0fde](https://linux-hardware.org/?probe=2338ae0fde) | Jun 28, 2020 |
| HP            | ZBook 17 G2                 | [467e55d0db](https://linux-hardware.org/?probe=467e55d0db) | Jun 20, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [652d0e5648](https://linux-hardware.org/?probe=652d0e5648) | Jun 18, 2020 |
| Lenovo        | ThinkPad E14 20RAS0KX00     | [3b5f86f3d4](https://linux-hardware.org/?probe=3b5f86f3d4) | Jun 18, 2020 |
| Dell          | Inspiron 5548               | [60a6140ac2](https://linux-hardware.org/?probe=60a6140ac2) | Jun 14, 2020 |
| Dell          | Inspiron 5548               | [ac70aa8a8d](https://linux-hardware.org/?probe=ac70aa8a8d) | Jun 14, 2020 |
| Dell          | Vostro 3590                 | [faca1b4063](https://linux-hardware.org/?probe=faca1b4063) | Jun 14, 2020 |
| HP            | ZBook Studio G3             | [91a0ff7707](https://linux-hardware.org/?probe=91a0ff7707) | Jun 10, 2020 |
| Dell          | Inspiron 5570               | [be05348be2](https://linux-hardware.org/?probe=be05348be2) | May 29, 2020 |
| Dell          | Inspiron 5570               | [945550a204](https://linux-hardware.org/?probe=945550a204) | May 29, 2020 |
| Dell          | Latitude E7440              | [26b5908778](https://linux-hardware.org/?probe=26b5908778) | May 20, 2020 |
| HP            | EliteBook 8570w             | [849bf107d8](https://linux-hardware.org/?probe=849bf107d8) | May 18, 2020 |
| HP            | EliteBook 8570w             | [5a938c4186](https://linux-hardware.org/?probe=5a938c4186) | May 17, 2020 |
| Dell          | Inspiron 7520               | [f400730782](https://linux-hardware.org/?probe=f400730782) | May 15, 2020 |
| HP            | ProBook 440 G6              | [272430b55d](https://linux-hardware.org/?probe=272430b55d) | May 12, 2020 |
| Toshiba       | PORTEGE T110                | [8c8ec8db54](https://linux-hardware.org/?probe=8c8ec8db54) | May 10, 2020 |
| Acer          | Aspire R3-131T              | [7e7b980d96](https://linux-hardware.org/?probe=7e7b980d96) | May 09, 2020 |
| Dell          | Vostro 14-5480              | [3edae78003](https://linux-hardware.org/?probe=3edae78003) | Apr 28, 2020 |
| Dell          | Inspiron 3558               | [8e17ac8b14](https://linux-hardware.org/?probe=8e17ac8b14) | Apr 27, 2020 |
| Acer          | Swift SF315-52              | [a41dc8c7b3](https://linux-hardware.org/?probe=a41dc8c7b3) | Apr 24, 2020 |
| Dell          | Vostro 3478                 | [65a16b0f00](https://linux-hardware.org/?probe=65a16b0f00) | Apr 22, 2020 |
| HP            | EliteBook 8560w             | [985dd25740](https://linux-hardware.org/?probe=985dd25740) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [8b6c1d10a4](https://linux-hardware.org/?probe=8b6c1d10a4) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [9cb006b675](https://linux-hardware.org/?probe=9cb006b675) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [e670bd004a](https://linux-hardware.org/?probe=e670bd004a) | Apr 19, 2020 |
| Apple         | MacBookPro12,1              | [ed1d4fbd62](https://linux-hardware.org/?probe=ed1d4fbd62) | Apr 19, 2020 |
| Acer          | Aspire E5-575               | [c51238bbe1](https://linux-hardware.org/?probe=c51238bbe1) | Apr 11, 2020 |
| Acer          | Aspire E5-575               | [e421f3a586](https://linux-hardware.org/?probe=e421f3a586) | Apr 10, 2020 |
| Dell          | XPS 13 9360                 | [9d7415c55e](https://linux-hardware.org/?probe=9d7415c55e) | Apr 04, 2020 |
| Dell          | Precision 5530              | [805db6810c](https://linux-hardware.org/?probe=805db6810c) | Mar 31, 2020 |
| HP            | EliteBook 8540w             | [6093f50362](https://linux-hardware.org/?probe=6093f50362) | Mar 30, 2020 |
| Sony          | VPCEB42EG                   | [d2586cdd17](https://linux-hardware.org/?probe=d2586cdd17) | Mar 25, 2020 |
| Sony          | VPCEB42EG                   | [424402e2b1](https://linux-hardware.org/?probe=424402e2b1) | Mar 25, 2020 |
| ASUSTek       | GL553VE                     | [1238bea224](https://linux-hardware.org/?probe=1238bea224) | Mar 21, 2020 |
| HP            | Compaq Presario CQ45        | [72a39494c1](https://linux-hardware.org/?probe=72a39494c1) | Mar 18, 2020 |
| HP            | Laptop 14-bs0xx             | [7dddec34d1](https://linux-hardware.org/?probe=7dddec34d1) | Mar 02, 2020 |
| HP            | Compaq Presario CQ45        | [f1e468eec0](https://linux-hardware.org/?probe=f1e468eec0) | Feb 29, 2020 |
| HP            | Laptop 14-bs0xx             | [3740504388](https://linux-hardware.org/?probe=3740504388) | Feb 28, 2020 |
| ASUSTek       | X411UA                      | [284484a6b6](https://linux-hardware.org/?probe=284484a6b6) | Feb 15, 2020 |
| Koompi        | Unknown                     | [46e5e1375d](https://linux-hardware.org/?probe=46e5e1375d) | Feb 12, 2020 |
| MSI           | GF63 8RD                    | [6eae1d7ba9](https://linux-hardware.org/?probe=6eae1d7ba9) | Feb 01, 2020 |
| MSI           | GF63 8RD                    | [b7087b6ba5](https://linux-hardware.org/?probe=b7087b6ba5) | Jan 31, 2020 |
| ASUSTek       | K501UX                      | [46c0e495c1](https://linux-hardware.org/?probe=46c0e495c1) | Jan 24, 2020 |
| HP            | EliteBook Folio 1040 G3     | [b2bc63b818](https://linux-hardware.org/?probe=b2bc63b818) | Jan 14, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [4ea2e33944](https://linux-hardware.org/?probe=4ea2e33944) | Jan 07, 2020 |
| AMI           | Cherry Trail FFD            | [c62d47b2a1](https://linux-hardware.org/?probe=c62d47b2a1) | Dec 22, 2019 |
| Jumper        | EZpad                       | [6dfb4e2274](https://linux-hardware.org/?probe=6dfb4e2274) | Oct 31, 2019 |
| Dell          | System Vostro 3450          | [2017fd9a25](https://linux-hardware.org/?probe=2017fd9a25) | Oct 29, 2019 |
| Dell          | System Vostro 3450          | [90391fe6fe](https://linux-hardware.org/?probe=90391fe6fe) | Sep 19, 2019 |
| Samsung       | NC208/NC108                 | [a99fe6de20](https://linux-hardware.org/?probe=a99fe6de20) | Sep 16, 2019 |
| Dell          | Inspiron 3421               | [46a7955491](https://linux-hardware.org/?probe=46a7955491) | Sep 04, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | [35dfb93d51](https://linux-hardware.org/?probe=35dfb93d51) | Sep 02, 2019 |
| Lenovo        | ThinkPad T410 2522AN6       | [635d10113c](https://linux-hardware.org/?probe=635d10113c) | Sep 02, 2019 |
| HP            | ProBook 450 G1              | [f9ed638fe3](https://linux-hardware.org/?probe=f9ed638fe3) | Aug 27, 2019 |
| Dell          | System Inspiron N4110       | [1923c8603b](https://linux-hardware.org/?probe=1923c8603b) | Aug 13, 2019 |
| Dell          | Inspiron 3537               | [96b08c73b2](https://linux-hardware.org/?probe=96b08c73b2) | Jul 03, 2019 |
| Dell          | Inspiron 7559               | [9662a59bb6](https://linux-hardware.org/?probe=9662a59bb6) | Jun 19, 2019 |
| ASUSTek       | K46CM                       | [f695a76e03](https://linux-hardware.org/?probe=f695a76e03) | Jun 16, 2019 |
| Lenovo        | ThinkPad X230 2325BK0       | [e3cbad71df](https://linux-hardware.org/?probe=e3cbad71df) | Jun 06, 2019 |
| Dell          | Precision M4800             | [87cd78dbb8](https://linux-hardware.org/?probe=87cd78dbb8) | Jun 06, 2019 |
| Dell          | Inspiron 7559               | [2b022f3e6e](https://linux-hardware.org/?probe=2b022f3e6e) | Jun 06, 2019 |
| HP            | Unknown                     | [5a84e64836](https://linux-hardware.org/?probe=5a84e64836) | Jun 05, 2019 |
| Lenovo        | Unknown                     | [bb521ffe81](https://linux-hardware.org/?probe=bb521ffe81) | May 29, 2019 |
| Lenovo        | Unknown                     | [ded7e33a30](https://linux-hardware.org/?probe=ded7e33a30) | May 29, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | [11b1a757e3](https://linux-hardware.org/?probe=11b1a757e3) | May 07, 2019 |
| Lenovo        | ThinkPad X230 2325YN1       | [48a1bab21b](https://linux-hardware.org/?probe=48a1bab21b) | May 06, 2019 |
| Dell          | Inspiron 3420               | [97669e6bac](https://linux-hardware.org/?probe=97669e6bac) | Apr 28, 2019 |
| Lenovo        | ThinkPad X240 20AMA01LVA    | [60e3dddb8e](https://linux-hardware.org/?probe=60e3dddb8e) | Apr 18, 2019 |
| Lenovo        | ThinkPad X230 2325VEN       | [7de9f34ff3](https://linux-hardware.org/?probe=7de9f34ff3) | Apr 08, 2019 |
| Lenovo        | ThinkPad T61 7661C54        | [f98ce96fd7](https://linux-hardware.org/?probe=f98ce96fd7) | Dec 14, 2018 |
| Lenovo        | ThinkPad T61 7661C54        | [3b2f20eb21](https://linux-hardware.org/?probe=3b2f20eb21) | Dec 14, 2018 |
| Lenovo        | ThinkPad X230 2325BK0       | [eb181d9db4](https://linux-hardware.org/?probe=eb181d9db4) | Nov 17, 2018 |
| MSI           | GP62 6QE                    | [0befde2891](https://linux-hardware.org/?probe=0befde2891) | Oct 29, 2018 |
| MSI           | GP62 6QE                    | [6d5cda0177](https://linux-hardware.org/?probe=6d5cda0177) | Oct 29, 2018 |
| ASUSTek       | FX503VM                     | [c3eafeed41](https://linux-hardware.org/?probe=c3eafeed41) | May 23, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | [b73b24ff47](https://linux-hardware.org/?probe=b73b24ff47) | May 16, 2018 |
| Lenovo        | ThinkPad W530 2447EJ9       | [4ced3a8a3c](https://linux-hardware.org/?probe=4ced3a8a3c) | Feb 04, 2018 |
| HP            | Notebook                    | [8f94426008](https://linux-hardware.org/?probe=8f94426008) | Dec 21, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [96a6c5cbab](https://linux-hardware.org/?probe=96a6c5cbab) | Dec 17, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [f59b817feb](https://linux-hardware.org/?probe=f59b817feb) | Dec 12, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [06a39a2c60](https://linux-hardware.org/?probe=06a39a2c60) | Dec 12, 2017 |
| Dell          | Precision M4600             | [dbbeb2486e](https://linux-hardware.org/?probe=dbbeb2486e) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [7ee7ca743b](https://linux-hardware.org/?probe=7ee7ca743b) | Dec 03, 2017 |
| Lenovo        | ThinkPad W530 2447EJ9       | [28ae3d12b8](https://linux-hardware.org/?probe=28ae3d12b8) | Dec 03, 2017 |
| ASUSTek       | GL552JX                     | [c3e4792075](https://linux-hardware.org/?probe=c3e4792075) | Dec 10, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Vietnam/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 64        | 12.55%  |
| Ubuntu 22.04                 | 42        | 8.24%   |
| Arch Rolling                 | 37        | 7.25%   |
| Ubuntu 18.04                 | 20        | 3.92%   |
| Ubuntu 24.04                 | 12        | 2.35%   |
| Pop!_OS 22.04                | 12        | 2.35%   |
| Arch                         | 12        | 2.35%   |
| ArcoLinux Rolling            | 11        | 2.16%   |
| Fedora 40                    | 10        | 1.96%   |
| Debian 12                    | 10        | 1.96%   |
| EndeavourOS Rolling          | 8         | 1.57%   |
| Fedora 38                    | 7         | 1.37%   |
| Xero Rolling                 | 6         | 1.18%   |
| Pop!_OS 20.04                | 6         | 1.18%   |
| openSUSE Tumbleweed-XXXXXXXX | 6         | 1.18%   |
| Manjaro                      | 6         | 1.18%   |
| Fedora 37                    | 6         | 1.18%   |
| Ubuntu 23.10                 | 5         | 0.98%   |
| Ubuntu 21.04                 | 5         | 0.98%   |
| Linux Mint 21.2              | 5         | 0.98%   |
| KDE neon 20.04               | 5         | 0.98%   |
| Debian 10                    | 5         | 0.98%   |
| Ubuntu 23.04                 | 4         | 0.78%   |
| Ubuntu 21.10                 | 4         | 0.78%   |
| Ubuntu 19.10                 | 4         | 0.78%   |
| Ubuntu 16.04                 | 4         | 0.78%   |
| Pop!_OS 21.04                | 4         | 0.78%   |
| OpenMandriva 4.2             | 4         | 0.78%   |
| Linux Mint 22                | 4         | 0.78%   |
| Fedora 41                    | 4         | 0.78%   |
| Fedora 39                    | 4         | 0.78%   |
| Fedora 34                    | 4         | 0.78%   |
| Zorin 16                     | 3         | 0.59%   |
| Xubuntu 22.04                | 3         | 0.59%   |
| Ubuntu 22.10                 | 3         | 0.59%   |
| OpenMandriva 4.3             | 3         | 0.59%   |
| OpenMandriva 24.07           | 3         | 0.59%   |
| NixOS 24.05                  | 3         | 0.59%   |
| Manjaro 22.0.0               | 3         | 0.59%   |
| Manjaro 20.2                 | 3         | 0.59%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Ubuntu           | 168       | 34.15%  |
| Arch             | 49        | 9.96%   |
| Fedora           | 40        | 8.13%   |
| Pop!_OS          | 26        | 5.28%   |
| Linux Mint       | 25        | 5.08%   |
| Debian           | 18        | 3.66%   |
| Manjaro          | 17        | 3.46%   |
| OpenMandriva     | 16        | 3.25%   |
| ArcoLinux        | 11        | 2.24%   |
| openSUSE         | 10        | 2.03%   |
| Kubuntu          | 8         | 1.63%   |
| EndeavourOS      | 8         | 1.63%   |
| KDE neon         | 7         | 1.42%   |
| Kali             | 7         | 1.42%   |
| Endless          | 7         | 1.42%   |
| Zorin            | 6         | 1.22%   |
| Xero             | 6         | 1.22%   |
| Xubuntu          | 5         | 1.02%   |
| Ubuntu Unity     | 5         | 1.02%   |
| NixOS            | 5         | 1.02%   |
| Lubuntu          | 5         | 1.02%   |
| Elementary       | 4         | 0.81%   |
| Nobara           | 3         | 0.61%   |
| Garuda Linux     | 3         | 0.61%   |
| Clear Linux      | 3         | 0.61%   |
| Void Linux       | 2         | 0.41%   |
| Ubuntu MATE      | 2         | 0.41%   |
| SteamOS          | 2         | 0.41%   |
| ROSA             | 2         | 0.41%   |
| MX               | 2         | 0.41%   |
| Gentoo           | 2         | 0.41%   |
| ChimeraOS        | 2         | 0.41%   |
| CentOS           | 2         | 0.41%   |
| Artix            | 2         | 0.41%   |
| Ultramarine      | 1         | 0.2%    |
| Solus            | 1         | 0.2%    |
| RHEL             | 1         | 0.2%    |
| Parrot           | 1         | 0.2%    |
| org.kde.Platform | 1         | 0.2%    |
| Nitrux           | 1         | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.8.0-40-generic         | 7         | 1.25%   |
| 5.4.0-42-generic         | 7         | 1.25%   |
| 6.8.0-31-generic         | 5         | 0.9%    |
| 5.4.0-52-generic         | 5         | 0.9%    |
| 5.4.0-48-generic         | 5         | 0.9%    |
| 5.4.0-40-generic         | 5         | 0.9%    |
| 5.4.0-37-generic         | 5         | 0.9%    |
| 5.15.0-56-generic        | 5         | 0.9%    |
| 6.9.3-arch1-1            | 4         | 0.72%   |
| 6.5.0-14-generic         | 4         | 0.72%   |
| 6.2.0-34-generic         | 4         | 0.72%   |
| 5.10.14-desktop-1omv4002 | 4         | 0.72%   |
| 6.9.3-76060903-generic   | 3         | 0.54%   |
| 6.8.0-45-generic         | 3         | 0.54%   |
| 6.5.0-15-generic         | 3         | 0.54%   |
| 6.2.9-300.fc38.x86_64    | 3         | 0.54%   |
| 6.2.0-76060200-generic   | 3         | 0.54%   |
| 6.12.1-arch1-1           | 3         | 0.54%   |
| 5.8.0-55-generic         | 3         | 0.54%   |
| 5.8.0-53-generic         | 3         | 0.54%   |
| 5.8.0-48-generic         | 3         | 0.54%   |
| 5.8.0-43-generic         | 3         | 0.54%   |
| 5.15.0-48-generic        | 3         | 0.54%   |
| 5.11.0-41-generic        | 3         | 0.54%   |
| 5.11.0-37-generic        | 3         | 0.54%   |
| 4.10.0-28-generic        | 3         | 0.54%   |
| 6.9.7-desktop-1omv2490   | 2         | 0.36%   |
| 6.8.6-200.fc39.x86_64    | 2         | 0.36%   |
| 6.8.1-arch1-1            | 2         | 0.36%   |
| 6.8.0-48-generic         | 2         | 0.36%   |
| 6.8.0-39-generic         | 2         | 0.36%   |
| 6.7.4-arch1-1            | 2         | 0.36%   |
| 6.6.2-desktop-1omv2390   | 2         | 0.36%   |
| 6.5.8-arch1-1            | 2         | 0.36%   |
| 6.5.5-arch1-1            | 2         | 0.36%   |
| 6.5.0-35-generic         | 2         | 0.36%   |
| 6.5.0-28-generic         | 2         | 0.36%   |
| 6.5.0-18-generic         | 2         | 0.36%   |
| 6.3.9-chimeraos-1        | 2         | 0.36%   |
| 6.3.5-desktop-3omv2390   | 2         | 0.36%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 51        | 9.64%   |
| 5.15.0  | 41        | 7.75%   |
| 5.8.0   | 24        | 4.54%   |
| 5.11.0  | 21        | 3.97%   |
| 6.8.0   | 19        | 3.59%   |
| 6.5.0   | 18        | 3.4%    |
| 6.2.0   | 16        | 3.02%   |
| 5.19.0  | 13        | 2.46%   |
| 6.1.0   | 12        | 2.27%   |
| 5.13.0  | 12        | 2.27%   |
| 5.3.0   | 11        | 2.08%   |
| 6.9.3   | 8         | 1.51%   |
| 4.15.0  | 8         | 1.51%   |
| 5.10.0  | 7         | 1.32%   |
| 5.0.0   | 7         | 1.32%   |
| 6.2.9   | 6         | 1.13%   |
| 4.18.0  | 6         | 1.13%   |
| 4.19.0  | 5         | 0.95%   |
| 6.5.5   | 4         | 0.76%   |
| 6.3.5   | 4         | 0.76%   |
| 6.11.4  | 4         | 0.76%   |
| 5.10.14 | 4         | 0.76%   |
| 4.10.0  | 4         | 0.76%   |
| 6.9.7   | 3         | 0.57%   |
| 6.7.4   | 3         | 0.57%   |
| 6.6.9   | 3         | 0.57%   |
| 6.5.6   | 3         | 0.57%   |
| 6.4.0   | 3         | 0.57%   |
| 6.3.9   | 3         | 0.57%   |
| 6.12.1  | 3         | 0.57%   |
| 6.11.8  | 3         | 0.57%   |
| 6.10.6  | 3         | 0.57%   |
| 6.0.8   | 3         | 0.57%   |
| 5.16.7  | 3         | 0.57%   |
| 6.8.6   | 2         | 0.38%   |
| 6.8.11  | 2         | 0.38%   |
| 6.8.1   | 2         | 0.38%   |
| 6.7.3   | 2         | 0.38%   |
| 6.6.2   | 2         | 0.38%   |
| 6.5.9   | 2         | 0.38%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 58        | 11.22%  |
| 5.15    | 54        | 10.44%  |
| 6.5     | 32        | 6.19%   |
| 6.8     | 31        | 6%      |
| 6.2     | 31        | 6%      |
| 5.8     | 27        | 5.22%   |
| 6.1     | 26        | 5.03%   |
| 5.11    | 22        | 4.26%   |
| 6.6     | 18        | 3.48%   |
| 5.13    | 18        | 3.48%   |
| 5.19    | 17        | 3.29%   |
| 6.9     | 15        | 2.9%    |
| 5.10    | 15        | 2.9%    |
| 6.4     | 13        | 2.51%   |
| 6.11    | 11        | 2.13%   |
| 5.3     | 11        | 2.13%   |
| 5.0     | 10        | 1.93%   |
| 6.10    | 9         | 1.74%   |
| 6.0     | 9         | 1.74%   |
| 6.7     | 8         | 1.55%   |
| 6.3     | 8         | 1.55%   |
| 5.18    | 8         | 1.55%   |
| 4.15    | 8         | 1.55%   |
| 5.16    | 7         | 1.35%   |
| 5.9     | 6         | 1.16%   |
| 5.14    | 6         | 1.16%   |
| 4.19    | 6         | 1.16%   |
| 4.18    | 6         | 1.16%   |
| 6.12    | 5         | 0.97%   |
| 5.12    | 5         | 0.97%   |
| 4.10    | 4         | 0.77%   |
| 5.7     | 3         | 0.58%   |
| 5.17    | 3         | 0.58%   |
| 5.5     | 2         | 0.39%   |
| 4.13    | 2         | 0.39%   |
| 4.4     | 1         | 0.19%   |
| 4.12    | 1         | 0.19%   |
| 4.1     | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 468       | 99.79%  |
| i686   | 1         | 0.21%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 242       | 48.99%  |
| KDE5             | 70        | 14.17%  |
| Unknown          | 43        | 8.7%    |
| XFCE             | 36        | 7.29%   |
| X-Cinnamon       | 23        | 4.66%   |
| KDE              | 15        | 3.04%   |
| KDE6             | 12        | 2.43%   |
| Hyprland         | 8         | 1.62%   |
| LXQt             | 7         | 1.42%   |
| Unity            | 5         | 1.01%   |
| Pantheon         | 4         | 0.81%   |
| MATE             | 4         | 0.81%   |
| Cinnamon         | 3         | 0.61%   |
| sway             | 2         | 0.4%    |
| Openbox          | 2         | 0.4%    |
| KDE4             | 2         | 0.4%    |
| i3               | 2         | 0.4%    |
| Deepin           | 2         | 0.4%    |
| bspwm            | 2         | 0.4%    |
| X-Generic        | 1         | 0.2%    |
| qtile            | 1         | 0.2%    |
| none+awesome     | 1         | 0.2%    |
| lightdm-xsession | 1         | 0.2%    |
| LeftWM           | 1         | 0.2%    |
| gamescope        | 1         | 0.2%    |
| fluxbox          | 1         | 0.2%    |
| dwm              | 1         | 0.2%    |
| Budgie           | 1         | 0.2%    |
| awesome          | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 320       | 65.17%  |
| Wayland | 137       | 27.9%   |
| Unknown | 24        | 4.89%   |
| Tty     | 10        | 2.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Unknown               | 195       | 39.55%  |
| SDDM                  | 80        | 16.23%  |
| GDM3                  | 74        | 15.01%  |
| GDM                   | 68        | 13.79%  |
| LightDM               | 57        | 11.56%  |
| TDM                   | 10        | 2.03%   |
| XDM                   | 2         | 0.41%   |
| SLiM                  | 2         | 0.41%   |
| GREETD                | 2         | 0.41%   |
| LY-DM                 | 1         | 0.2%    |
| KDM                   | 1         | 0.2%    |
| DISPLAY-MANAGER-START | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 375       | 79.28%  |
| Unknown | 36        | 7.61%   |
| vi_VN   | 25        | 5.29%   |
| C       | 18        | 3.81%   |
| en_GB   | 6         | 1.27%   |
| en_AU   | 4         | 0.85%   |
| ru_RU   | 3         | 0.63%   |
| ko_KR   | 1         | 0.21%   |
| fr_FR   | 1         | 0.21%   |
| es_ES   | 1         | 0.21%   |
| en_CA   | 1         | 0.21%   |
| en_BW   | 1         | 0.21%   |
| de      | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 318       | 65.7%   |
| BIOS | 166       | 34.3%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Notebooks | Percent |
|----------|-----------|---------|
| Ext4     | 346       | 71.93%  |
| Btrfs    | 67        | 13.93%  |
| Overlay  | 25        | 5.2%    |
| Tmpfs    | 20        | 4.16%   |
| Unknown  | 12        | 2.49%   |
| Xfs      | 5         | 1.04%   |
| Zfs      | 3         | 0.62%   |
| Reiserfs | 1         | 0.21%   |
| F2fs     | 1         | 0.21%   |
| Ext3     | 1         | 0.21%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 272       | 56.9%   |
| Unknown | 184       | 38.49%  |
| MBR     | 22        | 4.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 426       | 88.57%  |
| Yes       | 55        | 11.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 278       | 57.56%  |
| Yes       | 205       | 42.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Dell                | 112       | 23.88%  |
| Lenovo              | 100       | 21.32%  |
| ASUSTek Computer    | 70        | 14.93%  |
| Hewlett-Packard     | 65        | 13.86%  |
| Acer                | 36        | 7.68%   |
| MSI                 | 19        | 4.05%   |
| Apple               | 14        | 2.99%   |
| HUAWEI              | 7         | 1.49%   |
| Sony                | 6         | 1.28%   |
| Toshiba             | 5         | 1.07%   |
| Samsung Electronics | 5         | 1.07%   |
| Google              | 4         | 0.85%   |
| Chuwi               | 4         | 0.85%   |
| Gigabyte Technology | 3         | 0.64%   |
| Timi                | 2         | 0.43%   |
| OrangePi            | 2         | 0.43%   |
| MASSCOM VIETNAM     | 2         | 0.43%   |
| Alienware           | 2         | 0.43%   |
| Valve               | 1         | 0.21%   |
| TENKU               | 1         | 0.21%   |
| Panasonic           | 1         | 0.21%   |
| LG Electronics      | 1         | 0.21%   |
| Koompi              | 1         | 0.21%   |
| Jumper              | 1         | 0.21%   |
| itel Mobile Limited | 1         | 0.21%   |
| Gateway             | 1         | 0.21%   |
| COM1                | 1         | 0.21%   |
| Anbernic            | 1         | 0.21%   |
| AMI                 | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo ThinkPad E14 20RAS0KX00           | 4         | 0.85%   |
| Lenovo Legion 5 15ARH05 82B5             | 4         | 0.85%   |
| Dell Vostro 3578                         | 4         | 0.85%   |
| Dell Inspiron 3537                       | 4         | 0.85%   |
| Apple MacBookPro12,1                     | 4         | 0.85%   |
| Unknown                                  | 4         | 0.85%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2      | 3         | 0.64%   |
| HUAWEI BOM-WXX9                          | 3         | 0.64%   |
| HP Notebook                              | 3         | 0.64%   |
| Dell Vostro 15-3568                      | 3         | 0.64%   |
| ASUS X411UA                              | 3         | 0.64%   |
| Acer Nitro AN515-57                      | 3         | 0.64%   |
| Toshiba Satellite L840                   | 2         | 0.43%   |
| OrangePi NEO-01                          | 2         | 0.43%   |
| MSI Modern 15 A5M                        | 2         | 0.43%   |
| MSI Modern 14 B5M                        | 2         | 0.43%   |
| MSI GF63 8RD                             | 2         | 0.43%   |
| MASSCOM VIETNAM L133                     | 2         | 0.43%   |
| Lenovo Yoga 14sACH 2021 82MS             | 2         | 0.43%   |
| Lenovo ThinkPad W530 2447EJ9             | 2         | 0.43%   |
| Lenovo ThinkBook 14 G4+ ARA 21D0         | 2         | 0.43%   |
| Lenovo Legion 5 15ACH6H 82JU             | 2         | 0.43%   |
| Lenovo IdeaPad Gaming 3 15IMH05 81Y4     | 2         | 0.43%   |
| Lenovo IdeaPad 5 15ITL05 82FG            | 2         | 0.43%   |
| Lenovo IdeaPad 5 14ITL05 82FE            | 2         | 0.43%   |
| HUAWEI KLVL-WXXW                         | 2         | 0.43%   |
| HP Victus by Laptop 16-e0xxx             | 2         | 0.43%   |
| HP ProBook 450 G1                        | 2         | 0.43%   |
| HP ProBook 440 G7                        | 2         | 0.43%   |
| HP Laptop 15s-du1xxx                     | 2         | 0.43%   |
| HP Laptop 14-bs0xx                       | 2         | 0.43%   |
| HP EliteBook 8470p                       | 2         | 0.43%   |
| HP EliteBook 845 14 inch G10 Notebook PC | 2         | 0.43%   |
| HP EliteBook 840 G2                      | 2         | 0.43%   |
| HP EliteBook 2560p                       | 2         | 0.43%   |
| HP 15                                    | 2         | 0.43%   |
| Dell XPS 15 9570                         | 2         | 0.43%   |
| Dell Vostro 5568                         | 2         | 0.43%   |
| Dell Vostro 3590                         | 2         | 0.43%   |
| Dell Vostro 3478                         | 2         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 48        | 10.23%  |
| Dell Latitude        | 30        | 6.4%    |
| Dell Inspiron        | 27        | 5.76%   |
| Dell Vostro          | 23        | 4.9%    |
| Lenovo IdeaPad       | 21        | 4.48%   |
| Acer Aspire          | 20        | 4.26%   |
| HP EliteBook         | 18        | 3.84%   |
| ASUS ROG             | 15        | 3.2%    |
| ASUS VivoBook        | 14        | 2.99%   |
| Lenovo Legion        | 12        | 2.56%   |
| Dell Precision       | 12        | 2.56%   |
| ASUS ASUS            | 11        | 2.35%   |
| HP ProBook           | 10        | 2.13%   |
| Acer Nitro           | 10        | 2.13%   |
| Lenovo ThinkBook     | 9         | 1.92%   |
| HP Laptop            | 8         | 1.71%   |
| Dell XPS             | 7         | 1.49%   |
| MSI Modern           | 5         | 1.07%   |
| HP ZBook             | 5         | 1.07%   |
| HP Pavilion          | 5         | 1.07%   |
| Dell System          | 5         | 1.07%   |
| MSI GF63             | 4         | 0.85%   |
| Dell G3              | 4         | 0.85%   |
| Apple MacBookPro12   | 4         | 0.85%   |
| Unknown              | 4         | 0.85%   |
| Toshiba Satellite    | 3         | 0.64%   |
| HUAWEI BOM-WXX9      | 3         | 0.64%   |
| HP Notebook          | 3         | 0.64%   |
| HP Compaq            | 3         | 0.64%   |
| ASUS X411UA          | 3         | 0.64%   |
| ASUS TUF             | 3         | 0.64%   |
| Apple MacBookPro11   | 3         | 0.64%   |
| Acer Swift           | 3         | 0.64%   |
| Acer Predator        | 3         | 0.64%   |
| OrangePi NEO-01      | 2         | 0.43%   |
| MASSCOM VIETNAM L133 | 2         | 0.43%   |
| Lenovo Yoga          | 2         | 0.43%   |
| HUAWEI KLVL-WXXW     | 2         | 0.43%   |
| HP Victus            | 2         | 0.43%   |
| HP 245               | 2         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 61        | 13.01%  |
| 2018 | 54        | 11.51%  |
| 2020 | 51        | 10.87%  |
| 2019 | 36        | 7.68%   |
| 2012 | 32        | 6.82%   |
| 2022 | 29        | 6.18%   |
| 2017 | 28        | 5.97%   |
| 2015 | 27        | 5.76%   |
| 2013 | 27        | 5.76%   |
| 2023 | 25        | 5.33%   |
| 2016 | 25        | 5.33%   |
| 2011 | 24        | 5.12%   |
| 2014 | 21        | 4.48%   |
| 2009 | 8         | 1.71%   |
| 2024 | 6         | 1.28%   |
| 2010 | 6         | 1.28%   |
| 2008 | 6         | 1.28%   |
| 2007 | 3         | 0.64%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 469       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 429       | 90.32%  |
| Enabled  | 46        | 9.68%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 465       | 99.15%  |
| Yes  | 4         | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 135       | 28.36%  |
| 16.01-24.0  | 108       | 22.69%  |
| 8.01-16.0   | 92        | 19.33%  |
| 3.01-4.0    | 61        | 12.82%  |
| 32.01-64.0  | 45        | 9.45%   |
| 24.01-32.0  | 19        | 3.99%   |
| 1.01-2.0    | 10        | 2.1%    |
| 2.01-3.0    | 4         | 0.84%   |
| 64.01-256.0 | 1         | 0.21%   |
| 0.51-1.0    | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 169       | 32.5%   |
| 4.01-8.0   | 121       | 23.27%  |
| 1.01-2.0   | 97        | 18.65%  |
| 3.01-4.0   | 88        | 16.92%  |
| 8.01-16.0  | 31        | 5.96%   |
| 0.51-1.0   | 10        | 1.92%   |
| 16.01-24.0 | 3         | 0.58%   |
| 0.01-0.5   | 1         | 0.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 322       | 67.22%  |
| 2      | 136       | 28.39%  |
| 3      | 18        | 3.76%   |
| 4      | 2         | 0.42%   |
| 0      | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 393       | 83.62%  |
| Yes       | 77        | 16.38%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 369       | 77.68%  |
| No        | 106       | 22.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 466       | 99.36%  |
| No        | 3         | 0.64%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 420       | 89.17%  |
| No        | 51        | 10.83%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Vietnam | 469       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Ho Chi Minh City  | 207       | 41.73%  |
| Hanoi             | 164       | 33.06%  |
| Da Nang           | 17        | 3.43%   |
| Bien Hoa          | 8         | 1.61%   |
| Can Tho           | 7         | 1.41%   |
| Nha Trang         | 5         | 1.01%   |
| Đông Hà        | 4         | 0.81%   |
| Huế             | 4         | 0.81%   |
| Vũng Tàu        | 3         | 0.6%    |
| Vinh              | 3         | 0.6%    |
| Thuan An          | 3         | 0.6%    |
| Thai Nguyen       | 3         | 0.6%    |
| Tay Ninh          | 3         | 0.6%    |
| Nam Định       | 3         | 0.6%    |
| Buon Ma Thuot     | 3         | 0.6%    |
| Bến Tre         | 3         | 0.6%    |
| Bac Giang         | 3         | 0.6%    |
| Vinh Phuc         | 2         | 0.4%    |
| Viet Tri          | 2         | 0.4%    |
| Thu Duc           | 2         | 0.4%    |
| Thon Dien Ha      | 2         | 0.4%    |
| Thanh Hóa        | 2         | 0.4%    |
| Quảng Ngai      | 2         | 0.4%    |
| Dien Ban          | 2         | 0.4%    |
| Binh Hoa          | 2         | 0.4%    |
| Bao Loc           | 2         | 0.4%    |
| Xom My Tho        | 1         | 0.2%    |
| Vinh Yen          | 1         | 0.2%    |
| Tra Vinh          | 1         | 0.2%    |
| Tinh Quang Binh   | 1         | 0.2%    |
| Tinh GJong Nai    | 1         | 0.2%    |
| Tinh Binh Duong   | 1         | 0.2%    |
| Thai Binh         | 1         | 0.2%    |
| Tan An            | 1         | 0.2%    |
| Qui Nhon          | 1         | 0.2%    |
| Quang Trung       | 1         | 0.2%    |
| Quan Muoi Mot     | 1         | 0.2%    |
| Quan Muoi         | 1         | 0.2%    |
| Quận Hà Đông | 1         | 0.2%    |
| Quan Binh Thanh   | 1         | 0.2%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 104       | 133    | 16.3%   |
| WDC                         | 62        | 75     | 9.72%   |
| SK hynix                    | 46        | 55     | 7.21%   |
| Toshiba                     | 41        | 50     | 6.43%   |
| Seagate                     | 41        | 47     | 6.43%   |
| Micron Technology           | 38        | 43     | 5.96%   |
| Kingston                    | 29        | 43     | 4.55%   |
| Intel                       | 29        | 32     | 4.55%   |
| SanDisk                     | 28        | 37     | 4.39%   |
| HGST                        | 25        | 27     | 3.92%   |
| Unknown                     | 23        | 27     | 3.61%   |
| Crucial                     | 13        | 13     | 2.04%   |
| KIOXIA                      | 11        | 14     | 1.72%   |
| Hitachi                     | 11        | 15     | 1.72%   |
| Apple                       | 11        | 14     | 1.72%   |
| Plextor                     | 9         | 9      | 1.41%   |
| OSCOO                       | 6         | 7      | 0.94%   |
| MAXIO Technology (Hangzhou) | 6         | 6      | 0.94%   |
| KingSpec                    | 6         | 9      | 0.94%   |
| Transcend                   | 4         | 6      | 0.63%   |
| TO Exter                    | 4         | 6      | 0.63%   |
| LITEON                      | 4         | 4      | 0.63%   |
| Lexar                       | 4         | 4      | 0.63%   |
| Kingston Technology Company | 4         | 6      | 0.63%   |
| Kingmax                     | 4         | 4      | 0.63%   |
| China                       | 4         | 4      | 0.63%   |
| SPCC                        | 3         | 3      | 0.47%   |
| Silicon Motion              | 3         | 5      | 0.47%   |
| Phison Electronics          | 3         | 3      | 0.47%   |
| FORESEE                     | 3         | 3      | 0.47%   |
| Colorful                    | 3         | 3      | 0.47%   |
| UMIS                        | 2         | 2      | 0.31%   |
| Phison                      | 2         | 2      | 0.31%   |
| Netac                       | 2         | 3      | 0.31%   |
| KingFast                    | 2         | 2      | 0.31%   |
| KingDian                    | 2         | 3      | 0.31%   |
| Hikvision                   | 2         | 2      | 0.31%   |
| Gigabyte Technology         | 2         | 2      | 0.31%   |
| Apacer                      | 2         | 2      | 0.31%   |
| WDC PC S                    | 1         | 1      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB  | 12        | 1.83%   |
| HGST HTS721010A9E630 1TB                             | 11        | 1.67%   |
| Seagate ST1000LM035-1RK172 1TB                       | 10        | 1.52%   |
| Toshiba MQ01ABF050 500GB                             | 7         | 1.07%   |
| Samsung MZALQ512HALU-000L2 512GB                     | 7         | 1.07%   |
| Crucial CT240BX500SSD1 240GB                         | 7         | 1.07%   |
| Toshiba MQ04ABF100 1TB                               | 6         | 0.91%   |
| Samsung MZALQ512HBLU-00BL2 512GB                     | 6         | 0.91%   |
| Kingston OM8PCP3512F-AI1 512GB                       | 6         | 0.91%   |
| Intel SSDPEKNU512GZ 512GB                            | 6         | 0.91%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                     | 5         | 0.76%   |
| Unknown MMC Card  32GB                               | 5         | 0.76%   |
| Samsung NVMe SSD Drive 512GB                         | 5         | 0.76%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 512GB | 5         | 0.76%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB   | 5         | 0.76%   |
| Toshiba MQ01ABD100 1TB                               | 4         | 0.61%   |
| TO Exter nal USB 3.0 1024GB                          | 4         | 0.61%   |
| SK hynix NVMe SSD Drive 256GB                        | 4         | 0.61%   |
| Seagate ST9500325AS 500GB                            | 4         | 0.61%   |
| Seagate ST500LT012-1DG142 500GB                      | 4         | 0.61%   |
| Seagate ST1000LM049-2GH172 1TB                       | 4         | 0.61%   |
| Samsung SSD 980 1TB                                  | 4         | 0.61%   |
| Samsung SSD 870 EVO 500GB                            | 4         | 0.61%   |
| Samsung SSD 860 EVO 500GB                            | 4         | 0.61%   |
| Samsung SSD 860 EVO 250GB                            | 4         | 0.61%   |
| Micron 2450_MTFDKBA512TFK 512GB                      | 4         | 0.61%   |
| Micron 2400_MTFDKBA512QFM 512GB                      | 4         | 0.61%   |
| Micron 2210_MTFDHBA512QFD 512GB                      | 4         | 0.61%   |
| Kingston SA400S37480G 480GB SSD                      | 4         | 0.61%   |
| Kingston SA400S37120G 120GB SSD                      | 4         | 0.61%   |
| HGST HTS545050A7E680 500GB                           | 4         | 0.61%   |
| WDC WD5000LPLX-08ZNTT0 500GB                         | 3         | 0.46%   |
| WDC WD10SPZX-21Z10T0 1TB                             | 3         | 0.46%   |
| WDC WD10JPVX-75JC3T0 1TB                             | 3         | 0.46%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB            | 3         | 0.46%   |
| SK hynix NVMe SSD Drive 512GB                        | 3         | 0.46%   |
| SK hynix BC511 NVMe 512GB                            | 3         | 0.46%   |
| SK hynix BC501 NVMe Solid State Drive 512GB          | 3         | 0.46%   |
| Seagate ST500LT012-9WS142 500GB                      | 3         | 0.46%   |
| Samsung SSD 980 500GB                                | 3         | 0.46%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 41        | 47     | 28.08%  |
| WDC      | 37        | 47     | 25.34%  |
| Toshiba  | 26        | 29     | 17.81%  |
| HGST     | 25        | 27     | 17.12%  |
| Hitachi  | 11        | 15     | 7.53%   |
| TO Exter | 4         | 6      | 2.74%   |
| Fujitsu  | 1         | 2      | 0.68%   |
| External | 1         | 1      | 0.68%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 34     | 14.29%  |
| Kingston            | 14        | 24     | 7.41%   |
| SanDisk             | 13        | 18     | 6.88%   |
| Crucial             | 13        | 13     | 6.88%   |
| WDC                 | 11        | 11     | 5.82%   |
| Plextor             | 9         | 9      | 4.76%   |
| Apple               | 9         | 12     | 4.76%   |
| Intel               | 8         | 9      | 4.23%   |
| KingSpec            | 6         | 9      | 3.17%   |
| SK hynix            | 5         | 5      | 2.65%   |
| OSCOO               | 5         | 5      | 2.65%   |
| Transcend           | 4         | 6      | 2.12%   |
| Toshiba             | 4         | 6      | 2.12%   |
| Micron Technology   | 4         | 4      | 2.12%   |
| LITEON              | 4         | 4      | 2.12%   |
| Lexar               | 4         | 4      | 2.12%   |
| Kingmax             | 4         | 4      | 2.12%   |
| China               | 4         | 4      | 2.12%   |
| SPCC                | 3         | 3      | 1.59%   |
| FORESEE             | 3         | 3      | 1.59%   |
| Colorful            | 3         | 3      | 1.59%   |
| Netac               | 2         | 3      | 1.06%   |
| KingDian            | 2         | 3      | 1.06%   |
| Hikvision           | 2         | 2      | 1.06%   |
| Apacer              | 2         | 2      | 1.06%   |
| W800S               | 1         | 1      | 0.53%   |
| VSP-128G            | 1         | 1      | 0.53%   |
| Unknown             | 1         | 1      | 0.53%   |
| Team                | 1         | 1      | 0.53%   |
| SD                  | 1         | 1      | 0.53%   |
| SAM                 | 1         | 1      | 0.53%   |
| S100                | 1         | 1      | 0.53%   |
| OSC                 | 1         | 1      | 0.53%   |
| NGFF                | 1         | 1      | 0.53%   |
| Maxtor              | 1         | 3      | 0.53%   |
| LITEONIT            | 1         | 1      | 0.53%   |
| KLEVV               | 1         | 1      | 0.53%   |
| KIOXIA-EXCERIA      | 1         | 2      | 0.53%   |
| KingFast            | 1         | 1      | 0.53%   |
| KimMiDi             | 1         | 1      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 253       | 340    | 42.88%  |
| SSD     | 171       | 228    | 28.98%  |
| HDD     | 138       | 174    | 23.39%  |
| MMC     | 20        | 24     | 3.39%   |
| Unknown | 8         | 8      | 1.36%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 254       | 392    | 46.78%  |
| NVMe | 253       | 339    | 46.59%  |
| MMC  | 20        | 24     | 3.68%   |
| SAS  | 16        | 19     | 2.95%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 217       | 308    | 73.56%  |
| 0.51-1.0   | 71        | 84     | 24.07%  |
| 1.01-2.0   | 7         | 10     | 2.37%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 165       | 32.74%  |
| 251-500        | 140       | 27.78%  |
| 501-1000       | 51        | 10.12%  |
| 51-100         | 41        | 8.13%   |
| 1001-2000      | 27        | 5.36%   |
| 1-20           | 25        | 4.96%   |
| 21-50          | 22        | 4.37%   |
| Unknown        | 15        | 2.98%   |
| 2001-3000      | 11        | 2.18%   |
| More than 3000 | 7         | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 189       | 37.06%  |
| 21-50          | 104       | 20.39%  |
| 101-250        | 72        | 14.12%  |
| 51-100         | 66        | 12.94%  |
| 251-500        | 38        | 7.45%   |
| 501-1000       | 17        | 3.33%   |
| Unknown        | 15        | 2.94%   |
| 1001-2000      | 6         | 1.18%   |
| 2001-3000      | 2         | 0.39%   |
| More than 3000 | 1         | 0.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD             | 2         | 2      | 5.26%   |
| Seagate ST9320325AS 320GB                    | 2         | 3      | 5.26%   |
| Seagate ST1000LM035-1RK172 1TB               | 2         | 2      | 5.26%   |
| HGST HTS545050A7E680 500GB                   | 2         | 3      | 5.26%   |
| WDC WD5000LPVX-22V0TT0 500GB                 | 1         | 1      | 2.63%   |
| WDC WD5000LPLX-60ZNTT1 500GB                 | 1         | 1      | 2.63%   |
| WDC WD5000LPCX-24VHAT0 500GB                 | 1         | 1      | 2.63%   |
| WDC WD32 00BEVT-24A23 320GB                  | 1         | 1      | 2.63%   |
| WDC WD2500BEVT-75ZCT2 250GB                  | 1         | 1      | 2.63%   |
| WDC WD10JPVX-75JC3T0 1TB                     | 1         | 1      | 2.63%   |
| Unknown Bamba-240GB SSD                      | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD050 500GB                     | 1         | 1      | 2.63%   |
| Toshiba MK8046GSX 80GB                       | 1         | 1      | 2.63%   |
| Toshiba MK3265GSXN 320GB                     | 1         | 1      | 2.63%   |
| Toshiba HDWK105 500GB                        | 1         | 1      | 2.63%   |
| SPCC Solid State Disk 128GB                  | 1         | 1      | 2.63%   |
| SK hynix HFS032G34MNC-2200A 32GB SSD         | 1         | 1      | 2.63%   |
| SK hynix BC711 HFM256GD3JX013N 256GB         | 1         | 1      | 2.63%   |
| Seagate ST9640423AS 640GB                    | 1         | 1      | 2.63%   |
| Seagate ST9320320AS 320GB                    | 1         | 1      | 2.63%   |
| Seagate ST500LM021-1KJ152 500GB              | 1         | 1      | 2.63%   |
| Samsung Electronics MZVPW128HEGM-00000 128GB | 1         | 1      | 2.63%   |
| LITEON LCH-256V2S 256GB SSD                  | 1         | 1      | 2.63%   |
| Kingmax SSD 120GB                            | 1         | 1      | 2.63%   |
| KingFast SSD 32GB                            | 1         | 1      | 2.63%   |
| Hitachi HTS725050A7E635 500GB                | 1         | 1      | 2.63%   |
| Hitachi HTS545050A7E380 500GB                | 1         | 1      | 2.63%   |
| Hitachi HTS543232A7A384 320GB                | 1         | 1      | 2.63%   |
| HGST HTS725050A7E630 500GB                   | 1         | 1      | 2.63%   |
| HGST HTS725032A7E630 320GB                   | 1         | 1      | 2.63%   |
| HGST HTS721010A9E630 1TB                     | 1         | 1      | 2.63%   |
| HGST HTS545050A7 500GB                       | 1         | 1      | 2.63%   |
| HGST HTS541010A7E630 1TB                     | 1         | 1      | 2.63%   |
| Crucial CT525MX300SSD1 528GB                 | 1         | 1      | 2.63%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 8         | 8      | 21.05%  |
| Seagate             | 7         | 8      | 18.42%  |
| HGST                | 7         | 8      | 18.42%  |
| Toshiba             | 4         | 4      | 10.53%  |
| Hitachi             | 3         | 3      | 7.89%   |
| SK hynix            | 2         | 2      | 5.26%   |
| Unknown             | 1         | 1      | 2.63%   |
| SPCC                | 1         | 1      | 2.63%   |
| Samsung Electronics | 1         | 1      | 2.63%   |
| LITEON              | 1         | 1      | 2.63%   |
| Kingmax             | 1         | 1      | 2.63%   |
| KingFast            | 1         | 1      | 2.63%   |
| Crucial             | 1         | 1      | 2.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 8      | 25.93%  |
| HGST    | 7         | 8      | 25.93%  |
| WDC     | 6         | 6      | 22.22%  |
| Toshiba | 4         | 4      | 14.81%  |
| Hitachi | 3         | 3      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 27        | 29     | 71.05%  |
| SSD  | 9         | 9      | 23.68%  |
| NVMe | 2         | 2      | 5.26%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                    | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 243       | 365    | 46.55%  |
| Detected | 241       | 368    | 46.17%  |
| Malfunc  | 37        | 40     | 7.09%   |
| Failed   | 1         | 1      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 325       | 52.33%  |
| Samsung Electronics            | 88        | 14.17%  |
| SK hynix                       | 41        | 6.6%    |
| Micron Technology              | 34        | 5.48%   |
| AMD                            | 33        | 5.31%   |
| SanDisk                        | 27        | 4.35%   |
| Kingston Technology Company    | 18        | 2.9%    |
| KIOXIA                         | 12        | 1.93%   |
| Toshiba America Info Systems   | 11        | 1.77%   |
| Phison Electronics             | 7         | 1.13%   |
| MAXIO Technology (Hangzhou)    | 7         | 1.13%   |
| Solid State Storage Technology | 4         | 0.64%   |
| Silicon Motion                 | 4         | 0.64%   |
| Union Memory (Shenzhen)        | 2         | 0.32%   |
| Marvell Technology Group       | 2         | 0.32%   |
| ADATA Technology               | 2         | 0.32%   |
| Realtek Semiconductor          | 1         | 0.16%   |
| O2 Micro                       | 1         | 0.16%   |
| Lite-On Technology             | 1         | 0.16%   |
| Lenovo                         | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 42        | 6.45%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 38        | 5.84%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 33        | 5.07%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 32        | 4.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 29        | 4.45%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 24        | 3.69%   |
| Intel Volume Management Device NVMe RAID Controller                            | 20        | 3.07%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 19        | 2.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 18        | 2.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 18        | 2.76%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 18        | 2.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 15        | 2.3%    |
| Intel Comet Lake SATA AHCI Controller                                          | 13        | 2%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 12        | 1.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 1.69%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 11        | 1.69%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 10        | 1.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 10        | 1.54%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 9         | 1.38%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 1.38%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 9         | 1.38%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 9         | 1.38%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 8         | 1.23%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 1.23%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 8         | 1.23%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 7         | 1.08%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 7         | 1.08%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 7         | 1.08%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 7         | 1.08%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 1.08%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 6         | 0.92%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                     | 6         | 0.92%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 6         | 0.92%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 6         | 0.92%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 6         | 0.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 0.92%   |
| SK hynix BC511 NVMe SSD                                                        | 5         | 0.77%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 5         | 0.77%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 5         | 0.77%   |
| Intel SSD 660P Series                                                          | 5         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 310       | 49.84%  |
| NVMe | 254       | 40.84%  |
| RAID | 52        | 8.36%   |
| IDE  | 6         | 0.96%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 382       | 81.45%  |
| AMD    | 87        | 18.55%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 19        | 4.05%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 2.77%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 2.13%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 2.13%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 9         | 1.92%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 1.92%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 9         | 1.92%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 1.71%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 1.71%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 7         | 1.49%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 1.49%   |
| Intel 12th Gen Core i7-12700H                 | 7         | 1.49%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 7         | 1.49%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 1.28%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 6         | 1.28%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 6         | 1.28%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 6         | 1.28%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 6         | 1.28%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 5         | 1.07%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 5         | 1.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 5         | 1.07%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 5         | 1.07%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 5         | 1.07%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 5         | 1.07%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 1.07%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 0.85%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 4         | 0.85%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.85%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.85%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 4         | 0.85%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.85%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 4         | 0.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 4         | 0.85%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 0.64%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 3         | 0.64%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 3         | 0.64%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.64%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.64%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 0.64%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 145       | 30.92%  |
| Intel Core i7    | 93        | 19.83%  |
| Other            | 64        | 13.65%  |
| Intel Core i3    | 38        | 8.1%    |
| AMD Ryzen 7      | 37        | 7.89%   |
| AMD Ryzen 5      | 34        | 7.25%   |
| Intel Celeron    | 16        | 3.41%   |
| Intel Core 2 Duo | 9         | 1.92%   |
| Intel Atom       | 4         | 0.85%   |
| AMD Ryzen 7 PRO  | 4         | 0.85%   |
| AMD Ryzen 3      | 4         | 0.85%   |
| Intel Pentium    | 3         | 0.64%   |
| Intel Genuine    | 3         | 0.64%   |
| AMD Ryzen 9      | 3         | 0.64%   |
| Intel Xeon       | 2         | 0.43%   |
| Intel Core i9    | 2         | 0.43%   |
| Intel Core       | 2         | 0.43%   |
| AMD Ryzen 5 PRO  | 2         | 0.43%   |
| Intel Core m7    | 1         | 0.21%   |
| Intel Core M     | 1         | 0.21%   |
| AMD Athlon       | 1         | 0.21%   |
| AMD A8           | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 175       | 37.31%  |
| 4      | 151       | 32.2%   |
| 6      | 59        | 12.58%  |
| 8      | 52        | 11.09%  |
| 14     | 10        | 2.13%   |
| 12     | 8         | 1.71%   |
| 10     | 7         | 1.49%   |
| 1      | 3         | 0.64%   |
| 16     | 2         | 0.43%   |
| 24     | 1         | 0.21%   |
| 11     | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 468       | 99.79%  |
| 11     | 1         | 0.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 421       | 89.38%  |
| 1      | 50        | 10.62%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 465       | 98.94%  |
| Unknown        | 5         | 1.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 211       | 43.15%  |
| 0x306a9    | 26        | 5.32%   |
| 0x806ea    | 25        | 5.11%   |
| 0x806ec    | 17        | 3.48%   |
| 0x40651    | 17        | 3.48%   |
| 0x806c1    | 16        | 3.27%   |
| 0x206a7    | 15        | 3.07%   |
| 0x306d4    | 13        | 2.66%   |
| 0x806e9    | 12        | 2.45%   |
| 0x906ea    | 9         | 1.84%   |
| 0x08600106 | 9         | 1.84%   |
| 0x406e3    | 8         | 1.64%   |
| 0x08608103 | 8         | 1.64%   |
| 0x906e9    | 7         | 1.43%   |
| 0x306c3    | 7         | 1.43%   |
| 0x506e3    | 6         | 1.23%   |
| 0x0a50000c | 6         | 1.23%   |
| 0xa0652    | 5         | 1.02%   |
| 0x906a3    | 5         | 1.02%   |
| 0x806d1    | 5         | 1.02%   |
| 0x0a404102 | 5         | 1.02%   |
| 0x6fd      | 4         | 0.82%   |
| 0x1067a    | 4         | 0.82%   |
| 0x0a50000d | 4         | 0.82%   |
| 0x08600104 | 4         | 0.82%   |
| 0x08108102 | 4         | 0.82%   |
| 0x706e5    | 3         | 0.61%   |
| 0x20655    | 3         | 0.61%   |
| 0x08600103 | 3         | 0.61%   |
| 0x906ed    | 2         | 0.41%   |
| 0x906c0    | 2         | 0.41%   |
| 0x706a1    | 2         | 0.41%   |
| 0x406c4    | 2         | 0.41%   |
| 0x40661    | 2         | 0.41%   |
| 0x0a705203 | 2         | 0.41%   |
| 0x08108109 | 2         | 0.41%   |
| 0xb06a3    | 1         | 0.2%    |
| 0x806eb    | 1         | 0.2%    |
| 0x806c2    | 1         | 0.2%    |
| 0x406c3    | 1         | 0.2%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 112       | 23.88%  |
| Unknown           | 45        | 9.59%   |
| IvyBridge         | 39        | 8.32%   |
| Haswell           | 37        | 7.89%   |
| Skylake           | 27        | 5.76%   |
| TigerLake         | 25        | 5.33%   |
| Broadwell         | 24        | 5.12%   |
| Zen 3             | 23        | 4.9%    |
| Zen 2             | 22        | 4.69%   |
| SandyBridge       | 22        | 4.69%   |
| Alderlake Hybrid  | 20        | 4.26%   |
| Icelake           | 13        | 2.77%   |
| CometLake         | 11        | 2.35%   |
| Zen+              | 8         | 1.71%   |
| Silvermont        | 6         | 1.28%   |
| Penryn            | 6         | 1.28%   |
| Goldmont plus     | 6         | 1.28%   |
| Core              | 6         | 1.28%   |
| Westmere          | 5         | 1.07%   |
| Zen               | 2         | 0.43%   |
| Tremont           | 2         | 0.43%   |
| Meteorlake Hybrid | 2         | 0.43%   |
| Goldmont          | 2         | 0.43%   |
| Bonnell           | 2         | 0.43%   |
| Puma              | 1         | 0.21%   |
| Nehalem           | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 365       | 56.41%  |
| Nvidia | 169       | 26.12%  |
| AMD    | 113       | 17.47%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 37        | 5.67%   |
| Intel UHD Graphics 620                                                                   | 32        | 4.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 23        | 3.52%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 23        | 3.52%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 21        | 3.22%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 21        | 3.22%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 3.06%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 19        | 2.91%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 18        | 2.76%   |
| Intel HD Graphics 5500                                                                   | 18        | 2.76%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 16        | 2.45%   |
| Intel HD Graphics 620                                                                    | 16        | 2.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 2.45%   |
| AMD Lucienne                                                                             | 14        | 2.14%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 1.99%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 11        | 1.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 11        | 1.68%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 11        | 1.68%   |
| Intel HD Graphics 530                                                                    | 10        | 1.53%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 9         | 1.38%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 1.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 1.38%   |
| Intel HD Graphics 630                                                                    | 9         | 1.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 1.38%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 8         | 1.23%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 8         | 1.23%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 8         | 1.23%   |
| AMD Rembrandt [Radeon 680M]                                                              | 7         | 1.07%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 6         | 0.92%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 6         | 0.92%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.92%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]                         | 6         | 0.92%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 5         | 0.77%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 0.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 5         | 0.77%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.61%   |
| Intel Iris Graphics 6100                                                                 | 4         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 218       | 46.48%  |
| Intel + Nvidia | 121       | 25.8%   |
| 1 x AMD        | 53        | 11.3%   |
| AMD + Nvidia   | 31        | 6.61%   |
| Intel + AMD    | 25        | 5.33%   |
| 1 x Nvidia     | 16        | 3.41%   |
| 2 x AMD        | 4         | 0.85%   |
| Other          | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 354       | 74.21%  |
| Proprietary | 113       | 23.69%  |
| Unknown     | 10        | 2.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 329       | 67.98%  |
| 1.01-2.0   | 49        | 10.12%  |
| 3.01-4.0   | 40        | 8.26%   |
| 0.01-0.5   | 38        | 7.85%   |
| 0.51-1.0   | 17        | 3.51%   |
| 5.01-6.0   | 6         | 1.24%   |
| 7.01-8.0   | 2         | 0.41%   |
| 2.01-3.0   | 2         | 0.41%   |
| 8.01-16.0  | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 105       | 19.59%  |
| Chimei Innolux          | 88        | 16.42%  |
| AU Optronics            | 85        | 15.86%  |
| LG Display              | 60        | 11.19%  |
| Samsung Electronics     | 44        | 8.21%   |
| Dell                    | 23        | 4.29%   |
| PANDA                   | 17        | 3.17%   |
| Sharp                   | 13        | 2.43%   |
| Goldstar                | 13        | 2.43%   |
| Apple                   | 13        | 2.43%   |
| Lenovo                  | 7         | 1.31%   |
| InfoVision              | 7         | 1.31%   |
| Chi Mei Optoelectronics | 7         | 1.31%   |
| ViewSonic               | 6         | 1.12%   |
| CSO                     | 6         | 1.12%   |
| LGD                     | 5         | 0.93%   |
| TMX                     | 4         | 0.75%   |
| RTK                     | 4         | 0.75%   |
| ASUSTek Computer        | 4         | 0.75%   |
| Mi                      | 3         | 0.56%   |
| HKC                     | 3         | 0.56%   |
| Hewlett-Packard         | 3         | 0.56%   |
| AOC                     | 2         | 0.37%   |
| XYM                     | 1         | 0.19%   |
| VIE                     | 1         | 0.19%   |
| Valve                   | 1         | 0.19%   |
| Unknown (XXX)           | 1         | 0.19%   |
| TMK                     | 1         | 0.19%   |
| Sony                    | 1         | 0.19%   |
| SKG                     | 1         | 0.19%   |
| Philips                 | 1         | 0.19%   |
| OPI                     | 1         | 0.19%   |
| MStar                   | 1         | 0.19%   |
| LG Philips              | 1         | 0.19%   |
| InnoLux Display         | 1         | 0.19%   |
| HKD                     | 1         | 0.19%   |
| BenQ                    | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 10        | 1.86%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 8         | 1.48%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 1.3%    |
| LGD LCD Monitor 1920x1080                                             | 5         | 0.93%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 5         | 0.93%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 4         | 0.74%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                  | 4         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.74%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 4         | 0.74%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 4         | 0.74%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 4         | 0.74%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.74%   |
| TMX TL140BDXP01-0 TMX1400 2560x1440 310x174mm 14.0-inch               | 3         | 0.56%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 3         | 0.56%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 3         | 0.56%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.56%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch          | 3         | 0.56%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 3         | 0.56%   |
| Chimei Innolux P140ZKA-BZ1 CMN8C02 2160x1440 296x197mm 14.0-inch      | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15C5 1366x768 344x193mm 15.5-inch       | 3         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D3 1920x1080 309x173mm 13.9-inch      | 3         | 0.56%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                 | 3         | 0.56%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.56%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 3         | 0.56%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 3         | 0.56%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.56%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.56%   |
| Apple Color LCD APPA02A 2560x1600 286x179mm 13.3-inch                 | 3         | 0.56%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3649 1366x768 309x174mm 14.0-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 2         | 0.37%   |
| RTK FHD RTK2A3B 1920x1080 531x299mm 24.0-inch                         | 2         | 0.37%   |
| PANDA LCD Monitor NCP005F 1920x1080 344x194mm 15.5-inch               | 2         | 0.37%   |
| Mi Monitor XMI23C3 1920x1080 527x293mm 23.7-inch                      | 2         | 0.37%   |
| LG Display LCD Monitor LGD0657 1920x1080 344x194mm 15.5-inch          | 2         | 0.37%   |
| LG Display LCD Monitor LGD060F 1920x1080 309x174mm 14.0-inch          | 2         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Notebooks | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 261       | 52.62%  |
| 1366x768 (WXGA)   | 117       | 23.59%  |
| 2560x1440 (QHD)   | 21        | 4.23%   |
| 2560x1600         | 16        | 3.23%   |
| 1920x1200 (WUXGA) | 16        | 3.23%   |
| 3840x2160 (4K)    | 14        | 2.82%   |
| 2880x1800         | 14        | 2.82%   |
| 1600x900 (HD+)    | 7         | 1.41%   |
| 1280x800 (WXGA)   | 7         | 1.41%   |
| 2160x1440         | 5         | 1.01%   |
| 1440x900 (WXGA+)  | 5         | 1.01%   |
| 2560x1080         | 2         | 0.4%    |
| Unknown           | 2         | 0.4%    |
| 800x1280          | 1         | 0.2%    |
| 3456x2160         | 1         | 0.2%    |
| 3440x1440         | 1         | 0.2%    |
| 3200x2000         | 1         | 0.2%    |
| 3200x1800 (QHD+)  | 1         | 0.2%    |
| 2240x1400         | 1         | 0.2%    |
| 1920x1280         | 1         | 0.2%    |
| 1280x1024 (SXGA)  | 1         | 0.2%    |
| 1024x600          | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 201       | 37.57%  |
| 14      | 105       | 19.63%  |
| 13      | 88        | 16.45%  |
| 27      | 15        | 2.8%    |
| 21      | 15        | 2.8%    |
| 17      | 15        | 2.8%    |
| 16      | 14        | 2.62%   |
| 24      | 13        | 2.43%   |
| 23      | 11        | 2.06%   |
| 12      | 11        | 2.06%   |
| 31      | 10        | 1.87%   |
| 18      | 8         | 1.5%    |
| Unknown | 8         | 1.5%    |
| 11      | 4         | 0.75%   |
| 54      | 3         | 0.56%   |
| 57      | 2         | 0.37%   |
| 34      | 2         | 0.37%   |
| 25      | 2         | 0.37%   |
| 19      | 2         | 0.37%   |
| 52      | 1         | 0.19%   |
| 43      | 1         | 0.19%   |
| 28      | 1         | 0.19%   |
| 20      | 1         | 0.19%   |
| 10      | 1         | 0.19%   |
| 7       | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 369       | 69.23%  |
| 201-300     | 51        | 9.57%   |
| 501-600     | 39        | 7.32%   |
| 401-500     | 26        | 4.88%   |
| 351-400     | 18        | 3.38%   |
| 601-700     | 12        | 2.25%   |
| Unknown     | 8         | 1.5%    |
| 701-800     | 4         | 0.75%   |
| 1001-1500   | 4         | 0.75%   |
| 901-1000    | 1         | 0.19%   |
| 1-100       | 1         | 0.19%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 392       | 83.58%  |
| 16/10   | 56        | 11.94%  |
| Unknown | 8         | 1.71%   |
| 3/2     | 6         | 1.28%   |
| 21/9    | 3         | 0.64%   |
| 0.56    | 2         | 0.43%   |
| 5/4     | 1         | 0.21%   |
| 0.67    | 1         | 0.21%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 201       | 37.5%   |
| 81-90          | 170       | 31.72%  |
| 201-250        | 32        | 5.97%   |
| 71-80          | 22        | 4.1%    |
| 301-350        | 15        | 2.8%    |
| 121-130        | 14        | 2.61%   |
| 111-120        | 13        | 2.43%   |
| 351-500        | 12        | 2.24%   |
| 61-70          | 11        | 2.05%   |
| 151-200        | 8         | 1.49%   |
| 141-150        | 8         | 1.49%   |
| Unknown        | 8         | 1.49%   |
| 251-300        | 7         | 1.31%   |
| More than 1000 | 6         | 1.12%   |
| 51-60          | 4         | 0.75%   |
| 91-100         | 2         | 0.37%   |
| 41-50          | 1         | 0.19%   |
| 1-40           | 1         | 0.19%   |
| 501-1000       | 1         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 251       | 47.63%  |
| 101-120       | 129       | 24.48%  |
| 51-100        | 59        | 11.2%   |
| 161-240       | 54        | 10.25%  |
| More than 240 | 19        | 3.61%   |
| Unknown       | 8         | 1.52%   |
| 1-50          | 7         | 1.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 397       | 82.02%  |
| 2     | 75        | 15.5%   |
| 0     | 7         | 1.45%   |
| 3     | 5         | 1.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 274       | 36.98%  |
| Realtek Semiconductor                  | 261       | 35.22%  |
| Qualcomm Atheros                       | 80        | 10.8%   |
| Broadcom                               | 37        | 4.99%   |
| MediaTek                               | 31        | 4.18%   |
| Broadcom Limited                       | 15        | 2.02%   |
| Samsung Electronics                    | 8         | 1.08%   |
| Xiaomi                                 | 5         | 0.67%   |
| Marvell Technology Group               | 5         | 0.67%   |
| ASIX Electronics                       | 5         | 0.67%   |
| TP-Link                                | 3         | 0.4%    |
| Hewlett-Packard                        | 2         | 0.27%   |
| DisplayLink                            | 2         | 0.27%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.13%   |
| Sierra Wireless                        | 1         | 0.13%   |
| SEGGER                                 | 1         | 0.13%   |
| Ralink Technology                      | 1         | 0.13%   |
| Ralink                                 | 1         | 0.13%   |
| Qualcomm                               | 1         | 0.13%   |
| Microsoft                              | 1         | 0.13%   |
| Huawei Technologies                    | 1         | 0.13%   |
| Foxconn / Hon Hai                      | 1         | 0.13%   |
| Dell                                   | 1         | 0.13%   |
| D-Link                                 | 1         | 0.13%   |
| ASUSTek Computer                       | 1         | 0.13%   |
| Arduino SA                             | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 170       | 19.32%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 35        | 3.98%   |
| Intel Wi-Fi 6 AX200                                                    | 23        | 2.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 22        | 2.5%    |
| Intel Wireless 8265 / 8275                                             | 21        | 2.39%   |
| Intel Wireless 3165                                                    | 21        | 2.39%   |
| Intel Wi-Fi 6 AX201                                                    | 21        | 2.39%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 20        | 2.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 17        | 1.93%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 17        | 1.93%   |
| Intel Ethernet Connection (4) I219-LM                                  | 15        | 1.7%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 15        | 1.7%    |
| Intel Wireless 7265                                                    | 14        | 1.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 14        | 1.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 1.48%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 13        | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 13        | 1.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 13        | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 13        | 1.48%   |
| Broadcom BCM43142 802.11b/g/n                                          | 13        | 1.48%   |
| Intel Wireless 8260                                                    | 12        | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 11        | 1.25%   |
| Realtek Killer E2600 GbE Controller                                    | 11        | 1.25%   |
| Intel Wireless 7260                                                    | 11        | 1.25%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 10        | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 10        | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9         | 1.02%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 1.02%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 1.02%   |
| Intel Tiger Lake PCH CNVi WiFi                                         | 8         | 0.91%   |
| Intel Centrino Ultimate-N 6300                                         | 8         | 0.91%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 8         | 0.91%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 7         | 0.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 7         | 0.8%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 6         | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 6         | 0.68%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 0.68%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                              | 6         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 5         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 258       | 53.86%  |
| Qualcomm Atheros      | 70        | 14.61%  |
| Realtek Semiconductor | 61        | 12.73%  |
| Broadcom              | 35        | 7.31%   |
| MediaTek              | 30        | 6.26%   |
| Broadcom Limited      | 15        | 3.13%   |
| TP-Link               | 3         | 0.63%   |
| Xiaomi                | 1         | 0.21%   |
| Sierra Wireless       | 1         | 0.21%   |
| Ralink Technology     | 1         | 0.21%   |
| Ralink                | 1         | 0.21%   |
| Dell                  | 1         | 0.21%   |
| D-Link                | 1         | 0.21%   |
| ASUSTek Computer      | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 23        | 4.75%   |
| Intel Wireless 8265 / 8275                                     | 21        | 4.34%   |
| Intel Wireless 3165                                            | 21        | 4.34%   |
| Intel Wi-Fi 6 AX201                                            | 21        | 4.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 20        | 4.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 17        | 3.51%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 17        | 3.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 15        | 3.1%    |
| Intel Wireless 7265                                            | 14        | 2.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 14        | 2.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 13        | 2.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13        | 2.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 13        | 2.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 13        | 2.69%   |
| Broadcom BCM43142 802.11b/g/n                                  | 13        | 2.69%   |
| Intel Wireless 8260                                            | 12        | 2.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 11        | 2.27%   |
| Intel Wireless 7260                                            | 11        | 2.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 2.07%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 2.07%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 1.86%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8         | 1.65%   |
| Intel Centrino Ultimate-N 6300                                 | 8         | 1.65%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 8         | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 7         | 1.45%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 6         | 1.24%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 6         | 1.24%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 6         | 1.24%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 6         | 1.24%   |
| Intel Wireless 3160                                            | 5         | 1.03%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 5         | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 0.83%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4         | 0.83%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 4         | 0.83%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 4         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 0.83%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter    | 4         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 237       | 61.72%  |
| Intel                                  | 94        | 24.48%  |
| Qualcomm Atheros                       | 18        | 4.69%   |
| Samsung Electronics                    | 6         | 1.56%   |
| Marvell Technology Group               | 5         | 1.3%    |
| ASIX Electronics                       | 5         | 1.3%    |
| Xiaomi                                 | 4         | 1.04%   |
| Broadcom                               | 4         | 1.04%   |
| MediaTek                               | 3         | 0.78%   |
| DisplayLink                            | 2         | 0.52%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.26%   |
| Qualcomm                               | 1         | 0.26%   |
| Microsoft                              | 1         | 0.26%   |
| Huawei Technologies                    | 1         | 0.26%   |
| Hewlett-Packard                        | 1         | 0.26%   |
| Foxconn / Hon Hai                      | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 170       | 43.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 35        | 8.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 22        | 5.63%   |
| Intel Ethernet Connection (4) I219-LM                                  | 15        | 3.84%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 3.32%   |
| Realtek Killer E2600 GbE Controller                                    | 11        | 2.81%   |
| Intel Ethernet Connection (3) I218-LM                                  | 9         | 2.3%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 1.53%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 1.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 5         | 1.28%   |
| Intel Ethernet Connection I219-LM                                      | 5         | 1.28%   |
| Intel Ethernet Connection I218-LM                                      | 5         | 1.28%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 1.28%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 1.02%   |
| Intel Ethernet Connection (2) I219-LM                                  | 4         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 1.02%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.77%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.77%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                       | 3         | 0.77%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.77%   |
| Intel Ethernet Connection (5) I219-LM                                  | 3         | 0.77%   |
| Realtek PCIe GbE Family Controller                                     | 2         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.51%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.51%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                | 2         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.51%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 0.51%   |
| Intel 82562GT 10/100 Network Connection                                | 2         | 0.51%   |
| DisplayLink USB3 TO HDMI                                               | 2         | 0.51%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 1         | 0.26%   |
| Sony Ericsson Mobile AB D6503                                          | 1         | 0.26%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.26%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.26%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.26%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.26%   |
| Qualcomm Airtel 4G                                                     | 1         | 0.26%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                      | 1         | 0.26%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 466       | 55.48%  |
| Ethernet | 369       | 43.93%  |
| Modem    | 5         | 0.6%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 402       | 81.87%  |
| Ethernet | 89        | 18.13%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 343       | 73.13%  |
| 1     | 123       | 26.23%  |
| 3     | 2         | 0.43%   |
| 0     | 1         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 331       | 68.53%  |
| Yes  | 152       | 31.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 224       | 53.08%  |
| Realtek Semiconductor           | 38        | 9%      |
| Qualcomm Atheros Communications | 38        | 9%      |
| IMC Networks                    | 24        | 5.69%   |
| Broadcom                        | 24        | 5.69%   |
| Lite-On Technology              | 19        | 4.5%    |
| Foxconn / Hon Hai               | 16        | 3.79%   |
| Apple                           | 12        | 2.84%   |
| Realtek                         | 5         | 1.18%   |
| Dell                            | 5         | 1.18%   |
| MediaTek                        | 4         | 0.95%   |
| Hewlett-Packard                 | 4         | 0.95%   |
| Cambridge Silicon Radio         | 3         | 0.71%   |
| Toshiba                         | 1         | 0.24%   |
| Ralink                          | 1         | 0.24%   |
| Opticis                         | 1         | 0.24%   |
| Foxconn International           | 1         | 0.24%   |
| Chicony Electronics             | 1         | 0.24%   |
| Alps Electric                   | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 78        | 18.35%  |
| Intel AX201 Bluetooth                               | 55        | 12.94%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 29        | 6.82%   |
| Realtek Bluetooth Radio                             | 24        | 5.65%   |
| Intel AX200 Bluetooth                               | 23        | 5.41%   |
| Qualcomm Atheros  Bluetooth Device                  | 22        | 5.18%   |
| Intel AX210 Bluetooth                               | 17        | 4%      |
| Intel AX211 Bluetooth                               | 13        | 3.06%   |
| IMC Networks Wireless_Device                        | 12        | 2.82%   |
| Apple Bluetooth Host Controller                     | 8         | 1.88%   |
| Realtek  Bluetooth 4.2 Adapter                      | 7         | 1.65%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 1.65%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 6         | 1.41%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.41%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 1.41%   |
| Realtek Bluetooth Radio                             | 5         | 1.18%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 1.18%   |
| Foxconn / Hon Hai Wireless_Device                   | 5         | 1.18%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.94%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.94%   |
| MediaTek Wireless_Device                            | 4         | 0.94%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 0.94%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 4         | 0.94%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 4         | 0.94%   |
| Apple Bluetooth USB Host Controller                 | 4         | 0.94%   |
| Lite-On Wireless_Device                             | 3         | 0.71%   |
| Lite-On Bluetooth Device                            | 3         | 0.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 3         | 0.71%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 0.71%   |
| HP Broadcom 2070 Bluetooth Combo                    | 3         | 0.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 0.71%   |
| Broadcom HP Portable SoftSailing                    | 3         | 0.71%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 3         | 0.71%   |
| Realtek 802.11ac WLAN Adapter                       | 2         | 0.47%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 2         | 0.47%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 2         | 0.47%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.47%   |
| Lite-On Bluetooth Radio                             | 2         | 0.47%   |
| Lite-On Atheros Bluetooth                           | 2         | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.47%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 380       | 63.55%  |
| Nvidia                    | 103       | 17.22%  |
| AMD                       | 90        | 15.05%  |
| Generalplus Technology    | 3         | 0.5%    |
| Realtek Semiconductor     | 2         | 0.33%   |
| C-Media Electronics       | 2         | 0.33%   |
| Walmart                   | 1         | 0.17%   |
| Texas Instruments         | 1         | 0.17%   |
| Shenzhen Rapoo Technology | 1         | 0.17%   |
| Plantronics               | 1         | 0.17%   |
| OPPO Electronics          | 1         | 0.17%   |
| Micro Star International  | 1         | 0.17%   |
| Logitech                  | 1         | 0.17%   |
| JMTek                     | 1         | 0.17%   |
| Jieli Technology          | 1         | 0.17%   |
| GN Netcom                 | 1         | 0.17%   |
| FIFINE Microphones        | 1         | 0.17%   |
| EDFIER                    | 1         | 0.17%   |
| AudioQuest                | 1         | 0.17%   |
| Audeze                    | 1         | 0.17%   |
| ASUSTek Computer          | 1         | 0.17%   |
| Apple                     | 1         | 0.17%   |
| - KTMicro -               | 1         | 0.17%   |
| Unknown                   | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                 | 80        | 10.99%  |
| Intel Sunrise Point-LP HD Audio                                            | 64        | 8.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 48        | 6.59%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 41        | 5.63%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 25        | 3.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 24        | 3.3%    |
| Intel Broadwell-U Audio Controller                                         | 24        | 3.3%    |
| Intel Haswell-ULT HD Audio Controller                                      | 23        | 3.16%   |
| Intel Cannon Lake PCH cAVS                                                 | 23        | 3.16%   |
| Intel 8 Series HD Audio Controller                                         | 23        | 3.16%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 20        | 2.75%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 20        | 2.75%   |
| Nvidia GA107 High Definition Audio Controller                              | 17        | 2.34%   |
| Intel Comet Lake PCH-LP cAVS                                               | 17        | 2.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 17        | 2.34%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 15        | 2.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14        | 1.92%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 12        | 1.65%   |
| Intel CM238 HD Audio Controller                                            | 12        | 1.65%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 12        | 1.65%   |
| Intel Comet Lake PCH cAVS                                                  | 11        | 1.51%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 1.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 10        | 1.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 9         | 1.24%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 9         | 1.24%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 1.1%    |
| Nvidia GF108 High Definition Audio Controller                              | 8         | 1.1%    |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 1.1%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7         | 0.96%   |
| Nvidia TU116 High Definition Audio Controller                              | 6         | 0.82%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 6         | 0.82%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 0.82%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5         | 0.69%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 5         | 0.69%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.55%   |
| Nvidia GK107 HDMI Audio Controller                                         | 4         | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                              | 3         | 0.41%   |
| Nvidia High Definition Audio Controller                                    | 3         | 0.41%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.41%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 113       | 29.2%   |
| SK hynix                                | 80        | 20.67%  |
| Micron Technology                       | 62        | 16.02%  |
| Kingston                                | 54        | 13.95%  |
| Unknown                                 | 12        | 3.1%    |
| Crucial                                 | 12        | 3.1%    |
| G.Skill                                 | 11        | 2.84%   |
| Ramaxel Technology                      | 8         | 2.07%   |
| A-DATA Technology                       | 8         | 2.07%   |
| Corsair                                 | 6         | 1.55%   |
| Elpida                                  | 4         | 1.03%   |
| Apacer                                  | 3         | 0.78%   |
| Team                                    | 2         | 0.52%   |
| Kingmax                                 | 2         | 0.52%   |
| Unknown (ABCD)                          | 1         | 0.26%   |
| Unknown (7FE0)                          | 1         | 0.26%   |
| Silicon Power Computer & Communications | 1         | 0.26%   |
| PUSKILL                                 | 1         | 0.26%   |
| Nanya Technology                        | 1         | 0.26%   |
| Lexar Co Limited                        | 1         | 0.26%   |
| Kingmax Semiconductor                   | 1         | 0.26%   |
| KingFast                                | 1         | 0.26%   |
| ChangXin Memory                         | 1         | 0.26%   |
| Unknown                                 | 1         | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 7         | 1.68%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 7         | 1.68%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 6         | 1.44%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 1.44%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s     | 6         | 1.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s        | 6         | 1.44%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 5         | 1.2%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 5         | 1.2%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 1.2%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 5         | 1.2%    |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 5         | 1.2%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 5         | 1.2%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s         | 5         | 1.2%    |
| Kingston RAM LV32D4S2S8HD-8 8GB SODIMM DDR4 3200MT/s         | 5         | 1.2%    |
| Kingston RAM 9905700-122.A00G 16GB SODIMM DDR4 3200MT/s      | 5         | 1.2%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 4         | 0.96%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 4         | 0.96%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s         | 4         | 0.96%   |
| G.Skill RAM F4-3200C22-8GRS 8GB SODIMM DDR4 3200MT/s         | 4         | 0.96%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.72%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s | 3         | 0.72%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 3         | 0.72%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 3         | 0.72%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 3         | 0.72%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 0.72%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s        | 3         | 0.72%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s       | 3         | 0.72%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s       | 3         | 0.72%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 0.72%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 3         | 0.72%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s        | 3         | 0.72%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 3         | 0.72%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s        | 3         | 0.72%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s         | 3         | 0.72%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s        | 2         | 0.48%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 2         | 0.48%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1600MT/s                 | 2         | 0.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 2         | 0.48%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.48%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 184       | 60.73%  |
| DDR3   | 70        | 23.1%   |
| DDR5   | 15        | 4.95%   |
| LPDDR4 | 12        | 3.96%   |
| LPDDR5 | 10        | 3.3%    |
| LPDDR3 | 8         | 2.64%   |
| DDR2   | 3         | 0.99%   |
| SDRAM  | 1         | 0.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 270       | 88.52%  |
| Row Of Chips | 34        | 11.15%  |
| Unknown      | 1         | 0.33%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 151       | 45.07%  |
| 4096  | 87        | 25.97%  |
| 16384 | 63        | 18.81%  |
| 2048  | 21        | 6.27%   |
| 32768 | 10        | 2.99%   |
| 1024  | 3         | 0.9%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 97        | 29.39%  |
| 2667    | 74        | 22.42%  |
| 1600    | 56        | 16.97%  |
| 2400    | 27        | 8.18%   |
| 2133    | 12        | 3.64%   |
| 5600    | 8         | 2.42%   |
| 4800    | 7         | 2.12%   |
| 1334    | 7         | 2.12%   |
| 1333    | 6         | 1.82%   |
| 6400    | 5         | 1.52%   |
| 1867    | 5         | 1.52%   |
| 7500    | 4         | 1.21%   |
| 4267    | 4         | 1.21%   |
| 8400    | 3         | 0.91%   |
| Unknown | 3         | 0.91%   |
| 3266    | 2         | 0.61%   |
| 667     | 2         | 0.61%   |
| 7467    | 1         | 0.3%    |
| 4266    | 1         | 0.3%    |
| 4199    | 1         | 0.3%    |
| 3733    | 1         | 0.3%    |
| 2933    | 1         | 0.3%    |
| 1067    | 1         | 0.3%    |
| 975     | 1         | 0.3%    |
| 800     | 1         | 0.3%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| MIIIW              | 1         | 25%     |
| Hewlett-Packard    | 1         | 25%     |
| Canon              | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Notebooks | Percent |
|----------------------------|-----------|---------|
| MIIIW MW Keyboard Air Mini | 1         | 25%     |
| HP LaserJet P1102          | 1         | 25%     |
| Canon LBP6030/6030B/6018L  | 1         | 25%     |
| Brother HL-L2320D series   | 1         | 25%     |

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
| Chicony Electronics                    | 85        | 20.43%  |
| IMC Networks                           | 56        | 13.46%  |
| Microdia                               | 54        | 12.98%  |
| Sunplus Innovation Technology          | 35        | 8.41%   |
| Realtek Semiconductor                  | 32        | 7.69%   |
| Bison Electronics                      | 27        | 6.49%   |
| Quanta                                 | 26        | 6.25%   |
| Luxvisions Innotech Limited            | 16        | 3.85%   |
| Syntek                                 | 14        | 3.37%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 2.88%   |
| Lite-On Technology                     | 9         | 2.16%   |
| Apple                                  | 9         | 2.16%   |
| Suyin                                  | 7         | 1.68%   |
| Acer                                   | 7         | 1.68%   |
| Sonix Technology                       | 5         | 1.2%    |
| Logitech                               | 5         | 1.2%    |
| Ricoh                                  | 4         | 0.96%   |
| Silicon Motion                         | 2         | 0.48%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.48%   |
| Samsung Electronics                    | 2         | 0.48%   |
| Denron                                 | 2         | 0.48%   |
| Alcor Micro                            | 2         | 0.48%   |
| Shinetech                              | 1         | 0.24%   |
| Lenovo                                 | 1         | 0.24%   |
| ALi                                    | 1         | 0.24%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                     | 28        | 6.7%    |
| Chicony Integrated Camera                         | 27        | 6.46%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 20        | 4.78%   |
| Sunplus Integrated_Webcam_HD                      | 19        | 4.55%   |
| IMC Networks Integrated Camera                    | 14        | 3.35%   |
| Realtek Integrated_Webcam_HD                      | 13        | 3.11%   |
| Syntek Integrated Camera                          | 11        | 2.63%   |
| Bison HD Webcam                                   | 10        | 2.39%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 8         | 1.91%   |
| Chicony HD Webcam                                 | 8         | 1.91%   |
| Quanta HD User Facing                             | 7         | 1.67%   |
| Luxvisions Innotech Limited Integrated Camera     | 7         | 1.67%   |
| Chicony HP HD Camera                              | 7         | 1.67%   |
| Microdia Laptop_Integrated_Webcam_HD              | 6         | 1.44%   |
| Microdia Integrated Webcam                        | 6         | 1.44%   |
| Chicony HP TrueVision HD Camera                   | 6         | 1.44%   |
| Sonix USB2.0 HD UVC WebCam                        | 5         | 1.2%    |
| Realtek Integrated Webcam                         | 5         | 1.2%    |
| Bison SunplusIT Integrated Camera                 | 5         | 1.2%    |
| Bison Integrated Camera                           | 5         | 1.2%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                | 5         | 1.2%    |
| Acer Integrated Camera                            | 5         | 1.2%    |
| Realtek USB Camera                                | 4         | 0.96%   |
| Quanta HP TrueVision HD Camera                    | 4         | 0.96%   |
| Lite-On Integrated Camera                         | 4         | 0.96%   |
| Chicony HD User Facing                            | 4         | 0.96%   |
| Bison ThinkPad Integrated Camera                  | 4         | 0.96%   |
| Syntek Lenovo EasyCamera                          | 3         | 0.72%   |
| Sunplus Laptop_Integrated_Webcam_FHD              | 3         | 0.72%   |
| Realtek Integrated Webcam HD                      | 3         | 0.72%   |
| Quanta VGA WebCam                                 | 3         | 0.72%   |
| Quanta ov9734_techfront_camera                    | 3         | 0.72%   |
| Quanta HP HD Camera                               | 3         | 0.72%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 3         | 0.72%   |
| Luxvisions Innotech Limited HP 5MP Camera         | 3         | 0.72%   |
| IMC Networks VGA UVC WebCam                       | 3         | 0.72%   |
| IMC Networks USB2.0 UVC HD Webcam                 | 3         | 0.72%   |
| Chicony Integrated HP HD Webcam                   | 3         | 0.72%   |
| Chicony HP HD Webcam                              | 3         | 0.72%   |
| Chicony ACER HD User Facing                       | 3         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 40        | 43.96%  |
| Shenzhen Goodix Technology | 22        | 24.18%  |
| Synaptics                  | 20        | 21.98%  |
| Elan Microelectronics      | 3         | 3.3%    |
| Samsung Electronics        | 2         | 2.2%    |
| LighTuning Technology      | 2         | 2.2%    |
| Upek                       | 1         | 1.1%    |
| STMicroelectronics         | 1         | 1.1%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 16        | 17.58%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 9.89%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 7         | 7.69%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 6.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 6         | 6.59%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 5.49%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 5.49%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 5.49%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 4.4%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 4.4%    |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 4         | 4.4%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2.2%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.2%    |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 2.2%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.2%    |
| Elan ELAN:Fingerprint                                                      | 2         | 2.2%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.1%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 1.1%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 1.1%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 1.1%    |
| Synaptics UWP WBDI                                                         | 1         | 1.1%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.1%    |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 1.1%    |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.1%    |
| Shenzhen Goodix FingerPrint                                                | 1         | 1.1%    |
| Elan WBF Fingerprint Sensor                                                | 1         | 1.1%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 22        | 75.86%  |
| Alcor Micro | 4         | 13.79%  |
| Upek        | 1         | 3.45%   |
| OmniKey     | 1         | 3.45%   |
| Lenovo      | 1         | 3.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 9         | 31.03%  |
| Broadcom 5880                                                                | 8         | 27.59%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 13.79%  |
| Broadcom 58200                                                               | 3         | 10.34%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 6.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.45%   |
| OmniKey CardMan 4321                                                         | 1         | 3.45%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 3.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 284       | 58.32%  |
| 1     | 170       | 34.91%  |
| 2     | 28        | 5.75%   |
| 3     | 4         | 0.82%   |
| 5     | 1         | 0.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 89        | 38.03%  |
| Graphics card            | 45        | 19.23%  |
| Chipcard                 | 28        | 11.97%  |
| Net/wireless             | 20        | 8.55%   |
| Multimedia controller    | 19        | 8.12%   |
| Camera                   | 10        | 4.27%   |
| Communication controller | 7         | 2.99%   |
| Bluetooth                | 5         | 2.14%   |
| Net/ethernet             | 4         | 1.71%   |
| Storage                  | 3         | 1.28%   |
| Card reader              | 2         | 0.85%   |
| Unassigned class         | 1         | 0.43%   |
| Sound                    | 1         | 0.43%   |

