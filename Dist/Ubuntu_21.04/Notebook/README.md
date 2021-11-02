Ubuntu 21.04 - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for Ubuntu 21.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=ubuntu-21.04

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | 15                          | [ab5e53c9ed](https://linux-hardware.org/?probe=ab5e53c9ed) | Nov 01, 2021 |
| Apple         | MacBookPro9,2               | [783d081b5a](https://linux-hardware.org/?probe=783d081b5a) | Oct 31, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | [26adc81160](https://linux-hardware.org/?probe=26adc81160) | Oct 30, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [ff8c85568e](https://linux-hardware.org/?probe=ff8c85568e) | Oct 29, 2021 |
| Lenovo        | ThinkPad T15g Gen 1 20UR... | [6ae3033841](https://linux-hardware.org/?probe=6ae3033841) | Oct 28, 2021 |
| Dell          | XPS 15 9510                 | [27f4b2412f](https://linux-hardware.org/?probe=27f4b2412f) | Oct 27, 2021 |
| HUAWEI        | HN-WX9X                     | [c62bb4adc9](https://linux-hardware.org/?probe=c62bb4adc9) | Oct 27, 2021 |
| Lenovo        | ThinkPad E490 20N80010RT    | [3fc424b8c6](https://linux-hardware.org/?probe=3fc424b8c6) | Oct 27, 2021 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [cc4c888046](https://linux-hardware.org/?probe=cc4c888046) | Oct 27, 2021 |
| HP            | Laptop 15-bs2xx             | [d0f14fd899](https://linux-hardware.org/?probe=d0f14fd899) | Oct 26, 2021 |
| HP            | Laptop 15-bs2xx             | [44a5ff781e](https://linux-hardware.org/?probe=44a5ff781e) | Oct 26, 2021 |
| Dell          | Precision 7760              | [574b87362f](https://linux-hardware.org/?probe=574b87362f) | Oct 26, 2021 |
| Acer          | AO722                       | [832ca83fcd](https://linux-hardware.org/?probe=832ca83fcd) | Oct 25, 2021 |
| HP            | Laptop 15s-du1xxx           | [23c770232c](https://linux-hardware.org/?probe=23c770232c) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | [1f26867986](https://linux-hardware.org/?probe=1f26867986) | Oct 25, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [338ddd258e](https://linux-hardware.org/?probe=338ddd258e) | Oct 24, 2021 |
| HP            | ProBook 4540s               | [49ce392cd2](https://linux-hardware.org/?probe=49ce392cd2) | Oct 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [9b3e361eb7](https://linux-hardware.org/?probe=9b3e361eb7) | Oct 24, 2021 |
| HP            | Laptop 15-da0xxx            | [2de5c74bc0](https://linux-hardware.org/?probe=2de5c74bc0) | Oct 23, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e9991e486b](https://linux-hardware.org/?probe=e9991e486b) | Oct 23, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [16268db25b](https://linux-hardware.org/?probe=16268db25b) | Oct 22, 2021 |
| Dell          | Latitude E7470              | [96ef0ee68c](https://linux-hardware.org/?probe=96ef0ee68c) | Oct 22, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | [c7d518ca51](https://linux-hardware.org/?probe=c7d518ca51) | Oct 22, 2021 |
| HP            | Stream Laptop               | [95df1a4e45](https://linux-hardware.org/?probe=95df1a4e45) | Oct 22, 2021 |
| Acer          | Aspire ES1-111              | [98323be6f8](https://linux-hardware.org/?probe=98323be6f8) | Oct 22, 2021 |
| Acer          | NG-AN515-51-522Q            | [e4762b54f7](https://linux-hardware.org/?probe=e4762b54f7) | Oct 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [3fe556cde3](https://linux-hardware.org/?probe=3fe556cde3) | Oct 21, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [0413ebb72c](https://linux-hardware.org/?probe=0413ebb72c) | Oct 21, 2021 |
| Toshiba       | Satellite C850-19Z          | [9f60594657](https://linux-hardware.org/?probe=9f60594657) | Oct 21, 2021 |
| Toshiba       | Satellite C850-19Z          | [33c3868a32](https://linux-hardware.org/?probe=33c3868a32) | Oct 21, 2021 |
| Toshiba       | Satellite Pro C850-1G8      | [37b87b5c45](https://linux-hardware.org/?probe=37b87b5c45) | Oct 21, 2021 |
| Dell          | Latitude 5400               | [6a14ed2d5e](https://linux-hardware.org/?probe=6a14ed2d5e) | Oct 21, 2021 |
| Dell          | Latitude E6420              | [4c3c43daaa](https://linux-hardware.org/?probe=4c3c43daaa) | Oct 20, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [f1449188a9](https://linux-hardware.org/?probe=f1449188a9) | Oct 20, 2021 |
| ASUSTek       | U56E                        | [a610876405](https://linux-hardware.org/?probe=a610876405) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | [2db5d6dc7c](https://linux-hardware.org/?probe=2db5d6dc7c) | Oct 20, 2021 |
| HP            | ProBook 450 G7              | [1faf3f28e5](https://linux-hardware.org/?probe=1faf3f28e5) | Oct 20, 2021 |
| Lenovo        | G40-70 20369                | [c8606a3a2a](https://linux-hardware.org/?probe=c8606a3a2a) | Oct 20, 2021 |
| ASUSTek       | K72F                        | [0eedfc8a67](https://linux-hardware.org/?probe=0eedfc8a67) | Oct 20, 2021 |
| Lenovo        | ThinkPad E14 20RAS1M600     | [a14a745c3a](https://linux-hardware.org/?probe=a14a745c3a) | Oct 19, 2021 |
| HP            | Notebook                    | [ff690977bf](https://linux-hardware.org/?probe=ff690977bf) | Oct 19, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [a174c1781d](https://linux-hardware.org/?probe=a174c1781d) | Oct 19, 2021 |
| Dell          | Latitude E4300              | [127b65224f](https://linux-hardware.org/?probe=127b65224f) | Oct 18, 2021 |
| Framework     | Laptop                      | [591c9d1d8f](https://linux-hardware.org/?probe=591c9d1d8f) | Oct 18, 2021 |
| Dell          | XPS 15 7590                 | [c61bb65266](https://linux-hardware.org/?probe=c61bb65266) | Oct 18, 2021 |
| Fujitsu       | LIFEBOOK E752               | [4768b805ff](https://linux-hardware.org/?probe=4768b805ff) | Oct 17, 2021 |
| Dell          | Latitude E6400              | [fbc4bfa1b0](https://linux-hardware.org/?probe=fbc4bfa1b0) | Oct 16, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [214d892f21](https://linux-hardware.org/?probe=214d892f21) | Oct 16, 2021 |
| Fujitsu       | LIFEBOOK E752               | [2d7b0ea475](https://linux-hardware.org/?probe=2d7b0ea475) | Oct 16, 2021 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [a4d3e13675](https://linux-hardware.org/?probe=a4d3e13675) | Oct 16, 2021 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [19105d9255](https://linux-hardware.org/?probe=19105d9255) | Oct 16, 2021 |
| Acer          | Aspire 7715Z                | [d2b159ed70](https://linux-hardware.org/?probe=d2b159ed70) | Oct 16, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0180... | [da345e8de3](https://linux-hardware.org/?probe=da345e8de3) | Oct 15, 2021 |
| Dell          | Latitude E4300              | [81efc2581c](https://linux-hardware.org/?probe=81efc2581c) | Oct 15, 2021 |
| Lenovo        | G550 2958                   | [570b8131d1](https://linux-hardware.org/?probe=570b8131d1) | Oct 15, 2021 |
| Dell          | XPS 13 9310                 | [f04cc5e7a8](https://linux-hardware.org/?probe=f04cc5e7a8) | Oct 15, 2021 |
| Toshiba       | PORTEGE R830                | [06223f6db9](https://linux-hardware.org/?probe=06223f6db9) | Oct 15, 2021 |
| HP            | ProBook 4540s               | [046acc5982](https://linux-hardware.org/?probe=046acc5982) | Oct 14, 2021 |
| Google        | Treeya                      | [6c10b9bcb3](https://linux-hardware.org/?probe=6c10b9bcb3) | Oct 14, 2021 |
| Durabook      | S14AT                       | [60d38664ee](https://linux-hardware.org/?probe=60d38664ee) | Oct 14, 2021 |
| Alienware     | 17 R3                       | [0f1a877034](https://linux-hardware.org/?probe=0f1a877034) | Oct 13, 2021 |
| HP            | G42                         | [52ade78428](https://linux-hardware.org/?probe=52ade78428) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [df32df0b62](https://linux-hardware.org/?probe=df32df0b62) | Oct 13, 2021 |
| HP            | Laptop 15s-du1xxx           | [6b3505b5f2](https://linux-hardware.org/?probe=6b3505b5f2) | Oct 13, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | [c7239a1379](https://linux-hardware.org/?probe=c7239a1379) | Oct 13, 2021 |
| Sony          | SVE14126CXB                 | [acf29b49fd](https://linux-hardware.org/?probe=acf29b49fd) | Oct 13, 2021 |
| Dell          | XPS 13 9310                 | [20dc49f637](https://linux-hardware.org/?probe=20dc49f637) | Oct 13, 2021 |
| Wortmann      | TERRA_MOBILE_1541H          | [28dd4b8caf](https://linux-hardware.org/?probe=28dd4b8caf) | Oct 13, 2021 |
| Toshiba       | Satellite C850-19Z          | [59617db66a](https://linux-hardware.org/?probe=59617db66a) | Oct 13, 2021 |
| Acer          | Aspire 5741G                | [69b1b6e13e](https://linux-hardware.org/?probe=69b1b6e13e) | Oct 12, 2021 |
| Lenovo        | ThinkPad X260 20F5S08N00    | [c8e9d8e7a9](https://linux-hardware.org/?probe=c8e9d8e7a9) | Oct 12, 2021 |
| Apple         | MacBook7,1                  | [450992ab23](https://linux-hardware.org/?probe=450992ab23) | Oct 12, 2021 |
| HP            | Laptop 15-bs2xx             | [cc04e66dc0](https://linux-hardware.org/?probe=cc04e66dc0) | Oct 12, 2021 |
| Toshiba       | PORTEGE R830                | [b22927e36e](https://linux-hardware.org/?probe=b22927e36e) | Oct 12, 2021 |
| HP            | Notebook                    | [0b5eb78634](https://linux-hardware.org/?probe=0b5eb78634) | Oct 12, 2021 |
| ASUSTek       | ROG Strix G513QC_G513QC     | [80718210cc](https://linux-hardware.org/?probe=80718210cc) | Oct 12, 2021 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | [6047c37a95](https://linux-hardware.org/?probe=6047c37a95) | Oct 11, 2021 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | [3a3c3e4ad6](https://linux-hardware.org/?probe=3a3c3e4ad6) | Oct 11, 2021 |
| Lenovo        | E50-80 80J2                 | [c3d31689ec](https://linux-hardware.org/?probe=c3d31689ec) | Oct 11, 2021 |
| Sony          | SVE1713Y1EB                 | [b59de957b3](https://linux-hardware.org/?probe=b59de957b3) | Oct 11, 2021 |
| Lenovo        | ThinkPad X260 20F5S08N00    | [0d336a4605](https://linux-hardware.org/?probe=0d336a4605) | Oct 11, 2021 |
| Sony          | SVE1713Y1EB                 | [a427a26f34](https://linux-hardware.org/?probe=a427a26f34) | Oct 11, 2021 |
| HP            | EliteBook 830 G8 Noteboo... | [26a075831a](https://linux-hardware.org/?probe=26a075831a) | Oct 11, 2021 |
| Apple         | MacBookPro8,2               | [a3f3c59edc](https://linux-hardware.org/?probe=a3f3c59edc) | Oct 11, 2021 |
| Lenovo        | ThinkPad T410 2522ED2       | [c8c010b75c](https://linux-hardware.org/?probe=c8c010b75c) | Oct 11, 2021 |
| Alienware     | M11x R2                     | [e45fcc146d](https://linux-hardware.org/?probe=e45fcc146d) | Oct 10, 2021 |
| Toshiba       | Satellite L830              | [e8652672c3](https://linux-hardware.org/?probe=e8652672c3) | Oct 10, 2021 |
| Toshiba       | Satellite M305D             | [1ef98af428](https://linux-hardware.org/?probe=1ef98af428) | Oct 10, 2021 |
| Toshiba       | Satellite M305D             | [1b61cfb354](https://linux-hardware.org/?probe=1b61cfb354) | Oct 10, 2021 |
| Unknown       | Unknown                     | [1fe376939c](https://linux-hardware.org/?probe=1fe376939c) | Oct 10, 2021 |
| Lenovo        | ThinkPad X260 20F5S08N00    | [f8f9a09e2a](https://linux-hardware.org/?probe=f8f9a09e2a) | Oct 10, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [0ca3ca1067](https://linux-hardware.org/?probe=0ca3ca1067) | Oct 10, 2021 |
| Dell          | Vostro 3401                 | [5e53dc591c](https://linux-hardware.org/?probe=5e53dc591c) | Oct 10, 2021 |
| Dell          | Latitude E4300              | [89506f9460](https://linux-hardware.org/?probe=89506f9460) | Oct 10, 2021 |
| HP            | Pavilion g6                 | [07c4424a4e](https://linux-hardware.org/?probe=07c4424a4e) | Oct 10, 2021 |
| Acer          | Aspire E5-551               | [264e09233b](https://linux-hardware.org/?probe=264e09233b) | Oct 09, 2021 |
| Toshiba       | PORTEGE R830                | [43d48e705c](https://linux-hardware.org/?probe=43d48e705c) | Oct 09, 2021 |
| ASUSTek       | X555DG                      | [a7e80c532d](https://linux-hardware.org/?probe=a7e80c532d) | Oct 09, 2021 |
| HP            | Laptop 15s-fq2xxx           | [e5056b55dd](https://linux-hardware.org/?probe=e5056b55dd) | Oct 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [52a27483b1](https://linux-hardware.org/?probe=52a27483b1) | Oct 09, 2021 |
| Lenovo        | ThinkPad T440p 20AN00DJA... | [0797c0312e](https://linux-hardware.org/?probe=0797c0312e) | Oct 09, 2021 |
| Lenovo        | G50-45 80E3                 | [a0bc3d8be0](https://linux-hardware.org/?probe=a0bc3d8be0) | Oct 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [4fc1c292cb](https://linux-hardware.org/?probe=4fc1c292cb) | Oct 09, 2021 |
| Dell          | Latitude E7250              | [782a17c042](https://linux-hardware.org/?probe=782a17c042) | Oct 09, 2021 |
| Alienware     | M11x R2                     | [a2bb09f85a](https://linux-hardware.org/?probe=a2bb09f85a) | Oct 09, 2021 |
| HP            | Pavilion dv7                | [ba21dd1dd0](https://linux-hardware.org/?probe=ba21dd1dd0) | Oct 08, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [d521223809](https://linux-hardware.org/?probe=d521223809) | Oct 08, 2021 |
| Lenovo        | ThinkPad T420 4236AK9       | [2d3cccc2d0](https://linux-hardware.org/?probe=2d3cccc2d0) | Oct 08, 2021 |
| Dell          | Latitude E5520              | [5cabb513b7](https://linux-hardware.org/?probe=5cabb513b7) | Oct 07, 2021 |
| Dell          | Latitude E4300              | [a897649502](https://linux-hardware.org/?probe=a897649502) | Oct 07, 2021 |
| Dell          | Latitude E5520              | [26bed2c57f](https://linux-hardware.org/?probe=26bed2c57f) | Oct 07, 2021 |
| Sony          | VGN-NW21MF_W                | [3a4e2269af](https://linux-hardware.org/?probe=3a4e2269af) | Oct 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [9b74440deb](https://linux-hardware.org/?probe=9b74440deb) | Oct 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [9e72075ce8](https://linux-hardware.org/?probe=9e72075ce8) | Oct 07, 2021 |
| HP            | EliteBook 840 G2            | [24efeaacb7](https://linux-hardware.org/?probe=24efeaacb7) | Oct 07, 2021 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | [d2088e43b2](https://linux-hardware.org/?probe=d2088e43b2) | Oct 07, 2021 |
| Acer          | Aspire E5-573T              | [749a8c4ccc](https://linux-hardware.org/?probe=749a8c4ccc) | Oct 07, 2021 |
| Dell          | Inspiron 7586               | [2ecf794b47](https://linux-hardware.org/?probe=2ecf794b47) | Oct 07, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [ae154711ac](https://linux-hardware.org/?probe=ae154711ac) | Oct 07, 2021 |
| MSI           | GL63 8RD                    | [9f55f25caf](https://linux-hardware.org/?probe=9f55f25caf) | Oct 07, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [018213b3d3](https://linux-hardware.org/?probe=018213b3d3) | Oct 06, 2021 |
| Acer          | Aspire 5560                 | [6a49f40963](https://linux-hardware.org/?probe=6a49f40963) | Oct 06, 2021 |
| Acer          | Aspire 5560                 | [ac4da0432d](https://linux-hardware.org/?probe=ac4da0432d) | Oct 06, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [ac5c6a0dd6](https://linux-hardware.org/?probe=ac5c6a0dd6) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a68932119c](https://linux-hardware.org/?probe=a68932119c) | Oct 05, 2021 |
| Dell          | XPS 13 7390                 | [843d9a14d4](https://linux-hardware.org/?probe=843d9a14d4) | Oct 05, 2021 |
| Dell          | Latitude 5501               | [633e0959bc](https://linux-hardware.org/?probe=633e0959bc) | Oct 05, 2021 |
| Acer          | Predator PH315-51           | [fb9a605481](https://linux-hardware.org/?probe=fb9a605481) | Oct 05, 2021 |
| Dell          | Inspiron 5775               | [1f37c7ca65](https://linux-hardware.org/?probe=1f37c7ca65) | Oct 05, 2021 |
| Dell          | Inspiron 5775               | [c42e665e24](https://linux-hardware.org/?probe=c42e665e24) | Oct 05, 2021 |
| Acer          | Aspire 4750                 | [b00fc610cd](https://linux-hardware.org/?probe=b00fc610cd) | Oct 05, 2021 |
| HUAWEI        | KLVL-WXX9                   | [c3cccd51c4](https://linux-hardware.org/?probe=c3cccd51c4) | Oct 05, 2021 |
| Dell          | XPS 13 9310                 | [a37e8d930c](https://linux-hardware.org/?probe=a37e8d930c) | Oct 04, 2021 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [9c58f85510](https://linux-hardware.org/?probe=9c58f85510) | Oct 04, 2021 |
| Dell          | Latitude 5290               | [e3afd1ef97](https://linux-hardware.org/?probe=e3afd1ef97) | Oct 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [d9dcb6b432](https://linux-hardware.org/?probe=d9dcb6b432) | Oct 04, 2021 |
| Acer          | Aspire 4750                 | [82560e5d03](https://linux-hardware.org/?probe=82560e5d03) | Oct 04, 2021 |
| Acer          | Aspire 4750                 | [bf7fef3aa9](https://linux-hardware.org/?probe=bf7fef3aa9) | Oct 04, 2021 |
| Fujitsu       | LIFEBOOK S751               | [f34d1166a5](https://linux-hardware.org/?probe=f34d1166a5) | Oct 03, 2021 |
| Dell          | Latitude E4300              | [d6bb983804](https://linux-hardware.org/?probe=d6bb983804) | Oct 03, 2021 |
| Acer          | Aspire A315-31              | [65388cbcfc](https://linux-hardware.org/?probe=65388cbcfc) | Oct 03, 2021 |
| Acer          | Aspire A315-31              | [97dde270fa](https://linux-hardware.org/?probe=97dde270fa) | Oct 03, 2021 |
| Haier         | Y11C                        | [74b9ee5509](https://linux-hardware.org/?probe=74b9ee5509) | Oct 03, 2021 |
| Hampoo        | Cherry Trail CR             | [b95391e679](https://linux-hardware.org/?probe=b95391e679) | Oct 03, 2021 |
| Hampoo        | Cherry Trail CR             | [61c4dc2ac2](https://linux-hardware.org/?probe=61c4dc2ac2) | Oct 03, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [b5e9ab8f07](https://linux-hardware.org/?probe=b5e9ab8f07) | Oct 03, 2021 |
| Dell          | Inspiron 3541               | [43649f98a5](https://linux-hardware.org/?probe=43649f98a5) | Oct 02, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [96264b5cde](https://linux-hardware.org/?probe=96264b5cde) | Oct 02, 2021 |
| HP            | Laptop 15-ra0xx             | [5e542184d8](https://linux-hardware.org/?probe=5e542184d8) | Oct 02, 2021 |
| HP            | Pavilion Laptop 13-bb0xx... | [5a6c7b98c0](https://linux-hardware.org/?probe=5a6c7b98c0) | Oct 02, 2021 |
| Acer          | Predator G3-571             | [de7f48c895](https://linux-hardware.org/?probe=de7f48c895) | Oct 02, 2021 |
| Dell          | Latitude E6430              | [470770630d](https://linux-hardware.org/?probe=470770630d) | Oct 01, 2021 |
| ASUSTek       | G72GX                       | [984966986d](https://linux-hardware.org/?probe=984966986d) | Oct 01, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [a6d1182c1c](https://linux-hardware.org/?probe=a6d1182c1c) | Oct 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [5ac27f4e29](https://linux-hardware.org/?probe=5ac27f4e29) | Oct 01, 2021 |
| HP            | Laptop 15s-fq2xxx           | [b1066885ba](https://linux-hardware.org/?probe=b1066885ba) | Oct 01, 2021 |
| Acer          | Nitro AN515-52              | [a7e79f067e](https://linux-hardware.org/?probe=a7e79f067e) | Sep 30, 2021 |
| Acer          | Swift SF314-54              | [071fdd49c5](https://linux-hardware.org/?probe=071fdd49c5) | Sep 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [6e2173f8b4](https://linux-hardware.org/?probe=6e2173f8b4) | Sep 30, 2021 |
| FUJITSU CL... | U9311                       | [a76f2fbbe3](https://linux-hardware.org/?probe=a76f2fbbe3) | Sep 30, 2021 |
| Acer          | Nitro AN515-52              | [0b2f645654](https://linux-hardware.org/?probe=0b2f645654) | Sep 30, 2021 |
| Dell          | Latitude E6430              | [2438b80ef1](https://linux-hardware.org/?probe=2438b80ef1) | Sep 30, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [6876f0e86d](https://linux-hardware.org/?probe=6876f0e86d) | Sep 29, 2021 |
| HUAWEI        | MACHC-WAX9                  | [ae8aed0f28](https://linux-hardware.org/?probe=ae8aed0f28) | Sep 29, 2021 |
| TrekStor      | SurfTab wintron 7.0 ST70... | [c63b30f0df](https://linux-hardware.org/?probe=c63b30f0df) | Sep 29, 2021 |
| Dell          | XPS 15 9570                 | [cb6b5c443a](https://linux-hardware.org/?probe=cb6b5c443a) | Sep 29, 2021 |
| HP            | EliteBook 820 G1            | [5a23abfa74](https://linux-hardware.org/?probe=5a23abfa74) | Sep 29, 2021 |
| Dell          | Latitude E6540              | [f0552909c1](https://linux-hardware.org/?probe=f0552909c1) | Sep 29, 2021 |
| Dell          | Precision 7760              | [e710ec997f](https://linux-hardware.org/?probe=e710ec997f) | Sep 29, 2021 |
| Minix         | NEO Z83-4A                  | [2a5bd76571](https://linux-hardware.org/?probe=2a5bd76571) | Sep 28, 2021 |
| Dell          | Latitude E6430              | [178e06b47b](https://linux-hardware.org/?probe=178e06b47b) | Sep 28, 2021 |
| HP            | Pavilion dv7                | [9e073b9a8e](https://linux-hardware.org/?probe=9e073b9a8e) | Sep 28, 2021 |
| Lenovo        | IdeaPad 710S Plus-13IKB ... | [4a91c75662](https://linux-hardware.org/?probe=4a91c75662) | Sep 28, 2021 |
| HP            | Laptop 15-bs0xx             | [e9dd5491e8](https://linux-hardware.org/?probe=e9dd5491e8) | Sep 28, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [9fef1cf40f](https://linux-hardware.org/?probe=9fef1cf40f) | Sep 28, 2021 |
| HP            | Laptop 15-bs0xx             | [44d29122aa](https://linux-hardware.org/?probe=44d29122aa) | Sep 28, 2021 |
| Acer          | Aspire A315-31              | [cc2d8f070b](https://linux-hardware.org/?probe=cc2d8f070b) | Sep 28, 2021 |
| Acer          | Aspire A315-31              | [63f7fd3ea6](https://linux-hardware.org/?probe=63f7fd3ea6) | Sep 28, 2021 |
| Dell          | Latitude D620               | [1dc8e001f5](https://linux-hardware.org/?probe=1dc8e001f5) | Sep 28, 2021 |
| Linx          | LINX1010B                   | [5fd6a97443](https://linux-hardware.org/?probe=5fd6a97443) | Sep 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [feed153041](https://linux-hardware.org/?probe=feed153041) | Sep 28, 2021 |
| Haier         | Y11C                        | [591740bf00](https://linux-hardware.org/?probe=591740bf00) | Sep 27, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [691e7c2746](https://linux-hardware.org/?probe=691e7c2746) | Sep 27, 2021 |
| Dell          | Latitude E6430              | [b442a8bd08](https://linux-hardware.org/?probe=b442a8bd08) | Sep 27, 2021 |
| Dell          | Latitude E5470              | [e466f1b4d8](https://linux-hardware.org/?probe=e466f1b4d8) | Sep 27, 2021 |
| ASUSTek       | ROG Strix G732LV_G732LV     | [591896b2ee](https://linux-hardware.org/?probe=591896b2ee) | Sep 27, 2021 |
| HP            | EliteBook 820 G1            | [0646fc1739](https://linux-hardware.org/?probe=0646fc1739) | Sep 27, 2021 |
| Acer          | Aspire A315-31              | [7af0b1b5dd](https://linux-hardware.org/?probe=7af0b1b5dd) | Sep 27, 2021 |
| ASUSTek       | GL553VD                     | [07b1aa0f24](https://linux-hardware.org/?probe=07b1aa0f24) | Sep 27, 2021 |
| ASUSTek       | GL553VD                     | [2cdb257de7](https://linux-hardware.org/?probe=2cdb257de7) | Sep 27, 2021 |
| Toshiba       | Satellite C50-A             | [b1ae9995d6](https://linux-hardware.org/?probe=b1ae9995d6) | Sep 27, 2021 |
| Acer          | Extensa 2509                | [8383547e0a](https://linux-hardware.org/?probe=8383547e0a) | Sep 27, 2021 |
| Fujitsu       | LIFEBOOK T900               | [b8d983bbb2](https://linux-hardware.org/?probe=b8d983bbb2) | Sep 27, 2021 |
| Positivo      | W940TU                      | [0153e89101](https://linux-hardware.org/?probe=0153e89101) | Sep 27, 2021 |
| Fujitsu       | LIFEBOOK T900               | [0ad5cc2ce2](https://linux-hardware.org/?probe=0ad5cc2ce2) | Sep 26, 2021 |
| Positivo      | W940TU                      | [fc44f175b0](https://linux-hardware.org/?probe=fc44f175b0) | Sep 26, 2021 |
| ASUSTek       | GL702VSK                    | [bdc99c7ccb](https://linux-hardware.org/?probe=bdc99c7ccb) | Sep 26, 2021 |
| Dell          | Inspiron 15-3573            | [320d64d26e](https://linux-hardware.org/?probe=320d64d26e) | Sep 26, 2021 |
| Acer          | Nitro AN515-52              | [bb17541aae](https://linux-hardware.org/?probe=bb17541aae) | Sep 26, 2021 |
| HP            | EliteBook 2170p             | [58e81067e0](https://linux-hardware.org/?probe=58e81067e0) | Sep 26, 2021 |
| HP            | EliteBook 2170p             | [5e8a05628b](https://linux-hardware.org/?probe=5e8a05628b) | Sep 26, 2021 |
| Dell          | Latitude E5470              | [24f254f7e8](https://linux-hardware.org/?probe=24f254f7e8) | Sep 25, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [2ae9eaaa44](https://linux-hardware.org/?probe=2ae9eaaa44) | Sep 25, 2021 |
| Dell          | Latitude 5420               | [63d0044154](https://linux-hardware.org/?probe=63d0044154) | Sep 25, 2021 |
| Dell          | Inspiron 5502               | [b484f4f0cc](https://linux-hardware.org/?probe=b484f4f0cc) | Sep 25, 2021 |
| Dell          | XPS 13 9360                 | [8bb0307157](https://linux-hardware.org/?probe=8bb0307157) | Sep 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [0a11365d2c](https://linux-hardware.org/?probe=0a11365d2c) | Sep 25, 2021 |
| Acer          | Aspire 4752                 | [c68b87dd56](https://linux-hardware.org/?probe=c68b87dd56) | Sep 25, 2021 |
| Toshiba       | Satellite C70D-A            | [936256d533](https://linux-hardware.org/?probe=936256d533) | Sep 24, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [7565c48d46](https://linux-hardware.org/?probe=7565c48d46) | Sep 24, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [004998105d](https://linux-hardware.org/?probe=004998105d) | Sep 24, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [01362b36bf](https://linux-hardware.org/?probe=01362b36bf) | Sep 24, 2021 |
| Lenovo        | Legion 7 16ITHg6 82K6       | [44e4e1004f](https://linux-hardware.org/?probe=44e4e1004f) | Sep 24, 2021 |
| ASUSTek       | U47A                        | [226b519fcc](https://linux-hardware.org/?probe=226b519fcc) | Sep 23, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [d9d5a32bc0](https://linux-hardware.org/?probe=d9d5a32bc0) | Sep 23, 2021 |
| Apple         | MacBookPro6,2               | [01f37a66c7](https://linux-hardware.org/?probe=01f37a66c7) | Sep 23, 2021 |
| ASUSTek       | U36JC                       | [c6e87f1fb7](https://linux-hardware.org/?probe=c6e87f1fb7) | Sep 23, 2021 |
| Dell          | Latitude 5480               | [a62c0b3e81](https://linux-hardware.org/?probe=a62c0b3e81) | Sep 22, 2021 |
| HP            | Laptop 15s-eq2xxx           | [b08cd2f11d](https://linux-hardware.org/?probe=b08cd2f11d) | Sep 22, 2021 |
| Acer          | Aspire V3-571G              | [b9fcdffa50](https://linux-hardware.org/?probe=b9fcdffa50) | Sep 22, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [710301deba](https://linux-hardware.org/?probe=710301deba) | Sep 22, 2021 |
| Dell          | Vostro 5402                 | [9662887c26](https://linux-hardware.org/?probe=9662887c26) | Sep 22, 2021 |
| HP            | G42                         | [3f3e8bf19a](https://linux-hardware.org/?probe=3f3e8bf19a) | Sep 22, 2021 |
| Fujitsu       | LIFEBOOK E752               | [56833de251](https://linux-hardware.org/?probe=56833de251) | Sep 22, 2021 |
| ASUSTek       | K55VD                       | [0860cc542c](https://linux-hardware.org/?probe=0860cc542c) | Sep 21, 2021 |
| Dell          | XPS 15 7590                 | [7e0c5640af](https://linux-hardware.org/?probe=7e0c5640af) | Sep 21, 2021 |
| Apple         | MacBookAir3,2               | [17c3d61831](https://linux-hardware.org/?probe=17c3d61831) | Sep 21, 2021 |
| Acer          | Aspire 7740                 | [dda5431cbb](https://linux-hardware.org/?probe=dda5431cbb) | Sep 20, 2021 |
| Fujitsu       | LIFEBOOK E752               | [5a023f35b9](https://linux-hardware.org/?probe=5a023f35b9) | Sep 20, 2021 |
| Dell          | Vostro 15-3568              | [c0334c463b](https://linux-hardware.org/?probe=c0334c463b) | Sep 20, 2021 |
| HP            | Laptop 15-dw3xxx            | [0d4306fd72](https://linux-hardware.org/?probe=0d4306fd72) | Sep 20, 2021 |
| Dell          | Latitude 7424 Rugged Ext... | [362307c0b1](https://linux-hardware.org/?probe=362307c0b1) | Sep 19, 2021 |
| Fujitsu       | LIFEBOOK E752               | [d8e207997d](https://linux-hardware.org/?probe=d8e207997d) | Sep 19, 2021 |
| HP            | ProBook 450 G5              | [fc7ea9d020](https://linux-hardware.org/?probe=fc7ea9d020) | Sep 19, 2021 |
| Fujitsu       | LIFEBOOK E752               | [b799ab99bd](https://linux-hardware.org/?probe=b799ab99bd) | Sep 19, 2021 |
| Notebook      | NL40_50CU                   | [9319323793](https://linux-hardware.org/?probe=9319323793) | Sep 19, 2021 |
| Toshiba       | Satellite C855-2J5          | [56c7260e38](https://linux-hardware.org/?probe=56c7260e38) | Sep 19, 2021 |
| Dell          | Inspiron 5570               | [d51e979887](https://linux-hardware.org/?probe=d51e979887) | Sep 19, 2021 |
| Acer          | Extensa 2509                | [86b9641971](https://linux-hardware.org/?probe=86b9641971) | Sep 19, 2021 |
| Dell          | Inspiron 5570               | [c1d4799ecf](https://linux-hardware.org/?probe=c1d4799ecf) | Sep 18, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [e624a1c725](https://linux-hardware.org/?probe=e624a1c725) | Sep 18, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [2149dc459f](https://linux-hardware.org/?probe=2149dc459f) | Sep 18, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [b079ec3bca](https://linux-hardware.org/?probe=b079ec3bca) | Sep 18, 2021 |
| TUXEDO        | N130BU                      | [12a72404ea](https://linux-hardware.org/?probe=12a72404ea) | Sep 18, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7fbc9198ca](https://linux-hardware.org/?probe=7fbc9198ca) | Sep 18, 2021 |
| Dell          | XPS 13 9305                 | [369e99699a](https://linux-hardware.org/?probe=369e99699a) | Sep 18, 2021 |
| ASUSTek       | U50Vg                       | [8a8cd9fece](https://linux-hardware.org/?probe=8a8cd9fece) | Sep 18, 2021 |
| ASUSTek       | X551CAP                     | [89eb27bf06](https://linux-hardware.org/?probe=89eb27bf06) | Sep 18, 2021 |
| Dell          | Inspiron 5559               | [e646bde765](https://linux-hardware.org/?probe=e646bde765) | Sep 17, 2021 |
| ASUSTek       | N71Vg                       | [8e1fd4910a](https://linux-hardware.org/?probe=8e1fd4910a) | Sep 17, 2021 |
| Dell          | XPS 13 9310                 | [d374535153](https://linux-hardware.org/?probe=d374535153) | Sep 17, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [85cb48e026](https://linux-hardware.org/?probe=85cb48e026) | Sep 17, 2021 |
| HP            | Notebook                    | [f4ae81e712](https://linux-hardware.org/?probe=f4ae81e712) | Sep 16, 2021 |
| Dell          | Vostro 5402                 | [670c2b0df7](https://linux-hardware.org/?probe=670c2b0df7) | Sep 16, 2021 |
| Dell          | Vostro 5402                 | [134631220f](https://linux-hardware.org/?probe=134631220f) | Sep 16, 2021 |
| Acer          | Aspire A515-43              | [bf09dd7f40](https://linux-hardware.org/?probe=bf09dd7f40) | Sep 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [4d4918a470](https://linux-hardware.org/?probe=4d4918a470) | Sep 15, 2021 |
| Apple         | MacBookPro9,2               | [8d085a9a13](https://linux-hardware.org/?probe=8d085a9a13) | Sep 15, 2021 |
| Toshiba       | TECRA A50-C                 | [1a625d3feb](https://linux-hardware.org/?probe=1a625d3feb) | Sep 15, 2021 |
| Acer          | Aspire 8730                 | [6e53b2cfa9](https://linux-hardware.org/?probe=6e53b2cfa9) | Sep 15, 2021 |
| ASUSTek       | U50Vg                       | [7d12a66551](https://linux-hardware.org/?probe=7d12a66551) | Sep 15, 2021 |
| Dell          | Inspiron 5570               | [218d153444](https://linux-hardware.org/?probe=218d153444) | Sep 15, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [c51f5529e4](https://linux-hardware.org/?probe=c51f5529e4) | Sep 15, 2021 |
| ASUSTek       | N552VX                      | [ca7b7f7df9](https://linux-hardware.org/?probe=ca7b7f7df9) | Sep 15, 2021 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | [5fb084ffa4](https://linux-hardware.org/?probe=5fb084ffa4) | Sep 15, 2021 |
| ASUSTek       | N751JK                      | [9d34ea25cd](https://linux-hardware.org/?probe=9d34ea25cd) | Sep 14, 2021 |
| Dell          | Latitude 5290               | [baae3812d5](https://linux-hardware.org/?probe=baae3812d5) | Sep 14, 2021 |
| Lenovo        | ThinkPad T450s 20BWZ0CKU... | [a9e206d41b](https://linux-hardware.org/?probe=a9e206d41b) | Sep 14, 2021 |
| Lenovo        | ThinkPad P15 Gen 2i 20YR... | [b193a554c5](https://linux-hardware.org/?probe=b193a554c5) | Sep 14, 2021 |
| Acer          | Swift SF314-43              | [e5804af7f6](https://linux-hardware.org/?probe=e5804af7f6) | Sep 14, 2021 |
| HP            | EliteBook 820 G1            | [9631d6f9e1](https://linux-hardware.org/?probe=9631d6f9e1) | Sep 14, 2021 |
| Advance       | AN-5431                     | [d48465a943](https://linux-hardware.org/?probe=d48465a943) | Sep 14, 2021 |
| Dell          | Latitude E7270              | [479b6d4aa9](https://linux-hardware.org/?probe=479b6d4aa9) | Sep 14, 2021 |
| Toshiba       | Satellite C55-C             | [8966b3a7b5](https://linux-hardware.org/?probe=8966b3a7b5) | Sep 14, 2021 |
| Notebook      | W54_55SU1,SUW               | [7d4ed6e466](https://linux-hardware.org/?probe=7d4ed6e466) | Sep 13, 2021 |
| Sony          | SVS1312G3EW                 | [0a315b4077](https://linux-hardware.org/?probe=0a315b4077) | Sep 13, 2021 |
| Sony          | SVS1312G3EW                 | [bee47d862e](https://linux-hardware.org/?probe=bee47d862e) | Sep 13, 2021 |
| Dell          | Latitude 7370               | [7b446e8905](https://linux-hardware.org/?probe=7b446e8905) | Sep 13, 2021 |
| Dell          | Latitude 7370               | [ec12323a7e](https://linux-hardware.org/?probe=ec12323a7e) | Sep 13, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [9624b39eea](https://linux-hardware.org/?probe=9624b39eea) | Sep 13, 2021 |
| HP            | Notebook                    | [9082e7207c](https://linux-hardware.org/?probe=9082e7207c) | Sep 13, 2021 |
| HP            | EliteBook 8470p             | [651fc72613](https://linux-hardware.org/?probe=651fc72613) | Sep 13, 2021 |
| ASUSTek       | U50Vg                       | [f5d7593025](https://linux-hardware.org/?probe=f5d7593025) | Sep 13, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [229830926d](https://linux-hardware.org/?probe=229830926d) | Sep 13, 2021 |
| Thomson       | WWNEO14A-2BK32              | [1423ee3d10](https://linux-hardware.org/?probe=1423ee3d10) | Sep 13, 2021 |
| Schenker      | XMG CORE (TGL/M21)          | [d1f9d8c10c](https://linux-hardware.org/?probe=d1f9d8c10c) | Sep 13, 2021 |
| Dell          | Precision 5540              | [2888ae8d0a](https://linux-hardware.org/?probe=2888ae8d0a) | Sep 13, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | [c4f8c481e7](https://linux-hardware.org/?probe=c4f8c481e7) | Sep 13, 2021 |
| Dell          | Latitude 5400               | [1fed0bdd29](https://linux-hardware.org/?probe=1fed0bdd29) | Sep 13, 2021 |
| ASUSTek       | U50Vg                       | [8013b7cbcf](https://linux-hardware.org/?probe=8013b7cbcf) | Sep 13, 2021 |
| HP            | EliteBook 840 G2            | [31ca803af1](https://linux-hardware.org/?probe=31ca803af1) | Sep 13, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | [e2202296c9](https://linux-hardware.org/?probe=e2202296c9) | Sep 13, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f8ebf7eb90](https://linux-hardware.org/?probe=f8ebf7eb90) | Sep 13, 2021 |
| Dell          | XPS 13 9300                 | [d4ae821034](https://linux-hardware.org/?probe=d4ae821034) | Sep 12, 2021 |
| HP            | EliteBook 840 G1            | [1124d5133b](https://linux-hardware.org/?probe=1124d5133b) | Sep 12, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [0bba3925b9](https://linux-hardware.org/?probe=0bba3925b9) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | [675a3f37b7](https://linux-hardware.org/?probe=675a3f37b7) | Sep 12, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [ed7eccc83b](https://linux-hardware.org/?probe=ed7eccc83b) | Sep 12, 2021 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [edc7645bfe](https://linux-hardware.org/?probe=edc7645bfe) | Sep 12, 2021 |
| HP            | Pavilion Notebook           | [8fe2203713](https://linux-hardware.org/?probe=8fe2203713) | Sep 12, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [395e1bc884](https://linux-hardware.org/?probe=395e1bc884) | Sep 12, 2021 |
| HP            | EliteBook 820 G1            | [800d54370e](https://linux-hardware.org/?probe=800d54370e) | Sep 11, 2021 |
| Toshiba       | Satellite C850-1MC          | [98127c6225](https://linux-hardware.org/?probe=98127c6225) | Sep 11, 2021 |
| Toshiba       | Satellite Z930              | [2768d5ccb6](https://linux-hardware.org/?probe=2768d5ccb6) | Sep 11, 2021 |
| HP            | EliteBook 840 G1            | [c8da3fea5a](https://linux-hardware.org/?probe=c8da3fea5a) | Sep 11, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [dd09fcf11e](https://linux-hardware.org/?probe=dd09fcf11e) | Sep 10, 2021 |
| Timi          | TM1613                      | [a79355ced3](https://linux-hardware.org/?probe=a79355ced3) | Sep 10, 2021 |
| Dell          | G5 5587                     | [943e12f3e8](https://linux-hardware.org/?probe=943e12f3e8) | Sep 10, 2021 |
| HP            | Pavilion x2 Detachable      | [ddcedfc109](https://linux-hardware.org/?probe=ddcedfc109) | Sep 10, 2021 |
| HP            | Pavilion Aero Laptop 13-... | [0a2430ae78](https://linux-hardware.org/?probe=0a2430ae78) | Sep 10, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [6829dbdafc](https://linux-hardware.org/?probe=6829dbdafc) | Sep 10, 2021 |
| Dell          | Latitude E5400              | [191b8606ba](https://linux-hardware.org/?probe=191b8606ba) | Sep 09, 2021 |
| Notebook      | NJ5x_NJ7xLU                 | [4d544fc5d5](https://linux-hardware.org/?probe=4d544fc5d5) | Sep 09, 2021 |
| Lenovo        | ThinkPad T410 2522WZN       | [b6c19325a4](https://linux-hardware.org/?probe=b6c19325a4) | Sep 09, 2021 |
| HP            | EliteBook 850 G2            | [8a29546070](https://linux-hardware.org/?probe=8a29546070) | Sep 09, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [41fef8dc7e](https://linux-hardware.org/?probe=41fef8dc7e) | Sep 09, 2021 |
| Thomson       | WWNEO14A-2BK32              | [752aa1b840](https://linux-hardware.org/?probe=752aa1b840) | Sep 09, 2021 |
| Dell          | Latitude 5520               | [7e327f4604](https://linux-hardware.org/?probe=7e327f4604) | Sep 09, 2021 |
| Timi          | Mi NoteBook Ultra           | [1619cb6257](https://linux-hardware.org/?probe=1619cb6257) | Sep 08, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [588250b1be](https://linux-hardware.org/?probe=588250b1be) | Sep 08, 2021 |
| TUXEDO        | N130BU                      | [e81e4cc415](https://linux-hardware.org/?probe=e81e4cc415) | Sep 08, 2021 |
| ASUSTek       | P55VA                       | [b00df8e82a](https://linux-hardware.org/?probe=b00df8e82a) | Sep 08, 2021 |
| ASUSTek       | X550LC                      | [930ad79fe0](https://linux-hardware.org/?probe=930ad79fe0) | Sep 08, 2021 |
| Lenovo        | IdeaPad Gaming3 15ARH05D... | [f1bdc44923](https://linux-hardware.org/?probe=f1bdc44923) | Sep 08, 2021 |
| HP            | ProBook 430 G6              | [56f6e80ac3](https://linux-hardware.org/?probe=56f6e80ac3) | Sep 07, 2021 |
| Timi          | A35S                        | [0b22fc8994](https://linux-hardware.org/?probe=0b22fc8994) | Sep 07, 2021 |
| Lenovo        | ThinkPad T460p 20FWS0C50... | [5ac7df1c1c](https://linux-hardware.org/?probe=5ac7df1c1c) | Sep 07, 2021 |
| Dell          | XPS 15 9510                 | [7ca1df084e](https://linux-hardware.org/?probe=7ca1df084e) | Sep 07, 2021 |
| Acer          | Swift SF514-51              | [6ab5bc3174](https://linux-hardware.org/?probe=6ab5bc3174) | Sep 06, 2021 |
| Acer          | Swift SF514-51              | [1bf499eb80](https://linux-hardware.org/?probe=1bf499eb80) | Sep 06, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | [d410366b57](https://linux-hardware.org/?probe=d410366b57) | Sep 06, 2021 |
| TUXEDO        | P65_P67RGRERA               | [342dd3e712](https://linux-hardware.org/?probe=342dd3e712) | Sep 06, 2021 |
| Lenovo        | IdeaPad Gaming3 15ARH05D... | [782ea245a4](https://linux-hardware.org/?probe=782ea245a4) | Sep 06, 2021 |
| Apple         | MacBookPro7,1               | [51e31a6fa5](https://linux-hardware.org/?probe=51e31a6fa5) | Sep 05, 2021 |
| Intel         | SharkBay Platform           | [a19a4b3125](https://linux-hardware.org/?probe=a19a4b3125) | Sep 05, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [06404619aa](https://linux-hardware.org/?probe=06404619aa) | Sep 04, 2021 |
| Dell          | Latitude 7390 2-in-1        | [d1705e50a2](https://linux-hardware.org/?probe=d1705e50a2) | Sep 04, 2021 |
| Timi          | RedmiBook Pro 15S           | [9e63bc0888](https://linux-hardware.org/?probe=9e63bc0888) | Sep 04, 2021 |
| Acer          | Aspire 4750                 | [f88ba2a8ea](https://linux-hardware.org/?probe=f88ba2a8ea) | Sep 04, 2021 |
| HP            | OMEN by HP Laptop 15-dc1... | [f42fc0ef77](https://linux-hardware.org/?probe=f42fc0ef77) | Sep 04, 2021 |
| Packard Be... | EasyNote TE69HW             | [b02379df11](https://linux-hardware.org/?probe=b02379df11) | Sep 04, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [f485e570b4](https://linux-hardware.org/?probe=f485e570b4) | Sep 04, 2021 |
| HP            | Pavilion 17                 | [ef065acdd0](https://linux-hardware.org/?probe=ef065acdd0) | Sep 04, 2021 |
| Lenovo        | ThinkPad L470 20J5S2CP00    | [9ba4ef1dc5](https://linux-hardware.org/?probe=9ba4ef1dc5) | Sep 04, 2021 |
| Lenovo        | U310                        | [0be64d0c02](https://linux-hardware.org/?probe=0be64d0c02) | Sep 03, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [ae8bd5e632](https://linux-hardware.org/?probe=ae8bd5e632) | Sep 03, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [df9db29c8e](https://linux-hardware.org/?probe=df9db29c8e) | Sep 03, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d26d6327b1](https://linux-hardware.org/?probe=d26d6327b1) | Sep 03, 2021 |
| HP            | EliteBook Folio 1040 G3     | [6275aab341](https://linux-hardware.org/?probe=6275aab341) | Sep 03, 2021 |
| HP            | ProBook 4730s               | [36834479ab](https://linux-hardware.org/?probe=36834479ab) | Sep 03, 2021 |
| Dell          | XPS 13 7390                 | [be1de37337](https://linux-hardware.org/?probe=be1de37337) | Sep 03, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [96642dc49d](https://linux-hardware.org/?probe=96642dc49d) | Sep 02, 2021 |
| Dell          | XPS 13 9360                 | [77a32d2048](https://linux-hardware.org/?probe=77a32d2048) | Sep 02, 2021 |
| Acer          | Aspire 8730                 | [23961f8f02](https://linux-hardware.org/?probe=23961f8f02) | Sep 02, 2021 |
| Acer          | Aspire 8730                 | [a0f96eb144](https://linux-hardware.org/?probe=a0f96eb144) | Sep 02, 2021 |
| Acer          | Aspire V3-571               | [6998aee6d0](https://linux-hardware.org/?probe=6998aee6d0) | Sep 02, 2021 |
| Dell          | Latitude 5580               | [944d9e820d](https://linux-hardware.org/?probe=944d9e820d) | Sep 01, 2021 |
| Dell          | Inspiron 5584               | [48b4af3338](https://linux-hardware.org/?probe=48b4af3338) | Sep 01, 2021 |
| Dell          | XPS 15 9510                 | [5de0135b30](https://linux-hardware.org/?probe=5de0135b30) | Sep 01, 2021 |
| Lenovo        | ThinkPad X201 3626FBU       | [2a1b838727](https://linux-hardware.org/?probe=2a1b838727) | Sep 01, 2021 |
| Lenovo        | ThinkPad X201 3626FBU       | [ebe27cb3e0](https://linux-hardware.org/?probe=ebe27cb3e0) | Sep 01, 2021 |
| Acer          | Aspire ES1-572              | [301e2787bd](https://linux-hardware.org/?probe=301e2787bd) | Aug 31, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [8c8a4d9cdf](https://linux-hardware.org/?probe=8c8a4d9cdf) | Aug 31, 2021 |
| ASUSTek       | UX550VE                     | [cd80e1ebb2](https://linux-hardware.org/?probe=cd80e1ebb2) | Aug 31, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [bb2bba4301](https://linux-hardware.org/?probe=bb2bba4301) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [8f1f4a2c99](https://linux-hardware.org/?probe=8f1f4a2c99) | Aug 31, 2021 |
| Dell          | XPS 15 9560                 | [d33400a4fe](https://linux-hardware.org/?probe=d33400a4fe) | Aug 31, 2021 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | [2c57f8fa2f](https://linux-hardware.org/?probe=2c57f8fa2f) | Aug 31, 2021 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [0413b7b1e4](https://linux-hardware.org/?probe=0413b7b1e4) | Aug 31, 2021 |
| ASUSTek       | GL752VW                     | [1476b07c9d](https://linux-hardware.org/?probe=1476b07c9d) | Aug 31, 2021 |
| HUAWEI        | KLVL-WXX9                   | [b86e557def](https://linux-hardware.org/?probe=b86e557def) | Aug 31, 2021 |
| ASUSTek       | GL752VW                     | [625ac8c8bc](https://linux-hardware.org/?probe=625ac8c8bc) | Aug 31, 2021 |
| ASUSTek       | X550ZA                      | [210ca88228](https://linux-hardware.org/?probe=210ca88228) | Aug 30, 2021 |
| Acer          | Nitro AN515-44              | [628f8d49c7](https://linux-hardware.org/?probe=628f8d49c7) | Aug 30, 2021 |
| Acer          | Nitro AN515-44              | [882678793f](https://linux-hardware.org/?probe=882678793f) | Aug 30, 2021 |
| Acer          | Nitro AN515-44              | [1fcdd4041b](https://linux-hardware.org/?probe=1fcdd4041b) | Aug 30, 2021 |
| Dell          | Latitude E6520              | [03f5b8cb05](https://linux-hardware.org/?probe=03f5b8cb05) | Aug 30, 2021 |
| HP            | Pavilion Notebook           | [846b2e2a87](https://linux-hardware.org/?probe=846b2e2a87) | Aug 30, 2021 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [780244d79f](https://linux-hardware.org/?probe=780244d79f) | Aug 30, 2021 |
| HP            | Pavilion 17                 | [ca125d2f3c](https://linux-hardware.org/?probe=ca125d2f3c) | Aug 30, 2021 |
| ASUSTek       | P55VA                       | [12266fad85](https://linux-hardware.org/?probe=12266fad85) | Aug 30, 2021 |
| Lenovo        | B50-30 20382                | [1b602738e7](https://linux-hardware.org/?probe=1b602738e7) | Aug 30, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | [05e455f345](https://linux-hardware.org/?probe=05e455f345) | Aug 29, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [eec643e4e2](https://linux-hardware.org/?probe=eec643e4e2) | Aug 29, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [d700bad32f](https://linux-hardware.org/?probe=d700bad32f) | Aug 29, 2021 |
| Acer          | AOD260                      | [de4ce44515](https://linux-hardware.org/?probe=de4ce44515) | Aug 29, 2021 |
| MSI           | MS-16Y1                     | [a9801b616e](https://linux-hardware.org/?probe=a9801b616e) | Aug 29, 2021 |
| Acer          | AOD260                      | [3ed8c06a9c](https://linux-hardware.org/?probe=3ed8c06a9c) | Aug 29, 2021 |
| Toshiba       | Satellite C55-B             | [e7a572f322](https://linux-hardware.org/?probe=e7a572f322) | Aug 29, 2021 |
| Acer          | Aspire 5742                 | [5a1fa64f5d](https://linux-hardware.org/?probe=5a1fa64f5d) | Aug 29, 2021 |
| Lenovo        | ThinkPad X201 3626FBU       | [7fe9be041a](https://linux-hardware.org/?probe=7fe9be041a) | Aug 29, 2021 |
| Acer          | Extensa 2509                | [b6615e1699](https://linux-hardware.org/?probe=b6615e1699) | Aug 29, 2021 |
| Acer          | Extensa 2509                | [a185b2f23f](https://linux-hardware.org/?probe=a185b2f23f) | Aug 29, 2021 |
| HP            | EliteBook 8530w             | [19a30277a2](https://linux-hardware.org/?probe=19a30277a2) | Aug 28, 2021 |
| Acer          | Aspire A515-56              | [2672ce2fe7](https://linux-hardware.org/?probe=2672ce2fe7) | Aug 28, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | [6bcc1e1e33](https://linux-hardware.org/?probe=6bcc1e1e33) | Aug 28, 2021 |
| Lenovo        | IdeaPad Gaming3 15ARH05D... | [757d521e89](https://linux-hardware.org/?probe=757d521e89) | Aug 28, 2021 |
| ASUSTek       | K52Jr                       | [7ec475cdd0](https://linux-hardware.org/?probe=7ec475cdd0) | Aug 28, 2021 |
| Monster       | ABRA A7 V7.3                | [17d5cd11fa](https://linux-hardware.org/?probe=17d5cd11fa) | Aug 28, 2021 |
| Apple         | MacBookPro5,5               | [97ed1ed910](https://linux-hardware.org/?probe=97ed1ed910) | Aug 28, 2021 |
| HP            | Laptop 15-bw0xx             | [3c7b22938d](https://linux-hardware.org/?probe=3c7b22938d) | Aug 27, 2021 |
| Apple         | MacBookPro5,5               | [e035ede092](https://linux-hardware.org/?probe=e035ede092) | Aug 27, 2021 |
| Lenovo        | B50-30 20382                | [a7bca9bc08](https://linux-hardware.org/?probe=a7bca9bc08) | Aug 27, 2021 |
| Google        | Careena                     | [c71e6267cb](https://linux-hardware.org/?probe=c71e6267cb) | Aug 27, 2021 |
| ASUSTek       | X550ZA                      | [0a21d3b326](https://linux-hardware.org/?probe=0a21d3b326) | Aug 27, 2021 |
| HP            | ProBook 650 G1              | [fe97c44f4f](https://linux-hardware.org/?probe=fe97c44f4f) | Aug 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [50477e1758](https://linux-hardware.org/?probe=50477e1758) | Aug 27, 2021 |
| Acer          | AOD260                      | [d8cf89df4e](https://linux-hardware.org/?probe=d8cf89df4e) | Aug 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [d51c8093ec](https://linux-hardware.org/?probe=d51c8093ec) | Aug 27, 2021 |
| Acer          | Swift SF314-59              | [c4ec7d7706](https://linux-hardware.org/?probe=c4ec7d7706) | Aug 27, 2021 |
| Apple         | MacBookPro16,2              | [7e1625f75d](https://linux-hardware.org/?probe=7e1625f75d) | Aug 27, 2021 |
| Acer          | Aspire 5750G                | [03a89677c0](https://linux-hardware.org/?probe=03a89677c0) | Aug 26, 2021 |
| Apple         | MacBookPro8,1               | [d76439fc39](https://linux-hardware.org/?probe=d76439fc39) | Aug 26, 2021 |
| Apple         | MacBookPro8,1               | [41dce1e5d4](https://linux-hardware.org/?probe=41dce1e5d4) | Aug 26, 2021 |
| Dell          | Inspiron 15-3573            | [9ca63b6d40](https://linux-hardware.org/?probe=9ca63b6d40) | Aug 26, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [b3185cd80d](https://linux-hardware.org/?probe=b3185cd80d) | Aug 26, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [cfeb92ade1](https://linux-hardware.org/?probe=cfeb92ade1) | Aug 26, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [b090440019](https://linux-hardware.org/?probe=b090440019) | Aug 26, 2021 |
| ASUSTek       | S400CA                      | [d1c2760711](https://linux-hardware.org/?probe=d1c2760711) | Aug 26, 2021 |
| System76      | Oryx Pro                    | [ed8769ce16](https://linux-hardware.org/?probe=ed8769ce16) | Aug 26, 2021 |
| System76      | Oryx Pro                    | [a4ba687465](https://linux-hardware.org/?probe=a4ba687465) | Aug 26, 2021 |
| Dell          | Inspiron 5521               | [24bfc2b04a](https://linux-hardware.org/?probe=24bfc2b04a) | Aug 26, 2021 |
| Acer          | Swift SF313-53              | [8b7983c6f4](https://linux-hardware.org/?probe=8b7983c6f4) | Aug 26, 2021 |
| Acer          | Swift SF313-53              | [60ba1a6cf7](https://linux-hardware.org/?probe=60ba1a6cf7) | Aug 25, 2021 |
| BANGHO        | MOV                         | [9bacff92e1](https://linux-hardware.org/?probe=9bacff92e1) | Aug 25, 2021 |
| Acer          | Swift SF313-53              | [91b876aec6](https://linux-hardware.org/?probe=91b876aec6) | Aug 25, 2021 |
| Acer          | Swift SF313-53              | [19f99141b9](https://linux-hardware.org/?probe=19f99141b9) | Aug 25, 2021 |
| Lenovo        | ThinkPad T420s 4176W27      | [b84d5c31e3](https://linux-hardware.org/?probe=b84d5c31e3) | Aug 25, 2021 |
| Dell          | Inspiron 13-7359            | [0d1a190ded](https://linux-hardware.org/?probe=0d1a190ded) | Aug 25, 2021 |
| Dell          | Inspiron 13-7359            | [347f0ad714](https://linux-hardware.org/?probe=347f0ad714) | Aug 25, 2021 |
| Google        | Akemi                       | [11b458a90a](https://linux-hardware.org/?probe=11b458a90a) | Aug 25, 2021 |
| Google        | Akemi                       | [ebd0d7d1f9](https://linux-hardware.org/?probe=ebd0d7d1f9) | Aug 25, 2021 |
| Lenovo        | G500 20236                  | [fb90bc01bc](https://linux-hardware.org/?probe=fb90bc01bc) | Aug 25, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [642e4b5727](https://linux-hardware.org/?probe=642e4b5727) | Aug 25, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [f75424e1e1](https://linux-hardware.org/?probe=f75424e1e1) | Aug 25, 2021 |
| Dell          | XPS 13 9300                 | [2ef66334f0](https://linux-hardware.org/?probe=2ef66334f0) | Aug 24, 2021 |
| Lenovo        | B580 4377A9G                | [4a7f165a2f](https://linux-hardware.org/?probe=4a7f165a2f) | Aug 24, 2021 |
| Sony          | VGN-SZ4MN_B                 | [9b51d6eff6](https://linux-hardware.org/?probe=9b51d6eff6) | Aug 24, 2021 |
| Packard Be... | EasyNote LE69KB             | [adb16307d7](https://linux-hardware.org/?probe=adb16307d7) | Aug 24, 2021 |
| HP            | EliteBook 8530w             | [ea7f22c125](https://linux-hardware.org/?probe=ea7f22c125) | Aug 24, 2021 |
| CyberPower... | TRACER V                    | [d32f6e01af](https://linux-hardware.org/?probe=d32f6e01af) | Aug 24, 2021 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [fa55eabafd](https://linux-hardware.org/?probe=fa55eabafd) | Aug 23, 2021 |
| HP            | Notebook                    | [5edda59c62](https://linux-hardware.org/?probe=5edda59c62) | Aug 23, 2021 |
| Samsung       | 750XDA                      | [a93fe624c9](https://linux-hardware.org/?probe=a93fe624c9) | Aug 23, 2021 |
| Dell          | Vostro 5568                 | [bf921c6ff6](https://linux-hardware.org/?probe=bf921c6ff6) | Aug 23, 2021 |
| Dell          | Inspiron 3558               | [946f2bf799](https://linux-hardware.org/?probe=946f2bf799) | Aug 22, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [6a52dc6e12](https://linux-hardware.org/?probe=6a52dc6e12) | Aug 22, 2021 |
| Acer          | Aspire 4750                 | [6f5d61dc20](https://linux-hardware.org/?probe=6f5d61dc20) | Aug 22, 2021 |
| Acer          | Aspire ES1-572              | [12cb2077ff](https://linux-hardware.org/?probe=12cb2077ff) | Aug 22, 2021 |
| Toshiba       | Satellite C655D             | [63dfa0ffd8](https://linux-hardware.org/?probe=63dfa0ffd8) | Aug 22, 2021 |
| Toshiba       | Satellite C55-B             | [99dbadcdde](https://linux-hardware.org/?probe=99dbadcdde) | Aug 22, 2021 |
| HP            | EliteBook 850 G2            | [89bfd52b3d](https://linux-hardware.org/?probe=89bfd52b3d) | Aug 22, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [dcf6e0d950](https://linux-hardware.org/?probe=dcf6e0d950) | Aug 22, 2021 |
| HP            | EliteBook 850 G2            | [a82576e8e2](https://linux-hardware.org/?probe=a82576e8e2) | Aug 22, 2021 |
| HP            | Notebook                    | [5ac3618644](https://linux-hardware.org/?probe=5ac3618644) | Aug 22, 2021 |
| HP            | ProBook 650 G1              | [521e8315c2](https://linux-hardware.org/?probe=521e8315c2) | Aug 22, 2021 |
| Lenovo        | G500 20236                  | [37294c9129](https://linux-hardware.org/?probe=37294c9129) | Aug 21, 2021 |
| Dell          | Latitude E5400              | [0e1ba1167e](https://linux-hardware.org/?probe=0e1ba1167e) | Aug 21, 2021 |
| Dell          | Latitude E5400              | [10eee4ecd9](https://linux-hardware.org/?probe=10eee4ecd9) | Aug 21, 2021 |
| ASUSTek       | ZenBook UX434FQ             | [e5778c606b](https://linux-hardware.org/?probe=e5778c606b) | Aug 21, 2021 |
| HP            | Laptop 15s-du1xxx           | [0db32c3e7e](https://linux-hardware.org/?probe=0db32c3e7e) | Aug 21, 2021 |
| Dell          | XPS 13 9305                 | [875e2fe9eb](https://linux-hardware.org/?probe=875e2fe9eb) | Aug 20, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [05298cb71d](https://linux-hardware.org/?probe=05298cb71d) | Aug 20, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [bad0ffd0e2](https://linux-hardware.org/?probe=bad0ffd0e2) | Aug 20, 2021 |
| HP            | EliteBook 8570w             | [353385ccb8](https://linux-hardware.org/?probe=353385ccb8) | Aug 20, 2021 |
| Lenovo        | G560 0679                   | [a5d3d1f80c](https://linux-hardware.org/?probe=a5d3d1f80c) | Aug 20, 2021 |
| Lenovo        | G560 0679                   | [ce91db6192](https://linux-hardware.org/?probe=ce91db6192) | Aug 20, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [d1800db637](https://linux-hardware.org/?probe=d1800db637) | Aug 20, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [e5f9d8b06f](https://linux-hardware.org/?probe=e5f9d8b06f) | Aug 20, 2021 |
| HP            | ProBook 450 G6              | [a7ce746e66](https://linux-hardware.org/?probe=a7ce746e66) | Aug 20, 2021 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [b8f5afa2f7](https://linux-hardware.org/?probe=b8f5afa2f7) | Aug 20, 2021 |
| Dell          | Inspiron N5050              | [ed6b51261d](https://linux-hardware.org/?probe=ed6b51261d) | Aug 20, 2021 |
| SLIMBOOK      | TITAN                       | [1eb70ec6e6](https://linux-hardware.org/?probe=1eb70ec6e6) | Aug 19, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [743442952d](https://linux-hardware.org/?probe=743442952d) | Aug 19, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [a4e0272377](https://linux-hardware.org/?probe=a4e0272377) | Aug 19, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [481800b937](https://linux-hardware.org/?probe=481800b937) | Aug 19, 2021 |
| Dell          | Vostro 3360                 | [03074a36b2](https://linux-hardware.org/?probe=03074a36b2) | Aug 19, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [74f533e1b3](https://linux-hardware.org/?probe=74f533e1b3) | Aug 19, 2021 |
| HP            | 450                         | [9f5d03c478](https://linux-hardware.org/?probe=9f5d03c478) | Aug 19, 2021 |
| ASUSTek       | G55VW                       | [7daa09d3c3](https://linux-hardware.org/?probe=7daa09d3c3) | Aug 19, 2021 |
| Samsung       | 520U4C/520U4X               | [1863ae7d28](https://linux-hardware.org/?probe=1863ae7d28) | Aug 19, 2021 |
| ASUSTek       | K54C                        | [816e5c7efa](https://linux-hardware.org/?probe=816e5c7efa) | Aug 19, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [ea3fc1154c](https://linux-hardware.org/?probe=ea3fc1154c) | Aug 18, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [e1467bfa3e](https://linux-hardware.org/?probe=e1467bfa3e) | Aug 18, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [d9923e15e0](https://linux-hardware.org/?probe=d9923e15e0) | Aug 18, 2021 |
| Toshiba       | Satellite Z930              | [3138585fd8](https://linux-hardware.org/?probe=3138585fd8) | Aug 18, 2021 |
| Toshiba       | PORTEGE Z930                | [a49ad7f306](https://linux-hardware.org/?probe=a49ad7f306) | Aug 18, 2021 |
| Toshiba       | Satellite Z930              | [dfb39f616a](https://linux-hardware.org/?probe=dfb39f616a) | Aug 18, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | [251af23ff3](https://linux-hardware.org/?probe=251af23ff3) | Aug 18, 2021 |
| ASUSTek       | K52Je                       | [d35de28c56](https://linux-hardware.org/?probe=d35de28c56) | Aug 17, 2021 |
| HP            | ENVY 17                     | [339f78f408](https://linux-hardware.org/?probe=339f78f408) | Aug 17, 2021 |
| Acer          | Nitro AN515-57              | [3c18d3a700](https://linux-hardware.org/?probe=3c18d3a700) | Aug 17, 2021 |
| Lenovo        | ThinkPad W541 20EF0020GE    | [ea3fc647ce](https://linux-hardware.org/?probe=ea3fc647ce) | Aug 17, 2021 |
| HP            | EliteBook 820 G1            | [00bff94489](https://linux-hardware.org/?probe=00bff94489) | Aug 17, 2021 |
| Acer          | Swift SF314-54              | [d238322295](https://linux-hardware.org/?probe=d238322295) | Aug 16, 2021 |
| Medion        | P6640                       | [e83d5a51ac](https://linux-hardware.org/?probe=e83d5a51ac) | Aug 16, 2021 |
| Acer          | Aspire 5733                 | [7d63c49cee](https://linux-hardware.org/?probe=7d63c49cee) | Aug 16, 2021 |
| Notebook      | W94_95_97JU                 | [816ddae34c](https://linux-hardware.org/?probe=816ddae34c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | [5207c5584c](https://linux-hardware.org/?probe=5207c5584c) | Aug 16, 2021 |
| Lenovo        | G550 2958                   | [b7b363db20](https://linux-hardware.org/?probe=b7b363db20) | Aug 15, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [8e47965ba8](https://linux-hardware.org/?probe=8e47965ba8) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [f406892aa9](https://linux-hardware.org/?probe=f406892aa9) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b333da4703](https://linux-hardware.org/?probe=b333da4703) | Aug 14, 2021 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [3a83d976d0](https://linux-hardware.org/?probe=3a83d976d0) | Aug 14, 2021 |
| Dell          | Inspiron 1525               | [7df7534dd9](https://linux-hardware.org/?probe=7df7534dd9) | Aug 14, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [977c948bad](https://linux-hardware.org/?probe=977c948bad) | Aug 14, 2021 |
| Apple         | MacBookAir3,2               | [e359985b75](https://linux-hardware.org/?probe=e359985b75) | Aug 14, 2021 |
| HP            | EliteBook Folio 1040 G3     | [d03439a8d0](https://linux-hardware.org/?probe=d03439a8d0) | Aug 14, 2021 |
| Medion        | E2213 MD60193               | [5bb52d1b1b](https://linux-hardware.org/?probe=5bb52d1b1b) | Aug 14, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [6346388737](https://linux-hardware.org/?probe=6346388737) | Aug 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [11f9ccb3ad](https://linux-hardware.org/?probe=11f9ccb3ad) | Aug 13, 2021 |
| Radxa         | ROCK Pi X v1.4              | [d5c46e7235](https://linux-hardware.org/?probe=d5c46e7235) | Aug 13, 2021 |
| Dell          | XPS 15 7590                 | [8bb8411127](https://linux-hardware.org/?probe=8bb8411127) | Aug 13, 2021 |
| Acer          | TravelMate B117-M           | [be84ceed7a](https://linux-hardware.org/?probe=be84ceed7a) | Aug 12, 2021 |
| MSI           | Modern 14 A10M              | [d6668ff825](https://linux-hardware.org/?probe=d6668ff825) | Aug 12, 2021 |
| HP            | EliteBook Folio 1040 G3     | [fbeb3986b3](https://linux-hardware.org/?probe=fbeb3986b3) | Aug 12, 2021 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | [6d351fec42](https://linux-hardware.org/?probe=6d351fec42) | Aug 12, 2021 |
| Dell          | G5 5587                     | [204e0318ab](https://linux-hardware.org/?probe=204e0318ab) | Aug 12, 2021 |
| Razer         | Blade                       | [d04a50103d](https://linux-hardware.org/?probe=d04a50103d) | Aug 11, 2021 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | [1f6745d6bb](https://linux-hardware.org/?probe=1f6745d6bb) | Aug 11, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | [d24254d911](https://linux-hardware.org/?probe=d24254d911) | Aug 11, 2021 |
| Dell          | Latitude 5400               | [4f804f2046](https://linux-hardware.org/?probe=4f804f2046) | Aug 11, 2021 |
| HP            | Laptop 15s-du1xxx           | [19412614ef](https://linux-hardware.org/?probe=19412614ef) | Aug 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [90ae378555](https://linux-hardware.org/?probe=90ae378555) | Aug 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [268452e2ee](https://linux-hardware.org/?probe=268452e2ee) | Aug 11, 2021 |
| ASUSTek       | TP300LA                     | [f5dca95f99](https://linux-hardware.org/?probe=f5dca95f99) | Aug 11, 2021 |
| Apple         | MacBookPro7,1               | [4b8bdfd1eb](https://linux-hardware.org/?probe=4b8bdfd1eb) | Aug 10, 2021 |
| Dell          | Latitude E6330              | [cc6a9823e1](https://linux-hardware.org/?probe=cc6a9823e1) | Aug 10, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [eb1b7627ff](https://linux-hardware.org/?probe=eb1b7627ff) | Aug 10, 2021 |
| HP            | 15 Notebook PC              | [d01d6a6ab0](https://linux-hardware.org/?probe=d01d6a6ab0) | Aug 10, 2021 |
| ASUSTek       | T100HAN                     | [8b463c7abb](https://linux-hardware.org/?probe=8b463c7abb) | Aug 10, 2021 |
| Dell          | Latitude E5400              | [c54ea52d26](https://linux-hardware.org/?probe=c54ea52d26) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450 20BUS0G91F    | [8db659cf12](https://linux-hardware.org/?probe=8db659cf12) | Aug 09, 2021 |
| HP            | ProBook 450 G5              | [f8bbb08a59](https://linux-hardware.org/?probe=f8bbb08a59) | Aug 09, 2021 |
| HP            | ProBook 450 G5              | [8e62a52f33](https://linux-hardware.org/?probe=8e62a52f33) | Aug 09, 2021 |
| LG Electro... | 17Z90P-G.AD88B              | [d18eda768e](https://linux-hardware.org/?probe=d18eda768e) | Aug 09, 2021 |
| ASUSTek       | N552VW                      | [9cc9b3d62e](https://linux-hardware.org/?probe=9cc9b3d62e) | Aug 09, 2021 |
| Monster       | TULPAR T7 V20.4             | [f94dfc2fc6](https://linux-hardware.org/?probe=f94dfc2fc6) | Aug 09, 2021 |
| HP            | Laptop 15-da0xxx            | [22fa8558fa](https://linux-hardware.org/?probe=22fa8558fa) | Aug 09, 2021 |
| Dell          | Precision M6600             | [58b77bf05d](https://linux-hardware.org/?probe=58b77bf05d) | Aug 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [e88a377feb](https://linux-hardware.org/?probe=e88a377feb) | Aug 08, 2021 |
| HP            | EliteBook 8570w             | [59783ba71d](https://linux-hardware.org/?probe=59783ba71d) | Aug 08, 2021 |
| HP            | EliteBook 8570w             | [093f956e28](https://linux-hardware.org/?probe=093f956e28) | Aug 08, 2021 |
| HP            | EliteBook 840 G4            | [756d4b46ad](https://linux-hardware.org/?probe=756d4b46ad) | Aug 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [45d400c67b](https://linux-hardware.org/?probe=45d400c67b) | Aug 08, 2021 |
| Dell          | Inspiron N5110              | [f36ecee8d1](https://linux-hardware.org/?probe=f36ecee8d1) | Aug 07, 2021 |
| Dell          | Latitude 5290 2-in-1        | [293b45eded](https://linux-hardware.org/?probe=293b45eded) | Aug 07, 2021 |
| Panasonic     | CF-19KDR78CE                | [29eee33555](https://linux-hardware.org/?probe=29eee33555) | Aug 07, 2021 |
| ASUSTek       | E402SA                      | [790033a704](https://linux-hardware.org/?probe=790033a704) | Aug 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [b3dfe4bfe4](https://linux-hardware.org/?probe=b3dfe4bfe4) | Aug 07, 2021 |
| Medion        | P6640                       | [ee12482cc7](https://linux-hardware.org/?probe=ee12482cc7) | Aug 07, 2021 |
| Lenovo        | ThinkPad L580 20LW0010GE    | [3d2bc47483](https://linux-hardware.org/?probe=3d2bc47483) | Aug 07, 2021 |
| HP            | EliteBook 840 G4            | [0dd35a18fe](https://linux-hardware.org/?probe=0dd35a18fe) | Aug 07, 2021 |
| Dell          | XPS 13 9380                 | [9ffd679117](https://linux-hardware.org/?probe=9ffd679117) | Aug 07, 2021 |
| Dell          | XPS 13 9380                 | [e9e8cca53d](https://linux-hardware.org/?probe=e9e8cca53d) | Aug 07, 2021 |
| ASUSTek       | X550CA                      | [a1e7efd7c1](https://linux-hardware.org/?probe=a1e7efd7c1) | Aug 07, 2021 |
| HP            | EliteBook 840 G3            | [78bd17f4c4](https://linux-hardware.org/?probe=78bd17f4c4) | Aug 06, 2021 |
| HP            | ProBook 4540s               | [52b0186956](https://linux-hardware.org/?probe=52b0186956) | Aug 06, 2021 |
| eMachines     | E627                        | [b83fe7564f](https://linux-hardware.org/?probe=b83fe7564f) | Aug 06, 2021 |
| HP            | ENVY Laptop 13-ba1xxx       | [da4fd46a9b](https://linux-hardware.org/?probe=da4fd46a9b) | Aug 06, 2021 |
| HP            | ENVY Laptop 13-aq1xxx       | [6af058344f](https://linux-hardware.org/?probe=6af058344f) | Aug 06, 2021 |
| Dell          | Inspiron 5515               | [975daf858c](https://linux-hardware.org/?probe=975daf858c) | Aug 06, 2021 |
| Acer          | Aspire ES1-511              | [d8963041b5](https://linux-hardware.org/?probe=d8963041b5) | Aug 06, 2021 |
| HP            | ProBook 640 G1              | [4d0bb591af](https://linux-hardware.org/?probe=4d0bb591af) | Aug 06, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | [e0b87e63a3](https://linux-hardware.org/?probe=e0b87e63a3) | Aug 05, 2021 |
| Lenovo        | ThinkPad T410 253725G       | [47fca1c82c](https://linux-hardware.org/?probe=47fca1c82c) | Aug 05, 2021 |
| HKC           | Y11CC                       | [a8e149ef22](https://linux-hardware.org/?probe=a8e149ef22) | Aug 05, 2021 |
| Fujitsu       | LIFEBOOK E752               | [85bd90092b](https://linux-hardware.org/?probe=85bd90092b) | Aug 05, 2021 |
| Unknown       | Unknown                     | [d4db86e4ac](https://linux-hardware.org/?probe=d4db86e4ac) | Aug 05, 2021 |
| Unknown       | Unknown                     | [bcb72c9247](https://linux-hardware.org/?probe=bcb72c9247) | Aug 05, 2021 |
| Dell          | Latitude 7380               | [c83f32076d](https://linux-hardware.org/?probe=c83f32076d) | Aug 05, 2021 |
| IP3 Tech      | X30                         | [700e39c30d](https://linux-hardware.org/?probe=700e39c30d) | Aug 04, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [eaa9723b34](https://linux-hardware.org/?probe=eaa9723b34) | Aug 03, 2021 |
| Acer          | Swift SF313-53              | [f16feed16c](https://linux-hardware.org/?probe=f16feed16c) | Aug 03, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [fc2c2761bc](https://linux-hardware.org/?probe=fc2c2761bc) | Aug 03, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [636e961fcc](https://linux-hardware.org/?probe=636e961fcc) | Aug 03, 2021 |
| ASUSTek       | X542UQ                      | [63d2276d55](https://linux-hardware.org/?probe=63d2276d55) | Aug 03, 2021 |
| ASUSTek       | K73BY                       | [37b4b1362f](https://linux-hardware.org/?probe=37b4b1362f) | Aug 03, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3980... | [32507fdf80](https://linux-hardware.org/?probe=32507fdf80) | Aug 03, 2021 |
| Dell          | G3 3500                     | [3480d1f83d](https://linux-hardware.org/?probe=3480d1f83d) | Aug 03, 2021 |
| HP            | ENVY m6                     | [6d72ad672c](https://linux-hardware.org/?probe=6d72ad672c) | Aug 03, 2021 |
| Lenovo        | ThinkPad T440p 20AW0002I... | [7f53bdba21](https://linux-hardware.org/?probe=7f53bdba21) | Aug 03, 2021 |
| Dell          | Inspiron 5301               | [2387a6a66c](https://linux-hardware.org/?probe=2387a6a66c) | Aug 03, 2021 |
| HP            | ProBook 4540s               | [42b95781f5](https://linux-hardware.org/?probe=42b95781f5) | Aug 03, 2021 |
| Acer          | Swift SF314-54G             | [04a33a7d5c](https://linux-hardware.org/?probe=04a33a7d5c) | Aug 02, 2021 |
| HP            | ZBook 15u G4                | [d77bb6209a](https://linux-hardware.org/?probe=d77bb6209a) | Aug 02, 2021 |
| ASUSTek       | K73BY                       | [8fb5845dd4](https://linux-hardware.org/?probe=8fb5845dd4) | Aug 02, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [5ac36e570a](https://linux-hardware.org/?probe=5ac36e570a) | Aug 02, 2021 |
| HP            | EliteBook 820 G1            | [7b564a6ba6](https://linux-hardware.org/?probe=7b564a6ba6) | Aug 02, 2021 |
| HP            | 250 G4                      | [bd80a8cdf0](https://linux-hardware.org/?probe=bd80a8cdf0) | Aug 02, 2021 |
| HP            | EliteBook 820 G1            | [e9e0269b1a](https://linux-hardware.org/?probe=e9e0269b1a) | Aug 01, 2021 |
| Acer          | Swift SF313-53              | [5144862148](https://linux-hardware.org/?probe=5144862148) | Aug 01, 2021 |
| HP            | Pavilion dm1                | [ac0e534d86](https://linux-hardware.org/?probe=ac0e534d86) | Aug 01, 2021 |
| Advance       | AN-5431                     | [06409d8637](https://linux-hardware.org/?probe=06409d8637) | Aug 01, 2021 |
| HP            | Presario CQ61               | [3496f82684](https://linux-hardware.org/?probe=3496f82684) | Aug 01, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [fb4efe3736](https://linux-hardware.org/?probe=fb4efe3736) | Aug 01, 2021 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [22790f2a7e](https://linux-hardware.org/?probe=22790f2a7e) | Aug 01, 2021 |
| Alienware     | M17xR4                      | [940c3efccf](https://linux-hardware.org/?probe=940c3efccf) | Aug 01, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [ec65d6706f](https://linux-hardware.org/?probe=ec65d6706f) | Aug 01, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | [91cc6c6711](https://linux-hardware.org/?probe=91cc6c6711) | Aug 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [69c078f12b](https://linux-hardware.org/?probe=69c078f12b) | Aug 01, 2021 |
| MSI           | MS-16GF                     | [ba0b532d35](https://linux-hardware.org/?probe=ba0b532d35) | Aug 01, 2021 |
| Google        | Stout                       | [dcc159aacb](https://linux-hardware.org/?probe=dcc159aacb) | Aug 01, 2021 |
| Dell          | Latitude E5520              | [495c7ad655](https://linux-hardware.org/?probe=495c7ad655) | Jul 31, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [e2db581d0b](https://linux-hardware.org/?probe=e2db581d0b) | Jul 31, 2021 |
| Lenovo        | Yoga 500-15IBD 80N6         | [b893ad294a](https://linux-hardware.org/?probe=b893ad294a) | Jul 31, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [1e14356790](https://linux-hardware.org/?probe=1e14356790) | Jul 31, 2021 |
| Dell          | Vostro 14-5459              | [1a120753db](https://linux-hardware.org/?probe=1a120753db) | Jul 31, 2021 |
| HP            | Pavilion g6                 | [147539a271](https://linux-hardware.org/?probe=147539a271) | Jul 31, 2021 |
| Dell          | Vostro 14-5459              | [affecdcdb7](https://linux-hardware.org/?probe=affecdcdb7) | Jul 31, 2021 |
| Apple         | MacBookPro9,2               | [abb1e8ea82](https://linux-hardware.org/?probe=abb1e8ea82) | Jul 31, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [842c9c2629](https://linux-hardware.org/?probe=842c9c2629) | Jul 30, 2021 |
| Dell          | XPS 15 9570                 | [75228088e0](https://linux-hardware.org/?probe=75228088e0) | Jul 30, 2021 |
| Dell          | Inspiron 5720               | [08e504b4d9](https://linux-hardware.org/?probe=08e504b4d9) | Jul 30, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [d7a0f68d0d](https://linux-hardware.org/?probe=d7a0f68d0d) | Jul 30, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [64b0d25c3a](https://linux-hardware.org/?probe=64b0d25c3a) | Jul 29, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [5c8b0fb32b](https://linux-hardware.org/?probe=5c8b0fb32b) | Jul 29, 2021 |
| Sony          | SVF1521H2EW                 | [025ae9003b](https://linux-hardware.org/?probe=025ae9003b) | Jul 29, 2021 |
| Lenovo        | ThinkPad T430 2347AT2       | [ceac6ce540](https://linux-hardware.org/?probe=ceac6ce540) | Jul 29, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | [5cacc2c659](https://linux-hardware.org/?probe=5cacc2c659) | Jul 29, 2021 |
| Toshiba       | TECRA Z40-B                 | [d353412a4f](https://linux-hardware.org/?probe=d353412a4f) | Jul 29, 2021 |
| Sony          | VPCEJ1L1E                   | [03e1c179a3](https://linux-hardware.org/?probe=03e1c179a3) | Jul 29, 2021 |
| Samsung       | 935XDB                      | [ebc69d8a77](https://linux-hardware.org/?probe=ebc69d8a77) | Jul 29, 2021 |
| Sony          | VPCEJ1L1E                   | [a43c899910](https://linux-hardware.org/?probe=a43c899910) | Jul 29, 2021 |
| Dell          | Inspiron 5521               | [8242b46551](https://linux-hardware.org/?probe=8242b46551) | Jul 29, 2021 |
| Lenovo        | Unknown                     | [eef802c064](https://linux-hardware.org/?probe=eef802c064) | Jul 29, 2021 |
| ASUSTek       | T100HAN                     | [bdea6cca11](https://linux-hardware.org/?probe=bdea6cca11) | Jul 29, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [09419fd70a](https://linux-hardware.org/?probe=09419fd70a) | Jul 28, 2021 |
| Apple         | MacBookAir1,1               | [53bd733ffa](https://linux-hardware.org/?probe=53bd733ffa) | Jul 28, 2021 |
| Gigabyte      | i1520M                      | [5d0fb03190](https://linux-hardware.org/?probe=5d0fb03190) | Jul 28, 2021 |
| Gigabyte      | i1520M                      | [95de13078b](https://linux-hardware.org/?probe=95de13078b) | Jul 28, 2021 |
| HP            | 255 G7 Notebook PC          | [4b4496337a](https://linux-hardware.org/?probe=4b4496337a) | Jul 27, 2021 |
| Dell          | XPS 15 9570                 | [b6f42df92b](https://linux-hardware.org/?probe=b6f42df92b) | Jul 27, 2021 |
| Fujitsu       | LIFEBOOK E752               | [72e045b4da](https://linux-hardware.org/?probe=72e045b4da) | Jul 27, 2021 |
| Dell          | Latitude 7370               | [8844c61431](https://linux-hardware.org/?probe=8844c61431) | Jul 27, 2021 |
| Dell          | Latitude 7370               | [65b034f3f3](https://linux-hardware.org/?probe=65b034f3f3) | Jul 27, 2021 |
| Toshiba       | Satellite Pro L650          | [10e8624257](https://linux-hardware.org/?probe=10e8624257) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e2877b1692](https://linux-hardware.org/?probe=e2877b1692) | Jul 27, 2021 |
| Chuwi         | GemiBook Pro                | [a4ecebc31b](https://linux-hardware.org/?probe=a4ecebc31b) | Jul 27, 2021 |
| ASUSTek       | X551CAP                     | [59e9b7398f](https://linux-hardware.org/?probe=59e9b7398f) | Jul 27, 2021 |
| HP            | ProBook 650 G1              | [98486b5f47](https://linux-hardware.org/?probe=98486b5f47) | Jul 27, 2021 |
| Dell          | Precision M6600             | [67a1d8b2e4](https://linux-hardware.org/?probe=67a1d8b2e4) | Jul 27, 2021 |
| ASUSTek       | N551JM                      | [4334fcb285](https://linux-hardware.org/?probe=4334fcb285) | Jul 27, 2021 |
| HP            | ProBook 650 G1              | [86b2b34f64](https://linux-hardware.org/?probe=86b2b34f64) | Jul 27, 2021 |
| ASUSTek       | G73Jh                       | [e7af78fad2](https://linux-hardware.org/?probe=e7af78fad2) | Jul 26, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [177743cfae](https://linux-hardware.org/?probe=177743cfae) | Jul 26, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | [b56b5cfff2](https://linux-hardware.org/?probe=b56b5cfff2) | Jul 26, 2021 |
| roda compu... | DS13                        | [be0c6525a4](https://linux-hardware.org/?probe=be0c6525a4) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | [690b0d3adc](https://linux-hardware.org/?probe=690b0d3adc) | Jul 26, 2021 |
| Acer          | Swift SF314-43              | [3c2e8b0074](https://linux-hardware.org/?probe=3c2e8b0074) | Jul 26, 2021 |
| Acer          | Aspire V5-531P              | [b236b9b9d9](https://linux-hardware.org/?probe=b236b9b9d9) | Jul 26, 2021 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | [26ab6b470a](https://linux-hardware.org/?probe=26ab6b470a) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TDS... | [f3199bc88b](https://linux-hardware.org/?probe=f3199bc88b) | Jul 25, 2021 |
| Dell          | XPS 15 9510                 | [074932b079](https://linux-hardware.org/?probe=074932b079) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fb1170efa6](https://linux-hardware.org/?probe=fb1170efa6) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [19f5976aa3](https://linux-hardware.org/?probe=19f5976aa3) | Jul 25, 2021 |
| HP            | ProBook 650 G1              | [335bb2e92e](https://linux-hardware.org/?probe=335bb2e92e) | Jul 25, 2021 |
| ASUSTek       | T100HAN                     | [8d6daa25e8](https://linux-hardware.org/?probe=8d6daa25e8) | Jul 25, 2021 |
| HP            | ProBook 650 G5              | [6d3f09e9c2](https://linux-hardware.org/?probe=6d3f09e9c2) | Jul 25, 2021 |
| HP            | ProBook 650 G5              | [7580d2b74e](https://linux-hardware.org/?probe=7580d2b74e) | Jul 25, 2021 |
| Acer          | Aspire V7-582P              | [308aee8cb1](https://linux-hardware.org/?probe=308aee8cb1) | Jul 25, 2021 |
| Acer          | Aspire V7-582P              | [6ce43ddc17](https://linux-hardware.org/?probe=6ce43ddc17) | Jul 25, 2021 |
| HP            | ProBook 650 G5              | [d3851a242f](https://linux-hardware.org/?probe=d3851a242f) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [c466690f21](https://linux-hardware.org/?probe=c466690f21) | Jul 25, 2021 |
| Lenovo        | ThinkBook 14-IML 20RV       | [bfbf5b3302](https://linux-hardware.org/?probe=bfbf5b3302) | Jul 25, 2021 |
| HP            | ProBook 650 G1              | [534e1afff4](https://linux-hardware.org/?probe=534e1afff4) | Jul 25, 2021 |
| HP            | ProBook 650 G1              | [1f1197a640](https://linux-hardware.org/?probe=1f1197a640) | Jul 25, 2021 |
| HP            | ProBook 650 G1              | [ad6bb28669](https://linux-hardware.org/?probe=ad6bb28669) | Jul 24, 2021 |
| HP            | EliteBook 820 G1            | [7ed4e2945c](https://linux-hardware.org/?probe=7ed4e2945c) | Jul 24, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [7fa1d5f6ab](https://linux-hardware.org/?probe=7fa1d5f6ab) | Jul 24, 2021 |
| Sony          | VPCEJ1L1E                   | [ae5dc242e4](https://linux-hardware.org/?probe=ae5dc242e4) | Jul 24, 2021 |
| Dell          | Inspiron N5010              | [d83e888f43](https://linux-hardware.org/?probe=d83e888f43) | Jul 24, 2021 |
| Dell          | XPS 15 7590                 | [df948c9a32](https://linux-hardware.org/?probe=df948c9a32) | Jul 23, 2021 |
| Dell          | XPS 15 7590                 | [80e7ec8f3f](https://linux-hardware.org/?probe=80e7ec8f3f) | Jul 23, 2021 |
| DNS           | Unknown                     | [fce7ca77f0](https://linux-hardware.org/?probe=fce7ca77f0) | Jul 23, 2021 |
| roda compu... | DS13                        | [ff3f6c2d6f](https://linux-hardware.org/?probe=ff3f6c2d6f) | Jul 23, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | [d058df63d2](https://linux-hardware.org/?probe=d058df63d2) | Jul 23, 2021 |
| Dell          | Inspiron N5010              | [cca8fb82b1](https://linux-hardware.org/?probe=cca8fb82b1) | Jul 23, 2021 |
| Lenovo        | ThinkPad T420 4180ED3       | [0dc7d14a68](https://linux-hardware.org/?probe=0dc7d14a68) | Jul 23, 2021 |
| HP            | 14                          | [29af89c91b](https://linux-hardware.org/?probe=29af89c91b) | Jul 23, 2021 |
| Medion        | E6226                       | [aee8a0be6f](https://linux-hardware.org/?probe=aee8a0be6f) | Jul 22, 2021 |
| Lenovo        | Unknown                     | [425e6aa6da](https://linux-hardware.org/?probe=425e6aa6da) | Jul 22, 2021 |
| Dell          | Inspiron N5010              | [4f3af1bdc2](https://linux-hardware.org/?probe=4f3af1bdc2) | Jul 22, 2021 |
| Dell          | Latitude 3410               | [4058065b38](https://linux-hardware.org/?probe=4058065b38) | Jul 21, 2021 |
| HP            | EliteBook 820 G1            | [2682c21b3a](https://linux-hardware.org/?probe=2682c21b3a) | Jul 21, 2021 |
| Lenovo        | G485                        | [0810c75be3](https://linux-hardware.org/?probe=0810c75be3) | Jul 21, 2021 |
| ASUSTek       | K52JT                       | [243cac5745](https://linux-hardware.org/?probe=243cac5745) | Jul 20, 2021 |
| HP            | ProBook 650 G5              | [0880c07a99](https://linux-hardware.org/?probe=0880c07a99) | Jul 20, 2021 |
| Lenovo        | G485                        | [aa805dfe8d](https://linux-hardware.org/?probe=aa805dfe8d) | Jul 20, 2021 |
| Apple         | MacBookPro12,1              | [20eed1cd12](https://linux-hardware.org/?probe=20eed1cd12) | Jul 20, 2021 |
| HP            | 14                          | [345be169ae](https://linux-hardware.org/?probe=345be169ae) | Jul 20, 2021 |
| HP            | Pavilion Laptop 15-cs3xx... | [30a28565e9](https://linux-hardware.org/?probe=30a28565e9) | Jul 19, 2021 |
| HP            | ProBook 650 G1              | [1a9549039b](https://linux-hardware.org/?probe=1a9549039b) | Jul 19, 2021 |
| HP            | ProBook 650 G1              | [576d7b9871](https://linux-hardware.org/?probe=576d7b9871) | Jul 19, 2021 |
| Lenovo        | G500 20236                  | [e9ecd52e2c](https://linux-hardware.org/?probe=e9ecd52e2c) | Jul 18, 2021 |
| Apple         | MacBook8,1                  | [f7cabbb5fe](https://linux-hardware.org/?probe=f7cabbb5fe) | Jul 18, 2021 |
| Dell          | Latitude E6520              | [67d96eeb17](https://linux-hardware.org/?probe=67d96eeb17) | Jul 17, 2021 |
| HUAWEI        | HLYL-WXX9                   | [a44ab9f722](https://linux-hardware.org/?probe=a44ab9f722) | Jul 17, 2021 |
| ASUSTek       | K52Jr                       | [e8672d5819](https://linux-hardware.org/?probe=e8672d5819) | Jul 17, 2021 |
| Dell          | G3 3500                     | [12e1eb1ce7](https://linux-hardware.org/?probe=12e1eb1ce7) | Jul 17, 2021 |
| HP            | ProBook 640 G1              | [2db57969aa](https://linux-hardware.org/?probe=2db57969aa) | Jul 17, 2021 |
| Dell          | XPS 15 9550                 | [1183f6f39b](https://linux-hardware.org/?probe=1183f6f39b) | Jul 16, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [d1105aa53f](https://linux-hardware.org/?probe=d1105aa53f) | Jul 16, 2021 |
| Dell          | Inspiron 3793               | [a87acc7896](https://linux-hardware.org/?probe=a87acc7896) | Jul 15, 2021 |
| ASUSTek       | X751LJ                      | [fcbeeff3a2](https://linux-hardware.org/?probe=fcbeeff3a2) | Jul 15, 2021 |
| ASUSTek       | X751SA                      | [8bde6f919c](https://linux-hardware.org/?probe=8bde6f919c) | Jul 15, 2021 |
| Dell          | Inspiron 15-3567            | [1b1591901f](https://linux-hardware.org/?probe=1b1591901f) | Jul 15, 2021 |
| Samsung       | 800G5H/800G5S               | [43c5271ff4](https://linux-hardware.org/?probe=43c5271ff4) | Jul 15, 2021 |
| HP            | Laptop 15-bs1xx             | [3d1c92e425](https://linux-hardware.org/?probe=3d1c92e425) | Jul 15, 2021 |
| System76      | Serval WS                   | [9c6e77076c](https://linux-hardware.org/?probe=9c6e77076c) | Jul 15, 2021 |
| Acer          | Swift SF114-34              | [a27de08174](https://linux-hardware.org/?probe=a27de08174) | Jul 15, 2021 |
| Dell          | XPS 13 9310                 | [96ce85594c](https://linux-hardware.org/?probe=96ce85594c) | Jul 14, 2021 |
| Timi          | A35S                        | [27f9e877a1](https://linux-hardware.org/?probe=27f9e877a1) | Jul 14, 2021 |
| Dell          | XPS 13 9310                 | [8e96e56dc3](https://linux-hardware.org/?probe=8e96e56dc3) | Jul 14, 2021 |
| Lenovo        | ThinkPad E14 20RBS7WC00     | [4d34393d9f](https://linux-hardware.org/?probe=4d34393d9f) | Jul 14, 2021 |
| Dell          | Latitude 5300               | [c1bf5424e4](https://linux-hardware.org/?probe=c1bf5424e4) | Jul 14, 2021 |
| HP            | ProBook 4530s               | [603ec2d5c9](https://linux-hardware.org/?probe=603ec2d5c9) | Jul 14, 2021 |
| HP            | EliteBook 8560p             | [41a7775b52](https://linux-hardware.org/?probe=41a7775b52) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [aa5fadb321](https://linux-hardware.org/?probe=aa5fadb321) | Jul 13, 2021 |
| Lenovo        | ThinkPad X1C 5th W10DG 2... | [dcc22fa273](https://linux-hardware.org/?probe=dcc22fa273) | Jul 13, 2021 |
| Dell          | Latitude E7440              | [e4d6f94ccb](https://linux-hardware.org/?probe=e4d6f94ccb) | Jul 13, 2021 |
| HP            | EliteBook 8460p             | [870b9bdfca](https://linux-hardware.org/?probe=870b9bdfca) | Jul 13, 2021 |
| Dell          | Inspiron 7501               | [f63afb571d](https://linux-hardware.org/?probe=f63afb571d) | Jul 13, 2021 |
| Acer          | AS5750G                     | [5059f64428](https://linux-hardware.org/?probe=5059f64428) | Jul 13, 2021 |
| HP            | Stream Laptop 14-cb1XX      | [6fff913666](https://linux-hardware.org/?probe=6fff913666) | Jul 12, 2021 |
| Dell          | Inspiron 7501               | [4ad9830a25](https://linux-hardware.org/?probe=4ad9830a25) | Jul 12, 2021 |
| Lenovo        | ThinkPad W540 20BHS2LM02    | [6d00312e5e](https://linux-hardware.org/?probe=6d00312e5e) | Jul 12, 2021 |
| Acer          | Aspire E1-571               | [a32287126e](https://linux-hardware.org/?probe=a32287126e) | Jul 12, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [393ed0c954](https://linux-hardware.org/?probe=393ed0c954) | Jul 12, 2021 |
| Chuwi         | HeroBook Pro+               | [ab9af242f2](https://linux-hardware.org/?probe=ab9af242f2) | Jul 12, 2021 |
| Samsung       | 530U3C/530U4C/532U3C        | [3cf8675c2d](https://linux-hardware.org/?probe=3cf8675c2d) | Jul 12, 2021 |
| Fujitsu       | LIFEBOOK A556               | [076bf0f706](https://linux-hardware.org/?probe=076bf0f706) | Jul 11, 2021 |
| Dell          | XPS 15 9560                 | [62a4b43bb7](https://linux-hardware.org/?probe=62a4b43bb7) | Jul 11, 2021 |
| Apple         | MacBookAir6,2               | [f00c776e5d](https://linux-hardware.org/?probe=f00c776e5d) | Jul 11, 2021 |
| Dell          | Inspiron 15-3567            | [e76377da85](https://linux-hardware.org/?probe=e76377da85) | Jul 11, 2021 |
| Lenovo        | 3000 N200 0769ESG           | [17edd23abd](https://linux-hardware.org/?probe=17edd23abd) | Jul 10, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [dc0cd1d174](https://linux-hardware.org/?probe=dc0cd1d174) | Jul 10, 2021 |
| Acer          | Aspire V3-771               | [9371836e3e](https://linux-hardware.org/?probe=9371836e3e) | Jul 10, 2021 |
| Acer          | Aspire E1-531               | [064d13dec1](https://linux-hardware.org/?probe=064d13dec1) | Jul 10, 2021 |
| Medion        | Akoya E6416 MD99610         | [fa99920590](https://linux-hardware.org/?probe=fa99920590) | Jul 10, 2021 |
| Medion        | Akoya E6416 MD99610         | [a1a9ad6ac8](https://linux-hardware.org/?probe=a1a9ad6ac8) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [cd0155712e](https://linux-hardware.org/?probe=cd0155712e) | Jul 10, 2021 |
| Lenovo        | ThinkPad T430 2342A19       | [9727587570](https://linux-hardware.org/?probe=9727587570) | Jul 10, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T6C... | [516709833b](https://linux-hardware.org/?probe=516709833b) | Jul 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c006002427](https://linux-hardware.org/?probe=c006002427) | Jul 09, 2021 |
| Dell          | Vostro 5470                 | [aff224171e](https://linux-hardware.org/?probe=aff224171e) | Jul 09, 2021 |
| Wiltronic     | IVIEW Maximus Pro           | [94e424774a](https://linux-hardware.org/?probe=94e424774a) | Jul 09, 2021 |
| ASUSTek       | X751SA                      | [79ebf739a1](https://linux-hardware.org/?probe=79ebf739a1) | Jul 08, 2021 |
| HP            | EliteBook 840 G3            | [950a407dff](https://linux-hardware.org/?probe=950a407dff) | Jul 08, 2021 |
| Fujitsu       | LIFEBOOK E752               | [71f2a9ae1f](https://linux-hardware.org/?probe=71f2a9ae1f) | Jul 08, 2021 |
| Lenovo        | G500 20236                  | [cdc6087931](https://linux-hardware.org/?probe=cdc6087931) | Jul 08, 2021 |
| Lenovo        | G500 20236                  | [905b293afa](https://linux-hardware.org/?probe=905b293afa) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | [6aa95f6599](https://linux-hardware.org/?probe=6aa95f6599) | Jul 08, 2021 |
| MSI           | Bravo 17 A4DDR              | [2a2e03aaa8](https://linux-hardware.org/?probe=2a2e03aaa8) | Jul 08, 2021 |
| Unknown       | 1.0                         | [deb4346da8](https://linux-hardware.org/?probe=deb4346da8) | Jul 08, 2021 |
| ASUSTek       | X751SA                      | [fa4822db25](https://linux-hardware.org/?probe=fa4822db25) | Jul 08, 2021 |
| HP            | Laptop 14s-fq1xxx           | [f05a96bdac](https://linux-hardware.org/?probe=f05a96bdac) | Jul 07, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3980... | [99729a0a68](https://linux-hardware.org/?probe=99729a0a68) | Jul 07, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [de0ab0b7c2](https://linux-hardware.org/?probe=de0ab0b7c2) | Jul 07, 2021 |
| Alienware     | M17xR4                      | [584079f0f6](https://linux-hardware.org/?probe=584079f0f6) | Jul 07, 2021 |
| Dell          | G7 7700                     | [6fc41408bf](https://linux-hardware.org/?probe=6fc41408bf) | Jul 07, 2021 |
| Dell          | Inspiron 3501               | [64371c73a0](https://linux-hardware.org/?probe=64371c73a0) | Jul 07, 2021 |
| ASUSTek       | X551CAP                     | [bc8df07ff7](https://linux-hardware.org/?probe=bc8df07ff7) | Jul 06, 2021 |
| Dell          | Inspiron 5482               | [0d8c9adb49](https://linux-hardware.org/?probe=0d8c9adb49) | Jul 06, 2021 |
| Dell          | Latitude 5511               | [cac1bff4a1](https://linux-hardware.org/?probe=cac1bff4a1) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G713QR_G713QR     | [0b10aaa23c](https://linux-hardware.org/?probe=0b10aaa23c) | Jul 06, 2021 |
| ASUSTek       | ROG Strix G713QR_G713QR     | [6c81e98dd0](https://linux-hardware.org/?probe=6c81e98dd0) | Jul 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [1b38515a6a](https://linux-hardware.org/?probe=1b38515a6a) | Jul 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [0033ea368f](https://linux-hardware.org/?probe=0033ea368f) | Jul 06, 2021 |
| ASUSTek       | X551CAP                     | [c3bed169fd](https://linux-hardware.org/?probe=c3bed169fd) | Jul 06, 2021 |
| Dell          | Inspiron 5521               | [f2ab6f6a6f](https://linux-hardware.org/?probe=f2ab6f6a6f) | Jul 05, 2021 |
| Dell          | Inspiron 5521               | [260f6cb321](https://linux-hardware.org/?probe=260f6cb321) | Jul 05, 2021 |
| HP            | ENVY Laptop 13-ad0xx        | [92cfe5edd3](https://linux-hardware.org/?probe=92cfe5edd3) | Jul 05, 2021 |
| Dell          | Latitude E6320              | [dc31c90631](https://linux-hardware.org/?probe=dc31c90631) | Jul 05, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [621494a6e3](https://linux-hardware.org/?probe=621494a6e3) | Jul 05, 2021 |
| Packard Be... | EasyNote LS11HR             | [09dbdc286a](https://linux-hardware.org/?probe=09dbdc286a) | Jul 05, 2021 |
| Dell          | Latitude E5520              | [11a20a01eb](https://linux-hardware.org/?probe=11a20a01eb) | Jul 05, 2021 |
| ASUSTek       | X751SA                      | [98d8d8a1ca](https://linux-hardware.org/?probe=98d8d8a1ca) | Jul 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [94e917d395](https://linux-hardware.org/?probe=94e917d395) | Jul 04, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [867e24050a](https://linux-hardware.org/?probe=867e24050a) | Jul 04, 2021 |
| HP            | Compaq 510                  | [cd27b78fea](https://linux-hardware.org/?probe=cd27b78fea) | Jul 04, 2021 |
| HP            | EliteBook 840 G2            | [e807bd56bc](https://linux-hardware.org/?probe=e807bd56bc) | Jul 04, 2021 |
| Dell          | Inspiron 5593               | [926e72bc56](https://linux-hardware.org/?probe=926e72bc56) | Jul 03, 2021 |
| Dell          | Latitude E6400              | [18d5b00f71](https://linux-hardware.org/?probe=18d5b00f71) | Jul 03, 2021 |
| Dell          | Latitude 7490               | [c669795b35](https://linux-hardware.org/?probe=c669795b35) | Jul 03, 2021 |
| Chuwi         | HeroBook Pro+               | [bbd1ce59fa](https://linux-hardware.org/?probe=bbd1ce59fa) | Jul 03, 2021 |
| Dell          | Latitude E6430              | [43100da49e](https://linux-hardware.org/?probe=43100da49e) | Jul 02, 2021 |
| Dell          | Inspiron 1750               | [2ff81df67a](https://linux-hardware.org/?probe=2ff81df67a) | Jul 02, 2021 |
| Toshiba       | QOSMIO X70-B                | [dcec6c2c5f](https://linux-hardware.org/?probe=dcec6c2c5f) | Jul 02, 2021 |
| HP            | Stream Laptop 11-ak0xxx     | [f0de8a11c7](https://linux-hardware.org/?probe=f0de8a11c7) | Jul 02, 2021 |
| Sony          | VGN-FE880E                  | [920adf56ec](https://linux-hardware.org/?probe=920adf56ec) | Jul 02, 2021 |
| Sony          | VGN-FE880E                  | [6ae2ef9b19](https://linux-hardware.org/?probe=6ae2ef9b19) | Jul 02, 2021 |
| HP            | ProBook 430 G3              | [36176e3082](https://linux-hardware.org/?probe=36176e3082) | Jul 02, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [0dd8596f55](https://linux-hardware.org/?probe=0dd8596f55) | Jul 01, 2021 |
| Acer          | Aspire ES1-572              | [4e808a5437](https://linux-hardware.org/?probe=4e808a5437) | Jul 01, 2021 |
| Timi          | TM1701                      | [fe9f90644b](https://linux-hardware.org/?probe=fe9f90644b) | Jul 01, 2021 |
| HP            | 620                         | [a1ca12ac2c](https://linux-hardware.org/?probe=a1ca12ac2c) | Jul 01, 2021 |
| Dell          | Studio 1735                 | [2ed92032e0](https://linux-hardware.org/?probe=2ed92032e0) | Jul 01, 2021 |
| HP            | ProBook 430 G3              | [c7dfa113bc](https://linux-hardware.org/?probe=c7dfa113bc) | Jul 01, 2021 |
| HP            | EliteBook 8460p             | [f95f9de725](https://linux-hardware.org/?probe=f95f9de725) | Jul 01, 2021 |
| HP            | EliteBook 8460p             | [e752d2b1b7](https://linux-hardware.org/?probe=e752d2b1b7) | Jul 01, 2021 |
| HP            | EliteBook 840 G2            | [1c7ba3c173](https://linux-hardware.org/?probe=1c7ba3c173) | Jul 01, 2021 |
| HP            | EliteBook 8570w             | [57d8d9da44](https://linux-hardware.org/?probe=57d8d9da44) | Jun 30, 2021 |
| Dell          | Inspiron 7472               | [0624b57fad](https://linux-hardware.org/?probe=0624b57fad) | Jun 30, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [3ec309cb24](https://linux-hardware.org/?probe=3ec309cb24) | Jun 30, 2021 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | [618305c432](https://linux-hardware.org/?probe=618305c432) | Jun 30, 2021 |
| HP            | Laptop 15-dw1xxx            | [fa67031341](https://linux-hardware.org/?probe=fa67031341) | Jun 29, 2021 |
| HP            | Notebook                    | [3087e92283](https://linux-hardware.org/?probe=3087e92283) | Jun 29, 2021 |
| HP            | Notebook                    | [510eaefd82](https://linux-hardware.org/?probe=510eaefd82) | Jun 29, 2021 |
| HP            | ENVY Laptop 17m-ch0xxx      | [a310f33226](https://linux-hardware.org/?probe=a310f33226) | Jun 29, 2021 |
| Timi          | Mi Laptop Pro 15 2020       | [6632675d89](https://linux-hardware.org/?probe=6632675d89) | Jun 29, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [afce0a6d68](https://linux-hardware.org/?probe=afce0a6d68) | Jun 29, 2021 |
| Acer          | Aspire V3-771               | [44ea4016b6](https://linux-hardware.org/?probe=44ea4016b6) | Jun 29, 2021 |
| Acer          | Aspire V3-771               | [3f2438194e](https://linux-hardware.org/?probe=3f2438194e) | Jun 29, 2021 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [a26ce90876](https://linux-hardware.org/?probe=a26ce90876) | Jun 29, 2021 |
| Wiltronic     | IVIEW Maximus Pro           | [92570b133c](https://linux-hardware.org/?probe=92570b133c) | Jun 29, 2021 |
| HP            | Pavilion dv6                | [c0e15bcf06](https://linux-hardware.org/?probe=c0e15bcf06) | Jun 27, 2021 |
| Acer          | TravelMate P653-M           | [f8509314e3](https://linux-hardware.org/?probe=f8509314e3) | Jun 27, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [5c56f0fc2f](https://linux-hardware.org/?probe=5c56f0fc2f) | Jun 27, 2021 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [d96ffce12a](https://linux-hardware.org/?probe=d96ffce12a) | Jun 27, 2021 |
| HP            | ProBook 440 G5              | [d7bcf08f6a](https://linux-hardware.org/?probe=d7bcf08f6a) | Jun 26, 2021 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | [fa17f630fc](https://linux-hardware.org/?probe=fa17f630fc) | Jun 26, 2021 |
| HP            | ProBook 440 G4              | [730c184b2b](https://linux-hardware.org/?probe=730c184b2b) | Jun 26, 2021 |
| Dell          | Inspiron MM061              | [b28ac0c857](https://linux-hardware.org/?probe=b28ac0c857) | Jun 26, 2021 |
| HP            | EliteBook 8460p             | [5808532dbd](https://linux-hardware.org/?probe=5808532dbd) | Jun 26, 2021 |
| Dell          | G3 3590                     | [06d10d0717](https://linux-hardware.org/?probe=06d10d0717) | Jun 26, 2021 |
| HP            | Laptop 15s-eq1xxx           | [d1d2e34e3c](https://linux-hardware.org/?probe=d1d2e34e3c) | Jun 25, 2021 |
| Lenovo        | ThinkPad P73 20QR0024GE     | [16b2f5dcfc](https://linux-hardware.org/?probe=16b2f5dcfc) | Jun 25, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [71134cd640](https://linux-hardware.org/?probe=71134cd640) | Jun 25, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [7c679b05c3](https://linux-hardware.org/?probe=7c679b05c3) | Jun 25, 2021 |
| Teclast       | F7 Plus                     | [a11823af5a](https://linux-hardware.org/?probe=a11823af5a) | Jun 24, 2021 |
| Dell          | Latitude E6420              | [68f21f9b57](https://linux-hardware.org/?probe=68f21f9b57) | Jun 24, 2021 |
| Medion        | E6429 MD60812               | [8f8daf18b9](https://linux-hardware.org/?probe=8f8daf18b9) | Jun 24, 2021 |
| HP            | 245 G6                      | [7f8e4b050a](https://linux-hardware.org/?probe=7f8e4b050a) | Jun 24, 2021 |
| ASUSTek       | E402SA                      | [6e79fb94aa](https://linux-hardware.org/?probe=6e79fb94aa) | Jun 24, 2021 |
| Dell          | Latitude 5511               | [10434415d8](https://linux-hardware.org/?probe=10434415d8) | Jun 24, 2021 |
| HP            | Notebook                    | [c3f23110da](https://linux-hardware.org/?probe=c3f23110da) | Jun 24, 2021 |
| Toshiba       | PORTEGE R705                | [fe7063735e](https://linux-hardware.org/?probe=fe7063735e) | Jun 24, 2021 |
| Dell          | Latitude E5540              | [a240b57157](https://linux-hardware.org/?probe=a240b57157) | Jun 24, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [7804268ecf](https://linux-hardware.org/?probe=7804268ecf) | Jun 23, 2021 |
| HP            | Pavilion dv6700             | [f1d9fcd165](https://linux-hardware.org/?probe=f1d9fcd165) | Jun 23, 2021 |
| HP            | EliteBook 8460p             | [463c88f144](https://linux-hardware.org/?probe=463c88f144) | Jun 23, 2021 |
| Acer          | Extensa 5635Z               | [8c9260d570](https://linux-hardware.org/?probe=8c9260d570) | Jun 23, 2021 |
| Dell          | Vostro 5581                 | [5e0ea603d3](https://linux-hardware.org/?probe=5e0ea603d3) | Jun 23, 2021 |
| Lenovo        | Legion Y540-15IRH 81SX      | [f52276d111](https://linux-hardware.org/?probe=f52276d111) | Jun 22, 2021 |
| Maibenben     | MaiBook S                   | [a6e045f815](https://linux-hardware.org/?probe=a6e045f815) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [b6ea706618](https://linux-hardware.org/?probe=b6ea706618) | Jun 22, 2021 |
| Dell          | Latitude 5511               | [6625368d80](https://linux-hardware.org/?probe=6625368d80) | Jun 21, 2021 |
| Positivo      | W940SU2                     | [7baff31673](https://linux-hardware.org/?probe=7baff31673) | Jun 21, 2021 |
| HP            | Laptop 17-ak0xx             | [4ae96f3d68](https://linux-hardware.org/?probe=4ae96f3d68) | Jun 21, 2021 |
| Medion        | E6429 MD60812               | [05db194f3f](https://linux-hardware.org/?probe=05db194f3f) | Jun 21, 2021 |
| Dell          | Vostro 5581                 | [bd7fdd93ec](https://linux-hardware.org/?probe=bd7fdd93ec) | Jun 21, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UF0... | [ba24de57b3](https://linux-hardware.org/?probe=ba24de57b3) | Jun 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [08c40500a8](https://linux-hardware.org/?probe=08c40500a8) | Jun 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [550a41e850](https://linux-hardware.org/?probe=550a41e850) | Jun 21, 2021 |
| ASUSTek       | X550LB                      | [81070e651b](https://linux-hardware.org/?probe=81070e651b) | Jun 21, 2021 |
| Lenovo        | ThinkPad X230 23255NG       | [e8196c8861](https://linux-hardware.org/?probe=e8196c8861) | Jun 21, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [ac12b3d63e](https://linux-hardware.org/?probe=ac12b3d63e) | Jun 21, 2021 |
| Lenovo        | Yoga 14sACH 2021 82MS       | [3f07752a76](https://linux-hardware.org/?probe=3f07752a76) | Jun 20, 2021 |
| Positivo      | CHT12CP                     | [a563fa0660](https://linux-hardware.org/?probe=a563fa0660) | Jun 20, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [a3b81cc44c](https://linux-hardware.org/?probe=a3b81cc44c) | Jun 20, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [6cd85599cd](https://linux-hardware.org/?probe=6cd85599cd) | Jun 20, 2021 |
| Pegatron      | H36Y                        | [9209a16c5c](https://linux-hardware.org/?probe=9209a16c5c) | Jun 20, 2021 |
| System76      | Serval WS serw8-17g         | [913f491e05](https://linux-hardware.org/?probe=913f491e05) | Jun 20, 2021 |
| HP            | Laptop 14-dq1xxx            | [24e2ca432c](https://linux-hardware.org/?probe=24e2ca432c) | Jun 19, 2021 |
| Dell          | Latitude E5570              | [b4bd39cf38](https://linux-hardware.org/?probe=b4bd39cf38) | Jun 19, 2021 |
| Dell          | Precision 5540              | [399b3e61e0](https://linux-hardware.org/?probe=399b3e61e0) | Jun 19, 2021 |
| HP            | Notebook                    | [daae35477b](https://linux-hardware.org/?probe=daae35477b) | Jun 19, 2021 |
| Toshiba       | PORTEGE R705                | [a53fb9eb09](https://linux-hardware.org/?probe=a53fb9eb09) | Jun 19, 2021 |
| HP            | 18-5600br                   | [d0583b92ed](https://linux-hardware.org/?probe=d0583b92ed) | Jun 19, 2021 |
| HP            | 18-5600br                   | [cd3657d994](https://linux-hardware.org/?probe=cd3657d994) | Jun 19, 2021 |
| HP            | 18-5600br                   | [cae1aa1394](https://linux-hardware.org/?probe=cae1aa1394) | Jun 18, 2021 |
| HP            | 18-5600br                   | [e3f995175a](https://linux-hardware.org/?probe=e3f995175a) | Jun 18, 2021 |
| Dell          | Latitude E6420              | [c9cefa3aea](https://linux-hardware.org/?probe=c9cefa3aea) | Jun 18, 2021 |
| Schenker      | XMG CORE 17(M20, GTX 165... | [9445d67978](https://linux-hardware.org/?probe=9445d67978) | Jun 18, 2021 |
| Lenovo        | ThinkPad L580 20LXS6NE02    | [d9a2077c08](https://linux-hardware.org/?probe=d9a2077c08) | Jun 18, 2021 |
| Dell          | Latitude XT3                | [1c523898cb](https://linux-hardware.org/?probe=1c523898cb) | Jun 18, 2021 |
| Dell          | Latitude XT3                | [80e1b1d818](https://linux-hardware.org/?probe=80e1b1d818) | Jun 18, 2021 |
| HP            | EliteBook Folio 9470m       | [33fce68a70](https://linux-hardware.org/?probe=33fce68a70) | Jun 18, 2021 |
| Dell          | XPS 15 7590                 | [11daeeac47](https://linux-hardware.org/?probe=11daeeac47) | Jun 18, 2021 |
| HP            | Pavilion Laptop 15-cc6xx    | [b0d1052f9f](https://linux-hardware.org/?probe=b0d1052f9f) | Jun 17, 2021 |
| Lenovo        | IdeaPad Flex 15 20309       | [7a60f78b32](https://linux-hardware.org/?probe=7a60f78b32) | Jun 17, 2021 |
| Acer          | Aspire A715-75G             | [32ef787520](https://linux-hardware.org/?probe=32ef787520) | Jun 17, 2021 |
| Dell          | G3 3590                     | [adf875d64d](https://linux-hardware.org/?probe=adf875d64d) | Jun 17, 2021 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [097a4a8f7c](https://linux-hardware.org/?probe=097a4a8f7c) | Jun 16, 2021 |
| Acer          | Aspire A715-75G             | [886132fd6a](https://linux-hardware.org/?probe=886132fd6a) | Jun 16, 2021 |
| Lenovo        | ThinkPad E495 20NE001MRT    | [fff555363c](https://linux-hardware.org/?probe=fff555363c) | Jun 16, 2021 |
| HP            | EliteBook 725 G3            | [f57f7d1e53](https://linux-hardware.org/?probe=f57f7d1e53) | Jun 16, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9045745027](https://linux-hardware.org/?probe=9045745027) | Jun 15, 2021 |
| Lenovo        | IdeaPad S540-15IWL          | [ab0934d142](https://linux-hardware.org/?probe=ab0934d142) | Jun 15, 2021 |
| Lenovo        | BS145-15IIL 82HB            | [e1e37c4609](https://linux-hardware.org/?probe=e1e37c4609) | Jun 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [27be88c747](https://linux-hardware.org/?probe=27be88c747) | Jun 14, 2021 |
| Dell          | Vostro 1220                 | [c951207d24](https://linux-hardware.org/?probe=c951207d24) | Jun 14, 2021 |
| HP            | 255 G7 Notebook PC          | [79627ead32](https://linux-hardware.org/?probe=79627ead32) | Jun 14, 2021 |
| Lenovo        | ThinkPad E590 20NB0029UK    | [073912d946](https://linux-hardware.org/?probe=073912d946) | Jun 14, 2021 |
| Dell          | Latitude 3350               | [7fe0552d03](https://linux-hardware.org/?probe=7fe0552d03) | Jun 14, 2021 |
| HP            | 18-5600br                   | [2fca89986a](https://linux-hardware.org/?probe=2fca89986a) | Jun 13, 2021 |
| Dell          | Studio 1735                 | [6cd1b25005](https://linux-hardware.org/?probe=6cd1b25005) | Jun 13, 2021 |
| VINGA         | Iron S140                   | [24d0a16acd](https://linux-hardware.org/?probe=24d0a16acd) | Jun 13, 2021 |
| HP            | Notebook                    | [f1263ec1fc](https://linux-hardware.org/?probe=f1263ec1fc) | Jun 13, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [8b7af4e6fa](https://linux-hardware.org/?probe=8b7af4e6fa) | Jun 13, 2021 |
| Acer          | Aspire A515-44              | [611dfe93f6](https://linux-hardware.org/?probe=611dfe93f6) | Jun 12, 2021 |
| Timi          | TM1703                      | [61a3e61fd2](https://linux-hardware.org/?probe=61a3e61fd2) | Jun 12, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [6c64f10207](https://linux-hardware.org/?probe=6c64f10207) | Jun 12, 2021 |
| Alienware     | M17xR4                      | [ea7685d41d](https://linux-hardware.org/?probe=ea7685d41d) | Jun 12, 2021 |
| UNOWHY        | Y13G002S4EI                 | [805e3de988](https://linux-hardware.org/?probe=805e3de988) | Jun 11, 2021 |
| Dell          | Inspiron 3480               | [5e9614f03e](https://linux-hardware.org/?probe=5e9614f03e) | Jun 11, 2021 |
| Chuwi         | HeroBook Pro+               | [978d937d24](https://linux-hardware.org/?probe=978d937d24) | Jun 11, 2021 |
| Lenovo        | G50-80 80L0                 | [e13e5ed99e](https://linux-hardware.org/?probe=e13e5ed99e) | Jun 11, 2021 |
| Dell          | Precision 5540              | [b21ffd09ff](https://linux-hardware.org/?probe=b21ffd09ff) | Jun 11, 2021 |
| ASUSTek       | X550LD                      | [aea5a6b230](https://linux-hardware.org/?probe=aea5a6b230) | Jun 10, 2021 |
| Acer          | AS5750G                     | [29a60b38c7](https://linux-hardware.org/?probe=29a60b38c7) | Jun 10, 2021 |
| Dell          | XPS 15 9500                 | [fa7bfd58f6](https://linux-hardware.org/?probe=fa7bfd58f6) | Jun 10, 2021 |
| Lenovo        | ThinkPad T480s 20L7001PF... | [b54604a23d](https://linux-hardware.org/?probe=b54604a23d) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | [22e9ce0306](https://linux-hardware.org/?probe=22e9ce0306) | Jun 10, 2021 |
| HUAWEI        | HLYL-WXX9                   | [4bc5bdf702](https://linux-hardware.org/?probe=4bc5bdf702) | Jun 10, 2021 |
| Acer          | Aspire A515-51G             | [301f84c1e8](https://linux-hardware.org/?probe=301f84c1e8) | Jun 09, 2021 |
| Acer          | Aspire ES1-512              | [ca026e3930](https://linux-hardware.org/?probe=ca026e3930) | Jun 09, 2021 |
| Fujitsu       | STYLISTIC Q702              | [7607b3bb86](https://linux-hardware.org/?probe=7607b3bb86) | Jun 09, 2021 |
| Dell          | XPS 15 7590                 | [03514539b0](https://linux-hardware.org/?probe=03514539b0) | Jun 09, 2021 |
| MSI           | GS63 Stealth 8RE            | [a098121a4b](https://linux-hardware.org/?probe=a098121a4b) | Jun 09, 2021 |
| Acer          | Aspire A517-51P             | [0d9f4bfb3f](https://linux-hardware.org/?probe=0d9f4bfb3f) | Jun 08, 2021 |
| Acer          | Aspire V5-573G              | [4f2c1d3cf1](https://linux-hardware.org/?probe=4f2c1d3cf1) | Jun 08, 2021 |
| HP            | Pavilion dv5                | [a3ec72db59](https://linux-hardware.org/?probe=a3ec72db59) | Jun 08, 2021 |
| ASUSTek       | F50Z                        | [cf099f4a72](https://linux-hardware.org/?probe=cf099f4a72) | Jun 08, 2021 |
| Dell          | Inspiron 3480               | [c37379b181](https://linux-hardware.org/?probe=c37379b181) | Jun 08, 2021 |
| Dell          | Latitude E7440              | [5f0d57018e](https://linux-hardware.org/?probe=5f0d57018e) | Jun 07, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [7c843291b5](https://linux-hardware.org/?probe=7c843291b5) | Jun 07, 2021 |
| Dell          | Inspiron N5110              | [81034d3717](https://linux-hardware.org/?probe=81034d3717) | Jun 07, 2021 |
| Lenovo        | V14-IIL 82C4                | [5ccbd0c9dc](https://linux-hardware.org/?probe=5ccbd0c9dc) | Jun 07, 2021 |
| Lenovo        | V14-IIL 82C4                | [bf27f62c50](https://linux-hardware.org/?probe=bf27f62c50) | Jun 07, 2021 |
| Lenovo        | 100e 2nd Gen 82GJ           | [ce0d33750c](https://linux-hardware.org/?probe=ce0d33750c) | Jun 06, 2021 |
| Fujitsu       | LIFEBOOK S751               | [8cf5dc5f75](https://linux-hardware.org/?probe=8cf5dc5f75) | Jun 06, 2021 |
| Apple         | MacBookPro10,1              | [4081189cda](https://linux-hardware.org/?probe=4081189cda) | Jun 06, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [e192001666](https://linux-hardware.org/?probe=e192001666) | Jun 06, 2021 |
| ASUSTek       | G72GX                       | [9445bda61c](https://linux-hardware.org/?probe=9445bda61c) | Jun 05, 2021 |
| Lenovo        | ThinkPad T61 6463WCH        | [7497f56037](https://linux-hardware.org/?probe=7497f56037) | Jun 05, 2021 |
| Acer          | Aspire 5742Z                | [89ae1206bb](https://linux-hardware.org/?probe=89ae1206bb) | Jun 05, 2021 |
| Fujitsu       | LIFEBOOK A530               | [f8d06e3e17](https://linux-hardware.org/?probe=f8d06e3e17) | Jun 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f0133f78dc](https://linux-hardware.org/?probe=f0133f78dc) | Jun 04, 2021 |
| Acer          | Aspire ES1-512              | [fa65ebf8c6](https://linux-hardware.org/?probe=fa65ebf8c6) | Jun 04, 2021 |
| Dell          | Inspiron 3480               | [cf9db1ce7a](https://linux-hardware.org/?probe=cf9db1ce7a) | Jun 04, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [99de24cb78](https://linux-hardware.org/?probe=99de24cb78) | Jun 04, 2021 |
| Dell          | Inspiron 3505               | [fe512b6857](https://linux-hardware.org/?probe=fe512b6857) | Jun 04, 2021 |
| HP            | ProBook 4430s               | [46588303b9](https://linux-hardware.org/?probe=46588303b9) | Jun 03, 2021 |
| HP            | ProBook 4430s               | [53188205ea](https://linux-hardware.org/?probe=53188205ea) | Jun 03, 2021 |
| HP            | EliteBook 840 G1            | [7a364bc855](https://linux-hardware.org/?probe=7a364bc855) | Jun 03, 2021 |
| LG Electro... | 16Z90P-G.AA76G              | [7a64de799d](https://linux-hardware.org/?probe=7a64de799d) | Jun 03, 2021 |
| Toshiba       | PORTEGE Z930                | [4a95259edd](https://linux-hardware.org/?probe=4a95259edd) | Jun 03, 2021 |
| Dell          | Latitude 3350               | [abb4701070](https://linux-hardware.org/?probe=abb4701070) | Jun 03, 2021 |
| ASUSTek       | X550LB                      | [c5c49a53de](https://linux-hardware.org/?probe=c5c49a53de) | Jun 03, 2021 |
| HP            | Pavilion dv6                | [caa052636f](https://linux-hardware.org/?probe=caa052636f) | Jun 03, 2021 |
| HP            | Laptop 15s-eq1xxx           | [d53b1525ed](https://linux-hardware.org/?probe=d53b1525ed) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | [6b5f1170f9](https://linux-hardware.org/?probe=6b5f1170f9) | Jun 02, 2021 |
| HP            | Laptop 14-ck0xxx            | [e2389864db](https://linux-hardware.org/?probe=e2389864db) | Jun 02, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [ea28219e8a](https://linux-hardware.org/?probe=ea28219e8a) | Jun 02, 2021 |
| Dell          | Studio 1735                 | [b0485d3960](https://linux-hardware.org/?probe=b0485d3960) | Jun 02, 2021 |
| HP            | EliteBook 850 G7 Noteboo... | [8533dbc1de](https://linux-hardware.org/?probe=8533dbc1de) | Jun 02, 2021 |
| Dell          | Latitude 9520               | [10a4c770cf](https://linux-hardware.org/?probe=10a4c770cf) | Jun 02, 2021 |
| Acer          | Aspire A515-44              | [390085b056](https://linux-hardware.org/?probe=390085b056) | Jun 02, 2021 |
| Lenovo        | ThinkPad T430 2350B58       | [61b78ffc77](https://linux-hardware.org/?probe=61b78ffc77) | Jun 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0271a8fd47](https://linux-hardware.org/?probe=0271a8fd47) | Jun 02, 2021 |
| Dell          | Inspiron 3505               | [6efb3f85be](https://linux-hardware.org/?probe=6efb3f85be) | Jun 02, 2021 |
| HP            | ProBook 6560b               | [f9ee7c5367](https://linux-hardware.org/?probe=f9ee7c5367) | Jun 01, 2021 |
| HP            | ProBook 450 G6              | [6c241e0b82](https://linux-hardware.org/?probe=6c241e0b82) | Jun 01, 2021 |
| Dell          | Inspiron 5370               | [51235b00db](https://linux-hardware.org/?probe=51235b00db) | Jun 01, 2021 |
| HP            | ProBook 6560b               | [f2b70f9230](https://linux-hardware.org/?probe=f2b70f9230) | Jun 01, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [36f36a1183](https://linux-hardware.org/?probe=36f36a1183) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | [07aa0b9e2b](https://linux-hardware.org/?probe=07aa0b9e2b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | [6b0fca64c4](https://linux-hardware.org/?probe=6b0fca64c4) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | [4c650b1991](https://linux-hardware.org/?probe=4c650b1991) | Jun 01, 2021 |
| Lenovo        | G50-80 80E5                 | [09cc2aed35](https://linux-hardware.org/?probe=09cc2aed35) | May 31, 2021 |
| Dell          | Latitude 3350               | [14584ee6c7](https://linux-hardware.org/?probe=14584ee6c7) | May 31, 2021 |
| HP            | ProBook 6560b               | [523614fee6](https://linux-hardware.org/?probe=523614fee6) | May 31, 2021 |
| HP            | Pavilion dv6                | [6ac306c0da](https://linux-hardware.org/?probe=6ac306c0da) | May 31, 2021 |
| Lenovo        | V560                        | [62053ae42b](https://linux-hardware.org/?probe=62053ae42b) | May 30, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | [f8eb7b0f52](https://linux-hardware.org/?probe=f8eb7b0f52) | May 30, 2021 |
| Lenovo        | ThinkPad L590 20Q8S1FX00    | [d7f2524297](https://linux-hardware.org/?probe=d7f2524297) | May 30, 2021 |
| HCL Infosy... | HCL ME Laptop               | [5c17f36c61](https://linux-hardware.org/?probe=5c17f36c61) | May 30, 2021 |
| Lenovo        | ThinkPad T420 42366Y0       | [74547808d3](https://linux-hardware.org/?probe=74547808d3) | May 30, 2021 |
| HUAWEI        | MACH-WX9                    | [9358c3afbf](https://linux-hardware.org/?probe=9358c3afbf) | May 29, 2021 |
| Dell          | Inspiron 3505               | [4157528079](https://linux-hardware.org/?probe=4157528079) | May 29, 2021 |
| Lenovo        | ThinkPad T420 42366Y0       | [d36582d3d6](https://linux-hardware.org/?probe=d36582d3d6) | May 29, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [e2d1740f3a](https://linux-hardware.org/?probe=e2d1740f3a) | May 28, 2021 |
| Acer          | Aspire A515-55              | [09499164b9](https://linux-hardware.org/?probe=09499164b9) | May 28, 2021 |
| ASUSTek       | X550LB                      | [21f1da73fd](https://linux-hardware.org/?probe=21f1da73fd) | May 28, 2021 |
| ASUSTek       | X550LB                      | [cc4245844a](https://linux-hardware.org/?probe=cc4245844a) | May 28, 2021 |
| Acer          | Aspire E5-553               | [70037bddcb](https://linux-hardware.org/?probe=70037bddcb) | May 27, 2021 |
| Samsung       | RF510/RF410/RF710           | [ee109d9097](https://linux-hardware.org/?probe=ee109d9097) | May 27, 2021 |
| Dell          | Latitude 5520               | [f9327e8bb8](https://linux-hardware.org/?probe=f9327e8bb8) | May 27, 2021 |
| Acer          | Aspire A515-55              | [3cfa12f511](https://linux-hardware.org/?probe=3cfa12f511) | May 27, 2021 |
| Alienware     | M17xR4                      | [d3da4ef72c](https://linux-hardware.org/?probe=d3da4ef72c) | May 27, 2021 |
| Alienware     | M17xR4                      | [f534e321eb](https://linux-hardware.org/?probe=f534e321eb) | May 27, 2021 |
| ASUSTek       | GL553VD                     | [5c45dfb686](https://linux-hardware.org/?probe=5c45dfb686) | May 26, 2021 |
| ASUSTek       | GL553VD                     | [5177972753](https://linux-hardware.org/?probe=5177972753) | May 26, 2021 |
| HP            | Laptop 15-dy2xxx            | [5ec38e0f3f](https://linux-hardware.org/?probe=5ec38e0f3f) | May 25, 2021 |
| Lenovo        | ThinkPad T410 2537Z2J       | [d86d3e8984](https://linux-hardware.org/?probe=d86d3e8984) | May 25, 2021 |
| Apple         | MacBookPro8,3               | [c34278c355](https://linux-hardware.org/?probe=c34278c355) | May 25, 2021 |
| Dell          | G7 7500                     | [89f41d7487](https://linux-hardware.org/?probe=89f41d7487) | May 25, 2021 |
| HP            | EliteBook 820 G2            | [f9ed2cd1c9](https://linux-hardware.org/?probe=f9ed2cd1c9) | May 25, 2021 |
| MSI           | GS60 2QE                    | [7ef8c79c08](https://linux-hardware.org/?probe=7ef8c79c08) | May 24, 2021 |
| Apple         | MacBookAir5,2               | [ec1abd9485](https://linux-hardware.org/?probe=ec1abd9485) | May 24, 2021 |
| Sony          | VGN-AR850E                  | [e17fe551fb](https://linux-hardware.org/?probe=e17fe551fb) | May 24, 2021 |
| MSI           | GS60 2QE                    | [1660ac34ec](https://linux-hardware.org/?probe=1660ac34ec) | May 24, 2021 |
| ASUSTek       | ROG Strix G533QR_G533QR     | [f6856776e4](https://linux-hardware.org/?probe=f6856776e4) | May 24, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [08d0784b54](https://linux-hardware.org/?probe=08d0784b54) | May 24, 2021 |
| Lenovo        | G500 20236                  | [91cf490677](https://linux-hardware.org/?probe=91cf490677) | May 24, 2021 |
| Dell          | G5 5587                     | [65c1600593](https://linux-hardware.org/?probe=65c1600593) | May 24, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [2bbea8f317](https://linux-hardware.org/?probe=2bbea8f317) | May 24, 2021 |
| HUAWEI        | MACH-WX9                    | [1261bed89a](https://linux-hardware.org/?probe=1261bed89a) | May 24, 2021 |
| Acer          | TravelMate P215-53          | [dc89b4797f](https://linux-hardware.org/?probe=dc89b4797f) | May 24, 2021 |
| Acer          | Aspire one 1-431            | [db306fa1f7](https://linux-hardware.org/?probe=db306fa1f7) | May 24, 2021 |
| Dell          | Inspiron 1525               | [6fbef63c17](https://linux-hardware.org/?probe=6fbef63c17) | May 23, 2021 |
| Toshiba       | PORTEGE Z930                | [5169c2f96a](https://linux-hardware.org/?probe=5169c2f96a) | May 23, 2021 |
| Acer          | TravelMate P215-53          | [18ea2a888a](https://linux-hardware.org/?probe=18ea2a888a) | May 23, 2021 |
| System76      | Galago Pro                  | [7bc86eb366](https://linux-hardware.org/?probe=7bc86eb366) | May 23, 2021 |
| Dell          | XPS 13 9360                 | [97dbd7a2d0](https://linux-hardware.org/?probe=97dbd7a2d0) | May 23, 2021 |
| HUAWEI        | KLVL-WXX9                   | [8a8a2bded7](https://linux-hardware.org/?probe=8a8a2bded7) | May 23, 2021 |
| HP            | Pavilion dv5                | [97c2972e03](https://linux-hardware.org/?probe=97c2972e03) | May 22, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [b3da27422d](https://linux-hardware.org/?probe=b3da27422d) | May 22, 2021 |
| Acer          | Swift SF314-59              | [c781b981de](https://linux-hardware.org/?probe=c781b981de) | May 22, 2021 |
| Unknown       | T3 MRD                      | [1c16d2db6c](https://linux-hardware.org/?probe=1c16d2db6c) | May 21, 2021 |
| Lenovo        | ThinkPad T61 6463WCH        | [e1b3b6e090](https://linux-hardware.org/?probe=e1b3b6e090) | May 21, 2021 |
| Sony          | VGN-NS21Z_S                 | [4c412bd16f](https://linux-hardware.org/?probe=4c412bd16f) | May 21, 2021 |
| Dell          | Latitude 5410               | [6b5502593e](https://linux-hardware.org/?probe=6b5502593e) | May 21, 2021 |
| HP            | Spectre Pro x360 G2         | [236efc033e](https://linux-hardware.org/?probe=236efc033e) | May 21, 2021 |
| Dell          | Precision 5530              | [a5c63380d6](https://linux-hardware.org/?probe=a5c63380d6) | May 21, 2021 |
| Razer         | Blade Stealth               | [274e57be67](https://linux-hardware.org/?probe=274e57be67) | May 21, 2021 |
| HP            | Pavilion Notebook           | [d63952115c](https://linux-hardware.org/?probe=d63952115c) | May 20, 2021 |
| HP            | 15                          | [814d85cf91](https://linux-hardware.org/?probe=814d85cf91) | May 20, 2021 |
| HP            | 350 G1                      | [949ae1ce88](https://linux-hardware.org/?probe=949ae1ce88) | May 20, 2021 |
| Dell          | XPS 15 7590                 | [6d6ff7b4d8](https://linux-hardware.org/?probe=6d6ff7b4d8) | May 20, 2021 |
| Fujitsu       | LIFEBOOK T730               | [f220f9ac45](https://linux-hardware.org/?probe=f220f9ac45) | May 20, 2021 |
| Dell          | Inspiron 3505               | [c973055db8](https://linux-hardware.org/?probe=c973055db8) | May 20, 2021 |
| HUAWEI        | MACH-WX9                    | [6331748487](https://linux-hardware.org/?probe=6331748487) | May 20, 2021 |
| Lenovo        | ThinkPad W510 4318CTO       | [ed2a5f47c6](https://linux-hardware.org/?probe=ed2a5f47c6) | May 20, 2021 |
| Acer          | Aspire A515-43              | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| HP            | ProBook 455 G7              | [30a5ddc9a4](https://linux-hardware.org/?probe=30a5ddc9a4) | May 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [013af3c5de](https://linux-hardware.org/?probe=013af3c5de) | May 19, 2021 |
| ASUSTek       | GL502VSK                    | [577af42985](https://linux-hardware.org/?probe=577af42985) | May 19, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [99d22d0422](https://linux-hardware.org/?probe=99d22d0422) | May 19, 2021 |
| HP            | Pavilion 15                 | [c689ad926b](https://linux-hardware.org/?probe=c689ad926b) | May 19, 2021 |
| ASUSTek       | T100HAN                     | [bb0d60af3d](https://linux-hardware.org/?probe=bb0d60af3d) | May 19, 2021 |
| Notebook      | PCX0DX                      | [4556010665](https://linux-hardware.org/?probe=4556010665) | May 18, 2021 |
| Toshiba       | PORTEGE Z930                | [3b82b0b360](https://linux-hardware.org/?probe=3b82b0b360) | May 18, 2021 |
| Toshiba       | PORTEGE Z930                | [e006b8bf83](https://linux-hardware.org/?probe=e006b8bf83) | May 18, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [12ffaaefb1](https://linux-hardware.org/?probe=12ffaaefb1) | May 18, 2021 |
| ASUSTek       | X550LB                      | [3dc677388a](https://linux-hardware.org/?probe=3dc677388a) | May 18, 2021 |
| Apple         | MacBook5,1                  | [1bfce84c69](https://linux-hardware.org/?probe=1bfce84c69) | May 17, 2021 |
| HP            | ProBook 450 G7              | [deb906b69f](https://linux-hardware.org/?probe=deb906b69f) | May 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [7724221aba](https://linux-hardware.org/?probe=7724221aba) | May 17, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | [0e9e4151e9](https://linux-hardware.org/?probe=0e9e4151e9) | May 17, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [ed92840007](https://linux-hardware.org/?probe=ed92840007) | May 17, 2021 |
| Fujitsu       | STYLISTIC Q702              | [6af6b1aa99](https://linux-hardware.org/?probe=6af6b1aa99) | May 17, 2021 |
| Acer          | Aspire E3-112               | [fed9ba4c7d](https://linux-hardware.org/?probe=fed9ba4c7d) | May 16, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [65a3c1a830](https://linux-hardware.org/?probe=65a3c1a830) | May 16, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | [0c0dec114b](https://linux-hardware.org/?probe=0c0dec114b) | May 16, 2021 |
| Lenovo        | ThinkPad P53 20QNCTO1WW     | [5c67466a7e](https://linux-hardware.org/?probe=5c67466a7e) | May 16, 2021 |
| Dell          | XPS M1530                   | [19be0f2492](https://linux-hardware.org/?probe=19be0f2492) | May 16, 2021 |
| Dell          | Precision 3551              | [a080388baa](https://linux-hardware.org/?probe=a080388baa) | May 16, 2021 |
| Dell          | Precision 3551              | [f9f9852b96](https://linux-hardware.org/?probe=f9f9852b96) | May 16, 2021 |
| Dell          | Latitude 5285               | [c5396b5734](https://linux-hardware.org/?probe=c5396b5734) | May 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [00a8ed533c](https://linux-hardware.org/?probe=00a8ed533c) | May 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [14b8295348](https://linux-hardware.org/?probe=14b8295348) | May 15, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [30fa3fc2c7](https://linux-hardware.org/?probe=30fa3fc2c7) | May 15, 2021 |
| Dell          | Latitude 3350               | [f4e6b7cf7f](https://linux-hardware.org/?probe=f4e6b7cf7f) | May 15, 2021 |
| Positivo      | C14CR21TV                   | [8af930f7e1](https://linux-hardware.org/?probe=8af930f7e1) | May 15, 2021 |
| Lenovo        | G40-70 80GA                 | [619b20ccfb](https://linux-hardware.org/?probe=619b20ccfb) | May 15, 2021 |
| Lenovo        | G40-70 80GA                 | [c674fa597f](https://linux-hardware.org/?probe=c674fa597f) | May 15, 2021 |
| HP            | 1000                        | [d23f6c89ad](https://linux-hardware.org/?probe=d23f6c89ad) | May 15, 2021 |
| HP            | G62                         | [aec231d673](https://linux-hardware.org/?probe=aec231d673) | May 14, 2021 |
| Apple         | MacBookAir7,2               | [df405076a1](https://linux-hardware.org/?probe=df405076a1) | May 14, 2021 |
| MSI           | GF65 Thin 10SDR             | [fcbfa1c448](https://linux-hardware.org/?probe=fcbfa1c448) | May 14, 2021 |
| Sony          | VGN-AR51SU                  | [6d72715029](https://linux-hardware.org/?probe=6d72715029) | May 13, 2021 |
| Dell          | Latitude 3350               | [bb64b2df5c](https://linux-hardware.org/?probe=bb64b2df5c) | May 13, 2021 |
| HP            | ProBook 430 G1              | [20a2c142bf](https://linux-hardware.org/?probe=20a2c142bf) | May 13, 2021 |
| Insignia      | NS-P11W7100                 | [6bb54d0349](https://linux-hardware.org/?probe=6bb54d0349) | May 13, 2021 |
| ASUSTek       | ZenBook UX431FAC_UX431FA    | [9f56d64c9d](https://linux-hardware.org/?probe=9f56d64c9d) | May 13, 2021 |
| HP            | ProBook 450 G4              | [b8108b310a](https://linux-hardware.org/?probe=b8108b310a) | May 13, 2021 |
| HP            | ProBook 450 G4              | [c596247722](https://linux-hardware.org/?probe=c596247722) | May 13, 2021 |
| HP            | 1000                        | [a1ff0a7b3d](https://linux-hardware.org/?probe=a1ff0a7b3d) | May 13, 2021 |
| HP            | 1000                        | [4bbe06ec7a](https://linux-hardware.org/?probe=4bbe06ec7a) | May 13, 2021 |
| MSI           | Prestige 15 A11SCS          | [f892f92e65](https://linux-hardware.org/?probe=f892f92e65) | May 12, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [ca2397cddf](https://linux-hardware.org/?probe=ca2397cddf) | May 12, 2021 |
| Dell          | Precision M4500             | [784b8e3db4](https://linux-hardware.org/?probe=784b8e3db4) | May 11, 2021 |
| HP            | EliteBook 850 G4            | [2502c3d7e7](https://linux-hardware.org/?probe=2502c3d7e7) | May 11, 2021 |
| Positivo B... | VJFE53F11X-XXXXXX           | [2543210bfd](https://linux-hardware.org/?probe=2543210bfd) | May 11, 2021 |
| Acer          | Swift SF114-32              | [09ca2a6a53](https://linux-hardware.org/?probe=09ca2a6a53) | May 10, 2021 |
| Apple         | MacBookPro8,3               | [0537199c9f](https://linux-hardware.org/?probe=0537199c9f) | May 10, 2021 |
| Sony          | VPCCW2S8E                   | [4398b323b3](https://linux-hardware.org/?probe=4398b323b3) | May 10, 2021 |
| Sony          | VPCCW2S8E                   | [eba79cc54f](https://linux-hardware.org/?probe=eba79cc54f) | May 10, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [5ca33ceca6](https://linux-hardware.org/?probe=5ca33ceca6) | May 10, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [fc4143b244](https://linux-hardware.org/?probe=fc4143b244) | May 10, 2021 |
| Apple         | MacBookPro8,1               | [8afdfe2827](https://linux-hardware.org/?probe=8afdfe2827) | May 10, 2021 |
| Acer          | Aspire A315-33              | [b50018b47b](https://linux-hardware.org/?probe=b50018b47b) | May 09, 2021 |
| Dell          | Vostro 7500                 | [6041d49bff](https://linux-hardware.org/?probe=6041d49bff) | May 09, 2021 |
| Apple         | MacBookPro8,1               | [5da4e125b2](https://linux-hardware.org/?probe=5da4e125b2) | May 09, 2021 |
| Dell          | XPS 15 9500                 | [cf55e0e340](https://linux-hardware.org/?probe=cf55e0e340) | May 09, 2021 |
| Dell          | XPS 15 9500                 | [287b32a385](https://linux-hardware.org/?probe=287b32a385) | May 09, 2021 |
| HP            | Laptop 17-bs0xx             | [e6623d7b8e](https://linux-hardware.org/?probe=e6623d7b8e) | May 09, 2021 |
| Lenovo        | E41-25 81FS                 | [4ccf4659d4](https://linux-hardware.org/?probe=4ccf4659d4) | May 08, 2021 |
| Lenovo        | E41-25 81FS                 | [532af26481](https://linux-hardware.org/?probe=532af26481) | May 08, 2021 |
| Lenovo        | ThinkPad P50 20EN0007MS     | [adfdb43f0b](https://linux-hardware.org/?probe=adfdb43f0b) | May 08, 2021 |
| MSI           | GS66 Stealth 10SE           | [2869638c1b](https://linux-hardware.org/?probe=2869638c1b) | May 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [b7e4895fd8](https://linux-hardware.org/?probe=b7e4895fd8) | May 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [9d937a5244](https://linux-hardware.org/?probe=9d937a5244) | May 07, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [089fa466bc](https://linux-hardware.org/?probe=089fa466bc) | May 07, 2021 |
| HP            | Laptop 17-bs0xx             | [86f4c24f8f](https://linux-hardware.org/?probe=86f4c24f8f) | May 07, 2021 |
| ASUSTek       | K52F                        | [871f4c23c5](https://linux-hardware.org/?probe=871f4c23c5) | May 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [34b008d2a3](https://linux-hardware.org/?probe=34b008d2a3) | May 06, 2021 |
| Samsung       | RC530/RC730                 | [479ca4a221](https://linux-hardware.org/?probe=479ca4a221) | May 06, 2021 |
| Samsung       | RC530/RC730                 | [96541e6169](https://linux-hardware.org/?probe=96541e6169) | May 06, 2021 |
| HP            | ZBook 15                    | [ccdf2eebed](https://linux-hardware.org/?probe=ccdf2eebed) | May 06, 2021 |
| HP            | ZBook 15                    | [702b924ad3](https://linux-hardware.org/?probe=702b924ad3) | May 06, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [bc90a54ebf](https://linux-hardware.org/?probe=bc90a54ebf) | May 06, 2021 |
| HUAWEI        | HLYL-WXX9                   | [a8ae42440e](https://linux-hardware.org/?probe=a8ae42440e) | May 06, 2021 |
| ASUSTek       | T100TA                      | [61c9e8ca48](https://linux-hardware.org/?probe=61c9e8ca48) | May 05, 2021 |
| Acer          | Swift SF314-59              | [5a4f35e056](https://linux-hardware.org/?probe=5a4f35e056) | May 05, 2021 |
| Standard      | Unknown                     | [e9a891227f](https://linux-hardware.org/?probe=e9a891227f) | May 05, 2021 |
| HP            | ProBook 430 G1              | [64221d8f8a](https://linux-hardware.org/?probe=64221d8f8a) | May 04, 2021 |
| HP            | Pavilion Notebook           | [2d0fb807ed](https://linux-hardware.org/?probe=2d0fb807ed) | May 04, 2021 |
| Dell          | Vostro 5490                 | [c89b28e2f3](https://linux-hardware.org/?probe=c89b28e2f3) | May 03, 2021 |
| Acer          | Predator G9-793             | [90b04b667a](https://linux-hardware.org/?probe=90b04b667a) | May 03, 2021 |
| Dell          | Vostro 5490                 | [b852cc3b14](https://linux-hardware.org/?probe=b852cc3b14) | May 03, 2021 |
| Dell          | Vostro 5490                 | [43ecd6539f](https://linux-hardware.org/?probe=43ecd6539f) | May 03, 2021 |
| HP            | EliteBook 2540p             | [506fb4d003](https://linux-hardware.org/?probe=506fb4d003) | May 02, 2021 |
| HP            | Pavilion Notebook           | [dc246b5e6d](https://linux-hardware.org/?probe=dc246b5e6d) | May 02, 2021 |
| System76      | Galago Pro                  | [0081dd52a5](https://linux-hardware.org/?probe=0081dd52a5) | May 02, 2021 |
| Lenovo        | ThinkPad T470 20HES1HD01    | [4eb1086713](https://linux-hardware.org/?probe=4eb1086713) | May 02, 2021 |
| TUXEDO        | Unknown                     | [9e7bc88973](https://linux-hardware.org/?probe=9e7bc88973) | May 02, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [6223ea92f1](https://linux-hardware.org/?probe=6223ea92f1) | May 02, 2021 |
| Dell          | Vostro 3550                 | [8c78374db7](https://linux-hardware.org/?probe=8c78374db7) | May 02, 2021 |
| Acer          | Aspire A515-43              | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP            | ProBook 6460b               | [24fab4aa05](https://linux-hardware.org/?probe=24fab4aa05) | May 02, 2021 |
| HUAWEI        | WRTB-WXX9                   | [f9ceb7c523](https://linux-hardware.org/?probe=f9ceb7c523) | May 02, 2021 |
| Dell          | Vostro 3550                 | [9eaacbadec](https://linux-hardware.org/?probe=9eaacbadec) | May 01, 2021 |
| Sony          | VGN-FZ11S                   | [bd472575f4](https://linux-hardware.org/?probe=bd472575f4) | May 01, 2021 |
| Lenovo        | ThinkPad E480 20KN0061RT    | [6d6d654a5a](https://linux-hardware.org/?probe=6d6d654a5a) | May 01, 2021 |
| Lenovo        | ThinkPad E470 20H2S00700    | [cc35722c1f](https://linux-hardware.org/?probe=cc35722c1f) | May 01, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [d0838b99d8](https://linux-hardware.org/?probe=d0838b99d8) | May 01, 2021 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [7d6a70d93f](https://linux-hardware.org/?probe=7d6a70d93f) | Apr 30, 2021 |
| Samsung       | 270E5J/2570EJ               | [48c0082d7e](https://linux-hardware.org/?probe=48c0082d7e) | Apr 29, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | [61c335bd08](https://linux-hardware.org/?probe=61c335bd08) | Apr 28, 2021 |
| Acer          | Swift SF114-32              | [2b9b5faf20](https://linux-hardware.org/?probe=2b9b5faf20) | Apr 28, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [8e8858711b](https://linux-hardware.org/?probe=8e8858711b) | Apr 28, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [2c4d248451](https://linux-hardware.org/?probe=2c4d248451) | Apr 28, 2021 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | [56406a43bd](https://linux-hardware.org/?probe=56406a43bd) | Apr 28, 2021 |
| MSI           | GL75 Leopard 10SDR          | [458deed3d3](https://linux-hardware.org/?probe=458deed3d3) | Apr 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [b3217892ed](https://linux-hardware.org/?probe=b3217892ed) | Apr 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [ec5b0541a2](https://linux-hardware.org/?probe=ec5b0541a2) | Apr 27, 2021 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [8638d59270](https://linux-hardware.org/?probe=8638d59270) | Apr 27, 2021 |
| Lenovo        | Yoga S940-14IWL 81Q7        | [f729b14cca](https://linux-hardware.org/?probe=f729b14cca) | Apr 27, 2021 |
| Dell          | Inspiron 5593               | [cd9f6f91af](https://linux-hardware.org/?probe=cd9f6f91af) | Apr 26, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | [604a50766b](https://linux-hardware.org/?probe=604a50766b) | Apr 26, 2021 |
| HP            | EliteBook 840 G5            | [266fb405d7](https://linux-hardware.org/?probe=266fb405d7) | Apr 26, 2021 |
| Toshiba       | Satellite A350              | [5da06fd6b1](https://linux-hardware.org/?probe=5da06fd6b1) | Apr 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [bf2ec3a69c](https://linux-hardware.org/?probe=bf2ec3a69c) | Apr 26, 2021 |
| TUXEDO        | Unknown                     | [0609ea696c](https://linux-hardware.org/?probe=0609ea696c) | Apr 26, 2021 |
| Dell          | Inspiron 3542               | [9e090254cd](https://linux-hardware.org/?probe=9e090254cd) | Apr 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [0bcc333251](https://linux-hardware.org/?probe=0bcc333251) | Apr 25, 2021 |
| Lenovo        | ThinkPad T410 2537FP3       | [ae38a32169](https://linux-hardware.org/?probe=ae38a32169) | Apr 25, 2021 |
| Lenovo        | ThinkPad T410 2537FP3       | [45559a492c](https://linux-hardware.org/?probe=45559a492c) | Apr 25, 2021 |
| Lenovo        | ThinkPad T420 4236EF4       | [4d07ea7b58](https://linux-hardware.org/?probe=4d07ea7b58) | Apr 24, 2021 |
| Samsung       | NC210/NC110                 | [45678e2907](https://linux-hardware.org/?probe=45678e2907) | Apr 24, 2021 |
| Samsung       | NC210/NC110                 | [f178c672cf](https://linux-hardware.org/?probe=f178c672cf) | Apr 24, 2021 |
| HUAWEI        | MACHC-WAX9                  | [15cbbda6f8](https://linux-hardware.org/?probe=15cbbda6f8) | Apr 24, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [b6b305b0bd](https://linux-hardware.org/?probe=b6b305b0bd) | Apr 24, 2021 |
| HP            | ProBook 450 G7              | [f5bfb4f382](https://linux-hardware.org/?probe=f5bfb4f382) | Apr 24, 2021 |
| HP            | ProBook 450 G7              | [af9117e999](https://linux-hardware.org/?probe=af9117e999) | Apr 24, 2021 |
| ASUSTek       | K50IN                       | [7a84f17bdb](https://linux-hardware.org/?probe=7a84f17bdb) | Apr 23, 2021 |
| Lenovo        | ThinkPad X250 20CLS55S00    | [5dc10377ab](https://linux-hardware.org/?probe=5dc10377ab) | Apr 23, 2021 |
| ASUSTek       | ROG Zephyrus M15 GU502LU... | [3120e73dca](https://linux-hardware.org/?probe=3120e73dca) | Apr 23, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [470c00d1c5](https://linux-hardware.org/?probe=470c00d1c5) | Apr 23, 2021 |
| Dell          | XPS 15 7590                 | [7963c5b064](https://linux-hardware.org/?probe=7963c5b064) | Apr 23, 2021 |
| Lenovo        | ThinkPad T420 4236EF4       | [015d11b9cb](https://linux-hardware.org/?probe=015d11b9cb) | Apr 19, 2021 |
| Acer          | Aspire E5-771G              | [eb63a6bb36](https://linux-hardware.org/?probe=eb63a6bb36) | Apr 17, 2021 |
| Acer          | Aspire E5-771G              | [e3bc507a07](https://linux-hardware.org/?probe=e3bc507a07) | Apr 17, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [4e23f3b6b5](https://linux-hardware.org/?probe=4e23f3b6b5) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [18ee0d2d64](https://linux-hardware.org/?probe=18ee0d2d64) | Apr 16, 2021 |
| HP            | Compaq CQ58                 | [3274addf89](https://linux-hardware.org/?probe=3274addf89) | Apr 14, 2021 |
| HP            | Spectre XT Ultrabook PC     | [adf30d3202](https://linux-hardware.org/?probe=adf30d3202) | Apr 09, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [519d1fea88](https://linux-hardware.org/?probe=519d1fea88) | Apr 09, 2021 |
| Dell          | Inspiron 7560               | [b3110fa6fb](https://linux-hardware.org/?probe=b3110fa6fb) | Apr 09, 2021 |
| ASUSTek       | X542URR                     | [d49a5f2b6c](https://linux-hardware.org/?probe=d49a5f2b6c) | Apr 07, 2021 |
| Lenovo        | ThinkPad T430 2349DD5       | [3cf8173314](https://linux-hardware.org/?probe=3cf8173314) | Apr 05, 2021 |
| Lenovo        | B50-70 80EU                 | [6534232c53](https://linux-hardware.org/?probe=6534232c53) | Apr 04, 2021 |
| HUAWEI        | MACH-WX9                    | [806a28ffcb](https://linux-hardware.org/?probe=806a28ffcb) | Apr 02, 2021 |
| Lenovo        | ThinkPad T430 2349UWT       | [d6edf7c2df](https://linux-hardware.org/?probe=d6edf7c2df) | Mar 28, 2021 |
| Dell          | G3 3500                     | [83f2a24875](https://linux-hardware.org/?probe=83f2a24875) | Mar 27, 2021 |
| Google        | Edgar                       | [e31c334180](https://linux-hardware.org/?probe=e31c334180) | Mar 23, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [50b82af935](https://linux-hardware.org/?probe=50b82af935) | Mar 18, 2021 |
| Acer          | Aspire A515-56              | [1bdc8a756f](https://linux-hardware.org/?probe=1bdc8a756f) | Mar 17, 2021 |
| Razer         | Blade                       | [638dd21f45](https://linux-hardware.org/?probe=638dd21f45) | Mar 03, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | [986679aa93](https://linux-hardware.org/?probe=986679aa93) | Feb 25, 2021 |
| Dell          | XPS 15 7590                 | [bded62870c](https://linux-hardware.org/?probe=bded62870c) | Feb 23, 2021 |
| Acer          | Aspire A515-44              | [d87649a1b4](https://linux-hardware.org/?probe=d87649a1b4) | Jan 27, 2021 |
| Acer          | Aspire A515-44              | [ea1a9ef713](https://linux-hardware.org/?probe=ea1a9ef713) | Jan 27, 2021 |
| HASEE Comp... | HINS                        | [2419cd659a](https://linux-hardware.org/?probe=2419cd659a) | Jan 24, 2021 |
| HP            | 630                         | [1e3eae8729](https://linux-hardware.org/?probe=1e3eae8729) | Jan 21, 2021 |
| Acer          | Aspire V5-552G              | [8e70dd07f9](https://linux-hardware.org/?probe=8e70dd07f9) | Jan 19, 2021 |
| HP            | ProBook 650 G1              | [57427da656](https://linux-hardware.org/?probe=57427da656) | Jan 02, 2021 |
| Lenovo        | G505s 20255                 | [772dc9d4d7](https://linux-hardware.org/?probe=772dc9d4d7) | Dec 27, 2020 |
| ASUSTek       | X541NA                      | [b17ba4582e](https://linux-hardware.org/?probe=b17ba4582e) | Dec 22, 2020 |
| ASUSTek       | X541NA                      | [1feb258908](https://linux-hardware.org/?probe=1feb258908) | Dec 20, 2020 |
| Gateway       | M290                        | [0b09493054](https://linux-hardware.org/?probe=0b09493054) | Dec 15, 2020 |
| Gateway       | M290                        | [647ec28bce](https://linux-hardware.org/?probe=647ec28bce) | Dec 13, 2020 |
| Acer          | Aspire V5-552G              | [8f8a054e09](https://linux-hardware.org/?probe=8f8a054e09) | Dec 13, 2020 |
| Gateway       | M290                        | [361d599d08](https://linux-hardware.org/?probe=361d599d08) | Dec 11, 2020 |
| ASUSTek       | X556UQ                      | [06423fe399](https://linux-hardware.org/?probe=06423fe399) | Dec 02, 2020 |
| Alienware     | 13 R3                       | [b4b8471219](https://linux-hardware.org/?probe=b4b8471219) | Nov 22, 2020 |
| ASUSTek       | X556UQ                      | [4526906af6](https://linux-hardware.org/?probe=4526906af6) | Nov 06, 2020 |
| ASUSTek       | X556UQ                      | [d55510c234](https://linux-hardware.org/?probe=d55510c234) | Nov 06, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.11.0-25-generic        | 114       | 12.57%  |
| 5.11.0-16-generic        | 114       | 12.57%  |
| 5.11.0-31-generic        | 95        | 10.47%  |
| 5.11.0-22-generic        | 94        | 10.36%  |
| 5.11.0-37-generic        | 92        | 10.14%  |
| 5.11.0-18-generic        | 82        | 9.04%   |
| 5.11.0-17-generic        | 81        | 8.93%   |
| 5.11.0-34-generic        | 67        | 7.39%   |
| 5.11.0-36-generic        | 26        | 2.87%   |
| 5.11.0-38-generic        | 21        | 2.32%   |
| 5.11.0-26-generic        | 12        | 1.32%   |
| 5.11.0-24-generic        | 7         | 0.77%   |
| 5.11.0-20-generic        | 7         | 0.77%   |
| 5.11.0-33-generic        | 6         | 0.66%   |
| 5.11.0-13-generic        | 6         | 0.66%   |
| 5.13.0-051300-generic    | 4         | 0.44%   |
| 5.11.0-35-generic        | 4         | 0.44%   |
| 5.13.1-051301-generic    | 3         | 0.33%   |
| 5.11.0-11-generic        | 3         | 0.33%   |
| 5.10.0-14-generic        | 3         | 0.33%   |
| 5.8.0-50-generic         | 2         | 0.22%   |
| 5.8.0-36-generic         | 2         | 0.22%   |
| 5.8.0-32-generic         | 2         | 0.22%   |
| 5.8.0-25-generic         | 2         | 0.22%   |
| 5.14.9-051409-generic    | 2         | 0.22%   |
| 5.14.0-051400-generic    | 2         | 0.22%   |
| 5.13.9-051309-generic    | 2         | 0.22%   |
| 5.13.12-051312-generic   | 2         | 0.22%   |
| 5.12.12-051212-generic   | 2         | 0.22%   |
| 5.12.0-051200rc3-generic | 2         | 0.22%   |
| 5.12.0-051200-generic    | 2         | 0.22%   |
| 5.11.0-14-generic        | 2         | 0.22%   |
| 5.8.0-63-generic         | 1         | 0.11%   |
| 5.8.0-56-generic         | 1         | 0.11%   |
| 5.8.0-55-generic         | 1         | 0.11%   |
| 5.8.0-44-generic         | 1         | 0.11%   |
| 5.8.0-41-generic         | 1         | 0.11%   |
| 5.8.0-33-generic         | 1         | 0.11%   |
| 5.8.0-31-lowlatency      | 1         | 0.11%   |
| 5.8.0-29-generic         | 1         | 0.11%   |
| 5.8.0-26-lowlatency      | 1         | 0.11%   |
| 5.14.8-051408-generic    | 1         | 0.11%   |
| 5.14.3-051403-generic    | 1         | 0.11%   |
| 5.14.2-051402-generic    | 1         | 0.11%   |
| 5.14.1-051401-generic    | 1         | 0.11%   |
| 5.14.0-051400rc7-generic | 1         | 0.11%   |
| 5.14.0-051400rc6-generic | 1         | 0.11%   |
| 5.14.0-051400rc5-generic | 1         | 0.11%   |
| 5.14.0-051400rc3-generic | 1         | 0.11%   |
| 5.13.7-051307-generic    | 1         | 0.11%   |
| 5.13.4-051304-generic    | 1         | 0.11%   |
| 5.13.0-1017-oem          | 1         | 0.11%   |
| 5.13.0-051300rc7-generic | 1         | 0.11%   |
| 5.13.0-051300rc4-generic | 1         | 0.11%   |
| 5.12.9-051209-generic    | 1         | 0.11%   |
| 5.12.4-051204-generic    | 1         | 0.11%   |
| 5.12.0-051200rc5-generic | 1         | 0.11%   |
| 5.11.6-051106-generic    | 1         | 0.11%   |
| 5.11.12-051112-generic   | 1         | 0.11%   |
| 5.11.0-7620-generic      | 1         | 0.11%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11.0  | 773       | 92.69%  |
| 5.8.0   | 16        | 1.92%   |
| 5.13.0  | 7         | 0.84%   |
| 5.10.0  | 6         | 0.72%   |
| 5.14.0  | 5         | 0.6%    |
| 5.12.0  | 5         | 0.6%    |
| 5.13.1  | 3         | 0.36%   |
| 5.14.9  | 2         | 0.24%   |
| 5.13.9  | 2         | 0.24%   |
| 5.13.12 | 2         | 0.24%   |
| 5.12.12 | 2         | 0.24%   |
| 5.14.8  | 1         | 0.12%   |
| 5.14.3  | 1         | 0.12%   |
| 5.14.2  | 1         | 0.12%   |
| 5.14.1  | 1         | 0.12%   |
| 5.13.7  | 1         | 0.12%   |
| 5.13.4  | 1         | 0.12%   |
| 5.12.9  | 1         | 0.12%   |
| 5.12.4  | 1         | 0.12%   |
| 5.11.6  | 1         | 0.12%   |
| 5.11.12 | 1         | 0.12%   |
| 5.10.69 | 1         | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.11    | 775       | 93.04%  |
| 5.8     | 16        | 1.92%   |
| 5.13    | 15        | 1.8%    |
| 5.14    | 11        | 1.32%   |
| 5.12    | 9         | 1.08%   |
| 5.10    | 7         | 0.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 828       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 742       | 88.44%  |
| Unknown         | 74        | 8.82%   |
| X-Cinnamon      | 8         | 0.95%   |
| Unity           | 5         | 0.6%    |
| Deepin          | 4         | 0.48%   |
| Cinnamon        | 3         | 0.36%   |
| sway            | 1         | 0.12%   |
| i3              | 1         | 0.12%   |
| GNOME Flashback | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 532       | 62.81%  |
| X11     | 271       | 32%     |
| Unknown | 39        | 4.6%    |
| Tty     | 5         | 0.59%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 455       | 53.91%  |
| GDM     | 269       | 31.87%  |
| GDM3    | 103       | 12.2%   |
| LightDM | 8         | 0.95%   |
| TDM     | 6         | 0.71%   |
| SDDM    | 3         | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 366       | 44.1%   |
| de_DE   | 76        | 9.16%   |
| en_GB   | 51        | 6.14%   |
| fr_FR   | 48        | 5.78%   |
| en_IN   | 35        | 4.22%   |
| pt_BR   | 26        | 3.13%   |
| it_IT   | 25        | 3.01%   |
| es_ES   | 20        | 2.41%   |
| ru_RU   | 19        | 2.29%   |
| pl_PL   | 17        | 2.05%   |
| en_CA   | 14        | 1.69%   |
| en_AU   | 14        | 1.69%   |
| cs_CZ   | 13        | 1.57%   |
| nl_NL   | 11        | 1.33%   |
| en_ZA   | 7         | 0.84%   |
| de_AT   | 6         | 0.72%   |
| zh_CN   | 5         | 0.6%    |
| ja_JP   | 5         | 0.6%    |
| Unknown | 5         | 0.6%    |
| sv_SE   | 4         | 0.48%   |
| fr_BE   | 4         | 0.48%   |
| es_MX   | 4         | 0.48%   |
| es_CL   | 4         | 0.48%   |
| C       | 4         | 0.48%   |
| tr_TR   | 3         | 0.36%   |
| ru_UA   | 3         | 0.36%   |
| hu_HU   | 3         | 0.36%   |
| zh_TW   | 2         | 0.24%   |
| ro_RO   | 2         | 0.24%   |
| fr_CA   | 2         | 0.24%   |
| es_UY   | 2         | 0.24%   |
| es_EC   | 2         | 0.24%   |
| es_CO   | 2         | 0.24%   |
| es_AR   | 2         | 0.24%   |
| en_NZ   | 2         | 0.24%   |
| en_IL   | 2         | 0.24%   |
| da_DK   | 2         | 0.24%   |
| vi_VN   | 1         | 0.12%   |
| sr_RS   | 1         | 0.12%   |
| pt_PT   | 1         | 0.12%   |
| nb_NO   | 1         | 0.12%   |
| hr_HR   | 1         | 0.12%   |
| fi_FI   | 1         | 0.12%   |
| et_EE   | 1         | 0.12%   |
| es_PE   | 1         | 0.12%   |
| es_HN   | 1         | 0.12%   |
| es_CU   | 1         | 0.12%   |
| es_CR   | 1         | 0.12%   |
| en_SG   | 1         | 0.12%   |
| en_DK   | 1         | 0.12%   |
| de_IT   | 1         | 0.12%   |
| de_CH   | 1         | 0.12%   |
| ca_ES   | 1         | 0.12%   |
| bg_BG   | 1         | 0.12%   |
| ar_SA   | 1         | 0.12%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 487       | 58.11%  |
| EFI  | 351       | 41.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 765       | 92.39%  |
| Zfs     | 30        | 3.62%   |
| Overlay | 19        | 2.29%   |
| Btrfs   | 9         | 1.09%   |
| Xfs     | 2         | 0.24%   |
| Ext2    | 2         | 0.24%   |
| Unknown | 1         | 0.12%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 542       | 65.3%   |
| GPT     | 275       | 33.13%  |
| MBR     | 13        | 1.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 755       | 90.75%  |
| Yes       | 77        | 9.25%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 548       | 65.94%  |
| Yes       | 283       | 34.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                             | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Lenovo                           | 164       | 19.81%  |
| Hewlett-Packard                  | 154       | 18.6%   |
| Dell                             | 150       | 18.12%  |
| ASUSTek Computer                 | 91        | 10.99%  |
| Acer                             | 72        | 8.7%    |
| Apple                            | 22        | 2.66%   |
| Toshiba                          | 20        | 2.42%   |
| Samsung Electronics              | 17        | 2.05%   |
| HUAWEI                           | 15        | 1.81%   |
| Sony                             | 14        | 1.69%   |
| MSI                              | 11        | 1.33%   |
| Fujitsu                          | 9         | 1.09%   |
| Timi                             | 8         | 0.97%   |
| Notebook                         | 6         | 0.72%   |
| Medion                           | 5         | 0.6%    |
| TUXEDO                           | 4         | 0.48%   |
| System76                         | 4         | 0.48%   |
| Positivo                         | 4         | 0.48%   |
| Alienware                        | 4         | 0.48%   |
| Unknown                          | 4         | 0.48%   |
| Razer                            | 3         | 0.36%   |
| Packard Bell                     | 3         | 0.36%   |
| Google                           | 3         | 0.36%   |
| Schenker                         | 2         | 0.24%   |
| Monster                          | 2         | 0.24%   |
| LG Electronics                   | 2         | 0.24%   |
| Chuwi                            | 2         | 0.24%   |
| Wortmann AG                      | 1         | 0.12%   |
| Wiltronic                        | 1         | 0.12%   |
| VINGA                            | 1         | 0.12%   |
| TrekStor                         | 1         | 0.12%   |
| Thomson                          | 1         | 0.12%   |
| Teclast                          | 1         | 0.12%   |
| Standard                         | 1         | 0.12%   |
| roda computer                    | 1         | 0.12%   |
| Radxa                            | 1         | 0.12%   |
| Positivo Bahia - VAIO            | 1         | 0.12%   |
| Pegatron                         | 1         | 0.12%   |
| Panasonic                        | 1         | 0.12%   |
| Minix                            | 1         | 0.12%   |
| Maibenben                        | 1         | 0.12%   |
| Linx                             | 1         | 0.12%   |
| IP3 Tech                         | 1         | 0.12%   |
| Intel                            | 1         | 0.12%   |
| Insignia                         | 1         | 0.12%   |
| HKC                              | 1         | 0.12%   |
| HCL Infosystems Limited          | 1         | 0.12%   |
| HASEE Computer                   | 1         | 0.12%   |
| Hampoo                           | 1         | 0.12%   |
| Haier                            | 1         | 0.12%   |
| Gigabyte Technology              | 1         | 0.12%   |
| Gateway                          | 1         | 0.12%   |
| FUJITSU CLIENT COMPUTING LIMITED | 1         | 0.12%   |
| Framework                        | 1         | 0.12%   |
| eMachines                        | 1         | 0.12%   |
| Durabook                         | 1         | 0.12%   |
| DNS                              | 1         | 0.12%   |
| CyberPowerPC                     | 1         | 0.12%   |
| BANGHO                           | 1         | 0.12%   |
| Advance                          | 1         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Dell XPS 15 7590                      | 9         | 1.09%   |
| Unknown                               | 9         | 1.09%   |
| HP Notebook                           | 8         | 0.97%   |
| HP EliteBook 820 G1                   | 5         | 0.6%    |
| Dell XPS 13 9310                      | 5         | 0.6%    |
| Dell XPS 15 9510                      | 4         | 0.48%   |
| Lenovo IdeaPad 5 14ARE05 81YM         | 3         | 0.36%   |
| Lenovo G500 20236                     | 3         | 0.36%   |
| HUAWEI HLYL-WXX9                      | 3         | 0.36%   |
| HP ProBook 450 G7                     | 3         | 0.36%   |
| HP Pavilion Notebook                  | 3         | 0.36%   |
| HP EliteBook 845 G7 Notebook PC       | 3         | 0.36%   |
| HP EliteBook 840 G2                   | 3         | 0.36%   |
| Dell XPS 15 9570                      | 3         | 0.36%   |
| Dell XPS 13 9360                      | 3         | 0.36%   |
| Dell G5 5587                          | 3         | 0.36%   |
| Dell G3 3500                          | 3         | 0.36%   |
| ASUS X551CAP                          | 3         | 0.36%   |
| ASUS U50Vg                            | 3         | 0.36%   |
| ASUS ROG Strix G513QY_G513QY          | 3         | 0.36%   |
| Apple MacBookPro9,2                   | 3         | 0.36%   |
| Acer Swift SF314-59                   | 3         | 0.36%   |
| Acer Aspire A515-44                   | 3         | 0.36%   |
| Toshiba PORTEGE Z930                  | 2         | 0.24%   |
| Timi A35S                             | 2         | 0.24%   |
| System76 Serval WS                    | 2         | 0.24%   |
| Samsung 300E4C/300E5C/300E7C          | 2         | 0.24%   |
| Razer Blade                           | 2         | 0.24%   |
| Lenovo ThinkPad P14s Gen 1 20Y1CTO1WW | 2         | 0.24%   |
| Lenovo ThinkBook 16p Gen 2 20YM       | 2         | 0.24%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY  | 2         | 0.24%   |
| Lenovo IdeaPad 520-15IKB 81BF         | 2         | 0.24%   |
| Lenovo IdeaPad 5 15ITL05 82FG         | 2         | 0.24%   |
| Lenovo IdeaPad 5 15ALC05 82LN         | 2         | 0.24%   |
| Lenovo IdeaPad 330S-15ARR 81FB        | 2         | 0.24%   |
| Lenovo IdeaPad 330-15IKB 81DE         | 2         | 0.24%   |
| Lenovo IdeaPad 3 17ADA05 81W2         | 2         | 0.24%   |
| Lenovo IdeaPad 3 15IIL05 81WE         | 2         | 0.24%   |
| Lenovo IdeaPad 3 14ITL6 82H7          | 2         | 0.24%   |
| HUAWEI NBLK-WAX9X                     | 2         | 0.24%   |
| HUAWEI MACHC-WAX9                     | 2         | 0.24%   |
| HUAWEI MACH-WX9                       | 2         | 0.24%   |
| HUAWEI KLVL-WXX9                      | 2         | 0.24%   |
| HUAWEI BOHK-WAX9X                     | 2         | 0.24%   |
| HP ProBook 650 G1                     | 2         | 0.24%   |
| HP ProBook 4540s                      | 2         | 0.24%   |
| HP ProBook 450 G6                     | 2         | 0.24%   |
| HP Pavilion Laptop 15-cs3xxx          | 2         | 0.24%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 2         | 0.24%   |
| HP Pavilion dv7                       | 2         | 0.24%   |
| HP Pavilion dv6                       | 2         | 0.24%   |
| HP Pavilion dv5                       | 2         | 0.24%   |
| HP Pavilion 17                        | 2         | 0.24%   |
| HP Laptop 15s-fq2xxx                  | 2         | 0.24%   |
| HP Laptop 15s-eq1xxx                  | 2         | 0.24%   |
| HP Laptop 15-da0xxx                   | 2         | 0.24%   |
| HP ENVY Laptop 13-ad0xx               | 2         | 0.24%   |
| HP EliteBook Folio 1040 G3            | 2         | 0.24%   |
| HP EliteBook 8570w                    | 2         | 0.24%   |
| HP EliteBook 8530w                    | 2         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 83        | 10.02%  |
| Dell Latitude         | 49        | 5.92%   |
| Lenovo IdeaPad        | 45        | 5.43%   |
| Acer Aspire           | 44        | 5.31%   |
| HP EliteBook          | 38        | 4.59%   |
| Dell Inspiron         | 37        | 4.47%   |
| Dell XPS              | 36        | 4.35%   |
| HP Pavilion           | 27        | 3.26%   |
| HP ProBook            | 23        | 2.78%   |
| HP Laptop             | 20        | 2.42%   |
| ASUS ROG              | 18        | 2.17%   |
| Toshiba Satellite     | 14        | 1.69%   |
| Dell Vostro           | 12        | 1.45%   |
| Acer Swift            | 12        | 1.45%   |
| ASUS VivoBook         | 10        | 1.21%   |
| Unknown               | 9         | 1.09%   |
| HP Notebook           | 8         | 0.97%   |
| HP ENVY               | 7         | 0.85%   |
| Fujitsu LIFEBOOK      | 7         | 0.85%   |
| Dell Precision        | 6         | 0.72%   |
| ASUS ZenBook          | 6         | 0.72%   |
| Lenovo ThinkBook      | 5         | 0.6%    |
| Lenovo Legion         | 5         | 0.6%    |
| HP OMEN               | 4         | 0.48%   |
| Dell G3               | 4         | 0.48%   |
| Apple MacBookPro8     | 4         | 0.48%   |
| Acer Nitro            | 4         | 0.48%   |
| Toshiba PORTEGE       | 3         | 0.36%   |
| Razer Blade           | 3         | 0.36%   |
| Packard Bell EasyNote | 3         | 0.36%   |
| Lenovo G500           | 3         | 0.36%   |
| HUAWEI HLYL-WXX9      | 3         | 0.36%   |
| HP ZBook              | 3         | 0.36%   |
| HP Stream             | 3         | 0.36%   |
| HP 15                 | 3         | 0.36%   |
| Dell G5               | 3         | 0.36%   |
| ASUS X551CAP          | 3         | 0.36%   |
| ASUS U50Vg            | 3         | 0.36%   |
| ASUS ASUS             | 3         | 0.36%   |
| Apple MacBookPro9     | 3         | 0.36%   |
| Acer TravelMate       | 3         | 0.36%   |
| Acer Predator         | 3         | 0.36%   |
| Toshiba TECRA         | 2         | 0.24%   |
| Timi Mi               | 2         | 0.24%   |
| Timi A35S             | 2         | 0.24%   |
| System76 Serval       | 2         | 0.24%   |
| Schenker XMG          | 2         | 0.24%   |
| Samsung 300E4C        | 2         | 0.24%   |
| Lenovo Yoga           | 2         | 0.24%   |
| Lenovo G50-80         | 2         | 0.24%   |
| Lenovo G40-70         | 2         | 0.24%   |
| HUAWEI NBLK-WAX9X     | 2         | 0.24%   |
| HUAWEI MACHC-WAX9     | 2         | 0.24%   |
| HUAWEI MACH-WX9       | 2         | 0.24%   |
| HUAWEI KLVL-WXX9      | 2         | 0.24%   |
| HUAWEI BOHK-WAX9X     | 2         | 0.24%   |
| HP Spectre            | 2         | 0.24%   |
| HP Compaq             | 2         | 0.24%   |
| HP 255                | 2         | 0.24%   |
| Fujitsu STYLISTIC     | 2         | 0.24%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 194       | 23.43%  |
| 2020 | 160       | 19.32%  |
| 2019 | 91        | 10.99%  |
| 2018 | 59        | 7.13%   |
| 2011 | 51        | 6.16%   |
| 2013 | 45        | 5.43%   |
| 2015 | 39        | 4.71%   |
| 2012 | 35        | 4.23%   |
| 2016 | 30        | 3.62%   |
| 2017 | 29        | 3.5%    |
| 2014 | 28        | 3.38%   |
| 2009 | 26        | 3.14%   |
| 2010 | 23        | 2.78%   |
| 2008 | 13        | 1.57%   |
| 2007 | 5         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 828       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 730       | 87.74%  |
| Enabled  | 102       | 12.26%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 824       | 99.52%  |
| Yes  | 4         | 0.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 244       | 29.47%  |
| 3.01-4.0    | 168       | 20.29%  |
| 16.01-24.0  | 162       | 19.57%  |
| 8.01-16.0   | 140       | 16.91%  |
| 32.01-64.0  | 65        | 7.85%   |
| 1.01-2.0    | 30        | 3.62%   |
| 64.01-256.0 | 10        | 1.21%   |
| 24.01-32.0  | 5         | 0.6%    |
| 2.01-3.0    | 3         | 0.36%   |
| 0.51-1.0    | 1         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 316       | 36.28%  |
| 2.01-3.0   | 243       | 27.9%   |
| 4.01-8.0   | 137       | 15.73%  |
| 3.01-4.0   | 123       | 14.12%  |
| 8.01-16.0  | 26        | 2.99%   |
| 0.51-1.0   | 17        | 1.95%   |
| 16.01-24.0 | 5         | 0.57%   |
| 0.01-0.5   | 3         | 0.34%   |
| 24.01-32.0 | 1         | 0.11%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 626       | 75.33%  |
| 2      | 174       | 20.94%  |
| 3      | 19        | 2.29%   |
| 4      | 5         | 0.6%    |
| 0      | 5         | 0.6%    |
| 6      | 1         | 0.12%   |
| 5      | 1         | 0.12%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 562       | 67.87%  |
| Yes       | 266       | 32.13%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 638       | 76.87%  |
| No        | 192       | 23.13%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 806       | 97.23%  |
| No        | 23        | 2.77%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 677       | 81.18%  |
| No        | 157       | 18.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 127       | 15.28%  |
| Germany      | 94        | 11.31%  |
| France       | 51        | 6.14%   |
| UK           | 40        | 4.81%   |
| Italy        | 37        | 4.45%   |
| India        | 37        | 4.45%   |
| Russia       | 36        | 4.33%   |
| Brazil       | 34        | 4.09%   |
| Poland       | 30        | 3.61%   |
| Spain        | 29        | 3.49%   |
| Netherlands  | 20        | 2.41%   |
| Canada       | 20        | 2.41%   |
| Czechia      | 18        | 2.17%   |
| Australia    | 14        | 1.68%   |
| Ukraine      | 13        | 1.56%   |
| Austria      | 13        | 1.56%   |
| Finland      | 11        | 1.32%   |
| Turkey       | 10        | 1.2%    |
| Sweden       | 10        | 1.2%    |
| Romania      | 9         | 1.08%   |
| Mexico       | 9         | 1.08%   |
| South Africa | 8         | 0.96%   |
| Hungary      | 8         | 0.96%   |
| Belgium      | 8         | 0.96%   |
| Switzerland  | 6         | 0.72%   |
| Israel       | 6         | 0.72%   |
| Vietnam      | 5         | 0.6%    |
| Japan        | 5         | 0.6%    |
| Indonesia    | 5         | 0.6%    |
| Greece       | 5         | 0.6%    |
| China        | 5         | 0.6%    |
| Serbia       | 4         | 0.48%   |
| Portugal     | 4         | 0.48%   |
| Peru         | 4         | 0.48%   |
| New Zealand  | 4         | 0.48%   |
| Iran         | 4         | 0.48%   |
| Croatia      | 4         | 0.48%   |
| Colombia     | 4         | 0.48%   |
| Chile        | 4         | 0.48%   |
| Saudi Arabia | 3         | 0.36%   |
| Pakistan     | 3         | 0.36%   |
| Malaysia     | 3         | 0.36%   |
| Luxembourg   | 3         | 0.36%   |
| Latvia       | 3         | 0.36%   |
| Kenya        | 3         | 0.36%   |
| Egypt        | 3         | 0.36%   |
| Denmark      | 3         | 0.36%   |
| Belarus      | 3         | 0.36%   |
| Uruguay      | 2         | 0.24%   |
| Taiwan       | 2         | 0.24%   |
| Sudan        | 2         | 0.24%   |
| Slovakia     | 2         | 0.24%   |
| Morocco      | 2         | 0.24%   |
| Lithuania    | 2         | 0.24%   |
| Ecuador      | 2         | 0.24%   |
| Costa Rica   | 2         | 0.24%   |
| Argentina    | 2         | 0.24%   |
| Zimbabwe     | 1         | 0.12%   |
| Uzbekistan   | 1         | 0.12%   |
| Tunisia      | 1         | 0.12%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Notebooks | Percent |
|---------------|-----------|---------|
| Paris         | 13        | 1.53%   |
| Moscow        | 10        | 1.18%   |
| Warsaw        | 9         | 1.06%   |
| Vienna        | 9         | 1.06%   |
| Prague        | 9         | 1.06%   |
| Milan         | 7         | 0.82%   |
| Kyiv          | 7         | 0.82%   |
| Berlin        | 7         | 0.82%   |
| Helsinki      | 6         | 0.71%   |
| S??o Paulo    | 5         | 0.59%   |
| Cologne       | 5         | 0.59%   |
| Budapest      | 5         | 0.59%   |
| New Delhi     | 4         | 0.47%   |
| Madrid        | 4         | 0.47%   |
| Gdansk        | 4         | 0.47%   |
| Belgrade      | 4         | 0.47%   |
| Barcelona     | 4         | 0.47%   |
| Athens        | 4         | 0.47%   |
| Zagreb        | 3         | 0.35%   |
| Turin         | 3         | 0.35%   |
| Tehran        | 3         | 0.35%   |
| St Petersburg | 3         | 0.35%   |
| Santiago      | 3         | 0.35%   |
| Riga          | 3         | 0.35%   |
| Oklahoma City | 3         | 0.35%   |
| Nuremberg     | 3         | 0.35%   |
| Munich        | 3         | 0.35%   |
| Montreal      | 3         | 0.35%   |
| Melbourne     | 3         | 0.35%   |
| Los Angeles   | 3         | 0.35%   |
| Lima          | 3         | 0.35%   |
| Krakow        | 3         | 0.35%   |
| Kolkata       | 3         | 0.35%   |
| Johannesburg  | 3         | 0.35%   |
| Jakarta       | 3         | 0.35%   |
| Istanbul      | 3         | 0.35%   |
| Fort Wayne    | 3         | 0.35%   |
| Dallas        | 3         | 0.35%   |
| Cairo         | 3         | 0.35%   |
| Bucharest     | 3         | 0.35%   |
| Birmingham    | 3         | 0.35%   |
| Bielefeld     | 3         | 0.35%   |
| Bengaluru     | 3         | 0.35%   |
| Almere Stad   | 3         | 0.35%   |
| Alexandria    | 3         | 0.35%   |
| Valencia      | 2         | 0.24%   |
| Utrecht       | 2         | 0.24%   |
| Troy          | 2         | 0.24%   |
| Tokyo         | 2         | 0.24%   |
| Tel Aviv      | 2         | 0.24%   |
| Sydney        | 2         | 0.24%   |
| Stuttgart     | 2         | 0.24%   |
| Stockholm     | 2         | 0.24%   |
| Schifflange   | 2         | 0.24%   |
| San Francisco | 2         | 0.24%   |
| San Antonio   | 2         | 0.24%   |
| Salem         | 2         | 0.24%   |
| Rostov-on-Don | 2         | 0.24%   |
| Rome          | 2         | 0.24%   |
| Pune          | 2         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 162       | 190    | 16.25%  |
| WDC                       | 132       | 145    | 13.24%  |
| Seagate                   | 107       | 124    | 10.73%  |
| Toshiba                   | 106       | 125    | 10.63%  |
| SK Hynix                  | 53        | 56     | 5.32%   |
| SanDisk                   | 52        | 64     | 5.22%   |
| Unknown                   | 51        | 65     | 5.12%   |
| Intel                     | 42        | 50     | 4.21%   |
| Kingston                  | 38        | 43     | 3.81%   |
| HGST                      | 30        | 36     | 3.01%   |
| Micron Technology         | 27        | 30     | 2.71%   |
| Crucial                   | 27        | 35     | 2.71%   |
| Hitachi                   | 22        | 26     | 2.21%   |
| KIOXIA                    | 19        | 24     | 1.91%   |
| A-DATA Technology         | 10        | 11     | 1%      |
| Apple                     | 9         | 11     | 0.9%    |
| LITEON                    | 8         | 8      | 0.8%    |
| Phison                    | 6         | 6      | 0.6%    |
| Patriot                   | 6         | 7      | 0.6%    |
| Micron/Crucial Technology | 5         | 5      | 0.5%    |
| Union Memory              | 4         | 4      | 0.4%    |
| Team                      | 4         | 4      | 0.4%    |
| SPCC                      | 4         | 5      | 0.4%    |
| LITEONIT                  | 4         | 8      | 0.4%    |
| Hewlett-Packard           | 4         | 4      | 0.4%    |
| Transcend                 | 3         | 4      | 0.3%    |
| KingSpec                  | 3         | 3      | 0.3%    |
| JMicron                   | 3         | 3      | 0.3%    |
| Intenso                   | 3         | 4      | 0.3%    |
| Indilinx                  | 3         | 3      | 0.3%    |
| China                     | 3         | 4      | 0.3%    |
| ASMT                      | 3         | 6      | 0.3%    |
| Solid State Storage       | 2         | 2      | 0.2%    |
| Silicon Motion            | 2         | 2      | 0.2%    |
| PNY                       | 2         | 3      | 0.2%    |
| OSCOO                     | 2         | 2      | 0.2%    |
| OCZ                       | 2         | 2      | 0.2%    |
| Lenovo                    | 2         | 3      | 0.2%    |
| Fujitsu                   | 2         | 2      | 0.2%    |
| BIWIN                     | 2         | 2      | 0.2%    |
| XPG                       | 1         | 1      | 0.1%    |
| VC-500                    | 1         | 1      | 0.1%    |
| VALK                      | 1         | 1      | 0.1%    |
| USB3.1                    | 1         | 1      | 0.1%    |
| Union Memory (Shenzhen)   | 1         | 1      | 0.1%    |
| UMIS                      | 1         | 1      | 0.1%    |
| UDinfo                    | 1         | 1      | 0.1%    |
| TwinMOS                   | 1         | 1      | 0.1%    |
| Teclast                   | 1         | 1      | 0.1%    |
| StoreJet                  | 1         | 1      | 0.1%    |
| SABRENT                   | 1         | 1      | 0.1%    |
| S3+                       | 1         | 1      | 0.1%    |
| PLEXTOR                   | 1         | 1      | 0.1%    |
| PHISON S                  | 1         | 1      | 0.1%    |
| Phison Electronics        | 1         | 2      | 0.1%    |
| PCIe SSD                  | 1         | 2      | 0.1%    |
| Netac                     | 1         | 1      | 0.1%    |
| Mushkin                   | 1         | 2      | 0.1%    |
| Lite-On                   | 1         | 2      | 0.1%    |
| KingFast                  | 1         | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung PM963 2.5" NVMe PCIe SSD 512GB | 24        | 2.32%   |
| Seagate ST1000LM035-1RK172 1TB         | 22        | 2.13%   |
| Toshiba MQ01ABD100 1TB                 | 18        | 1.74%   |
| Unknown MMC Card  32GB                 | 16        | 1.55%   |
| Seagate ST500LT012-1DG142 500GB        | 12        | 1.16%   |
| HGST HTS721010A9E630 1TB               | 12        | 1.16%   |
| Toshiba MQ01ABF050 500GB               | 11        | 1.06%   |
| Intel NVMe SSD Drive 512GB             | 11        | 1.06%   |
| Toshiba MQ04ABF100 1TB                 | 10        | 0.97%   |
| SK Hynix NVMe SSD Drive 512GB          | 9         | 0.87%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 9         | 0.87%   |
| HGST HTS545050A7E680 500GB             | 8         | 0.77%   |
| Unknown MMC Card  64GB                 | 7         | 0.68%   |
| Toshiba NVMe SSD Drive 512GB           | 7         | 0.68%   |
| Sandisk NVMe SSD Drive 512GB           | 7         | 0.68%   |
| Seagate ST9500325AS 500GB              | 6         | 0.58%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 5         | 0.48%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB   | 5         | 0.48%   |
| Unknown MMC Card  128GB                | 5         | 0.48%   |
| Samsung SSD 850 EVO 250GB              | 5         | 0.48%   |
| Samsung NVMe SSD Drive 256GB           | 5         | 0.48%   |
| Samsung NVMe SSD Drive 1TB             | 5         | 0.48%   |
| Samsung HM500JI 500GB                  | 5         | 0.48%   |
| KIOXIA KBG40ZNV512G 512GB              | 5         | 0.48%   |
| Kingston SA400S37240G 240GB SSD        | 5         | 0.48%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB   | 4         | 0.39%   |
| WDC PC SN730 NVMe 1024GB               | 4         | 0.39%   |
| Unknown SD/MMC/MS PRO 128GB            | 4         | 0.39%   |
| SK Hynix NVMe SSD Drive 128GB          | 4         | 0.39%   |
| SK Hynix NVMe SSD Drive 1024GB         | 4         | 0.39%   |
| Seagate ST750LM022 HN-M750MBB 752GB    | 4         | 0.39%   |
| Sandisk NVMe SSD Drive 256GB           | 4         | 0.39%   |
| Kingston SA400S37480G 480GB SSD        | 4         | 0.39%   |
| Kingston SA400S37120G 120GB SSD        | 4         | 0.39%   |
| Intel SSDPEKKW256G7 256GB              | 4         | 0.39%   |
| Hitachi HTS547575A9E384 752GB          | 4         | 0.39%   |
| Hitachi HTS545050B9A300 500GB          | 4         | 0.39%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 3         | 0.29%   |
| WDC WDS100T2B0A-00SM50 1TB SSD         | 3         | 0.29%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 3         | 0.29%   |
| WDC WD5000BPVT-22HXZT3 500GB           | 3         | 0.29%   |
| WDC WD10SPZX-24Z10 1TB                 | 3         | 0.29%   |
| WDC WD10SPZX-21Z10T0 1TB               | 3         | 0.29%   |
| WDC PC SN520 SDAPNUW-512G-1006 512GB   | 3         | 0.29%   |
| WDC PC SN520 SDAPMUW-256G-1101 256GB   | 3         | 0.29%   |
| Unknown MMC Card  16GB                 | 3         | 0.29%   |
| Toshiba KBG40ZNT256G MEMORY 256GB      | 3         | 0.29%   |
| Toshiba HDWJ110 999GB                  | 3         | 0.29%   |
| SK Hynix PC711 NVMe 1TB                | 3         | 0.29%   |
| SK Hynix HFM001TD3JX013N 1TB           | 3         | 0.29%   |
| SK Hynix BC511 NVMe 512GB              | 3         | 0.29%   |
| Seagate ST9320423AS 320GB              | 3         | 0.29%   |
| Seagate ST9320325AS 320GB              | 3         | 0.29%   |
| Seagate ST500LM000-1EJ162 500GB        | 3         | 0.29%   |
| Seagate ST1000LM014-1EJ164 1TB         | 3         | 0.29%   |
| SanDisk SSD PLUS 480GB                 | 3         | 0.29%   |
| SanDisk SSD PLUS 240GB                 | 3         | 0.29%   |
| Samsung SSD 860 EVO M.2 500GB          | 3         | 0.29%   |
| Samsung SSD 860 EVO 500GB              | 3         | 0.29%   |
| Samsung SSD 860 EVO 250GB              | 3         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 103       | 117    | 34.11%  |
| WDC                 | 65        | 73     | 21.52%  |
| Toshiba             | 59        | 67     | 19.54%  |
| HGST                | 30        | 36     | 9.93%   |
| Hitachi             | 22        | 26     | 7.28%   |
| Samsung Electronics | 8         | 12     | 2.65%   |
| Unknown             | 4         | 4      | 1.32%   |
| JMicron             | 2         | 2      | 0.66%   |
| Intenso             | 2         | 3      | 0.66%   |
| Fujitsu             | 2         | 2      | 0.66%   |
| ASMT                | 2         | 5      | 0.66%   |
| Apple               | 2         | 3      | 0.66%   |
| SABRENT             | 1         | 1      | 0.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 69        | 78     | 24.64%  |
| SanDisk             | 34        | 42     | 12.14%  |
| Kingston            | 28        | 32     | 10%     |
| Crucial             | 24        | 32     | 8.57%   |
| WDC                 | 15        | 15     | 5.36%   |
| Intel               | 12        | 15     | 4.29%   |
| Micron Technology   | 10        | 11     | 3.57%   |
| Toshiba             | 8         | 9      | 2.86%   |
| LITEON              | 8         | 8      | 2.86%   |
| SK Hynix            | 7         | 7      | 2.5%    |
| Patriot             | 6         | 7      | 2.14%   |
| Apple               | 5         | 6      | 1.79%   |
| A-DATA Technology   | 5         | 5      | 1.79%   |
| Team                | 4         | 4      | 1.43%   |
| SPCC                | 4         | 5      | 1.43%   |
| LITEONIT            | 4         | 8      | 1.43%   |
| Hewlett-Packard     | 4         | 4      | 1.43%   |
| Transcend           | 3         | 4      | 1.07%   |
| KingSpec            | 3         | 3      | 1.07%   |
| China               | 3         | 4      | 1.07%   |
| PNY                 | 2         | 3      | 0.71%   |
| OSCOO               | 2         | 2      | 0.71%   |
| OCZ                 | 2         | 2      | 0.71%   |
| Indilinx            | 2         | 2      | 0.71%   |
| VALK                | 1         | 1      | 0.36%   |
| Union Memory        | 1         | 1      | 0.36%   |
| TwinMOS             | 1         | 1      | 0.36%   |
| Teclast             | 1         | 1      | 0.36%   |
| StoreJet            | 1         | 1      | 0.36%   |
| Seagate             | 1         | 1      | 0.36%   |
| S3+                 | 1         | 1      | 0.36%   |
| PLEXTOR             | 1         | 1      | 0.36%   |
| Netac               | 1         | 1      | 0.36%   |
| Lenovo              | 1         | 2      | 0.36%   |
| Intenso             | 1         | 1      | 0.36%   |
| EZCOOL              | 1         | 1      | 0.36%   |
| Dogfish             | 1         | 1      | 0.36%   |
| Biostar             | 1         | 2      | 0.36%   |
| ASMT                | 1         | 1      | 0.36%   |
| Apacer              | 1         | 1      | 0.36%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 345       | 409    | 35.9%   |
| HDD     | 292       | 351    | 30.39%  |
| SSD     | 263       | 326    | 27.37%  |
| MMC     | 46        | 60     | 4.79%   |
| Unknown | 15        | 19     | 1.56%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 508       | 650    | 54.62%  |
| NVMe | 344       | 408    | 36.99%  |
| MMC  | 46        | 60     | 4.95%   |
| SAS  | 32        | 47     | 3.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 356       | 445    | 64.85%  |
| 0.51-1.0   | 179       | 215    | 32.6%   |
| 1.01-2.0   | 11        | 12     | 2%      |
| 3.01-4.0   | 2         | 3      | 0.36%   |
| 4.01-10.0  | 1         | 2      | 0.18%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 247       | 29.62%  |
| 101-250        | 246       | 29.5%   |
| 501-1000       | 129       | 15.47%  |
| 51-100         | 69        | 8.27%   |
| 1-20           | 55        | 6.59%   |
| 1001-2000      | 33        | 3.96%   |
| 21-50          | 31        | 3.72%   |
| More than 3000 | 15        | 1.8%    |
| 2001-3000      | 5         | 0.6%    |
| Unknown        | 4         | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 348       | 40.89%  |
| 21-50          | 175       | 20.56%  |
| 51-100         | 126       | 14.81%  |
| 101-250        | 109       | 12.81%  |
| 251-500        | 49        | 5.76%   |
| 501-1000       | 24        | 2.82%   |
| More than 3000 | 7         | 0.82%   |
| 1001-2000      | 7         | 0.82%   |
| Unknown        | 4         | 0.47%   |
| 2001-3000      | 2         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                         | Notebooks | Drives | Percent |
|-----------------------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB               | 2         | 2      | 6.9%    |
| WDC WD5000LPLX-60ZNTT1 500GB                  | 1         | 1      | 3.45%   |
| WDC WD3200LPCX-24C6HT0 320GB                  | 1         | 1      | 3.45%   |
| WDC WD3200BEKT-60PVMT0 320GB                  | 1         | 1      | 3.45%   |
| WDC WD10SPZX-17Z10T0 1TB                      | 1         | 1      | 3.45%   |
| Toshiba MK3263GSXN 320GB                      | 1         | 1      | 3.45%   |
| Toshiba MK3252GSX 320GB                       | 1         | 1      | 3.45%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD         | 1         | 1      | 3.45%   |
| Seagate ST9320423AS 320GB                     | 1         | 1      | 3.45%   |
| Seagate ST500LT012-1DG142 500GB               | 1         | 1      | 3.45%   |
| Seagate ST500LM000-1EJ162 500GB               | 1         | 1      | 3.45%   |
| Seagate ST320LT020-9YG142 320GB               | 1         | 1      | 3.45%   |
| Seagate ST1000LM035-1RK172 1TB                | 1         | 1      | 3.45%   |
| SanDisk SSD U100 128GB                        | 1         | 1      | 3.45%   |
| SanDisk SSD PLUS 480GB                        | 1         | 1      | 3.45%   |
| SanDisk SDSSDHII240G 240GB                    | 1         | 1      | 3.45%   |
| SanDisk SD7SB3Q128G1002 128GB SSD             | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 860 EVO 500GB         | 1         | 1      | 3.45%   |
| Samsung Electronics SSD 850 EVO 250GB         | 1         | 1      | 3.45%   |
| Micron Technology MTFDDAT256MAM-1K2 256GB SSD | 1         | 1      | 3.45%   |
| LITEONIT LMT-32L3M mSATA 32GB SSD             | 1         | 1      | 3.45%   |
| Intel SSDSC2KF256H6L 256GB                    | 1         | 1      | 3.45%   |
| Intel SSDPEKKF256G7L 256GB                    | 1         | 1      | 3.45%   |
| Hitachi HTS542525K9A300 250GB                 | 1         | 1      | 3.45%   |
| HGST HTS725050A7E630 500GB                    | 1         | 1      | 3.45%   |
| Fujitsu MHV2080BH PL 80GB                     | 1         | 1      | 3.45%   |
| Crucial CT1000P1SSD8 1TB                      | 1         | 1      | 3.45%   |
| A-DATA Technology SU800NS38 512GB SSD         | 1         | 1      | 3.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 24.14%  |
| WDC                 | 4         | 4      | 13.79%  |
| SanDisk             | 4         | 4      | 13.79%  |
| Toshiba             | 2         | 2      | 6.9%    |
| Samsung Electronics | 2         | 2      | 6.9%    |
| Intel               | 2         | 2      | 6.9%    |
| SK Hynix            | 1         | 1      | 3.45%   |
| Micron Technology   | 1         | 1      | 3.45%   |
| LITEONIT            | 1         | 1      | 3.45%   |
| Hitachi             | 1         | 1      | 3.45%   |
| HGST                | 1         | 1      | 3.45%   |
| Fujitsu             | 1         | 1      | 3.45%   |
| Crucial             | 1         | 1      | 3.45%   |
| A-DATA Technology   | 1         | 1      | 3.45%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 43.75%  |
| WDC     | 4         | 4      | 25%     |
| Toshiba | 2         | 2      | 12.5%   |
| Hitachi | 1         | 1      | 6.25%   |
| HGST    | 1         | 1      | 6.25%   |
| Fujitsu | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 55.17%  |
| SSD  | 11        | 11     | 37.93%  |
| NVMe | 2         | 2      | 6.9%    |

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
| Detected | 525       | 752    | 60.34%  |
| Works    | 316       | 384    | 36.32%  |
| Malfunc  | 29        | 29     | 3.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 578       | 57.34%  |
| AMD                            | 91        | 9.03%   |
| Samsung Electronics            | 88        | 8.73%   |
| Sandisk                        | 70        | 6.94%   |
| SK Hynix                       | 45        | 4.46%   |
| Toshiba America Info Systems   | 38        | 3.77%   |
| KIOXIA                         | 22        | 2.18%   |
| Micron Technology              | 17        | 1.69%   |
| Kingston Technology Company    | 10        | 0.99%   |
| Phison Electronics             | 8         | 0.79%   |
| Micron/Crucial Technology      | 8         | 0.79%   |
| Nvidia                         | 7         | 0.69%   |
| ADATA Technology               | 6         | 0.6%    |
| Union Memory (Shenzhen)        | 5         | 0.5%    |
| Silicon Motion                 | 4         | 0.4%    |
| Solid State Storage Technology | 2         | 0.2%    |
| Apple                          | 2         | 0.2%    |
| Unknown                        | 1         | 0.1%    |
| Seagate Technology             | 1         | 0.1%    |
| Realtek Semiconductor          | 1         | 0.1%    |
| Marvell Technology Group       | 1         | 0.1%    |
| Lite-On Technology             | 1         | 0.1%    |
| Lenovo                         | 1         | 0.1%    |
| ASMedia Technology             | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 80        | 7.53%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 69        | 6.49%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 58        | 5.46%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 49        | 4.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 42        | 3.95%   |
| Intel Volume Management Device NVMe RAID Controller                              | 38        | 3.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 37        | 3.48%   |
| Samsung NVMe SSD Controller 980                                                  | 33        | 3.1%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 33        | 3.1%    |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                       | 31        | 2.92%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 30        | 2.82%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 23        | 2.16%   |
| KIOXIA Non-Volatile memory controller                                            | 22        | 2.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 21        | 1.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 21        | 1.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 20        | 1.88%   |
| Micron Non-Volatile memory controller                                            | 17        | 1.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 1.6%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 16        | 1.51%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 15        | 1.41%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 15        | 1.41%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 15        | 1.41%   |
| SK Hynix BC511                                                                   | 14        | 1.32%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                  | 14        | 1.32%   |
| Intel SSD 660P Series                                                            | 14        | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                            | 14        | 1.32%   |
| Sandisk WD Blue SN550 NVMe SSD                                                   | 13        | 1.22%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 12        | 1.13%   |
| SK Hynix Gold P31 SSD                                                            | 11        | 1.03%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 11        | 1.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 11        | 1.03%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 0.94%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 9         | 0.85%   |
| SK Hynix Non-Volatile memory controller                                          | 9         | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 9         | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 9         | 0.85%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 9         | 0.85%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 9         | 0.85%   |
| SK Hynix BC501 NVMe Solid State Drive                                            | 8         | 0.75%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 7         | 0.66%   |
| Sandisk PC SN520 NVMe SSD                                                        | 7         | 0.66%   |
| Intel Non-Volatile memory controller                                             | 7         | 0.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 7         | 0.66%   |
| Toshiba America Info Systems XG4 NVMe SSD Controller                             | 6         | 0.56%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 6         | 0.56%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 5         | 0.47%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 5         | 0.47%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]    | 5         | 0.47%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 4         | 0.38%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                  | 4         | 0.38%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 4         | 0.38%   |
| Kingston Company A2000 NVMe SSD                                                  | 4         | 0.38%   |
| Intel SSD 600P Series                                                            | 4         | 0.38%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 4         | 0.38%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 4         | 0.38%   |
| ADATA Non-Volatile memory controller                                             | 4         | 0.38%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 3         | 0.28%   |
| Sandisk Non-Volatile memory controller                                           | 3         | 0.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 3         | 0.28%   |
| Phison E12 NVMe Controller                                                       | 3         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 569       | 54.76%  |
| NVMe | 345       | 33.21%  |
| RAID | 91        | 8.76%   |
| IDE  | 34        | 3.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 680       | 82.13%  |
| AMD    | 148       | 17.87%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 2.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 16        | 1.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 1.93%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 15        | 1.81%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 14        | 1.69%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 1.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 1.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 13        | 1.57%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 1.33%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 11        | 1.33%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 11        | 1.33%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 1.21%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 10        | 1.21%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 10        | 1.21%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 9         | 1.09%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 9         | 1.09%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 9         | 1.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 9         | 1.09%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 8         | 0.97%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 0.97%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.97%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 8         | 0.97%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 0.97%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 8         | 0.97%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 0.97%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 8         | 0.97%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.85%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 0.85%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 7         | 0.85%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 7         | 0.85%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 7         | 0.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.85%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 6         | 0.72%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 6         | 0.72%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 6         | 0.72%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 6         | 0.72%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 6         | 0.72%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 6         | 0.72%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 6         | 0.72%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 5         | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.6%    |
| Intel Core i5-7300U CPU @ 2.60GHz             | 5         | 0.6%    |
| Intel Core i5 CPU M 430 @ 2.27GHz             | 5         | 0.6%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 0.6%    |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 5         | 0.6%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 5         | 0.6%    |
| Intel Celeron CPU 1007U @ 1.50GHz             | 5         | 0.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 5         | 0.6%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 5         | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 4         | 0.48%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 4         | 0.48%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 4         | 0.48%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.48%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.48%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.48%   |
| Intel Core i5-3427U CPU @ 1.80GHz             | 4         | 0.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 4         | 0.48%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 0.48%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 4         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 205       | 24.76%  |
| Intel Core i7                        | 201       | 24.28%  |
| Other                                | 70        | 8.45%   |
| Intel Core i3                        | 65        | 7.85%   |
| Intel Core 2 Duo                     | 41        | 4.95%   |
| Intel Celeron                        | 40        | 4.83%   |
| AMD Ryzen 5                          | 32        | 3.86%   |
| AMD Ryzen 7                          | 31        | 3.74%   |
| Intel Pentium                        | 22        | 2.66%   |
| Intel Atom                           | 18        | 2.17%   |
| AMD Ryzen 7 PRO                      | 12        | 1.45%   |
| AMD Ryzen 9                          | 11        | 1.33%   |
| AMD Ryzen 3                          | 8         | 0.97%   |
| AMD A10                              | 8         | 0.97%   |
| AMD Athlon                           | 6         | 0.72%   |
| AMD A6                               | 6         | 0.72%   |
| AMD A8                               | 5         | 0.6%    |
| Intel Pentium Silver                 | 4         | 0.48%   |
| Intel Pentium Dual-Core              | 4         | 0.48%   |
| Intel Core 2                         | 4         | 0.48%   |
| AMD E2                               | 4         | 0.48%   |
| AMD E1                               | 4         | 0.48%   |
| AMD E                                | 4         | 0.48%   |
| Intel Core i9                        | 3         | 0.36%   |
| Intel Xeon                           | 2         | 0.24%   |
| Intel Pentium Dual                   | 2         | 0.24%   |
| Intel Core m7                        | 2         | 0.24%   |
| AMD Ryzen 5 PRO                      | 2         | 0.24%   |
| AMD A4                               | 2         | 0.24%   |
| Intel Core m3                        | 1         | 0.12%   |
| Intel Core M                         | 1         | 0.12%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 1         | 0.12%   |
| AMD Turion X2 Dual-Core Mobile       | 1         | 0.12%   |
| AMD PRO A10                          | 1         | 0.12%   |
| AMD C-60                             | 1         | 0.12%   |
| AMD Athlon X2                        | 1         | 0.12%   |
| AMD Athlon II Dual-Core              | 1         | 0.12%   |
| AMD Athlon II                        | 1         | 0.12%   |
| AMD A12                              | 1         | 0.12%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 408       | 49.28%  |
| 4      | 281       | 33.94%  |
| 6      | 71        | 8.57%   |
| 8      | 64        | 7.73%   |
| 1      | 3         | 0.36%   |
| 3      | 1         | 0.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 828       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 643       | 77.66%  |
| 1      | 185       | 22.34%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 827       | 99.88%  |
| Unknown        | 1         | 0.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 447       | 52.84%  |
| 0x806c1    | 44        | 5.2%    |
| 0x806ec    | 28        | 3.31%   |
| 0x806ea    | 25        | 2.96%   |
| 0x306a9    | 24        | 2.84%   |
| 0xa0652    | 18        | 2.13%   |
| 0x906ea    | 18        | 2.13%   |
| 0x08600104 | 16        | 1.89%   |
| 0x806e9    | 15        | 1.77%   |
| 0x706e5    | 15        | 1.77%   |
| 0x406e3    | 13        | 1.54%   |
| 0x206a7    | 13        | 1.54%   |
| 0x0a50000c | 13        | 1.54%   |
| 0x08600106 | 13        | 1.54%   |
| 0x906e9    | 11        | 1.3%    |
| 0x806d1    | 10        | 1.18%   |
| 0x306d4    | 10        | 1.18%   |
| 0x08108109 | 9         | 1.06%   |
| 0x40651    | 8         | 0.95%   |
| 0x306c3    | 7         | 0.83%   |
| 0x08600103 | 7         | 0.83%   |
| 0x806eb    | 6         | 0.71%   |
| 0x506e3    | 6         | 0.71%   |
| 0x406c4    | 5         | 0.59%   |
| 0x30678    | 5         | 0.59%   |
| 0x20655    | 5         | 0.59%   |
| 0x1067a    | 5         | 0.59%   |
| 0x08608103 | 5         | 0.59%   |
| 0x20652    | 4         | 0.47%   |
| 0x0a50000b | 4         | 0.47%   |
| 0x706a1    | 3         | 0.35%   |
| 0x08108102 | 3         | 0.35%   |
| 0x06006705 | 3         | 0.35%   |
| 0x906ed    | 2         | 0.24%   |
| 0x6fd      | 2         | 0.24%   |
| 0x406c3    | 2         | 0.24%   |
| 0x106e5    | 2         | 0.24%   |
| 0x08608102 | 2         | 0.24%   |
| 0x08200103 | 2         | 0.24%   |
| 0x0810100b | 2         | 0.24%   |
| 0x07030105 | 2         | 0.24%   |
| 0x05000119 | 2         | 0.24%   |
| 0x706a8    | 1         | 0.12%   |
| 0x506c9    | 1         | 0.12%   |
| 0x30673    | 1         | 0.12%   |
| 0x07030106 | 1         | 0.12%   |
| 0x0700010f | 1         | 0.12%   |
| 0x06006704 | 1         | 0.12%   |
| 0x0600611a | 1         | 0.12%   |
| 0x06006110 | 1         | 0.12%   |
| 0x03000027 | 1         | 0.12%   |
| 0x02000032 | 1         | 0.12%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KabyLake        | 176       | 21.26%  |
| IvyBridge       | 65        | 7.85%   |
| TigerLake       | 54        | 6.52%   |
| SandyBridge     | 54        | 6.52%   |
| Haswell         | 54        | 6.52%   |
| Zen 2           | 45        | 5.43%   |
| Skylake         | 44        | 5.31%   |
| Silvermont      | 40        | 4.83%   |
| Westmere        | 37        | 4.47%   |
| Penryn          | 36        | 4.35%   |
| Icelake         | 33        | 3.99%   |
| CometLake       | 26        | 3.14%   |
| Broadwell       | 26        | 3.14%   |
| Zen 3           | 22        | 2.66%   |
| Zen+            | 20        | 2.42%   |
| Core            | 15        | 1.81%   |
| Excavator       | 12        | 1.45%   |
| Unknown         | 12        | 1.45%   |
| Goldmont plus   | 9         | 1.09%   |
| Puma            | 7         | 0.85%   |
| Bobcat          | 7         | 0.85%   |
| Zen             | 6         | 0.72%   |
| Piledriver      | 5         | 0.6%    |
| Jaguar          | 5         | 0.6%    |
| Nehalem         | 3         | 0.36%   |
| K8 & K10 hybrid | 3         | 0.36%   |
| Goldmont        | 3         | 0.36%   |
| Steamroller     | 2         | 0.24%   |
| K10 Llano       | 2         | 0.24%   |
| K10             | 2         | 0.24%   |
| Bonnell         | 2         | 0.24%   |
| K8 Hammer       | 1         | 0.12%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 612       | 58.45%  |
| Nvidia | 247       | 23.59%  |
| AMD    | 188       | 17.96%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 56        | 5.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 50        | 4.69%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 4.41%   |
| AMD Renoir                                                                               | 43        | 4.03%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 3.19%   |
| Intel UHD Graphics 620                                                                   | 33        | 3.1%    |
| Intel HD Graphics 620                                                                    | 32        | 3%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 29        | 2.72%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 29        | 2.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 2.53%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 26        | 2.44%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 2.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 22        | 2.06%   |
| Intel HD Graphics 5500                                                                   | 22        | 2.06%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 22        | 2.06%   |
| AMD Picasso                                                                              | 22        | 2.06%   |
| AMD Cezanne                                                                              | 20        | 1.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 19        | 1.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 16        | 1.5%    |
| Intel HD Graphics 530                                                                    | 16        | 1.5%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 16        | 1.5%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 15        | 1.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 1.22%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 11        | 1.03%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 11        | 1.03%   |
| Intel HD Graphics 630                                                                    | 11        | 1.03%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 0.94%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 10        | 0.94%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 9         | 0.84%   |
| Nvidia GP108M [GeForce MX150]                                                            | 9         | 0.84%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 9         | 0.84%   |
| AMD Lucienne                                                                             | 9         | 0.84%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 7         | 0.66%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 6         | 0.56%   |
| Nvidia GP108M [GeForce MX250]                                                            | 6         | 0.56%   |
| Intel Tiger Lake UHD Graphics                                                            | 6         | 0.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 6         | 0.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 6         | 0.56%   |
| Intel Iris Plus Graphics G7                                                              | 6         | 0.56%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 0.56%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 6         | 0.56%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.56%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 5         | 0.47%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 0.47%   |
| Nvidia TU117M                                                                            | 4         | 0.38%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 4         | 0.38%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.38%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 4         | 0.38%   |
| Nvidia GP107M [GeForce MX350]                                                            | 4         | 0.38%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 4         | 0.38%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 4         | 0.38%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 4         | 0.38%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 0.38%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 0.38%   |
| AMD Opal PRO [Radeon R7 M260X]                                                           | 4         | 0.38%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.38%   |
| Nvidia GT216M [GeForce GT 320M]                                                          | 3         | 0.28%   |
| Nvidia GP104BM [GeForce GTX 1070 Mobile]                                                 | 3         | 0.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 417       | 50.36%  |
| Intel + Nvidia | 169       | 20.41%  |
| 1 x AMD        | 128       | 15.46%  |
| 1 x Nvidia     | 54        | 6.52%   |
| Intel + AMD    | 26        | 3.14%   |
| AMD + Nvidia   | 24        | 2.9%    |
| 2 x AMD        | 10        | 1.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 705       | 84.53%  |
| Proprietary | 116       | 13.91%  |
| Unknown     | 13        | 1.56%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 633       | 75.99%  |
| 1.01-2.0   | 53        | 6.36%   |
| 0.01-0.5   | 50        | 6%      |
| 3.01-4.0   | 42        | 5.04%   |
| 0.51-1.0   | 22        | 2.64%   |
| 5.01-6.0   | 19        | 2.28%   |
| 7.01-8.0   | 8         | 0.96%   |
| 8.01-16.0  | 4         | 0.48%   |
| 2.01-3.0   | 2         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 195       | 20.21%  |
| LG Display              | 138       | 14.3%   |
| BOE                     | 124       | 12.85%  |
| Chimei Innolux          | 108       | 11.19%  |
| Samsung Electronics     | 91        | 9.43%   |
| Sharp                   | 42        | 4.35%   |
| Dell                    | 28        | 2.9%    |
| Goldstar                | 27        | 2.8%    |
| Apple                   | 22        | 2.28%   |
| Chi Mei Optoelectronics | 20        | 2.07%   |
| Hewlett-Packard         | 18        | 1.87%   |
| PANDA                   | 17        | 1.76%   |
| Lenovo                  | 16        | 1.66%   |
| Acer                    | 13        | 1.35%   |
| Philips                 | 9         | 0.93%   |
| BenQ                    | 8         | 0.83%   |
| InfoVision              | 7         | 0.73%   |
| Iiyama                  | 7         | 0.73%   |
| Unknown                 | 5         | 0.52%   |
| CSO                     | 5         | 0.52%   |
| AOC                     | 5         | 0.52%   |
| TMX                     | 4         | 0.41%   |
| ASUSTek Computer        | 4         | 0.41%   |
| Ancor Communications    | 4         | 0.41%   |
| ViewSonic               | 3         | 0.31%   |
| Sony                    | 3         | 0.31%   |
| LGD                     | 3         | 0.31%   |
| LG Philips              | 3         | 0.31%   |
| JDI                     | 3         | 0.31%   |
| Toshiba                 | 2         | 0.21%   |
| Sceptre Tech            | 2         | 0.21%   |
| KDC                     | 2         | 0.21%   |
| Denver                  | 2         | 0.21%   |
| CPT                     | 2         | 0.21%   |
| CHR                     | 2         | 0.21%   |
| BOE Technology Group    | 2         | 0.21%   |
| Westinghouse            | 1         | 0.1%    |
| Vizio                   | 1         | 0.1%    |
| Unknown (XXX)           | 1         | 0.1%    |
| TIANMA XM               | 1         | 0.1%    |
| SGT                     | 1         | 0.1%    |
| Sanyo                   | 1         | 0.1%    |
| S2-Tek                  | 1         | 0.1%    |
| RTK                     | 1         | 0.1%    |
| Panasonic               | 1         | 0.1%    |
| Nvidia                  | 1         | 0.1%    |
| NEC Computers           | 1         | 0.1%    |
| MiTAC                   | 1         | 0.1%    |
| LG Electronics          | 1         | 0.1%    |
| Insignia                | 1         | 0.1%    |
| Hitachi                 | 1         | 0.1%    |
| HannStar                | 1         | 0.1%    |
| GKK                     | 1         | 0.1%    |
| Fujitsu Siemens         | 1         | 0.1%    |
| Cbox                    | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 10        | 1.02%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 10        | 1.02%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 6         | 0.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 6         | 0.61%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 6         | 0.61%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 340x190mm 15.3-inch            | 6         | 0.61%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch           | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 5         | 0.51%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                  | 4         | 0.41%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 4         | 0.41%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch          | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 4         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 4         | 0.41%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 4         | 0.41%   |
| BOE LCD Monitor BOE07F6 1920x1080 309x174mm 14.0-inch                    | 4         | 0.41%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 340x190mm 15.3-inch            | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 4         | 0.41%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                  | 3         | 0.31%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 3         | 0.31%   |
| Samsung Electronics EPSON PJ SECA603 1920x1080 1600x900mm 72.3-inch      | 3         | 0.31%   |
| Samsung Electronics Color LCD SDCA029 2160x1440 252x168mm 11.9-inch      | 3         | 0.31%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                  | 3         | 0.31%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch             | 3         | 0.31%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch             | 3         | 0.31%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 3         | 0.31%   |
| LG Display LCD Monitor LGD056D 1920x1080 380x210mm 17.1-inch             | 3         | 0.31%   |
| LG Display LCD Monitor LGD046C 1920x1080 380x210mm 17.1-inch             | 3         | 0.31%   |
| LG Display LCD Monitor LGD03EE 1366x768 277x156mm 12.5-inch              | 3         | 0.31%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 3         | 0.31%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.31%   |
| Lenovo LCD Monitor LEN4035 1280x800 304x190mm 14.1-inch                  | 3         | 0.31%   |
| JDI LCD Monitor JDI422A 3000x2000 293x196mm 13.9-inch                    | 3         | 0.31%   |
| InfoVision LCD Monitor IVO061F 1920x1080 344x194mm 15.5-inch             | 3         | 0.31%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch                 | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 340x190mm 15.3-inch          | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN14C0 1920x1080 308x173mm 13.9-inch         | 3         | 0.31%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch          | 3         | 0.31%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 3         | 0.31%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO5B2D 1920x1080 293x162mm 13.2-inch           | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch           | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO35ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO31EC 1366x768 340x190mm 15.3-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO312C 1366x768 293x164mm 13.2-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO30EC 1366x768 344x193mm 15.5-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch            | 3         | 0.31%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch            | 3         | 0.31%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch                   | 3         | 0.31%   |
| Apple Color LCD APP9CC7 1280x800 290x180mm 13.4-inch                     | 3         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 398       | 44.22%  |
| 1366x768 (WXGA)    | 244       | 27.11%  |
| 1600x900 (HD+)     | 51        | 5.67%   |
| 3840x2160 (4K)     | 36        | 4%      |
| 1280x800 (WXGA)    | 32        | 3.56%   |
| 2560x1440 (QHD)    | 23        | 2.56%   |
| 1440x900 (WXGA+)   | 17        | 1.89%   |
| 1920x1200 (WUXGA)  | 15        | 1.67%   |
| 2560x1600          | 9         | 1%      |
| 1280x1024 (SXGA)   | 8         | 0.89%   |
| 3440x1440          | 6         | 0.67%   |
| 3840x2400          | 5         | 0.56%   |
| 2160x1440          | 5         | 0.56%   |
| Unknown            | 5         | 0.56%   |
| 3200x2000          | 4         | 0.44%   |
| 3200x1800 (QHD+)   | 4         | 0.44%   |
| 3000x2000          | 4         | 0.44%   |
| 2560x1080          | 4         | 0.44%   |
| 1680x1050 (WSXGA+) | 4         | 0.44%   |
| 1360x768           | 4         | 0.44%   |
| 3456x2160          | 3         | 0.33%   |
| 2256x1504          | 3         | 0.33%   |
| 1920x540           | 2         | 0.22%   |
| 1920x1280          | 2         | 0.22%   |
| 5760x2160          | 1         | 0.11%   |
| 3840x1200          | 1         | 0.11%   |
| 3840x1080          | 1         | 0.11%   |
| 3520x1080          | 1         | 0.11%   |
| 3280x1050          | 1         | 0.11%   |
| 2880x1800          | 1         | 0.11%   |
| 2304x1440          | 1         | 0.11%   |
| 1680x945           | 1         | 0.11%   |
| 1600x1200          | 1         | 0.11%   |
| 1280x768           | 1         | 0.11%   |
| 1080x2160          | 1         | 0.11%   |
| 1024x600           | 1         | 0.11%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 383       | 39.73%  |
| 13      | 146       | 15.15%  |
| 14      | 117       | 12.14%  |
| 17      | 72        | 7.47%   |
| 23      | 34        | 3.53%   |
| 27      | 33        | 3.42%   |
| 24      | 30        | 3.11%   |
| 12      | 23        | 2.39%   |
| 21      | 22        | 2.28%   |
| 11      | 17        | 1.76%   |
| Unknown | 15        | 1.56%   |
| 19      | 13        | 1.35%   |
| 31      | 9         | 0.93%   |
| 34      | 8         | 0.83%   |
| 16      | 8         | 0.83%   |
| 18      | 7         | 0.73%   |
| 72      | 4         | 0.41%   |
| 40      | 3         | 0.31%   |
| 20      | 3         | 0.31%   |
| 84      | 2         | 0.21%   |
| 48      | 2         | 0.21%   |
| 22      | 2         | 0.21%   |
| 10      | 2         | 0.21%   |
| 54      | 1         | 0.1%    |
| 49      | 1         | 0.1%    |
| 43      | 1         | 0.1%    |
| 42      | 1         | 0.1%    |
| 35      | 1         | 0.1%    |
| 32      | 1         | 0.1%    |
| 29      | 1         | 0.1%    |
| 25      | 1         | 0.1%    |
| 5       | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 554       | 58.01%  |
| 201-300     | 127       | 13.3%   |
| 501-600     | 90        | 9.42%   |
| 351-400     | 88        | 9.21%   |
| 401-500     | 42        | 4.4%    |
| Unknown     | 15        | 1.57%   |
| 601-700     | 13        | 1.36%   |
| 701-800     | 9         | 0.94%   |
| 1501-2000   | 6         | 0.63%   |
| 801-900     | 5         | 0.52%   |
| 1001-1500   | 4         | 0.42%   |
| 901-1000    | 1         | 0.1%    |
| 1-100       | 1         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 696       | 83.35%  |
| 16/10   | 89        | 10.66%  |
| 3/2     | 16        | 1.92%   |
| Unknown | 11        | 1.32%   |
| 21/9    | 10        | 1.2%    |
| 5/4     | 8         | 0.96%   |
| 4/3     | 2         | 0.24%   |
| 32/9    | 1         | 0.12%   |
| 1.96    | 1         | 0.12%   |
| 0.46    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 385       | 40.1%   |
| 81-90          | 199       | 20.73%  |
| 201-250        | 72        | 7.5%    |
| 121-130        | 66        | 6.88%   |
| 71-80          | 64        | 6.67%   |
| 301-350        | 34        | 3.54%   |
| 61-70          | 23        | 2.4%    |
| 151-200        | 21        | 2.19%   |
| 351-500        | 19        | 1.98%   |
| 51-60          | 17        | 1.77%   |
| Unknown        | 15        | 1.56%   |
| More than 1000 | 9         | 0.94%   |
| 141-150        | 9         | 0.94%   |
| 251-300        | 8         | 0.83%   |
| 501-1000       | 6         | 0.63%   |
| 111-120        | 5         | 0.52%   |
| 131-140        | 3         | 0.31%   |
| 41-50          | 2         | 0.21%   |
| 91-100         | 2         | 0.21%   |
| 1-40           | 1         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 377       | 39.98%  |
| 101-120       | 278       | 29.48%  |
| 51-100        | 146       | 15.48%  |
| 161-240       | 71        | 7.53%   |
| More than 240 | 45        | 4.77%   |
| Unknown       | 15        | 1.59%   |
| 1-50          | 11        | 1.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 634       | 75.84%  |
| 2     | 160       | 19.14%  |
| 0     | 26        | 3.11%   |
| 3     | 15        | 1.79%   |
| 4     | 1         | 0.12%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 462       | 36.29%  |
| Realtek Semiconductor             | 410       | 32.21%  |
| Qualcomm Atheros                  | 183       | 14.38%  |
| Broadcom                          | 87        | 6.83%   |
| Marvell Technology Group          | 16        | 1.26%   |
| Broadcom Limited                  | 16        | 1.26%   |
| MEDIATEK                          | 11        | 0.86%   |
| Ralink                            | 9         | 0.71%   |
| TP-Link                           | 8         | 0.63%   |
| Hewlett-Packard                   | 7         | 0.55%   |
| Lenovo                            | 6         | 0.47%   |
| JMicron Technology                | 6         | 0.47%   |
| Dell                              | 6         | 0.47%   |
| Samsung Electronics               | 4         | 0.31%   |
| Ericsson Business Mobile Networks | 4         | 0.31%   |
| DisplayLink                       | 4         | 0.31%   |
| Sierra Wireless                   | 3         | 0.24%   |
| Ralink Technology                 | 3         | 0.24%   |
| Nvidia                            | 3         | 0.24%   |
| NetGear                           | 3         | 0.24%   |
| Xiaomi                            | 2         | 0.16%   |
| U-Blox                            | 2         | 0.16%   |
| Qualcomm                          | 2         | 0.16%   |
| Edimax Technology                 | 2         | 0.16%   |
| ASUSTek Computer                  | 2         | 0.16%   |
| ASIX Electronics                  | 2         | 0.16%   |
| Realtek                           | 1         | 0.08%   |
| Qualcomm Atheros Communications   | 1         | 0.08%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.08%   |
| Motorola PCS                      | 1         | 0.08%   |
| ICS Advent                        | 1         | 0.08%   |
| Huawei Technologies               | 1         | 0.08%   |
| Google                            | 1         | 0.08%   |
| Fibocom                           | 1         | 0.08%   |
| D-Link                            | 1         | 0.08%   |
| Arduino SA                        | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 258       | 16.96%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 70        | 4.6%    |
| Intel Wi-Fi 6 AX200                                               | 57        | 3.75%   |
| Intel Wi-Fi 6 AX201                                               | 43        | 2.83%   |
| Intel Wireless 7265                                               | 32        | 2.1%    |
| Intel Wireless 8265 / 8275                                        | 31        | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 1.97%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 29        | 1.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 29        | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 28        | 1.84%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 28        | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 27        | 1.78%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 24        | 1.58%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 23        | 1.51%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 22        | 1.45%   |
| Intel Wireless 7260                                               | 22        | 1.45%   |
| Intel Wireless 8260                                               | 21        | 1.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 19        | 1.25%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 18        | 1.18%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 1.12%   |
| Intel Wireless 3165                                               | 16        | 1.05%   |
| Broadcom BCM43142 802.11b/g/n                                     | 16        | 1.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 15        | 0.99%   |
| Intel Wireless 3160                                               | 14        | 0.92%   |
| Intel Centrino Advanced-N 6235                                    | 14        | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 14        | 0.92%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 12        | 0.79%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 0.79%   |
| MEDIATEK Network controller                                       | 11        | 0.72%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.72%   |
| Intel Centrino Advanced-N 6200                                    | 11        | 0.72%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 10        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10        | 0.66%   |
| Intel Wireless-AC 9260                                            | 10        | 0.66%   |
| Intel WiFi Link 5100                                              | 10        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 9         | 0.59%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 0.59%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 9         | 0.59%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 0.59%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 8         | 0.53%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 8         | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 0.46%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 7         | 0.46%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)    | 7         | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 0.46%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 0.46%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.46%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 0.46%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 7         | 0.46%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 6         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 6         | 0.39%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 6         | 0.39%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 0.39%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 6         | 0.39%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 5         | 0.33%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 440       | 52.63%  |
| Qualcomm Atheros                | 158       | 18.9%   |
| Realtek Semiconductor           | 109       | 13.04%  |
| Broadcom                        | 71        | 8.49%   |
| Broadcom Limited                | 12        | 1.44%   |
| MEDIATEK                        | 11        | 1.32%   |
| Ralink                          | 9         | 1.08%   |
| TP-Link                         | 4         | 0.48%   |
| Dell                            | 4         | 0.48%   |
| Sierra Wireless                 | 3         | 0.36%   |
| Ralink Technology               | 3         | 0.36%   |
| Qualcomm                        | 2         | 0.24%   |
| NetGear                         | 2         | 0.24%   |
| Edimax Technology               | 2         | 0.24%   |
| Realtek                         | 1         | 0.12%   |
| Qualcomm Atheros Communications | 1         | 0.12%   |
| Hewlett-Packard                 | 1         | 0.12%   |
| Fibocom                         | 1         | 0.12%   |
| D-Link                          | 1         | 0.12%   |
| ASUSTek Computer                | 1         | 0.12%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 57        | 6.78%   |
| Intel Wi-Fi 6 AX201                                            | 43        | 5.11%   |
| Intel Wireless 7265                                            | 32        | 3.8%    |
| Intel Wireless 8265 / 8275                                     | 31        | 3.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 29        | 3.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 29        | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 28        | 3.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 28        | 3.33%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 27        | 3.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 24        | 2.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 22        | 2.62%   |
| Intel Wireless 7260                                            | 22        | 2.62%   |
| Intel Wireless 8260                                            | 21        | 2.5%    |
| Intel Comet Lake PCH CNVi WiFi                                 | 21        | 2.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 19        | 2.26%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 18        | 2.14%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 17        | 2.02%   |
| Intel Wireless 3165                                            | 16        | 1.9%    |
| Broadcom BCM43142 802.11b/g/n                                  | 16        | 1.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 15        | 1.78%   |
| Intel Wireless 3160                                            | 14        | 1.66%   |
| Intel Centrino Advanced-N 6235                                 | 14        | 1.66%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 14        | 1.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 12        | 1.43%   |
| MEDIATEK Network controller                                    | 11        | 1.31%   |
| Intel Centrino Advanced-N 6200                                 | 11        | 1.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 10        | 1.19%   |
| Intel Wireless-AC 9260                                         | 10        | 1.19%   |
| Intel WiFi Link 5100                                           | 10        | 1.19%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 9         | 1.07%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 9         | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 8         | 0.95%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 7         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 7         | 0.83%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 7         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 6         | 0.71%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 6         | 0.71%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 0.71%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 6         | 0.71%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 5         | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 5         | 0.59%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 5         | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 5         | 0.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 5         | 0.59%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 5         | 0.59%   |
| Realtek 802.11ac NIC                                           | 4         | 0.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 4         | 0.48%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 0.48%   |
| Intel Centrino Ultimate-N 6300                                 | 4         | 0.48%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 0.48%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.36%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 3         | 0.36%   |
| Intel Ultimate N WiFi Link 5300                                | 3         | 0.36%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 3         | 0.36%   |
| Broadcom BCM43227 802.11b/g/n                                  | 3         | 0.36%   |
| Sierra Wireless EM7455                                         | 2         | 0.24%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 0.24%   |
| Realtek RTL8187 Wireless Adapter                               | 2         | 0.24%   |
| Realtek Realtek Network controller                             | 2         | 0.24%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 363       | 54.59%  |
| Intel                         | 159       | 23.91%  |
| Qualcomm Atheros              | 46        | 6.92%   |
| Broadcom                      | 35        | 5.26%   |
| Marvell Technology Group      | 16        | 2.41%   |
| Lenovo                        | 6         | 0.9%    |
| JMicron Technology            | 6         | 0.9%    |
| TP-Link                       | 4         | 0.6%    |
| Samsung Electronics           | 4         | 0.6%    |
| Hewlett-Packard               | 4         | 0.6%    |
| DisplayLink                   | 4         | 0.6%    |
| Broadcom Limited              | 4         | 0.6%    |
| Nvidia                        | 3         | 0.45%   |
| Xiaomi                        | 2         | 0.3%    |
| ASIX Electronics              | 2         | 0.3%    |
| OnePlus Technology (Shenzhen) | 1         | 0.15%   |
| NetGear                       | 1         | 0.15%   |
| Motorola PCS                  | 1         | 0.15%   |
| ICS Advent                    | 1         | 0.15%   |
| Huawei Technologies           | 1         | 0.15%   |
| Google                        | 1         | 0.15%   |
| ASUSTek Computer              | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 258       | 38.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 70        | 10.46%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30        | 4.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 4.48%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 1.79%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 1.64%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 10        | 1.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 10        | 1.49%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 9         | 1.35%   |
| Intel Ethernet Connection I217-LM                                 | 9         | 1.35%   |
| Intel Ethernet Connection (4) I219-LM                             | 9         | 1.35%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 8         | 1.2%    |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.05%   |
| Intel Ethernet Connection (4) I219-V                              | 7         | 1.05%   |
| Intel 82567LM Gigabit Network Connection                          | 7         | 1.05%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 7         | 1.05%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.9%    |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 6         | 0.9%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 6         | 0.9%    |
| Intel Ethernet Connection (2) I219-LM                             | 5         | 0.75%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.75%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.75%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 4         | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.6%    |
| Lenovo ThinkPad Lan                                               | 4         | 0.6%    |
| Intel Ethernet Connection (6) I219-LM                             | 4         | 0.6%    |
| Intel Ethernet Connection (13) I219-LM                            | 4         | 0.6%    |
| Intel Ethernet Connection (10) I219-V                             | 4         | 0.6%    |
| HP lt4120 Snapdragon X5 LTE                                       | 4         | 0.6%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 4         | 0.6%    |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 3         | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.45%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 3         | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.45%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.45%   |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.45%   |
| Intel Ethernet Connection (13) I219-V                             | 3         | 0.45%   |
| Intel Ethernet Connection (10) I219-LM                            | 3         | 0.45%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.3%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.3%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.3%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.3%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.3%    |
| Nvidia MCP79 Ethernet                                             | 2         | 0.3%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 2         | 0.3%    |
| Marvell Group 88E8036 PCI-E Fast Ethernet Controller              | 2         | 0.3%    |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.3%    |
| Intel Ethernet Connection I219-V                                  | 2         | 0.3%    |
| Intel Ethernet Connection I217-V                                  | 2         | 0.3%    |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.3%    |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.3%    |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.3%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.3%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 2         | 0.3%    |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.15%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 807       | 55.54%  |
| Ethernet | 635       | 43.7%   |
| Modem    | 11        | 0.76%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 722       | 71.77%  |
| Ethernet | 284       | 28.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 586       | 70.77%  |
| 1     | 225       | 27.17%  |
| 0     | 13        | 1.57%   |
| 3     | 4         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 620       | 74.61%  |
| Yes  | 211       | 25.39%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 365       | 53.83%  |
| Qualcomm Atheros Communications | 66        | 9.73%   |
| Realtek Semiconductor           | 63        | 9.29%   |
| Broadcom                        | 35        | 5.16%   |
| IMC Networks                    | 25        | 3.69%   |
| Apple                           | 21        | 3.1%    |
| Foxconn / Hon Hai               | 20        | 2.95%   |
| Lite-On Technology              | 19        | 2.8%    |
| Dell                            | 11        | 1.62%   |
| Realtek                         | 10        | 1.47%   |
| Cambridge Silicon Radio         | 8         | 1.18%   |
| Toshiba                         | 7         | 1.03%   |
| Ralink                          | 6         | 0.88%   |
| Hewlett-Packard                 | 6         | 0.88%   |
| ASUSTek Computer                | 6         | 0.88%   |
| Alps Electric                   | 4         | 0.59%   |
| Foxconn International           | 2         | 0.29%   |
| Taiyo Yuden                     | 1         | 0.15%   |
| Ralink Technology               | 1         | 0.15%   |
| Chicony Electronics             | 1         | 0.15%   |
| Askey Computer                  | 1         | 0.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                                                               | 87        | 12.83%  |
| Intel Bluetooth wireless interface                                                  | 83        | 12.24%  |
| Intel Bluetooth Device                                                              | 66        | 9.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 55        | 8.11%   |
| Intel AX200 Bluetooth                                                               | 55        | 8.11%   |
| Realtek Bluetooth Radio                                                             | 44        | 6.49%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 28        | 4.13%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 15        | 2.21%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 14        | 2.06%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 13        | 1.92%   |
| Lite-On Bluetooth Device                                                            | 13        | 1.92%   |
| Realtek Bluetooth Radio                                                             | 10        | 1.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 10        | 1.47%   |
| Apple Bluetooth USB Host Controller                                                 | 10        | 1.47%   |
| Apple Bluetooth Host Controller                                                     | 10        | 1.47%   |
| IMC Networks Wireless_Device                                                        | 9         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 9         | 1.33%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 8         | 1.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 8         | 1.18%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 7         | 1.03%   |
| IMC Networks Bluetooth Radio                                                        | 7         | 1.03%   |
| Ralink RT3290 Bluetooth                                                             | 6         | 0.88%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 6         | 0.88%   |
| Intel AX210 Bluetooth                                                               | 5         | 0.74%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.74%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 5         | 0.74%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 0.59%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 0.59%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.59%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.59%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 4         | 0.59%   |
| Realtek RTL8821A Bluetooth                                                          | 3         | 0.44%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.44%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 3         | 0.44%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 3         | 0.44%   |
| Dell Wireless 365 Bluetooth                                                         | 3         | 0.44%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 0.44%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 3         | 0.44%   |
| Toshiba RT Bluetooth Radio                                                          | 2         | 0.29%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.29%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 2         | 0.29%   |
| Lite-On Wireless_Device                                                             | 2         | 0.29%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 2         | 0.29%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 2         | 0.29%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 2         | 0.29%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 2         | 0.29%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 2         | 0.29%   |
| Toshiba BCM43142A0                                                                  | 1         | 0.15%   |
| Toshiba Atheros AR3012 Bluetooth                                                    | 1         | 0.15%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.15%   |
| Taiyo Yuden Bluetooth Device                                                        | 1         | 0.15%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.15%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.15%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.15%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.15%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.15%   |
| IMC Networks Broadcom Bluetooth 2.1                                                 | 1         | 0.15%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.15%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth                                     | 1         | 0.15%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 1         | 0.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 658       | 65.6%   |
| AMD                                             | 167       | 16.65%  |
| Nvidia                                          | 125       | 12.46%  |
| C-Media Electronics                             | 7         | 0.7%    |
| GN Netcom                                       | 5         | 0.5%    |
| Lenovo                                          | 4         | 0.4%    |
| Realtek Semiconductor                           | 3         | 0.3%    |
| Hewlett-Packard                                 | 3         | 0.3%    |
| Focusrite-Novation                              | 3         | 0.3%    |
| Creative Technology                             | 3         | 0.3%    |
| Texas Instruments                               | 2         | 0.2%    |
| SteelSeries ApS                                 | 2         | 0.2%    |
| Sennheiser Communications                       | 2         | 0.2%    |
| Samson Technologies                             | 2         | 0.2%    |
| Logitech                                        | 2         | 0.2%    |
| USB MICROPHONE                                  | 1         | 0.1%    |
| RODE Microphones                                | 1         | 0.1%    |
| Numark                                          | 1         | 0.1%    |
| No brand                                        | 1         | 0.1%    |
| Licensed by Sony Computer Entertainment America | 1         | 0.1%    |
| JMTek                                           | 1         | 0.1%    |
| Elitegroup Computer Systems (ECS)               | 1         | 0.1%    |
| Dell                                            | 1         | 0.1%    |
| Datelink Technology                             | 1         | 0.1%    |
| Corsair                                         | 1         | 0.1%    |
| CMX Systems                                     | 1         | 0.1%    |
| Barco Display Systems                           | 1         | 0.1%    |
| Astro Gaming                                    | 1         | 0.1%    |
| Apple                                           | 1         | 0.1%    |
| Afatech                                         | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 102       | 8.39%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 97        | 7.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 75        | 6.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 62        | 5.1%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 54        | 4.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 44        | 3.62%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 40        | 3.29%   |
| Intel Cannon Lake PCH cAVS                                                                        | 35        | 2.88%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 34        | 2.8%    |
| Intel 8 Series HD Audio Controller                                                                | 34        | 2.8%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 31        | 2.55%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 27        | 2.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 26        | 2.14%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 26        | 2.14%   |
| Intel Broadwell-U Audio Controller                                                                | 26        | 2.14%   |
| Intel Comet Lake PCH cAVS                                                                         | 25        | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 25        | 2.06%   |
| AMD FCH Azalia Controller                                                                         | 24        | 1.97%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 22        | 1.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 1.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 18        | 1.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 1.48%   |
| Intel CM238 HD Audio Controller                                                                   | 17        | 1.4%    |
| AMD Kabini HDMI/DP Audio                                                                          | 17        | 1.4%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 15        | 1.23%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 13        | 1.07%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 12        | 0.99%   |
| Nvidia Audio device                                                                               | 12        | 0.99%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 12        | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 12        | 0.99%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 12        | 0.99%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 11        | 0.9%    |
| Nvidia TU106 High Definition Audio Controller                                                     | 11        | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 11        | 0.9%    |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 10        | 0.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 9         | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.66%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 8         | 0.66%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 6         | 0.49%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 6         | 0.49%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 0.49%   |
| AMD High Definition Audio Controller                                                              | 6         | 0.49%   |
| Nvidia High Definition Audio Controller                                                           | 5         | 0.41%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.41%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 0.41%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 5         | 0.41%   |
| AMD Trinity HDMI Audio Controller                                                                 | 5         | 0.41%   |
| Nvidia MCP89 High Definition Audio                                                                | 4         | 0.33%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 4         | 0.33%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 4         | 0.33%   |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.25%   |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.25%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.25%   |
| Hewlett-Packard USB Audio                                                                         | 3         | 0.25%   |
| C-Media Electronics CM108 Audio Controller                                                        | 3         | 0.25%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.25%   |
| AMD Navi 21 HDMI Audio [Radeon RX 6800/6800 XT / 6900 XT]                                         | 3         | 0.25%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.25%   |
| SteelSeries ApS SteelSeries Arctis 1 Wireless                                                     | 2         | 0.16%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 164       | 31.84%  |
| SK Hynix            | 117       | 22.72%  |
| Micron Technology   | 82        | 15.92%  |
| Kingston            | 47        | 9.13%   |
| Unknown             | 26        | 5.05%   |
| Crucial             | 19        | 3.69%   |
| Ramaxel Technology  | 9         | 1.75%   |
| A-DATA Technology   | 8         | 1.55%   |
| Elpida              | 7         | 1.36%   |
| Nanya Technology    | 5         | 0.97%   |
| Corsair             | 5         | 0.97%   |
| Team                | 4         | 0.78%   |
| Smart               | 4         | 0.78%   |
| G.Skill             | 4         | 0.78%   |
| Unknown (ABCD)      | 3         | 0.58%   |
| Unknown (09D5)      | 2         | 0.39%   |
| Transcend           | 2         | 0.39%   |
| Unknown (08AE)      | 1         | 0.19%   |
| Spectek             | 1         | 0.19%   |
| Smart Modular       | 1         | 0.19%   |
| SHARETRONIC         | 1         | 0.19%   |
| High Bridge         | 1         | 0.19%   |
| GOODRAM             | 1         | 0.19%   |
| Avant               | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 10        | 1.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 10        | 1.85%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 10        | 1.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 8         | 1.48%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 7         | 1.29%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB Row Of Chips DDR4 3200MT/s      | 7         | 1.29%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 7         | 1.29%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 6         | 1.11%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 1.11%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 2667MT/s               | 6         | 1.11%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 6         | 1.11%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 6         | 1.11%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 5         | 0.92%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 5         | 0.92%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s              | 5         | 0.92%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 5         | 0.92%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 5         | 0.92%   |
| Unknown RAM Module 2GB Row Of Chips LPDDR4 4267MT/s                 | 4         | 0.74%   |
| SK Hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 4         | 0.74%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 4         | 0.74%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 4         | 0.74%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 4         | 0.74%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 4         | 0.74%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s           | 4         | 0.74%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 4         | 0.74%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s               | 4         | 0.74%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 4         | 0.74%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s         | 4         | 0.74%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB Row Of Chips DDR4 3200MT/s       | 4         | 0.74%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM DDR3 2400MT/s   | 3         | 0.55%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 3         | 0.55%   |
| SK Hynix RAM HMAA2GS6AJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 3         | 0.55%   |
| SK Hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 3         | 0.55%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s             | 3         | 0.55%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s             | 3         | 0.55%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 0.55%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.55%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                         | 3         | 0.55%   |
| Samsung RAM Module 8GB Row Of Chips LPDDR3 2133MT/s                 | 3         | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 3         | 0.55%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 3         | 0.55%   |
| Samsung RAM M471A5244BB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 3         | 0.55%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 3         | 0.55%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.55%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 3         | 0.55%   |
| Samsung RAM M471A1G44AB0-CTD 8GB Row Of Chips DDR4 2667MT/s         | 3         | 0.55%   |
| Micron RAM 8ATF2G64HZ-3G2E2 16GB SODIMM DDR4 3200MT/s               | 3         | 0.55%   |
| Micron RAM 8ATF2G64HZ-3G2E1 16GB SODIMM DDR4 3200MT/s               | 3         | 0.55%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 3         | 0.55%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                         | 2         | 0.37%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s                 | 2         | 0.37%   |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1333MT/s               | 2         | 0.37%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 2         | 0.37%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 2         | 0.37%   |
| SK Hynix RAM Module 4GB DIMM DDR3 1600MT/s                          | 2         | 0.37%   |
| SK Hynix RAM Module 2GB SODIMM DDR3 1600MT/s                        | 2         | 0.37%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2667MT/s                       | 2         | 0.37%   |
| SK Hynix RAM Module 16GB SODIMM DDR4 2133MT/s                       | 2         | 0.37%   |
| SK Hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s               | 2         | 0.37%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s           | 2         | 0.37%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 269       | 60.59%  |
| DDR3   | 112       | 25.23%  |
| LPDDR3 | 28        | 6.31%   |
| LPDDR4 | 26        | 5.86%   |
| DDR2   | 7         | 1.58%   |
| SDRAM  | 2         | 0.45%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 372       | 81.58%  |
| Row Of Chips | 78        | 17.11%  |
| DIMM         | 3         | 0.66%   |
| Chip         | 2         | 0.44%   |
| Unknown      | 1         | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 187       | 39.7%   |
| 4096  | 141       | 29.94%  |
| 16384 | 81        | 17.2%   |
| 2048  | 42        | 8.92%   |
| 32768 | 14        | 2.97%   |
| 1024  | 6         | 1.27%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 126       | 26.47%  |
| 2667    | 123       | 25.84%  |
| 1600    | 84        | 17.65%  |
| 2133    | 29        | 6.09%   |
| 2400    | 28        | 5.88%   |
| 4267    | 19        | 3.99%   |
| 1334    | 19        | 3.99%   |
| 1333    | 12        | 2.52%   |
| 1867    | 11        | 2.31%   |
| 3266    | 6         | 1.26%   |
| 800     | 5         | 1.05%   |
| Unknown | 3         | 0.63%   |
| 975     | 2         | 0.42%   |
| 4266    | 1         | 0.21%   |
| 4199    | 1         | 0.21%   |
| 3733    | 1         | 0.21%   |
| 2048    | 1         | 0.21%   |
| 1777    | 1         | 0.21%   |
| 1067    | 1         | 0.21%   |
| 1066    | 1         | 0.21%   |
| 667     | 1         | 0.21%   |
| 533     | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Seiko Epson           | 2         | 33.33%  |
| Hewlett-Packard       | 2         | 33.33%  |
| Lexmark International | 1         | 16.67%  |
| Canon                 | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Seiko Epson XP-4100 Series                 | 1         | 16.67%  |
| Seiko Epson L395 Series                    | 1         | 16.67%  |
| Lexmark International InkJet Color Printer | 1         | 16.67%  |
| HP LaserJet M101-M106                      | 1         | 16.67%  |
| HP LaserJet 400 M401n                      | 1         | 16.67%  |
| Canon PIXMA TS6250                         | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Ultima Electronics | 1         | 33.33%  |
| Seiko Epson        | 1         | 33.33%  |
| Canon              | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Ultima Artec Ultima 2000              | 1         | 33.33%  |
| Seiko Epson GT-X770 [Perfection V500] | 1         | 33.33%  |
| Canon CanoScan LiDE 600F              | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 199       | 26.36%  |
| IMC Networks                           | 79        | 10.46%  |
| Microdia                               | 73        | 9.67%   |
| Realtek Semiconductor                  | 72        | 9.54%   |
| Acer                                   | 47        | 6.23%   |
| Quanta                                 | 39        | 5.17%   |
| Cheng Uei Precision Industry (Foxlink) | 39        | 5.17%   |
| Sunplus Innovation Technology          | 38        | 5.03%   |
| Suyin                                  | 25        | 3.31%   |
| Apple                                  | 22        | 2.91%   |
| Lite-On Technology                     | 21        | 2.78%   |
| Silicon Motion                         | 16        | 2.12%   |
| Syntek                                 | 14        | 1.85%   |
| Luxvisions Innotech Limited            | 8         | 1.06%   |
| Logitech                               | 8         | 1.06%   |
| Samsung Electronics                    | 7         | 0.93%   |
| Ricoh                                  | 7         | 0.93%   |
| Alcor Micro                            | 7         | 0.93%   |
| Lenovo                                 | 4         | 0.53%   |
| OmniVision Technologies                | 3         | 0.4%    |
| Importek                               | 3         | 0.4%    |
| Unknown                                | 2         | 0.26%   |
| Intel                                  | 2         | 0.26%   |
| 8SSC20F27114V1SR0C71XEG                | 2         | 0.26%   |
| Trust                                  | 1         | 0.13%   |
| SunplusIT                              | 1         | 0.13%   |
| Sunplus Technology                     | 1         | 0.13%   |
| Sonix Technology                       | 1         | 0.13%   |
| Primax Electronics                     | 1         | 0.13%   |
| Pixart Imaging                         | 1         | 0.13%   |
| OPPO Electronics                       | 1         | 0.13%   |
| Microsoft                              | 1         | 0.13%   |
| LG Electronics                         | 1         | 0.13%   |
| kingcome                               | 1         | 0.13%   |
| Huawei Technologies                    | 1         | 0.13%   |
| Guillemot                              | 1         | 0.13%   |
| Genesys Logic                          | 1         | 0.13%   |
| Generalplus Technology                 | 1         | 0.13%   |
| DJKANA1RSF34LM                         | 1         | 0.13%   |
| Creative Technology                    | 1         | 0.13%   |
| ARC International                      | 1         | 0.13%   |
| ALi                                    | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                | 48        | 6.36%   |
| Chicony Integrated Camera                                    | 43        | 5.7%    |
| Realtek Integrated_Webcam_HD                                 | 36        | 4.77%   |
| IMC Networks Integrated Camera                               | 30        | 3.97%   |
| Chicony HD WebCam                                            | 23        | 3.05%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 19        | 2.52%   |
| Acer Integrated Camera                                       | 14        | 1.85%   |
| Quanta HD User Facing                                        | 12        | 1.59%   |
| Sunplus Integrated_Webcam_HD                                 | 11        | 1.46%   |
| Syntek Integrated Camera                                     | 9         | 1.19%   |
| Chicony USB2.0 Camera                                        | 9         | 1.19%   |
| Chicony TOSHIBA Web Camera - HD                              | 9         | 1.19%   |
| Chicony HP HD Camera                                         | 9         | 1.19%   |
| Realtek USB Camera                                           | 8         | 1.06%   |
| Samsung Galaxy A5 (MTP)                                      | 7         | 0.93%   |
| Quanta HP TrueVision HD Camera                               | 7         | 0.93%   |
| Lite-On HP HD Camera                                         | 7         | 0.93%   |
| IMC Networks USB2.0 VGA UVC WebCam                           | 7         | 0.93%   |
| Chicony USB 2.0 Camera                                       | 7         | 0.93%   |
| Chicony Integrated HP HD Webcam                              | 7         | 0.93%   |
| Chicony HP TrueVision HD                                     | 7         | 0.93%   |
| Apple FaceTime HD Camera                                     | 7         | 0.93%   |
| Apple Built-in iSight                                        | 7         | 0.93%   |
| Acer BisonCam, NB Pro                                        | 7         | 0.93%   |
| Chicony USB2.0 HD UVC WebCam                                 | 6         | 0.79%   |
| Chicony Lenovo EasyCamera                                    | 6         | 0.79%   |
| Chicony HP Wide Vision HD Camera                             | 6         | 0.79%   |
| Chicony FJ Camera                                            | 6         | 0.79%   |
| Acer Lenovo EasyCamera                                       | 6         | 0.79%   |
| Sunplus HD WebCam                                            | 5         | 0.66%   |
| Realtek Lenovo EasyCamera                                    | 5         | 0.66%   |
| Realtek Integrated Webcam                                    | 5         | 0.66%   |
| Quanta HP Wide Vision HD Camera                              | 5         | 0.66%   |
| Lite-On HP HD Webcam                                         | 5         | 0.66%   |
| IMC Networks ov9734_azurewave_camera                         | 5         | 0.66%   |
| IMC Networks Integrated Webcam                               | 5         | 0.66%   |
| Chicony HD User Facing                                       | 5         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam          | 5         | 0.66%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera             | 5         | 0.66%   |
| Apple iPhone 5/5C/5S/6/SE                                    | 5         | 0.66%   |
| Suyin 1.3M HD WebCam                                         | 4         | 0.53%   |
| Realtek USB2.0 HD UVC WebCam                                 | 4         | 0.53%   |
| Quanta HP HD Camera                                          | 4         | 0.53%   |
| Quanta HD Webcam                                             | 4         | 0.53%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 4         | 0.53%   |
| Microdia Integrated Webcam                                   | 4         | 0.53%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 4         | 0.53%   |
| Lite-On Integrated Camera                                    | 4         | 0.53%   |
| Chicony HP Webcam                                            | 4         | 0.53%   |
| Chicony HP Truevision HD camera                              | 4         | 0.53%   |
| Chicony EasyCamera                                           | 4         | 0.53%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 4         | 0.53%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                | 4         | 0.53%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera          | 4         | 0.53%   |
| Alcor Micro USB 2.0 Camera                                   | 4         | 0.53%   |
| Acer SunplusIT Integrated Camera                             | 4         | 0.53%   |
| Suyin HP Truevision HD                                       | 3         | 0.4%    |
| Sunplus Asus Webcam                                          | 3         | 0.4%    |
| Realtek HP Webcam                                            | 3         | 0.4%    |
| Luxvisions Innotech Limited HP HD Camera                     | 3         | 0.4%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 58        | 32.22%  |
| Synaptics                  | 47        | 26.11%  |
| Shenzhen Goodix Technology | 40        | 22.22%  |
| LighTuning Technology      | 11        | 6.11%   |
| Elan Microelectronics      | 9         | 5%      |
| Upek                       | 6         | 3.33%   |
| AuthenTec                  | 6         | 3.33%   |
| STMicroelectronics         | 2         | 1.11%   |
| HOLTEK                     | 1         | 0.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 24        | 13.33%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 11.67%  |
| Shenzhen Goodix  FingerPrint Device                                        | 19        | 10.56%  |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 7.22%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 5%      |
| Elan ELAN:Fingerprint                                                      | 9         | 5%      |
| Shenzhen Goodix FingerPrint                                                | 8         | 4.44%   |
| Validity Sensors VFS491                                                    | 6         | 3.33%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 3.33%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 2.78%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 2.78%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 2.78%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 2.78%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 2.78%   |
| Unknown                                                                    | 5         | 2.78%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.22%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.67%   |
| Synaptics  WBDI                                                            | 3         | 1.67%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.11%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.11%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 1.11%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 1.11%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.11%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 1.11%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.11%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.11%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.56%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.56%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.56%   |
| Synaptics WBDI Device                                                      | 1         | 0.56%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.56%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 0.56%   |
| AuthenTec AES2810                                                          | 1         | 0.56%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 32        | 47.06%  |
| Alcor Micro           | 24        | 35.29%  |
| O2 Micro              | 4         | 5.88%   |
| Lenovo                | 3         | 4.41%   |
| Gemalto (was Gemplus) | 2         | 2.94%   |
| Upek                  | 1         | 1.47%   |
| Clay Logic            | 1         | 1.47%   |
| Cherry                | 1         | 1.47%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 35.29%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 14.71%  |
| Broadcom 5880                                                                | 10        | 14.71%  |
| Broadcom 58200                                                               | 9         | 13.24%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 4.41%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 4.41%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 4.41%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 1.47%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.47%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 1.47%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 1.47%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.47%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 1.47%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 502       | 60.12%  |
| 1     | 267       | 31.98%  |
| 2     | 56        | 6.71%   |
| 3     | 9         | 1.08%   |
| 4     | 1         | 0.12%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 176       | 44.22%  |
| Graphics card            | 74        | 18.59%  |
| Chipcard                 | 60        | 15.08%  |
| Net/wireless             | 48        | 12.06%  |
| Storage                  | 8         | 2.01%   |
| Multimedia controller    | 8         | 2.01%   |
| Bluetooth                | 8         | 2.01%   |
| Card reader              | 5         | 1.26%   |
| Camera                   | 4         | 1.01%   |
| Sound                    | 2         | 0.5%    |
| Net/ethernet             | 2         | 0.5%    |
| Unassigned class         | 1         | 0.25%   |
| Modem                    | 1         | 0.25%   |
| Communication controller | 1         | 0.25%   |

