Fedora - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Fedora.

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

Total: 12565

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [720ff4cf67](https://linux-hardware.org/?probe=720ff4cf67) | Dec 24, 2023 |
| Lenovo        | ThinkPad E460 20ET0016US    | [96959ec0a3](https://linux-hardware.org/?probe=96959ec0a3) | Dec 24, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [de6b5ead5b](https://linux-hardware.org/?probe=de6b5ead5b) | Dec 24, 2023 |
| Acer          | Aspire 5742Z                | [ddf1553f4b](https://linux-hardware.org/?probe=ddf1553f4b) | Dec 24, 2023 |
| Samsung       | RV415/RV515                 | [da980644b4](https://linux-hardware.org/?probe=da980644b4) | Dec 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [29b4b5a349](https://linux-hardware.org/?probe=29b4b5a349) | Dec 24, 2023 |
| Dell          | G16 7630                    | [71f36f8ed0](https://linux-hardware.org/?probe=71f36f8ed0) | Dec 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [c0ff23eba6](https://linux-hardware.org/?probe=c0ff23eba6) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [d49a8fe4d4](https://linux-hardware.org/?probe=d49a8fe4d4) | Dec 24, 2023 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [f1c9eab3f4](https://linux-hardware.org/?probe=f1c9eab3f4) | Dec 24, 2023 |
| Acer          | Aspire A515-43              | [922518c025](https://linux-hardware.org/?probe=922518c025) | Dec 23, 2023 |
| Dell          | Inspiron 15 3530            | [0688896e27](https://linux-hardware.org/?probe=0688896e27) | Dec 23, 2023 |
| HP            | Elite x2 1012 G1            | [b093087b3c](https://linux-hardware.org/?probe=b093087b3c) | Dec 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [a79885417a](https://linux-hardware.org/?probe=a79885417a) | Dec 23, 2023 |
| HP            | Elite x2 1012 G1            | [c93fffc388](https://linux-hardware.org/?probe=c93fffc388) | Dec 23, 2023 |
| Dell          | Latitude E6420              | [82c13c188b](https://linux-hardware.org/?probe=82c13c188b) | Dec 23, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b3e3c041d7](https://linux-hardware.org/?probe=b3e3c041d7) | Dec 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [40ba77bcb8](https://linux-hardware.org/?probe=40ba77bcb8) | Dec 23, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5c4d1c7d64](https://linux-hardware.org/?probe=5c4d1c7d64) | Dec 23, 2023 |
| Dell          | XPS 13 9310                 | [78b73643ff](https://linux-hardware.org/?probe=78b73643ff) | Dec 23, 2023 |
| ASUSTek       | T100TA                      | [9ad17d2d3c](https://linux-hardware.org/?probe=9ad17d2d3c) | Dec 23, 2023 |
| Toshiba       | Satellite P850              | [e16f04d074](https://linux-hardware.org/?probe=e16f04d074) | Dec 23, 2023 |
| Danew         | Dbook 131                   | [a3880bd02c](https://linux-hardware.org/?probe=a3880bd02c) | Dec 23, 2023 |
| Lenovo        | Slim Pro 7 14ARP8 83AX      | [1ace47e8fd](https://linux-hardware.org/?probe=1ace47e8fd) | Dec 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S69B00    | [16b6aaa173](https://linux-hardware.org/?probe=16b6aaa173) | Dec 23, 2023 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [9a5d0ca94a](https://linux-hardware.org/?probe=9a5d0ca94a) | Dec 23, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | [2ca58f3eb8](https://linux-hardware.org/?probe=2ca58f3eb8) | Dec 23, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K6... | [d53640436b](https://linux-hardware.org/?probe=d53640436b) | Dec 22, 2023 |
| Dell          | Latitude 5420               | [9858586a84](https://linux-hardware.org/?probe=9858586a84) | Dec 22, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [dbfd9ef700](https://linux-hardware.org/?probe=dbfd9ef700) | Dec 22, 2023 |
| Dell          | Precision M4800             | [ce7a9239f4](https://linux-hardware.org/?probe=ce7a9239f4) | Dec 22, 2023 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [d65cca0578](https://linux-hardware.org/?probe=d65cca0578) | Dec 22, 2023 |
| Dell          | Latitude 7300               | [8792895835](https://linux-hardware.org/?probe=8792895835) | Dec 22, 2023 |
| HP            | OMEN by Gaming Laptop 16... | [d36af9d69e](https://linux-hardware.org/?probe=d36af9d69e) | Dec 22, 2023 |
| Acer          | Nitro AN515-58              | [c7a31a4dab](https://linux-hardware.org/?probe=c7a31a4dab) | Dec 22, 2023 |
| Dell          | Latitude 14 Rugged (5404... | [084f663c15](https://linux-hardware.org/?probe=084f663c15) | Dec 22, 2023 |
| Danew         | Dbook 131                   | [0568c9bdbf](https://linux-hardware.org/?probe=0568c9bdbf) | Dec 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [283320e72d](https://linux-hardware.org/?probe=283320e72d) | Dec 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [6f60c08653](https://linux-hardware.org/?probe=6f60c08653) | Dec 21, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [cf835775a4](https://linux-hardware.org/?probe=cf835775a4) | Dec 21, 2023 |
| Gigabyte      | AORUS 15 XE4                | [5dd281e2dd](https://linux-hardware.org/?probe=5dd281e2dd) | Dec 21, 2023 |
| MSI           | Modern 15 B7M               | [77760018a7](https://linux-hardware.org/?probe=77760018a7) | Dec 21, 2023 |
| Lenovo        | ThinkBook 13s-IWL 20R9      | [e864a3cd22](https://linux-hardware.org/?probe=e864a3cd22) | Dec 21, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [cb7f868a54](https://linux-hardware.org/?probe=cb7f868a54) | Dec 21, 2023 |
| ASUSTek       | X411UA                      | [a4a14550e8](https://linux-hardware.org/?probe=a4a14550e8) | Dec 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ef2e756e7b](https://linux-hardware.org/?probe=ef2e756e7b) | Dec 21, 2023 |
| HUAWEI        | MRGFG-XX                    | [747de8fa3c](https://linux-hardware.org/?probe=747de8fa3c) | Dec 21, 2023 |
| Acer          | Aspire M5-581T              | [c99da67d31](https://linux-hardware.org/?probe=c99da67d31) | Dec 21, 2023 |
| HP            | ProBook 445 G7              | [4153ae7cc6](https://linux-hardware.org/?probe=4153ae7cc6) | Dec 21, 2023 |
| Acer          | Predator PH16-71            | [403fcc076f](https://linux-hardware.org/?probe=403fcc076f) | Dec 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [03b86f8fd8](https://linux-hardware.org/?probe=03b86f8fd8) | Dec 21, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [faabc05597](https://linux-hardware.org/?probe=faabc05597) | Dec 21, 2023 |
| Dell          | Latitude 3410               | [3de48ebce1](https://linux-hardware.org/?probe=3de48ebce1) | Dec 20, 2023 |
| Dell          | XPS 15 9510                 | [107d6edb72](https://linux-hardware.org/?probe=107d6edb72) | Dec 20, 2023 |
| ASUSTek       | X580VD                      | [18f5888ad5](https://linux-hardware.org/?probe=18f5888ad5) | Dec 20, 2023 |
| HP            | Stream Laptop 14-ax0XX      | [398a10f8ce](https://linux-hardware.org/?probe=398a10f8ce) | Dec 20, 2023 |
| MSI           | Prestige 14Evo A12M         | [23e7499358](https://linux-hardware.org/?probe=23e7499358) | Dec 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [eef5dcab57](https://linux-hardware.org/?probe=eef5dcab57) | Dec 20, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [c2eacfced7](https://linux-hardware.org/?probe=c2eacfced7) | Dec 20, 2023 |
| Dell          | Latitude E5450              | [6d4e378f53](https://linux-hardware.org/?probe=6d4e378f53) | Dec 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [44a01e07bb](https://linux-hardware.org/?probe=44a01e07bb) | Dec 20, 2023 |
| Apple         | MacBookPro14,2              | [e13dae2abd](https://linux-hardware.org/?probe=e13dae2abd) | Dec 20, 2023 |
| HUAWEI        | BOHB-WAX9                   | [7b4cd22d8d](https://linux-hardware.org/?probe=7b4cd22d8d) | Dec 20, 2023 |
| ASUSTek       | X556URK                     | [b4f01c5bd5](https://linux-hardware.org/?probe=b4f01c5bd5) | Dec 19, 2023 |
| Dell          | Latitude 3460               | [c3b4a00583](https://linux-hardware.org/?probe=c3b4a00583) | Dec 19, 2023 |
| Dell          | Latitude 3460               | [3b425238a6](https://linux-hardware.org/?probe=3b425238a6) | Dec 19, 2023 |
| Lenovo        | ThinkPad S430 336457G       | [4acd70fc9f](https://linux-hardware.org/?probe=4acd70fc9f) | Dec 19, 2023 |
| Acer          | Aspire A515-57              | [f6f623f0d8](https://linux-hardware.org/?probe=f6f623f0d8) | Dec 19, 2023 |
| HUAWEI        | MRGFG-XX                    | [6a10eb945c](https://linux-hardware.org/?probe=6a10eb945c) | Dec 19, 2023 |
| Dell          | Latitude E5450              | [627a81b211](https://linux-hardware.org/?probe=627a81b211) | Dec 19, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [a074081eb1](https://linux-hardware.org/?probe=a074081eb1) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [85531f6788](https://linux-hardware.org/?probe=85531f6788) | Dec 19, 2023 |
| Dell          | Inspiron N5110              | [761103087e](https://linux-hardware.org/?probe=761103087e) | Dec 19, 2023 |
| Acer          | Swift SF314-54              | [4d8fbbd6d0](https://linux-hardware.org/?probe=4d8fbbd6d0) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [4715b83a8c](https://linux-hardware.org/?probe=4715b83a8c) | Dec 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [e37edfc830](https://linux-hardware.org/?probe=e37edfc830) | Dec 19, 2023 |
| Dell          | Inspiron 3542               | [7d3f7e97ce](https://linux-hardware.org/?probe=7d3f7e97ce) | Dec 19, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2d2f0f8de2](https://linux-hardware.org/?probe=2d2f0f8de2) | Dec 19, 2023 |
| Dell          | Inspiron 5520               | [df5cca640e](https://linux-hardware.org/?probe=df5cca640e) | Dec 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9afec278e2](https://linux-hardware.org/?probe=9afec278e2) | Dec 18, 2023 |
| Dell          | Inspiron 5520               | [0d5fb0418b](https://linux-hardware.org/?probe=0d5fb0418b) | Dec 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [1d8ddbcb75](https://linux-hardware.org/?probe=1d8ddbcb75) | Dec 18, 2023 |
| Dell          | Latitude 3420               | [59784d2788](https://linux-hardware.org/?probe=59784d2788) | Dec 18, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [147873adce](https://linux-hardware.org/?probe=147873adce) | Dec 18, 2023 |
| Dell          | Latitude E5470              | [9aa1f53217](https://linux-hardware.org/?probe=9aa1f53217) | Dec 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [1c015093b2](https://linux-hardware.org/?probe=1c015093b2) | Dec 18, 2023 |
| Dell          | Latitude E5550              | [671595a2e5](https://linux-hardware.org/?probe=671595a2e5) | Dec 18, 2023 |
| GPD           | G1619-04                    | [63b517665b](https://linux-hardware.org/?probe=63b517665b) | Dec 18, 2023 |
| Lenovo        | ThinkPad T450s 20BX001LU... | [b3a6780db5](https://linux-hardware.org/?probe=b3a6780db5) | Dec 18, 2023 |
| Dell          | Latitude E7440              | [c2dce135e4](https://linux-hardware.org/?probe=c2dce135e4) | Dec 18, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4e18aeb53f](https://linux-hardware.org/?probe=4e18aeb53f) | Dec 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7d1b99f3a7](https://linux-hardware.org/?probe=7d1b99f3a7) | Dec 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [1a1a04845b](https://linux-hardware.org/?probe=1a1a04845b) | Dec 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [19fe61d807](https://linux-hardware.org/?probe=19fe61d807) | Dec 18, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [b0526a42f4](https://linux-hardware.org/?probe=b0526a42f4) | Dec 18, 2023 |
| Samsung       | 550P5C/550P7C               | [b06e8fbef4](https://linux-hardware.org/?probe=b06e8fbef4) | Dec 18, 2023 |
| ASUSTek       | K53SD                       | [4b43240ccd](https://linux-hardware.org/?probe=4b43240ccd) | Dec 18, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [612482d238](https://linux-hardware.org/?probe=612482d238) | Dec 18, 2023 |
| Compal        | PBL1011                     | [8983f2e331](https://linux-hardware.org/?probe=8983f2e331) | Dec 18, 2023 |
| Acer          | Nitro AN515-55              | [bdecd800b4](https://linux-hardware.org/?probe=bdecd800b4) | Dec 18, 2023 |
| Lenovo        | ThinkPad X270 20HMS0B60H    | [059545a4ad](https://linux-hardware.org/?probe=059545a4ad) | Dec 17, 2023 |
| Lenovo        | IdeaPad MIIX 700-12ISK 8... | [6ac6a904be](https://linux-hardware.org/?probe=6ac6a904be) | Dec 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [7b289201bc](https://linux-hardware.org/?probe=7b289201bc) | Dec 17, 2023 |
| Acer          | Nitro AN517-54              | [80aeddc1b2](https://linux-hardware.org/?probe=80aeddc1b2) | Dec 17, 2023 |
| HP            | ZBook 17 G5                 | [288e976604](https://linux-hardware.org/?probe=288e976604) | Dec 17, 2023 |
| Acer          | Nitro AN517-54              | [2f2bcf0c97](https://linux-hardware.org/?probe=2f2bcf0c97) | Dec 17, 2023 |
| Dell          | G5 5587                     | [0200ad8ea9](https://linux-hardware.org/?probe=0200ad8ea9) | Dec 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [26503ce57e](https://linux-hardware.org/?probe=26503ce57e) | Dec 17, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [16902836db](https://linux-hardware.org/?probe=16902836db) | Dec 17, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | [845e586dba](https://linux-hardware.org/?probe=845e586dba) | Dec 17, 2023 |
| ASUSTek       | ROG Strix G814JZ_G814JZ     | [b8d81eb2c9](https://linux-hardware.org/?probe=b8d81eb2c9) | Dec 17, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [c93d5be9d6](https://linux-hardware.org/?probe=c93d5be9d6) | Dec 17, 2023 |
| VIT           | P3400                       | [0564cdc52e](https://linux-hardware.org/?probe=0564cdc52e) | Dec 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [299d6ae362](https://linux-hardware.org/?probe=299d6ae362) | Dec 17, 2023 |
| Fujitsu       | LIFEBOOK U749               | [4ede8e182e](https://linux-hardware.org/?probe=4ede8e182e) | Dec 17, 2023 |
| Lenovo        | ThinkPad E580 20KTS0TF00    | [3a2290dbe0](https://linux-hardware.org/?probe=3a2290dbe0) | Dec 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [f4c923a84a](https://linux-hardware.org/?probe=f4c923a84a) | Dec 16, 2023 |
| Dell          | Inspiron 15-3567            | [570a822273](https://linux-hardware.org/?probe=570a822273) | Dec 16, 2023 |
| Fujitsu       | LIFEBOOK U728               | [381f2ea08d](https://linux-hardware.org/?probe=381f2ea08d) | Dec 16, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [a2a4eb520c](https://linux-hardware.org/?probe=a2a4eb520c) | Dec 16, 2023 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | [9e217a08be](https://linux-hardware.org/?probe=9e217a08be) | Dec 16, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [f7ffef008a](https://linux-hardware.org/?probe=f7ffef008a) | Dec 16, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [fc9b36317a](https://linux-hardware.org/?probe=fc9b36317a) | Dec 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [984c55c6a2](https://linux-hardware.org/?probe=984c55c6a2) | Dec 16, 2023 |
| Lenovo        | B50-80 80LT                 | [ea695bd9c5](https://linux-hardware.org/?probe=ea695bd9c5) | Dec 16, 2023 |
| Lenovo        | B50-80 80LT                 | [40d547e3f5](https://linux-hardware.org/?probe=40d547e3f5) | Dec 16, 2023 |
| HP            | Compaq CQ58                 | [7567b51bda](https://linux-hardware.org/?probe=7567b51bda) | Dec 16, 2023 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [56e95fc392](https://linux-hardware.org/?probe=56e95fc392) | Dec 16, 2023 |
| Apple         | MacBookPro10,1              | [adc736fc8d](https://linux-hardware.org/?probe=adc736fc8d) | Dec 16, 2023 |
| MSI           | GP62MVR 7RFX                | [fcb56f79d6](https://linux-hardware.org/?probe=fcb56f79d6) | Dec 16, 2023 |
| ASUSTek       | Q524UQ                      | [8466629595](https://linux-hardware.org/?probe=8466629595) | Dec 16, 2023 |
| Dell          | Inspiron 5447               | [0e868b4cba](https://linux-hardware.org/?probe=0e868b4cba) | Dec 15, 2023 |
| Dell          | Inspiron 5447               | [60320e4007](https://linux-hardware.org/?probe=60320e4007) | Dec 15, 2023 |
| Dell          | Inspiron 13-5378            | [d63cdec5eb](https://linux-hardware.org/?probe=d63cdec5eb) | Dec 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [cde85f7526](https://linux-hardware.org/?probe=cde85f7526) | Dec 15, 2023 |
| ASUSTek       | X540LJ                      | [281c56510a](https://linux-hardware.org/?probe=281c56510a) | Dec 15, 2023 |
| Apple         | MacBookPro5,3               | [f882c29faa](https://linux-hardware.org/?probe=f882c29faa) | Dec 15, 2023 |
| Dell          | Latitude E5550              | [dc16864fb6](https://linux-hardware.org/?probe=dc16864fb6) | Dec 15, 2023 |
| Apple         | MacBookPro11,3              | [106c5c6ec4](https://linux-hardware.org/?probe=106c5c6ec4) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e5916c58ec](https://linux-hardware.org/?probe=e5916c58ec) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [37495b67c9](https://linux-hardware.org/?probe=37495b67c9) | Dec 15, 2023 |
| ASUSTek       | ROG Strix G531GU_GL531GU    | [b3b3853325](https://linux-hardware.org/?probe=b3b3853325) | Dec 15, 2023 |
| HP            | ZBook 15u G6                | [4467debb1c](https://linux-hardware.org/?probe=4467debb1c) | Dec 15, 2023 |
| Sony          | SVF1521G6EW                 | [55b5387ed5](https://linux-hardware.org/?probe=55b5387ed5) | Dec 15, 2023 |
| Apple         | MacBookPro5,3               | [066c7e2b1a](https://linux-hardware.org/?probe=066c7e2b1a) | Dec 15, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [b342bc9627](https://linux-hardware.org/?probe=b342bc9627) | Dec 14, 2023 |
| Lenovo        | Yoga Slim 6 14IAP8 82WU     | [c2186c6471](https://linux-hardware.org/?probe=c2186c6471) | Dec 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [a043c13550](https://linux-hardware.org/?probe=a043c13550) | Dec 14, 2023 |
| Dell          | Inspiron 3793               | [90804693a6](https://linux-hardware.org/?probe=90804693a6) | Dec 14, 2023 |
| Dell          | Precision M3800             | [9e8d36821a](https://linux-hardware.org/?probe=9e8d36821a) | Dec 14, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | [91fd392ea3](https://linux-hardware.org/?probe=91fd392ea3) | Dec 14, 2023 |
| Apple         | MacBookAir9,1               | [6cadf8d04e](https://linux-hardware.org/?probe=6cadf8d04e) | Dec 14, 2023 |
| Dell          | Precision 5510              | [ddc02a6165](https://linux-hardware.org/?probe=ddc02a6165) | Dec 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [0728e617a0](https://linux-hardware.org/?probe=0728e617a0) | Dec 14, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [6a493a834d](https://linux-hardware.org/?probe=6a493a834d) | Dec 14, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [9d34609e0d](https://linux-hardware.org/?probe=9d34609e0d) | Dec 14, 2023 |
| Lenovo        | ThinkBook 13x G2 IAP 21A... | [2b65b49ba3](https://linux-hardware.org/?probe=2b65b49ba3) | Dec 14, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [309aea6480](https://linux-hardware.org/?probe=309aea6480) | Dec 14, 2023 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [cda15a71e9](https://linux-hardware.org/?probe=cda15a71e9) | Dec 14, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [0ece599b11](https://linux-hardware.org/?probe=0ece599b11) | Dec 14, 2023 |
| ASRock        | B560M Pro4/ac               | [0dd2927c25](https://linux-hardware.org/?probe=0dd2927c25) | Dec 14, 2023 |
| Dell          | G15 5520                    | [12b6fa0914](https://linux-hardware.org/?probe=12b6fa0914) | Dec 14, 2023 |
| A-DATA Tec... | XENIA 14                    | [ebbefc4570](https://linux-hardware.org/?probe=ebbefc4570) | Dec 14, 2023 |
| Dell          | G15 5520                    | [d212fe82aa](https://linux-hardware.org/?probe=d212fe82aa) | Dec 14, 2023 |
| Acer          | Nitro AN515-45              | [1ff0d683f4](https://linux-hardware.org/?probe=1ff0d683f4) | Dec 13, 2023 |
| Dell          | XPS 15 9530                 | [33d1f683ba](https://linux-hardware.org/?probe=33d1f683ba) | Dec 13, 2023 |
| Lenovo        | ThinkPad E560 20EV000SMZ    | [13b8795a4e](https://linux-hardware.org/?probe=13b8795a4e) | Dec 13, 2023 |
| Lenovo        | Z710 20250                  | [0ffc45c096](https://linux-hardware.org/?probe=0ffc45c096) | Dec 13, 2023 |
| HUAWEI        | HKD-WXX                     | [c6a0ea6b45](https://linux-hardware.org/?probe=c6a0ea6b45) | Dec 13, 2023 |
| Dell          | Precision 5510              | [0ce634decf](https://linux-hardware.org/?probe=0ce634decf) | Dec 13, 2023 |
| HP            | Laptop 17-cp0xxx            | [7d584c6a4d](https://linux-hardware.org/?probe=7d584c6a4d) | Dec 13, 2023 |
| HUAWEI        | HKD-WXX                     | [b0c03a26ce](https://linux-hardware.org/?probe=b0c03a26ce) | Dec 13, 2023 |
| Dell          | XPS 13 9350                 | [149a7f254a](https://linux-hardware.org/?probe=149a7f254a) | Dec 13, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [625439b5a5](https://linux-hardware.org/?probe=625439b5a5) | Dec 13, 2023 |
| Dell          | Precision 7510              | [863d50a5a5](https://linux-hardware.org/?probe=863d50a5a5) | Dec 13, 2023 |
| Dell          | Precision 7510              | [dddb88520a](https://linux-hardware.org/?probe=dddb88520a) | Dec 13, 2023 |
| HP            | EliteBook 840 G4            | [6440dbccd4](https://linux-hardware.org/?probe=6440dbccd4) | Dec 13, 2023 |
| Dell          | Inspiron 5584               | [525d98e3f0](https://linux-hardware.org/?probe=525d98e3f0) | Dec 13, 2023 |
| Lenovo        | ThinkPad E560 20EV000SMZ    | [1bb8694fda](https://linux-hardware.org/?probe=1bb8694fda) | Dec 12, 2023 |
| Acer          | Aspire A515-45              | [74dc572dd7](https://linux-hardware.org/?probe=74dc572dd7) | Dec 12, 2023 |
| Lenovo        | ThinkPad P1 20MD0001GE      | [e4c9202751](https://linux-hardware.org/?probe=e4c9202751) | Dec 12, 2023 |
| Lenovo        | ThinkPad P1 20MD0001GE      | [5662ef46db](https://linux-hardware.org/?probe=5662ef46db) | Dec 12, 2023 |
| Acer          | Aspire A515-45              | [089a40a6f2](https://linux-hardware.org/?probe=089a40a6f2) | Dec 12, 2023 |
| HP            | 15                          | [9c4fb8f41d](https://linux-hardware.org/?probe=9c4fb8f41d) | Dec 12, 2023 |
| HP            | OMEN by Laptop              | [12c97adbac](https://linux-hardware.org/?probe=12c97adbac) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | [9200b90a95](https://linux-hardware.org/?probe=9200b90a95) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | [917471b136](https://linux-hardware.org/?probe=917471b136) | Dec 12, 2023 |
| Apple         | MacBookPro13,2              | [6c3498a025](https://linux-hardware.org/?probe=6c3498a025) | Dec 12, 2023 |
| Apple         | MacBookPro14,1              | [16e9faf4e6](https://linux-hardware.org/?probe=16e9faf4e6) | Dec 12, 2023 |
| Apple         | MacBookPro14,1              | [05ceb8703b](https://linux-hardware.org/?probe=05ceb8703b) | Dec 12, 2023 |
| Timi          | A35R                        | [6133c765d4](https://linux-hardware.org/?probe=6133c765d4) | Dec 12, 2023 |
| Acer          | Extensa 215-55              | [40eaa33887](https://linux-hardware.org/?probe=40eaa33887) | Dec 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS1... | [293fe3fb8e](https://linux-hardware.org/?probe=293fe3fb8e) | Dec 12, 2023 |
| Alienware     | M17x                        | [da64c97fa8](https://linux-hardware.org/?probe=da64c97fa8) | Dec 12, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [dfe75293a5](https://linux-hardware.org/?probe=dfe75293a5) | Dec 12, 2023 |
| Acer          | Aspire A315-510P            | [e2bdedca29](https://linux-hardware.org/?probe=e2bdedca29) | Dec 12, 2023 |
| HUAWEI        | BOD-WXX9                    | [c12ada5b78](https://linux-hardware.org/?probe=c12ada5b78) | Dec 12, 2023 |
| Acer          | V5-171                      | [79abc82869](https://linux-hardware.org/?probe=79abc82869) | Dec 11, 2023 |
| MSI           | Modern 15 B7M               | [d4c74075be](https://linux-hardware.org/?probe=d4c74075be) | Dec 11, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [9a6a483608](https://linux-hardware.org/?probe=9a6a483608) | Dec 11, 2023 |
| Lenovo        | G50-70 20351                | [d22fb3a791](https://linux-hardware.org/?probe=d22fb3a791) | Dec 11, 2023 |
| ASUSTek       | U52F                        | [5bdf8ec184](https://linux-hardware.org/?probe=5bdf8ec184) | Dec 11, 2023 |
| Dell          | Precision M6500             | [5b287ea21f](https://linux-hardware.org/?probe=5b287ea21f) | Dec 11, 2023 |
| Dell          | XPS 15 9510                 | [b88a7e6159](https://linux-hardware.org/?probe=b88a7e6159) | Dec 10, 2023 |
| Lenovo        | ThinkPad T400 6475WJE       | [2dc1349392](https://linux-hardware.org/?probe=2dc1349392) | Dec 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [ee7a9f7ba7](https://linux-hardware.org/?probe=ee7a9f7ba7) | Dec 10, 2023 |
| HP            | Laptop 17-cn3xxx            | [7a93c4b54c](https://linux-hardware.org/?probe=7a93c4b54c) | Dec 10, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [070ba5c3c1](https://linux-hardware.org/?probe=070ba5c3c1) | Dec 10, 2023 |
| Dell          | Inspiron 1525               | [9eb3de84e4](https://linux-hardware.org/?probe=9eb3de84e4) | Dec 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [2aef9deafb](https://linux-hardware.org/?probe=2aef9deafb) | Dec 10, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | [3cfc2b72b4](https://linux-hardware.org/?probe=3cfc2b72b4) | Dec 10, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [c0797a823b](https://linux-hardware.org/?probe=c0797a823b) | Dec 10, 2023 |
| HP            | Laptop 15-da0xxx            | [2722000dd3](https://linux-hardware.org/?probe=2722000dd3) | Dec 10, 2023 |
| Lenovo        | Legion S7 16ARHA7 82UG      | [d6ec80c299](https://linux-hardware.org/?probe=d6ec80c299) | Dec 10, 2023 |
| HP            | ZBook Fury 15 G7 Mobile ... | [d31e9bc5eb](https://linux-hardware.org/?probe=d31e9bc5eb) | Dec 10, 2023 |
| Dell          | Latitude 7440               | [2aef8e5157](https://linux-hardware.org/?probe=2aef8e5157) | Dec 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [96a56fd534](https://linux-hardware.org/?probe=96a56fd534) | Dec 09, 2023 |
| ASUSTek       | P552LA                      | [cbe77e84b7](https://linux-hardware.org/?probe=cbe77e84b7) | Dec 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [a0670e0719](https://linux-hardware.org/?probe=a0670e0719) | Dec 09, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [baa82e571f](https://linux-hardware.org/?probe=baa82e571f) | Dec 09, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [140789380e](https://linux-hardware.org/?probe=140789380e) | Dec 09, 2023 |
| Dell          | Inspiron N5110              | [c7a949f9e8](https://linux-hardware.org/?probe=c7a949f9e8) | Dec 09, 2023 |
| Dell          | Latitude 3480               | [ee6070cfbe](https://linux-hardware.org/?probe=ee6070cfbe) | Dec 09, 2023 |
| Acer          | Predator PH16-71            | [234562596d](https://linux-hardware.org/?probe=234562596d) | Dec 09, 2023 |
| Gigabyte      | AORUS 15 9KF                | [d6386ee775](https://linux-hardware.org/?probe=d6386ee775) | Dec 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [587ff35c26](https://linux-hardware.org/?probe=587ff35c26) | Dec 08, 2023 |
| Acer          | Aspire A515-47              | [363153833d](https://linux-hardware.org/?probe=363153833d) | Dec 08, 2023 |
| Dell          | Latitude 5511               | [9f006edcd8](https://linux-hardware.org/?probe=9f006edcd8) | Dec 08, 2023 |
| HP            | 630                         | [b6c4bc59c1](https://linux-hardware.org/?probe=b6c4bc59c1) | Dec 08, 2023 |
| Dell          | Latitude E6430              | [dee39185ec](https://linux-hardware.org/?probe=dee39185ec) | Dec 08, 2023 |
| MSI           | Katana GF76 11UD            | [a489e0db56](https://linux-hardware.org/?probe=a489e0db56) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2cc6eaff05](https://linux-hardware.org/?probe=2cc6eaff05) | Dec 08, 2023 |
| MSI           | Katana GF76 11UD            | [0f09b2440c](https://linux-hardware.org/?probe=0f09b2440c) | Dec 08, 2023 |
| HUAWEI        | MRGF-XX                     | [ec03f0452e](https://linux-hardware.org/?probe=ec03f0452e) | Dec 08, 2023 |
| HUAWEI        | MRGF-XX                     | [88fc932f99](https://linux-hardware.org/?probe=88fc932f99) | Dec 08, 2023 |
| Dell          | Precision M4700             | [54abe2ce35](https://linux-hardware.org/?probe=54abe2ce35) | Dec 08, 2023 |
| HP            | 15 Notebook PC              | [35b7f5d288](https://linux-hardware.org/?probe=35b7f5d288) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7f76b4716d](https://linux-hardware.org/?probe=7f76b4716d) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0a3a227554](https://linux-hardware.org/?probe=0a3a227554) | Dec 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [cf832dba27](https://linux-hardware.org/?probe=cf832dba27) | Dec 08, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [01f7b97e5d](https://linux-hardware.org/?probe=01f7b97e5d) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [2eb0717bf1](https://linux-hardware.org/?probe=2eb0717bf1) | Dec 07, 2023 |
| Sony          | VPCEB25FX                   | [f2d99590ca](https://linux-hardware.org/?probe=f2d99590ca) | Dec 07, 2023 |
| HUAWEI        | KLVC-WXX9                   | [cd7c131bf1](https://linux-hardware.org/?probe=cd7c131bf1) | Dec 07, 2023 |
| HP            | EliteBook 840 14 inch G1... | [b2fcb75892](https://linux-hardware.org/?probe=b2fcb75892) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [eea00eb64c](https://linux-hardware.org/?probe=eea00eb64c) | Dec 07, 2023 |
| Toshiba       | Satellite C70-B             | [6493c4fcf8](https://linux-hardware.org/?probe=6493c4fcf8) | Dec 07, 2023 |
| Acer          | Aspire A515-45              | [ccc3f6589d](https://linux-hardware.org/?probe=ccc3f6589d) | Dec 07, 2023 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [96ab8b0be8](https://linux-hardware.org/?probe=96ab8b0be8) | Dec 07, 2023 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [8ec5586df3](https://linux-hardware.org/?probe=8ec5586df3) | Dec 07, 2023 |
| HONOR         | HGF-WX6                     | [0ba74f97d0](https://linux-hardware.org/?probe=0ba74f97d0) | Dec 07, 2023 |
| Dell          | System Inspiron N4110       | [72874bcc85](https://linux-hardware.org/?probe=72874bcc85) | Dec 07, 2023 |
| HP            | EliteBook 845 14 inch G1... | [aa4dc92984](https://linux-hardware.org/?probe=aa4dc92984) | Dec 07, 2023 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [3ffedf98eb](https://linux-hardware.org/?probe=3ffedf98eb) | Dec 07, 2023 |
| Dell          | XPS 13 9310                 | [1b786f8834](https://linux-hardware.org/?probe=1b786f8834) | Dec 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [2d483d736b](https://linux-hardware.org/?probe=2d483d736b) | Dec 06, 2023 |
| Dell          | XPS 13 9310                 | [2e32594a3f](https://linux-hardware.org/?probe=2e32594a3f) | Dec 06, 2023 |
| Lenovo        | ThinkPad T490s 20NYS7K90... | [65ec6660cc](https://linux-hardware.org/?probe=65ec6660cc) | Dec 06, 2023 |
| Packard Be... | EasyNote TSX66HR            | [8ca6149044](https://linux-hardware.org/?probe=8ca6149044) | Dec 06, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [7376c1f4cf](https://linux-hardware.org/?probe=7376c1f4cf) | Dec 06, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [0c0833952d](https://linux-hardware.org/?probe=0c0833952d) | Dec 06, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [f87c61387d](https://linux-hardware.org/?probe=f87c61387d) | Dec 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [5940ba1d2c](https://linux-hardware.org/?probe=5940ba1d2c) | Dec 06, 2023 |
| Toshiba       | Satellite C70-B             | [ea76b3e92c](https://linux-hardware.org/?probe=ea76b3e92c) | Dec 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [fc51759095](https://linux-hardware.org/?probe=fc51759095) | Dec 06, 2023 |
| HUAWEI        | RLEF-XX                     | [519c5e78fc](https://linux-hardware.org/?probe=519c5e78fc) | Dec 06, 2023 |
| HUAWEI        | KLVL-WXXW                   | [3c655a8eed](https://linux-hardware.org/?probe=3c655a8eed) | Dec 05, 2023 |
| Dell          | Precision 7720              | [da0616987d](https://linux-hardware.org/?probe=da0616987d) | Dec 05, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [de12499622](https://linux-hardware.org/?probe=de12499622) | Dec 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [ad7bb46855](https://linux-hardware.org/?probe=ad7bb46855) | Dec 05, 2023 |
| Dell          | Inspiron 3593               | [3a07569e5f](https://linux-hardware.org/?probe=3a07569e5f) | Dec 05, 2023 |
| Acer          | TravelMate P414-51          | [bc31600bfa](https://linux-hardware.org/?probe=bc31600bfa) | Dec 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [997c250e85](https://linux-hardware.org/?probe=997c250e85) | Dec 05, 2023 |
| ASUSTek       | GL553VD                     | [578cbbda94](https://linux-hardware.org/?probe=578cbbda94) | Dec 05, 2023 |
| Dell          | Latitude E7440              | [48aff5ace0](https://linux-hardware.org/?probe=48aff5ace0) | Dec 05, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [1cfd81f715](https://linux-hardware.org/?probe=1cfd81f715) | Dec 05, 2023 |
| Apple         | MacBookPro11,5              | [749492541f](https://linux-hardware.org/?probe=749492541f) | Dec 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [6e9230f8ab](https://linux-hardware.org/?probe=6e9230f8ab) | Dec 05, 2023 |
| Dell          | G7 7588                     | [8564f8e395](https://linux-hardware.org/?probe=8564f8e395) | Dec 05, 2023 |
| Lenovo        | ThinkPad T480 20L50011US    | [ac97a3fe1c](https://linux-hardware.org/?probe=ac97a3fe1c) | Dec 05, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [fe13325e26](https://linux-hardware.org/?probe=fe13325e26) | Dec 05, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [b8a831d450](https://linux-hardware.org/?probe=b8a831d450) | Dec 04, 2023 |
| HP            | 630                         | [7d372bb7da](https://linux-hardware.org/?probe=7d372bb7da) | Dec 04, 2023 |
| Lenovo        | Legion 5 17IMH05 82B3       | [a8c094f376](https://linux-hardware.org/?probe=a8c094f376) | Dec 04, 2023 |
| Acer          | Swift SF314-58G             | [14862c0964](https://linux-hardware.org/?probe=14862c0964) | Dec 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [3965451e6d](https://linux-hardware.org/?probe=3965451e6d) | Dec 04, 2023 |
| Acer          | Swift SFE16-42              | [f61134a2d0](https://linux-hardware.org/?probe=f61134a2d0) | Dec 04, 2023 |
| Dell          | Latitude 5420               | [b3ebc9b0fc](https://linux-hardware.org/?probe=b3ebc9b0fc) | Dec 04, 2023 |
| MSI           | Prestige 15 A12UD           | [b19937fb48](https://linux-hardware.org/?probe=b19937fb48) | Dec 04, 2023 |
| MSI           | Prestige 15 A12UD           | [0c9a3a5cae](https://linux-hardware.org/?probe=0c9a3a5cae) | Dec 04, 2023 |
| Dell          | XPS 15 9530                 | [e6d446fcd3](https://linux-hardware.org/?probe=e6d446fcd3) | Dec 04, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [ff7bf1a3cc](https://linux-hardware.org/?probe=ff7bf1a3cc) | Dec 04, 2023 |
| Lenovo        | Yoga Pro 9 14IRP8 83BU      | [1e1ea2cc1d](https://linux-hardware.org/?probe=1e1ea2cc1d) | Dec 04, 2023 |
| Valve         | Jupiter                     | [0caac1007d](https://linux-hardware.org/?probe=0caac1007d) | Dec 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [ccf7855510](https://linux-hardware.org/?probe=ccf7855510) | Dec 03, 2023 |
| Alienware     | M17x                        | [f1c871bbd9](https://linux-hardware.org/?probe=f1c871bbd9) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [7b5f2ca2f9](https://linux-hardware.org/?probe=7b5f2ca2f9) | Dec 03, 2023 |
| Lenovo        | ThinkPad S3-S440 20AYCTO... | [151a3ceaf0](https://linux-hardware.org/?probe=151a3ceaf0) | Dec 03, 2023 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | [2ffb70a1ca](https://linux-hardware.org/?probe=2ffb70a1ca) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [f8a528e1d6](https://linux-hardware.org/?probe=f8a528e1d6) | Dec 03, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [20e77986a2](https://linux-hardware.org/?probe=20e77986a2) | Dec 03, 2023 |
| MSI           | Thin GF63 12HW              | [0612c99f8a](https://linux-hardware.org/?probe=0612c99f8a) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a7c5eb788c](https://linux-hardware.org/?probe=a7c5eb788c) | Dec 03, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [20a5a6a137](https://linux-hardware.org/?probe=20a5a6a137) | Dec 03, 2023 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | [5f96e00c00](https://linux-hardware.org/?probe=5f96e00c00) | Dec 03, 2023 |
| Acer          | Swift SF314-58G             | [d2a73d55eb](https://linux-hardware.org/?probe=d2a73d55eb) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [e3255e030f](https://linux-hardware.org/?probe=e3255e030f) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [da6b435afa](https://linux-hardware.org/?probe=da6b435afa) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [fe6c19062f](https://linux-hardware.org/?probe=fe6c19062f) | Dec 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [b85f62262a](https://linux-hardware.org/?probe=b85f62262a) | Dec 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6189dc268f](https://linux-hardware.org/?probe=6189dc268f) | Dec 02, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [983698f613](https://linux-hardware.org/?probe=983698f613) | Dec 02, 2023 |
| Lenovo        | ThinkPad T480s 20L7001SM... | [da99e083aa](https://linux-hardware.org/?probe=da99e083aa) | Dec 02, 2023 |
| Lenovo        | ThinkPad E15 20RD0019IX     | [5d53fe03da](https://linux-hardware.org/?probe=5d53fe03da) | Dec 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7b5d061328](https://linux-hardware.org/?probe=7b5d061328) | Dec 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [1729d2c4c1](https://linux-hardware.org/?probe=1729d2c4c1) | Dec 02, 2023 |
| Dell          | Inspiron 15-3565            | [6e0eb386a4](https://linux-hardware.org/?probe=6e0eb386a4) | Dec 02, 2023 |
| Dell          | Latitude 3540               | [64067574ad](https://linux-hardware.org/?probe=64067574ad) | Dec 02, 2023 |
| Lenovo        | ThinkPad T460s 20FAS09H0... | [94274c6313](https://linux-hardware.org/?probe=94274c6313) | Dec 02, 2023 |
| Acer          | Aspire A515-45              | [9875097d6a](https://linux-hardware.org/?probe=9875097d6a) | Dec 01, 2023 |
| Dell          | Inspiron 7720               | [974a2661e2](https://linux-hardware.org/?probe=974a2661e2) | Dec 01, 2023 |
| TUXEDO        | InfinityBook Pro 14 Gen6    | [997f545600](https://linux-hardware.org/?probe=997f545600) | Dec 01, 2023 |
| Dynabook      | PORTEGE X50-G               | [65a2f2f3d5](https://linux-hardware.org/?probe=65a2f2f3d5) | Dec 01, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [bf9f891fe4](https://linux-hardware.org/?probe=bf9f891fe4) | Dec 01, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [b5086b8a65](https://linux-hardware.org/?probe=b5086b8a65) | Dec 01, 2023 |
| HP            | Pavilion Notebook           | [06fdc9d8e6](https://linux-hardware.org/?probe=06fdc9d8e6) | Dec 01, 2023 |
| ASUSTek       | X555LAB                     | [b60a0a3ed7](https://linux-hardware.org/?probe=b60a0a3ed7) | Dec 01, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [100228341f](https://linux-hardware.org/?probe=100228341f) | Dec 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [deba3c2073](https://linux-hardware.org/?probe=deba3c2073) | Nov 30, 2023 |
| Lenovo        | IdeaPad 305-15IBD 80NJ      | [c7a78a1510](https://linux-hardware.org/?probe=c7a78a1510) | Nov 30, 2023 |
| Apple         | MacBook4,1                  | [72fc73581b](https://linux-hardware.org/?probe=72fc73581b) | Nov 30, 2023 |
| HP            | ProBook 4540s               | [e1e15771c1](https://linux-hardware.org/?probe=e1e15771c1) | Nov 30, 2023 |
| Timi          | A35S                        | [3c967bd86d](https://linux-hardware.org/?probe=3c967bd86d) | Nov 30, 2023 |
| Lenovo        | Z51-70 80K6                 | [e7fab4df3b](https://linux-hardware.org/?probe=e7fab4df3b) | Nov 30, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [f2dc650bdf](https://linux-hardware.org/?probe=f2dc650bdf) | Nov 30, 2023 |
| Dell          | G15 5515                    | [25c732d6aa](https://linux-hardware.org/?probe=25c732d6aa) | Nov 30, 2023 |
| Dell          | G15 5511                    | [f77d3ad016](https://linux-hardware.org/?probe=f77d3ad016) | Nov 30, 2023 |
| Lenovo        | Yoga 14sARE 2020 82A8       | [13d2cf2679](https://linux-hardware.org/?probe=13d2cf2679) | Nov 30, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [cbe557a601](https://linux-hardware.org/?probe=cbe557a601) | Nov 30, 2023 |
| Dell          | XPS 9320                    | [e4ca1d9f5f](https://linux-hardware.org/?probe=e4ca1d9f5f) | Nov 30, 2023 |
| Dell          | Latitude 3480               | [f83ad2bb01](https://linux-hardware.org/?probe=f83ad2bb01) | Nov 30, 2023 |
| Avell High... | B.ON                        | [22a1430347](https://linux-hardware.org/?probe=22a1430347) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d9b203868f](https://linux-hardware.org/?probe=d9b203868f) | Nov 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [6596326097](https://linux-hardware.org/?probe=6596326097) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7db0c2781b](https://linux-hardware.org/?probe=7db0c2781b) | Nov 29, 2023 |
| Apple         | MacBook4,1                  | [ea63175ae6](https://linux-hardware.org/?probe=ea63175ae6) | Nov 29, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BE09    | [33b3b8ed10](https://linux-hardware.org/?probe=33b3b8ed10) | Nov 29, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [4fb92d7fe0](https://linux-hardware.org/?probe=4fb92d7fe0) | Nov 29, 2023 |
| Samsung       | RF511/RF411/RF711           | [4446f12e33](https://linux-hardware.org/?probe=4446f12e33) | Nov 29, 2023 |
| ASUSTek       | ASUS TUF Gaming A16 FA61... | [fa60a82ab5](https://linux-hardware.org/?probe=fa60a82ab5) | Nov 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [50fb1dbbfb](https://linux-hardware.org/?probe=50fb1dbbfb) | Nov 29, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | [a5caeab77f](https://linux-hardware.org/?probe=a5caeab77f) | Nov 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [5e08371b05](https://linux-hardware.org/?probe=5e08371b05) | Nov 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [c4bd54d16b](https://linux-hardware.org/?probe=c4bd54d16b) | Nov 29, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [61876cd7a5](https://linux-hardware.org/?probe=61876cd7a5) | Nov 29, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [248ac55d99](https://linux-hardware.org/?probe=248ac55d99) | Nov 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3302CEA... | [31b8894b55](https://linux-hardware.org/?probe=31b8894b55) | Nov 29, 2023 |
| Dell          | Inspiron 15 3530            | [410e2cc867](https://linux-hardware.org/?probe=410e2cc867) | Nov 29, 2023 |
| HP            | Elite x2 1012 G1            | [1fda4e1f6d](https://linux-hardware.org/?probe=1fda4e1f6d) | Nov 28, 2023 |
| Lenovo        | ThinkPad X13 Gen 3 21BNC... | [97719198b9](https://linux-hardware.org/?probe=97719198b9) | Nov 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9d88b4ad0b](https://linux-hardware.org/?probe=9d88b4ad0b) | Nov 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [184a3ca616](https://linux-hardware.org/?probe=184a3ca616) | Nov 28, 2023 |
| MSI           | Summit E14Evo A12M          | [32b533e055](https://linux-hardware.org/?probe=32b533e055) | Nov 28, 2023 |
| Apple         | MacBookPro11,1              | [e8fadc04f4](https://linux-hardware.org/?probe=e8fadc04f4) | Nov 28, 2023 |
| HP            | ProBook 445 G7              | [979fcdaea6](https://linux-hardware.org/?probe=979fcdaea6) | Nov 28, 2023 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [7be81f9e9c](https://linux-hardware.org/?probe=7be81f9e9c) | Nov 28, 2023 |
| HP            | ZBook 14 G2                 | [124f1ff011](https://linux-hardware.org/?probe=124f1ff011) | Nov 28, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [62b0e92532](https://linux-hardware.org/?probe=62b0e92532) | Nov 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0390B    | [9b37545fa9](https://linux-hardware.org/?probe=9b37545fa9) | Nov 28, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [f813230b08](https://linux-hardware.org/?probe=f813230b08) | Nov 27, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [f8cdbfddcd](https://linux-hardware.org/?probe=f8cdbfddcd) | Nov 27, 2023 |
| HP            | Laptop 15s-eq1xxx           | [0769357573](https://linux-hardware.org/?probe=0769357573) | Nov 27, 2023 |
| HONOR         | BMH-WCX9                    | [62d142db95](https://linux-hardware.org/?probe=62d142db95) | Nov 27, 2023 |
| HP            | EliteBook 650 15.6 inch ... | [6418e60f5a](https://linux-hardware.org/?probe=6418e60f5a) | Nov 27, 2023 |
| HP            | EliteBook 850 G6            | [597c5faf3a](https://linux-hardware.org/?probe=597c5faf3a) | Nov 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5fabcb33c4](https://linux-hardware.org/?probe=5fabcb33c4) | Nov 27, 2023 |
| Dell          | G15 5515                    | [b33a8c3a2e](https://linux-hardware.org/?probe=b33a8c3a2e) | Nov 27, 2023 |
| Dell          | Latitude 7490               | [70a7c438a1](https://linux-hardware.org/?probe=70a7c438a1) | Nov 27, 2023 |
| Lenovo        | 15ARE05 81W4                | [4fa9ab8a76](https://linux-hardware.org/?probe=4fa9ab8a76) | Nov 27, 2023 |
| Dell          | Inspiron 5566               | [df3eed7cc0](https://linux-hardware.org/?probe=df3eed7cc0) | Nov 27, 2023 |
| Teclast       | F6S                         | [d8c3190c92](https://linux-hardware.org/?probe=d8c3190c92) | Nov 27, 2023 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [23d18fc15e](https://linux-hardware.org/?probe=23d18fc15e) | Nov 27, 2023 |
| HP            | Notebook                    | [be0de1221c](https://linux-hardware.org/?probe=be0de1221c) | Nov 26, 2023 |
| Apple         | MacBook10,1                 | [78c3cc842b](https://linux-hardware.org/?probe=78c3cc842b) | Nov 26, 2023 |
| HP            | Laptop 15-bw0xx             | [542c0ce906](https://linux-hardware.org/?probe=542c0ce906) | Nov 26, 2023 |
| HUAWEI        | HVY-WXX9                    | [e083bf134c](https://linux-hardware.org/?probe=e083bf134c) | Nov 26, 2023 |
| HP            | Laptop 15-dy2xxx            | [858c641fcf](https://linux-hardware.org/?probe=858c641fcf) | Nov 26, 2023 |
| Dell          | Precision M3800             | [a01e02361f](https://linux-hardware.org/?probe=a01e02361f) | Nov 26, 2023 |
| Lenovo        | ThinkPad X270 20HN0015GE    | [68ead98f75](https://linux-hardware.org/?probe=68ead98f75) | Nov 26, 2023 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | [ce1806eec5](https://linux-hardware.org/?probe=ce1806eec5) | Nov 26, 2023 |
| Lenovo        | G510 20238                  | [3f9a7e29e7](https://linux-hardware.org/?probe=3f9a7e29e7) | Nov 26, 2023 |
| HP            | 250 G1                      | [ac68122660](https://linux-hardware.org/?probe=ac68122660) | Nov 26, 2023 |
| HUAWEI        | RLEF-XX                     | [626b08dbe0](https://linux-hardware.org/?probe=626b08dbe0) | Nov 26, 2023 |
| Lenovo        | Unknown                     | [504a4bd033](https://linux-hardware.org/?probe=504a4bd033) | Nov 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [ce68d047a6](https://linux-hardware.org/?probe=ce68d047a6) | Nov 26, 2023 |
| Unknown       | Unknown                     | [9bebf014dd](https://linux-hardware.org/?probe=9bebf014dd) | Nov 26, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [78b8e2f560](https://linux-hardware.org/?probe=78b8e2f560) | Nov 26, 2023 |
| MSI           | PS63 Modern 8RC             | [d647ccba36](https://linux-hardware.org/?probe=d647ccba36) | Nov 26, 2023 |
| Dell          | XPS 15 9570                 | [8e243668e7](https://linux-hardware.org/?probe=8e243668e7) | Nov 26, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [1e704edcd6](https://linux-hardware.org/?probe=1e704edcd6) | Nov 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [e18bd022e8](https://linux-hardware.org/?probe=e18bd022e8) | Nov 25, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [c887e86fe4](https://linux-hardware.org/?probe=c887e86fe4) | Nov 25, 2023 |
| Apple         | MacBookPro9,2               | [ab9cf7394e](https://linux-hardware.org/?probe=ab9cf7394e) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [36e2df7f72](https://linux-hardware.org/?probe=36e2df7f72) | Nov 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [2188d0c4b8](https://linux-hardware.org/?probe=2188d0c4b8) | Nov 25, 2023 |
| MSI           | Thin GF63 12HW              | [82a4c6642b](https://linux-hardware.org/?probe=82a4c6642b) | Nov 25, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [9e623760a1](https://linux-hardware.org/?probe=9e623760a1) | Nov 25, 2023 |
| Lenovo        | ThinkPad T470p 20J6CTO1W... | [8f6ce26933](https://linux-hardware.org/?probe=8f6ce26933) | Nov 25, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [6d1874da45](https://linux-hardware.org/?probe=6d1874da45) | Nov 25, 2023 |
| Acer          | Swift SFE16-42              | [6b2a075d5a](https://linux-hardware.org/?probe=6b2a075d5a) | Nov 25, 2023 |
| Matsushita... | CF-30FCDALAM                | [94d60b91d5](https://linux-hardware.org/?probe=94d60b91d5) | Nov 25, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [6c397edda9](https://linux-hardware.org/?probe=6c397edda9) | Nov 25, 2023 |
| Apple         | MacBookPro14,1              | [390152e044](https://linux-hardware.org/?probe=390152e044) | Nov 25, 2023 |
| HP            | Compaq CQ58                 | [51198853ca](https://linux-hardware.org/?probe=51198853ca) | Nov 25, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [cc4ce2ca20](https://linux-hardware.org/?probe=cc4ce2ca20) | Nov 25, 2023 |
| Lenovo        | G510 20238                  | [75a5b58cb8](https://linux-hardware.org/?probe=75a5b58cb8) | Nov 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [082c36ab01](https://linux-hardware.org/?probe=082c36ab01) | Nov 25, 2023 |
| Acer          | Aspire A315-24P             | [30586cdeb5](https://linux-hardware.org/?probe=30586cdeb5) | Nov 24, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [2b2ac91a50](https://linux-hardware.org/?probe=2b2ac91a50) | Nov 24, 2023 |
| Lenovo        | Legion 9 16IRX8 83AG        | [f511dac11e](https://linux-hardware.org/?probe=f511dac11e) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [3443df47ab](https://linux-hardware.org/?probe=3443df47ab) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [f8eb14af89](https://linux-hardware.org/?probe=f8eb14af89) | Nov 24, 2023 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [2852a62f61](https://linux-hardware.org/?probe=2852a62f61) | Nov 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [5289268737](https://linux-hardware.org/?probe=5289268737) | Nov 24, 2023 |
| Timi          | RedmiBook 15                | [5bcef78473](https://linux-hardware.org/?probe=5bcef78473) | Nov 24, 2023 |
| Timi          | RedmiBook 15                | [3edc0a53ce](https://linux-hardware.org/?probe=3edc0a53ce) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [145e6fbb42](https://linux-hardware.org/?probe=145e6fbb42) | Nov 24, 2023 |
| Gigabyte      | B550M AORUS ELITE AX        | [6ec8b667b0](https://linux-hardware.org/?probe=6ec8b667b0) | Nov 23, 2023 |
| Lenovo        | IdeaPad Slim 3 15IAN8 82... | [8b107cb438](https://linux-hardware.org/?probe=8b107cb438) | Nov 23, 2023 |
| SLIMBOOK      | PROX14-AMD                  | [cbd8cb44fe](https://linux-hardware.org/?probe=cbd8cb44fe) | Nov 23, 2023 |
| MSI           | Stealth GS66 12UGS          | [080042a410](https://linux-hardware.org/?probe=080042a410) | Nov 23, 2023 |
| MSI           | Stealth GS66 12UGS          | [f82ecf4011](https://linux-hardware.org/?probe=f82ecf4011) | Nov 23, 2023 |
| HP            | ProBook 4430s               | [847fb6fb22](https://linux-hardware.org/?probe=847fb6fb22) | Nov 23, 2023 |
| Dell          | Latitude E5450              | [fad9a32575](https://linux-hardware.org/?probe=fad9a32575) | Nov 23, 2023 |
| Acer          | Aspire A515-57              | [676da26c54](https://linux-hardware.org/?probe=676da26c54) | Nov 23, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [48677cfae1](https://linux-hardware.org/?probe=48677cfae1) | Nov 23, 2023 |
| Dell          | Inspiron 1525               | [a4927b394e](https://linux-hardware.org/?probe=a4927b394e) | Nov 23, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20CDCTO... | [3a3915012e](https://linux-hardware.org/?probe=3a3915012e) | Nov 23, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bf30102553](https://linux-hardware.org/?probe=bf30102553) | Nov 23, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [8806cbd1e7](https://linux-hardware.org/?probe=8806cbd1e7) | Nov 23, 2023 |
| HUAWEI        | NbDE-WXX9                   | [c5d9332805](https://linux-hardware.org/?probe=c5d9332805) | Nov 23, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [a749e7b6c5](https://linux-hardware.org/?probe=a749e7b6c5) | Nov 23, 2023 |
| Apple         | MacBookAir7,2               | [f7e288a635](https://linux-hardware.org/?probe=f7e288a635) | Nov 23, 2023 |
| HP            | ProBook 4430s               | [1b34dd379f](https://linux-hardware.org/?probe=1b34dd379f) | Nov 23, 2023 |
| ASUSTek       | E403SA                      | [01b3727f1a](https://linux-hardware.org/?probe=01b3727f1a) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | [0cc77ec093](https://linux-hardware.org/?probe=0cc77ec093) | Nov 23, 2023 |
| Apple         | MacBookPro11,3              | [f918e70d3e](https://linux-hardware.org/?probe=f918e70d3e) | Nov 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [97b04abe7f](https://linux-hardware.org/?probe=97b04abe7f) | Nov 22, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [20aa8a380c](https://linux-hardware.org/?probe=20aa8a380c) | Nov 22, 2023 |
| Acer          | Aspire AV15-51              | [6ca712a0bb](https://linux-hardware.org/?probe=6ca712a0bb) | Nov 22, 2023 |
| Acer          | Aspire AV15-51              | [09108a2bc4](https://linux-hardware.org/?probe=09108a2bc4) | Nov 22, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | [91b3ed41e0](https://linux-hardware.org/?probe=91b3ed41e0) | Nov 22, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [7e25b00cb4](https://linux-hardware.org/?probe=7e25b00cb4) | Nov 22, 2023 |
| Dell          | Latitude 7480               | [e6a9139a06](https://linux-hardware.org/?probe=e6a9139a06) | Nov 22, 2023 |
| Dell          | Latitude 7480               | [9cc316e781](https://linux-hardware.org/?probe=9cc316e781) | Nov 22, 2023 |
| Dell          | Latitude 5280               | [c2d1b79aeb](https://linux-hardware.org/?probe=c2d1b79aeb) | Nov 22, 2023 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [8cf21a227b](https://linux-hardware.org/?probe=8cf21a227b) | Nov 22, 2023 |
| Apple         | MacBookPro11,4              | [007d6a928b](https://linux-hardware.org/?probe=007d6a928b) | Nov 21, 2023 |
| Samsung       | 300V3A/300V4A/300V5A        | [5a2df7d067](https://linux-hardware.org/?probe=5a2df7d067) | Nov 21, 2023 |
| Gigabyte      | AX370-Gaming-CF se1         | [541752a388](https://linux-hardware.org/?probe=541752a388) | Nov 21, 2023 |
| HP            | ProBook 4540s               | [59a7759558](https://linux-hardware.org/?probe=59a7759558) | Nov 21, 2023 |
| Dell          | Inspiron 3593               | [3e6c300167](https://linux-hardware.org/?probe=3e6c300167) | Nov 21, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | [43be1d8514](https://linux-hardware.org/?probe=43be1d8514) | Nov 21, 2023 |
| Toshiba       | IS 1412                     | [0ed3e8195d](https://linux-hardware.org/?probe=0ed3e8195d) | Nov 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [2474e3d0e7](https://linux-hardware.org/?probe=2474e3d0e7) | Nov 21, 2023 |
| Lenovo        | B580 20144                  | [634e12256a](https://linux-hardware.org/?probe=634e12256a) | Nov 21, 2023 |
| Apple         | MacBookPro15,2              | [eb1dc5dbda](https://linux-hardware.org/?probe=eb1dc5dbda) | Nov 21, 2023 |
| ASUSTek       | ROG Strix G713IM_G713IM     | [bacf466ce6](https://linux-hardware.org/?probe=bacf466ce6) | Nov 21, 2023 |
| HUAWEI        | HVY-WXX9                    | [efba109da8](https://linux-hardware.org/?probe=efba109da8) | Nov 21, 2023 |
| Lenovo        | ThinkPad T490s 20NY000JM... | [a8668f58d9](https://linux-hardware.org/?probe=a8668f58d9) | Nov 21, 2023 |
| eMachines     | E725 V1.03                  | [bd5b32a320](https://linux-hardware.org/?probe=bd5b32a320) | Nov 20, 2023 |
| Apple         | MacBookPro15,2              | [07e0aacd4c](https://linux-hardware.org/?probe=07e0aacd4c) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [69d60bac42](https://linux-hardware.org/?probe=69d60bac42) | Nov 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [bf2a6c9451](https://linux-hardware.org/?probe=bf2a6c9451) | Nov 20, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [26ebeb2504](https://linux-hardware.org/?probe=26ebeb2504) | Nov 20, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [251174d0cc](https://linux-hardware.org/?probe=251174d0cc) | Nov 20, 2023 |
| Dell          | Vostro 14 5410              | [af794f8249](https://linux-hardware.org/?probe=af794f8249) | Nov 20, 2023 |
| HP            | Laptop 17-ca0xxx            | [f284bf043f](https://linux-hardware.org/?probe=f284bf043f) | Nov 20, 2023 |
| Apple         | MacBookPro11,1              | [5dfd18dfc1](https://linux-hardware.org/?probe=5dfd18dfc1) | Nov 20, 2023 |
| Apple         | MacBookPro11,1              | [b53cd95828](https://linux-hardware.org/?probe=b53cd95828) | Nov 20, 2023 |
| Jumper        | EZbook                      | [f41c8192dc](https://linux-hardware.org/?probe=f41c8192dc) | Nov 20, 2023 |
| HUAWEI        | BOD-WXX9                    | [13e6e37377](https://linux-hardware.org/?probe=13e6e37377) | Nov 20, 2023 |
| BTO           | 17X1183                     | [6cd57738ff](https://linux-hardware.org/?probe=6cd57738ff) | Nov 20, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [3dfe3f0994](https://linux-hardware.org/?probe=3dfe3f0994) | Nov 20, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | [209008741e](https://linux-hardware.org/?probe=209008741e) | Nov 20, 2023 |
| Apple         | MacBookPro4,1               | [908ca19a6d](https://linux-hardware.org/?probe=908ca19a6d) | Nov 19, 2023 |
| eMachines     | E725 V1.03                  | [bd29f2ff41](https://linux-hardware.org/?probe=bd29f2ff41) | Nov 19, 2023 |
| Acer          | Aspire A515-56              | [f8d242150d](https://linux-hardware.org/?probe=f8d242150d) | Nov 19, 2023 |
| HP            | Laptop 14-df0xxx            | [aaa013c1b1](https://linux-hardware.org/?probe=aaa013c1b1) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K340... | [f118e9b0a7](https://linux-hardware.org/?probe=f118e9b0a7) | Nov 19, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [b528cb2139](https://linux-hardware.org/?probe=b528cb2139) | Nov 19, 2023 |
| Acer          | Aspire A515-44              | [d17022be69](https://linux-hardware.org/?probe=d17022be69) | Nov 19, 2023 |
| Dell          | Inspiron 5548               | [63fec114db](https://linux-hardware.org/?probe=63fec114db) | Nov 19, 2023 |
| Notebook      | NL5xRU                      | [7b5f6c8151](https://linux-hardware.org/?probe=7b5f6c8151) | Nov 19, 2023 |
| Acer          | Nitro AN517-41              | [c5f0fec07b](https://linux-hardware.org/?probe=c5f0fec07b) | Nov 19, 2023 |
| Dell          | XPS 15 9560                 | [be841a1ee6](https://linux-hardware.org/?probe=be841a1ee6) | Nov 19, 2023 |
| Dell          | Inspiron 7375               | [b72b8abe13](https://linux-hardware.org/?probe=b72b8abe13) | Nov 19, 2023 |
| ASUSTek       | TP500LB                     | [697dfb4387](https://linux-hardware.org/?probe=697dfb4387) | Nov 19, 2023 |
| Acer          | Aspire 5750G                | [eb5f5d4b24](https://linux-hardware.org/?probe=eb5f5d4b24) | Nov 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [355e11bb80](https://linux-hardware.org/?probe=355e11bb80) | Nov 19, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [cc9d93b28f](https://linux-hardware.org/?probe=cc9d93b28f) | Nov 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [07aecd2eb5](https://linux-hardware.org/?probe=07aecd2eb5) | Nov 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [ab4faca57e](https://linux-hardware.org/?probe=ab4faca57e) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0f7f8ed2e1](https://linux-hardware.org/?probe=0f7f8ed2e1) | Nov 19, 2023 |
| Gigabyte      | B550M K                     | [989886ee56](https://linux-hardware.org/?probe=989886ee56) | Nov 19, 2023 |
| Dell          | Precision M6500             | [9bd0aab68e](https://linux-hardware.org/?probe=9bd0aab68e) | Nov 19, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [f5c9812962](https://linux-hardware.org/?probe=f5c9812962) | Nov 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [94962a7ceb](https://linux-hardware.org/?probe=94962a7ceb) | Nov 19, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c7d86840e8](https://linux-hardware.org/?probe=c7d86840e8) | Nov 19, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [d957a1a8c5](https://linux-hardware.org/?probe=d957a1a8c5) | Nov 19, 2023 |
| Dell          | XPS 13 9310                 | [ee45badecb](https://linux-hardware.org/?probe=ee45badecb) | Nov 18, 2023 |
| Lenovo        | ThinkPad T530 24297XG       | [2b1944e111](https://linux-hardware.org/?probe=2b1944e111) | Nov 18, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [aec2f789cf](https://linux-hardware.org/?probe=aec2f789cf) | Nov 18, 2023 |
| Timi          | TM1701                      | [f14bab873b](https://linux-hardware.org/?probe=f14bab873b) | Nov 18, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [3ad49c55c8](https://linux-hardware.org/?probe=3ad49c55c8) | Nov 18, 2023 |
| Alienware     | Area-51m R2                 | [0ed781b812](https://linux-hardware.org/?probe=0ed781b812) | Nov 18, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [80f392bd0d](https://linux-hardware.org/?probe=80f392bd0d) | Nov 18, 2023 |
| Medion        | Akoya E4214 MD99570         | [c194cb14f2](https://linux-hardware.org/?probe=c194cb14f2) | Nov 18, 2023 |
| Acer          | TravelMate 5742Z            | [382f8528fb](https://linux-hardware.org/?probe=382f8528fb) | Nov 18, 2023 |
| Acer          | Aspire A315-53G             | [7f9669bf0b](https://linux-hardware.org/?probe=7f9669bf0b) | Nov 18, 2023 |
| Dell          | Inspiron M5010              | [77b9c09532](https://linux-hardware.org/?probe=77b9c09532) | Nov 18, 2023 |
| MSI           | Prestige 14Evo A12M         | [39c61d33cc](https://linux-hardware.org/?probe=39c61d33cc) | Nov 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [95624a1d82](https://linux-hardware.org/?probe=95624a1d82) | Nov 18, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [f73e299a89](https://linux-hardware.org/?probe=f73e299a89) | Nov 18, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [cd775f0d29](https://linux-hardware.org/?probe=cd775f0d29) | Nov 18, 2023 |
| Apple         | MacBookPro14,3              | [c8b5a88695](https://linux-hardware.org/?probe=c8b5a88695) | Nov 18, 2023 |
| Dell          | Inspiron 7591               | [edb7712542](https://linux-hardware.org/?probe=edb7712542) | Nov 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | [ee6f116e8a](https://linux-hardware.org/?probe=ee6f116e8a) | Nov 17, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [0c33961f58](https://linux-hardware.org/?probe=0c33961f58) | Nov 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1aa00f4008](https://linux-hardware.org/?probe=1aa00f4008) | Nov 17, 2023 |
| Dell          | Precision 5510              | [a6c623e57a](https://linux-hardware.org/?probe=a6c623e57a) | Nov 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [8f0b8a5f62](https://linux-hardware.org/?probe=8f0b8a5f62) | Nov 17, 2023 |
| Dell          | Latitude 5520               | [234733a1e4](https://linux-hardware.org/?probe=234733a1e4) | Nov 17, 2023 |
| Lenovo        | ThinkPad T460s 20F9CTO1W... | [51e880c4fd](https://linux-hardware.org/?probe=51e880c4fd) | Nov 17, 2023 |
| ASUSTek       | N551JW                      | [b05c08e4ab](https://linux-hardware.org/?probe=b05c08e4ab) | Nov 17, 2023 |
| Google        | Kano                        | [3a0f7846c4](https://linux-hardware.org/?probe=3a0f7846c4) | Nov 17, 2023 |
| Google        | Kano                        | [0c5e699794](https://linux-hardware.org/?probe=0c5e699794) | Nov 17, 2023 |
| Dell          | Inspiron 7566               | [5709fca952](https://linux-hardware.org/?probe=5709fca952) | Nov 17, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [2af4aec091](https://linux-hardware.org/?probe=2af4aec091) | Nov 17, 2023 |
| Schenker      | VIA 15 Pro                  | [f11c1dcd90](https://linux-hardware.org/?probe=f11c1dcd90) | Nov 17, 2023 |
| Acer          | Nitro AN515-43              | [a9d9ea53da](https://linux-hardware.org/?probe=a9d9ea53da) | Nov 17, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5077cde917](https://linux-hardware.org/?probe=5077cde917) | Nov 16, 2023 |
| HP            | 250 G8 Notebook PC          | [731de0aa50](https://linux-hardware.org/?probe=731de0aa50) | Nov 16, 2023 |
| Dell          | Vostro 3300                 | [90986d4cf6](https://linux-hardware.org/?probe=90986d4cf6) | Nov 16, 2023 |
| HUAWEI        | BOD-WXX9                    | [9096161802](https://linux-hardware.org/?probe=9096161802) | Nov 16, 2023 |
| HP            | Laptop 15s-eq2xxx           | [6461e4f7af](https://linux-hardware.org/?probe=6461e4f7af) | Nov 16, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [4c58693314](https://linux-hardware.org/?probe=4c58693314) | Nov 16, 2023 |
| Acer          | Aspire A515-45              | [d1800f3356](https://linux-hardware.org/?probe=d1800f3356) | Nov 16, 2023 |
| Samsung       | 550P5C/550P7C               | [343e6ecd28](https://linux-hardware.org/?probe=343e6ecd28) | Nov 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [f1ba9de4ad](https://linux-hardware.org/?probe=f1ba9de4ad) | Nov 16, 2023 |
| Lenovo        | ThinkPad Edge E320 1298R... | [535d92743c](https://linux-hardware.org/?probe=535d92743c) | Nov 16, 2023 |
| Lenovo        | ThinkPad Edge E320 1298R... | [331f7da246](https://linux-hardware.org/?probe=331f7da246) | Nov 16, 2023 |
| Lenovo        | ThinkPad Edge E535 32605... | [a42aa89d19](https://linux-hardware.org/?probe=a42aa89d19) | Nov 16, 2023 |
| Jumper        | EZbook                      | [844843779e](https://linux-hardware.org/?probe=844843779e) | Nov 16, 2023 |
| HP            | ENVY Laptop 17-cr1xxx       | [806f9b287d](https://linux-hardware.org/?probe=806f9b287d) | Nov 16, 2023 |
| Dell          | Latitude E6440              | [a0a06323e0](https://linux-hardware.org/?probe=a0a06323e0) | Nov 16, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [af8edff0b6](https://linux-hardware.org/?probe=af8edff0b6) | Nov 15, 2023 |
| HP            | EliteBook 735 G5            | [49ea9a3b35](https://linux-hardware.org/?probe=49ea9a3b35) | Nov 15, 2023 |
| HP            | Laptop 14-ck0xxx            | [b082377950](https://linux-hardware.org/?probe=b082377950) | Nov 15, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [ffc320e32c](https://linux-hardware.org/?probe=ffc320e32c) | Nov 15, 2023 |
| Acer          | Aspire AV15-52              | [0eb415a325](https://linux-hardware.org/?probe=0eb415a325) | Nov 15, 2023 |
| ASUSTek       | ROG Strix G531GU_GL531GU    | [d4815cabeb](https://linux-hardware.org/?probe=d4815cabeb) | Nov 15, 2023 |
| HP            | ProBook 6570b               | [06cd45bab5](https://linux-hardware.org/?probe=06cd45bab5) | Nov 15, 2023 |
| Google        | Kohaku                      | [ac5c19b11f](https://linux-hardware.org/?probe=ac5c19b11f) | Nov 15, 2023 |
| HUAWEI        | HBB-WX9                     | [d3d635372e](https://linux-hardware.org/?probe=d3d635372e) | Nov 15, 2023 |
| Lenovo        | ThinkPad T490 20N2000NRT    | [fa750668a7](https://linux-hardware.org/?probe=fa750668a7) | Nov 15, 2023 |
| HP            | Laptop 15s-fr2xxx           | [be79137b4b](https://linux-hardware.org/?probe=be79137b4b) | Nov 15, 2023 |
| Google        | Nami                        | [53f0d03d36](https://linux-hardware.org/?probe=53f0d03d36) | Nov 15, 2023 |
| MSI           | GP72 6QF                    | [89f6458e06](https://linux-hardware.org/?probe=89f6458e06) | Nov 15, 2023 |
| Apple         | MacBookPro5,5               | [870fedf2eb](https://linux-hardware.org/?probe=870fedf2eb) | Nov 15, 2023 |
| Alienware     | 14                          | [3f12c6cbcd](https://linux-hardware.org/?probe=3f12c6cbcd) | Nov 15, 2023 |
| Acer          | Predator PH315-53           | [f2a6eea13e](https://linux-hardware.org/?probe=f2a6eea13e) | Nov 14, 2023 |
| HP            | EliteBook 840 G2            | [64cfcced5b](https://linux-hardware.org/?probe=64cfcced5b) | Nov 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [df8a98ef2c](https://linux-hardware.org/?probe=df8a98ef2c) | Nov 14, 2023 |
| Dell          | Latitude 5580               | [3f5fba6417](https://linux-hardware.org/?probe=3f5fba6417) | Nov 14, 2023 |
| Lenovo        | IdeaPad Slim 5 14IAH8 83... | [e33ce14e30](https://linux-hardware.org/?probe=e33ce14e30) | Nov 14, 2023 |
| MSI           | Prestige 14 A10SC           | [59ad7e7e27](https://linux-hardware.org/?probe=59ad7e7e27) | Nov 14, 2023 |
| MSI           | Prestige 14 A10SC           | [6b1a5452f8](https://linux-hardware.org/?probe=6b1a5452f8) | Nov 14, 2023 |
| Dell          | Inspiron 3543               | [305bd0b03f](https://linux-hardware.org/?probe=305bd0b03f) | Nov 14, 2023 |
| Dell          | XPS 17 9720                 | [d7e50818b4](https://linux-hardware.org/?probe=d7e50818b4) | Nov 14, 2023 |
| Dell          | Latitude 7390 2-in-1        | [f92b2d58ec](https://linux-hardware.org/?probe=f92b2d58ec) | Nov 14, 2023 |
| Dell          | Vostro 15 5510              | [c3944a39df](https://linux-hardware.org/?probe=c3944a39df) | Nov 14, 2023 |
| Intel Clie... | LAPRC710                    | [75dbf98926](https://linux-hardware.org/?probe=75dbf98926) | Nov 14, 2023 |
| Apple         | MacBookPro14,2              | [6ce3699c41](https://linux-hardware.org/?probe=6ce3699c41) | Nov 14, 2023 |
| Apple         | MacBookPro14,2              | [3e5fd22123](https://linux-hardware.org/?probe=3e5fd22123) | Nov 14, 2023 |
| Acer          | Aspire A515-57              | [7b7cf69882](https://linux-hardware.org/?probe=7b7cf69882) | Nov 14, 2023 |
| Dell          | Latitude 5430               | [9aed6642da](https://linux-hardware.org/?probe=9aed6642da) | Nov 14, 2023 |
| HP            | EliteBook 840 G2            | [4b522b316d](https://linux-hardware.org/?probe=4b522b316d) | Nov 14, 2023 |
| Acer          | Aspire A515-57              | [bb0f5fe1e2](https://linux-hardware.org/?probe=bb0f5fe1e2) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [392c269f06](https://linux-hardware.org/?probe=392c269f06) | Nov 14, 2023 |
| ASUSTek       | TUF Gaming FA506II_FA506... | [2e60a77926](https://linux-hardware.org/?probe=2e60a77926) | Nov 14, 2023 |
| ASUSTek       | X550JK                      | [200a783f1a](https://linux-hardware.org/?probe=200a783f1a) | Nov 14, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [db881a2b07](https://linux-hardware.org/?probe=db881a2b07) | Nov 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [1baa2ce489](https://linux-hardware.org/?probe=1baa2ce489) | Nov 13, 2023 |
| HP            | EliteBook 840 G2            | [74c6e6efae](https://linux-hardware.org/?probe=74c6e6efae) | Nov 13, 2023 |
| HP            | ENVY Laptop 13-aq0xxx       | [b43a43b268](https://linux-hardware.org/?probe=b43a43b268) | Nov 13, 2023 |
| HP            | Pavilion Notebook           | [9b7cd04c85](https://linux-hardware.org/?probe=9b7cd04c85) | Nov 13, 2023 |
| HUAWEI        | BOD-WXX9                    | [113193bb57](https://linux-hardware.org/?probe=113193bb57) | Nov 13, 2023 |
| HP            | Pavilion dv5                | [f08fc1d52e](https://linux-hardware.org/?probe=f08fc1d52e) | Nov 13, 2023 |
| Dell          | Inspiron 1525               | [f292f81323](https://linux-hardware.org/?probe=f292f81323) | Nov 13, 2023 |
| MSI           | Katana GF66 12UC            | [bd156c9515](https://linux-hardware.org/?probe=bd156c9515) | Nov 13, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [e8803a2d63](https://linux-hardware.org/?probe=e8803a2d63) | Nov 13, 2023 |
| Alienware     | m18 R1                      | [f4c5c9d2ec](https://linux-hardware.org/?probe=f4c5c9d2ec) | Nov 13, 2023 |
| ASUSTek       | F3Sv                        | [7cc246f28e](https://linux-hardware.org/?probe=7cc246f28e) | Nov 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [d0549c695d](https://linux-hardware.org/?probe=d0549c695d) | Nov 13, 2023 |
| HUAWEI        | HVY-WXX9                    | [b0ed26f85a](https://linux-hardware.org/?probe=b0ed26f85a) | Nov 13, 2023 |
| Apple         | MacBookPro11,3              | [4338ec3c3e](https://linux-hardware.org/?probe=4338ec3c3e) | Nov 13, 2023 |
| Apple         | MacBookPro8,1               | [c538f19c9e](https://linux-hardware.org/?probe=c538f19c9e) | Nov 13, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [661492882b](https://linux-hardware.org/?probe=661492882b) | Nov 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [47d681f4e6](https://linux-hardware.org/?probe=47d681f4e6) | Nov 13, 2023 |
| HP            | Laptop 14-cm0xxx            | [e2b369a154](https://linux-hardware.org/?probe=e2b369a154) | Nov 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [11995be92f](https://linux-hardware.org/?probe=11995be92f) | Nov 13, 2023 |
| Apple         | MacBookPro11,3              | [6a545de7a7](https://linux-hardware.org/?probe=6a545de7a7) | Nov 13, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [78b909aa81](https://linux-hardware.org/?probe=78b909aa81) | Nov 12, 2023 |
| Timi          | A35S                        | [f225083df7](https://linux-hardware.org/?probe=f225083df7) | Nov 12, 2023 |
| Apple         | MacBookPro5,5               | [87e3c4fa90](https://linux-hardware.org/?probe=87e3c4fa90) | Nov 12, 2023 |
| HP            | Laptop 15s-fr2xxx           | [f5d3c3e682](https://linux-hardware.org/?probe=f5d3c3e682) | Nov 12, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [3172a3c77c](https://linux-hardware.org/?probe=3172a3c77c) | Nov 12, 2023 |
| Dell          | Precision M3800             | [b84dd534c9](https://linux-hardware.org/?probe=b84dd534c9) | Nov 12, 2023 |
| HP            | EliteBook 840 G4            | [2651393e60](https://linux-hardware.org/?probe=2651393e60) | Nov 12, 2023 |
| Toshiba       | Satellite S55-B             | [bcc2e19a3a](https://linux-hardware.org/?probe=bcc2e19a3a) | Nov 12, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [cadbea6f61](https://linux-hardware.org/?probe=cadbea6f61) | Nov 12, 2023 |
| HP            | 630                         | [ccc318ee31](https://linux-hardware.org/?probe=ccc318ee31) | Nov 12, 2023 |
| HP            | 630                         | [df3b4ec5db](https://linux-hardware.org/?probe=df3b4ec5db) | Nov 12, 2023 |
| Dell          | Latitude 3420               | [5e829237c5](https://linux-hardware.org/?probe=5e829237c5) | Nov 12, 2023 |
| HP            | Pavilion dv6700             | [27e526a564](https://linux-hardware.org/?probe=27e526a564) | Nov 12, 2023 |
| Linx          | LINX1010B                   | [aa641d2775](https://linux-hardware.org/?probe=aa641d2775) | Nov 12, 2023 |
| Toshiba       | Satellite C70-B             | [a9534bcb6d](https://linux-hardware.org/?probe=a9534bcb6d) | Nov 12, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | [63c1b9a13e](https://linux-hardware.org/?probe=63c1b9a13e) | Nov 12, 2023 |
| Apple         | MacBookPro12,1              | [982139b13a](https://linux-hardware.org/?probe=982139b13a) | Nov 11, 2023 |
| Irbis         | NB211                       | [2d4aa9a87a](https://linux-hardware.org/?probe=2d4aa9a87a) | Nov 11, 2023 |
| Dell          | Latitude 3540               | [a28b72369b](https://linux-hardware.org/?probe=a28b72369b) | Nov 11, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | [6fcb2ca951](https://linux-hardware.org/?probe=6fcb2ca951) | Nov 11, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [99b19c5226](https://linux-hardware.org/?probe=99b19c5226) | Nov 11, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [0ba73e8306](https://linux-hardware.org/?probe=0ba73e8306) | Nov 11, 2023 |
| Dell          | Inspiron 5570               | [8ab7ca4fa6](https://linux-hardware.org/?probe=8ab7ca4fa6) | Nov 11, 2023 |
| HUAWEI        | HLY-WX9XX                   | [641f011e49](https://linux-hardware.org/?probe=641f011e49) | Nov 11, 2023 |
| Samsung       | QX311/QX411/QX412/QX511     | [7e9005c96d](https://linux-hardware.org/?probe=7e9005c96d) | Nov 11, 2023 |
| HP            | ProBook 450 G3              | [a749127ad5](https://linux-hardware.org/?probe=a749127ad5) | Nov 11, 2023 |
| HP            | ProBook 450 G3              | [ed70ccc9b1](https://linux-hardware.org/?probe=ed70ccc9b1) | Nov 11, 2023 |
| Apple         | MacBookPro9,2               | [9e6140b883](https://linux-hardware.org/?probe=9e6140b883) | Nov 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [5fcb6b8815](https://linux-hardware.org/?probe=5fcb6b8815) | Nov 11, 2023 |
| Lenovo        | ThinkPad P50s 20FL000EMS    | [81d1c107cc](https://linux-hardware.org/?probe=81d1c107cc) | Nov 11, 2023 |
| Samsung       | 305V4A/305V5A/3415VA        | [0ce9bba443](https://linux-hardware.org/?probe=0ce9bba443) | Nov 11, 2023 |
| Dell          | Inspiron 5559               | [86d8fabf27](https://linux-hardware.org/?probe=86d8fabf27) | Nov 11, 2023 |
| Lenovo        | ThinkPad T440p 20AN00DEU... | [99fde80a79](https://linux-hardware.org/?probe=99fde80a79) | Nov 11, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [4fd542edf2](https://linux-hardware.org/?probe=4fd542edf2) | Nov 11, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [7d86488ec6](https://linux-hardware.org/?probe=7d86488ec6) | Nov 11, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [885ca0663e](https://linux-hardware.org/?probe=885ca0663e) | Nov 11, 2023 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | [ba3527587e](https://linux-hardware.org/?probe=ba3527587e) | Nov 11, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d9e81e4df6](https://linux-hardware.org/?probe=d9e81e4df6) | Nov 10, 2023 |
| HP            | 255 15.6 inch G10           | [1f507d83b5](https://linux-hardware.org/?probe=1f507d83b5) | Nov 10, 2023 |
| HUAWEI        | BOD-WXX9                    | [4e81c16b62](https://linux-hardware.org/?probe=4e81c16b62) | Nov 10, 2023 |
| HP            | Pavilion Notebook           | [0dfa7c7cde](https://linux-hardware.org/?probe=0dfa7c7cde) | Nov 10, 2023 |
| HP            | Dragonfly Pro               | [c68e8688a2](https://linux-hardware.org/?probe=c68e8688a2) | Nov 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [2a8696e0f5](https://linux-hardware.org/?probe=2a8696e0f5) | Nov 10, 2023 |
| Apple         | MacBookPro11,4              | [029e4d74e4](https://linux-hardware.org/?probe=029e4d74e4) | Nov 10, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | [671a836d23](https://linux-hardware.org/?probe=671a836d23) | Nov 10, 2023 |
| Apple         | MacBookAir6,2               | [f5147fc0f5](https://linux-hardware.org/?probe=f5147fc0f5) | Nov 10, 2023 |
| HP            | ProBook 440 G7              | [fab830af79](https://linux-hardware.org/?probe=fab830af79) | Nov 10, 2023 |
| Dell          | XPS 13 9370                 | [8d5b1b0080](https://linux-hardware.org/?probe=8d5b1b0080) | Nov 10, 2023 |
| HP            | ProBook 640 G1              | [63a4283226](https://linux-hardware.org/?probe=63a4283226) | Nov 10, 2023 |
| Lenovo        | Y520-15IKBA 80WY            | [2a5b34f6e6](https://linux-hardware.org/?probe=2a5b34f6e6) | Nov 10, 2023 |
| Notebook      | NS5x_NS7xAU                 | [0ecd643e18](https://linux-hardware.org/?probe=0ecd643e18) | Nov 10, 2023 |
| Lenovo        | ThinkPad T490 20N2000NRT    | [fe5dd30b3d](https://linux-hardware.org/?probe=fe5dd30b3d) | Nov 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [9f3d17b672](https://linux-hardware.org/?probe=9f3d17b672) | Nov 10, 2023 |
| Lenovo        | ThinkPad T470s 20HFCTO1W... | [a5b20e26b9](https://linux-hardware.org/?probe=a5b20e26b9) | Nov 10, 2023 |
| Lenovo        | ThinkPad T490 20N3S7AA00    | [b4fd9fd045](https://linux-hardware.org/?probe=b4fd9fd045) | Nov 10, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [cfc1427577](https://linux-hardware.org/?probe=cfc1427577) | Nov 10, 2023 |
| Sony          | VGN-FZ140E                  | [6c88ea3af0](https://linux-hardware.org/?probe=6c88ea3af0) | Nov 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [2f1c3e00ef](https://linux-hardware.org/?probe=2f1c3e00ef) | Nov 10, 2023 |
| HP            | 250 G1                      | [a06122606d](https://linux-hardware.org/?probe=a06122606d) | Nov 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [60d38c4fae](https://linux-hardware.org/?probe=60d38c4fae) | Nov 09, 2023 |
| ASUSTek       | K95VM                       | [a58011f5bc](https://linux-hardware.org/?probe=a58011f5bc) | Nov 09, 2023 |
| Lenovo        | ThinkPad T420 42361H7       | [0f1bd55fbf](https://linux-hardware.org/?probe=0f1bd55fbf) | Nov 09, 2023 |
| Lenovo        | ThinkPad X250 20CLAOMLIN    | [88967f98bd](https://linux-hardware.org/?probe=88967f98bd) | Nov 09, 2023 |
| ASUSTek       | ROG Strix G713IM_G713IM     | [95d3d270b2](https://linux-hardware.org/?probe=95d3d270b2) | Nov 09, 2023 |
| Lenovo        | G580 20150                  | [8c11a6230e](https://linux-hardware.org/?probe=8c11a6230e) | Nov 09, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [840241bcdd](https://linux-hardware.org/?probe=840241bcdd) | Nov 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [d73d435640](https://linux-hardware.org/?probe=d73d435640) | Nov 09, 2023 |
| ASUSTek       | TX300CA                     | [b6176e4138](https://linux-hardware.org/?probe=b6176e4138) | Nov 09, 2023 |
| Acer          | Aspire A515-57              | [99456a20b8](https://linux-hardware.org/?probe=99456a20b8) | Nov 09, 2023 |
| Lenovo        | ThinkPad P16s Gen 2 21K9... | [80062f7576](https://linux-hardware.org/?probe=80062f7576) | Nov 09, 2023 |
| Apple         | MacBookAir6,1               | [e3e009b3ce](https://linux-hardware.org/?probe=e3e009b3ce) | Nov 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [80431017dc](https://linux-hardware.org/?probe=80431017dc) | Nov 09, 2023 |
| Notebook      | NJ50_70CU                   | [7ffd65d532](https://linux-hardware.org/?probe=7ffd65d532) | Nov 09, 2023 |
| Valve         | Jupiter                     | [2e7ed7b6c8](https://linux-hardware.org/?probe=2e7ed7b6c8) | Nov 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [9ae1f9c05f](https://linux-hardware.org/?probe=9ae1f9c05f) | Nov 08, 2023 |
| Notebook      | NJ50_70CU                   | [f48a185656](https://linux-hardware.org/?probe=f48a185656) | Nov 08, 2023 |
| Dell          | XPS 13 9370                 | [b6038fadcd](https://linux-hardware.org/?probe=b6038fadcd) | Nov 08, 2023 |
| Acer          | Nitro AN515-54              | [fbdaa89128](https://linux-hardware.org/?probe=fbdaa89128) | Nov 08, 2023 |
| HP            | Compaq Presario A900        | [1593f3e8b1](https://linux-hardware.org/?probe=1593f3e8b1) | Nov 08, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [63e0b9fc88](https://linux-hardware.org/?probe=63e0b9fc88) | Nov 08, 2023 |
| Sony          | SVF15N17CXB                 | [e8497bf6f6](https://linux-hardware.org/?probe=e8497bf6f6) | Nov 08, 2023 |
| HP            | Laptop 15-rb0xx             | [3d2ec07a57](https://linux-hardware.org/?probe=3d2ec07a57) | Nov 08, 2023 |
| HP            | Laptop 15-rb0xx             | [eb27db3944](https://linux-hardware.org/?probe=eb27db3944) | Nov 08, 2023 |
| MSI           | Creator M16 B12VE           | [fec840c7fd](https://linux-hardware.org/?probe=fec840c7fd) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [5cfd80c832](https://linux-hardware.org/?probe=5cfd80c832) | Nov 08, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [675571ef30](https://linux-hardware.org/?probe=675571ef30) | Nov 08, 2023 |
| Acer          | Swift SF314-512             | [895d64deec](https://linux-hardware.org/?probe=895d64deec) | Nov 08, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [ec440eff42](https://linux-hardware.org/?probe=ec440eff42) | Nov 08, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [4345e63ae2](https://linux-hardware.org/?probe=4345e63ae2) | Nov 08, 2023 |
| Acer          | Predator PH16-71            | [5fcac9e7de](https://linux-hardware.org/?probe=5fcac9e7de) | Nov 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [da7463eff8](https://linux-hardware.org/?probe=da7463eff8) | Nov 07, 2023 |
| Dell          | Latitude E5470              | [bbbdcac07b](https://linux-hardware.org/?probe=bbbdcac07b) | Nov 07, 2023 |
| Unknown       | Unknown                     | [fe49c747a0](https://linux-hardware.org/?probe=fe49c747a0) | Nov 07, 2023 |
| Unknown       | Unknown                     | [bfe1505cfc](https://linux-hardware.org/?probe=bfe1505cfc) | Nov 07, 2023 |
| HP            | Laptop 15-ef2xxx            | [b0d207b140](https://linux-hardware.org/?probe=b0d207b140) | Nov 07, 2023 |
| Apple         | MacBookPro13,1              | [e5ae7e8a94](https://linux-hardware.org/?probe=e5ae7e8a94) | Nov 07, 2023 |
| Dell          | Vostro 3500                 | [c85bdae7e5](https://linux-hardware.org/?probe=c85bdae7e5) | Nov 07, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [e874ddf25c](https://linux-hardware.org/?probe=e874ddf25c) | Nov 07, 2023 |
| Dell          | Latitude E5470              | [19fc06d0b2](https://linux-hardware.org/?probe=19fc06d0b2) | Nov 07, 2023 |
| ASUSTek       | N552VW                      | [b8f226f7f0](https://linux-hardware.org/?probe=b8f226f7f0) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [ce00056643](https://linux-hardware.org/?probe=ce00056643) | Nov 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [0cc84d3b82](https://linux-hardware.org/?probe=0cc84d3b82) | Nov 07, 2023 |
| Samsung       | 550P5C/550P7C               | [c7d84926af](https://linux-hardware.org/?probe=c7d84926af) | Nov 07, 2023 |
| Acer          | Aspire A315-41              | [e275461ffe](https://linux-hardware.org/?probe=e275461ffe) | Nov 07, 2023 |
| ASUSTek       | X55A                        | [705bc0e6a5](https://linux-hardware.org/?probe=705bc0e6a5) | Nov 07, 2023 |
| Dell          | Precision M4600             | [0aabbcfa0b](https://linux-hardware.org/?probe=0aabbcfa0b) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | [53fd99e067](https://linux-hardware.org/?probe=53fd99e067) | Nov 06, 2023 |
| Unknown       | Unknown                     | [1545b5a7bb](https://linux-hardware.org/?probe=1545b5a7bb) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | [d8adc9ee0d](https://linux-hardware.org/?probe=d8adc9ee0d) | Nov 06, 2023 |
| Dell          | XPS 15 9500                 | [e07422acdd](https://linux-hardware.org/?probe=e07422acdd) | Nov 06, 2023 |
| HP            | EliteBook 850 G3            | [dadc34f1bb](https://linux-hardware.org/?probe=dadc34f1bb) | Nov 06, 2023 |
| HP            | EliteBook 850 G3            | [b5b4c26e1e](https://linux-hardware.org/?probe=b5b4c26e1e) | Nov 06, 2023 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [a7c5843f17](https://linux-hardware.org/?probe=a7c5843f17) | Nov 06, 2023 |
| Timi          | Mi NoteBook Pro             | [a8a46eb495](https://linux-hardware.org/?probe=a8a46eb495) | Nov 06, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | [88cc97d0be](https://linux-hardware.org/?probe=88cc97d0be) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | [f09ace6b9d](https://linux-hardware.org/?probe=f09ace6b9d) | Nov 06, 2023 |
| HP            | G61                         | [65f7664fe3](https://linux-hardware.org/?probe=65f7664fe3) | Nov 06, 2023 |
| Samsung       | 550P5C/550P7C               | [f87e3a97c4](https://linux-hardware.org/?probe=f87e3a97c4) | Nov 06, 2023 |
| Acer          | Aspire A315-53              | [3daa9909b3](https://linux-hardware.org/?probe=3daa9909b3) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [d643312744](https://linux-hardware.org/?probe=d643312744) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d61e270082](https://linux-hardware.org/?probe=d61e270082) | Nov 06, 2023 |
| Dell          | Inspiron 5459               | [fc242f51bf](https://linux-hardware.org/?probe=fc242f51bf) | Nov 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [4bfe797838](https://linux-hardware.org/?probe=4bfe797838) | Nov 05, 2023 |
| ASUSTek       | X550WA                      | [8c15da796b](https://linux-hardware.org/?probe=8c15da796b) | Nov 05, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | [92ef56cc92](https://linux-hardware.org/?probe=92ef56cc92) | Nov 05, 2023 |
| Acer          | Predator PT516-52s          | [30b7a47643](https://linux-hardware.org/?probe=30b7a47643) | Nov 05, 2023 |
| Dell          | Inspiron 7559               | [da97d12548](https://linux-hardware.org/?probe=da97d12548) | Nov 05, 2023 |
| Toshiba       | Satellite L515              | [70a66852db](https://linux-hardware.org/?probe=70a66852db) | Nov 05, 2023 |
| Toshiba       | Satellite L845              | [4dc7e8931e](https://linux-hardware.org/?probe=4dc7e8931e) | Nov 05, 2023 |
| Dell          | Latitude E7440              | [5a151e929f](https://linux-hardware.org/?probe=5a151e929f) | Nov 05, 2023 |
| Lenovo        | S145-15IWL 81MV             | [d38fdaf0eb](https://linux-hardware.org/?probe=d38fdaf0eb) | Nov 04, 2023 |
| Lenovo        | ThinkPad W550s 20E2000PM... | [1294d54c1a](https://linux-hardware.org/?probe=1294d54c1a) | Nov 04, 2023 |
| MSI           | Modern 15 B7M               | [b4a588e60e](https://linux-hardware.org/?probe=b4a588e60e) | Nov 04, 2023 |
| HP            | ProBook 430 G8 Notebook ... | [5d8cae0407](https://linux-hardware.org/?probe=5d8cae0407) | Nov 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [b390f8cd05](https://linux-hardware.org/?probe=b390f8cd05) | Nov 04, 2023 |
| Apple         | MacBook5,2                  | [1d8dad6600](https://linux-hardware.org/?probe=1d8dad6600) | Nov 04, 2023 |
| HP            | EliteBook 850 G5            | [a7f0f43604](https://linux-hardware.org/?probe=a7f0f43604) | Nov 04, 2023 |
| Sony          | VPCEH3J1E                   | [e0ae745034](https://linux-hardware.org/?probe=e0ae745034) | Nov 04, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | [d0d84fed9a](https://linux-hardware.org/?probe=d0d84fed9a) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | [60187ba0be](https://linux-hardware.org/?probe=60187ba0be) | Nov 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [85e528f1bf](https://linux-hardware.org/?probe=85e528f1bf) | Nov 04, 2023 |
| HP            | EliteBook 840 G4            | [5abff2e87a](https://linux-hardware.org/?probe=5abff2e87a) | Nov 04, 2023 |
| Dell          | Inspiron 15 3511            | [8c23fbf7d1](https://linux-hardware.org/?probe=8c23fbf7d1) | Nov 04, 2023 |
| POV           | I102A                       | [955f97d47e](https://linux-hardware.org/?probe=955f97d47e) | Nov 04, 2023 |
| Irbis         | NB211                       | [694ca0f127](https://linux-hardware.org/?probe=694ca0f127) | Nov 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [85a38e7906](https://linux-hardware.org/?probe=85a38e7906) | Nov 03, 2023 |
| HUAWEI        | KLVL-WXX9                   | [61342b31ea](https://linux-hardware.org/?probe=61342b31ea) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [7b64212148](https://linux-hardware.org/?probe=7b64212148) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | [f4bae2d5b5](https://linux-hardware.org/?probe=f4bae2d5b5) | Nov 03, 2023 |
| Timi          | A35S                        | [d62fbb6f83](https://linux-hardware.org/?probe=d62fbb6f83) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | [0e71b912ec](https://linux-hardware.org/?probe=0e71b912ec) | Nov 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ff0d013246](https://linux-hardware.org/?probe=ff0d013246) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [f9bdbf6371](https://linux-hardware.org/?probe=f9bdbf6371) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [bcea72b22f](https://linux-hardware.org/?probe=bcea72b22f) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [00a8b74f46](https://linux-hardware.org/?probe=00a8b74f46) | Nov 03, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [6a2591b5e9](https://linux-hardware.org/?probe=6a2591b5e9) | Nov 03, 2023 |
| Lenovo        | ThinkBook Plus G3 IAP 21... | [a6fabd1a6d](https://linux-hardware.org/?probe=a6fabd1a6d) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | [28990f206a](https://linux-hardware.org/?probe=28990f206a) | Nov 03, 2023 |
| Irbis         | NB211                       | [3ebca4338a](https://linux-hardware.org/?probe=3ebca4338a) | Nov 03, 2023 |
| HP            | Pavilion Notebook           | [f23e44229f](https://linux-hardware.org/?probe=f23e44229f) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [94cdd979b2](https://linux-hardware.org/?probe=94cdd979b2) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [0929326be0](https://linux-hardware.org/?probe=0929326be0) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [5149df3a58](https://linux-hardware.org/?probe=5149df3a58) | Nov 03, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [1b43feda1f](https://linux-hardware.org/?probe=1b43feda1f) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [26bc5f025c](https://linux-hardware.org/?probe=26bc5f025c) | Nov 02, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [741bcd1343](https://linux-hardware.org/?probe=741bcd1343) | Nov 02, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | [56bbf7c0bb](https://linux-hardware.org/?probe=56bbf7c0bb) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [bb1da2575d](https://linux-hardware.org/?probe=bb1da2575d) | Nov 02, 2023 |
| Lenovo        | ThinkBook Plus G3 IAP 21... | [c6634f090f](https://linux-hardware.org/?probe=c6634f090f) | Nov 02, 2023 |
| Acer          | Aspire A715-41G             | [664191098d](https://linux-hardware.org/?probe=664191098d) | Nov 02, 2023 |
| HUAWEI        | BOM-WXX9                    | [97ca7a0bfd](https://linux-hardware.org/?probe=97ca7a0bfd) | Nov 02, 2023 |
| Lenovo        | ThinkPad T410 2537NT8       | [2d1404f4ae](https://linux-hardware.org/?probe=2d1404f4ae) | Nov 02, 2023 |
| Dell          | Inspiron N5110              | [ad0e3ec9ea](https://linux-hardware.org/?probe=ad0e3ec9ea) | Nov 01, 2023 |
| HP            | ProBook 650 G1              | [60c6e3a5d2](https://linux-hardware.org/?probe=60c6e3a5d2) | Nov 01, 2023 |
| Dell          | G3 3579                     | [0b33f63284](https://linux-hardware.org/?probe=0b33f63284) | Nov 01, 2023 |
| Acer          | TravelMate P259-MG          | [ba3faece8c](https://linux-hardware.org/?probe=ba3faece8c) | Nov 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [685b1b18eb](https://linux-hardware.org/?probe=685b1b18eb) | Nov 01, 2023 |
| Acer          | Nitro AN515-52              | [829c16d044](https://linux-hardware.org/?probe=829c16d044) | Nov 01, 2023 |
| Apple         | MacBookPro16,2              | [37b53d54e8](https://linux-hardware.org/?probe=37b53d54e8) | Nov 01, 2023 |
| Acer          | Aspire E1-572G              | [d347dc93b5](https://linux-hardware.org/?probe=d347dc93b5) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [bbf2002cea](https://linux-hardware.org/?probe=bbf2002cea) | Nov 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7dd972fb0d](https://linux-hardware.org/?probe=7dd972fb0d) | Nov 01, 2023 |
| Acer          | Aspire A715-41G             | [63fa5e90b2](https://linux-hardware.org/?probe=63fa5e90b2) | Nov 01, 2023 |
| Apple         | MacBookPro15,2              | [b724e20965](https://linux-hardware.org/?probe=b724e20965) | Nov 01, 2023 |
| HP            | Laptop 15-fc0xxx            | [d0be3aec4e](https://linux-hardware.org/?probe=d0be3aec4e) | Nov 01, 2023 |
| Lenovo        | ThinkPad L380 20M6S11800    | [06fd1ea497](https://linux-hardware.org/?probe=06fd1ea497) | Nov 01, 2023 |
| Lenovo        | ThinkPad L380 20M6S11800    | [ded89ffc10](https://linux-hardware.org/?probe=ded89ffc10) | Nov 01, 2023 |
| ASUSTek       | X555QG                      | [f047c1d264](https://linux-hardware.org/?probe=f047c1d264) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [0d9316dbcf](https://linux-hardware.org/?probe=0d9316dbcf) | Oct 31, 2023 |
| HUAWEI        | BOHB-WAX9                   | [5da84da52f](https://linux-hardware.org/?probe=5da84da52f) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [aef3dccca0](https://linux-hardware.org/?probe=aef3dccca0) | Oct 31, 2023 |
| Alienware     | 14                          | [e88b7c0ac6](https://linux-hardware.org/?probe=e88b7c0ac6) | Oct 31, 2023 |
| ASUSTek       | X507UA                      | [c52aa98c38](https://linux-hardware.org/?probe=c52aa98c38) | Oct 31, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [af854a07c5](https://linux-hardware.org/?probe=af854a07c5) | Oct 31, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [fadc897ee2](https://linux-hardware.org/?probe=fadc897ee2) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [ebec8d6fd1](https://linux-hardware.org/?probe=ebec8d6fd1) | Oct 31, 2023 |
| Apple         | MacBookPro8,1               | [0ea1a71a53](https://linux-hardware.org/?probe=0ea1a71a53) | Oct 31, 2023 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | [9785ae64c0](https://linux-hardware.org/?probe=9785ae64c0) | Oct 31, 2023 |
| Lenovo        | ThinkPad E470 20H1006KIX    | [d84959fadc](https://linux-hardware.org/?probe=d84959fadc) | Oct 31, 2023 |
| HP            | ProBook 645 G1              | [b637cedab4](https://linux-hardware.org/?probe=b637cedab4) | Oct 31, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [54a64f0a7e](https://linux-hardware.org/?probe=54a64f0a7e) | Oct 31, 2023 |
| Dell          | Latitude 5414               | [fd7b086e1b](https://linux-hardware.org/?probe=fd7b086e1b) | Oct 31, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | [487222ef3e](https://linux-hardware.org/?probe=487222ef3e) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [055e34b095](https://linux-hardware.org/?probe=055e34b095) | Oct 30, 2023 |
| Acer          | Aspire A515-45              | [25431e9c91](https://linux-hardware.org/?probe=25431e9c91) | Oct 30, 2023 |
| ASUSTek       | X555UJ                      | [de6e2775a4](https://linux-hardware.org/?probe=de6e2775a4) | Oct 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S03Q00    | [de24032ac7](https://linux-hardware.org/?probe=de24032ac7) | Oct 30, 2023 |
| Unknown       | Unknown                     | [43e6db0023](https://linux-hardware.org/?probe=43e6db0023) | Oct 30, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [0b129d4a95](https://linux-hardware.org/?probe=0b129d4a95) | Oct 30, 2023 |
| Dell          | Vostro 3525                 | [ad34d5b54f](https://linux-hardware.org/?probe=ad34d5b54f) | Oct 30, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [48f8f53d3e](https://linux-hardware.org/?probe=48f8f53d3e) | Oct 30, 2023 |
| Dell          | Latitude 5490               | [63f4fce332](https://linux-hardware.org/?probe=63f4fce332) | Oct 30, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | [249ea48334](https://linux-hardware.org/?probe=249ea48334) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [6cbfd91e78](https://linux-hardware.org/?probe=6cbfd91e78) | Oct 30, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [8730c3de9d](https://linux-hardware.org/?probe=8730c3de9d) | Oct 30, 2023 |
| Dell          | Precision 3551              | [4f054a63ef](https://linux-hardware.org/?probe=4f054a63ef) | Oct 30, 2023 |
| ASUSTek       | F3Sv                        | [3da2894228](https://linux-hardware.org/?probe=3da2894228) | Oct 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [b1adeb2f86](https://linux-hardware.org/?probe=b1adeb2f86) | Oct 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fe7dbb2385](https://linux-hardware.org/?probe=fe7dbb2385) | Oct 29, 2023 |
| Apple         | MacBookPro15,4              | [09ee918b60](https://linux-hardware.org/?probe=09ee918b60) | Oct 29, 2023 |
| Lenovo        | ThinkPad L14 Gen 4 21H10... | [0a7d468516](https://linux-hardware.org/?probe=0a7d468516) | Oct 29, 2023 |
| HP            | Notebook                    | [79843ed7c3](https://linux-hardware.org/?probe=79843ed7c3) | Oct 29, 2023 |
| Dell          | Precision 5480              | [5df408828c](https://linux-hardware.org/?probe=5df408828c) | Oct 29, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [313770aff1](https://linux-hardware.org/?probe=313770aff1) | Oct 29, 2023 |
| Dell          | Precision M6800             | [a5e2100522](https://linux-hardware.org/?probe=a5e2100522) | Oct 29, 2023 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [1d1a7bd472](https://linux-hardware.org/?probe=1d1a7bd472) | Oct 28, 2023 |
| Thomson       | N14C4WH64                   | [8dd9b1dbde](https://linux-hardware.org/?probe=8dd9b1dbde) | Oct 28, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [da25874b12](https://linux-hardware.org/?probe=da25874b12) | Oct 28, 2023 |
| Apple         | MacBookPro8,1               | [762e9a6d4d](https://linux-hardware.org/?probe=762e9a6d4d) | Oct 28, 2023 |
| Apple         | MacBookPro8,1               | [b4645667a4](https://linux-hardware.org/?probe=b4645667a4) | Oct 28, 2023 |
| HP            | Notebook                    | [791dfef3cc](https://linux-hardware.org/?probe=791dfef3cc) | Oct 28, 2023 |
| HUAWEI        | CREM-WXX9                   | [217aaa00da](https://linux-hardware.org/?probe=217aaa00da) | Oct 28, 2023 |
| Acer          | TravelMate P214-41          | [53659e599e](https://linux-hardware.org/?probe=53659e599e) | Oct 28, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [f78fcbc612](https://linux-hardware.org/?probe=f78fcbc612) | Oct 28, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [5591930fc0](https://linux-hardware.org/?probe=5591930fc0) | Oct 27, 2023 |
| Lenovo        | YogaAir 14s APU8 83AA       | [4f120347b7](https://linux-hardware.org/?probe=4f120347b7) | Oct 27, 2023 |
| Dell          | Precision 5530              | [e707fe59cc](https://linux-hardware.org/?probe=e707fe59cc) | Oct 27, 2023 |
| Acer          | Aspire V5-572P              | [18938afb70](https://linux-hardware.org/?probe=18938afb70) | Oct 27, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [bd82dd57be](https://linux-hardware.org/?probe=bd82dd57be) | Oct 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S69X08    | [61da163866](https://linux-hardware.org/?probe=61da163866) | Oct 27, 2023 |
| Apple         | MacBookPro14,2              | [346fad17ff](https://linux-hardware.org/?probe=346fad17ff) | Oct 27, 2023 |
| Apple         | MacBookPro14,2              | [481d6c83fb](https://linux-hardware.org/?probe=481d6c83fb) | Oct 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [057e350f82](https://linux-hardware.org/?probe=057e350f82) | Oct 27, 2023 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | [a20c6e2c77](https://linux-hardware.org/?probe=a20c6e2c77) | Oct 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [9650e62539](https://linux-hardware.org/?probe=9650e62539) | Oct 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [82ba56a70d](https://linux-hardware.org/?probe=82ba56a70d) | Oct 26, 2023 |
| Dell          | Latitude 5440               | [e7d56ee207](https://linux-hardware.org/?probe=e7d56ee207) | Oct 26, 2023 |
| Dell          | Latitude 7490               | [58324a8dfd](https://linux-hardware.org/?probe=58324a8dfd) | Oct 26, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [3aa43f0bf7](https://linux-hardware.org/?probe=3aa43f0bf7) | Oct 26, 2023 |
| HP            | EliteBook 630 13.3 inch ... | [8f57ab5108](https://linux-hardware.org/?probe=8f57ab5108) | Oct 26, 2023 |
| HP            | Pavilion dv7                | [15526c62b8](https://linux-hardware.org/?probe=15526c62b8) | Oct 26, 2023 |
| Maibenben     | MaiBook M                   | [ccee3b60c7](https://linux-hardware.org/?probe=ccee3b60c7) | Oct 26, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [4506629e6a](https://linux-hardware.org/?probe=4506629e6a) | Oct 26, 2023 |
| Unknown       | Unknown                     | [7d25c7409a](https://linux-hardware.org/?probe=7d25c7409a) | Oct 26, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [38046f165d](https://linux-hardware.org/?probe=38046f165d) | Oct 26, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [7830b3ae27](https://linux-hardware.org/?probe=7830b3ae27) | Oct 26, 2023 |
| Toshiba       | Satellite L75D-A            | [82efb2dd44](https://linux-hardware.org/?probe=82efb2dd44) | Oct 26, 2023 |
| Apple         | MacBookPro15,4              | [751e98cb04](https://linux-hardware.org/?probe=751e98cb04) | Oct 26, 2023 |
| Schenker      | VISION (M23)                | [64cead24ba](https://linux-hardware.org/?probe=64cead24ba) | Oct 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a17a8b4360](https://linux-hardware.org/?probe=a17a8b4360) | Oct 25, 2023 |
| Acer          | Aspire 7750G                | [673c675bc6](https://linux-hardware.org/?probe=673c675bc6) | Oct 25, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [3cf7c10977](https://linux-hardware.org/?probe=3cf7c10977) | Oct 25, 2023 |
| Timi          | TM1701                      | [13801c83a2](https://linux-hardware.org/?probe=13801c83a2) | Oct 25, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [7476940ad0](https://linux-hardware.org/?probe=7476940ad0) | Oct 25, 2023 |
| Packard Be... | EasyNote LE69KB             | [3626d833e9](https://linux-hardware.org/?probe=3626d833e9) | Oct 24, 2023 |
| HP            | Dragonfly Folio 13.5 inc... | [ffb075a639](https://linux-hardware.org/?probe=ffb075a639) | Oct 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3eee01cd16](https://linux-hardware.org/?probe=3eee01cd16) | Oct 24, 2023 |
| Lenovo        | ThinkPad T410 2537NT8       | [52b5addead](https://linux-hardware.org/?probe=52b5addead) | Oct 24, 2023 |
| Dell          | XPS 9315                    | [9246bb9a28](https://linux-hardware.org/?probe=9246bb9a28) | Oct 24, 2023 |
| Apple         | MacBookPro15,1              | [41fd350f12](https://linux-hardware.org/?probe=41fd350f12) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | [ed7e1a1932](https://linux-hardware.org/?probe=ed7e1a1932) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | [84883d560d](https://linux-hardware.org/?probe=84883d560d) | Oct 24, 2023 |
| GPD           | G1621-02                    | [ea3897be17](https://linux-hardware.org/?probe=ea3897be17) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | [37be8caf53](https://linux-hardware.org/?probe=37be8caf53) | Oct 23, 2023 |
| Lenovo        | G500 20236                  | [3effd4e3d3](https://linux-hardware.org/?probe=3effd4e3d3) | Oct 23, 2023 |
| Dell          | Latitude 5320               | [520c2effa3](https://linux-hardware.org/?probe=520c2effa3) | Oct 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8da5e9e836](https://linux-hardware.org/?probe=8da5e9e836) | Oct 23, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | [6d63f6c5ba](https://linux-hardware.org/?probe=6d63f6c5ba) | Oct 23, 2023 |
| TUXEDO        | Unknown                     | [0994b60ab4](https://linux-hardware.org/?probe=0994b60ab4) | Oct 23, 2023 |
| Dell          | G15 5515                    | [16754901cb](https://linux-hardware.org/?probe=16754901cb) | Oct 23, 2023 |
| HP            | ProBook 4530s               | [104df79d8e](https://linux-hardware.org/?probe=104df79d8e) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SS0... | [9877bb17c1](https://linux-hardware.org/?probe=9877bb17c1) | Oct 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2e4786bb32](https://linux-hardware.org/?probe=2e4786bb32) | Oct 23, 2023 |
| Lenovo        | Y50-70 20378                | [6f65dcd448](https://linux-hardware.org/?probe=6f65dcd448) | Oct 23, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [7981b12a61](https://linux-hardware.org/?probe=7981b12a61) | Oct 22, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [705aaea029](https://linux-hardware.org/?probe=705aaea029) | Oct 22, 2023 |
| Dell          | XPS 13 9300                 | [ccf935ca37](https://linux-hardware.org/?probe=ccf935ca37) | Oct 22, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | [38823c0a55](https://linux-hardware.org/?probe=38823c0a55) | Oct 22, 2023 |
| Lenovo        | ThinkPad L13 20R30005RT     | [23a9651432](https://linux-hardware.org/?probe=23a9651432) | Oct 22, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [c725f222a3](https://linux-hardware.org/?probe=c725f222a3) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [92d3be3fff](https://linux-hardware.org/?probe=92d3be3fff) | Oct 22, 2023 |
| Dell          | Venue 11 Pro 5130           | [7105618a0a](https://linux-hardware.org/?probe=7105618a0a) | Oct 22, 2023 |
| Dell          | Venue 11 Pro 5130           | [0b91bab038](https://linux-hardware.org/?probe=0b91bab038) | Oct 22, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [1eed0a53b6](https://linux-hardware.org/?probe=1eed0a53b6) | Oct 22, 2023 |
| Apple         | MacBookPro12,1              | [5d9310d00e](https://linux-hardware.org/?probe=5d9310d00e) | Oct 21, 2023 |
| ASUSTek       | N551JK                      | [863f309154](https://linux-hardware.org/?probe=863f309154) | Oct 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [dca6ad28b3](https://linux-hardware.org/?probe=dca6ad28b3) | Oct 21, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [1f4b7f796f](https://linux-hardware.org/?probe=1f4b7f796f) | Oct 21, 2023 |
| Apple         | MacBookAir4,2               | [dcef0a70af](https://linux-hardware.org/?probe=dcef0a70af) | Oct 21, 2023 |
| Dell          | Latitude E6320              | [c6965e07e3](https://linux-hardware.org/?probe=c6965e07e3) | Oct 21, 2023 |
| HP            | Pavilion Notebook           | [ffeaa7da2f](https://linux-hardware.org/?probe=ffeaa7da2f) | Oct 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [f1b2f555ef](https://linux-hardware.org/?probe=f1b2f555ef) | Oct 21, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | [3afdd1b0da](https://linux-hardware.org/?probe=3afdd1b0da) | Oct 21, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [a149fbf417](https://linux-hardware.org/?probe=a149fbf417) | Oct 21, 2023 |
| ASUSTek       | X442UAR                     | [454f454638](https://linux-hardware.org/?probe=454f454638) | Oct 21, 2023 |
| Dell          | Latitude 7440               | [e0997ac78c](https://linux-hardware.org/?probe=e0997ac78c) | Oct 20, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | [f4f7d19069](https://linux-hardware.org/?probe=f4f7d19069) | Oct 20, 2023 |
| BANGHO        | M7x0K                       | [1f72eb6b91](https://linux-hardware.org/?probe=1f72eb6b91) | Oct 20, 2023 |
| HP            | EliteBook 630 13.3 inch ... | [e1ed7c2ee4](https://linux-hardware.org/?probe=e1ed7c2ee4) | Oct 20, 2023 |
| Dell          | Vostro 14 5410              | [4cb4e5aab9](https://linux-hardware.org/?probe=4cb4e5aab9) | Oct 20, 2023 |
| Dell          | Latitude 7280               | [ec9e688b4e](https://linux-hardware.org/?probe=ec9e688b4e) | Oct 20, 2023 |
| HP            | Pavilion Notebook           | [9d49844572](https://linux-hardware.org/?probe=9d49844572) | Oct 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [aa76e46b18](https://linux-hardware.org/?probe=aa76e46b18) | Oct 20, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [32d375b029](https://linux-hardware.org/?probe=32d375b029) | Oct 20, 2023 |
| Dell          | G7 7700                     | [336bd76568](https://linux-hardware.org/?probe=336bd76568) | Oct 20, 2023 |
| Lenovo        | G500 20236                  | [6e5d214cb8](https://linux-hardware.org/?probe=6e5d214cb8) | Oct 20, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [c96f9ccef3](https://linux-hardware.org/?probe=c96f9ccef3) | Oct 19, 2023 |
| Apple         | MacBookAir5,2               | [deeaf6af5b](https://linux-hardware.org/?probe=deeaf6af5b) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | [15b78585e0](https://linux-hardware.org/?probe=15b78585e0) | Oct 19, 2023 |
| HP            | ProBook 445 G7              | [10fab445ad](https://linux-hardware.org/?probe=10fab445ad) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | [0d2e2856a9](https://linux-hardware.org/?probe=0d2e2856a9) | Oct 19, 2023 |
| ASUSTek       | PRIME X570-P                | [4506612f98](https://linux-hardware.org/?probe=4506612f98) | Oct 19, 2023 |
| Acer          | Aspire A315-57G             | [7e39a647e3](https://linux-hardware.org/?probe=7e39a647e3) | Oct 19, 2023 |
| ASUSTek       | X555QG                      | [e2e11a852f](https://linux-hardware.org/?probe=e2e11a852f) | Oct 19, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [09ad44bf2e](https://linux-hardware.org/?probe=09ad44bf2e) | Oct 19, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8d38f6e16d](https://linux-hardware.org/?probe=8d38f6e16d) | Oct 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [fbb4ce606d](https://linux-hardware.org/?probe=fbb4ce606d) | Oct 19, 2023 |
| Lenovo        | G50-80 80E5                 | [1f244ed949](https://linux-hardware.org/?probe=1f244ed949) | Oct 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [e94e48868c](https://linux-hardware.org/?probe=e94e48868c) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | [abafeadb35](https://linux-hardware.org/?probe=abafeadb35) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | [ab3c18427d](https://linux-hardware.org/?probe=ab3c18427d) | Oct 19, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [a25bc084fc](https://linux-hardware.org/?probe=a25bc084fc) | Oct 19, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | [4d4e3d82fd](https://linux-hardware.org/?probe=4d4e3d82fd) | Oct 18, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [1984a8305d](https://linux-hardware.org/?probe=1984a8305d) | Oct 18, 2023 |
| HP            | EliteBook 860 16 inch G1... | [bde071302f](https://linux-hardware.org/?probe=bde071302f) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [48b90d30be](https://linux-hardware.org/?probe=48b90d30be) | Oct 18, 2023 |
| Dell          | Precision 7680              | [70f6453d4c](https://linux-hardware.org/?probe=70f6453d4c) | Oct 18, 2023 |
| Dell          | XPS 13 9360                 | [dbbedd9f06](https://linux-hardware.org/?probe=dbbedd9f06) | Oct 18, 2023 |
| Samsung       | 670Z5E                      | [65ee0747bc](https://linux-hardware.org/?probe=65ee0747bc) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [04885ecaa3](https://linux-hardware.org/?probe=04885ecaa3) | Oct 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8002AM... | [b8d09ca2f5](https://linux-hardware.org/?probe=b8d09ca2f5) | Oct 18, 2023 |
| Dell          | Latitude 5440               | [2097e4ed5e](https://linux-hardware.org/?probe=2097e4ed5e) | Oct 18, 2023 |
| ASUSTek       | X556UJ                      | [010c7b3e14](https://linux-hardware.org/?probe=010c7b3e14) | Oct 17, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [6193aa3ed1](https://linux-hardware.org/?probe=6193aa3ed1) | Oct 17, 2023 |
| ASUSTek       | X556UJ                      | [e9065ad0d2](https://linux-hardware.org/?probe=e9065ad0d2) | Oct 17, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | [4d69a046ff](https://linux-hardware.org/?probe=4d69a046ff) | Oct 17, 2023 |
| HUAWEI        | KLVL-WXX9                   | [0ca9b4c2bd](https://linux-hardware.org/?probe=0ca9b4c2bd) | Oct 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [660d60e1a8](https://linux-hardware.org/?probe=660d60e1a8) | Oct 17, 2023 |
| HUAWEI        | MACH-WX9                    | [8cb8d0943c](https://linux-hardware.org/?probe=8cb8d0943c) | Oct 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0b4065c185](https://linux-hardware.org/?probe=0b4065c185) | Oct 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [6f1f662d3a](https://linux-hardware.org/?probe=6f1f662d3a) | Oct 17, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [8b92e44d64](https://linux-hardware.org/?probe=8b92e44d64) | Oct 17, 2023 |
| Lenovo        | ThinkPad T480 20L6S69X08    | [efc4ad7803](https://linux-hardware.org/?probe=efc4ad7803) | Oct 17, 2023 |
| Lenovo        | E41-50 82HW                 | [f31f632ea0](https://linux-hardware.org/?probe=f31f632ea0) | Oct 17, 2023 |
| MSI           | Prestige 14H B12UCX         | [81dac6f109](https://linux-hardware.org/?probe=81dac6f109) | Oct 17, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [d271c61b92](https://linux-hardware.org/?probe=d271c61b92) | Oct 16, 2023 |
| Dell          | Latitude E6540              | [27875d6fe5](https://linux-hardware.org/?probe=27875d6fe5) | Oct 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d14e5830b2](https://linux-hardware.org/?probe=d14e5830b2) | Oct 16, 2023 |
| Dell          | Vostro 14 5410              | [219d504a89](https://linux-hardware.org/?probe=219d504a89) | Oct 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [73e2838408](https://linux-hardware.org/?probe=73e2838408) | Oct 16, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [5651db5e36](https://linux-hardware.org/?probe=5651db5e36) | Oct 16, 2023 |
| HP            | Notebook                    | [44730825fa](https://linux-hardware.org/?probe=44730825fa) | Oct 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | [386d015b42](https://linux-hardware.org/?probe=386d015b42) | Oct 16, 2023 |
| GLM           | 14-Z8350-C                  | [2db6571799](https://linux-hardware.org/?probe=2db6571799) | Oct 15, 2023 |
| HUAWEI        | MACH-WX9                    | [19ec3283fc](https://linux-hardware.org/?probe=19ec3283fc) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [8c4e60d5ca](https://linux-hardware.org/?probe=8c4e60d5ca) | Oct 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [1a38144f94](https://linux-hardware.org/?probe=1a38144f94) | Oct 15, 2023 |
| Dell          | Latitude 5591               | [ef0287bbad](https://linux-hardware.org/?probe=ef0287bbad) | Oct 15, 2023 |
| Gigabyte      | G7 GD                       | [667243780c](https://linux-hardware.org/?probe=667243780c) | Oct 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [85e073cb44](https://linux-hardware.org/?probe=85e073cb44) | Oct 15, 2023 |
| Acer          | Aspire VN7-592G             | [13b64fc9bd](https://linux-hardware.org/?probe=13b64fc9bd) | Oct 15, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5aac34fb6e](https://linux-hardware.org/?probe=5aac34fb6e) | Oct 15, 2023 |
| HP            | Laptop 15-dy2xxx            | [5079c96f33](https://linux-hardware.org/?probe=5079c96f33) | Oct 15, 2023 |
| Toshiba       | Satellite CL10-C-102        | [cdaab4e230](https://linux-hardware.org/?probe=cdaab4e230) | Oct 15, 2023 |
| MSI           | Prestige 14H B12UCX         | [ddc0082c22](https://linux-hardware.org/?probe=ddc0082c22) | Oct 14, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4b4d5899fa](https://linux-hardware.org/?probe=4b4d5899fa) | Oct 14, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [3c91ad6491](https://linux-hardware.org/?probe=3c91ad6491) | Oct 14, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [160af8609e](https://linux-hardware.org/?probe=160af8609e) | Oct 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | [d68359ee50](https://linux-hardware.org/?probe=d68359ee50) | Oct 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11d91a0246](https://linux-hardware.org/?probe=11d91a0246) | Oct 14, 2023 |
| Dell          | XPS 9320                    | [21de4b869f](https://linux-hardware.org/?probe=21de4b869f) | Oct 14, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [1215db6b88](https://linux-hardware.org/?probe=1215db6b88) | Oct 13, 2023 |
| Google        | Morphius                    | [fd4be61654](https://linux-hardware.org/?probe=fd4be61654) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [3a6c620560](https://linux-hardware.org/?probe=3a6c620560) | Oct 13, 2023 |
| Dell          | Precision 7520              | [e9cb628c83](https://linux-hardware.org/?probe=e9cb628c83) | Oct 13, 2023 |
| Framework     | Laptop                      | [760f431061](https://linux-hardware.org/?probe=760f431061) | Oct 13, 2023 |
| Dell          | Precision 3580              | [f2a080ed43](https://linux-hardware.org/?probe=f2a080ed43) | Oct 13, 2023 |
| Apple         | MacBookPro11,3              | [1c1d7152a3](https://linux-hardware.org/?probe=1c1d7152a3) | Oct 13, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Fedora 38 | 1747      | 19.25%  |
| Fedora 36 | 1241      | 13.68%  |
| Fedora 37 | 1239      | 13.65%  |
| Fedora 35 | 974       | 10.73%  |
| Fedora 34 | 941       | 10.37%  |
| Fedora 33 | 857       | 9.44%   |
| Fedora 32 | 746       | 8.22%   |
| Fedora 39 | 528       | 5.82%   |
| Fedora 31 | 503       | 5.54%   |
| Fedora 30 | 163       | 1.8%    |
| Fedora 29 | 90        | 0.99%   |
| Fedora 28 | 22        | 0.24%   |
| Fedora 27 | 8         | 0.09%   |
| Fedora 40 | 5         | 0.06%   |
| Fedora 24 | 4         | 0.04%   |
| Fedora 21 | 4         | 0.04%   |
| Fedora 25 | 2         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Fedora | 8111      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.9-300.fc38.x86_64   | 220       | 2.19%   |
| 6.2.15-300.fc38.x86_64  | 142       | 1.41%   |
| 6.5.11-300.fc39.x86_64  | 136       | 1.35%   |
| 5.17.5-300.fc36.x86_64  | 115       | 1.14%   |
| 6.3.8-200.fc38.x86_64   | 114       | 1.13%   |
| 6.4.15-200.fc38.x86_64  | 102       | 1.01%   |
| 6.0.7-301.fc37.x86_64   | 92        | 0.91%   |
| 5.16.18-200.fc35.x86_64 | 92        | 0.91%   |
| 6.5.5-200.fc38.x86_64   | 90        | 0.89%   |
| 6.2.14-300.fc38.x86_64  | 90        | 0.89%   |
| 5.9.16-200.fc33.x86_64  | 90        | 0.89%   |
| 6.2.11-300.fc38.x86_64  | 87        | 0.86%   |
| 5.11.12-300.fc34.x86_64 | 77        | 0.77%   |
| 6.0.15-300.fc37.x86_64  | 76        | 0.76%   |
| 6.5.6-300.fc39.x86_64   | 72        | 0.72%   |
| 5.14.10-300.fc35.x86_64 | 71        | 0.71%   |
| 6.0.5-200.fc36.x86_64   | 69        | 0.69%   |
| 6.5.8-200.fc38.x86_64   | 66        | 0.66%   |
| 6.3.12-200.fc38.x86_64  | 66        | 0.66%   |
| 5.8.16-300.fc33.x86_64  | 64        | 0.64%   |
| 6.1.14-200.fc37.x86_64  | 61        | 0.61%   |
| 5.8.15-301.fc33.x86_64  | 61        | 0.61%   |
| 5.18.13-200.fc36.x86_64 | 61        | 0.61%   |
| 6.5.12-300.fc39.x86_64  | 59        | 0.59%   |
| 6.0.8-300.fc37.x86_64   | 57        | 0.57%   |
| 5.8.4-200.fc32.x86_64   | 57        | 0.57%   |
| 6.1.7-200.fc37.x86_64   | 56        | 0.56%   |
| 6.4.6-200.fc38.x86_64   | 55        | 0.55%   |
| 5.13.12-200.fc34.x86_64 | 54        | 0.54%   |
| 6.6.6-200.fc39.x86_64   | 53        | 0.53%   |
| 6.6.4-200.fc39.x86_64   | 53        | 0.53%   |
| 6.5.6-200.fc38.x86_64   | 53        | 0.53%   |
| 6.0.9-300.fc37.x86_64   | 52        | 0.52%   |
| 6.4.14-200.fc38.x86_64  | 51        | 0.51%   |
| 6.3.11-200.fc38.x86_64  | 51        | 0.51%   |
| 6.1.18-200.fc37.x86_64  | 51        | 0.51%   |
| 6.0.12-300.fc37.x86_64  | 51        | 0.51%   |
| 5.18.11-200.fc36.x86_64 | 50        | 0.5%    |
| 6.5.7-200.fc38.x86_64   | 47        | 0.47%   |
| 6.4.7-200.fc38.x86_64   | 47        | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.9   | 260       | 2.59%   |
| 6.2.15  | 182       | 1.81%   |
| 5.17.5  | 149       | 1.48%   |
| 6.5.11  | 138       | 1.37%   |
| 6.5.6   | 127       | 1.26%   |
| 6.3.8   | 125       | 1.24%   |
| 6.5.5   | 107       | 1.06%   |
| 6.4.15  | 104       | 1.03%   |
| 6.2.14  | 104       | 1.03%   |
| 6.0.7   | 102       | 1.01%   |
| 6.2.11  | 99        | 0.98%   |
| 5.9.16  | 96        | 0.95%   |
| 5.16.18 | 95        | 0.94%   |
| 5.8.15  | 88        | 0.88%   |
| 6.0.15  | 86        | 0.86%   |
| 5.11.12 | 84        | 0.84%   |
| 5.8.16  | 81        | 0.81%   |
| 5.14.10 | 80        | 0.8%    |
| 6.0.5   | 75        | 0.75%   |
| 5.19.16 | 75        | 0.75%   |
| 6.5.8   | 70        | 0.7%    |
| 6.3.12  | 70        | 0.7%    |
| 6.0.8   | 69        | 0.69%   |
| 6.0.12  | 69        | 0.69%   |
| 6.5.12  | 67        | 0.67%   |
| 6.0.9   | 67        | 0.67%   |
| 5.11.11 | 66        | 0.66%   |
| 5.18.13 | 65        | 0.65%   |
| 6.1.14  | 64        | 0.64%   |
| 5.8.18  | 64        | 0.64%   |
| 6.6.6   | 61        | 0.61%   |
| 6.1.7   | 61        | 0.61%   |
| 6.6.4   | 60        | 0.6%    |
| 6.2.8   | 57        | 0.57%   |
| 5.8.4   | 57        | 0.57%   |
| 5.13.12 | 57        | 0.57%   |
| 6.4.6   | 56        | 0.56%   |
| 5.14.18 | 56        | 0.56%   |
| 5.18.11 | 53        | 0.53%   |
| 6.5.7   | 52        | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 845       | 8.77%   |
| 6.0     | 658       | 6.83%   |
| 6.5     | 645       | 6.69%   |
| 5.17    | 521       | 5.41%   |
| 6.4     | 503       | 5.22%   |
| 6.1     | 481       | 4.99%   |
| 5.8     | 465       | 4.82%   |
| 5.19    | 449       | 4.66%   |
| 5.11    | 449       | 4.66%   |
| 5.18    | 410       | 4.25%   |
| 6.3     | 403       | 4.18%   |
| 5.14    | 395       | 4.1%    |
| 5.16    | 384       | 3.98%   |
| 5.15    | 310       | 3.22%   |
| 5.9     | 304       | 3.15%   |
| 5.13    | 303       | 3.14%   |
| 5.10    | 294       | 3.05%   |
| 5.6     | 286       | 2.97%   |
| 5.12    | 282       | 2.93%   |
| 6.6     | 232       | 2.41%   |
| 5.7     | 221       | 2.29%   |
| 5.3     | 194       | 2.01%   |
| 5.5     | 183       | 1.9%    |
| 5.4     | 169       | 1.75%   |
| 5.0     | 62        | 0.64%   |
| 5.2     | 47        | 0.49%   |
| 5.1     | 43        | 0.45%   |
| 4.19    | 30        | 0.31%   |
| 4.18    | 27        | 0.28%   |
| 4.20    | 18        | 0.19%   |
| 6.7     | 4         | 0.04%   |
| 4.16    | 3         | 0.03%   |
| 4.15    | 3         | 0.03%   |
| 4.11    | 3         | 0.03%   |
| 4.1     | 3         | 0.03%   |
| 4.8     | 2         | 0.02%   |
| 4.17    | 2         | 0.02%   |
| 4.5     | 1         | 0.01%   |
| 4.14    | 1         | 0.01%   |
| 4.10    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 8101      | 99.86%  |
| i686    | 5         | 0.06%   |
| aarch64 | 5         | 0.06%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 6217      | 74.62%  |
| KDE5            | 983       | 11.8%   |
| Unknown         | 340       | 4.08%   |
| XFCE            | 164       | 1.97%   |
| KDE             | 137       | 1.64%   |
| X-Cinnamon      | 111       | 1.33%   |
| MATE            | 100       | 1.2%    |
| Cinnamon        | 81        | 0.97%   |
| i3              | 37        | 0.44%   |
| GNOME Classic   | 29        | 0.35%   |
| LXQt            | 24        | 0.29%   |
| sway            | 20        | 0.24%   |
| LXDE            | 20        | 0.24%   |
| Budgie          | 14        | 0.17%   |
| Deepin          | 13        | 0.16%   |
| Pantheon        | 5         | 0.06%   |
| Hyprland        | 5         | 0.06%   |
| KDE4            | 4         | 0.05%   |
| fluxbox         | 4         | 0.05%   |
| awesome         | 4         | 0.05%   |
| openbox         | 3         | 0.04%   |
| GNOME-Classic   | 3         | 0.04%   |
| GNOME Flashback | 3         | 0.04%   |
| xinit-compat    | 2         | 0.02%   |
| dwm             | 2         | 0.02%   |
| bspwm           | 2         | 0.02%   |
| xmonad          | 1         | 0.01%   |
| Unity           | 1         | 0.01%   |
| qtile           | 1         | 0.01%   |
| KDE:old         | 1         | 0.01%   |
| custom          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 5791      | 68.92%  |
| X11     | 2332      | 27.75%  |
| Unknown | 218       | 2.59%   |
| Tty     | 61        | 0.73%   |
| Xcb     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4382      | 52.58%  |
| GDM     | 2917      | 35%     |
| SDDM    | 589       | 7.07%   |
| LightDM | 329       | 3.95%   |
| TDM     | 87        | 1.04%   |
| XDM     | 10        | 0.12%   |
| LXDM    | 9         | 0.11%   |
| KDM     | 8         | 0.1%    |
| SLiM    | 1         | 0.01%   |
| Ly      | 1         | 0.01%   |
| GREETD  | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 4223      | 51.15%  |
| en_GB   | 586       | 7.1%    |
| ru_RU   | 396       | 4.8%    |
| pt_BR   | 381       | 4.61%   |
| Unknown | 374       | 4.53%   |
| de_DE   | 293       | 3.55%   |
| fr_FR   | 242       | 2.93%   |
| it_IT   | 222       | 2.69%   |
| pl_PL   | 131       | 1.59%   |
| es_ES   | 128       | 1.55%   |
| en_CA   | 123       | 1.49%   |
| en_IN   | 109       | 1.32%   |
| en_AU   | 109       | 1.32%   |
| es_MX   | 86        | 1.04%   |
| es_CL   | 58        | 0.7%    |
| cs_CZ   | 50        | 0.61%   |
| zh_CN   | 44        | 0.53%   |
| tr_TR   | 42        | 0.51%   |
| es_AR   | 38        | 0.46%   |
| es_CO   | 35        | 0.42%   |
| pt_PT   | 34        | 0.41%   |
| en_DK   | 32        | 0.39%   |
| nl_NL   | 28        | 0.34%   |
| hu_HU   | 28        | 0.34%   |
| de_AT   | 27        | 0.33%   |
| sv_SE   | 25        | 0.3%    |
| en_NZ   | 24        | 0.29%   |
| en_IE   | 21        | 0.25%   |
| C       | 21        | 0.25%   |
| en_ZA   | 19        | 0.23%   |
| ru_UA   | 18        | 0.22%   |
| fr_CA   | 17        | 0.21%   |
| es_PE   | 15        | 0.18%   |
| fi_FI   | 14        | 0.17%   |
| fr_BE   | 13        | 0.16%   |
| en_SG   | 13        | 0.16%   |
| de_CH   | 13        | 0.16%   |
| sk_SK   | 12        | 0.15%   |
| nb_NO   | 12        | 0.15%   |
| es_EC   | 11        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 6660      | 80.99%  |
| BIOS | 1563      | 19.01%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Btrfs               | 5369      | 64.82%  |
| Ext4                | 2506      | 30.25%  |
| Unknown             | 196       | 2.37%   |
| Xfs                 | 189       | 2.28%   |
| Overlay             | 12        | 0.14%   |
| Zfs                 | 3         | 0.04%   |
| F2fs                | 3         | 0.04%   |
| Ext3                | 3         | 0.04%   |
| Fuse.fuse-overlayfs | 2         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4340      | 52.32%  |
| GPT     | 3533      | 42.59%  |
| MBR     | 422       | 5.09%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7463      | 91.01%  |
| Yes       | 737       | 8.99%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6732      | 82.05%  |
| Yes       | 1473      | 17.95%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 2376      | 29.29%  |
| Dell                   | 1416      | 17.46%  |
| Hewlett-Packard        | 1204      | 14.84%  |
| ASUSTek Computer       | 864       | 10.65%  |
| Acer                   | 524       | 6.46%   |
| Apple                  | 243       | 3%      |
| MSI                    | 192       | 2.37%   |
| HUAWEI                 | 186       | 2.29%   |
| Samsung Electronics    | 114       | 1.41%   |
| Toshiba                | 105       | 1.29%   |
| Sony                   | 63        | 0.78%   |
| Timi                   | 62        | 0.76%   |
| Notebook               | 60        | 0.74%   |
| Google                 | 45        | 0.55%   |
| Framework              | 44        | 0.54%   |
| Unknown                | 39        | 0.48%   |
| Fujitsu                | 36        | 0.44%   |
| Alienware              | 31        | 0.38%   |
| Positivo               | 25        | 0.31%   |
| System76               | 23        | 0.28%   |
| TUXEDO                 | 22        | 0.27%   |
| Gigabyte Technology    | 21        | 0.26%   |
| Razer                  | 19        | 0.23%   |
| LG Electronics         | 16        | 0.2%    |
| HONOR                  | 16        | 0.2%    |
| Chuwi                  | 15        | 0.18%   |
| Avell High Performance | 13        | 0.16%   |
| Schenker               | 12        | 0.15%   |
| PC Specialist          | 11        | 0.14%   |
| Packard Bell           | 10        | 0.12%   |
| GPU Company            | 10        | 0.12%   |
| GPD                    | 9         | 0.11%   |
| SLIMBOOK               | 8         | 0.1%    |
| Panasonic              | 8         | 0.1%    |
| Fujitsu Siemens        | 8         | 0.1%    |
| Intel Client Systems   | 7         | 0.09%   |
| Positivo Bahia - VAIO  | 6         | 0.07%   |
| Insyde                 | 6         | 0.07%   |
| Hampoo                 | 6         | 0.07%   |
| Clevo                  | 6         | 0.07%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 64        | 0.79%   |
| HP Notebook                                | 40        | 0.49%   |
| Framework Laptop                           | 30        | 0.37%   |
| Dell Latitude 7490                         | 29        | 0.36%   |
| Dell XPS 13 9370                           | 26        | 0.32%   |
| Dell XPS 15 9570                           | 25        | 0.31%   |
| Apple MacBookPro9,2                        | 25        | 0.31%   |
| Dell XPS 15 9560                           | 24        | 0.3%    |
| Dell XPS 15 7590                           | 24        | 0.3%    |
| Dell XPS 13 9310                           | 23        | 0.28%   |
| HP EliteBook 840 G6                        | 21        | 0.26%   |
| Dell XPS 15 9500                           | 20        | 0.25%   |
| Dell XPS 13 9360                           | 20        | 0.25%   |
| Dell XPS 13 7390                           | 19        | 0.23%   |
| Dell Latitude E7450                        | 19        | 0.23%   |
| Apple MacBookPro12,1                       | 19        | 0.23%   |
| HP Pavilion Notebook                       | 18        | 0.22%   |
| HP Pavilion dv6                            | 18        | 0.22%   |
| HP Pavilion 15                             | 17        | 0.21%   |
| Dell XPS 15 9550                           | 17        | 0.21%   |
| Apple MacBookPro8,1                        | 17        | 0.21%   |
| HP Laptop 15-da0xxx                        | 16        | 0.2%    |
| Dell XPS 13 9300                           | 16        | 0.2%    |
| Dell Latitude E6420                        | 16        | 0.2%    |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 15        | 0.18%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 15        | 0.18%   |
| HUAWEI KLVL-WXX9                           | 15        | 0.18%   |
| Dell Latitude E7440                        | 15        | 0.18%   |
| HUAWEI NBLK-WAX9X                          | 14        | 0.17%   |
| HP EliteBook 840 G3                        | 14        | 0.17%   |
| Dell XPS 13 9380                           | 14        | 0.17%   |
| Dell Latitude 5480                         | 14        | 0.17%   |
| Apple MacBookPro11,3                       | 14        | 0.17%   |
| Apple MacBookPro11,1                       | 14        | 0.17%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 13        | 0.16%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 13        | 0.16%   |
| HUAWEI HVY-WXX9                            | 13        | 0.16%   |
| Dell XPS 15 9510                           | 13        | 0.16%   |
| Dell XPS 13 9350                           | 13        | 0.16%   |
| Dell Inspiron 5570                         | 13        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1408      | 17.36%  |
| Lenovo IdeaPad     | 483       | 5.95%   |
| Dell Latitude      | 439       | 5.41%   |
| Dell Inspiron      | 388       | 4.78%   |
| Acer Aspire        | 330       | 4.07%   |
| Dell XPS           | 310       | 3.82%   |
| HP Pavilion        | 251       | 3.09%   |
| HP EliteBook       | 233       | 2.87%   |
| ASUS VivoBook      | 196       | 2.42%   |
| HP ProBook         | 180       | 2.22%   |
| HP Laptop          | 176       | 2.17%   |
| ASUS ROG           | 143       | 1.76%   |
| Dell Precision     | 121       | 1.49%   |
| Lenovo Legion      | 109       | 1.34%   |
| Lenovo ThinkBook   | 90        | 1.11%   |
| Toshiba Satellite  | 86        | 1.06%   |
| ASUS ASUS          | 83        | 1.02%   |
| Lenovo Yoga        | 77        | 0.95%   |
| Acer Nitro         | 77        | 0.95%   |
| ASUS ZenBook       | 73        | 0.9%    |
| Dell Vostro        | 69        | 0.85%   |
| Unknown            | 64        | 0.79%   |
| HP ZBook           | 61        | 0.75%   |
| HP ENVY            | 49        | 0.6%    |
| Acer Swift         | 48        | 0.59%   |
| HP OMEN            | 45        | 0.55%   |
| Framework Laptop   | 44        | 0.54%   |
| Apple MacBookPro11 | 44        | 0.54%   |
| HP Notebook        | 40        | 0.49%   |
| ASUS TUF           | 35        | 0.43%   |
| MSI Modern         | 32        | 0.39%   |
| Fujitsu LIFEBOOK   | 30        | 0.37%   |
| Apple MacBookPro9  | 29        | 0.36%   |
| Acer Predator      | 25        | 0.31%   |
| Dell G5            | 24        | 0.3%    |
| Apple MacBookPro8  | 23        | 0.28%   |
| HP 250             | 22        | 0.27%   |
| Apple MacBookPro12 | 19        | 0.23%   |
| Razer Blade        | 18        | 0.22%   |
| MSI Prestige       | 18        | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 1068      | 13.17%  |
| 2021    | 1000      | 12.33%  |
| 2019    | 947       | 11.68%  |
| 2018    | 820       | 10.11%  |
| 2017    | 585       | 7.21%   |
| 2022    | 541       | 6.67%   |
| 2012    | 472       | 5.82%   |
| 2015    | 447       | 5.51%   |
| 2013    | 436       | 5.38%   |
| 2016    | 434       | 5.35%   |
| 2014    | 418       | 5.15%   |
| 2011    | 334       | 4.12%   |
| 2023    | 192       | 2.37%   |
| 2010    | 174       | 2.15%   |
| 2008    | 109       | 1.34%   |
| 2009    | 85        | 1.05%   |
| 2007    | 37        | 0.46%   |
| 2006    | 6         | 0.07%   |
| Unknown | 5         | 0.06%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 8111      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 6430      | 77.81%  |
| Enabled  | 1834      | 22.19%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 8042      | 99.15%  |
| Yes  | 69        | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2385      | 28.95%  |
| 16.01-24.0  | 1936      | 23.5%   |
| 8.01-16.0   | 1650      | 20.03%  |
| 32.01-64.0  | 964       | 11.7%   |
| 3.01-4.0    | 790       | 9.59%   |
| 24.01-32.0  | 175       | 2.12%   |
| 64.01-256.0 | 145       | 1.76%   |
| 1.01-2.0    | 144       | 1.75%   |
| 2.01-3.0    | 37        | 0.45%   |
| 0.51-1.0    | 11        | 0.13%   |
| Unknown     | 2         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 2550      | 27.99%  |
| 2.01-3.0   | 2512      | 27.58%  |
| 3.01-4.0   | 2073      | 22.76%  |
| 1.01-2.0   | 1127      | 12.37%  |
| 8.01-16.0  | 663       | 7.28%   |
| 0.51-1.0   | 84        | 0.92%   |
| 16.01-24.0 | 69        | 0.76%   |
| 24.01-32.0 | 17        | 0.19%   |
| 32.01-64.0 | 8         | 0.09%   |
| 0.01-0.5   | 4         | 0.04%   |
| Unknown    | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 6029      | 73.09%  |
| 2      | 1909      | 23.14%  |
| 3      | 219       | 2.65%   |
| 0      | 39        | 0.47%   |
| 4      | 36        | 0.44%   |
| 5      | 9         | 0.11%   |
| 6      | 6         | 0.07%   |
| 8      | 1         | 0.01%   |
| 7      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6486      | 79.56%  |
| Yes       | 1666      | 20.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5976      | 73.19%  |
| No        | 2189      | 26.81%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7957      | 98.03%  |
| No        | 160       | 1.97%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6875      | 83.83%  |
| No        | 1326      | 16.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1341      | 16.35%  |
| Brazil      | 577       | 7.03%   |
| Germany     | 566       | 6.9%    |
| Russia      | 533       | 6.5%    |
| Italy       | 394       | 4.8%    |
| France      | 326       | 3.97%   |
| India       | 320       | 3.9%    |
| UK          | 297       | 3.62%   |
| Poland      | 243       | 2.96%   |
| Canada      | 233       | 2.84%   |
| Netherlands | 230       | 2.8%    |
| Spain       | 205       | 2.5%    |
| Mexico      | 161       | 1.96%   |
| Czechia     | 133       | 1.62%   |
| Turkey      | 132       | 1.61%   |
| Australia   | 130       | 1.58%   |
| Austria     | 99        | 1.21%   |
| Sweden      | 98        | 1.19%   |
| Switzerland | 89        | 1.09%   |
| Portugal    | 84        | 1.02%   |
| Romania     | 76        | 0.93%   |
| Chile       | 76        | 0.93%   |
| Belgium     | 76        | 0.93%   |
| Indonesia   | 72        | 0.88%   |
| Hungary     | 72        | 0.88%   |
| Argentina   | 72        | 0.88%   |
| Ukraine     | 66        | 0.8%    |
| Finland     | 66        | 0.8%    |
| Norway      | 64        | 0.78%   |
| Colombia    | 61        | 0.74%   |
| Denmark     | 59        | 0.72%   |
| China       | 52        | 0.63%   |
| Iran        | 46        | 0.56%   |
| Bulgaria    | 45        | 0.55%   |
| Belarus     | 43        | 0.52%   |
| Israel      | 40        | 0.49%   |
| Greece      | 40        | 0.49%   |
| Slovakia    | 39        | 0.48%   |
| Philippines | 35        | 0.43%   |
| Japan       | 35        | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 169       | 1.93%   |
| Sao Paulo         | 78        | 0.89%   |
| St Petersburg     | 73        | 0.83%   |
| Berlin            | 70        | 0.8%    |
| Vienna            | 66        | 0.75%   |
| Paris             | 63        | 0.72%   |
| Warsaw            | 56        | 0.64%   |
| Milan             | 56        | 0.64%   |
| Amsterdam         | 54        | 0.62%   |
| Istanbul          | 53        | 0.61%   |
| Prague            | 52        | 0.59%   |
| Madrid            | 49        | 0.56%   |
| Mexico City       | 43        | 0.49%   |
| Helsinki          | 43        | 0.49%   |
| Munich            | 41        | 0.47%   |
| Bengaluru         | 40        | 0.46%   |
| Santiago          | 37        | 0.42%   |
| Sydney            | 36        | 0.41%   |
| Melbourne         | 36        | 0.41%   |
| Budapest          | 36        | 0.41%   |
| Oslo              | 34        | 0.39%   |
| Frankfurt am Main | 32        | 0.37%   |
| Bucharest         | 31        | 0.35%   |
| Zurich            | 30        | 0.34%   |
| Lisbon            | 30        | 0.34%   |
| Sofia             | 29        | 0.33%   |
| Hamburg           | 29        | 0.33%   |
| Rio de Janeiro    | 28        | 0.32%   |
| Montreal          | 28        | 0.32%   |
| Jakarta           | 28        | 0.32%   |
| Delft             | 28        | 0.32%   |
| Brisbane          | 28        | 0.32%   |
| Minsk             | 27        | 0.31%   |
| Brasília         | 27        | 0.31%   |
| Tehran            | 26        | 0.3%    |
| Singapore         | 26        | 0.3%    |
| Barcelona         | 26        | 0.3%    |
| Toronto           | 24        | 0.27%   |
| Rome              | 24        | 0.27%   |
| Pune              | 24        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2153      | 3077   | 21.04%  |
| WDC                         | 937       | 1180   | 9.16%   |
| SanDisk                     | 822       | 1050   | 8.03%   |
| Seagate                     | 710       | 927    | 6.94%   |
| Toshiba                     | 643       | 819    | 6.28%   |
| SK hynix                    | 610       | 750    | 5.96%   |
| Unknown                     | 522       | 681    | 5.1%    |
| Kingston                    | 490       | 598    | 4.79%   |
| Intel                       | 437       | 609    | 4.27%   |
| Micron Technology           | 392       | 500    | 3.83%   |
| Crucial                     | 291       | 383    | 2.84%   |
| HGST                        | 192       | 260    | 1.88%   |
| KIOXIA                      | 166       | 226    | 1.62%   |
| A-DATA Technology           | 142       | 166    | 1.39%   |
| Apple                       | 138       | 190    | 1.35%   |
| Hitachi                     | 94        | 111    | 0.92%   |
| LITEON                      | 80        | 86     | 0.78%   |
| Silicon Motion              | 73        | 91     | 0.71%   |
| China                       | 73        | 87     | 0.71%   |
| Phison Electronics          | 64        | 70     | 0.63%   |
| Phison                      | 64        | 73     | 0.63%   |
| Micron/Crucial Technology   | 62        | 69     | 0.61%   |
| ADATA Technology            | 47        | 52     | 0.46%   |
| PNY                         | 45        | 59     | 0.44%   |
| Kingston Technology Company | 43        | 51     | 0.42%   |
| SPCC                        | 41        | 52     | 0.4%    |
| Transcend                   | 39        | 57     | 0.38%   |
| LITEONIT                    | 33        | 39     | 0.32%   |
| JMicron Technology          | 30        | 37     | 0.29%   |
| Lenovo                      | 28        | 34     | 0.27%   |
| Unknown                     | 27        | 33     | 0.26%   |
| Realtek Semiconductor       | 24        | 29     | 0.23%   |
| Corsair                     | 23        | 28     | 0.22%   |
| Netac                       | 21        | 27     | 0.21%   |
| Union Memory (Shenzhen)     | 20        | 33     | 0.2%    |
| Patriot                     | 20        | 26     | 0.2%    |
| Hewlett-Packard             | 20        | 19     | 0.2%    |
| Team                        | 19        | 22     | 0.19%   |
| Intenso                     | 19        | 22     | 0.19%   |
| XPG                         | 18        | 27     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 201       | 1.87%   |
| Seagate ST1000LM035-1RK172 1TB                      | 151       | 1.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 137       | 1.28%   |
| Samsung NVMe SSD Drive 512GB                        | 113       | 1.05%   |
| Kingston SA400S37240G 240GB SSD                     | 100       | 0.93%   |
| Unknown MMC Card  32GB                              | 85        | 0.79%   |
| HGST HTS721010A9E630 1TB                            | 84        | 0.78%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 83        | 0.77%   |
| Unknown MMC Card  64GB                              | 82        | 0.76%   |
| Toshiba MQ04ABF100 1TB                              | 81        | 0.75%   |
| SanDisk NVMe SSD Drive 512GB                        | 81        | 0.75%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 80        | 0.75%   |
| Kingston SA400S37480G 480GB SSD                     | 72        | 0.67%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 63        | 0.59%   |
| Samsung SSD 860 EVO 500GB                           | 62        | 0.58%   |
| Unknown MMC Card  128GB                             | 61        | 0.57%   |
| Toshiba MQ01ABD100 1TB                              | 61        | 0.57%   |
| Intel SSDPEKNU512GZ 512GB                           | 58        | 0.54%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 52        | 0.48%   |
| SK hynix NVMe SSD Drive 512GB                       | 51        | 0.48%   |
| Samsung NVMe SSD Drive 1024GB                       | 51        | 0.48%   |
| SanDisk NVMe SSD Drive 256GB                        | 48        | 0.45%   |
| Samsung SSD 850 EVO 500GB                           | 46        | 0.43%   |
| Samsung SSD 850 EVO 250GB                           | 46        | 0.43%   |
| Intel NVMe SSD Drive 512GB                          | 46        | 0.43%   |
| Seagate ST500LT012-1DG142 500GB                     | 45        | 0.42%   |
| Samsung NVMe SSD Drive 1TB                          | 43        | 0.4%    |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 40        | 0.37%   |
| Crucial CT240BX500SSD1 240GB                        | 40        | 0.37%   |
| Intel SSD 660P Series 512GB                         | 39        | 0.36%   |
| Toshiba NVMe SSD Drive 512GB                        | 38        | 0.35%   |
| Seagate Expansion 1TB                               | 38        | 0.35%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 37        | 0.34%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 37        | 0.34%   |
| Samsung SSD 980 1TB                                 | 37        | 0.34%   |
| Crucial CT1000MX500SSD1 1TB                         | 37        | 0.34%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 35        | 0.33%   |
| Crucial CT500MX500SSD1 500GB                        | 35        | 0.33%   |
| Samsung SSD 860 EVO 250GB                           | 34        | 0.32%   |
| Samsung SSD 860 EVO 1TB                             | 34        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 681       | 881    | 36.22%  |
| WDC                 | 499       | 631    | 26.54%  |
| Toshiba             | 312       | 390    | 16.6%   |
| HGST                | 192       | 260    | 10.21%  |
| Hitachi             | 94        | 111    | 5%      |
| Unknown             | 24        | 35     | 1.28%   |
| Samsung Electronics | 17        | 20     | 0.9%    |
| Fujitsu             | 14        | 14     | 0.74%   |
| Apple               | 13        | 14     | 0.69%   |
| TO Exter            | 5         | 5      | 0.27%   |
| External            | 5         | 7      | 0.27%   |
| USB3.0              | 3         | 3      | 0.16%   |
| HGST HTS            | 3         | 3      | 0.16%   |
| LIO-ORG             | 2         | 12     | 0.11%   |
| LaCie               | 2         | 3      | 0.11%   |
| ASMT                | 2         | 3      | 0.11%   |
| XrayDisk            | 1         | 1      | 0.05%   |
| StoreJet            | 1         | 1      | 0.05%   |
| SSK                 | 1         | 1      | 0.05%   |
| SAGE                | 1         | 1      | 0.05%   |
| QNAP                | 1         | 4      | 0.05%   |
| Phison              | 1         | 2      | 0.05%   |
| JMicron Technology  | 1         | 1      | 0.05%   |
| Intenso             | 1         | 1      | 0.05%   |
| Inateck             | 1         | 1      | 0.05%   |
| IB-AC703            | 1         | 1      | 0.05%   |
| IB                  | 1         | 2      | 0.05%   |
| ACASIS              | 1         | 1      | 0.05%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 734       | 1036   | 24.22%  |
| Kingston            | 353       | 426    | 11.65%  |
| SanDisk             | 309       | 414    | 10.2%   |
| Crucial             | 263       | 352    | 8.68%   |
| WDC                 | 163       | 208    | 5.38%   |
| Intel               | 102       | 160    | 3.37%   |
| Micron Technology   | 100       | 121    | 3.3%    |
| A-DATA Technology   | 93        | 108    | 3.07%   |
| Apple               | 91        | 105    | 3%      |
| SK hynix            | 78        | 95     | 2.57%   |
| China               | 72        | 86     | 2.38%   |
| Toshiba             | 67        | 84     | 2.21%   |
| LITEON              | 65        | 71     | 2.15%   |
| PNY                 | 43        | 56     | 1.42%   |
| SPCC                | 34        | 45     | 1.12%   |
| Transcend           | 33        | 47     | 1.09%   |
| LITEONIT            | 33        | 39     | 1.09%   |
| JMicron Technology  | 22        | 28     | 0.73%   |
| Patriot             | 18        | 23     | 0.59%   |
| OCZ                 | 16        | 18     | 0.53%   |
| Netac               | 16        | 20     | 0.53%   |
| KingSpec            | 16        | 19     | 0.53%   |
| Intenso             | 15        | 17     | 0.5%    |
| Gigabyte Technology | 15        | 21     | 0.5%    |
| Corsair             | 15        | 17     | 0.5%    |
| GOODRAM             | 14        | 23     | 0.46%   |
| Team                | 13        | 16     | 0.43%   |
| Lexar               | 13        | 23     | 0.43%   |
| Hewlett-Packard     | 12        | 12     | 0.4%    |
| Apacer              | 12        | 15     | 0.4%    |
| Seagate             | 10        | 11     | 0.33%   |
| Plextor             | 7         | 13     | 0.23%   |
| Unknown             | 6         | 6      | 0.2%    |
| Unknown             | 6         | 7      | 0.2%    |
| Teclast             | 5         | 6      | 0.17%   |
| Ramsta              | 5         | 6      | 0.17%   |
| Mushkin             | 5         | 14     | 0.17%   |
| KingDian            | 5         | 5      | 0.17%   |
| FORESEE             | 5         | 7      | 0.17%   |
| MidasForce          | 4         | 4      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 4388      | 6189   | 45.54%  |
| SSD     | 2811      | 3951   | 29.17%  |
| HDD     | 1815      | 2409   | 18.84%  |
| MMC     | 489       | 645    | 5.08%   |
| Unknown | 132       | 151    | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 4380      | 6156   | 47.27%  |
| SATA | 4051      | 6084   | 43.72%  |
| MMC  | 489       | 645    | 5.28%   |
| SAS  | 345       | 460    | 3.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2885      | 4036   | 62.69%  |
| 0.51-1.0   | 1528      | 2045   | 33.2%   |
| 1.01-2.0   | 159       | 245    | 3.46%   |
| 4.01-10.0  | 17        | 19     | 0.37%   |
| 3.01-4.0   | 12        | 13     | 0.26%   |
| 0          | 1         | 2      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1858      | 21.81%  |
| 501-1000       | 1856      | 21.79%  |
| 101-250        | 1443      | 16.94%  |
| 1001-2000      | 968       | 11.36%  |
| 1-20           | 901       | 10.58%  |
| Unknown        | 640       | 7.51%   |
| 51-100         | 328       | 3.85%   |
| More than 3000 | 183       | 2.15%   |
| 21-50          | 177       | 2.08%   |
| 2001-3000      | 164       | 1.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2758      | 30.88%  |
| 21-50          | 1555      | 17.41%  |
| 101-250        | 1358      | 15.21%  |
| 51-100         | 1122      | 12.56%  |
| 251-500        | 823       | 9.22%   |
| Unknown        | 640       | 7.17%   |
| 501-1000       | 465       | 5.21%   |
| 1001-2000      | 159       | 1.78%   |
| More than 3000 | 25        | 0.28%   |
| 2001-3000      | 25        | 0.28%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                | 13        | 13     | 3.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 19     | 2.67%   |
| HGST HTS721010A9E630 1TB                       | 9         | 11     | 2.67%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 2.08%   |
| HGST HTS541010A9E680 1TB                       | 7         | 7      | 2.08%   |
| Toshiba MQ01ABD100 1TB                         | 6         | 6      | 1.78%   |
| Seagate ST9500325AS 500GB                      | 6         | 8      | 1.78%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 6         | 6      | 1.78%   |
| HGST HTS545050A7E680 500GB                     | 6         | 6      | 1.78%   |
| Hitachi HTS547575A9E384 752GB                  | 5         | 7      | 1.48%   |
| Toshiba MQ01ABD075 752GB                       | 4         | 4      | 1.19%   |
| Hitachi HTS545050B9A300 500GB                  | 4         | 4      | 1.19%   |
| HGST HTS725050A7E630 500GB                     | 4         | 4      | 1.19%   |
| Toshiba MQ01ABF050 500GB                       | 3         | 4      | 0.89%   |
| SK hynix SC308 SATA 128GB SSD                  | 3         | 3      | 0.89%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 3         | 3      | 0.89%   |
| Seagate ST9500420AS 500GB                      | 3         | 4      | 0.89%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 0.89%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 4      | 0.89%   |
| Seagate ST2000LM003 HN-M201RAD 2TB             | 3         | 3      | 0.89%   |
| Seagate ST1000LM049-2GH172 1TB                 | 3         | 4      | 0.89%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 3         | 3      | 0.89%   |
| Samsung Electronics SSD 980 1TB                | 3         | 3      | 0.89%   |
| Samsung Electronics SSD 870 EVO 500GB          | 3         | 6      | 0.89%   |
| Crucial CT1000P1SSD8 1TB                       | 3         | 3      | 0.89%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 2         | 2      | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 2         | 2      | 0.59%   |
| WDC WD10SPZX-24Z10 1TB                         | 2         | 2      | 0.59%   |
| Toshiba MQ01ACF050 500GB                       | 2         | 2      | 0.59%   |
| Toshiba MQ01ABD050V 500GB                      | 2         | 2      | 0.59%   |
| Toshiba MK5061GSY 500GB                        | 2         | 2      | 0.59%   |
| Toshiba MK3275GSX 320GB                        | 2         | 3      | 0.59%   |
| SPCC Solid State Disk 256GB                    | 2         | 2      | 0.59%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 2         | 2      | 0.59%   |
| Seagate ST9750420AS 752GB                      | 2         | 2      | 0.59%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.59%   |
| Seagate ST500LM000-SSHD-8GB                    | 2         | 3      | 0.59%   |
| Seagate ST500LM000-1EJ162 500GB                | 2         | 2      | 0.59%   |
| SanDisk SSD PLUS 240GB                         | 2         | 2      | 0.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 71        | 88     | 21.13%  |
| WDC                 | 34        | 37     | 10.12%  |
| Toshiba             | 34        | 36     | 10.12%  |
| HGST                | 30        | 32     | 8.93%   |
| Samsung Electronics | 27        | 32     | 8.04%   |
| Hitachi             | 22        | 26     | 6.55%   |
| Micron Technology   | 16        | 19     | 4.76%   |
| SK hynix            | 15        | 16     | 4.46%   |
| Intel               | 15        | 26     | 4.46%   |
| SanDisk             | 14        | 16     | 4.17%   |
| Crucial             | 14        | 22     | 4.17%   |
| Kingston            | 9         | 11     | 2.68%   |
| A-DATA Technology   | 5         | 5      | 1.49%   |
| LITEON              | 4         | 4      | 1.19%   |
| LITEONIT            | 3         | 4      | 0.89%   |
| Fujitsu             | 3         | 3      | 0.89%   |
| SPCC                | 2         | 2      | 0.6%    |
| China               | 2         | 2      | 0.6%    |
| YS                  | 1         | 1      | 0.3%    |
| Wibtek              | 1         | 1      | 0.3%    |
| walram              | 1         | 1      | 0.3%    |
| Union Memory        | 1         | 1      | 0.3%    |
| Teclast             | 1         | 1      | 0.3%    |
| SSSTC               | 1         | 1      | 0.3%    |
| SSD                 | 1         | 1      | 0.3%    |
| PNY                 | 1         | 1      | 0.3%    |
| Plextor             | 1         | 1      | 0.3%    |
| Origin              | 1         | 1      | 0.3%    |
| OCZ-VERTEX3         | 1         | 1      | 0.3%    |
| Netac               | 1         | 1      | 0.3%    |
| Lenovo              | 1         | 2      | 0.3%    |
| HGST HTS            | 1         | 1      | 0.3%    |
| Apple               | 1         | 1      | 0.3%    |
| Unknown             | 1         | 1      | 0.3%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 71        | 88     | 36.79%  |
| Toshiba             | 33        | 35     | 17.1%   |
| HGST                | 30        | 32     | 15.54%  |
| WDC                 | 28        | 31     | 14.51%  |
| Hitachi             | 22        | 26     | 11.4%   |
| Samsung Electronics | 4         | 4      | 2.07%   |
| Fujitsu             | 3         | 3      | 1.55%   |
| HGST HTS            | 1         | 1      | 0.52%   |
| Apple               | 1         | 1      | 0.52%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 192       | 221    | 57.49%  |
| SSD  | 116       | 148    | 34.73%  |
| NVMe | 26        | 29     | 7.78%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Notebooks | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 14.29%  |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1         | 1      | 14.29%  |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 500GB                | 1         | 1      | 14.29%  |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 14.29%  |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 14.29%  |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 3         | 3      | 42.86%  |
| WDC                 | 1         | 1      | 14.29%  |
| Toshiba             | 1         | 1      | 14.29%  |
| Seagate             | 1         | 1      | 14.29%  |
| HGST                | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4787      | 7842   | 55.19%  |
| Works    | 3554      | 5098   | 40.98%  |
| Malfunc  | 325       | 398    | 3.75%   |
| Failed   | 7         | 7      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 4846      | 47.72%  |
| Samsung Electronics                     | 1512      | 14.89%  |
| AMD                                     | 844       | 8.31%   |
| SanDisk                                 | 764       | 7.52%   |
| SK hynix                                | 518       | 5.1%    |
| Micron Technology                       | 294       | 2.9%    |
| Toshiba America Info Systems            | 270       | 2.66%   |
| Kingston Technology Company             | 182       | 1.79%   |
| KIOXIA                                  | 167       | 1.64%   |
| Phison Electronics                      | 138       | 1.36%   |
| ADATA Technology                        | 104       | 1.02%   |
| Silicon Motion                          | 91        | 0.9%    |
| Micron/Crucial Technology               | 86        | 0.85%   |
| Union Memory (Shenzhen)                 | 46        | 0.45%   |
| Solid State Storage Technology          | 38        | 0.37%   |
| Nvidia                                  | 34        | 0.33%   |
| Realtek Semiconductor                   | 31        | 0.31%   |
| Apple                                   | 31        | 0.31%   |
| Lite-On Technology                      | 29        | 0.29%   |
| Lenovo                                  | 26        | 0.26%   |
| MAXIO Technology (Hangzhou)             | 15        | 0.15%   |
| Yangtze Memory Technologies             | 12        | 0.12%   |
| Shenzhen Longsys Electronics            | 12        | 0.12%   |
| Marvell Technology Group                | 12        | 0.12%   |
| Seagate Technology                      | 11        | 0.11%   |
| Solidigm                                | 8         | 0.08%   |
| Netac Technology                        | 6         | 0.06%   |
| JMicron Technology                      | 5         | 0.05%   |
| Biwin Storage Technology                | 5         | 0.05%   |
| Shenzhen Unionmemory Information System | 4         | 0.04%   |
| INNOGRIT                                | 3         | 0.03%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.02%   |
| ASMedia Technology                      | 2         | 0.02%   |
| ULi Electronics                         | 1         | 0.01%   |
| Transcend                               | 1         | 0.01%   |
| OCZ Technology Group                    | 1         | 0.01%   |
| Lite-On IT Corp. / Plextor              | 1         | 0.01%   |
| Enmotus                                 | 1         | 0.01%   |
| Beijing Starblaze Technology            | 1         | 0.01%   |
| Unknown                                 | 1         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 802       | 7.53%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 749       | 7.03%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 692       | 6.5%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 472       | 4.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 456       | 4.28%   |
| Intel Volume Management Device NVMe RAID Controller                            | 388       | 3.64%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 346       | 3.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 278       | 2.61%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 277       | 2.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 250       | 2.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 235       | 2.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 228       | 2.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 205       | 1.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 198       | 1.86%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 192       | 1.8%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 181       | 1.7%    |
| Intel Tiger Lake-LP SATA Controller                                            | 153       | 1.44%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 152       | 1.43%   |
| Intel Comet Lake SATA AHCI Controller                                          | 139       | 1.31%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 129       | 1.21%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 123       | 1.16%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 116       | 1.09%   |
| Intel SSD 660P Series                                                          | 114       | 1.07%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 105       | 0.99%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 104       | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 90        | 0.85%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 90        | 0.85%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 87        | 0.82%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 84        | 0.79%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 77        | 0.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 76        | 0.71%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 74        | 0.7%    |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 74        | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 70        | 0.66%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 68        | 0.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 68        | 0.64%   |
| SK hynix BC511 NVMe SSD                                                        | 66        | 0.62%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 58        | 0.54%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 57        | 0.54%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 55        | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 4791      | 46.86%  |
| NVMe | 4381      | 42.85%  |
| RAID | 905       | 8.85%   |
| IDE  | 147       | 1.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 6449      | 79.51%  |
| AMD          | 1655      | 20.4%   |
| ARM          | 4         | 0.05%   |
| Unknown      | 2         | 0.02%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 202       | 2.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 171       | 2.11%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 164       | 2.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 163       | 2.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 129       | 1.59%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 126       | 1.55%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 125       | 1.54%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 124       | 1.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 122       | 1.5%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 116       | 1.43%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 113       | 1.39%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 107       | 1.32%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 105       | 1.29%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 105       | 1.29%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 104       | 1.28%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 100       | 1.23%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 92        | 1.13%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 87        | 1.07%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 81        | 1%      |
| Intel Core i5-5200U CPU @ 2.20GHz             | 78        | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 76        | 0.94%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 75        | 0.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 75        | 0.92%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 70        | 0.86%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 64        | 0.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 63        | 0.78%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 62        | 0.76%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 59        | 0.73%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 58        | 0.71%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 54        | 0.67%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 54        | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 53        | 0.65%   |
| Intel 12th Gen Core i7-12700H                 | 53        | 0.65%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 53        | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 52        | 0.64%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 52        | 0.64%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 51        | 0.63%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 47        | 0.58%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 46        | 0.57%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 46        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 2207      | 27.2%   |
| Intel Core i5                  | 1959      | 24.14%  |
| Other                          | 1103      | 13.59%  |
| AMD Ryzen 7                    | 513       | 6.32%   |
| AMD Ryzen 5                    | 512       | 6.31%   |
| Intel Core i3                  | 468       | 5.77%   |
| Intel Celeron                  | 204       | 2.51%   |
| Intel Core 2 Duo               | 139       | 1.71%   |
| AMD Ryzen 7 PRO                | 122       | 1.5%    |
| AMD Ryzen 9                    | 120       | 1.48%   |
| Intel Atom                     | 119       | 1.47%   |
| Intel Pentium                  | 89        | 1.1%    |
| AMD Ryzen 3                    | 73        | 0.9%    |
| Intel Core i9                  | 63        | 0.78%   |
| AMD Ryzen 5 PRO                | 56        | 0.69%   |
| AMD A6                         | 48        | 0.59%   |
| AMD A10                        | 39        | 0.48%   |
| AMD A8                         | 33        | 0.41%   |
| Intel Pentium Silver           | 27        | 0.33%   |
| AMD A4                         | 24        | 0.3%    |
| Intel Xeon                     | 19        | 0.23%   |
| Intel Pentium Dual-Core        | 17        | 0.21%   |
| AMD E1                         | 15        | 0.18%   |
| AMD Athlon                     | 13        | 0.16%   |
| Intel Pentium Dual             | 12        | 0.15%   |
| AMD A12                        | 12        | 0.15%   |
| Intel Core m5                  | 11        | 0.14%   |
| Intel Core m3                  | 11        | 0.14%   |
| AMD E                          | 9         | 0.11%   |
| Intel Genuine                  | 8         | 0.1%    |
| AMD E2                         | 8         | 0.1%    |
| Intel Core M                   | 7         | 0.09%   |
| Intel Core m7                  | 5         | 0.06%   |
| AMD Athlon II                  | 5         | 0.06%   |
| Intel Core 2                   | 4         | 0.05%   |
| Intel Celeron Dual-Core        | 4         | 0.05%   |
| AMD PRO A10                    | 4         | 0.05%   |
| AMD Phenom II                  | 4         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.04%   |
| AMD Ryzen 3 PRO                | 3         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 3142      | 38.72%  |
| 2       | 2887      | 35.58%  |
| 8       | 864       | 10.65%  |
| 6       | 799       | 9.85%   |
| 12      | 132       | 1.63%   |
| 14      | 126       | 1.55%   |
| 10      | 114       | 1.4%    |
| 1       | 26        | 0.32%   |
| 24      | 10        | 0.12%   |
| 16      | 9         | 0.11%   |
| 3       | 2         | 0.02%   |
| 20      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 8110      | 99.98%  |
| 2       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 7136      | 87.84%  |
| 1       | 987       | 12.15%  |
| Unknown | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7973      | 98.04%  |
| Unknown        | 151       | 1.86%   |
| 64-bit         | 4         | 0.05%   |
| 32-bit         | 4         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2201      | 26.24%  |
| 0x806ec    | 398       | 4.74%   |
| 0x806ea    | 383       | 4.57%   |
| 0x306a9    | 357       | 4.26%   |
| 0x806c1    | 349       | 4.16%   |
| 0x206a7    | 279       | 3.33%   |
| 0x906ea    | 273       | 3.25%   |
| 0x406e3    | 272       | 3.24%   |
| 0x806e9    | 269       | 3.21%   |
| 0x0a50000c | 239       | 2.85%   |
| 0x40651    | 221       | 2.63%   |
| 0x306d4    | 216       | 2.57%   |
| 0x306c3    | 168       | 2%      |
| 0xa0652    | 166       | 1.98%   |
| 0x08600106 | 158       | 1.88%   |
| 0x08108109 | 142       | 1.69%   |
| 0x08108102 | 126       | 1.5%    |
| 0x08608103 | 123       | 1.47%   |
| 0x906e9    | 118       | 1.41%   |
| 0x506e3    | 112       | 1.34%   |
| 0x706e5    | 104       | 1.24%   |
| 0x906a3    | 88        | 1.05%   |
| 0x0a404102 | 88        | 1.05%   |
| 0x08600104 | 86        | 1.03%   |
| 0x20655    | 81        | 0.97%   |
| 0x806eb    | 75        | 0.89%   |
| 0x30678    | 75        | 0.89%   |
| 0x1067a    | 70        | 0.83%   |
| 0x0a50000d | 67        | 0.8%    |
| 0x806d1    | 61        | 0.73%   |
| 0x906ed    | 56        | 0.67%   |
| 0x08600103 | 56        | 0.67%   |
| 0x406c4    | 42        | 0.5%    |
| 0x08608102 | 42        | 0.5%    |
| 0x0810100b | 42        | 0.5%    |
| 0x0a404101 | 40        | 0.48%   |
| 0x06006705 | 35        | 0.42%   |
| 0x706a8    | 34        | 0.41%   |
| 0x406c3    | 31        | 0.37%   |
| 0x906a4    | 29        | 0.35%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 2066      | 25.44%  |
| TigerLake         | 570       | 7.02%   |
| Haswell           | 548       | 6.75%   |
| Skylake           | 512       | 6.31%   |
| IvyBridge         | 472       | 5.81%   |
| Unknown           | 400       | 4.93%   |
| Alderlake Hybrid  | 388       | 4.78%   |
| SandyBridge       | 370       | 4.56%   |
| Zen 2             | 354       | 4.36%   |
| Zen 3             | 339       | 4.17%   |
| Broadwell         | 282       | 3.47%   |
| Zen+              | 276       | 3.4%    |
| CometLake         | 251       | 3.09%   |
| Icelake           | 240       | 2.96%   |
| Silvermont        | 212       | 2.61%   |
| Westmere          | 154       | 1.9%    |
| Penryn            | 137       | 1.69%   |
| Goldmont plus     | 88        | 1.08%   |
| Zen               | 84        | 1.03%   |
| Excavator         | 79        | 0.97%   |
| Core              | 46        | 0.57%   |
| Goldmont          | 43        | 0.53%   |
| Piledriver        | 37        | 0.46%   |
| Puma              | 36        | 0.44%   |
| Jaguar            | 25        | 0.31%   |
| Nehalem           | 22        | 0.27%   |
| Bobcat            | 17        | 0.21%   |
| Tremont           | 15        | 0.18%   |
| K10               | 14        | 0.17%   |
| K10 Llano         | 10        | 0.12%   |
| Steamroller       | 9         | 0.11%   |
| K8 & K10 hybrid   | 6         | 0.07%   |
| Bonnell           | 6         | 0.07%   |
| K8 Hammer         | 5         | 0.06%   |
| P6                | 3         | 0.04%   |
| Gracemont         | 2         | 0.02%   |
| NetBurst          | 1         | 0.01%   |
| Meteorlake Hybrid | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6093      | 57.29%  |
| Nvidia                           | 2521      | 23.7%   |
| AMD                              | 2019      | 18.98%  |
| Zhaoxin                          | 1         | 0.01%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 521       | 4.81%   |
| Intel UHD Graphics 620                                                                   | 491       | 4.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 439       | 4.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 355       | 3.28%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 345       | 3.18%   |
| Intel HD Graphics 620                                                                    | 340       | 3.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 333       | 3.07%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 332       | 3.06%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 318       | 2.93%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 288       | 2.66%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 283       | 2.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 278       | 2.56%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 257       | 2.37%   |
| Intel HD Graphics 5500                                                                   | 239       | 2.21%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 211       | 1.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 206       | 1.9%    |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 184       | 1.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 177       | 1.63%   |
| AMD Lucienne                                                                             | 177       | 1.63%   |
| Intel HD Graphics 630                                                                    | 137       | 1.26%   |
| AMD Rembrandt [Radeon 680M]                                                              | 133       | 1.23%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 123       | 1.13%   |
| Intel HD Graphics 530                                                                    | 120       | 1.11%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 119       | 1.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 117       | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 100       | 0.92%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 100       | 0.92%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 95        | 0.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 93        | 0.86%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 91        | 0.84%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 91        | 0.84%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 81        | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 79        | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 76        | 0.7%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 73        | 0.67%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 67        | 0.62%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 67        | 0.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 67        | 0.62%   |
| AMD Barcelo                                                                              | 64        | 0.59%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 60        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 3859      | 47.38%  |
| Intel + Nvidia     | 1919      | 23.56%  |
| 1 x AMD            | 1285      | 15.78%  |
| 1 x Nvidia         | 308       | 3.78%   |
| AMD + Nvidia       | 298       | 3.66%   |
| Intel + AMD        | 296       | 3.63%   |
| 2 x AMD            | 143       | 1.76%   |
| 2 x Intel          | 18        | 0.22%   |
| Other              | 11        | 0.14%   |
| 2 x Nvidia         | 4         | 0.05%   |
| Intel + 2 x Nvidia | 2         | 0.02%   |
| 1 x Zhaoxin        | 1         | 0.01%   |
| 1 x SiS            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 6969      | 84.85%  |
| Proprietary | 1114      | 13.56%  |
| Unknown     | 130       | 1.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 5034      | 60.76%  |
| 1.01-2.0   | 1033      | 12.47%  |
| 0.01-0.5   | 914       | 11.03%  |
| 3.01-4.0   | 565       | 6.82%   |
| 0.51-1.0   | 450       | 5.43%   |
| 5.01-6.0   | 121       | 1.46%   |
| 7.01-8.0   | 111       | 1.34%   |
| 8.01-16.0  | 30        | 0.36%   |
| 2.01-3.0   | 27        | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1687      | 16.97%  |
| BOE                     | 1554      | 15.63%  |
| Chimei Innolux          | 1347      | 13.55%  |
| LG Display              | 1221      | 12.28%  |
| Samsung Electronics     | 808       | 8.13%   |
| Dell                    | 452       | 4.55%   |
| Sharp                   | 396       | 3.98%   |
| Goldstar                | 305       | 3.07%   |
| Apple                   | 241       | 2.42%   |
| Lenovo                  | 203       | 2.04%   |
| PANDA                   | 183       | 1.84%   |
| Hewlett-Packard         | 158       | 1.59%   |
| CSO                     | 127       | 1.28%   |
| Chi Mei Optoelectronics | 106       | 1.07%   |
| AOC                     | 102       | 1.03%   |
| Acer                    | 98        | 0.99%   |
| Philips                 | 97        | 0.98%   |
| BenQ                    | 97        | 0.98%   |
| InfoVision              | 92        | 0.93%   |
| Ancor Communications    | 68        | 0.68%   |
| TMX                     | 47        | 0.47%   |
| Iiyama                  | 47        | 0.47%   |
| ASUSTek Computer        | 41        | 0.41%   |
| ViewSonic               | 39        | 0.39%   |
| Sony                    | 25        | 0.25%   |
| Panasonic               | 25        | 0.25%   |
| Toshiba                 | 20        | 0.2%    |
| LG Philips              | 20        | 0.2%    |
| JDI                     | 20        | 0.2%    |
| MSI                     | 19        | 0.19%   |
| Gigabyte Technology     | 16        | 0.16%   |
| Sceptre Tech            | 12        | 0.12%   |
| CPT                     | 11        | 0.11%   |
| NEC Computers           | 10        | 0.1%    |
| Eizo                    | 10        | 0.1%    |
| Vizio                   | 9         | 0.09%   |
| HKC                     | 9         | 0.09%   |
| HannStar                | 9         | 0.09%   |
| Fujitsu Siemens         | 8         | 0.08%   |
| CTO                     | 8         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 79        | 0.78%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 67        | 0.66%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 65        | 0.64%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 61        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 60        | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 52        | 0.52%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 49        | 0.49%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 47        | 0.47%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 46        | 0.46%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 45        | 0.45%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 42        | 0.42%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 41        | 0.41%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 39        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 38        | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 35        | 0.35%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 34        | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 34        | 0.34%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 32        | 0.32%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 31        | 0.31%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 30        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 29        | 0.29%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 29        | 0.29%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 29        | 0.29%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 28        | 0.28%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 28        | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 26        | 0.26%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 26        | 0.26%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 25        | 0.25%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch         | 25        | 0.25%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 25        | 0.25%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 25        | 0.25%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 25        | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 25        | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 25        | 0.25%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 25        | 0.25%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch       | 25        | 0.25%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 24        | 0.24%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 24        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 24        | 0.24%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 23        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4572      | 50.01%  |
| 1366x768 (WXGA)    | 1732      | 18.94%  |
| 3840x2160 (4K)     | 524       | 5.73%   |
| 2560x1440 (QHD)    | 397       | 4.34%   |
| 1920x1200 (WUXGA)  | 303       | 3.31%   |
| 1600x900 (HD+)     | 295       | 3.23%   |
| 2560x1600          | 217       | 2.37%   |
| 1280x800 (WXGA)    | 148       | 1.62%   |
| 2880x1800          | 138       | 1.51%   |
| 2560x1080          | 91        | 1%      |
| 1440x900 (WXGA+)   | 91        | 1%      |
| 3440x1440          | 83        | 0.91%   |
| 3840x2400          | 69        | 0.75%   |
| 2160x1440          | 58        | 0.63%   |
| 1680x1050 (WSXGA+) | 53        | 0.58%   |
| 2256x1504          | 49        | 0.54%   |
| 1280x1024 (SXGA)   | 41        | 0.45%   |
| 3200x1800 (QHD+)   | 39        | 0.43%   |
| 3200x2000          | 23        | 0.25%   |
| 1360x768           | 21        | 0.23%   |
| 3000x2000          | 20        | 0.22%   |
| 2520x1680          | 17        | 0.19%   |
| 3456x2160          | 15        | 0.16%   |
| 3072x1920          | 15        | 0.16%   |
| 2240x1400          | 14        | 0.15%   |
| 1920x1280          | 13        | 0.14%   |
| 3840x1600          | 11        | 0.12%   |
| 2880x1620          | 10        | 0.11%   |
| 2160x1350          | 10        | 0.11%   |
| 3840x1080          | 8         | 0.09%   |
| 1024x768 (XGA)     | 7         | 0.08%   |
| 1920x540           | 6         | 0.07%   |
| 3840x1100          | 5         | 0.05%   |
| 1024x600           | 5         | 0.05%   |
| 2304x1440          | 4         | 0.04%   |
| Unknown            | 4         | 0.04%   |
| 800x1280           | 3         | 0.03%   |
| 3120x2080          | 3         | 0.03%   |
| 2288x1287          | 3         | 0.03%   |
| 1680x945           | 3         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3659      | 36.8%   |
| 13      | 1586      | 15.95%  |
| 14      | 1440      | 14.48%  |
| 17      | 473       | 4.76%   |
| 27      | 469       | 4.72%   |
| 24      | 434       | 4.36%   |
| 23      | 295       | 2.97%   |
| 12      | 246       | 2.47%   |
| 21      | 237       | 2.38%   |
| 16      | 219       | 2.2%    |
| 34      | 150       | 1.51%   |
| 31      | 102       | 1.03%   |
| 11      | 86        | 0.86%   |
| 18      | 80        | 0.8%    |
| 19      | 51        | 0.51%   |
| 20      | 41        | 0.41%   |
| 22      | 35        | 0.35%   |
| Unknown | 31        | 0.31%   |
| 40      | 29        | 0.29%   |
| 25      | 27        | 0.27%   |
| 84      | 25        | 0.25%   |
| 32      | 21        | 0.21%   |
| 26      | 19        | 0.19%   |
| 28      | 18        | 0.18%   |
| 54      | 17        | 0.17%   |
| 10      | 16        | 0.16%   |
| 72      | 15        | 0.15%   |
| 29      | 15        | 0.15%   |
| 35      | 14        | 0.14%   |
| 37      | 11        | 0.11%   |
| 48      | 8         | 0.08%   |
| 86      | 6         | 0.06%   |
| 39      | 6         | 0.06%   |
| 42      | 5         | 0.05%   |
| 74      | 4         | 0.04%   |
| 57      | 4         | 0.04%   |
| 52      | 4         | 0.04%   |
| 46      | 4         | 0.04%   |
| 38      | 4         | 0.04%   |
| 36      | 4         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 6008      | 61.11%  |
| 201-300        | 1127      | 11.46%  |
| 501-600        | 1111      | 11.3%   |
| 351-400        | 587       | 5.97%   |
| 401-500        | 417       | 4.24%   |
| 601-700        | 186       | 1.89%   |
| 701-800        | 179       | 1.82%   |
| 801-900        | 63        | 0.64%   |
| 1001-1500      | 58        | 0.59%   |
| 1501-2000      | 48        | 0.49%   |
| Unknown        | 31        | 0.32%   |
| 901-1000       | 9         | 0.09%   |
| 1-100          | 3         | 0.03%   |
| More than 2000 | 2         | 0.02%   |
| 101-200        | 2         | 0.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6845      | 81.07%  |
| 16/10   | 1124      | 13.31%  |
| 21/9    | 185       | 2.19%   |
| 3/2     | 177       | 2.1%    |
| 5/4     | 43        | 0.51%   |
| 4/3     | 18        | 0.21%   |
| 32/9    | 14        | 0.17%   |
| Unknown | 13        | 0.15%   |
| 0.56    | 7         | 0.08%   |
| 3.40    | 5         | 0.06%   |
| 0.67    | 3         | 0.04%   |
| 6/5     | 2         | 0.02%   |
| 1.00    | 2         | 0.02%   |
| 3.88    | 1         | 0.01%   |
| 3.73    | 1         | 0.01%   |
| 3.33    | 1         | 0.01%   |
| 0.89    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 3668      | 36.98%  |
| 81-90          | 2425      | 24.45%  |
| 201-250        | 788       | 7.95%   |
| 71-80          | 572       | 5.77%   |
| 301-350        | 489       | 4.93%   |
| 121-130        | 428       | 4.32%   |
| 351-500        | 309       | 3.12%   |
| 61-70          | 234       | 2.36%   |
| 111-120        | 202       | 2.04%   |
| 251-300        | 174       | 1.75%   |
| 151-200        | 150       | 1.51%   |
| More than 1000 | 93        | 0.94%   |
| 51-60          | 91        | 0.92%   |
| 141-150        | 88        | 0.89%   |
| 501-1000       | 77        | 0.78%   |
| 131-140        | 39        | 0.39%   |
| 91-100         | 38        | 0.38%   |
| Unknown        | 31        | 0.31%   |
| 41-50          | 16        | 0.16%   |
| 1-40           | 6         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 4333      | 44.72%  |
| 101-120       | 2127      | 21.95%  |
| 51-100        | 1474      | 15.21%  |
| 161-240       | 1126      | 11.62%  |
| More than 240 | 524       | 5.41%   |
| 1-50          | 74        | 0.76%   |
| Unknown       | 31        | 0.32%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 6178      | 73.52%  |
| 2     | 1774      | 21.11%  |
| 3     | 238       | 2.83%   |
| 0     | 193       | 2.3%    |
| 4     | 17        | 0.2%    |
| 5     | 3         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 4853      | 39.42%  |
| Realtek Semiconductor             | 4073      | 33.08%  |
| Qualcomm Atheros                  | 1269      | 10.31%  |
| Broadcom                          | 572       | 4.65%   |
| MediaTek                          | 347       | 2.82%   |
| Broadcom Limited                  | 129       | 1.05%   |
| Lenovo                            | 108       | 0.88%   |
| ASIX Electronics                  | 97        | 0.79%   |
| TP-Link                           | 76        | 0.62%   |
| Qualcomm                          | 74        | 0.6%    |
| Sierra Wireless                   | 72        | 0.58%   |
| DisplayLink                       | 51        | 0.41%   |
| Dell                              | 51        | 0.41%   |
| Ralink                            | 47        | 0.38%   |
| Samsung Electronics               | 45        | 0.37%   |
| Marvell Technology Group          | 45        | 0.37%   |
| Ralink Technology                 | 44        | 0.36%   |
| Xiaomi                            | 36        | 0.29%   |
| Ericsson Business Mobile Networks | 32        | 0.26%   |
| Hewlett-Packard                   | 31        | 0.25%   |
| Nvidia                            | 25        | 0.2%    |
| Huawei Technologies               | 22        | 0.18%   |
| Google                            | 18        | 0.15%   |
| ASUSTek Computer                  | 18        | 0.15%   |
| Apple                             | 16        | 0.13%   |
| Fibocom                           | 13        | 0.11%   |
| OPPO Electronics                  | 12        | 0.1%    |
| JMicron Technology                | 12        | 0.1%    |
| NetGear                           | 11        | 0.09%   |
| Qualcomm Atheros Communications   | 9         | 0.07%   |
| D-Link                            | 9         | 0.07%   |
| D-Link System                     | 7         | 0.06%   |
| T & A Mobile Phones               | 6         | 0.05%   |
| Microsoft                         | 6         | 0.05%   |
| Linksys                           | 6         | 0.05%   |
| Edimax Technology                 | 6         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.04%   |
| Motorola PCS                      | 5         | 0.04%   |
| Cypress Semiconductor             | 4         | 0.03%   |
| Belkin Components                 | 4         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2508      | 16.78%  |
| Intel Wi-Fi 6 AX200                                               | 543       | 3.63%   |
| Intel Wireless 8265 / 8275                                        | 507       | 3.39%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 499       | 3.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 471       | 3.15%   |
| Intel Wi-Fi 6 AX201                                               | 434       | 2.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 304       | 2.03%   |
| Intel Wireless 8260                                               | 270       | 1.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 269       | 1.8%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 269       | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 267       | 1.79%   |
| Intel Wireless 7260                                               | 256       | 1.71%   |
| Intel Wireless 7265                                               | 248       | 1.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 247       | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 239       | 1.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 212       | 1.42%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 211       | 1.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 207       | 1.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 200       | 1.34%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 199       | 1.33%   |
| Intel Ethernet Connection (4) I219-LM                             | 193       | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 191       | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 159       | 1.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 152       | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 138       | 0.92%   |
| Intel Wireless 3165                                               | 130       | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 122       | 0.82%   |
| Intel Ethernet Connection (4) I219-V                              | 112       | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 101       | 0.68%   |
| Intel Wireless-AC 9260                                            | 101       | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 98        | 0.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 98        | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                     | 93        | 0.62%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 92        | 0.62%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 90        | 0.6%    |
| Intel Ethernet Connection I218-LM                                 | 89        | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                     | 89        | 0.6%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 86        | 0.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 86        | 0.58%   |
| Intel Ethernet Connection (3) I218-LM                             | 84        | 0.56%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4724      | 56.6%   |
| Realtek Semiconductor                 | 1162      | 13.92%  |
| Qualcomm Atheros                      | 1109      | 13.29%  |
| Broadcom                              | 481       | 5.76%   |
| MediaTek                              | 336       | 4.03%   |
| Broadcom Limited                      | 102       | 1.22%   |
| Sierra Wireless                       | 72        | 0.86%   |
| Qualcomm                              | 59        | 0.71%   |
| TP-Link                               | 56        | 0.67%   |
| Ralink                                | 47        | 0.56%   |
| Ralink Technology                     | 44        | 0.53%   |
| Dell                                  | 44        | 0.53%   |
| ASUSTek Computer                      | 17        | 0.2%    |
| Fibocom                               | 13        | 0.16%   |
| NetGear                               | 10        | 0.12%   |
| Qualcomm Atheros Communications       | 9         | 0.11%   |
| Hewlett-Packard                       | 9         | 0.11%   |
| Ericsson Business Mobile Networks     | 9         | 0.11%   |
| D-Link System                         | 7         | 0.08%   |
| Edimax Technology                     | 6         | 0.07%   |
| D-Link                                | 6         | 0.07%   |
| Linksys                               | 5         | 0.06%   |
| Microsoft                             | 4         | 0.05%   |
| Belkin Components                     | 4         | 0.05%   |
| Quectel Wireless Solutions            | 2         | 0.02%   |
| Unknown                               | 2         | 0.02%   |
| ZyDAS                                 | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |
| Sitecom Europe                        | 1         | 0.01%   |
| Qualcomm Technologies                 | 1         | 0.01%   |
| IMC Networks                          | 1         | 0.01%   |
| AVM                                   | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 543       | 6.47%   |
| Intel Wireless 8265 / 8275                                     | 507       | 6.04%   |
| Intel Wi-Fi 6 AX201                                            | 434       | 5.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 304       | 3.62%   |
| Intel Wireless 8260                                            | 270       | 3.22%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 269       | 3.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 267       | 3.18%   |
| Intel Wireless 7260                                            | 256       | 3.05%   |
| Intel Wireless 7265                                            | 248       | 2.95%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 247       | 2.94%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 239       | 2.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 212       | 2.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 211       | 2.51%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 207       | 2.47%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 200       | 2.38%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 199       | 2.37%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 191       | 2.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 159       | 1.89%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 152       | 1.81%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 138       | 1.64%   |
| Intel Wireless 3165                                            | 130       | 1.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 101       | 1.2%    |
| Intel Wireless-AC 9260                                         | 101       | 1.2%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 98        | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 98        | 1.17%   |
| Broadcom BCM43142 802.11b/g/n                                  | 93        | 1.11%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 92        | 1.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 87        | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 86        | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 86        | 1.02%   |
| Intel Wireless 3160                                            | 80        | 0.95%   |
| Intel Centrino Ultimate-N 6300                                 | 80        | 0.95%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 75        | 0.89%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 73        | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 66        | 0.79%   |
| Intel Raptor Lake PCH CNVi WiFi                                | 58        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 56        | 0.67%   |
| Intel Centrino Advanced-N 6235                                 | 54        | 0.64%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 54        | 0.64%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 47        | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3574      | 56.29%  |
| Intel                                  | 1742      | 27.44%  |
| Qualcomm Atheros                       | 265       | 4.17%   |
| Broadcom                               | 180       | 2.84%   |
| Lenovo                                 | 105       | 1.65%   |
| ASIX Electronics                       | 97        | 1.53%   |
| DisplayLink                            | 51        | 0.8%    |
| Marvell Technology Group               | 45        | 0.71%   |
| Samsung Electronics                    | 37        | 0.58%   |
| Xiaomi                                 | 36        | 0.57%   |
| Broadcom Limited                       | 27        | 0.43%   |
| Nvidia                                 | 25        | 0.39%   |
| TP-Link                                | 22        | 0.35%   |
| Google                                 | 18        | 0.28%   |
| Apple                                  | 16        | 0.25%   |
| Qualcomm                               | 15        | 0.24%   |
| Huawei Technologies                    | 14        | 0.22%   |
| OPPO Electronics                       | 12        | 0.19%   |
| JMicron Technology                     | 12        | 0.19%   |
| MediaTek                               | 11        | 0.17%   |
| Hewlett-Packard                        | 8         | 0.13%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.06%   |
| Cypress Semiconductor                  | 4         | 0.06%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| D-Link                                 | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.03%   |
| Spreadtrum Communications              | 2         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.03%   |
| Motorola PCS                           | 2         | 0.03%   |
| Microsoft                              | 2         | 0.03%   |
| ICS Advent                             | 2         | 0.03%   |
| vivo                                   | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Linksys                                | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| HMD Global                             | 1         | 0.02%   |
| Foxconn / Hon Hai                      | 1         | 0.02%   |
| ASUSTek Computer                       | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2508      | 38.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 499       | 7.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 471       | 7.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 269       | 4.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 193       | 2.99%   |
| Intel Ethernet Connection I219-LM                                 | 122       | 1.89%   |
| Intel Ethernet Connection (4) I219-V                              | 112       | 1.73%   |
| Intel Ethernet Connection I218-LM                                 | 89        | 1.38%   |
| ASIX AX88179 Gigabit Ethernet                                     | 89        | 1.38%   |
| Intel Ethernet Connection (3) I218-LM                             | 84        | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 80        | 1.24%   |
| Intel Ethernet Connection (6) I219-V                              | 78        | 1.21%   |
| Intel Ethernet Connection (6) I219-LM                             | 66        | 1.02%   |
| Intel Ethernet Connection (10) I219-V                             | 63        | 0.98%   |
| Intel Ethernet Connection (7) I219-LM                             | 62        | 0.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 60        | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 52        | 0.8%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 51        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 49        | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 46        | 0.71%   |
| Intel Ethernet Connection I219-V                                  | 45        | 0.7%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 42        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                             | 39        | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 38        | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 38        | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 37        | 0.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 37        | 0.57%   |
| Intel Ethernet Connection (16) I219-V                             | 36        | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 32        | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 31        | 0.48%   |
| Intel Ethernet Connection (7) I219-V                              | 31        | 0.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 29        | 0.45%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 27        | 0.42%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 26        | 0.4%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 26        | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 25        | 0.39%   |
| Intel 82567LM Gigabit Network Connection                          | 25        | 0.39%   |
| Realtek Killer E3000 2.5GbE Controller                            | 22        | 0.34%   |
| Nvidia MCP79 Ethernet                                             | 22        | 0.34%   |
| Intel Ethernet Connection I217-V                                  | 22        | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7957      | 56.77%  |
| Ethernet | 5965      | 42.56%  |
| Modem    | 80        | 0.57%   |
| Unknown  | 15        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6867      | 79.67%  |
| Ethernet | 1750      | 20.3%   |
| Modem    | 2         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 5286      | 65.11%  |
| 1     | 2588      | 31.88%  |
| 0     | 155       | 1.91%   |
| 3     | 89        | 1.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 6508      | 78.57%  |
| Yes     | 1772      | 21.39%  |
| Unknown | 3         | 0.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3963      | 57.15%  |
| Realtek Semiconductor           | 705       | 10.17%  |
| Qualcomm Atheros Communications | 558       | 8.05%   |
| IMC Networks                    | 313       | 4.51%   |
| Foxconn / Hon Hai               | 281       | 4.05%   |
| Broadcom                        | 271       | 3.91%   |
| Lite-On Technology              | 246       | 3.55%   |
| Apple                           | 200       | 2.88%   |
| Realtek                         | 86        | 1.24%   |
| Dell                            | 47        | 0.68%   |
| Cambridge Silicon Radio         | 47        | 0.68%   |
| Hewlett-Packard                 | 35        | 0.5%    |
| Ralink                          | 32        | 0.46%   |
| Toshiba                         | 28        | 0.4%    |
| USI                             | 25        | 0.36%   |
| MediaTek                        | 20        | 0.29%   |
| ASUSTek Computer                | 20        | 0.29%   |
| Foxconn International           | 16        | 0.23%   |
| Opticis                         | 12        | 0.17%   |
| Ralink Technology               | 5         | 0.07%   |
| Askey Computer                  | 4         | 0.06%   |
| Alps Electric                   | 4         | 0.06%   |
| Smart Modular Technologies      | 3         | 0.04%   |
| Chicony Electronics             | 3         | 0.04%   |
| Taiyo Yuden                     | 2         | 0.03%   |
| Qcom                            | 2         | 0.03%   |
| TP-Link                         | 1         | 0.01%   |
| Syntek                          | 1         | 0.01%   |
| Micro Star International        | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| Dynex                           | 1         | 0.01%   |
| Corsair                         | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1364      | 19.65%  |
| Intel AX201 Bluetooth                               | 869       | 12.52%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 592       | 8.53%   |
| Intel AX200 Bluetooth                               | 530       | 7.64%   |
| Realtek Bluetooth Radio                             | 409       | 5.89%   |
| Qualcomm Atheros  Bluetooth Device                  | 322       | 4.64%   |
| Intel Bluetooth Device                              | 229       | 3.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 151       | 2.18%   |
| IMC Networks Wireless_Device                        | 136       | 1.96%   |
| Intel AX210 Bluetooth                               | 132       | 1.9%    |
| Apple Bluetooth Host Controller                     | 131       | 1.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 93        | 1.34%   |
| IMC Networks Bluetooth Radio                        | 92        | 1.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 88        | 1.27%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 87        | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                  | 80        | 1.15%   |
| Realtek 802.11ac WLAN Adapter                       | 79        | 1.14%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 79        | 1.14%   |
| Realtek 802.11ac WLAN Adapter                       | 74        | 1.07%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 73        | 1.05%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 59        | 0.85%   |
| Lite-On Bluetooth Device                            | 58        | 0.84%   |
| Intel Wireless-AC 3168 Bluetooth                    | 52        | 0.75%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 52        | 0.75%   |
| Apple Bluetooth USB Host Controller                 | 49        | 0.71%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 47        | 0.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 46        | 0.66%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 44        | 0.63%   |
| IMC Networks Bluetooth Device                       | 42        | 0.61%   |
| Broadcom BCM2045B (BDC-2.1)                         | 41        | 0.59%   |
| Lite-On Wireless_Device                             | 38        | 0.55%   |
| Foxconn / Hon Hai Wireless_Device                   | 37        | 0.53%   |
| Ralink RT3290 Bluetooth                             | 32        | 0.46%   |
| Lite-On Atheros AR3012 Bluetooth                    | 30        | 0.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 27        | 0.39%   |
| HP Broadcom 2070 Bluetooth Combo                    | 26        | 0.37%   |
| USI Bluetooth Device                                | 25        | 0.36%   |
| Realtek RTL8723B Bluetooth                          | 24        | 0.35%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 24        | 0.35%   |
| Dell DW375 Bluetooth Module                         | 21        | 0.3%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 6293      | 60.14%  |
| AMD                                  | 1754      | 16.76%  |
| Nvidia                               | 1399      | 13.37%  |
| Lenovo                               | 132       | 1.26%   |
| C-Media Electronics                  | 105       | 1%      |
| Realtek Semiconductor                | 94        | 0.9%    |
| Logitech                             | 78        | 0.75%   |
| GN Netcom                            | 76        | 0.73%   |
| Plantronics                          | 42        | 0.4%    |
| Hewlett-Packard                      | 36        | 0.34%   |
| JMTek                                | 35        | 0.33%   |
| Kingston Technology                  | 23        | 0.22%   |
| Texas Instruments                    | 22        | 0.21%   |
| Sony                                 | 20        | 0.19%   |
| Creative Technology                  | 19        | 0.18%   |
| Apple                                | 18        | 0.17%   |
| SteelSeries ApS                      | 16        | 0.15%   |
| Razer USA                            | 15        | 0.14%   |
| ASUSTek Computer                     | 15        | 0.14%   |
| DSEA A/S                             | 14        | 0.13%   |
| Corsair                              | 13        | 0.12%   |
| Focusrite-Novation                   | 12        | 0.11%   |
| Dell                                 | 12        | 0.11%   |
| Generalplus Technology               | 11        | 0.11%   |
| Blue Microphones                     | 10        | 0.1%    |
| Samson Technologies                  | 9         | 0.09%   |
| RODE Microphones                     | 9         | 0.09%   |
| Microsoft                            | 9         | 0.09%   |
| Conexant Systems                     | 8         | 0.08%   |
| XMOS                                 | 7         | 0.07%   |
| Samsung Electronics                  | 7         | 0.07%   |
| No brand                             | 7         | 0.07%   |
| FiiO Electronics Technology          | 6         | 0.06%   |
| CMX Systems                          | 6         | 0.06%   |
| Tenx Technology                      | 5         | 0.05%   |
| SAVITECH                             | 5         | 0.05%   |
| GYROCOM C&C                          | 5         | 0.05%   |
| Yamaha                               | 4         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.04%   |
| PreSonus Audio Electronics           | 4         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1351      | 10.57%  |
| Intel Sunrise Point-LP HD Audio                                            | 1229      | 9.62%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 744       | 5.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 569       | 4.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 522       | 4.08%   |
| Intel Cannon Lake PCH cAVS                                                 | 404       | 3.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 345       | 2.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 332       | 2.6%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 320       | 2.5%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 315       | 2.46%   |
| Intel Comet Lake PCH-LP cAVS                                               | 304       | 2.38%   |
| Intel Haswell-ULT HD Audio Controller                                      | 292       | 2.28%   |
| Intel 8 Series HD Audio Controller                                         | 291       | 2.28%   |
| Intel Broadwell-U Audio Controller                                         | 282       | 2.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 279       | 2.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 255       | 2%      |
| Intel Comet Lake PCH cAVS                                                  | 229       | 1.79%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 206       | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 201       | 1.57%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 175       | 1.37%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 172       | 1.35%   |
| Intel CM238 HD Audio Controller                                            | 162       | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 160       | 1.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 144       | 1.13%   |
| Nvidia Audio device                                                        | 143       | 1.12%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 141       | 1.1%    |
| AMD FCH Azalia Controller                                                  | 126       | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 123       | 0.96%   |
| Nvidia TU106 High Definition Audio Controller                              | 99        | 0.77%   |
| AMD Kabini HDMI/DP Audio                                                   | 99        | 0.77%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 97        | 0.76%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 94        | 0.74%   |
| Realtek Semiconductor USB Audio                                            | 93        | 0.73%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 88        | 0.69%   |
| Nvidia GF108 High Definition Audio Controller                              | 83        | 0.65%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 76        | 0.59%   |
| Nvidia GK107 HDMI Audio Controller                                         | 75        | 0.59%   |
| Nvidia GA104 High Definition Audio Controller                              | 71        | 0.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 69        | 0.54%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 68        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1472      | 30%     |
| SK hynix            | 1102      | 22.46%  |
| Micron Technology   | 723       | 14.74%  |
| Kingston            | 394       | 8.03%   |
| Crucial             | 284       | 5.79%   |
| Unknown             | 241       | 4.91%   |
| Ramaxel Technology  | 111       | 2.26%   |
| A-DATA Technology   | 104       | 2.12%   |
| Corsair             | 63        | 1.28%   |
| Elpida              | 45        | 0.92%   |
| Smart               | 34        | 0.69%   |
| Unknown             | 32        | 0.65%   |
| G.Skill             | 31        | 0.63%   |
| Unknown (ABCD)      | 29        | 0.59%   |
| Team                | 26        | 0.53%   |
| Nanya Technology    | 24        | 0.49%   |
| Patriot             | 20        | 0.41%   |
| Teikon              | 17        | 0.35%   |
| Smart Brazil        | 13        | 0.26%   |
| Transcend           | 12        | 0.24%   |
| GOODRAM             | 11        | 0.22%   |
| Avant               | 9         | 0.18%   |
| Timetec             | 5         | 0.1%    |
| Silicon Power       | 5         | 0.1%    |
| Goldkey             | 5         | 0.1%    |
| Apacer              | 5         | 0.1%    |
| V-GEN               | 4         | 0.08%   |
| PUSKILL             | 4         | 0.08%   |
| Lexar               | 4         | 0.08%   |
| Kllisre             | 4         | 0.08%   |
| CSX                 | 4         | 0.08%   |
| ChangXin Memory     | 4         | 0.08%   |
| 4ea5                | 4         | 0.08%   |
| PNY                 | 3         | 0.06%   |
| OnBoard             | 3         | 0.06%   |
| ASint Technology    | 3         | 0.06%   |
| Unknown (0x0B5E)    | 2         | 0.04%   |
| SHARETRONIC         | 2         | 0.04%   |
| Sesame              | 2         | 0.04%   |
| RZX                 | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 85        | 1.65%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 75        | 1.46%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 68        | 1.32%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 60        | 1.16%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 52        | 1.01%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 45        | 0.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 44        | 0.85%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 43        | 0.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 43        | 0.83%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 37        | 0.72%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 36        | 0.7%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 35        | 0.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 35        | 0.68%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 32        | 0.62%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 32        | 0.62%   |
| Unknown                                                          | 32        | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 31        | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 31        | 0.6%    |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 31        | 0.6%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 30        | 0.58%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s         | 30        | 0.58%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 29        | 0.56%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 29        | 0.56%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 28        | 0.54%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 28        | 0.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 28        | 0.54%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 28        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 28        | 0.54%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 27        | 0.52%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 26        | 0.5%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 26        | 0.5%    |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 26        | 0.5%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 25        | 0.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.49%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 25        | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 25        | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.47%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 24        | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 23        | 0.45%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 23        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 2331      | 56.96%  |
| DDR3    | 989       | 24.17%  |
| LPDDR4  | 224       | 5.47%   |
| LPDDR3  | 216       | 5.28%   |
| LPDDR5  | 135       | 3.3%    |
| DDR5    | 107       | 2.61%   |
| DDR2    | 49        | 1.2%    |
| SDRAM   | 23        | 0.56%   |
| Unknown | 14        | 0.34%   |
| DDR     | 3         | 0.07%   |
| DRAM    | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3453      | 82.83%  |
| Row Of Chips | 617       | 14.8%   |
| Chip         | 52        | 1.25%   |
| Unknown      | 26        | 0.62%   |
| DIMM         | 21        | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1943      | 43.44%  |
| 4096  | 1105      | 24.7%   |
| 16384 | 870       | 19.45%  |
| 2048  | 324       | 7.24%   |
| 32768 | 176       | 3.93%   |
| 1024  | 50        | 1.12%   |
| 3072  | 2         | 0.04%   |
| 12288 | 1         | 0.02%   |
| 512   | 1         | 0.02%   |
| 64    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 1091      | 24.79%  |
| 2667    | 1002      | 22.77%  |
| 1600    | 715       | 16.25%  |
| 2400    | 297       | 6.75%   |
| 2133    | 290       | 6.59%   |
| 6400    | 128       | 2.91%   |
| 1333    | 120       | 2.73%   |
| 1334    | 115       | 2.61%   |
| 4267    | 108       | 2.45%   |
| 4800    | 95        | 2.16%   |
| 1867    | 90        | 2.04%   |
| 3266    | 60        | 1.36%   |
| 1067    | 44        | 1%      |
| Unknown | 35        | 0.8%    |
| 4266    | 33        | 0.75%   |
| 8400    | 29        | 0.66%   |
| 667     | 29        | 0.66%   |
| 1066    | 18        | 0.41%   |
| 5600    | 17        | 0.39%   |
| 4199    | 17        | 0.39%   |
| 3733    | 17        | 0.39%   |
| 800     | 15        | 0.34%   |
| 975     | 5         | 0.11%   |
| 7467    | 4         | 0.09%   |
| 2933    | 4         | 0.09%   |
| 2048    | 4         | 0.09%   |
| 5500    | 3         | 0.07%   |
| 533     | 3         | 0.07%   |
| 7500    | 2         | 0.05%   |
| 1866    | 2         | 0.05%   |
| 5200    | 1         | 0.02%   |
| 3600    | 1         | 0.02%   |
| 3400    | 1         | 0.02%   |
| 2800    | 1         | 0.02%   |
| 1639    | 1         | 0.02%   |
| 1200    | 1         | 0.02%   |
| 933     | 1         | 0.02%   |
| 333     | 1         | 0.02%   |
| 133     | 1         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Hewlett-Packard               | 15        | 30%     |
| Canon                         | 8         | 16%     |
| Brother Industries            | 7         | 14%     |
| Samsung Electronics           | 6         | 12%     |
| Seiko Epson                   | 5         | 10%     |
| Prolific Technology           | 2         | 4%      |
| STMicroelectronics            | 1         | 2%      |
| Samsung Info. Systems America | 1         | 2%      |
| Ricoh                         | 1         | 2%      |
| Pantum                        | 1         | 2%      |
| NXP Semiconductors            | 1         | 2%      |
| MiiiW                         | 1         | 2%      |
| Dymo-CoStar                   | 1         | 2%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 2         | 4%      |
| Prolific PL2305 Parallel Port                                         | 2         | 4%      |
| HP LaserJet P1102                                                     | 2         | 4%      |
| Brother DCP-1600                                                      | 2         | 4%      |
| STMicroelectronics USB Printing Support                               | 1         | 2%      |
| Seiko Epson WF-2830 Series                                            | 1         | 2%      |
| Seiko Epson L3150 Series                                              | 1         | 2%      |
| Seiko Epson L200 Series                                               | 1         | 2%      |
| Samsung Info. Systems America SAMSUNG SRP-270                         | 1         | 2%      |
| Samsung SCX-4200 series                                               | 1         | 2%      |
| Samsung SCX-3200 Series                                               | 1         | 2%      |
| Samsung ML-331x Series Laser Printer                                  | 1         | 2%      |
| Samsung M2070 Series                                                  | 1         | 2%      |
| Samsung CLX-6260 Series                                               | 1         | 2%      |
| Samsung C43x Series                                                   | 1         | 2%      |
| Ricoh SP 211SU                                                        | 1         | 2%      |
| Pantum P2500W series                                                  | 1         | 2%      |
| NXP Semiconductors Printer-80                                         | 1         | 2%      |
| MiiiW MW USB Receiver                                                 | 1         | 2%      |
| HP Smart Tank 510 series                                              | 1         | 2%      |
| HP Photosmart B010 series                                             | 1         | 2%      |
| HP Officejet 2620 series                                              | 1         | 2%      |
| HP LaserJet 400 colorMFP M475dw                                       | 1         | 2%      |
| HP LaserJet 1010                                                      | 1         | 2%      |
| HP Ink Tank 310 series                                                | 1         | 2%      |
| HP ENVY Pro 6400 series                                               | 1         | 2%      |
| HP ENVY 4500 series                                                   | 1         | 2%      |
| HP Deskjet 3510 series                                                | 1         | 2%      |
| HP Deskjet 3050A                                                      | 1         | 2%      |
| HP DeskJet 2620 All-in-One Printer                                    | 1         | 2%      |
| HP DeskJet 2300 series                                                | 1         | 2%      |
| HP DeskJet 2130 series                                                | 1         | 2%      |
| Dymo-CoStar LabelWriter 450                                           | 1         | 2%      |
| Canon TR8500 series                                                   | 1         | 2%      |
| Canon TR150 series                                                    | 1         | 2%      |
| Canon PIXMA MG3600 Series                                             | 1         | 2%      |
| Canon PIXMA MG3500 Series                                             | 1         | 2%      |
| Canon PIXMA MG3000 series                                             | 1         | 2%      |
| Canon MF3110                                                          | 1         | 2%      |
| Canon MF220 Series                                                    | 1         | 2%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 60%     |
| Seiko Epson     | 3         | 30%     |
| Hewlett-Packard | 1         | 10%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20          | 2         | 20%     |
| Canon CanoScan LiDE 220                     | 2         | 20%     |
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 10%     |
| Seiko Epson GT-X770 [Perfection V500]       | 1         | 10%     |
| Seiko Epson ES-D400 [GT-S80]                | 1         | 10%     |
| HP Scanjet 300                              | 1         | 10%     |
| Canon CanoScan N650U/N656U                  | 1         | 10%     |
| Canon CanoScan LiDE 210                     | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1755      | 23.21%  |
| IMC Networks                           | 943       | 12.47%  |
| Microdia                               | 666       | 8.81%   |
| Bison Electronics                      | 620       | 8.2%    |
| Realtek Semiconductor                  | 612       | 8.09%   |
| Quanta                                 | 479       | 6.33%   |
| Sunplus Innovation Technology          | 398       | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 297       | 3.93%   |
| Syntek                                 | 216       | 2.86%   |
| Lite-On Technology                     | 201       | 2.66%   |
| Apple                                  | 179       | 2.37%   |
| Logitech                               | 169       | 2.23%   |
| Luxvisions Innotech Limited            | 165       | 2.18%   |
| Suyin                                  | 116       | 1.53%   |
| Acer                                   | 106       | 1.4%    |
| Silicon Motion                         | 91        | 1.2%    |
| Sonix Technology                       | 85        | 1.12%   |
| Alcor Micro                            | 54        | 0.71%   |
| Samsung Electronics                    | 47        | 0.62%   |
| Ricoh                                  | 40        | 0.53%   |
| SunplusIT                              | 25        | 0.33%   |
| Lenovo                                 | 25        | 0.33%   |
| Primax Electronics                     | 23        | 0.3%    |
| Microsoft                              | 19        | 0.25%   |
| Importek                               | 18        | 0.24%   |
| Z-Star Microelectronics                | 12        | 0.16%   |
| ShineTech                              | 12        | 0.16%   |
| icSpring                               | 10        | 0.13%   |
| Shenzhen Kingcome Optoelectronic       | 9         | 0.12%   |
| Generalplus Technology                 | 9         | 0.12%   |
| ALi                                    | 9         | 0.12%   |
| ARC International                      | 8         | 0.11%   |
| MacroSilicon                           | 7         | 0.09%   |
| Intel                                  | 7         | 0.09%   |
| Creative Technology                    | 7         | 0.09%   |
| KYE Systems (Mouse Systems)            | 6         | 0.08%   |
| WaveRider Communications               | 5         | 0.07%   |
| Tobii Technology AB                    | 5         | 0.07%   |
| Razer USA                              | 5         | 0.07%   |
| Pixart Imaging                         | 5         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 612       | 8.03%   |
| Microdia Integrated_Webcam_HD                       | 383       | 5.03%   |
| IMC Networks Integrated Camera                      | 364       | 4.78%   |
| Realtek Integrated_Webcam_HD                        | 271       | 3.56%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 254       | 3.33%   |
| Bison Integrated Camera                             | 225       | 2.95%   |
| Sunplus Integrated_Webcam_HD                        | 165       | 2.17%   |
| Chicony HD WebCam                                   | 158       | 2.07%   |
| Syntek Integrated Camera                            | 150       | 1.97%   |
| Quanta HD User Facing                               | 98        | 1.29%   |
| Lite-On Integrated Camera                           | 97        | 1.27%   |
| Chicony Integrated Camera (1280x720@30)             | 97        | 1.27%   |
| Chicony HP HD Camera                                | 76        | 1%      |
| IMC Networks USB2.0 VGA UVC WebCam                  | 74        | 0.97%   |
| Bison SunplusIT Integrated Camera                   | 72        | 0.94%   |
| Quanta HP TrueVision HD Camera                      | 60        | 0.79%   |
| Bison HD Webcam                                     | 58        | 0.76%   |
| IMC Networks HD Camera                              | 54        | 0.71%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                  | 54        | 0.71%   |
| Quanta HP HD Camera                                 | 53        | 0.7%    |
| Lite-On HP HD Camera                                | 52        | 0.68%   |
| Chicony HP TrueVision HD Camera                     | 52        | 0.68%   |
| Bison Lenovo EasyCamera                             | 52        | 0.68%   |
| Apple FaceTime HD Camera                            | 51        | 0.67%   |
| Realtek USB Camera                                  | 50        | 0.66%   |
| Sonix USB2.0 HD UVC WebCam                          | 48        | 0.63%   |
| Quanta HD Webcam                                    | 48        | 0.63%   |
| Microdia Integrated Webcam                          | 48        | 0.63%   |
| Samsung Galaxy series, misc. (MTP mode)             | 47        | 0.62%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 47        | 0.62%   |
| Quanta HP Wide Vision HD Camera                     | 44        | 0.58%   |
| Chicony HD User Facing                              | 44        | 0.58%   |
| Realtek Integrated Webcam                           | 42        | 0.55%   |
| Chicony HP Wide Vision HD Camera                    | 41        | 0.54%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 41        | 0.54%   |
| IMC Networks ov9734_azurewave_camera                | 40        | 0.52%   |
| Logitech HD Pro Webcam C920                         | 39        | 0.51%   |
| Sunplus HD WebCam                                   | 38        | 0.5%    |
| Apple Built-in iSight                               | 38        | 0.5%    |
| Chicony HP Truevision HD                            | 37        | 0.49%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 663       | 35.04%  |
| Validity Sensors                   | 553       | 29.23%  |
| Shenzhen Goodix Technology         | 346       | 18.29%  |
| Elan Microelectronics              | 117       | 6.18%   |
| Upek                               | 66        | 3.49%   |
| LighTuning Technology              | 59        | 3.12%   |
| AuthenTec                          | 43        | 2.27%   |
| Realtek USB2.0 Finger Print Bridge | 22        | 1.16%   |
| Samsung Electronics                | 11        | 0.58%   |
| STMicroelectronics                 | 5         | 0.26%   |
| Focal-systems.Corp                 | 5         | 0.26%   |
| HOLTEK                             | 1         | 0.05%   |
| Dell                               | 1         | 0.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 303       | 16.01%  |
| Shenzhen Goodix  Fingerprint Device                                        | 223       | 11.78%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 127       | 6.71%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 117       | 6.18%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 104       | 5.49%   |
| Shenzhen Goodix FingerPrint                                                | 66        | 3.49%   |
| Validity Sensors Synaptics WBDI                                            | 65        | 3.43%   |
| Elan ELAN:Fingerprint                                                      | 64        | 3.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 62        | 3.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 57        | 3.01%   |
| Elan ELAN:ARM-M4                                                           | 51        | 2.69%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 50        | 2.64%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 47        | 2.48%   |
| Synaptics Fingerprint reader [HP G6]                                       | 42        | 2.22%   |
| Validity Sensors VFS491                                                    | 31        | 1.64%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 31        | 1.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 30        | 1.58%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 29        | 1.53%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 29        | 1.53%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 28        | 1.48%   |
| Synaptics UWP WBDI Device                                                  | 25        | 1.32%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 25        | 1.32%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 23        | 1.22%   |
| Synaptics  WBDI                                                            | 22        | 1.16%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 22        | 1.16%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 18        | 0.95%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 0.95%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 16        | 0.85%   |
| Synaptics WBDI                                                             | 15        | 0.79%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 0.74%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 0.63%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 9         | 0.48%   |
| AuthenTec AES2810                                                          | 9         | 0.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 0.48%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.42%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.37%   |
| Synaptics UWP WBDI                                                         | 7         | 0.37%   |
| Synaptics TouchPad                                                         | 7         | 0.37%   |
| Unknown                                                                    | 7         | 0.37%   |
| Synaptics WBDI Device                                                      | 6         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 303       | 42.08%  |
| Alcor Micro                | 290       | 40.28%  |
| Upek                       | 41        | 5.69%   |
| Lenovo                     | 35        | 4.86%   |
| O2 Micro                   | 15        | 2.08%   |
| Gemalto (was Gemplus)      | 8         | 1.11%   |
| Yubico.com                 | 4         | 0.56%   |
| OmniKey                    | 4         | 0.56%   |
| Aladdin Knowledge Systems  | 4         | 0.56%   |
| SCM Microsystems           | 3         | 0.42%   |
| Realtek Semiconductor      | 3         | 0.42%   |
| Reiner SCT Kartensysteme   | 2         | 0.28%   |
| Advanced Card Systems      | 2         | 0.28%   |
| Purism, SPC                | 1         | 0.14%   |
| Hewlett-Packard            | 1         | 0.14%   |
| Chicony Electronics        | 1         | 0.14%   |
| Bit4id                     | 1         | 0.14%   |
| Athena Smartcard Solutions | 1         | 0.14%   |
| Aktiv                      | 1         | 0.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 289       | 40.14%  |
| Broadcom 5880                                                                | 98        | 13.61%  |
| Broadcom 58200                                                               | 87        | 12.08%  |
| Broadcom BCM5880 Secure Applications Processor                               | 67        | 9.31%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 49        | 6.81%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 41        | 5.69%   |
| Lenovo Integrated Smart Card Reader                                          | 34        | 4.72%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 12        | 1.67%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 6         | 0.83%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 4         | 0.56%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 0.56%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.42%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.42%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.28%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 0.28%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.28%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.28%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.14%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.14%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.14%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.14%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.14%   |
| Purism, SPC Librem Key                                                       | 1         | 0.14%   |
| OmniKey CardMan 4321                                                         | 1         | 0.14%   |
| OmniKey CardMan 1021                                                         | 1         | 0.14%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.14%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.14%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.14%   |
| Bit4id miniLector EVO                                                        | 1         | 0.14%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.14%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.14%   |
| Aktiv Rutoken lite                                                           | 1         | 0.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 4833      | 57.8%   |
| 1     | 2893      | 34.6%   |
| 2     | 543       | 6.49%   |
| 3     | 66        | 0.79%   |
| 4     | 9         | 0.11%   |
| 5     | 7         | 0.08%   |
| 6     | 5         | 0.06%   |
| 7     | 4         | 0.05%   |
| 8     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1872      | 45.12%  |
| Graphics card            | 857       | 20.66%  |
| Multimedia controller    | 442       | 10.65%  |
| Net/wireless             | 303       | 7.3%    |
| Chipcard                 | 222       | 5.35%   |
| Camera                   | 150       | 3.62%   |
| Bluetooth                | 80        | 1.93%   |
| Storage                  | 57        | 1.37%   |
| Card reader              | 54        | 1.3%    |
| Sound                    | 37        | 0.89%   |
| Net/ethernet             | 23        | 0.55%   |
| Communication controller | 19        | 0.46%   |
| Network                  | 18        | 0.43%   |
| Modem                    | 10        | 0.24%   |
| Flash memory             | 2         | 0.05%   |
| Video                    | 1         | 0.02%   |
| Firewire controller      | 1         | 0.02%   |
| Dvb card                 | 1         | 0.02%   |

