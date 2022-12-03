Zorin - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for Zorin.

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

Total: 3408

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire V5-121               | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| Sony          | VPCEB1M1E                   | [988c78f70d](https://linux-hardware.org/?probe=988c78f70d) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| Dell          | Latitude E5520              | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| Dell          | Studio 1558                 | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| MSI           | GE75 Raider 10SE            | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| Dell          | Latitude E6540              | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| Dell          | System XPS L502X            | [bd45da46bc](https://linux-hardware.org/?probe=bd45da46bc) | Nov 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNP           | [3dd83d6d9d](https://linux-hardware.org/?probe=3dd83d6d9d) | Nov 27, 2022 |
| Dell          | XPS 15 9560                 | [47782768eb](https://linux-hardware.org/?probe=47782768eb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| HP            | Pavilion g6                 | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| Dell          | Studio 1558                 | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | [c26e52327e](https://linux-hardware.org/?probe=c26e52327e) | Nov 26, 2022 |
| Dell          | Latitude E6540              | [543ca1307c](https://linux-hardware.org/?probe=543ca1307c) | Nov 26, 2022 |
| ASUSTek       | X202E                       | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Toshiba       | Satellite C50D-B            | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [1ed724b75e](https://linux-hardware.org/?probe=1ed724b75e) | Nov 25, 2022 |
| HP            | ENVY m6                     | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| Dell          | XPS 15 9510                 | [2c7485441f](https://linux-hardware.org/?probe=2c7485441f) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| Samsung       | 600B4B/600B5B               | [6cbdda4e27](https://linux-hardware.org/?probe=6cbdda4e27) | Nov 24, 2022 |
| Thomson       | GEN17V3C8WH256              | [7b1a510e2e](https://linux-hardware.org/?probe=7b1a510e2e) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| Toshiba       | Satellite S55t-B            | [4b01021314](https://linux-hardware.org/?probe=4b01021314) | Nov 24, 2022 |
| HP            | Notebook                    | [d65b0a06fe](https://linux-hardware.org/?probe=d65b0a06fe) | Nov 24, 2022 |
| HP            | Notebook                    | [54b351457e](https://linux-hardware.org/?probe=54b351457e) | Nov 24, 2022 |
| HP            | 15                          | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| Lenovo        | IdeaPad U400 09932JU        | [cb5d9871d0](https://linux-hardware.org/?probe=cb5d9871d0) | Nov 22, 2022 |
| Apple         | MacBookPro5,4               | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| Apple         | MacBookPro8,1               | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Framework     | Laptop                      | [6cc495c0d9](https://linux-hardware.org/?probe=6cc495c0d9) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [77dcd3bef6](https://linux-hardware.org/?probe=77dcd3bef6) | Nov 19, 2022 |
| GPU Compan... | GWTN156-2BK                 | [a7c034bd91](https://linux-hardware.org/?probe=a7c034bd91) | Nov 19, 2022 |
| Dell          | Latitude E6540              | [4148292f4d](https://linux-hardware.org/?probe=4148292f4d) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [0185c349b9](https://linux-hardware.org/?probe=0185c349b9) | Nov 18, 2022 |
| HP            | 14                          | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | [6992e11b21](https://linux-hardware.org/?probe=6992e11b21) | Nov 18, 2022 |
| Dell          | Latitude E6540              | [31752fdaa8](https://linux-hardware.org/?probe=31752fdaa8) | Nov 18, 2022 |
| HP            | 14                          | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| Unknown       | Unknown                     | [ef7af01d47](https://linux-hardware.org/?probe=ef7af01d47) | Nov 18, 2022 |
| Unknown       | Unknown                     | [ceca708c95](https://linux-hardware.org/?probe=ceca708c95) | Nov 18, 2022 |
| HP            | EliteBook 8470p             | [f324f5bc16](https://linux-hardware.org/?probe=f324f5bc16) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| ASUSTek       | ASUS Gaming FX570UD         | [522c9222c5](https://linux-hardware.org/?probe=522c9222c5) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [23f8c23e8b](https://linux-hardware.org/?probe=23f8c23e8b) | Nov 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [545eb5e46c](https://linux-hardware.org/?probe=545eb5e46c) | Nov 16, 2022 |
| Gateway       | NV59C                       | [b3be978b72](https://linux-hardware.org/?probe=b3be978b72) | Nov 16, 2022 |
| Dell          | Inspiron 3543               | [15cc03ec87](https://linux-hardware.org/?probe=15cc03ec87) | Nov 16, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [733e52cbdb](https://linux-hardware.org/?probe=733e52cbdb) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | [b240ae5338](https://linux-hardware.org/?probe=b240ae5338) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | [d1049db1fb](https://linux-hardware.org/?probe=d1049db1fb) | Nov 15, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [73bc7e7428](https://linux-hardware.org/?probe=73bc7e7428) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [9d798077df](https://linux-hardware.org/?probe=9d798077df) | Nov 14, 2022 |
| ALURIN        | PR1-M146                    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Microtech     | ebookLite                   | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| Acer          | Extensa 2530                | [ac83b4e3e9](https://linux-hardware.org/?probe=ac83b4e3e9) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| Hampoo        | Cherry Trail CR             | [ae8d0b2d8e](https://linux-hardware.org/?probe=ae8d0b2d8e) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| HP            | 250 G4                      | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| HP            | 250 G4                      | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| Microtech     | ebookLite                   | [9c3039fa75](https://linux-hardware.org/?probe=9c3039fa75) | Nov 12, 2022 |
| Fujitsu       | STYLISTIC Q572              | [afd0e0efc4](https://linux-hardware.org/?probe=afd0e0efc4) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| HP            | Pavilion Notebook           | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [2e79d44f43](https://linux-hardware.org/?probe=2e79d44f43) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | [1f9e0a7e16](https://linux-hardware.org/?probe=1f9e0a7e16) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | [d3a6ca47df](https://linux-hardware.org/?probe=d3a6ca47df) | Nov 11, 2022 |
| HP            | 2000                        | [5045f21cc3](https://linux-hardware.org/?probe=5045f21cc3) | Nov 10, 2022 |
| Microtech     | ebookLite                   | [63f80f900a](https://linux-hardware.org/?probe=63f80f900a) | Nov 10, 2022 |
| ASUSTek       | G50VT                       | [57f7e69b18](https://linux-hardware.org/?probe=57f7e69b18) | Nov 10, 2022 |
| HP            | Pavilion Notebook           | [150409691d](https://linux-hardware.org/?probe=150409691d) | Nov 09, 2022 |
| HP            | ProBook 430 G4              | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| GPU Compan... | GWTN156-2BK                 | [cf64038190](https://linux-hardware.org/?probe=cf64038190) | Nov 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c17772f8e7](https://linux-hardware.org/?probe=c17772f8e7) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| HP            | ProBook 430 G4              | [5d6f34affd](https://linux-hardware.org/?probe=5d6f34affd) | Nov 08, 2022 |
| Gateway       | ML6732                      | [7889349228](https://linux-hardware.org/?probe=7889349228) | Nov 08, 2022 |
| Dell          | Latitude E5420              | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5285abf94f](https://linux-hardware.org/?probe=5285abf94f) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [5cfd9a145a](https://linux-hardware.org/?probe=5cfd9a145a) | Nov 08, 2022 |
| Linx          | LINX1010B                   | [fa6d1ebd57](https://linux-hardware.org/?probe=fa6d1ebd57) | Nov 07, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [185c483599](https://linux-hardware.org/?probe=185c483599) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| ASUSTek       | U36SD                       | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| ASUSTek       | F5V                         | [877e968b61](https://linux-hardware.org/?probe=877e968b61) | Nov 07, 2022 |
| HP            | 240 G8                      | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [e44a807758](https://linux-hardware.org/?probe=e44a807758) | Nov 06, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [d763771ba6](https://linux-hardware.org/?probe=d763771ba6) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Quanta        | TW8/SW8/DW8                 | [31caaec976](https://linux-hardware.org/?probe=31caaec976) | Nov 05, 2022 |
| ASUSTek       | T200TAC                     | [e14cb334c4](https://linux-hardware.org/?probe=e14cb334c4) | Nov 05, 2022 |
| Dell          | Inspiron N5010              | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| Lenovo        | G40-30 80FY                 | [2313029c70](https://linux-hardware.org/?probe=2313029c70) | Nov 04, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| BANGHO        | W240HU/W250HUQ              | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [c796c2f9ee](https://linux-hardware.org/?probe=c796c2f9ee) | Nov 03, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [30cd9b0d29](https://linux-hardware.org/?probe=30cd9b0d29) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| Microtech     | CoreBook                    | [1276c24890](https://linux-hardware.org/?probe=1276c24890) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| Dell          | Latitude E6540              | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [56767f430b](https://linux-hardware.org/?probe=56767f430b) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | [b1ffa94d76](https://linux-hardware.org/?probe=b1ffa94d76) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [7c6ddf22b5](https://linux-hardware.org/?probe=7c6ddf22b5) | Nov 02, 2022 |
| GPU Compan... | GWTN156-2BK                 | [a7fb2c2163](https://linux-hardware.org/?probe=a7fb2c2163) | Nov 02, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [005b25ef06](https://linux-hardware.org/?probe=005b25ef06) | Nov 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| HP            | Pavilion 15                 | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| GPU Compan... | GWTN156-2BK                 | [99ab599fbc](https://linux-hardware.org/?probe=99ab599fbc) | Nov 01, 2022 |
| Dell          | Latitude E6500              | [b7be8c3204](https://linux-hardware.org/?probe=b7be8c3204) | Oct 31, 2022 |
| Dell          | Latitude E6500              | [cb3b467ba8](https://linux-hardware.org/?probe=cb3b467ba8) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| HP            | 2000                        | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [34727cd696](https://linux-hardware.org/?probe=34727cd696) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Packard Be... | EasyNote TE69KB             | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [50170811fd](https://linux-hardware.org/?probe=50170811fd) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [d8f6faad10](https://linux-hardware.org/?probe=d8f6faad10) | Oct 30, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [75dcd27c77](https://linux-hardware.org/?probe=75dcd27c77) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | [6c3a410233](https://linux-hardware.org/?probe=6c3a410233) | Oct 30, 2022 |
| Dell          | Inspiron 5537               | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| Dell          | Inspiron N5050              | [f844544154](https://linux-hardware.org/?probe=f844544154) | Oct 30, 2022 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [861aaf5a99](https://linux-hardware.org/?probe=861aaf5a99) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Acer          | Extensa 5635ZG              | [8c0a7c0aa1](https://linux-hardware.org/?probe=8c0a7c0aa1) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| Phoenix/Si... | M7x0S                       | [8b27fc5eb3](https://linux-hardware.org/?probe=8b27fc5eb3) | Oct 29, 2022 |
| Dell          | Latitude E6530              | [cdd3b5ce40](https://linux-hardware.org/?probe=cdd3b5ce40) | Oct 28, 2022 |
| HP            | Presario V6000 (RV053UA#... | [ca121e3727](https://linux-hardware.org/?probe=ca121e3727) | Oct 28, 2022 |
| HP            | OMEN Notebook PC 15         | [fea0167027](https://linux-hardware.org/?probe=fea0167027) | Oct 28, 2022 |
| Packard Be... | EasyNote MH45               | [b9aa4cc6d5](https://linux-hardware.org/?probe=b9aa4cc6d5) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| Acer          | Aspire 5720Z                | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | [58e18764cb](https://linux-hardware.org/?probe=58e18764cb) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | [06274bdff6](https://linux-hardware.org/?probe=06274bdff6) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [80c2aeb241](https://linux-hardware.org/?probe=80c2aeb241) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| Dell          | Latitude E6510              | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ALURIN        | PR1-M146                    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Dell          | Inspiron 1525               | [742bf13a9f](https://linux-hardware.org/?probe=742bf13a9f) | Oct 25, 2022 |
| MSI           | GT70 2PE                    | [26d9f8ba04](https://linux-hardware.org/?probe=26d9f8ba04) | Oct 25, 2022 |
| Toshiba       | K201                        | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| MSI           | GE62 7RE                    | [bd5b8943f4](https://linux-hardware.org/?probe=bd5b8943f4) | Oct 24, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| Lenovo        | ThinkPad T520 4243PN7       | [fdca71510b](https://linux-hardware.org/?probe=fdca71510b) | Oct 24, 2022 |
| Lenovo        | G50-45 80MQ                 | [2628815c23](https://linux-hardware.org/?probe=2628815c23) | Oct 24, 2022 |
| Apple         | MacBookPro8,2               | [200f2ac48e](https://linux-hardware.org/?probe=200f2ac48e) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| Alienware     | 18                          | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| Chuwi         | HeroBook Air                | [055a6c2be8](https://linux-hardware.org/?probe=055a6c2be8) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | [cb299f8f1b](https://linux-hardware.org/?probe=cb299f8f1b) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| AMI           | Unknown                     | [337d94fb96](https://linux-hardware.org/?probe=337d94fb96) | Oct 23, 2022 |
| ASUSTek       | X510UQ                      | [6d976f6f96](https://linux-hardware.org/?probe=6d976f6f96) | Oct 23, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [a8a9cdfabc](https://linux-hardware.org/?probe=a8a9cdfabc) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | [d82378ea41](https://linux-hardware.org/?probe=d82378ea41) | Oct 22, 2022 |
| Acer          | Aspire E5-411               | [f4fa3fce70](https://linux-hardware.org/?probe=f4fa3fce70) | Oct 22, 2022 |
| HP            | EliteBook 755 G5            | [b1550ee8e1](https://linux-hardware.org/?probe=b1550ee8e1) | Oct 22, 2022 |
| Dell          | Studio 1558                 | [ac449d0411](https://linux-hardware.org/?probe=ac449d0411) | Oct 21, 2022 |
| HP            | Stream Notebook             | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Acer          | Predator PH517-61           | [e30217884a](https://linux-hardware.org/?probe=e30217884a) | Oct 21, 2022 |
| Dell          | Vostro V13                  | [c7cd7a2ddf](https://linux-hardware.org/?probe=c7cd7a2ddf) | Oct 21, 2022 |
| Dell          | Vostro V13                  | [43eb559763](https://linux-hardware.org/?probe=43eb559763) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire A315-33              | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| ASUSTek       | T200TAC                     | [0aad9d8ecd](https://linux-hardware.org/?probe=0aad9d8ecd) | Oct 20, 2022 |
| HP            | G62                         | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| Microtech     | CoreBook                    | [0592b30e41](https://linux-hardware.org/?probe=0592b30e41) | Oct 19, 2022 |
| Microtech     | CoreBook                    | [536451ed8a](https://linux-hardware.org/?probe=536451ed8a) | Oct 19, 2022 |
| Dell          | Studio 1458                 | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| Dell          | Vostro 3500                 | [5d1bb5d8aa](https://linux-hardware.org/?probe=5d1bb5d8aa) | Oct 19, 2022 |
| ASUSTek       | T200TAC                     | [c33c750766](https://linux-hardware.org/?probe=c33c750766) | Oct 18, 2022 |
| HP            | Notebook                    | [01692e8f30](https://linux-hardware.org/?probe=01692e8f30) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ff6d42a3ef](https://linux-hardware.org/?probe=ff6d42a3ef) | Oct 17, 2022 |
| Acer          | Aspire E5-411               | [01979e17ce](https://linux-hardware.org/?probe=01979e17ce) | Oct 17, 2022 |
| HP            | Laptop 15-db0xxx            | [4b0c3a6022](https://linux-hardware.org/?probe=4b0c3a6022) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [f188526e04](https://linux-hardware.org/?probe=f188526e04) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Apple         | MacBookPro5,4               | [bc6696e1d5](https://linux-hardware.org/?probe=bc6696e1d5) | Oct 17, 2022 |
| Toshiba       | Satellite C55-A             | [f93fb31ad5](https://linux-hardware.org/?probe=f93fb31ad5) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| Google        | Lars                        | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HUAWEI        | KLVD-WXX9                   | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [772645390a](https://linux-hardware.org/?probe=772645390a) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | [7e770fd62b](https://linux-hardware.org/?probe=7e770fd62b) | Oct 14, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| Chuwi         | HeroBook Pro                | [4fe76d84fd](https://linux-hardware.org/?probe=4fe76d84fd) | Oct 13, 2022 |
| Dell          | Vostro 3558                 | [855e0d050c](https://linux-hardware.org/?probe=855e0d050c) | Oct 13, 2022 |
| Dell          | Latitude E6330              | [815d48ffba](https://linux-hardware.org/?probe=815d48ffba) | Oct 12, 2022 |
| Dell          | Latitude E6410              | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| TERRA         | TERRAPC                     | [048f3ad5ef](https://linux-hardware.org/?probe=048f3ad5ef) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| Acer          | Aspire A315-33              | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | [f6e7e1585c](https://linux-hardware.org/?probe=f6e7e1585c) | Oct 10, 2022 |
| Lenovo        | G500 20236                  | [897321f579](https://linux-hardware.org/?probe=897321f579) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Packard Be... | EasyNote TM82               | [8e3ecfd03d](https://linux-hardware.org/?probe=8e3ecfd03d) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Dell          | Inspiron 3521               | [0b225367b8](https://linux-hardware.org/?probe=0b225367b8) | Oct 08, 2022 |
| Dell          | Latitude E6410              | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [46b44504df](https://linux-hardware.org/?probe=46b44504df) | Oct 08, 2022 |
| AXDIA Inte... | WINBOOK 13                  | [35638411ee](https://linux-hardware.org/?probe=35638411ee) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK LH531              | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| Dell          | Inspiron 1200               | [45c46e1b91](https://linux-hardware.org/?probe=45c46e1b91) | Oct 08, 2022 |
| HP            | ZBook 17 G5                 | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| TERRA         | TERRAPC                     | [ec9068f7ea](https://linux-hardware.org/?probe=ec9068f7ea) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Toshiba       | Satellite L500              | [29c7a43356](https://linux-hardware.org/?probe=29c7a43356) | Oct 06, 2022 |
| Dell          | Vostro 2520                 | [da789d3a06](https://linux-hardware.org/?probe=da789d3a06) | Oct 06, 2022 |
| Dell          | Latitude E6500              | [84fa5b35ed](https://linux-hardware.org/?probe=84fa5b35ed) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| HP            | EliteBook 840 G6            | [397e5be75c](https://linux-hardware.org/?probe=397e5be75c) | Oct 05, 2022 |
| Dell          | Inspiron 3521               | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [9b8dc565f9](https://linux-hardware.org/?probe=9b8dc565f9) | Oct 04, 2022 |
| Gigabyte      | AORUS 7 SB                  | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| HP            | ENVY m6                     | [5c828496a7](https://linux-hardware.org/?probe=5c828496a7) | Oct 04, 2022 |
| Google        | Careena                     | [7ac4802a10](https://linux-hardware.org/?probe=7ac4802a10) | Oct 04, 2022 |
| Acer          | Extensa 2530                | [684b31b41d](https://linux-hardware.org/?probe=684b31b41d) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [d3bcd51be1](https://linux-hardware.org/?probe=d3bcd51be1) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| Lenovo        | V570 1066EDG                | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [dc7e0ada81](https://linux-hardware.org/?probe=dc7e0ada81) | Oct 01, 2022 |
| Acer          | Aspire 4733Z                | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Apple         | MacBookPro8,1               | [f42501fcc3](https://linux-hardware.org/?probe=f42501fcc3) | Oct 01, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Notebook      | NJ50GU                      | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Irbis         | NB61 WS001                  | [3fda78e356](https://linux-hardware.org/?probe=3fda78e356) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| Dell          | Inspiron 1200               | [32dd972d77](https://linux-hardware.org/?probe=32dd972d77) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | [01ebd7e70b](https://linux-hardware.org/?probe=01ebd7e70b) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | [d2c06711d7](https://linux-hardware.org/?probe=d2c06711d7) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Dell          | Inspiron 3582               | [8cd21b783a](https://linux-hardware.org/?probe=8cd21b783a) | Sep 28, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| Dell          | Inspiron 5559               | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
| Dell          | Latitude E6520              | [e228fa6546](https://linux-hardware.org/?probe=e228fa6546) | Sep 28, 2022 |
| Toshiba       | Satellite L855              | [19e5b180eb](https://linux-hardware.org/?probe=19e5b180eb) | Sep 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [f501591d1b](https://linux-hardware.org/?probe=f501591d1b) | Sep 27, 2022 |
| Dell          | System Inspiron N7110       | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | [c45069d56d](https://linux-hardware.org/?probe=c45069d56d) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | [3441e0cac3](https://linux-hardware.org/?probe=3441e0cac3) | Sep 26, 2022 |
| ASUSTek       | X201EP                      | [4e6c202d5d](https://linux-hardware.org/?probe=4e6c202d5d) | Sep 26, 2022 |
| Unknown       | NB-7000                     | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [28e086b848](https://linux-hardware.org/?probe=28e086b848) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | [6a8d9c1d7a](https://linux-hardware.org/?probe=6a8d9c1d7a) | Sep 25, 2022 |
| Dell          | Inspiron 14-3452            | [bb90844ff6](https://linux-hardware.org/?probe=bb90844ff6) | Sep 25, 2022 |
| HP            | Stream Laptop 14-ax0XX      | [d8a451b3e6](https://linux-hardware.org/?probe=d8a451b3e6) | Sep 25, 2022 |
| Dell          | Inspiron 3185               | [561c02f958](https://linux-hardware.org/?probe=561c02f958) | Sep 25, 2022 |
| Acer          | Aspire SW5-012              | [ed8f3f7403](https://linux-hardware.org/?probe=ed8f3f7403) | Sep 25, 2022 |
| Acer          | Extensa 5635ZG              | [ade183eadc](https://linux-hardware.org/?probe=ade183eadc) | Sep 24, 2022 |
| HP            | 250 G8 Notebook PC          | [fab0eac5a6](https://linux-hardware.org/?probe=fab0eac5a6) | Sep 24, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [dc3a97d467](https://linux-hardware.org/?probe=dc3a97d467) | Sep 23, 2022 |
| HP            | EliteBook Revolve 810 G3    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| HP            | EliteBook 840 G6            | [9ccc1b86a7](https://linux-hardware.org/?probe=9ccc1b86a7) | Sep 23, 2022 |
| Lenovo        | ThinkPad Edge E530 3259C... | [cdaec9c224](https://linux-hardware.org/?probe=cdaec9c224) | Sep 22, 2022 |
| HP            | ENVY Notebook               | [1eef25f6d8](https://linux-hardware.org/?probe=1eef25f6d8) | Sep 22, 2022 |
| HP            | ENVY Notebook               | [b95a98e133](https://linux-hardware.org/?probe=b95a98e133) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | [00e679e86c](https://linux-hardware.org/?probe=00e679e86c) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | [318436c7ab](https://linux-hardware.org/?probe=318436c7ab) | Sep 22, 2022 |
| ASUSTek       | 1201PN                      | [3dd4546344](https://linux-hardware.org/?probe=3dd4546344) | Sep 21, 2022 |
| ASUSTek       | 1201PN                      | [080d9c8964](https://linux-hardware.org/?probe=080d9c8964) | Sep 21, 2022 |
| Toshiba       | Satellite L855              | [4421e54d32](https://linux-hardware.org/?probe=4421e54d32) | Sep 21, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [6d0a2986ad](https://linux-hardware.org/?probe=6d0a2986ad) | Sep 21, 2022 |
| Alienware     | 18                          | [91d0153265](https://linux-hardware.org/?probe=91d0153265) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Dell          | G15 5515                    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| HP            | Pavilion g7                 | [d51d3d282a](https://linux-hardware.org/?probe=d51d3d282a) | Sep 20, 2022 |
| Dell          | Latitude D610               | [47e0f0fa27](https://linux-hardware.org/?probe=47e0f0fa27) | Sep 19, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| Lenovo        | ThinkPad 11e 20DAS09U00     | [81bd748796](https://linux-hardware.org/?probe=81bd748796) | Sep 19, 2022 |
| Dell          | Latitude E6540              | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| Alienware     | 18                          | [fda9eabd7e](https://linux-hardware.org/?probe=fda9eabd7e) | Sep 18, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [bceb6698c2](https://linux-hardware.org/?probe=bceb6698c2) | Sep 18, 2022 |
| Microtech     | CoreBook                    | [6b1a53d2c2](https://linux-hardware.org/?probe=6b1a53d2c2) | Sep 18, 2022 |
| Ematic        | EWT118                      | [41670ebd30](https://linux-hardware.org/?probe=41670ebd30) | Sep 18, 2022 |
| Dell          | Latitude D610               | [df13ed7396](https://linux-hardware.org/?probe=df13ed7396) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude E6510              | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [e7bb3017fb](https://linux-hardware.org/?probe=e7bb3017fb) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | [c81727b775](https://linux-hardware.org/?probe=c81727b775) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [5620510083](https://linux-hardware.org/?probe=5620510083) | Sep 16, 2022 |
| Dell          | Latitude E4300              | [b3c04d8a81](https://linux-hardware.org/?probe=b3c04d8a81) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [eeb58ef0f2](https://linux-hardware.org/?probe=eeb58ef0f2) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [258c624b3b](https://linux-hardware.org/?probe=258c624b3b) | Sep 15, 2022 |
| Dell          | Latitude D630               | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| Toshiba       | Satellite C855              | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| HP            | EliteBook 820 G2            | [199f191441](https://linux-hardware.org/?probe=199f191441) | Sep 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [676dbc76db](https://linux-hardware.org/?probe=676dbc76db) | Sep 13, 2022 |
| HP            | EliteBook 840 G6            | [3c13816886](https://linux-hardware.org/?probe=3c13816886) | Sep 13, 2022 |
| Samsung       | 800G5M/800G5W               | [ad3cd5381f](https://linux-hardware.org/?probe=ad3cd5381f) | Sep 13, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [ca9a099cf6](https://linux-hardware.org/?probe=ca9a099cf6) | Sep 12, 2022 |
| Samsung       | 600B4B/600B5B               | [25c2b764a6](https://linux-hardware.org/?probe=25c2b764a6) | Sep 12, 2022 |
| Dell          | Latitude E7240              | [72a8c650c5](https://linux-hardware.org/?probe=72a8c650c5) | Sep 11, 2022 |
| Gigabyte      | P64V7                       | [b9d2c998be](https://linux-hardware.org/?probe=b9d2c998be) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| HP            | Pavilion dv6000 (RP986EA... | [f20de20683](https://linux-hardware.org/?probe=f20de20683) | Sep 11, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| HP            | Pavilion dv6700             | [4e96c157b7](https://linux-hardware.org/?probe=4e96c157b7) | Sep 10, 2022 |
| AZW           | Z83-V                       | [70e8dba2ef](https://linux-hardware.org/?probe=70e8dba2ef) | Sep 10, 2022 |
| AZW           | Z83-V                       | [622725ab19](https://linux-hardware.org/?probe=622725ab19) | Sep 10, 2022 |
| Acer          | Aspire 7745G                | [a41158c2cc](https://linux-hardware.org/?probe=a41158c2cc) | Sep 10, 2022 |
| Toshiba       | Satellite P200              | [c49fec0796](https://linux-hardware.org/?probe=c49fec0796) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7c3cdfba24](https://linux-hardware.org/?probe=7c3cdfba24) | Sep 08, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | [e11963681c](https://linux-hardware.org/?probe=e11963681c) | Sep 08, 2022 |
| Dell          | XPS 15 9510                 | [db80996c7a](https://linux-hardware.org/?probe=db80996c7a) | Sep 08, 2022 |
| HP            | Laptop 17-bs0xx             | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| Dell          | Latitude E5420              | [b80d26540d](https://linux-hardware.org/?probe=b80d26540d) | Sep 08, 2022 |
| ASUSTek       | UX331UA                     | [e1e0acfdf3](https://linux-hardware.org/?probe=e1e0acfdf3) | Sep 08, 2022 |
| Dell          | Latitude E4300              | [5d3a9edf5d](https://linux-hardware.org/?probe=5d3a9edf5d) | Sep 07, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [70b198055e](https://linux-hardware.org/?probe=70b198055e) | Sep 07, 2022 |
| HP            | 15                          | [c02361a2ff](https://linux-hardware.org/?probe=c02361a2ff) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [44c27d1083](https://linux-hardware.org/?probe=44c27d1083) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | [ec3283d49b](https://linux-hardware.org/?probe=ec3283d49b) | Sep 06, 2022 |
| HP            | Pavilion g7                 | [5ed29a7629](https://linux-hardware.org/?probe=5ed29a7629) | Sep 05, 2022 |
| Apple         | MacBook5,1                  | [88c4e0664a](https://linux-hardware.org/?probe=88c4e0664a) | Sep 05, 2022 |
| HP            | G62                         | [a3f84f3bf8](https://linux-hardware.org/?probe=a3f84f3bf8) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [d0ec4eb9cc](https://linux-hardware.org/?probe=d0ec4eb9cc) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | [e7061e11ff](https://linux-hardware.org/?probe=e7061e11ff) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | [c661e65b46](https://linux-hardware.org/?probe=c661e65b46) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | [ad86775475](https://linux-hardware.org/?probe=ad86775475) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | [eec792ef79](https://linux-hardware.org/?probe=eec792ef79) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | [0751d35153](https://linux-hardware.org/?probe=0751d35153) | Sep 04, 2022 |
| Apple         | MacBookAir7,2               | [079d33f9b2](https://linux-hardware.org/?probe=079d33f9b2) | Sep 03, 2022 |
| HP            | 620                         | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| Itautec       | Infoway                     | [d207af3252](https://linux-hardware.org/?probe=d207af3252) | Sep 03, 2022 |
| Itautec       | Infoway                     | [737122a0d1](https://linux-hardware.org/?probe=737122a0d1) | Sep 03, 2022 |
| Apple         | MacBookPro8,2               | [c74752a0d2](https://linux-hardware.org/?probe=c74752a0d2) | Sep 02, 2022 |
| Positivo      | C14CR01                     | [ff4d1d45b7](https://linux-hardware.org/?probe=ff4d1d45b7) | Sep 01, 2022 |
| Positivo      | C14CR01                     | [d1fc217886](https://linux-hardware.org/?probe=d1fc217886) | Sep 01, 2022 |
| Dell          | Inspiron 15-3552            | [2eb780855d](https://linux-hardware.org/?probe=2eb780855d) | Sep 01, 2022 |
| Intel         | powered classmate PC        | [ed36baccf9](https://linux-hardware.org/?probe=ed36baccf9) | Aug 31, 2022 |
| Dell          | Inspiron 15-3552            | [8e2cd928f3](https://linux-hardware.org/?probe=8e2cd928f3) | Aug 31, 2022 |
| HP            | Laptop 15-dy1xxx            | [836644c18b](https://linux-hardware.org/?probe=836644c18b) | Aug 31, 2022 |
| HP            | ProBook 6470b               | [2cbe458c94](https://linux-hardware.org/?probe=2cbe458c94) | Aug 30, 2022 |
| Apple         | MacBookAir7,2               | [a96a893eac](https://linux-hardware.org/?probe=a96a893eac) | Aug 30, 2022 |
| Acer          | Aspire SW5-271              | [3446f93f1d](https://linux-hardware.org/?probe=3446f93f1d) | Aug 29, 2022 |
| Samsung       | 300E5M/300E5L               | [6f920f9002](https://linux-hardware.org/?probe=6f920f9002) | Aug 29, 2022 |
| Dell          | XPS 15 9510                 | [45bba02b35](https://linux-hardware.org/?probe=45bba02b35) | Aug 29, 2022 |
| Dell          | Latitude E5440              | [b0d92d186f](https://linux-hardware.org/?probe=b0d92d186f) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| Lenovo        | ThinkPad L440 20ASA1V8BP    | [64f71278c7](https://linux-hardware.org/?probe=64f71278c7) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [be59676867](https://linux-hardware.org/?probe=be59676867) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [04aec7a28a](https://linux-hardware.org/?probe=04aec7a28a) | Aug 28, 2022 |
| Google        | Butterfly                   | [df8fafaf3b](https://linux-hardware.org/?probe=df8fafaf3b) | Aug 28, 2022 |
| HUAWEI        | KLVD-WXX9                   | [c8eb396b68](https://linux-hardware.org/?probe=c8eb396b68) | Aug 26, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | [5b80fb349f](https://linux-hardware.org/?probe=5b80fb349f) | Aug 26, 2022 |
| Apple         | MacBook5,1                  | [7c9f388153](https://linux-hardware.org/?probe=7c9f388153) | Aug 26, 2022 |
| Dell          | XPS 15 9570                 | [c6fc39489e](https://linux-hardware.org/?probe=c6fc39489e) | Aug 26, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [b56c1d75a6](https://linux-hardware.org/?probe=b56c1d75a6) | Aug 25, 2022 |
| Framework     | Laptop                      | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| HP            | Pavilion Notebook           | [5d03f69f35](https://linux-hardware.org/?probe=5d03f69f35) | Aug 25, 2022 |
| Dell          | Latitude E7240              | [0e15063cb3](https://linux-hardware.org/?probe=0e15063cb3) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [59eec9a80d](https://linux-hardware.org/?probe=59eec9a80d) | Aug 24, 2022 |
| Framework     | Laptop                      | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| Toshiba       | Satellite L855              | [73de62c6c7](https://linux-hardware.org/?probe=73de62c6c7) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | [a43c618dbb](https://linux-hardware.org/?probe=a43c618dbb) | Aug 23, 2022 |
| HP            | Laptop 14-dq4xxx            | [8171eb84c2](https://linux-hardware.org/?probe=8171eb84c2) | Aug 23, 2022 |
| Alienware     | 15 R4                       | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [fc9bb1e6fa](https://linux-hardware.org/?probe=fc9bb1e6fa) | Aug 23, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [01416789ab](https://linux-hardware.org/?probe=01416789ab) | Aug 21, 2022 |
| Alienware     | 15 R3                       | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| HP            | 250 G7 Notebook PC          | [ced2388c29](https://linux-hardware.org/?probe=ced2388c29) | Aug 21, 2022 |
| Positivo      | C14CU51                     | [288c810d97](https://linux-hardware.org/?probe=288c810d97) | Aug 21, 2022 |
| ASUSTek       | X542BA                      | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [f37fce9f01](https://linux-hardware.org/?probe=f37fce9f01) | Aug 20, 2022 |
| Apple         | MacBookPro5,5               | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [ec1b67985f](https://linux-hardware.org/?probe=ec1b67985f) | Aug 19, 2022 |
| GPU Compan... | GWTN156-11                  | [c22aa4377d](https://linux-hardware.org/?probe=c22aa4377d) | Aug 19, 2022 |
| Dell          | Inspiron N5010              | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | [e056c24d1d](https://linux-hardware.org/?probe=e056c24d1d) | Aug 18, 2022 |
| HP            | 14                          | [0f2cde73bb](https://linux-hardware.org/?probe=0f2cde73bb) | Aug 17, 2022 |
| ASUSTek       | X756UQ                      | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | 250 G7 Notebook PC          | [8ea659cd8c](https://linux-hardware.org/?probe=8ea659cd8c) | Aug 17, 2022 |
| Dell          | Latitude E6420              | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| ASUSTek       | K54C                        | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| HP            | Pavilion dv9700             | [7c3e324e4f](https://linux-hardware.org/?probe=7c3e324e4f) | Aug 16, 2022 |
| Lenovo        | G505s 20255                 | [58a439770d](https://linux-hardware.org/?probe=58a439770d) | Aug 15, 2022 |
| Packard Be... | EasyNote TE69KB             | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | X555LAB                     | [5171fd1732](https://linux-hardware.org/?probe=5171fd1732) | Aug 15, 2022 |
| Lenovo        | IdeaPad Z580                | [f9d6b2f915](https://linux-hardware.org/?probe=f9d6b2f915) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [2257302110](https://linux-hardware.org/?probe=2257302110) | Aug 14, 2022 |
| HP            | Laptop 17-cn0xxx            | [0006dc34cf](https://linux-hardware.org/?probe=0006dc34cf) | Aug 14, 2022 |
| HP            | EliteBook 6930p             | [7267931d03](https://linux-hardware.org/?probe=7267931d03) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [fb405688fe](https://linux-hardware.org/?probe=fb405688fe) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [62a1acd85d](https://linux-hardware.org/?probe=62a1acd85d) | Aug 13, 2022 |
| HP            | 240 G7 Notebook PC          | [9321e2df1a](https://linux-hardware.org/?probe=9321e2df1a) | Aug 13, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [d08cbbc3d8](https://linux-hardware.org/?probe=d08cbbc3d8) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3dcb75072e](https://linux-hardware.org/?probe=3dcb75072e) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | [b3e408ce95](https://linux-hardware.org/?probe=b3e408ce95) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | [1fe351cfab](https://linux-hardware.org/?probe=1fe351cfab) | Aug 12, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [3d37c741c8](https://linux-hardware.org/?probe=3d37c741c8) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| Unknown       | Unknown                     | [ddeddb54bf](https://linux-hardware.org/?probe=ddeddb54bf) | Aug 12, 2022 |
| Unknown       | Unknown                     | [b19949df5a](https://linux-hardware.org/?probe=b19949df5a) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [dbbd0524d8](https://linux-hardware.org/?probe=dbbd0524d8) | Aug 12, 2022 |
| HP            | Pavilion 15                 | [462769d45e](https://linux-hardware.org/?probe=462769d45e) | Aug 11, 2022 |
| Google        | Kasumi                      | [0d1ce61572](https://linux-hardware.org/?probe=0d1ce61572) | Aug 11, 2022 |
| Google        | Kasumi                      | [47ebd6bcac](https://linux-hardware.org/?probe=47ebd6bcac) | Aug 11, 2022 |
| Dell          | Latitude D630               | [3650f52bba](https://linux-hardware.org/?probe=3650f52bba) | Aug 11, 2022 |
| Dell          | Inspiron 15-3567            | [4e54f20c67](https://linux-hardware.org/?probe=4e54f20c67) | Aug 10, 2022 |
| Samsung       | 600B4B/600B5B               | [889eb9531f](https://linux-hardware.org/?probe=889eb9531f) | Aug 10, 2022 |
| Dell          | Inspiron 3542               | [48722889b6](https://linux-hardware.org/?probe=48722889b6) | Aug 10, 2022 |
| HP            | Pro x2 612 G1 Tablet        | [a40ad10b4c](https://linux-hardware.org/?probe=a40ad10b4c) | Aug 10, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [2f4a79e056](https://linux-hardware.org/?probe=2f4a79e056) | Aug 10, 2022 |
| HP            | Stream Notebook PC 13       | [9071c341a9](https://linux-hardware.org/?probe=9071c341a9) | Aug 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4312639df6](https://linux-hardware.org/?probe=4312639df6) | Aug 09, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | [d1215796fb](https://linux-hardware.org/?probe=d1215796fb) | Aug 08, 2022 |
| Toshiba       | Satellite L655              | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | [69430d4693](https://linux-hardware.org/?probe=69430d4693) | Aug 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [404319dfd4](https://linux-hardware.org/?probe=404319dfd4) | Aug 07, 2022 |
| ASUSTek       | X550JK                      | [a90c14a429](https://linux-hardware.org/?probe=a90c14a429) | Aug 07, 2022 |
| AMI           | Unknown                     | [d40dbd9414](https://linux-hardware.org/?probe=d40dbd9414) | Aug 07, 2022 |
| MSI           | CR620                       | [517b816cd7](https://linux-hardware.org/?probe=517b816cd7) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [d19309cb56](https://linux-hardware.org/?probe=d19309cb56) | Aug 06, 2022 |
| Ematic        | EWT118                      | [a5362d970a](https://linux-hardware.org/?probe=a5362d970a) | Aug 05, 2022 |
| Acer          | Aspire 9410                 | [0d433f48f4](https://linux-hardware.org/?probe=0d433f48f4) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [af83e534ff](https://linux-hardware.org/?probe=af83e534ff) | Aug 04, 2022 |
| Medion        | E7419 MD60990               | [e1b74852bd](https://linux-hardware.org/?probe=e1b74852bd) | Aug 04, 2022 |
| Acer          | Peppy                       | [cc1c91fca6](https://linux-hardware.org/?probe=cc1c91fca6) | Aug 04, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| Toshiba       | Satellite P200              | [87bf7fcb48](https://linux-hardware.org/?probe=87bf7fcb48) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| HP            | Notebook                    | [661237e74a](https://linux-hardware.org/?probe=661237e74a) | Aug 03, 2022 |
| Toshiba       | Satellite P205              | [8ed745a2dc](https://linux-hardware.org/?probe=8ed745a2dc) | Aug 03, 2022 |
| Dell          | G15 5510                    | [f3406b36e3](https://linux-hardware.org/?probe=f3406b36e3) | Aug 02, 2022 |
| Packard Be... | EasyNote TE69KB             | [968a5f757f](https://linux-hardware.org/?probe=968a5f757f) | Aug 02, 2022 |
| Toshiba       | Satellite Pro L670          | [e6189ba78c](https://linux-hardware.org/?probe=e6189ba78c) | Aug 02, 2022 |
| Lenovo        | ThinkPad T420 4236VTQ       | [1ea6046182](https://linux-hardware.org/?probe=1ea6046182) | Aug 02, 2022 |
| HP            | Pro x2 612 G1 Tablet        | [b4bee86632](https://linux-hardware.org/?probe=b4bee86632) | Aug 02, 2022 |
| HP            | Laptop 14-dq4xxx            | [1e57f77386](https://linux-hardware.org/?probe=1e57f77386) | Aug 01, 2022 |
| HP            | Compaq 6730s                | [5d805b2f5e](https://linux-hardware.org/?probe=5d805b2f5e) | Jul 31, 2022 |
| HP            | 550                         | [efc4b32963](https://linux-hardware.org/?probe=efc4b32963) | Jul 30, 2022 |
| Dell          | Latitude E7450              | [894a489a03](https://linux-hardware.org/?probe=894a489a03) | Jul 30, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [4158c1696a](https://linux-hardware.org/?probe=4158c1696a) | Jul 29, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [1a5b34b200](https://linux-hardware.org/?probe=1a5b34b200) | Jul 29, 2022 |
| Dell          | Inspiron 15-3567            | [ceb521429a](https://linux-hardware.org/?probe=ceb521429a) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [b08a0deeff](https://linux-hardware.org/?probe=b08a0deeff) | Jul 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [4bcdc51e89](https://linux-hardware.org/?probe=4bcdc51e89) | Jul 27, 2022 |
| Dell          | Latitude E7450              | [4a277d4cee](https://linux-hardware.org/?probe=4a277d4cee) | Jul 27, 2022 |
| Sony          | VGN-Z31XN_B                 | [f27c511d04](https://linux-hardware.org/?probe=f27c511d04) | Jul 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [37ebea2647](https://linux-hardware.org/?probe=37ebea2647) | Jul 25, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [ff4dba6b3e](https://linux-hardware.org/?probe=ff4dba6b3e) | Jul 24, 2022 |
| HP            | Unknown                     | [1e1768ebfa](https://linux-hardware.org/?probe=1e1768ebfa) | Jul 24, 2022 |
| HP            | Stream Notebook             | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Dell          | Inspiron 1525               | [6c43e1dfd6](https://linux-hardware.org/?probe=6c43e1dfd6) | Jul 22, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [3b2f2c3bea](https://linux-hardware.org/?probe=3b2f2c3bea) | Jul 22, 2022 |
| HP            | ProBook 4540s               | [a2d1e2fd68](https://linux-hardware.org/?probe=a2d1e2fd68) | Jul 22, 2022 |
| HP            | Compaq 420                  | [913795a620](https://linux-hardware.org/?probe=913795a620) | Jul 21, 2022 |
| ASUSTek       | X550CL                      | [abd0b78e41](https://linux-hardware.org/?probe=abd0b78e41) | Jul 21, 2022 |
| Dell          | Inspiron 5520               | [ef41a8c220](https://linux-hardware.org/?probe=ef41a8c220) | Jul 20, 2022 |
| Dell          | Inspiron 3541               | [cb0f9c95d2](https://linux-hardware.org/?probe=cb0f9c95d2) | Jul 20, 2022 |
| Toshiba       | Satellite L655              | [e332607406](https://linux-hardware.org/?probe=e332607406) | Jul 19, 2022 |
| Dell          | Inspiron 1545               | [b0e3b75c3b](https://linux-hardware.org/?probe=b0e3b75c3b) | Jul 19, 2022 |
| Google        | Butterfly                   | [ed6aa75ba5](https://linux-hardware.org/?probe=ed6aa75ba5) | Jul 19, 2022 |
| HUAWEI        | HVY-WXX9                    | [82966b0f63](https://linux-hardware.org/?probe=82966b0f63) | Jul 18, 2022 |
| Apple         | MacBookPro12,1              | [4a5f294565](https://linux-hardware.org/?probe=4a5f294565) | Jul 18, 2022 |
| Dell          | Vostro 3559                 | [3770ab3d4c](https://linux-hardware.org/?probe=3770ab3d4c) | Jul 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [ca9e042e30](https://linux-hardware.org/?probe=ca9e042e30) | Jul 18, 2022 |
| Dell          | MXG061                      | [9301162b93](https://linux-hardware.org/?probe=9301162b93) | Jul 18, 2022 |
| Acer          | NC-A315-41G-R88F            | [8ffe1077fd](https://linux-hardware.org/?probe=8ffe1077fd) | Jul 17, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | [e8b9689526](https://linux-hardware.org/?probe=e8b9689526) | Jul 17, 2022 |
| HP            | ENVY 17                     | [bc1e8b41a5](https://linux-hardware.org/?probe=bc1e8b41a5) | Jul 17, 2022 |
| ASUSTek       | X751MA                      | [e8c8c0d6ec](https://linux-hardware.org/?probe=e8c8c0d6ec) | Jul 16, 2022 |
| Toshiba       | TECRA S11                   | [26ed071525](https://linux-hardware.org/?probe=26ed071525) | Jul 15, 2022 |
| Kogan         | KALAP13S300VA               | [9060455576](https://linux-hardware.org/?probe=9060455576) | Jul 15, 2022 |
| AMI           | Unknown                     | [2d15648f33](https://linux-hardware.org/?probe=2d15648f33) | Jul 14, 2022 |
| Alienware     | x15 R1                      | [95ee5b34a7](https://linux-hardware.org/?probe=95ee5b34a7) | Jul 14, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [ea2c3cd9e9](https://linux-hardware.org/?probe=ea2c3cd9e9) | Jul 14, 2022 |
| HP            | Unknown                     | [aa2aa159c9](https://linux-hardware.org/?probe=aa2aa159c9) | Jul 14, 2022 |
| HP            | ProBook 455 G1              | [a0dd163643](https://linux-hardware.org/?probe=a0dd163643) | Jul 14, 2022 |
| HP            | Laptop 15-dw3xxx            | [09e66aef7e](https://linux-hardware.org/?probe=09e66aef7e) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e3a3e1cac2](https://linux-hardware.org/?probe=e3a3e1cac2) | Jul 13, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| Star Labs     | StarBook                    | [fdae1cd2c3](https://linux-hardware.org/?probe=fdae1cd2c3) | Jul 12, 2022 |
| HP            | Laptop 15-dw3xxx            | [e974774285](https://linux-hardware.org/?probe=e974774285) | Jul 12, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| Dell          | Inspiron 5520               | [67d1588e47](https://linux-hardware.org/?probe=67d1588e47) | Jul 12, 2022 |
| HP            | ProBook 640 G1              | [bc5945b570](https://linux-hardware.org/?probe=bc5945b570) | Jul 11, 2022 |
| HP            | ProBook 640 G1              | [f25593cec7](https://linux-hardware.org/?probe=f25593cec7) | Jul 11, 2022 |
| MSI           | Creator 15 A10SET           | [d90f2aec1b](https://linux-hardware.org/?probe=d90f2aec1b) | Jul 10, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [8a02619147](https://linux-hardware.org/?probe=8a02619147) | Jul 10, 2022 |
| eMachines     | E720 V1.06                  | [ec23637bd5](https://linux-hardware.org/?probe=ec23637bd5) | Jul 09, 2022 |
| Packard Be... | EasyNote TE69KB             | [89403f1acb](https://linux-hardware.org/?probe=89403f1acb) | Jul 09, 2022 |
| HP            | Pavilion 15                 | [1fbb699502](https://linux-hardware.org/?probe=1fbb699502) | Jul 09, 2022 |
| Dell          | Latitude 5400               | [46ce7cf7fe](https://linux-hardware.org/?probe=46ce7cf7fe) | Jul 09, 2022 |
| HP            | Pavilion 15                 | [c74f3711f3](https://linux-hardware.org/?probe=c74f3711f3) | Jul 09, 2022 |
| Fujitsu Si... | AMILO L Series              | [410cd1aeec](https://linux-hardware.org/?probe=410cd1aeec) | Jul 08, 2022 |
| Sony          | VGN-Z31XN_B                 | [e541b7743e](https://linux-hardware.org/?probe=e541b7743e) | Jul 08, 2022 |
| Lenovo        | ThinkPad T400 2768GB4       | [498bb4a509](https://linux-hardware.org/?probe=498bb4a509) | Jul 08, 2022 |
| Acer          | Aspire 5755G                | [37aff6bb24](https://linux-hardware.org/?probe=37aff6bb24) | Jul 08, 2022 |
| HP            | EliteBook 745 G6            | [159ebeaa5e](https://linux-hardware.org/?probe=159ebeaa5e) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [f11f4826ba](https://linux-hardware.org/?probe=f11f4826ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [50e02d8554](https://linux-hardware.org/?probe=50e02d8554) | Jul 08, 2022 |
| Lenovo        | ThinkPad T61 6457B5S        | [34e97dae1e](https://linux-hardware.org/?probe=34e97dae1e) | Jul 08, 2022 |
| ASUSTek       | K70IC                       | [baa2ddeb5a](https://linux-hardware.org/?probe=baa2ddeb5a) | Jul 08, 2022 |
| Acer          | Aspire 5560                 | [e9615585f6](https://linux-hardware.org/?probe=e9615585f6) | Jul 07, 2022 |
| HP            | Mini 110-3100               | [5222f63258](https://linux-hardware.org/?probe=5222f63258) | Jul 06, 2022 |
| Samsung       | 550XDA                      | [74bcded10f](https://linux-hardware.org/?probe=74bcded10f) | Jul 06, 2022 |
| Dell          | Inspiron 3542               | [57fc50a4fb](https://linux-hardware.org/?probe=57fc50a4fb) | Jul 06, 2022 |
| Acer          | Aspire 5755G                | [0dcb64ed5f](https://linux-hardware.org/?probe=0dcb64ed5f) | Jul 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [167fe0c2d1](https://linux-hardware.org/?probe=167fe0c2d1) | Jul 06, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [59923a9781](https://linux-hardware.org/?probe=59923a9781) | Jul 06, 2022 |
| Samsung       | 500R5M/500R5W/501R5M        | [17607e5f03](https://linux-hardware.org/?probe=17607e5f03) | Jul 06, 2022 |
| Acer          | Aspire F5-573               | [1ada0ad162](https://linux-hardware.org/?probe=1ada0ad162) | Jul 06, 2022 |
| Lenovo        | V14-ADA 82C6                | [b8e2b7b6bd](https://linux-hardware.org/?probe=b8e2b7b6bd) | Jul 05, 2022 |
| Lenovo        | S21e-20 80M4                | [968f07d190](https://linux-hardware.org/?probe=968f07d190) | Jul 05, 2022 |
| ASUSTek       | X540LJ                      | [5994a314d0](https://linux-hardware.org/?probe=5994a314d0) | Jul 05, 2022 |
| HP            | ProBook 6475b               | [02eab8bd42](https://linux-hardware.org/?probe=02eab8bd42) | Jul 05, 2022 |
| Packard Be... | H17HV                       | [8b05e7f955](https://linux-hardware.org/?probe=8b05e7f955) | Jul 04, 2022 |
| Acer          | Aspire A515-51G             | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | [c208a1e955](https://linux-hardware.org/?probe=c208a1e955) | Jul 04, 2022 |
| Deffad        | Unknown                     | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| HP            | Laptop 15s-du2xxx           | [65debb520a](https://linux-hardware.org/?probe=65debb520a) | Jul 04, 2022 |
| Lenovo        | G40-45 80E1                 | [bce4ceea50](https://linux-hardware.org/?probe=bce4ceea50) | Jul 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [eb23a7916c](https://linux-hardware.org/?probe=eb23a7916c) | Jul 03, 2022 |
| Dell          | Inspiron 5520               | [2a4654f61b](https://linux-hardware.org/?probe=2a4654f61b) | Jul 03, 2022 |
| Dell          | Inspiron 7520               | [18acc5233d](https://linux-hardware.org/?probe=18acc5233d) | Jul 03, 2022 |
| ASUSTek       | N61Jq                       | [19b3d15d92](https://linux-hardware.org/?probe=19b3d15d92) | Jul 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [f54987d748](https://linux-hardware.org/?probe=f54987d748) | Jul 01, 2022 |
| ASUSTek       | ZenBook UX392FN_UX392FN     | [b4699ba106](https://linux-hardware.org/?probe=b4699ba106) | Jun 30, 2022 |
| MSI           | CR620                       | [0968b18823](https://linux-hardware.org/?probe=0968b18823) | Jun 30, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [7d85e08611](https://linux-hardware.org/?probe=7d85e08611) | Jun 29, 2022 |
| Dell          | Inspiron 3531               | [2c8286100d](https://linux-hardware.org/?probe=2c8286100d) | Jun 29, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V6535        | [3e451a9d00](https://linux-hardware.org/?probe=3e451a9d00) | Jun 28, 2022 |
| Dell          | Latitude E6400              | [df93b48c3c](https://linux-hardware.org/?probe=df93b48c3c) | Jun 28, 2022 |
| HP            | Pavilion Notebook           | [6e098b9c49](https://linux-hardware.org/?probe=6e098b9c49) | Jun 27, 2022 |
| Lenovo        | V14-IIL 82C4                | [740f06d30d](https://linux-hardware.org/?probe=740f06d30d) | Jun 27, 2022 |
| Dell          | XPS 15 9570                 | [8cf2281f01](https://linux-hardware.org/?probe=8cf2281f01) | Jun 27, 2022 |
| Acer          | Aspire A515-55G             | [d05c52e40b](https://linux-hardware.org/?probe=d05c52e40b) | Jun 26, 2022 |
| Google        | Candy                       | [8888e44843](https://linux-hardware.org/?probe=8888e44843) | Jun 25, 2022 |
| Acer          | Aspire A315-42              | [57d9c7c28a](https://linux-hardware.org/?probe=57d9c7c28a) | Jun 24, 2022 |
| HP            | Laptop 15-db0xxx            | [26cd390b15](https://linux-hardware.org/?probe=26cd390b15) | Jun 24, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [8f8ce01734](https://linux-hardware.org/?probe=8f8ce01734) | Jun 24, 2022 |
| Lenovo        | ThinkPad T420 4236J73       | [088ba8b97c](https://linux-hardware.org/?probe=088ba8b97c) | Jun 23, 2022 |
| Dell          | Latitude E6400              | [6198dd2784](https://linux-hardware.org/?probe=6198dd2784) | Jun 22, 2022 |
| Dell          | XPS 13 9360                 | [d5d7479c46](https://linux-hardware.org/?probe=d5d7479c46) | Jun 22, 2022 |
| Acer          | Swift SF314-54              | [3e80b4439f](https://linux-hardware.org/?probe=3e80b4439f) | Jun 22, 2022 |
| Dell          | Inspiron 5537               | [6b549dfe09](https://linux-hardware.org/?probe=6b549dfe09) | Jun 22, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [3bd256be91](https://linux-hardware.org/?probe=3bd256be91) | Jun 21, 2022 |
| Lenovo        | ThinkPad T430s 23539MU      | [cb159502de](https://linux-hardware.org/?probe=cb159502de) | Jun 21, 2022 |
| Dell          | XPS 12 9Q23                 | [463461920a](https://linux-hardware.org/?probe=463461920a) | Jun 21, 2022 |
| Toshiba       | Satellite C870-1C2          | [421b2e1975](https://linux-hardware.org/?probe=421b2e1975) | Jun 20, 2022 |
| HP            | Pavilion Notebook           | [551da1dbb6](https://linux-hardware.org/?probe=551da1dbb6) | Jun 20, 2022 |
| Lenovo        | Flex 2-15 20405             | [0cae0765c9](https://linux-hardware.org/?probe=0cae0765c9) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| HP            | EliteBook 840 G1            | [4a3e29a7c0](https://linux-hardware.org/?probe=4a3e29a7c0) | Jun 20, 2022 |
| Global Dis... | W11651                      | [a28b308f7f](https://linux-hardware.org/?probe=a28b308f7f) | Jun 19, 2022 |
| Dell          | Inspiron N5010              | [82ab434998](https://linux-hardware.org/?probe=82ab434998) | Jun 18, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a20ee1d5b6](https://linux-hardware.org/?probe=a20ee1d5b6) | Jun 17, 2022 |
| Dell          | Latitude E6540              | [4806aec13b](https://linux-hardware.org/?probe=4806aec13b) | Jun 16, 2022 |
| Dell          | Precision M4700             | [3d10ec3c17](https://linux-hardware.org/?probe=3d10ec3c17) | Jun 15, 2022 |
| Primux Tec... | Primux_1402F_W10            | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dell          | XPS 12 9Q23                 | [77c4dc4a62](https://linux-hardware.org/?probe=77c4dc4a62) | Jun 14, 2022 |
| GPU Compan... | GWTC116-2                   | [e849fd55ad](https://linux-hardware.org/?probe=e849fd55ad) | Jun 14, 2022 |
| Positivo      | Q464C                       | [1cb4cb4da1](https://linux-hardware.org/?probe=1cb4cb4da1) | Jun 13, 2022 |
| Positivo      | Q464C                       | [a772cd7eae](https://linux-hardware.org/?probe=a772cd7eae) | Jun 13, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [9baa7ce30e](https://linux-hardware.org/?probe=9baa7ce30e) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| HP            | Pavilion 17                 | [bed3614b80](https://linux-hardware.org/?probe=bed3614b80) | Jun 11, 2022 |
| Positivo      | C4500D                      | [70dc4735fa](https://linux-hardware.org/?probe=70dc4735fa) | Jun 11, 2022 |
| Acer          | Aspire 5736Z                | [dcaa9a66f4](https://linux-hardware.org/?probe=dcaa9a66f4) | Jun 10, 2022 |
| Lenovo        | G50-70 20351                | [828f110a40](https://linux-hardware.org/?probe=828f110a40) | Jun 10, 2022 |
| Dell          | Inspiron 5520               | [d80ec10f91](https://linux-hardware.org/?probe=d80ec10f91) | Jun 09, 2022 |
| Dell          | Inspiron 5520               | [39e10fd449](https://linux-hardware.org/?probe=39e10fd449) | Jun 09, 2022 |
| Toshiba       | QOSMIO X770                 | [d11736c26f](https://linux-hardware.org/?probe=d11736c26f) | Jun 09, 2022 |
| Samsung       | 600B4B/600B5B               | [431ccbf84a](https://linux-hardware.org/?probe=431ccbf84a) | Jun 08, 2022 |
| Toshiba       | Satellite A200              | [9719a84d3e](https://linux-hardware.org/?probe=9719a84d3e) | Jun 08, 2022 |
| Dell          | Inspiron 11-3168            | [9651975542](https://linux-hardware.org/?probe=9651975542) | Jun 07, 2022 |
| Dell          | Inspiron 11-3168            | [b43b02cdeb](https://linux-hardware.org/?probe=b43b02cdeb) | Jun 07, 2022 |
| HP            | Laptop 14-dq0xxx            | [39cfb21bae](https://linux-hardware.org/?probe=39cfb21bae) | Jun 07, 2022 |
| Lenovo        | ThinkPad T540p 20BF0038G... | [e7d830048d](https://linux-hardware.org/?probe=e7d830048d) | Jun 06, 2022 |
| Dell          | Inspiron 3521               | [81fad50492](https://linux-hardware.org/?probe=81fad50492) | Jun 06, 2022 |
| Lenovo        | V14-ADA 82C6                | [94d4930070](https://linux-hardware.org/?probe=94d4930070) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [2e08398c9a](https://linux-hardware.org/?probe=2e08398c9a) | Jun 06, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [8edffcde03](https://linux-hardware.org/?probe=8edffcde03) | Jun 06, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [96ed2caf25](https://linux-hardware.org/?probe=96ed2caf25) | Jun 06, 2022 |
| Lenovo        | Yoga710-14ISK 80TY          | [116abb675e](https://linux-hardware.org/?probe=116abb675e) | Jun 06, 2022 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [4af3ead1a7](https://linux-hardware.org/?probe=4af3ead1a7) | Jun 06, 2022 |
| Dell          | Latitude E6430              | [0ebbfb5b74](https://linux-hardware.org/?probe=0ebbfb5b74) | Jun 05, 2022 |
| HP            | ProBook 450 G3              | [654b62a3bb](https://linux-hardware.org/?probe=654b62a3bb) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [63467c4755](https://linux-hardware.org/?probe=63467c4755) | Jun 05, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8577975269](https://linux-hardware.org/?probe=8577975269) | Jun 05, 2022 |
| HP            | Pavilion dv6                | [8e20121256](https://linux-hardware.org/?probe=8e20121256) | Jun 04, 2022 |
| Dell          | Inspiron 15-5578            | [d88547de78](https://linux-hardware.org/?probe=d88547de78) | Jun 04, 2022 |
| HP            | ZBook Studio G7 Mobile W... | [894d121f66](https://linux-hardware.org/?probe=894d121f66) | Jun 03, 2022 |
| Ematic        | EWT935DK                    | [13c5b6c48c](https://linux-hardware.org/?probe=13c5b6c48c) | Jun 03, 2022 |
| Medion        | WIM2180                     | [0548ef61b7](https://linux-hardware.org/?probe=0548ef61b7) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| Medion        | WIM2180                     | [b645a2fa42](https://linux-hardware.org/?probe=b645a2fa42) | Jun 03, 2022 |
| Lenovo        | G780 2182                   | [878e602f7d](https://linux-hardware.org/?probe=878e602f7d) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [71e59838a5](https://linux-hardware.org/?probe=71e59838a5) | Jun 02, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [702f836250](https://linux-hardware.org/?probe=702f836250) | Jun 02, 2022 |
| Dell          | XPS 15 9510                 | [5eff529610](https://linux-hardware.org/?probe=5eff529610) | Jun 02, 2022 |
| Dell          | Inspiron 15-5578            | [7c1c1fa1ce](https://linux-hardware.org/?probe=7c1c1fa1ce) | Jun 01, 2022 |
| Apple         | MacBook2,1                  | [12cfa4cdb2](https://linux-hardware.org/?probe=12cfa4cdb2) | Jun 01, 2022 |
| Chuwi         | GemiBook Pro                | [24fb23a450](https://linux-hardware.org/?probe=24fb23a450) | May 31, 2022 |
| HP            | EliteBook 8460p             | [a9cca9972f](https://linux-hardware.org/?probe=a9cca9972f) | May 31, 2022 |
| HP            | EliteBook 8460p             | [f05323c723](https://linux-hardware.org/?probe=f05323c723) | May 31, 2022 |
| Dell          | Inspiron 5770               | [02b32c935c](https://linux-hardware.org/?probe=02b32c935c) | May 31, 2022 |
| ASUSTek       | X450LD                      | [b77a4297da](https://linux-hardware.org/?probe=b77a4297da) | May 31, 2022 |
| Dell          | Inspiron 3541               | [20b5815ca3](https://linux-hardware.org/?probe=20b5815ca3) | May 31, 2022 |
| Dell          | Latitude E6510              | [4fe104ba1c](https://linux-hardware.org/?probe=4fe104ba1c) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | [dbf473f0a0](https://linux-hardware.org/?probe=dbf473f0a0) | May 30, 2022 |
| GPU Compan... | GWTC116-2                   | [574439c3c6](https://linux-hardware.org/?probe=574439c3c6) | May 30, 2022 |
| HP            | Compaq 6510b (KE135EA#AK... | [28c05654fc](https://linux-hardware.org/?probe=28c05654fc) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [e34608096b](https://linux-hardware.org/?probe=e34608096b) | May 29, 2022 |
| HP            | EW7-I7D22875GR1             | [d21454c335](https://linux-hardware.org/?probe=d21454c335) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [33de40a2e1](https://linux-hardware.org/?probe=33de40a2e1) | May 29, 2022 |
| HP            | Laptop 14-dq0xxx            | [fac9e55ae9](https://linux-hardware.org/?probe=fac9e55ae9) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [0bf1fadaa2](https://linux-hardware.org/?probe=0bf1fadaa2) | May 29, 2022 |
| Lenovo        | G50-30 80G0                 | [8895ea240a](https://linux-hardware.org/?probe=8895ea240a) | May 29, 2022 |
| Dell          | Latitude 3410               | [b1115f6bbc](https://linux-hardware.org/?probe=b1115f6bbc) | May 28, 2022 |
| HP            | Laptop 14-dq0xxx            | [7d47123b6c](https://linux-hardware.org/?probe=7d47123b6c) | May 28, 2022 |
| Dell          | Latitude D630               | [0560d4c462](https://linux-hardware.org/?probe=0560d4c462) | May 27, 2022 |
| Dell          | Inspiron 5423               | [bd9cd24b2d](https://linux-hardware.org/?probe=bd9cd24b2d) | May 26, 2022 |
| Acer          | Aspire E3-112M              | [240ed3197a](https://linux-hardware.org/?probe=240ed3197a) | May 26, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | [ba19793a38](https://linux-hardware.org/?probe=ba19793a38) | May 26, 2022 |
| Lenovo        | ThinkPad T420 4236MBU       | [7a7ef6ced7](https://linux-hardware.org/?probe=7a7ef6ced7) | May 26, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [9d27d641ca](https://linux-hardware.org/?probe=9d27d641ca) | May 25, 2022 |
| HP            | ZHAN 66 Pro A 14 G3         | [db3577b92d](https://linux-hardware.org/?probe=db3577b92d) | May 25, 2022 |
| Lenovo        | ThinkPad X230 2324FV6       | [6386696f31](https://linux-hardware.org/?probe=6386696f31) | May 25, 2022 |
| HP            | ZBook 15 G2                 | [42ebc7f075](https://linux-hardware.org/?probe=42ebc7f075) | May 25, 2022 |
| HP            | EliteBook 8760w             | [b4066f49b0](https://linux-hardware.org/?probe=b4066f49b0) | May 25, 2022 |
| Toshiba       | Satellite C55-C             | [0c52032af4](https://linux-hardware.org/?probe=0c52032af4) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [a439693491](https://linux-hardware.org/?probe=a439693491) | May 24, 2022 |
| Lenovo        | ThinkPad P50 20EQS28400     | [cca71eec7f](https://linux-hardware.org/?probe=cca71eec7f) | May 24, 2022 |
| Dell          | Venue 8 Pro 5830            | [c07937f5ea](https://linux-hardware.org/?probe=c07937f5ea) | May 24, 2022 |
| ASUSTek       | X201EP                      | [783e306676](https://linux-hardware.org/?probe=783e306676) | May 24, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [d98649058e](https://linux-hardware.org/?probe=d98649058e) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | [aeb154944d](https://linux-hardware.org/?probe=aeb154944d) | May 24, 2022 |
| Dell          | Latitude D520               | [55364bfdc0](https://linux-hardware.org/?probe=55364bfdc0) | May 24, 2022 |
| Lenovo        | ThinkPad X301 277418G       | [0d9a530751](https://linux-hardware.org/?probe=0d9a530751) | May 24, 2022 |
| HP            | Laptop 15s-du2xxx           | [bcccd55aab](https://linux-hardware.org/?probe=bcccd55aab) | May 24, 2022 |
| Toshiba       | Satellite L75D-A            | [0a4b6bedbf](https://linux-hardware.org/?probe=0a4b6bedbf) | May 24, 2022 |
| ASUSTek       | X756UQ                      | [e8736821c1](https://linux-hardware.org/?probe=e8736821c1) | May 23, 2022 |
| Toshiba       | Satellite L10W-C            | [a66d178a46](https://linux-hardware.org/?probe=a66d178a46) | May 21, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [00a44d4f7e](https://linux-hardware.org/?probe=00a44d4f7e) | May 21, 2022 |
| ASUSTek       | K43U                        | [a46669147d](https://linux-hardware.org/?probe=a46669147d) | May 21, 2022 |
| Positivo      | CHT14B                      | [435bbd3b75](https://linux-hardware.org/?probe=435bbd3b75) | May 20, 2022 |
| HP            | Laptop 15-bs1xx             | [e2a3654000](https://linux-hardware.org/?probe=e2a3654000) | May 20, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [8e5e8ea1ba](https://linux-hardware.org/?probe=8e5e8ea1ba) | May 20, 2022 |
| Medion        | Akoya S6214T                | [b0a0df98e0](https://linux-hardware.org/?probe=b0a0df98e0) | May 20, 2022 |
| HP            | EliteBook Folio 1040 G3     | [13bc0ce7c5](https://linux-hardware.org/?probe=13bc0ce7c5) | May 19, 2022 |
| Acer          | TravelMate 5320             | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| ASUSTek       | K43U                        | [2748cd44f0](https://linux-hardware.org/?probe=2748cd44f0) | May 19, 2022 |
| HP            | Pavilion g4                 | [dcb7b65b12](https://linux-hardware.org/?probe=dcb7b65b12) | May 18, 2022 |
| Gateway       | NV55C                       | [16404d222a](https://linux-hardware.org/?probe=16404d222a) | May 18, 2022 |
| Gateway       | NV55C                       | [82fcde80bb](https://linux-hardware.org/?probe=82fcde80bb) | May 18, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [5c20c841d1](https://linux-hardware.org/?probe=5c20c841d1) | May 18, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [ecfb1c48d9](https://linux-hardware.org/?probe=ecfb1c48d9) | May 17, 2022 |
| Sony          | VGN-FW51MF_H                | [084402167e](https://linux-hardware.org/?probe=084402167e) | May 17, 2022 |
| ASUSTek       | ROG Strix G713IM_G713IM     | [eb1da20105](https://linux-hardware.org/?probe=eb1da20105) | May 17, 2022 |
| HP            | EliteBook 2570p             | [70ba6585e8](https://linux-hardware.org/?probe=70ba6585e8) | May 16, 2022 |
| Unknown       | Unknown                     | [bb968f8b83](https://linux-hardware.org/?probe=bb968f8b83) | May 16, 2022 |
| Dell          | Vostro 3500                 | [b95339f19d](https://linux-hardware.org/?probe=b95339f19d) | May 15, 2022 |
| ASUSTek       | GL552VW                     | [2f26e2ec6e](https://linux-hardware.org/?probe=2f26e2ec6e) | May 15, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [ddadf86375](https://linux-hardware.org/?probe=ddadf86375) | May 15, 2022 |
| HP            | ProBook 450 G1              | [c9da66f0e8](https://linux-hardware.org/?probe=c9da66f0e8) | May 15, 2022 |
| Thomson       | NEO14SBK                    | [2ae5fbd212](https://linux-hardware.org/?probe=2ae5fbd212) | May 15, 2022 |
| HP            | Pavilion 17                 | [a3f1fe480c](https://linux-hardware.org/?probe=a3f1fe480c) | May 14, 2022 |
| ASUSTek       | N80Vb                       | [74cb7e076b](https://linux-hardware.org/?probe=74cb7e076b) | May 13, 2022 |
| Acer          | Aspire E1-522               | [21a4fc80c7](https://linux-hardware.org/?probe=21a4fc80c7) | May 13, 2022 |
| Alienware     | 17                          | [b9be04342c](https://linux-hardware.org/?probe=b9be04342c) | May 13, 2022 |
| HP            | OMEN by Laptop              | [f08cef4e3b](https://linux-hardware.org/?probe=f08cef4e3b) | May 13, 2022 |
| Lenovo        | ThinkPad T61 7661V72        | [3d40fb11e8](https://linux-hardware.org/?probe=3d40fb11e8) | May 13, 2022 |
| Toshiba       | Satellite C55-C             | [2695dd828d](https://linux-hardware.org/?probe=2695dd828d) | May 13, 2022 |
| Acer          | Aspire E1-522               | [77fdc036b0](https://linux-hardware.org/?probe=77fdc036b0) | May 13, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [048951833f](https://linux-hardware.org/?probe=048951833f) | May 13, 2022 |
| Dell          | Vostro 3500                 | [3824ac02d2](https://linux-hardware.org/?probe=3824ac02d2) | May 12, 2022 |
| Dell          | Latitude E6540              | [422c7a9209](https://linux-hardware.org/?probe=422c7a9209) | May 11, 2022 |
| Acer          | Aspire E1-571               | [72b102de04](https://linux-hardware.org/?probe=72b102de04) | May 10, 2022 |
| ASUSTek       | X200CA                      | [e041ed14b2](https://linux-hardware.org/?probe=e041ed14b2) | May 10, 2022 |
| Apple         | MacBookPro8,1               | [92637583b8](https://linux-hardware.org/?probe=92637583b8) | May 10, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [81cd3de099](https://linux-hardware.org/?probe=81cd3de099) | May 09, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [a5deca63d5](https://linux-hardware.org/?probe=a5deca63d5) | May 09, 2022 |
| HP            | Laptop 15-db0xxx            | [42f2a531b5](https://linux-hardware.org/?probe=42f2a531b5) | May 09, 2022 |
| HP            | Pavilion Notebook           | [637a04a2d1](https://linux-hardware.org/?probe=637a04a2d1) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [911b8e4c5b](https://linux-hardware.org/?probe=911b8e4c5b) | May 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8e43525285](https://linux-hardware.org/?probe=8e43525285) | May 09, 2022 |
| HP            | Pavilion dv7                | [709b7bc3e0](https://linux-hardware.org/?probe=709b7bc3e0) | May 09, 2022 |
| ASUSTek       | G74Sx                       | [0ed6635d41](https://linux-hardware.org/?probe=0ed6635d41) | May 09, 2022 |
| ASUSTek       | U43F                        | [ad1a88d120](https://linux-hardware.org/?probe=ad1a88d120) | May 08, 2022 |
| Lenovo        | IdeaPad Z580                | [a0751c16d5](https://linux-hardware.org/?probe=a0751c16d5) | May 08, 2022 |
| HP            | Compaq 6530b (WA484LA#AB... | [13cda8fea2](https://linux-hardware.org/?probe=13cda8fea2) | May 08, 2022 |
| ASUSTek       | X200CA                      | [bed44df427](https://linux-hardware.org/?probe=bed44df427) | May 07, 2022 |
| Acer          | Aspire F5-573               | [d6961632c4](https://linux-hardware.org/?probe=d6961632c4) | May 07, 2022 |
| ASUSTek       | G74Sx                       | [44f45ca8ea](https://linux-hardware.org/?probe=44f45ca8ea) | May 07, 2022 |
| Toshiba       | TECRA A50-E                 | [29935ac4c6](https://linux-hardware.org/?probe=29935ac4c6) | May 06, 2022 |
| Lenovo        | G500 20236                  | [8439c948ec](https://linux-hardware.org/?probe=8439c948ec) | May 06, 2022 |
| HP            | Compaq 6730s                | [d1902442d8](https://linux-hardware.org/?probe=d1902442d8) | May 06, 2022 |
| HP            | Compaq 6730s                | [2e53f00a60](https://linux-hardware.org/?probe=2e53f00a60) | May 06, 2022 |
| HP            | Notebook                    | [05f1b18534](https://linux-hardware.org/?probe=05f1b18534) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [8aadfc9dc1](https://linux-hardware.org/?probe=8aadfc9dc1) | May 04, 2022 |
| Google        | Candy                       | [2c41b3e736](https://linux-hardware.org/?probe=2c41b3e736) | May 04, 2022 |
| ASUSTek       | E200HA                      | [399a40cb14](https://linux-hardware.org/?probe=399a40cb14) | May 03, 2022 |
| ASUSTek       | X550CL                      | [b224821361](https://linux-hardware.org/?probe=b224821361) | May 03, 2022 |
| HP            | Pavilion dv6                | [7587fe8761](https://linux-hardware.org/?probe=7587fe8761) | May 03, 2022 |
| HP            | Pavilion dv6                | [bf79099573](https://linux-hardware.org/?probe=bf79099573) | May 03, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | [4e21e1d28e](https://linux-hardware.org/?probe=4e21e1d28e) | May 02, 2022 |
| ASUSTek       | X550CL                      | [5340c940c2](https://linux-hardware.org/?probe=5340c940c2) | May 02, 2022 |
| ASUSTek       | X756UQ                      | [130944084d](https://linux-hardware.org/?probe=130944084d) | May 01, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | [317736e849](https://linux-hardware.org/?probe=317736e849) | May 01, 2022 |
| Lenovo        | Yoga 2 13 20344             | [ce528c379a](https://linux-hardware.org/?probe=ce528c379a) | May 01, 2022 |
| Acer          | Aspire V3-571               | [9cab38ff4f](https://linux-hardware.org/?probe=9cab38ff4f) | May 01, 2022 |
| Acer          | Aspire 5741                 | [f82c315ff4](https://linux-hardware.org/?probe=f82c315ff4) | May 01, 2022 |
| Acer          | V5-171                      | [a07ba20ff0](https://linux-hardware.org/?probe=a07ba20ff0) | Apr 30, 2022 |
| ASUSTek       | X756UQ                      | [2543d87831](https://linux-hardware.org/?probe=2543d87831) | Apr 30, 2022 |
| Toshiba       | Satellite C55-A-1J8         | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| Acer          | V5-171                      | [8500a1c376](https://linux-hardware.org/?probe=8500a1c376) | Apr 30, 2022 |
| ASUSTek       | X411UN                      | [c864c65ec1](https://linux-hardware.org/?probe=c864c65ec1) | Apr 29, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [c4021bd208](https://linux-hardware.org/?probe=c4021bd208) | Apr 29, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| Toshiba       | Satellite Pro R50-B         | [6a8bdd387c](https://linux-hardware.org/?probe=6a8bdd387c) | Apr 29, 2022 |
| Lenovo        | ThinkPad L412 440332U       | [6616ce20ee](https://linux-hardware.org/?probe=6616ce20ee) | Apr 28, 2022 |
| Toshiba       | Satellite C55-C             | [35e8d13a74](https://linux-hardware.org/?probe=35e8d13a74) | Apr 27, 2022 |
| Razer         | Blade                       | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| HP            | 15                          | [63e5782bc3](https://linux-hardware.org/?probe=63e5782bc3) | Apr 27, 2022 |
| Toshiba       | Satellite C55-C             | [d48006a0b2](https://linux-hardware.org/?probe=d48006a0b2) | Apr 26, 2022 |
| Toshiba       | Satellite C55-C             | [e9bc1aaf05](https://linux-hardware.org/?probe=e9bc1aaf05) | Apr 26, 2022 |
| HP            | Compaq Presario CQ70        | [ebfb06702f](https://linux-hardware.org/?probe=ebfb06702f) | Apr 25, 2022 |
| Dell          | Inspiron 1525               | [47a349b8db](https://linux-hardware.org/?probe=47a349b8db) | Apr 25, 2022 |
| ASUSTek       | X540LJ                      | [8e0c841b78](https://linux-hardware.org/?probe=8e0c841b78) | Apr 25, 2022 |
| Toshiba       | Satellite A200              | [f940bea00c](https://linux-hardware.org/?probe=f940bea00c) | Apr 25, 2022 |
| Toshiba       | Satellite A200              | [b1594df62f](https://linux-hardware.org/?probe=b1594df62f) | Apr 25, 2022 |
| Packard Be... | EasyNote TS11HR             | [e1731ce27f](https://linux-hardware.org/?probe=e1731ce27f) | Apr 25, 2022 |
| Packard Be... | EasyNote TS11HR             | [a681022e30](https://linux-hardware.org/?probe=a681022e30) | Apr 25, 2022 |
| HP            | Laptop 15-db0xxx            | [127dd69ddf](https://linux-hardware.org/?probe=127dd69ddf) | Apr 25, 2022 |
| HP            | Notebook                    | [339f862ddd](https://linux-hardware.org/?probe=339f862ddd) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [c954cb4ba4](https://linux-hardware.org/?probe=c954cb4ba4) | Apr 24, 2022 |
| Dell          | Latitude E5500              | [ab88dc2482](https://linux-hardware.org/?probe=ab88dc2482) | Apr 24, 2022 |
| Dell          | Latitude 3440               | [a0c0358f78](https://linux-hardware.org/?probe=a0c0358f78) | Apr 24, 2022 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [9edf97b766](https://linux-hardware.org/?probe=9edf97b766) | Apr 24, 2022 |
| Samsung       | 550XCJ/550XCR               | [4f5bd4cb03](https://linux-hardware.org/?probe=4f5bd4cb03) | Apr 23, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [f57f07921b](https://linux-hardware.org/?probe=f57f07921b) | Apr 23, 2022 |
| ASUSTek       | X55A                        | [9188b40f88](https://linux-hardware.org/?probe=9188b40f88) | Apr 23, 2022 |
| ASUSTek       | X401A1                      | [883c933519](https://linux-hardware.org/?probe=883c933519) | Apr 23, 2022 |
| ASUSTek       | X401A1                      | [9b960298ef](https://linux-hardware.org/?probe=9b960298ef) | Apr 23, 2022 |
| Dell          | Latitude E5440              | [91744e20c7](https://linux-hardware.org/?probe=91744e20c7) | Apr 22, 2022 |
| Google        | Candy                       | [5a31bd1da8](https://linux-hardware.org/?probe=5a31bd1da8) | Apr 22, 2022 |
| Gateway       | NV59C                       | [c7f652c9f8](https://linux-hardware.org/?probe=c7f652c9f8) | Apr 21, 2022 |
| HP            | Laptop 15-bw0xx             | [b251d7f8e6](https://linux-hardware.org/?probe=b251d7f8e6) | Apr 20, 2022 |
| Lenovo        | ThinkPad X220 4286A78       | [d5c9254caa](https://linux-hardware.org/?probe=d5c9254caa) | Apr 20, 2022 |
| HP            | Laptop 15s-du2xxx           | [fe39cbe3d1](https://linux-hardware.org/?probe=fe39cbe3d1) | Apr 20, 2022 |
| Acer          | Nitro AN515-44              | [5549666ce7](https://linux-hardware.org/?probe=5549666ce7) | Apr 20, 2022 |
| Lenovo        | Z40-70 20366                | [c77a5735b7](https://linux-hardware.org/?probe=c77a5735b7) | Apr 20, 2022 |
| HP            | Notebook                    | [f6d84934cd](https://linux-hardware.org/?probe=f6d84934cd) | Apr 19, 2022 |
| Dell          | Inspiron M5010              | [eff0448051](https://linux-hardware.org/?probe=eff0448051) | Apr 19, 2022 |
| HP            | Notebook                    | [b746d96b41](https://linux-hardware.org/?probe=b746d96b41) | Apr 19, 2022 |
| Acer          | Aspire A515-54              | [c1a060dd90](https://linux-hardware.org/?probe=c1a060dd90) | Apr 19, 2022 |
| Toshiba       | Satellite C870-1C2          | [c8917c947b](https://linux-hardware.org/?probe=c8917c947b) | Apr 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [ab4247484f](https://linux-hardware.org/?probe=ab4247484f) | Apr 18, 2022 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [3bf424720c](https://linux-hardware.org/?probe=3bf424720c) | Apr 18, 2022 |
| ASUSTek       | K73BR                       | [596b3b2df6](https://linux-hardware.org/?probe=596b3b2df6) | Apr 18, 2022 |
| Dell          | Latitude E6410              | [391866815a](https://linux-hardware.org/?probe=391866815a) | Apr 17, 2022 |
| Acer          | Aspire V3-112P              | [c27219930e](https://linux-hardware.org/?probe=c27219930e) | Apr 17, 2022 |
| Lenovo        | ThinkPad T430 2349D53       | [7b1d2ec5a1](https://linux-hardware.org/?probe=7b1d2ec5a1) | Apr 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1825f45bfa](https://linux-hardware.org/?probe=1825f45bfa) | Apr 17, 2022 |
| Lenovo        | G40-80 80JE                 | [28c58e21e0](https://linux-hardware.org/?probe=28c58e21e0) | Apr 16, 2022 |
| Lenovo        | ThinkPad E520 11433BU       | [eb10b5f739](https://linux-hardware.org/?probe=eb10b5f739) | Apr 16, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [7e7136d915](https://linux-hardware.org/?probe=7e7136d915) | Apr 16, 2022 |
| Dell          | Inspiron N5110              | [5ae4706be7](https://linux-hardware.org/?probe=5ae4706be7) | Apr 15, 2022 |
| Insignia      | NS-P89W6100 V1.0            | [dabc8a93a8](https://linux-hardware.org/?probe=dabc8a93a8) | Apr 15, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [c1273dfd07](https://linux-hardware.org/?probe=c1273dfd07) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | [23936e29bb](https://linux-hardware.org/?probe=23936e29bb) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | [ae514187f2](https://linux-hardware.org/?probe=ae514187f2) | Apr 15, 2022 |
| Toshiba       | Satellite P50t-A            | [f2eef93c50](https://linux-hardware.org/?probe=f2eef93c50) | Apr 15, 2022 |
| Notebook      | NJ50_70CU                   | [1ec86958b8](https://linux-hardware.org/?probe=1ec86958b8) | Apr 15, 2022 |
| AMI           | Intel                       | [bfee32835f](https://linux-hardware.org/?probe=bfee32835f) | Apr 14, 2022 |
| AMI           | Intel                       | [b7c76035df](https://linux-hardware.org/?probe=b7c76035df) | Apr 14, 2022 |
| HP            | Laptop 14-cm0xxx            | [d6463e4014](https://linux-hardware.org/?probe=d6463e4014) | Apr 14, 2022 |
| Fujitsu       | LIFEBOOK S760               | [6cb98b4c28](https://linux-hardware.org/?probe=6cb98b4c28) | Apr 12, 2022 |
| Toshiba       | Satellite E55-A             | [dc9e2fd729](https://linux-hardware.org/?probe=dc9e2fd729) | Apr 11, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [9a6b2ad9f9](https://linux-hardware.org/?probe=9a6b2ad9f9) | Apr 11, 2022 |
| Lenovo        | ThinkPad L560 20F1001YGE    | [574edf3e3b](https://linux-hardware.org/?probe=574edf3e3b) | Apr 11, 2022 |
| Framework     | Laptop                      | [14cf383f81](https://linux-hardware.org/?probe=14cf383f81) | Apr 09, 2022 |
| HP            | Presario C500 (GF852EA#A... | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| Lenovo        | Flex 2-15 20405             | [b7d6ae3171](https://linux-hardware.org/?probe=b7d6ae3171) | Apr 08, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | [4864fcdfa0](https://linux-hardware.org/?probe=4864fcdfa0) | Apr 07, 2022 |
| HP            | Pavilion Notebook           | [94a611644c](https://linux-hardware.org/?probe=94a611644c) | Apr 07, 2022 |
| HP            | ZBook 15 G3                 | [27bddd0a9c](https://linux-hardware.org/?probe=27bddd0a9c) | Apr 07, 2022 |
| Dell          | Latitude E6530              | [46bbc49e43](https://linux-hardware.org/?probe=46bbc49e43) | Apr 07, 2022 |
| Dell          | Studio 1749                 | [14d44c44fc](https://linux-hardware.org/?probe=14d44c44fc) | Apr 07, 2022 |
| Toshiba       | Satellite L755              | [be86a2f36e](https://linux-hardware.org/?probe=be86a2f36e) | Apr 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | [0f8f2d9229](https://linux-hardware.org/?probe=0f8f2d9229) | Apr 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | [5cc1a973d7](https://linux-hardware.org/?probe=5cc1a973d7) | Apr 06, 2022 |
| HP            | ProBook 4530s               | [1b32584f41](https://linux-hardware.org/?probe=1b32584f41) | Apr 06, 2022 |
| HP            | ProBook 4530s               | [f4dfc894d9](https://linux-hardware.org/?probe=f4dfc894d9) | Apr 06, 2022 |
| Dell          | Inspiron 1545               | [af6989215e](https://linux-hardware.org/?probe=af6989215e) | Apr 06, 2022 |
| Multilaser    | PC121                       | [f93e89718f](https://linux-hardware.org/?probe=f93e89718f) | Apr 05, 2022 |
| Multilaser    | PC121                       | [31f2c02434](https://linux-hardware.org/?probe=31f2c02434) | Apr 05, 2022 |
| HP            | EliteBook 8760w             | [e3a9cdfd95](https://linux-hardware.org/?probe=e3a9cdfd95) | Apr 05, 2022 |
| Lenovo        | B590 37612LG                | [153a6c2343](https://linux-hardware.org/?probe=153a6c2343) | Apr 04, 2022 |
| Medion        | S6417 MD99651               | [2911120bc0](https://linux-hardware.org/?probe=2911120bc0) | Apr 04, 2022 |
| ASUSTek       | T100TA                      | [dbfc15621f](https://linux-hardware.org/?probe=dbfc15621f) | Apr 04, 2022 |
| Dell          | Inspiron 1545               | [8e5b3df957](https://linux-hardware.org/?probe=8e5b3df957) | Apr 03, 2022 |
| Dell          | Inspiron 3185               | [17c6187b71](https://linux-hardware.org/?probe=17c6187b71) | Apr 03, 2022 |
| Lenovo        | ThinkPad T430 23473B2       | [aa0ad3f513](https://linux-hardware.org/?probe=aa0ad3f513) | Apr 03, 2022 |
| Toshiba       | BDB                         | [985b6a2865](https://linux-hardware.org/?probe=985b6a2865) | Apr 03, 2022 |
| HP            | Notebook                    | [e1af57dc16](https://linux-hardware.org/?probe=e1af57dc16) | Apr 02, 2022 |
| Apple         | MacBookAir5,1               | [d8657defc8](https://linux-hardware.org/?probe=d8657defc8) | Apr 02, 2022 |
| HP            | 240 G3                      | [3e6387008c](https://linux-hardware.org/?probe=3e6387008c) | Apr 02, 2022 |
| HP            | Compaq 6730b (NN204ET#AB... | [4f09568c52](https://linux-hardware.org/?probe=4f09568c52) | Apr 01, 2022 |
| Dell          | Latitude E5430 non-vPro     | [b47f5b30db](https://linux-hardware.org/?probe=b47f5b30db) | Apr 01, 2022 |
| HP            | Pavilion Notebook           | [e81da10444](https://linux-hardware.org/?probe=e81da10444) | Apr 01, 2022 |
| HP            | 255 G8 Notebook PC          | [1b1917729b](https://linux-hardware.org/?probe=1b1917729b) | Apr 01, 2022 |
| HP            | Pavilion dv6000 (GA443UA... | [b9a90b57c8](https://linux-hardware.org/?probe=b9a90b57c8) | Apr 01, 2022 |
| ASUSTek       | K55A                        | [71137b6a1e](https://linux-hardware.org/?probe=71137b6a1e) | Apr 01, 2022 |
| ASUSTek       | X102BA                      | [78ecf202d2](https://linux-hardware.org/?probe=78ecf202d2) | Apr 01, 2022 |
| Acer          | Nitro AN515-51              | [61a7788bfa](https://linux-hardware.org/?probe=61a7788bfa) | Mar 31, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d13496f68a](https://linux-hardware.org/?probe=d13496f68a) | Mar 31, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [19aa2cf50d](https://linux-hardware.org/?probe=19aa2cf50d) | Mar 31, 2022 |
| Dell          | Venue 8 Pro 5855            | [35a463a0fb](https://linux-hardware.org/?probe=35a463a0fb) | Mar 31, 2022 |
| Toshiba       | Satellite C660              | [60a6bafd86](https://linux-hardware.org/?probe=60a6bafd86) | Mar 30, 2022 |
| Acer          | Aspire ES1-572              | [bf6df72edf](https://linux-hardware.org/?probe=bf6df72edf) | Mar 29, 2022 |
| Notebook      | NJ50_70CU                   | [ba5b62756b](https://linux-hardware.org/?probe=ba5b62756b) | Mar 29, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [a6218b029c](https://linux-hardware.org/?probe=a6218b029c) | Mar 29, 2022 |
| Panasonic     | CF-31ACJAXPM                | [c90a918208](https://linux-hardware.org/?probe=c90a918208) | Mar 28, 2022 |
| HP            | Pavilion dv3                | [bd8d09108e](https://linux-hardware.org/?probe=bd8d09108e) | Mar 28, 2022 |
| Acer          | Nitro AN515-44              | [36681f4a2f](https://linux-hardware.org/?probe=36681f4a2f) | Mar 28, 2022 |
| ASUSTek       | K70IC                       | [977e15d60c](https://linux-hardware.org/?probe=977e15d60c) | Mar 28, 2022 |
| ASUSTek       | T100TA                      | [fa6858ef16](https://linux-hardware.org/?probe=fa6858ef16) | Mar 28, 2022 |
| Dell          | Precision M4800             | [1eacfc1ab5](https://linux-hardware.org/?probe=1eacfc1ab5) | Mar 27, 2022 |
| Acer          | Predator G9-792             | [4720698441](https://linux-hardware.org/?probe=4720698441) | Mar 27, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | [09cccd4869](https://linux-hardware.org/?probe=09cccd4869) | Mar 27, 2022 |
| Dell          | Inspiron M5030              | [7bc7e689a4](https://linux-hardware.org/?probe=7bc7e689a4) | Mar 26, 2022 |
| Insyde        | GeminiLake                  | [44967ed898](https://linux-hardware.org/?probe=44967ed898) | Mar 26, 2022 |
| HP            | ProBook 4530s               | [f4d3c7fddf](https://linux-hardware.org/?probe=f4d3c7fddf) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [09576b4897](https://linux-hardware.org/?probe=09576b4897) | Mar 25, 2022 |
| Lenovo        | IdeaPad Y550 20017          | [610b3ad535](https://linux-hardware.org/?probe=610b3ad535) | Mar 25, 2022 |
| Acer          | Aspire 3690                 | [76139c48e8](https://linux-hardware.org/?probe=76139c48e8) | Mar 25, 2022 |
| Dell          | Latitude E5540              | [c743515039](https://linux-hardware.org/?probe=c743515039) | Mar 25, 2022 |
| Dell          | Latitude E5540              | [0059ee485d](https://linux-hardware.org/?probe=0059ee485d) | Mar 25, 2022 |
| Toshiba       | Satellite S55t-C            | [0bebc02627](https://linux-hardware.org/?probe=0bebc02627) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [5eac01f806](https://linux-hardware.org/?probe=5eac01f806) | Mar 25, 2022 |
| Dell          | Vostro 1015                 | [ce0fa4ee36](https://linux-hardware.org/?probe=ce0fa4ee36) | Mar 25, 2022 |
| Lenovo        | ThinkPad SL500 274677G      | [1fcd4e44f1](https://linux-hardware.org/?probe=1fcd4e44f1) | Mar 25, 2022 |
| HP            | Laptop 15-bw0xx             | [eb140d5b4d](https://linux-hardware.org/?probe=eb140d5b4d) | Mar 25, 2022 |
| Sony          | SVT13125CLS                 | [5332da89c8](https://linux-hardware.org/?probe=5332da89c8) | Mar 25, 2022 |
| Acer          | Nitro AN515-44              | [4e75dbe2d2](https://linux-hardware.org/?probe=4e75dbe2d2) | Mar 23, 2022 |
| Positivo      | C14CU51                     | [1ca3c10e9b](https://linux-hardware.org/?probe=1ca3c10e9b) | Mar 23, 2022 |
| ASUSTek       | X405UA                      | [1895364071](https://linux-hardware.org/?probe=1895364071) | Mar 22, 2022 |
| Apple         | MacBookPro12,1              | [a39345cbf9](https://linux-hardware.org/?probe=a39345cbf9) | Mar 22, 2022 |
| Gateway       | NV59C                       | [ce722c3cc0](https://linux-hardware.org/?probe=ce722c3cc0) | Mar 22, 2022 |
| MSI           | CR643                       | [24e9c1fe40](https://linux-hardware.org/?probe=24e9c1fe40) | Mar 22, 2022 |
| BGH e-Nova    | Unknown                     | [408be10e82](https://linux-hardware.org/?probe=408be10e82) | Mar 22, 2022 |
| ASUSTek       | G75VW                       | [202d109eb5](https://linux-hardware.org/?probe=202d109eb5) | Mar 22, 2022 |
| HP            | EliteBook 8540p             | [15a215fc17](https://linux-hardware.org/?probe=15a215fc17) | Mar 22, 2022 |
| HP            | EliteBook 8540p             | [f0915a2702](https://linux-hardware.org/?probe=f0915a2702) | Mar 22, 2022 |
| HP            | Laptop 15-db0xxx            | [e0f906e560](https://linux-hardware.org/?probe=e0f906e560) | Mar 21, 2022 |
| HP            | Pavilion g6                 | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| HP            | ENVY dv7                    | [b15a265c66](https://linux-hardware.org/?probe=b15a265c66) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a3859ab679](https://linux-hardware.org/?probe=a3859ab679) | Mar 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9323d5d425](https://linux-hardware.org/?probe=9323d5d425) | Mar 19, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [a2f09086d6](https://linux-hardware.org/?probe=a2f09086d6) | Mar 19, 2022 |
| HP            | Pavilion Notebook           | [02e461a122](https://linux-hardware.org/?probe=02e461a122) | Mar 19, 2022 |
| HP            | Pavilion dv3                | [3dbd970796](https://linux-hardware.org/?probe=3dbd970796) | Mar 19, 2022 |
| Apple         | MacBookPro10,1              | [6da9c9f35d](https://linux-hardware.org/?probe=6da9c9f35d) | Mar 19, 2022 |
| Acer          | Unknown                     | [3c80f8700c](https://linux-hardware.org/?probe=3c80f8700c) | Mar 19, 2022 |
| Lenovo        | ThinkPad T520 424067G       | [3e6c1f772d](https://linux-hardware.org/?probe=3e6c1f772d) | Mar 18, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [3603330b59](https://linux-hardware.org/?probe=3603330b59) | Mar 18, 2022 |
| ASUSTek       | ZenBook UX433FN_U4300FN     | [0228881558](https://linux-hardware.org/?probe=0228881558) | Mar 18, 2022 |
| Dell          | Vostro 1500                 | [b2d732d46b](https://linux-hardware.org/?probe=b2d732d46b) | Mar 18, 2022 |
| Dell          | Vostro 1500                 | [6dbcdd388c](https://linux-hardware.org/?probe=6dbcdd388c) | Mar 18, 2022 |
| Dell          | Inspiron 7737               | [99852ed093](https://linux-hardware.org/?probe=99852ed093) | Mar 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [c3ffdf7791](https://linux-hardware.org/?probe=c3ffdf7791) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [77b0be92c8](https://linux-hardware.org/?probe=77b0be92c8) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [47a984d336](https://linux-hardware.org/?probe=47a984d336) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [662aed3d5d](https://linux-hardware.org/?probe=662aed3d5d) | Mar 17, 2022 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [b3fc1a1d0f](https://linux-hardware.org/?probe=b3fc1a1d0f) | Mar 17, 2022 |
| Dell          | Latitude E4200              | [7342f497b4](https://linux-hardware.org/?probe=7342f497b4) | Mar 16, 2022 |
| HP            | ProBook 450 G2              | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |
| Toshiba       | Satellite C855              | [71d2d562d7](https://linux-hardware.org/?probe=71d2d562d7) | Mar 16, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | [9aa148dba8](https://linux-hardware.org/?probe=9aa148dba8) | Mar 16, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [116bb6c003](https://linux-hardware.org/?probe=116bb6c003) | Mar 15, 2022 |
| Sony          | VGN-FW21E                   | [1dbc74cf43](https://linux-hardware.org/?probe=1dbc74cf43) | Mar 15, 2022 |
| Insyde        | i101c                       | [1d1171c005](https://linux-hardware.org/?probe=1d1171c005) | Mar 15, 2022 |
| Gigabyte      | P64V7                       | [13f2e44186](https://linux-hardware.org/?probe=13f2e44186) | Mar 15, 2022 |
| Toshiba       | Satellite C55-C             | [8fade33706](https://linux-hardware.org/?probe=8fade33706) | Mar 15, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [0755c3c4a6](https://linux-hardware.org/?probe=0755c3c4a6) | Mar 14, 2022 |
| Acer          | Aspire E5-571P              | [dd68b81b43](https://linux-hardware.org/?probe=dd68b81b43) | Mar 14, 2022 |
| Acer          | Aspire SW3-016              | [6988255f00](https://linux-hardware.org/?probe=6988255f00) | Mar 14, 2022 |
| Lenovo        | IdeaPad Z580                | [b5a56fb84b](https://linux-hardware.org/?probe=b5a56fb84b) | Mar 14, 2022 |
| ASUSTek       | X550LC                      | [cb90a1c509](https://linux-hardware.org/?probe=cb90a1c509) | Mar 13, 2022 |
| Lenovo        | IdeaPad 320S-15IKB 81BQ     | [088d2bf23b](https://linux-hardware.org/?probe=088d2bf23b) | Mar 13, 2022 |
| HP            | Notebook                    | [2a7e60663b](https://linux-hardware.org/?probe=2a7e60663b) | Mar 13, 2022 |
| Dell          | Latitude E6220              | [0dbd85da47](https://linux-hardware.org/?probe=0dbd85da47) | Mar 13, 2022 |
| Toshiba       | Satellite C50D-A-14E        | [256e08de3d](https://linux-hardware.org/?probe=256e08de3d) | Mar 13, 2022 |
| Toshiba       | Satellite M505              | [924c539075](https://linux-hardware.org/?probe=924c539075) | Mar 12, 2022 |
| HP            | Laptop 14-ck0xxx            | [92c7141f37](https://linux-hardware.org/?probe=92c7141f37) | Mar 12, 2022 |
| HP            | 1000                        | [c43fd3bfa5](https://linux-hardware.org/?probe=c43fd3bfa5) | Mar 11, 2022 |
| Lenovo        | V110-15IAP 80TG             | [5989c71041](https://linux-hardware.org/?probe=5989c71041) | Mar 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [14237b32d9](https://linux-hardware.org/?probe=14237b32d9) | Mar 11, 2022 |
| Dell          | Inspiron 5520               | [5d8f77310a](https://linux-hardware.org/?probe=5d8f77310a) | Mar 11, 2022 |
| Chuwi         | HeroBook Air                | [674a4fbede](https://linux-hardware.org/?probe=674a4fbede) | Mar 10, 2022 |
| HP            | 15 Notebook PC              | [8714d12640](https://linux-hardware.org/?probe=8714d12640) | Mar 09, 2022 |
| HP            | Laptop 14-dq2xxx            | [cb5d9880c6](https://linux-hardware.org/?probe=cb5d9880c6) | Mar 09, 2022 |
| Packard Be... | EasyNote LS11HR             | [7a99940861](https://linux-hardware.org/?probe=7a99940861) | Mar 08, 2022 |
| Dell          | Inspiron 13-7378            | [6c40e8cf0f](https://linux-hardware.org/?probe=6c40e8cf0f) | Mar 08, 2022 |
| Dell          | Vostro 3550                 | [25951f4351](https://linux-hardware.org/?probe=25951f4351) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [8a4f961472](https://linux-hardware.org/?probe=8a4f961472) | Mar 08, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [4d33fc28da](https://linux-hardware.org/?probe=4d33fc28da) | Mar 08, 2022 |
| Toshiba       | Satellite L875              | [ad99a6a57b](https://linux-hardware.org/?probe=ad99a6a57b) | Mar 07, 2022 |
| Acer          | TP-W700-53334G12            | [61d5d1483d](https://linux-hardware.org/?probe=61d5d1483d) | Mar 07, 2022 |
| HP            | ProBook 640 G1              | [bf9c067da8](https://linux-hardware.org/?probe=bf9c067da8) | Mar 07, 2022 |
| Toshiba       | Satellite L875              | [a5487c84f8](https://linux-hardware.org/?probe=a5487c84f8) | Mar 07, 2022 |
| HP            | Notebook                    | [a15666c682](https://linux-hardware.org/?probe=a15666c682) | Mar 07, 2022 |
| HP            | Notebook                    | [85eb96edd4](https://linux-hardware.org/?probe=85eb96edd4) | Mar 07, 2022 |
| ASUSTek       | X550LC                      | [97f4cf8c40](https://linux-hardware.org/?probe=97f4cf8c40) | Mar 06, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [6e8e3f12d0](https://linux-hardware.org/?probe=6e8e3f12d0) | Mar 06, 2022 |
| AXDIA Inte... | WINBOOK 13                  | [6cf2cc07ed](https://linux-hardware.org/?probe=6cf2cc07ed) | Mar 06, 2022 |
| Dell          | Inspiron MM061              | [ad5413d163](https://linux-hardware.org/?probe=ad5413d163) | Mar 06, 2022 |
| Toshiba       | Satellite C855              | [6911de7c71](https://linux-hardware.org/?probe=6911de7c71) | Mar 05, 2022 |
| Acer          | TP-W700-53334G12            | [cf6bad7b5c](https://linux-hardware.org/?probe=cf6bad7b5c) | Mar 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [14fc889e5f](https://linux-hardware.org/?probe=14fc889e5f) | Mar 05, 2022 |
| Dell          | Precision M6700             | [c5cb8cd111](https://linux-hardware.org/?probe=c5cb8cd111) | Mar 05, 2022 |
| Dell          | Latitude E5500              | [0f590ac9e5](https://linux-hardware.org/?probe=0f590ac9e5) | Mar 05, 2022 |
| HP            | ProBook 445 G7              | [b0b810cf14](https://linux-hardware.org/?probe=b0b810cf14) | Mar 04, 2022 |
| Toshiba       | Satellite A660              | [1a6607437d](https://linux-hardware.org/?probe=1a6607437d) | Mar 04, 2022 |
| Toshiba       | Satellite A660              | [584c89737c](https://linux-hardware.org/?probe=584c89737c) | Mar 04, 2022 |
| HP            | ProBook 4720s               | [631600dd74](https://linux-hardware.org/?probe=631600dd74) | Mar 04, 2022 |
| ASUSTek       | T100TA                      | [485c2b3aa7](https://linux-hardware.org/?probe=485c2b3aa7) | Mar 04, 2022 |
| HP            | Pavilion dv7                | [db550138fb](https://linux-hardware.org/?probe=db550138fb) | Mar 03, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [d09a669d80](https://linux-hardware.org/?probe=d09a669d80) | Mar 03, 2022 |
| Acer          | V5-171                      | [8c620eae72](https://linux-hardware.org/?probe=8c620eae72) | Mar 03, 2022 |
| Lenovo        | G560 0679                   | [07bbbdef41](https://linux-hardware.org/?probe=07bbbdef41) | Mar 03, 2022 |
| HP            | ProBook 4720s               | [8afd2b3c97](https://linux-hardware.org/?probe=8afd2b3c97) | Mar 03, 2022 |
| HP            | ProBook 640 G1              | [6acfc75347](https://linux-hardware.org/?probe=6acfc75347) | Mar 03, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82C5     | [d4b6e7276e](https://linux-hardware.org/?probe=d4b6e7276e) | Mar 03, 2022 |
| Lenovo        | HuronRiver Platform         | [a34efebccf](https://linux-hardware.org/?probe=a34efebccf) | Mar 02, 2022 |
| HP            | Compaq 6730b (NN204ET#AB... | [f20f8759b1](https://linux-hardware.org/?probe=f20f8759b1) | Mar 02, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [fb9f8e44d0](https://linux-hardware.org/?probe=fb9f8e44d0) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [46271114d7](https://linux-hardware.org/?probe=46271114d7) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [1df5245912](https://linux-hardware.org/?probe=1df5245912) | Mar 01, 2022 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [bd438d0f08](https://linux-hardware.org/?probe=bd438d0f08) | Mar 01, 2022 |
| Dell          | Latitude 3550               | [5b0d9e3d13](https://linux-hardware.org/?probe=5b0d9e3d13) | Feb 28, 2022 |
| HP            | 255 G5                      | [050e7b02e7](https://linux-hardware.org/?probe=050e7b02e7) | Feb 28, 2022 |
| Dell          | G5 5590                     | [f553433011](https://linux-hardware.org/?probe=f553433011) | Feb 27, 2022 |
| ASUSTek       | ZenBook UX482EG_UX482EG     | [f67c401f47](https://linux-hardware.org/?probe=f67c401f47) | Feb 27, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [d5c0be1b13](https://linux-hardware.org/?probe=d5c0be1b13) | Feb 27, 2022 |
| ASUSTek       | S500CA                      | [db6a143f17](https://linux-hardware.org/?probe=db6a143f17) | Feb 27, 2022 |
| Acer          | Swift SF114-34              | [49fb58c88b](https://linux-hardware.org/?probe=49fb58c88b) | Feb 27, 2022 |
| Dell          | Latitude E5500              | [c84caad5a2](https://linux-hardware.org/?probe=c84caad5a2) | Feb 26, 2022 |
| Dell          | Latitude E5500              | [38a51b4721](https://linux-hardware.org/?probe=38a51b4721) | Feb 26, 2022 |
| HP            | 630                         | [6bf505d86b](https://linux-hardware.org/?probe=6bf505d86b) | Feb 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [359368d345](https://linux-hardware.org/?probe=359368d345) | Feb 26, 2022 |
| HP            | EliteBook 840 G6            | [fabf12f128](https://linux-hardware.org/?probe=fabf12f128) | Feb 26, 2022 |
| Fujitsu       | FARQ0200GZ                  | [a309120953](https://linux-hardware.org/?probe=a309120953) | Feb 26, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Zorin 16 | 1226      | 52.87%  |
| Zorin 15 | 980       | 42.26%  |
| Zorin 12 | 113       | 4.87%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Notebooks | Percent |
|-------|-----------|---------|
| Zorin | 2311      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.11.0-38-generic | 97        | 3.74%   |
| 5.11.0-27-generic | 92        | 3.54%   |
| 5.15.0-46-generic | 88        | 3.39%   |
| 5.15.0-52-generic | 84        | 3.23%   |
| 5.13.0-30-generic | 72        | 2.77%   |
| 5.3.0-40-generic  | 67        | 2.58%   |
| 5.11.0-37-generic | 67        | 2.58%   |
| 5.11.0-40-generic | 65        | 2.5%    |
| 5.11.0-41-generic | 62        | 2.39%   |
| 5.4.0-42-generic  | 60        | 2.31%   |
| 5.13.0-39-generic | 60        | 2.31%   |
| 5.11.0-34-generic | 57        | 2.19%   |
| 5.11.0-43-generic | 56        | 2.16%   |
| 5.3.0-46-generic  | 53        | 2.04%   |
| 5.15.0-48-generic | 50        | 1.93%   |
| 5.13.0-44-generic | 48        | 1.85%   |
| 5.3.0-51-generic  | 47        | 1.81%   |
| 5.0.0-37-generic  | 47        | 1.81%   |
| 5.13.0-40-generic | 45        | 1.73%   |
| 5.13.0-35-generic | 40        | 1.54%   |
| 5.4.0-47-generic  | 38        | 1.46%   |
| 5.3.0-53-generic  | 37        | 1.42%   |
| 5.3.0-42-generic  | 36        | 1.39%   |
| 5.13.0-28-generic | 36        | 1.39%   |
| 5.15.0-53-generic | 34        | 1.31%   |
| 5.4.0-45-generic  | 33        | 1.27%   |
| 5.15.0-41-generic | 32        | 1.23%   |
| 5.4.0-58-generic  | 31        | 1.19%   |
| 5.4.0-48-generic  | 31        | 1.19%   |
| 5.13.0-52-generic | 31        | 1.19%   |
| 5.4.0-65-generic  | 28        | 1.08%   |
| 5.13.0-27-generic | 28        | 1.08%   |
| 5.4.0-80-generic  | 26        | 1%      |
| 5.11.0-46-generic | 26        | 1%      |
| 5.13.0-41-generic | 25        | 0.96%   |
| 5.4.0-72-generic  | 23        | 0.89%   |
| 5.4.0-52-generic  | 23        | 0.89%   |
| 5.11.0-36-generic | 22        | 0.85%   |
| 5.15.0-43-generic | 21        | 0.81%   |
| 5.4.0-73-generic  | 20        | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 557       | 23.09%  |
| 5.11.0  | 544       | 22.55%  |
| 5.13.0  | 402       | 16.67%  |
| 5.3.0   | 312       | 12.94%  |
| 5.15.0  | 297       | 12.31%  |
| 4.15.0  | 109       | 4.52%   |
| 5.0.0   | 89        | 3.69%   |
| 4.18.0  | 44        | 1.82%   |
| 5.8.0   | 22        | 0.91%   |
| 5.14.0  | 6         | 0.25%   |
| 4.4.0   | 4         | 0.17%   |
| 5.6.0   | 2         | 0.08%   |
| 5.16.0  | 2         | 0.08%   |
| 5.10.0  | 2         | 0.08%   |
| 6.0.0   | 1         | 0.04%   |
| 5.9.12  | 1         | 0.04%   |
| 5.9.0   | 1         | 0.04%   |
| 5.7.1   | 1         | 0.04%   |
| 5.4.180 | 1         | 0.04%   |
| 5.4.1   | 1         | 0.04%   |
| 5.19.9  | 1         | 0.04%   |
| 5.19.14 | 1         | 0.04%   |
| 5.19.12 | 1         | 0.04%   |
| 5.19.1  | 1         | 0.04%   |
| 5.19.0  | 1         | 0.04%   |
| 5.18.6  | 1         | 0.04%   |
| 5.18.15 | 1         | 0.04%   |
| 5.16.12 | 1         | 0.04%   |
| 5.15.49 | 1         | 0.04%   |
| 5.15.24 | 1         | 0.04%   |
| 5.13.18 | 1         | 0.04%   |
| 5.10.35 | 1         | 0.04%   |
| 5.10.16 | 1         | 0.04%   |
| 4.13.0  | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 559       | 23.18%  |
| 5.11    | 544       | 22.55%  |
| 5.13    | 403       | 16.71%  |
| 5.3     | 312       | 12.94%  |
| 5.15    | 299       | 12.4%   |
| 4.15    | 109       | 4.52%   |
| 5.0     | 89        | 3.69%   |
| 4.18    | 44        | 1.82%   |
| 5.8     | 22        | 0.91%   |
| 5.14    | 6         | 0.25%   |
| 5.19    | 5         | 0.21%   |
| 5.10    | 4         | 0.17%   |
| 4.4     | 4         | 0.17%   |
| 5.16    | 3         | 0.12%   |
| 5.9     | 2         | 0.08%   |
| 5.6     | 2         | 0.08%   |
| 5.18    | 2         | 0.08%   |
| 6.0     | 1         | 0.04%   |
| 5.7     | 1         | 0.04%   |
| 4.13    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2050      | 88.59%  |
| i686   | 264       | 11.41%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 1604      | 68.61%  |
| XFCE       | 555       | 23.74%  |
| Unknown    | 165       | 7.06%   |
| X-Cinnamon | 6         | 0.26%   |
| KDE        | 3         | 0.13%   |
| Unity      | 2         | 0.09%   |
| KDE5       | 1         | 0.04%   |
| i3         | 1         | 0.04%   |
| Cinnamon   | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 2188      | 93.87%  |
| Unknown | 105       | 4.5%    |
| Wayland | 38        | 1.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1898      | 80.97%  |
| GDM3    | 161       | 6.87%   |
| GDM     | 156       | 6.66%   |
| LightDM | 121       | 5.16%   |
| TDM     | 6         | 0.26%   |
| SDDM    | 2         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 805       | 34.53%  |
| de_DE   | 163       | 6.99%   |
| pt_BR   | 155       | 6.65%   |
| en_GB   | 138       | 5.92%   |
| Unknown | 126       | 5.41%   |
| it_IT   | 87        | 3.73%   |
| en_IN   | 74        | 3.17%   |
| en_CA   | 70        | 3%      |
| es_ES   | 67        | 2.87%   |
| fr_FR   | 65        | 2.79%   |
| pl_PL   | 53        | 2.27%   |
| en_AU   | 37        | 1.59%   |
| pt_PT   | 35        | 1.5%    |
| es_MX   | 33        | 1.42%   |
| nl_NL   | 31        | 1.33%   |
| ru_RU   | 30        | 1.29%   |
| cs_CZ   | 27        | 1.16%   |
| es_AR   | 25        | 1.07%   |
| en_ZA   | 23        | 0.99%   |
| tr_TR   | 20        | 0.86%   |
| C       | 19        | 0.82%   |
| es_CL   | 17        | 0.73%   |
| sv_SE   | 16        | 0.69%   |
| en_NZ   | 14        | 0.6%    |
| de_AT   | 13        | 0.56%   |
| fr_BE   | 12        | 0.51%   |
| fr_CA   | 11        | 0.47%   |
| ja_JP   | 10        | 0.43%   |
| hu_HU   | 10        | 0.43%   |
| el_GR   | 10        | 0.43%   |
| es_CO   | 9         | 0.39%   |
| da_DK   | 8         | 0.34%   |
| ru_UA   | 7         | 0.3%    |
| nl_BE   | 7         | 0.3%    |
| es_PE   | 7         | 0.3%    |
| en_PH   | 7         | 0.3%    |
| ro_RO   | 6         | 0.26%   |
| de_CH   | 6         | 0.26%   |
| fi_FI   | 5         | 0.21%   |
| bg_BG   | 5         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1277      | 54.62%  |
| EFI  | 1061      | 45.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 2182      | 94.09%  |
| Overlay | 50        | 2.16%   |
| Zfs     | 22        | 0.95%   |
| Btrfs   | 22        | 0.95%   |
| Ext2    | 20        | 0.86%   |
| Unknown | 17        | 0.73%   |
| Xfs     | 3         | 0.13%   |
| Ext3    | 3         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 2111      | 90.76%  |
| GPT     | 165       | 7.09%   |
| MBR     | 50        | 2.15%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2202      | 94.67%  |
| Yes       | 124       | 5.33%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1920      | 82.58%  |
| Yes       | 405       | 17.42%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 539       | 23.32%  |
| Dell                | 356       | 15.4%   |
| Lenovo              | 332       | 14.37%  |
| ASUSTek Computer    | 233       | 10.08%  |
| Acer                | 191       | 8.26%   |
| Toshiba             | 138       | 5.97%   |
| Apple               | 51        | 2.21%   |
| Samsung Electronics | 49        | 2.12%   |
| Sony                | 39        | 1.69%   |
| MSI                 | 34        | 1.47%   |
| Unknown             | 26        | 1.13%   |
| Packard Bell        | 24        | 1.04%   |
| Fujitsu Siemens     | 17        | 0.74%   |
| Positivo            | 16        | 0.69%   |
| Fujitsu             | 16        | 0.69%   |
| HUAWEI              | 15        | 0.65%   |
| Google              | 14        | 0.61%   |
| Medion              | 12        | 0.52%   |
| Notebook            | 11        | 0.48%   |
| Panasonic           | 9         | 0.39%   |
| Alienware           | 9         | 0.39%   |
| Gateway             | 8         | 0.35%   |
| Chuwi               | 7         | 0.3%    |
| AMI                 | 7         | 0.3%    |
| Insyde              | 6         | 0.26%   |
| eMachines           | 6         | 0.26%   |
| NEC Computers       | 5         | 0.22%   |
| LG Electronics      | 5         | 0.22%   |
| Ematic              | 5         | 0.22%   |
| Semp Toshiba        | 4         | 0.17%   |
| Razer               | 4         | 0.17%   |
| Quanta              | 4         | 0.17%   |
| Multilaser          | 4         | 0.17%   |
| Itautec             | 4         | 0.17%   |
| Digibras            | 4         | 0.17%   |
| Clevo               | 4         | 0.17%   |
| TUXEDO              | 3         | 0.13%   |
| TrekStor            | 3         | 0.13%   |
| Thomson             | 3         | 0.13%   |
| Jumper              | 3         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 51        | 2.21%   |
| HP Notebook                  | 24        | 1.04%   |
| HP Pavilion Notebook         | 15        | 0.65%   |
| HP 15                        | 11        | 0.48%   |
| Toshiba Satellite C660       | 10        | 0.43%   |
| HP Pavilion dv6              | 10        | 0.43%   |
| HP Pavilion dv7              | 9         | 0.39%   |
| HP Pavilion 15               | 9         | 0.39%   |
| Dell Inspiron 1545           | 9         | 0.39%   |
| HP Pavilion g6               | 8         | 0.35%   |
| HP Laptop 15-bw0xx           | 8         | 0.35%   |
| Dell Latitude D630           | 8         | 0.35%   |
| Dell Latitude E6540          | 7         | 0.3%    |
| Dell Latitude E6410          | 7         | 0.3%    |
| Dell Latitude E6400          | 7         | 0.3%    |
| Dell Inspiron 3521           | 7         | 0.3%    |
| Dell Inspiron 15-3567        | 7         | 0.3%    |
| Apple MacBookPro8,1          | 7         | 0.3%    |
| HP Pavilion dv6700           | 6         | 0.26%   |
| HP Pavilion 17               | 6         | 0.26%   |
| HP EliteBook 840 G1          | 6         | 0.26%   |
| Dell Inspiron 7520           | 6         | 0.26%   |
| Dell Inspiron 1525           | 6         | 0.26%   |
| Toshiba Satellite A100       | 5         | 0.22%   |
| HP ProBook 640 G1            | 5         | 0.22%   |
| HP Pavilion g7               | 5         | 0.22%   |
| HP Pavilion dv5              | 5         | 0.22%   |
| HP Laptop 15-db0xxx          | 5         | 0.22%   |
| HP EliteBook 8460p           | 5         | 0.22%   |
| HP Compaq Presario CQ60      | 5         | 0.22%   |
| HP 14                        | 5         | 0.22%   |
| Dell Latitude E6430          | 5         | 0.22%   |
| Dell Latitude E6420          | 5         | 0.22%   |
| Dell Inspiron N5010          | 5         | 0.22%   |
| Dell Inspiron 3542           | 5         | 0.22%   |
| Apple MacBookPro11,1         | 5         | 0.22%   |
| Toshiba Satellite C55-C      | 4         | 0.17%   |
| Toshiba Satellite C55-A      | 4         | 0.17%   |
| Samsung 340XAA/350XAA/550XAA | 4         | 0.17%   |
| Positivo Mobile              | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 141       | 6.1%    |
| HP Pavilion           | 138       | 5.97%   |
| Lenovo ThinkPad       | 134       | 5.8%    |
| Acer Aspire           | 134       | 5.8%    |
| Dell Latitude         | 130       | 5.63%   |
| Toshiba Satellite     | 117       | 5.06%   |
| Lenovo IdeaPad        | 103       | 4.46%   |
| HP EliteBook          | 64        | 2.77%   |
| HP ProBook            | 60        | 2.6%    |
| Unknown               | 51        | 2.21%   |
| HP Laptop             | 47        | 2.03%   |
| HP Compaq             | 43        | 1.86%   |
| ASUS VivoBook         | 29        | 1.25%   |
| HP Notebook           | 24        | 1.04%   |
| Dell Vostro           | 24        | 1.04%   |
| Packard Bell EasyNote | 22        | 0.95%   |
| HP ENVY               | 20        | 0.87%   |
| Dell XPS              | 19        | 0.82%   |
| HP Stream             | 16        | 0.69%   |
| HP Presario           | 13        | 0.56%   |
| HP 255                | 13        | 0.56%   |
| ASUS ZenBook          | 13        | 0.56%   |
| HP 15                 | 12        | 0.52%   |
| HP OMEN               | 11        | 0.48%   |
| Fujitsu LIFEBOOK      | 11        | 0.48%   |
| Dell Precision        | 11        | 0.48%   |
| ASUS ROG              | 11        | 0.48%   |
| Dell Studio           | 10        | 0.43%   |
| Apple MacBookPro8     | 10        | 0.43%   |
| Fujitsu Siemens AMILO | 9         | 0.39%   |
| Dell System           | 9         | 0.39%   |
| Toshiba PORTEGE       | 8         | 0.35%   |
| HP ZBook              | 8         | 0.35%   |
| HP Mini               | 8         | 0.35%   |
| ASUS ASUS             | 8         | 0.35%   |
| Lenovo Yoga           | 7         | 0.3%    |
| ASUS TUF              | 7         | 0.3%    |
| Apple MacBookPro11    | 7         | 0.3%    |
| Acer TravelMate       | 7         | 0.3%    |
| Acer Swift            | 7         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 227       | 9.82%   |
| 2013    | 199       | 8.61%   |
| 2012    | 196       | 8.48%   |
| 2010    | 179       | 7.75%   |
| 2008    | 163       | 7.05%   |
| 2014    | 144       | 6.23%   |
| 2019    | 142       | 6.14%   |
| 2018    | 136       | 5.88%   |
| 2017    | 130       | 5.63%   |
| 2007    | 128       | 5.54%   |
| 2009    | 119       | 5.15%   |
| 2015    | 118       | 5.11%   |
| 2016    | 114       | 4.93%   |
| 2020    | 109       | 4.72%   |
| 2021    | 105       | 4.54%   |
| 2006    | 51        | 2.21%   |
| 2005    | 32        | 1.38%   |
| 2022    | 12        | 0.52%   |
| Unknown | 4         | 0.17%   |
| 2003    | 2         | 0.09%   |
| 2004    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2311      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2059      | 88.6%   |
| Enabled  | 265       | 11.4%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2293      | 99.22%  |
| Yes  | 18        | 0.78%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 701       | 30.15%  |
| 4.01-8.0    | 637       | 27.4%   |
| 8.01-16.0   | 290       | 12.47%  |
| 1.01-2.0    | 280       | 12.04%  |
| 16.01-24.0  | 185       | 7.96%   |
| 2.01-3.0    | 94        | 4.04%   |
| 0.51-1.0    | 65        | 2.8%    |
| 32.01-64.0  | 58        | 2.49%   |
| 64.01-256.0 | 9         | 0.39%   |
| 24.01-32.0  | 6         | 0.26%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1094      | 44.15%  |
| 2.01-3.0   | 660       | 26.63%  |
| 3.01-4.0   | 266       | 10.73%  |
| 0.51-1.0   | 243       | 9.81%   |
| 4.01-8.0   | 167       | 6.74%   |
| 0.01-0.5   | 25        | 1.01%   |
| 8.01-16.0  | 20        | 0.81%   |
| 24.01-32.0 | 2         | 0.08%   |
| 16.01-24.0 | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1786      | 76.19%  |
| 2      | 484       | 20.65%  |
| 3      | 51        | 2.18%   |
| 0      | 10        | 0.43%   |
| 4      | 9         | 0.38%   |
| 5      | 2         | 0.09%   |
| 8      | 1         | 0.04%   |
| 6      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1191      | 51.31%  |
| No        | 1130      | 48.69%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1942      | 83.85%  |
| No        | 374       | 16.15%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2237      | 96.71%  |
| No        | 76        | 3.29%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1474      | 63.21%  |
| No        | 858       | 36.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 475       | 20.47%  |
| Germany      | 195       | 8.4%    |
| Brazil       | 179       | 7.71%   |
| UK           | 135       | 5.82%   |
| Italy        | 95        | 4.09%   |
| Canada       | 91        | 3.92%   |
| India        | 80        | 3.45%   |
| Spain        | 73        | 3.15%   |
| France       | 64        | 2.76%   |
| Poland       | 55        | 2.37%   |
| Mexico       | 52        | 2.24%   |
| Netherlands  | 50        | 2.15%   |
| Australia    | 44        | 1.9%    |
| Portugal     | 39        | 1.68%   |
| Sweden       | 31        | 1.34%   |
| Russia       | 31        | 1.34%   |
| Czechia      | 31        | 1.34%   |
| Argentina    | 31        | 1.34%   |
| Belgium      | 30        | 1.29%   |
| South Africa | 29        | 1.25%   |
| Romania      | 26        | 1.12%   |
| Austria      | 26        | 1.12%   |
| Turkey       | 25        | 1.08%   |
| Indonesia    | 24        | 1.03%   |
| Greece       | 21        | 0.9%    |
| Switzerland  | 19        | 0.82%   |
| New Zealand  | 17        | 0.73%   |
| Chile        | 17        | 0.73%   |
| Japan        | 15        | 0.65%   |
| Colombia     | 15        | 0.65%   |
| Norway       | 14        | 0.6%    |
| Serbia       | 13        | 0.56%   |
| Bulgaria     | 13        | 0.56%   |
| Ukraine      | 12        | 0.52%   |
| Hungary      | 12        | 0.52%   |
| Egypt        | 12        | 0.52%   |
| Kenya        | 10        | 0.43%   |
| Denmark      | 10        | 0.43%   |
| Philippines  | 9         | 0.39%   |
| Israel       | 9         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 20        | 0.83%   |
| Sydney         | 17        | 0.71%   |
| Vienna         | 14        | 0.58%   |
| Madrid         | 14        | 0.58%   |
| Berlin         | 14        | 0.58%   |
| Munich         | 13        | 0.54%   |
| Athens         | 13        | 0.54%   |
| Rome           | 12        | 0.5%    |
| Johannesburg   | 12        | 0.5%    |
| Montreal       | 11        | 0.46%   |
| Istanbul       | 11        | 0.46%   |
| Auckland       | 11        | 0.46%   |
| Rio de Janeiro | 10        | 0.41%   |
| New York       | 10        | 0.41%   |
| Milan          | 10        | 0.41%   |
| Mexico City    | 10        | 0.41%   |
| Jakarta        | 10        | 0.41%   |
| Hamburg        | 10        | 0.41%   |
| Stockholm      | 9         | 0.37%   |
| Prague         | 9         | 0.37%   |
| Nairobi        | 9         | 0.37%   |
| Dallas         | 9         | 0.37%   |
| Cairo          | 9         | 0.37%   |
| Warsaw         | 8         | 0.33%   |
| Toronto        | 8         | 0.33%   |
| Seattle        | 8         | 0.33%   |
| Paris          | 8         | 0.33%   |
| Moscow         | 8         | 0.33%   |
| Glasgow        | 8         | 0.33%   |
| Bengaluru      | 8         | 0.33%   |
| Tel Aviv       | 7         | 0.29%   |
| Perth          | 7         | 0.29%   |
| Krakow         | 7         | 0.29%   |
| Buenos Aires   | 7         | 0.29%   |
| Bucharest      | 7         | 0.29%   |
| Barcelona      | 7         | 0.29%   |
| Zurich         | 6         | 0.25%   |
| Stuttgart      | 6         | 0.25%   |
| Panama City    | 6         | 0.25%   |
| Oslo           | 6         | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 380       | 458    | 14.19%  |
| WDC                       | 343       | 406    | 12.81%  |
| Toshiba                   | 305       | 343    | 11.39%  |
| Samsung Electronics       | 293       | 393    | 10.95%  |
| Unknown                   | 217       | 299    | 8.11%   |
| Hitachi                   | 148       | 169    | 5.53%   |
| SanDisk                   | 141       | 163    | 5.27%   |
| Kingston                  | 121       | 142    | 4.52%   |
| Crucial                   | 90        | 108    | 3.36%   |
| HGST                      | 77        | 92     | 2.88%   |
| Intel                     | 59        | 71     | 2.2%    |
| SK hynix                  | 51        | 62     | 1.91%   |
| Fujitsu                   | 37        | 39     | 1.38%   |
| Micron Technology         | 36        | 43     | 1.34%   |
| A-DATA Technology         | 34        | 36     | 1.27%   |
| China                     | 25        | 28     | 0.93%   |
| Intenso                   | 20        | 21     | 0.75%   |
| PNY                       | 19        | 22     | 0.71%   |
| Apple                     | 18        | 19     | 0.67%   |
| LITEON                    | 15        | 19     | 0.56%   |
| SPCC                      | 14        | 16     | 0.52%   |
| Transcend                 | 13        | 18     | 0.49%   |
| KIOXIA                    | 13        | 13     | 0.49%   |
| LITEONIT                  | 12        | 14     | 0.45%   |
| Phison                    | 11        | 13     | 0.41%   |
| Team                      | 10        | 11     | 0.37%   |
| Patriot                   | 10        | 12     | 0.37%   |
| Netac                     | 10        | 10     | 0.37%   |
| JMicron Technology        | 9         | 10     | 0.34%   |
| Unknown                   | 9         | 11     | 0.34%   |
| SABRENT                   | 8         | 9      | 0.3%    |
| OCZ                       | 8         | 9      | 0.3%    |
| GOODRAM                   | 8         | 9      | 0.3%    |
| ASMT                      | 6         | 6      | 0.22%   |
| Lite-On                   | 5         | 7      | 0.19%   |
| Lexar                     | 4         | 4      | 0.15%   |
| IBM/Hitachi               | 4         | 5      | 0.15%   |
| Hewlett-Packard           | 4         | 4      | 0.15%   |
| Plextor                   | 3         | 3      | 0.11%   |
| Micron/Crucial Technology | 3         | 3      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 82        | 2.95%   |
| Unknown MMC Card  64GB                 | 54        | 1.94%   |
| Toshiba MQ01ABF050 500GB               | 44        | 1.58%   |
| Seagate ST1000LM035-1RK172 1TB         | 40        | 1.44%   |
| Toshiba MQ01ABD100 1TB                 | 31        | 1.12%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 29        | 1.04%   |
| Seagate ST500LT012-1DG142 500GB        | 27        | 0.97%   |
| Kingston SA400S37240G 240GB SSD        | 27        | 0.97%   |
| Toshiba MQ04ABF100 1TB                 | 26        | 0.94%   |
| Samsung NVMe SSD Drive 512GB           | 24        | 0.86%   |
| Unknown MMC Card  128GB                | 23        | 0.83%   |
| Seagate ST9500325AS 500GB              | 21        | 0.76%   |
| Unknown MMC Card  16GB                 | 20        | 0.72%   |
| SanDisk NVMe SSD Drive 256GB           | 20        | 0.72%   |
| Kingston SA400S37480G 480GB SSD        | 20        | 0.72%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 19        | 0.68%   |
| Crucial CT240BX500SSD1 240GB           | 18        | 0.65%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 17        | 0.61%   |
| Kingston SA400S37120G 120GB SSD        | 17        | 0.61%   |
| Intel NVMe SSD Drive 512GB             | 17        | 0.61%   |
| Seagate Expansion 1TB                  | 16        | 0.58%   |
| Hitachi HTS545032B9A300 320GB          | 16        | 0.58%   |
| HGST HTS725050A7E630 500GB             | 16        | 0.58%   |
| SanDisk NVMe SSD Drive 512GB           | 14        | 0.5%    |
| Samsung SSD 850 EVO 500GB              | 14        | 0.5%    |
| HGST HTS721010A9E630 1TB               | 14        | 0.5%    |
| Crucial CT500MX500SSD1 500GB           | 14        | 0.5%    |
| HGST HTS541010A9E680 1TB               | 13        | 0.47%   |
| Samsung SSD 860 EVO 500GB              | 12        | 0.43%   |
| Samsung SSD 860 EVO 250GB              | 12        | 0.43%   |
| HGST HTS545050A7E680 500GB             | 11        | 0.4%    |
| Unknown SD/MMC/MS PRO 8GB              | 10        | 0.36%   |
| Seagate ST9320325AS 320GB              | 10        | 0.36%   |
| Seagate ST500LT012-9WS142 500GB        | 10        | 0.36%   |
| Seagate ST500LM021-1KJ152 500GB        | 10        | 0.36%   |
| Kingston SV300S37A120G 120GB SSD       | 10        | 0.36%   |
| Hitachi HTS545050A7E380 500GB          | 10        | 0.36%   |
| Hitachi HTS543232A7A384 320GB          | 10        | 0.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 9         | 0.32%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 9         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 377       | 451    | 29.94%  |
| WDC                 | 297       | 342    | 23.59%  |
| Toshiba             | 261       | 292    | 20.73%  |
| Hitachi             | 148       | 169    | 11.76%  |
| HGST                | 77        | 92     | 6.12%   |
| Fujitsu             | 37        | 39     | 2.94%   |
| Samsung Electronics | 35        | 40     | 2.78%   |
| Unknown             | 10        | 14     | 0.79%   |
| ASMT                | 6         | 6      | 0.48%   |
| IBM/Hitachi         | 4         | 5      | 0.32%   |
| Apple               | 3         | 3      | 0.24%   |
| SABRENT             | 1         | 1      | 0.08%   |
| KESU                | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 1      | 0.08%   |
| Intenso             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 169       | 222    | 19.88%  |
| Kingston            | 103       | 123    | 12.12%  |
| Crucial             | 88        | 104    | 10.35%  |
| SanDisk             | 82        | 97     | 9.65%   |
| WDC                 | 38        | 49     | 4.47%   |
| A-DATA Technology   | 30        | 32     | 3.53%   |
| Toshiba             | 29        | 33     | 3.41%   |
| Intel               | 29        | 32     | 3.41%   |
| China               | 24        | 27     | 2.82%   |
| SK hynix            | 22        | 26     | 2.59%   |
| PNY                 | 19        | 22     | 2.24%   |
| Micron Technology   | 17        | 20     | 2%      |
| LITEON              | 15        | 19     | 1.76%   |
| Intenso             | 14        | 14     | 1.65%   |
| Apple               | 14        | 14     | 1.65%   |
| Transcend           | 13        | 18     | 1.53%   |
| SPCC                | 13        | 15     | 1.53%   |
| LITEONIT            | 12        | 14     | 1.41%   |
| Team                | 10        | 11     | 1.18%   |
| Patriot             | 10        | 12     | 1.18%   |
| Netac               | 10        | 10     | 1.18%   |
| OCZ                 | 8         | 9      | 0.94%   |
| GOODRAM             | 8         | 9      | 0.94%   |
| JMicron Technology  | 6         | 7      | 0.71%   |
| Unknown             | 4         | 6      | 0.47%   |
| Plextor             | 3         | 3      | 0.35%   |
| Lexar               | 3         | 3      | 0.35%   |
| Hewlett-Packard     | 3         | 3      | 0.35%   |
| BHT                 | 3         | 4      | 0.35%   |
| Verbatim            | 2         | 2      | 0.24%   |
| Vaseky              | 2         | 3      | 0.24%   |
| TO Exter            | 2         | 3      | 0.24%   |
| TCSUNBOW            | 2         | 2      | 0.24%   |
| Mushkin             | 2         | 2      | 0.24%   |
| Leven               | 2         | 2      | 0.24%   |
| KingSpec            | 2         | 2      | 0.24%   |
| KingDian            | 2         | 2      | 0.24%   |
| HS-SSD-E100         | 2         | 2      | 0.24%   |
| Zheino              | 1         | 1      | 0.12%   |
| USB30               | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1231      | 1457   | 47.35%  |
| SSD     | 808       | 1013   | 31.08%  |
| NVMe    | 308       | 402    | 11.85%  |
| MMC     | 216       | 297    | 8.31%   |
| Unknown | 37        | 41     | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1915      | 2407   | 76.29%  |
| NVMe | 303       | 394    | 12.07%  |
| MMC  | 216       | 297    | 8.61%   |
| SAS  | 76        | 112    | 3.03%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1520      | 1840   | 75.14%  |
| 0.51-1.0   | 463       | 573    | 22.89%  |
| 1.01-2.0   | 31        | 42     | 1.53%   |
| 4.01-10.0  | 5         | 8      | 0.25%   |
| 3.01-4.0   | 3         | 6      | 0.15%   |
| 2.01-3.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 823       | 34.71%  |
| 251-500        | 614       | 25.9%   |
| 501-1000       | 287       | 12.1%   |
| 51-100         | 274       | 11.56%  |
| 21-50          | 163       | 6.87%   |
| 1-20           | 77        | 3.25%   |
| 1001-2000      | 74        | 3.12%   |
| Unknown        | 23        | 0.97%   |
| More than 3000 | 22        | 0.93%   |
| 2001-3000      | 14        | 0.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1297      | 52.94%  |
| 21-50          | 555       | 22.65%  |
| 51-100         | 221       | 9.02%   |
| 101-250        | 197       | 8.04%   |
| 251-500        | 97        | 3.96%   |
| 501-1000       | 38        | 1.55%   |
| Unknown        | 23        | 0.94%   |
| More than 3000 | 10        | 0.41%   |
| 1001-2000      | 9         | 0.37%   |
| 2001-3000      | 3         | 0.12%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 3         | 3      | 7.32%   |
| Toshiba MQ02ABD100H 1TB                             | 2         | 2      | 4.88%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 2      | 4.88%   |
| Seagate ST500LT012-9WS142 500GB                     | 2         | 2      | 4.88%   |
| WDC WD6400BEVT-22A0RT0 640GB                        | 1         | 1      | 2.44%   |
| WDC WD5000LPVX-75V0TT0 500GB                        | 1         | 1      | 2.44%   |
| WDC WD3200BPVT-55ZEST0 320GB                        | 1         | 1      | 2.44%   |
| WDC WD10SPZX-75Z10T2 1TB                            | 1         | 1      | 2.44%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 1      | 2.44%   |
| WDC WD10JPVT-55A1YT0 1TB                            | 1         | 1      | 2.44%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD                | 1         | 1      | 2.44%   |
| Toshiba MQ01ABF050 500GB                            | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.44%   |
| Toshiba MK5061GSY 500GB                             | 1         | 1      | 2.44%   |
| Toshiba MK2046GSX 200GB                             | 1         | 1      | 2.44%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 2.44%   |
| Seagate ST9500420AS 500GB                           | 1         | 1      | 2.44%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 2.44%   |
| Seagate ST9250315AS 250GB                           | 1         | 1      | 2.44%   |
| Seagate ST9200420ASG 200GB                          | 1         | 1      | 2.44%   |
| Seagate ST9160314AS 160GB                           | 1         | 1      | 2.44%   |
| Seagate ST9120822AS 120GB                           | 1         | 1      | 2.44%   |
| Seagate ST500LM000-SSHD-8GB                         | 1         | 1      | 2.44%   |
| Seagate ST1000LX015-1U7172 1TB                      | 1         | 1      | 2.44%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 1         | 1      | 2.44%   |
| Samsung Electronics MMCRE64G8MPP-0VA 64GB SSD       | 1         | 1      | 2.44%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 2.44%   |
| LITEONIT LCT-256M3S 2.5 7mm 256GB SSD               | 1         | 1      | 2.44%   |
| Kingston SUV400S37240G 240GB SSD                    | 1         | 1      | 2.44%   |
| Kingston RBU-SNS8152S3256GG2 256GB SSD              | 1         | 1      | 2.44%   |
| Hitachi HTS725032A9A364 320GB                       | 1         | 1      | 2.44%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 2.44%   |
| HGST HTS725050A7E630 500GB                          | 1         | 1      | 2.44%   |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 2.44%   |
| HGST HTS541010A9E680 1TB                            | 1         | 1      | 2.44%   |
| Hewlett-Packard SSD S600 240GB                      | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 34.15%  |
| Toshiba             | 9         | 9      | 21.95%  |
| WDC                 | 6         | 6      | 14.63%  |
| HGST                | 3         | 3      | 7.32%   |
| Kingston            | 2         | 2      | 4.88%   |
| Hitachi             | 2         | 2      | 4.88%   |
| SK hynix            | 1         | 1      | 2.44%   |
| Samsung Electronics | 1         | 1      | 2.44%   |
| Micron Technology   | 1         | 1      | 2.44%   |
| LITEONIT            | 1         | 1      | 2.44%   |
| Hewlett-Packard     | 1         | 1      | 2.44%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 14     | 42.42%  |
| Toshiba | 8         | 8      | 24.24%  |
| WDC     | 6         | 6      | 18.18%  |
| HGST    | 3         | 3      | 9.09%   |
| Hitachi | 2         | 2      | 6.06%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 33     | 80.49%  |
| SSD  | 7         | 7      | 17.07%  |
| NVMe | 1         | 1      | 2.44%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2127      | 2960   | 90.9%   |
| Works    | 171       | 207    | 7.31%   |
| Malfunc  | 40        | 41     | 1.71%   |
| Failed   | 2         | 2      | 0.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1711      | 70.73%  |
| AMD                              | 310       | 12.82%  |
| Samsung Electronics              | 108       | 4.46%   |
| SanDisk                          | 61        | 2.52%   |
| Nvidia                           | 40        | 1.65%   |
| SK hynix                         | 27        | 1.12%   |
| Silicon Integrated Systems [SiS] | 27        | 1.12%   |
| Micron Technology                | 20        | 0.83%   |
| Kingston Technology Company      | 18        | 0.74%   |
| Toshiba America Info Systems     | 17        | 0.7%    |
| Phison Electronics               | 13        | 0.54%   |
| KIOXIA                           | 13        | 0.54%   |
| VIA Technologies                 | 11        | 0.45%   |
| Micron/Crucial Technology        | 6         | 0.25%   |
| Marvell Technology Group         | 5         | 0.21%   |
| JMicron Technology               | 5         | 0.21%   |
| ADATA Technology                 | 5         | 0.21%   |
| Lite-On Technology               | 4         | 0.17%   |
| ASMedia Technology               | 4         | 0.17%   |
| Silicon Motion                   | 3         | 0.12%   |
| Realtek Semiconductor            | 3         | 0.12%   |
| Yangtze Memory Technologies      | 2         | 0.08%   |
| Union Memory (Shenzhen)          | 2         | 0.08%   |
| Silicon Image                    | 2         | 0.08%   |
| Lenovo                           | 1         | 0.04%   |
| Apple                            | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 230       | 8.43%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 191       | 7%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 163       | 5.97%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 153       | 5.61%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 133       | 4.87%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 129       | 4.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 103       | 3.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 98        | 3.59%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 86        | 3.15%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 82        | 3%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 58        | 2.13%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 57        | 2.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 51        | 1.87%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 50        | 1.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 45        | 1.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 43        | 1.58%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 41        | 1.5%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 36        | 1.32%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 35        | 1.28%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 32        | 1.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 32        | 1.17%   |
| Intel Volume Management Device NVMe RAID Controller                              | 30        | 1.1%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 29        | 1.06%   |
| Samsung NVMe SSD Controller 980                                                  | 27        | 0.99%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 26        | 0.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 26        | 0.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 25        | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 25        | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                     | 24        | 0.88%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 22        | 0.81%   |
| Micron Non-Volatile memory controller                                            | 20        | 0.73%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 17        | 0.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 17        | 0.62%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 17        | 0.62%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 15        | 0.55%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 15        | 0.55%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 15        | 0.55%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 15        | 0.55%   |
| AMD IXP SB4x0 IDE Controller                                                     | 15        | 0.55%   |
| Intel SSD 660P Series                                                            | 14        | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1692      | 65.89%  |
| IDE  | 397       | 15.46%  |
| NVMe | 307       | 11.95%  |
| RAID | 172       | 6.7%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1936      | 83.77%  |
| AMD          | 374       | 16.18%  |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 31        | 1.34%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 30        | 1.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 28        | 1.21%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 25        | 1.08%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 21        | 0.91%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 21        | 0.91%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 21        | 0.91%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 20        | 0.86%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 20        | 0.86%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 19        | 0.82%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 18        | 0.78%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.78%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 18        | 0.78%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 18        | 0.78%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 18        | 0.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 17        | 0.73%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 17        | 0.73%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 17        | 0.73%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 17        | 0.73%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 15        | 0.65%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 15        | 0.65%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 15        | 0.65%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 15        | 0.65%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 14        | 0.61%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 14        | 0.61%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 14        | 0.61%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 14        | 0.61%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 14        | 0.61%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 14        | 0.61%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 14        | 0.61%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.56%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 13        | 0.56%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 13        | 0.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 13        | 0.56%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 13        | 0.56%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 13        | 0.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 12        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 469       | 20.28%  |
| Intel Core i7           | 342       | 14.79%  |
| Intel Core i3           | 245       | 10.59%  |
| Intel Core 2 Duo        | 207       | 8.95%   |
| Intel Celeron           | 186       | 8.04%   |
| Intel Atom              | 139       | 6.01%   |
| Intel Pentium           | 84        | 3.63%   |
| Other                   | 67        | 2.9%    |
| AMD Ryzen 5             | 53        | 2.29%   |
| AMD A6                  | 45        | 1.95%   |
| Intel Genuine           | 40        | 1.73%   |
| Intel Pentium Dual-Core | 33        | 1.43%   |
| AMD Ryzen 7             | 32        | 1.38%   |
| AMD A4                  | 31        | 1.34%   |
| Intel Pentium Dual      | 26        | 1.12%   |
| Intel Pentium M         | 22        | 0.95%   |
| Intel Core 2            | 22        | 0.95%   |
| Intel Celeron M         | 22        | 0.95%   |
| AMD A10                 | 22        | 0.95%   |
| AMD E1                  | 19        | 0.82%   |
| AMD Ryzen 3             | 18        | 0.78%   |
| AMD A8                  | 18        | 0.78%   |
| AMD E                   | 17        | 0.73%   |
| AMD Turion 64 X2 Mobile | 14        | 0.61%   |
| AMD Turion 64 Mobile    | 9         | 0.39%   |
| Intel Celeron Dual-Core | 8         | 0.35%   |
| Intel Core Duo          | 7         | 0.3%    |
| AMD E2                  | 7         | 0.3%    |
| AMD Athlon 64 X2        | 7         | 0.3%    |
| Intel Core M            | 6         | 0.26%   |
| AMD Ryzen 9             | 6         | 0.26%   |
| AMD C-50                | 6         | 0.26%   |
| AMD Athlon X2           | 6         | 0.26%   |
| AMD Athlon II           | 6         | 0.26%   |
| Intel Pentium Silver    | 5         | 0.22%   |
| AMD Sempron             | 5         | 0.22%   |
| AMD Mobile Sempron      | 5         | 0.22%   |
| AMD C-60                | 5         | 0.22%   |
| Intel Pentium 4         | 4         | 0.17%   |
| Intel Core m5           | 4         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1496      | 64.68%  |
| 4      | 540       | 23.35%  |
| 1      | 166       | 7.18%   |
| 6      | 60        | 2.59%   |
| 8      | 45        | 1.95%   |
| 14     | 2         | 0.09%   |
| 3      | 2         | 0.09%   |
| 16     | 1         | 0.04%   |
| 10     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2311      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1330      | 57.55%  |
| 1      | 981       | 42.45%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2200      | 95.16%  |
| 32-bit         | 110       | 4.76%   |
| Unknown        | 2         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 220       | 9.39%   |
| Unknown    | 212       | 9.04%   |
| 0x306a9    | 168       | 7.17%   |
| 0x1067a    | 129       | 5.5%    |
| 0x40651    | 108       | 4.61%   |
| 0x20655    | 86        | 3.67%   |
| 0x6fd      | 76        | 3.24%   |
| 0x406e3    | 67        | 2.86%   |
| 0x306d4    | 66        | 2.82%   |
| 0x306c3    | 66        | 2.82%   |
| 0x30678    | 60        | 2.56%   |
| 0x806e9    | 55        | 2.35%   |
| 0x806ea    | 53        | 2.26%   |
| 0x406c4    | 49        | 2.09%   |
| 0x10676    | 42        | 1.79%   |
| 0x806c1    | 37        | 1.58%   |
| 0x806ec    | 36        | 1.54%   |
| 0x906ea    | 33        | 1.41%   |
| 0x106ca    | 33        | 1.41%   |
| 0x406c3    | 32        | 1.37%   |
| 0x20652    | 32        | 1.37%   |
| 0x6e8      | 29        | 1.24%   |
| 0x506c9    | 28        | 1.19%   |
| 0x06006705 | 28        | 1.19%   |
| 0x6d8      | 27        | 1.15%   |
| 0x906e9    | 26        | 1.11%   |
| 0x706e5    | 26        | 1.11%   |
| 0x706a8    | 24        | 1.02%   |
| 0x106c2    | 24        | 1.02%   |
| 0x08108109 | 23        | 0.98%   |
| 0x08108102 | 23        | 0.98%   |
| 0x0700010f | 22        | 0.94%   |
| 0x05000119 | 22        | 0.94%   |
| 0x07030105 | 21        | 0.9%    |
| 0x6fb      | 20        | 0.85%   |
| 0x06001119 | 20        | 0.85%   |
| 0x6f6      | 19        | 0.81%   |
| 0x10661    | 16        | 0.68%   |
| 0x6ec      | 15        | 0.64%   |
| 0xa0652    | 14        | 0.6%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 240       | 10.39%  |
| SandyBridge      | 226       | 9.78%   |
| Haswell          | 189       | 8.18%   |
| Penryn           | 181       | 7.83%   |
| IvyBridge        | 176       | 7.62%   |
| Silvermont       | 165       | 7.14%   |
| Core             | 156       | 6.75%   |
| Westmere         | 125       | 5.41%   |
| Skylake          | 82        | 3.55%   |
| P6               | 77        | 3.33%   |
| Bonnell          | 67        | 2.9%    |
| Broadwell        | 66        | 2.86%   |
| Excavator        | 52        | 2.25%   |
| Zen+             | 48        | 2.08%   |
| TigerLake        | 44        | 1.9%    |
| K8 Hammer        | 40        | 1.73%   |
| Goldmont plus    | 38        | 1.64%   |
| IceLake          | 36        | 1.56%   |
| Bobcat           | 34        | 1.47%   |
| Puma             | 31        | 1.34%   |
| Goldmont         | 29        | 1.25%   |
| Zen 2            | 28        | 1.21%   |
| Jaguar           | 27        | 1.17%   |
| Piledriver       | 23        | 1%      |
| CometLake        | 19        | 0.82%   |
| Unknown          | 18        | 0.78%   |
| K10              | 16        | 0.69%   |
| K8 & K10 hybrid  | 15        | 0.65%   |
| Zen 3            | 14        | 0.61%   |
| K10 Llano        | 14        | 0.61%   |
| Zen              | 12        | 0.52%   |
| Nehalem          | 9         | 0.39%   |
| Steamroller      | 5         | 0.22%   |
| NetBurst         | 4         | 0.17%   |
| Tremont          | 3         | 0.13%   |
| Alderlake Hybrid | 2         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1681      | 61.94%  |
| AMD                              | 524       | 19.31%  |
| Nvidia                           | 475       | 17.5%   |
| Silicon Integrated Systems [SiS] | 24        | 0.88%   |
| VIA Technologies                 | 10        | 0.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 202       | 6.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 168       | 5.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 113       | 3.9%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 112       | 3.87%   |
| Intel Core Processor Integrated Graphics Controller                                      | 98        | 3.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 86        | 2.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 79        | 2.73%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 70        | 2.42%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 68        | 2.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 68        | 2.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 66        | 2.28%   |
| Intel HD Graphics 620                                                                    | 65        | 2.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 62        | 2.14%   |
| Intel UHD Graphics 620                                                                   | 51        | 1.76%   |
| Intel HD Graphics 5500                                                                   | 51        | 1.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 49        | 1.69%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 46        | 1.59%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 43        | 1.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 36        | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 34        | 1.17%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 34        | 1.17%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 33        | 1.14%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 29        | 1%      |
| AMD Renoir                                                                               | 28        | 0.97%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 24        | 0.83%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 24        | 0.83%   |
| Intel HD Graphics 630                                                                    | 24        | 0.83%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 24        | 0.83%   |
| Intel HD Graphics 500                                                                    | 23        | 0.79%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 22        | 0.76%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 22        | 0.76%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 22        | 0.76%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 20        | 0.69%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 0.69%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 18        | 0.62%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 18        | 0.62%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 16        | 0.55%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 15        | 0.52%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 14        | 0.48%   |
| AMD Lucienne                                                                             | 14        | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1301      | 56.2%   |
| 1 x AMD        | 369       | 15.94%  |
| Intel + Nvidia | 283       | 12.22%  |
| 1 x Nvidia     | 165       | 7.13%   |
| Intel + AMD    | 95        | 4.1%    |
| 2 x AMD        | 37        | 1.6%    |
| 1 x SiS        | 24        | 1.04%   |
| AMD + Nvidia   | 24        | 1.04%   |
| 1 x VIA        | 10        | 0.43%   |
| 2 x Nvidia     | 4         | 0.17%   |
| Other          | 3         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 2003      | 86.3%   |
| Proprietary | 235       | 10.12%  |
| Unknown     | 83        | 3.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1502      | 64.13%  |
| 0.01-0.5   | 377       | 16.1%   |
| 1.01-2.0   | 208       | 8.88%   |
| 0.51-1.0   | 146       | 6.23%   |
| 3.01-4.0   | 69        | 2.95%   |
| 5.01-6.0   | 18        | 0.77%   |
| 7.01-8.0   | 15        | 0.64%   |
| 2.01-3.0   | 6         | 0.26%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 455       | 19.45%  |
| LG Display              | 352       | 15.05%  |
| Samsung Electronics     | 335       | 14.32%  |
| Chimei Innolux          | 288       | 12.31%  |
| BOE                     | 243       | 10.39%  |
| Chi Mei Optoelectronics | 98        | 4.19%   |
| LG Philips              | 64        | 2.74%   |
| Apple                   | 53        | 2.27%   |
| Lenovo                  | 42        | 1.8%    |
| Dell                    | 37        | 1.58%   |
| Goldstar                | 36        | 1.54%   |
| Sharp                   | 33        | 1.41%   |
| InfoVision              | 24        | 1.03%   |
| PANDA                   | 23        | 0.98%   |
| CPT                     | 18        | 0.77%   |
| Toshiba                 | 17        | 0.73%   |
| HannStar                | 17        | 0.73%   |
| Hewlett-Packard         | 15        | 0.64%   |
| Acer                    | 12        | 0.51%   |
| Sony                    | 11        | 0.47%   |
| Quanta Display          | 11        | 0.47%   |
| LGD                     | 10        | 0.43%   |
| Philips                 | 9         | 0.38%   |
| Vizio                   | 8         | 0.34%   |
| Seiko/Epson             | 8         | 0.34%   |
| InnoLux Display         | 8         | 0.34%   |
| BenQ                    | 8         | 0.34%   |
| AOC                     | 8         | 0.34%   |
| Eizo                    | 6         | 0.26%   |
| Panasonic               | 5         | 0.21%   |
| Iiyama                  | 5         | 0.21%   |
| Unknown                 | 4         | 0.17%   |
| KDC                     | 4         | 0.17%   |
| ASUSTek Computer        | 4         | 0.17%   |
| SAC                     | 3         | 0.13%   |
| Nvidia                  | 3         | 0.13%   |
| IBM                     | 3         | 0.13%   |
| BOE Technology Group    | 3         | 0.13%   |
| Ancor Communications    | 3         | 0.13%   |
| ___                     | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 29        | 1.23%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.89%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.76%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 16        | 0.68%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 16        | 0.68%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.68%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 14        | 0.59%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 12        | 0.51%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 12        | 0.51%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.51%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 11        | 0.47%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 11        | 0.47%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 10        | 0.42%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch                  | 10        | 0.42%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.42%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 10        | 0.42%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 10        | 0.42%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 10        | 0.42%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 9         | 0.38%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 9         | 0.38%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 8         | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 8         | 0.34%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 8         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 8         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 8         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 8         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 8         | 0.34%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 8         | 0.34%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 8         | 0.34%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 8         | 0.34%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 8         | 0.34%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 8         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 7         | 0.3%    |
| InfoVision LCD Monitor IVO03F4 1920x1080 344x193mm 15.5-inch             | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 7         | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 7         | 0.3%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 7         | 0.3%    |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 7         | 0.3%    |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 6         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 984       | 43.08%  |
| 1920x1080 (FHD)    | 591       | 25.88%  |
| 1280x800 (WXGA)    | 196       | 8.58%   |
| 1600x900 (HD+)     | 152       | 6.65%   |
| 1440x900 (WXGA+)   | 66        | 2.89%   |
| 1024x600           | 46        | 2.01%   |
| 3840x2160 (4K)     | 45        | 1.97%   |
| 1680x1050 (WSXGA+) | 27        | 1.18%   |
| 1920x1200 (WUXGA)  | 25        | 1.09%   |
| 2560x1440 (QHD)    | 18        | 0.79%   |
| 2560x1600          | 15        | 0.66%   |
| 1360x768           | 14        | 0.61%   |
| 1280x1024 (SXGA)   | 12        | 0.53%   |
| 1024x768 (XGA)     | 10        | 0.44%   |
| Unknown            | 8         | 0.35%   |
| 2160x1440          | 7         | 0.31%   |
| 1280x768           | 7         | 0.31%   |
| 3200x1800 (QHD+)   | 6         | 0.26%   |
| 2560x1080          | 6         | 0.26%   |
| 2256x1504          | 6         | 0.26%   |
| 2880x1800          | 5         | 0.22%   |
| 3840x2400          | 4         | 0.18%   |
| 1920x540           | 4         | 0.18%   |
| 1680x945           | 4         | 0.18%   |
| 1400x1050          | 3         | 0.13%   |
| 1024x576           | 3         | 0.13%   |
| 5760x1080          | 2         | 0.09%   |
| 3840x1080          | 2         | 0.09%   |
| 3600x1080          | 2         | 0.09%   |
| 3440x1440          | 2         | 0.09%   |
| 1920x515           | 2         | 0.09%   |
| 5760x2160          | 1         | 0.04%   |
| 4480x1600          | 1         | 0.04%   |
| 3840x1200          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 2288x1287          | 1         | 0.04%   |
| 2048x1152          | 1         | 0.04%   |
| 1920x1280          | 1         | 0.04%   |
| 1600x1200          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1054      | 45.08%  |
| 13      | 292       | 12.49%  |
| 14      | 260       | 11.12%  |
| 17      | 200       | 8.55%   |
| 11      | 83        | 3.55%   |
| Unknown | 60        | 2.57%   |
| 12      | 58        | 2.48%   |
| 10      | 55        | 2.35%   |
| 27      | 37        | 1.58%   |
| 24      | 37        | 1.58%   |
| 23      | 27        | 1.15%   |
| 21      | 26        | 1.11%   |
| 18      | 23        | 0.98%   |
| 31      | 13        | 0.56%   |
| 20      | 12        | 0.51%   |
| 34      | 11        | 0.47%   |
| 16      | 11        | 0.47%   |
| 22      | 10        | 0.43%   |
| 19      | 9         | 0.38%   |
| 72      | 8         | 0.34%   |
| 84      | 5         | 0.21%   |
| 54      | 5         | 0.21%   |
| 40      | 5         | 0.21%   |
| 32      | 4         | 0.17%   |
| 8       | 4         | 0.17%   |
| 74      | 3         | 0.13%   |
| 49      | 3         | 0.13%   |
| 25      | 3         | 0.13%   |
| 58      | 2         | 0.09%   |
| 52      | 2         | 0.09%   |
| 37      | 2         | 0.09%   |
| 29      | 2         | 0.09%   |
| 26      | 2         | 0.09%   |
| 65      | 1         | 0.04%   |
| 64      | 1         | 0.04%   |
| 59      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 46      | 1         | 0.04%   |
| 44      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1442      | 61.94%  |
| 201-300     | 327       | 14.05%  |
| 351-400     | 241       | 10.35%  |
| 501-600     | 95        | 4.08%   |
| 401-500     | 79        | 3.39%   |
| Unknown     | 60        | 2.58%   |
| 601-700     | 20        | 0.86%   |
| 1001-1500   | 18        | 0.77%   |
| 701-800     | 16        | 0.69%   |
| 1501-2000   | 16        | 0.69%   |
| 801-900     | 7         | 0.3%    |
| 101-200     | 4         | 0.17%   |
| 901-1000    | 3         | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1733      | 80.12%  |
| 16/10   | 325       | 15.03%  |
| Unknown | 46        | 2.13%   |
| 4/3     | 17        | 0.79%   |
| 3/2     | 17        | 0.79%   |
| 5/4     | 10        | 0.46%   |
| 21/9    | 10        | 0.46%   |
| 32/9    | 2         | 0.09%   |
| 3.73    | 2         | 0.09%   |
| 0.62    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1056      | 45.26%  |
| 81-90          | 454       | 19.46%  |
| 121-130        | 141       | 6.04%   |
| 71-80          | 91        | 3.9%    |
| 51-60          | 83        | 3.56%   |
| 201-250        | 79        | 3.39%   |
| Unknown        | 60        | 2.57%   |
| 61-70          | 57        | 2.44%   |
| 41-50          | 55        | 2.36%   |
| 131-140        | 50        | 2.14%   |
| 301-350        | 38        | 1.63%   |
| 151-200        | 33        | 1.41%   |
| More than 1000 | 31        | 1.33%   |
| 351-500        | 30        | 1.29%   |
| 141-150        | 29        | 1.24%   |
| 501-1000       | 14        | 0.6%    |
| 251-300        | 12        | 0.51%   |
| 91-100         | 9         | 0.39%   |
| 111-120        | 7         | 0.3%    |
| 1-40           | 4         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 1037      | 45.22%  |
| 121-160       | 630       | 27.47%  |
| 51-100        | 420       | 18.32%  |
| 161-240       | 82        | 3.58%   |
| Unknown       | 60        | 2.62%   |
| 1-50          | 34        | 1.48%   |
| More than 240 | 30        | 1.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 2002      | 85.19%  |
| 2     | 241       | 10.26%  |
| 0     | 88        | 3.74%   |
| 3     | 17        | 0.72%   |
| 5     | 1         | 0.04%   |
| 4     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1183      | 31.18%  |
| Intel                             | 933       | 24.59%  |
| Qualcomm Atheros                  | 668       | 17.61%  |
| Broadcom                          | 386       | 10.17%  |
| Broadcom Limited                  | 124       | 3.27%   |
| Marvell Technology Group          | 70        | 1.85%   |
| Ralink                            | 50        | 1.32%   |
| Nvidia                            | 35        | 0.92%   |
| TP-Link                           | 25        | 0.66%   |
| Silicon Integrated Systems [SiS]  | 25        | 0.66%   |
| Ralink Technology                 | 22        | 0.58%   |
| ASIX Electronics                  | 22        | 0.58%   |
| JMicron Technology                | 20        | 0.53%   |
| Samsung Electronics               | 18        | 0.47%   |
| MediaTek                          | 17        | 0.45%   |
| Dell                              | 17        | 0.45%   |
| Xiaomi                            | 15        | 0.4%    |
| Sierra Wireless                   | 12        | 0.32%   |
| DisplayLink                       | 11        | 0.29%   |
| Hewlett-Packard                   | 10        | 0.26%   |
| VIA Technologies                  | 9         | 0.24%   |
| Qualcomm Atheros Communications   | 9         | 0.24%   |
| Huawei Technologies               | 9         | 0.24%   |
| Ericsson Business Mobile Networks | 9         | 0.24%   |
| Edimax Technology                 | 8         | 0.21%   |
| ASUSTek Computer                  | 8         | 0.21%   |
| AMD                               | 8         | 0.21%   |
| OPPO Electronics                  | 6         | 0.16%   |
| Attansic Technology               | 6         | 0.16%   |
| NetGear                           | 5         | 0.13%   |
| Motorola PCS                      | 5         | 0.13%   |
| Qualcomm                          | 4         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.11%   |
| D-Link System                     | 4         | 0.11%   |
| T & A Mobile Phones               | 3         | 0.08%   |
| Linksys                           | 3         | 0.08%   |
| D-Link                            | 3         | 0.08%   |
| ZyDAS                             | 2         | 0.05%   |
| Micro Star International          | 2         | 0.05%   |
| Davicom Semiconductor             | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 583       | 12.92%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 346       | 7.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 125       | 2.77%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 112       | 2.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 97        | 2.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 96        | 2.13%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 85        | 1.88%   |
| Intel Wireless 7260                                                     | 83        | 1.84%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 71        | 1.57%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 62        | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 61        | 1.35%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 60        | 1.33%   |
| Broadcom BCM43142 802.11b/g/n                                           | 56        | 1.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 55        | 1.22%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 53        | 1.17%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 46        | 1.02%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 45        | 1%      |
| Intel Wireless 8265 / 8275                                              | 45        | 1%      |
| Intel Wireless 7265                                                     | 44        | 0.98%   |
| Intel Wireless 3165                                                     | 43        | 0.95%   |
| Intel WiFi Link 5100                                                    | 42        | 0.93%   |
| Intel Wi-Fi 6 AX200                                                     | 42        | 0.93%   |
| Intel Wireless 8260                                                     | 36        | 0.8%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 35        | 0.78%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 0.73%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 32        | 0.71%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 31        | 0.69%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 30        | 0.66%   |
| Intel Centrino Ultimate-N 6300                                          | 28        | 0.62%   |
| Intel 82567LM Gigabit Network Connection                                | 28        | 0.62%   |
| Intel Ethernet Connection I218-LM                                       | 27        | 0.6%    |
| Intel Ethernet Connection I217-LM                                       | 27        | 0.6%    |
| Intel 82577LM Gigabit Network Connection                                | 27        | 0.6%    |
| Broadcom BCM4311 802.11b/g WLAN                                         | 27        | 0.6%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 26        | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 26        | 0.58%   |
| Intel Wi-Fi 6 AX201                                                     | 26        | 0.58%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 25        | 0.55%   |
| Intel Wireless 3160                                                     | 25        | 0.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 24        | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 859       | 35.75%  |
| Qualcomm Atheros                | 565       | 23.51%  |
| Realtek Semiconductor           | 411       | 17.1%   |
| Broadcom                        | 296       | 12.32%  |
| Broadcom Limited                | 87        | 3.62%   |
| Ralink                          | 50        | 2.08%   |
| Ralink Technology               | 22        | 0.92%   |
| TP-Link                         | 19        | 0.79%   |
| MediaTek                        | 15        | 0.62%   |
| Sierra Wireless                 | 12        | 0.5%    |
| Qualcomm Atheros Communications | 9         | 0.37%   |
| Edimax Technology               | 8         | 0.33%   |
| Dell                            | 8         | 0.33%   |
| ASUSTek Computer                | 7         | 0.29%   |
| NetGear                         | 5         | 0.21%   |
| Hewlett-Packard                 | 5         | 0.21%   |
| D-Link System                   | 4         | 0.17%   |
| Linksys                         | 3         | 0.12%   |
| ZyDAS                           | 2         | 0.08%   |
| Micro Star International        | 2         | 0.08%   |
| D-Link                          | 2         | 0.08%   |
| Belkin Components               | 2         | 0.08%   |
| ZyXEL Communications            | 1         | 0.04%   |
| Xiaomi                          | 1         | 0.04%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Qualcomm                        | 1         | 0.04%   |
| Qcom                            | 1         | 0.04%   |
| Mercucys                        | 1         | 0.04%   |
| Lite-On Technology              | 1         | 0.04%   |
| IMC Networks                    | 1         | 0.04%   |
| Fibocom                         | 1         | 0.04%   |
| Askey Computer                  | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 125       | 5.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 112       | 4.62%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 96        | 3.96%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 85        | 3.51%   |
| Intel Wireless 7260                                                     | 83        | 3.43%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 71        | 2.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 62        | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 61        | 2.52%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 60        | 2.48%   |
| Broadcom BCM43142 802.11b/g/n                                           | 56        | 2.31%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 55        | 2.27%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 53        | 2.19%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 46        | 1.9%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 45        | 1.86%   |
| Intel Wireless 8265 / 8275                                              | 45        | 1.86%   |
| Intel Wireless 7265                                                     | 44        | 1.82%   |
| Intel Wireless 3165                                                     | 43        | 1.77%   |
| Intel WiFi Link 5100                                                    | 42        | 1.73%   |
| Intel Wi-Fi 6 AX200                                                     | 42        | 1.73%   |
| Intel Wireless 8260                                                     | 36        | 1.49%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 1.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 31        | 1.28%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 30        | 1.24%   |
| Intel Centrino Ultimate-N 6300                                          | 28        | 1.16%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 27        | 1.11%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 26        | 1.07%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 26        | 1.07%   |
| Intel Wi-Fi 6 AX201                                                     | 26        | 1.07%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 25        | 1.03%   |
| Intel Wireless 3160                                                     | 25        | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 24        | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 21        | 0.87%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 21        | 0.87%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 20        | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 20        | 0.83%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 20        | 0.83%   |
| Intel Centrino Wireless-N 2230                                          | 19        | 0.78%   |
| Intel Centrino Advanced-N 6235                                          | 19        | 0.78%   |
| Intel Centrino Advanced-N 6200                                          | 19        | 0.78%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 18        | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1012      | 50.45%  |
| Intel                                  | 368       | 18.34%  |
| Qualcomm Atheros                       | 177       | 8.82%   |
| Broadcom                               | 136       | 6.78%   |
| Marvell Technology Group               | 70        | 3.49%   |
| Broadcom Limited                       | 42        | 2.09%   |
| Nvidia                                 | 35        | 1.74%   |
| Silicon Integrated Systems [SiS]       | 24        | 1.2%    |
| ASIX Electronics                       | 22        | 1.1%    |
| JMicron Technology                     | 20        | 1%      |
| Samsung Electronics                    | 18        | 0.9%    |
| Xiaomi                                 | 14        | 0.7%    |
| DisplayLink                            | 11        | 0.55%   |
| VIA Technologies                       | 9         | 0.45%   |
| TP-Link                                | 6         | 0.3%    |
| OPPO Electronics                       | 6         | 0.3%    |
| Huawei Technologies                    | 6         | 0.3%    |
| Attansic Technology                    | 6         | 0.3%    |
| Motorola PCS                           | 5         | 0.25%   |
| Qualcomm                               | 3         | 0.15%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.1%    |
| MediaTek                               | 2         | 0.1%    |
| Davicom Semiconductor                  | 2         | 0.1%    |
| T & A Mobile Phones                    | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Novatel Wireless                       | 1         | 0.05%   |
| Motorola BCS                           | 1         | 0.05%   |
| Lenovo                                 | 1         | 0.05%   |
| ICS Advent                             | 1         | 0.05%   |
| HMD Global                             | 1         | 0.05%   |
| Hewlett-Packard                        | 1         | 0.05%   |
| D-Link                                 | 1         | 0.05%   |
| ASUSTek Computer                       | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 583       | 28.95%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 346       | 17.18%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 97        | 4.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 35        | 1.74%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 32        | 1.59%   |
| Intel 82567LM Gigabit Network Connection                          | 28        | 1.39%   |
| Intel Ethernet Connection I218-LM                                 | 27        | 1.34%   |
| Intel Ethernet Connection I217-LM                                 | 27        | 1.34%   |
| Intel 82577LM Gigabit Network Connection                          | 27        | 1.34%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 23        | 1.14%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 1.14%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 22        | 1.09%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 22        | 1.09%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 21        | 1.04%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 1.04%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 0.99%   |
| Intel 82566MM Gigabit Network Connection                          | 19        | 0.94%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 18        | 0.89%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 17        | 0.84%   |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 0.79%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 15        | 0.74%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 14        | 0.7%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 13        | 0.65%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 12        | 0.6%    |
| Nvidia MCP67 Ethernet                                             | 12        | 0.6%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 12        | 0.6%    |
| Intel Ethernet Connection (3) I218-LM                             | 12        | 0.6%    |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 12        | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 12        | 0.6%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11        | 0.55%   |
| Nvidia MCP79 Ethernet                                             | 11        | 0.55%   |
| Intel PRO/100 VE Network Connection                               | 11        | 0.55%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 11        | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10        | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.5%    |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 10        | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 9         | 0.45%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2236      | 52.62%  |
| Ethernet | 1938      | 45.61%  |
| Modem    | 70        | 1.65%   |
| Unknown  | 5         | 0.12%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1868      | 77.64%  |
| Ethernet | 537       | 22.32%  |
| Unknown  | 1         | 0.04%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1798      | 77.73%  |
| 1     | 417       | 18.03%  |
| 0     | 89        | 3.85%   |
| 3     | 9         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1873      | 80.08%  |
| Yes  | 466       | 19.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 502       | 33.69%  |
| Qualcomm Atheros Communications | 195       | 13.09%  |
| Realtek Semiconductor           | 172       | 11.54%  |
| Broadcom                        | 127       | 8.52%   |
| IMC Networks                    | 70        | 4.7%    |
| Lite-On Technology              | 62        | 4.16%   |
| Dell                            | 57        | 3.83%   |
| Hewlett-Packard                 | 52        | 3.49%   |
| Foxconn / Hon Hai               | 51        | 3.42%   |
| Apple                           | 48        | 3.22%   |
| Toshiba                         | 31        | 2.08%   |
| Cambridge Silicon Radio         | 26        | 1.74%   |
| Ralink                          | 20        | 1.34%   |
| ASUSTek Computer                | 15        | 1.01%   |
| Alps Electric                   | 12        | 0.81%   |
| Realtek                         | 11        | 0.74%   |
| Foxconn International           | 10        | 0.67%   |
| Askey Computer                  | 6         | 0.4%    |
| Taiyo Yuden                     | 4         | 0.27%   |
| Ralink Technology               | 4         | 0.27%   |
| Dynex                           | 3         | 0.2%    |
| Chicony Electronics             | 3         | 0.2%    |
| Qcom                            | 2         | 0.13%   |
| MediaTek                        | 2         | 0.13%   |
| Integrated System Solution      | 2         | 0.13%   |
| TP-Link                         | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 264       | 17.69%  |
| Realtek Bluetooth Radio                             | 107       | 7.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 84        | 5.63%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 59        | 3.95%   |
| Intel AX201 Bluetooth                               | 54        | 3.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 53        | 3.55%   |
| Intel AX200 Bluetooth                               | 42        | 2.82%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 35        | 2.35%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 33        | 2.21%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 29        | 1.94%   |
| IMC Networks Bluetooth Device                       | 28        | 1.88%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 28        | 1.88%   |
| Apple Bluetooth Host Controller                     | 28        | 1.88%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 26        | 1.74%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 1.68%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 21        | 1.41%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 21        | 1.41%   |
| Ralink RT3290 Bluetooth                             | 20        | 1.34%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 1.27%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 18        | 1.21%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 17        | 1.14%   |
| IMC Networks Bluetooth Radio                        | 16        | 1.07%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 1.07%   |
| Dell DW375 Bluetooth Module                         | 15        | 1.01%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 15        | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 12        | 0.8%    |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 0.8%    |
| Dell Wireless 365 Bluetooth                         | 12        | 0.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.8%    |
| Realtek Bluetooth Radio                             | 11        | 0.74%   |
| Intel AX210 Bluetooth                               | 11        | 0.74%   |
| Foxconn International BCM43142A0 Bluetooth module   | 10        | 0.67%   |
| Dell BCM20702A0 Bluetooth Module                    | 10        | 0.67%   |
| Broadcom BCM2045 Bluetooth                          | 10        | 0.67%   |
| Lite-On Bluetooth Device                            | 9         | 0.6%    |
| IMC Networks Wireless_Device                        | 9         | 0.6%    |
| Toshiba Bluetooth Device                            | 8         | 0.54%   |
| Realtek RTL8723B Bluetooth                          | 8         | 0.54%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 8         | 0.54%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1813      | 70.16%  |
| AMD                                  | 414       | 16.02%  |
| Nvidia                               | 257       | 9.95%   |
| Silicon Integrated Systems [SiS]     | 27        | 1.04%   |
| VIA Technologies                     | 10        | 0.39%   |
| C-Media Electronics                  | 9         | 0.35%   |
| Tenx Technology                      | 5         | 0.19%   |
| Generalplus Technology               | 5         | 0.19%   |
| Realtek Semiconductor                | 4         | 0.15%   |
| Creative Technology                  | 4         | 0.15%   |
| Texas Instruments                    | 3         | 0.12%   |
| SteelSeries ApS                      | 3         | 0.12%   |
| GN Netcom                            | 3         | 0.12%   |
| Yamaha                               | 2         | 0.08%   |
| Logitech                             | 2         | 0.08%   |
| Lenovo                               | 2         | 0.08%   |
| Focusrite-Novation                   | 2         | 0.08%   |
| DCMT Technology                      | 2         | 0.08%   |
| ZOOM                                 | 1         | 0.04%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.04%   |
| Syntek                               | 1         | 0.04%   |
| Sony                                 | 1         | 0.04%   |
| Sennheiser Communications            | 1         | 0.04%   |
| Roland                               | 1         | 0.04%   |
| Razer USA                            | 1         | 0.04%   |
| PreSonus Audio Electronics           | 1         | 0.04%   |
| Plantronics                          | 1         | 0.04%   |
| OPPO Electronics                     | 1         | 0.04%   |
| JMTek                                | 1         | 0.04%   |
| Hewlett-Packard                      | 1         | 0.04%   |
| DSEA A/S                             | 1         | 0.04%   |
| Corsair                              | 1         | 0.04%   |
| Conexant Systems                     | 1         | 0.04%   |
| CMX Systems                          | 1         | 0.04%   |
| AKAI Professional M.I.               | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 218       | 6.97%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 193       | 6.17%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 183       | 5.85%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 156       | 4.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 134       | 4.28%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 131       | 4.19%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 115       | 3.68%   |
| Intel 8 Series HD Audio Controller                                                                | 114       | 3.64%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 110       | 3.52%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 109       | 3.48%   |
| AMD FCH Azalia Controller                                                                         | 109       | 3.48%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 75        | 2.4%    |
| AMD Kabini HDMI/DP Audio                                                                          | 67        | 2.14%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 66        | 2.11%   |
| Intel Broadwell-U Audio Controller                                                                | 66        | 2.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 64        | 2.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 59        | 1.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 56        | 1.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 53        | 1.69%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 50        | 1.6%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 48        | 1.53%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 44        | 1.41%   |
| AMD High Definition Audio Controller                                                              | 43        | 1.37%   |
| Intel Cannon Lake PCH cAVS                                                                        | 41        | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 38        | 1.21%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 38        | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 37        | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 32        | 1.02%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 29        | 0.93%   |
| Intel CM238 HD Audio Controller                                                                   | 28        | 0.9%    |
| AMD Wrestler HDMI Audio                                                                           | 28        | 0.9%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 27        | 0.86%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 24        | 0.77%   |
| AMD Trinity HDMI Audio Controller                                                                 | 23        | 0.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 22        | 0.7%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 21        | 0.67%   |
| Nvidia High Definition Audio Controller                                                           | 20        | 0.64%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 20        | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 17        | 0.54%   |
| Intel Comet Lake PCH cAVS                                                                         | 17        | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 132       | 25.19%  |
| SK hynix            | 127       | 24.24%  |
| Micron Technology   | 59        | 11.26%  |
| Unknown             | 53        | 10.11%  |
| Kingston            | 40        | 7.63%   |
| Unknown (ABCD)      | 16        | 3.05%   |
| Nanya Technology    | 15        | 2.86%   |
| Crucial             | 12        | 2.29%   |
| A-DATA Technology   | 12        | 2.29%   |
| Elpida              | 10        | 1.91%   |
| Ramaxel Technology  | 8         | 1.53%   |
| Smart               | 4         | 0.76%   |
| Qimonda             | 4         | 0.76%   |
| Transcend           | 2         | 0.38%   |
| Timetec             | 2         | 0.38%   |
| Team                | 2         | 0.38%   |
| Patriot             | 2         | 0.38%   |
| High Bridge         | 2         | 0.38%   |
| Corsair             | 2         | 0.38%   |
| Walton Chaintech    | 1         | 0.19%   |
| Unknown (08B5)      | 1         | 0.19%   |
| Toshiba             | 1         | 0.19%   |
| Teikon              | 1         | 0.19%   |
| Strontium           | 1         | 0.19%   |
| Smart Brazil        | 1         | 0.19%   |
| SHARETRONIC         | 1         | 0.19%   |
| PUSKILL             | 1         | 0.19%   |
| Netlist             | 1         | 0.19%   |
| Nayna               | 1         | 0.19%   |
| Kingmax             | 1         | 0.19%   |
| HBS                 | 1         | 0.19%   |
| GSkill              | 1         | 0.19%   |
| G.Skill             | 1         | 0.19%   |
| Essencore           | 1         | 0.19%   |
| CSX                 | 1         | 0.19%   |
| COS Memory          | 1         | 0.19%   |
| Axiom               | 1         | 0.19%   |
| Avant               | 1         | 0.19%   |
| Unknown             | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 14        | 2.5%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 1.43%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 1.43%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 1.43%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 1.25%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 800MT/s          | 6         | 1.07%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 6         | 1.07%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 6         | 1.07%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.89%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.71%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.71%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 4         | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.71%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 4         | 0.71%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.71%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 3         | 0.54%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 3         | 0.54%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 3         | 0.54%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.54%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.54%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.54%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.54%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.54%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.54%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.54%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.54%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 3         | 0.54%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 3         | 0.54%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.54%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 3         | 0.54%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 3         | 0.54%   |
| Kingston RAM ACR16D3LS1KFG/4G 4GB SODIMM DDR3 1600MT/s           | 3         | 0.54%   |
| Kingston RAM 99U5428-040.A01LF 4GB SODIMM DDR3 1334MT/s          | 3         | 0.54%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 174       | 39.37%  |
| DDR4    | 139       | 31.45%  |
| DDR2    | 58        | 13.12%  |
| LPDDR4  | 26        | 5.88%   |
| SDRAM   | 19        | 4.3%    |
| LPDDR3  | 11        | 2.49%   |
| DRAM    | 6         | 1.36%   |
| DDR     | 5         | 1.13%   |
| Unknown | 4         | 0.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 390       | 89.45%  |
| Row Of Chips | 33        | 7.57%   |
| DIMM         | 9         | 2.06%   |
| Chip         | 3         | 0.69%   |
| Unknown      | 1         | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 166       | 33.27%  |
| 8192  | 140       | 28.06%  |
| 2048  | 109       | 21.84%  |
| 1024  | 40        | 8.02%   |
| 16384 | 27        | 5.41%   |
| 512   | 11        | 2.2%    |
| 32768 | 4         | 0.8%    |
| 256   | 2         | 0.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 116       | 23.82%  |
| 2667    | 70        | 14.37%  |
| 3200    | 45        | 9.24%   |
| 2400    | 37        | 7.6%    |
| 667     | 33        | 6.78%   |
| 1334    | 32        | 6.57%   |
| 1333    | 23        | 4.72%   |
| Unknown | 23        | 4.72%   |
| 2133    | 19        | 3.9%    |
| 1066    | 14        | 2.87%   |
| 533     | 10        | 2.05%   |
| 4199    | 9         | 1.85%   |
| 975     | 9         | 1.85%   |
| 800     | 9         | 1.85%   |
| 3266    | 8         | 1.64%   |
| 4267    | 7         | 1.44%   |
| 2048    | 6         | 1.23%   |
| 8400    | 3         | 0.62%   |
| 1867    | 3         | 0.62%   |
| 1067    | 3         | 0.62%   |
| 400     | 3         | 0.62%   |
| 4800    | 1         | 0.21%   |
| 4266    | 1         | 0.21%   |
| 3733    | 1         | 0.21%   |
| 2933    | 1         | 0.21%   |
| 1639    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 42.31%  |
| Canon                 | 5         | 19.23%  |
| Seiko Epson           | 3         | 11.54%  |
| Samsung Electronics   | 2         | 7.69%   |
| Brother Industries    | 2         | 7.69%   |
| Zebra                 | 1         | 3.85%   |
| STMicroelectronics    | 1         | 3.85%   |
| Lexmark International | 1         | 3.85%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| HP ENVY Photo 6200 series                                 | 2         | 7.69%   |
| HP DeskJet 1110 series                                    | 2         | 7.69%   |
| Zebra ZP 450 Printer                                      | 1         | 3.85%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 3.85%   |
| Seiko Epson WF-2010 Series                                | 1         | 3.85%   |
| Seiko Epson Printer                                       | 1         | 3.85%   |
| Seiko Epson L3110 Series                                  | 1         | 3.85%   |
| Samsung M2020 Series                                      | 1         | 3.85%   |
| Samsung CLX-3300 Series                                   | 1         | 3.85%   |
| Lexmark International 2400 series                         | 1         | 3.85%   |
| HP Laserjet P1505                                         | 1         | 3.85%   |
| HP LaserJet 1200                                          | 1         | 3.85%   |
| HP LaserJet 1020                                          | 1         | 3.85%   |
| HP LaserJet 1000                                          | 1         | 3.85%   |
| HP DeskJet 2700 series                                    | 1         | 3.85%   |
| HP DeskJet 2300 series                                    | 1         | 3.85%   |
| HP Deskjet 1510                                           | 1         | 3.85%   |
| Canon TS3100 series                                       | 1         | 3.85%   |
| Canon PIXMA MX340                                         | 1         | 3.85%   |
| Canon PIXMA MG3600 Series                                 | 1         | 3.85%   |
| Canon PIXMA MG3000 series                                 | 1         | 3.85%   |
| Canon MG2100 series                                       | 1         | 3.85%   |
| Brother MFC-L2730DW series                                | 1         | 3.85%   |
| Brother DCP-T300                                          | 1         | 3.85%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Canon       | 3         | 60%     |
| Seiko Epson | 2         | 40%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 40%     |
| Canon CanoScan LiDE 90                      | 1         | 20%     |
| Canon CanoScan LIDE 25                      | 1         | 20%     |
| Canon CanoScan LiDE 200                     | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 488       | 26.39%  |
| Microdia                               | 173       | 9.36%   |
| Realtek Semiconductor                  | 153       | 8.27%   |
| IMC Networks                           | 144       | 7.79%   |
| Acer                                   | 122       | 6.6%    |
| Suyin                                  | 104       | 5.62%   |
| Sunplus Innovation Technology          | 104       | 5.62%   |
| Cheng Uei Precision Industry (Foxlink) | 87        | 4.71%   |
| Quanta                                 | 70        | 3.79%   |
| Apple                                  | 48        | 2.6%    |
| Silicon Motion                         | 45        | 2.43%   |
| Syntek                                 | 42        | 2.27%   |
| Lite-On Technology                     | 33        | 1.78%   |
| Alcor Micro                            | 32        | 1.73%   |
| Ricoh                                  | 31        | 1.68%   |
| Importek                               | 17        | 0.92%   |
| ALi                                    | 16        | 0.87%   |
| Samsung Electronics                    | 13        | 0.7%    |
| Primax Electronics                     | 13        | 0.7%    |
| USB Camera                             | 10        | 0.54%   |
| Luxvisions Innotech Limited            | 10        | 0.54%   |
| Z-Star Microelectronics                | 9         | 0.49%   |
| OmniVision Technologies                | 8         | 0.43%   |
| Logitech                               | 8         | 0.43%   |
| Lenovo                                 | 8         | 0.43%   |
| GEMBIRD                                | 8         | 0.43%   |
| Sonix Technology                       | 5         | 0.27%   |
| Genesys Logic                          | 5         | 0.27%   |
| DJKANA19IDX53W                         | 5         | 0.27%   |
| Sunplus Technology                     | 4         | 0.22%   |
| SunplusIT                              | 3         | 0.16%   |
| Generalplus Technology                 | 3         | 0.16%   |
| ARC International                      | 3         | 0.16%   |
| YGTek                                  | 2         | 0.11%   |
| Microsoft                              | 2         | 0.11%   |
| LG Electronics                         | 2         | 0.11%   |
| Huawei Technologies                    | 2         | 0.11%   |
| Y Media                                | 1         | 0.05%   |
| Unknown                                | 1         | 0.05%   |
| Trust                                  | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 54        | 2.91%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 34        | 1.83%   |
| Microdia Integrated_Webcam_HD                           | 32        | 1.73%   |
| Microdia Integrated Webcam                              | 32        | 1.73%   |
| Realtek Integrated_Webcam_HD                            | 30        | 1.62%   |
| Chicony HP TrueVision HD                                | 29        | 1.57%   |
| Realtek USB Camera                                      | 26        | 1.4%    |
| Chicony HD WebCam                                       | 26        | 1.4%    |
| Acer Lenovo EasyCamera                                  | 26        | 1.4%    |
| Chicony TOSHIBA Web Camera - HD                         | 24        | 1.3%    |
| Chicony USB 2.0 Camera                                  | 23        | 1.24%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 22        | 1.19%   |
| Acer Integrated Camera                                  | 22        | 1.19%   |
| Chicony HP TrueVision HD Camera                         | 21        | 1.13%   |
| Sunplus Integrated_Webcam_HD                            | 19        | 1.03%   |
| Chicony HP HD Webcam                                    | 18        | 0.97%   |
| Syntek Integrated Camera                                | 17        | 0.92%   |
| Sunplus HD WebCam                                       | 17        | 0.92%   |
| Chicony Lenovo EasyCamera                               | 17        | 0.92%   |
| Chicony EasyCamera                                      | 17        | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 17        | 0.92%   |
| Apple iPhone 5/5C/5S/6/SE                               | 17        | 0.92%   |
| Suyin HP Truevision HD                                  | 16        | 0.86%   |
| Realtek Integrated Webcam                               | 16        | 0.86%   |
| Chicony VGA Webcam                                      | 15        | 0.81%   |
| Chicony CNF9055 Toshiba Webcam                          | 15        | 0.81%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 14        | 0.76%   |
| Quanta HP Webcam                                        | 14        | 0.76%   |
| IMC Networks Integrated Camera                          | 14        | 0.76%   |
| Chicony USB2.0 VGA UVC WebCam                           | 14        | 0.76%   |
| ALi Gateway Webcam                                      | 14        | 0.76%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 13        | 0.7%    |
| Microdia Sonix USB 2.0 Camera                           | 13        | 0.7%    |
| Microdia Laptop_Integrated_Webcam_HD                    | 13        | 0.7%    |
| Chicony USB2.0 HD UVC WebCam                            | 13        | 0.7%    |
| Chicony HP Webcam                                       | 13        | 0.7%    |
| Apple FaceTime HD Camera                                | 13        | 0.7%    |
| Alcor Micro USB 2.0 Camera                              | 13        | 0.7%    |
| Quanta HP TrueVision HD Camera                          | 12        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 12        | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 149       | 46.86%  |
| AuthenTec                  | 53        | 16.67%  |
| Upek                       | 29        | 9.12%   |
| Shenzhen Goodix Technology | 28        | 8.81%   |
| Synaptics                  | 18        | 5.66%   |
| STMicroelectronics         | 17        | 5.35%   |
| Elan Microelectronics      | 15        | 4.72%   |
| LighTuning Technology      | 7         | 2.2%    |
| Samsung Electronics        | 1         | 0.31%   |
| Focal-systems.Corp         | 1         | 0.31%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 34        | 10.69%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 8.81%   |
| Shenzhen Goodix  FingerPrint Device                                        | 20        | 6.29%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 19        | 5.97%   |
| STMicroelectronics Fingerprint Reader                                      | 17        | 5.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 5.03%   |
| AuthenTec AES2810                                                          | 16        | 5.03%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 4.72%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 15        | 4.72%   |
| Validity Sensors Fingerprint scanner                                       | 14        | 4.4%    |
| Validity Sensors VFS491                                                    | 12        | 3.77%   |
| AuthenTec AES1600                                                          | 9         | 2.83%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.52%   |
| Elan ELAN:ARM-M4                                                           | 8         | 2.52%   |
| Elan ELAN:Fingerprint                                                      | 7         | 2.2%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.89%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.89%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.57%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 5         | 1.57%   |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 1.57%   |
| Unknown                                                                    | 5         | 1.57%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.26%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.26%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 1.26%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 1.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.26%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 1.26%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 0.94%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.94%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.94%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.63%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.63%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.63%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.31%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.31%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.31%   |
| Synaptics  WBDI                                                            | 1         | 0.31%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 0.31%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.31%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 72        | 52.55%  |
| O2 Micro                          | 21        | 15.33%  |
| Alcor Micro                       | 21        | 15.33%  |
| Lenovo                            | 8         | 5.84%   |
| Upek                              | 7         | 5.11%   |
| Yubico.com                        | 2         | 1.46%   |
| SCM Microsystems                  | 2         | 1.46%   |
| Realtek Semiconductor             | 2         | 1.46%   |
| VASCO Data Security International | 1         | 0.73%   |
| OmniKey                           | 1         | 0.73%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 36        | 26.28%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 14.6%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 19        | 13.87%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 12.41%  |
| Broadcom 5880                                                                | 14        | 10.22%  |
| Lenovo Integrated Smart Card Reader                                          | 8         | 5.84%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 5.11%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 2.92%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.46%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.46%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.46%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.46%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.73%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.73%   |
| Broadcom 58200                                                               | 1         | 0.73%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.73%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1540      | 65.64%  |
| 1     | 643       | 27.41%  |
| 2     | 149       | 6.35%   |
| 3     | 12        | 0.51%   |
| 7     | 1         | 0.04%   |
| 4     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 312       | 32.74%  |
| Graphics card            | 181       | 18.99%  |
| Chipcard                 | 128       | 13.43%  |
| Net/wireless             | 122       | 12.8%   |
| Multimedia controller    | 55        | 5.77%   |
| Storage                  | 34        | 3.57%   |
| Modem                    | 31        | 3.25%   |
| Bluetooth                | 27        | 2.83%   |
| Sound                    | 13        | 1.36%   |
| Flash memory             | 11        | 1.15%   |
| Camera                   | 10        | 1.05%   |
| Communication controller | 9         | 0.94%   |
| Net/ethernet             | 6         | 0.63%   |
| Card reader              | 5         | 0.52%   |
| Network                  | 3         | 0.31%   |
| Storage/nvme             | 2         | 0.21%   |
| Unclassified device      | 1         | 0.1%    |
| Storage/ide              | 1         | 0.1%    |
| Storage/ata              | 1         | 0.1%    |
| Dvb card                 | 1         | 0.1%    |

