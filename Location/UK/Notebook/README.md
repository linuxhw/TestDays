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

Total: 5949

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | XPS 15 9500                 | [a8f95ea32d](https://linux-hardware.org/?probe=a8f95ea32d) | Oct 01, 2023 |
| Acer          | Predator G9-793             | [fd305490af](https://linux-hardware.org/?probe=fd305490af) | Oct 01, 2023 |
| Valve         | Jupiter                     | [d64d0a1997](https://linux-hardware.org/?probe=d64d0a1997) | Sep 30, 2023 |
| Entroware     | Hybris                      | [5b124e9b7f](https://linux-hardware.org/?probe=5b124e9b7f) | Sep 30, 2023 |
| HP            | Pavilion dv5                | [0b1da8643f](https://linux-hardware.org/?probe=0b1da8643f) | Sep 30, 2023 |
| Acer          | Aspire 7741                 | [80d27e2808](https://linux-hardware.org/?probe=80d27e2808) | Sep 30, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [2afa933d2a](https://linux-hardware.org/?probe=2afa933d2a) | Sep 30, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [a7a8e627cb](https://linux-hardware.org/?probe=a7a8e627cb) | Sep 30, 2023 |
| OEGStone      | C4100/C5100                 | [0c27e50b14](https://linux-hardware.org/?probe=0c27e50b14) | Sep 29, 2023 |
| Lenovo        | ThinkPad X260 20F5S2WY00    | [6a18fb9b21](https://linux-hardware.org/?probe=6a18fb9b21) | Sep 29, 2023 |
| Alienware     | m16 R1 AMD                  | [710a10efce](https://linux-hardware.org/?probe=710a10efce) | Sep 29, 2023 |
| Alienware     | x15 R1                      | [a34b343fce](https://linux-hardware.org/?probe=a34b343fce) | Sep 29, 2023 |
| Dell          | XPS 13 9360                 | [2a3e49f18f](https://linux-hardware.org/?probe=2a3e49f18f) | Sep 29, 2023 |
| Google        | Swanky                      | [599959ccbe](https://linux-hardware.org/?probe=599959ccbe) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | [cb2cbda84d](https://linux-hardware.org/?probe=cb2cbda84d) | Sep 28, 2023 |
| Dell          | Precision 3560              | [14af02a240](https://linux-hardware.org/?probe=14af02a240) | Sep 28, 2023 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [dcf11408af](https://linux-hardware.org/?probe=dcf11408af) | Sep 28, 2023 |
| Valve         | Jupiter                     | [39bc0d89fe](https://linux-hardware.org/?probe=39bc0d89fe) | Sep 28, 2023 |
| Dell          | XPS 15 9560                 | [009a6a1a98](https://linux-hardware.org/?probe=009a6a1a98) | Sep 27, 2023 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | [2b7f074e47](https://linux-hardware.org/?probe=2b7f074e47) | Sep 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S5M000    | [58ddf5337a](https://linux-hardware.org/?probe=58ddf5337a) | Sep 27, 2023 |
| Dell          | Latitude E7440              | [9e117fe599](https://linux-hardware.org/?probe=9e117fe599) | Sep 27, 2023 |
| Dell          | Precision 5570              | [f00d32a04a](https://linux-hardware.org/?probe=f00d32a04a) | Sep 27, 2023 |
| Toshiba       | Satellite A200              | [6bdac98313](https://linux-hardware.org/?probe=6bdac98313) | Sep 27, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [9a3f695f09](https://linux-hardware.org/?probe=9a3f695f09) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [fb82c6e942](https://linux-hardware.org/?probe=fb82c6e942) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [c7ec123b46](https://linux-hardware.org/?probe=c7ec123b46) | Sep 27, 2023 |
| Apple         | MacBookAir7,2               | [d8c3afba9b](https://linux-hardware.org/?probe=d8c3afba9b) | Sep 26, 2023 |
| Valve         | Jupiter                     | [277f5aca9b](https://linux-hardware.org/?probe=277f5aca9b) | Sep 26, 2023 |
| Apple         | MacBookPro11,1              | [7463d4f447](https://linux-hardware.org/?probe=7463d4f447) | Sep 26, 2023 |
| ASUSTek       | X551CA                      | [1fdceb9309](https://linux-hardware.org/?probe=1fdceb9309) | Sep 26, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [47d912c5a9](https://linux-hardware.org/?probe=47d912c5a9) | Sep 26, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | [d2a926c703](https://linux-hardware.org/?probe=d2a926c703) | Sep 26, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [2568280c44](https://linux-hardware.org/?probe=2568280c44) | Sep 25, 2023 |
| Valve         | Jupiter                     | [7a64b4c44f](https://linux-hardware.org/?probe=7a64b4c44f) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 20HMS0EXOO    | [0818b5e737](https://linux-hardware.org/?probe=0818b5e737) | Sep 24, 2023 |
| HP            | ProBook 6545b               | [b0abb62083](https://linux-hardware.org/?probe=b0abb62083) | Sep 24, 2023 |
| Toshiba       | TECRA X40-E                 | [280f949acc](https://linux-hardware.org/?probe=280f949acc) | Sep 24, 2023 |
| Toshiba       | Satellite L50D-B            | [8b5b196475](https://linux-hardware.org/?probe=8b5b196475) | Sep 24, 2023 |
| Toshiba       | Satellite L50D-B            | [65d749c96e](https://linux-hardware.org/?probe=65d749c96e) | Sep 23, 2023 |
| Dell          | Inspiron 1564               | [f4232cfca8](https://linux-hardware.org/?probe=f4232cfca8) | Sep 23, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [083c0510ac](https://linux-hardware.org/?probe=083c0510ac) | Sep 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d3322d740d](https://linux-hardware.org/?probe=d3322d740d) | Sep 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [13a9f1d65a](https://linux-hardware.org/?probe=13a9f1d65a) | Sep 23, 2023 |
| Dell          | Inspiron 1564               | [c84457748d](https://linux-hardware.org/?probe=c84457748d) | Sep 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [d464d79df3](https://linux-hardware.org/?probe=d464d79df3) | Sep 23, 2023 |
| HP            | Pavilion g6                 | [c49107d782](https://linux-hardware.org/?probe=c49107d782) | Sep 22, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | [e63d1ae740](https://linux-hardware.org/?probe=e63d1ae740) | Sep 22, 2023 |
| Dell          | XPS 15 9560                 | [a437fe8bcf](https://linux-hardware.org/?probe=a437fe8bcf) | Sep 21, 2023 |
| Toshiba       | Satellite L855              | [ee1cb0c5cc](https://linux-hardware.org/?probe=ee1cb0c5cc) | Sep 21, 2023 |
| ASUSTek       | X550CL                      | [6c2de2dfb8](https://linux-hardware.org/?probe=6c2de2dfb8) | Sep 21, 2023 |
| PC Special... | Ionico 16                   | [dd18901106](https://linux-hardware.org/?probe=dd18901106) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | [2bb7ed1454](https://linux-hardware.org/?probe=2bb7ed1454) | Sep 21, 2023 |
| ASUSTek       | X501A                       | [5045eb238f](https://linux-hardware.org/?probe=5045eb238f) | Sep 20, 2023 |
| Acer          | Swift SF314-512             | [5c5a2a36e2](https://linux-hardware.org/?probe=5c5a2a36e2) | Sep 20, 2023 |
| HP            | EliteBook 845 14 inch G9... | [35d24c31cf](https://linux-hardware.org/?probe=35d24c31cf) | Sep 20, 2023 |
| Apple         | MacBook4,1                  | [3434dd8b54](https://linux-hardware.org/?probe=3434dd8b54) | Sep 20, 2023 |
| ASUSTek       | K52F                        | [8d4b7a978b](https://linux-hardware.org/?probe=8d4b7a978b) | Sep 19, 2023 |
| Dell          | Precision 5550              | [a1c163a7e2](https://linux-hardware.org/?probe=a1c163a7e2) | Sep 19, 2023 |
| Mini PC       | Cherry Trail CR             | [f16d8d4254](https://linux-hardware.org/?probe=f16d8d4254) | Sep 19, 2023 |
| ASUSTek       | X550CL                      | [2d5c5ab820](https://linux-hardware.org/?probe=2d5c5ab820) | Sep 19, 2023 |
| Valve         | Jupiter                     | [7baec97424](https://linux-hardware.org/?probe=7baec97424) | Sep 19, 2023 |
| HP            | Pavilion dv7                | [2bbc187582](https://linux-hardware.org/?probe=2bbc187582) | Sep 19, 2023 |
| Lenovo        | ThinkPad T430 2349BG6       | [dbd8f7715f](https://linux-hardware.org/?probe=dbd8f7715f) | Sep 19, 2023 |
| Dell          | Precision 3581              | [e1c8eb2810](https://linux-hardware.org/?probe=e1c8eb2810) | Sep 18, 2023 |
| Apple         | MacBookPro5,4               | [f2d4f47a8e](https://linux-hardware.org/?probe=f2d4f47a8e) | Sep 18, 2023 |
| Unknown       | M17PRO                      | [ccf362f14d](https://linux-hardware.org/?probe=ccf362f14d) | Sep 17, 2023 |
| Schenker      | XMG CORE (M19, GTX 1650)    | [612bda7c21](https://linux-hardware.org/?probe=612bda7c21) | Sep 17, 2023 |
| Dell          | XPS 13 9370                 | [7715522f7f](https://linux-hardware.org/?probe=7715522f7f) | Sep 17, 2023 |
| HP            | EliteBook 820 G4            | [a16a2ef714](https://linux-hardware.org/?probe=a16a2ef714) | Sep 16, 2023 |
| MSI           | GS43VR 7RE                  | [d9893a35c8](https://linux-hardware.org/?probe=d9893a35c8) | Sep 16, 2023 |
| Acer          | Aspire 5720                 | [9bfcaaa71a](https://linux-hardware.org/?probe=9bfcaaa71a) | Sep 16, 2023 |
| Acer          | Aspire 5720                 | [bad46323d7](https://linux-hardware.org/?probe=bad46323d7) | Sep 16, 2023 |
| Dell          | XPS 9320                    | [99fce2103f](https://linux-hardware.org/?probe=99fce2103f) | Sep 16, 2023 |
| HP            | Compaq 6820s                | [99a625283d](https://linux-hardware.org/?probe=99a625283d) | Sep 16, 2023 |
| HP            | Compaq 6820s                | [2ae8b9ac9d](https://linux-hardware.org/?probe=2ae8b9ac9d) | Sep 16, 2023 |
| Dell          | Latitude E5570              | [fd5ba4aa5a](https://linux-hardware.org/?probe=fd5ba4aa5a) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | [2073aca95d](https://linux-hardware.org/?probe=2073aca95d) | Sep 15, 2023 |
| HP            | Laptop 15-dw1xxx            | [fa484cf261](https://linux-hardware.org/?probe=fa484cf261) | Sep 15, 2023 |
| Dell          | XPS 15 9560                 | [c1f02dd477](https://linux-hardware.org/?probe=c1f02dd477) | Sep 15, 2023 |
| Dell          | XPS 9320                    | [054584d248](https://linux-hardware.org/?probe=054584d248) | Sep 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [982f29b6cc](https://linux-hardware.org/?probe=982f29b6cc) | Sep 14, 2023 |
| Clevo         | P170EM                      | [ee87854652](https://linux-hardware.org/?probe=ee87854652) | Sep 14, 2023 |
| Dell          | Precision 7530              | [035a4eb568](https://linux-hardware.org/?probe=035a4eb568) | Sep 14, 2023 |
| Dell          | Latitude 7390               | [4d8e0cb72b](https://linux-hardware.org/?probe=4d8e0cb72b) | Sep 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [aea796bbd9](https://linux-hardware.org/?probe=aea796bbd9) | Sep 14, 2023 |
| Acer          | AOA150                      | [bc32c4814d](https://linux-hardware.org/?probe=bc32c4814d) | Sep 13, 2023 |
| Dell          | Latitude 7390               | [2afdbd653c](https://linux-hardware.org/?probe=2afdbd653c) | Sep 13, 2023 |
| HP            | Compaq 6730b (NN204ET#AB... | [255f6ba979](https://linux-hardware.org/?probe=255f6ba979) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3831230caa](https://linux-hardware.org/?probe=3831230caa) | Sep 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | [f24f476710](https://linux-hardware.org/?probe=f24f476710) | Sep 11, 2023 |
| HP            | Pavilion Notebook           | [e4a14b2349](https://linux-hardware.org/?probe=e4a14b2349) | Sep 11, 2023 |
| ASUSTek       | N551JX                      | [8c034b254e](https://linux-hardware.org/?probe=8c034b254e) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [36c9a9e4d4](https://linux-hardware.org/?probe=36c9a9e4d4) | Sep 10, 2023 |
| HP            | 255 G7 Notebook PC          | [c5be1f9523](https://linux-hardware.org/?probe=c5be1f9523) | Sep 10, 2023 |
| Google        | Lillipup                    | [c3a892cdca](https://linux-hardware.org/?probe=c3a892cdca) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [3021f551f4](https://linux-hardware.org/?probe=3021f551f4) | Sep 09, 2023 |
| Valve         | Jupiter                     | [249a085da0](https://linux-hardware.org/?probe=249a085da0) | Sep 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [a03aa3f52d](https://linux-hardware.org/?probe=a03aa3f52d) | Sep 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fd38d07a69](https://linux-hardware.org/?probe=fd38d07a69) | Sep 08, 2023 |
| Apple         | MacBookPro10,1              | [81aab795b5](https://linux-hardware.org/?probe=81aab795b5) | Sep 08, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | [6870581b7c](https://linux-hardware.org/?probe=6870581b7c) | Sep 08, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [2614f063f8](https://linux-hardware.org/?probe=2614f063f8) | Sep 07, 2023 |
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
| Ubuntu 20.04       | 548       | 12.74%  |
| Ubuntu 18.04       | 278       | 6.46%   |
| Ubuntu 22.04       | 245       | 5.7%    |
| Zorin 16           | 111       | 2.58%   |
| Pop!_OS 22.04      | 84        | 1.95%   |
| OpenMandriva 4.3   | 84        | 1.95%   |
| Arch Rolling       | 78        | 1.81%   |
| Debian 11          | 75        | 1.74%   |
| Linux Mint 19.3    | 68        | 1.58%   |
| Ubuntu 19.04       | 62        | 1.44%   |
| Manjaro            | 61        | 1.42%   |
| OpenMandriva 4.2   | 60        | 1.39%   |
| Linux Mint 20.3    | 60        | 1.39%   |
| Linux Mint 21.1    | 57        | 1.32%   |
| Pop!_OS 20.04      | 55        | 1.28%   |
| Linux Mint 20.2    | 54        | 1.26%   |
| Arch               | 54        | 1.26%   |
| Ubuntu 20.10       | 53        | 1.23%   |
| Zorin 15           | 52        | 1.21%   |
| KDE neon 20.04     | 52        | 1.21%   |
| ArcoLinux Rolling  | 52        | 1.21%   |
| Ubuntu 21.10       | 51        | 1.19%   |
| Fedora 38          | 51        | 1.19%   |
| Linux Mint 20.1    | 50        | 1.16%   |
| Ubuntu 19.10       | 49        | 1.14%   |
| Pop!_OS 21.04      | 45        | 1.05%   |
| Ubuntu 21.04       | 44        | 1.02%   |
| OpenMandriva 23.01 | 44        | 1.02%   |
| OpenMandriva 23.03 | 41        | 0.95%   |
| Xubuntu 20.04      | 39        | 0.91%   |
| Linux Mint 20      | 36        | 0.84%   |
| Pop!_OS 20.10      | 34        | 0.79%   |
| Fedora 37          | 34        | 0.79%   |
| Pop!_OS 21.10      | 33        | 0.77%   |
| Fedora 35          | 33        | 0.77%   |
| Fedora 34          | 33        | 0.77%   |
| Fedora 36          | 32        | 0.74%   |
| Ubuntu 18.10       | 31        | 0.72%   |
| Linux Mint 21      | 30        | 0.7%    |
| BlackPanther 18.1  | 29        | 0.67%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1370      | 33.39%  |
| Linux Mint    | 377       | 9.19%   |
| OpenMandriva  | 264       | 6.43%   |
| Fedora        | 262       | 6.39%   |
| Pop!_OS       | 235       | 5.73%   |
| Zorin         | 171       | 4.17%   |
| Manjaro       | 135       | 3.29%   |
| Arch          | 130       | 3.17%   |
| Debian        | 129       | 3.14%   |
| Kubuntu       | 96        | 2.34%   |
| SteamOS       | 95        | 2.32%   |
| Xubuntu       | 90        | 2.19%   |
| KDE neon      | 77        | 1.88%   |
| ArcoLinux     | 56        | 1.36%   |
| Elementary    | 47        | 1.15%   |
| Lubuntu       | 41        | 1%      |
| ROSA          | 37        | 0.9%    |
| Ubuntu MATE   | 36        | 0.88%   |
| openSUSE      | 34        | 0.83%   |
| Gentoo        | 30        | 0.73%   |
| BlackPanther  | 30        | 0.73%   |
| Ubuntu Unity  | 29        | 0.71%   |
| Kali          | 29        | 0.71%   |
| Endless       | 29        | 0.71%   |
| EndeavourOS   | 21        | 0.51%   |
| MX            | 19        | 0.46%   |
| LMDE          | 19        | 0.46%   |
| Garuda Linux  | 19        | 0.46%   |
| Clear Linux   | 19        | 0.46%   |
| Ubuntu Budgie | 16        | 0.39%   |
| Parrot        | 15        | 0.37%   |
| Peppermint    | 12        | 0.29%   |
| CentOS        | 11        | 0.27%   |
| Nobara        | 8         | 0.19%   |
| NixOS         | 8         | 0.19%   |
| RHEL          | 7         | 0.17%   |
| Q4OS          | 5         | 0.12%   |
| PureOS        | 5         | 0.12%   |
| Linux Lite    | 5         | 0.12%   |
| blendOS       | 5         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 79        | 1.67%   |
| 5.4.0-42-generic         | 77        | 1.63%   |
| 5.10.14-desktop-1omv4002 | 57        | 1.2%    |
| 5.15.0-56-generic        | 49        | 1.03%   |
| 5.13.0-valve36-1-neptune | 42        | 0.89%   |
| 6.2.6-desktop-1omv2390   | 41        | 0.87%   |
| 5.4.0-48-generic         | 40        | 0.84%   |
| 5.4.0-52-generic         | 39        | 0.82%   |
| 6.1.1-desktop-1omv2290   | 38        | 0.8%    |
| 5.15.0-52-generic        | 38        | 0.8%    |
| 5.15.0-58-generic        | 37        | 0.78%   |
| 5.4.0-29-generic         | 35        | 0.74%   |
| 5.3.0-40-generic         | 35        | 0.74%   |
| 5.11.0-27-generic        | 34        | 0.72%   |
| 5.4.0-26-generic         | 33        | 0.7%    |
| 5.3.0-28-generic         | 33        | 0.7%    |
| 5.15.0-46-generic        | 33        | 0.7%    |
| 5.4.0-58-generic         | 30        | 0.63%   |
| 5.4.0-40-generic         | 29        | 0.61%   |
| 5.0.0-32-generic         | 29        | 0.61%   |
| 5.11.0-38-generic        | 28        | 0.59%   |
| 5.8.0-43-generic         | 25        | 0.53%   |
| 5.3.0-42-generic         | 25        | 0.53%   |
| 5.19.0-35-generic        | 25        | 0.53%   |
| 5.4.0-91-generic         | 24        | 0.51%   |
| 5.11.0-37-generic        | 24        | 0.51%   |
| 5.11.0-25-generic        | 24        | 0.51%   |
| 5.4.0-65-generic         | 23        | 0.49%   |
| 6.2.0-26-generic         | 22        | 0.46%   |
| 5.4.0-7634-generic       | 22        | 0.46%   |
| 5.4.0-33-generic         | 22        | 0.46%   |
| 5.13.0-7614-generic      | 22        | 0.46%   |
| 5.13.0-28-generic        | 22        | 0.46%   |
| 5.0.0-37-generic         | 22        | 0.46%   |
| 4.18.16-desktop-1bP      | 22        | 0.46%   |
| 5.8.0-50-generic         | 21        | 0.44%   |
| 5.8.0-44-generic         | 21        | 0.44%   |
| 5.4.0-56-generic         | 21        | 0.44%   |
| 5.4.0-54-generic         | 21        | 0.44%   |
| 5.3.0-46-generic         | 21        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 735       | 16.58%  |
| 5.15.0  | 408       | 9.21%   |
| 5.13.0  | 276       | 6.23%   |
| 5.11.0  | 243       | 5.48%   |
| 5.8.0   | 234       | 5.28%   |
| 5.3.0   | 204       | 4.6%    |
| 4.15.0  | 203       | 4.58%   |
| 5.19.0  | 157       | 3.54%   |
| 5.0.0   | 137       | 3.09%   |
| 5.10.0  | 101       | 2.28%   |
| 4.18.0  | 92        | 2.08%   |
| 6.2.0   | 84        | 1.9%    |
| 5.16.7  | 79        | 1.78%   |
| 6.2.6   | 64        | 1.44%   |
| 5.10.14 | 57        | 1.29%   |
| 6.1.1   | 39        | 0.88%   |
| 6.1.0   | 35        | 0.79%   |
| 4.19.0  | 30        | 0.68%   |
| 4.18.16 | 23        | 0.52%   |
| 6.4.11  | 19        | 0.43%   |
| 5.14.0  | 17        | 0.38%   |
| 5.17.5  | 16        | 0.36%   |
| 6.0.6   | 15        | 0.34%   |
| 6.0.0   | 15        | 0.34%   |
| 6.2.9   | 12        | 0.27%   |
| 4.9.60  | 12        | 0.27%   |
| 6.4.6   | 11        | 0.25%   |
| 6.4.12  | 11        | 0.25%   |
| 6.3.5   | 11        | 0.25%   |
| 6.0.12  | 11        | 0.25%   |
| 5.17.1  | 11        | 0.25%   |
| 5.16.0  | 11        | 0.25%   |
| 5.9.16  | 10        | 0.23%   |
| 5.15.12 | 10        | 0.23%   |
| 4.4.0   | 10        | 0.23%   |
| 5.18.10 | 9         | 0.2%    |
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
| 5.4     | 771       | 17.56%  |
| 5.15    | 498       | 11.34%  |
| 5.13    | 316       | 7.2%    |
| 5.8     | 279       | 6.35%   |
| 5.11    | 267       | 6.08%   |
| 5.3     | 228       | 5.19%   |
| 5.10    | 207       | 4.71%   |
| 4.15    | 204       | 4.65%   |
| 5.19    | 198       | 4.51%   |
| 6.2     | 194       | 4.42%   |
| 5.16    | 145       | 3.3%    |
| 5.0     | 144       | 3.28%   |
| 6.1     | 143       | 3.26%   |
| 4.18    | 117       | 2.66%   |
| 6.4     | 83        | 1.89%   |
| 6.0     | 78        | 1.78%   |
| 5.17    | 57        | 1.3%    |
| 6.3     | 54        | 1.23%   |
| 5.14    | 54        | 1.23%   |
| 5.9     | 46        | 1.05%   |
| 4.19    | 46        | 1.05%   |
| 5.12    | 42        | 0.96%   |
| 5.6     | 38        | 0.87%   |
| 4.9     | 33        | 0.75%   |
| 5.18    | 32        | 0.73%   |
| 5.7     | 30        | 0.68%   |
| 5.5     | 19        | 0.43%   |
| 6.5     | 15        | 0.34%   |
| 5.2     | 11        | 0.25%   |
| 4.4     | 11        | 0.25%   |
| 5.1     | 8         | 0.18%   |
| 3.10    | 4         | 0.09%   |
| 4.20    | 3         | 0.07%   |
| 4.16    | 3         | 0.07%   |
| 4.14    | 3         | 0.07%   |
| 4.8     | 2         | 0.05%   |
| 4.12    | 2         | 0.05%   |
| 4.1     | 2         | 0.05%   |
| 4.6     | 1         | 0.02%   |
| 4.17    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 3841      | 97.02%  |
| i686    | 117       | 2.96%   |
| aarch64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1843      | 44.65%  |
| KDE5             | 739       | 17.9%   |
| Unknown          | 421       | 10.2%   |
| X-Cinnamon       | 308       | 7.46%   |
| XFCE             | 296       | 7.17%   |
| MATE             | 111       | 2.69%   |
| KDE              | 85        | 2.06%   |
| Pantheon         | 44        | 1.07%   |
| LXQt             | 43        | 1.04%   |
| Cinnamon         | 41        | 0.99%   |
| Unity            | 31        | 0.75%   |
| LXDE             | 26        | 0.63%   |
| Budgie           | 23        | 0.56%   |
| i3               | 22        | 0.53%   |
| GNOME Flashback  | 17        | 0.41%   |
| KDE4             | 14        | 0.34%   |
| sway             | 9         | 0.22%   |
| Hyprland         | 7         | 0.17%   |
| qtile            | 6         | 0.15%   |
| GNOME Classic    | 6         | 0.15%   |
| awesome          | 6         | 0.15%   |
| bspwm            | 4         | 0.1%    |
| xmonad           | 3         | 0.07%   |
| trinity          | 3         | 0.07%   |
| openbox          | 3         | 0.07%   |
| Deepin           | 3         | 0.07%   |
| i3-with-shmlog   | 2         | 0.05%   |
| DWM              | 2         | 0.05%   |
| chadwm           | 2         | 0.05%   |
| Unicorn:XFCE     | 1         | 0.02%   |
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
| X11     | 3075      | 75.72%  |
| Wayland | 712       | 17.53%  |
| Unknown | 231       | 5.69%   |
| Tty     | 43        | 1.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2146      | 52.14%  |
| SDDM    | 591       | 14.36%  |
| GDM     | 445       | 10.81%  |
| GDM3    | 436       | 10.59%  |
| LightDM | 363       | 8.82%   |
| TDM     | 101       | 2.45%   |
| KDM     | 15        | 0.36%   |
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
| en_GB          | 2916      | 71.86%  |
| en_US          | 529       | 13.04%  |
| Unknown        | 414       | 10.2%   |
| C              | 55        | 1.36%   |
| pl_PL          | 41        | 1.01%   |
| de_DE          | 10        | 0.25%   |
| fr_FR          | 9         | 0.22%   |
| it_IT          | 7         | 0.17%   |
| en_CA          | 7         | 0.17%   |
| en_AU          | 7         | 0.17%   |
| ru_RU          | 6         | 0.15%   |
| POSIX          | 6         | 0.15%   |
| es_ES          | 6         | 0.15%   |
| en_IN          | 5         | 0.12%   |
| en_IE          | 5         | 0.12%   |
| cs_CZ          | 5         | 0.12%   |
| hu_HU          | 4         | 0.1%    |
| zh_CN          | 3         | 0.07%   |
| ro_RO          | 3         | 0.07%   |
| uk_UA          | 2         | 0.05%   |
| sk_SK          | 2         | 0.05%   |
| pt_PT          | 2         | 0.05%   |
| pt_BR          | 2         | 0.05%   |
| tr_TR          | 1         | 0.02%   |
| nl_BE          | 1         | 0.02%   |
| en_IL          | 1         | 0.02%   |
| en_HK          | 1         | 0.02%   |
| en_GG          | 1         | 0.02%   |
| en_GB.utf-8    | 1         | 0.02%   |
| en_GB.iso88591 | 1         | 0.02%   |
| en_AG          | 1         | 0.02%   |
| enGB           | 1         | 0.02%   |
| da_DK          | 1         | 0.02%   |
| C.UTF8         | 1         | 0.02%   |
| bg_BG          | 1         | 0.02%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 2069      | 51.28%  |
| BIOS | 1966      | 48.72%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 3064      | 75.3%   |
| Btrfs   | 431       | 10.59%  |
| Overlay | 278       | 6.83%   |
| Unknown | 112       | 2.75%   |
| Tmpfs   | 84        | 2.06%   |
| Xfs     | 49        | 1.2%    |
| Zfs     | 31        | 0.76%   |
| Ext2    | 9         | 0.22%   |
| F2fs    | 6         | 0.15%   |
| Ext3    | 4         | 0.1%    |
| Aufs    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2253      | 55.53%  |
| GPT     | 1444      | 35.59%  |
| MBR     | 360       | 8.87%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3596      | 89.36%  |
| Yes       | 428       | 10.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3048      | 75.93%  |
| Yes       | 966       | 24.07%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 781       | 19.75%  |
| Dell                | 773       | 19.54%  |
| Hewlett-Packard     | 644       | 16.28%  |
| Acer                | 290       | 7.33%   |
| ASUSTek Computer    | 282       | 7.13%   |
| Toshiba             | 173       | 4.37%   |
| Apple               | 124       | 3.14%   |
| Valve               | 97        | 2.45%   |
| Samsung Electronics | 76        | 1.92%   |
| Sony                | 64        | 1.62%   |
| MSI                 | 63        | 1.59%   |
| Google              | 47        | 1.19%   |
| PC Specialist       | 46        | 1.16%   |
| HUAWEI              | 45        | 1.14%   |
| Notebook            | 32        | 0.81%   |
| Unknown             | 32        | 0.81%   |
| Alienware           | 21        | 0.53%   |
| Razer               | 20        | 0.51%   |
| Star Labs           | 19        | 0.48%   |
| Fujitsu             | 19        | 0.48%   |
| Packard Bell        | 18        | 0.46%   |
| Entroware           | 15        | 0.38%   |
| Fujitsu Siemens     | 14        | 0.35%   |
| Dixonsxp            | 14        | 0.35%   |
| TUXEDO              | 13        | 0.33%   |
| GEO                 | 12        | 0.3%    |
| Clevo               | 12        | 0.3%    |
| LG Electronics      | 11        | 0.28%   |
| Linx                | 9         | 0.23%   |
| Gigabyte Technology | 9         | 0.23%   |
| Advent              | 9         | 0.23%   |
| Timi                | 8         | 0.2%    |
| Jumper              | 8         | 0.2%    |
| eMachines           | 8         | 0.2%    |
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
| Valve Jupiter           | 97        | 2.45%   |
| Unknown                 | 54        | 1.37%   |
| HP Pavilion g6          | 26        | 0.66%   |
| HP Notebook             | 21        | 0.53%   |
| HP Pavilion 15          | 20        | 0.51%   |
| HP Pavilion Notebook    | 17        | 0.43%   |
| Dell XPS 15 9560        | 16        | 0.4%    |
| Dell XPS 15 7590        | 16        | 0.4%    |
| Dell Inspiron 1545      | 15        | 0.38%   |
| Dell XPS 15 9570        | 14        | 0.35%   |
| Dell XPS 13 9380        | 14        | 0.35%   |
| Dell XPS 13 9370        | 14        | 0.35%   |
| Dell XPS 13 9360        | 13        | 0.33%   |
| Dell Latitude E6400     | 13        | 0.33%   |
| Dell Latitude E6410     | 12        | 0.3%    |
| Apple MacBookPro12,1    | 12        | 0.3%    |
| Toshiba Satellite C660  | 11        | 0.28%   |
| Lenovo V145-15AST 81MT  | 11        | 0.28%   |
| Dell XPS 13 7390        | 11        | 0.28%   |
| Dell Latitude E7240     | 11        | 0.28%   |
| HP Pavilion dv6         | 10        | 0.25%   |
| HP Laptop 15-da0xxx     | 10        | 0.25%   |
| Dell XPS 15 9550        | 10        | 0.25%   |
| Dell XPS 15 9510        | 10        | 0.25%   |
| Dell Latitude E7450     | 10        | 0.25%   |
| Dell Latitude E7440     | 10        | 0.25%   |
| Apple MacBookPro9,2     | 10        | 0.25%   |
| Acer Aspire ES1-531     | 10        | 0.25%   |
| Lenovo Z50-75 80EC      | 9         | 0.23%   |
| HP Laptop 15-bw0xx      | 9         | 0.23%   |
| HP 15                   | 9         | 0.23%   |
| Dell XPS 15 9500        | 9         | 0.23%   |
| Dell XPS 13 9310        | 9         | 0.23%   |
| Dell XPS 13 9305        | 9         | 0.23%   |
| Dell Latitude E6420     | 9         | 0.23%   |
| Apple MacBookPro5,5     | 9         | 0.23%   |
| Dell Inspiron 5570      | 8         | 0.2%    |
| Toshiba Satellite C50-B | 7         | 0.18%   |
| Star Labs LabTop        | 7         | 0.18%   |
| Razer Blade             | 7         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 447       | 11.3%   |
| Dell Latitude         | 267       | 6.75%   |
| Acer Aspire           | 207       | 5.23%   |
| Dell Inspiron         | 197       | 4.98%   |
| Dell XPS              | 183       | 4.63%   |
| Toshiba Satellite     | 150       | 3.79%   |
| Lenovo IdeaPad        | 145       | 3.67%   |
| HP Pavilion           | 141       | 3.57%   |
| HP EliteBook          | 108       | 2.73%   |
| Valve Jupiter         | 97        | 2.45%   |
| HP Laptop             | 72        | 1.82%   |
| HP ProBook            | 66        | 1.67%   |
| ASUS VivoBook         | 65        | 1.64%   |
| Unknown               | 54        | 1.37%   |
| Dell Precision        | 48        | 1.21%   |
| HP ENVY               | 34        | 0.86%   |
| HP Compaq             | 32        | 0.81%   |
| Lenovo Legion         | 29        | 0.73%   |
| Acer Swift            | 29        | 0.73%   |
| HP Stream             | 28        | 0.71%   |
| ASUS Zenbook          | 26        | 0.66%   |
| Dell Vostro           | 25        | 0.63%   |
| ASUS ROG              | 24        | 0.61%   |
| Lenovo Yoga           | 21        | 0.53%   |
| HP Notebook           | 21        | 0.53%   |
| Razer Blade           | 20        | 0.51%   |
| Lenovo ThinkBook      | 20        | 0.51%   |
| HP ZBook              | 19        | 0.48%   |
| HP 255                | 19        | 0.48%   |
| Packard Bell EasyNote | 17        | 0.43%   |
| HP Presario           | 17        | 0.43%   |
| Fujitsu LIFEBOOK      | 16        | 0.4%    |
| ASUS ASUS             | 16        | 0.4%    |
| Acer Nitro            | 16        | 0.4%    |
| HP OMEN               | 14        | 0.35%   |
| Dell System           | 13        | 0.33%   |
| Apple MacBookPro9     | 13        | 0.33%   |
| Apple MacBookPro5     | 13        | 0.33%   |
| Apple MacBookPro12    | 12        | 0.3%    |
| Lenovo V145-15AST     | 11        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 354       | 8.95%   |
| 2019    | 334       | 8.45%   |
| 2020    | 311       | 7.86%   |
| 2012    | 298       | 7.53%   |
| 2021    | 275       | 6.95%   |
| 2013    | 275       | 6.95%   |
| 2011    | 255       | 6.45%   |
| 2017    | 252       | 6.37%   |
| 2015    | 240       | 6.07%   |
| 2016    | 227       | 5.74%   |
| 2014    | 226       | 5.71%   |
| 2022    | 217       | 5.49%   |
| 2010    | 189       | 4.78%   |
| 2008    | 168       | 4.25%   |
| 2009    | 146       | 3.69%   |
| 2007    | 96        | 2.43%   |
| 2006    | 39        | 0.99%   |
| 2023    | 37        | 0.94%   |
| 2005    | 8         | 0.2%    |
| Unknown | 6         | 0.15%   |
| 2003    | 1         | 0.03%   |
| 2002    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3955      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 3551      | 88.93%  |
| Enabled  | 442       | 11.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3887      | 98.26%  |
| Yes  | 69        | 1.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1145      | 28.54%  |
| 3.01-4.0    | 782       | 19.49%  |
| 16.01-24.0  | 735       | 18.32%  |
| 8.01-16.0   | 664       | 16.55%  |
| 32.01-64.0  | 256       | 6.38%   |
| 1.01-2.0    | 224       | 5.58%   |
| 2.01-3.0    | 92        | 2.29%   |
| 64.01-256.0 | 43        | 1.07%   |
| 24.01-32.0  | 39        | 0.97%   |
| 0.51-1.0    | 31        | 0.77%   |
| 0.01-0.5    | 1         | 0.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1633      | 37.36%  |
| 2.01-3.0   | 1092      | 24.98%  |
| 4.01-8.0   | 607       | 13.89%  |
| 3.01-4.0   | 555       | 12.7%   |
| 0.51-1.0   | 279       | 6.38%   |
| 8.01-16.0  | 141       | 3.23%   |
| 0.01-0.5   | 37        | 0.85%   |
| 16.01-24.0 | 17        | 0.39%   |
| 24.01-32.0 | 7         | 0.16%   |
| 32.01-64.0 | 2         | 0.05%   |
| Unknown    | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2928      | 72.44%  |
| 2      | 943       | 23.33%  |
| 3      | 104       | 2.57%   |
| 0      | 36        | 0.89%   |
| 4      | 21        | 0.52%   |
| 5      | 4         | 0.1%    |
| 7      | 3         | 0.07%   |
| 9      | 1         | 0.02%   |
| 8      | 1         | 0.02%   |
| 6      | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2575      | 64.8%   |
| Yes       | 1399      | 35.2%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3027      | 76.29%  |
| No        | 941       | 23.71%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3898      | 98.51%  |
| No        | 59        | 1.49%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3091      | 77.39%  |
| No        | 903       | 22.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| UK      | 3955      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| London              | 269       | 6.16%   |
| Manchester          | 87        | 1.99%   |
| Birmingham          | 79        | 1.81%   |
| Glasgow             | 72        | 1.65%   |
| Edinburgh           | 68        | 1.56%   |
| Bristol             | 55        | 1.26%   |
| Leeds               | 53        | 1.21%   |
| Liverpool           | 48        | 1.1%    |
| Sheffield           | 46        | 1.05%   |
| Nottingham          | 46        | 1.05%   |
| Islington           | 43        | 0.99%   |
| Reading             | 40        | 0.92%   |
| Cambridge           | 38        | 0.87%   |
| Norwich             | 33        | 0.76%   |
| Coventry            | 33        | 0.76%   |
| Leicester           | 32        | 0.73%   |
| Oxford              | 30        | 0.69%   |
| Southampton         | 28        | 0.64%   |
| Aberdeen            | 28        | 0.64%   |
| Croydon             | 27        | 0.62%   |
| Milton Keynes       | 26        | 0.6%    |
| Cardiff             | 25        | 0.57%   |
| Bradford            | 24        | 0.55%   |
| York                | 22        | 0.5%    |
| Plymouth            | 22        | 0.5%    |
| Gloucester          | 22        | 0.5%    |
| Brighton            | 22        | 0.5%    |
| Bolton              | 22        | 0.5%    |
| Swindon             | 21        | 0.48%   |
| Chesterfield        | 21        | 0.48%   |
| Wolverhampton       | 20        | 0.46%   |
| Newcastle upon Tyne | 20        | 0.46%   |
| Kensington          | 20        | 0.46%   |
| Hackney             | 20        | 0.46%   |
| Wigan               | 19        | 0.44%   |
| Harrow              | 19        | 0.44%   |
| Colchester          | 19        | 0.44%   |
| Belfast             | 19        | 0.44%   |
| Walsall             | 18        | 0.41%   |
| Derby               | 18        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 769       | 1021   | 15.82%  |
| Seagate                     | 466       | 635    | 9.58%   |
| WDC                         | 462       | 592    | 9.5%    |
| Unknown                     | 434       | 563    | 8.93%   |
| Toshiba                     | 422       | 519    | 8.68%   |
| Sandisk                     | 303       | 374    | 6.23%   |
| Crucial                     | 209       | 285    | 4.3%    |
| SK hynix                    | 203       | 238    | 4.18%   |
| Kingston                    | 188       | 232    | 3.87%   |
| Hitachi                     | 177       | 209    | 3.64%   |
| Intel                       | 144       | 171    | 2.96%   |
| HGST                        | 122       | 178    | 2.51%   |
| Micron Technology           | 102       | 122    | 2.1%    |
| Apple                       | 60        | 78     | 1.23%   |
| KIOXIA                      | 53        | 64     | 1.09%   |
| Phison                      | 44        | 52     | 0.9%    |
| Phison Electronics          | 40        | 46     | 0.82%   |
| China                       | 40        | 58     | 0.82%   |
| A-DATA Technology           | 38        | 45     | 0.78%   |
| LITEON                      | 36        | 46     | 0.74%   |
| PNY                         | 31        | 37     | 0.64%   |
| Fujitsu                     | 31        | 39     | 0.64%   |
| Unknown                     | 28        | 32     | 0.58%   |
| Transcend                   | 27        | 34     | 0.56%   |
| Micron/Crucial Technology   | 24        | 25     | 0.49%   |
| LITEONIT                    | 24        | 31     | 0.49%   |
| Silicon Motion              | 23        | 27     | 0.47%   |
| Kingston Technology Company | 21        | 23     | 0.43%   |
| O2 Micro                    | 16        | 17     | 0.33%   |
| Integral                    | 14        | 16     | 0.29%   |
| SPCC                        | 12        | 18     | 0.25%   |
| OCZ                         | 12        | 13     | 0.25%   |
| Lenovo                      | 12        | 13     | 0.25%   |
| JMicron Technology          | 9         | 14     | 0.19%   |
| Corsair                     | 9         | 13     | 0.19%   |
| Team                        | 8         | 9      | 0.16%   |
| SABRENT                     | 8         | 8      | 0.16%   |
| Realtek                     | 8         | 8      | 0.16%   |
| TCSUNBOW                    | 7         | 11     | 0.14%   |
| Patriot                     | 7         | 13     | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 96        | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB                      | 63        | 1.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 53        | 1.04%   |
| Toshiba MQ01ABD100 1TB                              | 51        | 1%      |
| Unknown MMC Card  64GB                              | 48        | 0.94%   |
| Unknown MMC Card  128GB                             | 39        | 0.77%   |
| Samsung NVMe SSD Drive 512GB                        | 37        | 0.73%   |
| Unknown MMC Card  512GB                             | 34        | 0.67%   |
| Toshiba MQ01ABF050 500GB                            | 33        | 0.65%   |
| Unknown MMC Card  16GB                              | 31        | 0.61%   |
| Phison PS5013 E13 NVMe Controller 512GB             | 31        | 0.61%   |
| HGST HTS721010A9E630 1TB                            | 31        | 0.61%   |
| HGST HTS541010A9E680 1TB                            | 30        | 0.59%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB              | 29        | 0.57%   |
| Samsung SSD 850 EVO 500GB                           | 28        | 0.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 28        | 0.55%   |
| Unknown                                             | 28        | 0.55%   |
| Crucial CT500MX500SSD1 500GB                        | 27        | 0.53%   |
| Kingston SA400S37240G 240GB SSD                     | 26        | 0.51%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD                 | 25        | 0.49%   |
| Samsung SSD 860 EVO 500GB                           | 25        | 0.49%   |
| Samsung SSD 850 EVO 250GB                           | 24        | 0.47%   |
| Kingston SA400S37120G 120GB SSD                     | 24        | 0.47%   |
| Crucial CT1000MX500SSD1 1TB                         | 24        | 0.47%   |
| SanDisk NVMe SSD Drive 512GB                        | 22        | 0.43%   |
| Unknown SD/MMC/MS PRO 128GB                         | 21        | 0.41%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                  | 21        | 0.41%   |
| Samsung SSD 970 EVO Plus 1TB                        | 21        | 0.41%   |
| Toshiba MQ04ABF100 1TB                              | 20        | 0.39%   |
| Seagate ST500LT012-1DG142 500GB                     | 20        | 0.39%   |
| Samsung NVMe SSD Drive 1024GB                       | 20        | 0.39%   |
| Kingston SA400S37480G 480GB SSD                     | 20        | 0.39%   |
| Crucial CT240BX500SSD1 240GB                        | 20        | 0.39%   |
| Seagate ST9500325AS 500GB                           | 19        | 0.37%   |
| SK hynix NVMe SSD Drive 512GB                       | 18        | 0.35%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 18        | 0.35%   |
| Crucial CT250MX500SSD1 250GB                        | 18        | 0.35%   |
| Unknown MMC Card  256GB                             | 17        | 0.33%   |
| Toshiba NVMe SSD Drive 512GB                        | 17        | 0.33%   |
| SanDisk NVMe SSD Drive 256GB                        | 17        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 452       | 614    | 31.65%  |
| WDC                 | 276       | 353    | 19.33%  |
| Toshiba             | 272       | 325    | 19.05%  |
| Hitachi             | 177       | 209    | 12.39%  |
| HGST                | 122       | 178    | 8.54%   |
| Samsung Electronics | 45        | 50     | 3.15%   |
| Fujitsu             | 31        | 39     | 2.17%   |
| Unknown             | 21        | 24     | 1.47%   |
| SABRENT             | 7         | 7      | 0.49%   |
| Apple               | 7         | 7      | 0.49%   |
| SSK                 | 3         | 4      | 0.21%   |
| Initio              | 2         | 2      | 0.14%   |
| IBM/Hitachi         | 2         | 2      | 0.14%   |
| ASMT                | 2         | 25     | 0.14%   |
| USB3.0              | 1         | 1      | 0.07%   |
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
| Samsung Electronics | 335       | 454    | 21.68%  |
| Crucial             | 193       | 266    | 12.49%  |
| SanDisk             | 172       | 209    | 11.13%  |
| Kingston            | 148       | 179    | 9.58%   |
| WDC                 | 85        | 120    | 5.5%    |
| Intel               | 53        | 57     | 3.43%   |
| Micron Technology   | 46        | 54     | 2.98%   |
| SK hynix            | 42        | 53     | 2.72%   |
| Toshiba             | 38        | 51     | 2.46%   |
| China               | 38        | 53     | 2.46%   |
| Apple               | 35        | 45     | 2.27%   |
| LITEON              | 34        | 44     | 2.2%    |
| PNY                 | 30        | 35     | 1.94%   |
| A-DATA Technology   | 29        | 34     | 1.88%   |
| Transcend           | 27        | 34     | 1.75%   |
| LITEONIT            | 24        | 31     | 1.55%   |
| Integral            | 14        | 16     | 0.91%   |
| OCZ                 | 12        | 13     | 0.78%   |
| SPCC                | 11        | 16     | 0.71%   |
| Seagate             | 9         | 9      | 0.58%   |
| Unknown             | 7         | 7      | 0.45%   |
| Team                | 7         | 8      | 0.45%   |
| Patriot             | 7         | 13     | 0.45%   |
| Netac               | 7         | 10     | 0.45%   |
| TCSUNBOW            | 6         | 10     | 0.39%   |
| Star                | 6         | 7      | 0.39%   |
| Drevo               | 6         | 9      | 0.39%   |
| Corsair             | 6         | 10     | 0.39%   |
| BHT                 | 6         | 9      | 0.39%   |
| Gigabyte Technology | 5         | 5      | 0.32%   |
| ORTIAL              | 4         | 4      | 0.26%   |
| Lexar               | 4         | 5      | 0.26%   |
| KIOXIA-EXCERIA      | 4         | 4      | 0.26%   |
| BIWIN               | 4         | 4      | 0.26%   |
| ZTC                 | 3         | 6      | 0.19%   |
| Zheino              | 3         | 5      | 0.19%   |
| Vaseky              | 3         | 4      | 0.19%   |
| TO Exter            | 3         | 3      | 0.19%   |
| ShiJi               | 3         | 3      | 0.19%   |
| Plextor             | 3         | 4      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1404      | 1996   | 30.49%  |
| HDD     | 1381      | 1851   | 29.99%  |
| NVMe    | 1337      | 1746   | 29.03%  |
| MMC     | 434       | 561    | 9.42%   |
| Unknown | 49        | 61     | 1.06%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2556      | 3697   | 57.14%  |
| NVMe | 1334      | 1737   | 29.82%  |
| MMC  | 434       | 561    | 9.7%    |
| SAS  | 149       | 220    | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1925      | 2635   | 68.75%  |
| 0.51-1.0   | 754       | 1021   | 26.93%  |
| 1.01-2.0   | 92        | 127    | 3.29%   |
| 3.01-4.0   | 13        | 39     | 0.46%   |
| 4.01-10.0  | 13        | 22     | 0.46%   |
| 2.01-3.0   | 2         | 2      | 0.07%   |
| 10.01-20.0 | 1         | 1      | 0.04%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1235      | 29.57%  |
| 251-500        | 977       | 23.4%   |
| 501-1000       | 623       | 14.92%  |
| 1-20           | 326       | 7.81%   |
| 51-100         | 298       | 7.14%   |
| 21-50          | 247       | 5.91%   |
| 1001-2000      | 226       | 5.41%   |
| Unknown        | 111       | 2.66%   |
| More than 3000 | 79        | 1.89%   |
| 2001-3000      | 54        | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1840      | 42.54%  |
| 21-50          | 813       | 18.8%   |
| 101-250        | 542       | 12.53%  |
| 51-100         | 489       | 11.31%  |
| 251-500        | 294       | 6.8%    |
| 501-1000       | 144       | 3.33%   |
| Unknown        | 111       | 2.57%   |
| 1001-2000      | 59        | 1.36%   |
| More than 3000 | 17        | 0.39%   |
| 2001-3000      | 15        | 0.35%   |
| 0              | 1         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                 | 6         | 6      | 3.06%   |
| HGST HTS725050A7E630 500GB                     | 6         | 9      | 3.06%   |
| Seagate ST9500325AS 500GB                      | 5         | 9      | 2.55%   |
| Hitachi HTS547575A9E384 752GB                  | 5         | 7      | 2.55%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 4         | 5      | 2.04%   |
| Toshiba MK1656GSY 160GB                        | 3         | 3      | 1.53%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 3      | 1.53%   |
| Intel SSDSC2BF180A5L 180GB                     | 3         | 3      | 1.53%   |
| Hitachi HTS543216L9A300 160GB                  | 3         | 3      | 1.53%   |
| Hitachi HTS542512K9SA00 120GB                  | 3         | 3      | 1.53%   |
| HGST HTS541010A9E680 1TB                       | 3         | 3      | 1.53%   |
| WDC WD2500BEVT-80A23T0 250GB                   | 2         | 5      | 1.02%   |
| Toshiba MK5065GSXN 500GB                       | 2         | 2      | 1.02%   |
| Toshiba MK3256GSY 320GB                        | 2         | 3      | 1.02%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 1.02%   |
| Seagate ST1000LM014-SSHD-8GB                   | 2         | 3      | 1.02%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 2         | 2      | 1.02%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 2         | 2      | 1.02%   |
| LITEON CS1-SP32-11 M.2 2242 32GB SSD           | 2         | 2      | 1.02%   |
| Hitachi HTS547564A9E384 640GB                  | 2         | 2      | 1.02%   |
| Hitachi HTS545050A7E380 500GB                  | 2         | 2      | 1.02%   |
| Hitachi HTS545032B9A302 320GB                  | 2         | 3      | 1.02%   |
| Hitachi HTS545032B9A300 320GB                  | 2         | 2      | 1.02%   |
| Hitachi HTS545025B9A300 250GB                  | 2         | 2      | 1.02%   |
| Hitachi HTS541680J9SA00 80GB                   | 2         | 2      | 1.02%   |
| HGST HTS721010A9E630 1TB                       | 2         | 2      | 1.02%   |
| Drevo X1 SSD 64GB                              | 2         | 2      | 1.02%   |
| Crucial CT525MX300SSD4 528GB                   | 2         | 2      | 1.02%   |
| Zheino CHN mSATA02M 256 256GB SSD              | 1         | 2      | 0.51%   |
| WDC WD7500BPVT-60HXZT3 752GB                   | 1         | 1      | 0.51%   |
| WDC WD5000BPVT-55HXZT3 500GB                   | 1         | 1      | 0.51%   |
| WDC WD5000BEVT-75A0RT0 500GB                   | 1         | 1      | 0.51%   |
| WDC WD5000BEVT-60A0RT0 500GB                   | 1         | 2      | 0.51%   |
| WDC WD5000BEVT-35A0RT0 500GB                   | 1         | 1      | 0.51%   |
| WDC WD5000BEKT-75KA9T0 500GB                   | 1         | 1      | 0.51%   |
| WDC WD3200LPCX-24C6HT0 320GB                   | 1         | 1      | 0.51%   |
| WDC WD3200BEKT-75PVMT0 320GB                   | 1         | 1      | 0.51%   |
| WDC WD3200BEKT-60PVMT0 320GB                   | 1         | 1      | 0.51%   |
| WDC WD2500BEVT-75A23T0 250GB                   | 1         | 1      | 0.51%   |
| WDC WD2500BEVT-60A23T0 250GB                   | 1         | 1      | 0.51%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 54     | 24.1%   |
| Hitachi             | 35        | 38     | 17.95%  |
| Toshiba             | 23        | 24     | 11.79%  |
| HGST                | 15        | 18     | 7.69%   |
| WDC                 | 14        | 19     | 7.18%   |
| Samsung Electronics | 10        | 11     | 5.13%   |
| Crucial             | 10        | 10     | 5.13%   |
| Intel               | 7         | 7      | 3.59%   |
| SanDisk             | 5         | 5      | 2.56%   |
| Kingston            | 5         | 7      | 2.56%   |
| Fujitsu             | 4         | 4      | 2.05%   |
| Micron Technology   | 3         | 3      | 1.54%   |
| LITEON              | 3         | 3      | 1.54%   |
| SK hynix            | 2         | 2      | 1.03%   |
| Drevo               | 2         | 2      | 1.03%   |
| A-DATA Technology   | 2         | 2      | 1.03%   |
| Zheino              | 1         | 2      | 0.51%   |
| Team                | 1         | 1      | 0.51%   |
| OCZ                 | 1         | 1      | 0.51%   |
| LITEONIT            | 1         | 2      | 0.51%   |
| Corsair             | 1         | 1      | 0.51%   |
| China               | 1         | 1      | 0.51%   |
| BAITITON            | 1         | 1      | 0.51%   |
| 2-Power             | 1         | 1      | 0.51%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 47        | 54     | 33.81%  |
| Hitachi             | 35        | 38     | 25.18%  |
| Toshiba             | 21        | 22     | 15.11%  |
| HGST                | 15        | 18     | 10.79%  |
| WDC                 | 13        | 18     | 9.35%   |
| Samsung Electronics | 4         | 4      | 2.88%   |
| Fujitsu             | 4         | 4      | 2.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 138       | 158    | 71.13%  |
| SSD  | 53        | 58     | 27.32%  |
| NVMe | 3         | 3      | 1.55%   |

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
| Detected | 2592      | 4132   | 62.4%   |
| Works    | 1368      | 1860   | 32.93%  |
| Malfunc  | 191       | 219    | 4.6%    |
| Failed   | 3         | 4      | 0.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2662      | 58.65%  |
| Samsung Electronics              | 448       | 9.87%   |
| AMD                              | 442       | 9.74%   |
| SanDisk                          | 221       | 4.87%   |
| SK hynix                         | 157       | 3.46%   |
| Toshiba America Info Systems     | 119       | 2.62%   |
| Phison Electronics               | 92        | 2.03%   |
| Kingston Technology Company      | 61        | 1.34%   |
| Micron Technology                | 58        | 1.28%   |
| KIOXIA                           | 52        | 1.15%   |
| Nvidia                           | 38        | 0.84%   |
| Micron/Crucial Technology        | 38        | 0.84%   |
| Silicon Motion                   | 25        | 0.55%   |
| O2 Micro                         | 16        | 0.35%   |
| Apple                            | 16        | 0.35%   |
| ADATA Technology                 | 14        | 0.31%   |
| Silicon Integrated Systems [SiS] | 12        | 0.26%   |
| Lenovo                           | 11        | 0.24%   |
| Solid State Storage Technology   | 10        | 0.22%   |
| Union Memory (Shenzhen)          | 7         | 0.15%   |
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
| AMD FCH SATA Controller [AHCI mode]                                              | 373       | 7.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 303       | 6.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 260       | 5.33%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 259       | 5.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 207       | 4.25%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 188       | 3.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 167       | 3.43%   |
| Intel Volume Management Device NVMe RAID Controller                              | 130       | 2.67%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 129       | 2.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 118       | 2.42%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 114       | 2.34%   |
| Samsung NVMe SSD Controller 980                                                  | 90        | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 90        | 1.85%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 82        | 1.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 80        | 1.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 79        | 1.62%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 71        | 1.46%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 68        | 1.39%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 58        | 1.19%   |
| Intel Comet Lake SATA AHCI Controller                                            | 54        | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 53        | 1.09%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 53        | 1.09%   |
| Phison PS5013 E13 NVMe Controller                                                | 51        | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 51        | 1.05%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 49        | 1.01%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 48        | 0.98%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 46        | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 46        | 0.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 45        | 0.92%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 43        | 0.88%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 40        | 0.82%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 38        | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 38        | 0.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 38        | 0.78%   |
| Intel Tiger Lake-LP SATA Controller                                              | 35        | 0.72%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 35        | 0.72%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 30        | 0.62%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                             | 28        | 0.57%   |
| Intel SSD 660P Series                                                            | 28        | 0.57%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)             | 27        | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2616      | 55.99%  |
| NVMe | 1344      | 28.77%  |
| RAID | 401       | 8.58%   |
| IDE  | 311       | 6.66%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 3258      | 82.38%  |
| AMD    | 696       | 17.6%   |
| ARM    | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Custom APU 0405                           | 97        | 2.45%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 60        | 1.52%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 54        | 1.36%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 52        | 1.31%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 51        | 1.29%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 50        | 1.26%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 46        | 1.16%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 45        | 1.14%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 45        | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 44        | 1.11%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 42        | 1.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 42        | 1.06%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 40        | 1.01%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 40        | 1.01%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 39        | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 38        | 0.96%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 38        | 0.96%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 38        | 0.96%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 38        | 0.96%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 37        | 0.93%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 37        | 0.93%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 33        | 0.83%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 33        | 0.83%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 30        | 0.76%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 29        | 0.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 28        | 0.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 28        | 0.71%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 27        | 0.68%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 26        | 0.66%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 23        | 0.58%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 23        | 0.58%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 22        | 0.56%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 22        | 0.56%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 22        | 0.56%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 21        | 0.53%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.53%   |
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
| Intel Core i5           | 940       | 23.75%  |
| Intel Core i7           | 867       | 21.91%  |
| Other                   | 402       | 10.16%  |
| Intel Celeron           | 273       | 6.9%    |
| Intel Core i3           | 266       | 6.72%   |
| Intel Core 2 Duo        | 208       | 5.26%   |
| AMD Ryzen 7             | 110       | 2.78%   |
| Intel Pentium           | 109       | 2.75%   |
| AMD Ryzen 5             | 108       | 2.73%   |
| Intel Atom              | 81        | 2.05%   |
| AMD A6                  | 60        | 1.52%   |
| AMD A8                  | 41        | 1.04%   |
| Intel Pentium Dual-Core | 37        | 0.93%   |
| AMD Ryzen 3             | 33        | 0.83%   |
| Intel Core 2            | 31        | 0.78%   |
| Intel Pentium Dual      | 27        | 0.68%   |
| AMD A4                  | 27        | 0.68%   |
| Intel Genuine           | 25        | 0.63%   |
| AMD Ryzen 9             | 25        | 0.63%   |
| Intel Core i9           | 22        | 0.56%   |
| Intel Celeron Dual-Core | 20        | 0.51%   |
| AMD E1                  | 20        | 0.51%   |
| AMD A10                 | 17        | 0.43%   |
| AMD Ryzen 7 PRO         | 16        | 0.4%    |
| AMD E                   | 16        | 0.4%    |
| Intel Pentium Silver    | 15        | 0.38%   |
| Intel Celeron M         | 14        | 0.35%   |
| AMD E2                  | 14        | 0.35%   |
| Intel Pentium M         | 10        | 0.25%   |
| AMD Athlon              | 9         | 0.23%   |
| AMD Turion 64 X2 Mobile | 8         | 0.2%    |
| AMD FX                  | 7         | 0.18%   |
| AMD Athlon X2           | 7         | 0.18%   |
| AMD Athlon II           | 7         | 0.18%   |
| AMD Turion 64 Mobile    | 6         | 0.15%   |
| AMD Ryzen 5 PRO         | 6         | 0.15%   |
| Intel Pentium Gold      | 5         | 0.13%   |
| Intel Core m3           | 5         | 0.13%   |
| Intel Core M            | 5         | 0.13%   |
| AMD Phenom II           | 5         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2101      | 53.1%   |
| 4      | 1245      | 31.46%  |
| 6      | 215       | 5.43%   |
| 8      | 202       | 5.1%    |
| 1      | 107       | 2.7%    |
| 14     | 33        | 0.83%   |
| 12     | 29        | 0.73%   |
| 10     | 22        | 0.56%   |
| 3      | 2         | 0.05%   |
| 16     | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3954      | 99.97%  |
| 2      | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2810      | 71%     |
| 1      | 1148      | 29%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3852      | 97.1%   |
| Unknown        | 58        | 1.46%   |
| 32-bit         | 57        | 1.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1186      | 28.9%   |
| 0x306a9    | 231       | 5.63%   |
| 0x206a7    | 204       | 4.97%   |
| 0x1067a    | 153       | 3.73%   |
| 0x806ec    | 121       | 2.95%   |
| 0x806ea    | 120       | 2.92%   |
| 0x40651    | 118       | 2.88%   |
| 0x406e3    | 112       | 2.73%   |
| 0x806e9    | 106       | 2.58%   |
| 0x306d4    | 104       | 2.53%   |
| 0x20655    | 97        | 2.36%   |
| 0x806c1    | 93        | 2.27%   |
| 0x906ea    | 87        | 2.12%   |
| 0x6fd      | 69        | 1.68%   |
| 0x406c4    | 65        | 1.58%   |
| 0x306c3    | 64        | 1.56%   |
| 0x30678    | 61        | 1.49%   |
| 0x906e9    | 49        | 1.19%   |
| 0xa0652    | 48        | 1.17%   |
| 0x506e3    | 44        | 1.07%   |
| 0x506c9    | 44        | 1.07%   |
| 0x06006705 | 41        | 1%      |
| 0x08108109 | 38        | 0.93%   |
| 0x706e5    | 37        | 0.9%    |
| 0x0a50000c | 37        | 0.9%    |
| 0x08108102 | 36        | 0.88%   |
| 0x406c3    | 34        | 0.83%   |
| 0x20652    | 33        | 0.8%    |
| 0x10676    | 32        | 0.78%   |
| 0x806d1    | 31        | 0.76%   |
| 0x906a3    | 30        | 0.73%   |
| 0x07030105 | 30        | 0.73%   |
| 0x706a1    | 29        | 0.71%   |
| 0x6f6      | 25        | 0.61%   |
| 0x08600106 | 22        | 0.54%   |
| 0x06006704 | 22        | 0.54%   |
| 0x806eb    | 21        | 0.51%   |
| 0x05000119 | 20        | 0.49%   |
| 0x08600104 | 19        | 0.46%   |
| 0x08608103 | 17        | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 715       | 18.05%  |
| IvyBridge        | 297       | 7.5%    |
| Haswell          | 265       | 6.69%   |
| SandyBridge      | 264       | 6.66%   |
| Penryn           | 216       | 5.45%   |
| Skylake          | 213       | 5.38%   |
| Silvermont       | 202       | 5.1%    |
| Unknown          | 194       | 4.9%    |
| Westmere         | 164       | 4.14%   |
| Core             | 153       | 3.86%   |
| TigerLake        | 149       | 3.76%   |
| Broadwell        | 146       | 3.69%   |
| Zen+             | 92        | 2.32%   |
| Icelake          | 89        | 2.25%   |
| Excavator        | 82        | 2.07%   |
| CometLake        | 77        | 1.94%   |
| Zen 2            | 71        | 1.79%   |
| Alderlake Hybrid | 65        | 1.64%   |
| Goldmont plus    | 64        | 1.62%   |
| Zen 3            | 57        | 1.44%   |
| Puma             | 55        | 1.39%   |
| Goldmont         | 52        | 1.31%   |
| P6               | 40        | 1.01%   |
| Zen              | 38        | 0.96%   |
| Bobcat           | 35        | 0.88%   |
| Bonnell          | 32        | 0.81%   |
| K10              | 22        | 0.56%   |
| Jaguar           | 22        | 0.56%   |
| Piledriver       | 20        | 0.5%    |
| K8 Hammer        | 20        | 0.5%    |
| Steamroller      | 14        | 0.35%   |
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
| Intel                            | 3003      | 63.14%  |
| Nvidia                           | 908       | 19.09%  |
| AMD                              | 828       | 17.41%  |
| Silicon Integrated Systems [SiS] | 12        | 0.25%   |
| VIA Technologies                 | 4         | 0.08%   |
| ATI Technologies                 | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 282       | 5.74%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 250       | 5.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 172       | 3.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 156       | 3.18%   |
| Intel UHD Graphics 620                                                                   | 150       | 3.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 136       | 2.77%   |
| Intel Core Processor Integrated Graphics Controller                                      | 133       | 2.71%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 132       | 2.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 130       | 2.65%   |
| Intel HD Graphics 620                                                                    | 122       | 2.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 116       | 2.36%   |
| Intel HD Graphics 5500                                                                   | 109       | 2.22%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 100       | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 98        | 2%      |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 97        | 1.98%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 97        | 1.98%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 91        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 86        | 1.75%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 69        | 1.41%   |
| AMD Renoir                                                                               | 66        | 1.34%   |
| Intel HD Graphics 630                                                                    | 63        | 1.28%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 63        | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 60        | 1.22%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 60        | 1.22%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 54        | 1.1%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 53        | 1.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 49        | 1%      |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 48        | 0.98%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 47        | 0.96%   |
| Intel HD Graphics 530                                                                    | 47        | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 43        | 0.88%   |
| Intel HD Graphics 500                                                                    | 42        | 0.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 42        | 0.86%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 40        | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 37        | 0.75%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 35        | 0.71%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 33        | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 31        | 0.63%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 31        | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 31        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 2245      | 56.55%  |
| 1 x AMD                  | 654       | 16.47%  |
| Intel + Nvidia           | 653       | 16.45%  |
| 1 x Nvidia               | 195       | 4.91%   |
| Intel + AMD              | 85        | 2.14%   |
| AMD + Nvidia             | 56        | 1.41%   |
| 2 x AMD                  | 33        | 0.83%   |
| 2 x Intel                | 20        | 0.5%    |
| 1 x SiS                  | 12        | 0.3%    |
| Other                    | 8         | 0.2%    |
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
| Free        | 3446      | 86.09%  |
| Proprietary | 472       | 11.79%  |
| Unknown     | 85        | 2.12%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2815      | 69.42%  |
| 0.01-0.5   | 455       | 11.22%  |
| 1.01-2.0   | 325       | 8.01%   |
| 3.01-4.0   | 182       | 4.49%   |
| 0.51-1.0   | 159       | 3.92%   |
| 5.01-6.0   | 63        | 1.55%   |
| 7.01-8.0   | 38        | 0.94%   |
| 2.01-3.0   | 9         | 0.22%   |
| 8.01-16.0  | 9         | 0.22%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 823       | 19.01%  |
| LG Display              | 656       | 15.15%  |
| Chimei Innolux          | 525       | 12.13%  |
| BOE                     | 485       | 11.2%   |
| Samsung Electronics     | 454       | 10.49%  |
| Sharp                   | 204       | 4.71%   |
| Apple                   | 127       | 2.93%   |
| Dell                    | 106       | 2.45%   |
| Lenovo                  | 95        | 2.19%   |
| Chi Mei Optoelectronics | 84        | 1.94%   |
| PANDA                   | 64        | 1.48%   |
| Goldstar                | 63        | 1.46%   |
| Valve                   | 53        | 1.22%   |
| LG Philips              | 49        | 1.13%   |
| Acer                    | 46        | 1.06%   |
| Hewlett-Packard         | 45        | 1.04%   |
| InfoVision              | 36        | 0.83%   |
| BenQ                    | 34        | 0.79%   |
| Iiyama                  | 33        | 0.76%   |
| AOC                     | 31        | 0.72%   |
| Analogix                | 26        | 0.6%    |
| Philips                 | 22        | 0.51%   |
| CSO                     | 21        | 0.49%   |
| Ancor Communications    | 21        | 0.49%   |
| Panasonic               | 18        | 0.42%   |
| Sony                    | 15        | 0.35%   |
| ViewSonic               | 13        | 0.3%    |
| Toshiba                 | 13        | 0.3%    |
| LGD                     | 13        | 0.3%    |
| InnoLux Display         | 12        | 0.28%   |
| HannStar                | 11        | 0.25%   |
| Vestel Elektronik       | 9         | 0.21%   |
| ASUSTek Computer        | 8         | 0.18%   |
| CPT                     | 7         | 0.16%   |
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


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 53        | 1.21%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 43        | 0.98%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 35        | 0.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 33        | 0.76%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch         | 32        | 0.73%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 31        | 0.71%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 29        | 0.66%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 26        | 0.59%   |
| Analogix ANX7530 U ANX7539 800x1280                                   | 26        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 22        | 0.5%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 22        | 0.5%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 21        | 0.48%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 18        | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 17        | 0.39%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 16        | 0.37%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 16        | 0.37%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 15        | 0.34%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch         | 15        | 0.34%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 14        | 0.32%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 14        | 0.32%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 14        | 0.32%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch        | 14        | 0.32%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch         | 14        | 0.32%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch               | 13        | 0.3%    |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 13        | 0.3%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 13        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 13        | 0.3%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 13        | 0.3%    |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch               | 12        | 0.27%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 12        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 12        | 0.27%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 12        | 0.27%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch         | 12        | 0.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch  | 11        | 0.25%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch | 11        | 0.25%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 11        | 0.25%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch           | 11        | 0.25%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 11        | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1561      | 37.81%  |
| 1366x768 (WXGA)    | 1259      | 30.5%   |
| 1280x800 (WXGA)    | 213       | 5.16%   |
| 3840x2160 (4K)     | 189       | 4.58%   |
| 1600x900 (HD+)     | 158       | 3.83%   |
| 2560x1440 (QHD)    | 125       | 3.03%   |
| 1920x1200 (WUXGA)  | 81        | 1.96%   |
| 1440x900 (WXGA+)   | 81        | 1.96%   |
| 800x1280           | 76        | 1.84%   |
| 2560x1600          | 58        | 1.41%   |
| 2880x1800          | 36        | 0.87%   |
| 3840x2400          | 35        | 0.85%   |
| 1680x1050 (WSXGA+) | 32        | 0.78%   |
| 3440x1440          | 25        | 0.61%   |
| 3200x1800 (QHD+)   | 23        | 0.56%   |
| 1024x600           | 21        | 0.51%   |
| 1280x1024 (SXGA)   | 19        | 0.46%   |
| 2160x1440          | 13        | 0.31%   |
| 2560x1080          | 12        | 0.29%   |
| Unknown            | 10        | 0.24%   |
| 2256x1504          | 9         | 0.22%   |
| 1360x768           | 9         | 0.22%   |
| 1920x540           | 7         | 0.17%   |
| 3456x2160          | 6         | 0.15%   |
| 3072x1920          | 6         | 0.15%   |
| 1024x768 (XGA)     | 6         | 0.15%   |
| 2560x1700          | 5         | 0.12%   |
| 1920x1280          | 5         | 0.12%   |
| 1680x945           | 5         | 0.12%   |
| 3000x2000          | 4         | 0.1%    |
| 3840x1080          | 3         | 0.07%   |
| 2880x1920          | 3         | 0.07%   |
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
| 15      | 1742      | 40.35%  |
| 13      | 682       | 15.8%   |
| 14      | 435       | 10.08%  |
| 17      | 276       | 6.39%   |
| 12      | 193       | 4.47%   |
| 27      | 128       | 2.97%   |
| 11      | 120       | 2.78%   |
| 24      | 99        | 2.29%   |
| 23      | 76        | 1.76%   |
| 21      | 76        | 1.76%   |
| Unknown | 61        | 1.41%   |
| 7       | 53        | 1.23%   |
| 16      | 48        | 1.11%   |
| 31      | 43        | 1%      |
| 34      | 33        | 0.76%   |
| 10      | 32        | 0.74%   |
| 18      | 29        | 0.67%   |
| 3       | 26        | 0.6%    |
| 84      | 22        | 0.51%   |
| 19      | 18        | 0.42%   |
| 25      | 14        | 0.32%   |
| 22      | 13        | 0.3%    |
| 72      | 10        | 0.23%   |
| 26      | 10        | 0.23%   |
| 20      | 9         | 0.21%   |
| 8       | 8         | 0.19%   |
| 54      | 7         | 0.16%   |
| 40      | 7         | 0.16%   |
| 48      | 6         | 0.14%   |
| 32      | 5         | 0.12%   |
| 65      | 4         | 0.09%   |
| 86      | 3         | 0.07%   |
| 50      | 3         | 0.07%   |
| 35      | 3         | 0.07%   |
| 33      | 3         | 0.07%   |
| 28      | 3         | 0.07%   |
| 142     | 2         | 0.05%   |
| 49      | 2         | 0.05%   |
| 46      | 2         | 0.05%   |
| 39      | 2         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2446      | 56.95%  |
| 201-300        | 745       | 17.35%  |
| 351-400        | 349       | 8.13%   |
| 501-600        | 300       | 6.98%   |
| 401-500        | 129       | 3%      |
| 1-100          | 76        | 1.77%   |
| Unknown        | 61        | 1.42%   |
| 601-700        | 59        | 1.37%   |
| 701-800        | 41        | 0.95%   |
| 1501-2000      | 34        | 0.79%   |
| 1001-1500      | 29        | 0.68%   |
| 801-900        | 12        | 0.28%   |
| 101-200        | 8         | 0.19%   |
| More than 2000 | 3         | 0.07%   |
| 901-1000       | 3         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 3129      | 79.8%   |
| 16/10   | 526       | 13.41%  |
| Unknown | 55        | 1.4%    |
| 0.67    | 53        | 1.35%   |
| 3/2     | 52        | 1.33%   |
| 21/9    | 39        | 0.99%   |
| 6/5     | 29        | 0.74%   |
| 5/4     | 16        | 0.41%   |
| 4/3     | 11        | 0.28%   |
| 32/9    | 3         | 0.08%   |
| 1.00    | 3         | 0.08%   |
| 0.62    | 2         | 0.05%   |
| 0.56    | 2         | 0.05%   |
| 3.40    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1735      | 40.26%  |
| 81-90          | 795       | 18.45%  |
| 71-80          | 321       | 7.45%   |
| 121-130        | 227       | 5.27%   |
| 201-250        | 218       | 5.06%   |
| 61-70          | 185       | 4.29%   |
| 301-350        | 136       | 3.16%   |
| 51-60          | 122       | 2.83%   |
| 351-500        | 89        | 2.07%   |
| 1-40           | 84        | 1.95%   |
| More than 1000 | 61        | 1.42%   |
| Unknown        | 61        | 1.42%   |
| 111-120        | 51        | 1.18%   |
| 131-140        | 47        | 1.09%   |
| 151-200        | 46        | 1.07%   |
| 251-300        | 40        | 0.93%   |
| 41-50          | 31        | 0.72%   |
| 141-150        | 30        | 0.7%    |
| 501-1000       | 17        | 0.39%   |
| 91-100         | 13        | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1619      | 38%     |
| 101-120       | 1271      | 29.84%  |
| 51-100        | 596       | 13.99%  |
| 161-240       | 446       | 10.47%  |
| More than 240 | 219       | 5.14%   |
| Unknown       | 61        | 1.43%   |
| 1-50          | 48        | 1.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 3361      | 83.48%  |
| 2     | 531       | 13.19%  |
| 0     | 83        | 2.06%   |
| 3     | 46        | 1.14%   |
| 4     | 4         | 0.1%    |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 2156      | 35.2%   |
| Realtek Semiconductor             | 1869      | 30.51%  |
| Qualcomm Atheros                  | 827       | 13.5%   |
| Broadcom                          | 452       | 7.38%   |
| Broadcom Limited                  | 105       | 1.71%   |
| Marvell Technology Group          | 92        | 1.5%    |
| MediaTek                          | 54        | 0.88%   |
| Ralink Technology                 | 53        | 0.87%   |
| Ralink                            | 47        | 0.77%   |
| TP-Link                           | 44        | 0.72%   |
| Ericsson Business Mobile Networks | 41        | 0.67%   |
| ASIX Electronics                  | 35        | 0.57%   |
| Dell                              | 34        | 0.56%   |
| Nvidia                            | 28        | 0.46%   |
| Qualcomm                          | 27        | 0.44%   |
| DisplayLink                       | 27        | 0.44%   |
| Lenovo                            | 25        | 0.41%   |
| Samsung Electronics               | 22        | 0.36%   |
| Hewlett-Packard                   | 19        | 0.31%   |
| Sierra Wireless                   | 15        | 0.24%   |
| JMicron Technology                | 12        | 0.2%    |
| Huawei Technologies               | 12        | 0.2%    |
| Silicon Integrated Systems [SiS]  | 11        | 0.18%   |
| NetGear                           | 8         | 0.13%   |
| Edimax Technology                 | 8         | 0.13%   |
| Qualcomm Atheros Communications   | 6         | 0.1%    |
| ICS Advent                        | 6         | 0.1%    |
| Google                            | 6         | 0.1%    |
| OnePlus Technology (Shenzhen)     | 5         | 0.08%   |
| Micro Star International          | 5         | 0.08%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 997       | 13.43%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 393       | 5.3%    |
| Intel Wi-Fi 6 AX200                                                     | 181       | 2.44%   |
| Intel Wireless 8265 / 8275                                              | 170       | 2.29%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 168       | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 154       | 2.07%   |
| Intel Wireless 7265                                                     | 149       | 2.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 145       | 1.95%   |
| Intel Wireless 7260                                                     | 145       | 1.95%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 138       | 1.86%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 134       | 1.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 127       | 1.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 126       | 1.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 113       | 1.52%   |
| Intel Wireless 8260                                                     | 103       | 1.39%   |
| Intel Wi-Fi 6 AX201                                                     | 97        | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 93        | 1.25%   |
| Intel Wireless 3165                                                     | 87        | 1.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 85        | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 75        | 1.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 69        | 0.93%   |
| Broadcom BCM43142 802.11b/g/n                                           | 69        | 0.93%   |
| Intel 82577LM Gigabit Network Connection                                | 67        | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 65        | 0.88%   |
| Intel Ethernet Connection I218-LM                                       | 64        | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                                   | 64        | 0.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 0.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 60        | 0.81%   |
| Intel Wireless 3160                                                     | 54        | 0.73%   |
| Intel Wireless-AC 9260                                                  | 51        | 0.69%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 50        | 0.67%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 49        | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 48        | 0.65%   |
| Intel WiFi Link 5100                                                    | 47        | 0.63%   |
| Intel Centrino Ultimate-N 6300                                          | 46        | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 45        | 0.61%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 45        | 0.61%   |
| Intel Ethernet Connection I219-LM                                       | 45        | 0.61%   |
| Intel Ethernet Connection (3) I218-LM                                   | 44        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2068      | 50.02%  |
| Qualcomm Atheros                | 717       | 17.34%  |
| Realtek Semiconductor           | 629       | 15.22%  |
| Broadcom                        | 345       | 8.35%   |
| Broadcom Limited                | 82        | 1.98%   |
| Ralink Technology               | 53        | 1.28%   |
| MediaTek                        | 49        | 1.19%   |
| Ralink                          | 47        | 1.14%   |
| TP-Link                         | 37        | 0.9%    |
| Dell                            | 18        | 0.44%   |
| Qualcomm                        | 16        | 0.39%   |
| Sierra Wireless                 | 15        | 0.36%   |
| NetGear                         | 8         | 0.19%   |
| Edimax Technology               | 8         | 0.19%   |
| Qualcomm Atheros Communications | 6         | 0.15%   |
| Micro Star International        | 5         | 0.12%   |
| Belkin Components               | 5         | 0.12%   |
| Fibocom                         | 4         | 0.1%    |
| ASUSTek Computer                | 4         | 0.1%    |
| Wacom                           | 2         | 0.05%   |
| Qualcomm Technologies           | 2         | 0.05%   |
| Hewlett-Packard                 | 2         | 0.05%   |
| D-Link                          | 2         | 0.05%   |
| ZyDAS                           | 1         | 0.02%   |
| Senao                           | 1         | 0.02%   |
| Microsoft                       | 1         | 0.02%   |
| Marvell Technology Group        | 1         | 0.02%   |
| Linksys                         | 1         | 0.02%   |
| InProComm                       | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |
| Apple                           | 1         | 0.02%   |
| 3Com                            | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 181       | 4.35%   |
| Intel Wireless 8265 / 8275                                              | 170       | 4.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 154       | 3.7%    |
| Intel Wireless 7265                                                     | 149       | 3.58%   |
| Intel Wireless 7260                                                     | 145       | 3.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 138       | 3.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 134       | 3.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 127       | 3.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 126       | 3.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 113       | 2.72%   |
| Intel Wireless 8260                                                     | 103       | 2.48%   |
| Intel Wi-Fi 6 AX201                                                     | 97        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 93        | 2.24%   |
| Intel Wireless 3165                                                     | 87        | 2.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 85        | 2.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 75        | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 69        | 1.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 69        | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 65        | 1.56%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 65        | 1.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 61        | 1.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 59        | 1.42%   |
| Intel Wireless 3160                                                     | 54        | 1.3%    |
| Intel Wireless-AC 9260                                                  | 51        | 1.23%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 50        | 1.2%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 49        | 1.18%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 48        | 1.15%   |
| Intel WiFi Link 5100                                                    | 47        | 1.13%   |
| Intel Centrino Ultimate-N 6300                                          | 46        | 1.11%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 45        | 1.08%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 45        | 1.08%   |
| Intel Centrino Advanced-N 6200                                          | 42        | 1.01%   |
| Intel Centrino Advanced-N 6235                                          | 41        | 0.99%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 38        | 0.91%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 38        | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 33        | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 32        | 0.77%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 32        | 0.77%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 31        | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 29        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1598      | 51.09%  |
| Intel                            | 791       | 25.29%  |
| Qualcomm Atheros                 | 205       | 6.55%   |
| Broadcom                         | 175       | 5.59%   |
| Marvell Technology Group         | 91        | 2.91%   |
| ASIX Electronics                 | 35        | 1.12%   |
| Nvidia                           | 28        | 0.9%    |
| DisplayLink                      | 27        | 0.86%   |
| Broadcom Limited                 | 26        | 0.83%   |
| Samsung Electronics              | 22        | 0.7%    |
| Lenovo                           | 22        | 0.7%    |
| JMicron Technology               | 12        | 0.38%   |
| Qualcomm                         | 11        | 0.35%   |
| Silicon Integrated Systems [SiS] | 10        | 0.32%   |
| Huawei Technologies              | 10        | 0.32%   |
| TP-Link                          | 7         | 0.22%   |
| ICS Advent                       | 6         | 0.19%   |
| Google                           | 6         | 0.19%   |
| OnePlus Technology (Shenzhen)    | 5         | 0.16%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 997       | 31.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 393       | 12.44%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 168       | 5.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 145       | 4.59%   |
| Intel 82577LM Gigabit Network Connection                          | 67        | 2.12%   |
| Intel Ethernet Connection I218-LM                                 | 64        | 2.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 64        | 2.03%   |
| Intel Ethernet Connection I219-LM                                 | 45        | 1.42%   |
| Intel Ethernet Connection (3) I218-LM                             | 44        | 1.39%   |
| Intel 82567LM Gigabit Network Connection                          | 41        | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 37        | 1.17%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 36        | 1.14%   |
| Intel Ethernet Connection (4) I219-V                              | 36        | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 0.98%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29        | 0.92%   |
| Intel Ethernet Connection I219-V                                  | 26        | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 25        | 0.79%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 24        | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 0.76%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 24        | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 19        | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 18        | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 18        | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 18        | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                             | 18        | 0.57%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 17        | 0.54%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 17        | 0.54%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 17        | 0.54%   |
| Intel Ethernet Connection (2) I219-LM                             | 16        | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 15        | 0.47%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.47%   |
| Intel 82566MM Gigabit Network Connection                          | 15        | 0.47%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 15        | 0.47%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 14        | 0.44%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 14        | 0.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 13        | 0.41%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 13        | 0.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 12        | 0.38%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.38%   |
| Intel Ethernet Connection (6) I219-LM                             | 12        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3897      | 55.47%  |
| Ethernet | 3023      | 43.03%  |
| Modem    | 99        | 1.41%   |
| Unknown  | 6         | 0.09%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3363      | 80.96%  |
| Ethernet | 791       | 19.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2737      | 69.13%  |
| 1     | 1145      | 28.92%  |
| 0     | 59        | 1.49%   |
| 3     | 17        | 0.43%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3481      | 86.57%  |
| Yes  | 540       | 13.43%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1527      | 48.93%  |
| Qualcomm Atheros Communications | 274       | 8.78%   |
| Realtek Semiconductor           | 258       | 8.27%   |
| Broadcom                        | 206       | 6.6%    |
| IMC Networks                    | 198       | 6.34%   |
| Foxconn / Hon Hai               | 109       | 3.49%   |
| Apple                           | 107       | 3.43%   |
| Lite-On Technology              | 97        | 3.11%   |
| Dell                            | 73        | 2.34%   |
| Cambridge Silicon Radio         | 65        | 2.08%   |
| Toshiba                         | 58        | 1.86%   |
| Hewlett-Packard                 | 44        | 1.41%   |
| Realtek                         | 22        | 0.7%    |
| Alps Electric                   | 19        | 0.61%   |
| Foxconn International           | 14        | 0.45%   |
| Ralink                          | 9         | 0.29%   |
| ASUSTek Computer                | 8         | 0.26%   |
| Ralink Technology               | 6         | 0.19%   |
| Askey Computer                  | 6         | 0.19%   |
| USI                             | 5         | 0.16%   |
| Taiyo Yuden                     | 5         | 0.16%   |
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
| Intel Bluetooth wireless interface                  | 670       | 21.45%  |
| Intel AX201 Bluetooth                               | 255       | 8.17%   |
| Intel AX200 Bluetooth                               | 177       | 5.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 158       | 5.06%   |
| Realtek Bluetooth Radio                             | 152       | 4.87%   |
| IMC Networks Bluetooth Radio                        | 132       | 4.23%   |
| Qualcomm Atheros  Bluetooth Device                  | 103       | 3.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 73        | 2.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 72        | 2.31%   |
| Apple Bluetooth Host Controller                     | 69        | 2.21%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 65        | 2.08%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 62        | 1.99%   |
| Foxconn / Hon Hai Bluetooth Device                  | 58        | 1.86%   |
| Intel Bluetooth Device                              | 55        | 1.76%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 52        | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 43        | 1.38%   |
| Broadcom BCM2045B (BDC-2.1)                         | 42        | 1.34%   |
| Intel AX210 Bluetooth                               | 41        | 1.31%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 39        | 1.25%   |
| Intel Wireless-AC 3168 Bluetooth                    | 38        | 1.22%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 31        | 0.99%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 29        | 0.93%   |
| Apple Bluetooth USB Host Controller                 | 27        | 0.86%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 26        | 0.83%   |
| Dell DW375 Bluetooth Module                         | 26        | 0.83%   |
| IMC Networks Wireless_Device                        | 24        | 0.77%   |
| IMC Networks Bluetooth Device                       | 23        | 0.74%   |
| Realtek Bluetooth Radio                             | 22        | 0.7%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 22        | 0.7%    |
| Lite-On Bluetooth Device                            | 20        | 0.64%   |
| Toshiba Bluetooth Device                            | 19        | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 19        | 0.61%   |
| Dell BCM20702A0 Bluetooth Module                    | 19        | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 17        | 0.54%   |
| Broadcom HP Portable SoftSailing                    | 16        | 0.51%   |
| Realtek RTL8723B Bluetooth                          | 14        | 0.45%   |
| Foxconn International BCM43142A0 Bluetooth module   | 14        | 0.45%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 14        | 0.45%   |
| Toshiba Atheros AR3012 Bluetooth                    | 12        | 0.38%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 3168      | 67.4%   |
| AMD                              | 750       | 15.96%  |
| Nvidia                           | 483       | 10.28%  |
| C-Media Electronics              | 38        | 0.81%   |
| Realtek Semiconductor            | 28        | 0.6%    |
| GN Netcom                        | 20        | 0.43%   |
| Plantronics                      | 18        | 0.38%   |
| Lenovo                           | 18        | 0.38%   |
| Texas Instruments                | 14        | 0.3%    |
| Silicon Integrated Systems [SiS] | 12        | 0.26%   |
| Apple                            | 11        | 0.23%   |
| Logitech                         | 10        | 0.21%   |
| JMTek                            | 9         | 0.19%   |
| Creative Technology              | 8         | 0.17%   |
| ASUSTek Computer                 | 7         | 0.15%   |
| VIA Technologies                 | 5         | 0.11%   |
| Hewlett-Packard                  | 5         | 0.11%   |
| Corsair                          | 5         | 0.11%   |
| Conexant Systems                 | 5         | 0.11%   |
| SteelSeries ApS                  | 4         | 0.09%   |
| Sennheiser Communications        | 4         | 0.09%   |
| RODE Microphones                 | 4         | 0.09%   |
| Kingston Technology              | 4         | 0.09%   |
| Generalplus Technology           | 4         | 0.09%   |
| Focusrite-Novation               | 4         | 0.09%   |
| Blue Microphones                 | 4         | 0.09%   |
| Yamaha                           | 3         | 0.06%   |
| XMOS                             | 3         | 0.06%   |
| Sony                             | 3         | 0.06%   |
| Razer USA                        | 3         | 0.06%   |
| PreSonus Audio Electronics       | 3         | 0.06%   |
| Google                           | 3         | 0.06%   |
| Dell                             | 3         | 0.06%   |
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
| Intel Sunrise Point-LP HD Audio                                                                   | 445       | 7.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 347       | 6.16%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 303       | 5.38%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 212       | 3.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 208       | 3.7%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 175       | 3.11%   |
| Intel 8 Series HD Audio Controller                                                                | 158       | 2.81%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 157       | 2.79%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 149       | 2.65%   |
| Intel Cannon Lake PCH cAVS                                                                        | 149       | 2.65%   |
| Intel Broadwell-U Audio Controller                                                                | 146       | 2.59%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 140       | 2.49%   |
| AMD FCH Azalia Controller                                                                         | 134       | 2.38%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 132       | 2.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 121       | 2.15%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 115       | 2.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 108       | 1.92%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 108       | 1.92%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 98        | 1.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 91        | 1.62%   |
| AMD Kabini HDMI/DP Audio                                                                          | 90        | 1.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 88        | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 87        | 1.55%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 81        | 1.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 79        | 1.4%    |
| Intel Comet Lake PCH cAVS                                                                         | 71        | 1.26%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 71        | 1.26%   |
| Intel CM238 HD Audio Controller                                                                   | 70        | 1.24%   |
| AMD High Definition Audio Controller                                                              | 69        | 1.23%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 68        | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 64        | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 59        | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 59        | 1.05%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 54        | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 52        | 0.92%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 48        | 0.85%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 47        | 0.83%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 41        | 0.73%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 40        | 0.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 37        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 612       | 26.87%  |
| SK hynix            | 557       | 24.45%  |
| Micron Technology   | 303       | 13.3%   |
| Crucial             | 185       | 8.12%   |
| Unknown             | 157       | 6.89%   |
| Kingston            | 151       | 6.63%   |
| Corsair             | 54        | 2.37%   |
| Ramaxel Technology  | 49        | 2.15%   |
| Elpida              | 39        | 1.71%   |
| Nanya Technology    | 35        | 1.54%   |
| A-DATA Technology   | 26        | 1.14%   |
| Unknown (ABCD)      | 20        | 0.88%   |
| Unknown             | 15        | 0.66%   |
| Toshiba             | 6         | 0.26%   |
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
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 48        | 1.98%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 33        | 1.36%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 25        | 1.03%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 1.03%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 25        | 1.03%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.99%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 23        | 0.95%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 22        | 0.91%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 21        | 0.87%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 21        | 0.87%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 20        | 0.83%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 20        | 0.83%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.79%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.79%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 0.74%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 16        | 0.66%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 15        | 0.62%   |
| Unknown                                                          | 15        | 0.62%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.58%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 14        | 0.58%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 14        | 0.58%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.58%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 14        | 0.58%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 0.58%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.58%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 13        | 0.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 13        | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 13        | 0.54%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.54%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s          | 13        | 0.54%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 12        | 0.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 11        | 0.45%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s              | 10        | 0.41%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 10        | 0.41%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.41%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 10        | 0.41%   |
| Crucial RAM CT102464BF160B.M16 8GB SODIMM DDR3 1600MT/s          | 10        | 0.41%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 9         | 0.37%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.37%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 854       | 43.62%  |
| DDR3    | 644       | 32.89%  |
| DDR2    | 111       | 5.67%   |
| LPDDR4  | 110       | 5.62%   |
| LPDDR3  | 101       | 5.16%   |
| SDRAM   | 53        | 2.71%   |
| DDR5    | 33        | 1.69%   |
| LPDDR5  | 20        | 1.02%   |
| Unknown | 14        | 0.72%   |
| DDR     | 10        | 0.51%   |
| DRAM    | 8         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1678      | 86.27%  |
| Row Of Chips | 214       | 11%     |
| Unknown      | 24        | 1.23%   |
| Chip         | 19        | 0.98%   |
| DIMM         | 10        | 0.51%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 826       | 38.6%   |
| 4096  | 610       | 28.5%   |
| 2048  | 281       | 13.13%  |
| 16384 | 271       | 12.66%  |
| 1024  | 84        | 3.93%   |
| 32768 | 55        | 2.57%   |
| 512   | 12        | 0.56%   |
| 256   | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 462       | 22%     |
| 2667    | 416       | 19.81%  |
| 3200    | 312       | 14.86%  |
| 2400    | 152       | 7.24%   |
| 2133    | 119       | 5.67%   |
| 1334    | 91        | 4.33%   |
| 1333    | 64        | 3.05%   |
| 667     | 59        | 2.81%   |
| 1867    | 48        | 2.29%   |
| 4267    | 46        | 2.19%   |
| Unknown | 42        | 2%      |
| 1067    | 40        | 1.9%    |
| 4800    | 32        | 1.52%   |
| 800     | 28        | 1.33%   |
| 4199    | 25        | 1.19%   |
| 3266    | 25        | 1.19%   |
| 6400    | 21        | 1%      |
| 2048    | 21        | 1%      |
| 1066    | 18        | 0.86%   |
| 4266    | 14        | 0.67%   |
| 975     | 11        | 0.52%   |
| 533     | 10        | 0.48%   |
| 1866    | 8         | 0.38%   |
| 3733    | 6         | 0.29%   |
| 8400    | 5         | 0.24%   |
| 3000    | 3         | 0.14%   |
| 1639    | 3         | 0.14%   |
| 400     | 3         | 0.14%   |
| 333     | 3         | 0.14%   |
| 5600    | 2         | 0.1%    |
| 2933    | 2         | 0.1%    |
| 1776    | 2         | 0.1%    |
| 933     | 2         | 0.1%    |
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
| Canon                 | 10        | 32.26%  |
| Hewlett-Packard       | 6         | 19.35%  |
| Brother Industries    | 4         | 12.9%   |
| Samsung Electronics   | 3         | 9.68%   |
| Lexmark International | 3         | 9.68%   |
| Prolific Technology   | 2         | 6.45%   |
| STMicroelectronics    | 1         | 3.23%   |
| Seiko Epson           | 1         | 3.23%   |
| Kyocera               | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon PIXMA MG3600 Series                                 | 3         | 9.38%   |
| Prolific PL2305 Parallel Port                             | 2         | 6.25%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.13%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F    | 1         | 3.13%   |
| Samsung CLX-6260 Series                                   | 1         | 3.13%   |
| Samsung CLP-300 Series                                    | 1         | 3.13%   |
| Samsung C43x Series                                       | 1         | 3.13%   |
| Lexmark International MS610de                             | 1         | 3.13%   |
| Lexmark International C544                                | 1         | 3.13%   |
| Lexmark International 640 Series                          | 1         | 3.13%   |
| Kyocera FS-1041                                           | 1         | 3.13%   |
| HP Officejet 4630 series                                  | 1         | 3.13%   |
| HP LaserJet P2015 series                                  | 1         | 3.13%   |
| HP LaserJet 1010                                          | 1         | 3.13%   |
| HP ENVY Photo 6200 series                                 | 1         | 3.13%   |
| HP ENVY 4520 series                                       | 1         | 3.13%   |
| HP Deskjet 2540 series                                    | 1         | 3.13%   |
| Canon SELPHY CP400                                        | 1         | 3.13%   |
| Canon PIXMA MX490 Series                                  | 1         | 3.13%   |
| Canon PIXMA MG2500 Series                                 | 1         | 3.13%   |
| Canon MF4360-4390                                         | 1         | 3.13%   |
| Canon LiDE 400                                            | 1         | 3.13%   |
| Canon LiDE 300                                            | 1         | 3.13%   |
| Canon iX6500 series                                       | 1         | 3.13%   |
| Canon iP4800 series                                       | 1         | 3.13%   |
| Brother PT-9500PC                                         | 1         | 3.13%   |
| Brother MFC-J4540DW                                       | 1         | 3.13%   |
| Brother DCP-L3510CDW                                      | 1         | 3.13%   |
| Brother DCP-7025 Printer                                  | 1         | 3.13%   |

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
| Chicony Electronics                    | 867       | 25.55%  |
| Microdia                               | 381       | 11.23%  |
| IMC Networks                           | 297       | 8.75%   |
| Realtek Semiconductor                  | 289       | 8.52%   |
| Sunplus Innovation Technology          | 189       | 5.57%   |
| Bison Electronics                      | 154       | 4.54%   |
| Cheng Uei Precision Industry (Foxlink) | 136       | 4.01%   |
| Quanta                                 | 134       | 3.95%   |
| Suyin                                  | 109       | 3.21%   |
| Acer                                   | 98        | 2.89%   |
| Lite-On Technology                     | 92        | 2.71%   |
| Apple                                  | 83        | 2.45%   |
| Syntek                                 | 77        | 2.27%   |
| Silicon Motion                         | 61        | 1.8%    |
| Logitech                               | 51        | 1.5%    |
| Alcor Micro                            | 49        | 1.44%   |
| Ricoh                                  | 45        | 1.33%   |
| Lenovo                                 | 40        | 1.18%   |
| Luxvisions Innotech Limited            | 34        | 1%      |
| Samsung Electronics                    | 19        | 0.56%   |
| ALi                                    | 16        | 0.47%   |
| Z-Star Microelectronics                | 15        | 0.44%   |
| Sonix Technology                       | 15        | 0.44%   |
| Microsoft                              | 12        | 0.35%   |
| Primax Electronics                     | 11        | 0.32%   |
| Importek                               | 8         | 0.24%   |
| SunplusIT                              | 7         | 0.21%   |
| Sunplus Technology                     | 7         | 0.21%   |
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
| Microdia Integrated_Webcam_HD                           | 193       | 5.65%   |
| Chicony Integrated Camera                               | 155       | 4.54%   |
| Realtek Integrated_Webcam_HD                            | 103       | 3.02%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 85        | 2.49%   |
| IMC Networks Integrated Camera                          | 81        | 2.37%   |
| Sunplus Integrated_Webcam_HD                            | 75        | 2.2%    |
| Chicony HD WebCam                                       | 64        | 1.87%   |
| Chicony USB2.0 Camera                                   | 40        | 1.17%   |
| Microdia Integrated Webcam                              | 38        | 1.11%   |
| Chicony TOSHIBA Web Camera - HD                         | 38        | 1.11%   |
| Chicony HP TrueVision HD Camera                         | 36        | 1.05%   |
| Lite-On Integrated Camera                               | 35        | 1.02%   |
| Bison Integrated Camera                                 | 33        | 0.97%   |
| Acer BisonCam,NB Pro                                    | 33        | 0.97%   |
| Syntek Integrated Camera                                | 31        | 0.91%   |
| Apple Built-in iSight                                   | 31        | 0.91%   |
| Chicony USB 2.0 Camera                                  | 30        | 0.88%   |
| Chicony HP HD Camera                                    | 30        | 0.88%   |
| Chicony HP Truevision HD                                | 28        | 0.82%   |
| Quanta HD User Facing                                   | 26        | 0.76%   |
| Chicony EasyCamera                                      | 26        | 0.76%   |
| Bison SunplusIT Integrated Camera                       | 26        | 0.76%   |
| Chicony VGA Webcam                                      | 25        | 0.73%   |
| Syntek Lenovo EasyCamera                                | 24        | 0.7%    |
| Realtek USB Camera                                      | 24        | 0.7%    |
| Chicony Integrated Camera (1280x720@30)                 | 24        | 0.7%    |
| Apple FaceTime HD Camera                                | 24        | 0.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                      | 21        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 20        | 0.59%   |
| Alcor Micro USB 2.0 Web Camera                          | 20        | 0.59%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 19        | 0.56%   |
| Lenovo Integrated Webcam [R5U877]                       | 19        | 0.56%   |
| Chicony HP Wide Vision HD Camera                        | 19        | 0.56%   |
| Chicony CNF9055 Toshiba Webcam                          | 19        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) Webcam           | 19        | 0.56%   |
| Acer Integrated Camera                                  | 19        | 0.56%   |
| Sunplus HD WebCam                                       | 18        | 0.53%   |
| Chicony HD User Facing                                  | 18        | 0.53%   |
| Suyin HP Truevision HD                                  | 17        | 0.5%    |
| Realtek Integrated Webcam HD                            | 17        | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 219       | 33.13%  |
| Synaptics                          | 160       | 24.21%  |
| Shenzhen Goodix Technology         | 106       | 16.04%  |
| Upek                               | 52        | 7.87%   |
| AuthenTec                          | 52        | 7.87%   |
| LighTuning Technology              | 31        | 4.69%   |
| Elan Microelectronics              | 22        | 3.33%   |
| STMicroelectronics                 | 14        | 2.12%   |
| Samsung Electronics                | 2         | 0.3%    |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.3%    |
| Focal-systems.Corp                 | 1         | 0.15%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 57        | 8.62%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 50        | 7.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 43        | 6.51%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 39        | 5.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 38        | 5.75%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 28        | 4.24%   |
| Shenzhen Goodix FingerPrint                                                | 28        | 4.24%   |
| Validity Sensors Synaptics WBDI                                            | 21        | 3.18%   |
| Shenzhen Goodix Fingerprint Reader                                         | 21        | 3.18%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 2.72%   |
| Validity Sensors VFS491                                                    | 17        | 2.57%   |
| AuthenTec AES2810                                                          | 15        | 2.27%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 2.27%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 14        | 2.12%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 14        | 2.12%   |
| STMicroelectronics Fingerprint Reader                                      | 14        | 2.12%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 14        | 2.12%   |
| Synaptics UWP WBDI                                                         | 13        | 1.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 13        | 1.97%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 1.66%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 11        | 1.66%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 11        | 1.66%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 11        | 1.66%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 10        | 1.51%   |
| Elan ELAN:Fingerprint                                                      | 10        | 1.51%   |
| Unknown                                                                    | 10        | 1.51%   |
| Elan ELAN:ARM-M4                                                           | 9         | 1.36%   |
| Synaptics WBDI Device                                                      | 8         | 1.21%   |
| Synaptics UWP WBDI Device                                                  | 8         | 1.21%   |
| Synaptics  WBDI                                                            | 8         | 1.21%   |
| Synaptics Fingerprint reader [HP G6]                                       | 8         | 1.21%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 7         | 1.06%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 1.06%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 1.06%   |
| AuthenTec AES1600                                                          | 6         | 0.91%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.76%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.76%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 5         | 0.76%   |
| Validity Sensors VFS Fingerprint sensor                                    | 4         | 0.61%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 4         | 0.61%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 182       | 53.06%  |
| Alcor Micro           | 74        | 21.57%  |
| Upek                  | 28        | 8.16%   |
| O2 Micro              | 24        | 7%      |
| Lenovo                | 24        | 7%      |
| Gemalto (was Gemplus) | 4         | 1.17%   |
| SCM Microsystems      | 3         | 0.87%   |
| Purism, SPC           | 1         | 0.29%   |
| Clay Logic            | 1         | 0.29%   |
| Chicony Electronics   | 1         | 0.29%   |
| Cherry                | 1         | 0.29%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 73        | 21.28%  |
| Broadcom BCM5880 Secure Applications Processor                               | 71        | 20.7%   |
| Broadcom 5880                                                                | 47        | 13.7%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 34        | 9.91%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 28        | 8.16%   |
| Broadcom 58200                                                               | 28        | 8.16%   |
| Lenovo Integrated Smart Card Reader                                          | 23        | 6.71%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 19        | 5.54%   |
| O2 Micro Oz776 SmartCard Reader                                              | 5         | 1.46%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.87%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 0.58%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.58%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.29%   |
| Purism, SPC Librem Key                                                       | 1         | 0.29%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.29%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.29%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.29%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.29%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.29%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.29%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2532      | 62.56%  |
| 1     | 1159      | 28.64%  |
| 2     | 303       | 7.49%   |
| 3     | 42        | 1.04%   |
| 4     | 5         | 0.12%   |
| 5     | 3         | 0.07%   |
| 8     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |
| 6     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 643       | 34.17%  |
| Graphics card            | 351       | 18.65%  |
| Chipcard                 | 313       | 16.63%  |
| Net/wireless             | 205       | 10.89%  |
| Multimedia controller    | 108       | 5.74%   |
| Communication controller | 42        | 2.23%   |
| Storage                  | 40        | 2.13%   |
| Camera                   | 39        | 2.07%   |
| Bluetooth                | 37        | 1.97%   |
| Sound                    | 22        | 1.17%   |
| Card reader              | 20        | 1.06%   |
| Net/ethernet             | 18        | 0.96%   |
| Modem                    | 16        | 0.85%   |
| Network                  | 8         | 0.43%   |
| Flash memory             | 8         | 0.43%   |
| Firewire controller      | 5         | 0.27%   |
| Storage/nvme             | 3         | 0.16%   |
| Unassigned class         | 2         | 0.11%   |
| Storage/ide              | 2         | 0.11%   |

