Debian 11 - Tested Hardware & Statistics (Notebooks)
----------------------------------------------------

A project to collect tested hardware configurations for Debian 11.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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
| Dell          | Latitude 7480               | [edecedab9c](https://linux-hardware.org/?probe=edecedab9c) | Sep 30, 2021 |
| Acer          | Aspire A315-23G             | [b8b2183bc1](https://linux-hardware.org/?probe=b8b2183bc1) | Sep 30, 2021 |
| Intel Clie... | LAPBC710                    | [f2535939a1](https://linux-hardware.org/?probe=f2535939a1) | Sep 29, 2021 |
| Timi          | TM1613                      | [f6bb688e77](https://linux-hardware.org/?probe=f6bb688e77) | Sep 29, 2021 |
| Dell          | Precision 3561              | [59bbb944c2](https://linux-hardware.org/?probe=59bbb944c2) | Sep 29, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [885bbac853](https://linux-hardware.org/?probe=885bbac853) | Sep 29, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b8e7519557](https://linux-hardware.org/?probe=b8e7519557) | Sep 29, 2021 |
| Lenovo        | ThinkPad T480 20L5CTO1WW    | [d277db28c5](https://linux-hardware.org/?probe=d277db28c5) | Sep 29, 2021 |
| Acer          | Aspire A315-23G             | [f7a5bd6c04](https://linux-hardware.org/?probe=f7a5bd6c04) | Sep 29, 2021 |
| Dell          | Latitude D630               | [5e7edac95e](https://linux-hardware.org/?probe=5e7edac95e) | Sep 29, 2021 |
| Apple         | MacBookPro14,1              | [01ccd7b321](https://linux-hardware.org/?probe=01ccd7b321) | Sep 28, 2021 |
| Google        | Enguarde                    | [36df7d61be](https://linux-hardware.org/?probe=36df7d61be) | Sep 28, 2021 |
| Google        | Enguarde                    | [4514b06137](https://linux-hardware.org/?probe=4514b06137) | Sep 28, 2021 |
| Google        | Enguarde                    | [ac6c9be38a](https://linux-hardware.org/?probe=ac6c9be38a) | Sep 28, 2021 |
| Google        | Enguarde                    | [36532b595e](https://linux-hardware.org/?probe=36532b595e) | Sep 28, 2021 |
| HP            | Pavilion g6                 | [a349ae4420](https://linux-hardware.org/?probe=a349ae4420) | Sep 28, 2021 |
| Google        | Enguarde                    | [b4273a32be](https://linux-hardware.org/?probe=b4273a32be) | Sep 28, 2021 |
| Google        | Enguarde                    | [0b6cac4bce](https://linux-hardware.org/?probe=0b6cac4bce) | Sep 28, 2021 |
| Google        | Enguarde                    | [3ebd210998](https://linux-hardware.org/?probe=3ebd210998) | Sep 28, 2021 |
| Google        | Enguarde                    | [8ad08b2012](https://linux-hardware.org/?probe=8ad08b2012) | Sep 28, 2021 |
| Apple         | MacBookAir7,1               | [b8706044ce](https://linux-hardware.org/?probe=b8706044ce) | Sep 28, 2021 |
| ASUSTek       | N550JV                      | [5369aca258](https://linux-hardware.org/?probe=5369aca258) | Sep 28, 2021 |
| ASUSTek       | X556UAK                     | [6cd310a2c4](https://linux-hardware.org/?probe=6cd310a2c4) | Sep 27, 2021 |
| Lenovo        | ThinkPad T430 2349N7G       | [d82d96a0ce](https://linux-hardware.org/?probe=d82d96a0ce) | Sep 27, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [61fb50bdf0](https://linux-hardware.org/?probe=61fb50bdf0) | Sep 27, 2021 |
| Lenovo        | G50-45 80E3                 | [a01dd88bfb](https://linux-hardware.org/?probe=a01dd88bfb) | Sep 27, 2021 |
| Lenovo        | IdeaPad U510 4941           | [f0f189cfc9](https://linux-hardware.org/?probe=f0f189cfc9) | Sep 27, 2021 |
| HP            | G61                         | [348bab0a1b](https://linux-hardware.org/?probe=348bab0a1b) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | [721c266b6b](https://linux-hardware.org/?probe=721c266b6b) | Sep 27, 2021 |
| ASUSTek       | X550CA                      | [00d9651c96](https://linux-hardware.org/?probe=00d9651c96) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | [f290c9b80f](https://linux-hardware.org/?probe=f290c9b80f) | Sep 27, 2021 |
| Dell          | Inspiron 3421               | [82bd2ec7eb](https://linux-hardware.org/?probe=82bd2ec7eb) | Sep 27, 2021 |
| MSI           | Bravo 15 A4DDR              | [5236361305](https://linux-hardware.org/?probe=5236361305) | Sep 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8f8f724934](https://linux-hardware.org/?probe=8f8f724934) | Sep 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3b68a00361](https://linux-hardware.org/?probe=3b68a00361) | Sep 26, 2021 |
| Packard Be... | EasyNote TS11HR             | [abf2c60d3f](https://linux-hardware.org/?probe=abf2c60d3f) | Sep 26, 2021 |
| Acer          | Aspire F5-573G              | [97a2a90138](https://linux-hardware.org/?probe=97a2a90138) | Sep 26, 2021 |
| Toshiba       | Satellite C655D             | [7742f4cfe0](https://linux-hardware.org/?probe=7742f4cfe0) | Sep 26, 2021 |
| Lenovo        | IdeaPad 3 15IML05 81WR      | [1f56f02f1d](https://linux-hardware.org/?probe=1f56f02f1d) | Sep 26, 2021 |
| Acer          | TravelMate 2490             | [b09a0d7779](https://linux-hardware.org/?probe=b09a0d7779) | Sep 25, 2021 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [0c67accead](https://linux-hardware.org/?probe=0c67accead) | Sep 25, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [3b61d0a304](https://linux-hardware.org/?probe=3b61d0a304) | Sep 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [2762c5237d](https://linux-hardware.org/?probe=2762c5237d) | Sep 25, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [7a1202630f](https://linux-hardware.org/?probe=7a1202630f) | Sep 25, 2021 |
| Apple         | MacBookPro12,1              | [4d798633db](https://linux-hardware.org/?probe=4d798633db) | Sep 25, 2021 |
| HP            | Pavilion dv6                | [a97e17fc48](https://linux-hardware.org/?probe=a97e17fc48) | Sep 25, 2021 |
| Dell          | G3 3590                     | [519cea3f38](https://linux-hardware.org/?probe=519cea3f38) | Sep 25, 2021 |
| Dell          | G3 3590                     | [bb25c895cf](https://linux-hardware.org/?probe=bb25c895cf) | Sep 25, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [11ebd06d5f](https://linux-hardware.org/?probe=11ebd06d5f) | Sep 25, 2021 |
| HP            | ProBook 4530s               | [0fc1845cd7](https://linux-hardware.org/?probe=0fc1845cd7) | Sep 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e9d692e16d](https://linux-hardware.org/?probe=e9d692e16d) | Sep 24, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [c654d6756a](https://linux-hardware.org/?probe=c654d6756a) | Sep 24, 2021 |
| Dell          | Inspiron 5515               | [64af4c4882](https://linux-hardware.org/?probe=64af4c4882) | Sep 24, 2021 |
| Lenovo        | ThinkPad E14 20RA0036MX     | [b2183edddf](https://linux-hardware.org/?probe=b2183edddf) | Sep 24, 2021 |
| Dell          | Precision M4800             | [1d4a25cfec](https://linux-hardware.org/?probe=1d4a25cfec) | Sep 24, 2021 |
| Toshiba       | PORTEGE R830                | [fbe6b1147d](https://linux-hardware.org/?probe=fbe6b1147d) | Sep 24, 2021 |
| Acer          | TravelMate P273             | [125707a56f](https://linux-hardware.org/?probe=125707a56f) | Sep 24, 2021 |
| MSI           | GE70 2QE                    | [b1cbbbd78f](https://linux-hardware.org/?probe=b1cbbbd78f) | Sep 23, 2021 |
| ASUSTek       | 1015BXO                     | [0f2bd07e92](https://linux-hardware.org/?probe=0f2bd07e92) | Sep 23, 2021 |
| Dell          | Inspiron 5593               | [5ddd391946](https://linux-hardware.org/?probe=5ddd391946) | Sep 23, 2021 |
| HP            | 15                          | [0aec7fa603](https://linux-hardware.org/?probe=0aec7fa603) | Sep 22, 2021 |
| Apple         | MacBookAir7,1               | [e36127ceb6](https://linux-hardware.org/?probe=e36127ceb6) | Sep 22, 2021 |
| HP            | Pavilion dv6                | [72f179ec58](https://linux-hardware.org/?probe=72f179ec58) | Sep 22, 2021 |
| Lenovo        | Mixx-700-12ISK 80QL         | [090e25b77c](https://linux-hardware.org/?probe=090e25b77c) | Sep 22, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [1e8858844a](https://linux-hardware.org/?probe=1e8858844a) | Sep 22, 2021 |
| Dell          | Latitude E7240              | [7048aa6e8b](https://linux-hardware.org/?probe=7048aa6e8b) | Sep 22, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [ff5e9a45c3](https://linux-hardware.org/?probe=ff5e9a45c3) | Sep 21, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [64b5e6acaf](https://linux-hardware.org/?probe=64b5e6acaf) | Sep 21, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [5e6cd3a827](https://linux-hardware.org/?probe=5e6cd3a827) | Sep 21, 2021 |
| Dell          | Vostro 5471                 | [4ce9cddd8f](https://linux-hardware.org/?probe=4ce9cddd8f) | Sep 21, 2021 |
| Lenovo        | ThinkPad E590 20NB0029GE    | [65802f1a29](https://linux-hardware.org/?probe=65802f1a29) | Sep 21, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [14ea1aaa38](https://linux-hardware.org/?probe=14ea1aaa38) | Sep 21, 2021 |
| Lenovo        | ThinkPad T480S 20L7002HC... | [18b74e9f12](https://linux-hardware.org/?probe=18b74e9f12) | Sep 21, 2021 |
| HP            | Compaq CQ58                 | [ab40e7b1de](https://linux-hardware.org/?probe=ab40e7b1de) | Sep 21, 2021 |
| HP            | Compaq CQ58                 | [13687ea608](https://linux-hardware.org/?probe=13687ea608) | Sep 21, 2021 |
| ASUSTek       | K50IN                       | [7cdaef32aa](https://linux-hardware.org/?probe=7cdaef32aa) | Sep 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [203ccd91be](https://linux-hardware.org/?probe=203ccd91be) | Sep 20, 2021 |
| HUAWEI        | HN-WX9X                     | [e8748906aa](https://linux-hardware.org/?probe=e8748906aa) | Sep 20, 2021 |
| MSI           | GE70 2QE                    | [a8b9147ea7](https://linux-hardware.org/?probe=a8b9147ea7) | Sep 20, 2021 |
| Apple         | MacBookPro5,5               | [22262e98a5](https://linux-hardware.org/?probe=22262e98a5) | Sep 20, 2021 |
| Apple         | MacBookPro5,5               | [c266841471](https://linux-hardware.org/?probe=c266841471) | Sep 20, 2021 |
| HUAWEI        | HN-WX9X                     | [81802596f8](https://linux-hardware.org/?probe=81802596f8) | Sep 20, 2021 |
| HP            | Pavilion g6                 | [d7ce22ebcb](https://linux-hardware.org/?probe=d7ce22ebcb) | Sep 20, 2021 |
| HP            | Pavilion g6                 | [3c060f3910](https://linux-hardware.org/?probe=3c060f3910) | Sep 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0UM0... | [bcb44edae6](https://linux-hardware.org/?probe=bcb44edae6) | Sep 20, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0UM0... | [d623d8381b](https://linux-hardware.org/?probe=d623d8381b) | Sep 20, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [39921c4f34](https://linux-hardware.org/?probe=39921c4f34) | Sep 20, 2021 |
| Lenovo        | ThinkPad P53 20QQA004CD     | [50b6533131](https://linux-hardware.org/?probe=50b6533131) | Sep 20, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [72c81ecb73](https://linux-hardware.org/?probe=72c81ecb73) | Sep 19, 2021 |
| MSI           | U270 series                 | [6b98f78732](https://linux-hardware.org/?probe=6b98f78732) | Sep 19, 2021 |
| Acer          | AOA110                      | [a54c248743](https://linux-hardware.org/?probe=a54c248743) | Sep 19, 2021 |
| HP            | Pavilion dv6                | [b4d25f6f3a](https://linux-hardware.org/?probe=b4d25f6f3a) | Sep 19, 2021 |
| Sony          | VGN-CR21Z_N                 | [6fc19f4c67](https://linux-hardware.org/?probe=6fc19f4c67) | Sep 19, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [5dabdbd945](https://linux-hardware.org/?probe=5dabdbd945) | Sep 19, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [61fd64b037](https://linux-hardware.org/?probe=61fd64b037) | Sep 19, 2021 |
| MSI           | U270 series                 | [725e0a6a36](https://linux-hardware.org/?probe=725e0a6a36) | Sep 18, 2021 |
| Acer          | Aspire 5560                 | [f35af81d19](https://linux-hardware.org/?probe=f35af81d19) | Sep 18, 2021 |
| Dell          | Latitude E7450              | [f5963dc359](https://linux-hardware.org/?probe=f5963dc359) | Sep 18, 2021 |
| Lenovo        | G70-35 80Q5                 | [6ce6f8e7f7](https://linux-hardware.org/?probe=6ce6f8e7f7) | Sep 17, 2021 |
| Lenovo        | IdeaPad U510 4941           | [f5774645c1](https://linux-hardware.org/?probe=f5774645c1) | Sep 17, 2021 |
| HP            | 255 G7 Notebook PC          | [0f6db66354](https://linux-hardware.org/?probe=0f6db66354) | Sep 17, 2021 |
| HUAWEI        | HN-WX9X                     | [2179e59b37](https://linux-hardware.org/?probe=2179e59b37) | Sep 17, 2021 |
| HP            | 255 G7 Notebook PC          | [84394a400e](https://linux-hardware.org/?probe=84394a400e) | Sep 17, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [726f5ed51f](https://linux-hardware.org/?probe=726f5ed51f) | Sep 17, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [e0307085f3](https://linux-hardware.org/?probe=e0307085f3) | Sep 17, 2021 |
| MSI           | GE70 2QE                    | [e7b42c85f1](https://linux-hardware.org/?probe=e7b42c85f1) | Sep 17, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [abd7f0d0a1](https://linux-hardware.org/?probe=abd7f0d0a1) | Sep 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [c8208bc767](https://linux-hardware.org/?probe=c8208bc767) | Sep 17, 2021 |
| MSI           | GF75 Thin 9SC               | [47a6cd4031](https://linux-hardware.org/?probe=47a6cd4031) | Sep 17, 2021 |
| MSI           | GE70 2QE                    | [8d4eff5ca2](https://linux-hardware.org/?probe=8d4eff5ca2) | Sep 17, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [f226485da3](https://linux-hardware.org/?probe=f226485da3) | Sep 17, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [643fafdceb](https://linux-hardware.org/?probe=643fafdceb) | Sep 17, 2021 |
| HUAWEI        | HN-WX9X                     | [e801613095](https://linux-hardware.org/?probe=e801613095) | Sep 17, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [fb0c3317e3](https://linux-hardware.org/?probe=fb0c3317e3) | Sep 17, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [5282f852aa](https://linux-hardware.org/?probe=5282f852aa) | Sep 17, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [dd5496fa35](https://linux-hardware.org/?probe=dd5496fa35) | Sep 17, 2021 |
| Timi          | TM1801                      | [d0919977cb](https://linux-hardware.org/?probe=d0919977cb) | Sep 17, 2021 |
| MSI           | Bravo 15 A4DDR              | [722f184570](https://linux-hardware.org/?probe=722f184570) | Sep 17, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [10c9991f0b](https://linux-hardware.org/?probe=10c9991f0b) | Sep 16, 2021 |
| ASUSTek       | X751LD                      | [df29a592fb](https://linux-hardware.org/?probe=df29a592fb) | Sep 16, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [6b7410fa5c](https://linux-hardware.org/?probe=6b7410fa5c) | Sep 16, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [ee258307b1](https://linux-hardware.org/?probe=ee258307b1) | Sep 15, 2021 |
| PC Special... | Standard                    | [1454a60100](https://linux-hardware.org/?probe=1454a60100) | Sep 15, 2021 |
| Lenovo        | ThinkPad E460 20EUA00AAC    | [c7d8dc11ca](https://linux-hardware.org/?probe=c7d8dc11ca) | Sep 15, 2021 |
| ASUSTek       | X555LD                      | [576b90b734](https://linux-hardware.org/?probe=576b90b734) | Sep 15, 2021 |
| ASUSTek       | X555LD                      | [e9c177240a](https://linux-hardware.org/?probe=e9c177240a) | Sep 15, 2021 |
| Acer          | AO725                       | [68eeff0c2f](https://linux-hardware.org/?probe=68eeff0c2f) | Sep 15, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [730c0eebf9](https://linux-hardware.org/?probe=730c0eebf9) | Sep 14, 2021 |
| Lenovo        | V330-15IKB 81AX             | [a062985645](https://linux-hardware.org/?probe=a062985645) | Sep 14, 2021 |
| Dell          | Inspiron 15-3567            | [7e486cd179](https://linux-hardware.org/?probe=7e486cd179) | Sep 14, 2021 |
| Aquarius      | NS585                       | [7f88a77812](https://linux-hardware.org/?probe=7f88a77812) | Sep 14, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e606ccc75f](https://linux-hardware.org/?probe=e606ccc75f) | Sep 14, 2021 |
| Aquarius      | NS585                       | [f2363c7d5e](https://linux-hardware.org/?probe=f2363c7d5e) | Sep 14, 2021 |
| Acer          | Aspire A315-23              | [01008b3cfd](https://linux-hardware.org/?probe=01008b3cfd) | Sep 13, 2021 |
| Apple         | MacBookAir7,1               | [cd3844f542](https://linux-hardware.org/?probe=cd3844f542) | Sep 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [eb55a1f000](https://linux-hardware.org/?probe=eb55a1f000) | Sep 13, 2021 |
| HP            | Notebook                    | [17f4133e28](https://linux-hardware.org/?probe=17f4133e28) | Sep 13, 2021 |
| Lenovo        | G50-45 80E3                 | [51cf32f87c](https://linux-hardware.org/?probe=51cf32f87c) | Sep 12, 2021 |
| Lenovo        | ThinkPad E14 20RB0028BR     | [8b1b3a98ba](https://linux-hardware.org/?probe=8b1b3a98ba) | Sep 12, 2021 |
| ASUSTek       | M3N                         | [28a5b48a05](https://linux-hardware.org/?probe=28a5b48a05) | Sep 12, 2021 |
| ASUSTek       | M3N                         | [04307947ae](https://linux-hardware.org/?probe=04307947ae) | Sep 12, 2021 |
| Lenovo        | V15-IIL 82C5                | [64a2841581](https://linux-hardware.org/?probe=64a2841581) | Sep 11, 2021 |
| Apple         | MacBookAir7,1               | [795f6bba58](https://linux-hardware.org/?probe=795f6bba58) | Sep 10, 2021 |
| Schenker      | XMG NEO (TGL/M21)           | [de8f619f3c](https://linux-hardware.org/?probe=de8f619f3c) | Sep 10, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [10c0154577](https://linux-hardware.org/?probe=10c0154577) | Sep 10, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b95c1b013e](https://linux-hardware.org/?probe=b95c1b013e) | Sep 10, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [2377281799](https://linux-hardware.org/?probe=2377281799) | Sep 09, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [13d65a1a4e](https://linux-hardware.org/?probe=13d65a1a4e) | Sep 09, 2021 |
| ASUSTek       | X540NA                      | [f14257cc20](https://linux-hardware.org/?probe=f14257cc20) | Sep 09, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8433dfbbb9](https://linux-hardware.org/?probe=8433dfbbb9) | Sep 09, 2021 |
| Apple         | MacBookPro10,1              | [1ff67401db](https://linux-hardware.org/?probe=1ff67401db) | Sep 09, 2021 |
| LG Electro... | A410-K.BE43P1               | [7add887914](https://linux-hardware.org/?probe=7add887914) | Sep 08, 2021 |
| Apple         | MacBookAir7,2               | [5c6f3696b2](https://linux-hardware.org/?probe=5c6f3696b2) | Sep 08, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [d21daec9ea](https://linux-hardware.org/?probe=d21daec9ea) | Sep 08, 2021 |
| Lenovo        | ThinkPad T430 2349D10       | [11ab5d413d](https://linux-hardware.org/?probe=11ab5d413d) | Sep 08, 2021 |
| Lenovo        | ThinkPad X230 2325B12       | [a55f42da78](https://linux-hardware.org/?probe=a55f42da78) | Sep 08, 2021 |
| ASUSTek       | K52F                        | [b1f04036d8](https://linux-hardware.org/?probe=b1f04036d8) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | [19cfc85441](https://linux-hardware.org/?probe=19cfc85441) | Sep 07, 2021 |
| Lenovo        | ThinkPad P50 20EN0006MS     | [55f595b53f](https://linux-hardware.org/?probe=55f595b53f) | Sep 07, 2021 |
| ASUSTek       | K52F                        | [0d72cf73ac](https://linux-hardware.org/?probe=0d72cf73ac) | Sep 07, 2021 |
| MSI           | GF63 8RD                    | [498dd20152](https://linux-hardware.org/?probe=498dd20152) | Sep 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [6fc35e97d8](https://linux-hardware.org/?probe=6fc35e97d8) | Sep 07, 2021 |
| Dell          | Latitude 7480               | [844ab8df38](https://linux-hardware.org/?probe=844ab8df38) | Sep 06, 2021 |
| HP            | Laptop 15s-eq1xxx           | [9256f3fece](https://linux-hardware.org/?probe=9256f3fece) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | [7f6c0d6337](https://linux-hardware.org/?probe=7f6c0d6337) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | [e6ea97df06](https://linux-hardware.org/?probe=e6ea97df06) | Sep 06, 2021 |
| Acer          | Aspire A315-23              | [3aedb68952](https://linux-hardware.org/?probe=3aedb68952) | Sep 06, 2021 |
| Samsung       | NC10                        | [98ba59d155](https://linux-hardware.org/?probe=98ba59d155) | Sep 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [e42726b566](https://linux-hardware.org/?probe=e42726b566) | Sep 06, 2021 |
| Dell          | Vostro 5490                 | [b6e28c84c8](https://linux-hardware.org/?probe=b6e28c84c8) | Sep 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [2a4adea555](https://linux-hardware.org/?probe=2a4adea555) | Sep 05, 2021 |
| Toshiba       | Satellite C55-B             | [fe8833475a](https://linux-hardware.org/?probe=fe8833475a) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | [0a1850f760](https://linux-hardware.org/?probe=0a1850f760) | Sep 05, 2021 |
| HP            | EliteBook 820 G1            | [4ba7363e9e](https://linux-hardware.org/?probe=4ba7363e9e) | Sep 05, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [18fe596fba](https://linux-hardware.org/?probe=18fe596fba) | Sep 04, 2021 |
| HP            | Presario CQ62               | [4cdec89015](https://linux-hardware.org/?probe=4cdec89015) | Sep 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [9e235c4228](https://linux-hardware.org/?probe=9e235c4228) | Sep 04, 2021 |
| Dell          | Inspiron 1525               | [0e32e6945b](https://linux-hardware.org/?probe=0e32e6945b) | Sep 03, 2021 |
| Apple         | MacBookAir7,2               | [db35296aa1](https://linux-hardware.org/?probe=db35296aa1) | Sep 03, 2021 |
| Acer          | Aspire A315-23              | [fafd031d1f](https://linux-hardware.org/?probe=fafd031d1f) | Sep 03, 2021 |
| Apple         | MacBookAir7,2               | [1449c0a9cd](https://linux-hardware.org/?probe=1449c0a9cd) | Sep 02, 2021 |
| ASUSTek       | UX303LNB                    | [e0756d7ae6](https://linux-hardware.org/?probe=e0756d7ae6) | Sep 02, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [5d183d4587](https://linux-hardware.org/?probe=5d183d4587) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [666c4fef08](https://linux-hardware.org/?probe=666c4fef08) | Sep 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [d6ee033eb7](https://linux-hardware.org/?probe=d6ee033eb7) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | [28fbb3d82d](https://linux-hardware.org/?probe=28fbb3d82d) | Sep 02, 2021 |
| Apple         | MacBookAir7,1               | [27c2ebc917](https://linux-hardware.org/?probe=27c2ebc917) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | [1d9e3a7503](https://linux-hardware.org/?probe=1d9e3a7503) | Sep 02, 2021 |
| Acer          | Aspire A315-23              | [97c9e2dc1f](https://linux-hardware.org/?probe=97c9e2dc1f) | Sep 02, 2021 |
| HP            | EliteBook Folio 1040 G3     | [6bf33dd2cb](https://linux-hardware.org/?probe=6bf33dd2cb) | Sep 01, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | [f1cad98694](https://linux-hardware.org/?probe=f1cad98694) | Sep 01, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [d542a6b8f9](https://linux-hardware.org/?probe=d542a6b8f9) | Sep 01, 2021 |
| Acer          | Aspire A315-23              | [12a5a0f9c5](https://linux-hardware.org/?probe=12a5a0f9c5) | Sep 01, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3267eec643](https://linux-hardware.org/?probe=3267eec643) | Sep 01, 2021 |
| Timi          | TM1613                      | [f25eeca060](https://linux-hardware.org/?probe=f25eeca060) | Sep 01, 2021 |
| Lenovo        | ThinkPad T430 2349S9E       | [bc224fb15f](https://linux-hardware.org/?probe=bc224fb15f) | Aug 31, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [9510c18df6](https://linux-hardware.org/?probe=9510c18df6) | Aug 31, 2021 |
| HP            | Laptop 15s-eq1xxx           | [783955d696](https://linux-hardware.org/?probe=783955d696) | Aug 31, 2021 |
| Lenovo        | ThinkPad X250 20CLS2DK00    | [db94fcaf10](https://linux-hardware.org/?probe=db94fcaf10) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | [baf38e8736](https://linux-hardware.org/?probe=baf38e8736) | Aug 31, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [33a45018fc](https://linux-hardware.org/?probe=33a45018fc) | Aug 31, 2021 |
| Fujitsu Si... | LIFEBOOK S6420              | [b26e82328a](https://linux-hardware.org/?probe=b26e82328a) | Aug 31, 2021 |
| Apple         | MacBookAir7,2               | [70835c3aa7](https://linux-hardware.org/?probe=70835c3aa7) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | [3e22f55c7b](https://linux-hardware.org/?probe=3e22f55c7b) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | [b73b366bb6](https://linux-hardware.org/?probe=b73b366bb6) | Aug 30, 2021 |
| Toshiba       | Satellite C55-B             | [e1b2dc4810](https://linux-hardware.org/?probe=e1b2dc4810) | Aug 30, 2021 |
| Apple         | MacBookAir7,1               | [e94ab065a3](https://linux-hardware.org/?probe=e94ab065a3) | Aug 30, 2021 |
| HP            | EliteBook 8460p             | [b1425fa900](https://linux-hardware.org/?probe=b1425fa900) | Aug 30, 2021 |
| Apple         | MacBookAir7,2               | [b5a84f215b](https://linux-hardware.org/?probe=b5a84f215b) | Aug 30, 2021 |
| Dell          | Latitude E6330              | [95d65375e2](https://linux-hardware.org/?probe=95d65375e2) | Aug 30, 2021 |
| Lenovo        | ThinkPad T61 7661BF3        | [69b6d76471](https://linux-hardware.org/?probe=69b6d76471) | Aug 30, 2021 |
| ASUSTek       | K56CB                       | [1a44fc7e8f](https://linux-hardware.org/?probe=1a44fc7e8f) | Aug 29, 2021 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [6fcfbde79d](https://linux-hardware.org/?probe=6fcfbde79d) | Aug 29, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [17ae4593ea](https://linux-hardware.org/?probe=17ae4593ea) | Aug 28, 2021 |
| HP            | EliteBook 840 G3            | [8625d6f2f1](https://linux-hardware.org/?probe=8625d6f2f1) | Aug 28, 2021 |
| Apple         | MacBookAir7,2               | [d215521170](https://linux-hardware.org/?probe=d215521170) | Aug 27, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [2c85ec0205](https://linux-hardware.org/?probe=2c85ec0205) | Aug 27, 2021 |
| Lenovo        | ThinkPad T440p 20AN006GU... | [bca7704bb0](https://linux-hardware.org/?probe=bca7704bb0) | Aug 27, 2021 |
| Apple         | MacBookAir7,2               | [14747d88b3](https://linux-hardware.org/?probe=14747d88b3) | Aug 26, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [87904cbe92](https://linux-hardware.org/?probe=87904cbe92) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [1c2e910793](https://linux-hardware.org/?probe=1c2e910793) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | [4a69118897](https://linux-hardware.org/?probe=4a69118897) | Aug 26, 2021 |
| Apple         | MacBookAir7,1               | [474216fba9](https://linux-hardware.org/?probe=474216fba9) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [76d9383f33](https://linux-hardware.org/?probe=76d9383f33) | Aug 26, 2021 |
| Apple         | MacBookAir7,2               | [213d3f817b](https://linux-hardware.org/?probe=213d3f817b) | Aug 26, 2021 |
| YJKC          | vBOOK Plus RVP7             | [8c051a0ce9](https://linux-hardware.org/?probe=8c051a0ce9) | Aug 26, 2021 |
| Gigabyte      | AORUS 15G KB                | [6afefe68d7](https://linux-hardware.org/?probe=6afefe68d7) | Aug 26, 2021 |
| HP            | ProBook 4530s               | [2b4cab4d7c](https://linux-hardware.org/?probe=2b4cab4d7c) | Aug 25, 2021 |
| Dell          | Inspiron 3537               | [7bab6dd9db](https://linux-hardware.org/?probe=7bab6dd9db) | Aug 25, 2021 |
| HP            | ProBook 450 G7              | [a2f161dee0](https://linux-hardware.org/?probe=a2f161dee0) | Aug 25, 2021 |
| HUAWEI        | WRT-WX9                     | [e1e5a14c77](https://linux-hardware.org/?probe=e1e5a14c77) | Aug 25, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [3da8591ac6](https://linux-hardware.org/?probe=3da8591ac6) | Aug 25, 2021 |
| HP            | 630                         | [004d2b364d](https://linux-hardware.org/?probe=004d2b364d) | Aug 25, 2021 |
| Dell          | Latitude 7490               | [23ad45f1fd](https://linux-hardware.org/?probe=23ad45f1fd) | Aug 25, 2021 |
| Apple         | MacBookAir7,2               | [65d82bc8e7](https://linux-hardware.org/?probe=65d82bc8e7) | Aug 24, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [e1bd0ec7fd](https://linux-hardware.org/?probe=e1bd0ec7fd) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | [8a72f87e7b](https://linux-hardware.org/?probe=8a72f87e7b) | Aug 24, 2021 |
| Apple         | MacBookAir7,1               | [1f257714a9](https://linux-hardware.org/?probe=1f257714a9) | Aug 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [102aea0211](https://linux-hardware.org/?probe=102aea0211) | Aug 24, 2021 |
| HP            | Laptop 15s-fq2xxx           | [f755838fd8](https://linux-hardware.org/?probe=f755838fd8) | Aug 24, 2021 |
| Apple         | MacBookAir7,2               | [5cc74103a8](https://linux-hardware.org/?probe=5cc74103a8) | Aug 24, 2021 |
| HP            | 250 G4                      | [5d47aa9804](https://linux-hardware.org/?probe=5d47aa9804) | Aug 24, 2021 |
| ASUSTek       | UX430UAR                    | [77ce457de4](https://linux-hardware.org/?probe=77ce457de4) | Aug 24, 2021 |
| HP            | Laptop 14-cm0xxx            | [df0fa8e968](https://linux-hardware.org/?probe=df0fa8e968) | Aug 24, 2021 |
| Sony          | VPCF115FM                   | [9f9abf79b2](https://linux-hardware.org/?probe=9f9abf79b2) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [8a88eabb1c](https://linux-hardware.org/?probe=8a88eabb1c) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [c4ecd51a21](https://linux-hardware.org/?probe=c4ecd51a21) | Aug 23, 2021 |
| HP            | Laptop 15s-eq1xxx           | [1c9d3bb8b4](https://linux-hardware.org/?probe=1c9d3bb8b4) | Aug 23, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [14af647cc5](https://linux-hardware.org/?probe=14af647cc5) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [5bc9372587](https://linux-hardware.org/?probe=5bc9372587) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [8bcb9e62e1](https://linux-hardware.org/?probe=8bcb9e62e1) | Aug 23, 2021 |
| Apple         | MacBookAir7,2               | [6c44c4f7e3](https://linux-hardware.org/?probe=6c44c4f7e3) | Aug 23, 2021 |
| Google        | Enguarde                    | [12a2003770](https://linux-hardware.org/?probe=12a2003770) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [7f190e4ed2](https://linux-hardware.org/?probe=7f190e4ed2) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [2db5cafda3](https://linux-hardware.org/?probe=2db5cafda3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [abcab36e0c](https://linux-hardware.org/?probe=abcab36e0c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f3ccb91568](https://linux-hardware.org/?probe=f3ccb91568) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [0d8fa16f47](https://linux-hardware.org/?probe=0d8fa16f47) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [680e8106ec](https://linux-hardware.org/?probe=680e8106ec) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [c18b0215e9](https://linux-hardware.org/?probe=c18b0215e9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [fcc821b941](https://linux-hardware.org/?probe=fcc821b941) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [59f760dbb9](https://linux-hardware.org/?probe=59f760dbb9) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [e22a8e2ea4](https://linux-hardware.org/?probe=e22a8e2ea4) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [4fc69342da](https://linux-hardware.org/?probe=4fc69342da) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f2fcae5696](https://linux-hardware.org/?probe=f2fcae5696) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [2f823b2f52](https://linux-hardware.org/?probe=2f823b2f52) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [adf5b71331](https://linux-hardware.org/?probe=adf5b71331) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [618c1c7838](https://linux-hardware.org/?probe=618c1c7838) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [0dff1056d5](https://linux-hardware.org/?probe=0dff1056d5) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [fb0cf0a7a3](https://linux-hardware.org/?probe=fb0cf0a7a3) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6b9f550210](https://linux-hardware.org/?probe=6b9f550210) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [4b22440e91](https://linux-hardware.org/?probe=4b22440e91) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6bab7cdc7c](https://linux-hardware.org/?probe=6bab7cdc7c) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [d2a08022bd](https://linux-hardware.org/?probe=d2a08022bd) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [f39d94cf1b](https://linux-hardware.org/?probe=f39d94cf1b) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [e35bbfda2d](https://linux-hardware.org/?probe=e35bbfda2d) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [60170675ca](https://linux-hardware.org/?probe=60170675ca) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [64a6aa27db](https://linux-hardware.org/?probe=64a6aa27db) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [06b1dab7a0](https://linux-hardware.org/?probe=06b1dab7a0) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [cec5c36945](https://linux-hardware.org/?probe=cec5c36945) | Aug 23, 2021 |
| Apple         | MacBookAir7,1               | [6f38e35f9a](https://linux-hardware.org/?probe=6f38e35f9a) | Aug 23, 2021 |
| HP            | EliteBook 840 G4            | [ebe40b3244](https://linux-hardware.org/?probe=ebe40b3244) | Aug 22, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [d98bdb0d1c](https://linux-hardware.org/?probe=d98bdb0d1c) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [d688bffa01](https://linux-hardware.org/?probe=d688bffa01) | Aug 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [3d52884b6e](https://linux-hardware.org/?probe=3d52884b6e) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | [57b847b12c](https://linux-hardware.org/?probe=57b847b12c) | Aug 22, 2021 |
| ASUSTek       | G771JM                      | [db4b9878fa](https://linux-hardware.org/?probe=db4b9878fa) | Aug 22, 2021 |
| Dell          | Inspiron 6000               | [67c6b36361](https://linux-hardware.org/?probe=67c6b36361) | Aug 22, 2021 |
| Dell          | Inspiron 3593               | [dfed5d8b7a](https://linux-hardware.org/?probe=dfed5d8b7a) | Aug 21, 2021 |
| Dell          | Latitude E7470              | [e954672cb2](https://linux-hardware.org/?probe=e954672cb2) | Aug 21, 2021 |
| Lenovo        | IdeaPad Y500 20193          | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HP            | 14s-dq2003nw                | [f4dcd70da5](https://linux-hardware.org/?probe=f4dcd70da5) | Aug 21, 2021 |
| Lenovo        | ThinkPad E570 20H500B4GE    | [be964b556b](https://linux-hardware.org/?probe=be964b556b) | Aug 21, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [5ecdc39ac1](https://linux-hardware.org/?probe=5ecdc39ac1) | Aug 21, 2021 |
| Dell          | Precision 7520              | [372d627a69](https://linux-hardware.org/?probe=372d627a69) | Aug 21, 2021 |
| Apple         | MacBookAir7,1               | [daa01f79aa](https://linux-hardware.org/?probe=daa01f79aa) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [a96a7ada4f](https://linux-hardware.org/?probe=a96a7ada4f) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [c8305c0d4c](https://linux-hardware.org/?probe=c8305c0d4c) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [77359352d0](https://linux-hardware.org/?probe=77359352d0) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | [5312257240](https://linux-hardware.org/?probe=5312257240) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [75e262ddba](https://linux-hardware.org/?probe=75e262ddba) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [bd216572a3](https://linux-hardware.org/?probe=bd216572a3) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [e57aeadfef](https://linux-hardware.org/?probe=e57aeadfef) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [7211565d4a](https://linux-hardware.org/?probe=7211565d4a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [1c490522df](https://linux-hardware.org/?probe=1c490522df) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [16f0b9c14a](https://linux-hardware.org/?probe=16f0b9c14a) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [691bb379e5](https://linux-hardware.org/?probe=691bb379e5) | Aug 20, 2021 |
| Apple         | MacBookAir7,1               | [fe880ac0c8](https://linux-hardware.org/?probe=fe880ac0c8) | Aug 20, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [a5a146e42a](https://linux-hardware.org/?probe=a5a146e42a) | Aug 20, 2021 |
| Apple         | MacBookAir7,2               | [c60ef3fa1e](https://linux-hardware.org/?probe=c60ef3fa1e) | Aug 20, 2021 |
| Timi          | TM1612                      | [485caf5846](https://linux-hardware.org/?probe=485caf5846) | Aug 20, 2021 |
| Lenovo        | V510-15IKB 80WQ             | [2a61705899](https://linux-hardware.org/?probe=2a61705899) | Aug 20, 2021 |
| SLIMBOOK      | TITAN                       | [a2abd981d1](https://linux-hardware.org/?probe=a2abd981d1) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [1ce6738560](https://linux-hardware.org/?probe=1ce6738560) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [e134a1f7c3](https://linux-hardware.org/?probe=e134a1f7c3) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [87fa430aab](https://linux-hardware.org/?probe=87fa430aab) | Aug 19, 2021 |
| Apple         | MacBookAir7,2               | [c989eac16b](https://linux-hardware.org/?probe=c989eac16b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [3169e477dd](https://linux-hardware.org/?probe=3169e477dd) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [5fcb7fdb26](https://linux-hardware.org/?probe=5fcb7fdb26) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [7afbba35b0](https://linux-hardware.org/?probe=7afbba35b0) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [f1d159bbd1](https://linux-hardware.org/?probe=f1d159bbd1) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [38e8211556](https://linux-hardware.org/?probe=38e8211556) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [bd587e5998](https://linux-hardware.org/?probe=bd587e5998) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [3fa54711ec](https://linux-hardware.org/?probe=3fa54711ec) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [4a7f287161](https://linux-hardware.org/?probe=4a7f287161) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [fed5f28778](https://linux-hardware.org/?probe=fed5f28778) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [0ba8599928](https://linux-hardware.org/?probe=0ba8599928) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [e31d43b39d](https://linux-hardware.org/?probe=e31d43b39d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [703cdcf766](https://linux-hardware.org/?probe=703cdcf766) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [9b8ce55c3d](https://linux-hardware.org/?probe=9b8ce55c3d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [2b4af51f46](https://linux-hardware.org/?probe=2b4af51f46) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [b802b4a25b](https://linux-hardware.org/?probe=b802b4a25b) | Aug 18, 2021 |
| Google        | Enguarde                    | [cb421b796b](https://linux-hardware.org/?probe=cb421b796b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [f6c7230675](https://linux-hardware.org/?probe=f6c7230675) | Aug 18, 2021 |
| Google        | Enguarde                    | [7116839a4b](https://linux-hardware.org/?probe=7116839a4b) | Aug 18, 2021 |
| Google        | Enguarde                    | [04817bfb7f](https://linux-hardware.org/?probe=04817bfb7f) | Aug 18, 2021 |
| Google        | Enguarde                    | [92b401a705](https://linux-hardware.org/?probe=92b401a705) | Aug 18, 2021 |
| Google        | Enguarde                    | [f2a438a9be](https://linux-hardware.org/?probe=f2a438a9be) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [c9239b499b](https://linux-hardware.org/?probe=c9239b499b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [b708a97ef1](https://linux-hardware.org/?probe=b708a97ef1) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [31dc792a8b](https://linux-hardware.org/?probe=31dc792a8b) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [76a48b344d](https://linux-hardware.org/?probe=76a48b344d) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [244aba47d4](https://linux-hardware.org/?probe=244aba47d4) | Aug 18, 2021 |
| Google        | Enguarde                    | [b2391216c6](https://linux-hardware.org/?probe=b2391216c6) | Aug 18, 2021 |
| Google        | Enguarde                    | [53b311c24c](https://linux-hardware.org/?probe=53b311c24c) | Aug 18, 2021 |
| Google        | Enguarde                    | [61de56951c](https://linux-hardware.org/?probe=61de56951c) | Aug 18, 2021 |
| Google        | Enguarde                    | [7fd7f1ea77](https://linux-hardware.org/?probe=7fd7f1ea77) | Aug 18, 2021 |
| Google        | Enguarde                    | [2a090f8b2a](https://linux-hardware.org/?probe=2a090f8b2a) | Aug 18, 2021 |
| Google        | Enguarde                    | [62e4ff915a](https://linux-hardware.org/?probe=62e4ff915a) | Aug 18, 2021 |
| Google        | Enguarde                    | [eada085a33](https://linux-hardware.org/?probe=eada085a33) | Aug 18, 2021 |
| Google        | Enguarde                    | [474e20b9f2](https://linux-hardware.org/?probe=474e20b9f2) | Aug 18, 2021 |
| ASUSTek       | UX305CA                     | [6ab6beca67](https://linux-hardware.org/?probe=6ab6beca67) | Aug 18, 2021 |
| HP            | EliteBook 820 G1            | [c7155dfa07](https://linux-hardware.org/?probe=c7155dfa07) | Aug 18, 2021 |
| Apple         | MacBookAir7,2               | [451fe761a6](https://linux-hardware.org/?probe=451fe761a6) | Aug 18, 2021 |
| Google        | Enguarde                    | [dd0de8b832](https://linux-hardware.org/?probe=dd0de8b832) | Aug 17, 2021 |
| Google        | Enguarde                    | [a6ac2782a6](https://linux-hardware.org/?probe=a6ac2782a6) | Aug 17, 2021 |
| Google        | Enguarde                    | [d32e974941](https://linux-hardware.org/?probe=d32e974941) | Aug 17, 2021 |
| Google        | Enguarde                    | [fe90c1da98](https://linux-hardware.org/?probe=fe90c1da98) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [c3d98780bf](https://linux-hardware.org/?probe=c3d98780bf) | Aug 17, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [4b38b9e598](https://linux-hardware.org/?probe=4b38b9e598) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2c30321150](https://linux-hardware.org/?probe=2c30321150) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2f6317ebc5](https://linux-hardware.org/?probe=2f6317ebc5) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [707606ff5e](https://linux-hardware.org/?probe=707606ff5e) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [0c43bb89c0](https://linux-hardware.org/?probe=0c43bb89c0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [fcb540b848](https://linux-hardware.org/?probe=fcb540b848) | Aug 17, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [46240d5ef9](https://linux-hardware.org/?probe=46240d5ef9) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [6e85db6058](https://linux-hardware.org/?probe=6e85db6058) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [2e26440865](https://linux-hardware.org/?probe=2e26440865) | Aug 17, 2021 |
| Apple         | MacBook7,1                  | [5ad65197ad](https://linux-hardware.org/?probe=5ad65197ad) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [c185e120f1](https://linux-hardware.org/?probe=c185e120f1) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [ee22c0dcc0](https://linux-hardware.org/?probe=ee22c0dcc0) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b3fd5bee39](https://linux-hardware.org/?probe=b3fd5bee39) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [d68e571cd0](https://linux-hardware.org/?probe=d68e571cd0) | Aug 17, 2021 |
| Dell          | Latitude 7480               | [49272ed382](https://linux-hardware.org/?probe=49272ed382) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [28c2f85e9c](https://linux-hardware.org/?probe=28c2f85e9c) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [1f8c3f9487](https://linux-hardware.org/?probe=1f8c3f9487) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [9f6a737d07](https://linux-hardware.org/?probe=9f6a737d07) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [4eb4afec6b](https://linux-hardware.org/?probe=4eb4afec6b) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [5949002919](https://linux-hardware.org/?probe=5949002919) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b0d4ba09f6](https://linux-hardware.org/?probe=b0d4ba09f6) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [12377bdf65](https://linux-hardware.org/?probe=12377bdf65) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [f345284082](https://linux-hardware.org/?probe=f345284082) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [6229638b59](https://linux-hardware.org/?probe=6229638b59) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [b95e1787ff](https://linux-hardware.org/?probe=b95e1787ff) | Aug 17, 2021 |
| Apple         | MacBookAir7,1               | [f1d344625b](https://linux-hardware.org/?probe=f1d344625b) | Aug 17, 2021 |
| Google        | Enguarde                    | [4d7eaa38ba](https://linux-hardware.org/?probe=4d7eaa38ba) | Aug 17, 2021 |
| Google        | Enguarde                    | [8be28c3080](https://linux-hardware.org/?probe=8be28c3080) | Aug 17, 2021 |
| Lenovo        | ThinkPad X230 2325AT6       | [9e66245080](https://linux-hardware.org/?probe=9e66245080) | Aug 17, 2021 |
| Google        | Enguarde                    | [cfdf77fbd9](https://linux-hardware.org/?probe=cfdf77fbd9) | Aug 17, 2021 |
| Google        | Enguarde                    | [6e84dfb541](https://linux-hardware.org/?probe=6e84dfb541) | Aug 17, 2021 |
| Google        | Enguarde                    | [2549683d9f](https://linux-hardware.org/?probe=2549683d9f) | Aug 17, 2021 |
| Dell          | Latitude 7410               | [f7f6e5a4d5](https://linux-hardware.org/?probe=f7f6e5a4d5) | Aug 17, 2021 |
| ASUSTek       | 1225B                       | [1dd6877b22](https://linux-hardware.org/?probe=1dd6877b22) | Aug 17, 2021 |
| Google        | Enguarde                    | [0bdebdb178](https://linux-hardware.org/?probe=0bdebdb178) | Aug 16, 2021 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [3a489f9498](https://linux-hardware.org/?probe=3a489f9498) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [635d3ab3e5](https://linux-hardware.org/?probe=635d3ab3e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [2e04ae93d1](https://linux-hardware.org/?probe=2e04ae93d1) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [dffcb4d4f6](https://linux-hardware.org/?probe=dffcb4d4f6) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [e3816a3d3a](https://linux-hardware.org/?probe=e3816a3d3a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d76cf98938](https://linux-hardware.org/?probe=d76cf98938) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [fc7b752ce3](https://linux-hardware.org/?probe=fc7b752ce3) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [346d3ca919](https://linux-hardware.org/?probe=346d3ca919) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [eb7cdde4b5](https://linux-hardware.org/?probe=eb7cdde4b5) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [ae1b239645](https://linux-hardware.org/?probe=ae1b239645) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d7e9112089](https://linux-hardware.org/?probe=d7e9112089) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [35ab4c3075](https://linux-hardware.org/?probe=35ab4c3075) | Aug 16, 2021 |
| Lenovo        | ThinkPad E490 20N8001EUS    | [40796d62c2](https://linux-hardware.org/?probe=40796d62c2) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [1fa30fb77a](https://linux-hardware.org/?probe=1fa30fb77a) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [81f2a65461](https://linux-hardware.org/?probe=81f2a65461) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [a54d2e496c](https://linux-hardware.org/?probe=a54d2e496c) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [d0581c16e9](https://linux-hardware.org/?probe=d0581c16e9) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [4704dd7dc2](https://linux-hardware.org/?probe=4704dd7dc2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [2d48e28c72](https://linux-hardware.org/?probe=2d48e28c72) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [dcded26792](https://linux-hardware.org/?probe=dcded26792) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [de06f0cb03](https://linux-hardware.org/?probe=de06f0cb03) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [3171a06ab2](https://linux-hardware.org/?probe=3171a06ab2) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [154d3f4aac](https://linux-hardware.org/?probe=154d3f4aac) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 20J10046US      | [6943b835e5](https://linux-hardware.org/?probe=6943b835e5) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [56e2f75dab](https://linux-hardware.org/?probe=56e2f75dab) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [7e070c3cee](https://linux-hardware.org/?probe=7e070c3cee) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [be42bbb09a](https://linux-hardware.org/?probe=be42bbb09a) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [42a5d4fb48](https://linux-hardware.org/?probe=42a5d4fb48) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [845219864e](https://linux-hardware.org/?probe=845219864e) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [99531c5564](https://linux-hardware.org/?probe=99531c5564) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [7e2e8d1364](https://linux-hardware.org/?probe=7e2e8d1364) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [c9b0773c42](https://linux-hardware.org/?probe=c9b0773c42) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [947e3524e3](https://linux-hardware.org/?probe=947e3524e3) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [a30c87c3fe](https://linux-hardware.org/?probe=a30c87c3fe) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [edaac7af9f](https://linux-hardware.org/?probe=edaac7af9f) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [94047a5fdc](https://linux-hardware.org/?probe=94047a5fdc) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [ccd9ef4a72](https://linux-hardware.org/?probe=ccd9ef4a72) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [97aab17694](https://linux-hardware.org/?probe=97aab17694) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [3112135337](https://linux-hardware.org/?probe=3112135337) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [8da303b571](https://linux-hardware.org/?probe=8da303b571) | Aug 16, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [449ea4adf6](https://linux-hardware.org/?probe=449ea4adf6) | Aug 16, 2021 |
| Apple         | MacBookAir7,2               | [5bd9662328](https://linux-hardware.org/?probe=5bd9662328) | Aug 16, 2021 |
| Apple         | MacBookAir7,1               | [079ef9affe](https://linux-hardware.org/?probe=079ef9affe) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [9e81b88eb8](https://linux-hardware.org/?probe=9e81b88eb8) | Aug 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [7b614dd679](https://linux-hardware.org/?probe=7b614dd679) | Aug 16, 2021 |
| Acer          | Swift SF114-33              | [2cd1a890fa](https://linux-hardware.org/?probe=2cd1a890fa) | Aug 16, 2021 |
| Dell          | G3 3590                     | [05e11ad38d](https://linux-hardware.org/?probe=05e11ad38d) | Aug 16, 2021 |
| HP            | 630                         | [a57ed15001](https://linux-hardware.org/?probe=a57ed15001) | Aug 15, 2021 |
| HP            | Laptop 15s-eq1xxx           | [31fcb375f4](https://linux-hardware.org/?probe=31fcb375f4) | Aug 15, 2021 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0X... | [e3fd79d228](https://linux-hardware.org/?probe=e3fd79d228) | Aug 15, 2021 |
| Apple         | MacBookPro11,3              | [daf1b7a963](https://linux-hardware.org/?probe=daf1b7a963) | Aug 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [0b7f4b2da5](https://linux-hardware.org/?probe=0b7f4b2da5) | Aug 15, 2021 |
| Apple         | MacBookPro11,3              | [f6b6388040](https://linux-hardware.org/?probe=f6b6388040) | Aug 14, 2021 |
| HP            | Compaq nc6320 (EV073AV)     | [bf6050f750](https://linux-hardware.org/?probe=bf6050f750) | Aug 14, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [f3506aaa1c](https://linux-hardware.org/?probe=f3506aaa1c) | Aug 14, 2021 |
| Dell          | Latitude 7490               | [6ca174eba8](https://linux-hardware.org/?probe=6ca174eba8) | Aug 14, 2021 |
| Dell          | Latitude 7490               | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| Google        | Enguarde                    | [cac72ff077](https://linux-hardware.org/?probe=cac72ff077) | Aug 13, 2021 |
| Google        | Enguarde                    | [8c489e2c59](https://linux-hardware.org/?probe=8c489e2c59) | Aug 13, 2021 |
| Google        | Enguarde                    | [d79905590c](https://linux-hardware.org/?probe=d79905590c) | Aug 13, 2021 |
| Google        | Enguarde                    | [7efce8d06b](https://linux-hardware.org/?probe=7efce8d06b) | Aug 13, 2021 |
| Google        | Enguarde                    | [c53a0803e7](https://linux-hardware.org/?probe=c53a0803e7) | Aug 13, 2021 |
| Google        | Enguarde                    | [410a4b2e26](https://linux-hardware.org/?probe=410a4b2e26) | Aug 13, 2021 |
| Google        | Enguarde                    | [cbc9f75923](https://linux-hardware.org/?probe=cbc9f75923) | Aug 13, 2021 |
| Google        | Enguarde                    | [4ca322af56](https://linux-hardware.org/?probe=4ca322af56) | Aug 13, 2021 |
| Google        | Enguarde                    | [2af4090c36](https://linux-hardware.org/?probe=2af4090c36) | Aug 13, 2021 |
| Google        | Enguarde                    | [43919a91f3](https://linux-hardware.org/?probe=43919a91f3) | Aug 12, 2021 |
| Google        | Enguarde                    | [c93dcd9531](https://linux-hardware.org/?probe=c93dcd9531) | Aug 12, 2021 |
| Google        | Enguarde                    | [8e7147d832](https://linux-hardware.org/?probe=8e7147d832) | Aug 12, 2021 |
| Apple         | MacBookAir7,1               | [65a4eb9f2c](https://linux-hardware.org/?probe=65a4eb9f2c) | Aug 12, 2021 |
| Google        | Enguarde                    | [e9f95dc0ed](https://linux-hardware.org/?probe=e9f95dc0ed) | Aug 12, 2021 |
| Google        | Enguarde                    | [3b5b9d1698](https://linux-hardware.org/?probe=3b5b9d1698) | Aug 12, 2021 |
| Google        | Enguarde                    | [e423d1eee6](https://linux-hardware.org/?probe=e423d1eee6) | Aug 12, 2021 |
| Google        | Enguarde                    | [1f00600e9b](https://linux-hardware.org/?probe=1f00600e9b) | Aug 12, 2021 |
| Google        | Enguarde                    | [88adc88ccd](https://linux-hardware.org/?probe=88adc88ccd) | Aug 12, 2021 |
| Notebook      | NL4x_NL5xLU                 | [82a8b9c657](https://linux-hardware.org/?probe=82a8b9c657) | Aug 12, 2021 |
| Google        | Enguarde                    | [2434eac448](https://linux-hardware.org/?probe=2434eac448) | Aug 12, 2021 |
| Google        | Enguarde                    | [d766910df0](https://linux-hardware.org/?probe=d766910df0) | Aug 12, 2021 |
| Google        | Enguarde                    | [c0516ce965](https://linux-hardware.org/?probe=c0516ce965) | Aug 12, 2021 |
| Google        | Enguarde                    | [728007c621](https://linux-hardware.org/?probe=728007c621) | Aug 12, 2021 |
| Google        | Enguarde                    | [b808ac5856](https://linux-hardware.org/?probe=b808ac5856) | Aug 12, 2021 |
| Google        | Enguarde                    | [326cc3aae3](https://linux-hardware.org/?probe=326cc3aae3) | Aug 12, 2021 |
| Google        | Enguarde                    | [1fddcb2525](https://linux-hardware.org/?probe=1fddcb2525) | Aug 12, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| Dell          | G7 7790                     | [99dd172940](https://linux-hardware.org/?probe=99dd172940) | Aug 12, 2021 |
| Lenovo        | V14 G2 ITL 82KA             | [2bc14051d8](https://linux-hardware.org/?probe=2bc14051d8) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [cbe8c5170f](https://linux-hardware.org/?probe=cbe8c5170f) | Aug 12, 2021 |
| HP            | ProBook 4530s               | [14a78c65a1](https://linux-hardware.org/?probe=14a78c65a1) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| Samsung       | 300E5M/300E5L               | [4139a3a855](https://linux-hardware.org/?probe=4139a3a855) | Aug 11, 2021 |
| Notebook      | N13_N140ZU                  | [cbaecf1d3e](https://linux-hardware.org/?probe=cbaecf1d3e) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | [48573ed425](https://linux-hardware.org/?probe=48573ed425) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [cabe0ebbc8](https://linux-hardware.org/?probe=cabe0ebbc8) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | [1dcbf85471](https://linux-hardware.org/?probe=1dcbf85471) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | [0c67490330](https://linux-hardware.org/?probe=0c67490330) | Aug 10, 2021 |
| Dell          | Precision 3551              | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| HP            | 250 G4                      | [5640b0689d](https://linux-hardware.org/?probe=5640b0689d) | Aug 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [d650ff0c3e](https://linux-hardware.org/?probe=d650ff0c3e) | Aug 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | [4ce98656a4](https://linux-hardware.org/?probe=4ce98656a4) | Aug 10, 2021 |
| Dell          | Inspiron ME051              | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| Lenovo        | B51-35 80LH                 | [5f87168a65](https://linux-hardware.org/?probe=5f87168a65) | Aug 10, 2021 |
| Apple         | MacBookAir7,1               | [6ab68482c0](https://linux-hardware.org/?probe=6ab68482c0) | Aug 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS3R80... | [fbc29e2063](https://linux-hardware.org/?probe=fbc29e2063) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [e4ce236efd](https://linux-hardware.org/?probe=e4ce236efd) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1c26f935e6](https://linux-hardware.org/?probe=1c26f935e6) | Aug 09, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | [538a15f3cc](https://linux-hardware.org/?probe=538a15f3cc) | Aug 09, 2021 |
| HP            | 2000                        | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| Lenovo        | ThinkPad T580 20L9001AUS    | [65e201224c](https://linux-hardware.org/?probe=65e201224c) | Aug 09, 2021 |
| MSI           | GP60 2PE                    | [516f3cd4e5](https://linux-hardware.org/?probe=516f3cd4e5) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| Lenovo        | ThinkPad T410 2537E49       | [ea10aead92](https://linux-hardware.org/?probe=ea10aead92) | Aug 08, 2021 |
| Dell          | XPS 13 9370                 | [575a84d010](https://linux-hardware.org/?probe=575a84d010) | Aug 08, 2021 |
| Clevo         | W55xEU                      | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| Lenovo        | ThinkPad W500 406152G       | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| Acer          | TravelMate 5720             | [43aae04fa6](https://linux-hardware.org/?probe=43aae04fa6) | Aug 08, 2021 |
| Lenovo        | ThinkPad X230 23252FG       | [1c7914d660](https://linux-hardware.org/?probe=1c7914d660) | Aug 08, 2021 |
| HP            | Laptop 15s-fq2xxx           | [c5ef006a35](https://linux-hardware.org/?probe=c5ef006a35) | Aug 08, 2021 |
| Acer          | Swift SF314-51              | [88fa728376](https://linux-hardware.org/?probe=88fa728376) | Aug 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | [e18202a558](https://linux-hardware.org/?probe=e18202a558) | Aug 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | [a89cdf06f5](https://linux-hardware.org/?probe=a89cdf06f5) | Aug 07, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| Clevo         | P170EM                      | [f101b2b318](https://linux-hardware.org/?probe=f101b2b318) | Aug 07, 2021 |
| Acer          | Aspire E5-575               | [3caca4f238](https://linux-hardware.org/?probe=3caca4f238) | Aug 07, 2021 |
| Acer          | Aspire E5-571P              | [1dbaeef7d2](https://linux-hardware.org/?probe=1dbaeef7d2) | Aug 07, 2021 |
| Google        | Parrot                      | [2efb04c61c](https://linux-hardware.org/?probe=2efb04c61c) | Aug 07, 2021 |
| Lenovo        | ThinkPad T61 7661BK7        | [bbabc03a27](https://linux-hardware.org/?probe=bbabc03a27) | Aug 07, 2021 |
| Sony          | VPCF21AFX                   | [40aa5144f7](https://linux-hardware.org/?probe=40aa5144f7) | Aug 07, 2021 |
| Lenovo        | ThinkPad T450 20BUS16700    | [8123256638](https://linux-hardware.org/?probe=8123256638) | Aug 07, 2021 |
| Dell          | XPS 13 9350                 | [e82d4c3561](https://linux-hardware.org/?probe=e82d4c3561) | Aug 07, 2021 |
| HP            | Pavilion 15                 | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [412f800d01](https://linux-hardware.org/?probe=412f800d01) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | [69696c0e3a](https://linux-hardware.org/?probe=69696c0e3a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| HP            | 630                         | [b2d03b8717](https://linux-hardware.org/?probe=b2d03b8717) | Aug 07, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | [368abe4066](https://linux-hardware.org/?probe=368abe4066) | Aug 07, 2021 |
| HP            | 630                         | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SNZ... | [669874ee19](https://linux-hardware.org/?probe=669874ee19) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [ad24cf2899](https://linux-hardware.org/?probe=ad24cf2899) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | [9f994fc086](https://linux-hardware.org/?probe=9f994fc086) | Aug 07, 2021 |
| Apple         | MacBookAir7,1               | [e2b8c558f7](https://linux-hardware.org/?probe=e2b8c558f7) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [8cc604abc2](https://linux-hardware.org/?probe=8cc604abc2) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [c9c4b53460](https://linux-hardware.org/?probe=c9c4b53460) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [f54c45ab89](https://linux-hardware.org/?probe=f54c45ab89) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [81fef8f548](https://linux-hardware.org/?probe=81fef8f548) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | [4e000b3710](https://linux-hardware.org/?probe=4e000b3710) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | [493e2762bc](https://linux-hardware.org/?probe=493e2762bc) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [2eb3a16b53](https://linux-hardware.org/?probe=2eb3a16b53) | Aug 06, 2021 |
| Dell          | Precision 3540              | [1b8206cd29](https://linux-hardware.org/?probe=1b8206cd29) | Aug 06, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [10811e8109](https://linux-hardware.org/?probe=10811e8109) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | [bba0c0a13c](https://linux-hardware.org/?probe=bba0c0a13c) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [25f1a5ecdf](https://linux-hardware.org/?probe=25f1a5ecdf) | Aug 06, 2021 |
| HP            | EliteBook 8460p             | [a7114078e2](https://linux-hardware.org/?probe=a7114078e2) | Aug 06, 2021 |
| Lenovo        | ThinkPad W520 4284CY1       | [5e1c9e9e30](https://linux-hardware.org/?probe=5e1c9e9e30) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [639bb0ca17](https://linux-hardware.org/?probe=639bb0ca17) | Aug 06, 2021 |
| Dell          | G3 3579                     | [5a268dbc14](https://linux-hardware.org/?probe=5a268dbc14) | Aug 06, 2021 |
| Dell          | G3 3579                     | [6aae1a533f](https://linux-hardware.org/?probe=6aae1a533f) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | [41d352c625](https://linux-hardware.org/?probe=41d352c625) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [3256d646b0](https://linux-hardware.org/?probe=3256d646b0) | Aug 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Dell          | Latitude E7240              | [4dd840f3dd](https://linux-hardware.org/?probe=4dd840f3dd) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | [64b6992b74](https://linux-hardware.org/?probe=64b6992b74) | Aug 06, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [249a58dd07](https://linux-hardware.org/?probe=249a58dd07) | Aug 05, 2021 |
| Apple         | MacBookAir7,2               | [fa1f3da353](https://linux-hardware.org/?probe=fa1f3da353) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | [812e20e37e](https://linux-hardware.org/?probe=812e20e37e) | Aug 05, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [b90c18f9a0](https://linux-hardware.org/?probe=b90c18f9a0) | Aug 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| Apple         | MacBook2,1                  | [103dba0476](https://linux-hardware.org/?probe=103dba0476) | Aug 05, 2021 |
| HP            | ProBook 6450b               | [ec02a5333b](https://linux-hardware.org/?probe=ec02a5333b) | Aug 05, 2021 |
| HP            | 3085B                       | [6be769f55c](https://linux-hardware.org/?probe=6be769f55c) | Aug 05, 2021 |
| Apple         | MacBook5,2                  | [0a79f49420](https://linux-hardware.org/?probe=0a79f49420) | Aug 05, 2021 |
| HP            | Pavilion dm4                | [7ba854b03e](https://linux-hardware.org/?probe=7ba854b03e) | Aug 05, 2021 |
| Clevo         | W240HU/W250HUQ              | [f71032cd7f](https://linux-hardware.org/?probe=f71032cd7f) | Aug 05, 2021 |
| TUXEDO        | Pulse 15 Gen1               | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| Apple         | MacBook7,1                  | [a0e7632e28](https://linux-hardware.org/?probe=a0e7632e28) | Aug 04, 2021 |
| Apple         | MacBook5,2                  | [803a6be591](https://linux-hardware.org/?probe=803a6be591) | Aug 04, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [cca5aa2900](https://linux-hardware.org/?probe=cca5aa2900) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2c8c33becf](https://linux-hardware.org/?probe=2c8c33becf) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [97f8f86784](https://linux-hardware.org/?probe=97f8f86784) | Aug 04, 2021 |
| Notebook      | NJ50_70CU                   | [a9b3790d07](https://linux-hardware.org/?probe=a9b3790d07) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [2d764714a4](https://linux-hardware.org/?probe=2d764714a4) | Aug 04, 2021 |
| Lenovo        | IdeaPad 3 17IIL05 81WF      | [a3914442ca](https://linux-hardware.org/?probe=a3914442ca) | Aug 04, 2021 |
| Acer          | Aspire E5-571G              | [b2a62f65d6](https://linux-hardware.org/?probe=b2a62f65d6) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | [09a6257403](https://linux-hardware.org/?probe=09a6257403) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [eafaf5ece3](https://linux-hardware.org/?probe=eafaf5ece3) | Aug 04, 2021 |
| ASUSTek       | N53Ta                       | [896a02b57b](https://linux-hardware.org/?probe=896a02b57b) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | [c0bf2b7b10](https://linux-hardware.org/?probe=c0bf2b7b10) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [3d29b58c58](https://linux-hardware.org/?probe=3d29b58c58) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | [8b35a81ed6](https://linux-hardware.org/?probe=8b35a81ed6) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [87bca8ecbc](https://linux-hardware.org/?probe=87bca8ecbc) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [fbbd748072](https://linux-hardware.org/?probe=fbbd748072) | Aug 03, 2021 |
| Apple         | MacBook4,1                  | [71738ebf7e](https://linux-hardware.org/?probe=71738ebf7e) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | [06d86172a1](https://linux-hardware.org/?probe=06d86172a1) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | [aa415746d6](https://linux-hardware.org/?probe=aa415746d6) | Aug 03, 2021 |
| Apple         | MacBookAir7,1               | [c8674581d0](https://linux-hardware.org/?probe=c8674581d0) | Aug 03, 2021 |
| Dell          | Latitude E4310              | [75a9aa20f2](https://linux-hardware.org/?probe=75a9aa20f2) | Aug 03, 2021 |
| Google        | Enguarde                    | [c758164470](https://linux-hardware.org/?probe=c758164470) | Aug 03, 2021 |
| Lenovo        | ThinkPad R61e 7650DHU       | [82f2f3a1a7](https://linux-hardware.org/?probe=82f2f3a1a7) | Aug 03, 2021 |
| ASUSTek       | 1005HA                      | [1f83d95a2a](https://linux-hardware.org/?probe=1f83d95a2a) | Aug 03, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | [c14dd630ed](https://linux-hardware.org/?probe=c14dd630ed) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | [99ccdd5455](https://linux-hardware.org/?probe=99ccdd5455) | Aug 02, 2021 |
| Apple         | MacBook5,2                  | [aa5aaf6fd0](https://linux-hardware.org/?probe=aa5aaf6fd0) | Aug 02, 2021 |
| Google        | Stout                       | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| Dell          | Inspiron 5570               | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| Acer          | Aspire A315-23              | [acff56e8e3](https://linux-hardware.org/?probe=acff56e8e3) | Jul 29, 2021 |
| Acer          | Aspire A315-23              | [704ead0e75](https://linux-hardware.org/?probe=704ead0e75) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| Casper        | C17B                        | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| Apple         | MacBookPro11,4              | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| Dell          | Studio 1555                 | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| HP            | Laptop 15s-fq1xxx           | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d7722f9bbf](https://linux-hardware.org/?probe=d7722f9bbf) | Jul 12, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3eceba473e](https://linux-hardware.org/?probe=3eceba473e) | Jul 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [85da1219ad](https://linux-hardware.org/?probe=85da1219ad) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| Acer          | Aspire A315-23              | [bccfe7e145](https://linux-hardware.org/?probe=bccfe7e145) | Jul 08, 2021 |
| Acer          | Aspire A315-23              | [73a418aad6](https://linux-hardware.org/?probe=73a418aad6) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| Acer          | Aspire E5-573               | [d946214a58](https://linux-hardware.org/?probe=d946214a58) | Jul 06, 2021 |
| Dell          | Latitude E6330              | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| HP            | Compaq 6830s                | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| ASUSTek       | K42Jv                       | [88ee690bb2](https://linux-hardware.org/?probe=88ee690bb2) | Jun 30, 2021 |
| Sony          | SVE1512G1RB                 | [41dd93f0c7](https://linux-hardware.org/?probe=41dd93f0c7) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| Acer          | Nitro AN515-51              | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Dell          | Inspiron 3501               | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| MSI           | GF65 Thin 10UE              | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| Dell          | Precision 3560              | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| HP            | ProBook 455 G1              | [c334d50b1f](https://linux-hardware.org/?probe=c334d50b1f) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| Acer          | Aspire ES1-132              | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| Acer          | Aspire A315-23G             | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Acer          | Aspire V3-331               | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Acer          | Aspire A315-23              | [0de49e4ceb](https://linux-hardware.org/?probe=0de49e4ceb) | Jun 11, 2021 |
| Dell          | Latitude E7470              | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| Clevo         | W250ENQ / W270ENQ           | [95fe5984c2](https://linux-hardware.org/?probe=95fe5984c2) | Jun 09, 2021 |
| Clevo         | W250ENQ / W270ENQ           | [b992eee8b5](https://linux-hardware.org/?probe=b992eee8b5) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [d71fba3e59](https://linux-hardware.org/?probe=d71fba3e59) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| Acer          | Aspire A315-23              | [31547cbbcf](https://linux-hardware.org/?probe=31547cbbcf) | May 31, 2021 |
| Acer          | Aspire A315-23              | [4392e54288](https://linux-hardware.org/?probe=4392e54288) | May 31, 2021 |
| Acer          | Aspire A315-23              | [2fda3b392d](https://linux-hardware.org/?probe=2fda3b392d) | May 31, 2021 |
| Acer          | Aspire A315-23              | [41c4d75b72](https://linux-hardware.org/?probe=41c4d75b72) | May 31, 2021 |
| Acer          | Aspire A315-23              | [8b834e3fc0](https://linux-hardware.org/?probe=8b834e3fc0) | May 31, 2021 |
| Acer          | Aspire A315-23              | [8932eef460](https://linux-hardware.org/?probe=8932eef460) | May 31, 2021 |
| Toshiba       | Satellite U800W             | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| MSI           | CX700                       | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Dell          | XPS 13 9310                 | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| Lenovo        | Z710 20250                  | [76d72eb45f](https://linux-hardware.org/?probe=76d72eb45f) | May 27, 2021 |
| Aquarius      | NS585                       | [e2035017ff](https://linux-hardware.org/?probe=e2035017ff) | May 26, 2021 |
| Aquarius      | NS585                       | [d2b5b53798](https://linux-hardware.org/?probe=d2b5b53798) | May 26, 2021 |
| Aquarius      | NS585                       | [1c84a98f48](https://linux-hardware.org/?probe=1c84a98f48) | May 26, 2021 |
| Acer          | Aspire A315-23G             | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23              | [834e2e7b7e](https://linux-hardware.org/?probe=834e2e7b7e) | May 24, 2021 |
| Acer          | Aspire A315-23G             | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Acer          | Aspire A315-23              | [71c9c1e86f](https://linux-hardware.org/?probe=71c9c1e86f) | May 21, 2021 |
| HP            | EliteBook 840 G1            | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Acer          | Aspire A315-23G             | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7480               | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Acer          | Aspire A315-23G             | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| HP            | Compaq Presario C700        | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| ASUSTek       | T100TAS                     | [0b8e360f8a](https://linux-hardware.org/?probe=0b8e360f8a) | May 07, 2021 |
| HP            | Split 13 x2 PC              | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| MSI           | Bravo 15 A4DDR              | [372d11517d](https://linux-hardware.org/?probe=372d11517d) | Apr 28, 2021 |
| Lenovo        | G550 20023                  | [69b57eec89](https://linux-hardware.org/?probe=69b57eec89) | Apr 27, 2021 |
| Lenovo        | IdeaPad Z500 20202          | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| Acer          | Aspire 5560                 | [853337664f](https://linux-hardware.org/?probe=853337664f) | Apr 26, 2021 |
| HP            | EliteBook 8460p             | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Dell          | Latitude E6330              | [d2a06d1cde](https://linux-hardware.org/?probe=d2a06d1cde) | Apr 22, 2021 |
| MSI           | Bravo 15 A4DDR              | [60eb0d02a7](https://linux-hardware.org/?probe=60eb0d02a7) | Apr 21, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 3442               | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Dell          | Inspiron 5468               | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [92866f8994](https://linux-hardware.org/?probe=92866f8994) | Apr 17, 2021 |
| HP            | Pavilion g6                 | [7a88de99e8](https://linux-hardware.org/?probe=7a88de99e8) | Apr 16, 2021 |
| HP            | Pavilion g6                 | [8f9f4e211d](https://linux-hardware.org/?probe=8f9f4e211d) | Apr 15, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| HP            | Pavilion g6                 | [d3e2f03de0](https://linux-hardware.org/?probe=d3e2f03de0) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| HP            | Pavilion 17                 | [9bd4ef879a](https://linux-hardware.org/?probe=9bd4ef879a) | Apr 12, 2021 |
| Sony          | VPCEJ3S1R                   | [a57c607409](https://linux-hardware.org/?probe=a57c607409) | Apr 12, 2021 |
| Dell          | Inspiron 5721               | [d90f3a34d1](https://linux-hardware.org/?probe=d90f3a34d1) | Apr 08, 2021 |
| Dell          | Inspiron 5721               | [a0bb6867cd](https://linux-hardware.org/?probe=a0bb6867cd) | Apr 07, 2021 |
| Dell          | Latitude E6330              | [46855c6116](https://linux-hardware.org/?probe=46855c6116) | Apr 07, 2021 |
| Notebook      | N650DU                      | [34efc4fdfe](https://linux-hardware.org/?probe=34efc4fdfe) | Apr 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 20HRC... | [354cd6e94e](https://linux-hardware.org/?probe=354cd6e94e) | Apr 02, 2021 |
| Acer          | TravelMate P259-MG          | [9acbd94cd7](https://linux-hardware.org/?probe=9acbd94cd7) | Apr 01, 2021 |
| Dell          | Inspiron 5721               | [b93f919e23](https://linux-hardware.org/?probe=b93f919e23) | Mar 31, 2021 |
| Dell          | Inspiron 5721               | [2e925f1ee2](https://linux-hardware.org/?probe=2e925f1ee2) | Mar 30, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [8d09fd5fad](https://linux-hardware.org/?probe=8d09fd5fad) | Mar 29, 2021 |
| Dell          | Inspiron 5721               | [d22bc80177](https://linux-hardware.org/?probe=d22bc80177) | Mar 29, 2021 |
| Micro Elec... | MG-VCTR002-2060             | [3724755eea](https://linux-hardware.org/?probe=3724755eea) | Mar 28, 2021 |
| HP            | ProBook 4520s               | [7577a208f6](https://linux-hardware.org/?probe=7577a208f6) | Mar 22, 2021 |
| Lenovo        | B50-30 20382                | [2d50a5e736](https://linux-hardware.org/?probe=2d50a5e736) | Mar 21, 2021 |
| Dell          | Inspiron 5548               | [f20eacbf5c](https://linux-hardware.org/?probe=f20eacbf5c) | Mar 18, 2021 |
| Dell          | Inspiron 5548               | [e3d85d4006](https://linux-hardware.org/?probe=e3d85d4006) | Mar 15, 2021 |
| Dell          | Inspiron 5548               | [3c8f0ff2d4](https://linux-hardware.org/?probe=3c8f0ff2d4) | Mar 15, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [bcdd60dc85](https://linux-hardware.org/?probe=bcdd60dc85) | Mar 14, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [bd5d97f7e7](https://linux-hardware.org/?probe=bd5d97f7e7) | Mar 07, 2021 |
| Acer          | Aspire E5-521               | [d2ee782761](https://linux-hardware.org/?probe=d2ee782761) | Mar 07, 2021 |
| ASUSTek       | K53E                        | [f84c0f2b1b](https://linux-hardware.org/?probe=f84c0f2b1b) | Mar 05, 2021 |
| Micro Elec... | MG-VCTR002-2060             | [f86910b3b3](https://linux-hardware.org/?probe=f86910b3b3) | Mar 05, 2021 |
| ASUSTek       | K53E                        | [8a98e99c2f](https://linux-hardware.org/?probe=8a98e99c2f) | Mar 05, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [db2b8a39be](https://linux-hardware.org/?probe=db2b8a39be) | Mar 03, 2021 |
| Lenovo        | ThinkPad T430 2349PS9       | [4f805206d4](https://linux-hardware.org/?probe=4f805206d4) | Mar 03, 2021 |
| Dell          | XPS 13 9310                 | [d8b4e607e1](https://linux-hardware.org/?probe=d8b4e607e1) | Mar 02, 2021 |
| Dell          | XPS 13 9310                 | [eca0e7f55f](https://linux-hardware.org/?probe=eca0e7f55f) | Mar 02, 2021 |
| HP            | Pavilion Notebook           | [88c5aee182](https://linux-hardware.org/?probe=88c5aee182) | Mar 02, 2021 |
| Lenovo        | V570 HuronRiver Platform    | [d93b0955fa](https://linux-hardware.org/?probe=d93b0955fa) | Feb 27, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [744852fa69](https://linux-hardware.org/?probe=744852fa69) | Feb 25, 2021 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | [720734ca06](https://linux-hardware.org/?probe=720734ca06) | Feb 25, 2021 |
| Dell          | Inspiron 5759               | [3710e0320f](https://linux-hardware.org/?probe=3710e0320f) | Feb 24, 2021 |
| HP            | Laptop 15-da0xxx            | [3bb9f3d0f3](https://linux-hardware.org/?probe=3bb9f3d0f3) | Feb 23, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [88bab7f6e7](https://linux-hardware.org/?probe=88bab7f6e7) | Feb 22, 2021 |
| HP            | ENVY Notebook               | [e4cc508565](https://linux-hardware.org/?probe=e4cc508565) | Feb 21, 2021 |
| Lenovo        | B50-30 20382                | [6642872403](https://linux-hardware.org/?probe=6642872403) | Feb 19, 2021 |
| LG Electro... | A410-K.BE43P1               | [da5067a065](https://linux-hardware.org/?probe=da5067a065) | Feb 18, 2021 |
| Dell          | Latitude E6440              | [ce086f8df0](https://linux-hardware.org/?probe=ce086f8df0) | Feb 18, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [77da992403](https://linux-hardware.org/?probe=77da992403) | Feb 14, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [2e19efe5b1](https://linux-hardware.org/?probe=2e19efe5b1) | Feb 12, 2021 |
| Dell          | Inspiron 5759               | [e7c528c9be](https://linux-hardware.org/?probe=e7c528c9be) | Feb 11, 2021 |
| Dell          | XPS 13 9310                 | [97e14d7021](https://linux-hardware.org/?probe=97e14d7021) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | [954514a52a](https://linux-hardware.org/?probe=954514a52a) | Feb 10, 2021 |
| Lenovo        | B50-30 20382                | [67f2a70d2a](https://linux-hardware.org/?probe=67f2a70d2a) | Feb 09, 2021 |
| Dell          | Inspiron 5759               | [cd72d5cd68](https://linux-hardware.org/?probe=cd72d5cd68) | Feb 09, 2021 |
| Dell          | Latitude 7400               | [32c7787bcb](https://linux-hardware.org/?probe=32c7787bcb) | Feb 04, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [9b82b49d40](https://linux-hardware.org/?probe=9b82b49d40) | Feb 04, 2021 |
| Unknown       | Unknown                     | [6acba7c545](https://linux-hardware.org/?probe=6acba7c545) | Feb 03, 2021 |
| Unknown       | Unknown                     | [ad10dd6be0](https://linux-hardware.org/?probe=ad10dd6be0) | Feb 03, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [67cfeeb58a](https://linux-hardware.org/?probe=67cfeeb58a) | Jan 31, 2021 |
| Unknown       | Unknown                     | [ea0d120a2b](https://linux-hardware.org/?probe=ea0d120a2b) | Jan 31, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [288a08d946](https://linux-hardware.org/?probe=288a08d946) | Jan 26, 2021 |
| Positivo      | C14CR21                     | [0807ce46f1](https://linux-hardware.org/?probe=0807ce46f1) | Jan 19, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4bdbb16f3d](https://linux-hardware.org/?probe=4bdbb16f3d) | Jan 17, 2021 |
| Acer          | Aspire 5750Z                | [14ca9bb504](https://linux-hardware.org/?probe=14ca9bb504) | Jan 16, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [286214a4e2](https://linux-hardware.org/?probe=286214a4e2) | Jan 15, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | [1ec8c1ccd1](https://linux-hardware.org/?probe=1ec8c1ccd1) | Jan 13, 2021 |
| Dell          | Vostro 5490                 | [6afcc11fef](https://linux-hardware.org/?probe=6afcc11fef) | Jan 08, 2021 |
| Dell          | Vostro 5490                 | [1708c28c7b](https://linux-hardware.org/?probe=1708c28c7b) | Jan 08, 2021 |
| Dell          | Latitude E6330              | [1d09a49510](https://linux-hardware.org/?probe=1d09a49510) | Jan 04, 2021 |
| Lenovo        | ThinkPad E480 20KN001NMX    | [4f055c0cf5](https://linux-hardware.org/?probe=4f055c0cf5) | Oct 08, 2019 |
| Dell          | Inspiron 11-3168            | [3831423c95](https://linux-hardware.org/?probe=3831423c95) | Jun 30, 2019 |
| Dell          | Inspiron 11-3168            | [4343600da2](https://linux-hardware.org/?probe=4343600da2) | Jun 30, 2019 |
| Dell          | Inspiron 11-3168            | [a1f5874ef6](https://linux-hardware.org/?probe=a1f5874ef6) | Jun 30, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Notebooks | Percent |
|----------------------------|-----------|---------|
| 5.10.0-8-amd64             | 515       | 70.55%  |
| 5.10.0-7-amd64             | 80        | 10.96%  |
| 5.10.0-2-amd64             | 29        | 3.97%   |
| 5.10.0-6-amd64             | 26        | 3.56%   |
| 5.10.0-3-amd64             | 12        | 1.64%   |
| 5.10.0-8-686-pae           | 8         | 1.1%    |
| 5.10.0-5-amd64             | 6         | 0.82%   |
| 5.10.0-4-amd64             | 5         | 0.68%   |
| 5.10.0-1-amd64             | 5         | 0.68%   |
| 5.10.0-8-686               | 4         | 0.55%   |
| 5.12.0-19.3-liquorix-amd64 | 3         | 0.41%   |
| 4.19.0-14-amd64            | 2         | 0.27%   |
| 5.14.6-ndmnet-sid-1        | 1         | 0.14%   |
| 5.14.0-rc3-prygun          | 1         | 0.14%   |
| 5.14.0+                    | 1         | 0.14%   |
| 5.13.8-xanmod1             | 1         | 0.14%   |
| 5.13.8                     | 1         | 0.14%   |
| 5.13.5-xanmod1             | 1         | 0.14%   |
| 5.13.4-e5520               | 1         | 0.14%   |
| 5.13.3                     | 1         | 0.14%   |
| 5.13.15-xanmod1            | 1         | 0.14%   |
| 5.13.0-13.1-liquorix-amd64 | 1         | 0.14%   |
| 5.12.14-amd64-desktop      | 1         | 0.14%   |
| 5.12.10                    | 1         | 0.14%   |
| 5.12.1                     | 1         | 0.14%   |
| 5.12.0-9.2-liquorix-amd64  | 1         | 0.14%   |
| 5.12.0-14.2-liquorix-amd64 | 1         | 0.14%   |
| 5.11.9+                    | 1         | 0.14%   |
| 5.11.22-1-pve              | 1         | 0.14%   |
| 5.11.15-051115-generic     | 1         | 0.14%   |
| 5.11.14                    | 1         | 0.14%   |
| 5.11.0-rc6                 | 1         | 0.14%   |
| 5.11.0-11.1-liquorix-amd64 | 1         | 0.14%   |
| 5.10.40-ismynik            | 1         | 0.14%   |
| 5.10.18-xanmod1            | 1         | 0.14%   |
| 5.10.10-64                 | 1         | 0.14%   |
| 5.10.0-kali3-amd64         | 1         | 0.14%   |
| 5.10.0-io7-amd64           | 1         | 0.14%   |
| 5.10.0-6-rt-amd64          | 1         | 0.14%   |
| 5.10.0-6-686               | 1         | 0.14%   |
| 5.10.0-0.bpo.5-amd64       | 1         | 0.14%   |
| 5.1.12-xanmod8             | 1         | 0.14%   |
| 5.1.0                      | 1         | 0.14%   |
| 4.19.181-z580322           | 1         | 0.14%   |
| 4.19.0-17-686              | 1         | 0.14%   |
| 4.19.0-16-amd64            | 1         | 0.14%   |
| 4.19.0-16-686-pae          | 1         | 0.14%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.10.0   | 676       | 95.35%  |
| 5.12.0   | 4         | 0.56%   |
| 4.19.0   | 4         | 0.56%   |
| 5.14.0   | 2         | 0.28%   |
| 5.13.8   | 2         | 0.28%   |
| 5.11.0   | 2         | 0.28%   |
| 5.14.6   | 1         | 0.14%   |
| 5.13.5   | 1         | 0.14%   |
| 5.13.4   | 1         | 0.14%   |
| 5.13.3   | 1         | 0.14%   |
| 5.13.15  | 1         | 0.14%   |
| 5.13.0   | 1         | 0.14%   |
| 5.12.14  | 1         | 0.14%   |
| 5.12.10  | 1         | 0.14%   |
| 5.12.1   | 1         | 0.14%   |
| 5.11.9   | 1         | 0.14%   |
| 5.11.22  | 1         | 0.14%   |
| 5.11.15  | 1         | 0.14%   |
| 5.11.14  | 1         | 0.14%   |
| 5.10.40  | 1         | 0.14%   |
| 5.10.18  | 1         | 0.14%   |
| 5.10.10  | 1         | 0.14%   |
| 5.1.12   | 1         | 0.14%   |
| 5.1.0    | 1         | 0.14%   |
| 4.19.181 | 1         | 0.14%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.10    | 679       | 95.9%   |
| 5.12    | 7         | 0.99%   |
| 5.13    | 6         | 0.85%   |
| 5.11    | 6         | 0.85%   |
| 4.19    | 5         | 0.71%   |
| 5.14    | 3         | 0.42%   |
| 5.1     | 2         | 0.28%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 691       | 98.01%  |
| i686   | 14        | 1.99%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Unknown          | 292       | 41.13%  |
| GNOME            | 163       | 22.96%  |
| KDE5             | 89        | 12.54%  |
| XFCE             | 56        | 7.89%   |
| MATE             | 23        | 3.24%   |
| KDE              | 16        | 2.25%   |
| i3               | 11        | 1.55%   |
| LXDE             | 10        | 1.41%   |
| Cinnamon         | 10        | 1.41%   |
| X-Cinnamon       | 9         | 1.27%   |
| LXQt             | 8         | 1.13%   |
| lightdm-xsession | 6         | 0.85%   |
| GNOME Flashback  | 5         | 0.7%    |
| GNOME Classic    | 3         | 0.42%   |
| openbox          | 2         | 0.28%   |
| Enlightenment    | 2         | 0.28%   |
| sway             | 1         | 0.14%   |
| ICEWM            | 1         | 0.14%   |
| default          | 1         | 0.14%   |
| Deepin           | 1         | 0.14%   |
| awesome          | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 290       | 40.67%  |
| Unknown | 273       | 38.29%  |
| Wayland | 129       | 18.09%  |
| Tty     | 21        | 2.95%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 361       | 50.77%  |
| GDM     | 146       | 20.53%  |
| SDDM    | 94        | 13.22%  |
| TDM     | 72        | 10.13%  |
| LightDM | 35        | 4.92%   |
| XDM     | 2         | 0.28%   |
| KDM     | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 221       | 31.21%  |
| en_US   | 181       | 25.56%  |
| ru_RU   | 69        | 9.75%   |
| es_ES   | 31        | 4.38%   |
| en_GB   | 30        | 4.24%   |
| fr_FR   | 20        | 2.82%   |
| de_DE   | 19        | 2.68%   |
| pt_BR   | 15        | 2.12%   |
| it_IT   | 12        | 1.69%   |
| pl_PL   | 10        | 1.41%   |
| en_IN   | 7         | 0.99%   |
| zh_CN   | 5         | 0.71%   |
| tr_TR   | 5         | 0.71%   |
| sv_SE   | 5         | 0.71%   |
| en_CA   | 5         | 0.71%   |
| C       | 5         | 0.71%   |
| es_MX   | 4         | 0.56%   |
| en_AU   | 4         | 0.56%   |
| de_CH   | 4         | 0.56%   |
| uk_UA   | 3         | 0.42%   |
| pt_PT   | 3         | 0.42%   |
| nn_NO   | 3         | 0.42%   |
| ja_JP   | 3         | 0.42%   |
| fi_FI   | 3         | 0.42%   |
| en_IE   | 3         | 0.42%   |
| de_AT   | 3         | 0.42%   |
| cs_CZ   | 3         | 0.42%   |
| nl_NL   | 2         | 0.28%   |
| es_CO   | 2         | 0.28%   |
| es_AR   | 2         | 0.28%   |
| en_ZA   | 2         | 0.28%   |
| en_SG   | 2         | 0.28%   |
| zh_TW   | 1         | 0.14%   |
| sk_SK   | 1         | 0.14%   |
| ru_UA   | 1         | 0.14%   |
| ro_RO   | 1         | 0.14%   |
| nl_BE   | 1         | 0.14%   |
| nb_NO   | 1         | 0.14%   |
| hu_HU   | 1         | 0.14%   |
| hr_HR   | 1         | 0.14%   |
| gl_ES   | 1         | 0.14%   |
| et_EE   | 1         | 0.14%   |
| es_UY   | 1         | 0.14%   |
| es_GT   | 1         | 0.14%   |
| es_EC   | 1         | 0.14%   |
| es_CL   | 1         | 0.14%   |
| eo      | 1         | 0.14%   |
| en_ZM   | 1         | 0.14%   |
| en_SI   | 1         | 0.14%   |
| en_NZ   | 1         | 0.14%   |
| en_HK   | 1         | 0.14%   |
| en_DK   | 1         | 0.14%   |
| ca_ES   | 1         | 0.14%   |
| bg_BG   | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 499       | 70.38%  |
| BIOS | 210       | 29.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 381       | 53.97%  |
| Overlay | 289       | 40.93%  |
| Btrfs   | 24        | 3.4%    |
| Xfs     | 5         | 0.71%   |
| Zfs     | 2         | 0.28%   |
| Unknown | 2         | 0.28%   |
| Tmpfs   | 1         | 0.14%   |
| Rootfs  | 1         | 0.14%   |
| Ext3    | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 517       | 73.13%  |
| MBR     | 117       | 16.55%  |
| Unknown | 73        | 10.33%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 659       | 93.34%  |
| Yes       | 47        | 6.66%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 544       | 76.94%  |
| Yes       | 163       | 23.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo               | 177       | 25.11%  |
| Apple                | 155       | 21.99%  |
| Hewlett-Packard      | 79        | 11.21%  |
| Dell                 | 77        | 10.92%  |
| Google               | 49        | 6.95%   |
| Acer                 | 47        | 6.67%   |
| ASUSTek Computer     | 46        | 6.52%   |
| MSI                  | 12        | 1.7%    |
| Toshiba              | 6         | 0.85%   |
| HUAWEI               | 6         | 0.85%   |
| Sony                 | 5         | 0.71%   |
| Timi                 | 4         | 0.57%   |
| Samsung Electronics  | 4         | 0.57%   |
| Notebook             | 4         | 0.57%   |
| Clevo                | 4         | 0.57%   |
| Gigabyte Technology  | 3         | 0.43%   |
| Fujitsu              | 3         | 0.43%   |
| Aquarius             | 3         | 0.43%   |
| SLIMBOOK             | 2         | 0.28%   |
| PC Specialist        | 2         | 0.28%   |
| YJKC                 | 1         | 0.14%   |
| UNOWHY               | 1         | 0.14%   |
| TUXEDO               | 1         | 0.14%   |
| Schenker             | 1         | 0.14%   |
| Quanta               | 1         | 0.14%   |
| Positivo             | 1         | 0.14%   |
| Pegatron             | 1         | 0.14%   |
| Panasonic            | 1         | 0.14%   |
| Packard Bell         | 1         | 0.14%   |
| Monster              | 1         | 0.14%   |
| Micro Electronics    | 1         | 0.14%   |
| LG Electronics       | 1         | 0.14%   |
| Itautec              | 1         | 0.14%   |
| Intel Client Systems | 1         | 0.14%   |
| Fujitsu Siemens      | 1         | 0.14%   |
| Casper               | 1         | 0.14%   |
| Unknown              | 1         | 0.14%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Apple MacBookAir7,1                     | 75        | 10.64%  |
| Apple MacBookAir7,2                     | 66        | 9.36%   |
| Google Enguarde                         | 47        | 6.67%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US   | 15        | 2.13%   |
| Acer Aspire A315-23                     | 15        | 2.13%   |
| Dell Latitude 7480                      | 5         | 0.71%   |
| Dell XPS 13 9310                        | 4         | 0.57%   |
| Lenovo ThinkPad E475 20H40006US         | 3         | 0.43%   |
| Lenovo IdeaPad L340-15API 81LW          | 3         | 0.43%   |
| HUAWEI NBLK-WAX9X                       | 3         | 0.43%   |
| HP Pavilion Gaming Laptop 15-ec2xxx     | 3         | 0.43%   |
| HP EliteBook 8460p                      | 3         | 0.43%   |
| Aquarius NS585                          | 3         | 0.43%   |
| Timi TM1613                             | 2         | 0.28%   |
| MSI Bravo 15 A4DDR                      | 2         | 0.28%   |
| Lenovo V510-15IKB 80WQ                  | 2         | 0.28%   |
| Lenovo ThinkPad T490 20N2CTO1WW         | 2         | 0.28%   |
| Lenovo ThinkBook 14 G2 ARE 20VF         | 2         | 0.28%   |
| Lenovo IdeaPad 700-15ISK 80RU           | 2         | 0.28%   |
| Lenovo IdeaPad 330-15IKB 81DE           | 2         | 0.28%   |
| Lenovo IdeaPad 330-15ARR 81D2           | 2         | 0.28%   |
| Lenovo G50-80 80E5                      | 2         | 0.28%   |
| HP ProBook 4530s                        | 2         | 0.28%   |
| HP Pavilion g6                          | 2         | 0.28%   |
| HP Laptop 15s-fq2xxx                    | 2         | 0.28%   |
| HP Laptop 15s-eq1xxx                    | 2         | 0.28%   |
| HP Compaq nx6125 (PZ849UA#ABA)          | 2         | 0.28%   |
| HP Compaq nx6110 (PZ065UA#ABA)          | 2         | 0.28%   |
| Dell XPS 13 9370                        | 2         | 0.28%   |
| Dell XPS 13 7390                        | 2         | 0.28%   |
| Dell Vostro 5490                        | 2         | 0.28%   |
| Dell Vostro 5471                        | 2         | 0.28%   |
| Dell Precision 3540                     | 2         | 0.28%   |
| Dell Latitude E7470                     | 2         | 0.28%   |
| Dell Latitude E7240                     | 2         | 0.28%   |
| Dell Latitude E6330                     | 2         | 0.28%   |
| Dell Inspiron 5570                      | 2         | 0.28%   |
| Dell Inspiron 3793                      | 2         | 0.28%   |
| Dell Inspiron 15 7000 Gaming            | 2         | 0.28%   |
| Dell G3 3590                            | 2         | 0.28%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA | 2         | 0.28%   |
| ASUS TUF GAMING FX504GD_FX80GD          | 2         | 0.28%   |
| Apple MacBook7,1                        | 2         | 0.28%   |
| Apple MacBook5,2                        | 2         | 0.28%   |
| Acer Aspire 5560                        | 2         | 0.28%   |
| Acer Aspire 5315                        | 2         | 0.28%   |
| YJKC vBOOK Plus                         | 1         | 0.14%   |
| UNOWHY Y13G002S4EI                      | 1         | 0.14%   |
| TUXEDO Pulse 15 Gen1                    | 1         | 0.14%   |
| Toshiba Satellite U800W                 | 1         | 0.14%   |
| Toshiba Satellite S55-A                 | 1         | 0.14%   |
| Toshiba Satellite C655D                 | 1         | 0.14%   |
| Toshiba Satellite C55-B                 | 1         | 0.14%   |
| Toshiba Satellite C45-A                 | 1         | 0.14%   |
| Toshiba PORTEGE R830                    | 1         | 0.14%   |
| Timi TM1801                             | 1         | 0.14%   |
| Timi TM1612                             | 1         | 0.14%   |
| Sony VPCF21AFX                          | 1         | 0.14%   |
| Sony VPCF115FM                          | 1         | 0.14%   |
| Sony VPCEJ3S1R                          | 1         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Apple MacBookAir7   | 141       | 20%     |
| Lenovo ThinkPad     | 125       | 17.73%  |
| Google Enguarde     | 47        | 6.67%   |
| Acer Aspire         | 36        | 5.11%   |
| Lenovo IdeaPad      | 30        | 4.26%   |
| Dell Inspiron       | 28        | 3.97%   |
| Dell Latitude       | 19        | 2.7%    |
| HP ProBook          | 15        | 2.13%   |
| HP Pavilion         | 13        | 1.84%   |
| Dell XPS            | 13        | 1.84%   |
| HP EliteBook        | 12        | 1.7%    |
| HP Laptop           | 10        | 1.42%   |
| HP Compaq           | 9         | 1.28%   |
| Dell Precision      | 7         | 0.99%   |
| Toshiba Satellite   | 5         | 0.71%   |
| Dell Vostro         | 5         | 0.71%   |
| ASUS ZenBook        | 5         | 0.71%   |
| ASUS VivoBook       | 5         | 0.71%   |
| Lenovo ThinkBook    | 4         | 0.57%   |
| ASUS TUF            | 4         | 0.57%   |
| ASUS ROG            | 4         | 0.57%   |
| Acer TravelMate     | 4         | 0.57%   |
| HUAWEI NBLK-WAX9X   | 3         | 0.43%   |
| HP 250              | 3         | 0.43%   |
| Fujitsu LIFEBOOK    | 3         | 0.43%   |
| Dell G3             | 3         | 0.43%   |
| ASUS ASUS           | 3         | 0.43%   |
| Aquarius NS585      | 3         | 0.43%   |
| Acer Swift          | 3         | 0.43%   |
| Timi TM1613         | 2         | 0.28%   |
| MSI Bravo           | 2         | 0.28%   |
| Lenovo V510-15IKB   | 2         | 0.28%   |
| Lenovo G50-80       | 2         | 0.28%   |
| HP ZBook            | 2         | 0.28%   |
| HP Presario         | 2         | 0.28%   |
| HP OMEN             | 2         | 0.28%   |
| HP ENVY             | 2         | 0.28%   |
| Gigabyte AERO       | 2         | 0.28%   |
| Apple MacBookPro11  | 2         | 0.28%   |
| Apple MacBook7      | 2         | 0.28%   |
| Apple MacBook5      | 2         | 0.28%   |
| Acer Nitro          | 2         | 0.28%   |
| YJKC vBOOK          | 1         | 0.14%   |
| UNOWHY Y13G002S4EI  | 1         | 0.14%   |
| TUXEDO Pulse        | 1         | 0.14%   |
| Toshiba PORTEGE     | 1         | 0.14%   |
| Timi TM1801         | 1         | 0.14%   |
| Timi TM1612         | 1         | 0.14%   |
| Sony VPCF21AFX      | 1         | 0.14%   |
| Sony VPCF115FM      | 1         | 0.14%   |
| Sony VPCEJ3S1R      | 1         | 0.14%   |
| Sony VGN-CR21Z      | 1         | 0.14%   |
| Sony SVE1512G1RB    | 1         | 0.14%   |
| SLIMBOOK TITAN      | 1         | 0.14%   |
| SLIMBOOK PROX14-AMD | 1         | 0.14%   |
| Schenker XMG        | 1         | 0.14%   |
| Samsung NC10        | 1         | 0.14%   |
| Samsung 900X3C      | 1         | 0.14%   |
| Samsung 370E4K      | 1         | 0.14%   |
| Samsung 300E5M      | 1         | 0.14%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2020 | 194       | 27.52%  |
| 2021 | 159       | 22.55%  |
| 2019 | 120       | 17.02%  |
| 2018 | 38        | 5.39%   |
| 2013 | 25        | 3.55%   |
| 2011 | 25        | 3.55%   |
| 2012 | 24        | 3.4%    |
| 2016 | 22        | 3.12%   |
| 2014 | 18        | 2.55%   |
| 2008 | 18        | 2.55%   |
| 2015 | 16        | 2.27%   |
| 2009 | 14        | 1.99%   |
| 2017 | 13        | 1.84%   |
| 2010 | 8         | 1.13%   |
| 2007 | 3         | 0.43%   |
| 2006 | 3         | 0.43%   |
| 2005 | 3         | 0.43%   |
| 2004 | 2         | 0.28%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 705       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 652       | 92.22%  |
| Enabled  | 55        | 7.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 656       | 93.05%  |
| Yes  | 49        | 6.95%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 241       | 34.14%  |
| 3.01-4.0    | 187       | 26.49%  |
| 16.01-24.0  | 117       | 16.57%  |
| 8.01-16.0   | 84        | 11.9%   |
| 32.01-64.0  | 29        | 4.11%   |
| 1.01-2.0    | 22        | 3.12%   |
| 2.01-3.0    | 8         | 1.13%   |
| 64.01-256.0 | 6         | 0.85%   |
| 0.51-1.0    | 6         | 0.85%   |
| 0.01-0.5    | 4         | 0.57%   |
| 24.01-32.0  | 2         | 0.28%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 338       | 46.75%  |
| 2.01-3.0   | 129       | 17.84%  |
| 0.51-1.0   | 79        | 10.93%  |
| 4.01-8.0   | 75        | 10.37%  |
| 3.01-4.0   | 52        | 7.19%   |
| 8.01-16.0  | 28        | 3.87%   |
| 0.01-0.5   | 20        | 2.77%   |
| 32.01-64.0 | 1         | 0.14%   |
| 16.01-24.0 | 1         | 0.14%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 569       | 80.25%  |
| 2      | 125       | 17.63%  |
| 3      | 9         | 1.27%   |
| 4      | 4         | 0.56%   |
| 0      | 2         | 0.28%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 554       | 78.58%  |
| Yes       | 151       | 21.42%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 445       | 63.12%  |
| No        | 260       | 36.88%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 689       | 97.73%  |
| No        | 16        | 2.27%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 606       | 85.71%  |
| No        | 101       | 14.29%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 290       | 41.02%  |
| Russia       | 68        | 9.62%   |
| Spain        | 38        | 5.37%   |
| Germany      | 32        | 4.53%   |
| France       | 32        | 4.53%   |
| Brazil       | 19        | 2.69%   |
| UK           | 17        | 2.4%    |
| Poland       | 17        | 2.4%    |
| Ukraine      | 14        | 1.98%   |
| Italy        | 9         | 1.27%   |
| Switzerland  | 8         | 1.13%   |
| Netherlands  | 8         | 1.13%   |
| India        | 8         | 1.13%   |
| China        | 8         | 1.13%   |
| Canada       | 8         | 1.13%   |
| Turkey       | 7         | 0.99%   |
| Sweden       | 7         | 0.99%   |
| Portugal     | 7         | 0.99%   |
| Norway       | 5         | 0.71%   |
| Mexico       | 5         | 0.71%   |
| Greece       | 5         | 0.71%   |
| Czechia      | 5         | 0.71%   |
| Austria      | 5         | 0.71%   |
| Australia    | 5         | 0.71%   |
| Thailand     | 4         | 0.57%   |
| Romania      | 4         | 0.57%   |
| Kazakhstan   | 4         | 0.57%   |
| Finland      | 4         | 0.57%   |
| Belarus      | 4         | 0.57%   |
| Argentina    | 4         | 0.57%   |
| Japan        | 3         | 0.42%   |
| Ireland      | 3         | 0.42%   |
| Indonesia    | 3         | 0.42%   |
| Ecuador      | 3         | 0.42%   |
| Belgium      | 3         | 0.42%   |
| South Africa | 2         | 0.28%   |
| Slovenia     | 2         | 0.28%   |
| Philippines  | 2         | 0.28%   |
| Guatemala    | 2         | 0.28%   |
| Denmark      | 2         | 0.28%   |
| Croatia      | 2         | 0.28%   |
| Colombia     | 2         | 0.28%   |
| Chile        | 2         | 0.28%   |
| Bulgaria     | 2         | 0.28%   |
| Zambia       | 1         | 0.14%   |
| Vietnam      | 1         | 0.14%   |
| Uruguay      | 1         | 0.14%   |
| Taiwan       | 1         | 0.14%   |
| South Sudan  | 1         | 0.14%   |
| Slovakia     | 1         | 0.14%   |
| Singapore    | 1         | 0.14%   |
| Pakistan     | 1         | 0.14%   |
| New Zealand  | 1         | 0.14%   |
| Morocco      | 1         | 0.14%   |
| Mongolia     | 1         | 0.14%   |
| Moldova      | 1         | 0.14%   |
| Malaysia     | 1         | 0.14%   |
| Lebanon      | 1         | 0.14%   |
| Latvia       | 1         | 0.14%   |
| Israel       | 1         | 0.14%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Portland               | 224       | 31.28%  |
| Voronezh               | 40        | 5.59%   |
| St Petersburg          | 14        | 1.96%   |
| M??laga                | 14        | 1.96%   |
| Paris                  | 9         | 1.26%   |
| Hampden                | 7         | 0.98%   |
| Berlin                 | 5         | 0.7%    |
| Vienna                 | 4         | 0.56%   |
| S??o Paulo             | 4         | 0.56%   |
| Madrid                 | 4         | 0.56%   |
| Lyon                   | 4         | 0.56%   |
| London                 | 4         | 0.56%   |
| Bengaluru              | 4         | 0.56%   |
| Bangkok                | 4         | 0.56%   |
| Zurich                 | 3         | 0.42%   |
| Sunnyvale              | 3         | 0.42%   |
| Sevastopol             | 3         | 0.42%   |
| Milan                  | 3         | 0.42%   |
| Mesa                   | 3         | 0.42%   |
| Manchester             | 3         | 0.42%   |
| Iasi                   | 3         | 0.42%   |
| Helsinki               | 3         | 0.42%   |
| Halstead               | 3         | 0.42%   |
| Frankfort              | 3         | 0.42%   |
| Dublin                 | 3         | 0.42%   |
| Athens                 | 3         | 0.42%   |
| Ankara                 | 3         | 0.42%   |
| Yevpatoriya            | 2         | 0.28%   |
| Wroclaw                | 2         | 0.28%   |
| Warsaw                 | 2         | 0.28%   |
| Valencia               | 2         | 0.28%   |
| Tyreso Strand          | 2         | 0.28%   |
| Toronto                | 2         | 0.28%   |
| Thermopolis            | 2         | 0.28%   |
| Ternopil               | 2         | 0.28%   |
| Sydney                 | 2         | 0.28%   |
| San Miguel de Tucum??n | 2         | 0.28%   |
| Roseville              | 2         | 0.28%   |
| Rio de Janeiro         | 2         | 0.28%   |
| Plano                  | 2         | 0.28%   |
| Perm                   | 2         | 0.28%   |
| Offenburg              | 2         | 0.28%   |
| Moscow                 | 2         | 0.28%   |
| Molde                  | 2         | 0.28%   |
| Loziska                | 2         | 0.28%   |
| Kyiv                   | 2         | 0.28%   |
| Krakow                 | 2         | 0.28%   |
| Katowice               | 2         | 0.28%   |
| Kalamazoo              | 2         | 0.28%   |
| Istanbul               | 2         | 0.28%   |
| Hamburg                | 2         | 0.28%   |
| Halifax                | 2         | 0.28%   |
| Guatemala City         | 2         | 0.28%   |
| Gorinchem              | 2         | 0.28%   |
| Gloucester             | 2         | 0.28%   |
| Fryazino               | 2         | 0.28%   |
| Denpasar               | 2         | 0.28%   |
| Chelyabinsk            | 2         | 0.28%   |
| Amsterdam              | 2         | 0.28%   |
| Ajdov????ina           | 2         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Apple                     | 146       | 151    | 17.42%  |
| Samsung Electronics       | 129       | 147    | 15.39%  |
| WDC                       | 81        | 95     | 9.67%   |
| Unknown                   | 69        | 85     | 8.23%   |
| Seagate                   | 62        | 72     | 7.4%    |
| Kingston                  | 45        | 50     | 5.37%   |
| Toshiba                   | 41        | 42     | 4.89%   |
| SanDisk                   | 27        | 29     | 3.22%   |
| Crucial                   | 27        | 30     | 3.22%   |
| SK Hynix                  | 22        | 25     | 2.63%   |
| Intel                     | 21        | 21     | 2.51%   |
| Hitachi                   | 18        | 18     | 2.15%   |
| Micron Technology         | 15        | 15     | 1.79%   |
| A-DATA Technology         | 15        | 18     | 1.79%   |
| SABRENT                   | 14        | 14     | 1.67%   |
| HGST                      | 13        | 14     | 1.55%   |
| China                     | 8         | 8      | 0.95%   |
| Fujitsu                   | 7         | 8      | 0.84%   |
| Transcend                 | 6         | 6      | 0.72%   |
| LITEON                    | 6         | 6      | 0.72%   |
| KIOXIA                    | 6         | 7      | 0.72%   |
| Union Memory              | 4         | 4      | 0.48%   |
| Silicon Motion            | 4         | 5      | 0.48%   |
| Lenovo                    | 4         | 4      | 0.48%   |
| LITEONIT                  | 3         | 3      | 0.36%   |
| Lexar                     | 3         | 4      | 0.36%   |
| JMicron                   | 3         | 3      | 0.36%   |
| Intenso                   | 3         | 3      | 0.36%   |
| ZTC                       | 2         | 4      | 0.24%   |
| XPG                       | 2         | 2      | 0.24%   |
| Team                      | 2         | 2      | 0.24%   |
| Solid State Storage       | 2         | 2      | 0.24%   |
| PNY                       | 2         | 2      | 0.24%   |
| Phison                    | 2         | 5      | 0.24%   |
| Patriot                   | 2         | 2      | 0.24%   |
| Mass                      | 2         | 2      | 0.24%   |
| Corsair                   | 2         | 2      | 0.24%   |
| Apacer                    | 2         | 2      | 0.24%   |
| USB3.0                    | 1         | 1      | 0.12%   |
| SPCC                      | 1         | 1      | 0.12%   |
| SILICONMOTION             | 1         | 1      | 0.12%   |
| RDM-II                    | 1         | 1      | 0.12%   |
| PLEXTOR                   | 1         | 1      | 0.12%   |
| Phison Electronics        | 1         | 1      | 0.12%   |
| MyDigitalSSD              | 1         | 1      | 0.12%   |
| Micron/Crucial Technology | 1         | 1      | 0.12%   |
| MAXTOR                    | 1         | 3      | 0.12%   |
| LDLC                      | 1         | 1      | 0.12%   |
| KIOXIA-EXCERIA            | 1         | 1      | 0.12%   |
| GOODRAM                   | 1         | 1      | 0.12%   |
| FORESEE                   | 1         | 1      | 0.12%   |
| BIWIN                     | 1         | 1      | 0.12%   |
| ASUS-PHISON               | 1         | 1      | 0.12%   |
| AMD                       | 1         | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Apple SSD AP0128H 121GB                 | 75        | 8.72%   |
| Apple SSD SM0128G 121GB                 | 65        | 7.56%   |
| Unknown AGND3R  16GB                    | 25        | 2.91%   |
| Seagate ST1000LM035-1RK172 1TB          | 21        | 2.44%   |
| Unknown HAG2e  16GB                     | 19        | 2.21%   |
| SABRENT Disk 1TB                        | 14        | 1.63%   |
| Toshiba MQ04ABF100 1TB                  | 9         | 1.05%   |
| SanDisk SD8SN8U128G1001 128GB SSD       | 8         | 0.93%   |
| Samsung MZNTY128HDHP-000L1 128GB SSD    | 8         | 0.93%   |
| Kingston SA400S37120G 120GB SSD         | 7         | 0.81%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 6         | 0.7%    |
| Samsung SSD 870 EVO 500GB               | 6         | 0.7%    |
| Samsung SSD 860 EVO 500GB               | 6         | 0.7%    |
| HGST HTS721010A9E630 1TB                | 6         | 0.7%    |
| Samsung SSD 970 EVO Plus 500GB          | 5         | 0.58%   |
| Samsung SSD 970 EVO Plus 1TB            | 5         | 0.58%   |
| Kingston SA400S37240G 240GB SSD         | 5         | 0.58%   |
| Crucial CT500MX500SSD1 500GB            | 5         | 0.58%   |
| WDC WD10SPZX-24Z10 1TB                  | 4         | 0.47%   |
| Samsung SSD 860 EVO 250GB               | 4         | 0.47%   |
| Samsung SSD 860 EVO 1TB                 | 4         | 0.47%   |
| Samsung SSD 850 PRO 1TB                 | 4         | 0.47%   |
| Samsung SSD 850 EVO 500GB               | 4         | 0.47%   |
| Kingston SV300S37A120G 120GB SSD        | 4         | 0.47%   |
| Kingston SA400S37480G 480GB SSD         | 4         | 0.47%   |
| WDC WD10SPZX-60Z10T0 1TB                | 3         | 0.35%   |
| WDC WD10SPZX-21Z10T0 1TB                | 3         | 0.35%   |
| WDC WD10JPVX-22JC3T0 1TB                | 3         | 0.35%   |
| Unknown SDW16G  16GB                    | 3         | 0.35%   |
| Unknown DA4064  64GB                    | 3         | 0.35%   |
| Toshiba MQ04ABD200 2TB                  | 3         | 0.35%   |
| Seagate ST9320325AS 320GB               | 3         | 0.35%   |
| Seagate ST500LT012-9WS142 500GB         | 3         | 0.35%   |
| Seagate ST2000LX001-1RG174 2TB          | 3         | 0.35%   |
| Samsung SSD 980 1TB                     | 3         | 0.35%   |
| Samsung SSD 970 EVO 1TB                 | 3         | 0.35%   |
| Samsung SSD 860 EVO M.2 1TB             | 3         | 0.35%   |
| Samsung SSD 850 EVO 250GB               | 3         | 0.35%   |
| Samsung MZALQ256HAJD-000L1 256GB        | 3         | 0.35%   |
| Lexar 512GB SSD                         | 3         | 0.35%   |
| Intel SSDPEKNW512G8 512GB               | 3         | 0.35%   |
| Hitachi HTS543216L9A300 160GB           | 3         | 0.35%   |
| HGST HTS725050A7E630 500GB              | 3         | 0.35%   |
| Crucial CT250MX500SSD1 250GB            | 3         | 0.35%   |
| Crucial CT1000P1SSD8 1TB                | 3         | 0.35%   |
| Crucial CT1000MX500SSD1 1TB             | 3         | 0.35%   |
| A-DATA SU800 512GB SSD                  | 3         | 0.35%   |
| ZTC SM201-512G                          | 2         | 0.23%   |
| XPG NVMe SSD Drive 1024GB               | 2         | 0.23%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 2         | 0.23%   |
| WDC WD7500BPVX-22JC3T0 752GB            | 2         | 0.23%   |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 0.23%   |
| WDC WD50 00LPCX-24VHA 500GB             | 2         | 0.23%   |
| WDC PC SN730 SDBPNTY-512G-1027 512GB    | 2         | 0.23%   |
| WDC PC SN730 SDBPNTY-512G-1006 512GB    | 2         | 0.23%   |
| WDC PC SN730 SDBPNTY-1T00-1006 1TB      | 2         | 0.23%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB    | 2         | 0.23%   |
| WDC PC SN530 NVMe 256GB                 | 2         | 0.23%   |
| Unknown SD32G  32GB                     | 2         | 0.23%   |
| Union Memory UMIS RPJTJ256MEE1OWX 256GB | 2         | 0.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 58        | 68     | 33.92%  |
| WDC                 | 46        | 50     | 26.9%   |
| Toshiba             | 23        | 23     | 13.45%  |
| Hitachi             | 18        | 18     | 10.53%  |
| HGST                | 13        | 14     | 7.6%    |
| Fujitsu             | 7         | 8      | 4.09%   |
| Samsung Electronics | 3         | 3      | 1.75%   |
| USB3.0              | 1         | 1      | 0.58%   |
| Unknown             | 1         | 1      | 0.58%   |
| SILICONMOTION       | 1         | 1      | 0.58%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 76        | 86     | 23.17%  |
| Apple               | 70        | 70     | 21.34%  |
| Kingston            | 35        | 40     | 10.67%  |
| SanDisk             | 21        | 23     | 6.4%    |
| Crucial             | 20        | 23     | 6.1%    |
| SABRENT             | 14        | 14     | 4.27%   |
| WDC                 | 9         | 12     | 2.74%   |
| Intel               | 9         | 9      | 2.74%   |
| China               | 8         | 8      | 2.44%   |
| A-DATA Technology   | 7         | 7      | 2.13%   |
| Transcend           | 6         | 6      | 1.83%   |
| SK Hynix            | 5         | 6      | 1.52%   |
| Micron Technology   | 5         | 5      | 1.52%   |
| LITEON              | 5         | 5      | 1.52%   |
| Toshiba             | 4         | 4      | 1.22%   |
| LITEONIT            | 3         | 3      | 0.91%   |
| Lexar               | 3         | 4      | 0.91%   |
| Intenso             | 3         | 3      | 0.91%   |
| ZTC                 | 2         | 4      | 0.61%   |
| Team                | 2         | 2      | 0.61%   |
| Seagate             | 2         | 2      | 0.61%   |
| PNY                 | 2         | 2      | 0.61%   |
| Patriot             | 2         | 2      | 0.61%   |
| Apacer              | 2         | 2      | 0.61%   |
| Unknown             | 1         | 1      | 0.3%    |
| Union Memory        | 1         | 1      | 0.3%    |
| SPCC                | 1         | 1      | 0.3%    |
| RDM-II              | 1         | 1      | 0.3%    |
| PLEXTOR             | 1         | 1      | 0.3%    |
| MyDigitalSSD        | 1         | 1      | 0.3%    |
| MAXTOR              | 1         | 3      | 0.3%    |
| LDLC                | 1         | 1      | 0.3%    |
| GOODRAM             | 1         | 1      | 0.3%    |
| FORESEE             | 1         | 1      | 0.3%    |
| Corsair             | 1         | 1      | 0.3%    |
| ASUS-PHISON         | 1         | 1      | 0.3%    |
| AMD                 | 1         | 2      | 0.3%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 309       | 358    | 38.15%  |
| NVMe    | 260       | 298    | 32.1%   |
| HDD     | 169       | 187    | 20.86%  |
| MMC     | 67        | 83     | 8.27%   |
| Unknown | 5         | 5      | 0.62%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 425       | 515    | 54.42%  |
| NVMe | 258       | 296    | 33.03%  |
| MMC  | 67        | 83     | 8.58%   |
| SAS  | 31        | 37     | 3.97%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 326       | 374    | 68.06%  |
| 0.51-1.0   | 138       | 155    | 28.81%  |
| 1.01-2.0   | 10        | 11     | 2.09%   |
| 3.01-4.0   | 2         | 2      | 0.42%   |
| 4.01-10.0  | 2         | 2      | 0.42%   |
| 2.01-3.0   | 1         | 1      | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 314       | 44.04%  |
| 251-500        | 114       | 15.99%  |
| 1-20           | 76        | 10.66%  |
| 501-1000       | 62        | 8.7%    |
| Unknown        | 54        | 7.57%   |
| 1001-2000      | 39        | 5.47%   |
| 51-100         | 25        | 3.51%   |
| 21-50          | 14        | 1.96%   |
| More than 3000 | 11        | 1.54%   |
| 2001-3000      | 4         | 0.56%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 369       | 51.25%  |
| 101-250        | 74        | 10.28%  |
| 21-50          | 70        | 9.72%   |
| 51-100         | 64        | 8.89%   |
| Unknown        | 54        | 7.5%    |
| 251-500        | 43        | 5.97%   |
| 501-1000       | 28        | 3.89%   |
| 1001-2000      | 11        | 1.53%   |
| 0              | 4         | 0.56%   |
| More than 3000 | 2         | 0.28%   |
| 2001-3000      | 1         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 2      | 3.7%    |
| Seagate ST500LT012-9WS142 500GB                | 2         | 2      | 3.7%    |
| WDC WD7500BPVX-22JC3T0 752GB                   | 1         | 1      | 1.85%   |
| WDC WD7500BPVT-80HXZT3 752GB                   | 1         | 1      | 1.85%   |
| WDC WD10SPZX-24Z10 1TB                         | 1         | 1      | 1.85%   |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 1.85%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 1.85%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 1.85%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 1.85%   |
| Toshiba MQ01ABD050 500GB                       | 1         | 1      | 1.85%   |
| SK Hynix SH920 mSATA 128GB SSD                 | 1         | 1      | 1.85%   |
| SK Hynix HFS256G39TND-N210A 256GB SSD          | 1         | 1      | 1.85%   |
| Seagate ST960822A 64GB                         | 1         | 1      | 1.85%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 1.85%   |
| Seagate ST9160310AS 160GB                      | 1         | 1      | 1.85%   |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 1.85%   |
| Seagate ST500LM000-SSHD-8GB                    | 1         | 1      | 1.85%   |
| Seagate ST2000LX001-1RG174 2TB                 | 1         | 1      | 1.85%   |
| Seagate ST1000LX015-1U7172 1TB                 | 1         | 1      | 1.85%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 1.85%   |
| SanDisk SD7SB3Q128G1002 128GB SSD              | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 870 EVO 500GB          | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 850 EVO 1TB            | 1         | 1      | 1.85%   |
| Samsung Electronics SSD 840 PRO Series 256GB   | 1         | 2      | 1.85%   |
| Samsung Electronics HM321HI 320GB              | 1         | 1      | 1.85%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.85%   |
| Micron Technology 1100_MTFDDAK256TBN 256GB SSD | 1         | 1      | 1.85%   |
| LITEONIT LMT-64M6M-HP 64GB SSD                 | 1         | 1      | 1.85%   |
| LITEON IT SCS-256L9S 256GB SSD                 | 1         | 1      | 1.85%   |
| Kingston SV300S37A120G 120GB SSD               | 1         | 1      | 1.85%   |
| Kingston SA400S37120G 120GB SSD                | 1         | 1      | 1.85%   |
| Intel SSDSC2KW120H6 120GB                      | 1         | 1      | 1.85%   |
| Intel SSDSC2BF180A4H 180GB                     | 1         | 1      | 1.85%   |
| Intel SSDSA2M160G2HP 160GB                     | 1         | 1      | 1.85%   |
| Intel SSDPEKKF256G7H 256GB                     | 1         | 1      | 1.85%   |
| Hitachi HTS725050A9A364 500GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS545050A7E380 500GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS543225L9A300 250GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS543212L9A300 120GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS542516K9SA00 160GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS541075A9E680 752GB                  | 1         | 1      | 1.85%   |
| Hitachi HTS541060G9AT00 64GB                   | 1         | 1      | 1.85%   |
| Hitachi HTS541040G9AT00 37GB                   | 1         | 1      | 1.85%   |
| HGST HTS725050A7E630 500GB                     | 1         | 1      | 1.85%   |
| HGST HTS545050A7 500GB                         | 1         | 1      | 1.85%   |
| HGST HTS541010A9E680 1TB                       | 1         | 1      | 1.85%   |
| Fujitsu MHZ2320BH G2 320GB                     | 1         | 1      | 1.85%   |
| Crucial CT128MX100SSD1 128GB                   | 1         | 1      | 1.85%   |
| A-DATA Technology SU630 480GB SSD              | 1         | 1      | 1.85%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 11        | 11     | 20.37%  |
| Seagate             | 10        | 10     | 18.52%  |
| WDC                 | 6         | 6      | 11.11%  |
| Toshiba             | 4         | 4      | 7.41%   |
| Samsung Electronics | 4         | 5      | 7.41%   |
| Intel               | 4         | 4      | 7.41%   |
| HGST                | 3         | 3      | 5.56%   |
| SK Hynix            | 2         | 2      | 3.7%    |
| Micron Technology   | 2         | 2      | 3.7%    |
| Kingston            | 2         | 2      | 3.7%    |
| SanDisk             | 1         | 1      | 1.85%   |
| LITEONIT            | 1         | 1      | 1.85%   |
| LITEON              | 1         | 1      | 1.85%   |
| Fujitsu             | 1         | 1      | 1.85%   |
| Crucial             | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Hitachi             | 11        | 11     | 30.56%  |
| Seagate             | 10        | 10     | 27.78%  |
| WDC                 | 6         | 6      | 16.67%  |
| Toshiba             | 4         | 4      | 11.11%  |
| HGST                | 3         | 3      | 8.33%   |
| Samsung Electronics | 1         | 1      | 2.78%   |
| Fujitsu             | 1         | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 36        | 36     | 66.67%  |
| SSD  | 17        | 18     | 31.48%  |
| NVMe | 1         | 1      | 1.85%   |

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
| Works    | 536       | 647    | 71.47%  |
| Detected | 160       | 229    | 21.33%  |
| Malfunc  | 54        | 55     | 7.2%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 347       | 46.14%  |
| Samsung Electronics            | 122       | 16.22%  |
| Apple                          | 76        | 10.11%  |
| AMD                            | 72        | 9.57%   |
| Sandisk                        | 35        | 4.65%   |
| SK Hynix                       | 17        | 2.26%   |
| Toshiba America Info Systems   | 11        | 1.46%   |
| Micron Technology              | 10        | 1.33%   |
| KIOXIA                         | 10        | 1.33%   |
| Kingston Technology Company    | 10        | 1.33%   |
| ADATA Technology               | 9         | 1.2%    |
| Micron/Crucial Technology      | 8         | 1.06%   |
| Silicon Motion                 | 6         | 0.8%    |
| Nvidia                         | 6         | 0.8%    |
| Phison Electronics             | 4         | 0.53%   |
| Union Memory (Shenzhen)        | 3         | 0.4%    |
| Lenovo                         | 3         | 0.4%    |
| Solid State Storage Technology | 2         | 0.27%   |
| Lite-On Technology             | 1         | 0.13%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Apple S1X NVMe Controller                                                      | 75        | 9.55%   |
| Samsung Electronics SATA controller                                            | 68        | 8.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 64        | 8.15%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 64        | 8.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 47        | 5.99%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 31        | 3.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 24        | 3.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 22        | 2.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 18        | 2.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 18        | 2.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 16        | 2.04%   |
| Samsung NVMe SSD Controller 980                                                | 14        | 1.78%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 14        | 1.78%   |
| Intel Comet Lake SATA AHCI Controller                                          | 13        | 1.66%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 12        | 1.53%   |
| Intel Volume Management Device NVMe RAID Controller                            | 12        | 1.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 11        | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 11        | 1.4%    |
| Micron Non-Volatile memory controller                                          | 10        | 1.27%   |
| KIOXIA Non-Volatile memory controller                                          | 10        | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 9         | 1.15%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 8         | 1.02%   |
| Intel SSD 660P Series                                                          | 7         | 0.89%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 7         | 0.89%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 0.89%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 6         | 0.76%   |
| Sandisk Non-Volatile memory controller                                         | 6         | 0.76%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 6         | 0.76%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 0.76%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 6         | 0.76%   |
| SK Hynix Gold P31 SSD                                                          | 5         | 0.64%   |
| SK Hynix BC511                                                                 | 5         | 0.64%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 5         | 0.64%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 5         | 0.64%   |
| Sandisk PC SN520 NVMe SSD                                                      | 5         | 0.64%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 5         | 0.64%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 5         | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 5         | 0.64%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 0.51%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 4         | 0.51%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 0.51%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 0.51%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 4         | 0.51%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 4         | 0.51%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 0.38%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.38%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.38%   |
| Phison E12 NVMe Controller                                                     | 3         | 0.38%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 0.38%   |
| Lenovo Non-Volatile memory controller                                          | 3         | 0.38%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 0.38%   |
| Intel Tiger Lake-LP SATA Controller [AHCI mode]                                | 3         | 0.38%   |
| Intel SSD 600P Series                                                          | 3         | 0.38%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.38%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 0.38%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 0.38%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 3         | 0.38%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 0.38%   |
| AMD IXP SB4x0 IDE Controller                                                   | 3         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 440       | 57.37%  |
| NVMe | 258       | 33.64%  |
| IDE  | 36        | 4.69%   |
| RAID | 33        | 4.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 608       | 86.24%  |
| AMD    | 97        | 13.76%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-5250U CPU @ 1.60GHz             | 140       | 19.86%  |
| Intel Celeron CPU N2840 @ 2.16GHz             | 47        | 6.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 3.69%   |
| Intel Celeron CPU 3865U @ 1.80GHz             | 16        | 2.27%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 13        | 1.84%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 13        | 1.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 13        | 1.84%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 8         | 1.13%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 1.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.13%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 8         | 1.13%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.13%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 7         | 0.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 7         | 0.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 7         | 0.99%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 7         | 0.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 7         | 0.99%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 7         | 0.99%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 0.99%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 6         | 0.85%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 6         | 0.85%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 0.85%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 6         | 0.85%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 6         | 0.85%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 5         | 0.71%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 5         | 0.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.71%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 4         | 0.57%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 4         | 0.57%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 4         | 0.57%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 0.57%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 4         | 0.57%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.57%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 4         | 0.57%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 0.57%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 0.57%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 0.57%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 4         | 0.57%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 3         | 0.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 3         | 0.43%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 3         | 0.43%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 3         | 0.43%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 3         | 0.43%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 3         | 0.43%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 3         | 0.43%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 3         | 0.43%   |
| Intel Core i5-3337U CPU @ 1.80GHz             | 3         | 0.43%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 3         | 0.43%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 3         | 0.43%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 3         | 0.43%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 3         | 0.43%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 3         | 0.43%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 3         | 0.43%   |
| Intel Celeron CPU B800 @ 1.50GHz              | 3         | 0.43%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 3         | 0.43%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 3         | 0.43%   |
| AMD PRO A6-9500B R5, 6 COMPUTE CORES 2C+4G    | 3         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 285       | 40.43%  |
| Intel Core i7           | 122       | 17.3%   |
| Intel Celeron           | 79        | 11.21%  |
| AMD Ryzen 5             | 38        | 5.39%   |
| Other                   | 32        | 4.54%   |
| Intel Core i3           | 32        | 4.54%   |
| Intel Core 2 Duo        | 23        | 3.26%   |
| AMD Ryzen 7             | 15        | 2.13%   |
| Intel Pentium           | 11        | 1.56%   |
| AMD Ryzen 7 PRO         | 9         | 1.28%   |
| Intel Pentium M         | 5         | 0.71%   |
| Intel Atom              | 5         | 0.71%   |
| Intel Celeron M         | 4         | 0.57%   |
| AMD Ryzen 9             | 4         | 0.57%   |
| AMD A8                  | 4         | 0.57%   |
| AMD A4                  | 4         | 0.57%   |
| Intel Core 2            | 3         | 0.43%   |
| AMD Ryzen 3             | 3         | 0.43%   |
| AMD A6                  | 3         | 0.43%   |
| Intel Pentium Dual      | 2         | 0.28%   |
| Intel Genuine           | 2         | 0.28%   |
| Intel Core m3           | 2         | 0.28%   |
| AMD Turion 64 Mobile    | 2         | 0.28%   |
| AMD E                   | 2         | 0.28%   |
| AMD C-60                | 2         | 0.28%   |
| AMD A12                 | 2         | 0.28%   |
| Intel Xeon              | 1         | 0.14%   |
| Intel Pentium Silver    | 1         | 0.14%   |
| Intel Pentium Gold      | 1         | 0.14%   |
| Intel Pentium Dual-Core | 1         | 0.14%   |
| Intel Core m7           | 1         | 0.14%   |
| AMD E1                  | 1         | 0.14%   |
| AMD C-50                | 1         | 0.14%   |
| AMD C-30                | 1         | 0.14%   |
| AMD Athlon 64           | 1         | 0.14%   |
| AMD Athlon              | 1         | 0.14%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 442       | 62.7%   |
| 4      | 180       | 25.53%  |
| 6      | 34        | 4.82%   |
| 8      | 27        | 3.83%   |
| 1      | 22        | 3.12%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 705       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 535       | 75.89%  |
| 1      | 170       | 24.11%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 691       | 98.01%  |
| 32-bit         | 13        | 1.84%   |
| Unknown        | 1         | 0.14%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x306d4    | 159       | 22.36%  |
| Unknown    | 113       | 15.89%  |
| 0x30678    | 48        | 6.75%   |
| 0x806e9    | 36        | 5.06%   |
| 0x306a9    | 34        | 4.78%   |
| 0x206a7    | 27        | 3.8%    |
| 0x08108109 | 24        | 3.38%   |
| 0x806c1    | 20        | 2.81%   |
| 0x806ec    | 19        | 2.67%   |
| 0x406e3    | 19        | 2.67%   |
| 0x806ea    | 17        | 2.39%   |
| 0x906ea    | 14        | 1.97%   |
| 0x1067a    | 14        | 1.97%   |
| 0x40651    | 13        | 1.83%   |
| 0xa0652    | 12        | 1.69%   |
| 0x706e5    | 11        | 1.55%   |
| 0x306c3    | 10        | 1.41%   |
| 0x08600106 | 9         | 1.27%   |
| 0x806eb    | 7         | 0.98%   |
| 0x6d8      | 6         | 0.84%   |
| 0x20655    | 6         | 0.84%   |
| 0x6fd      | 5         | 0.7%    |
| 0x506c9    | 5         | 0.7%    |
| 0x08600104 | 5         | 0.7%    |
| 0x08108102 | 5         | 0.7%    |
| 0x906e9    | 4         | 0.56%   |
| 0x106c2    | 4         | 0.56%   |
| 0x0a50000b | 4         | 0.56%   |
| 0x08608103 | 4         | 0.56%   |
| 0x08600103 | 4         | 0.56%   |
| 0x0600611a | 4         | 0.56%   |
| 0x906eb    | 3         | 0.42%   |
| 0x706a8    | 3         | 0.42%   |
| 0x6f6      | 3         | 0.42%   |
| 0x10676    | 3         | 0.42%   |
| 0x0a50000c | 3         | 0.42%   |
| 0x06006705 | 3         | 0.42%   |
| 0x806d1    | 2         | 0.28%   |
| 0x6fa      | 2         | 0.28%   |
| 0x695      | 2         | 0.28%   |
| 0x506e3    | 2         | 0.28%   |
| 0x40661    | 2         | 0.28%   |
| 0x0810100b | 2         | 0.28%   |
| 0x07030105 | 2         | 0.28%   |
| 0x03000027 | 2         | 0.28%   |
| 0x906ed    | 1         | 0.14%   |
| 0x6fb      | 1         | 0.14%   |
| 0x6e8      | 1         | 0.14%   |
| 0x406c4    | 1         | 0.14%   |
| 0x406c3    | 1         | 0.14%   |
| 0x20652    | 1         | 0.14%   |
| 0x106e5    | 1         | 0.14%   |
| 0x10661    | 1         | 0.14%   |
| 0x07030106 | 1         | 0.14%   |
| 0x06001119 | 1         | 0.14%   |
| 0x05000119 | 1         | 0.14%   |
| 0x05000101 | 1         | 0.14%   |
| 0x05000029 | 1         | 0.14%   |
| 0x05000028 | 1         | 0.14%   |
| 0x03000014 | 1         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Broadwell     | 160       | 22.7%   |
| KabyLake      | 129       | 18.3%   |
| Silvermont    | 52        | 7.38%   |
| IvyBridge     | 45        | 6.38%   |
| Haswell       | 35        | 4.96%   |
| SandyBridge   | 33        | 4.68%   |
| Zen+          | 32        | 4.54%   |
| Skylake       | 31        | 4.4%    |
| TigerLake     | 27        | 3.83%   |
| Zen 2         | 23        | 3.26%   |
| Penryn        | 18        | 2.55%   |
| Icelake       | 15        | 2.13%   |
| Core          | 14        | 1.99%   |
| Westmere      | 13        | 1.84%   |
| CometLake     | 13        | 1.84%   |
| P6            | 9         | 1.28%   |
| Zen 3         | 8         | 1.13%   |
| Excavator     | 8         | 1.13%   |
| Goldmont      | 6         | 0.85%   |
| Bobcat        | 6         | 0.85%   |
| Puma          | 5         | 0.71%   |
| Bonnell       | 4         | 0.57%   |
| Unknown       | 4         | 0.57%   |
| Zen           | 3         | 0.43%   |
| K8 Hammer     | 3         | 0.43%   |
| K10 Llano     | 3         | 0.43%   |
| Goldmont plus | 3         | 0.43%   |
| Piledriver    | 1         | 0.14%   |
| Nehalem       | 1         | 0.14%   |
| Jaguar        | 1         | 0.14%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 581       | 70.08%  |
| Nvidia | 125       | 15.08%  |
| AMD    | 123       | 14.84%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 6000                                                                   | 141       | 16.45%  |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 49        | 5.72%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 43        | 5.02%   |
| AMD Picasso                                                                              | 33        | 3.85%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 29        | 3.38%   |
| Intel UHD Graphics 620                                                                   | 25        | 2.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 24        | 2.8%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 23        | 2.68%   |
| Intel HD Graphics 620                                                                    | 23        | 2.68%   |
| AMD Renoir                                                                               | 23        | 2.68%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 19        | 2.22%   |
| Intel HD Graphics 5500                                                                   | 18        | 2.1%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 18        | 2.1%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 2.1%    |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 17        | 1.98%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 15        | 1.75%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 14        | 1.63%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 12        | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 1.28%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 1.28%   |
| Intel Core Processor Integrated Graphics Controller                                      | 11        | 1.28%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 9         | 1.05%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 1.05%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 8         | 0.93%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 8         | 0.93%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.82%   |
| AMD Cezanne                                                                              | 7         | 0.82%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 6         | 0.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.58%   |
| Nvidia TU117M                                                                            | 5         | 0.58%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 5         | 0.58%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 5         | 0.58%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 5         | 0.58%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 0.58%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.58%   |
| Intel HD Graphics 630                                                                    | 5         | 0.58%   |
| Intel HD Graphics 530                                                                    | 5         | 0.58%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 5         | 0.58%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5         | 0.58%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.47%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.47%   |
| Nvidia GM108M [GeForce 840M]                                                             | 4         | 0.47%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.47%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 0.47%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 4         | 0.47%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 0.47%   |
| AMD Lucienne                                                                             | 4         | 0.47%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.35%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 3         | 0.35%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.35%   |
| Intel HD Graphics 515                                                                    | 3         | 0.35%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.35%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 0.35%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.35%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 3         | 0.35%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 0.35%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.35%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.23%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.23%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.23%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 467       | 66.05%  |
| Intel + Nvidia | 95        | 13.44%  |
| 1 x AMD        | 86        | 12.16%  |
| 1 x Nvidia     | 21        | 2.97%   |
| Intel + AMD    | 19        | 2.69%   |
| AMD + Nvidia   | 10        | 1.41%   |
| 2 x AMD        | 8         | 1.13%   |
| Other          | 1         | 0.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 616       | 87.25%  |
| Proprietary | 46        | 6.52%   |
| Unknown     | 44        | 6.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 590       | 83.22%  |
| 0.01-0.5   | 48        | 6.77%   |
| 1.01-2.0   | 26        | 3.67%   |
| 3.01-4.0   | 21        | 2.96%   |
| 0.51-1.0   | 20        | 2.82%   |
| 7.01-8.0   | 2         | 0.28%   |
| 5.01-6.0   | 2         | 0.28%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Apple                   | 155       | 20.81%  |
| BOE                     | 116       | 15.57%  |
| AU Optronics            | 115       | 15.44%  |
| Chimei Innolux          | 84        | 11.28%  |
| LG Display              | 78        | 10.47%  |
| Samsung Electronics     | 39        | 5.23%   |
| Sharp                   | 20        | 2.68%   |
| Lenovo                  | 15        | 2.01%   |
| Dell                    | 15        | 2.01%   |
| InfoVision              | 11        | 1.48%   |
| Goldstar                | 9         | 1.21%   |
| Philips                 | 8         | 1.07%   |
| PANDA                   | 8         | 1.07%   |
| Chi Mei Optoelectronics | 8         | 1.07%   |
| Hewlett-Packard         | 7         | 0.94%   |
| Ancor Communications    | 6         | 0.81%   |
| LG Philips              | 5         | 0.67%   |
| BenQ                    | 5         | 0.67%   |
| ViewSonic               | 4         | 0.54%   |
| Unknown                 | 4         | 0.54%   |
| NEC Computers           | 3         | 0.4%    |
| HannStar                | 3         | 0.4%    |
| CPT                     | 3         | 0.4%    |
| AOC                     | 3         | 0.4%    |
| CSO                     | 2         | 0.27%   |
| ASUSTek Computer        | 2         | 0.27%   |
| Acer                    | 2         | 0.27%   |
| ___                     | 1         | 0.13%   |
| Vestel Elektronik       | 1         | 0.13%   |
| Sony                    | 1         | 0.13%   |
| Quanta Display          | 1         | 0.13%   |
| Panasonic               | 1         | 0.13%   |
| NCS                     | 1         | 0.13%   |
| MSI                     | 1         | 0.13%   |
| LPL                     | 1         | 0.13%   |
| JXG                     | 1         | 0.13%   |
| JRY                     | 1         | 0.13%   |
| IOD                     | 1         | 0.13%   |
| Iiyama                  | 1         | 0.13%   |
| Compaq Computer         | 1         | 0.13%   |
| CMN                     | 1         | 0.13%   |
| BOE Technology Group    | 1         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 40        | 5.31%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 39        | 5.18%   |
| Apple Color LCD APP9CF2 1366x768 260x140mm 11.6-inch                      | 35        | 4.65%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 30        | 3.98%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                      | 23        | 3.05%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 10        | 1.33%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch             | 10        | 1.33%   |
| BOE LCD Monitor BOE06CF 1366x768 277x156mm 12.5-inch                      | 9         | 1.2%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch            | 9         | 1.2%    |
| InfoVision LCD Monitor IVO0533 1366x768 293x164mm 13.2-inch               | 7         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 6         | 0.8%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 6         | 0.8%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 6         | 0.8%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 5         | 0.66%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 5         | 0.66%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 4         | 0.53%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                   | 4         | 0.53%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch               | 4         | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 4         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 4         | 0.53%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 4         | 0.53%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch            | 4         | 0.53%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 4         | 0.53%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 4         | 0.53%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch             | 4         | 0.53%   |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                      | 4         | 0.53%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 3         | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 3         | 0.4%    |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 3         | 0.4%    |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch             | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 3         | 0.4%    |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                   | 2         | 0.27%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                   | 2         | 0.27%   |
| Sharp LCD Monitor SHP1447 1920x1080 290x170mm 13.2-inch                   | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch      | 2         | 0.27%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                   | 2         | 0.27%   |
| NEC Computers EA244WMi NEC68D7 1920x1080 520x320mm 24.0-inch              | 2         | 0.27%   |
| NEC Computers EA244WMi NEC68D5 1920x1200 520x320mm 24.0-inch              | 2         | 0.27%   |
| LG Philips LCD Monitor LPL1151 1024x768 304x228mm 15.0-inch               | 2         | 0.27%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch              | 2         | 0.27%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 2         | 0.27%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 2         | 0.27%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.27%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch              | 2         | 0.27%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch              | 2         | 0.27%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch               | 2         | 0.27%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 2         | 0.27%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 2         | 0.27%   |
| LG Display LCD Monitor LGD034C 1366x768 293x165mm 13.2-inch               | 2         | 0.27%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 2         | 0.27%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 2         | 0.27%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch              | 2         | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 2         | 0.27%   |
| Goldstar FULL HD GSM5B54 1920x1080 480x270mm 21.7-inch                    | 2         | 0.27%   |
| CPT LCD Monitor CPT04C4 1024x600 222x130mm 10.1-inch                      | 2         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 255       | 35.42%  |
| 1920x1080 (FHD)    | 253       | 35.14%  |
| 1440x900 (WXGA+)   | 74        | 10.28%  |
| 1600x900 (HD+)     | 23        | 3.19%   |
| 1280x800 (WXGA)    | 23        | 3.19%   |
| 1920x1200 (WUXGA)  | 17        | 2.36%   |
| 3840x2160 (4K)     | 16        | 2.22%   |
| 2560x1440 (QHD)    | 14        | 1.94%   |
| 1280x1024 (SXGA)   | 6         | 0.83%   |
| 1024x600           | 6         | 0.83%   |
| 2880x1800          | 5         | 0.69%   |
| 1024x768 (XGA)     | 5         | 0.69%   |
| 2288x1287          | 3         | 0.42%   |
| 2160x1440          | 3         | 0.42%   |
| 1680x1050 (WSXGA+) | 3         | 0.42%   |
| 3840x1080          | 2         | 0.28%   |
| 3440x1440          | 2         | 0.28%   |
| 3200x1800 (QHD+)   | 2         | 0.28%   |
| 2560x1600          | 2         | 0.28%   |
| 3840x2400          | 1         | 0.14%   |
| 2880x1920          | 1         | 0.14%   |
| 2256x1504          | 1         | 0.14%   |
| 1792x768           | 1         | 0.14%   |
| 1600x1200          | 1         | 0.14%   |
| Unknown            | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 182       | 24.53%  |
| 13      | 174       | 23.45%  |
| 11      | 134       | 18.06%  |
| 14      | 77        | 10.38%  |
| 12      | 35        | 4.72%   |
| 17      | 32        | 4.31%   |
| 24      | 25        | 3.37%   |
| 21      | 14        | 1.89%   |
| 23      | 12        | 1.62%   |
| 27      | 11        | 1.48%   |
| 31      | 5         | 0.67%   |
| 25      | 5         | 0.67%   |
| 19      | 5         | 0.67%   |
| 10      | 4         | 0.54%   |
| Unknown | 4         | 0.54%   |
| 142     | 3         | 0.4%    |
| 84      | 2         | 0.27%   |
| 40      | 2         | 0.27%   |
| 34      | 2         | 0.27%   |
| 32      | 2         | 0.27%   |
| 18      | 2         | 0.27%   |
| 16      | 2         | 0.27%   |
| 72      | 1         | 0.13%   |
| 48      | 1         | 0.13%   |
| 47      | 1         | 0.13%   |
| 46      | 1         | 0.13%   |
| 33      | 1         | 0.13%   |
| 22      | 1         | 0.13%   |
| 20      | 1         | 0.13%   |
| 8       | 1         | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 317       | 42.84%  |
| 201-300        | 289       | 39.05%  |
| 501-600        | 47        | 6.35%   |
| 351-400        | 36        | 4.86%   |
| 401-500        | 22        | 2.97%   |
| 601-700        | 8         | 1.08%   |
| 701-800        | 5         | 0.68%   |
| Unknown        | 4         | 0.54%   |
| More than 2000 | 3         | 0.41%   |
| 1501-2000      | 3         | 0.41%   |
| 1001-1500      | 3         | 0.41%   |
| 801-900        | 2         | 0.27%   |
| 101-200        | 1         | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 532       | 77.89%  |
| 16/10   | 120       | 17.57%  |
| 4/3     | 7         | 1.02%   |
| 3/2     | 7         | 1.02%   |
| 5/4     | 6         | 0.88%   |
| Unknown | 4         | 0.59%   |
| 21/9    | 3         | 0.44%   |
| 1.00    | 3         | 0.44%   |
| 32/9    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 184       | 24.76%  |
| 81-90          | 172       | 23.15%  |
| 51-60          | 134       | 18.03%  |
| 71-80          | 80        | 10.77%  |
| 201-250        | 40        | 5.38%   |
| 61-70          | 33        | 4.44%   |
| 121-130        | 28        | 3.77%   |
| 251-300        | 13        | 1.75%   |
| 301-350        | 11        | 1.48%   |
| 351-500        | 10        | 1.35%   |
| 151-200        | 9         | 1.21%   |
| More than 1000 | 6         | 0.81%   |
| 141-150        | 6         | 0.81%   |
| 501-1000       | 5         | 0.67%   |
| 41-50          | 4         | 0.54%   |
| Unknown        | 4         | 0.54%   |
| 91-100         | 2         | 0.27%   |
| 1-40           | 1         | 0.13%   |
| 131-140        | 1         | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 457       | 62.6%   |
| 101-120       | 127       | 17.4%   |
| 51-100        | 86        | 11.78%  |
| 161-240       | 37        | 5.07%   |
| More than 240 | 11        | 1.51%   |
| 1-50          | 8         | 1.1%    |
| Unknown       | 4         | 0.55%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 568       | 80.23%  |
| 2     | 83        | 11.72%  |
| 0     | 48        | 6.78%   |
| 3     | 9         | 1.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 349       | 34.32%  |
| Realtek Semiconductor             | 269       | 26.45%  |
| Broadcom Limited                  | 157       | 15.44%  |
| Qualcomm Atheros                  | 116       | 11.41%  |
| Broadcom                          | 49        | 4.82%   |
| Marvell Technology Group          | 9         | 0.88%   |
| Ralink                            | 7         | 0.69%   |
| TP-Link                           | 6         | 0.59%   |
| Sierra Wireless                   | 6         | 0.59%   |
| Nvidia                            | 5         | 0.49%   |
| DisplayLink                       | 5         | 0.49%   |
| Dell                              | 5         | 0.49%   |
| JMicron Technology                | 4         | 0.39%   |
| Ericsson Business Mobile Networks | 4         | 0.39%   |
| MEDIATEK                          | 3         | 0.29%   |
| AMD                               | 3         | 0.29%   |
| Lenovo                            | 2         | 0.2%    |
| Cypress Semiconductor             | 2         | 0.2%    |
| Attansic Technology               | 2         | 0.2%    |
| ASUSTek Computer                  | 2         | 0.2%    |
| Xiaomi                            | 1         | 0.1%    |
| Samsung Electronics               | 1         | 0.1%    |
| Ralink Technology                 | 1         | 0.1%    |
| Qualcomm Atheros Communications   | 1         | 0.1%    |
| Qualcomm                          | 1         | 0.1%    |
| Microchip Technology              | 1         | 0.1%    |
| Huawei Technologies               | 1         | 0.1%    |
| Hewlett-Packard                   | 1         | 0.1%    |
| Google                            | 1         | 0.1%    |
| Fibocom                           | 1         | 0.1%    |
| Edimax Technology                 | 1         | 0.1%    |
| D-Link                            | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 184       | 15.27%  |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter              | 141       | 11.7%   |
| Intel Wireless 7260                                                     | 61        | 5.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 43        | 3.57%   |
| Intel Wireless 8265 / 8275                                              | 42        | 3.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 35        | 2.9%    |
| Intel Wi-Fi 6 AX200                                                     | 33        | 2.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 30        | 2.49%   |
| Intel Ethernet Connection (4) I219-V                                    | 25        | 2.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 22        | 1.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 19        | 1.58%   |
| Intel Wireless 8260                                                     | 18        | 1.49%   |
| Intel Wireless 7265                                                     | 18        | 1.49%   |
| Intel Wi-Fi 6 AX201                                                     | 17        | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 16        | 1.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 15        | 1.24%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 15        | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 1.16%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 13        | 1.08%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 1.08%   |
| Intel Ethernet Connection (4) I219-LM                                   | 12        | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 10        | 0.83%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 9         | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 8         | 0.66%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 8         | 0.66%   |
| Intel Wireless 3165                                                     | 8         | 0.66%   |
| Intel Ethernet Connection I219-LM                                       | 8         | 0.66%   |
| Intel Ethernet Connection I218-LM                                       | 8         | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                                   | 8         | 0.66%   |
| Intel Centrino Wireless-N 2230                                          | 8         | 0.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 8         | 0.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 7         | 0.58%   |
| Intel Wireless 3160                                                     | 7         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 0.5%    |
| Intel Wireless-AC 9260                                                  | 6         | 0.5%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 6         | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 6         | 0.5%    |
| Intel Centrino Ultimate-N 6300                                          | 6         | 0.5%    |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 0.5%    |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 5         | 0.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 5         | 0.41%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 5         | 0.41%   |
| Intel 82577LM Gigabit Network Connection                                | 5         | 0.41%   |
| Sierra Wireless EM7345 4G LTE                                           | 4         | 0.33%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                        | 4         | 0.33%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 4         | 0.33%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 4         | 0.33%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 4         | 0.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 4         | 0.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 4         | 0.33%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 4         | 0.33%   |
| Intel Ethernet Connection I219-V                                        | 4         | 0.33%   |
| Intel Ethernet Connection (6) I219-V                                    | 4         | 0.33%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 3         | 0.25%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 3         | 0.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 0.25%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 3         | 0.25%   |
| Nvidia MCP79 Ethernet                                                   | 3         | 0.25%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 332       | 46.83%  |
| Broadcom Limited                | 151       | 21.3%   |
| Qualcomm Atheros                | 104       | 14.67%  |
| Realtek Semiconductor           | 66        | 9.31%   |
| Broadcom                        | 31        | 4.37%   |
| Ralink                          | 7         | 0.99%   |
| TP-Link                         | 3         | 0.42%   |
| MEDIATEK                        | 3         | 0.42%   |
| Dell                            | 3         | 0.42%   |
| Sierra Wireless                 | 2         | 0.28%   |
| ASUSTek Computer                | 2         | 0.28%   |
| Ralink Technology               | 1         | 0.14%   |
| Qualcomm Atheros Communications | 1         | 0.14%   |
| Qualcomm                        | 1         | 0.14%   |
| Fibocom                         | 1         | 0.14%   |
| Edimax Technology               | 1         | 0.14%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Notebooks | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                  | 141       | 19.78%  |
| Intel Wireless 7260                                                         | 61        | 8.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 43        | 6.03%   |
| Intel Wireless 8265 / 8275                                                  | 42        | 5.89%   |
| Intel Wi-Fi 6 AX200                                                         | 33        | 4.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 22        | 3.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 19        | 2.66%   |
| Intel Wireless 8260                                                         | 18        | 2.52%   |
| Intel Wireless 7265                                                         | 18        | 2.52%   |
| Intel Wi-Fi 6 AX201                                                         | 17        | 2.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 16        | 2.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 15        | 2.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 14        | 1.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 14        | 1.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 13        | 1.82%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 10        | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 8         | 1.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 8         | 1.12%   |
| Intel Wireless 3165                                                         | 8         | 1.12%   |
| Intel Centrino Wireless-N 2230                                              | 8         | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 8         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 7         | 0.98%   |
| Intel Wireless 3160                                                         | 7         | 0.98%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 6         | 0.84%   |
| Intel Wireless-AC 9260                                                      | 6         | 0.84%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 6         | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                             | 6         | 0.84%   |
| Intel Centrino Ultimate-N 6300                                              | 6         | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                               | 6         | 0.84%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 5         | 0.7%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 5         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                   | 4         | 0.56%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 4         | 0.56%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 4         | 0.56%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                         | 4         | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                    | 3         | 0.42%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                             | 3         | 0.42%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 3         | 0.42%   |
| MEDIATEK Network controller                                                 | 3         | 0.42%   |
| Intel Ultimate N WiFi Link 5300                                             | 3         | 0.42%   |
| Intel Centrino Advanced-N 6200                                              | 3         | 0.42%   |
| Broadcom BCM43227 802.11b/g/n                                               | 3         | 0.42%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 3         | 0.42%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                           | 3         | 0.42%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                         | 2         | 0.28%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 2         | 0.28%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                     | 2         | 0.28%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 2         | 0.28%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 2         | 0.28%   |
| Intel Tiger Lake PCH CNVi WiFi                                              | 2         | 0.28%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 2         | 0.28%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                    | 2         | 0.28%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 2         | 0.28%   |
| Intel Centrino Advanced-N 6235                                              | 2         | 0.28%   |
| Broadcom Limited BCM43224 802.11a/b/g/n                                     | 2         | 0.28%   |
| Broadcom Limited BCM4318 [AirForce 54g] 802.11a/b/g PCI Express Transceiver | 2         | 0.28%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                 | 2         | 0.28%   |
| Broadcom BCM4331 802.11a/b/g/n                                              | 2         | 0.28%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 2         | 0.28%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller         | 2         | 0.28%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 242       | 51.49%  |
| Intel                    | 136       | 28.94%  |
| Broadcom                 | 23        | 4.89%   |
| Qualcomm Atheros         | 20        | 4.26%   |
| Marvell Technology Group | 9         | 1.91%   |
| Broadcom Limited         | 7         | 1.49%   |
| Nvidia                   | 5         | 1.06%   |
| DisplayLink              | 5         | 1.06%   |
| Sierra Wireless          | 4         | 0.85%   |
| JMicron Technology       | 4         | 0.85%   |
| TP-Link                  | 3         | 0.64%   |
| Lenovo                   | 2         | 0.43%   |
| Cypress Semiconductor    | 2         | 0.43%   |
| Attansic Technology      | 2         | 0.43%   |
| Xiaomi                   | 1         | 0.21%   |
| Samsung Electronics      | 1         | 0.21%   |
| Microchip Technology     | 1         | 0.21%   |
| Huawei Technologies      | 1         | 0.21%   |
| Google                   | 1         | 0.21%   |
| D-Link                   | 1         | 0.21%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 184       | 38.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 7.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 6.29%   |
| Intel Ethernet Connection (4) I219-V                              | 25        | 5.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 13        | 2.73%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 2.52%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 1.68%   |
| Intel Ethernet Connection I218-LM                                 | 8         | 1.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 8         | 1.68%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 7         | 1.47%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.05%   |
| Sierra Wireless EM7345 4G LTE                                     | 4         | 0.84%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 4         | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.84%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 4         | 0.84%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.84%   |
| Intel Ethernet Connection (6) I219-V                              | 4         | 0.84%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 4         | 0.84%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.63%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.63%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.63%   |
| Intel Ethernet Connection (13) I219-V                             | 3         | 0.63%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.63%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 0.63%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 3         | 0.63%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 2         | 0.42%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.42%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.42%   |
| Nvidia MCP89 Ethernet                                             | 2         | 0.42%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 2         | 0.42%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                  | 2         | 0.42%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.42%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.42%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.42%   |
| Intel 82566MM Gigabit Network Connection                          | 2         | 0.42%   |
| Cypress K38231_03                                                 | 2         | 0.42%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                       | 2         | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.42%   |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe           | 2         | 0.42%   |
| Broadcom Limited BCM4401-B0 100Base-TX                            | 2         | 0.42%   |
| Attansic AR8152 v2.0 Fast Ethernet                                | 2         | 0.42%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.21%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.21%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.21%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                  | 1         | 0.21%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 1         | 0.21%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.21%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.21%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.21%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1         | 0.21%   |
| Microchip LAN9512/LAN9514 Ethernet 10/100 Adapter (SAL10)         | 1         | 0.21%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.21%   |
| Marvell Group 88E8071 PCI-E Gigabit Ethernet Controller           | 1         | 0.21%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.21%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 689       | 59.97%  |
| Ethernet | 445       | 38.73%  |
| Modem    | 15        | 1.31%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 625       | 64.7%   |
| Ethernet | 339       | 35.09%  |
| Modem    | 2         | 0.21%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 411       | 58.3%   |
| 1     | 286       | 40.57%  |
| 3     | 7         | 0.99%   |
| 0     | 1         | 0.14%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 624       | 88.01%  |
| Yes  | 85        | 11.99%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 265       | 43.66%  |
| Apple                           | 153       | 25.21%  |
| Realtek Semiconductor           | 41        | 6.75%   |
| Qualcomm Atheros Communications | 39        | 6.43%   |
| Lite-On Technology              | 29        | 4.78%   |
| Broadcom                        | 24        | 3.95%   |
| IMC Networks                    | 15        | 2.47%   |
| Foxconn / Hon Hai               | 10        | 1.65%   |
| Hewlett-Packard                 | 6         | 0.99%   |
| Cambridge Silicon Radio         | 6         | 0.99%   |
| Realtek                         | 5         | 0.82%   |
| Ralink                          | 4         | 0.66%   |
| Toshiba                         | 3         | 0.49%   |
| Dell                            | 3         | 0.49%   |
| Taiyo Yuden                     | 2         | 0.33%   |
| ASUSTek Computer                | 1         | 0.16%   |
| Alps Electric                   | 1         | 0.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Apple Bluetooth USB Host Controller                                                 | 141       | 23.15%  |
| Intel Bluetooth wireless interface                                                  | 117       | 19.21%  |
| Intel Bluetooth Device                                                              | 108       | 17.73%  |
| Intel AX200 Bluetooth                                                               | 34        | 5.58%   |
| Realtek Bluetooth Radio                                                             | 30        | 4.93%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 27        | 4.43%   |
| Lite-On Bluetooth Device                                                            | 22        | 3.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 1.31%   |
| Apple Bluetooth Host Controller                                                     | 8         | 1.31%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 6         | 0.99%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 0.99%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 0.99%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 0.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 6         | 0.99%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 6         | 0.99%   |
| Realtek Bluetooth Radio                                                             | 5         | 0.82%   |
| Ralink RT3290 Bluetooth                                                             | 4         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 4         | 0.66%   |
| IMC Networks Bluetooth Radio                                                        | 4         | 0.66%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 0.66%   |
| Toshiba Bluetooth Device                                                            | 3         | 0.49%   |
| IMC Networks Bluetooth Device                                                       | 3         | 0.49%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.33%   |
| Realtek 802.11n WLAN Adapter                                                        | 2         | 0.33%   |
| Lite-On BCM43142A0                                                                  | 2         | 0.33%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.33%   |
| IMC Networks Wireless_Device                                                        | 2         | 0.33%   |
| IMC Networks Bluetooth module                                                       | 2         | 0.33%   |
| IMC Networks Bluetooth                                                              | 2         | 0.33%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.33%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 2         | 0.33%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 2         | 0.33%   |
| Broadcom BCM2045 Bluetooth                                                          | 2         | 0.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 2         | 0.33%   |
| Apple Bluetooth HCI MacBookPro (HID mode)                                           | 2         | 0.33%   |
| Taiyo Yuden Bluetooth Device (V2.1+EDR)                                             | 1         | 0.16%   |
| Taiyo Yuden Bluetooth Device                                                        | 1         | 0.16%   |
| Realtek RTL8723A Bluetooth                                                          | 1         | 0.16%   |
| Realtek CSR BS8510                                                                  | 1         | 0.16%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.16%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 1         | 0.16%   |
| Lite-On Wireless_Device                                                             | 1         | 0.16%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.16%   |
| Lite-On Bluetooth Radio                                                             | 1         | 0.16%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 1         | 0.16%   |
| IMC Networks Bluetooth USB Host Controller                                          | 1         | 0.16%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.16%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.16%   |
| HP Atheros AR9285 Malbec Bluetooth Adapter                                          | 1         | 0.16%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.16%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.16%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 1         | 0.16%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 1         | 0.16%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.16%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.16%   |
| Dell BCM20702A0                                                                     | 1         | 0.16%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.16%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.16%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 1         | 0.16%   |
| Alps Electric Bluetooth Controller (ALPS/UGPZ6)                                     | 1         | 0.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 601       | 74.66%  |
| AMD                    | 102       | 12.67%  |
| Nvidia                 | 68        | 8.45%   |
| Generalplus Technology | 6         | 0.75%   |
| C-Media Electronics    | 5         | 0.62%   |
| Creative Technology    | 4         | 0.5%    |
| Plantronics            | 3         | 0.37%   |
| Logitech               | 3         | 0.37%   |
| GN Netcom              | 3         | 0.37%   |
| Texas Instruments      | 2         | 0.25%   |
| Lenovo                 | 2         | 0.25%   |
| SAVITECH               | 1         | 0.12%   |
| Realtek Semiconductor  | 1         | 0.12%   |
| Razer USA              | 1         | 0.12%   |
| Microsoft              | 1         | 0.12%   |
| JMTek                  | 1         | 0.12%   |
| CMX Systems            | 1         | 0.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Broadwell-U Audio Controller                                                                | 160       | 14.73%  |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 159       | 14.64%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 93        | 8.56%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 70        | 6.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 52        | 4.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 48        | 4.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 35        | 3.22%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 28        | 2.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 27        | 2.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 2.39%   |
| Intel Cannon Lake PCH cAVS                                                                        | 23        | 2.12%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 19        | 1.75%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 19        | 1.75%   |
| Intel 8 Series HD Audio Controller                                                                | 19        | 1.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 1.47%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 15        | 1.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 14        | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 14        | 1.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 14        | 1.29%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 13        | 1.2%    |
| Intel Comet Lake PCH cAVS                                                                         | 13        | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 13        | 1.2%    |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 1.01%   |
| AMD FCH Azalia Controller                                                                         | 11        | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 10        | 0.92%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 0.92%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 8         | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 6         | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 6         | 0.55%   |
| Generalplus Technology Usb Audio Device                                                           | 6         | 0.55%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.46%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.46%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 0.46%   |
| Intel CM238 HD Audio Controller                                                                   | 5         | 0.46%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 0.46%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 0.46%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 0.46%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 0.37%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.37%   |
| Nvidia Audio device                                                                               | 3         | 0.28%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.28%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.28%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 3         | 0.28%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.28%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 3         | 0.28%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.28%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 3         | 0.28%   |
| Texas Instruments PCM2912A Audio Codec                                                            | 2         | 0.18%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.18%   |
| Nvidia MCP89 High Definition Audio                                                                | 2         | 0.18%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.18%   |
| Lenovo ThinkPad Dock Audio                                                                        | 2         | 0.18%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.18%   |
| Intel 82801DB/DBL/DBM (ICH4/ICH4-L/ICH4-M) AC'97 Audio Controller                                 | 2         | 0.18%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 2         | 0.18%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 0.18%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.18%   |
| SAVITECH SA9023 audio controller                                                                  | 1         | 0.09%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.09%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 245       | 33.52%  |
| SK Hynix               | 139       | 19.02%  |
| Micron Technology      | 78        | 10.67%  |
| Elpida                 | 53        | 7.25%   |
| Crucial                | 50        | 6.84%   |
| Kingston               | 48        | 6.57%   |
| Unknown                | 34        | 4.65%   |
| Ramaxel Technology     | 18        | 2.46%   |
| A-DATA Technology      | 13        | 1.78%   |
| Corsair                | 12        | 1.64%   |
| Nanya Technology       | 9         | 1.23%   |
| Team                   | 5         | 0.68%   |
| Smart                  | 4         | 0.55%   |
| PNY                    | 2         | 0.27%   |
| GOODRAM                | 2         | 0.27%   |
| ASint Technology       | 2         | 0.27%   |
| AMD                    | 2         | 0.27%   |
| Wilk                   | 1         | 0.14%   |
| Unknown (ABCD)         | 1         | 0.14%   |
| Unknown (0080000080AD) | 1         | 0.14%   |
| Unifosa                | 1         | 0.14%   |
| Transcend              | 1         | 0.14%   |
| SMART Brazil           | 1         | 0.14%   |
| Silicon Power          | 1         | 0.14%   |
| Sesame                 | 1         | 0.14%   |
| Patriot                | 1         | 0.14%   |
| Novatech               | 1         | 0.14%   |
| Kllisre                | 1         | 0.14%   |
| Infineon               | 1         | 0.14%   |
| Goldkey                | 1         | 0.14%   |
| G.Skill                | 1         | 0.14%   |
| Avant                  | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                         | 60        | 7.89%   |
| Samsung RAM M471B5674QH0-YK0 2048MB SODIMM DDR3 1600MT/s            | 38        | 5%      |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                          | 30        | 3.95%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                         | 20        | 2.63%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                        | 19        | 2.5%    |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB SODIMM DDR4 3200MT/s            | 18        | 2.37%   |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s              | 18        | 2.37%   |
| Elpida RAM Module 2GB SODIMM DDR3 1600MT/s                          | 15        | 1.97%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 10        | 1.32%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s                | 10        | 1.32%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 9         | 1.18%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s           | 8         | 1.05%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 7         | 0.92%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 7         | 0.92%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 6         | 0.79%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s            | 6         | 0.79%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 6         | 0.79%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s           | 5         | 0.66%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 5         | 0.66%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 5         | 0.66%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s            | 5         | 0.66%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s            | 5         | 0.66%   |
| Micron RAM 4ATF51264HZ-3G2J1 4096MB Row Of Chips DDR4 3200MT/s      | 5         | 0.66%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 4         | 0.53%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 4         | 0.53%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s            | 4         | 0.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 4         | 0.53%   |
| Samsung RAM M471A1K43BB1-CRC 8192MB SODIMM DDR4 2667MT/s            | 4         | 0.53%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8192MB SODIMM DDR4 3200MT/s             | 4         | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 4         | 0.53%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s             | 4         | 0.53%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s              | 3         | 0.39%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s          | 3         | 0.39%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 3         | 0.39%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 3         | 0.39%   |
| Samsung RAM Module 1GB SODIMM DDR2 533MT/s                          | 3         | 0.39%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s            | 3         | 0.39%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s              | 3         | 0.39%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 3         | 0.39%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4096MB SODIMM DDR4 2667MT/s        | 3         | 0.39%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s             | 3         | 0.39%   |
| Micron RAM 4ATF51264HZ-2G6E1 4096MB SODIMM DDR4 2667MT/s            | 3         | 0.39%   |
| Kingston RAM 99U5469-046.A00LF 4096MB SODIMM DDR3 1333MT/s          | 3         | 0.39%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8192MB SODIMM DDR4 2667MT/s          | 3         | 0.39%   |
| Crucial RAM CT51264BF160B.C16F 4096MB SODIMM DDR3 1600MT/s          | 3         | 0.39%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s          | 3         | 0.39%   |
| Unknown SODIMM 1GB SODIMM DDR2 533MT/s                              | 2         | 0.26%   |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                        | 2         | 0.26%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                         | 2         | 0.26%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 2         | 0.26%   |
| Unknown RAM Module 4GB SODIMM DDR3                                  | 2         | 0.26%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 2         | 0.26%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 2         | 0.26%   |
| Unknown RAM Module 2GB SODIMM DDR2                                  | 2         | 0.26%   |
| Unknown RAM Module 1GB SODIMM SDRAM                                 | 2         | 0.26%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s               | 2         | 0.26%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                        | 2         | 0.26%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 800MT/s                         | 2         | 0.26%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 667MT/s                         | 2         | 0.26%   |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s            | 2         | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 337       | 52.41%  |
| DDR4    | 230       | 35.77%  |
| DDR2    | 26        | 4.04%   |
| LPDDR3  | 20        | 3.11%   |
| LPDDR4  | 13        | 2.02%   |
| DDR     | 8         | 1.24%   |
| SDRAM   | 7         | 1.09%   |
| DRAM    | 1         | 0.16%   |
| Unknown | 1         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 604       | 93.64%  |
| Row Of Chips | 35        | 5.43%   |
| Chip         | 5         | 0.78%   |
| Unknown      | 1         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 240       | 34.83%  |
| 2048  | 173       | 25.11%  |
| 8192  | 170       | 24.67%  |
| 16384 | 55        | 7.98%   |
| 1024  | 28        | 4.06%   |
| 32768 | 13        | 1.89%   |
| 512   | 8         | 1.16%   |
| 256   | 2         | 0.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 282       | 41.53%  |
| 2667    | 114       | 16.79%  |
| 3200    | 83        | 12.22%  |
| 2400    | 36        | 5.3%    |
| 1333    | 29        | 4.27%   |
| 1334    | 26        | 3.83%   |
| 2133    | 25        | 3.68%   |
| 667     | 12        | 1.77%   |
| 3266    | 10        | 1.47%   |
| 1867    | 10        | 1.47%   |
| Unknown | 10        | 1.47%   |
| 533     | 8         | 1.18%   |
| 1067    | 7         | 1.03%   |
| 4267    | 6         | 0.88%   |
| 975     | 4         | 0.59%   |
| 333     | 4         | 0.59%   |
| 4199    | 3         | 0.44%   |
| 800     | 3         | 0.44%   |
| 400     | 3         | 0.44%   |
| 1866    | 2         | 0.29%   |
| 4266    | 1         | 0.15%   |
| 2048    | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 50%     |
| Brother Industries  | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-2010P Mono Laser Printer | 1         | 50%     |
| Brother MFC-L2707DW                 | 1         | 50%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 50%     |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 122       | 24.45%  |
| Quanta                                 | 68        | 13.63%  |
| IMC Networks                           | 64        | 12.83%  |
| Acer                                   | 52        | 10.42%  |
| Realtek Semiconductor                  | 40        | 8.02%   |
| Microdia                               | 34        | 6.81%   |
| Suyin                                  | 17        | 3.41%   |
| Sunplus Innovation Technology          | 14        | 2.81%   |
| Lite-On Technology                     | 14        | 2.81%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 2.81%   |
| Syntek                                 | 8         | 1.6%    |
| Logitech                               | 8         | 1.6%    |
| Apple                                  | 8         | 1.6%    |
| Luxvisions Innotech Limited            | 7         | 1.4%    |
| Lenovo                                 | 5         | 1%      |
| Silicon Motion                         | 3         | 0.6%    |
| Primax Electronics                     | 3         | 0.6%    |
| Z-Star Microelectronics                | 2         | 0.4%    |
| Ricoh                                  | 2         | 0.4%    |
| Alcor Micro                            | 2         | 0.4%    |
| Sunplus Technology                     | 1         | 0.2%    |
| Sonix Technology                       | 1         | 0.2%    |
| Pixart Imaging                         | 1         | 0.2%    |
| Mimaki Engineering                     | 1         | 0.2%    |
| KYE Systems (Mouse Systems)            | 1         | 0.2%    |
| Intel                                  | 1         | 0.2%    |
| Importek                               | 1         | 0.2%    |
| eMPIA Technology                       | 1         | 0.2%    |
| DJKCVA1BIDQ8CL                         | 1         | 0.2%    |
| ALi                                    | 1         | 0.2%    |
| A4Tech                                 | 1         | 0.2%    |
| 8SSC20F27114V1SR11K1SE2                | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 47        | 9.38%   |
| Quanta Chromebook HD Camera                                  | 37        | 7.39%   |
| IMC Networks Integrated Camera                               | 20        | 3.99%   |
| Microdia Integrated_Webcam_HD                                | 19        | 3.79%   |
| Realtek Integrated_Webcam_HD                                 | 18        | 3.59%   |
| Quanta VGA WebCam                                            | 18        | 3.59%   |
| Chicony HD WebCam                                            | 17        | 3.39%   |
| Acer Integrated Camera                                       | 15        | 2.99%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 14        | 2.79%   |
| Chicony Chromebook HD Camera                                 | 10        | 2%      |
| Acer SunplusIT Integrated Camera                             | 10        | 2%      |
| Sunplus Integrated_Webcam_HD                                 | 7         | 1.4%    |
| Lite-On Integrated Camera                                    | 7         | 1.4%    |
| Chicony HP HD Camera                                         | 7         | 1.4%    |
| Acer BisonCam, NB Pro                                        | 6         | 1.2%    |
| IMC Networks USB2.0 VGA UVC WebCam                           | 5         | 1%      |
| Chicony Integrated Camera (1280x720@30)                      | 5         | 1%      |
| Syntek Integrated Camera                                     | 4         | 0.8%    |
| Realtek Integrated Webcam                                    | 4         | 0.8%    |
| Lenovo Integrated Webcam                                     | 4         | 0.8%    |
| Chicony USB2.0 Camera                                        | 4         | 0.8%    |
| Chicony Lenovo EasyCamera                                    | 4         | 0.8%    |
| Acer Lenovo EasyCamera                                       | 4         | 0.8%    |
| Acer EasyCamera                                              | 4         | 0.8%    |
| Realtek USB Camera                                           | 3         | 0.6%    |
| Quanta HP TrueVision HD Camera                               | 3         | 0.6%    |
| Microdia Integrated Webcam HD                                | 3         | 0.6%    |
| Microdia Integrated Webcam                                   | 3         | 0.6%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera          | 3         | 0.6%    |
| Lite-On HP HD Camera                                         | 3         | 0.6%    |
| IMC Networks UVC VGA Webcam                                  | 3         | 0.6%    |
| IMC Networks ov9734_azurewave_camera                         | 3         | 0.6%    |
| IMC Networks HP TrueVision HD Camera                         | 3         | 0.6%    |
| Chicony HP TrueVision HD Camera                              | 3         | 0.6%    |
| Chicony HP Truevision HD                                     | 3         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 3         | 0.6%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD      | 3         | 0.6%    |
| Apple Built-in iSight                                        | 3         | 0.6%    |
| Acer ThinkPad Integrated Camera                              | 3         | 0.6%    |
| Acer HD Webcam                                               | 3         | 0.6%    |
| Syntek Lenovo EasyCamera                                     | 2         | 0.4%    |
| Suyin Integrated_Webcam_HD                                   | 2         | 0.4%    |
| Suyin Acer/HP Integrated Webcam [CN0314]                     | 2         | 0.4%    |
| Suyin Acer CrystalEye Webcam                                 | 2         | 0.4%    |
| Suyin 1.3M HD WebCam                                         | 2         | 0.4%    |
| Sunplus HP Universal Camera                                  | 2         | 0.4%    |
| Realtek USB2.0 HD UVC WebCam                                 | 2         | 0.4%    |
| Realtek Lenovo EasyCamera                                    | 2         | 0.4%    |
| Realtek Integrated Webcam_HD                                 | 2         | 0.4%    |
| Realtek HD WebCam                                            | 2         | 0.4%    |
| Realtek EasyCamera                                           | 2         | 0.4%    |
| Quanta HP Wide Vision HD Camera                              | 2         | 0.4%    |
| Quanta HP Webcam                                             | 2         | 0.4%    |
| Quanta HD Webcam                                             | 2         | 0.4%    |
| Luxvisions Innotech Limited Integrated Camera                | 2         | 0.4%    |
| Luxvisions Innotech Limited HP HD Camera                     | 2         | 0.4%    |
| Logitech Webcam C270                                         | 2         | 0.4%    |
| Logitech C505 HD Webcam                                      | 2         | 0.4%    |
| Lite-On HP Webcam                                            | 2         | 0.4%    |
| IMC Networks USB2.0 UVC HD Webcam                            | 2         | 0.4%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 44        | 38.94%  |
| Synaptics                  | 28        | 24.78%  |
| Shenzhen Goodix Technology | 20        | 17.7%   |
| Upek                       | 7         | 6.19%   |
| AuthenTec                  | 6         | 5.31%   |
| Elan Microelectronics      | 4         | 3.54%   |
| LighTuning Technology      | 3         | 2.65%   |
| STMicroelectronics         | 1         | 0.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 17.7%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 13        | 11.5%   |
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 9.73%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 7.08%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 7.08%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 6.19%   |
| Shenzhen Goodix FingerPrint                                                | 6         | 5.31%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 4.42%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 4.42%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 3.54%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.54%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 2.65%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 2.65%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 2.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.77%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.77%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.77%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.88%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.88%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 0.88%   |
| Synaptics  WBDI                                                            | 1         | 0.88%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.88%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.88%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 19        | 37.25%  |
| Alcor Micro | 16        | 31.37%  |
| Upek        | 6         | 11.76%  |
| Lenovo      | 6         | 11.76%  |
| O2 Micro    | 2         | 3.92%   |
| OmniKey     | 1         | 1.96%   |
| Cherry      | 1         | 1.96%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 31.37%  |
| Broadcom 5880                                                                | 7         | 13.73%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 6         | 11.76%  |
| Lenovo Integrated Smart Card Reader                                          | 6         | 11.76%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 9.8%    |
| Broadcom 58200                                                               | 5         | 9.8%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 3.92%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 3.92%   |
| OmniKey CardMan 4321                                                         | 1         | 1.96%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 1.96%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 337       | 47.4%   |
| 1     | 315       | 44.3%   |
| 2     | 49        | 6.89%   |
| 3     | 9         | 1.27%   |
| 4     | 1         | 0.14%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Multimedia controller    | 155       | 36.47%  |
| Fingerprint reader       | 113       | 26.59%  |
| Graphics card            | 70        | 16.47%  |
| Chipcard                 | 42        | 9.88%   |
| Net/wireless             | 18        | 4.24%   |
| Bluetooth                | 8         | 1.88%   |
| Communication controller | 6         | 1.41%   |
| Storage                  | 4         | 0.94%   |
| Network                  | 2         | 0.47%   |
| Card reader              | 2         | 0.47%   |
| Tv card                  | 1         | 0.24%   |
| Net/ethernet             | 1         | 0.24%   |
| Modem                    | 1         | 0.24%   |
| Flash memory             | 1         | 0.24%   |
| Firewire controller      | 1         | 0.24%   |

