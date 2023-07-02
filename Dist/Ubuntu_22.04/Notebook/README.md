Ubuntu 22.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 22.04.

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

Total: 7372

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 3537               | [43b81e38cd](https://linux-hardware.org/?probe=43b81e38cd) | Jul 01, 2023 |
| ASUSTek       | K52Dr                       | [f97425ba5f](https://linux-hardware.org/?probe=f97425ba5f) | Jun 30, 2023 |
| Acer          | Aspire E5-575G              | [f127804b4a](https://linux-hardware.org/?probe=f127804b4a) | Jun 30, 2023 |
| Sony          | VGN-NS38E_S                 | [270e8b9fb7](https://linux-hardware.org/?probe=270e8b9fb7) | Jun 30, 2023 |
| Sony          | VGN-NS38E_S                 | [ca33cfbc67](https://linux-hardware.org/?probe=ca33cfbc67) | Jun 30, 2023 |
| Apple         | MacBookPro8,2               | [8386acaa29](https://linux-hardware.org/?probe=8386acaa29) | Jun 30, 2023 |
| HP            | 15                          | [2d80407689](https://linux-hardware.org/?probe=2d80407689) | Jun 30, 2023 |
| HP            | 15                          | [398d659d8c](https://linux-hardware.org/?probe=398d659d8c) | Jun 30, 2023 |
| HP            | EliteBook 8460p             | [d4a008aefb](https://linux-hardware.org/?probe=d4a008aefb) | Jun 30, 2023 |
| Dell          | Latitude 7350               | [95fc412b55](https://linux-hardware.org/?probe=95fc412b55) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [05cb990f84](https://linux-hardware.org/?probe=05cb990f84) | Jun 30, 2023 |
| Apple         | MacBookAir9,1               | [bd5c030739](https://linux-hardware.org/?probe=bd5c030739) | Jun 30, 2023 |
| Apple         | MacBookAir9,1               | [ce486a5063](https://linux-hardware.org/?probe=ce486a5063) | Jun 30, 2023 |
| HP            | Laptop 15-ef2xxx            | [d0ea6a2d9d](https://linux-hardware.org/?probe=d0ea6a2d9d) | Jun 30, 2023 |
| HP            | EliteBook 2540p             | [7b546735a4](https://linux-hardware.org/?probe=7b546735a4) | Jun 30, 2023 |
| Acer          | Aspire 5737Z                | [842aa57faf](https://linux-hardware.org/?probe=842aa57faf) | Jun 30, 2023 |
| Samsung       | R430/R480                   | [485a09a0d2](https://linux-hardware.org/?probe=485a09a0d2) | Jun 30, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [39f7adb927](https://linux-hardware.org/?probe=39f7adb927) | Jun 30, 2023 |
| Monster       | TULPAR T7 V21.7             | [046803a297](https://linux-hardware.org/?probe=046803a297) | Jun 30, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [7f9164d1e0](https://linux-hardware.org/?probe=7f9164d1e0) | Jun 29, 2023 |
| HP            | ProBook 4530s               | [d1c3bf37ff](https://linux-hardware.org/?probe=d1c3bf37ff) | Jun 29, 2023 |
| Dell          | XPS 15 9570                 | [e0492d6173](https://linux-hardware.org/?probe=e0492d6173) | Jun 29, 2023 |
| Dell          | Latitude 7350               | [8ae13e8fdb](https://linux-hardware.org/?probe=8ae13e8fdb) | Jun 29, 2023 |
| MSI           | Modern 14 B5M               | [cb0eb574da](https://linux-hardware.org/?probe=cb0eb574da) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [93e0628fbe](https://linux-hardware.org/?probe=93e0628fbe) | Jun 29, 2023 |
| HP            | Pavilion dv6                | [a24ee9a903](https://linux-hardware.org/?probe=a24ee9a903) | Jun 29, 2023 |
| ASUSTek       | X751MA                      | [b36ca5687c](https://linux-hardware.org/?probe=b36ca5687c) | Jun 29, 2023 |
| Acer          | TravelMate B113             | [04738ce824](https://linux-hardware.org/?probe=04738ce824) | Jun 29, 2023 |
| Acer          | TravelMate B113             | [9cfe4d5036](https://linux-hardware.org/?probe=9cfe4d5036) | Jun 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [0f0defbd9c](https://linux-hardware.org/?probe=0f0defbd9c) | Jun 29, 2023 |
| Dell          | Precision M6500             | [199e90722c](https://linux-hardware.org/?probe=199e90722c) | Jun 29, 2023 |
| HP            | Pavilion g6                 | [ef275e1249](https://linux-hardware.org/?probe=ef275e1249) | Jun 29, 2023 |
| Lenovo        | ThinkPad Edge E545 20B2S... | [c7e71c8c0b](https://linux-hardware.org/?probe=c7e71c8c0b) | Jun 29, 2023 |
| Lenovo        | ThinkPad Edge E545 20B2S... | [0c3b48af38](https://linux-hardware.org/?probe=0c3b48af38) | Jun 29, 2023 |
| Lenovo        | ThinkBook 14s-IML 20RS      | [e3d095fc9f](https://linux-hardware.org/?probe=e3d095fc9f) | Jun 29, 2023 |
| Toshiba       | TECRA R950                  | [cab34ec3dc](https://linux-hardware.org/?probe=cab34ec3dc) | Jun 28, 2023 |
| Toshiba       | Satellite X200              | [4a3e7008cf](https://linux-hardware.org/?probe=4a3e7008cf) | Jun 28, 2023 |
| HP            | ProBook 470 G3              | [1025bf4027](https://linux-hardware.org/?probe=1025bf4027) | Jun 28, 2023 |
| HP            | ProBook 470 G3              | [b8453a6830](https://linux-hardware.org/?probe=b8453a6830) | Jun 28, 2023 |
| Lenovo        | ThinkPad X240 20AL007LUK    | [ee0761a131](https://linux-hardware.org/?probe=ee0761a131) | Jun 28, 2023 |
| Dell          | Latitude 7440               | [24f85667ac](https://linux-hardware.org/?probe=24f85667ac) | Jun 28, 2023 |
| ASUSTek       | N75SF                       | [eda2a0d726](https://linux-hardware.org/?probe=eda2a0d726) | Jun 28, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [5d30ae9d05](https://linux-hardware.org/?probe=5d30ae9d05) | Jun 28, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | [fee1e04033](https://linux-hardware.org/?probe=fee1e04033) | Jun 28, 2023 |
| HP            | EliteBook 745 G2            | [f64e6dd56e](https://linux-hardware.org/?probe=f64e6dd56e) | Jun 28, 2023 |
| ASUSTek       | F5SR                        | [3722cfa5fb](https://linux-hardware.org/?probe=3722cfa5fb) | Jun 27, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | [46e3ea33a3](https://linux-hardware.org/?probe=46e3ea33a3) | Jun 27, 2023 |
| Dell          | Latitude E6530              | [f015f73aef](https://linux-hardware.org/?probe=f015f73aef) | Jun 27, 2023 |
| Samsung       | 550XCJ/550XCR               | [bca3e799e0](https://linux-hardware.org/?probe=bca3e799e0) | Jun 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [5922b4d31f](https://linux-hardware.org/?probe=5922b4d31f) | Jun 27, 2023 |
| UNOWHY        | Y13G002S4EI                 | [dae5fc72df](https://linux-hardware.org/?probe=dae5fc72df) | Jun 27, 2023 |
| UNOWHY        | Y13G002S4EI                 | [c91c09307d](https://linux-hardware.org/?probe=c91c09307d) | Jun 27, 2023 |
| Dell          | XPS 15 9500                 | [8ea6d92813](https://linux-hardware.org/?probe=8ea6d92813) | Jun 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | [fc7f2b378b](https://linux-hardware.org/?probe=fc7f2b378b) | Jun 27, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [3928ad0893](https://linux-hardware.org/?probe=3928ad0893) | Jun 27, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ec69000909](https://linux-hardware.org/?probe=ec69000909) | Jun 27, 2023 |
| Acer          | Nitro AN515-45              | [0bfb7dc30a](https://linux-hardware.org/?probe=0bfb7dc30a) | Jun 27, 2023 |
| Apple         | MacBookPro8,2               | [3e5baaaa01](https://linux-hardware.org/?probe=3e5baaaa01) | Jun 27, 2023 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [0defa5c92d](https://linux-hardware.org/?probe=0defa5c92d) | Jun 27, 2023 |
| Apple         | MacBook4,1                  | [fe27e643ac](https://linux-hardware.org/?probe=fe27e643ac) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [cde6a94b92](https://linux-hardware.org/?probe=cde6a94b92) | Jun 26, 2023 |
| HP            | Pavilion dv6                | [fe7974bbc9](https://linux-hardware.org/?probe=fe7974bbc9) | Jun 26, 2023 |
| HP            | Pavilion dv6                | [3051c4ac4e](https://linux-hardware.org/?probe=3051c4ac4e) | Jun 26, 2023 |
| MSI           | Prestige 14H B12UCX         | [abf425c8d7](https://linux-hardware.org/?probe=abf425c8d7) | Jun 26, 2023 |
| MSI           | Crosshair 15 A11UEK         | [8ce4fd5481](https://linux-hardware.org/?probe=8ce4fd5481) | Jun 26, 2023 |
| Lenovo        | ThinkPad P51 20HJS16Q0J     | [d328a1e8f3](https://linux-hardware.org/?probe=d328a1e8f3) | Jun 26, 2023 |
| MSI           | Crosshair 15 A11UEK         | [bdb7d2c45e](https://linux-hardware.org/?probe=bdb7d2c45e) | Jun 26, 2023 |
| ASUSTek       | GL752VW                     | [1256645a67](https://linux-hardware.org/?probe=1256645a67) | Jun 26, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [eeb516967a](https://linux-hardware.org/?probe=eeb516967a) | Jun 26, 2023 |
| HP            | EliteBook 8540w             | [2f2e5281ef](https://linux-hardware.org/?probe=2f2e5281ef) | Jun 26, 2023 |
| Acer          | Aspire A715-51G             | [08ba4bf92b](https://linux-hardware.org/?probe=08ba4bf92b) | Jun 26, 2023 |
| Acer          | Aspire A715-51G             | [3dc15705c8](https://linux-hardware.org/?probe=3dc15705c8) | Jun 26, 2023 |
| HP            | EliteBook 8540w             | [ca160c2c1c](https://linux-hardware.org/?probe=ca160c2c1c) | Jun 26, 2023 |
| Dell          | Latitude E5470              | [c463ab7b16](https://linux-hardware.org/?probe=c463ab7b16) | Jun 26, 2023 |
| ASUSTek       | F5SR                        | [059a0b2611](https://linux-hardware.org/?probe=059a0b2611) | Jun 26, 2023 |
| HP            | EliteBook 2540p             | [f5e04da161](https://linux-hardware.org/?probe=f5e04da161) | Jun 26, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA    | [8a764f6629](https://linux-hardware.org/?probe=8a764f6629) | Jun 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [44f08646c1](https://linux-hardware.org/?probe=44f08646c1) | Jun 26, 2023 |
| Dell          | Precision 7670              | [4138a39697](https://linux-hardware.org/?probe=4138a39697) | Jun 26, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [8db0a77e13](https://linux-hardware.org/?probe=8db0a77e13) | Jun 26, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R70... | [047bdacac5](https://linux-hardware.org/?probe=047bdacac5) | Jun 25, 2023 |
| Star Labs     | LabTop                      | [a413031ef8](https://linux-hardware.org/?probe=a413031ef8) | Jun 25, 2023 |
| Acer          | Aspire E5-575G              | [2f5357533f](https://linux-hardware.org/?probe=2f5357533f) | Jun 25, 2023 |
| Dell          | Latitude 7420               | [d5cb3d4bfa](https://linux-hardware.org/?probe=d5cb3d4bfa) | Jun 25, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [3a045583a7](https://linux-hardware.org/?probe=3a045583a7) | Jun 25, 2023 |
| Dell          | Precision 5540              | [7d6c1fe39d](https://linux-hardware.org/?probe=7d6c1fe39d) | Jun 25, 2023 |
| HP            | Laptop 15-db0xxx            | [79979ceac7](https://linux-hardware.org/?probe=79979ceac7) | Jun 25, 2023 |
| Sony          | VGN-AR74DB                  | [c51cc05c0a](https://linux-hardware.org/?probe=c51cc05c0a) | Jun 25, 2023 |
| Dell          | Latitude E5470              | [e8f8b7e986](https://linux-hardware.org/?probe=e8f8b7e986) | Jun 25, 2023 |
| Dell          | Latitude E5470              | [e218b300b7](https://linux-hardware.org/?probe=e218b300b7) | Jun 25, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [0ec7fedf29](https://linux-hardware.org/?probe=0ec7fedf29) | Jun 24, 2023 |
| HP            | EliteBook 840 G1            | [37239831de](https://linux-hardware.org/?probe=37239831de) | Jun 24, 2023 |
| Acer          | Aspire A315-22              | [5e2e395efd](https://linux-hardware.org/?probe=5e2e395efd) | Jun 24, 2023 |
| Dell          | Latitude E6500              | [2b1720ad90](https://linux-hardware.org/?probe=2b1720ad90) | Jun 24, 2023 |
| Dell          | Inspiron 3576               | [c756e98d81](https://linux-hardware.org/?probe=c756e98d81) | Jun 24, 2023 |
| HP            | Pavilion dv7                | [ab7310809d](https://linux-hardware.org/?probe=ab7310809d) | Jun 24, 2023 |
| Toshiba       | Satellite L655              | [6ed0182e96](https://linux-hardware.org/?probe=6ed0182e96) | Jun 24, 2023 |
| Dell          | Inspiron 3576               | [874b84ce94](https://linux-hardware.org/?probe=874b84ce94) | Jun 24, 2023 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [09419812ab](https://linux-hardware.org/?probe=09419812ab) | Jun 24, 2023 |
| HP            | 15 Notebook PC              | [440f4bbf29](https://linux-hardware.org/?probe=440f4bbf29) | Jun 24, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | [0834c21488](https://linux-hardware.org/?probe=0834c21488) | Jun 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 16IAH7 ... | [ef5eb06f90](https://linux-hardware.org/?probe=ef5eb06f90) | Jun 24, 2023 |
| Medion        | P6624                       | [49bd227ded](https://linux-hardware.org/?probe=49bd227ded) | Jun 23, 2023 |
| eMachines     | eMG520                      | [2a33e0b985](https://linux-hardware.org/?probe=2a33e0b985) | Jun 23, 2023 |
| Packard Be... | EN Butterfly m              | [70bae75df2](https://linux-hardware.org/?probe=70bae75df2) | Jun 23, 2023 |
| Dell          | XPS 9320                    | [2dcfa6718b](https://linux-hardware.org/?probe=2dcfa6718b) | Jun 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4429a0f659](https://linux-hardware.org/?probe=4429a0f659) | Jun 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | [bb559685e3](https://linux-hardware.org/?probe=bb559685e3) | Jun 23, 2023 |
| Notebook      | W54_55SU1,SUW               | [622462c1d1](https://linux-hardware.org/?probe=622462c1d1) | Jun 23, 2023 |
| Notebook      | W54_55SU1,SUW               | [117e92a397](https://linux-hardware.org/?probe=117e92a397) | Jun 23, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [c75670186a](https://linux-hardware.org/?probe=c75670186a) | Jun 23, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [32f2a1756a](https://linux-hardware.org/?probe=32f2a1756a) | Jun 23, 2023 |
| HP            | EliteBook 2540p             | [b33e52fa0a](https://linux-hardware.org/?probe=b33e52fa0a) | Jun 22, 2023 |
| Acer          | Aspire E5-575G              | [5c76172491](https://linux-hardware.org/?probe=5c76172491) | Jun 22, 2023 |
| Dell          | XPS 17 9710                 | [892620ac83](https://linux-hardware.org/?probe=892620ac83) | Jun 22, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [4b866ca19f](https://linux-hardware.org/?probe=4b866ca19f) | Jun 22, 2023 |
| ASUSTek       | K55VD                       | [223967ea1d](https://linux-hardware.org/?probe=223967ea1d) | Jun 22, 2023 |
| Acer          | Aspire A515-57              | [0ee3dcbbb5](https://linux-hardware.org/?probe=0ee3dcbbb5) | Jun 22, 2023 |
| HP            | Pavilion dv6                | [fa9045c36f](https://linux-hardware.org/?probe=fa9045c36f) | Jun 22, 2023 |
| Timi          | RedmiBook 14-APCS           | [3dadb16806](https://linux-hardware.org/?probe=3dadb16806) | Jun 22, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | [110c366456](https://linux-hardware.org/?probe=110c366456) | Jun 22, 2023 |
| HP            | Dragonfly 13.5 inch G4 N... | [22c2768f76](https://linux-hardware.org/?probe=22c2768f76) | Jun 22, 2023 |
| Medion        | Erazer P6661 MD60303        | [22fb03fe41](https://linux-hardware.org/?probe=22fb03fe41) | Jun 22, 2023 |
| Toshiba       | PORTEGE Z930                | [0cad0d9955](https://linux-hardware.org/?probe=0cad0d9955) | Jun 22, 2023 |
| Lenovo        | ThinkPad L380 20M5000UGE    | [06db720b62](https://linux-hardware.org/?probe=06db720b62) | Jun 22, 2023 |
| HP            | Pavilion dv5                | [4a0db4b1ba](https://linux-hardware.org/?probe=4a0db4b1ba) | Jun 22, 2023 |
| HP            | Pavilion dv5                | [902335f2cb](https://linux-hardware.org/?probe=902335f2cb) | Jun 22, 2023 |
| Samsung       | 550XDA                      | [f20386ccdd](https://linux-hardware.org/?probe=f20386ccdd) | Jun 22, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [42cb7025f1](https://linux-hardware.org/?probe=42cb7025f1) | Jun 22, 2023 |
| Dell          | Inspiron 15 3511            | [0ef8557b4d](https://linux-hardware.org/?probe=0ef8557b4d) | Jun 22, 2023 |
| Dell          | Latitude 3520               | [ada304545e](https://linux-hardware.org/?probe=ada304545e) | Jun 22, 2023 |
| System76      | Gazelle                     | [858e408027](https://linux-hardware.org/?probe=858e408027) | Jun 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [079f84c10d](https://linux-hardware.org/?probe=079f84c10d) | Jun 21, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [017f0476b0](https://linux-hardware.org/?probe=017f0476b0) | Jun 21, 2023 |
| Acer          | Aspire E1-572G              | [c4af4bf38c](https://linux-hardware.org/?probe=c4af4bf38c) | Jun 21, 2023 |
| Lenovo        | ThinkPad L440 20ASS19B03    | [3acd887212](https://linux-hardware.org/?probe=3acd887212) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [7de42486fb](https://linux-hardware.org/?probe=7de42486fb) | Jun 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [b61cc560f8](https://linux-hardware.org/?probe=b61cc560f8) | Jun 21, 2023 |
| Dell          | Latitude 5430               | [458a2111da](https://linux-hardware.org/?probe=458a2111da) | Jun 21, 2023 |
| Dell          | XPS 9320                    | [6a60a308d1](https://linux-hardware.org/?probe=6a60a308d1) | Jun 21, 2023 |
| MSI           | GE75 Raider 10SF            | [b3ce37b2cb](https://linux-hardware.org/?probe=b3ce37b2cb) | Jun 21, 2023 |
| ASUSTek       | GL552VW                     | [592b7aa556](https://linux-hardware.org/?probe=592b7aa556) | Jun 21, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | [4af402b7c9](https://linux-hardware.org/?probe=4af402b7c9) | Jun 21, 2023 |
| Apple         | MacBookPro6,2               | [3beb323b62](https://linux-hardware.org/?probe=3beb323b62) | Jun 21, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [caaf6ce403](https://linux-hardware.org/?probe=caaf6ce403) | Jun 21, 2023 |
| ASUSTek       | K55VD                       | [49f6cc6986](https://linux-hardware.org/?probe=49f6cc6986) | Jun 20, 2023 |
| MSI           | Katana GF76 12UD            | [1897f5f0cb](https://linux-hardware.org/?probe=1897f5f0cb) | Jun 20, 2023 |
| Dell          | Latitude E6410              | [b34442d8c3](https://linux-hardware.org/?probe=b34442d8c3) | Jun 20, 2023 |
| Apple         | MacBookPro11,1              | [4850296b9d](https://linux-hardware.org/?probe=4850296b9d) | Jun 20, 2023 |
| Acer          | Predator PHN16-71           | [16f2ca887d](https://linux-hardware.org/?probe=16f2ca887d) | Jun 20, 2023 |
| Apple         | MacBookPro13,1              | [95a82b40ce](https://linux-hardware.org/?probe=95a82b40ce) | Jun 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [7c906bbd1c](https://linux-hardware.org/?probe=7c906bbd1c) | Jun 20, 2023 |
| Dell          | Precision 5560              | [ee53248c8c](https://linux-hardware.org/?probe=ee53248c8c) | Jun 20, 2023 |
| Google        | Blooguard                   | [f1d90deb53](https://linux-hardware.org/?probe=f1d90deb53) | Jun 20, 2023 |
| Lenovo        | ThinkPad T460s 20F9005BU... | [59a527c934](https://linux-hardware.org/?probe=59a527c934) | Jun 20, 2023 |
| HP            | OMEN by Laptop 15-dh0xxx    | [6e2f7d8295](https://linux-hardware.org/?probe=6e2f7d8295) | Jun 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [67c63af138](https://linux-hardware.org/?probe=67c63af138) | Jun 19, 2023 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [f52b994470](https://linux-hardware.org/?probe=f52b994470) | Jun 19, 2023 |
| HP            | Pavilion dv6                | [09d49049bf](https://linux-hardware.org/?probe=09d49049bf) | Jun 19, 2023 |
| Samsung       | RC420/RC520/RC720           | [406b650f19](https://linux-hardware.org/?probe=406b650f19) | Jun 19, 2023 |
| Lenovo        | ThinkPad L440 20ASS19B03    | [a881db7c2b](https://linux-hardware.org/?probe=a881db7c2b) | Jun 19, 2023 |
| Dell          | Inspiron 3185               | [f53e8d1094](https://linux-hardware.org/?probe=f53e8d1094) | Jun 19, 2023 |
| ASUSTek       | X756UVK                     | [8ac304b302](https://linux-hardware.org/?probe=8ac304b302) | Jun 19, 2023 |
| ASUSTek       | X756UVK                     | [beb200bb6b](https://linux-hardware.org/?probe=beb200bb6b) | Jun 19, 2023 |
| Acer          | Aspire A515-57G             | [b783c040ee](https://linux-hardware.org/?probe=b783c040ee) | Jun 19, 2023 |
| Dell          | Inspiron 7347               | [026935ac8f](https://linux-hardware.org/?probe=026935ac8f) | Jun 19, 2023 |
| HP            | Pavilion Laptop 13-an0xx... | [0f68ace67c](https://linux-hardware.org/?probe=0f68ace67c) | Jun 19, 2023 |
| Dell          | G7 7588                     | [2cdb34b778](https://linux-hardware.org/?probe=2cdb34b778) | Jun 19, 2023 |
| Timi          | A34R                        | [da4d787d75](https://linux-hardware.org/?probe=da4d787d75) | Jun 19, 2023 |
| HP            | Laptop 15-db0xxx            | [c67d08fe43](https://linux-hardware.org/?probe=c67d08fe43) | Jun 19, 2023 |
| Acer          | Aspire ES1-420              | [76aab864d4](https://linux-hardware.org/?probe=76aab864d4) | Jun 19, 2023 |
| HP            | Laptop 14s-fq0xxx           | [6ff28ccac1](https://linux-hardware.org/?probe=6ff28ccac1) | Jun 19, 2023 |
| Acer          | Aspire 7739                 | [eda7fb180a](https://linux-hardware.org/?probe=eda7fb180a) | Jun 19, 2023 |
| Dell          | Latitude E6540              | [3721b0046f](https://linux-hardware.org/?probe=3721b0046f) | Jun 19, 2023 |
| Dell          | Inspiron 7352               | [dd9c020f92](https://linux-hardware.org/?probe=dd9c020f92) | Jun 19, 2023 |
| HP            | ProBook 440 G4              | [4b20fef62f](https://linux-hardware.org/?probe=4b20fef62f) | Jun 19, 2023 |
| ASUSTek       | X541NA                      | [2fa7c42c59](https://linux-hardware.org/?probe=2fa7c42c59) | Jun 18, 2023 |
| Acer          | Aspire 7739                 | [34854e20dd](https://linux-hardware.org/?probe=34854e20dd) | Jun 18, 2023 |
| Dell          | Latitude 5430               | [7c591ed7d8](https://linux-hardware.org/?probe=7c591ed7d8) | Jun 18, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [d237a2bfe6](https://linux-hardware.org/?probe=d237a2bfe6) | Jun 18, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [4777b096a3](https://linux-hardware.org/?probe=4777b096a3) | Jun 18, 2023 |
| HP            | Pavilion Notebook           | [5d417b3d76](https://linux-hardware.org/?probe=5d417b3d76) | Jun 18, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [e4a3b14c4c](https://linux-hardware.org/?probe=e4a3b14c4c) | Jun 18, 2023 |
| Acer          | Aspire A515-57              | [e7f63885d1](https://linux-hardware.org/?probe=e7f63885d1) | Jun 18, 2023 |
| Dell          | Latitude 5531               | [bf22616526](https://linux-hardware.org/?probe=bf22616526) | Jun 18, 2023 |
| Hampoo        | Cherry Trail CR Hampoo_r... | [68f03108e5](https://linux-hardware.org/?probe=68f03108e5) | Jun 18, 2023 |
| Dell          | Vostro 1015                 | [e195f838c3](https://linux-hardware.org/?probe=e195f838c3) | Jun 18, 2023 |
| Toshiba       | Satellite Pro L500          | [14765b8284](https://linux-hardware.org/?probe=14765b8284) | Jun 18, 2023 |
| Dell          | Latitude 3189               | [c7f2d1b100](https://linux-hardware.org/?probe=c7f2d1b100) | Jun 17, 2023 |
| HP            | EliteBook 840 G3            | [75bb32cc26](https://linux-hardware.org/?probe=75bb32cc26) | Jun 17, 2023 |
| Dell          | Latitude 5430               | [1797038bf6](https://linux-hardware.org/?probe=1797038bf6) | Jun 17, 2023 |
| Dell          | Latitude 5420               | [f7c9224ef1](https://linux-hardware.org/?probe=f7c9224ef1) | Jun 17, 2023 |
| Dell          | Latitude 5420               | [f553a4e5e7](https://linux-hardware.org/?probe=f553a4e5e7) | Jun 17, 2023 |
| HP            | 250 G4                      | [f25c49812b](https://linux-hardware.org/?probe=f25c49812b) | Jun 17, 2023 |
| Unknown       | Unknown                     | [c3aaea0987](https://linux-hardware.org/?probe=c3aaea0987) | Jun 17, 2023 |
| HP            | EliteBook 2540p             | [a62dc4b2ed](https://linux-hardware.org/?probe=a62dc4b2ed) | Jun 17, 2023 |
| Acer          | Aspire A515-46              | [dc64dc75dc](https://linux-hardware.org/?probe=dc64dc75dc) | Jun 17, 2023 |
| Acer          | Aspire A515-46              | [42ab827d04](https://linux-hardware.org/?probe=42ab827d04) | Jun 17, 2023 |
| Apple         | MacBookPro5,5               | [22e0a1e0cc](https://linux-hardware.org/?probe=22e0a1e0cc) | Jun 17, 2023 |
| Dell          | Inspiron 15-7568            | [4d0efefd7c](https://linux-hardware.org/?probe=4d0efefd7c) | Jun 17, 2023 |
| BANGHO        | MAX L5                      | [47f4fd7822](https://linux-hardware.org/?probe=47f4fd7822) | Jun 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [e2357f72af](https://linux-hardware.org/?probe=e2357f72af) | Jun 17, 2023 |
| HP            | Laptop 15-fc0xxx            | [af90ec4131](https://linux-hardware.org/?probe=af90ec4131) | Jun 16, 2023 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [2c6d49788f](https://linux-hardware.org/?probe=2c6d49788f) | Jun 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [ea2e8604af](https://linux-hardware.org/?probe=ea2e8604af) | Jun 16, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [a210e832a8](https://linux-hardware.org/?probe=a210e832a8) | Jun 16, 2023 |
| HP            | ZBook Fury 15.6 inch G8 ... | [eb6365c303](https://linux-hardware.org/?probe=eb6365c303) | Jun 16, 2023 |
| Toshiba       | Satellite C55D-B            | [341da36529](https://linux-hardware.org/?probe=341da36529) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | [1869c3f4dc](https://linux-hardware.org/?probe=1869c3f4dc) | Jun 16, 2023 |
| Chuwi         | LarkBook X                  | [2aed95c237](https://linux-hardware.org/?probe=2aed95c237) | Jun 16, 2023 |
| BANGHO        | MAX L5                      | [5027ce5059](https://linux-hardware.org/?probe=5027ce5059) | Jun 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0d90e728fe](https://linux-hardware.org/?probe=0d90e728fe) | Jun 16, 2023 |
| Dell          | Inspiron 5548               | [547ffd8db7](https://linux-hardware.org/?probe=547ffd8db7) | Jun 16, 2023 |
| Acer          | Aspire ES1-522              | [25f52202b2](https://linux-hardware.org/?probe=25f52202b2) | Jun 16, 2023 |
| HUAWEI        | BOM-WXX9                    | [130605379e](https://linux-hardware.org/?probe=130605379e) | Jun 15, 2023 |
| Dell          | Precision 3551              | [f65ccf6171](https://linux-hardware.org/?probe=f65ccf6171) | Jun 15, 2023 |
| Dell          | Precision 3551              | [bc3299a9d7](https://linux-hardware.org/?probe=bc3299a9d7) | Jun 15, 2023 |
| Beelink       | Gemini X                    | [f95615a561](https://linux-hardware.org/?probe=f95615a561) | Jun 15, 2023 |
| Beelink       | Gemini X                    | [3f69d07a3e](https://linux-hardware.org/?probe=3f69d07a3e) | Jun 15, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | [41d5c8b913](https://linux-hardware.org/?probe=41d5c8b913) | Jun 15, 2023 |
| Lenovo        | ThinkPad T490 20N20032US    | [3df7663e0d](https://linux-hardware.org/?probe=3df7663e0d) | Jun 15, 2023 |
| Apple         | MacBookPro8,2               | [d254709437](https://linux-hardware.org/?probe=d254709437) | Jun 15, 2023 |
| ASUSTek       | K70AC                       | [b9dc7d0b00](https://linux-hardware.org/?probe=b9dc7d0b00) | Jun 15, 2023 |
| Dell          | Latitude E7450              | [05ebaf45ae](https://linux-hardware.org/?probe=05ebaf45ae) | Jun 15, 2023 |
| Dell          | Precision 5570              | [76bbf6a26f](https://linux-hardware.org/?probe=76bbf6a26f) | Jun 15, 2023 |
| HUAWEI        | BOHB-WAX9                   | [1858e12df4](https://linux-hardware.org/?probe=1858e12df4) | Jun 15, 2023 |
| HP            | Laptop 15s-fq0xxx           | [bbc15bef9c](https://linux-hardware.org/?probe=bbc15bef9c) | Jun 15, 2023 |
| Dell          | Inspiron 5505               | [7747deeb57](https://linux-hardware.org/?probe=7747deeb57) | Jun 15, 2023 |
| Toshiba       | Satellite X200              | [d57a63387d](https://linux-hardware.org/?probe=d57a63387d) | Jun 15, 2023 |
| Acer          | Aspire V5-472               | [58dc632831](https://linux-hardware.org/?probe=58dc632831) | Jun 15, 2023 |
| Razer         | Blade 16 - RZ09-0483        | [a8cc966bac](https://linux-hardware.org/?probe=a8cc966bac) | Jun 15, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [f92cfc0ad7](https://linux-hardware.org/?probe=f92cfc0ad7) | Jun 15, 2023 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | [1f5222a92f](https://linux-hardware.org/?probe=1f5222a92f) | Jun 15, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [5b85dc34c6](https://linux-hardware.org/?probe=5b85dc34c6) | Jun 15, 2023 |
| Apple         | MacBookPro7,1               | [ae4444566b](https://linux-hardware.org/?probe=ae4444566b) | Jun 14, 2023 |
| HP            | ENVY 17                     | [269ca0c6e9](https://linux-hardware.org/?probe=269ca0c6e9) | Jun 14, 2023 |
| HUAWEI        | MACH-WX9                    | [b6998602c8](https://linux-hardware.org/?probe=b6998602c8) | Jun 14, 2023 |
| HP            | ProBook 430 G4              | [fe39c9b2ce](https://linux-hardware.org/?probe=fe39c9b2ce) | Jun 14, 2023 |
| HP            | ProBook 430 G4              | [2b4d088695](https://linux-hardware.org/?probe=2b4d088695) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [7d329c0bee](https://linux-hardware.org/?probe=7d329c0bee) | Jun 14, 2023 |
| HUAWEI        | BOHB-WAX9                   | [40ec446343](https://linux-hardware.org/?probe=40ec446343) | Jun 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [acf5c5a440](https://linux-hardware.org/?probe=acf5c5a440) | Jun 14, 2023 |
| HP            | ZBook Power 15.6 inch G9... | [467be092e4](https://linux-hardware.org/?probe=467be092e4) | Jun 14, 2023 |
| Apple         | MacBookAir4,1               | [ac4f715f77](https://linux-hardware.org/?probe=ac4f715f77) | Jun 14, 2023 |
| Acer          | Aspire ES1-420              | [5c3a2078ca](https://linux-hardware.org/?probe=5c3a2078ca) | Jun 14, 2023 |
| Toshiba       | Satellite L650              | [d92c0dea02](https://linux-hardware.org/?probe=d92c0dea02) | Jun 14, 2023 |
| Dell          | XPS 15 9560                 | [f3b25c0959](https://linux-hardware.org/?probe=f3b25c0959) | Jun 14, 2023 |
| Fujitsu       | LIFEBOOK U747               | [aea3f705ed](https://linux-hardware.org/?probe=aea3f705ed) | Jun 13, 2023 |
| Dell          | XPS 9320                    | [a6567a0c58](https://linux-hardware.org/?probe=a6567a0c58) | Jun 13, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [6dadff138b](https://linux-hardware.org/?probe=6dadff138b) | Jun 13, 2023 |
| Medion        | E7424 MD60150               | [c8d6acdb6f](https://linux-hardware.org/?probe=c8d6acdb6f) | Jun 13, 2023 |
| Medion        | E7424 MD60150               | [9f4ec54afd](https://linux-hardware.org/?probe=9f4ec54afd) | Jun 13, 2023 |
| ASUSTek       | ZenBook UX425EA_BX425EA     | [a0b003c3b1](https://linux-hardware.org/?probe=a0b003c3b1) | Jun 13, 2023 |
| Dell          | Latitude E5540              | [029d51e57f](https://linux-hardware.org/?probe=029d51e57f) | Jun 13, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [5e636c4693](https://linux-hardware.org/?probe=5e636c4693) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [f47c4b27fe](https://linux-hardware.org/?probe=f47c4b27fe) | Jun 13, 2023 |
| Unknown       | Unknown                     | [8c81783d26](https://linux-hardware.org/?probe=8c81783d26) | Jun 13, 2023 |
| Apple         | MacBookPro7,1               | [c1f5bf2148](https://linux-hardware.org/?probe=c1f5bf2148) | Jun 13, 2023 |
| Gateway       | NE572                       | [771f8d0d63](https://linux-hardware.org/?probe=771f8d0d63) | Jun 13, 2023 |
| HUAWEI        | HKF-WXX                     | [ad88913ce4](https://linux-hardware.org/?probe=ad88913ce4) | Jun 13, 2023 |
| Lenovo        | Legion Y530-15ICH-1060 8... | [1c33fe3f61](https://linux-hardware.org/?probe=1c33fe3f61) | Jun 12, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [40d06bae85](https://linux-hardware.org/?probe=40d06bae85) | Jun 12, 2023 |
| Dell          | XPS 15 9560                 | [ca84981180](https://linux-hardware.org/?probe=ca84981180) | Jun 12, 2023 |
| Acer          | Aspire F5-573G              | [c85f08223b](https://linux-hardware.org/?probe=c85f08223b) | Jun 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [39d97bb85b](https://linux-hardware.org/?probe=39d97bb85b) | Jun 12, 2023 |
| Lenovo        | ThinkPad X250 20CLS45J00    | [64bbeab44d](https://linux-hardware.org/?probe=64bbeab44d) | Jun 12, 2023 |
| Lenovo        | ThinkPad X250 20CLS45J00    | [a08326363f](https://linux-hardware.org/?probe=a08326363f) | Jun 12, 2023 |
| Lenovo        | ThinkPad T490 20RY0002US    | [2a6a7f9099](https://linux-hardware.org/?probe=2a6a7f9099) | Jun 12, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [aca09b2a54](https://linux-hardware.org/?probe=aca09b2a54) | Jun 12, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [f3dae81611](https://linux-hardware.org/?probe=f3dae81611) | Jun 12, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [f19d062310](https://linux-hardware.org/?probe=f19d062310) | Jun 12, 2023 |
| HP            | Pavilion Notebook           | [4c5907abd5](https://linux-hardware.org/?probe=4c5907abd5) | Jun 12, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [d4da1625e2](https://linux-hardware.org/?probe=d4da1625e2) | Jun 12, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [88fc978934](https://linux-hardware.org/?probe=88fc978934) | Jun 12, 2023 |
| Dell          | Precision 7560              | [fc461aad87](https://linux-hardware.org/?probe=fc461aad87) | Jun 12, 2023 |
| HP            | Laptop 15-da1xxx            | [5bc14dc937](https://linux-hardware.org/?probe=5bc14dc937) | Jun 12, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [0b737be0c6](https://linux-hardware.org/?probe=0b737be0c6) | Jun 12, 2023 |
| Notebook      | PCX0DX                      | [9030773fa9](https://linux-hardware.org/?probe=9030773fa9) | Jun 12, 2023 |
| Notebook      | PCX0DX                      | [689901fd34](https://linux-hardware.org/?probe=689901fd34) | Jun 12, 2023 |
| Fujitsu       | T900                        | [4716750f3f](https://linux-hardware.org/?probe=4716750f3f) | Jun 12, 2023 |
| Dell          | Latitude 7350               | [1f5f117feb](https://linux-hardware.org/?probe=1f5f117feb) | Jun 12, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | [0b42de0b42](https://linux-hardware.org/?probe=0b42de0b42) | Jun 12, 2023 |
| Dell          | Latitude 7350               | [bad2e8b0b2](https://linux-hardware.org/?probe=bad2e8b0b2) | Jun 12, 2023 |
| HP            | Pavilion 17                 | [e6279cb0df](https://linux-hardware.org/?probe=e6279cb0df) | Jun 12, 2023 |
| Apple         | MacBookPro5,5               | [cba5fb51f8](https://linux-hardware.org/?probe=cba5fb51f8) | Jun 11, 2023 |
| Dell          | Latitude 5520               | [f0fc9a8003](https://linux-hardware.org/?probe=f0fc9a8003) | Jun 11, 2023 |
| Notebook      | NJx0MU                      | [d2cb2b5360](https://linux-hardware.org/?probe=d2cb2b5360) | Jun 11, 2023 |
| Dell          | Latitude E6400              | [c1f065966d](https://linux-hardware.org/?probe=c1f065966d) | Jun 11, 2023 |
| Dell          | XPS 13 9310                 | [740fb14b2f](https://linux-hardware.org/?probe=740fb14b2f) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [8a3bd0a576](https://linux-hardware.org/?probe=8a3bd0a576) | Jun 11, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [a67c1e25b2](https://linux-hardware.org/?probe=a67c1e25b2) | Jun 11, 2023 |
| HP            | ZBook 15 G6                 | [180abd0b90](https://linux-hardware.org/?probe=180abd0b90) | Jun 11, 2023 |
| Acer          | Aspire E5-572G              | [6f58cbafdd](https://linux-hardware.org/?probe=6f58cbafdd) | Jun 10, 2023 |
| Lenovo        | ThinkPad T480 20L50010US    | [aa44c2c8b9](https://linux-hardware.org/?probe=aa44c2c8b9) | Jun 10, 2023 |
| Acer          | Aspire E5-574G              | [8ca78da386](https://linux-hardware.org/?probe=8ca78da386) | Jun 10, 2023 |
| Beelink       | Gemini X                    | [adcb5e774d](https://linux-hardware.org/?probe=adcb5e774d) | Jun 10, 2023 |
| HUAWEI        | HVY-WXX9                    | [d6be89e452](https://linux-hardware.org/?probe=d6be89e452) | Jun 10, 2023 |
| Lenovo        | ThinkPad T480 20L50010US    | [398d708c85](https://linux-hardware.org/?probe=398d708c85) | Jun 10, 2023 |
| HP            | EliteBook 1040 G4           | [98aa06475b](https://linux-hardware.org/?probe=98aa06475b) | Jun 10, 2023 |
| Lenovo        | ThinkPad X240 20AMS5XY00    | [3b98c592e0](https://linux-hardware.org/?probe=3b98c592e0) | Jun 10, 2023 |
| HP            | Laptop 17-by3xxx            | [421ff52b0b](https://linux-hardware.org/?probe=421ff52b0b) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | [6adee93e47](https://linux-hardware.org/?probe=6adee93e47) | Jun 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7c9662b5eb](https://linux-hardware.org/?probe=7c9662b5eb) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | [86f646e00f](https://linux-hardware.org/?probe=86f646e00f) | Jun 10, 2023 |
| Dell          | Vostro 3560                 | [1bb9178df2](https://linux-hardware.org/?probe=1bb9178df2) | Jun 10, 2023 |
| Exo           | Smart Serie LT              | [bbecad1cea](https://linux-hardware.org/?probe=bbecad1cea) | Jun 10, 2023 |
| Apple         | MacBookPro9,2               | [f502f89e9d](https://linux-hardware.org/?probe=f502f89e9d) | Jun 10, 2023 |
| HP            | ProBook 6360b               | [cdef37cb2d](https://linux-hardware.org/?probe=cdef37cb2d) | Jun 09, 2023 |
| Dell          | Vostro 3558                 | [15185698e7](https://linux-hardware.org/?probe=15185698e7) | Jun 09, 2023 |
| HUAWEI        | MACHC-WAX9                  | [6f26f51ef6](https://linux-hardware.org/?probe=6f26f51ef6) | Jun 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [9cb24f9445](https://linux-hardware.org/?probe=9cb24f9445) | Jun 09, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [fb9e2f9fc8](https://linux-hardware.org/?probe=fb9e2f9fc8) | Jun 09, 2023 |
| HP            | ProBook 4510s               | [43a29ea83e](https://linux-hardware.org/?probe=43a29ea83e) | Jun 09, 2023 |
| HP            | Laptop 17-bs0xx             | [c93d52343c](https://linux-hardware.org/?probe=c93d52343c) | Jun 09, 2023 |
| Google        | Akali 360                   | [1f7d5f8bc5](https://linux-hardware.org/?probe=1f7d5f8bc5) | Jun 09, 2023 |
| Dell          | Latitude E7470              | [c5457da74f](https://linux-hardware.org/?probe=c5457da74f) | Jun 09, 2023 |
| Dell          | Inspiron 3583               | [adcb3b193a](https://linux-hardware.org/?probe=adcb3b193a) | Jun 09, 2023 |
| HUAWEI        | BOHB-WAX9                   | [aa0b439e8d](https://linux-hardware.org/?probe=aa0b439e8d) | Jun 09, 2023 |
| Lenovo        | ThinkPad T460s 20FAS11X0... | [23568da401](https://linux-hardware.org/?probe=23568da401) | Jun 09, 2023 |
| Apple         | MacBookPro5,5               | [09344fa63e](https://linux-hardware.org/?probe=09344fa63e) | Jun 09, 2023 |
| HP            | ENVY 15                     | [3776ac93b3](https://linux-hardware.org/?probe=3776ac93b3) | Jun 08, 2023 |
| Samsung       | 910S3L                      | [f8e59b4c0f](https://linux-hardware.org/?probe=f8e59b4c0f) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [c98ac6e82c](https://linux-hardware.org/?probe=c98ac6e82c) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | [d6a8e02362](https://linux-hardware.org/?probe=d6a8e02362) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | [fdb80f6e89](https://linux-hardware.org/?probe=fdb80f6e89) | Jun 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3444C... | [4e5e1d4052](https://linux-hardware.org/?probe=4e5e1d4052) | Jun 08, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [7879db73f8](https://linux-hardware.org/?probe=7879db73f8) | Jun 08, 2023 |
| Acer          | Aspire ES1-711              | [79bb8d8e39](https://linux-hardware.org/?probe=79bb8d8e39) | Jun 08, 2023 |
| HONOR         | NBR-WAX9                    | [697f2b18e8](https://linux-hardware.org/?probe=697f2b18e8) | Jun 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [292625f2da](https://linux-hardware.org/?probe=292625f2da) | Jun 08, 2023 |
| HP            | 2000                        | [4ae1384345](https://linux-hardware.org/?probe=4ae1384345) | Jun 07, 2023 |
| Beelink       | Gemini X                    | [49aca69972](https://linux-hardware.org/?probe=49aca69972) | Jun 07, 2023 |
| Dell          | Latitude 3350               | [ef85473c50](https://linux-hardware.org/?probe=ef85473c50) | Jun 07, 2023 |
| Dell          | XPS 9320                    | [ff5fc17acc](https://linux-hardware.org/?probe=ff5fc17acc) | Jun 07, 2023 |
| Dell          | XPS 13 9370                 | [f70195a177](https://linux-hardware.org/?probe=f70195a177) | Jun 07, 2023 |
| Onda TLC      | ONDA Oliver                 | [bbfcf4a3be](https://linux-hardware.org/?probe=bbfcf4a3be) | Jun 07, 2023 |
| HP            | EliteBook 2560p             | [1b491bcfeb](https://linux-hardware.org/?probe=1b491bcfeb) | Jun 07, 2023 |
| HP            | EliteBook 2560p             | [f1060e2b5d](https://linux-hardware.org/?probe=f1060e2b5d) | Jun 07, 2023 |
| Acer          | Nitro AN515-55              | [99b42755e8](https://linux-hardware.org/?probe=99b42755e8) | Jun 07, 2023 |
| Dell          | Inspiron 5547               | [7775c4c871](https://linux-hardware.org/?probe=7775c4c871) | Jun 07, 2023 |
| Dell          | Inspiron 5547               | [3a43778152](https://linux-hardware.org/?probe=3a43778152) | Jun 07, 2023 |
| Dell          | Latitude E7250              | [a80182e728](https://linux-hardware.org/?probe=a80182e728) | Jun 06, 2023 |
| Sony          | VPCEH3N6E                   | [788ddd35a8](https://linux-hardware.org/?probe=788ddd35a8) | Jun 06, 2023 |
| Acer          | Aspire A715-51G             | [dbde8636bb](https://linux-hardware.org/?probe=dbde8636bb) | Jun 06, 2023 |
| Acer          | Aspire A315-31              | [d5da1b4b30](https://linux-hardware.org/?probe=d5da1b4b30) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [e4335c33f6](https://linux-hardware.org/?probe=e4335c33f6) | Jun 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [bf403bb6d8](https://linux-hardware.org/?probe=bf403bb6d8) | Jun 06, 2023 |
| Samsung       | 910S3L                      | [2db0ae25d8](https://linux-hardware.org/?probe=2db0ae25d8) | Jun 06, 2023 |
| Lenovo        | ThinkPad T590 20N5000AMH    | [91c0d99427](https://linux-hardware.org/?probe=91c0d99427) | Jun 06, 2023 |
| Dell          | Latitude 7400               | [9968377d89](https://linux-hardware.org/?probe=9968377d89) | Jun 06, 2023 |
| Dell          | XPS 13 9370                 | [82aba8957b](https://linux-hardware.org/?probe=82aba8957b) | Jun 06, 2023 |
| Dell          | Latitude E6400              | [ced90af89e](https://linux-hardware.org/?probe=ced90af89e) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [503bc1f4cc](https://linux-hardware.org/?probe=503bc1f4cc) | Jun 06, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [31a814cd0e](https://linux-hardware.org/?probe=31a814cd0e) | Jun 06, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [5159be9e2b](https://linux-hardware.org/?probe=5159be9e2b) | Jun 06, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [fc49284b9f](https://linux-hardware.org/?probe=fc49284b9f) | Jun 06, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [53cb8df21f](https://linux-hardware.org/?probe=53cb8df21f) | Jun 06, 2023 |
| Dell          | Precision 3571              | [35f408bce4](https://linux-hardware.org/?probe=35f408bce4) | Jun 06, 2023 |
| Dell          | Latitude 5530               | [a302ecd3cd](https://linux-hardware.org/?probe=a302ecd3cd) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | [450d20f29d](https://linux-hardware.org/?probe=450d20f29d) | Jun 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a06e6ab7ad](https://linux-hardware.org/?probe=a06e6ab7ad) | Jun 05, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [c8ca6e8787](https://linux-hardware.org/?probe=c8ca6e8787) | Jun 05, 2023 |
| ASUSTek       | G750JM                      | [cdb3539c93](https://linux-hardware.org/?probe=cdb3539c93) | Jun 05, 2023 |
| HP            | ENVY m6 Notebook            | [5bc28b7062](https://linux-hardware.org/?probe=5bc28b7062) | Jun 05, 2023 |
| HP            | ENVY m6 Notebook            | [aff6da41b8](https://linux-hardware.org/?probe=aff6da41b8) | Jun 05, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [ceab55a00c](https://linux-hardware.org/?probe=ceab55a00c) | Jun 05, 2023 |
| HP            | Laptop 14-fq0xxx            | [02614f184c](https://linux-hardware.org/?probe=02614f184c) | Jun 05, 2023 |
| Infinix       | INBOOK X2                   | [0a82b1aed3](https://linux-hardware.org/?probe=0a82b1aed3) | Jun 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ea07821e39](https://linux-hardware.org/?probe=ea07821e39) | Jun 05, 2023 |
| HP            | Pavilion dm4                | [63bd248ea6](https://linux-hardware.org/?probe=63bd248ea6) | Jun 05, 2023 |
| Toshiba       | Satellite L655              | [1b9656a4a1](https://linux-hardware.org/?probe=1b9656a4a1) | Jun 04, 2023 |
| ASUSTek       | G750JM                      | [f492ab6829](https://linux-hardware.org/?probe=f492ab6829) | Jun 04, 2023 |
| HP            | 2000                        | [7b24eaf0d9](https://linux-hardware.org/?probe=7b24eaf0d9) | Jun 04, 2023 |
| HP            | 2000                        | [dfee85b8e7](https://linux-hardware.org/?probe=dfee85b8e7) | Jun 04, 2023 |
| IP3 Tech      | AP1                         | [d24ecf10e2](https://linux-hardware.org/?probe=d24ecf10e2) | Jun 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | [8fa7afa4a1](https://linux-hardware.org/?probe=8fa7afa4a1) | Jun 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [a00b8e7d13](https://linux-hardware.org/?probe=a00b8e7d13) | Jun 04, 2023 |
| Apple         | MacBookPro13,3              | [885709a33f](https://linux-hardware.org/?probe=885709a33f) | Jun 04, 2023 |
| Lenovo        | ThinkPad T450 20BU000FUS    | [a0181fbf52](https://linux-hardware.org/?probe=a0181fbf52) | Jun 04, 2023 |
| Samsung       | 950XED                      | [185834c02e](https://linux-hardware.org/?probe=185834c02e) | Jun 04, 2023 |
| Lanix         | AL V9                       | [3bd23fdde7](https://linux-hardware.org/?probe=3bd23fdde7) | Jun 04, 2023 |
| MSI           | Modern 14 B5M               | [da21766a5c](https://linux-hardware.org/?probe=da21766a5c) | Jun 04, 2023 |
| HP            | Pavilion 15                 | [dc8f67bb03](https://linux-hardware.org/?probe=dc8f67bb03) | Jun 03, 2023 |
| Schenker      | XMG FOCUS (M22)             | [31203c3645](https://linux-hardware.org/?probe=31203c3645) | Jun 03, 2023 |
| Dell          | Inspiron 13-5368            | [33bb0f34df](https://linux-hardware.org/?probe=33bb0f34df) | Jun 03, 2023 |
| ASUSTek       | X553MA                      | [d07b3215b1](https://linux-hardware.org/?probe=d07b3215b1) | Jun 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f12b791748](https://linux-hardware.org/?probe=f12b791748) | Jun 03, 2023 |
| ASUSTek       | K52Je                       | [c6f78ba2aa](https://linux-hardware.org/?probe=c6f78ba2aa) | Jun 03, 2023 |
| Dell          | Inspiron 5559               | [9e1fe43cf9](https://linux-hardware.org/?probe=9e1fe43cf9) | Jun 03, 2023 |
| Acer          | Aspire A114-31              | [7a760e7ad6](https://linux-hardware.org/?probe=7a760e7ad6) | Jun 03, 2023 |
| Dell          | Latitude E5430 non-vPro     | [ba2dfac7ae](https://linux-hardware.org/?probe=ba2dfac7ae) | Jun 03, 2023 |
| Dell          | Latitude E7450              | [fe7cb1e53f](https://linux-hardware.org/?probe=fe7cb1e53f) | Jun 03, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [1e4ffa48ce](https://linux-hardware.org/?probe=1e4ffa48ce) | Jun 03, 2023 |
| Dell          | Inspiron 5490               | [a0cc355293](https://linux-hardware.org/?probe=a0cc355293) | Jun 03, 2023 |
| Dell          | G15 5520                    | [b77b760dfe](https://linux-hardware.org/?probe=b77b760dfe) | Jun 03, 2023 |
| NCS-Tech      | B300                        | [895395765b](https://linux-hardware.org/?probe=895395765b) | Jun 03, 2023 |
| Toshiba       | Satellite L655              | [9b83a4575b](https://linux-hardware.org/?probe=9b83a4575b) | Jun 02, 2023 |
| Notebook      | NL40_50CU                   | [47b838db36](https://linux-hardware.org/?probe=47b838db36) | Jun 02, 2023 |
| Dell          | Latitude 6430U              | [3104417f5e](https://linux-hardware.org/?probe=3104417f5e) | Jun 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [a6d6fdfe4f](https://linux-hardware.org/?probe=a6d6fdfe4f) | Jun 02, 2023 |
| Dell          | Inspiron 15 7000 Gaming     | [664282cc84](https://linux-hardware.org/?probe=664282cc84) | Jun 02, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4d170e024e](https://linux-hardware.org/?probe=4d170e024e) | Jun 02, 2023 |
| Acer          | Aspire 7745G                | [7739f949e1](https://linux-hardware.org/?probe=7739f949e1) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b8c8f96b56](https://linux-hardware.org/?probe=b8c8f96b56) | Jun 02, 2023 |
| HUAWEI        | MACHC-WAX9                  | [c87d784c98](https://linux-hardware.org/?probe=c87d784c98) | Jun 02, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [a7c067f896](https://linux-hardware.org/?probe=a7c067f896) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [6b1168349b](https://linux-hardware.org/?probe=6b1168349b) | Jun 02, 2023 |
| HP            | Laptop 15s-eq2xxx           | [302ae0e2dc](https://linux-hardware.org/?probe=302ae0e2dc) | Jun 02, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [3da98cc9bb](https://linux-hardware.org/?probe=3da98cc9bb) | Jun 02, 2023 |
| Apple         | MacBookPro5,5               | [29c4ba7312](https://linux-hardware.org/?probe=29c4ba7312) | Jun 01, 2023 |
| Unknown       | Unknown                     | [fa6344a8eb](https://linux-hardware.org/?probe=fa6344a8eb) | Jun 01, 2023 |
| Lenovo        | ThinkPad T530 2392AHG       | [05c41c8464](https://linux-hardware.org/?probe=05c41c8464) | Jun 01, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [98b0b355db](https://linux-hardware.org/?probe=98b0b355db) | Jun 01, 2023 |
| Apple         | MacBookAir4,1               | [42b1507aa8](https://linux-hardware.org/?probe=42b1507aa8) | Jun 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [fcc2d0ed39](https://linux-hardware.org/?probe=fcc2d0ed39) | Jun 01, 2023 |
| HP            | EliteBook 820 G2            | [c9409c532d](https://linux-hardware.org/?probe=c9409c532d) | Jun 01, 2023 |
| Lenovo        | G400s VILG1                 | [fee541ee18](https://linux-hardware.org/?probe=fee541ee18) | Jun 01, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [33e440f44f](https://linux-hardware.org/?probe=33e440f44f) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | [9324563727](https://linux-hardware.org/?probe=9324563727) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | [778e78d2a5](https://linux-hardware.org/?probe=778e78d2a5) | Jun 01, 2023 |
| HP            | ProBook 440 G4              | [af2f742bc5](https://linux-hardware.org/?probe=af2f742bc5) | Jun 01, 2023 |
| ASUSTek       | X550CA                      | [fe31674f48](https://linux-hardware.org/?probe=fe31674f48) | Jun 01, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [0afa6e53d0](https://linux-hardware.org/?probe=0afa6e53d0) | Jun 01, 2023 |
| Apple         | MacBook4,1                  | [996b318420](https://linux-hardware.org/?probe=996b318420) | Jun 01, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [3e49e329d3](https://linux-hardware.org/?probe=3e49e329d3) | Jun 01, 2023 |
| Packard Be... | EasyNote LJ75               | [95c733d00f](https://linux-hardware.org/?probe=95c733d00f) | May 31, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [b7032438d2](https://linux-hardware.org/?probe=b7032438d2) | May 31, 2023 |
| MSI           | GE70 2QE                    | [a075b8b77d](https://linux-hardware.org/?probe=a075b8b77d) | May 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | [bfcb7f950d](https://linux-hardware.org/?probe=bfcb7f950d) | May 31, 2023 |
| Lenovo        | Yoga S740-14IIL 81RS        | [2c315764a9](https://linux-hardware.org/?probe=2c315764a9) | May 31, 2023 |
| Dell          | Inspiron 3502               | [3c734d2900](https://linux-hardware.org/?probe=3c734d2900) | May 31, 2023 |
| Toshiba       | Satellite L850              | [cee0a13d3f](https://linux-hardware.org/?probe=cee0a13d3f) | May 31, 2023 |
| Dell          | Precision 7670              | [77b039b486](https://linux-hardware.org/?probe=77b039b486) | May 31, 2023 |
| AXIOO         | Mybook-14E                  | [cb04b551d8](https://linux-hardware.org/?probe=cb04b551d8) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [7210e5c07e](https://linux-hardware.org/?probe=7210e5c07e) | May 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [0ead50ad49](https://linux-hardware.org/?probe=0ead50ad49) | May 31, 2023 |
| Jumper        | EZbook                      | [3ccf2e1365](https://linux-hardware.org/?probe=3ccf2e1365) | May 31, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [742ae62ba6](https://linux-hardware.org/?probe=742ae62ba6) | May 30, 2023 |
| Acer          | Aspire V3-574G              | [728459dd4a](https://linux-hardware.org/?probe=728459dd4a) | May 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [ada20f1f6a](https://linux-hardware.org/?probe=ada20f1f6a) | May 30, 2023 |
| HP            | ENVY 15                     | [5acbfb03f4](https://linux-hardware.org/?probe=5acbfb03f4) | May 30, 2023 |
| Toshiba       | Satellite C665              | [c6149a6430](https://linux-hardware.org/?probe=c6149a6430) | May 30, 2023 |
| Apple         | MacBookPro11,1              | [b881639bef](https://linux-hardware.org/?probe=b881639bef) | May 30, 2023 |
| HP            | Pavilion 15                 | [ca18fafda8](https://linux-hardware.org/?probe=ca18fafda8) | May 29, 2023 |
| Acer          | Aspire A515-57              | [e9f91331b2](https://linux-hardware.org/?probe=e9f91331b2) | May 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [509bb7aae7](https://linux-hardware.org/?probe=509bb7aae7) | May 29, 2023 |
| MSI           | Katana GF76 12UD            | [b1b1816b59](https://linux-hardware.org/?probe=b1b1816b59) | May 29, 2023 |
| Notebook      | NV4XMB,ME,MZ                | [6fdc7285f2](https://linux-hardware.org/?probe=6fdc7285f2) | May 29, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [202bf4f657](https://linux-hardware.org/?probe=202bf4f657) | May 29, 2023 |
| Lenovo        | ThinkBook 16p Gen 4 21J8    | [bb60c42e07](https://linux-hardware.org/?probe=bb60c42e07) | May 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | [ea6330526c](https://linux-hardware.org/?probe=ea6330526c) | May 29, 2023 |
| Sony          | VPCEA45FG                   | [873ca04445](https://linux-hardware.org/?probe=873ca04445) | May 29, 2023 |
| MSI           | Raider GE76 12UE            | [5e8f375846](https://linux-hardware.org/?probe=5e8f375846) | May 29, 2023 |
| Dell          | Inspiron 15-7568            | [227930e25d](https://linux-hardware.org/?probe=227930e25d) | May 29, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [4353f50548](https://linux-hardware.org/?probe=4353f50548) | May 28, 2023 |
| Lenovo        | ThinkPad T540p 20BE00AKZ... | [f9bc4694e4](https://linux-hardware.org/?probe=f9bc4694e4) | May 28, 2023 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | [d993490e5a](https://linux-hardware.org/?probe=d993490e5a) | May 28, 2023 |
| Apple         | MacBookAir4,1               | [25c6965a47](https://linux-hardware.org/?probe=25c6965a47) | May 28, 2023 |
| Apple         | MacBookAir4,1               | [e950caa0ce](https://linux-hardware.org/?probe=e950caa0ce) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [95793a85de](https://linux-hardware.org/?probe=95793a85de) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [7c9addaf1c](https://linux-hardware.org/?probe=7c9addaf1c) | May 28, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [9178413d40](https://linux-hardware.org/?probe=9178413d40) | May 28, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [c5b13d6ea2](https://linux-hardware.org/?probe=c5b13d6ea2) | May 28, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [960ddf4eaf](https://linux-hardware.org/?probe=960ddf4eaf) | May 28, 2023 |
| Lenovo        | V130-15IKB 81HN             | [e50700f8be](https://linux-hardware.org/?probe=e50700f8be) | May 28, 2023 |
| HP            | EliteBook 840 G1            | [a1aa06298d](https://linux-hardware.org/?probe=a1aa06298d) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [86876e9715](https://linux-hardware.org/?probe=86876e9715) | May 28, 2023 |
| HUAWEI        | HVY-WXX9                    | [412b42ae92](https://linux-hardware.org/?probe=412b42ae92) | May 28, 2023 |
| Shuttle       | X50V5                       | [277cc7ca36](https://linux-hardware.org/?probe=277cc7ca36) | May 28, 2023 |
| Acer          | Aspire A515-56              | [4d8767d94b](https://linux-hardware.org/?probe=4d8767d94b) | May 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [c2125f60d2](https://linux-hardware.org/?probe=c2125f60d2) | May 28, 2023 |
| Apple         | MacBookAir8,1               | [47b2ee3c0d](https://linux-hardware.org/?probe=47b2ee3c0d) | May 28, 2023 |
| Dell          | Vostro 5402                 | [41a9c1dcf2](https://linux-hardware.org/?probe=41a9c1dcf2) | May 28, 2023 |
| Lenovo        | V130-15IGM 81HL             | [76a357994a](https://linux-hardware.org/?probe=76a357994a) | May 27, 2023 |
| HP            | Laptop 15s-fq5xxx           | [c6309fc374](https://linux-hardware.org/?probe=c6309fc374) | May 27, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [1eecbd5808](https://linux-hardware.org/?probe=1eecbd5808) | May 27, 2023 |
| Lenovo        | G50-70 20351                | [ee0a9f666c](https://linux-hardware.org/?probe=ee0a9f666c) | May 27, 2023 |
| HUAWEI        | HVY-WXX9                    | [3f6fc3ec0c](https://linux-hardware.org/?probe=3f6fc3ec0c) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | [9605e313ac](https://linux-hardware.org/?probe=9605e313ac) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | [0a8ae92c13](https://linux-hardware.org/?probe=0a8ae92c13) | May 27, 2023 |
| HP            | ProBook 650 G1              | [8b2266868a](https://linux-hardware.org/?probe=8b2266868a) | May 27, 2023 |
| Dell          | Latitude 7490               | [fbad4c1a53](https://linux-hardware.org/?probe=fbad4c1a53) | May 27, 2023 |
| Dell          | Latitude 7490               | [00c44ed00c](https://linux-hardware.org/?probe=00c44ed00c) | May 27, 2023 |
| Apple         | MacBookPro5,5               | [f1b7ea69ea](https://linux-hardware.org/?probe=f1b7ea69ea) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [cc9d03264f](https://linux-hardware.org/?probe=cc9d03264f) | May 27, 2023 |
| Samsung       | 910S3G/910S3T               | [e041a5365e](https://linux-hardware.org/?probe=e041a5365e) | May 26, 2023 |
| MSI           | Raider GE76 12UE            | [25bcdc17b0](https://linux-hardware.org/?probe=25bcdc17b0) | May 26, 2023 |
| Dell          | Inspiron N4020              | [6350805cd6](https://linux-hardware.org/?probe=6350805cd6) | May 26, 2023 |
| Dell          | Inspiron N4020              | [801ec6309f](https://linux-hardware.org/?probe=801ec6309f) | May 26, 2023 |
| ASUSTek       | K52Je                       | [3b40aeae90](https://linux-hardware.org/?probe=3b40aeae90) | May 26, 2023 |
| HP            | Pavilion Notebook           | [1c67718bdb](https://linux-hardware.org/?probe=1c67718bdb) | May 26, 2023 |
| Dell          | Latitude E7450              | [4a88622321](https://linux-hardware.org/?probe=4a88622321) | May 26, 2023 |
| ASUSTek       | X550CA                      | [3aebf9eb7c](https://linux-hardware.org/?probe=3aebf9eb7c) | May 26, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [98308c882b](https://linux-hardware.org/?probe=98308c882b) | May 26, 2023 |
| Toshiba       | Satellite S55-A             | [2b9beaf4a6](https://linux-hardware.org/?probe=2b9beaf4a6) | May 25, 2023 |
| Clevo         | P150HMx                     | [d6c90a2c0c](https://linux-hardware.org/?probe=d6c90a2c0c) | May 25, 2023 |
| MSI           | GE75 Raider 10SF            | [5ee0afea25](https://linux-hardware.org/?probe=5ee0afea25) | May 25, 2023 |
| ASUSTek       | N75SF                       | [38840055c8](https://linux-hardware.org/?probe=38840055c8) | May 25, 2023 |
| Dell          | Latitude 5480               | [adb6ba25f1](https://linux-hardware.org/?probe=adb6ba25f1) | May 25, 2023 |
| HP            | Pavilion Notebook           | [945b06d022](https://linux-hardware.org/?probe=945b06d022) | May 25, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | [270540781d](https://linux-hardware.org/?probe=270540781d) | May 25, 2023 |
| Dell          | G15 5510                    | [325fcf6e78](https://linux-hardware.org/?probe=325fcf6e78) | May 25, 2023 |
| Dell          | Latitude 5440               | [5a27bd40e7](https://linux-hardware.org/?probe=5a27bd40e7) | May 25, 2023 |
| Samsung       | 900X5T                      | [9f1d226c85](https://linux-hardware.org/?probe=9f1d226c85) | May 25, 2023 |
| Dell          | Latitude 5480               | [45b63ce664](https://linux-hardware.org/?probe=45b63ce664) | May 25, 2023 |
| HP            | Laptop 14-dq2xxx            | [589112cb44](https://linux-hardware.org/?probe=589112cb44) | May 25, 2023 |
| Dell          | Inspiron 15-7568            | [161ed53585](https://linux-hardware.org/?probe=161ed53585) | May 25, 2023 |
| Acer          | Aspire A514-55              | [17996395f4](https://linux-hardware.org/?probe=17996395f4) | May 25, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [5d83c85225](https://linux-hardware.org/?probe=5d83c85225) | May 25, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [c885a13922](https://linux-hardware.org/?probe=c885a13922) | May 25, 2023 |
| Fujitsu       | LIFEBOOK AH530              | [897b688aba](https://linux-hardware.org/?probe=897b688aba) | May 25, 2023 |
| Dell          | Latitude 5420               | [a4690b7476](https://linux-hardware.org/?probe=a4690b7476) | May 25, 2023 |
| HP            | Laptop 14-dq1xxx            | [dddde1dc45](https://linux-hardware.org/?probe=dddde1dc45) | May 25, 2023 |
| HP            | Pavilion 17                 | [792ac6919d](https://linux-hardware.org/?probe=792ac6919d) | May 24, 2023 |
| Alienware     | 17 R3                       | [a567b379a1](https://linux-hardware.org/?probe=a567b379a1) | May 24, 2023 |
| Apple         | MacBookPro6,2               | [6858db4f73](https://linux-hardware.org/?probe=6858db4f73) | May 24, 2023 |
| MSI           | GF63 Thin 9RC               | [aef2c48b64](https://linux-hardware.org/?probe=aef2c48b64) | May 24, 2023 |
| ASUSTek       | K55VJ                       | [2b12b33767](https://linux-hardware.org/?probe=2b12b33767) | May 24, 2023 |
| HP            | Laptop 14-dq1xxx            | [d8261039f8](https://linux-hardware.org/?probe=d8261039f8) | May 24, 2023 |
| Dell          | Precision 5520              | [a5e0cc8586](https://linux-hardware.org/?probe=a5e0cc8586) | May 24, 2023 |
| Lenovo        | ThinkPad W530 24472BG       | [6431c2bb45](https://linux-hardware.org/?probe=6431c2bb45) | May 24, 2023 |
| Dell          | G15 5510                    | [730985e467](https://linux-hardware.org/?probe=730985e467) | May 24, 2023 |
| HP            | Stream Laptop 14-ds0xxx     | [587ab1857a](https://linux-hardware.org/?probe=587ab1857a) | May 24, 2023 |
| Lenovo        | Unknown                     | [e7148e7a18](https://linux-hardware.org/?probe=e7148e7a18) | May 23, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [0c665ebdd8](https://linux-hardware.org/?probe=0c665ebdd8) | May 23, 2023 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [a81e627367](https://linux-hardware.org/?probe=a81e627367) | May 23, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [3e2ccc8b5e](https://linux-hardware.org/?probe=3e2ccc8b5e) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [47c0ef11d2](https://linux-hardware.org/?probe=47c0ef11d2) | May 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E203... | [0f7e3e95a2](https://linux-hardware.org/?probe=0f7e3e95a2) | May 23, 2023 |
| Lenovo        | ThinkPad T470s 20HGS4RU0... | [ac8df81694](https://linux-hardware.org/?probe=ac8df81694) | May 23, 2023 |
| HP            | ENVY Laptop 13-ba1xxx       | [a11fdd0361](https://linux-hardware.org/?probe=a11fdd0361) | May 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [d704fd9efd](https://linux-hardware.org/?probe=d704fd9efd) | May 23, 2023 |
| HP            | ProBook 450 G3              | [4400f1205b](https://linux-hardware.org/?probe=4400f1205b) | May 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [2fffd70abb](https://linux-hardware.org/?probe=2fffd70abb) | May 23, 2023 |
| Apple         | MacBookPro13,2              | [8b87a13f50](https://linux-hardware.org/?probe=8b87a13f50) | May 23, 2023 |
| Dell          | Inspiron 5575               | [7d93944943](https://linux-hardware.org/?probe=7d93944943) | May 23, 2023 |
| Apple         | MacBookPro13,2              | [f0ef45dcf3](https://linux-hardware.org/?probe=f0ef45dcf3) | May 23, 2023 |
| Chuwi         | HeroBook Air                | [724db856f3](https://linux-hardware.org/?probe=724db856f3) | May 23, 2023 |
| Lenovo        | ThinkBook 15 G4 ABA 21DL    | [c77cb59a5c](https://linux-hardware.org/?probe=c77cb59a5c) | May 23, 2023 |
| Lenovo        | ThinkPad T540p 20BF001NU... | [2a770d2eac](https://linux-hardware.org/?probe=2a770d2eac) | May 23, 2023 |
| Dell          | Latitude E5570              | [3b1aaa683d](https://linux-hardware.org/?probe=3b1aaa683d) | May 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS0100G    | [069d442d0d](https://linux-hardware.org/?probe=069d442d0d) | May 22, 2023 |
| Acer          | Aspire A715-42G             | [39bb190ac7](https://linux-hardware.org/?probe=39bb190ac7) | May 22, 2023 |
| ASUSTek       | X555LNB                     | [a1aa3cf4b2](https://linux-hardware.org/?probe=a1aa3cf4b2) | May 22, 2023 |
| HUAWEI        | KLVL-WXXW                   | [6ca579ee78](https://linux-hardware.org/?probe=6ca579ee78) | May 22, 2023 |
| HP            | EliteBook 850 G6            | [b38d6399b4](https://linux-hardware.org/?probe=b38d6399b4) | May 22, 2023 |
| ASUSTek       | UX301LAB                    | [69f7b4ae4f](https://linux-hardware.org/?probe=69f7b4ae4f) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | [895bca272b](https://linux-hardware.org/?probe=895bca272b) | May 22, 2023 |
| Apple         | MacBookPro5,5               | [7978c97691](https://linux-hardware.org/?probe=7978c97691) | May 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [14b20068ca](https://linux-hardware.org/?probe=14b20068ca) | May 22, 2023 |
| Apple         | MacBookPro15,1              | [f1d994fa47](https://linux-hardware.org/?probe=f1d994fa47) | May 22, 2023 |
| Dell          | XPS 9315                    | [6c3fdbf590](https://linux-hardware.org/?probe=6c3fdbf590) | May 22, 2023 |
| Dell          | Inspiron 7520               | [eeca18ff12](https://linux-hardware.org/?probe=eeca18ff12) | May 22, 2023 |
| HP            | Pavilion g4                 | [3324fbbbaa](https://linux-hardware.org/?probe=3324fbbbaa) | May 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [dedcc1bb3f](https://linux-hardware.org/?probe=dedcc1bb3f) | May 22, 2023 |
| HUAWEI        | MACHC-WAX9                  | [536b91dce1](https://linux-hardware.org/?probe=536b91dce1) | May 21, 2023 |
| Acer          | Aspire E5-575G              | [d27d5d547e](https://linux-hardware.org/?probe=d27d5d547e) | May 21, 2023 |
| Sony          | VPCF120FD                   | [a438459d06](https://linux-hardware.org/?probe=a438459d06) | May 21, 2023 |
| MSI           | PS63 Modern 8MO             | [5d6f78bfbb](https://linux-hardware.org/?probe=5d6f78bfbb) | May 21, 2023 |
| Apple         | MacBookPro16,2              | [e4adcd71f1](https://linux-hardware.org/?probe=e4adcd71f1) | May 21, 2023 |
| Apple         | MacBookPro16,2              | [09f37f2540](https://linux-hardware.org/?probe=09f37f2540) | May 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [32e623c724](https://linux-hardware.org/?probe=32e623c724) | May 21, 2023 |
| HP            | Pavilion 15                 | [7afbe545bc](https://linux-hardware.org/?probe=7afbe545bc) | May 21, 2023 |
| Apple         | MacBook4,1                  | [d404dc5e03](https://linux-hardware.org/?probe=d404dc5e03) | May 21, 2023 |
| ASUSTek       | UX430UAR                    | [7815f47a45](https://linux-hardware.org/?probe=7815f47a45) | May 21, 2023 |
| ASUSTek       | K56CA                       | [6ae76c1553](https://linux-hardware.org/?probe=6ae76c1553) | May 21, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [3a448141db](https://linux-hardware.org/?probe=3a448141db) | May 21, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [dda7ad1c16](https://linux-hardware.org/?probe=dda7ad1c16) | May 21, 2023 |
| Toshiba       | Satellite Pro S500          | [b08ca84ea8](https://linux-hardware.org/?probe=b08ca84ea8) | May 20, 2023 |
| Unknown       | Unknown                     | [2d705adeaa](https://linux-hardware.org/?probe=2d705adeaa) | May 20, 2023 |
| Dell          | G3 3500                     | [29f1b0fbda](https://linux-hardware.org/?probe=29f1b0fbda) | May 20, 2023 |
| Acer          | Aspire E1-571               | [cce6eaa028](https://linux-hardware.org/?probe=cce6eaa028) | May 20, 2023 |
| Lenovo        | IdeaPad 1 15IGL7 82V7       | [6bce5f1ff0](https://linux-hardware.org/?probe=6bce5f1ff0) | May 20, 2023 |
| Dell          | Latitude E7450              | [51f34cd446](https://linux-hardware.org/?probe=51f34cd446) | May 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [c5fee7bb50](https://linux-hardware.org/?probe=c5fee7bb50) | May 20, 2023 |
| Acer          | Aspire S3                   | [b6841c9aeb](https://linux-hardware.org/?probe=b6841c9aeb) | May 20, 2023 |
| Acer          | Aspire S3                   | [3fafb0df5d](https://linux-hardware.org/?probe=3fafb0df5d) | May 20, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [7d4516eff2](https://linux-hardware.org/?probe=7d4516eff2) | May 20, 2023 |
| HP            | ProBook 450 G4              | [054ec4f1cb](https://linux-hardware.org/?probe=054ec4f1cb) | May 20, 2023 |
| Dell          | Latitude 7280               | [9b98a88e3d](https://linux-hardware.org/?probe=9b98a88e3d) | May 19, 2023 |
| Dell          | Latitude E7450              | [e844aeb177](https://linux-hardware.org/?probe=e844aeb177) | May 19, 2023 |
| Lenovo        | G50-30 80G0                 | [03c6d7a815](https://linux-hardware.org/?probe=03c6d7a815) | May 19, 2023 |
| HUAWEI        | BOHB-WAX9                   | [f69b95b887](https://linux-hardware.org/?probe=f69b95b887) | May 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [3ad05eed61](https://linux-hardware.org/?probe=3ad05eed61) | May 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [73aafcfb9c](https://linux-hardware.org/?probe=73aafcfb9c) | May 19, 2023 |
| Acer          | Aspire E5-771G              | [0dadbeca5b](https://linux-hardware.org/?probe=0dadbeca5b) | May 19, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [c0e3ea54c0](https://linux-hardware.org/?probe=c0e3ea54c0) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [b0ed659e7d](https://linux-hardware.org/?probe=b0ed659e7d) | May 19, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [749d31d44a](https://linux-hardware.org/?probe=749d31d44a) | May 19, 2023 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [85da505294](https://linux-hardware.org/?probe=85da505294) | May 19, 2023 |
| MSI           | GE75 Raider 10SF            | [8aaec63d14](https://linux-hardware.org/?probe=8aaec63d14) | May 19, 2023 |
| Lenovo        | IdeaPad U530 Touch 20289    | [72e254e4ee](https://linux-hardware.org/?probe=72e254e4ee) | May 19, 2023 |
| MSI           | GE75 Raider 10SF            | [f3724cb7da](https://linux-hardware.org/?probe=f3724cb7da) | May 19, 2023 |
| Unknown       | Unknown                     | [49c702a8c9](https://linux-hardware.org/?probe=49c702a8c9) | May 18, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C2C... | [a0f983e519](https://linux-hardware.org/?probe=a0f983e519) | May 18, 2023 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [7f35aa414f](https://linux-hardware.org/?probe=7f35aa414f) | May 18, 2023 |
| Dell          | Latitude E6500              | [27213adbe8](https://linux-hardware.org/?probe=27213adbe8) | May 18, 2023 |
| Sony          | SVF1521A6EW                 | [49a9f77ea9](https://linux-hardware.org/?probe=49a9f77ea9) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [6141537b7b](https://linux-hardware.org/?probe=6141537b7b) | May 18, 2023 |
| Dell          | Vostro 15 3510              | [e5e7213107](https://linux-hardware.org/?probe=e5e7213107) | May 18, 2023 |
| Toshiba       | PORTEGE Z830                | [f4548ca81b](https://linux-hardware.org/?probe=f4548ca81b) | May 18, 2023 |
| HUAWEI        | BOD-WXX9                    | [62e064b7d0](https://linux-hardware.org/?probe=62e064b7d0) | May 18, 2023 |
| Acer          | Aspire 7535                 | [32b02980a7](https://linux-hardware.org/?probe=32b02980a7) | May 18, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [ba813a3367](https://linux-hardware.org/?probe=ba813a3367) | May 18, 2023 |
| Sony          | VPCEB4Z1E                   | [d1cca131ad](https://linux-hardware.org/?probe=d1cca131ad) | May 18, 2023 |
| Dell          | Inspiron 5567               | [45888dea42](https://linux-hardware.org/?probe=45888dea42) | May 18, 2023 |
| Clevo         | P150HMx                     | [17e11751ef](https://linux-hardware.org/?probe=17e11751ef) | May 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c152120c9e](https://linux-hardware.org/?probe=c152120c9e) | May 18, 2023 |
| Clevo         | P150HMx                     | [f749300168](https://linux-hardware.org/?probe=f749300168) | May 18, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [cf1d4ac757](https://linux-hardware.org/?probe=cf1d4ac757) | May 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | [a23a2d1c6c](https://linux-hardware.org/?probe=a23a2d1c6c) | May 18, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [a167afa608](https://linux-hardware.org/?probe=a167afa608) | May 17, 2023 |
| Acer          | Swift SF316-51              | [663e7fe745](https://linux-hardware.org/?probe=663e7fe745) | May 17, 2023 |
| ASUSTek       | TP300LA                     | [e2e6bc0209](https://linux-hardware.org/?probe=e2e6bc0209) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | [d07aa12d74](https://linux-hardware.org/?probe=d07aa12d74) | May 17, 2023 |
| Acer          | TravelMate P215-53G         | [d2908ee6a9](https://linux-hardware.org/?probe=d2908ee6a9) | May 17, 2023 |
| Acer          | Nitro AN517-54              | [9372615767](https://linux-hardware.org/?probe=9372615767) | May 17, 2023 |
| Dell          | Inspiron 5580               | [7ced5f9473](https://linux-hardware.org/?probe=7ced5f9473) | May 17, 2023 |
| HP            | Laptop 15s-du0xxx           | [ddc3152cbc](https://linux-hardware.org/?probe=ddc3152cbc) | May 17, 2023 |
| Acer          | Nitro AN515-58              | [c9d2b44907](https://linux-hardware.org/?probe=c9d2b44907) | May 17, 2023 |
| Acer          | Aspire 5742G                | [04a6fe63c1](https://linux-hardware.org/?probe=04a6fe63c1) | May 17, 2023 |
| Acer          | Aspire E5-571               | [76e48382f5](https://linux-hardware.org/?probe=76e48382f5) | May 17, 2023 |
| Dell          | Latitude 5290 2-in-1        | [cb196c4c37](https://linux-hardware.org/?probe=cb196c4c37) | May 17, 2023 |
| HP            | Laptop 15s-fq4xxx           | [c6d11a2f8e](https://linux-hardware.org/?probe=c6d11a2f8e) | May 17, 2023 |
| Packard Be... | EasyNote TV43CM             | [66dbc844c7](https://linux-hardware.org/?probe=66dbc844c7) | May 17, 2023 |
| Google        | Samus                       | [d627862e56](https://linux-hardware.org/?probe=d627862e56) | May 16, 2023 |
| ASUSTek       | UX305FA                     | [36cb231f34](https://linux-hardware.org/?probe=36cb231f34) | May 16, 2023 |
| HP            | Pavilion dv6                | [bc505434f7](https://linux-hardware.org/?probe=bc505434f7) | May 16, 2023 |
| Dell          | Latitude 5420               | [ddd072b69c](https://linux-hardware.org/?probe=ddd072b69c) | May 16, 2023 |
| Acer          | Aspire 5050                 | [44f9abca04](https://linux-hardware.org/?probe=44f9abca04) | May 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [2bfe226026](https://linux-hardware.org/?probe=2bfe226026) | May 16, 2023 |
| MSI           | GF63 Thin 9RC               | [b8f2e92853](https://linux-hardware.org/?probe=b8f2e92853) | May 16, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [c2ccca0208](https://linux-hardware.org/?probe=c2ccca0208) | May 16, 2023 |
| Toshiba       | Satellite C805D             | [21ee852978](https://linux-hardware.org/?probe=21ee852978) | May 16, 2023 |
| Dell          | Precision 5530              | [16366ef886](https://linux-hardware.org/?probe=16366ef886) | May 16, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [05441101a8](https://linux-hardware.org/?probe=05441101a8) | May 16, 2023 |
| AZW           | GT-R                        | [e156c5b105](https://linux-hardware.org/?probe=e156c5b105) | May 16, 2023 |
| Acer          | Aspire E5-571               | [6094f7a191](https://linux-hardware.org/?probe=6094f7a191) | May 16, 2023 |
| ASUSTek       | X550CC                      | [cce2c46f1e](https://linux-hardware.org/?probe=cce2c46f1e) | May 16, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [b2b220a903](https://linux-hardware.org/?probe=b2b220a903) | May 16, 2023 |
| HP            | ENVY 4                      | [ddc467f053](https://linux-hardware.org/?probe=ddc467f053) | May 16, 2023 |
| Lenovo        | ThinkPad L480 20LTSAK70R    | [551d238ad3](https://linux-hardware.org/?probe=551d238ad3) | May 16, 2023 |
| HP            | Compaq Presario CQ60        | [e01dbddbd0](https://linux-hardware.org/?probe=e01dbddbd0) | May 16, 2023 |
| HP            | Compaq Presario CQ60        | [72db5ccefc](https://linux-hardware.org/?probe=72db5ccefc) | May 15, 2023 |
| Dell          | Latitude E5530 non-vPro     | [040fb99c20](https://linux-hardware.org/?probe=040fb99c20) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [996d19a70c](https://linux-hardware.org/?probe=996d19a70c) | May 15, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [f5ef3c16c5](https://linux-hardware.org/?probe=f5ef3c16c5) | May 15, 2023 |
| Toshiba       | Satellite L655              | [2fa63538ef](https://linux-hardware.org/?probe=2fa63538ef) | May 15, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | [1bf9f3a0df](https://linux-hardware.org/?probe=1bf9f3a0df) | May 15, 2023 |
| Dell          | G3 3590                     | [75a6a8a107](https://linux-hardware.org/?probe=75a6a8a107) | May 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [33a9b42068](https://linux-hardware.org/?probe=33a9b42068) | May 15, 2023 |
| Apple         | MacBook4,1                  | [755f1920f2](https://linux-hardware.org/?probe=755f1920f2) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eg2xx... | [26c3a1e5cf](https://linux-hardware.org/?probe=26c3a1e5cf) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | [3bd39e50a8](https://linux-hardware.org/?probe=3bd39e50a8) | May 15, 2023 |
| Dell          | XPS 13 9350                 | [3e34d3a71c](https://linux-hardware.org/?probe=3e34d3a71c) | May 15, 2023 |
| Dell          | G3 3590                     | [b19462038d](https://linux-hardware.org/?probe=b19462038d) | May 15, 2023 |
| Lenovo        | ThinkPad T440p 20AN0079M... | [ec0250b092](https://linux-hardware.org/?probe=ec0250b092) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [b4e8e5504e](https://linux-hardware.org/?probe=b4e8e5504e) | May 15, 2023 |
| HP            | 250 G8 Notebook PC          | [47430a463a](https://linux-hardware.org/?probe=47430a463a) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [1573285475](https://linux-hardware.org/?probe=1573285475) | May 15, 2023 |
| Dell          | Inspiron 5405               | [9d3ae56a5e](https://linux-hardware.org/?probe=9d3ae56a5e) | May 15, 2023 |
| HP            | Laptop 15-db0xxx            | [61665ffc1a](https://linux-hardware.org/?probe=61665ffc1a) | May 15, 2023 |
| Dell          | Latitude 5520               | [721000195d](https://linux-hardware.org/?probe=721000195d) | May 15, 2023 |
| Dell          | Latitude 5401               | [4304efbed6](https://linux-hardware.org/?probe=4304efbed6) | May 15, 2023 |
| Lenovo        | ThinkPad L440 20ASA09T06    | [48009f1be4](https://linux-hardware.org/?probe=48009f1be4) | May 15, 2023 |
| Lenovo        | ThinkPad L440 20ASA09T06    | [49e6d93eb1](https://linux-hardware.org/?probe=49e6d93eb1) | May 15, 2023 |
| ASUSTek       | X550CA                      | [f48f5f9eaa](https://linux-hardware.org/?probe=f48f5f9eaa) | May 15, 2023 |
| HP            | Laptop 17-cn2xxx            | [9492267a05](https://linux-hardware.org/?probe=9492267a05) | May 15, 2023 |
| HUAWEI        | KLVL-WXXW                   | [d7e4640b82](https://linux-hardware.org/?probe=d7e4640b82) | May 15, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [fb4bda01b7](https://linux-hardware.org/?probe=fb4bda01b7) | May 15, 2023 |
| ASUSTek       | UX430UNR                    | [36f918cce7](https://linux-hardware.org/?probe=36f918cce7) | May 15, 2023 |
| ASUSTek       | UX430UNR                    | [1ba0adc2ba](https://linux-hardware.org/?probe=1ba0adc2ba) | May 15, 2023 |
| Acer          | Aspire A715-42G             | [b43ec1363a](https://linux-hardware.org/?probe=b43ec1363a) | May 14, 2023 |
| Acer          | Aspire A715-42G             | [b80a472c1a](https://linux-hardware.org/?probe=b80a472c1a) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | [bb119829d0](https://linux-hardware.org/?probe=bb119829d0) | May 14, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [d200313f91](https://linux-hardware.org/?probe=d200313f91) | May 14, 2023 |
| ASUSTek       | K55VJ                       | [bf3ff003f9](https://linux-hardware.org/?probe=bf3ff003f9) | May 14, 2023 |
| HP            | ZBook 15u G5                | [4f1f52ce64](https://linux-hardware.org/?probe=4f1f52ce64) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | [0ea14cadea](https://linux-hardware.org/?probe=0ea14cadea) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [8747e49a83](https://linux-hardware.org/?probe=8747e49a83) | May 14, 2023 |
| ASUSTek       | N76VZ                       | [fc6d34934a](https://linux-hardware.org/?probe=fc6d34934a) | May 14, 2023 |
| HP            | EliteBook 850 G6            | [df19e8413c](https://linux-hardware.org/?probe=df19e8413c) | May 14, 2023 |
| Acer          | Aspire A315-23              | [64237b5d6e](https://linux-hardware.org/?probe=64237b5d6e) | May 14, 2023 |
| HP            | Notebook                    | [c14e7a41cf](https://linux-hardware.org/?probe=c14e7a41cf) | May 13, 2023 |
| HP            | Notebook                    | [726fa4fcd1](https://linux-hardware.org/?probe=726fa4fcd1) | May 13, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [ed72b68c39](https://linux-hardware.org/?probe=ed72b68c39) | May 13, 2023 |
| ASUSTek       | UX430UNR                    | [a15b90ff4b](https://linux-hardware.org/?probe=a15b90ff4b) | May 13, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [0239277ed2](https://linux-hardware.org/?probe=0239277ed2) | May 13, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | [ef37458c10](https://linux-hardware.org/?probe=ef37458c10) | May 13, 2023 |
| ASUSTek       | K55DR                       | [e4f7010e78](https://linux-hardware.org/?probe=e4f7010e78) | May 13, 2023 |
| ASUSTek       | K55DR                       | [0d4d8571bf](https://linux-hardware.org/?probe=0d4d8571bf) | May 13, 2023 |
| Samsung       | 550XDA                      | [5f562807be](https://linux-hardware.org/?probe=5f562807be) | May 13, 2023 |
| HP            | ENVY Laptop 14-eb0xxx       | [79db0c9b3c](https://linux-hardware.org/?probe=79db0c9b3c) | May 13, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [6ade055af7](https://linux-hardware.org/?probe=6ade055af7) | May 13, 2023 |
| HP            | EliteBook 840 14 inch G9... | [26beee94a9](https://linux-hardware.org/?probe=26beee94a9) | May 12, 2023 |
| MSI           | GL73 8RC                    | [4eb76264f2](https://linux-hardware.org/?probe=4eb76264f2) | May 12, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [29e584b980](https://linux-hardware.org/?probe=29e584b980) | May 12, 2023 |
| Digma         | EVE 15 P417 NP3158CXW01     | [22673e3f0c](https://linux-hardware.org/?probe=22673e3f0c) | May 12, 2023 |
| Dell          | Precision 5550              | [f6d4846655](https://linux-hardware.org/?probe=f6d4846655) | May 12, 2023 |
| HP            | ENVY 17                     | [9f71f0b3e1](https://linux-hardware.org/?probe=9f71f0b3e1) | May 12, 2023 |
| MSI           | Stealth GS77 12UH           | [08fdf9cb20](https://linux-hardware.org/?probe=08fdf9cb20) | May 12, 2023 |
| ASUSTek       | X580VD                      | [971b7bfcd1](https://linux-hardware.org/?probe=971b7bfcd1) | May 12, 2023 |
| Panasonic     | CF-19-8                     | [1aa7d4071a](https://linux-hardware.org/?probe=1aa7d4071a) | May 12, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [b054e28875](https://linux-hardware.org/?probe=b054e28875) | May 12, 2023 |
| TUXEDO        | Pulse 15 Gen2               | [703faeb982](https://linux-hardware.org/?probe=703faeb982) | May 12, 2023 |
| Toshiba       | STI NA 1401                 | [c9aa3a7539](https://linux-hardware.org/?probe=c9aa3a7539) | May 12, 2023 |
| Samsung       | R430/R480                   | [076f13d198](https://linux-hardware.org/?probe=076f13d198) | May 12, 2023 |
| Dell          | Latitude 5300               | [917bfc93a5](https://linux-hardware.org/?probe=917bfc93a5) | May 12, 2023 |
| HP            | Laptop 17-cp0xxx            | [a47136c4d8](https://linux-hardware.org/?probe=a47136c4d8) | May 12, 2023 |
| Digma         | Pro Magnus M DN16R7-ADXW... | [4e4a1278e9](https://linux-hardware.org/?probe=4e4a1278e9) | May 12, 2023 |
| Dell          | Latitude 5530               | [ade218e4fa](https://linux-hardware.org/?probe=ade218e4fa) | May 11, 2023 |
| Acer          | Swift SFX14-51G             | [e18646482f](https://linux-hardware.org/?probe=e18646482f) | May 11, 2023 |
| Apple         | MacBookPro6,2               | [f56ecb2642](https://linux-hardware.org/?probe=f56ecb2642) | May 11, 2023 |
| Lenovo        | Slim 9 14IAP7 82T1          | [6c391cd64d](https://linux-hardware.org/?probe=6c391cd64d) | May 11, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | [9ed9aa95e8](https://linux-hardware.org/?probe=9ed9aa95e8) | May 11, 2023 |
| Lenovo        | Slim 9 14IAP7 82T1          | [4d2b811352](https://linux-hardware.org/?probe=4d2b811352) | May 11, 2023 |
| Chuwi         | GemiBook Pro                | [1f22322c4a](https://linux-hardware.org/?probe=1f22322c4a) | May 11, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [f55f75ca7d](https://linux-hardware.org/?probe=f55f75ca7d) | May 11, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | [8c58684afd](https://linux-hardware.org/?probe=8c58684afd) | May 11, 2023 |
| TUXEDO        | Book_XA1510                 | [9aed9e823a](https://linux-hardware.org/?probe=9aed9e823a) | May 11, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | [328d899b1c](https://linux-hardware.org/?probe=328d899b1c) | May 11, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | [c26f143862](https://linux-hardware.org/?probe=c26f143862) | May 11, 2023 |
| Digma         | EVE 11 C422 ES1068EW        | [6c6b40d9de](https://linux-hardware.org/?probe=6c6b40d9de) | May 10, 2023 |
| HP            | Pavilion g6                 | [2eaacf14f6](https://linux-hardware.org/?probe=2eaacf14f6) | May 10, 2023 |
| Acer          | Aspire 5810T                | [d21ea25d7a](https://linux-hardware.org/?probe=d21ea25d7a) | May 10, 2023 |
| Dell          | Inspiron 5590               | [117a2b318d](https://linux-hardware.org/?probe=117a2b318d) | May 10, 2023 |
| ASUSTek       | X550CC                      | [4d0b606423](https://linux-hardware.org/?probe=4d0b606423) | May 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [601a09abf6](https://linux-hardware.org/?probe=601a09abf6) | May 10, 2023 |
| Toshiba       | Satellite Pro R50-C         | [66fe960f10](https://linux-hardware.org/?probe=66fe960f10) | May 10, 2023 |
| Sony          | SVE1713K1EB                 | [96244b73e7](https://linux-hardware.org/?probe=96244b73e7) | May 10, 2023 |
| Fujitsu Si... | AMILO Pa 2548               | [d5d7d8308f](https://linux-hardware.org/?probe=d5d7d8308f) | May 10, 2023 |
| HUAWEI        | MACHD-WXX9                  | [7b956abe69](https://linux-hardware.org/?probe=7b956abe69) | May 10, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [35750a650a](https://linux-hardware.org/?probe=35750a650a) | May 10, 2023 |
| HP            | EliteBook 840 G3            | [46015ea246](https://linux-hardware.org/?probe=46015ea246) | May 10, 2023 |
| HONOR         | HYM-WXX                     | [ab5b69b742](https://linux-hardware.org/?probe=ab5b69b742) | May 10, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JW... | [0308c5d0c5](https://linux-hardware.org/?probe=0308c5d0c5) | May 10, 2023 |
| eMachines     | E625                        | [1271e33078](https://linux-hardware.org/?probe=1271e33078) | May 10, 2023 |
| Dell          | Inspiron 5590               | [9c53d54cae](https://linux-hardware.org/?probe=9c53d54cae) | May 10, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | [da9df7e3c6](https://linux-hardware.org/?probe=da9df7e3c6) | May 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [813acd1225](https://linux-hardware.org/?probe=813acd1225) | May 10, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1bd26fc56f](https://linux-hardware.org/?probe=1bd26fc56f) | May 10, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [afde593648](https://linux-hardware.org/?probe=afde593648) | May 10, 2023 |
| eMachines     | E625                        | [3160c872b8](https://linux-hardware.org/?probe=3160c872b8) | May 10, 2023 |
| Gateway       | P-7805u                     | [2713d979c4](https://linux-hardware.org/?probe=2713d979c4) | May 10, 2023 |
| Gateway       | P-7805u                     | [bdf7e6c628](https://linux-hardware.org/?probe=bdf7e6c628) | May 10, 2023 |
| HP            | Pavilion g6                 | [5c616bbd80](https://linux-hardware.org/?probe=5c616bbd80) | May 10, 2023 |
| Apple         | MacBook8,1                  | [89d87ca773](https://linux-hardware.org/?probe=89d87ca773) | May 09, 2023 |
| Thomson       | WWNEO14C-4BK32F             | [28a4468d2d](https://linux-hardware.org/?probe=28a4468d2d) | May 09, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [d01779a93b](https://linux-hardware.org/?probe=d01779a93b) | May 09, 2023 |
| HP            | Pavilion g6                 | [fc978d0a03](https://linux-hardware.org/?probe=fc978d0a03) | May 09, 2023 |
| HP            | Pavilion Laptop 14-dv0xx... | [745096932c](https://linux-hardware.org/?probe=745096932c) | May 09, 2023 |
| Toshiba       | Satellite P500              | [16472912d5](https://linux-hardware.org/?probe=16472912d5) | May 09, 2023 |
| HUAWEI        | KLVD-WXX9                   | [3ad22447bb](https://linux-hardware.org/?probe=3ad22447bb) | May 09, 2023 |
| MSI           | Katana 17 B12UCXK           | [15b9d97c10](https://linux-hardware.org/?probe=15b9d97c10) | May 09, 2023 |
| HP            | ProBook 440 G3              | [20365b7b02](https://linux-hardware.org/?probe=20365b7b02) | May 09, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [32fba9e487](https://linux-hardware.org/?probe=32fba9e487) | May 09, 2023 |
| Dell          | G5 5590                     | [c07c29d5de](https://linux-hardware.org/?probe=c07c29d5de) | May 09, 2023 |
| Unknown       | Unknown                     | [0225c3c300](https://linux-hardware.org/?probe=0225c3c300) | May 09, 2023 |
| Apple         | MacBookPro5,5               | [ff3919b7f3](https://linux-hardware.org/?probe=ff3919b7f3) | May 09, 2023 |
| Apple         | MacBookPro6,2               | [db93afa653](https://linux-hardware.org/?probe=db93afa653) | May 09, 2023 |
| Lanix Amer... | A V19                       | [31e64dbd5d](https://linux-hardware.org/?probe=31e64dbd5d) | May 08, 2023 |
| Samsung       | 950XED                      | [15e2cfcac7](https://linux-hardware.org/?probe=15e2cfcac7) | May 08, 2023 |
| Dell          | Latitude E5440              | [6db42a9acc](https://linux-hardware.org/?probe=6db42a9acc) | May 08, 2023 |
| ASUSTek       | X200MA                      | [1f7840b315](https://linux-hardware.org/?probe=1f7840b315) | May 08, 2023 |
| HP            | Laptop 17-cn2xxx            | [ddf0cb8a28](https://linux-hardware.org/?probe=ddf0cb8a28) | May 08, 2023 |
| Acer          | Aspire 7741                 | [995e6d9580](https://linux-hardware.org/?probe=995e6d9580) | May 08, 2023 |
| Avell High... | 1513                        | [6e383641d6](https://linux-hardware.org/?probe=6e383641d6) | May 08, 2023 |
| HP            | EliteBook 725 G4            | [bf3ce4741e](https://linux-hardware.org/?probe=bf3ce4741e) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [f4d1f788e1](https://linux-hardware.org/?probe=f4d1f788e1) | May 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X432... | [395097d3a3](https://linux-hardware.org/?probe=395097d3a3) | May 08, 2023 |
| Dell          | Latitude 7390               | [dc5c96e431](https://linux-hardware.org/?probe=dc5c96e431) | May 08, 2023 |
| Sony          | VPCZ12C5E                   | [512da95fb0](https://linux-hardware.org/?probe=512da95fb0) | May 08, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [78e63b3bd3](https://linux-hardware.org/?probe=78e63b3bd3) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | [30bd232e19](https://linux-hardware.org/?probe=30bd232e19) | May 07, 2023 |
| Dell          | Inspiron 13-7359            | [923397bc88](https://linux-hardware.org/?probe=923397bc88) | May 07, 2023 |
| Dell          | Latitude 5310               | [d72db172f0](https://linux-hardware.org/?probe=d72db172f0) | May 07, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7e003cf7a9](https://linux-hardware.org/?probe=7e003cf7a9) | May 07, 2023 |
| Dell          | MXG061                      | [8ef701b61d](https://linux-hardware.org/?probe=8ef701b61d) | May 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [816f9e047a](https://linux-hardware.org/?probe=816f9e047a) | May 07, 2023 |
| Sony          | VPCZ12C5E                   | [67e1fdf9c2](https://linux-hardware.org/?probe=67e1fdf9c2) | May 07, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [020041a666](https://linux-hardware.org/?probe=020041a666) | May 07, 2023 |
| HP            | x2 210                      | [f7a174063f](https://linux-hardware.org/?probe=f7a174063f) | May 07, 2023 |
| HP            | x2 210                      | [b3c5b71d27](https://linux-hardware.org/?probe=b3c5b71d27) | May 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b1b0fa7485](https://linux-hardware.org/?probe=b1b0fa7485) | May 07, 2023 |
| Acer          | Predator PH315-53           | [efb597952f](https://linux-hardware.org/?probe=efb597952f) | May 07, 2023 |
| Toshiba       | Satellite C855D             | [7cdcc71b4e](https://linux-hardware.org/?probe=7cdcc71b4e) | May 07, 2023 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | [845c2112be](https://linux-hardware.org/?probe=845c2112be) | May 06, 2023 |
| HP            | ENVY TS 17                  | [d18f9c3e77](https://linux-hardware.org/?probe=d18f9c3e77) | May 06, 2023 |
| Dell          | Studio 1749                 | [43eb37cfd7](https://linux-hardware.org/?probe=43eb37cfd7) | May 06, 2023 |
| Dell          | Inspiron 3537               | [5b49eec8c6](https://linux-hardware.org/?probe=5b49eec8c6) | May 06, 2023 |
| HP            | Notebook                    | [cb89261339](https://linux-hardware.org/?probe=cb89261339) | May 06, 2023 |
| ASUSTek       | X441BA                      | [326309c1f1](https://linux-hardware.org/?probe=326309c1f1) | May 06, 2023 |
| HP            | EliteBook Folio 9470m       | [20461b100d](https://linux-hardware.org/?probe=20461b100d) | May 06, 2023 |
| ASUSTek       | X441BA                      | [dee3bc2cdb](https://linux-hardware.org/?probe=dee3bc2cdb) | May 06, 2023 |
| Google        | Samus                       | [aed9bd140f](https://linux-hardware.org/?probe=aed9bd140f) | May 06, 2023 |
| Notebook      | N7x0WU                      | [985f971691](https://linux-hardware.org/?probe=985f971691) | May 06, 2023 |
| ASUSTek       | ZenBook UX434FL_UX434FL     | [21ef45e81c](https://linux-hardware.org/?probe=21ef45e81c) | May 06, 2023 |
| HP            | 250 G5 Notebook PC          | [e12a1d28ba](https://linux-hardware.org/?probe=e12a1d28ba) | May 06, 2023 |
| Dell          | Inspiron 7558               | [aab9b575d7](https://linux-hardware.org/?probe=aab9b575d7) | May 06, 2023 |
| HP            | ZBook Studio G7 Mobile W... | [b0464a0b99](https://linux-hardware.org/?probe=b0464a0b99) | May 06, 2023 |
| Packard Be... | EasyNote TE69HW             | [fff5650658](https://linux-hardware.org/?probe=fff5650658) | May 05, 2023 |
| Fujitsu Si... | AMILO Pa 2548               | [449779fbe4](https://linux-hardware.org/?probe=449779fbe4) | May 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [ec3e2f4be9](https://linux-hardware.org/?probe=ec3e2f4be9) | May 05, 2023 |
| Fujitsu Si... | AMILO Pa 2548               | [ffce6dd6d5](https://linux-hardware.org/?probe=ffce6dd6d5) | May 05, 2023 |
| Lenovo        | ThinkPad L512 44444WG       | [db330cab38](https://linux-hardware.org/?probe=db330cab38) | May 05, 2023 |
| HUAWEI        | CREM-WXX9                   | [55e2b9f062](https://linux-hardware.org/?probe=55e2b9f062) | May 05, 2023 |
| HUAWEI        | CREM-WXX9                   | [70f39dc2df](https://linux-hardware.org/?probe=70f39dc2df) | May 05, 2023 |
| Acer          | Aspire A315-23              | [2e4e7c801d](https://linux-hardware.org/?probe=2e4e7c801d) | May 05, 2023 |
| Medion        | Akoya E1317T                | [e8eb05a52a](https://linux-hardware.org/?probe=e8eb05a52a) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 4174W2X      | [082029ecf5](https://linux-hardware.org/?probe=082029ecf5) | May 05, 2023 |
| Lenovo        | ThinkPad T420s 4174W2X      | [e2f37d94cd](https://linux-hardware.org/?probe=e2f37d94cd) | May 05, 2023 |
| Acer          | Aspire A315-58              | [34a67ec7c4](https://linux-hardware.org/?probe=34a67ec7c4) | May 05, 2023 |
| ASUSTek       | G73Jh                       | [0485192408](https://linux-hardware.org/?probe=0485192408) | May 05, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | [d02d56f013](https://linux-hardware.org/?probe=d02d56f013) | May 05, 2023 |
| Lenovo        | ThinkPad T480 20L5000UUS    | [1dacd7233b](https://linux-hardware.org/?probe=1dacd7233b) | May 05, 2023 |
| Dynabook      | TECRA A50-J                 | [76a87cd7fc](https://linux-hardware.org/?probe=76a87cd7fc) | May 04, 2023 |
| Dell          | Latitude 5410               | [840aaee455](https://linux-hardware.org/?probe=840aaee455) | May 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [72336867ab](https://linux-hardware.org/?probe=72336867ab) | May 04, 2023 |
| Dell          | Latitude 5410               | [f95e1d32bf](https://linux-hardware.org/?probe=f95e1d32bf) | May 04, 2023 |
| Dell          | Latitude E5570              | [6b532c004d](https://linux-hardware.org/?probe=6b532c004d) | May 04, 2023 |
| Dell          | Latitude 5490               | [c2d5f80f6e](https://linux-hardware.org/?probe=c2d5f80f6e) | May 04, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | [a27c899176](https://linux-hardware.org/?probe=a27c899176) | May 04, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [1d74519195](https://linux-hardware.org/?probe=1d74519195) | May 04, 2023 |
| HUAWEI        | BOM-WXX9                    | [7a7021d420](https://linux-hardware.org/?probe=7a7021d420) | May 04, 2023 |
| HP            | ProBook 440 G4              | [ac499d5a17](https://linux-hardware.org/?probe=ac499d5a17) | May 04, 2023 |
| Acer          | Nitro AN515-58              | [e788d3fee0](https://linux-hardware.org/?probe=e788d3fee0) | May 04, 2023 |
| HP            | 255 G8 Notebook PC          | [af9621c92b](https://linux-hardware.org/?probe=af9621c92b) | May 04, 2023 |
| Apple         | MacBookAir7,2               | [57ad5809ad](https://linux-hardware.org/?probe=57ad5809ad) | May 04, 2023 |
| Apple         | MacBookAir7,2               | [e69ecc7c30](https://linux-hardware.org/?probe=e69ecc7c30) | May 04, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [1c26fc22d1](https://linux-hardware.org/?probe=1c26fc22d1) | May 04, 2023 |
| Notebook      | N7x0WU                      | [b11821f4a1](https://linux-hardware.org/?probe=b11821f4a1) | May 03, 2023 |
| HP            | Laptop 15-db0xxx            | [5b2534c11a](https://linux-hardware.org/?probe=5b2534c11a) | May 03, 2023 |
| MSI           | Katana GF66 11UE            | [00cae795f4](https://linux-hardware.org/?probe=00cae795f4) | May 03, 2023 |
| ASUSTek       | X751LJ                      | [708ac49447](https://linux-hardware.org/?probe=708ac49447) | May 03, 2023 |
| Dell          | Latitude 5580               | [e6c5e8bb0b](https://linux-hardware.org/?probe=e6c5e8bb0b) | May 03, 2023 |
| ASUSTek       | X751LJ                      | [66e45eac2c](https://linux-hardware.org/?probe=66e45eac2c) | May 03, 2023 |
| HUAWEI        | RLEF-XX                     | [b97932d8f1](https://linux-hardware.org/?probe=b97932d8f1) | May 03, 2023 |
| HP            | 250 G5 Notebook PC          | [4cb6025c16](https://linux-hardware.org/?probe=4cb6025c16) | May 03, 2023 |
| Packard Be... | EasyNote TE69BM             | [fc905a42fb](https://linux-hardware.org/?probe=fc905a42fb) | May 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [910824ac40](https://linux-hardware.org/?probe=910824ac40) | May 03, 2023 |
| Sony          | VPCEH14FM                   | [a21be2b066](https://linux-hardware.org/?probe=a21be2b066) | May 03, 2023 |
| MSI           | GT72S 6QE                   | [bd81a36394](https://linux-hardware.org/?probe=bd81a36394) | May 03, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [4da21d35eb](https://linux-hardware.org/?probe=4da21d35eb) | May 03, 2023 |
| Acer          | Swift SFX14-41G             | [e290126c8d](https://linux-hardware.org/?probe=e290126c8d) | May 03, 2023 |
| Lenovo        | IdeaPad Z565 4311           | [15b7663490](https://linux-hardware.org/?probe=15b7663490) | May 03, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | [56d274f769](https://linux-hardware.org/?probe=56d274f769) | May 03, 2023 |
| Dell          | Inspiron 11 - 3147          | [2e537d8cda](https://linux-hardware.org/?probe=2e537d8cda) | May 03, 2023 |
| Lenovo        | V130-15IKB 81HN             | [8c3e5e8d50](https://linux-hardware.org/?probe=8c3e5e8d50) | May 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [1e70580006](https://linux-hardware.org/?probe=1e70580006) | May 02, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [1704454cdb](https://linux-hardware.org/?probe=1704454cdb) | May 02, 2023 |
| Dell          | Latitude E7470              | [b642589c50](https://linux-hardware.org/?probe=b642589c50) | May 02, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [d2f8737b9d](https://linux-hardware.org/?probe=d2f8737b9d) | May 02, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [3ab78594e3](https://linux-hardware.org/?probe=3ab78594e3) | May 02, 2023 |
| Sony          | VPCF11C5E                   | [77f08d3d00](https://linux-hardware.org/?probe=77f08d3d00) | May 02, 2023 |
| Samsung       | 550XDA                      | [4bea46787f](https://linux-hardware.org/?probe=4bea46787f) | May 02, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [5e2f76de77](https://linux-hardware.org/?probe=5e2f76de77) | May 02, 2023 |
| HP            | Laptop 15-db0xxx            | [678f7989e8](https://linux-hardware.org/?probe=678f7989e8) | May 01, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [61ca990255](https://linux-hardware.org/?probe=61ca990255) | May 01, 2023 |
| Acer          | Aspire R5-571T              | [9d4259548f](https://linux-hardware.org/?probe=9d4259548f) | May 01, 2023 |
| Acer          | Aspire R5-571T              | [1e80e6a5fb](https://linux-hardware.org/?probe=1e80e6a5fb) | May 01, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f3e8baa565](https://linux-hardware.org/?probe=f3e8baa565) | May 01, 2023 |
| HP            | 240 G6 Notebook PC          | [3ca97c367a](https://linux-hardware.org/?probe=3ca97c367a) | May 01, 2023 |
| Panasonic     | CF-20-1                     | [a6ce7489e1](https://linux-hardware.org/?probe=a6ce7489e1) | May 01, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [e7398c9db0](https://linux-hardware.org/?probe=e7398c9db0) | May 01, 2023 |
| HP            | OMEN by Laptop              | [bfbda66d8b](https://linux-hardware.org/?probe=bfbda66d8b) | May 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [0f77b52547](https://linux-hardware.org/?probe=0f77b52547) | May 01, 2023 |
| Dell          | Latitude 3420               | [cb213cd50f](https://linux-hardware.org/?probe=cb213cd50f) | May 01, 2023 |
| Dell          | Latitude 3420               | [43edcd4b2b](https://linux-hardware.org/?probe=43edcd4b2b) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [5086f7f4a2](https://linux-hardware.org/?probe=5086f7f4a2) | May 01, 2023 |
| Dell          | Vostro 3550                 | [a644bc676e](https://linux-hardware.org/?probe=a644bc676e) | May 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [e3984b7285](https://linux-hardware.org/?probe=e3984b7285) | May 01, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [ea5b56dbca](https://linux-hardware.org/?probe=ea5b56dbca) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [7bb2ae638b](https://linux-hardware.org/?probe=7bb2ae638b) | May 01, 2023 |
| HP            | ZBook Firefly 15 inch G8... | [e67706f385](https://linux-hardware.org/?probe=e67706f385) | May 01, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | [bd0458e8a9](https://linux-hardware.org/?probe=bd0458e8a9) | May 01, 2023 |
| ASUSTek       | X550CC                      | [cc784397f9](https://linux-hardware.org/?probe=cc784397f9) | May 01, 2023 |
| Dell          | Latitude 3420               | [327be624ce](https://linux-hardware.org/?probe=327be624ce) | May 01, 2023 |
| Acer          | Aspire A715-51G             | [842333a8da](https://linux-hardware.org/?probe=842333a8da) | May 01, 2023 |
| Dell          | Latitude 3420               | [1ce0c58a17](https://linux-hardware.org/?probe=1ce0c58a17) | May 01, 2023 |
| Lenovo        | ThinkPad T480 20L6A0LJCL    | [f67154866c](https://linux-hardware.org/?probe=f67154866c) | May 01, 2023 |
| Acer          | Nitro AN517-54              | [593a6b247f](https://linux-hardware.org/?probe=593a6b247f) | May 01, 2023 |
| Acer          | Aspire A715-51G             | [4f72daaab8](https://linux-hardware.org/?probe=4f72daaab8) | May 01, 2023 |
| HP            | EliteBook 8470p             | [f75b4a9457](https://linux-hardware.org/?probe=f75b4a9457) | May 01, 2023 |
| Unknown       | Unknown                     | [8978b9aa5f](https://linux-hardware.org/?probe=8978b9aa5f) | May 01, 2023 |
| HP            | Unknown                     | [475eb33956](https://linux-hardware.org/?probe=475eb33956) | May 01, 2023 |
| Unknown       | Unknown                     | [070854df6b](https://linux-hardware.org/?probe=070854df6b) | Apr 30, 2023 |
| Lenovo        | Z50-75 80EC                 | [af5d37f4f7](https://linux-hardware.org/?probe=af5d37f4f7) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [05251702aa](https://linux-hardware.org/?probe=05251702aa) | Apr 30, 2023 |
| Lenovo        | IdeaPad L340-17API 81LY     | [44c60dcec2](https://linux-hardware.org/?probe=44c60dcec2) | Apr 30, 2023 |
| Dell          | Vostro 3558                 | [5d77d7d922](https://linux-hardware.org/?probe=5d77d7d922) | Apr 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [94118ab632](https://linux-hardware.org/?probe=94118ab632) | Apr 30, 2023 |
| HP            | Pavilion Laptop 14-ec0xx... | [d4cfc1e964](https://linux-hardware.org/?probe=d4cfc1e964) | Apr 30, 2023 |
| Dell          | XPS 13 9350                 | [95b5e79487](https://linux-hardware.org/?probe=95b5e79487) | Apr 30, 2023 |
| Acer          | Aspire E5-551G              | [bba2f8d1ad](https://linux-hardware.org/?probe=bba2f8d1ad) | Apr 30, 2023 |
| Dell          | Vostro 5468                 | [93eb16d30d](https://linux-hardware.org/?probe=93eb16d30d) | Apr 30, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [28b11100ac](https://linux-hardware.org/?probe=28b11100ac) | Apr 30, 2023 |
| Gateway       | P-7805u                     | [0958f250f2](https://linux-hardware.org/?probe=0958f250f2) | Apr 30, 2023 |
| Maibenben     | MaiBook X series            | [5f97e34b20](https://linux-hardware.org/?probe=5f97e34b20) | Apr 30, 2023 |
| Dell          | G15 5511                    | [7d5f166e7a](https://linux-hardware.org/?probe=7d5f166e7a) | Apr 30, 2023 |
| Dell          | XPS 13 7390                 | [c5000ec967](https://linux-hardware.org/?probe=c5000ec967) | Apr 30, 2023 |
| Lenovo        | V130-15IGM 81HL             | [ff24454021](https://linux-hardware.org/?probe=ff24454021) | Apr 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [272103e5a7](https://linux-hardware.org/?probe=272103e5a7) | Apr 29, 2023 |
| ASUSTek       | G56JR                       | [b7eb868ec4](https://linux-hardware.org/?probe=b7eb868ec4) | Apr 29, 2023 |
| Acer          | TravelMate 5730             | [e74d115d0d](https://linux-hardware.org/?probe=e74d115d0d) | Apr 29, 2023 |
| Lenovo        | V130-15IGM 81HL             | [9081fc703d](https://linux-hardware.org/?probe=9081fc703d) | Apr 29, 2023 |
| Dell          | Inspiron 7773               | [19741ac2ea](https://linux-hardware.org/?probe=19741ac2ea) | Apr 29, 2023 |
| Acer          | Aspire A515-51G             | [bd4c84da60](https://linux-hardware.org/?probe=bd4c84da60) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [21d008c7d8](https://linux-hardware.org/?probe=21d008c7d8) | Apr 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [49557b8214](https://linux-hardware.org/?probe=49557b8214) | Apr 29, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21CH0... | [7598c18042](https://linux-hardware.org/?probe=7598c18042) | Apr 29, 2023 |
| Dell          | Latitude E5470              | [c6c943679f](https://linux-hardware.org/?probe=c6c943679f) | Apr 29, 2023 |
| ASUSTek       | X756UVK                     | [72ba8fbf57](https://linux-hardware.org/?probe=72ba8fbf57) | Apr 29, 2023 |
| Dell          | Latitude 3301               | [3a0aad0e75](https://linux-hardware.org/?probe=3a0aad0e75) | Apr 29, 2023 |
| Dell          | Precision M6600             | [39d9af4736](https://linux-hardware.org/?probe=39d9af4736) | Apr 28, 2023 |
| Dell          | Inspiron 3180               | [bc3400a372](https://linux-hardware.org/?probe=bc3400a372) | Apr 28, 2023 |
| Dell          | Inspiron 15-3567            | [5dcd15cacf](https://linux-hardware.org/?probe=5dcd15cacf) | Apr 28, 2023 |
| Dell          | Latitude E5450              | [85fb3ec2fd](https://linux-hardware.org/?probe=85fb3ec2fd) | Apr 28, 2023 |
| Acer          | Aspire ES1-731              | [140e5eb8fc](https://linux-hardware.org/?probe=140e5eb8fc) | Apr 28, 2023 |
| Acer          | Swift SF314-57G             | [6fd79b811f](https://linux-hardware.org/?probe=6fd79b811f) | Apr 28, 2023 |
| HP            | Laptop 15-ef2xxx            | [f922f80a69](https://linux-hardware.org/?probe=f922f80a69) | Apr 28, 2023 |
| Pegatron      | A15                         | [e9de945dce](https://linux-hardware.org/?probe=e9de945dce) | Apr 28, 2023 |
| Lenovo        | ThinkPad L480 20LTS1NK27    | [6569669912](https://linux-hardware.org/?probe=6569669912) | Apr 28, 2023 |
| Lenovo        | V15 G2 ITL Ua 82KB          | [65f390b956](https://linux-hardware.org/?probe=65f390b956) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [a72fdebd89](https://linux-hardware.org/?probe=a72fdebd89) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [31bdde77c9](https://linux-hardware.org/?probe=31bdde77c9) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [eb550390c1](https://linux-hardware.org/?probe=eb550390c1) | Apr 28, 2023 |
| Dell          | Latitude 3301               | [855564b077](https://linux-hardware.org/?probe=855564b077) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | [7c34e35183](https://linux-hardware.org/?probe=7c34e35183) | Apr 28, 2023 |
| ASUSTek       | T100TA                      | [266477f792](https://linux-hardware.org/?probe=266477f792) | Apr 28, 2023 |
| Apple         | MacBookPro6,2               | [ceaa38e624](https://linux-hardware.org/?probe=ceaa38e624) | Apr 28, 2023 |
| Gigabyte      | G5 GD                       | [d09d6fb712](https://linux-hardware.org/?probe=d09d6fb712) | Apr 27, 2023 |
| HP            | Compaq 6910p                | [049253c0c8](https://linux-hardware.org/?probe=049253c0c8) | Apr 27, 2023 |
| TUXEDO        | Unknown                     | [5108a05d49](https://linux-hardware.org/?probe=5108a05d49) | Apr 27, 2023 |
| Dell          | XPS 13 7390                 | [318ea8ad1e](https://linux-hardware.org/?probe=318ea8ad1e) | Apr 27, 2023 |
| Dell          | XPS 15 9520                 | [07572e6599](https://linux-hardware.org/?probe=07572e6599) | Apr 27, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [f428173506](https://linux-hardware.org/?probe=f428173506) | Apr 27, 2023 |
| Lenovo        | V14 G2 ITL 82NM             | [6a56164bfd](https://linux-hardware.org/?probe=6a56164bfd) | Apr 27, 2023 |
| HP            | Pavilion Laptop 15-cc5xx    | [9344f38032](https://linux-hardware.org/?probe=9344f38032) | Apr 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [393c7b06d5](https://linux-hardware.org/?probe=393c7b06d5) | Apr 26, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [e35780d356](https://linux-hardware.org/?probe=e35780d356) | Apr 26, 2023 |
| Toshiba       | Satellite Pro S500          | [7a2503959a](https://linux-hardware.org/?probe=7a2503959a) | Apr 26, 2023 |
| Lenovo        | ThinkPad X250 20CLA003TA    | [ea8109c2a7](https://linux-hardware.org/?probe=ea8109c2a7) | Apr 26, 2023 |
| Sony          | SVD1322X2EW                 | [2574ef07fb](https://linux-hardware.org/?probe=2574ef07fb) | Apr 26, 2023 |
| Acer          | Aspire A515-45              | [d910b01835](https://linux-hardware.org/?probe=d910b01835) | Apr 26, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [3c104a89ef](https://linux-hardware.org/?probe=3c104a89ef) | Apr 26, 2023 |
| Dell          | Vostro 15 3510              | [81cae0ba77](https://linux-hardware.org/?probe=81cae0ba77) | Apr 26, 2023 |
| Dell          | XPS 15 9500                 | [e37d368767](https://linux-hardware.org/?probe=e37d368767) | Apr 26, 2023 |
| HP            | EliteBook Folio 9470m       | [e0d69966e9](https://linux-hardware.org/?probe=e0d69966e9) | Apr 26, 2023 |
| ASUSTek       | ROG Strix G731GT_GL731GT    | [940cbb6ef0](https://linux-hardware.org/?probe=940cbb6ef0) | Apr 26, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [5daf26faca](https://linux-hardware.org/?probe=5daf26faca) | Apr 26, 2023 |
| System76      | Gazelle                     | [dbf4d8b33d](https://linux-hardware.org/?probe=dbf4d8b33d) | Apr 26, 2023 |
| Dell          | Precision M6600             | [4f5cd6d28e](https://linux-hardware.org/?probe=4f5cd6d28e) | Apr 26, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [c9ef115a29](https://linux-hardware.org/?probe=c9ef115a29) | Apr 26, 2023 |
| Lenovo        | ThinkPad T430 2349UKM       | [6adb010c7a](https://linux-hardware.org/?probe=6adb010c7a) | Apr 25, 2023 |
| Acer          | Aspire E1-571               | [c6a1179816](https://linux-hardware.org/?probe=c6a1179816) | Apr 25, 2023 |
| Timi          | Mi NoteBook Ultra           | [b6b7cdfe22](https://linux-hardware.org/?probe=b6b7cdfe22) | Apr 25, 2023 |
| Acer          | Nitro AN517-42              | [5e54d08f91](https://linux-hardware.org/?probe=5e54d08f91) | Apr 25, 2023 |
| Avell High... | A70 HYB BS                  | [c7b5f9ef04](https://linux-hardware.org/?probe=c7b5f9ef04) | Apr 25, 2023 |
| Dell          | XPS 13 9310                 | [b9bc4703a8](https://linux-hardware.org/?probe=b9bc4703a8) | Apr 25, 2023 |
| Acer          | Aspire 5920G                | [c6387003fc](https://linux-hardware.org/?probe=c6387003fc) | Apr 25, 2023 |
| Dell          | Latitude 5490               | [32ddaf898c](https://linux-hardware.org/?probe=32ddaf898c) | Apr 25, 2023 |
| HP            | 255 G5 Notebook PC          | [c542c2df7e](https://linux-hardware.org/?probe=c542c2df7e) | Apr 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [3a7c24a13f](https://linux-hardware.org/?probe=3a7c24a13f) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d5bd7e8fa](https://linux-hardware.org/?probe=7d5bd7e8fa) | Apr 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [24bf298df5](https://linux-hardware.org/?probe=24bf298df5) | Apr 25, 2023 |
| Lenovo        | ThinkPad Edge E545 20B20... | [fd66f3852a](https://linux-hardware.org/?probe=fd66f3852a) | Apr 25, 2023 |
| Notebook      | W650EH                      | [8e848e589e](https://linux-hardware.org/?probe=8e848e589e) | Apr 25, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [1602540ab8](https://linux-hardware.org/?probe=1602540ab8) | Apr 25, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [5fd25f9235](https://linux-hardware.org/?probe=5fd25f9235) | Apr 25, 2023 |
| ASUSTek       | PRIME X670-P                | [37f98c9450](https://linux-hardware.org/?probe=37f98c9450) | Apr 25, 2023 |
| Dell          | Inspiron 3543               | [2a3020f392](https://linux-hardware.org/?probe=2a3020f392) | Apr 24, 2023 |
| ASUSTek       | X510UQR                     | [4a2e357ace](https://linux-hardware.org/?probe=4a2e357ace) | Apr 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9e926f5c65](https://linux-hardware.org/?probe=9e926f5c65) | Apr 24, 2023 |
| Dell          | Vostro 15 3515              | [13c75fa32e](https://linux-hardware.org/?probe=13c75fa32e) | Apr 24, 2023 |
| INSYS         | PT1-140C                    | [902536abce](https://linux-hardware.org/?probe=902536abce) | Apr 24, 2023 |
| Lenovo        | G700                        | [75ee4cf99d](https://linux-hardware.org/?probe=75ee4cf99d) | Apr 24, 2023 |
| Dell          | System XPS L502X            | [4fd4992d0f](https://linux-hardware.org/?probe=4fd4992d0f) | Apr 24, 2023 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [253f35c2c3](https://linux-hardware.org/?probe=253f35c2c3) | Apr 24, 2023 |
| Dell          | Inspiron 15 5510            | [c8f22361f6](https://linux-hardware.org/?probe=c8f22361f6) | Apr 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [2787d97e6e](https://linux-hardware.org/?probe=2787d97e6e) | Apr 24, 2023 |
| Fujitsu       | LIFEBOOK S751               | [e01b26f35f](https://linux-hardware.org/?probe=e01b26f35f) | Apr 24, 2023 |
| HP            | Laptop 15-db0xxx            | [2ab42d58bf](https://linux-hardware.org/?probe=2ab42d58bf) | Apr 24, 2023 |
| HP            | Laptop 15-db0xxx            | [8c5aea6211](https://linux-hardware.org/?probe=8c5aea6211) | Apr 24, 2023 |
| Dell          | Inspiron 3542               | [9f4ce3c5a4](https://linux-hardware.org/?probe=9f4ce3c5a4) | Apr 24, 2023 |
| LG Electro... | 16Z90Q-G.AD78F              | [99bbc09adb](https://linux-hardware.org/?probe=99bbc09adb) | Apr 24, 2023 |
| Lenovo        | ThinkPad T440s 20ARS16G0... | [b019f5af89](https://linux-hardware.org/?probe=b019f5af89) | Apr 24, 2023 |
| HP            | ProBook 450 G7              | [57f0ae7486](https://linux-hardware.org/?probe=57f0ae7486) | Apr 24, 2023 |
| ASUSTek       | PRIME X670-P                | [ebe7f36c99](https://linux-hardware.org/?probe=ebe7f36c99) | Apr 23, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | [e562ba35c6](https://linux-hardware.org/?probe=e562ba35c6) | Apr 23, 2023 |
| HP            | 350 G2                      | [ffa4ab3dc0](https://linux-hardware.org/?probe=ffa4ab3dc0) | Apr 23, 2023 |
| Samsung       | R510/P510                   | [4b58936ad7](https://linux-hardware.org/?probe=4b58936ad7) | Apr 23, 2023 |
| HP            | G42                         | [1d5b2eefc3](https://linux-hardware.org/?probe=1d5b2eefc3) | Apr 23, 2023 |
| Lenovo        | ThinkPad X220 4290EC5       | [f6fe80f275](https://linux-hardware.org/?probe=f6fe80f275) | Apr 23, 2023 |
| MSI           | Bravo 15 B5DD               | [180f1dd402](https://linux-hardware.org/?probe=180f1dd402) | Apr 23, 2023 |
| Dell          | Latitude 5591               | [b4dfa57eea](https://linux-hardware.org/?probe=b4dfa57eea) | Apr 23, 2023 |
| Sony          | SVD1322X2EW                 | [1652ce4c8f](https://linux-hardware.org/?probe=1652ce4c8f) | Apr 23, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [18fc5f09ed](https://linux-hardware.org/?probe=18fc5f09ed) | Apr 23, 2023 |
| Dell          | Latitude 5591               | [1a45f96f80](https://linux-hardware.org/?probe=1a45f96f80) | Apr 23, 2023 |
| Acer          | Aspire A515-57              | [23f076b6d3](https://linux-hardware.org/?probe=23f076b6d3) | Apr 23, 2023 |
| HP            | Pavilion dv7                | [0ca422761e](https://linux-hardware.org/?probe=0ca422761e) | Apr 23, 2023 |
| Dell          | Latitude E7240              | [1b5828d441](https://linux-hardware.org/?probe=1b5828d441) | Apr 23, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Ubuntu_22.04/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 5.15.0-56-generic     | 422       | 7.26%   |
| 5.15.0-52-generic     | 373       | 6.42%   |
| 5.15.0-58-generic     | 345       | 5.94%   |
| 5.15.0-48-generic     | 292       | 5.03%   |
| 5.15.0-43-generic     | 286       | 4.92%   |
| 5.19.0-35-generic     | 274       | 4.72%   |
| 5.19.0-32-generic     | 268       | 4.61%   |
| 5.15.0-47-generic     | 254       | 4.37%   |
| 5.15.0-46-generic     | 234       | 4.03%   |
| 5.19.0-41-generic     | 233       | 4.01%   |
| 5.15.0-53-generic     | 211       | 3.63%   |
| 5.19.0-38-generic     | 197       | 3.39%   |
| 5.15.0-25-generic     | 185       | 3.18%   |
| 5.15.0-27-generic     | 175       | 3.01%   |
| 5.15.0-41-generic     | 166       | 2.86%   |
| 5.15.0-40-generic     | 156       | 2.69%   |
| 5.19.0-43-generic     | 153       | 2.63%   |
| 5.15.0-50-generic     | 145       | 2.5%    |
| 5.15.0-60-generic     | 127       | 2.19%   |
| 5.15.0-33-generic     | 108       | 1.86%   |
| 5.19.0-45-generic     | 104       | 1.79%   |
| 5.15.0-57-generic     | 103       | 1.77%   |
| 5.19.0-40-generic     | 88        | 1.51%   |
| 5.15.0-30-generic     | 87        | 1.5%    |
| 5.15.0-39-generic     | 73        | 1.26%   |
| 5.19.0-42-generic     | 72        | 1.24%   |
| 5.15.0-37-generic     | 57        | 0.98%   |
| 5.15.0-35-generic     | 46        | 0.79%   |
| 5.15.0-71-generic     | 29        | 0.5%    |
| 5.15.0-67-generic     | 24        | 0.41%   |
| 5.15.0-23-generic     | 21        | 0.36%   |
| 5.15.0-69-generic     | 20        | 0.34%   |
| 5.15.0-18-generic     | 13        | 0.22%   |
| 5.19.0-46-generic     | 11        | 0.19%   |
| 5.15.0-73-generic     | 11        | 0.19%   |
| 5.15.0-59-generic     | 11        | 0.19%   |
| 5.15.0-72-generic     | 10        | 0.17%   |
| 5.17.0-1019-oem       | 8         | 0.14%   |
| 5.15.0-54-generic     | 8         | 0.14%   |
| 6.2.11-060211-generic | 7         | 0.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.0  | 3810      | 69.54%  |
| 5.19.0  | 1353      | 24.69%  |
| 5.17.0  | 57        | 1.04%   |
| 5.14.0  | 30        | 0.55%   |
| 6.0.0   | 17        | 0.31%   |
| 5.13.0  | 13        | 0.24%   |
| 6.1.0   | 12        | 0.22%   |
| 5.18.0  | 9         | 0.16%   |
| 6.2.0   | 8         | 0.15%   |
| 6.2.11  | 7         | 0.13%   |
| 5.19.5  | 7         | 0.13%   |
| 5.17.1  | 7         | 0.13%   |
| 6.3.1   | 6         | 0.11%   |
| 6.2.2   | 6         | 0.11%   |
| 6.0.9   | 6         | 0.11%   |
| 6.2.8   | 5         | 0.09%   |
| 5.17.5  | 5         | 0.09%   |
| 6.2.10  | 4         | 0.07%   |
| 6.0.6   | 4         | 0.07%   |
| 5.13.19 | 4         | 0.07%   |
| 6.3.3   | 3         | 0.05%   |
| 6.2.9   | 3         | 0.05%   |
| 6.2.6   | 3         | 0.05%   |
| 6.1.12  | 3         | 0.05%   |
| 5.4.0   | 3         | 0.05%   |
| 5.18.8  | 3         | 0.05%   |
| 5.17.9  | 3         | 0.05%   |
| 5.17.8  | 3         | 0.05%   |
| 5.17.2  | 3         | 0.05%   |
| 5.16.0  | 3         | 0.05%   |
| 6.3.7   | 2         | 0.04%   |
| 6.2.7   | 2         | 0.04%   |
| 6.2.5   | 2         | 0.04%   |
| 6.2.1   | 2         | 0.04%   |
| 6.1.9   | 2         | 0.04%   |
| 6.0.7   | 2         | 0.04%   |
| 6.0.2   | 2         | 0.04%   |
| 5.19.3  | 2         | 0.04%   |
| 5.19.11 | 2         | 0.04%   |
| 5.18.6  | 2         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 3822      | 69.83%  |
| 5.19    | 1368      | 25%     |
| 5.17    | 85        | 1.55%   |
| 6.2     | 42        | 0.77%   |
| 6.0     | 35        | 0.64%   |
| 5.14    | 30        | 0.55%   |
| 5.18    | 25        | 0.46%   |
| 6.1     | 23        | 0.42%   |
| 5.13    | 17        | 0.31%   |
| 6.3     | 13        | 0.24%   |
| 5.16    | 5         | 0.09%   |
| 5.4     | 3         | 0.05%   |
| 5.11    | 2         | 0.04%   |
| 6       | 1         | 0.02%   |
| 5.8     | 1         | 0.02%   |
| 5.10    | 1         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 5341      | 99.98%  |
| aarch64 | 1         | 0.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| GNOME             | 5144      | 96.1%   |
| Unknown           | 106       | 1.98%   |
| X-Cinnamon        | 37        | 0.69%   |
| GNOME Flashback   | 29        | 0.54%   |
| i3                | 11        | 0.21%   |
| GNOME Classic     | 7         | 0.13%   |
| sway              | 4         | 0.07%   |
| Cinnamon          | 4         | 0.07%   |
| awesome           | 3         | 0.06%   |
| dwm               | 2         | 0.04%   |
| Yaru:ubuntu:GNOME | 1         | 0.02%   |
| xsession          | 1         | 0.02%   |
| ratflow           | 1         | 0.02%   |
| Pantheon          | 1         | 0.02%   |
| GNUstep           | 1         | 0.02%   |
| fluxbox           | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 3725      | 68.71%  |
| X11     | 1563      | 28.83%  |
| Unknown | 92        | 1.7%    |
| Tty     | 41        | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM3    | 4942      | 92.17%  |
| Unknown | 305       | 5.69%   |
| LightDM | 68        | 1.27%   |
| GDM     | 23        | 0.43%   |
| SDDM    | 19        | 0.35%   |
| SLiM    | 4         | 0.07%   |
| XDM     | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 2503      | 46.72%  |
| de_DE   | 409       | 7.63%   |
| fr_FR   | 320       | 5.97%   |
| en_GB   | 260       | 4.85%   |
| pt_BR   | 216       | 4.03%   |
| en_IN   | 192       | 3.58%   |
| it_IT   | 179       | 3.34%   |
| ru_RU   | 142       | 2.65%   |
| es_ES   | 130       | 2.43%   |
| en_CA   | 111       | 2.07%   |
| pl_PL   | 78        | 1.46%   |
| en_AU   | 58        | 1.08%   |
| nl_NL   | 51        | 0.95%   |
| zh_CN   | 41        | 0.77%   |
| Unknown | 39        | 0.73%   |
| hu_HU   | 38        | 0.71%   |
| es_MX   | 38        | 0.71%   |
| en_ZA   | 33        | 0.62%   |
| es_AR   | 31        | 0.58%   |
| C       | 31        | 0.58%   |
| cs_CZ   | 30        | 0.56%   |
| pt_PT   | 27        | 0.5%    |
| tr_TR   | 23        | 0.43%   |
| sv_SE   | 23        | 0.43%   |
| de_AT   | 21        | 0.39%   |
| es_CO   | 20        | 0.37%   |
| en_PH   | 17        | 0.32%   |
| de_CH   | 17        | 0.32%   |
| es_CL   | 14        | 0.26%   |
| en_NZ   | 14        | 0.26%   |
| da_DK   | 14        | 0.26%   |
| fr_BE   | 13        | 0.24%   |
| ko_KR   | 12        | 0.22%   |
| ja_JP   | 12        | 0.22%   |
| fi_FI   | 12        | 0.22%   |
| en_IL   | 12        | 0.22%   |
| ro_RO   | 11        | 0.21%   |
| nb_NO   | 11        | 0.21%   |
| en_IE   | 11        | 0.21%   |
| en_SG   | 8         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 2943      | 54.54%  |
| EFI  | 2453      | 45.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 4725      | 87.42%  |
| Tmpfs   | 338       | 6.25%   |
| Overlay | 141       | 2.61%   |
| Zfs     | 128       | 2.37%   |
| Btrfs   | 47        | 0.87%   |
| Xfs     | 10        | 0.19%   |
| Ext3    | 8         | 0.15%   |
| Ext2    | 7         | 0.13%   |
| XXX4    | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 3804      | 70.17%  |
| Unknown | 1232      | 22.73%  |
| MBR     | 385       | 7.1%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 4948      | 91.95%  |
| Yes       | 433       | 8.05%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3449      | 64.22%  |
| Yes       | 1922      | 35.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 1093      | 20.46%  |
| Hewlett-Packard        | 992       | 18.57%  |
| Dell                   | 923       | 17.28%  |
| ASUSTek Computer       | 558       | 10.45%  |
| Acer                   | 418       | 7.82%   |
| Apple                  | 155       | 2.9%    |
| MSI                    | 148       | 2.77%   |
| HUAWEI                 | 129       | 2.41%   |
| Toshiba                | 112       | 2.1%    |
| Samsung Electronics    | 85        | 1.59%   |
| Sony                   | 55        | 1.03%   |
| Notebook               | 45        | 0.84%   |
| Unknown                | 41        | 0.77%   |
| Timi                   | 37        | 0.69%   |
| Fujitsu                | 34        | 0.64%   |
| Google                 | 33        | 0.62%   |
| Alienware              | 33        | 0.62%   |
| Medion                 | 24        | 0.45%   |
| Packard Bell           | 21        | 0.39%   |
| Positivo               | 19        | 0.36%   |
| LG Electronics         | 19        | 0.36%   |
| Chuwi                  | 19        | 0.36%   |
| TUXEDO                 | 17        | 0.32%   |
| System76               | 14        | 0.26%   |
| Gigabyte Technology    | 14        | 0.26%   |
| Avell High Performance | 13        | 0.24%   |
| Razer                  | 12        | 0.22%   |
| HONOR                  | 12        | 0.22%   |
| Gateway                | 12        | 0.22%   |
| Framework              | 12        | 0.22%   |
| Teclast                | 9         | 0.17%   |
| Schenker               | 9         | 0.17%   |
| Panasonic              | 8         | 0.15%   |
| AZW                    | 8         | 0.15%   |
| GPU Company            | 7         | 0.13%   |
| PC Specialist          | 6         | 0.11%   |
| Monster                | 6         | 0.11%   |
| Jumper                 | 6         | 0.11%   |
| Intel                  | 6         | 0.11%   |
| AMI                    | 6         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 57        | 1.07%   |
| HP Notebook                     | 25        | 0.47%   |
| Dell Latitude 5420              | 18        | 0.34%   |
| HP Pavilion Notebook            | 16        | 0.3%    |
| Dell XPS 15 9520                | 16        | 0.3%    |
| HUAWEI HVY-WXX9                 | 15        | 0.28%   |
| HP Pavilion dv7                 | 15        | 0.28%   |
| HP EliteBook 840 G8 Notebook PC | 15        | 0.28%   |
| HP Pavilion g6                  | 14        | 0.26%   |
| HP Pavilion dv6                 | 14        | 0.26%   |
| HP 15                           | 14        | 0.26%   |
| HP EliteBook 840 G5             | 13        | 0.24%   |
| HP EliteBook 840 G3             | 13        | 0.24%   |
| HUAWEI BOM-WXX9                 | 12        | 0.22%   |
| HUAWEI BOHB-WAX9                | 12        | 0.22%   |
| HP Pavilion 15                  | 12        | 0.22%   |
| Dell XPS 15 9500                | 12        | 0.22%   |
| HUAWEI NBLK-WAX9X               | 11        | 0.21%   |
| HUAWEI NBLB-WAX9N               | 11        | 0.21%   |
| HUAWEI BOD-WXX9                 | 11        | 0.21%   |
| HP Pavilion g7                  | 11        | 0.21%   |
| HP EliteBook 8470p              | 11        | 0.21%   |
| Dell XPS 9320                   | 11        | 0.21%   |
| Dell XPS 13 9380                | 11        | 0.21%   |
| Dell XPS 13 9370                | 11        | 0.21%   |
| Dell Latitude 7420              | 11        | 0.21%   |
| Acer Aspire E5-571              | 11        | 0.21%   |
| Timi TM1701                     | 10        | 0.19%   |
| Lenovo ThinkBook 15 G2 ITL 20VE | 10        | 0.19%   |
| HP Laptop 15s-eq2xxx            | 10        | 0.19%   |
| HP Laptop 15-db0xxx             | 10        | 0.19%   |
| Dell XPS 15 9570                | 10        | 0.19%   |
| Dell XPS 15 7590                | 10        | 0.19%   |
| Dell XPS 13 7390                | 10        | 0.19%   |
| Dell Vostro 3500                | 10        | 0.19%   |
| Dell Latitude E7470             | 10        | 0.19%   |
| Dell G15 5510                   | 10        | 0.19%   |
| Apple MacBookPro9,2             | 10        | 0.19%   |
| HP EliteBook 8460p              | 9         | 0.17%   |
| HP EliteBook 840 G1             | 9         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 539       | 10.09%  |
| Dell Latitude         | 329       | 6.16%   |
| Acer Aspire           | 284       | 5.32%   |
| Lenovo IdeaPad        | 266       | 4.98%   |
| Dell Inspiron         | 231       | 4.32%   |
| HP Pavilion           | 200       | 3.74%   |
| HP EliteBook          | 193       | 3.61%   |
| ASUS VivoBook         | 152       | 2.85%   |
| Dell XPS              | 148       | 2.77%   |
| HP ProBook            | 146       | 2.73%   |
| HP Laptop             | 145       | 2.71%   |
| Toshiba Satellite     | 88        | 1.65%   |
| Dell Precision        | 82        | 1.54%   |
| Dell Vostro           | 75        | 1.4%    |
| Lenovo ThinkBook      | 65        | 1.22%   |
| Unknown               | 57        | 1.07%   |
| Lenovo Legion         | 54        | 1.01%   |
| ASUS ZenBook          | 54        | 1.01%   |
| ASUS ROG              | 53        | 0.99%   |
| HP ZBook              | 48        | 0.9%    |
| Acer Swift            | 45        | 0.84%   |
| HP ENVY               | 44        | 0.82%   |
| ASUS ASUS             | 41        | 0.77%   |
| Acer Nitro            | 36        | 0.67%   |
| Fujitsu LIFEBOOK      | 29        | 0.54%   |
| HP OMEN               | 26        | 0.49%   |
| HP Notebook           | 26        | 0.49%   |
| Dell G15              | 26        | 0.49%   |
| HP 250                | 23        | 0.43%   |
| Lenovo Yoga           | 21        | 0.39%   |
| HP 255                | 20        | 0.37%   |
| HP 15                 | 20        | 0.37%   |
| Packard Bell EasyNote | 19        | 0.36%   |
| HP Compaq             | 17        | 0.32%   |
| Apple MacBookPro8     | 17        | 0.32%   |
| Apple MacBookPro11    | 17        | 0.32%   |
| Acer TravelMate       | 17        | 0.32%   |
| MSI Stealth           | 16        | 0.3%    |
| MSI Prestige          | 16        | 0.3%    |
| MSI Modern            | 15        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 867       | 16.23%  |
| 2020    | 657       | 12.3%   |
| 2019    | 482       | 9.02%   |
| 2022    | 457       | 8.55%   |
| 2018    | 397       | 7.43%   |
| 2013    | 329       | 6.16%   |
| 2017    | 309       | 5.78%   |
| 2012    | 308       | 5.77%   |
| 2011    | 286       | 5.35%   |
| 2014    | 268       | 5.02%   |
| 2016    | 244       | 4.57%   |
| 2015    | 244       | 4.57%   |
| 2010    | 215       | 4.02%   |
| 2008    | 108       | 2.02%   |
| 2009    | 97        | 1.82%   |
| 2007    | 35        | 0.66%   |
| 2023    | 22        | 0.41%   |
| 2006    | 12        | 0.22%   |
| Unknown | 5         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 5342      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 4619      | 85.93%  |
| Enabled  | 756       | 14.07%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 5300      | 99.21%  |
| Yes  | 42        | 0.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 1624      | 30.33%  |
| 16.01-24.0  | 1170      | 21.85%  |
| 3.01-4.0    | 883       | 16.49%  |
| 8.01-16.0   | 868       | 16.21%  |
| 32.01-64.0  | 478       | 8.93%   |
| 1.01-2.0    | 99        | 1.85%   |
| 64.01-256.0 | 96        | 1.79%   |
| 24.01-32.0  | 86        | 1.61%   |
| 2.01-3.0    | 47        | 0.88%   |
| 0.51-1.0    | 3         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 1776      | 31.71%  |
| 1.01-2.0   | 1510      | 26.96%  |
| 4.01-8.0   | 1034      | 18.46%  |
| 3.01-4.0   | 909       | 16.23%  |
| 8.01-16.0  | 282       | 5.04%   |
| 0.51-1.0   | 38        | 0.68%   |
| 16.01-24.0 | 32        | 0.57%   |
| 24.01-32.0 | 11        | 0.2%    |
| 32.01-64.0 | 4         | 0.07%   |
| 0.01-0.5   | 4         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 4136      | 76.81%  |
| 2      | 1105      | 20.52%  |
| 3      | 93        | 1.73%   |
| 0      | 36        | 0.67%   |
| 4      | 11        | 0.2%    |
| 7      | 2         | 0.04%   |
| 5      | 2         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 3882      | 72.49%  |
| Yes       | 1473      | 27.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4017      | 75.04%  |
| No        | 1336      | 24.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5259      | 98.41%  |
| No        | 85        | 1.59%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 4423      | 82.27%  |
| No        | 953       | 17.73%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 813       | 15.16%  |
| Germany      | 544       | 10.15%  |
| France       | 385       | 7.18%   |
| Brazil       | 300       | 5.59%   |
| Italy        | 269       | 5.02%   |
| India        | 217       | 4.05%   |
| UK           | 210       | 3.92%   |
| Russia       | 207       | 3.86%   |
| Spain        | 157       | 2.93%   |
| Poland       | 155       | 2.89%   |
| Canada       | 127       | 2.37%   |
| Netherlands  | 126       | 2.35%   |
| Mexico       | 80        | 1.49%   |
| Turkey       | 77        | 1.44%   |
| Sweden       | 70        | 1.31%   |
| Hungary      | 68        | 1.27%   |
| Argentina    | 61        | 1.14%   |
| Belgium      | 55        | 1.03%   |
| Portugal     | 53        | 0.99%   |
| Czechia      | 53        | 0.99%   |
| Australia    | 53        | 0.99%   |
| Switzerland  | 52        | 0.97%   |
| Austria      | 51        | 0.95%   |
| Romania      | 49        | 0.91%   |
| China        | 45        | 0.84%   |
| Indonesia    | 44        | 0.82%   |
| Greece       | 41        | 0.76%   |
| Colombia     | 39        | 0.73%   |
| South Africa | 35        | 0.65%   |
| Denmark      | 34        | 0.63%   |
| Finland      | 32        | 0.6%    |
| Chile        | 30        | 0.56%   |
| Bulgaria     | 30        | 0.56%   |
| Iran         | 29        | 0.54%   |
| Egypt        | 29        | 0.54%   |
| Pakistan     | 28        | 0.52%   |
| Ukraine      | 25        | 0.47%   |
| South Korea  | 25        | 0.47%   |
| Serbia       | 25        | 0.47%   |
| Japan        | 24        | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Paris             | 62        | 1.12%   |
| Berlin            | 59        | 1.07%   |
| Moscow            | 54        | 0.98%   |
| Milan             | 49        | 0.89%   |
| Warsaw            | 40        | 0.72%   |
| Madrid            | 40        | 0.72%   |
| St Petersburg     | 39        | 0.71%   |
| Budapest          | 36        | 0.65%   |
| Sao Paulo         | 33        | 0.6%    |
| Rome              | 33        | 0.6%    |
| Vienna            | 29        | 0.53%   |
| Istanbul          | 27        | 0.49%   |
| Bengaluru         | 24        | 0.43%   |
| Barcelona         | 24        | 0.43%   |
| Munich            | 23        | 0.42%   |
| Rio de Janeiro    | 22        | 0.4%    |
| Nairobi           | 21        | 0.38%   |
| Amsterdam         | 21        | 0.38%   |
| London            | 20        | 0.36%   |
| Hamburg           | 20        | 0.36%   |
| Frankfurt am Main | 20        | 0.36%   |
| Tehran            | 19        | 0.34%   |
| Prague            | 19        | 0.34%   |
| Helsinki          | 19        | 0.34%   |
| Athens            | 19        | 0.34%   |
| Mexico City       | 18        | 0.33%   |
| Denver            | 18        | 0.33%   |
| Bogotá           | 18        | 0.33%   |
| Sydney            | 17        | 0.31%   |
| Stockholm         | 17        | 0.31%   |
| Santiago          | 17        | 0.31%   |
| Los Angeles       | 17        | 0.31%   |
| Dublin            | 17        | 0.31%   |
| Cape Town         | 17        | 0.31%   |
| Belgrade          | 17        | 0.31%   |
| Wroclaw           | 16        | 0.29%   |
| Chennai           | 16        | 0.29%   |
| New York          | 15        | 0.27%   |
| Cairo             | 15        | 0.27%   |
| Ankara            | 15        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1129      | 1334   | 17.66%  |
| WDC                         | 637       | 730    | 9.97%   |
| Seagate                     | 527       | 616    | 8.24%   |
| Toshiba                     | 417       | 461    | 6.52%   |
| SanDisk                     | 406       | 474    | 6.35%   |
| SK hynix                    | 342       | 369    | 5.35%   |
| Kingston                    | 323       | 359    | 5.05%   |
| Unknown                     | 300       | 360    | 4.69%   |
| Micron Technology           | 269       | 287    | 4.21%   |
| Intel                       | 238       | 286    | 3.72%   |
| Crucial                     | 197       | 222    | 3.08%   |
| KIOXIA                      | 151       | 163    | 2.36%   |
| HGST                        | 144       | 156    | 2.25%   |
| Hitachi                     | 140       | 166    | 2.19%   |
| Apple                       | 91        | 104    | 1.42%   |
| A-DATA Technology           | 89        | 100    | 1.39%   |
| Phison                      | 66        | 73     | 1.03%   |
| Unknown                     | 55        | 56     | 0.86%   |
| China                       | 49        | 59     | 0.77%   |
| LITEON                      | 41        | 43     | 0.64%   |
| SPCC                        | 35        | 41     | 0.55%   |
| Silicon Motion              | 34        | 40     | 0.53%   |
| Intenso                     | 31        | 40     | 0.48%   |
| Kingston Technology Company | 29        | 34     | 0.45%   |
| Netac                       | 27        | 29     | 0.42%   |
| SSSTC                       | 23        | 25     | 0.36%   |
| Micron/Crucial Technology   | 23        | 24     | 0.36%   |
| PNY                         | 22        | 26     | 0.34%   |
| Phison Electronics          | 22        | 24     | 0.34%   |
| Fujitsu                     | 19        | 20     | 0.3%    |
| Transcend                   | 18        | 20     | 0.28%   |
| ADATA Technology            | 18        | 22     | 0.28%   |
| LITEONIT                    | 15        | 21     | 0.23%   |
| JMicron Technology          | 15        | 17     | 0.23%   |
| GOODRAM                     | 15        | 16     | 0.23%   |
| UMIS                        | 14        | 14     | 0.22%   |
| Patriot                     | 13        | 15     | 0.2%    |
| Gigabyte Technology         | 13        | 14     | 0.2%    |
| Team                        | 12        | 13     | 0.19%   |
| Solid State Storage         | 12        | 14     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB                      | 80        | 1.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 74        | 1.12%   |
| Toshiba MQ04ABF100 1TB                              | 59        | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 58        | 0.88%   |
| Toshiba MQ01ABD100 1TB                              | 56        | 0.85%   |
| Unknown                                             | 55        | 0.83%   |
| Kingston SA400S37240G 240GB SSD                     | 54        | 0.82%   |
| Unknown MMC Card  64GB                              | 53        | 0.8%    |
| Unknown MMC Card  32GB                              | 53        | 0.8%    |
| Seagate ST500LT012-1DG142 500GB                     | 40        | 0.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 40        | 0.61%   |
| Toshiba MQ01ABF050 500GB                            | 38        | 0.58%   |
| Samsung NVMe SSD Drive 512GB                        | 38        | 0.58%   |
| HGST HTS721010A9E630 1TB                            | 37        | 0.56%   |
| Seagate ST9500325AS 500GB                           | 35        | 0.53%   |
| Intel SSDPEKNU512GZ 512GB                           | 35        | 0.53%   |
| Samsung SSD 860 EVO 500GB                           | 34        | 0.52%   |
| Crucial CT500MX500SSD1 500GB                        | 34        | 0.52%   |
| Kingston SA400S37480G 480GB SSD                     | 33        | 0.5%    |
| Phison 311CD0512GB                                  | 31        | 0.47%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                      | 31        | 0.47%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 30        | 0.46%   |
| SanDisk NVMe SSD Drive 512GB                        | 29        | 0.44%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 28        | 0.43%   |
| HGST HTS541010A9E680 1TB                            | 27        | 0.41%   |
| HGST HTS545050A7E680 500GB                          | 26        | 0.39%   |
| Crucial CT240BX500SSD1 240GB                        | 25        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB                         | 25        | 0.38%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 24        | 0.36%   |
| Samsung SSD 850 EVO 500GB                           | 24        | 0.36%   |
| Intel SSD 660P Series 512GB                         | 24        | 0.36%   |
| SanDisk NVMe SSD Drive 1TB                          | 23        | 0.35%   |
| KIOXIA KBG40ZNV512G 512GB                           | 23        | 0.35%   |
| Unknown MMC Card  128GB                             | 22        | 0.33%   |
| Samsung NVMe SSD Drive 256GB                        | 22        | 0.33%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 22        | 0.33%   |
| Samsung MZVL21T0HCLR-00B00 1TB                      | 22        | 0.33%   |
| Intel SSDPEKNW512G8 512GB                           | 22        | 0.33%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 21        | 0.32%   |
| SanDisk NVMe SSD Drive 256GB                        | 21        | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 506       | 588    | 33.16%  |
| WDC                 | 361       | 408    | 23.66%  |
| Toshiba             | 275       | 296    | 18.02%  |
| HGST                | 144       | 156    | 9.44%   |
| Hitachi             | 139       | 165    | 9.11%   |
| Samsung Electronics | 33        | 38     | 2.16%   |
| Unknown             | 21        | 23     | 1.38%   |
| Fujitsu             | 19        | 20     | 1.25%   |
| Apple               | 6         | 6      | 0.39%   |
| ASMT                | 4         | 4      | 0.26%   |
| USB3.0              | 3         | 3      | 0.2%    |
| Intenso             | 3         | 3      | 0.2%    |
| SSK                 | 2         | 2      | 0.13%   |
| ASMedia             | 2         | 2      | 0.13%   |
| USB                 | 1         | 1      | 0.07%   |
| StoreJet            | 1         | 1      | 0.07%   |
| SAGE                | 1         | 1      | 0.07%   |
| PHD 3.0             | 1         | 1      | 0.07%   |
| MARSHAL             | 1         | 1      | 0.07%   |
| LaCie               | 1         | 1      | 0.07%   |
| JMicron Technology  | 1         | 1      | 0.07%   |
| HGST HTS            | 1         | 2      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 368       | 421    | 20.5%   |
| Kingston            | 214       | 243    | 11.92%  |
| SanDisk             | 184       | 221    | 10.25%  |
| Crucial             | 171       | 191    | 9.53%   |
| WDC                 | 106       | 124    | 5.91%   |
| SK hynix            | 56        | 67     | 3.12%   |
| Micron Technology   | 56        | 61     | 3.12%   |
| China               | 47        | 53     | 2.62%   |
| Intel               | 42        | 45     | 2.34%   |
| Apple               | 41        | 43     | 2.28%   |
| A-DATA Technology   | 41        | 43     | 2.28%   |
| LITEON              | 37        | 39     | 2.06%   |
| SPCC                | 33        | 39     | 1.84%   |
| Toshiba             | 32        | 35     | 1.78%   |
| Netac               | 26        | 27     | 1.45%   |
| PNY                 | 20        | 23     | 1.11%   |
| Unknown             | 18        | 18     | 1%      |
| Intenso             | 17        | 21     | 0.95%   |
| Transcend           | 16        | 18     | 0.89%   |
| LITEONIT            | 15        | 21     | 0.84%   |
| GOODRAM             | 14        | 15     | 0.78%   |
| Patriot             | 13        | 15     | 0.72%   |
| Team                | 11        | 11     | 0.61%   |
| KingSpec            | 11        | 11     | 0.61%   |
| Lexar               | 9         | 9      | 0.5%    |
| Gigabyte Technology | 9         | 9      | 0.5%    |
| Teclast             | 8         | 9      | 0.45%   |
| OCZ                 | 8         | 8      | 0.45%   |
| Hewlett-Packard     | 8         | 15     | 0.45%   |
| BIWIN               | 7         | 7      | 0.39%   |
| BHT                 | 7         | 9      | 0.39%   |
| Seagate             | 6         | 8      | 0.33%   |
| Corsair             | 6         | 6      | 0.33%   |
| Apacer              | 6         | 6      | 0.33%   |
| Emtec               | 5         | 6      | 0.28%   |
| Verbatim            | 4         | 4      | 0.22%   |
| SSSTC               | 4         | 5      | 0.22%   |
| Plextor             | 4         | 4      | 0.22%   |
| Maxtor              | 4         | 4      | 0.22%   |
| KIOXIA-EXCERIA      | 4         | 6      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 2565      | 3049   | 41.71%  |
| SSD     | 1700      | 2044   | 27.65%  |
| HDD     | 1482      | 1723   | 24.1%   |
| MMC     | 305       | 368    | 4.96%   |
| Unknown | 97        | 117    | 1.58%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2875      | 3651   | 48.38%  |
| NVMe | 2556      | 3027   | 43.02%  |
| MMC  | 305       | 368    | 5.13%   |
| SAS  | 206       | 255    | 3.47%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2022      | 2456   | 64.33%  |
| 0.51-1.0   | 1011      | 1177   | 32.17%  |
| 1.01-2.0   | 81        | 94     | 2.58%   |
| 4.01-10.0  | 16        | 23     | 0.51%   |
| 3.01-4.0   | 10        | 10     | 0.32%   |
| 2.01-3.0   | 3         | 7      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1695      | 31.18%  |
| 251-500        | 1643      | 30.22%  |
| 501-1000       | 894       | 16.44%  |
| 51-100         | 320       | 5.89%   |
| 1-20           | 263       | 4.84%   |
| 1001-2000      | 245       | 4.51%   |
| 21-50          | 208       | 3.83%   |
| More than 3000 | 65        | 1.2%    |
| 2001-3000      | 53        | 0.97%   |
| Unknown        | 51        | 0.94%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1998      | 35.76%  |
| 21-50          | 1255      | 22.46%  |
| 51-100         | 827       | 14.8%   |
| 101-250        | 782       | 13.99%  |
| 251-500        | 388       | 6.94%   |
| 501-1000       | 190       | 3.4%    |
| 1001-2000      | 63        | 1.13%   |
| Unknown        | 51        | 0.91%   |
| More than 3000 | 22        | 0.39%   |
| 2001-3000      | 12        | 0.21%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB        | 8         | 8      | 3.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 6         | 7      | 2.58%   |
| Toshiba MQ01ABD100 1TB                | 5         | 5      | 2.15%   |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 5         | 5      | 2.15%   |
| Seagate ST9500325AS 500GB             | 5         | 5      | 2.15%   |
| HGST HTS541010A9E680 1TB              | 5         | 5      | 2.15%   |
| Toshiba MQ04ABF100 1TB                | 4         | 4      | 1.72%   |
| Seagate ST500LT012-9WS142 500GB       | 4         | 4      | 1.72%   |
| Seagate ST500LT012-1DG142 500GB       | 4         | 4      | 1.72%   |
| Seagate ST1000LX015-1U7172 1TB        | 4         | 4      | 1.72%   |
| Seagate ST1000LM014-1EJ164 1TB        | 4         | 5      | 1.72%   |
| Seagate ST9320325AS 320GB             | 3         | 3      | 1.29%   |
| Seagate ST1000LM014-SSHD-8GB          | 3         | 3      | 1.29%   |
| Hitachi HTS545050A7E380 500GB         | 3         | 3      | 1.29%   |
| Hitachi HTS543232A7A384 320GB         | 3         | 3      | 1.29%   |
| HGST HTS725050A7E630 500GB            | 3         | 3      | 1.29%   |
| HGST HTS721010A9E630 1TB              | 3         | 3      | 1.29%   |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 1.29%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 2         | 2      | 0.86%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 2         | 2      | 0.86%   |
| WDC WD10JPVX-60JC3T0 1TB              | 2         | 2      | 0.86%   |
| WDC WD10JPCX-24UE4T0 1TB              | 2         | 2      | 0.86%   |
| Toshiba MQ01ABD050 500GB              | 2         | 2      | 0.86%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 2         | 2      | 0.86%   |
| Seagate ST9500420AS 500GB             | 2         | 2      | 0.86%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 2         | 3      | 0.86%   |
| Seagate ST1000LM049-2GH172 1TB        | 2         | 2      | 0.86%   |
| Micron Technology 1100 SATA 256GB SSD | 2         | 2      | 0.86%   |
| Intel SSDSC2BF180A5L 180GB            | 2         | 2      | 0.86%   |
| Hitachi HTS547564A9E384 640GB         | 2         | 2      | 0.86%   |
| Hitachi HTS547550A9E384 500GB         | 2         | 2      | 0.86%   |
| HGST HTS541075A9E680 752GB            | 2         | 2      | 0.86%   |
| Crucial CT275MX300SSD4 275GB          | 2         | 2      | 0.86%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 0.43%   |
| WDC WDS120G2G0A-00JH30 128GB SSD      | 1         | 1      | 0.43%   |
| WDC WD7500BPVT-24HXZT3 752GB          | 1         | 1      | 0.43%   |
| WDC WD7500BPKT-22PK4T0 752GB          | 1         | 1      | 0.43%   |
| WDC WD6000HLHX-01JJPV0 600GB          | 1         | 1      | 0.43%   |
| WDC WD5000LPVX-22V0TT0 500GB          | 1         | 1      | 0.43%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 60     | 23.71%  |
| WDC                 | 31        | 33     | 13.36%  |
| Toshiba             | 23        | 24     | 9.91%   |
| Hitachi             | 20        | 21     | 8.62%   |
| SK hynix            | 19        | 19     | 8.19%   |
| HGST                | 19        | 19     | 8.19%   |
| Samsung Electronics | 12        | 12     | 5.17%   |
| Intel               | 9         | 9      | 3.88%   |
| SanDisk             | 8         | 9      | 3.45%   |
| Micron Technology   | 6         | 6      | 2.59%   |
| A-DATA Technology   | 5         | 5      | 2.16%   |
| LITEON              | 4         | 4      | 1.72%   |
| Kingston            | 3         | 4      | 1.29%   |
| Crucial             | 3         | 3      | 1.29%   |
| China               | 2         | 2      | 0.86%   |
| WALRAM              | 1         | 1      | 0.43%   |
| VISIPRO             | 1         | 1      | 0.43%   |
| tecmiyo             | 1         | 1      | 0.43%   |
| SSSTC               | 1         | 1      | 0.43%   |
| ShiJi               | 1         | 1      | 0.43%   |
| RX7                 | 1         | 1      | 0.43%   |
| Netac               | 1         | 1      | 0.43%   |
| KingSpec            | 1         | 1      | 0.43%   |
| Intenso             | 1         | 1      | 0.43%   |
| HS-SSD-E100         | 1         | 1      | 0.43%   |
| Fujitsu             | 1         | 1      | 0.43%   |
| Corsair             | 1         | 1      | 0.43%   |
| Apple               | 1         | 1      | 0.43%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 60     | 37.67%  |
| WDC                 | 25        | 27     | 17.12%  |
| Toshiba             | 21        | 22     | 14.38%  |
| Hitachi             | 20        | 21     | 13.7%   |
| HGST                | 19        | 19     | 13.01%  |
| Samsung Electronics | 4         | 4      | 2.74%   |
| Fujitsu             | 1         | 1      | 0.68%   |
| Apple               | 1         | 1      | 0.68%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 146       | 155    | 62.93%  |
| SSD  | 61        | 63     | 26.29%  |
| NVMe | 25        | 25     | 10.78%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD7500BPVT-22HXZT1 752GB                                    | 1         | 1      | 20%     |
| WDC WD5000BEVT-22A0RT0 500GB                                    | 1         | 1      | 20%     |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 20%     |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 20%     |
| Crucial M4-CT256M4SSD3 256GB                                    | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 2         | 2      | 40%     |
| Samsung Electronics | 1         | 1      | 20%     |
| HGST                | 1         | 1      | 20%     |
| Crucial             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3130      | 4380   | 56.34%  |
| Works    | 2191      | 2672   | 39.43%  |
| Malfunc  | 229       | 243    | 4.12%   |
| Failed   | 5         | 5      | 0.09%   |
| Fixed    | 1         | 1      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 3491      | 52.77%  |
| Samsung Electronics                     | 781       | 11.8%   |
| AMD                                     | 576       | 8.71%   |
| SanDisk                                 | 383       | 5.79%   |
| SK hynix                                | 276       | 4.17%   |
| Micron Technology                       | 213       | 3.22%   |
| KIOXIA                                  | 142       | 2.15%   |
| Kingston Technology Company             | 136       | 2.06%   |
| Toshiba America Info Systems            | 122       | 1.84%   |
| Phison Electronics                      | 91        | 1.38%   |
| ADATA Technology                        | 63        | 0.95%   |
| Silicon Motion                          | 51        | 0.77%   |
| Micron/Crucial Technology               | 51        | 0.77%   |
| Solid State Storage Technology          | 46        | 0.7%    |
| Apple                                   | 41        | 0.62%   |
| Nvidia                                  | 33        | 0.5%    |
| Union Memory (Shenzhen)                 | 25        | 0.38%   |
| Yangtze Memory Technologies             | 15        | 0.23%   |
| Marvell Technology Group                | 13        | 0.2%    |
| Shenzhen Longsys Electronics            | 9         | 0.14%   |
| Realtek Semiconductor                   | 9         | 0.14%   |
| Lite-On Technology                      | 9         | 0.14%   |
| Lenovo                                  | 7         | 0.11%   |
| Seagate Technology                      | 6         | 0.09%   |
| MAXIO Technology (Hangzhou)             | 4         | 0.06%   |
| ASMedia Technology                      | 4         | 0.06%   |
| Unknown                                 | 4         | 0.06%   |
| Transcend                               | 3         | 0.05%   |
| Biwin Storage Technology                | 3         | 0.05%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.03%   |
| INNOGRIT                                | 2         | 0.03%   |
| Zhaoxin                                 | 1         | 0.02%   |
| Shenzhen Unionmemory Information System | 1         | 0.02%   |
| Ramaxel Technology(Shenzhen) Limited    | 1         | 0.02%   |
| Netac Technology                        | 1         | 0.02%   |
| JMicron Technology                      | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 510       | 7.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 418       | 5.97%   |
| Intel Volume Management Device NVMe RAID Controller                            | 398       | 5.69%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 318       | 4.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 303       | 4.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 268       | 3.83%   |
| Samsung NVMe SSD Controller 980                                                | 235       | 3.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 216       | 3.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 172       | 2.46%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 164       | 2.34%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 143       | 2.04%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 141       | 2.01%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 140       | 2%      |
| Intel Tiger Lake-LP SATA Controller                                            | 137       | 1.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 129       | 1.84%   |
| Micron NVMe Storage Controller                                                 | 127       | 1.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 123       | 1.76%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 114       | 1.63%   |
| Intel Comet Lake SATA AHCI Controller                                          | 107       | 1.53%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 96        | 1.37%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 93        | 1.33%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 87        | 1.24%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 83        | 1.19%   |
| Intel Non-Volatile memory controller                                           | 80        | 1.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 72        | 1.03%   |
| Intel SSD 660P Series                                                          | 72        | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 67        | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 64        | 0.91%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 62        | 0.89%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 62        | 0.89%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 59        | 0.84%   |
| Phison PS5013 E13 NVMe Controller                                              | 57        | 0.81%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 56        | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 54        | 0.77%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 53        | 0.76%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 52        | 0.74%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 51        | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 48        | 0.69%   |
| Micron 2450 NVMe SSD (DRAM-less)                                               | 47        | 0.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 44        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 3384      | 49.77%  |
| NVMe | 2548      | 37.48%  |
| RAID | 713       | 10.49%  |
| IDE  | 154       | 2.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 4369      | 81.79%  |
| AMD          | 971       | 18.18%  |
| Phytium      | 1         | 0.02%   |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 155       | 2.9%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 145       | 2.71%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 89        | 1.67%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 76        | 1.42%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 74        | 1.39%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 72        | 1.35%   |
| Intel 12th Gen Core i7-12700H                 | 72        | 1.35%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 65        | 1.22%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 63        | 1.18%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 62        | 1.16%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 62        | 1.16%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 62        | 1.16%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 60        | 1.12%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 59        | 1.1%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 58        | 1.09%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 57        | 1.07%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 56        | 1.05%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 55        | 1.03%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 54        | 1.01%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 54        | 1.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 51        | 0.95%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 48        | 0.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 46        | 0.86%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 46        | 0.86%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 43        | 0.8%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 37        | 0.69%   |
| Intel 12th Gen Core i7-1260P                  | 36        | 0.67%   |
| Intel 12th Gen Core i7-1255U                  | 36        | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 35        | 0.66%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 35        | 0.66%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 34        | 0.64%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 33        | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 31        | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 31        | 0.58%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 31        | 0.58%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 30        | 0.56%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 29        | 0.54%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 29        | 0.54%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 29        | 0.54%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 29        | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1244      | 23.29%  |
| Intel Core i7           | 1103      | 20.65%  |
| Other                   | 928       | 17.37%  |
| Intel Core i3           | 386       | 7.23%   |
| Intel Celeron           | 313       | 5.86%   |
| AMD Ryzen 5             | 276       | 5.17%   |
| AMD Ryzen 7             | 254       | 4.75%   |
| Intel Core 2 Duo        | 135       | 2.53%   |
| Intel Pentium           | 118       | 2.21%   |
| AMD Ryzen 9             | 47        | 0.88%   |
| AMD Ryzen 3             | 47        | 0.88%   |
| Intel Atom              | 46        | 0.86%   |
| AMD A6                  | 46        | 0.86%   |
| AMD Ryzen 7 PRO         | 37        | 0.69%   |
| AMD A8                  | 36        | 0.67%   |
| AMD A4                  | 30        | 0.56%   |
| AMD A10                 | 27        | 0.51%   |
| AMD E2                  | 24        | 0.45%   |
| Intel Pentium Dual-Core | 23        | 0.43%   |
| Intel Core i9           | 20        | 0.37%   |
| Intel Pentium Dual      | 16        | 0.3%    |
| AMD Athlon              | 15        | 0.28%   |
| AMD E1                  | 14        | 0.26%   |
| AMD Ryzen 5 PRO         | 13        | 0.24%   |
| AMD E                   | 12        | 0.22%   |
| Intel Xeon              | 11        | 0.21%   |
| Intel Pentium Silver    | 11        | 0.21%   |
| Intel Genuine           | 8         | 0.15%   |
| Intel Core 2            | 8         | 0.15%   |
| Intel Core M            | 7         | 0.13%   |
| AMD Turion 64 X2 Mobile | 7         | 0.13%   |
| AMD Phenom II           | 6         | 0.11%   |
| AMD Athlon II           | 6         | 0.11%   |
| Intel Core m3           | 5         | 0.09%   |
| Intel Celeron Dual-Core | 5         | 0.09%   |
| AMD FX                  | 5         | 0.09%   |
| AMD A12                 | 5         | 0.09%   |
| AMD Turion 64 Mobile    | 4         | 0.07%   |
| AMD Athlon X2           | 4         | 0.07%   |
| AMD Athlon II Dual-Core | 4         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 2270      | 42.49%  |
| 4      | 1847      | 34.57%  |
| 8      | 450       | 8.42%   |
| 6      | 426       | 7.97%   |
| 14     | 137       | 2.56%   |
| 12     | 85        | 1.59%   |
| 10     | 78        | 1.46%   |
| 1      | 35        | 0.66%   |
| 16     | 8         | 0.15%   |
| 3      | 3         | 0.06%   |
| 24     | 2         | 0.04%   |
| 5      | 2         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5342      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 4280      | 80.07%  |
| 1      | 1065      | 19.93%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 5341      | 99.98%  |
| Unknown        | 1         | 0.02%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2778      | 51.05%  |
| 0x806c1    | 304       | 5.59%   |
| 0x806ec    | 194       | 3.56%   |
| 0x906a3    | 156       | 2.87%   |
| 0x806ea    | 136       | 2.5%    |
| 0x306a9    | 123       | 2.26%   |
| 0x0a50000c | 110       | 2.02%   |
| 0x206a7    | 90        | 1.65%   |
| 0x906ea    | 88        | 1.62%   |
| 0x40651    | 84        | 1.54%   |
| 0xa0652    | 80        | 1.47%   |
| 0x406e3    | 80        | 1.47%   |
| 0x08608103 | 79        | 1.45%   |
| 0x306d4    | 78        | 1.43%   |
| 0x806d1    | 73        | 1.34%   |
| 0x806e9    | 71        | 1.3%    |
| 0x706e5    | 63        | 1.16%   |
| 0x706a8    | 58        | 1.07%   |
| 0x306c3    | 57        | 1.05%   |
| 0x906a4    | 50        | 0.92%   |
| 0x08600106 | 50        | 0.92%   |
| 0x08108109 | 48        | 0.88%   |
| 0x20655    | 40        | 0.74%   |
| 0x906e9    | 31        | 0.57%   |
| 0x806eb    | 29        | 0.53%   |
| 0x506e3    | 26        | 0.48%   |
| 0x1067a    | 23        | 0.42%   |
| 0x906ed    | 22        | 0.4%    |
| 0x30678    | 22        | 0.4%    |
| 0x506c9    | 21        | 0.39%   |
| 0x08600104 | 21        | 0.39%   |
| 0x08108102 | 21        | 0.39%   |
| 0x706a1    | 20        | 0.37%   |
| 0x06006705 | 19        | 0.35%   |
| 0x806c2    | 16        | 0.29%   |
| 0x0a50000d | 15        | 0.28%   |
| 0x20652    | 14        | 0.26%   |
| 0x0a404102 | 14        | 0.26%   |
| 0x06001119 | 13        | 0.24%   |
| 0x6fd      | 12        | 0.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 1022      | 19.11%  |
| TigerLake        | 470       | 8.79%   |
| Haswell          | 364       | 6.81%   |
| Unknown          | 350       | 6.54%   |
| IvyBridge        | 328       | 6.13%   |
| SandyBridge      | 297       | 5.55%   |
| Skylake          | 268       | 5.01%   |
| Alderlake Hybrid | 215       | 4.02%   |
| Zen 3            | 203       | 3.8%    |
| Icelake          | 199       | 3.72%   |
| Broadwell        | 176       | 3.29%   |
| Westmere         | 172       | 3.22%   |
| Silvermont       | 153       | 2.86%   |
| Zen+             | 141       | 2.64%   |
| Penryn           | 135       | 2.52%   |
| Goldmont plus    | 135       | 2.52%   |
| Zen 2            | 131       | 2.45%   |
| CometLake        | 131       | 2.45%   |
| Excavator        | 82        | 1.53%   |
| Core             | 67        | 1.25%   |
| Goldmont         | 59        | 1.1%    |
| Puma             | 38        | 0.71%   |
| Zen              | 32        | 0.6%    |
| Piledriver       | 32        | 0.6%    |
| Bobcat           | 31        | 0.58%   |
| K10              | 25        | 0.47%   |
| K8 Hammer        | 16        | 0.3%    |
| Jaguar           | 16        | 0.3%    |
| Nehalem          | 15        | 0.28%   |
| Steamroller      | 14        | 0.26%   |
| K10 Llano        | 13        | 0.24%   |
| K8 & K10 hybrid  | 11        | 0.21%   |
| Tremont          | 6         | 0.11%   |
| Bonnell          | 2         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4083      | 59.24%  |
| Nvidia                           | 1557      | 22.59%  |
| AMD                              | 1250      | 18.14%  |
| Zhaoxin                          | 1         | 0.01%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 432       | 6.17%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 301       | 4.3%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 275       | 3.93%   |
| Intel UHD Graphics 620                                                                   | 232       | 3.32%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 213       | 3.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 193       | 2.76%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 183       | 2.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 180       | 2.57%   |
| Intel HD Graphics 620                                                                    | 166       | 2.37%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 160       | 2.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 157       | 2.24%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 157       | 2.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 147       | 2.1%    |
| Intel HD Graphics 5500                                                                   | 146       | 2.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 146       | 2.09%   |
| AMD Lucienne                                                                             | 142       | 2.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 124       | 1.77%   |
| AMD Renoir                                                                               | 123       | 1.76%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 114       | 1.63%   |
| Intel Core Processor Integrated Graphics Controller                                      | 114       | 1.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 112       | 1.6%    |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 106       | 1.51%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 90        | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 81        | 1.16%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 72        | 1.03%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 72        | 1.03%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 71        | 1.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 65        | 0.93%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 64        | 0.91%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 61        | 0.87%   |
| Intel HD Graphics 500                                                                    | 53        | 0.76%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 52        | 0.74%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 49        | 0.7%    |
| Intel HD Graphics 630                                                                    | 48        | 0.69%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 46        | 0.66%   |
| Intel HD Graphics 530                                                                    | 45        | 0.64%   |
| AMD Rembrandt [Radeon 680M]                                                              | 42        | 0.6%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 41        | 0.59%   |
| Nvidia TU117M                                                                            | 39        | 0.56%   |
| Nvidia GP108M [GeForce MX150]                                                            | 39        | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 2671      | 49.98%  |
| Intel + Nvidia | 1202      | 22.49%  |
| 1 x AMD        | 846       | 15.83%  |
| 1 x Nvidia     | 207       | 3.87%   |
| Intel + AMD    | 195       | 3.65%   |
| AMD + Nvidia   | 145       | 2.71%   |
| 2 x AMD        | 63        | 1.18%   |
| Other          | 10        | 0.19%   |
| 2 x Nvidia     | 2         | 0.04%   |
| 2 x Intel      | 1         | 0.02%   |
| 1 x Zhaoxin    | 1         | 0.02%   |
| 1 x SiS        | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 4428      | 82.4%   |
| Proprietary | 850       | 15.82%  |
| Unknown     | 96        | 1.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4413      | 81.97%  |
| 0.01-0.5   | 316       | 5.87%   |
| 1.01-2.0   | 295       | 5.48%   |
| 0.51-1.0   | 145       | 2.69%   |
| 3.01-4.0   | 139       | 2.58%   |
| 5.01-6.0   | 41        | 0.76%   |
| 7.01-8.0   | 23        | 0.43%   |
| 2.01-3.0   | 7         | 0.13%   |
| 8.01-16.0  | 5         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1129      | 18.01%  |
| BOE                     | 1060      | 16.91%  |
| Chimei Innolux          | 845       | 13.48%  |
| LG Display              | 789       | 12.59%  |
| Samsung Electronics     | 594       | 9.48%   |
| Dell                    | 200       | 3.19%   |
| Sharp                   | 194       | 3.1%    |
| Apple                   | 152       | 2.43%   |
| Goldstar                | 143       | 2.28%   |
| PANDA                   | 110       | 1.76%   |
| Chi Mei Optoelectronics | 106       | 1.69%   |
| Lenovo                  | 98        | 1.56%   |
| Hewlett-Packard         | 85        | 1.36%   |
| Acer                    | 58        | 0.93%   |
| InfoVision              | 57        | 0.91%   |
| CSO                     | 56        | 0.89%   |
| AOC                     | 51        | 0.81%   |
| Philips                 | 49        | 0.78%   |
| BenQ                    | 38        | 0.61%   |
| Ancor Communications    | 38        | 0.61%   |
| Iiyama                  | 35        | 0.56%   |
| Sony                    | 29        | 0.46%   |
| ASUSTek Computer        | 26        | 0.41%   |
| ViewSonic               | 24        | 0.38%   |
| LG Philips              | 23        | 0.37%   |
| TMX                     | 20        | 0.32%   |
| CPT                     | 15        | 0.24%   |
| MSI                     | 13        | 0.21%   |
| Mi                      | 13        | 0.21%   |
| Toshiba                 | 11        | 0.18%   |
| Panasonic               | 10        | 0.16%   |
| Vizio                   | 8         | 0.13%   |
| Eizo                    | 8         | 0.13%   |
| SLD                     | 7         | 0.11%   |
| Fujitsu Siemens         | 7         | 0.11%   |
| Vestel Elektronik       | 6         | 0.1%    |
| HannStar                | 6         | 0.1%    |
| STA                     | 5         | 0.08%   |
| SGT                     | 5         | 0.08%   |
| NEC Computers           | 5         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 49        | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 38        | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 37        | 0.58%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch     | 36        | 0.57%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 36        | 0.57%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 34        | 0.54%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 32        | 0.5%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 28        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 27        | 0.43%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 26        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 26        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 26        | 0.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 26        | 0.41%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 22        | 0.35%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 21        | 0.33%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 20        | 0.32%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 18        | 0.28%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 18        | 0.28%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                    | 18        | 0.28%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                    | 18        | 0.28%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 17        | 0.27%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch           | 17        | 0.27%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 17        | 0.27%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 16        | 0.25%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 16        | 0.25%   |
| BOE LCD Monitor BOE091D 1920x1080 309x174mm 14.0-inch                    | 16        | 0.25%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 16        | 0.25%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 15        | 0.24%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch             | 15        | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 15        | 0.24%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 15        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 15        | 0.24%   |
| Chimei Innolux LCD Monitor CMN140A 1920x1080 309x173mm 13.9-inch         | 15        | 0.24%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 15        | 0.24%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 14        | 0.22%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 14        | 0.22%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 14        | 0.22%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                    | 14        | 0.22%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 14        | 0.22%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 14        | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 2723      | 46.52%  |
| 1366x768 (WXGA)    | 1455      | 24.85%  |
| 1600x900 (HD+)     | 292       | 4.99%   |
| 3840x2160 (4K)     | 239       | 4.08%   |
| 2560x1440 (QHD)    | 210       | 3.59%   |
| 1920x1200 (WUXGA)  | 157       | 2.68%   |
| 1280x800 (WXGA)    | 132       | 2.25%   |
| 2560x1600          | 111       | 1.9%    |
| 2880x1800          | 77        | 1.32%   |
| 1440x900 (WXGA+)   | 65        | 1.11%   |
| 3840x2400          | 50        | 0.85%   |
| 2560x1080          | 45        | 0.77%   |
| 1680x1050 (WSXGA+) | 44        | 0.75%   |
| 3440x1440          | 39        | 0.67%   |
| 2160x1440          | 30        | 0.51%   |
| 1280x1024 (SXGA)   | 22        | 0.38%   |
| 1360x768           | 16        | 0.27%   |
| 2256x1504          | 14        | 0.24%   |
| 3200x1800 (QHD+)   | 11        | 0.19%   |
| 2520x1680          | 10        | 0.17%   |
| 3840x1080          | 9         | 0.15%   |
| 3200x2000          | 9         | 0.15%   |
| 3456x2160          | 8         | 0.14%   |
| 3000x2000          | 8         | 0.14%   |
| 3072x1920          | 7         | 0.12%   |
| 1920x540           | 7         | 0.12%   |
| Unknown            | 6         | 0.1%    |
| 2880x1620          | 5         | 0.09%   |
| 2240x1400          | 5         | 0.09%   |
| 1680x945           | 5         | 0.09%   |
| 3840x1600          | 4         | 0.07%   |
| 1920x1280          | 4         | 0.07%   |
| 1024x768 (XGA)     | 4         | 0.07%   |
| 2304x1440          | 3         | 0.05%   |
| 1280x720 (HD)      | 3         | 0.05%   |
| 2160x1350          | 2         | 0.03%   |
| 1600x1200          | 2         | 0.03%   |
| 1400x1050          | 2         | 0.03%   |
| 1024x600           | 2         | 0.03%   |
| 6400x2160          | 1         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 2517      | 40.17%  |
| 13      | 899       | 14.35%  |
| 14      | 804       | 12.83%  |
| 17      | 458       | 7.31%   |
| 27      | 240       | 3.83%   |
| 24      | 216       | 3.45%   |
| 23      | 172       | 2.74%   |
| 16      | 145       | 2.31%   |
| 21      | 138       | 2.2%    |
| 12      | 109       | 1.74%   |
| 11      | 99        | 1.58%   |
| 34      | 75        | 1.2%    |
| 31      | 58        | 0.93%   |
| 18      | 44        | 0.7%    |
| Unknown | 38        | 0.61%   |
| 22      | 27        | 0.43%   |
| 19      | 24        | 0.38%   |
| 20      | 19        | 0.3%    |
| 84      | 18        | 0.29%   |
| 40      | 18        | 0.29%   |
| 54      | 17        | 0.27%   |
| 72      | 15        | 0.24%   |
| 10      | 15        | 0.24%   |
| 26      | 13        | 0.21%   |
| 28      | 12        | 0.19%   |
| 32      | 10        | 0.16%   |
| 25      | 8         | 0.13%   |
| 43      | 6         | 0.1%    |
| 37      | 6         | 0.1%    |
| 65      | 5         | 0.08%   |
| 48      | 5         | 0.08%   |
| 49      | 4         | 0.06%   |
| 47      | 4         | 0.06%   |
| 46      | 4         | 0.06%   |
| 38      | 4         | 0.06%   |
| 52      | 3         | 0.05%   |
| 29      | 3         | 0.05%   |
| 74      | 2         | 0.03%   |
| 42      | 2         | 0.03%   |
| 35      | 2         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 3819      | 61.36%  |
| 201-300     | 679       | 10.91%  |
| 501-600     | 588       | 9.45%   |
| 351-400     | 551       | 8.85%   |
| 401-500     | 243       | 3.9%    |
| 601-700     | 98        | 1.57%   |
| 701-800     | 86        | 1.38%   |
| 1001-1500   | 44        | 0.71%   |
| Unknown     | 38        | 0.61%   |
| 1501-2000   | 36        | 0.58%   |
| 801-900     | 31        | 0.5%    |
| 901-1000    | 8         | 0.13%   |
| 101-200     | 3         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 4550      | 83.18%  |
| 16/10   | 682       | 12.47%  |
| 21/9    | 91        | 1.66%   |
| 3/2     | 79        | 1.44%   |
| Unknown | 19        | 0.35%   |
| 4/3     | 16        | 0.29%   |
| 5/4     | 15        | 0.27%   |
| 32/9    | 8         | 0.15%   |
| 6/5     | 3         | 0.05%   |
| 0.62    | 2         | 0.04%   |
| 3.73    | 1         | 0.02%   |
| 3.33    | 1         | 0.02%   |
| 3.20    | 1         | 0.02%   |
| 2.12    | 1         | 0.02%   |
| 2.00    | 1         | 0.02%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 2523      | 40.33%  |
| 81-90          | 1360      | 21.74%  |
| 201-250        | 448       | 7.16%   |
| 121-130        | 403       | 6.44%   |
| 71-80          | 337       | 5.39%   |
| 301-350        | 251       | 4.01%   |
| 351-500        | 152       | 2.43%   |
| 111-120        | 124       | 1.98%   |
| 61-70          | 101       | 1.61%   |
| 51-60          | 99        | 1.58%   |
| 251-300        | 81        | 1.29%   |
| 151-200        | 77        | 1.23%   |
| More than 1000 | 63        | 1.01%   |
| 131-140        | 52        | 0.83%   |
| 501-1000       | 51        | 0.82%   |
| 141-150        | 48        | 0.77%   |
| Unknown        | 38        | 0.61%   |
| 91-100         | 30        | 0.48%   |
| 41-50          | 16        | 0.26%   |
| 1-40           | 2         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 2643      | 43.1%   |
| 101-120       | 1685      | 27.48%  |
| 51-100        | 913       | 14.89%  |
| 161-240       | 568       | 9.26%   |
| More than 240 | 230       | 3.75%   |
| 1-50          | 55        | 0.9%    |
| Unknown       | 38        | 0.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 4164      | 76.97%  |
| 2     | 975       | 18.02%  |
| 0     | 132       | 2.44%   |
| 3     | 127       | 2.35%   |
| 4     | 10        | 0.18%   |
| 6     | 1         | 0.02%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Intel                                  | 2978      | 35.82%  |
| Realtek Semiconductor                  | 2865      | 34.46%  |
| Qualcomm Atheros                       | 971       | 11.68%  |
| Broadcom                               | 458       | 5.51%   |
| MediaTek                               | 208       | 2.5%    |
| Broadcom Limited                       | 111       | 1.34%   |
| ASIX Electronics                       | 67        | 0.81%   |
| Ralink                                 | 61        | 0.73%   |
| TP-Link                                | 50        | 0.6%    |
| Marvell Technology Group               | 47        | 0.57%   |
| DisplayLink                            | 44        | 0.53%   |
| Samsung Electronics                    | 37        | 0.45%   |
| Dell                                   | 35        | 0.42%   |
| Qualcomm                               | 30        | 0.36%   |
| Lenovo                                 | 29        | 0.35%   |
| Ralink Technology                      | 28        | 0.34%   |
| Xiaomi                                 | 24        | 0.29%   |
| Nvidia                                 | 24        | 0.29%   |
| Sierra Wireless                        | 23        | 0.28%   |
| NetGear                                | 20        | 0.24%   |
| Ericsson Business Mobile Networks      | 20        | 0.24%   |
| Hewlett-Packard                        | 17        | 0.2%    |
| JMicron Technology                     | 16        | 0.19%   |
| Apple                                  | 13        | 0.16%   |
| Qualcomm Atheros Communications        | 12        | 0.14%   |
| Huawei Technologies                    | 12        | 0.14%   |
| ICS Advent                             | 11        | 0.13%   |
| OPPO Electronics                       | 10        | 0.12%   |
| Google                                 | 10        | 0.12%   |
| Motorola PCS                           | 8         | 0.1%    |
| D-Link                                 | 7         | 0.08%   |
| Fibocom                                | 6         | 0.07%   |
| U-Blox                                 | 5         | 0.06%   |
| Edimax Technology                      | 5         | 0.06%   |
| Arduino SA                             | 5         | 0.06%   |
| Toshiba                                | 4         | 0.05%   |
| D-Link System                          | 3         | 0.04%   |
| TRENDnet                               | 2         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.02%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1618      | 16.34%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 395       | 3.99%   |
| Intel Wi-Fi 6 AX201                                               | 366       | 3.7%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 277       | 2.8%    |
| Intel Wi-Fi 6 AX200                                               | 245       | 2.47%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 242       | 2.44%   |
| Intel Wireless 8265 / 8275                                        | 239       | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 191       | 1.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 187       | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 186       | 1.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 181       | 1.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 149       | 1.5%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 148       | 1.49%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 147       | 1.48%   |
| Intel Wireless 7265                                               | 145       | 1.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 136       | 1.37%   |
| Intel Wireless 7260                                               | 135       | 1.36%   |
| Intel Wireless 8260                                               | 128       | 1.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 125       | 1.26%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 106       | 1.07%   |
| Intel Ethernet Connection (4) I219-LM                             | 103       | 1.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 98        | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 90        | 0.91%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 89        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 88        | 0.89%   |
| Intel Wireless 3165                                               | 79        | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 77        | 0.78%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 76        | 0.77%   |
| Intel Ethernet Connection I219-LM                                 | 76        | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 67        | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 66        | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                     | 64        | 0.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 63        | 0.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 62        | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 58        | 0.59%   |
| Intel 82577LM Gigabit Network Connection                          | 56        | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 55        | 0.56%   |
| Intel Ethernet Connection I218-LM                                 | 52        | 0.53%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 52        | 0.53%   |
| Intel Wireless 3160                                               | 51        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2850      | 51.9%   |
| Realtek Semiconductor           | 901       | 16.41%  |
| Qualcomm Atheros                | 828       | 15.08%  |
| Broadcom                        | 372       | 6.77%   |
| MediaTek                        | 198       | 3.61%   |
| Broadcom Limited                | 74        | 1.35%   |
| Ralink                          | 61        | 1.11%   |
| TP-Link                         | 40        | 0.73%   |
| Ralink Technology               | 28        | 0.51%   |
| Dell                            | 24        | 0.44%   |
| Sierra Wireless                 | 23        | 0.42%   |
| Qualcomm                        | 23        | 0.42%   |
| NetGear                         | 19        | 0.35%   |
| Qualcomm Atheros Communications | 12        | 0.22%   |
| Hewlett-Packard                 | 6         | 0.11%   |
| Fibocom                         | 6         | 0.11%   |
| D-Link                          | 6         | 0.11%   |
| Edimax Technology               | 5         | 0.09%   |
| D-Link System                   | 3         | 0.05%   |
| TRENDnet                        | 2         | 0.04%   |
| U.S. Robotics                   | 1         | 0.02%   |
| Quectel Wireless Solutions      | 1         | 0.02%   |
| Microsoft                       | 1         | 0.02%   |
| Linksys                         | 1         | 0.02%   |
| IMC Networks                    | 1         | 0.02%   |
| I-O Data Device                 | 1         | 0.02%   |
| Guillemot                       | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| Belkin Components               | 1         | 0.02%   |
| AboCom Systems                  | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 366       | 6.61%   |
| Intel Wi-Fi 6 AX200                                            | 245       | 4.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 242       | 4.37%   |
| Intel Wireless 8265 / 8275                                     | 239       | 4.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 191       | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 187       | 3.38%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 186       | 3.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 181       | 3.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 148       | 2.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 147       | 2.66%   |
| Intel Wireless 7265                                            | 145       | 2.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 136       | 2.46%   |
| Intel Wireless 7260                                            | 135       | 2.44%   |
| Intel Wireless 8260                                            | 128       | 2.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 125       | 2.26%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 106       | 1.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 98        | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 90        | 1.63%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 89        | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 88        | 1.59%   |
| Intel Wireless 3165                                            | 79        | 1.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 77        | 1.39%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 76        | 1.37%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 67        | 1.21%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 66        | 1.19%   |
| Broadcom BCM43142 802.11b/g/n                                  | 64        | 1.16%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 62        | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 58        | 1.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 52        | 0.94%   |
| Intel Wireless 3160                                            | 51        | 0.92%   |
| Intel Centrino Wireless-N 2230                                 | 49        | 0.89%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 48        | 0.87%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 47        | 0.85%   |
| Intel Wireless-AC 9260                                         | 45        | 0.81%   |
| Intel Centrino Advanced-N 6200                                 | 43        | 0.78%   |
| Realtek 802.11n WLAN Adapter                                   | 40        | 0.72%   |
| Intel Centrino Ultimate-N 6300                                 | 40        | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 38        | 0.69%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 38        | 0.69%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 37        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 2429      | 57.6%   |
| Intel                                  | 975       | 23.12%  |
| Qualcomm Atheros                       | 235       | 5.57%   |
| Broadcom                               | 160       | 3.79%   |
| ASIX Electronics                       | 67        | 1.59%   |
| Marvell Technology Group               | 47        | 1.11%   |
| DisplayLink                            | 44        | 1.04%   |
| Broadcom Limited                       | 39        | 0.92%   |
| Lenovo                                 | 29        | 0.69%   |
| Samsung Electronics                    | 27        | 0.64%   |
| Xiaomi                                 | 24        | 0.57%   |
| Nvidia                                 | 24        | 0.57%   |
| JMicron Technology                     | 16        | 0.38%   |
| Apple                                  | 13        | 0.31%   |
| ICS Advent                             | 11        | 0.26%   |
| TP-Link                                | 10        | 0.24%   |
| OPPO Electronics                       | 10        | 0.24%   |
| MediaTek                               | 10        | 0.24%   |
| Google                                 | 10        | 0.24%   |
| Qualcomm                               | 7         | 0.17%   |
| Huawei Technologies                    | 7         | 0.17%   |
| Motorola PCS                           | 5         | 0.12%   |
| Hewlett-Packard                        | 4         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.05%   |
| HMD Global                             | 2         | 0.05%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Research In Motion                     | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Netchip Technology                     | 1         | 0.02%   |
| LG Electronics                         | 1         | 0.02%   |
| Davicom Semiconductor                  | 1         | 0.02%   |
| D-Link                                 | 1         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1618      | 37.82%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 395       | 9.23%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 277       | 6.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 149       | 3.48%   |
| Intel Ethernet Connection (4) I219-LM                             | 103       | 2.41%   |
| Intel Ethernet Connection I219-LM                                 | 76        | 1.78%   |
| ASIX AX88179 Gigabit Ethernet                                     | 63        | 1.47%   |
| Intel 82577LM Gigabit Network Connection                          | 56        | 1.31%   |
| Realtek RTL8125 2.5GbE Controller                                 | 55        | 1.29%   |
| Intel Ethernet Connection I218-LM                                 | 52        | 1.22%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 43        | 1.01%   |
| Intel Ethernet Connection (3) I218-LM                             | 43        | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 41        | 0.96%   |
| Intel Ethernet Connection (4) I219-V                              | 41        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 40        | 0.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 39        | 0.91%   |
| Realtek Killer E3000 2.5GbE Controller                            | 36        | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                             | 32        | 0.75%   |
| Intel Ethernet Connection (6) I219-V                              | 31        | 0.72%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 30        | 0.7%    |
| Intel Ethernet Connection (13) I219-LM                            | 30        | 0.7%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 27        | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 27        | 0.63%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 27        | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 24        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 23        | 0.54%   |
| Intel Ethernet Connection (16) I219-V                             | 23        | 0.54%   |
| Intel Ethernet Connection (16) I219-LM                            | 23        | 0.54%   |
| Intel Ethernet Connection (13) I219-V                             | 21        | 0.49%   |
| Intel 82579V Gigabit Network Connection                           | 21        | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 20        | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 20        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 20        | 0.47%   |
| Intel 82567LM Gigabit Network Connection                          | 20        | 0.47%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 20        | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 19        | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 19        | 0.44%   |
| Nvidia MCP79 Ethernet                                             | 19        | 0.44%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 18        | 0.42%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 18        | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 5262      | 56.26%  |
| Ethernet | 4005      | 42.82%  |
| Modem    | 75        | 0.8%    |
| Unknown  | 11        | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 4467      | 79.1%   |
| Ethernet | 1180      | 20.9%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 3541      | 66.27%  |
| 1     | 1672      | 31.29%  |
| 0     | 95        | 1.78%   |
| 3     | 35        | 0.66%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3776      | 69.99%  |
| Yes  | 1619      | 30.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2417      | 54.3%   |
| Realtek Semiconductor           | 509       | 11.44%  |
| Qualcomm Atheros Communications | 334       | 7.5%    |
| IMC Networks                    | 233       | 5.23%   |
| Lite-On Technology              | 183       | 4.11%   |
| Foxconn / Hon Hai               | 176       | 3.95%   |
| Broadcom                        | 158       | 3.55%   |
| Apple                           | 110       | 2.47%   |
| Dell                            | 62        | 1.39%   |
| Realtek                         | 52        | 1.17%   |
| Hewlett-Packard                 | 41        | 0.92%   |
| Cambridge Silicon Radio         | 39        | 0.88%   |
| Ralink                          | 33        | 0.74%   |
| Toshiba                         | 28        | 0.63%   |
| ASUSTek Computer                | 12        | 0.27%   |
| Foxconn International           | 10        | 0.22%   |
| Alps Electric                   | 10        | 0.22%   |
| Ralink Technology               | 9         | 0.2%    |
| MediaTek                        | 8         | 0.18%   |
| USI                             | 7         | 0.16%   |
| Askey Computer                  | 5         | 0.11%   |
| Opticis                         | 4         | 0.09%   |
| Integrated System Solution      | 2         | 0.04%   |
| TP-Link                         | 1         | 0.02%   |
| Taiyo Yuden                     | 1         | 0.02%   |
| Roper                           | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Mobile Action Technology        | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Edimax Technology               | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 766       | 17.2%   |
| Intel AX201 Bluetooth                               | 655       | 14.71%  |
| Realtek Bluetooth Radio                             | 367       | 8.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 330       | 7.41%   |
| Intel AX200 Bluetooth                               | 241       | 5.41%   |
| Intel Bluetooth Device                              | 198       | 4.45%   |
| Qualcomm Atheros  Bluetooth Device                  | 175       | 3.93%   |
| Realtek  Bluetooth 4.2 Adapter                      | 103       | 2.31%   |
| IMC Networks Wireless_Device                        | 92        | 2.07%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 77        | 1.73%   |
| Apple Bluetooth Host Controller                     | 70        | 1.57%   |
| IMC Networks Bluetooth Radio                        | 66        | 1.48%   |
| Intel AX210 Bluetooth                               | 63        | 1.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 61        | 1.37%   |
| Foxconn / Hon Hai Bluetooth Device                  | 56        | 1.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 54        | 1.21%   |
| Realtek Bluetooth Radio                             | 52        | 1.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 40        | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 40        | 0.9%    |
| IMC Networks Bluetooth Device                       | 39        | 0.88%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 39        | 0.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 39        | 0.88%   |
| Lite-On Atheros AR3012 Bluetooth                    | 37        | 0.83%   |
| Ralink RT3290 Bluetooth                             | 33        | 0.74%   |
| Lite-On Bluetooth Device                            | 33        | 0.74%   |
| Intel Wireless-AC 3168 Bluetooth                    | 31        | 0.7%    |
| Apple Bluetooth USB Host Controller                 | 30        | 0.67%   |
| Lite-On Wireless_Device                             | 29        | 0.65%   |
| HP Broadcom 2070 Bluetooth Combo                    | 28        | 0.63%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 27        | 0.61%   |
| Dell DW375 Bluetooth Module                         | 24        | 0.54%   |
| Broadcom BCM2045B (BDC-2.1)                         | 22        | 0.49%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 21        | 0.47%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 20        | 0.45%   |
| Broadcom HP Portable SoftSailing                    | 19        | 0.43%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 17        | 0.38%   |
| Foxconn / Hon Hai Wireless_Device                   | 17        | 0.38%   |
| Realtek RTL8723B Bluetooth                          | 16        | 0.36%   |
| Dell BCM20702A0 Bluetooth Module                    | 16        | 0.36%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 15        | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Notebooks | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4289      | 64.24%  |
| AMD                                          | 1090      | 16.32%  |
| Nvidia                                       | 831       | 12.45%  |
| Realtek Semiconductor                        | 38        | 0.57%   |
| Logitech                                     | 38        | 0.57%   |
| C-Media Electronics                          | 37        | 0.55%   |
| Hewlett-Packard                              | 35        | 0.52%   |
| GN Netcom                                    | 34        | 0.51%   |
| Lenovo                                       | 32        | 0.48%   |
| Apple                                        | 30        | 0.45%   |
| Plantronics                                  | 29        | 0.43%   |
| JMTek                                        | 17        | 0.25%   |
| Corsair                                      | 13        | 0.19%   |
| Generalplus Technology                       | 12        | 0.18%   |
| Kingston Technology                          | 11        | 0.16%   |
| Texas Instruments                            | 10        | 0.15%   |
| Razer USA                                    | 10        | 0.15%   |
| Sennheiser Communications                    | 8         | 0.12%   |
| Creative Technology                          | 8         | 0.12%   |
| SteelSeries ApS                              | 6         | 0.09%   |
| ASUSTek Computer                             | 6         | 0.09%   |
| Jieli Technology                             | 5         | 0.07%   |
| Focusrite-Novation                           | 5         | 0.07%   |
| DCMT Technology                              | 5         | 0.07%   |
| Sony                                         | 4         | 0.06%   |
| RODE Microphones                             | 4         | 0.06%   |
| DSEA A/S                                     | 4         | 0.06%   |
| BEHRINGER International                      | 4         | 0.06%   |
| JBL                                          | 3         | 0.04%   |
| Dell                                         | 3         | 0.04%   |
| Zoran Co. Personal Media Division (Nogatech) | 2         | 0.03%   |
| XMOS                                         | 2         | 0.03%   |
| Syntek                                       | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]             | 2         | 0.03%   |
| Samsung Electronics                          | 2         | 0.03%   |
| OPPO Electronics                             | 2         | 0.03%   |
| Microsoft                                    | 2         | 0.03%   |
| Huawei Technologies                          | 2         | 0.03%   |
| Google                                       | 2         | 0.03%   |
| FIFINE Microphones                           | 2         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 649       | 8.08%   |
| Intel Sunrise Point-LP HD Audio                                            | 631       | 7.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 470       | 5.85%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 414       | 5.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 378       | 4.71%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 295       | 3.67%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 246       | 3.06%   |
| Intel Haswell-ULT HD Audio Controller                                      | 198       | 2.47%   |
| Intel 8 Series HD Audio Controller                                         | 198       | 2.47%   |
| Intel Comet Lake PCH-LP cAVS                                               | 189       | 2.35%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 186       | 2.32%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 176       | 2.19%   |
| Intel Broadwell-U Audio Controller                                         | 176       | 2.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 175       | 2.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 170       | 2.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 168       | 2.09%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 159       | 1.98%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 138       | 1.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 135       | 1.68%   |
| AMD FCH Azalia Controller                                                  | 128       | 1.59%   |
| Intel Comet Lake PCH cAVS                                                  | 124       | 1.54%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 121       | 1.51%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 116       | 1.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 112       | 1.39%   |
| Nvidia GA106 High Definition Audio Controller                              | 104       | 1.3%    |
| Nvidia Audio device                                                        | 99        | 1.23%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 97        | 1.21%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 80        | 1%      |
| Nvidia GA104 High Definition Audio Controller                              | 77        | 0.96%   |
| AMD Kabini HDMI/DP Audio                                                   | 72        | 0.9%    |
| AMD High Definition Audio Controller                                       | 64        | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 63        | 0.78%   |
| Nvidia TU106 High Definition Audio Controller                              | 62        | 0.77%   |
| Nvidia GF108 High Definition Audio Controller                              | 58        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 58        | 0.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 58        | 0.72%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 57        | 0.71%   |
| Intel CM238 HD Audio Controller                                            | 56        | 0.7%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 54        | 0.67%   |
| Nvidia GP107GL High Definition Audio Controller                            | 53        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 1094      | 31.17%  |
| SK hynix                                | 825       | 23.5%   |
| Micron Technology                       | 493       | 14.05%  |
| Kingston                                | 261       | 7.44%   |
| Crucial                                 | 170       | 4.84%   |
| Unknown                                 | 115       | 3.28%   |
| A-DATA Technology                       | 84        | 2.39%   |
| Unknown (ABCD)                          | 71        | 2.02%   |
| Ramaxel Technology                      | 71        | 2.02%   |
| Nanya Technology                        | 41        | 1.17%   |
| Elpida                                  | 33        | 0.94%   |
| Corsair                                 | 31        | 0.88%   |
| Unknown                                 | 30        | 0.85%   |
| Smart                                   | 25        | 0.71%   |
| G.Skill                                 | 19        | 0.54%   |
| Team                                    | 16        | 0.46%   |
| Patriot                                 | 10        | 0.28%   |
| Smart Brazil                            | 9         | 0.26%   |
| Transcend                               | 7         | 0.2%    |
| GOODRAM                                 | 7         | 0.2%    |
| ChangXin Memory                         | 7         | 0.2%    |
| Goldkey                                 | 6         | 0.17%   |
| Wilk                                    | 4         | 0.11%   |
| Neo Forza                               | 4         | 0.11%   |
| Toshiba                                 | 3         | 0.09%   |
| SHARETRONIC                             | 3         | 0.09%   |
| PNY                                     | 3         | 0.09%   |
| fef5                                    | 3         | 0.09%   |
| Avant                                   | 3         | 0.09%   |
| ASint Technology                        | 3         | 0.09%   |
| Apacer                                  | 3         | 0.09%   |
| AMD                                     | 3         | 0.09%   |
| Unknown (768A)                          | 2         | 0.06%   |
| Teikon                                  | 2         | 0.06%   |
| Smart Modular                           | 2         | 0.06%   |
| Silicon Power Computer & Communications | 2         | 0.06%   |
| Silicon Power                           | 2         | 0.06%   |
| Qimonda                                 | 2         | 0.06%   |
| OM Nanotech                             | 2         | 0.06%   |
| Netac                                   | 2         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 79        | 2.15%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 68        | 1.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 52        | 1.41%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 42        | 1.14%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 38        | 1.03%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 36        | 0.98%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 35        | 0.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 35        | 0.95%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 35        | 0.95%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 32        | 0.87%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 31        | 0.84%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 30        | 0.82%   |
| Unknown                                                          | 30        | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 28        | 0.76%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 27        | 0.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 26        | 0.71%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 25        | 0.68%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 25        | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 24        | 0.65%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 24        | 0.65%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 23        | 0.63%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 0.6%    |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 22        | 0.6%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 21        | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.54%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 20        | 0.54%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 20        | 0.54%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 20        | 0.54%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 20        | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.54%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 20        | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 20        | 0.54%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 19        | 0.52%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 19        | 0.52%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 19        | 0.52%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 19        | 0.52%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 19        | 0.52%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 18        | 0.49%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 18        | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 1687      | 56.36%  |
| DDR3    | 686       | 22.92%  |
| LPDDR4  | 260       | 8.69%   |
| LPDDR3  | 113       | 3.78%   |
| DDR5    | 112       | 3.74%   |
| LPDDR5  | 58        | 1.94%   |
| DDR2    | 42        | 1.4%    |
| SDRAM   | 21        | 0.7%    |
| Unknown | 11        | 0.37%   |
| DDR     | 2         | 0.07%   |
| DRAM    | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 2513      | 82.86%  |
| Row Of Chips    | 471       | 15.53%  |
| Unknown         | 20        | 0.66%   |
| Chip            | 16        | 0.53%   |
| DIMM            | 11        | 0.36%   |
| Proprietary Car | 2         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size   | Notebooks | Percent |
|--------|-----------|---------|
| 8192   | 1403      | 43.34%  |
| 4096   | 845       | 26.1%   |
| 16384  | 618       | 19.09%  |
| 2048   | 209       | 6.46%   |
| 32768  | 115       | 3.55%   |
| 1024   | 42        | 1.3%    |
| 6144   | 2         | 0.06%   |
| 131072 | 1         | 0.03%   |
| 65536  | 1         | 0.03%   |
| 1536   | 1         | 0.03%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 929       | 29.18%  |
| 2667    | 631       | 19.82%  |
| 1600    | 516       | 16.21%  |
| 2400    | 246       | 7.73%   |
| 2133    | 158       | 4.96%   |
| 4800    | 113       | 3.55%   |
| 4267    | 103       | 3.23%   |
| 1334    | 101       | 3.17%   |
| 1333    | 65        | 2.04%   |
| 6400    | 62        | 1.95%   |
| 3266    | 38        | 1.19%   |
| 1867    | 31        | 0.97%   |
| 4266    | 29        | 0.91%   |
| 667     | 25        | 0.79%   |
| Unknown | 23        | 0.72%   |
| 1067    | 22        | 0.69%   |
| 4199    | 17        | 0.53%   |
| 3733    | 15        | 0.47%   |
| 8400    | 12        | 0.38%   |
| 1066    | 12        | 0.38%   |
| 800     | 8         | 0.25%   |
| 2933    | 5         | 0.16%   |
| 2048    | 4         | 0.13%   |
| 1866    | 3         | 0.09%   |
| 533     | 3         | 0.09%   |
| 5600    | 2         | 0.06%   |
| 975     | 2         | 0.06%   |
| 333     | 2         | 0.06%   |
| 5200    | 1         | 0.03%   |
| 3000    | 1         | 0.03%   |
| 2800    | 1         | 0.03%   |
| 2666    | 1         | 0.03%   |
| 1777    | 1         | 0.03%   |
| 1200    | 1         | 0.03%   |
| 933     | 1         | 0.03%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 20        | 38.46%  |
| Canon               | 9         | 17.31%  |
| Brother Industries  | 7         | 13.46%  |
| Seiko Epson         | 5         | 9.62%   |
| Samsung Electronics | 4         | 7.69%   |
| STMicroelectronics  | 2         | 3.85%   |
| Xiaomi              | 1         | 1.92%   |
| Xerox               | 1         | 1.92%   |
| QinHeng Electronics | 1         | 1.92%   |
| Kyocera             | 1         | 1.92%   |
| Unknown             | 1         | 1.92%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP DeskJet 2300 series                                    | 4         | 7.55%   |
| HP LaserJet 1020                                          | 2         | 3.77%   |
| HP DeskJet 2700 series                                    | 2         | 3.77%   |
| Brother DCP-1510                                          | 2         | 3.77%   |
| Xiaomi MiMouse 2                                          | 1         | 1.89%   |
| Xerox Phaser 3260                                         | 1         | 1.89%   |
| STMicroelectronics USB Printer P                          | 1         | 1.89%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 1.89%   |
| Seiko Epson XP-4100 Series                                | 1         | 1.89%   |
| Seiko Epson Stylus NX230/SX235W Series                    | 1         | 1.89%   |
| Seiko Epson L3110 Series                                  | 1         | 1.89%   |
| Seiko Epson FX-2190IIN                                    | 1         | 1.89%   |
| Seiko Epson Epson Stylus Photo 1500                       | 1         | 1.89%   |
| Samsung ML-216x Series Laser Printer                      | 1         | 1.89%   |
| Samsung ML-1610 Mono Laser Printer                        | 1         | 1.89%   |
| Samsung M2020 Series                                      | 1         | 1.89%   |
| Samsung C43x Series                                       | 1         | 1.89%   |
| QinHeng CH340S                                            | 1         | 1.89%   |
| Kyocera FS-1116MFP                                        | 1         | 1.89%   |
| HP OfficeJet 5600 (USBHUB)                                | 1         | 1.89%   |
| HP Officejet 4630 series                                  | 1         | 1.89%   |
| HP Officejet 4500 G510n-z                                 | 1         | 1.89%   |
| HP LaserJet M14-M17                                       | 1         | 1.89%   |
| HP LaserJet 4250                                          | 1         | 1.89%   |
| HP LaserJet 400 M401a                                     | 1         | 1.89%   |
| HP LaserJet 1300                                          | 1         | 1.89%   |
| HP LaserJet 1150                                          | 1         | 1.89%   |
| HP LaserJet 1018                                          | 1         | 1.89%   |
| HP Laser 107a                                             | 1         | 1.89%   |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 1.89%   |
| HP Color LaserJet CP1215                                  | 1         | 1.89%   |
| HP color LaserJet 5550                                    | 1         | 1.89%   |
| Canon SELPHY CP400                                        | 1         | 1.89%   |
| Canon PIXMA MX330                                         | 1         | 1.89%   |
| Canon PIXMA MG2900 Series                                 | 1         | 1.89%   |
| Canon MF633C/635C                                         | 1         | 1.89%   |
| Canon MF4100 series                                       | 1         | 1.89%   |
| Canon MF3110                                              | 1         | 1.89%   |
| Canon LBP6030w/6018w                                      | 1         | 1.89%   |
| Canon LBP2900                                             | 1         | 1.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 4         | 44.44%  |
| Seiko Epson     | 2         | 22.22%  |
| Mustek Systems  | 1         | 11.11%  |
| Hewlett-Packard | 1         | 11.11%  |
| AGFA-Gevaert NV | 1         | 11.11%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO] | 1         | 11.11%  |
| Seiko Epson ES-D200 [GT-S50]                      | 1         | 11.11%  |
| Mustek Systems BearPaw 2448 CU Pro                | 1         | 11.11%  |
| HP OfficeJet 6110                                 | 1         | 11.11%  |
| Canon CanoScan LIDE 25                            | 1         | 11.11%  |
| Canon CanoScan LiDE 110                           | 1         | 11.11%  |
| Canon CanoScan LiDE 100                           | 1         | 11.11%  |
| Canon CanoScan 4200F                              | 1         | 11.11%  |
| AGFA-Gevaert NV SnapScan 1212U (?)                | 1         | 11.11%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1020      | 20.77%  |
| IMC Networks                           | 561       | 11.42%  |
| Microdia                               | 502       | 10.22%  |
| Realtek Semiconductor                  | 392       | 7.98%   |
| Quanta                                 | 335       | 6.82%   |
| Sunplus Innovation Technology          | 319       | 6.5%    |
| Cheng Uei Precision Industry (Foxlink) | 207       | 4.22%   |
| Bison Electronics                      | 204       | 4.15%   |
| Acer                                   | 172       | 3.5%    |
| Luxvisions Innotech Limited            | 152       | 3.1%    |
| Suyin                                  | 135       | 2.75%   |
| Syntek                                 | 130       | 2.65%   |
| Lite-On Technology                     | 114       | 2.32%   |
| Apple                                  | 112       | 2.28%   |
| Logitech                               | 68        | 1.38%   |
| Alcor Micro                            | 55        | 1.12%   |
| Silicon Motion                         | 54        | 1.1%    |
| Sonix Technology                       | 44        | 0.9%    |
| Samsung Electronics                    | 42        | 0.86%   |
| Ricoh                                  | 36        | 0.73%   |
| SunplusIT                              | 26        | 0.53%   |
| USB Camera                             | 22        | 0.45%   |
| Lenovo                                 | 22        | 0.45%   |
| Primax Electronics                     | 20        | 0.41%   |
| Importek                               | 19        | 0.39%   |
| Y Media                                | 16        | 0.33%   |
| ALi                                    | 15        | 0.31%   |
| Z-Star Microelectronics                | 12        | 0.24%   |
| Microsoft                              | 8         | 0.16%   |
| Sunplus Technology                     | 5         | 0.1%    |
| OmniVision Technologies                | 5         | 0.1%    |
| Intel                                  | 5         | 0.1%    |
| DigiTech                               | 5         | 0.1%    |
| Unknown                                | 5         | 0.1%    |
| WaveRider Communications               | 3         | 0.06%   |
| Unknown (3730304231385631394831)       | 3         | 0.06%   |
| Unknown                                | 3         | 0.06%   |
| Sunplus IT                             | 3         | 0.06%   |
| Shenzhen Kingcome Optoelectronic       | 3         | 0.06%   |
| LG Electronics                         | 3         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                       | 283       | 5.74%   |
| Chicony Integrated Camera                           | 231       | 4.68%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 154       | 3.12%   |
| IMC Networks Integrated Camera                      | 147       | 2.98%   |
| Realtek Integrated_Webcam_HD                        | 145       | 2.94%   |
| Sunplus Integrated_Webcam_HD                        | 97        | 1.97%   |
| Chicony HD WebCam                                   | 96        | 1.95%   |
| Syntek Integrated Camera                            | 86        | 1.74%   |
| Acer Integrated Camera                              | 70        | 1.42%   |
| Chicony HP HD Camera                                | 64        | 1.3%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 58        | 1.18%   |
| Quanta HD User Facing                               | 53        | 1.07%   |
| Quanta HP HD Camera                                 | 51        | 1.03%   |
| IMC Networks HD Camera                              | 48        | 0.97%   |
| Bison Integrated Camera                             | 48        | 0.97%   |
| Sunplus HD WebCam                                   | 45        | 0.91%   |
| Samsung Galaxy A5 (MTP)                             | 42        | 0.85%   |
| Quanta HP TrueVision HD Camera                      | 42        | 0.85%   |
| Lite-On Integrated Camera                           | 38        | 0.77%   |
| Luxvisions Innotech Limited Integrated Camera       | 37        | 0.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 37        | 0.75%   |
| Acer HD Webcam                                      | 37        | 0.75%   |
| Chicony USB2.0 Camera                               | 35        | 0.71%   |
| Chicony HD User Facing                              | 35        | 0.71%   |
| Chicony TOSHIBA Web Camera - HD                     | 34        | 0.69%   |
| Chicony HP Truevision HD camera                     | 34        | 0.69%   |
| Luxvisions Innotech Limited HP HD Camera            | 32        | 0.65%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 32        | 0.65%   |
| Quanta HP Wide Vision HD Camera                     | 31        | 0.63%   |
| Bison SunplusIT Integrated Camera                   | 31        | 0.63%   |
| Sonix USB2.0 HD UVC WebCam                          | 30        | 0.61%   |
| Chicony HP Wide Vision HD Camera                    | 30        | 0.61%   |
| Realtek USB Camera                                  | 29        | 0.59%   |
| Microdia Integrated Webcam                          | 29        | 0.59%   |
| Suyin HP Truevision HD                              | 28        | 0.57%   |
| Realtek Integrated Webcam                           | 28        | 0.57%   |
| Chicony USB2.0 HD UVC WebCam                        | 28        | 0.57%   |
| Chicony HP Truevision HD                            | 28        | 0.57%   |
| Apple Built-in iSight                               | 28        | 0.57%   |
| Quanta ACER HD User Facing                          | 27        | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 335       | 30.68%  |
| Synaptics                          | 299       | 27.38%  |
| Shenzhen Goodix Technology         | 238       | 21.79%  |
| Elan Microelectronics              | 89        | 8.15%   |
| Upek                               | 39        | 3.57%   |
| AuthenTec                          | 34        | 3.11%   |
| LighTuning Technology              | 26        | 2.38%   |
| Realtek USB2.0 Finger Print Bridge | 14        | 1.28%   |
| STMicroelectronics                 | 6         | 0.55%   |
| Samsung Electronics                | 5         | 0.46%   |
| HOLTEK                             | 3         | 0.27%   |
| Focal-systems.Corp                 | 3         | 0.27%   |
| DigitalPersona                     | 1         | 0.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 177       | 16.21%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 89        | 8.15%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 79        | 7.23%   |
| Elan ELAN:ARM-M4                                                           | 54        | 4.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 47        | 4.3%    |
| Elan ELAN:Fingerprint                                                      | 35        | 3.21%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 34        | 3.11%   |
| Shenzhen Goodix FingerPrint                                                | 33        | 3.02%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 30        | 2.75%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 30        | 2.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 28        | 2.56%   |
| Shenzhen Goodix Fingerprint Reader                                         | 28        | 2.56%   |
| Validity Sensors Synaptics WBDI                                            | 27        | 2.47%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 27        | 2.47%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 26        | 2.38%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 24        | 2.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 23        | 2.11%   |
| Validity Sensors VFS491                                                    | 21        | 1.92%   |
| Validity Sensors Fingerprint scanner                                       | 20        | 1.83%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 18        | 1.65%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 17        | 1.56%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 16        | 1.47%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 16        | 1.47%   |
| Synaptics UWP WBDI Device                                                  | 16        | 1.47%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 15        | 1.37%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 15        | 1.37%   |
| AuthenTec Fingerprint Sensor                                               | 15        | 1.37%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 14        | 1.28%   |
| Synaptics UWP WBDI                                                         | 12        | 1.1%    |
| Synaptics WBDI                                                             | 11        | 1.01%   |
| Unknown                                                                    | 10        | 0.92%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 7         | 0.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.64%   |
| AuthenTec AES2810                                                          | 7         | 0.64%   |
| Validity Sensors VFS Fingerprint sensor                                    | 6         | 0.55%   |
| Synaptics  WBDI                                                            | 6         | 0.55%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.55%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 0.55%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 0.46%   |
| LighTuning Fingerprint Reader                                              | 4         | 0.37%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 240       | 56.6%   |
| Alcor Micro               | 113       | 26.65%  |
| O2 Micro                  | 21        | 4.95%   |
| Upek                      | 17        | 4.01%   |
| Gemalto (was Gemplus)     | 9         | 2.12%   |
| Lenovo                    | 7         | 1.65%   |
| Watchdata                 | 2         | 0.47%   |
| SCM Microsystems          | 2         | 0.47%   |
| OmniKey                   | 2         | 0.47%   |
| Chicony Electronics       | 2         | 0.47%   |
| Aladdin Knowledge Systems | 2         | 0.47%   |
| Reiner SCT Kartensysteme  | 1         | 0.24%   |
| NXP Semiconductors        | 1         | 0.24%   |
| Giesecke & Devrient       | 1         | 0.24%   |
| Fujitsu Siemens Computers | 1         | 0.24%   |
| Cherry                    | 1         | 0.24%   |
| C3PO                      | 1         | 0.24%   |
| Aktiv                     | 1         | 0.24%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 113       | 26.65%  |
| Broadcom 58200                                                               | 88        | 20.75%  |
| Broadcom BCM5880 Secure Applications Processor                               | 68        | 16.04%  |
| Broadcom 5880                                                                | 54        | 12.74%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 30        | 7.08%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 20        | 4.72%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 17        | 4.01%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 1.65%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 7         | 1.65%   |
| Watchdata USB Key                                                            | 2         | 0.47%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.47%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.47%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 0.47%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.24%   |
| OmniKey CardMan 4321                                                         | 1         | 0.24%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.24%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.24%   |
| NXP Semiconductors PR533                                                     | 1         | 0.24%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.24%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.24%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.24%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.24%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.24%   |
| C3PO LTC31v2                                                                 | 1         | 0.24%   |
| Aktiv Rutoken lite                                                           | 1         | 0.24%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 3090      | 57.18%  |
| 1     | 1827      | 33.81%  |
| 2     | 430       | 7.96%   |
| 3     | 46        | 0.85%   |
| 5     | 3         | 0.06%   |
| 8     | 2         | 0.04%   |
| 6     | 2         | 0.04%   |
| 4     | 2         | 0.04%   |
| 9     | 1         | 0.02%   |
| 7     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1067      | 37.65%  |
| Graphics card            | 634       | 22.37%  |
| Chipcard                 | 398       | 14.04%  |
| Net/wireless             | 236       | 8.33%   |
| Camera                   | 182       | 6.42%   |
| Multimedia controller    | 92        | 3.25%   |
| Bluetooth                | 70        | 2.47%   |
| Sound                    | 39        | 1.38%   |
| Storage                  | 36        | 1.27%   |
| Card reader              | 26        | 0.92%   |
| Net/ethernet             | 18        | 0.64%   |
| Communication controller | 18        | 0.64%   |
| Network                  | 13        | 0.46%   |
| Flash memory             | 3         | 0.11%   |
| Modem                    | 2         | 0.07%   |

