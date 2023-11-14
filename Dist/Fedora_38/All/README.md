Fedora 38 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Fedora 38.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora_38/Desktop/README.md) and [notebooks](/Dist/Fedora_38/Notebook/README.md).

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

Total: 3956

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E15 20RD0011IX     | Notebook    | [88cc97d0be](https://linux-hardware.org/?probe=88cc97d0be) | Nov 06, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [fe01dc6819](https://linux-hardware.org/?probe=fe01dc6819) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | Notebook    | [f09ace6b9d](https://linux-hardware.org/?probe=f09ace6b9d) | Nov 06, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [d57d789e77](https://linux-hardware.org/?probe=d57d789e77) | Nov 06, 2023 |
| HP            | G61                         | Notebook    | [65f7664fe3](https://linux-hardware.org/?probe=65f7664fe3) | Nov 06, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f87e3a97c4](https://linux-hardware.org/?probe=f87e3a97c4) | Nov 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3a2a72df26](https://linux-hardware.org/?probe=3a2a72df26) | Nov 06, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [3daa9909b3](https://linux-hardware.org/?probe=3daa9909b3) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [d643312744](https://linux-hardware.org/?probe=d643312744) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d61e270082](https://linux-hardware.org/?probe=d61e270082) | Nov 06, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [a8c249eafd](https://linux-hardware.org/?probe=a8c249eafd) | Nov 05, 2023 |
| ASUSTek       | X550WA                      | Notebook    | [8c15da796b](https://linux-hardware.org/?probe=8c15da796b) | Nov 05, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | Notebook    | [92ef56cc92](https://linux-hardware.org/?probe=92ef56cc92) | Nov 05, 2023 |
| Acer          | Predator PT516-52s          | Notebook    | [30b7a47643](https://linux-hardware.org/?probe=30b7a47643) | Nov 05, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [da97d12548](https://linux-hardware.org/?probe=da97d12548) | Nov 05, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [05a8c22a35](https://linux-hardware.org/?probe=05a8c22a35) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [e1d50d8743](https://linux-hardware.org/?probe=e1d50d8743) | Nov 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a42da62572](https://linux-hardware.org/?probe=a42da62572) | Nov 05, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [98439489ad](https://linux-hardware.org/?probe=98439489ad) | Nov 05, 2023 |
| HP            | 1494                        | Desktop     | [93e0e0302f](https://linux-hardware.org/?probe=93e0e0302f) | Nov 05, 2023 |
| Toshiba       | Satellite L845              | Notebook    | [4dc7e8931e](https://linux-hardware.org/?probe=4dc7e8931e) | Nov 05, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4998a82a6b](https://linux-hardware.org/?probe=4998a82a6b) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [539d8551fc](https://linux-hardware.org/?probe=539d8551fc) | Nov 05, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [a9ad2b542a](https://linux-hardware.org/?probe=a9ad2b542a) | Nov 05, 2023 |
| Dell          | Latitude E7440              | Notebook    | [5a151e929f](https://linux-hardware.org/?probe=5a151e929f) | Nov 05, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [f8860a91a3](https://linux-hardware.org/?probe=f8860a91a3) | Nov 05, 2023 |
| Lenovo        | S145-15IWL 81MV             | Notebook    | [d38fdaf0eb](https://linux-hardware.org/?probe=d38fdaf0eb) | Nov 04, 2023 |
| Lenovo        | ThinkPad W550s 20E2000PM... | Notebook    | [1294d54c1a](https://linux-hardware.org/?probe=1294d54c1a) | Nov 04, 2023 |
| MSI           | Modern 15 B7M               | Notebook    | [b4a588e60e](https://linux-hardware.org/?probe=b4a588e60e) | Nov 04, 2023 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [77f3748e01](https://linux-hardware.org/?probe=77f3748e01) | Nov 04, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [5d8cae0407](https://linux-hardware.org/?probe=5d8cae0407) | Nov 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b390f8cd05](https://linux-hardware.org/?probe=b390f8cd05) | Nov 04, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [7fb9150b16](https://linux-hardware.org/?probe=7fb9150b16) | Nov 04, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [1d8dad6600](https://linux-hardware.org/?probe=1d8dad6600) | Nov 04, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [a7f0f43604](https://linux-hardware.org/?probe=a7f0f43604) | Nov 04, 2023 |
| Sony          | VPCEH3J1E                   | Notebook    | [e0ae745034](https://linux-hardware.org/?probe=e0ae745034) | Nov 04, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | Notebook    | [d0d84fed9a](https://linux-hardware.org/?probe=d0d84fed9a) | Nov 04, 2023 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [8edaffcccb](https://linux-hardware.org/?probe=8edaffcccb) | Nov 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [50949c6e51](https://linux-hardware.org/?probe=50949c6e51) | Nov 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [85e528f1bf](https://linux-hardware.org/?probe=85e528f1bf) | Nov 04, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [8c23fbf7d1](https://linux-hardware.org/?probe=8c23fbf7d1) | Nov 04, 2023 |
| POV           | I102A                       | Notebook    | [955f97d47e](https://linux-hardware.org/?probe=955f97d47e) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [2ab63a2fb6](https://linux-hardware.org/?probe=2ab63a2fb6) | Nov 04, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [cfb51ce306](https://linux-hardware.org/?probe=cfb51ce306) | Nov 03, 2023 |
| Irbis         | NB211                       | Notebook    | [694ca0f127](https://linux-hardware.org/?probe=694ca0f127) | Nov 03, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [61342b31ea](https://linux-hardware.org/?probe=61342b31ea) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f4bae2d5b5](https://linux-hardware.org/?probe=f4bae2d5b5) | Nov 03, 2023 |
| HP            | 859C                        | Desktop     | [7928158950](https://linux-hardware.org/?probe=7928158950) | Nov 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ff0d013246](https://linux-hardware.org/?probe=ff0d013246) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [f9bdbf6371](https://linux-hardware.org/?probe=f9bdbf6371) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [bcea72b22f](https://linux-hardware.org/?probe=bcea72b22f) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [00a8b74f46](https://linux-hardware.org/?probe=00a8b74f46) | Nov 03, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | Notebook    | [6a2591b5e9](https://linux-hardware.org/?probe=6a2591b5e9) | Nov 03, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [3a4be91563](https://linux-hardware.org/?probe=3a4be91563) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [28990f206a](https://linux-hardware.org/?probe=28990f206a) | Nov 03, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [3618f2a4b5](https://linux-hardware.org/?probe=3618f2a4b5) | Nov 03, 2023 |
| Irbis         | NB211                       | Notebook    | [3ebca4338a](https://linux-hardware.org/?probe=3ebca4338a) | Nov 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f23e44229f](https://linux-hardware.org/?probe=f23e44229f) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [94cdd979b2](https://linux-hardware.org/?probe=94cdd979b2) | Nov 03, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [36fb8d63bb](https://linux-hardware.org/?probe=36fb8d63bb) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [0929326be0](https://linux-hardware.org/?probe=0929326be0) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [5149df3a58](https://linux-hardware.org/?probe=5149df3a58) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [26bc5f025c](https://linux-hardware.org/?probe=26bc5f025c) | Nov 02, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b58b97e74a](https://linux-hardware.org/?probe=b58b97e74a) | Nov 02, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [741bcd1343](https://linux-hardware.org/?probe=741bcd1343) | Nov 02, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | Notebook    | [56bbf7c0bb](https://linux-hardware.org/?probe=56bbf7c0bb) | Nov 02, 2023 |
| GreatWall     | W1011                       | Tablet      | [fe355d55c3](https://linux-hardware.org/?probe=fe355d55c3) | Nov 02, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cf88c7f3db](https://linux-hardware.org/?probe=cf88c7f3db) | Nov 02, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [bbe345cd5d](https://linux-hardware.org/?probe=bbe345cd5d) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [bb1da2575d](https://linux-hardware.org/?probe=bb1da2575d) | Nov 02, 2023 |
| Lenovo        | ThinkBook Plus G3 IAP 21... | Notebook    | [c6634f090f](https://linux-hardware.org/?probe=c6634f090f) | Nov 02, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [664191098d](https://linux-hardware.org/?probe=664191098d) | Nov 02, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [97ca7a0bfd](https://linux-hardware.org/?probe=97ca7a0bfd) | Nov 02, 2023 |
| ASRock        | B760M PG SONIC WiFi         | Desktop     | [71e1e69f30](https://linux-hardware.org/?probe=71e1e69f30) | Nov 02, 2023 |
| MSI           | IONA                        | Desktop     | [579757d1cf](https://linux-hardware.org/?probe=579757d1cf) | Nov 02, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [60c6e3a5d2](https://linux-hardware.org/?probe=60c6e3a5d2) | Nov 01, 2023 |
| ASUSTek       | M52AD_M12AD                 | Desktop     | [a75715ee4a](https://linux-hardware.org/?probe=a75715ee4a) | Nov 01, 2023 |
| Dell          | G3 3579                     | Notebook    | [0b33f63284](https://linux-hardware.org/?probe=0b33f63284) | Nov 01, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [ba3faece8c](https://linux-hardware.org/?probe=ba3faece8c) | Nov 01, 2023 |
| ASRock        | H97M Anniversary            | Desktop     | [6c66e3862d](https://linux-hardware.org/?probe=6c66e3862d) | Nov 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [685b1b18eb](https://linux-hardware.org/?probe=685b1b18eb) | Nov 01, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [829c16d044](https://linux-hardware.org/?probe=829c16d044) | Nov 01, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [236c6c4f9a](https://linux-hardware.org/?probe=236c6c4f9a) | Nov 01, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [37b53d54e8](https://linux-hardware.org/?probe=37b53d54e8) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [bbf2002cea](https://linux-hardware.org/?probe=bbf2002cea) | Nov 01, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [bb9a00e5b5](https://linux-hardware.org/?probe=bb9a00e5b5) | Nov 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [7dd972fb0d](https://linux-hardware.org/?probe=7dd972fb0d) | Nov 01, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [63fa5e90b2](https://linux-hardware.org/?probe=63fa5e90b2) | Nov 01, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [b724e20965](https://linux-hardware.org/?probe=b724e20965) | Nov 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [636993569c](https://linux-hardware.org/?probe=636993569c) | Nov 01, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [168597b33e](https://linux-hardware.org/?probe=168597b33e) | Nov 01, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [d0be3aec4e](https://linux-hardware.org/?probe=d0be3aec4e) | Nov 01, 2023 |
| HP            | 8767 A                      | Desktop     | [618323a058](https://linux-hardware.org/?probe=618323a058) | Nov 01, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [f047c1d264](https://linux-hardware.org/?probe=f047c1d264) | Nov 01, 2023 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [0c51ffc039](https://linux-hardware.org/?probe=0c51ffc039) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | Notebook    | [0d9316dbcf](https://linux-hardware.org/?probe=0d9316dbcf) | Oct 31, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [7296b22122](https://linux-hardware.org/?probe=7296b22122) | Oct 31, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [3b79851103](https://linux-hardware.org/?probe=3b79851103) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [aef3dccca0](https://linux-hardware.org/?probe=aef3dccca0) | Oct 31, 2023 |
| Alienware     | 14                          | Notebook    | [e88b7c0ac6](https://linux-hardware.org/?probe=e88b7c0ac6) | Oct 31, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [af854a07c5](https://linux-hardware.org/?probe=af854a07c5) | Oct 31, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | Notebook    | [fadc897ee2](https://linux-hardware.org/?probe=fadc897ee2) | Oct 31, 2023 |
| HP            | Elite x360 1040 14 inch ... | Convertible | [f7385ed51b](https://linux-hardware.org/?probe=f7385ed51b) | Oct 31, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [ebec8d6fd1](https://linux-hardware.org/?probe=ebec8d6fd1) | Oct 31, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [ef58eef71a](https://linux-hardware.org/?probe=ef58eef71a) | Oct 31, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [069872b404](https://linux-hardware.org/?probe=069872b404) | Oct 31, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [0ea1a71a53](https://linux-hardware.org/?probe=0ea1a71a53) | Oct 31, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [3179102373](https://linux-hardware.org/?probe=3179102373) | Oct 31, 2023 |
| Lenovo        | ThinkPad T490 20N2S0QE00    | Notebook    | [9785ae64c0](https://linux-hardware.org/?probe=9785ae64c0) | Oct 31, 2023 |
| Lenovo        | ThinkPad E470 20H1006KIX    | Notebook    | [d84959fadc](https://linux-hardware.org/?probe=d84959fadc) | Oct 31, 2023 |
| HP            | ProBook 645 G1              | Notebook    | [b637cedab4](https://linux-hardware.org/?probe=b637cedab4) | Oct 31, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [54a64f0a7e](https://linux-hardware.org/?probe=54a64f0a7e) | Oct 31, 2023 |
| Dell          | Latitude 5414               | Notebook    | [fd7b086e1b](https://linux-hardware.org/?probe=fd7b086e1b) | Oct 31, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [487222ef3e](https://linux-hardware.org/?probe=487222ef3e) | Oct 31, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [a9a2e2ab03](https://linux-hardware.org/?probe=a9a2e2ab03) | Oct 30, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [055e34b095](https://linux-hardware.org/?probe=055e34b095) | Oct 30, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [25431e9c91](https://linux-hardware.org/?probe=25431e9c91) | Oct 30, 2023 |
| ASUSTek       | X555UJ                      | Notebook    | [de6e2775a4](https://linux-hardware.org/?probe=de6e2775a4) | Oct 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S03Q00    | Notebook    | [de24032ac7](https://linux-hardware.org/?probe=de24032ac7) | Oct 30, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | Desktop     | [53e53337bb](https://linux-hardware.org/?probe=53e53337bb) | Oct 30, 2023 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [0b129d4a95](https://linux-hardware.org/?probe=0b129d4a95) | Oct 30, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [ad34d5b54f](https://linux-hardware.org/?probe=ad34d5b54f) | Oct 30, 2023 |
| Dell          | Latitude 5490               | Notebook    | [63f4fce332](https://linux-hardware.org/?probe=63f4fce332) | Oct 30, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | Notebook    | [249ea48334](https://linux-hardware.org/?probe=249ea48334) | Oct 30, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [624a99186e](https://linux-hardware.org/?probe=624a99186e) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | Notebook    | [6cbfd91e78](https://linux-hardware.org/?probe=6cbfd91e78) | Oct 30, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | Notebook    | [8730c3de9d](https://linux-hardware.org/?probe=8730c3de9d) | Oct 30, 2023 |
| Dell          | Precision 3551              | Notebook    | [4f054a63ef](https://linux-hardware.org/?probe=4f054a63ef) | Oct 30, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [949a1ab2bb](https://linux-hardware.org/?probe=949a1ab2bb) | Oct 30, 2023 |
| Fujitsu       | D3049-B1 S26361-D3049-B1... | Server      | [261e5240fe](https://linux-hardware.org/?probe=261e5240fe) | Oct 30, 2023 |
| ASUSTek       | F3Sv                        | Notebook    | [3da2894228](https://linux-hardware.org/?probe=3da2894228) | Oct 30, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [cfeea44315](https://linux-hardware.org/?probe=cfeea44315) | Oct 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [b1adeb2f86](https://linux-hardware.org/?probe=b1adeb2f86) | Oct 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fe7dbb2385](https://linux-hardware.org/?probe=fe7dbb2385) | Oct 29, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [e41780f56a](https://linux-hardware.org/?probe=e41780f56a) | Oct 29, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [a526322459](https://linux-hardware.org/?probe=a526322459) | Oct 29, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [7d0eb8f922](https://linux-hardware.org/?probe=7d0eb8f922) | Oct 29, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [ff941d75c9](https://linux-hardware.org/?probe=ff941d75c9) | Oct 29, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [307134fa91](https://linux-hardware.org/?probe=307134fa91) | Oct 29, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [09ee918b60](https://linux-hardware.org/?probe=09ee918b60) | Oct 29, 2023 |
| HP            | Notebook                    | Notebook    | [79843ed7c3](https://linux-hardware.org/?probe=79843ed7c3) | Oct 29, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [519bf4fbae](https://linux-hardware.org/?probe=519bf4fbae) | Oct 29, 2023 |
| Dell          | Precision 5480              | Notebook    | [5df408828c](https://linux-hardware.org/?probe=5df408828c) | Oct 29, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [deef4da5dc](https://linux-hardware.org/?probe=deef4da5dc) | Oct 29, 2023 |
| MSI           | PRO B650M-P                 | Desktop     | [521367f574](https://linux-hardware.org/?probe=521367f574) | Oct 29, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [12d5c69b6a](https://linux-hardware.org/?probe=12d5c69b6a) | Oct 29, 2023 |
| ASRock        | X399 Taichi                 | Desktop     | [78ab56301b](https://linux-hardware.org/?probe=78ab56301b) | Oct 29, 2023 |
| raspberryp... | Raspberry Pi 4 Model B R... | Soc         | [2aa83dbdfc](https://linux-hardware.org/?probe=2aa83dbdfc) | Oct 29, 2023 |
| Dell          | Precision M6800             | Notebook    | [a5e2100522](https://linux-hardware.org/?probe=a5e2100522) | Oct 29, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [dee4ef8a3b](https://linux-hardware.org/?probe=dee4ef8a3b) | Oct 29, 2023 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [f589e0c914](https://linux-hardware.org/?probe=f589e0c914) | Oct 28, 2023 |
| Lenovo        | ThinkPad E14 20RA0020AU     | Notebook    | [1d1a7bd472](https://linux-hardware.org/?probe=1d1a7bd472) | Oct 28, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [8dd9b1dbde](https://linux-hardware.org/?probe=8dd9b1dbde) | Oct 28, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | Notebook    | [da25874b12](https://linux-hardware.org/?probe=da25874b12) | Oct 28, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [762e9a6d4d](https://linux-hardware.org/?probe=762e9a6d4d) | Oct 28, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b4645667a4](https://linux-hardware.org/?probe=b4645667a4) | Oct 28, 2023 |
| HP            | 8053                        | Desktop     | [352cc1bad8](https://linux-hardware.org/?probe=352cc1bad8) | Oct 28, 2023 |
| HP            | Notebook                    | Notebook    | [791dfef3cc](https://linux-hardware.org/?probe=791dfef3cc) | Oct 28, 2023 |
| HP            | 8053                        | Desktop     | [25f2c6e830](https://linux-hardware.org/?probe=25f2c6e830) | Oct 28, 2023 |
| ASUSTek       | Z10PE-D8 WS                 | Desktop     | [4562f80268](https://linux-hardware.org/?probe=4562f80268) | Oct 28, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [217aaa00da](https://linux-hardware.org/?probe=217aaa00da) | Oct 28, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | Notebook    | [f78fcbc612](https://linux-hardware.org/?probe=f78fcbc612) | Oct 28, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [77541125c0](https://linux-hardware.org/?probe=77541125c0) | Oct 28, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [944bb2ecb2](https://linux-hardware.org/?probe=944bb2ecb2) | Oct 28, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [d78b4f6222](https://linux-hardware.org/?probe=d78b4f6222) | Oct 28, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5591930fc0](https://linux-hardware.org/?probe=5591930fc0) | Oct 27, 2023 |
| Lenovo        | YogaAir 14s APU8 83AA       | Notebook    | [4f120347b7](https://linux-hardware.org/?probe=4f120347b7) | Oct 27, 2023 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [b18bbae606](https://linux-hardware.org/?probe=b18bbae606) | Oct 27, 2023 |
| Dell          | Precision 5530              | Notebook    | [e707fe59cc](https://linux-hardware.org/?probe=e707fe59cc) | Oct 27, 2023 |
| HP            | 843F                        | Desktop     | [c39418a5fe](https://linux-hardware.org/?probe=c39418a5fe) | Oct 27, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [4eacfc5dd8](https://linux-hardware.org/?probe=4eacfc5dd8) | Oct 27, 2023 |
| Acer          | Aspire V5-572P              | Notebook    | [18938afb70](https://linux-hardware.org/?probe=18938afb70) | Oct 27, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [bd82dd57be](https://linux-hardware.org/?probe=bd82dd57be) | Oct 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S69X08    | Notebook    | [61da163866](https://linux-hardware.org/?probe=61da163866) | Oct 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [1cb73bada5](https://linux-hardware.org/?probe=1cb73bada5) | Oct 27, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [346fad17ff](https://linux-hardware.org/?probe=346fad17ff) | Oct 27, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [481d6c83fb](https://linux-hardware.org/?probe=481d6c83fb) | Oct 27, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [51e6c3cef4](https://linux-hardware.org/?probe=51e6c3cef4) | Oct 27, 2023 |
| Lenovo        | 300w Gen 3 82J1             | Convertible | [570c03f594](https://linux-hardware.org/?probe=570c03f594) | Oct 27, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [057e350f82](https://linux-hardware.org/?probe=057e350f82) | Oct 27, 2023 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [a20c6e2c77](https://linux-hardware.org/?probe=a20c6e2c77) | Oct 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [9650e62539](https://linux-hardware.org/?probe=9650e62539) | Oct 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [82ba56a70d](https://linux-hardware.org/?probe=82ba56a70d) | Oct 26, 2023 |
| Dell          | Latitude 5440               | Notebook    | [e7d56ee207](https://linux-hardware.org/?probe=e7d56ee207) | Oct 26, 2023 |
| Dell          | Latitude 7490               | Notebook    | [58324a8dfd](https://linux-hardware.org/?probe=58324a8dfd) | Oct 26, 2023 |
| ASUSTek       | TUF Gaming B760M-PLUS       | Desktop     | [a576bfd0b1](https://linux-hardware.org/?probe=a576bfd0b1) | Oct 26, 2023 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [3aa43f0bf7](https://linux-hardware.org/?probe=3aa43f0bf7) | Oct 26, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [3279dc82a1](https://linux-hardware.org/?probe=3279dc82a1) | Oct 26, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [ccee3b60c7](https://linux-hardware.org/?probe=ccee3b60c7) | Oct 26, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [4506629e6a](https://linux-hardware.org/?probe=4506629e6a) | Oct 26, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [fff464540a](https://linux-hardware.org/?probe=fff464540a) | Oct 26, 2023 |
| Intel         | NUC6i5SYB H81131-505        | Mini pc     | [992a1810e2](https://linux-hardware.org/?probe=992a1810e2) | Oct 26, 2023 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [67b3859d9d](https://linux-hardware.org/?probe=67b3859d9d) | Oct 26, 2023 |
| Toshiba       | Satellite L75D-A            | Notebook    | [82efb2dd44](https://linux-hardware.org/?probe=82efb2dd44) | Oct 26, 2023 |
| Apple         | MacBookPro15,4              | Notebook    | [751e98cb04](https://linux-hardware.org/?probe=751e98cb04) | Oct 26, 2023 |
| Schenker      | VISION (M23)                | Notebook    | [64cead24ba](https://linux-hardware.org/?probe=64cead24ba) | Oct 26, 2023 |
| Dell          | 0KJCC5 A00                  | Desktop     | [f4f5605117](https://linux-hardware.org/?probe=f4f5605117) | Oct 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ca40b148a0](https://linux-hardware.org/?probe=ca40b148a0) | Oct 26, 2023 |
| ASRock        | 890GM Pro3                  | Desktop     | [ca2fb95579](https://linux-hardware.org/?probe=ca2fb95579) | Oct 25, 2023 |
| ASUSTek       | ROG STRIX B760-I GAMING ... | Desktop     | [d5afb1c9da](https://linux-hardware.org/?probe=d5afb1c9da) | Oct 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [a17a8b4360](https://linux-hardware.org/?probe=a17a8b4360) | Oct 25, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [a3a2c0b74b](https://linux-hardware.org/?probe=a3a2c0b74b) | Oct 25, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [673c675bc6](https://linux-hardware.org/?probe=673c675bc6) | Oct 25, 2023 |
| HP            | 8433 11                     | Desktop     | [902343e220](https://linux-hardware.org/?probe=902343e220) | Oct 25, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [9207de9b44](https://linux-hardware.org/?probe=9207de9b44) | Oct 25, 2023 |
| Dell          | 0C27VV A02                  | Desktop     | [7a88945a88](https://linux-hardware.org/?probe=7a88945a88) | Oct 25, 2023 |
| Timi          | TM1701                      | Notebook    | [13801c83a2](https://linux-hardware.org/?probe=13801c83a2) | Oct 25, 2023 |
| Supermicro    | X8SAX                       | Desktop     | [5d90e1af8c](https://linux-hardware.org/?probe=5d90e1af8c) | Oct 25, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | Notebook    | [7476940ad0](https://linux-hardware.org/?probe=7476940ad0) | Oct 25, 2023 |
| ASRock        | FM2A88X+ Killer             | Desktop     | [c9b5ffd5b8](https://linux-hardware.org/?probe=c9b5ffd5b8) | Oct 24, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [d4a28890a5](https://linux-hardware.org/?probe=d4a28890a5) | Oct 24, 2023 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [2a476e881e](https://linux-hardware.org/?probe=2a476e881e) | Oct 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3eee01cd16](https://linux-hardware.org/?probe=3eee01cd16) | Oct 24, 2023 |
| TrekStor      | Primebook C11B              | Convertible | [7038c45f32](https://linux-hardware.org/?probe=7038c45f32) | Oct 24, 2023 |
| Lenovo        | ThinkPad T410 2537NT8       | Notebook    | [52b5addead](https://linux-hardware.org/?probe=52b5addead) | Oct 24, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [ed696b1c52](https://linux-hardware.org/?probe=ed696b1c52) | Oct 24, 2023 |
| Dell          | XPS 9315                    | Notebook    | [9246bb9a28](https://linux-hardware.org/?probe=9246bb9a28) | Oct 24, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [41fd350f12](https://linux-hardware.org/?probe=41fd350f12) | Oct 24, 2023 |
| ASUSTek       | P5Q3                        | Desktop     | [660547e520](https://linux-hardware.org/?probe=660547e520) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ed7e1a1932](https://linux-hardware.org/?probe=ed7e1a1932) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | Notebook    | [84883d560d](https://linux-hardware.org/?probe=84883d560d) | Oct 24, 2023 |
| GPD           | G1621-02                    | Notebook    | [ea3897be17](https://linux-hardware.org/?probe=ea3897be17) | Oct 24, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [92dbf8615b](https://linux-hardware.org/?probe=92dbf8615b) | Oct 24, 2023 |
| Lenovo        | 371E SDK0J40709 WIN 3259... | All in one  | [47d70a6fcb](https://linux-hardware.org/?probe=47d70a6fcb) | Oct 24, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4e13c711c7](https://linux-hardware.org/?probe=4e13c711c7) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [37be8caf53](https://linux-hardware.org/?probe=37be8caf53) | Oct 23, 2023 |
| Acer          | Aspire X1900                | Desktop     | [6454f71562](https://linux-hardware.org/?probe=6454f71562) | Oct 23, 2023 |
| Dell          | Latitude 5320               | Notebook    | [520c2effa3](https://linux-hardware.org/?probe=520c2effa3) | Oct 23, 2023 |
| MSI           | Z170A GAMING PRO CARBON     | Desktop     | [4440cac740](https://linux-hardware.org/?probe=4440cac740) | Oct 23, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [6d63f6c5ba](https://linux-hardware.org/?probe=6d63f6c5ba) | Oct 23, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [2ac0a2ecc8](https://linux-hardware.org/?probe=2ac0a2ecc8) | Oct 23, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [0994b60ab4](https://linux-hardware.org/?probe=0994b60ab4) | Oct 23, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [7c86d9f1e5](https://linux-hardware.org/?probe=7c86d9f1e5) | Oct 23, 2023 |
| ASRock        | D1800M                      | Desktop     | [d31fadd4a5](https://linux-hardware.org/?probe=d31fadd4a5) | Oct 23, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [2af156789d](https://linux-hardware.org/?probe=2af156789d) | Oct 23, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [eb9bba4f5c](https://linux-hardware.org/?probe=eb9bba4f5c) | Oct 23, 2023 |
| Dell          | G15 5515                    | Notebook    | [16754901cb](https://linux-hardware.org/?probe=16754901cb) | Oct 23, 2023 |
| HP            | ProBook 4530s               | Notebook    | [104df79d8e](https://linux-hardware.org/?probe=104df79d8e) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SS0... | Notebook    | [9877bb17c1](https://linux-hardware.org/?probe=9877bb17c1) | Oct 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2e4786bb32](https://linux-hardware.org/?probe=2e4786bb32) | Oct 23, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [1f16388df7](https://linux-hardware.org/?probe=1f16388df7) | Oct 23, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [7190f336e0](https://linux-hardware.org/?probe=7190f336e0) | Oct 23, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [fc5437cf30](https://linux-hardware.org/?probe=fc5437cf30) | Oct 22, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [7981b12a61](https://linux-hardware.org/?probe=7981b12a61) | Oct 22, 2023 |
| MSI           | IONA                        | Desktop     | [e444708510](https://linux-hardware.org/?probe=e444708510) | Oct 22, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [705aaea029](https://linux-hardware.org/?probe=705aaea029) | Oct 22, 2023 |
| Dell          | XPS 13 9300                 | Notebook    | [ccf935ca37](https://linux-hardware.org/?probe=ccf935ca37) | Oct 22, 2023 |
| HP            | ENVY Laptop 13-ba0xxx       | Notebook    | [38823c0a55](https://linux-hardware.org/?probe=38823c0a55) | Oct 22, 2023 |
| Lenovo        | ThinkPad L13 20R30005RT     | Notebook    | [23a9651432](https://linux-hardware.org/?probe=23a9651432) | Oct 22, 2023 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | Notebook    | [c725f222a3](https://linux-hardware.org/?probe=c725f222a3) | Oct 22, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [92d3be3fff](https://linux-hardware.org/?probe=92d3be3fff) | Oct 22, 2023 |
| AZW           | SER V1                      | Desktop     | [4262bad6c4](https://linux-hardware.org/?probe=4262bad6c4) | Oct 22, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [7105618a0a](https://linux-hardware.org/?probe=7105618a0a) | Oct 22, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0b91bab038](https://linux-hardware.org/?probe=0b91bab038) | Oct 22, 2023 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [1eed0a53b6](https://linux-hardware.org/?probe=1eed0a53b6) | Oct 22, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3ba4cde45a](https://linux-hardware.org/?probe=3ba4cde45a) | Oct 22, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [04a430e244](https://linux-hardware.org/?probe=04a430e244) | Oct 22, 2023 |
| HP            | 83E9                        | Desktop     | [c324d1ee0a](https://linux-hardware.org/?probe=c324d1ee0a) | Oct 22, 2023 |
| HP            | 83E9                        | Desktop     | [8102d00cdc](https://linux-hardware.org/?probe=8102d00cdc) | Oct 22, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [5d9310d00e](https://linux-hardware.org/?probe=5d9310d00e) | Oct 21, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [7c383004b6](https://linux-hardware.org/?probe=7c383004b6) | Oct 21, 2023 |
| ASUSTek       | N551JK                      | Notebook    | [863f309154](https://linux-hardware.org/?probe=863f309154) | Oct 21, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [1f4b7f796f](https://linux-hardware.org/?probe=1f4b7f796f) | Oct 21, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [dcef0a70af](https://linux-hardware.org/?probe=dcef0a70af) | Oct 21, 2023 |
| Dell          | Latitude E6320              | Notebook    | [c6965e07e3](https://linux-hardware.org/?probe=c6965e07e3) | Oct 21, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [37389245cd](https://linux-hardware.org/?probe=37389245cd) | Oct 21, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [ce517165dc](https://linux-hardware.org/?probe=ce517165dc) | Oct 21, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [422e70640a](https://linux-hardware.org/?probe=422e70640a) | Oct 21, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [64148c88c0](https://linux-hardware.org/?probe=64148c88c0) | Oct 21, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [ffeaa7da2f](https://linux-hardware.org/?probe=ffeaa7da2f) | Oct 21, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [c1ad18b5c9](https://linux-hardware.org/?probe=c1ad18b5c9) | Oct 21, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [f1b2f555ef](https://linux-hardware.org/?probe=f1b2f555ef) | Oct 21, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | Notebook    | [3afdd1b0da](https://linux-hardware.org/?probe=3afdd1b0da) | Oct 21, 2023 |
| ASRock        | H610M-HVS/M.2 R2.0          | Desktop     | [74df5e1893](https://linux-hardware.org/?probe=74df5e1893) | Oct 21, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [a149fbf417](https://linux-hardware.org/?probe=a149fbf417) | Oct 21, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [466e429ddd](https://linux-hardware.org/?probe=466e429ddd) | Oct 21, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [edefe667a4](https://linux-hardware.org/?probe=edefe667a4) | Oct 21, 2023 |
| ASUSTek       | X442UAR                     | Notebook    | [454f454638](https://linux-hardware.org/?probe=454f454638) | Oct 21, 2023 |
| Packard Be... | IMEDIA S3840                | Desktop     | [3cc1398528](https://linux-hardware.org/?probe=3cc1398528) | Oct 21, 2023 |
| Dell          | Latitude 7440               | Notebook    | [e0997ac78c](https://linux-hardware.org/?probe=e0997ac78c) | Oct 20, 2023 |
| ASUSTek       | ROG STRIX Z690-E GAMING ... | Desktop     | [8290e4c160](https://linux-hardware.org/?probe=8290e4c160) | Oct 20, 2023 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [f4f7d19069](https://linux-hardware.org/?probe=f4f7d19069) | Oct 20, 2023 |
| BANGHO        | M7x0K                       | Notebook    | [1f72eb6b91](https://linux-hardware.org/?probe=1f72eb6b91) | Oct 20, 2023 |
| Dell          | Vostro 14 5410              | Notebook    | [4cb4e5aab9](https://linux-hardware.org/?probe=4cb4e5aab9) | Oct 20, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [86fca6aaf4](https://linux-hardware.org/?probe=86fca6aaf4) | Oct 20, 2023 |
| Dell          | Latitude 7280               | Notebook    | [ec9e688b4e](https://linux-hardware.org/?probe=ec9e688b4e) | Oct 20, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9d49844572](https://linux-hardware.org/?probe=9d49844572) | Oct 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [aa76e46b18](https://linux-hardware.org/?probe=aa76e46b18) | Oct 20, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [984eba244a](https://linux-hardware.org/?probe=984eba244a) | Oct 20, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [32d375b029](https://linux-hardware.org/?probe=32d375b029) | Oct 20, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [6bb9b08c6e](https://linux-hardware.org/?probe=6bb9b08c6e) | Oct 20, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [17b8a78644](https://linux-hardware.org/?probe=17b8a78644) | Oct 20, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [fe5af0991d](https://linux-hardware.org/?probe=fe5af0991d) | Oct 20, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [6e5d214cb8](https://linux-hardware.org/?probe=6e5d214cb8) | Oct 20, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | Notebook    | [c96f9ccef3](https://linux-hardware.org/?probe=c96f9ccef3) | Oct 19, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [3b1da376dc](https://linux-hardware.org/?probe=3b1da376dc) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | Notebook    | [15b78585e0](https://linux-hardware.org/?probe=15b78585e0) | Oct 19, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [10fab445ad](https://linux-hardware.org/?probe=10fab445ad) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | Notebook    | [0d2e2856a9](https://linux-hardware.org/?probe=0d2e2856a9) | Oct 19, 2023 |
| ASUSTek       | PRIME X570-P                | Notebook    | [4506612f98](https://linux-hardware.org/?probe=4506612f98) | Oct 19, 2023 |
| Acer          | Aspire A315-57G             | Notebook    | [7e39a647e3](https://linux-hardware.org/?probe=7e39a647e3) | Oct 19, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [e2e11a852f](https://linux-hardware.org/?probe=e2e11a852f) | Oct 19, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8d38f6e16d](https://linux-hardware.org/?probe=8d38f6e16d) | Oct 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [fbb4ce606d](https://linux-hardware.org/?probe=fbb4ce606d) | Oct 19, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [1f244ed949](https://linux-hardware.org/?probe=1f244ed949) | Oct 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [e94e48868c](https://linux-hardware.org/?probe=e94e48868c) | Oct 19, 2023 |
| Gigabyte      | B75M-D3V                    | Desktop     | [b02f1b04e3](https://linux-hardware.org/?probe=b02f1b04e3) | Oct 19, 2023 |
| MACHINIST     | X99 G7 V1.0                 | Desktop     | [caca14cc52](https://linux-hardware.org/?probe=caca14cc52) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [abafeadb35](https://linux-hardware.org/?probe=abafeadb35) | Oct 19, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [ab3c18427d](https://linux-hardware.org/?probe=ab3c18427d) | Oct 19, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [a25bc084fc](https://linux-hardware.org/?probe=a25bc084fc) | Oct 19, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [77cf0c3af6](https://linux-hardware.org/?probe=77cf0c3af6) | Oct 18, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [b3cd8983eb](https://linux-hardware.org/?probe=b3cd8983eb) | Oct 18, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [4d4e3d82fd](https://linux-hardware.org/?probe=4d4e3d82fd) | Oct 18, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [064dc574bb](https://linux-hardware.org/?probe=064dc574bb) | Oct 18, 2023 |
| Timi          | Redmi Book Pro 14 2022      | Notebook    | [1984a8305d](https://linux-hardware.org/?probe=1984a8305d) | Oct 18, 2023 |
| Lenovo        | 30D9 SDK0J40705 WIN 3425... | Desktop     | [305b104f83](https://linux-hardware.org/?probe=305b104f83) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [0566ab2287](https://linux-hardware.org/?probe=0566ab2287) | Oct 18, 2023 |
| HP            | 2B52                        | Desktop     | [b14a00a196](https://linux-hardware.org/?probe=b14a00a196) | Oct 18, 2023 |
| HP            | EliteBook 860 16 inch G1... | Notebook    | [bde071302f](https://linux-hardware.org/?probe=bde071302f) | Oct 18, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [d7ddb794ec](https://linux-hardware.org/?probe=d7ddb794ec) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [48b90d30be](https://linux-hardware.org/?probe=48b90d30be) | Oct 18, 2023 |
| Dell          | Precision 7680              | Notebook    | [70f6453d4c](https://linux-hardware.org/?probe=70f6453d4c) | Oct 18, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [bb941b90f8](https://linux-hardware.org/?probe=bb941b90f8) | Oct 18, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [0c16d31374](https://linux-hardware.org/?probe=0c16d31374) | Oct 18, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [dbbedd9f06](https://linux-hardware.org/?probe=dbbedd9f06) | Oct 18, 2023 |
| Samsung       | 670Z5E                      | Notebook    | [65ee0747bc](https://linux-hardware.org/?probe=65ee0747bc) | Oct 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [04885ecaa3](https://linux-hardware.org/?probe=04885ecaa3) | Oct 18, 2023 |
| Lenovo        | ThinkPad T480s 20L8002AM... | Notebook    | [b8d09ca2f5](https://linux-hardware.org/?probe=b8d09ca2f5) | Oct 18, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d531813a7a](https://linux-hardware.org/?probe=d531813a7a) | Oct 18, 2023 |
| Dell          | Latitude 5440               | Notebook    | [2097e4ed5e](https://linux-hardware.org/?probe=2097e4ed5e) | Oct 18, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [2530967a90](https://linux-hardware.org/?probe=2530967a90) | Oct 17, 2023 |
| ASUSTek       | X556UJ                      | Notebook    | [010c7b3e14](https://linux-hardware.org/?probe=010c7b3e14) | Oct 17, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | Notebook    | [6193aa3ed1](https://linux-hardware.org/?probe=6193aa3ed1) | Oct 17, 2023 |
| ASUSTek       | X556UJ                      | Notebook    | [e9065ad0d2](https://linux-hardware.org/?probe=e9065ad0d2) | Oct 17, 2023 |
| HP            | 1589                        | Desktop     | [9fca3eb994](https://linux-hardware.org/?probe=9fca3eb994) | Oct 17, 2023 |
| ASUSTek       | Zenbook UX3402VA_UX3402V... | Notebook    | [4d69a046ff](https://linux-hardware.org/?probe=4d69a046ff) | Oct 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [660d60e1a8](https://linux-hardware.org/?probe=660d60e1a8) | Oct 17, 2023 |
| AZW           | SER V1                      | Desktop     | [fa5f054ba7](https://linux-hardware.org/?probe=fa5f054ba7) | Oct 17, 2023 |
| AZW           | SER V1                      | Desktop     | [e5c570b755](https://linux-hardware.org/?probe=e5c570b755) | Oct 17, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [8422037a50](https://linux-hardware.org/?probe=8422037a50) | Oct 17, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [8cb8d0943c](https://linux-hardware.org/?probe=8cb8d0943c) | Oct 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0b4065c185](https://linux-hardware.org/?probe=0b4065c185) | Oct 17, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [b552badf93](https://linux-hardware.org/?probe=b552badf93) | Oct 17, 2023 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [6f8e6d4251](https://linux-hardware.org/?probe=6f8e6d4251) | Oct 17, 2023 |
| MSI           | MS-1T31                     | Desktop     | [2ca507b92f](https://linux-hardware.org/?probe=2ca507b92f) | Oct 17, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [10c951fdee](https://linux-hardware.org/?probe=10c951fdee) | Oct 17, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [375e62bbf4](https://linux-hardware.org/?probe=375e62bbf4) | Oct 17, 2023 |
| Samsung       | 930QCG                      | Convertible | [26595d7bc0](https://linux-hardware.org/?probe=26595d7bc0) | Oct 17, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [85e4efe1d3](https://linux-hardware.org/?probe=85e4efe1d3) | Oct 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [6f1f662d3a](https://linux-hardware.org/?probe=6f1f662d3a) | Oct 17, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [8b92e44d64](https://linux-hardware.org/?probe=8b92e44d64) | Oct 17, 2023 |
| Lenovo        | ThinkPad T480 20L6S69X08    | Notebook    | [efc4ad7803](https://linux-hardware.org/?probe=efc4ad7803) | Oct 17, 2023 |
| Lenovo        | E41-50 82HW                 | Notebook    | [f31f632ea0](https://linux-hardware.org/?probe=f31f632ea0) | Oct 17, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [e28562a4d2](https://linux-hardware.org/?probe=e28562a4d2) | Oct 17, 2023 |
| HP            | 8AB6 SMVB                   | Desktop     | [e88f9153df](https://linux-hardware.org/?probe=e88f9153df) | Oct 17, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [81dac6f109](https://linux-hardware.org/?probe=81dac6f109) | Oct 17, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [3f87e6216a](https://linux-hardware.org/?probe=3f87e6216a) | Oct 16, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [d271c61b92](https://linux-hardware.org/?probe=d271c61b92) | Oct 16, 2023 |
| Dynabook E... | Satellite Pro ET10-G-106    | Tablet      | [e5a0e9fee3](https://linux-hardware.org/?probe=e5a0e9fee3) | Oct 16, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [55d07d6ee2](https://linux-hardware.org/?probe=55d07d6ee2) | Oct 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d14e5830b2](https://linux-hardware.org/?probe=d14e5830b2) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | Desktop     | [66c28b84cf](https://linux-hardware.org/?probe=66c28b84cf) | Oct 16, 2023 |
| ASUSTek       | P8H61-M                     | Desktop     | [982543f4bc](https://linux-hardware.org/?probe=982543f4bc) | Oct 16, 2023 |
| Dell          | Vostro 14 5410              | Notebook    | [219d504a89](https://linux-hardware.org/?probe=219d504a89) | Oct 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [73e2838408](https://linux-hardware.org/?probe=73e2838408) | Oct 16, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [5651db5e36](https://linux-hardware.org/?probe=5651db5e36) | Oct 16, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [70c2d315e0](https://linux-hardware.org/?probe=70c2d315e0) | Oct 16, 2023 |
| HP            | Notebook                    | Notebook    | [44730825fa](https://linux-hardware.org/?probe=44730825fa) | Oct 16, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [453546268b](https://linux-hardware.org/?probe=453546268b) | Oct 16, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [d294330c51](https://linux-hardware.org/?probe=d294330c51) | Oct 16, 2023 |
| GLM           | 14-Z8350-C                  | Notebook    | [2db6571799](https://linux-hardware.org/?probe=2db6571799) | Oct 15, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [19ec3283fc](https://linux-hardware.org/?probe=19ec3283fc) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8c4e60d5ca](https://linux-hardware.org/?probe=8c4e60d5ca) | Oct 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [bfbd0b0a49](https://linux-hardware.org/?probe=bfbd0b0a49) | Oct 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [37983381b0](https://linux-hardware.org/?probe=37983381b0) | Oct 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | Notebook    | [1a38144f94](https://linux-hardware.org/?probe=1a38144f94) | Oct 15, 2023 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [6082a5c0de](https://linux-hardware.org/?probe=6082a5c0de) | Oct 15, 2023 |
| Dell          | Latitude 5591               | Notebook    | [ef0287bbad](https://linux-hardware.org/?probe=ef0287bbad) | Oct 15, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [5330b349cb](https://linux-hardware.org/?probe=5330b349cb) | Oct 15, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [8bbdd141fe](https://linux-hardware.org/?probe=8bbdd141fe) | Oct 15, 2023 |
| HP            | 1589                        | Desktop     | [88e5bbcc5a](https://linux-hardware.org/?probe=88e5bbcc5a) | Oct 15, 2023 |
| MSI           | PRO B660M-P DDR4            | Desktop     | [364fd8849a](https://linux-hardware.org/?probe=364fd8849a) | Oct 15, 2023 |
| Gigabyte      | G7 GD                       | Notebook    | [667243780c](https://linux-hardware.org/?probe=667243780c) | Oct 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [85e073cb44](https://linux-hardware.org/?probe=85e073cb44) | Oct 15, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [27881eaaac](https://linux-hardware.org/?probe=27881eaaac) | Oct 15, 2023 |
| Dell          | 0TY915                      | Desktop     | [8ebe2fefc1](https://linux-hardware.org/?probe=8ebe2fefc1) | Oct 15, 2023 |
| Dell          | 0TY915                      | Desktop     | [736f520474](https://linux-hardware.org/?probe=736f520474) | Oct 15, 2023 |
| ASRock        | A320M-DGS                   | Desktop     | [a9599537b8](https://linux-hardware.org/?probe=a9599537b8) | Oct 15, 2023 |
| MSI           | MPG Z690 FORCE WIFI         | Desktop     | [7e4e4b6a5d](https://linux-hardware.org/?probe=7e4e4b6a5d) | Oct 15, 2023 |
| Acer          | Aspire VN7-592G             | Notebook    | [13b64fc9bd](https://linux-hardware.org/?probe=13b64fc9bd) | Oct 15, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5079c96f33](https://linux-hardware.org/?probe=5079c96f33) | Oct 15, 2023 |
| Intel         | DP55WB AAE64798-204         | Desktop     | [b5d7147862](https://linux-hardware.org/?probe=b5d7147862) | Oct 15, 2023 |
| Intel         | DP55WB AAE64798-204         | Desktop     | [642ecadbd2](https://linux-hardware.org/?probe=642ecadbd2) | Oct 15, 2023 |
| Toshiba       | Satellite CL10-C-102        | Notebook    | [cdaab4e230](https://linux-hardware.org/?probe=cdaab4e230) | Oct 15, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [ddc0082c22](https://linux-hardware.org/?probe=ddc0082c22) | Oct 14, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [4b4d5899fa](https://linux-hardware.org/?probe=4b4d5899fa) | Oct 14, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [d68359ee50](https://linux-hardware.org/?probe=d68359ee50) | Oct 14, 2023 |
| Dell          | 0Y2K8N A01                  | Desktop     | [32a0d75e98](https://linux-hardware.org/?probe=32a0d75e98) | Oct 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [11d91a0246](https://linux-hardware.org/?probe=11d91a0246) | Oct 14, 2023 |
| Dell          | XPS 9320                    | Notebook    | [21de4b869f](https://linux-hardware.org/?probe=21de4b869f) | Oct 14, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [70b85fc17d](https://linux-hardware.org/?probe=70b85fc17d) | Oct 14, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [0a86fd4e1d](https://linux-hardware.org/?probe=0a86fd4e1d) | Oct 14, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [1215db6b88](https://linux-hardware.org/?probe=1215db6b88) | Oct 13, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [039e898b5d](https://linux-hardware.org/?probe=039e898b5d) | Oct 13, 2023 |
| HPE           | ProLiant MicroServer Gen... | Server      | [62f56cc610](https://linux-hardware.org/?probe=62f56cc610) | Oct 13, 2023 |
| Google        | Morphius                    | Notebook    | [fd4be61654](https://linux-hardware.org/?probe=fd4be61654) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [3a6c620560](https://linux-hardware.org/?probe=3a6c620560) | Oct 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [2edd75be93](https://linux-hardware.org/?probe=2edd75be93) | Oct 13, 2023 |
| Dell          | Precision 7520              | Notebook    | [e9cb628c83](https://linux-hardware.org/?probe=e9cb628c83) | Oct 13, 2023 |
| Framework     | Laptop                      | Notebook    | [760f431061](https://linux-hardware.org/?probe=760f431061) | Oct 13, 2023 |
| Dell          | Precision 3580              | Notebook    | [f2a080ed43](https://linux-hardware.org/?probe=f2a080ed43) | Oct 13, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [1c1d7152a3](https://linux-hardware.org/?probe=1c1d7152a3) | Oct 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [01e717042e](https://linux-hardware.org/?probe=01e717042e) | Oct 13, 2023 |
| ASRock        | H87 Performance             | Desktop     | [5d1713de03](https://linux-hardware.org/?probe=5d1713de03) | Oct 13, 2023 |
| Lenovo        | ThinkPad P53 20QN20VZZC     | Notebook    | [4485ad6d0b](https://linux-hardware.org/?probe=4485ad6d0b) | Oct 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [a4dfa6f17f](https://linux-hardware.org/?probe=a4dfa6f17f) | Oct 13, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [63a132c897](https://linux-hardware.org/?probe=63a132c897) | Oct 13, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [a93d337261](https://linux-hardware.org/?probe=a93d337261) | Oct 13, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [d268453669](https://linux-hardware.org/?probe=d268453669) | Oct 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [17b0ef31ee](https://linux-hardware.org/?probe=17b0ef31ee) | Oct 13, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f6dd5e142c](https://linux-hardware.org/?probe=f6dd5e142c) | Oct 13, 2023 |
| HP            | G61                         | Notebook    | [34e955886e](https://linux-hardware.org/?probe=34e955886e) | Oct 13, 2023 |
| Dell          | Precision M4700             | Notebook    | [1c10565d3f](https://linux-hardware.org/?probe=1c10565d3f) | Oct 13, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [f24ebc31a5](https://linux-hardware.org/?probe=f24ebc31a5) | Oct 13, 2023 |
| Dell          | Precision 7520              | Notebook    | [de5b9c8fa1](https://linux-hardware.org/?probe=de5b9c8fa1) | Oct 13, 2023 |
| Dell          | 0WR7PY A03                  | Desktop     | [f59286c03f](https://linux-hardware.org/?probe=f59286c03f) | Oct 13, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [1f1524c080](https://linux-hardware.org/?probe=1f1524c080) | Oct 13, 2023 |
| Dell          | Latitude 7430               | Notebook    | [fb8c320433](https://linux-hardware.org/?probe=fb8c320433) | Oct 13, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [f51db4d9ed](https://linux-hardware.org/?probe=f51db4d9ed) | Oct 12, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [92726caa44](https://linux-hardware.org/?probe=92726caa44) | Oct 12, 2023 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [2598a9d29b](https://linux-hardware.org/?probe=2598a9d29b) | Oct 12, 2023 |
| Dell          | Latitude 3490               | Notebook    | [1c5aa8fca4](https://linux-hardware.org/?probe=1c5aa8fca4) | Oct 12, 2023 |
| Infinix       | ZERO BOOK 13                | Notebook    | [c20c04a240](https://linux-hardware.org/?probe=c20c04a240) | Oct 12, 2023 |
| MSI           | Modern 15 A11M              | Notebook    | [33272a00fb](https://linux-hardware.org/?probe=33272a00fb) | Oct 12, 2023 |
| Dell          | XPS 9320                    | Notebook    | [33d6205766](https://linux-hardware.org/?probe=33d6205766) | Oct 12, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [c6c1d1b3d1](https://linux-hardware.org/?probe=c6c1d1b3d1) | Oct 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [6396467c6d](https://linux-hardware.org/?probe=6396467c6d) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | Notebook    | [18b3c9fef8](https://linux-hardware.org/?probe=18b3c9fef8) | Oct 12, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [87e16d607b](https://linux-hardware.org/?probe=87e16d607b) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | Notebook    | [7c843b4c27](https://linux-hardware.org/?probe=7c843b4c27) | Oct 12, 2023 |
| MSI           | A68HM-E33                   | Desktop     | [71c8888ea4](https://linux-hardware.org/?probe=71c8888ea4) | Oct 12, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [cc8062e568](https://linux-hardware.org/?probe=cc8062e568) | Oct 12, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [c7b68dbfe1](https://linux-hardware.org/?probe=c7b68dbfe1) | Oct 12, 2023 |
| HP            | EliteBook 840 G6 HC         | Notebook    | [e1b3f5dbeb](https://linux-hardware.org/?probe=e1b3f5dbeb) | Oct 11, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | Notebook    | [3fe12fb88e](https://linux-hardware.org/?probe=3fe12fb88e) | Oct 11, 2023 |
| MSI           | PS42 Modern 8MO             | Notebook    | [be9a0659d4](https://linux-hardware.org/?probe=be9a0659d4) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [b71efdb817](https://linux-hardware.org/?probe=b71efdb817) | Oct 11, 2023 |
| Lenovo        | ThinkPad P53 20QN20VZZC     | Notebook    | [2659f02d19](https://linux-hardware.org/?probe=2659f02d19) | Oct 11, 2023 |
| HP            | 843B                        | Desktop     | [652027900b](https://linux-hardware.org/?probe=652027900b) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [2e77fb6729](https://linux-hardware.org/?probe=2e77fb6729) | Oct 11, 2023 |
| ASUSTek       | Z97-DELUXE                  | Desktop     | [fa0785421a](https://linux-hardware.org/?probe=fa0785421a) | Oct 11, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [3ceccfff97](https://linux-hardware.org/?probe=3ceccfff97) | Oct 11, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [d7d6c74d55](https://linux-hardware.org/?probe=d7d6c74d55) | Oct 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [ea3f6440b2](https://linux-hardware.org/?probe=ea3f6440b2) | Oct 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9b5d4b21a7](https://linux-hardware.org/?probe=9b5d4b21a7) | Oct 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [7aeb935c28](https://linux-hardware.org/?probe=7aeb935c28) | Oct 11, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [3d389cfbfa](https://linux-hardware.org/?probe=3d389cfbfa) | Oct 11, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [a8028e0998](https://linux-hardware.org/?probe=a8028e0998) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5566e985cf](https://linux-hardware.org/?probe=5566e985cf) | Oct 11, 2023 |
| Avell High... | B.ON                        | Notebook    | [3a419fbd20](https://linux-hardware.org/?probe=3a419fbd20) | Oct 11, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [e06a4e6c13](https://linux-hardware.org/?probe=e06a4e6c13) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [69f9b41478](https://linux-hardware.org/?probe=69f9b41478) | Oct 11, 2023 |
| Dell          | Precision 3571              | Notebook    | [ac3735cea4](https://linux-hardware.org/?probe=ac3735cea4) | Oct 11, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [22f4ada2e9](https://linux-hardware.org/?probe=22f4ada2e9) | Oct 10, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [50682769d9](https://linux-hardware.org/?probe=50682769d9) | Oct 10, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [9de05646a3](https://linux-hardware.org/?probe=9de05646a3) | Oct 10, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [162889c4a3](https://linux-hardware.org/?probe=162889c4a3) | Oct 10, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [87471871a7](https://linux-hardware.org/?probe=87471871a7) | Oct 10, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [b1ff58e369](https://linux-hardware.org/?probe=b1ff58e369) | Oct 10, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [8091bb0ceb](https://linux-hardware.org/?probe=8091bb0ceb) | Oct 10, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [19f6294d43](https://linux-hardware.org/?probe=19f6294d43) | Oct 10, 2023 |
| HP            | 89B5 A                      | Desktop     | [746fef0fc7](https://linux-hardware.org/?probe=746fef0fc7) | Oct 10, 2023 |
| ASRock        | B365M IB-R                  | Desktop     | [c1ac8c374a](https://linux-hardware.org/?probe=c1ac8c374a) | Oct 10, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [47ba0bddd0](https://linux-hardware.org/?probe=47ba0bddd0) | Oct 10, 2023 |
| AMI           | Intel                       | Convertible | [dd83e7aaf0](https://linux-hardware.org/?probe=dd83e7aaf0) | Oct 10, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [5954b70bb9](https://linux-hardware.org/?probe=5954b70bb9) | Oct 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [28a78b32e5](https://linux-hardware.org/?probe=28a78b32e5) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [7d759c245f](https://linux-hardware.org/?probe=7d759c245f) | Oct 10, 2023 |
| Dell          | Latitude 9430               | Convertible | [c7e409eb50](https://linux-hardware.org/?probe=c7e409eb50) | Oct 10, 2023 |
| Teclast       | F7S                         | Notebook    | [92c51af32a](https://linux-hardware.org/?probe=92c51af32a) | Oct 10, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [4a1888b421](https://linux-hardware.org/?probe=4a1888b421) | Oct 09, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [9e8bfb1d9e](https://linux-hardware.org/?probe=9e8bfb1d9e) | Oct 09, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [4ef40bc57a](https://linux-hardware.org/?probe=4ef40bc57a) | Oct 09, 2023 |
| Dell          | 0478VN A00                  | Desktop     | [8881cc216c](https://linux-hardware.org/?probe=8881cc216c) | Oct 09, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [830730801b](https://linux-hardware.org/?probe=830730801b) | Oct 09, 2023 |
| Lenovo        | ThinkPad T490 20N3S8HL00    | Notebook    | [e75ca9bf06](https://linux-hardware.org/?probe=e75ca9bf06) | Oct 09, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [5776334e3a](https://linux-hardware.org/?probe=5776334e3a) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [749e1a7e28](https://linux-hardware.org/?probe=749e1a7e28) | Oct 09, 2023 |
| Acer          | Predator PH315-51           | Notebook    | [265a8e5346](https://linux-hardware.org/?probe=265a8e5346) | Oct 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | Notebook    | [f269e7a6ee](https://linux-hardware.org/?probe=f269e7a6ee) | Oct 09, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [7aa0b01da6](https://linux-hardware.org/?probe=7aa0b01da6) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [b249985c20](https://linux-hardware.org/?probe=b249985c20) | Oct 09, 2023 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [90b88ff378](https://linux-hardware.org/?probe=90b88ff378) | Oct 09, 2023 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [882d0daf54](https://linux-hardware.org/?probe=882d0daf54) | Oct 09, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7070641150](https://linux-hardware.org/?probe=7070641150) | Oct 08, 2023 |
| Gigabyte      | F2A55M-DS2                  | Desktop     | [dd44b0dc9e](https://linux-hardware.org/?probe=dd44b0dc9e) | Oct 08, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [26708ac497](https://linux-hardware.org/?probe=26708ac497) | Oct 08, 2023 |
| Google        | Lindar                      | Notebook    | [75852e1ad7](https://linux-hardware.org/?probe=75852e1ad7) | Oct 08, 2023 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [fd3c1d1196](https://linux-hardware.org/?probe=fd3c1d1196) | Oct 08, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b04266e656](https://linux-hardware.org/?probe=b04266e656) | Oct 08, 2023 |
| AZW           | GTR V01                     | Mini pc     | [c2718a5c04](https://linux-hardware.org/?probe=c2718a5c04) | Oct 08, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [d400853f78](https://linux-hardware.org/?probe=d400853f78) | Oct 08, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [db5dd15d83](https://linux-hardware.org/?probe=db5dd15d83) | Oct 08, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [5f69a24978](https://linux-hardware.org/?probe=5f69a24978) | Oct 08, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [b0a2980430](https://linux-hardware.org/?probe=b0a2980430) | Oct 08, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [d43dc626c0](https://linux-hardware.org/?probe=d43dc626c0) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [907f3a4cf1](https://linux-hardware.org/?probe=907f3a4cf1) | Oct 08, 2023 |
| ASUSTek       | ROG STRIX B660-I GAMING ... | Desktop     | [998f01f73b](https://linux-hardware.org/?probe=998f01f73b) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [d003fa7343](https://linux-hardware.org/?probe=d003fa7343) | Oct 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [173accc37f](https://linux-hardware.org/?probe=173accc37f) | Oct 08, 2023 |
| HP            | 158A                        | Desktop     | [a1c0d51b9d](https://linux-hardware.org/?probe=a1c0d51b9d) | Oct 08, 2023 |
| Lenovo        | 32E9 SDK0T76461 WIN 3422... | Desktop     | [86f56798dc](https://linux-hardware.org/?probe=86f56798dc) | Oct 07, 2023 |
| Dell          | Inspiron 16 Plus 7630       | Notebook    | [51571d43df](https://linux-hardware.org/?probe=51571d43df) | Oct 07, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [bad231ff7d](https://linux-hardware.org/?probe=bad231ff7d) | Oct 07, 2023 |
| Samsung       | 960XFH                      | Notebook    | [0d8aca1f6e](https://linux-hardware.org/?probe=0d8aca1f6e) | Oct 07, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | Notebook    | [eac5ec9d19](https://linux-hardware.org/?probe=eac5ec9d19) | Oct 07, 2023 |
| Samsung       | 960XFH                      | Notebook    | [a2138fa3f8](https://linux-hardware.org/?probe=a2138fa3f8) | Oct 07, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [3c93fdc206](https://linux-hardware.org/?probe=3c93fdc206) | Oct 07, 2023 |
| Framework     | Laptop                      | Notebook    | [92ced4e3c6](https://linux-hardware.org/?probe=92ced4e3c6) | Oct 07, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | Notebook    | [2adab9deb5](https://linux-hardware.org/?probe=2adab9deb5) | Oct 07, 2023 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [0d980c4a61](https://linux-hardware.org/?probe=0d980c4a61) | Oct 07, 2023 |
| Dell          | Latitude 3490               | Notebook    | [723d6797ae](https://linux-hardware.org/?probe=723d6797ae) | Oct 07, 2023 |
| VANT          | MOOVE14_2023                | Notebook    | [d9379b5405](https://linux-hardware.org/?probe=d9379b5405) | Oct 06, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [4f9d192833](https://linux-hardware.org/?probe=4f9d192833) | Oct 06, 2023 |
| Acer          | Aspire X1900                | Desktop     | [38b7e52e6b](https://linux-hardware.org/?probe=38b7e52e6b) | Oct 06, 2023 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | Notebook    | [c5c7ad01ed](https://linux-hardware.org/?probe=c5c7ad01ed) | Oct 06, 2023 |
| Lenovo        | Mullins-LarneML             | Notebook    | [73b6f496a3](https://linux-hardware.org/?probe=73b6f496a3) | Oct 06, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [3d434adf2c](https://linux-hardware.org/?probe=3d434adf2c) | Oct 06, 2023 |
| HP            | Notebook                    | Notebook    | [be54658252](https://linux-hardware.org/?probe=be54658252) | Oct 06, 2023 |
| Gigabyte      | H81M-D2V                    | Desktop     | [a41f086304](https://linux-hardware.org/?probe=a41f086304) | Oct 06, 2023 |
| HP            | Notebook                    | Notebook    | [02dae8739a](https://linux-hardware.org/?probe=02dae8739a) | Oct 06, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [e8ae378997](https://linux-hardware.org/?probe=e8ae378997) | Oct 06, 2023 |
| HP            | EliteBook 735 G5            | Notebook    | [108728a0b6](https://linux-hardware.org/?probe=108728a0b6) | Oct 06, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [25612e7681](https://linux-hardware.org/?probe=25612e7681) | Oct 06, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [6bf5869cab](https://linux-hardware.org/?probe=6bf5869cab) | Oct 06, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [0b9d1772cd](https://linux-hardware.org/?probe=0b9d1772cd) | Oct 06, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [76c6fdfad6](https://linux-hardware.org/?probe=76c6fdfad6) | Oct 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [676106fbb7](https://linux-hardware.org/?probe=676106fbb7) | Oct 06, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [a2fb75cc3e](https://linux-hardware.org/?probe=a2fb75cc3e) | Oct 06, 2023 |
| Razer         | Blade 15 Base Model (Lat... | Notebook    | [8ae84cb1dc](https://linux-hardware.org/?probe=8ae84cb1dc) | Oct 05, 2023 |
| Dell          | Precision 5480              | Notebook    | [3a87c7a065](https://linux-hardware.org/?probe=3a87c7a065) | Oct 05, 2023 |
| Medion        | MS-7707                     | Desktop     | [42bc6357f7](https://linux-hardware.org/?probe=42bc6357f7) | Oct 05, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [010c54ccaf](https://linux-hardware.org/?probe=010c54ccaf) | Oct 05, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [bfe115219f](https://linux-hardware.org/?probe=bfe115219f) | Oct 05, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [2ed7997cfe](https://linux-hardware.org/?probe=2ed7997cfe) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [01f88bafa7](https://linux-hardware.org/?probe=01f88bafa7) | Oct 05, 2023 |
| Dell          | 0478VN A00                  | Desktop     | [511df57852](https://linux-hardware.org/?probe=511df57852) | Oct 05, 2023 |
| Google        | Magpie                      | Notebook    | [91fa583b13](https://linux-hardware.org/?probe=91fa583b13) | Oct 05, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [68e28eea76](https://linux-hardware.org/?probe=68e28eea76) | Oct 05, 2023 |
| Acer          | Spin SP314-21               | Convertible | [644e66499e](https://linux-hardware.org/?probe=644e66499e) | Oct 05, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [7b888eeb58](https://linux-hardware.org/?probe=7b888eeb58) | Oct 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9948b7ed73](https://linux-hardware.org/?probe=9948b7ed73) | Oct 05, 2023 |
| Dell          | 0N4YC8 A00                  | Desktop     | [fd4fb61bac](https://linux-hardware.org/?probe=fd4fb61bac) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [d8f9e7b32a](https://linux-hardware.org/?probe=d8f9e7b32a) | Oct 05, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [ae798c007e](https://linux-hardware.org/?probe=ae798c007e) | Oct 05, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [0aa9a5ddc3](https://linux-hardware.org/?probe=0aa9a5ddc3) | Oct 05, 2023 |
| ASRock        | AD2700-ITX                  | Desktop     | [3aea9e7d2f](https://linux-hardware.org/?probe=3aea9e7d2f) | Oct 05, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | Notebook    | [09c308ed3d](https://linux-hardware.org/?probe=09c308ed3d) | Oct 05, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6be4af5bb3](https://linux-hardware.org/?probe=6be4af5bb3) | Oct 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7700b3d342](https://linux-hardware.org/?probe=7700b3d342) | Oct 04, 2023 |
| Samsung       | 940Z5L                      | Notebook    | [120b5dac7e](https://linux-hardware.org/?probe=120b5dac7e) | Oct 04, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [135859015c](https://linux-hardware.org/?probe=135859015c) | Oct 04, 2023 |
| HP            | EliteBook 745 G6            | Notebook    | [77cfc34723](https://linux-hardware.org/?probe=77cfc34723) | Oct 04, 2023 |
| Lenovo        | ThinkPad L13 20R30009RT     | Notebook    | [8bc32c8cb6](https://linux-hardware.org/?probe=8bc32c8cb6) | Oct 04, 2023 |
| Dell          | Latitude 7340               | Notebook    | [713640e574](https://linux-hardware.org/?probe=713640e574) | Oct 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [b2f26d1c00](https://linux-hardware.org/?probe=b2f26d1c00) | Oct 04, 2023 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [ca79f8ce4c](https://linux-hardware.org/?probe=ca79f8ce4c) | Oct 04, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [08f5cef7f3](https://linux-hardware.org/?probe=08f5cef7f3) | Oct 04, 2023 |
| MSI           | PR600                       | Notebook    | [09fe9eb818](https://linux-hardware.org/?probe=09fe9eb818) | Oct 04, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [8e9fff1e35](https://linux-hardware.org/?probe=8e9fff1e35) | Oct 04, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7bb81b99a0](https://linux-hardware.org/?probe=7bb81b99a0) | Oct 04, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | Notebook    | [eb797a8074](https://linux-hardware.org/?probe=eb797a8074) | Oct 03, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [a98397577c](https://linux-hardware.org/?probe=a98397577c) | Oct 03, 2023 |
| ASUSTek       | K52JT                       | Notebook    | [30a087cc37](https://linux-hardware.org/?probe=30a087cc37) | Oct 03, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [4c6c3c41b3](https://linux-hardware.org/?probe=4c6c3c41b3) | Oct 03, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [400e01b1bf](https://linux-hardware.org/?probe=400e01b1bf) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [452537ff56](https://linux-hardware.org/?probe=452537ff56) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [0085d7a6ca](https://linux-hardware.org/?probe=0085d7a6ca) | Oct 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [5813f8d107](https://linux-hardware.org/?probe=5813f8d107) | Oct 03, 2023 |
| Samsung       | 940XGK                      | Notebook    | [63aededb0c](https://linux-hardware.org/?probe=63aededb0c) | Oct 03, 2023 |
| Samsung       | 940XGK                      | Notebook    | [805cef3023](https://linux-hardware.org/?probe=805cef3023) | Oct 03, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [a55f97899c](https://linux-hardware.org/?probe=a55f97899c) | Oct 03, 2023 |
| Lenovo        | ThinkPad T420 4236BR4       | Notebook    | [002422b029](https://linux-hardware.org/?probe=002422b029) | Oct 03, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | Notebook    | [cc7ba8c1ea](https://linux-hardware.org/?probe=cc7ba8c1ea) | Oct 03, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [6bc4edfef5](https://linux-hardware.org/?probe=6bc4edfef5) | Oct 02, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [b225569c1d](https://linux-hardware.org/?probe=b225569c1d) | Oct 02, 2023 |
| MSI           | VR630                       | Notebook    | [a9ce96c1ff](https://linux-hardware.org/?probe=a9ce96c1ff) | Oct 02, 2023 |
| HP            | Pavilion 17                 | Notebook    | [d78757ca20](https://linux-hardware.org/?probe=d78757ca20) | Oct 02, 2023 |
| HP            | 15                          | Notebook    | [254f7000e9](https://linux-hardware.org/?probe=254f7000e9) | Oct 02, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [59f53b1488](https://linux-hardware.org/?probe=59f53b1488) | Oct 02, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [a9b3098036](https://linux-hardware.org/?probe=a9b3098036) | Oct 02, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [2452e6e54f](https://linux-hardware.org/?probe=2452e6e54f) | Oct 02, 2023 |
| Chuwi         | UBook X                     | Convertible | [dd61ba0953](https://linux-hardware.org/?probe=dd61ba0953) | Oct 02, 2023 |
| Chuwi         | UBook X                     | Convertible | [641ddde28b](https://linux-hardware.org/?probe=641ddde28b) | Oct 02, 2023 |
| Apple         | MacBookPro16,3              | Notebook    | [9ca487f2cf](https://linux-hardware.org/?probe=9ca487f2cf) | Oct 02, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [4c5eef8118](https://linux-hardware.org/?probe=4c5eef8118) | Oct 02, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [020c2fbbf8](https://linux-hardware.org/?probe=020c2fbbf8) | Oct 02, 2023 |
| HP            | 15                          | Notebook    | [a5814d048c](https://linux-hardware.org/?probe=a5814d048c) | Oct 02, 2023 |
| MSI           | Vector GP68HX 12VH          | Notebook    | [e582127237](https://linux-hardware.org/?probe=e582127237) | Oct 02, 2023 |
| Unknown       | Unknown                     | Desktop     | [1f2e2a6b13](https://linux-hardware.org/?probe=1f2e2a6b13) | Oct 02, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [6f11536a5f](https://linux-hardware.org/?probe=6f11536a5f) | Oct 02, 2023 |
| Dell          | Inspiron 7573               | Convertible | [04d2b10c14](https://linux-hardware.org/?probe=04d2b10c14) | Oct 02, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [76c5466daa](https://linux-hardware.org/?probe=76c5466daa) | Oct 02, 2023 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | Notebook    | [ae0c9bf33a](https://linux-hardware.org/?probe=ae0c9bf33a) | Oct 02, 2023 |
| Intel         | H110                        | Desktop     | [eaf6f0f81c](https://linux-hardware.org/?probe=eaf6f0f81c) | Oct 02, 2023 |
| Acer          | Aspire X1900                | Desktop     | [5d958ae7d1](https://linux-hardware.org/?probe=5d958ae7d1) | Oct 02, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [17aca5008c](https://linux-hardware.org/?probe=17aca5008c) | Oct 02, 2023 |
| ASRock        | H370M-ITX/ac                | Desktop     | [cf9e8e26c2](https://linux-hardware.org/?probe=cf9e8e26c2) | Oct 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [5442de3655](https://linux-hardware.org/?probe=5442de3655) | Oct 02, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [b27cfa6ad6](https://linux-hardware.org/?probe=b27cfa6ad6) | Oct 02, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [45b94d86b5](https://linux-hardware.org/?probe=45b94d86b5) | Oct 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [4462bfcb6d](https://linux-hardware.org/?probe=4462bfcb6d) | Oct 02, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [9e09848439](https://linux-hardware.org/?probe=9e09848439) | Oct 02, 2023 |
| Google        | Magpie                      | Notebook    | [32a7bba307](https://linux-hardware.org/?probe=32a7bba307) | Oct 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [cd70d42de1](https://linux-hardware.org/?probe=cd70d42de1) | Oct 01, 2023 |
| ASRock        | B650E PG-ITX WiFi           | Desktop     | [10e1561364](https://linux-hardware.org/?probe=10e1561364) | Oct 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [21a71fe352](https://linux-hardware.org/?probe=21a71fe352) | Oct 01, 2023 |
| Lenovo        | G500 20236                  | Notebook    | [96ce4b8060](https://linux-hardware.org/?probe=96ce4b8060) | Oct 01, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [44bfa52d57](https://linux-hardware.org/?probe=44bfa52d57) | Oct 01, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [e1945fe82f](https://linux-hardware.org/?probe=e1945fe82f) | Oct 01, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [113ab4dbc3](https://linux-hardware.org/?probe=113ab4dbc3) | Oct 01, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [9dd550337d](https://linux-hardware.org/?probe=9dd550337d) | Oct 01, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [16354c8d94](https://linux-hardware.org/?probe=16354c8d94) | Oct 01, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [a8f95ea32d](https://linux-hardware.org/?probe=a8f95ea32d) | Oct 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [34b8e1853b](https://linux-hardware.org/?probe=34b8e1853b) | Oct 01, 2023 |
| Toshiba       | Satellite L735              | Notebook    | [c969a72669](https://linux-hardware.org/?probe=c969a72669) | Oct 01, 2023 |
| Acer          | Predator PH16-71            | Notebook    | [a07278dc43](https://linux-hardware.org/?probe=a07278dc43) | Oct 01, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [9d3a95cfd5](https://linux-hardware.org/?probe=9d3a95cfd5) | Oct 01, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1e825c5574](https://linux-hardware.org/?probe=1e825c5574) | Oct 01, 2023 |
| Dell          | Latitude 5520               | Notebook    | [024af71640](https://linux-hardware.org/?probe=024af71640) | Oct 01, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [124425b8b3](https://linux-hardware.org/?probe=124425b8b3) | Oct 01, 2023 |
| Google        | Nocturne                    | Tablet      | [966636d4d1](https://linux-hardware.org/?probe=966636d4d1) | Oct 01, 2023 |
| Google        | Nocturne                    | Tablet      | [5c4cae2a0b](https://linux-hardware.org/?probe=5c4cae2a0b) | Oct 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3e13770075](https://linux-hardware.org/?probe=3e13770075) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [913e98318d](https://linux-hardware.org/?probe=913e98318d) | Oct 01, 2023 |
| Gigabyte      | D525TUD                     | Desktop     | [f48a538837](https://linux-hardware.org/?probe=f48a538837) | Oct 01, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [9e04efc2d9](https://linux-hardware.org/?probe=9e04efc2d9) | Oct 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [30bf4415dc](https://linux-hardware.org/?probe=30bf4415dc) | Sep 30, 2023 |
| HUAWEI        | VLT-WX0                     | Notebook    | [a312a57d16](https://linux-hardware.org/?probe=a312a57d16) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [b3a006adc7](https://linux-hardware.org/?probe=b3a006adc7) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [f3d279f91b](https://linux-hardware.org/?probe=f3d279f91b) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | Notebook    | [1c1f35d1c8](https://linux-hardware.org/?probe=1c1f35d1c8) | Sep 30, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [bee067d5dd](https://linux-hardware.org/?probe=bee067d5dd) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B660M-PLUS D4    | Desktop     | [02af70281a](https://linux-hardware.org/?probe=02af70281a) | Sep 30, 2023 |
| Dell          | Latitude 7280               | Notebook    | [dbe9d3e4be](https://linux-hardware.org/?probe=dbe9d3e4be) | Sep 30, 2023 |
| Toshiba       | PORTEGE R30-D               | Notebook    | [04ef694f1d](https://linux-hardware.org/?probe=04ef694f1d) | Sep 30, 2023 |
| Dell          | 0V8WGR A02                  | Desktop     | [9c9ded765b](https://linux-hardware.org/?probe=9c9ded765b) | Sep 30, 2023 |
| Fanless Mi... | Rev GMLR1                   | Mini pc     | [751b4d268a](https://linux-hardware.org/?probe=751b4d268a) | Sep 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | Notebook    | [91873a529a](https://linux-hardware.org/?probe=91873a529a) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [9a749a1c41](https://linux-hardware.org/?probe=9a749a1c41) | Sep 30, 2023 |
| Gigabyte      | Z790 AORUS ELITE AX         | Desktop     | [452cd2622a](https://linux-hardware.org/?probe=452cd2622a) | Sep 30, 2023 |
| Lenovo        | ThinkPad T420 4180BV1       | Notebook    | [e81749053b](https://linux-hardware.org/?probe=e81749053b) | Sep 30, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [5a507ec4da](https://linux-hardware.org/?probe=5a507ec4da) | Sep 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [a36938e994](https://linux-hardware.org/?probe=a36938e994) | Sep 30, 2023 |
| Acer          | Aspire A514-53              | Notebook    | [6d8a5b1a13](https://linux-hardware.org/?probe=6d8a5b1a13) | Sep 30, 2023 |
| HP            | 8055                        | Desktop     | [3ddf31c78e](https://linux-hardware.org/?probe=3ddf31c78e) | Sep 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3bec9011bd](https://linux-hardware.org/?probe=3bec9011bd) | Sep 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [74bed86ee5](https://linux-hardware.org/?probe=74bed86ee5) | Sep 30, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [c69ab4bc0f](https://linux-hardware.org/?probe=c69ab4bc0f) | Sep 30, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [4a7b1ee936](https://linux-hardware.org/?probe=4a7b1ee936) | Sep 29, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [c1a605af33](https://linux-hardware.org/?probe=c1a605af33) | Sep 29, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [3c9f4d4aef](https://linux-hardware.org/?probe=3c9f4d4aef) | Sep 29, 2023 |
| Intel         | H61                         | Desktop     | [f6a417439c](https://linux-hardware.org/?probe=f6a417439c) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [ec1384a424](https://linux-hardware.org/?probe=ec1384a424) | Sep 29, 2023 |
| Razer         | Blade 15 Base Model (Lat... | Notebook    | [95dc405a73](https://linux-hardware.org/?probe=95dc405a73) | Sep 29, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8e039e23f3](https://linux-hardware.org/?probe=8e039e23f3) | Sep 29, 2023 |
| Intel         | H61                         | Desktop     | [e7dac2f9ed](https://linux-hardware.org/?probe=e7dac2f9ed) | Sep 29, 2023 |
| HP            | Laptop 17-cn1xxx            | Notebook    | [051a233121](https://linux-hardware.org/?probe=051a233121) | Sep 29, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [e51fd2a8e9](https://linux-hardware.org/?probe=e51fd2a8e9) | Sep 29, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [e1f22fdce4](https://linux-hardware.org/?probe=e1f22fdce4) | Sep 29, 2023 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [4b5a46a1e2](https://linux-hardware.org/?probe=4b5a46a1e2) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [d958b4e16a](https://linux-hardware.org/?probe=d958b4e16a) | Sep 29, 2023 |
| HP            | EliteBook 745 G5            | Notebook    | [b734ec49e2](https://linux-hardware.org/?probe=b734ec49e2) | Sep 29, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [1a7ed0ba7d](https://linux-hardware.org/?probe=1a7ed0ba7d) | Sep 29, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [c822d38335](https://linux-hardware.org/?probe=c822d38335) | Sep 29, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [222c45e72e](https://linux-hardware.org/?probe=222c45e72e) | Sep 29, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [e57cdefe7a](https://linux-hardware.org/?probe=e57cdefe7a) | Sep 29, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [427ea0aa4f](https://linux-hardware.org/?probe=427ea0aa4f) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [713d59f3d0](https://linux-hardware.org/?probe=713d59f3d0) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [c434f30a15](https://linux-hardware.org/?probe=c434f30a15) | Sep 29, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [fac4bb4863](https://linux-hardware.org/?probe=fac4bb4863) | Sep 29, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [60c04875f1](https://linux-hardware.org/?probe=60c04875f1) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| Dell          | 0YJPT1 A00                  | Desktop     | [a0a41d401e](https://linux-hardware.org/?probe=a0a41d401e) | Sep 28, 2023 |
| MSI           | H310M PRO-VD                | Desktop     | [67e14c1b2d](https://linux-hardware.org/?probe=67e14c1b2d) | Sep 28, 2023 |
| ASUSTek       | Z97-A-USB31                 | Desktop     | [b7e5fb069c](https://linux-hardware.org/?probe=b7e5fb069c) | Sep 28, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [1210322d55](https://linux-hardware.org/?probe=1210322d55) | Sep 28, 2023 |
| Dell          | 0XC7MM A01                  | Desktop     | [9fdfc5a13f](https://linux-hardware.org/?probe=9fdfc5a13f) | Sep 28, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [4cef8be854](https://linux-hardware.org/?probe=4cef8be854) | Sep 28, 2023 |
| HP            | EliteBook 840 G2            | Notebook    | [bec979fcd0](https://linux-hardware.org/?probe=bec979fcd0) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [356b5f053d](https://linux-hardware.org/?probe=356b5f053d) | Sep 28, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [5b87382fce](https://linux-hardware.org/?probe=5b87382fce) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [5dbe8e1541](https://linux-hardware.org/?probe=5dbe8e1541) | Sep 28, 2023 |
| ASUSTek       | ROG Flow X13 GV302XU_GV3... | Convertible | [abf12be6ff](https://linux-hardware.org/?probe=abf12be6ff) | Sep 28, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [2e3d19e919](https://linux-hardware.org/?probe=2e3d19e919) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | Notebook    | [737b3910bb](https://linux-hardware.org/?probe=737b3910bb) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | Notebook    | [b064b5b9ca](https://linux-hardware.org/?probe=b064b5b9ca) | Sep 28, 2023 |
| HP            | Notebook                    | Notebook    | [b13debd2fa](https://linux-hardware.org/?probe=b13debd2fa) | Sep 27, 2023 |
| Dell          | Latitude 7490               | Notebook    | [6f5e4547fa](https://linux-hardware.org/?probe=6f5e4547fa) | Sep 27, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | Desktop     | [23150c5bd3](https://linux-hardware.org/?probe=23150c5bd3) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [a95feaee78](https://linux-hardware.org/?probe=a95feaee78) | Sep 27, 2023 |
| Framework     | Laptop                      | Notebook    | [2a65b0dff2](https://linux-hardware.org/?probe=2a65b0dff2) | Sep 27, 2023 |
| Acer          | Predator G3-571             | Notebook    | [f301a514ad](https://linux-hardware.org/?probe=f301a514ad) | Sep 27, 2023 |
| Samsung       | 550XDA                      | Notebook    | [ab1fabfe9b](https://linux-hardware.org/?probe=ab1fabfe9b) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [546df5b57f](https://linux-hardware.org/?probe=546df5b57f) | Sep 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [503570ad7a](https://linux-hardware.org/?probe=503570ad7a) | Sep 27, 2023 |
| Chuwi         | CoreBook X                  | Notebook    | [0c31a47880](https://linux-hardware.org/?probe=0c31a47880) | Sep 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [41f0f8666c](https://linux-hardware.org/?probe=41f0f8666c) | Sep 27, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [4f0651ccc2](https://linux-hardware.org/?probe=4f0651ccc2) | Sep 27, 2023 |
| Notebook      | PCx0Dx                      | Notebook    | [53dd8cbd0d](https://linux-hardware.org/?probe=53dd8cbd0d) | Sep 27, 2023 |
| HP            | Stream x360 Convertible ... | Convertible | [d237ab1a11](https://linux-hardware.org/?probe=d237ab1a11) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [fed9f17a22](https://linux-hardware.org/?probe=fed9f17a22) | Sep 27, 2023 |
| Acer          | Predator G3-571             | Notebook    | [06b0300670](https://linux-hardware.org/?probe=06b0300670) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | Notebook    | [0dd1b47aa0](https://linux-hardware.org/?probe=0dd1b47aa0) | Sep 27, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [b6e832a4d8](https://linux-hardware.org/?probe=b6e832a4d8) | Sep 27, 2023 |
| Gigabyte      | B650M K                     | Desktop     | [73da1b7ade](https://linux-hardware.org/?probe=73da1b7ade) | Sep 27, 2023 |
| Dell          | Latitude E7450              | Notebook    | [afa1cce666](https://linux-hardware.org/?probe=afa1cce666) | Sep 27, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [b4de4fe266](https://linux-hardware.org/?probe=b4de4fe266) | Sep 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4f890f283a](https://linux-hardware.org/?probe=4f890f283a) | Sep 26, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [f61801ddb3](https://linux-hardware.org/?probe=f61801ddb3) | Sep 26, 2023 |
| Dell          | Latitude 7490               | Notebook    | [8bb2e054ec](https://linux-hardware.org/?probe=8bb2e054ec) | Sep 26, 2023 |
| Dell          | G15 5520                    | Notebook    | [64cfeba3ee](https://linux-hardware.org/?probe=64cfeba3ee) | Sep 26, 2023 |
| Dell          | Latitude 5420               | Notebook    | [3a22857022](https://linux-hardware.org/?probe=3a22857022) | Sep 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3bb1109d44](https://linux-hardware.org/?probe=3bb1109d44) | Sep 26, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [424e7e3d87](https://linux-hardware.org/?probe=424e7e3d87) | Sep 26, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [85c6c01e63](https://linux-hardware.org/?probe=85c6c01e63) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [dd48e0075b](https://linux-hardware.org/?probe=dd48e0075b) | Sep 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | Notebook    | [35e9d35a69](https://linux-hardware.org/?probe=35e9d35a69) | Sep 26, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [8da87a8c78](https://linux-hardware.org/?probe=8da87a8c78) | Sep 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | Notebook    | [dc762f9ae6](https://linux-hardware.org/?probe=dc762f9ae6) | Sep 26, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [4b0aff27e8](https://linux-hardware.org/?probe=4b0aff27e8) | Sep 26, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b49d28bbd4](https://linux-hardware.org/?probe=b49d28bbd4) | Sep 26, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ccb7f736f6](https://linux-hardware.org/?probe=ccb7f736f6) | Sep 26, 2023 |
| Lenovo        | ThinkPad T490s 20NX003NR... | Notebook    | [0a38f1e9a4](https://linux-hardware.org/?probe=0a38f1e9a4) | Sep 26, 2023 |
| Huanan        | X99-8M-F V1.2               | Desktop     | [4ddba514a1](https://linux-hardware.org/?probe=4ddba514a1) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [14766bbd15](https://linux-hardware.org/?probe=14766bbd15) | Sep 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7c547aa37a](https://linux-hardware.org/?probe=7c547aa37a) | Sep 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [b69e9b97ec](https://linux-hardware.org/?probe=b69e9b97ec) | Sep 26, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | Notebook    | [b22a584cea](https://linux-hardware.org/?probe=b22a584cea) | Sep 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [73d2dae51c](https://linux-hardware.org/?probe=73d2dae51c) | Sep 26, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [ccdfae441b](https://linux-hardware.org/?probe=ccdfae441b) | Sep 26, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [37fdb062e1](https://linux-hardware.org/?probe=37fdb062e1) | Sep 26, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [4375a551e1](https://linux-hardware.org/?probe=4375a551e1) | Sep 25, 2023 |
| ASUSTek       | P9D WS                      | Desktop     | [fd2133400d](https://linux-hardware.org/?probe=fd2133400d) | Sep 25, 2023 |
| MSI           | MPG Z490M GAMING EDGE WI... | Desktop     | [a6ef2b5028](https://linux-hardware.org/?probe=a6ef2b5028) | Sep 25, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [b7dae6ef48](https://linux-hardware.org/?probe=b7dae6ef48) | Sep 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c665cddf99](https://linux-hardware.org/?probe=c665cddf99) | Sep 25, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [1c1268d4e0](https://linux-hardware.org/?probe=1c1268d4e0) | Sep 25, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [4fbb517b71](https://linux-hardware.org/?probe=4fbb517b71) | Sep 25, 2023 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [2953047bfa](https://linux-hardware.org/?probe=2953047bfa) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [4e0f83e1fe](https://linux-hardware.org/?probe=4e0f83e1fe) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [60ff167d14](https://linux-hardware.org/?probe=60ff167d14) | Sep 25, 2023 |
| System76      | Pangolin                    | Notebook    | [3c56c50463](https://linux-hardware.org/?probe=3c56c50463) | Sep 25, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [6b5dcea023](https://linux-hardware.org/?probe=6b5dcea023) | Sep 25, 2023 |
| Dell          | Latitude E7270              | Notebook    | [98dd5eefb6](https://linux-hardware.org/?probe=98dd5eefb6) | Sep 25, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [f4d45948eb](https://linux-hardware.org/?probe=f4d45948eb) | Sep 25, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [91c3333a18](https://linux-hardware.org/?probe=91c3333a18) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [9a24a19f6e](https://linux-hardware.org/?probe=9a24a19f6e) | Sep 25, 2023 |
| HP            | ProBook 6570b               | Notebook    | [a67981aa91](https://linux-hardware.org/?probe=a67981aa91) | Sep 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [88385cbacc](https://linux-hardware.org/?probe=88385cbacc) | Sep 25, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [4233a2e5e3](https://linux-hardware.org/?probe=4233a2e5e3) | Sep 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c6dc860de5](https://linux-hardware.org/?probe=c6dc860de5) | Sep 25, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [705c3fdeff](https://linux-hardware.org/?probe=705c3fdeff) | Sep 25, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [1b8b856469](https://linux-hardware.org/?probe=1b8b856469) | Sep 25, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e741b61807](https://linux-hardware.org/?probe=e741b61807) | Sep 25, 2023 |
| MSI           | GL65 Leopard 10SER          | Notebook    | [e97a8fa2c7](https://linux-hardware.org/?probe=e97a8fa2c7) | Sep 25, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [88ce9be8a1](https://linux-hardware.org/?probe=88ce9be8a1) | Sep 24, 2023 |
| MSI           | GL65 Leopard 10SER          | Notebook    | [fac92f385c](https://linux-hardware.org/?probe=fac92f385c) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [0531db8cb8](https://linux-hardware.org/?probe=0531db8cb8) | Sep 24, 2023 |
| Acer          | TravelMate P259-MG          | Notebook    | [26ca7317b2](https://linux-hardware.org/?probe=26ca7317b2) | Sep 24, 2023 |
| Intel         | NUC7i7DNB J83500-204        | Mini pc     | [44784bdea7](https://linux-hardware.org/?probe=44784bdea7) | Sep 24, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [408377c3fd](https://linux-hardware.org/?probe=408377c3fd) | Sep 24, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [23d9e87224](https://linux-hardware.org/?probe=23d9e87224) | Sep 24, 2023 |
| Sony          | VAIO                        | All in one  | [75e484b949](https://linux-hardware.org/?probe=75e484b949) | Sep 24, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [cba55a15ec](https://linux-hardware.org/?probe=cba55a15ec) | Sep 24, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [53051aa7eb](https://linux-hardware.org/?probe=53051aa7eb) | Sep 24, 2023 |
| Dell          | Latitude 7400               | Notebook    | [f537b79d15](https://linux-hardware.org/?probe=f537b79d15) | Sep 24, 2023 |
| Lenovo        | V14-ARE 82DQ                | Notebook    | [31a635bff8](https://linux-hardware.org/?probe=31a635bff8) | Sep 24, 2023 |
| Google        | Eve                         | Convertible | [b3c890ec7a](https://linux-hardware.org/?probe=b3c890ec7a) | Sep 24, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [88653e2f06](https://linux-hardware.org/?probe=88653e2f06) | Sep 24, 2023 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [57d5f67adf](https://linux-hardware.org/?probe=57d5f67adf) | Sep 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [72940bf53e](https://linux-hardware.org/?probe=72940bf53e) | Sep 24, 2023 |
| HP            | 350 G2                      | Notebook    | [8440938e22](https://linux-hardware.org/?probe=8440938e22) | Sep 24, 2023 |
| ASUSTek       | PRIME B660M-A AC D4         | Desktop     | [7c0eb47c16](https://linux-hardware.org/?probe=7c0eb47c16) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [01b1c1acdb](https://linux-hardware.org/?probe=01b1c1acdb) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [fc14083064](https://linux-hardware.org/?probe=fc14083064) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [acba7de2ec](https://linux-hardware.org/?probe=acba7de2ec) | Sep 24, 2023 |
| Google        | Eve                         | Convertible | [eccabb6bc2](https://linux-hardware.org/?probe=eccabb6bc2) | Sep 24, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [5ed3f9381a](https://linux-hardware.org/?probe=5ed3f9381a) | Sep 23, 2023 |
| HP            | 255 15.6 inch G10           | Notebook    | [9f02426c5d](https://linux-hardware.org/?probe=9f02426c5d) | Sep 23, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [18b2a7026b](https://linux-hardware.org/?probe=18b2a7026b) | Sep 23, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [60f81eeb50](https://linux-hardware.org/?probe=60f81eeb50) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [fa3021d826](https://linux-hardware.org/?probe=fa3021d826) | Sep 23, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | Notebook    | [a34763914d](https://linux-hardware.org/?probe=a34763914d) | Sep 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [bd8ae0385b](https://linux-hardware.org/?probe=bd8ae0385b) | Sep 23, 2023 |
| ASRock        | N68C-S UCC                  | Desktop     | [844c35381f](https://linux-hardware.org/?probe=844c35381f) | Sep 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [f59df7021c](https://linux-hardware.org/?probe=f59df7021c) | Sep 23, 2023 |
| Dell          | Latitude 7280               | Notebook    | [1d032535e1](https://linux-hardware.org/?probe=1d032535e1) | Sep 23, 2023 |
| Gigabyte      | MZGLKBP-00                  | Desktop     | [678c17756d](https://linux-hardware.org/?probe=678c17756d) | Sep 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a6ff891fa1](https://linux-hardware.org/?probe=a6ff891fa1) | Sep 23, 2023 |
| Casper        | NIRVANA NB F500             | Notebook    | [1f66f22544](https://linux-hardware.org/?probe=1f66f22544) | Sep 23, 2023 |
| ASRock        | H61M/U3S3                   | Desktop     | [1d397abb90](https://linux-hardware.org/?probe=1d397abb90) | Sep 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [d464d79df3](https://linux-hardware.org/?probe=d464d79df3) | Sep 23, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [11ce4105e1](https://linux-hardware.org/?probe=11ce4105e1) | Sep 23, 2023 |
| Gigabyte      | B85-HD3                     | Desktop     | [5da83e8683](https://linux-hardware.org/?probe=5da83e8683) | Sep 23, 2023 |
| ASUSTek       | PRIME B360-PLUS             | Desktop     | [5629e161ab](https://linux-hardware.org/?probe=5629e161ab) | Sep 23, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [b96887841e](https://linux-hardware.org/?probe=b96887841e) | Sep 23, 2023 |
| MSI           | MS-7388                     | Desktop     | [f5ee235af0](https://linux-hardware.org/?probe=f5ee235af0) | Sep 23, 2023 |
| ASUSTek       | PRIME B660M-A AC D4         | Desktop     | [1a81f24fbb](https://linux-hardware.org/?probe=1a81f24fbb) | Sep 23, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [c6f224508a](https://linux-hardware.org/?probe=c6f224508a) | Sep 23, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [904a43b77e](https://linux-hardware.org/?probe=904a43b77e) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3b9bbcebb0](https://linux-hardware.org/?probe=3b9bbcebb0) | Sep 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | Notebook    | [6a6fde2ca9](https://linux-hardware.org/?probe=6a6fde2ca9) | Sep 23, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [eedf248084](https://linux-hardware.org/?probe=eedf248084) | Sep 23, 2023 |
| Acer          | Aspire ES1-520              | Notebook    | [22ce921c1e](https://linux-hardware.org/?probe=22ce921c1e) | Sep 22, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [535d4769c8](https://linux-hardware.org/?probe=535d4769c8) | Sep 22, 2023 |
| Acer          | Aspire A715-51G             | Notebook    | [674c086aa5](https://linux-hardware.org/?probe=674c086aa5) | Sep 22, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [169fe58269](https://linux-hardware.org/?probe=169fe58269) | Sep 22, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [40380b4dce](https://linux-hardware.org/?probe=40380b4dce) | Sep 22, 2023 |
| HP            | 834F                        | Desktop     | [b69b667f2c](https://linux-hardware.org/?probe=b69b667f2c) | Sep 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [8b1188ba33](https://linux-hardware.org/?probe=8b1188ba33) | Sep 22, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [909efbf81b](https://linux-hardware.org/?probe=909efbf81b) | Sep 22, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [fd5d5651ce](https://linux-hardware.org/?probe=fd5d5651ce) | Sep 22, 2023 |
| Dell          | Latitude 5420               | Notebook    | [d9c1c1537f](https://linux-hardware.org/?probe=d9c1c1537f) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7b093ed910](https://linux-hardware.org/?probe=7b093ed910) | Sep 22, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [21b73523cf](https://linux-hardware.org/?probe=21b73523cf) | Sep 22, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [2e715ca7b2](https://linux-hardware.org/?probe=2e715ca7b2) | Sep 22, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | Notebook    | [0e85445e8e](https://linux-hardware.org/?probe=0e85445e8e) | Sep 21, 2023 |
| Lenovo        | 1036 SDK0Q40104 WIN 3305... | Desktop     | [80c7b750ea](https://linux-hardware.org/?probe=80c7b750ea) | Sep 21, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | Notebook    | [3a372bed63](https://linux-hardware.org/?probe=3a372bed63) | Sep 21, 2023 |
| Lenovo        | Slim 7 14IRP8 83A4          | Notebook    | [b1ccf59045](https://linux-hardware.org/?probe=b1ccf59045) | Sep 21, 2023 |
| HP            | Pavilion dv6                | Notebook    | [270b0c0878](https://linux-hardware.org/?probe=270b0c0878) | Sep 21, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [3cd9b7841a](https://linux-hardware.org/?probe=3cd9b7841a) | Sep 21, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [609a91b51f](https://linux-hardware.org/?probe=609a91b51f) | Sep 21, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [b8821b0cf1](https://linux-hardware.org/?probe=b8821b0cf1) | Sep 21, 2023 |
| ANGXUN        | X99-DM3 V3.0                | Desktop     | [20e0572ade](https://linux-hardware.org/?probe=20e0572ade) | Sep 21, 2023 |
| Intel         | B75                         | Desktop     | [37b59e6605](https://linux-hardware.org/?probe=37b59e6605) | Sep 21, 2023 |
| HP            | 1495                        | Desktop     | [ad97ea883d](https://linux-hardware.org/?probe=ad97ea883d) | Sep 21, 2023 |
| HP            | 3047h                       | Desktop     | [cb19fdc589](https://linux-hardware.org/?probe=cb19fdc589) | Sep 21, 2023 |
| Apple         | Mac-27AD2F918AE68F61 Mac... | Desktop     | [ff9bab7040](https://linux-hardware.org/?probe=ff9bab7040) | Sep 21, 2023 |
| Gigabyte      | B360M D3H-CF                | Desktop     | [875f4f3f2a](https://linux-hardware.org/?probe=875f4f3f2a) | Sep 21, 2023 |
| Lenovo        | Mullins-LarneML             | Notebook    | [56157a1cff](https://linux-hardware.org/?probe=56157a1cff) | Sep 21, 2023 |
| Samsung       | R530/R730/R540              | Notebook    | [658ca13022](https://linux-hardware.org/?probe=658ca13022) | Sep 21, 2023 |
| ASUSTek       | V230IC                      | Desktop     | [aea46e7fc6](https://linux-hardware.org/?probe=aea46e7fc6) | Sep 21, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [522d50a437](https://linux-hardware.org/?probe=522d50a437) | Sep 21, 2023 |
| MSI           | Z270M MORTAR                | Desktop     | [ec0adfb60f](https://linux-hardware.org/?probe=ec0adfb60f) | Sep 21, 2023 |
| HP            | Pavilion g6                 | Notebook    | [11c60c8645](https://linux-hardware.org/?probe=11c60c8645) | Sep 21, 2023 |
| Dell          | Vostro 1310                 | Notebook    | [bc0c23c23c](https://linux-hardware.org/?probe=bc0c23c23c) | Sep 21, 2023 |
| Sony          | VAIO                        | All in one  | [5cd160ea53](https://linux-hardware.org/?probe=5cd160ea53) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2bb7ed1454](https://linux-hardware.org/?probe=2bb7ed1454) | Sep 21, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [5e05853c00](https://linux-hardware.org/?probe=5e05853c00) | Sep 20, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a2a2bc81e9](https://linux-hardware.org/?probe=a2a2bc81e9) | Sep 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [b4f1770e14](https://linux-hardware.org/?probe=b4f1770e14) | Sep 20, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [ddf1d6a712](https://linux-hardware.org/?probe=ddf1d6a712) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [6f81167a6c](https://linux-hardware.org/?probe=6f81167a6c) | Sep 20, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [7377101d6d](https://linux-hardware.org/?probe=7377101d6d) | Sep 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [79111191a0](https://linux-hardware.org/?probe=79111191a0) | Sep 20, 2023 |
| HP            | 3397                        | Desktop     | [f202c90e23](https://linux-hardware.org/?probe=f202c90e23) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | Notebook    | [e0ee68b1a7](https://linux-hardware.org/?probe=e0ee68b1a7) | Sep 20, 2023 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [f4d4f80645](https://linux-hardware.org/?probe=f4d4f80645) | Sep 20, 2023 |
| TUXEDO        | P65_P67RGRERA               | Notebook    | [97bae35595](https://linux-hardware.org/?probe=97bae35595) | Sep 20, 2023 |
| TUXEDO        | P65_P67RGRERA               | Notebook    | [0aefa5e3c6](https://linux-hardware.org/?probe=0aefa5e3c6) | Sep 20, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [3434dd8b54](https://linux-hardware.org/?probe=3434dd8b54) | Sep 20, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [624ebbd6c1](https://linux-hardware.org/?probe=624ebbd6c1) | Sep 20, 2023 |
| Samsung       | NC210/NC110                 | Notebook    | [1e194a2568](https://linux-hardware.org/?probe=1e194a2568) | Sep 20, 2023 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [238224ef08](https://linux-hardware.org/?probe=238224ef08) | Sep 20, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [27002ca3a9](https://linux-hardware.org/?probe=27002ca3a9) | Sep 20, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [94e8c710d5](https://linux-hardware.org/?probe=94e8c710d5) | Sep 20, 2023 |
| Gigabyte      | H110M-DS2-CF                | Desktop     | [b2519e8577](https://linux-hardware.org/?probe=b2519e8577) | Sep 20, 2023 |
| Dell          | 06HR05 A00                  | Desktop     | [a01d6b8630](https://linux-hardware.org/?probe=a01d6b8630) | Sep 20, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [bb52b1ddc5](https://linux-hardware.org/?probe=bb52b1ddc5) | Sep 20, 2023 |
| Samsung       | 960XFH                      | Notebook    | [c25c858bd4](https://linux-hardware.org/?probe=c25c858bd4) | Sep 19, 2023 |
| Maibenben     | MaiBook M Series            | Notebook    | [dc2eb7a7d7](https://linux-hardware.org/?probe=dc2eb7a7d7) | Sep 19, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [411b34f287](https://linux-hardware.org/?probe=411b34f287) | Sep 19, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [56d2a67030](https://linux-hardware.org/?probe=56d2a67030) | Sep 19, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [6edec4d045](https://linux-hardware.org/?probe=6edec4d045) | Sep 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [ca0ad87f0b](https://linux-hardware.org/?probe=ca0ad87f0b) | Sep 19, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [1bd6653d3e](https://linux-hardware.org/?probe=1bd6653d3e) | Sep 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [aeffbe0fe5](https://linux-hardware.org/?probe=aeffbe0fe5) | Sep 19, 2023 |
| Lenovo        | ThinkPad W540 20BG0014US    | Notebook    | [2d1c5101ea](https://linux-hardware.org/?probe=2d1c5101ea) | Sep 19, 2023 |
| HP            | ProBook 6475b               | Notebook    | [43c4870e11](https://linux-hardware.org/?probe=43c4870e11) | Sep 19, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [f9e5656f54](https://linux-hardware.org/?probe=f9e5656f54) | Sep 19, 2023 |
| Lenovo        | ThinkPad X240 20AMS1WN0A    | Notebook    | [858aed6617](https://linux-hardware.org/?probe=858aed6617) | Sep 19, 2023 |
| Dell          | Precision 3581              | Notebook    | [e1c8eb2810](https://linux-hardware.org/?probe=e1c8eb2810) | Sep 18, 2023 |
| AMI           | Intel                       | Convertible | [31bb2bf7aa](https://linux-hardware.org/?probe=31bb2bf7aa) | Sep 18, 2023 |
| HUAWEI        | DRC-WXX                     | Tablet      | [defee9ae2d](https://linux-hardware.org/?probe=defee9ae2d) | Sep 18, 2023 |
| Positivo      | POS-EIH610EX 11187943       | Desktop     | [10fbe8fd9b](https://linux-hardware.org/?probe=10fbe8fd9b) | Sep 18, 2023 |
| Lenovo        | ThinkCentre M58p 7220A72    | Desktop     | [39d6e8a728](https://linux-hardware.org/?probe=39d6e8a728) | Sep 18, 2023 |
| Dell          | Inspiron 5480               | Notebook    | [51aca22643](https://linux-hardware.org/?probe=51aca22643) | Sep 18, 2023 |
| Dell          | 0DY2X0 A01                  | Server      | [2384b2e12c](https://linux-hardware.org/?probe=2384b2e12c) | Sep 18, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [7e05f3299f](https://linux-hardware.org/?probe=7e05f3299f) | Sep 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [4d986c5384](https://linux-hardware.org/?probe=4d986c5384) | Sep 18, 2023 |
| Dell          | Latitude 5490               | Notebook    | [94eb709dfc](https://linux-hardware.org/?probe=94eb709dfc) | Sep 18, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [517795acfd](https://linux-hardware.org/?probe=517795acfd) | Sep 18, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [f797b137a3](https://linux-hardware.org/?probe=f797b137a3) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [f58cf1f72d](https://linux-hardware.org/?probe=f58cf1f72d) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | Notebook    | [68cef2242a](https://linux-hardware.org/?probe=68cef2242a) | Sep 18, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | Notebook    | [a4964c1b7a](https://linux-hardware.org/?probe=a4964c1b7a) | Sep 18, 2023 |
| HP            | EliteBook 745 G2            | Notebook    | [7e5ee5a990](https://linux-hardware.org/?probe=7e5ee5a990) | Sep 18, 2023 |
| Lenovo        | ThinkPad T480 20L6SCYF0P    | Notebook    | [c406bf7b56](https://linux-hardware.org/?probe=c406bf7b56) | Sep 18, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [5597daf348](https://linux-hardware.org/?probe=5597daf348) | Sep 18, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [b0de1885b9](https://linux-hardware.org/?probe=b0de1885b9) | Sep 18, 2023 |
| Lenovo        | G50-30 80G0                 | Notebook    | [fa9bd484cd](https://linux-hardware.org/?probe=fa9bd484cd) | Sep 17, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [bd7a7a6f22](https://linux-hardware.org/?probe=bd7a7a6f22) | Sep 17, 2023 |
| Lenovo        | G400 20235                  | Notebook    | [c8ecd1e0c9](https://linux-hardware.org/?probe=c8ecd1e0c9) | Sep 17, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [8566235f94](https://linux-hardware.org/?probe=8566235f94) | Sep 17, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | Notebook    | [290f6c66d1](https://linux-hardware.org/?probe=290f6c66d1) | Sep 17, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [ec87c19874](https://linux-hardware.org/?probe=ec87c19874) | Sep 17, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [2b66c2969e](https://linux-hardware.org/?probe=2b66c2969e) | Sep 17, 2023 |
| HP            | Pavilion g6                 | Notebook    | [dd1ade8736](https://linux-hardware.org/?probe=dd1ade8736) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | Notebook    | [93d01648a0](https://linux-hardware.org/?probe=93d01648a0) | Sep 17, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [a0d31a56e5](https://linux-hardware.org/?probe=a0d31a56e5) | Sep 17, 2023 |
| Dell          | Inspiron 1464               | Notebook    | [9830a0345b](https://linux-hardware.org/?probe=9830a0345b) | Sep 17, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [2e8cd612d8](https://linux-hardware.org/?probe=2e8cd612d8) | Sep 17, 2023 |
| Intel         | NUC5i3RYB H41000-503        | Mini pc     | [0ac315fe1c](https://linux-hardware.org/?probe=0ac315fe1c) | Sep 17, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [21b0d9faff](https://linux-hardware.org/?probe=21b0d9faff) | Sep 17, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [83a224edea](https://linux-hardware.org/?probe=83a224edea) | Sep 17, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [56f2d4d1eb](https://linux-hardware.org/?probe=56f2d4d1eb) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [3bb8e84b6b](https://linux-hardware.org/?probe=3bb8e84b6b) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [a53b964a47](https://linux-hardware.org/?probe=a53b964a47) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [648af5d937](https://linux-hardware.org/?probe=648af5d937) | Sep 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [77a72808f7](https://linux-hardware.org/?probe=77a72808f7) | Sep 17, 2023 |
| HP            | 250 G1                      | Notebook    | [0e052c1de2](https://linux-hardware.org/?probe=0e052c1de2) | Sep 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [bf532ab6ec](https://linux-hardware.org/?probe=bf532ab6ec) | Sep 16, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [a16a2ef714](https://linux-hardware.org/?probe=a16a2ef714) | Sep 16, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [06e45359c0](https://linux-hardware.org/?probe=06e45359c0) | Sep 16, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | Notebook    | [1b2e11b609](https://linux-hardware.org/?probe=1b2e11b609) | Sep 16, 2023 |
| Lenovo        | IdeaPad Z500 5931           | Notebook    | [0986123aac](https://linux-hardware.org/?probe=0986123aac) | Sep 16, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [394d932643](https://linux-hardware.org/?probe=394d932643) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [83c2fb6018](https://linux-hardware.org/?probe=83c2fb6018) | Sep 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F7... | Notebook    | [2c90700f4f](https://linux-hardware.org/?probe=2c90700f4f) | Sep 16, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [12456f4694](https://linux-hardware.org/?probe=12456f4694) | Sep 16, 2023 |
| Dell          | XPS 9320                    | Notebook    | [99fce2103f](https://linux-hardware.org/?probe=99fce2103f) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Notebook    | [a5c073ca7a](https://linux-hardware.org/?probe=a5c073ca7a) | Sep 16, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [2085bafc62](https://linux-hardware.org/?probe=2085bafc62) | Sep 16, 2023 |
| Acer          | TravelMate 5335             | Notebook    | [d440c12063](https://linux-hardware.org/?probe=d440c12063) | Sep 16, 2023 |
| Dell          | XPS L501X                   | Notebook    | [13d0075027](https://linux-hardware.org/?probe=13d0075027) | Sep 16, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [c78ab23cc7](https://linux-hardware.org/?probe=c78ab23cc7) | Sep 16, 2023 |
| Intel         | DQ45CB AAE30148-207         | Desktop     | [2c74d735db](https://linux-hardware.org/?probe=2c74d735db) | Sep 16, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [ec3d359099](https://linux-hardware.org/?probe=ec3d359099) | Sep 15, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | Desktop     | [3ebcf35cf2](https://linux-hardware.org/?probe=3ebcf35cf2) | Sep 15, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [fa207e873a](https://linux-hardware.org/?probe=fa207e873a) | Sep 15, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [054463900e](https://linux-hardware.org/?probe=054463900e) | Sep 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [b76ae8f9db](https://linux-hardware.org/?probe=b76ae8f9db) | Sep 15, 2023 |
| Lenovo        | G550 20023                  | Notebook    | [cdc9163353](https://linux-hardware.org/?probe=cdc9163353) | Sep 15, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [1c5a009557](https://linux-hardware.org/?probe=1c5a009557) | Sep 15, 2023 |
| ASUSTek       | Zenbook UP6502ZD_UP6502Z... | Convertible | [54221437db](https://linux-hardware.org/?probe=54221437db) | Sep 15, 2023 |
| Gigabyte      | GA-H81M-DS2-CF              | Desktop     | [8e5f637ac0](https://linux-hardware.org/?probe=8e5f637ac0) | Sep 15, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | Notebook    | [951dc3d5b0](https://linux-hardware.org/?probe=951dc3d5b0) | Sep 15, 2023 |
| HP            | EliteBook Folio 9470m       | Notebook    | [4a598eb0b3](https://linux-hardware.org/?probe=4a598eb0b3) | Sep 15, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [ae2f1fa903](https://linux-hardware.org/?probe=ae2f1fa903) | Sep 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [982f29b6cc](https://linux-hardware.org/?probe=982f29b6cc) | Sep 14, 2023 |
| HP            | 3397                        | Desktop     | [3cf175e939](https://linux-hardware.org/?probe=3cf175e939) | Sep 14, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [43020fecfb](https://linux-hardware.org/?probe=43020fecfb) | Sep 14, 2023 |
| MSI           | 2A9C                        | Desktop     | [378490ed0b](https://linux-hardware.org/?probe=378490ed0b) | Sep 14, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [a02233b901](https://linux-hardware.org/?probe=a02233b901) | Sep 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | Notebook    | [934dc9c297](https://linux-hardware.org/?probe=934dc9c297) | Sep 14, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [37e1d06001](https://linux-hardware.org/?probe=37e1d06001) | Sep 14, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [d907642716](https://linux-hardware.org/?probe=d907642716) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [426914b6e5](https://linux-hardware.org/?probe=426914b6e5) | Sep 14, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [756eff685a](https://linux-hardware.org/?probe=756eff685a) | Sep 14, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [305679af22](https://linux-hardware.org/?probe=305679af22) | Sep 14, 2023 |
| System76      | Darter Pro                  | Notebook    | [78c45153a3](https://linux-hardware.org/?probe=78c45153a3) | Sep 14, 2023 |
| HP            | 8459                        | Desktop     | [e7cbc6d34d](https://linux-hardware.org/?probe=e7cbc6d34d) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [820a13876a](https://linux-hardware.org/?probe=820a13876a) | Sep 14, 2023 |
| Dell          | Latitude 7390               | Notebook    | [4d8e0cb72b](https://linux-hardware.org/?probe=4d8e0cb72b) | Sep 14, 2023 |
| Dell          | 0YXT71 A02                  | Desktop     | [f462fe5985](https://linux-hardware.org/?probe=f462fe5985) | Sep 14, 2023 |
| Intel         | DH87MC AAG74242-401         | Desktop     | [6c37cc0b51](https://linux-hardware.org/?probe=6c37cc0b51) | Sep 14, 2023 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [58de71a548](https://linux-hardware.org/?probe=58de71a548) | Sep 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [d56bacdbb8](https://linux-hardware.org/?probe=d56bacdbb8) | Sep 14, 2023 |
| HP            | 843B                        | Desktop     | [08ce9ca0eb](https://linux-hardware.org/?probe=08ce9ca0eb) | Sep 14, 2023 |
| Toshiba       | PORTEGE M750                | Notebook    | [1c3442d87f](https://linux-hardware.org/?probe=1c3442d87f) | Sep 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [9ace0dfae8](https://linux-hardware.org/?probe=9ace0dfae8) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [d61823257e](https://linux-hardware.org/?probe=d61823257e) | Sep 13, 2023 |
| MSI           | MPG Z690 EDGE WIFI          | Desktop     | [2ad1c71fce](https://linux-hardware.org/?probe=2ad1c71fce) | Sep 13, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [acd8db76a1](https://linux-hardware.org/?probe=acd8db76a1) | Sep 13, 2023 |
| Dell          | Latitude 5421               | Notebook    | [6942c0131d](https://linux-hardware.org/?probe=6942c0131d) | Sep 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | Notebook    | [cb29d8cb77](https://linux-hardware.org/?probe=cb29d8cb77) | Sep 13, 2023 |
| Gigabyte      | Z170-D3H-CF                 | Desktop     | [418eee8ea7](https://linux-hardware.org/?probe=418eee8ea7) | Sep 13, 2023 |
| Dell          | Latitude 7390               | Notebook    | [2afdbd653c](https://linux-hardware.org/?probe=2afdbd653c) | Sep 13, 2023 |
| Fujitsu       | LIFEBOOK UH554              | Notebook    | [92f2e6135e](https://linux-hardware.org/?probe=92f2e6135e) | Sep 13, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [6c9eaad10e](https://linux-hardware.org/?probe=6c9eaad10e) | Sep 13, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [746f94b75d](https://linux-hardware.org/?probe=746f94b75d) | Sep 13, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [046d28d32d](https://linux-hardware.org/?probe=046d28d32d) | Sep 13, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [035fb7f099](https://linux-hardware.org/?probe=035fb7f099) | Sep 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0918609cf3](https://linux-hardware.org/?probe=0918609cf3) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [e8b1e251a3](https://linux-hardware.org/?probe=e8b1e251a3) | Sep 13, 2023 |
| MSI           | MAG B460M MORTAR            | Desktop     | [c0980eee03](https://linux-hardware.org/?probe=c0980eee03) | Sep 13, 2023 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [20ec05f55b](https://linux-hardware.org/?probe=20ec05f55b) | Sep 13, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [caa54219cf](https://linux-hardware.org/?probe=caa54219cf) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0317b3bcf6](https://linux-hardware.org/?probe=0317b3bcf6) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [37f8406bab](https://linux-hardware.org/?probe=37f8406bab) | Sep 13, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a7e93922ce](https://linux-hardware.org/?probe=a7e93922ce) | Sep 13, 2023 |
| Acer          | F690GVM                     | Desktop     | [a9a370c528](https://linux-hardware.org/?probe=a9a370c528) | Sep 13, 2023 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [a09109e90c](https://linux-hardware.org/?probe=a09109e90c) | Sep 13, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | Notebook    | [fcac50bfba](https://linux-hardware.org/?probe=fcac50bfba) | Sep 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [52a1dc1e19](https://linux-hardware.org/?probe=52a1dc1e19) | Sep 12, 2023 |
| Pegatron      | IPMSB-VH1/HDMI/ODM          | Desktop     | [fd4e189b56](https://linux-hardware.org/?probe=fd4e189b56) | Sep 12, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_38/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 6.2.9-300.fc38.x86_64        | 336       | 10.69%  |
| 6.2.15-300.fc38.x86_64       | 232       | 7.38%   |
| 6.3.8-200.fc38.x86_64        | 208       | 6.62%   |
| 6.4.15-200.fc38.x86_64       | 189       | 6.01%   |
| 6.5.5-200.fc38.x86_64        | 163       | 5.18%   |
| 6.2.14-300.fc38.x86_64       | 154       | 4.9%    |
| 6.2.11-300.fc38.x86_64       | 133       | 4.23%   |
| 6.3.12-200.fc38.x86_64       | 119       | 3.78%   |
| 6.5.8-200.fc38.x86_64        | 99        | 3.15%   |
| 6.5.6-200.fc38.x86_64        | 98        | 3.12%   |
| 6.4.11-200.fc38.x86_64       | 93        | 2.96%   |
| 6.5.7-200.fc38.x86_64        | 91        | 2.89%   |
| 6.4.6-200.fc38.x86_64        | 90        | 2.86%   |
| 6.3.11-200.fc38.x86_64       | 89        | 2.83%   |
| 6.4.12-200.fc38.x86_64       | 81        | 2.58%   |
| 6.4.14-200.fc38.x86_64       | 78        | 2.48%   |
| 6.4.7-200.fc38.x86_64        | 76        | 2.42%   |
| 6.3.5-200.fc38.x86_64        | 76        | 2.42%   |
| 6.4.13-200.fc38.x86_64       | 74        | 2.35%   |
| 6.2.13-300.fc38.x86_64       | 72        | 2.29%   |
| 6.4.10-200.fc38.x86_64       | 68        | 2.16%   |
| 6.3.6-200.fc38.x86_64        | 62        | 1.97%   |
| 6.2.12-300.fc38.x86_64       | 57        | 1.81%   |
| 6.4.4-200.fc38.x86_64        | 51        | 1.62%   |
| 6.3.4-201.fc38.x86_64        | 50        | 1.59%   |
| 6.3.7-200.fc38.x86_64        | 49        | 1.56%   |
| 6.4.9-200.fc38.x86_64        | 42        | 1.34%   |
| 6.5.9-200.fc38.x86_64        | 17        | 0.54%   |
| 6.2.8-300.fc38.x86_64        | 14        | 0.45%   |
| 6.4.8-200.fc38.x86_64        | 13        | 0.41%   |
| 6.2.6-300.fc38.x86_64        | 12        | 0.38%   |
| 6.2.10-300.fc38.x86_64       | 10        | 0.32%   |
| 6.2.2-301.fc38.x86_64        | 8         | 0.25%   |
| 6.2.7-300.fc38.x86_64        | 7         | 0.22%   |
| 6.2.15-703.inttf.fc38.x86_64 | 7         | 0.22%   |
| 6.3.3-200.fc38.x86_64        | 6         | 0.19%   |
| 6.2.0-63.fc38.x86_64         | 4         | 0.13%   |
| 6.3.10-200.fc38.x86_64       | 3         | 0.1%    |
| 6.2.2-300.fc38.x86_64        | 3         | 0.1%    |
| 6.5.6-1.surface.fc38.x86_64  | 2         | 0.06%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.9   | 338       | 10.75%  |
| 6.2.15  | 241       | 7.67%   |
| 6.3.8   | 210       | 6.68%   |
| 6.4.15  | 189       | 6.01%   |
| 6.5.5   | 166       | 5.28%   |
| 6.2.14  | 156       | 4.96%   |
| 6.2.11  | 135       | 4.3%    |
| 6.3.12  | 119       | 3.79%   |
| 6.5.8   | 101       | 3.21%   |
| 6.5.6   | 100       | 3.18%   |
| 6.4.11  | 93        | 2.96%   |
| 6.5.7   | 91        | 2.9%    |
| 6.4.6   | 91        | 2.9%    |
| 6.3.11  | 90        | 2.86%   |
| 6.4.12  | 82        | 2.61%   |
| 6.4.7   | 78        | 2.48%   |
| 6.4.14  | 78        | 2.48%   |
| 6.3.5   | 76        | 2.42%   |
| 6.4.13  | 75        | 2.39%   |
| 6.2.13  | 72        | 2.29%   |
| 6.4.10  | 70        | 2.23%   |
| 6.3.6   | 63        | 2%      |
| 6.2.12  | 57        | 1.81%   |
| 6.4.4   | 53        | 1.69%   |
| 6.3.4   | 50        | 1.59%   |
| 6.3.7   | 49        | 1.56%   |
| 6.4.9   | 42        | 1.34%   |
| 6.5.9   | 17        | 0.54%   |
| 6.2.8   | 14        | 0.45%   |
| 6.4.8   | 13        | 0.41%   |
| 6.2.6   | 12        | 0.38%   |
| 6.2.10  | 12        | 0.38%   |
| 6.2.0   | 12        | 0.38%   |
| 6.2.2   | 11        | 0.35%   |
| 6.3.3   | 8         | 0.25%   |
| 6.2.7   | 7         | 0.22%   |
| 6.5.0   | 6         | 0.19%   |
| 6.4.0   | 6         | 0.19%   |
| 6.3.1   | 5         | 0.16%   |
| 6.1.0   | 5         | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 1034      | 33.96%  |
| 6.4     | 840       | 27.59%  |
| 6.3     | 658       | 21.61%  |
| 6.5     | 480       | 15.76%  |
| 6.1     | 11        | 0.36%   |
| 6.0     | 11        | 0.36%   |
| 6.6     | 4         | 0.13%   |
| 5.19    | 2         | 0.07%   |
| 5.15    | 2         | 0.07%   |
| 5.4     | 1         | 0.03%   |
| 5.11    | 1         | 0.03%   |
| 5.10    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2817      | 99.68%  |
| aarch64 | 8         | 0.28%   |
| ppc64le | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 2214      | 77.66%  |
| KDE5          | 408       | 14.31%  |
| Unknown       | 52        | 1.82%   |
| XFCE          | 38        | 1.33%   |
| X-Cinnamon    | 33        | 1.16%   |
| Cinnamon      | 28        | 0.98%   |
| GNOME Classic | 20        | 0.7%    |
| MATE          | 12        | 0.42%   |
| sway          | 10        | 0.35%   |
| Budgie        | 8         | 0.28%   |
| Hyprland      | 7         | 0.25%   |
| LXDE          | 5         | 0.18%   |
| i3            | 5         | 0.18%   |
| LXQt          | 4         | 0.14%   |
| Unity         | 1         | 0.04%   |
| Pantheon      | 1         | 0.04%   |
| openbox       | 1         | 0.04%   |
| KDE4          | 1         | 0.04%   |
| KDE           | 1         | 0.04%   |
| e16-session   | 1         | 0.04%   |
| Deepin        | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 2269      | 79.34%  |
| X11     | 505       | 17.66%  |
| Tty     | 58        | 2.03%   |
| Unknown | 27        | 0.94%   |
| Xcb     | 1         | 0.03%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1837      | 64.5%   |
| GDM     | 695       | 24.4%   |
| SDDM    | 193       | 6.78%   |
| LightDM | 118       | 4.14%   |
| LXDM    | 4         | 0.14%   |
| SLiM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1444      | 50.79%  |
| en_GB   | 204       | 7.18%   |
| de_DE   | 144       | 5.07%   |
| ru_RU   | 141       | 4.96%   |
| pt_BR   | 130       | 4.57%   |
| it_IT   | 74        | 2.6%    |
| en_AU   | 73        | 2.57%   |
| fr_FR   | 72        | 2.53%   |
| en_CA   | 71        | 2.5%    |
| es_ES   | 58        | 2.04%   |
| es_MX   | 39        | 1.37%   |
| pl_PL   | 38        | 1.34%   |
| en_IN   | 27        | 0.95%   |
| es_CL   | 21        | 0.74%   |
| es_CO   | 20        | 0.7%    |
| es_AR   | 17        | 0.6%    |
| pt_PT   | 15        | 0.53%   |
| en_DK   | 15        | 0.53%   |
| cs_CZ   | 15        | 0.53%   |
| de_AT   | 13        | 0.46%   |
| zh_CN   | 12        | 0.42%   |
| tr_TR   | 12        | 0.42%   |
| Unknown | 11        | 0.39%   |
| nl_NL   | 10        | 0.35%   |
| hu_HU   | 10        | 0.35%   |
| fr_CA   | 8         | 0.28%   |
| es_PE   | 8         | 0.28%   |
| en_NZ   | 7         | 0.25%   |
| en_IE   | 7         | 0.25%   |
| ru_UA   | 6         | 0.21%   |
| nl_BE   | 6         | 0.21%   |
| en_PH   | 6         | 0.21%   |
| de_CH   | 6         | 0.21%   |
| zh_TW   | 5         | 0.18%   |
| sk_SK   | 5         | 0.18%   |
| id_ID   | 5         | 0.18%   |
| en_ZA   | 5         | 0.18%   |
| da_DK   | 5         | 0.18%   |
| sv_SE   | 4         | 0.14%   |
| ja_JP   | 4         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 2318      | 81.53%  |
| BIOS | 525       | 18.47%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 2370      | 83.66%  |
| Ext4    | 389       | 13.73%  |
| Xfs     | 65        | 2.29%   |
| Overlay | 4         | 0.14%   |
| Zfs     | 2         | 0.07%   |
| F2fs    | 1         | 0.04%   |
| Ext3    | 1         | 0.04%   |
| Unknown | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1789      | 62.88%  |
| GPT     | 1001      | 35.18%  |
| MBR     | 55        | 1.93%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2607      | 91.73%  |
| Yes       | 235       | 8.27%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2404      | 84.86%  |
| Yes       | 429       | 15.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 548       | 19.39%  |
| ASUSTek Computer                     | 441       | 15.61%  |
| Hewlett-Packard                      | 361       | 12.77%  |
| Dell                                 | 352       | 12.46%  |
| MSI                                  | 201       | 7.11%   |
| Gigabyte Technology                  | 168       | 5.94%   |
| Acer                                 | 115       | 4.07%   |
| Apple                                | 106       | 3.75%   |
| ASRock                               | 83        | 2.94%   |
| HUAWEI                               | 48        | 1.7%    |
| Samsung Electronics                  | 36        | 1.27%   |
| Intel                                | 29        | 1.03%   |
| Microsoft                            | 23        | 0.81%   |
| Unknown                              | 23        | 0.81%   |
| Timi                                 | 19        | 0.67%   |
| Google                               | 18        | 0.64%   |
| Toshiba                              | 17        | 0.6%    |
| Fujitsu                              | 13        | 0.46%   |
| AZW                                  | 13        | 0.46%   |
| Sony                                 | 12        | 0.42%   |
| Pegatron                             | 10        | 0.35%   |
| Framework                            | 10        | 0.35%   |
| Notebook                             | 8         | 0.28%   |
| System76                             | 6         | 0.21%   |
| Positivo                             | 6         | 0.21%   |
| Chuwi                                | 6         | 0.21%   |
| TUXEDO                               | 5         | 0.18%   |
| Shenzhen Meigao Electronic Equipment | 5         | 0.18%   |
| Huanan                               | 5         | 0.18%   |
| Schenker                             | 4         | 0.14%   |
| Razer                                | 4         | 0.14%   |
| Positivo Bahia - VAIO                | 4         | 0.14%   |
| Packard Bell                         | 4         | 0.14%   |
| Medion                               | 4         | 0.14%   |
| Itautec                              | 4         | 0.14%   |
| AMI                                  | 4         | 0.14%   |
| Alienware                            | 4         | 0.14%   |
| raspberrypi,4-model-b                | 3         | 0.11%   |
| PC Specialist                        | 3         | 0.11%   |
| Maibenben                            | 3         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 27        | 0.96%   |
| ASUS All Series                      | 16        | 0.57%   |
| Apple MacBookPro9,2                  | 12        | 0.42%   |
| HP Notebook                          | 10        | 0.35%   |
| Apple MacBookPro8,1                  | 10        | 0.35%   |
| Dell OptiPlex 7010                   | 9         | 0.32%   |
| Framework Laptop                     | 8         | 0.28%   |
| MSI MS-7C37                          | 7         | 0.25%   |
| Dell XPS 13 9310                     | 7         | 0.25%   |
| MSI MS-7C95                          | 6         | 0.21%   |
| MSI MS-7C56                          | 6         | 0.21%   |
| MSI MS-7B89                          | 6         | 0.21%   |
| Lenovo IdeaPad 3 15ITL6 82H8         | 6         | 0.21%   |
| Gigabyte X570 I AORUS PRO WIFI       | 6         | 0.21%   |
| AZW SER                              | 6         | 0.21%   |
| Samsung 550XDA                       | 5         | 0.18%   |
| MSI MS-7C91                          | 5         | 0.18%   |
| MSI MS-7C02                          | 5         | 0.18%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU    | 5         | 0.18%   |
| HP ENVY x360 2-in-1 Laptop 15-ey0xxx | 5         | 0.18%   |
| HP EliteBook 840 G6                  | 5         | 0.18%   |
| Gigabyte B550 GAMING X V2            | 5         | 0.18%   |
| Dell OptiPlex 9020                   | 5         | 0.18%   |
| Dell Latitude 7490                   | 5         | 0.18%   |
| ASUS TUF Gaming X570-PLUS            | 5         | 0.18%   |
| ASUS ROG STRIX X670E-I GAMING WIFI   | 5         | 0.18%   |
| ASRock B450M Pro4                    | 5         | 0.18%   |
| Apple MacBookPro12,1                 | 5         | 0.18%   |
| Apple MacBookPro11,1                 | 5         | 0.18%   |
| Apple MacBookAir7,2                  | 5         | 0.18%   |
| Timi Redmi Book Pro 14 2022          | 4         | 0.14%   |
| MSI MS-7C52                          | 4         | 0.14%   |
| MSI MS-7B79                          | 4         | 0.14%   |
| MSI MS-7A38                          | 4         | 0.14%   |
| Microsoft Surface Pro 7              | 4         | 0.14%   |
| Lenovo Yoga 6 13ALC6 82ND            | 4         | 0.14%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ     | 4         | 0.14%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2    | 4         | 0.14%   |
| HUAWEI HVY-WXX9                      | 4         | 0.14%   |
| HUAWEI CREM-WXX9                     | 4         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 246       | 8.7%    |
| Lenovo IdeaPad     | 105       | 3.72%   |
| Dell Latitude      | 102       | 3.61%   |
| ASUS ROG           | 94        | 3.33%   |
| Dell Inspiron      | 82        | 2.9%    |
| ASUS VivoBook      | 70        | 2.48%   |
| Acer Aspire        | 66        | 2.34%   |
| HP Pavilion        | 65        | 2.3%    |
| Dell XPS           | 56        | 1.98%   |
| ASUS PRIME         | 56        | 1.98%   |
| HP EliteBook       | 51        | 1.8%    |
| ASUS TUF           | 46        | 1.63%   |
| Dell OptiPlex      | 43        | 1.52%   |
| Lenovo Yoga        | 42        | 1.49%   |
| HP ProBook         | 36        | 1.27%   |
| HP Laptop          | 36        | 1.27%   |
| Lenovo Legion      | 34        | 1.2%    |
| Dell Precision     | 34        | 1.2%    |
| HP ENVY            | 33        | 1.17%   |
| ASUS ASUS          | 27        | 0.96%   |
| Unknown            | 27        | 0.96%   |
| Microsoft Surface  | 23        | 0.81%   |
| Lenovo ThinkBook   | 22        | 0.78%   |
| Lenovo ThinkCentre | 21        | 0.74%   |
| ASUS Zenbook       | 21        | 0.74%   |
| HP Compaq          | 20        | 0.71%   |
| Acer Nitro         | 19        | 0.67%   |
| Lenovo IdeaPadFlex | 18        | 0.64%   |
| ASUS All           | 16        | 0.57%   |
| Dell Vostro        | 14        | 0.5%    |
| Toshiba Satellite  | 13        | 0.46%   |
| HP OMEN            | 13        | 0.46%   |
| Apple MacBookPro9  | 13        | 0.46%   |
| Gigabyte B550M     | 12        | 0.42%   |
| Apple MacBookPro8  | 12        | 0.42%   |
| HP EliteDesk       | 11        | 0.39%   |
| Gigabyte X570      | 11        | 0.39%   |
| HP Notebook        | 10        | 0.35%   |
| Gigabyte B550      | 10        | 0.35%   |
| Framework Laptop   | 10        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 389       | 13.77%  |
| 2022    | 371       | 13.13%  |
| 2020    | 366       | 12.95%  |
| 2018    | 272       | 9.62%   |
| 2019    | 254       | 8.99%   |
| 2017    | 170       | 6.02%   |
| 2023    | 158       | 5.59%   |
| 2012    | 139       | 4.92%   |
| 2015    | 125       | 4.42%   |
| 2013    | 122       | 4.32%   |
| 2014    | 115       | 4.07%   |
| 2016    | 100       | 3.54%   |
| 2011    | 89        | 3.15%   |
| 2010    | 63        | 2.23%   |
| 2009    | 39        | 1.38%   |
| 2008    | 33        | 1.17%   |
| 2007    | 13        | 0.46%   |
| 2006    | 4         | 0.14%   |
| Unknown | 3         | 0.11%   |
| 2005    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1677      | 59.34%  |
| Desktop        | 871       | 30.82%  |
| Convertible    | 131       | 4.64%   |
| Tablet         | 50        | 1.77%   |
| Mini pc        | 48        | 1.7%    |
| All in one     | 29        | 1.03%   |
| Server         | 14        | 0.5%    |
| System on chip | 6         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2201      | 77.34%  |
| Enabled  | 645       | 22.66%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2802      | 99.15%  |
| Yes  | 24        | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 694       | 24.39%  |
| 4.01-8.0        | 637       | 22.38%  |
| 8.01-16.0       | 535       | 18.8%   |
| 32.01-64.0      | 440       | 15.46%  |
| 3.01-4.0        | 236       | 8.29%   |
| 64.01-256.0     | 151       | 5.31%   |
| 24.01-32.0      | 103       | 3.62%   |
| 1.01-2.0        | 37        | 1.3%    |
| 2.01-3.0        | 12        | 0.42%   |
| More than 256.0 | 1         | 0.04%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 931       | 30.96%  |
| 2.01-3.0    | 778       | 25.87%  |
| 3.01-4.0    | 709       | 23.58%  |
| 1.01-2.0    | 297       | 9.88%   |
| 8.01-16.0   | 235       | 7.82%   |
| 0.51-1.0    | 26        | 0.86%   |
| 16.01-24.0  | 21        | 0.7%    |
| 32.01-64.0  | 5         | 0.17%   |
| 24.01-32.0  | 3         | 0.1%    |
| 64.01-256.0 | 1         | 0.03%   |
| 0.01-0.5    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1755      | 61.24%  |
| 2      | 710       | 24.77%  |
| 3      | 212       | 7.4%    |
| 4      | 98        | 3.42%   |
| 5      | 44        | 1.54%   |
| 6      | 24        | 0.84%   |
| 0      | 7         | 0.24%   |
| 7      | 6         | 0.21%   |
| 8      | 4         | 0.14%   |
| 10     | 3         | 0.1%    |
| 11     | 2         | 0.07%   |
| 9      | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2275      | 80.3%   |
| Yes       | 558       | 19.7%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2187      | 77.17%  |
| No        | 647       | 22.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2396      | 84.54%  |
| No        | 438       | 15.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2117      | 74.52%  |
| No        | 724       | 25.48%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 520       | 18.34%  |
| Germany     | 216       | 7.62%   |
| Brazil      | 197       | 6.95%   |
| Russia      | 156       | 5.5%    |
| Italy       | 127       | 4.48%   |
| Canada      | 110       | 3.88%   |
| UK          | 106       | 3.74%   |
| France      | 90        | 3.17%   |
| India       | 85        | 3%      |
| Spain       | 82        | 2.89%   |
| Australia   | 80        | 2.82%   |
| Poland      | 72        | 2.54%   |
| Mexico      | 70        | 2.47%   |
| Netherlands | 67        | 2.36%   |
| Turkey      | 42        | 1.48%   |
| Czechia     | 36        | 1.27%   |
| Colombia    | 34        | 1.2%    |
| Sweden      | 29        | 1.02%   |
| Austria     | 29        | 1.02%   |
| Switzerland | 28        | 0.99%   |
| Chile       | 28        | 0.99%   |
| Belgium     | 27        | 0.95%   |
| Argentina   | 27        | 0.95%   |
| Portugal    | 25        | 0.88%   |
| Indonesia   | 24        | 0.85%   |
| Hungary     | 24        | 0.85%   |
| Belarus     | 21        | 0.74%   |
| Norway      | 20        | 0.71%   |
| Denmark     | 20        | 0.71%   |
| Bulgaria    | 19        | 0.67%   |
| Finland     | 17        | 0.6%    |
| Thailand    | 16        | 0.56%   |
| Romania     | 16        | 0.56%   |
| China       | 16        | 0.56%   |
| Philippines | 15        | 0.53%   |
| Israel      | 13        | 0.46%   |
| Serbia      | 12        | 0.42%   |
| Vietnam     | 11        | 0.39%   |
| Singapore   | 11        | 0.39%   |
| Ireland     | 11        | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 36        | 1.25%   |
| Sydney            | 33        | 1.14%   |
| Sao Paulo         | 23        | 0.8%    |
| Berlin            | 23        | 0.8%    |
| Mexico City       | 21        | 0.73%   |
| Vienna            | 20        | 0.69%   |
| Milan             | 18        | 0.62%   |
| Warsaw            | 17        | 0.59%   |
| St Petersburg     | 17        | 0.59%   |
| Santiago          | 17        | 0.59%   |
| Minsk             | 17        | 0.59%   |
| Melbourne         | 16        | 0.55%   |
| Madrid            | 16        | 0.55%   |
| Montreal          | 14        | 0.49%   |
| Sofia             | 13        | 0.45%   |
| Prague            | 13        | 0.45%   |
| Paris             | 13        | 0.45%   |
| Helsinki          | 13        | 0.45%   |
| Delhi             | 13        | 0.45%   |
| Budapest          | 13        | 0.45%   |
| Rio de Janeiro    | 12        | 0.42%   |
| Istanbul          | 12        | 0.42%   |
| Bogotá           | 12        | 0.42%   |
| Amsterdam         | 12        | 0.42%   |
| Toronto           | 11        | 0.38%   |
| Singapore         | 11        | 0.38%   |
| Seattle           | 11        | 0.38%   |
| Munich            | 11        | 0.38%   |
| Lisbon            | 11        | 0.38%   |
| Brisbane          | 11        | 0.38%   |
| Bangkok           | 11        | 0.38%   |
| Hamburg           | 10        | 0.35%   |
| Frankfurt am Main | 10        | 0.35%   |
| Brussels          | 10        | 0.35%   |
| Brasília         | 10        | 0.35%   |
| San Jose          | 9         | 0.31%   |
| Palmas            | 9         | 0.31%   |
| New York          | 9         | 0.31%   |
| Los Angeles       | 9         | 0.31%   |
| London            | 9         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 800       | 1131   | 19.38%  |
| Sandisk                        | 368       | 439    | 8.91%   |
| WDC                            | 365       | 521    | 8.84%   |
| Seagate                        | 357       | 480    | 8.65%   |
| Kingston                       | 220       | 260    | 5.33%   |
| Toshiba                        | 191       | 248    | 4.63%   |
| SK hynix                       | 152       | 164    | 3.68%   |
| Intel                          | 147       | 199    | 3.56%   |
| Crucial                        | 147       | 191    | 3.56%   |
| Unknown                        | 146       | 177    | 3.54%   |
| Micron Technology              | 143       | 154    | 3.46%   |
| Phison Electronics             | 74        | 91     | 1.79%   |
| Micron/Crucial Technology      | 65        | 71     | 1.57%   |
| Apple                          | 57        | 75     | 1.38%   |
| KIOXIA                         | 56        | 67     | 1.36%   |
| A-DATA Technology              | 53        | 60     | 1.28%   |
| Silicon Motion                 | 52        | 60     | 1.26%   |
| Hitachi                        | 48        | 65     | 1.16%   |
| Kingston Technology Company    | 47        | 56     | 1.14%   |
| HGST                           | 45        | 46     | 1.09%   |
| China                          | 41        | 52     | 0.99%   |
| ADATA Technology               | 31        | 35     | 0.75%   |
| PNY                            | 21        | 25     | 0.51%   |
| SPCC                           | 20        | 22     | 0.48%   |
| Patriot                        | 20        | 26     | 0.48%   |
| Netac                          | 20        | 21     | 0.48%   |
| Realtek Semiconductor          | 18        | 22     | 0.44%   |
| MAXIO Technology (Hangzhou)    | 17        | 20     | 0.41%   |
| JMicron Technology             | 17        | 21     | 0.41%   |
| Intenso                        | 17        | 19     | 0.41%   |
| Shenzhen Longsys Electronics   | 12        | 14     | 0.29%   |
| KingSpec                       | 11        | 12     | 0.27%   |
| Unknown                        | 11        | 13     | 0.27%   |
| Team                           | 10        | 12     | 0.24%   |
| Solid State Storage            | 10        | 10     | 0.24%   |
| SABRENT                        | 10        | 10     | 0.24%   |
| Union Memory                   | 9         | 9      | 0.22%   |
| Transcend                      | 9         | 11     | 0.22%   |
| Solid State Storage Technology | 9         | 9      | 0.22%   |
| Phison                         | 9         | 11     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                 | 192       | 4.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                | 117       | 2.63%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                                | 54        | 1.22%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                             | 48        | 1.08%   |
| Kingston SA400S37240G 240GB SSD                                   | 45        | 1.01%   |
| Kingston SA400S37480G 480GB SSD                                   | 42        | 0.95%   |
| Unknown MMC Card  64GB                                            | 40        | 0.9%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB               | 37        | 0.83%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB                 | 35        | 0.79%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB             | 34        | 0.77%   |
| Samsung SSD 980 1TB                                               | 34        | 0.77%   |
| Seagate ST1000LM035-1RK172 1TB                                    | 33        | 0.74%   |
| Phison E12 NVMe Controller 1TB                                    | 32        | 0.72%   |
| Crucial CT500MX500SSD1 500GB                                      | 32        | 0.72%   |
| Intel SSD 660P Series 1024GB                                      | 31        | 0.7%    |
| Unknown MMC Card  32GB                                            | 29        | 0.65%   |
| Unknown MMC Card  128GB                                           | 28        | 0.63%   |
| Toshiba XG6 NVMe SSD Controller 256GB                             | 25        | 0.56%   |
| Samsung SSD 850 EVO 250GB                                         | 25        | 0.56%   |
| Intel SSDPEKNU512GZ 512GB                                         | 25        | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB                                    | 23        | 0.52%   |
| Sandisk WD Black SN850 1TB                                        | 23        | 0.52%   |
| Samsung SSD 870 EVO 1TB                                           | 23        | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                                       | 22        | 0.5%    |
| Samsung SSD 860 EVO 1TB                                           | 21        | 0.47%   |
| Samsung SSD 860 EVO 500GB                                         | 20        | 0.45%   |
| Phison PS5013 E13 NVMe Controller 256GB                           | 19        | 0.43%   |
| Seagate ST500DM002-1BD142 500GB                                   | 18        | 0.41%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 17        | 0.38%   |
| Samsung SSD 850 EVO 500GB                                         | 17        | 0.38%   |
| Toshiba DT01ACA100 1TB                                            | 16        | 0.36%   |
| SK hynix BC501 NVMe Solid State Drive 512GB                       | 16        | 0.36%   |
| Seagate ST2000DM006-2DM164 2TB                                    | 16        | 0.36%   |
| Crucial CT240BX500SSD1 240GB                                      | 16        | 0.36%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 512GB | 16        | 0.36%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                                  | 15        | 0.34%   |
| Toshiba MQ04ABF100 1TB                                            | 15        | 0.34%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB                   | 15        | 0.34%   |
| Phison E16 PCIe4 NVMe Controller 500GB                            | 15        | 0.34%   |
| Kingston SA400S37120G 120GB SSD                                   | 15        | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 340       | 452    | 37.08%  |
| WDC                 | 287       | 413    | 31.3%   |
| Toshiba             | 120       | 162    | 13.09%  |
| Hitachi             | 48        | 65     | 5.23%   |
| HGST                | 45        | 46     | 4.91%   |
| Samsung Electronics | 28        | 37     | 3.05%   |
| Apple               | 18        | 20     | 1.96%   |
| Unknown             | 12        | 14     | 1.31%   |
| QNAP                | 3         | 6      | 0.33%   |
| Maxtor              | 3         | 3      | 0.33%   |
| Fujitsu             | 3         | 3      | 0.33%   |
| USB3.0              | 1         | 1      | 0.11%   |
| USB                 | 1         | 1      | 0.11%   |
| SAGE                | 1         | 1      | 0.11%   |
| Maxone              | 1         | 1      | 0.11%   |
| LaCie               | 1         | 1      | 0.11%   |
| JMicron Technology  | 1         | 1      | 0.11%   |
| Intenso             | 1         | 1      | 0.11%   |
| IB                  | 1         | 2      | 0.11%   |
| ASMT                | 1         | 2      | 0.11%   |
| ACASIS              | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 278       | 389    | 22.13%  |
| Kingston            | 161       | 190    | 12.82%  |
| Crucial             | 144       | 185    | 11.46%  |
| SanDisk             | 98        | 113    | 7.8%    |
| WDC                 | 78        | 94     | 6.21%   |
| A-DATA Technology   | 44        | 50     | 3.5%    |
| China               | 41        | 52     | 3.26%   |
| Intel               | 40        | 63     | 3.18%   |
| Apple               | 26        | 28     | 2.07%   |
| Toshiba             | 24        | 29     | 1.91%   |
| Micron Technology   | 23        | 24     | 1.83%   |
| PNY                 | 21        | 25     | 1.67%   |
| SPCC                | 20        | 22     | 1.59%   |
| Patriot             | 20        | 26     | 1.59%   |
| Netac               | 12        | 12     | 0.96%   |
| SABRENT             | 10        | 10     | 0.8%    |
| KingSpec            | 10        | 11     | 0.8%    |
| Intenso             | 10        | 10     | 0.8%    |
| Team                | 9         | 11     | 0.72%   |
| SK hynix            | 9         | 10     | 0.72%   |
| LITEONIT            | 9         | 9      | 0.72%   |
| LITEON              | 9         | 9      | 0.72%   |
| GOODRAM             | 9         | 13     | 0.72%   |
| Transcend           | 8         | 10     | 0.64%   |
| OCZ                 | 7         | 11     | 0.56%   |
| Lexar               | 7         | 7      | 0.56%   |
| Hewlett-Packard     | 7         | 7      | 0.56%   |
| Gigabyte Technology | 7         | 9      | 0.56%   |
| Apacer              | 7         | 9      | 0.56%   |
| Mushkin             | 6         | 6      | 0.48%   |
| Emtec               | 5         | 6      | 0.4%    |
| ASMT                | 4         | 4      | 0.32%   |
| AMD                 | 4         | 4      | 0.32%   |
| Unknown             | 4         | 6      | 0.32%   |
| XrayDisk            | 3         | 3      | 0.24%   |
| TO Exter            | 3         | 3      | 0.24%   |
| Smartbuy            | 3         | 3      | 0.24%   |
| MidasForce          | 3         | 3      | 0.24%   |
| Colorful            | 3         | 3      | 0.24%   |
| Advantech           | 3         | 3      | 0.24%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1669      | 2207   | 44.2%   |
| SSD     | 1091      | 1565   | 28.89%  |
| HDD     | 804       | 1233   | 21.29%  |
| MMC     | 134       | 160    | 3.55%   |
| Unknown | 78        | 86     | 2.07%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1662      | 2184   | 48.26%  |
| SATA | 1507      | 2732   | 43.76%  |
| SAS  | 141       | 175    | 4.09%   |
| MMC  | 134       | 160    | 3.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1040      | 1532   | 53.44%  |
| 0.51-1.0   | 613       | 819    | 31.5%   |
| 1.01-2.0   | 177       | 257    | 9.1%    |
| 3.01-4.0   | 59        | 84     | 3.03%   |
| 4.01-10.0  | 29        | 61     | 1.49%   |
| 2.01-3.0   | 22        | 26     | 1.13%   |
| 10.01-20.0 | 6         | 19     | 0.31%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 661       | 22.86%  |
| 251-500        | 537       | 18.57%  |
| 1001-2000      | 475       | 16.43%  |
| 101-250        | 351       | 12.14%  |
| 1-20           | 222       | 7.68%   |
| Unknown        | 208       | 7.19%   |
| More than 3000 | 187       | 6.47%   |
| 2001-3000      | 118       | 4.08%   |
| 51-100         | 93        | 3.22%   |
| 21-50          | 38        | 1.31%   |
| 0              | 1         | 0.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 920       | 31.15%  |
| 21-50          | 494       | 16.73%  |
| 101-250        | 372       | 12.6%   |
| 51-100         | 320       | 10.84%  |
| 251-500        | 268       | 9.08%   |
| Unknown        | 208       | 7.04%   |
| 501-1000       | 184       | 6.23%   |
| 1001-2000      | 107       | 3.62%   |
| More than 3000 | 41        | 1.39%   |
| 2001-3000      | 38        | 1.29%   |
| 0              | 1         | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 4         | 4      | 3.28%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3         | 3      | 2.46%   |
| Intel SSDSC2CT120A3 120GB             | 3         | 9      | 2.46%   |
| HGST HTS721010A9E630 1TB              | 3         | 3      | 2.46%   |
| WDC WD20EZRX-00D8PB0 2TB              | 2         | 2      | 1.64%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 1.64%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 1.64%   |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 1.64%   |
| Seagate ST31000524AS 1TB              | 2         | 2      | 1.64%   |
| SanDisk SSD PLUS 480GB                | 2         | 2      | 1.64%   |
| SanDisk SD8SBAT256G1122 256GB SSD     | 2         | 2      | 1.64%   |
| Kingston SA400S37480G 480GB SSD       | 2         | 3      | 1.64%   |
| Crucial CT120M500SSD1 120GB           | 2         | 7      | 1.64%   |
| YS SSD 240GB                          | 1         | 1      | 0.82%   |
| Wibtek W800S 512GB SSD                | 1         | 1      | 0.82%   |
| WDC WDS100T2G0A-00JH30 1TB SSD        | 1         | 1      | 0.82%   |
| WDC WD5000LPCX-60VHAT0 500GB          | 1         | 1      | 0.82%   |
| WDC WD5000BPVT-75HXZT1 500GB          | 1         | 1      | 0.82%   |
| WDC WD5000AVCS-632DY1 500GB           | 1         | 3      | 0.82%   |
| WDC WD5000AAKX-603CA0 500GB           | 1         | 1      | 0.82%   |
| WDC WD5000AAKS-00UU3A0 500GB          | 1         | 1      | 0.82%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 1      | 0.82%   |
| WDC WD40PURX-64GVNY0 4TB              | 1         | 1      | 0.82%   |
| WDC WD30EZRX-00SPEB0 3TB              | 1         | 1      | 0.82%   |
| WDC WD30EFRX-68AX9N0 3TB              | 1         | 1      | 0.82%   |
| WDC WD2500BEVT-80A23T0 250GB          | 1         | 1      | 0.82%   |
| WDC WD20EZRZ-22Z5HB0 2TB              | 1         | 1      | 0.82%   |
| WDC WD20EARS-00J2GB0 2TB              | 1         | 1      | 0.82%   |
| WDC WD10JPVT-60A1YT0 1TB              | 1         | 1      | 0.82%   |
| WDC WD10EZRZ-00HTKB0 1TB              | 1         | 1      | 0.82%   |
| WDC WD10EZEX-08WN4A0 1TB              | 1         | 1      | 0.82%   |
| WDC WD1002FAEX-00Y9A0 1TB             | 1         | 1      | 0.82%   |
| Toshiba MQ02ABD100H 1TB               | 1         | 1      | 0.82%   |
| SSSTC CVB-8D128-HP 128GB              | 1         | 1      | 0.82%   |
| SPCC Solid State Disk 128GB           | 1         | 1      | 0.82%   |
| SK hynix HFS128G3AMNB-2200A 128GB SSD | 1         | 1      | 0.82%   |
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 0.82%   |
| Seagate ST9750420AS 752GB             | 1         | 1      | 0.82%   |
| Seagate ST9500420AS 500GB             | 1         | 1      | 0.82%   |
| Seagate ST9250827AS 250GB             | 1         | 1      | 0.82%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 23        | 26     | 19.49%  |
| WDC                         | 19        | 24     | 16.1%   |
| Samsung Electronics         | 13        | 19     | 11.02%  |
| Intel                       | 9         | 15     | 7.63%   |
| Hitachi                     | 7         | 7      | 5.93%   |
| Toshiba                     | 5         | 5      | 4.24%   |
| SanDisk                     | 5         | 5      | 4.24%   |
| Kingston                    | 5         | 8      | 4.24%   |
| HGST                        | 5         | 5      | 4.24%   |
| Crucial                     | 4         | 9      | 3.39%   |
| SK hynix                    | 2         | 2      | 1.69%   |
| Micron Technology           | 2         | 2      | 1.69%   |
| Maxtor                      | 2         | 2      | 1.69%   |
| LITEONIT                    | 2         | 2      | 1.69%   |
| Intenso                     | 2         | 2      | 1.69%   |
| China                       | 2         | 2      | 1.69%   |
| A-DATA Technology           | 2         | 2      | 1.69%   |
| YS                          | 1         | 1      | 0.85%   |
| Wibtek                      | 1         | 1      | 0.85%   |
| SSSTC                       | 1         | 1      | 0.85%   |
| SPCC                        | 1         | 1      | 0.85%   |
| Netac                       | 1         | 1      | 0.85%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.85%   |
| LITEON                      | 1         | 1      | 0.85%   |
| HPE                         | 1         | 1      | 0.85%   |
| Apple                       | 1         | 1      | 0.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 23        | 26     | 35.94%  |
| WDC                 | 16        | 20     | 25%     |
| Hitachi             | 7         | 7      | 10.94%  |
| Toshiba             | 5         | 5      | 7.81%   |
| Samsung Electronics | 5         | 10     | 7.81%   |
| HGST                | 5         | 5      | 7.81%   |
| Maxtor              | 2         | 2      | 3.13%   |
| Apple               | 1         | 1      | 1.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 60        | 76     | 53.1%   |
| SSD  | 48        | 65     | 42.48%  |
| NVMe | 5         | 5      | 4.42%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1917      | 3424   | 64.2%   |
| Works    | 962       | 1681   | 32.22%  |
| Malfunc  | 107       | 146    | 3.58%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1488      | 37.97%  |
| AMD                                     | 601       | 15.34%  |
| Samsung Electronics                     | 562       | 14.34%  |
| SanDisk                                 | 282       | 7.2%    |
| SK hynix                                | 142       | 3.62%   |
| Micron Technology                       | 120       | 3.06%   |
| Kingston Technology Company             | 111       | 2.83%   |
| Phison Electronics                      | 81        | 2.07%   |
| Micron/Crucial Technology               | 67        | 1.71%   |
| Silicon Motion                          | 54        | 1.38%   |
| ASMedia Technology                      | 54        | 1.38%   |
| KIOXIA                                  | 53        | 1.35%   |
| Toshiba America Info Systems            | 51        | 1.3%    |
| ADATA Technology                        | 39        | 1%      |
| Marvell Technology Group                | 25        | 0.64%   |
| Solid State Storage Technology          | 20        | 0.51%   |
| Realtek Semiconductor                   | 18        | 0.46%   |
| MAXIO Technology (Hangzhou)             | 17        | 0.43%   |
| Union Memory (Shenzhen)                 | 16        | 0.41%   |
| Nvidia                                  | 14        | 0.36%   |
| Apple                                   | 14        | 0.36%   |
| Shenzhen Longsys Electronics            | 12        | 0.31%   |
| Seagate Technology                      | 12        | 0.31%   |
| Netac Technology                        | 9         | 0.23%   |
| JMicron Technology                      | 9         | 0.23%   |
| LSI Logic / Symbios Logic               | 7         | 0.18%   |
| Lenovo                                  | 7         | 0.18%   |
| Yangtze Memory Technologies             | 5         | 0.13%   |
| VIA Technologies                        | 4         | 0.1%    |
| Solidigm                                | 4         | 0.1%    |
| Broadcom / LSI                          | 4         | 0.1%    |
| INNOGRIT                                | 3         | 0.08%   |
| Silicon Image                           | 2         | 0.05%   |
| Shenzhen Unionmemory Information System | 2         | 0.05%   |
| Lite-On Technology                      | 2         | 0.05%   |
| Biwin Storage Technology                | 2         | 0.05%   |
| Adaptec                                 | 2         | 0.05%   |
| ULi Electronics                         | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]        | 1         | 0.03%   |
| PMC-Sierra                              | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 426       | 9.96%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 204       | 4.77%   |
| Intel Volume Management Device NVMe RAID Controller                            | 155       | 3.63%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 145       | 3.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 128       | 2.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 122       | 2.85%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 87        | 2.04%   |
| AMD 500 Series Chipset SATA Controller                                         | 86        | 2.01%   |
| AMD 400 Series Chipset SATA Controller                                         | 86        | 2.01%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 78        | 1.82%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 78        | 1.82%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 64        | 1.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 60        | 1.4%    |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 56        | 1.31%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 52        | 1.22%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 50        | 1.17%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 50        | 1.17%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 48        | 1.12%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 46        | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 46        | 1.08%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 43        | 1.01%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 42        | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 42        | 0.98%   |
| Intel Tiger Lake-LP SATA Controller                                            | 41        | 0.96%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 40        | 0.94%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 40        | 0.94%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 37        | 0.87%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 35        | 0.82%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 35        | 0.82%   |
| Intel Comet Lake SATA AHCI Controller                                          | 35        | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 35        | 0.82%   |
| Phison E12 NVMe Controller                                                     | 33        | 0.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 32        | 0.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 31        | 0.73%   |
| Intel SSD 660P Series                                                          | 31        | 0.73%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 29        | 0.68%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 29        | 0.68%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 29        | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 28        | 0.65%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 27        | 0.63%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1783      | 46.12%  |
| NVMe | 1653      | 42.76%  |
| RAID | 307       | 7.94%   |
| IDE  | 110       | 2.85%   |
| SAS  | 7         | 0.18%   |
| SCSI | 6         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 1943      | 68.75%  |
| AMD                      | 873       | 30.89%  |
| ARM                      | 7         | 0.25%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.04%   |
| CentaurHauls             | 1         | 0.04%   |
| Unknown                  | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 68        | 2.4%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 45        | 1.59%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 35        | 1.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 33        | 1.17%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 33        | 1.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 27        | 0.95%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 26        | 0.92%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 25        | 0.88%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 25        | 0.88%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 24        | 0.85%   |
| AMD Ryzen 5 3600 6-Core Processor             | 24        | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 23        | 0.81%   |
| Intel 12th Gen Core i7-12700H                 | 23        | 0.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 0.78%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 22        | 0.78%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 21        | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 0.74%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 21        | 0.74%   |
| Intel 12th Gen Core i7-1255U                  | 20        | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 0.67%   |
| Intel 12th Gen Core i7-1260P                  | 19        | 0.67%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 19        | 0.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 18        | 0.64%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 18        | 0.64%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 18        | 0.64%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 17        | 0.6%    |
| Intel 12th Gen Core i5-12500H                 | 17        | 0.6%    |
| Intel 12th Gen Core i5-1235U                  | 17        | 0.6%    |
| AMD Ryzen 5 5600G with Radeon Graphics        | 17        | 0.6%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 17        | 0.6%    |
| AMD Ryzen 7 5825U with Radeon Graphics        | 16        | 0.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.53%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 15        | 0.53%   |
| AMD Ryzen 9 7950X 16-Core Processor           | 15        | 0.53%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 15        | 0.53%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 15        | 0.53%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 15        | 0.53%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 14        | 0.5%    |
| Intel Core i7-3770 CPU @ 3.40GHz              | 13        | 0.46%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 13        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 562       | 19.88%  |
| Other                   | 503       | 17.79%  |
| Intel Core i7           | 448       | 15.85%  |
| AMD Ryzen 7             | 284       | 10.05%  |
| AMD Ryzen 5             | 280       | 9.9%    |
| Intel Core i3           | 132       | 4.67%   |
| AMD Ryzen 9             | 110       | 3.89%   |
| Intel Celeron           | 84        | 2.97%   |
| Intel Xeon              | 58        | 2.05%   |
| Intel Core 2 Duo        | 44        | 1.56%   |
| Intel Atom              | 36        | 1.27%   |
| AMD Ryzen 3             | 31        | 1.1%    |
| AMD Ryzen 7 PRO         | 23        | 0.81%   |
| Intel Pentium           | 19        | 0.67%   |
| AMD FX                  | 19        | 0.67%   |
| Intel Core i9           | 17        | 0.6%    |
| AMD A10                 | 16        | 0.57%   |
| Intel Pentium Silver    | 15        | 0.53%   |
| AMD Ryzen 5 PRO         | 15        | 0.53%   |
| AMD Phenom II X4        | 13        | 0.46%   |
| AMD A6                  | 13        | 0.46%   |
| Intel Core 2 Quad       | 11        | 0.39%   |
| AMD A8                  | 10        | 0.35%   |
| AMD Ryzen Threadripper  | 7         | 0.25%   |
| AMD Athlon              | 7         | 0.25%   |
| AMD A4                  | 7         | 0.25%   |
| Intel Pentium Gold      | 5         | 0.18%   |
| Intel Pentium Dual      | 5         | 0.18%   |
| Intel Pentium Dual-Core | 4         | 0.14%   |
| Intel Genuine           | 4         | 0.14%   |
| AMD E2                  | 4         | 0.14%   |
| Intel Core m5           | 3         | 0.11%   |
| Intel Core 2            | 3         | 0.11%   |
| AMD Phenom II X6        | 3         | 0.11%   |
| AMD Phenom II X2        | 3         | 0.11%   |
| AMD E1                  | 3         | 0.11%   |
| AMD A12                 | 3         | 0.11%   |
| Intel Core m3           | 2         | 0.07%   |
| Intel Core M            | 2         | 0.07%   |
| Intel Celeron Dual-Core | 2         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 975       | 34.5%   |
| 2       | 685       | 24.24%  |
| 8       | 412       | 14.58%  |
| 6       | 401       | 14.19%  |
| 12      | 120       | 4.25%   |
| 10      | 78        | 2.76%   |
| 14      | 64        | 2.26%   |
| 16      | 53        | 1.88%   |
| 24      | 11        | 0.39%   |
| 1       | 11        | 0.39%   |
| 3       | 6         | 0.21%   |
| Unknown | 3         | 0.11%   |
| 36      | 2         | 0.07%   |
| 32      | 2         | 0.07%   |
| 20      | 2         | 0.07%   |
| 18      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2805      | 99.26%  |
| 2       | 18        | 0.64%   |
| Unknown | 3         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2302      | 81.43%  |
| 1       | 521       | 18.43%  |
| Unknown | 3         | 0.11%   |
| 4       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2819      | 99.75%  |
| 64-bit         | 6         | 0.21%   |
| Unknown        | 1         | 0.04%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1997      | 70.39%  |
| 0x0a50000c | 85        | 3%      |
| 0x0a50000d | 72        | 2.54%   |
| 0x08108109 | 49        | 1.73%   |
| 0x0a601203 | 46        | 1.62%   |
| 0x08608103 | 45        | 1.59%   |
| 0x08600106 | 45        | 1.59%   |
| 0x0a404102 | 44        | 1.55%   |
| 0x0a20120a | 44        | 1.55%   |
| 0x08701021 | 38        | 1.34%   |
| 0x0800820d | 31        | 1.09%   |
| 0x0a201016 | 20        | 0.7%    |
| 0x08600104 | 19        | 0.67%   |
| 0x08108102 | 18        | 0.63%   |
| 0x08701030 | 16        | 0.56%   |
| 0x0a404101 | 14        | 0.49%   |
| 0x010000c8 | 11        | 0.39%   |
| 0x06006705 | 10        | 0.35%   |
| 0x06001119 | 10        | 0.35%   |
| 0x08a00008 | 9         | 0.32%   |
| 0x08608104 | 9         | 0.32%   |
| 0x08608102 | 9         | 0.32%   |
| 0x08701013 | 8         | 0.28%   |
| 0x08600103 | 8         | 0.28%   |
| 0x06000822 | 8         | 0.28%   |
| 0x0a704103 | 7         | 0.25%   |
| 0x0a201025 | 7         | 0.25%   |
| 0x08600109 | 7         | 0.25%   |
| 0x08101016 | 7         | 0.25%   |
| 0x0a201009 | 6         | 0.21%   |
| 0x08001138 | 6         | 0.21%   |
| 0x08001137 | 6         | 0.21%   |
| 0x0600611a | 6         | 0.21%   |
| 0x0a201205 | 5         | 0.18%   |
| 0x0810100b | 5         | 0.18%   |
| 0x0700010f | 5         | 0.18%   |
| 0x010000b6 | 5         | 0.18%   |
| 0x0a704101 | 4         | 0.14%   |
| 0x0a50000b | 4         | 0.14%   |
| 0x0a201204 | 4         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 475       | 16.79%  |
| Zen 3             | 265       | 9.37%   |
| Alderlake Hybrid  | 250       | 8.84%   |
| Unknown           | 231       | 8.17%   |
| TigerLake         | 181       | 6.4%    |
| Haswell           | 163       | 5.76%   |
| Zen 2             | 148       | 5.23%   |
| IvyBridge         | 148       | 5.23%   |
| Skylake           | 140       | 4.95%   |
| Zen+              | 105       | 3.71%   |
| SandyBridge       | 100       | 3.53%   |
| Icelake           | 81        | 2.86%   |
| CometLake         | 80        | 2.83%   |
| Silvermont        | 57        | 2.01%   |
| Broadwell         | 54        | 1.91%   |
| Penryn            | 52        | 1.84%   |
| Westmere          | 49        | 1.73%   |
| Goldmont plus     | 38        | 1.34%   |
| Zen               | 36        | 1.27%   |
| Piledriver        | 32        | 1.13%   |
| K10               | 24        | 0.85%   |
| Excavator         | 24        | 0.85%   |
| Core              | 21        | 0.74%   |
| Tremont           | 13        | 0.46%   |
| Goldmont          | 13        | 0.46%   |
| Nehalem           | 8         | 0.28%   |
| Puma              | 7         | 0.25%   |
| Steamroller       | 6         | 0.21%   |
| Jaguar            | 6         | 0.21%   |
| K8 Hammer         | 5         | 0.18%   |
| Bonnell           | 5         | 0.18%   |
| Bulldozer         | 4         | 0.14%   |
| Gracemont         | 3         | 0.11%   |
| K10 Llano         | 2         | 0.07%   |
| Meteorlake Hybrid | 1         | 0.04%   |
| K8 & K10 hybrid   | 1         | 0.04%   |
| Bobcat            | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1597      | 47.33%  |
| AMD                              | 909       | 26.94%  |
| Nvidia                           | 852       | 25.25%  |
| Matrox Electronics Systems       | 10        | 0.3%    |
| ASPEED Technology                | 3         | 0.09%   |
| Zhaoxin                          | 1         | 0.03%   |
| VIA Technologies                 | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 169       | 4.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 118       | 3.41%   |
| Intel UHD Graphics 620                                                                   | 90        | 2.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 82        | 2.37%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 78        | 2.25%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 78        | 2.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 74        | 2.14%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 68        | 1.96%   |
| AMD Lucienne                                                                             | 65        | 1.88%   |
| Intel HD Graphics 620                                                                    | 63        | 1.82%   |
| AMD Rembrandt [Radeon 680M]                                                              | 63        | 1.82%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 58        | 1.67%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 56        | 1.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 55        | 1.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 54        | 1.56%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 51        | 1.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 51        | 1.47%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 47        | 1.36%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 43        | 1.24%   |
| Intel HD Graphics 530                                                                    | 42        | 1.21%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 41        | 1.18%   |
| AMD Raphael                                                                              | 40        | 1.15%   |
| AMD Barcelo                                                                              | 37        | 1.07%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 35        | 1.01%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 34        | 0.98%   |
| Intel HD Graphics 630                                                                    | 34        | 0.98%   |
| Intel HD Graphics 5500                                                                   | 33        | 0.95%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 33        | 0.95%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 32        | 0.92%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 32        | 0.92%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 30        | 0.87%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 29        | 0.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 28        | 0.81%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 27        | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 27        | 0.78%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 27        | 0.78%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 26        | 0.75%   |
| Intel Core Processor Integrated Graphics Controller                                      | 26        | 0.75%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 26        | 0.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 23        | 0.66%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 1133      | 39.92%  |
| 1 x AMD         | 694       | 24.45%  |
| Intel + Nvidia  | 379       | 13.35%  |
| 1 x Nvidia      | 367       | 12.93%  |
| AMD + Nvidia    | 100       | 3.52%   |
| 2 x AMD         | 60        | 2.11%   |
| Intel + AMD     | 56        | 1.97%   |
| 2 x Intel       | 14        | 0.49%   |
| Other           | 11        | 0.39%   |
| 1 x Matrox      | 9         | 0.32%   |
| 2 x Nvidia      | 7         | 0.25%   |
| 1 x ASPEED      | 2         | 0.07%   |
| 1 x Zhaoxin     | 1         | 0.04%   |
| 1 x VIA         | 1         | 0.04%   |
| 1 x SiS         | 1         | 0.04%   |
| Nvidia + Matrox | 1         | 0.04%   |
| Intel + 2 x AMD | 1         | 0.04%   |
| AMD + ASPEED    | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2367      | 83.2%   |
| Proprietary | 394       | 13.85%  |
| Unknown     | 84        | 2.95%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1525      | 53.32%  |
| 0.01-0.5   | 334       | 11.68%  |
| 1.01-2.0   | 253       | 8.85%   |
| 3.01-4.0   | 225       | 7.87%   |
| 7.01-8.0   | 188       | 6.57%   |
| 0.51-1.0   | 157       | 5.49%   |
| 8.01-16.0  | 89        | 3.11%   |
| 5.01-6.0   | 51        | 1.78%   |
| 16.01-24.0 | 20        | 0.7%    |
| 2.01-3.0   | 17        | 0.59%   |
| 4.01-5.0   | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 409       | 12.45%  |
| Samsung Electronics     | 369       | 11.23%  |
| AU Optronics            | 348       | 10.59%  |
| Chimei Innolux          | 308       | 9.38%   |
| Goldstar                | 237       | 7.21%   |
| Dell                    | 220       | 6.7%    |
| LG Display              | 217       | 6.61%   |
| Hewlett-Packard         | 100       | 3.04%   |
| Apple                   | 96        | 2.92%   |
| Acer                    | 81        | 2.47%   |
| Sharp                   | 72        | 2.19%   |
| Lenovo                  | 71        | 2.16%   |
| AOC                     | 65        | 1.98%   |
| Philips                 | 59        | 1.8%    |
| BenQ                    | 53        | 1.61%   |
| Ancor Communications    | 46        | 1.4%    |
| ASUSTek Computer        | 43        | 1.31%   |
| PANDA                   | 37        | 1.13%   |
| CSO                     | 34        | 1.04%   |
| InfoVision              | 33        | 1%      |
| ViewSonic               | 25        | 0.76%   |
| Iiyama                  | 25        | 0.76%   |
| Chi Mei Optoelectronics | 21        | 0.64%   |
| Gigabyte Technology     | 20        | 0.61%   |
| MSI                     | 19        | 0.58%   |
| TMX                     | 17        | 0.52%   |
| Sceptre Tech            | 16        | 0.49%   |
| Unknown                 | 15        | 0.46%   |
| Sony                    | 13        | 0.4%    |
| Toshiba                 | 8         | 0.24%   |
| Mi                      | 8         | 0.24%   |
| LG Philips              | 8         | 0.24%   |
| Panasonic               | 7         | 0.21%   |
| Fujitsu Siemens         | 7         | 0.21%   |
| HUAWEI                  | 6         | 0.18%   |
| HKC                     | 6         | 0.18%   |
| Eizo                    | 6         | 0.18%   |
| Vizio                   | 5         | 0.15%   |
| Belinea                 | 5         | 0.15%   |
| ___                     | 4         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 19        | 0.56%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 18        | 0.53%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 14        | 0.41%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 13        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 13        | 0.38%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 12        | 0.36%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 12        | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 12        | 0.36%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 11        | 0.33%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 11        | 0.33%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 11        | 0.33%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 10        | 0.3%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 9         | 0.27%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch          | 9         | 0.27%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch               | 9         | 0.27%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch          | 9         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1406 1920x1080 309x173mm 13.9-inch      | 9         | 0.27%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 9         | 0.27%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 9         | 0.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 9         | 0.27%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 9         | 0.27%   |
| AOC Q27P2W AOC2702 2560x1440 597x336mm 27.0-inch                      | 9         | 0.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 8         | 0.24%   |
| Goldstar ULTRAGEAR GSM5B7F 2560x1440 597x336mm 27.0-inch              | 8         | 0.24%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch           | 8         | 0.24%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 8         | 0.24%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 8         | 0.24%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 7         | 0.21%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 7         | 0.21%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch              | 7         | 0.21%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 7         | 0.21%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch        | 7         | 0.21%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                     | 7         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 7         | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 7         | 0.21%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                 | 7         | 0.21%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 7         | 0.21%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 7         | 0.21%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 7         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1446      | 46.48%  |
| 1366x768 (WXGA)    | 357       | 11.48%  |
| 3840x2160 (4K)     | 253       | 8.13%   |
| 2560x1440 (QHD)    | 242       | 7.78%   |
| 1920x1200 (WUXGA)  | 105       | 3.38%   |
| 2560x1600          | 90        | 2.89%   |
| 1600x900 (HD+)     | 77        | 2.48%   |
| 3440x1440          | 65        | 2.09%   |
| 1680x1050 (WSXGA+) | 49        | 1.58%   |
| 2560x1080          | 45        | 1.45%   |
| 1440x900 (WXGA+)   | 45        | 1.45%   |
| 1280x800 (WXGA)    | 45        | 1.45%   |
| 2880x1800          | 44        | 1.41%   |
| 1280x1024 (SXGA)   | 44        | 1.41%   |
| 2160x1440          | 18        | 0.58%   |
| 3840x2400          | 17        | 0.55%   |
| 1360x768           | 17        | 0.55%   |
| 2256x1504          | 15        | 0.48%   |
| 3840x1080          | 12        | 0.39%   |
| 2736x1824          | 11        | 0.35%   |
| 2880x1620          | 9         | 0.29%   |
| 2288x1287          | 9         | 0.29%   |
| 1920x1280          | 8         | 0.26%   |
| 3200x2000          | 7         | 0.23%   |
| 2240x1400          | 7         | 0.23%   |
| 1920x540           | 6         | 0.19%   |
| 3840x1600          | 5         | 0.16%   |
| 2520x1680          | 5         | 0.16%   |
| 2160x1350          | 5         | 0.16%   |
| 3456x2160          | 4         | 0.13%   |
| 3000x2000          | 4         | 0.13%   |
| 2048x1152          | 4         | 0.13%   |
| 1024x768 (XGA)     | 4         | 0.13%   |
| Unknown            | 4         | 0.13%   |
| 3200x1800 (QHD+)   | 3         | 0.1%    |
| 3072x1920          | 3         | 0.1%    |
| 2880x1920          | 3         | 0.1%    |
| 1600x1200          | 3         | 0.1%    |
| 3840x2560          | 2         | 0.06%   |
| 3840x1100          | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 776       | 23.53%  |
| 13      | 381       | 11.55%  |
| 14      | 367       | 11.13%  |
| 27      | 338       | 10.25%  |
| 24      | 229       | 6.94%   |
| 23      | 180       | 5.46%   |
| 21      | 158       | 4.79%   |
| 34      | 100       | 3.03%   |
| 31      | 100       | 3.03%   |
| 17      | 89        | 2.7%    |
| 16      | 85        | 2.58%   |
| 12      | 58        | 1.76%   |
| 19      | 47        | 1.43%   |
| 20      | 45        | 1.36%   |
| 18      | 38        | 1.15%   |
| 22      | 35        | 1.06%   |
| Unknown | 28        | 0.85%   |
| 84      | 25        | 0.76%   |
| 11      | 23        | 0.7%    |
| 72      | 19        | 0.58%   |
| 32      | 19        | 0.58%   |
| 28      | 17        | 0.52%   |
| 54      | 16        | 0.49%   |
| 40      | 15        | 0.45%   |
| 48      | 12        | 0.36%   |
| 26      | 11        | 0.33%   |
| 25      | 10        | 0.3%    |
| 10      | 10        | 0.3%    |
| 142     | 9         | 0.27%   |
| 52      | 6         | 0.18%   |
| 49      | 6         | 0.18%   |
| 35      | 6         | 0.18%   |
| 65      | 5         | 0.15%   |
| 37      | 5         | 0.15%   |
| 42      | 4         | 0.12%   |
| 33      | 3         | 0.09%   |
| 86      | 2         | 0.06%   |
| 63      | 2         | 0.06%   |
| 57      | 2         | 0.06%   |
| 38      | 2         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1362      | 42.25%  |
| 501-600        | 670       | 20.78%  |
| 201-300        | 321       | 9.96%   |
| 401-500        | 286       | 8.87%   |
| 601-700        | 160       | 4.96%   |
| 351-400        | 129       | 4%      |
| 701-800        | 122       | 3.78%   |
| 1001-1500      | 51        | 1.58%   |
| 1501-2000      | 47        | 1.46%   |
| 801-900        | 31        | 0.96%   |
| Unknown        | 28        | 0.87%   |
| More than 2000 | 9         | 0.28%   |
| 901-1000       | 6         | 0.19%   |
| 101-200        | 1         | 0.03%   |
| 1-100          | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2177      | 74.84%  |
| 16/10   | 444       | 15.26%  |
| 21/9    | 115       | 3.95%   |
| 3/2     | 71        | 2.44%   |
| 5/4     | 39        | 1.34%   |
| 32/9    | 15        | 0.52%   |
| 4/3     | 13        | 0.45%   |
| 1.00    | 10        | 0.34%   |
| Unknown | 10        | 0.34%   |
| 6/5     | 6         | 0.21%   |
| 0.56    | 4         | 0.14%   |
| 3.40    | 2         | 0.07%   |
| 2.12    | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 784       | 23.96%  |
| 81-90          | 581       | 17.76%  |
| 201-250        | 459       | 14.03%  |
| 301-350        | 346       | 10.57%  |
| 351-500        | 238       | 7.27%   |
| 71-80          | 163       | 4.98%   |
| 151-200        | 144       | 4.4%    |
| More than 1000 | 96        | 2.93%   |
| 251-300        | 95        | 2.9%    |
| 111-120        | 74        | 2.26%   |
| 121-130        | 73        | 2.23%   |
| 61-70          | 47        | 1.44%   |
| 141-150        | 45        | 1.38%   |
| 501-1000       | 44        | 1.34%   |
| Unknown        | 28        | 0.86%   |
| 51-60          | 27        | 0.83%   |
| 91-100         | 15        | 0.46%   |
| 41-50          | 8         | 0.24%   |
| 131-140        | 3         | 0.09%   |
| 1-40           | 2         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1011      | 31.92%  |
| 51-100        | 865       | 27.31%  |
| 101-120       | 688       | 21.72%  |
| 161-240       | 386       | 12.19%  |
| More than 240 | 118       | 3.73%   |
| 1-50          | 71        | 2.24%   |
| Unknown       | 28        | 0.88%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2137      | 74.59%  |
| 2     | 550       | 19.2%   |
| 0     | 106       | 3.7%    |
| 3     | 65        | 2.27%   |
| 4     | 6         | 0.21%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1540      | 36.76%  |
| Realtek Semiconductor           | 1465      | 34.97%  |
| Qualcomm Atheros                | 260       | 6.21%   |
| Broadcom                        | 236       | 5.63%   |
| MediaTek                        | 185       | 4.42%   |
| TP-Link                         | 51        | 1.22%   |
| ASIX Electronics                | 41        | 0.98%   |
| Broadcom Limited                | 38        | 0.91%   |
| Ralink Technology               | 31        | 0.74%   |
| Samsung Electronics             | 27        | 0.64%   |
| Qualcomm                        | 24        | 0.57%   |
| Ralink                          | 23        | 0.55%   |
| Microsoft                       | 22        | 0.53%   |
| Lenovo                          | 21        | 0.5%    |
| Marvell Technology Group        | 20        | 0.48%   |
| Xiaomi                          | 17        | 0.41%   |
| Aquantia                        | 16        | 0.38%   |
| DisplayLink                     | 13        | 0.31%   |
| Nvidia                          | 12        | 0.29%   |
| Sierra Wireless                 | 11        | 0.26%   |
| Google                          | 10        | 0.24%   |
| Qualcomm Atheros Communications | 8         | 0.19%   |
| OPPO Electronics                | 8         | 0.19%   |
| NetGear                         | 8         | 0.19%   |
| Dell                            | 8         | 0.19%   |
| D-Link                          | 8         | 0.19%   |
| Hewlett-Packard                 | 7         | 0.17%   |
| ASUSTek Computer                | 7         | 0.17%   |
| Mellanox Technologies           | 6         | 0.14%   |
| Huawei Technologies             | 5         | 0.12%   |
| Motorola PCS                    | 3         | 0.07%   |
| JMicron Technology              | 3         | 0.07%   |
| ICS Advent                      | 3         | 0.07%   |
| D-Link System                   | 3         | 0.07%   |
| Apple                           | 3         | 0.07%   |
| ZyDAS                           | 2         | 0.05%   |
| Wilocity                        | 2         | 0.05%   |
| VIA Technologies                | 2         | 0.05%   |
| U-Blox                          | 2         | 0.05%   |
| STMicroelectronics              | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 937       | 18.89%  |
| Intel Wi-Fi 6 AX200                                               | 185       | 3.73%   |
| Intel Wi-Fi 6 AX201                                               | 146       | 2.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 123       | 2.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 116       | 2.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 115       | 2.32%   |
| Intel Wireless 8265 / 8275                                        | 106       | 2.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 91        | 1.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 82        | 1.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 78        | 1.57%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 74        | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 73        | 1.47%   |
| Intel Ethernet Controller I225-V                                  | 73        | 1.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 72        | 1.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 66        | 1.33%   |
| Intel I211 Gigabit Network Connection                             | 64        | 1.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 56        | 1.13%   |
| Intel Wireless 7265                                               | 53        | 1.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 50        | 1.01%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 47        | 0.95%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 47        | 0.95%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 44        | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 44        | 0.89%   |
| Intel Wireless 8260                                               | 42        | 0.85%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 42        | 0.85%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 40        | 0.81%   |
| Intel Wireless 7260                                               | 40        | 0.81%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 40        | 0.81%   |
| ASIX AX88179 Gigabit Ethernet                                     | 38        | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 0.75%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 37        | 0.75%   |
| Intel Wireless 3165                                               | 33        | 0.67%   |
| Intel Ethernet Connection I217-LM                                 | 33        | 0.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 32        | 0.65%   |
| Intel Ethernet Connection (2) I219-V                              | 29        | 0.58%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 29        | 0.58%   |
| Broadcom BCM43142 802.11b/g/n                                     | 29        | 0.58%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 27        | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 27        | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 27        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1289      | 51.42%  |
| Realtek Semiconductor                 | 390       | 15.56%  |
| Qualcomm Atheros                      | 215       | 8.58%   |
| Broadcom                              | 188       | 7.5%    |
| MediaTek                              | 184       | 7.34%   |
| TP-Link                               | 48        | 1.91%   |
| Broadcom Limited                      | 32        | 1.28%   |
| Ralink Technology                     | 31        | 1.24%   |
| Ralink                                | 23        | 0.92%   |
| Microsoft                             | 18        | 0.72%   |
| Qualcomm                              | 16        | 0.64%   |
| Sierra Wireless                       | 11        | 0.44%   |
| Qualcomm Atheros Communications       | 8         | 0.32%   |
| NetGear                               | 8         | 0.32%   |
| Marvell Technology Group              | 7         | 0.28%   |
| ASUSTek Computer                      | 7         | 0.28%   |
| Dell                                  | 5         | 0.2%    |
| D-Link                                | 5         | 0.2%    |
| ZyDAS                                 | 2         | 0.08%   |
| Wilocity                              | 2         | 0.08%   |
| Edimax Technology                     | 2         | 0.08%   |
| D-Link System                         | 2         | 0.08%   |
| AVM                                   | 2         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.08%   |
| Wacom                                 | 1         | 0.04%   |
| Sitecom Europe                        | 1         | 0.04%   |
| Quectel Wireless Solutions            | 1         | 0.04%   |
| Qualcomm Technologies                 | 1         | 0.04%   |
| Mercucys                              | 1         | 0.04%   |
| Linksys                               | 1         | 0.04%   |
| IMC Networks                          | 1         | 0.04%   |
| Hewlett-Packard                       | 1         | 0.04%   |
| Belkin Components                     | 1         | 0.04%   |
| Unknown                               | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                  | 185       | 7.34%   |
| Intel Wi-Fi 6 AX201                                                  | 146       | 5.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 114       | 4.53%   |
| Intel Wireless 8265 / 8275                                           | 106       | 4.21%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 82        | 3.26%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 78        | 3.1%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 74        | 2.94%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 73        | 2.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 66        | 2.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 56        | 2.22%   |
| Intel Wireless 7265                                                  | 53        | 2.1%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 50        | 1.98%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 47        | 1.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 47        | 1.87%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 44        | 1.75%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 44        | 1.75%   |
| Intel Wireless 8260                                                  | 42        | 1.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 42        | 1.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 40        | 1.59%   |
| Intel Wireless 7260                                                  | 40        | 1.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 40        | 1.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 37        | 1.47%   |
| Intel Wireless 3165                                                  | 33        | 1.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 32        | 1.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 29        | 1.15%   |
| Broadcom BCM43142 802.11b/g/n                                        | 29        | 1.15%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                              | 27        | 1.07%   |
| Intel Wireless-AC 9260                                               | 26        | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 24        | 0.95%   |
| Intel Alder Lake-S PCH CNVi WiFi                                     | 24        | 0.95%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 22        | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 21        | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 21        | 0.83%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 21        | 0.83%   |
| Realtek 802.11ac NIC                                                 | 20        | 0.79%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter         | 20        | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 19        | 0.75%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 17        | 0.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 15        | 0.6%    |
| Ralink MT7601U Wireless Adapter                                      | 14        | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1272      | 54.15%  |
| Intel                                  | 683       | 29.08%  |
| Broadcom                               | 94        | 4%      |
| Qualcomm Atheros                       | 62        | 2.64%   |
| ASIX Electronics                       | 41        | 1.75%   |
| Samsung Electronics                    | 27        | 1.15%   |
| Lenovo                                 | 21        | 0.89%   |
| Xiaomi                                 | 17        | 0.72%   |
| Aquantia                               | 16        | 0.68%   |
| Marvell Technology Group               | 13        | 0.55%   |
| DisplayLink                            | 13        | 0.55%   |
| Nvidia                                 | 12        | 0.51%   |
| Google                                 | 10        | 0.43%   |
| Qualcomm                               | 8         | 0.34%   |
| OPPO Electronics                       | 8         | 0.34%   |
| Broadcom Limited                       | 6         | 0.26%   |
| Mellanox Technologies                  | 5         | 0.21%   |
| Microsoft                              | 4         | 0.17%   |
| Huawei Technologies                    | 4         | 0.17%   |
| Hewlett-Packard                        | 4         | 0.17%   |
| TP-Link                                | 3         | 0.13%   |
| JMicron Technology                     | 3         | 0.13%   |
| ICS Advent                             | 3         | 0.13%   |
| D-Link                                 | 3         | 0.13%   |
| Apple                                  | 3         | 0.13%   |
| VIA Technologies                       | 2         | 0.09%   |
| 3Com                                   | 2         | 0.09%   |
| Tehuti Networks                        | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| Motorola PCS                           | 1         | 0.04%   |
| MediaTek                               | 1         | 0.04%   |
| IBM                                    | 1         | 0.04%   |
| HMD Global                             | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |
| Dell                                   | 1         | 0.04%   |
| D-Link System                          | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 937       | 38.85%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 123       | 5.1%    |
| Realtek RTL8125 2.5GbE Controller                                 | 116       | 4.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 91        | 3.77%   |
| Intel Ethernet Controller I225-V                                  | 73        | 3.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 72        | 2.99%   |
| Intel I211 Gigabit Network Connection                             | 64        | 2.65%   |
| ASIX AX88179 Gigabit Ethernet                                     | 38        | 1.58%   |
| Intel Ethernet Connection (4) I219-LM                             | 37        | 1.53%   |
| Intel Ethernet Connection I217-LM                                 | 33        | 1.37%   |
| Intel Ethernet Connection (2) I219-V                              | 29        | 1.2%    |
| Intel Ethernet Connection (4) I219-V                              | 27        | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 27        | 1.12%   |
| Intel Ethernet Connection I219-LM                                 | 24        | 1%      |
| Intel Ethernet Connection (7) I219-V                              | 23        | 0.95%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 22        | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 22        | 0.91%   |
| Intel Ethernet Connection (16) I219-V                             | 19        | 0.79%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 17        | 0.7%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 15        | 0.62%   |
| Intel Ethernet Connection (6) I219-V                              | 15        | 0.62%   |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 13        | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 13        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 11        | 0.46%   |
| Intel I210 Gigabit Network Connection                             | 11        | 0.46%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.46%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.46%   |
| Intel Ethernet Connection (2) I218-V                              | 11        | 0.46%   |
| Intel Ethernet Connection (16) I219-LM                            | 11        | 0.46%   |
| Intel Ethernet Connection (14) I219-V                             | 11        | 0.46%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 0.46%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 10        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 10        | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.41%   |
| Nvidia MCP79 Ethernet                                             | 10        | 0.41%   |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 0.41%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.41%   |
| Intel 82574L Gigabit Network Connection                           | 10        | 0.41%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 8         | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2393      | 52.01%  |
| Ethernet | 2180      | 47.38%  |
| Modem    | 19        | 0.41%   |
| Unknown  | 9         | 0.2%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1871      | 63.27%  |
| Ethernet | 1086      | 36.73%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1474      | 52.01%  |
| 1     | 1218      | 42.98%  |
| 3     | 69        | 2.43%   |
| 0     | 53        | 1.87%   |
| 4     | 16        | 0.56%   |
| 6     | 2         | 0.07%   |
| 5     | 2         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1980      | 69.09%  |
| Yes  | 886       | 30.91%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1153      | 53.65%  |
| Realtek Semiconductor           | 242       | 11.26%  |
| Qualcomm Atheros Communications | 107       | 4.98%   |
| Foxconn / Hon Hai               | 107       | 4.98%   |
| IMC Networks                    | 92        | 4.28%   |
| Apple                           | 91        | 4.23%   |
| Broadcom                        | 72        | 3.35%   |
| Cambridge Silicon Radio         | 66        | 3.07%   |
| MediaTek                        | 44        | 2.05%   |
| Lite-On Technology              | 43        | 2%      |
| ASUSTek Computer                | 23        | 1.07%   |
| Realtek                         | 21        | 0.98%   |
| TP-Link                         | 12        | 0.56%   |
| Dell                            | 11        | 0.51%   |
| USI                             | 10        | 0.47%   |
| Toshiba                         | 8         | 0.37%   |
| Hewlett-Packard                 | 8         | 0.37%   |
| Marvell Semiconductor           | 7         | 0.33%   |
| Ralink                          | 6         | 0.28%   |
| Opticis                         | 6         | 0.28%   |
| Foxconn International           | 5         | 0.23%   |
| Askey Computer                  | 2         | 0.09%   |
| Unknown                         | 2         | 0.09%   |
| Taiyo Yuden                     | 1         | 0.05%   |
| Syntek                          | 1         | 0.05%   |
| Smart Modular Technologies      | 1         | 0.05%   |
| Mobile Action Technology        | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Dynex                           | 1         | 0.05%   |
| D-Link                          | 1         | 0.05%   |
| AVM                             | 1         | 0.05%   |
| Alps Electric                   | 1         | 0.05%   |
| Actions                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 286       | 13.3%   |
| Intel Bluetooth wireless interface                  | 255       | 11.85%  |
| Realtek Bluetooth Radio                             | 204       | 9.48%   |
| Intel AX200 Bluetooth                               | 179       | 8.32%   |
| Intel Bluetooth Device                              | 142       | 6.6%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 136       | 6.32%   |
| Intel AX210 Bluetooth                               | 75        | 3.49%   |
| Foxconn / Hon Hai Wireless_Device                   | 72        | 3.35%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 66        | 3.07%   |
| Qualcomm Atheros  Bluetooth Device                  | 61        | 2.84%   |
| IMC Networks Wireless_Device                        | 50        | 2.32%   |
| MediaTek Wireless_Device                            | 44        | 2.05%   |
| Apple Bluetooth Host Controller                     | 44        | 2.05%   |
| Intel Wireless-AC 3168 Bluetooth                    | 38        | 1.77%   |
| Realtek  Bluetooth 4.2 Adapter                      | 30        | 1.39%   |
| Apple Bluetooth USB Host Controller                 | 30        | 1.39%   |
| IMC Networks Bluetooth Radio                        | 26        | 1.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 25        | 1.16%   |
| Realtek Bluetooth Radio                             | 21        | 0.98%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 17        | 0.79%   |
| IMC Networks Bluetooth Device                       | 14        | 0.65%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 0.65%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 13        | 0.6%    |
| TP-Link UB500 Adapter                               | 12        | 0.56%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 11        | 0.51%   |
| Lite-On Wireless_Device                             | 11        | 0.51%   |
| USI Bluetooth Device                                | 10        | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.46%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 9         | 0.42%   |
| Lite-On Bluetooth Device                            | 8         | 0.37%   |
| Broadcom HP Portable Bumble Bee                     | 7         | 0.33%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 7         | 0.33%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.33%   |
| Broadcom BCM2045B (BDC-2.1)                         | 7         | 0.33%   |
| ASUS ASUS USB-BT500                                 | 7         | 0.33%   |
| Ralink RT3290 Bluetooth                             | 6         | 0.28%   |
| Opticis Bluetooth Radio                             | 6         | 0.28%   |
| Lite-On Atheros AR3012 Bluetooth                    | 6         | 0.28%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1872      | 45.49%  |
| AMD                                          | 976       | 23.72%  |
| Nvidia                                       | 649       | 15.77%  |
| C-Media Electronics                          | 82        | 1.99%   |
| Logitech                                     | 52        | 1.26%   |
| Lenovo                                       | 33        | 0.8%    |
| ASUSTek Computer                             | 30        | 0.73%   |
| Realtek Semiconductor                        | 25        | 0.61%   |
| JMTek                                        | 25        | 0.61%   |
| Kingston Technology                          | 22        | 0.53%   |
| GN Netcom                                    | 19        | 0.46%   |
| SteelSeries ApS                              | 18        | 0.44%   |
| Razer USA                                    | 17        | 0.41%   |
| Micro Star International                     | 17        | 0.41%   |
| Focusrite-Novation                           | 15        | 0.36%   |
| Creative Labs                                | 14        | 0.34%   |
| Generalplus Technology                       | 13        | 0.32%   |
| Sony                                         | 11        | 0.27%   |
| Hewlett-Packard                              | 11        | 0.27%   |
| Creative Technology                          | 11        | 0.27%   |
| Plantronics                                  | 10        | 0.24%   |
| Texas Instruments                            | 9         | 0.22%   |
| Corsair                                      | 8         | 0.19%   |
| Apple                                        | 8         | 0.19%   |
| RODE Microphones                             | 7         | 0.17%   |
| Dell                                         | 7         | 0.17%   |
| Microsoft                                    | 6         | 0.15%   |
| Audio-Technica                               | 6         | 0.15%   |
| Zoran Co. Personal Media Division (Nogatech) | 5         | 0.12%   |
| Samson Technologies                          | 5         | 0.12%   |
| Yamaha                                       | 4         | 0.1%    |
| KTMicro                                      | 4         | 0.1%    |
| JBL                                          | 4         | 0.1%    |
| FIFINE Microphones                           | 4         | 0.1%    |
| DSEA A/S                                     | 4         | 0.1%    |
| BEHRINGER International                      | 4         | 0.1%    |
| Schiit Audio                                 | 3         | 0.07%   |
| Jieli Technology                             | 3         | 0.07%   |
| Elgato Systems                               | 3         | 0.07%   |
| Blue Microphones                             | 3         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 509       | 10.13%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 286       | 5.69%   |
| Intel Sunrise Point-LP HD Audio                                            | 232       | 4.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 181       | 3.6%    |
| AMD Starship/Matisse HD Audio Controller                                   | 158       | 3.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 148       | 2.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 143       | 2.85%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 120       | 2.39%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 120       | 2.39%   |
| Intel Cannon Lake PCH cAVS                                                 | 103       | 2.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 92        | 1.83%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 86        | 1.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 80        | 1.59%   |
| Nvidia Audio device                                                        | 79        | 1.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 72        | 1.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 66        | 1.31%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 61        | 1.21%   |
| Nvidia GA106 High Definition Audio Controller                              | 58        | 1.15%   |
| Nvidia GA104 High Definition Audio Controller                              | 57        | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 57        | 1.13%   |
| Intel Comet Lake PCH-LP cAVS                                               | 56        | 1.11%   |
| Intel Comet Lake PCH cAVS                                                  | 56        | 1.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 55        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 55        | 1.09%   |
| Intel 200 Series PCH HD Audio                                              | 54        | 1.07%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 53        | 1.05%   |
| Intel Haswell-ULT HD Audio Controller                                      | 52        | 1.03%   |
| Intel 8 Series HD Audio Controller                                         | 52        | 1.03%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 50        | 0.99%   |
| Intel Broadwell-U Audio Controller                                         | 46        | 0.92%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 45        | 0.9%    |
| Intel Alder Lake-S HD Audio Controller                                     | 45        | 0.9%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 45        | 0.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 42        | 0.84%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 41        | 0.82%   |
| AMD FCH Azalia Controller                                                  | 40        | 0.8%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 38        | 0.76%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 37        | 0.74%   |
| Nvidia TU116 High Definition Audio Controller                              | 32        | 0.64%   |
| Nvidia GP104 High Definition Audio Controller                              | 32        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 317       | 24.98%  |
| SK hynix                     | 212       | 16.71%  |
| Micron Technology            | 161       | 12.69%  |
| Kingston                     | 119       | 9.38%   |
| Crucial                      | 86        | 6.78%   |
| Corsair                      | 75        | 5.91%   |
| Unknown                      | 56        | 4.41%   |
| G.Skill                      | 55        | 4.33%   |
| A-DATA Technology            | 29        | 2.29%   |
| Unknown                      | 28        | 2.21%   |
| Ramaxel Technology           | 20        | 1.58%   |
| Smart                        | 11        | 0.87%   |
| Team                         | 9         | 0.71%   |
| Elpida                       | 9         | 0.71%   |
| Unknown (ABCD)               | 7         | 0.55%   |
| Teikon                       | 6         | 0.47%   |
| Patriot                      | 5         | 0.39%   |
| Nanya Technology             | 5         | 0.39%   |
| Apacer                       | 5         | 0.39%   |
| Timetec                      | 4         | 0.32%   |
| V-GeN                        | 3         | 0.24%   |
| Lexar                        | 3         | 0.24%   |
| GOODRAM                      | 3         | 0.24%   |
| 4ea5                         | 3         | 0.24%   |
| Transcend                    | 2         | 0.16%   |
| Silicon Power                | 2         | 0.16%   |
| Qumo                         | 2         | 0.16%   |
| PNY                          | 2         | 0.16%   |
| ff                           | 2         | 0.16%   |
| CSX                          | 2         | 0.16%   |
| AMD                          | 2         | 0.16%   |
| Unknown (8A02)               | 1         | 0.08%   |
| Unknown (0x5846)             | 1         | 0.08%   |
| Unknown (0x0E9D)             | 1         | 0.08%   |
| Unknown (0x0CDC)             | 1         | 0.08%   |
| Unknown (0x0B5E)             | 1         | 0.08%   |
| Smart Brazil                 | 1         | 0.08%   |
| Sesame                       | 1         | 0.08%   |
| PUSKILL                      | 1         | 0.08%   |
| Patriot Memory (PDP Systems) | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 28        | 2.11%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 1.28%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 16        | 1.21%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 0.83%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 0.83%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 10        | 0.75%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 10        | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.75%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 0.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 9         | 0.68%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 8         | 0.6%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 0.6%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 8         | 0.6%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 7         | 0.53%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 7         | 0.53%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.45%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 6         | 0.45%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 6         | 0.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.45%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 6         | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.45%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 6         | 0.45%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 6         | 0.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.38%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 0.38%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.38%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.38%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 5         | 0.38%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 5         | 0.38%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.38%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.38%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 5         | 0.38%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.38%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s          | 5         | 0.38%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 5         | 0.38%   |
| A-DATA RAM DDR4 3200 8GB DIMM DDR4 3600MT/s                      | 5         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 603       | 55.32%  |
| DDR3    | 195       | 17.89%  |
| DDR5    | 86        | 7.89%   |
| LPDDR5  | 66        | 6.06%   |
| LPDDR4  | 54        | 4.95%   |
| LPDDR3  | 42        | 3.85%   |
| DDR2    | 14        | 1.28%   |
| Unknown | 14        | 1.28%   |
| SDRAM   | 9         | 0.83%   |
| DRAM    | 5         | 0.46%   |
| DDR     | 2         | 0.18%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 612       | 55.74%  |
| DIMM         | 295       | 26.87%  |
| Row Of Chips | 175       | 15.94%  |
| Unknown      | 10        | 0.91%   |
| Chip         | 5         | 0.46%   |
| RIMM         | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 492       | 41.98%  |
| 16384 | 260       | 22.18%  |
| 4096  | 241       | 20.56%  |
| 2048  | 86        | 7.34%   |
| 32768 | 76        | 6.48%   |
| 1024  | 16        | 1.37%   |
| 49152 | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 313       | 26.82%  |
| 2667    | 146       | 12.51%  |
| 1600    | 130       | 11.14%  |
| 6400    | 68        | 5.83%   |
| 2400    | 67        | 5.74%   |
| 4800    | 58        | 4.97%   |
| 2133    | 55        | 4.71%   |
| 3600    | 39        | 3.34%   |
| 1333    | 37        | 3.17%   |
| 4267    | 29        | 2.49%   |
| 1867    | 27        | 2.31%   |
| 1334    | 18        | 1.54%   |
| 5600    | 13        | 1.11%   |
| 1067    | 12        | 1.03%   |
| 3733    | 11        | 0.94%   |
| 3266    | 11        | 0.94%   |
| 667     | 10        | 0.86%   |
| 800     | 8         | 0.69%   |
| Unknown | 8         | 0.69%   |
| 4266    | 7         | 0.6%    |
| 3400    | 7         | 0.6%    |
| 3534    | 6         | 0.51%   |
| 3000    | 6         | 0.51%   |
| 1800    | 6         | 0.51%   |
| 6000    | 5         | 0.43%   |
| 3800    | 5         | 0.43%   |
| 1866    | 5         | 0.43%   |
| 3866    | 4         | 0.34%   |
| 3666    | 4         | 0.34%   |
| 2933    | 4         | 0.34%   |
| 2800    | 4         | 0.34%   |
| 2666    | 4         | 0.34%   |
| 7467    | 3         | 0.26%   |
| 2733    | 3         | 0.26%   |
| 8400    | 2         | 0.17%   |
| 5800    | 2         | 0.17%   |
| 5500    | 2         | 0.17%   |
| 5200    | 2         | 0.17%   |
| 3466    | 2         | 0.17%   |
| 3334    | 2         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Hewlett-Packard               | 18        | 45%     |
| Seiko Epson                   | 6         | 15%     |
| Brother Industries            | 5         | 12.5%   |
| Dymo-CoStar                   | 3         | 7.5%    |
| Canon                         | 3         | 7.5%    |
| Samsung Electronics           | 2         | 5%      |
| STMicroelectronics            | 1         | 2.5%    |
| Samsung Info. Systems America | 1         | 2.5%    |
| Pantum                        | 1         | 2.5%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HP LaserJet P1102                                                     | 3         | 7.5%    |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 2         | 5%      |
| HP LaserJet 1010                                                      | 2         | 5%      |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 5%      |
| STMicroelectronics USB Printing Support                               | 1         | 2.5%    |
| Seiko Epson WF-2860 Series                                            | 1         | 2.5%    |
| Seiko Epson L120 Series                                               | 1         | 2.5%    |
| Seiko Epson ET-2710 Series                                            | 1         | 2.5%    |
| Seiko Epson AL-M310DN                                                 | 1         | 2.5%    |
| Samsung Info. Systems America SAMSUNG SRP-270                         | 1         | 2.5%    |
| Samsung ML-216x Series Laser Printer                                  | 1         | 2.5%    |
| Samsung M2070 Series                                                  | 1         | 2.5%    |
| Pantum M6500W-series                                                  | 1         | 2.5%    |
| HP LaserJet Professional P1102w                                       | 1         | 2.5%    |
| HP LaserJet Pro M148-M149                                             | 1         | 2.5%    |
| HP LaserJet 1020                                                      | 1         | 2.5%    |
| HP Ink Tank 310 series                                                | 1         | 2.5%    |
| HP ENVY Photo 7800 series                                             | 1         | 2.5%    |
| HP ENVY Inspire 7200 series                                           | 1         | 2.5%    |
| HP ENVY 5000 series                                                   | 1         | 2.5%    |
| HP DeskJet 5650c                                                      | 1         | 2.5%    |
| HP DeskJet 3700 series                                                | 1         | 2.5%    |
| HP DeskJet 35xx                                                       | 1         | 2.5%    |
| HP DeskJet 2700 series                                                | 1         | 2.5%    |
| HP DeskJet 2600 series                                                | 1         | 2.5%    |
| HP Deskjet 2050 J510                                                  | 1         | 2.5%    |
| Dymo-CoStar LabelWriter 400                                           | 1         | 2.5%    |
| Canon TR4500 series                                                   | 1         | 2.5%    |
| Canon PIXMA MP250                                                     | 1         | 2.5%    |
| Canon MF3010                                                          | 1         | 2.5%    |
| Brother HL-L2390DW                                                    | 1         | 2.5%    |
| Brother HL-2130 series                                                | 1         | 2.5%    |
| Brother HL-1440 Laser Printer                                         | 1         | 2.5%    |
| Brother DCP-L3550CDW                                                  | 1         | 2.5%    |
| Brother DCP-1600                                                      | 1         | 2.5%    |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Canon       | 7         | 70%     |
| Seiko Epson | 3         | 30%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                       | 3         | 30%     |
| Seiko Epson Scanner                           | 1         | 10%     |
| Seiko Epson GT-X770 [Perfection V500]         | 1         | 10%     |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO] | 1         | 10%     |
| Canon CanoScan LiDE 700F                      | 1         | 10%     |
| Canon CanoScan LiDE 220                       | 1         | 10%     |
| Canon CanoScan LiDE 110                       | 1         | 10%     |
| Canon CanoScan 4400F                          | 1         | 10%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 325       | 17.07%  |
| IMC Networks                           | 217       | 11.4%   |
| Microdia                               | 145       | 7.62%   |
| Bison Electronics                      | 137       | 7.2%    |
| Logitech                               | 136       | 7.14%   |
| Quanta                                 | 132       | 6.93%   |
| Realtek Semiconductor                  | 120       | 6.3%    |
| Apple                                  | 92        | 4.83%   |
| Sunplus Innovation Technology          | 89        | 4.67%   |
| Cheng Uei Precision Industry (Foxlink) | 64        | 3.36%   |
| Syntek                                 | 52        | 2.73%   |
| Luxvisions Innotech Limited            | 50        | 2.63%   |
| Sonix Technology                       | 45        | 2.36%   |
| Acer                                   | 31        | 1.63%   |
| Lite-On Technology                     | 30        | 1.58%   |
| Suyin                                  | 25        | 1.31%   |
| Microsoft                              | 20        | 1.05%   |
| Silicon Motion                         | 15        | 0.79%   |
| Alcor Micro                            | 15        | 0.79%   |
| SunplusIT                              | 13        | 0.68%   |
| Samsung Electronics                    | 13        | 0.68%   |
| Shinetech                              | 9         | 0.47%   |
| Shenzhen Kingcome Optoelectronic       | 8         | 0.42%   |
| Lenovo                                 | 7         | 0.37%   |
| Ricoh                                  | 6         | 0.32%   |
| Razer USA                              | 6         | 0.32%   |
| Unknown                                | 6         | 0.32%   |
| Trust                                  | 5         | 0.26%   |
| AVerMedia Technologies                 | 5         | 0.26%   |
| MacroSilicon                           | 4         | 0.21%   |
| Importek                               | 4         | 0.21%   |
| HD 2MP WEBCAM                          | 4         | 0.21%   |
| Generalplus Technology                 | 4         | 0.21%   |
| ARC International                      | 4         | 0.21%   |
| Z-Star Microelectronics                | 3         | 0.16%   |
| Primax Electronics                     | 3         | 0.16%   |
| Jieli Technology                       | 3         | 0.16%   |
| Google                                 | 3         | 0.16%   |
| Cubeternet                             | 3         | 0.16%   |
| Creative Technology                    | 3         | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 109       | 5.68%   |
| IMC Networks Integrated Camera                      | 81        | 4.22%   |
| Microdia Integrated_Webcam_HD                       | 80        | 4.17%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 70        | 3.65%   |
| Realtek Integrated_Webcam_HD                        | 56        | 2.92%   |
| Bison Integrated Camera                             | 55        | 2.87%   |
| Syntek Integrated Camera                            | 43        | 2.24%   |
| Sunplus Integrated_Webcam_HD                        | 28        | 1.46%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 28        | 1.46%   |
| Logitech Webcam C270                                | 25        | 1.3%    |
| Apple FaceTime HD Camera                            | 25        | 1.3%    |
| Chicony HD Webcam                                   | 24        | 1.25%   |
| Sonix USB2.0 FHD UVC WebCam                         | 23        | 1.2%    |
| Quanta HD User Facing                               | 23        | 1.2%    |
| Quanta HP Wide Vision HD Camera                     | 21        | 1.09%   |
| Sonix USB2.0 HD UVC WebCam                          | 20        | 1.04%   |
| Logitech HD Pro Webcam C920                         | 18        | 0.94%   |
| Apple FaceTime HD Camera (Built-in)                 | 18        | 0.94%   |
| Acer Integrated Camera                              | 18        | 0.94%   |
| Lite-On Integrated Camera                           | 17        | 0.89%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 17        | 0.89%   |
| Bison HD Webcam                                     | 17        | 0.89%   |
| Chicony Integrated Camera (1280x720@30)             | 16        | 0.83%   |
| Quanta HP HD Camera                                 | 15        | 0.78%   |
| Chicony HP TrueVision HD Camera                     | 14        | 0.73%   |
| Chicony HP HD Camera                                | 14        | 0.73%   |
| Bison Integrated RGB Camera                         | 14        | 0.73%   |
| Apple Built-in iSight                               | 14        | 0.73%   |
| Samsung Galaxy series, misc. (MTP mode)             | 13        | 0.68%   |
| Microdia Integrated_Webcam_FHD                      | 13        | 0.68%   |
| Quanta ACER HD User Facing                          | 12        | 0.63%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 12        | 0.63%   |
| Logitech C922 Pro Stream Webcam                     | 12        | 0.63%   |
| Chicony HP Wide Vision HD Camera                    | 12        | 0.63%   |
| Chicony HD User Facing                              | 12        | 0.63%   |
| Luxvisions Innotech Limited Integrated Camera       | 11        | 0.57%   |
| Logitech C920 PRO HD Webcam                         | 11        | 0.57%   |
| Quanta HD Camera                                    | 10        | 0.52%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 10        | 0.52%   |
| IMC Networks ov9734_azurewave_camera                | 10        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 139       | 33.74%  |
| Shenzhen Goodix Technology         | 96        | 23.3%   |
| Validity Sensors                   | 82        | 19.9%   |
| Elan Microelectronics              | 35        | 8.5%    |
| Realtek USB2.0 Finger Print Bridge | 15        | 3.64%   |
| Upek                               | 13        | 3.16%   |
| LighTuning Technology              | 12        | 2.91%   |
| AuthenTec                          | 11        | 2.67%   |
| Samsung Electronics                | 7         | 1.7%    |
| STMicroelectronics                 | 1         | 0.24%   |
| Focal-systems.Corp                 | 1         | 0.24%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 63        | 15.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 39        | 9.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 25        | 6.07%   |
| Elan ELAN:ARM-M4                                                           | 22        | 5.34%   |
| Shenzhen Goodix Fingerprint Reader                                         | 21        | 5.1%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 4.13%   |
| Validity Sensors Synaptics WBDI                                            | 17        | 4.13%   |
| Synaptics WBDI                                                             | 16        | 3.88%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 15        | 3.64%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 3.16%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 2.91%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 2.67%   |
| Elan ELAN:Fingerprint                                                      | 11        | 2.67%   |
| Synaptics UWP WBDI Device                                                  | 10        | 2.43%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 2.43%   |
| Synaptics UWP WBDI                                                         | 8         | 1.94%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 1.7%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.7%    |
| Synaptics Fingerprint reader [HP G6]                                       | 7         | 1.7%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 1.46%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 6         | 1.46%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.46%   |
| Validity Sensors VFS491                                                    | 5         | 1.21%   |
| Synaptics  WBDI                                                            | 5         | 1.21%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 0.97%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 0.97%   |
| Synaptics TouchPad                                                         | 3         | 0.73%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.73%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.73%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.73%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 0.73%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.49%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.49%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.49%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.49%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.49%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.49%   |
| AuthenTec AES2810                                                          | 2         | 0.49%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.49%   |
| AuthenTec AES1600                                                          | 2         | 0.49%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 79        | 54.11%  |
| Alcor Micro                       | 40        | 27.4%   |
| Upek                              | 6         | 4.11%   |
| Lenovo                            | 5         | 3.42%   |
| O2 Micro                          | 3         | 2.05%   |
| Gemalto (was Gemplus)             | 3         | 2.05%   |
| Yubico.com                        | 2         | 1.37%   |
| Bit4id                            | 2         | 1.37%   |
| Aladdin Knowledge Systems         | 2         | 1.37%   |
| VASCO Data Security International | 1         | 0.68%   |
| Realtek Semiconductor             | 1         | 0.68%   |
| Cherry                            | 1         | 0.68%   |
| Advanced Card Systems             | 1         | 0.68%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 40        | 27.4%   |
| Broadcom 58200                                                               | 37        | 25.34%  |
| Broadcom 5880                                                                | 19        | 13.01%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 8.9%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 6.85%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 4.11%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.42%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.37%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.37%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.37%   |
| Bit4id miniLector EVO                                                        | 2         | 1.37%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.37%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.68%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.68%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.68%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.68%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.68%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.68%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1870      | 65.29%  |
| 1     | 804       | 28.07%  |
| 2     | 160       | 5.59%   |
| 3     | 22        | 0.77%   |
| 6     | 3         | 0.1%    |
| 4     | 3         | 0.1%    |
| 8     | 1         | 0.03%   |
| 5     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 405       | 34.23%  |
| Graphics card            | 297       | 25.11%  |
| Multimedia controller    | 170       | 14.37%  |
| Net/wireless             | 132       | 11.16%  |
| Camera                   | 33        | 2.79%   |
| Chipcard                 | 26        | 2.2%    |
| Bluetooth                | 21        | 1.78%   |
| Sound                    | 20        | 1.69%   |
| Unassigned class         | 18        | 1.52%   |
| Communication controller | 17        | 1.44%   |
| Storage                  | 12        | 1.01%   |
| Card reader              | 12        | 1.01%   |
| Net/ethernet             | 9         | 0.76%   |
| Network                  | 3         | 0.25%   |
| Modem                    | 3         | 0.25%   |
| Firewire controller      | 2         | 0.17%   |
| Storage/raid             | 1         | 0.08%   |
| Storage/nvme             | 1         | 0.08%   |
| Storage/ide              | 1         | 0.08%   |

