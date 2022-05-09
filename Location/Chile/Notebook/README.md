Linux in Chile - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Chile.

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

Total: 629

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 2560p             | [c275c52e93](https://linux-hardware.org/?probe=c275c52e93) | May 04, 2022 |
| HP            | EliteBook 2560p             | [799038a9eb](https://linux-hardware.org/?probe=799038a9eb) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [61e54407f3](https://linux-hardware.org/?probe=61e54407f3) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [7d0cabeccf](https://linux-hardware.org/?probe=7d0cabeccf) | May 04, 2022 |
| HP            | Pavilion g4                 | [afad13fa01](https://linux-hardware.org/?probe=afad13fa01) | May 04, 2022 |
| HP            | Pavilion g4                 | [2124f7a6c7](https://linux-hardware.org/?probe=2124f7a6c7) | May 04, 2022 |
| Lenovo        | ThinkPad T61 7659A39        | [e5c32846e2](https://linux-hardware.org/?probe=e5c32846e2) | Apr 30, 2022 |
| Acer          | Aspire E5-411G              | [0629e76746](https://linux-hardware.org/?probe=0629e76746) | Apr 30, 2022 |
| HP            | Pavilion 14                 | [84bde5e223](https://linux-hardware.org/?probe=84bde5e223) | Apr 29, 2022 |
| HP            | Pavilion g4                 | [d225cb6b3d](https://linux-hardware.org/?probe=d225cb6b3d) | Apr 28, 2022 |
| HP            | Pavilion g4                 | [a10918283d](https://linux-hardware.org/?probe=a10918283d) | Apr 28, 2022 |
| Intel         | Unknown                     | [41b673dda8](https://linux-hardware.org/?probe=41b673dda8) | Apr 26, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [6fbbf00053](https://linux-hardware.org/?probe=6fbbf00053) | Apr 23, 2022 |
| Lenovo        | IdeaPadFlex 15 20309        | [6dac014a49](https://linux-hardware.org/?probe=6dac014a49) | Apr 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [4e2119abc8](https://linux-hardware.org/?probe=4e2119abc8) | Apr 21, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d43a69ef63](https://linux-hardware.org/?probe=d43a69ef63) | Apr 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [28897f0c7b](https://linux-hardware.org/?probe=28897f0c7b) | Apr 13, 2022 |
| ASUSTek       | X405UQ                      | [4b63447e77](https://linux-hardware.org/?probe=4b63447e77) | Apr 10, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [4c367d8a9c](https://linux-hardware.org/?probe=4c367d8a9c) | Apr 08, 2022 |
| Dell          | Vostro A860                 | [15ce9e1f63](https://linux-hardware.org/?probe=15ce9e1f63) | Apr 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [4ad9fe021c](https://linux-hardware.org/?probe=4ad9fe021c) | Mar 31, 2022 |
| Dell          | Latitude E5450              | [776f0672a0](https://linux-hardware.org/?probe=776f0672a0) | Mar 23, 2022 |
| Dell          | Latitude E5450              | [fb7f18d5a2](https://linux-hardware.org/?probe=fb7f18d5a2) | Mar 23, 2022 |
| HUAWEI        | KLVL-WXX9                   | [95acb8d0af](https://linux-hardware.org/?probe=95acb8d0af) | Mar 21, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [95c6b15672](https://linux-hardware.org/?probe=95c6b15672) | Mar 14, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [82cfb46909](https://linux-hardware.org/?probe=82cfb46909) | Mar 13, 2022 |
| Packard Be... | EasyNote MH35               | [66bff1bcfd](https://linux-hardware.org/?probe=66bff1bcfd) | Mar 08, 2022 |
| ASUSTek       | G752VY                      | [379733b3e7](https://linux-hardware.org/?probe=379733b3e7) | Mar 07, 2022 |
| Elife         | series                      | [dddf04aa69](https://linux-hardware.org/?probe=dddf04aa69) | Mar 05, 2022 |
| Elife         | series                      | [979e43c05a](https://linux-hardware.org/?probe=979e43c05a) | Mar 05, 2022 |
| HP            | 2140                        | [6956607bfd](https://linux-hardware.org/?probe=6956607bfd) | Mar 02, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2f1bb56767](https://linux-hardware.org/?probe=2f1bb56767) | Feb 28, 2022 |
| Lenovo        | ThinkPad T490 20RXS0VX00    | [8f42f6fd5f](https://linux-hardware.org/?probe=8f42f6fd5f) | Feb 28, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [8dfdb07f98](https://linux-hardware.org/?probe=8dfdb07f98) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Lenovo        | ThinkPad T495 20NJ0004US    | [d8002e9eae](https://linux-hardware.org/?probe=d8002e9eae) | Feb 23, 2022 |
| Google        | Barla                       | [12180ab1ff](https://linux-hardware.org/?probe=12180ab1ff) | Feb 22, 2022 |
| Toshiba       | Satellite L505              | [16e608fb6b](https://linux-hardware.org/?probe=16e608fb6b) | Feb 22, 2022 |
| HP            | ENVY 15                     | [9758bb9b66](https://linux-hardware.org/?probe=9758bb9b66) | Feb 20, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [46021e669f](https://linux-hardware.org/?probe=46021e669f) | Feb 17, 2022 |
| Apple         | MacBookPro11,3              | [4de3659979](https://linux-hardware.org/?probe=4de3659979) | Feb 16, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [c81bbf6c93](https://linux-hardware.org/?probe=c81bbf6c93) | Feb 16, 2022 |
| Apple         | MacBookPro11,3              | [309f440466](https://linux-hardware.org/?probe=309f440466) | Feb 15, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [81f2a365be](https://linux-hardware.org/?probe=81f2a365be) | Feb 13, 2022 |
| HP            | Laptop 15-da0xxx            | [18fa19a4f0](https://linux-hardware.org/?probe=18fa19a4f0) | Feb 10, 2022 |
| HP            | EliteBook 840 G6            | [dae40dba1f](https://linux-hardware.org/?probe=dae40dba1f) | Feb 09, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3060acc083](https://linux-hardware.org/?probe=3060acc083) | Jan 22, 2022 |
| Acer          | Aspire ES1-111M             | [02368f5bb1](https://linux-hardware.org/?probe=02368f5bb1) | Jan 22, 2022 |
| Lenovo        | G400 20235                  | [cba5cda239](https://linux-hardware.org/?probe=cba5cda239) | Jan 21, 2022 |
| HP            | Laptop 15-da1xxx            | [d6706833ff](https://linux-hardware.org/?probe=d6706833ff) | Jan 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [c00dd7c570](https://linux-hardware.org/?probe=c00dd7c570) | Jan 18, 2022 |
| Dell          | Inspiron 3480               | [ca729da91f](https://linux-hardware.org/?probe=ca729da91f) | Jan 16, 2022 |
| Lenovo        | ThinkPad T480 20L6A0UGCL    | [e9dbb29c83](https://linux-hardware.org/?probe=e9dbb29c83) | Jan 16, 2022 |
| Acer          | AOD255E                     | [cf1f3ab0e0](https://linux-hardware.org/?probe=cf1f3ab0e0) | Jan 13, 2022 |
| HP            | Pavilion 15                 | [95f3d87b66](https://linux-hardware.org/?probe=95f3d87b66) | Jan 09, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [edc40344ef](https://linux-hardware.org/?probe=edc40344ef) | Jan 08, 2022 |
| HONOR         | NBR-WAX9                    | [979f80197d](https://linux-hardware.org/?probe=979f80197d) | Jan 07, 2022 |
| Sony          | SVE14A390X                  | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | EliteBook 6930p             | [0346ff374d](https://linux-hardware.org/?probe=0346ff374d) | Dec 26, 2021 |
| Acer          | Aspire E1-531               | [d1d6054fc3](https://linux-hardware.org/?probe=d1d6054fc3) | Dec 22, 2021 |
| Google        | Barla                       | [cfdb4935cd](https://linux-hardware.org/?probe=cfdb4935cd) | Dec 21, 2021 |
| Google        | Barla                       | [0629410759](https://linux-hardware.org/?probe=0629410759) | Dec 21, 2021 |
| HP            | EliteBook 840 G6            | [46dab8c74a](https://linux-hardware.org/?probe=46dab8c74a) | Dec 16, 2021 |
| Samsung       | R510/P510                   | [37a9793570](https://linux-hardware.org/?probe=37a9793570) | Dec 08, 2021 |
| Dell          | Inspiron 14-3467            | [c53e56384e](https://linux-hardware.org/?probe=c53e56384e) | Dec 07, 2021 |
| Samsung       | R510/P510                   | [f55c0c88cc](https://linux-hardware.org/?probe=f55c0c88cc) | Dec 07, 2021 |
| Lenovo        | ThinkPad T460 20FMA03MCL    | [aecb392c83](https://linux-hardware.org/?probe=aecb392c83) | Dec 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [18da52385a](https://linux-hardware.org/?probe=18da52385a) | Dec 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [db4aacc50a](https://linux-hardware.org/?probe=db4aacc50a) | Dec 03, 2021 |
| Acer          | Swift SF113-31              | [f1e3d8c722](https://linux-hardware.org/?probe=f1e3d8c722) | Nov 29, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [baa3bf4a04](https://linux-hardware.org/?probe=baa3bf4a04) | Nov 27, 2021 |
| Dell          | Inspiron M5010              | [489679b294](https://linux-hardware.org/?probe=489679b294) | Nov 27, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | [93b6cabcb6](https://linux-hardware.org/?probe=93b6cabcb6) | Nov 25, 2021 |
| HP            | 245 G6                      | [103da5dd76](https://linux-hardware.org/?probe=103da5dd76) | Nov 25, 2021 |
| Acer          | Aspire V5-471P              | [bf3b81cbb6](https://linux-hardware.org/?probe=bf3b81cbb6) | Nov 20, 2021 |
| HP            | 250 G5 Notebook PC          | [befb5b9afe](https://linux-hardware.org/?probe=befb5b9afe) | Nov 18, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [787fc2d581](https://linux-hardware.org/?probe=787fc2d581) | Nov 18, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [d26e2fac89](https://linux-hardware.org/?probe=d26e2fac89) | Nov 17, 2021 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [10a3cb9d12](https://linux-hardware.org/?probe=10a3cb9d12) | Nov 15, 2021 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | [d0f383a016](https://linux-hardware.org/?probe=d0f383a016) | Nov 13, 2021 |
| Unknown       | Unknown                     | [a61385548e](https://linux-hardware.org/?probe=a61385548e) | Nov 13, 2021 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [8b26cea464](https://linux-hardware.org/?probe=8b26cea464) | Nov 13, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6S... | [835c948f68](https://linux-hardware.org/?probe=835c948f68) | Nov 13, 2021 |
| Samsung       | 550P5C/550P7C               | [31bc59dcb9](https://linux-hardware.org/?probe=31bc59dcb9) | Nov 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [ab746b7399](https://linux-hardware.org/?probe=ab746b7399) | Nov 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [258e2f1594](https://linux-hardware.org/?probe=258e2f1594) | Nov 08, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1dd0c3ba0a](https://linux-hardware.org/?probe=1dd0c3ba0a) | Nov 05, 2021 |
| HP            | 250 G5 Notebook PC          | [d6eff141a3](https://linux-hardware.org/?probe=d6eff141a3) | Nov 04, 2021 |
| Acer          | Aspire ES1-311              | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| Dell          | Vostro 3500                 | [befb41472e](https://linux-hardware.org/?probe=befb41472e) | Oct 23, 2021 |
| Samsung       | 550P5C/550P7C               | [2713972f14](https://linux-hardware.org/?probe=2713972f14) | Oct 22, 2021 |
| HP            | 250 G6 Notebook PC          | [7076268ecc](https://linux-hardware.org/?probe=7076268ecc) | Oct 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f7524634b9](https://linux-hardware.org/?probe=f7524634b9) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | [e51cebc629](https://linux-hardware.org/?probe=e51cebc629) | Oct 16, 2021 |
| HP            | Compaq CQ45                 | [18a1e9d294](https://linux-hardware.org/?probe=18a1e9d294) | Oct 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [06b7518f72](https://linux-hardware.org/?probe=06b7518f72) | Oct 14, 2021 |
| Acer          | Aspire ES1-311              | [8f1dd3ce3a](https://linux-hardware.org/?probe=8f1dd3ce3a) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | [a0e3e93f48](https://linux-hardware.org/?probe=a0e3e93f48) | Oct 12, 2021 |
| Acer          | Aspire ES1-311              | [df266accf1](https://linux-hardware.org/?probe=df266accf1) | Oct 12, 2021 |
| ASUSTek       | X302LJ                      | [ad35db71c7](https://linux-hardware.org/?probe=ad35db71c7) | Oct 12, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [fc28e4f7f8](https://linux-hardware.org/?probe=fc28e4f7f8) | Oct 10, 2021 |
| HP            | x2 210                      | [ccf01919ab](https://linux-hardware.org/?probe=ccf01919ab) | Oct 09, 2021 |
| HP            | x2 210                      | [a35274c0a7](https://linux-hardware.org/?probe=a35274c0a7) | Oct 09, 2021 |
| HP            | Notebook                    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | Notebook                    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Alienware     | M17xR3                      | [740de1796c](https://linux-hardware.org/?probe=740de1796c) | Oct 05, 2021 |
| Dell          | Inspiron N5110              | [8ea6adfced](https://linux-hardware.org/?probe=8ea6adfced) | Oct 03, 2021 |
| ASUSTek       | X555LB                      | [3af223c792](https://linux-hardware.org/?probe=3af223c792) | Sep 30, 2021 |
| Dell          | G3 3590                     | [519cea3f38](https://linux-hardware.org/?probe=519cea3f38) | Sep 25, 2021 |
| Dell          | G3 3590                     | [bb25c895cf](https://linux-hardware.org/?probe=bb25c895cf) | Sep 25, 2021 |
| ASUSTek       | X302LJ                      | [281beb5fe7](https://linux-hardware.org/?probe=281beb5fe7) | Sep 23, 2021 |
| Acer          | Aspire ES1-572              | [36c622eabc](https://linux-hardware.org/?probe=36c622eabc) | Sep 21, 2021 |
| Acer          | Aspire ES1-572              | [0ce8da0fe0](https://linux-hardware.org/?probe=0ce8da0fe0) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [079bf76915](https://linux-hardware.org/?probe=079bf76915) | Sep 18, 2021 |
| HP            | EliteBook 840 G5            | [68305a2ede](https://linux-hardware.org/?probe=68305a2ede) | Sep 15, 2021 |
| Dell          | Inspiron 5459               | [ef87caa5ba](https://linux-hardware.org/?probe=ef87caa5ba) | Sep 12, 2021 |
| Dell          | Inspiron 5459               | [feea6f3fec](https://linux-hardware.org/?probe=feea6f3fec) | Sep 11, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [15ed5db330](https://linux-hardware.org/?probe=15ed5db330) | Sep 09, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | [890790d388](https://linux-hardware.org/?probe=890790d388) | Sep 07, 2021 |
| ASUSTek       | TUF Gaming FX506LI_FX506... | [341d88eae9](https://linux-hardware.org/?probe=341d88eae9) | Sep 07, 2021 |
| Dell          | Inspiron N5110              | [a8f9c859be](https://linux-hardware.org/?probe=a8f9c859be) | Sep 05, 2021 |
| Dell          | Inspiron N5110              | [3c5b6aa997](https://linux-hardware.org/?probe=3c5b6aa997) | Sep 05, 2021 |
| Acer          | Swift SF314-59              | [f6df33267b](https://linux-hardware.org/?probe=f6df33267b) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | [436287e7dc](https://linux-hardware.org/?probe=436287e7dc) | Sep 02, 2021 |
| Lenovo        | G480 20156                  | [a89f3e4acf](https://linux-hardware.org/?probe=a89f3e4acf) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | [d2804fad00](https://linux-hardware.org/?probe=d2804fad00) | Sep 01, 2021 |
| ASUSTek       | UX410UQK                    | [819b70e8cb](https://linux-hardware.org/?probe=819b70e8cb) | Sep 01, 2021 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [93a7aa0485](https://linux-hardware.org/?probe=93a7aa0485) | Aug 31, 2021 |
| Apple         | MacBookPro11,1              | [1dbc26a990](https://linux-hardware.org/?probe=1dbc26a990) | Aug 29, 2021 |
| Toshiba       | Satellite C845D             | [ac992ef3e5](https://linux-hardware.org/?probe=ac992ef3e5) | Aug 29, 2021 |
| Lenovo        | ThinkPad X260 20F5S3J00D    | [eeb6586c28](https://linux-hardware.org/?probe=eeb6586c28) | Aug 26, 2021 |
| Sony          | VGN-NW215T                  | [3b59710f01](https://linux-hardware.org/?probe=3b59710f01) | Aug 25, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [207f0c8966](https://linux-hardware.org/?probe=207f0c8966) | Aug 24, 2021 |
| Acer          | Aspire 7741                 | [849c1fe7e3](https://linux-hardware.org/?probe=849c1fe7e3) | Aug 22, 2021 |
| HP            | ProBook 440 G3              | [80aa412668](https://linux-hardware.org/?probe=80aa412668) | Aug 22, 2021 |
| Lenovo        | V145-15AST 81MT             | [28d8feb60d](https://linux-hardware.org/?probe=28d8feb60d) | Aug 20, 2021 |
| Lenovo        | V145-15AST 81MT             | [f207dc8e9a](https://linux-hardware.org/?probe=f207dc8e9a) | Aug 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [ab27a12603](https://linux-hardware.org/?probe=ab27a12603) | Aug 18, 2021 |
| Dell          | Inspiron 5459               | [b99b48660a](https://linux-hardware.org/?probe=b99b48660a) | Aug 08, 2021 |
| Sony          | SVE14A27CLS                 | [53a5965063](https://linux-hardware.org/?probe=53a5965063) | Aug 07, 2021 |
| HP            | ProBook 640 G1              | [4d0bb591af](https://linux-hardware.org/?probe=4d0bb591af) | Aug 06, 2021 |
| Dell          | G3 3590                     | [16bdb588e1](https://linux-hardware.org/?probe=16bdb588e1) | Aug 05, 2021 |
| Dell          | G3 3590                     | [01a9560f9c](https://linux-hardware.org/?probe=01a9560f9c) | Aug 05, 2021 |
| Packard Be... | EasyNote MH35               | [e053c132dc](https://linux-hardware.org/?probe=e053c132dc) | Aug 02, 2021 |
| Dell          | Inspiron 5459               | [acc597c748](https://linux-hardware.org/?probe=acc597c748) | Aug 02, 2021 |
| Dell          | Inspiron 5459               | [d59cdfdb47](https://linux-hardware.org/?probe=d59cdfdb47) | Jul 30, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2e753f12ce](https://linux-hardware.org/?probe=2e753f12ce) | Jul 28, 2021 |
| Unknown       | MEDION                      | [021ba4d5b5](https://linux-hardware.org/?probe=021ba4d5b5) | Jul 25, 2021 |
| Unknown       | MEDION                      | [5df19c2a06](https://linux-hardware.org/?probe=5df19c2a06) | Jul 25, 2021 |
| Unknown       | MEDION                      | [e9c5e99e0b](https://linux-hardware.org/?probe=e9c5e99e0b) | Jul 25, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [1d0f458592](https://linux-hardware.org/?probe=1d0f458592) | Jul 23, 2021 |
| Acer          | Swift SF314-42              | [f8812e14cb](https://linux-hardware.org/?probe=f8812e14cb) | Jul 23, 2021 |
| Lenovo        | IdeaPad 710S-13ISK 80SW     | [0d3be70373](https://linux-hardware.org/?probe=0d3be70373) | Jul 20, 2021 |
| HP            | ENVY 15                     | [d2a3149a9a](https://linux-hardware.org/?probe=d2a3149a9a) | Jul 17, 2021 |
| HP            | ProBook 640 G1              | [2db57969aa](https://linux-hardware.org/?probe=2db57969aa) | Jul 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f024f2512e](https://linux-hardware.org/?probe=f024f2512e) | Jul 14, 2021 |
| HP            | Spectre Laptop 13-af0xx     | [bfef4cded0](https://linux-hardware.org/?probe=bfef4cded0) | Jul 09, 2021 |
| Lenovo        | G40-30 80FY                 | [ef9a6d3444](https://linux-hardware.org/?probe=ef9a6d3444) | Jul 08, 2021 |
| HP            | Notebook                    | [3087e92283](https://linux-hardware.org/?probe=3087e92283) | Jun 29, 2021 |
| HP            | Notebook                    | [510eaefd82](https://linux-hardware.org/?probe=510eaefd82) | Jun 29, 2021 |
| HP            | ENVY Laptop 13-ah0xxx       | [48a1dddc38](https://linux-hardware.org/?probe=48a1dddc38) | Jun 27, 2021 |
| ASUSTek       | N551JX                      | [3ef394cafb](https://linux-hardware.org/?probe=3ef394cafb) | Jun 24, 2021 |
| Toshiba       | PORTEGE R705                | [fe7063735e](https://linux-hardware.org/?probe=fe7063735e) | Jun 24, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [9d80703f35](https://linux-hardware.org/?probe=9d80703f35) | Jun 23, 2021 |
| Dell          | Inspiron 5459               | [22f31e0de1](https://linux-hardware.org/?probe=22f31e0de1) | Jun 19, 2021 |
| Toshiba       | PORTEGE R705                | [a53fb9eb09](https://linux-hardware.org/?probe=a53fb9eb09) | Jun 19, 2021 |
| HP            | Notebook                    | [f1263ec1fc](https://linux-hardware.org/?probe=f1263ec1fc) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | [6529cc537c](https://linux-hardware.org/?probe=6529cc537c) | Jun 13, 2021 |
| Acer          | Aspire A515-56              | [2aa173f32b](https://linux-hardware.org/?probe=2aa173f32b) | Jun 12, 2021 |
| Unknown       | Unknown                     | [16d75c0003](https://linux-hardware.org/?probe=16d75c0003) | Jun 11, 2021 |
| Samsung       | 670Z5E                      | [252e20c152](https://linux-hardware.org/?probe=252e20c152) | Jun 11, 2021 |
| Dell          | Inspiron 5567               | [0ffe39ef8d](https://linux-hardware.org/?probe=0ffe39ef8d) | Jun 09, 2021 |
| Sony          | SVE14113ELW                 | [738c72c21c](https://linux-hardware.org/?probe=738c72c21c) | Jun 09, 2021 |
| HP            | ENVY 15                     | [8d7a772e05](https://linux-hardware.org/?probe=8d7a772e05) | Jun 07, 2021 |
| Dell          | Precision 5520              | [199dec46c7](https://linux-hardware.org/?probe=199dec46c7) | Jun 01, 2021 |
| HP            | 1000                        | [21fb6389e7](https://linux-hardware.org/?probe=21fb6389e7) | Jun 01, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [4688dc5b46](https://linux-hardware.org/?probe=4688dc5b46) | May 29, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [b1500a1319](https://linux-hardware.org/?probe=b1500a1319) | May 28, 2021 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [abc55fc46d](https://linux-hardware.org/?probe=abc55fc46d) | May 28, 2021 |
| Personal C... | Iris                        | [835df5c61e](https://linux-hardware.org/?probe=835df5c61e) | May 27, 2021 |
| Toshiba       | PORTEGE R705                | [afd83c5750](https://linux-hardware.org/?probe=afd83c5750) | May 25, 2021 |
| Acer          | Swift SF313-53              | [66e4f1aeff](https://linux-hardware.org/?probe=66e4f1aeff) | May 23, 2021 |
| Unknown       | Unknown                     | [e9dc8181d8](https://linux-hardware.org/?probe=e9dc8181d8) | May 20, 2021 |
| Toshiba       | Satellite L45-B             | [544d468137](https://linux-hardware.org/?probe=544d468137) | May 16, 2021 |
| HP            | 435                         | [65bbde1e13](https://linux-hardware.org/?probe=65bbde1e13) | May 16, 2021 |
| HP            | 435                         | [fe5a82cf02](https://linux-hardware.org/?probe=fe5a82cf02) | May 16, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [a98d93888d](https://linux-hardware.org/?probe=a98d93888d) | May 14, 2021 |
| Dell          | Latitude 7490               | [c533165389](https://linux-hardware.org/?probe=c533165389) | May 13, 2021 |
| Acer          | Swift SF313-53              | [9a7cca485d](https://linux-hardware.org/?probe=9a7cca485d) | May 13, 2021 |
| Samsung       | RF712                       | [a3624b29fa](https://linux-hardware.org/?probe=a3624b29fa) | May 11, 2021 |
| Samsung       | RF712                       | [652fb28adb](https://linux-hardware.org/?probe=652fb28adb) | May 11, 2021 |
| Acer          | Swift SF313-53              | [2e4262cb53](https://linux-hardware.org/?probe=2e4262cb53) | May 11, 2021 |
| Dell          | Inspiron 5567               | [aacf9438d2](https://linux-hardware.org/?probe=aacf9438d2) | May 11, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [2196430972](https://linux-hardware.org/?probe=2196430972) | May 09, 2021 |
| HP            | EliteBook 840 G6            | [08d59f23ab](https://linux-hardware.org/?probe=08d59f23ab) | May 09, 2021 |
| HP            | 1000                        | [4205750e24](https://linux-hardware.org/?probe=4205750e24) | May 08, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ce41256b96](https://linux-hardware.org/?probe=ce41256b96) | May 07, 2021 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [566133628f](https://linux-hardware.org/?probe=566133628f) | May 07, 2021 |
| Toshiba       | Satellite U505              | [50baa8508f](https://linux-hardware.org/?probe=50baa8508f) | May 05, 2021 |
| Toshiba       | Satellite U505              | [c5785176bd](https://linux-hardware.org/?probe=c5785176bd) | May 05, 2021 |
| Packard Be... | EasyNote TM98               | [2bb98626e9](https://linux-hardware.org/?probe=2bb98626e9) | May 03, 2021 |
| HUAWEI        | WRTB-WXX9                   | [f9ceb7c523](https://linux-hardware.org/?probe=f9ceb7c523) | May 02, 2021 |
| Dell          | Latitude D630               | [40a03f054f](https://linux-hardware.org/?probe=40a03f054f) | May 02, 2021 |
| Acer          | Aspire ES1-431              | [cc8dd98cc6](https://linux-hardware.org/?probe=cc8dd98cc6) | May 01, 2021 |
| Acer          | Aspire ES1-431              | [b471fb7c4f](https://linux-hardware.org/?probe=b471fb7c4f) | May 01, 2021 |
| HP            | 14                          | [f2874ea965](https://linux-hardware.org/?probe=f2874ea965) | May 01, 2021 |
| HP            | ENVY 17 Leap Motion SE N... | [18b8d3d480](https://linux-hardware.org/?probe=18b8d3d480) | Apr 30, 2021 |
| HP            | Pavilion dm4                | [dd8938cac1](https://linux-hardware.org/?probe=dd8938cac1) | Apr 29, 2021 |
| Dell          | Inspiron N4110              | [17b9bc8eb3](https://linux-hardware.org/?probe=17b9bc8eb3) | Apr 27, 2021 |
| HP            | ProBook 430 G3              | [c3acaeb030](https://linux-hardware.org/?probe=c3acaeb030) | Apr 26, 2021 |
| HP            | ProBook 430 G3              | [de3298645e](https://linux-hardware.org/?probe=de3298645e) | Apr 26, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [8ff356e9be](https://linux-hardware.org/?probe=8ff356e9be) | Apr 25, 2021 |
| Packard Be... | EasyNote_BU45               | [83204d550c](https://linux-hardware.org/?probe=83204d550c) | Apr 19, 2021 |
| Toshiba       | PORTEGE R705                | [6bee6da553](https://linux-hardware.org/?probe=6bee6da553) | Apr 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [998919a455](https://linux-hardware.org/?probe=998919a455) | Apr 18, 2021 |
| Dell          | Latitude 7410               | [7792c66c17](https://linux-hardware.org/?probe=7792c66c17) | Apr 15, 2021 |
| Toshiba       | PORTEGE R705                | [00dee5f7b1](https://linux-hardware.org/?probe=00dee5f7b1) | Apr 15, 2021 |
| Toshiba       | PORTEGE R705                | [36c36beaf0](https://linux-hardware.org/?probe=36c36beaf0) | Apr 14, 2021 |
| ASUSTek       | ROG Zephyrus GX550LXS_GX... | [8eeff8c77c](https://linux-hardware.org/?probe=8eeff8c77c) | Apr 13, 2021 |
| Dell          | Latitude 7410               | [5711fac8b6](https://linux-hardware.org/?probe=5711fac8b6) | Apr 11, 2021 |
| Dell          | Latitude 7400               | [41a2361010](https://linux-hardware.org/?probe=41a2361010) | Apr 11, 2021 |
| Acer          | Aspire ES1-431              | [9109f31570](https://linux-hardware.org/?probe=9109f31570) | Apr 10, 2021 |
| Acer          | Aspire ES1-431              | [df53cbed23](https://linux-hardware.org/?probe=df53cbed23) | Apr 10, 2021 |
| Toshiba       | PORTEGE R705                | [dd16cda442](https://linux-hardware.org/?probe=dd16cda442) | Apr 10, 2021 |
| ASUSTek       | N46VB                       | [a425e290d7](https://linux-hardware.org/?probe=a425e290d7) | Apr 09, 2021 |
| Personal C... | Iris                        | [add36a3a7c](https://linux-hardware.org/?probe=add36a3a7c) | Apr 09, 2021 |
| Personal C... | Iris                        | [4ec2ee9e6d](https://linux-hardware.org/?probe=4ec2ee9e6d) | Apr 09, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [adb7fbfc0d](https://linux-hardware.org/?probe=adb7fbfc0d) | Apr 08, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [9b9172e5a7](https://linux-hardware.org/?probe=9b9172e5a7) | Apr 08, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [3c44770d1a](https://linux-hardware.org/?probe=3c44770d1a) | Apr 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U2S... | [3a85124409](https://linux-hardware.org/?probe=3a85124409) | Apr 07, 2021 |
| HP            | ENVY Notebook               | [83a0078309](https://linux-hardware.org/?probe=83a0078309) | Apr 06, 2021 |
| Dell          | Inspiron 5459               | [243557128f](https://linux-hardware.org/?probe=243557128f) | Apr 06, 2021 |
| Dell          | Inspiron 5459               | [f3b9205a6c](https://linux-hardware.org/?probe=f3b9205a6c) | Apr 06, 2021 |
| Dell          | Inspiron 1545               | [ace9676e8c](https://linux-hardware.org/?probe=ace9676e8c) | Apr 05, 2021 |
| HP            | 15                          | [69d2aa2538](https://linux-hardware.org/?probe=69d2aa2538) | Apr 05, 2021 |
| Lenovo        | ThinkPad T440p 20AWS0DU0... | [8d5f33367e](https://linux-hardware.org/?probe=8d5f33367e) | Apr 04, 2021 |
| Lenovo        | IdeaPad Y480                | [d0aeb8aafc](https://linux-hardware.org/?probe=d0aeb8aafc) | Apr 03, 2021 |
| Dell          | Inspiron 3420               | [4d76b6366d](https://linux-hardware.org/?probe=4d76b6366d) | Apr 01, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [742b7afcc8](https://linux-hardware.org/?probe=742b7afcc8) | Apr 01, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [8856c82ed6](https://linux-hardware.org/?probe=8856c82ed6) | Mar 31, 2021 |
| HP            | ENVY 15                     | [31c601923e](https://linux-hardware.org/?probe=31c601923e) | Mar 31, 2021 |
| HP            | ENVY 15                     | [3628d88bc1](https://linux-hardware.org/?probe=3628d88bc1) | Mar 31, 2021 |
| HP            | 250 G4 Notebook PC          | [e3119c3a18](https://linux-hardware.org/?probe=e3119c3a18) | Mar 30, 2021 |
| HP            | 245 G7 Notebook PC          | [3a4703f85d](https://linux-hardware.org/?probe=3a4703f85d) | Mar 27, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [867936010e](https://linux-hardware.org/?probe=867936010e) | Mar 25, 2021 |
| Dell          | Inspiron 14-3467            | [6079a062b3](https://linux-hardware.org/?probe=6079a062b3) | Mar 18, 2021 |
| HP            | 240 G7 Notebook PC          | [669e53f097](https://linux-hardware.org/?probe=669e53f097) | Mar 16, 2021 |
| Dell          | Inspiron 5721               | [0f95174924](https://linux-hardware.org/?probe=0f95174924) | Mar 15, 2021 |
| HP            | Notebook                    | [9c176242dd](https://linux-hardware.org/?probe=9c176242dd) | Mar 14, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [e2e99630ca](https://linux-hardware.org/?probe=e2e99630ca) | Mar 14, 2021 |
| HP            | 15                          | [08b381f369](https://linux-hardware.org/?probe=08b381f369) | Mar 12, 2021 |
| Dell          | Inspiron 14-3467            | [64c0ae2c8b](https://linux-hardware.org/?probe=64c0ae2c8b) | Mar 11, 2021 |
| Dell          | Inspiron 14-3467            | [0611d13dff](https://linux-hardware.org/?probe=0611d13dff) | Mar 11, 2021 |
| HP            | ProBook 440 G3              | [fc6181a7c1](https://linux-hardware.org/?probe=fc6181a7c1) | Mar 11, 2021 |
| HP            | ProBook 440 G3              | [38042c5772](https://linux-hardware.org/?probe=38042c5772) | Mar 11, 2021 |
| Toshiba       | PORTEGE R705                | [f537f51a95](https://linux-hardware.org/?probe=f537f51a95) | Mar 09, 2021 |
| Acer          | Aspire 5738                 | [a1a9e12988](https://linux-hardware.org/?probe=a1a9e12988) | Mar 07, 2021 |
| MSI           | Stealth 15M A11SEK          | [1187156178](https://linux-hardware.org/?probe=1187156178) | Mar 05, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [76006e9ba5](https://linux-hardware.org/?probe=76006e9ba5) | Mar 01, 2021 |
| Dell          | Inspiron 14-3467            | [7991d50dfd](https://linux-hardware.org/?probe=7991d50dfd) | Mar 01, 2021 |
| Unknown       | Unknown                     | [e8359056f7](https://linux-hardware.org/?probe=e8359056f7) | Feb 26, 2021 |
| HP            | Pavilion Notebook           | [45dfe3c2b1](https://linux-hardware.org/?probe=45dfe3c2b1) | Feb 24, 2021 |
| Dell          | Vostro V13                  | [f9b40741e7](https://linux-hardware.org/?probe=f9b40741e7) | Feb 19, 2021 |
| Toshiba       | Satellite C845D             | [6a73d1fd72](https://linux-hardware.org/?probe=6a73d1fd72) | Feb 19, 2021 |
| Packard Be... | EasyNote TM85               | [972a7d0f8c](https://linux-hardware.org/?probe=972a7d0f8c) | Feb 17, 2021 |
| ASUSTek       | GL502VMK                    | [54b49d2dc7](https://linux-hardware.org/?probe=54b49d2dc7) | Feb 15, 2021 |
| ASUSTek       | GL502VMK                    | [514a434029](https://linux-hardware.org/?probe=514a434029) | Feb 15, 2021 |
| Dell          | Latitude 3440               | [d2806294ef](https://linux-hardware.org/?probe=d2806294ef) | Feb 13, 2021 |
| Unknown       | Unknown                     | [acd23bb798](https://linux-hardware.org/?probe=acd23bb798) | Feb 13, 2021 |
| Sony          | VPCEG15FL                   | [48a16e8a4a](https://linux-hardware.org/?probe=48a16e8a4a) | Feb 10, 2021 |
| Dell          | System Inspiron N411Z       | [eed8ecb624](https://linux-hardware.org/?probe=eed8ecb624) | Feb 08, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd F... | [799c301ad6](https://linux-hardware.org/?probe=799c301ad6) | Feb 08, 2021 |
| Dell          | System Inspiron N411Z       | [f6ea43033f](https://linux-hardware.org/?probe=f6ea43033f) | Feb 07, 2021 |
| Unknown       | Unknown                     | [01a4eafbb6](https://linux-hardware.org/?probe=01a4eafbb6) | Feb 02, 2021 |
| Unknown       | Unknown                     | [9cc5c245d0](https://linux-hardware.org/?probe=9cc5c245d0) | Feb 02, 2021 |
| HP            | 240 G6 Notebook PC          | [2ba1c141b8](https://linux-hardware.org/?probe=2ba1c141b8) | Feb 01, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [3f400fbc08](https://linux-hardware.org/?probe=3f400fbc08) | Jan 31, 2021 |
| ASUSTek       | UX430UNR                    | [e32eec7802](https://linux-hardware.org/?probe=e32eec7802) | Jan 27, 2021 |
| HP            | EliteBook 2560p             | [8289f3c10b](https://linux-hardware.org/?probe=8289f3c10b) | Jan 24, 2021 |
| HP            | Pavilion 15                 | [b83dc673fd](https://linux-hardware.org/?probe=b83dc673fd) | Jan 23, 2021 |
| HP            | 14                          | [7c1ff6f4a8](https://linux-hardware.org/?probe=7c1ff6f4a8) | Jan 22, 2021 |
| Dell          | Vostro 1520                 | [36392e13b5](https://linux-hardware.org/?probe=36392e13b5) | Jan 22, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [5f648131f5](https://linux-hardware.org/?probe=5f648131f5) | Jan 19, 2021 |
| ASUSTek       | UX310UQK                    | [7006cf4aa0](https://linux-hardware.org/?probe=7006cf4aa0) | Jan 13, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [4b69e8576c](https://linux-hardware.org/?probe=4b69e8576c) | Jan 11, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [7ae430600b](https://linux-hardware.org/?probe=7ae430600b) | Jan 07, 2021 |
| HP            | EliteBook 840 G6            | [5d26e74a5d](https://linux-hardware.org/?probe=5d26e74a5d) | Jan 07, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [1ce6d33d5b](https://linux-hardware.org/?probe=1ce6d33d5b) | Jan 07, 2021 |
| HP            | Notebook                    | [38341a3370](https://linux-hardware.org/?probe=38341a3370) | Jan 06, 2021 |
| HP            | EliteBook 840 G6            | [724662dec7](https://linux-hardware.org/?probe=724662dec7) | Jan 05, 2021 |
| Sony          | SVE14113ELW                 | [695f68585f](https://linux-hardware.org/?probe=695f68585f) | Jan 05, 2021 |
| Sony          | SVE14113ELW                 | [09553d1a31](https://linux-hardware.org/?probe=09553d1a31) | Jan 05, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [b8232e1903](https://linux-hardware.org/?probe=b8232e1903) | Jan 04, 2021 |
| Sony          | SVE14113ELW                 | [2f05d7efd0](https://linux-hardware.org/?probe=2f05d7efd0) | Jan 03, 2021 |
| Sony          | SVE14113ELW                 | [88ef270eb5](https://linux-hardware.org/?probe=88ef270eb5) | Jan 03, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [019f053a89](https://linux-hardware.org/?probe=019f053a89) | Jan 02, 2021 |
| HP            | Notebook                    | [cf3a2917d1](https://linux-hardware.org/?probe=cf3a2917d1) | Dec 28, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [0a8ed33e62](https://linux-hardware.org/?probe=0a8ed33e62) | Dec 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [9a02f6b2cf](https://linux-hardware.org/?probe=9a02f6b2cf) | Dec 22, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [680d4771b2](https://linux-hardware.org/?probe=680d4771b2) | Dec 15, 2020 |
| Acer          | Aspire 5738                 | [ad2cafcbe8](https://linux-hardware.org/?probe=ad2cafcbe8) | Dec 13, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [43e55c9de6](https://linux-hardware.org/?probe=43e55c9de6) | Dec 13, 2020 |
| HP            | EliteBook 840r G4           | [ebc64db4ca](https://linux-hardware.org/?probe=ebc64db4ca) | Dec 12, 2020 |
| Acer          | Aspire 5738                 | [f29c073cfb](https://linux-hardware.org/?probe=f29c073cfb) | Dec 11, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [5bae11079c](https://linux-hardware.org/?probe=5bae11079c) | Dec 09, 2020 |
| Toshiba       | Satellite C645              | [0e17d5e680](https://linux-hardware.org/?probe=0e17d5e680) | Dec 09, 2020 |
| Toshiba       | Satellite C645              | [0fcca906f6](https://linux-hardware.org/?probe=0fcca906f6) | Dec 09, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [d9258de65c](https://linux-hardware.org/?probe=d9258de65c) | Dec 09, 2020 |
| Apple         | MacBookPro9,2               | [7469e3af08](https://linux-hardware.org/?probe=7469e3af08) | Dec 08, 2020 |
| HP            | ProBook 440 G7              | [01b2a334c8](https://linux-hardware.org/?probe=01b2a334c8) | Dec 04, 2020 |
| Lenovo        | IdeaPad Z400 20201          | [9f4318e1fa](https://linux-hardware.org/?probe=9f4318e1fa) | Dec 03, 2020 |
| Lenovo        | K2450 20243                 | [33409ba105](https://linux-hardware.org/?probe=33409ba105) | Dec 03, 2020 |
| Lenovo        | K2450 20243                 | [5c14a1c448](https://linux-hardware.org/?probe=5c14a1c448) | Dec 02, 2020 |
| Dell          | Latitude E7470              | [ff5ee269cb](https://linux-hardware.org/?probe=ff5ee269cb) | Dec 01, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [9be5961a82](https://linux-hardware.org/?probe=9be5961a82) | Nov 25, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [2ce0bde22b](https://linux-hardware.org/?probe=2ce0bde22b) | Nov 21, 2020 |
| ASUSTek       | X405UA                      | [e27b62e8d8](https://linux-hardware.org/?probe=e27b62e8d8) | Nov 19, 2020 |
| Lenovo        | K2450 20243                 | [4d44042257](https://linux-hardware.org/?probe=4d44042257) | Nov 19, 2020 |
| HP            | EliteBook 840r G4           | [4782db92e6](https://linux-hardware.org/?probe=4782db92e6) | Nov 19, 2020 |
| Lenovo        | IdeaPad S206 20154          | [393f27acf7](https://linux-hardware.org/?probe=393f27acf7) | Nov 18, 2020 |
| Lenovo        | G400 20235                  | [7cdfc8df41](https://linux-hardware.org/?probe=7cdfc8df41) | Nov 17, 2020 |
| Lenovo        | G400 20235                  | [9d19c00f4e](https://linux-hardware.org/?probe=9d19c00f4e) | Nov 17, 2020 |
| Positivo      | Mobile                      | [87704474ae](https://linux-hardware.org/?probe=87704474ae) | Nov 12, 2020 |
| HP            | 1000                        | [a79972678b](https://linux-hardware.org/?probe=a79972678b) | Nov 10, 2020 |
| Lenovo        | ThinkPad T400 6474AU5       | [1b3d0a7938](https://linux-hardware.org/?probe=1b3d0a7938) | Nov 09, 2020 |
| HP            | 420                         | [8b2ce5df27](https://linux-hardware.org/?probe=8b2ce5df27) | Nov 09, 2020 |
| Unknown       | Unknown                     | [8651ede6c2](https://linux-hardware.org/?probe=8651ede6c2) | Nov 04, 2020 |
| Dell          | XPS 13 9300                 | [764cabc447](https://linux-hardware.org/?probe=764cabc447) | Nov 03, 2020 |
| HP            | Pavilion dv4                | [80f9a1311e](https://linux-hardware.org/?probe=80f9a1311e) | Oct 30, 2020 |
| Toshiba       | Satellite C45-A             | [bbfec71882](https://linux-hardware.org/?probe=bbfec71882) | Oct 30, 2020 |
| HP            | Laptop 14-cf0xxx            | [5ae192d7e1](https://linux-hardware.org/?probe=5ae192d7e1) | Oct 26, 2020 |
| HP            | Laptop 14-cf0xxx            | [8999670eb2](https://linux-hardware.org/?probe=8999670eb2) | Oct 25, 2020 |
| Acer          | Swift SF314-42              | [628265bca0](https://linux-hardware.org/?probe=628265bca0) | Oct 25, 2020 |
| Lenovo        | IdeaPad S300 20197          | [d03e3dc110](https://linux-hardware.org/?probe=d03e3dc110) | Oct 23, 2020 |
| Dell          | Latitude E6440              | [46a2699a96](https://linux-hardware.org/?probe=46a2699a96) | Oct 21, 2020 |
| Acer          | Swift SF314-42              | [01143e194b](https://linux-hardware.org/?probe=01143e194b) | Oct 20, 2020 |
| ASUSTek       | X555LB                      | [75ba1f9ee4](https://linux-hardware.org/?probe=75ba1f9ee4) | Oct 19, 2020 |
| Acer          | Aspire E1-531               | [78a57e6fb8](https://linux-hardware.org/?probe=78a57e6fb8) | Oct 13, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [63831d979c](https://linux-hardware.org/?probe=63831d979c) | Oct 06, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [887dc701b4](https://linux-hardware.org/?probe=887dc701b4) | Oct 05, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [eed07ba536](https://linux-hardware.org/?probe=eed07ba536) | Oct 05, 2020 |
| Unknown       | Unknown                     | [afc109116d](https://linux-hardware.org/?probe=afc109116d) | Oct 01, 2020 |
| HP            | 530                         | [c330f06c15](https://linux-hardware.org/?probe=c330f06c15) | Sep 30, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ad0d202176](https://linux-hardware.org/?probe=ad0d202176) | Sep 29, 2020 |
| HP            | Pavilion Power Laptop 15... | [6f97a1bc53](https://linux-hardware.org/?probe=6f97a1bc53) | Sep 28, 2020 |
| Lenovo        | ThinkPad T460 20FMS05G4L    | [2934114047](https://linux-hardware.org/?probe=2934114047) | Sep 28, 2020 |
| Dell          | XPS 13 9370                 | [bd632f89ef](https://linux-hardware.org/?probe=bd632f89ef) | Sep 26, 2020 |
| HP            | EliteBook 840r G4           | [2ed34e371e](https://linux-hardware.org/?probe=2ed34e371e) | Sep 26, 2020 |
| Unknown       | Unknown                     | [6ce0ba50a1](https://linux-hardware.org/?probe=6ce0ba50a1) | Sep 23, 2020 |
| Unknown       | Unknown                     | [be59c4d6c4](https://linux-hardware.org/?probe=be59c4d6c4) | Sep 23, 2020 |
| HP            | EliteBook 840 G6            | [42e3c550cb](https://linux-hardware.org/?probe=42e3c550cb) | Sep 22, 2020 |
| ASUSTek       | X556URK                     | [1c0033b367](https://linux-hardware.org/?probe=1c0033b367) | Sep 20, 2020 |
| ASUSTek       | G55VW                       | [8bfec34af2](https://linux-hardware.org/?probe=8bfec34af2) | Sep 20, 2020 |
| HP            | 245 G5 Notebook PC          | [d2e8cd8f97](https://linux-hardware.org/?probe=d2e8cd8f97) | Sep 15, 2020 |
| HP            | 245 G5 Notebook PC          | [da0f03edfc](https://linux-hardware.org/?probe=da0f03edfc) | Sep 14, 2020 |
| Acer          | Aspire 5542                 | [da115e748b](https://linux-hardware.org/?probe=da115e748b) | Sep 14, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | [1f5bd64812](https://linux-hardware.org/?probe=1f5bd64812) | Sep 09, 2020 |
| HP            | Pavilion 15                 | [df560484b4](https://linux-hardware.org/?probe=df560484b4) | Sep 09, 2020 |
| Acer          | Nitro AN515-43              | [44782a039e](https://linux-hardware.org/?probe=44782a039e) | Sep 07, 2020 |
| Lenovo        | ThinkPad A485 20MVS0N300    | [6ad17e6cf7](https://linux-hardware.org/?probe=6ad17e6cf7) | Sep 05, 2020 |
| HP            | Notebook                    | [c5d0ec5edb](https://linux-hardware.org/?probe=c5d0ec5edb) | Aug 30, 2020 |
| Acer          | Aspire E1-422               | [a239e53a11](https://linux-hardware.org/?probe=a239e53a11) | Aug 29, 2020 |
| Acer          | Aspire A315-21              | [02f9010c71](https://linux-hardware.org/?probe=02f9010c71) | Aug 26, 2020 |
| HP            | Pavilion Notebook           | [341b0f6231](https://linux-hardware.org/?probe=341b0f6231) | Aug 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [be74487ec4](https://linux-hardware.org/?probe=be74487ec4) | Aug 23, 2020 |
| Acer          | Aspire ES1-111M             | [fcee1a2241](https://linux-hardware.org/?probe=fcee1a2241) | Aug 21, 2020 |
| Acer          | Aspire ES1-111M             | [43f35553ae](https://linux-hardware.org/?probe=43f35553ae) | Aug 21, 2020 |
| HP            | Pavilion 15                 | [d9c1a66672](https://linux-hardware.org/?probe=d9c1a66672) | Aug 20, 2020 |
| HP            | Laptop 15-bs0xx             | [f6678c3632](https://linux-hardware.org/?probe=f6678c3632) | Aug 17, 2020 |
| Lenovo        | ThinkPad E420 1141DAS       | [ab579f2102](https://linux-hardware.org/?probe=ab579f2102) | Aug 17, 2020 |
| Lenovo        | ThinkPad E420 1141DAS       | [d4beb495bd](https://linux-hardware.org/?probe=d4beb495bd) | Aug 17, 2020 |
| ASUSTek       | FX503VD                     | [26ce95f067](https://linux-hardware.org/?probe=26ce95f067) | Aug 03, 2020 |
| HP            | Laptop 15-bs0xx             | [467112cf04](https://linux-hardware.org/?probe=467112cf04) | Jul 31, 2020 |
| HP            | ProBook 440 G3              | [9a34cb7ec7](https://linux-hardware.org/?probe=9a34cb7ec7) | Jul 28, 2020 |
| Acer          | Aspire ES1-572              | [1db75aee39](https://linux-hardware.org/?probe=1db75aee39) | Jul 27, 2020 |
| Acer          | Aspire R3-431T              | [b3bc6f8d90](https://linux-hardware.org/?probe=b3bc6f8d90) | Jul 24, 2020 |
| HP            | Pavilion 15                 | [7410d46ef8](https://linux-hardware.org/?probe=7410d46ef8) | Jul 24, 2020 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [dbb48c14f0](https://linux-hardware.org/?probe=dbb48c14f0) | Jul 22, 2020 |
| HP            | Notebook                    | [431d1d1482](https://linux-hardware.org/?probe=431d1d1482) | Jul 22, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [3216dbc594](https://linux-hardware.org/?probe=3216dbc594) | Jul 18, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [f8c9b50bc3](https://linux-hardware.org/?probe=f8c9b50bc3) | Jul 18, 2020 |
| Sony          | VGN-FW360TJ                 | [8b037cac91](https://linux-hardware.org/?probe=8b037cac91) | Jul 18, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Apple         | MacBookAir7,2               | [f53c9923c4](https://linux-hardware.org/?probe=f53c9923c4) | Jul 11, 2020 |
| HP            | Presario CQ43               | [48fe8649ca](https://linux-hardware.org/?probe=48fe8649ca) | Jul 08, 2020 |
| HP            | Presario CQ43               | [db6a9d6546](https://linux-hardware.org/?probe=db6a9d6546) | Jul 06, 2020 |
| HP            | ProBook 4440s               | [48a7e1a88c](https://linux-hardware.org/?probe=48a7e1a88c) | Jul 05, 2020 |
| Dell          | Inspiron N5110              | [bd30f237dd](https://linux-hardware.org/?probe=bd30f237dd) | Jul 05, 2020 |
| Acer          | Aspire ES1-331              | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| HP            | ProBook 640 G1              | [1a2462dee7](https://linux-hardware.org/?probe=1a2462dee7) | Jul 01, 2020 |
| Toshiba       | PORTEGE R30-A               | [d33d8295b1](https://linux-hardware.org/?probe=d33d8295b1) | Jun 29, 2020 |
| Corporativ... | LX4SI                       | [3a15f8865d](https://linux-hardware.org/?probe=3a15f8865d) | Jun 26, 2020 |
| ASUSTek       | X450LN                      | [347ebd88a5](https://linux-hardware.org/?probe=347ebd88a5) | Jun 25, 2020 |
| ASUSTek       | X450LN                      | [10dd68f147](https://linux-hardware.org/?probe=10dd68f147) | Jun 25, 2020 |
| Corporativ... | LX4SI                       | [f9e67e8a5f](https://linux-hardware.org/?probe=f9e67e8a5f) | Jun 25, 2020 |
| HP            | 240 G6 Notebook PC          | [c43e5357b0](https://linux-hardware.org/?probe=c43e5357b0) | Jun 24, 2020 |
| Packard Be... | DOT S                       | [d2cd9b2728](https://linux-hardware.org/?probe=d2cd9b2728) | Jun 24, 2020 |
| Lenovo        | IdeaPad 500-14ISK 80NS      | [1af5a3043b](https://linux-hardware.org/?probe=1af5a3043b) | Jun 23, 2020 |
| HP            | ProBook 430 G2              | [d988a74820](https://linux-hardware.org/?probe=d988a74820) | Jun 23, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | [0fbefbc62c](https://linux-hardware.org/?probe=0fbefbc62c) | Jun 21, 2020 |
| Lenovo        | IdeaPad 720S-14IKB 80XC     | [a281f8c305](https://linux-hardware.org/?probe=a281f8c305) | Jun 19, 2020 |
| HP            | 245 G4 Notebook PC          | [4f96cc852f](https://linux-hardware.org/?probe=4f96cc852f) | Jun 18, 2020 |
| HP            | 245 G4 Notebook PC          | [2c0356727d](https://linux-hardware.org/?probe=2c0356727d) | Jun 18, 2020 |
| Dell          | Inspiron 3420               | [5101d0c83c](https://linux-hardware.org/?probe=5101d0c83c) | Jun 17, 2020 |
| Dell          | Inspiron 14-3452            | [c83e4c2dd8](https://linux-hardware.org/?probe=c83e4c2dd8) | Jun 15, 2020 |
| Lenovo        | IdeaPad Z470                | [7167c9a1eb](https://linux-hardware.org/?probe=7167c9a1eb) | Jun 10, 2020 |
| Packard Be... | ENNS11HR                    | [952d5d4772](https://linux-hardware.org/?probe=952d5d4772) | Jun 05, 2020 |
| HP            | ProBook 4440s               | [730e093bc4](https://linux-hardware.org/?probe=730e093bc4) | Jun 05, 2020 |
| Acer          | Aspire V5-132               | [44a89c002a](https://linux-hardware.org/?probe=44a89c002a) | Jun 02, 2020 |
| Acer          | Aspire V5-132               | [5b82f8d7d3](https://linux-hardware.org/?probe=5b82f8d7d3) | Jun 02, 2020 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [fbccea1bb2](https://linux-hardware.org/?probe=fbccea1bb2) | May 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | [9a867c7a5b](https://linux-hardware.org/?probe=9a867c7a5b) | May 28, 2020 |
| Dell          | Latitude E7450              | [c3eab25bca](https://linux-hardware.org/?probe=c3eab25bca) | May 28, 2020 |
| Clevo         | W240HU/W250HUQ              | [9fac55b56b](https://linux-hardware.org/?probe=9fac55b56b) | May 28, 2020 |
| Clevo         | W240HU/W250HUQ              | [9403cfc9c4](https://linux-hardware.org/?probe=9403cfc9c4) | May 27, 2020 |
| Clevo         | W240HU/W250HUQ              | [216a9db389](https://linux-hardware.org/?probe=216a9db389) | May 27, 2020 |
| Dell          | Inspiron 14-3452            | [33a29d72b1](https://linux-hardware.org/?probe=33a29d72b1) | May 26, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [38e63a05e2](https://linux-hardware.org/?probe=38e63a05e2) | May 26, 2020 |
| Dell          | Inspiron 14-3452            | [f894499ac3](https://linux-hardware.org/?probe=f894499ac3) | May 26, 2020 |
| HP            | OMEN by HP Laptop           | [6cea5aa3fd](https://linux-hardware.org/?probe=6cea5aa3fd) | May 26, 2020 |
| HP            | OMEN by HP Laptop           | [a621749c2d](https://linux-hardware.org/?probe=a621749c2d) | May 26, 2020 |
| Acer          | ES1-111M                    | [53e45e403c](https://linux-hardware.org/?probe=53e45e403c) | May 23, 2020 |
| HP            | 240 G6 Notebook PC          | [d7e931edde](https://linux-hardware.org/?probe=d7e931edde) | May 22, 2020 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [fae71925c5](https://linux-hardware.org/?probe=fae71925c5) | May 21, 2020 |
| Acer          | Aspire 4739Z                | [f51ee0fe5a](https://linux-hardware.org/?probe=f51ee0fe5a) | May 20, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [910d27523a](https://linux-hardware.org/?probe=910d27523a) | May 20, 2020 |
| HP            | 240 G6 Notebook PC          | [43a1f986fe](https://linux-hardware.org/?probe=43a1f986fe) | May 19, 2020 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [ffe1142072](https://linux-hardware.org/?probe=ffe1142072) | May 19, 2020 |
| Acer          | Aspire A114-32              | [35ddb37c29](https://linux-hardware.org/?probe=35ddb37c29) | May 17, 2020 |
| Acer          | Aspire E5-551G              | [cda77789ec](https://linux-hardware.org/?probe=cda77789ec) | May 17, 2020 |
| Acer          | Aspire E5-551G              | [ee3ddbe726](https://linux-hardware.org/?probe=ee3ddbe726) | May 17, 2020 |
| Dell          | Latitude E6420              | [46a7b9904a](https://linux-hardware.org/?probe=46a7b9904a) | May 17, 2020 |
| Dell          | Latitude E6420              | [15d9716666](https://linux-hardware.org/?probe=15d9716666) | May 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [aaea2e35fd](https://linux-hardware.org/?probe=aaea2e35fd) | May 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [55850d2bd2](https://linux-hardware.org/?probe=55850d2bd2) | May 17, 2020 |
| Dell          | Inspiron 14-3452            | [65292593ee](https://linux-hardware.org/?probe=65292593ee) | May 15, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [fd09b801b7](https://linux-hardware.org/?probe=fd09b801b7) | May 14, 2020 |
| HP            | Pavilion Notebook           | [825d07d907](https://linux-hardware.org/?probe=825d07d907) | May 14, 2020 |
| Dell          | Precision 7520              | [bf1d29844b](https://linux-hardware.org/?probe=bf1d29844b) | May 13, 2020 |
| Dell          | Inspiron 1420               | [917741e728](https://linux-hardware.org/?probe=917741e728) | May 13, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [8006d3f65a](https://linux-hardware.org/?probe=8006d3f65a) | May 12, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [3c636a52de](https://linux-hardware.org/?probe=3c636a52de) | May 12, 2020 |
| Lenovo        | ThinkPad T495s 20QKA008C... | [9767ed89e1](https://linux-hardware.org/?probe=9767ed89e1) | May 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f15c21aabd](https://linux-hardware.org/?probe=f15c21aabd) | May 11, 2020 |
| Toshiba       | NB505                       | [26eaa80c8a](https://linux-hardware.org/?probe=26eaa80c8a) | May 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [ebf32d4cbf](https://linux-hardware.org/?probe=ebf32d4cbf) | May 08, 2020 |
| ASUSTek       | K50AB                       | [ac598fedba](https://linux-hardware.org/?probe=ac598fedba) | May 06, 2020 |
| ASUSTek       | K50AB                       | [c6bddf5ef2](https://linux-hardware.org/?probe=c6bddf5ef2) | May 06, 2020 |
| ASUSTek       | K50AB                       | [9e3de662ae](https://linux-hardware.org/?probe=9e3de662ae) | May 06, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [3abae5c4a3](https://linux-hardware.org/?probe=3abae5c4a3) | May 05, 2020 |
| HP            | Pavilion Notebook           | [b995e0664a](https://linux-hardware.org/?probe=b995e0664a) | May 03, 2020 |
| HP            | ElitePad 1000 G2            | [40df66d7b8](https://linux-hardware.org/?probe=40df66d7b8) | Apr 29, 2020 |
| Acer          | Aspire E1-531               | [c814274f99](https://linux-hardware.org/?probe=c814274f99) | Apr 27, 2020 |
| HP            | 240 G6 Notebook PC          | [542ddefbc5](https://linux-hardware.org/?probe=542ddefbc5) | Apr 25, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | [3fd8a137d5](https://linux-hardware.org/?probe=3fd8a137d5) | Apr 21, 2020 |
| HP            | 240 G6 Notebook PC          | [e96b3b2ace](https://linux-hardware.org/?probe=e96b3b2ace) | Apr 21, 2020 |
| HP            | 240 G6 Notebook PC          | [5058e946ea](https://linux-hardware.org/?probe=5058e946ea) | Apr 21, 2020 |
| Acer          | Aspire E1-531               | [a7e6d42571](https://linux-hardware.org/?probe=a7e6d42571) | Apr 21, 2020 |
| Acer          | Aspire E1-531               | [384b1e8269](https://linux-hardware.org/?probe=384b1e8269) | Apr 20, 2020 |
| HP            | EliteBook 840 G6            | [57feb728c2](https://linux-hardware.org/?probe=57feb728c2) | Apr 19, 2020 |
| Toshiba       | NB505                       | [174dd8b4cd](https://linux-hardware.org/?probe=174dd8b4cd) | Apr 16, 2020 |
| HP            | ENVY 15                     | [d38936efb2](https://linux-hardware.org/?probe=d38936efb2) | Apr 16, 2020 |
| Toshiba       | NB505                       | [a28c9ef432](https://linux-hardware.org/?probe=a28c9ef432) | Apr 12, 2020 |
| HP            | Pavilion g4                 | [ee7f720be3](https://linux-hardware.org/?probe=ee7f720be3) | Apr 12, 2020 |
| HP            | Pavilion Sleekbook 15       | [309b26e9a7](https://linux-hardware.org/?probe=309b26e9a7) | Apr 12, 2020 |
| HP            | Pavilion Sleekbook 15       | [2e367c6e47](https://linux-hardware.org/?probe=2e367c6e47) | Apr 12, 2020 |
| HP            | Pavilion Sleekbook 15       | [ca7cea286a](https://linux-hardware.org/?probe=ca7cea286a) | Apr 12, 2020 |
| Toshiba       | PORTEGE Z20t-C              | [9411f4e22a](https://linux-hardware.org/?probe=9411f4e22a) | Apr 09, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | [cf13d07d7d](https://linux-hardware.org/?probe=cf13d07d7d) | Apr 08, 2020 |
| Toshiba       | NB505                       | [c52e8296ad](https://linux-hardware.org/?probe=c52e8296ad) | Apr 06, 2020 |
| HP            | Notebook                    | [60ebb42480](https://linux-hardware.org/?probe=60ebb42480) | Apr 05, 2020 |
| HP            | Notebook                    | [6102146f30](https://linux-hardware.org/?probe=6102146f30) | Apr 04, 2020 |
| Toshiba       | Satellite P745D             | [82c4813a13](https://linux-hardware.org/?probe=82c4813a13) | Apr 02, 2020 |
| Toshiba       | Satellite P745D             | [dd172e55aa](https://linux-hardware.org/?probe=dd172e55aa) | Apr 02, 2020 |
| Toshiba       | Satellite P745D             | [41b7d310c8](https://linux-hardware.org/?probe=41b7d310c8) | Apr 02, 2020 |
| Toshiba       | Satellite P745D             | [a04d4d7bcb](https://linux-hardware.org/?probe=a04d4d7bcb) | Apr 02, 2020 |
| HP            | 250 G5 Notebook PC          | [ccc351f3a5](https://linux-hardware.org/?probe=ccc351f3a5) | Apr 01, 2020 |
| ASUSTek       | X580VD                      | [e8c7cfc3af](https://linux-hardware.org/?probe=e8c7cfc3af) | Mar 31, 2020 |
| Lenovo        | ThinkPad T410 2537M82       | [7c71cd5a53](https://linux-hardware.org/?probe=7c71cd5a53) | Mar 30, 2020 |
| Samsung       | RF511/RF411/RF711           | [54fd8a8ef3](https://linux-hardware.org/?probe=54fd8a8ef3) | Mar 27, 2020 |
| HP            | Laptop 14-bs0xx             | [872a291771](https://linux-hardware.org/?probe=872a291771) | Mar 26, 2020 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [62d04b32f4](https://linux-hardware.org/?probe=62d04b32f4) | Mar 25, 2020 |
| ASUSTek       | X455LAB                     | [cfe6c04671](https://linux-hardware.org/?probe=cfe6c04671) | Mar 19, 2020 |
| Acer          | Aspire 4332                 | [1ffe28f950](https://linux-hardware.org/?probe=1ffe28f950) | Mar 19, 2020 |
| Acer          | Aspire 4332                 | [4ef79a9f26](https://linux-hardware.org/?probe=4ef79a9f26) | Mar 19, 2020 |
| HP            | EliteBook 840 G6            | [d512b89622](https://linux-hardware.org/?probe=d512b89622) | Mar 13, 2020 |
| Acer          | TravelMate P258-M           | [6275f9d007](https://linux-hardware.org/?probe=6275f9d007) | Feb 22, 2020 |
| Samsung       | 450R4E/450R5E/450R4V/450... | [6e0ef2fa11](https://linux-hardware.org/?probe=6e0ef2fa11) | Feb 22, 2020 |
| Samsung       | 450R4E/450R5E/450R4V/450... | [2d80c7d577](https://linux-hardware.org/?probe=2d80c7d577) | Feb 22, 2020 |
| Samsung       | 450R4E/450R5E/450R4V/450... | [152883e525](https://linux-hardware.org/?probe=152883e525) | Feb 22, 2020 |
| HP            | ENVY 17 Leap Motion SE N... | [811ba67ee3](https://linux-hardware.org/?probe=811ba67ee3) | Feb 21, 2020 |
| HP            | 245 G5 Notebook PC          | [ecbab8f357](https://linux-hardware.org/?probe=ecbab8f357) | Feb 19, 2020 |
| HP            | 240 G6 Notebook PC          | [c709480047](https://linux-hardware.org/?probe=c709480047) | Feb 14, 2020 |
| Samsung       | R540/R580/R780/SA41/E452    | [b72d68e62c](https://linux-hardware.org/?probe=b72d68e62c) | Jan 31, 2020 |
| Sony          | VPCEG20EL                   | [d2ac041c40](https://linux-hardware.org/?probe=d2ac041c40) | Jan 22, 2020 |
| HP            | Presario CQ56               | [cafdaff7c6](https://linux-hardware.org/?probe=cafdaff7c6) | Jan 16, 2020 |
| AMI           | Board                       | [4d89af9f9b](https://linux-hardware.org/?probe=4d89af9f9b) | Jan 16, 2020 |
| Acer          | Aspire ES1-111M             | [ba1b65c973](https://linux-hardware.org/?probe=ba1b65c973) | Jan 13, 2020 |
| Acer          | Aspire E3-111               | [87473b8d1c](https://linux-hardware.org/?probe=87473b8d1c) | Jan 07, 2020 |
| Dell          | Latitude E7440              | [de95222539](https://linux-hardware.org/?probe=de95222539) | Dec 28, 2019 |
| Insyde        | CherryTrail                 | [9f7a2725e5](https://linux-hardware.org/?probe=9f7a2725e5) | Dec 07, 2019 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [ad5138a45f](https://linux-hardware.org/?probe=ad5138a45f) | Dec 04, 2019 |
| Dell          | Latitude E5470              | [5bf1258e74](https://linux-hardware.org/?probe=5bf1258e74) | Dec 03, 2019 |
| HP            | 245 G5 Notebook PC          | [8c201c4443](https://linux-hardware.org/?probe=8c201c4443) | Nov 30, 2019 |
| ASUSTek       | FX503VD                     | [f5dc0694e1](https://linux-hardware.org/?probe=f5dc0694e1) | Nov 28, 2019 |
| ASUSTek       | X406UAR                     | [a1d52e4665](https://linux-hardware.org/?probe=a1d52e4665) | Nov 25, 2019 |
| ASUSTek       | FX503VD                     | [5f33fb689d](https://linux-hardware.org/?probe=5f33fb689d) | Nov 24, 2019 |
| MSI           | GS65 Stealth 9SF            | [dfb909840b](https://linux-hardware.org/?probe=dfb909840b) | Nov 22, 2019 |
| ASUSTek       | FX503VD                     | [e4c827972e](https://linux-hardware.org/?probe=e4c827972e) | Nov 22, 2019 |
| ASUSTek       | FX503VD                     | [a5ad247bdc](https://linux-hardware.org/?probe=a5ad247bdc) | Nov 21, 2019 |
| ASUSTek       | E402NA                      | [07bf7c4021](https://linux-hardware.org/?probe=07bf7c4021) | Nov 10, 2019 |
| Toshiba       | Satellite L745              | [93ab04c913](https://linux-hardware.org/?probe=93ab04c913) | Nov 07, 2019 |
| Apple         | MacBookAir7,2               | [0e1f45ae13](https://linux-hardware.org/?probe=0e1f45ae13) | Oct 22, 2019 |
| Samsung       | RF511/RF411/RF711           | [3f7beb5458](https://linux-hardware.org/?probe=3f7beb5458) | Oct 20, 2019 |
| ASUSTek       | FX503VD                     | [f95cd75d9e](https://linux-hardware.org/?probe=f95cd75d9e) | Oct 08, 2019 |
| Dell          | Inspiron 5421               | [0403587941](https://linux-hardware.org/?probe=0403587941) | Oct 05, 2019 |
| Dell          | Inspiron 5570               | [3fec0285f1](https://linux-hardware.org/?probe=3fec0285f1) | Oct 05, 2019 |
| HP            | Pavilion 15                 | [c6002f59ca](https://linux-hardware.org/?probe=c6002f59ca) | Oct 02, 2019 |
| OX            | PC-9890166                  | [75abcb1b69](https://linux-hardware.org/?probe=75abcb1b69) | Sep 29, 2019 |
| OX            | PC-9890166                  | [9c2460c5e0](https://linux-hardware.org/?probe=9c2460c5e0) | Sep 29, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [5cebf9dcc4](https://linux-hardware.org/?probe=5cebf9dcc4) | Sep 25, 2019 |
| Acer          | Aspire 4736Z                | [a1a9c940fb](https://linux-hardware.org/?probe=a1a9c940fb) | Sep 22, 2019 |
| Sony          | VGN-NR330FE                 | [71126383fe](https://linux-hardware.org/?probe=71126383fe) | Sep 20, 2019 |
| Dell          | Latitude E6420              | [683f31db53](https://linux-hardware.org/?probe=683f31db53) | Sep 19, 2019 |
| HP            | G42                         | [5addde0384](https://linux-hardware.org/?probe=5addde0384) | Sep 15, 2019 |
| HP            | 240 G6 Notebook PC          | [45a420f97b](https://linux-hardware.org/?probe=45a420f97b) | Sep 12, 2019 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [6cbeb4c5dd](https://linux-hardware.org/?probe=6cbeb4c5dd) | Sep 10, 2019 |
| HP            | Unknown                     | [f4e6748e0d](https://linux-hardware.org/?probe=f4e6748e0d) | Sep 06, 2019 |
| Creative V... | C14CT series                | [fe141371eb](https://linux-hardware.org/?probe=fe141371eb) | Sep 04, 2019 |
| HP            | Pavilion Notebook           | [407ab6ce27](https://linux-hardware.org/?probe=407ab6ce27) | Aug 26, 2019 |
| HP            | 240 G6 Notebook PC          | [48697f4bda](https://linux-hardware.org/?probe=48697f4bda) | Aug 22, 2019 |
| OEM           | V40SI2                      | [0ef7e2c60f](https://linux-hardware.org/?probe=0ef7e2c60f) | Aug 22, 2019 |
| ASUSTek       | FX503VD                     | [ae34f8295e](https://linux-hardware.org/?probe=ae34f8295e) | Aug 12, 2019 |
| ASUSTek       | FX503VD                     | [38883ca57b](https://linux-hardware.org/?probe=38883ca57b) | Aug 12, 2019 |
| ASUSTek       | FX503VD                     | [1d12fb594c](https://linux-hardware.org/?probe=1d12fb594c) | Aug 10, 2019 |
| ASUSTek       | FX503VD                     | [b4d34b6e82](https://linux-hardware.org/?probe=b4d34b6e82) | Aug 09, 2019 |
| ASUSTek       | FX503VD                     | [6c73fab2d7](https://linux-hardware.org/?probe=6c73fab2d7) | Aug 09, 2019 |
| Acer          | Swift SF314-52G             | [39291bfee6](https://linux-hardware.org/?probe=39291bfee6) | Aug 06, 2019 |
| HP            | 240 G6 Notebook PC          | [f82cbc8005](https://linux-hardware.org/?probe=f82cbc8005) | Aug 05, 2019 |
| HP            | Laptop 15-bs0xx             | [f416d66db4](https://linux-hardware.org/?probe=f416d66db4) | Jul 31, 2019 |
| HP            | Laptop 15-bs0xx             | [71e60872ea](https://linux-hardware.org/?probe=71e60872ea) | Jul 31, 2019 |
| HP            | Laptop 15-bw0xx             | [0ab5bf5b1a](https://linux-hardware.org/?probe=0ab5bf5b1a) | Jul 27, 2019 |
| HP            | 240 G6 Notebook PC          | [11487c8b52](https://linux-hardware.org/?probe=11487c8b52) | Jul 26, 2019 |
| HP            | 240 G6 Notebook PC          | [83ee2da6f3](https://linux-hardware.org/?probe=83ee2da6f3) | Jul 25, 2019 |
| HP            | Notebook                    | [8ec780e92f](https://linux-hardware.org/?probe=8ec780e92f) | Jul 18, 2019 |
| Dell          | Inspiron 3437               | [30c4e0f323](https://linux-hardware.org/?probe=30c4e0f323) | Jul 16, 2019 |
| Lenovo        | ThinkPad E420 1141RH3       | [72424367ad](https://linux-hardware.org/?probe=72424367ad) | Jul 07, 2019 |
| Samsung       | R430/P430                   | [ec62fdb035](https://linux-hardware.org/?probe=ec62fdb035) | Jul 04, 2019 |
| ASUSTek       | FX503VD                     | [7c30cd3e69](https://linux-hardware.org/?probe=7c30cd3e69) | Jul 02, 2019 |
| ASUSTek       | FX503VD                     | [d125120368](https://linux-hardware.org/?probe=d125120368) | Jul 02, 2019 |
| Toshiba       | Satellite L515              | [3832002e7f](https://linux-hardware.org/?probe=3832002e7f) | Jul 01, 2019 |
| HP            | 240 G6 Notebook PC          | [e97a9cf2c6](https://linux-hardware.org/?probe=e97a9cf2c6) | Jun 29, 2019 |
| Dell          | Latitude E6420              | [3cf5c7994e](https://linux-hardware.org/?probe=3cf5c7994e) | Jun 24, 2019 |
| Sony          | SVF14325CLW                 | [67abaeea89](https://linux-hardware.org/?probe=67abaeea89) | Jun 20, 2019 |
| HP            | 240 G6 Notebook PC          | [7f16c01d91](https://linux-hardware.org/?probe=7f16c01d91) | Jun 18, 2019 |
| HP            | 240 G6 Notebook PC          | [1647f2de79](https://linux-hardware.org/?probe=1647f2de79) | Jun 18, 2019 |
| HP            | 240 G6 Notebook PC          | [793c84cebd](https://linux-hardware.org/?probe=793c84cebd) | Jun 18, 2019 |
| HP            | 240 G6 Notebook PC          | [e333e77665](https://linux-hardware.org/?probe=e333e77665) | Jun 18, 2019 |
| Acer          | Aspire E1-422               | [c32e2104f1](https://linux-hardware.org/?probe=c32e2104f1) | Jun 14, 2019 |
| Acer          | Aspire E1-422               | [8ba524cf2d](https://linux-hardware.org/?probe=8ba524cf2d) | Jun 14, 2019 |
| ASUSTek       | X302LJ                      | [ca06e39372](https://linux-hardware.org/?probe=ca06e39372) | Jun 11, 2019 |
| ASUSTek       | X302LJ                      | [38ba3bc487](https://linux-hardware.org/?probe=38ba3bc487) | Jun 11, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [872526f7f7](https://linux-hardware.org/?probe=872526f7f7) | Jun 10, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [fcc5af7203](https://linux-hardware.org/?probe=fcc5af7203) | Jun 10, 2019 |
| ASUSTek       | X302LJ                      | [96aa51f787](https://linux-hardware.org/?probe=96aa51f787) | Jun 09, 2019 |
| ASUSTek       | X302LJ                      | [5efedcaa21](https://linux-hardware.org/?probe=5efedcaa21) | Jun 09, 2019 |
| ASUSTek       | X302LJ                      | [b1c95fbf3d](https://linux-hardware.org/?probe=b1c95fbf3d) | Jun 09, 2019 |
| Apple         | MacBookPro9,2               | [6819d18bc8](https://linux-hardware.org/?probe=6819d18bc8) | Jun 08, 2019 |
| ASUSTek       | FX503VD                     | [94dffadeba](https://linux-hardware.org/?probe=94dffadeba) | Jun 04, 2019 |
| ASUSTek       | FX503VD                     | [b8b7156cd0](https://linux-hardware.org/?probe=b8b7156cd0) | Jun 04, 2019 |
| Lenovo        | ThinkPad T450 20BUS1DH00    | [3686a559e0](https://linux-hardware.org/?probe=3686a559e0) | May 28, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [10159a71f6](https://linux-hardware.org/?probe=10159a71f6) | May 25, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [5e20d7d4e0](https://linux-hardware.org/?probe=5e20d7d4e0) | May 20, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [24236a720c](https://linux-hardware.org/?probe=24236a720c) | May 20, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [bc3ec67a48](https://linux-hardware.org/?probe=bc3ec67a48) | May 20, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [329c7ece42](https://linux-hardware.org/?probe=329c7ece42) | May 20, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [d6014772c4](https://linux-hardware.org/?probe=d6014772c4) | May 20, 2019 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [1988815ca4](https://linux-hardware.org/?probe=1988815ca4) | May 20, 2019 |
| Dell          | Inspiron M5040              | [6621280c03](https://linux-hardware.org/?probe=6621280c03) | May 14, 2019 |
| HP            | ProBook 5330m               | [79b5425192](https://linux-hardware.org/?probe=79b5425192) | May 11, 2019 |
| HP            | EliteBook 8470p             | [9489581964](https://linux-hardware.org/?probe=9489581964) | May 08, 2019 |
| HP            | EliteBook 8470p             | [55b280af12](https://linux-hardware.org/?probe=55b280af12) | May 07, 2019 |
| Samsung       | RC410/RC510/RC710           | [c780e50507](https://linux-hardware.org/?probe=c780e50507) | May 05, 2019 |
| HP            | Pavilion Notebook           | [2d0e845055](https://linux-hardware.org/?probe=2d0e845055) | May 01, 2019 |
| Dell          | Inspiron M5040              | [bc2495b50a](https://linux-hardware.org/?probe=bc2495b50a) | May 01, 2019 |
| Dell          | Inspiron M5040              | [17879a2dfc](https://linux-hardware.org/?probe=17879a2dfc) | May 01, 2019 |
| HP            | Presario V3000 (GG542LA#... | [e964514e68](https://linux-hardware.org/?probe=e964514e68) | Apr 28, 2019 |
| HP            | Pavilion Gaming Laptop 1... | [37ced39aa5](https://linux-hardware.org/?probe=37ced39aa5) | Apr 23, 2019 |
| Dell          | Inspiron M5040              | [bfc540e551](https://linux-hardware.org/?probe=bfc540e551) | Apr 20, 2019 |
| Dell          | Inspiron M5040              | [6833cf2d42](https://linux-hardware.org/?probe=6833cf2d42) | Apr 20, 2019 |
| HP            | 14                          | [fb281475c9](https://linux-hardware.org/?probe=fb281475c9) | Apr 15, 2019 |
| HP            | 14                          | [178f0eb4e7](https://linux-hardware.org/?probe=178f0eb4e7) | Apr 15, 2019 |
| HP            | ENVY m6                     | [4180a07245](https://linux-hardware.org/?probe=4180a07245) | Apr 13, 2019 |
| HP            | 1000                        | [82d8e28c9e](https://linux-hardware.org/?probe=82d8e28c9e) | Apr 13, 2019 |
| HP            | 1000                        | [43b1a1db40](https://linux-hardware.org/?probe=43b1a1db40) | Apr 13, 2019 |
| HP            | 1000                        | [445d946c9f](https://linux-hardware.org/?probe=445d946c9f) | Apr 12, 2019 |
| HP            | 240 G6 Notebook PC          | [01b46e3429](https://linux-hardware.org/?probe=01b46e3429) | Apr 10, 2019 |
| Sony          | SVE11115ELB                 | [8cd5213bb6](https://linux-hardware.org/?probe=8cd5213bb6) | Apr 10, 2019 |
| HP            | 240 G6 Notebook PC          | [ca36723635](https://linux-hardware.org/?probe=ca36723635) | Apr 10, 2019 |
| Toshiba       | Satellite L305              | [e39a1f246e](https://linux-hardware.org/?probe=e39a1f246e) | Mar 31, 2019 |
| Acer          | Aspire ES1-433G             | [e667efbc30](https://linux-hardware.org/?probe=e667efbc30) | Mar 24, 2019 |
| HP            | ENVY 14                     | [6c4e6833ab](https://linux-hardware.org/?probe=6c4e6833ab) | Mar 24, 2019 |
| HP            | EliteBook 8530w             | [3f7f390254](https://linux-hardware.org/?probe=3f7f390254) | Mar 24, 2019 |
| Lenovo        | G40-70 20369                | [663bc4d39a](https://linux-hardware.org/?probe=663bc4d39a) | Mar 23, 2019 |
| HP            | Mini 110-1000               | [e718456945](https://linux-hardware.org/?probe=e718456945) | Mar 20, 2019 |
| HP            | Pavilion Sleekbook 14 PC    | [f4b4b7905c](https://linux-hardware.org/?probe=f4b4b7905c) | Mar 13, 2019 |
| Lenovo        | V330-14IKB 81B0             | [d317fbeb81](https://linux-hardware.org/?probe=d317fbeb81) | Mar 11, 2019 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | [bb2ab44009](https://linux-hardware.org/?probe=bb2ab44009) | Feb 26, 2019 |
| Lenovo        | IdeaPad 300-14IBR 80M2      | [fff09a2435](https://linux-hardware.org/?probe=fff09a2435) | Feb 26, 2019 |
| Toshiba       | Satellite L305              | [b8b1e3027d](https://linux-hardware.org/?probe=b8b1e3027d) | Feb 17, 2019 |
| Unknown       | Unknown                     | [e0bb4e4cb4](https://linux-hardware.org/?probe=e0bb4e4cb4) | Jan 14, 2019 |
| Toshiba       | Satellite L305              | [9e67a0eae4](https://linux-hardware.org/?probe=9e67a0eae4) | Dec 22, 2018 |
| HP            | Mini 110-1000               | [a3a08e14ca](https://linux-hardware.org/?probe=a3a08e14ca) | Dec 21, 2018 |
| HP            | Mini 110-1000               | [69af53ff8e](https://linux-hardware.org/?probe=69af53ff8e) | Dec 21, 2018 |
| HP            | 245 G5 Notebook PC          | [20db28aad6](https://linux-hardware.org/?probe=20db28aad6) | Dec 08, 2018 |
| Dell          | Latitude E6400              | [719eebfabf](https://linux-hardware.org/?probe=719eebfabf) | Nov 20, 2018 |
| Dell          | Latitude E6400              | [99cbd8eb33](https://linux-hardware.org/?probe=99cbd8eb33) | Nov 10, 2018 |
| Dell          | Latitude E6400              | [6078573db4](https://linux-hardware.org/?probe=6078573db4) | Nov 10, 2018 |
| HP            | Laptop 15-da0xxx            | [88bdb4e503](https://linux-hardware.org/?probe=88bdb4e503) | Oct 27, 2018 |
| HP            | Laptop 15-da0xxx            | [19b85d2469](https://linux-hardware.org/?probe=19b85d2469) | Oct 27, 2018 |
| Apple         | MacBookPro9,2               | [ce4d1a0c42](https://linux-hardware.org/?probe=ce4d1a0c42) | Apr 01, 2018 |
| HP            | Pavilion dv4                | [fead4bde0c](https://linux-hardware.org/?probe=fead4bde0c) | Nov 04, 2017 |
| HP            | Pavilion dv4                | [43c72d9707](https://linux-hardware.org/?probe=43c72d9707) | Oct 26, 2017 |
| Dell          | Precision M6400             | [d399313d03](https://linux-hardware.org/?probe=d399313d03) | Oct 24, 2017 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 68        | 16.39%  |
| Ubuntu 18.04        | 52        | 12.53%  |
| Debian 10           | 15        | 3.61%   |
| Ubuntu 19.04        | 14        | 3.37%   |
| OpenMandriva 4.2    | 11        | 2.65%   |
| Pop!_OS 20.04       | 9         | 2.17%   |
| Linux Mint 20.1     | 9         | 2.17%   |
| Fedora 34           | 9         | 2.17%   |
| Ubuntu 21.10        | 8         | 1.93%   |
| Ubuntu 19.10        | 8         | 1.93%   |
| Fedora 35           | 8         | 1.93%   |
| Debian 11           | 8         | 1.93%   |
| Arch                | 8         | 1.93%   |
| Zorin 16            | 7         | 1.69%   |
| Zorin 15            | 7         | 1.69%   |
| Ubuntu 20.10        | 7         | 1.69%   |
| Manjaro             | 7         | 1.69%   |
| ROSA R10            | 6         | 1.45%   |
| KDE neon 20.04      | 6         | 1.45%   |
| Fedora 33           | 6         | 1.45%   |
| Fedora 32           | 6         | 1.45%   |
| OpenMandriva 4.3    | 5         | 1.2%    |
| Linux Mint 19.3     | 5         | 1.2%    |
| Debian Testing      | 5         | 1.2%    |
| Xubuntu 20.04       | 4         | 0.96%   |
| Ubuntu 21.04        | 4         | 0.96%   |
| Ubuntu 18.10        | 4         | 0.96%   |
| Linux Mint 20.2     | 4         | 0.96%   |
| Linux Mint 20       | 4         | 0.96%   |
| Linux Mint 19.1     | 4         | 0.96%   |
| Kubuntu 20.04       | 4         | 0.96%   |
| Elementary 6.1      | 4         | 0.96%   |
| ArcoLinux Rolling   | 4         | 0.96%   |
| Xubuntu 18.04       | 3         | 0.72%   |
| Ubuntu 16.04        | 3         | 0.72%   |
| ROSA R11            | 3         | 0.72%   |
| Pop!_OS 20.10       | 3         | 0.72%   |
| KDE neon 18.04      | 3         | 0.72%   |
| Ubuntu MATE 20.04   | 2         | 0.48%   |
| Ubuntu MATE 18.04   | 2         | 0.48%   |
| Ubuntu Budgie 21.04 | 2         | 0.48%   |
| ROSA R9             | 2         | 0.48%   |
| Pop!_OS 21.10       | 2         | 0.48%   |
| Pop!_OS 21.04       | 2         | 0.48%   |
| Lubuntu 20.04       | 2         | 0.48%   |
| Kubuntu 19.10       | 2         | 0.48%   |
| Gentoo 2.7          | 2         | 0.48%   |
| Arch Rolling        | 2         | 0.48%   |
| Xubuntu 20.10       | 1         | 0.24%   |
| Ubuntu Budgie 20.04 | 1         | 0.24%   |
| Ubuntu 22.04        | 1         | 0.24%   |
| Ubuntu 17.10        | 1         | 0.24%   |
| Sparky 5.13         | 1         | 0.24%   |
| Solus 4.1           | 1         | 0.24%   |
| Solus 4.0           | 1         | 0.24%   |
| Slackware 14.2      | 1         | 0.24%   |
| ROSA R11.1          | 1         | 0.24%   |
| ROSA 12.2           | 1         | 0.24%   |
| RHEL 8              | 1         | 0.24%   |
| Reborn OS           | 1         | 0.24%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 166       | 41.19%  |
| Linux Mint    | 27        | 6.7%    |
| Fedora        | 27        | 6.7%    |
| Debian        | 27        | 6.7%    |
| OpenMandriva  | 17        | 4.22%   |
| Pop!_OS       | 16        | 3.97%   |
| Zorin         | 14        | 3.47%   |
| ROSA          | 13        | 3.23%   |
| Arch          | 10        | 2.48%   |
| Manjaro       | 9         | 2.23%   |
| KDE neon      | 9         | 2.23%   |
| Xubuntu       | 8         | 1.99%   |
| Elementary    | 7         | 1.74%   |
| Endless       | 5         | 1.24%   |
| Ubuntu MATE   | 4         | 0.99%   |
| openSUSE      | 4         | 0.99%   |
| Lubuntu       | 4         | 0.99%   |
| Kubuntu       | 4         | 0.99%   |
| ArcoLinux     | 4         | 0.99%   |
| Ubuntu Budgie | 3         | 0.74%   |
| Deepin        | 3         | 0.74%   |
| Clear Linux   | 3         | 0.74%   |
| Solus         | 2         | 0.5%    |
| Kali          | 2         | 0.5%    |
| Gentoo        | 2         | 0.5%    |
| Sparky        | 1         | 0.25%   |
| Slackware     | 1         | 0.25%   |
| RHEL          | 1         | 0.25%   |
| Reborn OS     | 1         | 0.25%   |
| Parrot        | 1         | 0.25%   |
| MX            | 1         | 0.25%   |
| LMDE          | 1         | 0.25%   |
| LinuxFX       | 1         | 0.25%   |
| GNOME OS      | 1         | 0.25%   |
| CentOS        | 1         | 0.25%   |
| BlackPanther  | 1         | 0.25%   |
| Artix         | 1         | 0.25%   |
| antergos      | 1         | 0.25%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 10        | 2.2%    |
| 5.4.0-58-generic                | 8         | 1.76%   |
| 5.8.0-48-generic                | 6         | 1.32%   |
| 5.4.0-56-generic                | 6         | 1.32%   |
| 5.4.0-48-generic                | 6         | 1.32%   |
| 5.4.0-42-generic                | 6         | 1.32%   |
| 5.4.0-26-generic                | 6         | 1.32%   |
| 5.11.0-37-generic               | 6         | 1.32%   |
| 5.8.0-50-generic                | 5         | 1.1%    |
| 5.3.0-46-generic                | 5         | 1.1%    |
| 5.16.7-desktop-1omv4003         | 5         | 1.1%    |
| 5.11.0-27-generic               | 5         | 1.1%    |
| 5.0.0-23-generic                | 5         | 1.1%    |
| 4.18.0-15-generic               | 5         | 1.1%    |
| 5.4.0-72-generic                | 4         | 0.88%   |
| 5.4.0-47-generic                | 4         | 0.88%   |
| 5.4.0-37-generic                | 4         | 0.88%   |
| 5.3.0-51-generic                | 4         | 0.88%   |
| 5.3.0-42-generic                | 4         | 0.88%   |
| 5.13.0-30-generic               | 4         | 0.88%   |
| 5.0.0-32-generic                | 4         | 0.88%   |
| 5.0.0-29-generic                | 4         | 0.88%   |
| 5.0.0-27-generic                | 4         | 0.88%   |
| 5.0.0-13-generic                | 4         | 0.88%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 4         | 0.88%   |
| 4.19.0-12-amd64                 | 4         | 0.88%   |
| 4.15.0-20-generic               | 4         | 0.88%   |
| 5.8.0-55-generic                | 3         | 0.66%   |
| 5.8.0-43-generic                | 3         | 0.66%   |
| 5.4.0-7634-generic              | 3         | 0.66%   |
| 5.4.0-73-generic                | 3         | 0.66%   |
| 5.4.0-66-generic                | 3         | 0.66%   |
| 5.4.0-53-generic                | 3         | 0.66%   |
| 5.4.0-52-generic                | 3         | 0.66%   |
| 5.4.0-29-generic                | 3         | 0.66%   |
| 5.4.0-28-generic                | 3         | 0.66%   |
| 5.3.0-53-generic                | 3         | 0.66%   |
| 5.3.0-23-generic                | 3         | 0.66%   |
| 5.14.0-12.1-liquorix-amd64      | 3         | 0.66%   |
| 5.13.0-21-generic               | 3         | 0.66%   |
| 5.0.0-21-generic                | 3         | 0.66%   |
| 5.0.0-20-generic                | 3         | 0.66%   |
| 4.18.0-17-generic               | 3         | 0.66%   |
| 5.8.12-200.fc32.x86_64          | 2         | 0.44%   |
| 5.8.0-59-generic                | 2         | 0.44%   |
| 5.8.0-53-generic                | 2         | 0.44%   |
| 5.8.0-44-generic                | 2         | 0.44%   |
| 5.8.0-26-generic                | 2         | 0.44%   |
| 5.8.0-14-generic                | 2         | 0.44%   |
| 5.4.0-90-generic                | 2         | 0.44%   |
| 5.4.0-77-generic                | 2         | 0.44%   |
| 5.4.0-7642-generic              | 2         | 0.44%   |
| 5.4.0-7626-generic              | 2         | 0.44%   |
| 5.4.0-70-generic                | 2         | 0.44%   |
| 5.4.0-59-generic                | 2         | 0.44%   |
| 5.4.0-54-generic                | 2         | 0.44%   |
| 5.4.0-45-generic                | 2         | 0.44%   |
| 5.4.0-39-generic                | 2         | 0.44%   |
| 5.4.0-33-generic                | 2         | 0.44%   |
| 5.4.0-21-generic                | 2         | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 97        | 22.77%  |
| 5.0.0   | 33        | 7.75%   |
| 5.8.0   | 32        | 7.51%   |
| 5.11.0  | 32        | 7.51%   |
| 5.3.0   | 26        | 6.1%    |
| 4.15.0  | 24        | 5.63%   |
| 4.18.0  | 17        | 3.99%   |
| 5.13.0  | 15        | 3.52%   |
| 4.19.0  | 12        | 2.82%   |
| 5.10.14 | 10        | 2.35%   |
| 5.10.0  | 10        | 2.35%   |
| 5.14.0  | 6         | 1.41%   |
| 5.16.7  | 5         | 1.17%   |
| 4.9.60  | 5         | 1.17%   |
| 4.4.0   | 3         | 0.7%    |
| 5.9.0   | 2         | 0.47%   |
| 5.8.12  | 2         | 0.47%   |
| 5.6.0   | 2         | 0.47%   |
| 5.5.0   | 2         | 0.47%   |
| 5.16.18 | 2         | 0.47%   |
| 5.15.0  | 2         | 0.47%   |
| 5.13.19 | 2         | 0.47%   |
| 5.13.13 | 2         | 0.47%   |
| 5.12.11 | 2         | 0.47%   |
| 5.11.6  | 2         | 0.47%   |
| 5.11.12 | 2         | 0.47%   |
| 5.11.11 | 2         | 0.47%   |
| 5.11.10 | 2         | 0.47%   |
| 5.10.9  | 2         | 0.47%   |
| 4.9.124 | 2         | 0.47%   |
| 5.9.9   | 1         | 0.23%   |
| 5.9.8   | 1         | 0.23%   |
| 5.9.6   | 1         | 0.23%   |
| 5.9.16  | 1         | 0.23%   |
| 5.9.1   | 1         | 0.23%   |
| 5.8.10  | 1         | 0.23%   |
| 5.6.12  | 1         | 0.23%   |
| 5.6.11  | 1         | 0.23%   |
| 5.5.9   | 1         | 0.23%   |
| 5.5.3   | 1         | 0.23%   |
| 5.5.13  | 1         | 0.23%   |
| 5.4.67  | 1         | 0.23%   |
| 5.4.51  | 1         | 0.23%   |
| 5.4.50  | 1         | 0.23%   |
| 5.4.36  | 1         | 0.23%   |
| 5.4.12  | 1         | 0.23%   |
| 5.3.7   | 1         | 0.23%   |
| 5.17.4  | 1         | 0.23%   |
| 5.16.8  | 1         | 0.23%   |
| 5.16.5  | 1         | 0.23%   |
| 5.16.20 | 1         | 0.23%   |
| 5.16.11 | 1         | 0.23%   |
| 5.16.10 | 1         | 0.23%   |
| 5.16.1  | 1         | 0.23%   |
| 5.15.8  | 1         | 0.23%   |
| 5.15.27 | 1         | 0.23%   |
| 5.15.15 | 1         | 0.23%   |
| 5.14.18 | 1         | 0.23%   |
| 5.14.15 | 1         | 0.23%   |
| 5.14.10 | 1         | 0.23%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 102       | 24.11%  |
| 5.11    | 43        | 10.17%  |
| 5.0     | 36        | 8.51%   |
| 5.8     | 35        | 8.27%   |
| 5.10    | 34        | 8.04%   |
| 5.3     | 27        | 6.38%   |
| 4.15    | 24        | 5.67%   |
| 5.13    | 21        | 4.96%   |
| 4.18    | 18        | 4.26%   |
| 5.16    | 13        | 3.07%   |
| 4.19    | 12        | 2.84%   |
| 5.14    | 9         | 2.13%   |
| 4.9     | 9         | 2.13%   |
| 5.12    | 8         | 1.89%   |
| 5.9     | 7         | 1.65%   |
| 5.5     | 5         | 1.18%   |
| 5.15    | 5         | 1.18%   |
| 5.6     | 4         | 0.95%   |
| 4.4     | 4         | 0.95%   |
| 5.1     | 3         | 0.71%   |
| 5.17    | 1         | 0.24%   |
| 4.13    | 1         | 0.24%   |
| 3.10    | 1         | 0.24%   |
| Unknown | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 383       | 96.23%  |
| i686    | 14        | 3.52%   |
| Unknown | 1         | 0.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 185       | 45.34%  |
| Unknown         | 70        | 17.16%  |
| KDE5            | 37        | 9.07%   |
| X-Cinnamon      | 24        | 5.88%   |
| XFCE            | 21        | 5.15%   |
| KDE             | 16        | 3.92%   |
| MATE            | 9         | 2.21%   |
| KDE4            | 9         | 2.21%   |
| Pantheon        | 7         | 1.72%   |
| i3              | 6         | 1.47%   |
| Budgie          | 6         | 1.47%   |
| Cinnamon        | 4         | 0.98%   |
| Deepin          | 3         | 0.74%   |
| Unity           | 2         | 0.49%   |
| qtile           | 2         | 0.49%   |
| LXQt            | 2         | 0.49%   |
| GNOME Flashback | 2         | 0.49%   |
| Trinity         | 1         | 0.25%   |
| LXDE            | 1         | 0.25%   |
| awesome         | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 324       | 79.8%   |
| Wayland | 42        | 10.34%  |
| Unknown | 36        | 8.87%   |
| Tty     | 4         | 0.99%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 262       | 64.69%  |
| GDM     | 53        | 13.09%  |
| SDDM    | 37        | 9.14%   |
| TDM     | 17        | 4.2%    |
| LightDM | 15        | 3.7%    |
| GDM3    | 11        | 2.72%   |
| KDM     | 9         | 2.22%   |
| XDM     | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_CL   | 217       | 53.71%  |
| Unknown | 74        | 18.32%  |
| en_US   | 69        | 17.08%  |
| es_ES   | 22        | 5.45%   |
| es_MX   | 6         | 1.49%   |
| en_GB   | 4         | 0.99%   |
| C       | 4         | 0.99%   |
| es_AR   | 2         | 0.5%    |
| ru_RU   | 1         | 0.25%   |
| fr_FR   | 1         | 0.25%   |
| es_CO   | 1         | 0.25%   |
| es_BO   | 1         | 0.25%   |
| en_CA   | 1         | 0.25%   |
| de_DE   | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 215       | 53.75%  |
| BIOS | 185       | 46.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 329       | 81.64%  |
| Unknown | 33        | 8.19%   |
| Btrfs   | 21        | 5.21%   |
| Overlay | 15        | 3.72%   |
| Xfs     | 4         | 0.99%   |
| Zfs     | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 277       | 68.56%  |
| GPT     | 96        | 23.76%  |
| MBR     | 31        | 7.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 373       | 93.02%  |
| Yes       | 28        | 6.98%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 298       | 73.22%  |
| Yes       | 109       | 26.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                      | Notebooks | Percent |
|---------------------------|-----------|---------|
| Hewlett-Packard           | 116       | 29.22%  |
| Lenovo                    | 70        | 17.63%  |
| Dell                      | 47        | 11.84%  |
| ASUSTek Computer          | 40        | 10.08%  |
| Acer                      | 38        | 9.57%   |
| Samsung Electronics       | 20        | 5.04%   |
| Toshiba                   | 15        | 3.78%   |
| Sony                      | 10        | 2.52%   |
| Packard Bell              | 7         | 1.76%   |
| Apple                     | 7         | 1.76%   |
| Unknown                   | 7         | 1.76%   |
| HUAWEI                    | 4         | 1.01%   |
| MSI                       | 2         | 0.5%    |
| Positivo                  | 1         | 0.25%   |
| Personal Computer Factory | 1         | 0.25%   |
| OX                        | 1         | 0.25%   |
| OEM                       | 1         | 0.25%   |
| Intel                     | 1         | 0.25%   |
| Insyde                    | 1         | 0.25%   |
| HONOR                     | 1         | 0.25%   |
| Google                    | 1         | 0.25%   |
| Elife                     | 1         | 0.25%   |
| Creative Vision           | 1         | 0.25%   |
| Corporativo Lanix         | 1         | 0.25%   |
| Clevo                     | 1         | 0.25%   |
| AMI                       | 1         | 0.25%   |
| Alienware                 | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                           | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| HP Notebook                                    | 9         | 2.27%   |
| Unknown                                        | 9         | 2.27%   |
| HP 240 G6 Notebook PC                          | 6         | 1.51%   |
| HP Pavilion Notebook                           | 5         | 1.26%   |
| HP Pavilion 15                                 | 4         | 1.01%   |
| HP ENVY 15                                     | 4         | 1.01%   |
| HP ProBook 440 G3                              | 3         | 0.76%   |
| HP EliteBook 840 G6                            | 3         | 0.76%   |
| HP 14                                          | 3         | 0.76%   |
| HP 1000                                        | 3         | 0.76%   |
| Dell Latitude E6420                            | 3         | 0.76%   |
| Dell Inspiron 14-3467                          | 3         | 0.76%   |
| Apple MacBookPro9,2                            | 3         | 0.76%   |
| Acer Aspire ES1-111M                           | 3         | 0.76%   |
| Toshiba Satellite C845D                        | 2         | 0.5%    |
| Samsung RF511/RF411/RF711                      | 2         | 0.5%    |
| Samsung 300E5EV/300E4EV/270E5EV/270E4EV/2470EV | 2         | 0.5%    |
| Packard Bell EasyNote MH35                     | 2         | 0.5%    |
| Lenovo Y520-15IKBN 80WK                        | 2         | 0.5%    |
| Lenovo Legion Y530-15ICH 81FV                  | 2         | 0.5%    |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY           | 2         | 0.5%    |
| Lenovo IdeaPad 720S-14IKB 80XC                 | 2         | 0.5%    |
| Lenovo IdeaPad 330S-15ARR 81FB                 | 2         | 0.5%    |
| Lenovo IdeaPad 320-15ABR 80XS                  | 2         | 0.5%    |
| Lenovo G400 20235                              | 2         | 0.5%    |
| HP ProBook 640 G1                              | 2         | 0.5%    |
| HP Pavilion Laptop 15-eh0xxx                   | 2         | 0.5%    |
| HP Pavilion Laptop 15-cw1xxx                   | 2         | 0.5%    |
| HP Pavilion Laptop 15-cw0xxx                   | 2         | 0.5%    |
| HP Pavilion g4                                 | 2         | 0.5%    |
| HP Pavilion dv4                                | 2         | 0.5%    |
| HP Laptop 15-da0xxx                            | 2         | 0.5%    |
| HP Laptop 15-bs0xx                             | 2         | 0.5%    |
| HP ENVY 17 Leap Motion SE NB PC                | 2         | 0.5%    |
| HP EliteBook 2560p                             | 2         | 0.5%    |
| HP 250 G5 Notebook PC                          | 2         | 0.5%    |
| HP 245 G5 Notebook PC                          | 2         | 0.5%    |
| HP 15                                          | 2         | 0.5%    |
| Dell Inspiron N5110                            | 2         | 0.5%    |
| Dell Inspiron M5040                            | 2         | 0.5%    |
| Dell Inspiron 14-3452                          | 2         | 0.5%    |
| ASUS ZenBook UX433FN_UX433FN                   | 2         | 0.5%    |
| ASUS ZenBook UX325EA_UX325EA                   | 2         | 0.5%    |
| ASUS X555LB                                    | 2         | 0.5%    |
| ASUS X302LJ                                    | 2         | 0.5%    |
| ASUS TUF Gaming FX505DT_FX505DT                | 2         | 0.5%    |
| Apple MacBookAir7,2                            | 2         | 0.5%    |
| Acer Swift SF314-42                            | 2         | 0.5%    |
| Acer Aspire ES1-572                            | 2         | 0.5%    |
| Acer Aspire ES1-311                            | 2         | 0.5%    |
| Acer Aspire E1-531                             | 2         | 0.5%    |
| Toshiba Satellite U505                         | 1         | 0.25%   |
| Toshiba Satellite P745D                        | 1         | 0.25%   |
| Toshiba Satellite L745                         | 1         | 0.25%   |
| Toshiba Satellite L515                         | 1         | 0.25%   |
| Toshiba Satellite L505                         | 1         | 0.25%   |
| Toshiba Satellite L45-B                        | 1         | 0.25%   |
| Toshiba Satellite L305                         | 1         | 0.25%   |
| Toshiba Satellite C645                         | 1         | 0.25%   |
| Toshiba Satellite C45-A                        | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| HP Pavilion           | 28        | 7.05%   |
| Acer Aspire           | 28        | 7.05%   |
| Lenovo ThinkPad       | 27        | 6.8%    |
| Lenovo IdeaPad        | 27        | 6.8%    |
| Dell Inspiron         | 22        | 5.54%   |
| Dell Latitude         | 14        | 3.53%   |
| HP EliteBook          | 12        | 3.02%   |
| Toshiba Satellite     | 11        | 2.77%   |
| HP ProBook            | 10        | 2.52%   |
| HP ENVY               | 10        | 2.52%   |
| HP Notebook           | 9         | 2.27%   |
| Unknown               | 9         | 2.27%   |
| HP Laptop             | 8         | 2.02%   |
| HP 240                | 7         | 1.76%   |
| ASUS VivoBook         | 7         | 1.76%   |
| Acer Swift            | 6         | 1.51%   |
| Packard Bell EasyNote | 5         | 1.26%   |
| HP 245                | 5         | 1.26%   |
| Lenovo Legion         | 4         | 1.01%   |
| HP 250                | 4         | 1.01%   |
| Dell Vostro           | 4         | 1.01%   |
| ASUS ZenBook          | 4         | 1.01%   |
| ASUS TUF              | 4         | 1.01%   |
| Toshiba PORTEGE       | 3         | 0.76%   |
| Samsung 300E5EV       | 3         | 0.76%   |
| HP Presario           | 3         | 0.76%   |
| HP 14                 | 3         | 0.76%   |
| HP 1000               | 3         | 0.76%   |
| Dell Precision        | 3         | 0.76%   |
| Apple MacBookPro9     | 3         | 0.76%   |
| Samsung RF511         | 2         | 0.5%    |
| Lenovo Y520-15IKBN    | 2         | 0.5%    |
| Lenovo G400           | 2         | 0.5%    |
| HP 15                 | 2         | 0.5%    |
| Dell XPS              | 2         | 0.5%    |
| ASUS X555LB           | 2         | 0.5%    |
| ASUS X302LJ           | 2         | 0.5%    |
| ASUS ASUS             | 2         | 0.5%    |
| Apple MacBookPro11    | 2         | 0.5%    |
| Apple MacBookAir7     | 2         | 0.5%    |
| Toshiba NB505         | 1         | 0.25%   |
| Sony VPCEG20EL        | 1         | 0.25%   |
| Sony VPCEG15FL        | 1         | 0.25%   |
| Sony VGN-NW215T       | 1         | 0.25%   |
| Sony VGN-NR330FE      | 1         | 0.25%   |
| Sony VGN-FW360TJ      | 1         | 0.25%   |
| Sony SVF14325CLW      | 1         | 0.25%   |
| Sony SVE14A390X       | 1         | 0.25%   |
| Sony SVE14A27CLS      | 1         | 0.25%   |
| Sony SVE14113ELW      | 1         | 0.25%   |
| Sony SVE11115ELB      | 1         | 0.25%   |
| Samsung RV411         | 1         | 0.25%   |
| Samsung RV410         | 1         | 0.25%   |
| Samsung RF712         | 1         | 0.25%   |
| Samsung RC410         | 1         | 0.25%   |
| Samsung R540          | 1         | 0.25%   |
| Samsung R510          | 1         | 0.25%   |
| Samsung R430          | 1         | 0.25%   |
| Samsung 900X3C        | 1         | 0.25%   |
| Samsung 670Z5E        | 1         | 0.25%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2017 | 51        | 12.85%  |
| 2011 | 40        | 10.08%  |
| 2019 | 36        | 9.07%   |
| 2013 | 36        | 9.07%   |
| 2018 | 33        | 8.31%   |
| 2012 | 29        | 7.3%    |
| 2020 | 28        | 7.05%   |
| 2016 | 27        | 6.8%    |
| 2015 | 27        | 6.8%    |
| 2014 | 26        | 6.55%   |
| 2010 | 19        | 4.79%   |
| 2009 | 16        | 4.03%   |
| 2008 | 13        | 3.27%   |
| 2007 | 9         | 2.27%   |
| 2021 | 7         | 1.76%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 397       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 352       | 88.22%  |
| Enabled  | 47        | 11.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 396       | 99.75%  |
| Yes  | 1         | 0.25%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 126       | 31.42%  |
| 3.01-4.0   | 102       | 25.44%  |
| 8.01-16.0  | 72        | 17.96%  |
| 16.01-24.0 | 47        | 11.72%  |
| 1.01-2.0   | 23        | 5.74%   |
| 32.01-64.0 | 12        | 2.99%   |
| 2.01-3.0   | 10        | 2.49%   |
| 24.01-32.0 | 6         | 1.5%    |
| 0.51-1.0   | 2         | 0.5%    |
| Unknown    | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 160       | 36.78%  |
| 2.01-3.0   | 108       | 24.83%  |
| 3.01-4.0   | 62        | 14.25%  |
| 4.01-8.0   | 55        | 12.64%  |
| 0.51-1.0   | 35        | 8.05%   |
| 8.01-16.0  | 10        | 2.3%    |
| 0.01-0.5   | 3         | 0.69%   |
| 24.01-32.0 | 1         | 0.23%   |
| Unknown    | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 317       | 78.86%  |
| 2      | 75        | 18.66%  |
| 3      | 6         | 1.49%   |
| 0      | 4         | 1%      |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 256       | 64.48%  |
| Yes       | 141       | 35.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 347       | 87.41%  |
| No        | 50        | 12.59%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 393       | 98.99%  |
| No        | 4         | 1.01%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 300       | 75%     |
| No        | 100       | 25%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Chile   | 397       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Santiago            | 149       | 35.99%  |
| Las Condes          | 18        | 4.35%   |
| Maipu               | 13        | 3.14%   |
| Puente Alto         | 12        | 2.9%    |
| Temuco              | 11        | 2.66%   |
| Nunoa               | 11        | 2.66%   |
| ViГ±a del Mar     | 10        | 2.42%   |
| Providencia         | 10        | 2.42%   |
| ViÃ±a del Mar     | 9         | 2.17%   |
| Valdivia            | 9         | 2.17%   |
| La Florida          | 9         | 2.17%   |
| ConcepciГіn       | 9         | 2.17%   |
| San Miguel          | 8         | 1.93%   |
| Antofagasta         | 7         | 1.69%   |
| ValparaГ­so       | 5         | 1.21%   |
| Quillota            | 5         | 1.21%   |
| Port Montt          | 5         | 1.21%   |
| San Bernardo        | 4         | 0.97%   |
| QuilpuГ©          | 4         | 0.97%   |
| La Serena           | 4         | 0.97%   |
| Iquique             | 4         | 0.97%   |
| Viña del Mar       | 3         | 0.72%   |
| Punta Arenas        | 3         | 0.72%   |
| Penalolen           | 3         | 0.72%   |
| Osorno              | 3         | 0.72%   |
| Los Ãngeles      | 3         | 0.72%   |
| La Reina            | 3         | 0.72%   |
| La Cisterna         | 3         | 0.72%   |
| Hualpen             | 3         | 0.72%   |
| Coronel             | 3         | 0.72%   |
| Concon              | 3         | 0.72%   |
| Colina              | 3         | 0.72%   |
| ValparaÃ­so       | 2         | 0.48%   |
| Padre Las Casas     | 2         | 0.48%   |
| Los ГЃngeles      | 2         | 0.48%   |
| Los Andes           | 2         | 0.48%   |
| La Cruz             | 2         | 0.48%   |
| La Calera           | 2         | 0.48%   |
| Coquimbo            | 2         | 0.48%   |
| ConcepciÃ³n       | 2         | 0.48%   |
| Chillan             | 2         | 0.48%   |
| Cabrero             | 2         | 0.48%   |
| Arauco              | 2         | 0.48%   |
| Vitacura            | 1         | 0.24%   |
| Villa Alemana       | 1         | 0.24%   |
| Vicuna              | 1         | 0.24%   |
| Victoria            | 1         | 0.24%   |
| Vallenar            | 1         | 0.24%   |
| Talcahuano          | 1         | 0.24%   |
| Talca               | 1         | 0.24%   |
| Santa Cruz          | 1         | 0.24%   |
| San Pedro de la Paz | 1         | 0.24%   |
| San Felipe          | 1         | 0.24%   |
| San Antonio         | 1         | 0.24%   |
| Rio Bueno           | 1         | 0.24%   |
| Requinoa            | 1         | 0.24%   |
| Recoleta            | 1         | 0.24%   |
| Rancagua            | 1         | 0.24%   |
| Quintero            | 1         | 0.24%   |
| QuilpuÃ©          | 1         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 85        | 110    | 18.6%   |
| Seagate                   | 58        | 76     | 12.69%  |
| Toshiba                   | 50        | 57     | 10.94%  |
| Samsung Electronics       | 45        | 56     | 9.85%   |
| Crucial                   | 34        | 36     | 7.44%   |
| Kingston                  | 33        | 43     | 7.22%   |
| HGST                      | 22        | 22     | 4.81%   |
| Hitachi                   | 21        | 22     | 4.6%    |
| Unknown                   | 20        | 26     | 4.38%   |
| SanDisk                   | 20        | 20     | 4.38%   |
| SK Hynix                  | 13        | 14     | 2.84%   |
| Intel                     | 11        | 18     | 2.41%   |
| Apple                     | 6         | 6      | 1.31%   |
| Micron Technology         | 5         | 5      | 1.09%   |
| KingSpec                  | 3         | 10     | 0.66%   |
| China                     | 3         | 4      | 0.66%   |
| LITEON                    | 2         | 2      | 0.44%   |
| KIOXIA                    | 2         | 3      | 0.44%   |
| JMicron                   | 2         | 2      | 0.44%   |
| Corsair                   | 2         | 2      | 0.44%   |
| A-DATA Technology         | 2         | 4      | 0.44%   |
| XPG                       | 1         | 1      | 0.22%   |
| Wdxsky                    | 1         | 1      | 0.22%   |
| walram                    | 1         | 1      | 0.22%   |
| Vaseky                    | 1         | 1      | 0.22%   |
| UMIS                      | 1         | 1      | 0.22%   |
| Phison                    | 1         | 1      | 0.22%   |
| Netac                     | 1         | 1      | 0.22%   |
| Micron/Crucial Technology | 1         | 1      | 0.22%   |
| Mass                      | 1         | 1      | 0.22%   |
| LITEONIT                  | 1         | 1      | 0.22%   |
| Lexar                     | 1         | 5      | 0.22%   |
| KingDian                  | 1         | 2      | 0.22%   |
| HUAWEI                    | 1         | 1      | 0.22%   |
| Hewlett-Packard           | 1         | 1      | 0.22%   |
| Gigabyte Technology       | 1         | 1      | 0.22%   |
| Fujitsu                   | 1         | 1      | 0.22%   |
| FORESEE                   | 1         | 2      | 0.22%   |
| FASPEED                   | 1         | 1      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB               | 11        | 2.31%   |
| Seagate ST1000LM035-1RK172 1TB         | 11        | 2.31%   |
| Toshiba MQ01ABD100 1TB                 | 8         | 1.68%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 8         | 1.68%   |
| Kingston SA400S37480G 480GB SSD        | 7         | 1.47%   |
| Kingston SA400S37240G 240GB SSD        | 7         | 1.47%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 6         | 1.26%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 6         | 1.26%   |
| Samsung NVMe SSD Drive 512GB           | 6         | 1.26%   |
| Crucial CT240BX500SSD1 240GB           | 6         | 1.26%   |
| Crucial CT120BX500SSD1 120GB           | 6         | 1.26%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 5         | 1.05%   |
| Toshiba MQ04ABF100 1TB                 | 5         | 1.05%   |
| Toshiba MQ01ABD075 752GB               | 5         | 1.05%   |
| Seagate ST9500325AS 500GB              | 5         | 1.05%   |
| Seagate ST500LT012-1DG142 500GB        | 5         | 1.05%   |
| HGST HTS545050A7E680 500GB             | 5         | 1.05%   |
| Unknown MMC Card  32GB                 | 4         | 0.84%   |
| Seagate ST500LM021-1KJ152 500GB        | 4         | 0.84%   |
| Sandisk NVMe SSD Drive 500GB           | 4         | 0.84%   |
| Samsung HN-M500MBB 500GB               | 4         | 0.84%   |
| Intel NVMe SSD Drive 512GB             | 4         | 0.84%   |
| Hitachi HTS545050B9A300 500GB          | 4         | 0.84%   |
| HGST HTS541010B7E610 1TB               | 4         | 0.84%   |
| HGST HTS541010A9E680 1TB               | 4         | 0.84%   |
| Crucial CT480BX500SSD1 480GB           | 4         | 0.84%   |
| Crucial CT120BX300SSD1 120GB           | 4         | 0.84%   |
| WDC WDS480G2G0A-00JH30 480GB SSD       | 3         | 0.63%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 3         | 0.63%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 3         | 0.63%   |
| WDC WD2500LPVX-22V0TT0 250GB           | 3         | 0.63%   |
| WDC WD10SPZX-75Z10T2 1TB               | 3         | 0.63%   |
| WDC WD10SPZX-60Z10T0 1TB               | 3         | 0.63%   |
| WDC WD10SPZX-24Z10 1TB                 | 3         | 0.63%   |
| WDC WD10JPVX-22JC3T0 1TB               | 3         | 0.63%   |
| Unknown MMC Card  64GB                 | 3         | 0.63%   |
| Toshiba MQ01ACF050 500GB               | 3         | 0.63%   |
| SK Hynix NVMe SSD Drive 512GB          | 3         | 0.63%   |
| Samsung SSD 850 EVO 250GB              | 3         | 0.63%   |
| Samsung SM963 2.5" NVMe PCIe SSD 128GB | 3         | 0.63%   |
| HGST HTS721010A9E630 1TB               | 3         | 0.63%   |
| Crucial CT1000MX500SSD1 1TB            | 3         | 0.63%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 2         | 0.42%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD       | 2         | 0.42%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD       | 2         | 0.42%   |
| WDC WDS120G1G0A-00SS50 120GB SSD       | 2         | 0.42%   |
| WDC WD5000LPVT-08G33T1 500GB           | 2         | 0.42%   |
| WDC WD5000LPCX-75VHAT0 500GB           | 2         | 0.42%   |
| WDC WD5000LPCX-21VHAT0 500GB           | 2         | 0.42%   |
| WDC WD2500BEVT-22ZCT0 250GB            | 2         | 0.42%   |
| WDC WD10SPCX-60KHST0 1TB               | 2         | 0.42%   |
| WDC WD10JPVX-60JC3T1 1TB               | 2         | 0.42%   |
| WDC WD10JPVX-60JC3T0 1TB               | 2         | 0.42%   |
| Unknown SD64G  64GB                    | 2         | 0.42%   |
| Unknown MMC Card  128GB                | 2         | 0.42%   |
| Toshiba NVMe SSD Drive 512GB           | 2         | 0.42%   |
| Toshiba MQ01ABD032 320GB               | 2         | 0.42%   |
| Toshiba MK3265GSX 320GB                | 2         | 0.42%   |
| SK Hynix HFM512GDJTNI-82A0A 512GB      | 2         | 0.42%   |
| Seagate ST9750420AS 752GB              | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 58        | 70     | 26.98%  |
| Seagate             | 58        | 76     | 26.98%  |
| Toshiba             | 45        | 49     | 20.93%  |
| HGST                | 22        | 22     | 10.23%  |
| Hitachi             | 21        | 22     | 9.77%   |
| Samsung Electronics | 7         | 9      | 3.26%   |
| Apple               | 2         | 2      | 0.93%   |
| Unknown             | 1         | 1      | 0.47%   |
| Fujitsu             | 1         | 1      | 0.47%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Crucial             | 34        | 36     | 22.82%  |
| Kingston            | 27        | 36     | 18.12%  |
| WDC                 | 26        | 36     | 17.45%  |
| Samsung Electronics | 17        | 18     | 11.41%  |
| SanDisk             | 12        | 12     | 8.05%   |
| Apple               | 4         | 4      | 2.68%   |
| KingSpec            | 3         | 10     | 2.01%   |
| China               | 3         | 4      | 2.01%   |
| SK Hynix            | 2         | 2      | 1.34%   |
| JMicron             | 2         | 2      | 1.34%   |
| Intel               | 2         | 3      | 1.34%   |
| Corsair             | 2         | 2      | 1.34%   |
| A-DATA Technology   | 2         | 4      | 1.34%   |
| Wdxsky              | 1         | 1      | 0.67%   |
| Vaseky              | 1         | 1      | 0.67%   |
| Toshiba             | 1         | 4      | 0.67%   |
| Netac               | 1         | 1      | 0.67%   |
| Micron Technology   | 1         | 1      | 0.67%   |
| LITEONIT            | 1         | 1      | 0.67%   |
| LITEON              | 1         | 1      | 0.67%   |
| Lexar               | 1         | 5      | 0.67%   |
| KingDian            | 1         | 2      | 0.67%   |
| Hewlett-Packard     | 1         | 1      | 0.67%   |
| Gigabyte Technology | 1         | 1      | 0.67%   |
| FORESEE             | 1         | 2      | 0.67%   |
| FASPEED             | 1         | 1      | 0.67%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 212       | 252    | 47.96%  |
| SSD     | 140       | 191    | 31.67%  |
| NVMe    | 68        | 91     | 15.38%  |
| MMC     | 19        | 25     | 4.3%    |
| Unknown | 3         | 3      | 0.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 328       | 438    | 77.73%  |
| NVMe | 68        | 91     | 16.11%  |
| MMC  | 19        | 25     | 4.5%    |
| SAS  | 7         | 8      | 1.66%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 235       | 302    | 68.51%  |
| 0.51-1.0   | 105       | 138    | 30.61%  |
| 1.01-2.0   | 3         | 3      | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 251-500    | 134       | 32.6%   |
| 101-250    | 125       | 30.41%  |
| 501-1000   | 65        | 15.82%  |
| 1-20       | 26        | 6.33%   |
| 51-100     | 22        | 5.35%   |
| 21-50      | 16        | 3.89%   |
| 1001-2000  | 14        | 3.41%   |
| Unknown    | 7         | 1.7%    |
| 2001-3000  | 2         | 0.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 183       | 42.76%  |
| 21-50     | 77        | 17.99%  |
| 101-250   | 59        | 13.79%  |
| 51-100    | 51        | 11.92%  |
| 251-500   | 36        | 8.41%   |
| 501-1000  | 14        | 3.27%   |
| Unknown   | 7         | 1.64%   |
| 1001-2000 | 1         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB     | 2         | 2      | 6.67%   |
| HGST HTS545050A7E680 500GB          | 2         | 2      | 6.67%   |
| WDC WDS120G2G0B-00EPW0 120GB SSD    | 1         | 1      | 3.33%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 3.33%   |
| WDC WD5000LPCX-60VHAT0 500GB        | 1         | 1      | 3.33%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 3.33%   |
| Vaseky V820/1TB SSD                 | 1         | 1      | 3.33%   |
| Toshiba MQ01ABD075 752GB            | 1         | 1      | 3.33%   |
| Toshiba MK3265GSX 320GB             | 1         | 1      | 3.33%   |
| Seagate ST9750420AS 752GB           | 1         | 1      | 3.33%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 3.33%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 3.33%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 3.33%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 5      | 3.33%   |
| LITEON CV8-8E128-HP 128GB SSD       | 1         | 1      | 3.33%   |
| Kingston SVP200S3120G 120GB SSD     | 1         | 1      | 3.33%   |
| Hitachi HTS722016K9A300 160GB       | 1         | 1      | 3.33%   |
| Hitachi HTS547564A9E384 640GB       | 1         | 2      | 3.33%   |
| Hitachi HTS545050B9A300 500GB       | 1         | 1      | 3.33%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 3.33%   |
| Hitachi HTS543232L9A300 320GB       | 1         | 1      | 3.33%   |
| HGST HTS725032A7E630 320GB          | 1         | 1      | 3.33%   |
| HGST HTS545050A7E660 500GB          | 1         | 1      | 3.33%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 3.33%   |
| HGST HTS541075A9E680 752GB          | 1         | 1      | 3.33%   |
| HGST HTS541010B7E610 1TB            | 1         | 1      | 3.33%   |
| FASPEED H5-500G SSD                 | 1         | 1      | 3.33%   |
| Crucial CT480M500SSD1 480GB         | 1         | 1      | 3.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 7         | 11     | 23.33%  |
| HGST     | 7         | 7      | 23.33%  |
| Hitachi  | 5         | 6      | 16.67%  |
| WDC      | 4         | 4      | 13.33%  |
| Toshiba  | 2         | 2      | 6.67%   |
| Vaseky   | 1         | 1      | 3.33%   |
| LITEON   | 1         | 1      | 3.33%   |
| Kingston | 1         | 1      | 3.33%   |
| FASPEED  | 1         | 1      | 3.33%   |
| Crucial  | 1         | 1      | 3.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 11     | 29.17%  |
| HGST    | 7         | 7      | 29.17%  |
| Hitachi | 5         | 6      | 20.83%  |
| WDC     | 3         | 3      | 12.5%   |
| Toshiba | 2         | 2      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 29     | 80%     |
| SSD  | 6         | 6      | 20%     |

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
| Detected | 278       | 389    | 67.31%  |
| Works    | 105       | 138    | 25.42%  |
| Malfunc  | 30        | 35     | 7.26%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 278       | 65.72%  |
| AMD                              | 68        | 16.08%  |
| Samsung Electronics              | 27        | 6.38%   |
| Sandisk                          | 12        | 2.84%   |
| SK Hynix                         | 11        | 2.6%    |
| Kingston Technology Company      | 6         | 1.42%   |
| Toshiba America Info Systems     | 4         | 0.95%   |
| Silicon Integrated Systems [SiS] | 4         | 0.95%   |
| Micron Technology                | 4         | 0.95%   |
| Nvidia                           | 2         | 0.47%   |
| KIOXIA                           | 2         | 0.47%   |
| Union Memory (Shenzhen)          | 1         | 0.24%   |
| Phison Electronics               | 1         | 0.24%   |
| Micron/Crucial Technology        | 1         | 0.24%   |
| Lite-On Technology               | 1         | 0.24%   |
| ADATA Technology                 | 1         | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 57        | 12.64%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 53        | 11.75%  |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 34        | 7.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 21        | 4.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 19        | 4.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 18        | 3.99%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 16        | 3.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 13        | 2.88%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 12        | 2.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 11        | 2.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 9         | 2%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 8         | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 8         | 1.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 8         | 1.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 1.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 6         | 1.33%   |
| SK Hynix BC511                                                                         | 5         | 1.11%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 5         | 1.11%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 5         | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 5         | 1.11%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 5         | 1.11%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 4         | 0.89%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 4         | 0.89%   |
| Samsung NVMe SSD Controller 980                                                        | 4         | 0.89%   |
| Micron Non-Volatile memory controller                                                  | 4         | 0.89%   |
| Intel SSD 660P Series                                                                  | 4         | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 4         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 4         | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 4         | 0.89%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 4         | 0.89%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 4         | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 4         | 0.89%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 0.89%   |
| SK Hynix Non-Volatile memory controller                                                | 3         | 0.67%   |
| SK Hynix Gold P31 SSD                                                                  | 3         | 0.67%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 3         | 0.67%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 3         | 0.67%   |
| Intel Non-Volatile memory controller                                                   | 3         | 0.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 3         | 0.67%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 3         | 0.67%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 0.44%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                              | 2         | 0.44%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                        | 2         | 0.44%   |
| Samsung Electronics SATA controller                                                    | 2         | 0.44%   |
| Samsung Apple PCIe SSD                                                                 | 2         | 0.44%   |
| KIOXIA Non-Volatile memory controller                                                  | 2         | 0.44%   |
| Kingston Company Company Non-Volatile memory controller                                | 2         | 0.44%   |
| Kingston Company SNVS2000G [NV1 NVMe PCIe SSD 2TB]                                     | 2         | 0.44%   |
| Kingston Company A2000 NVMe SSD                                                        | 2         | 0.44%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 2         | 0.44%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 2         | 0.44%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 2         | 0.44%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                          | 2         | 0.44%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 2         | 0.44%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 0.44%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 2         | 0.44%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 2         | 0.44%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                   | 2         | 0.44%   |
| Union Memory (Shenzhen) NVMe 256G SSD device                                           | 1         | 0.22%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller       | 1         | 0.22%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 305       | 70.93%  |
| NVMe | 69        | 16.05%  |
| RAID | 28        | 6.51%   |
| IDE  | 28        | 6.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 312       | 78.59%  |
| AMD    | 85        | 21.41%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz               | 10        | 2.52%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 10        | 2.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 8         | 2.02%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 7         | 1.76%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 6         | 1.51%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 6         | 1.51%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz              | 6         | 1.51%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 5         | 1.26%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 5         | 1.26%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 5         | 1.26%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 4         | 1.01%   |
| Intel Core i7-6600U CPU @ 2.60GHz               | 4         | 1.01%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 4         | 1.01%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 4         | 1.01%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 4         | 1.01%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 4         | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 4         | 1.01%   |
| AMD Ryzen 3 4300U with Radeon Graphics          | 4         | 1.01%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz     | 3         | 0.76%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz              | 3         | 0.76%   |
| Intel Core i7-4500U CPU @ 1.80GHz               | 3         | 0.76%   |
| Intel Core i5-9300H CPU @ 2.40GHz               | 3         | 0.76%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 3         | 0.76%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 3         | 0.76%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 3         | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 3         | 0.76%   |
| Intel Core i5-2430M CPU @ 2.40GHz               | 3         | 0.76%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 3         | 0.76%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 3         | 0.76%   |
| Intel Core i3 CPU M 370 @ 2.40GHz               | 3         | 0.76%   |
| Intel Core 2 Duo CPU T9400 @ 2.53GHz            | 3         | 0.76%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 3         | 0.76%   |
| Intel Celeron CPU 3955U @ 2.00GHz               | 3         | 0.76%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 3         | 0.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 0.76%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 3         | 0.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 3         | 0.76%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx   | 3         | 0.76%   |
| AMD E2-1800 APU with Radeon HD Graphics         | 3         | 0.76%   |
| AMD E-300 APU with Radeon HD Graphics           | 3         | 0.76%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics     | 3         | 0.76%   |
| AMD A8-6410 APU with AMD Radeon R5 Graphics     | 3         | 0.76%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 3         | 0.76%   |
| AMD A10-8700P Radeon R6, 10 Compute Cores 4C+6G | 3         | 0.76%   |
| AMD A10-5750M APU with Radeon HD Graphics       | 3         | 0.76%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz        | 2         | 0.5%    |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 2         | 0.5%    |
| Intel Pentium Dual CPU T3400 @ 2.16GHz          | 2         | 0.5%    |
| Intel Pentium CPU N4200 @ 1.10GHz               | 2         | 0.5%    |
| Intel Pentium CPU B960 @ 2.20GHz                | 2         | 0.5%    |
| Intel Pentium CPU 5405U @ 2.30GHz               | 2         | 0.5%    |
| Intel Pentium CPU 3825U @ 1.90GHz               | 2         | 0.5%    |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 0.5%    |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 0.5%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 2         | 0.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 0.5%    |
| Intel Core i7-5500U CPU @ 2.40GHz               | 2         | 0.5%    |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 0.5%    |
| Intel Core i7-4600M CPU @ 2.90GHz               | 2         | 0.5%    |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 93        | 23.43%  |
| Intel Core i7           | 70        | 17.63%  |
| Intel Core i3           | 40        | 10.08%  |
| Intel Celeron           | 32        | 8.06%   |
| Intel Pentium           | 21        | 5.29%   |
| Intel Atom              | 13        | 3.27%   |
| Intel Core 2 Duo        | 12        | 3.02%   |
| AMD Ryzen 5             | 10        | 2.52%   |
| AMD Ryzen 7             | 9         | 2.27%   |
| AMD A10                 | 9         | 2.27%   |
| Other                   | 8         | 2.02%   |
| Intel Pentium Dual-Core | 7         | 1.76%   |
| AMD Ryzen 3             | 7         | 1.76%   |
| AMD A8                  | 7         | 1.76%   |
| AMD E2                  | 6         | 1.51%   |
| Intel Pentium Dual      | 5         | 1.26%   |
| AMD A6                  | 5         | 1.26%   |
| AMD E1                  | 4         | 1.01%   |
| AMD E                   | 4         | 1.01%   |
| AMD A12                 | 4         | 1.01%   |
| Intel Genuine           | 3         | 0.76%   |
| Intel Celeron Dual-Core | 3         | 0.76%   |
| AMD Turion II Dual-Core | 3         | 0.76%   |
| AMD A4                  | 3         | 0.76%   |
| Intel Pentium Silver    | 2         | 0.5%    |
| AMD Ryzen 7 PRO         | 2         | 0.5%    |
| AMD Ryzen 5 PRO         | 2         | 0.5%    |
| AMD Mobile Sempron      | 2         | 0.5%    |
| AMD C-60                | 2         | 0.5%    |
| AMD Athlon II           | 2         | 0.5%    |
| Intel Xeon              | 1         | 0.25%   |
| Intel Core m5           | 1         | 0.25%   |
| Intel Core i9           | 1         | 0.25%   |
| Intel Core Duo          | 1         | 0.25%   |
| Intel Core 2 Extreme    | 1         | 0.25%   |
| AMD C-50                | 1         | 0.25%   |
| AMD Athlon X2           | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 244       | 61.31%  |
| 4       | 125       | 31.41%  |
| 8       | 9         | 2.26%   |
| 6       | 8         | 2.01%   |
| 1       | 7         | 1.76%   |
| Unknown | 5         | 1.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 395       | 99.5%   |
| 4       | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 252       | 63.32%  |
| 1       | 141       | 35.43%  |
| Unknown | 5         | 1.26%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 379       | 94.99%  |
| Unknown        | 10        | 2.51%   |
| 64-bit         | 5         | 1.25%   |
| 32-bit         | 5         | 1.25%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 59        | 14.71%  |
| 0x206a7    | 29        | 7.23%   |
| 0x406e3    | 26        | 6.48%   |
| 0x306a9    | 21        | 5.24%   |
| 0x40651    | 18        | 4.49%   |
| 0x806e9    | 16        | 3.99%   |
| 0x1067a    | 15        | 3.74%   |
| 0x806ec    | 13        | 3.24%   |
| 0x30678    | 13        | 3.24%   |
| 0x806ea    | 11        | 2.74%   |
| 0x906ea    | 10        | 2.49%   |
| 0x306d4    | 10        | 2.49%   |
| 0x20655    | 10        | 2.49%   |
| 0x05000119 | 9         | 2.24%   |
| 0x906e9    | 8         | 2%      |
| 0x6fd      | 8         | 2%      |
| 0x406c4    | 7         | 1.75%   |
| 0x306c3    | 7         | 1.75%   |
| 0x08108102 | 6         | 1.5%    |
| 0x0810100b | 6         | 1.5%    |
| 0x406c3    | 5         | 1.25%   |
| 0x08600106 | 5         | 1.25%   |
| 0xa0652    | 4         | 1%      |
| 0x806c1    | 4         | 1%      |
| 0x706a1    | 4         | 1%      |
| 0x506c9    | 4         | 1%      |
| 0x07030106 | 4         | 1%      |
| 0x07030105 | 4         | 1%      |
| 0x0700010f | 4         | 1%      |
| 0x706e5    | 3         | 0.75%   |
| 0x106ca    | 3         | 0.75%   |
| 0x106c2    | 3         | 0.75%   |
| 0x10676    | 3         | 0.75%   |
| 0x0a50000c | 3         | 0.75%   |
| 0x08108109 | 3         | 0.75%   |
| 0x06001119 | 3         | 0.75%   |
| 0x806eb    | 2         | 0.5%    |
| 0x706a8    | 2         | 0.5%    |
| 0x506e3    | 2         | 0.5%    |
| 0x20652    | 2         | 0.5%    |
| 0x08600103 | 2         | 0.5%    |
| 0x08600102 | 2         | 0.5%    |
| 0x06006705 | 2         | 0.5%    |
| 0x06006704 | 2         | 0.5%    |
| 0x0600611a | 2         | 0.5%    |
| 0x05000029 | 2         | 0.5%    |
| 0x03000027 | 2         | 0.5%    |
| 0x010000c8 | 2         | 0.5%    |
| 0x6fb      | 1         | 0.25%   |
| 0x6ec      | 1         | 0.25%   |
| 0x6e8      | 1         | 0.25%   |
| 0x40661    | 1         | 0.25%   |
| 0x30661    | 1         | 0.25%   |
| 0x08600104 | 1         | 0.25%   |
| 0x08101016 | 1         | 0.25%   |
| 0x07000110 | 1         | 0.25%   |
| 0x06006118 | 1         | 0.25%   |
| 0x06006110 | 1         | 0.25%   |
| 0x06003106 | 1         | 0.25%   |
| 0x0600111f | 1         | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 76        | 19.14%  |
| SandyBridge     | 36        | 9.07%   |
| Skylake         | 32        | 8.06%   |
| Haswell         | 29        | 7.3%    |
| Silvermont      | 26        | 6.55%   |
| IvyBridge       | 24        | 6.05%   |
| Penryn          | 21        | 5.29%   |
| Westmere        | 14        | 3.53%   |
| Excavator       | 12        | 3.02%   |
| Bobcat          | 12        | 3.02%   |
| Zen 2           | 11        | 2.77%   |
| Broadwell       | 11        | 2.77%   |
| Zen+            | 9         | 2.27%   |
| Puma            | 9         | 2.27%   |
| Core            | 9         | 2.27%   |
| Zen             | 7         | 1.76%   |
| Bonnell         | 7         | 1.76%   |
| TigerLake       | 6         | 1.51%   |
| Piledriver      | 6         | 1.51%   |
| Goldmont plus   | 6         | 1.51%   |
| K10             | 5         | 1.26%   |
| Jaguar          | 5         | 1.26%   |
| CometLake       | 5         | 1.26%   |
| Goldmont        | 4         | 1.01%   |
| Zen 3           | 3         | 0.76%   |
| IceLake         | 3         | 0.76%   |
| P6              | 2         | 0.5%    |
| K8 Hammer       | 2         | 0.5%    |
| K10 Llano       | 2         | 0.5%    |
| Steamroller     | 1         | 0.25%   |
| K8 & K10 hybrid | 1         | 0.25%   |
| Unknown         | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 292       | 59.59%  |
| AMD                              | 105       | 21.43%  |
| Nvidia                           | 88        | 17.96%  |
| Silicon Integrated Systems [SiS] | 4         | 0.82%   |
| ATI Technologies                 | 1         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 34        | 6.56%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 4.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 23        | 4.44%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 19        | 3.67%   |
| Intel HD Graphics 620                                                                    | 18        | 3.47%   |
| Intel UHD Graphics 620                                                                   | 15        | 2.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 2.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 14        | 2.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 2.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 2.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 2.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.12%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 2.12%   |
| AMD Renoir                                                                               | 11        | 2.12%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 1.93%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 1.74%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 9         | 1.74%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 1.74%   |
| Intel HD Graphics 630                                                                    | 8         | 1.54%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.35%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 7         | 1.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 1.35%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 7         | 1.35%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 1.16%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 1.16%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.97%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.97%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.97%   |
| Intel HD Graphics 510                                                                    | 5         | 0.97%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.97%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 0.97%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 5         | 0.97%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 4         | 0.77%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 0.77%   |
| Nvidia TU117M                                                                            | 4         | 0.77%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 4         | 0.77%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.77%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 0.77%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 0.77%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 4         | 0.77%   |
| AMD Mars [Radeon HD 8670A/8670M/8750M / R7 M370]                                         | 4         | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 3         | 0.58%   |
| Nvidia GK107M [GeForce GT 750M]                                                          | 3         | 0.58%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 3         | 0.58%   |
| AMD Wrestler [Radeon HD 7340]                                                            | 3         | 0.58%   |
| AMD Richland [Radeon HD 8650G]                                                           | 3         | 0.58%   |
| AMD Cezanne                                                                              | 3         | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.39%   |
| Nvidia GT218M [GeForce 315M]                                                             | 2         | 0.39%   |
| Nvidia GM108M [GeForce MX110]                                                            | 2         | 0.39%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.39%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.39%   |
| Nvidia GM107GLM [Quadro M1200 Mobile]                                                    | 2         | 0.39%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 2         | 0.39%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.39%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.39%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 2         | 0.39%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 207       | 52.14%  |
| Intel + Nvidia | 67        | 16.88%  |
| 1 x AMD        | 62        | 15.62%  |
| 2 x AMD        | 18        | 4.53%   |
| Intel + AMD    | 18        | 4.53%   |
| 1 x Nvidia     | 13        | 3.27%   |
| AMD + Nvidia   | 8         | 2.02%   |
| 1 x SiS        | 4         | 1.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 342       | 85.93%  |
| Proprietary | 43        | 10.8%   |
| Unknown     | 13        | 3.27%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 236       | 58.56%  |
| 0.01-0.5   | 60        | 14.89%  |
| 1.01-2.0   | 56        | 13.9%   |
| 0.51-1.0   | 25        | 6.2%    |
| 3.01-4.0   | 22        | 5.46%   |
| 2.01-3.0   | 2         | 0.5%    |
| 7.01-8.0   | 1         | 0.25%   |
| 5.01-6.0   | 1         | 0.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 83        | 18.74%  |
| BOE                     | 77        | 17.38%  |
| Samsung Electronics     | 63        | 14.22%  |
| Chimei Innolux          | 62        | 14%     |
| LG Display              | 55        | 12.42%  |
| Goldstar                | 15        | 3.39%   |
| Lenovo                  | 8         | 1.81%   |
| Chi Mei Optoelectronics | 8         | 1.81%   |
| Apple                   | 7         | 1.58%   |
| PANDA                   | 6         | 1.35%   |
| InfoVision              | 6         | 1.35%   |
| AOC                     | 5         | 1.13%   |
| ViewSonic               | 4         | 0.9%    |
| Sharp                   | 4         | 0.9%    |
| Dell                    | 4         | 0.9%    |
| Unknown                 | 3         | 0.68%   |
| Sony                    | 3         | 0.68%   |
| Envision                | 3         | 0.68%   |
| CSO                     | 3         | 0.68%   |
| ASUSTek Computer        | 3         | 0.68%   |
| SAC                     | 2         | 0.45%   |
| LGD                     | 2         | 0.45%   |
| LG Philips              | 2         | 0.45%   |
| Hewlett-Packard         | 2         | 0.45%   |
| CPT                     | 2         | 0.45%   |
| Ancor Communications    | 2         | 0.45%   |
| Acer                    | 2         | 0.45%   |
| ___                     | 1         | 0.23%   |
| SGT                     | 1         | 0.23%   |
| NCS                     | 1         | 0.23%   |
| MSI                     | 1         | 0.23%   |
| InnoLux Display         | 1         | 0.23%   |
| Hitachi                 | 1         | 0.23%   |
| ELD                     | 1         | 0.23%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 7         | 1.56%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 5         | 1.11%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 5         | 1.11%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 5         | 1.11%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 5         | 1.11%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 4         | 0.89%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 4         | 0.89%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 4         | 0.89%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 0.89%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch     | 3         | 0.67%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 3         | 0.67%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.67%   |
| Envision L32W931 EPI2009 1360x768 696x392mm 31.4-inch                    | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch          | 3         | 0.67%   |
| Chimei Innolux LCD Monitor CMN1493 1366x768 309x173mm 13.9-inch          | 3         | 0.67%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 3         | 0.67%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 3         | 0.67%   |
| BOE LCD Monitor BOE0628 1366x768 309x173mm 13.9-inch                     | 3         | 0.67%   |
| BOE LCD Monitor BOE0602 1366x768 344x193mm 15.5-inch                     | 3         | 0.67%   |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                     | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch            | 3         | 0.67%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 3         | 0.67%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                           | 3         | 0.67%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch     | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch     | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SEC335A 1366x768 309x174mm 14.0-inch     | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4E42 1366x768 309x174mm 14.0-inch     | 2         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch    | 2         | 0.45%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.45%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 2         | 0.45%   |
| LG Display LCD Monitor LGD03FA 1366x768 310x174mm 14.0-inch              | 2         | 0.45%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 2         | 0.45%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch              | 2         | 0.45%   |
| LG Display LCD Monitor LGD0372 1600x900 382x215mm 17.3-inch              | 2         | 0.45%   |
| LG Display LCD Monitor LGD033F 1366x768 310x174mm 14.0-inch              | 2         | 0.45%   |
| Lenovo LCD Monitor LEN4033 1440x900 304x190mm 14.1-inch                  | 2         | 0.45%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch             | 2         | 0.45%   |
| InfoVision LCD Monitor IVO057A 1366x768 309x174mm 14.0-inch              | 2         | 0.45%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 2         | 0.45%   |
| Goldstar E2360 GSM57E4 1920x1080 510x290mm 23.1-inch                     | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN14D2 1920x1080 309x173mm 13.9-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch          | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch          | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch         | 2         | 0.45%   |
| Chimei Innolux LCD Monitor CMN1362 1366x768 293x164mm 13.2-inch          | 2         | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1444 1366x768 309x174mm 14.0-inch | 2         | 0.45%   |
| Chi Mei Optoelectronics LCD Monitor CMO1425 1280x800 303x190mm 14.1-inch | 2         | 0.45%   |
| BOE LCD Monitor BOE0920 1366x768 344x194mm 15.5-inch                     | 2         | 0.45%   |
| BOE LCD Monitor BOE08E8 1920x1080 344x194mm 15.5-inch                    | 2         | 0.45%   |
| BOE LCD Monitor BOE0868 1920x1080 309x174mm 14.0-inch                    | 2         | 0.45%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                    | 2         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 216       | 50.82%  |
| 1920x1080 (FHD)    | 117       | 27.53%  |
| 1600x900 (HD+)     | 19        | 4.47%   |
| 1280x800 (WXGA)    | 14        | 3.29%   |
| 3840x2160 (4K)     | 9         | 2.12%   |
| 1360x768           | 9         | 2.12%   |
| 1440x900 (WXGA+)   | 7         | 1.65%   |
| 1920x1200 (WUXGA)  | 4         | 0.94%   |
| 1680x1050 (WSXGA+) | 4         | 0.94%   |
| 1280x1024 (SXGA)   | 4         | 0.94%   |
| 1024x600           | 3         | 0.71%   |
| 3440x1440          | 2         | 0.47%   |
| 2560x1600          | 2         | 0.47%   |
| 2560x1080          | 2         | 0.47%   |
| 2160x1440          | 2         | 0.47%   |
| 1024x576           | 2         | 0.47%   |
| Unknown            | 2         | 0.47%   |
| 5440x1800          | 1         | 0.24%   |
| 3840x1100          | 1         | 0.24%   |
| 3286x1080          | 1         | 0.24%   |
| 2560x1440 (QHD)    | 1         | 0.24%   |
| 2288x1287          | 1         | 0.24%   |
| 1920x540           | 1         | 0.24%   |
| 1680x945           | 1         | 0.24%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 131       | 29.31%  |
| 13      | 103       | 23.04%  |
| 14      | 98        | 21.92%  |
| 23      | 17        | 3.8%    |
| 17      | 12        | 2.68%   |
| 21      | 11        | 2.46%   |
| 24      | 8         | 1.79%   |
| 19      | 7         | 1.57%   |
| 10      | 7         | 1.57%   |
| 31      | 6         | 1.34%   |
| 27      | 6         | 1.34%   |
| 11      | 6         | 1.34%   |
| Unknown | 6         | 1.34%   |
| 12      | 5         | 1.12%   |
| 72      | 4         | 0.89%   |
| 34      | 4         | 0.89%   |
| 20      | 3         | 0.67%   |
| 18      | 3         | 0.67%   |
| 54      | 2         | 0.45%   |
| 48      | 2         | 0.45%   |
| 22      | 2         | 0.45%   |
| 142     | 1         | 0.22%   |
| 84      | 1         | 0.22%   |
| 32      | 1         | 0.22%   |
| 16      | 1         | 0.22%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 300       | 67.72%  |
| 201-300        | 47        | 10.61%  |
| 501-600        | 29        | 6.55%   |
| 401-500        | 21        | 4.74%   |
| 351-400        | 18        | 4.06%   |
| 601-700        | 7         | 1.58%   |
| Unknown        | 6         | 1.35%   |
| 701-800        | 5         | 1.13%   |
| 1501-2000      | 5         | 1.13%   |
| 1001-1500      | 4         | 0.9%    |
| More than 2000 | 1         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 335       | 86.12%  |
| 16/10   | 35        | 9%      |
| 5/4     | 4         | 1.03%   |
| 21/9    | 4         | 1.03%   |
| Unknown | 4         | 1.03%   |
| 4/3     | 2         | 0.51%   |
| 3/2     | 2         | 0.51%   |
| 3.40    | 1         | 0.26%   |
| 1.96    | 1         | 0.26%   |
| 1.00    | 1         | 0.26%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 174       | 39.01%  |
| 101-110        | 130       | 29.15%  |
| 201-250        | 32        | 7.17%   |
| 71-80          | 26        | 5.83%   |
| 151-200        | 13        | 2.91%   |
| 351-500        | 11        | 2.47%   |
| More than 1000 | 9         | 2.02%   |
| 121-130        | 9         | 2.02%   |
| 51-60          | 7         | 1.57%   |
| 41-50          | 7         | 1.57%   |
| 301-350        | 6         | 1.35%   |
| Unknown        | 6         | 1.35%   |
| 61-70          | 4         | 0.9%    |
| 141-150        | 4         | 0.9%    |
| 251-300        | 2         | 0.45%   |
| 131-140        | 2         | 0.45%   |
| 111-120        | 2         | 0.45%   |
| 501-1000       | 1         | 0.22%   |
| 91-100         | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 231       | 52.26%  |
| 121-160       | 108       | 24.43%  |
| 51-100        | 64        | 14.48%  |
| 161-240       | 16        | 3.62%   |
| 1-50          | 13        | 2.94%   |
| Unknown       | 6         | 1.36%   |
| More than 240 | 4         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 314       | 77.53%  |
| 2     | 72        | 17.78%  |
| 0     | 14        | 3.46%   |
| 3     | 5         | 1.23%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 261       | 40.09%  |
| Intel                            | 147       | 22.58%  |
| Qualcomm Atheros                 | 108       | 16.59%  |
| Broadcom                         | 47        | 7.22%   |
| Ralink                           | 13        | 2%      |
| Huawei Technologies              | 10        | 1.54%   |
| Broadcom Limited                 | 9         | 1.38%   |
| Marvell Technology Group         | 8         | 1.23%   |
| Ralink Technology                | 7         | 1.08%   |
| TP-Link                          | 6         | 0.92%   |
| Silicon Integrated Systems [SiS] | 4         | 0.61%   |
| Samsung Electronics              | 4         | 0.61%   |
| Qualcomm Atheros Communications  | 4         | 0.61%   |
| Xiaomi                           | 3         | 0.46%   |
| MEDIATEK                         | 3         | 0.46%   |
| JMicron Technology               | 3         | 0.46%   |
| Nvidia                           | 2         | 0.31%   |
| ICS Advent                       | 2         | 0.31%   |
| D-Link                           | 2         | 0.31%   |
| Qcom                             | 1         | 0.15%   |
| Microsoft                        | 1         | 0.15%   |
| Microchip Technology             | 1         | 0.15%   |
| Hewlett-Packard                  | 1         | 0.15%   |
| DisplayLink                      | 1         | 0.15%   |
| D-Link System                    | 1         | 0.15%   |
| ASUSTek Computer                 | 1         | 0.15%   |
| Arduino SA                       | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 152       | 19.36%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 77        | 9.81%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 26        | 3.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 21        | 2.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 19        | 2.42%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 2.17%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 14        | 1.78%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 1.78%   |
| Intel Wireless 8260                                                     | 13        | 1.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.53%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 1.53%   |
| Intel Wireless 8265 / 8275                                              | 11        | 1.4%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 10        | 1.27%   |
| Intel Wireless 7260                                                     | 10        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 1.27%   |
| Intel Wireless 7265                                                     | 9         | 1.15%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 1.15%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.02%   |
| Intel Ethernet Connection I219-LM                                       | 8         | 1.02%   |
| Huawei JNY-LX1                                                          | 8         | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 0.89%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.89%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 0.89%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 0.76%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 6         | 0.76%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 0.76%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 0.64%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 5         | 0.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.64%   |
| Intel Wireless 3165                                                     | 5         | 0.64%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 0.64%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.64%   |
| TP-Link 802.11ac WLAN Adapter                                           | 4         | 0.51%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 4         | 0.51%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.51%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.51%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.51%   |
| Intel Wireless 3160                                                     | 4         | 0.51%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.51%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                                    | 4         | 0.51%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.51%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 4         | 0.51%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                                | 4         | 0.51%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.38%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.38%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.38%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 0.38%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 3         | 0.38%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.38%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.38%   |
| Intel Ethernet Connection (3) I218-LM                                   | 3         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 142       | 33.81%  |
| Realtek Semiconductor           | 96        | 22.86%  |
| Qualcomm Atheros                | 95        | 22.62%  |
| Broadcom                        | 39        | 9.29%   |
| Ralink                          | 13        | 3.1%    |
| Broadcom Limited                | 8         | 1.9%    |
| Ralink Technology               | 7         | 1.67%   |
| TP-Link                         | 6         | 1.43%   |
| Qualcomm Atheros Communications | 4         | 0.95%   |
| MEDIATEK                        | 3         | 0.71%   |
| Samsung Electronics             | 1         | 0.24%   |
| Qcom                            | 1         | 0.24%   |
| Microsoft                       | 1         | 0.24%   |
| Hewlett-Packard                 | 1         | 0.24%   |
| D-Link System                   | 1         | 0.24%   |
| D-Link                          | 1         | 0.24%   |
| ASUSTek Computer                | 1         | 0.24%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 26        | 6.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 21        | 4.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 19        | 4.5%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 4.03%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 14        | 3.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 3.32%   |
| Intel Wireless 8260                                                     | 13        | 3.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 13        | 3.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 12        | 2.84%   |
| Intel Wi-Fi 6 AX200                                                     | 12        | 2.84%   |
| Intel Wireless 8265 / 8275                                              | 11        | 2.61%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 10        | 2.37%   |
| Intel Wireless 7260                                                     | 10        | 2.37%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 2.37%   |
| Intel Wireless 7265                                                     | 9         | 2.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 9         | 2.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 1.9%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 1.66%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 1.66%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 6         | 1.42%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.42%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 6         | 1.42%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 5         | 1.18%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 5         | 1.18%   |
| Intel Wireless 3165                                                     | 5         | 1.18%   |
| Intel Wi-Fi 6 AX201                                                     | 5         | 1.18%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.18%   |
| TP-Link 802.11ac WLAN Adapter                                           | 4         | 0.95%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.95%   |
| Qualcomm Atheros AR9271 802.11n                                         | 4         | 0.95%   |
| Intel Wireless 3160                                                     | 4         | 0.95%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 4         | 0.95%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 4         | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.95%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 3         | 0.71%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.71%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.71%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 0.71%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 3         | 0.71%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 0.71%   |
| Intel Centrino Wireless-N 2230                                          | 3         | 0.71%   |
| Intel Centrino Wireless-N 130                                           | 3         | 0.71%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 3         | 0.71%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 0.71%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 0.71%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 0.71%   |
| MEDIATEK MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.47%   |
| Intel Wireless-AC 9260                                                  | 2         | 0.47%   |
| Intel WiFi Link 5100                                                    | 2         | 0.47%   |
| Intel Ultimate N WiFi Link 5300                                         | 2         | 0.47%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.47%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.47%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 2         | 0.47%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 2         | 0.47%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.47%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 238       | 65.93%  |
| Intel                            | 47        | 13.02%  |
| Qualcomm Atheros                 | 24        | 6.65%   |
| Broadcom                         | 14        | 3.88%   |
| Huawei Technologies              | 9         | 2.49%   |
| Marvell Technology Group         | 8         | 2.22%   |
| Silicon Integrated Systems [SiS] | 4         | 1.11%   |
| Xiaomi                           | 3         | 0.83%   |
| Samsung Electronics              | 3         | 0.83%   |
| JMicron Technology               | 3         | 0.83%   |
| Nvidia                           | 2         | 0.55%   |
| ICS Advent                       | 2         | 0.55%   |
| Microchip Technology             | 1         | 0.28%   |
| DisplayLink                      | 1         | 0.28%   |
| D-Link                           | 1         | 0.28%   |
| Broadcom Limited                 | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller    | 152       | 42.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                | 77        | 21.33%  |
| Intel Ethernet Connection I219-LM                                    | 8         | 2.22%   |
| Huawei JNY-LX1                                                       | 8         | 2.22%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                             | 7         | 1.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                | 7         | 1.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                           | 6         | 1.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                        | 5         | 1.39%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter        | 4         | 1.11%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                 | 4         | 1.11%   |
| Intel Ethernet Connection I217-LM                                    | 4         | 1.11%   |
| Intel Ethernet Connection (6) I219-V                                 | 4         | 1.11%   |
| Intel Ethernet Connection (4) I219-V                                 | 4         | 1.11%   |
| Intel 82567LM Gigabit Network Connection                             | 4         | 1.11%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller               | 3         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                                | 3         | 0.83%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                    | 3         | 0.83%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                      | 3         | 0.83%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                      | 3         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS)                                       | 2         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                        | 2         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                                | 2         | 0.55%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                               | 2         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                            | 2         | 0.55%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                | 2         | 0.55%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                           | 2         | 0.55%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                | 2         | 0.55%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller              | 2         | 0.55%   |
| Intel Ethernet Connection I218-LM                                    | 2         | 0.55%   |
| Intel 82577LM Gigabit Network Connection                             | 2         | 0.55%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                      | 2         | 0.55%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                 | 1         | 0.28%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)          | 1         | 0.28%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller            | 1         | 0.28%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                             | 1         | 0.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet       | 1         | 0.28%   |
| Nvidia MCP67 Ethernet                                                | 1         | 0.28%   |
| Nvidia MCP51 Ethernet Controller                                     | 1         | 0.28%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                        | 1         | 0.28%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller              | 1         | 0.28%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                 | 1         | 0.28%   |
| Intel Ethernet Connection I219-V                                     | 1         | 0.28%   |
| Intel Ethernet Connection I217-V                                     | 1         | 0.28%   |
| Intel Ethernet Connection (7) I219-V                                 | 1         | 0.28%   |
| Intel Ethernet Connection (5) I219-LM                                | 1         | 0.28%   |
| Intel Ethernet Connection (4) I219-LM                                | 1         | 0.28%   |
| Intel Ethernet Connection (10) I219-V                                | 1         | 0.28%   |
| Intel Ethernet Connection (10) I219-LM                               | 1         | 0.28%   |
| Intel 82566MM Gigabit Network Connection                             | 1         | 0.28%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile | 1         | 0.28%   |
| ICS Advent USB 10/100 LAN                                            | 1         | 0.28%   |
| ICS Advent DM9601 Fast Ethernet Adapter                              | 1         | 0.28%   |
| Huawei E353/E3131                                                    | 1         | 0.28%   |
| DisplayLink Dell Universal Dock D6000                                | 1         | 0.28%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.B1) [ASIX AX88772]         | 1         | 0.28%   |
| Broadcom NetXtreme BCM57761 Gigabit Ethernet PCIe                    | 1         | 0.28%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express             | 1         | 0.28%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                  | 1         | 0.28%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe            | 1         | 0.28%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 393       | 52.96%  |
| Ethernet | 347       | 46.77%  |
| Modem    | 2         | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 347       | 66.6%   |
| Ethernet | 174       | 33.4%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 318       | 80.1%   |
| 1     | 69        | 17.38%  |
| 3     | 5         | 1.26%   |
| 0     | 5         | 1.26%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 381       | 95.73%  |
| Yes  | 17        | 4.27%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 109       | 35.86%  |
| Realtek Semiconductor           | 56        | 18.42%  |
| Qualcomm Atheros Communications | 28        | 9.21%   |
| Broadcom                        | 24        | 7.89%   |
| Lite-On Technology              | 18        | 5.92%   |
| IMC Networks                    | 17        | 5.59%   |
| Foxconn / Hon Hai               | 10        | 3.29%   |
| Ralink                          | 7         | 2.3%    |
| Dell                            | 7         | 2.3%    |
| Apple                           | 7         | 2.3%    |
| Realtek                         | 4         | 1.32%   |
| Hewlett-Packard                 | 4         | 1.32%   |
| Toshiba                         | 3         | 0.99%   |
| Ralink Technology               | 3         | 0.99%   |
| Foxconn International           | 2         | 0.66%   |
| Cambridge Silicon Radio         | 2         | 0.66%   |
| ASUSTek Computer                | 2         | 0.66%   |
| Alps Electric                   | 1         | 0.33%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 53        | 17.43%  |
| Realtek Bluetooth Radio                             | 26        | 8.55%   |
| Realtek 802.11n WLAN Adapter                        | 13        | 4.28%   |
| Qualcomm Atheros  Bluetooth Device                  | 13        | 4.28%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 13        | 4.28%   |
| Intel AX201 Bluetooth                               | 13        | 4.28%   |
| Intel AX200 Bluetooth                               | 12        | 3.95%   |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 3.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 2.63%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 8         | 2.63%   |
| Ralink RT3290 Bluetooth                             | 7         | 2.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 2.3%    |
| Intel Bluetooth Device                              | 7         | 2.3%    |
| IMC Networks Bluetooth Radio                        | 6         | 1.97%   |
| IMC Networks Bluetooth Device                       | 6         | 1.97%   |
| Realtek RTL8821A Bluetooth                          | 5         | 1.64%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 1.64%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 5         | 1.64%   |
| Apple Bluetooth USB Host Controller                 | 5         | 1.64%   |
| Realtek Bluetooth Radio                             | 4         | 1.32%   |
| Lite-On Bluetooth Device                            | 4         | 1.32%   |
| Broadcom BCM2070 Bluetooth Device                   | 4         | 1.32%   |
| Toshiba Bluetooth Device                            | 3         | 0.99%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 3         | 0.99%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 3         | 0.99%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 0.99%   |
| Dell Wireless 365 Bluetooth                         | 3         | 0.99%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.99%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.66%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 2         | 0.66%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.66%   |
| IMC Networks Wireless_Device                        | 2         | 0.66%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.66%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 0.66%   |
| Foxconn International BCM43142A0 Bluetooth module   | 2         | 0.66%   |
| Foxconn / Hon Hai Bluetooth Device                  | 2         | 0.66%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.66%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 2         | 0.66%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.66%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.66%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.66%   |
| Apple Bluetooth Host Controller                     | 2         | 0.66%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.33%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.33%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.33%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.33%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.33%   |
| Foxconn / Hon Hai BT                                | 1         | 0.33%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device     | 1         | 0.33%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth       | 1         | 0.33%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth     | 1         | 0.33%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.33%   |
| Dell Wireless 360 Bluetooth                         | 1         | 0.33%   |
| Dell Wireless 355 Bluetooth                         | 1         | 0.33%   |
| Broadcom HP Portable Valentine                      | 1         | 0.33%   |
| Broadcom HP Portable SoftSailing                    | 1         | 0.33%   |
| Broadcom Bluetooth Controller                       | 1         | 0.33%   |
| Broadcom Bluetooth 3.0 USB Dongle                   | 1         | 0.33%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 302       | 67.11%  |
| AMD                              | 88        | 19.56%  |
| Nvidia                           | 36        | 8%      |
| C-Media Electronics              | 5         | 1.11%   |
| Silicon Integrated Systems [SiS] | 4         | 0.89%   |
| Logitech                         | 3         | 0.67%   |
| Generalplus Technology           | 2         | 0.44%   |
| Shenzhen Riitek Technology       | 1         | 0.22%   |
| Pixart Imaging                   | 1         | 0.22%   |
| Microsoft                        | 1         | 0.22%   |
| Lenovo                           | 1         | 0.22%   |
| Kingston Technology              | 1         | 0.22%   |
| Focusrite-Novation               | 1         | 0.22%   |
| ESS Technology                   | 1         | 0.22%   |
| DigiTech                         | 1         | 0.22%   |
| Creative Technology              | 1         | 0.22%   |
| Apple                            | 1         | 0.22%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 65        | 11.63%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 36        | 6.44%   |
| AMD FCH Azalia Controller                                                                         | 30        | 5.37%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 29        | 5.19%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 4.47%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 21        | 3.76%   |
| AMD Kabini HDMI/DP Audio                                                                          | 21        | 3.76%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 18        | 3.22%   |
| Intel 8 Series HD Audio Controller                                                                | 18        | 3.22%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 14        | 2.5%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 13        | 2.33%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 12        | 2.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 11        | 1.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 1.97%   |
| Intel Broadwell-U Audio Controller                                                                | 11        | 1.97%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 11        | 1.97%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 11        | 1.97%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 1.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 1.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 9         | 1.61%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 9         | 1.61%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 9         | 1.61%   |
| AMD Wrestler HDMI Audio                                                                           | 9         | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 8         | 1.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.07%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.07%   |
| AMD Trinity HDMI Audio Controller                                                                 | 6         | 1.07%   |
| Intel Comet Lake PCH cAVS                                                                         | 5         | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 0.89%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 0.89%   |
| AMD High Definition Audio Controller                                                              | 5         | 0.89%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 4         | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.72%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.54%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.54%   |
| C-Media Electronics CM108 Audio Controller                                                        | 3         | 0.54%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.36%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.36%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.36%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.36%   |
| Logitech USB Headset                                                                              | 2         | 0.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 0.36%   |
| Generalplus Technology Usb Audio Device                                                           | 2         | 0.36%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.36%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.36%   |
| Shenzhen Riitek Technology Multimedia Air Mouse Keyboard                                          | 1         | 0.18%   |
| Pixart Imaging Multimedia audio controller                                                        | 1         | 0.18%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.18%   |
| Nvidia TU104 HD Audio Controller                                                                  | 1         | 0.18%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.18%   |
| Nvidia MCP51 High Definition Audio                                                                | 1         | 0.18%   |
| Nvidia GM206 High Definition Audio Controller                                                     | 1         | 0.18%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.18%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.18%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 1         | 0.18%   |
| Nvidia Audio device                                                                               | 1         | 0.18%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 82        | 33.88%  |
| SK Hynix            | 47        | 19.42%  |
| Micron Technology   | 34        | 14.05%  |
| Crucial             | 22        | 9.09%   |
| Kingston            | 20        | 8.26%   |
| Ramaxel Technology  | 10        | 4.13%   |
| Unknown             | 9         | 3.72%   |
| A-DATA Technology   | 3         | 1.24%   |
| Nanya Technology    | 2         | 0.83%   |
| G.Skill             | 2         | 0.83%   |
| Corsair             | 2         | 0.83%   |
| Unknown (ABCD)      | 1         | 0.41%   |
| Unknown (090E)      | 1         | 0.41%   |
| Unknown (08C8)      | 1         | 0.41%   |
| Smart               | 1         | 0.41%   |
| PNY                 | 1         | 0.41%   |
| Kllisre             | 1         | 0.41%   |
| Elpida              | 1         | 0.41%   |
| ASint Technology    | 1         | 0.41%   |
| Unknown             | 1         | 0.41%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 8         | 3.14%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 5         | 1.96%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 5         | 1.96%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 4         | 1.57%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 4         | 1.57%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 4         | 1.57%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 4         | 1.57%   |
| Micron RAM 8KTF51264HZ-1G6N1 4096MB SODIMM DDR3 1600MT/s            | 4         | 1.57%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 1.18%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 3         | 1.18%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s               | 3         | 1.18%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 3         | 1.18%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 1.18%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s            | 3         | 1.18%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 3         | 1.18%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s        | 3         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 3         | 1.18%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 2         | 0.78%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.78%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 2         | 0.78%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s              | 2         | 0.78%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 2         | 0.78%   |
| SK Hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 0.78%   |
| SK Hynix RAM H9CCNNNBJTALAR-NVD 4GB Row Of Chips LPDDR3 2133MT/s    | 2         | 0.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 0.78%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 0.78%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 2         | 0.78%   |
| Samsung RAM 16HTF25664HY-667E1 4096MB SODIMM DDR2 800MT/s           | 2         | 0.78%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s               | 2         | 0.78%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s             | 2         | 0.78%   |
| Kingston RAM 9905428-417.A00LF 8GB SODIMM DDR3 1600MT/s             | 2         | 0.78%   |
| Crucial RAM CT8G4SFRA32A.M8FRS 8192MB SODIMM DDR4 3200MT/s          | 2         | 0.78%   |
| Crucial RAM CT51264AC800.C16FC 4GB SODIMM DDR2 800MT/s              | 2         | 0.78%   |
| Unknown RAM Module 8GB SODIMM LPDDR4 4266MT/s                       | 1         | 0.39%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1333MT/s                      | 1         | 0.39%   |
| Unknown RAM Module 8192MB SODIMM DDR3                               | 1         | 0.39%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s              | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR3 667MT/s                          | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 1         | 0.39%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                          | 1         | 0.39%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                          | 1         | 0.39%   |
| Unknown RAM Module 16384MB SODIMM DDR4 2400MT/s                     | 1         | 0.39%   |
| Unknown RAM DDR4 NB 8G 2400 8192MB SODIMM DDR4 2667MT/s             | 1         | 0.39%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 0.39%   |
| Unknown (090E) RAM ARM Ltd:R0M1333M 8192MB SODIMM DDR3 1333MT/s     | 1         | 0.39%   |
| Unknown (090E) RAM ARM Ltd:R00M1333 8192MB SODIMM DDR3 1333MT/s     | 1         | 0.39%   |
| Unknown (08C8) RAM Module 16GB SODIMM DDR4 2667MT/s                 | 1         | 0.39%   |
| Smart RAM SH564568FH8NWPHSFR 2GB SODIMM DDR3 1334MT/s               | 1         | 0.39%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 3200MT/s                        | 1         | 0.39%   |
| SK Hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                | 1         | 0.39%   |
| SK Hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                     | 1         | 0.39%   |
| SK Hynix RAM Module 4096MB SODIMM DDR4 2400MT/s                     | 1         | 0.39%   |
| SK Hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.39%   |
| SK Hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.39%   |
| SK Hynix RAM HMT451S6AFR6A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.39%   |
| SK Hynix RAM HMT41GS6DFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.39%   |
| SK Hynix RAM HMT41GS6DFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 0.39%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.39%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.39%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 1         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 81        | 44.02%  |
| DDR3   | 72        | 39.13%  |
| LPDDR4 | 9         | 4.89%   |
| LPDDR3 | 9         | 4.89%   |
| DDR2   | 8         | 4.35%   |
| SDRAM  | 5         | 2.72%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 164       | 91.62%  |
| Row Of Chips | 14        | 7.82%   |
| Unknown      | 1         | 0.56%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 93        | 44.93%  |
| 8192  | 72        | 34.78%  |
| 2048  | 22        | 10.63%  |
| 16384 | 16        | 7.73%   |
| 1024  | 3         | 1.45%   |
| 64    | 1         | 0.48%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 57        | 26.76%  |
| 2667    | 48        | 22.54%  |
| 2400    | 23        | 10.8%   |
| 3200    | 20        | 9.39%   |
| 2133    | 16        | 7.51%   |
| 1334    | 9         | 4.23%   |
| 3266    | 8         | 3.76%   |
| 1333    | 7         | 3.29%   |
| 667     | 5         | 2.35%   |
| 4199    | 3         | 1.41%   |
| 800     | 3         | 1.41%   |
| 4267    | 2         | 0.94%   |
| 4266    | 2         | 0.94%   |
| 2048    | 2         | 0.94%   |
| 1867    | 2         | 0.94%   |
| 1067    | 2         | 0.94%   |
| 975     | 1         | 0.47%   |
| 933     | 1         | 0.47%   |
| 533     | 1         | 0.47%   |
| Unknown | 1         | 0.47%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Brother Industries | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                  | Notebooks | Percent |
|------------------------|-----------|---------|
| Brother HL-1200 series | 1         | 50%     |
| Brother DCP-1600       | 1         | 50%     |

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
| Chicony Electronics                    | 92        | 24.93%  |
| IMC Networks                           | 39        | 10.57%  |
| Realtek Semiconductor                  | 33        | 8.94%   |
| Microdia                               | 28        | 7.59%   |
| Sunplus Innovation Technology          | 23        | 6.23%   |
| Cheng Uei Precision Industry (Foxlink) | 23        | 6.23%   |
| Acer                                   | 20        | 5.42%   |
| Suyin                                  | 16        | 4.34%   |
| Lite-On Technology                     | 16        | 4.34%   |
| Silicon Motion                         | 14        | 3.79%   |
| Quanta                                 | 12        | 3.25%   |
| Syntek                                 | 6         | 1.63%   |
| Apple                                  | 5         | 1.36%   |
| Ricoh                                  | 4         | 1.08%   |
| Z-Star Microelectronics                | 3         | 0.81%   |
| Importek                               | 3         | 0.81%   |
| Sonix Technology                       | 2         | 0.54%   |
| Samsung Electronics                    | 2         | 0.54%   |
| Logitech                               | 2         | 0.54%   |
| Lenovo                                 | 2         | 0.54%   |
| Leap Motion                            | 2         | 0.54%   |
| KYE Systems (Mouse Systems)            | 2         | 0.54%   |
| Foxconn / Hon Hai                      | 2         | 0.54%   |
| DigiTech                               | 2         | 0.54%   |
| ALi                                    | 2         | 0.54%   |
| Alcor Micro                            | 2         | 0.54%   |
| 8SSC20F27114V1GZ07N14V2                | 2         | 0.54%   |
| Sunplus Technology                     | 1         | 0.27%   |
| SHENZHEN EMEET TECHNOLOGY              | 1         | 0.27%   |
| Ruision                                | 1         | 0.27%   |
| OmniVision Technologies                | 1         | 0.27%   |
| Microsoft                              | 1         | 0.27%   |
| Luxvisions Innotech Limited            | 1         | 0.27%   |
| Intel                                  | 1         | 0.27%   |
| Huawei Technologies                    | 1         | 0.27%   |
| GEMBIRD                                | 1         | 0.27%   |
| ARC International                      | 1         | 0.27%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                               | 14        | 3.77%   |
| Chicony Integrated Camera                                       | 10        | 2.7%    |
| IMC Networks Integrated Camera                                  | 8         | 2.16%   |
| Chicony HD WebCam                                               | 8         | 2.16%   |
| Realtek Integrated_Webcam_HD                                    | 7         | 1.89%   |
| Realtek HP Truevision HD                                        | 7         | 1.89%   |
| Chicony HP Webcam                                               | 6         | 1.62%   |
| Suyin HP Truevision HD                                          | 5         | 1.35%   |
| Sunplus HP TrueVision HD Camera                                 | 5         | 1.35%   |
| Microdia HP Webcam                                              | 5         | 1.35%   |
| Lite-On Integrated Camera                                       | 5         | 1.35%   |
| Chicony USB2.0 VGA UVC WebCam                                   | 5         | 1.35%   |
| Chicony HP Truevision HD                                        | 5         | 1.35%   |
| Chicony EasyCamera                                              | 5         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD         | 5         | 1.35%   |
| Acer Integrated Camera                                          | 5         | 1.35%   |
| Sunplus Laptop Integrated WebCam HD                             | 4         | 1.08%   |
| Realtek HP "Truevision HD" laptop camera                        | 4         | 1.08%   |
| Lite-On HP Wide Vision HD Camera                                | 4         | 1.08%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 4         | 1.08%   |
| Chicony VGA Webcam                                              | 4         | 1.08%   |
| Chicony HP Wide Vision HD Camera                                | 4         | 1.08%   |
| Chicony HP Truevision HD camera                                 | 4         | 1.08%   |
| Chicony HP HD Camera                                            | 4         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                   | 4         | 1.08%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                | 4         | 1.08%   |
| Acer EasyCamera                                                 | 4         | 1.08%   |
| Syntek Integrated Camera                                        | 3         | 0.81%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                        | 3         | 0.81%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)     | 3         | 0.81%   |
| Sunplus HD Webcam                                               | 3         | 0.81%   |
| Silicon Motion WebCam SCB-1100N                                 | 3         | 0.81%   |
| Realtek USB Camera                                              | 3         | 0.81%   |
| Quanta HD User Facing                                           | 3         | 0.81%   |
| Microdia Webcam SC-10HDD12636P                                  | 3         | 0.81%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 3         | 0.81%   |
| Microdia Integrated_Webcam_HD                                   | 3         | 0.81%   |
| Lite-On HP HD Camera                                            | 3         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 3         | 0.81%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 3         | 0.81%   |
| Apple FaceTime HD Camera                                        | 3         | 0.81%   |
| Syntek EasyCamera                                               | 2         | 0.54%   |
| Suyin Integrated_Webcam_HD                                      | 2         | 0.54%   |
| Suyin HD WebCam                                                 | 2         | 0.54%   |
| Sunplus Laptop_Integrated_Webcam_HD                             | 2         | 0.54%   |
| Sunplus Integrated_Webcam_HD                                    | 2         | 0.54%   |
| Sunplus Dell HD Webcam                                          | 2         | 0.54%   |
| Sonix USB2.0 HD UVC WebCam                                      | 2         | 0.54%   |
| Silicon Motion WebCam SC-13HDL11939N                            | 2         | 0.54%   |
| Samsung Galaxy A5 (MTP)                                         | 2         | 0.54%   |
| Realtek USB2.0 HD UVC WebCam                                    | 2         | 0.54%   |
| Realtek Integrated Webcam HD                                    | 2         | 0.54%   |
| Realtek Integrated Webcam                                       | 2         | 0.54%   |
| Realtek HD WebCam                                               | 2         | 0.54%   |
| Quanta VGA WebCam                                               | 2         | 0.54%   |
| Quanta HP Webcam                                                | 2         | 0.54%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 0.54%   |
| Quanta HP HD Camera                                             | 2         | 0.54%   |
| Microdia Lenovo EasyCamera                                      | 2         | 0.54%   |
| Microdia Laptop_Integrated_Webcam_2M                            | 2         | 0.54%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 24        | 44.44%  |
| Synaptics                  | 15        | 27.78%  |
| AuthenTec                  | 4         | 7.41%   |
| Upek                       | 3         | 5.56%   |
| Shenzhen Goodix Technology | 3         | 5.56%   |
| LighTuning Technology      | 2         | 3.7%    |
| STMicroelectronics         | 1         | 1.85%   |
| Focal-systems.Corp         | 1         | 1.85%   |
| Elan Microelectronics      | 1         | 1.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 12.96%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 9.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 9.26%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 7.41%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 5.56%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 5.56%   |
| Synaptics  WBDI                                                            | 3         | 5.56%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 3         | 5.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 5.56%   |
| AuthenTec AES2810                                                          | 3         | 5.56%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 3.7%    |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 3.7%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.7%    |
| Validity Sensors VFS491                                                    | 1         | 1.85%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 1.85%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 1.85%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.85%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.85%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 1.85%   |
| Elan ELAN:Fingerprint                                                      | 1         | 1.85%   |
| AuthenTec AES1600                                                          | 1         | 1.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor   | Notebooks | Percent |
|----------|-----------|---------|
| Broadcom | 13        | 92.86%  |
| O2 Micro | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 5         | 35.71%  |
| Broadcom 5880                                                                | 4         | 28.57%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 21.43%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.14%   |
| Broadcom 58200                                                               | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 273       | 68.08%  |
| 1     | 105       | 26.18%  |
| 2     | 22        | 5.49%   |
| 5     | 1         | 0.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 54        | 36.49%  |
| Graphics card            | 28        | 18.92%  |
| Net/wireless             | 22        | 14.86%  |
| Chipcard                 | 13        | 8.78%   |
| Bluetooth                | 10        | 6.76%   |
| Multimedia controller    | 8         | 5.41%   |
| Storage                  | 4         | 2.7%    |
| Communication controller | 3         | 2.03%   |
| Net/ethernet             | 2         | 1.35%   |
| Card reader              | 2         | 1.35%   |
| Sound                    | 1         | 0.68%   |
| Camera                   | 1         | 0.68%   |

