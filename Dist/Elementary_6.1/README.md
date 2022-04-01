Elementary 6.1 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6.1/Desktop/README.md) and [notebooks](/Dist/Elementary_6.1/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

Total: 393

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 8730w             | Notebook    | [caade8e7ff](https://linux-hardware.org/?probe=caade8e7ff) | Mar 31, 2022 |
| ASUSTek       | UL80VT                      | Notebook    | [bd7c5c01e6](https://linux-hardware.org/?probe=bd7c5c01e6) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [b67f1750b8](https://linux-hardware.org/?probe=b67f1750b8) | Mar 31, 2022 |
| Lenovo        | ThinkCentre M58 6258D3G     | Desktop     | [1cd22c83f1](https://linux-hardware.org/?probe=1cd22c83f1) | Mar 31, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [97f38615e3](https://linux-hardware.org/?probe=97f38615e3) | Mar 31, 2022 |
| MSI           | MEG X570 ACE                | Desktop     | [55572b8a7e](https://linux-hardware.org/?probe=55572b8a7e) | Mar 31, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [513f01a83f](https://linux-hardware.org/?probe=513f01a83f) | Mar 30, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [e617f1e49b](https://linux-hardware.org/?probe=e617f1e49b) | Mar 30, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [5eb56f360e](https://linux-hardware.org/?probe=5eb56f360e) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [01f1ca7f9d](https://linux-hardware.org/?probe=01f1ca7f9d) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d299b01a23](https://linux-hardware.org/?probe=d299b01a23) | Mar 29, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1b9e12b8fb](https://linux-hardware.org/?probe=1b9e12b8fb) | Mar 29, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [c067a4d0e7](https://linux-hardware.org/?probe=c067a4d0e7) | Mar 29, 2022 |
| Acer          | Aspire ES1-520              | Notebook    | [95df1e3190](https://linux-hardware.org/?probe=95df1e3190) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [677a8dfae3](https://linux-hardware.org/?probe=677a8dfae3) | Mar 28, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2f7a9a8ab0](https://linux-hardware.org/?probe=2f7a9a8ab0) | Mar 28, 2022 |
| LG Electro... | 17Z95P-K.AAE8U1             | Notebook    | [0a3f06a9e5](https://linux-hardware.org/?probe=0a3f06a9e5) | Mar 28, 2022 |
| Dell          | Latitude 5520               | Notebook    | [ca6e0db25d](https://linux-hardware.org/?probe=ca6e0db25d) | Mar 27, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ac055e5e8a](https://linux-hardware.org/?probe=ac055e5e8a) | Mar 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [0521ab3bd7](https://linux-hardware.org/?probe=0521ab3bd7) | Mar 27, 2022 |
| Sony          | VPCCA4E1E                   | Notebook    | [95fc0956c8](https://linux-hardware.org/?probe=95fc0956c8) | Mar 27, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [9e39c749a1](https://linux-hardware.org/?probe=9e39c749a1) | Mar 27, 2022 |
| Toshiba       | Satellite C70D-A            | Notebook    | [c8b872d005](https://linux-hardware.org/?probe=c8b872d005) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [33ae998152](https://linux-hardware.org/?probe=33ae998152) | Mar 26, 2022 |
| Dell          | 0C522T A00                  | Desktop     | [90242bb090](https://linux-hardware.org/?probe=90242bb090) | Mar 26, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7ca2f5d5cb](https://linux-hardware.org/?probe=7ca2f5d5cb) | Mar 26, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [7577679057](https://linux-hardware.org/?probe=7577679057) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | Notebook    | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [744a69ec7d](https://linux-hardware.org/?probe=744a69ec7d) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a237859a86](https://linux-hardware.org/?probe=a237859a86) | Mar 24, 2022 |
| Intel         | X79Turbo V1.x               | Desktop     | [18b126a753](https://linux-hardware.org/?probe=18b126a753) | Mar 24, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [1535349482](https://linux-hardware.org/?probe=1535349482) | Mar 24, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [552f06718c](https://linux-hardware.org/?probe=552f06718c) | Mar 23, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [dd34f9d506](https://linux-hardware.org/?probe=dd34f9d506) | Mar 23, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [bbea34ce64](https://linux-hardware.org/?probe=bbea34ce64) | Mar 22, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [552d30ae49](https://linux-hardware.org/?probe=552d30ae49) | Mar 22, 2022 |
| Sony          | SVP1321B4E                  | Notebook    | [b539c23011](https://linux-hardware.org/?probe=b539c23011) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [2b39b0fda2](https://linux-hardware.org/?probe=2b39b0fda2) | Mar 21, 2022 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [9054ee5a3d](https://linux-hardware.org/?probe=9054ee5a3d) | Mar 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [78df63a35f](https://linux-hardware.org/?probe=78df63a35f) | Mar 20, 2022 |
| AMI           | Cherry Trail CR             | Desktop     | [bc5a34ef7e](https://linux-hardware.org/?probe=bc5a34ef7e) | Mar 20, 2022 |
| Dell          | Inspiron 5481               | Convertible | [7292765d92](https://linux-hardware.org/?probe=7292765d92) | Mar 20, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [6806f47a62](https://linux-hardware.org/?probe=6806f47a62) | Mar 19, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7d4d2482ed](https://linux-hardware.org/?probe=7d4d2482ed) | Mar 18, 2022 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [1268effe7d](https://linux-hardware.org/?probe=1268effe7d) | Mar 17, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [7f5053b061](https://linux-hardware.org/?probe=7f5053b061) | Mar 16, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [7b2fa4b8e8](https://linux-hardware.org/?probe=7b2fa4b8e8) | Mar 16, 2022 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [7ff55a3ca6](https://linux-hardware.org/?probe=7ff55a3ca6) | Mar 16, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [f4d49b97ec](https://linux-hardware.org/?probe=f4d49b97ec) | Mar 15, 2022 |
| Dell          | Latitude E6220              | Notebook    | [e2c9477eb3](https://linux-hardware.org/?probe=e2c9477eb3) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [a10cf12536](https://linux-hardware.org/?probe=a10cf12536) | Mar 15, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [eda8848760](https://linux-hardware.org/?probe=eda8848760) | Mar 15, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [c95c5598af](https://linux-hardware.org/?probe=c95c5598af) | Mar 15, 2022 |
| AOpen         | D1009 A1A4                  | Desktop     | [a7375d4581](https://linux-hardware.org/?probe=a7375d4581) | Mar 13, 2022 |
| Acer          | Aspire A315-21G             | Notebook    | [4e85fcd677](https://linux-hardware.org/?probe=4e85fcd677) | Mar 13, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [4a24f1b828](https://linux-hardware.org/?probe=4a24f1b828) | Mar 13, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [9eb7577acd](https://linux-hardware.org/?probe=9eb7577acd) | Mar 12, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [7f9721781e](https://linux-hardware.org/?probe=7f9721781e) | Mar 12, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [bc5d95b759](https://linux-hardware.org/?probe=bc5d95b759) | Mar 12, 2022 |
| MSI           | B85I                        | Desktop     | [d134c8451b](https://linux-hardware.org/?probe=d134c8451b) | Mar 12, 2022 |
| Teclast       | F15S                        | Notebook    | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [12459fc7ea](https://linux-hardware.org/?probe=12459fc7ea) | Mar 11, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [85c103c654](https://linux-hardware.org/?probe=85c103c654) | Mar 10, 2022 |
| ASUSTek       | X200CA                      | Notebook    | [25518274da](https://linux-hardware.org/?probe=25518274da) | Mar 10, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [a64818ccea](https://linux-hardware.org/?probe=a64818ccea) | Mar 10, 2022 |
| Biostar       | N68S3B                      | Desktop     | [aa1e6a4c82](https://linux-hardware.org/?probe=aa1e6a4c82) | Mar 10, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [b950d195ce](https://linux-hardware.org/?probe=b950d195ce) | Mar 10, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [1064e67665](https://linux-hardware.org/?probe=1064e67665) | Mar 10, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [83dc415e28](https://linux-hardware.org/?probe=83dc415e28) | Mar 09, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [e6a6f71bb5](https://linux-hardware.org/?probe=e6a6f71bb5) | Mar 09, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [ee3693d6a7](https://linux-hardware.org/?probe=ee3693d6a7) | Mar 09, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [8bb5baaa5a](https://linux-hardware.org/?probe=8bb5baaa5a) | Mar 09, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fc064cce68](https://linux-hardware.org/?probe=fc064cce68) | Mar 09, 2022 |
| Microsoft     | Surface Laptop 3            | Tablet      | [d55f23484e](https://linux-hardware.org/?probe=d55f23484e) | Mar 09, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [661d068b83](https://linux-hardware.org/?probe=661d068b83) | Mar 08, 2022 |
| Biostar       | H61MLV2                     | Desktop     | [d5c330bad8](https://linux-hardware.org/?probe=d5c330bad8) | Mar 08, 2022 |
| HP            | 2ADC                        | Desktop     | [ed0714a64a](https://linux-hardware.org/?probe=ed0714a64a) | Mar 07, 2022 |
| MSI           | B85I                        | Desktop     | [39926596b7](https://linux-hardware.org/?probe=39926596b7) | Mar 07, 2022 |
| Lenovo        | ThinkPad L470 20J4002FMX    | Notebook    | [c3e1baf45a](https://linux-hardware.org/?probe=c3e1baf45a) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [8a9f469e1e](https://linux-hardware.org/?probe=8a9f469e1e) | Mar 06, 2022 |
| Lenovo        | ThinkPad T420 4236JY2       | Notebook    | [caa5c3eef1](https://linux-hardware.org/?probe=caa5c3eef1) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [766b0e4665](https://linux-hardware.org/?probe=766b0e4665) | Mar 06, 2022 |
| Dell          | 0PU052                      | Desktop     | [a8e19bd112](https://linux-hardware.org/?probe=a8e19bd112) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [02818352e0](https://linux-hardware.org/?probe=02818352e0) | Mar 06, 2022 |
| iOTA          | IOTA2320                    | Notebook    | [6cf7733a53](https://linux-hardware.org/?probe=6cf7733a53) | Mar 06, 2022 |
| Lenovo        | ThinkPad X230 2325ND9       | Notebook    | [24a601d3aa](https://linux-hardware.org/?probe=24a601d3aa) | Mar 06, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [7e967f4daa](https://linux-hardware.org/?probe=7e967f4daa) | Mar 06, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [db5f524190](https://linux-hardware.org/?probe=db5f524190) | Mar 06, 2022 |
| HP            | 1589                        | Desktop     | [88876808e9](https://linux-hardware.org/?probe=88876808e9) | Mar 05, 2022 |
| Acer          | Nitro AN517-52              | Notebook    | [4576110ce4](https://linux-hardware.org/?probe=4576110ce4) | Mar 05, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [707b59278e](https://linux-hardware.org/?probe=707b59278e) | Mar 05, 2022 |
| HP            | 802E                        | Desktop     | [14c73a40e0](https://linux-hardware.org/?probe=14c73a40e0) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [0b7875b1b5](https://linux-hardware.org/?probe=0b7875b1b5) | Mar 05, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [d08f8cbc35](https://linux-hardware.org/?probe=d08f8cbc35) | Mar 05, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [4fc1001606](https://linux-hardware.org/?probe=4fc1001606) | Mar 02, 2022 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [6a5d0584bd](https://linux-hardware.org/?probe=6a5d0584bd) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [9cfd9c7142](https://linux-hardware.org/?probe=9cfd9c7142) | Mar 02, 2022 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [a93699018b](https://linux-hardware.org/?probe=a93699018b) | Mar 02, 2022 |
| HP            | 805D                        | Desktop     | [2a09665009](https://linux-hardware.org/?probe=2a09665009) | Mar 02, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [1f32b0aa84](https://linux-hardware.org/?probe=1f32b0aa84) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [ef94f0dd4d](https://linux-hardware.org/?probe=ef94f0dd4d) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| MSI           | B85I                        | Desktop     | [24674e9e3a](https://linux-hardware.org/?probe=24674e9e3a) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Intel         | DH61BE AAG14062-210         | Desktop     | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| MSI           | B85I                        | Desktop     | [633f6bf495](https://linux-hardware.org/?probe=633f6bf495) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| ASUSTek       | P5B                         | Desktop     | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel         | H61                         | Desktop     | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | Desktop     | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | Notebook    | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| MSI           | B85I                        | Desktop     | [28c1f1b8ae](https://linux-hardware.org/?probe=28c1f1b8ae) | Feb 13, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | Notebook    | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| MSI           | B85I                        | Desktop     | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Dell          | Precision 7720              | Notebook    | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Google        | Lulu                        | Notebook    | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| Sony          | SVE15115EN                  | Notebook    | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [0caedcc26b](https://linux-hardware.org/?probe=0caedcc26b) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| BANGHO        | Suma 1025                   | Tablet      | [585ea8c657](https://linux-hardware.org/?probe=585ea8c657) | Feb 10, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| Timi          | TM1613                      | Notebook    | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| Dell          | Inspiron 5481               | Convertible | [1f266a5183](https://linux-hardware.org/?probe=1f266a5183) | Feb 08, 2022 |
| ECS           | H55H-M                      | Desktop     | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | Notebook    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | Notebook    | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f7500c309c](https://linux-hardware.org/?probe=f7500c309c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [a933b9c8f4](https://linux-hardware.org/?probe=a933b9c8f4) | Feb 05, 2022 |
| HP            | 802E                        | Desktop     | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | Notebook    | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | P5B                         | Desktop     | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | 82A5                        | Mini pc     | [c47d9b3ae0](https://linux-hardware.org/?probe=c47d9b3ae0) | Feb 03, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [4d2233f824](https://linux-hardware.org/?probe=4d2233f824) | Feb 03, 2022 |
| HP            | 339A                        | Desktop     | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| ASUSTek       | K95VJ                       | Notebook    | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | Notebook    | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | Notebook    | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| HP            | 805D                        | Desktop     | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Teclast       | X6 plus                     | Tablet      | [a84fba541b](https://linux-hardware.org/?probe=a84fba541b) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| MSI           | Z270 KRAIT GAMING           | Desktop     | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [124dcb4c34](https://linux-hardware.org/?probe=124dcb4c34) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [804f9dbb94](https://linux-hardware.org/?probe=804f9dbb94) | Jan 26, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | Notebook    | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| Lenovo        | G550 20023                  | Notebook    | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| FIRICH        | J1900                       | Desktop     | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| HP            | ProBook 4540s               | Notebook    | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [a0fdaf761c](https://linux-hardware.org/?probe=a0fdaf761c) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [f7c8c966dc](https://linux-hardware.org/?probe=f7c8c966dc) | Jan 17, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| Dell          | Latitude E5400              | Notebook    | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | Notebook    | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | Notebook    | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| ASUSTek       | H61M-CS                     | Desktop     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [fae944592d](https://linux-hardware.org/?probe=fae944592d) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [de61623232](https://linux-hardware.org/?probe=de61623232) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | Notebook    | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | Notebook    | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| Star Labs     | StarBook                    | Notebook    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | Notebook    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [27756cb751](https://linux-hardware.org/?probe=27756cb751) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | Notebook    | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | Notebook    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | Notebook    | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [1172390e59](https://linux-hardware.org/?probe=1172390e59) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [c91feb11a8](https://linux-hardware.org/?probe=c91feb11a8) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | Notebook    | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | Notebook    | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | Notebook    | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| MSI           | 2A9C                        | Desktop     | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | Notebook    | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| HP            | 3397                        | Desktop     | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| Wortmann      | 1220729_1470271             | Notebook    | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| HP            | 1589                        | Desktop     | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [829dc5243a](https://linux-hardware.org/?probe=829dc5243a) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [352c62bd8f](https://linux-hardware.org/?probe=352c62bd8f) | Dec 28, 2021 |
| Dell          | Latitude 3580               | Notebook    | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5d91acd13d](https://linux-hardware.org/?probe=5d91acd13d) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [730558c6bd](https://linux-hardware.org/?probe=730558c6bd) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | Notebook    | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [64d2a0328e](https://linux-hardware.org/?probe=64d2a0328e) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | Notebook    | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [d9077a5d94](https://linux-hardware.org/?probe=d9077a5d94) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | Notebook    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [3371572aa9](https://linux-hardware.org/?probe=3371572aa9) | Dec 16, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.11.0-43-generic          | 83        | 26.43%  |
| 5.13.0-28-generic          | 54        | 17.2%   |
| 5.13.0-30-generic          | 39        | 12.42%  |
| 5.13.0-27-generic          | 33        | 10.51%  |
| 5.13.0-35-generic          | 22        | 7.01%   |
| 5.11.0-44-generic          | 17        | 5.41%   |
| 5.13.0-37-generic          | 16        | 5.1%    |
| 5.11.0-46-generic          | 12        | 3.82%   |
| 5.11.0-41-generic          | 10        | 3.18%   |
| 5.13.0-25-generic          | 4         | 1.27%   |
| 5.13.0-39-generic          | 3         | 0.96%   |
| 5.11.0-40-generic          | 2         | 0.64%   |
| 5.8.0-50-generic           | 1         | 0.32%   |
| 5.4.0-1055-raspi           | 1         | 0.32%   |
| 5.16.16-051616-generic     | 1         | 0.32%   |
| 5.16.11-surface            | 1         | 0.32%   |
| 5.16.10-051610-generic     | 1         | 0.32%   |
| 5.16.0-13.4-liquorix-amd64 | 1         | 0.32%   |
| 5.15.6-surface             | 1         | 0.32%   |
| 5.15.3-xanmod1             | 1         | 0.32%   |
| 5.15.13-xanmod1            | 1         | 0.32%   |
| 5.15.12-xanmod1-tt         | 1         | 0.32%   |
| 5.15.11-t2-big-sur         | 1         | 0.32%   |
| 5.15.10-xanmod1            | 1         | 0.32%   |
| 5.14.10-051410-generic     | 1         | 0.32%   |
| 5.14.0-1029-oem            | 1         | 0.32%   |
| 5.14.0-1011-oem            | 1         | 0.32%   |
| 5.13.0-28-lowlatency       | 1         | 0.32%   |
| 5.13.0-22-generic          | 1         | 0.32%   |
| 5.11.0-43-lowlatency       | 1         | 0.32%   |
| 5.11.0-37-generic          | 1         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13.0  | 164       | 54.13%  |
| 5.11.0  | 124       | 40.92%  |
| 5.14.0  | 2         | 0.66%   |
| 5.8.0   | 1         | 0.33%   |
| 5.4.0   | 1         | 0.33%   |
| 5.16.16 | 1         | 0.33%   |
| 5.16.11 | 1         | 0.33%   |
| 5.16.10 | 1         | 0.33%   |
| 5.16.0  | 1         | 0.33%   |
| 5.15.6  | 1         | 0.33%   |
| 5.15.3  | 1         | 0.33%   |
| 5.15.13 | 1         | 0.33%   |
| 5.15.12 | 1         | 0.33%   |
| 5.15.11 | 1         | 0.33%   |
| 5.15.10 | 1         | 0.33%   |
| 5.14.10 | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.13    | 164       | 54.3%   |
| 5.11    | 124       | 41.06%  |
| 5.15    | 6         | 1.99%   |
| 5.16    | 3         | 0.99%   |
| 5.14    | 3         | 0.99%   |
| 5.8     | 1         | 0.33%   |
| 5.4     | 1         | 0.33%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 297       | 99.66%  |
| aarch64 | 1         | 0.34%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 298       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 298       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 234       | 78.26%  |
| LightDM | 64        | 21.4%   |
| GDM     | 1         | 0.33%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 135       | 45.3%   |
| de_DE | 46        | 15.44%  |
| es_ES | 17        | 5.7%    |
| en_GB | 17        | 5.7%    |
| fr_FR | 14        | 4.7%    |
| ru_RU | 12        | 4.03%   |
| pt_BR | 10        | 3.36%   |
| it_IT | 10        | 3.36%   |
| pl_PL | 8         | 2.68%   |
| pt_PT | 4         | 1.34%   |
| en_AU | 4         | 1.34%   |
| tr_TR | 3         | 1.01%   |
| en_CA | 3         | 1.01%   |
| sv_SE | 2         | 0.67%   |
| nl_NL | 2         | 0.67%   |
| nb_NO | 2         | 0.67%   |
| sr_RS | 1         | 0.34%   |
| ja_JP | 1         | 0.34%   |
| hu_HU | 1         | 0.34%   |
| hr_HR | 1         | 0.34%   |
| fr_CA | 1         | 0.34%   |
| et_EE | 1         | 0.34%   |
| cs_CZ | 1         | 0.34%   |
| C     | 1         | 0.34%   |
| bg_BG | 1         | 0.34%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 201       | 67.45%  |
| BIOS | 97        | 32.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 289       | 96.98%  |
| Btrfs   | 7         | 2.35%   |
| Xfs     | 1         | 0.34%   |
| Overlay | 1         | 0.34%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 247       | 82.61%  |
| GPT     | 46        | 15.38%  |
| MBR     | 6         | 2.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 288       | 96.64%  |
| Yes       | 10        | 3.36%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 277       | 92.95%  |
| Yes       | 21        | 7.05%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 49        | 16.44%  |
| ASUSTek Computer        | 44        | 14.77%  |
| Hewlett-Packard         | 35        | 11.74%  |
| Apple                   | 33        | 11.07%  |
| Dell                    | 25        | 8.39%   |
| Acer                    | 18        | 6.04%   |
| MSI                     | 15        | 5.03%   |
| Gigabyte Technology     | 13        | 4.36%   |
| HUAWEI                  | 7         | 2.35%   |
| Sony                    | 5         | 1.68%   |
| ASRock                  | 5         | 1.68%   |
| Samsung Electronics     | 4         | 1.34%   |
| Microsoft               | 4         | 1.34%   |
| Intel                   | 4         | 1.34%   |
| Toshiba                 | 3         | 1.01%   |
| Teclast                 | 3         | 1.01%   |
| Biostar                 | 3         | 1.01%   |
| Timi                    | 2         | 0.67%   |
| Star Labs               | 2         | 0.67%   |
| Notebook                | 2         | 0.67%   |
| Monster                 | 2         | 0.67%   |
| LG Electronics          | 2         | 0.67%   |
| Foxconn                 | 2         | 0.67%   |
| Unknown                 | 2         | 0.67%   |
| Wortmann AG             | 1         | 0.34%   |
| Razer                   | 1         | 0.34%   |
| Raspberry Pi Foundation | 1         | 0.34%   |
| PIPO                    | 1         | 0.34%   |
| Packard Bell            | 1         | 0.34%   |
| iOTA                    | 1         | 0.34%   |
| Google                  | 1         | 0.34%   |
| Fujitsu                 | 1         | 0.34%   |
| FIRICH                  | 1         | 0.34%   |
| ECS                     | 1         | 0.34%   |
| BANGHO                  | 1         | 0.34%   |
| AOpen                   | 1         | 0.34%   |
| AMI                     | 1         | 0.34%   |
| Acidanthera             | 1         | 0.34%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Apple MacBook5,1                                  | 4         | 1.34%   |
| HUAWEI MACHD-WXX9                                 | 3         | 1.01%   |
| Timi TM1613                                       | 2         | 0.67%   |
| Lenovo IdeaPad 310-15IKB 80TV                     | 2         | 0.67%   |
| HP EliteBook 8460p                                | 2         | 0.67%   |
| Gigabyte Z390 UD                                  | 2         | 0.67%   |
| Dell Inspiron N5050                               | 2         | 0.67%   |
| Dell Inspiron 15-3567                             | 2         | 0.67%   |
| ASUS X550CA                                       | 2         | 0.67%   |
| ASUS TUF GAMING B550M-PLUS                        | 2         | 0.67%   |
| ASUS All Series                                   | 2         | 0.67%   |
| Apple MacBookPro8,2                               | 2         | 0.67%   |
| Apple MacBookPro6,2                               | 2         | 0.67%   |
| Apple MacBookPro5,5                               | 2         | 0.67%   |
| Apple MacBookAir7,1                               | 2         | 0.67%   |
| Apple iMac9,1                                     | 2         | 0.67%   |
| Unknown                                           | 2         | 0.67%   |
| Wortmann AG 1220729_1470271                       | 1         | 0.34%   |
| Toshiba Satellite L850D-BJS                       | 1         | 0.34%   |
| Toshiba Satellite L50D-C                          | 1         | 0.34%   |
| Toshiba Satellite C70D-A                          | 1         | 0.34%   |
| Teclast X6 plus                                   | 1         | 0.34%   |
| Teclast F7                                        | 1         | 0.34%   |
| Teclast F15S                                      | 1         | 0.34%   |
| Star Labs StarBook                                | 1         | 0.34%   |
| Star Labs LabTop                                  | 1         | 0.34%   |
| Sony VPCEA3S1E                                    | 1         | 0.34%   |
| Sony VPCCA4E1E                                    | 1         | 0.34%   |
| Sony SVP1321B4E                                   | 1         | 0.34%   |
| Sony SVE15115EN                                   | 1         | 0.34%   |
| Sony SVE14A390X                                   | 1         | 0.34%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411       | 1         | 0.34%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D        | 1         | 0.34%   |
| Samsung 870Z5E/880Z5E/680Z5E                      | 1         | 0.34%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.34%   |
| Razer Blade Stealth                               | 1         | 0.34%   |
| RPi Raspberry Pi                                  | 1         | 0.34%   |
| PIPO W9                                           | 1         | 0.34%   |
| Packard Bell EasyNote LS11HR                      | 1         | 0.34%   |
| Notebook W65_67SJ                                 | 1         | 0.34%   |
| Notebook P65xHP                                   | 1         | 0.34%   |
| MSI PS63 Modern 8RD                               | 1         | 0.34%   |
| MSI PPPPP-CCC#MMMMMMMM                            | 1         | 0.34%   |
| MSI MS-7C91                                       | 1         | 0.34%   |
| MSI MS-7C52                                       | 1         | 0.34%   |
| MSI MS-7C35                                       | 1         | 0.34%   |
| MSI MS-7C02                                       | 1         | 0.34%   |
| MSI MS-7B86                                       | 1         | 0.34%   |
| MSI MS-7B79                                       | 1         | 0.34%   |
| MSI MS-7A59                                       | 1         | 0.34%   |
| MSI MS-7A40                                       | 1         | 0.34%   |
| MSI MS-7918                                       | 1         | 0.34%   |
| MSI MS-7851                                       | 1         | 0.34%   |
| MSI Modern 14 B4MW                                | 1         | 0.34%   |
| MSI Modern 14 B10MW                               | 1         | 0.34%   |
| MSI GF63 Thin 9SCSR                               | 1         | 0.34%   |
| Monster MARKUT M7 V1.x                            | 1         | 0.34%   |
| Monster ABRA A5 V13.2                             | 1         | 0.34%   |
| Microsoft Surface with Windows 8 Pro              | 1         | 0.34%   |
| Microsoft Surface Laptop 3                        | 1         | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 22        | 7.38%   |
| Lenovo IdeaPad      | 15        | 5.03%   |
| Dell Inspiron       | 11        | 3.69%   |
| Acer Aspire         | 10        | 3.36%   |
| HP EliteBook        | 6         | 2.01%   |
| ASUS VivoBook       | 6         | 2.01%   |
| HP Pavilion         | 5         | 1.68%   |
| Dell Latitude       | 5         | 1.68%   |
| Apple MacBook5      | 5         | 1.68%   |
| Microsoft Surface   | 4         | 1.34%   |
| HP ProBook          | 4         | 1.34%   |
| HP Laptop           | 4         | 1.34%   |
| Dell Precision      | 4         | 1.34%   |
| Acer Swift          | 4         | 1.34%   |
| Toshiba Satellite   | 3         | 1.01%   |
| HUAWEI MACHD-WXX9   | 3         | 1.01%   |
| HP ProDesk          | 3         | 1.01%   |
| ASUS ZenBook        | 3         | 1.01%   |
| ASUS TUF            | 3         | 1.01%   |
| ASUS PRIME          | 3         | 1.01%   |
| Apple MacBookPro8   | 3         | 1.01%   |
| Apple MacBookPro5   | 3         | 1.01%   |
| Apple MacBookAir7   | 3         | 1.01%   |
| Timi TM1613         | 2         | 0.67%   |
| MSI Modern          | 2         | 0.67%   |
| Lenovo ThinkCentre  | 2         | 0.67%   |
| Lenovo Legion       | 2         | 0.67%   |
| Lenovo G550         | 2         | 0.67%   |
| HP ProLiant         | 2         | 0.67%   |
| HP ENVY             | 2         | 0.67%   |
| HP Compaq           | 2         | 0.67%   |
| Gigabyte Z390       | 2         | 0.67%   |
| Dell Vostro         | 2         | 0.67%   |
| Dell OptiPlex       | 2         | 0.67%   |
| ASUS X550CA         | 2         | 0.67%   |
| ASUS ROG            | 2         | 0.67%   |
| ASUS All            | 2         | 0.67%   |
| Apple MacBookPro9   | 2         | 0.67%   |
| Apple MacBookPro6   | 2         | 0.67%   |
| Apple MacBookAir6   | 2         | 0.67%   |
| Apple iMac9         | 2         | 0.67%   |
| Acer Nitro          | 2         | 0.67%   |
| Unknown             | 2         | 0.67%   |
| Wortmann AG 1220729 | 1         | 0.34%   |
| Teclast X6          | 1         | 0.34%   |
| Teclast F7          | 1         | 0.34%   |
| Teclast F15S        | 1         | 0.34%   |
| Star Labs StarBook  | 1         | 0.34%   |
| Star Labs LabTop    | 1         | 0.34%   |
| Sony VPCEA3S1E      | 1         | 0.34%   |
| Sony VPCCA4E1E      | 1         | 0.34%   |
| Sony SVP1321B4E     | 1         | 0.34%   |
| Sony SVE15115EN     | 1         | 0.34%   |
| Sony SVE14A390X     | 1         | 0.34%   |
| Samsung RV411       | 1         | 0.34%   |
| Samsung 900X3C      | 1         | 0.34%   |
| Samsung 870Z5E      | 1         | 0.34%   |
| Samsung 500R4K      | 1         | 0.34%   |
| Razer Blade         | 1         | 0.34%   |
| RPi Raspberry       | 1         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 39        | 13.09%  |
| 2018    | 31        | 10.4%   |
| 2019    | 25        | 8.39%   |
| 2012    | 24        | 8.05%   |
| 2015    | 23        | 7.72%   |
| 2021    | 22        | 7.38%   |
| 2011    | 21        | 7.05%   |
| 2017    | 19        | 6.38%   |
| 2016    | 19        | 6.38%   |
| 2014    | 19        | 6.38%   |
| 2013    | 16        | 5.37%   |
| 2009    | 15        | 5.03%   |
| 2010    | 14        | 4.7%    |
| 2008    | 6         | 2.01%   |
| 2007    | 2         | 0.67%   |
| 2006    | 2         | 0.67%   |
| Unknown | 1         | 0.34%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 196       | 65.77%  |
| Desktop        | 77        | 25.84%  |
| Tablet         | 8         | 2.68%   |
| All in one     | 8         | 2.68%   |
| Convertible    | 5         | 1.68%   |
| Mini pc        | 2         | 0.67%   |
| System on chip | 1         | 0.34%   |
| Server         | 1         | 0.34%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 260       | 87.25%  |
| Enabled  | 38        | 12.75%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 295       | 98.99%  |
| Yes  | 3         | 1.01%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 99        | 33.11%  |
| 3.01-4.0    | 58        | 19.4%   |
| 16.01-24.0  | 53        | 17.73%  |
| 8.01-16.0   | 47        | 15.72%  |
| 32.01-64.0  | 24        | 8.03%   |
| 1.01-2.0    | 11        | 3.68%   |
| 24.01-32.0  | 3         | 1%      |
| 64.01-256.0 | 3         | 1%      |
| 2.01-3.0    | 1         | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 119       | 38.02%  |
| 2.01-3.0   | 95        | 30.35%  |
| 3.01-4.0   | 44        | 14.06%  |
| 4.01-8.0   | 32        | 10.22%  |
| 0.51-1.0   | 12        | 3.83%   |
| 8.01-16.0  | 9         | 2.88%   |
| 24.01-32.0 | 1         | 0.32%   |
| 16.01-24.0 | 1         | 0.32%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 190       | 63.12%  |
| 2      | 79        | 26.25%  |
| 3      | 16        | 5.32%   |
| 4      | 8         | 2.66%   |
| 5      | 3         | 1%      |
| 7      | 2         | 0.66%   |
| 6      | 2         | 0.66%   |
| 0      | 1         | 0.33%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 197       | 65.67%  |
| Yes       | 103       | 34.33%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 228       | 76.51%  |
| No        | 70        | 23.49%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 251       | 84.23%  |
| No        | 47        | 15.77%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 228       | 76.51%  |
| No        | 70        | 23.49%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 43        | 14.43%  |
| USA          | 37        | 12.42%  |
| Russia       | 16        | 5.37%   |
| India        | 15        | 5.03%   |
| UK           | 14        | 4.7%    |
| Brazil       | 14        | 4.7%    |
| Italy        | 13        | 4.36%   |
| Australia    | 11        | 3.69%   |
| France       | 10        | 3.36%   |
| Spain        | 9         | 3.02%   |
| Poland       | 9         | 3.02%   |
| Turkey       | 8         | 2.68%   |
| Indonesia    | 8         | 2.68%   |
| Austria      | 8         | 2.68%   |
| Canada       | 7         | 2.35%   |
| New Zealand  | 4         | 1.34%   |
| Mexico       | 4         | 1.34%   |
| Czechia      | 4         | 1.34%   |
| Argentina    | 4         | 1.34%   |
| Switzerland  | 3         | 1.01%   |
| Sweden       | 3         | 1.01%   |
| South Africa | 3         | 1.01%   |
| Netherlands  | 3         | 1.01%   |
| Belgium      | 3         | 1.01%   |
| Serbia       | 2         | 0.67%   |
| Romania      | 2         | 0.67%   |
| Portugal     | 2         | 0.67%   |
| Norway       | 2         | 0.67%   |
| Japan        | 2         | 0.67%   |
| Iran         | 2         | 0.67%   |
| Colombia     | 2         | 0.67%   |
| Chile        | 2         | 0.67%   |
| Bulgaria     | 2         | 0.67%   |
| Belarus      | 2         | 0.67%   |
| Vietnam      | 1         | 0.34%   |
| Ukraine      | 1         | 0.34%   |
| Thailand     | 1         | 0.34%   |
| Taiwan       | 1         | 0.34%   |
| Sri Lanka    | 1         | 0.34%   |
| Peru         | 1         | 0.34%   |
| Pakistan     | 1         | 0.34%   |
| Nicaragua    | 1         | 0.34%   |
| Mozambique   | 1         | 0.34%   |
| Malaysia     | 1         | 0.34%   |
| Luxembourg   | 1         | 0.34%   |
| Lithuania    | 1         | 0.34%   |
| Latvia       | 1         | 0.34%   |
| Kenya        | 1         | 0.34%   |
| Israel       | 1         | 0.34%   |
| Ireland      | 1         | 0.34%   |
| Iceland      | 1         | 0.34%   |
| Hungary      | 1         | 0.34%   |
| Hong Kong    | 1         | 0.34%   |
| Guyana       | 1         | 0.34%   |
| Greece       | 1         | 0.34%   |
| Finland      | 1         | 0.34%   |
| Estonia      | 1         | 0.34%   |
| Egypt        | 1         | 0.34%   |
| Croatia      | 1         | 0.34%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Sydney                  | 7         | 2.26%   |
| Munich                  | 5         | 1.61%   |
| Warsaw                  | 4         | 1.29%   |
| Vienna                  | 4         | 1.29%   |
| Moscow                  | 4         | 1.29%   |
| Ankara                  | 4         | 1.29%   |
| St Petersburg           | 3         | 0.97%   |
| Madrid                  | 3         | 0.97%   |
| Wolgast                 | 2         | 0.65%   |
| Wellington              | 2         | 0.65%   |
| Tucson                  | 2         | 0.65%   |
| Sao Paulo               | 2         | 0.65%   |
| Paris                   | 2         | 0.65%   |
| Muralto                 | 2         | 0.65%   |
| Minsk                   | 2         | 0.65%   |
| London                  | 2         | 0.65%   |
| Jakarta                 | 2         | 0.65%   |
| Hamburg                 | 2         | 0.65%   |
| Dresden                 | 2         | 0.65%   |
| Brisbane                | 2         | 0.65%   |
| Berlin                  | 2         | 0.65%   |
| Antalya                 | 2         | 0.65%   |
| Znojmo                  | 1         | 0.32%   |
| Wroclaw                 | 1         | 0.32%   |
| Wriedel                 | 1         | 0.32%   |
| Woolloongabba           | 1         | 0.32%   |
| Wonosari                | 1         | 0.32%   |
| Witbank                 | 1         | 0.32%   |
| West Bromwich           | 1         | 0.32%   |
| Wattala                 | 1         | 0.32%   |
| VitÃ³ria da Conquista | 1         | 0.32%   |
| Vinnytsia               | 1         | 0.32%   |
| Vilanova i la GeltrÃº | 1         | 0.32%   |
| Vila Nova de Gaia       | 1         | 0.32%   |
| Vigodarzere             | 1         | 0.32%   |
| Vantaa                  | 1         | 0.32%   |
| Valencia                | 1         | 0.32%   |
| Uppsala                 | 1         | 0.32%   |
| Ulyanovsk               | 1         | 0.32%   |
| Ubstadt-Weiher          | 1         | 0.32%   |
| Tromsø                 | 1         | 0.32%   |
| Trieste                 | 1         | 0.32%   |
| Treviso                 | 1         | 0.32%   |
| Tournus                 | 1         | 0.32%   |
| Tongeren                | 1         | 0.32%   |
| Tomsk                   | 1         | 0.32%   |
| Thrissur                | 1         | 0.32%   |
| The Hague               | 1         | 0.32%   |
| Tel Aviv                | 1         | 0.32%   |
| Tehran                  | 1         | 0.32%   |
| Tecuci                  | 1         | 0.32%   |
| Tangerang               | 1         | 0.32%   |
| Surrey                  | 1         | 0.32%   |
| Suresnes                | 1         | 0.32%   |
| Surabaya                | 1         | 0.32%   |
| Stronsdorf              | 1         | 0.32%   |
| Strasbourg              | 1         | 0.32%   |
| Stockholm               | 1         | 0.32%   |
| Steinbach               | 1         | 0.32%   |
| Spello                  | 1         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 65        | 83     | 15.51%  |
| WDC                       | 48        | 65     | 11.46%  |
| Seagate                   | 45        | 51     | 10.74%  |
| Kingston                  | 33        | 37     | 7.88%   |
| SanDisk                   | 30        | 33     | 7.16%   |
| Toshiba                   | 25        | 27     | 5.97%   |
| Crucial                   | 21        | 22     | 5.01%   |
| Unknown                   | 17        | 25     | 4.06%   |
| SK Hynix                  | 11        | 11     | 2.63%   |
| Apple                     | 10        | 11     | 2.39%   |
| Intel                     | 9         | 10     | 2.15%   |
| Hitachi                   | 9         | 9      | 2.15%   |
| HGST                      | 9         | 9      | 2.15%   |
| A-DATA Technology         | 7         | 7      | 1.67%   |
| PNY                       | 5         | 8      | 1.19%   |
| Phison                    | 5         | 5      | 1.19%   |
| Micron Technology         | 5         | 5      | 1.19%   |
| Unknown                   | 5         | 6      | 1.19%   |
| KIOXIA                    | 4         | 4      | 0.95%   |
| Transcend                 | 3         | 3      | 0.72%   |
| Leven                     | 3         | 3      | 0.72%   |
| China                     | 3         | 3      | 0.72%   |
| ASMT                      | 3         | 3      | 0.72%   |
| Teclast                   | 2         | 2      | 0.48%   |
| Netac                     | 2         | 2      | 0.48%   |
| Micron/Crucial Technology | 2         | 3      | 0.48%   |
| LITEON                    | 2         | 2      | 0.48%   |
| KingDian                  | 2         | 2      | 0.48%   |
| JMicron                   | 2         | 2      | 0.48%   |
| Fujitsu                   | 2         | 2      | 0.48%   |
| XPG                       | 1         | 1      | 0.24%   |
| TO Exter                  | 1         | 1      | 0.24%   |
| Team                      | 1         | 1      | 0.24%   |
| Star Drive                | 1         | 1      | 0.24%   |
| Star                      | 1         | 1      | 0.24%   |
| SSK                       | 1         | 1      | 0.24%   |
| SSDPR-CX                  | 1         | 1      | 0.24%   |
| SPCC                      | 1         | 1      | 0.24%   |
| Smartbuy                  | 1         | 1      | 0.24%   |
| Silicon Motion            | 1         | 1      | 0.24%   |
| SABRENT                   | 1         | 1      | 0.24%   |
| Realtek Semiconductor     | 1         | 1      | 0.24%   |
| PLEXTOR                   | 1         | 1      | 0.24%   |
| Pichau                    | 1         | 1      | 0.24%   |
| OCZ                       | 1         | 1      | 0.24%   |
| NGFF                      | 1         | 1      | 0.24%   |
| MidasForce                | 1         | 1      | 0.24%   |
| MENGMI                    | 1         | 1      | 0.24%   |
| MAXTOR                    | 1         | 1      | 0.24%   |
| KingSpec                  | 1         | 1      | 0.24%   |
| Intenso                   | 1         | 1      | 0.24%   |
| Hewlett-Packard           | 1         | 1      | 0.24%   |
| GOODRAM                   | 1         | 1      | 0.24%   |
| Gigabyte Technology       | 1         | 1      | 0.24%   |
| Ext Hard                  | 1         | 1      | 0.24%   |
| Dogfish                   | 1         | 1      | 0.24%   |
| Corsair                   | 1         | 1      | 0.24%   |
| Colorful                  | 1         | 1      | 0.24%   |
| asmedia                   | 1         | 1      | 0.24%   |
| Apacer                    | 1         | 1      | 0.24%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 256GB         | 8         | 1.79%   |
| Kingston SA400S37240G 240GB SSD      | 7         | 1.57%   |
| Seagate ST1000LM035-1RK172 1TB       | 6         | 1.35%   |
| Sandisk NVMe SSD Drive 512GB         | 6         | 1.35%   |
| Samsung NVMe SSD Drive 512GB         | 6         | 1.35%   |
| Kingston SA400S37120G 120GB SSD      | 6         | 1.35%   |
| Samsung SSD 850 EVO 250GB            | 5         | 1.12%   |
| Samsung NVMe SSD Drive 500GB         | 5         | 1.12%   |
| Crucial CT240BX500SSD1 240GB         | 5         | 1.12%   |
| Unknown                              | 5         | 1.12%   |
| Unknown MMC Card  32GB               | 4         | 0.9%    |
| SK Hynix NVMe SSD Drive 512GB        | 4         | 0.9%    |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 4         | 0.9%    |
| Intel NVMe SSD Drive 512GB           | 4         | 0.9%    |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 3         | 0.67%   |
| Unknown MMC Card  128GB              | 3         | 0.67%   |
| Toshiba NVMe SSD Drive 512GB         | 3         | 0.67%   |
| Toshiba MQ04ABF100 1TB               | 3         | 0.67%   |
| Toshiba MQ01ABF050 500GB             | 3         | 0.67%   |
| Toshiba DT01ACA050 500GB             | 3         | 0.67%   |
| SK Hynix NVMe SSD Drive 256GB        | 3         | 0.67%   |
| Seagate ST500LT012-1DG142 500GB      | 3         | 0.67%   |
| Samsung SSD 860 EVO 250GB            | 3         | 0.67%   |
| PNY CS900 480GB SSD                  | 3         | 0.67%   |
| Kingston NVMe SSD Drive 500GB        | 3         | 0.67%   |
| HGST HTS541010B7E610 1TB             | 3         | 0.67%   |
| Crucial CT1000MX500SSD1 1TB          | 3         | 0.67%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 2         | 0.45%   |
| WDC WD5000AAKX-00ERMA0 500GB         | 2         | 0.45%   |
| WDC WD40EFRX-68N32N0 4TB             | 2         | 0.45%   |
| Unknown SD/MMC 16GB                  | 2         | 0.45%   |
| Unknown M.S./M.S.Pro/HG 16GB         | 2         | 0.45%   |
| Toshiba NVMe SSD Drive 256GB         | 2         | 0.45%   |
| Toshiba HDWD110 1TB                  | 2         | 0.45%   |
| Seagate ST9500325AS 500GB            | 2         | 0.45%   |
| Seagate ST3500418AS 500GB            | 2         | 0.45%   |
| Seagate ST2000DX002-2DV164 2TB       | 2         | 0.45%   |
| Seagate ST1000DM003-1ER162 1TB       | 2         | 0.45%   |
| Seagate OneTouch HDD 4TB             | 2         | 0.45%   |
| Seagate Expansion Desk 4TB           | 2         | 0.45%   |
| SanDisk SSD PLUS 240GB               | 2         | 0.45%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD  | 2         | 0.45%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD  | 2         | 0.45%   |
| Sandisk NVMe SSD Drive 1TB           | 2         | 0.45%   |
| Sandisk NVMe SSD Drive 1024GB        | 2         | 0.45%   |
| Samsung SSD 860 EVO 500GB            | 2         | 0.45%   |
| Samsung SSD 860 EVO 1TB              | 2         | 0.45%   |
| Samsung SSD 850 EVO 120GB            | 2         | 0.45%   |
| Samsung SSD 840 EVO 120GB            | 2         | 0.45%   |
| Samsung NVMe SSD Drive 1TB           | 2         | 0.45%   |
| Samsung NVMe SSD Drive 1024GB        | 2         | 0.45%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD | 2         | 0.45%   |
| Samsung HD322HJ 320GB                | 2         | 0.45%   |
| PNY CS900 120GB SSD                  | 2         | 0.45%   |
| Phison NVMe SSD Drive 512GB          | 2         | 0.45%   |
| Phison NVMe SSD Drive 1TB            | 2         | 0.45%   |
| Micron/Crucial NVMe SSD Drive 1TB    | 2         | 0.45%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD  | 2         | 0.45%   |
| Kingston SV300S37A120G 120GB SSD     | 2         | 0.45%   |
| Kingston NVMe SSD Drive 1TB          | 2         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 44        | 50     | 34.38%  |
| WDC                 | 36        | 46     | 28.13%  |
| Toshiba             | 17        | 18     | 13.28%  |
| Hitachi             | 9         | 9      | 7.03%   |
| HGST                | 9         | 9      | 7.03%   |
| Samsung Electronics | 3         | 4      | 2.34%   |
| Fujitsu             | 2         | 2      | 1.56%   |
| ASMT                | 2         | 2      | 1.56%   |
| Apple               | 2         | 2      | 1.56%   |
| Unknown             | 1         | 1      | 0.78%   |
| SABRENT             | 1         | 1      | 0.78%   |
| Hewlett-Packard     | 1         | 1      | 0.78%   |
| Ext Hard            | 1         | 1      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 39        | 46     | 22.81%  |
| Kingston            | 23        | 24     | 13.45%  |
| Crucial             | 21        | 22     | 12.28%  |
| SanDisk             | 17        | 19     | 9.94%   |
| WDC                 | 9         | 13     | 5.26%   |
| Apple               | 8         | 8      | 4.68%   |
| A-DATA Technology   | 6         | 6      | 3.51%   |
| PNY                 | 5         | 8      | 2.92%   |
| Micron Technology   | 4         | 4      | 2.34%   |
| Transcend           | 3         | 3      | 1.75%   |
| China               | 3         | 3      | 1.75%   |
| Toshiba             | 2         | 2      | 1.17%   |
| Teclast             | 2         | 2      | 1.17%   |
| LITEON              | 2         | 2      | 1.17%   |
| Leven               | 2         | 2      | 1.17%   |
| Intel               | 2         | 2      | 1.17%   |
| TO Exter            | 1         | 1      | 0.58%   |
| Team                | 1         | 1      | 0.58%   |
| Star                | 1         | 1      | 0.58%   |
| SPCC                | 1         | 1      | 0.58%   |
| Smartbuy            | 1         | 1      | 0.58%   |
| PLEXTOR             | 1         | 1      | 0.58%   |
| Pichau              | 1         | 1      | 0.58%   |
| OCZ                 | 1         | 1      | 0.58%   |
| NGFF                | 1         | 1      | 0.58%   |
| Netac               | 1         | 1      | 0.58%   |
| MidasForce          | 1         | 1      | 0.58%   |
| MENGMI              | 1         | 1      | 0.58%   |
| MAXTOR              | 1         | 1      | 0.58%   |
| KingSpec            | 1         | 1      | 0.58%   |
| KingDian            | 1         | 1      | 0.58%   |
| Intenso             | 1         | 1      | 0.58%   |
| GOODRAM             | 1         | 1      | 0.58%   |
| Gigabyte Technology | 1         | 1      | 0.58%   |
| Dogfish             | 1         | 1      | 0.58%   |
| Corsair             | 1         | 1      | 0.58%   |
| Colorful            | 1         | 1      | 0.58%   |
| Apacer              | 1         | 1      | 0.58%   |
| Unknown             | 1         | 1      | 0.58%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 157       | 189    | 39.75%  |
| HDD     | 116       | 146    | 29.37%  |
| NVMe    | 92        | 110    | 23.29%  |
| MMC     | 16        | 19     | 4.05%   |
| Unknown | 14        | 21     | 3.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 228       | 327    | 64.04%  |
| NVMe | 92        | 110    | 25.84%  |
| SAS  | 20        | 29     | 5.62%   |
| MMC  | 16        | 19     | 4.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 177       | 230    | 68.08%  |
| 0.51-1.0   | 57        | 73     | 21.92%  |
| 1.01-2.0   | 13        | 17     | 5%      |
| 3.01-4.0   | 9         | 10     | 3.46%   |
| 2.01-3.0   | 2         | 3      | 0.77%   |
| 4.01-10.0  | 2         | 2      | 0.77%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 115       | 38.33%  |
| 251-500        | 82        | 27.33%  |
| 501-1000       | 40        | 13.33%  |
| 51-100         | 23        | 7.67%   |
| 1001-2000      | 19        | 6.33%   |
| 21-50          | 13        | 4.33%   |
| More than 3000 | 7         | 2.33%   |
| 2001-3000      | 1         | 0.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 139       | 45.13%  |
| 21-50          | 71        | 23.05%  |
| 101-250        | 33        | 10.71%  |
| 51-100         | 33        | 10.71%  |
| 251-500        | 15        | 4.87%   |
| 501-1000       | 10        | 3.25%   |
| 1001-2000      | 4         | 1.3%    |
| 2001-3000      | 2         | 0.65%   |
| More than 3000 | 1         | 0.32%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB                  | 1         | 1      | 14.29%  |
| Toshiba KBG30ZPZ128G 128GB              | 1         | 1      | 14.29%  |
| Seagate ST500LM030-2E717D 500GB         | 1         | 1      | 14.29%  |
| Seagate ST3500312CS 500GB               | 1         | 1      | 14.29%  |
| SanDisk SSD PLUS 240GB                  | 1         | 1      | 14.29%  |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1      | 14.29%  |
| Crucial CT512M550SSD3 512GB             | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 2         | 2      | 28.57%  |
| WDC      | 1         | 1      | 14.29%  |
| Toshiba  | 1         | 1      | 14.29%  |
| SanDisk  | 1         | 1      | 14.29%  |
| Kingston | 1         | 1      | 14.29%  |
| Crucial  | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 3         | 3      | 42.86%  |
| HDD  | 3         | 3      | 42.86%  |
| NVMe | 1         | 1      | 14.29%  |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 260       | 410    | 82.54%  |
| Works    | 48        | 68     | 15.24%  |
| Malfunc  | 7         | 7      | 2.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 196       | 54.6%   |
| AMD                          | 49        | 13.65%  |
| Samsung Electronics          | 31        | 8.64%   |
| Sandisk                      | 16        | 4.46%   |
| Nvidia                       | 13        | 3.62%   |
| SK Hynix                     | 11        | 3.06%   |
| Kingston Technology Company  | 11        | 3.06%   |
| Toshiba America Info Systems | 6         | 1.67%   |
| Phison Electronics           | 6         | 1.67%   |
| Marvell Technology Group     | 4         | 1.11%   |
| ASMedia Technology           | 3         | 0.84%   |
| Realtek Semiconductor        | 2         | 0.56%   |
| Micron/Crucial Technology    | 2         | 0.56%   |
| KIOXIA                       | 2         | 0.56%   |
| Silicon Motion               | 1         | 0.28%   |
| Seagate Technology           | 1         | 0.28%   |
| Micron Technology            | 1         | 0.28%   |
| JMicron Technology           | 1         | 0.28%   |
| Hewlett-Packard              | 1         | 0.28%   |
| Apple                        | 1         | 0.28%   |
| ADATA Technology             | 1         | 0.28%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 38        | 9.62%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 18        | 4.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 17        | 4.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 15        | 3.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14        | 3.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 11        | 2.78%   |
| Samsung NVMe SSD Controller 980                                                         | 9         | 2.28%   |
| Nvidia MCP79 AHCI Controller                                                            | 9         | 2.28%   |
| AMD 400 Series Chipset SATA Controller                                                  | 9         | 2.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 8         | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 8         | 2.03%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 1.77%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7         | 1.77%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7         | 1.77%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 7         | 1.77%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 6         | 1.52%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 6         | 1.52%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 5         | 1.27%   |
| Intel SSD 660P Series                                                                   | 5         | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 1.27%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 5         | 1.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 1.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.27%   |
| SK Hynix BC511                                                                          | 4         | 1.01%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 4         | 1.01%   |
| Kingston Company A2000 NVMe SSD                                                         | 4         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 4         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 4         | 1.01%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 4         | 1.01%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 3         | 0.76%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 3         | 0.76%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.76%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3         | 0.76%   |
| Samsung Electronics SATA controller                                                     | 3         | 0.76%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.76%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 3         | 0.76%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 0.76%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 0.76%   |
| SK Hynix Gold P31 SSD                                                                   | 2         | 0.51%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.51%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 0.51%   |
| Sandisk Non-Volatile memory controller                                                  | 2         | 0.51%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 0.51%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.51%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 2         | 0.51%   |
| Marvell Group 88SS9183 PCIe SSD Controller                                              | 2         | 0.51%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 0.51%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2         | 0.51%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 2         | 0.51%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 2         | 0.51%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 2         | 0.51%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.51%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 234       | 64.11%  |
| NVMe | 90        | 24.66%  |
| IDE  | 27        | 7.4%    |
| RAID | 13        | 3.56%   |
| SAS  | 1         | 0.27%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 233       | 78.19%  |
| AMD    | 64        | 21.48%  |
| ARM    | 1         | 0.34%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 7         | 2.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 6         | 2.01%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 5         | 1.68%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 4         | 1.34%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 4         | 1.34%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 4         | 1.34%   |
| Intel Core i5-10210U CPU @ 1.60GHz              | 4         | 1.34%   |
| Intel Celeron CPU N3050 @ 1.60GHz               | 4         | 1.34%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 4         | 1.34%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 3         | 1.01%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 3         | 1.01%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 3         | 1.01%   |
| Intel Core i3-8145U CPU @ 2.10GHz               | 3         | 1.01%   |
| Intel Core i3-10110U CPU @ 2.10GHz              | 3         | 1.01%   |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz            | 3         | 1.01%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 3         | 1.01%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 3         | 1.01%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 3         | 1.01%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 1.01%   |
| AMD Ryzen 5 4500U with Radeon Graphics          | 3         | 1.01%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 3         | 1.01%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 3         | 1.01%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 2         | 0.67%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 2         | 0.67%   |
| Intel Core i7-9700 CPU @ 3.00GHz                | 2         | 0.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 0.67%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 2         | 0.67%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 2         | 0.67%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 2         | 0.67%   |
| Intel Core i7-5650U CPU @ 2.20GHz               | 2         | 0.67%   |
| Intel Core i7-3630QM CPU @ 2.40GHz              | 2         | 0.67%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 2         | 0.67%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 2         | 0.67%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 2         | 0.67%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 2         | 0.67%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 0.67%   |
| Intel Core i5-4260U CPU @ 1.40GHz               | 2         | 0.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz               | 2         | 0.67%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 2         | 0.67%   |
| Intel Core i3 CPU M 350 @ 2.27GHz               | 2         | 0.67%   |
| Intel Core i3 CPU 530 @ 2.93GHz                 | 2         | 0.67%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 2         | 0.67%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz         | 2         | 0.67%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 0.67%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 0.67%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 2         | 0.67%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 2         | 0.67%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G    | 2         | 0.67%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G    | 2         | 0.67%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 0.67%   |
| Intel Xeon CPU E5462 @ 2.80GHz                  | 1         | 0.34%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz              | 1         | 0.34%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz              | 1         | 0.34%   |
| Intel Xeon CPU E5-2665 0 @ 2.40GHz              | 1         | 0.34%   |
| Intel Xeon CPU E5-1660 0 @ 3.30GHz              | 1         | 0.34%   |
| Intel Xeon CPU E31270 @ 3.40GHz                 | 1         | 0.34%   |
| Intel Xeon CPU E31240 @ 3.30GHz                 | 1         | 0.34%   |
| Intel Xeon CPU E3-1230 v3 @ 3.30GHz             | 1         | 0.34%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 0.34%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 64        | 21.48%  |
| Intel Core i7           | 60        | 20.13%  |
| Intel Core i3           | 31        | 10.4%   |
| Intel Celeron           | 20        | 6.71%   |
| AMD Ryzen 5             | 19        | 6.38%   |
| Intel Core 2 Duo        | 18        | 6.04%   |
| Other                   | 16        | 5.37%   |
| AMD Ryzen 7             | 11        | 3.69%   |
| Intel Xeon              | 8         | 2.68%   |
| Intel Pentium           | 5         | 1.68%   |
| Intel Atom              | 5         | 1.68%   |
| AMD Ryzen 3             | 5         | 1.68%   |
| AMD Ryzen 9             | 3         | 1.01%   |
| AMD Ryzen 7 PRO         | 3         | 1.01%   |
| AMD Phenom II X4        | 3         | 1.01%   |
| AMD A6                  | 3         | 1.01%   |
| AMD A10                 | 3         | 1.01%   |
| Intel Pentium Silver    | 2         | 0.67%   |
| Intel Pentium Dual-Core | 2         | 0.67%   |
| Intel Core 2 Quad       | 2         | 0.67%   |
| AMD Athlon              | 2         | 0.67%   |
| AMD A8                  | 2         | 0.67%   |
| AMD A12                 | 2         | 0.67%   |
| Intel Genuine           | 1         | 0.34%   |
| Intel Core m5           | 1         | 0.34%   |
| Intel Core 2            | 1         | 0.34%   |
| Intel Celeron Dual-Core | 1         | 0.34%   |
| AMD FX                  | 1         | 0.34%   |
| AMD E1                  | 1         | 0.34%   |
| AMD Athlon X4           | 1         | 0.34%   |
| AMD Athlon II X2        | 1         | 0.34%   |
| AMD A4                  | 1         | 0.34%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 136       | 45.64%  |
| 4      | 110       | 36.91%  |
| 6      | 24        | 8.05%   |
| 8      | 23        | 7.72%   |
| 12     | 2         | 0.67%   |
| 1      | 2         | 0.67%   |
| 16     | 1         | 0.34%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 296       | 99.33%  |
| 2      | 2         | 0.67%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 198       | 66.44%  |
| 1      | 100       | 33.56%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 297       | 99.66%  |
| 64-bit         | 1         | 0.34%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 27        | 9%      |
| Unknown    | 24        | 8%      |
| 0x306a9    | 19        | 6.33%   |
| 0x1067a    | 15        | 5%      |
| 0x306c3    | 12        | 4%      |
| 0x306d4    | 10        | 3.33%   |
| 0x806ec    | 9         | 3%      |
| 0x806c1    | 9         | 3%      |
| 0x406e3    | 8         | 2.67%   |
| 0x40651    | 8         | 2.67%   |
| 0x20655    | 7         | 2.33%   |
| 0x10676    | 7         | 2.33%   |
| 0x08600106 | 7         | 2.33%   |
| 0x906ea    | 6         | 2%      |
| 0x806ea    | 6         | 2%      |
| 0x806e9    | 6         | 2%      |
| 0x506e3    | 6         | 2%      |
| 0x406c3    | 6         | 2%      |
| 0x08701021 | 6         | 2%      |
| 0x906e9    | 5         | 1.67%   |
| 0x806eb    | 5         | 1.67%   |
| 0x506c9    | 5         | 1.67%   |
| 0x08108109 | 5         | 1.67%   |
| 0x706a8    | 4         | 1.33%   |
| 0x206d7    | 4         | 1.33%   |
| 0x20652    | 4         | 1.33%   |
| 0x08108102 | 4         | 1.33%   |
| 0x06006705 | 4         | 1.33%   |
| 0xa0652    | 3         | 1%      |
| 0x906ed    | 3         | 1%      |
| 0x406c4    | 3         | 1%      |
| 0x08608103 | 3         | 1%      |
| 0xa0671    | 2         | 0.67%   |
| 0x906eb    | 2         | 0.67%   |
| 0x706e5    | 2         | 0.67%   |
| 0x6fb      | 2         | 0.67%   |
| 0x30678    | 2         | 0.67%   |
| 0x106e5    | 2         | 0.67%   |
| 0x08101007 | 2         | 0.67%   |
| 0x0800820d | 2         | 0.67%   |
| 0x0700010f | 2         | 0.67%   |
| 0x06003106 | 2         | 0.67%   |
| 0x06001119 | 2         | 0.67%   |
| 0x010000c8 | 2         | 0.67%   |
| 0xa0660    | 1         | 0.33%   |
| 0x906ec    | 1         | 0.33%   |
| 0x906c0    | 1         | 0.33%   |
| 0x806c2    | 1         | 0.33%   |
| 0x706a1    | 1         | 0.33%   |
| 0x6fd      | 1         | 0.33%   |
| 0x6fa      | 1         | 0.33%   |
| 0x6f2      | 1         | 0.33%   |
| 0x40661    | 1         | 0.33%   |
| 0x306e4    | 1         | 0.33%   |
| 0x106ca    | 1         | 0.33%   |
| 0x0a50000c | 1         | 0.33%   |
| 0x0a201009 | 1         | 0.33%   |
| 0x08701013 | 1         | 0.33%   |
| 0x08600104 | 1         | 0.33%   |
| 0x08101016 | 1         | 0.33%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 51        | 17.11%  |
| SandyBridge   | 32        | 10.74%  |
| Haswell       | 23        | 7.72%   |
| Penryn        | 22        | 7.38%   |
| IvyBridge     | 20        | 6.71%   |
| Zen 2         | 19        | 6.38%   |
| Skylake       | 15        | 5.03%   |
| Zen+          | 13        | 4.36%   |
| Silvermont    | 12        | 4.03%   |
| Westmere      | 11        | 3.69%   |
| TigerLake     | 10        | 3.36%   |
| Broadwell     | 10        | 3.36%   |
| Excavator     | 8         | 2.68%   |
| Zen           | 5         | 1.68%   |
| Goldmont plus | 5         | 1.68%   |
| Goldmont      | 5         | 1.68%   |
| Core          | 5         | 1.68%   |
| Unknown       | 5         | 1.68%   |
| K10           | 4         | 1.34%   |
| IceLake       | 4         | 1.34%   |
| CometLake     | 4         | 1.34%   |
| Zen 3         | 2         | 0.67%   |
| Steamroller   | 2         | 0.67%   |
| Puma          | 2         | 0.67%   |
| Piledriver    | 2         | 0.67%   |
| Nehalem       | 2         | 0.67%   |
| Jaguar        | 2         | 0.67%   |
| Tremont       | 1         | 0.34%   |
| Bulldozer     | 1         | 0.34%   |
| Bonnell       | 1         | 0.34%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 179       | 51%     |
| AMD                        | 87        | 24.79%  |
| Nvidia                     | 84        | 23.93%  |
| Matrox Electronics Systems | 1         | 0.28%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 24        | 6.63%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 3.87%   |
| AMD Renoir                                                                               | 11        | 3.04%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 2.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 2.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 9         | 2.49%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 9         | 2.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 2.21%   |
| Intel UHD Graphics 620                                                                   | 8         | 2.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 2.21%   |
| Nvidia C79 [GeForce 9400M]                                                               | 7         | 1.93%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 1.93%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.93%   |
| Intel HD Graphics 5500                                                                   | 7         | 1.93%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 1.93%   |
| Intel HD Graphics 620                                                                    | 6         | 1.66%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.38%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.38%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 5         | 1.38%   |
| Intel HD Graphics 630                                                                    | 4         | 1.1%    |
| Intel HD Graphics 530                                                                    | 4         | 1.1%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.1%    |
| AMD Lucienne                                                                             | 4         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 0.83%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 3         | 0.83%   |
| Intel HD Graphics 6000                                                                   | 3         | 0.83%   |
| Intel HD Graphics 500                                                                    | 3         | 0.83%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.83%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 0.83%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.83%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.83%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 0.83%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 3         | 0.83%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 3         | 0.83%   |
| Nvidia TU117M                                                                            | 2         | 0.55%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.55%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 2         | 0.55%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.55%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.55%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.55%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.55%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.55%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.55%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.55%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.55%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.55%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.55%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 2         | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.55%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 0.55%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.55%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.55%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.55%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.55%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2         | 0.55%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 2         | 0.55%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 0.55%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.28%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 128       | 42.81%  |
| 1 x AMD        | 67        | 22.41%  |
| 1 x Nvidia     | 43        | 14.38%  |
| Intel + Nvidia | 38        | 12.71%  |
| Intel + AMD    | 11        | 3.68%   |
| 2 x AMD        | 7         | 2.34%   |
| AMD + Nvidia   | 2         | 0.67%   |
| Other          | 1         | 0.33%   |
| 2 x Nvidia     | 1         | 0.33%   |
| 1 x Matrox     | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 256       | 85.62%  |
| Proprietary | 40        | 13.38%  |
| Unknown     | 3         | 1%      |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 150       | 50%     |
| 0.01-0.5   | 42        | 14%     |
| 1.01-2.0   | 40        | 13.33%  |
| 0.51-1.0   | 27        | 9%      |
| 3.01-4.0   | 24        | 8%      |
| 7.01-8.0   | 7         | 2.33%   |
| 5.01-6.0   | 6         | 2%      |
| 2.01-3.0   | 2         | 0.67%   |
| 8.01-16.0  | 2         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 48        | 14.29%  |
| LG Display              | 37        | 11.01%  |
| Apple                   | 32        | 9.52%   |
| Chimei Innolux          | 29        | 8.63%   |
| Samsung Electronics     | 27        | 8.04%   |
| BOE                     | 24        | 7.14%   |
| Hewlett-Packard         | 14        | 4.17%   |
| Acer                    | 14        | 4.17%   |
| Goldstar                | 13        | 3.87%   |
| Dell                    | 12        | 3.57%   |
| Sharp                   | 9         | 2.68%   |
| Philips                 | 8         | 2.38%   |
| Lenovo                  | 8         | 2.38%   |
| BenQ                    | 7         | 2.08%   |
| PANDA                   | 6         | 1.79%   |
| CSO                     | 4         | 1.19%   |
| AOC                     | 4         | 1.19%   |
| Ancor Communications    | 4         | 1.19%   |
| Chi Mei Optoelectronics | 3         | 0.89%   |
| ViewSonic               | 2         | 0.6%    |
| Panasonic               | 2         | 0.6%    |
| InfoVision              | 2         | 0.6%    |
| AUS                     | 2         | 0.6%    |
| ___                     | 1         | 0.3%    |
| Vizio                   | 1         | 0.3%    |
| Vestel                  | 1         | 0.3%    |
| Unknown                 | 1         | 0.3%    |
| Toshiba                 | 1         | 0.3%    |
| SPC                     | 1         | 0.3%    |
| Sony                    | 1         | 0.3%    |
| Packard Bell            | 1         | 0.3%    |
| MSI                     | 1         | 0.3%    |
| Mi                      | 1         | 0.3%    |
| Marantz                 | 1         | 0.3%    |
| LG Electronics          | 1         | 0.3%    |
| Konka                   | 1         | 0.3%    |
| JDI                     | 1         | 0.3%    |
| IOD                     | 1         | 0.3%    |
| Iiyama                  | 1         | 0.3%    |
| HUAWEI                  | 1         | 0.3%    |
| HPN                     | 1         | 0.3%    |
| Fujitsu Siemens         | 1         | 0.3%    |
| Element                 | 1         | 0.3%    |
| Eizo                    | 1         | 0.3%    |
| CPT                     | 1         | 0.3%    |
| CHR                     | 1         | 0.3%    |
| CHD                     | 1         | 0.3%    |
| Unknown                 | 1         | 0.3%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 1.16%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 256x144mm 11.6-inch  | 3         | 0.87%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 3         | 0.87%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                 | 3         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.87%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.87%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 3         | 0.87%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.87%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                | 3         | 0.87%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 2         | 0.58%   |
| Panasonic VVX13F009G00 MEI96A2 1920x1080 344x193mm 15.5-inch          | 2         | 0.58%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch          | 2         | 0.58%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 2         | 0.58%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch           | 2         | 0.58%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch            | 2         | 0.58%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.58%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                 | 2         | 0.58%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 2         | 0.58%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 0.58%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.58%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                 | 2         | 0.58%   |
| BenQ EL2870U BNQ7949 3840x2160 621x341mm 27.9-inch                    | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO313C 1366x768 309x173mm 13.9-inch         | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch         | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 2         | 0.58%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch        | 2         | 0.58%   |
| Apple LCD Monitor APP9CA3 1440x900 331x207mm 15.4-inch                | 2         | 0.58%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 2         | 0.58%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 2         | 0.58%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 2         | 0.58%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                  | 2         | 0.58%   |
| ___ LCD TV ___9000 1360x768                                           | 1         | 0.29%   |
| Vizio M322i-B1 VIZ1005 1920x1080 698x392mm 31.5-inch                  | 1         | 0.29%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch             | 1         | 0.29%   |
| ViewSonic LCD Monitor VX2260WM 3840x1080                              | 1         | 0.29%   |
| ViewSonic LCD Monitor VX2260WM                                        | 1         | 0.29%   |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                             | 1         | 0.29%   |
| Unknown LCDTV16 9000 1360x768 1600x900mm 72.3-inch                    | 1         | 0.29%   |
| Toshiba TV TSB2019 3840x2160                                          | 1         | 0.29%   |
| SPC LCD Monitor SPC1900 1440x900 368x207mm 16.6-inch                  | 1         | 0.29%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                 | 1         | 0.29%   |
| Sharp PN-K321 SHP21DD 3840x2160                                       | 1         | 0.29%   |
| Sharp LQ150P1JX51 SHP14B4 2496x1664 317x211mm 15.0-inch               | 1         | 0.29%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch               | 1         | 0.29%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch               | 1         | 0.29%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 697x392mm 31.5-inch     | 1         | 0.29%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch     | 1         | 0.29%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch     | 1         | 0.29%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch  | 1         | 0.29%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch  | 1         | 0.29%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch     | 1         | 0.29%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch     | 1         | 0.29%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch  | 1         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch  | 1         | 0.29%   |
| Samsung Electronics LCD Monitor SEC3242 1920x1080 235x132mm 10.6-inch | 1         | 0.29%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 127       | 38.84%  |
| 1366x768 (WXGA)    | 75        | 22.94%  |
| 2560x1440 (QHD)    | 22        | 6.73%   |
| 3840x2160 (4K)     | 20        | 6.12%   |
| 1600x900 (HD+)     | 13        | 3.98%   |
| 1440x900 (WXGA+)   | 13        | 3.98%   |
| 1680x1050 (WSXGA+) | 11        | 3.36%   |
| 1280x800 (WXGA)    | 11        | 3.36%   |
| 1920x1200 (WUXGA)  | 5         | 1.53%   |
| 3000x2000          | 4         | 1.22%   |
| 1360x768           | 3         | 0.92%   |
| Unknown            | 3         | 0.92%   |
| 3840x1080          | 2         | 0.61%   |
| 3440x1440          | 2         | 0.61%   |
| 2560x1600          | 2         | 0.61%   |
| 2560x1080          | 2         | 0.61%   |
| 1920x1280          | 2         | 0.61%   |
| 7680x2160          | 1         | 0.31%   |
| 3840x2400          | 1         | 0.31%   |
| 3200x1800 (QHD+)   | 1         | 0.31%   |
| 3072x1920          | 1         | 0.31%   |
| 2880x1920          | 1         | 0.31%   |
| 2880x1800          | 1         | 0.31%   |
| 2496x1664          | 1         | 0.31%   |
| 1920x540           | 1         | 0.31%   |
| 1800x1200          | 1         | 0.31%   |
| 1280x1024 (SXGA)   | 1         | 0.31%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 90        | 26.95%  |
| 13      | 50        | 14.97%  |
| 14      | 33        | 9.88%   |
| 27      | 20        | 5.99%   |
| 24      | 17        | 5.09%   |
| Unknown | 16        | 4.79%   |
| 23      | 15        | 4.49%   |
| 17      | 14        | 4.19%   |
| 21      | 13        | 3.89%   |
| 22      | 8         | 2.4%    |
| 31      | 7         | 2.1%    |
| 11      | 7         | 2.1%    |
| 12      | 6         | 1.8%    |
| 18      | 5         | 1.5%    |
| 34      | 4         | 1.2%    |
| 20      | 4         | 1.2%    |
| 32      | 3         | 0.9%    |
| 26      | 3         | 0.9%    |
| 25      | 3         | 0.9%    |
| 16      | 3         | 0.9%    |
| 10      | 3         | 0.9%    |
| 72      | 2         | 0.6%    |
| 19      | 2         | 0.6%    |
| 65      | 1         | 0.3%    |
| 55      | 1         | 0.3%    |
| 52      | 1         | 0.3%    |
| 48      | 1         | 0.3%    |
| 47      | 1         | 0.3%    |
| 43      | 1         | 0.3%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 141       | 42.73%  |
| 501-600     | 51        | 15.45%  |
| 201-300     | 47        | 14.24%  |
| 401-500     | 31        | 9.39%   |
| 351-400     | 18        | 5.45%   |
| Unknown     | 16        | 4.85%   |
| 601-700     | 11        | 3.33%   |
| 701-800     | 7         | 2.12%   |
| 1001-1500   | 5         | 1.52%   |
| 1501-2000   | 2         | 0.61%   |
| 901-1000    | 1         | 0.3%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 229       | 75.83%  |
| 16/10   | 46        | 15.23%  |
| Unknown | 13        | 4.3%    |
| 3/2     | 10        | 3.31%   |
| 21/9    | 4         | 1.32%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 87        | 26.36%  |
| 81-90          | 63        | 19.09%  |
| 201-250        | 40        | 12.12%  |
| 71-80          | 21        | 6.36%   |
| 301-350        | 21        | 6.36%   |
| Unknown        | 16        | 4.85%   |
| 351-500        | 14        | 4.24%   |
| 251-300        | 12        | 3.64%   |
| 121-130        | 11        | 3.33%   |
| 151-200        | 9         | 2.73%   |
| 51-60          | 7         | 2.12%   |
| More than 1000 | 6         | 1.82%   |
| 61-70          | 5         | 1.52%   |
| 141-150        | 4         | 1.21%   |
| 111-120        | 4         | 1.21%   |
| 41-50          | 3         | 0.91%   |
| 131-140        | 3         | 0.91%   |
| 501-1000       | 2         | 0.61%   |
| 91-100         | 2         | 0.61%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 101       | 30.89%  |
| 101-120       | 98        | 29.97%  |
| 51-100        | 72        | 22.02%  |
| 161-240       | 21        | 6.42%   |
| Unknown       | 16        | 4.89%   |
| More than 240 | 12        | 3.67%   |
| 1-50          | 7         | 2.14%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 254       | 84.95%  |
| 2     | 38        | 12.71%  |
| 3     | 6         | 2.01%   |
| 0     | 1         | 0.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 145       | 33.56%  |
| Intel                             | 133       | 30.79%  |
| Qualcomm Atheros                  | 48        | 11.11%  |
| Broadcom                          | 44        | 10.19%  |
| Nvidia                            | 11        | 2.55%   |
| Broadcom Limited                  | 9         | 2.08%   |
| Marvell Technology Group          | 6         | 1.39%   |
| TP-Link                           | 4         | 0.93%   |
| Ralink Technology                 | 4         | 0.93%   |
| Ralink                            | 4         | 0.93%   |
| Xiaomi                            | 3         | 0.69%   |
| Samsung Electronics               | 3         | 0.69%   |
| Google                            | 2         | 0.46%   |
| Sitecom Europe                    | 1         | 0.23%   |
| Sierra Wireless                   | 1         | 0.23%   |
| OPPO Electronics                  | 1         | 0.23%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.23%   |
| Motorola PCS                      | 1         | 0.23%   |
| Microsoft                         | 1         | 0.23%   |
| MEDIATEK                          | 1         | 0.23%   |
| Linksys                           | 1         | 0.23%   |
| LG Electronics                    | 1         | 0.23%   |
| Huawei Technologies               | 1         | 0.23%   |
| Hewlett-Packard                   | 1         | 0.23%   |
| Ericsson Business Mobile Networks | 1         | 0.23%   |
| D-Link System                     | 1         | 0.23%   |
| AVM                               | 1         | 0.23%   |
| ASIX Electronics                  | 1         | 0.23%   |
| Apple                             | 1         | 0.23%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 94        | 18.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 20        | 3.94%   |
| Intel Wi-Fi 6 AX200                                               | 14        | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 2.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 11        | 2.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 10        | 1.97%   |
| Nvidia MCP79 Ethernet                                             | 10        | 1.97%   |
| Intel Wireless 8260                                               | 10        | 1.97%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.77%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 9         | 1.77%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 8         | 1.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7         | 1.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 1.38%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.18%   |
| Intel Wireless 7265                                               | 6         | 1.18%   |
| Intel Wireless 7260                                               | 6         | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.18%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 1.18%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 1.18%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 6         | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 5         | 0.98%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 0.98%   |
| Intel Wireless 3165                                               | 5         | 0.98%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 5         | 0.98%   |
| Realtek 802.11ac NIC                                              | 4         | 0.79%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.79%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.79%   |
| Intel I211 Gigabit Network Connection                             | 4         | 0.79%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.79%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.59%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.59%   |
| Intel Wireless-AC 9260                                            | 3         | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.59%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.59%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 3         | 0.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.59%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.59%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 0.59%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 3         | 0.59%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 3         | 0.59%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.39%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 2         | 0.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.39%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.39%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 2         | 0.39%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.39%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.39%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.39%   |
| Intel Wireless 3160                                               | 2         | 0.39%   |
| Intel Ultimate N WiFi Link 5300                                   | 2         | 0.39%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 109       | 41.6%   |
| Realtek Semiconductor    | 44        | 16.79%  |
| Broadcom                 | 40        | 15.27%  |
| Qualcomm Atheros         | 38        | 14.5%   |
| Broadcom Limited         | 9         | 3.44%   |
| TP-Link                  | 4         | 1.53%   |
| Ralink Technology        | 4         | 1.53%   |
| Ralink                   | 4         | 1.53%   |
| Marvell Technology Group | 2         | 0.76%   |
| Sitecom Europe           | 1         | 0.38%   |
| Sierra Wireless          | 1         | 0.38%   |
| Microsoft                | 1         | 0.38%   |
| MEDIATEK                 | 1         | 0.38%   |
| Linksys                  | 1         | 0.38%   |
| LG Electronics           | 1         | 0.38%   |
| D-Link System            | 1         | 0.38%   |
| AVM                      | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 14        | 5.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 4.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 10        | 3.79%   |
| Intel Wireless 8260                                            | 10        | 3.79%   |
| Intel Wi-Fi 6 AX201                                            | 10        | 3.79%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 3.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 9         | 3.41%   |
| Intel Wireless 8265 / 8275                                     | 8         | 3.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 8         | 3.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 7         | 2.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 2.65%   |
| Intel Wireless 7265                                            | 6         | 2.27%   |
| Intel Wireless 7260                                            | 6         | 2.27%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 2.27%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 2.27%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 6         | 2.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 5         | 1.89%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 1.89%   |
| Intel Wireless 3165                                            | 5         | 1.89%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 5         | 1.89%   |
| Realtek 802.11ac NIC                                           | 4         | 1.52%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 3         | 1.14%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.14%   |
| Intel Wireless-AC 9260                                         | 3         | 1.14%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.14%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.14%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 3         | 1.14%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.14%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 1.14%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 3         | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 2         | 0.76%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.76%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 2         | 0.76%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.76%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.76%   |
| Intel Wireless 3160                                            | 2         | 0.76%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 0.76%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.76%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 0.76%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 2         | 0.76%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 2         | 0.76%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 0.76%   |
| Broadcom BCM43227 802.11b/g/n                                  | 2         | 0.76%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 0.76%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 0.76%   |
| TP-Link Archer T4U ver.3                                       | 1         | 0.38%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.38%   |
| TP-Link 802.11n NIC                                            | 1         | 0.38%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.38%   |
| Sitecom Europe WL-329 Wireless Dualband USB adapter 300N       | 1         | 0.38%   |
| Sierra Wireless EM7455                                         | 1         | 0.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.38%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.38%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.38%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.38%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.38%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.38%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 127       | 52.7%   |
| Intel                    | 55        | 22.82%  |
| Broadcom                 | 15        | 6.22%   |
| Qualcomm Atheros         | 14        | 5.81%   |
| Nvidia                   | 11        | 4.56%   |
| Marvell Technology Group | 4         | 1.66%   |
| Xiaomi                   | 3         | 1.24%   |
| Samsung Electronics      | 3         | 1.24%   |
| Google                   | 2         | 0.83%   |
| OPPO Electronics         | 1         | 0.41%   |
| Motorola PCS             | 1         | 0.41%   |
| Huawei Technologies      | 1         | 0.41%   |
| Hewlett-Packard          | 1         | 0.41%   |
| Broadcom Limited         | 1         | 0.41%   |
| ASIX Electronics         | 1         | 0.41%   |
| Apple                    | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 94        | 38.84%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 20        | 8.26%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 11        | 4.55%   |
| Nvidia MCP79 Ethernet                                                          | 10        | 4.13%   |
| Realtek RTL8125 2.5GbE Controller                                              | 6         | 2.48%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 2.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 4         | 1.65%   |
| Intel I211 Gigabit Network Connection                                          | 4         | 1.65%   |
| Intel Ethernet Connection (2) I219-V                                           | 4         | 1.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 1.24%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 1.24%   |
| Intel 82579V Gigabit Network Connection                                        | 3         | 1.24%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 3         | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 0.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 0.83%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.83%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 2         | 0.83%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 0.83%   |
| Intel Ethernet Controller I225-V                                               | 2         | 0.83%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 0.83%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 0.83%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 0.83%   |
| Intel Ethernet Connection (10) I219-V                                          | 2         | 0.83%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.83%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 0.83%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 0.83%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1         | 0.41%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.41%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.41%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.41%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 1         | 0.41%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 1         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1         | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.41%   |
| OPPO RMX2001                                                                   | 1         | 0.41%   |
| Nvidia MCP61 Ethernet                                                          | 1         | 0.41%   |
| Motorola PCS moto g(7) optimo maxx(XT1955DL)                                   | 1         | 0.41%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.41%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 1         | 0.41%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.41%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.41%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.41%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.41%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.41%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.41%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.41%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.41%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.41%   |
| Intel Ethernet Connection (13) I219-V                                          | 1         | 0.41%   |
| Intel 82578DM Gigabit Network Connection                                       | 1         | 0.41%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.41%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 0.41%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1         | 0.41%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 1         | 0.41%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                         | 1         | 0.41%   |
| Huawei SNE-LX3                                                                 | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 253       | 52.6%   |
| Ethernet | 226       | 46.99%  |
| Modem    | 1         | 0.21%   |
| Unknown  | 1         | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 232       | 53.33%  |
| Ethernet | 202       | 46.44%  |
| Modem    | 1         | 0.23%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 158       | 53.02%  |
| 1     | 128       | 42.95%  |
| 3     | 6         | 2.01%   |
| 0     | 5         | 1.68%   |
| 4     | 1         | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 210       | 69.77%  |
| Yes  | 91        | 30.23%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 96        | 41.56%  |
| Apple                           | 35        | 15.15%  |
| Realtek Semiconductor           | 27        | 11.69%  |
| Qualcomm Atheros Communications | 15        | 6.49%   |
| Cambridge Silicon Radio         | 11        | 4.76%   |
| Lite-On Technology              | 9         | 3.9%    |
| Broadcom                        | 9         | 3.9%    |
| IMC Networks                    | 8         | 3.46%   |
| Foxconn / Hon Hai               | 6         | 2.6%    |
| Toshiba                         | 3         | 1.3%    |
| Hewlett-Packard                 | 3         | 1.3%    |
| Ralink                          | 2         | 0.87%   |
| Marvell Semiconductor           | 2         | 0.87%   |
| ASUSTek Computer                | 2         | 0.87%   |
| Realtek                         | 1         | 0.43%   |
| Qcom                            | 1         | 0.43%   |
| Dell                            | 1         | 0.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 40        | 17.32%  |
| Realtek Bluetooth Radio                                                             | 19        | 8.23%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 18        | 7.79%   |
| Intel AX201 Bluetooth                                                               | 17        | 7.36%   |
| Apple Bluetooth Host Controller                                                     | 14        | 6.06%   |
| Intel AX200 Bluetooth                                                               | 13        | 5.63%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 11        | 4.76%   |
| Apple Bluetooth USB Host Controller                                                 | 11        | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 10        | 4.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 6         | 2.6%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 5         | 2.16%   |
| Apple Bluetooth HCI                                                                 | 4         | 1.73%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 1.3%    |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.3%    |
| Intel Bluetooth Device                                                              | 3         | 1.3%    |
| IMC Networks Bluetooth Device                                                       | 3         | 1.3%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 3         | 1.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 1.3%    |
| Ralink RT3290 Bluetooth                                                             | 2         | 0.87%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 0.87%   |
| IMC Networks Bluetooth Radio                                                        | 2         | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.87%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.43%   |
| Toshiba Bluetooth Radio                                                             | 1         | 0.43%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 1         | 0.43%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.43%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.43%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.43%   |
| Qcom Bluetooth USB                                                                  | 1         | 0.43%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.43%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.43%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.43%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.43%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.43%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.43%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.43%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 1         | 0.43%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.43%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.43%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.43%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.43%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.43%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.43%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.43%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.43%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 1         | 0.43%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 1         | 0.43%   |
| ASUS BCM20702A0                                                                     | 1         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 213       | 55.61%  |
| AMD                     | 86        | 22.45%  |
| Nvidia                  | 57        | 14.88%  |
| C-Media Electronics     | 6         | 1.57%   |
| Logitech                | 4         | 1.04%   |
| Creative Labs           | 4         | 1.04%   |
| Unknown                 | 1         | 0.26%   |
| Texas Instruments       | 1         | 0.26%   |
| Realtek Semiconductor   | 1         | 0.26%   |
| Razer USA               | 1         | 0.26%   |
| No brand                | 1         | 0.26%   |
| GN Netcom               | 1         | 0.26%   |
| Generalplus Technology  | 1         | 0.26%   |
| Focusrite-Novation      | 1         | 0.26%   |
| ESS Technology          | 1         | 0.26%   |
| Dell                    | 1         | 0.26%   |
| Corsair                 | 1         | 0.26%   |
| BEHRINGER International | 1         | 0.26%   |
| Apple                   | 1         | 0.26%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 6.47%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 27        | 5.82%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 24        | 5.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 20        | 4.31%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 3.23%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 2.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 13        | 2.8%    |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 2.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 11        | 2.37%   |
| Nvidia MCP79 High Definition Audio                                                                | 10        | 2.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 10        | 2.16%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 2.16%   |
| Intel Broadwell-U Audio Controller                                                                | 10        | 2.16%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 9         | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.94%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 1.94%   |
| Intel 8 Series HD Audio Controller                                                                | 9         | 1.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 8         | 1.72%   |
| AMD FCH Azalia Controller                                                                         | 8         | 1.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 8         | 1.72%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 8         | 1.72%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.51%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 1.51%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.51%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 6         | 1.29%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.29%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.29%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 6         | 1.29%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 1.08%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 5         | 1.08%   |
| AMD High Definition Audio Controller                                                              | 5         | 1.08%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 0.86%   |
| Nvidia TU104 HD Audio Controller                                                                  | 4         | 0.86%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.86%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.86%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 0.86%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 4         | 0.86%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 4         | 0.86%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.65%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.65%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.65%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 3         | 0.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.65%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 0.65%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.43%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.43%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.43%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.43%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.43%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 0.43%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 0.43%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 0.43%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 2         | 0.43%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.43%   |
| Unknown USB MIDI Interface                                                                        | 1         | 0.22%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 24        | 35.82%  |
| SK Hynix            | 13        | 19.4%   |
| Micron Technology   | 8         | 11.94%  |
| Unknown             | 5         | 7.46%   |
| Kingston            | 3         | 4.48%   |
| Ramaxel Technology  | 2         | 2.99%   |
| G.Skill             | 2         | 2.99%   |
| Corsair             | 2         | 2.99%   |
| Unknown (ABCD)      | 1         | 1.49%   |
| SHARETRONIC         | 1         | 1.49%   |
| PNY                 | 1         | 1.49%   |
| Patriot             | 1         | 1.49%   |
| Hewlett-Packard     | 1         | 1.49%   |
| GSkill              | 1         | 1.49%   |
| Crucial             | 1         | 1.49%   |
| A-DATA Technology   | 1         | 1.49%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 3         | 4.05%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 2         | 2.7%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 2         | 2.7%    |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 2         | 2.7%    |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s            | 2         | 2.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 2.7%    |
| Unknown RAM Module 8192MB SODIMM DDR3                               | 1         | 1.35%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                        | 1         | 1.35%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                      | 1         | 1.35%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                      | 1         | 1.35%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 1.35%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 1         | 1.35%   |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                     | 1         | 1.35%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                   | 1         | 1.35%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                     | 1         | 1.35%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s                | 1         | 1.35%   |
| SK Hynix RAM HMT42GR7BMR4C 16384MB DIMM DDR3 1066MT/s               | 1         | 1.35%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s             | 1         | 1.35%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 1.35%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4096MB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| SK Hynix RAM HMA425S6AFR6N-UH 2048MB SODIMM DDR4 2400MT/s           | 1         | 1.35%   |
| SHARETRONIC RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 1.35%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                        | 1         | 1.35%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s                      | 1         | 1.35%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s               | 1         | 1.35%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s               | 1         | 1.35%   |
| Samsung RAM M471A5143EB1-CRC 4096MB SODIMM DDR4 2400MT/s            | 1         | 1.35%   |
| Samsung RAM M471A2K43DB1-CTD 16384MB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s        | 1         | 1.35%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 1         | 1.35%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s            | 1         | 1.35%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s               | 1         | 1.35%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s               | 1         | 1.35%   |
| Samsung RAM M393B2K70DM0 16384MB DIMM DDR3 1066MT/s                 | 1         | 1.35%   |
| Samsung RAM M378B5273DH0-CK0 4GB DIMM DDR3 2200MT/s                 | 1         | 1.35%   |
| Samsung RAM K4EBE304ED-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s     | 1         | 1.35%   |
| Samsung RAM K3QF4F40BM-AGCF 4096MB Row Of Chips LPDDR3 1867MT/s     | 1         | 1.35%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s           | 1         | 1.35%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 3200MT/s              | 1         | 1.35%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s                  | 1         | 1.35%   |
| Micron RAM MT40A1G16KD-062E:E 8192MB SODIMM DDR4 2667MT/s           | 1         | 1.35%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                       | 1         | 1.35%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s               | 1         | 1.35%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 1         | 1.35%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s         | 1         | 1.35%   |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s          | 1         | 1.35%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s               | 1         | 1.35%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s            | 1         | 1.35%   |
| Kingston RAM KHYXPX-HYJ 8GB SODIMM DDR4 2667MT/s                    | 1         | 1.35%   |
| Kingston RAM 9905625-030.A00G 8192MB DIMM DDR4 2133MT/s             | 1         | 1.35%   |
| Kingston RAM 9905471-015.A00LF 4096MB DIMM DDR3 1333MT/s            | 1         | 1.35%   |
| HP RAM 647650-071 8192MB DIMM DDR3 1333MT/s                         | 1         | 1.35%   |
| GSkill RAM F4-3200C22-8GRS 8192MB SODIMM DDR4 3200MT/s              | 1         | 1.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 31        | 50.82%  |
| DDR3   | 23        | 37.7%   |
| LPDDR4 | 4         | 6.56%   |
| LPDDR3 | 3         | 4.92%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 44        | 72.13%  |
| DIMM         | 11        | 18.03%  |
| Row Of Chips | 5         | 8.2%    |
| Chip         | 1         | 1.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 29        | 44.62%  |
| 4096  | 23        | 35.38%  |
| 16384 | 6         | 9.23%   |
| 2048  | 6         | 9.23%   |
| 32768 | 1         | 1.54%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 15        | 23.44%  |
| 2667    | 13        | 20.31%  |
| 3200    | 10        | 15.63%  |
| 2400    | 5         | 7.81%   |
| 2133    | 4         | 6.25%   |
| 1333    | 3         | 4.69%   |
| 4267    | 2         | 3.13%   |
| 3266    | 2         | 3.13%   |
| 1867    | 2         | 3.13%   |
| 1066    | 2         | 3.13%   |
| 2800    | 1         | 1.56%   |
| 2666    | 1         | 1.56%   |
| 2200    | 1         | 1.56%   |
| 1800    | 1         | 1.56%   |
| 1334    | 1         | 1.56%   |
| Unknown | 1         | 1.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Canon                           | 2         | 40%     |
| Samsung Electronics             | 1         | 20%     |
| Dymo-CoStar                     | 1         | 20%     |
| cab Produkttechnik GmbH & Co KG | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung M2020 Series                     | 1         | 20%     |
| Dymo-CoStar LabelWriter 450              | 1         | 20%     |
| Canon PIXMA MG3600 Series                | 1         | 20%     |
| Canon PIXMA MG2500 Series                | 1         | 20%     |
| cab Produkttechnik GmbH & Co KG EOS2/300 | 1         | 20%     |

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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 39        | 18.22%  |
| Apple                                  | 29        | 13.55%  |
| IMC Networks                           | 25        | 11.68%  |
| Realtek Semiconductor                  | 20        | 9.35%   |
| Acer                                   | 15        | 7.01%   |
| Quanta                                 | 13        | 6.07%   |
| Microdia                               | 12        | 5.61%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 4.67%   |
| Syntek                                 | 7         | 3.27%   |
| Suyin                                  | 7         | 3.27%   |
| Alcor Micro                            | 6         | 2.8%    |
| Sunplus Innovation Technology          | 5         | 2.34%   |
| Logitech                               | 5         | 2.34%   |
| Silicon Motion                         | 4         | 1.87%   |
| Microsoft                              | 4         | 1.87%   |
| Ricoh                                  | 2         | 0.93%   |
| Luxvisions Innotech Limited            | 2         | 0.93%   |
| Y Media                                | 1         | 0.47%   |
| Sony                                   | 1         | 0.47%   |
| Lite-On Technology                     | 1         | 0.47%   |
| Lenovo                                 | 1         | 0.47%   |
| kingcome                               | 1         | 0.47%   |
| Google                                 | 1         | 0.47%   |
| Generalplus Technology                 | 1         | 0.47%   |
| Foxconn / Hon Hai                      | 1         | 0.47%   |
| ANYKA                                  | 1         | 0.47%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                    | 14        | 6.42%   |
| IMC Networks Integrated Camera                                           | 9         | 4.13%   |
| Chicony Integrated Camera                                                | 8         | 3.67%   |
| Syntek Integrated Camera                                                 | 7         | 3.21%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 6         | 2.75%   |
| Chicony HD WebCam                                                        | 6         | 2.75%   |
| Realtek Integrated_Webcam_HD                                             | 5         | 2.29%   |
| Microdia Integrated_Webcam_HD                                            | 5         | 2.29%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 5         | 2.29%   |
| Apple FaceTime HD Camera                                                 | 5         | 2.29%   |
| Acer Lenovo EasyCamera                                                   | 4         | 1.83%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 3         | 1.38%   |
| Quanta VGA WebCam                                                        | 3         | 1.38%   |
| Quanta HD User Facing                                                    | 3         | 1.38%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 3         | 1.38%   |
| Chicony USB 2.0 Camera                                                   | 3         | 1.38%   |
| Apple FaceTime HD Camera (Built-in)                                      | 3         | 1.38%   |
| Alcor Micro USB 2.0 PC cam                                               | 3         | 1.38%   |
| Acer HD Webcam                                                           | 3         | 1.38%   |
| Sunplus Integrated_Webcam_HD                                             | 2         | 0.92%   |
| Realtek USB2.0 HD UVC WebCam                                             | 2         | 0.92%   |
| Realtek USB Camera                                                       | 2         | 0.92%   |
| Realtek Integrated Webcam                                                | 2         | 0.92%   |
| Realtek Acer 640 x 480 laptop camera                                     | 2         | 0.92%   |
| Quanta HP TrueVision HD Camera                                           | 2         | 0.92%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 2         | 0.92%   |
| Logitech Logi 4K Stream Edition                                          | 2         | 0.92%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 2         | 0.92%   |
| IMC Networks EasyCamera                                                  | 2         | 0.92%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 0.92%   |
| Chicony HP Wide Vision HD Camera                                         | 2         | 0.92%   |
| Chicony EasyCamera                                                       | 2         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam                         | 2         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 2         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 2         | 0.92%   |
| Apple FaceTime Camera                                                    | 2         | 0.92%   |
| Alcor Micro Acer Integrated Webcam                                       | 2         | 0.92%   |
| Acer Integrated Camera                                                   | 2         | 0.92%   |
| Acer EasyCamera                                                          | 2         | 0.92%   |
| Y Media USB Camera                                                       | 1         | 0.46%   |
| Suyin UVC HD Webcam                                                      | 1         | 0.46%   |
| Suyin USB 2.0 Camera                                                     | 1         | 0.46%   |
| Suyin Integrated_Webcam_HD                                               | 1         | 0.46%   |
| Suyin HP Integrated Webcam                                               | 1         | 0.46%   |
| Suyin HD WebCam                                                          | 1         | 0.46%   |
| Suyin Asus Integrated Webcam [CN031B]                                    | 1         | 0.46%   |
| Suyin 1.3M HD WebCam                                                     | 1         | 0.46%   |
| Sunplus Laptop_Integrated_Webcam_HD                                      | 1         | 0.46%   |
| Sunplus HP Universal Camera                                              | 1         | 0.46%   |
| Sunplus HP HD Webcam [Fixed]                                             | 1         | 0.46%   |
| Sony CEVCECM                                                             | 1         | 0.46%   |
| Silicon Motion WebCam SCB-0385N                                          | 1         | 0.46%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.]                  | 1         | 0.46%   |
| Silicon Motion WebCam SC-10HDP12631N                                     | 1         | 0.46%   |
| Silicon Motion ATIV VGA Camera                                           | 1         | 0.46%   |
| Ricoh USB2.0 Camera                                                      | 1         | 0.46%   |
| Ricoh Dell Laptop Integrated Webcam                                      | 1         | 0.46%   |
| Realtek LG Webcam                                                        | 1         | 0.46%   |
| Realtek LG Camera                                                        | 1         | 0.46%   |
| Realtek Integrated Camera                                                | 1         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 11        | 36.67%  |
| Validity Sensors           | 8         | 26.67%  |
| LighTuning Technology      | 5         | 16.67%  |
| Upek                       | 2         | 6.67%   |
| Shenzhen Goodix Technology | 2         | 6.67%   |
| Elan Microelectronics      | 2         | 6.67%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 4         | 13.33%  |
| LighTuning EgisTec Touch Fingerprint Sensor               | 3         | 10%     |
| Unknown                                                   | 3         | 10%     |
| Validity Sensors VFS5011 Fingerprint Reader               | 2         | 6.67%   |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 6.67%   |
| Validity Sensors VFS 5011 fingerprint sensor              | 2         | 6.67%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor    | 2         | 6.67%   |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 6.67%   |
| Shenzhen Goodix  Fingerprint Device                       | 2         | 6.67%   |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 2         | 6.67%   |
| Validity Sensors VFS491                                   | 1         | 3.33%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 3.33%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 3.33%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 1         | 3.33%   |
| Elan ELAN:Fingerprint                                     | 1         | 3.33%   |
| Elan ELAN:ARM-M4                                          | 1         | 3.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 4         | 33.33%  |
| Alcor Micro           | 4         | 33.33%  |
| Lenovo                | 2         | 16.67%  |
| Gemalto (was Gemplus) | 1         | 8.33%   |
| Chicony Electronics   | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                    | 4         | 33.33%  |
| Lenovo Integrated Smart Card Reader                    | 2         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor         | 2         | 16.67%  |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer | 1         | 8.33%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard   | 1         | 8.33%   |
| Broadcom 5880                                          | 1         | 8.33%   |
| Broadcom 58200                                         | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 228       | 76%     |
| 1     | 59        | 19.67%  |
| 2     | 12        | 4%      |
| 4     | 1         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 30        | 34.88%  |
| Net/wireless             | 17        | 19.77%  |
| Multimedia controller    | 12        | 13.95%  |
| Chipcard                 | 11        | 12.79%  |
| Graphics card            | 6         | 6.98%   |
| Camera                   | 3         | 3.49%   |
| Bluetooth                | 3         | 3.49%   |
| Storage/ide              | 1         | 1.16%   |
| Storage                  | 1         | 1.16%   |
| Sound                    | 1         | 1.16%   |
| Communication controller | 1         | 1.16%   |

