Fedora 38 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Fedora 38.

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

Total: 2280

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad E15 20RD0011IX     | [88cc97d0be](https://linux-hardware.org/?probe=88cc97d0be) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | [f09ace6b9d](https://linux-hardware.org/?probe=f09ace6b9d) | Nov 06, 2023 |
| HP            | G61                         | [65f7664fe3](https://linux-hardware.org/?probe=65f7664fe3) | Nov 06, 2023 |
| Samsung       | 550P5C/550P7C               | [f87e3a97c4](https://linux-hardware.org/?probe=f87e3a97c4) | Nov 06, 2023 |
| Acer          | Aspire A315-53              | [3daa9909b3](https://linux-hardware.org/?probe=3daa9909b3) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | [d643312744](https://linux-hardware.org/?probe=d643312744) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [d61e270082](https://linux-hardware.org/?probe=d61e270082) | Nov 06, 2023 |
| ASUSTek       | X550WA                      | [8c15da796b](https://linux-hardware.org/?probe=8c15da796b) | Nov 05, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | [92ef56cc92](https://linux-hardware.org/?probe=92ef56cc92) | Nov 05, 2023 |
| Acer          | Predator PT516-52s          | [30b7a47643](https://linux-hardware.org/?probe=30b7a47643) | Nov 05, 2023 |
| Dell          | Inspiron 7559               | [da97d12548](https://linux-hardware.org/?probe=da97d12548) | Nov 05, 2023 |
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
| Lenovo        | V15 G2 ITL 82KB             | [85e528f1bf](https://linux-hardware.org/?probe=85e528f1bf) | Nov 04, 2023 |
| Dell          | Inspiron 15 3511            | [8c23fbf7d1](https://linux-hardware.org/?probe=8c23fbf7d1) | Nov 04, 2023 |
| POV           | I102A                       | [955f97d47e](https://linux-hardware.org/?probe=955f97d47e) | Nov 04, 2023 |
| Irbis         | NB211                       | [694ca0f127](https://linux-hardware.org/?probe=694ca0f127) | Nov 03, 2023 |
| HUAWEI        | KLVL-WXX9                   | [61342b31ea](https://linux-hardware.org/?probe=61342b31ea) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | [f4bae2d5b5](https://linux-hardware.org/?probe=f4bae2d5b5) | Nov 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [ff0d013246](https://linux-hardware.org/?probe=ff0d013246) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [f9bdbf6371](https://linux-hardware.org/?probe=f9bdbf6371) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [bcea72b22f](https://linux-hardware.org/?probe=bcea72b22f) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s 20HF0047U... | [00a8b74f46](https://linux-hardware.org/?probe=00a8b74f46) | Nov 03, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [6a2591b5e9](https://linux-hardware.org/?probe=6a2591b5e9) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | [28990f206a](https://linux-hardware.org/?probe=28990f206a) | Nov 03, 2023 |
| Irbis         | NB211                       | [3ebca4338a](https://linux-hardware.org/?probe=3ebca4338a) | Nov 03, 2023 |
| HP            | Pavilion Notebook           | [f23e44229f](https://linux-hardware.org/?probe=f23e44229f) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [94cdd979b2](https://linux-hardware.org/?probe=94cdd979b2) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | [0929326be0](https://linux-hardware.org/?probe=0929326be0) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | [5149df3a58](https://linux-hardware.org/?probe=5149df3a58) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [26bc5f025c](https://linux-hardware.org/?probe=26bc5f025c) | Nov 02, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [741bcd1343](https://linux-hardware.org/?probe=741bcd1343) | Nov 02, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | [56bbf7c0bb](https://linux-hardware.org/?probe=56bbf7c0bb) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [bb1da2575d](https://linux-hardware.org/?probe=bb1da2575d) | Nov 02, 2023 |
| Lenovo        | ThinkBook Plus G3 IAP 21... | [c6634f090f](https://linux-hardware.org/?probe=c6634f090f) | Nov 02, 2023 |
| Acer          | Aspire A715-41G             | [664191098d](https://linux-hardware.org/?probe=664191098d) | Nov 02, 2023 |
| HUAWEI        | BOM-WXX9                    | [97ca7a0bfd](https://linux-hardware.org/?probe=97ca7a0bfd) | Nov 02, 2023 |
| HP            | ProBook 650 G1              | [60c6e3a5d2](https://linux-hardware.org/?probe=60c6e3a5d2) | Nov 01, 2023 |
| Dell          | G3 3579                     | [0b33f63284](https://linux-hardware.org/?probe=0b33f63284) | Nov 01, 2023 |
| Acer          | TravelMate P259-MG          | [ba3faece8c](https://linux-hardware.org/?probe=ba3faece8c) | Nov 01, 2023 |
| HP            | Laptop 15s-eq2xxx           | [685b1b18eb](https://linux-hardware.org/?probe=685b1b18eb) | Nov 01, 2023 |
| Acer          | Nitro AN515-52              | [829c16d044](https://linux-hardware.org/?probe=829c16d044) | Nov 01, 2023 |
| Apple         | MacBookPro16,2              | [37b53d54e8](https://linux-hardware.org/?probe=37b53d54e8) | Nov 01, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | [bbf2002cea](https://linux-hardware.org/?probe=bbf2002cea) | Nov 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [7dd972fb0d](https://linux-hardware.org/?probe=7dd972fb0d) | Nov 01, 2023 |
| Acer          | Aspire A715-41G             | [63fa5e90b2](https://linux-hardware.org/?probe=63fa5e90b2) | Nov 01, 2023 |
| Apple         | MacBookPro15,2              | [b724e20965](https://linux-hardware.org/?probe=b724e20965) | Nov 01, 2023 |
| HP            | Laptop 15-fc0xxx            | [d0be3aec4e](https://linux-hardware.org/?probe=d0be3aec4e) | Nov 01, 2023 |
| ASUSTek       | X555QG                      | [f047c1d264](https://linux-hardware.org/?probe=f047c1d264) | Nov 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HDC... | [0d9316dbcf](https://linux-hardware.org/?probe=0d9316dbcf) | Oct 31, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [aef3dccca0](https://linux-hardware.org/?probe=aef3dccca0) | Oct 31, 2023 |
| Alienware     | 14                          | [e88b7c0ac6](https://linux-hardware.org/?probe=e88b7c0ac6) | Oct 31, 2023 |
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
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [0b129d4a95](https://linux-hardware.org/?probe=0b129d4a95) | Oct 30, 2023 |
| Dell          | Vostro 3525                 | [ad34d5b54f](https://linux-hardware.org/?probe=ad34d5b54f) | Oct 30, 2023 |
| Dell          | Latitude 5490               | [63f4fce332](https://linux-hardware.org/?probe=63f4fce332) | Oct 30, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | [249ea48334](https://linux-hardware.org/?probe=249ea48334) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [6cbfd91e78](https://linux-hardware.org/?probe=6cbfd91e78) | Oct 30, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | [8730c3de9d](https://linux-hardware.org/?probe=8730c3de9d) | Oct 30, 2023 |
| Dell          | Precision 3551              | [4f054a63ef](https://linux-hardware.org/?probe=4f054a63ef) | Oct 30, 2023 |
| ASUSTek       | F3Sv                        | [3da2894228](https://linux-hardware.org/?probe=3da2894228) | Oct 30, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [b1adeb2f86](https://linux-hardware.org/?probe=b1adeb2f86) | Oct 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fe7dbb2385](https://linux-hardware.org/?probe=fe7dbb2385) | Oct 29, 2023 |
| Apple         | MacBookPro15,4              | [09ee918b60](https://linux-hardware.org/?probe=09ee918b60) | Oct 29, 2023 |
| HP            | Notebook                    | [79843ed7c3](https://linux-hardware.org/?probe=79843ed7c3) | Oct 29, 2023 |
| Dell          | Precision 5480              | [5df408828c](https://linux-hardware.org/?probe=5df408828c) | Oct 29, 2023 |
| Dell          | Precision M6800             | [a5e2100522](https://linux-hardware.org/?probe=a5e2100522) | Oct 29, 2023 |
| Lenovo        | ThinkPad E14 20RA0020AU     | [1d1a7bd472](https://linux-hardware.org/?probe=1d1a7bd472) | Oct 28, 2023 |
| Thomson       | N14C4WH64                   | [8dd9b1dbde](https://linux-hardware.org/?probe=8dd9b1dbde) | Oct 28, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | [da25874b12](https://linux-hardware.org/?probe=da25874b12) | Oct 28, 2023 |
| Apple         | MacBookPro8,1               | [762e9a6d4d](https://linux-hardware.org/?probe=762e9a6d4d) | Oct 28, 2023 |
| Apple         | MacBookPro8,1               | [b4645667a4](https://linux-hardware.org/?probe=b4645667a4) | Oct 28, 2023 |
| HP            | Notebook                    | [791dfef3cc](https://linux-hardware.org/?probe=791dfef3cc) | Oct 28, 2023 |
| HUAWEI        | CREM-WXX9                   | [217aaa00da](https://linux-hardware.org/?probe=217aaa00da) | Oct 28, 2023 |
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
| Maibenben     | MaiBook M                   | [ccee3b60c7](https://linux-hardware.org/?probe=ccee3b60c7) | Oct 26, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [4506629e6a](https://linux-hardware.org/?probe=4506629e6a) | Oct 26, 2023 |
| Toshiba       | Satellite L75D-A            | [82efb2dd44](https://linux-hardware.org/?probe=82efb2dd44) | Oct 26, 2023 |
| Apple         | MacBookPro15,4              | [751e98cb04](https://linux-hardware.org/?probe=751e98cb04) | Oct 26, 2023 |
| Schenker      | VISION (M23)                | [64cead24ba](https://linux-hardware.org/?probe=64cead24ba) | Oct 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [a17a8b4360](https://linux-hardware.org/?probe=a17a8b4360) | Oct 25, 2023 |
| Acer          | Aspire 7750G                | [673c675bc6](https://linux-hardware.org/?probe=673c675bc6) | Oct 25, 2023 |
| Timi          | TM1701                      | [13801c83a2](https://linux-hardware.org/?probe=13801c83a2) | Oct 25, 2023 |
| Lenovo        | IdeaPadFlex 15 20309        | [7476940ad0](https://linux-hardware.org/?probe=7476940ad0) | Oct 25, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3eee01cd16](https://linux-hardware.org/?probe=3eee01cd16) | Oct 24, 2023 |
| Lenovo        | ThinkPad T410 2537NT8       | [52b5addead](https://linux-hardware.org/?probe=52b5addead) | Oct 24, 2023 |
| Dell          | XPS 9315                    | [9246bb9a28](https://linux-hardware.org/?probe=9246bb9a28) | Oct 24, 2023 |
| Apple         | MacBookPro15,1              | [41fd350f12](https://linux-hardware.org/?probe=41fd350f12) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | [ed7e1a1932](https://linux-hardware.org/?probe=ed7e1a1932) | Oct 24, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | [84883d560d](https://linux-hardware.org/?probe=84883d560d) | Oct 24, 2023 |
| GPD           | G1621-02                    | [ea3897be17](https://linux-hardware.org/?probe=ea3897be17) | Oct 24, 2023 |
| Apple         | MacBookPro5,5               | [37be8caf53](https://linux-hardware.org/?probe=37be8caf53) | Oct 23, 2023 |
| Dell          | Latitude 5320               | [520c2effa3](https://linux-hardware.org/?probe=520c2effa3) | Oct 23, 2023 |
| Schenker      | XMG NEO (TGL/M21)           | [6d63f6c5ba](https://linux-hardware.org/?probe=6d63f6c5ba) | Oct 23, 2023 |
| TUXEDO        | Unknown                     | [0994b60ab4](https://linux-hardware.org/?probe=0994b60ab4) | Oct 23, 2023 |
| Dell          | G15 5515                    | [16754901cb](https://linux-hardware.org/?probe=16754901cb) | Oct 23, 2023 |
| HP            | ProBook 4530s               | [104df79d8e](https://linux-hardware.org/?probe=104df79d8e) | Oct 23, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SS0... | [9877bb17c1](https://linux-hardware.org/?probe=9877bb17c1) | Oct 23, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [2e4786bb32](https://linux-hardware.org/?probe=2e4786bb32) | Oct 23, 2023 |
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
| Dell          | Vostro 14 5410              | [4cb4e5aab9](https://linux-hardware.org/?probe=4cb4e5aab9) | Oct 20, 2023 |
| Dell          | Latitude 7280               | [ec9e688b4e](https://linux-hardware.org/?probe=ec9e688b4e) | Oct 20, 2023 |
| HP            | Pavilion Notebook           | [9d49844572](https://linux-hardware.org/?probe=9d49844572) | Oct 20, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [aa76e46b18](https://linux-hardware.org/?probe=aa76e46b18) | Oct 20, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [32d375b029](https://linux-hardware.org/?probe=32d375b029) | Oct 20, 2023 |
| Lenovo        | G500 20236                  | [6e5d214cb8](https://linux-hardware.org/?probe=6e5d214cb8) | Oct 20, 2023 |
| ASUSTek       | Zephyrus M GU502GW_GU502... | [c96f9ccef3](https://linux-hardware.org/?probe=c96f9ccef3) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | [15b78585e0](https://linux-hardware.org/?probe=15b78585e0) | Oct 19, 2023 |
| HP            | ProBook 445 G7              | [10fab445ad](https://linux-hardware.org/?probe=10fab445ad) | Oct 19, 2023 |
| Toshiba       | Satellite A500              | [0d2e2856a9](https://linux-hardware.org/?probe=0d2e2856a9) | Oct 19, 2023 |
| ASUSTek       | PRIME X570-P                | [4506612f98](https://linux-hardware.org/?probe=4506612f98) | Oct 19, 2023 |
| Acer          | Aspire A315-57G             | [7e39a647e3](https://linux-hardware.org/?probe=7e39a647e3) | Oct 19, 2023 |
| ASUSTek       | X555QG                      | [e2e11a852f](https://linux-hardware.org/?probe=e2e11a852f) | Oct 19, 2023 |
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
| HP            | OMEN by Laptop 16-c0xxx     | [660d60e1a8](https://linux-hardware.org/?probe=660d60e1a8) | Oct 17, 2023 |
| HUAWEI        | MACH-WX9                    | [8cb8d0943c](https://linux-hardware.org/?probe=8cb8d0943c) | Oct 17, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [0b4065c185](https://linux-hardware.org/?probe=0b4065c185) | Oct 17, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [6f1f662d3a](https://linux-hardware.org/?probe=6f1f662d3a) | Oct 17, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [8b92e44d64](https://linux-hardware.org/?probe=8b92e44d64) | Oct 17, 2023 |
| Lenovo        | ThinkPad T480 20L6S69X08    | [efc4ad7803](https://linux-hardware.org/?probe=efc4ad7803) | Oct 17, 2023 |
| Lenovo        | E41-50 82HW                 | [f31f632ea0](https://linux-hardware.org/?probe=f31f632ea0) | Oct 17, 2023 |
| MSI           | Prestige 14H B12UCX         | [81dac6f109](https://linux-hardware.org/?probe=81dac6f109) | Oct 17, 2023 |
| Positivo B... | VJFE42F11X-XXXXXX           | [d271c61b92](https://linux-hardware.org/?probe=d271c61b92) | Oct 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d14e5830b2](https://linux-hardware.org/?probe=d14e5830b2) | Oct 16, 2023 |
| Dell          | Vostro 14 5410              | [219d504a89](https://linux-hardware.org/?probe=219d504a89) | Oct 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [73e2838408](https://linux-hardware.org/?probe=73e2838408) | Oct 16, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [5651db5e36](https://linux-hardware.org/?probe=5651db5e36) | Oct 16, 2023 |
| HP            | Notebook                    | [44730825fa](https://linux-hardware.org/?probe=44730825fa) | Oct 16, 2023 |
| GLM           | 14-Z8350-C                  | [2db6571799](https://linux-hardware.org/?probe=2db6571799) | Oct 15, 2023 |
| HUAWEI        | MACH-WX9                    | [19ec3283fc](https://linux-hardware.org/?probe=19ec3283fc) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [8c4e60d5ca](https://linux-hardware.org/?probe=8c4e60d5ca) | Oct 15, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [1a38144f94](https://linux-hardware.org/?probe=1a38144f94) | Oct 15, 2023 |
| Dell          | Latitude 5591               | [ef0287bbad](https://linux-hardware.org/?probe=ef0287bbad) | Oct 15, 2023 |
| Gigabyte      | G7 GD                       | [667243780c](https://linux-hardware.org/?probe=667243780c) | Oct 15, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [85e073cb44](https://linux-hardware.org/?probe=85e073cb44) | Oct 15, 2023 |
| Acer          | Aspire VN7-592G             | [13b64fc9bd](https://linux-hardware.org/?probe=13b64fc9bd) | Oct 15, 2023 |
| HP            | Laptop 15-dy2xxx            | [5079c96f33](https://linux-hardware.org/?probe=5079c96f33) | Oct 15, 2023 |
| Toshiba       | Satellite CL10-C-102        | [cdaab4e230](https://linux-hardware.org/?probe=cdaab4e230) | Oct 15, 2023 |
| MSI           | Prestige 14H B12UCX         | [ddc0082c22](https://linux-hardware.org/?probe=ddc0082c22) | Oct 14, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [4b4d5899fa](https://linux-hardware.org/?probe=4b4d5899fa) | Oct 14, 2023 |
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
| Dell          | Precision 7520              | [de5b9c8fa1](https://linux-hardware.org/?probe=de5b9c8fa1) | Oct 13, 2023 |
| Acer          | Nitro AN515-44              | [1f1524c080](https://linux-hardware.org/?probe=1f1524c080) | Oct 13, 2023 |
| Dell          | Latitude 7430               | [fb8c320433](https://linux-hardware.org/?probe=fb8c320433) | Oct 13, 2023 |
| Dell          | Inspiron N5110              | [92726caa44](https://linux-hardware.org/?probe=92726caa44) | Oct 12, 2023 |
| Dell          | Latitude 3490               | [1c5aa8fca4](https://linux-hardware.org/?probe=1c5aa8fca4) | Oct 12, 2023 |
| Infinix       | ZERO BOOK 13                | [c20c04a240](https://linux-hardware.org/?probe=c20c04a240) | Oct 12, 2023 |
| MSI           | Modern 15 A11M              | [33272a00fb](https://linux-hardware.org/?probe=33272a00fb) | Oct 12, 2023 |
| Dell          | XPS 9320                    | [33d6205766](https://linux-hardware.org/?probe=33d6205766) | Oct 12, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | [6396467c6d](https://linux-hardware.org/?probe=6396467c6d) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | [18b3c9fef8](https://linux-hardware.org/?probe=18b3c9fef8) | Oct 12, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [87e16d607b](https://linux-hardware.org/?probe=87e16d607b) | Oct 12, 2023 |
| Lenovo        | ThinkPad T470s 20HGS29Y0... | [7c843b4c27](https://linux-hardware.org/?probe=7c843b4c27) | Oct 12, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [cc8062e568](https://linux-hardware.org/?probe=cc8062e568) | Oct 12, 2023 |
| HP            | EliteBook 840 G6 HC         | [e1b3f5dbeb](https://linux-hardware.org/?probe=e1b3f5dbeb) | Oct 11, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [3fe12fb88e](https://linux-hardware.org/?probe=3fe12fb88e) | Oct 11, 2023 |
| MSI           | PS42 Modern 8MO             | [be9a0659d4](https://linux-hardware.org/?probe=be9a0659d4) | Oct 11, 2023 |
| Lenovo        | ThinkPad P53 20QN20VZZC     | [2659f02d19](https://linux-hardware.org/?probe=2659f02d19) | Oct 11, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [d7d6c74d55](https://linux-hardware.org/?probe=d7d6c74d55) | Oct 11, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [ea3f6440b2](https://linux-hardware.org/?probe=ea3f6440b2) | Oct 11, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [7aeb935c28](https://linux-hardware.org/?probe=7aeb935c28) | Oct 11, 2023 |
| Lenovo        | ThinkPad T410 2522PT3       | [3d389cfbfa](https://linux-hardware.org/?probe=3d389cfbfa) | Oct 11, 2023 |
| Avell High... | B.ON                        | [3a419fbd20](https://linux-hardware.org/?probe=3a419fbd20) | Oct 11, 2023 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [e06a4e6c13](https://linux-hardware.org/?probe=e06a4e6c13) | Oct 11, 2023 |
| Dell          | Precision 3571              | [ac3735cea4](https://linux-hardware.org/?probe=ac3735cea4) | Oct 11, 2023 |
| HP            | 240 G5 Notebook PC          | [22f4ada2e9](https://linux-hardware.org/?probe=22f4ada2e9) | Oct 10, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [50682769d9](https://linux-hardware.org/?probe=50682769d9) | Oct 10, 2023 |
| Apple         | MacBookPro12,1              | [9de05646a3](https://linux-hardware.org/?probe=9de05646a3) | Oct 10, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [162889c4a3](https://linux-hardware.org/?probe=162889c4a3) | Oct 10, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [47ba0bddd0](https://linux-hardware.org/?probe=47ba0bddd0) | Oct 10, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [28a78b32e5](https://linux-hardware.org/?probe=28a78b32e5) | Oct 10, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7d759c245f](https://linux-hardware.org/?probe=7d759c245f) | Oct 10, 2023 |
| Teclast       | F7S                         | [92c51af32a](https://linux-hardware.org/?probe=92c51af32a) | Oct 10, 2023 |
| Notebook      | PCx0Dx                      | [9e8bfb1d9e](https://linux-hardware.org/?probe=9e8bfb1d9e) | Oct 09, 2023 |
| Lenovo        | ThinkPad T490 20N3S8HL00    | [e75ca9bf06](https://linux-hardware.org/?probe=e75ca9bf06) | Oct 09, 2023 |
| Dell          | Vostro 3700                 | [5776334e3a](https://linux-hardware.org/?probe=5776334e3a) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [749e1a7e28](https://linux-hardware.org/?probe=749e1a7e28) | Oct 09, 2023 |
| Acer          | Predator PH315-51           | [265a8e5346](https://linux-hardware.org/?probe=265a8e5346) | Oct 09, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [f269e7a6ee](https://linux-hardware.org/?probe=f269e7a6ee) | Oct 09, 2023 |
| MSI           | Summit E16Flip A12UCT       | [882d0daf54](https://linux-hardware.org/?probe=882d0daf54) | Oct 09, 2023 |
| Google        | Lindar                      | [75852e1ad7](https://linux-hardware.org/?probe=75852e1ad7) | Oct 08, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [d400853f78](https://linux-hardware.org/?probe=d400853f78) | Oct 08, 2023 |
| HP            | 240 G5 Notebook PC          | [db5dd15d83](https://linux-hardware.org/?probe=db5dd15d83) | Oct 08, 2023 |
| Dell          | Inspiron 14 5410            | [5f69a24978](https://linux-hardware.org/?probe=5f69a24978) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | [907f3a4cf1](https://linux-hardware.org/?probe=907f3a4cf1) | Oct 08, 2023 |
| Acer          | Nitro AN515-58              | [d003fa7343](https://linux-hardware.org/?probe=d003fa7343) | Oct 08, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [173accc37f](https://linux-hardware.org/?probe=173accc37f) | Oct 08, 2023 |
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
| HP            | EliteBook 655 15.6 inch ... | [7b888eeb58](https://linux-hardware.org/?probe=7b888eeb58) | Oct 05, 2023 |
| Direkt-Tek    | DTLAPY116-1                 | [09c308ed3d](https://linux-hardware.org/?probe=09c308ed3d) | Oct 05, 2023 |
| HP            | EliteBook 8460p             | [6be4af5bb3](https://linux-hardware.org/?probe=6be4af5bb3) | Oct 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [7700b3d342](https://linux-hardware.org/?probe=7700b3d342) | Oct 04, 2023 |
| Samsung       | 940Z5L                      | [120b5dac7e](https://linux-hardware.org/?probe=120b5dac7e) | Oct 04, 2023 |
| HP            | EliteBook 745 G6            | [77cfc34723](https://linux-hardware.org/?probe=77cfc34723) | Oct 04, 2023 |
| Lenovo        | ThinkPad L13 20R30009RT     | [8bc32c8cb6](https://linux-hardware.org/?probe=8bc32c8cb6) | Oct 04, 2023 |
| Dell          | Latitude 7340               | [713640e574](https://linux-hardware.org/?probe=713640e574) | Oct 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | [b2f26d1c00](https://linux-hardware.org/?probe=b2f26d1c00) | Oct 04, 2023 |
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
| ASUSTek       | VivoBook_ASUSLaptop M160... | [4462bfcb6d](https://linux-hardware.org/?probe=4462bfcb6d) | Oct 02, 2023 |
| Acer          | Aspire A515-45              | [9e09848439](https://linux-hardware.org/?probe=9e09848439) | Oct 02, 2023 |
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
| MSI           | Prestige 14H B12UCX         | [1c1f35d1c8](https://linux-hardware.org/?probe=1c1f35d1c8) | Sep 30, 2023 |
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
| HP            | EliteBook 840 G6            | [e57cdefe7a](https://linux-hardware.org/?probe=e57cdefe7a) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [713d59f3d0](https://linux-hardware.org/?probe=713d59f3d0) | Sep 29, 2023 |
| HUAWEI        | HVY-WXX9                    | [c434f30a15](https://linux-hardware.org/?probe=c434f30a15) | Sep 29, 2023 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | [d95e370c54](https://linux-hardware.org/?probe=d95e370c54) | Sep 29, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4cef8be854](https://linux-hardware.org/?probe=4cef8be854) | Sep 28, 2023 |
| HP            | EliteBook 840 G2            | [bec979fcd0](https://linux-hardware.org/?probe=bec979fcd0) | Sep 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | [356b5f053d](https://linux-hardware.org/?probe=356b5f053d) | Sep 28, 2023 |
| HP            | EliteBook 840 G6            | [5b87382fce](https://linux-hardware.org/?probe=5b87382fce) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [737b3910bb](https://linux-hardware.org/?probe=737b3910bb) | Sep 28, 2023 |
| Lenovo        | ThinkPad T495 20NJ000XGE    | [b064b5b9ca](https://linux-hardware.org/?probe=b064b5b9ca) | Sep 28, 2023 |
| HP            | Notebook                    | [b13debd2fa](https://linux-hardware.org/?probe=b13debd2fa) | Sep 27, 2023 |
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
| Dell          | Latitude E7450              | [afa1cce666](https://linux-hardware.org/?probe=afa1cce666) | Sep 27, 2023 |
| Dell          | Latitude 5420               | [4f890f283a](https://linux-hardware.org/?probe=4f890f283a) | Sep 26, 2023 |
| Dell          | Latitude 7490               | [8bb2e054ec](https://linux-hardware.org/?probe=8bb2e054ec) | Sep 26, 2023 |
| Dell          | G15 5520                    | [64cfeba3ee](https://linux-hardware.org/?probe=64cfeba3ee) | Sep 26, 2023 |
| Dell          | Latitude 5420               | [3a22857022](https://linux-hardware.org/?probe=3a22857022) | Sep 26, 2023 |
| HP            | Laptop 14s-dq2xxx           | [424e7e3d87](https://linux-hardware.org/?probe=424e7e3d87) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [dd48e0075b](https://linux-hardware.org/?probe=dd48e0075b) | Sep 26, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21HD0... | [35e9d35a69](https://linux-hardware.org/?probe=35e9d35a69) | Sep 26, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [dc762f9ae6](https://linux-hardware.org/?probe=dc762f9ae6) | Sep 26, 2023 |
| Lenovo        | ThinkPad T490s 20NX003NR... | [0a38f1e9a4](https://linux-hardware.org/?probe=0a38f1e9a4) | Sep 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | [14766bbd15](https://linux-hardware.org/?probe=14766bbd15) | Sep 26, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7c547aa37a](https://linux-hardware.org/?probe=7c547aa37a) | Sep 26, 2023 |
| Lenovo        | IdeaPad Slim 5 16IRL8 82... | [b22a584cea](https://linux-hardware.org/?probe=b22a584cea) | Sep 26, 2023 |
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
| Apple         | MacBookPro14,1              | [8b1188ba33](https://linux-hardware.org/?probe=8b1188ba33) | Sep 22, 2023 |
| HUAWEI        | BOD-WXX9                    | [909efbf81b](https://linux-hardware.org/?probe=909efbf81b) | Sep 22, 2023 |
| Dell          | Latitude 5420               | [d9c1c1537f](https://linux-hardware.org/?probe=d9c1c1537f) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7b093ed910](https://linux-hardware.org/?probe=7b093ed910) | Sep 22, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [0e85445e8e](https://linux-hardware.org/?probe=0e85445e8e) | Sep 21, 2023 |
| HP            | EliteBook 840 G5 NOTEBOO... | [3a372bed63](https://linux-hardware.org/?probe=3a372bed63) | Sep 21, 2023 |
| Lenovo        | Slim 7 14IRP8 83A4          | [b1ccf59045](https://linux-hardware.org/?probe=b1ccf59045) | Sep 21, 2023 |
| HP            | Pavilion dv6                | [270b0c0878](https://linux-hardware.org/?probe=270b0c0878) | Sep 21, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [3cd9b7841a](https://linux-hardware.org/?probe=3cd9b7841a) | Sep 21, 2023 |
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
| TUXEDO        | P65_P67RGRERA               | [0aefa5e3c6](https://linux-hardware.org/?probe=0aefa5e3c6) | Sep 20, 2023 |
| Apple         | MacBook4,1                  | [3434dd8b54](https://linux-hardware.org/?probe=3434dd8b54) | Sep 20, 2023 |
| Samsung       | NC210/NC110                 | [1e194a2568](https://linux-hardware.org/?probe=1e194a2568) | Sep 20, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [27002ca3a9](https://linux-hardware.org/?probe=27002ca3a9) | Sep 20, 2023 |
| Timi          | Xiaomi Book Pro 16 2022     | [94e8c710d5](https://linux-hardware.org/?probe=94e8c710d5) | Sep 20, 2023 |
| Acer          | Aspire A515-56              | [bb52b1ddc5](https://linux-hardware.org/?probe=bb52b1ddc5) | Sep 20, 2023 |
| Samsung       | 960XFH                      | [c25c858bd4](https://linux-hardware.org/?probe=c25c858bd4) | Sep 19, 2023 |
| Maibenben     | MaiBook M Series            | [dc2eb7a7d7](https://linux-hardware.org/?probe=dc2eb7a7d7) | Sep 19, 2023 |
| Apple         | MacBookAir7,2               | [6edec4d045](https://linux-hardware.org/?probe=6edec4d045) | Sep 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [ca0ad87f0b](https://linux-hardware.org/?probe=ca0ad87f0b) | Sep 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | [aeffbe0fe5](https://linux-hardware.org/?probe=aeffbe0fe5) | Sep 19, 2023 |
| Lenovo        | ThinkPad W540 20BG0014US    | [2d1c5101ea](https://linux-hardware.org/?probe=2d1c5101ea) | Sep 19, 2023 |
| HP            | ProBook 6475b               | [43c4870e11](https://linux-hardware.org/?probe=43c4870e11) | Sep 19, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [f9e5656f54](https://linux-hardware.org/?probe=f9e5656f54) | Sep 19, 2023 |
| Lenovo        | ThinkPad X240 20AMS1WN0A    | [858aed6617](https://linux-hardware.org/?probe=858aed6617) | Sep 19, 2023 |
| Dell          | Precision 3581              | [e1c8eb2810](https://linux-hardware.org/?probe=e1c8eb2810) | Sep 18, 2023 |
| Dell          | Inspiron 5480               | [51aca22643](https://linux-hardware.org/?probe=51aca22643) | Sep 18, 2023 |
| HP            | ProBook 445 G8 Notebook ... | [4d986c5384](https://linux-hardware.org/?probe=4d986c5384) | Sep 18, 2023 |
| Dell          | Latitude 5490               | [94eb709dfc](https://linux-hardware.org/?probe=94eb709dfc) | Sep 18, 2023 |
| MSI           | Katana GF76 11UD            | [f797b137a3](https://linux-hardware.org/?probe=f797b137a3) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | [f58cf1f72d](https://linux-hardware.org/?probe=f58cf1f72d) | Sep 18, 2023 |
| Acer          | Aspire 5755G                | [68cef2242a](https://linux-hardware.org/?probe=68cef2242a) | Sep 18, 2023 |
| HUAWEI        | KLVDZ-WXX9                  | [a4964c1b7a](https://linux-hardware.org/?probe=a4964c1b7a) | Sep 18, 2023 |
| HP            | EliteBook 745 G2            | [7e5ee5a990](https://linux-hardware.org/?probe=7e5ee5a990) | Sep 18, 2023 |
| Lenovo        | ThinkPad T480 20L6SCYF0P    | [c406bf7b56](https://linux-hardware.org/?probe=c406bf7b56) | Sep 18, 2023 |
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
| Lenovo        | Legion Pro 7 16IRX8 82WR    | [951dc3d5b0](https://linux-hardware.org/?probe=951dc3d5b0) | Sep 15, 2023 |
| HP            | EliteBook Folio 9470m       | [4a598eb0b3](https://linux-hardware.org/?probe=4a598eb0b3) | Sep 15, 2023 |
| Acer          | Swift SF314-43              | [ae2f1fa903](https://linux-hardware.org/?probe=ae2f1fa903) | Sep 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [982f29b6cc](https://linux-hardware.org/?probe=982f29b6cc) | Sep 14, 2023 |
| Fujitsu       | LIFEBOOK A357               | [a02233b901](https://linux-hardware.org/?probe=a02233b901) | Sep 14, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS5... | [934dc9c297](https://linux-hardware.org/?probe=934dc9c297) | Sep 14, 2023 |
| Apple         | MacBookPro9,2               | [37e1d06001](https://linux-hardware.org/?probe=37e1d06001) | Sep 14, 2023 |
| Acer          | Swift SF314-42              | [d907642716](https://linux-hardware.org/?probe=d907642716) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [426914b6e5](https://linux-hardware.org/?probe=426914b6e5) | Sep 14, 2023 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [756eff685a](https://linux-hardware.org/?probe=756eff685a) | Sep 14, 2023 |
| System76      | Darter Pro                  | [78c45153a3](https://linux-hardware.org/?probe=78c45153a3) | Sep 14, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [820a13876a](https://linux-hardware.org/?probe=820a13876a) | Sep 14, 2023 |
| Dell          | Latitude 7390               | [4d8e0cb72b](https://linux-hardware.org/?probe=4d8e0cb72b) | Sep 14, 2023 |
| HP            | Pavilion 13 x360 PC         | [58de71a548](https://linux-hardware.org/?probe=58de71a548) | Sep 14, 2023 |
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
| HP            | EliteBook 845 14 inch G9... | [4c595a576a](https://linux-hardware.org/?probe=4c595a576a) | Aug 30, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [78e163bc13](https://linux-hardware.org/?probe=78e163bc13) | Aug 30, 2023 |
| Timi          | Redmi Book Pro 14 2022      | [0842215d23](https://linux-hardware.org/?probe=0842215d23) | Aug 30, 2023 |
| Acer          | TravelMate P259-MG          | [dc9b122d90](https://linux-hardware.org/?probe=dc9b122d90) | Aug 30, 2023 |
| Dell          | Latitude 5430               | [477898be1f](https://linux-hardware.org/?probe=477898be1f) | Aug 30, 2023 |
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
| Acer          | Nitro AN515-44              | [b14dfb0798](https://linux-hardware.org/?probe=b14dfb0798) | Aug 25, 2023 |
| Acer          | Aspire ES1-512              | [22187e6de0](https://linux-hardware.org/?probe=22187e6de0) | Aug 25, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [810ccd6f4f](https://linux-hardware.org/?probe=810ccd6f4f) | Aug 25, 2023 |
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
| Lenovo        | ThinkPad X200 74591P0       | [adda6295fb](https://linux-hardware.org/?probe=adda6295fb) | Aug 23, 2023 |
| Acer          | Predator PT715-51           | [e187e199c9](https://linux-hardware.org/?probe=e187e199c9) | Aug 23, 2023 |
| Dell          | XPS 15 7590                 | [66b46e04d3](https://linux-hardware.org/?probe=66b46e04d3) | Aug 23, 2023 |
| Google        | Nami                        | [db2c6bfb0a](https://linux-hardware.org/?probe=db2c6bfb0a) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [08801db21d](https://linux-hardware.org/?probe=08801db21d) | Aug 23, 2023 |
| HUAWEI        | BOM-WXX9                    | [9b3cf2a525](https://linux-hardware.org/?probe=9b3cf2a525) | Aug 23, 2023 |
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
| Toshiba       | Satellite C70-B             | [d4f90e5eff](https://linux-hardware.org/?probe=d4f90e5eff) | Aug 21, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [5fa4b8ae13](https://linux-hardware.org/?probe=5fa4b8ae13) | Aug 20, 2023 |
| HP            | ProBook 430 G1              | [24a2760d65](https://linux-hardware.org/?probe=24a2760d65) | Aug 20, 2023 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | [448603376e](https://linux-hardware.org/?probe=448603376e) | Aug 20, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [8e91f085b4](https://linux-hardware.org/?probe=8e91f085b4) | Aug 20, 2023 |
| Acer          | Aspire A315-53              | [03bd8885a0](https://linux-hardware.org/?probe=03bd8885a0) | Aug 20, 2023 |
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
| HP            | ProBook 640 G1              | [e688e27904](https://linux-hardware.org/?probe=e688e27904) | Aug 17, 2023 |
| Dell          | Latitude 7440               | [e56c46e8fe](https://linux-hardware.org/?probe=e56c46e8fe) | Aug 17, 2023 |
| Dell          | Latitude 7440               | [aef57d5421](https://linux-hardware.org/?probe=aef57d5421) | Aug 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [d0d3c76bb8](https://linux-hardware.org/?probe=d0d3c76bb8) | Aug 17, 2023 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [c753cfdb08](https://linux-hardware.org/?probe=c753cfdb08) | Aug 17, 2023 |
| Lenovo        | Legion 5 15IAH7 82RC        | [75556aed08](https://linux-hardware.org/?probe=75556aed08) | Aug 16, 2023 |
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
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [da5582d4bf](https://linux-hardware.org/?probe=da5582d4bf) | Aug 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402XI... | [63f2bc3a80](https://linux-hardware.org/?probe=63f2bc3a80) | Aug 16, 2023 |
| Apple         | MacBookPro5,5               | [ee72caa76d](https://linux-hardware.org/?probe=ee72caa76d) | Aug 16, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [8733f22b33](https://linux-hardware.org/?probe=8733f22b33) | Aug 16, 2023 |
| Lenovo        | ThinkPad T440p 20AWS03V0... | [f50a83684f](https://linux-hardware.org/?probe=f50a83684f) | Aug 16, 2023 |
| Lenovo        | ThinkPad T550 20CJS1JT00    | [78cd2292c2](https://linux-hardware.org/?probe=78cd2292c2) | Aug 16, 2023 |
| Dell          | Latitude 3301               | [8cbe049a08](https://linux-hardware.org/?probe=8cbe049a08) | Aug 15, 2023 |
| Samsung       | 550XDA                      | [5e5606074a](https://linux-hardware.org/?probe=5e5606074a) | Aug 15, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | [cfa082df13](https://linux-hardware.org/?probe=cfa082df13) | Aug 15, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [30e2a20d37](https://linux-hardware.org/?probe=30e2a20d37) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [6c933602ca](https://linux-hardware.org/?probe=6c933602ca) | Aug 15, 2023 |
| Topstar       | Cantiga & ICH9M Chipset     | [5102056c71](https://linux-hardware.org/?probe=5102056c71) | Aug 15, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [618b4d5598](https://linux-hardware.org/?probe=618b4d5598) | Aug 15, 2023 |
| Dell          | Latitude E6530              | [9cbe752127](https://linux-hardware.org/?probe=9cbe752127) | Aug 15, 2023 |
| Toshiba       | Satellite C55D-A            | [5a86eae963](https://linux-hardware.org/?probe=5a86eae963) | Aug 15, 2023 |
| Google        | Bobba360                    | [e2ae1afdcc](https://linux-hardware.org/?probe=e2ae1afdcc) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [52bd9574d8](https://linux-hardware.org/?probe=52bd9574d8) | Aug 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [f99741ec7f](https://linux-hardware.org/?probe=f99741ec7f) | Aug 14, 2023 |
| Google        | Bobba360                    | [f211501fde](https://linux-hardware.org/?probe=f211501fde) | Aug 14, 2023 |
| HP            | Notebook                    | [f32b596c87](https://linux-hardware.org/?probe=f32b596c87) | Aug 14, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [c192c37af2](https://linux-hardware.org/?probe=c192c37af2) | Aug 14, 2023 |
| Apple         | MacBookPro11,1              | [11b8c16b30](https://linux-hardware.org/?probe=11b8c16b30) | Aug 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [74eb1759e1](https://linux-hardware.org/?probe=74eb1759e1) | Aug 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | [24b85b3417](https://linux-hardware.org/?probe=24b85b3417) | Aug 14, 2023 |
| Dell          | Latitude E7470              | [99518b81f7](https://linux-hardware.org/?probe=99518b81f7) | Aug 13, 2023 |
| Google        | Blorb                       | [d1abf19439](https://linux-hardware.org/?probe=d1abf19439) | Aug 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | [400e17fe60](https://linux-hardware.org/?probe=400e17fe60) | Aug 13, 2023 |
| HP            | ProBook 6450b               | [8862a40143](https://linux-hardware.org/?probe=8862a40143) | Aug 13, 2023 |
| Acer          | Aspire E5-721               | [9a7018c6cb](https://linux-hardware.org/?probe=9a7018c6cb) | Aug 13, 2023 |
| HP            | EliteBook 845 14 inch G9... | [0650746552](https://linux-hardware.org/?probe=0650746552) | Aug 13, 2023 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [8ef1bbdcec](https://linux-hardware.org/?probe=8ef1bbdcec) | Aug 13, 2023 |
| Lenovo        | ThinkPad X250 20CLS3320C    | [51f9e0c482](https://linux-hardware.org/?probe=51f9e0c482) | Aug 13, 2023 |
| HP            | Pavilion Laptop 15z-eh00... | [6f54d654ac](https://linux-hardware.org/?probe=6f54d654ac) | Aug 13, 2023 |
| Toshiba       | Satellite C55D-A            | [136ac6835c](https://linux-hardware.org/?probe=136ac6835c) | Aug 13, 2023 |
| Dell          | Inspiron M5010              | [dd2538ba1a](https://linux-hardware.org/?probe=dd2538ba1a) | Aug 13, 2023 |
| MSI           | GT62VR 7RE                  | [105839bee0](https://linux-hardware.org/?probe=105839bee0) | Aug 13, 2023 |
| Framework     | Laptop                      | [8ac155813e](https://linux-hardware.org/?probe=8ac155813e) | Aug 13, 2023 |
| Apple         | MacBookPro14,3              | [05a4c5e1ec](https://linux-hardware.org/?probe=05a4c5e1ec) | Aug 13, 2023 |
| Dell          | XPS 13 9300                 | [ed549bc47c](https://linux-hardware.org/?probe=ed549bc47c) | Aug 12, 2023 |
| HONOR         | NMH-WCX9                    | [788c2c9e31](https://linux-hardware.org/?probe=788c2c9e31) | Aug 12, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | [def5f9423e](https://linux-hardware.org/?probe=def5f9423e) | Aug 12, 2023 |
| HP            | Laptop 14s-dq2xxx           | [f2f4f8a844](https://linux-hardware.org/?probe=f2f4f8a844) | Aug 12, 2023 |
| HP            | Laptop 15-db0xxx            | [3d875407fc](https://linux-hardware.org/?probe=3d875407fc) | Aug 12, 2023 |
| Apple         | MacBookPro13,3              | [b43e2738d9](https://linux-hardware.org/?probe=b43e2738d9) | Aug 12, 2023 |
| Dell          | G15 5510                    | [3cfac2d234](https://linux-hardware.org/?probe=3cfac2d234) | Aug 12, 2023 |
| Lenovo        | ThinkPad T460p 20FXS1C30... | [08542d994e](https://linux-hardware.org/?probe=08542d994e) | Aug 12, 2023 |
| ASUSTek       | K55VD                       | [05024005e4](https://linux-hardware.org/?probe=05024005e4) | Aug 12, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | [411b9f412c](https://linux-hardware.org/?probe=411b9f412c) | Aug 12, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | [d25ab08211](https://linux-hardware.org/?probe=d25ab08211) | Aug 12, 2023 |
| Toshiba       | Satellite C55-A             | [d1bf5ba3c3](https://linux-hardware.org/?probe=d1bf5ba3c3) | Aug 12, 2023 |
| Dell          | Latitude E7270              | [63fd1b0d6b](https://linux-hardware.org/?probe=63fd1b0d6b) | Aug 12, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [377a0e25aa](https://linux-hardware.org/?probe=377a0e25aa) | Aug 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | [7574e6b53a](https://linux-hardware.org/?probe=7574e6b53a) | Aug 11, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | [c336f9aa8c](https://linux-hardware.org/?probe=c336f9aa8c) | Aug 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | [c352abad93](https://linux-hardware.org/?probe=c352abad93) | Aug 11, 2023 |
| Acer          | Aspire E5-721               | [f4abfc94d4](https://linux-hardware.org/?probe=f4abfc94d4) | Aug 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | [8c449cd820](https://linux-hardware.org/?probe=8c449cd820) | Aug 11, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | [29065a56ee](https://linux-hardware.org/?probe=29065a56ee) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [22fc28c382](https://linux-hardware.org/?probe=22fc28c382) | Aug 11, 2023 |
| Dell          | XPS 15 9560                 | [471e3c5077](https://linux-hardware.org/?probe=471e3c5077) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| Dell          | Latitude 5300               | [661051063f](https://linux-hardware.org/?probe=661051063f) | Aug 10, 2023 |
| Lenovo        | ThinkPad X220 4291SEN       | [b62026890a](https://linux-hardware.org/?probe=b62026890a) | Aug 10, 2023 |
| HP            | 250 G3                      | [512fd5d81f](https://linux-hardware.org/?probe=512fd5d81f) | Aug 10, 2023 |
| HP            | ProBook 430 G2              | [426901227d](https://linux-hardware.org/?probe=426901227d) | Aug 10, 2023 |
| Acer          | Aspire E5-721               | [6743c7ca9d](https://linux-hardware.org/?probe=6743c7ca9d) | Aug 10, 2023 |
| Gigabyte      | AERO 15-WA                  | [bd9f5d0f39](https://linux-hardware.org/?probe=bd9f5d0f39) | Aug 10, 2023 |
| Apple         | MacBookPro5,1               | [23fc9401d3](https://linux-hardware.org/?probe=23fc9401d3) | Aug 10, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | [4446f503d5](https://linux-hardware.org/?probe=4446f503d5) | Aug 10, 2023 |
| HP            | 14                          | [8692626574](https://linux-hardware.org/?probe=8692626574) | Aug 09, 2023 |
| HP            | Laptop 14s-dq2xxx           | [bb40aa6fd9](https://linux-hardware.org/?probe=bb40aa6fd9) | Aug 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [0f34656484](https://linux-hardware.org/?probe=0f34656484) | Aug 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [afa02e4c02](https://linux-hardware.org/?probe=afa02e4c02) | Aug 09, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | [6de592988e](https://linux-hardware.org/?probe=6de592988e) | Aug 09, 2023 |
| Acer          | Aspire A317-33              | [6dd8126a05](https://linux-hardware.org/?probe=6dd8126a05) | Aug 09, 2023 |
| HP            | Notebook                    | [bac7155006](https://linux-hardware.org/?probe=bac7155006) | Aug 09, 2023 |
| Dell          | Inspiron M5010              | [be4ad618b4](https://linux-hardware.org/?probe=be4ad618b4) | Aug 09, 2023 |
| HP            | 240 G5 Notebook PC          | [c801f4bbd0](https://linux-hardware.org/?probe=c801f4bbd0) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [a8fc44190a](https://linux-hardware.org/?probe=a8fc44190a) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [766e35e920](https://linux-hardware.org/?probe=766e35e920) | Aug 09, 2023 |
| Apple         | MacBookPro15,2              | [68e26bb5d3](https://linux-hardware.org/?probe=68e26bb5d3) | Aug 09, 2023 |
| Dell          | Latitude 7320               | [6db1867722](https://linux-hardware.org/?probe=6db1867722) | Aug 09, 2023 |
| Acer          | Aspire E5-721               | [82a8a2346a](https://linux-hardware.org/?probe=82a8a2346a) | Aug 08, 2023 |
| Dell          | Inspiron 15 3515            | [7ce5fc846b](https://linux-hardware.org/?probe=7ce5fc846b) | Aug 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [2e4e848552](https://linux-hardware.org/?probe=2e4e848552) | Aug 08, 2023 |
| Acer          | Aspire A515-51G             | [1105c8c2ea](https://linux-hardware.org/?probe=1105c8c2ea) | Aug 08, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | [914ff5745c](https://linux-hardware.org/?probe=914ff5745c) | Aug 08, 2023 |
| Lenovo        | Y720-15IKB 80VR             | [7a088aea04](https://linux-hardware.org/?probe=7a088aea04) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | [1a3b5297dd](https://linux-hardware.org/?probe=1a3b5297dd) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | [18208500ee](https://linux-hardware.org/?probe=18208500ee) | Aug 08, 2023 |
| Acer          | Aspire 4752                 | [1c68b4d24a](https://linux-hardware.org/?probe=1c68b4d24a) | Aug 08, 2023 |
| HP            | Elite x2 1012 G1            | [0ee8428f91](https://linux-hardware.org/?probe=0ee8428f91) | Aug 07, 2023 |
| Dell          | Inspiron 3505               | [e07624ae41](https://linux-hardware.org/?probe=e07624ae41) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [36b0caba9e](https://linux-hardware.org/?probe=36b0caba9e) | Aug 07, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [d989868a6b](https://linux-hardware.org/?probe=d989868a6b) | Aug 07, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [8b5e74e190](https://linux-hardware.org/?probe=8b5e74e190) | Aug 07, 2023 |
| Apple         | MacBookPro11,1              | [0a1b8d0627](https://linux-hardware.org/?probe=0a1b8d0627) | Aug 07, 2023 |
| Timi          | A7S                         | [34a354df5a](https://linux-hardware.org/?probe=34a354df5a) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [b4b049b997](https://linux-hardware.org/?probe=b4b049b997) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [8633bc5aa5](https://linux-hardware.org/?probe=8633bc5aa5) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [aabc0a8aee](https://linux-hardware.org/?probe=aabc0a8aee) | Aug 07, 2023 |
| HUAWEI        | WRTD-WXX9                   | [dc02eefe63](https://linux-hardware.org/?probe=dc02eefe63) | Aug 06, 2023 |
| Dell          | XPS 13 9310                 | [1134279f41](https://linux-hardware.org/?probe=1134279f41) | Aug 06, 2023 |
| Dell          | Inspiron 3520               | [eed6ad702b](https://linux-hardware.org/?probe=eed6ad702b) | Aug 06, 2023 |
| Dell          | Inspiron 3520               | [8a3ba73fae](https://linux-hardware.org/?probe=8a3ba73fae) | Aug 06, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | [e71ac5ca78](https://linux-hardware.org/?probe=e71ac5ca78) | Aug 06, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | [27d1d39b58](https://linux-hardware.org/?probe=27d1d39b58) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | [f77c465da0](https://linux-hardware.org/?probe=f77c465da0) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [56c7715a6d](https://linux-hardware.org/?probe=56c7715a6d) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [6a9e7cc3e2](https://linux-hardware.org/?probe=6a9e7cc3e2) | Aug 06, 2023 |
| RCA           | 038-WT9S10WM02              | [61c1a104d2](https://linux-hardware.org/?probe=61c1a104d2) | Aug 06, 2023 |
| RCA           | 038-WT9S10WM02              | [fe15934abe](https://linux-hardware.org/?probe=fe15934abe) | Aug 06, 2023 |
| Dell          | Inspiron 15-3567            | [2e8d48f9bc](https://linux-hardware.org/?probe=2e8d48f9bc) | Aug 06, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora_38/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                                                | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| 6.2.9-300.fc38.x86_64                                  | 216       | 11.84%  |
| 6.2.15-300.fc38.x86_64                                 | 141       | 7.73%   |
| 6.3.8-200.fc38.x86_64                                  | 114       | 6.25%   |
| 6.4.15-200.fc38.x86_64                                 | 101       | 5.53%   |
| 6.2.14-300.fc38.x86_64                                 | 90        | 4.93%   |
| 6.5.5-200.fc38.x86_64                                  | 89        | 4.88%   |
| 6.2.11-300.fc38.x86_64                                 | 87        | 4.77%   |
| 6.3.12-200.fc38.x86_64                                 | 66        | 3.62%   |
| 6.5.8-200.fc38.x86_64                                  | 61        | 3.34%   |
| 6.4.6-200.fc38.x86_64                                  | 55        | 3.01%   |
| 6.5.6-200.fc38.x86_64                                  | 51        | 2.79%   |
| 6.3.11-200.fc38.x86_64                                 | 51        | 2.79%   |
| 6.4.14-200.fc38.x86_64                                 | 50        | 2.74%   |
| 6.4.7-200.fc38.x86_64                                  | 47        | 2.58%   |
| 6.3.5-200.fc38.x86_64                                  | 47        | 2.58%   |
| 6.5.7-200.fc38.x86_64                                  | 46        | 2.52%   |
| 6.4.11-200.fc38.x86_64                                 | 46        | 2.52%   |
| 6.2.13-300.fc38.x86_64                                 | 46        | 2.52%   |
| 6.4.13-200.fc38.x86_64                                 | 44        | 2.41%   |
| 6.3.6-200.fc38.x86_64                                  | 43        | 2.36%   |
| 6.4.12-200.fc38.x86_64                                 | 42        | 2.3%    |
| 6.4.10-200.fc38.x86_64                                 | 42        | 2.3%    |
| 6.2.12-300.fc38.x86_64                                 | 33        | 1.81%   |
| 6.4.4-200.fc38.x86_64                                  | 28        | 1.53%   |
| 6.4.9-200.fc38.x86_64                                  | 26        | 1.42%   |
| 6.3.4-201.fc38.x86_64                                  | 24        | 1.32%   |
| 6.3.7-200.fc38.x86_64                                  | 22        | 1.21%   |
| 6.5.9-200.fc38.x86_64                                  | 12        | 0.66%   |
| 6.2.8-300.fc38.x86_64                                  | 9         | 0.49%   |
| 6.4.8-200.fc38.x86_64                                  | 7         | 0.38%   |
| 6.2.10-300.fc38.x86_64                                 | 7         | 0.38%   |
| 6.2.6-300.fc38.x86_64                                  | 6         | 0.33%   |
| 6.2.2-301.fc38.x86_64                                  | 4         | 0.22%   |
| 6.2.7-300.fc38.x86_64                                  | 3         | 0.16%   |
| 6.2.15-703.inttf.fc38.x86_64                           | 3         | 0.16%   |
| 6.4.0-0.rc4.334.vanilla.fc38.x86_64                    | 2         | 0.11%   |
| 6.2.11-703.inttf.fc38.x86_64                           | 2         | 0.11%   |
| 6.2.0-63.fc38.x86_64                                   | 2         | 0.11%   |
| 6.6.0-0.rc2.219.vanilla.fc38.x86_64                    | 1         | 0.05%   |
| 6.6.0-0.rc1.20230913gt3669558b.214.vanilla.fc38.x86_64 | 1         | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2.9   | 216       | 11.84%  |
| 6.2.15  | 146       | 8%      |
| 6.3.8   | 115       | 6.3%    |
| 6.4.15  | 101       | 5.53%   |
| 6.2.14  | 92        | 5.04%   |
| 6.5.5   | 91        | 4.99%   |
| 6.2.11  | 89        | 4.88%   |
| 6.3.12  | 66        | 3.62%   |
| 6.5.8   | 61        | 3.34%   |
| 6.4.6   | 55        | 3.01%   |
| 6.5.6   | 51        | 2.79%   |
| 6.3.11  | 51        | 2.79%   |
| 6.4.14  | 50        | 2.74%   |
| 6.4.7   | 48        | 2.63%   |
| 6.3.5   | 47        | 2.58%   |
| 6.5.7   | 46        | 2.52%   |
| 6.4.11  | 46        | 2.52%   |
| 6.2.13  | 46        | 2.52%   |
| 6.4.13  | 45        | 2.47%   |
| 6.4.10  | 44        | 2.41%   |
| 6.3.6   | 44        | 2.41%   |
| 6.4.12  | 43        | 2.36%   |
| 6.2.12  | 33        | 1.81%   |
| 6.4.4   | 28        | 1.53%   |
| 6.4.9   | 26        | 1.42%   |
| 6.3.4   | 24        | 1.32%   |
| 6.3.7   | 22        | 1.21%   |
| 6.5.9   | 12        | 0.66%   |
| 6.2.8   | 9         | 0.49%   |
| 6.2.10  | 8         | 0.44%   |
| 6.2.0   | 8         | 0.44%   |
| 6.4.8   | 7         | 0.38%   |
| 6.2.6   | 6         | 0.33%   |
| 6.2.2   | 5         | 0.27%   |
| 6.5.0   | 4         | 0.22%   |
| 6.4.0   | 4         | 0.22%   |
| 6.3.1   | 4         | 0.22%   |
| 6.6.0   | 3         | 0.16%   |
| 6.2.7   | 3         | 0.16%   |
| 6.0.8   | 3         | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.2     | 642       | 36.09%  |
| 6.4     | 481       | 27.04%  |
| 6.3     | 372       | 20.91%  |
| 6.5     | 268       | 15.06%  |
| 6.0     | 6         | 0.34%   |
| 6.6     | 3         | 0.17%   |
| 6.1     | 3         | 0.17%   |
| 5.4     | 1         | 0.06%   |
| 5.19    | 1         | 0.06%   |
| 5.15    | 1         | 0.06%   |
| 5.10    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 1675      | 99.88%  |
| aarch64 | 2         | 0.12%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 1335      | 78.99%  |
| KDE5          | 236       | 13.96%  |
| Unknown       | 28        | 1.66%   |
| XFCE          | 23        | 1.36%   |
| X-Cinnamon    | 22        | 1.3%    |
| Cinnamon      | 11        | 0.65%   |
| GNOME Classic | 6         | 0.36%   |
| MATE          | 5         | 0.3%    |
| Budgie        | 5         | 0.3%    |
| sway          | 4         | 0.24%   |
| LXDE          | 4         | 0.24%   |
| i3            | 3         | 0.18%   |
| Hyprland      | 3         | 0.18%   |
| LXQt          | 2         | 0.12%   |
| Unity         | 1         | 0.06%   |
| Pantheon      | 1         | 0.06%   |
| KDE4          | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 1393      | 82.33%  |
| X11     | 269       | 15.9%   |
| Unknown | 17        | 1%      |
| Tty     | 12        | 0.71%   |
| Xcb     | 1         | 0.06%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1067      | 63.06%  |
| GDM     | 447       | 26.42%  |
| SDDM    | 112       | 6.62%   |
| LightDM | 62        | 3.66%   |
| LXDM    | 3         | 0.18%   |
| SLiM    | 1         | 0.06%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 872       | 51.69%  |
| en_GB   | 128       | 7.59%   |
| ru_RU   | 87        | 5.16%   |
| pt_BR   | 82        | 4.86%   |
| de_DE   | 77        | 4.56%   |
| fr_FR   | 47        | 2.79%   |
| it_IT   | 41        | 2.43%   |
| es_ES   | 33        | 1.96%   |
| es_MX   | 26        | 1.54%   |
| en_CA   | 25        | 1.48%   |
| pl_PL   | 23        | 1.36%   |
| en_AU   | 23        | 1.36%   |
| en_IN   | 21        | 1.24%   |
| es_CL   | 19        | 1.13%   |
| es_CO   | 14        | 0.83%   |
| pt_PT   | 12        | 0.71%   |
| en_DK   | 10        | 0.59%   |
| zh_CN   | 9         | 0.53%   |
| cs_CZ   | 9         | 0.53%   |
| hu_HU   | 8         | 0.47%   |
| es_PE   | 7         | 0.41%   |
| es_AR   | 7         | 0.41%   |
| de_AT   | 7         | 0.41%   |
| tr_TR   | 6         | 0.36%   |
| ru_UA   | 6         | 0.36%   |
| fr_CA   | 6         | 0.36%   |
| Unknown | 6         | 0.36%   |
| sk_SK   | 5         | 0.3%    |
| nl_NL   | 4         | 0.24%   |
| id_ID   | 4         | 0.24%   |
| en_ZA   | 4         | 0.24%   |
| en_PH   | 4         | 0.24%   |
| en_IE   | 4         | 0.24%   |
| nl_BE   | 3         | 0.18%   |
| ja_JP   | 3         | 0.18%   |
| es_UY   | 3         | 0.18%   |
| es_EC   | 3         | 0.18%   |
| en_SG   | 3         | 0.18%   |
| en_NZ   | 3         | 0.18%   |
| da_DK   | 3         | 0.18%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1428      | 84.5%   |
| BIOS | 262       | 15.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Btrfs   | 1429      | 85.11%  |
| Ext4    | 222       | 13.22%  |
| Xfs     | 26        | 1.55%   |
| Overlay | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1042      | 61.69%  |
| GPT     | 626       | 37.06%  |
| MBR     | 21        | 1.24%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1563      | 93.04%  |
| Yes       | 117       | 6.96%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1441      | 85.77%  |
| Yes       | 239       | 14.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 456       | 27.19%  |
| Dell                   | 266       | 15.86%  |
| Hewlett-Packard        | 250       | 14.91%  |
| ASUSTek Computer       | 207       | 12.34%  |
| Acer                   | 101       | 6.02%   |
| Apple                  | 79        | 4.71%   |
| HUAWEI                 | 47        | 2.8%    |
| MSI                    | 44        | 2.62%   |
| Samsung Electronics    | 27        | 1.61%   |
| Timi                   | 19        | 1.13%   |
| Toshiba                | 17        | 1.01%   |
| Google                 | 16        | 0.95%   |
| Sony                   | 10        | 0.6%    |
| Framework              | 10        | 0.6%    |
| Notebook               | 8         | 0.48%   |
| Unknown                | 8         | 0.48%   |
| Gigabyte Technology    | 7         | 0.42%   |
| Fujitsu                | 7         | 0.42%   |
| System76               | 6         | 0.36%   |
| TUXEDO                 | 5         | 0.3%    |
| Chuwi                  | 5         | 0.3%    |
| Schenker               | 4         | 0.24%   |
| Razer                  | 4         | 0.24%   |
| Positivo Bahia - VAIO  | 4         | 0.24%   |
| Positivo               | 4         | 0.24%   |
| PC Specialist          | 3         | 0.18%   |
| Maibenben              | 3         | 0.18%   |
| HONOR                  | 3         | 0.18%   |
| GPU Company            | 3         | 0.18%   |
| Avell High Performance | 3         | 0.18%   |
| Alienware              | 3         | 0.18%   |
| UNOWHY                 | 2         | 0.12%   |
| Packard Bell           | 2         | 0.12%   |
| MECHREVO               | 2         | 0.12%   |
| LDLC                   | 2         | 0.12%   |
| Intel Client Systems   | 2         | 0.12%   |
| Corsair                | 2         | 0.12%   |
| Xplore                 | 1         | 0.06%   |
| XIAOMI                 | 1         | 0.06%   |
| VPU Company            | 1         | 0.06%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Apple MacBookPro9,2                     | 12        | 0.72%   |
| Unknown                                 | 12        | 0.72%   |
| HP Notebook                             | 10        | 0.6%    |
| Apple MacBookPro8,1                     | 10        | 0.6%    |
| Framework Laptop                        | 8         | 0.48%   |
| Dell XPS 13 9310                        | 7         | 0.42%   |
| Lenovo IdeaPad 3 15ITL6 82H8            | 6         | 0.36%   |
| Samsung 550XDA                          | 5         | 0.3%    |
| HP EliteBook 840 G6                     | 5         | 0.3%    |
| Dell Latitude 7490                      | 5         | 0.3%    |
| Apple MacBookPro12,1                    | 5         | 0.3%    |
| Apple MacBookPro11,1                    | 5         | 0.3%    |
| Apple MacBookAir7,2                     | 5         | 0.3%    |
| Timi Redmi Book Pro 14 2022             | 4         | 0.24%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ        | 4         | 0.24%   |
| HUAWEI HVY-WXX9                         | 4         | 0.24%   |
| HUAWEI CREM-WXX9                        | 4         | 0.24%   |
| HUAWEI BOM-WXX9                         | 4         | 0.24%   |
| HP Victus by Laptop 16-e0xxx            | 4         | 0.24%   |
| HP ProBook 450 15.6 inch G9 Notebook PC | 4         | 0.24%   |
| HP ProBook 445 G8 Notebook PC           | 4         | 0.24%   |
| HP Pavilion Aero Laptop 13-be0xxx       | 4         | 0.24%   |
| HP 255 G8 Notebook PC                   | 4         | 0.24%   |
| Dell XPS 9320                           | 4         | 0.24%   |
| Dell XPS 15 9560                        | 4         | 0.24%   |
| Dell XPS 13 9380                        | 4         | 0.24%   |
| Dell XPS 13 9305                        | 4         | 0.24%   |
| Dell Latitude E7470                     | 4         | 0.24%   |
| Dell Latitude E7450                     | 4         | 0.24%   |
| Dell Latitude 5490                      | 4         | 0.24%   |
| Dell Latitude 5420                      | 4         | 0.24%   |
| Dell Inspiron 15 5510                   | 4         | 0.24%   |
| ASUS Vivobook Go E1504FA_E1504FA        | 4         | 0.24%   |
| Apple MacBookPro5,5                     | 4         | 0.24%   |
| Acer Nitro AN515-55                     | 4         | 0.24%   |
| Acer Aspire A515-45                     | 4         | 0.24%   |
| Timi Mi NoteBook Ultra                  | 3         | 0.18%   |
| Samsung 550P5C/550P7C                   | 3         | 0.18%   |
| MSI Prestige 14H B12UCX                 | 3         | 0.18%   |
| MSI Modern 14 B4MW                      | 3         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 237       | 14.13%  |
| Lenovo IdeaPad     | 103       | 6.14%   |
| Dell Latitude      | 97        | 5.78%   |
| ASUS VivoBook      | 67        | 4%      |
| Dell Inspiron      | 65        | 3.88%   |
| Acer Aspire        | 61        | 3.64%   |
| HP Pavilion        | 52        | 3.1%    |
| Dell XPS           | 51        | 3.04%   |
| HP EliteBook       | 47        | 2.8%    |
| ASUS ROG           | 41        | 2.44%   |
| HP Laptop          | 36        | 2.15%   |
| HP ProBook         | 34        | 2.03%   |
| Lenovo Legion      | 33        | 1.97%   |
| ASUS ASUS          | 26        | 1.55%   |
| Dell Precision     | 25        | 1.49%   |
| Lenovo ThinkBook   | 20        | 1.19%   |
| Acer Nitro         | 19        | 1.13%   |
| Lenovo Yoga        | 18        | 1.07%   |
| ASUS Zenbook       | 17        | 1.01%   |
| Toshiba Satellite  | 13        | 0.78%   |
| Apple MacBookPro9  | 13        | 0.78%   |
| Apple MacBookPro8  | 12        | 0.72%   |
| Unknown            | 12        | 0.72%   |
| HP ENVY            | 11        | 0.66%   |
| Dell Vostro        | 11        | 0.66%   |
| HP OMEN            | 10        | 0.6%    |
| HP Notebook        | 10        | 0.6%    |
| Framework Laptop   | 10        | 0.6%    |
| MSI Modern         | 9         | 0.54%   |
| HP 255             | 8         | 0.48%   |
| Apple MacBookPro11 | 8         | 0.48%   |
| Acer Swift         | 8         | 0.48%   |
| HP ZBook           | 7         | 0.42%   |
| Dell G15           | 7         | 0.42%   |
| ASUS TUF           | 7         | 0.42%   |
| Timi Redmi         | 6         | 0.36%   |
| MSI Prestige       | 6         | 0.36%   |
| Lenovo V15         | 6         | 0.36%   |
| HP Victus          | 6         | 0.36%   |
| Apple MacBookPro5  | 6         | 0.36%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 273       | 16.28%  |
| 2022    | 230       | 13.71%  |
| 2020    | 206       | 12.28%  |
| 2019    | 148       | 8.83%   |
| 2018    | 129       | 7.69%   |
| 2023    | 108       | 6.44%   |
| 2017    | 94        | 5.61%   |
| 2012    | 83        | 4.95%   |
| 2014    | 76        | 4.53%   |
| 2015    | 71        | 4.23%   |
| 2013    | 65        | 3.88%   |
| 2011    | 58        | 3.46%   |
| 2016    | 55        | 3.28%   |
| 2010    | 30        | 1.79%   |
| 2009    | 22        | 1.31%   |
| 2008    | 19        | 1.13%   |
| 2007    | 8         | 0.48%   |
| 2006    | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1677      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1243      | 73.59%  |
| Enabled  | 446       | 26.41%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1655      | 98.69%  |
| Yes  | 22        | 1.31%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 472       | 28.05%  |
| 16.01-24.0  | 372       | 22.1%   |
| 8.01-16.0   | 352       | 20.92%  |
| 32.01-64.0  | 212       | 12.6%   |
| 3.01-4.0    | 164       | 9.74%   |
| 24.01-32.0  | 46        | 2.73%   |
| 64.01-256.0 | 32        | 1.9%    |
| 1.01-2.0    | 25        | 1.49%   |
| 2.01-3.0    | 8         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 533       | 30.1%   |
| 2.01-3.0   | 470       | 26.54%  |
| 3.01-4.0   | 446       | 25.18%  |
| 1.01-2.0   | 175       | 9.88%   |
| 8.01-16.0  | 130       | 7.34%   |
| 0.51-1.0   | 9         | 0.51%   |
| 16.01-24.0 | 5         | 0.28%   |
| 24.01-32.0 | 2         | 0.11%   |
| 0.01-0.5   | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1275      | 75.58%  |
| 2      | 363       | 21.52%  |
| 3      | 33        | 1.96%   |
| 4      | 7         | 0.41%   |
| 5      | 4         | 0.24%   |
| 0      | 3         | 0.18%   |
| 8      | 1         | 0.06%   |
| 6      | 1         | 0.06%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1385      | 82.49%  |
| Yes       | 294       | 17.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1195      | 70.96%  |
| No        | 489       | 29.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1653      | 98.51%  |
| No        | 25        | 1.49%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1462      | 86.71%  |
| No        | 224       | 13.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 252       | 14.96%  |
| Germany     | 127       | 7.54%   |
| Brazil      | 116       | 6.88%   |
| Russia      | 101       | 5.99%   |
| Italy       | 78        | 4.63%   |
| India       | 70        | 4.15%   |
| UK          | 63        | 3.74%   |
| France      | 59        | 3.5%    |
| Canada      | 54        | 3.2%    |
| Spain       | 51        | 3.03%   |
| Mexico      | 48        | 2.85%   |
| Poland      | 43        | 2.55%   |
| Netherlands | 40        | 2.37%   |
| Turkey      | 34        | 2.02%   |
| Czechia     | 27        | 1.6%    |
| Australia   | 26        | 1.54%   |
| Chile       | 24        | 1.42%   |
| Colombia    | 22        | 1.31%   |
| Portugal    | 19        | 1.13%   |
| Indonesia   | 18        | 1.07%   |
| Hungary     | 16        | 0.95%   |
| Belgium     | 16        | 0.95%   |
| Austria     | 16        | 0.95%   |
| Switzerland | 15        | 0.89%   |
| Sweden      | 13        | 0.77%   |
| Denmark     | 13        | 0.77%   |
| Romania     | 12        | 0.71%   |
| Philippines | 12        | 0.71%   |
| Bulgaria    | 12        | 0.71%   |
| Argentina   | 12        | 0.71%   |
| Norway      | 11        | 0.65%   |
| Israel      | 11        | 0.65%   |
| Belarus     | 11        | 0.65%   |
| Finland     | 10        | 0.59%   |
| China       | 10        | 0.59%   |
| Peru        | 8         | 0.47%   |
| Egypt       | 8         | 0.47%   |
| Vietnam     | 7         | 0.42%   |
| Thailand    | 7         | 0.42%   |
| Singapore   | 7         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Moscow         | 23        | 1.35%   |
| Berlin         | 17        | 0.99%   |
| Mexico City    | 15        | 0.88%   |
| Santiago       | 14        | 0.82%   |
| Sao Paulo      | 13        | 0.76%   |
| St Petersburg  | 12        | 0.7%    |
| Delhi          | 12        | 0.7%    |
| Milan          | 11        | 0.64%   |
| Madrid         | 11        | 0.64%   |
| Vienna         | 10        | 0.58%   |
| Sofia          | 10        | 0.58%   |
| Prague         | 10        | 0.58%   |
| Paris          | 10        | 0.58%   |
| Warsaw         | 9         | 0.53%   |
| Istanbul       | 9         | 0.53%   |
| Sydney         | 8         | 0.47%   |
| Munich         | 8         | 0.47%   |
| Montreal       | 8         | 0.47%   |
| Lisbon         | 8         | 0.47%   |
| Hamburg        | 8         | 0.47%   |
| Budapest       | 8         | 0.47%   |
| Bengaluru      | 8         | 0.47%   |
| Singapore      | 7         | 0.41%   |
| Minsk          | 7         | 0.41%   |
| Helsinki       | 7         | 0.41%   |
| Bogotá        | 7         | 0.41%   |
| Barcelona      | 7         | 0.41%   |
| Amsterdam      | 7         | 0.41%   |
| Zurich         | 6         | 0.35%   |
| San José      | 6         | 0.35%   |
| Rio de Janeiro | 6         | 0.35%   |
| Naaldwijk      | 6         | 0.35%   |
| Melbourne      | 6         | 0.35%   |
| London         | 6         | 0.35%   |
| Dublin         | 6         | 0.35%   |
| Cologne        | 6         | 0.35%   |
| Brasília      | 6         | 0.35%   |
| Bangkok        | 6         | 0.35%   |
| Atlanta        | 6         | 0.35%   |
| Yekaterinburg  | 5         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 427       | 522    | 20.62%  |
| Sandisk                        | 222       | 250    | 10.72%  |
| WDC                            | 118       | 124    | 5.7%    |
| SK hynix                       | 117       | 123    | 5.65%   |
| Micron Technology              | 117       | 127    | 5.65%   |
| Seagate                        | 114       | 124    | 5.5%    |
| Kingston                       | 104       | 117    | 5.02%   |
| Toshiba                        | 101       | 115    | 4.88%   |
| Unknown                        | 96        | 111    | 4.64%   |
| Intel                          | 92        | 109    | 4.44%   |
| Crucial                        | 47        | 55     | 2.27%   |
| Apple                          | 41        | 54     | 1.98%   |
| KIOXIA                         | 37        | 47     | 1.79%   |
| Phison Electronics             | 29        | 29     | 1.4%    |
| Micron/Crucial Technology      | 27        | 27     | 1.3%    |
| HGST                           | 26        | 26     | 1.26%   |
| Silicon Motion                 | 23        | 23     | 1.11%   |
| Kingston Technology Company    | 23        | 26     | 1.11%   |
| China                          | 23        | 28     | 1.11%   |
| A-DATA Technology              | 22        | 23     | 1.06%   |
| ADATA Technology               | 16        | 17     | 0.77%   |
| JMicron Technology             | 12        | 15     | 0.58%   |
| Hitachi                        | 12        | 13     | 0.58%   |
| Solid State Storage            | 10        | 10     | 0.48%   |
| Netac                          | 10        | 11     | 0.48%   |
| SPCC                           | 8         | 8      | 0.39%   |
| Solid State Storage Technology | 8         | 8      | 0.39%   |
| PNY                            | 8         | 8      | 0.39%   |
| Phison                         | 8         | 10     | 0.39%   |
| Union Memory (Shenzhen)        | 7         | 13     | 0.34%   |
| MAXIO Technology (Hangzhou)    | 7         | 7      | 0.34%   |
| Shenzhen Longsys Electronics   | 6         | 8      | 0.29%   |
| LITEON                         | 6         | 6      | 0.29%   |
| Lenovo                         | 6         | 6      | 0.29%   |
| SABRENT                        | 5         | 5      | 0.24%   |
| Realtek Semiconductor          | 5         | 5      | 0.24%   |
| LITEONIT                       | 5         | 5      | 0.24%   |
| Intenso                        | 5         | 5      | 0.24%   |
| Hewlett-Packard                | 5         | 5      | 0.24%   |
| Gigabyte Technology            | 5         | 6      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 96        | 4.51%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 64        | 3%      |
| Sandisk WD Blue SN550 NVMe SSD 1TB                    | 37        | 1.74%   |
| Unknown MMC Card  64GB                                | 28        | 1.31%   |
| Seagate ST1000LM035-1RK172 1TB                        | 27        | 1.27%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 23        | 1.08%   |
| Kingston SA400S37240G 240GB SSD                       | 23        | 1.08%   |
| Intel SSD 660P Series 1024GB                          | 23        | 1.08%   |
| Kingston SA400S37480G 480GB SSD                       | 22        | 1.03%   |
| Intel SSDPEKNU512GZ 512GB                             | 22        | 1.03%   |
| Toshiba XG6 NVMe SSD Controller 256GB                 | 21        | 0.99%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 21        | 0.99%   |
| Samsung SSD 980 1TB                                   | 19        | 0.89%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 121GB   | 18        | 0.85%   |
| Unknown MMC Card  32GB                                | 16        | 0.75%   |
| Unknown MMC Card  128GB                               | 15        | 0.7%    |
| Toshiba MQ04ABF100 1TB                                | 14        | 0.66%   |
| SK hynix BC501 NVMe Solid State Drive 512GB           | 14        | 0.66%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 14        | 0.66%   |
| Sandisk WD Black SN850 1TB                            | 14        | 0.66%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB       | 13        | 0.61%   |
| Micron 2450_MTFDKBA512TFK 512GB                       | 13        | 0.61%   |
| Phison E12 NVMe Controller 1TB                        | 12        | 0.56%   |
| HGST HTS721010A9E630 1TB                              | 12        | 0.56%   |
| Seagate ST500LT012-1DG142 500GB                       | 11        | 0.52%   |
| JMicron Generic 256GB                                 | 11        | 0.52%   |
| Intel SSDPEKNW512GZL 512GB                            | 11        | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 9         | 0.42%   |
| Sandisk WD Blue SN570 1TB                             | 9         | 0.42%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                      | 9         | 0.42%   |
| Samsung MZALQ512HALU-000L2 512GB                      | 9         | 0.42%   |
| Phison PS5013 E13 NVMe Controller 256GB               | 9         | 0.42%   |
| Toshiba MQ01ABF050 500GB                              | 8         | 0.38%   |
| Toshiba MQ01ABD100 1TB                                | 8         | 0.38%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                  | 8         | 0.38%   |
| SK hynix BC511 512GB                                  | 8         | 0.38%   |
| Sandisk PC SN520 NVMe SSD 256GB                       | 8         | 0.38%   |
| Samsung SSD 870 EVO 1TB                               | 8         | 0.38%   |
| Samsung MZALQ512HBLU-00BL2 512GB                      | 8         | 0.38%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                         | 8         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 106       | 114    | 35.57%  |
| WDC                 | 80        | 85     | 26.85%  |
| Toshiba             | 53        | 59     | 17.79%  |
| HGST                | 26        | 26     | 8.72%   |
| Hitachi             | 12        | 13     | 4.03%   |
| Apple               | 5         | 5      | 1.68%   |
| Unknown             | 4         | 6      | 1.34%   |
| Samsung Electronics | 4         | 4      | 1.34%   |
| Fujitsu             | 3         | 3      | 1.01%   |
| SAGE                | 1         | 1      | 0.34%   |
| QNAP                | 1         | 4      | 0.34%   |
| LaCie               | 1         | 1      | 0.34%   |
| IB                  | 1         | 2      | 0.34%   |
| ACASIS              | 1         | 1      | 0.34%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 110       | 132    | 21.11%  |
| Kingston            | 75        | 83     | 14.4%   |
| SanDisk             | 46        | 49     | 8.83%   |
| Crucial             | 46        | 54     | 8.83%   |
| WDC                 | 30        | 30     | 5.76%   |
| China               | 23        | 28     | 4.41%   |
| Apple               | 23        | 24     | 4.41%   |
| Micron Technology   | 15        | 16     | 2.88%   |
| Toshiba             | 14        | 14     | 2.69%   |
| Intel               | 13        | 17     | 2.5%    |
| A-DATA Technology   | 13        | 13     | 2.5%    |
| SPCC                | 8         | 8      | 1.54%   |
| PNY                 | 8         | 8      | 1.54%   |
| Netac               | 6         | 6      | 1.15%   |
| LITEON              | 6         | 6      | 1.15%   |
| SK hynix            | 5         | 6      | 0.96%   |
| SABRENT             | 5         | 5      | 0.96%   |
| LITEONIT            | 5         | 5      | 0.96%   |
| Hewlett-Packard     | 4         | 4      | 0.77%   |
| Gigabyte Technology | 4         | 5      | 0.77%   |
| Apacer              | 4         | 5      | 0.77%   |
| Team                | 3         | 3      | 0.58%   |
| MidasForce          | 3         | 3      | 0.58%   |
| Lexar               | 3         | 3      | 0.58%   |
| KingSpec            | 3         | 4      | 0.58%   |
| GOODRAM             | 3         | 5      | 0.58%   |
| V-GeN               | 2         | 2      | 0.38%   |
| Transcend           | 2         | 2      | 0.38%   |
| Smartbuy            | 2         | 2      | 0.38%   |
| Ramsta              | 2         | 2      | 0.38%   |
| Patriot             | 2         | 2      | 0.38%   |
| Mushkin             | 2         | 2      | 0.38%   |
| Intenso             | 2         | 2      | 0.38%   |
| Advantech           | 2         | 2      | 0.38%   |
| YS                  | 1         | 1      | 0.19%   |
| XrayDisk            | 1         | 1      | 0.19%   |
| Wibtek              | 1         | 1      | 0.19%   |
| Union Memory        | 1         | 1      | 0.19%   |
| Teclast             | 1         | 1      | 0.19%   |
| SSSTC               | 1         | 1      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1041      | 1304   | 53.3%   |
| SSD     | 493       | 583    | 25.24%  |
| HDD     | 289       | 324    | 14.8%   |
| MMC     | 93        | 105    | 4.76%   |
| Unknown | 37        | 39     | 1.89%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 1036      | 1286   | 54.5%   |
| SATA | 704       | 878    | 37.03%  |
| MMC  | 93        | 105    | 4.89%   |
| SAS  | 68        | 86     | 3.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 500       | 599    | 64.6%   |
| 0.51-1.0   | 251       | 284    | 32.43%  |
| 1.01-2.0   | 20        | 21     | 2.58%   |
| 3.01-4.0   | 2         | 2      | 0.26%   |
| 4.01-10.0  | 1         | 1      | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 418       | 24.57%  |
| 251-500        | 360       | 21.16%  |
| 1001-2000      | 244       | 14.34%  |
| 101-250        | 200       | 11.76%  |
| 1-20           | 165       | 9.7%    |
| Unknown        | 160       | 9.41%   |
| 51-100         | 55        | 3.23%   |
| More than 3000 | 46        | 2.7%    |
| 2001-3000      | 33        | 1.94%   |
| 21-50          | 20        | 1.18%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 610       | 35.16%  |
| 21-50          | 293       | 16.89%  |
| 101-250        | 223       | 12.85%  |
| 51-100         | 186       | 10.72%  |
| Unknown        | 160       | 9.22%   |
| 251-500        | 140       | 8.07%   |
| 501-1000       | 79        | 4.55%   |
| 1001-2000      | 30        | 1.73%   |
| More than 3000 | 8         | 0.46%   |
| 2001-3000      | 6         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                        | Notebooks | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD             | 2         | 2      | 5.88%   |
| Toshiba MQ01ABF050 500GB                     | 2         | 2      | 5.88%   |
| Seagate ST500LT012-1DG142 500GB              | 2         | 2      | 5.88%   |
| HGST HTS721010A9E630 1TB                     | 2         | 2      | 5.88%   |
| YS SSD 240GB                                 | 1         | 1      | 2.94%   |
| Wibtek W800S 512GB SSD                       | 1         | 1      | 2.94%   |
| WDC WD5000LPCX-60VHAT0 500GB                 | 1         | 1      | 2.94%   |
| WDC WD5000BPVT-75HXZT1 500GB                 | 1         | 1      | 2.94%   |
| SSSTC CVB-8D128-HP 128GB                     | 1         | 1      | 2.94%   |
| SK hynix HFS128G39TND-N210A 128GB SSD        | 1         | 1      | 2.94%   |
| Seagate ST9750420AS 752GB                    | 1         | 1      | 2.94%   |
| Seagate ST9500420AS 500GB                    | 1         | 1      | 2.94%   |
| Seagate ST1000LM049-2GH172 1TB               | 1         | 1      | 2.94%   |
| SanDisk SSD PLUS 480GB                       | 1         | 1      | 2.94%   |
| SanDisk SD8SBAT256G1122 256GB SSD            | 1         | 1      | 2.94%   |
| Samsung Electronics SSD 840 PRO Series 256GB | 1         | 1      | 2.94%   |
| Samsung Electronics HD154UI 1TB              | 1         | 1      | 2.94%   |
| Netac NVMe SSD 2TB                           | 1         | 1      | 2.94%   |
| Micron Technology 1100 SATA 256GB SSD        | 1         | 1      | 2.94%   |
| LITEONIT LCT-128M3S 128GB SSD                | 1         | 1      | 2.94%   |
| Kingston SA400S37480G 480GB SSD              | 1         | 1      | 2.94%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD      | 1         | 3      | 2.94%   |
| Intel SSDSC2KF256H6 SATA 256GB               | 1         | 1      | 2.94%   |
| Intel SSDSC2BF180A5H SED 180GB               | 1         | 1      | 2.94%   |
| Intel HBRPEKNX0202AHO 32GB                   | 1         | 1      | 2.94%   |
| Hitachi HTS545025B9SA02 250GB                | 1         | 1      | 2.94%   |
| HGST HTS541010A9E680 1TB                     | 1         | 1      | 2.94%   |
| Crucial CT1050MX300SSD1 1050GB               | 1         | 1      | 2.94%   |
| China SSD 256GB                              | 1         | 1      | 2.94%   |
| Apple HDD HTS545050A7E362 500GB              | 1         | 1      | 2.94%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 14.71%  |
| WDC                 | 4         | 4      | 11.76%  |
| Intel               | 3         | 3      | 8.82%   |
| HGST                | 3         | 3      | 8.82%   |
| Toshiba             | 2         | 2      | 5.88%   |
| SanDisk             | 2         | 2      | 5.88%   |
| Samsung Electronics | 2         | 2      | 5.88%   |
| Kingston            | 2         | 4      | 5.88%   |
| YS                  | 1         | 1      | 2.94%   |
| Wibtek              | 1         | 1      | 2.94%   |
| SSSTC               | 1         | 1      | 2.94%   |
| SK hynix            | 1         | 1      | 2.94%   |
| Netac               | 1         | 1      | 2.94%   |
| Micron Technology   | 1         | 1      | 2.94%   |
| LITEONIT            | 1         | 1      | 2.94%   |
| Hitachi             | 1         | 1      | 2.94%   |
| Crucial             | 1         | 1      | 2.94%   |
| China               | 1         | 1      | 2.94%   |
| Apple               | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 5         | 5      | 33.33%  |
| HGST                | 3         | 3      | 20%     |
| WDC                 | 2         | 2      | 13.33%  |
| Toshiba             | 2         | 2      | 13.33%  |
| Samsung Electronics | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |
| Apple               | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 17        | 19     | 50%     |
| HDD  | 15        | 15     | 44.12%  |
| NVMe | 2         | 2      | 5.88%   |

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
| Detected | 1125      | 1559   | 64.4%   |
| Works    | 589       | 760    | 33.71%  |
| Malfunc  | 33        | 36     | 1.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 903       | 42.1%   |
| Samsung Electronics                     | 328       | 15.29%  |
| AMD                                     | 182       | 8.48%   |
| SanDisk                                 | 180       | 8.39%   |
| SK hynix                                | 112       | 5.22%   |
| Micron Technology                       | 102       | 4.76%   |
| Kingston Technology Company             | 54        | 2.52%   |
| Toshiba America Info Systems            | 38        | 1.77%   |
| Phison Electronics                      | 35        | 1.63%   |
| KIOXIA                                  | 34        | 1.59%   |
| Micron/Crucial Technology               | 27        | 1.26%   |
| Silicon Motion                          | 25        | 1.17%   |
| ADATA Technology                        | 24        | 1.12%   |
| Solid State Storage Technology          | 19        | 0.89%   |
| Apple                                   | 12        | 0.56%   |
| Union Memory (Shenzhen)                 | 10        | 0.47%   |
| Nvidia                                  | 10        | 0.47%   |
| MAXIO Technology (Hangzhou)             | 8         | 0.37%   |
| Shenzhen Longsys Electronics            | 6         | 0.28%   |
| Yangtze Memory Technologies             | 5         | 0.23%   |
| Realtek Semiconductor                   | 5         | 0.23%   |
| Netac Technology                        | 5         | 0.23%   |
| Marvell Technology Group                | 5         | 0.23%   |
| Lenovo                                  | 5         | 0.23%   |
| Solidigm                                | 3         | 0.14%   |
| Shenzhen Unionmemory Information System | 2         | 0.09%   |
| Seagate Technology                      | 2         | 0.09%   |
| Lite-On Technology                      | 1         | 0.05%   |
| INNOGRIT                                | 1         | 0.05%   |
| Biwin Storage Technology                | 1         | 0.05%   |
| ASMedia Technology                      | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 176       | 7.81%   |
| Intel Volume Management Device NVMe RAID Controller                            | 118       | 5.24%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 109       | 4.84%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 105       | 4.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 104       | 4.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 82        | 3.64%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 73        | 3.24%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 64        | 2.84%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 51        | 2.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 46        | 2.04%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 41        | 1.82%   |
| Intel Tiger Lake-LP SATA Controller                                            | 39        | 1.73%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 38        | 1.69%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 36        | 1.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 36        | 1.6%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 34        | 1.51%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 30        | 1.33%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 30        | 1.33%   |
| Intel Comet Lake SATA AHCI Controller                                          | 27        | 1.2%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 25        | 1.11%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 24        | 1.07%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 24        | 1.07%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 24        | 1.07%   |
| Intel SSD 660P Series                                                          | 23        | 1.02%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 23        | 1.02%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 22        | 0.98%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 22        | 0.98%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 21        | 0.93%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 21        | 0.93%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 21        | 0.93%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 21        | 0.93%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 20        | 0.89%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 19        | 0.84%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 18        | 0.8%    |
| SK hynix BC501 NVMe Solid State Drive                                          | 16        | 0.71%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 16        | 0.71%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 16        | 0.71%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 15        | 0.67%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 15        | 0.67%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 15        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 1029      | 47.91%  |
| SATA | 879       | 40.92%  |
| RAID | 211       | 9.82%   |
| IDE  | 29        | 1.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1264      | 75.37%  |
| AMD          | 410       | 24.45%  |
| CentaurHauls | 1         | 0.06%   |
| ARM          | 1         | 0.06%   |
| Unknown      | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 57        | 3.4%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 32        | 1.91%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 31        | 1.85%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 29        | 1.73%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 25        | 1.49%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 24        | 1.43%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 21        | 1.25%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 21        | 1.25%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 21        | 1.25%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 21        | 1.25%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 21        | 1.25%   |
| Intel 12th Gen Core i7-12700H                 | 20        | 1.19%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 1.13%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 18        | 1.07%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 17        | 1.01%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 17        | 1.01%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 17        | 1.01%   |
| Intel 12th Gen Core i7-1255U                  | 17        | 1.01%   |
| Intel 12th Gen Core i5-12500H                 | 17        | 1.01%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 17        | 1.01%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 0.95%   |
| Intel 12th Gen Core i5-1235U                  | 16        | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.89%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 15        | 0.89%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 15        | 0.89%   |
| Intel 12th Gen Core i7-1260P                  | 14        | 0.83%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 14        | 0.83%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.77%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 13        | 0.77%   |
| AMD Ryzen 7 5825U with Radeon Graphics        | 13        | 0.77%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.72%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 0.72%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.72%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 12        | 0.72%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 12        | 0.72%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 12        | 0.72%   |
| Intel 12th Gen Core i5-1240P                  | 11        | 0.66%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 10        | 0.6%    |
| Intel Core i5-5300U CPU @ 2.30GHz             | 10        | 0.6%    |
| Intel Core i5-10300H CPU @ 2.50GHz            | 10        | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Other                   | 366       | 21.81%  |
| Intel Core i5           | 362       | 21.57%  |
| Intel Core i7           | 305       | 18.18%  |
| AMD Ryzen 7             | 148       | 8.82%   |
| AMD Ryzen 5             | 128       | 7.63%   |
| Intel Core i3           | 81        | 4.83%   |
| Intel Celeron           | 59        | 3.52%   |
| Intel Core 2 Duo        | 34        | 2.03%   |
| AMD Ryzen 9             | 32        | 1.91%   |
| AMD Ryzen 7 PRO         | 20        | 1.19%   |
| AMD Ryzen 3             | 18        | 1.07%   |
| Intel Atom              | 16        | 0.95%   |
| Intel Pentium           | 13        | 0.77%   |
| Intel Pentium Silver    | 11        | 0.66%   |
| AMD Ryzen 5 PRO         | 11        | 0.66%   |
| AMD A6                  | 11        | 0.66%   |
| AMD A10                 | 9         | 0.54%   |
| AMD A8                  | 7         | 0.42%   |
| Intel Core i9           | 5         | 0.3%    |
| Intel Pentium Dual      | 3         | 0.18%   |
| Intel Genuine           | 3         | 0.18%   |
| Intel Core m5           | 3         | 0.18%   |
| AMD E2                  | 3         | 0.18%   |
| AMD E1                  | 3         | 0.18%   |
| AMD Athlon              | 3         | 0.18%   |
| AMD A4                  | 3         | 0.18%   |
| Intel Xeon              | 2         | 0.12%   |
| Intel Pentium Dual-Core | 2         | 0.12%   |
| Intel Core m3           | 2         | 0.12%   |
| Intel Core M            | 2         | 0.12%   |
| Intel Core 2            | 2         | 0.12%   |
| Intel Celeron Dual-Core | 2         | 0.12%   |
| AMD A12                 | 2         | 0.12%   |
| Intel Core 2 Quad       | 1         | 0.06%   |
| AMD Turion II Dual-Core | 1         | 0.06%   |
| AMD Ryzen 3 PRO         | 1         | 0.06%   |
| AMD FX                  | 1         | 0.06%   |
| AMD Athlon X2           | 1         | 0.06%   |
| AMD Athlon II Dual-Core | 1         | 0.06%   |
| AMD Athlon II           | 1         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 560       | 33.39%  |
| 2      | 543       | 32.38%  |
| 8      | 230       | 13.71%  |
| 6      | 165       | 9.84%   |
| 12     | 57        | 3.4%    |
| 14     | 55        | 3.28%   |
| 10     | 53        | 3.16%   |
| 1      | 5         | 0.3%    |
| 24     | 4         | 0.24%   |
| 16     | 4         | 0.24%   |
| 20     | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1677      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1470      | 87.6%   |
| 1      | 208       | 12.4%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1675      | 99.88%  |
| 64-bit         | 2         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1285      | 76.35%  |
| 0x0a50000c | 68        | 4.04%   |
| 0x0a50000d | 38        | 2.26%   |
| 0x0a404102 | 35        | 2.08%   |
| 0x08608103 | 33        | 1.96%   |
| 0x08600106 | 29        | 1.72%   |
| 0x08108109 | 28        | 1.66%   |
| 0x08600104 | 17        | 1.01%   |
| 0x08108102 | 17        | 1.01%   |
| 0x0a404101 | 12        | 0.71%   |
| 0x06006705 | 10        | 0.59%   |
| 0x08a00008 | 9         | 0.53%   |
| 0x08608102 | 9         | 0.53%   |
| 0x08600103 | 7         | 0.42%   |
| 0x0a704103 | 5         | 0.3%    |
| 0x0a601203 | 5         | 0.3%    |
| 0x08608104 | 5         | 0.3%    |
| 0x08600109 | 5         | 0.3%    |
| 0x06001119 | 5         | 0.3%    |
| 0x0810100b | 4         | 0.24%   |
| 0x08101007 | 4         | 0.24%   |
| 0x0700010f | 4         | 0.24%   |
| 0x0a704101 | 3         | 0.18%   |
| 0x0a50000b | 3         | 0.18%   |
| 0x07030105 | 3         | 0.18%   |
| 0x06006118 | 3         | 0.18%   |
| 0x0600111f | 3         | 0.18%   |
| 0x06001116 | 3         | 0.18%   |
| 0x08101016 | 2         | 0.12%   |
| 0x07030104 | 2         | 0.12%   |
| 0x0600611a | 2         | 0.12%   |
| 0x06006110 | 2         | 0.12%   |
| 0x906ea    | 1         | 0.06%   |
| 0x806e9    | 1         | 0.06%   |
| 0x806c1    | 1         | 0.06%   |
| 0x506c9    | 1         | 0.06%   |
| 0x406e3    | 1         | 0.06%   |
| 0x40651    | 1         | 0.06%   |
| 0x306a9    | 1         | 0.06%   |
| 0x10676    | 1         | 0.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 314       | 18.71%  |
| Alderlake Hybrid  | 174       | 10.37%  |
| TigerLake         | 147       | 8.76%   |
| Unknown           | 139       | 8.28%   |
| Zen 3             | 115       | 6.85%   |
| IvyBridge         | 84        | 5.01%   |
| Haswell           | 81        | 4.83%   |
| Skylake           | 79        | 4.71%   |
| SandyBridge       | 64        | 3.81%   |
| Zen 2             | 61        | 3.64%   |
| IceLake           | 56        | 3.34%   |
| CometLake         | 48        | 2.86%   |
| Zen+              | 47        | 2.8%    |
| Broadwell         | 44        | 2.62%   |
| Silvermont        | 34        | 2.03%   |
| Westmere          | 33        | 1.97%   |
| Penryn            | 33        | 1.97%   |
| Goldmont plus     | 31        | 1.85%   |
| Excavator         | 18        | 1.07%   |
| Zen               | 13        | 0.77%   |
| Core              | 12        | 0.72%   |
| Piledriver        | 11        | 0.66%   |
| Goldmont          | 11        | 0.66%   |
| Puma              | 7         | 0.42%   |
| Tremont           | 6         | 0.36%   |
| Jaguar            | 4         | 0.24%   |
| K10               | 3         | 0.18%   |
| Steamroller       | 2         | 0.12%   |
| Nehalem           | 2         | 0.12%   |
| Meteorlake Hybrid | 1         | 0.06%   |
| K8 Hammer         | 1         | 0.06%   |
| K8 & K10 hybrid   | 1         | 0.06%   |
| Bonnell           | 1         | 0.06%   |
| Bobcat            | 1         | 0.06%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 1197      | 55.78%  |
| Nvidia  | 495       | 23.07%  |
| AMD     | 453       | 21.11%  |
| Zhaoxin | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 136       | 6.22%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 78        | 3.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 76        | 3.48%   |
| Intel UHD Graphics 620                                                                   | 73        | 3.34%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 70        | 3.2%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 62        | 2.83%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 61        | 2.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 54        | 2.47%   |
| Intel HD Graphics 620                                                                    | 51        | 2.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 51        | 2.33%   |
| AMD Rembrandt [Radeon 680M]                                                              | 50        | 2.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 49        | 2.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 49        | 2.24%   |
| AMD Lucienne                                                                             | 49        | 2.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 48        | 2.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 47        | 2.15%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 42        | 1.92%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 38        | 1.74%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 34        | 1.55%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 34        | 1.55%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 31        | 1.42%   |
| Intel HD Graphics 5500                                                                   | 31        | 1.42%   |
| AMD Barcelo                                                                              | 30        | 1.37%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 27        | 1.23%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 26        | 1.19%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 23        | 1.05%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 1.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 23        | 1.05%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 20        | 0.91%   |
| Intel HD Graphics 630                                                                    | 20        | 0.91%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 19        | 0.87%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 19        | 0.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 19        | 0.87%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 18        | 0.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 16        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 15        | 0.69%   |
| Nvidia GP108M [GeForce MX150]                                                            | 12        | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 12        | 0.55%   |
| Nvidia AD106M [GeForce RTX 4070 Max-Q / Mobile]                                          | 12        | 0.55%   |
| Intel HD Graphics 530                                                                    | 12        | 0.55%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 799       | 47.47%  |
| Intel + Nvidia | 347       | 20.62%  |
| 1 x AMD        | 306       | 18.18%  |
| AMD + Nvidia   | 82        | 4.87%   |
| 1 x Nvidia     | 67        | 3.98%   |
| Intel + AMD    | 40        | 2.38%   |
| 2 x AMD        | 26        | 1.54%   |
| 2 x Intel      | 9         | 0.53%   |
| Other          | 5         | 0.3%    |
| 2 x Nvidia     | 1         | 0.06%   |
| 1 x Zhaoxin    | 1         | 0.06%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1429      | 84.66%  |
| Proprietary | 217       | 12.86%  |
| Unknown     | 42        | 2.49%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1037      | 61.18%  |
| 0.01-0.5   | 221       | 13.04%  |
| 1.01-2.0   | 153       | 9.03%   |
| 3.01-4.0   | 128       | 7.55%   |
| 0.51-1.0   | 90        | 5.31%   |
| 5.01-6.0   | 31        | 1.83%   |
| 7.01-8.0   | 24        | 1.42%   |
| 8.01-16.0  | 9         | 0.53%   |
| 2.01-3.0   | 2         | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 383       | 19.15%  |
| AU Optronics            | 311       | 15.55%  |
| Chimei Innolux          | 288       | 14.4%   |
| LG Display              | 190       | 9.5%    |
| Samsung Electronics     | 170       | 8.5%    |
| Dell                    | 79        | 3.95%   |
| Apple                   | 78        | 3.9%    |
| Goldstar                | 65        | 3.25%   |
| Sharp                   | 62        | 3.1%    |
| Lenovo                  | 39        | 1.95%   |
| PANDA                   | 35        | 1.75%   |
| CSO                     | 33        | 1.65%   |
| InfoVision              | 24        | 1.2%    |
| Hewlett-Packard         | 23        | 1.15%   |
| Chi Mei Optoelectronics | 21        | 1.05%   |
| AOC                     | 17        | 0.85%   |
| TMX                     | 15        | 0.75%   |
| Philips                 | 14        | 0.7%    |
| Acer                    | 14        | 0.7%    |
| ASUSTek Computer        | 12        | 0.6%    |
| BenQ                    | 10        | 0.5%    |
| Ancor Communications    | 9         | 0.45%   |
| LG Philips              | 8         | 0.4%    |
| Iiyama                  | 8         | 0.4%    |
| MSI                     | 7         | 0.35%   |
| Gigabyte Technology     | 6         | 0.3%    |
| ViewSonic               | 5         | 0.25%   |
| Unknown                 | 4         | 0.2%    |
| Panasonic               | 4         | 0.2%    |
| HKC                     | 4         | 0.2%    |
| Toshiba                 | 3         | 0.15%   |
| Sony                    | 3         | 0.15%   |
| NEC Computers           | 3         | 0.15%   |
| ___                     | 2         | 0.1%    |
| Vizio                   | 2         | 0.1%    |
| Unknown (XXX)           | 2         | 0.1%    |
| Tianma XM               | 2         | 0.1%    |
| SKY                     | 2         | 0.1%    |
| Pixio                   | 2         | 0.1%    |
| KDC                     | 2         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 18        | 0.89%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 16        | 0.79%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 13        | 0.64%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 12        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 11        | 0.54%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                 | 11        | 0.54%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 11        | 0.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 11        | 0.54%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 10        | 0.49%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 10        | 0.49%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                 | 9         | 0.44%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                 | 9         | 0.44%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 9         | 0.44%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 9         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 8         | 0.39%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                  | 8         | 0.39%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 7         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 7         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 7         | 0.35%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                 | 7         | 0.35%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 7         | 0.35%   |
| AU Optronics LCD Monitor AUO408D 1920x1080 309x174mm 14.0-inch        | 7         | 0.35%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 6         | 0.3%    |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 6         | 0.3%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 6         | 0.3%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch       | 6         | 0.3%    |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 6         | 0.3%    |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                  | 6         | 0.3%    |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 6         | 0.3%    |
| AU Optronics LCD Monitor AUO369F 1920x1080 344x194mm 15.5-inch        | 6         | 0.3%    |
| Apple LCD Monitor APP9CC3 1280x800 286x179mm 13.3-inch                | 6         | 0.3%    |
| LG Display LCD Monitor LGD071D 1920x1080 344x194mm 15.5-inch          | 5         | 0.25%   |
| LG Display LCD Monitor LGD06B3 1920x1200 336x210mm 15.6-inch          | 5         | 0.25%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch           | 5         | 0.25%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 5         | 0.25%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 5         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 892       | 47.73%  |
| 1366x768 (WXGA)    | 330       | 17.66%  |
| 3840x2160 (4K)     | 88        | 4.71%   |
| 2560x1600          | 83        | 4.44%   |
| 2560x1440 (QHD)    | 78        | 4.17%   |
| 1920x1200 (WUXGA)  | 74        | 3.96%   |
| 1600x900 (HD+)     | 46        | 2.46%   |
| 1280x800 (WXGA)    | 44        | 2.35%   |
| 2880x1800          | 39        | 2.09%   |
| 1440x900 (WXGA+)   | 27        | 1.44%   |
| 3440x1440          | 21        | 1.12%   |
| 2560x1080          | 20        | 1.07%   |
| 3840x2400          | 16        | 0.86%   |
| 2160x1440          | 14        | 0.75%   |
| 2256x1504          | 13        | 0.7%    |
| 1680x1050 (WSXGA+) | 10        | 0.54%   |
| 3200x2000          | 7         | 0.37%   |
| 2880x1620          | 7         | 0.37%   |
| 1280x1024 (SXGA)   | 7         | 0.37%   |
| 2240x1400          | 6         | 0.32%   |
| 2520x1680          | 5         | 0.27%   |
| 2160x1350          | 5         | 0.27%   |
| 3840x1600          | 4         | 0.21%   |
| 3456x2160          | 4         | 0.21%   |
| 1920x1280          | 4         | 0.21%   |
| 3200x1800 (QHD+)   | 3         | 0.16%   |
| 3072x1920          | 3         | 0.16%   |
| 3000x2000          | 3         | 0.16%   |
| 1360x768           | 3         | 0.16%   |
| 3840x1100          | 2         | 0.11%   |
| 3840x1080          | 2         | 0.11%   |
| 2304x1440          | 2         | 0.11%   |
| 1024x768 (XGA)     | 2         | 0.11%   |
| 800x1280           | 1         | 0.05%   |
| 3120x2080          | 1         | 0.05%   |
| 2944x1840          | 1         | 0.05%   |
| 2288x1287          | 1         | 0.05%   |
| 1920x540           | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 726       | 36.25%  |
| 13      | 329       | 16.43%  |
| 14      | 326       | 16.28%  |
| 27      | 84        | 4.19%   |
| 16      | 81        | 4.04%   |
| 17      | 76        | 3.79%   |
| 24      | 68        | 3.39%   |
| 23      | 51        | 2.55%   |
| 21      | 43        | 2.15%   |
| 12      | 41        | 2.05%   |
| 34      | 36        | 1.8%    |
| 31      | 21        | 1.05%   |
| 11      | 20        | 1%      |
| 18      | 11        | 0.55%   |
| 28      | 9         | 0.45%   |
| 19      | 7         | 0.35%   |
| 84      | 6         | 0.3%    |
| 72      | 6         | 0.3%    |
| 32      | 6         | 0.3%    |
| 22      | 6         | 0.3%    |
| 20      | 6         | 0.3%    |
| 40      | 5         | 0.25%   |
| 10      | 5         | 0.25%   |
| 54      | 4         | 0.2%    |
| 37      | 4         | 0.2%    |
| Unknown | 4         | 0.2%    |
| 25      | 3         | 0.15%   |
| 52      | 2         | 0.1%    |
| 49      | 2         | 0.1%    |
| 35      | 2         | 0.1%    |
| 142     | 1         | 0.05%   |
| 95      | 1         | 0.05%   |
| 86      | 1         | 0.05%   |
| 65      | 1         | 0.05%   |
| 64      | 1         | 0.05%   |
| 63      | 1         | 0.05%   |
| 55      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 42      | 1         | 0.05%   |
| 38      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1245      | 62.78%  |
| 201-300        | 257       | 12.96%  |
| 501-600        | 181       | 9.13%   |
| 351-400        | 100       | 5.04%   |
| 401-500        | 69        | 3.48%   |
| 701-800        | 43        | 2.17%   |
| 601-700        | 42        | 2.12%   |
| 1001-1500      | 14        | 0.71%   |
| 1501-2000      | 13        | 0.66%   |
| 801-900        | 12        | 0.61%   |
| Unknown        | 4         | 0.2%    |
| More than 2000 | 1         | 0.05%   |
| 901-1000       | 1         | 0.05%   |
| 1-100          | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1323      | 75.56%  |
| 16/10   | 322       | 18.39%  |
| 21/9    | 45        | 2.57%   |
| 3/2     | 41        | 2.34%   |
| 5/4     | 7         | 0.4%    |
| 4/3     | 4         | 0.23%   |
| 32/9    | 3         | 0.17%   |
| 3.40    | 2         | 0.11%   |
| 1.00    | 1         | 0.06%   |
| 0.67    | 1         | 0.06%   |
| 0.56    | 1         | 0.06%   |
| Unknown | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 735       | 36.73%  |
| 81-90          | 525       | 26.24%  |
| 201-250        | 131       | 6.55%   |
| 71-80          | 118       | 5.9%    |
| 301-350        | 87        | 4.35%   |
| 121-130        | 71        | 3.55%   |
| 111-120        | 71        | 3.55%   |
| 351-500        | 70        | 3.5%    |
| 61-70          | 39        | 1.95%   |
| 251-300        | 33        | 1.65%   |
| More than 1000 | 25        | 1.25%   |
| 51-60          | 22        | 1.1%    |
| 151-200        | 22        | 1.1%    |
| 141-150        | 14        | 0.7%    |
| 501-1000       | 14        | 0.7%    |
| 91-100         | 11        | 0.55%   |
| 41-50          | 5         | 0.25%   |
| Unknown        | 4         | 0.2%    |
| 131-140        | 3         | 0.15%   |
| 1-40           | 1         | 0.05%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 873       | 44.47%  |
| 101-120       | 422       | 21.5%   |
| 161-240       | 293       | 14.93%  |
| 51-100        | 264       | 13.45%  |
| More than 240 | 92        | 4.69%   |
| 1-50          | 15        | 0.76%   |
| Unknown       | 4         | 0.2%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1282      | 75.46%  |
| 2     | 319       | 18.78%  |
| 0     | 52        | 3.06%   |
| 3     | 44        | 2.59%   |
| 4     | 2         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 958       | 37.84%  |
| Realtek Semiconductor             | 862       | 34.04%  |
| Qualcomm Atheros                  | 178       | 7.03%   |
| Broadcom                          | 160       | 6.32%   |
| MediaTek                          | 111       | 4.38%   |
| Broadcom Limited                  | 31        | 1.22%   |
| ASIX Electronics                  | 29        | 1.15%   |
| Qualcomm                          | 23        | 0.91%   |
| Lenovo                            | 20        | 0.79%   |
| Samsung Electronics               | 17        | 0.67%   |
| TP-Link                           | 15        | 0.59%   |
| Ralink Technology                 | 15        | 0.59%   |
| Xiaomi                            | 11        | 0.43%   |
| Sierra Wireless                   | 11        | 0.43%   |
| DisplayLink                       | 9         | 0.36%   |
| Ralink                            | 8         | 0.32%   |
| Nvidia                            | 8         | 0.32%   |
| Dell                              | 7         | 0.28%   |
| Marvell Technology Group          | 6         | 0.24%   |
| Google                            | 5         | 0.2%    |
| OPPO Electronics                  | 4         | 0.16%   |
| Hewlett-Packard                   | 4         | 0.16%   |
| Qualcomm Atheros Communications   | 3         | 0.12%   |
| Microsoft                         | 3         | 0.12%   |
| JMicron Technology                | 3         | 0.12%   |
| Huawei Technologies               | 3         | 0.12%   |
| ASUSTek Computer                  | 3         | 0.12%   |
| Apple                             | 3         | 0.12%   |
| NetGear                           | 2         | 0.08%   |
| Ericsson Business Mobile Networks | 2         | 0.08%   |
| D-Link                            | 2         | 0.08%   |
| ZyDAS                             | 1         | 0.04%   |
| WEMOS.CC                          | 1         | 0.04%   |
| U-Blox                            | 1         | 0.04%   |
| Sitecom Europe                    | 1         | 0.04%   |
| Shenzhen Goodix Technology        | 1         | 0.04%   |
| Quectel Wireless Solutions        | 1         | 0.04%   |
| Qualcomm Technologies             | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.04%   |
| INGENICO                          | 1         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 515       | 16.97%  |
| Intel Wi-Fi 6 AX201                                               | 116       | 3.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 101       | 3.33%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 101       | 3.33%   |
| Intel Wi-Fi 6 AX200                                               | 92        | 3.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 88        | 2.9%    |
| Intel Wireless 8265 / 8275                                        | 87        | 2.87%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 63        | 2.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 62        | 2.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 51        | 1.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 50        | 1.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 46        | 1.52%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 42        | 1.38%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 40        | 1.32%   |
| Intel Wireless 7265                                               | 39        | 1.29%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 39        | 1.29%   |
| Intel Raptor Lake PCH CNVi WiFi                                   | 38        | 1.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38        | 1.25%   |
| Intel Wireless 7260                                               | 37        | 1.22%   |
| Intel Ethernet Connection (4) I219-LM                             | 36        | 1.19%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 34        | 1.12%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 34        | 1.12%   |
| Intel Wireless 8260                                               | 33        | 1.09%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 32        | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 32        | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 29        | 0.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 27        | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                     | 27        | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 0.86%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 25        | 0.82%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 25        | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23        | 0.76%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 0.76%   |
| Intel Wireless 3165                                               | 22        | 0.73%   |
| Intel Ethernet Connection I219-LM                                 | 21        | 0.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 20        | 0.66%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 19        | 0.63%   |
| Intel Ethernet Connection (16) I219-V                             | 19        | 0.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 18        | 0.59%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 18        | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 931       | 53.94%  |
| Realtek Semiconductor                 | 268       | 15.53%  |
| Qualcomm Atheros                      | 156       | 9.04%   |
| Broadcom                              | 145       | 8.4%    |
| MediaTek                              | 110       | 6.37%   |
| Broadcom Limited                      | 27        | 1.56%   |
| Qualcomm                              | 16        | 0.93%   |
| Ralink Technology                     | 15        | 0.87%   |
| TP-Link                               | 13        | 0.75%   |
| Sierra Wireless                       | 11        | 0.64%   |
| Ralink                                | 8         | 0.46%   |
| Dell                                  | 5         | 0.29%   |
| Qualcomm Atheros Communications       | 3         | 0.17%   |
| ASUSTek Computer                      | 3         | 0.17%   |
| NetGear                               | 2         | 0.12%   |
| D-Link                                | 2         | 0.12%   |
| ZyDAS                                 | 1         | 0.06%   |
| Sitecom Europe                        | 1         | 0.06%   |
| Quectel Wireless Solutions            | 1         | 0.06%   |
| Qualcomm Technologies                 | 1         | 0.06%   |
| Microsoft                             | 1         | 0.06%   |
| Hewlett-Packard                       | 1         | 0.06%   |
| Edimax Technology                     | 1         | 0.06%   |
| D-Link System                         | 1         | 0.06%   |
| AVM                                   | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |
| Unknown                               | 1         | 0.06%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 116       | 6.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 100       | 5.77%   |
| Intel Wi-Fi 6 AX200                                                  | 92        | 5.31%   |
| Intel Wireless 8265 / 8275                                           | 87        | 5.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 63        | 3.63%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter        | 62        | 3.58%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 51        | 2.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 50        | 2.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 46        | 2.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                               | 42        | 2.42%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller          | 40        | 2.31%   |
| Intel Wireless 7265                                                  | 39        | 2.25%   |
| Intel Comet Lake PCH CNVi WiFi                                       | 39        | 2.25%   |
| Intel Raptor Lake PCH CNVi WiFi                                      | 38        | 2.19%   |
| Intel Wireless 7260                                                  | 37        | 2.13%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 34        | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                      | 34        | 1.96%   |
| Intel Wireless 8260                                                  | 33        | 1.9%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 32        | 1.85%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 32        | 1.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 29        | 1.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 27        | 1.56%   |
| Broadcom BCM43142 802.11b/g/n                                        | 27        | 1.56%   |
| Broadcom BCM4331 802.11a/b/g/n                                       | 25        | 1.44%   |
| Intel Wireless 3165                                                  | 22        | 1.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 20        | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 19        | 1.1%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 18        | 1.04%   |
| Broadcom BCM43228 802.11a/b/g/n                                      | 18        | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 15        | 0.87%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 14        | 0.81%   |
| Qualcomm QCNFA765 Wireless Network Adapter                           | 13        | 0.75%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 12        | 0.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 12        | 0.69%   |
| Intel Wireless-AC 9260                                               | 12        | 0.69%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 12        | 0.69%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                          | 12        | 0.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                  | 11        | 0.63%   |
| Intel Centrino Ultimate-N 6300                                       | 10        | 0.58%   |
| Intel Centrino Advanced-N 6200                                       | 10        | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 729       | 57.86%  |
| Intel                         | 312       | 24.76%  |
| Broadcom                      | 48        | 3.81%   |
| Qualcomm Atheros              | 34        | 2.7%    |
| ASIX Electronics              | 29        | 2.3%    |
| Lenovo                        | 20        | 1.59%   |
| Samsung Electronics           | 17        | 1.35%   |
| Xiaomi                        | 11        | 0.87%   |
| DisplayLink                   | 9         | 0.71%   |
| Nvidia                        | 8         | 0.63%   |
| Qualcomm                      | 7         | 0.56%   |
| Marvell Technology Group      | 6         | 0.48%   |
| Google                        | 5         | 0.4%    |
| OPPO Electronics              | 4         | 0.32%   |
| Broadcom Limited              | 4         | 0.32%   |
| JMicron Technology            | 3         | 0.24%   |
| Huawei Technologies           | 3         | 0.24%   |
| Apple                         | 3         | 0.24%   |
| TP-Link                       | 2         | 0.16%   |
| Microsoft                     | 2         | 0.16%   |
| OnePlus Technology (Shenzhen) | 1         | 0.08%   |
| MediaTek                      | 1         | 0.08%   |
| Hewlett-Packard               | 1         | 0.08%   |
| Foxconn / Hon Hai             | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 515       | 40.05%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 101       | 7.85%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 88        | 6.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 38        | 2.95%   |
| Intel Ethernet Connection (4) I219-LM                             | 36        | 2.8%    |
| ASIX AX88179 Gigabit Ethernet                                     | 26        | 2.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 25        | 1.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23        | 1.79%   |
| Intel Ethernet Connection (4) I219-V                              | 23        | 1.79%   |
| Intel Ethernet Connection I219-LM                                 | 21        | 1.63%   |
| Intel Ethernet Connection (16) I219-V                             | 19        | 1.48%   |
| Intel Ethernet Connection I217-LM                                 | 16        | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15        | 1.17%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 14        | 1.09%   |
| Intel Ethernet Connection (3) I218-LM                             | 13        | 1.01%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.86%   |
| Intel Ethernet Connection (16) I219-LM                            | 11        | 0.86%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 0.86%   |
| Intel Ethernet Connection (6) I219-V                              | 10        | 0.78%   |
| Intel Ethernet Connection (6) I219-LM                             | 10        | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 9         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 8         | 0.62%   |
| Nvidia MCP79 Ethernet                                             | 8         | 0.62%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 8         | 0.62%   |
| Intel Ethernet Connection (13) I219-LM                            | 7         | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 7         | 0.54%   |
| Qualcomm SDM630-MTP _SN:0B9EB96E                                  | 6         | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 6         | 0.47%   |
| Intel Ethernet Connection I219-V                                  | 6         | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 6         | 0.47%   |
| Intel Ethernet Connection (10) I219-V                             | 6         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.39%   |
| Intel Ethernet Connection (13) I219-V                             | 5         | 0.39%   |
| DisplayLink Dell Universal Dock D6000                             | 5         | 0.39%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 5         | 0.39%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 0.31%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1651      | 57.85%  |
| Ethernet | 1189      | 41.66%  |
| Modem    | 9         | 0.32%   |
| Unknown  | 5         | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1401      | 79.92%  |
| Ethernet | 352       | 20.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1026      | 61.18%  |
| 1     | 609       | 36.31%  |
| 0     | 29        | 1.73%   |
| 3     | 13        | 0.78%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1169      | 68.93%  |
| Yes  | 527       | 31.07%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 804       | 54.55%  |
| Realtek Semiconductor           | 169       | 11.47%  |
| Qualcomm Atheros Communications | 88        | 5.97%   |
| Foxconn / Hon Hai               | 81        | 5.5%    |
| IMC Networks                    | 76        | 5.16%   |
| Apple                           | 65        | 4.41%   |
| Broadcom                        | 58        | 3.93%   |
| Lite-On Technology              | 38        | 2.58%   |
| Realtek                         | 19        | 1.29%   |
| Dell                            | 11        | 0.75%   |
| USI                             | 10        | 0.68%   |
| Toshiba                         | 8         | 0.54%   |
| Hewlett-Packard                 | 7         | 0.47%   |
| Ralink                          | 6         | 0.41%   |
| Opticis                         | 6         | 0.41%   |
| MediaTek                        | 6         | 0.41%   |
| Cambridge Silicon Radio         | 6         | 0.41%   |
| Foxconn International           | 4         | 0.27%   |
| ASUSTek Computer                | 4         | 0.27%   |
| Askey Computer                  | 2         | 0.14%   |
| TP-Link                         | 1         | 0.07%   |
| Taiyo Yuden                     | 1         | 0.07%   |
| Syntek                          | 1         | 0.07%   |
| Smart Modular Technologies      | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |
| Dynex                           | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 225       | 15.24%  |
| Intel Bluetooth wireless interface                  | 198       | 13.41%  |
| Realtek Bluetooth Radio                             | 142       | 9.62%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 114       | 7.72%   |
| Intel Bluetooth Device                              | 105       | 7.11%   |
| Intel AX200 Bluetooth                               | 89        | 6.03%   |
| Qualcomm Atheros  Bluetooth Device                  | 52        | 3.52%   |
| Foxconn / Hon Hai Wireless_Device                   | 48        | 3.25%   |
| IMC Networks Wireless_Device                        | 43        | 2.91%   |
| Intel AX210 Bluetooth                               | 39        | 2.64%   |
| Apple Bluetooth Host Controller                     | 34        | 2.3%    |
| Apple Bluetooth USB Host Controller                 | 24        | 1.63%   |
| IMC Networks Bluetooth Radio                        | 22        | 1.49%   |
| Realtek  Bluetooth 4.2 Adapter                      | 20        | 1.36%   |
| Realtek Bluetooth Radio                             | 19        | 1.29%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 15        | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 0.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 0.81%   |
| Lite-On Wireless_Device                             | 11        | 0.75%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 11        | 0.75%   |
| USI Bluetooth Device                                | 10        | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.68%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 10        | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 10        | 0.68%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 0.68%   |
| IMC Networks Bluetooth Device                       | 9         | 0.61%   |
| Broadcom HP Portable Bumble Bee                     | 7         | 0.47%   |
| Broadcom BCM43142 Bluetooth 4.0                     | 7         | 0.47%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 7         | 0.47%   |
| Broadcom BCM2045B (BDC-2.1)                         | 7         | 0.47%   |
| Ralink RT3290 Bluetooth                             | 6         | 0.41%   |
| Opticis Bluetooth Radio                             | 6         | 0.41%   |
| MediaTek Wireless_Device                            | 6         | 0.41%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.41%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 0.41%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 6         | 0.41%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 6         | 0.41%   |
| Lite-On Bluetooth Device                            | 5         | 0.34%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.34%   |
| Broadcom HP Portable SoftSailing                    | 5         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 1240      | 56.85%  |
| AMD                   | 424       | 19.44%  |
| Nvidia                | 307       | 14.08%  |
| Lenovo                | 31        | 1.42%   |
| Logitech              | 22        | 1.01%   |
| C-Media Electronics   | 20        | 0.92%   |
| Realtek Semiconductor | 16        | 0.73%   |
| GN Netcom             | 13        | 0.6%    |
| JMTek                 | 11        | 0.5%    |
| ASUSTek Computer      | 8         | 0.37%   |
| Sony                  | 6         | 0.28%   |
| Kingston Technology   | 6         | 0.28%   |
| Hewlett-Packard       | 6         | 0.28%   |
| Apple                 | 6         | 0.28%   |
| Razer USA             | 4         | 0.18%   |
| Plantronics           | 4         | 0.18%   |
| Focusrite-Novation    | 4         | 0.18%   |
| Dell                  | 4         | 0.18%   |
| Creative Technology   | 4         | 0.18%   |
| Microsoft             | 3         | 0.14%   |
| Texas Instruments     | 2         | 0.09%   |
| SteelSeries ApS       | 2         | 0.09%   |
| DSEA A/S              | 2         | 0.09%   |
| Blue Microphones      | 2         | 0.09%   |
| Audio-Technica        | 2         | 0.09%   |
| Zhaoxin               | 1         | 0.05%   |
| Yamaha                | 1         | 0.05%   |
| Trust                 | 1         | 0.05%   |
| Tenx Technology       | 1         | 0.05%   |
| Synaptics             | 1         | 0.05%   |
| Silicon Motion        | 1         | 0.05%   |
| shw                   | 1         | 0.05%   |
| Samsung Electronics   | 1         | 0.05%   |
| Samson Technologies   | 1         | 0.05%   |
| RODE Microphones      | 1         | 0.05%   |
| ROCCAT                | 1         | 0.05%   |
| Plugable              | 1         | 0.05%   |
| OPPO Electronics      | 1         | 0.05%   |
| No brand              | 1         | 0.05%   |
| Native Instruments    | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 340       | 12.78%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 193       | 7.25%   |
| Intel Sunrise Point-LP HD Audio                                            | 190       | 7.14%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 147       | 5.52%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 129       | 4.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 94        | 3.53%   |
| Nvidia Audio device                                                        | 73        | 2.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 69        | 2.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 55        | 2.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 54        | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 54        | 2.03%   |
| Intel Comet Lake PCH-LP cAVS                                               | 53        | 1.99%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 53        | 1.99%   |
| Intel Haswell-ULT HD Audio Controller                                      | 48        | 1.8%    |
| Intel 8 Series HD Audio Controller                                         | 48        | 1.8%    |
| Intel Raptor Lake-P/U/H cAVS                                               | 44        | 1.65%   |
| Intel Broadwell-U Audio Controller                                         | 44        | 1.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 43        | 1.62%   |
| Intel Comet Lake PCH cAVS                                                  | 43        | 1.62%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 41        | 1.54%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 35        | 1.32%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 33        | 1.24%   |
| Nvidia GA106 High Definition Audio Controller                              | 31        | 1.16%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 31        | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 28        | 1.05%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 28        | 1.05%   |
| Intel CM238 HD Audio Controller                                            | 25        | 0.94%   |
| AMD FCH Azalia Controller                                                  | 25        | 0.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 23        | 0.86%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 23        | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 21        | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                              | 19        | 0.71%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 19        | 0.71%   |
| AMD Kabini HDMI/DP Audio                                                   | 18        | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 18        | 0.68%   |
| Realtek Semiconductor USB Audio                                            | 16        | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                              | 16        | 0.6%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 15        | 0.56%   |
| Nvidia TU106 High Definition Audio Controller                              | 14        | 0.53%   |
| Nvidia GK107 HDMI Audio Controller                                         | 14        | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 254       | 32.11%  |
| SK hynix            | 165       | 20.86%  |
| Micron Technology   | 124       | 15.68%  |
| Kingston            | 56        | 7.08%   |
| Crucial             | 47        | 5.94%   |
| Unknown             | 25        | 3.16%   |
| Unknown             | 18        | 2.28%   |
| Ramaxel Technology  | 16        | 2.02%   |
| A-DATA Technology   | 11        | 1.39%   |
| Elpida              | 8         | 1.01%   |
| Corsair             | 8         | 1.01%   |
| Teikon              | 6         | 0.76%   |
| Unknown (ABCD)      | 5         | 0.63%   |
| Smart               | 4         | 0.51%   |
| G.Skill             | 4         | 0.51%   |
| V-GeN               | 3         | 0.38%   |
| Timetec             | 3         | 0.38%   |
| Team                | 3         | 0.38%   |
| Nanya Technology    | 3         | 0.38%   |
| 4ea5                | 3         | 0.38%   |
| Patriot             | 2         | 0.25%   |
| ff                  | 2         | 0.25%   |
| Unknown (0x0CDC)    | 1         | 0.13%   |
| Unknown (0x0B5E)    | 1         | 0.13%   |
| Transcend           | 1         | 0.13%   |
| Smart Brazil        | 1         | 0.13%   |
| Qumo                | 1         | 0.13%   |
| PUSKILL             | 1         | 0.13%   |
| Neo Forza           | 1         | 0.13%   |
| Lexar               | 1         | 0.13%   |
| Kllisre             | 1         | 0.13%   |
| Hikvision           | 1         | 0.13%   |
| HANA                | 1         | 0.13%   |
| GOODRAM             | 1         | 0.13%   |
| Goldkey             | 1         | 0.13%   |
| Gold Key            | 1         | 0.13%   |
| CSX                 | 1         | 0.13%   |
| ChangXin Memory     | 1         | 0.13%   |
| Avant               | 1         | 0.13%   |
| Apacer              | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 18        | 2.2%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 17        | 2.08%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 1.47%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 11        | 1.35%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.35%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 1.22%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 10        | 1.22%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 10        | 1.22%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 1.1%    |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 8         | 0.98%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.98%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 8         | 0.98%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.86%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 6         | 0.73%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 6         | 0.73%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 6         | 0.73%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.73%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.73%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 6         | 0.73%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 6         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 0.61%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.61%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB Row Of Chips LPDDR5 6400MT/s | 5         | 0.61%   |
| Samsung RAM Module 16GB SODIMM DDR4 3200MT/s                     | 5         | 0.61%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.61%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.61%   |
| Micron RAM Module 2GB Row Of Chips LPDDR5 6400MT/s               | 5         | 0.61%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.61%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.61%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.61%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 4         | 0.49%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.49%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.49%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 4         | 0.49%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 0.49%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.49%   |
| Samsung RAM K3LKCKC0BM-MGCP 4GB Row Of Chips LPDDR5 6400MT/s     | 4         | 0.49%   |
| Kingston RAM KF3200C20S4/16G 16GB SODIMM DDR4 3200MT/s           | 4         | 0.49%   |
| Crucial RAM CT16G48C40S5.M8A1 16GB SODIMM DDR5 4800MT/s          | 4         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 360       | 53.89%  |
| DDR3    | 119       | 17.81%  |
| LPDDR5  | 58        | 8.68%   |
| DDR5    | 50        | 7.49%   |
| LPDDR4  | 40        | 5.99%   |
| LPDDR3  | 33        | 4.94%   |
| DDR2    | 5         | 0.75%   |
| SDRAM   | 2         | 0.3%    |
| Unknown | 1         | 0.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 526       | 77.35%  |
| Row Of Chips | 139       | 20.44%  |
| Unknown      | 10        | 1.47%   |
| Chip         | 3         | 0.44%   |
| DIMM         | 2         | 0.29%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 314       | 43.92%  |
| 4096  | 168       | 23.5%   |
| 16384 | 150       | 20.98%  |
| 2048  | 47        | 6.57%   |
| 32768 | 30        | 4.2%    |
| 1024  | 6         | 0.84%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 217       | 30.74%  |
| 2667    | 117       | 16.57%  |
| 1600    | 83        | 11.76%  |
| 6400    | 54        | 7.65%   |
| 4800    | 41        | 5.81%   |
| 2400    | 38        | 5.38%   |
| 2133    | 35        | 4.96%   |
| 4267    | 19        | 2.69%   |
| 1334    | 18        | 2.55%   |
| 1867    | 17        | 2.41%   |
| 1333    | 11        | 1.56%   |
| 5600    | 10        | 1.42%   |
| 1067    | 9         | 1.27%   |
| 4266    | 7         | 0.99%   |
| 3266    | 6         | 0.85%   |
| 7467    | 3         | 0.42%   |
| 800     | 3         | 0.42%   |
| 667     | 3         | 0.42%   |
| 8400    | 2         | 0.28%   |
| 5500    | 2         | 0.28%   |
| 3733    | 2         | 0.28%   |
| 2048    | 2         | 0.28%   |
| 1066    | 2         | 0.28%   |
| Unknown | 2         | 0.28%   |
| 3600    | 1         | 0.14%   |
| 2933    | 1         | 0.14%   |
| 975     | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Hewlett-Packard               | 5         | 50%     |
| Seiko Epson                   | 2         | 20%     |
| STMicroelectronics            | 1         | 10%     |
| Samsung Info. Systems America | 1         | 10%     |
| Brother Industries            | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 2         | 20%     |
| HP LaserJet P1102                                                     | 2         | 20%     |
| STMicroelectronics USB Printing Support                               | 1         | 10%     |
| Samsung Info. Systems America SAMSUNG SRP-270                         | 1         | 10%     |
| HP LaserJet 1010                                                      | 1         | 10%     |
| HP Ink Tank 310 series                                                | 1         | 10%     |
| HP DeskJet 2600 series                                                | 1         | 10%     |
| Brother DCP-1600                                                      | 1         | 10%     |

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
| Chicony Electronics                    | 291       | 19.01%  |
| IMC Networks                           | 201       | 13.13%  |
| Microdia                               | 126       | 8.23%   |
| Quanta                                 | 119       | 7.77%   |
| Bison Electronics                      | 117       | 7.64%   |
| Realtek Semiconductor                  | 105       | 6.86%   |
| Sunplus Innovation Technology          | 79        | 5.16%   |
| Apple                                  | 65        | 4.25%   |
| Cheng Uei Precision Industry (Foxlink) | 59        | 3.85%   |
| Syntek                                 | 47        | 3.07%   |
| Luxvisions Innotech Limited            | 44        | 2.87%   |
| Sonix Technology                       | 43        | 2.81%   |
| Logitech                               | 33        | 2.16%   |
| Lite-On Technology                     | 29        | 1.89%   |
| Acer                                   | 29        | 1.89%   |
| Suyin                                  | 23        | 1.5%    |
| Silicon Motion                         | 15        | 0.98%   |
| Alcor Micro                            | 11        | 0.72%   |
| SunplusIT                              | 10        | 0.65%   |
| Shinetech                              | 9         | 0.59%   |
| Samsung Electronics                    | 7         | 0.46%   |
| Lenovo                                 | 7         | 0.46%   |
| Shenzhen Kingcome Optoelectronic       | 5         | 0.33%   |
| Ricoh                                  | 5         | 0.33%   |
| Importek                               | 4         | 0.26%   |
| Primax Electronics                     | 3         | 0.2%    |
| Creative Technology                    | 3         | 0.2%    |
| ALi                                    | 3         | 0.2%    |
| Unknown                                | 3         | 0.2%    |
| Unknown (3730304233345731394146)       | 2         | 0.13%   |
| Razer USA                              | 2         | 0.13%   |
| Microsoft                              | 2         | 0.13%   |
| MacroSilicon                           | 2         | 0.13%   |
| icSpring                               | 2         | 0.13%   |
| Foxconn / Hon Hai                      | 2         | 0.13%   |
| 8SSC21D67422V1SR28902JL                | 2         | 0.13%   |
| 8SSC20F27114V1SR0BK1X4S                | 2         | 0.13%   |
| ZOOM                                   | 1         | 0.07%   |
| Z-Star Microelectronics                | 1         | 0.07%   |
| WaveRider Communications               | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 101       | 6.57%   |
| Microdia Integrated_Webcam_HD                        | 79        | 5.14%   |
| IMC Networks Integrated Camera                       | 72        | 4.68%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 65        | 4.23%   |
| Realtek Integrated_Webcam_HD                         | 48        | 3.12%   |
| Bison Integrated Camera                              | 40        | 2.6%    |
| Syntek Integrated Camera                             | 38        | 2.47%   |
| Sunplus Integrated_Webcam_HD                         | 28        | 1.82%   |
| Apple FaceTime HD Camera                             | 25        | 1.63%   |
| Chicony HD Webcam                                    | 23        | 1.5%    |
| Sonix USB2.0 FHD UVC WebCam                          | 22        | 1.43%   |
| Quanta HD User Facing                                | 22        | 1.43%   |
| Sonix USB2.0 HD UVC WebCam                           | 20        | 1.3%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 18        | 1.17%   |
| Quanta HP Wide Vision HD Camera                      | 17        | 1.11%   |
| Lite-On Integrated Camera                            | 17        | 1.11%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 17        | 1.11%   |
| Bison HD Webcam                                      | 17        | 1.11%   |
| Acer Integrated Camera                               | 17        | 1.11%   |
| Quanta HP HD Camera                                  | 15        | 0.98%   |
| Chicony Integrated Camera (1280x720@30)              | 15        | 0.98%   |
| Chicony HP TrueVision HD Camera                      | 14        | 0.91%   |
| Quanta ACER HD User Facing                           | 12        | 0.78%   |
| Chicony HP HD Camera                                 | 12        | 0.78%   |
| Chicony HD User Facing                               | 12        | 0.78%   |
| Microdia Integrated_Webcam_FHD                       | 11        | 0.72%   |
| Luxvisions Innotech Limited Integrated Camera        | 11        | 0.72%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 11        | 0.72%   |
| Bison Integrated RGB Camera                          | 11        | 0.72%   |
| Quanta HD Camera                                     | 10        | 0.65%   |
| IMC Networks ov9734_azurewave_camera                 | 10        | 0.65%   |
| Chicony USB2.0 Camera                                | 10        | 0.65%   |
| Bison SunplusIT Integrated Camera                    | 10        | 0.65%   |
| Bison Lenovo EasyCamera                              | 10        | 0.65%   |
| IMC Networks HD Camera                               | 9         | 0.59%   |
| Chicony HP TrueVision HD                             | 9         | 0.59%   |
| Quanta HP TrueVision HD Camera                       | 8         | 0.52%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 8         | 0.52%   |
| Luxvisions Innotech Limited HP HD Camera             | 8         | 0.52%   |
| Logitech Webcam C270                                 | 8         | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 108       | 30.95%  |
| Shenzhen Goodix Technology         | 83        | 23.78%  |
| Validity Sensors                   | 73        | 20.92%  |
| Elan Microelectronics              | 31        | 8.88%   |
| Realtek USB2.0 Finger Print Bridge | 15        | 4.3%    |
| Upek                               | 13        | 3.72%   |
| AuthenTec                          | 10        | 2.87%   |
| LighTuning Technology              | 9         | 2.58%   |
| Samsung Electronics                | 5         | 1.43%   |
| STMicroelectronics                 | 1         | 0.29%   |
| Focal-systems.Corp                 | 1         | 0.29%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 61        | 17.48%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 10.89%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 23        | 6.59%   |
| Elan ELAN:ARM-M4                                                           | 21        | 6.02%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 4.87%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 15        | 4.3%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 13        | 3.72%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 3.72%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 3.44%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 3.15%   |
| Synaptics UWP WBDI Device                                                  | 10        | 2.87%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 2.87%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 9         | 2.58%   |
| Elan ELAN:Fingerprint                                                      | 9         | 2.58%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 6         | 1.72%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 6         | 1.72%   |
| Synaptics Fingerprint reader [HP G6]                                       | 6         | 1.72%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 1.72%   |
| Validity Sensors VFS491                                                    | 5         | 1.43%   |
| Synaptics WBDI                                                             | 5         | 1.43%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 1.15%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 1.15%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 1.15%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 4         | 1.15%   |
| Synaptics TouchPad                                                         | 3         | 0.86%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 0.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.86%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 0.86%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.57%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.57%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 0.57%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.57%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.57%   |
| AuthenTec AES2810                                                          | 2         | 0.57%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 0.57%   |
| AuthenTec AES1600                                                          | 2         | 0.57%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.29%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.29%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.29%   |
| Synaptics UWP WBDI                                                         | 1         | 0.29%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 75        | 56.39%  |
| Alcor Micro               | 37        | 27.82%  |
| Upek                      | 6         | 4.51%   |
| Lenovo                    | 5         | 3.76%   |
| O2 Micro                  | 3         | 2.26%   |
| Gemalto (was Gemplus)     | 2         | 1.5%    |
| Yubico.com                | 1         | 0.75%   |
| Realtek Semiconductor     | 1         | 0.75%   |
| Bit4id                    | 1         | 0.75%   |
| Aladdin Knowledge Systems | 1         | 0.75%   |
| Advanced Card Systems     | 1         | 0.75%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 37        | 27.82%  |
| Broadcom 58200                                                               | 33        | 24.81%  |
| Broadcom 5880                                                                | 19        | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 9.77%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 10        | 7.52%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 4.51%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 3.76%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 1.5%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.5%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 0.75%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.75%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.75%   |
| Bit4id miniLector EVO                                                        | 1         | 0.75%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.75%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.75%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 953       | 56.06%  |
| 1     | 606       | 35.65%  |
| 2     | 121       | 7.12%   |
| 3     | 15        | 0.88%   |
| 6     | 2         | 0.12%   |
| 8     | 1         | 0.06%   |
| 5     | 1         | 0.06%   |
| 4     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 342       | 38.26%  |
| Graphics card            | 233       | 26.06%  |
| Multimedia controller    | 133       | 14.88%  |
| Net/wireless             | 75        | 8.39%   |
| Chipcard                 | 25        | 2.8%    |
| Camera                   | 24        | 2.68%   |
| Bluetooth                | 18        | 2.01%   |
| Storage                  | 12        | 1.34%   |
| Sound                    | 12        | 1.34%   |
| Card reader              | 10        | 1.12%   |
| Net/ethernet             | 4         | 0.45%   |
| Network                  | 3         | 0.34%   |
| Modem                    | 2         | 0.22%   |
| Communication controller | 1         | 0.11%   |

