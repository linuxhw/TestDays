Linux in Estonia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Estonia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Estonia/Desktop/README.md) and [notebooks](/Location/Estonia/Notebook/README.md).

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

Total: 418

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | 8643 SMVB                   | Desktop     | [961a04643c](https://linux-hardware.org/?probe=961a04643c) | May 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| Microsoft     | Surface Book                | Tablet      | [7bb9611a98](https://linux-hardware.org/?probe=7bb9611a98) | May 21, 2023 |
| Lenovo        | ThinkPad L480 20LTSAK70R    | Notebook    | [551d238ad3](https://linux-hardware.org/?probe=551d238ad3) | May 16, 2023 |
| Notebook      | N150SD/N155SD               | Notebook    | [55f219bc3f](https://linux-hardware.org/?probe=55f219bc3f) | May 11, 2023 |
| ASUSTek       | N550JK                      | Notebook    | [a799667521](https://linux-hardware.org/?probe=a799667521) | May 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [fdaef83d1e](https://linux-hardware.org/?probe=fdaef83d1e) | Apr 23, 2023 |
| Lenovo        | ThinkStation D20 4158GK1    | Desktop     | [44d9536051](https://linux-hardware.org/?probe=44d9536051) | Apr 14, 2023 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [33e5d369a7](https://linux-hardware.org/?probe=33e5d369a7) | Apr 04, 2023 |
| HP            | 304Ah                       | Desktop     | [14d92e85a2](https://linux-hardware.org/?probe=14d92e85a2) | Apr 01, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [6694c9279d](https://linux-hardware.org/?probe=6694c9279d) | Mar 31, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [b06257fd9c](https://linux-hardware.org/?probe=b06257fd9c) | Mar 28, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [3a0d77d195](https://linux-hardware.org/?probe=3a0d77d195) | Mar 28, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [6b088adaf9](https://linux-hardware.org/?probe=6b088adaf9) | Mar 27, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [32afc6a4cf](https://linux-hardware.org/?probe=32afc6a4cf) | Mar 23, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4efbf8be88](https://linux-hardware.org/?probe=4efbf8be88) | Mar 23, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| GPD           | G1619-04                    | Notebook    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | 304Ah                       | Desktop     | [49adbe8acf](https://linux-hardware.org/?probe=49adbe8acf) | Mar 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [c87313bdd4](https://linux-hardware.org/?probe=c87313bdd4) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| Lenovo        | ThinkPad T540p 20BFS3BR0... | Notebook    | [6218acf76f](https://linux-hardware.org/?probe=6218acf76f) | Mar 12, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [ec707b621c](https://linux-hardware.org/?probe=ec707b621c) | Mar 05, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [36699f94c9](https://linux-hardware.org/?probe=36699f94c9) | Mar 05, 2023 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [396ad2d6aa](https://linux-hardware.org/?probe=396ad2d6aa) | Mar 04, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [6f09d6cd6c](https://linux-hardware.org/?probe=6f09d6cd6c) | Feb 05, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [07d496ada9](https://linux-hardware.org/?probe=07d496ada9) | Feb 04, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [82ce911f26](https://linux-hardware.org/?probe=82ce911f26) | Jan 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [2141789e3a](https://linux-hardware.org/?probe=2141789e3a) | Jan 14, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [f1c4c8b89e](https://linux-hardware.org/?probe=f1c4c8b89e) | Jan 13, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [8674044a95](https://linux-hardware.org/?probe=8674044a95) | Jan 13, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [ff12fe840d](https://linux-hardware.org/?probe=ff12fe840d) | Jan 12, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [146f307b8e](https://linux-hardware.org/?probe=146f307b8e) | Jan 10, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [aa21c2b75f](https://linux-hardware.org/?probe=aa21c2b75f) | Jan 06, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [efa2d6986f](https://linux-hardware.org/?probe=efa2d6986f) | Dec 28, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [4a85ebbc33](https://linux-hardware.org/?probe=4a85ebbc33) | Dec 26, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [70436ae3c3](https://linux-hardware.org/?probe=70436ae3c3) | Dec 15, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [4c5bac90eb](https://linux-hardware.org/?probe=4c5bac90eb) | Dec 15, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [2ace77f72c](https://linux-hardware.org/?probe=2ace77f72c) | Dec 14, 2022 |
| ASRock        | Z490M Pro4                  | Desktop     | [0b91c8c70f](https://linux-hardware.org/?probe=0b91c8c70f) | Dec 14, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | Notebook    | [d8b614d1ca](https://linux-hardware.org/?probe=d8b614d1ca) | Dec 12, 2022 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [280f28a486](https://linux-hardware.org/?probe=280f28a486) | Dec 11, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1f904e68af](https://linux-hardware.org/?probe=1f904e68af) | Nov 29, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [6f3bf3fe46](https://linux-hardware.org/?probe=6f3bf3fe46) | Nov 28, 2022 |
| ASUSTek       | N53Jf                       | Notebook    | [e4dc6e5cd9](https://linux-hardware.org/?probe=e4dc6e5cd9) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [b792955af6](https://linux-hardware.org/?probe=b792955af6) | Nov 27, 2022 |
| Lenovo        | ThinkPad X240 20AMA0W706    | Notebook    | [033e206fab](https://linux-hardware.org/?probe=033e206fab) | Nov 25, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| Valve         | Jupiter                     | Notebook    | [0e77de9dba](https://linux-hardware.org/?probe=0e77de9dba) | Nov 20, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [96d82e20c4](https://linux-hardware.org/?probe=96d82e20c4) | Nov 19, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [f5fd517d69](https://linux-hardware.org/?probe=f5fd517d69) | Nov 19, 2022 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [b8dae15ebf](https://linux-hardware.org/?probe=b8dae15ebf) | Nov 09, 2022 |
| Alienware     | 17                          | Notebook    | [91358a0bec](https://linux-hardware.org/?probe=91358a0bec) | Nov 09, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [c479fc2cea](https://linux-hardware.org/?probe=c479fc2cea) | Nov 06, 2022 |
| HP            | Unknown                     | Notebook    | [aa28b92716](https://linux-hardware.org/?probe=aa28b92716) | Nov 06, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X2S... | Notebook    | [36d7199821](https://linux-hardware.org/?probe=36d7199821) | Nov 01, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [8eb1316a14](https://linux-hardware.org/?probe=8eb1316a14) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [81374a561c](https://linux-hardware.org/?probe=81374a561c) | Oct 31, 2022 |
| ASUSTek       | M4A78                       | Desktop     | [d88d101a3c](https://linux-hardware.org/?probe=d88d101a3c) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | Notebook    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [5405caf9dc](https://linux-hardware.org/?probe=5405caf9dc) | Oct 28, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [5548027da3](https://linux-hardware.org/?probe=5548027da3) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [26d539c606](https://linux-hardware.org/?probe=26d539c606) | Oct 26, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [dbb72f4c00](https://linux-hardware.org/?probe=dbb72f4c00) | Oct 26, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8b459ac79b](https://linux-hardware.org/?probe=8b459ac79b) | Oct 20, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| ASRock        | B460 Steel Legend           | Desktop     | [ca98840e23](https://linux-hardware.org/?probe=ca98840e23) | Oct 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7a1b08d912](https://linux-hardware.org/?probe=7a1b08d912) | Oct 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3f808f36a0](https://linux-hardware.org/?probe=3f808f36a0) | Oct 13, 2022 |
| Unknown       | Seagate Personal Cloud (... | Desktop     | [40ea197650](https://linux-hardware.org/?probe=40ea197650) | Oct 09, 2022 |
| Dell          | Latitude 7390               | Notebook    | [268add52b3](https://linux-hardware.org/?probe=268add52b3) | Sep 19, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9a7d178f1b](https://linux-hardware.org/?probe=9a7d178f1b) | Sep 15, 2022 |
| ASUSTek       | 1225C                       | Notebook    | [91f049c977](https://linux-hardware.org/?probe=91f049c977) | Sep 09, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [d805aa67b2](https://linux-hardware.org/?probe=d805aa67b2) | Sep 09, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [f6c6b627f7](https://linux-hardware.org/?probe=f6c6b627f7) | Aug 28, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [7332174749](https://linux-hardware.org/?probe=7332174749) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [8c56960243](https://linux-hardware.org/?probe=8c56960243) | Aug 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| Valve         | Jupiter                     | Notebook    | [ced35212a7](https://linux-hardware.org/?probe=ced35212a7) | Aug 07, 2022 |
| MSI           | MAG B460M BAZOOKA           | Desktop     | [5dae076f42](https://linux-hardware.org/?probe=5dae076f42) | Jul 27, 2022 |
| ECS           | G41T-M7                     | Desktop     | [a531a754a8](https://linux-hardware.org/?probe=a531a754a8) | Jul 23, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | 3646h                       | Desktop     | [88b38da161](https://linux-hardware.org/?probe=88b38da161) | Jul 11, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [cdb4149eba](https://linux-hardware.org/?probe=cdb4149eba) | Jun 27, 2022 |
| MSI           | Z77A-G41                    | Desktop     | [d0f55f3c0b](https://linux-hardware.org/?probe=d0f55f3c0b) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [d8f9374e6c](https://linux-hardware.org/?probe=d8f9374e6c) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [00495646c1](https://linux-hardware.org/?probe=00495646c1) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [208e447fe1](https://linux-hardware.org/?probe=208e447fe1) | Jun 17, 2022 |
| ASUSTek       | E502NA                      | Notebook    | [d65dd8fc52](https://linux-hardware.org/?probe=d65dd8fc52) | Jun 09, 2022 |
| ASUSTek       | E502NA                      | Notebook    | [d3d64dcb5b](https://linux-hardware.org/?probe=d3d64dcb5b) | Jun 09, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [a068a18649](https://linux-hardware.org/?probe=a068a18649) | Jun 08, 2022 |
| Dell          | 088DT1 A00                  | Desktop     | [b585cb1f70](https://linux-hardware.org/?probe=b585cb1f70) | Jun 07, 2022 |
| HP            | Presario CQ57               | Notebook    | [9f87592293](https://linux-hardware.org/?probe=9f87592293) | Jun 02, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [714722d24b](https://linux-hardware.org/?probe=714722d24b) | Jun 01, 2022 |
| Intel         | DP67BG AAG10491-305         | Desktop     | [966ab11802](https://linux-hardware.org/?probe=966ab11802) | May 31, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [49223fe44b](https://linux-hardware.org/?probe=49223fe44b) | May 21, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [40cb336486](https://linux-hardware.org/?probe=40cb336486) | May 21, 2022 |
| Gigabyte      | H55M-S2                     | Desktop     | [4d68acc78c](https://linux-hardware.org/?probe=4d68acc78c) | May 18, 2022 |
| Dell          | Latitude 5520               | Notebook    | [320ed1c4fc](https://linux-hardware.org/?probe=320ed1c4fc) | May 17, 2022 |
| Dell          | Latitude 5520               | Notebook    | [18823f33fb](https://linux-hardware.org/?probe=18823f33fb) | May 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [5107890ffd](https://linux-hardware.org/?probe=5107890ffd) | May 15, 2022 |
| Lenovo        | ThinkCentre M58 7360WQK     | Desktop     | [9002375046](https://linux-hardware.org/?probe=9002375046) | May 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0773b6244e](https://linux-hardware.org/?probe=0773b6244e) | May 11, 2022 |
| Gigabyte      | B560 HD3                    | Desktop     | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| Lenovo        | ThinkPad T490s 20NX000AM... | Notebook    | [f07b38c5f9](https://linux-hardware.org/?probe=f07b38c5f9) | May 10, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| mPTech        | ARC 11.6 128GB HD           | Notebook    | [aafa7cb1cb](https://linux-hardware.org/?probe=aafa7cb1cb) | May 07, 2022 |
| Dell          | Precision 7540              | Notebook    | [8b1b7dd8da](https://linux-hardware.org/?probe=8b1b7dd8da) | Apr 30, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [a10fb9fe10](https://linux-hardware.org/?probe=a10fb9fe10) | Apr 23, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [b963507390](https://linux-hardware.org/?probe=b963507390) | Apr 19, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [fff8ad361e](https://linux-hardware.org/?probe=fff8ad361e) | Apr 19, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [d948d987b4](https://linux-hardware.org/?probe=d948d987b4) | Apr 18, 2022 |
| Framework     | Laptop                      | Notebook    | [d4a02dfec9](https://linux-hardware.org/?probe=d4a02dfec9) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | Notebook    | [8444b44333](https://linux-hardware.org/?probe=8444b44333) | Apr 04, 2022 |
| Lenovo        | ThinkPad X260 20F5S84400    | Notebook    | [69e1c25b4c](https://linux-hardware.org/?probe=69e1c25b4c) | Apr 03, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [8af8994f80](https://linux-hardware.org/?probe=8af8994f80) | Apr 02, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [ccf4457b51](https://linux-hardware.org/?probe=ccf4457b51) | Mar 28, 2022 |
| HP            | 18E9                        | Desktop     | [5a223b8722](https://linux-hardware.org/?probe=5a223b8722) | Mar 23, 2022 |
| Dell          | Latitude 5520               | Notebook    | [a8e30b61c6](https://linux-hardware.org/?probe=a8e30b61c6) | Mar 21, 2022 |
| Dell          | Latitude 5520               | Notebook    | [02b408b5f6](https://linux-hardware.org/?probe=02b408b5f6) | Mar 21, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [7fb04e6c7d](https://linux-hardware.org/?probe=7fb04e6c7d) | Mar 03, 2022 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [0f27bdf5a8](https://linux-hardware.org/?probe=0f27bdf5a8) | Mar 02, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [d34e3c79a0](https://linux-hardware.org/?probe=d34e3c79a0) | Mar 01, 2022 |
| Lenovo        | ThinkPad X220 429136G       | Notebook    | [324d66c0fc](https://linux-hardware.org/?probe=324d66c0fc) | Feb 23, 2022 |
| ECS           | G41T-M7                     | Desktop     | [c4aca5bc12](https://linux-hardware.org/?probe=c4aca5bc12) | Feb 20, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [5f3cd9e8d5](https://linux-hardware.org/?probe=5f3cd9e8d5) | Feb 16, 2022 |
| MSI           | B150M PRO-VD                | Desktop     | [b46943492e](https://linux-hardware.org/?probe=b46943492e) | Feb 15, 2022 |
| HP            | 304Ah                       | Desktop     | [078b605c39](https://linux-hardware.org/?probe=078b605c39) | Feb 09, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96f97ed2d6](https://linux-hardware.org/?probe=96f97ed2d6) | Jan 23, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [c9b246d9a8](https://linux-hardware.org/?probe=c9b246d9a8) | Jan 12, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [49234f883d](https://linux-hardware.org/?probe=49234f883d) | Jan 12, 2022 |
| Huanan        | X79 V2.47                   | Desktop     | [a27e7cdbef](https://linux-hardware.org/?probe=a27e7cdbef) | Jan 09, 2022 |
| Dell          | 0KH290                      | Desktop     | [e8c0e16dfb](https://linux-hardware.org/?probe=e8c0e16dfb) | Dec 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [ca26ae6ff8](https://linux-hardware.org/?probe=ca26ae6ff8) | Dec 22, 2021 |
| ASUSTek       | K52Jc                       | Notebook    | [f6789bc7ac](https://linux-hardware.org/?probe=f6789bc7ac) | Dec 18, 2021 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [5c0550c1e8](https://linux-hardware.org/?probe=5c0550c1e8) | Dec 09, 2021 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [db552307a3](https://linux-hardware.org/?probe=db552307a3) | Dec 07, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [142cab14c6](https://linux-hardware.org/?probe=142cab14c6) | Dec 02, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [0b2751c5c1](https://linux-hardware.org/?probe=0b2751c5c1) | Dec 02, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [dbbe56da66](https://linux-hardware.org/?probe=dbbe56da66) | Dec 01, 2021 |
| Gigabyte      | X570 UD                     | Desktop     | [79c117738b](https://linux-hardware.org/?probe=79c117738b) | Dec 01, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [dc981a1604](https://linux-hardware.org/?probe=dc981a1604) | Nov 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [362a840c47](https://linux-hardware.org/?probe=362a840c47) | Nov 20, 2021 |
| Alienware     | 17                          | Notebook    | [d3460bdfd1](https://linux-hardware.org/?probe=d3460bdfd1) | Nov 20, 2021 |
| Dell          | Precision 5550              | Notebook    | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [6eb5a4107e](https://linux-hardware.org/?probe=6eb5a4107e) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [a922d5f3fc](https://linux-hardware.org/?probe=a922d5f3fc) | Nov 10, 2021 |
| ZOTAC         | ZBOX-CA621NANO              | Mini pc     | [e540507afc](https://linux-hardware.org/?probe=e540507afc) | Nov 10, 2021 |
| Intel         | D33217GKE G69901-205        | Desktop     | [dd1ddaf74f](https://linux-hardware.org/?probe=dd1ddaf74f) | Nov 09, 2021 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [201bc8d044](https://linux-hardware.org/?probe=201bc8d044) | Oct 17, 2021 |
| Getac         | B300G4                      | Notebook    | [78b2fab1e0](https://linux-hardware.org/?probe=78b2fab1e0) | Oct 17, 2021 |
| HP            | Pavilion dv7                | Notebook    | [6c14033e55](https://linux-hardware.org/?probe=6c14033e55) | Oct 16, 2021 |
| HP            | Pavilion dv7                | Notebook    | [f93789f29a](https://linux-hardware.org/?probe=f93789f29a) | Oct 16, 2021 |
| Acer          | Extensa 5620                | Notebook    | [5cae4fe0fa](https://linux-hardware.org/?probe=5cae4fe0fa) | Oct 11, 2021 |
| HP            | EliteBook x360 1030 G2      | Convertible | [95d389bfe5](https://linux-hardware.org/?probe=95d389bfe5) | Oct 07, 2021 |
| Huanan        | X79 V2.47                   | Desktop     | [326b3f5892](https://linux-hardware.org/?probe=326b3f5892) | Oct 07, 2021 |
| Huanan        | X79 V2.47                   | Desktop     | [c2c6287186](https://linux-hardware.org/?probe=c2c6287186) | Oct 07, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [9cd559605c](https://linux-hardware.org/?probe=9cd559605c) | Sep 27, 2021 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [68f4ff7431](https://linux-hardware.org/?probe=68f4ff7431) | Sep 27, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | Notebook    | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [d339553d59](https://linux-hardware.org/?probe=d339553d59) | Sep 19, 2021 |
| Prestigio     | PNT10131DEDB                | Convertible | [39dc1df1df](https://linux-hardware.org/?probe=39dc1df1df) | Sep 18, 2021 |
| Alienware     | 17                          | Notebook    | [c97b201719](https://linux-hardware.org/?probe=c97b201719) | Sep 17, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [47fb03fde8](https://linux-hardware.org/?probe=47fb03fde8) | Sep 17, 2021 |
| MSI           | MS-B901                     | All in one  | [282992f343](https://linux-hardware.org/?probe=282992f343) | Sep 14, 2021 |
| MSI           | MS-B901                     | All in one  | [3a288bcc81](https://linux-hardware.org/?probe=3a288bcc81) | Sep 14, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4f393c5347](https://linux-hardware.org/?probe=4f393c5347) | Sep 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [1240138d48](https://linux-hardware.org/?probe=1240138d48) | Sep 11, 2021 |
| ASUSTek       | UX530UX                     | Notebook    | [c713dcf9e2](https://linux-hardware.org/?probe=c713dcf9e2) | Sep 08, 2021 |
| ASUSTek       | X510UA                      | Notebook    | [0a8045cc4f](https://linux-hardware.org/?probe=0a8045cc4f) | Sep 05, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [210ca88228](https://linux-hardware.org/?probe=210ca88228) | Aug 30, 2021 |
| Lenovo        | ThinkPad X201 3680CG7       | Notebook    | [9565bae9c3](https://linux-hardware.org/?probe=9565bae9c3) | Aug 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [75619baa6e](https://linux-hardware.org/?probe=75619baa6e) | Aug 29, 2021 |
| ASUSTek       | X550ZA                      | Notebook    | [0a21d3b326](https://linux-hardware.org/?probe=0a21d3b326) | Aug 27, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [bf81c78371](https://linux-hardware.org/?probe=bf81c78371) | Aug 26, 2021 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [b40ad47903](https://linux-hardware.org/?probe=b40ad47903) | Aug 25, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [e5d8500e1c](https://linux-hardware.org/?probe=e5d8500e1c) | Aug 21, 2021 |
| Lenovo        | ThinkPad T510 4384GFG       | Notebook    | [67b971a2dd](https://linux-hardware.org/?probe=67b971a2dd) | Aug 21, 2021 |
| Lenovo        | ThinkPad W541 20EF001TMS    | Notebook    | [bc2879c7e5](https://linux-hardware.org/?probe=bc2879c7e5) | Aug 19, 2021 |
| Lenovo        | ThinkPad 20AY001DMH         | Notebook    | [d3f7b62a42](https://linux-hardware.org/?probe=d3f7b62a42) | Aug 19, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [559742f4d7](https://linux-hardware.org/?probe=559742f4d7) | Aug 19, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [f21459caa1](https://linux-hardware.org/?probe=f21459caa1) | Aug 19, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [5f9d1cd1a6](https://linux-hardware.org/?probe=5f9d1cd1a6) | Aug 18, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d28cc83aed](https://linux-hardware.org/?probe=d28cc83aed) | Aug 17, 2021 |
| Dell          | 0NW6H5 A00                  | Desktop     | [be5db43316](https://linux-hardware.org/?probe=be5db43316) | Aug 17, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [0ce69e02fa](https://linux-hardware.org/?probe=0ce69e02fa) | Aug 17, 2021 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [286d06cd5e](https://linux-hardware.org/?probe=286d06cd5e) | Aug 15, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [fcd91a58e2](https://linux-hardware.org/?probe=fcd91a58e2) | Aug 13, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [b2db3ea0a9](https://linux-hardware.org/?probe=b2db3ea0a9) | Aug 10, 2021 |
| Gigabyte      | B250M-D2V-CF                | Desktop     | [c086b1441c](https://linux-hardware.org/?probe=c086b1441c) | Aug 09, 2021 |
| HP            | Pavilion dv7                | Notebook    | [a56935a751](https://linux-hardware.org/?probe=a56935a751) | Aug 09, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2a9fe5f63c](https://linux-hardware.org/?probe=2a9fe5f63c) | Jul 31, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c5dccfd22](https://linux-hardware.org/?probe=1c5dccfd22) | Jul 31, 2021 |
| MSI           | GP62M 7RDX                  | Notebook    | [f02c96473f](https://linux-hardware.org/?probe=f02c96473f) | Jul 30, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [19a4054ab4](https://linux-hardware.org/?probe=19a4054ab4) | Jul 28, 2021 |
| Dell          | Inspiron 15-3567            | Notebook    | [bc64d314a1](https://linux-hardware.org/?probe=bc64d314a1) | Jul 28, 2021 |
| ASUSTek       | M3N78                       | Desktop     | [810e386d8b](https://linux-hardware.org/?probe=810e386d8b) | Jul 26, 2021 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [4f26f93184](https://linux-hardware.org/?probe=4f26f93184) | Jul 26, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [932c4de6ce](https://linux-hardware.org/?probe=932c4de6ce) | Jul 18, 2021 |
| Lenovo        | ThinkPad T440 20B60061MD    | Notebook    | [7207e6aa0f](https://linux-hardware.org/?probe=7207e6aa0f) | Jul 08, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [a47fb764b4](https://linux-hardware.org/?probe=a47fb764b4) | Jul 01, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [e9cd0640f7](https://linux-hardware.org/?probe=e9cd0640f7) | Jun 30, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a01d3d232](https://linux-hardware.org/?probe=7a01d3d232) | Jun 28, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [c42e493962](https://linux-hardware.org/?probe=c42e493962) | Jun 26, 2021 |
| ASUSTek       | N3050I-C                    | Desktop     | [9834731c15](https://linux-hardware.org/?probe=9834731c15) | Jun 26, 2021 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [d96aea9f90](https://linux-hardware.org/?probe=d96aea9f90) | Jun 26, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [cb4242a344](https://linux-hardware.org/?probe=cb4242a344) | Jun 15, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [7bf0e678ea](https://linux-hardware.org/?probe=7bf0e678ea) | Jun 13, 2021 |
| Lenovo        | ThinkPad T450s 20BWS1RG0... | Notebook    | [79d386a567](https://linux-hardware.org/?probe=79d386a567) | Jun 08, 2021 |
| Dell          | Latitude 5511               | Notebook    | [933fb253d4](https://linux-hardware.org/?probe=933fb253d4) | Jun 07, 2021 |
| Dell          | Latitude 5511               | Notebook    | [7b5e6276c0](https://linux-hardware.org/?probe=7b5e6276c0) | Jun 07, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6a7fe6469a](https://linux-hardware.org/?probe=6a7fe6469a) | Jun 06, 2021 |
| Timi          | RedmiBook 14 II             | Notebook    | [8700a7eaed](https://linux-hardware.org/?probe=8700a7eaed) | May 31, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1ba665b0b3](https://linux-hardware.org/?probe=1ba665b0b3) | May 24, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [3ae2f83c9f](https://linux-hardware.org/?probe=3ae2f83c9f) | May 23, 2021 |
| Dell          | G5 5587                     | Notebook    | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| Dell          | Precision 5530              | Notebook    | [aa0aa77e62](https://linux-hardware.org/?probe=aa0aa77e62) | May 16, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6f3d7a9d3f](https://linux-hardware.org/?probe=6f3d7a9d3f) | May 15, 2021 |
| Dell          | Vostro V131                 | Notebook    | [43fe3f190f](https://linux-hardware.org/?probe=43fe3f190f) | May 14, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [426f99f758](https://linux-hardware.org/?probe=426f99f758) | May 14, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [fe95dd9355](https://linux-hardware.org/?probe=fe95dd9355) | May 11, 2021 |
| Dell          | System Inspiron N7110       | Notebook    | [f5f418c337](https://linux-hardware.org/?probe=f5f418c337) | May 02, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [1bbe4079c5](https://linux-hardware.org/?probe=1bbe4079c5) | Apr 27, 2021 |
| HP            | Compaq nx6120 (PV170PA#U... | Notebook    | [5f105dda68](https://linux-hardware.org/?probe=5f105dda68) | Apr 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f84cf26650](https://linux-hardware.org/?probe=f84cf26650) | Apr 10, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [a677fe0972](https://linux-hardware.org/?probe=a677fe0972) | Apr 08, 2021 |
| MSI           | B250M PRO-VD                | Desktop     | [20ff770033](https://linux-hardware.org/?probe=20ff770033) | Apr 07, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ed6b3b5754](https://linux-hardware.org/?probe=ed6b3b5754) | Apr 04, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [218092e59f](https://linux-hardware.org/?probe=218092e59f) | Apr 03, 2021 |
| Lenovo        | Y50-70 20378                | Notebook    | [18ec5d54a4](https://linux-hardware.org/?probe=18ec5d54a4) | Apr 02, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [6e6dc77b21](https://linux-hardware.org/?probe=6e6dc77b21) | Mar 29, 2021 |
| Samsung       | R410                        | Notebook    | [331d909654](https://linux-hardware.org/?probe=331d909654) | Mar 27, 2021 |
| ASUSTek       | P5LD2                       | Desktop     | [72b40a39d4](https://linux-hardware.org/?probe=72b40a39d4) | Mar 25, 2021 |
| Samsung       | R410                        | Notebook    | [5aa6fee818](https://linux-hardware.org/?probe=5aa6fee818) | Mar 25, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f555918663](https://linux-hardware.org/?probe=f555918663) | Mar 24, 2021 |
| Samsung       | R410                        | Notebook    | [d3f94bcc8c](https://linux-hardware.org/?probe=d3f94bcc8c) | Mar 24, 2021 |
| OEM           | Intel H81                   | Desktop     | [385b6ee448](https://linux-hardware.org/?probe=385b6ee448) | Mar 19, 2021 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [013a785195](https://linux-hardware.org/?probe=013a785195) | Mar 18, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [fb33c2e9b9](https://linux-hardware.org/?probe=fb33c2e9b9) | Mar 17, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9b991380f9](https://linux-hardware.org/?probe=9b991380f9) | Mar 17, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [273fba9fd2](https://linux-hardware.org/?probe=273fba9fd2) | Mar 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [75a661f9f8](https://linux-hardware.org/?probe=75a661f9f8) | Mar 14, 2021 |
| Notebook      | W35xSS_370SS                | Notebook    | [0e98472f08](https://linux-hardware.org/?probe=0e98472f08) | Mar 02, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [ff698cacf3](https://linux-hardware.org/?probe=ff698cacf3) | Feb 27, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [116202ee88](https://linux-hardware.org/?probe=116202ee88) | Feb 27, 2021 |
| Lenovo        | ThinkPad T61 766112G        | Notebook    | [04ec7d5efd](https://linux-hardware.org/?probe=04ec7d5efd) | Feb 25, 2021 |
| Acer          | Aspire V5-572P              | Notebook    | [61834c786c](https://linux-hardware.org/?probe=61834c786c) | Feb 24, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [4c935ce981](https://linux-hardware.org/?probe=4c935ce981) | Feb 18, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [69090d5f4c](https://linux-hardware.org/?probe=69090d5f4c) | Feb 17, 2021 |
| MSI           | MS-7267                     | Desktop     | [b987c1ad14](https://linux-hardware.org/?probe=b987c1ad14) | Feb 15, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [e1dc5a8ea7](https://linux-hardware.org/?probe=e1dc5a8ea7) | Feb 14, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [d3004980ee](https://linux-hardware.org/?probe=d3004980ee) | Feb 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [8652b51903](https://linux-hardware.org/?probe=8652b51903) | Jan 20, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [77be7c1164](https://linux-hardware.org/?probe=77be7c1164) | Jan 18, 2021 |
| HP            | EliteBook 840 G5            | Notebook    | [59aaeda6a9](https://linux-hardware.org/?probe=59aaeda6a9) | Dec 28, 2020 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [81daeffb49](https://linux-hardware.org/?probe=81daeffb49) | Dec 28, 2020 |
| MSI           | Z77A-G41                    | Desktop     | [171be87aa0](https://linux-hardware.org/?probe=171be87aa0) | Dec 27, 2020 |
| Timi          | RedmiBook 16                | Notebook    | [34bc3ceb48](https://linux-hardware.org/?probe=34bc3ceb48) | Dec 24, 2020 |
| MSI           | GT70 2OC/2OD                | Notebook    | [e52bbc40aa](https://linux-hardware.org/?probe=e52bbc40aa) | Dec 19, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [95355fcff6](https://linux-hardware.org/?probe=95355fcff6) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 64665DG        | Notebook    | [3ee030e6ac](https://linux-hardware.org/?probe=3ee030e6ac) | Dec 17, 2020 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [9651814a46](https://linux-hardware.org/?probe=9651814a46) | Dec 08, 2020 |
| MSI           | H81I                        | Desktop     | [772ce7ff24](https://linux-hardware.org/?probe=772ce7ff24) | Dec 03, 2020 |
| MSI           | Boston                      | Desktop     | [9843e15faa](https://linux-hardware.org/?probe=9843e15faa) | Dec 01, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [07c05e281b](https://linux-hardware.org/?probe=07c05e281b) | Nov 29, 2020 |
| HP            | ENVY Laptop 13-ah0xxx       | Notebook    | [4defcea6f8](https://linux-hardware.org/?probe=4defcea6f8) | Nov 24, 2020 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [1280ebbedf](https://linux-hardware.org/?probe=1280ebbedf) | Nov 17, 2020 |
| Intel         | D425KT AAE93083-400         | Mini pc     | [e1f6c727d9](https://linux-hardware.org/?probe=e1f6c727d9) | Oct 14, 2020 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [f61cacc391](https://linux-hardware.org/?probe=f61cacc391) | Oct 05, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [ed0e6634d4](https://linux-hardware.org/?probe=ed0e6634d4) | Sep 29, 2020 |
| HP            | EliteBook 745 G5            | Notebook    | [e9d2889a6d](https://linux-hardware.org/?probe=e9d2889a6d) | Sep 28, 2020 |
| MSI           | X470 GAMING PRO             | Desktop     | [6b818c1352](https://linux-hardware.org/?probe=6b818c1352) | Sep 28, 2020 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [3255a17583](https://linux-hardware.org/?probe=3255a17583) | Sep 28, 2020 |
| MSI           | Z170-A PRO                  | Desktop     | [bcf22d328e](https://linux-hardware.org/?probe=bcf22d328e) | Sep 28, 2020 |
| Dell          | Latitude 7490               | Notebook    | [cfd6c8dcc4](https://linux-hardware.org/?probe=cfd6c8dcc4) | Sep 28, 2020 |
| Intel         | DX79TO AAG28805-400         | Desktop     | [d4cdc0726f](https://linux-hardware.org/?probe=d4cdc0726f) | Sep 26, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [118729faeb](https://linux-hardware.org/?probe=118729faeb) | Sep 23, 2020 |
| TUXEDO        | Book BA1510                 | Notebook    | [d89436074e](https://linux-hardware.org/?probe=d89436074e) | Sep 23, 2020 |
| Lenovo        | ThinkPad E495 20NE001GMX    | Notebook    | [3399940dd9](https://linux-hardware.org/?probe=3399940dd9) | Sep 17, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [5bd6ca5aba](https://linux-hardware.org/?probe=5bd6ca5aba) | Sep 15, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [83263681eb](https://linux-hardware.org/?probe=83263681eb) | Sep 15, 2020 |
| Notebook      | W35xSS_370SS                | Notebook    | [5b35813fca](https://linux-hardware.org/?probe=5b35813fca) | Sep 10, 2020 |
| HP            | ZBook 17                    | Notebook    | [605dfd3279](https://linux-hardware.org/?probe=605dfd3279) | Sep 08, 2020 |
| HP            | ZBook 17                    | Notebook    | [09e5bd8eb6](https://linux-hardware.org/?probe=09e5bd8eb6) | Sep 08, 2020 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [0dd7682249](https://linux-hardware.org/?probe=0dd7682249) | Sep 08, 2020 |
| ASUSTek       | X542UQR                     | Notebook    | [7782f01f3c](https://linux-hardware.org/?probe=7782f01f3c) | Sep 04, 2020 |
| ASUSTek       | E502MA                      | Notebook    | [1eb9e7db73](https://linux-hardware.org/?probe=1eb9e7db73) | Sep 01, 2020 |
| ASUSTek       | X501U                       | Notebook    | [006dc7a8d6](https://linux-hardware.org/?probe=006dc7a8d6) | Aug 15, 2020 |
| ASRock        | P45DE3                      | Desktop     | [3fce267079](https://linux-hardware.org/?probe=3fce267079) | Aug 11, 2020 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [5b48876c88](https://linux-hardware.org/?probe=5b48876c88) | Aug 11, 2020 |
| Lenovo        | 0x36A017AA SDK0J40700 WI... | Desktop     | [420e531d0c](https://linux-hardware.org/?probe=420e531d0c) | Aug 11, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [fd8d68081e](https://linux-hardware.org/?probe=fd8d68081e) | Aug 08, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [30d102a39e](https://linux-hardware.org/?probe=30d102a39e) | Aug 07, 2020 |
| Lenovo        | ThinkPad X220 4291R30       | Notebook    | [bdf2c40591](https://linux-hardware.org/?probe=bdf2c40591) | Aug 06, 2020 |
| Lenovo        | ThinkPad T490 20N2000NMX    | Notebook    | [8f21de6e06](https://linux-hardware.org/?probe=8f21de6e06) | Aug 05, 2020 |
| Acer          | Extensa 5620                | Notebook    | [dba48971a3](https://linux-hardware.org/?probe=dba48971a3) | Jul 24, 2020 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [f6f1267e91](https://linux-hardware.org/?probe=f6f1267e91) | Jul 23, 2020 |
| Lenovo        | ThinkPad T480s 20L7001VU... | Notebook    | [03bcc8865c](https://linux-hardware.org/?probe=03bcc8865c) | Jul 23, 2020 |
| ASRock        | B250M Pro4                  | Desktop     | [3ad9bafdc1](https://linux-hardware.org/?probe=3ad9bafdc1) | Jul 19, 2020 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [43684f5ded](https://linux-hardware.org/?probe=43684f5ded) | Jul 15, 2020 |
| ASUSTek       | P5LD2                       | Desktop     | [caa5d2a038](https://linux-hardware.org/?probe=caa5d2a038) | Jul 13, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [751ba49889](https://linux-hardware.org/?probe=751ba49889) | Jul 09, 2020 |
| ASRock        | Z170 Pro4S                  | Desktop     | [71665893c0](https://linux-hardware.org/?probe=71665893c0) | Jul 08, 2020 |
| ASRock        | Z170 Pro4S                  | Desktop     | [2d7a70bd54](https://linux-hardware.org/?probe=2d7a70bd54) | Jul 06, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [3149f0037a](https://linux-hardware.org/?probe=3149f0037a) | Jul 03, 2020 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [9bd5a64d0d](https://linux-hardware.org/?probe=9bd5a64d0d) | Jun 25, 2020 |
| HP            | Presario CQ56               | Notebook    | [f668bc59f5](https://linux-hardware.org/?probe=f668bc59f5) | Jun 23, 2020 |
| HP            | Presario CQ56               | Notebook    | [b8db4c3694](https://linux-hardware.org/?probe=b8db4c3694) | Jun 23, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [867ca870fd](https://linux-hardware.org/?probe=867ca870fd) | Jun 14, 2020 |
| ASUSTek       | WS X299 SAGE                | Desktop     | [bfc9505d4b](https://linux-hardware.org/?probe=bfc9505d4b) | Jun 05, 2020 |
| MSI           | Boston                      | Desktop     | [48a3bf1932](https://linux-hardware.org/?probe=48a3bf1932) | Jun 02, 2020 |
| Samsung       | 535U3C                      | Notebook    | [e7bc13b354](https://linux-hardware.org/?probe=e7bc13b354) | May 30, 2020 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [26c8949a0a](https://linux-hardware.org/?probe=26c8949a0a) | May 29, 2020 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [869444acf6](https://linux-hardware.org/?probe=869444acf6) | May 26, 2020 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [d4e3d725fa](https://linux-hardware.org/?probe=d4e3d725fa) | May 19, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [32fc505cab](https://linux-hardware.org/?probe=32fc505cab) | May 17, 2020 |
| MSI           | Z170A GAMING M3             | Desktop     | [369ce228c3](https://linux-hardware.org/?probe=369ce228c3) | May 16, 2020 |
| Lenovo        | ThinkPad T540p 20BFS4510... | Notebook    | [6c5bf8bfbe](https://linux-hardware.org/?probe=6c5bf8bfbe) | May 05, 2020 |
| HP            | EliteBook 840 G2            | Notebook    | [e1602a8c0e](https://linux-hardware.org/?probe=e1602a8c0e) | May 04, 2020 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [a1a1ce6e00](https://linux-hardware.org/?probe=a1a1ce6e00) | May 02, 2020 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [e3321de949](https://linux-hardware.org/?probe=e3321de949) | May 02, 2020 |
| Samsung       | 900X3C/900X3D/900X4C/900... | Notebook    | [35b95432ac](https://linux-hardware.org/?probe=35b95432ac) | Apr 30, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [eea0fa4941](https://linux-hardware.org/?probe=eea0fa4941) | Apr 25, 2020 |
| MSI           | B360-A PRO                  | Desktop     | [c42cb75770](https://linux-hardware.org/?probe=c42cb75770) | Apr 24, 2020 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [91770bcd78](https://linux-hardware.org/?probe=91770bcd78) | Apr 22, 2020 |
| MSI           | GS75 Stealth 8SE            | Notebook    | [1c50333136](https://linux-hardware.org/?probe=1c50333136) | Apr 07, 2020 |
| HP            | EliteBook 2560p             | Notebook    | [cdca82a043](https://linux-hardware.org/?probe=cdca82a043) | Apr 05, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [61c4420d0e](https://linux-hardware.org/?probe=61c4420d0e) | Mar 22, 2020 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [76af4a7e0b](https://linux-hardware.org/?probe=76af4a7e0b) | Mar 21, 2020 |
| ASRock        | P45DE3                      | Desktop     | [fffef664cd](https://linux-hardware.org/?probe=fffef664cd) | Mar 18, 2020 |
| MSI           | B75A-G43                    | Desktop     | [9683ec9bd4](https://linux-hardware.org/?probe=9683ec9bd4) | Mar 16, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [95eb08349e](https://linux-hardware.org/?probe=95eb08349e) | Mar 15, 2020 |
| Samsung       | 275E4E/275E5E               | Notebook    | [6b624f1079](https://linux-hardware.org/?probe=6b624f1079) | Mar 12, 2020 |
| Lenovo        | ThinkPad A285 20MXS0BG00    | Notebook    | [4dabcb8d3f](https://linux-hardware.org/?probe=4dabcb8d3f) | Mar 11, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [e30b449cc4](https://linux-hardware.org/?probe=e30b449cc4) | Mar 08, 2020 |
| ASUSTek       | Z97-A                       | Desktop     | [8bc7b7979a](https://linux-hardware.org/?probe=8bc7b7979a) | Mar 01, 2020 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [63e19ed1f4](https://linux-hardware.org/?probe=63e19ed1f4) | Feb 28, 2020 |
| MSI           | 990FXA-GD65                 | Desktop     | [adc15c7147](https://linux-hardware.org/?probe=adc15c7147) | Feb 24, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b17f2abd3e](https://linux-hardware.org/?probe=b17f2abd3e) | Feb 20, 2020 |
| Lenovo        | ThinkPad P50 20EN0006MS     | Notebook    | [c71def9148](https://linux-hardware.org/?probe=c71def9148) | Feb 18, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ed5efcdf48](https://linux-hardware.org/?probe=ed5efcdf48) | Feb 03, 2020 |
| Gigabyte      | H81M-S1                     | Desktop     | [754bdf88c1](https://linux-hardware.org/?probe=754bdf88c1) | Jan 26, 2020 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [1eb5f177d1](https://linux-hardware.org/?probe=1eb5f177d1) | Jan 13, 2020 |
| Dell          | 0D28YY A01                  | Desktop     | [be51211fe3](https://linux-hardware.org/?probe=be51211fe3) | Dec 09, 2019 |
| Dell          | Latitude 5289               | Convertible | [dfdc8c484f](https://linux-hardware.org/?probe=dfdc8c484f) | Dec 04, 2019 |
| Gigabyte      | H81M-S1                     | Desktop     | [57524ab581](https://linux-hardware.org/?probe=57524ab581) | Dec 03, 2019 |
| Dell          | Precision 5510              | Notebook    | [68c56e0ab4](https://linux-hardware.org/?probe=68c56e0ab4) | Dec 02, 2019 |
| ASUSTek       | VM60                        | Desktop     | [4842363a0b](https://linux-hardware.org/?probe=4842363a0b) | Nov 14, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [c4917de06e](https://linux-hardware.org/?probe=c4917de06e) | Oct 17, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [9f867b307a](https://linux-hardware.org/?probe=9f867b307a) | Oct 12, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [8beb57338d](https://linux-hardware.org/?probe=8beb57338d) | Oct 02, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [f3f1a208c1](https://linux-hardware.org/?probe=f3f1a208c1) | Sep 26, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [0639ef182a](https://linux-hardware.org/?probe=0639ef182a) | Sep 20, 2019 |
| HP            | Pavilion Gaming Notebook    | Notebook    | [3b99dff2c2](https://linux-hardware.org/?probe=3b99dff2c2) | Sep 19, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [abc398724a](https://linux-hardware.org/?probe=abc398724a) | Sep 16, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [f6acac9fc8](https://linux-hardware.org/?probe=f6acac9fc8) | Sep 15, 2019 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [d2b5c32d2f](https://linux-hardware.org/?probe=d2b5c32d2f) | Sep 15, 2019 |
| Dell          | Inspiron 5748               | Notebook    | [75647e5457](https://linux-hardware.org/?probe=75647e5457) | Sep 03, 2019 |
| Acer          | Aspire V3-771               | Notebook    | [335c3fea78](https://linux-hardware.org/?probe=335c3fea78) | Aug 10, 2019 |
| Quanta        | TWH                         | Notebook    | [b6c3554305](https://linux-hardware.org/?probe=b6c3554305) | Aug 05, 2019 |
| Quanta        | TWH                         | Notebook    | [243be58298](https://linux-hardware.org/?probe=243be58298) | Aug 05, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [4a247c1234](https://linux-hardware.org/?probe=4a247c1234) | Aug 03, 2019 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [15bfdc0f25](https://linux-hardware.org/?probe=15bfdc0f25) | Aug 03, 2019 |
| HP            | OMEN by Laptop              | Notebook    | [cd37f24ff8](https://linux-hardware.org/?probe=cd37f24ff8) | Aug 01, 2019 |
| HP            | 1495                        | Desktop     | [3d9e77ae8a](https://linux-hardware.org/?probe=3d9e77ae8a) | Jul 23, 2019 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [46e1a9fc55](https://linux-hardware.org/?probe=46e1a9fc55) | Jul 04, 2019 |
| Dell          | Inspiron 5558               | Notebook    | [f26b9a5e36](https://linux-hardware.org/?probe=f26b9a5e36) | Jun 29, 2019 |
| ASUSTek       | N56VZ                       | Notebook    | [02928f6b1e](https://linux-hardware.org/?probe=02928f6b1e) | Jun 25, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [3a8d19c8fc](https://linux-hardware.org/?probe=3a8d19c8fc) | Jun 22, 2019 |
| Gigabyte      | 970-GAMING                  | Desktop     | [aa1385d100](https://linux-hardware.org/?probe=aa1385d100) | Jun 03, 2019 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [1edb7b5f96](https://linux-hardware.org/?probe=1edb7b5f96) | May 25, 2019 |
| HP            | Pavilion dv4000 (EK980EA... | Notebook    | [837230178b](https://linux-hardware.org/?probe=837230178b) | May 23, 2019 |
| Intel         | DQ35JO AAD82085-807         | Desktop     | [7f57ad053d](https://linux-hardware.org/?probe=7f57ad053d) | May 20, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [84c3544bb2](https://linux-hardware.org/?probe=84c3544bb2) | May 20, 2019 |
| Samsung       | 275E4E/275E5E               | Notebook    | [60cb87eeb6](https://linux-hardware.org/?probe=60cb87eeb6) | May 11, 2019 |
| Dell          | Latitude 5289               | Convertible | [e28d069f05](https://linux-hardware.org/?probe=e28d069f05) | May 07, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | Notebook    | [cfcb3e3b82](https://linux-hardware.org/?probe=cfcb3e3b82) | May 02, 2019 |
| Lenovo        | ThinkPad T61 76641FG        | Notebook    | [c577dfbf17](https://linux-hardware.org/?probe=c577dfbf17) | May 02, 2019 |
| Samsung       | 770Z5E/780Z5E               | Notebook    | [e07529a7fc](https://linux-hardware.org/?probe=e07529a7fc) | Apr 14, 2019 |
| Dell          | 0KP561                      | Desktop     | [bba0fe2672](https://linux-hardware.org/?probe=bba0fe2672) | Apr 05, 2019 |
| Dell          | 0KP561                      | Desktop     | [f3085d1ae9](https://linux-hardware.org/?probe=f3085d1ae9) | Apr 04, 2019 |
| Fujitsu Si... | AMILO La1703                | Notebook    | [4530891733](https://linux-hardware.org/?probe=4530891733) | Apr 01, 2019 |
| ASRock        | H370M-ITX/ac                | Desktop     | [ba39531b87](https://linux-hardware.org/?probe=ba39531b87) | Mar 31, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [e411551975](https://linux-hardware.org/?probe=e411551975) | Mar 21, 2019 |
| Dell          | Inspiron 3543               | Notebook    | [f85fec55bb](https://linux-hardware.org/?probe=f85fec55bb) | Mar 19, 2019 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [bee48cd1c5](https://linux-hardware.org/?probe=bee48cd1c5) | Mar 09, 2019 |
| Lenovo        | ThinkPad T580 20L90026MX    | Notebook    | [14afd9ea12](https://linux-hardware.org/?probe=14afd9ea12) | Feb 27, 2019 |
| HP            | 18E7                        | Desktop     | [19df4fb560](https://linux-hardware.org/?probe=19df4fb560) | Feb 22, 2019 |
| HP            | ProBook 470 G1              | Notebook    | [268414d1b5](https://linux-hardware.org/?probe=268414d1b5) | Feb 07, 2019 |
| ABIT          | KN9 Series                  | Desktop     | [10015b723b](https://linux-hardware.org/?probe=10015b723b) | Feb 04, 2019 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [f1a9b27e5c](https://linux-hardware.org/?probe=f1a9b27e5c) | Feb 04, 2019 |
| ASRock        | B250M Pro4                  | Desktop     | [b702949950](https://linux-hardware.org/?probe=b702949950) | Dec 19, 2018 |
| Lenovo        | ThinkPad T480 20L5000BMX    | Notebook    | [5357d8ad3a](https://linux-hardware.org/?probe=5357d8ad3a) | Dec 04, 2018 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [158fb83dcc](https://linux-hardware.org/?probe=158fb83dcc) | Nov 13, 2018 |
| ASRock        | B250M Pro4                  | Desktop     | [a00ad66604](https://linux-hardware.org/?probe=a00ad66604) | Oct 24, 2018 |
| ASRock        | B250M Pro4                  | Desktop     | [9c47ffacd5](https://linux-hardware.org/?probe=9c47ffacd5) | Oct 24, 2018 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [a075fc73d3](https://linux-hardware.org/?probe=a075fc73d3) | Oct 09, 2018 |
| ASUSTek       | X55A                        | Notebook    | [403b1aa1d7](https://linux-hardware.org/?probe=403b1aa1d7) | May 08, 2018 |
| ASUSTek       | K40IJ                       | Notebook    | [24366329c2](https://linux-hardware.org/?probe=24366329c2) | May 07, 2018 |
| ECS           | H55H-3.8L                   | Desktop     | [7e782321c8](https://linux-hardware.org/?probe=7e782321c8) | Mar 31, 2018 |
| Dell          | Inspiron N5110              | Notebook    | [d7b2f7f719](https://linux-hardware.org/?probe=d7b2f7f719) | Oct 05, 2017 |
| ASUSTek       | M2N-MX SE                   | Desktop     | [78791d4918](https://linux-hardware.org/?probe=78791d4918) | Sep 13, 2017 |
| Acer          | Aspire 6530G                | Notebook    | [2f88dba791](https://linux-hardware.org/?probe=2f88dba791) | Aug 13, 2017 |
| ASUSTek       | P8H67                       | Desktop     | [e36d00c6f9](https://linux-hardware.org/?probe=e36d00c6f9) | Jul 21, 2017 |
| HP            | Compaq nx7400 (RH387EA#A... | Notebook    | [116c8bc9de](https://linux-hardware.org/?probe=116c8bc9de) | Jun 03, 2017 |
| Toshiba       | Satellite L855              | Notebook    | [de2e163003](https://linux-hardware.org/?probe=de2e163003) | May 17, 2017 |
| ECS           | nVidia-nForce               | Desktop     | [db8fd734f9](https://linux-hardware.org/?probe=db8fd734f9) | May 16, 2017 |
| HP            | Pavilion dv5                | Notebook    | [3191678465](https://linux-hardware.org/?probe=3191678465) | May 04, 2017 |
| HP            | Pavilion dv5                | Notebook    | [1f21f421ed](https://linux-hardware.org/?probe=1f21f421ed) | May 02, 2017 |
| Quanta        | TWH                         | Notebook    | [4807bd6702](https://linux-hardware.org/?probe=4807bd6702) | Apr 28, 2017 |
| Quanta        | TWH                         | Notebook    | [0105619fb7](https://linux-hardware.org/?probe=0105619fb7) | Apr 27, 2017 |
| Acer          | Aspire 5541                 | Notebook    | [efa45ad21c](https://linux-hardware.org/?probe=efa45ad21c) | Nov 14, 2016 |
| Acer          | Aspire 5541                 | Notebook    | [b61eb7bcb0](https://linux-hardware.org/?probe=b61eb7bcb0) | Nov 13, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Ubuntu 20.04      | 31        | 10.06%  |
| Ubuntu 18.04      | 22        | 7.14%   |
| Ubuntu 22.04      | 18        | 5.84%   |
| ROSA R11          | 10        | 3.25%   |
| Arch Rolling      | 10        | 3.25%   |
| Arch              | 10        | 3.25%   |
| Fedora 34         | 8         | 2.6%    |
| Ubuntu 19.04      | 7         | 2.27%   |
| ROSA R8.1         | 7         | 2.27%   |
| OpenMandriva 4.3  | 7         | 2.27%   |
| Kubuntu 20.04     | 7         | 2.27%   |
| ArcoLinux Rolling | 7         | 2.27%   |
| Manjaro           | 6         | 1.95%   |
| Linux Mint 20.1   | 6         | 1.95%   |
| ROSA 12.2         | 5         | 1.62%   |
| OpenMandriva 4.2  | 5         | 1.62%   |
| Fedora 36         | 5         | 1.62%   |
| Fedora 35         | 5         | 1.62%   |
| ROSA R9           | 4         | 1.3%    |
| Kubuntu 22.04     | 4         | 1.3%    |
| KDE neon 20.04    | 4         | 1.3%    |
| Zorin 16          | 3         | 0.97%   |
| Ubuntu MATE 22.04 | 3         | 0.97%   |
| Ubuntu 21.10      | 3         | 0.97%   |
| Ubuntu 19.10      | 3         | 0.97%   |
| ROSA R10          | 3         | 0.97%   |
| Pop!_OS 20.04     | 3         | 0.97%   |
| Linux Mint 20.3   | 3         | 0.97%   |
| Gentoo 2.6        | 3         | 0.97%   |
| Fedora 31         | 3         | 0.97%   |
| Debian Testing    | 3         | 0.97%   |
| Debian 11         | 3         | 0.97%   |
| Xubuntu 20.04     | 2         | 0.65%   |
| Xubuntu 18.04     | 2         | 0.65%   |
| Ubuntu MATE 20.04 | 2         | 0.65%   |
| Ubuntu 21.04      | 2         | 0.65%   |
| Ubuntu 20.10      | 2         | 0.65%   |
| Ubuntu 16.04      | 2         | 0.65%   |
| Reborn OS         | 2         | 0.65%   |
| Pop!_OS 22.04     | 2         | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 90        | 29.9%   |
| ROSA         | 32        | 10.63%  |
| Fedora       | 23        | 7.64%   |
| Arch         | 20        | 6.64%   |
| OpenMandriva | 16        | 5.32%   |
| Manjaro      | 16        | 5.32%   |
| Linux Mint   | 16        | 5.32%   |
| Kubuntu      | 10        | 3.32%   |
| Pop!_OS      | 9         | 2.99%   |
| Debian       | 8         | 2.66%   |
| ArcoLinux    | 7         | 2.33%   |
| Xubuntu      | 6         | 1.99%   |
| Ubuntu MATE  | 5         | 1.66%   |
| KDE neon     | 5         | 1.66%   |
| Zorin        | 4         | 1.33%   |
| Gentoo       | 4         | 1.33%   |
| Endless      | 4         | 1.33%   |
| Elementary   | 4         | 1.33%   |
| openSUSE     | 3         | 1%      |
| Clear Linux  | 3         | 1%      |
| SteamOS      | 2         | 0.66%   |
| Reborn OS    | 2         | 0.66%   |
| Nobara       | 2         | 0.66%   |
| LMDE         | 2         | 0.66%   |
| Kali         | 2         | 0.66%   |
| EndeavourOS  | 2         | 0.66%   |
| Ubuntu Unity | 1         | 0.33%   |
| MX           | 1         | 0.33%   |
| Lubuntu      | 1         | 0.33%   |
| ChimeraOS    | 1         | 0.33%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.4.0-42-generic                    | 8         | 2.39%   |
| 5.16.7-desktop-1omv4003             | 7         | 2.09%   |
| 5.15.0-52-generic                   | 5         | 1.49%   |
| 5.10.14-desktop-1omv4002            | 5         | 1.49%   |
| 5.15.0-53-generic                   | 4         | 1.19%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 4         | 1.19%   |
| 5.4.0-65-generic                    | 3         | 0.9%    |
| 5.4.0-47-generic                    | 3         | 0.9%    |
| 5.4.0-28-generic                    | 3         | 0.9%    |
| 5.15.0-56-generic                   | 3         | 0.9%    |
| 5.10.74-generic-2rosa2021.1-x86_64  | 3         | 0.9%    |
| 5.10.118-generic-2rosa2021.1-x86_64 | 3         | 0.9%    |
| 4.15.0-desktop-45.1rosa-x86_64      | 3         | 0.9%    |
| 6.2.6-desktop-1omv2390              | 2         | 0.6%    |
| 6.1.1-desktop-1omv2290              | 2         | 0.6%    |
| 6.1.0-kali7-amd64                   | 2         | 0.6%    |
| 5.8.0-63-generic                    | 2         | 0.6%    |
| 5.8.0-53-generic                    | 2         | 0.6%    |
| 5.5.2-1-MANJARO                     | 2         | 0.6%    |
| 5.4.0-88-generic                    | 2         | 0.6%    |
| 5.4.0-58-generic                    | 2         | 0.6%    |
| 5.4.0-53-generic                    | 2         | 0.6%    |
| 5.4.0-45-generic                    | 2         | 0.6%    |
| 5.4.0-33-generic                    | 2         | 0.6%    |
| 5.4.0-29-generic                    | 2         | 0.6%    |
| 5.4.0-26-generic                    | 2         | 0.6%    |
| 5.3.0-40-generic                    | 2         | 0.6%    |
| 5.15.5-76051505-generic             | 2         | 0.6%    |
| 5.15.2-arch1-1                      | 2         | 0.6%    |
| 5.15.0-46-generic                   | 2         | 0.6%    |
| 5.15.0-41-generic                   | 2         | 0.6%    |
| 5.13.12-200.fc34.x86_64             | 2         | 0.6%    |
| 5.13.0-39-generic                   | 2         | 0.6%    |
| 5.11.0-37-generic                   | 2         | 0.6%    |
| 5.11.0-34-generic                   | 2         | 0.6%    |
| 5.11.0-27-generic                   | 2         | 0.6%    |
| 5.11.0-25-generic                   | 2         | 0.6%    |
| 5.0.0-23-generic                    | 2         | 0.6%    |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 2         | 0.6%    |
| 4.18.0-15-generic                   | 2         | 0.6%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4.0    | 48        | 14.86%  |
| 4.15.0   | 26        | 8.05%   |
| 5.15.0   | 25        | 7.74%   |
| 5.11.0   | 15        | 4.64%   |
| 5.13.0   | 12        | 3.72%   |
| 5.8.0    | 11        | 3.41%   |
| 5.0.0    | 10        | 3.1%    |
| 5.16.7   | 7         | 2.17%   |
| 5.3.0    | 6         | 1.86%   |
| 4.18.0   | 6         | 1.86%   |
| 6.2.6    | 5         | 1.55%   |
| 5.19.0   | 5         | 1.55%   |
| 5.10.14  | 5         | 1.55%   |
| 4.9.20   | 5         | 1.55%   |
| 5.10.0   | 4         | 1.24%   |
| 5.15.2   | 3         | 0.93%   |
| 5.13.12  | 3         | 0.93%   |
| 5.10.74  | 3         | 0.93%   |
| 5.10.118 | 3         | 0.93%   |
| 4.9.9    | 3         | 0.93%   |
| 6.1.1    | 2         | 0.62%   |
| 6.1.0    | 2         | 0.62%   |
| 6.0.9    | 2         | 0.62%   |
| 6.0.11   | 2         | 0.62%   |
| 5.8.10   | 2         | 0.62%   |
| 5.5.2    | 2         | 0.62%   |
| 5.17.1   | 2         | 0.62%   |
| 5.15.5   | 2         | 0.62%   |
| 5.13.19  | 2         | 0.62%   |
| 5.13.13  | 2         | 0.62%   |
| 5.11.12  | 2         | 0.62%   |
| 5.11.11  | 2         | 0.62%   |
| 4.9.60   | 2         | 0.62%   |
| 4.19.0   | 2         | 0.62%   |
| 6.3.1    | 1         | 0.31%   |
| 6.2.7    | 1         | 0.31%   |
| 6.1.9    | 1         | 0.31%   |
| 6.1.5    | 1         | 0.31%   |
| 6.1.4    | 1         | 0.31%   |
| 6.1.29   | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 54        | 16.77%  |
| 5.15    | 33        | 10.25%  |
| 4.15    | 26        | 8.07%   |
| 5.13    | 25        | 7.76%   |
| 5.10    | 22        | 6.83%   |
| 5.11    | 20        | 6.21%   |
| 5.8     | 14        | 4.35%   |
| 4.9     | 14        | 4.35%   |
| 5.16    | 12        | 3.73%   |
| 6.1     | 11        | 3.42%   |
| 5.0     | 11        | 3.42%   |
| 6.0     | 9         | 2.8%    |
| 5.3     | 8         | 2.48%   |
| 5.14    | 8         | 2.48%   |
| 5.19    | 7         | 2.17%   |
| 6.2     | 6         | 1.86%   |
| 5.17    | 6         | 1.86%   |
| 4.18    | 6         | 1.86%   |
| 5.9     | 4         | 1.24%   |
| 5.5     | 4         | 1.24%   |
| 5.12    | 4         | 1.24%   |
| 4.19    | 4         | 1.24%   |
| 5.6     | 3         | 0.93%   |
| 5.18    | 3         | 0.93%   |
| 4.1     | 2         | 0.62%   |
| 6.3     | 1         | 0.31%   |
| 5.7     | 1         | 0.31%   |
| 5.1     | 1         | 0.31%   |
| 4.4     | 1         | 0.31%   |
| 4.10    | 1         | 0.31%   |
| 3.16    | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 283       | 95.93%  |
| i686   | 11        | 3.73%   |
| armv7l | 1         | 0.34%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 110       | 36.3%   |
| KDE5       | 54        | 17.82%  |
| Unknown    | 44        | 14.52%  |
| XFCE       | 21        | 6.93%   |
| KDE4       | 19        | 6.27%   |
| X-Cinnamon | 16        | 5.28%   |
| MATE       | 11        | 3.63%   |
| KDE        | 5         | 1.65%   |
| i3         | 5         | 1.65%   |
| Pantheon   | 4         | 1.32%   |
| LXQt       | 3         | 0.99%   |
| Unity      | 2         | 0.66%   |
| sway       | 2         | 0.66%   |
| LXDE       | 2         | 0.66%   |
| awesome    | 2         | 0.66%   |
| openbox    | 1         | 0.33%   |
| Cinnamon   | 1         | 0.33%   |
| Budgie     | 1         | 0.33%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 228       | 76.77%  |
| Wayland | 50        | 16.84%  |
| Unknown | 16        | 5.39%   |
| Tty     | 2         | 0.67%   |
| Web     | 1         | 0.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 134       | 44.67%  |
| SDDM    | 52        | 17.33%  |
| GDM     | 38        | 12.67%  |
| GDM3    | 27        | 9%      |
| KDM     | 19        | 6.33%   |
| LightDM | 18        | 6%      |
| TDM     | 12        | 4%      |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang            | Computers | Percent |
|-----------------|-----------|---------|
| en_US           | 142       | 47.18%  |
| Unknown         | 60        | 19.93%  |
| et_EE           | 46        | 15.28%  |
| ru_RU           | 27        | 8.97%   |
| en_GB           | 11        | 3.65%   |
| de_DE           | 3         | 1%      |
| pl_PL           | 2         | 0.66%   |
| fr_FR           | 2         | 0.66%   |
| en_DK           | 2         | 0.66%   |
| C               | 2         | 0.66%   |
| uk_UA           | 1         | 0.33%   |
| ru_UA           | 1         | 0.33%   |
| en_US.iso885915 | 1         | 0.33%   |
| en_DE           | 1         | 0.33%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 160       | 53.16%  |
| EFI  | 141       | 46.84%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 215       | 72.39%  |
| Btrfs   | 39        | 13.13%  |
| Unknown | 19        | 6.4%    |
| Overlay | 18        | 6.06%   |
| Xfs     | 3         | 1.01%   |
| Ext3    | 2         | 0.67%   |
| Zfs     | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 138       | 46.62%  |
| GPT     | 117       | 39.53%  |
| MBR     | 41        | 13.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 249       | 83%     |
| Yes       | 51        | 17%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 206       | 68.9%   |
| Yes       | 93        | 31.1%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 61        | 20.68%  |
| ASUSTek Computer    | 47        | 15.93%  |
| Hewlett-Packard     | 39        | 13.22%  |
| Dell                | 29        | 9.83%   |
| MSI                 | 28        | 9.49%   |
| Gigabyte Technology | 23        | 7.8%    |
| ASRock              | 10        | 3.39%   |
| Samsung Electronics | 7         | 2.37%   |
| Intel               | 6         | 2.03%   |
| Acer                | 6         | 2.03%   |
| Fujitsu             | 4         | 1.36%   |
| Apple               | 4         | 1.36%   |
| ECS                 | 3         | 1.02%   |
| Valve               | 2         | 0.68%   |
| Timi                | 2         | 0.68%   |
| Quanta              | 2         | 0.68%   |
| Notebook            | 2         | 0.68%   |
| Alienware           | 2         | 0.68%   |
| ZOTAC               | 1         | 0.34%   |
| TUXEDO              | 1         | 0.34%   |
| Toshiba             | 1         | 0.34%   |
| Supermicro          | 1         | 0.34%   |
| Prestigio           | 1         | 0.34%   |
| Packard Bell        | 1         | 0.34%   |
| OEM                 | 1         | 0.34%   |
| mPTech              | 1         | 0.34%   |
| Microsoft           | 1         | 0.34%   |
| HUAWEI              | 1         | 0.34%   |
| Huanan              | 1         | 0.34%   |
| GPD                 | 1         | 0.34%   |
| Getac               | 1         | 0.34%   |
| Fujitsu Siemens     | 1         | 0.34%   |
| Framework           | 1         | 0.34%   |
| Chuwi               | 1         | 0.34%   |
| ABIT                | 1         | 0.34%   |
| Unknown             | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| ASUS All Series                                       | 4         | 1.36%   |
| Valve Jupiter                                         | 2         | 0.68%   |
| Quanta TWH                                            | 2         | 0.68%   |
| MSI MS-7C02                                           | 2         | 0.68%   |
| MSI MS-7758                                           | 2         | 0.68%   |
| Lenovo Y50-70 20378                                   | 2         | 0.68%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2                     | 2         | 0.68%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                   | 2         | 0.68%   |
| HP Pavilion dv7                                       | 2         | 0.68%   |
| HP ENVY Laptop 13-ah0xxx                              | 2         | 0.68%   |
| HP EliteBook 8470p                                    | 2         | 0.68%   |
| HP EliteBook 8460p                                    | 2         | 0.68%   |
| HP EliteBook 840 G2                                   | 2         | 0.68%   |
| HP Compaq 8100 Elite SFF PC                           | 2         | 0.68%   |
| Gigabyte X570 AORUS PRO                               | 2         | 0.68%   |
| Gigabyte Q87M-D2H                                     | 2         | 0.68%   |
| Dell Inspiron N5110                                   | 2         | 0.68%   |
| Alienware 17                                          | 2         | 0.68%   |
| Unknown                                               | 2         | 0.68%   |
| ZOTAC B410                                            | 1         | 0.34%   |
| TUXEDO Book BA1510                                    | 1         | 0.34%   |
| Toshiba Satellite L855                                | 1         | 0.34%   |
| Timi RedmiBook 16                                     | 1         | 0.34%   |
| Timi RedmiBook 14 II                                  | 1         | 0.34%   |
| Supermicro X10SLH-F/X10SLM+-F                         | 1         | 0.34%   |
| Samsung R410                                          | 1         | 0.34%   |
| Samsung 900X3C/900X3D/900X4C/900X4D                   | 1         | 0.34%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D            | 1         | 0.34%   |
| Samsung 770Z5E/780Z5E                                 | 1         | 0.34%   |
| Samsung 535U3C                                        | 1         | 0.34%   |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV/2470EE | 1         | 0.34%   |
| Samsung 275E4E/275E5E                                 | 1         | 0.34%   |
| Prestigio PNT10131DEDB                                | 1         | 0.34%   |
| Packard Bell EasyNote TK87                            | 1         | 0.34%   |
| OEM Intel H81                                         | 1         | 0.34%   |
| Notebook W35xSS_370SS                                 | 1         | 0.34%   |
| Notebook N150SD/N155SD                                | 1         | 0.34%   |
| MSI MS-B90111                                         | 1         | 0.34%   |
| MSI MS-7D43                                           | 1         | 0.34%   |
| MSI MS-7C91                                           | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 40        | 13.56%  |
| HP EliteBook        | 13        | 4.41%   |
| HP Pavilion         | 8         | 2.71%   |
| Dell Inspiron       | 7         | 2.37%   |
| HP Compaq           | 6         | 2.03%   |
| Dell Latitude       | 6         | 2.03%   |
| ASUS PRIME          | 6         | 2.03%   |
| Dell OptiPlex       | 5         | 1.69%   |
| Lenovo IdeaPad      | 4         | 1.36%   |
| Gigabyte X570       | 4         | 1.36%   |
| Dell XPS            | 4         | 1.36%   |
| Dell Precision      | 4         | 1.36%   |
| ASUS VivoBook       | 4         | 1.36%   |
| ASUS All            | 4         | 1.36%   |
| Acer Aspire         | 4         | 1.36%   |
| Lenovo ThinkCentre  | 3         | 1.02%   |
| Lenovo IdeaPadFlex  | 3         | 1.02%   |
| HP ENVY             | 3         | 1.02%   |
| Fujitsu LIFEBOOK    | 3         | 1.02%   |
| ASUS TUF            | 3         | 1.02%   |
| ASUS ROG            | 3         | 1.02%   |
| Valve Jupiter       | 2         | 0.68%   |
| Timi RedmiBook      | 2         | 0.68%   |
| Samsung 900X3C      | 2         | 0.68%   |
| Quanta TWH          | 2         | 0.68%   |
| MSI MS-7C02         | 2         | 0.68%   |
| MSI MS-7758         | 2         | 0.68%   |
| Lenovo Y50-70       | 2         | 0.68%   |
| Lenovo Legion       | 2         | 0.68%   |
| HP ProDesk          | 2         | 0.68%   |
| HP Presario         | 2         | 0.68%   |
| HP OMEN             | 2         | 0.68%   |
| Gigabyte Q87M-D2H   | 2         | 0.68%   |
| ASUS ZenBook        | 2         | 0.68%   |
| Alienware 17        | 2         | 0.68%   |
| Unknown             | 2         | 0.68%   |
| ZOTAC B410          | 1         | 0.34%   |
| TUXEDO Book         | 1         | 0.34%   |
| Toshiba Satellite   | 1         | 0.34%   |
| Supermicro X10SLH-F | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 36        | 12.2%   |
| 2018    | 31        | 10.51%  |
| 2013    | 27        | 9.15%   |
| 2019    | 25        | 8.47%   |
| 2014    | 20        | 6.78%   |
| 2012    | 20        | 6.78%   |
| 2011    | 20        | 6.78%   |
| 2017    | 17        | 5.76%   |
| 2015    | 17        | 5.76%   |
| 2016    | 13        | 4.41%   |
| 2021    | 12        | 4.07%   |
| 2010    | 12        | 4.07%   |
| 2009    | 10        | 3.39%   |
| 2008    | 10        | 3.39%   |
| 2007    | 9         | 3.05%   |
| 2022    | 8         | 2.71%   |
| 2006    | 4         | 1.36%   |
| 2005    | 2         | 0.68%   |
| 2004    | 1         | 0.34%   |
| Unknown | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 167       | 56.61%  |
| Desktop     | 112       | 37.97%  |
| Convertible | 10        | 3.39%   |
| Mini pc     | 3         | 1.02%   |
| Tablet      | 1         | 0.34%   |
| All in one  | 1         | 0.34%   |
| Server      | 1         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 277       | 93.27%  |
| Enabled  | 20        | 6.73%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 295       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 62        | 20.81%  |
| 8.01-16.0   | 62        | 20.81%  |
| 4.01-8.0    | 57        | 19.13%  |
| 3.01-4.0    | 46        | 15.44%  |
| 32.01-64.0  | 35        | 11.74%  |
| 24.01-32.0  | 10        | 3.36%   |
| 2.01-3.0    | 9         | 3.02%   |
| 1.01-2.0    | 8         | 2.68%   |
| 64.01-256.0 | 6         | 2.01%   |
| 0.51-1.0    | 2         | 0.67%   |
| 0.01-0.5    | 1         | 0.34%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 96        | 30.28%  |
| 2.01-3.0   | 72        | 22.71%  |
| 4.01-8.0   | 58        | 18.3%   |
| 3.01-4.0   | 35        | 11.04%  |
| 0.51-1.0   | 25        | 7.89%   |
| 8.01-16.0  | 21        | 6.62%   |
| 0.01-0.5   | 4         | 1.26%   |
| 24.01-32.0 | 3         | 0.95%   |
| 16.01-24.0 | 3         | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 179       | 58.88%  |
| 2      | 68        | 22.37%  |
| 3      | 31        | 10.2%   |
| 4      | 11        | 3.62%   |
| 6      | 8         | 2.63%   |
| 5      | 4         | 1.32%   |
| 0      | 2         | 0.66%   |
| 7      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 184       | 61.74%  |
| Yes       | 114       | 38.26%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 263       | 88.55%  |
| No        | 34        | 11.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 217       | 73.56%  |
| No        | 78        | 26.44%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 177       | 59.4%   |
| No        | 121       | 40.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Estonia | 295       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Tallinn           | 192       | 63.58%  |
| Tartu             | 31        | 10.26%  |
| Pärnu            | 11        | 3.64%   |
| Rapla             | 7         | 2.32%   |
| Rakvere           | 6         | 1.99%   |
| Haapsalu          | 5         | 1.66%   |
| Narva             | 4         | 1.32%   |
| Maardu            | 3         | 0.99%   |
| Vinni             | 2         | 0.66%   |
| Viljandi          | 2         | 0.66%   |
| Tapa              | 2         | 0.66%   |
| Saku              | 2         | 0.66%   |
| Põlva            | 2         | 0.66%   |
| Paldiski          | 2         | 0.66%   |
| Otepaeae          | 2         | 0.66%   |
| Kohtla-Järve     | 2         | 0.66%   |
| Keila             | 2         | 0.66%   |
| Jõhvi            | 2         | 0.66%   |
| Vatla             | 1         | 0.33%   |
| Vaidasoo          | 1         | 0.33%   |
| Türi             | 1         | 0.33%   |
| Tabasalu          | 1         | 0.33%   |
| Sindi             | 1         | 0.33%   |
| Sillamäe         | 1         | 0.33%   |
| Sauga             | 1         | 0.33%   |
| Rae Parish        | 1         | 0.33%   |
| Pohja-Sakala vald | 1         | 0.33%   |
| Paide             | 1         | 0.33%   |
| Laagri            | 1         | 0.33%   |
| Kuressaare        | 1         | 0.33%   |
| Kose              | 1         | 0.33%   |
| Kiviõli          | 1         | 0.33%   |
| Kärdla           | 1         | 0.33%   |
| Kaeina            | 1         | 0.33%   |
| Kadrina           | 1         | 0.33%   |
| Jüri             | 1         | 0.33%   |
| Jõgeva           | 1         | 0.33%   |
| Jaerva vald       | 1         | 0.33%   |
| Hiiumaa           | 1         | 0.33%   |
| Haabneeme         | 1         | 0.33%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 95        | 129    | 21.25%  |
| Seagate                   | 59        | 76     | 13.2%   |
| WDC                       | 52        | 77     | 11.63%  |
| Kingston                  | 37        | 51     | 8.28%   |
| Toshiba                   | 29        | 30     | 6.49%   |
| SanDisk                   | 16        | 18     | 3.58%   |
| Hitachi                   | 16        | 20     | 3.58%   |
| Crucial                   | 16        | 25     | 3.58%   |
| SK hynix                  | 15        | 19     | 3.36%   |
| HGST                      | 12        | 16     | 2.68%   |
| Unknown                   | 11        | 11     | 2.46%   |
| Intel                     | 10        | 12     | 2.24%   |
| A-DATA Technology         | 9         | 15     | 2.01%   |
| Patriot                   | 5         | 6      | 1.12%   |
| Apacer                    | 5         | 6      | 1.12%   |
| KingSpec                  | 4         | 6      | 0.89%   |
| Gigabyte Technology       | 4         | 5      | 0.89%   |
| China                     | 4         | 4      | 0.89%   |
| Transcend                 | 3         | 6      | 0.67%   |
| Micron Technology         | 3         | 3      | 0.67%   |
| Lenovo                    | 3         | 3      | 0.67%   |
| ADATA Technology          | 3         | 3      | 0.67%   |
| SPCC                      | 2         | 2      | 0.45%   |
| Phison Electronics        | 2         | 2      | 0.45%   |
| Maxtor                    | 2         | 2      | 0.45%   |
| LITEONIT                  | 2         | 2      | 0.45%   |
| Fujitsu                   | 2         | 2      | 0.45%   |
| Corsair                   | 2         | 2      | 0.45%   |
| Apple                     | 2         | 2      | 0.45%   |
| ZADAK                     | 1         | 1      | 0.22%   |
| XPG                       | 1         | 1      | 0.22%   |
| Team                      | 1         | 2      | 0.22%   |
| Silicon Motion            | 1         | 2      | 0.22%   |
| PNY                       | 1         | 1      | 0.22%   |
| Plextor                   | 1         | 1      | 0.22%   |
| Phison                    | 1         | 1      | 0.22%   |
| Netac                     | 1         | 1      | 0.22%   |
| Micron/Crucial Technology | 1         | 1      | 0.22%   |
| Lexar                     | 1         | 1      | 0.22%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                                       | 6         | 1.21%   |
| Samsung NVMe SSD Drive 1TB                                      | 6         | 1.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB             | 6         | 1.21%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 5         | 1.01%   |
| Samsung SSD 850 EVO 500GB                                       | 5         | 1.01%   |
| Kingston SA400S37240G 240GB SSD                                 | 5         | 1.01%   |
| Seagate ST500LT012-9WS142 500GB                                 | 4         | 0.81%   |
| Samsung SSD 860 EVO 250GB                                       | 4         | 0.81%   |
| Samsung NVMe SSD Drive 512GB                                    | 4         | 0.81%   |
| Samsung HD103SJ 1TB                                             | 4         | 0.81%   |
| Kingston SA400S37120G 120GB SSD                                 | 4         | 0.81%   |
| HGST HTS541010A9E680 1TB                                        | 4         | 0.81%   |
| SK hynix NVMe SSD Drive 256GB                                   | 3         | 0.6%    |
| Seagate ST500LM021-1KJ152 500GB                                 | 3         | 0.6%    |
| Seagate ST500DM002-1BD142 500GB                                 | 3         | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB                                  | 3         | 0.6%    |
| Samsung SSD 970 EVO Plus 500GB                                  | 3         | 0.6%    |
| Samsung SSD 970 EVO Plus 1TB                                    | 3         | 0.6%    |
| Samsung SSD 960 PRO 512GB                                       | 3         | 0.6%    |
| Samsung SSD 860 EVO 500GB                                       | 3         | 0.6%    |
| Samsung MZ7TY128HDHP-000L1 128GB SSD                            | 3         | 0.6%    |
| Kingston SV300S37A120G 120GB SSD                                | 3         | 0.6%    |
| Kingston SUV400S37240G 240GB SSD                                | 3         | 0.6%    |
| HGST HTS721010A9E630 1TB                                        | 3         | 0.6%    |
| Crucial CT500MX500SSD1 500GB                                    | 3         | 0.6%    |
| Apacer AS350 512GB SSD                                          | 3         | 0.6%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 1TB | 3         | 0.6%    |
| A-DATA SX8200PNP 512GB                                          | 3         | 0.6%    |
| WDC WD10EADS-00M2B0 1TB                                         | 2         | 0.4%    |
| WDC PC SN730 SDBQNTY-512G-1001 512GB                            | 2         | 0.4%    |
| WDC PC SN530 SDBPMPZ-256G-1001 256GB                            | 2         | 0.4%    |
| Unknown MMC Card  16GB                                          | 2         | 0.4%    |
| Unknown ArtisanTribute-512GB                                    | 2         | 0.4%    |
| Toshiba NVMe SSD Drive 512GB                                    | 2         | 0.4%    |
| Toshiba MQ01ABF050 500GB                                        | 2         | 0.4%    |
| Toshiba MQ01ABD100 1TB                                          | 2         | 0.4%    |
| Toshiba HDWD130 3TB                                             | 2         | 0.4%    |
| Toshiba DT01ACA100 1TB                                          | 2         | 0.4%    |
| SK hynix NVMe SSD Drive 512GB                                   | 2         | 0.4%    |
| Seagate ST500LT012-1DG142 500GB                                 | 2         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 75     | 35.8%   |
| WDC                 | 39        | 57     | 24.07%  |
| Toshiba             | 17        | 17     | 10.49%  |
| Hitachi             | 16        | 20     | 9.88%   |
| Samsung Electronics | 13        | 16     | 8.02%   |
| HGST                | 12        | 16     | 7.41%   |
| Maxtor              | 2         | 2      | 1.23%   |
| Fujitsu             | 2         | 2      | 1.23%   |
| Unknown             | 1         | 1      | 0.62%   |
| External            | 1         | 1      | 0.62%   |
| Apple               | 1         | 1      | 0.62%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 53        | 64     | 30.29%  |
| Kingston            | 29        | 39     | 16.57%  |
| Crucial             | 16        | 25     | 9.14%   |
| SanDisk             | 11        | 13     | 6.29%   |
| WDC                 | 8         | 11     | 4.57%   |
| A-DATA Technology   | 7         | 12     | 4%      |
| Patriot             | 5         | 6      | 2.86%   |
| Apacer              | 5         | 6      | 2.86%   |
| SK hynix            | 4         | 4      | 2.29%   |
| KingSpec            | 4         | 6      | 2.29%   |
| China               | 4         | 4      | 2.29%   |
| Transcend           | 3         | 6      | 1.71%   |
| Toshiba             | 3         | 4      | 1.71%   |
| Micron Technology   | 3         | 3      | 1.71%   |
| Intel               | 3         | 4      | 1.71%   |
| SPCC                | 2         | 2      | 1.14%   |
| LITEONIT            | 2         | 2      | 1.14%   |
| Gigabyte Technology | 2         | 3      | 1.14%   |
| Corsair             | 2         | 2      | 1.14%   |
| Team                | 1         | 2      | 0.57%   |
| Plextor             | 1         | 1      | 0.57%   |
| Netac               | 1         | 1      | 0.57%   |
| Lexar               | 1         | 1      | 0.57%   |
| Intenso             | 1         | 1      | 0.57%   |
| Integral            | 1         | 1      | 0.57%   |
| i-FlashDisk         | 1         | 1      | 0.57%   |
| ASMT                | 1         | 1      | 0.57%   |
| Apple               | 1         | 1      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 141       | 226    | 36.34%  |
| HDD     | 133       | 208    | 34.28%  |
| NVMe    | 98        | 130    | 25.26%  |
| MMC     | 9         | 9      | 2.32%   |
| Unknown | 7         | 8      | 1.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 223       | 426    | 64.45%  |
| NVMe | 98        | 130    | 28.32%  |
| SAS  | 16        | 16     | 4.62%   |
| MMC  | 9         | 9      | 2.6%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 180       | 281    | 61.02%  |
| 0.51-1.0   | 78        | 103    | 26.44%  |
| 1.01-2.0   | 19        | 25     | 6.44%   |
| 4.01-10.0  | 7         | 7      | 2.37%   |
| 3.01-4.0   | 5         | 5      | 1.69%   |
| 2.01-3.0   | 5         | 12     | 1.69%   |
| 10.01-20.0 | 1         | 1      | 0.34%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 85        | 27.51%  |
| 251-500        | 63        | 20.39%  |
| 501-1000       | 37        | 11.97%  |
| 1-20           | 31        | 10.03%  |
| 1001-2000      | 28        | 9.06%   |
| 51-100         | 20        | 6.47%   |
| More than 3000 | 19        | 6.15%   |
| Unknown        | 10        | 3.24%   |
| 21-50          | 9         | 2.91%   |
| 2001-3000      | 7         | 2.27%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 125       | 39.81%  |
| 21-50          | 44        | 14.01%  |
| 101-250        | 41        | 13.06%  |
| 51-100         | 30        | 9.55%   |
| 251-500        | 22        | 7.01%   |
| 501-1000       | 19        | 6.05%   |
| 1001-2000      | 11        | 3.5%    |
| Unknown        | 10        | 3.18%   |
| More than 3000 | 9         | 2.87%   |
| 2001-3000      | 3         | 0.96%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Crucial CT128MX100SSD1 128GB                        | 2         | 3      | 4.76%   |
| WDC WD60EFRX-68MYMN1 6TB                            | 1         | 1      | 2.38%   |
| WDC WD5002AALX-00J37A0 500GB                        | 1         | 1      | 2.38%   |
| WDC WD5000BPVT-00HXZT1 500GB                        | 1         | 1      | 2.38%   |
| WDC WD5000AAKX-00ERMA0 500GB                        | 1         | 1      | 2.38%   |
| WDC WD2500BEVT-80A23T0 250GB                        | 1         | 1      | 2.38%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 1         | 2      | 2.38%   |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 1      | 2.38%   |
| WDC WD10PURX-64E5EY0 1TB                            | 1         | 1      | 2.38%   |
| WDC WD10EAVS-00D7B1 1TB                             | 1         | 1      | 2.38%   |
| WDC WD10EADS-00M2B0 1TB                             | 1         | 2      | 2.38%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD            | 1         | 2      | 2.38%   |
| Seagate ST98823AS 80GB                              | 1         | 1      | 2.38%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.38%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 2.38%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 2.38%   |
| Seagate ST750LX003-1AC154 752GB                     | 1         | 1      | 2.38%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 1      | 2.38%   |
| Seagate ST340016A 40GB                              | 1         | 2      | 2.38%   |
| Seagate ST320LT012-9WS14C 320GB                     | 1         | 1      | 2.38%   |
| Seagate ST31000528AS 1TB                            | 1         | 1      | 2.38%   |
| Seagate ST1000LM035-1RK172 1TB                      | 1         | 1      | 2.38%   |
| Seagate ST1000DM010-2EP102 1TB                      | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 840 PRO Series 128GB        | 1         | 1      | 2.38%   |
| Samsung Electronics SP0802N 80GB                    | 1         | 1      | 2.38%   |
| Samsung Electronics HD642JJ 640GB                   | 1         | 1      | 2.38%   |
| Samsung Electronics HD501LJ 500GB                   | 1         | 1      | 2.38%   |
| Samsung Electronics HD103SJ 1TB                     | 1         | 1      | 2.38%   |
| Patriot P210 256GB SSD                              | 1         | 1      | 2.38%   |
| Patriot Burst 480GB SSD                             | 1         | 1      | 2.38%   |
| Netac SSD 720GB                                     | 1         | 1      | 2.38%   |
| Micron Technology MTFDDAK128MAY-1AH1ZABHA 128GB SSD | 1         | 1      | 2.38%   |
| Maxtor STM3250310AS 250GB                           | 1         | 1      | 2.38%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 2.38%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 2.38%   |
| Hitachi HDS721680PLA380 80GB                        | 1         | 1      | 2.38%   |
| Hitachi HDS721010DLE630 1TB                         | 1         | 1      | 2.38%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 2.38%   |
| Fujitsu MHT2040AH PL 40GB                           | 1         | 1      | 2.38%   |
| Crucial CT480M500SSD3 480GB                         | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 27.5%   |
| WDC                 | 9         | 12     | 22.5%   |
| Samsung Electronics | 4         | 5      | 10%     |
| Crucial             | 4         | 5      | 10%     |
| Hitachi             | 3         | 3      | 7.5%    |
| Patriot             | 2         | 2      | 5%      |
| Toshiba             | 1         | 2      | 2.5%    |
| Netac               | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 1      | 2.5%    |
| Maxtor              | 1         | 1      | 2.5%    |
| Kingston            | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 37.93%  |
| WDC                 | 9         | 12     | 31.03%  |
| Samsung Electronics | 3         | 4      | 10.34%  |
| Hitachi             | 3         | 3      | 10.34%  |
| Maxtor              | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 28        | 34     | 73.68%  |
| SSD  | 10        | 13     | 26.32%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 157       | 309    | 48.46%  |
| Works    | 129       | 224    | 39.81%  |
| Malfunc  | 37        | 47     | 11.42%  |
| Failed   | 1         | 1      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 199       | 52.23%  |
| AMD                          | 55        | 14.44%  |
| Samsung Electronics          | 41        | 10.76%  |
| SanDisk                      | 13        | 3.41%   |
| SK hynix                     | 11        | 2.89%   |
| Kingston Technology Company  | 10        | 2.62%   |
| Toshiba America Info Systems | 7         | 1.84%   |
| Marvell Technology Group     | 7         | 1.84%   |
| Nvidia                       | 6         | 1.57%   |
| ADATA Technology             | 6         | 1.57%   |
| Phison Electronics           | 5         | 1.31%   |
| KIOXIA                       | 4         | 1.05%   |
| ASMedia Technology           | 4         | 1.05%   |
| VIA Technologies             | 3         | 0.79%   |
| Lenovo                       | 3         | 0.79%   |
| Silicon Motion               | 2         | 0.52%   |
| JMicron Technology           | 2         | 0.52%   |
| Silicon Image                | 1         | 0.26%   |
| Micron/Crucial Technology    | 1         | 0.26%   |
| Adaptec                      | 1         | 0.26%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 38        | 8.82%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 28        | 6.5%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 27        | 6.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 16        | 3.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 13        | 3.02%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 9         | 2.09%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 8         | 1.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 8         | 1.86%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 1.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 7         | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7         | 1.62%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 1.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 6         | 1.39%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 1.39%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.39%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 6         | 1.39%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 6         | 1.39%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 6         | 1.39%   |
| AMD 500 Series Chipset SATA Controller                                         | 6         | 1.39%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 6         | 1.39%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 1.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.16%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 1.16%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 5         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 5         | 1.16%   |
| Samsung NVMe SSD Controller 980                                                | 4         | 0.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 4         | 0.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 0.93%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 4         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 0.93%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 3         | 0.7%    |
| SK hynix PC401 NVMe Solid State Drive 256GB                                    | 3         | 0.7%    |
| SK hynix Non-Volatile memory controller                                        | 3         | 0.7%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 3         | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.7%    |
| Phison E16 PCIe4 NVMe Controller                                               | 3         | 0.7%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 229       | 60.26%  |
| NVMe | 100       | 26.32%  |
| IDE  | 39        | 10.26%  |
| RAID | 11        | 2.89%   |
| SCSI | 1         | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 220       | 74.58%  |
| AMD                   | 74        | 25.08%  |
| Marvell Semiconductor | 1         | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz       | 7         | 2.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 5         | 1.69%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 5         | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 4         | 1.36%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 4         | 1.36%   |
| AMD Ryzen 5 4500U with Radeon Graphics  | 4         | 1.36%   |
| AMD Ryzen 5 3600 6-Core Processor       | 4         | 1.36%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 3         | 1.02%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 3         | 1.02%   |
| Intel Core i7-4710MQ CPU @ 2.50GHz      | 3         | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 3         | 1.02%   |
| Intel Core i5-7300U CPU @ 2.60GHz       | 3         | 1.02%   |
| Intel Core i3-4130 CPU @ 3.40GHz        | 3         | 1.02%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz    | 3         | 1.02%   |
| AMD Ryzen 7 4700U with Radeon Graphics  | 3         | 1.02%   |
| Intel Xeon CPU E3-1241 v3 @ 3.50GHz     | 2         | 0.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz        | 2         | 0.68%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz      | 2         | 0.68%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz      | 2         | 0.68%   |
| Intel Core i7-5600U CPU @ 2.60GHz       | 2         | 0.68%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz      | 2         | 0.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 2         | 0.68%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 2         | 0.68%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz      | 2         | 0.68%   |
| Intel Core i7-4500U CPU @ 1.80GHz       | 2         | 0.68%   |
| Intel Core i7-2620M CPU @ 2.70GHz       | 2         | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 2         | 0.68%   |
| Intel Core i5-9600K CPU @ 3.70GHz       | 2         | 0.68%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz      | 2         | 0.68%   |
| Intel Core i5-5200U CPU @ 2.20GHz       | 2         | 0.68%   |
| Intel Core i5-4690K CPU @ 3.50GHz       | 2         | 0.68%   |
| Intel Core i5-4590 CPU @ 3.30GHz        | 2         | 0.68%   |
| Intel Core i5-4200U CPU @ 1.60GHz       | 2         | 0.68%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 2         | 0.68%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 2         | 0.68%   |
| Intel Core i5-2500 CPU @ 3.30GHz        | 2         | 0.68%   |
| Intel Core i5 CPU M 460 @ 2.53GHz       | 2         | 0.68%   |
| Intel Core i3-6006U CPU @ 2.00GHz       | 2         | 0.68%   |
| Intel Core i3-3217U CPU @ 1.80GHz       | 2         | 0.68%   |
| Intel Core i3-2350M CPU @ 2.30GHz       | 2         | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 72        | 24.41%  |
| Intel Core i7                  | 63        | 21.36%  |
| AMD Ryzen 5                    | 20        | 6.78%   |
| Intel Core i3                  | 19        | 6.44%   |
| AMD Ryzen 7                    | 17        | 5.76%   |
| Other                          | 14        | 4.75%   |
| Intel Core 2 Duo               | 13        | 4.41%   |
| Intel Celeron                  | 12        | 4.07%   |
| Intel Pentium                  | 7         | 2.37%   |
| Intel Xeon                     | 5         | 1.69%   |
| AMD Ryzen 9                    | 5         | 1.69%   |
| AMD Ryzen 7 PRO                | 5         | 1.69%   |
| AMD Phenom II X4               | 4         | 1.36%   |
| AMD Athlon 64 X2               | 4         | 1.36%   |
| Intel Core i9                  | 3         | 1.02%   |
| Intel Atom                     | 3         | 1.02%   |
| Intel Pentium M                | 2         | 0.68%   |
| Intel Celeron Dual-Core        | 2         | 0.68%   |
| AMD FX                         | 2         | 0.68%   |
| AMD A10                        | 2         | 0.68%   |
| Intel Pentium Silver           | 1         | 0.34%   |
| Intel Pentium Gold             | 1         | 0.34%   |
| Intel Pentium Dual-Core        | 1         | 0.34%   |
| Intel Pentium Dual             | 1         | 0.34%   |
| Intel Pentium D                | 1         | 0.34%   |
| Intel Pentium 4                | 1         | 0.34%   |
| Intel Core 2                   | 1         | 0.34%   |
| Intel Celeron M                | 1         | 0.34%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.34%   |
| AMD Ryzen 5 PRO                | 1         | 0.34%   |
| AMD Ryzen 3 PRO                | 1         | 0.34%   |
| AMD Ryzen 3                    | 1         | 0.34%   |
| AMD Phenom II X6               | 1         | 0.34%   |
| AMD E2                         | 1         | 0.34%   |
| AMD E                          | 1         | 0.34%   |
| AMD C-60                       | 1         | 0.34%   |
| AMD Athlon XP                  | 1         | 0.34%   |
| AMD Athlon II Dual-Core        | 1         | 0.34%   |
| AMD A8                         | 1         | 0.34%   |
| AMD A6                         | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 114       | 38.64%  |
| 4       | 97        | 32.88%  |
| 6       | 38        | 12.88%  |
| 8       | 26        | 8.81%   |
| 1       | 10        | 3.39%   |
| 12      | 3         | 1.02%   |
| Unknown | 3         | 1.02%   |
| 16      | 2         | 0.68%   |
| 14      | 1         | 0.34%   |
| 3       | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 294       | 99.66%  |
| 2      | 1         | 0.34%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 200       | 67.57%  |
| 1       | 93        | 31.42%  |
| Unknown | 3         | 1.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 289       | 97.64%  |
| Unknown        | 4         | 1.35%   |
| 32-bit         | 3         | 1.01%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 74        | 24.18%  |
| 0x306c3    | 22        | 7.19%   |
| 0x306a9    | 20        | 6.54%   |
| 0x206a7    | 16        | 5.23%   |
| 0x906e9    | 9         | 2.94%   |
| 0x806ea    | 9         | 2.94%   |
| 0x08600106 | 9         | 2.94%   |
| 0x1067a    | 8         | 2.61%   |
| 0x906ea    | 7         | 2.29%   |
| 0x40651    | 7         | 2.29%   |
| 0x306d4    | 6         | 1.96%   |
| 0x20655    | 6         | 1.96%   |
| 0x08701021 | 6         | 1.96%   |
| 0x806ec    | 5         | 1.63%   |
| 0x806e9    | 5         | 1.63%   |
| 0x806c1    | 5         | 1.63%   |
| 0x6fb      | 5         | 1.63%   |
| 0x506e3    | 5         | 1.63%   |
| 0x08701013 | 5         | 1.63%   |
| 0xa0652    | 4         | 1.31%   |
| 0x6fd      | 4         | 1.31%   |
| 0xa0655    | 3         | 0.98%   |
| 0x406e3    | 3         | 0.98%   |
| 0x08108102 | 3         | 0.98%   |
| 0x05000119 | 3         | 0.98%   |
| 0xa0671    | 2         | 0.65%   |
| 0x906ed    | 2         | 0.65%   |
| 0x90672    | 2         | 0.65%   |
| 0x706a1    | 2         | 0.65%   |
| 0x6d8      | 2         | 0.65%   |
| 0x30678    | 2         | 0.65%   |
| 0x0a50000c | 2         | 0.65%   |
| 0x08600103 | 2         | 0.65%   |
| 0x0810100b | 2         | 0.65%   |
| 0x08001138 | 2         | 0.65%   |
| 0x06003106 | 2         | 0.65%   |
| 0x06000852 | 2         | 0.65%   |
| 0x010000db | 2         | 0.65%   |
| 0xf64      | 1         | 0.33%   |
| 0xf4a      | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 49        | 16.61%  |
| Haswell          | 40        | 13.56%  |
| Zen 2            | 30        | 10.17%  |
| IvyBridge        | 23        | 7.8%    |
| SandyBridge      | 21        | 7.12%   |
| Skylake          | 13        | 4.41%   |
| Core             | 12        | 4.07%   |
| Westmere         | 11        | 3.73%   |
| Penryn           | 9         | 3.05%   |
| Unknown          | 9         | 3.05%   |
| CometLake        | 8         | 2.71%   |
| Broadwell        | 7         | 2.37%   |
| TigerLake        | 6         | 2.03%   |
| K10              | 6         | 2.03%   |
| Zen+             | 5         | 1.69%   |
| Zen 3            | 5         | 1.69%   |
| Zen              | 5         | 1.69%   |
| Silvermont       | 4         | 1.36%   |
| K8 Hammer        | 4         | 1.36%   |
| IceLake          | 4         | 1.36%   |
| Steamroller      | 3         | 1.02%   |
| Piledriver       | 3         | 1.02%   |
| Goldmont plus    | 3         | 1.02%   |
| Bobcat           | 3         | 1.02%   |
| P6               | 2         | 0.68%   |
| NetBurst         | 2         | 0.68%   |
| Bonnell          | 2         | 0.68%   |
| Alderlake Hybrid | 2         | 0.68%   |
| K8 & K10 hybrid  | 1         | 0.34%   |
| K6               | 1         | 0.34%   |
| Goldmont         | 1         | 0.34%   |
| Excavator        | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 172       | 46.24%  |
| Nvidia            | 122       | 32.8%   |
| AMD               | 76        | 20.43%  |
| VIA Technologies  | 1         | 0.27%   |
| ASPEED Technology | 1         | 0.27%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                              | 16        | 4.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 15        | 3.92%   |
| AMD Renoir                                                                    | 15        | 3.92%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 12        | 3.13%   |
| Intel UHD Graphics 620                                                        | 11        | 2.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                       | 11        | 2.87%   |
| Intel Haswell-ULT Integrated Graphics Controller                              | 9         | 2.35%   |
| Intel Core Processor Integrated Graphics Controller                           | 9         | 2.35%   |
| Intel HD Graphics 630                                                         | 7         | 1.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 6         | 1.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                     | 6         | 1.57%   |
| Nvidia GP108M [GeForce MX150]                                                 | 5         | 1.31%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 5         | 1.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                    | 5         | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)           | 5         | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)             | 5         | 1.31%   |
| Intel HD Graphics 620                                                         | 5         | 1.31%   |
| Intel HD Graphics 5500                                                        | 5         | 1.31%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 5         | 1.31%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                            | 4         | 1.04%   |
| Nvidia GP104 [GeForce GTX 1070]                                               | 4         | 1.04%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller   | 4         | 1.04%   |
| Intel HD Graphics 530                                                         | 4         | 1.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 4         | 1.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 4         | 1.04%   |
| Nvidia GP108 [GeForce GT 1030]                                                | 3         | 0.78%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                            | 3         | 0.78%   |
| Nvidia GM107M [GeForce GTX 950M]                                              | 3         | 0.78%   |
| Nvidia GK208B [GeForce GT 710]                                                | 3         | 0.78%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller              | 3         | 0.78%   |
| Intel Skylake GT2 [HD Graphics 520]                                           | 3         | 0.78%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 3         | 0.78%   |
| Intel CometLake-U GT2 [UHD Graphics]                                          | 3         | 0.78%   |
| Intel 4 Series Chipset Integrated Graphics Controller                         | 3         | 0.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 3         | 0.78%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]              | 3         | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 2         | 0.52%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 2         | 0.52%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                         | 2         | 0.52%   |
| Nvidia TU116 [GeForce GTX 1660 Ti]                                            | 2         | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 103       | 34.8%   |
| 1 x Nvidia     | 58        | 19.59%  |
| 1 x AMD        | 58        | 19.59%  |
| Intel + Nvidia | 57        | 19.26%  |
| Intel + AMD    | 8         | 2.7%    |
| AMD + Nvidia   | 5         | 1.69%   |
| 2 x AMD        | 3         | 1.01%   |
| Other          | 1         | 0.34%   |
| 2 x Nvidia     | 1         | 0.34%   |
| 1 x VIA        | 1         | 0.34%   |
| AMD + ASPEED   | 1         | 0.34%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 214       | 71.1%   |
| Proprietary | 77        | 25.58%  |
| Unknown     | 10        | 3.32%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 46%     |
| 1.01-2.0   | 50        | 16.67%  |
| 0.01-0.5   | 36        | 12%     |
| 3.01-4.0   | 23        | 7.67%   |
| 7.01-8.0   | 18        | 6%      |
| 0.51-1.0   | 17        | 5.67%   |
| 5.01-6.0   | 8         | 2.67%   |
| 8.01-16.0  | 7         | 2.33%   |
| 2.01-3.0   | 2         | 0.67%   |
| 4.01-5.0   | 1         | 0.33%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 43        | 12.72%  |
| Dell                    | 40        | 11.83%  |
| Chimei Innolux          | 35        | 10.36%  |
| AU Optronics            | 35        | 10.36%  |
| LG Display              | 24        | 7.1%    |
| Goldstar                | 23        | 6.8%    |
| BOE                     | 21        | 6.21%   |
| Hewlett-Packard         | 13        | 3.85%   |
| Chi Mei Optoelectronics | 11        | 3.25%   |
| AOC                     | 10        | 2.96%   |
| Philips                 | 9         | 2.66%   |
| ViewSonic               | 8         | 2.37%   |
| Sharp                   | 7         | 2.07%   |
| Lenovo                  | 7         | 2.07%   |
| BenQ                    | 6         | 1.78%   |
| PANDA                   | 4         | 1.18%   |
| Apple                   | 4         | 1.18%   |
| Sony                    | 3         | 0.89%   |
| LG Philips              | 3         | 0.89%   |
| Hitachi                 | 3         | 0.89%   |
| Unknown                 | 2         | 0.59%   |
| RoverScan               | 2         | 0.59%   |
| Panasonic               | 2         | 0.59%   |
| Fujitsu Siemens         | 2         | 0.59%   |
| ASUSTek Computer        | 2         | 0.59%   |
| Acer                    | 2         | 0.59%   |
| Toshiba                 | 1         | 0.3%    |
| Tech Concepts           | 1         | 0.3%    |
| Seiko/Epson             | 1         | 0.3%    |
| Plain Tree Systems      | 1         | 0.3%    |
| LG Electronics          | 1         | 0.3%    |
| Lenovo Group Limited    | 1         | 0.3%    |
| KDB                     | 1         | 0.3%    |
| JDI                     | 1         | 0.3%    |
| InfoVision              | 1         | 0.3%    |
| Gigabyte Technology     | 1         | 0.3%    |
| Eizo                    | 1         | 0.3%    |
| CSO                     | 1         | 0.3%    |
| CPT                     | 1         | 0.3%    |
| Belinea                 | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 4         | 1.12%   |
| Goldstar 27GL850 GSM5B80 2560x1440 697x392mm 31.5-inch                    | 3         | 0.84%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 3         | 0.84%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 0.84%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 3         | 0.84%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 338x270mm 17.0-inch             | 2         | 0.56%   |
| Sony TV SNYDB01 1920x1080                                                 | 2         | 0.56%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 2         | 0.56%   |
| Samsung Electronics S32D850 SAM0BCB 2560x1440 708x398mm 32.0-inch         | 2         | 0.56%   |
| Samsung Electronics S24C650 SAM0B18 1920x1200 518x324mm 24.1-inch         | 2         | 0.56%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 2         | 0.56%   |
| Panasonic VVX14T092N00 MEI96A2 2256x1504 285x190mm 13.5-inch              | 2         | 0.56%   |
| LG Display LCD Monitor LGD0685 1920x1080 309x174mm 14.0-inch              | 2         | 0.56%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                   | 2         | 0.56%   |
| Hitachi HISENSE HEC0030 1920x1080 580x330mm 26.3-inch                     | 2         | 0.56%   |
| Hewlett-Packard ZR24w HWP2869 1920x1200 546x352mm 25.6-inch               | 2         | 0.56%   |
| Hewlett-Packard 27es HWP3325 1920x1080 598x336mm 27.0-inch                | 2         | 0.56%   |
| Goldstar ULTRAWIDE GSM7768 3440x1440 800x334mm 34.1-inch                  | 2         | 0.56%   |
| Goldstar MP59G GSM5B34 1920x1080 480x270mm 21.7-inch                      | 2         | 0.56%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 2         | 0.56%   |
| Dell U2719D DEL415A 2560x1440 597x336mm 27.0-inch                         | 2         | 0.56%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                        | 2         | 0.56%   |
| Dell P2418D DELD0C2 2560x1440 526x296mm 23.8-inch                         | 2         | 0.56%   |
| Dell P2314H DEL4098 1920x1080 509x286mm 23.0-inch                         | 2         | 0.56%   |
| Dell 2407WFP DELA017 1920x1200 520x330mm 24.2-inch                        | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch           | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch           | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch          | 2         | 0.56%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch          | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 2         | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO1467 1366x768 309x174mm 14.0-inch  | 2         | 0.56%   |
| BOE LCD Monitor BOE07DB 1920x1080 309x174mm 14.0-inch                     | 2         | 0.56%   |
| BOE LCD Monitor BOE077A 1920x1080 294x165mm 13.3-inch                     | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO36ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch             | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 2         | 0.56%   |
| AU Optronics LCD Monitor AUO206C 1366x768 277x156mm 12.5-inch             | 2         | 0.56%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 136       | 42.63%  |
| 1366x768 (WXGA)    | 44        | 13.79%  |
| 3840x2160 (4K)     | 26        | 8.15%   |
| 1280x1024 (SXGA)   | 21        | 6.58%   |
| 1920x1200 (WUXGA)  | 20        | 6.27%   |
| 2560x1440 (QHD)    | 18        | 5.64%   |
| 1600x900 (HD+)     | 13        | 4.08%   |
| 1280x800 (WXGA)    | 11        | 3.45%   |
| 3440x1440          | 8         | 2.51%   |
| 1680x1050 (WSXGA+) | 7         | 2.19%   |
| 2560x1600          | 5         | 1.57%   |
| 1440x900 (WXGA+)   | 4         | 1.25%   |
| 800x1280           | 1         | 0.31%   |
| 3840x2400          | 1         | 0.31%   |
| 2560x1080          | 1         | 0.31%   |
| 2256x1504          | 1         | 0.31%   |
| 1920x540           | 1         | 0.31%   |
| 1600x1200          | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 80        | 23.32%  |
| 24      | 34        | 9.91%   |
| 13      | 31        | 9.04%   |
| 17      | 28        | 8.16%   |
| 14      | 28        | 8.16%   |
| 27      | 23        | 6.71%   |
| 23      | 18        | 5.25%   |
| 21      | 15        | 4.37%   |
| Unknown | 14        | 4.08%   |
| 12      | 9         | 2.62%   |
| 34      | 7         | 2.04%   |
| 31      | 6         | 1.75%   |
| 19      | 6         | 1.75%   |
| 84      | 5         | 1.46%   |
| 40      | 4         | 1.17%   |
| 16      | 4         | 1.17%   |
| 72      | 3         | 0.87%   |
| 32      | 3         | 0.87%   |
| 25      | 3         | 0.87%   |
| 22      | 3         | 0.87%   |
| 20      | 3         | 0.87%   |
| 18      | 3         | 0.87%   |
| 54      | 2         | 0.58%   |
| 43      | 2         | 0.58%   |
| 33      | 2         | 0.58%   |
| 65      | 1         | 0.29%   |
| 38      | 1         | 0.29%   |
| 29      | 1         | 0.29%   |
| 26      | 1         | 0.29%   |
| 11      | 1         | 0.29%   |
| 10      | 1         | 0.29%   |
| 3       | 1         | 0.29%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 133       | 39.7%   |
| 501-600     | 68        | 20.3%   |
| 201-300     | 31        | 9.25%   |
| 401-500     | 25        | 7.46%   |
| 351-400     | 21        | 6.27%   |
| Unknown     | 14        | 4.18%   |
| 701-800     | 12        | 3.58%   |
| 601-700     | 12        | 3.58%   |
| 1501-2000   | 8         | 2.39%   |
| 801-900     | 5         | 1.49%   |
| 1001-1500   | 3         | 0.9%    |
| 901-1000    | 2         | 0.6%    |
| 1-100       | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 211       | 69.41%  |
| 16/10   | 48        | 15.79%  |
| 5/4     | 17        | 5.59%   |
| Unknown | 12        | 3.95%   |
| 21/9    | 7         | 2.3%    |
| 6/5     | 3         | 0.99%   |
| 4/3     | 3         | 0.99%   |
| 3/2     | 2         | 0.66%   |
| 32/9    | 1         | 0.33%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 78        | 22.94%  |
| 201-250        | 46        | 13.53%  |
| 81-90          | 41        | 12.06%  |
| 301-350        | 24        | 7.06%   |
| 251-300        | 21        | 6.18%   |
| 351-500        | 19        | 5.59%   |
| 71-80          | 18        | 5.29%   |
| 141-150        | 16        | 4.71%   |
| Unknown        | 14        | 4.12%   |
| 151-200        | 13        | 3.82%   |
| 121-130        | 13        | 3.82%   |
| More than 1000 | 11        | 3.24%   |
| 61-70          | 9         | 2.65%   |
| 501-1000       | 7         | 2.06%   |
| 111-120        | 6         | 1.76%   |
| 51-60          | 1         | 0.29%   |
| 41-50          | 1         | 0.29%   |
| 1-40           | 1         | 0.29%   |
| 131-140        | 1         | 0.29%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 112       | 33.94%  |
| 121-160       | 94        | 28.48%  |
| 101-120       | 73        | 22.12%  |
| 161-240       | 23        | 6.97%   |
| Unknown       | 14        | 4.24%   |
| More than 240 | 8         | 2.42%   |
| 1-50          | 6         | 1.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 224       | 74.17%  |
| 2     | 59        | 19.54%  |
| 3     | 9         | 2.98%   |
| 0     | 9         | 2.98%   |
| 4     | 1         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 152       | 34.62%  |
| Realtek Semiconductor             | 147       | 33.49%  |
| Qualcomm Atheros                  | 42        | 9.57%   |
| Broadcom                          | 16        | 3.64%   |
| TP-Link                           | 10        | 2.28%   |
| MediaTek                          | 8         | 1.82%   |
| Ralink                            | 7         | 1.59%   |
| Nvidia                            | 6         | 1.37%   |
| Broadcom Limited                  | 5         | 1.14%   |
| Ralink Technology                 | 4         | 0.91%   |
| Marvell Technology Group          | 4         | 0.91%   |
| Lenovo                            | 4         | 0.91%   |
| Ericsson Business Mobile Networks | 4         | 0.91%   |
| Hewlett-Packard                   | 3         | 0.68%   |
| Fibocom                           | 3         | 0.68%   |
| ASIX Electronics                  | 3         | 0.68%   |
| Sierra Wireless                   | 2         | 0.46%   |
| Samsung Electronics               | 2         | 0.46%   |
| Qualcomm Atheros Communications   | 2         | 0.46%   |
| Microsoft                         | 2         | 0.46%   |
| Huawei Technologies               | 2         | 0.46%   |
| D-Link System                     | 2         | 0.46%   |
| VIA Technologies                  | 1         | 0.23%   |
| Van Ooijen Technische Informatica | 1         | 0.23%   |
| OPPO Electronics                  | 1         | 0.23%   |
| JMicron Technology                | 1         | 0.23%   |
| DisplayLink                       | 1         | 0.23%   |
| D-Link                            | 1         | 0.23%   |
| ASUSTek Computer                  | 1         | 0.23%   |
| Aquantia                          | 1         | 0.23%   |
| Apple                             | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93        | 17.58%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 3.78%   |
| Intel Wireless 8265 / 8275                                        | 13        | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 11        | 2.08%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 11        | 2.08%   |
| Intel Wireless 7260                                               | 10        | 1.89%   |
| Intel Wi-Fi 6 AX200                                               | 10        | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 1.7%    |
| Intel Wireless 7265                                               | 8         | 1.51%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 1.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 1.32%   |
| Intel I211 Gigabit Network Connection                             | 7         | 1.32%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 6         | 1.13%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 1.13%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.95%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 5         | 0.95%   |
| Intel Wireless 3165                                               | 5         | 0.95%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 0.95%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 0.95%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 5         | 0.95%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 4         | 0.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.76%   |
| Intel Wireless 8260                                               | 4         | 0.76%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 0.76%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.76%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 0.76%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.57%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                         | 3         | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.57%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 0.57%   |
| Intel Wireless 3160                                               | 3         | 0.57%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.57%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 115       | 49.78%  |
| Realtek Semiconductor           | 33        | 14.29%  |
| Qualcomm Atheros                | 30        | 12.99%  |
| Broadcom                        | 11        | 4.76%   |
| TP-Link                         | 9         | 3.9%    |
| Ralink                          | 7         | 3.03%   |
| MediaTek                        | 7         | 3.03%   |
| Ralink Technology               | 4         | 1.73%   |
| Fibocom                         | 3         | 1.3%    |
| Sierra Wireless                 | 2         | 0.87%   |
| Qualcomm Atheros Communications | 2         | 0.87%   |
| Microsoft                       | 2         | 0.87%   |
| Broadcom Limited                | 2         | 0.87%   |
| Marvell Technology Group        | 1         | 0.43%   |
| Hewlett-Packard                 | 1         | 0.43%   |
| D-Link System                   | 1         | 0.43%   |
| D-Link                          | 1         | 0.43%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 13        | 5.58%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 4.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 11        | 4.72%   |
| Intel Wireless 7260                                                     | 10        | 4.29%   |
| Intel Wi-Fi 6 AX200                                                     | 10        | 4.29%   |
| Intel Wireless 7265                                                     | 8         | 3.43%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 7         | 3%      |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.15%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 5         | 2.15%   |
| Intel Wireless 3165                                                     | 5         | 2.15%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 5         | 2.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.15%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 4         | 1.72%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 4         | 1.72%   |
| Intel Wireless 8260                                                     | 4         | 1.72%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.29%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.29%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.29%   |
| Intel Wireless 3160                                                     | 3         | 1.29%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 1.29%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 1.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.29%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.29%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.29%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.29%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 3         | 1.29%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                                   | 2         | 0.86%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.86%   |
| TP-Link Archer T4U ver.3                                                | 2         | 0.86%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                               | 2         | 0.86%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.86%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.86%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.86%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.86%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.86%   |
| Ralink RT2500 Wireless 802.11bg                                         | 2         | 0.86%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.86%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 129       | 46.57%  |
| Intel                    | 92        | 33.21%  |
| Qualcomm Atheros         | 19        | 6.86%   |
| Broadcom                 | 8         | 2.89%   |
| Nvidia                   | 6         | 2.17%   |
| Marvell Technology Group | 3         | 1.08%   |
| Lenovo                   | 3         | 1.08%   |
| Broadcom Limited         | 3         | 1.08%   |
| ASIX Electronics         | 3         | 1.08%   |
| VIA Technologies         | 1         | 0.36%   |
| TP-Link                  | 1         | 0.36%   |
| OPPO Electronics         | 1         | 0.36%   |
| MediaTek                 | 1         | 0.36%   |
| JMicron Technology       | 1         | 0.36%   |
| Hewlett-Packard          | 1         | 0.36%   |
| DisplayLink              | 1         | 0.36%   |
| D-Link System            | 1         | 0.36%   |
| ASUSTek Computer         | 1         | 0.36%   |
| Aquantia                 | 1         | 0.36%   |
| Apple                    | 1         | 0.36%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 93        | 32.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 7.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 4.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 3.18%   |
| Intel Ethernet Connection I217-LM                                 | 8         | 2.83%   |
| Intel I211 Gigabit Network Connection                             | 7         | 2.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 2.12%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 2.12%   |
| Intel Ethernet Connection (4) I219-V                              | 5         | 1.77%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 1.77%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 1.41%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 1.41%   |
| Intel 82566MM Gigabit Network Connection                          | 4         | 1.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 1.06%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 1.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.06%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.06%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.06%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.06%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.71%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.71%   |
| Nvidia CK804 Ethernet Controller                                  | 2         | 0.71%   |
| Lenovo ThinkPad TBT3 LAN                                          | 2         | 0.71%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.71%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.71%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.71%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.71%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.71%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.71%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.71%   |
| Intel 82578DM Gigabit Network Connection                          | 2         | 0.71%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 2         | 0.71%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.71%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.35%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.35%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.35%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.35%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 262       | 53.25%  |
| WiFi     | 217       | 44.11%  |
| Modem    | 13        | 2.64%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 166       | 55.15%  |
| Ethernet | 135       | 44.85%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 160       | 54.24%  |
| 1     | 124       | 42.03%  |
| 0     | 6         | 2.03%   |
| 3     | 4         | 1.36%   |
| 6     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 253       | 84.62%  |
| Yes  | 46        | 15.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 47.49%  |
| Cambridge Silicon Radio         | 17        | 9.5%    |
| Realtek Semiconductor           | 15        | 8.38%   |
| Qualcomm Atheros Communications | 12        | 6.7%    |
| Broadcom                        | 11        | 6.15%   |
| IMC Networks                    | 10        | 5.59%   |
| Realtek                         | 4         | 2.23%   |
| Hewlett-Packard                 | 4         | 2.23%   |
| Foxconn / Hon Hai               | 4         | 2.23%   |
| Apple                           | 4         | 2.23%   |
| ASUSTek Computer                | 3         | 1.68%   |
| TP-Link                         | 2         | 1.12%   |
| Edimax Technology               | 2         | 1.12%   |
| Toshiba                         | 1         | 0.56%   |
| Ralink                          | 1         | 0.56%   |
| Lite-On Technology              | 1         | 0.56%   |
| Integrated System Solution      | 1         | 0.56%   |
| Dell                            | 1         | 0.56%   |
| Askey Computer                  | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 42        | 23.46%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 17        | 9.5%    |
| Intel AX201 Bluetooth                                 | 12        | 6.7%    |
| Realtek Bluetooth Radio                               | 10        | 5.59%   |
| Intel AX200 Bluetooth                                 | 9         | 5.03%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 8         | 4.47%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 6         | 3.35%   |
| IMC Networks Bluetooth Device                         | 5         | 2.79%   |
| Realtek Bluetooth Radio                               | 4         | 2.23%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 4         | 2.23%   |
| Intel Wireless-AC 3168 Bluetooth                      | 3         | 1.68%   |
| Intel Bluetooth Device                                | 3         | 1.68%   |
| Intel AX210 Bluetooth                                 | 3         | 1.68%   |
| HP Broadcom 2070 Bluetooth Combo                      | 3         | 1.68%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]      | 3         | 1.68%   |
| Apple Bluetooth Host Controller                       | 3         | 1.68%   |
| TP-Link UB500 Adapter                                 | 2         | 1.12%   |
| Realtek RTL8723B Bluetooth                            | 2         | 1.12%   |
| Realtek  Bluetooth 4.2 Adapter                        | 2         | 1.12%   |
| Qualcomm Atheros  Bluetooth Device                    | 2         | 1.12%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2         | 1.12%   |
| IMC Networks Bluetooth Radio                          | 2         | 1.12%   |
| Foxconn / Hon Hai Wireless_Device                     | 2         | 1.12%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 2         | 1.12%   |
| Edimax Bluetooth Adapter                              | 2         | 1.12%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 2         | 1.12%   |
| Broadcom BCM2045B (BDC-2.1)                           | 2         | 1.12%   |
| Broadcom BCM2045 Bluetooth                            | 2         | 1.12%   |
| ASUS ASUS USB-BT500                                   | 2         | 1.12%   |
| Toshiba Bluetooth USB Host Controller                 | 1         | 0.56%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.56%   |
| Ralink RT3290 Bluetooth                               | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth                     | 1         | 0.56%   |
| Lite-On Bluetooth Device                              | 1         | 0.56%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 0.56%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter | 1         | 0.56%   |
| IMC Networks Wireless_Device                          | 1         | 0.56%   |
| IMC Networks BCM20702A0                               | 1         | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter     | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 214       | 50.71%  |
| AMD                     | 88        | 20.85%  |
| Nvidia                  | 76        | 18.01%  |
| C-Media Electronics     | 8         | 1.9%    |
| Kingston Technology     | 5         | 1.18%   |
| Lenovo                  | 4         | 0.95%   |
| Razer USA               | 3         | 0.71%   |
| Logitech                | 3         | 0.71%   |
| TerraTec Electronic     | 2         | 0.47%   |
| SteelSeries ApS         | 2         | 0.47%   |
| Realtek Semiconductor   | 2         | 0.47%   |
| JMTek                   | 2         | 0.47%   |
| Focusrite-Novation      | 2         | 0.47%   |
| VIA Technologies        | 1         | 0.24%   |
| Texas Instruments       | 1         | 0.24%   |
| Syntek                  | 1         | 0.24%   |
| Samson Technologies     | 1         | 0.24%   |
| Roland                  | 1         | 0.24%   |
| Micronas                | 1         | 0.24%   |
| Mark of the Unicorn     | 1         | 0.24%   |
| M-Audio                 | 1         | 0.24%   |
| Creative Labs           | 1         | 0.24%   |
| BEHRINGER International | 1         | 0.24%   |
| ASUSTek Computer        | 1         | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 28        | 5.65%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 27        | 5.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 22        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 21        | 4.23%   |
| Intel Sunrise Point-LP HD Audio                                            | 20        | 4.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 17        | 3.43%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 16        | 3.23%   |
| AMD Starship/Matisse HD Audio Controller                                   | 15        | 3.02%   |
| Intel Cannon Lake PCH cAVS                                                 | 12        | 2.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 11        | 2.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10        | 2.02%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 2.02%   |
| Intel Haswell-ULT HD Audio Controller                                      | 9         | 1.81%   |
| Intel 8 Series HD Audio Controller                                         | 9         | 1.81%   |
| Nvidia TU106 High Definition Audio Controller                              | 8         | 1.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8         | 1.61%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 7         | 1.41%   |
| Intel Broadwell-U Audio Controller                                         | 7         | 1.41%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 1.41%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 1.41%   |
| Nvidia GP104 High Definition Audio Controller                              | 6         | 1.21%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 1.21%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 1.21%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 1.21%   |
| AMD FCH Azalia Controller                                                  | 6         | 1.21%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.01%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.01%   |
| Intel CM238 HD Audio Controller                                            | 5         | 1.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 5         | 1.01%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 5         | 1.01%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 0.81%   |
| Kingston Technology HyperX 7.1 Audio                                       | 4         | 0.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 0.6%    |
| Nvidia GP108 High Definition Audio Controller                              | 3         | 0.6%    |
| Nvidia GP102 HDMI Audio Controller                                         | 3         | 0.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 0.6%    |
| Nvidia GK104 HDMI Audio Controller                                         | 3         | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 21.15%  |
| SK hynix            | 34        | 16.35%  |
| Kingston            | 25        | 12.02%  |
| Micron Technology   | 21        | 10.1%   |
| Unknown             | 19        | 9.13%   |
| G.Skill             | 17        | 8.17%   |
| Crucial             | 15        | 7.21%   |
| Corsair             | 5         | 2.4%    |
| Ramaxel Technology  | 4         | 1.92%   |
| A-DATA Technology   | 3         | 1.44%   |
| Unknown (ABCD)      | 2         | 0.96%   |
| Patriot             | 2         | 0.96%   |
| Nanya Technology    | 2         | 0.96%   |
| Elpida              | 2         | 0.96%   |
| ASint Technology    | 2         | 0.96%   |
| Apacer              | 2         | 0.96%   |
| Wilk                | 1         | 0.48%   |
| Unifosa             | 1         | 0.48%   |
| Team                | 1         | 0.48%   |
| Silicon Power       | 1         | 0.48%   |
| Qimonda             | 1         | 0.48%   |
| GOODRAM             | 1         | 0.48%   |
| AMD                 | 1         | 0.48%   |
| Aeneon              | 1         | 0.48%   |
| Unknown             | 1         | 0.48%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 2.19%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 3         | 1.32%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 2         | 0.88%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.88%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.88%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 2         | 0.88%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.88%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.88%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.88%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.88%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.88%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.88%   |
| Samsung RAM M471A1G44AB0-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.88%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s              | 2         | 0.88%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.88%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 2         | 0.88%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.88%   |
| Crucial RAM BLS8G4D240FSB.16FBR2 8GB DIMM DDR4 2400MT/s          | 2         | 0.88%   |
| Wilk RAM IRX3200D464L16SA/8G 8GB DIMM DDR4 3200MT/s              | 1         | 0.44%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 1         | 0.44%   |
| Unknown RAM Module 8192MB DIMM DDR3 1600MT/s                     | 1         | 0.44%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.44%   |
| Unknown RAM Module 512MB DIMM                                    | 1         | 0.44%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 4096MB Row Of Chips LPDDR3 1867MT/s           | 1         | 0.44%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 1         | 0.44%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.44%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.44%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 0.44%   |
| Unknown RAM Module 256MB DIMM                                    | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 1         | 0.44%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 1         | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR3 800MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 0.44%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1         | 0.44%   |
| Unknown RAM Module 1024MB DIMM                                   | 1         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 85        | 48.57%  |
| DDR3    | 59        | 33.71%  |
| DDR2    | 9         | 5.14%   |
| SDRAM   | 7         | 4%      |
| LPDDR4  | 5         | 2.86%   |
| Unknown | 5         | 2.86%   |
| LPDDR3  | 2         | 1.14%   |
| DDR     | 2         | 1.14%   |
| LPDDR5  | 1         | 0.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 93        | 53.76%  |
| DIMM         | 72        | 41.62%  |
| Row Of Chips | 8         | 4.62%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 76        | 40%     |
| 4096  | 51        | 26.84%  |
| 16384 | 24        | 12.63%  |
| 2048  | 20        | 10.53%  |
| 1024  | 8         | 4.21%   |
| 32768 | 5         | 2.63%   |
| 512   | 5         | 2.63%   |
| 256   | 1         | 0.53%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 40        | 20.41%  |
| 2667    | 31        | 15.82%  |
| 3200    | 28        | 14.29%  |
| 1333    | 16        | 8.16%   |
| 2400    | 11        | 5.61%   |
| 3600    | 7         | 3.57%   |
| 2133    | 7         | 3.57%   |
| 1334    | 7         | 3.57%   |
| Unknown | 7         | 3.57%   |
| 667     | 5         | 2.55%   |
| 3266    | 4         | 2.04%   |
| 800     | 4         | 2.04%   |
| 4267    | 3         | 1.53%   |
| 3666    | 3         | 1.53%   |
| 1067    | 3         | 1.53%   |
| 4199    | 2         | 1.02%   |
| 1867    | 2         | 1.02%   |
| 6400    | 1         | 0.51%   |
| 4133    | 1         | 0.51%   |
| 3800    | 1         | 0.51%   |
| 3733    | 1         | 0.51%   |
| 3334    | 1         | 0.51%   |
| 3000    | 1         | 0.51%   |
| 2933    | 1         | 0.51%   |
| 2733    | 1         | 0.51%   |
| 2666    | 1         | 0.51%   |
| 2134    | 1         | 0.51%   |
| 1866    | 1         | 0.51%   |
| 1800    | 1         | 0.51%   |
| 1066    | 1         | 0.51%   |
| 975     | 1         | 0.51%   |
| 533     | 1         | 0.51%   |
| 400     | 1         | 0.51%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Brother Industries              | 2         | 25%     |
| Seiko Epson                     | 1         | 12.5%   |
| Samsung Electronics             | 1         | 12.5%   |
| QinHeng Electronics             | 1         | 12.5%   |
| Konica Minolta                  | 1         | 12.5%   |
| Hewlett-Packard                 | 1         | 12.5%   |
| cab Produkttechnik GmbH & Co KG | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson Thermal Receipt Printer [TM-T20] | 1         | 12.5%   |
| Samsung SCX-3400 Series                      | 1         | 12.5%   |
| QinHeng CH340S                               | 1         | 12.5%   |
| Konica Minolta Printer                       | 1         | 12.5%   |
| HP Smart Tank 750 series                     | 1         | 12.5%   |
| cab Produkttechnik GmbH & Co KG EOS2/300     | 1         | 12.5%   |
| Brother HL-4140CN series                     | 1         | 12.5%   |
| Brother DCP-L2510D series                    | 1         | 12.5%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Seiko Epson Perfection 660                          | 1         | 50%     |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 37        | 21.51%  |
| IMC Networks                           | 16        | 9.3%    |
| Microdia                               | 15        | 8.72%   |
| Realtek Semiconductor                  | 13        | 7.56%   |
| Sunplus Innovation Technology          | 12        | 6.98%   |
| Logitech                               | 11        | 6.4%    |
| Bison Electronics                      | 11        | 6.4%    |
| Lite-On Technology                     | 7         | 4.07%   |
| Silicon Motion                         | 5         | 2.91%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 2.91%   |
| Apple                                  | 5         | 2.91%   |
| Acer                                   | 5         | 2.91%   |
| Syntek                                 | 4         | 2.33%   |
| Suyin                                  | 4         | 2.33%   |
| Luxvisions Innotech Limited            | 4         | 2.33%   |
| Quanta                                 | 2         | 1.16%   |
| Lenovo                                 | 2         | 1.16%   |
| Arkmicro Technologies                  | 2         | 1.16%   |
| Alcor Micro                            | 2         | 1.16%   |
| Z-Star Microelectronics                | 1         | 0.58%   |
| Xiaomi                                 | 1         | 0.58%   |
| Tripath Technology                     | 1         | 0.58%   |
| Sonix Technology                       | 1         | 0.58%   |
| Samsung Electronics                    | 1         | 0.58%   |
| Microsoft                              | 1         | 0.58%   |
| LG Electronics                         | 1         | 0.58%   |
| Importek                               | 1         | 0.58%   |
| Huddly                                 | 1         | 0.58%   |
| Creative Technology                    | 1         | 0.58%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 5.17%   |
| Chicony Integrated Camera                               | 7         | 4.02%   |
| Lite-On Integrated Camera                               | 6         | 3.45%   |
| IMC Networks Integrated Camera                          | 5         | 2.87%   |
| Realtek USB Camera                                      | 4         | 2.3%    |
| Bison Integrated Camera                                 | 4         | 2.3%    |
| Logitech Webcam C930e                                   | 3         | 1.72%   |
| Logitech HD Webcam C525                                 | 3         | 1.72%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 3         | 1.72%   |
| Chicony Lenovo Integrated Camera (0.3MP)                | 3         | 1.72%   |
| Chicony Integrated HP HD Webcam                         | 3         | 1.72%   |
| Chicony FJ Camera                                       | 3         | 1.72%   |
| Syntek Integrated Camera                                | 2         | 1.15%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 1.15%   |
| Sunplus Asus Webcam                                     | 2         | 1.15%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.] | 2         | 1.15%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.15%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.15%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 2         | 1.15%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 2         | 1.15%   |
| Logitech Webcam C270                                    | 2         | 1.15%   |
| Logitech HD Pro Webcam C920                             | 2         | 1.15%   |
| Chicony USB2.0 VGA UVC WebCam                           | 2         | 1.15%   |
| Chicony ThinkPad T490 Webcam                            | 2         | 1.15%   |
| Chicony Integrated Camera (1280x720@30)                 | 2         | 1.15%   |
| Chicony HP Wide Vision HD Camera                        | 2         | 1.15%   |
| Chicony HP HD Webcam                                    | 2         | 1.15%   |
| Arkmicro USB2.0 PC CAMERA                               | 2         | 1.15%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 2         | 1.15%   |
| Apple FaceTime HD Camera                                | 2         | 1.15%   |
| Z-Star A4 TECH USB2.0 PC Camera E                       | 1         | 0.57%   |
| Xiaomi Mi 9 Lite                                        | 1         | 0.57%   |
| Tripath USB Camera                                      | 1         | 0.57%   |
| Syntek USB2.0 UVC PC Camera                             | 1         | 0.57%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.57%   |
| Suyin USB Webcam                                        | 1         | 0.57%   |
| Suyin Integrated_Webcam_HD                              | 1         | 0.57%   |
| Suyin HD WebCam                                         | 1         | 0.57%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 1         | 0.57%   |
| Sunplus Laptop_Integrated_Webcam_HD                     | 1         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 20        | 40.82%  |
| Synaptics                          | 13        | 26.53%  |
| Upek                               | 4         | 8.16%   |
| STMicroelectronics                 | 4         | 8.16%   |
| Shenzhen Goodix Technology         | 4         | 8.16%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.04%   |
| LighTuning Technology              | 1         | 2.04%   |
| Elan Microelectronics              | 1         | 2.04%   |
| AuthenTec                          | 1         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 5         | 10.2%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 5         | 10.2%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 5         | 10.2%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 4         | 8.16%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 4         | 8.16%   |
| STMicroelectronics Fingerprint Reader                           | 4         | 8.16%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 6.12%   |
| Synaptics WBDI                                                  | 3         | 6.12%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 4.08%   |
| Shenzhen Goodix  FingerPrint Device                             | 2         | 4.08%   |
| Shenzhen Goodix FingerPrint                                     | 2         | 4.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 2.04%   |
| Validity Sensors VFS101 Fingerprint Reader                      | 1         | 2.04%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 1         | 2.04%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.04%   |
| Synaptics UWP WBDI                                              | 1         | 2.04%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 1         | 2.04%   |
| Elan ELAN:Fingerprint                                           | 1         | 2.04%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 25        | 41.67%  |
| OmniKey               | 19        | 31.67%  |
| Gemalto (was Gemplus) | 7         | 11.67%  |
| Lenovo                | 3         | 5%      |
| Broadcom              | 3         | 5%      |
| SCM Microsystems      | 1         | 1.67%   |
| O2 Micro              | 1         | 1.67%   |
| Clay Logic            | 1         | 1.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 21        | 35%     |
| OmniKey CardMan 1021                                   | 16        | 26.67%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader      | 6         | 10%     |
| Alcor Micro Watchdata W 1981                           | 4         | 6.67%   |
| OmniKey CardMan 4321                                   | 3         | 5%      |
| Lenovo Integrated Smart Card Reader                    | 3         | 5%      |
| Broadcom 58200                                         | 3         | 5%      |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader | 1         | 1.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                   | 1         | 1.67%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 1.67%   |
| Clay Logic Nitrokey Start                              | 1         | 1.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 192       | 63.58%  |
| 1     | 86        | 28.48%  |
| 2     | 21        | 6.95%   |
| 3     | 3         | 0.99%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 49        | 36.3%   |
| Graphics card            | 35        | 25.93%  |
| Chipcard                 | 29        | 21.48%  |
| Net/wireless             | 6         | 4.44%   |
| Multimedia controller    | 3         | 2.22%   |
| Communication controller | 3         | 2.22%   |
| Camera                   | 3         | 2.22%   |
| Net/ethernet             | 2         | 1.48%   |
| Card reader              | 2         | 1.48%   |
| Sound                    | 1         | 0.74%   |
| Modem                    | 1         | 0.74%   |
| Bluetooth                | 1         | 0.74%   |

