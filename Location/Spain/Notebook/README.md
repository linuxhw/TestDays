Linux in Spain - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

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

Total: 4779

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 15 3511            | [27381bdf35](https://linux-hardware.org/?probe=27381bdf35) | Nov 06, 2023 |
| HP            | ProBook 640 G1              | [1cc495d15b](https://linux-hardware.org/?probe=1cc495d15b) | Nov 05, 2023 |
| HP            | Spectre Pro G1              | [78bce56071](https://linux-hardware.org/?probe=78bce56071) | Nov 05, 2023 |
| Toshiba       | TECRA R950                  | [864877692e](https://linux-hardware.org/?probe=864877692e) | Nov 05, 2023 |
| HP            | Pavilion dm4                | [ed4309477f](https://linux-hardware.org/?probe=ed4309477f) | Nov 05, 2023 |
| HP            | Pavilion dv6                | [60ff7a74af](https://linux-hardware.org/?probe=60ff7a74af) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [ae9fcece31](https://linux-hardware.org/?probe=ae9fcece31) | Nov 05, 2023 |
| MSI           | Modern 15 B7M               | [b4a588e60e](https://linux-hardware.org/?probe=b4a588e60e) | Nov 04, 2023 |
| Lenovo        | G580 2189                   | [29a529e02c](https://linux-hardware.org/?probe=29a529e02c) | Nov 03, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [8b855ce4f4](https://linux-hardware.org/?probe=8b855ce4f4) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b724ede64d](https://linux-hardware.org/?probe=b724ede64d) | Nov 02, 2023 |
| MSI           | Prestige 14 A11SCS          | [e114e8ae5b](https://linux-hardware.org/?probe=e114e8ae5b) | Nov 02, 2023 |
| Lenovo        | Yoga Slim 9 14IAP7 82T0     | [11e373f762](https://linux-hardware.org/?probe=11e373f762) | Nov 02, 2023 |
| Lenovo        | ThinkPad X240 20AMS2EC00    | [820620d5c4](https://linux-hardware.org/?probe=820620d5c4) | Nov 01, 2023 |
| Dell          | G3 3579                     | [0b33f63284](https://linux-hardware.org/?probe=0b33f63284) | Nov 01, 2023 |
| Lenovo        | ThinkPad E560 20EVA02SSP    | [165be504bf](https://linux-hardware.org/?probe=165be504bf) | Nov 01, 2023 |
| HP            | ZBook 15u G6                | [b74e35da2b](https://linux-hardware.org/?probe=b74e35da2b) | Nov 01, 2023 |
| Acer          | Aspire E1-572G              | [d347dc93b5](https://linux-hardware.org/?probe=d347dc93b5) | Nov 01, 2023 |
| ASUSTek       | X550LD                      | [2d0fae2241](https://linux-hardware.org/?probe=2d0fae2241) | Nov 01, 2023 |
| ASUSTek       | X555QG                      | [f047c1d264](https://linux-hardware.org/?probe=f047c1d264) | Nov 01, 2023 |
| VANT          | MOOVE3-15                   | [5fc04a6d0a](https://linux-hardware.org/?probe=5fc04a6d0a) | Oct 31, 2023 |
| Toshiba       | Satellite C55-C             | [859d23eed0](https://linux-hardware.org/?probe=859d23eed0) | Oct 31, 2023 |
| VANT          | MOOVE3-15                   | [7e12621e6d](https://linux-hardware.org/?probe=7e12621e6d) | Oct 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [0eae5ed294](https://linux-hardware.org/?probe=0eae5ed294) | Oct 31, 2023 |
| Timi          | RedmiBook Pro 14S           | [780e721e24](https://linux-hardware.org/?probe=780e721e24) | Oct 30, 2023 |
| Unknown       | Unknown                     | [43e6db0023](https://linux-hardware.org/?probe=43e6db0023) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [bb991098d1](https://linux-hardware.org/?probe=bb991098d1) | Oct 30, 2023 |
| MSI           | GF75 Thin 10SC              | [7aa47ebfa1](https://linux-hardware.org/?probe=7aa47ebfa1) | Oct 30, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [794edd04ea](https://linux-hardware.org/?probe=794edd04ea) | Oct 30, 2023 |
| Lenovo        | ZIWB2                       | [9e6bd45db9](https://linux-hardware.org/?probe=9e6bd45db9) | Oct 29, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d443352482](https://linux-hardware.org/?probe=d443352482) | Oct 29, 2023 |
| Apple         | MacBookPro15,4              | [09ee918b60](https://linux-hardware.org/?probe=09ee918b60) | Oct 29, 2023 |
| Allview       | Allbook H                   | [e56046d262](https://linux-hardware.org/?probe=e56046d262) | Oct 29, 2023 |
| Allview       | Allbook H                   | [3f2fc29d49](https://linux-hardware.org/?probe=3f2fc29d49) | Oct 29, 2023 |
| Lenovo        | ThinkPad X270 20HMS1T600    | [97fbe59dd7](https://linux-hardware.org/?probe=97fbe59dd7) | Oct 29, 2023 |
| SLIMBOOK      | TITAN                       | [8697e4de09](https://linux-hardware.org/?probe=8697e4de09) | Oct 29, 2023 |
| HP            | Laptop 15-da0xxx            | [39d06d7acf](https://linux-hardware.org/?probe=39d06d7acf) | Oct 28, 2023 |
| HP            | Notebook                    | [715435e533](https://linux-hardware.org/?probe=715435e533) | Oct 28, 2023 |
| Toshiba       | TECRA R950                  | [afa984b0d3](https://linux-hardware.org/?probe=afa984b0d3) | Oct 28, 2023 |
| Packard Be... | EasyNote MH36               | [6d73774152](https://linux-hardware.org/?probe=6d73774152) | Oct 28, 2023 |
| SLIMBOOK      | PROX14-10                   | [4ffcd3ced8](https://linux-hardware.org/?probe=4ffcd3ced8) | Oct 28, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | [d59d45eb50](https://linux-hardware.org/?probe=d59d45eb50) | Oct 27, 2023 |
| MSI           | Modern 15 A10M              | [79b0d0252f](https://linux-hardware.org/?probe=79b0d0252f) | Oct 27, 2023 |
| Acer          | TravelMate P259-M           | [7c1c04b9b2](https://linux-hardware.org/?probe=7c1c04b9b2) | Oct 26, 2023 |
| Acer          | TravelMate P259-M           | [670cd56ea3](https://linux-hardware.org/?probe=670cd56ea3) | Oct 26, 2023 |
| Lenovo        | ZIWB2                       | [2537a6e7b9](https://linux-hardware.org/?probe=2537a6e7b9) | Oct 26, 2023 |
| Lenovo        | G580 2189                   | [bba412f376](https://linux-hardware.org/?probe=bba412f376) | Oct 26, 2023 |
| Unknown       | Unknown                     | [7d25c7409a](https://linux-hardware.org/?probe=7d25c7409a) | Oct 26, 2023 |
| Apple         | MacBookPro15,4              | [751e98cb04](https://linux-hardware.org/?probe=751e98cb04) | Oct 26, 2023 |
| MSI           | Prestige 15 A10SC           | [796a2f6a53](https://linux-hardware.org/?probe=796a2f6a53) | Oct 25, 2023 |
| ASUSTek       | GL752VW                     | [a11cf1d28d](https://linux-hardware.org/?probe=a11cf1d28d) | Oct 25, 2023 |
| Acer          | Aspire 9300                 | [3094b549c5](https://linux-hardware.org/?probe=3094b549c5) | Oct 25, 2023 |
| HP            | 14                          | [5e8b808f2f](https://linux-hardware.org/?probe=5e8b808f2f) | Oct 24, 2023 |
| TUXEDO        | InfinityBook Pro Gen8 (M... | [3907a62f64](https://linux-hardware.org/?probe=3907a62f64) | Oct 24, 2023 |
| rocky         | ASUS EXPERTBOOK B1402CBA... | [e7dc573b01](https://linux-hardware.org/?probe=e7dc573b01) | Oct 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | [823dcebef0](https://linux-hardware.org/?probe=823dcebef0) | Oct 23, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | [b7e1e895b9](https://linux-hardware.org/?probe=b7e1e895b9) | Oct 23, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | [f4375f7115](https://linux-hardware.org/?probe=f4375f7115) | Oct 23, 2023 |
| Acer          | TravelMate P259-M           | [d6096c6736](https://linux-hardware.org/?probe=d6096c6736) | Oct 23, 2023 |
| ASUSTek       | X551CA                      | [43c37fb1fe](https://linux-hardware.org/?probe=43c37fb1fe) | Oct 22, 2023 |
| ASUSTek       | X551CA                      | [e9a381c722](https://linux-hardware.org/?probe=e9a381c722) | Oct 22, 2023 |
| AZW           | SEi                         | [94602bd41b](https://linux-hardware.org/?probe=94602bd41b) | Oct 22, 2023 |
| Acer          | Aspire A715-76G             | [448723995f](https://linux-hardware.org/?probe=448723995f) | Oct 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [c5027da111](https://linux-hardware.org/?probe=c5027da111) | Oct 22, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [59d8c7186d](https://linux-hardware.org/?probe=59d8c7186d) | Oct 21, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [f2ee678da1](https://linux-hardware.org/?probe=f2ee678da1) | Oct 21, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [37cdbd73b0](https://linux-hardware.org/?probe=37cdbd73b0) | Oct 21, 2023 |
| HP            | TouchSmart tm2              | [a79b82edd3](https://linux-hardware.org/?probe=a79b82edd3) | Oct 21, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [56621ceace](https://linux-hardware.org/?probe=56621ceace) | Oct 20, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [7323684232](https://linux-hardware.org/?probe=7323684232) | Oct 20, 2023 |
| Sony          | VPCSB2L1R                   | [153440d631](https://linux-hardware.org/?probe=153440d631) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [64929e25f7](https://linux-hardware.org/?probe=64929e25f7) | Oct 20, 2023 |
| Chuwi         | MiniBook                    | [baaf33908c](https://linux-hardware.org/?probe=baaf33908c) | Oct 20, 2023 |
| Lenovo        | G500 20236                  | [6e5d214cb8](https://linux-hardware.org/?probe=6e5d214cb8) | Oct 20, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [da8f06a8e0](https://linux-hardware.org/?probe=da8f06a8e0) | Oct 19, 2023 |
| Toshiba       | Satellite P50t-B-118        | [5237c0866e](https://linux-hardware.org/?probe=5237c0866e) | Oct 19, 2023 |
| Dell          | Precision 7760              | [30e33a33c3](https://linux-hardware.org/?probe=30e33a33c3) | Oct 19, 2023 |
| ASUSTek       | X555QG                      | [e2e11a852f](https://linux-hardware.org/?probe=e2e11a852f) | Oct 19, 2023 |
| ASUSTek       | K46CB                       | [58573f017a](https://linux-hardware.org/?probe=58573f017a) | Oct 19, 2023 |
| HP            | TouchSmart tm2              | [f72f6a43b5](https://linux-hardware.org/?probe=f72f6a43b5) | Oct 19, 2023 |
| HP            | Laptop 15s-eq2xxx           | [9c9781a7ee](https://linux-hardware.org/?probe=9c9781a7ee) | Oct 19, 2023 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [a25bc084fc](https://linux-hardware.org/?probe=a25bc084fc) | Oct 19, 2023 |
| MSI           | Modern 15 A5M               | [cb9366b6ae](https://linux-hardware.org/?probe=cb9366b6ae) | Oct 18, 2023 |
| HP            | 250 G3                      | [e4e0140eb3](https://linux-hardware.org/?probe=e4e0140eb3) | Oct 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [b99a873ab7](https://linux-hardware.org/?probe=b99a873ab7) | Oct 18, 2023 |
| ASUSTek       | K46CB                       | [f524007ed7](https://linux-hardware.org/?probe=f524007ed7) | Oct 18, 2023 |
| HUAWEI        | KLVL-WXX9                   | [0ca9b4c2bd](https://linux-hardware.org/?probe=0ca9b4c2bd) | Oct 17, 2023 |
| HP            | Pavilion dv6                | [0846a94456](https://linux-hardware.org/?probe=0846a94456) | Oct 17, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DL... | [060a9c66c5](https://linux-hardware.org/?probe=060a9c66c5) | Oct 17, 2023 |
| Dell          | XPS 13 9310                 | [295c6b08bd](https://linux-hardware.org/?probe=295c6b08bd) | Oct 17, 2023 |
| ASUSTek       | N61Jv                       | [cb8a1ca22a](https://linux-hardware.org/?probe=cb8a1ca22a) | Oct 17, 2023 |
| MSI           | Prestige 14H B12UCX         | [81dac6f109](https://linux-hardware.org/?probe=81dac6f109) | Oct 17, 2023 |
| HP            | ProBook 440 G6              | [5860734f3a](https://linux-hardware.org/?probe=5860734f3a) | Oct 16, 2023 |
| Allview       | Allbook H                   | [456afe3921](https://linux-hardware.org/?probe=456afe3921) | Oct 16, 2023 |
| MSI           | Modern 14 A10RAS            | [571e9b4e91](https://linux-hardware.org/?probe=571e9b4e91) | Oct 15, 2023 |
| ASUSTek       | UX550VD                     | [a58d0c5f1c](https://linux-hardware.org/?probe=a58d0c5f1c) | Oct 15, 2023 |
| ASUSTek       | UX550VD                     | [c29e83963a](https://linux-hardware.org/?probe=c29e83963a) | Oct 15, 2023 |
| Teclast       | F7 Plus                     | [8c4d203e84](https://linux-hardware.org/?probe=8c4d203e84) | Oct 15, 2023 |
| Google        | Dratini                     | [0c74e4ac18](https://linux-hardware.org/?probe=0c74e4ac18) | Oct 15, 2023 |
| Google        | Dratini                     | [bc181ae269](https://linux-hardware.org/?probe=bc181ae269) | Oct 15, 2023 |
| Dell          | XPS 13 9343                 | [97a3c4d92d](https://linux-hardware.org/?probe=97a3c4d92d) | Oct 15, 2023 |
| MSI           | Prestige 14H B12UCX         | [ddc0082c22](https://linux-hardware.org/?probe=ddc0082c22) | Oct 14, 2023 |
| Dell          | Latitude E4200              | [2a5bbc07aa](https://linux-hardware.org/?probe=2a5bbc07aa) | Oct 14, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [11d91a0246](https://linux-hardware.org/?probe=11d91a0246) | Oct 14, 2023 |
| Medion        | E15415                      | [b9a4ecdc97](https://linux-hardware.org/?probe=b9a4ecdc97) | Oct 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [584433cc95](https://linux-hardware.org/?probe=584433cc95) | Oct 14, 2023 |
| MSI           | Prestige 14H B12UCX         | [63a132c897](https://linux-hardware.org/?probe=63a132c897) | Oct 13, 2023 |
| Panasonic     | CF-C1AD06GDE                | [473265139b](https://linux-hardware.org/?probe=473265139b) | Oct 13, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [b53da36041](https://linux-hardware.org/?probe=b53da36041) | Oct 12, 2023 |
| HP            | Unknown                     | [c64a37f28f](https://linux-hardware.org/?probe=c64a37f28f) | Oct 12, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ba690b36a3](https://linux-hardware.org/?probe=ba690b36a3) | Oct 12, 2023 |
| MSI           | PS42 Modern 8MO             | [be9a0659d4](https://linux-hardware.org/?probe=be9a0659d4) | Oct 11, 2023 |
| HP            | EliteBook 840 G5            | [0baddc9010](https://linux-hardware.org/?probe=0baddc9010) | Oct 11, 2023 |
| HP            | 240 G8 Notebook PC          | [0a98dcd952](https://linux-hardware.org/?probe=0a98dcd952) | Oct 11, 2023 |
| Toshiba       | QOSMIO X70-B                | [fc0abd191f](https://linux-hardware.org/?probe=fc0abd191f) | Oct 11, 2023 |
| HP            | Laptop 15-fc0xxx            | [670b2194c0](https://linux-hardware.org/?probe=670b2194c0) | Oct 11, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [046e552e27](https://linux-hardware.org/?probe=046e552e27) | Oct 11, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | [d7d6c74d55](https://linux-hardware.org/?probe=d7d6c74d55) | Oct 11, 2023 |
| Lenovo        | G580 2189                   | [ea46e68be2](https://linux-hardware.org/?probe=ea46e68be2) | Oct 11, 2023 |
| Valve         | Jupiter                     | [2bde49db66](https://linux-hardware.org/?probe=2bde49db66) | Oct 11, 2023 |
| ASUSTek       | S550CM                      | [ad1b08de66](https://linux-hardware.org/?probe=ad1b08de66) | Oct 10, 2023 |
| HP            | Pavilion 11 x360 PC         | [947e4c6b2f](https://linux-hardware.org/?probe=947e4c6b2f) | Oct 10, 2023 |
| HUAWEI        | KLVL-WXXW                   | [3f6528d99d](https://linux-hardware.org/?probe=3f6528d99d) | Oct 10, 2023 |
| Lenovo        | ThinkPad L540 20AUS11P00    | [ec64651cec](https://linux-hardware.org/?probe=ec64651cec) | Oct 10, 2023 |
| Teclast       | F7S                         | [92c51af32a](https://linux-hardware.org/?probe=92c51af32a) | Oct 10, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6d2a6c2a6f](https://linux-hardware.org/?probe=6d2a6c2a6f) | Oct 09, 2023 |
| Apple         | MacBookAir5,1               | [e4f9055fce](https://linux-hardware.org/?probe=e4f9055fce) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [a41b75e081](https://linux-hardware.org/?probe=a41b75e081) | Oct 09, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [ac6149e371](https://linux-hardware.org/?probe=ac6149e371) | Oct 08, 2023 |
| Valve         | Jupiter                     | [86be8c226a](https://linux-hardware.org/?probe=86be8c226a) | Oct 08, 2023 |
| HP            | Notebook                    | [a181ec12af](https://linux-hardware.org/?probe=a181ec12af) | Oct 08, 2023 |
| HP            | Notebook                    | [039a70e9ce](https://linux-hardware.org/?probe=039a70e9ce) | Oct 07, 2023 |
| Dell          | Inspiron 16 Plus 7630       | [51571d43df](https://linux-hardware.org/?probe=51571d43df) | Oct 07, 2023 |
| VANT          | MOOVE14_2023                | [d9379b5405](https://linux-hardware.org/?probe=d9379b5405) | Oct 06, 2023 |
| Dell          | Latitude 7275               | [f1892c721d](https://linux-hardware.org/?probe=f1892c721d) | Oct 06, 2023 |
| Allview       | Allbook H                   | [9c1933c4eb](https://linux-hardware.org/?probe=9c1933c4eb) | Oct 06, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [39b9855097](https://linux-hardware.org/?probe=39b9855097) | Oct 05, 2023 |
| MSI           | GE63 Raider RGB 8RE         | [74bb875f9f](https://linux-hardware.org/?probe=74bb875f9f) | Oct 05, 2023 |
| Lenovo        | G580 2189                   | [bd7f2d9d03](https://linux-hardware.org/?probe=bd7f2d9d03) | Oct 05, 2023 |
| MSI           | Prestige 15 A11SCX          | [9a4bc722e5](https://linux-hardware.org/?probe=9a4bc722e5) | Oct 05, 2023 |
| Lenovo        | B50-80 80LT                 | [74b54d0f3f](https://linux-hardware.org/?probe=74b54d0f3f) | Oct 05, 2023 |
| Acer          | Aspire M3-581G              | [040dc9b84b](https://linux-hardware.org/?probe=040dc9b84b) | Oct 04, 2023 |
| HP            | EliteBook 745 G6            | [77cfc34723](https://linux-hardware.org/?probe=77cfc34723) | Oct 04, 2023 |
| Apple         | MacBookPro14,2              | [49a295d5f0](https://linux-hardware.org/?probe=49a295d5f0) | Oct 04, 2023 |
| HP            | ENVY 15                     | [589ff0a0af](https://linux-hardware.org/?probe=589ff0a0af) | Oct 03, 2023 |
| Acer          | TravelMate P414-51          | [520fe0b494](https://linux-hardware.org/?probe=520fe0b494) | Oct 03, 2023 |
| HP            | EliteBook 840 G5            | [6615883de3](https://linux-hardware.org/?probe=6615883de3) | Oct 03, 2023 |
| Dynabook      | Satellite Pro C50-G         | [36e6d60078](https://linux-hardware.org/?probe=36e6d60078) | Oct 02, 2023 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [7d076d124e](https://linux-hardware.org/?probe=7d076d124e) | Oct 02, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | [29d9d8dd30](https://linux-hardware.org/?probe=29d9d8dd30) | Oct 02, 2023 |
| Shuttle       | DS47D                       | [d4c27bdf9e](https://linux-hardware.org/?probe=d4c27bdf9e) | Oct 02, 2023 |
| MSI           | Vector GP68HX 12VH          | [e582127237](https://linux-hardware.org/?probe=e582127237) | Oct 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [6fb4d2a754](https://linux-hardware.org/?probe=6fb4d2a754) | Oct 01, 2023 |
| HP            | Presario CQ57               | [e83f052dc8](https://linux-hardware.org/?probe=e83f052dc8) | Oct 01, 2023 |
| Lenovo        | G500 20236                  | [96ce4b8060](https://linux-hardware.org/?probe=96ce4b8060) | Oct 01, 2023 |
| Packard Be... | DOT S                       | [5fd6d403d1](https://linux-hardware.org/?probe=5fd6d403d1) | Oct 01, 2023 |
| Acer          | Aspire E1-571               | [2e7aba6432](https://linux-hardware.org/?probe=2e7aba6432) | Oct 01, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [085fbda5a6](https://linux-hardware.org/?probe=085fbda5a6) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | [b3a006adc7](https://linux-hardware.org/?probe=b3a006adc7) | Sep 30, 2023 |
| MSI           | Prestige 15 A10SC           | [6e53cd8a65](https://linux-hardware.org/?probe=6e53cd8a65) | Sep 30, 2023 |
| MSI           | Prestige 14H B12UCX         | [1c1f35d1c8](https://linux-hardware.org/?probe=1c1f35d1c8) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [3421ba07f9](https://linux-hardware.org/?probe=3421ba07f9) | Sep 30, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [480316a0da](https://linux-hardware.org/?probe=480316a0da) | Sep 30, 2023 |
| HP            | 250 G7 Notebook PC          | [2fc3f16671](https://linux-hardware.org/?probe=2fc3f16671) | Sep 30, 2023 |
| Packard Be... | EasyNote TK85               | [0c62f48dda](https://linux-hardware.org/?probe=0c62f48dda) | Sep 30, 2023 |
| Lenovo        | Z50-70 20354                | [eb33abdaae](https://linux-hardware.org/?probe=eb33abdaae) | Sep 29, 2023 |
| HP            | Laptop 15s-fq1xxx           | [08fb652352](https://linux-hardware.org/?probe=08fb652352) | Sep 29, 2023 |
| HP            | Laptop 15-fd0xxx            | [0a548c4390](https://linux-hardware.org/?probe=0a548c4390) | Sep 28, 2023 |
| HP            | Pavilion 11 x360 PC         | [b6316ea4df](https://linux-hardware.org/?probe=b6316ea4df) | Sep 28, 2023 |
| HP            | Pavilion 11 x360 PC         | [f75ab187aa](https://linux-hardware.org/?probe=f75ab187aa) | Sep 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [426e8bd9c0](https://linux-hardware.org/?probe=426e8bd9c0) | Sep 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [3c4c65947a](https://linux-hardware.org/?probe=3c4c65947a) | Sep 28, 2023 |
| Packard Be... | EasyNote TK85               | [79e6dd1302](https://linux-hardware.org/?probe=79e6dd1302) | Sep 27, 2023 |
| Dell          | XPS 9315                    | [6fa1beb451](https://linux-hardware.org/?probe=6fa1beb451) | Sep 26, 2023 |
| LG Electro... | 13U70Q-G.AA75B              | [f38b79055b](https://linux-hardware.org/?probe=f38b79055b) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [dd48e0075b](https://linux-hardware.org/?probe=dd48e0075b) | Sep 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [21c3145a6a](https://linux-hardware.org/?probe=21c3145a6a) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | [f19700e7b0](https://linux-hardware.org/?probe=f19700e7b0) | Sep 26, 2023 |
| MSI           | GF75 Thin 10SC              | [a7610be494](https://linux-hardware.org/?probe=a7610be494) | Sep 26, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [786338b217](https://linux-hardware.org/?probe=786338b217) | Sep 26, 2023 |
| Sony          | VPCSB2L1R                   | [9395b9347e](https://linux-hardware.org/?probe=9395b9347e) | Sep 26, 2023 |
| Acer          | Extensa 5635Z               | [19afe08920](https://linux-hardware.org/?probe=19afe08920) | Sep 25, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1deb55b03b](https://linux-hardware.org/?probe=1deb55b03b) | Sep 25, 2023 |
| Sony          | SVF14A15CXB                 | [cbce21a887](https://linux-hardware.org/?probe=cbce21a887) | Sep 25, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [7d4c2dc8f6](https://linux-hardware.org/?probe=7d4c2dc8f6) | Sep 25, 2023 |
| Lenovo        | G580 2189                   | [7ddc30adc9](https://linux-hardware.org/?probe=7ddc30adc9) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [a579fd2872](https://linux-hardware.org/?probe=a579fd2872) | Sep 23, 2023 |
| Lenovo        | G580 2189                   | [fe1c9060da](https://linux-hardware.org/?probe=fe1c9060da) | Sep 23, 2023 |
| Packard Be... | EasyNote TK85               | [c970ee5a12](https://linux-hardware.org/?probe=c970ee5a12) | Sep 23, 2023 |
| HP            | Pavilion g6                 | [226a590989](https://linux-hardware.org/?probe=226a590989) | Sep 23, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [347b768d57](https://linux-hardware.org/?probe=347b768d57) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [6ae9f9d9f2](https://linux-hardware.org/?probe=6ae9f9d9f2) | Sep 22, 2023 |
| Toshiba       | Satellite Pro R40-D         | [d33d1b7b77](https://linux-hardware.org/?probe=d33d1b7b77) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [7b093ed910](https://linux-hardware.org/?probe=7b093ed910) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [a1911e4e9a](https://linux-hardware.org/?probe=a1911e4e9a) | Sep 22, 2023 |
| ASUSTek       | ZenBook Pro 15 UX550GEX_... | [aee02d5429](https://linux-hardware.org/?probe=aee02d5429) | Sep 22, 2023 |
| Dell          | XPS 9320                    | [1fe2e34799](https://linux-hardware.org/?probe=1fe2e34799) | Sep 22, 2023 |
| Primux Tec... | Primux_1406F_W10            | [c267e8d9a3](https://linux-hardware.org/?probe=c267e8d9a3) | Sep 22, 2023 |
| Dell          | XPS 15 7590                 | [146d33a16d](https://linux-hardware.org/?probe=146d33a16d) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [7c5cc5e0ab](https://linux-hardware.org/?probe=7c5cc5e0ab) | Sep 22, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [74fa7aed8b](https://linux-hardware.org/?probe=74fa7aed8b) | Sep 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | [28c84c64c1](https://linux-hardware.org/?probe=28c84c64c1) | Sep 21, 2023 |
| Acer          | Aspire F5-571               | [21bcc4a506](https://linux-hardware.org/?probe=21bcc4a506) | Sep 21, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [f9430fd075](https://linux-hardware.org/?probe=f9430fd075) | Sep 21, 2023 |
| MSI           | Prestige 14 A10SC           | [6f81167a6c](https://linux-hardware.org/?probe=6f81167a6c) | Sep 20, 2023 |
| Toshiba       | PORTEGE X30-E               | [2225b3687d](https://linux-hardware.org/?probe=2225b3687d) | Sep 20, 2023 |
| MSI           | Prestige 14 A10SC           | [e0ee68b1a7](https://linux-hardware.org/?probe=e0ee68b1a7) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [c34d9b9514](https://linux-hardware.org/?probe=c34d9b9514) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [7ec3567855](https://linux-hardware.org/?probe=7ec3567855) | Sep 20, 2023 |
| ASUSTek       | X556UQ                      | [676dd13401](https://linux-hardware.org/?probe=676dd13401) | Sep 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [911f7b8df2](https://linux-hardware.org/?probe=911f7b8df2) | Sep 19, 2023 |
| Apple         | MacBookAir7,2               | [6edec4d045](https://linux-hardware.org/?probe=6edec4d045) | Sep 19, 2023 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | [b858f753b2](https://linux-hardware.org/?probe=b858f753b2) | Sep 19, 2023 |
| HP            | Laptop 15-fc0xxx            | [bb3c1bf2b9](https://linux-hardware.org/?probe=bb3c1bf2b9) | Sep 18, 2023 |
| HP            | Laptop 15-fc0xxx            | [4e845095f4](https://linux-hardware.org/?probe=4e845095f4) | Sep 18, 2023 |
| HP            | ProBook 4530s               | [251e7cc45b](https://linux-hardware.org/?probe=251e7cc45b) | Sep 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [1e40d8e0b9](https://linux-hardware.org/?probe=1e40d8e0b9) | Sep 18, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [178981670d](https://linux-hardware.org/?probe=178981670d) | Sep 17, 2023 |
| HP            | Pavilion g6                 | [158b6f4df9](https://linux-hardware.org/?probe=158b6f4df9) | Sep 17, 2023 |
| Google        | Droid                       | [e0a0628d0a](https://linux-hardware.org/?probe=e0a0628d0a) | Sep 17, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [d37d40b74c](https://linux-hardware.org/?probe=d37d40b74c) | Sep 16, 2023 |
| Valve         | Jupiter                     | [3bd1c975cc](https://linux-hardware.org/?probe=3bd1c975cc) | Sep 16, 2023 |
| Chuwi         | GemiBook Pro                | [add3c0be93](https://linux-hardware.org/?probe=add3c0be93) | Sep 15, 2023 |
| HP            | Laptop 15-fc0xxx            | [c8ac03221f](https://linux-hardware.org/?probe=c8ac03221f) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [1322cd195f](https://linux-hardware.org/?probe=1322cd195f) | Sep 15, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [b76ae8f9db](https://linux-hardware.org/?probe=b76ae8f9db) | Sep 15, 2023 |
| HP            | EliteBook 840 14 inch G9... | [9390e3d243](https://linux-hardware.org/?probe=9390e3d243) | Sep 15, 2023 |
| HP            | EliteBook 840 14 inch G9... | [9fc334d8b3](https://linux-hardware.org/?probe=9fc334d8b3) | Sep 15, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | [fd2d28b8af](https://linux-hardware.org/?probe=fd2d28b8af) | Sep 14, 2023 |
| Dell          | XPS 15 9560                 | [b0702745f5](https://linux-hardware.org/?probe=b0702745f5) | Sep 14, 2023 |
| Dell          | Inspiron N5110              | [e2454dd5b9](https://linux-hardware.org/?probe=e2454dd5b9) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [a3e1ac295c](https://linux-hardware.org/?probe=a3e1ac295c) | Sep 14, 2023 |
| ASUSTek       | ROG Strix G713IC_G713IC     | [1cf96bfa0e](https://linux-hardware.org/?probe=1cf96bfa0e) | Sep 14, 2023 |
| Toshiba       | PORTEGE Z830                | [6f4c4a4120](https://linux-hardware.org/?probe=6f4c4a4120) | Sep 14, 2023 |
| Chuwi         | GemiBook Pro                | [9b982600ce](https://linux-hardware.org/?probe=9b982600ce) | Sep 14, 2023 |
| HP            | Laptop 15-bw0xx             | [c0bcb5b2c6](https://linux-hardware.org/?probe=c0bcb5b2c6) | Sep 14, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [262209b6a0](https://linux-hardware.org/?probe=262209b6a0) | Sep 13, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [d334b8fcd2](https://linux-hardware.org/?probe=d334b8fcd2) | Sep 13, 2023 |
| Lenovo        | ThinkPad E490 20N8000YUK    | [df9271331c](https://linux-hardware.org/?probe=df9271331c) | Sep 12, 2023 |
| MSI           | Katana GF66 12UC            | [0191ff7bb8](https://linux-hardware.org/?probe=0191ff7bb8) | Sep 12, 2023 |
| Acer          | Aspire A315-21              | [a7fca90eab](https://linux-hardware.org/?probe=a7fca90eab) | Sep 12, 2023 |
| SLIMBOOK      | Essential15L                | [92dbc92137](https://linux-hardware.org/?probe=92dbc92137) | Sep 12, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [84f6190c40](https://linux-hardware.org/?probe=84f6190c40) | Sep 11, 2023 |
| MSI           | GE70 2PE                    | [335798b8c9](https://linux-hardware.org/?probe=335798b8c9) | Sep 11, 2023 |
| MSI           | GE62 7RD                    | [ff590de77d](https://linux-hardware.org/?probe=ff590de77d) | Sep 11, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [24e256ad9e](https://linux-hardware.org/?probe=24e256ad9e) | Sep 11, 2023 |
| HP            | Laptop 15s-fq2xxx           | [366932ee55](https://linux-hardware.org/?probe=366932ee55) | Sep 11, 2023 |
| HP            | 240 G8 Notebook PC          | [6fec1bd640](https://linux-hardware.org/?probe=6fec1bd640) | Sep 11, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [7809da04f1](https://linux-hardware.org/?probe=7809da04f1) | Sep 10, 2023 |
| MSI           | Modern 14 A10M              | [978f30c076](https://linux-hardware.org/?probe=978f30c076) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | [9f3f71e147](https://linux-hardware.org/?probe=9f3f71e147) | Sep 10, 2023 |
| Acer          | Aspire E1-572G              | [f56c6e875b](https://linux-hardware.org/?probe=f56c6e875b) | Sep 10, 2023 |
| Fujitsu       | LIFEBOOK S752               | [de16eeb9ef](https://linux-hardware.org/?probe=de16eeb9ef) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [3865278574](https://linux-hardware.org/?probe=3865278574) | Sep 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | [2e9fbd4683](https://linux-hardware.org/?probe=2e9fbd4683) | Sep 08, 2023 |
| HUAWEI        | KLVL-WXX9                   | [ff8e50a7ea](https://linux-hardware.org/?probe=ff8e50a7ea) | Sep 08, 2023 |
| ASUSTek       | UX430UAR                    | [dbd0ea122b](https://linux-hardware.org/?probe=dbd0ea122b) | Sep 08, 2023 |
| ASUSTek       | UX430UAR                    | [34601ced54](https://linux-hardware.org/?probe=34601ced54) | Sep 08, 2023 |
| HP            | 630                         | [11393e1391](https://linux-hardware.org/?probe=11393e1391) | Sep 08, 2023 |
| Lenovo        | ThinkPad E14 20RA001BUK     | [6bd319be4e](https://linux-hardware.org/?probe=6bd319be4e) | Sep 08, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [b906e23303](https://linux-hardware.org/?probe=b906e23303) | Sep 08, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [7be90edf82](https://linux-hardware.org/?probe=7be90edf82) | Sep 08, 2023 |
| Notebook      | W65_67SR                    | [7169bc1dbb](https://linux-hardware.org/?probe=7169bc1dbb) | Sep 07, 2023 |
| Gigabyte      | Z97X-Gaming 5               | [a3cdc2345d](https://linux-hardware.org/?probe=a3cdc2345d) | Sep 07, 2023 |
| HP            | Pavilion dv6                | [9ffcb827b4](https://linux-hardware.org/?probe=9ffcb827b4) | Sep 07, 2023 |
| MSI           | Alpha 15 A3DDK              | [9a87dfb80b](https://linux-hardware.org/?probe=9a87dfb80b) | Sep 07, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [0ca7d43ae9](https://linux-hardware.org/?probe=0ca7d43ae9) | Sep 07, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [a4fb146fe8](https://linux-hardware.org/?probe=a4fb146fe8) | Sep 06, 2023 |
| Sony          | VGN-AW41MF_H                | [d3a3262a6e](https://linux-hardware.org/?probe=d3a3262a6e) | Sep 06, 2023 |
| Lenovo        | ThinkPad X390 20Q0002UUS    | [aab185ac48](https://linux-hardware.org/?probe=aab185ac48) | Sep 06, 2023 |
| Valve         | Jupiter                     | [8209a15afb](https://linux-hardware.org/?probe=8209a15afb) | Sep 06, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | [cac93ead6f](https://linux-hardware.org/?probe=cac93ead6f) | Sep 05, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [9d86c0f6e5](https://linux-hardware.org/?probe=9d86c0f6e5) | Sep 05, 2023 |
| ASUSTek       | X751LD                      | [ed90b83cc0](https://linux-hardware.org/?probe=ed90b83cc0) | Sep 05, 2023 |
| Dell          | Precision 7670              | [42788bf2c7](https://linux-hardware.org/?probe=42788bf2c7) | Sep 05, 2023 |
| MSI           | Prestige 14H B12UCX         | [75d602c66f](https://linux-hardware.org/?probe=75d602c66f) | Sep 05, 2023 |
| Dell          | Precision 7670              | [41bb07b203](https://linux-hardware.org/?probe=41bb07b203) | Sep 05, 2023 |
| Valve         | Jupiter                     | [8ae585f958](https://linux-hardware.org/?probe=8ae585f958) | Sep 05, 2023 |
| Dell          | Inspiron 3482               | [078746577b](https://linux-hardware.org/?probe=078746577b) | Sep 05, 2023 |
| HUAWEI        | KLVL-WXX9                   | [d3cde5f4c5](https://linux-hardware.org/?probe=d3cde5f4c5) | Sep 04, 2023 |
| Acer          | Aspire E1-571               | [032fca9d1d](https://linux-hardware.org/?probe=032fca9d1d) | Sep 04, 2023 |
| Chuwi         | GemiBook                    | [cfdc48e9f6](https://linux-hardware.org/?probe=cfdc48e9f6) | Sep 04, 2023 |
| SLIMBOOK      | PROX14-AMD                  | [c2da44c04f](https://linux-hardware.org/?probe=c2da44c04f) | Sep 04, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | [8e29b0ae51](https://linux-hardware.org/?probe=8e29b0ae51) | Sep 04, 2023 |
| HUAWEI        | KLVL-WXX9                   | [c3e4035d47](https://linux-hardware.org/?probe=c3e4035d47) | Sep 03, 2023 |
| IP3 Techno... | ARN59P                      | [493a986305](https://linux-hardware.org/?probe=493a986305) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [ba5eecca4c](https://linux-hardware.org/?probe=ba5eecca4c) | Sep 03, 2023 |
| Lenovo        | ThinkPad T15p Gen 3 21DA... | [6f9a36245f](https://linux-hardware.org/?probe=6f9a36245f) | Sep 03, 2023 |
| Toshiba       | Satellite L50-A-1DL         | [d46487843e](https://linux-hardware.org/?probe=d46487843e) | Sep 03, 2023 |
| HP            | Laptop 15-bs0xx             | [9651a05c1d](https://linux-hardware.org/?probe=9651a05c1d) | Sep 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1458b372fd](https://linux-hardware.org/?probe=1458b372fd) | Sep 03, 2023 |
| Toshiba       | Satellite L10W-B-101        | [1865cdf1ad](https://linux-hardware.org/?probe=1865cdf1ad) | Sep 02, 2023 |
| HP            | ZBook 15 G2                 | [d20f8f324d](https://linux-hardware.org/?probe=d20f8f324d) | Sep 02, 2023 |
| HP            | Pavilion dv6                | [9190ad12c2](https://linux-hardware.org/?probe=9190ad12c2) | Sep 02, 2023 |
| Lenovo        | V145-15AST 81MT             | [741ffec692](https://linux-hardware.org/?probe=741ffec692) | Sep 01, 2023 |
| Lenovo        | G70-70 80HW                 | [f8ac18ebd1](https://linux-hardware.org/?probe=f8ac18ebd1) | Sep 01, 2023 |
| Fujitsu       | LIFEBOOK S760               | [b7439f4404](https://linux-hardware.org/?probe=b7439f4404) | Sep 01, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [0a715ba5aa](https://linux-hardware.org/?probe=0a715ba5aa) | Sep 01, 2023 |
| Medion        | E15301                      | [7f6c4eb814](https://linux-hardware.org/?probe=7f6c4eb814) | Aug 31, 2023 |
| Acer          | Extensa 5230                | [e4877c4cd7](https://linux-hardware.org/?probe=e4877c4cd7) | Aug 31, 2023 |
| Acer          | Aspire E1-571               | [62b0ee9c60](https://linux-hardware.org/?probe=62b0ee9c60) | Aug 31, 2023 |
| Acer          | Aspire E1-530               | [39c2df1a0b](https://linux-hardware.org/?probe=39c2df1a0b) | Aug 30, 2023 |
| Lenovo        | ThinkPad X230 2325AJG       | [fa550a5ea1](https://linux-hardware.org/?probe=fa550a5ea1) | Aug 30, 2023 |
| Alurin        | Go Notebook                 | [d07fd99df0](https://linux-hardware.org/?probe=d07fd99df0) | Aug 30, 2023 |
| HP            | Laptop 15s-fq2xxx           | [6d85c1d397](https://linux-hardware.org/?probe=6d85c1d397) | Aug 30, 2023 |
| Dell          | Precision 7680              | [90240d0ffd](https://linux-hardware.org/?probe=90240d0ffd) | Aug 30, 2023 |
| Dell          | Precision 7680              | [065ed91451](https://linux-hardware.org/?probe=065ed91451) | Aug 30, 2023 |
| Dell          | Latitude 5330               | [7e63575d10](https://linux-hardware.org/?probe=7e63575d10) | Aug 29, 2023 |
| Acer          | Aspire E1-571               | [3208c59e9c](https://linux-hardware.org/?probe=3208c59e9c) | Aug 29, 2023 |
| Dell          | Latitude 5530               | [151de667a5](https://linux-hardware.org/?probe=151de667a5) | Aug 28, 2023 |
| MSI           | Katana GF66 12UGS           | [ca352a81f4](https://linux-hardware.org/?probe=ca352a81f4) | Aug 28, 2023 |
| Dell          | XPS 15 7590                 | [9abe07288a](https://linux-hardware.org/?probe=9abe07288a) | Aug 28, 2023 |
| Dell          | XPS 15 9560                 | [8288d35dff](https://linux-hardware.org/?probe=8288d35dff) | Aug 28, 2023 |
| HP            | ProBook 4540s               | [a477892896](https://linux-hardware.org/?probe=a477892896) | Aug 27, 2023 |
| Dell          | Latitude E5470              | [582c495a92](https://linux-hardware.org/?probe=582c495a92) | Aug 27, 2023 |
| Dell          | Latitude E5470              | [63816a7b5f](https://linux-hardware.org/?probe=63816a7b5f) | Aug 27, 2023 |
| Notebook      | NL4x_NL5xLU                 | [22c5b125e0](https://linux-hardware.org/?probe=22c5b125e0) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [d0de544ecd](https://linux-hardware.org/?probe=d0de544ecd) | Aug 25, 2023 |
| HP            | Laptop                      | [94fd1a7af2](https://linux-hardware.org/?probe=94fd1a7af2) | Aug 25, 2023 |
| HP            | Laptop 15s-fq4xxx           | [e2c530b9fd](https://linux-hardware.org/?probe=e2c530b9fd) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | [113a5418ca](https://linux-hardware.org/?probe=113a5418ca) | Aug 25, 2023 |
| Acer          | TravelMate P215-53          | [b2579f594d](https://linux-hardware.org/?probe=b2579f594d) | Aug 25, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [188af952b0](https://linux-hardware.org/?probe=188af952b0) | Aug 24, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [7fdfaacf03](https://linux-hardware.org/?probe=7fdfaacf03) | Aug 24, 2023 |
| Acer          | TravelMate P214-52          | [6d7eeef62a](https://linux-hardware.org/?probe=6d7eeef62a) | Aug 23, 2023 |
| Acer          | TravelMate P214-52          | [0a000435ae](https://linux-hardware.org/?probe=0a000435ae) | Aug 23, 2023 |
| Apple         | MacBookPro8,1               | [06b5fb7c7f](https://linux-hardware.org/?probe=06b5fb7c7f) | Aug 22, 2023 |
| Dynabook      | Satellite Pro C50-E-11F     | [b8955c7cf1](https://linux-hardware.org/?probe=b8955c7cf1) | Aug 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [b66d308d42](https://linux-hardware.org/?probe=b66d308d42) | Aug 21, 2023 |
| Packard Be... | EasyNote TJ66               | [7e5e1655a6](https://linux-hardware.org/?probe=7e5e1655a6) | Aug 20, 2023 |
| MSI           | GF75 Thin 10SC              | [f50df27008](https://linux-hardware.org/?probe=f50df27008) | Aug 20, 2023 |
| Lenovo        | Unknown                     | [fbbadac782](https://linux-hardware.org/?probe=fbbadac782) | Aug 20, 2023 |
| Lenovo        | IdeaPad 110-15AST 80TR      | [60385dd9f0](https://linux-hardware.org/?probe=60385dd9f0) | Aug 20, 2023 |
| Lenovo        | IdeaPad Z500 20202          | [d93165e8a9](https://linux-hardware.org/?probe=d93165e8a9) | Aug 19, 2023 |
| HP            | EliteBook 850 G3            | [a6a7224d63](https://linux-hardware.org/?probe=a6a7224d63) | Aug 17, 2023 |
| Chuwi         | GemiBook Pro                | [6a2e05ff64](https://linux-hardware.org/?probe=6a2e05ff64) | Aug 17, 2023 |
| Valve         | Jupiter                     | [2981eb04ba](https://linux-hardware.org/?probe=2981eb04ba) | Aug 16, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [bf65b5fe16](https://linux-hardware.org/?probe=bf65b5fe16) | Aug 16, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [97ced089bf](https://linux-hardware.org/?probe=97ced089bf) | Aug 15, 2023 |
| Acer          | Aspire A315-59              | [901f34e440](https://linux-hardware.org/?probe=901f34e440) | Aug 15, 2023 |
| Packard Be... | EasyNote TK85               | [214e2092c6](https://linux-hardware.org/?probe=214e2092c6) | Aug 15, 2023 |
| System76      | Galago Pro                  | [54348f9c55](https://linux-hardware.org/?probe=54348f9c55) | Aug 14, 2023 |
| Medion        | E15301                      | [e42771be29](https://linux-hardware.org/?probe=e42771be29) | Aug 14, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | [589af795e9](https://linux-hardware.org/?probe=589af795e9) | Aug 14, 2023 |
| MSI           | GE60 2OC\2OD\2OE            | [f99741ec7f](https://linux-hardware.org/?probe=f99741ec7f) | Aug 14, 2023 |
| Lenovo        | B50-50 80S2                 | [6c897e0c63](https://linux-hardware.org/?probe=6c897e0c63) | Aug 14, 2023 |
| Packard Be... | EasyNote TK85               | [da059008eb](https://linux-hardware.org/?probe=da059008eb) | Aug 14, 2023 |
| Acer          | Aspire 5742                 | [ebc3e37c86](https://linux-hardware.org/?probe=ebc3e37c86) | Aug 13, 2023 |
| Acer          | Extensa 5635Z               | [e1a35ce655](https://linux-hardware.org/?probe=e1a35ce655) | Aug 13, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [1632c89b98](https://linux-hardware.org/?probe=1632c89b98) | Aug 13, 2023 |
| AXDIA Inte... | WINPAD V10                  | [4dc8c20191](https://linux-hardware.org/?probe=4dc8c20191) | Aug 13, 2023 |
| MSI           | Summit E16Flip A13VET       | [c8d4dbcf88](https://linux-hardware.org/?probe=c8d4dbcf88) | Aug 13, 2023 |
| Valve         | Jupiter                     | [441be5ab4d](https://linux-hardware.org/?probe=441be5ab4d) | Aug 13, 2023 |
| Lenovo        | G505s 20255                 | [9e0052d329](https://linux-hardware.org/?probe=9e0052d329) | Aug 12, 2023 |
| Lenovo        | ThinkPad L13 20R3CTO1WW     | [6ac135c81c](https://linux-hardware.org/?probe=6ac135c81c) | Aug 12, 2023 |
| HP            | Laptop 15-db0xxx            | [3d875407fc](https://linux-hardware.org/?probe=3d875407fc) | Aug 12, 2023 |
| Dell          | G7 7588                     | [48faf46c2c](https://linux-hardware.org/?probe=48faf46c2c) | Aug 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [72899a615b](https://linux-hardware.org/?probe=72899a615b) | Aug 12, 2023 |
| Intel Clie... | LAPQC71A                    | [c87bff1d43](https://linux-hardware.org/?probe=c87bff1d43) | Aug 11, 2023 |
| MSI           | Creator Z16 A11UET          | [7883e9a69d](https://linux-hardware.org/?probe=7883e9a69d) | Aug 11, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [c083cb5f2f](https://linux-hardware.org/?probe=c083cb5f2f) | Aug 11, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a708832571](https://linux-hardware.org/?probe=a708832571) | Aug 11, 2023 |
| ASUSTek       | 1005PE                      | [088a155ec9](https://linux-hardware.org/?probe=088a155ec9) | Aug 10, 2023 |
| PC Special... | NH5xAx                      | [891b5ec398](https://linux-hardware.org/?probe=891b5ec398) | Aug 10, 2023 |
| HP            | Victus by Gaming Laptop ... | [8b57037d50](https://linux-hardware.org/?probe=8b57037d50) | Aug 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [afa02e4c02](https://linux-hardware.org/?probe=afa02e4c02) | Aug 09, 2023 |
| Dell          | Latitude 5520               | [478f0a6a07](https://linux-hardware.org/?probe=478f0a6a07) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [a8fc44190a](https://linux-hardware.org/?probe=a8fc44190a) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | [766e35e920](https://linux-hardware.org/?probe=766e35e920) | Aug 09, 2023 |
| Acer          | Ferrari One 200             | [be688aa584](https://linux-hardware.org/?probe=be688aa584) | Aug 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [de86921bce](https://linux-hardware.org/?probe=de86921bce) | Aug 08, 2023 |
| MSI           | Creator Z16 A11UET          | [ea05388cf5](https://linux-hardware.org/?probe=ea05388cf5) | Aug 08, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b73a01acaf](https://linux-hardware.org/?probe=b73a01acaf) | Aug 07, 2023 |
| SGIN          | laptop                      | [d80389ea87](https://linux-hardware.org/?probe=d80389ea87) | Aug 07, 2023 |
| HP            | 255 G3                      | [d4e6fedb82](https://linux-hardware.org/?probe=d4e6fedb82) | Aug 07, 2023 |
| HP            | 255 G3                      | [0861b2330b](https://linux-hardware.org/?probe=0861b2330b) | Aug 07, 2023 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [77840c201a](https://linux-hardware.org/?probe=77840c201a) | Aug 07, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [804851c490](https://linux-hardware.org/?probe=804851c490) | Aug 07, 2023 |
| Acer          | Aspire V5-121               | [4b8b0f132d](https://linux-hardware.org/?probe=4b8b0f132d) | Aug 07, 2023 |
| Notebook      | NS5x_NS7xPU                 | [d71ac9524e](https://linux-hardware.org/?probe=d71ac9524e) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [56c7715a6d](https://linux-hardware.org/?probe=56c7715a6d) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [6a9e7cc3e2](https://linux-hardware.org/?probe=6a9e7cc3e2) | Aug 06, 2023 |
| HP            | Victus by Laptop 16-d1xx... | [74c80ca51b](https://linux-hardware.org/?probe=74c80ca51b) | Aug 06, 2023 |
| ASUSTek       | R2H                         | [a2972dc454](https://linux-hardware.org/?probe=a2972dc454) | Aug 06, 2023 |
| ASUSTek       | R2H                         | [c32b5889aa](https://linux-hardware.org/?probe=c32b5889aa) | Aug 06, 2023 |
| Acer          | Aspire A315-59              | [fc1d6007aa](https://linux-hardware.org/?probe=fc1d6007aa) | Aug 05, 2023 |
| Acer          | Aspire A315-59              | [deff4c99b6](https://linux-hardware.org/?probe=deff4c99b6) | Aug 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [1d6bf926f6](https://linux-hardware.org/?probe=1d6bf926f6) | Aug 05, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | [e815f65a97](https://linux-hardware.org/?probe=e815f65a97) | Aug 05, 2023 |
| Sony          | VGN-NS11S_S                 | [8ad31bd20c](https://linux-hardware.org/?probe=8ad31bd20c) | Aug 05, 2023 |
| Chuwi         | GemiBook Pro                | [87ecdcb4bd](https://linux-hardware.org/?probe=87ecdcb4bd) | Aug 04, 2023 |
| Toshiba       | PORTEGE R700                | [f0df061bb2](https://linux-hardware.org/?probe=f0df061bb2) | Aug 04, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ee147b0313](https://linux-hardware.org/?probe=ee147b0313) | Aug 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7f601fe313](https://linux-hardware.org/?probe=7f601fe313) | Aug 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | [f495796fe8](https://linux-hardware.org/?probe=f495796fe8) | Aug 03, 2023 |
| Acer          | Aspire M3-581G              | [82814fbe1e](https://linux-hardware.org/?probe=82814fbe1e) | Aug 02, 2023 |
| Chuwi         | GemiBook Pro                | [eb2554dce9](https://linux-hardware.org/?probe=eb2554dce9) | Aug 02, 2023 |
| MSI           | Modern 15 A10M              | [bab451a11e](https://linux-hardware.org/?probe=bab451a11e) | Aug 02, 2023 |
| Sony          | VPCSB2L1R                   | [582f50ea25](https://linux-hardware.org/?probe=582f50ea25) | Aug 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [839698eb4c](https://linux-hardware.org/?probe=839698eb4c) | Aug 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [8e7e80c44e](https://linux-hardware.org/?probe=8e7e80c44e) | Aug 01, 2023 |
| HP            | Laptop 15-db0xxx            | [2d7cbca56b](https://linux-hardware.org/?probe=2d7cbca56b) | Aug 01, 2023 |
| Chuwi         | GemiBook Pro                | [be8a59432a](https://linux-hardware.org/?probe=be8a59432a) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [2dcefa3349](https://linux-hardware.org/?probe=2dcefa3349) | Aug 01, 2023 |
| Valve         | Jupiter                     | [6ea9f908cb](https://linux-hardware.org/?probe=6ea9f908cb) | Aug 01, 2023 |
| Acer          | Aspire E5-573G              | [7e3e1a7ee9](https://linux-hardware.org/?probe=7e3e1a7ee9) | Jul 31, 2023 |
| SHENZHEN Y... | A8S PRO                     | [829a4178a5](https://linux-hardware.org/?probe=829a4178a5) | Jul 30, 2023 |
| Panasonic     | CFMX4-1                     | [925f36396d](https://linux-hardware.org/?probe=925f36396d) | Jul 30, 2023 |
| VANT          | MOOVE15_2023                | [6943d341c4](https://linux-hardware.org/?probe=6943d341c4) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [ce140941bc](https://linux-hardware.org/?probe=ce140941bc) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [19850c3ad1](https://linux-hardware.org/?probe=19850c3ad1) | Jul 29, 2023 |
| SHENZHEN Y... | A8S PRO                     | [08a6feda0e](https://linux-hardware.org/?probe=08a6feda0e) | Jul 28, 2023 |
| HP            | Victus by Gaming Laptop ... | [7595472fb4](https://linux-hardware.org/?probe=7595472fb4) | Jul 28, 2023 |
| HP            | g14                         | [39d4ce09a1](https://linux-hardware.org/?probe=39d4ce09a1) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | [61321e569d](https://linux-hardware.org/?probe=61321e569d) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [4bd819d37b](https://linux-hardware.org/?probe=4bd819d37b) | Jul 28, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [0a1ef2aa5b](https://linux-hardware.org/?probe=0a1ef2aa5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d4914d5e5d](https://linux-hardware.org/?probe=d4914d5e5d) | Jul 27, 2023 |
| Samsung       | 700T                        | [a6c83540ad](https://linux-hardware.org/?probe=a6c83540ad) | Jul 27, 2023 |
| Acer          | Extensa 2510                | [b276a715eb](https://linux-hardware.org/?probe=b276a715eb) | Jul 27, 2023 |
| Acer          | Aspire V3-571G              | [88f60930be](https://linux-hardware.org/?probe=88f60930be) | Jul 26, 2023 |
| Samsung       | 700T                        | [881cb15d92](https://linux-hardware.org/?probe=881cb15d92) | Jul 25, 2023 |
| Acer          | Extensa 2530                | [6691e96edf](https://linux-hardware.org/?probe=6691e96edf) | Jul 25, 2023 |
| AXDIA Inte... | WINPAD V10                  | [0e7e712860](https://linux-hardware.org/?probe=0e7e712860) | Jul 24, 2023 |
| Apple         | MacBookAir4,2               | [e220379405](https://linux-hardware.org/?probe=e220379405) | Jul 24, 2023 |
| Medion        | E15301                      | [e20403ff58](https://linux-hardware.org/?probe=e20403ff58) | Jul 22, 2023 |
| Toshiba       | Satellite L50-B             | [5e7da1cf33](https://linux-hardware.org/?probe=5e7da1cf33) | Jul 22, 2023 |
| AMI           | Cherry Trail CR             | [42d75ac45a](https://linux-hardware.org/?probe=42d75ac45a) | Jul 21, 2023 |
| Packard Be... | EasyNote SL65               | [f66a4415f3](https://linux-hardware.org/?probe=f66a4415f3) | Jul 21, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [fe0c696d47](https://linux-hardware.org/?probe=fe0c696d47) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [b541d17031](https://linux-hardware.org/?probe=b541d17031) | Jul 21, 2023 |
| Dell          | XPS 15 7590                 | [714d6a38d3](https://linux-hardware.org/?probe=714d6a38d3) | Jul 20, 2023 |
| Dell          | XPS 15 7590                 | [f7edcc8364](https://linux-hardware.org/?probe=f7edcc8364) | Jul 20, 2023 |
| Lenovo        | Z50-70 20354                | [f92f9065bc](https://linux-hardware.org/?probe=f92f9065bc) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ec673415b4](https://linux-hardware.org/?probe=ec673415b4) | Jul 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [35944db669](https://linux-hardware.org/?probe=35944db669) | Jul 19, 2023 |
| Apple         | MacBookPro16,1              | [dd5d384a71](https://linux-hardware.org/?probe=dd5d384a71) | Jul 18, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [dc76c90236](https://linux-hardware.org/?probe=dc76c90236) | Jul 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1cffa4bad9](https://linux-hardware.org/?probe=1cffa4bad9) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [cdaad6fa25](https://linux-hardware.org/?probe=cdaad6fa25) | Jul 18, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [fdbbd2b641](https://linux-hardware.org/?probe=fdbbd2b641) | Jul 18, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [b0c8aaef19](https://linux-hardware.org/?probe=b0c8aaef19) | Jul 16, 2023 |
| HP            | Laptop 15s-fq1xxx           | [10e24627b0](https://linux-hardware.org/?probe=10e24627b0) | Jul 16, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [5e43c9d869](https://linux-hardware.org/?probe=5e43c9d869) | Jul 15, 2023 |
| HP            | Laptop 15-bw0xx             | [56448b6dd8](https://linux-hardware.org/?probe=56448b6dd8) | Jul 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [bcf8e9f2c3](https://linux-hardware.org/?probe=bcf8e9f2c3) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f1bbc61bb6](https://linux-hardware.org/?probe=f1bbc61bb6) | Jul 14, 2023 |
| Dell          | XPS 15 7590                 | [28b21d099f](https://linux-hardware.org/?probe=28b21d099f) | Jul 14, 2023 |
| Acer          | TravelMate P246-MG          | [62348fa6ed](https://linux-hardware.org/?probe=62348fa6ed) | Jul 13, 2023 |
| Acer          | Aspire 5749                 | [fc6d20a364](https://linux-hardware.org/?probe=fc6d20a364) | Jul 13, 2023 |
| Chuwi         | GemiBook Pro                | [f73994358d](https://linux-hardware.org/?probe=f73994358d) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [d7c5b64bcb](https://linux-hardware.org/?probe=d7c5b64bcb) | Jul 12, 2023 |
| Dell          | XPS 13 9380                 | [e40c69408d](https://linux-hardware.org/?probe=e40c69408d) | Jul 11, 2023 |
| Dell          | Latitude 7275               | [0647894f7f](https://linux-hardware.org/?probe=0647894f7f) | Jul 11, 2023 |
| ASUSTek       | X555LAB                     | [464293fd0e](https://linux-hardware.org/?probe=464293fd0e) | Jul 11, 2023 |
| Clevo         | M550SE/M660SE               | [65697a4412](https://linux-hardware.org/?probe=65697a4412) | Jul 10, 2023 |
| Acer          | Extensa 5635Z               | [4967fbddb9](https://linux-hardware.org/?probe=4967fbddb9) | Jul 10, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [4ee2490bde](https://linux-hardware.org/?probe=4ee2490bde) | Jul 10, 2023 |
| Dell          | Latitude E5420              | [6dba8e523b](https://linux-hardware.org/?probe=6dba8e523b) | Jul 09, 2023 |
| Notebook      | V1x0PNPx                    | [5a37402681](https://linux-hardware.org/?probe=5a37402681) | Jul 09, 2023 |
| Apple         | MacBookPro14,1              | [62bbadc762](https://linux-hardware.org/?probe=62bbadc762) | Jul 08, 2023 |
| Valve         | Jupiter                     | [7fc70add85](https://linux-hardware.org/?probe=7fc70add85) | Jul 08, 2023 |
| Acer          | Nitro AN515-46              | [010208e38d](https://linux-hardware.org/?probe=010208e38d) | Jul 08, 2023 |
| Valve         | Jupiter                     | [fd3d1bc540](https://linux-hardware.org/?probe=fd3d1bc540) | Jul 08, 2023 |
| Apple         | MacBookPro12,1              | [8877b51b89](https://linux-hardware.org/?probe=8877b51b89) | Jul 08, 2023 |
| Lenovo        | G580 2189                   | [a783ca495d](https://linux-hardware.org/?probe=a783ca495d) | Jul 06, 2023 |
| Acer          | Aspire 5749                 | [c4bea06a7d](https://linux-hardware.org/?probe=c4bea06a7d) | Jul 06, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [f603fed65f](https://linux-hardware.org/?probe=f603fed65f) | Jul 05, 2023 |
| Apple         | MacBookPro8,1               | [d25474786c](https://linux-hardware.org/?probe=d25474786c) | Jul 05, 2023 |
| Acer          | TravelMate P246-MG          | [e1e4548a49](https://linux-hardware.org/?probe=e1e4548a49) | Jul 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [8121ccc8a9](https://linux-hardware.org/?probe=8121ccc8a9) | Jul 05, 2023 |
| HUAWEI        | BOD-WXX9                    | [656b411052](https://linux-hardware.org/?probe=656b411052) | Jul 05, 2023 |
| Medion        | X782X                       | [7369e18cc2](https://linux-hardware.org/?probe=7369e18cc2) | Jul 05, 2023 |
| HP            | Pavilion dv5                | [8064b5c083](https://linux-hardware.org/?probe=8064b5c083) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [54a88e79d1](https://linux-hardware.org/?probe=54a88e79d1) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c3098317a7](https://linux-hardware.org/?probe=c3098317a7) | Jul 04, 2023 |
| Lenovo        | G580 2189                   | [4c68104591](https://linux-hardware.org/?probe=4c68104591) | Jul 03, 2023 |
| Dell          | Latitude 5520               | [acb3fdea1b](https://linux-hardware.org/?probe=acb3fdea1b) | Jul 03, 2023 |
| Dell          | Latitude 5520               | [4bbef448c9](https://linux-hardware.org/?probe=4bbef448c9) | Jul 03, 2023 |
| HP            | ENVY m6                     | [748e336af0](https://linux-hardware.org/?probe=748e336af0) | Jul 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [5daabbcd55](https://linux-hardware.org/?probe=5daabbcd55) | Jul 02, 2023 |
| Valve         | Jupiter                     | [7863106765](https://linux-hardware.org/?probe=7863106765) | Jul 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1eb1ecf3a9](https://linux-hardware.org/?probe=1eb1ecf3a9) | Jul 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [f78c4a1930](https://linux-hardware.org/?probe=f78c4a1930) | Jul 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [27c53e1152](https://linux-hardware.org/?probe=27c53e1152) | Jul 01, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [c1051d3ef0](https://linux-hardware.org/?probe=c1051d3ef0) | Jul 01, 2023 |
| Apple         | MacBookAir9,1               | [d5e55f9e7d](https://linux-hardware.org/?probe=d5e55f9e7d) | Jul 01, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [546fe2b3ab](https://linux-hardware.org/?probe=546fe2b3ab) | Jul 01, 2023 |
| Apple         | MacBookAir9,1               | [bd5c030739](https://linux-hardware.org/?probe=bd5c030739) | Jun 30, 2023 |
| Apple         | MacBookAir9,1               | [ce486a5063](https://linux-hardware.org/?probe=ce486a5063) | Jun 30, 2023 |
| MSI           | Modern 14 B5M               | [cb0eb574da](https://linux-hardware.org/?probe=cb0eb574da) | Jun 29, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [06212dc183](https://linux-hardware.org/?probe=06212dc183) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [1bb728e7dd](https://linux-hardware.org/?probe=1bb728e7dd) | Jun 29, 2023 |
| ASUSTek       | X541UAK                     | [83d0d28a2a](https://linux-hardware.org/?probe=83d0d28a2a) | Jun 29, 2023 |
| Acer          | TravelMate P648-G2-M        | [d1ade76136](https://linux-hardware.org/?probe=d1ade76136) | Jun 29, 2023 |
| Chuwi         | GemiBook                    | [90f0de1460](https://linux-hardware.org/?probe=90f0de1460) | Jun 28, 2023 |
| Acer          | Nitro AN515-54              | [b30ff15571](https://linux-hardware.org/?probe=b30ff15571) | Jun 28, 2023 |
| HP            | ENVY m6                     | [715d68bfc0](https://linux-hardware.org/?probe=715d68bfc0) | Jun 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | [5922b4d31f](https://linux-hardware.org/?probe=5922b4d31f) | Jun 27, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [18c2eb78d4](https://linux-hardware.org/?probe=18c2eb78d4) | Jun 26, 2023 |
| MSI           | Prestige 14H B12UCX         | [abf425c8d7](https://linux-hardware.org/?probe=abf425c8d7) | Jun 26, 2023 |
| Acer          | TravelMate 6493             | [490906b996](https://linux-hardware.org/?probe=490906b996) | Jun 25, 2023 |
| Dell          | Inspiron MM061              | [8152698df7](https://linux-hardware.org/?probe=8152698df7) | Jun 25, 2023 |
| Toshiba       | Satellite U400              | [58b2ad81eb](https://linux-hardware.org/?probe=58b2ad81eb) | Jun 25, 2023 |
| Acer          | Aspire M3-581G              | [0c348c2570](https://linux-hardware.org/?probe=0c348c2570) | Jun 25, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [f14b9f6ce5](https://linux-hardware.org/?probe=f14b9f6ce5) | Jun 25, 2023 |
| HUAWEI        | HKD-WXX                     | [433d7b4f7e](https://linux-hardware.org/?probe=433d7b4f7e) | Jun 24, 2023 |
| Toshiba       | Satellite U400              | [aa6254ebd2](https://linux-hardware.org/?probe=aa6254ebd2) | Jun 24, 2023 |
| HP            | Compaq 610                  | [f312ec5ede](https://linux-hardware.org/?probe=f312ec5ede) | Jun 23, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [6c3a0a7fe0](https://linux-hardware.org/?probe=6c3a0a7fe0) | Jun 23, 2023 |
| Dell          | XPS 9320                    | [2dcfa6718b](https://linux-hardware.org/?probe=2dcfa6718b) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [69dfee1765](https://linux-hardware.org/?probe=69dfee1765) | Jun 22, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [014c851c43](https://linux-hardware.org/?probe=014c851c43) | Jun 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [291796e3e4](https://linux-hardware.org/?probe=291796e3e4) | Jun 21, 2023 |
| HP            | ENVY m6                     | [ea4c3aca13](https://linux-hardware.org/?probe=ea4c3aca13) | Jun 20, 2023 |
| win elemen... | MoreFine S500+              | [32b221a438](https://linux-hardware.org/?probe=32b221a438) | Jun 20, 2023 |
| Dell          | Latitude 7430               | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| Samsung       | RF510/RF410/RF710           | [6131e6746c](https://linux-hardware.org/?probe=6131e6746c) | Jun 19, 2023 |
| Toshiba       | TECRA M10                   | [37f232dce0](https://linux-hardware.org/?probe=37f232dce0) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [2b32ca2d11](https://linux-hardware.org/?probe=2b32ca2d11) | Jun 18, 2023 |
| Toshiba       | NB510                       | [a66bda9742](https://linux-hardware.org/?probe=a66bda9742) | Jun 18, 2023 |
| HP            | Pavilion Notebook           | [5d417b3d76](https://linux-hardware.org/?probe=5d417b3d76) | Jun 18, 2023 |
| Samsung       | RV415/RV515/E3415           | [b17c80df83](https://linux-hardware.org/?probe=b17c80df83) | Jun 17, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [9cdeeb06de](https://linux-hardware.org/?probe=9cdeeb06de) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [19e270cab0](https://linux-hardware.org/?probe=19e270cab0) | Jun 16, 2023 |
| Acer          | Aspire E1-571               | [e4b27c6a92](https://linux-hardware.org/?probe=e4b27c6a92) | Jun 16, 2023 |
| MSI           | Modern 14 B5M               | [21bd3b8234](https://linux-hardware.org/?probe=21bd3b8234) | Jun 16, 2023 |
| MSI           | MPG Z490 GAMING PLUS        | [3ea85763dc](https://linux-hardware.org/?probe=3ea85763dc) | Jun 16, 2023 |
| HP            | G62                         | [2e1e964887](https://linux-hardware.org/?probe=2e1e964887) | Jun 16, 2023 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [2c6d49788f](https://linux-hardware.org/?probe=2c6d49788f) | Jun 16, 2023 |
| Valve         | Jupiter                     | [28dc5a83fe](https://linux-hardware.org/?probe=28dc5a83fe) | Jun 16, 2023 |
| Beelink       | Gemini X                    | [f95615a561](https://linux-hardware.org/?probe=f95615a561) | Jun 15, 2023 |
| Beelink       | Gemini X                    | [3f69d07a3e](https://linux-hardware.org/?probe=3f69d07a3e) | Jun 15, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [b9eac1e0b6](https://linux-hardware.org/?probe=b9eac1e0b6) | Jun 15, 2023 |
| HP            | Notebook                    | [dc40bd89f8](https://linux-hardware.org/?probe=dc40bd89f8) | Jun 15, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [f616cb77b5](https://linux-hardware.org/?probe=f616cb77b5) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [542a1217bd](https://linux-hardware.org/?probe=542a1217bd) | Jun 13, 2023 |
| Alurin        | ALU-LPT-N4020-8256-156      | [0b717c2785](https://linux-hardware.org/?probe=0b717c2785) | Jun 13, 2023 |
| HP            | ENVY m6                     | [b3c165b329](https://linux-hardware.org/?probe=b3c165b329) | Jun 12, 2023 |
| MSI           | Stealth 15M B12UE           | [aabb8192ee](https://linux-hardware.org/?probe=aabb8192ee) | Jun 12, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [7b48584062](https://linux-hardware.org/?probe=7b48584062) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [e6079c9659](https://linux-hardware.org/?probe=e6079c9659) | Jun 11, 2023 |
| HUAWEI        | BOD-WXX9                    | [5a7c331645](https://linux-hardware.org/?probe=5a7c331645) | Jun 11, 2023 |
| HUAWEI        | BoDE-WXX9                   | [8bc28cc12c](https://linux-hardware.org/?probe=8bc28cc12c) | Jun 11, 2023 |
| Lenovo        | G580 2189                   | [eac7ae2f7a](https://linux-hardware.org/?probe=eac7ae2f7a) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [0d419f2c9d](https://linux-hardware.org/?probe=0d419f2c9d) | Jun 11, 2023 |
| Valve         | Jupiter                     | [c7e458735d](https://linux-hardware.org/?probe=c7e458735d) | Jun 11, 2023 |
| Valve         | Jupiter                     | [3e31827529](https://linux-hardware.org/?probe=3e31827529) | Jun 11, 2023 |
| Sony          | VGN-FW41J_H                 | [afc5d143fe](https://linux-hardware.org/?probe=afc5d143fe) | Jun 11, 2023 |
| MSI           | Prestige 15 A10SC           | [ceb7680734](https://linux-hardware.org/?probe=ceb7680734) | Jun 11, 2023 |
| Lenovo        | ThinkPad T450 20BU000BIX    | [d82c175e3e](https://linux-hardware.org/?probe=d82c175e3e) | Jun 10, 2023 |
| Beelink       | Gemini X                    | [adcb5e774d](https://linux-hardware.org/?probe=adcb5e774d) | Jun 10, 2023 |
| Packard Be... | EasyNote TE11BZ             | [a8f9a31f17](https://linux-hardware.org/?probe=a8f9a31f17) | Jun 10, 2023 |
| Lenovo        | ThinkPad T61 7660A25        | [e1617105e0](https://linux-hardware.org/?probe=e1617105e0) | Jun 10, 2023 |
| Dell          | Latitude E5500              | [41ad12c465](https://linux-hardware.org/?probe=41ad12c465) | Jun 10, 2023 |
| Apple         | MacBookPro5,5               | [1b3630b25a](https://linux-hardware.org/?probe=1b3630b25a) | Jun 10, 2023 |
| Apple         | MacBookPro11,4              | [6d70667d42](https://linux-hardware.org/?probe=6d70667d42) | Jun 09, 2023 |
| MSI           | GE66 Raider 10UE            | [38a5122d9c](https://linux-hardware.org/?probe=38a5122d9c) | Jun 08, 2023 |
| Micro Comp... | NUCXI7                      | [3b930f4e22](https://linux-hardware.org/?probe=3b930f4e22) | Jun 08, 2023 |
| Beelink       | Gemini X                    | [49aca69972](https://linux-hardware.org/?probe=49aca69972) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | [ff2ebbb0ae](https://linux-hardware.org/?probe=ff2ebbb0ae) | Jun 07, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | [265c19be27](https://linux-hardware.org/?probe=265c19be27) | Jun 07, 2023 |
| MSI           | GT72 2QE                    | [211494a051](https://linux-hardware.org/?probe=211494a051) | Jun 07, 2023 |
| MSI           | Stealth 15M B12UE           | [acae4ee06e](https://linux-hardware.org/?probe=acae4ee06e) | Jun 06, 2023 |
| MSI           | Modern 14 C12M              | [a5d1a0e656](https://linux-hardware.org/?probe=a5d1a0e656) | Jun 04, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [1352a1d7c7](https://linux-hardware.org/?probe=1352a1d7c7) | Jun 04, 2023 |
| Acer          | Aspire E1-572P              | [a90316cac7](https://linux-hardware.org/?probe=a90316cac7) | Jun 04, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [04fdc3c3b8](https://linux-hardware.org/?probe=04fdc3c3b8) | Jun 03, 2023 |
| Valve         | Jupiter                     | [8c33873318](https://linux-hardware.org/?probe=8c33873318) | Jun 03, 2023 |
| MSI           | Prestige 16 A12UD           | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| Notebook      | NL40_50CU                   | [47b838db36](https://linux-hardware.org/?probe=47b838db36) | Jun 02, 2023 |
| Notebook      | N141CU                      | [4af09bd0c3](https://linux-hardware.org/?probe=4af09bd0c3) | Jun 02, 2023 |
| Valve         | Jupiter                     | [762287e555](https://linux-hardware.org/?probe=762287e555) | Jun 02, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [c9e1edde25](https://linux-hardware.org/?probe=c9e1edde25) | Jun 02, 2023 |
| ASUSTek       | K70IJ                       | [5b877dfec5](https://linux-hardware.org/?probe=5b877dfec5) | Jun 02, 2023 |
| Lenovo        | ThinkPad T530 2392AHG       | [05c41c8464](https://linux-hardware.org/?probe=05c41c8464) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| Lenovo        | G580 2189                   | [3138d92b76](https://linux-hardware.org/?probe=3138d92b76) | Jun 01, 2023 |
| MSI           | Modern 14 B4MW              | [2c4acbbad3](https://linux-hardware.org/?probe=2c4acbbad3) | May 31, 2023 |
| Acer          | Nitro AN515-54              | [7c031081c5](https://linux-hardware.org/?probe=7c031081c5) | May 31, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [5e96e1c54e](https://linux-hardware.org/?probe=5e96e1c54e) | May 31, 2023 |
| Chuwi         | HeroBook Air                | [80afc31c99](https://linux-hardware.org/?probe=80afc31c99) | May 30, 2023 |
| Lenovo        | Legion 5 15IMH05 82AU       | [2ac99b8909](https://linux-hardware.org/?probe=2ac99b8909) | May 30, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [7de5857b40](https://linux-hardware.org/?probe=7de5857b40) | May 29, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [e9830d0123](https://linux-hardware.org/?probe=e9830d0123) | May 29, 2023 |
| Lenovo        | V145-15AST 81MT             | [bf9c082ee0](https://linux-hardware.org/?probe=bf9c082ee0) | May 28, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [dc2b5e538f](https://linux-hardware.org/?probe=dc2b5e538f) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | [9605e313ac](https://linux-hardware.org/?probe=9605e313ac) | May 27, 2023 |
| HP            | Laptop 15-bs0xx             | [0a8ae92c13](https://linux-hardware.org/?probe=0a8ae92c13) | May 27, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [f7f07e78d5](https://linux-hardware.org/?probe=f7f07e78d5) | May 27, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [0ccc456c4e](https://linux-hardware.org/?probe=0ccc456c4e) | May 27, 2023 |
| HP            | 255 G8 Notebook PC          | [9ecbba0aaa](https://linux-hardware.org/?probe=9ecbba0aaa) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [3ce97963e7](https://linux-hardware.org/?probe=3ce97963e7) | May 26, 2023 |
| Toshiba       | TECRA M10                   | [2c574f9677](https://linux-hardware.org/?probe=2c574f9677) | May 26, 2023 |
| ASUSTek       | TUF Gaming FX505GD_FX505... | [89b7c17d00](https://linux-hardware.org/?probe=89b7c17d00) | May 26, 2023 |
| MSI           | Alpha 15 A3DDK              | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Acer          | TravelMate 5720             | [1066a7a5c5](https://linux-hardware.org/?probe=1066a7a5c5) | May 25, 2023 |
| HP            | Laptop 15s-fq4xxx           | [810c2ac411](https://linux-hardware.org/?probe=810c2ac411) | May 24, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [428a152134](https://linux-hardware.org/?probe=428a152134) | May 23, 2023 |
| Notebook      | W54_55SU1,SUW               | [25b79c51e2](https://linux-hardware.org/?probe=25b79c51e2) | May 23, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [77f092da32](https://linux-hardware.org/?probe=77f092da32) | May 23, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [cd94cacffb](https://linux-hardware.org/?probe=cd94cacffb) | May 23, 2023 |
| Acer          | Extensa 5635Z               | [dcff2c30c6](https://linux-hardware.org/?probe=dcff2c30c6) | May 22, 2023 |
| MSI           | Modern 14 B10MW             | [895bca272b](https://linux-hardware.org/?probe=895bca272b) | May 22, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [c720d7e316](https://linux-hardware.org/?probe=c720d7e316) | May 22, 2023 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | [21f52b0bc9](https://linux-hardware.org/?probe=21f52b0bc9) | May 22, 2023 |
| MSI           | Stealth 15M B12UE           | [4051f4b27d](https://linux-hardware.org/?probe=4051f4b27d) | May 22, 2023 |
| Dell          | Inspiron 5770               | [4c16a00ef6](https://linux-hardware.org/?probe=4c16a00ef6) | May 22, 2023 |
| Acer          | Aspire E5-575G              | [d27d5d547e](https://linux-hardware.org/?probe=d27d5d547e) | May 21, 2023 |
| Lenovo        | ThinkPad Helix 36986DG      | [a6b4b230da](https://linux-hardware.org/?probe=a6b4b230da) | May 21, 2023 |
| Lenovo        | G580 2189                   | [8e7dbefb51](https://linux-hardware.org/?probe=8e7dbefb51) | May 21, 2023 |
| Apple         | MacBookPro8,1               | [43c5b0db78](https://linux-hardware.org/?probe=43c5b0db78) | May 20, 2023 |
| Apple         | MacBookAir7,2               | [7687732509](https://linux-hardware.org/?probe=7687732509) | May 20, 2023 |
| HP            | 350 G1                      | [7629c78328](https://linux-hardware.org/?probe=7629c78328) | May 20, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [e464ddd1b6](https://linux-hardware.org/?probe=e464ddd1b6) | May 20, 2023 |
| Chuwi         | GemiBook Pro                | [a8553d6ad6](https://linux-hardware.org/?probe=a8553d6ad6) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [c1f679b4d4](https://linux-hardware.org/?probe=c1f679b4d4) | May 20, 2023 |
| HP            | 255 G8 Notebook PC          | [0c163f5c69](https://linux-hardware.org/?probe=0c163f5c69) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [7f2ca00e36](https://linux-hardware.org/?probe=7f2ca00e36) | May 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [161776168b](https://linux-hardware.org/?probe=161776168b) | May 18, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [d4fc64a451](https://linux-hardware.org/?probe=d4fc64a451) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [0c6bb22a24](https://linux-hardware.org/?probe=0c6bb22a24) | May 18, 2023 |
| HP            | Laptop 15-db0xxx            | [e042bb19ba](https://linux-hardware.org/?probe=e042bb19ba) | May 18, 2023 |
| ASUSTek       | TP300LA                     | [e2e6bc0209](https://linux-hardware.org/?probe=e2e6bc0209) | May 17, 2023 |
| MSI           | Stealth 15M B12UE           | [8517139acb](https://linux-hardware.org/?probe=8517139acb) | May 16, 2023 |
| AZW           | GT-R                        | [e156c5b105](https://linux-hardware.org/?probe=e156c5b105) | May 16, 2023 |
| HP            | 630                         | [3527caae6f](https://linux-hardware.org/?probe=3527caae6f) | May 16, 2023 |
| HP            | 630                         | [f34f960671](https://linux-hardware.org/?probe=f34f960671) | May 16, 2023 |
| ASUSTek       | X541UJ                      | [923f447e90](https://linux-hardware.org/?probe=923f447e90) | May 15, 2023 |
| Acer          | TravelMate P215-41-G2       | [84d5e196da](https://linux-hardware.org/?probe=84d5e196da) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a54f1f4e15](https://linux-hardware.org/?probe=a54f1f4e15) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [c01a4de2f3](https://linux-hardware.org/?probe=c01a4de2f3) | May 15, 2023 |
| HP            | Presario CQ61               | [0967999006](https://linux-hardware.org/?probe=0967999006) | May 14, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | [d697ec6804](https://linux-hardware.org/?probe=d697ec6804) | May 14, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | [8d819952c9](https://linux-hardware.org/?probe=8d819952c9) | May 14, 2023 |
| HP            | 630                         | [40e895a75a](https://linux-hardware.org/?probe=40e895a75a) | May 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [dc1c717240](https://linux-hardware.org/?probe=dc1c717240) | May 13, 2023 |
| ASUSTek       | X551CA                      | [df0583682c](https://linux-hardware.org/?probe=df0583682c) | May 13, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | [9dda4f6b83](https://linux-hardware.org/?probe=9dda4f6b83) | May 13, 2023 |
| Valve         | Jupiter                     | [02275a9849](https://linux-hardware.org/?probe=02275a9849) | May 13, 2023 |
| Apple         | MacBookPro11,4              | [576d66cba7](https://linux-hardware.org/?probe=576d66cba7) | May 12, 2023 |
| HP            | Pavilion Sleekbook 15       | [db2c740451](https://linux-hardware.org/?probe=db2c740451) | May 12, 2023 |
| Valve         | Jupiter                     | [4b2b4bf799](https://linux-hardware.org/?probe=4b2b4bf799) | May 12, 2023 |
| Valve         | Jupiter                     | [e89eb08b8d](https://linux-hardware.org/?probe=e89eb08b8d) | May 11, 2023 |
| Acer          | Aspire 5253G                | [c5cae82cf1](https://linux-hardware.org/?probe=c5cae82cf1) | May 11, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [30d9e5ca7d](https://linux-hardware.org/?probe=30d9e5ca7d) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [d3655e5453](https://linux-hardware.org/?probe=d3655e5453) | May 11, 2023 |
| Dell          | XPS 15 9560                 | [62abfc3d83](https://linux-hardware.org/?probe=62abfc3d83) | May 11, 2023 |
| Dell          | XPS 15 9560                 | [4c714fc6ea](https://linux-hardware.org/?probe=4c714fc6ea) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [7d19994aa2](https://linux-hardware.org/?probe=7d19994aa2) | May 11, 2023 |
| Toshiba       | TECRA M10                   | [cf43cf62c7](https://linux-hardware.org/?probe=cf43cf62c7) | May 10, 2023 |
| Toshiba       | TECRA M10                   | [d2be66b23b](https://linux-hardware.org/?probe=d2be66b23b) | May 10, 2023 |
| Samsung       | X420/X520                   | [aec20f5b38](https://linux-hardware.org/?probe=aec20f5b38) | May 10, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [2e58ce6bd7](https://linux-hardware.org/?probe=2e58ce6bd7) | May 10, 2023 |
| HP            | Compaq Mini CQ10-500        | [4b9087625d](https://linux-hardware.org/?probe=4b9087625d) | May 09, 2023 |
| HP            | 630                         | [69a6753dab](https://linux-hardware.org/?probe=69a6753dab) | May 09, 2023 |
| HP            | 630                         | [d729f66fa2](https://linux-hardware.org/?probe=d729f66fa2) | May 09, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [7b102d2ecc](https://linux-hardware.org/?probe=7b102d2ecc) | May 08, 2023 |
| TerraQue      | W65_W67RB                   | [842f203ec5](https://linux-hardware.org/?probe=842f203ec5) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| eMachines     | eME728                      | [031e24359e](https://linux-hardware.org/?probe=031e24359e) | May 06, 2023 |
| HP            | 630                         | [20d6860e43](https://linux-hardware.org/?probe=20d6860e43) | May 05, 2023 |
| HP            | 630                         | [57d5ffbec9](https://linux-hardware.org/?probe=57d5ffbec9) | May 05, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [6069763b68](https://linux-hardware.org/?probe=6069763b68) | May 05, 2023 |
| Acer          | Nitro AN515-55              | [6264cfc1e6](https://linux-hardware.org/?probe=6264cfc1e6) | May 04, 2023 |
| Gigabyte      | G5 KD                       | [15f1eb707f](https://linux-hardware.org/?probe=15f1eb707f) | May 04, 2023 |
| MSI           | Stealth 15M B12UE           | [9e3dbb15ed](https://linux-hardware.org/?probe=9e3dbb15ed) | May 04, 2023 |
| Acer          | Aspire 5732Z                | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
| Notebook      | W54_55SU1,SUW               | [fbcadee14f](https://linux-hardware.org/?probe=fbcadee14f) | May 03, 2023 |
| Notebook      | W54_55SU1,SUW               | [f9071ed10e](https://linux-hardware.org/?probe=f9071ed10e) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [2509256cea](https://linux-hardware.org/?probe=2509256cea) | May 03, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [3e7b117db0](https://linux-hardware.org/?probe=3e7b117db0) | May 03, 2023 |
| Acer          | TravelMate 5720             | [ad56dc6f51](https://linux-hardware.org/?probe=ad56dc6f51) | May 03, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [f2c18c96df](https://linux-hardware.org/?probe=f2c18c96df) | May 02, 2023 |
| Lenovo        | V15-ADA 82C7                | [b11670d60d](https://linux-hardware.org/?probe=b11670d60d) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Toshiba       | Satellite L50-B             | [fb815bb11c](https://linux-hardware.org/?probe=fb815bb11c) | May 02, 2023 |
| Toshiba       | Satellite L755              | [20fdcbe744](https://linux-hardware.org/?probe=20fdcbe744) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [000c0450b9](https://linux-hardware.org/?probe=000c0450b9) | May 02, 2023 |
| HP            | 240 G6 Notebook PC          | [3ca97c367a](https://linux-hardware.org/?probe=3ca97c367a) | May 01, 2023 |
| Acer          | Aspire A315-21              | [f2c5618e4d](https://linux-hardware.org/?probe=f2c5618e4d) | May 01, 2023 |
| Dell          | Inspiron 7548               | [15fe439a9a](https://linux-hardware.org/?probe=15fe439a9a) | Apr 30, 2023 |
| ASUSTek       | X555QG                      | [5263b174b2](https://linux-hardware.org/?probe=5263b174b2) | Apr 30, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [70e92668aa](https://linux-hardware.org/?probe=70e92668aa) | Apr 30, 2023 |
| MSI           | GF63 Thin 9SC               | [f6a250b3e2](https://linux-hardware.org/?probe=f6a250b3e2) | Apr 29, 2023 |
| MSI           | Modern 14 A10M              | [22ad1f6bfb](https://linux-hardware.org/?probe=22ad1f6bfb) | Apr 29, 2023 |
| Chuwi         | HeroBook Air                | [123f6df9f8](https://linux-hardware.org/?probe=123f6df9f8) | Apr 29, 2023 |
| Sony          | VPCZ13M9E                   | [caf336efc3](https://linux-hardware.org/?probe=caf336efc3) | Apr 28, 2023 |
| ASUSTek       | X555QG                      | [b33f41d3c3](https://linux-hardware.org/?probe=b33f41d3c3) | Apr 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [61151daf36](https://linux-hardware.org/?probe=61151daf36) | Apr 28, 2023 |
| Lenovo        | ThinkPad Edge 25453BG       | [2b5c6e2ded](https://linux-hardware.org/?probe=2b5c6e2ded) | Apr 28, 2023 |
| ASUSTek       | S550CM                      | [068365f788](https://linux-hardware.org/?probe=068365f788) | Apr 28, 2023 |
| Toshiba       | TECRA Z40-C                 | [a72fdebd89](https://linux-hardware.org/?probe=a72fdebd89) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | [ca70475f8a](https://linux-hardware.org/?probe=ca70475f8a) | Apr 28, 2023 |
| HP            | OMEN by Laptop 16-b1xxx     | [beca0f768b](https://linux-hardware.org/?probe=beca0f768b) | Apr 27, 2023 |
| Gigabyte      | G5 GD                       | [d09d6fb712](https://linux-hardware.org/?probe=d09d6fb712) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [0e403fcd17](https://linux-hardware.org/?probe=0e403fcd17) | Apr 27, 2023 |
| Valve         | Jupiter                     | [72f64e795a](https://linux-hardware.org/?probe=72f64e795a) | Apr 27, 2023 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [018ade4782](https://linux-hardware.org/?probe=018ade4782) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [de95ac0857](https://linux-hardware.org/?probe=de95ac0857) | Apr 26, 2023 |
| HUAWEI        | KLVL-WXXW                   | [07906a30e3](https://linux-hardware.org/?probe=07906a30e3) | Apr 26, 2023 |
| MSI           | Stealth 15M B12UE           | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [8a88263cea](https://linux-hardware.org/?probe=8a88263cea) | Apr 26, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [2f7f2efd4f](https://linux-hardware.org/?probe=2f7f2efd4f) | Apr 26, 2023 |
| MSI           | Modern 14 A10M              | [dc3595e3cc](https://linux-hardware.org/?probe=dc3595e3cc) | Apr 25, 2023 |
| HP            | Compaq 15                   | [4799b2a649](https://linux-hardware.org/?probe=4799b2a649) | Apr 25, 2023 |
| Toshiba       | Satellite L350D             | [911ac6edf0](https://linux-hardware.org/?probe=911ac6edf0) | Apr 25, 2023 |
| INSYS         | PT1-140C                    | [902536abce](https://linux-hardware.org/?probe=902536abce) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [b1c3492700](https://linux-hardware.org/?probe=b1c3492700) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [db8e950d12](https://linux-hardware.org/?probe=db8e950d12) | Apr 24, 2023 |
| Acer          | Aspire E1-571G              | [0e2671ee2e](https://linux-hardware.org/?probe=0e2671ee2e) | Apr 23, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e682d7b9dd](https://linux-hardware.org/?probe=e682d7b9dd) | Apr 22, 2023 |
| HP            | Notebook                    | [1d975dfc4f](https://linux-hardware.org/?probe=1d975dfc4f) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [694966dbd7](https://linux-hardware.org/?probe=694966dbd7) | Apr 22, 2023 |
| Toshiba       | Satellite L50-C             | [11f0485b1a](https://linux-hardware.org/?probe=11f0485b1a) | Apr 21, 2023 |
| Toshiba       | Satellite L50-C             | [969bbe5df0](https://linux-hardware.org/?probe=969bbe5df0) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | [3caa3d5076](https://linux-hardware.org/?probe=3caa3d5076) | Apr 21, 2023 |
| Dell          | Inspiron MM061              | [aaecae8f5a](https://linux-hardware.org/?probe=aaecae8f5a) | Apr 20, 2023 |
| MSI           | Stealth 15M B12UE           | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| Lenovo        | ThinkPad T420 4180FP9       | [655c151267](https://linux-hardware.org/?probe=655c151267) | Apr 20, 2023 |
| Acer          | TravelMate B115-M           | [178dbe3693](https://linux-hardware.org/?probe=178dbe3693) | Apr 19, 2023 |
| MSI           | Bravo 15 B5DD               | [433c482314](https://linux-hardware.org/?probe=433c482314) | Apr 19, 2023 |
| Acer          | TravelMate B115-M           | [973070ca0e](https://linux-hardware.org/?probe=973070ca0e) | Apr 19, 2023 |
| HP            | ZBook Firefly 16 inch G9... | [194535b314](https://linux-hardware.org/?probe=194535b314) | Apr 19, 2023 |
| Toshiba       | Satellite L500              | [0896195ea4](https://linux-hardware.org/?probe=0896195ea4) | Apr 18, 2023 |
| Toshiba       | Satellite L500              | [7105145a87](https://linux-hardware.org/?probe=7105145a87) | Apr 18, 2023 |
| MSI           | Prestige 15 A12UC           | [0f4c1e1ac3](https://linux-hardware.org/?probe=0f4c1e1ac3) | Apr 18, 2023 |
| HP            | Pavilion Laptop 15-ck0xx    | [e9278fb49b](https://linux-hardware.org/?probe=e9278fb49b) | Apr 18, 2023 |
| MSI           | PS42 Modern 8RC             | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| HP            | Laptop 15s-eq2xxx           | [879e47fc04](https://linux-hardware.org/?probe=879e47fc04) | Apr 17, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [8b6a2af9ce](https://linux-hardware.org/?probe=8b6a2af9ce) | Apr 16, 2023 |
| Medion        | E15415                      | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| HUAWEI        | MRC-WX0                     | [5b446c43f3](https://linux-hardware.org/?probe=5b446c43f3) | Apr 15, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| Dell          | Inspiron 5759               | [f3bbb04052](https://linux-hardware.org/?probe=f3bbb04052) | Apr 15, 2023 |
| Dell          | Precision 5560              | [b6d20ef4bf](https://linux-hardware.org/?probe=b6d20ef4bf) | Apr 14, 2023 |
| Dell          | Precision 5560              | [b76f840bd9](https://linux-hardware.org/?probe=b76f840bd9) | Apr 14, 2023 |
| HUAWEI        | HVY-WXX9                    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| Lenovo        | ThinkPad T410 2537NY6       | [977014ae11](https://linux-hardware.org/?probe=977014ae11) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | [a9b7cf3c18](https://linux-hardware.org/?probe=a9b7cf3c18) | Apr 13, 2023 |
| MiTAC         | Notebook PC                 | [b2259951b5](https://linux-hardware.org/?probe=b2259951b5) | Apr 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [af4ccb91b1](https://linux-hardware.org/?probe=af4ccb91b1) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | [d914c2a179](https://linux-hardware.org/?probe=d914c2a179) | Apr 12, 2023 |
| Gigabyte      | G5 GD                       | [5b861c968e](https://linux-hardware.org/?probe=5b861c968e) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| Valve         | Jupiter                     | [8fdb71aed1](https://linux-hardware.org/?probe=8fdb71aed1) | Apr 12, 2023 |
| Dell          | XPS 15 9520                 | [5b01d0eda1](https://linux-hardware.org/?probe=5b01d0eda1) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [27688332ee](https://linux-hardware.org/?probe=27688332ee) | Apr 11, 2023 |
| ASUSTek       | X550JF                      | [dff4654bd2](https://linux-hardware.org/?probe=dff4654bd2) | Apr 11, 2023 |
| Acer          | Aspire E1-571G              | [45a3503764](https://linux-hardware.org/?probe=45a3503764) | Apr 11, 2023 |
| HP            | Laptop 15-bw0xx             | [0cef536369](https://linux-hardware.org/?probe=0cef536369) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ac983c99b9](https://linux-hardware.org/?probe=ac983c99b9) | Apr 10, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [a2dcc97485](https://linux-hardware.org/?probe=a2dcc97485) | Apr 09, 2023 |
| HP            | Laptop 15s-eq1xxx           | [eab5adc4e6](https://linux-hardware.org/?probe=eab5adc4e6) | Apr 09, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [7033d674d8](https://linux-hardware.org/?probe=7033d674d8) | Apr 09, 2023 |
| HP            | Pavilion dv6                | [10eeff8916](https://linux-hardware.org/?probe=10eeff8916) | Apr 08, 2023 |
| ASUSTek       | X540LA                      | [38299d8248](https://linux-hardware.org/?probe=38299d8248) | Apr 08, 2023 |
| Dell          | Latitude E5550              | [b0e2c2e0d5](https://linux-hardware.org/?probe=b0e2c2e0d5) | Apr 07, 2023 |
| Gigabyte      | G5 GD                       | [d492c2eca8](https://linux-hardware.org/?probe=d492c2eca8) | Apr 06, 2023 |
| Dell          | Latitude E7250              | [e5fe0c7962](https://linux-hardware.org/?probe=e5fe0c7962) | Apr 06, 2023 |
| HP            | Compaq Presario CQ70        | [11cd73fbce](https://linux-hardware.org/?probe=11cd73fbce) | Apr 06, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [62b5ed7cdf](https://linux-hardware.org/?probe=62b5ed7cdf) | Apr 06, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | [705d5f2396](https://linux-hardware.org/?probe=705d5f2396) | Apr 05, 2023 |
| Dell          | Latitude E4200              | [6dae8e5ff4](https://linux-hardware.org/?probe=6dae8e5ff4) | Apr 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [80bd0aed09](https://linux-hardware.org/?probe=80bd0aed09) | Apr 05, 2023 |
| ASUSTek       | X58C                        | [ff580ffa57](https://linux-hardware.org/?probe=ff580ffa57) | Apr 05, 2023 |
| ASUSTek       | X58C                        | [ae9888c407](https://linux-hardware.org/?probe=ae9888c407) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d006e94e8f](https://linux-hardware.org/?probe=d006e94e8f) | Apr 04, 2023 |
| Valve         | Jupiter                     | [70eb6c0ec1](https://linux-hardware.org/?probe=70eb6c0ec1) | Apr 04, 2023 |
| Timi          | RedmiBook 16                | [681c9f1403](https://linux-hardware.org/?probe=681c9f1403) | Apr 03, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [10e0075b35](https://linux-hardware.org/?probe=10e0075b35) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [89d4ef9333](https://linux-hardware.org/?probe=89d4ef9333) | Apr 02, 2023 |
| Thomson       | SPNEOX13-4RD64              | [bf3eb39804](https://linux-hardware.org/?probe=bf3eb39804) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | [f7f0d77f00](https://linux-hardware.org/?probe=f7f0d77f00) | Apr 02, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [92c94ff8a5](https://linux-hardware.org/?probe=92c94ff8a5) | Apr 02, 2023 |
| Google        | Snappy                      | [6ca49159d2](https://linux-hardware.org/?probe=6ca49159d2) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | [41b51a471d](https://linux-hardware.org/?probe=41b51a471d) | Apr 01, 2023 |
| Chuwi         | GemiBook Pro                | [fc4116204b](https://linux-hardware.org/?probe=fc4116204b) | Apr 01, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [6ab0a0226d](https://linux-hardware.org/?probe=6ab0a0226d) | Apr 01, 2023 |
| Intel         | Kabylake Platform           | [2b0fd79264](https://linux-hardware.org/?probe=2b0fd79264) | Mar 31, 2023 |
| Acer          | Aspire E5-571               | [45887eb5f3](https://linux-hardware.org/?probe=45887eb5f3) | Mar 31, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [59b2b4e152](https://linux-hardware.org/?probe=59b2b4e152) | Mar 31, 2023 |
| MSI           | Modern 15 A5M               | [2a00bed043](https://linux-hardware.org/?probe=2a00bed043) | Mar 31, 2023 |
| ASUSTek       | X551MA                      | [5ea823d079](https://linux-hardware.org/?probe=5ea823d079) | Mar 31, 2023 |
| Apple         | MacBookPro9,2               | [8c60cf0ec1](https://linux-hardware.org/?probe=8c60cf0ec1) | Mar 31, 2023 |
| Dell          | G15 5515                    | [7bb6311632](https://linux-hardware.org/?probe=7bb6311632) | Mar 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [faa3d2b7ad](https://linux-hardware.org/?probe=faa3d2b7ad) | Mar 30, 2023 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [e7e49e22ba](https://linux-hardware.org/?probe=e7e49e22ba) | Mar 30, 2023 |
| ASUSTek       | K53SD                       | [81710aaa51](https://linux-hardware.org/?probe=81710aaa51) | Mar 30, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [a9e7ad7ecd](https://linux-hardware.org/?probe=a9e7ad7ecd) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [3836173aad](https://linux-hardware.org/?probe=3836173aad) | Mar 29, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | [cf75eeabd5](https://linux-hardware.org/?probe=cf75eeabd5) | Mar 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [46a8636dfd](https://linux-hardware.org/?probe=46a8636dfd) | Mar 29, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ccb2d60f5c](https://linux-hardware.org/?probe=ccb2d60f5c) | Mar 29, 2023 |
| ASUSTek       | N550JX                      | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| TEKNOSERVI... | NJ5x_NJ7xLU                 | [2a0feae3f9](https://linux-hardware.org/?probe=2a0feae3f9) | Mar 28, 2023 |
| Notebook      | L140CU                      | [98b71e9790](https://linux-hardware.org/?probe=98b71e9790) | Mar 28, 2023 |
| Dell          | Precision 5540              | [f9e20de07f](https://linux-hardware.org/?probe=f9e20de07f) | Mar 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [66a10dc91a](https://linux-hardware.org/?probe=66a10dc91a) | Mar 27, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [ef962f373f](https://linux-hardware.org/?probe=ef962f373f) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | [574bb4272c](https://linux-hardware.org/?probe=574bb4272c) | Mar 27, 2023 |
| Dell          | Precision 3571              | [13d1ce389d](https://linux-hardware.org/?probe=13d1ce389d) | Mar 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [bddc9116d1](https://linux-hardware.org/?probe=bddc9116d1) | Mar 27, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C10... | [6a8962feba](https://linux-hardware.org/?probe=6a8962feba) | Mar 27, 2023 |
| Samsung       | N150P/N210P/N220P           | [70d943698c](https://linux-hardware.org/?probe=70d943698c) | Mar 27, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ca83615d40](https://linux-hardware.org/?probe=ca83615d40) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | [285462b197](https://linux-hardware.org/?probe=285462b197) | Mar 26, 2023 |
| HUAWEI        | KLVD-WXX9                   | [fc40632056](https://linux-hardware.org/?probe=fc40632056) | Mar 26, 2023 |
| Dell          | G15 5515                    | [3af5157823](https://linux-hardware.org/?probe=3af5157823) | Mar 26, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | [68017924d7](https://linux-hardware.org/?probe=68017924d7) | Mar 26, 2023 |
| HUAWEI        | BOD-WXX9                    | [bee83a6b50](https://linux-hardware.org/?probe=bee83a6b50) | Mar 26, 2023 |
| Chuwi         | HeroBook Air                | [836112a53f](https://linux-hardware.org/?probe=836112a53f) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [8a6705ba5a](https://linux-hardware.org/?probe=8a6705ba5a) | Mar 26, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | [d1427e69b3](https://linux-hardware.org/?probe=d1427e69b3) | Mar 26, 2023 |
| Notebook      | NL40_50CU                   | [4870d52d1e](https://linux-hardware.org/?probe=4870d52d1e) | Mar 25, 2023 |
| Gigabyte      | AERO 15 XD                  | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [05b2003fc0](https://linux-hardware.org/?probe=05b2003fc0) | Mar 25, 2023 |
| MSI           | PE62 7RD                    | [de18d40d94](https://linux-hardware.org/?probe=de18d40d94) | Mar 25, 2023 |
| Lenovo        | G580 2189                   | [edba6da5b6](https://linux-hardware.org/?probe=edba6da5b6) | Mar 25, 2023 |
| HP            | 255 G7 Notebook PC          | [2097578b64](https://linux-hardware.org/?probe=2097578b64) | Mar 25, 2023 |
| Dynabook      | PORTEGE X40L-K              | [9f4a50bc98](https://linux-hardware.org/?probe=9f4a50bc98) | Mar 25, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [548c06032b](https://linux-hardware.org/?probe=548c06032b) | Mar 24, 2023 |
| ASUSTek       | K52Jr                       | [a88997ecfd](https://linux-hardware.org/?probe=a88997ecfd) | Mar 24, 2023 |
| Dell          | G15 5515                    | [3510cdb4cf](https://linux-hardware.org/?probe=3510cdb4cf) | Mar 24, 2023 |
| HP            | 2000                        | [9820715e60](https://linux-hardware.org/?probe=9820715e60) | Mar 24, 2023 |
| ASUSTek       | GL752VW                     | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | [4054877ef0](https://linux-hardware.org/?probe=4054877ef0) | Mar 24, 2023 |
| Chuwi         | GemiBook Pro                | [da37222f12](https://linux-hardware.org/?probe=da37222f12) | Mar 24, 2023 |
| HP            | 2000                        | [87ba6d3696](https://linux-hardware.org/?probe=87ba6d3696) | Mar 24, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ca7d9a9342](https://linux-hardware.org/?probe=ca7d9a9342) | Mar 24, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e4a3f70cbf](https://linux-hardware.org/?probe=e4a3f70cbf) | Mar 23, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d55de052b1](https://linux-hardware.org/?probe=d55de052b1) | Mar 23, 2023 |
| Lenovo        | G500 20236                  | [8688a57db6](https://linux-hardware.org/?probe=8688a57db6) | Mar 22, 2023 |
| Packard Be... | EasyNote LJ75               | [1a3b095372](https://linux-hardware.org/?probe=1a3b095372) | Mar 22, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [4ee498d9fc](https://linux-hardware.org/?probe=4ee498d9fc) | Mar 22, 2023 |
| Dell          | G3 3579                     | [b6f8dd5ffe](https://linux-hardware.org/?probe=b6f8dd5ffe) | Mar 22, 2023 |
| Acer          | Aspire ES1-512              | [901b9b1b6b](https://linux-hardware.org/?probe=901b9b1b6b) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [e7344d03c0](https://linux-hardware.org/?probe=e7344d03c0) | Mar 20, 2023 |
| HP            | 250 G4                      | [46e0314fb1](https://linux-hardware.org/?probe=46e0314fb1) | Mar 20, 2023 |
| MSI           | Pulse GL66 12UEK            | [9790d0bb28](https://linux-hardware.org/?probe=9790d0bb28) | Mar 20, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4223bbbf7e](https://linux-hardware.org/?probe=4223bbbf7e) | Mar 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [77b7fd07a4](https://linux-hardware.org/?probe=77b7fd07a4) | Mar 19, 2023 |
| Acer          | Aspire M3-581G              | [1434607f7e](https://linux-hardware.org/?probe=1434607f7e) | Mar 19, 2023 |
| HUAWEI        | NBLK-WAX9X                  | [5c0e12ebd0](https://linux-hardware.org/?probe=5c0e12ebd0) | Mar 19, 2023 |
| Acer          | Aspire E1-532               | [ed3693c1c8](https://linux-hardware.org/?probe=ed3693c1c8) | Mar 18, 2023 |
| Chuwi         | HeroBook Air                | [e9d0a5dd9a](https://linux-hardware.org/?probe=e9d0a5dd9a) | Mar 18, 2023 |
| Chuwi         | GemiBook Pro                | [7bd3a3e64c](https://linux-hardware.org/?probe=7bd3a3e64c) | Mar 18, 2023 |
| HP            | 250 G8 Notebook PC          | [aade64a567](https://linux-hardware.org/?probe=aade64a567) | Mar 18, 2023 |
| Chuwi         | HeroBook                    | [7a70fa6c57](https://linux-hardware.org/?probe=7a70fa6c57) | Mar 17, 2023 |
| MSI           | GF63 Thin 9SC               | [88dcbd2740](https://linux-hardware.org/?probe=88dcbd2740) | Mar 17, 2023 |
| Apple         | MacBook8,1                  | [a3ef4e5a56](https://linux-hardware.org/?probe=a3ef4e5a56) | Mar 16, 2023 |
| Valve         | Jupiter                     | [0a2038deed](https://linux-hardware.org/?probe=0a2038deed) | Mar 16, 2023 |
| HP            | Laptop 15-db0xxx            | [56b19568ce](https://linux-hardware.org/?probe=56b19568ce) | Mar 16, 2023 |
| HP            | Pavilion Notebook           | [db96098c80](https://linux-hardware.org/?probe=db96098c80) | Mar 15, 2023 |
| Razer         | Blade 14 (2022) - RZ09-0... | [428ea81050](https://linux-hardware.org/?probe=428ea81050) | Mar 15, 2023 |
| Acer          | Aspire E5-573G              | [a24986d87d](https://linux-hardware.org/?probe=a24986d87d) | Mar 15, 2023 |
| HP            | Mini 210-1000               | [cccfcdba22](https://linux-hardware.org/?probe=cccfcdba22) | Mar 15, 2023 |
| MSI           | Katana GF66 12UC            | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Intel         | powered classmate PC        | [891664a0ae](https://linux-hardware.org/?probe=891664a0ae) | Mar 14, 2023 |
| Dell          | Inspiron 14 5410            | [54ff309c3d](https://linux-hardware.org/?probe=54ff309c3d) | Mar 14, 2023 |
| MSI           | Stealth GS77 12UHS          | [fe00606a03](https://linux-hardware.org/?probe=fe00606a03) | Mar 14, 2023 |
| Chuwi         | GemiBook Pro                | [f30cf91b1c](https://linux-hardware.org/?probe=f30cf91b1c) | Mar 13, 2023 |
| Valve         | Jupiter                     | [95598d1841](https://linux-hardware.org/?probe=95598d1841) | Mar 13, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [fc75288cce](https://linux-hardware.org/?probe=fc75288cce) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [e5f001172d](https://linux-hardware.org/?probe=e5f001172d) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | [a421f89675](https://linux-hardware.org/?probe=a421f89675) | Mar 12, 2023 |
| Chuwi         | GemiBook Pro                | [4708653fb3](https://linux-hardware.org/?probe=4708653fb3) | Mar 12, 2023 |
| Acer          | TravelMate B113             | [ba6dc5dcb5](https://linux-hardware.org/?probe=ba6dc5dcb5) | Mar 11, 2023 |
| Dynabook      | Satellite Pro C50-E-11H     | [1a37e14422](https://linux-hardware.org/?probe=1a37e14422) | Mar 11, 2023 |
| Toshiba       | Satellite Pro L300          | [7c5e811612](https://linux-hardware.org/?probe=7c5e811612) | Mar 11, 2023 |
| Valve         | Jupiter                     | [07f6e9ed10](https://linux-hardware.org/?probe=07f6e9ed10) | Mar 10, 2023 |
| Dynabook      | Satellite Pro C50-G         | [835785f6a7](https://linux-hardware.org/?probe=835785f6a7) | Mar 10, 2023 |
| MSI           | GL75 Leopard 10SEK          | [9fdc1bd5c4](https://linux-hardware.org/?probe=9fdc1bd5c4) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Dell          | Latitude E5420              | [9b346e0658](https://linux-hardware.org/?probe=9b346e0658) | Mar 10, 2023 |
| Acer          | Aspire 5750G                | [b4af1eb2cb](https://linux-hardware.org/?probe=b4af1eb2cb) | Mar 10, 2023 |
| Acer          | Aspire M3-581G              | [65b41dc560](https://linux-hardware.org/?probe=65b41dc560) | Mar 09, 2023 |
| Dell          | Latitude E6540              | [3bf25841b3](https://linux-hardware.org/?probe=3bf25841b3) | Mar 09, 2023 |
| Chuwi         | GemiBook Pro                | [23a97367b7](https://linux-hardware.org/?probe=23a97367b7) | Mar 09, 2023 |
| Intel         | powered classmate PC        | [c25d03cf3f](https://linux-hardware.org/?probe=c25d03cf3f) | Mar 09, 2023 |
| Intel         | powered classmate PC        | [8c62787a5b](https://linux-hardware.org/?probe=8c62787a5b) | Mar 09, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [fd15fc475a](https://linux-hardware.org/?probe=fd15fc475a) | Mar 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | [0e054a9861](https://linux-hardware.org/?probe=0e054a9861) | Mar 08, 2023 |
| HP            | Pavilion g6                 | [35f93de82d](https://linux-hardware.org/?probe=35f93de82d) | Mar 08, 2023 |
| ASUSTek       | K53SC                       | [bd182b6d80](https://linux-hardware.org/?probe=bd182b6d80) | Mar 08, 2023 |
| Sony          | SVF1521B1EW                 | [5b5a9dbc40](https://linux-hardware.org/?probe=5b5a9dbc40) | Mar 08, 2023 |
| Acer          | Aspire 5740                 | [37c0c0602c](https://linux-hardware.org/?probe=37c0c0602c) | Mar 08, 2023 |
| ASUSTek       | K54HR                       | [a7c688e9be](https://linux-hardware.org/?probe=a7c688e9be) | Mar 08, 2023 |
| Lenovo        | ThinkPad P1 Gen 2 20QUS1... | [798d6e74da](https://linux-hardware.org/?probe=798d6e74da) | Mar 06, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | [cee8496315](https://linux-hardware.org/?probe=cee8496315) | Mar 06, 2023 |
| Notebook      | N2x0WU                      | [4948392f03](https://linux-hardware.org/?probe=4948392f03) | Mar 06, 2023 |
| Fujitsu Si... | STYLISTIC ST6012            | [0d9314f673](https://linux-hardware.org/?probe=0d9314f673) | Mar 06, 2023 |
| Lenovo        | ThinkPad T15p Gen 1 20TN... | [0811163639](https://linux-hardware.org/?probe=0811163639) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [42469e8f5d](https://linux-hardware.org/?probe=42469e8f5d) | Mar 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | [b73251069c](https://linux-hardware.org/?probe=b73251069c) | Mar 05, 2023 |
| Intel         | powered classmate PC        | [bfd724fd2f](https://linux-hardware.org/?probe=bfd724fd2f) | Mar 04, 2023 |
| Acer          | Aspire A315-43              | [c9efc71e60](https://linux-hardware.org/?probe=c9efc71e60) | Mar 04, 2023 |
| Chuwi         | HeroBook Air                | [43248e0ae9](https://linux-hardware.org/?probe=43248e0ae9) | Mar 03, 2023 |
| Lenovo        | ThinkPad E490 20N8002ASP    | [9b91ef4633](https://linux-hardware.org/?probe=9b91ef4633) | Mar 02, 2023 |
| ASUSTek       | T100HAN                     | [5729d41d01](https://linux-hardware.org/?probe=5729d41d01) | Mar 02, 2023 |
| Toshiba       | Satellite A100              | [51e1183b15](https://linux-hardware.org/?probe=51e1183b15) | Mar 02, 2023 |
| Acer          | TravelMate 5720             | [2e0c5ff8f1](https://linux-hardware.org/?probe=2e0c5ff8f1) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [3a2e77122d](https://linux-hardware.org/?probe=3a2e77122d) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [1c09e468d0](https://linux-hardware.org/?probe=1c09e468d0) | Mar 01, 2023 |
| ASUSTek       | T100HAN                     | [a8b1a02128](https://linux-hardware.org/?probe=a8b1a02128) | Mar 01, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASUSTek       | T100HAN                     | [4f835a4f35](https://linux-hardware.org/?probe=4f835a4f35) | Feb 28, 2023 |
| Dell          | G5 5590                     | [75f2235434](https://linux-hardware.org/?probe=75f2235434) | Feb 28, 2023 |
| ASUSTek       | X550JD                      | [6804351029](https://linux-hardware.org/?probe=6804351029) | Feb 28, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [c829e9e0b8](https://linux-hardware.org/?probe=c829e9e0b8) | Feb 27, 2023 |
| Apple         | MacBookPro6,2               | [3696f0b49e](https://linux-hardware.org/?probe=3696f0b49e) | Feb 27, 2023 |
| HP            | 250 G7 Notebook PC          | [9e587033a4](https://linux-hardware.org/?probe=9e587033a4) | Feb 26, 2023 |
| HP            | Notebook                    | [06dba3c8b3](https://linux-hardware.org/?probe=06dba3c8b3) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [02608a8288](https://linux-hardware.org/?probe=02608a8288) | Feb 25, 2023 |
| HP            | EliteBook Folio 9470m       | [8cc1fdf5b4](https://linux-hardware.org/?probe=8cc1fdf5b4) | Feb 24, 2023 |
| HP            | 250 G7 Notebook PC          | [182cdb3772](https://linux-hardware.org/?probe=182cdb3772) | Feb 24, 2023 |
| HP            | Pavilion g6                 | [602cac9f15](https://linux-hardware.org/?probe=602cac9f15) | Feb 24, 2023 |
| Acer          | AOD255                      | [f5f5ed9b36](https://linux-hardware.org/?probe=f5f5ed9b36) | Feb 24, 2023 |
| Acer          | Aspire S3                   | [9d0301c490](https://linux-hardware.org/?probe=9d0301c490) | Feb 24, 2023 |
| Valve         | Jupiter                     | [08585b6c97](https://linux-hardware.org/?probe=08585b6c97) | Feb 24, 2023 |
| Lenovo        | ThinkPad X201 3680U6V       | [abcf384939](https://linux-hardware.org/?probe=abcf384939) | Feb 23, 2023 |
| Acer          | AOD255                      | [b4ccf00506](https://linux-hardware.org/?probe=b4ccf00506) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [c4ef9294ef](https://linux-hardware.org/?probe=c4ef9294ef) | Feb 23, 2023 |
| MSI           | Alpha 15 A3DDK              | [219483f968](https://linux-hardware.org/?probe=219483f968) | Feb 23, 2023 |
| Toshiba       | Satellite C855-1T5          | [8a96579c89](https://linux-hardware.org/?probe=8a96579c89) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [53d46c67f9](https://linux-hardware.org/?probe=53d46c67f9) | Feb 23, 2023 |
| HP            | Compaq 6720s                | [48cbefb8f6](https://linux-hardware.org/?probe=48cbefb8f6) | Feb 23, 2023 |
| HP            | Compaq 6720s                | [0dac92bb9d](https://linux-hardware.org/?probe=0dac92bb9d) | Feb 23, 2023 |
| HP            | Pavilion 15                 | [48439104ea](https://linux-hardware.org/?probe=48439104ea) | Feb 23, 2023 |
| Gigabyte      | G5 KD                       | [65c50530c8](https://linux-hardware.org/?probe=65c50530c8) | Feb 22, 2023 |
| Sony          | SVF1521N6EW                 | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Acer          | Swift SF514-54T             | [ebbff689ba](https://linux-hardware.org/?probe=ebbff689ba) | Feb 22, 2023 |
| Acer          | TravelMate P256-MG          | [4dbdb229c5](https://linux-hardware.org/?probe=4dbdb229c5) | Feb 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [50f5c21eeb](https://linux-hardware.org/?probe=50f5c21eeb) | Feb 21, 2023 |
| HP            | EliteBook 640 14 inch G9... | [1c0772ccd7](https://linux-hardware.org/?probe=1c0772ccd7) | Feb 21, 2023 |
| Toshiba       | PORTEGE Z30-A               | [882e2c977d](https://linux-hardware.org/?probe=882e2c977d) | Feb 20, 2023 |
| Notebook      | W54_55SU1,SUW               | [5a296bed7f](https://linux-hardware.org/?probe=5a296bed7f) | Feb 19, 2023 |
| Dell          | XPS 13 9370                 | [e710561f68](https://linux-hardware.org/?probe=e710561f68) | Feb 19, 2023 |
| Chuwi         | HeroBook Air                | [c669fff700](https://linux-hardware.org/?probe=c669fff700) | Feb 19, 2023 |
| Unknown       | Unknown                     | [e48cf758d0](https://linux-hardware.org/?probe=e48cf758d0) | Feb 19, 2023 |
| Dell          | XPS M1530                   | [c2f2509941](https://linux-hardware.org/?probe=c2f2509941) | Feb 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [84d8598da2](https://linux-hardware.org/?probe=84d8598da2) | Feb 18, 2023 |
| Sony          | VPCZ13M9E                   | [b3db404e91](https://linux-hardware.org/?probe=b3db404e91) | Feb 17, 2023 |
| Chuwi         | GemiBook Pro                | [af76238a5c](https://linux-hardware.org/?probe=af76238a5c) | Feb 17, 2023 |
| Unknown       | Unknown                     | [8cdf723a7d](https://linux-hardware.org/?probe=8cdf723a7d) | Feb 17, 2023 |
| SLIMBOOK      | TITAN                       | [4638729e72](https://linux-hardware.org/?probe=4638729e72) | Feb 17, 2023 |
| HP            | G61                         | [52bb3c7afb](https://linux-hardware.org/?probe=52bb3c7afb) | Feb 17, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [09aefeb3d6](https://linux-hardware.org/?probe=09aefeb3d6) | Feb 17, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [ffd622d65f](https://linux-hardware.org/?probe=ffd622d65f) | Feb 17, 2023 |
| ASUSTek       | GL553VD                     | [97f3fd27fa](https://linux-hardware.org/?probe=97f3fd27fa) | Feb 16, 2023 |
| Acer          | Aspire V3-372               | [bde68b3ed7](https://linux-hardware.org/?probe=bde68b3ed7) | Feb 16, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [abc91903be](https://linux-hardware.org/?probe=abc91903be) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| Lenovo        | ThinkPad T510 43147VG       | [16b032ccc3](https://linux-hardware.org/?probe=16b032ccc3) | Feb 16, 2023 |
| Acer          | Aspire ES1-512              | [a21a70af4c](https://linux-hardware.org/?probe=a21a70af4c) | Feb 15, 2023 |
| Unknown       | Unknown                     | [7fd524ac5b](https://linux-hardware.org/?probe=7fd524ac5b) | Feb 15, 2023 |
| Lenovo        | ThinkPad P50 20EQS64N09     | [72fad631b7](https://linux-hardware.org/?probe=72fad631b7) | Feb 15, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [70885f1dfd](https://linux-hardware.org/?probe=70885f1dfd) | Feb 15, 2023 |
| Acer          | Extensa 5230                | [2716bcf519](https://linux-hardware.org/?probe=2716bcf519) | Feb 15, 2023 |
| Lenovo        | ThinkPad Edge E530 62724... | [fcf87be002](https://linux-hardware.org/?probe=fcf87be002) | Feb 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [a4f13f23ce](https://linux-hardware.org/?probe=a4f13f23ce) | Feb 15, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [9368822d6a](https://linux-hardware.org/?probe=9368822d6a) | Feb 14, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [cbcadcf80a](https://linux-hardware.org/?probe=cbcadcf80a) | Feb 14, 2023 |
| Dell          | Latitude 5480               | [ab1652f0da](https://linux-hardware.org/?probe=ab1652f0da) | Feb 14, 2023 |
| Gigabyte      | RC14UD                      | [cce1ca1ac5](https://linux-hardware.org/?probe=cce1ca1ac5) | Feb 14, 2023 |
| Acer          | Extensa 5220                | [87682be3fd](https://linux-hardware.org/?probe=87682be3fd) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [9b84a7339e](https://linux-hardware.org/?probe=9b84a7339e) | Feb 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | [20428fc0ed](https://linux-hardware.org/?probe=20428fc0ed) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | [3bd522dc2c](https://linux-hardware.org/?probe=3bd522dc2c) | Feb 13, 2023 |
| Lenovo        | V14-ADA 82C6                | [cfa774a092](https://linux-hardware.org/?probe=cfa774a092) | Feb 13, 2023 |
| Google        | Droid                       | [435ab67598](https://linux-hardware.org/?probe=435ab67598) | Feb 12, 2023 |
| Acer          | Extensa 5230                | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [96dfdd671c](https://linux-hardware.org/?probe=96dfdd671c) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| MSI           | Prestige 15 A12UD           | [9688180ef7](https://linux-hardware.org/?probe=9688180ef7) | Feb 11, 2023 |
| Dell          | Latitude 5290 2-in-1        | [cb03f9e72e](https://linux-hardware.org/?probe=cb03f9e72e) | Feb 10, 2023 |
| Dell          | Latitude 5290 2-in-1        | [c56001eede](https://linux-hardware.org/?probe=c56001eede) | Feb 10, 2023 |
| HP            | Pavilion 15                 | [408fd874e7](https://linux-hardware.org/?probe=408fd874e7) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [b3eaee0a71](https://linux-hardware.org/?probe=b3eaee0a71) | Feb 10, 2023 |
| Acer          | Aspire A515-51              | [d68fb933eb](https://linux-hardware.org/?probe=d68fb933eb) | Feb 09, 2023 |
| Lenovo        | ThinkPad P53s 20N6CTO1WW    | [6b74ce317f](https://linux-hardware.org/?probe=6b74ce317f) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| Acer          | Aspire E5-573G              | [8400619736](https://linux-hardware.org/?probe=8400619736) | Feb 09, 2023 |
| Lenovo        | Legion Y520-15IKBN 80WK     | [ec17af9e06](https://linux-hardware.org/?probe=ec17af9e06) | Feb 09, 2023 |
| Unknown       | Unknown                     | [b541173c03](https://linux-hardware.org/?probe=b541173c03) | Feb 09, 2023 |
| Samsung       | R530/R730                   | [f212e58647](https://linux-hardware.org/?probe=f212e58647) | Feb 07, 2023 |
| Samsung       | R530/R730                   | [9ccb976ccd](https://linux-hardware.org/?probe=9ccb976ccd) | Feb 07, 2023 |
| Lenovo        | B50-70 80EU                 | [637336f0d0](https://linux-hardware.org/?probe=637336f0d0) | Feb 07, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 404       | 11.65%  |
| Ubuntu 18.04       | 256       | 7.38%   |
| Ubuntu 22.04       | 219       | 6.32%   |
| Debian 11          | 138       | 3.98%   |
| OpenMandriva 4.2   | 85        | 2.45%   |
| Zorin 16           | 79        | 2.28%   |
| KDE neon 20.04     | 63        | 1.82%   |
| OpenMandriva 4.3   | 62        | 1.79%   |
| Fedora 38          | 51        | 1.47%   |
| Arch Rolling       | 49        | 1.41%   |
| Linux Mint 20.3    | 46        | 1.33%   |
| Arch               | 41        | 1.18%   |
| Pop!_OS 22.04      | 40        | 1.15%   |
| Manjaro            | 40        | 1.15%   |
| Xubuntu 20.04      | 39        | 1.12%   |
| Ubuntu 20.10       | 39        | 1.12%   |
| Linux Mint 21.1    | 39        | 1.12%   |
| Debian 12          | 39        | 1.12%   |
| OpenMandriva 23.01 | 38        | 1.1%    |
| Linux Mint 19.3    | 37        | 1.07%   |
| Debian 10          | 36        | 1.04%   |
| Ubuntu 19.10       | 34        | 0.98%   |
| Ubuntu 21.04       | 32        | 0.92%   |
| Ubuntu 19.04       | 32        | 0.92%   |
| Linux Mint 20.1    | 32        | 0.92%   |
| Kubuntu 20.04      | 32        | 0.92%   |
| Fedora 36          | 32        | 0.92%   |
| Ubuntu 21.10       | 30        | 0.87%   |
| Linux Mint 20      | 30        | 0.87%   |
| Fedora 37          | 30        | 0.87%   |
| Ubuntu 22.10       | 29        | 0.84%   |
| Xubuntu 18.04      | 28        | 0.81%   |
| Zorin 15           | 27        | 0.78%   |
| Linux Mint 21      | 27        | 0.78%   |
| Linux Mint 20.2    | 27        | 0.78%   |
| Ubuntu 23.04       | 25        | 0.72%   |
| OpenMandriva 23.03 | 25        | 0.72%   |
| Fedora 35          | 25        | 0.72%   |
| Fedora 34          | 24        | 0.69%   |
| Fedora 33          | 24        | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 1092      | 33.28%  |
| Linux Mint    | 271       | 8.26%   |
| Debian        | 236       | 7.19%   |
| OpenMandriva  | 234       | 7.13%   |
| Fedora        | 197       | 6%      |
| Zorin         | 109       | 3.32%   |
| Manjaro       | 104       | 3.17%   |
| Endless       | 102       | 3.11%   |
| Pop!_OS       | 93        | 2.83%   |
| Arch          | 89        | 2.71%   |
| KDE neon      | 82        | 2.5%    |
| Xubuntu       | 81        | 2.47%   |
| Kubuntu       | 79        | 2.41%   |
| ROSA          | 57        | 1.74%   |
| Ubuntu MATE   | 34        | 1.04%   |
| SteamOS       | 34        | 1.04%   |
| Elementary    | 33        | 1.01%   |
| Kali          | 32        | 0.98%   |
| ArcoLinux     | 30        | 0.91%   |
| openSUSE      | 28        | 0.85%   |
| Ubuntu Unity  | 23        | 0.7%    |
| Gentoo        | 19        | 0.58%   |
| Lubuntu       | 18        | 0.55%   |
| EndeavourOS   | 16        | 0.49%   |
| BlackPanther  | 16        | 0.49%   |
| Parrot        | 14        | 0.43%   |
| Nobara        | 14        | 0.43%   |
| LMDE          | 14        | 0.43%   |
| MX            | 10        | 0.3%    |
| Clear Linux   | 9         | 0.27%   |
| Ubuntu Budgie | 8         | 0.24%   |
| Sparky        | 5         | 0.15%   |
| Garuda Linux  | 5         | 0.15%   |
| Deepin        | 5         | 0.15%   |
| CentOS        | 5         | 0.15%   |
| Ubuntu Studio | 4         | 0.12%   |
| RHEL          | 4         | 0.12%   |
| BunsenLabs    | 4         | 0.12%   |
| Archcraft     | 4         | 0.12%   |
| Xero          | 3         | 0.09%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 83        | 2.19%   |
| 5.16.7-desktop-1omv4003  | 61        | 1.61%   |
| 5.4.0-42-generic         | 48        | 1.27%   |
| 5.15.0-56-generic        | 36        | 0.95%   |
| 6.1.1-desktop-1omv2290   | 35        | 0.92%   |
| 5.10.0-8-amd64           | 34        | 0.9%    |
| 5.4.0-58-generic         | 33        | 0.87%   |
| 5.15.0-52-generic        | 32        | 0.85%   |
| 5.3.0-28-generic         | 31        | 0.82%   |
| 5.4.0-54-generic         | 27        | 0.71%   |
| 5.4.0-52-generic         | 26        | 0.69%   |
| 5.4.0-26-generic         | 26        | 0.69%   |
| 5.10.0-18-amd64          | 26        | 0.69%   |
| 6.2.6-desktop-1omv2390   | 25        | 0.66%   |
| 5.15.0-58-generic        | 24        | 0.63%   |
| 5.15.0-53-generic        | 22        | 0.58%   |
| 5.11.0-27-generic        | 22        | 0.58%   |
| 5.0.0-37-generic         | 22        | 0.58%   |
| 5.3.0-46-generic         | 21        | 0.55%   |
| 5.3.0-40-generic         | 21        | 0.55%   |
| 5.15.0-48-generic        | 21        | 0.55%   |
| 5.4.0-65-generic         | 20        | 0.53%   |
| 5.4.0-48-generic         | 20        | 0.53%   |
| 5.19.0-35-generic        | 19        | 0.5%    |
| 5.13.0-valve36-1-neptune | 19        | 0.5%    |
| 5.11.0-43-generic        | 19        | 0.5%    |
| 5.11.0-41-generic        | 19        | 0.5%    |
| 5.4.0-72-generic         | 18        | 0.48%   |
| 5.4.0-40-generic         | 18        | 0.48%   |
| 5.0.0-32-generic         | 18        | 0.48%   |
| 5.8.0-44-generic         | 17        | 0.45%   |
| 5.15.0-47-generic        | 17        | 0.45%   |
| 6.4.11-desktop-1omv2390  | 16        | 0.42%   |
| 5.4.0-19-generic         | 16        | 0.42%   |
| 5.3.0-45-generic         | 16        | 0.42%   |
| 5.8.0-14-generic         | 15        | 0.4%    |
| 5.4.0-91-generic         | 15        | 0.4%    |
| 5.4.0-53-generic         | 15        | 0.4%    |
| 5.4.0-29-generic         | 15        | 0.4%    |
| 5.13.0-28-generic        | 15        | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 548       | 15.31%  |
| 5.15.0  | 344       | 9.61%   |
| 4.15.0  | 205       | 5.73%   |
| 5.11.0  | 168       | 4.69%   |
| 5.10.0  | 161       | 4.5%    |
| 5.3.0   | 153       | 4.27%   |
| 5.8.0   | 151       | 4.22%   |
| 5.13.0  | 147       | 4.11%   |
| 5.19.0  | 122       | 3.41%   |
| 5.0.0   | 109       | 3.05%   |
| 5.10.14 | 84        | 2.35%   |
| 6.2.0   | 78        | 2.18%   |
| 4.18.0  | 71        | 1.98%   |
| 5.16.7  | 65        | 1.82%   |
| 6.1.0   | 61        | 1.7%    |
| 4.19.0  | 42        | 1.17%   |
| 6.1.1   | 41        | 1.15%   |
| 6.2.6   | 39        | 1.09%   |
| 6.4.11  | 19        | 0.53%   |
| 5.14.0  | 19        | 0.53%   |
| 6.0.0   | 16        | 0.45%   |
| 4.9.60  | 15        | 0.42%   |
| 6.5.5   | 13        | 0.36%   |
| 6.0.12  | 13        | 0.36%   |
| 5.18.0  | 13        | 0.36%   |
| 4.4.0   | 13        | 0.36%   |
| 4.18.16 | 13        | 0.36%   |
| 6.1.11  | 11        | 0.31%   |
| 6.4.6   | 10        | 0.28%   |
| 5.9.16  | 10        | 0.28%   |
| 5.17.5  | 10        | 0.28%   |
| 6.2.9   | 8         | 0.22%   |
| 6.1.12  | 8         | 0.22%   |
| 5.16.0  | 8         | 0.22%   |
| 6.0.10  | 7         | 0.2%    |
| 5.3.18  | 7         | 0.2%    |
| 5.17.1  | 7         | 0.2%    |
| 5.13.12 | 7         | 0.2%    |
| 5.11.12 | 7         | 0.2%    |
| 6.5.7   | 6         | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 581       | 16.49%  |
| 5.15    | 403       | 11.44%  |
| 5.10    | 285       | 8.09%   |
| 4.15    | 205       | 5.82%   |
| 5.11    | 196       | 5.56%   |
| 5.8     | 177       | 5.02%   |
| 5.3     | 168       | 4.77%   |
| 5.13    | 167       | 4.74%   |
| 6.1     | 161       | 4.57%   |
| 6.2     | 159       | 4.51%   |
| 5.19    | 156       | 4.43%   |
| 5.0     | 111       | 3.15%   |
| 5.16    | 102       | 2.9%    |
| 4.18    | 84        | 2.38%   |
| 6.4     | 67        | 1.9%    |
| 6.0     | 59        | 1.67%   |
| 4.19    | 50        | 1.42%   |
| 5.14    | 48        | 1.36%   |
| 6.5     | 47        | 1.33%   |
| 4.9     | 39        | 1.11%   |
| 5.18    | 37        | 1.05%   |
| 6.3     | 31        | 0.88%   |
| 5.17    | 31        | 0.88%   |
| 5.9     | 29        | 0.82%   |
| 5.6     | 25        | 0.71%   |
| 5.7     | 24        | 0.68%   |
| 5.12    | 23        | 0.65%   |
| 5.5     | 14        | 0.4%    |
| 4.4     | 14        | 0.4%    |
| 4.16    | 5         | 0.14%   |
| 5.2     | 4         | 0.11%   |
| 4.1     | 4         | 0.11%   |
| 3.10    | 4         | 0.11%   |
| 5.1     | 3         | 0.09%   |
| 4.20    | 3         | 0.09%   |
| 4.13    | 3         | 0.09%   |
| 6.6     | 1         | 0.03%   |
| 4.8     | 1         | 0.03%   |
| 4.17    | 1         | 0.03%   |
| 3.16    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 3039      | 95.99%  |
| i686   | 127       | 4.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 1479      | 44.66%  |
| KDE5             | 586       | 17.69%  |
| Unknown          | 341       | 10.3%   |
| XFCE             | 262       | 7.91%   |
| X-Cinnamon       | 210       | 6.34%   |
| MATE             | 90        | 2.72%   |
| KDE              | 77        | 2.32%   |
| LXQt             | 36        | 1.09%   |
| Cinnamon         | 33        | 1%      |
| Pantheon         | 32        | 0.97%   |
| i3               | 24        | 0.72%   |
| Unity            | 22        | 0.66%   |
| KDE4             | 22        | 0.66%   |
| Budgie           | 16        | 0.48%   |
| LXDE             | 15        | 0.45%   |
| GNOME Flashback  | 12        | 0.36%   |
| Deepin           | 10        | 0.3%    |
| Openbox          | 6         | 0.18%   |
| GNOME Classic    | 5         | 0.15%   |
| bspwm            | 5         | 0.15%   |
| lightdm-xsession | 4         | 0.12%   |
| DWM              | 4         | 0.12%   |
| LeftWM           | 2         | 0.06%   |
| icewm            | 2         | 0.06%   |
| Hyprland         | 2         | 0.06%   |
| Endless:GNOME    | 2         | 0.06%   |
| Cutefish         | 2         | 0.06%   |
| awesome          | 2         | 0.06%   |
| xmonad           | 1         | 0.03%   |
| trinity          | 1         | 0.03%   |
| sway             | 1         | 0.03%   |
| river            | 1         | 0.03%   |
| qtile            | 1         | 0.03%   |
| Lubuntu          | 1         | 0.03%   |
| i3-with-shmlog   | 1         | 0.03%   |
| enlightenment    | 1         | 0.03%   |
| BunsenLabs       | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2455      | 75.03%  |
| Wayland | 598       | 18.28%  |
| Unknown | 194       | 5.93%   |
| Tty     | 25        | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1594      | 48.54%  |
| SDDM    | 492       | 14.98%  |
| GDM     | 391       | 11.91%  |
| GDM3    | 383       | 11.66%  |
| LightDM | 294       | 8.95%   |
| TDM     | 90        | 2.74%   |
| KDM     | 24        | 0.73%   |
| XDM     | 7         | 0.21%   |
| SLiM    | 3         | 0.09%   |
| Ly      | 3         | 0.09%   |
| SLIMSKI | 1         | 0.03%   |
| LY-DM   | 1         | 0.03%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| es_ES          | 1869      | 57.45%  |
| en_US          | 644       | 19.8%   |
| Unknown        | 344       | 10.57%  |
| ca_ES          | 128       | 3.93%   |
| en_GB          | 80        | 2.46%   |
| C              | 32        | 0.98%   |
| de_DE          | 23        | 0.71%   |
| gl_ES          | 14        | 0.43%   |
| eu_ES          | 13        | 0.4%    |
| ru_RU          | 11        | 0.34%   |
| fr_FR          | 11        | 0.34%   |
| it_IT          | 10        | 0.31%   |
| an_ES          | 9         | 0.28%   |
| pt_BR          | 6         | 0.18%   |
| es_MX          | 6         | 0.18%   |
| es_AR          | 6         | 0.18%   |
| en_AG          | 5         | 0.15%   |
| ca_AD          | 4         | 0.12%   |
| pl_PL          | 3         | 0.09%   |
| fr_BE          | 3         | 0.09%   |
| en_IE          | 3         | 0.09%   |
| POSIX          | 2         | 0.06%   |
| nl_NL          | 2         | 0.06%   |
| es_US          | 2         | 0.06%   |
| es_BO          | 2         | 0.06%   |
| en_CA          | 2         | 0.06%   |
| de_CH          | 2         | 0.06%   |
| de_AT          | 2         | 0.06%   |
| ca_ES@valencia | 2         | 0.06%   |
| sp_SP          | 1         | 0.03%   |
| ro_RO          | 1         | 0.03%   |
| nb_NO          | 1         | 0.03%   |
| fr_CH          | 1         | 0.03%   |
| et_EE          | 1         | 0.03%   |
| es_VE          | 1         | 0.03%   |
| es_PE          | 1         | 0.03%   |
| eo             | 1         | 0.03%   |
| en_NZ          | 1         | 0.03%   |
| en_HK          | 1         | 0.03%   |
| en_AU          | 1         | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1768      | 54.62%  |
| BIOS | 1469      | 45.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2473      | 75.88%  |
| Btrfs   | 278       | 8.53%   |
| Overlay | 234       | 7.18%   |
| Unknown | 111       | 3.41%   |
| Tmpfs   | 79        | 2.42%   |
| Xfs     | 45        | 1.38%   |
| Zfs     | 19        | 0.58%   |
| Ext2    | 10        | 0.31%   |
| Ext3    | 4         | 0.12%   |
| Aufs    | 3         | 0.09%   |
| Jfs     | 2         | 0.06%   |
| F2fs    | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1673      | 51.64%  |
| GPT     | 1242      | 38.33%  |
| MBR     | 325       | 10.03%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2851      | 88.4%   |
| Yes       | 374       | 11.6%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2245      | 69.7%   |
| Yes       | 976       | 30.3%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 582       | 18.39%  |
| Lenovo              | 545       | 17.22%  |
| ASUSTek Computer    | 466       | 14.72%  |
| Acer                | 308       | 9.73%   |
| Dell                | 255       | 8.06%   |
| MSI                 | 211       | 6.67%   |
| Toshiba             | 121       | 3.82%   |
| Apple               | 81        | 2.56%   |
| HUAWEI              | 54        | 1.71%   |
| Sony                | 46        | 1.45%   |
| Packard Bell        | 39        | 1.23%   |
| Chuwi               | 38        | 1.2%    |
| Notebook            | 35        | 1.11%   |
| Valve               | 34        | 1.07%   |
| Samsung Electronics | 33        | 1.04%   |
| Unknown             | 32        | 1.01%   |
| SLIMBOOK            | 28        | 0.88%   |
| LG Electronics      | 21        | 0.66%   |
| Medion              | 18        | 0.57%   |
| Fujitsu             | 15        | 0.47%   |
| Timi                | 13        | 0.41%   |
| Gigabyte Technology | 12        | 0.38%   |
| Fujitsu Siemens     | 12        | 0.38%   |
| eMachines           | 11        | 0.35%   |
| Teclast             | 10        | 0.32%   |
| Dynabook            | 10        | 0.32%   |
| Clevo               | 9         | 0.28%   |
| Intel               | 8         | 0.25%   |
| Google              | 6         | 0.19%   |
| VANT                | 4         | 0.13%   |
| Razer               | 4         | 0.13%   |
| PC Specialist       | 4         | 0.13%   |
| HONOR               | 4         | 0.13%   |
| TUXEDO              | 3         | 0.09%   |
| Thomson             | 3         | 0.09%   |
| Qilive              | 3         | 0.09%   |
| Panasonic           | 3         | 0.09%   |
| IBM                 | 3         | 0.09%   |
| Compal              | 3         | 0.09%   |
| Beelink             | 3         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 53        | 1.67%   |
| Valve Jupiter                              | 34        | 1.07%   |
| HP Pavilion g6                             | 24        | 0.76%   |
| HP Pavilion dv6                            | 22        | 0.7%    |
| HP Notebook                                | 21        | 0.66%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.57%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 17        | 0.54%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 16        | 0.51%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 12        | 0.38%   |
| HUAWEI BOHK-WAX9X                          | 12        | 0.38%   |
| HP G62                                     | 12        | 0.38%   |
| HP Laptop 15-da0xxx                        | 11        | 0.35%   |
| Chuwi GemiBook Pro                         | 11        | 0.35%   |
| HP Pavilion 15                             | 10        | 0.32%   |
| Dell XPS 13 7390                           | 10        | 0.32%   |
| HP Laptop 15s-fq1xxx                       | 9         | 0.28%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.28%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.25%   |
| MSI Prestige 15 A10SC                      | 8         | 0.25%   |
| MSI Modern 14 A10M                         | 8         | 0.25%   |
| HP Laptop 15-bw0xx                         | 8         | 0.25%   |
| Dell XPS 15 7590                           | 8         | 0.25%   |
| ASUS X555LAB                               | 8         | 0.25%   |
| ASUS X550VX                                | 8         | 0.25%   |
| ASUS X540NA                                | 8         | 0.25%   |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 8         | 0.25%   |
| Acer TravelMate 5720                       | 8         | 0.25%   |
| Acer Aspire 5750G                          | 8         | 0.25%   |
| Lenovo Z50-70 20354                        | 7         | 0.22%   |
| Lenovo Y520-15IKBN 80WK                    | 7         | 0.22%   |
| Lenovo Legion 5 15ACH6H 82JU               | 7         | 0.22%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.22%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2        | 7         | 0.22%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 7         | 0.22%   |
| Lenovo G50-70 20351                        | 7         | 0.22%   |
| HUAWEI NBLK-WAX9X                          | 7         | 0.22%   |
| HP Victus by Laptop 16-e0xxx               | 7         | 0.22%   |
| HP ProBook 450 G8 Notebook PC              | 7         | 0.22%   |
| HP Pavilion Notebook                       | 7         | 0.22%   |
| HP Pavilion dv7                            | 7         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 217       | 6.86%   |
| Lenovo ThinkPad       | 208       | 6.57%   |
| Lenovo IdeaPad        | 155       | 4.9%    |
| HP Pavilion           | 140       | 4.42%   |
| Dell Latitude         | 100       | 3.16%   |
| Toshiba Satellite     | 93        | 2.94%   |
| ASUS VivoBook         | 89        | 2.81%   |
| HP Laptop             | 88        | 2.78%   |
| Dell XPS              | 64        | 2.02%   |
| HP EliteBook          | 63        | 1.99%   |
| Unknown               | 53        | 1.67%   |
| HP ProBook            | 43        | 1.36%   |
| Dell Inspiron         | 43        | 1.36%   |
| ASUS ZenBook          | 42        | 1.33%   |
| HP Compaq             | 40        | 1.26%   |
| MSI Prestige          | 38        | 1.2%    |
| ASUS ROG              | 38        | 1.2%    |
| Packard Bell EasyNote | 35        | 1.11%   |
| Valve Jupiter         | 34        | 1.07%   |
| MSI Modern            | 33        | 1.04%   |
| HP 250                | 33        | 1.04%   |
| Lenovo Legion         | 30        | 0.95%   |
| Acer TravelMate       | 29        | 0.92%   |
| HP OMEN               | 24        | 0.76%   |
| ASUS ASUS             | 22        | 0.7%    |
| Acer Extensa          | 22        | 0.7%    |
| HP Notebook           | 21        | 0.66%   |
| Lenovo ThinkBook      | 20        | 0.63%   |
| Chuwi GemiBook        | 17        | 0.54%   |
| ASUS TUF              | 17        | 0.54%   |
| HP ENVY               | 16        | 0.51%   |
| Lenovo Yoga           | 15        | 0.47%   |
| HP Victus             | 15        | 0.47%   |
| Fujitsu LIFEBOOK      | 14        | 0.44%   |
| Dell Precision        | 13        | 0.41%   |
| HUAWEI BOHK-WAX9X     | 12        | 0.38%   |
| HP G62                | 12        | 0.38%   |
| HP 255                | 12        | 0.38%   |
| Dell Vostro           | 12        | 0.38%   |
| Toshiba PORTEGE       | 11        | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 317       | 10.02%  |
| 2018    | 304       | 9.61%   |
| 2021    | 293       | 9.26%   |
| 2020    | 289       | 9.13%   |
| 2014    | 210       | 6.64%   |
| 2015    | 194       | 6.13%   |
| 2011    | 184       | 5.81%   |
| 2017    | 180       | 5.69%   |
| 2013    | 159       | 5.02%   |
| 2010    | 159       | 5.02%   |
| 2012    | 153       | 4.83%   |
| 2022    | 148       | 4.68%   |
| 2008    | 143       | 4.52%   |
| 2009    | 128       | 4.04%   |
| 2016    | 125       | 3.95%   |
| 2007    | 91        | 2.88%   |
| 2023    | 33        | 1.04%   |
| 2006    | 32        | 1.01%   |
| 2005    | 10        | 0.32%   |
| 2004    | 5         | 0.16%   |
| 2003    | 3         | 0.09%   |
| Unknown | 3         | 0.09%   |
| 2002    | 1         | 0.03%   |
| 2001    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 3165      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2894      | 90.75%  |
| Enabled  | 295       | 9.25%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3156      | 99.72%  |
| Yes  | 9         | 0.28%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 831       | 25.94%  |
| 3.01-4.0    | 683       | 21.32%  |
| 8.01-16.0   | 619       | 19.32%  |
| 16.01-24.0  | 572       | 17.85%  |
| 32.01-64.0  | 211       | 6.59%   |
| 1.01-2.0    | 143       | 4.46%   |
| 2.01-3.0    | 57        | 1.78%   |
| 0.51-1.0    | 48        | 1.5%    |
| 24.01-32.0  | 19        | 0.59%   |
| 64.01-256.0 | 19        | 0.59%   |
| 0.01-0.5    | 2         | 0.06%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1269      | 36.17%  |
| 2.01-3.0   | 931       | 26.54%  |
| 4.01-8.0   | 465       | 13.26%  |
| 3.01-4.0   | 419       | 11.94%  |
| 0.51-1.0   | 260       | 7.41%   |
| 8.01-16.0  | 122       | 3.48%   |
| 0.01-0.5   | 30        | 0.86%   |
| 16.01-24.0 | 8         | 0.23%   |
| 24.01-32.0 | 3         | 0.09%   |
| 32.01-64.0 | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2438      | 75.55%  |
| 2      | 679       | 21.04%  |
| 3      | 74        | 2.29%   |
| 0      | 26        | 0.81%   |
| 4      | 7         | 0.22%   |
| 5      | 3         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2114      | 66.46%  |
| Yes       | 1067      | 33.54%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2509      | 78.78%  |
| No        | 676       | 21.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 3104      | 98.04%  |
| No        | 62        | 1.96%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2391      | 74.93%  |
| No        | 800       | 25.07%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 3165      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 547       | 15.82%  |
| Barcelona                  | 385       | 11.14%  |
| Seville                    | 124       | 3.59%   |
| Valencia                   | 110       | 3.18%   |
| Zaragoza                   | 57        | 1.65%   |
| Granada                    | 53        | 1.53%   |
| Málaga                    | 49        | 1.42%   |
| Alcobendas                 | 43        | 1.24%   |
| Palma                      | 40        | 1.16%   |
| Vigo                       | 37        | 1.07%   |
| Valladolid                 | 34        | 0.98%   |
| Sabadell                   | 33        | 0.95%   |
| Bilbao                     | 29        | 0.84%   |
| Alicante                   | 28        | 0.81%   |
| Pamplona                   | 27        | 0.78%   |
| Las Palmas de Gran Canaria | 26        | 0.75%   |
| Córdoba                   | 26        | 0.75%   |
| Santiago de Compostela     | 23        | 0.67%   |
| Oviedo                     | 23        | 0.67%   |
| Alcalá de Henares         | 23        | 0.67%   |
| A Coruña                  | 23        | 0.67%   |
| Donostia / San Sebastian   | 22        | 0.64%   |
| Murcia                     | 21        | 0.61%   |
| Burgos                     | 19        | 0.55%   |
| León                      | 17        | 0.49%   |
| Mostoles                   | 16        | 0.46%   |
| Gijón                     | 16        | 0.46%   |
| Vitoria-Gasteiz            | 15        | 0.43%   |
| Salamanca                  | 15        | 0.43%   |
| Reus                       | 15        | 0.43%   |
| Getxo                      | 14        | 0.4%    |
| Barakaldo                  | 14        | 0.4%    |
| Almería                   | 14        | 0.4%    |
| Santander                  | 13        | 0.38%   |
| Santa Cruz de Tenerife     | 12        | 0.35%   |
| Ourense                    | 12        | 0.35%   |
| Girona                     | 12        | 0.35%   |
| Cartagena                  | 12        | 0.35%   |
| Badalona                   | 12        | 0.35%   |
| Tarragona                  | 11        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 547       | 676    | 14.22%  |
| WDC                         | 398       | 500    | 10.34%  |
| Seagate                     | 386       | 458    | 10.03%  |
| Kingston                    | 382       | 485    | 9.93%   |
| Toshiba                     | 312       | 399    | 8.11%   |
| SanDisk                     | 261       | 342    | 6.78%   |
| Unknown                     | 189       | 260    | 4.91%   |
| SK hynix                    | 176       | 212    | 4.57%   |
| Micron Technology           | 138       | 175    | 3.59%   |
| Hitachi                     | 134       | 159    | 3.48%   |
| Intel                       | 131       | 181    | 3.4%    |
| Crucial                     | 113       | 142    | 2.94%   |
| HGST                        | 110       | 133    | 2.86%   |
| China                       | 39        | 57     | 1.01%   |
| KIOXIA                      | 37        | 47     | 0.96%   |
| Apple                       | 35        | 44     | 0.91%   |
| Phison                      | 33        | 36     | 0.86%   |
| Fujitsu                     | 33        | 37     | 0.86%   |
| Phison Electronics          | 29        | 33     | 0.75%   |
| Kingston Technology Company | 27        | 38     | 0.7%    |
| Netac                       | 20        | 31     | 0.52%   |
| LITEON                      | 19        | 20     | 0.49%   |
| Micron/Crucial Technology   | 18        | 21     | 0.47%   |
| KingSpec                    | 15        | 21     | 0.39%   |
| A-DATA Technology           | 13        | 15     | 0.34%   |
| JMicron Technology          | 12        | 12     | 0.31%   |
| Unknown                     | 11        | 12     | 0.29%   |
| FORESEE                     | 10        | 16     | 0.26%   |
| Transcend                   | 9         | 15     | 0.23%   |
| Teclast                     | 9         | 9      | 0.23%   |
| Silicon Motion              | 8         | 8      | 0.21%   |
| PNY                         | 8         | 14     | 0.21%   |
| OCZ                         | 8         | 9      | 0.21%   |
| Emtec                       | 8         | 8      | 0.21%   |
| USB30                       | 7         | 8      | 0.18%   |
| Patriot                     | 6         | 8      | 0.16%   |
| LITEONIT                    | 6         | 7      | 0.16%   |
| Intenso                     | 6         | 12     | 0.16%   |
| TCSUNBOW                    | 5         | 6      | 0.13%   |
| O2 Micro                    | 5         | 5      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 134       | 3.37%   |
| Kingston SA400S37480G 480GB SSD                    | 56        | 1.41%   |
| Seagate ST500LT012-1DG142 500GB                    | 48        | 1.21%   |
| Unknown MMC Card  32GB                             | 38        | 0.96%   |
| Unknown MMC Card  64GB                             | 37        | 0.93%   |
| HGST HTS721010A9E630 1TB                           | 37        | 0.93%   |
| Toshiba MQ01ABD100 1TB                             | 36        | 0.91%   |
| Seagate ST1000LM035-1RK172 1TB                     | 35        | 0.88%   |
| SK hynix NVMe SSD Drive 512GB                      | 34        | 0.86%   |
| Seagate ST9500325AS 500GB                          | 34        | 0.86%   |
| Toshiba MQ01ABF050 500GB                           | 33        | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 33        | 0.83%   |
| Samsung NVMe SSD Drive 512GB                       | 31        | 0.78%   |
| Toshiba MQ04ABF100 1TB                             | 28        | 0.7%    |
| SanDisk NVMe SSD Drive 512GB                       | 28        | 0.7%    |
| Unknown MMC Card  128GB                            | 23        | 0.58%   |
| SanDisk SSD PLUS 480GB                             | 23        | 0.58%   |
| Toshiba MQ01ABD050 500GB                           | 22        | 0.55%   |
| Samsung SSD 860 EVO 500GB                          | 22        | 0.55%   |
| Samsung SSD 850 EVO 250GB                          | 22        | 0.55%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 22        | 0.55%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 22        | 0.55%   |
| Kingston SUV400S37240G 240GB SSD                   | 22        | 0.55%   |
| Kingston SA400S37120G 120GB SSD                    | 22        | 0.55%   |
| HGST HTS545050A7E680 500GB                         | 22        | 0.55%   |
| Intel NVMe SSD Drive 512GB                         | 21        | 0.53%   |
| WDC WD10JPVX-22JC3T0 1TB                           | 20        | 0.5%    |
| Kingston RBUSC180DS37256GJ 256GB SSD               | 20        | 0.5%    |
| HGST HTS541010A9E680 1TB                           | 19        | 0.48%   |
| Seagate Expansion 1TB                              | 18        | 0.45%   |
| SanDisk NVMe SSD Drive 256GB                       | 18        | 0.45%   |
| Crucial CT500MX500SSD1 500GB                       | 17        | 0.43%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB  | 16        | 0.4%    |
| Samsung SSD 850 EVO 500GB                          | 16        | 0.4%    |
| Seagate ST1000LM049-2GH172 1TB                     | 15        | 0.38%   |
| Kingston SA400S37960G 960GB SSD                    | 15        | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 14        | 0.35%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                 | 13        | 0.33%   |
| Micron NVMe SSD Drive 512GB                        | 13        | 0.33%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB            | 13        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 379       | 450    | 32.48%  |
| WDC                 | 251       | 306    | 21.51%  |
| Toshiba             | 204       | 251    | 17.48%  |
| Hitachi             | 134       | 159    | 11.48%  |
| HGST                | 110       | 133    | 9.43%   |
| Fujitsu             | 33        | 37     | 2.83%   |
| Samsung Electronics | 30        | 31     | 2.57%   |
| Unknown             | 9         | 13     | 0.77%   |
| Apple               | 4         | 4      | 0.34%   |
| USB3.0              | 3         | 3      | 0.26%   |
| USB                 | 2         | 2      | 0.17%   |
| SSK                 | 2         | 2      | 0.17%   |
| LaCie               | 2         | 2      | 0.17%   |
| SABRENT             | 1         | 1      | 0.09%   |
| OEM                 | 1         | 1      | 0.09%   |
| Maxone              | 1         | 1      | 0.09%   |
| IBM                 | 1         | 1      | 0.09%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 328       | 417    | 26.69%  |
| Samsung Electronics | 206       | 255    | 16.76%  |
| SanDisk             | 129       | 160    | 10.5%   |
| Crucial             | 103       | 129    | 8.38%   |
| Toshiba             | 51        | 69     | 4.15%   |
| WDC                 | 47        | 63     | 3.82%   |
| SK hynix            | 39        | 43     | 3.17%   |
| China               | 39        | 57     | 3.17%   |
| Micron Technology   | 35        | 45     | 2.85%   |
| Intel               | 22        | 35     | 1.79%   |
| Netac               | 20        | 31     | 1.63%   |
| Apple               | 18        | 20     | 1.46%   |
| LITEON              | 17        | 17     | 1.38%   |
| KingSpec            | 15        | 21     | 1.22%   |
| A-DATA Technology   | 11        | 13     | 0.9%    |
| FORESEE             | 10        | 16     | 0.81%   |
| Teclast             | 9         | 9      | 0.73%   |
| Transcend           | 8         | 14     | 0.65%   |
| OCZ                 | 8         | 9      | 0.65%   |
| USB30               | 7         | 8      | 0.57%   |
| Emtec               | 7         | 7      | 0.57%   |
| PNY                 | 6         | 12     | 0.49%   |
| LITEONIT            | 6         | 7      | 0.49%   |
| Patriot             | 5         | 7      | 0.41%   |
| Intenso             | 5         | 10     | 0.41%   |
| KIOXIA-EXCERIA      | 4         | 7      | 0.33%   |
| KingDian            | 4         | 4      | 0.33%   |
| Corsair             | 4         | 5      | 0.33%   |
| Unknown             | 4         | 4      | 0.33%   |
| Unknown             | 3         | 3      | 0.24%   |
| TCSUNBOW            | 3         | 4      | 0.24%   |
| Phison              | 3         | 4      | 0.24%   |
| Drevo               | 3         | 3      | 0.24%   |
| Dogfish             | 3         | 3      | 0.24%   |
| BAITITON            | 3         | 8      | 0.24%   |
| ASMT                | 3         | 3      | 0.24%   |
| Verbatim            | 2         | 3      | 0.16%   |
| ShanDianZhe         | 2         | 2      | 0.16%   |
| Plextor             | 2         | 3      | 0.16%   |
| Lexar               | 2         | 2      | 0.16%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1165      | 1562   | 31.68%  |
| SSD     | 1148      | 1578   | 31.22%  |
| HDD     | 1139      | 1397   | 30.98%  |
| MMC     | 185       | 252    | 5.03%   |
| Unknown | 40        | 47     | 1.09%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2016      | 2869   | 57.68%  |
| NVMe | 1160      | 1549   | 33.19%  |
| MMC  | 185       | 252    | 5.29%   |
| SAS  | 134       | 166    | 3.83%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1627      | 2212   | 72.83%  |
| 0.51-1.0   | 555       | 695    | 24.84%  |
| 1.01-2.0   | 42        | 55     | 1.88%   |
| 3.01-4.0   | 5         | 6      | 0.22%   |
| 2.01-3.0   | 3         | 4      | 0.13%   |
| 4.01-10.0  | 2         | 3      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 1005      | 30.17%  |
| 251-500        | 948       | 28.46%  |
| 501-1000       | 428       | 12.85%  |
| 1-20           | 241       | 7.24%   |
| 51-100         | 234       | 7.02%   |
| 1001-2000      | 168       | 5.04%   |
| 21-50          | 148       | 4.44%   |
| Unknown        | 71        | 2.13%   |
| 2001-3000      | 45        | 1.35%   |
| More than 3000 | 43        | 1.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1411      | 40.34%  |
| 21-50          | 654       | 18.7%   |
| 101-250        | 489       | 13.98%  |
| 51-100         | 408       | 11.66%  |
| 251-500        | 262       | 7.49%   |
| 501-1000       | 139       | 3.97%   |
| Unknown        | 71        | 2.03%   |
| 1001-2000      | 41        | 1.17%   |
| 2001-3000      | 11        | 0.31%   |
| More than 3000 | 10        | 0.29%   |
| 0              | 2         | 0.06%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 7         | 8      | 3.54%   |
| HGST HTS545050A7E680 500GB            | 7         | 9      | 3.54%   |
| Seagate ST500LT012-1DG142 500GB       | 6         | 6      | 3.03%   |
| SanDisk SSD PLUS 480GB                | 6         | 7      | 3.03%   |
| China G521N256GB SSD                  | 5         | 6      | 2.53%   |
| Seagate ST9500420AS 500GB             | 4         | 4      | 2.02%   |
| Seagate ST9250827AS 250GB             | 4         | 4      | 2.02%   |
| Seagate ST500LM021-1KJ152 500GB       | 4         | 4      | 2.02%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 4      | 2.02%   |
| Kingston SA400S37480G 480GB SSD       | 4         | 4      | 2.02%   |
| Hitachi HTS545050A7E380 500GB         | 4         | 4      | 2.02%   |
| HGST HTS721010A9E630 1TB              | 4         | 4      | 2.02%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 1.52%   |
| HGST HTS541010A9E680 1TB              | 3         | 3      | 1.52%   |
| WDC WD5000BPVT-60HXZT3 500GB          | 2         | 3      | 1.01%   |
| Toshiba Q300 240GB SSD                | 2         | 2      | 1.01%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 1.01%   |
| Toshiba MQ01ABD050 500GB              | 2         | 2      | 1.01%   |
| Toshiba MK5076GSX 500GB               | 2         | 2      | 1.01%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 2         | 2      | 1.01%   |
| Seagate ST9500420ASG 500GB            | 2         | 2      | 1.01%   |
| Seagate ST500LT012-9WS142 500GB       | 2         | 2      | 1.01%   |
| Seagate ST320LT012-9WS14C 320GB       | 2         | 2      | 1.01%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 2      | 1.01%   |
| Intel SSDSC2BF180A5H SED 180GB        | 2         | 2      | 1.01%   |
| Hitachi HTS723232A7A364 320GB         | 2         | 2      | 1.01%   |
| Hitachi HTS547550A9E384 500GB         | 2         | 2      | 1.01%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 2      | 1.01%   |
| Hitachi HTS543232L9A300 320GB         | 2         | 3      | 1.01%   |
| Hitachi HTS543232A7A384 320GB         | 2         | 2      | 1.01%   |
| Hitachi HTS543216L9A300 160GB         | 2         | 2      | 1.01%   |
| HGST HTS545050A7E380 500GB            | 2         | 2      | 1.01%   |
| Fujitsu MHZ2250BH G2 250GB            | 2         | 2      | 1.01%   |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 1         | 1      | 0.51%   |
| WDC WD7500BPVT-60HXZT1 752GB          | 1         | 1      | 0.51%   |
| WDC WD6400BEVT-22A0RT0 640GB          | 1         | 2      | 0.51%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 1         | 1      | 0.51%   |
| WDC WD5000BEVT-22ZAT0 500GB           | 1         | 1      | 0.51%   |
| WDC WD5000BEVT-22A0RT0 500GB          | 1         | 1      | 0.51%   |
| WDC WD3200BEVT-00A0RT0 320GB          | 1         | 1      | 0.51%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 53     | 25.76%  |
| Hitachi             | 26        | 28     | 13.13%  |
| Toshiba             | 23        | 25     | 11.62%  |
| WDC                 | 18        | 21     | 9.09%   |
| HGST                | 18        | 21     | 9.09%   |
| Samsung Electronics | 12        | 13     | 6.06%   |
| SanDisk             | 8         | 9      | 4.04%   |
| Kingston            | 8         | 9      | 4.04%   |
| SK hynix            | 7         | 7      | 3.54%   |
| Intel               | 6         | 6      | 3.03%   |
| China               | 6         | 7      | 3.03%   |
| Fujitsu             | 5         | 5      | 2.53%   |
| Micron Technology   | 4         | 5      | 2.02%   |
| Crucial             | 4         | 6      | 2.02%   |
| OCZ                 | 1         | 1      | 0.51%   |
| IBM                 | 1         | 1      | 0.51%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 53     | 35.92%  |
| Hitachi             | 26        | 28     | 18.31%  |
| Toshiba             | 18        | 20     | 12.68%  |
| HGST                | 18        | 21     | 12.68%  |
| WDC                 | 17        | 20     | 11.97%  |
| Samsung Electronics | 6         | 6      | 4.23%   |
| Fujitsu             | 5         | 5      | 3.52%   |
| IBM                 | 1         | 1      | 0.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 140       | 154    | 71.79%  |
| SSD  | 48        | 56     | 24.62%  |
| NVMe | 7         | 7      | 3.59%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1912      | 2974   | 57.04%  |
| Works    | 1246      | 1644   | 37.17%  |
| Malfunc  | 193       | 217    | 5.76%   |
| Failed   | 1         | 1      | 0.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2163      | 58.51%  |
| AMD                              | 347       | 9.39%   |
| Samsung Electronics              | 343       | 9.28%   |
| SanDisk                          | 226       | 6.11%   |
| SK hynix                         | 131       | 3.54%   |
| Micron Technology                | 103       | 2.79%   |
| Kingston Technology Company      | 79        | 2.14%   |
| Phison Electronics               | 64        | 1.73%   |
| Toshiba America Info Systems     | 58        | 1.57%   |
| KIOXIA                           | 42        | 1.14%   |
| Nvidia                           | 28        | 0.76%   |
| Micron/Crucial Technology        | 25        | 0.68%   |
| Silicon Integrated Systems [SiS] | 14        | 0.38%   |
| Silicon Motion                   | 11        | 0.3%    |
| Apple                            | 11        | 0.3%    |
| VIA Technologies                 | 7         | 0.19%   |
| Union Memory (Shenzhen)          | 7         | 0.19%   |
| Solid State Storage Technology   | 5         | 0.14%   |
| O2 Micro                         | 5         | 0.14%   |
| JMicron Technology               | 5         | 0.14%   |
| Shenzhen Longsys Electronics     | 3         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.08%   |
| Lite-On Technology               | 3         | 0.08%   |
| Silicon Image                    | 2         | 0.05%   |
| Marvell Technology Group         | 2         | 0.05%   |
| Lenovo                           | 2         | 0.05%   |
| ADATA Technology                 | 2         | 0.05%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| Solidigm                         | 1         | 0.03%   |
| Seagate Technology               | 1         | 0.03%   |
| Netac Technology                 | 1         | 0.03%   |
| Biwin Storage Technology         | 1         | 0.03%   |
| ASMedia Technology               | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 298       | 7.46%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 232       | 5.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 158       | 3.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 158       | 3.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 149       | 3.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 143       | 3.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 139       | 3.48%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 126       | 3.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 105       | 2.63%   |
| Intel Volume Management Device NVMe RAID Controller                            | 102       | 2.55%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 95        | 2.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 85        | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 85        | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 85        | 2.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 80        | 2%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 79        | 1.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 73        | 1.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 68        | 1.7%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 64        | 1.6%    |
| Intel SSD 660P Series                                                          | 58        | 1.45%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 52        | 1.3%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 48        | 1.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 45        | 1.13%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 42        | 1.05%   |
| Intel Tiger Lake-LP SATA Controller                                            | 41        | 1.03%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 40        | 1%      |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 39        | 0.98%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 36        | 0.9%    |
| Intel Comet Lake SATA AHCI Controller                                          | 36        | 0.9%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 35        | 0.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 35        | 0.88%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 32        | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 30        | 0.75%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 30        | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 29        | 0.73%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 29        | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 29        | 0.73%   |
| Kingston Company A1000/U-SNS8154P3 x2 NVMe SSD                                 | 28        | 0.7%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 28        | 0.7%    |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                          | 27        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 2165      | 56.23%  |
| NVMe | 1168      | 30.34%  |
| RAID | 260       | 6.75%   |
| IDE  | 257       | 6.68%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 2587      | 81.74%  |
| AMD          | 577       | 18.23%  |
| CentaurHauls | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 64        | 2.02%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 57        | 1.8%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 56        | 1.77%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 52        | 1.64%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 51        | 1.61%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 48        | 1.52%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 46        | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 41        | 1.29%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 40        | 1.26%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 40        | 1.26%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 40        | 1.26%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 39        | 1.23%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 39        | 1.23%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 35        | 1.11%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 35        | 1.11%   |
| AMD Custom APU 0405                           | 34        | 1.07%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 33        | 1.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 31        | 0.98%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 30        | 0.95%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 28        | 0.88%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 27        | 0.85%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 26        | 0.82%   |
| Intel 12th Gen Core i7-12700H                 | 26        | 0.82%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 25        | 0.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 25        | 0.79%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 24        | 0.76%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 24        | 0.76%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 23        | 0.73%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 22        | 0.69%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 21        | 0.66%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 21        | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 19        | 0.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 19        | 0.6%    |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 19        | 0.6%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 19        | 0.6%    |
| Intel Atom CPU N450 @ 1.66GHz                 | 19        | 0.6%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.57%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.57%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 18        | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 723       | 22.84%  |
| Intel Core i5           | 615       | 19.43%  |
| Other                   | 350       | 11.05%  |
| Intel Celeron           | 236       | 7.45%   |
| Intel Core i3           | 226       | 7.14%   |
| Intel Core 2 Duo        | 179       | 5.65%   |
| AMD Ryzen 7             | 169       | 5.34%   |
| AMD Ryzen 5             | 123       | 3.89%   |
| Intel Atom              | 106       | 3.35%   |
| Intel Pentium Dual-Core | 41        | 1.3%    |
| Intel Pentium           | 39        | 1.23%   |
| Intel Pentium Dual      | 31        | 0.98%   |
| AMD A4                  | 30        | 0.95%   |
| AMD A6                  | 28        | 0.88%   |
| Intel Genuine           | 26        | 0.82%   |
| Intel Core 2            | 26        | 0.82%   |
| AMD E1                  | 22        | 0.69%   |
| AMD A8                  | 21        | 0.66%   |
| AMD Ryzen 9             | 15        | 0.47%   |
| AMD E                   | 14        | 0.44%   |
| AMD Ryzen 7 PRO         | 13        | 0.41%   |
| AMD Ryzen 3             | 13        | 0.41%   |
| Intel Core i9           | 10        | 0.32%   |
| Intel Pentium M         | 9         | 0.28%   |
| Intel Celeron M         | 9         | 0.28%   |
| AMD Athlon              | 9         | 0.28%   |
| AMD A10                 | 9         | 0.28%   |
| Intel Core m3           | 6         | 0.19%   |
| AMD Turion 64 X2 Mobile | 6         | 0.19%   |
| Intel Pentium 4         | 4         | 0.13%   |
| AMD Turion II Dual-Core | 4         | 0.13%   |
| AMD FX                  | 4         | 0.13%   |
| AMD Athlon II           | 4         | 0.13%   |
| Intel Core m5           | 3         | 0.09%   |
| AMD Turion 64 Mobile    | 3         | 0.09%   |
| AMD Athlon X2           | 3         | 0.09%   |
| AMD A12                 | 3         | 0.09%   |
| Intel Xeon              | 2         | 0.06%   |
| Intel Pentium Silver    | 2         | 0.06%   |
| Intel Core M            | 2         | 0.06%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1518      | 47.9%   |
| 4       | 995       | 31.4%   |
| 6       | 224       | 7.07%   |
| 8       | 216       | 6.82%   |
| 1       | 121       | 3.82%   |
| 14      | 43        | 1.36%   |
| 10      | 28        | 0.88%   |
| 12      | 16        | 0.5%    |
| Unknown | 4         | 0.13%   |
| 16      | 2         | 0.06%   |
| 24      | 1         | 0.03%   |
| 20      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 3164      | 99.97%  |
| 2      | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 2273      | 71.73%  |
| 1       | 892       | 28.15%  |
| Unknown | 4         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 3055      | 96.07%  |
| 32-bit         | 57        | 1.79%   |
| Unknown        | 54        | 1.7%    |
| 64-bit         | 14        | 0.44%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 806       | 24.48%  |
| 0x206a7    | 144       | 4.37%   |
| 0x306a9    | 124       | 3.77%   |
| 0x806c1    | 112       | 3.4%    |
| 0x40651    | 104       | 3.16%   |
| 0x806ea    | 102       | 3.1%    |
| 0x906ea    | 97        | 2.95%   |
| 0x806ec    | 96        | 2.92%   |
| 0x406e3    | 86        | 2.61%   |
| 0x1067a    | 86        | 2.61%   |
| 0x806e9    | 79        | 2.4%    |
| 0x6fd      | 78        | 2.37%   |
| 0x20655    | 77        | 2.34%   |
| 0x306d4    | 71        | 2.16%   |
| 0x306c3    | 66        | 2%      |
| 0x30678    | 53        | 1.61%   |
| 0x0a50000c | 51        | 1.55%   |
| 0x08108109 | 50        | 1.52%   |
| 0xa0652    | 42        | 1.28%   |
| 0x706e5    | 41        | 1.25%   |
| 0x10676    | 41        | 1.25%   |
| 0x06006705 | 38        | 1.15%   |
| 0x706a1    | 37        | 1.12%   |
| 0x20652    | 36        | 1.09%   |
| 0x506e3    | 35        | 1.06%   |
| 0x906a3    | 33        | 1%      |
| 0x08600106 | 32        | 0.97%   |
| 0x106ca    | 31        | 0.94%   |
| 0x08108102 | 30        | 0.91%   |
| 0x906e9    | 29        | 0.88%   |
| 0x706a8    | 29        | 0.88%   |
| 0x806eb    | 28        | 0.85%   |
| 0x506c9    | 25        | 0.76%   |
| 0x406c4    | 25        | 0.76%   |
| 0x08608103 | 25        | 0.76%   |
| 0x806d1    | 24        | 0.73%   |
| 0x406c3    | 22        | 0.67%   |
| 0x08600104 | 22        | 0.67%   |
| 0x6f6      | 20        | 0.61%   |
| 0x106c2    | 19        | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 566       | 17.88%  |
| Haswell          | 239       | 7.55%   |
| SandyBridge      | 177       | 5.59%   |
| Penryn           | 165       | 5.21%   |
| TigerLake        | 164       | 5.18%   |
| Core             | 151       | 4.77%   |
| Skylake          | 150       | 4.74%   |
| IvyBridge        | 150       | 4.74%   |
| Unknown          | 134       | 4.23%   |
| Westmere         | 133       | 4.2%    |
| Silvermont       | 121       | 3.82%   |
| Broadwell        | 100       | 3.16%   |
| Zen+             | 93        | 2.94%   |
| Zen 2            | 86        | 2.72%   |
| Goldmont plus    | 86        | 2.72%   |
| Zen 3            | 83        | 2.62%   |
| IceLake          | 67        | 2.12%   |
| CometLake        | 66        | 2.08%   |
| Excavator        | 65        | 2.05%   |
| Bonnell          | 65        | 2.05%   |
| Alderlake Hybrid | 62        | 1.96%   |
| Goldmont         | 33        | 1.04%   |
| Puma             | 28        | 0.88%   |
| P6               | 28        | 0.88%   |
| Zen              | 27        | 0.85%   |
| Jaguar           | 24        | 0.76%   |
| Bobcat           | 23        | 0.73%   |
| K8 Hammer        | 17        | 0.54%   |
| K10              | 15        | 0.47%   |
| Tremont          | 12        | 0.38%   |
| Piledriver       | 10        | 0.32%   |
| Nehalem          | 9         | 0.28%   |
| Steamroller      | 5         | 0.16%   |
| NetBurst         | 5         | 0.16%   |
| K10 Llano        | 4         | 0.13%   |
| K8 & K10 hybrid  | 3         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2320      | 57.07%  |
| Nvidia                           | 942       | 23.17%  |
| AMD                              | 787       | 19.36%  |
| Silicon Integrated Systems [SiS] | 9         | 0.22%   |
| VIA Technologies                 | 7         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 161       | 3.83%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 155       | 3.69%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 145       | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 140       | 3.33%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 129       | 3.07%   |
| Intel UHD Graphics 620                                                                   | 114       | 2.71%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 101       | 2.4%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 101       | 2.4%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 96        | 2.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 91        | 2.17%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 90        | 2.14%   |
| Intel HD Graphics 620                                                                    | 90        | 2.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 86        | 2.05%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 85        | 2.02%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 84        | 2%      |
| Intel HD Graphics 5500                                                                   | 83        | 1.97%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 83        | 1.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 70        | 1.67%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 69        | 1.64%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 68        | 1.62%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 67        | 1.59%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 54        | 1.28%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 53        | 1.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 53        | 1.26%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 49        | 1.17%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 1.12%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 47        | 1.12%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 47        | 1.12%   |
| Intel HD Graphics 530                                                                    | 46        | 1.09%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 44        | 1.05%   |
| AMD Lucienne                                                                             | 41        | 0.98%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 38        | 0.9%    |
| Intel HD Graphics 630                                                                    | 38        | 0.9%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 36        | 0.86%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 34        | 0.81%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 34        | 0.81%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 33        | 0.79%   |
| Intel HD Graphics 500                                                                    | 30        | 0.71%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 29        | 0.69%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 29        | 0.69%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1515      | 47.73%  |
| Intel + Nvidia | 683       | 21.52%  |
| 1 x AMD        | 525       | 16.54%  |
| 1 x Nvidia     | 156       | 4.91%   |
| Intel + AMD    | 110       | 3.47%   |
| AMD + Nvidia   | 103       | 3.25%   |
| 2 x AMD        | 48        | 1.51%   |
| 2 x Intel      | 11        | 0.35%   |
| 1 x SiS        | 9         | 0.28%   |
| 1 x VIA        | 7         | 0.22%   |
| 2 x Nvidia     | 4         | 0.13%   |
| Other          | 3         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2662      | 83.06%  |
| Proprietary | 442       | 13.79%  |
| Unknown     | 101       | 3.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 2025      | 62.27%  |
| 0.01-0.5   | 413       | 12.7%   |
| 1.01-2.0   | 359       | 11.04%  |
| 3.01-4.0   | 207       | 6.37%   |
| 0.51-1.0   | 168       | 5.17%   |
| 5.01-6.0   | 43        | 1.32%   |
| 7.01-8.0   | 30        | 0.92%   |
| 2.01-3.0   | 4         | 0.12%   |
| 8.01-16.0  | 3         | 0.09%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 609       | 17.15%  |
| Chimei Innolux          | 564       | 15.88%  |
| LG Display              | 465       | 13.09%  |
| BOE                     | 436       | 12.28%  |
| Samsung Electronics     | 333       | 9.38%   |
| Sharp                   | 97        | 2.73%   |
| Chi Mei Optoelectronics | 96        | 2.7%    |
| Goldstar                | 92        | 2.59%   |
| Dell                    | 85        | 2.39%   |
| Apple                   | 81        | 2.28%   |
| PANDA                   | 75        | 2.11%   |
| Hewlett-Packard         | 72        | 2.03%   |
| BenQ                    | 54        | 1.52%   |
| Lenovo                  | 49        | 1.38%   |
| LG Philips              | 45        | 1.27%   |
| Acer                    | 33        | 0.93%   |
| Philips                 | 32        | 0.9%    |
| Ancor Communications    | 26        | 0.73%   |
| Valve                   | 25        | 0.7%    |
| AOC                     | 25        | 0.7%    |
| HannStar                | 21        | 0.59%   |
| Sony                    | 19        | 0.54%   |
| InfoVision              | 18        | 0.51%   |
| ASUSTek Computer        | 16        | 0.45%   |
| CPT                     | 15        | 0.42%   |
| CSO                     | 14        | 0.39%   |
| Quanta Display          | 8         | 0.23%   |
| ViewSonic               | 7         | 0.2%    |
| Unknown                 | 7         | 0.2%    |
| TMX                     | 7         | 0.2%    |
| MSI                     | 7         | 0.2%    |
| Analogix                | 7         | 0.2%    |
| Mi                      | 6         | 0.17%   |
| Toshiba                 | 5         | 0.14%   |
| Seiko/Epson             | 5         | 0.14%   |
| Panasonic               | 5         | 0.14%   |
| AGO                     | 5         | 0.14%   |
| ___                     | 4         | 0.11%   |
| NEC Computers           | 4         | 0.11%   |
| MStar                   | 3         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 68        | 1.89%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 42        | 1.17%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 35        | 0.97%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 32        | 0.89%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 32        | 0.89%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 25        | 0.7%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 25        | 0.7%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 23        | 0.64%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 22        | 0.61%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 21        | 0.58%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 21        | 0.58%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 20        | 0.56%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 20        | 0.56%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 17        | 0.47%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 17        | 0.47%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 16        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 16        | 0.45%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 16        | 0.45%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 16        | 0.45%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 15        | 0.42%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 15        | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 15        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 381x214mm 17.2-inch         | 15        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 15        | 0.42%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 15        | 0.42%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 14        | 0.39%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 13        | 0.36%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 13        | 0.36%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 13        | 0.36%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 13        | 0.36%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 12        | 0.33%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 12        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 12        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 12        | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 12        | 0.33%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 11        | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 11        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch         | 11        | 0.31%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                    | 11        | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1361      | 41.32%  |
| 1366x768 (WXGA)    | 1040      | 31.57%  |
| 1280x800 (WXGA)    | 174       | 5.28%   |
| 3840x2160 (4K)     | 96        | 2.91%   |
| 1600x900 (HD+)     | 82        | 2.49%   |
| 2560x1440 (QHD)    | 68        | 2.06%   |
| 1440x900 (WXGA+)   | 68        | 2.06%   |
| 1920x1200 (WUXGA)  | 49        | 1.49%   |
| 1024x600           | 45        | 1.37%   |
| 2560x1600          | 41        | 1.24%   |
| 1680x1050 (WSXGA+) | 32        | 0.97%   |
| 1280x1024 (SXGA)   | 32        | 0.97%   |
| 800x1280           | 31        | 0.94%   |
| 2160x1440          | 31        | 0.94%   |
| 2880x1800          | 25        | 0.76%   |
| 3440x1440          | 16        | 0.49%   |
| 2560x1080          | 15        | 0.46%   |
| 3200x1800 (QHD+)   | 9         | 0.27%   |
| 1360x768           | 8         | 0.24%   |
| 1024x768 (XGA)     | 8         | 0.24%   |
| 3840x2400          | 7         | 0.21%   |
| Unknown            | 5         | 0.15%   |
| 1280x768           | 4         | 0.12%   |
| 3456x2160          | 3         | 0.09%   |
| 3072x1920          | 3         | 0.09%   |
| 2520x1680          | 3         | 0.09%   |
| 2288x1287          | 3         | 0.09%   |
| 1920x540           | 3         | 0.09%   |
| 1920x1280          | 3         | 0.09%   |
| 1600x1200          | 3         | 0.09%   |
| 1400x1050          | 3         | 0.09%   |
| 3840x1600          | 2         | 0.06%   |
| 3840x1080          | 2         | 0.06%   |
| 3200x2000          | 2         | 0.06%   |
| 2304x1440          | 2         | 0.06%   |
| 5760x1080          | 1         | 0.03%   |
| 3200x1080          | 1         | 0.03%   |
| 3000x2000          | 1         | 0.03%   |
| 2880x1920          | 1         | 0.03%   |
| 2736x1824          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1684      | 47.4%   |
| 13      | 418       | 11.76%  |
| 14      | 307       | 8.64%   |
| 17      | 188       | 5.29%   |
| 24      | 125       | 3.52%   |
| 27      | 108       | 3.04%   |
| 23      | 97        | 2.73%   |
| 21      | 96        | 2.7%    |
| 12      | 71        | 2%      |
| 16      | 61        | 1.72%   |
| 11      | 56        | 1.58%   |
| 10      | 52        | 1.46%   |
| Unknown | 41        | 1.15%   |
| 34      | 32        | 0.9%    |
| 31      | 30        | 0.84%   |
| 7       | 25        | 0.7%    |
| 19      | 24        | 0.68%   |
| 18      | 17        | 0.48%   |
| 84      | 16        | 0.45%   |
| 20      | 16        | 0.45%   |
| 22      | 10        | 0.28%   |
| 72      | 9         | 0.25%   |
| 54      | 8         | 0.23%   |
| 40      | 8         | 0.23%   |
| 25      | 8         | 0.23%   |
| 3       | 7         | 0.2%    |
| 26      | 5         | 0.14%   |
| 52      | 4         | 0.11%   |
| 8       | 4         | 0.11%   |
| 46      | 3         | 0.08%   |
| 38      | 3         | 0.08%   |
| 37      | 3         | 0.08%   |
| 32      | 3         | 0.08%   |
| 142     | 2         | 0.06%   |
| 35      | 2         | 0.06%   |
| 28      | 2         | 0.06%   |
| 86      | 1         | 0.03%   |
| 65      | 1         | 0.03%   |
| 57      | 1         | 0.03%   |
| 48      | 1         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 2175      | 61.9%   |
| 201-300        | 428       | 12.18%  |
| 501-600        | 310       | 8.82%   |
| 351-400        | 238       | 6.77%   |
| 401-500        | 148       | 4.21%   |
| Unknown        | 41        | 1.17%   |
| 601-700        | 40        | 1.14%   |
| 701-800        | 35        | 1%      |
| 1-100          | 32        | 0.91%   |
| 1501-2000      | 25        | 0.71%   |
| 1001-1500      | 19        | 0.54%   |
| 801-900        | 16        | 0.46%   |
| 101-200        | 4         | 0.11%   |
| More than 2000 | 2         | 0.06%   |
| 901-1000       | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 2514      | 80.68%  |
| 16/10   | 402       | 12.9%   |
| 3/2     | 48        | 1.54%   |
| 21/9    | 33        | 1.06%   |
| 5/4     | 31        | 0.99%   |
| Unknown | 29        | 0.93%   |
| 0.67    | 25        | 0.8%    |
| 4/3     | 18        | 0.58%   |
| 6/5     | 7         | 0.22%   |
| 1.00    | 2         | 0.06%   |
| 0.56    | 2         | 0.06%   |
| 32/9    | 1         | 0.03%   |
| 1.03    | 1         | 0.03%   |
| 0.89    | 1         | 0.03%   |
| 0.65    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1700      | 48.05%  |
| 81-90          | 534       | 15.09%  |
| 201-250        | 272       | 7.69%   |
| 71-80          | 187       | 5.29%   |
| 121-130        | 135       | 3.82%   |
| 301-350        | 109       | 3.08%   |
| 351-500        | 67        | 1.89%   |
| 61-70          | 66        | 1.87%   |
| 151-200        | 63        | 1.78%   |
| 51-60          | 56        | 1.58%   |
| 41-50          | 52        | 1.47%   |
| More than 1000 | 43        | 1.22%   |
| Unknown        | 41        | 1.16%   |
| 131-140        | 38        | 1.07%   |
| 111-120        | 37        | 1.05%   |
| 1-40           | 36        | 1.02%   |
| 251-300        | 32        | 0.9%    |
| 141-150        | 32        | 0.9%    |
| 501-1000       | 20        | 0.57%   |
| 91-100         | 18        | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1269      | 36.57%  |
| 101-120       | 1092      | 31.47%  |
| 51-100        | 667       | 19.22%  |
| 161-240       | 272       | 7.84%   |
| More than 240 | 87        | 2.51%   |
| 1-50          | 42        | 1.21%   |
| Unknown       | 41        | 1.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2546      | 78.36%  |
| 2     | 513       | 15.79%  |
| 0     | 110       | 3.39%   |
| 3     | 73        | 2.25%   |
| 4     | 6         | 0.18%   |
| 5     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1770      | 34.67%  |
| Intel                             | 1515      | 29.67%  |
| Qualcomm Atheros                  | 754       | 14.77%  |
| Broadcom                          | 378       | 7.4%    |
| Broadcom Limited                  | 81        | 1.59%   |
| MediaTek                          | 79        | 1.55%   |
| Marvell Technology Group          | 76        | 1.49%   |
| Ralink                            | 54        | 1.06%   |
| TP-Link                           | 52        | 1.02%   |
| Ralink Technology                 | 40        | 0.78%   |
| ASIX Electronics                  | 34        | 0.67%   |
| Xiaomi                            | 25        | 0.49%   |
| Nvidia                            | 21        | 0.41%   |
| Samsung Electronics               | 18        | 0.35%   |
| Dell                              | 16        | 0.31%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.27%   |
| Lenovo                            | 14        | 0.27%   |
| JMicron Technology                | 14        | 0.27%   |
| Ericsson Business Mobile Networks | 14        | 0.27%   |
| Hewlett-Packard                   | 13        | 0.25%   |
| Sierra Wireless                   | 11        | 0.22%   |
| Qualcomm                          | 11        | 0.22%   |
| DisplayLink                       | 11        | 0.22%   |
| Qualcomm Atheros Communications   | 9         | 0.18%   |
| Huawei Technologies               | 8         | 0.16%   |
| D-Link                            | 7         | 0.14%   |
| VIA Technologies                  | 6         | 0.12%   |
| Edimax Technology                 | 5         | 0.1%    |
| ASUSTek Computer                  | 5         | 0.1%    |
| LSI                               | 4         | 0.08%   |
| Google                            | 4         | 0.08%   |
| Attansic Technology               | 4         | 0.08%   |
| Toshiba                           | 3         | 0.06%   |
| NetGear                           | 3         | 0.06%   |
| D-Link System                     | 3         | 0.06%   |
| Arduino SA                        | 3         | 0.06%   |
| Apple                             | 3         | 0.06%   |
| OPPO Electronics                  | 2         | 0.04%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.04%   |
| Microchip Technology              | 2         | 0.04%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1006      | 16.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 298       | 4.97%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 147       | 2.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 142       | 2.37%   |
| Intel Wi-Fi 6 AX200                                                     | 134       | 2.23%   |
| Intel Wi-Fi 6 AX201                                                     | 118       | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 113       | 1.88%   |
| Intel Wireless 8265 / 8275                                              | 110       | 1.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 109       | 1.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 106       | 1.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 106       | 1.77%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 90        | 1.5%    |
| Intel Wireless 7265                                                     | 86        | 1.43%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 83        | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 81        | 1.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 70        | 1.17%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 67        | 1.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 66        | 1.1%    |
| Intel Wireless 7260                                                     | 66        | 1.1%    |
| Intel Wireless 3165                                                     | 63        | 1.05%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 59        | 0.98%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 59        | 0.98%   |
| Broadcom BCM43142 802.11b/g/n                                           | 57        | 0.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 56        | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 51        | 0.85%   |
| Intel WiFi Link 5100                                                    | 49        | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 46        | 0.77%   |
| Intel Wireless 3160                                                     | 43        | 0.72%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 43        | 0.72%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 41        | 0.68%   |
| Intel Wireless 8260                                                     | 41        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 40        | 0.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 40        | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 38        | 0.63%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 36        | 0.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 35        | 0.58%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 31        | 0.52%   |
| ASIX AX88179 Gigabit Ethernet                                           | 31        | 0.52%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 30        | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 29        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1462      | 44.41%  |
| Qualcomm Atheros                  | 630       | 19.14%  |
| Realtek Semiconductor             | 607       | 18.44%  |
| Broadcom                          | 258       | 7.84%   |
| MediaTek                          | 76        | 2.31%   |
| Broadcom Limited                  | 56        | 1.7%    |
| Ralink                            | 54        | 1.64%   |
| Ralink Technology                 | 40        | 1.22%   |
| TP-Link                           | 34        | 1.03%   |
| Sierra Wireless                   | 11        | 0.33%   |
| Qualcomm Atheros Communications   | 9         | 0.27%   |
| Dell                              | 9         | 0.27%   |
| D-Link                            | 7         | 0.21%   |
| Qualcomm                          | 5         | 0.15%   |
| Edimax Technology                 | 5         | 0.15%   |
| ASUSTek Computer                  | 5         | 0.15%   |
| Hewlett-Packard                   | 4         | 0.12%   |
| Ericsson Business Mobile Networks | 4         | 0.12%   |
| NetGear                           | 3         | 0.09%   |
| D-Link System                     | 3         | 0.09%   |
| Fibocom                           | 2         | 0.06%   |
| Belkin Components                 | 2         | 0.06%   |
| Accton Technology                 | 2         | 0.06%   |
| Sitecom Europe                    | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| Gemtek                            | 1         | 0.03%   |
| AirTies Wireless Networks         | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 147       | 4.43%   |
| Intel Wi-Fi 6 AX200                                                     | 134       | 4.04%   |
| Intel Wi-Fi 6 AX201                                                     | 118       | 3.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 113       | 3.41%   |
| Intel Wireless 8265 / 8275                                              | 110       | 3.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 109       | 3.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 106       | 3.2%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 106       | 3.2%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 90        | 2.71%   |
| Intel Wireless 7265                                                     | 86        | 2.59%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 83        | 2.5%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 81        | 2.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 70        | 2.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 67        | 2.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 66        | 1.99%   |
| Intel Wireless 7260                                                     | 66        | 1.99%   |
| Intel Wireless 3165                                                     | 63        | 1.9%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 59        | 1.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 59        | 1.78%   |
| Broadcom BCM43142 802.11b/g/n                                           | 57        | 1.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 51        | 1.54%   |
| Intel WiFi Link 5100                                                    | 49        | 1.48%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 46        | 1.39%   |
| Intel Wireless 3160                                                     | 43        | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 43        | 1.3%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 41        | 1.24%   |
| Intel Wireless 8260                                                     | 41        | 1.24%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 40        | 1.21%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 40        | 1.21%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 38        | 1.15%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 31        | 0.94%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 30        | 0.9%    |
| Intel Centrino Advanced-N 6200                                          | 29        | 0.87%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 28        | 0.84%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 28        | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 28        | 0.84%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 26        | 0.78%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 26        | 0.78%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 25        | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 24        | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1496      | 57.67%  |
| Intel                                  | 402       | 15.5%   |
| Qualcomm Atheros                       | 206       | 7.94%   |
| Broadcom                               | 168       | 6.48%   |
| Marvell Technology Group               | 76        | 2.93%   |
| ASIX Electronics                       | 34        | 1.31%   |
| Broadcom Limited                       | 27        | 1.04%   |
| Xiaomi                                 | 25        | 0.96%   |
| Nvidia                                 | 21        | 0.81%   |
| TP-Link                                | 19        | 0.73%   |
| Samsung Electronics                    | 18        | 0.69%   |
| Silicon Integrated Systems [SiS]       | 14        | 0.54%   |
| Lenovo                                 | 14        | 0.54%   |
| JMicron Technology                     | 14        | 0.54%   |
| DisplayLink                            | 11        | 0.42%   |
| VIA Technologies                       | 6         | 0.23%   |
| Qualcomm                               | 6         | 0.23%   |
| Hewlett-Packard                        | 5         | 0.19%   |
| LSI                                    | 4         | 0.15%   |
| Huawei Technologies                    | 4         | 0.15%   |
| Google                                 | 4         | 0.15%   |
| Attansic Technology                    | 4         | 0.15%   |
| MediaTek                               | 3         | 0.12%   |
| Apple                                  | 3         | 0.12%   |
| OPPO Electronics                       | 2         | 0.08%   |
| Microchip Technology                   | 2         | 0.08%   |
| T & A Mobile Phones                    | 1         | 0.04%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.04%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.04%   |
| National Semiconductor                 | 1         | 0.04%   |
| Davicom Semiconductor                  | 1         | 0.04%   |
| ADMtek                                 | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1006      | 38.25%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 298       | 11.33%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 142       | 5.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 56        | 2.13%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 36        | 1.37%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 35        | 1.33%   |
| ASIX AX88179 Gigabit Ethernet                                     | 31        | 1.18%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 29        | 1.1%    |
| Intel 82577LM Gigabit Network Connection                          | 28        | 1.06%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 25        | 0.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 25        | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                             | 24        | 0.91%   |
| Intel Ethernet Connection I218-LM                                 | 23        | 0.87%   |
| Intel Ethernet Connection (3) I218-LM                             | 22        | 0.84%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 21        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 20        | 0.76%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 19        | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 19        | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 18        | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 17        | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 17        | 0.65%   |
| Intel Ethernet Connection (4) I219-V                              | 17        | 0.65%   |
| Intel Ethernet Connection (13) I219-V                             | 17        | 0.65%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 17        | 0.65%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 15        | 0.57%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 15        | 0.57%   |
| Nvidia MCP79 Ethernet                                             | 15        | 0.57%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 15        | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 15        | 0.57%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 15        | 0.57%   |
| Realtek RTL8125 2.5GbE Controller                                 | 14        | 0.53%   |
| Intel 82579V Gigabit Network Connection                           | 14        | 0.53%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 14        | 0.53%   |
| Intel Ethernet Connection I217-LM                                 | 13        | 0.49%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 12        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 12        | 0.46%   |
| Intel Ethernet Connection I219-V                                  | 12        | 0.46%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 12        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 3104      | 54.82%  |
| Ethernet | 2507      | 44.28%  |
| Modem    | 45        | 0.79%   |
| Unknown  | 6         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2533      | 75.66%  |
| Ethernet | 815       | 24.34%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 2233      | 70.49%  |
| 1     | 856       | 27.02%  |
| 0     | 63        | 1.99%   |
| 3     | 15        | 0.47%   |
| 4     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 3041      | 95.36%  |
| Yes  | 148       | 4.64%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1125      | 46.6%   |
| Realtek Semiconductor           | 298       | 12.34%  |
| IMC Networks                    | 192       | 7.95%   |
| Qualcomm Atheros Communications | 154       | 6.38%   |
| Foxconn / Hon Hai               | 108       | 4.47%   |
| Lite-On Technology              | 106       | 4.39%   |
| Broadcom                        | 97        | 4.02%   |
| Apple                           | 69        | 2.86%   |
| Realtek                         | 44        | 1.82%   |
| Toshiba                         | 41        | 1.7%    |
| Cambridge Silicon Radio         | 39        | 1.62%   |
| Dell                            | 28        | 1.16%   |
| Hewlett-Packard                 | 26        | 1.08%   |
| Ralink                          | 25        | 1.04%   |
| ASUSTek Computer                | 17        | 0.7%    |
| Alps Electric                   | 16        | 0.66%   |
| Foxconn International           | 11        | 0.46%   |
| Ralink Technology               | 4         | 0.17%   |
| MediaTek                        | 4         | 0.17%   |
| Askey Computer                  | 3         | 0.12%   |
| Taiyo Yuden                     | 2         | 0.08%   |
| Actions                         | 2         | 0.08%   |
| Opticis                         | 1         | 0.04%   |
| ISSC                            | 1         | 0.04%   |
| Chicony Electronics             | 1         | 0.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 404       | 16.74%  |
| Intel AX201 Bluetooth                               | 233       | 9.65%   |
| Realtek Bluetooth Radio                             | 207       | 8.57%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 202       | 8.37%   |
| Intel AX200 Bluetooth                               | 132       | 5.47%   |
| IMC Networks Bluetooth Radio                        | 99        | 4.1%    |
| Qualcomm Atheros  Bluetooth Device                  | 63        | 2.61%   |
| Intel Bluetooth Device                              | 61        | 2.53%   |
| Realtek  Bluetooth 4.2 Adapter                      | 58        | 2.4%    |
| Realtek Bluetooth Radio                             | 44        | 1.82%   |
| IMC Networks Bluetooth Device                       | 44        | 1.82%   |
| Foxconn / Hon Hai Bluetooth Device                  | 41        | 1.7%    |
| Apple Bluetooth Host Controller                     | 41        | 1.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 39        | 1.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 36        | 1.49%   |
| IMC Networks Wireless_Device                        | 33        | 1.37%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 30        | 1.24%   |
| Foxconn / Hon Hai Wireless_Device                   | 29        | 1.2%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 28        | 1.16%   |
| Intel AX210 Bluetooth                               | 28        | 1.16%   |
| Lite-On Atheros AR3012 Bluetooth                    | 27        | 1.12%   |
| Ralink RT3290 Bluetooth                             | 25        | 1.04%   |
| Lite-On Bluetooth Device                            | 25        | 1.04%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 24        | 0.99%   |
| Intel Wireless-AC 3168 Bluetooth                    | 22        | 0.91%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 19        | 0.79%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 0.79%   |
| Apple Bluetooth USB Host Controller                 | 18        | 0.75%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 16        | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                    | 14        | 0.58%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 0.58%   |
| Realtek RTL8723B Bluetooth                          | 12        | 0.5%    |
| Toshiba Integrated Bluetooth HCI                    | 11        | 0.46%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 11        | 0.46%   |
| Foxconn International BCM43142A0 Bluetooth module   | 11        | 0.46%   |
| Realtek RTL8821A Bluetooth                          | 10        | 0.41%   |
| Broadcom BCM2045 Bluetooth                          | 10        | 0.41%   |
| Alps Electric BCM2046 Bluetooth Device              | 10        | 0.41%   |
| Foxconn / Hon Hai BCM20702A0                        | 9         | 0.37%   |
| Dell DW375 Bluetooth Module                         | 9         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 2497      | 65.09%  |
| AMD                                  | 672       | 17.52%  |
| Nvidia                               | 445       | 11.6%   |
| C-Media Electronics                  | 26        | 0.68%   |
| Logitech                             | 20        | 0.52%   |
| Lenovo                               | 17        | 0.44%   |
| Silicon Integrated Systems [SiS]     | 14        | 0.36%   |
| Plantronics                          | 12        | 0.31%   |
| GN Netcom                            | 11        | 0.29%   |
| JMTek                                | 8         | 0.21%   |
| VIA Technologies                     | 7         | 0.18%   |
| Texas Instruments                    | 7         | 0.18%   |
| Realtek Semiconductor                | 7         | 0.18%   |
| Apple                                | 6         | 0.16%   |
| SteelSeries ApS                      | 5         | 0.13%   |
| Kingston Technology                  | 5         | 0.13%   |
| Generalplus Technology               | 5         | 0.13%   |
| ASUSTek Computer                     | 5         | 0.13%   |
| Hewlett-Packard                      | 4         | 0.1%    |
| Corsair                              | 4         | 0.1%    |
| BEHRINGER International              | 4         | 0.1%    |
| Sony                                 | 3         | 0.08%   |
| Sennheiser Communications            | 3         | 0.08%   |
| Creative Technology                  | 3         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.05%   |
| No brand                             | 2         | 0.05%   |
| Huawei Technologies                  | 2         | 0.05%   |
| Guillemot                            | 2         | 0.05%   |
| Conexant Systems                     | 2         | 0.05%   |
| CMX Systems                          | 2         | 0.05%   |
| Blue Microphones                     | 2         | 0.05%   |
| Alesis                               | 2         | 0.05%   |
| Vestax                               | 1         | 0.03%   |
| Veho                                 | 1         | 0.03%   |
| Trust                                | 1         | 0.03%   |
| ThrustMaster                         | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |
| Signalpath International             | 1         | 0.03%   |
| Samsung Electronics                  | 1         | 0.03%   |
| Razer USA                            | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 338       | 7.29%   |
| Intel Sunrise Point-LP HD Audio                                            | 316       | 6.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 181       | 3.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 164       | 3.54%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 162       | 3.49%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 161       | 3.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 146       | 3.15%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 142       | 3.06%   |
| Intel Haswell-ULT HD Audio Controller                                      | 141       | 3.04%   |
| Intel 8 Series HD Audio Controller                                         | 141       | 3.04%   |
| Intel Cannon Lake PCH cAVS                                                 | 137       | 2.96%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 110       | 2.37%   |
| Intel Comet Lake PCH-LP cAVS                                               | 108       | 2.33%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 102       | 2.2%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 101       | 2.18%   |
| Intel Broadwell-U Audio Controller                                         | 100       | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 95        | 2.05%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 90        | 1.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 86        | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 83        | 1.79%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 79        | 1.7%    |
| AMD FCH Azalia Controller                                                  | 79        | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 75        | 1.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 64        | 1.38%   |
| AMD Kabini HDMI/DP Audio                                                   | 63        | 1.36%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 57        | 1.23%   |
| Intel Comet Lake PCH cAVS                                                  | 54        | 1.16%   |
| AMD High Definition Audio Controller                                       | 54        | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 53        | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 48        | 1.04%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 47        | 1.01%   |
| Nvidia GA106 High Definition Audio Controller                              | 44        | 0.95%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 43        | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 42        | 0.91%   |
| Intel CM238 HD Audio Controller                                            | 41        | 0.88%   |
| Nvidia TU106 High Definition Audio Controller                              | 40        | 0.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 40        | 0.86%   |
| Nvidia Audio device                                                        | 39        | 0.84%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 33        | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                              | 32        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 603       | 30.52%  |
| SK hynix                                         | 426       | 21.56%  |
| Micron Technology                                | 254       | 12.85%  |
| Kingston                                         | 186       | 9.41%   |
| Unknown                                          | 139       | 7.03%   |
| Crucial                                          | 101       | 5.11%   |
| Ramaxel Technology                               | 62        | 3.14%   |
| Elpida                                           | 31        | 1.57%   |
| Unknown (ABCD)                                   | 28        | 1.42%   |
| A-DATA Technology                                | 24        | 1.21%   |
| Nanya Technology                                 | 19        | 0.96%   |
| Corsair                                          | 18        | 0.91%   |
| G.Skill                                          | 12        | 0.61%   |
| Silicon Power                                    | 10        | 0.51%   |
| Unknown                                          | 10        | 0.51%   |
| GOODRAM                                          | 6         | 0.3%    |
| Transcend                                        | 5         | 0.25%   |
| Wilk                                             | 3         | 0.15%   |
| Apacer                                           | 3         | 0.15%   |
| Toshiba                                          | 2         | 0.1%    |
| Timetec                                          | 2         | 0.1%    |
| SHARETRONIC                                      | 2         | 0.1%    |
| Patriot                                          | 2         | 0.1%    |
| KomputerBay                                      | 2         | 0.1%    |
| Kllisre                                          | 2         | 0.1%    |
| ChangXin Memory                                  | 2         | 0.1%    |
| Avant                                            | 2         | 0.1%    |
| Unknown (0x202020202020202020202020202020202020) | 1         | 0.05%   |
| Unifosa                                          | 1         | 0.05%   |
| Team                                             | 1         | 0.05%   |
| Qimonda                                          | 1         | 0.05%   |
| PUSKILL                                          | 1         | 0.05%   |
| PNY                                              | 1         | 0.05%   |
| Patriot Memory (PDP Systems)                     | 1         | 0.05%   |
| Netlist                                          | 1         | 0.05%   |
| Netac                                            | 1         | 0.05%   |
| Neo Forza                                        | 1         | 0.05%   |
| Micron/Elpida                                    | 1         | 0.05%   |
| Kembona                                          | 1         | 0.05%   |
| Goldkey                                          | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 36        | 1.75%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 34        | 1.65%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 26        | 1.26%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 24        | 1.16%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 24        | 1.16%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 22        | 1.07%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 22        | 1.07%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 22        | 1.07%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 19        | 0.92%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 19        | 0.92%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 18        | 0.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 18        | 0.87%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 18        | 0.87%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 17        | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 17        | 0.82%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 17        | 0.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 17        | 0.82%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 16        | 0.78%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 15        | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 15        | 0.73%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 14        | 0.68%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 14        | 0.68%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.68%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 14        | 0.68%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 13        | 0.63%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 0.63%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 13        | 0.63%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 12        | 0.58%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 0.58%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.58%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.58%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.58%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.58%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 12        | 0.58%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 12        | 0.58%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 11        | 0.53%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 10        | 0.48%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.48%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 10        | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 832       | 49.55%  |
| DDR3    | 496       | 29.54%  |
| DDR2    | 96        | 5.72%   |
| LPDDR4  | 91        | 5.42%   |
| LPDDR3  | 57        | 3.39%   |
| SDRAM   | 36        | 2.14%   |
| DDR5    | 31        | 1.85%   |
| LPDDR5  | 15        | 0.89%   |
| Unknown | 11        | 0.66%   |
| DDR     | 8         | 0.48%   |
| DRAM    | 6         | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 1494      | 87.99%  |
| Row Of Chips    | 182       | 10.72%  |
| DIMM            | 10        | 0.59%   |
| Chip            | 9         | 0.53%   |
| Unknown         | 2         | 0.12%   |
| Proprietary Car | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 752       | 41.14%  |
| 4096  | 476       | 26.04%  |
| 16384 | 285       | 15.59%  |
| 2048  | 202       | 11.05%  |
| 1024  | 64        | 3.5%    |
| 32768 | 39        | 2.13%   |
| 512   | 6         | 0.33%   |
| 256   | 3         | 0.16%   |
| 3072  | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 378       | 21.01%  |
| 2667    | 370       | 20.57%  |
| 1600    | 333       | 18.51%  |
| 2400    | 114       | 6.34%   |
| 1334    | 86        | 4.78%   |
| 2133    | 78        | 4.34%   |
| 667     | 66        | 3.67%   |
| 1333    | 58        | 3.22%   |
| Unknown | 42        | 2.33%   |
| 8400    | 34        | 1.89%   |
| 4800    | 31        | 1.72%   |
| 4267    | 31        | 1.72%   |
| 1067    | 26        | 1.45%   |
| 1867    | 19        | 1.06%   |
| 800     | 19        | 1.06%   |
| 3266    | 18        | 1%      |
| 6400    | 16        | 0.89%   |
| 2048    | 14        | 0.78%   |
| 533     | 12        | 0.67%   |
| 4199    | 11        | 0.61%   |
| 4266    | 9         | 0.5%    |
| 1066    | 9         | 0.5%    |
| 975     | 7         | 0.39%   |
| 3733    | 3         | 0.17%   |
| 5600    | 2         | 0.11%   |
| 2933    | 2         | 0.11%   |
| 1639    | 2         | 0.11%   |
| 1200    | 2         | 0.11%   |
| 3600    | 1         | 0.06%   |
| 3000    | 1         | 0.06%   |
| 1866    | 1         | 0.06%   |
| 1776    | 1         | 0.06%   |
| 666     | 1         | 0.06%   |
| 333     | 1         | 0.06%   |
| 266     | 1         | 0.06%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 16        | 55.17%  |
| Brother Industries | 5         | 17.24%  |
| Seiko Epson        | 4         | 13.79%  |
| Canon              | 4         | 13.79%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Canon PIXMA MG2500 Series        | 3         | 10.34%  |
| HP Printing Support              | 2         | 6.9%    |
| HP DeskJet 2600 series           | 2         | 6.9%    |
| Seiko Epson XP-235 Series        | 1         | 3.45%   |
| Seiko Epson Printer              | 1         | 3.45%   |
| Seiko Epson L555 Series          | 1         | 3.45%   |
| Seiko Epson ET-2700 Series       | 1         | 3.45%   |
| HP PSC 1500 series               | 1         | 3.45%   |
| HP Officejet 7110 series         | 1         | 3.45%   |
| HP LaserJet Professional P 1102w | 1         | 3.45%   |
| HP LaserJet Pro M404-M405        | 1         | 3.45%   |
| HP LaserJet M14-M17              | 1         | 3.45%   |
| HP LaserJet 1320                 | 1         | 3.45%   |
| HP LaserJet 1020                 | 1         | 3.45%   |
| HP LaserJet 1018                 | 1         | 3.45%   |
| HP LaserJet 1000                 | 1         | 3.45%   |
| HP DeskJet F300 series           | 1         | 3.45%   |
| HP DeskJet F2492 All-in-One      | 1         | 3.45%   |
| HP Deskjet 2050 J510             | 1         | 3.45%   |
| Canon TS3100 series              | 1         | 3.45%   |
| Brother MFC-J5330DW              | 1         | 3.45%   |
| Brother HL-L3270CDW series       | 1         | 3.45%   |
| Brother HL-2030 Laser Printer    | 1         | 3.45%   |
| Brother HL-1210W series          | 1         | 3.45%   |
| Brother DCP-L2520DW              | 1         | 3.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 3         | 75%     |
| Hewlett-Packard | 1         | 25%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan LiDE 210       | 2         | 50%     |
| HP ScanJet 4300c              | 1         | 25%     |
| Canon CanoScan N1240U/LiDE 30 | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 687       | 25.29%  |
| IMC Networks                           | 339       | 12.48%  |
| Bison Electronics                      | 239       | 8.8%    |
| Microdia                               | 185       | 6.81%   |
| Realtek Semiconductor                  | 170       | 6.26%   |
| Quanta                                 | 146       | 5.37%   |
| Suyin                                  | 127       | 4.67%   |
| Sunplus Innovation Technology          | 116       | 4.27%   |
| Cheng Uei Precision Industry (Foxlink) | 107       | 3.94%   |
| Syntek                                 | 80        | 2.94%   |
| Acer                                   | 57        | 2.1%    |
| Alcor Micro                            | 50        | 1.84%   |
| Apple                                  | 48        | 1.77%   |
| Luxvisions Innotech Limited            | 43        | 1.58%   |
| Lite-On Technology                     | 43        | 1.58%   |
| Ricoh                                  | 34        | 1.25%   |
| Logitech                               | 29        | 1.07%   |
| Silicon Motion                         | 24        | 0.88%   |
| Sonix Technology                       | 22        | 0.81%   |
| Samsung Electronics                    | 15        | 0.55%   |
| Importek                               | 12        | 0.44%   |
| icSpring                               | 12        | 0.44%   |
| Lenovo                                 | 10        | 0.37%   |
| ALi                                    | 10        | 0.37%   |
| Z-Star Microelectronics                | 9         | 0.33%   |
| GEMBIRD                                | 8         | 0.29%   |
| Sunplus Technology                     | 7         | 0.26%   |
| Primax Electronics                     | 7         | 0.26%   |
| Intel                                  | 7         | 0.26%   |
| DigiTech                               | 7         | 0.26%   |
| OmniVision Technologies                | 5         | 0.18%   |
| KYE Systems (Mouse Systems)            | 5         | 0.18%   |
| Genesys Logic                          | 5         | 0.18%   |
| ARC International                      | 4         | 0.15%   |
| Trust                                  | 3         | 0.11%   |
| Generalplus Technology                 | 3         | 0.11%   |
| Creative Technology                    | 3         | 0.11%   |
| 8SSC20F27114V1SR0BK1X4S                | 3         | 0.11%   |
| SunplusIT                              | 2         | 0.07%   |
| ShineTech                              | 2         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 91        | 3.34%   |
| Chicony HD Webcam                                   | 78        | 2.86%   |
| Chicony Integrated Camera                           | 76        | 2.79%   |
| Microdia Integrated_Webcam_HD                       | 75        | 2.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 71        | 2.6%    |
| Bison HD Webcam                                     | 71        | 2.6%    |
| IMC Networks Integrated Camera                      | 59        | 2.16%   |
| Chicony USB2.0 VGA UVC WebCam                       | 44        | 1.61%   |
| Bison Integrated Camera                             | 40        | 1.47%   |
| Sunplus HD WebCam                                   | 36        | 1.32%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 34        | 1.25%   |
| Realtek Integrated_Webcam_HD                        | 33        | 1.21%   |
| Quanta HP TrueVision HD Camera                      | 33        | 1.21%   |
| Chicony TOSHIBA Web Camera - HD                     | 29        | 1.06%   |
| Realtek USB Camera                                  | 28        | 1.03%   |
| Syntek Integrated Camera                            | 27        | 0.99%   |
| Chicony EasyCamera                                  | 26        | 0.95%   |
| Acer Integrated Camera                              | 26        | 0.95%   |
| Chicony USB 2.0 Camera                              | 25        | 0.92%   |
| Chicony USB2.0 HD UVC WebCam                        | 23        | 0.84%   |
| Chicony USB2.0 Camera                               | 23        | 0.84%   |
| Chicony HP TrueVision HD Camera                     | 21        | 0.77%   |
| Chicony HP TrueVision HD                            | 21        | 0.77%   |
| Bison Lenovo EasyCamera                             | 21        | 0.77%   |
| Realtek Lenovo EasyCamera                           | 20        | 0.73%   |
| Microdia Webcam Vitade AF                           | 20        | 0.73%   |
| IMC Networks ov9734_azurewave_camera                | 20        | 0.73%   |
| Bison EasyCamera                                    | 20        | 0.73%   |
| Syntek Lenovo EasyCamera                            | 19        | 0.7%    |
| Syntek EasyCamera                                   | 19        | 0.7%    |
| Sonix USB2.0 HD UVC WebCam                          | 19        | 0.7%    |
| Alcor Micro USB 2.0 Camera                          | 19        | 0.7%    |
| Lite-On Integrated Camera                           | 18        | 0.66%   |
| Chicony VGA Webcam                                  | 18        | 0.66%   |
| Chicony Integrated Camera (1280x720@30)             | 18        | 0.66%   |
| Apple Built-in iSight                               | 18        | 0.66%   |
| Sunplus Integrated_Webcam_HD                        | 17        | 0.62%   |
| Quanta HP Wide Vision HD Camera                     | 17        | 0.62%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 17        | 0.62%   |
| Chicony HP HD Camera                                | 17        | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 125       | 28.54%  |
| Validity Sensors                   | 104       | 23.74%  |
| Shenzhen Goodix Technology         | 79        | 18.04%  |
| AuthenTec                          | 43        | 9.82%   |
| Elan Microelectronics              | 41        | 9.36%   |
| Upek                               | 27        | 6.16%   |
| LighTuning Technology              | 11        | 2.51%   |
| STMicroelectronics                 | 7         | 1.6%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.23%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 61        | 13.93%  |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 43        | 9.82%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 35        | 7.99%   |
| Elan ELAN:Fingerprint                                                      | 35        | 7.99%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 22        | 5.02%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 4.79%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 16        | 3.65%   |
| Shenzhen Goodix Fingerprint Reader                                         | 14        | 3.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 2.97%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 12        | 2.74%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.05%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 2.05%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 1.83%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 1.83%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 1.83%   |
| AuthenTec AES1600                                                          | 8         | 1.83%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 7         | 1.6%    |
| STMicroelectronics Fingerprint Reader                                      | 7         | 1.6%    |
| Validity Sensors VFS491                                                    | 6         | 1.37%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 1.37%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.37%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 1.37%   |
| Elan ELAN:ARM-M4                                                           | 6         | 1.37%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 6         | 1.37%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.14%   |
| Upek TCS5B Fingerprint sensor                                              | 5         | 1.14%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.14%   |
| AuthenTec AES2810                                                          | 5         | 1.14%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 0.91%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 0.91%   |
| Synaptics UWP WBDI Device                                                  | 4         | 0.91%   |
| Synaptics  WBDI                                                            | 4         | 0.91%   |
| Synaptics Fingerprint reader [HP G6]                                       | 4         | 0.91%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 0.91%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 0.91%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.91%   |
| Synaptics WBDI                                                             | 3         | 0.68%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.46%   |
| Synaptics TouchPad                                                         | 2         | 0.46%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.46%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 68        | 36.76%  |
| Broadcom              | 60        | 32.43%  |
| O2 Micro              | 25        | 13.51%  |
| Lenovo                | 10        | 5.41%   |
| Upek                  | 5         | 2.7%    |
| Cherry                | 4         | 2.16%   |
| C3PO                  | 4         | 2.16%   |
| Realtek Semiconductor | 3         | 1.62%   |
| Gemalto (was Gemplus) | 3         | 1.62%   |
| In Focus Systems      | 1         | 0.54%   |
| Chicony Electronics   | 1         | 0.54%   |
| Advanced Card Systems | 1         | 0.54%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 68        | 36.76%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 12.97%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 10.81%  |
| Broadcom 5880                                                                | 17        | 9.19%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 5.95%   |
| Broadcom 58200                                                               | 11        | 5.95%   |
| Lenovo Integrated Smart Card Reader                                          | 10        | 5.41%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 2.7%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 1.62%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.62%   |
| Cherry SmartTerminal XX1X                                                    | 3         | 1.62%   |
| C3PO LTC31v2                                                                 | 3         | 1.62%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.54%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.54%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.54%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.54%   |
| C3PO USB SMART CARD READER                                                   | 1         | 0.54%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 0.54%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.54%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 2082      | 63.94%  |
| 1     | 896       | 27.52%  |
| 2     | 224       | 6.88%   |
| 3     | 36        | 1.11%   |
| 4     | 10        | 0.31%   |
| 5     | 5         | 0.15%   |
| 6     | 2         | 0.06%   |
| 8     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 428       | 29.25%  |
| Graphics card            | 355       | 24.27%  |
| Net/wireless             | 188       | 12.85%  |
| Chipcard                 | 161       | 11%     |
| Multimedia controller    | 95        | 6.49%   |
| Camera                   | 54        | 3.69%   |
| Bluetooth                | 43        | 2.94%   |
| Storage                  | 30        | 2.05%   |
| Communication controller | 25        | 1.71%   |
| Card reader              | 21        | 1.44%   |
| Sound                    | 16        | 1.09%   |
| Net/ethernet             | 13        | 0.89%   |
| Flash memory             | 11        | 0.75%   |
| Modem                    | 9         | 0.62%   |
| Network                  | 8         | 0.55%   |
| Dvb card                 | 4         | 0.27%   |
| Storage/raid             | 1         | 0.07%   |
| Storage/ide              | 1         | 0.07%   |

