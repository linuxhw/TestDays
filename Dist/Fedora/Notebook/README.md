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

Total: 11837

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Lenovo        | ThinkPad P53 20QN20VZZC     | [4485ad6d0b](https://linux-hardware.org/?probe=4485ad6d0b) | Oct 13, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [a4dfa6f17f](https://linux-hardware.org/?probe=a4dfa6f17f) | Oct 13, 2023 |
| MSI           | Prestige 14H B12UCX         | [63a132c897](https://linux-hardware.org/?probe=63a132c897) | Oct 13, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [d268453669](https://linux-hardware.org/?probe=d268453669) | Oct 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [17b0ef31ee](https://linux-hardware.org/?probe=17b0ef31ee) | Oct 13, 2023 |
| HP            | G61                         | [34e955886e](https://linux-hardware.org/?probe=34e955886e) | Oct 13, 2023 |
| Dell          | Precision M4700             | [1c10565d3f](https://linux-hardware.org/?probe=1c10565d3f) | Oct 13, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [1b88716ae2](https://linux-hardware.org/?probe=1b88716ae2) | Oct 13, 2023 |
| Dell          | Precision 7520              | [de5b9c8fa1](https://linux-hardware.org/?probe=de5b9c8fa1) | Oct 13, 2023 |
| Acer          | Nitro AN515-44              | [1f1524c080](https://linux-hardware.org/?probe=1f1524c080) | Oct 13, 2023 |
| Dell          | Latitude 7430               | [fb8c320433](https://linux-hardware.org/?probe=fb8c320433) | Oct 13, 2023 |
| Dell          | Inspiron N5110              | [92726caa44](https://linux-hardware.org/?probe=92726caa44) | Oct 12, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [67b91cca13](https://linux-hardware.org/?probe=67b91cca13) | Oct 12, 2023 |
| Dell          | Latitude 3490               | [1c5aa8fca4](https://linux-hardware.org/?probe=1c5aa8fca4) | Oct 12, 2023 |
| Infinix       | ZERO BOOK 13                | [c20c04a240](https://linux-hardware.org/?probe=c20c04a240) | Oct 12, 2023 |
| MSI           | Modern 15 A11M              | [33272a00fb](https://linux-hardware.org/?probe=33272a00fb) | Oct 12, 2023 |
| ASUSTek       | X510UQ                      | [0494369566](https://linux-hardware.org/?probe=0494369566) | Oct 12, 2023 |
| Dell          | XPS 9320                    | [33d6205766](https://linux-hardware.org/?probe=33d6205766) | Oct 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [6396467c6d](https://linux-hardware.org/?probe=6396467c6d) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | [18b3c9fef8](https://linux-hardware.org/?probe=18b3c9fef8) | Oct 12, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [87e16d607b](https://linux-hardware.org/?probe=87e16d607b) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | [7c843b4c27](https://linux-hardware.org/?probe=7c843b4c27) | Oct 12, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [cc8062e568](https://linux-hardware.org/?probe=cc8062e568) | Oct 12, 2023 |
| HP            | EliteBook 840 G6 HC         | [e1b3f5dbeb](https://linux-hardware.org/?probe=e1b3f5dbeb) | Oct 11, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [3fe12fb88e](https://linux-hardware.org/?probe=3fe12fb88e) | Oct 11, 2023 |
| MSI           | PS42 Modern 8MO             | [be9a0659d4](https://linux-hardware.org/?probe=be9a0659d4) | Oct 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [de934434ec](https://linux-hardware.org/?probe=de934434ec) | Oct 11, 2023 |
| Lenovo        | ThinkPad P53 20QN20VZZC     | [2659f02d19](https://linux-hardware.org/?probe=2659f02d19) | Oct 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [275a0bcd64](https://linux-hardware.org/?probe=275a0bcd64) | Oct 11, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [d7d6c74d55](https://linux-hardware.org/?probe=d7d6c74d55) | Oct 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [ea3f6440b2](https://linux-hardware.org/?probe=ea3f6440b2) | Oct 11, 2023 |
| HP            | ProBook 640 G1              | [f6fbcbf614](https://linux-hardware.org/?probe=f6fbcbf614) | Oct 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7aeb935c28](https://linux-hardware.org/?probe=7aeb935c28) | Oct 11, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [3d389cfbfa](https://linux-hardware.org/?probe=3d389cfbfa) | Oct 11, 2023 |
| Avell High... | B.ON                        | [3a419fbd20](https://linux-hardware.org/?probe=3a419fbd20) | Oct 11, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e06a4e6c13](https://linux-hardware.org/?probe=e06a4e6c13) | Oct 11, 2023 |
| Dell          | Precision 3571              | [ac3735cea4](https://linux-hardware.org/?probe=ac3735cea4) | Oct 11, 2023 |
| Dell          | Latitude 5440               | [54922b77f9](https://linux-hardware.org/?probe=54922b77f9) | Oct 10, 2023 |
| Acer          | Nitro AN515-58              | [767f2c26e0](https://linux-hardware.org/?probe=767f2c26e0) | Oct 10, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [b4db6e379a](https://linux-hardware.org/?probe=b4db6e379a) | Oct 10, 2023 |
| HP            | 240 G5 Notebook PC          | [22f4ada2e9](https://linux-hardware.org/?probe=22f4ada2e9) | Oct 10, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [50682769d9](https://linux-hardware.org/?probe=50682769d9) | Oct 10, 2023 |
| Apple         | MacBookPro12,1              | [9de05646a3](https://linux-hardware.org/?probe=9de05646a3) | Oct 10, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [162889c4a3](https://linux-hardware.org/?probe=162889c4a3) | Oct 10, 2023 |
| Lenovo        | ThinkPad T510 43142PU       | [fb8a2b5bf1](https://linux-hardware.org/?probe=fb8a2b5bf1) | Oct 10, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [47ba0bddd0](https://linux-hardware.org/?probe=47ba0bddd0) | Oct 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [28a78b32e5](https://linux-hardware.org/?probe=28a78b32e5) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7d759c245f](https://linux-hardware.org/?probe=7d759c245f) | Oct 10, 2023 |
| Teclast       | F7S                         | [92c51af32a](https://linux-hardware.org/?probe=92c51af32a) | Oct 10, 2023 |
| Notebook      | PCx0Dx                      | [9e8bfb1d9e](https://linux-hardware.org/?probe=9e8bfb1d9e) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [2777b3d965](https://linux-hardware.org/?probe=2777b3d965) | Oct 09, 2023 |
| Lenovo        | ThinkPad T490 20N3S8HL00    | [e75ca9bf06](https://linux-hardware.org/?probe=e75ca9bf06) | Oct 09, 2023 |
| Dell          | Vostro 3700                 | [5776334e3a](https://linux-hardware.org/?probe=5776334e3a) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [749e1a7e28](https://linux-hardware.org/?probe=749e1a7e28) | Oct 09, 2023 |
| Acer          | Predator PH315-51           | [265a8e5346](https://linux-hardware.org/?probe=265a8e5346) | Oct 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f269e7a6ee](https://linux-hardware.org/?probe=f269e7a6ee) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [60a4c67d48](https://linux-hardware.org/?probe=60a4c67d48) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [65a1ff3587](https://linux-hardware.org/?probe=65a1ff3587) | Oct 09, 2023 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [a1ae219e54](https://linux-hardware.org/?probe=a1ae219e54) | Oct 09, 2023 |
| MSI           | Summit E16Flip A12UCT       | [882d0daf54](https://linux-hardware.org/?probe=882d0daf54) | Oct 09, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | [e4158a4175](https://linux-hardware.org/?probe=e4158a4175) | Oct 08, 2023 |
| Google        | Lindar                      | [75852e1ad7](https://linux-hardware.org/?probe=75852e1ad7) | Oct 08, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [d400853f78](https://linux-hardware.org/?probe=d400853f78) | Oct 08, 2023 |
| Dell          | Vostro 1450                 | [55334a897d](https://linux-hardware.org/?probe=55334a897d) | Oct 08, 2023 |
| HP            | 240 G5 Notebook PC          | [db5dd15d83](https://linux-hardware.org/?probe=db5dd15d83) | Oct 08, 2023 |
| Dell          | Inspiron 14 5410            | [5f69a24978](https://linux-hardware.org/?probe=5f69a24978) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | [907f3a4cf1](https://linux-hardware.org/?probe=907f3a4cf1) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | [d003fa7343](https://linux-hardware.org/?probe=d003fa7343) | Oct 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [173accc37f](https://linux-hardware.org/?probe=173accc37f) | Oct 08, 2023 |
| Timi          | A35S                        | [58494c03cf](https://linux-hardware.org/?probe=58494c03cf) | Oct 07, 2023 |
| Dell          | Inspiron 16 Plus 7630       | [51571d43df](https://linux-hardware.org/?probe=51571d43df) | Oct 07, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [bad231ff7d](https://linux-hardware.org/?probe=bad231ff7d) | Oct 07, 2023 |
| Samsung       | 960XFH                      | [0d8aca1f6e](https://linux-hardware.org/?probe=0d8aca1f6e) | Oct 07, 2023 |
| XIAOMI        | Redmi Book Pro 15 2023      | [eac5ec9d19](https://linux-hardware.org/?probe=eac5ec9d19) | Oct 07, 2023 |
| Samsung       | 960XFH                      | [a2138fa3f8](https://linux-hardware.org/?probe=a2138fa3f8) | Oct 07, 2023 |
| HP            | ProBook 455 15.6 inch G9... | [3c93fdc206](https://linux-hardware.org/?probe=3c93fdc206) | Oct 07, 2023 |
| Framework     | Laptop                      | [92ced4e3c6](https://linux-hardware.org/?probe=92ced4e3c6) | Oct 07, 2023 |
| Lenovo        | IdeaPad 320-14IKB 80XK      | [2adab9deb5](https://linux-hardware.org/?probe=2adab9deb5) | Oct 07, 2023 |
| Dell          | Latitude 3490               | [723d6797ae](https://linux-hardware.org/?probe=723d6797ae) | Oct 07, 2023 |
| VANT          | MOOVE14_2023                | [d9379b5405](https://linux-hardware.org/?probe=d9379b5405) | Oct 06, 2023 |
| Timi          | A35S                        | [8d2f6ffa19](https://linux-hardware.org/?probe=8d2f6ffa19) | Oct 06, 2023 |
| Lenovo        | G400 20235                  | [4f9d192833](https://linux-hardware.org/?probe=4f9d192833) | Oct 06, 2023 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [c5c7ad01ed](https://linux-hardware.org/?probe=c5c7ad01ed) | Oct 06, 2023 |
| Lenovo        | Mullins-LarneML             | [73b6f496a3](https://linux-hardware.org/?probe=73b6f496a3) | Oct 06, 2023 |
| HP            | Notebook                    | [be54658252](https://linux-hardware.org/?probe=be54658252) | Oct 06, 2023 |
| HP            | Notebook                    | [02dae8739a](https://linux-hardware.org/?probe=02dae8739a) | Oct 06, 2023 |
| HP            | EliteBook 840 G6            | [e8ae378997](https://linux-hardware.org/?probe=e8ae378997) | Oct 06, 2023 |
| HP            | EliteBook 735 G5            | [108728a0b6](https://linux-hardware.org/?probe=108728a0b6) | Oct 06, 2023 |
| HP            | Laptop 17-bs0xx             | [0b9d1772cd](https://linux-hardware.org/?probe=0b9d1772cd) | Oct 06, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [676106fbb7](https://linux-hardware.org/?probe=676106fbb7) | Oct 06, 2023 |
| Razer         | Blade 15 Base Model (Lat... | [8ae84cb1dc](https://linux-hardware.org/?probe=8ae84cb1dc) | Oct 05, 2023 |
| Dell          | Precision 5480              | [3a87c7a065](https://linux-hardware.org/?probe=3a87c7a065) | Oct 05, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [bfe115219f](https://linux-hardware.org/?probe=bfe115219f) | Oct 05, 2023 |
| Acer          | Aspire A314-23P             | [2ed7997cfe](https://linux-hardware.org/?probe=2ed7997cfe) | Oct 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | [01f88bafa7](https://linux-hardware.org/?probe=01f88bafa7) | Oct 05, 2023 |
| Google        | Magpie                      | [91fa583b13](https://linux-hardware.org/?probe=91fa583b13) | Oct 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [ee95e8f5fd](https://linux-hardware.org/?probe=ee95e8f5fd) | Oct 05, 2023 |
| HP            | EliteBook 655 15.6 inch ... | [7b888eeb58](https://linux-hardware.org/?probe=7b888eeb58) | Oct 05, 2023 |
| Dell          | Inspiron 5459               | [965f7580d3](https://linux-hardware.org/?probe=965f7580d3) | Oct 05, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [09c308ed3d](https://linux-hardware.org/?probe=09c308ed3d) | Oct 05, 2023 |
| MSI           | Prestige 15 A11SCX          | [9a4bc722e5](https://linux-hardware.org/?probe=9a4bc722e5) | Oct 05, 2023 |
| HP            | EliteBook 8460p             | [6be4af5bb3](https://linux-hardware.org/?probe=6be4af5bb3) | Oct 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7700b3d342](https://linux-hardware.org/?probe=7700b3d342) | Oct 04, 2023 |
| Samsung       | 940Z5L                      | [120b5dac7e](https://linux-hardware.org/?probe=120b5dac7e) | Oct 04, 2023 |
| HP            | EliteBook 745 G6            | [77cfc34723](https://linux-hardware.org/?probe=77cfc34723) | Oct 04, 2023 |
| Lenovo        | ThinkPad L13 20R30009RT     | [8bc32c8cb6](https://linux-hardware.org/?probe=8bc32c8cb6) | Oct 04, 2023 |
| HP            | EliteBook 840 G1            | [2447ea5d85](https://linux-hardware.org/?probe=2447ea5d85) | Oct 04, 2023 |
| Dell          | Latitude 7340               | [713640e574](https://linux-hardware.org/?probe=713640e574) | Oct 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [b2f26d1c00](https://linux-hardware.org/?probe=b2f26d1c00) | Oct 04, 2023 |
| HP            | EliteBook 735 G5            | [5600a75dba](https://linux-hardware.org/?probe=5600a75dba) | Oct 04, 2023 |
| MSI           | PR600                       | [09fe9eb818](https://linux-hardware.org/?probe=09fe9eb818) | Oct 04, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7bb81b99a0](https://linux-hardware.org/?probe=7bb81b99a0) | Oct 04, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [eb797a8074](https://linux-hardware.org/?probe=eb797a8074) | Oct 03, 2023 |
| ASUSTek       | K52JT                       | [30a087cc37](https://linux-hardware.org/?probe=30a087cc37) | Oct 03, 2023 |
| HP            | Laptop 14-cf2xxx            | [4c6c3c41b3](https://linux-hardware.org/?probe=4c6c3c41b3) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [452537ff56](https://linux-hardware.org/?probe=452537ff56) | Oct 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [0085d7a6ca](https://linux-hardware.org/?probe=0085d7a6ca) | Oct 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [5813f8d107](https://linux-hardware.org/?probe=5813f8d107) | Oct 03, 2023 |
| Samsung       | 940XGK                      | [63aededb0c](https://linux-hardware.org/?probe=63aededb0c) | Oct 03, 2023 |
| Samsung       | 940XGK                      | [805cef3023](https://linux-hardware.org/?probe=805cef3023) | Oct 03, 2023 |
| HUAWEI        | KLVL-WXXW                   | [a55f97899c](https://linux-hardware.org/?probe=a55f97899c) | Oct 03, 2023 |
| Lenovo        | ThinkPad T420 4236BR4       | [002422b029](https://linux-hardware.org/?probe=002422b029) | Oct 03, 2023 |
| ASUSTek       | Zenbook UX7602ZM_UX7602Z... | [cc7ba8c1ea](https://linux-hardware.org/?probe=cc7ba8c1ea) | Oct 03, 2023 |
| Acer          | Aspire A715-51G             | [6bc4edfef5](https://linux-hardware.org/?probe=6bc4edfef5) | Oct 02, 2023 |
| MSI           | VR630                       | [a9ce96c1ff](https://linux-hardware.org/?probe=a9ce96c1ff) | Oct 02, 2023 |
| HP            | Pavilion 17                 | [d78757ca20](https://linux-hardware.org/?probe=d78757ca20) | Oct 02, 2023 |
| HP            | 15                          | [254f7000e9](https://linux-hardware.org/?probe=254f7000e9) | Oct 02, 2023 |
| Acer          | Aspire A715-51G             | [a9b3098036](https://linux-hardware.org/?probe=a9b3098036) | Oct 02, 2023 |
| Acer          | Swift SF515-51T             | [2452e6e54f](https://linux-hardware.org/?probe=2452e6e54f) | Oct 02, 2023 |
| Apple         | MacBookPro16,3              | [9ca487f2cf](https://linux-hardware.org/?probe=9ca487f2cf) | Oct 02, 2023 |
| HP            | Laptop 14s-dq2xxx           | [4c5eef8118](https://linux-hardware.org/?probe=4c5eef8118) | Oct 02, 2023 |
| HP            | 15                          | [a5814d048c](https://linux-hardware.org/?probe=a5814d048c) | Oct 02, 2023 |
| MSI           | Vector GP68HX 12VH          | [e582127237](https://linux-hardware.org/?probe=e582127237) | Oct 02, 2023 |
| Fujitsu       | LIFEBOOK A357               | [6f11536a5f](https://linux-hardware.org/?probe=6f11536a5f) | Oct 02, 2023 |
| Lenovo        | IdeaPad L3 15ITL6 82HL      | [ae0c9bf33a](https://linux-hardware.org/?probe=ae0c9bf33a) | Oct 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [657482458f](https://linux-hardware.org/?probe=657482458f) | Oct 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [4462bfcb6d](https://linux-hardware.org/?probe=4462bfcb6d) | Oct 02, 2023 |
| Acer          | Aspire A515-45              | [9e09848439](https://linux-hardware.org/?probe=9e09848439) | Oct 02, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [160d49a81f](https://linux-hardware.org/?probe=160d49a81f) | Oct 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [445e604c2e](https://linux-hardware.org/?probe=445e604c2e) | Oct 01, 2023 |
| Google        | Magpie                      | [32a7bba307](https://linux-hardware.org/?probe=32a7bba307) | Oct 01, 2023 |
| Lenovo        | G500 20236                  | [96ce4b8060](https://linux-hardware.org/?probe=96ce4b8060) | Oct 01, 2023 |
| Dell          | Inspiron 15 3515            | [44bfa52d57](https://linux-hardware.org/?probe=44bfa52d57) | Oct 01, 2023 |
| HP            | ProBook 640 G1              | [e1945fe82f](https://linux-hardware.org/?probe=e1945fe82f) | Oct 01, 2023 |
| Acer          | Nitro AN515-55              | [9dd550337d](https://linux-hardware.org/?probe=9dd550337d) | Oct 01, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [16354c8d94](https://linux-hardware.org/?probe=16354c8d94) | Oct 01, 2023 |
| Dell          | XPS 15 9500                 | [a8f95ea32d](https://linux-hardware.org/?probe=a8f95ea32d) | Oct 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [34b8e1853b](https://linux-hardware.org/?probe=34b8e1853b) | Oct 01, 2023 |
| Toshiba       | Satellite L735              | [c969a72669](https://linux-hardware.org/?probe=c969a72669) | Oct 01, 2023 |
| Acer          | Predator PH16-71            | [a07278dc43](https://linux-hardware.org/?probe=a07278dc43) | Oct 01, 2023 |
| Dell          | Latitude 5520               | [024af71640](https://linux-hardware.org/?probe=024af71640) | Oct 01, 2023 |
| Apple         | MacBookPro9,2               | [124425b8b3](https://linux-hardware.org/?probe=124425b8b3) | Oct 01, 2023 |
| Dell          | Latitude E6420              | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [30bf4415dc](https://linux-hardware.org/?probe=30bf4415dc) | Sep 30, 2023 |
| HUAWEI        | VLT-WX0                     | [a312a57d16](https://linux-hardware.org/?probe=a312a57d16) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | [b3a006adc7](https://linux-hardware.org/?probe=b3a006adc7) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | [700c901144](https://linux-hardware.org/?probe=700c901144) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | [1c1f35d1c8](https://linux-hardware.org/?probe=1c1f35d1c8) | Sep 30, 2023 |
| HP            | EliteBook 745 G3            | [16f4068970](https://linux-hardware.org/?probe=16f4068970) | Sep 30, 2023 |
| Dell          | Latitude 7280               | [dbe9d3e4be](https://linux-hardware.org/?probe=dbe9d3e4be) | Sep 30, 2023 |
| Toshiba       | PORTEGE R30-D               | [04ef694f1d](https://linux-hardware.org/?probe=04ef694f1d) | Sep 30, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1402CBA... | [91873a529a](https://linux-hardware.org/?probe=91873a529a) | Sep 30, 2023 |
| Lenovo        | ThinkPad T420 4180BV1       | [e81749053b](https://linux-hardware.org/?probe=e81749053b) | Sep 30, 2023 |
| Acer          | Aspire A514-53              | [6d8a5b1a13](https://linux-hardware.org/?probe=6d8a5b1a13) | Sep 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [c1a605af33](https://linux-hardware.org/?probe=c1a605af33) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [ec1384a424](https://linux-hardware.org/?probe=ec1384a424) | Sep 29, 2023 |
| Razer         | Blade 15 Base Model (Lat... | [95dc405a73](https://linux-hardware.org/?probe=95dc405a73) | Sep 29, 2023 |
| HP            | Laptop 17-cn1xxx            | [051a233121](https://linux-hardware.org/?probe=051a233121) | Sep 29, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [e51fd2a8e9](https://linux-hardware.org/?probe=e51fd2a8e9) | Sep 29, 2023 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [d958b4e16a](https://linux-hardware.org/?probe=d958b4e16a) | Sep 29, 2023 |
| HP            | EliteBook 745 G5            | [b734ec49e2](https://linux-hardware.org/?probe=b734ec49e2) | Sep 29, 2023 |
| Dell          | Latitude 7490               | [a22e4e9304](https://linux-hardware.org/?probe=a22e4e9304) | Sep 29, 2023 |
| HP            | EliteBook 840 G6            | [e57cdefe7a](https://linux-hardware.org/?probe=e57cdefe7a) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [713d59f3d0](https://linux-hardware.org/?probe=713d59f3d0) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [c434f30a15](https://linux-hardware.org/?probe=c434f30a15) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4cef8be854](https://linux-hardware.org/?probe=4cef8be854) | Sep 28, 2023 |
| HP            | EliteBook 840 G2            | [bec979fcd0](https://linux-hardware.org/?probe=bec979fcd0) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [356b5f053d](https://linux-hardware.org/?probe=356b5f053d) | Sep 28, 2023 |
| HP            | EliteBook 840 G6            | [5b87382fce](https://linux-hardware.org/?probe=5b87382fce) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| HP            | ProBook 430 G5              | [9e68b6e2be](https://linux-hardware.org/?probe=9e68b6e2be) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [737b3910bb](https://linux-hardware.org/?probe=737b3910bb) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [b064b5b9ca](https://linux-hardware.org/?probe=b064b5b9ca) | Sep 28, 2023 |
| HP            | Notebook                    | [b13debd2fa](https://linux-hardware.org/?probe=b13debd2fa) | Sep 27, 2023 |
| Zebra Tech... | 10-WLAN-1                   | [9959efdb76](https://linux-hardware.org/?probe=9959efdb76) | Sep 27, 2023 |
| Dell          | Latitude 7490               | [6f5e4547fa](https://linux-hardware.org/?probe=6f5e4547fa) | Sep 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [a95feaee78](https://linux-hardware.org/?probe=a95feaee78) | Sep 27, 2023 |
| Framework     | Laptop                      | [2a65b0dff2](https://linux-hardware.org/?probe=2a65b0dff2) | Sep 27, 2023 |
| Acer          | Predator G3-571             | [f301a514ad](https://linux-hardware.org/?probe=f301a514ad) | Sep 27, 2023 |
| Samsung       | 550XDA                      | [ab1fabfe9b](https://linux-hardware.org/?probe=ab1fabfe9b) | Sep 27, 2023 |
| Chuwi         | CoreBook X                  | [0c31a47880](https://linux-hardware.org/?probe=0c31a47880) | Sep 27, 2023 |
| Notebook      | PCx0Dx                      | [53dd8cbd0d](https://linux-hardware.org/?probe=53dd8cbd0d) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [fed9f17a22](https://linux-hardware.org/?probe=fed9f17a22) | Sep 27, 2023 |
| Acer          | Predator G3-571             | [06b0300670](https://linux-hardware.org/?probe=06b0300670) | Sep 27, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [0dd1b47aa0](https://linux-hardware.org/?probe=0dd1b47aa0) | Sep 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | [c7ec123b46](https://linux-hardware.org/?probe=c7ec123b46) | Sep 27, 2023 |
| Dell          | Latitude E7450              | [afa1cce666](https://linux-hardware.org/?probe=afa1cce666) | Sep 27, 2023 |
| HUAWEI        | RLEF-XX                     | [156140f867](https://linux-hardware.org/?probe=156140f867) | Sep 27, 2023 |
| Dell          | Latitude 5420               | [4f890f283a](https://linux-hardware.org/?probe=4f890f283a) | Sep 26, 2023 |
| Dell          | Latitude 7490               | [8bb2e054ec](https://linux-hardware.org/?probe=8bb2e054ec) | Sep 26, 2023 |
| Dell          | G15 5520                    | [64cfeba3ee](https://linux-hardware.org/?probe=64cfeba3ee) | Sep 26, 2023 |
| Dell          | Latitude 5420               | [3a22857022](https://linux-hardware.org/?probe=3a22857022) | Sep 26, 2023 |
| HP            | Laptop 14s-dq2xxx           | [424e7e3d87](https://linux-hardware.org/?probe=424e7e3d87) | Sep 26, 2023 |
| HP            | EliteBook 745 G6            | [bb5a7f8b2c](https://linux-hardware.org/?probe=bb5a7f8b2c) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [dd48e0075b](https://linux-hardware.org/?probe=dd48e0075b) | Sep 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [35e9d35a69](https://linux-hardware.org/?probe=35e9d35a69) | Sep 26, 2023 |
| Dell          | Inspiron 7577               | [a90c8128d1](https://linux-hardware.org/?probe=a90c8128d1) | Sep 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [dc762f9ae6](https://linux-hardware.org/?probe=dc762f9ae6) | Sep 26, 2023 |
| Lenovo        | ThinkPad T490s 20NX003NR... | [0a38f1e9a4](https://linux-hardware.org/?probe=0a38f1e9a4) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [14766bbd15](https://linux-hardware.org/?probe=14766bbd15) | Sep 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7c547aa37a](https://linux-hardware.org/?probe=7c547aa37a) | Sep 26, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [b22a584cea](https://linux-hardware.org/?probe=b22a584cea) | Sep 26, 2023 |
| Juana Mans... | SF20GM7                     | [355aaa1b07](https://linux-hardware.org/?probe=355aaa1b07) | Sep 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [73d2dae51c](https://linux-hardware.org/?probe=73d2dae51c) | Sep 26, 2023 |
| Lenovo        | Z50-70 20354                | [ccdfae441b](https://linux-hardware.org/?probe=ccdfae441b) | Sep 26, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [37fdb062e1](https://linux-hardware.org/?probe=37fdb062e1) | Sep 26, 2023 |
| Apple         | MacBookPro10,1              | [1c1268d4e0](https://linux-hardware.org/?probe=1c1268d4e0) | Sep 25, 2023 |
| Apple         | MacBookPro10,1              | [4fbb517b71](https://linux-hardware.org/?probe=4fbb517b71) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | [4e0f83e1fe](https://linux-hardware.org/?probe=4e0f83e1fe) | Sep 25, 2023 |
| HP            | EliteBook 840 G3            | [60ff167d14](https://linux-hardware.org/?probe=60ff167d14) | Sep 25, 2023 |
| System76      | Pangolin                    | [3c56c50463](https://linux-hardware.org/?probe=3c56c50463) | Sep 25, 2023 |
| Acer          | Aspire V3-571G              | [6b5dcea023](https://linux-hardware.org/?probe=6b5dcea023) | Sep 25, 2023 |
| Dell          | Latitude E7270              | [98dd5eefb6](https://linux-hardware.org/?probe=98dd5eefb6) | Sep 25, 2023 |
| HP            | 255 G8 Notebook PC          | [91c3333a18](https://linux-hardware.org/?probe=91c3333a18) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [9a24a19f6e](https://linux-hardware.org/?probe=9a24a19f6e) | Sep 25, 2023 |
| HP            | ProBook 6570b               | [a67981aa91](https://linux-hardware.org/?probe=a67981aa91) | Sep 25, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [88385cbacc](https://linux-hardware.org/?probe=88385cbacc) | Sep 25, 2023 |
| Dell          | XPS 13 9310                 | [4233a2e5e3](https://linux-hardware.org/?probe=4233a2e5e3) | Sep 25, 2023 |
| Dell          | XPS 13 9380                 | [705c3fdeff](https://linux-hardware.org/?probe=705c3fdeff) | Sep 25, 2023 |
| MSI           | GL65 Leopard 10SER          | [e97a8fa2c7](https://linux-hardware.org/?probe=e97a8fa2c7) | Sep 25, 2023 |
| HP            | 250 G6 Notebook PC          | [88ce9be8a1](https://linux-hardware.org/?probe=88ce9be8a1) | Sep 24, 2023 |
| MSI           | GL65 Leopard 10SER          | [fac92f385c](https://linux-hardware.org/?probe=fac92f385c) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [0531db8cb8](https://linux-hardware.org/?probe=0531db8cb8) | Sep 24, 2023 |
| Acer          | TravelMate P259-MG          | [26ca7317b2](https://linux-hardware.org/?probe=26ca7317b2) | Sep 24, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [408377c3fd](https://linux-hardware.org/?probe=408377c3fd) | Sep 24, 2023 |
| Apple         | MacBookPro8,2               | [cba55a15ec](https://linux-hardware.org/?probe=cba55a15ec) | Sep 24, 2023 |
| Dell          | Latitude 7400               | [f537b79d15](https://linux-hardware.org/?probe=f537b79d15) | Sep 24, 2023 |
| Lenovo        | V14-ARE 82DQ                | [31a635bff8](https://linux-hardware.org/?probe=31a635bff8) | Sep 24, 2023 |
| HUAWEI        | NBD-WXX9                    | [f728eb13bd](https://linux-hardware.org/?probe=f728eb13bd) | Sep 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | [72940bf53e](https://linux-hardware.org/?probe=72940bf53e) | Sep 24, 2023 |
| HP            | 350 G2                      | [8440938e22](https://linux-hardware.org/?probe=8440938e22) | Sep 24, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [01b1c1acdb](https://linux-hardware.org/?probe=01b1c1acdb) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [fc14083064](https://linux-hardware.org/?probe=fc14083064) | Sep 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [acba7de2ec](https://linux-hardware.org/?probe=acba7de2ec) | Sep 24, 2023 |
| HP            | 255 15.6 inch G10           | [9f02426c5d](https://linux-hardware.org/?probe=9f02426c5d) | Sep 23, 2023 |
| Apple         | MacBookPro10,1              | [18b2a7026b](https://linux-hardware.org/?probe=18b2a7026b) | Sep 23, 2023 |
| Apple         | MacBookPro10,1              | [60f81eeb50](https://linux-hardware.org/?probe=60f81eeb50) | Sep 23, 2023 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [a34763914d](https://linux-hardware.org/?probe=a34763914d) | Sep 23, 2023 |
| HP            | Pavilion dv6                | [bd8ae0385b](https://linux-hardware.org/?probe=bd8ae0385b) | Sep 23, 2023 |
| Dell          | Latitude 7280               | [1d032535e1](https://linux-hardware.org/?probe=1d032535e1) | Sep 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [a6ff891fa1](https://linux-hardware.org/?probe=a6ff891fa1) | Sep 23, 2023 |
| Casper        | NIRVANA NB F500             | [1f66f22544](https://linux-hardware.org/?probe=1f66f22544) | Sep 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [d464d79df3](https://linux-hardware.org/?probe=d464d79df3) | Sep 23, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [11ce4105e1](https://linux-hardware.org/?probe=11ce4105e1) | Sep 23, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [b96887841e](https://linux-hardware.org/?probe=b96887841e) | Sep 23, 2023 |
| Toshiba       | Satellite C70-B             | [904a43b77e](https://linux-hardware.org/?probe=904a43b77e) | Sep 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [6a6fde2ca9](https://linux-hardware.org/?probe=6a6fde2ca9) | Sep 23, 2023 |
| Toshiba       | Satellite C70-B             | [eedf248084](https://linux-hardware.org/?probe=eedf248084) | Sep 23, 2023 |
| Acer          | Aspire ES1-520              | [22ce921c1e](https://linux-hardware.org/?probe=22ce921c1e) | Sep 22, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [535d4769c8](https://linux-hardware.org/?probe=535d4769c8) | Sep 22, 2023 |
| Acer          | Aspire A715-51G             | [674c086aa5](https://linux-hardware.org/?probe=674c086aa5) | Sep 22, 2023 |
| Apple         | MacBookPro11,1              | [169fe58269](https://linux-hardware.org/?probe=169fe58269) | Sep 22, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [c933242918](https://linux-hardware.org/?probe=c933242918) | Sep 22, 2023 |
| Dell          | Inspiron N5110              | [e98b118b85](https://linux-hardware.org/?probe=e98b118b85) | Sep 22, 2023 |
| Apple         | MacBookPro14,1              | [8b1188ba33](https://linux-hardware.org/?probe=8b1188ba33) | Sep 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [909efbf81b](https://linux-hardware.org/?probe=909efbf81b) | Sep 22, 2023 |
| Dell          | Latitude 5420               | [d9c1c1537f](https://linux-hardware.org/?probe=d9c1c1537f) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7b093ed910](https://linux-hardware.org/?probe=7b093ed910) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7c5cc5e0ab](https://linux-hardware.org/?probe=7c5cc5e0ab) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [74fa7aed8b](https://linux-hardware.org/?probe=74fa7aed8b) | Sep 22, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [0e85445e8e](https://linux-hardware.org/?probe=0e85445e8e) | Sep 21, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [3a372bed63](https://linux-hardware.org/?probe=3a372bed63) | Sep 21, 2023 |
| Lenovo        | Slim 7 14IRP8 83A4          | [b1ccf59045](https://linux-hardware.org/?probe=b1ccf59045) | Sep 21, 2023 |
| HP            | Pavilion dv6                | [270b0c0878](https://linux-hardware.org/?probe=270b0c0878) | Sep 21, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [3cd9b7841a](https://linux-hardware.org/?probe=3cd9b7841a) | Sep 21, 2023 |
| Timi          | A35S                        | [ae2a6acf26](https://linux-hardware.org/?probe=ae2a6acf26) | Sep 21, 2023 |
| Timi          | RedmiBook 15                | [af7ac2b917](https://linux-hardware.org/?probe=af7ac2b917) | Sep 21, 2023 |
| Lenovo        | Mullins-LarneML             | [56157a1cff](https://linux-hardware.org/?probe=56157a1cff) | Sep 21, 2023 |
| Samsung       | R530/R730/R540              | [658ca13022](https://linux-hardware.org/?probe=658ca13022) | Sep 21, 2023 |
| Samsung       | 550XBE/350XBE               | [522d50a437](https://linux-hardware.org/?probe=522d50a437) | Sep 21, 2023 |
| HP            | Pavilion g6                 | [11c60c8645](https://linux-hardware.org/?probe=11c60c8645) | Sep 21, 2023 |
| Dell          | Vostro 1310                 | [bc0c23c23c](https://linux-hardware.org/?probe=bc0c23c23c) | Sep 21, 2023 |
| Dell          | XPS 15 9520                 | [2bb7ed1454](https://linux-hardware.org/?probe=2bb7ed1454) | Sep 21, 2023 |
| HP            | 250 G7 Notebook PC          | [a2a2bc81e9](https://linux-hardware.org/?probe=a2a2bc81e9) | Sep 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [b4f1770e14](https://linux-hardware.org/?probe=b4f1770e14) | Sep 20, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [ddf1d6a712](https://linux-hardware.org/?probe=ddf1d6a712) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | [6f81167a6c](https://linux-hardware.org/?probe=6f81167a6c) | Sep 20, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [7377101d6d](https://linux-hardware.org/?probe=7377101d6d) | Sep 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [79111191a0](https://linux-hardware.org/?probe=79111191a0) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | [e0ee68b1a7](https://linux-hardware.org/?probe=e0ee68b1a7) | Sep 20, 2023 |
| TUXEDO        | P65_P67RGRERA               | [97bae35595](https://linux-hardware.org/?probe=97bae35595) | Sep 20, 2023 |
| Lenovo        | ThinkPad P50 20EQS0VV2S     | [b7d1f6f3cf](https://linux-hardware.org/?probe=b7d1f6f3cf) | Sep 20, 2023 |
| TUXEDO        | P65_P67RGRERA               | [0aefa5e3c6](https://linux-hardware.org/?probe=0aefa5e3c6) | Sep 20, 2023 |
| Apple         | MacBook4,1                  | [3434dd8b54](https://linux-hardware.org/?probe=3434dd8b54) | Sep 20, 2023 |
| Samsung       | NC210/NC110                 | [1e194a2568](https://linux-hardware.org/?probe=1e194a2568) | Sep 20, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [27002ca3a9](https://linux-hardware.org/?probe=27002ca3a9) | Sep 20, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [94e8c710d5](https://linux-hardware.org/?probe=94e8c710d5) | Sep 20, 2023 |
| Acer          | Aspire A515-56              | [bb52b1ddc5](https://linux-hardware.org/?probe=bb52b1ddc5) | Sep 20, 2023 |
| Samsung       | 960XFH                      | [c25c858bd4](https://linux-hardware.org/?probe=c25c858bd4) | Sep 19, 2023 |
| Maibenben     | MaiBook M Series            | [dc2eb7a7d7](https://linux-hardware.org/?probe=dc2eb7a7d7) | Sep 19, 2023 |
| Apple         | MacBookAir7,2               | [6edec4d045](https://linux-hardware.org/?probe=6edec4d045) | Sep 19, 2023 |
| MSI           | Summit E15 A11SCST          | [aa908f1cea](https://linux-hardware.org/?probe=aa908f1cea) | Sep 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ca0ad87f0b](https://linux-hardware.org/?probe=ca0ad87f0b) | Sep 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [aeffbe0fe5](https://linux-hardware.org/?probe=aeffbe0fe5) | Sep 19, 2023 |
| Lenovo        | ThinkPad W540 20BG0014US    | [2d1c5101ea](https://linux-hardware.org/?probe=2d1c5101ea) | Sep 19, 2023 |
| HP            | ProBook 6475b               | [43c4870e11](https://linux-hardware.org/?probe=43c4870e11) | Sep 19, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [f9e5656f54](https://linux-hardware.org/?probe=f9e5656f54) | Sep 19, 2023 |
| Lenovo        | ThinkPad X240 20AMS1WN0A    | [858aed6617](https://linux-hardware.org/?probe=858aed6617) | Sep 19, 2023 |
| Dell          | Precision 3581              | [e1c8eb2810](https://linux-hardware.org/?probe=e1c8eb2810) | Sep 18, 2023 |
| Acer          | Aspire A315-59              | [d00d3fed03](https://linux-hardware.org/?probe=d00d3fed03) | Sep 18, 2023 |
| Dell          | Inspiron 5480               | [51aca22643](https://linux-hardware.org/?probe=51aca22643) | Sep 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [4d986c5384](https://linux-hardware.org/?probe=4d986c5384) | Sep 18, 2023 |
| Dell          | Latitude 5490               | [94eb709dfc](https://linux-hardware.org/?probe=94eb709dfc) | Sep 18, 2023 |
| MSI           | Katana GF76 11UD            | [f797b137a3](https://linux-hardware.org/?probe=f797b137a3) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | [f58cf1f72d](https://linux-hardware.org/?probe=f58cf1f72d) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | [68cef2242a](https://linux-hardware.org/?probe=68cef2242a) | Sep 18, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [a4964c1b7a](https://linux-hardware.org/?probe=a4964c1b7a) | Sep 18, 2023 |
| HP            | EliteBook 745 G2            | [7e5ee5a990](https://linux-hardware.org/?probe=7e5ee5a990) | Sep 18, 2023 |
| Lenovo        | ThinkPad T480 20L6SCYF0P    | [c406bf7b56](https://linux-hardware.org/?probe=c406bf7b56) | Sep 18, 2023 |
| Dell          | Inspiron N5110              | [6903c7fc50](https://linux-hardware.org/?probe=6903c7fc50) | Sep 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [1e40d8e0b9](https://linux-hardware.org/?probe=1e40d8e0b9) | Sep 18, 2023 |
| Lenovo        | G50-30 80G0                 | [fa9bd484cd](https://linux-hardware.org/?probe=fa9bd484cd) | Sep 17, 2023 |
| Lenovo        | G400 20235                  | [bd7a7a6f22](https://linux-hardware.org/?probe=bd7a7a6f22) | Sep 17, 2023 |
| Lenovo        | G400 20235                  | [c8ecd1e0c9](https://linux-hardware.org/?probe=c8ecd1e0c9) | Sep 17, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [290f6c66d1](https://linux-hardware.org/?probe=290f6c66d1) | Sep 17, 2023 |
| Dell          | XPS 15 9520                 | [2b66c2969e](https://linux-hardware.org/?probe=2b66c2969e) | Sep 17, 2023 |
| HP            | Pavilion g6                 | [dd1ade8736](https://linux-hardware.org/?probe=dd1ade8736) | Sep 17, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XY... | [93d01648a0](https://linux-hardware.org/?probe=93d01648a0) | Sep 17, 2023 |
| Dell          | Inspiron 1464               | [9830a0345b](https://linux-hardware.org/?probe=9830a0345b) | Sep 17, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [21b0d9faff](https://linux-hardware.org/?probe=21b0d9faff) | Sep 17, 2023 |
| MSI           | Modern 14 B4MW              | [83a224edea](https://linux-hardware.org/?probe=83a224edea) | Sep 17, 2023 |
| Dell          | Inspiron 5566               | [56f2d4d1eb](https://linux-hardware.org/?probe=56f2d4d1eb) | Sep 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3bb8e84b6b](https://linux-hardware.org/?probe=3bb8e84b6b) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [a53b964a47](https://linux-hardware.org/?probe=a53b964a47) | Sep 17, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [648af5d937](https://linux-hardware.org/?probe=648af5d937) | Sep 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [77a72808f7](https://linux-hardware.org/?probe=77a72808f7) | Sep 17, 2023 |
| HP            | 250 G1                      | [0e052c1de2](https://linux-hardware.org/?probe=0e052c1de2) | Sep 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [bf532ab6ec](https://linux-hardware.org/?probe=bf532ab6ec) | Sep 16, 2023 |
| HP            | EliteBook 820 G4            | [a16a2ef714](https://linux-hardware.org/?probe=a16a2ef714) | Sep 16, 2023 |
| MSI           | Modern 14 B4MW              | [06e45359c0](https://linux-hardware.org/?probe=06e45359c0) | Sep 16, 2023 |
| Lenovo        | Legion 5-15IMH05H 81Y6      | [1b2e11b609](https://linux-hardware.org/?probe=1b2e11b609) | Sep 16, 2023 |
| Lenovo        | IdeaPad Z500 5931           | [0986123aac](https://linux-hardware.org/?probe=0986123aac) | Sep 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F7... | [2c90700f4f](https://linux-hardware.org/?probe=2c90700f4f) | Sep 16, 2023 |
| HP            | Laptop 14s-dq2xxx           | [12456f4694](https://linux-hardware.org/?probe=12456f4694) | Sep 16, 2023 |
| Dell          | XPS 9320                    | [99fce2103f](https://linux-hardware.org/?probe=99fce2103f) | Sep 16, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [a5c073ca7a](https://linux-hardware.org/?probe=a5c073ca7a) | Sep 16, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [2085bafc62](https://linux-hardware.org/?probe=2085bafc62) | Sep 16, 2023 |
| Acer          | TravelMate 5335             | [d440c12063](https://linux-hardware.org/?probe=d440c12063) | Sep 16, 2023 |
| Dell          | XPS L501X                   | [13d0075027](https://linux-hardware.org/?probe=13d0075027) | Sep 16, 2023 |
| Dell          | Inspiron M5010              | [c78ab23cc7](https://linux-hardware.org/?probe=c78ab23cc7) | Sep 16, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [ec3d359099](https://linux-hardware.org/?probe=ec3d359099) | Sep 15, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [fa207e873a](https://linux-hardware.org/?probe=fa207e873a) | Sep 15, 2023 |
| Lenovo        | G550 20023                  | [054463900e](https://linux-hardware.org/?probe=054463900e) | Sep 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [b76ae8f9db](https://linux-hardware.org/?probe=b76ae8f9db) | Sep 15, 2023 |
| Lenovo        | G550 20023                  | [cdc9163353](https://linux-hardware.org/?probe=cdc9163353) | Sep 15, 2023 |
| Timi          | Mi NoteBook Ultra           | [1c5a009557](https://linux-hardware.org/?probe=1c5a009557) | Sep 15, 2023 |
| Lenovo        | ThinkPad X220 42911H8       | [032cd70e81](https://linux-hardware.org/?probe=032cd70e81) | Sep 15, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [951dc3d5b0](https://linux-hardware.org/?probe=951dc3d5b0) | Sep 15, 2023 |
| HP            | EliteBook Folio 9470m       | [4a598eb0b3](https://linux-hardware.org/?probe=4a598eb0b3) | Sep 15, 2023 |
| Acer          | Swift SF314-43              | [ae2f1fa903](https://linux-hardware.org/?probe=ae2f1fa903) | Sep 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [982f29b6cc](https://linux-hardware.org/?probe=982f29b6cc) | Sep 14, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a02233b901](https://linux-hardware.org/?probe=a02233b901) | Sep 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [934dc9c297](https://linux-hardware.org/?probe=934dc9c297) | Sep 14, 2023 |
| Apple         | MacBookPro9,2               | [37e1d06001](https://linux-hardware.org/?probe=37e1d06001) | Sep 14, 2023 |
| Acer          | Swift SF314-42              | [d907642716](https://linux-hardware.org/?probe=d907642716) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [426914b6e5](https://linux-hardware.org/?probe=426914b6e5) | Sep 14, 2023 |
| Lenovo        | G505 20240                  | [db2962124c](https://linux-hardware.org/?probe=db2962124c) | Sep 14, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [756eff685a](https://linux-hardware.org/?probe=756eff685a) | Sep 14, 2023 |
| System76      | Darter Pro                  | [78c45153a3](https://linux-hardware.org/?probe=78c45153a3) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [820a13876a](https://linux-hardware.org/?probe=820a13876a) | Sep 14, 2023 |
| Dell          | Latitude 7390               | [4d8e0cb72b](https://linux-hardware.org/?probe=4d8e0cb72b) | Sep 14, 2023 |
| HP            | Pavilion 13 x360 PC         | [58de71a548](https://linux-hardware.org/?probe=58de71a548) | Sep 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | [aea796bbd9](https://linux-hardware.org/?probe=aea796bbd9) | Sep 14, 2023 |
| Toshiba       | PORTEGE M750                | [1c3442d87f](https://linux-hardware.org/?probe=1c3442d87f) | Sep 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [9ace0dfae8](https://linux-hardware.org/?probe=9ace0dfae8) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | [d61823257e](https://linux-hardware.org/?probe=d61823257e) | Sep 13, 2023 |
| Dell          | Latitude 5421               | [6942c0131d](https://linux-hardware.org/?probe=6942c0131d) | Sep 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [cb29d8cb77](https://linux-hardware.org/?probe=cb29d8cb77) | Sep 13, 2023 |
| Dell          | Latitude 7390               | [2afdbd653c](https://linux-hardware.org/?probe=2afdbd653c) | Sep 13, 2023 |
| Fujitsu       | LIFEBOOK UH554              | [92f2e6135e](https://linux-hardware.org/?probe=92f2e6135e) | Sep 13, 2023 |
| Dell          | Inspiron 5566               | [6c9eaad10e](https://linux-hardware.org/?probe=6c9eaad10e) | Sep 13, 2023 |
| Dell          | Inspiron 5558               | [046d28d32d](https://linux-hardware.org/?probe=046d28d32d) | Sep 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0918609cf3](https://linux-hardware.org/?probe=0918609cf3) | Sep 13, 2023 |
| Apple         | MacBookPro9,2               | [e8b1e251a3](https://linux-hardware.org/?probe=e8b1e251a3) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0317b3bcf6](https://linux-hardware.org/?probe=0317b3bcf6) | Sep 13, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [37f8406bab](https://linux-hardware.org/?probe=37f8406bab) | Sep 13, 2023 |
| Lenovo        | IdeaPad Slim 3 15AMN8 82... | [fcac50bfba](https://linux-hardware.org/?probe=fcac50bfba) | Sep 13, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [52a1dc1e19](https://linux-hardware.org/?probe=52a1dc1e19) | Sep 12, 2023 |
| ASUSTek       | K53SK                       | [5dcbdaa6d7](https://linux-hardware.org/?probe=5dcbdaa6d7) | Sep 12, 2023 |
| ASUSTek       | X550JK                      | [0965a776b0](https://linux-hardware.org/?probe=0965a776b0) | Sep 12, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [d1d5edf95c](https://linux-hardware.org/?probe=d1d5edf95c) | Sep 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | [b11bc1c28f](https://linux-hardware.org/?probe=b11bc1c28f) | Sep 12, 2023 |
| ASUSTek       | X550JK                      | [00a34c8719](https://linux-hardware.org/?probe=00a34c8719) | Sep 12, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [3ef24a5b48](https://linux-hardware.org/?probe=3ef24a5b48) | Sep 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [4715a2425e](https://linux-hardware.org/?probe=4715a2425e) | Sep 12, 2023 |
| Apple         | MacBookPro9,2               | [77db8877eb](https://linux-hardware.org/?probe=77db8877eb) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [564a2ea72e](https://linux-hardware.org/?probe=564a2ea72e) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [58b852c7cb](https://linux-hardware.org/?probe=58b852c7cb) | Sep 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [10ff64dcf5](https://linux-hardware.org/?probe=10ff64dcf5) | Sep 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [f018495b81](https://linux-hardware.org/?probe=f018495b81) | Sep 12, 2023 |
| HP            | Laptop 15-dy5xxx            | [20ff9ece53](https://linux-hardware.org/?probe=20ff9ece53) | Sep 12, 2023 |
| Lenovo        | G770 20089                  | [39c8088b09](https://linux-hardware.org/?probe=39c8088b09) | Sep 12, 2023 |
| Apple         | MacBookAir6,2               | [e71b5644ea](https://linux-hardware.org/?probe=e71b5644ea) | Sep 12, 2023 |
| Dell          | XPS L521X                   | [d9e9a65142](https://linux-hardware.org/?probe=d9e9a65142) | Sep 12, 2023 |
| Positivo      | S14CT01                     | [57ed555d4b](https://linux-hardware.org/?probe=57ed555d4b) | Sep 11, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [84f6190c40](https://linux-hardware.org/?probe=84f6190c40) | Sep 11, 2023 |
| HUAWEI        | MACHC-WAX9                  | [3cafef18bf](https://linux-hardware.org/?probe=3cafef18bf) | Sep 11, 2023 |
| Dell          | XPS L322X                   | [77135f7967](https://linux-hardware.org/?probe=77135f7967) | Sep 11, 2023 |
| Dell          | Inspiron M5010              | [70147b0015](https://linux-hardware.org/?probe=70147b0015) | Sep 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d4178bc91c](https://linux-hardware.org/?probe=d4178bc91c) | Sep 11, 2023 |
| HP            | ProBook 645 G1              | [ced1631b20](https://linux-hardware.org/?probe=ced1631b20) | Sep 11, 2023 |
| ASUSTek       | X505BA                      | [cbb45a815f](https://linux-hardware.org/?probe=cbb45a815f) | Sep 11, 2023 |
| Dell          | XPS L322X                   | [fdf4ba47e1](https://linux-hardware.org/?probe=fdf4ba47e1) | Sep 11, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [92762d264f](https://linux-hardware.org/?probe=92762d264f) | Sep 11, 2023 |
| HP            | EliteBook 2570p             | [6259de24be](https://linux-hardware.org/?probe=6259de24be) | Sep 11, 2023 |
| Samsung       | 530XBB                      | [f6039477c2](https://linux-hardware.org/?probe=f6039477c2) | Sep 11, 2023 |
| Dell          | Inspiron 7548               | [0259762efc](https://linux-hardware.org/?probe=0259762efc) | Sep 11, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | [38a80416eb](https://linux-hardware.org/?probe=38a80416eb) | Sep 10, 2023 |
| HP            | ProBook 645 G1              | [e78c297114](https://linux-hardware.org/?probe=e78c297114) | Sep 10, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6RF0... | [6c62d111db](https://linux-hardware.org/?probe=6c62d111db) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | [8dc4477486](https://linux-hardware.org/?probe=8dc4477486) | Sep 10, 2023 |
| Acer          | Aspire 5742G                | [e737851117](https://linux-hardware.org/?probe=e737851117) | Sep 10, 2023 |
| Apple         | MacBookPro8,1               | [d3b821a061](https://linux-hardware.org/?probe=d3b821a061) | Sep 10, 2023 |
| MSI           | Modern 14 A10M              | [c78162f5fd](https://linux-hardware.org/?probe=c78162f5fd) | Sep 10, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [30fd7bf070](https://linux-hardware.org/?probe=30fd7bf070) | Sep 10, 2023 |
| Dell          | Latitude E6400              | [b0943a149a](https://linux-hardware.org/?probe=b0943a149a) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | [45261be082](https://linux-hardware.org/?probe=45261be082) | Sep 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8b6b039242](https://linux-hardware.org/?probe=8b6b039242) | Sep 10, 2023 |
| Apple         | MacBookPro13,3              | [225a9ae1c5](https://linux-hardware.org/?probe=225a9ae1c5) | Sep 10, 2023 |
| HP            | Laptop 14-ck0xxx            | [8c5abbf5a2](https://linux-hardware.org/?probe=8c5abbf5a2) | Sep 10, 2023 |
| Packard Be... | EasyNote TK85               | [4dfd50fada](https://linux-hardware.org/?probe=4dfd50fada) | Sep 10, 2023 |
| Apple         | MacBookPro8,1               | [69a1a556e0](https://linux-hardware.org/?probe=69a1a556e0) | Sep 09, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [64ea9bc56d](https://linux-hardware.org/?probe=64ea9bc56d) | Sep 09, 2023 |
| Dell          | XPS 13 9310                 | [f898a390e2](https://linux-hardware.org/?probe=f898a390e2) | Sep 09, 2023 |
| Acer          | Aspire 5745G                | [0528523e15](https://linux-hardware.org/?probe=0528523e15) | Sep 09, 2023 |
| Acer          | Aspire A715-51G             | [25649c8a92](https://linux-hardware.org/?probe=25649c8a92) | Sep 09, 2023 |
| Dell          | Inspiron 15-3552            | [eaf6dbaf3e](https://linux-hardware.org/?probe=eaf6dbaf3e) | Sep 09, 2023 |
| Acer          | Predator PH16-71            | [f0b0cc7736](https://linux-hardware.org/?probe=f0b0cc7736) | Sep 09, 2023 |
| Apple         | MacBookPro11,1              | [bc1887667f](https://linux-hardware.org/?probe=bc1887667f) | Sep 09, 2023 |
| Apple         | MacBookPro11,1              | [2da701e211](https://linux-hardware.org/?probe=2da701e211) | Sep 09, 2023 |
| Dell          | Inspiron 1545               | [95d13f26f0](https://linux-hardware.org/?probe=95d13f26f0) | Sep 09, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21CK... | [ec08aee6ff](https://linux-hardware.org/?probe=ec08aee6ff) | Sep 09, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [aa6e5c75fc](https://linux-hardware.org/?probe=aa6e5c75fc) | Sep 09, 2023 |
| Lenovo        | Flex 2-14 20404             | [139a93ab8b](https://linux-hardware.org/?probe=139a93ab8b) | Sep 09, 2023 |
| HUAWEI        | KLVL-WXX9                   | [ff8e50a7ea](https://linux-hardware.org/?probe=ff8e50a7ea) | Sep 08, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [a7026388f3](https://linux-hardware.org/?probe=a7026388f3) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | [7c5a19bc69](https://linux-hardware.org/?probe=7c5a19bc69) | Sep 08, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | [6ea0b6ed9f](https://linux-hardware.org/?probe=6ea0b6ed9f) | Sep 08, 2023 |
| HP            | 630                         | [11393e1391](https://linux-hardware.org/?probe=11393e1391) | Sep 08, 2023 |
| Lenovo        | ThinkPad E14 20RA001BUK     | [6bd319be4e](https://linux-hardware.org/?probe=6bd319be4e) | Sep 08, 2023 |
| Dell          | Inspiron 3543               | [74e5f6b8a5](https://linux-hardware.org/?probe=74e5f6b8a5) | Sep 08, 2023 |
| Dell          | Inspiron 3543               | [d4df00af33](https://linux-hardware.org/?probe=d4df00af33) | Sep 08, 2023 |
| Unknown       | W1415A                      | [67fc8d5ea8](https://linux-hardware.org/?probe=67fc8d5ea8) | Sep 08, 2023 |
| Acer          | Predator PH315-51           | [89e33145c3](https://linux-hardware.org/?probe=89e33145c3) | Sep 08, 2023 |
| Sony          | SVE14A25CLW                 | [9646f55c7d](https://linux-hardware.org/?probe=9646f55c7d) | Sep 08, 2023 |
| Sony          | SVE14A25CLW                 | [3f8a5dcaaf](https://linux-hardware.org/?probe=3f8a5dcaaf) | Sep 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [0de4c341fa](https://linux-hardware.org/?probe=0de4c341fa) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [89772ef854](https://linux-hardware.org/?probe=89772ef854) | Sep 07, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [c9ea6ff204](https://linux-hardware.org/?probe=c9ea6ff204) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | [f2df6b2c70](https://linux-hardware.org/?probe=f2df6b2c70) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | [e39cb4e3e6](https://linux-hardware.org/?probe=e39cb4e3e6) | Sep 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [69fc5aab82](https://linux-hardware.org/?probe=69fc5aab82) | Sep 07, 2023 |
| Lenovo        | V580c 20160                 | [87f8bad27d](https://linux-hardware.org/?probe=87f8bad27d) | Sep 07, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [384d2074ad](https://linux-hardware.org/?probe=384d2074ad) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-15API 81UT     | [8a05090057](https://linux-hardware.org/?probe=8a05090057) | Sep 07, 2023 |
| Acer          | Aspire V5-531               | [63fd300645](https://linux-hardware.org/?probe=63fd300645) | Sep 07, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [a2fab791b4](https://linux-hardware.org/?probe=a2fab791b4) | Sep 07, 2023 |
| Timi          | Redmi Book Pro 14S          | [b2776d8282](https://linux-hardware.org/?probe=b2776d8282) | Sep 07, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [24eca3030c](https://linux-hardware.org/?probe=24eca3030c) | Sep 07, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [da7303433d](https://linux-hardware.org/?probe=da7303433d) | Sep 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [9911fc5254](https://linux-hardware.org/?probe=9911fc5254) | Sep 07, 2023 |
| MSI           | Bravo 17 A4DDR              | [2592f883ef](https://linux-hardware.org/?probe=2592f883ef) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b982251e82](https://linux-hardware.org/?probe=b982251e82) | Sep 07, 2023 |
| Dell          | Latitude E6500              | [b4b035c4f7](https://linux-hardware.org/?probe=b4b035c4f7) | Sep 07, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [3c6e29c3c3](https://linux-hardware.org/?probe=3c6e29c3c3) | Sep 06, 2023 |
| GPU Compan... | GWNR71517                   | [b6a521128f](https://linux-hardware.org/?probe=b6a521128f) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | [f59dbec9af](https://linux-hardware.org/?probe=f59dbec9af) | Sep 06, 2023 |
| Samsung       | 550P5C/550P7C               | [83c77f6733](https://linux-hardware.org/?probe=83c77f6733) | Sep 06, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [c8ee0a00a5](https://linux-hardware.org/?probe=c8ee0a00a5) | Sep 06, 2023 |
| Dell          | XPS 13 9310                 | [7e81f7531b](https://linux-hardware.org/?probe=7e81f7531b) | Sep 06, 2023 |
| Lenovo        | ThinkPad P1 Gen 6 21FV00... | [c9a07c44d5](https://linux-hardware.org/?probe=c9a07c44d5) | Sep 06, 2023 |
| Dell          | Inspiron 3542               | [1756563167](https://linux-hardware.org/?probe=1756563167) | Sep 06, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [f946665a24](https://linux-hardware.org/?probe=f946665a24) | Sep 06, 2023 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [b5f142ae13](https://linux-hardware.org/?probe=b5f142ae13) | Sep 06, 2023 |
| Apple         | MacBookPro13,1              | [d6b6455af2](https://linux-hardware.org/?probe=d6b6455af2) | Sep 06, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | [c31e15f2ba](https://linux-hardware.org/?probe=c31e15f2ba) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | [25ec8e4a16](https://linux-hardware.org/?probe=25ec8e4a16) | Sep 05, 2023 |
| Dell          | Latitude 7400               | [e1ea4eb614](https://linux-hardware.org/?probe=e1ea4eb614) | Sep 05, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | [bb7f6aed1a](https://linux-hardware.org/?probe=bb7f6aed1a) | Sep 05, 2023 |
| ASUSTek       | E402SA                      | [efad2958a0](https://linux-hardware.org/?probe=efad2958a0) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [3c55d4d55b](https://linux-hardware.org/?probe=3c55d4d55b) | Sep 05, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [0309bcca29](https://linux-hardware.org/?probe=0309bcca29) | Sep 05, 2023 |
| Dell          | Latitude 7490               | [c03e42edee](https://linux-hardware.org/?probe=c03e42edee) | Sep 05, 2023 |
| Unknown       | Unknown                     | [9b4d95cf35](https://linux-hardware.org/?probe=9b4d95cf35) | Sep 05, 2023 |
| Apple         | MacBookPro9,2               | [424ab4dc3d](https://linux-hardware.org/?probe=424ab4dc3d) | Sep 05, 2023 |
| HP            | ProBook 450 G8 Notebook ... | [5dbf7515d1](https://linux-hardware.org/?probe=5dbf7515d1) | Sep 05, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [7619d8e5e8](https://linux-hardware.org/?probe=7619d8e5e8) | Sep 05, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [ea1d0861a1](https://linux-hardware.org/?probe=ea1d0861a1) | Sep 05, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [229ca6e8cb](https://linux-hardware.org/?probe=229ca6e8cb) | Sep 05, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [ab9c556dc7](https://linux-hardware.org/?probe=ab9c556dc7) | Sep 05, 2023 |
| Acer          | Aspire 4738Z                | [88b34596c0](https://linux-hardware.org/?probe=88b34596c0) | Sep 05, 2023 |
| Dell          | XPS 13 7390                 | [5154be8883](https://linux-hardware.org/?probe=5154be8883) | Sep 05, 2023 |
| Dell          | G15 5530                    | [91dcc569ee](https://linux-hardware.org/?probe=91dcc569ee) | Sep 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | [d3cde5f4c5](https://linux-hardware.org/?probe=d3cde5f4c5) | Sep 04, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [2a53f8dc55](https://linux-hardware.org/?probe=2a53f8dc55) | Sep 04, 2023 |
| Dell          | Inspiron 3576               | [5139d104cc](https://linux-hardware.org/?probe=5139d104cc) | Sep 04, 2023 |
| Acer          | Aspire E1-571               | [032fca9d1d](https://linux-hardware.org/?probe=032fca9d1d) | Sep 04, 2023 |
| HP            | Laptop 14s-dq2xxx           | [3a5b200954](https://linux-hardware.org/?probe=3a5b200954) | Sep 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QE... | [da42098f81](https://linux-hardware.org/?probe=da42098f81) | Sep 04, 2023 |
| Dell          | XPS 13 9380                 | [94e7b43fe2](https://linux-hardware.org/?probe=94e7b43fe2) | Sep 04, 2023 |
| HP            | Laptop 15-dw2xxx            | [fff758a5d9](https://linux-hardware.org/?probe=fff758a5d9) | Sep 04, 2023 |
| Chuwi         | GemiBook                    | [cfdc48e9f6](https://linux-hardware.org/?probe=cfdc48e9f6) | Sep 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1d6a4b4279](https://linux-hardware.org/?probe=1d6a4b4279) | Sep 04, 2023 |
| Dell          | Latitude 5285               | [9ddc47c6a9](https://linux-hardware.org/?probe=9ddc47c6a9) | Sep 04, 2023 |
| Maibenben     | MaiBook M                   | [7189994067](https://linux-hardware.org/?probe=7189994067) | Sep 04, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [18d1abc9ca](https://linux-hardware.org/?probe=18d1abc9ca) | Sep 04, 2023 |
| HUAWEI        | KLVL-WXX9                   | [c3e4035d47](https://linux-hardware.org/?probe=c3e4035d47) | Sep 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1211fca3e2](https://linux-hardware.org/?probe=1211fca3e2) | Sep 03, 2023 |
| Notebook      | PCx0Dx                      | [89d5a9b606](https://linux-hardware.org/?probe=89d5a9b606) | Sep 03, 2023 |
| Lenovo        | ThinkPad T550 20CKA00ECD    | [20be702d65](https://linux-hardware.org/?probe=20be702d65) | Sep 03, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [2973871c04](https://linux-hardware.org/?probe=2973871c04) | Sep 03, 2023 |
| HP            | Pavilion Gaming Laptop      | [733f5cb987](https://linux-hardware.org/?probe=733f5cb987) | Sep 03, 2023 |
| Framework     | Laptop                      | [d153316fdd](https://linux-hardware.org/?probe=d153316fdd) | Sep 03, 2023 |
| Dell          | Latitude 3540               | [e7d1d4f160](https://linux-hardware.org/?probe=e7d1d4f160) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [e0f8242693](https://linux-hardware.org/?probe=e0f8242693) | Sep 02, 2023 |
| Lenovo        | Legion Slim 5 16IRH8 82Y... | [8f29742c47](https://linux-hardware.org/?probe=8f29742c47) | Sep 02, 2023 |
| ASUSTek       | X540NA                      | [69ccd7d6f2](https://linux-hardware.org/?probe=69ccd7d6f2) | Sep 02, 2023 |
| Dell          | Latitude 5400               | [aac8791780](https://linux-hardware.org/?probe=aac8791780) | Sep 02, 2023 |
| Lenovo        | 14w Gen 2 82N9              | [87c8a118b5](https://linux-hardware.org/?probe=87c8a118b5) | Sep 02, 2023 |
| Prestigio     | Multipad Visconte V         | [3c60fe1d14](https://linux-hardware.org/?probe=3c60fe1d14) | Sep 01, 2023 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [3080550241](https://linux-hardware.org/?probe=3080550241) | Sep 01, 2023 |
| Fujitsu       | LIFEBOOK S760               | [b7439f4404](https://linux-hardware.org/?probe=b7439f4404) | Sep 01, 2023 |
| Timi          | Mi NoteBook Pro             | [7d3823ff94](https://linux-hardware.org/?probe=7d3823ff94) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | [864a10779f](https://linux-hardware.org/?probe=864a10779f) | Sep 01, 2023 |
| HP            | EliteBook 820 G3            | [24d0eafc15](https://linux-hardware.org/?probe=24d0eafc15) | Sep 01, 2023 |
| Apple         | MacBookAir5,2               | [bda3b1837c](https://linux-hardware.org/?probe=bda3b1837c) | Sep 01, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [edd00c35fd](https://linux-hardware.org/?probe=edd00c35fd) | Sep 01, 2023 |
| Apple         | MacBookAir4,1               | [61da3436a8](https://linux-hardware.org/?probe=61da3436a8) | Sep 01, 2023 |
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [239b46961f](https://linux-hardware.org/?probe=239b46961f) | Sep 01, 2023 |
| Lenovo        | ThinkPad X270 20HMS6AT00    | [e111bad271](https://linux-hardware.org/?probe=e111bad271) | Sep 01, 2023 |
| HP            | EliteBook 860 16 inch G9... | [5e0da96bdd](https://linux-hardware.org/?probe=5e0da96bdd) | Sep 01, 2023 |
| Dell          | Latitude 5290 2-in-1        | [3a4c0e0930](https://linux-hardware.org/?probe=3a4c0e0930) | Aug 31, 2023 |
| Apple         | MacBook9,1                  | [b6a28c1e1a](https://linux-hardware.org/?probe=b6a28c1e1a) | Aug 31, 2023 |
| Dell          | Latitude 5290 2-in-1        | [5b632410e7](https://linux-hardware.org/?probe=5b632410e7) | Aug 31, 2023 |
| ASUSTek       | ASUS EXPERTBOOK L2402CYA... | [9881dd3268](https://linux-hardware.org/?probe=9881dd3268) | Aug 31, 2023 |
| Lenovo        | ThinkPad L470 20J40010GE    | [53adc42d66](https://linux-hardware.org/?probe=53adc42d66) | Aug 31, 2023 |
| Dell          | Latitude 5590               | [59d99ec581](https://linux-hardware.org/?probe=59d99ec581) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [c3d8f5daca](https://linux-hardware.org/?probe=c3d8f5daca) | Aug 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS0LR00    | [a85743e60e](https://linux-hardware.org/?probe=a85743e60e) | Aug 31, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [f94ed7f5d1](https://linux-hardware.org/?probe=f94ed7f5d1) | Aug 31, 2023 |
| System76      | Lemur Pro                   | [c04af9751f](https://linux-hardware.org/?probe=c04af9751f) | Aug 31, 2023 |
| Apple         | MacBookPro15,2              | [a93751de6d](https://linux-hardware.org/?probe=a93751de6d) | Aug 30, 2023 |
| HP            | ProBook 440 14 inch G9 N... | [b37cf7f8cf](https://linux-hardware.org/?probe=b37cf7f8cf) | Aug 30, 2023 |
| HP            | EliteBook 845 14 inch G9... | [4c595a576a](https://linux-hardware.org/?probe=4c595a576a) | Aug 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [78e163bc13](https://linux-hardware.org/?probe=78e163bc13) | Aug 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [0842215d23](https://linux-hardware.org/?probe=0842215d23) | Aug 30, 2023 |
| Acer          | TravelMate P259-MG          | [dc9b122d90](https://linux-hardware.org/?probe=dc9b122d90) | Aug 30, 2023 |
| Dell          | Latitude 5430               | [477898be1f](https://linux-hardware.org/?probe=477898be1f) | Aug 30, 2023 |
| Dell          | Vostro 2520                 | [73ca89b4fa](https://linux-hardware.org/?probe=73ca89b4fa) | Aug 30, 2023 |
| HP            | Laptop 17-by0xxx            | [4617fe766a](https://linux-hardware.org/?probe=4617fe766a) | Aug 29, 2023 |
| Dell          | Latitude 5480               | [88c6621b31](https://linux-hardware.org/?probe=88c6621b31) | Aug 29, 2023 |
| Dell          | Precision 5480              | [5fd5bf187d](https://linux-hardware.org/?probe=5fd5bf187d) | Aug 29, 2023 |
| Lenovo        | ThinkBook 14 G4+ IAP 21C... | [0eeb1276f0](https://linux-hardware.org/?probe=0eeb1276f0) | Aug 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d036282290](https://linux-hardware.org/?probe=d036282290) | Aug 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [7e48b59643](https://linux-hardware.org/?probe=7e48b59643) | Aug 29, 2023 |
| Timi          | A34S                        | [eb6a3c2430](https://linux-hardware.org/?probe=eb6a3c2430) | Aug 29, 2023 |
| Acer          | Aspire E1-571               | [3208c59e9c](https://linux-hardware.org/?probe=3208c59e9c) | Aug 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d627b8c625](https://linux-hardware.org/?probe=d627b8c625) | Aug 28, 2023 |
| Dell          | XPS 15 9510                 | [4b78bfab47](https://linux-hardware.org/?probe=4b78bfab47) | Aug 28, 2023 |
| Dell          | Latitude E6400              | [2af0a423ef](https://linux-hardware.org/?probe=2af0a423ef) | Aug 28, 2023 |
| Dell          | XPS 15 9560                 | [8288d35dff](https://linux-hardware.org/?probe=8288d35dff) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5fddb9cc18](https://linux-hardware.org/?probe=5fddb9cc18) | Aug 28, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [a762e96941](https://linux-hardware.org/?probe=a762e96941) | Aug 28, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | [40c64b6ec2](https://linux-hardware.org/?probe=40c64b6ec2) | Aug 28, 2023 |
| Acer          | Nitro AN515-57              | [7608fab281](https://linux-hardware.org/?probe=7608fab281) | Aug 28, 2023 |
| Lenovo        | IdeaPad 1 14IAU7 82QC       | [90e0cad295](https://linux-hardware.org/?probe=90e0cad295) | Aug 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [da73419cb5](https://linux-hardware.org/?probe=da73419cb5) | Aug 27, 2023 |
| Framework     | Laptop                      | [b3e9d2d48d](https://linux-hardware.org/?probe=b3e9d2d48d) | Aug 27, 2023 |
| Corsair       | Voyager a1600               | [405bce7897](https://linux-hardware.org/?probe=405bce7897) | Aug 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8acc158836](https://linux-hardware.org/?probe=8acc158836) | Aug 27, 2023 |
| HP            | Laptop 15s-eq2xxx           | [864a9d9f37](https://linux-hardware.org/?probe=864a9d9f37) | Aug 27, 2023 |
| ASUSTek       | T100TA                      | [69d14b429e](https://linux-hardware.org/?probe=69d14b429e) | Aug 27, 2023 |
| Dell          | Latitude E6400              | [fdcbc50452](https://linux-hardware.org/?probe=fdcbc50452) | Aug 27, 2023 |
| ASUSTek       | GL753VD                     | [3903bc9e14](https://linux-hardware.org/?probe=3903bc9e14) | Aug 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDC... | [fe02fb8d64](https://linux-hardware.org/?probe=fe02fb8d64) | Aug 27, 2023 |
| Timi          | TM1701                      | [2a6a4225a0](https://linux-hardware.org/?probe=2a6a4225a0) | Aug 27, 2023 |
| Timi          | TM1701                      | [8ea7c21e18](https://linux-hardware.org/?probe=8ea7c21e18) | Aug 27, 2023 |
| HP            | Pavilion 15                 | [1731ba4ae5](https://linux-hardware.org/?probe=1731ba4ae5) | Aug 27, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [5d220003c1](https://linux-hardware.org/?probe=5d220003c1) | Aug 27, 2023 |
| HP            | Pavilion 15                 | [0f51268684](https://linux-hardware.org/?probe=0f51268684) | Aug 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a8600db157](https://linux-hardware.org/?probe=a8600db157) | Aug 27, 2023 |
| ASUSTek       | K55VD                       | [7bdfc94045](https://linux-hardware.org/?probe=7bdfc94045) | Aug 27, 2023 |
| Lenovo        | IdeaPad Z570 1024DCU        | [8a11757d37](https://linux-hardware.org/?probe=8a11757d37) | Aug 26, 2023 |
| Corsair       | Voyager a1600               | [97a1c576f7](https://linux-hardware.org/?probe=97a1c576f7) | Aug 26, 2023 |
| Lenovo        | ThinkBook 14 G4 IAP 21DH    | [4e5f7a05c6](https://linux-hardware.org/?probe=4e5f7a05c6) | Aug 26, 2023 |
| ASUSTek       | Strix 17 GL703GE            | [b2ad72336f](https://linux-hardware.org/?probe=b2ad72336f) | Aug 26, 2023 |
| HP            | OMEN by Laptop              | [df71a92503](https://linux-hardware.org/?probe=df71a92503) | Aug 26, 2023 |
| Acer          | Aspire A715-72G             | [cbbaecabb1](https://linux-hardware.org/?probe=cbbaecabb1) | Aug 26, 2023 |
| ASUSTek       | X542BP                      | [58cc535a58](https://linux-hardware.org/?probe=58cc535a58) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [95548b426e](https://linux-hardware.org/?probe=95548b426e) | Aug 26, 2023 |
| Chuwi         | CoreBook X                  | [6bd0ecde29](https://linux-hardware.org/?probe=6bd0ecde29) | Aug 26, 2023 |
| Acer          | Predator PH16-71            | [ef267bc627](https://linux-hardware.org/?probe=ef267bc627) | Aug 26, 2023 |
| Apple         | MacBookPro13,2              | [b910d52198](https://linux-hardware.org/?probe=b910d52198) | Aug 26, 2023 |
| Lenovo        | ThinkPad E520 1143CWG       | [66d9a31686](https://linux-hardware.org/?probe=66d9a31686) | Aug 25, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | [6e84e686ec](https://linux-hardware.org/?probe=6e84e686ec) | Aug 25, 2023 |
| Acer          | Nitro AN515-44              | [b14dfb0798](https://linux-hardware.org/?probe=b14dfb0798) | Aug 25, 2023 |
| Acer          | Aspire ES1-512              | [22187e6de0](https://linux-hardware.org/?probe=22187e6de0) | Aug 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [810ccd6f4f](https://linux-hardware.org/?probe=810ccd6f4f) | Aug 25, 2023 |
| Dell          | Inspiron 5585               | [49a9e7dbf0](https://linux-hardware.org/?probe=49a9e7dbf0) | Aug 25, 2023 |
| Dell          | Latitude 3490               | [05705b1834](https://linux-hardware.org/?probe=05705b1834) | Aug 25, 2023 |
| ASUSTek       | T100TA                      | [ef7b263d48](https://linux-hardware.org/?probe=ef7b263d48) | Aug 25, 2023 |
| Toshiba       | Satellite C70-B             | [2647e2edd8](https://linux-hardware.org/?probe=2647e2edd8) | Aug 24, 2023 |
| Dell          | G15 5510                    | [f9e857e751](https://linux-hardware.org/?probe=f9e857e751) | Aug 24, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [7e6a7de337](https://linux-hardware.org/?probe=7e6a7de337) | Aug 24, 2023 |
| Sony          | SVF15A1M2ES                 | [b352453232](https://linux-hardware.org/?probe=b352453232) | Aug 24, 2023 |
| Dell          | Inspiron 5759               | [bf7413fc5f](https://linux-hardware.org/?probe=bf7413fc5f) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [1a9c135840](https://linux-hardware.org/?probe=1a9c135840) | Aug 24, 2023 |
| LDLC          | SPC-I                       | [bb114215e6](https://linux-hardware.org/?probe=bb114215e6) | Aug 24, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | [5f18850003](https://linux-hardware.org/?probe=5f18850003) | Aug 24, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | [de37c3c7eb](https://linux-hardware.org/?probe=de37c3c7eb) | Aug 24, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [ce5f964a0c](https://linux-hardware.org/?probe=ce5f964a0c) | Aug 24, 2023 |
| Dell          | Latitude 3490               | [148d4806cb](https://linux-hardware.org/?probe=148d4806cb) | Aug 24, 2023 |
| HP            | 255 G8 Notebook PC          | [68c01672c3](https://linux-hardware.org/?probe=68c01672c3) | Aug 24, 2023 |
| Xplore        | iX104C6                     | [5d8ea1a454](https://linux-hardware.org/?probe=5d8ea1a454) | Aug 24, 2023 |
| Lenovo        | Yoga710-14ISK 80TY          | [17525a9aef](https://linux-hardware.org/?probe=17525a9aef) | Aug 24, 2023 |
| Positivo B... | VJFE59F11X-B0411H           | [5e5059f835](https://linux-hardware.org/?probe=5e5059f835) | Aug 23, 2023 |
| ASUSTek       | X540UP                      | [7041925c33](https://linux-hardware.org/?probe=7041925c33) | Aug 23, 2023 |
| Lenovo        | ThinkPad X200 74591P0       | [adda6295fb](https://linux-hardware.org/?probe=adda6295fb) | Aug 23, 2023 |
| Acer          | Predator PT715-51           | [e187e199c9](https://linux-hardware.org/?probe=e187e199c9) | Aug 23, 2023 |
| Dell          | XPS 15 7590                 | [66b46e04d3](https://linux-hardware.org/?probe=66b46e04d3) | Aug 23, 2023 |
| Google        | Nami                        | [db2c6bfb0a](https://linux-hardware.org/?probe=db2c6bfb0a) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [08801db21d](https://linux-hardware.org/?probe=08801db21d) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [9b3cf2a525](https://linux-hardware.org/?probe=9b3cf2a525) | Aug 23, 2023 |
| Toshiba       | Satellite L515              | [fa5d7d5547](https://linux-hardware.org/?probe=fa5d7d5547) | Aug 23, 2023 |
| Lenovo        | Legion Y9000P IAH7H 82RF    | [f429d18938](https://linux-hardware.org/?probe=f429d18938) | Aug 23, 2023 |
| Dell          | Inspiron 5559               | [310e1f561c](https://linux-hardware.org/?probe=310e1f561c) | Aug 22, 2023 |
| HUAWEI        | BOHB-WAX9                   | [f7580a556b](https://linux-hardware.org/?probe=f7580a556b) | Aug 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [68d28831a5](https://linux-hardware.org/?probe=68d28831a5) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [25d163ad9e](https://linux-hardware.org/?probe=25d163ad9e) | Aug 22, 2023 |
| Google        | Nami                        | [69d8c7bfb8](https://linux-hardware.org/?probe=69d8c7bfb8) | Aug 22, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [9ad109a4df](https://linux-hardware.org/?probe=9ad109a4df) | Aug 22, 2023 |
| HP            | Pavilion 11 x360 PC         | [bf401f98a7](https://linux-hardware.org/?probe=bf401f98a7) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [f35c644052](https://linux-hardware.org/?probe=f35c644052) | Aug 22, 2023 |
| HP            | EliteBook 8440p             | [4f4bed768e](https://linux-hardware.org/?probe=4f4bed768e) | Aug 22, 2023 |
| Dell          | Latitude 7430               | [1ccbb8329f](https://linux-hardware.org/?probe=1ccbb8329f) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | [39dbb86112](https://linux-hardware.org/?probe=39dbb86112) | Aug 22, 2023 |
| HP            | ProBook 655 G1              | [2d616412f1](https://linux-hardware.org/?probe=2d616412f1) | Aug 22, 2023 |
| Dell          | Inspiron 5567               | [76c16d7ffe](https://linux-hardware.org/?probe=76c16d7ffe) | Aug 22, 2023 |
| HUAWEI        | HVY-WXX9                    | [55e95b21f1](https://linux-hardware.org/?probe=55e95b21f1) | Aug 22, 2023 |
| HP            | Laptop 15-fc0xxx            | [d2378787ac](https://linux-hardware.org/?probe=d2378787ac) | Aug 21, 2023 |
| Dell          | Latitude 3301               | [69389fff09](https://linux-hardware.org/?probe=69389fff09) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | [63b37fd7f7](https://linux-hardware.org/?probe=63b37fd7f7) | Aug 21, 2023 |
| Lenovo        | ThinkPad T430 2347C32       | [6956f76011](https://linux-hardware.org/?probe=6956f76011) | Aug 21, 2023 |
| Dell          | Inspiron 5547               | [b5b7a6d8f8](https://linux-hardware.org/?probe=b5b7a6d8f8) | Aug 21, 2023 |
| MSI           | GE63 Raider RGB 8RF         | [dd12e382c8](https://linux-hardware.org/?probe=dd12e382c8) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713IE_G713IE     | [22443858cb](https://linux-hardware.org/?probe=22443858cb) | Aug 21, 2023 |
| Apple         | MacBookPro9,2               | [a8a1e5df49](https://linux-hardware.org/?probe=a8a1e5df49) | Aug 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [359cd5a655](https://linux-hardware.org/?probe=359cd5a655) | Aug 21, 2023 |
| Dell          | Latitude 7490               | [90685f1b4d](https://linux-hardware.org/?probe=90685f1b4d) | Aug 21, 2023 |
| Lenovo        | Legion 5 82B5               | [6047cef31c](https://linux-hardware.org/?probe=6047cef31c) | Aug 21, 2023 |
| Lenovo        | Legion 5 82B5               | [986599dc77](https://linux-hardware.org/?probe=986599dc77) | Aug 21, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [c1a5eb75bf](https://linux-hardware.org/?probe=c1a5eb75bf) | Aug 21, 2023 |
| ASUSTek       | X510URR                     | [d1ee285db9](https://linux-hardware.org/?probe=d1ee285db9) | Aug 21, 2023 |
| HP            | ProBook 640 G1              | [f38ba797d9](https://linux-hardware.org/?probe=f38ba797d9) | Aug 21, 2023 |
| HP            | EliteBook 840 G6            | [9fa60a1eba](https://linux-hardware.org/?probe=9fa60a1eba) | Aug 21, 2023 |
| Toshiba       | Satellite C70-B             | [d4f90e5eff](https://linux-hardware.org/?probe=d4f90e5eff) | Aug 21, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [5fa4b8ae13](https://linux-hardware.org/?probe=5fa4b8ae13) | Aug 20, 2023 |
| HP            | ProBook 430 G1              | [24a2760d65](https://linux-hardware.org/?probe=24a2760d65) | Aug 20, 2023 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [448603376e](https://linux-hardware.org/?probe=448603376e) | Aug 20, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [8e91f085b4](https://linux-hardware.org/?probe=8e91f085b4) | Aug 20, 2023 |
| Acer          | Aspire A315-53              | [03bd8885a0](https://linux-hardware.org/?probe=03bd8885a0) | Aug 20, 2023 |
| HP            | Laptop 15s-eq2xxx           | [34f09bffb0](https://linux-hardware.org/?probe=34f09bffb0) | Aug 20, 2023 |
| PC Special... | Ionico 16                   | [96fb68dc70](https://linux-hardware.org/?probe=96fb68dc70) | Aug 20, 2023 |
| Sony          | SVF1521USTW                 | [ce7fbec260](https://linux-hardware.org/?probe=ce7fbec260) | Aug 20, 2023 |
| Sony          | SVF1521USTW                 | [e92fad444f](https://linux-hardware.org/?probe=e92fad444f) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [36417c2601](https://linux-hardware.org/?probe=36417c2601) | Aug 19, 2023 |
| Lenovo        | ThinkPad SL510 28477MG      | [ed572b9b04](https://linux-hardware.org/?probe=ed572b9b04) | Aug 19, 2023 |
| Packard Be... | EasyNote ENTF71BM           | [81dd9b9a7a](https://linux-hardware.org/?probe=81dd9b9a7a) | Aug 19, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [651f263a9d](https://linux-hardware.org/?probe=651f263a9d) | Aug 19, 2023 |
| HUAWEI        | NBM-WXX9                    | [ac85dd7bb4](https://linux-hardware.org/?probe=ac85dd7bb4) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | [c6f3f044c9](https://linux-hardware.org/?probe=c6f3f044c9) | Aug 19, 2023 |
| Acer          | Swift SF114-32              | [9734816ff1](https://linux-hardware.org/?probe=9734816ff1) | Aug 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [80b304814d](https://linux-hardware.org/?probe=80b304814d) | Aug 19, 2023 |
| HP            | Pavilion dv4                | [5f1e0c4484](https://linux-hardware.org/?probe=5f1e0c4484) | Aug 19, 2023 |
| Acer          | Aspire A514-55              | [98ebe4bf9a](https://linux-hardware.org/?probe=98ebe4bf9a) | Aug 19, 2023 |
| Dell          | Inspiron 7520               | [3cdfdae368](https://linux-hardware.org/?probe=3cdfdae368) | Aug 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dee14abe77](https://linux-hardware.org/?probe=dee14abe77) | Aug 18, 2023 |
| Acer          | Aspire A514-55              | [cace7d6efb](https://linux-hardware.org/?probe=cace7d6efb) | Aug 18, 2023 |
| Lenovo        | IdeaPad Slim 3 15ABR8 82... | [12c6ae9006](https://linux-hardware.org/?probe=12c6ae9006) | Aug 18, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [f7d0bbc3d9](https://linux-hardware.org/?probe=f7d0bbc3d9) | Aug 18, 2023 |
| Lenovo        | IdeaPad 320-17ISK 80XJ      | [c9e9e56ddd](https://linux-hardware.org/?probe=c9e9e56ddd) | Aug 18, 2023 |
| Dell          | Latitude 7320               | [a51289d9dd](https://linux-hardware.org/?probe=a51289d9dd) | Aug 18, 2023 |
| System76      | Pangolin                    | [5191e3a345](https://linux-hardware.org/?probe=5191e3a345) | Aug 18, 2023 |
| Schenker      | MEDIA (M22)                 | [463903cc03](https://linux-hardware.org/?probe=463903cc03) | Aug 18, 2023 |
| PC Special... | Ionico 16                   | [da33e8f1c1](https://linux-hardware.org/?probe=da33e8f1c1) | Aug 18, 2023 |
| MSI           | MS-1057                     | [081ae63942](https://linux-hardware.org/?probe=081ae63942) | Aug 18, 2023 |
| MSI           | MS-1057                     | [615f03f3b8](https://linux-hardware.org/?probe=615f03f3b8) | Aug 18, 2023 |
| Acer          | Aspire E5-575               | [cfbf5747b3](https://linux-hardware.org/?probe=cfbf5747b3) | Aug 18, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [b8e5fd59d3](https://linux-hardware.org/?probe=b8e5fd59d3) | Aug 18, 2023 |
| Lenovo        | ThinkPad L480 20LTS6S904    | [32ded049ec](https://linux-hardware.org/?probe=32ded049ec) | Aug 17, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [df194863d1](https://linux-hardware.org/?probe=df194863d1) | Aug 17, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | [87a6bd39ae](https://linux-hardware.org/?probe=87a6bd39ae) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [bbf57bf744](https://linux-hardware.org/?probe=bbf57bf744) | Aug 17, 2023 |
| HP            | ProBook 640 G1              | [e688e27904](https://linux-hardware.org/?probe=e688e27904) | Aug 17, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [2cd51b6fce](https://linux-hardware.org/?probe=2cd51b6fce) | Aug 17, 2023 |
| Dell          | Latitude 7440               | [e56c46e8fe](https://linux-hardware.org/?probe=e56c46e8fe) | Aug 17, 2023 |
| Dell          | Latitude 7440               | [aef57d5421](https://linux-hardware.org/?probe=aef57d5421) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d0d3c76bb8](https://linux-hardware.org/?probe=d0d3c76bb8) | Aug 17, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [c753cfdb08](https://linux-hardware.org/?probe=c753cfdb08) | Aug 17, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [75556aed08](https://linux-hardware.org/?probe=75556aed08) | Aug 16, 2023 |
| HP            | Compaq 6710b (FG040EC#AB... | [a0cd8c1b40](https://linux-hardware.org/?probe=a0cd8c1b40) | Aug 16, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [82c579f8a7](https://linux-hardware.org/?probe=82c579f8a7) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480s 20L7001VG... | [b0b2f8a7e1](https://linux-hardware.org/?probe=b0b2f8a7e1) | Aug 16, 2023 |
| Lenovo        | ThinkPad T480s 20L7001VG... | [07b5827382](https://linux-hardware.org/?probe=07b5827382) | Aug 16, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [f3c603341d](https://linux-hardware.org/?probe=f3c603341d) | Aug 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [af217ce6dc](https://linux-hardware.org/?probe=af217ce6dc) | Aug 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | [feeb3d8bbe](https://linux-hardware.org/?probe=feeb3d8bbe) | Aug 16, 2023 |
| ASUSTek       | X541NA                      | [8e3f72e46d](https://linux-hardware.org/?probe=8e3f72e46d) | Aug 16, 2023 |
| HP            | Laptop 17-ca0xxx            | [bbf606d6e8](https://linux-hardware.org/?probe=bbf606d6e8) | Aug 16, 2023 |
| Dell          | Latitude E5400              | [7d861c3812](https://linux-hardware.org/?probe=7d861c3812) | Aug 16, 2023 |
| Dell          | Latitude 5420               | [12d46be852](https://linux-hardware.org/?probe=12d46be852) | Aug 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [b326fccb63](https://linux-hardware.org/?probe=b326fccb63) | Aug 16, 2023 |
| HUAWEI        | CREM-WXX9                   | [24cd5deaa3](https://linux-hardware.org/?probe=24cd5deaa3) | Aug 16, 2023 |
| Dell          | Latitude 7490               | [efb4abea09](https://linux-hardware.org/?probe=efb4abea09) | Aug 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [ff958dc821](https://linux-hardware.org/?probe=ff958dc821) | Aug 16, 2023 |
| HUAWEI        | CREM-WXX9                   | [b42d5dec8e](https://linux-hardware.org/?probe=b42d5dec8e) | Aug 16, 2023 |

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
| Fedora 38 | 1677      | 19.69%  |
| Fedora 36 | 1238      | 14.54%  |
| Fedora 37 | 1228      | 14.42%  |
| Fedora 35 | 971       | 11.4%   |
| Fedora 34 | 939       | 11.03%  |
| Fedora 33 | 856       | 10.05%  |
| Fedora 32 | 746       | 8.76%   |
| Fedora 31 | 503       | 5.91%   |
| Fedora 30 | 163       | 1.91%   |
| Fedora 29 | 90        | 1.06%   |
| Fedora 39 | 60        | 0.7%    |
| Fedora 28 | 22        | 0.26%   |
| Fedora 27 | 8         | 0.09%   |
| Fedora 40 | 4         | 0.05%   |
| Fedora 24 | 4         | 0.05%   |
| Fedora 21 | 4         | 0.05%   |
| Fedora 25 | 2         | 0.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Fedora | 7642      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 6.2.9-300.fc38.x86_64   | 216       | 2.28%   |
| 6.2.15-300.fc38.x86_64  | 141       | 1.49%   |
| 6.3.8-200.fc38.x86_64   | 114       | 1.2%    |
| 5.17.5-300.fc36.x86_64  | 113       | 1.19%   |
| 6.4.15-200.fc38.x86_64  | 101       | 1.07%   |
| 6.0.7-301.fc37.x86_64   | 92        | 0.97%   |
| 5.16.18-200.fc35.x86_64 | 92        | 0.97%   |
| 6.2.14-300.fc38.x86_64  | 90        | 0.95%   |
| 5.9.16-200.fc33.x86_64  | 90        | 0.95%   |
| 6.5.5-200.fc38.x86_64   | 89        | 0.94%   |
| 6.2.11-300.fc38.x86_64  | 87        | 0.92%   |
| 5.11.12-300.fc34.x86_64 | 77        | 0.81%   |
| 6.0.15-300.fc37.x86_64  | 76        | 0.8%    |
| 5.14.10-300.fc35.x86_64 | 70        | 0.74%   |
| 6.0.5-200.fc36.x86_64   | 69        | 0.73%   |
| 6.3.12-200.fc38.x86_64  | 66        | 0.7%    |
| 5.8.16-300.fc33.x86_64  | 64        | 0.68%   |
| 6.5.8-200.fc38.x86_64   | 61        | 0.64%   |
| 6.1.14-200.fc37.x86_64  | 61        | 0.64%   |
| 5.18.13-200.fc36.x86_64 | 61        | 0.64%   |
| 5.8.15-301.fc33.x86_64  | 60        | 0.63%   |
| 5.8.4-200.fc32.x86_64   | 57        | 0.6%    |
| 6.1.7-200.fc37.x86_64   | 56        | 0.59%   |
| 6.0.8-300.fc37.x86_64   | 56        | 0.59%   |
| 6.4.6-200.fc38.x86_64   | 55        | 0.58%   |
| 5.13.12-200.fc34.x86_64 | 54        | 0.57%   |
| 6.0.9-300.fc37.x86_64   | 52        | 0.55%   |
| 6.5.6-200.fc38.x86_64   | 51        | 0.54%   |
| 6.3.11-200.fc38.x86_64  | 51        | 0.54%   |
| 6.1.18-200.fc37.x86_64  | 51        | 0.54%   |
| 6.0.12-300.fc37.x86_64  | 51        | 0.54%   |
| 6.4.14-200.fc38.x86_64  | 50        | 0.53%   |
| 5.18.11-200.fc36.x86_64 | 50        | 0.53%   |
| 6.4.7-200.fc38.x86_64   | 47        | 0.5%    |
| 6.3.5-200.fc38.x86_64   | 47        | 0.5%    |
| 5.19.16-200.fc36.x86_64 | 47        | 0.5%    |
| 6.5.7-200.fc38.x86_64   | 46        | 0.49%   |
| 6.4.11-200.fc38.x86_64  | 46        | 0.49%   |
| 6.2.8-200.fc37.x86_64   | 46        | 0.49%   |
| 6.2.13-300.fc38.x86_64  | 46        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.9   | 256       | 2.7%    |
| 6.2.15  | 177       | 1.87%   |
| 5.17.5  | 147       | 1.55%   |
| 6.3.8   | 125       | 1.32%   |
| 6.5.5   | 106       | 1.12%   |
| 6.2.14  | 104       | 1.1%    |
| 6.4.15  | 103       | 1.09%   |
| 6.0.7   | 102       | 1.08%   |
| 6.2.11  | 99        | 1.05%   |
| 5.9.16  | 96        | 1.01%   |
| 5.16.18 | 95        | 1%      |
| 5.8.15  | 87        | 0.92%   |
| 6.0.15  | 86        | 0.91%   |
| 5.11.12 | 84        | 0.89%   |
| 5.8.16  | 81        | 0.86%   |
| 5.14.10 | 79        | 0.83%   |
| 6.0.5   | 75        | 0.79%   |
| 5.19.16 | 75        | 0.79%   |
| 6.5.6   | 70        | 0.74%   |
| 6.3.12  | 70        | 0.74%   |
| 6.0.8   | 68        | 0.72%   |
| 6.0.9   | 67        | 0.71%   |
| 6.0.12  | 67        | 0.71%   |
| 5.11.11 | 66        | 0.7%    |
| 6.5.8   | 65        | 0.69%   |
| 5.18.13 | 65        | 0.69%   |
| 6.1.14  | 64        | 0.68%   |
| 5.8.18  | 64        | 0.68%   |
| 6.1.7   | 61        | 0.64%   |
| 6.2.8   | 57        | 0.6%    |
| 5.8.4   | 57        | 0.6%    |
| 5.13.12 | 57        | 0.6%    |
| 6.4.6   | 56        | 0.59%   |
| 5.14.18 | 56        | 0.59%   |
| 5.18.11 | 53        | 0.56%   |
| 6.4.7   | 52        | 0.55%   |
| 6.1.18  | 52        | 0.55%   |
| 5.14.16 | 52        | 0.55%   |
| 6.3.11  | 51        | 0.54%   |
| 5.9.8   | 51        | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 836       | 9.22%   |
| 6.0     | 654       | 7.21%   |
| 5.17    | 517       | 5.7%    |
| 6.4     | 501       | 5.53%   |
| 6.1     | 481       | 5.3%    |
| 5.8     | 464       | 5.12%   |
| 5.19    | 449       | 4.95%   |
| 5.11    | 449       | 4.95%   |
| 5.18    | 410       | 4.52%   |
| 6.3     | 403       | 4.44%   |
| 5.14    | 394       | 4.35%   |
| 5.16    | 384       | 4.24%   |
| 6.5     | 326       | 3.6%    |
| 5.15    | 310       | 3.42%   |
| 5.9     | 304       | 3.35%   |
| 5.13    | 303       | 3.34%   |
| 5.10    | 294       | 3.24%   |
| 5.6     | 286       | 3.15%   |
| 5.12    | 282       | 3.11%   |
| 5.7     | 221       | 2.44%   |
| 5.3     | 194       | 2.14%   |
| 5.5     | 183       | 2.02%   |
| 5.4     | 169       | 1.86%   |
| 5.0     | 62        | 0.68%   |
| 5.2     | 47        | 0.52%   |
| 5.1     | 43        | 0.47%   |
| 4.19    | 30        | 0.33%   |
| 4.18    | 27        | 0.3%    |
| 4.20    | 18        | 0.2%    |
| 6.6     | 5         | 0.06%   |
| 4.16    | 3         | 0.03%   |
| 4.15    | 3         | 0.03%   |
| 4.11    | 3         | 0.03%   |
| 4.1     | 3         | 0.03%   |
| 4.8     | 2         | 0.02%   |
| 4.17    | 2         | 0.02%   |
| 4.5     | 1         | 0.01%   |
| 4.14    | 1         | 0.01%   |
| 4.10    | 1         | 0.01%   |
| 3.17    | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 7632      | 99.86%  |
| i686    | 5         | 0.07%   |
| aarch64 | 5         | 0.07%   |
| Unknown | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 5833      | 74.29%  |
| KDE5            | 925       | 11.78%  |
| Unknown         | 335       | 4.27%   |
| XFCE            | 157       | 2%      |
| KDE             | 136       | 1.73%   |
| X-Cinnamon      | 109       | 1.39%   |
| MATE            | 89        | 1.13%   |
| Cinnamon        | 80        | 1.02%   |
| i3              | 35        | 0.45%   |
| GNOME Classic   | 27        | 0.34%   |
| LXQt            | 24        | 0.31%   |
| LXDE            | 20        | 0.25%   |
| sway            | 19        | 0.24%   |
| Deepin          | 13        | 0.17%   |
| Budgie          | 10        | 0.13%   |
| Pantheon        | 5         | 0.06%   |
| KDE4            | 4         | 0.05%   |
| Hyprland        | 4         | 0.05%   |
| fluxbox         | 4         | 0.05%   |
| awesome         | 4         | 0.05%   |
| openbox         | 3         | 0.04%   |
| GNOME Flashback | 3         | 0.04%   |
| xinit-compat    | 2         | 0.03%   |
| GNOME-Classic   | 2         | 0.03%   |
| dwm             | 2         | 0.03%   |
| bspwm           | 2         | 0.03%   |
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
| Wayland | 5383      | 67.98%  |
| X11     | 2261      | 28.56%  |
| Unknown | 213       | 2.69%   |
| Tty     | 60        | 0.76%   |
| Xcb     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4081      | 51.92%  |
| GDM     | 2797      | 35.59%  |
| SDDM    | 560       | 7.12%   |
| LightDM | 305       | 3.88%   |
| TDM     | 87        | 1.11%   |
| XDM     | 10        | 0.13%   |
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
| en_US   | 3991      | 51.3%   |
| en_GB   | 552       | 7.1%    |
| Unknown | 372       | 4.78%   |
| ru_RU   | 366       | 4.7%    |
| pt_BR   | 360       | 4.63%   |
| de_DE   | 274       | 3.52%   |
| fr_FR   | 227       | 2.92%   |
| it_IT   | 205       | 2.63%   |
| es_ES   | 122       | 1.57%   |
| pl_PL   | 121       | 1.56%   |
| en_CA   | 112       | 1.44%   |
| en_AU   | 99        | 1.27%   |
| en_IN   | 97        | 1.25%   |
| es_MX   | 83        | 1.07%   |
| es_CL   | 54        | 0.69%   |
| cs_CZ   | 50        | 0.64%   |
| zh_CN   | 41        | 0.53%   |
| tr_TR   | 37        | 0.48%   |
| es_AR   | 36        | 0.46%   |
| es_CO   | 32        | 0.41%   |
| pt_PT   | 31        | 0.4%    |
| nl_NL   | 28        | 0.36%   |
| hu_HU   | 27        | 0.35%   |
| en_DK   | 27        | 0.35%   |
| de_AT   | 27        | 0.35%   |
| sv_SE   | 24        | 0.31%   |
| en_NZ   | 23        | 0.3%    |
| C       | 21        | 0.27%   |
| en_ZA   | 18        | 0.23%   |
| en_IE   | 18        | 0.23%   |
| ru_UA   | 17        | 0.22%   |
| fr_CA   | 17        | 0.22%   |
| es_PE   | 14        | 0.18%   |
| fi_FI   | 13        | 0.17%   |
| sk_SK   | 12        | 0.15%   |
| fr_BE   | 12        | 0.15%   |
| en_SG   | 11        | 0.14%   |
| de_CH   | 11        | 0.14%   |
| uk_UA   | 10        | 0.13%   |
| nb_NO   | 10        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 6251      | 80.69%  |
| BIOS | 1496      | 19.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Notebooks | Percent |
|---------------------|-----------|---------|
| Btrfs               | 4968      | 63.63%  |
| Ext4                | 2439      | 31.24%  |
| Unknown             | 196       | 2.51%   |
| Xfs                 | 182       | 2.33%   |
| Overlay             | 12        | 0.15%   |
| Zfs                 | 3         | 0.04%   |
| F2fs                | 3         | 0.04%   |
| Ext3                | 3         | 0.04%   |
| Fuse.fuse-overlayfs | 2         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 4042      | 51.68%  |
| GPT     | 3363      | 43%     |
| MBR     | 416       | 5.32%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 7026      | 90.94%  |
| Yes       | 700       | 9.06%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6338      | 81.95%  |
| Yes       | 1396      | 18.05%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 2247      | 29.4%   |
| Dell                   | 1346      | 17.61%  |
| Hewlett-Packard        | 1140      | 14.92%  |
| ASUSTek Computer       | 800       | 10.47%  |
| Acer                   | 491       | 6.43%   |
| Apple                  | 224       | 2.93%   |
| MSI                    | 181       | 2.37%   |
| HUAWEI                 | 170       | 2.22%   |
| Samsung Electronics    | 107       | 1.4%    |
| Toshiba                | 103       | 1.35%   |
| Sony                   | 59        | 0.77%   |
| Timi                   | 58        | 0.76%   |
| Notebook               | 57        | 0.75%   |
| Google                 | 42        | 0.55%   |
| Framework              | 41        | 0.54%   |
| Unknown                | 38        | 0.5%    |
| Fujitsu                | 33        | 0.43%   |
| Alienware              | 28        | 0.37%   |
| Positivo               | 25        | 0.33%   |
| System76               | 23        | 0.3%    |
| TUXEDO                 | 21        | 0.27%   |
| Razer                  | 19        | 0.25%   |
| LG Electronics         | 16        | 0.21%   |
| Gigabyte Technology    | 16        | 0.21%   |
| Chuwi                  | 15        | 0.2%    |
| HONOR                  | 14        | 0.18%   |
| Avell High Performance | 12        | 0.16%   |
| Schenker               | 11        | 0.14%   |
| PC Specialist          | 11        | 0.14%   |
| GPU Company            | 10        | 0.13%   |
| Packard Bell           | 9         | 0.12%   |
| Panasonic              | 8         | 0.1%    |
| GPD                    | 8         | 0.1%    |
| Fujitsu Siemens        | 8         | 0.1%    |
| SLIMBOOK               | 7         | 0.09%   |
| Positivo Bahia - VAIO  | 6         | 0.08%   |
| Intel Client Systems   | 6         | 0.08%   |
| Insyde                 | 6         | 0.08%   |
| Hampoo                 | 6         | 0.08%   |
| Clevo                  | 6         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 63        | 0.82%   |
| HP Notebook                                | 39        | 0.51%   |
| Framework Laptop                           | 30        | 0.39%   |
| Dell Latitude 7490                         | 28        | 0.37%   |
| Dell XPS 15 9570                           | 25        | 0.33%   |
| Dell XPS 13 9370                           | 25        | 0.33%   |
| Dell XPS 15 7590                           | 24        | 0.31%   |
| Apple MacBookPro9,2                        | 24        | 0.31%   |
| Dell XPS 15 9560                           | 23        | 0.3%    |
| Dell XPS 13 9310                           | 22        | 0.29%   |
| HP EliteBook 840 G6                        | 21        | 0.27%   |
| Dell XPS 13 9360                           | 20        | 0.26%   |
| Dell XPS 15 9500                           | 19        | 0.25%   |
| Dell XPS 13 7390                           | 19        | 0.25%   |
| Dell Latitude E7450                        | 19        | 0.25%   |
| HP Pavilion dv6                            | 18        | 0.24%   |
| Apple MacBookPro12,1                       | 18        | 0.24%   |
| HP Pavilion 15                             | 17        | 0.22%   |
| Dell XPS 15 9550                           | 17        | 0.22%   |
| Apple MacBookPro8,1                        | 17        | 0.22%   |
| HP Pavilion Notebook                       | 16        | 0.21%   |
| Dell XPS 13 9300                           | 16        | 0.21%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 15        | 0.2%    |
| HUAWEI KLVL-WXX9                           | 15        | 0.2%    |
| HP Laptop 15-da0xxx                        | 15        | 0.2%    |
| Dell Latitude E6420                        | 15        | 0.2%    |
| Lenovo IdeaPad 3 15ITL6 82H8               | 14        | 0.18%   |
| HUAWEI NBLK-WAX9X                          | 14        | 0.18%   |
| HP EliteBook 840 G3                        | 14        | 0.18%   |
| Dell XPS 13 9380                           | 14        | 0.18%   |
| Dell Latitude E7440                        | 14        | 0.18%   |
| Dell Latitude 5480                         | 14        | 0.18%   |
| Lenovo ThinkPad X1 Carbon Gen 8 20U9CTO1WW | 13        | 0.17%   |
| Lenovo IdeaPad 5 15ARE05 81YQ              | 13        | 0.17%   |
| Dell XPS 15 9510                           | 13        | 0.17%   |
| Dell Inspiron 15 7000 Gaming               | 13        | 0.17%   |
| ASUS ROG Zephyrus G14 GA401QM_GA401QM      | 13        | 0.17%   |
| Acer Nitro AN515-54                        | 13        | 0.17%   |
| HUAWEI HVY-WXX9                            | 12        | 0.16%   |
| HP Pavilion dv7                            | 12        | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1335      | 17.47%  |
| Lenovo IdeaPad     | 462       | 6.05%   |
| Dell Latitude      | 416       | 5.44%   |
| Dell Inspiron      | 368       | 4.82%   |
| Acer Aspire        | 311       | 4.07%   |
| Dell XPS           | 301       | 3.94%   |
| HP Pavilion        | 243       | 3.18%   |
| HP EliteBook       | 222       | 2.9%    |
| ASUS VivoBook      | 177       | 2.32%   |
| HP ProBook         | 173       | 2.26%   |
| HP Laptop          | 163       | 2.13%   |
| ASUS ROG           | 132       | 1.73%   |
| Dell Precision     | 113       | 1.48%   |
| Lenovo Legion      | 97        | 1.27%   |
| Lenovo ThinkBook   | 86        | 1.13%   |
| Toshiba Satellite  | 84        | 1.1%    |
| ASUS ASUS          | 75        | 0.98%   |
| Acer Nitro         | 71        | 0.93%   |
| Lenovo Yoga        | 70        | 0.92%   |
| ASUS ZenBook       | 67        | 0.88%   |
| Dell Vostro        | 66        | 0.86%   |
| Unknown            | 63        | 0.82%   |
| HP ZBook           | 56        | 0.73%   |
| HP ENVY            | 47        | 0.62%   |
| Acer Swift         | 44        | 0.58%   |
| Framework Laptop   | 41        | 0.54%   |
| HP OMEN            | 40        | 0.52%   |
| HP Notebook        | 39        | 0.51%   |
| Apple MacBookPro11 | 39        | 0.51%   |
| ASUS TUF           | 34        | 0.44%   |
| MSI Modern         | 31        | 0.41%   |
| Apple MacBookPro9  | 28        | 0.37%   |
| Fujitsu LIFEBOOK   | 27        | 0.35%   |
| Acer Predator      | 25        | 0.33%   |
| Dell G5            | 23        | 0.3%    |
| Apple MacBookPro8  | 23        | 0.3%    |
| HP 250             | 19        | 0.25%   |
| Razer Blade        | 18        | 0.24%   |
| Apple MacBookPro12 | 18        | 0.24%   |
| HP 255             | 16        | 0.21%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2020    | 1014      | 13.27%  |
| 2021    | 944       | 12.35%  |
| 2019    | 929       | 12.16%  |
| 2018    | 788       | 10.31%  |
| 2017    | 559       | 7.31%   |
| 2022    | 481       | 6.29%   |
| 2012    | 437       | 5.72%   |
| 2015    | 433       | 5.67%   |
| 2016    | 414       | 5.42%   |
| 2013    | 412       | 5.39%   |
| 2014    | 395       | 5.17%   |
| 2011    | 319       | 4.17%   |
| 2010    | 166       | 2.17%   |
| 2023    | 129       | 1.69%   |
| 2008    | 103       | 1.35%   |
| 2009    | 82        | 1.07%   |
| 2007    | 25        | 0.33%   |
| 2006    | 6         | 0.08%   |
| Unknown | 5         | 0.07%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 7642      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 6076      | 78.08%  |
| Enabled  | 1706      | 21.92%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 7577      | 99.15%  |
| Yes  | 65        | 0.85%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 2256      | 29.07%  |
| 16.01-24.0  | 1821      | 23.47%  |
| 8.01-16.0   | 1556      | 20.05%  |
| 32.01-64.0  | 892       | 11.49%  |
| 3.01-4.0    | 762       | 9.82%   |
| 24.01-32.0  | 151       | 1.95%   |
| 1.01-2.0    | 142       | 1.83%   |
| 64.01-256.0 | 134       | 1.73%   |
| 2.01-3.0    | 33        | 0.43%   |
| 0.51-1.0    | 11        | 0.14%   |
| Unknown     | 2         | 0.03%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 2382      | 27.78%  |
| 2.01-3.0   | 2371      | 27.65%  |
| 3.01-4.0   | 1934      | 22.55%  |
| 1.01-2.0   | 1083      | 12.63%  |
| 8.01-16.0  | 627       | 7.31%   |
| 0.51-1.0   | 83        | 0.97%   |
| 16.01-24.0 | 65        | 0.76%   |
| 24.01-32.0 | 17        | 0.2%    |
| 32.01-64.0 | 7         | 0.08%   |
| 0.01-0.5   | 4         | 0.05%   |
| Unknown    | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 5666      | 72.91%  |
| 2      | 1808      | 23.27%  |
| 3      | 209       | 2.69%   |
| 0      | 39        | 0.5%    |
| 4      | 33        | 0.42%   |
| 5      | 9         | 0.12%   |
| 6      | 6         | 0.08%   |
| 8      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 6114      | 79.71%  |
| Yes       | 1556      | 20.29%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 5642      | 73.36%  |
| No        | 2049      | 26.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 7499      | 98.05%  |
| No        | 149       | 1.95%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 6468      | 83.68%  |
| No        | 1261      | 16.32%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 1263      | 16.35%  |
| Brazil      | 548       | 7.09%   |
| Germany     | 531       | 6.87%   |
| Russia      | 501       | 6.48%   |
| Italy       | 368       | 4.76%   |
| France      | 308       | 3.99%   |
| India       | 303       | 3.92%   |
| UK          | 278       | 3.6%    |
| Poland      | 224       | 2.9%    |
| Netherlands | 221       | 2.86%   |
| Canada      | 217       | 2.81%   |
| Spain       | 197       | 2.55%   |
| Mexico      | 154       | 1.99%   |
| Czechia     | 129       | 1.67%   |
| Turkey      | 127       | 1.64%   |
| Australia   | 120       | 1.55%   |
| Sweden      | 95        | 1.23%   |
| Austria     | 95        | 1.23%   |
| Switzerland | 82        | 1.06%   |
| Portugal    | 77        | 1%      |
| Chile       | 71        | 0.92%   |
| Belgium     | 71        | 0.92%   |
| Indonesia   | 70        | 0.91%   |
| Argentina   | 70        | 0.91%   |
| Hungary     | 66        | 0.85%   |
| Ukraine     | 65        | 0.84%   |
| Romania     | 64        | 0.83%   |
| Norway      | 62        | 0.8%    |
| Finland     | 61        | 0.79%   |
| Colombia    | 55        | 0.71%   |
| Denmark     | 53        | 0.69%   |
| China       | 49        | 0.63%   |
| Iran        | 46        | 0.6%    |
| Bulgaria    | 42        | 0.54%   |
| Israel      | 40        | 0.52%   |
| Belarus     | 38        | 0.49%   |
| Greece      | 37        | 0.48%   |
| Slovakia    | 36        | 0.47%   |
| Japan       | 35        | 0.45%   |
| Philippines | 33        | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 159       | 1.93%   |
| Sao Paulo         | 73        | 0.89%   |
| St Petersburg     | 71        | 0.86%   |
| Berlin            | 65        | 0.79%   |
| Vienna            | 62        | 0.75%   |
| Paris             | 59        | 0.72%   |
| Milan             | 55        | 0.67%   |
| Warsaw            | 53        | 0.64%   |
| Istanbul          | 52        | 0.63%   |
| Prague            | 51        | 0.62%   |
| Amsterdam         | 51        | 0.62%   |
| Madrid            | 47        | 0.57%   |
| Mexico City       | 42        | 0.51%   |
| Bengaluru         | 39        | 0.47%   |
| Munich            | 38        | 0.46%   |
| Helsinki          | 38        | 0.46%   |
| Melbourne         | 35        | 0.42%   |
| Sydney            | 34        | 0.41%   |
| Santiago          | 33        | 0.4%    |
| Oslo              | 33        | 0.4%    |
| Budapest          | 33        | 0.4%    |
| Frankfurt am Main | 31        | 0.38%   |
| Lisbon            | 29        | 0.35%   |
| Hamburg           | 29        | 0.35%   |
| Sofia             | 28        | 0.34%   |
| Rio de Janeiro    | 28        | 0.34%   |
| Delft             | 28        | 0.34%   |
| Zurich            | 27        | 0.33%   |
| Montreal          | 27        | 0.33%   |
| Jakarta           | 27        | 0.33%   |
| Tehran            | 26        | 0.32%   |
| Bucharest         | 26        | 0.32%   |
| Barcelona         | 26        | 0.32%   |
| Singapore         | 25        | 0.3%    |
| Brisbane          | 25        | 0.3%    |
| Brasília         | 25        | 0.3%    |
| Kyiv              | 24        | 0.29%   |
| Rome              | 23        | 0.28%   |
| Minsk             | 23        | 0.28%   |
| Pune              | 22        | 0.27%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 2041      | 2916   | 21.12%  |
| WDC                         | 902       | 1136   | 9.34%   |
| Sandisk                     | 754       | 970    | 7.8%    |
| Seagate                     | 685       | 894    | 7.09%   |
| Toshiba                     | 624       | 788    | 6.46%   |
| SK hynix                    | 575       | 704    | 5.95%   |
| Unknown                     | 500       | 647    | 5.17%   |
| Kingston                    | 468       | 572    | 4.84%   |
| Intel                       | 413       | 571    | 4.27%   |
| Micron Technology           | 349       | 446    | 3.61%   |
| Crucial                     | 276       | 366    | 2.86%   |
| HGST                        | 184       | 251    | 1.9%    |
| KIOXIA                      | 150       | 209    | 1.55%   |
| A-DATA Technology           | 137       | 159    | 1.42%   |
| Apple                       | 125       | 168    | 1.29%   |
| Hitachi                     | 89        | 104    | 0.92%   |
| LITEON                      | 78        | 84     | 0.81%   |
| China                       | 67        | 80     | 0.69%   |
| Silicon Motion              | 65        | 82     | 0.67%   |
| Phison                      | 64        | 72     | 0.66%   |
| Micron/Crucial Technology   | 52        | 56     | 0.54%   |
| Phison Electronics          | 47        | 51     | 0.49%   |
| PNY                         | 43        | 56     | 0.45%   |
| ADATA Technology            | 43        | 46     | 0.45%   |
| Transcend                   | 39        | 56     | 0.4%    |
| SPCC                        | 37        | 47     | 0.38%   |
| Kingston Technology Company | 37        | 42     | 0.38%   |
| LITEONIT                    | 31        | 37     | 0.32%   |
| JMicron Technology          | 29        | 35     | 0.3%    |
| Lenovo                      | 28        | 31     | 0.29%   |
| Unknown                     | 25        | 30     | 0.26%   |
| Realtek Semiconductor       | 23        | 28     | 0.24%   |
| Corsair                     | 22        | 27     | 0.23%   |
| Netac                       | 21        | 27     | 0.22%   |
| Union Memory (Shenzhen)     | 19        | 32     | 0.2%    |
| Team                        | 19        | 22     | 0.2%    |
| Patriot                     | 19        | 25     | 0.2%    |
| Intenso                     | 19        | 22     | 0.2%    |
| Hewlett-Packard             | 19        | 18     | 0.2%    |
| XPG                         | 18        | 27     | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 172       | 1.7%    |
| Seagate ST1000LM035-1RK172 1TB                     | 146       | 1.44%   |
| Samsung NVMe SSD Drive 512GB                       | 113       | 1.11%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 111       | 1.09%   |
| Kingston SA400S37240G 240GB SSD                    | 92        | 0.91%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 83        | 0.82%   |
| SanDisk NVMe SSD Drive 512GB                       | 81        | 0.8%    |
| Unknown MMC Card  64GB                             | 80        | 0.79%   |
| Unknown MMC Card  32GB                             | 80        | 0.79%   |
| HGST HTS721010A9E630 1TB                           | 79        | 0.78%   |
| Toshiba MQ04ABF100 1TB                             | 78        | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 76        | 0.75%   |
| Kingston SA400S37480G 480GB SSD                    | 67        | 0.66%   |
| Toshiba MQ01ABD100 1TB                             | 61        | 0.6%    |
| Samsung SSD 860 EVO 500GB                          | 60        | 0.59%   |
| Unknown MMC Card  128GB                            | 54        | 0.53%   |
| SK hynix NVMe SSD Drive 512GB                      | 51        | 0.5%    |
| Samsung NVMe SSD Drive 1024GB                      | 51        | 0.5%    |
| Sandisk WD Blue SN550 NVMe SSD 1TB                 | 49        | 0.48%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB  | 48        | 0.47%   |
| SanDisk NVMe SSD Drive 256GB                       | 48        | 0.47%   |
| Intel SSDPEKNU512GZ 512GB                          | 46        | 0.45%   |
| Intel NVMe SSD Drive 512GB                         | 46        | 0.45%   |
| Samsung SSD 850 EVO 250GB                          | 45        | 0.44%   |
| Seagate ST500LT012-1DG142 500GB                    | 44        | 0.43%   |
| Samsung SSD 850 EVO 500GB                          | 44        | 0.43%   |
| Samsung NVMe SSD Drive 1TB                         | 43        | 0.42%   |
| Toshiba NVMe SSD Drive 512GB                       | 38        | 0.37%   |
| Crucial CT240BX500SSD1 240GB                       | 38        | 0.37%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 36        | 0.36%   |
| Seagate Expansion 1TB                              | 35        | 0.35%   |
| Samsung SSD 980 1TB                                | 35        | 0.35%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 35        | 0.35%   |
| Crucial CT1000MX500SSD1 1TB                        | 35        | 0.35%   |
| Samsung SSD 860 EVO 250GB                          | 34        | 0.34%   |
| Toshiba NVMe SSD Drive 256GB                       | 33        | 0.33%   |
| Samsung SSD 860 EVO 1TB                            | 33        | 0.33%   |
| Samsung NVMe SSD Drive 500GB                       | 33        | 0.33%   |
| Intel SSD 660P Series 1024GB                       | 33        | 0.33%   |
| HGST HTS541010A9E680 1TB                           | 33        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 657       | 851    | 36.52%  |
| WDC                 | 473       | 602    | 26.29%  |
| Toshiba             | 305       | 376    | 16.95%  |
| HGST                | 184       | 251    | 10.23%  |
| Hitachi             | 89        | 104    | 4.95%   |
| Unknown             | 24        | 35     | 1.33%   |
| Samsung Electronics | 17        | 20     | 0.94%   |
| Fujitsu             | 14        | 14     | 0.78%   |
| Apple               | 13        | 14     | 0.72%   |
| External            | 4         | 6      | 0.22%   |
| USB3.0              | 2         | 2      | 0.11%   |
| LIO-ORG             | 2         | 8      | 0.11%   |
| LaCie               | 2         | 3      | 0.11%   |
| HGST HTS            | 2         | 2      | 0.11%   |
| ASMT                | 2         | 3      | 0.11%   |
| SSK                 | 1         | 1      | 0.06%   |
| SAGE                | 1         | 1      | 0.06%   |
| QNAP                | 1         | 4      | 0.06%   |
| Phison              | 1         | 2      | 0.06%   |
| JMicron Technology  | 1         | 1      | 0.06%   |
| Intenso             | 1         | 1      | 0.06%   |
| IB-AC703            | 1         | 1      | 0.06%   |
| IB                  | 1         | 2      | 0.06%   |
| ACASIS              | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 702       | 995    | 24.41%  |
| Kingston            | 336       | 407    | 11.68%  |
| SanDisk             | 293       | 395    | 10.19%  |
| Crucial             | 248       | 335    | 8.62%   |
| WDC                 | 153       | 193    | 5.32%   |
| Intel               | 99        | 155    | 3.44%   |
| Micron Technology   | 93        | 113    | 3.23%   |
| A-DATA Technology   | 89        | 104    | 3.09%   |
| Apple               | 82        | 93     | 2.85%   |
| SK hynix            | 74        | 89     | 2.57%   |
| China               | 66        | 79     | 2.29%   |
| Toshiba             | 63        | 80     | 2.19%   |
| LITEON              | 63        | 69     | 2.19%   |
| PNY                 | 41        | 53     | 1.43%   |
| Transcend           | 33        | 46     | 1.15%   |
| LITEONIT            | 31        | 37     | 1.08%   |
| SPCC                | 30        | 40     | 1.04%   |
| Patriot             | 17        | 22     | 0.59%   |
| Netac               | 16        | 20     | 0.56%   |
| KingSpec            | 16        | 19     | 0.56%   |
| OCZ                 | 15        | 17     | 0.52%   |
| Intenso             | 15        | 17     | 0.52%   |
| Gigabyte Technology | 15        | 21     | 0.52%   |
| SABRENT             | 14        | 14     | 0.49%   |
| Corsair             | 14        | 16     | 0.49%   |
| Team                | 13        | 16     | 0.45%   |
| GOODRAM             | 13        | 22     | 0.45%   |
| Lexar               | 12        | 22     | 0.42%   |
| Hewlett-Packard     | 11        | 11     | 0.38%   |
| Apacer              | 11        | 14     | 0.38%   |
| Seagate             | 10        | 11     | 0.35%   |
| Plextor             | 7         | 11     | 0.24%   |
| Unknown             | 6         | 6      | 0.21%   |
| TO Exter            | 5         | 5      | 0.17%   |
| Ramsta              | 5         | 6      | 0.17%   |
| Mushkin             | 5         | 14     | 0.17%   |
| FORESEE             | 5         | 6      | 0.17%   |
| Unknown             | 5         | 6      | 0.17%   |
| Teclast             | 4         | 5      | 0.14%   |
| MidasForce          | 4         | 4      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 4094      | 5768   | 45.01%  |
| SSD     | 2667      | 3752   | 29.32%  |
| HDD     | 1736      | 2305   | 19.09%  |
| MMC     | 472       | 617    | 5.19%   |
| Unknown | 127       | 141    | 1.4%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 4082      | 5729   | 46.68%  |
| SATA | 3866      | 5810   | 44.21%  |
| MMC  | 472       | 617    | 5.4%    |
| SAS  | 324       | 427    | 3.71%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2738      | 3828   | 62.44%  |
| 0.51-1.0   | 1463      | 1963   | 33.36%  |
| 1.01-2.0   | 149       | 228    | 3.4%    |
| 3.01-4.0   | 14        | 16     | 0.32%   |
| 4.01-10.0  | 11        | 11     | 0.25%   |
| 2.01-3.0   | 8         | 8      | 0.18%   |
| 10.01-20.0 | 1         | 1      | 0.02%   |
| 0          | 1         | 2      | 0.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 1757      | 21.89%  |
| 501-1000       | 1736      | 21.63%  |
| 101-250        | 1386      | 17.27%  |
| 1001-2000      | 901       | 11.23%  |
| 1-20           | 854       | 10.64%  |
| Unknown        | 592       | 7.38%   |
| 51-100         | 310       | 3.86%   |
| 21-50          | 173       | 2.16%   |
| More than 3000 | 166       | 2.07%   |
| 2001-3000      | 150       | 1.87%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 2587      | 30.74%  |
| 21-50          | 1459      | 17.33%  |
| 101-250        | 1281      | 15.22%  |
| 51-100         | 1075      | 12.77%  |
| 251-500        | 782       | 9.29%   |
| Unknown        | 592       | 7.03%   |
| 501-1000       | 447       | 5.31%   |
| 1001-2000      | 146       | 1.73%   |
| More than 3000 | 25        | 0.3%    |
| 2001-3000      | 22        | 0.26%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB                | 13        | 13     | 3.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 9         | 19     | 2.76%   |
| HGST HTS721010A9E630 1TB                       | 8         | 10     | 2.45%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 2.15%   |
| HGST HTS541010A9E680 1TB                       | 7         | 7      | 2.15%   |
| Toshiba MQ01ABD100 1TB                         | 6         | 6      | 1.84%   |
| Seagate ST9500325AS 500GB                      | 6         | 8      | 1.84%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 6         | 6      | 1.84%   |
| HGST HTS545050A7E680 500GB                     | 6         | 6      | 1.84%   |
| Toshiba MQ01ABD075 752GB                       | 4         | 4      | 1.23%   |
| Hitachi HTS547575A9E384 752GB                  | 4         | 6      | 1.23%   |
| HGST HTS725050A7E630 500GB                     | 4         | 4      | 1.23%   |
| Toshiba MQ01ABF050 500GB                       | 3         | 3      | 0.92%   |
| SK hynix SC308 SATA 128GB SSD                  | 3         | 3      | 0.92%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 3         | 3      | 0.92%   |
| Seagate ST9500420AS 500GB                      | 3         | 4      | 0.92%   |
| Seagate ST9320325AS 320GB                      | 3         | 3      | 0.92%   |
| Seagate ST500LM021-1KJ152 500GB                | 3         | 4      | 0.92%   |
| Seagate ST1000LM049-2GH172 1TB                 | 3         | 4      | 0.92%   |
| Seagate ST1000LM014-1EJ164 1TB                 | 3         | 3      | 0.92%   |
| Samsung Electronics SSD 980 1TB                | 3         | 3      | 0.92%   |
| Samsung Electronics SSD 870 EVO 500GB          | 3         | 6      | 0.92%   |
| Hitachi HTS545050B9A300 500GB                  | 3         | 3      | 0.92%   |
| Crucial CT1000P1SSD8 1TB                       | 3         | 3      | 0.92%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 2         | 2      | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD               | 2         | 2      | 0.61%   |
| WDC WD10SPZX-24Z10 1TB                         | 2         | 2      | 0.61%   |
| Toshiba MQ01ACF050 500GB                       | 2         | 2      | 0.61%   |
| Toshiba MQ01ABD050V 497GB                      | 2         | 2      | 0.61%   |
| Toshiba MK5061GSY 500GB                        | 2         | 2      | 0.61%   |
| Toshiba MK3275GSX 320GB                        | 2         | 3      | 0.61%   |
| SPCC Solid State Disk 256GB                    | 2         | 2      | 0.61%   |
| SK hynix HFS256G39TND-N210A 256GB SSD          | 2         | 2      | 0.61%   |
| Seagate ST9750420AS 752GB                      | 2         | 2      | 0.61%   |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 0.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 2         | 2      | 0.61%   |
| Seagate ST500LM000-SSHD-8GB                    | 2         | 3      | 0.61%   |
| Seagate ST500LM000-1EJ162 500GB                | 2         | 2      | 0.61%   |
| Seagate ST2000LM003 HN-M201RAD 2TB             | 2         | 2      | 0.61%   |
| SanDisk SSD PLUS 240GB                         | 2         | 2      | 0.61%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 70        | 87     | 21.54%  |
| Toshiba             | 34        | 35     | 10.46%  |
| WDC                 | 32        | 35     | 9.85%   |
| HGST                | 29        | 31     | 8.92%   |
| Samsung Electronics | 27        | 32     | 8.31%   |
| Hitachi             | 20        | 24     | 6.15%   |
| Micron Technology   | 15        | 18     | 4.62%   |
| Intel               | 15        | 26     | 4.62%   |
| SK hynix            | 14        | 15     | 4.31%   |
| SanDisk             | 13        | 15     | 4%      |
| Crucial             | 12        | 20     | 3.69%   |
| Kingston            | 9         | 11     | 2.77%   |
| A-DATA Technology   | 5         | 5      | 1.54%   |
| LITEON              | 4         | 4      | 1.23%   |
| LITEONIT            | 3         | 4      | 0.92%   |
| Fujitsu             | 3         | 3      | 0.92%   |
| SPCC                | 2         | 2      | 0.62%   |
| China               | 2         | 2      | 0.62%   |
| YS                  | 1         | 1      | 0.31%   |
| Wibtek              | 1         | 1      | 0.31%   |
| walram              | 1         | 1      | 0.31%   |
| Union Memory        | 1         | 1      | 0.31%   |
| Teclast             | 1         | 1      | 0.31%   |
| SSSTC               | 1         | 1      | 0.31%   |
| SSD                 | 1         | 1      | 0.31%   |
| PNY                 | 1         | 1      | 0.31%   |
| Plextor             | 1         | 1      | 0.31%   |
| Origin              | 1         | 1      | 0.31%   |
| OCZ-VERTEX3         | 1         | 1      | 0.31%   |
| Netac               | 1         | 1      | 0.31%   |
| Lenovo              | 1         | 2      | 0.31%   |
| HGST HTS            | 1         | 1      | 0.31%   |
| Apple               | 1         | 1      | 0.31%   |
| Unknown             | 1         | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 70        | 87     | 37.04%  |
| Toshiba             | 33        | 34     | 17.46%  |
| HGST                | 29        | 31     | 15.34%  |
| WDC                 | 28        | 31     | 14.81%  |
| Hitachi             | 20        | 24     | 10.58%  |
| Samsung Electronics | 4         | 4      | 2.12%   |
| Fujitsu             | 3         | 3      | 1.59%   |
| HGST HTS            | 1         | 1      | 0.53%   |
| Apple               | 1         | 1      | 0.53%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 188       | 216    | 58.2%   |
| SSD  | 109       | 141    | 33.75%  |
| NVMe | 26        | 29     | 8.05%   |

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
| Detected | 4468      | 7321   | 54.6%   |
| Works    | 3394      | 4869   | 41.48%  |
| Malfunc  | 314       | 386    | 3.84%   |
| Failed   | 7         | 7      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 4606      | 48.16%  |
| Samsung Electronics                     | 1420      | 14.85%  |
| AMD                                     | 798       | 8.34%   |
| SanDisk                                 | 713       | 7.46%   |
| SK hynix                                | 487       | 5.09%   |
| Toshiba America Info Systems            | 262       | 2.74%   |
| Micron Technology                       | 258       | 2.7%    |
| Kingston Technology Company             | 171       | 1.79%   |
| KIOXIA                                  | 150       | 1.57%   |
| Phison Electronics                      | 122       | 1.28%   |
| ADATA Technology                        | 99        | 1.04%   |
| Silicon Motion                          | 83        | 0.87%   |
| Micron/Crucial Technology               | 76        | 0.79%   |
| Union Memory (Shenzhen)                 | 41        | 0.43%   |
| Solid State Storage Technology          | 37        | 0.39%   |
| Nvidia                                  | 33        | 0.35%   |
| Realtek Semiconductor                   | 30        | 0.31%   |
| Lite-On Technology                      | 29        | 0.3%    |
| Apple                                   | 27        | 0.28%   |
| Lenovo                                  | 26        | 0.27%   |
| MAXIO Technology (Hangzhou)             | 13        | 0.14%   |
| Yangtze Memory Technologies             | 12        | 0.13%   |
| Shenzhen Longsys Electronics            | 11        | 0.12%   |
| Seagate Technology                      | 11        | 0.12%   |
| Marvell Technology Group                | 11        | 0.12%   |
| Netac Technology                        | 6         | 0.06%   |
| JMicron Technology                      | 5         | 0.05%   |
| Biwin Storage Technology                | 5         | 0.05%   |
| Solidigm                                | 4         | 0.04%   |
| Shenzhen Unionmemory Information System | 4         | 0.04%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.02%   |
| INNOGRIT                                | 2         | 0.02%   |
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
| AMD FCH SATA Controller [AHCI mode]                                            | 761       | 7.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 719       | 7.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 664       | 6.63%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 448       | 4.48%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 439       | 4.39%   |
| Intel Volume Management Device NVMe RAID Controller                            | 353       | 3.53%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 333       | 3.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 271       | 2.71%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 264       | 2.64%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 240       | 2.4%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 213       | 2.13%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 209       | 2.09%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 194       | 1.94%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 188       | 1.88%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 188       | 1.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 176       | 1.76%   |
| Intel Tiger Lake-LP SATA Controller                                            | 141       | 1.41%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 138       | 1.38%   |
| Intel Comet Lake SATA AHCI Controller                                          | 129       | 1.29%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 124       | 1.24%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 117       | 1.17%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 110       | 1.1%    |
| Intel SSD 660P Series                                                          | 109       | 1.09%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 101       | 1.01%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 92        | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 89        | 0.89%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 86        | 0.86%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 83        | 0.83%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 82        | 0.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 76        | 0.76%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 74        | 0.74%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 74        | 0.74%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 70        | 0.7%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 67        | 0.67%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 64        | 0.64%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 64        | 0.64%   |
| SK hynix BC511 NVMe SSD                                                        | 63        | 0.63%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 57        | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 55        | 0.55%   |
| Toshiba America Info Systems XG5 NVMe SSD Controller                           | 53        | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 4565      | 47.47%  |
| NVMe | 4082      | 42.45%  |
| RAID | 834       | 8.67%   |
| IDE  | 135       | 1.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 6097      | 79.78%  |
| AMD          | 1538      | 20.13%  |
| ARM          | 4         | 0.05%   |
| Unknown      | 2         | 0.03%   |
| CentaurHauls | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 190       | 2.48%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 169       | 2.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 157       | 2.05%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 155       | 2.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 123       | 1.61%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 123       | 1.61%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 121       | 1.58%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 121       | 1.58%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 114       | 1.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 113       | 1.48%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 110       | 1.44%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 102       | 1.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 101       | 1.32%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 101       | 1.32%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 101       | 1.32%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 90        | 1.18%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 88        | 1.15%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 84        | 1.1%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 77        | 1.01%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 74        | 0.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 74        | 0.97%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 73        | 0.95%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 72        | 0.94%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 69        | 0.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 62        | 0.81%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 61        | 0.8%    |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 58        | 0.76%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 57        | 0.75%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 57        | 0.75%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 52        | 0.68%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 50        | 0.65%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 50        | 0.65%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 50        | 0.65%   |
| Intel 12th Gen Core i7-12700H                 | 49        | 0.64%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 49        | 0.64%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 48        | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 46        | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 45        | 0.59%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 44        | 0.58%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 44        | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 2115      | 27.67%  |
| Intel Core i5                  | 1874      | 24.51%  |
| Other                          | 983       | 12.86%  |
| AMD Ryzen 5                    | 476       | 6.23%   |
| AMD Ryzen 7                    | 470       | 6.15%   |
| Intel Core i3                  | 444       | 5.81%   |
| Intel Celeron                  | 198       | 2.59%   |
| Intel Core 2 Duo               | 132       | 1.73%   |
| Intel Atom                     | 117       | 1.53%   |
| AMD Ryzen 9                    | 112       | 1.47%   |
| AMD Ryzen 7 PRO                | 110       | 1.44%   |
| Intel Pentium                  | 82        | 1.07%   |
| AMD Ryzen 3                    | 69        | 0.9%    |
| Intel Core i9                  | 60        | 0.78%   |
| AMD Ryzen 5 PRO                | 54        | 0.71%   |
| AMD A6                         | 44        | 0.58%   |
| AMD A10                        | 39        | 0.51%   |
| AMD A8                         | 32        | 0.42%   |
| Intel Pentium Silver           | 27        | 0.35%   |
| AMD A4                         | 23        | 0.3%    |
| Intel Xeon                     | 17        | 0.22%   |
| Intel Pentium Dual-Core        | 16        | 0.21%   |
| AMD E1                         | 15        | 0.2%    |
| AMD Athlon                     | 12        | 0.16%   |
| AMD A12                        | 12        | 0.16%   |
| Intel Pentium Dual             | 10        | 0.13%   |
| Intel Core m3                  | 10        | 0.13%   |
| Intel Core m5                  | 9         | 0.12%   |
| Intel Genuine                  | 8         | 0.1%    |
| AMD E                          | 8         | 0.1%    |
| Intel Core M                   | 7         | 0.09%   |
| AMD E2                         | 7         | 0.09%   |
| Intel Core m7                  | 5         | 0.07%   |
| Intel Core 2                   | 4         | 0.05%   |
| Intel Celeron Dual-Core        | 4         | 0.05%   |
| AMD PRO A10                    | 4         | 0.05%   |
| AMD Phenom II                  | 4         | 0.05%   |
| AMD Athlon II                  | 4         | 0.05%   |
| AMD Turion X2 Dual-Core Mobile | 3         | 0.04%   |
| AMD Ryzen 3 PRO                | 3         | 0.04%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 4       | 3007      | 39.33%  |
| 2       | 2747      | 35.93%  |
| 8       | 784       | 10.26%  |
| 6       | 755       | 9.88%   |
| 12      | 111       | 1.45%   |
| 14      | 108       | 1.41%   |
| 10      | 89        | 1.16%   |
| 1       | 26        | 0.34%   |
| 16      | 9         | 0.12%   |
| 24      | 4         | 0.05%   |
| 3       | 2         | 0.03%   |
| 20      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 7641      | 99.97%  |
| 2       | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 6712      | 87.7%   |
| 1       | 940       | 12.28%  |
| Unknown | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7504      | 97.93%  |
| Unknown        | 151       | 1.97%   |
| 64-bit         | 4         | 0.05%   |
| 32-bit         | 4         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1829      | 23.18%  |
| 0x806ec    | 398       | 5.04%   |
| 0x806ea    | 383       | 4.85%   |
| 0x306a9    | 356       | 4.51%   |
| 0x806c1    | 349       | 4.42%   |
| 0x206a7    | 278       | 3.52%   |
| 0x906ea    | 273       | 3.46%   |
| 0x406e3    | 272       | 3.45%   |
| 0x806e9    | 269       | 3.41%   |
| 0x0a50000c | 228       | 2.89%   |
| 0x40651    | 221       | 2.8%    |
| 0x306d4    | 215       | 2.72%   |
| 0x306c3    | 168       | 2.13%   |
| 0xa0652    | 165       | 2.09%   |
| 0x08600106 | 149       | 1.89%   |
| 0x08108109 | 134       | 1.7%    |
| 0x08108102 | 124       | 1.57%   |
| 0x906e9    | 118       | 1.5%    |
| 0x08608103 | 113       | 1.43%   |
| 0x506e3    | 111       | 1.41%   |
| 0x706e5    | 104       | 1.32%   |
| 0x906a3    | 88        | 1.12%   |
| 0x08600104 | 85        | 1.08%   |
| 0x20655    | 81        | 1.03%   |
| 0x806eb    | 75        | 0.95%   |
| 0x30678    | 75        | 0.95%   |
| 0x0a404102 | 74        | 0.94%   |
| 0x1067a    | 70        | 0.89%   |
| 0x806d1    | 61        | 0.77%   |
| 0x906ed    | 56        | 0.71%   |
| 0x0a50000d | 55        | 0.7%    |
| 0x08600103 | 53        | 0.67%   |
| 0x406c4    | 42        | 0.53%   |
| 0x0810100b | 41        | 0.52%   |
| 0x0a404101 | 38        | 0.48%   |
| 0x08608102 | 38        | 0.48%   |
| 0x706a8    | 34        | 0.43%   |
| 0x06006705 | 32        | 0.41%   |
| 0x406c3    | 30        | 0.38%   |
| 0x906a4    | 29        | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 1984      | 25.93%  |
| TigerLake         | 538       | 7.03%   |
| Haswell           | 519       | 6.78%   |
| Skylake           | 490       | 6.41%   |
| IvyBridge         | 455       | 5.95%   |
| SandyBridge       | 351       | 4.59%   |
| Unknown           | 344       | 4.5%    |
| Zen 2             | 338       | 4.42%   |
| Alderlake Hybrid  | 314       | 4.1%    |
| Zen 3             | 313       | 4.09%   |
| Zen+              | 267       | 3.49%   |
| Broadwell         | 263       | 3.44%   |
| CometLake         | 240       | 3.14%   |
| Icelake           | 227       | 2.97%   |
| Silvermont        | 206       | 2.69%   |
| Westmere          | 147       | 1.92%   |
| Penryn            | 132       | 1.73%   |
| Goldmont plus     | 87        | 1.14%   |
| Zen               | 80        | 1.05%   |
| Excavator         | 73        | 0.95%   |
| Core              | 41        | 0.54%   |
| Goldmont          | 40        | 0.52%   |
| Piledriver        | 37        | 0.48%   |
| Puma              | 36        | 0.47%   |
| Jaguar            | 24        | 0.31%   |
| Nehalem           | 20        | 0.26%   |
| Bobcat            | 16        | 0.21%   |
| Tremont           | 15        | 0.2%    |
| K10               | 13        | 0.17%   |
| Steamroller       | 9         | 0.12%   |
| K10 Llano         | 9         | 0.12%   |
| K8 & K10 hybrid   | 6         | 0.08%   |
| Bonnell           | 6         | 0.08%   |
| K8 Hammer         | 5         | 0.07%   |
| P6                | 3         | 0.04%   |
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
| Intel                            | 5753      | 57.39%  |
| Nvidia                           | 2384      | 23.78%  |
| AMD                              | 1885      | 18.8%   |
| Zhaoxin                          | 1         | 0.01%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 492       | 4.82%   |
| Intel UHD Graphics 620                                                                   | 470       | 4.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 423       | 4.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 345       | 3.38%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 329       | 3.22%   |
| Intel HD Graphics 620                                                                    | 324       | 3.17%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 323       | 3.16%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 313       | 3.07%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 305       | 2.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 273       | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 270       | 2.64%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 269       | 2.63%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 242       | 2.37%   |
| Intel HD Graphics 5500                                                                   | 223       | 2.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 202       | 1.98%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 196       | 1.92%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 170       | 1.66%   |
| AMD Lucienne                                                                             | 160       | 1.57%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 157       | 1.54%   |
| Intel HD Graphics 630                                                                    | 131       | 1.28%   |
| AMD Rembrandt [Radeon 680M]                                                              | 117       | 1.15%   |
| Intel HD Graphics 530                                                                    | 115       | 1.13%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 115       | 1.13%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 113       | 1.11%   |
| Intel Core Processor Integrated Graphics Controller                                      | 111       | 1.09%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 97        | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 96        | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 91        | 0.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 91        | 0.89%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 88        | 0.86%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 84        | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 77        | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 77        | 0.75%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 73        | 0.71%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 66        | 0.65%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 65        | 0.64%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 64        | 0.63%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 62        | 0.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 58        | 0.57%   |
| AMD Barcelo                                                                              | 55        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 3640      | 47.44%  |
| Intel + Nvidia     | 1815      | 23.65%  |
| 1 x AMD            | 1197      | 15.6%   |
| 1 x Nvidia         | 296       | 3.86%   |
| Intel + AMD        | 281       | 3.66%   |
| AMD + Nvidia       | 276       | 3.6%    |
| 2 x AMD            | 134       | 1.75%   |
| 2 x Intel          | 16        | 0.21%   |
| Other              | 11        | 0.14%   |
| 2 x Nvidia         | 3         | 0.04%   |
| Intel + 2 x Nvidia | 2         | 0.03%   |
| 1 x Zhaoxin        | 1         | 0.01%   |
| 1 x SiS            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 6562      | 84.81%  |
| Proprietary | 1053      | 13.61%  |
| Unknown     | 122       | 1.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 4759      | 60.97%  |
| 1.01-2.0   | 980       | 12.55%  |
| 0.01-0.5   | 849       | 10.88%  |
| 3.01-4.0   | 528       | 6.76%   |
| 0.51-1.0   | 425       | 5.44%   |
| 5.01-6.0   | 114       | 1.46%   |
| 7.01-8.0   | 99        | 1.27%   |
| 8.01-16.0  | 27        | 0.35%   |
| 2.01-3.0   | 25        | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1588      | 16.92%  |
| BOE                     | 1459      | 15.55%  |
| Chimei Innolux          | 1278      | 13.62%  |
| LG Display              | 1165      | 12.42%  |
| Samsung Electronics     | 746       | 7.95%   |
| Dell                    | 435       | 4.64%   |
| Sharp                   | 382       | 4.07%   |
| Goldstar                | 289       | 3.08%   |
| Apple                   | 223       | 2.38%   |
| Lenovo                  | 193       | 2.06%   |
| PANDA                   | 174       | 1.85%   |
| Hewlett-Packard         | 148       | 1.58%   |
| CSO                     | 114       | 1.21%   |
| Chi Mei Optoelectronics | 98        | 1.04%   |
| AOC                     | 96        | 1.02%   |
| Acer                    | 94        | 1%      |
| BenQ                    | 93        | 0.99%   |
| Philips                 | 91        | 0.97%   |
| InfoVision              | 88        | 0.94%   |
| Ancor Communications    | 66        | 0.7%    |
| Iiyama                  | 44        | 0.47%   |
| TMX                     | 40        | 0.43%   |
| ASUSTek Computer        | 38        | 0.4%    |
| ViewSonic               | 37        | 0.39%   |
| Panasonic               | 24        | 0.26%   |
| Sony                    | 22        | 0.23%   |
| Toshiba                 | 20        | 0.21%   |
| MSI                     | 19        | 0.2%    |
| LG Philips              | 19        | 0.2%    |
| JDI                     | 19        | 0.2%    |
| Gigabyte Technology     | 13        | 0.14%   |
| Sceptre Tech            | 11        | 0.12%   |
| CPT                     | 11        | 0.12%   |
| NEC Computers           | 10        | 0.11%   |
| Vizio                   | 9         | 0.1%    |
| HannStar                | 9         | 0.1%    |
| Eizo                    | 9         | 0.1%    |
| Fujitsu Siemens         | 8         | 0.09%   |
| Vestel Elektronik       | 7         | 0.07%   |
| Tianma XM               | 7         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 77        | 0.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 65        | 0.68%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 60        | 0.63%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 60        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 56        | 0.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 51        | 0.54%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 48        | 0.5%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 45        | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 43        | 0.45%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 43        | 0.45%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 42        | 0.44%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch       | 39        | 0.41%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch        | 38        | 0.4%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 37        | 0.39%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 34        | 0.36%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 33        | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch | 32        | 0.34%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 31        | 0.33%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 29        | 0.3%    |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 28        | 0.29%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                | 28        | 0.29%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                | 27        | 0.28%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 26        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 26        | 0.27%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 26        | 0.27%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 25        | 0.26%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch          | 25        | 0.26%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch          | 25        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 25        | 0.26%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch       | 25        | 0.26%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch       | 25        | 0.26%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 24        | 0.25%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 24        | 0.25%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 24        | 0.25%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 23        | 0.24%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch         | 23        | 0.24%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 23        | 0.24%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 23        | 0.24%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 23        | 0.24%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch       | 23        | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 4333      | 50.26%  |
| 1366x768 (WXGA)    | 1654      | 19.19%  |
| 3840x2160 (4K)     | 496       | 5.75%   |
| 2560x1440 (QHD)    | 368       | 4.27%   |
| 1600x900 (HD+)     | 284       | 3.29%   |
| 1920x1200 (WUXGA)  | 272       | 3.16%   |
| 2560x1600          | 195       | 2.26%   |
| 1280x800 (WXGA)    | 143       | 1.66%   |
| 2880x1800          | 123       | 1.43%   |
| 2560x1080          | 86        | 1%      |
| 1440x900 (WXGA+)   | 84        | 0.97%   |
| 3440x1440          | 81        | 0.94%   |
| 3840x2400          | 63        | 0.73%   |
| 2160x1440          | 55        | 0.64%   |
| 1680x1050 (WSXGA+) | 50        | 0.58%   |
| 2256x1504          | 46        | 0.53%   |
| 1280x1024 (SXGA)   | 38        | 0.44%   |
| 3200x1800 (QHD+)   | 37        | 0.43%   |
| 3000x2000          | 20        | 0.23%   |
| 1360x768           | 20        | 0.23%   |
| 3200x2000          | 17        | 0.2%    |
| 2520x1680          | 15        | 0.17%   |
| 2240x1400          | 14        | 0.16%   |
| 3072x1920          | 12        | 0.14%   |
| 1920x1280          | 12        | 0.14%   |
| 3456x2160          | 11        | 0.13%   |
| 2160x1350          | 10        | 0.12%   |
| 3840x1600          | 9         | 0.1%    |
| 2880x1620          | 8         | 0.09%   |
| 3840x1080          | 7         | 0.08%   |
| 1024x768 (XGA)     | 7         | 0.08%   |
| 1920x540           | 6         | 0.07%   |
| 1024x600           | 5         | 0.06%   |
| 3840x1100          | 4         | 0.05%   |
| Unknown            | 4         | 0.05%   |
| 2304x1440          | 3         | 0.03%   |
| 2288x1287          | 3         | 0.03%   |
| 1680x945           | 3         | 0.03%   |
| 800x1280           | 2         | 0.02%   |
| 2880x1920          | 2         | 0.02%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 3451      | 36.77%  |
| 13      | 1517      | 16.16%  |
| 14      | 1337      | 14.24%  |
| 17      | 448       | 4.77%   |
| 27      | 443       | 4.72%   |
| 24      | 415       | 4.42%   |
| 23      | 284       | 3.03%   |
| 12      | 238       | 2.54%   |
| 21      | 230       | 2.45%   |
| 16      | 190       | 2.02%   |
| 34      | 144       | 1.53%   |
| 31      | 96        | 1.02%   |
| 11      | 85        | 0.91%   |
| 18      | 79        | 0.84%   |
| 19      | 46        | 0.49%   |
| 20      | 40        | 0.43%   |
| 22      | 32        | 0.34%   |
| Unknown | 30        | 0.32%   |
| 40      | 27        | 0.29%   |
| 25      | 27        | 0.29%   |
| 84      | 23        | 0.25%   |
| 32      | 19        | 0.2%    |
| 28      | 18        | 0.19%   |
| 10      | 16        | 0.17%   |
| 54      | 15        | 0.16%   |
| 35      | 14        | 0.15%   |
| 26      | 14        | 0.15%   |
| 72      | 13        | 0.14%   |
| 29      | 13        | 0.14%   |
| 37      | 10        | 0.11%   |
| 48      | 7         | 0.07%   |
| 86      | 6         | 0.06%   |
| 42      | 5         | 0.05%   |
| 39      | 5         | 0.05%   |
| 74      | 4         | 0.04%   |
| 52      | 4         | 0.04%   |
| 33      | 4         | 0.04%   |
| 63      | 3         | 0.03%   |
| 57      | 3         | 0.03%   |
| 49      | 3         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 5651      | 60.89%  |
| 201-300        | 1077      | 11.6%   |
| 501-600        | 1056      | 11.38%  |
| 351-400        | 553       | 5.96%   |
| 401-500        | 402       | 4.33%   |
| 601-700        | 175       | 1.89%   |
| 701-800        | 170       | 1.83%   |
| 801-900        | 59        | 0.64%   |
| 1001-1500      | 52        | 0.56%   |
| 1501-2000      | 43        | 0.46%   |
| Unknown        | 30        | 0.32%   |
| 901-1000       | 8         | 0.09%   |
| More than 2000 | 2         | 0.02%   |
| 1-100          | 2         | 0.02%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 6492      | 81.56%  |
| 16/10   | 1023      | 12.85%  |
| 21/9    | 177       | 2.22%   |
| 3/2     | 165       | 2.07%   |
| 5/4     | 40        | 0.5%    |
| 4/3     | 16        | 0.2%    |
| Unknown | 13        | 0.16%   |
| 32/9    | 12        | 0.15%   |
| 0.56    | 7         | 0.09%   |
| 3.40    | 4         | 0.05%   |
| 6/5     | 2         | 0.03%   |
| 1.00    | 2         | 0.03%   |
| 0.67    | 2         | 0.03%   |
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
| 101-110        | 3455      | 36.9%   |
| 81-90          | 2287      | 24.43%  |
| 201-250        | 753       | 8.04%   |
| 71-80          | 548       | 5.85%   |
| 301-350        | 458       | 4.89%   |
| 121-130        | 407       | 4.35%   |
| 351-500        | 294       | 3.14%   |
| 61-70          | 227       | 2.42%   |
| 111-120        | 178       | 1.9%    |
| 251-300        | 170       | 1.82%   |
| 151-200        | 144       | 1.54%   |
| 51-60          | 89        | 0.95%   |
| 141-150        | 86        | 0.92%   |
| More than 1000 | 85        | 0.91%   |
| 501-1000       | 68        | 0.73%   |
| 131-140        | 36        | 0.38%   |
| Unknown        | 30        | 0.32%   |
| 91-100         | 27        | 0.29%   |
| 41-50          | 16        | 0.17%   |
| 1-40           | 4         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 4100      | 44.83%  |
| 101-120       | 2030      | 22.2%   |
| 51-100        | 1403      | 15.34%  |
| 161-240       | 1034      | 11.31%  |
| More than 240 | 482       | 5.27%   |
| 1-50          | 67        | 0.73%   |
| Unknown       | 30        | 0.33%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 5798      | 73.23%  |
| 2     | 1692      | 21.37%  |
| 3     | 228       | 2.88%   |
| 0     | 182       | 2.3%    |
| 4     | 15        | 0.19%   |
| 5     | 3         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 4591      | 39.64%  |
| Realtek Semiconductor             | 3817      | 32.96%  |
| Qualcomm Atheros                  | 1223      | 10.56%  |
| Broadcom                          | 533       | 4.6%    |
| MediaTek                          | 300       | 2.59%   |
| Broadcom Limited                  | 120       | 1.04%   |
| Lenovo                            | 105       | 0.91%   |
| ASIX Electronics                  | 90        | 0.78%   |
| TP-Link                           | 72        | 0.62%   |
| Sierra Wireless                   | 70        | 0.6%    |
| Qualcomm                          | 66        | 0.57%   |
| DisplayLink                       | 48        | 0.41%   |
| Dell                              | 48        | 0.41%   |
| Ralink                            | 46        | 0.4%    |
| Samsung Electronics               | 41        | 0.35%   |
| Ralink Technology                 | 40        | 0.35%   |
| Marvell Technology Group          | 39        | 0.34%   |
| Xiaomi                            | 32        | 0.28%   |
| Ericsson Business Mobile Networks | 31        | 0.27%   |
| Hewlett-Packard                   | 30        | 0.26%   |
| Nvidia                            | 24        | 0.21%   |
| Huawei Technologies               | 21        | 0.18%   |
| ASUSTek Computer                  | 17        | 0.15%   |
| Apple                             | 16        | 0.14%   |
| Google                            | 15        | 0.13%   |
| JMicron Technology                | 12        | 0.1%    |
| Fibocom                           | 11        | 0.09%   |
| OPPO Electronics                  | 10        | 0.09%   |
| NetGear                           | 10        | 0.09%   |
| Qualcomm Atheros Communications   | 9         | 0.08%   |
| D-Link                            | 8         | 0.07%   |
| T & A Mobile Phones               | 6         | 0.05%   |
| Microsoft                         | 6         | 0.05%   |
| Linksys                           | 6         | 0.05%   |
| D-Link System                     | 6         | 0.05%   |
| OnePlus Technology (Shenzhen)     | 5         | 0.04%   |
| Edimax Technology                 | 5         | 0.04%   |
| Motorola PCS                      | 4         | 0.03%   |
| Cypress Semiconductor             | 4         | 0.03%   |
| Shenzhen Goodix Technology        | 3         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2366      | 16.79%  |
| Intel Wi-Fi 6 AX200                                               | 525       | 3.73%   |
| Intel Wireless 8265 / 8275                                        | 482       | 3.42%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 474       | 3.36%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 432       | 3.07%   |
| Intel Wi-Fi 6 AX201                                               | 411       | 2.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 295       | 2.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 265       | 1.88%   |
| Intel Wireless 8260                                               | 260       | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 259       | 1.84%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 251       | 1.78%   |
| Intel Wireless 7260                                               | 241       | 1.71%   |
| Intel Wireless 7265                                               | 234       | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 226       | 1.6%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 207       | 1.47%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 199       | 1.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 198       | 1.41%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 192       | 1.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 192       | 1.36%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 190       | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 184       | 1.31%   |
| Intel Ethernet Connection (4) I219-LM                             | 181       | 1.28%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 155       | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 148       | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 130       | 0.92%   |
| Intel Wireless 3165                                               | 122       | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 118       | 0.84%   |
| Intel Ethernet Connection (4) I219-V                              | 107       | 0.76%   |
| Intel Wireless-AC 9260                                            | 101       | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 98        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 96        | 0.68%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 95        | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 89        | 0.63%   |
| Intel Ethernet Connection I218-LM                                 | 86        | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 85        | 0.6%    |
| Broadcom BCM43142 802.11b/g/n                                     | 84        | 0.6%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 82        | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 82        | 0.58%   |
| Intel Centrino Ultimate-N 6300                                    | 77        | 0.55%   |
| Intel Ethernet Connection (6) I219-V                              | 76        | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 4467      | 56.82%  |
| Realtek Semiconductor                 | 1092      | 13.89%  |
| Qualcomm Atheros                      | 1071      | 13.62%  |
| Broadcom                              | 448       | 5.7%    |
| MediaTek                              | 293       | 3.73%   |
| Broadcom Limited                      | 95        | 1.21%   |
| Sierra Wireless                       | 70        | 0.89%   |
| TP-Link                               | 53        | 0.67%   |
| Qualcomm                              | 50        | 0.64%   |
| Ralink                                | 46        | 0.59%   |
| Ralink Technology                     | 40        | 0.51%   |
| Dell                                  | 36        | 0.46%   |
| ASUSTek Computer                      | 16        | 0.2%    |
| Fibocom                               | 11        | 0.14%   |
| Qualcomm Atheros Communications       | 9         | 0.11%   |
| NetGear                               | 9         | 0.11%   |
| Hewlett-Packard                       | 9         | 0.11%   |
| Ericsson Business Mobile Networks     | 9         | 0.11%   |
| D-Link System                         | 6         | 0.08%   |
| Linksys                               | 5         | 0.06%   |
| Edimax Technology                     | 5         | 0.06%   |
| D-Link                                | 5         | 0.06%   |
| Microsoft                             | 4         | 0.05%   |
| Quectel Wireless Solutions            | 2         | 0.03%   |
| Belkin Components                     | 2         | 0.03%   |
| ZyDAS                                 | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |
| Sitecom Europe                        | 1         | 0.01%   |
| Qualcomm Technologies                 | 1         | 0.01%   |
| IMC Networks                          | 1         | 0.01%   |
| AVM                                   | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |
| Unknown                               | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 525       | 6.64%   |
| Intel Wireless 8265 / 8275                                     | 482       | 6.1%    |
| Intel Wi-Fi 6 AX201                                            | 411       | 5.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 295       | 3.73%   |
| Intel Wireless 8260                                            | 260       | 3.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 259       | 3.28%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 251       | 3.18%   |
| Intel Wireless 7260                                            | 241       | 3.05%   |
| Intel Wireless 7265                                            | 234       | 2.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 226       | 2.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 205       | 2.59%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 199       | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 198       | 2.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 192       | 2.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 192       | 2.43%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 190       | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 184       | 2.33%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 155       | 1.96%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 148       | 1.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 130       | 1.64%   |
| Intel Wireless 3165                                            | 122       | 1.54%   |
| Intel Wireless-AC 9260                                         | 101       | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 98        | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 96        | 1.21%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 95        | 1.2%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 89        | 1.13%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 85        | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                  | 84        | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 82        | 1.04%   |
| Intel Centrino Ultimate-N 6300                                 | 77        | 0.97%   |
| Intel Wireless 3160                                            | 75        | 0.95%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 71        | 0.9%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 71        | 0.9%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 64        | 0.81%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 60        | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 55        | 0.7%    |
| Intel Centrino Advanced-N 6235                                 | 53        | 0.67%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 53        | 0.67%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 45        | 0.57%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 45        | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 3351      | 55.87%  |
| Intel                                  | 1667      | 27.79%  |
| Qualcomm Atheros                       | 255       | 4.25%   |
| Broadcom                               | 172       | 2.87%   |
| Lenovo                                 | 103       | 1.72%   |
| ASIX Electronics                       | 90        | 1.5%    |
| DisplayLink                            | 48        | 0.8%    |
| Samsung Electronics                    | 41        | 0.68%   |
| Marvell Technology Group               | 39        | 0.65%   |
| Xiaomi                                 | 32        | 0.53%   |
| Broadcom Limited                       | 25        | 0.42%   |
| Nvidia                                 | 24        | 0.4%    |
| TP-Link                                | 21        | 0.35%   |
| Qualcomm                               | 16        | 0.27%   |
| Apple                                  | 16        | 0.27%   |
| Google                                 | 15        | 0.25%   |
| Huawei Technologies                    | 13        | 0.22%   |
| JMicron Technology                     | 12        | 0.2%    |
| OPPO Electronics                       | 10        | 0.17%   |
| MediaTek                               | 7         | 0.12%   |
| Hewlett-Packard                        | 7         | 0.12%   |
| OnePlus Technology (Shenzhen)          | 4         | 0.07%   |
| Cypress Semiconductor                  | 4         | 0.07%   |
| T & A Mobile Phones                    | 3         | 0.05%   |
| D-Link                                 | 3         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 2         | 0.03%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.03%   |
| Microsoft                              | 2         | 0.03%   |
| ICS Advent                             | 2         | 0.03%   |
| vivo                                   | 1         | 0.02%   |
| Spreadtrum Communications              | 1         | 0.02%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.02%   |
| Novatel Wireless                       | 1         | 0.02%   |
| NetGear                                | 1         | 0.02%   |
| Motorola PCS                           | 1         | 0.02%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2366      | 38.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 474       | 7.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 432       | 7.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 265       | 4.34%   |
| Intel Ethernet Connection (4) I219-LM                             | 181       | 2.97%   |
| Intel Ethernet Connection I219-LM                                 | 118       | 1.93%   |
| Intel Ethernet Connection (4) I219-V                              | 107       | 1.75%   |
| Intel Ethernet Connection I218-LM                                 | 86        | 1.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 82        | 1.34%   |
| Intel Ethernet Connection (6) I219-V                              | 76        | 1.25%   |
| Intel Ethernet Connection I217-LM                                 | 75        | 1.23%   |
| Intel Ethernet Connection (3) I218-LM                             | 75        | 1.23%   |
| Intel Ethernet Connection (6) I219-LM                             | 62        | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                             | 61        | 1%      |
| Intel Ethernet Connection (10) I219-V                             | 61        | 1%      |
| Realtek RTL8125 2.5GbE Controller                                 | 52        | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 51        | 0.84%   |
| Intel 82577LM Gigabit Network Connection                          | 49        | 0.8%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 45        | 0.74%   |
| Intel Ethernet Connection (2) I219-LM                             | 44        | 0.72%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 41        | 0.67%   |
| Intel Ethernet Connection I219-V                                  | 41        | 0.67%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 38        | 0.62%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 36        | 0.59%   |
| Intel Ethernet Connection (13) I219-V                             | 36        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 35        | 0.57%   |
| Intel Ethernet Connection (16) I219-V                             | 34        | 0.56%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 33        | 0.54%   |
| Intel Ethernet Connection (7) I219-V                              | 30        | 0.49%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 29        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 27        | 0.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 27        | 0.44%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 26        | 0.43%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 25        | 0.41%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 25        | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 24        | 0.39%   |
| Intel 82567LM Gigabit Network Connection                          | 24        | 0.39%   |
| Nvidia MCP79 Ethernet                                             | 21        | 0.34%   |
| Intel Ethernet Connection I217-V                                  | 21        | 0.34%   |
| Intel Ethernet Connection (10) I219-LM                            | 20        | 0.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 7498      | 56.72%  |
| Ethernet | 5634      | 42.62%  |
| Modem    | 73        | 0.55%   |
| Unknown  | 14        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 6483      | 79.79%  |
| Ethernet | 1640      | 20.18%  |
| Modem    | 2         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 5008      | 65.47%  |
| 1     | 2407      | 31.47%  |
| 0     | 148       | 1.93%   |
| 3     | 86        | 1.12%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Notebooks | Percent |
|---------|-----------|---------|
| No      | 6179      | 79.2%   |
| Yes     | 1620      | 20.76%  |
| Unknown | 3         | 0.04%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 3737      | 57.28%  |
| Realtek Semiconductor           | 656       | 10.06%  |
| Qualcomm Atheros Communications | 542       | 8.31%   |
| IMC Networks                    | 284       | 4.35%   |
| Foxconn / Hon Hai               | 261       | 4%      |
| Broadcom                        | 258       | 3.95%   |
| Lite-On Technology              | 227       | 3.48%   |
| Apple                           | 187       | 2.87%   |
| Realtek                         | 80        | 1.23%   |
| Dell                            | 46        | 0.71%   |
| Cambridge Silicon Radio         | 45        | 0.69%   |
| Hewlett-Packard                 | 35        | 0.54%   |
| Ralink                          | 32        | 0.49%   |
| Toshiba                         | 28        | 0.43%   |
| ASUSTek Computer                | 20        | 0.31%   |
| USI                             | 19        | 0.29%   |
| Foxconn International           | 15        | 0.23%   |
| MediaTek                        | 14        | 0.21%   |
| Opticis                         | 12        | 0.18%   |
| Ralink Technology               | 4         | 0.06%   |
| Smart Modular Technologies      | 3         | 0.05%   |
| Chicony Electronics             | 3         | 0.05%   |
| Askey Computer                  | 3         | 0.05%   |
| Alps Electric                   | 3         | 0.05%   |
| Taiyo Yuden                     | 2         | 0.03%   |
| Qcom                            | 2         | 0.03%   |
| TP-Link                         | 1         | 0.02%   |
| Syntek                          | 1         | 0.02%   |
| Micro Star International        | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Corsair                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1294      | 19.81%  |
| Intel AX201 Bluetooth                               | 813       | 12.45%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 569       | 8.71%   |
| Intel AX200 Bluetooth                               | 513       | 7.85%   |
| Realtek Bluetooth Radio                             | 428       | 6.55%   |
| Qualcomm Atheros  Bluetooth Device                  | 314       | 4.81%   |
| Intel Bluetooth Device                              | 209       | 3.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 141       | 2.16%   |
| Intel AX210 Bluetooth                               | 124       | 1.9%    |
| Apple Bluetooth Host Controller                     | 123       | 1.88%   |
| IMC Networks Wireless_Device                        | 119       | 1.82%   |
| Foxconn / Hon Hai Wireless_Device                   | 112       | 1.71%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 90        | 1.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 88        | 1.35%   |
| IMC Networks Bluetooth Radio                        | 86        | 1.32%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 83        | 1.27%   |
| Realtek Bluetooth Radio                             | 80        | 1.22%   |
| Foxconn / Hon Hai Bluetooth Device                  | 78        | 1.19%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 77        | 1.18%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 57        | 0.87%   |
| Lite-On Bluetooth Device                            | 53        | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 51        | 0.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 51        | 0.78%   |
| Apple Bluetooth USB Host Controller                 | 46        | 0.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 45        | 0.69%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 44        | 0.67%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 44        | 0.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 0.6%    |
| IMC Networks Bluetooth Device                       | 38        | 0.58%   |
| Ralink RT3290 Bluetooth                             | 32        | 0.49%   |
| Lite-On Wireless_Device                             | 30        | 0.46%   |
| Lite-On Atheros AR3012 Bluetooth                    | 30        | 0.46%   |
| HP Broadcom 2070 Bluetooth Combo                    | 26        | 0.4%    |
| Realtek RTL8723B Bluetooth                          | 23        | 0.35%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 23        | 0.35%   |
| Dell DW375 Bluetooth Module                         | 21        | 0.32%   |
| USI Bluetooth Device                                | 19        | 0.29%   |
| Dell BCM20702A0 Bluetooth Module                    | 19        | 0.29%   |
| Broadcom HP Portable SoftSailing                    | 19        | 0.29%   |
| Broadcom HP Portable Bumble Bee                     | 19        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                      | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 5944      | 60.31%  |
| AMD                         | 1633      | 16.57%  |
| Nvidia                      | 1318      | 13.37%  |
| Lenovo                      | 127       | 1.29%   |
| C-Media Electronics         | 99        | 1%      |
| Realtek Semiconductor       | 91        | 0.92%   |
| Logitech                    | 75        | 0.76%   |
| GN Netcom                   | 69        | 0.7%    |
| Plantronics                 | 41        | 0.42%   |
| JMTek                       | 33        | 0.33%   |
| Hewlett-Packard             | 32        | 0.32%   |
| Kingston Technology         | 22        | 0.22%   |
| Texas Instruments           | 19        | 0.19%   |
| Creative Technology         | 18        | 0.18%   |
| SteelSeries ApS             | 16        | 0.16%   |
| Apple                       | 16        | 0.16%   |
| Sony                        | 15        | 0.15%   |
| Razer USA                   | 14        | 0.14%   |
| Corsair                     | 13        | 0.13%   |
| ASUSTek Computer            | 13        | 0.13%   |
| Dell                        | 12        | 0.12%   |
| Generalplus Technology      | 11        | 0.11%   |
| Sennheiser Communications   | 10        | 0.1%    |
| Focusrite-Novation          | 10        | 0.1%    |
| Blue Microphones            | 10        | 0.1%    |
| Samson Technologies         | 9         | 0.09%   |
| RODE Microphones            | 9         | 0.09%   |
| Microsoft                   | 9         | 0.09%   |
| Conexant Systems            | 8         | 0.08%   |
| Samsung Electronics         | 7         | 0.07%   |
| No brand                    | 7         | 0.07%   |
| XMOS                        | 6         | 0.06%   |
| CMX Systems                 | 6         | 0.06%   |
| Tenx Technology             | 5         | 0.05%   |
| SAVITECH                    | 5         | 0.05%   |
| GYROCOM C&C                 | 5         | 0.05%   |
| FiiO Electronics Technology | 5         | 0.05%   |
| DSEA A/S                    | 5         | 0.05%   |
| Yamaha                      | 4         | 0.04%   |
| PreSonus Audio Electronics  | 4         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1252      | 10.42%  |
| Intel Sunrise Point-LP HD Audio                                            | 1173      | 9.76%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 694       | 5.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 537       | 4.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 501       | 4.17%   |
| Intel Cannon Lake PCH cAVS                                                 | 393       | 3.27%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 334       | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 320       | 2.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 305       | 2.54%   |
| Intel Comet Lake PCH-LP cAVS                                               | 291       | 2.42%   |
| Intel Haswell-ULT HD Audio Controller                                      | 277       | 2.31%   |
| Intel 8 Series HD Audio Controller                                         | 277       | 2.31%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 264       | 2.2%    |
| Intel Broadwell-U Audio Controller                                         | 263       | 2.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 260       | 2.16%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 241       | 2.01%   |
| Intel Comet Lake PCH cAVS                                                  | 218       | 1.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 196       | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 191       | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 166       | 1.38%   |
| Intel CM238 HD Audio Controller                                            | 155       | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                            | 154       | 1.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 138       | 1.15%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 137       | 1.14%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 137       | 1.14%   |
| AMD FCH Azalia Controller                                                  | 124       | 1.03%   |
| Nvidia Audio device                                                        | 116       | 0.97%   |
| Nvidia GA106 High Definition Audio Controller                              | 112       | 0.93%   |
| AMD Kabini HDMI/DP Audio                                                   | 98        | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 96        | 0.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 92        | 0.77%   |
| Realtek Semiconductor USB Audio                                            | 90        | 0.75%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 89        | 0.74%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 87        | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                              | 77        | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                         | 71        | 0.59%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 70        | 0.58%   |
| Nvidia TU116 High Definition Audio Controller                              | 67        | 0.56%   |
| Nvidia GA104 High Definition Audio Controller                              | 66        | 0.55%   |
| Nvidia GP106 High Definition Audio Controller                              | 53        | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1410      | 30.11%  |
| SK hynix            | 1046      | 22.34%  |
| Micron Technology   | 680       | 14.52%  |
| Kingston            | 377       | 8.05%   |
| Crucial             | 266       | 5.68%   |
| Unknown             | 232       | 4.95%   |
| Ramaxel Technology  | 109       | 2.33%   |
| A-DATA Technology   | 102       | 2.18%   |
| Corsair             | 63        | 1.35%   |
| Elpida              | 43        | 0.92%   |
| Smart               | 33        | 0.7%    |
| Unknown             | 31        | 0.66%   |
| G.Skill             | 29        | 0.62%   |
| Unknown (ABCD)      | 28        | 0.6%    |
| Team                | 26        | 0.56%   |
| Nanya Technology    | 22        | 0.47%   |
| Patriot             | 20        | 0.43%   |
| Teikon              | 16        | 0.34%   |
| Smart Brazil        | 13        | 0.28%   |
| Transcend           | 11        | 0.23%   |
| GOODRAM             | 11        | 0.23%   |
| Avant               | 9         | 0.19%   |
| Timetec             | 5         | 0.11%   |
| Silicon Power       | 5         | 0.11%   |
| Goldkey             | 5         | 0.11%   |
| Apacer              | 5         | 0.11%   |
| V-GeN               | 4         | 0.09%   |
| PUSKILL             | 4         | 0.09%   |
| Lexar               | 4         | 0.09%   |
| Kllisre             | 4         | 0.09%   |
| CSX                 | 4         | 0.09%   |
| 4ea5                | 4         | 0.09%   |
| PNY                 | 3         | 0.06%   |
| OnBoard             | 3         | 0.06%   |
| ChangXin Memory     | 3         | 0.06%   |
| Unknown (0x0B5E)    | 2         | 0.04%   |
| SHARETRONIC         | 2         | 0.04%   |
| Sesame              | 2         | 0.04%   |
| RZX                 | 2         | 0.04%   |
| Qumo                | 2         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 83        | 1.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 75        | 1.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 65        | 1.32%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 59        | 1.2%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 47        | 0.96%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 44        | 0.89%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 42        | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 41        | 0.83%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 40        | 0.81%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 36        | 0.73%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 36        | 0.73%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 34        | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 33        | 0.67%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 32        | 0.65%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 31        | 0.63%   |
| Unknown                                                          | 31        | 0.63%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 30        | 0.61%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 30        | 0.61%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 29        | 0.59%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 29        | 0.59%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 28        | 0.57%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 27        | 0.55%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 27        | 0.55%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 27        | 0.55%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 27        | 0.55%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 27        | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 27        | 0.55%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 26        | 0.53%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 26        | 0.53%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 26        | 0.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 25        | 0.51%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 25        | 0.51%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 24        | 0.49%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.49%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 24        | 0.49%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 23        | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 23        | 0.47%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 23        | 0.47%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 23        | 0.47%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 22        | 0.45%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 2241      | 57.39%  |
| DDR3    | 956       | 24.48%  |
| LPDDR4  | 213       | 5.45%   |
| LPDDR3  | 208       | 5.33%   |
| LPDDR5  | 111       | 2.84%   |
| DDR5    | 89        | 2.28%   |
| DDR2    | 47        | 1.2%    |
| SDRAM   | 22        | 0.56%   |
| Unknown | 14        | 0.36%   |
| DDR     | 3         | 0.08%   |
| DRAM    | 1         | 0.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 3303      | 83.01%  |
| Row Of Chips | 581       | 14.6%   |
| Chip         | 49        | 1.23%   |
| Unknown      | 26        | 0.65%   |
| DIMM         | 20        | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 1863      | 43.66%  |
| 4096  | 1058      | 24.79%  |
| 16384 | 814       | 19.08%  |
| 2048  | 310       | 7.27%   |
| 32768 | 168       | 3.94%   |
| 1024  | 49        | 1.15%   |
| 3072  | 2         | 0.05%   |
| 12288 | 1         | 0.02%   |
| 512   | 1         | 0.02%   |
| 64    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 1029      | 24.49%  |
| 2667    | 978       | 23.28%  |
| 1600    | 688       | 16.38%  |
| 2400    | 290       | 6.9%    |
| 2133    | 276       | 6.57%   |
| 1333    | 118       | 2.81%   |
| 1334    | 111       | 2.64%   |
| 6400    | 106       | 2.52%   |
| 4267    | 103       | 2.45%   |
| 1867    | 88        | 2.09%   |
| 4800    | 84        | 2%      |
| 3266    | 59        | 1.4%    |
| 1067    | 44        | 1.05%   |
| Unknown | 31        | 0.74%   |
| 4266    | 30        | 0.71%   |
| 8400    | 29        | 0.69%   |
| 667     | 29        | 0.69%   |
| 1066    | 18        | 0.43%   |
| 4199    | 16        | 0.38%   |
| 3733    | 16        | 0.38%   |
| 800     | 15        | 0.36%   |
| 5600    | 11        | 0.26%   |
| 975     | 5         | 0.12%   |
| 2933    | 4         | 0.1%    |
| 2048    | 4         | 0.1%    |
| 7467    | 3         | 0.07%   |
| 5500    | 3         | 0.07%   |
| 1866    | 2         | 0.05%   |
| 533     | 2         | 0.05%   |
| 7500    | 1         | 0.02%   |
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
| Hewlett-Packard               | 14        | 29.79%  |
| Canon                         | 8         | 17.02%  |
| Samsung Electronics           | 6         | 12.77%  |
| Brother Industries            | 6         | 12.77%  |
| Seiko Epson                   | 5         | 10.64%  |
| Prolific Technology           | 2         | 4.26%   |
| STMicroelectronics            | 1         | 2.13%   |
| Samsung Info. Systems America | 1         | 2.13%   |
| Ricoh                         | 1         | 2.13%   |
| Pantum                        | 1         | 2.13%   |
| NXP Semiconductors            | 1         | 2.13%   |
| MiiiW                         | 1         | 2.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 2         | 4.26%   |
| Prolific PL2305 Parallel Port                                         | 2         | 4.26%   |
| HP LaserJet P1102                                                     | 2         | 4.26%   |
| Brother DCP-1600                                                      | 2         | 4.26%   |
| STMicroelectronics USB Printing Support                               | 1         | 2.13%   |
| Seiko Epson WF-2830 Series                                            | 1         | 2.13%   |
| Seiko Epson L200 Series                                               | 1         | 2.13%   |
| Seiko Epson ET-2710 Series                                            | 1         | 2.13%   |
| Samsung Info. Systems America SAMSUNG SRP-270                         | 1         | 2.13%   |
| Samsung SCX-4200 series                                               | 1         | 2.13%   |
| Samsung SCX-3200 Series                                               | 1         | 2.13%   |
| Samsung ML-331x Series Laser Printer                                  | 1         | 2.13%   |
| Samsung M2070 Series                                                  | 1         | 2.13%   |
| Samsung CLX-6260 Series                                               | 1         | 2.13%   |
| Samsung C43x Series                                                   | 1         | 2.13%   |
| Ricoh SP 210SU                                                        | 1         | 2.13%   |
| Pantum P2500W series                                                  | 1         | 2.13%   |
| NXP Semiconductors Printer-80                                         | 1         | 2.13%   |
| MiiiW MW USB Receiver                                                 | 1         | 2.13%   |
| HP Photosmart B010 series                                             | 1         | 2.13%   |
| HP Officejet 2620 series                                              | 1         | 2.13%   |
| HP LaserJet 400 colorMFP M475dw                                       | 1         | 2.13%   |
| HP LaserJet 1010                                                      | 1         | 2.13%   |
| HP Ink Tank 310 series                                                | 1         | 2.13%   |
| HP ENVY Pro 6400 series                                               | 1         | 2.13%   |
| HP ENVY 4500 series                                                   | 1         | 2.13%   |
| HP Deskjet 3510 series                                                | 1         | 2.13%   |
| HP Deskjet 3050A                                                      | 1         | 2.13%   |
| HP DeskJet 2600 series                                                | 1         | 2.13%   |
| HP DeskJet 2300 series                                                | 1         | 2.13%   |
| HP DeskJet 2130 series                                                | 1         | 2.13%   |
| Canon TR8500 series                                                   | 1         | 2.13%   |
| Canon TR150 series                                                    | 1         | 2.13%   |
| Canon PIXMA MG3600 Series                                             | 1         | 2.13%   |
| Canon PIXMA MG3500 Series                                             | 1         | 2.13%   |
| Canon PIXMA MG3000 series                                             | 1         | 2.13%   |
| Canon MF3110                                                          | 1         | 2.13%   |
| Canon MF220 Series                                                    | 1         | 2.13%   |
| Canon iP7200 series                                                   | 1         | 2.13%   |
| Brother Printer                                                       | 1         | 2.13%   |

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
| Chicony Electronics                    | 1668      | 23.34%  |
| IMC Networks                           | 884       | 12.37%  |
| Microdia                               | 631       | 8.83%   |
| Realtek Semiconductor                  | 582       | 8.14%   |
| Bison Electronics                      | 487       | 6.82%   |
| Quanta                                 | 447       | 6.26%   |
| Sunplus Innovation Technology          | 379       | 5.3%    |
| Cheng Uei Precision Industry (Foxlink) | 285       | 3.99%   |
| Syntek                                 | 206       | 2.88%   |
| Lite-On Technology                     | 194       | 2.71%   |
| Acer                                   | 191       | 2.67%   |
| Apple                                  | 174       | 2.43%   |
| Logitech                               | 165       | 2.31%   |
| Luxvisions Innotech Limited            | 136       | 1.9%    |
| Suyin                                  | 111       | 1.55%   |
| Silicon Motion                         | 84        | 1.18%   |
| Sonix Technology                       | 70        | 0.98%   |
| Alcor Micro                            | 50        | 0.7%    |
| Samsung Electronics                    | 46        | 0.64%   |
| Ricoh                                  | 39        | 0.55%   |
| Lenovo                                 | 25        | 0.35%   |
| SunplusIT                              | 23        | 0.32%   |
| Primax Electronics                     | 23        | 0.32%   |
| Microsoft                              | 18        | 0.25%   |
| Importek                               | 18        | 0.25%   |
| Z-Star Microelectronics                | 12        | 0.17%   |
| ShineTech                              | 10        | 0.14%   |
| Shenzhen Kingcome Optoelectronic       | 9         | 0.13%   |
| icSpring                               | 9         | 0.13%   |
| Generalplus Technology                 | 9         | 0.13%   |
| ALi                                    | 9         | 0.13%   |
| ARC International                      | 8         | 0.11%   |
| MacroSilicon                           | 7         | 0.1%    |
| 8SSC21D67422V1SR28902JL                | 7         | 0.1%    |
| KYE Systems (Mouse Systems)            | 6         | 0.08%   |
| Intel                                  | 6         | 0.08%   |
| Creative Technology                    | 6         | 0.08%   |
| WaveRider Communications               | 5         | 0.07%   |
| Razer USA                              | 5         | 0.07%   |
| Pixart Imaging                         | 5         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 576       | 8%      |
| Microdia Integrated_Webcam_HD                       | 368       | 5.11%   |
| IMC Networks Integrated Camera                      | 345       | 4.79%   |
| Realtek Integrated_Webcam_HD                        | 261       | 3.63%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 235       | 3.26%   |
| Sunplus Integrated_Webcam_HD                        | 158       | 2.19%   |
| Chicony HD Webcam                                   | 153       | 2.13%   |
| Syntek Integrated Camera                            | 142       | 1.97%   |
| Bison Integrated Camera                             | 130       | 1.81%   |
| Chicony Integrated Camera (1280x720@30)             | 95        | 1.32%   |
| Quanta HD User Facing                               | 94        | 1.31%   |
| Lite-On Integrated Camera                           | 93        | 1.29%   |
| Acer Integrated Camera                              | 89        | 1.24%   |
| Chicony HP HD Camera                                | 73        | 1.01%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 70        | 0.97%   |
| Bison SunplusIT Integrated Camera                   | 69        | 0.96%   |
| Quanta HP TrueVision HD Camera                      | 58        | 0.81%   |
| Bison HD Webcam                                     | 55        | 0.76%   |
| Chicony USB2.0 Camera                               | 52        | 0.72%   |
| Quanta HP HD Camera                                 | 51        | 0.71%   |
| Bison Lenovo EasyCamera                             | 51        | 0.71%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 51        | 0.71%   |
| Apple FaceTime HD Camera                            | 50        | 0.69%   |
| IMC Networks HD Camera                              | 49        | 0.68%   |
| Chicony HP TrueVision HD Camera                     | 49        | 0.68%   |
| Samsung Galaxy series, misc. (MTP mode)             | 46        | 0.64%   |
| Microdia Integrated Webcam                          | 46        | 0.64%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 43        | 0.6%    |
| Quanta HP Wide Vision HD Camera                     | 42        | 0.58%   |
| Lite-On HP HD Camera                                | 41        | 0.57%   |
| Chicony HP Wide Vision HD Camera                    | 41        | 0.57%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 40        | 0.56%   |
| Sunplus HD WebCam                                   | 39        | 0.54%   |
| Realtek Integrated Webcam                           | 39        | 0.54%   |
| Quanta HD Webcam                                    | 39        | 0.54%   |
| IMC Networks ov9734_azurewave_camera                | 39        | 0.54%   |
| Chicony HD User Facing                              | 39        | 0.54%   |
| Logitech HD Pro Webcam C920                         | 38        | 0.53%   |
| Sonix USB2.0 HD UVC WebCam                          | 37        | 0.51%   |
| Realtek USB Camera                                  | 37        | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 634       | 35.05%  |
| Validity Sensors                   | 530       | 29.3%   |
| Shenzhen Goodix Technology         | 328       | 18.13%  |
| Elan Microelectronics              | 112       | 6.19%   |
| Upek                               | 64        | 3.54%   |
| LighTuning Technology              | 57        | 3.15%   |
| AuthenTec                          | 43        | 2.38%   |
| Realtek USB2.0 Finger Print Bridge | 19        | 1.05%   |
| Samsung Electronics                | 11        | 0.61%   |
| STMicroelectronics                 | 5         | 0.28%   |
| Focal-systems.Corp                 | 5         | 0.28%   |
| Dell                               | 1         | 0.06%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 295       | 16.3%   |
| Shenzhen Goodix  Fingerprint Device                                        | 209       | 11.55%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 120       | 6.63%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 112       | 6.19%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 100       | 5.52%   |
| Shenzhen Goodix FingerPrint                                                | 64        | 3.54%   |
| Validity Sensors Synaptics WBDI                                            | 61        | 3.37%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 60        | 3.31%   |
| Elan ELAN:Fingerprint                                                      | 60        | 3.31%   |
| Shenzhen Goodix Fingerprint Reader                                         | 55        | 3.04%   |
| Elan ELAN:ARM-M4                                                           | 50        | 2.76%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 49        | 2.71%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 44        | 2.43%   |
| Synaptics Fingerprint reader [HP G6]                                       | 41        | 2.27%   |
| Validity Sensors VFS491                                                    | 30        | 1.66%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 30        | 1.66%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 29        | 1.6%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 27        | 1.49%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 27        | 1.49%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 25        | 1.38%   |
| Synaptics UWP WBDI Device                                                  | 23        | 1.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 23        | 1.27%   |
| Synaptics  WBDI                                                            | 22        | 1.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 21        | 1.16%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 19        | 1.05%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 0.99%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 17        | 0.94%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 15        | 0.83%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 0.77%   |
| Synaptics WBDI                                                             | 14        | 0.77%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 0.66%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 9         | 0.5%    |
| AuthenTec AES2810                                                          | 9         | 0.5%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 0.5%    |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.44%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.39%   |
| Synaptics TouchPad                                                         | 7         | 0.39%   |
| Unknown                                                                    | 7         | 0.39%   |
| Synaptics WBDI Device                                                      | 6         | 0.33%   |
| Synaptics UWP WBDI                                                         | 6         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 290       | 42.27%  |
| Alcor Micro                | 275       | 40.09%  |
| Upek                       | 41        | 5.98%   |
| Lenovo                     | 34        | 4.96%   |
| O2 Micro                   | 15        | 2.19%   |
| Gemalto (was Gemplus)      | 7         | 1.02%   |
| Aladdin Knowledge Systems  | 4         | 0.58%   |
| Yubico.com                 | 3         | 0.44%   |
| SCM Microsystems           | 3         | 0.44%   |
| Realtek Semiconductor      | 3         | 0.44%   |
| OmniKey                    | 3         | 0.44%   |
| Advanced Card Systems      | 2         | 0.29%   |
| Reiner SCT Kartensysteme   | 1         | 0.15%   |
| Purism, SPC                | 1         | 0.15%   |
| Hewlett-Packard            | 1         | 0.15%   |
| Chicony Electronics        | 1         | 0.15%   |
| Bit4id                     | 1         | 0.15%   |
| Athena Smartcard Solutions | 1         | 0.15%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 274       | 39.94%  |
| Broadcom 5880                                                                | 94        | 13.7%   |
| Broadcom 58200                                                               | 85        | 12.39%  |
| Broadcom BCM5880 Secure Applications Processor                               | 64        | 9.33%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 45        | 6.56%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 41        | 5.98%   |
| Lenovo Integrated Smart Card Reader                                          | 33        | 4.81%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 12        | 1.75%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 6         | 0.87%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 0.58%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.44%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 0.44%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.44%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.29%   |
| Advanced Card Systems ACR39U                                                 | 2         | 0.29%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.15%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.15%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.15%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.15%   |
| Purism, SPC Librem Key                                                       | 1         | 0.15%   |
| OmniKey CardMan 4321                                                         | 1         | 0.15%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.15%   |
| OmniKey CardMan 1021                                                         | 1         | 0.15%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.15%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.15%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.15%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.15%   |
| Bit4id miniLector EVO                                                        | 1         | 0.15%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.15%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 0.15%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 4557      | 57.86%  |
| 1     | 2723      | 34.57%  |
| 2     | 504       | 6.4%    |
| 3     | 64        | 0.81%   |
| 4     | 10        | 0.13%   |
| 5     | 7         | 0.09%   |
| 6     | 5         | 0.06%   |
| 7     | 4         | 0.05%   |
| 8     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1789      | 45.77%  |
| Graphics card            | 785       | 20.08%  |
| Multimedia controller    | 401       | 10.26%  |
| Net/wireless             | 284       | 7.27%   |
| Chipcard                 | 218       | 5.58%   |
| Camera                   | 141       | 3.61%   |
| Bluetooth                | 80        | 2.05%   |
| Storage                  | 55        | 1.41%   |
| Card reader              | 51        | 1.3%    |
| Sound                    | 34        | 0.87%   |
| Net/ethernet             | 21        | 0.54%   |
| Communication controller | 18        | 0.46%   |
| Network                  | 17        | 0.43%   |
| Modem                    | 10        | 0.26%   |
| Flash memory             | 2         | 0.05%   |
| Video                    | 1         | 0.03%   |
| Firewire controller      | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

