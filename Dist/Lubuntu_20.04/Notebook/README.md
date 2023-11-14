Lubuntu 20.04 - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------

A project to collect tested hardware configurations for Lubuntu 20.04.

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

Total: 384

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire 9300                 | [3094b549c5](https://linux-hardware.org/?probe=3094b549c5) | Oct 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | [358936d398](https://linux-hardware.org/?probe=358936d398) | Oct 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [81411c1db8](https://linux-hardware.org/?probe=81411c1db8) | Aug 08, 2023 |
| Lenovo        | ThinkPad T430 2349G7G       | [b0eefed750](https://linux-hardware.org/?probe=b0eefed750) | Jul 03, 2023 |
| HP            | Laptop 15-da0xxx            | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| Toshiba       | Satellite P200              | [19350653f7](https://linux-hardware.org/?probe=19350653f7) | Jun 23, 2023 |
| Sony          | SVF1521C6EW                 | [57e1c14061](https://linux-hardware.org/?probe=57e1c14061) | Apr 30, 2023 |
| HP            | Laptop 15-da0xxx            | [c64154e569](https://linux-hardware.org/?probe=c64154e569) | Apr 17, 2023 |
| HP            | Pavilion dv6                | [d938ba339d](https://linux-hardware.org/?probe=d938ba339d) | Apr 14, 2023 |
| Acer          | Aspire E1-570               | [ad70ba8e9d](https://linux-hardware.org/?probe=ad70ba8e9d) | Apr 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [2d5d0e42c5](https://linux-hardware.org/?probe=2d5d0e42c5) | Mar 15, 2023 |
| MSI           | GS65 Stealth 9SD            | [1eef9edf97](https://linux-hardware.org/?probe=1eef9edf97) | Mar 04, 2023 |
| DEXP          | Aquilon C15                 | [9ae006e12a](https://linux-hardware.org/?probe=9ae006e12a) | Mar 03, 2023 |
| Lenovo        | ThinkPad X201 3626AL3       | [9c3a1f5cd5](https://linux-hardware.org/?probe=9c3a1f5cd5) | Feb 26, 2023 |
| Unknown       | Unknown                     | [1dfaaf5a59](https://linux-hardware.org/?probe=1dfaaf5a59) | Feb 25, 2023 |
| Lenovo        | ThinkPad X240 20AMS0RR00    | [d159971f77](https://linux-hardware.org/?probe=d159971f77) | Feb 18, 2023 |
| Toshiba       | Satellite C55D-A            | [38083cc2a4](https://linux-hardware.org/?probe=38083cc2a4) | Feb 05, 2023 |
| AXDIA Inte... | WINPAD V10                  | [be66e9073f](https://linux-hardware.org/?probe=be66e9073f) | Jan 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | [3a8aced1b7](https://linux-hardware.org/?probe=3a8aced1b7) | Jan 25, 2023 |
| Acer          | Aspire One 721              | [4b9311cfed](https://linux-hardware.org/?probe=4b9311cfed) | Jan 08, 2023 |
| HP            | Laptop 15-da0xxx            | [96a4f739b8](https://linux-hardware.org/?probe=96a4f739b8) | Dec 26, 2022 |
| HP            | Laptop 15-da0xxx            | [19af161114](https://linux-hardware.org/?probe=19af161114) | Dec 26, 2022 |
| HP            | Compaq 6715b (RM174UT#AB... | [db3b8615f7](https://linux-hardware.org/?probe=db3b8615f7) | Dec 21, 2022 |
| Lenovo        | ThinkPad R61 77324TG        | [90c300a51c](https://linux-hardware.org/?probe=90c300a51c) | Dec 18, 2022 |
| HP            | Compaq 6830s                | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Lenovo        | V145-15AST 81MT             | [b37755877d](https://linux-hardware.org/?probe=b37755877d) | Nov 24, 2022 |
| Acer          | AOD255E                     | [817724283b](https://linux-hardware.org/?probe=817724283b) | Nov 11, 2022 |
| Toshiba       | Satellite L15-B             | [b7a5fabbbd](https://linux-hardware.org/?probe=b7a5fabbbd) | Nov 08, 2022 |
| HP            | EliteBook 850 G5            | [3408fb4c36](https://linux-hardware.org/?probe=3408fb4c36) | Nov 07, 2022 |
| Dell          | Inspiron N5010              | [a5712d3982](https://linux-hardware.org/?probe=a5712d3982) | Oct 31, 2022 |
| Dell          | Inspiron N5010              | [9b53e5c27d](https://linux-hardware.org/?probe=9b53e5c27d) | Oct 31, 2022 |
| Teclast       | F7 Plus                     | [f416278476](https://linux-hardware.org/?probe=f416278476) | Oct 29, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [084149046b](https://linux-hardware.org/?probe=084149046b) | Oct 25, 2022 |
| Fujitsu Si... | AMILO Li 2727               | [c9811709ec](https://linux-hardware.org/?probe=c9811709ec) | Oct 25, 2022 |
| HP            | 431 Notebook                | [fd2980af46](https://linux-hardware.org/?probe=fd2980af46) | Oct 16, 2022 |
| Acer          | Aspire 4739Z                | [b85222f02c](https://linux-hardware.org/?probe=b85222f02c) | Oct 09, 2022 |
| ASUSTek       | X451CA                      | [bdfe92eb66](https://linux-hardware.org/?probe=bdfe92eb66) | Sep 21, 2022 |
| ASUSTek       | 1201N                       | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| Star Labs     | Lite                        | [c08b209f09](https://linux-hardware.org/?probe=c08b209f09) | Sep 09, 2022 |
| HP            | ProBook 450 G6              | [7763040d56](https://linux-hardware.org/?probe=7763040d56) | Aug 30, 2022 |
| HP            | 240 G8 Notebook PC          | [f4533284b4](https://linux-hardware.org/?probe=f4533284b4) | Aug 01, 2022 |
| Google        | Celes                       | [fae813e4dc](https://linux-hardware.org/?probe=fae813e4dc) | Jul 31, 2022 |
| HP            | Presario CQ56               | [aead18fee1](https://linux-hardware.org/?probe=aead18fee1) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [894bf232f8](https://linux-hardware.org/?probe=894bf232f8) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [eb752c319e](https://linux-hardware.org/?probe=eb752c319e) | Jul 28, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [3451f0e8b5](https://linux-hardware.org/?probe=3451f0e8b5) | Jul 26, 2022 |
| HP            | Laptop 17-cn0xxx            | [55d8e5a779](https://linux-hardware.org/?probe=55d8e5a779) | Jul 24, 2022 |
| Dell          | Inspiron N5010              | [826672a49e](https://linux-hardware.org/?probe=826672a49e) | Jul 22, 2022 |
| HP            | G62                         | [2411be6ba6](https://linux-hardware.org/?probe=2411be6ba6) | Jun 04, 2022 |
| Packard Be... | EasyNote TE11HC             | [8350bd6d87](https://linux-hardware.org/?probe=8350bd6d87) | May 30, 2022 |
| HP            | Berknip                     | [c81d3442c2](https://linux-hardware.org/?probe=c81d3442c2) | May 27, 2022 |
| ASUSTek       | X205TA                      | [9fa4c6beef](https://linux-hardware.org/?probe=9fa4c6beef) | May 26, 2022 |
| ASUSTek       | X402CA                      | [eb6132725e](https://linux-hardware.org/?probe=eb6132725e) | May 21, 2022 |
| ASUSTek       | K55VD                       | [8ff47b2a2c](https://linux-hardware.org/?probe=8ff47b2a2c) | May 05, 2022 |
| Toshiba       | Satellite C670D-12N         | [f6bd692d1f](https://linux-hardware.org/?probe=f6bd692d1f) | May 05, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | [5a36e4d0fc](https://linux-hardware.org/?probe=5a36e4d0fc) | May 04, 2022 |
| Samsung       | RV415/RV515                 | [bc88bd7582](https://linux-hardware.org/?probe=bc88bd7582) | May 04, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [39475a20ff](https://linux-hardware.org/?probe=39475a20ff) | May 01, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [1ec609b350](https://linux-hardware.org/?probe=1ec609b350) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | [c206790d1e](https://linux-hardware.org/?probe=c206790d1e) | May 01, 2022 |
| HP            | EliteBook 8570p             | [2dffdad8a4](https://linux-hardware.org/?probe=2dffdad8a4) | May 01, 2022 |
| YASHI         | MYBOOK 360                  | [d44c4fd567](https://linux-hardware.org/?probe=d44c4fd567) | Apr 29, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [753e3fda7d](https://linux-hardware.org/?probe=753e3fda7d) | Apr 26, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [c8f16c0d16](https://linux-hardware.org/?probe=c8f16c0d16) | Apr 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ff77bbf8ae](https://linux-hardware.org/?probe=ff77bbf8ae) | Apr 22, 2022 |
| HP            | Laptop 14s-dk0xxx           | [ec7bef597a](https://linux-hardware.org/?probe=ec7bef597a) | Apr 20, 2022 |
| HP            | Laptop 14s-dk0xxx           | [1edc356b52](https://linux-hardware.org/?probe=1edc356b52) | Apr 20, 2022 |
| Dell          | Inspiron 3180               | [9d280b4678](https://linux-hardware.org/?probe=9d280b4678) | Apr 14, 2022 |
| Dell          | Latitude E7240              | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Dell          | Inspiron N4010              | [0aac536dbf](https://linux-hardware.org/?probe=0aac536dbf) | Apr 04, 2022 |
| Samsung       | N100SP                      | [6a70399256](https://linux-hardware.org/?probe=6a70399256) | Mar 31, 2022 |
| Intel         | W7650                       | [67d43b2ee4](https://linux-hardware.org/?probe=67d43b2ee4) | Mar 28, 2022 |
| Haier         | U1520EM                     | [5fde1c39e9](https://linux-hardware.org/?probe=5fde1c39e9) | Mar 25, 2022 |
| HP            | Pavilion g7                 | [2c480cdfac](https://linux-hardware.org/?probe=2c480cdfac) | Mar 22, 2022 |
| HP            | EliteBook 745 G6            | [a3f94c2957](https://linux-hardware.org/?probe=a3f94c2957) | Mar 20, 2022 |
| Google        | Celes                       | [cfcec68610](https://linux-hardware.org/?probe=cfcec68610) | Mar 15, 2022 |
| Dell          | Latitude D630               | [707be96775](https://linux-hardware.org/?probe=707be96775) | Mar 13, 2022 |
| Lenovo        | G50-30 80G0                 | [efc41b55f4](https://linux-hardware.org/?probe=efc41b55f4) | Mar 06, 2022 |
| Dell          | Inspiron 1090               | [31efa1bb6f](https://linux-hardware.org/?probe=31efa1bb6f) | Mar 03, 2022 |
| Dell          | Inspiron 1090               | [6a97a96f56](https://linux-hardware.org/?probe=6a97a96f56) | Mar 01, 2022 |
| Dell          | Inspiron 1090               | [9d63b9e47f](https://linux-hardware.org/?probe=9d63b9e47f) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [9a59eff157](https://linux-hardware.org/?probe=9a59eff157) | Feb 26, 2022 |
| Toshiba       | Satellite S55-B             | [f07aaa2fd3](https://linux-hardware.org/?probe=f07aaa2fd3) | Feb 25, 2022 |
| Toshiba       | Satellite S55-B             | [8551d043a9](https://linux-hardware.org/?probe=8551d043a9) | Feb 20, 2022 |
| Alienware     | M17                         | [9d29db918d](https://linux-hardware.org/?probe=9d29db918d) | Feb 18, 2022 |
| Positivo      | N600                        | [0181f9186d](https://linux-hardware.org/?probe=0181f9186d) | Feb 08, 2022 |
| Dell          | Inspiron 11-3168            | [c4ed40f38f](https://linux-hardware.org/?probe=c4ed40f38f) | Feb 07, 2022 |
| Dell          | Latitude E5540              | [e895dcce0f](https://linux-hardware.org/?probe=e895dcce0f) | Feb 07, 2022 |
| Dell          | Inspiron 11-3168            | [2178360bbd](https://linux-hardware.org/?probe=2178360bbd) | Feb 07, 2022 |
| HP            | 255 G6 Notebook PC          | [9c5efed237](https://linux-hardware.org/?probe=9c5efed237) | Feb 06, 2022 |
| Toshiba       | Satellite C875              | [1dd31ebdd6](https://linux-hardware.org/?probe=1dd31ebdd6) | Feb 02, 2022 |
| Lenovo        | ThinkPad T460 20FMS2J000    | [f75f8240a4](https://linux-hardware.org/?probe=f75f8240a4) | Jan 31, 2022 |
| Prestigio     | PSB141C01BFH                | [5adcd620f6](https://linux-hardware.org/?probe=5adcd620f6) | Jan 30, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [433e46caa5](https://linux-hardware.org/?probe=433e46caa5) | Jan 19, 2022 |
| Dell          | Inspiron 15-3573            | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Positivo      | N600                        | [2088081d6e](https://linux-hardware.org/?probe=2088081d6e) | Jan 10, 2022 |
| UNOWHY        | Y13G010S4EI                 | [66d00e2cd5](https://linux-hardware.org/?probe=66d00e2cd5) | Jan 05, 2022 |
| UNOWHY        | Y13G010S4EI                 | [7cf1327087](https://linux-hardware.org/?probe=7cf1327087) | Jan 05, 2022 |
| Acer          | Aspire 7715Z                | [4f79a85c6b](https://linux-hardware.org/?probe=4f79a85c6b) | Jan 03, 2022 |
| Lanix         | NeuronALV5                  | [11aa45646b](https://linux-hardware.org/?probe=11aa45646b) | Jan 01, 2022 |
| Sony          | VPCEJ1E1E                   | [0211323709](https://linux-hardware.org/?probe=0211323709) | Dec 28, 2021 |
| Sony          | VPCEJ1E1E                   | [d8d2b553bf](https://linux-hardware.org/?probe=d8d2b553bf) | Dec 24, 2021 |
| I-Life Dig... | ZED AIR                     | [4ff26a058b](https://linux-hardware.org/?probe=4ff26a058b) | Dec 22, 2021 |
| Acer          | Aspire E1-572G              | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| Samsung       | 275E4E/275E5E               | [3d01509464](https://linux-hardware.org/?probe=3d01509464) | Dec 15, 2021 |
| MSI           | Katana GF76 11UC            | [73fd53a50c](https://linux-hardware.org/?probe=73fd53a50c) | Dec 08, 2021 |
| Hungaro Fl... | Navon Loop 360              | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| HP            | ProBook 440 G7              | [155ec30920](https://linux-hardware.org/?probe=155ec30920) | Dec 03, 2021 |
| I-Life Dig... | ZED AIR                     | [a6e2e61f26](https://linux-hardware.org/?probe=a6e2e61f26) | Nov 24, 2021 |
| Toshiba       | Satellite L40               | [43d9bb451a](https://linux-hardware.org/?probe=43d9bb451a) | Nov 23, 2021 |
| Dell          | Latitude 3330               | [2c8f88588b](https://linux-hardware.org/?probe=2c8f88588b) | Nov 23, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | [867419b410](https://linux-hardware.org/?probe=867419b410) | Nov 21, 2021 |
| HP            | Pavilion dv6                | [591f986631](https://linux-hardware.org/?probe=591f986631) | Nov 14, 2021 |
| ASUSTek       | 1015BX                      | [51933ea3ac](https://linux-hardware.org/?probe=51933ea3ac) | Nov 14, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [0e17c0b84d](https://linux-hardware.org/?probe=0e17c0b84d) | Nov 13, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [4e3e71f6ab](https://linux-hardware.org/?probe=4e3e71f6ab) | Nov 07, 2021 |
| Samsung       | R40/R41                     | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| HP            | Pavilion dv6                | [e84cd86eb0](https://linux-hardware.org/?probe=e84cd86eb0) | Oct 31, 2021 |
| HP            | ProBook 4540s               | [e565d7befe](https://linux-hardware.org/?probe=e565d7befe) | Oct 31, 2021 |
| HP            | Presario CQ58               | [60d72bdce7](https://linux-hardware.org/?probe=60d72bdce7) | Oct 28, 2021 |
| HP            | Presario CQ58               | [8989debda6](https://linux-hardware.org/?probe=8989debda6) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [e1e44b58f3](https://linux-hardware.org/?probe=e1e44b58f3) | Oct 27, 2021 |
| Lenovo        | ThinkPad L440 20ASS0QS00    | [42d3788463](https://linux-hardware.org/?probe=42d3788463) | Oct 27, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1663dc4946](https://linux-hardware.org/?probe=1663dc4946) | Oct 26, 2021 |
| Dell          | Inspiron 3583               | [8f25043c64](https://linux-hardware.org/?probe=8f25043c64) | Oct 24, 2021 |
| Sony          | VGN-CR11Z_R                 | [538c03b235](https://linux-hardware.org/?probe=538c03b235) | Oct 23, 2021 |
| Sony          | VGN-CR11Z_R                 | [57043d09fe](https://linux-hardware.org/?probe=57043d09fe) | Oct 22, 2021 |
| Intel         | W7650                       | [6fb87337c0](https://linux-hardware.org/?probe=6fb87337c0) | Oct 19, 2021 |
| MSI           | Modern 15 A10M              | [184c512c35](https://linux-hardware.org/?probe=184c512c35) | Oct 18, 2021 |
| Lenovo        | ThinkPad X61 76744NG        | [ee90608b54](https://linux-hardware.org/?probe=ee90608b54) | Oct 15, 2021 |
| HP            | Pavilion x2 Detachable      | [e5702172f9](https://linux-hardware.org/?probe=e5702172f9) | Oct 11, 2021 |
| HP            | Notebook                    | [d332712e6f](https://linux-hardware.org/?probe=d332712e6f) | Oct 08, 2021 |
| HP            | Pavilion x2 Detachable      | [f81838645f](https://linux-hardware.org/?probe=f81838645f) | Oct 07, 2021 |
| HP            | Notebook                    | [04313f623e](https://linux-hardware.org/?probe=04313f623e) | Oct 07, 2021 |
| HP            | Notebook                    | [282f030bc4](https://linux-hardware.org/?probe=282f030bc4) | Oct 07, 2021 |
| Dell          | Inspiron 15-3567            | [414e52d7a4](https://linux-hardware.org/?probe=414e52d7a4) | Oct 06, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [61b646614a](https://linux-hardware.org/?probe=61b646614a) | Sep 30, 2021 |
| HP            | EliteBook 8440p (SH923UC... | [21ddcdea76](https://linux-hardware.org/?probe=21ddcdea76) | Sep 27, 2021 |
| Lenovo        | G50-80 80L0                 | [b818d8d0f6](https://linux-hardware.org/?probe=b818d8d0f6) | Sep 17, 2021 |
| Apple         | MacBookPro8,1               | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| Lenovo        | G50-80 80L0                 | [46e1004405](https://linux-hardware.org/?probe=46e1004405) | Sep 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [727f3718a1](https://linux-hardware.org/?probe=727f3718a1) | Sep 08, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [d819b1cc24](https://linux-hardware.org/?probe=d819b1cc24) | Sep 04, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [b5388437b9](https://linux-hardware.org/?probe=b5388437b9) | Sep 04, 2021 |
| Notebook      | NL40_50GU                   | [977812d04b](https://linux-hardware.org/?probe=977812d04b) | Aug 29, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [92d57d3ea8](https://linux-hardware.org/?probe=92d57d3ea8) | Aug 15, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [3edbab6d15](https://linux-hardware.org/?probe=3edbab6d15) | Aug 15, 2021 |
| Lenovo        | ThinkPad W500 406138U       | [a72c7ecd8a](https://linux-hardware.org/?probe=a72c7ecd8a) | Aug 14, 2021 |
| Dell          | Inspiron 3583               | [17b5565505](https://linux-hardware.org/?probe=17b5565505) | Aug 08, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [9b893159ef](https://linux-hardware.org/?probe=9b893159ef) | Aug 06, 2021 |
| Mediacom      | SmartBook 14 FullHD - SB... | [0719538c6e](https://linux-hardware.org/?probe=0719538c6e) | Aug 02, 2021 |
| Dell          | Latitude E5450              | [203e92fef9](https://linux-hardware.org/?probe=203e92fef9) | Jul 30, 2021 |
| HP            | ProBook 6450b               | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| Dell          | Inspiron M5040              | [c38c747e1b](https://linux-hardware.org/?probe=c38c747e1b) | Jul 23, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [d4852f4d01](https://linux-hardware.org/?probe=d4852f4d01) | Jul 14, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| Apple         | MacBook4,1                  | [17dcc66fd5](https://linux-hardware.org/?probe=17dcc66fd5) | Jul 02, 2021 |
| Samsung       | RV415/RV515                 | [581180a4d8](https://linux-hardware.org/?probe=581180a4d8) | Jun 30, 2021 |
| Samsung       | RV415/RV515                 | [99a0739814](https://linux-hardware.org/?probe=99a0739814) | Jun 28, 2021 |
| HP            | EliteBook 840 G6            | [cfd34d8c5b](https://linux-hardware.org/?probe=cfd34d8c5b) | Jun 22, 2021 |
| Notebook      | NHxxRZQ                     | [221e4d197b](https://linux-hardware.org/?probe=221e4d197b) | Jun 19, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [fdbc9729c1](https://linux-hardware.org/?probe=fdbc9729c1) | Jun 18, 2021 |
| Samsung       | RC512                       | [d8681e5e08](https://linux-hardware.org/?probe=d8681e5e08) | Jun 11, 2021 |
| Dell          | Vostro 3360                 | [3427b85349](https://linux-hardware.org/?probe=3427b85349) | Jun 11, 2021 |
| Google        | Kohaku                      | [6de3f99f1d](https://linux-hardware.org/?probe=6de3f99f1d) | Jun 08, 2021 |
| ASUSTek       | T100HAN                     | [d13f35a6f4](https://linux-hardware.org/?probe=d13f35a6f4) | Jun 04, 2021 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b24bfd08ee](https://linux-hardware.org/?probe=b24bfd08ee) | Jun 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| MSI           | Modern 15 A10M              | [23182c745b](https://linux-hardware.org/?probe=23182c745b) | May 27, 2021 |
| Dell          | Latitude D630               | [e65fcdd35a](https://linux-hardware.org/?probe=e65fcdd35a) | May 24, 2021 |
| Acer          | Aspire 5715Z                | [24040eecb6](https://linux-hardware.org/?probe=24040eecb6) | May 23, 2021 |
| Lenovo        | G70-80 80FF                 | [fba07779e2](https://linux-hardware.org/?probe=fba07779e2) | May 21, 2021 |
| MSI           | Modern 15 A10M              | [001eb9ea2f](https://linux-hardware.org/?probe=001eb9ea2f) | May 21, 2021 |
| Toshiba       | Satellite L70-B             | [aba62024a7](https://linux-hardware.org/?probe=aba62024a7) | May 15, 2021 |
| Sony          | VPCSB1V9E                   | [5682d68364](https://linux-hardware.org/?probe=5682d68364) | May 14, 2021 |
| Samsung       | R520/R522/R620              | [2216d5b0b1](https://linux-hardware.org/?probe=2216d5b0b1) | May 14, 2021 |
| Samsung       | R520/R522/R620              | [b724b0cc62](https://linux-hardware.org/?probe=b724b0cc62) | May 14, 2021 |
| Sony          | VPCSB1V9E                   | [d044706f11](https://linux-hardware.org/?probe=d044706f11) | May 13, 2021 |
| Lenovo        | G40-30 80FY                 | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| Sony          | VPCSB1V9E                   | [25eb899222](https://linux-hardware.org/?probe=25eb899222) | May 12, 2021 |
| HP            | Notebook                    | [ca99bba8dc](https://linux-hardware.org/?probe=ca99bba8dc) | May 02, 2021 |
| LG Electro... | S425-L.BC22P1               | [791fd9ff12](https://linux-hardware.org/?probe=791fd9ff12) | Apr 28, 2021 |
| Lenovo        | G460 20041                  | [4015285676](https://linux-hardware.org/?probe=4015285676) | Apr 26, 2021 |
| Sony          | VGN-SZ670AN                 | [e958267bec](https://linux-hardware.org/?probe=e958267bec) | Apr 25, 2021 |
| Sony          | VGN-SZ670AN                 | [cf6e170fcc](https://linux-hardware.org/?probe=cf6e170fcc) | Apr 25, 2021 |
| Dell          | Inspiron N4020              | [9002772847](https://linux-hardware.org/?probe=9002772847) | Apr 21, 2021 |
| Lenovo        | Z50-70 20354                | [b1a5f6b663](https://linux-hardware.org/?probe=b1a5f6b663) | Apr 18, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [6a22991dbe](https://linux-hardware.org/?probe=6a22991dbe) | Apr 18, 2021 |
| Lenovo        | Z50-70 20354                | [fd354e9bec](https://linux-hardware.org/?probe=fd354e9bec) | Apr 18, 2021 |
| Dell          | Inspiron 15-3567            | [0a367170ed](https://linux-hardware.org/?probe=0a367170ed) | Apr 17, 2021 |
| LG Electro... | S425-L.BC22P1               | [64a50f7bb8](https://linux-hardware.org/?probe=64a50f7bb8) | Apr 15, 2021 |
| Dell          | Inspiron N4020              | [e0086be941](https://linux-hardware.org/?probe=e0086be941) | Apr 15, 2021 |
| Lenovo        | G460 20041                  | [e2dea3ec01](https://linux-hardware.org/?probe=e2dea3ec01) | Apr 14, 2021 |
| Dell          | Studio 1555                 | [c161e182c2](https://linux-hardware.org/?probe=c161e182c2) | Apr 14, 2021 |
| Acer          | Aspire 5715Z                | [30729baf7a](https://linux-hardware.org/?probe=30729baf7a) | Apr 07, 2021 |
| GTZS          | Unknown                     | [5600074bc0](https://linux-hardware.org/?probe=5600074bc0) | Apr 07, 2021 |
| Toshiba       | Satellite C70D-B            | [f3e45414fa](https://linux-hardware.org/?probe=f3e45414fa) | Apr 04, 2021 |
| Toshiba       | Satellite C70D-B            | [eacca5eceb](https://linux-hardware.org/?probe=eacca5eceb) | Apr 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [db0eb79b4e](https://linux-hardware.org/?probe=db0eb79b4e) | Mar 31, 2021 |
| ASUSTek       | 1005PE                      | [d75411e5b3](https://linux-hardware.org/?probe=d75411e5b3) | Mar 30, 2021 |
| Toshiba       | Satellite L70-B             | [4f1445876a](https://linux-hardware.org/?probe=4f1445876a) | Mar 27, 2021 |
| Dell          | Vostro 5470                 | [c9dfbce9bd](https://linux-hardware.org/?probe=c9dfbce9bd) | Mar 26, 2021 |
| Toshiba       | Satellite L70-B             | [961ef41a18](https://linux-hardware.org/?probe=961ef41a18) | Mar 21, 2021 |
| Acer          | Aspire 5742G                | [82480a0f24](https://linux-hardware.org/?probe=82480a0f24) | Mar 21, 2021 |
| Lenovo        | S10-3                       | [42884278c4](https://linux-hardware.org/?probe=42884278c4) | Mar 19, 2021 |
| Dell          | System XPS 15Z              | [cb1bcbb365](https://linux-hardware.org/?probe=cb1bcbb365) | Mar 18, 2021 |
| Acer          | Aspire A315-57G             | [4235b59b38](https://linux-hardware.org/?probe=4235b59b38) | Mar 17, 2021 |
| Acer          | Aspire A315-57G             | [4b3b196273](https://linux-hardware.org/?probe=4b3b196273) | Mar 17, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [d2ff3aaec4](https://linux-hardware.org/?probe=d2ff3aaec4) | Mar 12, 2021 |
| ASUSTek       | P53E                        | [3aacf8a497](https://linux-hardware.org/?probe=3aacf8a497) | Mar 07, 2021 |
| Dell          | Vostro 3700                 | [0b9b8232f9](https://linux-hardware.org/?probe=0b9b8232f9) | Mar 05, 2021 |
| HP            | Compaq Presario CQ60        | [06a3cd7d2f](https://linux-hardware.org/?probe=06a3cd7d2f) | Mar 04, 2021 |
| Toshiba       | Satellite A660              | [70166b0f32](https://linux-hardware.org/?probe=70166b0f32) | Mar 01, 2021 |
| Lenovo        | S10-3                       | [6d4f0001a3](https://linux-hardware.org/?probe=6d4f0001a3) | Mar 01, 2021 |
| Notebook      | W54_W94_W955TU,-T,-C        | [1ecf28a1c8](https://linux-hardware.org/?probe=1ecf28a1c8) | Feb 27, 2021 |
| Itautec       | Infoway w7430               | [72a0d46cbd](https://linux-hardware.org/?probe=72a0d46cbd) | Feb 25, 2021 |
| Timi          | TM1612                      | [517a0ea812](https://linux-hardware.org/?probe=517a0ea812) | Feb 23, 2021 |
| Dell          | Vostro 3700                 | [1063468eed](https://linux-hardware.org/?probe=1063468eed) | Feb 21, 2021 |
| Dell          | Vostro 3700                 | [234fac5997](https://linux-hardware.org/?probe=234fac5997) | Feb 21, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | [e79cbcdc53](https://linux-hardware.org/?probe=e79cbcdc53) | Feb 20, 2021 |
| HP            | Pavilion dv6000 (RG264UA... | [eaeef8bb7b](https://linux-hardware.org/?probe=eaeef8bb7b) | Feb 19, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [486fd539f1](https://linux-hardware.org/?probe=486fd539f1) | Feb 19, 2021 |
| Dell          | Inspiron 1525               | [eeabc1752d](https://linux-hardware.org/?probe=eeabc1752d) | Feb 15, 2021 |
| HP            | ProBook 430 G8 Notebook ... | [95b0ea2335](https://linux-hardware.org/?probe=95b0ea2335) | Feb 15, 2021 |
| HP            | ProBook 440 G6              | [715d525514](https://linux-hardware.org/?probe=715d525514) | Feb 07, 2021 |
| HP            | ProBook 440 G7              | [4fd36e0cb3](https://linux-hardware.org/?probe=4fd36e0cb3) | Feb 07, 2021 |
| HP            | ProBook 440 G6              | [f943690f6e](https://linux-hardware.org/?probe=f943690f6e) | Feb 07, 2021 |
| HP            | Pavilion g7                 | [5151e90c72](https://linux-hardware.org/?probe=5151e90c72) | Feb 06, 2021 |
| HP            | G42                         | [b9fbeca924](https://linux-hardware.org/?probe=b9fbeca924) | Feb 05, 2021 |
| HP            | Compaq 6715b (GP690US#AB... | [e77dbfe4a6](https://linux-hardware.org/?probe=e77dbfe4a6) | Feb 05, 2021 |
| Lenovo        | ThinkPad L460 20FVS20700    | [e456ebd9cc](https://linux-hardware.org/?probe=e456ebd9cc) | Jan 29, 2021 |
| HP            | Notebook                    | [c83f3fcce6](https://linux-hardware.org/?probe=c83f3fcce6) | Jan 27, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [c654b7b4ad](https://linux-hardware.org/?probe=c654b7b4ad) | Jan 26, 2021 |
| Lenovo        | IdeaPad 330-17AST 81D7      | [20f7e526b4](https://linux-hardware.org/?probe=20f7e526b4) | Jan 26, 2021 |
| ASUSTek       | X541NA                      | [13d63adbcf](https://linux-hardware.org/?probe=13d63adbcf) | Jan 26, 2021 |
| ASUSTek       | K53SD                       | [81d9e91c01](https://linux-hardware.org/?probe=81d9e91c01) | Jan 19, 2021 |
| Lenovo        | IdeaPad Y550 4186           | [d6ae69ca34](https://linux-hardware.org/?probe=d6ae69ca34) | Jan 17, 2021 |
| Toshiba       | Satellite A205              | [57f9413b16](https://linux-hardware.org/?probe=57f9413b16) | Jan 16, 2021 |
| Lenovo        | ThinkPad T430 2349G7G       | [a6e84d99aa](https://linux-hardware.org/?probe=a6e84d99aa) | Jan 14, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [5335da910d](https://linux-hardware.org/?probe=5335da910d) | Jan 10, 2021 |
| Lenovo        | ThinkPad R400 2786W1L       | [c7fbffcc09](https://linux-hardware.org/?probe=c7fbffcc09) | Jan 10, 2021 |
| Packard Be... | EasyNote_ST85-M-010FR       | [1f7fadda6e](https://linux-hardware.org/?probe=1f7fadda6e) | Jan 10, 2021 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [01626f040a](https://linux-hardware.org/?probe=01626f040a) | Jan 05, 2021 |
| Lenovo        | G50-45 80E3                 | [65ed0bcd53](https://linux-hardware.org/?probe=65ed0bcd53) | Jan 02, 2021 |
| Positivo      | S14CT01                     | [2b0f53fc1a](https://linux-hardware.org/?probe=2b0f53fc1a) | Jan 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [c11d9786f7](https://linux-hardware.org/?probe=c11d9786f7) | Dec 29, 2020 |
| Fujitsu       | FMVNFA50                    | [27b2b3f4de](https://linux-hardware.org/?probe=27b2b3f4de) | Dec 22, 2020 |
| HP            | Pavilion TS 15              | [aea4de88ed](https://linux-hardware.org/?probe=aea4de88ed) | Dec 22, 2020 |
| Toshiba       | Satellite C55D-A            | [f29fb73181](https://linux-hardware.org/?probe=f29fb73181) | Dec 20, 2020 |
| ASUSTek       | K53SD                       | [96067d7a81](https://linux-hardware.org/?probe=96067d7a81) | Dec 13, 2020 |
| Toshiba       | NB510                       | [41d6c29f97](https://linux-hardware.org/?probe=41d6c29f97) | Dec 13, 2020 |
| Gateway       | NE56R                       | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| Lenovo        | ThinkPad T540p 20BFS0WP0... | [6ee5c7543b](https://linux-hardware.org/?probe=6ee5c7543b) | Dec 10, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | [80ecb8f763](https://linux-hardware.org/?probe=80ecb8f763) | Dec 06, 2020 |
| Panasonic     | CF-52PGNBE2M                | [e6e31de556](https://linux-hardware.org/?probe=e6e31de556) | Nov 28, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | [503449ba47](https://linux-hardware.org/?probe=503449ba47) | Nov 27, 2020 |
| Samsung       | 300E4M/300E4S/300E4L        | [f45a6362f7](https://linux-hardware.org/?probe=f45a6362f7) | Nov 27, 2020 |
| HP            | Presario F700 (KA698EA#A... | [19fd9647b4](https://linux-hardware.org/?probe=19fd9647b4) | Nov 23, 2020 |
| HP            | Presario F700 (KA698EA#A... | [b46ffd3c2e](https://linux-hardware.org/?probe=b46ffd3c2e) | Nov 23, 2020 |
| MSI           | GL65 9SDK                   | [a9b83b75fe](https://linux-hardware.org/?probe=a9b83b75fe) | Nov 22, 2020 |
| Positivo      | S14BW01                     | [13fed8ca27](https://linux-hardware.org/?probe=13fed8ca27) | Nov 17, 2020 |
| Gateway       | NE56R                       | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| HP            | ProBook 4720s               | [e58dca9ad5](https://linux-hardware.org/?probe=e58dca9ad5) | Nov 11, 2020 |
| Unknown       | Unknown                     | [5ecd7c84ac](https://linux-hardware.org/?probe=5ecd7c84ac) | Nov 09, 2020 |
| Unknown       | Unknown                     | [abc04e2dfd](https://linux-hardware.org/?probe=abc04e2dfd) | Nov 09, 2020 |
| Samsung       | R530/R730/P530              | [f83b2806d0](https://linux-hardware.org/?probe=f83b2806d0) | Nov 05, 2020 |
| Toshiba       | Satellite Pro U400          | [e6a9e4a78e](https://linux-hardware.org/?probe=e6a9e4a78e) | Nov 05, 2020 |
| Acer          | AOD257                      | [a45ddcc3ab](https://linux-hardware.org/?probe=a45ddcc3ab) | Nov 03, 2020 |
| Acer          | AOD257                      | [3daaf2fdad](https://linux-hardware.org/?probe=3daaf2fdad) | Nov 02, 2020 |
| Samsung       | RV408/RV508                 | [208f929309](https://linux-hardware.org/?probe=208f929309) | Nov 02, 2020 |
| Dell          | Inspiron 3542               | [292816d53a](https://linux-hardware.org/?probe=292816d53a) | Nov 02, 2020 |
| ASUSTek       | E200HA                      | [7fd48df4aa](https://linux-hardware.org/?probe=7fd48df4aa) | Oct 31, 2020 |
| Toshiba       | Satellite L305              | [c2a545a417](https://linux-hardware.org/?probe=c2a545a417) | Oct 30, 2020 |
| Dell          | Inspiron 5759               | [a9f65003ad](https://linux-hardware.org/?probe=a9f65003ad) | Oct 29, 2020 |
| Samsung       | R530/R730/P530              | [855274d6b0](https://linux-hardware.org/?probe=855274d6b0) | Oct 29, 2020 |
| Notebook      | W740SU                      | [cd23f8c64d](https://linux-hardware.org/?probe=cd23f8c64d) | Oct 28, 2020 |
| Lenovo        | ThinkPad T460s 20FAS8CH0... | [bd938bf5fd](https://linux-hardware.org/?probe=bd938bf5fd) | Oct 28, 2020 |
| Positivo      | H14BT58                     | [84c73b4beb](https://linux-hardware.org/?probe=84c73b4beb) | Oct 27, 2020 |
| Itautec       | Infoway                     | [b67c3f6870](https://linux-hardware.org/?probe=b67c3f6870) | Oct 27, 2020 |
| MSI           | U180                        | [7b3f357ff5](https://linux-hardware.org/?probe=7b3f357ff5) | Oct 26, 2020 |
| Lenovo        | G575 4383                   | [43b5c51358](https://linux-hardware.org/?probe=43b5c51358) | Oct 25, 2020 |
| Acer          | Extensa 4620                | [62e829d249](https://linux-hardware.org/?probe=62e829d249) | Oct 22, 2020 |
| Notebook      | W54_55SU1,SUW               | [9655c9ef29](https://linux-hardware.org/?probe=9655c9ef29) | Oct 21, 2020 |
| Acer          | Aspire E1-532P              | [95778c93aa](https://linux-hardware.org/?probe=95778c93aa) | Oct 18, 2020 |
| Toshiba       | Satellite L840              | [4ae1d604ac](https://linux-hardware.org/?probe=4ae1d604ac) | Oct 16, 2020 |
| Acer          | Extensa 4620                | [dd858548d7](https://linux-hardware.org/?probe=dd858548d7) | Oct 15, 2020 |
| Lenovo        | ThinkPad T410 2522DS2       | [a422be5fc0](https://linux-hardware.org/?probe=a422be5fc0) | Oct 15, 2020 |
| Lenovo        | IdeaPad L340-17API 81LY     | [1717667731](https://linux-hardware.org/?probe=1717667731) | Oct 13, 2020 |
| LAMINA        | T-1012B NORD                | [633e33d892](https://linux-hardware.org/?probe=633e33d892) | Oct 12, 2020 |
| Google        | Wolf                        | [0ebdfebf96](https://linux-hardware.org/?probe=0ebdfebf96) | Oct 10, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | [03d64c9c3d](https://linux-hardware.org/?probe=03d64c9c3d) | Oct 10, 2020 |
| HP            | Pavilion dv6                | [0d0a5ac639](https://linux-hardware.org/?probe=0d0a5ac639) | Oct 07, 2020 |
| HP            | Unknown                     | [6ff5164672](https://linux-hardware.org/?probe=6ff5164672) | Oct 07, 2020 |
| Dell          | Latitude D630               | [df80a0678a](https://linux-hardware.org/?probe=df80a0678a) | Oct 04, 2020 |
| ASUSTek       | X202EP                      | [7003257b9c](https://linux-hardware.org/?probe=7003257b9c) | Sep 26, 2020 |
| Dell          | Inspiron 1440               | [863493a36c](https://linux-hardware.org/?probe=863493a36c) | Sep 25, 2020 |
| Fujitsu       | LIFEBOOK P702               | [4f2bb45d77](https://linux-hardware.org/?probe=4f2bb45d77) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57e9fe3f34](https://linux-hardware.org/?probe=57e9fe3f34) | Sep 23, 2020 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [2c253a5689](https://linux-hardware.org/?probe=2c253a5689) | Sep 23, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [d62d875657](https://linux-hardware.org/?probe=d62d875657) | Sep 22, 2020 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [cb4d6ae384](https://linux-hardware.org/?probe=cb4d6ae384) | Sep 22, 2020 |
| Fujitsu       | FMVA05008                   | [36816f2b18](https://linux-hardware.org/?probe=36816f2b18) | Sep 18, 2020 |
| ASUSTek       | X202EP                      | [7331377f2b](https://linux-hardware.org/?probe=7331377f2b) | Sep 16, 2020 |
| Acer          | Prespa M                    | [4310240814](https://linux-hardware.org/?probe=4310240814) | Sep 13, 2020 |
| Acer          | Prespa M                    | [dc7c7827ea](https://linux-hardware.org/?probe=dc7c7827ea) | Sep 13, 2020 |
| ASUSTek       | F7L                         | [0190224dc8](https://linux-hardware.org/?probe=0190224dc8) | Sep 12, 2020 |
| Dell          | MXG071                      | [5fc63c5480](https://linux-hardware.org/?probe=5fc63c5480) | Sep 12, 2020 |
| Apple         | MacBookPro10,2              | [3bc9d8ad1e](https://linux-hardware.org/?probe=3bc9d8ad1e) | Sep 10, 2020 |
| ASUSTek       | P553UA                      | [fca37591fc](https://linux-hardware.org/?probe=fca37591fc) | Sep 10, 2020 |
| Lenovo        | IdeaPad G485 QAWGE          | [2cca042481](https://linux-hardware.org/?probe=2cca042481) | Sep 10, 2020 |
| Lenovo        | Y50-70 20378                | [84a053df62](https://linux-hardware.org/?probe=84a053df62) | Sep 09, 2020 |
| Dell          | Latitude E5450              | [d5eebfddb5](https://linux-hardware.org/?probe=d5eebfddb5) | Sep 07, 2020 |
| Google        | Gandof                      | [6b79edadc5](https://linux-hardware.org/?probe=6b79edadc5) | Sep 04, 2020 |
| Acer          | Aspire ES1-522              | [c5e6143bbd](https://linux-hardware.org/?probe=c5e6143bbd) | Sep 02, 2020 |
| Dell          | XPS 13 9300                 | [121fd4e00e](https://linux-hardware.org/?probe=121fd4e00e) | Aug 30, 2020 |
| Dell          | XPS 13 9300                 | [3a0e9bb81b](https://linux-hardware.org/?probe=3a0e9bb81b) | Aug 30, 2020 |
| Dell          | Inspiron 1440               | [ea7a9a7e0f](https://linux-hardware.org/?probe=ea7a9a7e0f) | Aug 29, 2020 |
| Dell          | Inspiron 1440               | [b7beb93997](https://linux-hardware.org/?probe=b7beb93997) | Aug 28, 2020 |
| Apple         | MacBookPro10,2              | [b5a228d9bf](https://linux-hardware.org/?probe=b5a228d9bf) | Aug 26, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [e95b44a1c2](https://linux-hardware.org/?probe=e95b44a1c2) | Aug 23, 2020 |
| ASUSTek       | K50C                        | [dd9986741e](https://linux-hardware.org/?probe=dd9986741e) | Aug 19, 2020 |
| Acer          | Aspire A315-21              | [72e40559e9](https://linux-hardware.org/?probe=72e40559e9) | Aug 17, 2020 |
| Digibras      | NH4CU03                     | [3ba7006e38](https://linux-hardware.org/?probe=3ba7006e38) | Aug 15, 2020 |
| HP            | ProBook 440 G2              | [18e6bfd3b5](https://linux-hardware.org/?probe=18e6bfd3b5) | Aug 14, 2020 |
| Toshiba       | Satellite C855D             | [ca848be2f0](https://linux-hardware.org/?probe=ca848be2f0) | Aug 12, 2020 |
| Toshiba       | Satellite C855D             | [723c72f289](https://linux-hardware.org/?probe=723c72f289) | Aug 12, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [a8401cc827](https://linux-hardware.org/?probe=a8401cc827) | Aug 12, 2020 |
| HP            | ProBook 445 G7              | [6507b9ca49](https://linux-hardware.org/?probe=6507b9ca49) | Jul 25, 2020 |
| Acer          | V5-171                      | [1f30ec8b2e](https://linux-hardware.org/?probe=1f30ec8b2e) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | [8b84442168](https://linux-hardware.org/?probe=8b84442168) | Jul 25, 2020 |
| Dell          | Inspiron 3442               | [468608973e](https://linux-hardware.org/?probe=468608973e) | Jul 25, 2020 |
| Positivo      | H14BT58                     | [3cb433c2cc](https://linux-hardware.org/?probe=3cb433c2cc) | Jul 24, 2020 |
| ASUSTek       | 1015BX                      | [5f48c6c53b](https://linux-hardware.org/?probe=5f48c6c53b) | Jul 24, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [3d1f4e7cb8](https://linux-hardware.org/?probe=3d1f4e7cb8) | Jul 21, 2020 |
| Apple         | MacBookPro10,2              | [ee73a556b1](https://linux-hardware.org/?probe=ee73a556b1) | Jul 19, 2020 |
| Apple         | MacBookPro10,2              | [33e46bd029](https://linux-hardware.org/?probe=33e46bd029) | Jul 19, 2020 |
| Dell          | Studio 1555                 | [0d511c045e](https://linux-hardware.org/?probe=0d511c045e) | Jul 16, 2020 |
| Dell          | Latitude D520               | [c41f563801](https://linux-hardware.org/?probe=c41f563801) | Jul 16, 2020 |
| ASUSTek       | Q302LA                      | [c453eada8f](https://linux-hardware.org/?probe=c453eada8f) | Jul 09, 2020 |
| HP            | Notebook                    | [10cadcd9b6](https://linux-hardware.org/?probe=10cadcd9b6) | Jul 09, 2020 |
| Toshiba       | Satellite C55D-A            | [9e35eb4bff](https://linux-hardware.org/?probe=9e35eb4bff) | Jul 08, 2020 |
| HP            | Pavilion 15                 | [9f54b2c875](https://linux-hardware.org/?probe=9f54b2c875) | Jul 06, 2020 |
| Acer          | Swift SF314-52G             | [8cd6b05831](https://linux-hardware.org/?probe=8cd6b05831) | Jul 03, 2020 |
| HP            | Pavilion dv6000 (RD870AV... | [921ea4c212](https://linux-hardware.org/?probe=921ea4c212) | Jul 03, 2020 |
| Acer          | Aspire ES1-331              | [b154bdb93b](https://linux-hardware.org/?probe=b154bdb93b) | Jul 02, 2020 |
| HP            | ProBook 450 G6              | [193cbfc862](https://linux-hardware.org/?probe=193cbfc862) | Jun 30, 2020 |
| HP            | Compaq 615                  | [38dc3f0f55](https://linux-hardware.org/?probe=38dc3f0f55) | Jun 29, 2020 |
| Dell          | XPS 13 7390                 | [598acef23f](https://linux-hardware.org/?probe=598acef23f) | Jun 26, 2020 |
| HP            | Compaq 6710b (RM338UT#AB... | [997dd3289c](https://linux-hardware.org/?probe=997dd3289c) | Jun 25, 2020 |
| HP            | Compaq 615                  | [d24b727a5b](https://linux-hardware.org/?probe=d24b727a5b) | Jun 24, 2020 |
| Apple         | MacBookPro8,1               | [93ced4c964](https://linux-hardware.org/?probe=93ced4c964) | Jun 18, 2020 |
| HP            | ProBook 645 G4              | [0803c9f10d](https://linux-hardware.org/?probe=0803c9f10d) | Jun 18, 2020 |
| Acer          | Aspire A515-51G             | [a612626f7b](https://linux-hardware.org/?probe=a612626f7b) | Jun 16, 2020 |
| HP            | ProBook 645 G4              | [1c258b2abb](https://linux-hardware.org/?probe=1c258b2abb) | Jun 15, 2020 |
| HP            | Compaq Presario C700        | [5473d1a8e3](https://linux-hardware.org/?probe=5473d1a8e3) | Jun 10, 2020 |
| HP            | Compaq Presario C700        | [ad60c0409d](https://linux-hardware.org/?probe=ad60c0409d) | Jun 09, 2020 |
| Acer          | Aspire 5734Z                | [6af54cea15](https://linux-hardware.org/?probe=6af54cea15) | Jun 07, 2020 |
| HP            | Pavilion 15                 | [131d6a40c2](https://linux-hardware.org/?probe=131d6a40c2) | Jun 03, 2020 |
| Lenovo        | IdeaPad C340-14API 81N6     | [ea9fb1590a](https://linux-hardware.org/?probe=ea9fb1590a) | Jun 03, 2020 |
| HUAWEI        | KPL-W0X                     | [89038c4214](https://linux-hardware.org/?probe=89038c4214) | Jun 01, 2020 |
| HP            | Pavilion dv5                | [41390482f3](https://linux-hardware.org/?probe=41390482f3) | May 30, 2020 |
| Positivo      | S14CT01                     | [027689152b](https://linux-hardware.org/?probe=027689152b) | May 28, 2020 |
| ASUSTek       | 1015B                       | [4a7ecd1578](https://linux-hardware.org/?probe=4a7ecd1578) | May 28, 2020 |
| ASUSTek       | 1015B                       | [51f3309bfb](https://linux-hardware.org/?probe=51f3309bfb) | May 28, 2020 |
| ASUSTek       | 1015B                       | [73d7cd6398](https://linux-hardware.org/?probe=73d7cd6398) | May 27, 2020 |
| Acer          | Aspire E1-531               | [663bfb0664](https://linux-hardware.org/?probe=663bfb0664) | May 27, 2020 |
| Lenovo        | IdeaPad 320-14IKB 80YF      | [0686c2c434](https://linux-hardware.org/?probe=0686c2c434) | May 25, 2020 |
| Lenovo        | ThinkPad X220 Tablet 429... | [78df8e8526](https://linux-hardware.org/?probe=78df8e8526) | May 21, 2020 |
| HP            | Pavilion Laptop 15-cs2xx... | [a68c9e0a74](https://linux-hardware.org/?probe=a68c9e0a74) | May 18, 2020 |
| ASUSTek       | X201E                       | [aa1e3973cf](https://linux-hardware.org/?probe=aa1e3973cf) | May 18, 2020 |
| Packard Be... | EN Butterfly s              | [587286fd1b](https://linux-hardware.org/?probe=587286fd1b) | May 17, 2020 |
| Lenovo        | ThinkBook 15-IML 20RW       | [c0cf69cb37](https://linux-hardware.org/?probe=c0cf69cb37) | May 13, 2020 |
| Dixonsxp      | Unknown                     | [7ee061c41d](https://linux-hardware.org/?probe=7ee061c41d) | May 09, 2020 |
| HP            | Notebook                    | [0cab8a6d17](https://linux-hardware.org/?probe=0cab8a6d17) | May 07, 2020 |
| Dixonsxp      | Unknown                     | [baf1cb6830](https://linux-hardware.org/?probe=baf1cb6830) | May 06, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [21ce99e154](https://linux-hardware.org/?probe=21ce99e154) | May 03, 2020 |
| Lenovo        | ThinkPad T400 2768AA6       | [665d6e56af](https://linux-hardware.org/?probe=665d6e56af) | May 01, 2020 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [1a00b67e81](https://linux-hardware.org/?probe=1a00b67e81) | Apr 27, 2020 |
| Apple         | MacBookPro9,2               | [74edb3ce25](https://linux-hardware.org/?probe=74edb3ce25) | Apr 26, 2020 |
| Lenovo        | ThinkPad Mini10 3507A31     | [734c5c160a](https://linux-hardware.org/?probe=734c5c160a) | Apr 11, 2020 |
| ASUSTek       | K43E                        | [ef4c10e588](https://linux-hardware.org/?probe=ef4c10e588) | Mar 11, 2020 |
| ASUSTek       | K43E                        | [d03eae9c55](https://linux-hardware.org/?probe=d03eae9c55) | Mar 10, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 21        | 7%      |
| 5.4.0-52-generic  | 13        | 4.33%   |
| 5.4.0-48-generic  | 9         | 3%      |
| 5.4.0-26-generic  | 9         | 3%      |
| 5.4.0-47-generic  | 8         | 2.67%   |
| 5.4.0-65-generic  | 7         | 2.33%   |
| 5.4.0-40-generic  | 7         | 2.33%   |
| 5.13.0-30-generic | 7         | 2.33%   |
| 5.4.0-54-generic  | 6         | 2%      |
| 5.4.0-29-generic  | 6         | 2%      |
| 5.13.0-40-generic | 6         | 2%      |
| 5.13.0-28-generic | 6         | 2%      |
| 5.11.0-38-generic | 6         | 2%      |
| 5.11.0-27-generic | 6         | 2%      |
| 5.4.0-33-generic  | 5         | 1.67%   |
| 5.15.0-41-generic | 5         | 1.67%   |
| 5.8.0-53-generic  | 4         | 1.33%   |
| 5.4.0-72-generic  | 4         | 1.33%   |
| 5.4.0-59-generic  | 4         | 1.33%   |
| 5.4.0-58-generic  | 4         | 1.33%   |
| 5.4.0-56-generic  | 4         | 1.33%   |
| 5.4.0-51-generic  | 4         | 1.33%   |
| 5.4.0-45-generic  | 4         | 1.33%   |
| 5.4.0-37-generic  | 4         | 1.33%   |
| 5.11.0-37-generic | 4         | 1.33%   |
| 5.8.0-55-generic  | 3         | 1%      |
| 5.8.0-49-generic  | 3         | 1%      |
| 5.8.0-45-generic  | 3         | 1%      |
| 5.8.0-41-generic  | 3         | 1%      |
| 5.4.0-91-generic  | 3         | 1%      |
| 5.4.0-89-generic  | 3         | 1%      |
| 5.4.0-81-generic  | 3         | 1%      |
| 5.4.0-74-generic  | 3         | 1%      |
| 5.4.0-73-generic  | 3         | 1%      |
| 5.4.0-62-generic  | 3         | 1%      |
| 5.4.0-60-generic  | 3         | 1%      |
| 5.4.0-31-generic  | 3         | 1%      |
| 5.4.0-131-generic | 3         | 1%      |
| 5.15.0-67-generic | 3         | 1%      |
| 5.15.0-46-generic | 3         | 1%      |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 167       | 60.51%  |
| 5.11.0  | 30        | 10.87%  |
| 5.8.0   | 27        | 9.78%   |
| 5.13.0  | 26        | 9.42%   |
| 5.15.0  | 21        | 7.61%   |
| 5.9.0   | 1         | 0.36%   |
| 5.7.9   | 1         | 0.36%   |
| 5.6.0   | 1         | 0.36%   |
| 5.5.2   | 1         | 0.36%   |
| 5.10.0  | 1         | 0.36%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 167       | 60.51%  |
| 5.11    | 30        | 10.87%  |
| 5.8     | 27        | 9.78%   |
| 5.13    | 26        | 9.42%   |
| 5.15    | 21        | 7.61%   |
| 5.9     | 1         | 0.36%   |
| 5.7     | 1         | 0.36%   |
| 5.6     | 1         | 0.36%   |
| 5.5     | 1         | 0.36%   |
| 5.10    | 1         | 0.36%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 271       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| LXQt     | 257       | 94.14%  |
| LXDE     | 7         | 2.56%   |
| GNOME    | 3         | 1.1%    |
| Cinnamon | 2         | 0.73%   |
| MATE     | 1         | 0.37%   |
| KDE5     | 1         | 0.37%   |
| KDE      | 1         | 0.37%   |
| i3       | 1         | 0.37%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 257       | 94.49%  |
| Tty     | 12        | 4.41%   |
| Wayland | 3         | 1.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 149       | 54.18%  |
| Unknown | 82        | 29.82%  |
| GDM     | 16        | 5.82%   |
| LightDM | 15        | 5.45%   |
| TDM     | 11        | 4%      |
| GDM3    | 2         | 0.73%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 96        | 35.42%  |
| fr_FR | 32        | 11.81%  |
| pt_BR | 23        | 8.49%   |
| en_GB | 19        | 7.01%   |
| it_IT | 14        | 5.17%   |
| de_DE | 13        | 4.8%    |
| ru_RU | 9         | 3.32%   |
| pl_PL | 7         | 2.58%   |
| es_ES | 7         | 2.58%   |
| C     | 7         | 2.58%   |
| en_IN | 4         | 1.48%   |
| en_AU | 4         | 1.48%   |
| fr_CH | 3         | 1.11%   |
| es_MX | 3         | 1.11%   |
| es_AR | 3         | 1.11%   |
| en_IE | 3         | 1.11%   |
| nl_NL | 2         | 0.74%   |
| hu_HU | 2         | 0.74%   |
| es_CL | 2         | 0.74%   |
| en_PH | 2         | 0.74%   |
| en_CA | 2         | 0.74%   |
| tr_TR | 1         | 0.37%   |
| ru_UA | 1         | 0.37%   |
| pt_PT | 1         | 0.37%   |
| nl_BE | 1         | 0.37%   |
| lt_LT | 1         | 0.37%   |
| ja_JP | 1         | 0.37%   |
| fr_BE | 1         | 0.37%   |
| es_UY | 1         | 0.37%   |
| es_CR | 1         | 0.37%   |
| en_ZA | 1         | 0.37%   |
| en_SG | 1         | 0.37%   |
| en_DE | 1         | 0.37%   |
| el_GR | 1         | 0.37%   |
| ca_ES | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 148       | 54.41%  |
| EFI  | 124       | 45.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 254       | 93.38%  |
| Overlay | 10        | 3.68%   |
| Btrfs   | 5         | 1.84%   |
| Xfs     | 1         | 0.37%   |
| Tmpfs   | 1         | 0.37%   |
| Aufs    | 1         | 0.37%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 102       | 37.23%  |
| GPT     | 95        | 34.67%  |
| MBR     | 77        | 28.1%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 246       | 90.11%  |
| Yes       | 27        | 9.89%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 197       | 72.16%  |
| Yes       | 76        | 27.84%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 56        | 20.66%  |
| Lenovo                      | 46        | 16.97%  |
| Dell                        | 33        | 12.18%  |
| ASUSTek Computer            | 27        | 9.96%   |
| Acer                        | 22        | 8.12%   |
| Toshiba                     | 15        | 5.54%   |
| Samsung Electronics         | 10        | 3.69%   |
| Sony                        | 5         | 1.85%   |
| Positivo                    | 5         | 1.85%   |
| Notebook                    | 5         | 1.85%   |
| MSI                         | 5         | 1.85%   |
| Apple                       | 5         | 1.85%   |
| Google                      | 4         | 1.48%   |
| Fujitsu                     | 4         | 1.48%   |
| Packard Bell                | 3         | 1.11%   |
| YASHI                       | 2         | 0.74%   |
| Unknown                     | 2         | 0.74%   |
| UNOWHY                      | 1         | 0.37%   |
| Timi                        | 1         | 0.37%   |
| Teclast                     | 1         | 0.37%   |
| Star Labs                   | 1         | 0.37%   |
| Prestigio                   | 1         | 0.37%   |
| Panasonic                   | 1         | 0.37%   |
| Mediacom                    | 1         | 0.37%   |
| Lanix                       | 1         | 0.37%   |
| LAMINA                      | 1         | 0.37%   |
| Itautec                     | 1         | 0.37%   |
| Intel                       | 1         | 0.37%   |
| I-Life Digital Technologies | 1         | 0.37%   |
| Hungaro Flotta Kft          | 1         | 0.37%   |
| HUAWEI                      | 1         | 0.37%   |
| Haier                       | 1         | 0.37%   |
| GTZS                        | 1         | 0.37%   |
| Gateway                     | 1         | 0.37%   |
| Fujitsu Siemens             | 1         | 0.37%   |
| Dixonsxp                    | 1         | 0.37%   |
| Digibras                    | 1         | 0.37%   |
| DEXP                        | 1         | 0.37%   |
| Alienware                   | 1         | 0.37%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP Notebook                   | 5         | 1.85%   |
| Unknown                       | 5         | 1.85%   |
| HP Pavilion dv6               | 4         | 1.48%   |
| Dell Latitude D630            | 3         | 1.11%   |
| YASHI MYBOOK 360              | 2         | 0.74%   |
| Positivo H14BT58              | 2         | 0.74%   |
| Lenovo IdeaPad 320-15AST 80XV | 2         | 0.74%   |
| HP ProBook 450 G6             | 2         | 0.74%   |
| HP ProBook 440 G8 Notebook PC | 2         | 0.74%   |
| HP ProBook 440 G7             | 2         | 0.74%   |
| HP Pavilion g7                | 2         | 0.74%   |
| Dell Inspiron N5010           | 2         | 0.74%   |
| Dell Inspiron 15-3567         | 2         | 0.74%   |
| ASUS 1015BX                   | 2         | 0.74%   |
| Apple MacBookPro8,1           | 2         | 0.74%   |
| UNOWHY Y13G010S4EI            | 1         | 0.37%   |
| Toshiba Satellite S55-B       | 1         | 0.37%   |
| Toshiba Satellite Pro U400    | 1         | 0.37%   |
| Toshiba Satellite P200        | 1         | 0.37%   |
| Toshiba Satellite L840        | 1         | 0.37%   |
| Toshiba Satellite L70-B       | 1         | 0.37%   |
| Toshiba Satellite L305        | 1         | 0.37%   |
| Toshiba Satellite L15-B       | 1         | 0.37%   |
| Toshiba Satellite C875        | 1         | 0.37%   |
| Toshiba Satellite C855D       | 1         | 0.37%   |
| Toshiba Satellite C70D-B      | 1         | 0.37%   |
| Toshiba Satellite C670D-12N   | 1         | 0.37%   |
| Toshiba Satellite C55D-A      | 1         | 0.37%   |
| Toshiba Satellite A660        | 1         | 0.37%   |
| Toshiba Satellite A205        | 1         | 0.37%   |
| Toshiba NB510                 | 1         | 0.37%   |
| Timi TM1612                   | 1         | 0.37%   |
| Teclast F7 Plus               | 1         | 0.37%   |
| Star Labs Lite                | 1         | 0.37%   |
| Sony VPCSB1V9E                | 1         | 0.37%   |
| Sony VPCEJ1E1E                | 1         | 0.37%   |
| Sony VGN-SZ670AN              | 1         | 0.37%   |
| Sony VGN-CR11Z_R              | 1         | 0.37%   |
| Sony SVF1521C6EW              | 1         | 0.37%   |
| Samsung RV415/RV515           | 1         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 19        | 7.01%   |
| Acer Aspire           | 17        | 6.27%   |
| Lenovo IdeaPad        | 16        | 5.9%    |
| Dell Inspiron         | 16        | 5.9%    |
| Toshiba Satellite     | 14        | 5.17%   |
| HP Pavilion           | 13        | 4.8%    |
| HP ProBook            | 12        | 4.43%   |
| Dell Latitude         | 9         | 3.32%   |
| HP Compaq             | 7         | 2.58%   |
| ASUS VivoBook         | 6         | 2.21%   |
| HP Notebook           | 5         | 1.85%   |
| HP EliteBook          | 5         | 1.85%   |
| Unknown               | 5         | 1.85%   |
| HP Presario           | 3         | 1.11%   |
| HP Laptop             | 3         | 1.11%   |
| Dell Vostro           | 3         | 1.11%   |
| YASHI MYBOOK          | 2         | 0.74%   |
| Positivo H14BT58      | 2         | 0.74%   |
| Packard Bell EasyNote | 2         | 0.74%   |
| Notebook W54          | 2         | 0.74%   |
| Fujitsu LIFEBOOK      | 2         | 0.74%   |
| Dell XPS              | 2         | 0.74%   |
| ASUS ASUS             | 2         | 0.74%   |
| ASUS 1015BX           | 2         | 0.74%   |
| Apple MacBookPro8     | 2         | 0.74%   |
| UNOWHY Y13G010S4EI    | 1         | 0.37%   |
| Toshiba NB510         | 1         | 0.37%   |
| Timi TM1612           | 1         | 0.37%   |
| Teclast F7            | 1         | 0.37%   |
| Star Labs Lite        | 1         | 0.37%   |
| Sony VPCSB1V9E        | 1         | 0.37%   |
| Sony VPCEJ1E1E        | 1         | 0.37%   |
| Sony VGN-SZ670AN      | 1         | 0.37%   |
| Sony VGN-CR11Z        | 1         | 0.37%   |
| Sony SVF1521C6EW      | 1         | 0.37%   |
| Samsung RV415         | 1         | 0.37%   |
| Samsung RV410         | 1         | 0.37%   |
| Samsung RV408         | 1         | 0.37%   |
| Samsung RC512         | 1         | 0.37%   |
| Samsung R530          | 1         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 25        | 9.23%   |
| 2010 | 23        | 8.49%   |
| 2011 | 22        | 8.12%   |
| 2013 | 20        | 7.38%   |
| 2012 | 20        | 7.38%   |
| 2008 | 20        | 7.38%   |
| 2014 | 19        | 7.01%   |
| 2016 | 17        | 6.27%   |
| 2007 | 17        | 6.27%   |
| 2020 | 16        | 5.9%    |
| 2017 | 15        | 5.54%   |
| 2015 | 14        | 5.17%   |
| 2018 | 13        | 4.8%    |
| 2009 | 13        | 4.8%    |
| 2021 | 10        | 3.69%   |
| 2006 | 5         | 1.85%   |
| 2022 | 2         | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 271       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 247       | 90.48%  |
| Enabled  | 26        | 9.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 266       | 98.15%  |
| Yes  | 5         | 1.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 86        | 31.5%   |
| 4.01-8.0   | 71        | 26.01%  |
| 1.01-2.0   | 49        | 17.95%  |
| 8.01-16.0  | 30        | 10.99%  |
| 16.01-24.0 | 19        | 6.96%   |
| 2.01-3.0   | 11        | 4.03%   |
| 32.01-64.0 | 4         | 1.47%   |
| 0.51-1.0   | 2         | 0.73%   |
| 24.01-32.0 | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 144       | 49.48%  |
| 0.51-1.0  | 55        | 18.9%   |
| 2.01-3.0  | 36        | 12.37%  |
| 4.01-8.0  | 28        | 9.62%   |
| 3.01-4.0  | 20        | 6.87%   |
| 0.01-0.5  | 6         | 2.06%   |
| 8.01-16.0 | 2         | 0.69%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 201       | 73.36%  |
| 2      | 66        | 24.09%  |
| 3      | 5         | 1.82%   |
| 4      | 1         | 0.36%   |
| 0      | 1         | 0.36%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 144       | 52.94%  |
| Yes       | 128       | 47.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 233       | 85.66%  |
| No        | 39        | 14.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 256       | 94.46%  |
| No        | 15        | 5.54%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 168       | 60.87%  |
| No        | 108       | 39.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 43        | 15.81%  |
| France       | 35        | 12.87%  |
| Brazil       | 28        | 10.29%  |
| Italy        | 21        | 7.72%   |
| Germany      | 18        | 6.62%   |
| Russia       | 14        | 5.15%   |
| UK           | 13        | 4.78%   |
| Spain        | 9         | 3.31%   |
| Poland       | 9         | 3.31%   |
| Netherlands  | 6         | 2.21%   |
| Switzerland  | 5         | 1.84%   |
| Australia    | 5         | 1.84%   |
| Ukraine      | 4         | 1.47%   |
| Mexico       | 4         | 1.47%   |
| Ireland      | 4         | 1.47%   |
| Indonesia    | 4         | 1.47%   |
| India        | 4         | 1.47%   |
| Argentina    | 3         | 1.1%    |
| Vietnam      | 2         | 0.74%   |
| South Africa | 2         | 0.74%   |
| Romania      | 2         | 0.74%   |
| Philippines  | 2         | 0.74%   |
| Norway       | 2         | 0.74%   |
| Iran         | 2         | 0.74%   |
| Hungary      | 2         | 0.74%   |
| Finland      | 2         | 0.74%   |
| Chile        | 2         | 0.74%   |
| Canada       | 2         | 0.74%   |
| Belgium      | 2         | 0.74%   |
| Uruguay      | 1         | 0.37%   |
| Turkey       | 1         | 0.37%   |
| Tunisia      | 1         | 0.37%   |
| Slovenia     | 1         | 0.37%   |
| Slovakia     | 1         | 0.37%   |
| Singapore    | 1         | 0.37%   |
| Serbia       | 1         | 0.37%   |
| Portugal     | 1         | 0.37%   |
| Luxembourg   | 1         | 0.37%   |
| Lithuania    | 1         | 0.37%   |
| Lebanon      | 1         | 0.37%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Paris                  | 6         | 2.12%   |
| Rome                   | 4         | 1.41%   |
| Milan                  | 4         | 1.41%   |
| Salvador               | 3         | 1.06%   |
| Mexico City            | 3         | 1.06%   |
| Derry                  | 3         | 1.06%   |
| Bengaluru              | 3         | 1.06%   |
| Yekaterinburg          | 2         | 0.71%   |
| Vicosa                 | 2         | 0.71%   |
| Tehran                 | 2         | 0.71%   |
| Stuttgart              | 2         | 0.71%   |
| Southampton            | 2         | 0.71%   |
| Poznan                 | 2         | 0.71%   |
| Porto Alegre           | 2         | 0.71%   |
| Munich                 | 2         | 0.71%   |
| Moscow                 | 2         | 0.71%   |
| Melbourne              | 2         | 0.71%   |
| Krakow                 | 2         | 0.71%   |
| Houston                | 2         | 0.71%   |
| Helsinki               | 2         | 0.71%   |
| Frankfurt am Main      | 2         | 0.71%   |
| Fortaleza              | 2         | 0.71%   |
| Florence               | 2         | 0.71%   |
| Curitiba               | 2         | 0.71%   |
| Cossington             | 2         | 0.71%   |
| Brasília              | 2         | 0.71%   |
| Athens                 | 2         | 0.71%   |
| Zwanenburg             | 1         | 0.35%   |
| Zurich                 | 1         | 0.35%   |
| Winchester             | 1         | 0.35%   |
| Williamsburg           | 1         | 0.35%   |
| Warrington             | 1         | 0.35%   |
| Wadsworth              | 1         | 0.35%   |
| Wadi Maliz             | 1         | 0.35%   |
| Vladivostok            | 1         | 0.35%   |
| Villeneuve-d'Ascq      | 1         | 0.35%   |
| Villars                | 1         | 0.35%   |
| Villandry              | 1         | 0.35%   |
| Villamuriel de Cerrato | 1         | 0.35%   |
| Villabon               | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 48        | 56     | 14.86%  |
| WDC                       | 47        | 56     | 14.55%  |
| Samsung Electronics       | 29        | 33     | 8.98%   |
| Unknown                   | 28        | 34     | 8.67%   |
| Toshiba                   | 27        | 28     | 8.36%   |
| Hitachi                   | 22        | 27     | 6.81%   |
| Kingston                  | 18        | 21     | 5.57%   |
| Crucial                   | 14        | 15     | 4.33%   |
| SanDisk                   | 11        | 16     | 3.41%   |
| Intel                     | 10        | 11     | 3.1%    |
| Fujitsu                   | 8         | 8      | 2.48%   |
| SK hynix                  | 6         | 6      | 1.86%   |
| HGST                      | 6         | 8      | 1.86%   |
| China                     | 4         | 4      | 1.24%   |
| PNY                       | 3         | 3      | 0.93%   |
| Micron Technology         | 3         | 3      | 0.93%   |
| LITEONIT                  | 3         | 3      | 0.93%   |
| KIOXIA                    | 3         | 3      | 0.93%   |
| Apacer                    | 3         | 3      | 0.93%   |
| A-DATA Technology         | 3         | 3      | 0.93%   |
| Patriot                   | 2         | 2      | 0.62%   |
| Unknown                   | 2         | 3      | 0.62%   |
| Vaseky                    | 1         | 1      | 0.31%   |
| USB                       | 1         | 1      | 0.31%   |
| Transcend                 | 1         | 1      | 0.31%   |
| TCSUNBOW                  | 1         | 1      | 0.31%   |
| Star                      | 1         | 1      | 0.31%   |
| SPCC                      | 1         | 1      | 0.31%   |
| QGEEM                     | 1         | 1      | 0.31%   |
| Phison Electronics        | 1         | 1      | 0.31%   |
| OCZ                       | 1         | 1      | 0.31%   |
| Micron/Crucial Technology | 1         | 1      | 0.31%   |
| LITEON                    | 1         | 2      | 0.31%   |
| LDLC                      | 1         | 1      | 0.31%   |
| LaCie                     | 1         | 2      | 0.31%   |
| KingSpec                  | 1         | 1      | 0.31%   |
| KingDian                  | 1         | 1      | 0.31%   |
| JMicron Technology        | 1         | 1      | 0.31%   |
| Integral                  | 1         | 1      | 0.31%   |
| Gigabyte Technology       | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 10        | 2.99%   |
| Toshiba MQ01ABF050 500GB             | 6         | 1.8%    |
| Kingston SA400S37240G 240GB SSD      | 6         | 1.8%    |
| Seagate ST500LT012-1DG142 500GB      | 5         | 1.5%    |
| Seagate ST500LM012 HN-M500MBB 500GB  | 5         | 1.5%    |
| Seagate ST9500325AS 500GB            | 4         | 1.2%    |
| Seagate ST1000LM035-1RK172 1TB       | 4         | 1.2%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 1.2%    |
| WDC WD10SPZX-24Z10T0 1TB             | 3         | 0.9%    |
| WDC PC SN520 SDAPNUW-256G-1006 256GB | 3         | 0.9%    |
| Toshiba MQ01ABD100 1TB               | 3         | 0.9%    |
| Seagate ST320LT007-9ZV142 320GB      | 3         | 0.9%    |
| Kingston SA400S37480G 480GB SSD      | 3         | 0.9%    |
| Crucial CT480BX500SSD1 480GB         | 3         | 0.9%    |
| Crucial CT240BX500SSD1 240GB         | 3         | 0.9%    |
| WDC WD7500BPVX-22JC3T0 752GB         | 2         | 0.6%    |
| WDC WD3200BPVT-22JJ5T0 320GB         | 2         | 0.6%    |
| Unknown MMC Card  64GB               | 2         | 0.6%    |
| Unknown MMC Card  16GB               | 2         | 0.6%    |
| Unknown DA4064  64GB                 | 2         | 0.6%    |
| Unknown 128G32  128GB                | 2         | 0.6%    |
| Toshiba THNSFJ256GDNU A 256GB SSD    | 2         | 0.6%    |
| Toshiba MQ01ABD050 500GB             | 2         | 0.6%    |
| Seagate ST9250410AS 250GB            | 2         | 0.6%    |
| Seagate ST9160412AS 160GB            | 2         | 0.6%    |
| Seagate ST500LT012-9WS142 500GB      | 2         | 0.6%    |
| Seagate ST2000LX001-1RG174 2TB       | 2         | 0.6%    |
| SanDisk NVMe SSD Drive 512GB         | 2         | 0.6%    |
| Samsung SSD 850 EVO 250GB            | 2         | 0.6%    |
| Samsung NVMe SSD Drive 512GB         | 2         | 0.6%    |
| Samsung HM320II 320GB                | 2         | 0.6%    |
| PNY CS900 240GB SSD                  | 2         | 0.6%    |
| Intel SSDSA2M080G2LE 80GB            | 2         | 0.6%    |
| Hitachi HTS547575A9E384 752GB        | 2         | 0.6%    |
| Hitachi HTS543232A7A384 320GB        | 2         | 0.6%    |
| Hitachi HTS542512K9SA00 120GB        | 2         | 0.6%    |
| Hitachi HTS541616J9SA00 160GB        | 2         | 0.6%    |
| HGST HTS545050A7E680 500GB           | 2         | 0.6%    |
| Crucial CT1000MX500SSD1 1TB          | 2         | 0.6%    |
| A-DATA SU650 240GB SSD               | 2         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48        | 56     | 31.37%  |
| WDC                 | 38        | 46     | 24.84%  |
| Toshiba             | 22        | 23     | 14.38%  |
| Hitachi             | 22        | 27     | 14.38%  |
| Fujitsu             | 8         | 8      | 5.23%   |
| Samsung Electronics | 7         | 8      | 4.58%   |
| HGST                | 6         | 8      | 3.92%   |
| USB                 | 1         | 1      | 0.65%   |
| LaCie               | 1         | 1      | 0.65%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 14        | 16     | 14.29%  |
| Crucial             | 14        | 15     | 14.29%  |
| Samsung Electronics | 13        | 14     | 13.27%  |
| Intel               | 8         | 9      | 8.16%   |
| SanDisk             | 7         | 12     | 7.14%   |
| WDC                 | 4         | 5      | 4.08%   |
| China               | 4         | 4      | 4.08%   |
| Toshiba             | 3         | 3      | 3.06%   |
| PNY                 | 3         | 3      | 3.06%   |
| LITEONIT            | 3         | 3      | 3.06%   |
| Apacer              | 3         | 3      | 3.06%   |
| A-DATA Technology   | 3         | 3      | 3.06%   |
| SK hynix            | 2         | 2      | 2.04%   |
| Patriot             | 2         | 2      | 2.04%   |
| Vaseky              | 1         | 1      | 1.02%   |
| Unknown             | 1         | 1      | 1.02%   |
| Transcend           | 1         | 1      | 1.02%   |
| TCSUNBOW            | 1         | 1      | 1.02%   |
| Star                | 1         | 1      | 1.02%   |
| SPCC                | 1         | 1      | 1.02%   |
| OCZ                 | 1         | 1      | 1.02%   |
| Micron Technology   | 1         | 1      | 1.02%   |
| LITEON              | 1         | 2      | 1.02%   |
| LDLC                | 1         | 1      | 1.02%   |
| KingSpec            | 1         | 1      | 1.02%   |
| KingDian            | 1         | 1      | 1.02%   |
| Integral            | 1         | 1      | 1.02%   |
| Dell                | 1         | 1      | 1.02%   |
| Apple               | 1         | 3      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 150       | 178    | 47.62%  |
| SSD     | 96        | 112    | 30.48%  |
| NVMe    | 34        | 40     | 10.79%  |
| MMC     | 30        | 38     | 9.52%   |
| Unknown | 5         | 5      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 226       | 282    | 75.33%  |
| NVMe | 34        | 40     | 11.33%  |
| MMC  | 30        | 38     | 10%     |
| SAS  | 10        | 13     | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 184       | 226    | 77.31%  |
| 0.51-1.0   | 44        | 51     | 18.49%  |
| 1.01-2.0   | 6         | 8      | 2.52%   |
| 3.01-4.0   | 2         | 3      | 0.84%   |
| 2.01-3.0   | 1         | 1      | 0.42%   |
| 4.01-10.0  | 1         | 1      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 81        | 29.35%  |
| 251-500        | 77        | 27.9%   |
| 501-1000       | 33        | 11.96%  |
| 51-100         | 29        | 10.51%  |
| 1-20           | 20        | 7.25%   |
| 21-50          | 17        | 6.16%   |
| 1001-2000      | 10        | 3.62%   |
| More than 3000 | 7         | 2.54%   |
| 2001-3000      | 1         | 0.36%   |
| Unknown        | 1         | 0.36%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 132       | 46.64%  |
| 21-50          | 54        | 19.08%  |
| 101-250        | 41        | 14.49%  |
| 51-100         | 25        | 8.83%   |
| 251-500        | 15        | 5.3%    |
| 501-1000       | 11        | 3.89%   |
| More than 3000 | 2         | 0.71%   |
| 2001-3000      | 1         | 0.35%   |
| 1001-2000      | 1         | 0.35%   |
| Unknown        | 1         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                      | Notebooks | Drives | Percent |
|--------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB         | 2         | 2      | 6.06%   |
| WDC WDS240G2G0A-00JH30 240GB SSD           | 1         | 1      | 3.03%   |
| WDC WD800BEVS-60RST0 80GB                  | 1         | 1      | 3.03%   |
| WDC WD5000LUCT-62C26Y0 500GB               | 1         | 1      | 3.03%   |
| WDC WD3200BPVT-80ZEST0 320GB               | 1         | 1      | 3.03%   |
| WDC WD3200BEVT-75A23T0 320GB               | 1         | 1      | 3.03%   |
| WDC WD2500BEVT-80A23T0 250GB               | 1         | 2      | 3.03%   |
| Toshiba MK5059GSXP 500GB                   | 1         | 1      | 3.03%   |
| TCSUNBOW X1 32GB SSD                       | 1         | 1      | 3.03%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD      | 1         | 1      | 3.03%   |
| SK hynix HFS128G39TND-N210A 128GB SSD      | 1         | 1      | 3.03%   |
| Seagate ST9320325AS 320GB                  | 1         | 1      | 3.03%   |
| Seagate ST9250410AS 250GB                  | 1         | 1      | 3.03%   |
| Seagate ST500LM021-1KJ152 500GB            | 1         | 1      | 3.03%   |
| Seagate ST320LT007-9ZV142 320GB            | 1         | 1      | 3.03%   |
| Samsung Electronics HM160JI 160GB          | 1         | 1      | 3.03%   |
| Samsung Electronics HM121HI 120GB          | 1         | 2      | 3.03%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD    | 1         | 1      | 3.03%   |
| KingSpec NT-256 256GB SSD                  | 1         | 1      | 3.03%   |
| Intel SSDSA2M080G2LE 80GB                  | 1         | 1      | 3.03%   |
| Hitachi HTS723232A7A364 320GB              | 1         | 1      | 3.03%   |
| Hitachi HTS722012K9SA00 120GB              | 1         | 1      | 3.03%   |
| Hitachi HTS545032B9A300 320GB              | 1         | 1      | 3.03%   |
| Hitachi HTS542512K9SA00 120GB              | 1         | 1      | 3.03%   |
| Hitachi HTS541616J9SA00 160GB              | 1         | 1      | 3.03%   |
| HGST HTS545050A7E680 500GB                 | 1         | 1      | 3.03%   |
| HGST HTS541075A9E680 752GB                 | 1         | 1      | 3.03%   |
| HGST HTS541010A9E680 1TB                   | 1         | 1      | 3.03%   |
| Crucial CT960M500SSD1 960GB                | 1         | 1      | 3.03%   |
| Crucial CT120M500SSD3 120GB                | 1         | 1      | 3.03%   |
| Crucial CT120M500SSD1 120GB                | 1         | 1      | 3.03%   |
| A-DATA Technology IM2S3334-256GD 256GB SSD | 1         | 1      | 3.03%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 6         | 7      | 18.18%  |
| Seagate             | 6         | 6      | 18.18%  |
| Hitachi             | 5         | 5      | 15.15%  |
| HGST                | 3         | 3      | 9.09%   |
| Crucial             | 3         | 3      | 9.09%   |
| SK hynix            | 2         | 2      | 6.06%   |
| Samsung Electronics | 2         | 3      | 6.06%   |
| Toshiba             | 1         | 1      | 3.03%   |
| TCSUNBOW            | 1         | 1      | 3.03%   |
| Kingston            | 1         | 1      | 3.03%   |
| KingSpec            | 1         | 1      | 3.03%   |
| Intel               | 1         | 1      | 3.03%   |
| A-DATA Technology   | 1         | 1      | 3.03%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 27.27%  |
| WDC                 | 5         | 6      | 22.73%  |
| Hitachi             | 5         | 5      | 22.73%  |
| HGST                | 3         | 3      | 13.64%  |
| Samsung Electronics | 2         | 3      | 9.09%   |
| Toshiba             | 1         | 1      | 4.55%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 24     | 66.67%  |
| SSD  | 11        | 11     | 33.33%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD2500BEVT-75A23T0 250GB | 1         | 2      | 33.33%  |
| WDC WD1200BEVS-22UST0 120GB  | 1         | 1      | 33.33%  |
| WDC WD10SPZX-22Z10T0 1TB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 3         | 4      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 128       | 186    | 43.99%  |
| Works    | 127       | 148    | 43.64%  |
| Malfunc  | 33        | 35     | 11.34%  |
| Failed   | 3         | 4      | 1.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 198       | 70.21%  |
| AMD                              | 43        | 15.25%  |
| Samsung Electronics              | 9         | 3.19%   |
| SanDisk                          | 7         | 2.48%   |
| Nvidia                           | 4         | 1.42%   |
| Kingston Technology Company      | 4         | 1.42%   |
| SK hynix                         | 3         | 1.06%   |
| KIOXIA                           | 3         | 1.06%   |
| Toshiba America Info Systems     | 2         | 0.71%   |
| Micron Technology                | 2         | 0.71%   |
| JMicron Technology               | 2         | 0.71%   |
| Solid State Storage Technology   | 1         | 0.35%   |
| Silicon Motion                   | 1         | 0.35%   |
| Silicon Integrated Systems [SiS] | 1         | 0.35%   |
| Phison Electronics               | 1         | 0.35%   |
| Micron/Crucial Technology        | 1         | 0.35%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 27        | 8.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 21        | 6.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 20        | 6.19%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 19        | 5.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 17        | 5.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 4.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 14        | 4.33%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 12        | 3.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 10        | 3.1%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 10        | 3.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 9         | 2.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 8         | 2.48%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 8         | 2.48%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 8         | 2.48%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 2.17%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 6         | 1.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 6         | 1.86%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.55%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 1.55%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 4         | 1.24%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                    | 4         | 1.24%   |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 1.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 4         | 1.24%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 4         | 1.24%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 3         | 0.93%   |
| Nvidia MCP51 Serial ATA Controller                                               | 3         | 0.93%   |
| Nvidia MCP51 IDE                                                                 | 3         | 0.93%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 3         | 0.93%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 3         | 0.93%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 2         | 0.62%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 2         | 0.62%   |
| Intel Tiger Lake-LP SATA Controller                                              | 2         | 0.62%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.62%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 2         | 0.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 2         | 0.62%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 0.62%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 0.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                 | 2         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 215       | 70.26%  |
| IDE  | 43        | 14.05%  |
| NVMe | 33        | 10.78%  |
| RAID | 15        | 4.9%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 222       | 81.92%  |
| AMD    | 49        | 18.08%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                        | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz            | 6         | 2.21%   |
| Intel Core i3-6006U CPU @ 2.00GHz            | 6         | 2.21%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz  | 5         | 1.85%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz         | 5         | 1.85%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz            | 5         | 1.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz            | 4         | 1.48%   |
| Intel Celeron N4020 CPU @ 1.10GHz            | 4         | 1.48%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz            | 4         | 1.48%   |
| AMD E-300 APU with Radeon HD Graphics        | 4         | 1.48%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz     | 3         | 1.11%   |
| Intel Core i7-9750H CPU @ 2.60GHz            | 3         | 1.11%   |
| Intel Core i5-7200U CPU @ 2.50GHz            | 3         | 1.11%   |
| Intel Core i5-2410M CPU @ 2.30GHz            | 3         | 1.11%   |
| Intel Core i5-10210U CPU @ 1.60GHz           | 3         | 1.11%   |
| Intel Core i3 CPU M 380 @ 2.53GHz            | 3         | 1.11%   |
| Intel Celeron CPU 847 @ 1.10GHz              | 3         | 1.11%   |
| Intel Atom CPU Z3735F @ 1.33GHz              | 3         | 1.11%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz      | 3         | 1.11%   |
| AMD A4-9125 RADEON R3, 4 COMPUTE CORES 2C+2G | 3         | 1.11%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz  | 2         | 0.74%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz       | 2         | 0.74%   |
| Intel Pentium Dual CPU T2310 @ 1.46GHz       | 2         | 0.74%   |
| Intel Pentium CPU N3710 @ 1.60GHz            | 2         | 0.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz            | 2         | 0.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz            | 2         | 0.74%   |
| Intel Core i7-4510U CPU @ 2.00GHz            | 2         | 0.74%   |
| Intel Core i7-2640M CPU @ 2.80GHz            | 2         | 0.74%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz           | 2         | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz           | 2         | 0.74%   |
| Intel Core i7 CPU M 620 @ 2.67GHz            | 2         | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz            | 2         | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz            | 2         | 0.74%   |
| Intel Core i5-4200U CPU @ 1.60GHz            | 2         | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz            | 2         | 0.74%   |
| Intel Core i5 CPU M 540 @ 2.53GHz            | 2         | 0.74%   |
| Intel Core i5 CPU M 520 @ 2.40GHz            | 2         | 0.74%   |
| Intel Core i3-4005U CPU @ 1.70GHz            | 2         | 0.74%   |
| Intel Core i3-3217U CPU @ 1.80GHz            | 2         | 0.74%   |
| Intel Core i3-2350M CPU @ 2.30GHz            | 2         | 0.74%   |
| Intel Core i3 CPU M 370 @ 2.40GHz            | 2         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 47        | 17.34%  |
| Intel Core i3                  | 31        | 11.44%  |
| Intel Celeron                  | 29        | 10.7%   |
| Intel Core i7                  | 28        | 10.33%  |
| Intel Atom                     | 23        | 8.49%   |
| Intel Core 2 Duo               | 22        | 8.12%   |
| Other                          | 10        | 3.69%   |
| Intel Pentium                  | 9         | 3.32%   |
| Intel Pentium Dual-Core        | 8         | 2.95%   |
| Intel Pentium Dual             | 5         | 1.85%   |
| AMD E                          | 5         | 1.85%   |
| Intel Core 2                   | 4         | 1.48%   |
| AMD Turion 64 X2 Mobile        | 4         | 1.48%   |
| AMD Ryzen 5                    | 4         | 1.48%   |
| AMD E1                         | 4         | 1.48%   |
| AMD A6                         | 4         | 1.48%   |
| AMD A4                         | 4         | 1.48%   |
| Intel Pentium Silver           | 3         | 1.11%   |
| AMD Ryzen 7                    | 3         | 1.11%   |
| Intel Celeron Dual-Core        | 2         | 0.74%   |
| AMD Ryzen 7 PRO                | 2         | 0.74%   |
| AMD Ryzen 3                    | 2         | 0.74%   |
| AMD Phenom II                  | 2         | 0.74%   |
| AMD Athlon X2                  | 2         | 0.74%   |
| Intel Genuine                  | 1         | 0.37%   |
| Intel Core m3                  | 1         | 0.37%   |
| Intel Core 2 Solo              | 1         | 0.37%   |
| Intel Core 2 Extreme           | 1         | 0.37%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.37%   |
| AMD Ryzen 5 PRO                | 1         | 0.37%   |
| AMD Mobile Sempron             | 1         | 0.37%   |
| AMD E2                         | 1         | 0.37%   |
| AMD C-60                       | 1         | 0.37%   |
| AMD C-50                       | 1         | 0.37%   |
| AMD C-30                       | 1         | 0.37%   |
| AMD Athlon II Neo              | 1         | 0.37%   |
| AMD Athlon 64 X2               | 1         | 0.37%   |
| AMD A8                         | 1         | 0.37%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 186       | 68.63%  |
| 4      | 61        | 22.51%  |
| 1      | 12        | 4.43%   |
| 8      | 6         | 2.21%   |
| 6      | 5         | 1.85%   |
| 3      | 1         | 0.37%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 271       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 137       | 50.55%  |
| 2      | 134       | 49.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 271       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 24        | 8.73%   |
| Unknown    | 21        | 7.64%   |
| 0x6fd      | 15        | 5.45%   |
| 0x306a9    | 13        | 4.73%   |
| 0x1067a    | 13        | 4.73%   |
| 0x406e3    | 12        | 4.36%   |
| 0x40651    | 12        | 4.36%   |
| 0x806ec    | 9         | 3.27%   |
| 0x30678    | 9         | 3.27%   |
| 0x20655    | 9         | 3.27%   |
| 0x406c4    | 8         | 2.91%   |
| 0x06006705 | 8         | 2.91%   |
| 0x406c3    | 7         | 2.55%   |
| 0x10676    | 7         | 2.55%   |
| 0x05000119 | 7         | 2.55%   |
| 0x706a1    | 6         | 2.18%   |
| 0x306c3    | 6         | 2.18%   |
| 0x20652    | 6         | 2.18%   |
| 0x306d4    | 5         | 1.82%   |
| 0x106ca    | 5         | 1.82%   |
| 0x806e9    | 4         | 1.45%   |
| 0x806c1    | 4         | 1.45%   |
| 0x706a8    | 4         | 1.45%   |
| 0x906ea    | 3         | 1.09%   |
| 0x806eb    | 3         | 1.09%   |
| 0x806ea    | 3         | 1.09%   |
| 0x6f6      | 3         | 1.09%   |
| 0x30661    | 3         | 1.09%   |
| 0x10661    | 3         | 1.09%   |
| 0x07030105 | 3         | 1.09%   |
| 0x010000c8 | 3         | 1.09%   |
| 0x906ed    | 2         | 0.73%   |
| 0x806d1    | 2         | 0.73%   |
| 0x706e5    | 2         | 0.73%   |
| 0x6fb      | 2         | 0.73%   |
| 0x6fa      | 2         | 0.73%   |
| 0x506ca    | 2         | 0.73%   |
| 0x30673    | 2         | 0.73%   |
| 0x08600106 | 2         | 0.73%   |
| 0x08600104 | 2         | 0.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Silvermont      | 26        | 9.59%   |
| KabyLake        | 26        | 9.59%   |
| Core            | 26        | 9.59%   |
| SandyBridge     | 25        | 9.23%   |
| Penryn          | 21        | 7.75%   |
| Haswell         | 20        | 7.38%   |
| Westmere        | 16        | 5.9%    |
| Skylake         | 13        | 4.8%    |
| IvyBridge       | 13        | 4.8%    |
| Goldmont plus   | 10        | 3.69%   |
| Excavator       | 9         | 3.32%   |
| Bonnell         | 9         | 3.32%   |
| Bobcat          | 9         | 3.32%   |
| Zen 2           | 6         | 2.21%   |
| Puma            | 6         | 2.21%   |
| K8 Hammer       | 6         | 2.21%   |
| TigerLake       | 5         | 1.85%   |
| Broadwell       | 5         | 1.85%   |
| Zen+            | 4         | 1.48%   |
| IceLake         | 4         | 1.48%   |
| K8 & K10 hybrid | 3         | 1.11%   |
| K10             | 3         | 1.11%   |
| Goldmont        | 3         | 1.11%   |
| Zen             | 2         | 0.74%   |
| Jaguar          | 1         | 0.37%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 203       | 65.91%  |
| AMD                              | 67        | 21.75%  |
| Nvidia                           | 37        | 12.01%  |
| Silicon Integrated Systems [SiS] | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 7.27%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 18        | 5.45%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 18        | 5.45%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 15        | 4.55%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 4.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 3.94%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 3.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 3.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 3.33%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 10        | 3.03%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 9         | 2.73%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 2.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 2.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 1.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 6         | 1.82%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 6         | 1.82%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 5         | 1.52%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.52%   |
| Intel HD Graphics 620                                                                    | 4         | 1.21%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 4         | 1.21%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 1.21%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.21%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.91%   |
| Intel UHD Graphics 620                                                                   | 3         | 0.91%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 0.91%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.91%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.91%   |
| Intel HD Graphics 500                                                                    | 3         | 0.91%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.91%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 3         | 0.91%   |
| AMD RV620/M82 [Mobility Radeon HD 3450/3470]                                             | 3         | 0.91%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 3         | 0.91%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.91%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.61%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 2         | 0.61%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.61%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 2         | 0.61%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 168       | 61.99%  |
| 1 x AMD        | 52        | 19.19%  |
| Intel + Nvidia | 23        | 8.49%   |
| 1 x Nvidia     | 12        | 4.43%   |
| Intel + AMD    | 12        | 4.43%   |
| AMD + Nvidia   | 2         | 0.74%   |
| 2 x AMD        | 1         | 0.37%   |
| 1 x SiS        | 1         | 0.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 251       | 91.94%  |
| Proprietary | 19        | 6.96%   |
| Unknown     | 3         | 1.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 179       | 65.57%  |
| 0.01-0.5   | 54        | 19.78%  |
| 1.01-2.0   | 17        | 6.23%   |
| 0.51-1.0   | 15        | 5.49%   |
| 3.01-4.0   | 5         | 1.83%   |
| 2.01-3.0   | 2         | 0.73%   |
| 5.01-6.0   | 1         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 51        | 17.89%  |
| LG Display              | 43        | 15.09%  |
| Samsung Electronics     | 37        | 12.98%  |
| BOE                     | 37        | 12.98%  |
| Chimei Innolux          | 36        | 12.63%  |
| Chi Mei Optoelectronics | 9         | 3.16%   |
| Lenovo                  | 8         | 2.81%   |
| LG Philips              | 7         | 2.46%   |
| Goldstar                | 6         | 2.11%   |
| Apple                   | 6         | 2.11%   |
| Acer                    | 6         | 2.11%   |
| Hewlett-Packard         | 5         | 1.75%   |
| Dell                    | 5         | 1.75%   |
| InfoVision              | 4         | 1.4%    |
| PANDA                   | 3         | 1.05%   |
| Sharp                   | 2         | 0.7%    |
| KDC                     | 2         | 0.7%    |
| HannStar                | 2         | 0.7%    |
| CPT                     | 2         | 0.7%    |
| Vizio                   | 1         | 0.35%   |
| Videoseven              | 1         | 0.35%   |
| Sony                    | 1         | 0.35%   |
| Philips                 | 1         | 0.35%   |
| NEC Computers           | 1         | 0.35%   |
| Lenovo Group Limited    | 1         | 0.35%   |
| InnoLux Display         | 1         | 0.35%   |
| Iiyama                  | 1         | 0.35%   |
| HKC                     | 1         | 0.35%   |
| HannStar Display        | 1         | 0.35%   |
| DENON                   | 1         | 0.35%   |
| CVT                     | 1         | 0.35%   |
| BenQ                    | 1         | 0.35%   |
| AOC                     | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 1.75%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 4         | 1.4%    |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch     | 3         | 1.05%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 1.05%   |
| Lenovo LCD Monitor LEN4031 1280x800 304x190mm 14.1-inch                  | 3         | 1.05%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 3         | 1.05%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 1.05%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch     | 2         | 0.7%    |
| Samsung Electronics LCD Monitor SEC4442 1280x800 303x190mm 14.1-inch     | 2         | 0.7%    |
| Samsung Electronics LCD Monitor SEC3245 1366x768 344x194mm 15.5-inch     | 2         | 0.7%    |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch              | 2         | 0.7%    |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 2         | 0.7%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 2         | 0.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.7%    |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                     | 2         | 0.7%    |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.7%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 2         | 0.7%    |
| BOE LCD Monitor BOE0685 1600x900 382x215mm 17.3-inch                     | 2         | 0.7%    |
| BOE LCD Monitor BOE0674 1366x768 344x194mm 15.5-inch                     | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO6287 1440x900 367x229mm 17.0-inch            | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO305C 1366x768 256x144mm 11.6-inch            | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch            | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 2         | 0.7%    |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                     | 2         | 0.7%    |
| Vizio E260MV VIZ0062 1920x1080 509x286mm 23.0-inch                       | 1         | 0.35%   |
| Videoseven L27ADS IGM2700 1920x1080 598x336mm 27.0-inch                  | 1         | 0.35%   |
| Sony TV SNYA401 1920x1080                                                | 1         | 0.35%   |
| Sharp LCD Monitor SHP14CC 3840x2400 288x180mm 13.4-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                  | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch     | 1         | 0.35%   |
| Samsung Electronics SMS23A550H SAM07C9 1920x1080 509x286mm 23.0-inch     | 1         | 0.35%   |
| Samsung Electronics S22C300 SAM0A1E 1920x1080 477x268mm 21.5-inch        | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 1         | 0.35%   |
| Samsung Electronics LCD Monitor SEC504B 1600x900 382x215mm 17.3-inch     | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 119       | 43.12%  |
| 1920x1080 (FHD)    | 70        | 25.36%  |
| 1280x800 (WXGA)    | 26        | 9.42%   |
| 1600x900 (HD+)     | 20        | 7.25%   |
| 3840x2160 (4K)     | 9         | 3.26%   |
| 1920x1200 (WUXGA)  | 8         | 2.9%    |
| 1440x900 (WXGA+)   | 5         | 1.81%   |
| 1680x1050 (WSXGA+) | 4         | 1.45%   |
| 1280x1024 (SXGA)   | 4         | 1.45%   |
| 1024x600           | 4         | 1.45%   |
| 3840x2400          | 1         | 0.36%   |
| 2560x1600          | 1         | 0.36%   |
| 2560x1440 (QHD)    | 1         | 0.36%   |
| 1360x768           | 1         | 0.36%   |
| 1280x768           | 1         | 0.36%   |
| 1280x720 (HD)      | 1         | 0.36%   |
| 1024x768 (XGA)     | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 115       | 40.35%  |
| 14      | 41        | 14.39%  |
| 13      | 41        | 14.39%  |
| 17      | 24        | 8.42%   |
| 11      | 14        | 4.91%   |
| 23      | 7         | 2.46%   |
| 12      | 7         | 2.46%   |
| 10      | 7         | 2.46%   |
| 21      | 6         | 2.11%   |
| 27      | 5         | 1.75%   |
| 24      | 4         | 1.4%    |
| 22      | 3         | 1.05%   |
| Unknown | 3         | 1.05%   |
| 72      | 2         | 0.7%    |
| 84      | 1         | 0.35%   |
| 33      | 1         | 0.35%   |
| 26      | 1         | 0.35%   |
| 20      | 1         | 0.35%   |
| 19      | 1         | 0.35%   |
| 18      | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 177       | 62.54%  |
| 201-300     | 43        | 15.19%  |
| 351-400     | 28        | 9.89%   |
| 501-600     | 17        | 6.01%   |
| 401-500     | 11        | 3.89%   |
| 1501-2000   | 3         | 1.06%   |
| Unknown     | 3         | 1.06%   |
| 701-800     | 1         | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 212       | 81.23%  |
| 16/10   | 41        | 15.71%  |
| 5/4     | 3         | 1.15%   |
| 4/3     | 2         | 0.77%   |
| Unknown | 2         | 0.77%   |
| 3/2     | 1         | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 113       | 39.65%  |
| 81-90          | 71        | 24.91%  |
| 201-250        | 17        | 5.96%   |
| 121-130        | 16        | 5.61%   |
| 51-60          | 14        | 4.91%   |
| 71-80          | 12        | 4.21%   |
| 41-50          | 7         | 2.46%   |
| 61-70          | 6         | 2.11%   |
| 131-140        | 6         | 2.11%   |
| 301-350        | 5         | 1.75%   |
| 251-300        | 4         | 1.4%    |
| More than 1000 | 3         | 1.05%   |
| 141-150        | 3         | 1.05%   |
| Unknown        | 3         | 1.05%   |
| 151-200        | 2         | 0.7%    |
| 351-500        | 1         | 0.35%   |
| 111-120        | 1         | 0.35%   |
| 91-100         | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 133       | 47.33%  |
| 121-160       | 82        | 29.18%  |
| 51-100        | 52        | 18.51%  |
| 161-240       | 6         | 2.14%   |
| More than 240 | 3         | 1.07%   |
| Unknown       | 3         | 1.07%   |
| 1-50          | 2         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 235       | 85.14%  |
| 2     | 36        | 13.04%  |
| 0     | 3         | 1.09%   |
| 3     | 2         | 0.72%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 150       | 34.56%  |
| Intel                             | 109       | 25.12%  |
| Qualcomm Atheros                  | 79        | 18.2%   |
| Broadcom                          | 39        | 8.99%   |
| Marvell Technology Group          | 14        | 3.23%   |
| Broadcom Limited                  | 9         | 2.07%   |
| Ralink Technology                 | 5         | 1.15%   |
| TP-Link                           | 3         | 0.69%   |
| Ralink                            | 3         | 0.69%   |
| Nvidia                            | 3         | 0.69%   |
| ASIX Electronics                  | 3         | 0.69%   |
| Samsung Electronics               | 2         | 0.46%   |
| Fibocom                           | 2         | 0.46%   |
| Ericsson Business Mobile Networks | 2         | 0.46%   |
| Dell                              | 2         | 0.46%   |
| Attansic Technology               | 2         | 0.46%   |
| Xiaomi                            | 1         | 0.23%   |
| Tenda                             | 1         | 0.23%   |
| Seeed                             | 1         | 0.23%   |
| QinHeng Electronics               | 1         | 0.23%   |
| NetGear                           | 1         | 0.23%   |
| MediaTek                          | 1         | 0.23%   |
| Hewlett-Packard                   | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 72        | 13.9%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 45        | 8.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 3.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 2.7%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 2.32%   |
| Intel Wireless 7260                                                     | 12        | 2.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 2.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 10        | 1.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 1.74%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 8         | 1.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 1.35%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 1.35%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 1.16%   |
| Intel Wireless 3160                                                     | 6         | 1.16%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.97%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.97%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 5         | 0.97%   |
| Intel Wireless 8260                                                     | 5         | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 0.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.77%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 4         | 0.77%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.77%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 4         | 0.77%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 0.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 4         | 0.77%   |
| Intel 82577LM Gigabit Network Connection                                | 4         | 0.77%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                       | 4         | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 0.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 3         | 0.58%   |
| Realtek 802.11ac NIC                                                    | 3         | 0.58%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.58%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 3         | 0.58%   |
| Nvidia MCP51 Ethernet Controller                                        | 3         | 0.58%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 3         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 107       | 39.63%  |
| Qualcomm Atheros                  | 67        | 24.81%  |
| Realtek Semiconductor             | 50        | 18.52%  |
| Broadcom                          | 25        | 9.26%   |
| Ralink Technology                 | 5         | 1.85%   |
| Broadcom Limited                  | 4         | 1.48%   |
| TP-Link                           | 3         | 1.11%   |
| Ralink                            | 3         | 1.11%   |
| Fibocom                           | 2         | 0.74%   |
| Tenda                             | 1         | 0.37%   |
| NetGear                           | 1         | 0.37%   |
| Ericsson Business Mobile Networks | 1         | 0.37%   |
| Dell                              | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 17        | 6.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 14        | 5.15%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 4.41%   |
| Intel Wireless 7260                                                     | 12        | 4.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 11        | 4.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 3.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 9         | 3.31%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 8         | 2.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 7         | 2.57%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 2.57%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 7         | 2.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 2.21%   |
| Intel Wireless 3160                                                     | 6         | 2.21%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 6         | 2.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.84%   |
| Intel Wireless 8260                                                     | 5         | 1.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.84%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 1.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.47%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 4         | 1.47%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 4         | 1.47%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 4         | 1.47%   |
| Realtek 802.11ac NIC                                                    | 3         | 1.1%    |
| Ralink MT7601U Wireless Adapter                                         | 3         | 1.1%    |
| Intel Wireless 7265                                                     | 3         | 1.1%    |
| Intel Wireless 3165                                                     | 3         | 1.1%    |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 3         | 1.1%    |
| Intel Centrino Wireless-N 100                                           | 3         | 1.1%    |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.1%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.1%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.74%   |
| Realtek RTL8191SEvA Wireless LAN Controller                             | 2         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.74%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 2         | 0.74%   |
| Realtek 802.11n WLAN Adapter                                            | 2         | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 134       | 55.83%  |
| Intel                    | 33        | 13.75%  |
| Qualcomm Atheros         | 22        | 9.17%   |
| Broadcom                 | 20        | 8.33%   |
| Marvell Technology Group | 14        | 5.83%   |
| Broadcom Limited         | 5         | 2.08%   |
| Nvidia                   | 3         | 1.25%   |
| ASIX Electronics         | 3         | 1.25%   |
| Samsung Electronics      | 2         | 0.83%   |
| Attansic Technology      | 2         | 0.83%   |
| Xiaomi                   | 1         | 0.42%   |
| MediaTek                 | 1         | 0.42%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 72        | 29.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 45        | 18.67%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 10        | 4.15%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 5         | 2.07%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 5         | 2.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 1.66%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 4         | 1.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 4         | 1.66%   |
| Intel 82577LM Gigabit Network Connection                                       | 4         | 1.66%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 4         | 1.66%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 4         | 1.66%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 3         | 1.24%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 3         | 1.24%   |
| Nvidia MCP51 Ethernet Controller                                               | 3         | 1.24%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 3         | 1.24%   |
| Intel Ethernet Connection I219-V                                               | 3         | 1.24%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.24%   |
| Intel 82567LM Gigabit Network Connection                                       | 3         | 1.24%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 3         | 1.24%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 3         | 1.24%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 3         | 1.24%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 1.24%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2         | 0.83%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.83%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.83%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.83%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 2         | 0.83%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.83%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.83%   |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.83%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 2         | 0.83%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 1         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.41%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 1         | 0.41%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.41%   |
| MediaTek Wiko U316AT                                                           | 1         | 0.41%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.41%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 257       | 51.92%  |
| Ethernet | 233       | 47.07%  |
| Modem    | 5         | 1.01%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 212       | 75.44%  |
| Ethernet | 69        | 24.56%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 207       | 76.38%  |
| 1     | 47        | 17.34%  |
| 0     | 15        | 5.54%   |
| 3     | 2         | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 234       | 84.48%  |
| Yes  | 43        | 15.52%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 68        | 39.31%  |
| Qualcomm Atheros Communications | 20        | 11.56%  |
| Realtek Semiconductor           | 16        | 9.25%   |
| Broadcom                        | 14        | 8.09%   |
| Lite-On Technology              | 10        | 5.78%   |
| Cambridge Silicon Radio         | 9         | 5.2%    |
| IMC Networks                    | 8         | 4.62%   |
| Dell                            | 6         | 3.47%   |
| Apple                           | 5         | 2.89%   |
| Hewlett-Packard                 | 3         | 1.73%   |
| Foxconn / Hon Hai               | 3         | 1.73%   |
| ASUSTek Computer                | 3         | 1.73%   |
| Toshiba                         | 2         | 1.16%   |
| Ralink Technology               | 2         | 1.16%   |
| Alps Electric                   | 2         | 1.16%   |
| TP-Link                         | 1         | 0.58%   |
| Chicony Electronics             | 1         | 0.58%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 34        | 19.65%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 16        | 9.25%   |
| Realtek Bluetooth Radio                                                             | 11        | 6.36%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 11        | 6.36%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 5.2%    |
| Intel AX200 Bluetooth                                                               | 7         | 4.05%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 2.89%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 2.31%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 4         | 2.31%   |
| Intel AX201 Bluetooth                                                               | 4         | 2.31%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 2.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 3         | 1.73%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.73%   |
| Intel Bluetooth Device                                                              | 3         | 1.73%   |
| Apple Bluetooth Host Controller                                                     | 3         | 1.73%   |
| Realtek RTL8821A Bluetooth                                                          | 2         | 1.16%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 1.16%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 1.16%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.16%   |
| IMC Networks Bluetooth Device                                                       | 2         | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.16%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 1.16%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 1.16%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 2         | 1.16%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 1.16%   |
| TP-Link UB500 Adapter                                                               | 1         | 0.58%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.58%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.58%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.58%   |
| Qualcomm Atheros Bluetooth                                                          | 1         | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.58%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 1         | 0.58%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.58%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 1         | 0.58%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.58%   |
| IMC Networks Bluetooth module                                                       | 1         | 0.58%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.58%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.58%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.58%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 206       | 70.79%  |
| AMD                               | 54        | 18.56%  |
| Nvidia                            | 21        | 7.22%   |
| GN Netcom                         | 2         | 0.69%   |
| C-Media Electronics               | 2         | 0.69%   |
| Texas Instruments                 | 1         | 0.34%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.34%   |
| Realtek Semiconductor             | 1         | 0.34%   |
| Logitech                          | 1         | 0.34%   |
| Hewlett-Packard                   | 1         | 0.34%   |
| Elitegroup Computer Systems (ECS) | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 23        | 6.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 22        | 6.21%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 5.65%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 20        | 5.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 16        | 4.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 15        | 4.24%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 3.95%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 3.67%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 3.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 3.11%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 3.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 2.82%   |
| AMD FCH Azalia Controller                                                                         | 10        | 2.82%   |
| AMD High Definition Audio Controller                                                              | 9         | 2.54%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 9         | 2.54%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 2.26%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 2.26%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.98%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.69%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 1.69%   |
| AMD Wrestler HDMI Audio                                                                           | 6         | 1.69%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 6         | 1.69%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.69%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 5         | 1.41%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.41%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.41%   |
| Intel Broadwell-U Audio Controller                                                                | 5         | 1.41%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.41%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.85%   |
| Nvidia MCP51 High Definition Audio                                                                | 3         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.85%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.85%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 3         | 0.85%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.56%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 53        | 24.31%  |
| SK hynix            | 41        | 18.81%  |
| Unknown             | 35        | 16.06%  |
| Micron Technology   | 21        | 9.63%   |
| A-DATA Technology   | 9         | 4.13%   |
| Nanya Technology    | 8         | 3.67%   |
| Kingston            | 8         | 3.67%   |
| Crucial             | 7         | 3.21%   |
| Unknown (ABCD)      | 6         | 2.75%   |
| Smart               | 4         | 1.83%   |
| Corsair             | 4         | 1.83%   |
| Elpida              | 3         | 1.38%   |
| Team                | 2         | 0.92%   |
| Patriot             | 2         | 0.92%   |
| Transcend           | 1         | 0.46%   |
| Teikon              | 1         | 0.46%   |
| Sesame              | 1         | 0.46%   |
| Ramaxel Technology  | 1         | 0.46%   |
| Qimonda             | 1         | 0.46%   |
| PNY                 | 1         | 0.46%   |
| Multilaser          | 1         | 0.46%   |
| GOODRAM             | 1         | 0.46%   |
| Goldkey             | 1         | 0.46%   |
| Goldenmars          | 1         | 0.46%   |
| G.Skill             | 1         | 0.46%   |
| Digiboard           | 1         | 0.46%   |
| Avant               | 1         | 0.46%   |
| ASint Technology    | 1         | 0.46%   |
| Apacer              | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 2.16%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 2.16%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 5         | 2.16%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 4         | 1.72%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 3         | 1.29%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                    | 3         | 1.29%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 1.29%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 3         | 1.29%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 3         | 1.29%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 3         | 1.29%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.29%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.29%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.29%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.29%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1066MT/s                   | 2         | 0.86%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.86%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.86%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 2         | 0.86%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 2         | 0.86%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1600MT/s                  | 2         | 0.86%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.86%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.86%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 2         | 0.86%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.86%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.86%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 2         | 0.86%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.86%   |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 2         | 0.86%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.86%   |
| Micron RAM Module 8192MB SODIMM DDR4 2667MT/s                    | 2         | 0.86%   |
| Micron RAM 8KTF51264HZ-1G6E1 4096MB SODIMM DDR3 1600MT/s         | 2         | 0.86%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 2         | 0.86%   |
| Corsair RAM CMSO8GX3M1C1600C11 8GB SODIMM DDR3 1600MT/s          | 2         | 0.86%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2133MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 8192MB SODIMM DDR3 1333MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 8192MB Row Of Chips LPDDR4 4267MT/s           | 1         | 0.43%   |
| Unknown RAM Module 512MB SODIMM DDR2                             | 1         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2133MT/s                   | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 85        | 46.7%   |
| DDR4    | 52        | 28.57%  |
| DDR2    | 24        | 13.19%  |
| LPDDR4  | 10        | 5.49%   |
| SDRAM   | 5         | 2.75%   |
| LPDDR3  | 4         | 2.2%    |
| DDR     | 1         | 0.55%   |
| Unknown | 1         | 0.55%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 173       | 95.58%  |
| Row Of Chips | 5         | 2.76%   |
| DIMM         | 1         | 0.55%   |
| Chip         | 1         | 0.55%   |
| Unknown      | 1         | 0.55%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 74        | 34.58%  |
| 8192  | 55        | 25.7%   |
| 2048  | 52        | 24.3%   |
| 1024  | 20        | 9.35%   |
| 16384 | 9         | 4.21%   |
| 32768 | 3         | 1.4%    |
| 512   | 1         | 0.47%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 51        | 25.25%  |
| 1334    | 23        | 11.39%  |
| 2667    | 22        | 10.89%  |
| 2400    | 21        | 10.4%   |
| 3200    | 15        | 7.43%   |
| 667     | 14        | 6.93%   |
| 1333    | 12        | 5.94%   |
| 2133    | 6         | 2.97%   |
| 2048    | 5         | 2.48%   |
| 800     | 5         | 2.48%   |
| Unknown | 5         | 2.48%   |
| 1867    | 4         | 1.98%   |
| 1067    | 4         | 1.98%   |
| 533     | 4         | 1.98%   |
| 3266    | 3         | 1.49%   |
| 1066    | 3         | 1.49%   |
| 8400    | 1         | 0.5%    |
| 4267    | 1         | 0.5%    |
| 1200    | 1         | 0.5%    |
| 2       | 1         | 0.5%    |
| 1       | 1         | 0.5%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 2         | 40%     |
| Brother Industries  | 2         | 40%     |
| Samsung Electronics | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Samsung SCX-4200 series | 1         | 20%     |
| HP Deskjet 3520 series  | 1         | 20%     |
| HP Deskjet 1050 J410    | 1         | 20%     |
| Brother PTUSB Printing  | 1         | 20%     |
| Brother DCP-7055W       | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 63        | 27.75%  |
| Realtek Semiconductor                  | 18        | 7.93%   |
| IMC Networks                           | 18        | 7.93%   |
| Bison Electronics                      | 17        | 7.49%   |
| Microdia                               | 15        | 6.61%   |
| Alcor Micro                            | 10        | 4.41%   |
| Quanta                                 | 9         | 3.96%   |
| Suyin                                  | 8         | 3.52%   |
| Sunplus Innovation Technology          | 8         | 3.52%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 3.52%   |
| Silicon Motion                         | 6         | 2.64%   |
| Lite-On Technology                     | 5         | 2.2%    |
| Apple                                  | 5         | 2.2%    |
| Ricoh                                  | 4         | 1.76%   |
| Lenovo                                 | 4         | 1.76%   |
| Syntek                                 | 3         | 1.32%   |
| Luxvisions Innotech Limited            | 3         | 1.32%   |
| Importek                               | 3         | 1.32%   |
| ALi                                    | 3         | 1.32%   |
| Acer                                   | 3         | 1.32%   |
| Z-Star Microelectronics                | 2         | 0.88%   |
| Samsung Electronics                    | 2         | 0.88%   |
| Y Media                                | 1         | 0.44%   |
| WCM_USB                                | 1         | 0.44%   |
| OmniVision Technologies                | 1         | 0.44%   |
| Nintendo                               | 1         | 0.44%   |
| LG Electronics                         | 1         | 0.44%   |
| Hy-UXGA(B5M2)-Camera                   | 1         | 0.44%   |
| HD USB Camera                          | 1         | 0.44%   |
| Generalplus Technology                 | 1         | 0.44%   |
| GEMBIRD                                | 1         | 0.44%   |
| DigiTech                               | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 9         | 3.95%   |
| Realtek Integrated_Webcam_HD                         | 6         | 2.63%   |
| Chicony TOSHIBA Web Camera - HD                      | 6         | 2.63%   |
| Alcor Micro USB 2.0 Camera                           | 6         | 2.63%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 4         | 1.75%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 4         | 1.75%   |
| Chicony HP HD Camera                                 | 4         | 1.75%   |
| Bison Lenovo EasyCamera                              | 4         | 1.75%   |
| Realtek Integrated Webcam                            | 3         | 1.32%   |
| Quanta HP HD Camera                                  | 3         | 1.32%   |
| Lite-On HP HD Camera                                 | 3         | 1.32%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 3         | 1.32%   |
| Chicony USB 2.0 Camera                               | 3         | 1.32%   |
| Chicony HD WebCam (Acer)                             | 3         | 1.32%   |
| Chicony EasyCamera                                   | 3         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101 | 3         | 1.32%   |
| Bison VGA WebCam                                     | 3         | 1.32%   |
| Bison HD Webcam                                      | 3         | 1.32%   |
| Apple FaceTime HD Camera                             | 3         | 1.32%   |
| Alcor Micro Asus Integrated Webcam                   | 3         | 1.32%   |
| Sunplus Laptop Integrated Webcam HD                  | 2         | 0.88%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 0.88%   |
| Sunplus HD WebCam                                    | 2         | 0.88%   |
| Samsung Galaxy series, misc. (MTP mode)              | 2         | 0.88%   |
| Realtek USB2.0-Camera                                | 2         | 0.88%   |
| Realtek Lenovo EasyCamera                            | 2         | 0.88%   |
| Quanta VGA WebCam                                    | 2         | 0.88%   |
| Quanta HP Webcam                                     | 2         | 0.88%   |
| Microdia Sonix USB 2.0 Camera                        | 2         | 0.88%   |
| Microdia Laptop_Integrated_Webcam_2M                 | 2         | 0.88%   |
| Microdia Integrated Webcam                           | 2         | 0.88%   |
| Microdia 1.3 MPixel Integrated Webcam                | 2         | 0.88%   |
| Luxvisions Innotech Limited HP HD Camera             | 2         | 0.88%   |
| Lenovo Integrated Webcam                             | 2         | 0.88%   |
| Importek TOSHIBA Web Camera - HD                     | 2         | 0.88%   |
| IMC Networks USB 2.0 UVC VGA WebCam                  | 2         | 0.88%   |
| IMC Networks Integrated Camera                       | 2         | 0.88%   |
| Chicony HP Webcam                                    | 2         | 0.88%   |
| Chicony HP TrueVision HD                             | 2         | 0.88%   |
| Chicony HD WebCam                                    | 2         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 36.67%  |
| AuthenTec                  | 8         | 26.67%  |
| Shenzhen Goodix Technology | 3         | 10%     |
| Upek                       | 2         | 6.67%   |
| Synaptics                  | 2         | 6.67%   |
| STMicroelectronics         | 2         | 6.67%   |
| LighTuning Technology      | 1         | 3.33%   |
| Elan Microelectronics      | 1         | 3.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| AuthenTec AES2501 Fingerprint Sensor                   | 3         | 10%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 2         | 6.67%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 6.67%   |
| Synaptics Fingerprint reader [HP G6]                   | 2         | 6.67%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 6.67%   |
| AuthenTec AES2810                                      | 2         | 6.67%   |
| AuthenTec AES1600                                      | 2         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 3.33%   |
| Validity Sensors VFS491                                | 1         | 3.33%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 3.33%   |
| Validity Sensors VFS301 Fingerprint Reader             | 1         | 3.33%   |
| Validity Sensors VFS300 Fingerprint Reader             | 1         | 3.33%   |
| Validity Sensors VFS101 Fingerprint Reader             | 1         | 3.33%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 3.33%   |
| Shenzhen Goodix  FingerPrint Device                    | 1         | 3.33%   |
| Shenzhen Goodix Fingerprint Reader                     | 1         | 3.33%   |
| Shenzhen Goodix FingerPrint                            | 1         | 3.33%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 3.33%   |
| Elan ELAN:Fingerprint                                  | 1         | 3.33%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 4         | 40%     |
| O2 Micro    | 3         | 30%     |
| Broadcom    | 2         | 20%     |
| Upek        | 1         | 10%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 40%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 30%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 10%     |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 10%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 210       | 76.36%  |
| 1     | 51        | 18.55%  |
| 2     | 13        | 4.73%   |
| 3     | 1         | 0.36%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 30        | 38.46%  |
| Graphics card         | 18        | 23.08%  |
| Net/wireless          | 10        | 12.82%  |
| Chipcard              | 10        | 12.82%  |
| Camera                | 3         | 3.85%   |
| Storage               | 2         | 2.56%   |
| Sound                 | 1         | 1.28%   |
| Net/ethernet          | 1         | 1.28%   |
| Multimedia controller | 1         | 1.28%   |
| Flash memory          | 1         | 1.28%   |
| Bluetooth             | 1         | 1.28%   |

