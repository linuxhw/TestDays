ROSA - Tested Hardware & Statistics
-----------------------------------

A project to collect tested hardware configurations for ROSA.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ROSA/Desktop/README.md) and [notebooks](/Dist/ROSA/Notebook/README.md).

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

Total: 38552

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | 3190 NOK                    | Mini pc     | [5f6f023f22](https://linux-hardware.org/?probe=5f6f023f22) | Jun 01, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [60eba56233](https://linux-hardware.org/?probe=60eba56233) | Jun 01, 2022 |
| Huanan        | X99-F8 NALEX                | Desktop     | [5c3c77a5a0](https://linux-hardware.org/?probe=5c3c77a5a0) | May 31, 2022 |
| Acer          | AO756                       | Notebook    | [dd33104b58](https://linux-hardware.org/?probe=dd33104b58) | May 31, 2022 |
| Huanan        | X99-F8 NALEX                | Desktop     | [11d242c4f4](https://linux-hardware.org/?probe=11d242c4f4) | May 31, 2022 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [990cfd2d12](https://linux-hardware.org/?probe=990cfd2d12) | May 31, 2022 |
| Gigabyte      | P31-S3L                     | Desktop     | [329c96c5af](https://linux-hardware.org/?probe=329c96c5af) | May 31, 2022 |
| ASUSTek       | P8Z68-V GEN3                | Desktop     | [139f0688be](https://linux-hardware.org/?probe=139f0688be) | May 31, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [6d4b89571e](https://linux-hardware.org/?probe=6d4b89571e) | May 31, 2022 |
| Dell          | Inspiron 3180               | Notebook    | [ee18866cf0](https://linux-hardware.org/?probe=ee18866cf0) | May 31, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [2d6ef8ef23](https://linux-hardware.org/?probe=2d6ef8ef23) | May 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ec1c8e7378](https://linux-hardware.org/?probe=ec1c8e7378) | May 31, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [ce5695fd2a](https://linux-hardware.org/?probe=ce5695fd2a) | May 31, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [451572720e](https://linux-hardware.org/?probe=451572720e) | May 31, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [5f44d47258](https://linux-hardware.org/?probe=5f44d47258) | May 31, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [0368b3543a](https://linux-hardware.org/?probe=0368b3543a) | May 31, 2022 |
| Acer          | Aspire V5-571G              | Notebook    | [b1c8a97e57](https://linux-hardware.org/?probe=b1c8a97e57) | May 31, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [d593c93e62](https://linux-hardware.org/?probe=d593c93e62) | May 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [e63df7d890](https://linux-hardware.org/?probe=e63df7d890) | May 30, 2022 |
| Gigabyte      | EP45C-DS3R                  | Desktop     | [dc6dbe40d9](https://linux-hardware.org/?probe=dc6dbe40d9) | May 30, 2022 |
| Huanan        | X99-F8 NALEX                | Desktop     | [d6de670b16](https://linux-hardware.org/?probe=d6de670b16) | May 30, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [ed0b412ea1](https://linux-hardware.org/?probe=ed0b412ea1) | May 30, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [1a67c11533](https://linux-hardware.org/?probe=1a67c11533) | May 30, 2022 |
| ASUSTek       | F1A75-M-PRO R2.0            | Desktop     | [070e59ce1e](https://linux-hardware.org/?probe=070e59ce1e) | May 30, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [90c386e917](https://linux-hardware.org/?probe=90c386e917) | May 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [217b497fa9](https://linux-hardware.org/?probe=217b497fa9) | May 30, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [6a48092da4](https://linux-hardware.org/?probe=6a48092da4) | May 30, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [7ca55e50b4](https://linux-hardware.org/?probe=7ca55e50b4) | May 30, 2022 |
| Intel         | DH55TC AAE70932-204         | Desktop     | [774da6cf18](https://linux-hardware.org/?probe=774da6cf18) | May 30, 2022 |
| Apple         | Mac-F22C86C8                | Mini pc     | [28bb098deb](https://linux-hardware.org/?probe=28bb098deb) | May 30, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [cc7ddb2cbc](https://linux-hardware.org/?probe=cc7ddb2cbc) | May 30, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [7b22d97da7](https://linux-hardware.org/?probe=7b22d97da7) | May 30, 2022 |
| Toshiba       | Satellite U400              | Notebook    | [cbcfeeeb48](https://linux-hardware.org/?probe=cbcfeeeb48) | May 30, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [f1ed3c6a46](https://linux-hardware.org/?probe=f1ed3c6a46) | May 30, 2022 |
| HP            | Laptop 15-ra0xx             | Notebook    | [dab3ef3dee](https://linux-hardware.org/?probe=dab3ef3dee) | May 30, 2022 |
| Lenovo        | 3129 SDK0J40679 WIN 3273... | Desktop     | [0314182c7f](https://linux-hardware.org/?probe=0314182c7f) | May 29, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [5fdf8e3100](https://linux-hardware.org/?probe=5fdf8e3100) | May 29, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [5d2f3565ff](https://linux-hardware.org/?probe=5d2f3565ff) | May 29, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [b261adaa93](https://linux-hardware.org/?probe=b261adaa93) | May 29, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [458bf7fd6d](https://linux-hardware.org/?probe=458bf7fd6d) | May 29, 2022 |
| Chuwi         | LarkBook                    | Notebook    | [46e805f477](https://linux-hardware.org/?probe=46e805f477) | May 29, 2022 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [70e20c1143](https://linux-hardware.org/?probe=70e20c1143) | May 29, 2022 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [75d42068ac](https://linux-hardware.org/?probe=75d42068ac) | May 29, 2022 |
| Gigabyte      | B250-HD3-CF                 | Desktop     | [f4a35d313c](https://linux-hardware.org/?probe=f4a35d313c) | May 29, 2022 |
| HP            | Pavilion g6                 | Notebook    | [49471ad092](https://linux-hardware.org/?probe=49471ad092) | May 29, 2022 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [bcc7398945](https://linux-hardware.org/?probe=bcc7398945) | May 29, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [3734fbcb7d](https://linux-hardware.org/?probe=3734fbcb7d) | May 29, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [4647f374ee](https://linux-hardware.org/?probe=4647f374ee) | May 28, 2022 |
| HP            | ProBook 4540s               | Notebook    | [bb0ac4bfa9](https://linux-hardware.org/?probe=bb0ac4bfa9) | May 28, 2022 |
| Notebook      | W65_67SF                    | Notebook    | [c8ba646143](https://linux-hardware.org/?probe=c8ba646143) | May 28, 2022 |
| Dell          | Vostro 5468                 | Notebook    | [2784f8c927](https://linux-hardware.org/?probe=2784f8c927) | May 28, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [7e68528d56](https://linux-hardware.org/?probe=7e68528d56) | May 28, 2022 |
| Gigabyte      | 965P-S3                     | Desktop     | [2058a25c1e](https://linux-hardware.org/?probe=2058a25c1e) | May 28, 2022 |
| Intel         | X79 V2.72B                  | Desktop     | [15d19c724b](https://linux-hardware.org/?probe=15d19c724b) | May 28, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [c7eceb86c2](https://linux-hardware.org/?probe=c7eceb86c2) | May 28, 2022 |
| ASRock        | H87 Pro4                    | Desktop     | [c2bbd20120](https://linux-hardware.org/?probe=c2bbd20120) | May 28, 2022 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [6c8e83728c](https://linux-hardware.org/?probe=6c8e83728c) | May 28, 2022 |
| MACHINIST     | X99-K9 V2.0                 | Desktop     | [11bdd69dc0](https://linux-hardware.org/?probe=11bdd69dc0) | May 28, 2022 |
| Lenovo        | 3000 G410                   | Notebook    | [e745b05a55](https://linux-hardware.org/?probe=e745b05a55) | May 28, 2022 |
| ASUSTek       | X541UVK                     | Notebook    | [af4a83b898](https://linux-hardware.org/?probe=af4a83b898) | May 28, 2022 |
| ASUSTek       | P8H61                       | Desktop     | [45ec66aa68](https://linux-hardware.org/?probe=45ec66aa68) | May 28, 2022 |
| Intel         | X79 V2.72B                  | Desktop     | [a1a4ad8594](https://linux-hardware.org/?probe=a1a4ad8594) | May 28, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [a634794de3](https://linux-hardware.org/?probe=a634794de3) | May 28, 2022 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [2540080e55](https://linux-hardware.org/?probe=2540080e55) | May 28, 2022 |
| Toshiba       | Satellite U300              | Notebook    | [1635f05f8d](https://linux-hardware.org/?probe=1635f05f8d) | May 28, 2022 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [f61c44c7b4](https://linux-hardware.org/?probe=f61c44c7b4) | May 28, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [2dba625d78](https://linux-hardware.org/?probe=2dba625d78) | May 28, 2022 |
| Acer          | Veriton X2665G              | Desktop     | [b07be0c2aa](https://linux-hardware.org/?probe=b07be0c2aa) | May 27, 2022 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [93de227774](https://linux-hardware.org/?probe=93de227774) | May 27, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [8cdbd043a4](https://linux-hardware.org/?probe=8cdbd043a4) | May 27, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [e5dd5ddffe](https://linux-hardware.org/?probe=e5dd5ddffe) | May 27, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [59159b4b05](https://linux-hardware.org/?probe=59159b4b05) | May 27, 2022 |
| Lenovo        | ThinkPad L460 20FVS14V00    | Notebook    | [63b7b8022c](https://linux-hardware.org/?probe=63b7b8022c) | May 27, 2022 |
| Lenovo        | G575 20081                  | Notebook    | [14e84df65f](https://linux-hardware.org/?probe=14e84df65f) | May 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [4728993173](https://linux-hardware.org/?probe=4728993173) | May 27, 2022 |
| ONDA          | OBOOK 20 PLUS               | Notebook    | [c0152b04cb](https://linux-hardware.org/?probe=c0152b04cb) | May 27, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [2cca2a7979](https://linux-hardware.org/?probe=2cca2a7979) | May 27, 2022 |
| HP            | 0B54h D                     | Desktop     | [d36988a09b](https://linux-hardware.org/?probe=d36988a09b) | May 26, 2022 |
| Lenovo        | 3000 G410                   | Notebook    | [3ebbe29445](https://linux-hardware.org/?probe=3ebbe29445) | May 26, 2022 |
| ASRock        | B85M Pro3                   | Desktop     | [661f30003c](https://linux-hardware.org/?probe=661f30003c) | May 26, 2022 |
| Dell          | Latitude E6430              | Notebook    | [5a914a9c89](https://linux-hardware.org/?probe=5a914a9c89) | May 26, 2022 |
| Intel         | DH55TC AAE70932-204         | Desktop     | [63c6e6a359](https://linux-hardware.org/?probe=63c6e6a359) | May 26, 2022 |
| ASUSTek       | H87-PLUS                    | Desktop     | [b3abdcf25f](https://linux-hardware.org/?probe=b3abdcf25f) | May 26, 2022 |
| Gigabyte      | P61A-D3                     | Desktop     | [2ec61142d0](https://linux-hardware.org/?probe=2ec61142d0) | May 26, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [a34b43d64c](https://linux-hardware.org/?probe=a34b43d64c) | May 25, 2022 |
| Acer          | Extensa 5630                | Notebook    | [9728bad307](https://linux-hardware.org/?probe=9728bad307) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [30207c3cdc](https://linux-hardware.org/?probe=30207c3cdc) | May 25, 2022 |
| HP            | Pavilion g7                 | Notebook    | [e038c828f9](https://linux-hardware.org/?probe=e038c828f9) | May 25, 2022 |
| Gigabyte      | P75-D3                      | Desktop     | [becf8cce19](https://linux-hardware.org/?probe=becf8cce19) | May 25, 2022 |
| Samsung       | 530U3C/530U4C               | Notebook    | [a52fc8f40a](https://linux-hardware.org/?probe=a52fc8f40a) | May 25, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [ed4df544d6](https://linux-hardware.org/?probe=ed4df544d6) | May 24, 2022 |
| Acer          | Aspire TC-705               | Desktop     | [57bd3c5501](https://linux-hardware.org/?probe=57bd3c5501) | May 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [f680d813d7](https://linux-hardware.org/?probe=f680d813d7) | May 24, 2022 |
| HPE           | ProLiant DL160 Gen10        | Server      | [dc086873ea](https://linux-hardware.org/?probe=dc086873ea) | May 24, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [f99b47321c](https://linux-hardware.org/?probe=f99b47321c) | May 24, 2022 |
| HP            | Mini 110-4100               | Notebook    | [c09a467c25](https://linux-hardware.org/?probe=c09a467c25) | May 24, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [068b759d6e](https://linux-hardware.org/?probe=068b759d6e) | May 24, 2022 |
| HP            | 0B54h D                     | Desktop     | [9dc982847a](https://linux-hardware.org/?probe=9dc982847a) | May 24, 2022 |
| Acer          | Aspire C24-865              | All in one  | [e61762236d](https://linux-hardware.org/?probe=e61762236d) | May 23, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [7200a39439](https://linux-hardware.org/?probe=7200a39439) | May 23, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [13c83f5c47](https://linux-hardware.org/?probe=13c83f5c47) | May 23, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6d2738eb29](https://linux-hardware.org/?probe=6d2738eb29) | May 23, 2022 |
| HP            | 8523 A01                    | Mini pc     | [d3affbbdf4](https://linux-hardware.org/?probe=d3affbbdf4) | May 23, 2022 |
| ASUSTek       | C60M1-I                     | Desktop     | [169d96b73b](https://linux-hardware.org/?probe=169d96b73b) | May 23, 2022 |
| HP            | Notebook                    | Notebook    | [3e5ee0fcbb](https://linux-hardware.org/?probe=3e5ee0fcbb) | May 23, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [861da6e999](https://linux-hardware.org/?probe=861da6e999) | May 23, 2022 |
| Dell          | G7 7588                     | Notebook    | [6224d3a656](https://linux-hardware.org/?probe=6224d3a656) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [be23737ca8](https://linux-hardware.org/?probe=be23737ca8) | May 22, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [bee7a3bfc6](https://linux-hardware.org/?probe=bee7a3bfc6) | May 22, 2022 |
| Gigabyte      | H55M-USB3                   | Desktop     | [08e7d1f0d2](https://linux-hardware.org/?probe=08e7d1f0d2) | May 22, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [ed2bf9256c](https://linux-hardware.org/?probe=ed2bf9256c) | May 22, 2022 |
| Intel         | X79                         | Desktop     | [904bf5297c](https://linux-hardware.org/?probe=904bf5297c) | May 22, 2022 |
| Unknown       | Intel X79                   | Desktop     | [52d19fdb12](https://linux-hardware.org/?probe=52d19fdb12) | May 22, 2022 |
| ASUSTek       | N53Jq                       | Notebook    | [f8e79d7221](https://linux-hardware.org/?probe=f8e79d7221) | May 22, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [b64b85418b](https://linux-hardware.org/?probe=b64b85418b) | May 22, 2022 |
| Acer          | Aspire 5734Z                | Notebook    | [6c47938031](https://linux-hardware.org/?probe=6c47938031) | May 22, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [58dcd147b7](https://linux-hardware.org/?probe=58dcd147b7) | May 22, 2022 |
| HP            | Pavilion 17                 | Notebook    | [d2dbdbd444](https://linux-hardware.org/?probe=d2dbdbd444) | May 22, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [aeb22efb30](https://linux-hardware.org/?probe=aeb22efb30) | May 22, 2022 |
| ASUSTek       | N61Da                       | Notebook    | [e96feda0f9](https://linux-hardware.org/?probe=e96feda0f9) | May 22, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [092f8be315](https://linux-hardware.org/?probe=092f8be315) | May 22, 2022 |
| Samsung       | 530U3C/530U4C               | Notebook    | [cd12ece868](https://linux-hardware.org/?probe=cd12ece868) | May 22, 2022 |
| ASUSTek       | N61Da                       | Notebook    | [406255b638](https://linux-hardware.org/?probe=406255b638) | May 22, 2022 |
| Intel         | Unknown                     | Notebook    | [9f704ad203](https://linux-hardware.org/?probe=9f704ad203) | May 22, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [0e14154fc0](https://linux-hardware.org/?probe=0e14154fc0) | May 22, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [27be8e7d2f](https://linux-hardware.org/?probe=27be8e7d2f) | May 21, 2022 |
| ASUSTek       | P5KPL-AM IN/ROEM/SI         | Desktop     | [a94464dc7e](https://linux-hardware.org/?probe=a94464dc7e) | May 21, 2022 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [bd3a571c95](https://linux-hardware.org/?probe=bd3a571c95) | May 21, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [77ba979b27](https://linux-hardware.org/?probe=77ba979b27) | May 21, 2022 |
| ASUSTek       | N53Jq                       | Notebook    | [a0d24cad99](https://linux-hardware.org/?probe=a0d24cad99) | May 21, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [12aa7cac29](https://linux-hardware.org/?probe=12aa7cac29) | May 21, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [299fbf792e](https://linux-hardware.org/?probe=299fbf792e) | May 21, 2022 |
| HP            | Compaq 6735s                | Notebook    | [bcd9db6031](https://linux-hardware.org/?probe=bcd9db6031) | May 20, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [91fe66d159](https://linux-hardware.org/?probe=91fe66d159) | May 20, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [193e7d05a0](https://linux-hardware.org/?probe=193e7d05a0) | May 20, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [71797f9336](https://linux-hardware.org/?probe=71797f9336) | May 20, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [25cf1b1ec9](https://linux-hardware.org/?probe=25cf1b1ec9) | May 20, 2022 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [afce6e6cee](https://linux-hardware.org/?probe=afce6e6cee) | May 20, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [da744c49fd](https://linux-hardware.org/?probe=da744c49fd) | May 20, 2022 |
| Acer          | Unknown                     | Notebook    | [c8e97c31be](https://linux-hardware.org/?probe=c8e97c31be) | May 20, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [696932f291](https://linux-hardware.org/?probe=696932f291) | May 20, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [be0659ce93](https://linux-hardware.org/?probe=be0659ce93) | May 20, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [acbead429c](https://linux-hardware.org/?probe=acbead429c) | May 20, 2022 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [88882c2c94](https://linux-hardware.org/?probe=88882c2c94) | May 19, 2022 |
| Lenovo        | Legion 5 17IMH05H 81Y8      | Notebook    | [08638290ff](https://linux-hardware.org/?probe=08638290ff) | May 19, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [73fdd642c6](https://linux-hardware.org/?probe=73fdd642c6) | May 19, 2022 |
| Lenovo        | G585 20137                  | Notebook    | [5eae6b5a34](https://linux-hardware.org/?probe=5eae6b5a34) | May 19, 2022 |
| ASUSTek       | F5RL                        | Notebook    | [30e7f880d5](https://linux-hardware.org/?probe=30e7f880d5) | May 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [50fc292dd2](https://linux-hardware.org/?probe=50fc292dd2) | May 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [d61129ec0f](https://linux-hardware.org/?probe=d61129ec0f) | May 19, 2022 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [1064f07721](https://linux-hardware.org/?probe=1064f07721) | May 19, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d5649e5a3a](https://linux-hardware.org/?probe=d5649e5a3a) | May 19, 2022 |
| ASUSTek       | N53Jq                       | Notebook    | [b8c3bdc3de](https://linux-hardware.org/?probe=b8c3bdc3de) | May 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [7a6f957def](https://linux-hardware.org/?probe=7a6f957def) | May 18, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [63acfbdc55](https://linux-hardware.org/?probe=63acfbdc55) | May 18, 2022 |
| Gigabyte      | B365 HD3                    | Desktop     | [82bd3dbfe9](https://linux-hardware.org/?probe=82bd3dbfe9) | May 18, 2022 |
| HP            | 82A5                        | Mini pc     | [4390094fd8](https://linux-hardware.org/?probe=4390094fd8) | May 18, 2022 |
| Gigabyte      | H55-UD3H                    | Desktop     | [e766ad4581](https://linux-hardware.org/?probe=e766ad4581) | May 18, 2022 |
| ASUSTek       | P5E                         | Desktop     | [4038be4f49](https://linux-hardware.org/?probe=4038be4f49) | May 18, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [cc38925ca1](https://linux-hardware.org/?probe=cc38925ca1) | May 18, 2022 |
| Lenovo        | ThinkPad L520 5017BK4       | Notebook    | [087884b808](https://linux-hardware.org/?probe=087884b808) | May 18, 2022 |
| Gigabyte      | E350N WIN8                  | Desktop     | [31923a075f](https://linux-hardware.org/?probe=31923a075f) | May 18, 2022 |
| Gigabyte      | P61A-D3                     | Desktop     | [dd4b8bf4e7](https://linux-hardware.org/?probe=dd4b8bf4e7) | May 18, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [01dc038814](https://linux-hardware.org/?probe=01dc038814) | May 18, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [5f2fb2e8bd](https://linux-hardware.org/?probe=5f2fb2e8bd) | May 17, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [1f15f778fd](https://linux-hardware.org/?probe=1f15f778fd) | May 17, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [a54f021132](https://linux-hardware.org/?probe=a54f021132) | May 17, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [4e6962ed18](https://linux-hardware.org/?probe=4e6962ed18) | May 17, 2022 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [5feb18b37b](https://linux-hardware.org/?probe=5feb18b37b) | May 17, 2022 |
| HP            | Pavilion g6                 | Notebook    | [9a7ac94310](https://linux-hardware.org/?probe=9a7ac94310) | May 17, 2022 |
| EPoX Compu... | nForce3 DDR: 8KDA3I Seri... | Desktop     | [4b38991c7a](https://linux-hardware.org/?probe=4b38991c7a) | May 17, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [0d1a3da50a](https://linux-hardware.org/?probe=0d1a3da50a) | May 17, 2022 |
| Foxconn       | 945 7MD Series              | Desktop     | [523af6afbd](https://linux-hardware.org/?probe=523af6afbd) | May 17, 2022 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [7fe3dc4301](https://linux-hardware.org/?probe=7fe3dc4301) | May 17, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [63fd31813f](https://linux-hardware.org/?probe=63fd31813f) | May 17, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [a3b4c84c89](https://linux-hardware.org/?probe=a3b4c84c89) | May 17, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [1589892eec](https://linux-hardware.org/?probe=1589892eec) | May 17, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [a38bac0479](https://linux-hardware.org/?probe=a38bac0479) | May 17, 2022 |
| Gigabyte      | H67N-USB3-B3                | Desktop     | [8feeed71b7](https://linux-hardware.org/?probe=8feeed71b7) | May 17, 2022 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [5186d57b24](https://linux-hardware.org/?probe=5186d57b24) | May 17, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [aee504bd13](https://linux-hardware.org/?probe=aee504bd13) | May 17, 2022 |
| Gigabyte      | P61A-D3                     | Desktop     | [d495e3aa63](https://linux-hardware.org/?probe=d495e3aa63) | May 17, 2022 |
| Toshiba       | Satellite L750D             | Notebook    | [6a84eb18c8](https://linux-hardware.org/?probe=6a84eb18c8) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [909b5d9be4](https://linux-hardware.org/?probe=909b5d9be4) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [4487dba8aa](https://linux-hardware.org/?probe=4487dba8aa) | May 16, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [934bd75010](https://linux-hardware.org/?probe=934bd75010) | May 16, 2022 |
| MSI           | GL62M 7REX                  | Notebook    | [767733bb1e](https://linux-hardware.org/?probe=767733bb1e) | May 16, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | Notebook    | [cad77c8a2c](https://linux-hardware.org/?probe=cad77c8a2c) | May 16, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [b7466ace8a](https://linux-hardware.org/?probe=b7466ace8a) | May 16, 2022 |
| Acer          | Aspire TC-705               | Desktop     | [b0873a64d2](https://linux-hardware.org/?probe=b0873a64d2) | May 16, 2022 |
| Acer          | Extensa 2519                | Notebook    | [e07a5704a8](https://linux-hardware.org/?probe=e07a5704a8) | May 16, 2022 |
| Gigabyte      | H81M-S2V                    | Desktop     | [9646d7027f](https://linux-hardware.org/?probe=9646d7027f) | May 16, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [fb414ad293](https://linux-hardware.org/?probe=fb414ad293) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [633d4d525b](https://linux-hardware.org/?probe=633d4d525b) | May 16, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [66067f39a0](https://linux-hardware.org/?probe=66067f39a0) | May 16, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [2c91bb6c51](https://linux-hardware.org/?probe=2c91bb6c51) | May 16, 2022 |
| ASUSTek       | K52JT                       | Notebook    | [68862e338e](https://linux-hardware.org/?probe=68862e338e) | May 16, 2022 |
| Sony          | SVE1512H1RW                 | Notebook    | [0a75cef1f7](https://linux-hardware.org/?probe=0a75cef1f7) | May 16, 2022 |
| ASUSTek       | M51Sr                       | Notebook    | [ebcb6315c9](https://linux-hardware.org/?probe=ebcb6315c9) | May 16, 2022 |
| MSI           | GL62M 7REX                  | Notebook    | [79f61f478d](https://linux-hardware.org/?probe=79f61f478d) | May 16, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [1cabcd1318](https://linux-hardware.org/?probe=1cabcd1318) | May 16, 2022 |
| Foxconn       | A9DA                        | Desktop     | [ab3ac79470](https://linux-hardware.org/?probe=ab3ac79470) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [040dc0a951](https://linux-hardware.org/?probe=040dc0a951) | May 16, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [44da55727f](https://linux-hardware.org/?probe=44da55727f) | May 16, 2022 |
| Foxconn       | A9DA                        | Desktop     | [e950ffe8d9](https://linux-hardware.org/?probe=e950ffe8d9) | May 16, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [ea483c055f](https://linux-hardware.org/?probe=ea483c055f) | May 16, 2022 |
| HP            | Compaq 6830s                | Notebook    | [edca070359](https://linux-hardware.org/?probe=edca070359) | May 15, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [45da577bc5](https://linux-hardware.org/?probe=45da577bc5) | May 15, 2022 |
| ECS           | BSWI-D2                     | Desktop     | [f5ad79fb60](https://linux-hardware.org/?probe=f5ad79fb60) | May 15, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [a777a043ac](https://linux-hardware.org/?probe=a777a043ac) | May 15, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [e5121153f7](https://linux-hardware.org/?probe=e5121153f7) | May 15, 2022 |
| Acer          | Acadia V1.45                | Notebook    | [778c730721](https://linux-hardware.org/?probe=778c730721) | May 15, 2022 |
| Samsung       | SQ45S70S                    | Notebook    | [fd62971ba0](https://linux-hardware.org/?probe=fd62971ba0) | May 15, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [18cf20e9a2](https://linux-hardware.org/?probe=18cf20e9a2) | May 15, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [15d32c7578](https://linux-hardware.org/?probe=15d32c7578) | May 15, 2022 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [eab1bcc17e](https://linux-hardware.org/?probe=eab1bcc17e) | May 15, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [59b99933d2](https://linux-hardware.org/?probe=59b99933d2) | May 14, 2022 |
| Dell          | Precision M6800             | Notebook    | [65d5a77965](https://linux-hardware.org/?probe=65d5a77965) | May 14, 2022 |
| Unknown       | GB01                        | Stick pc    | [8bbc53c60c](https://linux-hardware.org/?probe=8bbc53c60c) | May 14, 2022 |
| HP            | Pavilion g6                 | Notebook    | [6106cdb29d](https://linux-hardware.org/?probe=6106cdb29d) | May 14, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [5fb1304e59](https://linux-hardware.org/?probe=5fb1304e59) | May 14, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [b202236bb9](https://linux-hardware.org/?probe=b202236bb9) | May 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [2cb841c94e](https://linux-hardware.org/?probe=2cb841c94e) | May 14, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [1e48c58c4d](https://linux-hardware.org/?probe=1e48c58c4d) | May 14, 2022 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [ecacfd48de](https://linux-hardware.org/?probe=ecacfd48de) | May 14, 2022 |
| Gigabyte      | P61A-D3                     | Desktop     | [5abe5033c6](https://linux-hardware.org/?probe=5abe5033c6) | May 14, 2022 |
| Acer          | Aspire 5349                 | Notebook    | [17c18c2202](https://linux-hardware.org/?probe=17c18c2202) | May 14, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [c4a3491741](https://linux-hardware.org/?probe=c4a3491741) | May 14, 2022 |
| ASRock        | G41M-VS2                    | Desktop     | [9cf93ac497](https://linux-hardware.org/?probe=9cf93ac497) | May 14, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [abbad40394](https://linux-hardware.org/?probe=abbad40394) | May 14, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [9fece02922](https://linux-hardware.org/?probe=9fece02922) | May 14, 2022 |
| ASRock        | B75M-DGS R2.0               | Desktop     | [1d61892cb0](https://linux-hardware.org/?probe=1d61892cb0) | May 14, 2022 |
| MSI           | B350M PRO-VDH               | Desktop     | [a8033573ef](https://linux-hardware.org/?probe=a8033573ef) | May 14, 2022 |
| Lenovo        | ThinkPad X200 7455FPG       | Notebook    | [9c403ef686](https://linux-hardware.org/?probe=9c403ef686) | May 13, 2022 |
| Unknown       | GB01                        | Stick pc    | [68de5db99f](https://linux-hardware.org/?probe=68de5db99f) | May 13, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [a068dc57c8](https://linux-hardware.org/?probe=a068dc57c8) | May 13, 2022 |
| T-Platform... | TF307-MB-S-C                | Soc         | [9c8a709fe8](https://linux-hardware.org/?probe=9c8a709fe8) | May 13, 2022 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [30085d6f41](https://linux-hardware.org/?probe=30085d6f41) | May 13, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [4aeb51ba34](https://linux-hardware.org/?probe=4aeb51ba34) | May 13, 2022 |
| Acer          | Aspire ES1-511              | Notebook    | [0b5faf442b](https://linux-hardware.org/?probe=0b5faf442b) | May 13, 2022 |
| eMachines     | eME732ZG                    | Notebook    | [459bdc2a9c](https://linux-hardware.org/?probe=459bdc2a9c) | May 13, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [531749d46b](https://linux-hardware.org/?probe=531749d46b) | May 12, 2022 |
| eMachines     | eME732ZG                    | Notebook    | [6304ba86ef](https://linux-hardware.org/?probe=6304ba86ef) | May 12, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [e50b53ba02](https://linux-hardware.org/?probe=e50b53ba02) | May 12, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [a53ce6039b](https://linux-hardware.org/?probe=a53ce6039b) | May 12, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [5674fc5620](https://linux-hardware.org/?probe=5674fc5620) | May 12, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [56b6d0f154](https://linux-hardware.org/?probe=56b6d0f154) | May 12, 2022 |
| ASRock        | H310CM-HDV                  | Desktop     | [319f70da4e](https://linux-hardware.org/?probe=319f70da4e) | May 12, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [cf7ae5c07b](https://linux-hardware.org/?probe=cf7ae5c07b) | May 12, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [41c7fd7bcc](https://linux-hardware.org/?probe=41c7fd7bcc) | May 12, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [c0b6c60fb0](https://linux-hardware.org/?probe=c0b6c60fb0) | May 12, 2022 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [4cd5815707](https://linux-hardware.org/?probe=4cd5815707) | May 12, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [a4f4e7c199](https://linux-hardware.org/?probe=a4f4e7c199) | May 12, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [e4107f3e84](https://linux-hardware.org/?probe=e4107f3e84) | May 12, 2022 |
| Compaq        | Presario CQ-25              | Notebook    | [581b490f0c](https://linux-hardware.org/?probe=581b490f0c) | May 12, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [d14b68d592](https://linux-hardware.org/?probe=d14b68d592) | May 11, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [c37decd47b](https://linux-hardware.org/?probe=c37decd47b) | May 11, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [a6873c7d7b](https://linux-hardware.org/?probe=a6873c7d7b) | May 11, 2022 |
| ASUSTek       | B75M-A                      | Desktop     | [70ef1387b3](https://linux-hardware.org/?probe=70ef1387b3) | May 11, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [819ca99934](https://linux-hardware.org/?probe=819ca99934) | May 11, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [bc84347b65](https://linux-hardware.org/?probe=bc84347b65) | May 11, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [610c48d5c2](https://linux-hardware.org/?probe=610c48d5c2) | May 11, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [67db373009](https://linux-hardware.org/?probe=67db373009) | May 11, 2022 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [4060102b0d](https://linux-hardware.org/?probe=4060102b0d) | May 11, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [06a97b74c2](https://linux-hardware.org/?probe=06a97b74c2) | May 11, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [e118437b55](https://linux-hardware.org/?probe=e118437b55) | May 11, 2022 |
| ASRock        | N68-S3 UCC                  | Desktop     | [083ee33b93](https://linux-hardware.org/?probe=083ee33b93) | May 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [657c27be04](https://linux-hardware.org/?probe=657c27be04) | May 10, 2022 |
| Huanan        | X99 F8D V2.2                | Desktop     | [af98aacde1](https://linux-hardware.org/?probe=af98aacde1) | May 10, 2022 |
| MSI           | Z370 TOMAHAWK               | Desktop     | [89222d6d5a](https://linux-hardware.org/?probe=89222d6d5a) | May 10, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [0b131ecdc3](https://linux-hardware.org/?probe=0b131ecdc3) | May 10, 2022 |
| ASUSTek       | Q170T                       | Desktop     | [7b142a9bf8](https://linux-hardware.org/?probe=7b142a9bf8) | May 10, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [d329ab7f27](https://linux-hardware.org/?probe=d329ab7f27) | May 10, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [897ae85fd2](https://linux-hardware.org/?probe=897ae85fd2) | May 10, 2022 |
| HP            | Pavilion g6                 | Notebook    | [7b42128ef0](https://linux-hardware.org/?probe=7b42128ef0) | May 10, 2022 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [38838b0da0](https://linux-hardware.org/?probe=38838b0da0) | May 10, 2022 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [b0a089f59e](https://linux-hardware.org/?probe=b0a089f59e) | May 10, 2022 |
| ASRock        | FM2A55M-VG3+                | Desktop     | [43c813fe70](https://linux-hardware.org/?probe=43c813fe70) | May 10, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [21b06f22da](https://linux-hardware.org/?probe=21b06f22da) | May 09, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [876ec3c7c3](https://linux-hardware.org/?probe=876ec3c7c3) | May 09, 2022 |
| ASUSTek       | M2N-VM HDMI                 | Desktop     | [28ef8fe01d](https://linux-hardware.org/?probe=28ef8fe01d) | May 09, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [36fe76c490](https://linux-hardware.org/?probe=36fe76c490) | May 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c3da40525e](https://linux-hardware.org/?probe=c3da40525e) | May 09, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [5fbac11232](https://linux-hardware.org/?probe=5fbac11232) | May 09, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [2a916e3eb5](https://linux-hardware.org/?probe=2a916e3eb5) | May 09, 2022 |
| ASRock        | H81M-ITX                    | Desktop     | [7da59c1f4c](https://linux-hardware.org/?probe=7da59c1f4c) | May 09, 2022 |
| Timi          | TM1607                      | Notebook    | [3cdd16d975](https://linux-hardware.org/?probe=3cdd16d975) | May 09, 2022 |
| Acer          | Aspire TC-710 V:1.1         | Desktop     | [bc95d94be6](https://linux-hardware.org/?probe=bc95d94be6) | May 08, 2022 |
| Gigabyte      | P31-S3G                     | Desktop     | [98c00acfd0](https://linux-hardware.org/?probe=98c00acfd0) | May 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [ff7a5266e3](https://linux-hardware.org/?probe=ff7a5266e3) | May 08, 2022 |
| HP            | Notebook                    | Notebook    | [3e346da5bf](https://linux-hardware.org/?probe=3e346da5bf) | May 08, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [c7e61a8776](https://linux-hardware.org/?probe=c7e61a8776) | May 08, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [b532438c73](https://linux-hardware.org/?probe=b532438c73) | May 08, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [05b35ee0cc](https://linux-hardware.org/?probe=05b35ee0cc) | May 08, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [ee12f03755](https://linux-hardware.org/?probe=ee12f03755) | May 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [9127ce17dc](https://linux-hardware.org/?probe=9127ce17dc) | May 08, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [61776a02d4](https://linux-hardware.org/?probe=61776a02d4) | May 07, 2022 |
| K-Systems     | Crestline+ICH8M             | Notebook    | [e94aa3f1ff](https://linux-hardware.org/?probe=e94aa3f1ff) | May 07, 2022 |
| MSI           | 970A-G43                    | Desktop     | [3338da03cc](https://linux-hardware.org/?probe=3338da03cc) | May 07, 2022 |
| Dell          | 0M858N A00                  | Desktop     | [a864f8a7c4](https://linux-hardware.org/?probe=a864f8a7c4) | May 07, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [7a595e57da](https://linux-hardware.org/?probe=7a595e57da) | May 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6e0ebf856b](https://linux-hardware.org/?probe=6e0ebf856b) | May 07, 2022 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [38c0346cf7](https://linux-hardware.org/?probe=38c0346cf7) | May 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4f8a4f6d1d](https://linux-hardware.org/?probe=4f8a4f6d1d) | May 07, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [1f6748931c](https://linux-hardware.org/?probe=1f6748931c) | May 07, 2022 |
| ASUSTek       | H110M-R                     | Desktop     | [720be5218f](https://linux-hardware.org/?probe=720be5218f) | May 07, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [f115d870eb](https://linux-hardware.org/?probe=f115d870eb) | May 07, 2022 |
| Samsung       | R530/R730/P530              | Notebook    | [d209735fd8](https://linux-hardware.org/?probe=d209735fd8) | May 07, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [7847a3091b](https://linux-hardware.org/?probe=7847a3091b) | May 07, 2022 |
| Acer          | Aspire TC-391               | Desktop     | [ec090fb244](https://linux-hardware.org/?probe=ec090fb244) | May 07, 2022 |
| MSI           | GP60 2QE                    | Notebook    | [50a45201e9](https://linux-hardware.org/?probe=50a45201e9) | May 07, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [addef0004e](https://linux-hardware.org/?probe=addef0004e) | May 06, 2022 |
| Lenovo        | 3000 G410                   | Notebook    | [1865fb9b1c](https://linux-hardware.org/?probe=1865fb9b1c) | May 06, 2022 |
| Acer          | Extensa 2519                | Notebook    | [86f643f1bb](https://linux-hardware.org/?probe=86f643f1bb) | May 06, 2022 |
| ASUSTek       | VivoBook S15 X530UF         | Notebook    | [3d6fe0b407](https://linux-hardware.org/?probe=3d6fe0b407) | May 06, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [a395b8eda0](https://linux-hardware.org/?probe=a395b8eda0) | May 06, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [d0e53387f7](https://linux-hardware.org/?probe=d0e53387f7) | May 05, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [24e9a90d68](https://linux-hardware.org/?probe=24e9a90d68) | May 05, 2022 |
| Huanan        | X99-F8                      | Desktop     | [f9699aaa3e](https://linux-hardware.org/?probe=f9699aaa3e) | May 05, 2022 |
| MSI           | H410I PRO WIFI              | Desktop     | [bc1d89fabc](https://linux-hardware.org/?probe=bc1d89fabc) | May 05, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [e533455f48](https://linux-hardware.org/?probe=e533455f48) | May 05, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | Notebook    | [5c730dc365](https://linux-hardware.org/?probe=5c730dc365) | May 05, 2022 |
| MSI           | A520M-A PRO                 | Desktop     | [ab6c74c421](https://linux-hardware.org/?probe=ab6c74c421) | May 05, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [ef0e05c7aa](https://linux-hardware.org/?probe=ef0e05c7aa) | May 05, 2022 |
| HP            | Pavilion Laptop 14-ce1xx... | Notebook    | [cc78e4f439](https://linux-hardware.org/?probe=cc78e4f439) | May 05, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PA... | Notebook    | [a6a0d2276e](https://linux-hardware.org/?probe=a6a0d2276e) | May 05, 2022 |
| Gigabyte      | IMB1900N                    | Desktop     | [8ed8cb17d5](https://linux-hardware.org/?probe=8ed8cb17d5) | May 04, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [61c02ee0e9](https://linux-hardware.org/?probe=61c02ee0e9) | May 04, 2022 |
| MSI           | 970A-G43                    | Desktop     | [8b6588eada](https://linux-hardware.org/?probe=8b6588eada) | May 04, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [08bd0f2662](https://linux-hardware.org/?probe=08bd0f2662) | May 04, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [506ffac23c](https://linux-hardware.org/?probe=506ffac23c) | May 04, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c25a0f8526](https://linux-hardware.org/?probe=c25a0f8526) | May 04, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [c89b45b9ad](https://linux-hardware.org/?probe=c89b45b9ad) | May 04, 2022 |
| Lenovo        | ThinkCentre M55 8795B1G     | Desktop     | [295fe2b588](https://linux-hardware.org/?probe=295fe2b588) | May 04, 2022 |
| Lenovo        | ThinkCentre M55 8795B1G     | Desktop     | [b88ff00133](https://linux-hardware.org/?probe=b88ff00133) | May 04, 2022 |
| Unknown       | RS690-SB600                 | Desktop     | [a5a63d87df](https://linux-hardware.org/?probe=a5a63d87df) | May 04, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [5e1f408239](https://linux-hardware.org/?probe=5e1f408239) | May 04, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [256b7b7658](https://linux-hardware.org/?probe=256b7b7658) | May 03, 2022 |
| Lenovo        | ThinkPad T480 20L5000ART    | Notebook    | [f4cd0ce06c](https://linux-hardware.org/?probe=f4cd0ce06c) | May 03, 2022 |
| Lenovo        | ThinkPad T480 20L5000ART    | Notebook    | [4360d63d4a](https://linux-hardware.org/?probe=4360d63d4a) | May 03, 2022 |
| Unknown       | RS690-SB600                 | Desktop     | [cdda671470](https://linux-hardware.org/?probe=cdda671470) | May 03, 2022 |
| Irbis         | TW39                        | Notebook    | [38844a7f5e](https://linux-hardware.org/?probe=38844a7f5e) | May 03, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [2f061f5e18](https://linux-hardware.org/?probe=2f061f5e18) | May 03, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [ee0d654e52](https://linux-hardware.org/?probe=ee0d654e52) | May 03, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [2010f5f8cc](https://linux-hardware.org/?probe=2010f5f8cc) | May 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [aed319bae8](https://linux-hardware.org/?probe=aed319bae8) | May 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [755bcaa97c](https://linux-hardware.org/?probe=755bcaa97c) | May 03, 2022 |
| ABIT          | F-I90HD                     | Desktop     | [a76a1e15a0](https://linux-hardware.org/?probe=a76a1e15a0) | May 03, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [73358636b6](https://linux-hardware.org/?probe=73358636b6) | May 03, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [fd61db399b](https://linux-hardware.org/?probe=fd61db399b) | May 03, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [6b961e699a](https://linux-hardware.org/?probe=6b961e699a) | May 03, 2022 |
| ASUSTek       | B150-PRO D3                 | Desktop     | [1620040802](https://linux-hardware.org/?probe=1620040802) | May 02, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [68a966265b](https://linux-hardware.org/?probe=68a966265b) | May 02, 2022 |
| ASUSTek       | X551CAP                     | Notebook    | [c4f8ae2abf](https://linux-hardware.org/?probe=c4f8ae2abf) | May 02, 2022 |
| MSI           | NF520T-C35                  | Desktop     | [626f45376a](https://linux-hardware.org/?probe=626f45376a) | May 02, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [ab4b021f1b](https://linux-hardware.org/?probe=ab4b021f1b) | May 02, 2022 |
| Dell          | Vostro A860                 | Notebook    | [c314c4b269](https://linux-hardware.org/?probe=c314c4b269) | May 02, 2022 |
| Huanan        | X79 INTEL (INTEL Xeon E5... | Desktop     | [f776c43073](https://linux-hardware.org/?probe=f776c43073) | May 02, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [e0983f2b8c](https://linux-hardware.org/?probe=e0983f2b8c) | May 02, 2022 |
| ASRock        | B450M-HDV                   | Desktop     | [1e0e1acbd3](https://linux-hardware.org/?probe=1e0e1acbd3) | May 02, 2022 |
| ICL           | RAYbook Si1507              | Notebook    | [eaf9bd7ea3](https://linux-hardware.org/?probe=eaf9bd7ea3) | May 02, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [fa46d0866b](https://linux-hardware.org/?probe=fa46d0866b) | May 02, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [ccabd73c80](https://linux-hardware.org/?probe=ccabd73c80) | May 02, 2022 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [e6a2ee3ec5](https://linux-hardware.org/?probe=e6a2ee3ec5) | May 02, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [f77de23642](https://linux-hardware.org/?probe=f77de23642) | May 02, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [c19f2858f0](https://linux-hardware.org/?probe=c19f2858f0) | May 01, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [8532d4b88f](https://linux-hardware.org/?probe=8532d4b88f) | May 01, 2022 |
| ASRock        | Z270 Gaming K4              | Desktop     | [c497e3c5a9](https://linux-hardware.org/?probe=c497e3c5a9) | May 01, 2022 |
| Intel         | Unknown                     | Notebook    | [8353c6d487](https://linux-hardware.org/?probe=8353c6d487) | May 01, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [57d77dbfdd](https://linux-hardware.org/?probe=57d77dbfdd) | May 01, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [67404fab24](https://linux-hardware.org/?probe=67404fab24) | May 01, 2022 |
| Gigabyte      | H310M S2P                   | Desktop     | [c5303ab540](https://linux-hardware.org/?probe=c5303ab540) | May 01, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [c7ac6032f5](https://linux-hardware.org/?probe=c7ac6032f5) | May 01, 2022 |
| Acer          | Aspire TC-705               | Desktop     | [0e4b8cfff4](https://linux-hardware.org/?probe=0e4b8cfff4) | May 01, 2022 |
| Supermicro    | X11SSE-F                    | Mini pc     | [01c5f4fe66](https://linux-hardware.org/?probe=01c5f4fe66) | May 01, 2022 |
| Lenovo        | H420                        | Desktop     | [2f22f32e19](https://linux-hardware.org/?probe=2f22f32e19) | May 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [467c181d49](https://linux-hardware.org/?probe=467c181d49) | May 01, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [95d109769d](https://linux-hardware.org/?probe=95d109769d) | May 01, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [8538f5cbeb](https://linux-hardware.org/?probe=8538f5cbeb) | May 01, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [da9df39f8c](https://linux-hardware.org/?probe=da9df39f8c) | Apr 30, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [72ea7f5155](https://linux-hardware.org/?probe=72ea7f5155) | Apr 30, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [23a77acbe8](https://linux-hardware.org/?probe=23a77acbe8) | Apr 30, 2022 |
| Lenovo        | ThinkPad T61 7659A39        | Notebook    | [e5c32846e2](https://linux-hardware.org/?probe=e5c32846e2) | Apr 30, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [a788b08450](https://linux-hardware.org/?probe=a788b08450) | Apr 30, 2022 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [b6658c2ada](https://linux-hardware.org/?probe=b6658c2ada) | Apr 30, 2022 |
| Acer          | Aspire A517-51G             | Notebook    | [a7e637b1af](https://linux-hardware.org/?probe=a7e637b1af) | Apr 30, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [24faa6d3b2](https://linux-hardware.org/?probe=24faa6d3b2) | Apr 30, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [5220d21e84](https://linux-hardware.org/?probe=5220d21e84) | Apr 30, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [81d7fd8d2e](https://linux-hardware.org/?probe=81d7fd8d2e) | Apr 30, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [d5d92c2890](https://linux-hardware.org/?probe=d5d92c2890) | Apr 30, 2022 |
| HP            | ProBook 440 G7              | Notebook    | [6bba4f2274](https://linux-hardware.org/?probe=6bba4f2274) | Apr 30, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a53000596e](https://linux-hardware.org/?probe=a53000596e) | Apr 30, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [3d56136487](https://linux-hardware.org/?probe=3d56136487) | Apr 30, 2022 |
| Gigabyte      | H610I DDR4                  | Desktop     | [b9ee954651](https://linux-hardware.org/?probe=b9ee954651) | Apr 30, 2022 |
| Gigabyte      | H610I DDR4                  | Desktop     | [ead878ad96](https://linux-hardware.org/?probe=ead878ad96) | Apr 29, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [56fabb8cec](https://linux-hardware.org/?probe=56fabb8cec) | Apr 29, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [442670a18f](https://linux-hardware.org/?probe=442670a18f) | Apr 29, 2022 |
| ASUSTek       | K52N                        | Notebook    | [29f3f98ad0](https://linux-hardware.org/?probe=29f3f98ad0) | Apr 29, 2022 |
| ASUSTek       | X553MA                      | Notebook    | [2c284d0f8c](https://linux-hardware.org/?probe=2c284d0f8c) | Apr 29, 2022 |
| Acer          | TravelMate 2490             | Notebook    | [8cc2cf84f4](https://linux-hardware.org/?probe=8cc2cf84f4) | Apr 29, 2022 |
| ASUSTek       | M4N68T                      | Desktop     | [8113a96dff](https://linux-hardware.org/?probe=8113a96dff) | Apr 29, 2022 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | Notebook    | [d5828a8f9f](https://linux-hardware.org/?probe=d5828a8f9f) | Apr 29, 2022 |
| Dell          | Latitude 3420               | Notebook    | [d1239521b9](https://linux-hardware.org/?probe=d1239521b9) | Apr 29, 2022 |
| Lite-On       | 08FCh E01                   | Desktop     | [876d70350c](https://linux-hardware.org/?probe=876d70350c) | Apr 29, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [d3872db37e](https://linux-hardware.org/?probe=d3872db37e) | Apr 29, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [9686556653](https://linux-hardware.org/?probe=9686556653) | Apr 29, 2022 |
| Gigabyte      | H55M-UD2H                   | Desktop     | [12e326fab8](https://linux-hardware.org/?probe=12e326fab8) | Apr 28, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [c4fc81307d](https://linux-hardware.org/?probe=c4fc81307d) | Apr 28, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [02b4a9bd72](https://linux-hardware.org/?probe=02b4a9bd72) | Apr 28, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [22369d04ff](https://linux-hardware.org/?probe=22369d04ff) | Apr 28, 2022 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [7669e97557](https://linux-hardware.org/?probe=7669e97557) | Apr 28, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [7050d2a05f](https://linux-hardware.org/?probe=7050d2a05f) | Apr 28, 2022 |
| ECS           | A780LM-M2                   | Desktop     | [ae8fabafb3](https://linux-hardware.org/?probe=ae8fabafb3) | Apr 28, 2022 |
| ASUSTek       | X550LC                      | Notebook    | [c5f3191403](https://linux-hardware.org/?probe=c5f3191403) | Apr 27, 2022 |
| Matsushita... | CF-30CTQAZBG                | Notebook    | [7935a074aa](https://linux-hardware.org/?probe=7935a074aa) | Apr 27, 2022 |
| Acer          | Aspire 6930G                | Notebook    | [f0c8ad777d](https://linux-hardware.org/?probe=f0c8ad777d) | Apr 27, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [155297b5da](https://linux-hardware.org/?probe=155297b5da) | Apr 27, 2022 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [217e24d827](https://linux-hardware.org/?probe=217e24d827) | Apr 27, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [8332dfca0b](https://linux-hardware.org/?probe=8332dfca0b) | Apr 27, 2022 |
| Lenovo        | SHARKBAY 31900059 STD       | All in one  | [910be59af9](https://linux-hardware.org/?probe=910be59af9) | Apr 27, 2022 |
| Acer          | Aspire 5625G                | Notebook    | [654e51fb7c](https://linux-hardware.org/?probe=654e51fb7c) | Apr 27, 2022 |
| Gigabyte      | F2A68HM-S1                  | Desktop     | [e1f76d9f38](https://linux-hardware.org/?probe=e1f76d9f38) | Apr 27, 2022 |
| HP            | 2000                        | Notebook    | [65891d90cc](https://linux-hardware.org/?probe=65891d90cc) | Apr 27, 2022 |
| ASUSTek       | K50IE                       | Notebook    | [5d8cdec08c](https://linux-hardware.org/?probe=5d8cdec08c) | Apr 27, 2022 |
| MSI           | B85M-P33                    | Desktop     | [b18d0beead](https://linux-hardware.org/?probe=b18d0beead) | Apr 27, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [32fd06793f](https://linux-hardware.org/?probe=32fd06793f) | Apr 27, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [2670b60f3c](https://linux-hardware.org/?probe=2670b60f3c) | Apr 27, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [a756a0148d](https://linux-hardware.org/?probe=a756a0148d) | Apr 27, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [67c03df307](https://linux-hardware.org/?probe=67c03df307) | Apr 27, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [7630e097d9](https://linux-hardware.org/?probe=7630e097d9) | Apr 27, 2022 |
| Acer          | Aspire 5625G                | Notebook    | [6dfe24b002](https://linux-hardware.org/?probe=6dfe24b002) | Apr 26, 2022 |
| Acer          | Aspire V3-571               | Notebook    | [65d778f931](https://linux-hardware.org/?probe=65d778f931) | Apr 26, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [9fc1163ba6](https://linux-hardware.org/?probe=9fc1163ba6) | Apr 26, 2022 |
| Lenovo        | B450 1S16800336100RT        | Notebook    | [ddaca02cbd](https://linux-hardware.org/?probe=ddaca02cbd) | Apr 26, 2022 |
| Acer          | Aspire 7736                 | Notebook    | [a0b8522191](https://linux-hardware.org/?probe=a0b8522191) | Apr 26, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [458eb421b9](https://linux-hardware.org/?probe=458eb421b9) | Apr 26, 2022 |
| ZoomSmart     | A8006                       | Tablet      | [988bb3eda7](https://linux-hardware.org/?probe=988bb3eda7) | Apr 26, 2022 |
| ASUSTek       | ZenBook UX434FQ_UX434FQ     | Notebook    | [9f8c80ed7d](https://linux-hardware.org/?probe=9f8c80ed7d) | Apr 26, 2022 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [26a7e61215](https://linux-hardware.org/?probe=26a7e61215) | Apr 26, 2022 |
| ZoomSmart     | A8006                       | Tablet      | [fcc5f522b3](https://linux-hardware.org/?probe=fcc5f522b3) | Apr 26, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [a8934b94b8](https://linux-hardware.org/?probe=a8934b94b8) | Apr 26, 2022 |
| ASUSTek       | K50ID                       | Notebook    | [7d7776358b](https://linux-hardware.org/?probe=7d7776358b) | Apr 26, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [b48dc21646](https://linux-hardware.org/?probe=b48dc21646) | Apr 26, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [7e8c222029](https://linux-hardware.org/?probe=7e8c222029) | Apr 26, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [feea6c0d76](https://linux-hardware.org/?probe=feea6c0d76) | Apr 25, 2022 |
| Lenovo        | 3132 SDK0J40697 WIN 3305... | Desktop     | [c26bb7d11c](https://linux-hardware.org/?probe=c26bb7d11c) | Apr 25, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [5ac12e226f](https://linux-hardware.org/?probe=5ac12e226f) | Apr 25, 2022 |
| Sony          | SVE1712V1RB                 | Notebook    | [e63891da73](https://linux-hardware.org/?probe=e63891da73) | Apr 25, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [f7290e5680](https://linux-hardware.org/?probe=f7290e5680) | Apr 25, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [5991a49238](https://linux-hardware.org/?probe=5991a49238) | Apr 25, 2022 |
| iRU           | LPGR.469559.001             | Notebook    | [3758808bc5](https://linux-hardware.org/?probe=3758808bc5) | Apr 25, 2022 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [7c068a38f3](https://linux-hardware.org/?probe=7c068a38f3) | Apr 25, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [f0f822fa1b](https://linux-hardware.org/?probe=f0f822fa1b) | Apr 25, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [643eb9c031](https://linux-hardware.org/?probe=643eb9c031) | Apr 25, 2022 |
| Toshiba       | Satellite U300              | Notebook    | [1fa01f4156](https://linux-hardware.org/?probe=1fa01f4156) | Apr 25, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [99bd45c11d](https://linux-hardware.org/?probe=99bd45c11d) | Apr 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [4479bed84f](https://linux-hardware.org/?probe=4479bed84f) | Apr 25, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [4fd4202535](https://linux-hardware.org/?probe=4fd4202535) | Apr 25, 2022 |
| HP            | Pavilion dv6000             | Notebook    | [f41a09331b](https://linux-hardware.org/?probe=f41a09331b) | Apr 24, 2022 |
| ASUSTek       | S400CA                      | Notebook    | [b9b3e314e5](https://linux-hardware.org/?probe=b9b3e314e5) | Apr 24, 2022 |
| Notebook      | W65_67SF                    | Notebook    | [37712c1d2b](https://linux-hardware.org/?probe=37712c1d2b) | Apr 24, 2022 |
| Lenovo        | G510 20238                  | Notebook    | [906f1626d7](https://linux-hardware.org/?probe=906f1626d7) | Apr 24, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [9d244bbdcc](https://linux-hardware.org/?probe=9d244bbdcc) | Apr 24, 2022 |
| HP            | Pavilion dv6000 (RE386EA... | Notebook    | [9d00048a2d](https://linux-hardware.org/?probe=9d00048a2d) | Apr 24, 2022 |
| ASUSTek       | UX32A                       | Notebook    | [0cbf3a6f80](https://linux-hardware.org/?probe=0cbf3a6f80) | Apr 24, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [a4c9b28b0f](https://linux-hardware.org/?probe=a4c9b28b0f) | Apr 24, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [5c94950753](https://linux-hardware.org/?probe=5c94950753) | Apr 24, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [6dad6af75e](https://linux-hardware.org/?probe=6dad6af75e) | Apr 24, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [12060212f8](https://linux-hardware.org/?probe=12060212f8) | Apr 24, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [fee9fe1263](https://linux-hardware.org/?probe=fee9fe1263) | Apr 24, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [734fbc9db6](https://linux-hardware.org/?probe=734fbc9db6) | Apr 24, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [c3e874826b](https://linux-hardware.org/?probe=c3e874826b) | Apr 24, 2022 |
| Acer          | Aspire ES1-521              | Notebook    | [0d1857219f](https://linux-hardware.org/?probe=0d1857219f) | Apr 24, 2022 |
| Acer          | Aspire TC-390               | Desktop     | [69a7263b5a](https://linux-hardware.org/?probe=69a7263b5a) | Apr 24, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [fa2c44bf71](https://linux-hardware.org/?probe=fa2c44bf71) | Apr 24, 2022 |
| Haier         | U1520SD                     | Notebook    | [a546af91bb](https://linux-hardware.org/?probe=a546af91bb) | Apr 24, 2022 |
| Acer          | AOD270                      | Notebook    | [50198f1c2f](https://linux-hardware.org/?probe=50198f1c2f) | Apr 24, 2022 |
| Haier         | S424                        | Notebook    | [9dcf76fcf7](https://linux-hardware.org/?probe=9dcf76fcf7) | Apr 24, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [0ca4241f02](https://linux-hardware.org/?probe=0ca4241f02) | Apr 23, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d68949ed95](https://linux-hardware.org/?probe=d68949ed95) | Apr 23, 2022 |
| ASUSTek       | AM1I-A                      | Desktop     | [b041f2cde0](https://linux-hardware.org/?probe=b041f2cde0) | Apr 23, 2022 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [0324fe4cc6](https://linux-hardware.org/?probe=0324fe4cc6) | Apr 23, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [c1cd0a61e1](https://linux-hardware.org/?probe=c1cd0a61e1) | Apr 23, 2022 |
| Sony          | SVE1512H1RW                 | Notebook    | [0fc6ea9996](https://linux-hardware.org/?probe=0fc6ea9996) | Apr 23, 2022 |
| ASUSTek       | N550JV                      | Notebook    | [acbc0ffb3b](https://linux-hardware.org/?probe=acbc0ffb3b) | Apr 23, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [5d81eb4631](https://linux-hardware.org/?probe=5d81eb4631) | Apr 23, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [d01bcb69ea](https://linux-hardware.org/?probe=d01bcb69ea) | Apr 23, 2022 |
| Gigabyte      | E2500N                      | Desktop     | [92784cd549](https://linux-hardware.org/?probe=92784cd549) | Apr 23, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [661b8cc46d](https://linux-hardware.org/?probe=661b8cc46d) | Apr 23, 2022 |
| Toshiba       | Satellite U300              | Notebook    | [9db41e52eb](https://linux-hardware.org/?probe=9db41e52eb) | Apr 23, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [5357a4e149](https://linux-hardware.org/?probe=5357a4e149) | Apr 23, 2022 |
| ASRock        | H410M-HVS                   | Desktop     | [97f2c666ff](https://linux-hardware.org/?probe=97f2c666ff) | Apr 23, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [0033f5692b](https://linux-hardware.org/?probe=0033f5692b) | Apr 23, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [a10fb9fe10](https://linux-hardware.org/?probe=a10fb9fe10) | Apr 23, 2022 |
| ASRock        | QC5000M                     | Desktop     | [b9341a0704](https://linux-hardware.org/?probe=b9341a0704) | Apr 23, 2022 |
| Acer          | AOD257                      | Notebook    | [9b11649bce](https://linux-hardware.org/?probe=9b11649bce) | Apr 22, 2022 |
| Acer          | Aspire 7110                 | Notebook    | [6e46dbc582](https://linux-hardware.org/?probe=6e46dbc582) | Apr 22, 2022 |
| Lenovo        | ThinkPad X230 2325I63       | Notebook    | [22522f125f](https://linux-hardware.org/?probe=22522f125f) | Apr 22, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [1d8b10f388](https://linux-hardware.org/?probe=1d8b10f388) | Apr 22, 2022 |
| Acer          | AOD257                      | Notebook    | [e321b17ef8](https://linux-hardware.org/?probe=e321b17ef8) | Apr 22, 2022 |
| MSI           | MS-7267                     | Desktop     | [d0d0dc78d5](https://linux-hardware.org/?probe=d0d0dc78d5) | Apr 22, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4033356f39](https://linux-hardware.org/?probe=4033356f39) | Apr 22, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [f682ddf4ed](https://linux-hardware.org/?probe=f682ddf4ed) | Apr 22, 2022 |
| MSI           | B250M BAZOOKA               | Desktop     | [36386a3115](https://linux-hardware.org/?probe=36386a3115) | Apr 22, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [ec4003c77d](https://linux-hardware.org/?probe=ec4003c77d) | Apr 22, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [c80263e88a](https://linux-hardware.org/?probe=c80263e88a) | Apr 22, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4bb685c310](https://linux-hardware.org/?probe=4bb685c310) | Apr 22, 2022 |
| ASUSTek       | P5B                         | Desktop     | [00f8e07a8d](https://linux-hardware.org/?probe=00f8e07a8d) | Apr 22, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [508d41c597](https://linux-hardware.org/?probe=508d41c597) | Apr 22, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [ef07d8d824](https://linux-hardware.org/?probe=ef07d8d824) | Apr 22, 2022 |
| Pegatron      | A15W8                       | Notebook    | [93ddbc3b82](https://linux-hardware.org/?probe=93ddbc3b82) | Apr 22, 2022 |
| Colorful T... | C.H81A-BTC V20              | Desktop     | [1f0dab0203](https://linux-hardware.org/?probe=1f0dab0203) | Apr 22, 2022 |
| Pegatron      | A15W8                       | Notebook    | [c02c5b8796](https://linux-hardware.org/?probe=c02c5b8796) | Apr 22, 2022 |
| Gigabyte      | U2152                       | Notebook    | [0226fcddee](https://linux-hardware.org/?probe=0226fcddee) | Apr 22, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [de27893552](https://linux-hardware.org/?probe=de27893552) | Apr 22, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [1b5a8b5542](https://linux-hardware.org/?probe=1b5a8b5542) | Apr 21, 2022 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [98eb9909d0](https://linux-hardware.org/?probe=98eb9909d0) | Apr 21, 2022 |
| Acer          | Aspire 7540                 | Notebook    | [0700a2eb31](https://linux-hardware.org/?probe=0700a2eb31) | Apr 21, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [7ab5ec522c](https://linux-hardware.org/?probe=7ab5ec522c) | Apr 21, 2022 |
| Dell          | 02X6YT A01                  | Desktop     | [f672bdbf0e](https://linux-hardware.org/?probe=f672bdbf0e) | Apr 21, 2022 |
| KLLISRE       | X99-B5 V1.1                 | Desktop     | [14e557ad2d](https://linux-hardware.org/?probe=14e557ad2d) | Apr 21, 2022 |
| MSI           | 0A48                        | Desktop     | [1e73c16d0c](https://linux-hardware.org/?probe=1e73c16d0c) | Apr 21, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [725dad09bf](https://linux-hardware.org/?probe=725dad09bf) | Apr 21, 2022 |
| ASUSTek       | F5SL                        | Notebook    | [a5cf2fd4ca](https://linux-hardware.org/?probe=a5cf2fd4ca) | Apr 21, 2022 |
| MSI           | Sword 15 A11UE              | Notebook    | [c9316aedb8](https://linux-hardware.org/?probe=c9316aedb8) | Apr 21, 2022 |
| Gigabyte      | H310M S2                    | Desktop     | [0f18c98ee7](https://linux-hardware.org/?probe=0f18c98ee7) | Apr 21, 2022 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [8ed5a0f97a](https://linux-hardware.org/?probe=8ed5a0f97a) | Apr 21, 2022 |
| MSI           | Z97-G43 GAMING              | Desktop     | [a4d2dc6c95](https://linux-hardware.org/?probe=a4d2dc6c95) | Apr 21, 2022 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [089f66bac4](https://linux-hardware.org/?probe=089f66bac4) | Apr 20, 2022 |
| ASUSTek       | U35JC                       | Notebook    | [d5ba4e2fdf](https://linux-hardware.org/?probe=d5ba4e2fdf) | Apr 20, 2022 |
| Digma         | CITI 10 C402T CS1044EW      | Tablet      | [c9719f58e9](https://linux-hardware.org/?probe=c9719f58e9) | Apr 20, 2022 |
| Dell          | Precision M2300             | Notebook    | [05928bee5f](https://linux-hardware.org/?probe=05928bee5f) | Apr 20, 2022 |
| Gigabyte      | H310M H                     | Desktop     | [9a462cda5a](https://linux-hardware.org/?probe=9a462cda5a) | Apr 20, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [76bcd3a380](https://linux-hardware.org/?probe=76bcd3a380) | Apr 20, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [1d8b7fa1f2](https://linux-hardware.org/?probe=1d8b7fa1f2) | Apr 20, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [96e7ccb1b4](https://linux-hardware.org/?probe=96e7ccb1b4) | Apr 20, 2022 |
| Unknown       | RS690-SB600                 | Desktop     | [0cb86e267f](https://linux-hardware.org/?probe=0cb86e267f) | Apr 20, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [f1881dec46](https://linux-hardware.org/?probe=f1881dec46) | Apr 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [b09a55b7ad](https://linux-hardware.org/?probe=b09a55b7ad) | Apr 19, 2022 |
| ASUSTek       | X301A1                      | Notebook    | [b935ecb34c](https://linux-hardware.org/?probe=b935ecb34c) | Apr 19, 2022 |
| HP            | 8437                        | Desktop     | [f359fffed7](https://linux-hardware.org/?probe=f359fffed7) | Apr 19, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [a3bf1cf766](https://linux-hardware.org/?probe=a3bf1cf766) | Apr 19, 2022 |
| Huanan        | X79 V2.47                   | Desktop     | [7441d98b6a](https://linux-hardware.org/?probe=7441d98b6a) | Apr 19, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [4fd2fa24e4](https://linux-hardware.org/?probe=4fd2fa24e4) | Apr 19, 2022 |
| MSI           | MS-7388                     | Desktop     | [2d133cd746](https://linux-hardware.org/?probe=2d133cd746) | Apr 19, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [80950d86dc](https://linux-hardware.org/?probe=80950d86dc) | Apr 19, 2022 |
| Lenovo        | 312F NOK                    | Mini pc     | [98fdf4128a](https://linux-hardware.org/?probe=98fdf4128a) | Apr 19, 2022 |
| Lenovo        | ThinkPad X230 2324A15       | Notebook    | [8ff57cadde](https://linux-hardware.org/?probe=8ff57cadde) | Apr 19, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [264d31f34e](https://linux-hardware.org/?probe=264d31f34e) | Apr 19, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [72972fdcd8](https://linux-hardware.org/?probe=72972fdcd8) | Apr 19, 2022 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [10f79ec4bc](https://linux-hardware.org/?probe=10f79ec4bc) | Apr 19, 2022 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [26c006e6e3](https://linux-hardware.org/?probe=26c006e6e3) | Apr 19, 2022 |
| MSI           | Z97-G43 GAMING              | Desktop     | [927a1a0b8d](https://linux-hardware.org/?probe=927a1a0b8d) | Apr 18, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [ec0d75d365](https://linux-hardware.org/?probe=ec0d75d365) | Apr 18, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [3ebe403371](https://linux-hardware.org/?probe=3ebe403371) | Apr 18, 2022 |
| AMI           | Intel                       | Convertible | [ed2743ce85](https://linux-hardware.org/?probe=ed2743ce85) | Apr 18, 2022 |
| Acer          | P7YE0                       | Notebook    | [5e81ff3f2e](https://linux-hardware.org/?probe=5e81ff3f2e) | Apr 18, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [8d13032194](https://linux-hardware.org/?probe=8d13032194) | Apr 18, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [e3a29e4f7f](https://linux-hardware.org/?probe=e3a29e4f7f) | Apr 18, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [f8696ef7df](https://linux-hardware.org/?probe=f8696ef7df) | Apr 18, 2022 |
| ASUSTek       | N56VV                       | Notebook    | [2e4a4c394e](https://linux-hardware.org/?probe=2e4a4c394e) | Apr 18, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [1bfd1d7042](https://linux-hardware.org/?probe=1bfd1d7042) | Apr 18, 2022 |
| ASUSTek       | N56VV                       | Notebook    | [2ad328ebc8](https://linux-hardware.org/?probe=2ad328ebc8) | Apr 18, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [71ace683c7](https://linux-hardware.org/?probe=71ace683c7) | Apr 18, 2022 |
| ASUSTek       | M4A88T-I DELUXE             | Desktop     | [24d5e6293f](https://linux-hardware.org/?probe=24d5e6293f) | Apr 18, 2022 |
| Acer          | RS780HVF                    | Desktop     | [cfccb88227](https://linux-hardware.org/?probe=cfccb88227) | Apr 18, 2022 |
| Lenovo        | ThinkPad T520 4243RT9       | Notebook    | [d948d987b4](https://linux-hardware.org/?probe=d948d987b4) | Apr 18, 2022 |
| Biostar       | A320MH                      | Desktop     | [9beb151bac](https://linux-hardware.org/?probe=9beb151bac) | Apr 18, 2022 |
| Toshiba       | Satellite Pro L300          | Notebook    | [6b08a26a10](https://linux-hardware.org/?probe=6b08a26a10) | Apr 18, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [f5e7c2d5a1](https://linux-hardware.org/?probe=f5e7c2d5a1) | Apr 18, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [0e97aa77b4](https://linux-hardware.org/?probe=0e97aa77b4) | Apr 17, 2022 |
| ASUSTek       | UX303LB                     | Notebook    | [104779add9](https://linux-hardware.org/?probe=104779add9) | Apr 17, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [28836e512c](https://linux-hardware.org/?probe=28836e512c) | Apr 17, 2022 |
| HP            | 250 G2                      | Notebook    | [eafcfe8215](https://linux-hardware.org/?probe=eafcfe8215) | Apr 17, 2022 |
| Sony          | SVF1521L1RB                 | Notebook    | [e2034a7617](https://linux-hardware.org/?probe=e2034a7617) | Apr 17, 2022 |
| ASUSTek       | X541NC                      | Notebook    | [d1dc342eb9](https://linux-hardware.org/?probe=d1dc342eb9) | Apr 17, 2022 |
| ASUSTek       | X550EP                      | Notebook    | [fbc44882a3](https://linux-hardware.org/?probe=fbc44882a3) | Apr 17, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [a245e4681b](https://linux-hardware.org/?probe=a245e4681b) | Apr 17, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [b3dd50d275](https://linux-hardware.org/?probe=b3dd50d275) | Apr 17, 2022 |
| Samsung       | R425D/R525D                 | Notebook    | [84fdb88779](https://linux-hardware.org/?probe=84fdb88779) | Apr 17, 2022 |
| ASUSTek       | M4A785-M                    | Desktop     | [25526ee77d](https://linux-hardware.org/?probe=25526ee77d) | Apr 17, 2022 |
| MACHINIST     | B75 PRO V1.0                | Desktop     | [bc17af5881](https://linux-hardware.org/?probe=bc17af5881) | Apr 17, 2022 |
| ASUSTek       | P8Z77-V LX2                 | Desktop     | [a61fc6c54e](https://linux-hardware.org/?probe=a61fc6c54e) | Apr 17, 2022 |
| HP            | EliteBook 8560w             | Notebook    | [1c7ab231f3](https://linux-hardware.org/?probe=1c7ab231f3) | Apr 17, 2022 |
| ASUSTek       | TUF Gaming H570-PRO         | Desktop     | [94b69dd7bc](https://linux-hardware.org/?probe=94b69dd7bc) | Apr 17, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [1675f1f8a1](https://linux-hardware.org/?probe=1675f1f8a1) | Apr 17, 2022 |
| Acer          | Aspire F5-571G              | Notebook    | [16518ad895](https://linux-hardware.org/?probe=16518ad895) | Apr 17, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [211859a28f](https://linux-hardware.org/?probe=211859a28f) | Apr 17, 2022 |
| Acer          | Aspire C24-865              | All in one  | [873c58a401](https://linux-hardware.org/?probe=873c58a401) | Apr 17, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [ae0700c71c](https://linux-hardware.org/?probe=ae0700c71c) | Apr 17, 2022 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [5aa8ec8c7e](https://linux-hardware.org/?probe=5aa8ec8c7e) | Apr 17, 2022 |
| Acer          | Aspire 5720Z                | Notebook    | [e8155eac20](https://linux-hardware.org/?probe=e8155eac20) | Apr 16, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [f2e4d7052d](https://linux-hardware.org/?probe=f2e4d7052d) | Apr 16, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [861c47b139](https://linux-hardware.org/?probe=861c47b139) | Apr 16, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [c2a4357527](https://linux-hardware.org/?probe=c2a4357527) | Apr 16, 2022 |
| Lenovo        | IdeaPad Z565 20066          | Notebook    | [258c94f58b](https://linux-hardware.org/?probe=258c94f58b) | Apr 16, 2022 |
| Acer          | IPISB-AG                    | All in one  | [e263b7e641](https://linux-hardware.org/?probe=e263b7e641) | Apr 16, 2022 |
| DNS           | W510LU                      | Notebook    | [b3f74317f2](https://linux-hardware.org/?probe=b3f74317f2) | Apr 16, 2022 |
| Dell          | Precision M6800             | Notebook    | [a632e8de16](https://linux-hardware.org/?probe=a632e8de16) | Apr 16, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [690867d18c](https://linux-hardware.org/?probe=690867d18c) | Apr 16, 2022 |
| Samsung       | NB30P                       | Notebook    | [a64bf01edf](https://linux-hardware.org/?probe=a64bf01edf) | Apr 16, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [c9510b64e8](https://linux-hardware.org/?probe=c9510b64e8) | Apr 16, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [559213734d](https://linux-hardware.org/?probe=559213734d) | Apr 16, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [c20f1de565](https://linux-hardware.org/?probe=c20f1de565) | Apr 16, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [cb64383c99](https://linux-hardware.org/?probe=cb64383c99) | Apr 16, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [55c72a253b](https://linux-hardware.org/?probe=55c72a253b) | Apr 16, 2022 |
| Acer          | Aspire C24-865              | All in one  | [961f1373a2](https://linux-hardware.org/?probe=961f1373a2) | Apr 16, 2022 |
| Gigabyte      | G1.Sniper A88X-CF           | Desktop     | [5971999c12](https://linux-hardware.org/?probe=5971999c12) | Apr 16, 2022 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [c8146beb84](https://linux-hardware.org/?probe=c8146beb84) | Apr 16, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [b097841482](https://linux-hardware.org/?probe=b097841482) | Apr 16, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [ad5a24dbb3](https://linux-hardware.org/?probe=ad5a24dbb3) | Apr 15, 2022 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [13324a7aea](https://linux-hardware.org/?probe=13324a7aea) | Apr 15, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [3e7ec0a1bb](https://linux-hardware.org/?probe=3e7ec0a1bb) | Apr 15, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [a01b211bb4](https://linux-hardware.org/?probe=a01b211bb4) | Apr 15, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [83edb7e224](https://linux-hardware.org/?probe=83edb7e224) | Apr 15, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [c58a4b9726](https://linux-hardware.org/?probe=c58a4b9726) | Apr 15, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [cc6e57929e](https://linux-hardware.org/?probe=cc6e57929e) | Apr 15, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [f5aba83efe](https://linux-hardware.org/?probe=f5aba83efe) | Apr 15, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [4cf37abd8d](https://linux-hardware.org/?probe=4cf37abd8d) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [c9c0498d72](https://linux-hardware.org/?probe=c9c0498d72) | Apr 15, 2022 |
| Unknown       | Unknown                     | Desktop     | [0735862439](https://linux-hardware.org/?probe=0735862439) | Apr 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [a9e2d5e0ef](https://linux-hardware.org/?probe=a9e2d5e0ef) | Apr 15, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [8b4c83d150](https://linux-hardware.org/?probe=8b4c83d150) | Apr 15, 2022 |
| MSI           | X470 GAMING PLUS            | Desktop     | [72af1b2afe](https://linux-hardware.org/?probe=72af1b2afe) | Apr 15, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [0b5246a205](https://linux-hardware.org/?probe=0b5246a205) | Apr 15, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [90559719b1](https://linux-hardware.org/?probe=90559719b1) | Apr 15, 2022 |
| HP            | Compaq Mini CQ10-100        | Notebook    | [89c92e2cf7](https://linux-hardware.org/?probe=89c92e2cf7) | Apr 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [2aac95b872](https://linux-hardware.org/?probe=2aac95b872) | Apr 15, 2022 |
| HP            | Compaq 8710w                | Notebook    | [cd5964d073](https://linux-hardware.org/?probe=cd5964d073) | Apr 14, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [1e26bb146f](https://linux-hardware.org/?probe=1e26bb146f) | Apr 14, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [3a0df7b88f](https://linux-hardware.org/?probe=3a0df7b88f) | Apr 14, 2022 |
| Dell          | 0YR541 A01                  | Desktop     | [f206c3667e](https://linux-hardware.org/?probe=f206c3667e) | Apr 14, 2022 |
| MSI           | Z370-A PRO                  | Desktop     | [d23bd1d06f](https://linux-hardware.org/?probe=d23bd1d06f) | Apr 14, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [46b7178535](https://linux-hardware.org/?probe=46b7178535) | Apr 14, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [3a04e2b5f2](https://linux-hardware.org/?probe=3a04e2b5f2) | Apr 14, 2022 |
| Gigabyte      | Z270P-D3-CF                 | Desktop     | [155e5c0ef5](https://linux-hardware.org/?probe=155e5c0ef5) | Apr 14, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [5f4832051e](https://linux-hardware.org/?probe=5f4832051e) | Apr 14, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [14eacf8520](https://linux-hardware.org/?probe=14eacf8520) | Apr 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [a4da99355b](https://linux-hardware.org/?probe=a4da99355b) | Apr 14, 2022 |
| HP            | Pavilion m6                 | Notebook    | [2886b9d0c1](https://linux-hardware.org/?probe=2886b9d0c1) | Apr 13, 2022 |
| Dell          | 0C2XKD A00                  | Desktop     | [4ece5fe0b7](https://linux-hardware.org/?probe=4ece5fe0b7) | Apr 13, 2022 |
| Acer          | Extensa 5620                | Notebook    | [b19ed102e0](https://linux-hardware.org/?probe=b19ed102e0) | Apr 13, 2022 |
| Gigabyte      | GA-A55M-S2HP                | Desktop     | [68c70673ef](https://linux-hardware.org/?probe=68c70673ef) | Apr 13, 2022 |
| HPE           | ProLiant MicroServer Gen... | Server      | [3c0b8415b8](https://linux-hardware.org/?probe=3c0b8415b8) | Apr 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [26a879283d](https://linux-hardware.org/?probe=26a879283d) | Apr 13, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [fcc2e4ef69](https://linux-hardware.org/?probe=fcc2e4ef69) | Apr 13, 2022 |
| MSI           | B360M PRO-VDH               | Desktop     | [33af7f8008](https://linux-hardware.org/?probe=33af7f8008) | Apr 13, 2022 |
| ONDA          | OBOOK 20 PLUS               | Notebook    | [f4f58931b7](https://linux-hardware.org/?probe=f4f58931b7) | Apr 13, 2022 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [f420769b88](https://linux-hardware.org/?probe=f420769b88) | Apr 13, 2022 |
| Lenovo        | ThinkPad E480 20KN001VRT    | Notebook    | [43b93d84fd](https://linux-hardware.org/?probe=43b93d84fd) | Apr 13, 2022 |
| Intel         | X79 V1.3                    | Desktop     | [7f3431a44d](https://linux-hardware.org/?probe=7f3431a44d) | Apr 13, 2022 |
| MSI           | C847IS-P33                  | Desktop     | [1d421862e1](https://linux-hardware.org/?probe=1d421862e1) | Apr 13, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [e517f230fa](https://linux-hardware.org/?probe=e517f230fa) | Apr 13, 2022 |
| HP            | Notebook                    | Notebook    | [e15febc7e4](https://linux-hardware.org/?probe=e15febc7e4) | Apr 13, 2022 |
| Medion        | BTDD-EAIO                   | All in one  | [8de03f374b](https://linux-hardware.org/?probe=8de03f374b) | Apr 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [ce4447422d](https://linux-hardware.org/?probe=ce4447422d) | Apr 13, 2022 |
| Haier         | S424                        | Notebook    | [c0b23cd835](https://linux-hardware.org/?probe=c0b23cd835) | Apr 13, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [2b96c77aae](https://linux-hardware.org/?probe=2b96c77aae) | Apr 12, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [9d1d134940](https://linux-hardware.org/?probe=9d1d134940) | Apr 12, 2022 |
| ASUSTek       | N56VJ                       | Notebook    | [02581c1388](https://linux-hardware.org/?probe=02581c1388) | Apr 12, 2022 |
| Gigabyte      | U2152                       | Notebook    | [f668079691](https://linux-hardware.org/?probe=f668079691) | Apr 12, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [deda69fa6d](https://linux-hardware.org/?probe=deda69fa6d) | Apr 12, 2022 |
| ASUSTek       | P5K Premium                 | Desktop     | [93ea12ef83](https://linux-hardware.org/?probe=93ea12ef83) | Apr 12, 2022 |
| Lenovo        | M5400 20281                 | Notebook    | [dd1a23fe3f](https://linux-hardware.org/?probe=dd1a23fe3f) | Apr 12, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [07de6c8eb6](https://linux-hardware.org/?probe=07de6c8eb6) | Apr 12, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [eae6b5ed56](https://linux-hardware.org/?probe=eae6b5ed56) | Apr 12, 2022 |
| Lenovo        | V570c HuronRiver Platfor... | Notebook    | [0858e6ff56](https://linux-hardware.org/?probe=0858e6ff56) | Apr 12, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [7ea9773813](https://linux-hardware.org/?probe=7ea9773813) | Apr 12, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [6b70f0a384](https://linux-hardware.org/?probe=6b70f0a384) | Apr 12, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [6273f8eefb](https://linux-hardware.org/?probe=6273f8eefb) | Apr 12, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [0025682d7d](https://linux-hardware.org/?probe=0025682d7d) | Apr 12, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [d751a52423](https://linux-hardware.org/?probe=d751a52423) | Apr 11, 2022 |
| eMachines     | E725                        | Notebook    | [cd03638757](https://linux-hardware.org/?probe=cd03638757) | Apr 11, 2022 |
| Acer          | Aspire 5734Z                | Notebook    | [982dccf136](https://linux-hardware.org/?probe=982dccf136) | Apr 11, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [3b949d56a9](https://linux-hardware.org/?probe=3b949d56a9) | Apr 11, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [259f72f743](https://linux-hardware.org/?probe=259f72f743) | Apr 11, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [c2de5fcfd5](https://linux-hardware.org/?probe=c2de5fcfd5) | Apr 11, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [5cc893af9c](https://linux-hardware.org/?probe=5cc893af9c) | Apr 11, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [1dff7e3c31](https://linux-hardware.org/?probe=1dff7e3c31) | Apr 11, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [816c91bfcd](https://linux-hardware.org/?probe=816c91bfcd) | Apr 11, 2022 |
| Intel         | Tiger Hill                  | Desktop     | [1fbea29754](https://linux-hardware.org/?probe=1fbea29754) | Apr 11, 2022 |
| ASRock        | N68-VGS3 FX                 | Desktop     | [292cc244de](https://linux-hardware.org/?probe=292cc244de) | Apr 11, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [d43f5778b1](https://linux-hardware.org/?probe=d43f5778b1) | Apr 11, 2022 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [a52c5e98af](https://linux-hardware.org/?probe=a52c5e98af) | Apr 11, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [cb60e697d1](https://linux-hardware.org/?probe=cb60e697d1) | Apr 11, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1b2b5e921d](https://linux-hardware.org/?probe=1b2b5e921d) | Apr 11, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [95ae38af4e](https://linux-hardware.org/?probe=95ae38af4e) | Apr 11, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [eb62b9de81](https://linux-hardware.org/?probe=eb62b9de81) | Apr 11, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [ef0b36db62](https://linux-hardware.org/?probe=ef0b36db62) | Apr 11, 2022 |
| KLLISRE       | X99-B5 V1.1                 | Desktop     | [5c1d47d9c9](https://linux-hardware.org/?probe=5c1d47d9c9) | Apr 11, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [5de4abca91](https://linux-hardware.org/?probe=5de4abca91) | Apr 11, 2022 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [67018740b8](https://linux-hardware.org/?probe=67018740b8) | Apr 11, 2022 |
| Gigabyte      | B75-D3V                     | Desktop     | [ea939b5214](https://linux-hardware.org/?probe=ea939b5214) | Apr 10, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [335125845e](https://linux-hardware.org/?probe=335125845e) | Apr 10, 2022 |
| Intel         | X99                         | Desktop     | [ecea2585e1](https://linux-hardware.org/?probe=ecea2585e1) | Apr 10, 2022 |
| Dell          | Inspiron 5759               | Notebook    | [315fcfc017](https://linux-hardware.org/?probe=315fcfc017) | Apr 10, 2022 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [5abfaa2b99](https://linux-hardware.org/?probe=5abfaa2b99) | Apr 10, 2022 |
| HP            | 3048h                       | Desktop     | [c55f6bc20c](https://linux-hardware.org/?probe=c55f6bc20c) | Apr 10, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | Desktop     | [071e82f576](https://linux-hardware.org/?probe=071e82f576) | Apr 10, 2022 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [f4b5ca3229](https://linux-hardware.org/?probe=f4b5ca3229) | Apr 10, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [63aaae3d92](https://linux-hardware.org/?probe=63aaae3d92) | Apr 10, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [8737781637](https://linux-hardware.org/?probe=8737781637) | Apr 10, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [a71131cba6](https://linux-hardware.org/?probe=a71131cba6) | Apr 10, 2022 |
| Lenovo        | Legion Y540-17IRH 81UJ      | Notebook    | [d29d125641](https://linux-hardware.org/?probe=d29d125641) | Apr 10, 2022 |
| ASUSTek       | F5RL                        | Notebook    | [c4f44cce57](https://linux-hardware.org/?probe=c4f44cce57) | Apr 10, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [9014595f74](https://linux-hardware.org/?probe=9014595f74) | Apr 10, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [dd55fda409](https://linux-hardware.org/?probe=dd55fda409) | Apr 10, 2022 |
| ASUSTek       | K50IN                       | Notebook    | [97e92ead43](https://linux-hardware.org/?probe=97e92ead43) | Apr 10, 2022 |
| Sony          | VGN-TT31MR_N                | Notebook    | [d8eb5d22da](https://linux-hardware.org/?probe=d8eb5d22da) | Apr 10, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [ad84faeb49](https://linux-hardware.org/?probe=ad84faeb49) | Apr 09, 2022 |
| Irbis         | NB211                       | Notebook    | [75ad10cc68](https://linux-hardware.org/?probe=75ad10cc68) | Apr 09, 2022 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [43c15ac73b](https://linux-hardware.org/?probe=43c15ac73b) | Apr 09, 2022 |
| Acer          | Aspire E5-532               | Notebook    | [d2135748fe](https://linux-hardware.org/?probe=d2135748fe) | Apr 09, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [d19ae9b1d5](https://linux-hardware.org/?probe=d19ae9b1d5) | Apr 09, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [01bc8ef97c](https://linux-hardware.org/?probe=01bc8ef97c) | Apr 09, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [0326b913dd](https://linux-hardware.org/?probe=0326b913dd) | Apr 09, 2022 |
| ASRock        | P43DE3                      | Desktop     | [21eed63d16](https://linux-hardware.org/?probe=21eed63d16) | Apr 09, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [c46bf4b738](https://linux-hardware.org/?probe=c46bf4b738) | Apr 09, 2022 |
| Intel         | DP35DP AAD81073-206         | Desktop     | [b257e3cf76](https://linux-hardware.org/?probe=b257e3cf76) | Apr 09, 2022 |
| Acer          | Nitro AN515-56              | Notebook    | [3c444ad400](https://linux-hardware.org/?probe=3c444ad400) | Apr 09, 2022 |
| Gigabyte      | Z87P-D3                     | Desktop     | [9ea9a7e8ef](https://linux-hardware.org/?probe=9ea9a7e8ef) | Apr 09, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [a096b22b37](https://linux-hardware.org/?probe=a096b22b37) | Apr 09, 2022 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [457adc950f](https://linux-hardware.org/?probe=457adc950f) | Apr 09, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [f0045560de](https://linux-hardware.org/?probe=f0045560de) | Apr 09, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ea4da8fb23](https://linux-hardware.org/?probe=ea4da8fb23) | Apr 09, 2022 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [bb210a31b5](https://linux-hardware.org/?probe=bb210a31b5) | Apr 09, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [09946e9edf](https://linux-hardware.org/?probe=09946e9edf) | Apr 09, 2022 |
| DNS           | Unknown                     | Notebook    | [ce4a6e5c43](https://linux-hardware.org/?probe=ce4a6e5c43) | Apr 09, 2022 |
| Gigabyte      | GA-MA785GM-US2H             | Desktop     | [387e498dfc](https://linux-hardware.org/?probe=387e498dfc) | Apr 09, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [f5ee5fd187](https://linux-hardware.org/?probe=f5ee5fd187) | Apr 09, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [b40816245c](https://linux-hardware.org/?probe=b40816245c) | Apr 09, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [3d06c8719d](https://linux-hardware.org/?probe=3d06c8719d) | Apr 08, 2022 |
| Acer          | Aspire C24-320              | All in one  | [54cb792966](https://linux-hardware.org/?probe=54cb792966) | Apr 08, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [f2af37f520](https://linux-hardware.org/?probe=f2af37f520) | Apr 08, 2022 |
| ASRock        | H61M-S                      | Desktop     | [7f0b28837f](https://linux-hardware.org/?probe=7f0b28837f) | Apr 08, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [be7a7cb25f](https://linux-hardware.org/?probe=be7a7cb25f) | Apr 08, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [74c07daf2f](https://linux-hardware.org/?probe=74c07daf2f) | Apr 08, 2022 |
| Acer          | Aspire 1830T                | Notebook    | [b5348b2c70](https://linux-hardware.org/?probe=b5348b2c70) | Apr 08, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [ac9ab2383f](https://linux-hardware.org/?probe=ac9ab2383f) | Apr 08, 2022 |
| Packard Be... | EasyNote LM85               | Notebook    | [56cf496cf2](https://linux-hardware.org/?probe=56cf496cf2) | Apr 08, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [5da93676f7](https://linux-hardware.org/?probe=5da93676f7) | Apr 08, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [8ab0db4e45](https://linux-hardware.org/?probe=8ab0db4e45) | Apr 08, 2022 |
| Acer          | Batman A01                  | Desktop     | [a102f85d9d](https://linux-hardware.org/?probe=a102f85d9d) | Apr 08, 2022 |
| Packard Be... | EasyNote LM85               | Notebook    | [32140f5b90](https://linux-hardware.org/?probe=32140f5b90) | Apr 08, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603HE... | Notebook    | [bce81d50a8](https://linux-hardware.org/?probe=bce81d50a8) | Apr 08, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [8986d7abf1](https://linux-hardware.org/?probe=8986d7abf1) | Apr 08, 2022 |
| eMachines     | eM355                       | Notebook    | [76ddd795cc](https://linux-hardware.org/?probe=76ddd795cc) | Apr 08, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [304330a609](https://linux-hardware.org/?probe=304330a609) | Apr 08, 2022 |
| Intel         | X79 (INTEL Xeon E5/Corei... | Desktop     | [263621f796](https://linux-hardware.org/?probe=263621f796) | Apr 08, 2022 |
| Acer          | AOD255                      | Notebook    | [f1a5682c95](https://linux-hardware.org/?probe=f1a5682c95) | Apr 08, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [7e98fd7db9](https://linux-hardware.org/?probe=7e98fd7db9) | Apr 08, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [0cabea6484](https://linux-hardware.org/?probe=0cabea6484) | Apr 08, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [256bfd0a56](https://linux-hardware.org/?probe=256bfd0a56) | Apr 08, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | Notebook    | [043d63cc06](https://linux-hardware.org/?probe=043d63cc06) | Apr 08, 2022 |
| MSI           | Z270 TOMAHAWK               | Desktop     | [4063e06462](https://linux-hardware.org/?probe=4063e06462) | Apr 07, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [bc8934f133](https://linux-hardware.org/?probe=bc8934f133) | Apr 07, 2022 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [f1f94d1273](https://linux-hardware.org/?probe=f1f94d1273) | Apr 07, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [7b41cf9275](https://linux-hardware.org/?probe=7b41cf9275) | Apr 07, 2022 |
| Digma         | EVE 10 C301 ES1050EW        | Notebook    | [7db1a321e8](https://linux-hardware.org/?probe=7db1a321e8) | Apr 07, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [1c1830c301](https://linux-hardware.org/?probe=1c1830c301) | Apr 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [2dce0bfd4f](https://linux-hardware.org/?probe=2dce0bfd4f) | Apr 07, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [0b8ce7d654](https://linux-hardware.org/?probe=0b8ce7d654) | Apr 07, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f8b24828c3](https://linux-hardware.org/?probe=f8b24828c3) | Apr 07, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [0579a9b7d8](https://linux-hardware.org/?probe=0579a9b7d8) | Apr 07, 2022 |
| ASUSTek       | 1015B                       | Notebook    | [e271b0d0f3](https://linux-hardware.org/?probe=e271b0d0f3) | Apr 07, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [5d846383e8](https://linux-hardware.org/?probe=5d846383e8) | Apr 07, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [9e7f22efa7](https://linux-hardware.org/?probe=9e7f22efa7) | Apr 07, 2022 |
| Maibenben     | DaMai E series              | Notebook    | [3a37c71f1e](https://linux-hardware.org/?probe=3a37c71f1e) | Apr 07, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [49c1cb4d2b](https://linux-hardware.org/?probe=49c1cb4d2b) | Apr 07, 2022 |
| HP            | 550                         | Notebook    | [5b302acef8](https://linux-hardware.org/?probe=5b302acef8) | Apr 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [6e12ed717c](https://linux-hardware.org/?probe=6e12ed717c) | Apr 07, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [c049a4a3a5](https://linux-hardware.org/?probe=c049a4a3a5) | Apr 07, 2022 |
| HP            | ProBook 4520s               | Notebook    | [938de7402b](https://linux-hardware.org/?probe=938de7402b) | Apr 07, 2022 |
| Samsung       | N150/N210/N220              | Notebook    | [d431ef7f66](https://linux-hardware.org/?probe=d431ef7f66) | Apr 07, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [1097c7afa9](https://linux-hardware.org/?probe=1097c7afa9) | Apr 07, 2022 |
| Samsung       | R519/R719                   | Notebook    | [4bc0e89e19](https://linux-hardware.org/?probe=4bc0e89e19) | Apr 07, 2022 |
| Acer          | TravelMate 5620             | Notebook    | [fe6508476e](https://linux-hardware.org/?probe=fe6508476e) | Apr 07, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [b30a3c00f9](https://linux-hardware.org/?probe=b30a3c00f9) | Apr 07, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [1b6a57154d](https://linux-hardware.org/?probe=1b6a57154d) | Apr 07, 2022 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [632f031e00](https://linux-hardware.org/?probe=632f031e00) | Apr 07, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [92e741954d](https://linux-hardware.org/?probe=92e741954d) | Apr 07, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [db01c6669b](https://linux-hardware.org/?probe=db01c6669b) | Apr 07, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [28320f2e89](https://linux-hardware.org/?probe=28320f2e89) | Apr 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b8b32cb958](https://linux-hardware.org/?probe=b8b32cb958) | Apr 07, 2022 |
| Acer          | AOD255                      | Notebook    | [20bbc537d6](https://linux-hardware.org/?probe=20bbc537d6) | Apr 07, 2022 |
| Acer          | Aspire 1830T                | Notebook    | [5517b27bee](https://linux-hardware.org/?probe=5517b27bee) | Apr 07, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [bcbdedc21a](https://linux-hardware.org/?probe=bcbdedc21a) | Apr 07, 2022 |
| Toshiba       | QOSMIO F60                  | Notebook    | [225135dedb](https://linux-hardware.org/?probe=225135dedb) | Apr 07, 2022 |
| ASRock        | A520M Pro4                  | Desktop     | [1eecc7b812](https://linux-hardware.org/?probe=1eecc7b812) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b925472f54](https://linux-hardware.org/?probe=b925472f54) | Apr 07, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [f488ae3a24](https://linux-hardware.org/?probe=f488ae3a24) | Apr 07, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [aa5806bcd5](https://linux-hardware.org/?probe=aa5806bcd5) | Apr 07, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [3cb9a7fe16](https://linux-hardware.org/?probe=3cb9a7fe16) | Apr 07, 2022 |
| Lenovo        | V570c HuronRiver Platfor... | Notebook    | [b39c0569bb](https://linux-hardware.org/?probe=b39c0569bb) | Apr 07, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [9f6e1da5bd](https://linux-hardware.org/?probe=9f6e1da5bd) | Apr 07, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [ba5fa5ac1d](https://linux-hardware.org/?probe=ba5fa5ac1d) | Apr 07, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [91c32e3a92](https://linux-hardware.org/?probe=91c32e3a92) | Apr 07, 2022 |
| ASUSTek       | P5BV-C/4L                   | Desktop     | [b1eba1811a](https://linux-hardware.org/?probe=b1eba1811a) | Apr 07, 2022 |
| ASUSTek       | P5G41C-M                    | Desktop     | [438a8f1001](https://linux-hardware.org/?probe=438a8f1001) | Apr 07, 2022 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [d61b85b58c](https://linux-hardware.org/?probe=d61b85b58c) | Apr 07, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [8cf7fd2319](https://linux-hardware.org/?probe=8cf7fd2319) | Apr 07, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [c5b2bc51dc](https://linux-hardware.org/?probe=c5b2bc51dc) | Apr 06, 2022 |
| Dell          | Latitude 7480               | Notebook    | [b088dbb113](https://linux-hardware.org/?probe=b088dbb113) | Apr 06, 2022 |
| MSI           | B360-A PRO                  | Desktop     | [9db9a23b5d](https://linux-hardware.org/?probe=9db9a23b5d) | Apr 06, 2022 |
| MSI           | Z87I GAMING AC              | Desktop     | [f9596aa625](https://linux-hardware.org/?probe=f9596aa625) | Apr 06, 2022 |
| ASUSTek       | X541NC                      | Notebook    | [a7af7e79fd](https://linux-hardware.org/?probe=a7af7e79fd) | Apr 06, 2022 |
| MSI           | MS-N0E1 Ver                 | Notebook    | [95f1378c78](https://linux-hardware.org/?probe=95f1378c78) | Apr 06, 2022 |
| MSI           | G41M-P28                    | Desktop     | [b19249859b](https://linux-hardware.org/?probe=b19249859b) | Apr 06, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f26f24743f](https://linux-hardware.org/?probe=f26f24743f) | Apr 06, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [c14aa9ce1a](https://linux-hardware.org/?probe=c14aa9ce1a) | Apr 06, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [91224772eb](https://linux-hardware.org/?probe=91224772eb) | Apr 06, 2022 |
| Unknown       | H510I                       | Desktop     | [ff0188e03f](https://linux-hardware.org/?probe=ff0188e03f) | Apr 06, 2022 |
| Samsung       | R19/R20/R21                 | Notebook    | [77b19cd7c5](https://linux-hardware.org/?probe=77b19cd7c5) | Apr 06, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [f25aa95e78](https://linux-hardware.org/?probe=f25aa95e78) | Apr 06, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [6e2067ac48](https://linux-hardware.org/?probe=6e2067ac48) | Apr 06, 2022 |
| ASUSTek       | K8N-VM                      | Desktop     | [ec2a4f7170](https://linux-hardware.org/?probe=ec2a4f7170) | Apr 06, 2022 |
| SYWZ          | S200 Series                 | Desktop     | [8c4c52cd9b](https://linux-hardware.org/?probe=8c4c52cd9b) | Apr 06, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [39ab6f56fb](https://linux-hardware.org/?probe=39ab6f56fb) | Apr 06, 2022 |
| ASUSTek       | F5SL                        | Notebook    | [76272ce111](https://linux-hardware.org/?probe=76272ce111) | Apr 06, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [41f654dc20](https://linux-hardware.org/?probe=41f654dc20) | Apr 06, 2022 |
| Dell          | Vostro A860                 | Notebook    | [72c05fd9ee](https://linux-hardware.org/?probe=72c05fd9ee) | Apr 06, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [e5cdfad4e6](https://linux-hardware.org/?probe=e5cdfad4e6) | Apr 06, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [0cca11beab](https://linux-hardware.org/?probe=0cca11beab) | Apr 05, 2022 |
| Unknown       | RS690-SB600                 | Desktop     | [19ae42107e](https://linux-hardware.org/?probe=19ae42107e) | Apr 05, 2022 |
| ASUSTek       | 1011CX                      | Notebook    | [39035efe16](https://linux-hardware.org/?probe=39035efe16) | Apr 05, 2022 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [200d7fafb9](https://linux-hardware.org/?probe=200d7fafb9) | Apr 05, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [55622262b1](https://linux-hardware.org/?probe=55622262b1) | Apr 05, 2022 |
| Dell          | Latitude 5590               | Notebook    | [6e22c70e48](https://linux-hardware.org/?probe=6e22c70e48) | Apr 05, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [1a090182c2](https://linux-hardware.org/?probe=1a090182c2) | Apr 05, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [68512f2b49](https://linux-hardware.org/?probe=68512f2b49) | Apr 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [011cc4e8f8](https://linux-hardware.org/?probe=011cc4e8f8) | Apr 05, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [b642303f8e](https://linux-hardware.org/?probe=b642303f8e) | Apr 05, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [a3d0521e54](https://linux-hardware.org/?probe=a3d0521e54) | Apr 05, 2022 |
| MSI           | G41M-P33 Combo              | Desktop     | [2290edabe7](https://linux-hardware.org/?probe=2290edabe7) | Apr 05, 2022 |
| ASUSTek       | B560M-A PRIME               | Desktop     | [1aff04b3de](https://linux-hardware.org/?probe=1aff04b3de) | Apr 05, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [6d2f9e0fce](https://linux-hardware.org/?probe=6d2f9e0fce) | Apr 05, 2022 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [6c25d1250d](https://linux-hardware.org/?probe=6c25d1250d) | Apr 05, 2022 |
| ASUSTek       | K8N-VM                      | Desktop     | [d914bc84e9](https://linux-hardware.org/?probe=d914bc84e9) | Apr 05, 2022 |
| HP            | ENVY 17                     | Notebook    | [060904cd87](https://linux-hardware.org/?probe=060904cd87) | Apr 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [d57ec60736](https://linux-hardware.org/?probe=d57ec60736) | Apr 05, 2022 |
| Acer          | Aspire Z3730                | All in one  | [6fdf5d94d7](https://linux-hardware.org/?probe=6fdf5d94d7) | Apr 05, 2022 |
| ONDA          | OBOOK 20 PLUS               | Notebook    | [1b39269806](https://linux-hardware.org/?probe=1b39269806) | Apr 05, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [7842a96018](https://linux-hardware.org/?probe=7842a96018) | Apr 05, 2022 |
| ONDA          | OBOOK 20 PLUS               | Notebook    | [279c2a3de8](https://linux-hardware.org/?probe=279c2a3de8) | Apr 05, 2022 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [bb16122030](https://linux-hardware.org/?probe=bb16122030) | Apr 05, 2022 |
| Acer          | Aspire 5734Z                | Notebook    | [12ff3844f5](https://linux-hardware.org/?probe=12ff3844f5) | Apr 05, 2022 |
| Gigabyte      | F2A68HM-HD2                 | Desktop     | [cb0794850f](https://linux-hardware.org/?probe=cb0794850f) | Apr 05, 2022 |
| ASUSTek       | M3A78-EH                    | Desktop     | [4298b6c9dc](https://linux-hardware.org/?probe=4298b6c9dc) | Apr 05, 2022 |
| HP            | Pavilion 15                 | Notebook    | [470ca0bc41](https://linux-hardware.org/?probe=470ca0bc41) | Apr 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [8f491b9fc2](https://linux-hardware.org/?probe=8f491b9fc2) | Apr 05, 2022 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [75da1802c3](https://linux-hardware.org/?probe=75da1802c3) | Apr 05, 2022 |
| ASUSTek       | P5Q DELUXE                  | Desktop     | [1c37d5b9ed](https://linux-hardware.org/?probe=1c37d5b9ed) | Apr 04, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [c474b8d1a2](https://linux-hardware.org/?probe=c474b8d1a2) | Apr 04, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [bc5ffea6a3](https://linux-hardware.org/?probe=bc5ffea6a3) | Apr 04, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [1167744ae0](https://linux-hardware.org/?probe=1167744ae0) | Apr 04, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [0134ef08d6](https://linux-hardware.org/?probe=0134ef08d6) | Apr 04, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [e49282700d](https://linux-hardware.org/?probe=e49282700d) | Apr 04, 2022 |
| Gigabyte      | H67A-UD3H-B3                | Desktop     | [5ccef6f1fe](https://linux-hardware.org/?probe=5ccef6f1fe) | Apr 04, 2022 |
| Dell          | Precision M6800             | Notebook    | [d3510b5479](https://linux-hardware.org/?probe=d3510b5479) | Apr 04, 2022 |
| ASUSTek       | P5B                         | Desktop     | [fd9454ab7a](https://linux-hardware.org/?probe=fd9454ab7a) | Apr 04, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [864d69baab](https://linux-hardware.org/?probe=864d69baab) | Apr 04, 2022 |
| Acer          | Aspire A317-32              | Notebook    | [8980c8b316](https://linux-hardware.org/?probe=8980c8b316) | Apr 04, 2022 |
| MSI           | G41M-P28                    | Desktop     | [afb7898d63](https://linux-hardware.org/?probe=afb7898d63) | Apr 04, 2022 |
| Unknown       | Unknown                     | Desktop     | [214ae5185b](https://linux-hardware.org/?probe=214ae5185b) | Apr 04, 2022 |
| HP            | ProBook 4535s               | Notebook    | [89adb58230](https://linux-hardware.org/?probe=89adb58230) | Apr 04, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [eae759532b](https://linux-hardware.org/?probe=eae759532b) | Apr 04, 2022 |
| MSI           | Sword 15 A11UE              | Notebook    | [dfc5aa7490](https://linux-hardware.org/?probe=dfc5aa7490) | Apr 04, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [2904ae2343](https://linux-hardware.org/?probe=2904ae2343) | Apr 03, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [4368fb5c23](https://linux-hardware.org/?probe=4368fb5c23) | Apr 03, 2022 |
| Acer          | Aspire 7110                 | Notebook    | [eb141ad92d](https://linux-hardware.org/?probe=eb141ad92d) | Apr 03, 2022 |
| Acer          | Aspire 5739G                | Notebook    | [60bc55e587](https://linux-hardware.org/?probe=60bc55e587) | Apr 03, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [2de94117ab](https://linux-hardware.org/?probe=2de94117ab) | Apr 03, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [68793d8d5a](https://linux-hardware.org/?probe=68793d8d5a) | Apr 03, 2022 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [d2abd78cfc](https://linux-hardware.org/?probe=d2abd78cfc) | Apr 03, 2022 |
| Gigabyte      | P41-ES3G                    | Desktop     | [3db559b0cb](https://linux-hardware.org/?probe=3db559b0cb) | Apr 03, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [c6cb4c0d83](https://linux-hardware.org/?probe=c6cb4c0d83) | Apr 03, 2022 |
| Gigabyte      | P41-ES3G                    | Desktop     | [ba5297b664](https://linux-hardware.org/?probe=ba5297b664) | Apr 03, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [45f577da9e](https://linux-hardware.org/?probe=45f577da9e) | Apr 03, 2022 |
| MSI           | B360M PRO-VDH               | Desktop     | [b2da2d7cc2](https://linux-hardware.org/?probe=b2da2d7cc2) | Apr 03, 2022 |
| Jumper        | EZpad                       | Notebook    | [4ebe3328db](https://linux-hardware.org/?probe=4ebe3328db) | Apr 03, 2022 |
| ASUSTek       | B75M-A                      | Desktop     | [06415c4f91](https://linux-hardware.org/?probe=06415c4f91) | Apr 02, 2022 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [1ccfd166ec](https://linux-hardware.org/?probe=1ccfd166ec) | Apr 02, 2022 |
| Digma         | EVE 10 C301 ES1050EW        | Notebook    | [21b48c0c97](https://linux-hardware.org/?probe=21b48c0c97) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [49aec76409](https://linux-hardware.org/?probe=49aec76409) | Apr 02, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [2b9c6b4b05](https://linux-hardware.org/?probe=2b9c6b4b05) | Apr 02, 2022 |
| Intel         | D2500CC AAG81477-401        | Desktop     | [5beb419727](https://linux-hardware.org/?probe=5beb419727) | Apr 02, 2022 |
| eMachines     | E625                        | Notebook    | [d2e61292e0](https://linux-hardware.org/?probe=d2e61292e0) | Apr 02, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [c7cc0b8ae7](https://linux-hardware.org/?probe=c7cc0b8ae7) | Apr 02, 2022 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [9bc98bf38e](https://linux-hardware.org/?probe=9bc98bf38e) | Apr 02, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [2054f135d4](https://linux-hardware.org/?probe=2054f135d4) | Apr 02, 2022 |
| Sony          | VGN-P688E                   | Notebook    | [bd0b916fe7](https://linux-hardware.org/?probe=bd0b916fe7) | Apr 02, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [044dde3226](https://linux-hardware.org/?probe=044dde3226) | Apr 02, 2022 |
| MSI           | P55M-SD40                   | Desktop     | [3232f9fb77](https://linux-hardware.org/?probe=3232f9fb77) | Apr 02, 2022 |
| eMachines     | Unknown                     | Notebook    | [177156159a](https://linux-hardware.org/?probe=177156159a) | Apr 02, 2022 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f5a5374d7f](https://linux-hardware.org/?probe=f5a5374d7f) | Apr 02, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [df93928fb7](https://linux-hardware.org/?probe=df93928fb7) | Apr 02, 2022 |
| ASUSTek       | K40IJ                       | Notebook    | [f05cdebfd9](https://linux-hardware.org/?probe=f05cdebfd9) | Apr 02, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [8ed3394de0](https://linux-hardware.org/?probe=8ed3394de0) | Apr 02, 2022 |
| ASUSTek       | P7P55D                      | Desktop     | [626d7d9cf9](https://linux-hardware.org/?probe=626d7d9cf9) | Apr 02, 2022 |
| ECS           | G31T-M7                     | Desktop     | [c6f5fbd8ff](https://linux-hardware.org/?probe=c6f5fbd8ff) | Apr 02, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [cd49e5d099](https://linux-hardware.org/?probe=cd49e5d099) | Apr 02, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [609849a9e7](https://linux-hardware.org/?probe=609849a9e7) | Apr 02, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [80007d3994](https://linux-hardware.org/?probe=80007d3994) | Apr 02, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [a6f8e740aa](https://linux-hardware.org/?probe=a6f8e740aa) | Apr 02, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [ae5976d302](https://linux-hardware.org/?probe=ae5976d302) | Apr 01, 2022 |
| Dell          | Inspiron 1521               | Notebook    | [ddd74ed487](https://linux-hardware.org/?probe=ddd74ed487) | Apr 01, 2022 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [0b410c35cf](https://linux-hardware.org/?probe=0b410c35cf) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [dd28d6de9b](https://linux-hardware.org/?probe=dd28d6de9b) | Apr 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [fe5fe3040c](https://linux-hardware.org/?probe=fe5fe3040c) | Apr 01, 2022 |
| Gigabyte      | GA-A55M-S2HP                | Desktop     | [6655b05056](https://linux-hardware.org/?probe=6655b05056) | Apr 01, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [ce851fba8f](https://linux-hardware.org/?probe=ce851fba8f) | Apr 01, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [198fed544f](https://linux-hardware.org/?probe=198fed544f) | Apr 01, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [86b685b176](https://linux-hardware.org/?probe=86b685b176) | Apr 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [bd224d9eb3](https://linux-hardware.org/?probe=bd224d9eb3) | Apr 01, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [ee8cf37d90](https://linux-hardware.org/?probe=ee8cf37d90) | Apr 01, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [0eb7c0d9b2](https://linux-hardware.org/?probe=0eb7c0d9b2) | Apr 01, 2022 |
| ASUSTek       | K42F                        | Notebook    | [29766a27d6](https://linux-hardware.org/?probe=29766a27d6) | Apr 01, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [6284bd7200](https://linux-hardware.org/?probe=6284bd7200) | Apr 01, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [7c61bf8ce7](https://linux-hardware.org/?probe=7c61bf8ce7) | Apr 01, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [7cba7f428a](https://linux-hardware.org/?probe=7cba7f428a) | Apr 01, 2022 |
| ASUSTek       | P5K                         | Desktop     | [544e656548](https://linux-hardware.org/?probe=544e656548) | Apr 01, 2022 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [0190cbbd27](https://linux-hardware.org/?probe=0190cbbd27) | Apr 01, 2022 |
| ASUSTek       | X55VD                       | Notebook    | [36e2e9943a](https://linux-hardware.org/?probe=36e2e9943a) | Mar 31, 2022 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [667310c4b8](https://linux-hardware.org/?probe=667310c4b8) | Mar 31, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [4153c10d0b](https://linux-hardware.org/?probe=4153c10d0b) | Mar 31, 2022 |
| MSI           | P67A-C45                    | Desktop     | [5ec0cd08a4](https://linux-hardware.org/?probe=5ec0cd08a4) | Mar 31, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [18f5f3d92a](https://linux-hardware.org/?probe=18f5f3d92a) | Mar 31, 2022 |
| Intel         | ChiefRiver                  | Notebook    | [619464014d](https://linux-hardware.org/?probe=619464014d) | Mar 31, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [e4059f2c1d](https://linux-hardware.org/?probe=e4059f2c1d) | Mar 31, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [fe17eb0fec](https://linux-hardware.org/?probe=fe17eb0fec) | Mar 31, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [96487ebeb0](https://linux-hardware.org/?probe=96487ebeb0) | Mar 31, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [efae9a6cb7](https://linux-hardware.org/?probe=efae9a6cb7) | Mar 31, 2022 |
| ASRock        | Z170 Pro4/D3                | Desktop     | [275edd1533](https://linux-hardware.org/?probe=275edd1533) | Mar 31, 2022 |
| MSI           | GT72 2QE                    | Notebook    | [ff49dc0593](https://linux-hardware.org/?probe=ff49dc0593) | Mar 31, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [fd66ebbeee](https://linux-hardware.org/?probe=fd66ebbeee) | Mar 31, 2022 |
| Dell          | Latitude E6430              | Notebook    | [a045dc014b](https://linux-hardware.org/?probe=a045dc014b) | Mar 31, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [8781d04da2](https://linux-hardware.org/?probe=8781d04da2) | Mar 31, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [1f74cc9211](https://linux-hardware.org/?probe=1f74cc9211) | Mar 31, 2022 |
| Lenovo        | E43                         | Notebook    | [356aa25045](https://linux-hardware.org/?probe=356aa25045) | Mar 30, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [e9508b7cce](https://linux-hardware.org/?probe=e9508b7cce) | Mar 30, 2022 |
| HP            | Pavilion dv6                | Notebook    | [b456c7a1a3](https://linux-hardware.org/?probe=b456c7a1a3) | Mar 30, 2022 |
| ASRock        | H61MV-ITX                   | Desktop     | [da935498ad](https://linux-hardware.org/?probe=da935498ad) | Mar 30, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [75a190fb7c](https://linux-hardware.org/?probe=75a190fb7c) | Mar 30, 2022 |
| ASUSTek       | M2N                         | Desktop     | [1d11c3c0f9](https://linux-hardware.org/?probe=1d11c3c0f9) | Mar 30, 2022 |
| MSI           | MS-7346                     | Desktop     | [207eda5f34](https://linux-hardware.org/?probe=207eda5f34) | Mar 30, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [d783ed375d](https://linux-hardware.org/?probe=d783ed375d) | Mar 30, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [03f276b46f](https://linux-hardware.org/?probe=03f276b46f) | Mar 30, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [4374d376e6](https://linux-hardware.org/?probe=4374d376e6) | Mar 30, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [0fa8cd8737](https://linux-hardware.org/?probe=0fa8cd8737) | Mar 30, 2022 |
| Fujitsu Si... | AMILO Pi 2550               | Notebook    | [2ab7c6e8e9](https://linux-hardware.org/?probe=2ab7c6e8e9) | Mar 30, 2022 |
| Toshiba       | Satellite Pro L300          | Notebook    | [ee5a484f5e](https://linux-hardware.org/?probe=ee5a484f5e) | Mar 30, 2022 |
| Samsung       | R519/R719                   | Notebook    | [2d46b53c07](https://linux-hardware.org/?probe=2d46b53c07) | Mar 29, 2022 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [a220b7b7cc](https://linux-hardware.org/?probe=a220b7b7cc) | Mar 29, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [c0d1cdbeaf](https://linux-hardware.org/?probe=c0d1cdbeaf) | Mar 29, 2022 |
| ASUSTek       | Z170-K                      | Desktop     | [1b4b237c62](https://linux-hardware.org/?probe=1b4b237c62) | Mar 29, 2022 |
| ASUSTek       | X550CL                      | Notebook    | [a015b46fec](https://linux-hardware.org/?probe=a015b46fec) | Mar 29, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [c29c76ec93](https://linux-hardware.org/?probe=c29c76ec93) | Mar 29, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [8b6f847c8e](https://linux-hardware.org/?probe=8b6f847c8e) | Mar 29, 2022 |
| eMachines     | E725                        | Notebook    | [b248c29df3](https://linux-hardware.org/?probe=b248c29df3) | Mar 29, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [5c10e8ed7d](https://linux-hardware.org/?probe=5c10e8ed7d) | Mar 29, 2022 |
| ASRock        | B365M-HDV                   | Desktop     | [ce8992d4dd](https://linux-hardware.org/?probe=ce8992d4dd) | Mar 29, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [16e1a01da4](https://linux-hardware.org/?probe=16e1a01da4) | Mar 29, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [66daa065a8](https://linux-hardware.org/?probe=66daa065a8) | Mar 29, 2022 |
| ASUSTek       | P8H61-I                     | Desktop     | [2e1b862b8b](https://linux-hardware.org/?probe=2e1b862b8b) | Mar 28, 2022 |
| ECS           | H67H2-M3                    | Desktop     | [d6abbba502](https://linux-hardware.org/?probe=d6abbba502) | Mar 28, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [6d4270f045](https://linux-hardware.org/?probe=6d4270f045) | Mar 28, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [c785b6b54b](https://linux-hardware.org/?probe=c785b6b54b) | Mar 28, 2022 |
| Dell          | 500                         | Notebook    | [885884468f](https://linux-hardware.org/?probe=885884468f) | Mar 28, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2b900adf8e](https://linux-hardware.org/?probe=2b900adf8e) | Mar 28, 2022 |
| ECS           | G41T-M7                     | Desktop     | [9bd8c1ef5a](https://linux-hardware.org/?probe=9bd8c1ef5a) | Mar 28, 2022 |
| ASUSTek       | M4A88T-M                    | Desktop     | [4cfedd9c7a](https://linux-hardware.org/?probe=4cfedd9c7a) | Mar 28, 2022 |
| Lenovo        | H420                        | Desktop     | [3da1375d85](https://linux-hardware.org/?probe=3da1375d85) | Mar 28, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [45513b120d](https://linux-hardware.org/?probe=45513b120d) | Mar 28, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [915761391f](https://linux-hardware.org/?probe=915761391f) | Mar 28, 2022 |
| HP            | Compaq 615                  | Notebook    | [77439caf8f](https://linux-hardware.org/?probe=77439caf8f) | Mar 28, 2022 |
| ASUSTek       | P8H61-M PRO                 | Desktop     | [870dc37754](https://linux-hardware.org/?probe=870dc37754) | Mar 28, 2022 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [c9cc022a93](https://linux-hardware.org/?probe=c9cc022a93) | Mar 28, 2022 |
| ASRock        | AB350M-HDV R3.0             | Desktop     | [7024cc263a](https://linux-hardware.org/?probe=7024cc263a) | Mar 28, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [c9368e5a4a](https://linux-hardware.org/?probe=c9368e5a4a) | Mar 28, 2022 |
| ASUSTek       | ROG STRIX B360-F GAMING     | Desktop     | [11d32dddf9](https://linux-hardware.org/?probe=11d32dddf9) | Mar 28, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [7829bdde58](https://linux-hardware.org/?probe=7829bdde58) | Mar 28, 2022 |
| ECS           | G41T-M7                     | Desktop     | [cdeda3b238](https://linux-hardware.org/?probe=cdeda3b238) | Mar 27, 2022 |
| Acer          | Aspire Z3101                | All in one  | [180a248108](https://linux-hardware.org/?probe=180a248108) | Mar 27, 2022 |
| ASRock        | A785GXH/128M                | Desktop     | [e644d9e545](https://linux-hardware.org/?probe=e644d9e545) | Mar 27, 2022 |
| MSI           | 970A-G46                    | Desktop     | [c1543a34cf](https://linux-hardware.org/?probe=c1543a34cf) | Mar 27, 2022 |
| ASRock        | B250 Pro4                   | Desktop     | [052897615f](https://linux-hardware.org/?probe=052897615f) | Mar 27, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [b2884ac582](https://linux-hardware.org/?probe=b2884ac582) | Mar 27, 2022 |
| ASUSTek       | K52F                        | Notebook    | [37baf143fa](https://linux-hardware.org/?probe=37baf143fa) | Mar 27, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [1727b6bd44](https://linux-hardware.org/?probe=1727b6bd44) | Mar 27, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [7a70776029](https://linux-hardware.org/?probe=7a70776029) | Mar 27, 2022 |
| HP            | 09F8h                       | Desktop     | [dbfc9b9f29](https://linux-hardware.org/?probe=dbfc9b9f29) | Mar 27, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [a79e7dc9c5](https://linux-hardware.org/?probe=a79e7dc9c5) | Mar 27, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [450dae5049](https://linux-hardware.org/?probe=450dae5049) | Mar 27, 2022 |
| ASUSTek       | N56VJ                       | Notebook    | [e5a80caf47](https://linux-hardware.org/?probe=e5a80caf47) | Mar 27, 2022 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [6ca9c192ee](https://linux-hardware.org/?probe=6ca9c192ee) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [0a94255553](https://linux-hardware.org/?probe=0a94255553) | Mar 27, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [f7eb22bcfc](https://linux-hardware.org/?probe=f7eb22bcfc) | Mar 27, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [026a52c3bf](https://linux-hardware.org/?probe=026a52c3bf) | Mar 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [4d4d8a247d](https://linux-hardware.org/?probe=4d4d8a247d) | Mar 27, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e7211c8a24](https://linux-hardware.org/?probe=e7211c8a24) | Mar 27, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [c5dac7978e](https://linux-hardware.org/?probe=c5dac7978e) | Mar 27, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [bbb38ea950](https://linux-hardware.org/?probe=bbb38ea950) | Mar 27, 2022 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [ab14b95970](https://linux-hardware.org/?probe=ab14b95970) | Mar 27, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ddd1434a1d](https://linux-hardware.org/?probe=ddd1434a1d) | Mar 27, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [2e240346e4](https://linux-hardware.org/?probe=2e240346e4) | Mar 27, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [b055956ef9](https://linux-hardware.org/?probe=b055956ef9) | Mar 27, 2022 |
| Dell          | Latitude D630               | Notebook    | [1aef88fee8](https://linux-hardware.org/?probe=1aef88fee8) | Mar 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a8f5aed110](https://linux-hardware.org/?probe=a8f5aed110) | Mar 27, 2022 |
| Gigabyte      | GA-E6010N                   | Desktop     | [92e299d57a](https://linux-hardware.org/?probe=92e299d57a) | Mar 27, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [0cfc174313](https://linux-hardware.org/?probe=0cfc174313) | Mar 26, 2022 |
| Acer          | Aspire C24-320              | All in one  | [34813dfad2](https://linux-hardware.org/?probe=34813dfad2) | Mar 26, 2022 |
| Acer          | Aspire 5930                 | Notebook    | [792fcd62f8](https://linux-hardware.org/?probe=792fcd62f8) | Mar 26, 2022 |
| Gigabyte      | P41T-D3P                    | Desktop     | [3952f72348](https://linux-hardware.org/?probe=3952f72348) | Mar 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [01a39ed63c](https://linux-hardware.org/?probe=01a39ed63c) | Mar 26, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [0e02af9ab7](https://linux-hardware.org/?probe=0e02af9ab7) | Mar 26, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [80db7a4eb7](https://linux-hardware.org/?probe=80db7a4eb7) | Mar 26, 2022 |
| ASUSTek       | K54C                        | Notebook    | [07db23bedc](https://linux-hardware.org/?probe=07db23bedc) | Mar 26, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [e37db9015b](https://linux-hardware.org/?probe=e37db9015b) | Mar 26, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [733309bfe7](https://linux-hardware.org/?probe=733309bfe7) | Mar 26, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [5baa3973a9](https://linux-hardware.org/?probe=5baa3973a9) | Mar 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [a1b46c124a](https://linux-hardware.org/?probe=a1b46c124a) | Mar 26, 2022 |
| ECS           | G31T-M7                     | Desktop     | [6ae60fc846](https://linux-hardware.org/?probe=6ae60fc846) | Mar 26, 2022 |
| Gigabyte      | EP31-DS3L                   | Desktop     | [349383626b](https://linux-hardware.org/?probe=349383626b) | Mar 26, 2022 |
| ASUSTek       | GL553VE                     | Notebook    | [819be626ab](https://linux-hardware.org/?probe=819be626ab) | Mar 26, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [a7d9a4a0de](https://linux-hardware.org/?probe=a7d9a4a0de) | Mar 26, 2022 |
| ASUSTek       | P5G41T-M LX3                | Desktop     | [10b27986c9](https://linux-hardware.org/?probe=10b27986c9) | Mar 26, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [6690115e22](https://linux-hardware.org/?probe=6690115e22) | Mar 25, 2022 |
| MSI           | H61M-P31                    | Desktop     | [0b50659b44](https://linux-hardware.org/?probe=0b50659b44) | Mar 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [fa8d5965d7](https://linux-hardware.org/?probe=fa8d5965d7) | Mar 25, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [419c6047da](https://linux-hardware.org/?probe=419c6047da) | Mar 25, 2022 |
| ASUSTek       | F2A55-M LE                  | Desktop     | [e027562517](https://linux-hardware.org/?probe=e027562517) | Mar 25, 2022 |
| Infomash      | MS-163A                     | Notebook    | [90c92e916b](https://linux-hardware.org/?probe=90c92e916b) | Mar 25, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [9fb63e991c](https://linux-hardware.org/?probe=9fb63e991c) | Mar 25, 2022 |
| Lenovo        | B590 20208                  | Notebook    | [a955ba8b71](https://linux-hardware.org/?probe=a955ba8b71) | Mar 25, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [77f39ed5ef](https://linux-hardware.org/?probe=77f39ed5ef) | Mar 25, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [00e8da8c29](https://linux-hardware.org/?probe=00e8da8c29) | Mar 25, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [811ccad24d](https://linux-hardware.org/?probe=811ccad24d) | Mar 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [1381f81018](https://linux-hardware.org/?probe=1381f81018) | Mar 25, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [3ff575d2e1](https://linux-hardware.org/?probe=3ff575d2e1) | Mar 25, 2022 |
| Acer          | Extensa 2540                | Notebook    | [15f6f446ee](https://linux-hardware.org/?probe=15f6f446ee) | Mar 25, 2022 |
| Unknown       | YL-J1900-V1                 | Desktop     | [835f68900c](https://linux-hardware.org/?probe=835f68900c) | Mar 25, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [d60719a932](https://linux-hardware.org/?probe=d60719a932) | Mar 25, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [36f716cd9b](https://linux-hardware.org/?probe=36f716cd9b) | Mar 25, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [1a9b30af2a](https://linux-hardware.org/?probe=1a9b30af2a) | Mar 25, 2022 |
| Infomash      | MS-163A                     | Notebook    | [d620350f18](https://linux-hardware.org/?probe=d620350f18) | Mar 25, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [2a059657b4](https://linux-hardware.org/?probe=2a059657b4) | Mar 24, 2022 |
| HP            | Compaq 615                  | Notebook    | [c61f5e75c7](https://linux-hardware.org/?probe=c61f5e75c7) | Mar 24, 2022 |
| Acer          | Aspire C22-760              | All in one  | [212ddc6fe7](https://linux-hardware.org/?probe=212ddc6fe7) | Mar 24, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [150e438d6e](https://linux-hardware.org/?probe=150e438d6e) | Mar 24, 2022 |
| ASUSTek       | K53U                        | Notebook    | [71a6293088](https://linux-hardware.org/?probe=71a6293088) | Mar 24, 2022 |
| Intel         | B75                         | Desktop     | [e536726a62](https://linux-hardware.org/?probe=e536726a62) | Mar 24, 2022 |
| Gigabyte      | X570S AORUS MASTER          | Desktop     | [b4c23c72de](https://linux-hardware.org/?probe=b4c23c72de) | Mar 24, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [4e1401bc98](https://linux-hardware.org/?probe=4e1401bc98) | Mar 24, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [29ede999bb](https://linux-hardware.org/?probe=29ede999bb) | Mar 24, 2022 |
| Acer          | Aspire C24-320              | All in one  | [a41d66f593](https://linux-hardware.org/?probe=a41d66f593) | Mar 24, 2022 |
| ASUSTek       | P5Q SE                      | Desktop     | [926ae629bd](https://linux-hardware.org/?probe=926ae629bd) | Mar 24, 2022 |
| HP            | ProBook 455 G1              | Notebook    | [9e554de092](https://linux-hardware.org/?probe=9e554de092) | Mar 24, 2022 |
| Sony          | VPCF13E1R                   | Notebook    | [361546db94](https://linux-hardware.org/?probe=361546db94) | Mar 24, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [d9e98611b8](https://linux-hardware.org/?probe=d9e98611b8) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [ebd44c18a4](https://linux-hardware.org/?probe=ebd44c18a4) | Mar 23, 2022 |
| ASRock        | H510M-HVS                   | Desktop     | [f47c9449b9](https://linux-hardware.org/?probe=f47c9449b9) | Mar 23, 2022 |
| Acer          | TravelMate B118-M           | Notebook    | [30b2718a46](https://linux-hardware.org/?probe=30b2718a46) | Mar 23, 2022 |
| MSI           | Z270-A PRO                  | Desktop     | [e0fefdb7c8](https://linux-hardware.org/?probe=e0fefdb7c8) | Mar 23, 2022 |
| Dell          | G3 3590                     | Notebook    | [2181ac62a9](https://linux-hardware.org/?probe=2181ac62a9) | Mar 23, 2022 |
| Dell          | 0M858N A00                  | Desktop     | [b5b6beaa5d](https://linux-hardware.org/?probe=b5b6beaa5d) | Mar 23, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [4bef3efcae](https://linux-hardware.org/?probe=4bef3efcae) | Mar 23, 2022 |
| Dell          | G3 3590                     | Notebook    | [8081671504](https://linux-hardware.org/?probe=8081671504) | Mar 23, 2022 |
| Acer          | Aspire A315-51              | Notebook    | [8f801104d1](https://linux-hardware.org/?probe=8f801104d1) | Mar 23, 2022 |
| ASUSTek       | K84L                        | Notebook    | [4c12e53ed1](https://linux-hardware.org/?probe=4c12e53ed1) | Mar 23, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [61a3132b66](https://linux-hardware.org/?probe=61a3132b66) | Mar 23, 2022 |
| ASRock        | N68-VS3 FX                  | Desktop     | [c675421a82](https://linux-hardware.org/?probe=c675421a82) | Mar 23, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [66d2a3d28a](https://linux-hardware.org/?probe=66d2a3d28a) | Mar 23, 2022 |
| Lenovo        | ThinkPad L450 20DT0013RT    | Notebook    | [3feee1f95c](https://linux-hardware.org/?probe=3feee1f95c) | Mar 23, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [42e6c66cbd](https://linux-hardware.org/?probe=42e6c66cbd) | Mar 23, 2022 |
| ASUSTek       | M5A97                       | Desktop     | [ea157e214f](https://linux-hardware.org/?probe=ea157e214f) | Mar 23, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [26443633b7](https://linux-hardware.org/?probe=26443633b7) | Mar 23, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [ae49c43f44](https://linux-hardware.org/?probe=ae49c43f44) | Mar 23, 2022 |
| Samsung       | 530U3BI/530U4BI/530U4BH     | Notebook    | [d9fc74e94c](https://linux-hardware.org/?probe=d9fc74e94c) | Mar 23, 2022 |
| Lenovo        | 3000 G430 4153/200          | Notebook    | [19a8b8118b](https://linux-hardware.org/?probe=19a8b8118b) | Mar 23, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [6ae3b7ae99](https://linux-hardware.org/?probe=6ae3b7ae99) | Mar 23, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [27b65f8212](https://linux-hardware.org/?probe=27b65f8212) | Mar 23, 2022 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [7b835e9a57](https://linux-hardware.org/?probe=7b835e9a57) | Mar 23, 2022 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [a2055267ff](https://linux-hardware.org/?probe=a2055267ff) | Mar 23, 2022 |
| HP            | Laptop 15-bs1xx             | Notebook    | [1564427e82](https://linux-hardware.org/?probe=1564427e82) | Mar 23, 2022 |
| Unknown       | YL-J1900-V1                 | Desktop     | [add4b942ef](https://linux-hardware.org/?probe=add4b942ef) | Mar 23, 2022 |
| MSI           | H61M-P21                    | Desktop     | [99db7fcf53](https://linux-hardware.org/?probe=99db7fcf53) | Mar 23, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [305ac1dddd](https://linux-hardware.org/?probe=305ac1dddd) | Mar 23, 2022 |
| ASUSTek       | M2N-MX                      | Desktop     | [6d2cb7a6f5](https://linux-hardware.org/?probe=6d2cb7a6f5) | Mar 22, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [3625536523](https://linux-hardware.org/?probe=3625536523) | Mar 22, 2022 |
| Gigabyte      | P55-UD3L                    | Desktop     | [ee3e9ec967](https://linux-hardware.org/?probe=ee3e9ec967) | Mar 22, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [1b06197c8b](https://linux-hardware.org/?probe=1b06197c8b) | Mar 22, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [59daba0b8a](https://linux-hardware.org/?probe=59daba0b8a) | Mar 22, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [6788522a8a](https://linux-hardware.org/?probe=6788522a8a) | Mar 22, 2022 |
| ASRock        | B550M-HDV                   | Desktop     | [22983e54a4](https://linux-hardware.org/?probe=22983e54a4) | Mar 22, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [0a9892ebf9](https://linux-hardware.org/?probe=0a9892ebf9) | Mar 22, 2022 |
| HP            | 859C                        | Desktop     | [4c598fdb6d](https://linux-hardware.org/?probe=4c598fdb6d) | Mar 22, 2022 |
| Unknown       | YL-J1900-V1                 | Desktop     | [396ac36ac2](https://linux-hardware.org/?probe=396ac36ac2) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [378bbcd029](https://linux-hardware.org/?probe=378bbcd029) | Mar 22, 2022 |
| ASUSTek       | P5K                         | Desktop     | [da0019c5d0](https://linux-hardware.org/?probe=da0019c5d0) | Mar 22, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [6ede510a1b](https://linux-hardware.org/?probe=6ede510a1b) | Mar 22, 2022 |
| MSI           | MS-7250                     | Desktop     | [c115855cc4](https://linux-hardware.org/?probe=c115855cc4) | Mar 22, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [7662478d56](https://linux-hardware.org/?probe=7662478d56) | Mar 22, 2022 |
| Lenovo        | B5400 20278                 | Notebook    | [ef29445841](https://linux-hardware.org/?probe=ef29445841) | Mar 22, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [416808d28d](https://linux-hardware.org/?probe=416808d28d) | Mar 22, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [8d1459408f](https://linux-hardware.org/?probe=8d1459408f) | Mar 22, 2022 |
| Acer          | Iconia W700                 | Notebook    | [e4ed6bd52d](https://linux-hardware.org/?probe=e4ed6bd52d) | Mar 22, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6f9fd785de](https://linux-hardware.org/?probe=6f9fd785de) | Mar 21, 2022 |
| ASRock        | G41C-GS R2.0                | Desktop     | [6cd511ea30](https://linux-hardware.org/?probe=6cd511ea30) | Mar 21, 2022 |
| Toshiba       | Satellite L40               | Notebook    | [273b204272](https://linux-hardware.org/?probe=273b204272) | Mar 21, 2022 |
| Samsung       | 530U4E/540U4E               | Notebook    | [2a013dea90](https://linux-hardware.org/?probe=2a013dea90) | Mar 21, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [c795f0ba68](https://linux-hardware.org/?probe=c795f0ba68) | Mar 21, 2022 |
| HP            | ProBook 430 G1              | Notebook    | [a9acd08c72](https://linux-hardware.org/?probe=a9acd08c72) | Mar 21, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [46c12ec623](https://linux-hardware.org/?probe=46c12ec623) | Mar 21, 2022 |
| Acer          | Aspire ES1-521              | Notebook    | [7c8de8440e](https://linux-hardware.org/?probe=7c8de8440e) | Mar 21, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [80ef8b623c](https://linux-hardware.org/?probe=80ef8b623c) | Mar 21, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [0b69dcafad](https://linux-hardware.org/?probe=0b69dcafad) | Mar 21, 2022 |
| Samsung       | 530U4E/540U4E               | Notebook    | [95b1b45b99](https://linux-hardware.org/?probe=95b1b45b99) | Mar 21, 2022 |
| MSI           | Sword 15 A11UE              | Notebook    | [c9d9ef0d26](https://linux-hardware.org/?probe=c9d9ef0d26) | Mar 21, 2022 |
| ASUSTek       | B150 PRO GAMING             | Desktop     | [fce8e3cc98](https://linux-hardware.org/?probe=fce8e3cc98) | Mar 21, 2022 |
| ASUSTek       | X542UA                      | Notebook    | [37f9251b2d](https://linux-hardware.org/?probe=37f9251b2d) | Mar 20, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [dad19ddec6](https://linux-hardware.org/?probe=dad19ddec6) | Mar 20, 2022 |
| ASRock        | G41C-GS                     | Desktop     | [baab4934ee](https://linux-hardware.org/?probe=baab4934ee) | Mar 20, 2022 |
| Pegatron      | A15                         | Notebook    | [624909f9a0](https://linux-hardware.org/?probe=624909f9a0) | Mar 20, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f8f92ef73d](https://linux-hardware.org/?probe=f8f92ef73d) | Mar 20, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [d9a23e9bfb](https://linux-hardware.org/?probe=d9a23e9bfb) | Mar 20, 2022 |
| HP            | Pavilion 15                 | Notebook    | [dc84500611](https://linux-hardware.org/?probe=dc84500611) | Mar 20, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [d54a831153](https://linux-hardware.org/?probe=d54a831153) | Mar 20, 2022 |
| Intel         | B75                         | Desktop     | [242c4cde30](https://linux-hardware.org/?probe=242c4cde30) | Mar 20, 2022 |
| HP            | Notebook                    | Notebook    | [e15e8a7e88](https://linux-hardware.org/?probe=e15e8a7e88) | Mar 20, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [739ed6ff81](https://linux-hardware.org/?probe=739ed6ff81) | Mar 20, 2022 |
| Lenovo        | V570c HuronRiver Platfor... | Notebook    | [bcbde01649](https://linux-hardware.org/?probe=bcbde01649) | Mar 20, 2022 |
| Dell          | Inspiron 7720               | Notebook    | [eed3c9f6e5](https://linux-hardware.org/?probe=eed3c9f6e5) | Mar 20, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [7247904393](https://linux-hardware.org/?probe=7247904393) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [a9ac1b42ff](https://linux-hardware.org/?probe=a9ac1b42ff) | Mar 20, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [15e53dcce2](https://linux-hardware.org/?probe=15e53dcce2) | Mar 20, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [bee5c791e6](https://linux-hardware.org/?probe=bee5c791e6) | Mar 20, 2022 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [e2d7611daa](https://linux-hardware.org/?probe=e2d7611daa) | Mar 20, 2022 |
| HP            | G62                         | Notebook    | [5a5a9ce935](https://linux-hardware.org/?probe=5a5a9ce935) | Mar 20, 2022 |
| Prestigio     | PSB133S01ZFH                | Notebook    | [c1e54c7eab](https://linux-hardware.org/?probe=c1e54c7eab) | Mar 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8847624b97](https://linux-hardware.org/?probe=8847624b97) | Mar 20, 2022 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [5b7201b789](https://linux-hardware.org/?probe=5b7201b789) | Mar 20, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [29e1abc7b1](https://linux-hardware.org/?probe=29e1abc7b1) | Mar 20, 2022 |
| ASRock        | 890GX Extreme4              | Desktop     | [3c57e1ac31](https://linux-hardware.org/?probe=3c57e1ac31) | Mar 20, 2022 |
| Foxconn       | H67M-S/H67M-V/H67M          | Desktop     | [ced87dc2b5](https://linux-hardware.org/?probe=ced87dc2b5) | Mar 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [a6674cd472](https://linux-hardware.org/?probe=a6674cd472) | Mar 20, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [bb400c5756](https://linux-hardware.org/?probe=bb400c5756) | Mar 20, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [ca3ab5bf1d](https://linux-hardware.org/?probe=ca3ab5bf1d) | Mar 20, 2022 |
| Lenovo        | B50-45 20388                | Notebook    | [5269284471](https://linux-hardware.org/?probe=5269284471) | Mar 20, 2022 |
| ASUSTek       | K53SC                       | Notebook    | [7f0fe8a60c](https://linux-hardware.org/?probe=7f0fe8a60c) | Mar 20, 2022 |
| ASRock        | 890GX Extreme4              | Desktop     | [8c38c582bf](https://linux-hardware.org/?probe=8c38c582bf) | Mar 20, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [779e8733bd](https://linux-hardware.org/?probe=779e8733bd) | Mar 20, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [8740fa2680](https://linux-hardware.org/?probe=8740fa2680) | Mar 20, 2022 |
| Dell          | 0F3KHR A00                  | Desktop     | [b312650d8d](https://linux-hardware.org/?probe=b312650d8d) | Mar 20, 2022 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [2ec6236c3a](https://linux-hardware.org/?probe=2ec6236c3a) | Mar 20, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [2fd6e0b6e8](https://linux-hardware.org/?probe=2fd6e0b6e8) | Mar 20, 2022 |
| Unknown       | Unknown                     | Desktop     | [ba50ffd3f8](https://linux-hardware.org/?probe=ba50ffd3f8) | Mar 20, 2022 |
| ASUSTek       | 1015BX                      | Notebook    | [e0b95ee4e6](https://linux-hardware.org/?probe=e0b95ee4e6) | Mar 19, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [f789f4563a](https://linux-hardware.org/?probe=f789f4563a) | Mar 19, 2022 |
| Lenovo        | ThinkPad X250 20CLS2JX00    | Notebook    | [c70a6de9d2](https://linux-hardware.org/?probe=c70a6de9d2) | Mar 19, 2022 |
| Samsung       | R528/R728                   | Notebook    | [0c8e6339bc](https://linux-hardware.org/?probe=0c8e6339bc) | Mar 19, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [5ee99a6dc2](https://linux-hardware.org/?probe=5ee99a6dc2) | Mar 19, 2022 |
| ASUSTek       | P8Z68-V LX                  | Desktop     | [2b99f73675](https://linux-hardware.org/?probe=2b99f73675) | Mar 19, 2022 |
| Acer          | Aspire A715-42G             | Notebook    | [29e36c8581](https://linux-hardware.org/?probe=29e36c8581) | Mar 19, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [90adc19337](https://linux-hardware.org/?probe=90adc19337) | Mar 19, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [3ca3cc710d](https://linux-hardware.org/?probe=3ca3cc710d) | Mar 19, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [da9b5fc00d](https://linux-hardware.org/?probe=da9b5fc00d) | Mar 19, 2022 |
| ASRock        | Z270 Gaming K4              | Desktop     | [fd96a47e75](https://linux-hardware.org/?probe=fd96a47e75) | Mar 19, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [b07f0b09c6](https://linux-hardware.org/?probe=b07f0b09c6) | Mar 19, 2022 |
| ASUSTek       | B150M-PLUS D3               | Desktop     | [3ab8a178e9](https://linux-hardware.org/?probe=3ab8a178e9) | Mar 19, 2022 |
| Toshiba       | Satellite P500              | Notebook    | [7ea81d88f5](https://linux-hardware.org/?probe=7ea81d88f5) | Mar 19, 2022 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [97e0d86243](https://linux-hardware.org/?probe=97e0d86243) | Mar 19, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [db1d7d479d](https://linux-hardware.org/?probe=db1d7d479d) | Mar 19, 2022 |
| Gigabyte      | H97-HD3                     | Desktop     | [92215486d6](https://linux-hardware.org/?probe=92215486d6) | Mar 19, 2022 |
| ASUSTek       | X551CAP                     | Notebook    | [c0a4d8f9b3](https://linux-hardware.org/?probe=c0a4d8f9b3) | Mar 19, 2022 |
| Gigabyte      | GA-78LMT-S2 R2              | Desktop     | [550ded7f81](https://linux-hardware.org/?probe=550ded7f81) | Mar 19, 2022 |
| Acer          | Aspire V5-572PG             | Notebook    | [71bde2a34c](https://linux-hardware.org/?probe=71bde2a34c) | Mar 19, 2022 |
| Lenovo        | 3000 G410                   | Notebook    | [4ed6a8bd15](https://linux-hardware.org/?probe=4ed6a8bd15) | Mar 19, 2022 |
| Biostar       | H61MHV2                     | Desktop     | [7215b0c338](https://linux-hardware.org/?probe=7215b0c338) | Mar 18, 2022 |
| Gigabyte      | B560M GAMING HD             | Desktop     | [7fb3161cf4](https://linux-hardware.org/?probe=7fb3161cf4) | Mar 18, 2022 |
| Acer          | TravelMate B117-M           | Notebook    | [7cc2868a61](https://linux-hardware.org/?probe=7cc2868a61) | Mar 18, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [e1abb8fa21](https://linux-hardware.org/?probe=e1abb8fa21) | Mar 18, 2022 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [520707aa61](https://linux-hardware.org/?probe=520707aa61) | Mar 18, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [a164112f8d](https://linux-hardware.org/?probe=a164112f8d) | Mar 18, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [5f407ad359](https://linux-hardware.org/?probe=5f407ad359) | Mar 18, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [e9e34594e8](https://linux-hardware.org/?probe=e9e34594e8) | Mar 18, 2022 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [b8ad1b22aa](https://linux-hardware.org/?probe=b8ad1b22aa) | Mar 18, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [4b2329edf6](https://linux-hardware.org/?probe=4b2329edf6) | Mar 18, 2022 |
| ASUSTek       | P50IJ                       | Notebook    | [1c1bbe3dad](https://linux-hardware.org/?probe=1c1bbe3dad) | Mar 18, 2022 |
| HP            | Presario CQ57               | Notebook    | [d5985051c5](https://linux-hardware.org/?probe=d5985051c5) | Mar 18, 2022 |
| Dell          | G5 5590                     | Notebook    | [459123608b](https://linux-hardware.org/?probe=459123608b) | Mar 18, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [406c69d7cd](https://linux-hardware.org/?probe=406c69d7cd) | Mar 18, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [f2011ec78e](https://linux-hardware.org/?probe=f2011ec78e) | Mar 18, 2022 |
| Lenovo        | ThinkPad E470 20H2S17C00    | Notebook    | [10ad5ccfbe](https://linux-hardware.org/?probe=10ad5ccfbe) | Mar 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [dc42360c90](https://linux-hardware.org/?probe=dc42360c90) | Mar 18, 2022 |
| Lenovo        | H420                        | Desktop     | [b6aa4d1454](https://linux-hardware.org/?probe=b6aa4d1454) | Mar 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [58912ced73](https://linux-hardware.org/?probe=58912ced73) | Mar 18, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [9f2b618c06](https://linux-hardware.org/?probe=9f2b618c06) | Mar 17, 2022 |
| MSI           | H81M-P33                    | Desktop     | [3cfbfd5eae](https://linux-hardware.org/?probe=3cfbfd5eae) | Mar 17, 2022 |
| Acer          | Veriton S2610G              | Desktop     | [f386a19d48](https://linux-hardware.org/?probe=f386a19d48) | Mar 17, 2022 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [6848ceabc3](https://linux-hardware.org/?probe=6848ceabc3) | Mar 17, 2022 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [a40f7ff51b](https://linux-hardware.org/?probe=a40f7ff51b) | Mar 17, 2022 |
| Gigabyte      | GA-78LMT-S2 R2              | Desktop     | [715a4f0c38](https://linux-hardware.org/?probe=715a4f0c38) | Mar 17, 2022 |
| Dell          | Precision 7510              | Notebook    | [b245b3fbbe](https://linux-hardware.org/?probe=b245b3fbbe) | Mar 17, 2022 |
| Acer          | Veriton N4660G              | Desktop     | [d388b291e1](https://linux-hardware.org/?probe=d388b291e1) | Mar 17, 2022 |
| Acer          | TravelMate P259-MG          | Notebook    | [cff272c0eb](https://linux-hardware.org/?probe=cff272c0eb) | Mar 17, 2022 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [7067f88bee](https://linux-hardware.org/?probe=7067f88bee) | Mar 17, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [9b36863bd5](https://linux-hardware.org/?probe=9b36863bd5) | Mar 17, 2022 |
| HP            | 876C SMVB                   | Desktop     | [70e0a9f8cd](https://linux-hardware.org/?probe=70e0a9f8cd) | Mar 17, 2022 |
| HP            | 876C SMVB                   | Desktop     | [f077c079e1](https://linux-hardware.org/?probe=f077c079e1) | Mar 17, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [d011070d04](https://linux-hardware.org/?probe=d011070d04) | Mar 17, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [fdc892fa82](https://linux-hardware.org/?probe=fdc892fa82) | Mar 16, 2022 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [a524460989](https://linux-hardware.org/?probe=a524460989) | Mar 16, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [43a66e755d](https://linux-hardware.org/?probe=43a66e755d) | Mar 16, 2022 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [5dc9563e82](https://linux-hardware.org/?probe=5dc9563e82) | Mar 16, 2022 |
| Lenovo        | Legion Y730-17ICH 81HG      | Notebook    | [f351aaa28f](https://linux-hardware.org/?probe=f351aaa28f) | Mar 16, 2022 |
| Acer          | AOD260                      | Notebook    | [a2c202021a](https://linux-hardware.org/?probe=a2c202021a) | Mar 16, 2022 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [bde043ea5f](https://linux-hardware.org/?probe=bde043ea5f) | Mar 16, 2022 |
| ASUSTek       | K53SM                       | Notebook    | [8b4b50fef2](https://linux-hardware.org/?probe=8b4b50fef2) | Mar 16, 2022 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [0a84cfb575](https://linux-hardware.org/?probe=0a84cfb575) | Mar 16, 2022 |
| Acer          | AOD260                      | Notebook    | [ad3082d89c](https://linux-hardware.org/?probe=ad3082d89c) | Mar 16, 2022 |
| ASRock        | M3A770DE                    | Desktop     | [5d198542ea](https://linux-hardware.org/?probe=5d198542ea) | Mar 16, 2022 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [1137a7fe46](https://linux-hardware.org/?probe=1137a7fe46) | Mar 16, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [58397d6bc1](https://linux-hardware.org/?probe=58397d6bc1) | Mar 16, 2022 |
| MSI           | MS-7346                     | Desktop     | [2c94f0863d](https://linux-hardware.org/?probe=2c94f0863d) | Mar 16, 2022 |
| Gigabyte      | MZBSWMP-00                  | Desktop     | [8016ca75e5](https://linux-hardware.org/?probe=8016ca75e5) | Mar 16, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [a72345ecaa](https://linux-hardware.org/?probe=a72345ecaa) | Mar 16, 2022 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [1d88facac1](https://linux-hardware.org/?probe=1d88facac1) | Mar 16, 2022 |
| HP            | Pavilion g7                 | Notebook    | [7b01e72658](https://linux-hardware.org/?probe=7b01e72658) | Mar 16, 2022 |
| ASUSTek       | X75VD                       | Notebook    | [e4e91f90ab](https://linux-hardware.org/?probe=e4e91f90ab) | Mar 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [6fb5a4b51e](https://linux-hardware.org/?probe=6fb5a4b51e) | Mar 15, 2022 |
| Gigabyte      | E3000N                      | Desktop     | [10118ff80d](https://linux-hardware.org/?probe=10118ff80d) | Mar 15, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [0d18f0227e](https://linux-hardware.org/?probe=0d18f0227e) | Mar 15, 2022 |
| HP            | Notebook                    | Notebook    | [2a54a0b644](https://linux-hardware.org/?probe=2a54a0b644) | Mar 15, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [16371f42e1](https://linux-hardware.org/?probe=16371f42e1) | Mar 15, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [84a794e739](https://linux-hardware.org/?probe=84a794e739) | Mar 15, 2022 |
| ECS           | GeForce6100PM-M2            | Desktop     | [ebabbc9e72](https://linux-hardware.org/?probe=ebabbc9e72) | Mar 15, 2022 |
| ASUSTek       | K53U                        | Notebook    | [e2c08bf0fd](https://linux-hardware.org/?probe=e2c08bf0fd) | Mar 15, 2022 |
| ASUSTek       | P5K                         | Desktop     | [28f94dd7f7](https://linux-hardware.org/?probe=28f94dd7f7) | Mar 15, 2022 |
| ASUSTek       | X551CA                      | Notebook    | [9f824eb133](https://linux-hardware.org/?probe=9f824eb133) | Mar 15, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [f1844c7ecb](https://linux-hardware.org/?probe=f1844c7ecb) | Mar 15, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [2a0c9b98d8](https://linux-hardware.org/?probe=2a0c9b98d8) | Mar 15, 2022 |
| ASUSTek       | P5KPL-AM IN/GB              | Desktop     | [ccc391b2d8](https://linux-hardware.org/?probe=ccc391b2d8) | Mar 15, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [8e0a8d6f39](https://linux-hardware.org/?probe=8e0a8d6f39) | Mar 15, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [0bfaf3176d](https://linux-hardware.org/?probe=0bfaf3176d) | Mar 14, 2022 |
| Fujitsu       | LIFEBOOK A512               | Notebook    | [b7592d46e1](https://linux-hardware.org/?probe=b7592d46e1) | Mar 14, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [834e2eaf27](https://linux-hardware.org/?probe=834e2eaf27) | Mar 14, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [7e9674d806](https://linux-hardware.org/?probe=7e9674d806) | Mar 14, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [893a0b24ad](https://linux-hardware.org/?probe=893a0b24ad) | Mar 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [9ec78dcd40](https://linux-hardware.org/?probe=9ec78dcd40) | Mar 14, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [2720add6c2](https://linux-hardware.org/?probe=2720add6c2) | Mar 14, 2022 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [29373ba448](https://linux-hardware.org/?probe=29373ba448) | Mar 14, 2022 |
| ASRock        | B75M-DGS                    | Desktop     | [2d0363d0ee](https://linux-hardware.org/?probe=2d0363d0ee) | Mar 14, 2022 |
| Sony          | VPCEJ3L1R                   | Notebook    | [dbe66e9e9c](https://linux-hardware.org/?probe=dbe66e9e9c) | Mar 14, 2022 |
| ASUSTek       | X542UA                      | Notebook    | [60343e7f21](https://linux-hardware.org/?probe=60343e7f21) | Mar 13, 2022 |
| Dell          | 0V6XGW A01                  | Desktop     | [7b091c2035](https://linux-hardware.org/?probe=7b091c2035) | Mar 13, 2022 |
| Acer          | Swift SF113-31              | Notebook    | [52d4aeefe6](https://linux-hardware.org/?probe=52d4aeefe6) | Mar 13, 2022 |
| Acer          | Aspire 5720Z                | Notebook    | [722af64178](https://linux-hardware.org/?probe=722af64178) | Mar 13, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [368bf3c9c6](https://linux-hardware.org/?probe=368bf3c9c6) | Mar 13, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [801998f12b](https://linux-hardware.org/?probe=801998f12b) | Mar 13, 2022 |
| Dell          | Inspiron N4050              | Notebook    | [f4746b80f4](https://linux-hardware.org/?probe=f4746b80f4) | Mar 13, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [a4e0cb6c6e](https://linux-hardware.org/?probe=a4e0cb6c6e) | Mar 13, 2022 |
| ASRock        | M3A785GM-LE/128M            | Desktop     | [c975b33785](https://linux-hardware.org/?probe=c975b33785) | Mar 13, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [35a45d8ad1](https://linux-hardware.org/?probe=35a45d8ad1) | Mar 13, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [a1d347d586](https://linux-hardware.org/?probe=a1d347d586) | Mar 13, 2022 |
| ASUSTek       | K43SJ                       | Notebook    | [e761c99715](https://linux-hardware.org/?probe=e761c99715) | Mar 13, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [2012897e8d](https://linux-hardware.org/?probe=2012897e8d) | Mar 13, 2022 |
| ASRock        | M3A785GM-LE/128M            | Desktop     | [f53d1d8915](https://linux-hardware.org/?probe=f53d1d8915) | Mar 13, 2022 |
| Dell          | Latitude 3490               | Notebook    | [1dba55d488](https://linux-hardware.org/?probe=1dba55d488) | Mar 13, 2022 |
| Q87IX-06 1... | Unknown                     | Desktop     | [76207bc752](https://linux-hardware.org/?probe=76207bc752) | Mar 13, 2022 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [4ff0a96ca0](https://linux-hardware.org/?probe=4ff0a96ca0) | Mar 13, 2022 |
| ASUSTek       | X542UQ                      | Notebook    | [420374cb35](https://linux-hardware.org/?probe=420374cb35) | Mar 13, 2022 |
| ASUSTek       | H81M-D PLUS                 | Desktop     | [ac0b0cf98a](https://linux-hardware.org/?probe=ac0b0cf98a) | Mar 13, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [91c5ac0437](https://linux-hardware.org/?probe=91c5ac0437) | Mar 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [65301eac1a](https://linux-hardware.org/?probe=65301eac1a) | Mar 13, 2022 |
| MSI           | MS-7388                     | Desktop     | [fdd664b3fe](https://linux-hardware.org/?probe=fdd664b3fe) | Mar 13, 2022 |
| MSI           | MS-7346                     | Desktop     | [0be963d491](https://linux-hardware.org/?probe=0be963d491) | Mar 13, 2022 |
| Sony          | VPCSA3Z9R                   | Notebook    | [3a61548567](https://linux-hardware.org/?probe=3a61548567) | Mar 12, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [7e8c13d66a](https://linux-hardware.org/?probe=7e8c13d66a) | Mar 12, 2022 |
| MSI           | H510M-A PRO                 | Desktop     | [dc8b7b9927](https://linux-hardware.org/?probe=dc8b7b9927) | Mar 12, 2022 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [0198690333](https://linux-hardware.org/?probe=0198690333) | Mar 12, 2022 |
| ASRock        | Z68 Pro3-M                  | Desktop     | [2a053f027f](https://linux-hardware.org/?probe=2a053f027f) | Mar 12, 2022 |
| MSI           | H81M-P33                    | Desktop     | [95d1b63c52](https://linux-hardware.org/?probe=95d1b63c52) | Mar 12, 2022 |
| Sony          | VPCEB2M1R                   | Notebook    | [aa365b6983](https://linux-hardware.org/?probe=aa365b6983) | Mar 12, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [1aa06e7b53](https://linux-hardware.org/?probe=1aa06e7b53) | Mar 12, 2022 |
| ASUSTek       | M2A74-AM SE                 | Desktop     | [7b20c55003](https://linux-hardware.org/?probe=7b20c55003) | Mar 12, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [2894a9c0be](https://linux-hardware.org/?probe=2894a9c0be) | Mar 12, 2022 |
| ASUSTek       | X551CA                      | Notebook    | [6822444b1c](https://linux-hardware.org/?probe=6822444b1c) | Mar 12, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [01c90d7554](https://linux-hardware.org/?probe=01c90d7554) | Mar 12, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [5f10f7d1af](https://linux-hardware.org/?probe=5f10f7d1af) | Mar 12, 2022 |
| Dell          | Inspiron M5040              | Notebook    | [d765287ece](https://linux-hardware.org/?probe=d765287ece) | Mar 12, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [c378755487](https://linux-hardware.org/?probe=c378755487) | Mar 12, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [33a860d059](https://linux-hardware.org/?probe=33a860d059) | Mar 12, 2022 |
| Lenovo        | ThinkPad E580 20KS004GRT    | Notebook    | [4b3ecbe68e](https://linux-hardware.org/?probe=4b3ecbe68e) | Mar 11, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [30fd47f18c](https://linux-hardware.org/?probe=30fd47f18c) | Mar 11, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [7297101144](https://linux-hardware.org/?probe=7297101144) | Mar 11, 2022 |
| ASUSTek       | P5G41-M LE                  | Desktop     | [b6f7044980](https://linux-hardware.org/?probe=b6f7044980) | Mar 11, 2022 |
| Unknown       | Intel X79                   | Desktop     | [c848063fc1](https://linux-hardware.org/?probe=c848063fc1) | Mar 11, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [5a356066ca](https://linux-hardware.org/?probe=5a356066ca) | Mar 11, 2022 |
| ASUSTek       | P8H61-V                     | Desktop     | [566a8ae873](https://linux-hardware.org/?probe=566a8ae873) | Mar 11, 2022 |
| Lenovo        | 20208                       | Notebook    | [533a09b178](https://linux-hardware.org/?probe=533a09b178) | Mar 11, 2022 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [a6560af3a5](https://linux-hardware.org/?probe=a6560af3a5) | Mar 11, 2022 |
| Acer          | Aspire V5-571G              | Notebook    | [10a01b6a76](https://linux-hardware.org/?probe=10a01b6a76) | Mar 11, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [0da436fc26](https://linux-hardware.org/?probe=0da436fc26) | Mar 11, 2022 |
| Clevo         | M770SUA                     | Notebook    | [25b6849aa9](https://linux-hardware.org/?probe=25b6849aa9) | Mar 11, 2022 |
| AZW           | Gemini J45                  | Desktop     | [6705e1afd9](https://linux-hardware.org/?probe=6705e1afd9) | Mar 11, 2022 |
| MSI           | GP60 2OD                    | Notebook    | [14ec7ffbca](https://linux-hardware.org/?probe=14ec7ffbca) | Mar 11, 2022 |
| Gigabyte      | F2A75M-D3H                  | Desktop     | [093ff734b6](https://linux-hardware.org/?probe=093ff734b6) | Mar 11, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [725cbb4998](https://linux-hardware.org/?probe=725cbb4998) | Mar 11, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [f6068483ce](https://linux-hardware.org/?probe=f6068483ce) | Mar 11, 2022 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [5c45b0b08a](https://linux-hardware.org/?probe=5c45b0b08a) | Mar 11, 2022 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [2b68e9fabf](https://linux-hardware.org/?probe=2b68e9fabf) | Mar 11, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [cb8afcb315](https://linux-hardware.org/?probe=cb8afcb315) | Mar 11, 2022 |
| Acer          | Aspire V5-571G              | Notebook    | [e909e31559](https://linux-hardware.org/?probe=e909e31559) | Mar 11, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [59a21d0aa2](https://linux-hardware.org/?probe=59a21d0aa2) | Mar 11, 2022 |
| Acer          | IPISB-AG                    | All in one  | [520a9bc6a0](https://linux-hardware.org/?probe=520a9bc6a0) | Mar 11, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [dab731fd45](https://linux-hardware.org/?probe=dab731fd45) | Mar 11, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [1a144a142f](https://linux-hardware.org/?probe=1a144a142f) | Mar 11, 2022 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [0a534cf272](https://linux-hardware.org/?probe=0a534cf272) | Mar 11, 2022 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [f58bb47a42](https://linux-hardware.org/?probe=f58bb47a42) | Mar 11, 2022 |
| ASUSTek       | M4N68T V2                   | Desktop     | [5b061fa374](https://linux-hardware.org/?probe=5b061fa374) | Mar 11, 2022 |
| ASUSTek       | N56VJ                       | Notebook    | [a1d8d94b5f](https://linux-hardware.org/?probe=a1d8d94b5f) | Mar 11, 2022 |
| ASRock        | B75M-DGS                    | Desktop     | [01d3e72fe4](https://linux-hardware.org/?probe=01d3e72fe4) | Mar 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [2ab16bfcee](https://linux-hardware.org/?probe=2ab16bfcee) | Mar 10, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [b5a4e6051e](https://linux-hardware.org/?probe=b5a4e6051e) | Mar 10, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [95b79e0953](https://linux-hardware.org/?probe=95b79e0953) | Mar 10, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [8bbf7f5495](https://linux-hardware.org/?probe=8bbf7f5495) | Mar 10, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [b4738fcf35](https://linux-hardware.org/?probe=b4738fcf35) | Mar 10, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [0a1f5e9bed](https://linux-hardware.org/?probe=0a1f5e9bed) | Mar 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [74aa64e60f](https://linux-hardware.org/?probe=74aa64e60f) | Mar 10, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [73d930be97](https://linux-hardware.org/?probe=73d930be97) | Mar 10, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [e8e38c1cf0](https://linux-hardware.org/?probe=e8e38c1cf0) | Mar 10, 2022 |
| HP            | Presario CQ58               | Notebook    | [2d71998513](https://linux-hardware.org/?probe=2d71998513) | Mar 10, 2022 |
| ASUSTek       | X541UA                      | Notebook    | [629d92121b](https://linux-hardware.org/?probe=629d92121b) | Mar 10, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [45beec1b7c](https://linux-hardware.org/?probe=45beec1b7c) | Mar 10, 2022 |
| JW Technol... | JW-A61PM-D3 Ver1.0          | Desktop     | [36d5ff9438](https://linux-hardware.org/?probe=36d5ff9438) | Mar 10, 2022 |
| ASUSTek       | K53U                        | Notebook    | [262bd2b6b5](https://linux-hardware.org/?probe=262bd2b6b5) | Mar 10, 2022 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [a6fc7b9f12](https://linux-hardware.org/?probe=a6fc7b9f12) | Mar 10, 2022 |
| ASRock        | G31M-GS                     | Desktop     | [fffba31b29](https://linux-hardware.org/?probe=fffba31b29) | Mar 10, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [f07a9bd206](https://linux-hardware.org/?probe=f07a9bd206) | Mar 10, 2022 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [57531c7393](https://linux-hardware.org/?probe=57531c7393) | Mar 10, 2022 |
| ASUSTek       | 1005P                       | Notebook    | [e138dde726](https://linux-hardware.org/?probe=e138dde726) | Mar 09, 2022 |
| Dell          | Latitude E5550              | Notebook    | [38404c5760](https://linux-hardware.org/?probe=38404c5760) | Mar 09, 2022 |
| Intel         | D945GCLF2 AAE46416-101      | Desktop     | [800bc08dbd](https://linux-hardware.org/?probe=800bc08dbd) | Mar 09, 2022 |
| Toshiba       | Satellite A660              | Notebook    | [d52ba5f273](https://linux-hardware.org/?probe=d52ba5f273) | Mar 09, 2022 |
| Dell          | 0RJ291                      | Desktop     | [52526b4a77](https://linux-hardware.org/?probe=52526b4a77) | Mar 09, 2022 |
| Lenovo        | ThinkPad T410 2537VGY       | Notebook    | [4601c3aa77](https://linux-hardware.org/?probe=4601c3aa77) | Mar 09, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [8bb70cc1a1](https://linux-hardware.org/?probe=8bb70cc1a1) | Mar 09, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [17dd3a82ae](https://linux-hardware.org/?probe=17dd3a82ae) | Mar 09, 2022 |
| Dell          | Latitude E6430s             | Notebook    | [2af2bba8da](https://linux-hardware.org/?probe=2af2bba8da) | Mar 09, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [e8e64665a6](https://linux-hardware.org/?probe=e8e64665a6) | Mar 09, 2022 |
| Notebook      | W517GU1                     | Notebook    | [6a4971b810](https://linux-hardware.org/?probe=6a4971b810) | Mar 09, 2022 |
| Samsung       | R425D/R525D                 | Notebook    | [7e3a87a955](https://linux-hardware.org/?probe=7e3a87a955) | Mar 09, 2022 |
| MSI           | G41M-P26                    | Desktop     | [b6af52fe64](https://linux-hardware.org/?probe=b6af52fe64) | Mar 09, 2022 |
| ASUSTek       | P5K                         | Desktop     | [1232b6173b](https://linux-hardware.org/?probe=1232b6173b) | Mar 09, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [2f29bf2f45](https://linux-hardware.org/?probe=2f29bf2f45) | Mar 09, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [6f9fd5c747](https://linux-hardware.org/?probe=6f9fd5c747) | Mar 09, 2022 |
| MSI           | H97 PC Mate                 | Desktop     | [0f042a9f94](https://linux-hardware.org/?probe=0f042a9f94) | Mar 08, 2022 |
| ASUSTek       | H81M-D                      | Desktop     | [4a77df037b](https://linux-hardware.org/?probe=4a77df037b) | Mar 08, 2022 |
| Acer          | Aspire TC-391               | Desktop     | [146505adee](https://linux-hardware.org/?probe=146505adee) | Mar 08, 2022 |
| Lenovo        | H420                        | Desktop     | [79b5590711](https://linux-hardware.org/?probe=79b5590711) | Mar 08, 2022 |
| Lenovo        | G580                        | Notebook    | [b9824d8702](https://linux-hardware.org/?probe=b9824d8702) | Mar 08, 2022 |
| HP            | 15                          | Notebook    | [5b2f656c49](https://linux-hardware.org/?probe=5b2f656c49) | Mar 08, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c28b8c26c1](https://linux-hardware.org/?probe=c28b8c26c1) | Mar 08, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [e8067701ed](https://linux-hardware.org/?probe=e8067701ed) | Mar 08, 2022 |
| MSI           | G31M2                       | Desktop     | [b801fd62b9](https://linux-hardware.org/?probe=b801fd62b9) | Mar 08, 2022 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [21926a008c](https://linux-hardware.org/?probe=21926a008c) | Mar 08, 2022 |
| ASUSTek       | M2N-MX SE                   | Desktop     | [6b9596628e](https://linux-hardware.org/?probe=6b9596628e) | Mar 08, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [ced72ee9f4](https://linux-hardware.org/?probe=ced72ee9f4) | Mar 08, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [2704174c66](https://linux-hardware.org/?probe=2704174c66) | Mar 07, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [061074980c](https://linux-hardware.org/?probe=061074980c) | Mar 07, 2022 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [826909597b](https://linux-hardware.org/?probe=826909597b) | Mar 07, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [a013213da6](https://linux-hardware.org/?probe=a013213da6) | Mar 07, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [5af22f3639](https://linux-hardware.org/?probe=5af22f3639) | Mar 07, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [20a55aa1f3](https://linux-hardware.org/?probe=20a55aa1f3) | Mar 07, 2022 |
| HP            | Mini 110-4100               | Notebook    | [2c1bf1951f](https://linux-hardware.org/?probe=2c1bf1951f) | Mar 07, 2022 |
| Lenovo        | G505 20240                  | Notebook    | [c42d057b96](https://linux-hardware.org/?probe=c42d057b96) | Mar 07, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [7d4fb351f4](https://linux-hardware.org/?probe=7d4fb351f4) | Mar 07, 2022 |
| ASUSTek       | M2N-MX SE                   | Desktop     | [439d12c6fc](https://linux-hardware.org/?probe=439d12c6fc) | Mar 07, 2022 |
| Gigabyte      | B550M S2H                   | Desktop     | [ba45148aae](https://linux-hardware.org/?probe=ba45148aae) | Mar 07, 2022 |
| Acer          | Aspire 3650                 | Notebook    | [29dcfad748](https://linux-hardware.org/?probe=29dcfad748) | Mar 07, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7df453dfd2](https://linux-hardware.org/?probe=7df453dfd2) | Mar 07, 2022 |
| GTZS          | Unknown                     | Notebook    | [7fe0316acf](https://linux-hardware.org/?probe=7fe0316acf) | Mar 07, 2022 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [9e62e2e6d8](https://linux-hardware.org/?probe=9e62e2e6d8) | Mar 07, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [cca7575f29](https://linux-hardware.org/?probe=cca7575f29) | Mar 07, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [1f42efe596](https://linux-hardware.org/?probe=1f42efe596) | Mar 07, 2022 |
| Gateway       | M-6307                      | Notebook    | [046587a2d1](https://linux-hardware.org/?probe=046587a2d1) | Mar 07, 2022 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [be99e3e64a](https://linux-hardware.org/?probe=be99e3e64a) | Mar 07, 2022 |
| Gigabyte      | Z590 GAMING X               | Desktop     | [b3d65c3dfe](https://linux-hardware.org/?probe=b3d65c3dfe) | Mar 07, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [7535a8d317](https://linux-hardware.org/?probe=7535a8d317) | Mar 06, 2022 |
| ASUSTek       | Z87-K                       | Desktop     | [4e3d7eb078](https://linux-hardware.org/?probe=4e3d7eb078) | Mar 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8170747d86](https://linux-hardware.org/?probe=8170747d86) | Mar 06, 2022 |
| Gigabyte      | U2442                       | Notebook    | [24abf055f8](https://linux-hardware.org/?probe=24abf055f8) | Mar 06, 2022 |
| ASRock        | P43DE                       | Desktop     | [08da43be7f](https://linux-hardware.org/?probe=08da43be7f) | Mar 06, 2022 |
| Gigabyte      | H61M-D2H                    | Desktop     | [de63f89d08](https://linux-hardware.org/?probe=de63f89d08) | Mar 06, 2022 |
| GTZS          | Unknown                     | Notebook    | [c6cfedc194](https://linux-hardware.org/?probe=c6cfedc194) | Mar 06, 2022 |
| Gigabyte      | H55-UD3H                    | Desktop     | [d95c52bff7](https://linux-hardware.org/?probe=d95c52bff7) | Mar 06, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [b371240959](https://linux-hardware.org/?probe=b371240959) | Mar 06, 2022 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [80b844d396](https://linux-hardware.org/?probe=80b844d396) | Mar 06, 2022 |
| HP            | Notebook                    | Notebook    | [57ce8d33b8](https://linux-hardware.org/?probe=57ce8d33b8) | Mar 06, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [8a30ea3dc6](https://linux-hardware.org/?probe=8a30ea3dc6) | Mar 06, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [3210667e8d](https://linux-hardware.org/?probe=3210667e8d) | Mar 06, 2022 |
| Acer          | Swift SF114-34              | Notebook    | [18486d2474](https://linux-hardware.org/?probe=18486d2474) | Mar 06, 2022 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7301ac3b25](https://linux-hardware.org/?probe=7301ac3b25) | Mar 06, 2022 |
| HP            | 650                         | Notebook    | [7b018f66df](https://linux-hardware.org/?probe=7b018f66df) | Mar 06, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [85a405bce4](https://linux-hardware.org/?probe=85a405bce4) | Mar 06, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [9a0f2a2848](https://linux-hardware.org/?probe=9a0f2a2848) | Mar 06, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [8d2f324da4](https://linux-hardware.org/?probe=8d2f324da4) | Mar 06, 2022 |
| Sony          | SVS1512U1RW                 | Notebook    | [a8c9c44e7d](https://linux-hardware.org/?probe=a8c9c44e7d) | Mar 06, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [8512aba5f1](https://linux-hardware.org/?probe=8512aba5f1) | Mar 05, 2022 |
| Lenovo        | IdeaPad S20-30              | Notebook    | [d1282ebbca](https://linux-hardware.org/?probe=d1282ebbca) | Mar 05, 2022 |
| Sony          | SVS1512U1RW                 | Notebook    | [007a73bc6e](https://linux-hardware.org/?probe=007a73bc6e) | Mar 05, 2022 |
| Acer          | Aspire A315-34              | Notebook    | [6f53445c9d](https://linux-hardware.org/?probe=6f53445c9d) | Mar 05, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [18b6ca38b8](https://linux-hardware.org/?probe=18b6ca38b8) | Mar 05, 2022 |
| AIO           | H61H-G11                    | Desktop     | [0d7e8c7568](https://linux-hardware.org/?probe=0d7e8c7568) | Mar 05, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [eeb665e3dc](https://linux-hardware.org/?probe=eeb665e3dc) | Mar 05, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [2a1c30169a](https://linux-hardware.org/?probe=2a1c30169a) | Mar 05, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [fb109e5618](https://linux-hardware.org/?probe=fb109e5618) | Mar 05, 2022 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [30ff404b05](https://linux-hardware.org/?probe=30ff404b05) | Mar 05, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [19345d9a81](https://linux-hardware.org/?probe=19345d9a81) | Mar 04, 2022 |
| ASRock        | Q370M vPro                  | Desktop     | [4f6fe9951a](https://linux-hardware.org/?probe=4f6fe9951a) | Mar 04, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [7ba52b85fe](https://linux-hardware.org/?probe=7ba52b85fe) | Mar 04, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [87f171aaf2](https://linux-hardware.org/?probe=87f171aaf2) | Mar 04, 2022 |
| ASRock        | G31M-S                      | Desktop     | [f4f545a858](https://linux-hardware.org/?probe=f4f545a858) | Mar 04, 2022 |
| ASUSTek       | 1201T                       | Notebook    | [0c5ab272e7](https://linux-hardware.org/?probe=0c5ab272e7) | Mar 04, 2022 |
| ASUSTek       | F3E                         | Notebook    | [67c210b75c](https://linux-hardware.org/?probe=67c210b75c) | Mar 04, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [a93cb7c85e](https://linux-hardware.org/?probe=a93cb7c85e) | Mar 04, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [eb84a61b0d](https://linux-hardware.org/?probe=eb84a61b0d) | Mar 03, 2022 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [0d5303fc1a](https://linux-hardware.org/?probe=0d5303fc1a) | Mar 03, 2022 |
| HP            | 635                         | Notebook    | [0d571de480](https://linux-hardware.org/?probe=0d571de480) | Mar 03, 2022 |
| MSI           | GF63 Thin 9SCXR             | Notebook    | [1dd9830ab5](https://linux-hardware.org/?probe=1dd9830ab5) | Mar 03, 2022 |
| Gigabyte      | F2A55-DS3                   | Desktop     | [a1086c2436](https://linux-hardware.org/?probe=a1086c2436) | Mar 03, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [f4e226bea7](https://linux-hardware.org/?probe=f4e226bea7) | Mar 03, 2022 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [9e310a9389](https://linux-hardware.org/?probe=9e310a9389) | Mar 03, 2022 |
| ASUSTek       | P5B-V                       | Desktop     | [2bca34990f](https://linux-hardware.org/?probe=2bca34990f) | Mar 03, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [75a505dc2e](https://linux-hardware.org/?probe=75a505dc2e) | Mar 03, 2022 |
| HP            | G62                         | Notebook    | [5cb594a70d](https://linux-hardware.org/?probe=5cb594a70d) | Mar 02, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [312b86f0cc](https://linux-hardware.org/?probe=312b86f0cc) | Mar 02, 2022 |
| Lenovo        | ThinkPad W530 243857U       | Notebook    | [21c4433bf2](https://linux-hardware.org/?probe=21c4433bf2) | Mar 02, 2022 |
| ASUSTek       | P5BV-C/4L                   | Desktop     | [d05dbacfb2](https://linux-hardware.org/?probe=d05dbacfb2) | Mar 02, 2022 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [4dd2db58c8](https://linux-hardware.org/?probe=4dd2db58c8) | Mar 02, 2022 |
| Gigabyte      | H310M S2                    | Desktop     | [af747fddc7](https://linux-hardware.org/?probe=af747fddc7) | Mar 02, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [c272aff72c](https://linux-hardware.org/?probe=c272aff72c) | Mar 02, 2022 |
| Acer          | P5WE0                       | Notebook    | [c79056479e](https://linux-hardware.org/?probe=c79056479e) | Mar 01, 2022 |
| Irbis         | G04NB6602812000702          | Desktop     | [9aca90e6d5](https://linux-hardware.org/?probe=9aca90e6d5) | Mar 01, 2022 |
| Gigabyte      | GA-MA780G-UD3H              | Desktop     | [d200cdb05c](https://linux-hardware.org/?probe=d200cdb05c) | Mar 01, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [f26f40aa50](https://linux-hardware.org/?probe=f26f40aa50) | Mar 01, 2022 |
| ASRock        | 990FX Extreme9              | Desktop     | [408514b026](https://linux-hardware.org/?probe=408514b026) | Mar 01, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6708cd0723](https://linux-hardware.org/?probe=6708cd0723) | Mar 01, 2022 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [36e3089b38](https://linux-hardware.org/?probe=36e3089b38) | Mar 01, 2022 |
| ASUSTek       | F5SL                        | Notebook    | [f9f7087cdf](https://linux-hardware.org/?probe=f9f7087cdf) | Mar 01, 2022 |
| MSI           | H55M-P31                    | Desktop     | [cde1b92fdc](https://linux-hardware.org/?probe=cde1b92fdc) | Mar 01, 2022 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [a40ff918fe](https://linux-hardware.org/?probe=a40ff918fe) | Mar 01, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7b08a801d1](https://linux-hardware.org/?probe=7b08a801d1) | Mar 01, 2022 |
| Lenovo        | B560                        | Notebook    | [a860ecebe5](https://linux-hardware.org/?probe=a860ecebe5) | Feb 28, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [c11fd047fb](https://linux-hardware.org/?probe=c11fd047fb) | Feb 28, 2022 |
| ASUSTek       | F5SL                        | Notebook    | [01accf63ad](https://linux-hardware.org/?probe=01accf63ad) | Feb 28, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [6cf3696f35](https://linux-hardware.org/?probe=6cf3696f35) | Feb 28, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [4d274afb4a](https://linux-hardware.org/?probe=4d274afb4a) | Feb 28, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [e6b604b9dc](https://linux-hardware.org/?probe=e6b604b9dc) | Feb 28, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [dccdb6871d](https://linux-hardware.org/?probe=dccdb6871d) | Feb 28, 2022 |
| Gigabyte      | H77-DS3H                    | Desktop     | [eb150521bc](https://linux-hardware.org/?probe=eb150521bc) | Feb 28, 2022 |
| Samsung       | Q310                        | Notebook    | [88aa731039](https://linux-hardware.org/?probe=88aa731039) | Feb 28, 2022 |
| ASRock        | N68-S                       | Desktop     | [56c03860e3](https://linux-hardware.org/?probe=56c03860e3) | Feb 28, 2022 |
| Lenovo        | ThinkPad X230 2330A17       | Notebook    | [ed014e00c8](https://linux-hardware.org/?probe=ed014e00c8) | Feb 27, 2022 |
| Dell          | Latitude E6540              | Notebook    | [cb7e492cd9](https://linux-hardware.org/?probe=cb7e492cd9) | Feb 27, 2022 |
| Toshiba       | QOSMIO F60                  | Notebook    | [71e17539c9](https://linux-hardware.org/?probe=71e17539c9) | Feb 27, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [c08be74242](https://linux-hardware.org/?probe=c08be74242) | Feb 27, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9ae863d68c](https://linux-hardware.org/?probe=9ae863d68c) | Feb 27, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [9ffeec636e](https://linux-hardware.org/?probe=9ffeec636e) | Feb 26, 2022 |
| ASRock        | P4i65G                      | Desktop     | [aa7a236464](https://linux-hardware.org/?probe=aa7a236464) | Feb 26, 2022 |
| Lenovo        | ThinkPad X240 20AL0067RT    | Notebook    | [f246d643b4](https://linux-hardware.org/?probe=f246d643b4) | Feb 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [ed1b593603](https://linux-hardware.org/?probe=ed1b593603) | Feb 26, 2022 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [fd3aa1b379](https://linux-hardware.org/?probe=fd3aa1b379) | Feb 26, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [441141c87d](https://linux-hardware.org/?probe=441141c87d) | Feb 26, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [4722b6373e](https://linux-hardware.org/?probe=4722b6373e) | Feb 26, 2022 |
| ASUSTek       | N53SV                       | Notebook    | [d7b0ae17c0](https://linux-hardware.org/?probe=d7b0ae17c0) | Feb 26, 2022 |
| MSI           | MS-7346                     | Desktop     | [369821f3f9](https://linux-hardware.org/?probe=369821f3f9) | Feb 26, 2022 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [b2ba0fabdc](https://linux-hardware.org/?probe=b2ba0fabdc) | Feb 25, 2022 |
| Packard Be... | Veriton M275                | Desktop     | [4957ee6cb9](https://linux-hardware.org/?probe=4957ee6cb9) | Feb 25, 2022 |
| ASUSTek       | 1005PXD                     | Notebook    | [600a38a244](https://linux-hardware.org/?probe=600a38a244) | Feb 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [65eae3fe4c](https://linux-hardware.org/?probe=65eae3fe4c) | Feb 25, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [c3347258f5](https://linux-hardware.org/?probe=c3347258f5) | Feb 24, 2022 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [cfb97398c6](https://linux-hardware.org/?probe=cfb97398c6) | Feb 24, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [1c753ca45b](https://linux-hardware.org/?probe=1c753ca45b) | Feb 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [ff0c4fc3a1](https://linux-hardware.org/?probe=ff0c4fc3a1) | Feb 24, 2022 |
| Unknown       | Unknown                     | Desktop     | [604009e029](https://linux-hardware.org/?probe=604009e029) | Feb 24, 2022 |
| HP            | 84DE                        | All in one  | [43184fd6bf](https://linux-hardware.org/?probe=43184fd6bf) | Feb 23, 2022 |
| Lenovo        | ThinkPad T500 2056Y2Z       | Notebook    | [fcf18af227](https://linux-hardware.org/?probe=fcf18af227) | Feb 23, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [db8b03c5b3](https://linux-hardware.org/?probe=db8b03c5b3) | Feb 23, 2022 |
| Acer          | Extensa 5620                | Notebook    | [d814497f9a](https://linux-hardware.org/?probe=d814497f9a) | Feb 23, 2022 |
| Lenovo        | IdeaPad S10-2 20027         | Notebook    | [35ffcaed33](https://linux-hardware.org/?probe=35ffcaed33) | Feb 23, 2022 |
| Lenovo        | ThinkPad T420 42367A4       | Notebook    | [8a65b38196](https://linux-hardware.org/?probe=8a65b38196) | Feb 23, 2022 |
| Apple         | MacBookAir2,1               | Notebook    | [70a8d35e9e](https://linux-hardware.org/?probe=70a8d35e9e) | Feb 23, 2022 |
| Packard Be... | DOT S                       | Notebook    | [337bbf93b3](https://linux-hardware.org/?probe=337bbf93b3) | Feb 23, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [30a18704d2](https://linux-hardware.org/?probe=30a18704d2) | Feb 23, 2022 |
| ASUSTek       | X55A                        | Notebook    | [2549eae4a5](https://linux-hardware.org/?probe=2549eae4a5) | Feb 23, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [6cbbd9a058](https://linux-hardware.org/?probe=6cbbd9a058) | Feb 23, 2022 |
| Acer          | Aspire M1470                | Desktop     | [1bbfd129de](https://linux-hardware.org/?probe=1bbfd129de) | Feb 23, 2022 |
| eMachines     | E725                        | Notebook    | [312a83e700](https://linux-hardware.org/?probe=312a83e700) | Feb 23, 2022 |
| Sony          | SVE1412E1RW                 | Notebook    | [3e0ba8aacd](https://linux-hardware.org/?probe=3e0ba8aacd) | Feb 23, 2022 |
| HP            | ProBook 4520s               | Notebook    | [c60e1c19e1](https://linux-hardware.org/?probe=c60e1c19e1) | Feb 23, 2022 |
| Dell          | Latitude E5520              | Notebook    | [323ea2506d](https://linux-hardware.org/?probe=323ea2506d) | Feb 23, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [2dc15462eb](https://linux-hardware.org/?probe=2dc15462eb) | Feb 23, 2022 |
| Samsung       | N150/N210/N220              | Notebook    | [c0ce4da770](https://linux-hardware.org/?probe=c0ce4da770) | Feb 22, 2022 |
| ASUSTek       | P5P800-VM                   | Desktop     | [134186f7a6](https://linux-hardware.org/?probe=134186f7a6) | Feb 22, 2022 |
| Acer          | Aspire M1470                | Desktop     | [216efdea1e](https://linux-hardware.org/?probe=216efdea1e) | Feb 22, 2022 |
| Lenovo        | ThinkCentre M90p 5485AG8    | Desktop     | [413a69681a](https://linux-hardware.org/?probe=413a69681a) | Feb 22, 2022 |
| Intel         | HuronRiver Platform         | Notebook    | [a2763becf2](https://linux-hardware.org/?probe=a2763becf2) | Feb 22, 2022 |
| Lenovo        | 3130 NOK                    | Mini pc     | [cc222d78b9](https://linux-hardware.org/?probe=cc222d78b9) | Feb 22, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e5706d5397](https://linux-hardware.org/?probe=e5706d5397) | Feb 22, 2022 |
| Pegatron      | 2A99                        | Desktop     | [f6351515fa](https://linux-hardware.org/?probe=f6351515fa) | Feb 22, 2022 |
| eMachines     | eM250                       | Notebook    | [ebd724598b](https://linux-hardware.org/?probe=ebd724598b) | Feb 21, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [035b0766cc](https://linux-hardware.org/?probe=035b0766cc) | Feb 21, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [4c10662fd3](https://linux-hardware.org/?probe=4c10662fd3) | Feb 21, 2022 |
| Gigabyte      | E2500N                      | Desktop     | [ca6fbcaf48](https://linux-hardware.org/?probe=ca6fbcaf48) | Feb 21, 2022 |
| ASUSTek       | Leonite2                    | Desktop     | [a90bf8db74](https://linux-hardware.org/?probe=a90bf8db74) | Feb 21, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [c98a25e545](https://linux-hardware.org/?probe=c98a25e545) | Feb 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [aabaad1b1e](https://linux-hardware.org/?probe=aabaad1b1e) | Feb 20, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [90a12c2aa1](https://linux-hardware.org/?probe=90a12c2aa1) | Feb 20, 2022 |
| ASUSTek       | U24E                        | Notebook    | [c11b6b6a56](https://linux-hardware.org/?probe=c11b6b6a56) | Feb 20, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [2164cfa14f](https://linux-hardware.org/?probe=2164cfa14f) | Feb 20, 2022 |
| Lenovo        | E43                         | Notebook    | [4af9ba3590](https://linux-hardware.org/?probe=4af9ba3590) | Feb 20, 2022 |
| Acer          | Aspire ES1-522              | Notebook    | [51b531d8e7](https://linux-hardware.org/?probe=51b531d8e7) | Feb 20, 2022 |
| ASUSTek       | X45U                        | Notebook    | [41f11e9487](https://linux-hardware.org/?probe=41f11e9487) | Feb 20, 2022 |
| MSI           | H55M-P31                    | Desktop     | [f87bc52ff4](https://linux-hardware.org/?probe=f87bc52ff4) | Feb 20, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [f20c485a7b](https://linux-hardware.org/?probe=f20c485a7b) | Feb 20, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [4482b4bb18](https://linux-hardware.org/?probe=4482b4bb18) | Feb 20, 2022 |
| ASUSTek       | N76VZ                       | Notebook    | [2f54a2ead3](https://linux-hardware.org/?probe=2f54a2ead3) | Feb 19, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [263d909f47](https://linux-hardware.org/?probe=263d909f47) | Feb 19, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [fde5d3aa86](https://linux-hardware.org/?probe=fde5d3aa86) | Feb 19, 2022 |
| ASUSTek       | TP401CA                     | Convertible | [47c03e4dee](https://linux-hardware.org/?probe=47c03e4dee) | Feb 19, 2022 |
| Intel         | D945GCLF2 AAE46416-101      | Desktop     | [4f5fc5f5da](https://linux-hardware.org/?probe=4f5fc5f5da) | Feb 19, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [8233027724](https://linux-hardware.org/?probe=8233027724) | Feb 19, 2022 |
| HP            | Pavilion dv6                | Notebook    | [5c76391813](https://linux-hardware.org/?probe=5c76391813) | Feb 19, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [124b030ac3](https://linux-hardware.org/?probe=124b030ac3) | Feb 19, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [018ca406e2](https://linux-hardware.org/?probe=018ca406e2) | Feb 19, 2022 |
| MSI           | 970A-G43 PLUS               | Desktop     | [c3c6ed6429](https://linux-hardware.org/?probe=c3c6ed6429) | Feb 19, 2022 |
| Medion        | P7612                       | Notebook    | [7a8dc95cc8](https://linux-hardware.org/?probe=7a8dc95cc8) | Feb 18, 2022 |
| MSI           | PH61-P33                    | Desktop     | [1bddbbedba](https://linux-hardware.org/?probe=1bddbbedba) | Feb 18, 2022 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [f5b5daa4cb](https://linux-hardware.org/?probe=f5b5daa4cb) | Feb 18, 2022 |
| Gigabyte      | GA-MA78G-DS3H               | Desktop     | [d799c9b2f2](https://linux-hardware.org/?probe=d799c9b2f2) | Feb 18, 2022 |
| MSI           | X370 GAMING PLUS            | Desktop     | [63a5e1d0ad](https://linux-hardware.org/?probe=63a5e1d0ad) | Feb 18, 2022 |
| Huanan        | X99 F8D V2.2                | Desktop     | [b024b95162](https://linux-hardware.org/?probe=b024b95162) | Feb 18, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [ed8a6eb12f](https://linux-hardware.org/?probe=ed8a6eb12f) | Feb 17, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [866eb72e69](https://linux-hardware.org/?probe=866eb72e69) | Feb 17, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [b32ffb9adc](https://linux-hardware.org/?probe=b32ffb9adc) | Feb 17, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [ac7c6763e3](https://linux-hardware.org/?probe=ac7c6763e3) | Feb 17, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [e3f921b6a5](https://linux-hardware.org/?probe=e3f921b6a5) | Feb 17, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [7652292ba2](https://linux-hardware.org/?probe=7652292ba2) | Feb 17, 2022 |
| Dell          | 0FXD80 A00                  | Desktop     | [46450d22d3](https://linux-hardware.org/?probe=46450d22d3) | Feb 17, 2022 |
| HP            | 255 G4                      | Notebook    | [52e97dffc1](https://linux-hardware.org/?probe=52e97dffc1) | Feb 17, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [86257153d8](https://linux-hardware.org/?probe=86257153d8) | Feb 17, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [1b648c8fc9](https://linux-hardware.org/?probe=1b648c8fc9) | Feb 16, 2022 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [b9aeffa5f3](https://linux-hardware.org/?probe=b9aeffa5f3) | Feb 16, 2022 |
| Notebook      | W54_W94_W955TU,-T,-C        | Notebook    | [6228810562](https://linux-hardware.org/?probe=6228810562) | Feb 16, 2022 |
| ASRock        | G31M-GS                     | Desktop     | [8968aa239b](https://linux-hardware.org/?probe=8968aa239b) | Feb 16, 2022 |
| ASUSTek       | 1005PXD                     | Notebook    | [b454702c84](https://linux-hardware.org/?probe=b454702c84) | Feb 16, 2022 |
| HP            | ENVY dv7                    | Notebook    | [64d7869867](https://linux-hardware.org/?probe=64d7869867) | Feb 16, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [e5e7379587](https://linux-hardware.org/?probe=e5e7379587) | Feb 16, 2022 |
| ASUSTek       | F2A55-M LK                  | Desktop     | [131de7d020](https://linux-hardware.org/?probe=131de7d020) | Feb 15, 2022 |
| iRU           | J231                        | All in one  | [8259fb58ce](https://linux-hardware.org/?probe=8259fb58ce) | Feb 15, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [28c2882750](https://linux-hardware.org/?probe=28c2882750) | Feb 15, 2022 |
| ASUSTek       | V221ID                      | All in one  | [ef42b78dc5](https://linux-hardware.org/?probe=ef42b78dc5) | Feb 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [e8455d8225](https://linux-hardware.org/?probe=e8455d8225) | Feb 15, 2022 |
| ECS           | A740GM-M                    | Desktop     | [f8ac8fed60](https://linux-hardware.org/?probe=f8ac8fed60) | Feb 15, 2022 |
| BESSTAR Te... | UM270 V1.0                  | Desktop     | [a2ee2f6a38](https://linux-hardware.org/?probe=a2ee2f6a38) | Feb 15, 2022 |
| ASUSTek       | M4A785T-M                   | Desktop     | [f5e313fff6](https://linux-hardware.org/?probe=f5e313fff6) | Feb 14, 2022 |
| Fujitsu Si... | LIFEBOOK S7110              | Notebook    | [e9fdc5bbc4](https://linux-hardware.org/?probe=e9fdc5bbc4) | Feb 14, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [40f0863805](https://linux-hardware.org/?probe=40f0863805) | Feb 14, 2022 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [4fb06cfe97](https://linux-hardware.org/?probe=4fb06cfe97) | Feb 14, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [13989d56ec](https://linux-hardware.org/?probe=13989d56ec) | Feb 14, 2022 |
| ASUSTek       | P5E-VM SE                   | Desktop     | [bfadfad800](https://linux-hardware.org/?probe=bfadfad800) | Feb 14, 2022 |
| ASUSTek       | M2NPV-VM                    | Desktop     | [1c60918a3d](https://linux-hardware.org/?probe=1c60918a3d) | Feb 14, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [2effd1e9c6](https://linux-hardware.org/?probe=2effd1e9c6) | Feb 14, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [ca29e05afe](https://linux-hardware.org/?probe=ca29e05afe) | Feb 14, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [fa19ca0049](https://linux-hardware.org/?probe=fa19ca0049) | Feb 14, 2022 |
| Dell          | Inspiron 3558               | Notebook    | [9a70b72ce5](https://linux-hardware.org/?probe=9a70b72ce5) | Feb 13, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [eb68a95d51](https://linux-hardware.org/?probe=eb68a95d51) | Feb 13, 2022 |
| ASUSTek       | 1011PX                      | Notebook    | [81437151b6](https://linux-hardware.org/?probe=81437151b6) | Feb 13, 2022 |
| ECS           | G41T-R3                     | Desktop     | [ad4ba21957](https://linux-hardware.org/?probe=ad4ba21957) | Feb 13, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [7a19abc29f](https://linux-hardware.org/?probe=7a19abc29f) | Feb 13, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [92eab3e301](https://linux-hardware.org/?probe=92eab3e301) | Feb 13, 2022 |
| HP            | G7000                       | Notebook    | [77d8f165c0](https://linux-hardware.org/?probe=77d8f165c0) | Feb 13, 2022 |
| Fujitsu       | CELSIUS H700                | Notebook    | [80008ebc38](https://linux-hardware.org/?probe=80008ebc38) | Feb 13, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [39b082fe06](https://linux-hardware.org/?probe=39b082fe06) | Feb 13, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [085add9a8c](https://linux-hardware.org/?probe=085add9a8c) | Feb 13, 2022 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [ab412a55d6](https://linux-hardware.org/?probe=ab412a55d6) | Feb 13, 2022 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [cebe791ff7](https://linux-hardware.org/?probe=cebe791ff7) | Feb 13, 2022 |
| Gigabyte      | H510M S2H V2                | Desktop     | [25ae1cdef0](https://linux-hardware.org/?probe=25ae1cdef0) | Feb 13, 2022 |
| Dell          | 0Y5DDC A00                  | Desktop     | [c970d00ddd](https://linux-hardware.org/?probe=c970d00ddd) | Feb 12, 2022 |
| ASUSTek       | P5K                         | Desktop     | [b6d1577be5](https://linux-hardware.org/?probe=b6d1577be5) | Feb 12, 2022 |
| HP            | Pavilion 15                 | Notebook    | [01960d4a72](https://linux-hardware.org/?probe=01960d4a72) | Feb 12, 2022 |
| Dell          | Vostro 5490                 | Notebook    | [39e19c2b14](https://linux-hardware.org/?probe=39e19c2b14) | Feb 12, 2022 |
| Acer          | Extensa 2511G               | Notebook    | [c1cd812a42](https://linux-hardware.org/?probe=c1cd812a42) | Feb 12, 2022 |
| Dell          | Latitude E5420              | Notebook    | [f016e9f3ad](https://linux-hardware.org/?probe=f016e9f3ad) | Feb 12, 2022 |
| Dell          | Latitude E5420              | Notebook    | [8843a735a0](https://linux-hardware.org/?probe=8843a735a0) | Feb 12, 2022 |
| HP            | 09F8h                       | Desktop     | [a3d99bd1ad](https://linux-hardware.org/?probe=a3d99bd1ad) | Feb 12, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [2c41d85640](https://linux-hardware.org/?probe=2c41d85640) | Feb 12, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [d1aaa12f3c](https://linux-hardware.org/?probe=d1aaa12f3c) | Feb 12, 2022 |
| ASRock        | P43DE3                      | Desktop     | [a90b00597e](https://linux-hardware.org/?probe=a90b00597e) | Feb 12, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [469a5d773b](https://linux-hardware.org/?probe=469a5d773b) | Feb 12, 2022 |
| Pegatron      | E60                         | Desktop     | [ea6a720ebf](https://linux-hardware.org/?probe=ea6a720ebf) | Feb 11, 2022 |
| Pegatron      | E60                         | Desktop     | [cb064b517f](https://linux-hardware.org/?probe=cb064b517f) | Feb 11, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [a814e7ba37](https://linux-hardware.org/?probe=a814e7ba37) | Feb 11, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [c8ff899a05](https://linux-hardware.org/?probe=c8ff899a05) | Feb 11, 2022 |
| Lenovo        | ThinkPad SL410 2842RN9      | Notebook    | [c0180c17d9](https://linux-hardware.org/?probe=c0180c17d9) | Feb 11, 2022 |
| ASUSTek       | N61Vn                       | Notebook    | [a933b77b15](https://linux-hardware.org/?probe=a933b77b15) | Feb 11, 2022 |
| MSI           | GP60 2OD                    | Notebook    | [dce2436e3a](https://linux-hardware.org/?probe=dce2436e3a) | Feb 11, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [3055523150](https://linux-hardware.org/?probe=3055523150) | Feb 11, 2022 |
| ASUSTek       | A58M-K                      | Desktop     | [340256ddb2](https://linux-hardware.org/?probe=340256ddb2) | Feb 10, 2022 |
| ASUSTek       | PRO H410M-C                 | Desktop     | [e0619a1fd7](https://linux-hardware.org/?probe=e0619a1fd7) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [3fe8db326e](https://linux-hardware.org/?probe=3fe8db326e) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [b6494cc86c](https://linux-hardware.org/?probe=b6494cc86c) | Feb 10, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [c010a2df07](https://linux-hardware.org/?probe=c010a2df07) | Feb 10, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [40808dc413](https://linux-hardware.org/?probe=40808dc413) | Feb 08, 2022 |
| ASRock        | H55M-LE                     | Desktop     | [4d4434a1ae](https://linux-hardware.org/?probe=4d4434a1ae) | Feb 08, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [d0e07d420c](https://linux-hardware.org/?probe=d0e07d420c) | Feb 08, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [d0e38ff5e5](https://linux-hardware.org/?probe=d0e38ff5e5) | Feb 08, 2022 |
| HP            | Pavilion g6                 | Notebook    | [ea7fe617bc](https://linux-hardware.org/?probe=ea7fe617bc) | Feb 08, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [0600816ba9](https://linux-hardware.org/?probe=0600816ba9) | Feb 08, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [4b6abf8148](https://linux-hardware.org/?probe=4b6abf8148) | Feb 08, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [7c09c25b46](https://linux-hardware.org/?probe=7c09c25b46) | Feb 08, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [5b8ad7499b](https://linux-hardware.org/?probe=5b8ad7499b) | Feb 07, 2022 |
| ASUSTek       | AM1I-A                      | Desktop     | [5f6867fad7](https://linux-hardware.org/?probe=5f6867fad7) | Feb 07, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [2e1512ed5d](https://linux-hardware.org/?probe=2e1512ed5d) | Feb 07, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [b1d68da487](https://linux-hardware.org/?probe=b1d68da487) | Feb 07, 2022 |
| Notebook      | WA50SRQ                     | Notebook    | [d7188c65fe](https://linux-hardware.org/?probe=d7188c65fe) | Feb 07, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [3aa5fa2d91](https://linux-hardware.org/?probe=3aa5fa2d91) | Feb 06, 2022 |
| Chuwi         | Hero Book                   | Notebook    | [b5dbc15bbf](https://linux-hardware.org/?probe=b5dbc15bbf) | Feb 06, 2022 |
| Foxconn       | M61PMV FAB A1               | Desktop     | [1a31d1ca9f](https://linux-hardware.org/?probe=1a31d1ca9f) | Feb 06, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [1d55b1f711](https://linux-hardware.org/?probe=1d55b1f711) | Feb 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [fcff45ddb4](https://linux-hardware.org/?probe=fcff45ddb4) | Feb 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [b75541868b](https://linux-hardware.org/?probe=b75541868b) | Feb 06, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [b9e58087b7](https://linux-hardware.org/?probe=b9e58087b7) | Feb 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a41632fc91](https://linux-hardware.org/?probe=a41632fc91) | Feb 05, 2022 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [cced3f9eec](https://linux-hardware.org/?probe=cced3f9eec) | Feb 05, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [0b905c31b5](https://linux-hardware.org/?probe=0b905c31b5) | Feb 05, 2022 |
| Gigabyte      | P35-DS3R                    | Desktop     | [3164a5ed5b](https://linux-hardware.org/?probe=3164a5ed5b) | Feb 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [9d6680df17](https://linux-hardware.org/?probe=9d6680df17) | Feb 05, 2022 |
| Lenovo        | IdeaPad S110 20126          | Notebook    | [b7ae05b6a1](https://linux-hardware.org/?probe=b7ae05b6a1) | Feb 05, 2022 |
| Acer          | Extensa 2519                | Notebook    | [6ac9948350](https://linux-hardware.org/?probe=6ac9948350) | Feb 05, 2022 |
| Acer          | Aspire 5610                 | Notebook    | [fb5b6d4c90](https://linux-hardware.org/?probe=fb5b6d4c90) | Feb 05, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [731f4c84e6](https://linux-hardware.org/?probe=731f4c84e6) | Feb 05, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [b3ba3d3112](https://linux-hardware.org/?probe=b3ba3d3112) | Feb 04, 2022 |
| HP            | Mini 110-3500               | Notebook    | [c64c9ca5ce](https://linux-hardware.org/?probe=c64c9ca5ce) | Feb 04, 2022 |
| Samsung       | R40/R41                     | Notebook    | [b53c8e5ef4](https://linux-hardware.org/?probe=b53c8e5ef4) | Feb 04, 2022 |
| ASUSTek       | P5P41D                      | Desktop     | [d7264306f6](https://linux-hardware.org/?probe=d7264306f6) | Feb 04, 2022 |
| Gigabyte      | H81M-HD3                    | Desktop     | [d554447e6b](https://linux-hardware.org/?probe=d554447e6b) | Feb 04, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [fa05c49b58](https://linux-hardware.org/?probe=fa05c49b58) | Feb 04, 2022 |
| Samsung       | QX310/QX410/QX510/SF310/... | Notebook    | [adb5d9b8b9](https://linux-hardware.org/?probe=adb5d9b8b9) | Feb 04, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [075f4c7c9d](https://linux-hardware.org/?probe=075f4c7c9d) | Feb 03, 2022 |
| Acer          | AOA110                      | Notebook    | [3290f1de93](https://linux-hardware.org/?probe=3290f1de93) | Feb 02, 2022 |
| ASUSTek       | P5L1394                     | Desktop     | [4969e4fecb](https://linux-hardware.org/?probe=4969e4fecb) | Feb 02, 2022 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [8b92af27e3](https://linux-hardware.org/?probe=8b92af27e3) | Feb 02, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [edcd28a541](https://linux-hardware.org/?probe=edcd28a541) | Feb 02, 2022 |
| Pegatron      | 2A73h                       | Desktop     | [b31d0806f5](https://linux-hardware.org/?probe=b31d0806f5) | Feb 02, 2022 |
| ASUSTek       | PRIME B460M-A R2.0          | Desktop     | [bb7c4c5854](https://linux-hardware.org/?probe=bb7c4c5854) | Feb 02, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [824ae3f413](https://linux-hardware.org/?probe=824ae3f413) | Feb 02, 2022 |
| Dell          | 0200DY A00                  | Desktop     | [e5f15a17d5](https://linux-hardware.org/?probe=e5f15a17d5) | Feb 02, 2022 |
| Toshiba       | Satellite C850-C3K          | Notebook    | [9b7c25ddbc](https://linux-hardware.org/?probe=9b7c25ddbc) | Feb 02, 2022 |
| HP            | Compaq Presario CQ71        | Notebook    | [436407f045](https://linux-hardware.org/?probe=436407f045) | Feb 01, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [443b05e506](https://linux-hardware.org/?probe=443b05e506) | Feb 01, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [5d4dc0566d](https://linux-hardware.org/?probe=5d4dc0566d) | Feb 01, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d3a9e62b95](https://linux-hardware.org/?probe=d3a9e62b95) | Feb 01, 2022 |
| Biostar       | NF560-A2G                   | Desktop     | [49802d698d](https://linux-hardware.org/?probe=49802d698d) | Feb 01, 2022 |
| Lenovo        | IdeaPad Z470                | Notebook    | [63443cfe31](https://linux-hardware.org/?probe=63443cfe31) | Feb 01, 2022 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [6ab247def8](https://linux-hardware.org/?probe=6ab247def8) | Feb 01, 2022 |
| Dell          | 0MN1TX A02                  | Desktop     | [c22ec93e89](https://linux-hardware.org/?probe=c22ec93e89) | Feb 01, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [8fba4698c9](https://linux-hardware.org/?probe=8fba4698c9) | Feb 01, 2022 |
| ASUSTek       | N60Dp                       | Notebook    | [2ddb4635f8](https://linux-hardware.org/?probe=2ddb4635f8) | Jan 31, 2022 |
| Huanan        | X99-BD4 V1.31               | Desktop     | [a0bdb67b8a](https://linux-hardware.org/?probe=a0bdb67b8a) | Jan 31, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [53ea0036b1](https://linux-hardware.org/?probe=53ea0036b1) | Jan 31, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [2609297f16](https://linux-hardware.org/?probe=2609297f16) | Jan 31, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [1e1667b837](https://linux-hardware.org/?probe=1e1667b837) | Jan 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [662c007223](https://linux-hardware.org/?probe=662c007223) | Jan 31, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [a66c49ed35](https://linux-hardware.org/?probe=a66c49ed35) | Jan 31, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [c9af7240b9](https://linux-hardware.org/?probe=c9af7240b9) | Jan 31, 2022 |
| Clevo         | W240EL/W250ELQ/W270ELQ      | Notebook    | [8ca99b238c](https://linux-hardware.org/?probe=8ca99b238c) | Jan 30, 2022 |
| Unknown       | Unknown                     | Desktop     | [07e2f38566](https://linux-hardware.org/?probe=07e2f38566) | Jan 30, 2022 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [5d3328d8a8](https://linux-hardware.org/?probe=5d3328d8a8) | Jan 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [50fae55964](https://linux-hardware.org/?probe=50fae55964) | Jan 30, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [5f679efaa1](https://linux-hardware.org/?probe=5f679efaa1) | Jan 30, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [5f6a8cf57f](https://linux-hardware.org/?probe=5f6a8cf57f) | Jan 29, 2022 |
| Fujitsu       | D2812-A2 S26361-D2812-A2    | Desktop     | [9ff78b6d13](https://linux-hardware.org/?probe=9ff78b6d13) | Jan 29, 2022 |
| EVOO          | EVC156-1                    | Notebook    | [d6818d7d1d](https://linux-hardware.org/?probe=d6818d7d1d) | Jan 28, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [d2acef09e9](https://linux-hardware.org/?probe=d2acef09e9) | Jan 28, 2022 |
| Acer          | TravelMate B118-M           | Notebook    | [649bc8e7c0](https://linux-hardware.org/?probe=649bc8e7c0) | Jan 28, 2022 |
| Dell          | 0M9KCM A00                  | Desktop     | [8ce5fcb03f](https://linux-hardware.org/?probe=8ce5fcb03f) | Jan 27, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [ae15cd3df6](https://linux-hardware.org/?probe=ae15cd3df6) | Jan 27, 2022 |
| ASUSTek       | F5SL                        | Notebook    | [5c64f7d8d6](https://linux-hardware.org/?probe=5c64f7d8d6) | Jan 27, 2022 |
| Acer          | Extensa 215-32              | Notebook    | [7eae690bd4](https://linux-hardware.org/?probe=7eae690bd4) | Jan 27, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [742b413a15](https://linux-hardware.org/?probe=742b413a15) | Jan 27, 2022 |
| HP            | Presario CQ57               | Notebook    | [6a8428a112](https://linux-hardware.org/?probe=6a8428a112) | Jan 27, 2022 |
| ECS           | G31T-M7                     | Desktop     | [7c1b175bd1](https://linux-hardware.org/?probe=7c1b175bd1) | Jan 27, 2022 |
| HP            | ProBook 6560b               | Notebook    | [e61fbcfd64](https://linux-hardware.org/?probe=e61fbcfd64) | Jan 27, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [f34ec65c4f](https://linux-hardware.org/?probe=f34ec65c4f) | Jan 27, 2022 |
| ASRock        | Z270M Pro4                  | Desktop     | [dcd0c78f98](https://linux-hardware.org/?probe=dcd0c78f98) | Jan 27, 2022 |
| ASUSTek       | Leonite2                    | Desktop     | [c63a40538a](https://linux-hardware.org/?probe=c63a40538a) | Jan 27, 2022 |
| MSI           | 870-C45                     | Desktop     | [7234642cde](https://linux-hardware.org/?probe=7234642cde) | Jan 26, 2022 |
| HP            | Pavilion g6                 | Notebook    | [0030f5a26d](https://linux-hardware.org/?probe=0030f5a26d) | Jan 26, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [934ebdf176](https://linux-hardware.org/?probe=934ebdf176) | Jan 26, 2022 |
| EVOO          | EVC156-1                    | Notebook    | [6b5bb91221](https://linux-hardware.org/?probe=6b5bb91221) | Jan 26, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [0771453742](https://linux-hardware.org/?probe=0771453742) | Jan 25, 2022 |
| ASUSTek       | Z77-A                       | Desktop     | [310162f4cd](https://linux-hardware.org/?probe=310162f4cd) | Jan 25, 2022 |
| Acer          | Aspire TC-391               | Desktop     | [bf81a4069a](https://linux-hardware.org/?probe=bf81a4069a) | Jan 25, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [4235bc9196](https://linux-hardware.org/?probe=4235bc9196) | Jan 24, 2022 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [826facb133](https://linux-hardware.org/?probe=826facb133) | Jan 24, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [aff3eafa53](https://linux-hardware.org/?probe=aff3eafa53) | Jan 24, 2022 |
| Intel         | NUC7i3DNB J57625-508        | Mini pc     | [0261508ba5](https://linux-hardware.org/?probe=0261508ba5) | Jan 24, 2022 |
| ASRock        | A320M-DVS R3.0              | Desktop     | [e84d3eedbc](https://linux-hardware.org/?probe=e84d3eedbc) | Jan 23, 2022 |
| Irbis         | NB248                       | Notebook    | [3dce59fcf8](https://linux-hardware.org/?probe=3dce59fcf8) | Jan 23, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [41f8a4a3fb](https://linux-hardware.org/?probe=41f8a4a3fb) | Jan 23, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [6728b7369a](https://linux-hardware.org/?probe=6728b7369a) | Jan 23, 2022 |
| Medion        | BTDD-EAIO                   | All in one  | [19e17713b3](https://linux-hardware.org/?probe=19e17713b3) | Jan 22, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [f15cbbcef7](https://linux-hardware.org/?probe=f15cbbcef7) | Jan 22, 2022 |
| ASUSTek       | AM1I-A                      | Desktop     | [3928ad3bfc](https://linux-hardware.org/?probe=3928ad3bfc) | Jan 22, 2022 |
| ASUSTek       | AM1I-A                      | Desktop     | [fc51118bc1](https://linux-hardware.org/?probe=fc51118bc1) | Jan 22, 2022 |
| HP            | Pavilion dv6                | Notebook    | [6ff7329a99](https://linux-hardware.org/?probe=6ff7329a99) | Jan 22, 2022 |
| ASUSTek       | K42Jc                       | Notebook    | [a6a5772c7f](https://linux-hardware.org/?probe=a6a5772c7f) | Jan 22, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [0206126edb](https://linux-hardware.org/?probe=0206126edb) | Jan 22, 2022 |
| Intel         | DG35EC AAE29266-203         | Desktop     | [de1f1438cb](https://linux-hardware.org/?probe=de1f1438cb) | Jan 22, 2022 |
| Toshiba       | Satellite L670D             | Notebook    | [51fb2a4a10](https://linux-hardware.org/?probe=51fb2a4a10) | Jan 22, 2022 |
| ASRock        | Z87 Killer                  | Desktop     | [0be767a418](https://linux-hardware.org/?probe=0be767a418) | Jan 22, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [8fd6a325ec](https://linux-hardware.org/?probe=8fd6a325ec) | Jan 21, 2022 |
| Intel         | DG35EC AAE29266-203         | Desktop     | [11f6273e6d](https://linux-hardware.org/?probe=11f6273e6d) | Jan 21, 2022 |
| Acer          | AOD260                      | Notebook    | [f6f4250ae1](https://linux-hardware.org/?probe=f6f4250ae1) | Jan 21, 2022 |
| MSI           | H410M PRO-VH                | Desktop     | [3f64c5903b](https://linux-hardware.org/?probe=3f64c5903b) | Jan 21, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [ba082175be](https://linux-hardware.org/?probe=ba082175be) | Jan 21, 2022 |
| Medion        | BTDD-EAIO                   | All in one  | [acee4deb32](https://linux-hardware.org/?probe=acee4deb32) | Jan 21, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [ed04c0200e](https://linux-hardware.org/?probe=ed04c0200e) | Jan 20, 2022 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [a97bcb6c80](https://linux-hardware.org/?probe=a97bcb6c80) | Jan 20, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [d787ff9850](https://linux-hardware.org/?probe=d787ff9850) | Jan 20, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [62117934f0](https://linux-hardware.org/?probe=62117934f0) | Jan 20, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [f0c1dbbf81](https://linux-hardware.org/?probe=f0c1dbbf81) | Jan 20, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [bcd74bd272](https://linux-hardware.org/?probe=bcd74bd272) | Jan 20, 2022 |
| ASUSTek       | U31SD                       | Notebook    | [40dfca6e1b](https://linux-hardware.org/?probe=40dfca6e1b) | Jan 20, 2022 |
| ASUSTek       | H81M-C                      | Desktop     | [0b7b3544b2](https://linux-hardware.org/?probe=0b7b3544b2) | Jan 20, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [d63cfb2c70](https://linux-hardware.org/?probe=d63cfb2c70) | Jan 20, 2022 |
| Supermicro    | C7Q67 V1.01                 | Desktop     | [0160b3ff00](https://linux-hardware.org/?probe=0160b3ff00) | Jan 20, 2022 |
| ASUSTek       | X201EP                      | Notebook    | [5bac2a4ba7](https://linux-hardware.org/?probe=5bac2a4ba7) | Jan 20, 2022 |
| ASUSTek       | F5Z                         | Notebook    | [a329bd2dfc](https://linux-hardware.org/?probe=a329bd2dfc) | Jan 19, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [dc5f20ce86](https://linux-hardware.org/?probe=dc5f20ce86) | Jan 19, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [d4e8219651](https://linux-hardware.org/?probe=d4e8219651) | Jan 19, 2022 |
| Acer          | eMachine V1.45              | Notebook    | [3ac730a19e](https://linux-hardware.org/?probe=3ac730a19e) | Jan 19, 2022 |
| Shuttle       | DS68U                       | Notebook    | [5ac4aed9d9](https://linux-hardware.org/?probe=5ac4aed9d9) | Jan 19, 2022 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [b8829db8e1](https://linux-hardware.org/?probe=b8829db8e1) | Jan 19, 2022 |
| ASUSTek       | Q170T                       | Desktop     | [5712025f97](https://linux-hardware.org/?probe=5712025f97) | Jan 19, 2022 |
| Lenovo        | ThinkCentre Edge71 1583C... | Desktop     | [8f1ed70aa6](https://linux-hardware.org/?probe=8f1ed70aa6) | Jan 19, 2022 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [722709c052](https://linux-hardware.org/?probe=722709c052) | Jan 19, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [fca800793f](https://linux-hardware.org/?probe=fca800793f) | Jan 18, 2022 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [96b920990c](https://linux-hardware.org/?probe=96b920990c) | Jan 18, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [bfb8f77808](https://linux-hardware.org/?probe=bfb8f77808) | Jan 18, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [0cf59407cd](https://linux-hardware.org/?probe=0cf59407cd) | Jan 17, 2022 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [4f313ddd6a](https://linux-hardware.org/?probe=4f313ddd6a) | Jan 17, 2022 |
| ASRock        | Z87 Killer                  | Desktop     | [6931f1ca2f](https://linux-hardware.org/?probe=6931f1ca2f) | Jan 17, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [c69ec5ad5b](https://linux-hardware.org/?probe=c69ec5ad5b) | Jan 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2e60d849ec](https://linux-hardware.org/?probe=2e60d849ec) | Jan 16, 2022 |
| ASUSTek       | J1800I-C                    | Desktop     | [17e652ed06](https://linux-hardware.org/?probe=17e652ed06) | Jan 16, 2022 |
| HP            | 09F8h                       | Desktop     | [9c088ae8dc](https://linux-hardware.org/?probe=9c088ae8dc) | Jan 16, 2022 |
| HP            | 09F8h                       | Desktop     | [a3769a7ca0](https://linux-hardware.org/?probe=a3769a7ca0) | Jan 16, 2022 |
| ASRock        | P43DE3                      | Desktop     | [40ef64d720](https://linux-hardware.org/?probe=40ef64d720) | Jan 16, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [5d6c02a6e1](https://linux-hardware.org/?probe=5d6c02a6e1) | Jan 16, 2022 |
| Lenovo        | B50-70 20384                | Notebook    | [a72e344e07](https://linux-hardware.org/?probe=a72e344e07) | Jan 16, 2022 |
| Toshiba       | Satellite A300              | Notebook    | [c3f3665555](https://linux-hardware.org/?probe=c3f3665555) | Jan 16, 2022 |
| Gigabyte      | P31-DS3L                    | Desktop     | [7d922415df](https://linux-hardware.org/?probe=7d922415df) | Jan 16, 2022 |
| ASRock        | 760GM-S3                    | Desktop     | [effb341d7c](https://linux-hardware.org/?probe=effb341d7c) | Jan 16, 2022 |
| Gigabyte      | P31-DS3L                    | Desktop     | [856f1716c9](https://linux-hardware.org/?probe=856f1716c9) | Jan 16, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [7fd773a8f9](https://linux-hardware.org/?probe=7fd773a8f9) | Jan 15, 2022 |
| ASUSTek       | Q170T                       | Desktop     | [6538d8f8be](https://linux-hardware.org/?probe=6538d8f8be) | Jan 15, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [d3bf3d7ad7](https://linux-hardware.org/?probe=d3bf3d7ad7) | Jan 15, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [290161508a](https://linux-hardware.org/?probe=290161508a) | Jan 15, 2022 |
| Acer          | TravelMate B118-M           | Notebook    | [49fb79c000](https://linux-hardware.org/?probe=49fb79c000) | Jan 15, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [8e0e9f89bd](https://linux-hardware.org/?probe=8e0e9f89bd) | Jan 15, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [a0f722b3aa](https://linux-hardware.org/?probe=a0f722b3aa) | Jan 14, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [d06eaa03f6](https://linux-hardware.org/?probe=d06eaa03f6) | Jan 14, 2022 |
| ASRock        | G31M-VS                     | Desktop     | [d456869dd7](https://linux-hardware.org/?probe=d456869dd7) | Jan 14, 2022 |
| Dell          | 0RY007                      | Desktop     | [7c76fda071](https://linux-hardware.org/?probe=7c76fda071) | Jan 14, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [291a3e234b](https://linux-hardware.org/?probe=291a3e234b) | Jan 14, 2022 |
| ASRock        | Z87 Killer                  | Desktop     | [268b4e1ed2](https://linux-hardware.org/?probe=268b4e1ed2) | Jan 14, 2022 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [6779dfb408](https://linux-hardware.org/?probe=6779dfb408) | Jan 14, 2022 |
| Gigabyte      | GA-78LMT-S2PV               | Desktop     | [69ba359c54](https://linux-hardware.org/?probe=69ba359c54) | Jan 13, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [2ee1f74170](https://linux-hardware.org/?probe=2ee1f74170) | Jan 13, 2022 |
| eMachines     | E625                        | Notebook    | [7ff6bcac68](https://linux-hardware.org/?probe=7ff6bcac68) | Jan 13, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [abd0e9203d](https://linux-hardware.org/?probe=abd0e9203d) | Jan 13, 2022 |
| HP            | Pavilion Laptop 15-cs2xx... | Notebook    | [b0fa30c056](https://linux-hardware.org/?probe=b0fa30c056) | Jan 13, 2022 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [e9207f1244](https://linux-hardware.org/?probe=e9207f1244) | Jan 13, 2022 |
| Dell          | Latitude E4300              | Notebook    | [0d0020f062](https://linux-hardware.org/?probe=0d0020f062) | Jan 12, 2022 |
| Acer          | TravelMate B118-M           | Notebook    | [950b54f965](https://linux-hardware.org/?probe=950b54f965) | Jan 12, 2022 |
| ASUSTek       | P5P41D                      | Desktop     | [fda05ec433](https://linux-hardware.org/?probe=fda05ec433) | Jan 12, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [9046bc1e4a](https://linux-hardware.org/?probe=9046bc1e4a) | Jan 11, 2022 |
| Gigabyte      | B450 GAMING X               | Desktop     | [4e745131e9](https://linux-hardware.org/?probe=4e745131e9) | Jan 11, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [a904228b9d](https://linux-hardware.org/?probe=a904228b9d) | Jan 11, 2022 |
| MSI           | MS-7430 0A                  | Desktop     | [fc801d2c87](https://linux-hardware.org/?probe=fc801d2c87) | Jan 10, 2022 |
| HP            | ProBook 5310m               | Notebook    | [e3c8188e1e](https://linux-hardware.org/?probe=e3c8188e1e) | Jan 10, 2022 |
| Gigabyte      | G41MT-USB3                  | Desktop     | [e68dfeaed6](https://linux-hardware.org/?probe=e68dfeaed6) | Jan 10, 2022 |
| Acer          | Aspire V5-572G              | Notebook    | [9257745e1c](https://linux-hardware.org/?probe=9257745e1c) | Jan 10, 2022 |
| ASUSTek       | P5Q SE2                     | Desktop     | [2ac94caa52](https://linux-hardware.org/?probe=2ac94caa52) | Jan 10, 2022 |
| MSI           | 870-C45                     | Desktop     | [c93f681412](https://linux-hardware.org/?probe=c93f681412) | Jan 09, 2022 |
| Acer          | Ferrari5                    | Notebook    | [7381cf9c0f](https://linux-hardware.org/?probe=7381cf9c0f) | Jan 09, 2022 |
| ASRock        | Z590 Phantom Gaming 4       | Desktop     | [2213b9d944](https://linux-hardware.org/?probe=2213b9d944) | Jan 09, 2022 |
| Acer          | AOD260                      | Notebook    | [fbd7c92891](https://linux-hardware.org/?probe=fbd7c92891) | Jan 09, 2022 |
| MB            | A320-SF110                  | Desktop     | [a7e48dafce](https://linux-hardware.org/?probe=a7e48dafce) | Jan 09, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [1d54af3923](https://linux-hardware.org/?probe=1d54af3923) | Jan 09, 2022 |
| Unknown       | Intel X79                   | Desktop     | [fb3cd8e89f](https://linux-hardware.org/?probe=fb3cd8e89f) | Jan 09, 2022 |
| Unknown       | Intel X79                   | Desktop     | [f11e53c43f](https://linux-hardware.org/?probe=f11e53c43f) | Jan 09, 2022 |
| ASUSTek       | M2N32 WS Professional       | Desktop     | [55570a4caf](https://linux-hardware.org/?probe=55570a4caf) | Jan 09, 2022 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [e5a3dd58b4](https://linux-hardware.org/?probe=e5a3dd58b4) | Jan 08, 2022 |
| MSI           | A68HM-P33 V2                | Desktop     | [6f850c21dd](https://linux-hardware.org/?probe=6f850c21dd) | Jan 08, 2022 |
| ASUSTek       | 1001PQD                     | Notebook    | [f820362ec8](https://linux-hardware.org/?probe=f820362ec8) | Jan 08, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [e540f5490c](https://linux-hardware.org/?probe=e540f5490c) | Jan 08, 2022 |
| Pegatron      | IPPPV-D3G                   | Desktop     | [7d91f4b386](https://linux-hardware.org/?probe=7d91f4b386) | Jan 08, 2022 |
| ASUSTek       | X201EP                      | Notebook    | [c7c03f84b3](https://linux-hardware.org/?probe=c7c03f84b3) | Jan 08, 2022 |
| HP            | 1497                        | Desktop     | [adfca54c7c](https://linux-hardware.org/?probe=adfca54c7c) | Jan 07, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [5121cfd7d6](https://linux-hardware.org/?probe=5121cfd7d6) | Jan 07, 2022 |
| Samsung       | NC210/NC110                 | Notebook    | [4f250b5f81](https://linux-hardware.org/?probe=4f250b5f81) | Jan 07, 2022 |
| HP            | Pavilion dv5                | Notebook    | [5934fe650f](https://linux-hardware.org/?probe=5934fe650f) | Jan 06, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [4cffd63b02](https://linux-hardware.org/?probe=4cffd63b02) | Jan 06, 2022 |
| Unknown       | Intel X79                   | Desktop     | [68f9084f74](https://linux-hardware.org/?probe=68f9084f74) | Jan 06, 2022 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [75d88ef705](https://linux-hardware.org/?probe=75d88ef705) | Jan 06, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [c2c863f82a](https://linux-hardware.org/?probe=c2c863f82a) | Jan 06, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [865394b031](https://linux-hardware.org/?probe=865394b031) | Jan 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [cf754c071b](https://linux-hardware.org/?probe=cf754c071b) | Jan 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [67487c4d3d](https://linux-hardware.org/?probe=67487c4d3d) | Jan 05, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [da41cecf9e](https://linux-hardware.org/?probe=da41cecf9e) | Jan 05, 2022 |
| IBM           | ThinkPad T43p 2668H9K       | Notebook    | [230290ea58](https://linux-hardware.org/?probe=230290ea58) | Jan 05, 2022 |
| IBM           | ThinkPad T43p 2668H9K       | Notebook    | [d091be7bdc](https://linux-hardware.org/?probe=d091be7bdc) | Jan 05, 2022 |
| Acer          | Aspire V3-551G              | Notebook    | [ec9cd18ee2](https://linux-hardware.org/?probe=ec9cd18ee2) | Jan 04, 2022 |
| ASUSTek       | M50Vc                       | Notebook    | [4d89c46c4f](https://linux-hardware.org/?probe=4d89c46c4f) | Jan 04, 2022 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [ecdbfe9b1d](https://linux-hardware.org/?probe=ecdbfe9b1d) | Jan 04, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [13999054c0](https://linux-hardware.org/?probe=13999054c0) | Jan 04, 2022 |
| MB            | A320-SF110                  | Desktop     | [7c1330f6a5](https://linux-hardware.org/?probe=7c1330f6a5) | Jan 04, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [a5cdfc2911](https://linux-hardware.org/?probe=a5cdfc2911) | Jan 03, 2022 |
| Dell          | Latitude E5550              | Notebook    | [ad5349f18a](https://linux-hardware.org/?probe=ad5349f18a) | Jan 03, 2022 |
| ASRock        | P43DE3                      | Desktop     | [b5593246f1](https://linux-hardware.org/?probe=b5593246f1) | Jan 03, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [667fd8b37d](https://linux-hardware.org/?probe=667fd8b37d) | Jan 03, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [ad4a117f64](https://linux-hardware.org/?probe=ad4a117f64) | Jan 03, 2022 |
| Apple         | MacBookAir2,1               | Notebook    | [225c657246](https://linux-hardware.org/?probe=225c657246) | Jan 03, 2022 |
| Unknown       | X79                         | Desktop     | [c3b10952db](https://linux-hardware.org/?probe=c3b10952db) | Jan 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [e87dc26de6](https://linux-hardware.org/?probe=e87dc26de6) | Jan 02, 2022 |
| ASUSTek       | H110M-A D3                  | Desktop     | [e97344283c](https://linux-hardware.org/?probe=e97344283c) | Jan 02, 2022 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [d42022e33e](https://linux-hardware.org/?probe=d42022e33e) | Jan 02, 2022 |
| HP            | 8184 X4                     | Desktop     | [3394545f42](https://linux-hardware.org/?probe=3394545f42) | Jan 02, 2022 |
| HP            | 8184 X4                     | Desktop     | [a5132121e1](https://linux-hardware.org/?probe=a5132121e1) | Jan 02, 2022 |
| ASUSTek       | H110M-A D3                  | Desktop     | [8259411656](https://linux-hardware.org/?probe=8259411656) | Jan 02, 2022 |
| Biostar       | A55MH                       | Desktop     | [3b3b92074f](https://linux-hardware.org/?probe=3b3b92074f) | Jan 02, 2022 |
| Lenovo        | G70-80 80FF                 | Notebook    | [b1279c6db3](https://linux-hardware.org/?probe=b1279c6db3) | Jan 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [188b0e95e0](https://linux-hardware.org/?probe=188b0e95e0) | Jan 01, 2022 |
| MSI           | MS-AC151 100                | All in one  | [76b99f17c7](https://linux-hardware.org/?probe=76b99f17c7) | Jan 01, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [9f93f2dd73](https://linux-hardware.org/?probe=9f93f2dd73) | Jan 01, 2022 |
| Dell          | 0XC7MM A01                  | Desktop     | [731572496c](https://linux-hardware.org/?probe=731572496c) | Jan 01, 2022 |
| ASRock        | 760GM-S3                    | Desktop     | [410f2a617f](https://linux-hardware.org/?probe=410f2a617f) | Jan 01, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [5ae8552af0](https://linux-hardware.org/?probe=5ae8552af0) | Jan 01, 2022 |
| ASRock        | G41C-GS                     | Desktop     | [2fe51370fe](https://linux-hardware.org/?probe=2fe51370fe) | Dec 31, 2021 |
| HP            | Cario CQ57                  | Notebook    | [5ac4e3101c](https://linux-hardware.org/?probe=5ac4e3101c) | Dec 31, 2021 |
| MSI           | GS63 7RD                    | Notebook    | [1566fa00e5](https://linux-hardware.org/?probe=1566fa00e5) | Dec 31, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [c5384c403d](https://linux-hardware.org/?probe=c5384c403d) | Dec 30, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [07cc3676cf](https://linux-hardware.org/?probe=07cc3676cf) | Dec 30, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [881f6198e2](https://linux-hardware.org/?probe=881f6198e2) | Dec 30, 2021 |
| ASRock        | ALiveXFire-eSATA2           | Desktop     | [fd1407e384](https://linux-hardware.org/?probe=fd1407e384) | Dec 30, 2021 |
| QIYIDA        | X99-H9 V2.0                 | Desktop     | [56da257cb5](https://linux-hardware.org/?probe=56da257cb5) | Dec 29, 2021 |
| HP            | Notebook                    | Notebook    | [398d69b2ac](https://linux-hardware.org/?probe=398d69b2ac) | Dec 29, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [c863a88fdf](https://linux-hardware.org/?probe=c863a88fdf) | Dec 28, 2021 |
| ASRock        | G31M-GS                     | Desktop     | [d31b2036c2](https://linux-hardware.org/?probe=d31b2036c2) | Dec 28, 2021 |
| Dell          | 0KH290                      | Desktop     | [e8c0e16dfb](https://linux-hardware.org/?probe=e8c0e16dfb) | Dec 28, 2021 |
| MSI           | P55-GD65                    | Desktop     | [37da95512b](https://linux-hardware.org/?probe=37da95512b) | Dec 28, 2021 |
| HP            | 843C                        | Desktop     | [f822738421](https://linux-hardware.org/?probe=f822738421) | Dec 28, 2021 |
| ECS           | GF8100VM-M5                 | Desktop     | [674ce5ec9c](https://linux-hardware.org/?probe=674ce5ec9c) | Dec 28, 2021 |
| Dell          | Vostro 1510                 | Notebook    | [38a24e373f](https://linux-hardware.org/?probe=38a24e373f) | Dec 28, 2021 |
| MSI           | 970A SLI Krait Edition      | Desktop     | [af3c225e1b](https://linux-hardware.org/?probe=af3c225e1b) | Dec 28, 2021 |
| Intel         | Unknown                     | Notebook    | [8bcebe35ef](https://linux-hardware.org/?probe=8bcebe35ef) | Dec 27, 2021 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [bee2c521b1](https://linux-hardware.org/?probe=bee2c521b1) | Dec 27, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [267bc3ffbd](https://linux-hardware.org/?probe=267bc3ffbd) | Dec 27, 2021 |
| Gigabyte      | N3050ND3H                   | Desktop     | [3b5551f0df](https://linux-hardware.org/?probe=3b5551f0df) | Dec 26, 2021 |
| EPoX Compu... | i915PL DDR : 5ELA3I         | Desktop     | [eed50d7d0b](https://linux-hardware.org/?probe=eed50d7d0b) | Dec 26, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [4210ac05a8](https://linux-hardware.org/?probe=4210ac05a8) | Dec 26, 2021 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [61630a987b](https://linux-hardware.org/?probe=61630a987b) | Dec 25, 2021 |
| ASRock        | J5040-ITX                   | Desktop     | [a3599c2da5](https://linux-hardware.org/?probe=a3599c2da5) | Dec 25, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [cb2ae92d82](https://linux-hardware.org/?probe=cb2ae92d82) | Dec 25, 2021 |
| HP            | Presario CQ57               | Notebook    | [0294a92fd1](https://linux-hardware.org/?probe=0294a92fd1) | Dec 25, 2021 |
| HP            | EliteBook 840 G4            | Notebook    | [8dda1bd936](https://linux-hardware.org/?probe=8dda1bd936) | Dec 24, 2021 |
| HP            | 87A4 10100                  | All in one  | [fcc6f8ec82](https://linux-hardware.org/?probe=fcc6f8ec82) | Dec 24, 2021 |
| ASRock        | H61M                        | Desktop     | [6326fff611](https://linux-hardware.org/?probe=6326fff611) | Dec 24, 2021 |
| HP            | 1905                        | Desktop     | [9e2637fa00](https://linux-hardware.org/?probe=9e2637fa00) | Dec 23, 2021 |
| HP            | 87A4 10100                  | All in one  | [71b9f56317](https://linux-hardware.org/?probe=71b9f56317) | Dec 23, 2021 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [d8aa2ff291](https://linux-hardware.org/?probe=d8aa2ff291) | Dec 23, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [b6cffe86a0](https://linux-hardware.org/?probe=b6cffe86a0) | Dec 23, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [efdf9bd8ec](https://linux-hardware.org/?probe=efdf9bd8ec) | Dec 23, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [3a7331c884](https://linux-hardware.org/?probe=3a7331c884) | Dec 22, 2021 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [66cd7cb6e5](https://linux-hardware.org/?probe=66cd7cb6e5) | Dec 22, 2021 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [7ded80ebab](https://linux-hardware.org/?probe=7ded80ebab) | Dec 22, 2021 |
| Sony          | SVE1412E1RW                 | Notebook    | [0a5b673fb5](https://linux-hardware.org/?probe=0a5b673fb5) | Dec 22, 2021 |
| Acer          | Aspire 7220                 | Notebook    | [7eb278623d](https://linux-hardware.org/?probe=7eb278623d) | Dec 22, 2021 |
| Gigabyte      | G41MT-D3                    | Desktop     | [c575f5fc18](https://linux-hardware.org/?probe=c575f5fc18) | Dec 22, 2021 |
| Dell          | Latitude 5490               | Notebook    | [11ae9aa9e4](https://linux-hardware.org/?probe=11ae9aa9e4) | Dec 21, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [fe425f8432](https://linux-hardware.org/?probe=fe425f8432) | Dec 20, 2021 |
| Samsung       | Q35/Q36                     | Notebook    | [9e522c605c](https://linux-hardware.org/?probe=9e522c605c) | Dec 20, 2021 |
| eMachines     | ET1850                      | Desktop     | [cffccff919](https://linux-hardware.org/?probe=cffccff919) | Dec 20, 2021 |
| Gigabyte      | M61SME-S2                   | Desktop     | [be9f6cac13](https://linux-hardware.org/?probe=be9f6cac13) | Dec 20, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [3a2ef6b552](https://linux-hardware.org/?probe=3a2ef6b552) | Dec 20, 2021 |
| MSI           | X370 GAMING PLUS            | Desktop     | [79ff299ff3](https://linux-hardware.org/?probe=79ff299ff3) | Dec 19, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [9f1ab29552](https://linux-hardware.org/?probe=9f1ab29552) | Dec 19, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [3a78778c18](https://linux-hardware.org/?probe=3a78778c18) | Dec 19, 2021 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [b7f81353b8](https://linux-hardware.org/?probe=b7f81353b8) | Dec 19, 2021 |
| MSI           | A320M PRO-VD PLUS           | Desktop     | [7f0853c09e](https://linux-hardware.org/?probe=7f0853c09e) | Dec 19, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [9ab82ba1e9](https://linux-hardware.org/?probe=9ab82ba1e9) | Dec 19, 2021 |
| HP            | Mini 110-3000               | Notebook    | [ce45dd9a4d](https://linux-hardware.org/?probe=ce45dd9a4d) | Dec 19, 2021 |
| Apple         | MacBookAir2,1               | Notebook    | [30dd1b6e63](https://linux-hardware.org/?probe=30dd1b6e63) | Dec 19, 2021 |
| Acer          | FIH57                       | All in one  | [93684f3ecf](https://linux-hardware.org/?probe=93684f3ecf) | Dec 19, 2021 |
| Apple         | MacBookAir2,1               | Notebook    | [cdfa4e4182](https://linux-hardware.org/?probe=cdfa4e4182) | Dec 18, 2021 |
| Acer          | EM61SM/EM61PM               | Desktop     | [28533baa5a](https://linux-hardware.org/?probe=28533baa5a) | Dec 18, 2021 |
| Acer          | EM61SM/EM61PM               | Desktop     | [1a6d1fc80e](https://linux-hardware.org/?probe=1a6d1fc80e) | Dec 18, 2021 |
| HP            | 630                         | Notebook    | [027b9733fa](https://linux-hardware.org/?probe=027b9733fa) | Dec 18, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8641a3f536](https://linux-hardware.org/?probe=8641a3f536) | Dec 17, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [25a567546a](https://linux-hardware.org/?probe=25a567546a) | Dec 17, 2021 |
| ASUSTek       | P5LD2                       | Desktop     | [64809c7cee](https://linux-hardware.org/?probe=64809c7cee) | Dec 17, 2021 |
| Huanan        | X99-F8                      | Desktop     | [3d3a49ce43](https://linux-hardware.org/?probe=3d3a49ce43) | Dec 17, 2021 |
| Huanan        | X99-F8                      | Desktop     | [ffd502b8dc](https://linux-hardware.org/?probe=ffd502b8dc) | Dec 17, 2021 |
| Acer          | Aspire V3-551G              | Notebook    | [8d712af9e8](https://linux-hardware.org/?probe=8d712af9e8) | Dec 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ba8814b84b](https://linux-hardware.org/?probe=ba8814b84b) | Dec 17, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [23ea4933bf](https://linux-hardware.org/?probe=23ea4933bf) | Dec 17, 2021 |
| Packard Be... | EN Butterfly m              | Notebook    | [9c2bffdd98](https://linux-hardware.org/?probe=9c2bffdd98) | Dec 16, 2021 |
| Pegatron      | H110-P1                     | Desktop     | [4ba766f851](https://linux-hardware.org/?probe=4ba766f851) | Dec 16, 2021 |
| ASUSTek       | PRIME H310I-PLUS R2.0       | Desktop     | [c1dac87021](https://linux-hardware.org/?probe=c1dac87021) | Dec 16, 2021 |
| Lenovo        | B590 20206                  | Notebook    | [d80c9d4f20](https://linux-hardware.org/?probe=d80c9d4f20) | Dec 16, 2021 |
| Lenovo        | B590 20206                  | Notebook    | [63051e4ef5](https://linux-hardware.org/?probe=63051e4ef5) | Dec 16, 2021 |
| Biostar       | N68S3+                      | Desktop     | [8812de783f](https://linux-hardware.org/?probe=8812de783f) | Dec 16, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [fd350b52da](https://linux-hardware.org/?probe=fd350b52da) | Dec 16, 2021 |
| Lenovo        | MAHOBAY No DPK              | All in one  | [968b139684](https://linux-hardware.org/?probe=968b139684) | Dec 15, 2021 |
| Sony          | VGN-FW51JF_H                | Notebook    | [65e7795371](https://linux-hardware.org/?probe=65e7795371) | Dec 15, 2021 |
| Sony          | VAIO                        | All in one  | [e43a2c01eb](https://linux-hardware.org/?probe=e43a2c01eb) | Dec 15, 2021 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [bd40ed7f17](https://linux-hardware.org/?probe=bd40ed7f17) | Dec 15, 2021 |
| MSI           | B75MA-E33                   | Desktop     | [bcd1e4cb29](https://linux-hardware.org/?probe=bcd1e4cb29) | Dec 15, 2021 |
| Unknown       | Unknown                     | Desktop     | [21e1829e7a](https://linux-hardware.org/?probe=21e1829e7a) | Dec 14, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [ab6de59887](https://linux-hardware.org/?probe=ab6de59887) | Dec 14, 2021 |
| Fujitsu       | LIFEBOOK AH531              | Notebook    | [b294d0719f](https://linux-hardware.org/?probe=b294d0719f) | Dec 14, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [1192a0862d](https://linux-hardware.org/?probe=1192a0862d) | Dec 14, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [382ba35de6](https://linux-hardware.org/?probe=382ba35de6) | Dec 14, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [a3c85ddcb3](https://linux-hardware.org/?probe=a3c85ddcb3) | Dec 14, 2021 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [cb886a82aa](https://linux-hardware.org/?probe=cb886a82aa) | Dec 13, 2021 |
| BenQ          | Joybook R56                 | Notebook    | [e05d04b5ec](https://linux-hardware.org/?probe=e05d04b5ec) | Dec 13, 2021 |
| ASUSTek       | H87-PLUS                    | Desktop     | [bb93c7406e](https://linux-hardware.org/?probe=bb93c7406e) | Dec 12, 2021 |
| HASEE Comp... | W65KJ1_KK1                  | Notebook    | [acc8611de6](https://linux-hardware.org/?probe=acc8611de6) | Dec 12, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [cc66463e42](https://linux-hardware.org/?probe=cc66463e42) | Dec 12, 2021 |
| ASUSTek       | E402SA                      | Notebook    | [2a140138d3](https://linux-hardware.org/?probe=2a140138d3) | Dec 12, 2021 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [f4c075a2d2](https://linux-hardware.org/?probe=f4c075a2d2) | Dec 11, 2021 |
| Samsung       | R528/R728                   | Notebook    | [2c553ccbfd](https://linux-hardware.org/?probe=2c553ccbfd) | Dec 11, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [bba01dfbb6](https://linux-hardware.org/?probe=bba01dfbb6) | Dec 11, 2021 |
| Lenovo        | ThinkPad X220 42912WG       | Notebook    | [f26ab9e1e1](https://linux-hardware.org/?probe=f26ab9e1e1) | Dec 11, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [9c69e84acb](https://linux-hardware.org/?probe=9c69e84acb) | Dec 11, 2021 |
| ASUSTek       | B150M-C                     | Desktop     | [f2f2c5cb49](https://linux-hardware.org/?probe=f2f2c5cb49) | Dec 10, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [e261e82842](https://linux-hardware.org/?probe=e261e82842) | Dec 10, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [9815e03f0d](https://linux-hardware.org/?probe=9815e03f0d) | Dec 10, 2021 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [8fa17a7ab6](https://linux-hardware.org/?probe=8fa17a7ab6) | Dec 10, 2021 |
| Huanan        | X79 V2.3 249PC              | Desktop     | [486dfd146e](https://linux-hardware.org/?probe=486dfd146e) | Dec 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [27e8bdccce](https://linux-hardware.org/?probe=27e8bdccce) | Dec 09, 2021 |
| MSI           | MS-7238                     | Desktop     | [05583cce99](https://linux-hardware.org/?probe=05583cce99) | Dec 09, 2021 |
| Lenovo        | G70-80 80FF                 | Notebook    | [7d694ce256](https://linux-hardware.org/?probe=7d694ce256) | Dec 09, 2021 |
| Samsung       | R528/R728                   | Notebook    | [e0c29683e8](https://linux-hardware.org/?probe=e0c29683e8) | Dec 09, 2021 |
| Acer          | Acadia V1.14                | Notebook    | [83720787eb](https://linux-hardware.org/?probe=83720787eb) | Dec 09, 2021 |
| ASRock        | N68C-S                      | Desktop     | [ea417e042a](https://linux-hardware.org/?probe=ea417e042a) | Dec 09, 2021 |
| MSI           | B560M PRO-VDH               | Desktop     | [ba2880686f](https://linux-hardware.org/?probe=ba2880686f) | Dec 08, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [d84eb83569](https://linux-hardware.org/?probe=d84eb83569) | Dec 08, 2021 |
| ASRock        | N68C-GS UCC                 | Desktop     | [9da859a341](https://linux-hardware.org/?probe=9da859a341) | Dec 08, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [d111b1da0d](https://linux-hardware.org/?probe=d111b1da0d) | Dec 08, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [d11e027c87](https://linux-hardware.org/?probe=d11e027c87) | Dec 08, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [0ad46680b2](https://linux-hardware.org/?probe=0ad46680b2) | Dec 07, 2021 |
| HP            | Pavilion g6                 | Notebook    | [f5eef58820](https://linux-hardware.org/?probe=f5eef58820) | Dec 07, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [4b383d9b07](https://linux-hardware.org/?probe=4b383d9b07) | Dec 07, 2021 |
| Sony          | SVE1512G1RB                 | Notebook    | [e4ce73b2a4](https://linux-hardware.org/?probe=e4ce73b2a4) | Dec 07, 2021 |
| Samsung       | R530/R730                   | Notebook    | [164d49aa5a](https://linux-hardware.org/?probe=164d49aa5a) | Dec 07, 2021 |
| Gigabyte      | GA-MA78LM-S2                | Desktop     | [43317bd67f](https://linux-hardware.org/?probe=43317bd67f) | Dec 07, 2021 |
| DNS           | W510LU                      | Notebook    | [0c8c5f2fd0](https://linux-hardware.org/?probe=0c8c5f2fd0) | Dec 07, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [38912e55d8](https://linux-hardware.org/?probe=38912e55d8) | Dec 07, 2021 |
| ASUSTek       | B150M-C                     | Desktop     | [a3e2cda715](https://linux-hardware.org/?probe=a3e2cda715) | Dec 07, 2021 |
| HP            | 1905                        | Desktop     | [e16a65e786](https://linux-hardware.org/?probe=e16a65e786) | Dec 06, 2021 |
| HP            | 1905                        | Desktop     | [d58c2f29a4](https://linux-hardware.org/?probe=d58c2f29a4) | Dec 06, 2021 |
| Lenovo        | ThinkPad W540 20BG001KUK    | Notebook    | [68023d22af](https://linux-hardware.org/?probe=68023d22af) | Dec 06, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [3c415780c5](https://linux-hardware.org/?probe=3c415780c5) | Dec 06, 2021 |
| ASRock        | H55M Pro                    | Desktop     | [6a4ccca36d](https://linux-hardware.org/?probe=6a4ccca36d) | Dec 05, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [c44fa77c0e](https://linux-hardware.org/?probe=c44fa77c0e) | Dec 05, 2021 |
| ASUSTek       | K43E                        | Notebook    | [bb13b10409](https://linux-hardware.org/?probe=bb13b10409) | Dec 05, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [641a9747b5](https://linux-hardware.org/?probe=641a9747b5) | Dec 05, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [c39160cbba](https://linux-hardware.org/?probe=c39160cbba) | Dec 05, 2021 |
| Acer          | Aspire ES1-522              | Notebook    | [f7bb1e4f3a](https://linux-hardware.org/?probe=f7bb1e4f3a) | Dec 05, 2021 |
| ASUSTek       | X401A1                      | Notebook    | [cf9f6e6049](https://linux-hardware.org/?probe=cf9f6e6049) | Dec 05, 2021 |
| ABIT          | AN52                        | Desktop     | [c77f120f57](https://linux-hardware.org/?probe=c77f120f57) | Dec 05, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | Notebook    | [fbe30211c6](https://linux-hardware.org/?probe=fbe30211c6) | Dec 05, 2021 |
| ASUSTek       | K50IE                       | Notebook    | [985ed9e52c](https://linux-hardware.org/?probe=985ed9e52c) | Dec 05, 2021 |
| Toshiba       | Satellite L30               | Notebook    | [c27dfb9787](https://linux-hardware.org/?probe=c27dfb9787) | Dec 04, 2021 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [66c631fa19](https://linux-hardware.org/?probe=66c631fa19) | Dec 04, 2021 |
| HP            | Pavilion g6                 | Notebook    | [b401047908](https://linux-hardware.org/?probe=b401047908) | Dec 04, 2021 |
| HP            | EliteBook 2760p             | Notebook    | [9efe885c4c](https://linux-hardware.org/?probe=9efe885c4c) | Dec 04, 2021 |
| ECS           | H310H5-M2                   | Desktop     | [a308733c0a](https://linux-hardware.org/?probe=a308733c0a) | Dec 04, 2021 |
| MSI           | B350 TOMAHAWK PLUS          | Desktop     | [a718308a13](https://linux-hardware.org/?probe=a718308a13) | Dec 04, 2021 |
| Acer          | Aspire TC-605               | Desktop     | [6737d1ed9d](https://linux-hardware.org/?probe=6737d1ed9d) | Dec 04, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f8286e866e](https://linux-hardware.org/?probe=f8286e866e) | Dec 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [4e5949da98](https://linux-hardware.org/?probe=4e5949da98) | Dec 03, 2021 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [dba1ac491b](https://linux-hardware.org/?probe=dba1ac491b) | Dec 03, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [7530a42730](https://linux-hardware.org/?probe=7530a42730) | Dec 03, 2021 |
| Lenovo        | 1048 SDK0T08861 WIN 3305... | Desktop     | [c8b48bd2a7](https://linux-hardware.org/?probe=c8b48bd2a7) | Dec 03, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [d13f0450b4](https://linux-hardware.org/?probe=d13f0450b4) | Dec 03, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [bd730964e5](https://linux-hardware.org/?probe=bd730964e5) | Dec 02, 2021 |
| Lenovo        | B590 20206                  | Notebook    | [dca5dcaeaf](https://linux-hardware.org/?probe=dca5dcaeaf) | Dec 02, 2021 |
| Gigabyte      | Z390 UD V2                  | Desktop     | [c45fd8b141](https://linux-hardware.org/?probe=c45fd8b141) | Dec 02, 2021 |
| HP            | Pavilion 15                 | Notebook    | [495bcb1b46](https://linux-hardware.org/?probe=495bcb1b46) | Dec 02, 2021 |
| Packard Be... | EasyNote LJ75               | Notebook    | [df13a85c43](https://linux-hardware.org/?probe=df13a85c43) | Dec 02, 2021 |
| HP            | ProLiant DL360 G5           | Server      | [24d4b5b8db](https://linux-hardware.org/?probe=24d4b5b8db) | Dec 02, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [e04a7b1f0f](https://linux-hardware.org/?probe=e04a7b1f0f) | Dec 01, 2021 |
| HP            | Compaq Presario CQ60        | Notebook    | [ca488bbc88](https://linux-hardware.org/?probe=ca488bbc88) | Dec 01, 2021 |
| MSI           | 0AB8                        | Desktop     | [4bf8e40af9](https://linux-hardware.org/?probe=4bf8e40af9) | Dec 01, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fe6b093555](https://linux-hardware.org/?probe=fe6b093555) | Dec 01, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [209e43a42c](https://linux-hardware.org/?probe=209e43a42c) | Dec 01, 2021 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [d319a0f393](https://linux-hardware.org/?probe=d319a0f393) | Dec 01, 2021 |
| Lenovo        | ThinkPad T430 2349S1N       | Notebook    | [7667b857cc](https://linux-hardware.org/?probe=7667b857cc) | Nov 30, 2021 |
| HP            | Pavilion g6                 | Notebook    | [c6bdce68cc](https://linux-hardware.org/?probe=c6bdce68cc) | Nov 30, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [791569d6e8](https://linux-hardware.org/?probe=791569d6e8) | Nov 30, 2021 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [aa7bf24fd4](https://linux-hardware.org/?probe=aa7bf24fd4) | Nov 30, 2021 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [a7db584bd5](https://linux-hardware.org/?probe=a7db584bd5) | Nov 29, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [d8baefc30d](https://linux-hardware.org/?probe=d8baefc30d) | Nov 29, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [bea60488c2](https://linux-hardware.org/?probe=bea60488c2) | Nov 29, 2021 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [b0c19bcc93](https://linux-hardware.org/?probe=b0c19bcc93) | Nov 29, 2021 |
| ASUSTek       | M2N                         | Desktop     | [f76f2473ac](https://linux-hardware.org/?probe=f76f2473ac) | Nov 28, 2021 |
| Lenovo        | 0x36C4                      | All in one  | [c2a07b6931](https://linux-hardware.org/?probe=c2a07b6931) | Nov 28, 2021 |
| ASRock        | A320M-HDV R3.0              | Desktop     | [5df73b5935](https://linux-hardware.org/?probe=5df73b5935) | Nov 28, 2021 |
| ECS           | G31T-M7                     | Desktop     | [6c5f9af439](https://linux-hardware.org/?probe=6c5f9af439) | Nov 28, 2021 |
| ASUSTek       | X540YA                      | Notebook    | [833019e25c](https://linux-hardware.org/?probe=833019e25c) | Nov 28, 2021 |
| ASUSTek       | P5KPL                       | Desktop     | [5770f2e744](https://linux-hardware.org/?probe=5770f2e744) | Nov 28, 2021 |
| DNS           | W510LU                      | Notebook    | [0716ee5d69](https://linux-hardware.org/?probe=0716ee5d69) | Nov 28, 2021 |
| ASUSTek       | X551MA                      | Notebook    | [e497d43da5](https://linux-hardware.org/?probe=e497d43da5) | Nov 28, 2021 |
| ASUSTek       | M4A77                       | Desktop     | [1ae1f0835d](https://linux-hardware.org/?probe=1ae1f0835d) | Nov 28, 2021 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [a37391d012](https://linux-hardware.org/?probe=a37391d012) | Nov 27, 2021 |
| OEM           | Intel H81                   | Desktop     | [751a43c7b2](https://linux-hardware.org/?probe=751a43c7b2) | Nov 27, 2021 |
| HP            | Notebook                    | Notebook    | [f7455d1de6](https://linux-hardware.org/?probe=f7455d1de6) | Nov 27, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [00c297540d](https://linux-hardware.org/?probe=00c297540d) | Nov 27, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [0a5275c755](https://linux-hardware.org/?probe=0a5275c755) | Nov 27, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [a60ff3baf4](https://linux-hardware.org/?probe=a60ff3baf4) | Nov 27, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [c71cc581b6](https://linux-hardware.org/?probe=c71cc581b6) | Nov 27, 2021 |
| ASRock        | H77M                        | Desktop     | [c606652163](https://linux-hardware.org/?probe=c606652163) | Nov 27, 2021 |
| Dell          | Latitude E6420              | Notebook    | [b4d8c9967f](https://linux-hardware.org/?probe=b4d8c9967f) | Nov 27, 2021 |
| Dell          | Latitude E6420              | Notebook    | [e06c2e635f](https://linux-hardware.org/?probe=e06c2e635f) | Nov 26, 2021 |
| ASUSTek       | M3A78-VM                    | Desktop     | [3796a07da9](https://linux-hardware.org/?probe=3796a07da9) | Nov 26, 2021 |
| ASUSTek       | Commando                    | Desktop     | [93b2d8a807](https://linux-hardware.org/?probe=93b2d8a807) | Nov 26, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [58a93e8a00](https://linux-hardware.org/?probe=58a93e8a00) | Nov 26, 2021 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [75c7366fc8](https://linux-hardware.org/?probe=75c7366fc8) | Nov 26, 2021 |
| HASEE Comp... | W65KJ1_KK1                  | Notebook    | [714fab132e](https://linux-hardware.org/?probe=714fab132e) | Nov 25, 2021 |
| HP            | Pavilion m6                 | Notebook    | [e0946dd051](https://linux-hardware.org/?probe=e0946dd051) | Nov 25, 2021 |
| Gigabyte      | H81-D3                      | Desktop     | [6a4a93bc26](https://linux-hardware.org/?probe=6a4a93bc26) | Nov 25, 2021 |
| Gigabyte      | H410M H V3                  | Desktop     | [7c367c256c](https://linux-hardware.org/?probe=7c367c256c) | Nov 25, 2021 |
| HP            | 834F                        | Desktop     | [ee1361ee2f](https://linux-hardware.org/?probe=ee1361ee2f) | Nov 25, 2021 |
| ASUSTek       | M3A78-CM                    | Desktop     | [013a418252](https://linux-hardware.org/?probe=013a418252) | Nov 24, 2021 |
| Gigabyte      | B560 HD3                    | Desktop     | [6d3791ee95](https://linux-hardware.org/?probe=6d3791ee95) | Nov 24, 2021 |
| Acer          | Aspire 3610                 | Notebook    | [8e86e03a2e](https://linux-hardware.org/?probe=8e86e03a2e) | Nov 24, 2021 |
| OEM           | Intel H81                   | Desktop     | [2e1f87c49e](https://linux-hardware.org/?probe=2e1f87c49e) | Nov 24, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [f473a174c6](https://linux-hardware.org/?probe=f473a174c6) | Nov 24, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [df1011f2fc](https://linux-hardware.org/?probe=df1011f2fc) | Nov 24, 2021 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [698d70a723](https://linux-hardware.org/?probe=698d70a723) | Nov 24, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [719ce542c2](https://linux-hardware.org/?probe=719ce542c2) | Nov 23, 2021 |
| Toshiba       | Satellite Pro C50-A-154     | Notebook    | [6fb1dbf0e0](https://linux-hardware.org/?probe=6fb1dbf0e0) | Nov 23, 2021 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [bf541402c8](https://linux-hardware.org/?probe=bf541402c8) | Nov 23, 2021 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [1e54dd310c](https://linux-hardware.org/?probe=1e54dd310c) | Nov 23, 2021 |
| Google        | Panther                     | Desktop     | [5e5d9936ec](https://linux-hardware.org/?probe=5e5d9936ec) | Nov 23, 2021 |
| Lenovo        | Legion Y7000 2019 81NS      | Notebook    | [19ce916e45](https://linux-hardware.org/?probe=19ce916e45) | Nov 22, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [646c8dd3dd](https://linux-hardware.org/?probe=646c8dd3dd) | Nov 22, 2021 |
| HP            | Pavilion g6                 | Notebook    | [9f2968c92d](https://linux-hardware.org/?probe=9f2968c92d) | Nov 21, 2021 |
| HP            | Pavilion g6                 | Notebook    | [629853d948](https://linux-hardware.org/?probe=629853d948) | Nov 21, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [d87aa63f87](https://linux-hardware.org/?probe=d87aa63f87) | Nov 21, 2021 |
| Dell          | Latitude E5550              | Notebook    | [8bdee49fb5](https://linux-hardware.org/?probe=8bdee49fb5) | Nov 21, 2021 |
| ASUSTek       | M3A78-EM                    | Desktop     | [1ed97ae220](https://linux-hardware.org/?probe=1ed97ae220) | Nov 21, 2021 |
| Gigabyte      | F2A88X-D3HP                 | Desktop     | [1966eaf4c2](https://linux-hardware.org/?probe=1966eaf4c2) | Nov 21, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [0cf346d7e2](https://linux-hardware.org/?probe=0cf346d7e2) | Nov 20, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [86d0614397](https://linux-hardware.org/?probe=86d0614397) | Nov 20, 2021 |
| ASUSTek       | K52JB                       | Notebook    | [a29b8340b0](https://linux-hardware.org/?probe=a29b8340b0) | Nov 20, 2021 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [0ec755606d](https://linux-hardware.org/?probe=0ec755606d) | Nov 20, 2021 |
| ASUSTek       | X541SA                      | Notebook    | [4c170f3e67](https://linux-hardware.org/?probe=4c170f3e67) | Nov 20, 2021 |
| ASUSTek       | X550CL                      | Notebook    | [746f2f97d8](https://linux-hardware.org/?probe=746f2f97d8) | Nov 20, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [3aa8299eba](https://linux-hardware.org/?probe=3aa8299eba) | Nov 20, 2021 |
| ASRock        | J3455-ITX                   | Desktop     | [f89a82d2d3](https://linux-hardware.org/?probe=f89a82d2d3) | Nov 20, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [96f99ce226](https://linux-hardware.org/?probe=96f99ce226) | Nov 20, 2021 |
| Samsung       | R519/R719                   | Notebook    | [cd5ea0ec09](https://linux-hardware.org/?probe=cd5ea0ec09) | Nov 19, 2021 |
| Samsung       | R540/R580/R780/SA41/E452... | Notebook    | [f6e2eff346](https://linux-hardware.org/?probe=f6e2eff346) | Nov 19, 2021 |
| ASUSTek       | F5V                         | Notebook    | [77029e9a4c](https://linux-hardware.org/?probe=77029e9a4c) | Nov 19, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [a9ed0baee9](https://linux-hardware.org/?probe=a9ed0baee9) | Nov 19, 2021 |
| Unknown       | NF-CK804                    | Desktop     | [ad5962b940](https://linux-hardware.org/?probe=ad5962b940) | Nov 19, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [b711c3ef4b](https://linux-hardware.org/?probe=b711c3ef4b) | Nov 19, 2021 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [f72f0b000f](https://linux-hardware.org/?probe=f72f0b000f) | Nov 19, 2021 |
| ASUSTek       | 1018P                       | Notebook    | [2fafc42636](https://linux-hardware.org/?probe=2fafc42636) | Nov 19, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [7334fe69b4](https://linux-hardware.org/?probe=7334fe69b4) | Nov 18, 2021 |
| MSI           | B85-G43                     | Desktop     | [d09af779e6](https://linux-hardware.org/?probe=d09af779e6) | Nov 18, 2021 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [6590ce45fe](https://linux-hardware.org/?probe=6590ce45fe) | Nov 18, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [f1e260cc78](https://linux-hardware.org/?probe=f1e260cc78) | Nov 18, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [abeaeb3a7d](https://linux-hardware.org/?probe=abeaeb3a7d) | Nov 18, 2021 |
| ASUSTek       | M2N                         | Desktop     | [ba2f298ff6](https://linux-hardware.org/?probe=ba2f298ff6) | Nov 18, 2021 |
| Lenovo        | B590 20206                  | Notebook    | [c5d3f06c7e](https://linux-hardware.org/?probe=c5d3f06c7e) | Nov 18, 2021 |
| ASUSTek       | M2N                         | Desktop     | [959cdba098](https://linux-hardware.org/?probe=959cdba098) | Nov 17, 2021 |
| ASUSTek       | P5L-VM 1394                 | Desktop     | [44fcd8b12a](https://linux-hardware.org/?probe=44fcd8b12a) | Nov 17, 2021 |
| ASUSTek       | M3400WUA                    | All in one  | [f788930c1e](https://linux-hardware.org/?probe=f788930c1e) | Nov 17, 2021 |
| MSI           | A320M PRO-E                 | Desktop     | [18dfc2b1a3](https://linux-hardware.org/?probe=18dfc2b1a3) | Nov 17, 2021 |
| Gigabyte      | H81M-S1                     | Desktop     | [1707b7e52b](https://linux-hardware.org/?probe=1707b7e52b) | Nov 17, 2021 |
| Toshiba       | Satellite M100              | Notebook    | [b430b2f9ab](https://linux-hardware.org/?probe=b430b2f9ab) | Nov 17, 2021 |
| HP            | Laptop 14-bp0xx             | Notebook    | [5304c07cec](https://linux-hardware.org/?probe=5304c07cec) | Nov 16, 2021 |
| HP            | Notebook                    | Notebook    | [b4472b4f06](https://linux-hardware.org/?probe=b4472b4f06) | Nov 16, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [f8a555b358](https://linux-hardware.org/?probe=f8a555b358) | Nov 16, 2021 |
| MSI           | G31M3-F V2                  | Desktop     | [d8fd50a08b](https://linux-hardware.org/?probe=d8fd50a08b) | Nov 16, 2021 |
| Acer          | AOA110                      | Notebook    | [0a0f33d176](https://linux-hardware.org/?probe=0a0f33d176) | Nov 16, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [add0711cbf](https://linux-hardware.org/?probe=add0711cbf) | Nov 16, 2021 |
| Lenovo        | NOK                         | Desktop     | [b3446fbdb9](https://linux-hardware.org/?probe=b3446fbdb9) | Nov 15, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5c83563aec](https://linux-hardware.org/?probe=5c83563aec) | Nov 15, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [5e1df477d7](https://linux-hardware.org/?probe=5e1df477d7) | Nov 15, 2021 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [16fc189abd](https://linux-hardware.org/?probe=16fc189abd) | Nov 15, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [c9936f4f25](https://linux-hardware.org/?probe=c9936f4f25) | Nov 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [9bc9b5743c](https://linux-hardware.org/?probe=9bc9b5743c) | Nov 15, 2021 |
| MSI           | B350 TOMAHAWK PLUS          | Desktop     | [a11982a380](https://linux-hardware.org/?probe=a11982a380) | Nov 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [03a705eace](https://linux-hardware.org/?probe=03a705eace) | Nov 13, 2021 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [4565c94d5a](https://linux-hardware.org/?probe=4565c94d5a) | Nov 13, 2021 |
| HP            | Pavilion g6                 | Notebook    | [52636906d8](https://linux-hardware.org/?probe=52636906d8) | Nov 13, 2021 |
| Gigabyte      | H77-DS3H                    | Desktop     | [b21ac5cce6](https://linux-hardware.org/?probe=b21ac5cce6) | Nov 13, 2021 |
| ASUSTek       | M4A88T-M                    | Desktop     | [90c25fdd8c](https://linux-hardware.org/?probe=90c25fdd8c) | Nov 13, 2021 |
| Fujitsu Si... | D1561 S26361-D1561          | Desktop     | [8bbf7045eb](https://linux-hardware.org/?probe=8bbf7045eb) | Nov 13, 2021 |
| Toshiba       | Satellite L650D             | Notebook    | [88a5830818](https://linux-hardware.org/?probe=88a5830818) | Nov 13, 2021 |
| Foxconn       | H61MXV/H67MXV               | Desktop     | [42c27f6732](https://linux-hardware.org/?probe=42c27f6732) | Nov 13, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [1eb66f9b96](https://linux-hardware.org/?probe=1eb66f9b96) | Nov 13, 2021 |
| IBM           | 9210D7G                     | Desktop     | [c699acdcf7](https://linux-hardware.org/?probe=c699acdcf7) | Nov 13, 2021 |
| HP            | 620                         | Notebook    | [5ac140224b](https://linux-hardware.org/?probe=5ac140224b) | Nov 12, 2021 |
| Gigabyte      | H81M-S1                     | Desktop     | [df6d9da79f](https://linux-hardware.org/?probe=df6d9da79f) | Nov 12, 2021 |
| ASRock        | A520M Pro4                  | Desktop     | [ea53d31af0](https://linux-hardware.org/?probe=ea53d31af0) | Nov 12, 2021 |
| ASRock        | H55M-LE                     | Desktop     | [38d555d601](https://linux-hardware.org/?probe=38d555d601) | Nov 12, 2021 |
| Samsung       | RC410/RC510/RC710           | Notebook    | [94f8e88090](https://linux-hardware.org/?probe=94f8e88090) | Nov 12, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [3dff717d1e](https://linux-hardware.org/?probe=3dff717d1e) | Nov 12, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [f143724787](https://linux-hardware.org/?probe=f143724787) | Nov 12, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [b3c9f63108](https://linux-hardware.org/?probe=b3c9f63108) | Nov 12, 2021 |
| HP            | Pavilion g7                 | Notebook    | [a9179e23c1](https://linux-hardware.org/?probe=a9179e23c1) | Nov 11, 2021 |
| Acer          | Aspire 5820TG               | Notebook    | [b178d97dc6](https://linux-hardware.org/?probe=b178d97dc6) | Nov 10, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [c7d2dc593b](https://linux-hardware.org/?probe=c7d2dc593b) | Nov 10, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [039315b907](https://linux-hardware.org/?probe=039315b907) | Nov 10, 2021 |
| ASUSTek       | P5L1394                     | Desktop     | [77429f6d4e](https://linux-hardware.org/?probe=77429f6d4e) | Nov 10, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [3cd35960f1](https://linux-hardware.org/?probe=3cd35960f1) | Nov 10, 2021 |
| Acer          | AO751h                      | Notebook    | [71eac887d5](https://linux-hardware.org/?probe=71eac887d5) | Nov 09, 2021 |
| MSI           | GF615M-P33                  | Desktop     | [2cab5edfa7](https://linux-hardware.org/?probe=2cab5edfa7) | Nov 09, 2021 |
| Notebook      | W65_W670SR                  | Notebook    | [ac4a0b408f](https://linux-hardware.org/?probe=ac4a0b408f) | Nov 09, 2021 |
| Acer          | Extensa 5220                | Notebook    | [f2a3d26a93](https://linux-hardware.org/?probe=f2a3d26a93) | Nov 08, 2021 |
| ASRock        | G31M-S                      | Desktop     | [2ff442af20](https://linux-hardware.org/?probe=2ff442af20) | Nov 08, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [38ce19b0a2](https://linux-hardware.org/?probe=38ce19b0a2) | Nov 08, 2021 |
| Supermicro    | X9SCL/X9SCMA                | Desktop     | [84f842950b](https://linux-hardware.org/?probe=84f842950b) | Nov 08, 2021 |
| Digma         | EVE 10 C301 ES1050EW        | Notebook    | [89cca4144e](https://linux-hardware.org/?probe=89cca4144e) | Nov 08, 2021 |
| MSI           | G41M-P33 Combo              | Desktop     | [935a16fe22](https://linux-hardware.org/?probe=935a16fe22) | Nov 08, 2021 |
| MSI           | X99A SLI PLUS               | Desktop     | [8d4a878fcf](https://linux-hardware.org/?probe=8d4a878fcf) | Nov 08, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [e2b0275b48](https://linux-hardware.org/?probe=e2b0275b48) | Nov 08, 2021 |
| ASUSTek       | P5K-VM                      | Desktop     | [8dbda1ce8f](https://linux-hardware.org/?probe=8dbda1ce8f) | Nov 08, 2021 |
| ASUSTek       | P5Q PRO TURBO               | Desktop     | [abea647afe](https://linux-hardware.org/?probe=abea647afe) | Nov 08, 2021 |
| BenQ          | Joybook P41                 | Notebook    | [380b155fb4](https://linux-hardware.org/?probe=380b155fb4) | Nov 07, 2021 |
| ASUSTek       | M4A78LT-M LX                | Desktop     | [417b74c746](https://linux-hardware.org/?probe=417b74c746) | Nov 07, 2021 |
| HP            | 1493                        | Desktop     | [fc15a1ee5c](https://linux-hardware.org/?probe=fc15a1ee5c) | Nov 07, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [3722e4de1a](https://linux-hardware.org/?probe=3722e4de1a) | Nov 07, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [a55cdb7c83](https://linux-hardware.org/?probe=a55cdb7c83) | Nov 07, 2021 |
| Lenovo        | H420                        | Desktop     | [4a3b12d8f9](https://linux-hardware.org/?probe=4a3b12d8f9) | Nov 07, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [c4fd612984](https://linux-hardware.org/?probe=c4fd612984) | Nov 07, 2021 |
| MSI           | 760GM -E51                  | Desktop     | [945b3dc58b](https://linux-hardware.org/?probe=945b3dc58b) | Nov 06, 2021 |
| Acer          | Extensa 5220                | Notebook    | [c7c798e2bd](https://linux-hardware.org/?probe=c7c798e2bd) | Nov 06, 2021 |
| ASRock        | G31M-S                      | Desktop     | [5c3725202d](https://linux-hardware.org/?probe=5c3725202d) | Nov 06, 2021 |
| ASUSTek       | X750JB                      | Notebook    | [462cceab3c](https://linux-hardware.org/?probe=462cceab3c) | Nov 06, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [aa927a00f4](https://linux-hardware.org/?probe=aa927a00f4) | Nov 06, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [4ed7dbe5c8](https://linux-hardware.org/?probe=4ed7dbe5c8) | Nov 06, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [0bcdb10009](https://linux-hardware.org/?probe=0bcdb10009) | Nov 06, 2021 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [f0d8cb68f0](https://linux-hardware.org/?probe=f0d8cb68f0) | Nov 06, 2021 |
| Gigabyte      | GA-MA78GM-UD2H              | Desktop     | [ed6d77fb5b](https://linux-hardware.org/?probe=ed6d77fb5b) | Nov 06, 2021 |
| ASUSTek       | P5WD2                       | Desktop     | [e82d0dced2](https://linux-hardware.org/?probe=e82d0dced2) | Nov 06, 2021 |
| Samsung       | R59P/R60P/R61P              | Notebook    | [c04f0fcb02](https://linux-hardware.org/?probe=c04f0fcb02) | Nov 06, 2021 |
| MSI           | MS-7367                     | Desktop     | [6fcb312c9f](https://linux-hardware.org/?probe=6fcb312c9f) | Nov 05, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [67b99ebd43](https://linux-hardware.org/?probe=67b99ebd43) | Nov 05, 2021 |
| HP            | 82F2                        | Desktop     | [f8e717ec61](https://linux-hardware.org/?probe=f8e717ec61) | Nov 05, 2021 |
| ASUSTek       | X51R                        | Notebook    | [c49e03715c](https://linux-hardware.org/?probe=c49e03715c) | Nov 05, 2021 |
| ASRock        | N68-S                       | Desktop     | [49d6a34547](https://linux-hardware.org/?probe=49d6a34547) | Nov 04, 2021 |
| Acer          | Extensa 5230                | Notebook    | [ffaedf3579](https://linux-hardware.org/?probe=ffaedf3579) | Nov 04, 2021 |
| ASUSTek       | P5LD2-X                     | Desktop     | [856557708b](https://linux-hardware.org/?probe=856557708b) | Nov 04, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [f338aaec9f](https://linux-hardware.org/?probe=f338aaec9f) | Nov 04, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [94d9e3af73](https://linux-hardware.org/?probe=94d9e3af73) | Nov 04, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [5a4355a42b](https://linux-hardware.org/?probe=5a4355a42b) | Nov 04, 2021 |
| HP            | Pavilion dv6                | Notebook    | [461518c8a8](https://linux-hardware.org/?probe=461518c8a8) | Nov 03, 2021 |
| Lenovo        | NOK                         | Desktop     | [eee8c3a308](https://linux-hardware.org/?probe=eee8c3a308) | Nov 03, 2021 |
| MSI           | MS-7238                     | Desktop     | [8b91670469](https://linux-hardware.org/?probe=8b91670469) | Nov 03, 2021 |
| ASUSTek       | N60Dp                       | Notebook    | [011d08ddf4](https://linux-hardware.org/?probe=011d08ddf4) | Nov 03, 2021 |
| ASUSTek       | 2A73h                       | Desktop     | [a6c46734c1](https://linux-hardware.org/?probe=a6c46734c1) | Nov 03, 2021 |
| HP            | Pavilion dv7                | Notebook    | [991d13b12e](https://linux-hardware.org/?probe=991d13b12e) | Nov 03, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [6c197fdb65](https://linux-hardware.org/?probe=6c197fdb65) | Nov 02, 2021 |
| Gigabyte      | F2A55-DS3                   | Desktop     | [aae253ddac](https://linux-hardware.org/?probe=aae253ddac) | Nov 02, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [189d6ecf8f](https://linux-hardware.org/?probe=189d6ecf8f) | Nov 02, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [50e58a14b9](https://linux-hardware.org/?probe=50e58a14b9) | Nov 02, 2021 |
| ASUSTek       | P5L-MX                      | Desktop     | [746067cde3](https://linux-hardware.org/?probe=746067cde3) | Nov 02, 2021 |
| Acer          | Aspire 5630                 | Notebook    | [83204d14a3](https://linux-hardware.org/?probe=83204d14a3) | Nov 02, 2021 |
| ASUSTek       | M5A97 PRO                   | Desktop     | [a45bbdd2d0](https://linux-hardware.org/?probe=a45bbdd2d0) | Nov 01, 2021 |
| ASUSTek       | 1015PE                      | Notebook    | [c61a8ce57c](https://linux-hardware.org/?probe=c61a8ce57c) | Nov 01, 2021 |
| Intel         | powered classmate PC        | Notebook    | [dc59479961](https://linux-hardware.org/?probe=dc59479961) | Nov 01, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [9458cd71ea](https://linux-hardware.org/?probe=9458cd71ea) | Nov 01, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [500411363b](https://linux-hardware.org/?probe=500411363b) | Nov 01, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [4e56cc0e91](https://linux-hardware.org/?probe=4e56cc0e91) | Nov 01, 2021 |
| ASUSTek       | K50C                        | Notebook    | [99381074cf](https://linux-hardware.org/?probe=99381074cf) | Nov 01, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [ec1917e00c](https://linux-hardware.org/?probe=ec1917e00c) | Nov 01, 2021 |
| Samsung       | R425/R525                   | Notebook    | [cf2bc09886](https://linux-hardware.org/?probe=cf2bc09886) | Nov 01, 2021 |
| Lenovo        | ThinkCentre A55 89857DG     | Desktop     | [de9d0646da](https://linux-hardware.org/?probe=de9d0646da) | Oct 31, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [51862605ef](https://linux-hardware.org/?probe=51862605ef) | Oct 31, 2021 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [a0bd55a486](https://linux-hardware.org/?probe=a0bd55a486) | Oct 31, 2021 |
| ASUSTek       | M4A88T-M                    | Desktop     | [b820b810c9](https://linux-hardware.org/?probe=b820b810c9) | Oct 31, 2021 |
| Dell          | 0M859N A00                  | Desktop     | [3593cfb30c](https://linux-hardware.org/?probe=3593cfb30c) | Oct 31, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [d4f86565b3](https://linux-hardware.org/?probe=d4f86565b3) | Oct 30, 2021 |
| Gigabyte      | H61M-S2PH                   | Desktop     | [863c87266b](https://linux-hardware.org/?probe=863c87266b) | Oct 30, 2021 |
| MSI           | MS-7309                     | Desktop     | [0a4d7fb95d](https://linux-hardware.org/?probe=0a4d7fb95d) | Oct 30, 2021 |
| ASUSTek       | UL30A                       | Notebook    | [84f6267ad8](https://linux-hardware.org/?probe=84f6267ad8) | Oct 30, 2021 |
| HP            | Mini 110-3500               | Notebook    | [f696958f46](https://linux-hardware.org/?probe=f696958f46) | Oct 30, 2021 |
| MSI           | A320M PRO-VD/S              | Desktop     | [da176384c5](https://linux-hardware.org/?probe=da176384c5) | Oct 30, 2021 |
| Gigabyte      | F2A88X-D3HP                 | Desktop     | [15946036b1](https://linux-hardware.org/?probe=15946036b1) | Oct 30, 2021 |
| MSI           | G31TM-P35                   | Desktop     | [1157c2a82c](https://linux-hardware.org/?probe=1157c2a82c) | Oct 30, 2021 |
| MSI           | MS-7222                     | Desktop     | [ed7c7ab87d](https://linux-hardware.org/?probe=ed7c7ab87d) | Oct 30, 2021 |
| ASRock        | A780LM-S                    | Desktop     | [c96a2aa7a8](https://linux-hardware.org/?probe=c96a2aa7a8) | Oct 30, 2021 |
| ASUSTek       | UL30A                       | Notebook    | [283af13e5e](https://linux-hardware.org/?probe=283af13e5e) | Oct 30, 2021 |
| Gigabyte      | G41MT-S2                    | Desktop     | [f493a9d83b](https://linux-hardware.org/?probe=f493a9d83b) | Oct 29, 2021 |
| MSI           | CR61 2M/CX61 2OC/CX61 2O... | Notebook    | [532fd196d0](https://linux-hardware.org/?probe=532fd196d0) | Oct 29, 2021 |
| MSI           | A78M-E35                    | Desktop     | [69da26c946](https://linux-hardware.org/?probe=69da26c946) | Oct 29, 2021 |
| Shuttle       | FN78S V10                   | Desktop     | [6b6d198b0d](https://linux-hardware.org/?probe=6b6d198b0d) | Oct 29, 2021 |
| HP            | 1497                        | Desktop     | [9f4091c7ee](https://linux-hardware.org/?probe=9f4091c7ee) | Oct 29, 2021 |
| eMachines     | eME440                      | Notebook    | [1427ebffb0](https://linux-hardware.org/?probe=1427ebffb0) | Oct 29, 2021 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [b754c74b11](https://linux-hardware.org/?probe=b754c74b11) | Oct 29, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [b96d5d5fdc](https://linux-hardware.org/?probe=b96d5d5fdc) | Oct 28, 2021 |
| Gigabyte      | X79-UD3                     | Desktop     | [853e99eee4](https://linux-hardware.org/?probe=853e99eee4) | Oct 28, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [df0c058313](https://linux-hardware.org/?probe=df0c058313) | Oct 28, 2021 |
| Gigabyte      | P75-D3                      | Desktop     | [a223391bc0](https://linux-hardware.org/?probe=a223391bc0) | Oct 28, 2021 |
| Apple         | MacBookPro7,1               | Notebook    | [80e0b6af9e](https://linux-hardware.org/?probe=80e0b6af9e) | Oct 28, 2021 |
| Samsung       | NC110P/NC108P/NC111P        | Notebook    | [a83e302aba](https://linux-hardware.org/?probe=a83e302aba) | Oct 27, 2021 |
| Dell          | 0PGMR1 A00                  | All in one  | [04c5f1689d](https://linux-hardware.org/?probe=04c5f1689d) | Oct 27, 2021 |
| HP            | Mini 110-3700               | Notebook    | [c9d1b330a2](https://linux-hardware.org/?probe=c9d1b330a2) | Oct 27, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [1ac48c620e](https://linux-hardware.org/?probe=1ac48c620e) | Oct 27, 2021 |
| Dell          | 0M858N A00                  | Desktop     | [f27a29129f](https://linux-hardware.org/?probe=f27a29129f) | Oct 27, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [0f23350175](https://linux-hardware.org/?probe=0f23350175) | Oct 27, 2021 |
| ASRock        | H61M                        | Desktop     | [625a58f05c](https://linux-hardware.org/?probe=625a58f05c) | Oct 27, 2021 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [ce48b79fe7](https://linux-hardware.org/?probe=ce48b79fe7) | Oct 27, 2021 |
| Gigabyte      | Z87-HD3                     | Desktop     | [3934a7e59d](https://linux-hardware.org/?probe=3934a7e59d) | Oct 27, 2021 |
| Samsung       | R530/R730                   | Notebook    | [e872cab6ac](https://linux-hardware.org/?probe=e872cab6ac) | Oct 27, 2021 |
| Samsung       | R530/R730                   | Notebook    | [c8f8adc564](https://linux-hardware.org/?probe=c8f8adc564) | Oct 27, 2021 |
| ASUSTek       | P5L-MX                      | Desktop     | [d7fbb47c8b](https://linux-hardware.org/?probe=d7fbb47c8b) | Oct 27, 2021 |
| Lenovo        | B590 20206                  | Notebook    | [0b6699ecd2](https://linux-hardware.org/?probe=0b6699ecd2) | Oct 27, 2021 |
| Nvidia        | MCP7A 2                     | Desktop     | [5ca23cf3f6](https://linux-hardware.org/?probe=5ca23cf3f6) | Oct 26, 2021 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [f6de3176e5](https://linux-hardware.org/?probe=f6de3176e5) | Oct 26, 2021 |
| Intel         | X99                         | Desktop     | [f432ba24e0](https://linux-hardware.org/?probe=f432ba24e0) | Oct 26, 2021 |
| Packard Be... | EasyNote TJ71               | Notebook    | [85c9dd8233](https://linux-hardware.org/?probe=85c9dd8233) | Oct 26, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [452a28e8fa](https://linux-hardware.org/?probe=452a28e8fa) | Oct 25, 2021 |
| ASUSTek       | N56DP                       | Notebook    | [7332da68ec](https://linux-hardware.org/?probe=7332da68ec) | Oct 25, 2021 |
| ICL           | H410SB                      | Desktop     | [d6ae31e8d8](https://linux-hardware.org/?probe=d6ae31e8d8) | Oct 25, 2021 |
| Samsung       | R508                        | Notebook    | [89842bec44](https://linux-hardware.org/?probe=89842bec44) | Oct 25, 2021 |
| Compaq        | Presario CQ-25              | Notebook    | [ff46dc73d4](https://linux-hardware.org/?probe=ff46dc73d4) | Oct 25, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [c4df2d99ff](https://linux-hardware.org/?probe=c4df2d99ff) | Oct 25, 2021 |
| HP            | Notebook                    | Notebook    | [1963a09646](https://linux-hardware.org/?probe=1963a09646) | Oct 24, 2021 |
| Sony          | VGN-Z11VRN_B                | Notebook    | [87bd2c1cbf](https://linux-hardware.org/?probe=87bd2c1cbf) | Oct 24, 2021 |
| HP            | Pavilion 15                 | Notebook    | [e8585dc0d7](https://linux-hardware.org/?probe=e8585dc0d7) | Oct 24, 2021 |
| MSI           | 970A-G43                    | Desktop     | [e7042308e9](https://linux-hardware.org/?probe=e7042308e9) | Oct 24, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [d9956cac67](https://linux-hardware.org/?probe=d9956cac67) | Oct 24, 2021 |
| Acer          | Aspire A515-54G             | Notebook    | [fdbf1831d8](https://linux-hardware.org/?probe=fdbf1831d8) | Oct 24, 2021 |
| MSI           | H81M-E33                    | Desktop     | [33eafc06a0](https://linux-hardware.org/?probe=33eafc06a0) | Oct 24, 2021 |
| MSI           | H81M-E33                    | Desktop     | [24cc401b63](https://linux-hardware.org/?probe=24cc401b63) | Oct 24, 2021 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [cdd35d634d](https://linux-hardware.org/?probe=cdd35d634d) | Oct 24, 2021 |
| ASRock        | G31M-GS                     | Desktop     | [522367965d](https://linux-hardware.org/?probe=522367965d) | Oct 23, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [c29ee7ca9f](https://linux-hardware.org/?probe=c29ee7ca9f) | Oct 23, 2021 |
| HP            | 1905                        | Desktop     | [99b9973f19](https://linux-hardware.org/?probe=99b9973f19) | Oct 23, 2021 |
| MB            | A320-SF110                  | Desktop     | [e201a7d2d4](https://linux-hardware.org/?probe=e201a7d2d4) | Oct 23, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [23cdc0f5ac](https://linux-hardware.org/?probe=23cdc0f5ac) | Oct 23, 2021 |
| Dell          | Vostro 3559                 | Notebook    | [cbb0dc67de](https://linux-hardware.org/?probe=cbb0dc67de) | Oct 22, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [10c1e2b304](https://linux-hardware.org/?probe=10c1e2b304) | Oct 22, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [43eefcbf97](https://linux-hardware.org/?probe=43eefcbf97) | Oct 22, 2021 |
| Dell          | 0G679R                      | Desktop     | [e77852d5c2](https://linux-hardware.org/?probe=e77852d5c2) | Oct 22, 2021 |
| Lenovo        | B70-80 80MR                 | Notebook    | [fbc505d1bf](https://linux-hardware.org/?probe=fbc505d1bf) | Oct 22, 2021 |
| Acer          | WG43M                       | Desktop     | [f4e981b2c3](https://linux-hardware.org/?probe=f4e981b2c3) | Oct 22, 2021 |
| Samsung       | 300E5K/300E5Q               | Notebook    | [967d1d28ce](https://linux-hardware.org/?probe=967d1d28ce) | Oct 22, 2021 |
| HP            | Compaq CQ58                 | Notebook    | [553a61003f](https://linux-hardware.org/?probe=553a61003f) | Oct 21, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [fc6f79950a](https://linux-hardware.org/?probe=fc6f79950a) | Oct 21, 2021 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [97a2c9d098](https://linux-hardware.org/?probe=97a2c9d098) | Oct 21, 2021 |
| HP            | 86F0 11000                  | All in one  | [75738404ae](https://linux-hardware.org/?probe=75738404ae) | Oct 21, 2021 |
| ASUSTek       | P7H55                       | Desktop     | [22f632dfe5](https://linux-hardware.org/?probe=22f632dfe5) | Oct 21, 2021 |
| ASUSTek       | P7H55                       | Desktop     | [db15940c21](https://linux-hardware.org/?probe=db15940c21) | Oct 21, 2021 |
| HP            | 2820h                       | Desktop     | [eaa60f7610](https://linux-hardware.org/?probe=eaa60f7610) | Oct 21, 2021 |
| HP            | Presario CQ61               | Notebook    | [ce99148b7c](https://linux-hardware.org/?probe=ce99148b7c) | Oct 21, 2021 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [cedb153d12](https://linux-hardware.org/?probe=cedb153d12) | Oct 21, 2021 |
| Lenovo        | IdeaPad S12 20021,2959      | Notebook    | [d408de645f](https://linux-hardware.org/?probe=d408de645f) | Oct 21, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [bbabc93b07](https://linux-hardware.org/?probe=bbabc93b07) | Oct 21, 2021 |
| Dell          | 0M858N A00                  | Desktop     | [a473e9ed9c](https://linux-hardware.org/?probe=a473e9ed9c) | Oct 21, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [8ac4ec44b1](https://linux-hardware.org/?probe=8ac4ec44b1) | Oct 20, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [2e510be170](https://linux-hardware.org/?probe=2e510be170) | Oct 20, 2021 |
| HP            | Pavilion dv6                | Notebook    | [603a200096](https://linux-hardware.org/?probe=603a200096) | Oct 20, 2021 |
| Lenovo        | V580c 20160                 | Notebook    | [fbeb39e0ce](https://linux-hardware.org/?probe=fbeb39e0ce) | Oct 20, 2021 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [e7abad8af5](https://linux-hardware.org/?probe=e7abad8af5) | Oct 20, 2021 |
| HP            | 1497                        | Desktop     | [802f5fc90e](https://linux-hardware.org/?probe=802f5fc90e) | Oct 20, 2021 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [c64672a543](https://linux-hardware.org/?probe=c64672a543) | Oct 20, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [a031bfbdbf](https://linux-hardware.org/?probe=a031bfbdbf) | Oct 20, 2021 |
| Lenovo        | ThinkCentre M71e 3167A46    | Desktop     | [afc98aba09](https://linux-hardware.org/?probe=afc98aba09) | Oct 20, 2021 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [4b9b11b7b3](https://linux-hardware.org/?probe=4b9b11b7b3) | Oct 20, 2021 |
| Acer          | Aspire A315-33              | Notebook    | [ae05301ddc](https://linux-hardware.org/?probe=ae05301ddc) | Oct 19, 2021 |
| ASUSTek       | K53SV                       | Notebook    | [fc712846d9](https://linux-hardware.org/?probe=fc712846d9) | Oct 19, 2021 |
| ASUSTek       | PRIME H570-PLUS             | Desktop     | [da8850dc6a](https://linux-hardware.org/?probe=da8850dc6a) | Oct 19, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4aa0bd8b9f](https://linux-hardware.org/?probe=4aa0bd8b9f) | Oct 19, 2021 |
| Samsung       | R528/R728                   | Notebook    | [810ae66791](https://linux-hardware.org/?probe=810ae66791) | Oct 19, 2021 |
| MSI           | X370 GAMING PLUS            | Desktop     | [4574e23b8d](https://linux-hardware.org/?probe=4574e23b8d) | Oct 19, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [a34f4e81c4](https://linux-hardware.org/?probe=a34f4e81c4) | Oct 19, 2021 |
| Dell          | Inspiron 5748               | Notebook    | [989d9e52f7](https://linux-hardware.org/?probe=989d9e52f7) | Oct 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d6e67470ff](https://linux-hardware.org/?probe=d6e67470ff) | Oct 19, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [f1633c1e6c](https://linux-hardware.org/?probe=f1633c1e6c) | Oct 19, 2021 |
| Sony          | VGN-CR19VN_B                | Notebook    | [409f7c6aed](https://linux-hardware.org/?probe=409f7c6aed) | Oct 19, 2021 |
| Shuttle       | DS57U                       | Notebook    | [780ca9b317](https://linux-hardware.org/?probe=780ca9b317) | Oct 19, 2021 |
| MSI           | G41M-P28                    | Desktop     | [4ddbec0c08](https://linux-hardware.org/?probe=4ddbec0c08) | Oct 19, 2021 |
| ASUSTek       | X550CL                      | Notebook    | [3498166fa2](https://linux-hardware.org/?probe=3498166fa2) | Oct 19, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [ed5599f795](https://linux-hardware.org/?probe=ed5599f795) | Oct 19, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [112c9b533b](https://linux-hardware.org/?probe=112c9b533b) | Oct 19, 2021 |
| Gigabyte      | P35-DS3R                    | Desktop     | [01145b2627](https://linux-hardware.org/?probe=01145b2627) | Oct 18, 2021 |
| Intel         | X58 V1608                   | Desktop     | [0409a5bd94](https://linux-hardware.org/?probe=0409a5bd94) | Oct 18, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [891ec5c214](https://linux-hardware.org/?probe=891ec5c214) | Oct 18, 2021 |
| Medion        | BTDD-EAIO                   | All in one  | [f04d685411](https://linux-hardware.org/?probe=f04d685411) | Oct 18, 2021 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [b49fe0761b](https://linux-hardware.org/?probe=b49fe0761b) | Oct 18, 2021 |
| Lenovo        | B590 20206                  | Notebook    | [7ed2650105](https://linux-hardware.org/?probe=7ed2650105) | Oct 18, 2021 |
| iRU           | AraT                        | All in one  | [4ed51200e5](https://linux-hardware.org/?probe=4ed51200e5) | Oct 18, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [cfa532ddf3](https://linux-hardware.org/?probe=cfa532ddf3) | Oct 18, 2021 |
| HP            | 255 G1                      | Notebook    | [d37ee677e9](https://linux-hardware.org/?probe=d37ee677e9) | Oct 17, 2021 |
| Intel         | X79G V2.x                   | Desktop     | [6e4d8a1bd8](https://linux-hardware.org/?probe=6e4d8a1bd8) | Oct 17, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [f41f68a362](https://linux-hardware.org/?probe=f41f68a362) | Oct 17, 2021 |
| ASRock        | H410M-HVS                   | Desktop     | [e8b2ffaf8b](https://linux-hardware.org/?probe=e8b2ffaf8b) | Oct 17, 2021 |
| MSI           | GL65 9SEK                   | Notebook    | [fda8529760](https://linux-hardware.org/?probe=fda8529760) | Oct 17, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [b02ac47d33](https://linux-hardware.org/?probe=b02ac47d33) | Oct 17, 2021 |
| Lenovo        | B590 20206                  | Notebook    | [04f3e18b31](https://linux-hardware.org/?probe=04f3e18b31) | Oct 17, 2021 |
| Biostar       | N61PB-M2S                   | Desktop     | [e16a5113ba](https://linux-hardware.org/?probe=e16a5113ba) | Oct 17, 2021 |
| ASRock        | H61M-VS                     | Desktop     | [4520566497](https://linux-hardware.org/?probe=4520566497) | Oct 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3cd54cd42d](https://linux-hardware.org/?probe=3cd54cd42d) | Oct 16, 2021 |
| Gigabyte      | GB-BLPD-5005R               | Desktop     | [a973c7f319](https://linux-hardware.org/?probe=a973c7f319) | Oct 16, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [4e8f164e16](https://linux-hardware.org/?probe=4e8f164e16) | Oct 16, 2021 |
| eMachines     | eM350                       | Notebook    | [09b8fc981c](https://linux-hardware.org/?probe=09b8fc981c) | Oct 16, 2021 |
| MSI           | H110I PRO                   | Desktop     | [0aeac6b99e](https://linux-hardware.org/?probe=0aeac6b99e) | Oct 16, 2021 |
| Lenovo        | IdeaPad S205 Brazos         | Notebook    | [71753d9a10](https://linux-hardware.org/?probe=71753d9a10) | Oct 16, 2021 |
| ASRock        | G31M-GS                     | Desktop     | [595e5715a4](https://linux-hardware.org/?probe=595e5715a4) | Oct 16, 2021 |
| Biostar       | N61PB-M2S                   | Desktop     | [d17b2a3da0](https://linux-hardware.org/?probe=d17b2a3da0) | Oct 16, 2021 |
| HP            | 2B17                        | Desktop     | [e1d8985621](https://linux-hardware.org/?probe=e1d8985621) | Oct 16, 2021 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [044227e4ba](https://linux-hardware.org/?probe=044227e4ba) | Oct 15, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [1003b2549b](https://linux-hardware.org/?probe=1003b2549b) | Oct 15, 2021 |
| Lenovo        | 30C7 SDK0J40679 WIN 3273... | Desktop     | [f5a166e6a5](https://linux-hardware.org/?probe=f5a166e6a5) | Oct 15, 2021 |
| HP            | Pavilion dv6                | Notebook    | [2992dd1df0](https://linux-hardware.org/?probe=2992dd1df0) | Oct 15, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6b1d1f059f](https://linux-hardware.org/?probe=6b1d1f059f) | Oct 15, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [0e98fbf176](https://linux-hardware.org/?probe=0e98fbf176) | Oct 15, 2021 |
| Colorful T... | C.A68M-K PLUS V16           | Desktop     | [2b49043eeb](https://linux-hardware.org/?probe=2b49043eeb) | Oct 15, 2021 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [29e604d7dc](https://linux-hardware.org/?probe=29e604d7dc) | Oct 15, 2021 |
| ASRock        | 970 Extreme4                | Desktop     | [0a65b6d93e](https://linux-hardware.org/?probe=0a65b6d93e) | Oct 15, 2021 |
| MSI           | A320M PRO-VD/S              | Desktop     | [0699d95b3a](https://linux-hardware.org/?probe=0699d95b3a) | Oct 15, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [661f69eb29](https://linux-hardware.org/?probe=661f69eb29) | Oct 15, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [3b31ebd53c](https://linux-hardware.org/?probe=3b31ebd53c) | Oct 15, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [bf03c8601d](https://linux-hardware.org/?probe=bf03c8601d) | Oct 14, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [a8699be8c7](https://linux-hardware.org/?probe=a8699be8c7) | Oct 14, 2021 |
| Fujitsu Si... | D1561 S26361-D1561          | Desktop     | [467c3682c1](https://linux-hardware.org/?probe=467c3682c1) | Oct 13, 2021 |
| Lenovo        | ThinkPad T60p 200793G       | Notebook    | [cf747bee4e](https://linux-hardware.org/?probe=cf747bee4e) | Oct 13, 2021 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [ee0feeeab4](https://linux-hardware.org/?probe=ee0feeeab4) | Oct 13, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [889fddb7d8](https://linux-hardware.org/?probe=889fddb7d8) | Oct 13, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [498e89971e](https://linux-hardware.org/?probe=498e89971e) | Oct 13, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [987e9d49e0](https://linux-hardware.org/?probe=987e9d49e0) | Oct 13, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [08cda4fcb0](https://linux-hardware.org/?probe=08cda4fcb0) | Oct 13, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [3c6b489f05](https://linux-hardware.org/?probe=3c6b489f05) | Oct 13, 2021 |
| ASUSTek       | K52JT                       | Notebook    | [1013f2f693](https://linux-hardware.org/?probe=1013f2f693) | Oct 13, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [07e3892a07](https://linux-hardware.org/?probe=07e3892a07) | Oct 13, 2021 |
| Gigabyte      | GA-MA78GM-UD2H              | Desktop     | [5384254f8b](https://linux-hardware.org/?probe=5384254f8b) | Oct 13, 2021 |
| Acer          | Aspire A315-51              | Notebook    | [bfb1e33411](https://linux-hardware.org/?probe=bfb1e33411) | Oct 13, 2021 |
| ECS           | G31T-M7                     | Desktop     | [0f15dcbaa1](https://linux-hardware.org/?probe=0f15dcbaa1) | Oct 13, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [4d34b74685](https://linux-hardware.org/?probe=4d34b74685) | Oct 13, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [9e2728d4b4](https://linux-hardware.org/?probe=9e2728d4b4) | Oct 13, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [2ae59d9d7f](https://linux-hardware.org/?probe=2ae59d9d7f) | Oct 13, 2021 |
| Lenovo        | S40-70 80GQ                 | Notebook    | [5515480ed0](https://linux-hardware.org/?probe=5515480ed0) | Oct 13, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [d9d0dd7c3c](https://linux-hardware.org/?probe=d9d0dd7c3c) | Oct 13, 2021 |
| Acer          | AOHAPPY                     | Notebook    | [e12c8838c3](https://linux-hardware.org/?probe=e12c8838c3) | Oct 13, 2021 |
| Intel         | D946GZAB AAD66610-300       | Desktop     | [364790b01e](https://linux-hardware.org/?probe=364790b01e) | Oct 13, 2021 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [573399db2f](https://linux-hardware.org/?probe=573399db2f) | Oct 13, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [488dae59a1](https://linux-hardware.org/?probe=488dae59a1) | Oct 12, 2021 |
| HP            | 625                         | Notebook    | [adfe19c61c](https://linux-hardware.org/?probe=adfe19c61c) | Oct 12, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [a4da62f3ed](https://linux-hardware.org/?probe=a4da62f3ed) | Oct 12, 2021 |
| ASUSTek       | P5B-VM                      | Desktop     | [1207b5d281](https://linux-hardware.org/?probe=1207b5d281) | Oct 12, 2021 |
| ASUSTek       | P5B-VM                      | Desktop     | [8e9082cb5b](https://linux-hardware.org/?probe=8e9082cb5b) | Oct 12, 2021 |
| ASUSTek       | 1015BX                      | Notebook    | [95653b7969](https://linux-hardware.org/?probe=95653b7969) | Oct 12, 2021 |
| Acer          | Unknown                     | Notebook    | [b0b64ccb39](https://linux-hardware.org/?probe=b0b64ccb39) | Oct 11, 2021 |
| ASUSTek       | 1003HAG                     | Notebook    | [ffb279a366](https://linux-hardware.org/?probe=ffb279a366) | Oct 11, 2021 |
| ASUSTek       | P8H77-M LE                  | Desktop     | [faf35cb112](https://linux-hardware.org/?probe=faf35cb112) | Oct 11, 2021 |
| Acer          | Unknown                     | Notebook    | [0482a7e2cd](https://linux-hardware.org/?probe=0482a7e2cd) | Oct 11, 2021 |
| Unknown       | P4VM800                     | Desktop     | [a89ce27a40](https://linux-hardware.org/?probe=a89ce27a40) | Oct 11, 2021 |
| MSI           | G31M3-F V2                  | Desktop     | [df4ad3c0a7](https://linux-hardware.org/?probe=df4ad3c0a7) | Oct 11, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [251c4b666f](https://linux-hardware.org/?probe=251c4b666f) | Oct 11, 2021 |
| ASRock        | A520M Pro4                  | Desktop     | [e8beb09c69](https://linux-hardware.org/?probe=e8beb09c69) | Oct 11, 2021 |
| ASRock        | H410M-HVS                   | Desktop     | [179cd83878](https://linux-hardware.org/?probe=179cd83878) | Oct 11, 2021 |
| AQUARIUS      | AQH310CM                    | Desktop     | [c68ea41dca](https://linux-hardware.org/?probe=c68ea41dca) | Oct 11, 2021 |
| Apple         | MacBookAir4,2               | Notebook    | [a4f5d74cbf](https://linux-hardware.org/?probe=a4f5d74cbf) | Oct 10, 2021 |
| ASUSTek       | 901                         | Notebook    | [b8c2df18db](https://linux-hardware.org/?probe=b8c2df18db) | Oct 10, 2021 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [a421b58ebc](https://linux-hardware.org/?probe=a421b58ebc) | Oct 10, 2021 |
| Acer          | Veriton S2610G              | Desktop     | [88de86b5ff](https://linux-hardware.org/?probe=88de86b5ff) | Oct 10, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [4c64fde9dc](https://linux-hardware.org/?probe=4c64fde9dc) | Oct 10, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [5db93c72ad](https://linux-hardware.org/?probe=5db93c72ad) | Oct 10, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [0d8ca4adc7](https://linux-hardware.org/?probe=0d8ca4adc7) | Oct 10, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [fc9f6541dd](https://linux-hardware.org/?probe=fc9f6541dd) | Oct 09, 2021 |
| Toshiba       | Satellite C655              | Notebook    | [39f61ad9fd](https://linux-hardware.org/?probe=39f61ad9fd) | Oct 09, 2021 |
| ASUSTek       | M4N68T V2                   | Desktop     | [202302262c](https://linux-hardware.org/?probe=202302262c) | Oct 09, 2021 |
| Lenovo        | G580 20157                  | Notebook    | [36877dbfbd](https://linux-hardware.org/?probe=36877dbfbd) | Oct 09, 2021 |
| MSI           | B75MA-E33                   | Desktop     | [025212c8d0](https://linux-hardware.org/?probe=025212c8d0) | Oct 09, 2021 |
| MB            | A320-SF110                  | Desktop     | [d8fd0b4675](https://linux-hardware.org/?probe=d8fd0b4675) | Oct 09, 2021 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [d2a5ca4aca](https://linux-hardware.org/?probe=d2a5ca4aca) | Oct 09, 2021 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [270399bf0d](https://linux-hardware.org/?probe=270399bf0d) | Oct 09, 2021 |
| Acer          | Aspire C24-963              | All in one  | [9b4659e4dd](https://linux-hardware.org/?probe=9b4659e4dd) | Oct 09, 2021 |
| MSI           | A320M PRO-E                 | Desktop     | [2d1a36e7fe](https://linux-hardware.org/?probe=2d1a36e7fe) | Oct 09, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [610aac8c66](https://linux-hardware.org/?probe=610aac8c66) | Oct 08, 2021 |
| Unknown       | P4VM800                     | Desktop     | [7f085cdc02](https://linux-hardware.org/?probe=7f085cdc02) | Oct 08, 2021 |
| Toshiba       | Satellite U300              | Notebook    | [a8f19ba877](https://linux-hardware.org/?probe=a8f19ba877) | Oct 08, 2021 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [08e695107b](https://linux-hardware.org/?probe=08e695107b) | Oct 08, 2021 |
| Unknown       | Unknown                     | Desktop     | [5df5253cb3](https://linux-hardware.org/?probe=5df5253cb3) | Oct 08, 2021 |
| Acer          | AOD255                      | Notebook    | [a2032bb3cd](https://linux-hardware.org/?probe=a2032bb3cd) | Oct 07, 2021 |
| Acer          | M945G                       | Desktop     | [d7bc24b484](https://linux-hardware.org/?probe=d7bc24b484) | Oct 07, 2021 |
| ASUSTek       | P5K                         | Desktop     | [e65f644073](https://linux-hardware.org/?probe=e65f644073) | Oct 07, 2021 |
| ASUSTek       | P5W DH Deluxe               | Desktop     | [3a064bdf05](https://linux-hardware.org/?probe=3a064bdf05) | Oct 07, 2021 |
| Sony          | SVE1512G1RB                 | Notebook    | [5c87601314](https://linux-hardware.org/?probe=5c87601314) | Oct 07, 2021 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [54824f8998](https://linux-hardware.org/?probe=54824f8998) | Oct 07, 2021 |
| ASRock        | H410M-HVS                   | Desktop     | [746dd1395d](https://linux-hardware.org/?probe=746dd1395d) | Oct 07, 2021 |
| Lenovo        | H420                        | Desktop     | [846e0be845](https://linux-hardware.org/?probe=846e0be845) | Oct 07, 2021 |
| Quanta        | TWH                         | Notebook    | [b0e1ee9fdf](https://linux-hardware.org/?probe=b0e1ee9fdf) | Oct 06, 2021 |
| Acer          | Aspire C24-963              | All in one  | [215146c423](https://linux-hardware.org/?probe=215146c423) | Oct 06, 2021 |
| ASRock        | B450M-HDV                   | Desktop     | [7513f2e656](https://linux-hardware.org/?probe=7513f2e656) | Oct 06, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [4ff1c6afd0](https://linux-hardware.org/?probe=4ff1c6afd0) | Oct 06, 2021 |
| Toshiba       | Satellite U300              | Notebook    | [0354a4dbc4](https://linux-hardware.org/?probe=0354a4dbc4) | Oct 06, 2021 |
| Unknown       | Intel X79                   | Desktop     | [ecc9cf68cd](https://linux-hardware.org/?probe=ecc9cf68cd) | Oct 06, 2021 |
| eMachines     | E525                        | Notebook    | [c42d20565c](https://linux-hardware.org/?probe=c42d20565c) | Oct 06, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [6a714e7513](https://linux-hardware.org/?probe=6a714e7513) | Oct 06, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [d571076b6b](https://linux-hardware.org/?probe=d571076b6b) | Oct 05, 2021 |
| IBM           | 9210D7G                     | Desktop     | [2e1244832b](https://linux-hardware.org/?probe=2e1244832b) | Oct 05, 2021 |
| Samsung       | NC10                        | Notebook    | [341f7c60ed](https://linux-hardware.org/?probe=341f7c60ed) | Oct 05, 2021 |
| Toshiba       | Satellite U300              | Notebook    | [8536fdd650](https://linux-hardware.org/?probe=8536fdd650) | Oct 05, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [b99c6d022e](https://linux-hardware.org/?probe=b99c6d022e) | Oct 05, 2021 |
| ASRock        | A520M Pro4                  | Desktop     | [afedcb10fd](https://linux-hardware.org/?probe=afedcb10fd) | Oct 05, 2021 |
| HP            | Pavilion g7                 | Notebook    | [31a556cbe5](https://linux-hardware.org/?probe=31a556cbe5) | Oct 05, 2021 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [39482e36d6](https://linux-hardware.org/?probe=39482e36d6) | Oct 05, 2021 |
| MSI           | G41M-P28                    | Desktop     | [0fe41602c0](https://linux-hardware.org/?probe=0fe41602c0) | Oct 04, 2021 |
| ASUSTek       | K70ID                       | Notebook    | [ae8948a236](https://linux-hardware.org/?probe=ae8948a236) | Oct 04, 2021 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [b978be9281](https://linux-hardware.org/?probe=b978be9281) | Oct 04, 2021 |
| Samsung       | NC210/NC110                 | Notebook    | [d66ebd7a47](https://linux-hardware.org/?probe=d66ebd7a47) | Oct 04, 2021 |
| ASUSTek       | Leonite2                    | Desktop     | [48cebcd10c](https://linux-hardware.org/?probe=48cebcd10c) | Oct 03, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [c7c7306c5b](https://linux-hardware.org/?probe=c7c7306c5b) | Oct 03, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [d1b6f9621a](https://linux-hardware.org/?probe=d1b6f9621a) | Oct 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [8db9070723](https://linux-hardware.org/?probe=8db9070723) | Oct 03, 2021 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [3d18262d97](https://linux-hardware.org/?probe=3d18262d97) | Oct 03, 2021 |
| Lenovo        | NOK                         | Desktop     | [a78a7c1909](https://linux-hardware.org/?probe=a78a7c1909) | Oct 02, 2021 |
| ASUSTek       | P8H61-MX                    | Desktop     | [7aee651d14](https://linux-hardware.org/?probe=7aee651d14) | Oct 02, 2021 |
| Athermiter... | X99 Beta vk.com/@2485616    | Desktop     | [6006da0a12](https://linux-hardware.org/?probe=6006da0a12) | Oct 01, 2021 |
| ASUSTek       | F5RL                        | Notebook    | [e110aa6fe2](https://linux-hardware.org/?probe=e110aa6fe2) | Oct 01, 2021 |
| Gigabyte      | GA-MA790GP-DS4H             | Desktop     | [0614d7cbfc](https://linux-hardware.org/?probe=0614d7cbfc) | Oct 01, 2021 |
| Acer          | TravelMate P243             | Notebook    | [6ef5fcfb44](https://linux-hardware.org/?probe=6ef5fcfb44) | Oct 01, 2021 |
| Intel         | DG31PR AAD97573-203         | Desktop     | [c4a761604c](https://linux-hardware.org/?probe=c4a761604c) | Oct 01, 2021 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [6caab74a48](https://linux-hardware.org/?probe=6caab74a48) | Oct 01, 2021 |
| Intel         | H61M-S1                     | Desktop     | [ba0b4c102b](https://linux-hardware.org/?probe=ba0b4c102b) | Sep 30, 2021 |
| ASUSTek       | M4A77TD                     | Desktop     | [b50bdc7fc8](https://linux-hardware.org/?probe=b50bdc7fc8) | Sep 30, 2021 |
| ZoomSmart     | A1002                       | Tablet      | [07c752aa8c](https://linux-hardware.org/?probe=07c752aa8c) | Sep 30, 2021 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [0ae8b1a33a](https://linux-hardware.org/?probe=0ae8b1a33a) | Sep 30, 2021 |
| Gateway       | M-6307                      | Notebook    | [66d41efd4c](https://linux-hardware.org/?probe=66d41efd4c) | Sep 29, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [01291b303d](https://linux-hardware.org/?probe=01291b303d) | Sep 29, 2021 |
| Toshiba       | TECRA A9                    | Notebook    | [35e362031c](https://linux-hardware.org/?probe=35e362031c) | Sep 29, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [584658e9c3](https://linux-hardware.org/?probe=584658e9c3) | Sep 29, 2021 |
| ASUSTek       | K50IP                       | Notebook    | [75903baeac](https://linux-hardware.org/?probe=75903baeac) | Sep 29, 2021 |
| HP            | Mini 110-3700               | Notebook    | [0e84e432d9](https://linux-hardware.org/?probe=0e84e432d9) | Sep 29, 2021 |
| HP            | 86F0 11000                  | All in one  | [d94d1dcab2](https://linux-hardware.org/?probe=d94d1dcab2) | Sep 29, 2021 |
| Acer          | Aspire 7736                 | Notebook    | [24d3e1d1c0](https://linux-hardware.org/?probe=24d3e1d1c0) | Sep 28, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [cff8a7824e](https://linux-hardware.org/?probe=cff8a7824e) | Sep 28, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [27d8484dcf](https://linux-hardware.org/?probe=27d8484dcf) | Sep 28, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [c002c44040](https://linux-hardware.org/?probe=c002c44040) | Sep 27, 2021 |
| ASUSTek       | F9E                         | Notebook    | [b53c1fc258](https://linux-hardware.org/?probe=b53c1fc258) | Sep 27, 2021 |
| Acer          | F690GVM                     | Desktop     | [13957ded6b](https://linux-hardware.org/?probe=13957ded6b) | Sep 27, 2021 |
| ASRock        | A520M Pro4                  | Desktop     | [59abf22963](https://linux-hardware.org/?probe=59abf22963) | Sep 27, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [8c1b272056](https://linux-hardware.org/?probe=8c1b272056) | Sep 27, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [9ebf40dd91](https://linux-hardware.org/?probe=9ebf40dd91) | Sep 27, 2021 |
| Acer          | Aspire E1-531               | Notebook    | [348655ab4c](https://linux-hardware.org/?probe=348655ab4c) | Sep 27, 2021 |
| HP            | Pavilion dv6                | Notebook    | [ffc397f9f8](https://linux-hardware.org/?probe=ffc397f9f8) | Sep 26, 2021 |
| Gigabyte      | GA-MA790X-UD4               | Desktop     | [59d57fe423](https://linux-hardware.org/?probe=59d57fe423) | Sep 26, 2021 |
| Dell          | Latitude E6440              | Notebook    | [14a1218871](https://linux-hardware.org/?probe=14a1218871) | Sep 26, 2021 |
| Unknown       | Unknown                     | Desktop     | [d9560e08b8](https://linux-hardware.org/?probe=d9560e08b8) | Sep 26, 2021 |
| Acer          | AOD260                      | Notebook    | [4aa905f3b3](https://linux-hardware.org/?probe=4aa905f3b3) | Sep 26, 2021 |
| MSI           | 870-C45                     | Desktop     | [097e0980e6](https://linux-hardware.org/?probe=097e0980e6) | Sep 25, 2021 |
| ASUSTek       | P8H61-M LX2 R2.0            | Desktop     | [a20f0c2015](https://linux-hardware.org/?probe=a20f0c2015) | Sep 25, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [de58749699](https://linux-hardware.org/?probe=de58749699) | Sep 25, 2021 |
| MSI           | H61M-P31                    | Desktop     | [182415c8b2](https://linux-hardware.org/?probe=182415c8b2) | Sep 25, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [2e2134c3f2](https://linux-hardware.org/?probe=2e2134c3f2) | Sep 25, 2021 |
| Gigabyte      | EX58-UD5                    | Desktop     | [0623fe57da](https://linux-hardware.org/?probe=0623fe57da) | Sep 25, 2021 |
| Gigabyte      | EX58-UD5                    | Desktop     | [e45c27d6ae](https://linux-hardware.org/?probe=e45c27d6ae) | Sep 25, 2021 |
| ASRock        | P41C-DE                     | Desktop     | [1db6c915d2](https://linux-hardware.org/?probe=1db6c915d2) | Sep 24, 2021 |
| Acer          | Aspire A114-31              | Notebook    | [c36e4dcb54](https://linux-hardware.org/?probe=c36e4dcb54) | Sep 24, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [eec2ab619d](https://linux-hardware.org/?probe=eec2ab619d) | Sep 23, 2021 |
| Gigabyte      | G31M-S2C                    | Desktop     | [b1b87c83d5](https://linux-hardware.org/?probe=b1b87c83d5) | Sep 23, 2021 |
| Acer          | Aspire A114-31              | Notebook    | [61a139df2a](https://linux-hardware.org/?probe=61a139df2a) | Sep 23, 2021 |
| Unknown       | Unknown                     | Desktop     | [052a0c2ee7](https://linux-hardware.org/?probe=052a0c2ee7) | Sep 23, 2021 |
| MSI           | H61M-P31                    | Desktop     | [ad7fa9f2af](https://linux-hardware.org/?probe=ad7fa9f2af) | Sep 23, 2021 |
| Acer          | Aspire 5920                 | Notebook    | [d7c90eb05b](https://linux-hardware.org/?probe=d7c90eb05b) | Sep 23, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [3ad631da18](https://linux-hardware.org/?probe=3ad631da18) | Sep 23, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [1aa6ac8ca9](https://linux-hardware.org/?probe=1aa6ac8ca9) | Sep 23, 2021 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [78d7ad575a](https://linux-hardware.org/?probe=78d7ad575a) | Sep 22, 2021 |
| ASUSTek       | A6Je                        | Notebook    | [452e94323b](https://linux-hardware.org/?probe=452e94323b) | Sep 22, 2021 |
| Samsung       | R540/R580/R780/SA41/E452... | Notebook    | [a2ebb6a9f9](https://linux-hardware.org/?probe=a2ebb6a9f9) | Sep 22, 2021 |
| ASRock        | G31M-VS                     | Desktop     | [79a5ef3dad](https://linux-hardware.org/?probe=79a5ef3dad) | Sep 22, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [bf1f731b30](https://linux-hardware.org/?probe=bf1f731b30) | Sep 22, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [b2fc30d77f](https://linux-hardware.org/?probe=b2fc30d77f) | Sep 22, 2021 |
| MSI           | A320M PRO-E                 | Desktop     | [e3843e92d8](https://linux-hardware.org/?probe=e3843e92d8) | Sep 22, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [6840d01b98](https://linux-hardware.org/?probe=6840d01b98) | Sep 21, 2021 |
| ASRock        | P43DE3                      | Desktop     | [98b11d2398](https://linux-hardware.org/?probe=98b11d2398) | Sep 21, 2021 |
| ASRock        | P43DE3                      | Desktop     | [8fe21cf133](https://linux-hardware.org/?probe=8fe21cf133) | Sep 21, 2021 |
| Acer          | Aspire C22-760              | All in one  | [b4d0ad514d](https://linux-hardware.org/?probe=b4d0ad514d) | Sep 21, 2021 |
| Gigabyte      | Z87P-D3                     | Desktop     | [80b6244981](https://linux-hardware.org/?probe=80b6244981) | Sep 21, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [237ad3b201](https://linux-hardware.org/?probe=237ad3b201) | Sep 20, 2021 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [6930297e24](https://linux-hardware.org/?probe=6930297e24) | Sep 20, 2021 |
| HP            | 15                          | Notebook    | [d44c57c33b](https://linux-hardware.org/?probe=d44c57c33b) | Sep 20, 2021 |
| Samsung       | R460                        | Notebook    | [e5e235ff54](https://linux-hardware.org/?probe=e5e235ff54) | Sep 19, 2021 |
| eMachines     | E620                        | Notebook    | [b470708f29](https://linux-hardware.org/?probe=b470708f29) | Sep 18, 2021 |
| HP            | Pavilion m6                 | Notebook    | [c6f24d0ba4](https://linux-hardware.org/?probe=c6f24d0ba4) | Sep 17, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [4260037285](https://linux-hardware.org/?probe=4260037285) | Sep 17, 2021 |
| HP            | Laptop 15-ra0xx             | Notebook    | [663afde26f](https://linux-hardware.org/?probe=663afde26f) | Sep 17, 2021 |
| Acer          | Aspire 5530                 | Notebook    | [0326de1fc0](https://linux-hardware.org/?probe=0326de1fc0) | Sep 17, 2021 |
| Lenovo        | Unknown                     | Notebook    | [c344d683b4](https://linux-hardware.org/?probe=c344d683b4) | Sep 17, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [d0c64b1828](https://linux-hardware.org/?probe=d0c64b1828) | Sep 17, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [5dbfcf37a5](https://linux-hardware.org/?probe=5dbfcf37a5) | Sep 16, 2021 |
| ASUSTek       | Z97-A                       | Desktop     | [ecc945f2f9](https://linux-hardware.org/?probe=ecc945f2f9) | Sep 16, 2021 |
| ASUSTek       | P4P800-VM                   | Desktop     | [4284f4a0f3](https://linux-hardware.org/?probe=4284f4a0f3) | Sep 16, 2021 |
| ASUSTek       | P5KPL-AM EPU                | Desktop     | [1d25062113](https://linux-hardware.org/?probe=1d25062113) | Sep 16, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [8dd420ee26](https://linux-hardware.org/?probe=8dd420ee26) | Sep 15, 2021 |
| Acer          | Aspire V5-121               | Notebook    | [6e28d60f83](https://linux-hardware.org/?probe=6e28d60f83) | Sep 15, 2021 |
| Acer          | Aspire V5-121               | Notebook    | [f086d2f79f](https://linux-hardware.org/?probe=f086d2f79f) | Sep 15, 2021 |
| Sony          | SVE1512H1RW                 | Notebook    | [728c8bd8bb](https://linux-hardware.org/?probe=728c8bd8bb) | Sep 15, 2021 |
| ASUSTek       | P5KPL/1600                  | Desktop     | [4a92fad651](https://linux-hardware.org/?probe=4a92fad651) | Sep 15, 2021 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [3100e4c8bf](https://linux-hardware.org/?probe=3100e4c8bf) | Sep 15, 2021 |
| ASRock        | P43DE3                      | Desktop     | [a9ff01ecdd](https://linux-hardware.org/?probe=a9ff01ecdd) | Sep 15, 2021 |
| ASRock        | P43DE3                      | Desktop     | [dd167235b9](https://linux-hardware.org/?probe=dd167235b9) | Sep 15, 2021 |
| Acer          | Aspire C24-963              | All in one  | [01d4780c32](https://linux-hardware.org/?probe=01d4780c32) | Sep 14, 2021 |
| Gigabyte      | H77-DS3H                    | Desktop     | [5f504899b8](https://linux-hardware.org/?probe=5f504899b8) | Sep 14, 2021 |
| MSI           | 0AB8                        | Desktop     | [613aa45d0a](https://linux-hardware.org/?probe=613aa45d0a) | Sep 14, 2021 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [ee506588ee](https://linux-hardware.org/?probe=ee506588ee) | Sep 13, 2021 |
| MSI           | B360M PRO-VD                | Desktop     | [4672f48ccd](https://linux-hardware.org/?probe=4672f48ccd) | Sep 13, 2021 |
| Samsung       | R530/R730                   | Notebook    | [69fb51f097](https://linux-hardware.org/?probe=69fb51f097) | Sep 13, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [925dc425ce](https://linux-hardware.org/?probe=925dc425ce) | Sep 12, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [cbfc1612df](https://linux-hardware.org/?probe=cbfc1612df) | Sep 12, 2021 |
| Toshiba       | Satellite L850-D7W          | Notebook    | [e79a9bb4b6](https://linux-hardware.org/?probe=e79a9bb4b6) | Sep 12, 2021 |
| ASRock        | P43DE3                      | Desktop     | [6dec7059f1](https://linux-hardware.org/?probe=6dec7059f1) | Sep 12, 2021 |
| HP            | 18E4                        | Desktop     | [a862f30d46](https://linux-hardware.org/?probe=a862f30d46) | Sep 12, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [76a9293adc](https://linux-hardware.org/?probe=76a9293adc) | Sep 11, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [3714e570af](https://linux-hardware.org/?probe=3714e570af) | Sep 11, 2021 |
| Medion        | A17                         | Notebook    | [c5bbd083a4](https://linux-hardware.org/?probe=c5bbd083a4) | Sep 11, 2021 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [55cce80c82](https://linux-hardware.org/?probe=55cce80c82) | Sep 11, 2021 |
| HP            | Pavilion g6                 | Notebook    | [261221a1da](https://linux-hardware.org/?probe=261221a1da) | Sep 10, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [584c0b3409](https://linux-hardware.org/?probe=584c0b3409) | Sep 10, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [8f5d2dc657](https://linux-hardware.org/?probe=8f5d2dc657) | Sep 10, 2021 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [05acf7ad74](https://linux-hardware.org/?probe=05acf7ad74) | Sep 09, 2021 |
| HP            | ProBook 4515s               | Notebook    | [f421481ba4](https://linux-hardware.org/?probe=f421481ba4) | Sep 09, 2021 |
| HP            | ProBook 4515s               | Notebook    | [308aea486b](https://linux-hardware.org/?probe=308aea486b) | Sep 09, 2021 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [ecd516a1e0](https://linux-hardware.org/?probe=ecd516a1e0) | Sep 09, 2021 |
| ASRock        | N68C-GS UCC                 | Desktop     | [4448771bff](https://linux-hardware.org/?probe=4448771bff) | Sep 09, 2021 |
| ASUSTek       | P5QC                        | Desktop     | [fee02db17d](https://linux-hardware.org/?probe=fee02db17d) | Sep 08, 2021 |
| Clevo         | W251EFQ/W270EFQ             | Notebook    | [f195e85baa](https://linux-hardware.org/?probe=f195e85baa) | Sep 08, 2021 |
| MSI           | A68HM-P33 V2                | Desktop     | [8cf59588a3](https://linux-hardware.org/?probe=8cf59588a3) | Sep 08, 2021 |
| Gigabyte      | B450M S2H                   | Desktop     | [4fb11f7572](https://linux-hardware.org/?probe=4fb11f7572) | Sep 06, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [576b96b6da](https://linux-hardware.org/?probe=576b96b6da) | Sep 06, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [fded231b38](https://linux-hardware.org/?probe=fded231b38) | Sep 06, 2021 |
| Gigabyte      | M61PME-S2P                  | Desktop     | [d9c403ba71](https://linux-hardware.org/?probe=d9c403ba71) | Sep 06, 2021 |
| Samsung       | R508                        | Notebook    | [9e358e751b](https://linux-hardware.org/?probe=9e358e751b) | Sep 06, 2021 |
| Acer          | AOD270                      | Notebook    | [10ac46eefd](https://linux-hardware.org/?probe=10ac46eefd) | Sep 05, 2021 |
| Gigabyte      | H61M-S1                     | Desktop     | [7804dfb86b](https://linux-hardware.org/?probe=7804dfb86b) | Sep 05, 2021 |
| ASRock        | A520M Pro4                  | Desktop     | [5a93a4f276](https://linux-hardware.org/?probe=5a93a4f276) | Sep 05, 2021 |
| HP            | Pavilion 15                 | Notebook    | [9185255b98](https://linux-hardware.org/?probe=9185255b98) | Sep 05, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [8777411d8d](https://linux-hardware.org/?probe=8777411d8d) | Sep 04, 2021 |
| Dell          | Latitude D610               | Notebook    | [94c017baca](https://linux-hardware.org/?probe=94c017baca) | Sep 04, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | Desktop     | [85860b751d](https://linux-hardware.org/?probe=85860b751d) | Sep 04, 2021 |
| HP            | Compaq 610                  | Notebook    | [a8792baad7](https://linux-hardware.org/?probe=a8792baad7) | Sep 03, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [8125a944df](https://linux-hardware.org/?probe=8125a944df) | Sep 03, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [737644b609](https://linux-hardware.org/?probe=737644b609) | Sep 03, 2021 |
| MB            | A320-SF110                  | Desktop     | [51c7f8a1a1](https://linux-hardware.org/?probe=51c7f8a1a1) | Sep 03, 2021 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [00349ed993](https://linux-hardware.org/?probe=00349ed993) | Sep 02, 2021 |
| HP            | Pavilion dv6                | Notebook    | [db6f843983](https://linux-hardware.org/?probe=db6f843983) | Sep 02, 2021 |
| Samsung       | 450R4E/450R5E/450R4V/450... | Notebook    | [7a645d8ab0](https://linux-hardware.org/?probe=7a645d8ab0) | Sep 02, 2021 |
| Toshiba       | Satellite C655              | Notebook    | [1a24fad6d9](https://linux-hardware.org/?probe=1a24fad6d9) | Sep 02, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [e754e82729](https://linux-hardware.org/?probe=e754e82729) | Sep 02, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [48ef40abbf](https://linux-hardware.org/?probe=48ef40abbf) | Sep 02, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [1704e285e7](https://linux-hardware.org/?probe=1704e285e7) | Sep 02, 2021 |
| ASUSTek       | P5LD2-SE                    | Desktop     | [dc8736b161](https://linux-hardware.org/?probe=dc8736b161) | Sep 02, 2021 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [dbeb8785e6](https://linux-hardware.org/?probe=dbeb8785e6) | Sep 01, 2021 |
| Gigabyte      | 8I915P Pro                  | Desktop     | [7bcb8565d4](https://linux-hardware.org/?probe=7bcb8565d4) | Sep 01, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [a0f5403419](https://linux-hardware.org/?probe=a0f5403419) | Sep 01, 2021 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [1247b30f09](https://linux-hardware.org/?probe=1247b30f09) | Sep 01, 2021 |
| MB            | A320-SF110                  | Desktop     | [0ed6f00c34](https://linux-hardware.org/?probe=0ed6f00c34) | Sep 01, 2021 |
| HP            | 3031h                       | Desktop     | [9fc8c93cd1](https://linux-hardware.org/?probe=9fc8c93cd1) | Sep 01, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7456ab8ada](https://linux-hardware.org/?probe=7456ab8ada) | Sep 01, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [b96bbfe2d7](https://linux-hardware.org/?probe=b96bbfe2d7) | Aug 31, 2021 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [fd0ac9d6b1](https://linux-hardware.org/?probe=fd0ac9d6b1) | Aug 31, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [5e8d8b35df](https://linux-hardware.org/?probe=5e8d8b35df) | Aug 31, 2021 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [25278e9320](https://linux-hardware.org/?probe=25278e9320) | Aug 30, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [7a413c610e](https://linux-hardware.org/?probe=7a413c610e) | Aug 29, 2021 |
| ASUSTek       | K53BR                       | Notebook    | [989a6f27be](https://linux-hardware.org/?probe=989a6f27be) | Aug 29, 2021 |
| ASUSTek       | K52JU                       | Notebook    | [df8b34c73d](https://linux-hardware.org/?probe=df8b34c73d) | Aug 29, 2021 |
| ASUSTek       | M4A77T                      | Desktop     | [5854aabe6a](https://linux-hardware.org/?probe=5854aabe6a) | Aug 29, 2021 |
| Chuwi         | AeroBook                    | Notebook    | [b70d093b2f](https://linux-hardware.org/?probe=b70d093b2f) | Aug 29, 2021 |
| ASUSTek       | K54HR                       | Notebook    | [b03089591a](https://linux-hardware.org/?probe=b03089591a) | Aug 29, 2021 |
| ASUSTek       | M4A77T                      | Desktop     | [f59dbf2475](https://linux-hardware.org/?probe=f59dbf2475) | Aug 29, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [b14353bdc2](https://linux-hardware.org/?probe=b14353bdc2) | Aug 28, 2021 |
| Gigabyte      | MQHUDVI                     | All in one  | [dd512d1882](https://linux-hardware.org/?probe=dd512d1882) | Aug 28, 2021 |
| MSI           | 0A48                        | Desktop     | [c3443c43ee](https://linux-hardware.org/?probe=c3443c43ee) | Aug 28, 2021 |
| ASUSTek       | AM1I-A                      | Desktop     | [a854efaa0c](https://linux-hardware.org/?probe=a854efaa0c) | Aug 28, 2021 |
| ASUSTek       | A6Je                        | Notebook    | [c753f9d2cb](https://linux-hardware.org/?probe=c753f9d2cb) | Aug 28, 2021 |
| Samsung       | QX310/QX410/QX510/SF310/... | Notebook    | [5f9d928791](https://linux-hardware.org/?probe=5f9d928791) | Aug 27, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [dc8b19978f](https://linux-hardware.org/?probe=dc8b19978f) | Aug 27, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [b98982700d](https://linux-hardware.org/?probe=b98982700d) | Aug 27, 2021 |
| Acer          | Aspire 5100                 | Notebook    | [02bfe697f2](https://linux-hardware.org/?probe=02bfe697f2) | Aug 27, 2021 |
| HP            | 3396                        | Desktop     | [35b0f473e3](https://linux-hardware.org/?probe=35b0f473e3) | Aug 27, 2021 |
| ASUSTek       | P5K SE                      | Desktop     | [04d08cb6d2](https://linux-hardware.org/?probe=04d08cb6d2) | Aug 27, 2021 |
| Biostar       | A960D+V3                    | Desktop     | [f65660cdbe](https://linux-hardware.org/?probe=f65660cdbe) | Aug 26, 2021 |
| ASUSTek       | 1015B                       | Notebook    | [86fa6d91a6](https://linux-hardware.org/?probe=86fa6d91a6) | Aug 26, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [08f2cd37aa](https://linux-hardware.org/?probe=08f2cd37aa) | Aug 26, 2021 |
| ASRock        | G31M-VS                     | Desktop     | [ea71d93f96](https://linux-hardware.org/?probe=ea71d93f96) | Aug 26, 2021 |
| ASUSTek       | M2N68 Plus                  | Desktop     | [e8580758c1](https://linux-hardware.org/?probe=e8580758c1) | Aug 26, 2021 |
| Supermicro    | X11SSE-F                    | Mini pc     | [8d4cbf243d](https://linux-hardware.org/?probe=8d4cbf243d) | Aug 26, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [972245ac13](https://linux-hardware.org/?probe=972245ac13) | Aug 25, 2021 |
| ASUSTek       | M51Vr                       | Notebook    | [a1793e4cba](https://linux-hardware.org/?probe=a1793e4cba) | Aug 25, 2021 |
| OEM           | I41SI1                      | Notebook    | [5eb737349b](https://linux-hardware.org/?probe=5eb737349b) | Aug 25, 2021 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [56d031328b](https://linux-hardware.org/?probe=56d031328b) | Aug 25, 2021 |
| ASUSTek       | A6Je                        | Notebook    | [5875fd41c9](https://linux-hardware.org/?probe=5875fd41c9) | Aug 25, 2021 |
| HP            | 84DE                        | All in one  | [11f4f1348a](https://linux-hardware.org/?probe=11f4f1348a) | Aug 25, 2021 |
| HP            | 84DE                        | All in one  | [ba6157396c](https://linux-hardware.org/?probe=ba6157396c) | Aug 25, 2021 |
| HP            | Pavilion g6                 | Notebook    | [5ae6647c3e](https://linux-hardware.org/?probe=5ae6647c3e) | Aug 24, 2021 |
| Toshiba       | Satellite C650              | Notebook    | [80aa88bb5f](https://linux-hardware.org/?probe=80aa88bb5f) | Aug 24, 2021 |
| Intel         | H61M-S1                     | Desktop     | [46407e3bfe](https://linux-hardware.org/?probe=46407e3bfe) | Aug 24, 2021 |
| ASUSTek       | 1000HE                      | Notebook    | [523f51e980](https://linux-hardware.org/?probe=523f51e980) | Aug 24, 2021 |
| MSI           | G41M4                       | Desktop     | [84a631b3d1](https://linux-hardware.org/?probe=84a631b3d1) | Aug 24, 2021 |
| Gigabyte      | 8IPE1000-G                  | Desktop     | [68aa921622](https://linux-hardware.org/?probe=68aa921622) | Aug 23, 2021 |
| Unknown       | Intel X79                   | Desktop     | [ba70931b17](https://linux-hardware.org/?probe=ba70931b17) | Aug 23, 2021 |
| Dell          | Latitude E6430              | Notebook    | [1d8649d961](https://linux-hardware.org/?probe=1d8649d961) | Aug 23, 2021 |
| Acer          | Aspire A315-55G             | Notebook    | [3b94c6f7ae](https://linux-hardware.org/?probe=3b94c6f7ae) | Aug 23, 2021 |
| Acer          | Aspire 4736Z                | Notebook    | [a8d66e3be1](https://linux-hardware.org/?probe=a8d66e3be1) | Aug 23, 2021 |
| Huanan        | X99 F8D V2.2                | Desktop     | [baa9f58e33](https://linux-hardware.org/?probe=baa9f58e33) | Aug 22, 2021 |
| Aquarius      | Cmp NS585                   | Notebook    | [6a7a6fd29b](https://linux-hardware.org/?probe=6a7a6fd29b) | Aug 22, 2021 |
| HP            | 255 G3                      | Notebook    | [ac95ecc04e](https://linux-hardware.org/?probe=ac95ecc04e) | Aug 22, 2021 |
| ASRock        | AD510PV                     | Desktop     | [439a096e82](https://linux-hardware.org/?probe=439a096e82) | Aug 22, 2021 |
| Dell          | Inspiron M5110              | Notebook    | [fba36e8a9c](https://linux-hardware.org/?probe=fba36e8a9c) | Aug 22, 2021 |
| HP            | Notebook                    | Notebook    | [d5199840df](https://linux-hardware.org/?probe=d5199840df) | Aug 22, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | Notebook    | [e7f145f52b](https://linux-hardware.org/?probe=e7f145f52b) | Aug 21, 2021 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [ecee18882d](https://linux-hardware.org/?probe=ecee18882d) | Aug 21, 2021 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [e7cb77014b](https://linux-hardware.org/?probe=e7cb77014b) | Aug 21, 2021 |
| Notebook      | W65_67SB                    | Notebook    | [6b0450bc16](https://linux-hardware.org/?probe=6b0450bc16) | Aug 21, 2021 |
| Gigabyte      | H270-HD3-CF                 | Desktop     | [9bc00c1a22](https://linux-hardware.org/?probe=9bc00c1a22) | Aug 21, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [098bde6390](https://linux-hardware.org/?probe=098bde6390) | Aug 20, 2021 |
| ASUSTek       | M4A78LT-M-LE                | Desktop     | [3f52a340fb](https://linux-hardware.org/?probe=3f52a340fb) | Aug 20, 2021 |
| Gigabyte      | GA-780T-D3L                 | Desktop     | [5f22b29100](https://linux-hardware.org/?probe=5f22b29100) | Aug 20, 2021 |
| ASUSTek       | P8H61-M LX3                 | Desktop     | [51750fd3ff](https://linux-hardware.org/?probe=51750fd3ff) | Aug 19, 2021 |
| ASUSTek       | M2N                         | Desktop     | [feb08a099a](https://linux-hardware.org/?probe=feb08a099a) | Aug 19, 2021 |
| Dell          | Inspiron 5575               | Notebook    | [0972b616a0](https://linux-hardware.org/?probe=0972b616a0) | Aug 18, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [c358dfd2e6](https://linux-hardware.org/?probe=c358dfd2e6) | Aug 18, 2021 |
| ASUSTek       | M2N                         | Desktop     | [dc19fc7fd2](https://linux-hardware.org/?probe=dc19fc7fd2) | Aug 17, 2021 |
| MSI           | A68HM-P33 V2                | Desktop     | [50147690d8](https://linux-hardware.org/?probe=50147690d8) | Aug 17, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [9e04e05e9a](https://linux-hardware.org/?probe=9e04e05e9a) | Aug 16, 2021 |
| Toshiba       | Satellite M105              | Notebook    | [47e1c834e0](https://linux-hardware.org/?probe=47e1c834e0) | Aug 16, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [6f7d488d10](https://linux-hardware.org/?probe=6f7d488d10) | Aug 16, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [41fdc1fb70](https://linux-hardware.org/?probe=41fdc1fb70) | Aug 16, 2021 |
| Unknown       | T360D11                     | Desktop     | [ff09241a08](https://linux-hardware.org/?probe=ff09241a08) | Aug 16, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [3057301e6e](https://linux-hardware.org/?probe=3057301e6e) | Aug 16, 2021 |
| Toshiba       | Satellite M105              | Notebook    | [8b9be19e69](https://linux-hardware.org/?probe=8b9be19e69) | Aug 16, 2021 |
| ASUSTek       | K50IJ                       | Notebook    | [c43c7805a1](https://linux-hardware.org/?probe=c43c7805a1) | Aug 15, 2021 |
| MSI           | 870-C45                     | Desktop     | [d93f0fd195](https://linux-hardware.org/?probe=d93f0fd195) | Aug 15, 2021 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [931c0ec7c3](https://linux-hardware.org/?probe=931c0ec7c3) | Aug 15, 2021 |
| Biostar       | Hi-Fi A75S3                 | Desktop     | [f75bdb68fa](https://linux-hardware.org/?probe=f75bdb68fa) | Aug 14, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [1e977555fc](https://linux-hardware.org/?probe=1e977555fc) | Aug 14, 2021 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | Desktop     | [594b4ac16a](https://linux-hardware.org/?probe=594b4ac16a) | Aug 14, 2021 |
| HP            | ProLiant DL360 G5           | Server      | [b6088e88ba](https://linux-hardware.org/?probe=b6088e88ba) | Aug 14, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [b1bb6bfcaf](https://linux-hardware.org/?probe=b1bb6bfcaf) | Aug 14, 2021 |
| Intel         | DG31PR AAD97573-206         | Desktop     | [9c87bd51d2](https://linux-hardware.org/?probe=9c87bd51d2) | Aug 13, 2021 |
| ASUSTek       | P5B-MX/WiFi-AP              | Desktop     | [0036a1ec28](https://linux-hardware.org/?probe=0036a1ec28) | Aug 13, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [37acc42413](https://linux-hardware.org/?probe=37acc42413) | Aug 13, 2021 |
| ASUSTek       | P8H61-I                     | Desktop     | [df9f6bf9df](https://linux-hardware.org/?probe=df9f6bf9df) | Aug 13, 2021 |
| HP            | Notebook                    | Notebook    | [a7edab167a](https://linux-hardware.org/?probe=a7edab167a) | Aug 12, 2021 |
| Unknown       | Intel X79                   | Desktop     | [48fca9d39d](https://linux-hardware.org/?probe=48fca9d39d) | Aug 12, 2021 |
| Acer          | AOD270                      | Notebook    | [0c81349dd2](https://linux-hardware.org/?probe=0c81349dd2) | Aug 12, 2021 |
| Lenovo        | 3719 No DPK                 | All in one  | [6443ef9e75](https://linux-hardware.org/?probe=6443ef9e75) | Aug 12, 2021 |
| Lenovo        | 3719 No DPK                 | All in one  | [83bbc32997](https://linux-hardware.org/?probe=83bbc32997) | Aug 12, 2021 |
| ASUSTek       | X751LN                      | Notebook    | [c608a3b670](https://linux-hardware.org/?probe=c608a3b670) | Aug 12, 2021 |
| Dell          | 042P49 A00                  | Desktop     | [cc76d5eec6](https://linux-hardware.org/?probe=cc76d5eec6) | Aug 11, 2021 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | Desktop     | [b07993a438](https://linux-hardware.org/?probe=b07993a438) | Aug 11, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [188799420a](https://linux-hardware.org/?probe=188799420a) | Aug 11, 2021 |
| Sony          | VGN-FE11MR                  | Notebook    | [7c1f897bc6](https://linux-hardware.org/?probe=7c1f897bc6) | Aug 10, 2021 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [3f414f0c0c](https://linux-hardware.org/?probe=3f414f0c0c) | Aug 10, 2021 |
| Gigabyte      | P31-DS3L                    | Desktop     | [6b6744a8d3](https://linux-hardware.org/?probe=6b6744a8d3) | Aug 10, 2021 |
| ASUSTek       | N53Jg                       | Notebook    | [1ce5593104](https://linux-hardware.org/?probe=1ce5593104) | Aug 10, 2021 |
| Lenovo        | G550 20023                  | Notebook    | [d997251cee](https://linux-hardware.org/?probe=d997251cee) | Aug 09, 2021 |
| HP            | Mini 110-3000               | Notebook    | [f9f36e83c2](https://linux-hardware.org/?probe=f9f36e83c2) | Aug 09, 2021 |
| HP            | Notebook                    | Notebook    | [e7304a0193](https://linux-hardware.org/?probe=e7304a0193) | Aug 09, 2021 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [20990b5e3f](https://linux-hardware.org/?probe=20990b5e3f) | Aug 09, 2021 |
| Gigabyte      | 945GCM-S2C                  | Desktop     | [6ca0293f8e](https://linux-hardware.org/?probe=6ca0293f8e) | Aug 09, 2021 |
| MSI           | B360M PRO-VD 2019-01-24     | Desktop     | [8168eff4f5](https://linux-hardware.org/?probe=8168eff4f5) | Aug 08, 2021 |
| ASRock        | B75M-DGS                    | Desktop     | [b2b190475e](https://linux-hardware.org/?probe=b2b190475e) | Aug 08, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [a1901cec89](https://linux-hardware.org/?probe=a1901cec89) | Aug 08, 2021 |
| Unknown       | NF-CK804                    | Desktop     | [8df4832d94](https://linux-hardware.org/?probe=8df4832d94) | Aug 07, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [f7efc4e4e9](https://linux-hardware.org/?probe=f7efc4e4e9) | Aug 07, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [4d6f6eeb66](https://linux-hardware.org/?probe=4d6f6eeb66) | Aug 07, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [592e55045f](https://linux-hardware.org/?probe=592e55045f) | Aug 07, 2021 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [a149a51fb4](https://linux-hardware.org/?probe=a149a51fb4) | Aug 07, 2021 |
| Apple         | MacBookPro5,4               | Notebook    | [6ec15abd38](https://linux-hardware.org/?probe=6ec15abd38) | Aug 06, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [8dbfe8f85a](https://linux-hardware.org/?probe=8dbfe8f85a) | Aug 06, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [1743386c07](https://linux-hardware.org/?probe=1743386c07) | Aug 06, 2021 |
| Packard Be... | EasyNote LX                 | Notebook    | [125ad979fe](https://linux-hardware.org/?probe=125ad979fe) | Aug 06, 2021 |
| Dell          | Latitude D631               | Notebook    | [5414c974c3](https://linux-hardware.org/?probe=5414c974c3) | Aug 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [650ed8fe7a](https://linux-hardware.org/?probe=650ed8fe7a) | Aug 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [81f59d918f](https://linux-hardware.org/?probe=81f59d918f) | Aug 06, 2021 |
| Samsung       | QX310/QX410/QX510/SF310/... | Notebook    | [dda551c93b](https://linux-hardware.org/?probe=dda551c93b) | Aug 05, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [eb60e18ee8](https://linux-hardware.org/?probe=eb60e18ee8) | Aug 05, 2021 |
| ASUSTek       | P5E                         | Desktop     | [4689d6c169](https://linux-hardware.org/?probe=4689d6c169) | Aug 05, 2021 |
| eMachines     | E525                        | Notebook    | [411c80564c](https://linux-hardware.org/?probe=411c80564c) | Aug 05, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [a6011c35b9](https://linux-hardware.org/?probe=a6011c35b9) | Aug 05, 2021 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [14780d67bc](https://linux-hardware.org/?probe=14780d67bc) | Aug 05, 2021 |
| Unknown       | NF-CK804                    | Desktop     | [b99a60f54b](https://linux-hardware.org/?probe=b99a60f54b) | Aug 04, 2021 |
| ASUSTek       | P5Q SE PLUS                 | Desktop     | [4bde9c26aa](https://linux-hardware.org/?probe=4bde9c26aa) | Aug 04, 2021 |
| Biostar       | N68S3+                      | Desktop     | [1eae78eec0](https://linux-hardware.org/?probe=1eae78eec0) | Aug 04, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [ae3eabe5fa](https://linux-hardware.org/?probe=ae3eabe5fa) | Aug 03, 2021 |
| eMachines     | E525                        | Notebook    | [8412ffa356](https://linux-hardware.org/?probe=8412ffa356) | Aug 03, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [98fa6e0d50](https://linux-hardware.org/?probe=98fa6e0d50) | Aug 03, 2021 |
| ASUSTek       | K53U                        | Notebook    | [cab278f376](https://linux-hardware.org/?probe=cab278f376) | Aug 03, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [4cc68d302c](https://linux-hardware.org/?probe=4cc68d302c) | Aug 03, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [744c8e8d0b](https://linux-hardware.org/?probe=744c8e8d0b) | Aug 02, 2021 |
| Intel         | DP67BG AAG10491-306         | Desktop     | [dd9c81ab1b](https://linux-hardware.org/?probe=dd9c81ab1b) | Aug 02, 2021 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [515d1e0a9a](https://linux-hardware.org/?probe=515d1e0a9a) | Aug 02, 2021 |
| ASUSTek       | P5K                         | Desktop     | [c3fc0fa844](https://linux-hardware.org/?probe=c3fc0fa844) | Aug 02, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [ac8b80768e](https://linux-hardware.org/?probe=ac8b80768e) | Aug 01, 2021 |
| Samsung       | R425/R525                   | Notebook    | [c06e86048c](https://linux-hardware.org/?probe=c06e86048c) | Aug 01, 2021 |
| ASRock        | H410M-HVS                   | Desktop     | [730c16f8df](https://linux-hardware.org/?probe=730c16f8df) | Aug 01, 2021 |
| ECS           | G41T-M5                     | Desktop     | [5298d7a72e](https://linux-hardware.org/?probe=5298d7a72e) | Jul 31, 2021 |
| MSI           | G31M3-F V2                  | Desktop     | [db236f6287](https://linux-hardware.org/?probe=db236f6287) | Jul 31, 2021 |
| Samsung       | RV408/RV508                 | Notebook    | [20dabc5192](https://linux-hardware.org/?probe=20dabc5192) | Jul 31, 2021 |
| ASUSTek       | P8H61-M LE                  | Desktop     | [f4bfa36a7c](https://linux-hardware.org/?probe=f4bfa36a7c) | Jul 31, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [b6db9ab080](https://linux-hardware.org/?probe=b6db9ab080) | Jul 30, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [ea959bb531](https://linux-hardware.org/?probe=ea959bb531) | Jul 30, 2021 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [d50da9843f](https://linux-hardware.org/?probe=d50da9843f) | Jul 30, 2021 |
| Fujitsu       | D3003-B1 S26361-D3003-B1    | Desktop     | [4459cd023f](https://linux-hardware.org/?probe=4459cd023f) | Jul 29, 2021 |
| Gigabyte      | Z87-HD3                     | Desktop     | [c680f1b861](https://linux-hardware.org/?probe=c680f1b861) | Jul 29, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [5675901640](https://linux-hardware.org/?probe=5675901640) | Jul 29, 2021 |
| ASRock        | A520M Pro4                  | Desktop     | [f7d5fd707c](https://linux-hardware.org/?probe=f7d5fd707c) | Jul 29, 2021 |
| ASRock        | A520M Pro4                  | Desktop     | [ed45765bdf](https://linux-hardware.org/?probe=ed45765bdf) | Jul 29, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2d6df73c81](https://linux-hardware.org/?probe=2d6df73c81) | Jul 29, 2021 |
| ASUSTek       | UX31E                       | Notebook    | [af97b2b4d4](https://linux-hardware.org/?probe=af97b2b4d4) | Jul 29, 2021 |
| ASUSTek       | H61M-E                      | Desktop     | [d312398917](https://linux-hardware.org/?probe=d312398917) | Jul 29, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [d86a526a9b](https://linux-hardware.org/?probe=d86a526a9b) | Jul 28, 2021 |
| Samsung       | R540/R580/R780/SA41/E452... | Notebook    | [fad66ae632](https://linux-hardware.org/?probe=fad66ae632) | Jul 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [170a4660ae](https://linux-hardware.org/?probe=170a4660ae) | Jul 28, 2021 |
| Dell          | 0NK70N A04                  | Desktop     | [2b72ce131c](https://linux-hardware.org/?probe=2b72ce131c) | Jul 28, 2021 |
| ASUSTek       | X550WA                      | Notebook    | [cb1abeff8b](https://linux-hardware.org/?probe=cb1abeff8b) | Jul 28, 2021 |
| HP            | 81B7 0100                   | All in one  | [a0df6ba7d1](https://linux-hardware.org/?probe=a0df6ba7d1) | Jul 28, 2021 |
| Lenovo        | H420                        | Desktop     | [620b47fb12](https://linux-hardware.org/?probe=620b47fb12) | Jul 28, 2021 |
| Acer          | AO532h                      | Notebook    | [37a98643da](https://linux-hardware.org/?probe=37a98643da) | Jul 28, 2021 |
| Lenovo        | H420                        | Desktop     | [c5fb5791b7](https://linux-hardware.org/?probe=c5fb5791b7) | Jul 28, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [373daa5184](https://linux-hardware.org/?probe=373daa5184) | Jul 27, 2021 |
| HP            | 86F3 00100                  | All in one  | [fe1efbae85](https://linux-hardware.org/?probe=fe1efbae85) | Jul 27, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [4bb9a0e968](https://linux-hardware.org/?probe=4bb9a0e968) | Jul 27, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bf7b9902da](https://linux-hardware.org/?probe=bf7b9902da) | Jul 27, 2021 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [2495c9ce20](https://linux-hardware.org/?probe=2495c9ce20) | Jul 26, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [00b00de719](https://linux-hardware.org/?probe=00b00de719) | Jul 26, 2021 |
| Acer          | AOD270                      | Notebook    | [61e7dc1d25](https://linux-hardware.org/?probe=61e7dc1d25) | Jul 26, 2021 |
| Dell          | Latitude D631               | Notebook    | [0533727114](https://linux-hardware.org/?probe=0533727114) | Jul 26, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [c3b2be0c4a](https://linux-hardware.org/?probe=c3b2be0c4a) | Jul 26, 2021 |
| ASUSTek       | X540LJ                      | Notebook    | [a114c9634e](https://linux-hardware.org/?probe=a114c9634e) | Jul 25, 2021 |
| Dell          | Inspiron 1110               | Notebook    | [adcf60a5af](https://linux-hardware.org/?probe=adcf60a5af) | Jul 25, 2021 |
| Acer          | Aspire V3-771               | Notebook    | [0705cfcba0](https://linux-hardware.org/?probe=0705cfcba0) | Jul 25, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [c2407dc36c](https://linux-hardware.org/?probe=c2407dc36c) | Jul 25, 2021 |
| HP            | Pavilion dv9000 (EY797AV... | Notebook    | [f5fdb45e75](https://linux-hardware.org/?probe=f5fdb45e75) | Jul 25, 2021 |
| LG Electro... | S525-L.ACO1R1               | Notebook    | [0af3286dbd](https://linux-hardware.org/?probe=0af3286dbd) | Jul 25, 2021 |
| HP            | 1497                        | Desktop     | [56ad46b70d](https://linux-hardware.org/?probe=56ad46b70d) | Jul 24, 2021 |
| Gigabyte      | Z370 HD3-CF                 | Desktop     | [881292ae79](https://linux-hardware.org/?probe=881292ae79) | Jul 23, 2021 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [f162513c41](https://linux-hardware.org/?probe=f162513c41) | Jul 23, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [ef9eaa12bd](https://linux-hardware.org/?probe=ef9eaa12bd) | Jul 23, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [589b72e249](https://linux-hardware.org/?probe=589b72e249) | Jul 23, 2021 |
| Acer          | Extensa 7620                | Notebook    | [e0e9a2e532](https://linux-hardware.org/?probe=e0e9a2e532) | Jul 23, 2021 |
| Elenberg      | EL_T1011                    | Notebook    | [c2e05805b1](https://linux-hardware.org/?probe=c2e05805b1) | Jul 23, 2021 |
| Acer          | Aspire 5570Z                | Notebook    | [37e8699217](https://linux-hardware.org/?probe=37e8699217) | Jul 22, 2021 |
| MSI           | P67S-C43                    | Desktop     | [f0eb1cc19d](https://linux-hardware.org/?probe=f0eb1cc19d) | Jul 22, 2021 |
| ASUSTek       | P5Q-E                       | Desktop     | [1c195bc48a](https://linux-hardware.org/?probe=1c195bc48a) | Jul 22, 2021 |
| Acer          | MCP73PV NVIDIA MCP73        | Desktop     | [4aec616b4d](https://linux-hardware.org/?probe=4aec616b4d) | Jul 22, 2021 |
| HP            | Pavilion dv6                | Notebook    | [fa033b5868](https://linux-hardware.org/?probe=fa033b5868) | Jul 21, 2021 |
| Gigabyte      | 965P-S3                     | Desktop     | [27fef98e18](https://linux-hardware.org/?probe=27fef98e18) | Jul 21, 2021 |
| Samsung       | R560                        | Notebook    | [50521a5f62](https://linux-hardware.org/?probe=50521a5f62) | Jul 21, 2021 |
| Acer          | Aspire 7750                 | Notebook    | [1d55be6cb0](https://linux-hardware.org/?probe=1d55be6cb0) | Jul 21, 2021 |
| ASUSTek       | B75M-A                      | Desktop     | [25113d73cc](https://linux-hardware.org/?probe=25113d73cc) | Jul 21, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [36840dc5d4](https://linux-hardware.org/?probe=36840dc5d4) | Jul 20, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [51d593306a](https://linux-hardware.org/?probe=51d593306a) | Jul 20, 2021 |
| Acer          | Extensa 5620                | Notebook    | [dace11c2f2](https://linux-hardware.org/?probe=dace11c2f2) | Jul 20, 2021 |
| Lenovo        | B50-30 20382                | Notebook    | [000e3dcc67](https://linux-hardware.org/?probe=000e3dcc67) | Jul 20, 2021 |
| Acer          | AOA150                      | Notebook    | [013d358eb3](https://linux-hardware.org/?probe=013d358eb3) | Jul 20, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [995e947961](https://linux-hardware.org/?probe=995e947961) | Jul 19, 2021 |
| MSI           | H61M-P23                    | Desktop     | [4a4add18d1](https://linux-hardware.org/?probe=4a4add18d1) | Jul 19, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [1509516abe](https://linux-hardware.org/?probe=1509516abe) | Jul 19, 2021 |
| ASUSTek       | P6T SE                      | Desktop     | [9319f360bf](https://linux-hardware.org/?probe=9319f360bf) | Jul 19, 2021 |
| Gigabyte      | M61PM-S2                    | Desktop     | [f43de0121a](https://linux-hardware.org/?probe=f43de0121a) | Jul 19, 2021 |
| ASUSTek       | K54HR                       | Notebook    | [9466263a8a](https://linux-hardware.org/?probe=9466263a8a) | Jul 18, 2021 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [bec64317cc](https://linux-hardware.org/?probe=bec64317cc) | Jul 18, 2021 |
| ASUSTek       | Puffer                      | Desktop     | [70d79984df](https://linux-hardware.org/?probe=70d79984df) | Jul 18, 2021 |
| ASUSTek       | K53SC                       | Notebook    | [1db7dac3bd](https://linux-hardware.org/?probe=1db7dac3bd) | Jul 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f88958a5b9](https://linux-hardware.org/?probe=f88958a5b9) | Jul 17, 2021 |
| Acer          | Aspire 7720                 | Notebook    | [4c7c08aef4](https://linux-hardware.org/?probe=4c7c08aef4) | Jul 17, 2021 |
| HP            | 15                          | Notebook    | [fcc367258f](https://linux-hardware.org/?probe=fcc367258f) | Jul 17, 2021 |
| Acer          | Aspire 5930                 | Notebook    | [0701bfe1b5](https://linux-hardware.org/?probe=0701bfe1b5) | Jul 17, 2021 |
| MSI           | A320M-A PRO                 | Desktop     | [8ecc4ba8fc](https://linux-hardware.org/?probe=8ecc4ba8fc) | Jul 17, 2021 |
| Lenovo        | Unknown                     | Desktop     | [202578e326](https://linux-hardware.org/?probe=202578e326) | Jul 17, 2021 |
| Lenovo        | Unknown                     | Desktop     | [2834140b85](https://linux-hardware.org/?probe=2834140b85) | Jul 17, 2021 |
| Lenovo        | Unknown                     | Desktop     | [ddbbbdaf5a](https://linux-hardware.org/?probe=ddbbbdaf5a) | Jul 17, 2021 |
| ASUSTek       | M2N-MX                      | Desktop     | [ccf35bc529](https://linux-hardware.org/?probe=ccf35bc529) | Jul 17, 2021 |
| Samsung       | R520/R522/R620              | Notebook    | [ea92d28043](https://linux-hardware.org/?probe=ea92d28043) | Jul 16, 2021 |
| Toshiba       | Satellite A300              | Notebook    | [852c0d1233](https://linux-hardware.org/?probe=852c0d1233) | Jul 16, 2021 |
| Gigabyte      | H310M S2                    | Desktop     | [16f992ae46](https://linux-hardware.org/?probe=16f992ae46) | Jul 16, 2021 |
| ASUSTek       | M2N-MX                      | Desktop     | [2808a8e2ed](https://linux-hardware.org/?probe=2808a8e2ed) | Jul 16, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ab8b0d224b](https://linux-hardware.org/?probe=ab8b0d224b) | Jul 16, 2021 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [33706dadff](https://linux-hardware.org/?probe=33706dadff) | Jul 16, 2021 |
| Apple         | MacBookPro6,2               | Notebook    | [9e135cd0f7](https://linux-hardware.org/?probe=9e135cd0f7) | Jul 16, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2aeaab8842](https://linux-hardware.org/?probe=2aeaab8842) | Jul 15, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [8f825c43b5](https://linux-hardware.org/?probe=8f825c43b5) | Jul 15, 2021 |
| ASUSTek       | X751MD                      | Notebook    | [ed8bbb2836](https://linux-hardware.org/?probe=ed8bbb2836) | Jul 15, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [8430084f74](https://linux-hardware.org/?probe=8430084f74) | Jul 15, 2021 |
| Packard Be... | Cuba MS-7301                | Desktop     | [c3ac2909b9](https://linux-hardware.org/?probe=c3ac2909b9) | Jul 15, 2021 |
| ASUSTek       | P5Q TURBO                   | Desktop     | [571e42bf60](https://linux-hardware.org/?probe=571e42bf60) | Jul 15, 2021 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [7d86c66df2](https://linux-hardware.org/?probe=7d86c66df2) | Jul 15, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [06af94ba2d](https://linux-hardware.org/?probe=06af94ba2d) | Jul 15, 2021 |
| Lenovo        | G575 20081                  | Notebook    | [71e1fc252c](https://linux-hardware.org/?probe=71e1fc252c) | Jul 14, 2021 |
| MSI           | CR643                       | Notebook    | [939f7d4995](https://linux-hardware.org/?probe=939f7d4995) | Jul 14, 2021 |
| ASUSTek       | PRIME Z390M-PLUS            | Desktop     | [1f4a85bedb](https://linux-hardware.org/?probe=1f4a85bedb) | Jul 14, 2021 |
| ASUSTek       | PRIME A320M-R               | Desktop     | [53ccd50e56](https://linux-hardware.org/?probe=53ccd50e56) | Jul 13, 2021 |
| HP            | Mini 311-1000               | Notebook    | [0206e43dbf](https://linux-hardware.org/?probe=0206e43dbf) | Jul 13, 2021 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [7970cb8db9](https://linux-hardware.org/?probe=7970cb8db9) | Jul 13, 2021 |
| ASUSTek       | A7U                         | Notebook    | [1fd194d456](https://linux-hardware.org/?probe=1fd194d456) | Jul 13, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [b394b8edd3](https://linux-hardware.org/?probe=b394b8edd3) | Jul 12, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [76e94683d3](https://linux-hardware.org/?probe=76e94683d3) | Jul 12, 2021 |
| MSI           | 0AB8                        | Desktop     | [4599275ed5](https://linux-hardware.org/?probe=4599275ed5) | Jul 12, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [2ac11db77d](https://linux-hardware.org/?probe=2ac11db77d) | Jul 12, 2021 |
| Notebook      | W65_W670SR                  | Notebook    | [5bff5f7e4d](https://linux-hardware.org/?probe=5bff5f7e4d) | Jul 12, 2021 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [d87a7c8a0e](https://linux-hardware.org/?probe=d87a7c8a0e) | Jul 12, 2021 |
| eMachines     | eM355                       | Notebook    | [683517b03e](https://linux-hardware.org/?probe=683517b03e) | Jul 12, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [ae86521e87](https://linux-hardware.org/?probe=ae86521e87) | Jul 11, 2021 |
| Lenovo        | ThinkPad L430 24641J9       | Notebook    | [368b6ae06f](https://linux-hardware.org/?probe=368b6ae06f) | Jul 11, 2021 |
| ECS           | G43T-WM                     | Desktop     | [fdd73f0829](https://linux-hardware.org/?probe=fdd73f0829) | Jul 11, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [2a107b60a0](https://linux-hardware.org/?probe=2a107b60a0) | Jul 11, 2021 |
| HP            | Compaq 6730b (GB988EA)      | Notebook    | [ca4426ce30](https://linux-hardware.org/?probe=ca4426ce30) | Jul 11, 2021 |
| ASRock        | Z68 Extreme3 Gen3           | Desktop     | [33377199b8](https://linux-hardware.org/?probe=33377199b8) | Jul 10, 2021 |
| ASUSTek       | X75VCP                      | Notebook    | [711285e3d5](https://linux-hardware.org/?probe=711285e3d5) | Jul 10, 2021 |
| ASRock        | AB350M-HDV R3.0             | Desktop     | [9c9a2262f1](https://linux-hardware.org/?probe=9c9a2262f1) | Jul 10, 2021 |
| HP            | Pavilion TS 11              | Notebook    | [f0cb6206a5](https://linux-hardware.org/?probe=f0cb6206a5) | Jul 10, 2021 |
| ASUSTek       | P5WD2-Premium               | Desktop     | [9633075f87](https://linux-hardware.org/?probe=9633075f87) | Jul 10, 2021 |
| Foxconn       | RS690M2MA 0A                | Desktop     | [300bc10d1b](https://linux-hardware.org/?probe=300bc10d1b) | Jul 09, 2021 |
| Samsung       | NC10                        | Notebook    | [2ff4481ec4](https://linux-hardware.org/?probe=2ff4481ec4) | Jul 08, 2021 |
| Acer          | Extensa 2510G               | Notebook    | [85d6d83d4e](https://linux-hardware.org/?probe=85d6d83d4e) | Jul 08, 2021 |
| eMachines     | eM350                       | Notebook    | [1124de4983](https://linux-hardware.org/?probe=1124de4983) | Jul 08, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [09b9141e21](https://linux-hardware.org/?probe=09b9141e21) | Jul 08, 2021 |
| Dell          | Inspiron 3576               | Notebook    | [58572f3e5a](https://linux-hardware.org/?probe=58572f3e5a) | Jul 08, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [c8375fb45e](https://linux-hardware.org/?probe=c8375fb45e) | Jul 07, 2021 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [9b0cadb81e](https://linux-hardware.org/?probe=9b0cadb81e) | Jul 07, 2021 |
| ASUSTek       | P6T WS PRO                  | Desktop     | [1b2467601e](https://linux-hardware.org/?probe=1b2467601e) | Jul 07, 2021 |
| ASUSTek       | P5KPL-VM                    | Desktop     | [d4df40e320](https://linux-hardware.org/?probe=d4df40e320) | Jul 07, 2021 |
| eMachines     | eM355                       | Notebook    | [01a11f0163](https://linux-hardware.org/?probe=01a11f0163) | Jul 06, 2021 |
| Acer          | AOD260                      | Notebook    | [a583f0ada3](https://linux-hardware.org/?probe=a583f0ada3) | Jul 06, 2021 |
| eMachines     | eM350                       | Notebook    | [eb388a1fdb](https://linux-hardware.org/?probe=eb388a1fdb) | Jul 06, 2021 |
| Sony          | SVE1512N1RW                 | Notebook    | [9cfa353121](https://linux-hardware.org/?probe=9cfa353121) | Jul 05, 2021 |
| ASUSTek       | X501U                       | Notebook    | [0957e28187](https://linux-hardware.org/?probe=0957e28187) | Jul 05, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [436bd07287](https://linux-hardware.org/?probe=436bd07287) | Jul 05, 2021 |
| Samsung       | RV415/RV515/E3415           | Notebook    | [09ee8c08c7](https://linux-hardware.org/?probe=09ee8c08c7) | Jul 05, 2021 |
| Acer          | Aspire one                  | Notebook    | [d3201325ed](https://linux-hardware.org/?probe=d3201325ed) | Jul 05, 2021 |
| Gigabyte      | 945PLM-S2                   | Desktop     | [b3b4ebb5dd](https://linux-hardware.org/?probe=b3b4ebb5dd) | Jul 05, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [4e6f9ccc6c](https://linux-hardware.org/?probe=4e6f9ccc6c) | Jul 05, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [d7eba01877](https://linux-hardware.org/?probe=d7eba01877) | Jul 05, 2021 |
| Gigabyte      | 8I915P Duo                  | Desktop     | [c68136f956](https://linux-hardware.org/?probe=c68136f956) | Jul 04, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [fd1b061559](https://linux-hardware.org/?probe=fd1b061559) | Jul 04, 2021 |
| ASUSTek       | K54LY                       | Notebook    | [9346edd3b0](https://linux-hardware.org/?probe=9346edd3b0) | Jul 03, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [64beaec8c9](https://linux-hardware.org/?probe=64beaec8c9) | Jul 03, 2021 |
| HP            | Pavilion 15                 | Notebook    | [4ac1869d91](https://linux-hardware.org/?probe=4ac1869d91) | Jul 03, 2021 |
| MSI           | H81M-E33                    | Desktop     | [0357196534](https://linux-hardware.org/?probe=0357196534) | Jul 03, 2021 |
| HP            | 620                         | Notebook    | [d46db3418c](https://linux-hardware.org/?probe=d46db3418c) | Jul 02, 2021 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [c67bb7a1a9](https://linux-hardware.org/?probe=c67bb7a1a9) | Jul 02, 2021 |
| Biostar       | A10N-9830E                  | Desktop     | [64060930db](https://linux-hardware.org/?probe=64060930db) | Jul 02, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [7f54ec0331](https://linux-hardware.org/?probe=7f54ec0331) | Jul 02, 2021 |
| Samsung       | RV408/RV508                 | Notebook    | [9c6043e9e1](https://linux-hardware.org/?probe=9c6043e9e1) | Jul 01, 2021 |
| Gigabyte      | EP43-UD3L                   | Desktop     | [3b6839e225](https://linux-hardware.org/?probe=3b6839e225) | Jul 01, 2021 |
| ASUSTek       | P8H67                       | Desktop     | [7e70af0f39](https://linux-hardware.org/?probe=7e70af0f39) | Jul 01, 2021 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [574fbeb737](https://linux-hardware.org/?probe=574fbeb737) | Jul 01, 2021 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [27cbcf65f2](https://linux-hardware.org/?probe=27cbcf65f2) | Jul 01, 2021 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [546a5bb1a6](https://linux-hardware.org/?probe=546a5bb1a6) | Jul 01, 2021 |
| ASUSTek       | X75VCP                      | Notebook    | [542b38326d](https://linux-hardware.org/?probe=542b38326d) | Jul 01, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [aa6055e733](https://linux-hardware.org/?probe=aa6055e733) | Jun 30, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [a6ba20bd7c](https://linux-hardware.org/?probe=a6ba20bd7c) | Jun 30, 2021 |
| Lenovo        | ThinkPad T400 6474WPU       | Notebook    | [8625a3eb57](https://linux-hardware.org/?probe=8625a3eb57) | Jun 30, 2021 |
| Toshiba       | TECRA A9                    | Notebook    | [dfbfa7cede](https://linux-hardware.org/?probe=dfbfa7cede) | Jun 30, 2021 |
| HP            | Pavilion dv7                | Notebook    | [cd1d25fb69](https://linux-hardware.org/?probe=cd1d25fb69) | Jun 29, 2021 |
| Acer          | Aspire 5750ZG               | Notebook    | [629aa6ef43](https://linux-hardware.org/?probe=629aa6ef43) | Jun 29, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [060e8c4c6d](https://linux-hardware.org/?probe=060e8c4c6d) | Jun 29, 2021 |
| Gigabyte      | B75M-D3H                    | Desktop     | [9b4edd921b](https://linux-hardware.org/?probe=9b4edd921b) | Jun 29, 2021 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [9d315f40dd](https://linux-hardware.org/?probe=9d315f40dd) | Jun 29, 2021 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [ad42aba768](https://linux-hardware.org/?probe=ad42aba768) | Jun 28, 2021 |
| Intel         | H61M-S1                     | Desktop     | [10ef09acce](https://linux-hardware.org/?probe=10ef09acce) | Jun 28, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [15261fa935](https://linux-hardware.org/?probe=15261fa935) | Jun 27, 2021 |
| Samsung       | N150/N210/N220              | Notebook    | [cac30487cb](https://linux-hardware.org/?probe=cac30487cb) | Jun 27, 2021 |
| HP            | 21D0                        | Desktop     | [26ca3026ae](https://linux-hardware.org/?probe=26ca3026ae) | Jun 27, 2021 |
| Gigabyte      | E3000N                      | Desktop     | [676dc02757](https://linux-hardware.org/?probe=676dc02757) | Jun 27, 2021 |
| HP            | ZBook 14                    | Notebook    | [4ee6c8e056](https://linux-hardware.org/?probe=4ee6c8e056) | Jun 26, 2021 |
| Toshiba       | Satellite L775-A1W          | Notebook    | [33a641af5f](https://linux-hardware.org/?probe=33a641af5f) | Jun 26, 2021 |
| ASUSTek       | P5P41D                      | Desktop     | [7ddf671031](https://linux-hardware.org/?probe=7ddf671031) | Jun 26, 2021 |
| Lenovo        | IdeaPad S145-15IIL 81W8     | Notebook    | [0ea0ca4ac6](https://linux-hardware.org/?probe=0ea0ca4ac6) | Jun 26, 2021 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [d96aea9f90](https://linux-hardware.org/?probe=d96aea9f90) | Jun 26, 2021 |
| Biostar       | TA770E                      | Desktop     | [e91f400988](https://linux-hardware.org/?probe=e91f400988) | Jun 26, 2021 |
| ASRock        | J3355B-ITX                  | Desktop     | [a367138ddb](https://linux-hardware.org/?probe=a367138ddb) | Jun 26, 2021 |
| Acer          | Aspire 1551                 | Notebook    | [ce4a36f7f8](https://linux-hardware.org/?probe=ce4a36f7f8) | Jun 26, 2021 |
| Gigabyte      | E3000N                      | Desktop     | [e50a93669f](https://linux-hardware.org/?probe=e50a93669f) | Jun 26, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [9323ade702](https://linux-hardware.org/?probe=9323ade702) | Jun 26, 2021 |
| Foxconn       | 945 7AD Series              | Desktop     | [9a763d1e1e](https://linux-hardware.org/?probe=9a763d1e1e) | Jun 25, 2021 |
| ASUSTek       | M3A76-CM                    | Desktop     | [8e9ddfba30](https://linux-hardware.org/?probe=8e9ddfba30) | Jun 25, 2021 |
| Biostar       | NF520-A2 TE                 | Desktop     | [53072a0af9](https://linux-hardware.org/?probe=53072a0af9) | Jun 25, 2021 |
| Biostar       | NF520-A2 TE                 | Desktop     | [b5c0eda1f8](https://linux-hardware.org/?probe=b5c0eda1f8) | Jun 24, 2021 |
| ASUSTek       | K45DR                       | Notebook    | [c880f45738](https://linux-hardware.org/?probe=c880f45738) | Jun 24, 2021 |
| HP            | ProBook 440 G4              | Notebook    | [724aa7587e](https://linux-hardware.org/?probe=724aa7587e) | Jun 24, 2021 |
| HP            | ProBook 440 G4              | Notebook    | [c673467e71](https://linux-hardware.org/?probe=c673467e71) | Jun 24, 2021 |
| ASUSTek       | P4P800                      | Desktop     | [34311a4871](https://linux-hardware.org/?probe=34311a4871) | Jun 24, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [ffcdcab1a9](https://linux-hardware.org/?probe=ffcdcab1a9) | Jun 24, 2021 |
| ASUSTek       | N73SV                       | Notebook    | [38f9d7e8b1](https://linux-hardware.org/?probe=38f9d7e8b1) | Jun 23, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3b70bc8b9a](https://linux-hardware.org/?probe=3b70bc8b9a) | Jun 23, 2021 |
| Dell          | 06D7TR A00                  | Desktop     | [9d37088823](https://linux-hardware.org/?probe=9d37088823) | Jun 23, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E51... | Notebook    | [c406972730](https://linux-hardware.org/?probe=c406972730) | Jun 23, 2021 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [be30616f33](https://linux-hardware.org/?probe=be30616f33) | Jun 23, 2021 |
| Sony          | VPCEH1S1R                   | Notebook    | [96dd4b03c3](https://linux-hardware.org/?probe=96dd4b03c3) | Jun 22, 2021 |
| ASUSTek       | K56CB                       | Notebook    | [61afc9dd41](https://linux-hardware.org/?probe=61afc9dd41) | Jun 22, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [4f57c06051](https://linux-hardware.org/?probe=4f57c06051) | Jun 22, 2021 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [5e8534fc80](https://linux-hardware.org/?probe=5e8534fc80) | Jun 21, 2021 |
| ASUSTek       | A68HM-K                     | Desktop     | [b34ddd69c9](https://linux-hardware.org/?probe=b34ddd69c9) | Jun 21, 2021 |
| ASUSTek       | F5V                         | Notebook    | [d6a0692bae](https://linux-hardware.org/?probe=d6a0692bae) | Jun 20, 2021 |
| ASUSTek       | P8Z77-V PRO                 | Desktop     | [5c836091a7](https://linux-hardware.org/?probe=5c836091a7) | Jun 20, 2021 |
| Alienware     | 17                          | Notebook    | [542f46849c](https://linux-hardware.org/?probe=542f46849c) | Jun 20, 2021 |
| ASUSTek       | P9X79                       | Desktop     | [7c86a49663](https://linux-hardware.org/?probe=7c86a49663) | Jun 20, 2021 |
| Gigabyte      | B360M HD3                   | Desktop     | [435ed8b17a](https://linux-hardware.org/?probe=435ed8b17a) | Jun 20, 2021 |
| ASRock        | N68-VS3 UCC                 | Desktop     | [4e90b8e643](https://linux-hardware.org/?probe=4e90b8e643) | Jun 20, 2021 |
| ilife         | S806                        | Notebook    | [aa05451075](https://linux-hardware.org/?probe=aa05451075) | Jun 20, 2021 |
| HP            | Laptop 15-rb0xx             | Notebook    | [28d8f1272e](https://linux-hardware.org/?probe=28d8f1272e) | Jun 19, 2021 |
| Gigabyte      | GA-770T-USB3                | Desktop     | [ecf185efee](https://linux-hardware.org/?probe=ecf185efee) | Jun 19, 2021 |
| ASUSTek       | X51RL                       | Notebook    | [897edc4bdb](https://linux-hardware.org/?probe=897edc4bdb) | Jun 19, 2021 |
| ASUSTek       | X555LJ                      | Notebook    | [f94fcd505f](https://linux-hardware.org/?probe=f94fcd505f) | Jun 19, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8d86cdfbad](https://linux-hardware.org/?probe=8d86cdfbad) | Jun 19, 2021 |
| Lenovo        | ThinkPad L540 20AUS0DW00    | Notebook    | [a3e83938c3](https://linux-hardware.org/?probe=a3e83938c3) | Jun 19, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [53251cda1f](https://linux-hardware.org/?probe=53251cda1f) | Jun 18, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [44b174fec2](https://linux-hardware.org/?probe=44b174fec2) | Jun 18, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7e61f5d1e6](https://linux-hardware.org/?probe=7e61f5d1e6) | Jun 18, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [2e2fece47d](https://linux-hardware.org/?probe=2e2fece47d) | Jun 18, 2021 |
| Gigabyte      | H310M S2                    | Desktop     | [209ea9e009](https://linux-hardware.org/?probe=209ea9e009) | Jun 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [d069f181ac](https://linux-hardware.org/?probe=d069f181ac) | Jun 16, 2021 |
| ASUSTek       | P8B75-M LE                  | Desktop     | [ad17a21f6e](https://linux-hardware.org/?probe=ad17a21f6e) | Jun 16, 2021 |
| Dell          | Vostro 1000                 | Notebook    | [f8c1f4c020](https://linux-hardware.org/?probe=f8c1f4c020) | Jun 16, 2021 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [eef8cc869c](https://linux-hardware.org/?probe=eef8cc869c) | Jun 15, 2021 |
| MSI           | MS-7388                     | Desktop     | [f00c1908ad](https://linux-hardware.org/?probe=f00c1908ad) | Jun 15, 2021 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [cbffdf2c56](https://linux-hardware.org/?probe=cbffdf2c56) | Jun 15, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [d0e4206217](https://linux-hardware.org/?probe=d0e4206217) | Jun 14, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [f60d0c5b30](https://linux-hardware.org/?probe=f60d0c5b30) | Jun 14, 2021 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [25ace34c70](https://linux-hardware.org/?probe=25ace34c70) | Jun 14, 2021 |
| Lenovo        | NOK                         | Desktop     | [b474627724](https://linux-hardware.org/?probe=b474627724) | Jun 14, 2021 |
| Acer          | Aspire ES1-532G             | Notebook    | [be8aa07f5a](https://linux-hardware.org/?probe=be8aa07f5a) | Jun 14, 2021 |
| Dell          | 07K1DC A00                  | All in one  | [054f273240](https://linux-hardware.org/?probe=054f273240) | Jun 14, 2021 |
| Gigabyte      | GA-MA78GM-UD2H              | Desktop     | [02b585e8c0](https://linux-hardware.org/?probe=02b585e8c0) | Jun 14, 2021 |
| Acer          | Mandolin                    | Notebook    | [c5a4b06851](https://linux-hardware.org/?probe=c5a4b06851) | Jun 13, 2021 |
| Dell          | 0Y5DDC A00                  | Desktop     | [8d55100a23](https://linux-hardware.org/?probe=8d55100a23) | Jun 13, 2021 |
| Intel         | D945GNT AAC96315-405        | Desktop     | [6d87fe62c8](https://linux-hardware.org/?probe=6d87fe62c8) | Jun 13, 2021 |
| HP            | Notebook                    | Notebook    | [49ac1224d1](https://linux-hardware.org/?probe=49ac1224d1) | Jun 12, 2021 |
| eMachines     | E725                        | Notebook    | [f2272ab286](https://linux-hardware.org/?probe=f2272ab286) | Jun 12, 2021 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [88fb2527e3](https://linux-hardware.org/?probe=88fb2527e3) | Jun 12, 2021 |
| Sony          | VPCY216FD                   | Notebook    | [c3a77197c1](https://linux-hardware.org/?probe=c3a77197c1) | Jun 12, 2021 |
| Dell          | Inspiron ME051              | Notebook    | [b44f7a5cdb](https://linux-hardware.org/?probe=b44f7a5cdb) | Jun 11, 2021 |
| Acer          | Extensa 5635Z               | Notebook    | [18f9b41743](https://linux-hardware.org/?probe=18f9b41743) | Jun 11, 2021 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [8380ef5fcb](https://linux-hardware.org/?probe=8380ef5fcb) | Jun 11, 2021 |
| Gigabyte      | H81M-S1                     | Desktop     | [f6f52067a1](https://linux-hardware.org/?probe=f6f52067a1) | Jun 11, 2021 |
| HP            | 0A64h                       | Desktop     | [d684cffab5](https://linux-hardware.org/?probe=d684cffab5) | Jun 11, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [772b1f766d](https://linux-hardware.org/?probe=772b1f766d) | Jun 11, 2021 |
| Toshiba       | Satellite C660D             | Notebook    | [bc8685c579](https://linux-hardware.org/?probe=bc8685c579) | Jun 10, 2021 |
| ASUSTek       | X550EA                      | Notebook    | [71b07821f1](https://linux-hardware.org/?probe=71b07821f1) | Jun 10, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [ced0fe43f9](https://linux-hardware.org/?probe=ced0fe43f9) | Jun 10, 2021 |
| Gigabyte      | F2A55M-S1                   | Desktop     | [c924ff87cc](https://linux-hardware.org/?probe=c924ff87cc) | Jun 10, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [0c74b3a6cb](https://linux-hardware.org/?probe=0c74b3a6cb) | Jun 09, 2021 |
| Digma         | CITI E301 ES3008EW          | Notebook    | [bd19cdf69e](https://linux-hardware.org/?probe=bd19cdf69e) | Jun 09, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [2e162c78fb](https://linux-hardware.org/?probe=2e162c78fb) | Jun 09, 2021 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [7aa69ff82b](https://linux-hardware.org/?probe=7aa69ff82b) | Jun 09, 2021 |
| Acer          | TP-SW5-012-11EH             | Notebook    | [bf65a1a0c1](https://linux-hardware.org/?probe=bf65a1a0c1) | Jun 09, 2021 |
| Biostar       | Hi-Fi A70U3P                | Desktop     | [858dd464d9](https://linux-hardware.org/?probe=858dd464d9) | Jun 08, 2021 |
| MSI           | MS-7519                     | Desktop     | [0203405b2e](https://linux-hardware.org/?probe=0203405b2e) | Jun 08, 2021 |
| Biostar       | G31-M7 TE                   | Desktop     | [4f82a1cfe1](https://linux-hardware.org/?probe=4f82a1cfe1) | Jun 08, 2021 |
| Acer          | Aspire ES1-523              | Notebook    | [9ad7b323c7](https://linux-hardware.org/?probe=9ad7b323c7) | Jun 07, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [d6ce4db697](https://linux-hardware.org/?probe=d6ce4db697) | Jun 07, 2021 |
| HP            | Pavilion g6                 | Notebook    | [8c9a317bcf](https://linux-hardware.org/?probe=8c9a317bcf) | Jun 06, 2021 |
| Dell          | Inspiron 1525               | Notebook    | [f83d37571a](https://linux-hardware.org/?probe=f83d37571a) | Jun 06, 2021 |
| Acer          | WG43M                       | Desktop     | [f575dddee3](https://linux-hardware.org/?probe=f575dddee3) | Jun 06, 2021 |
| Acer          | AOD270                      | Notebook    | [b688b70a31](https://linux-hardware.org/?probe=b688b70a31) | Jun 06, 2021 |
| Samsung       | R460                        | Notebook    | [3017d2bfa6](https://linux-hardware.org/?probe=3017d2bfa6) | Jun 06, 2021 |
| ASUSTek       | H110M-C                     | Desktop     | [20c3f5040c](https://linux-hardware.org/?probe=20c3f5040c) | Jun 06, 2021 |
| Lenovo        | C200                        | All in one  | [11b9953715](https://linux-hardware.org/?probe=11b9953715) | Jun 05, 2021 |
| Intel         | E5 M2L-8D                   | Desktop     | [7cca14c70d](https://linux-hardware.org/?probe=7cca14c70d) | Jun 05, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [06198ed17c](https://linux-hardware.org/?probe=06198ed17c) | Jun 05, 2021 |
| NEC Comput... | SiS650                      | Desktop     | [a787298bdb](https://linux-hardware.org/?probe=a787298bdb) | Jun 05, 2021 |
| ASUSTek       | N73SV                       | Notebook    | [e5a41083d0](https://linux-hardware.org/?probe=e5a41083d0) | Jun 05, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [8047806178](https://linux-hardware.org/?probe=8047806178) | Jun 05, 2021 |
| Acer          | Extensa 2520G               | Notebook    | [920260f467](https://linux-hardware.org/?probe=920260f467) | Jun 05, 2021 |
| Dell          | Latitude E6510              | Notebook    | [7f86c73ee7](https://linux-hardware.org/?probe=7f86c73ee7) | Jun 04, 2021 |
| ICL           | RAYbook Si1514              | Notebook    | [e933cb5ff5](https://linux-hardware.org/?probe=e933cb5ff5) | Jun 04, 2021 |
| Lenovo        | G580                        | Notebook    | [b19f14193e](https://linux-hardware.org/?probe=b19f14193e) | Jun 03, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [0e6dfe4e9b](https://linux-hardware.org/?probe=0e6dfe4e9b) | Jun 03, 2021 |
| Sony          | VPCCW1S1R                   | Notebook    | [92bd24774d](https://linux-hardware.org/?probe=92bd24774d) | Jun 03, 2021 |
| ASRock        | 880GM-LE                    | Desktop     | [f6c59e217a](https://linux-hardware.org/?probe=f6c59e217a) | Jun 03, 2021 |
| HP            | Unknown                     | Notebook    | [73935c874b](https://linux-hardware.org/?probe=73935c874b) | Jun 02, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [d9bef668d6](https://linux-hardware.org/?probe=d9bef668d6) | Jun 02, 2021 |
| Foxconn       | H55M-S                      | Desktop     | [80857165cd](https://linux-hardware.org/?probe=80857165cd) | Jun 02, 2021 |
| Gigabyte      | B75-D3V                     | Desktop     | [017269b5ef](https://linux-hardware.org/?probe=017269b5ef) | Jun 02, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ROSA/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ROSA R10           | 4388      | 15.22%  |
| ROSA R11           | 4101      | 14.23%  |
| ROSA R8            | 3637      | 12.62%  |
| ROSA R6            | 3496      | 12.13%  |
| ROSA R7            | 3301      | 11.45%  |
| ROSA R8.1          | 2852      | 9.89%   |
| ROSA R9            | 2547      | 8.84%   |
| ROSA R11.1         | 2120      | 7.35%   |
| ROSA 12.2          | 971       | 3.37%   |
| ROSA R5            | 571       | 1.98%   |
| ROSA 12.1          | 302       | 1.05%   |
| ROSA 12            | 176       | 0.61%   |
| ROSA R4            | 121       | 0.42%   |
| ROSA R3            | 86        | 0.3%    |
| ROSA R12           | 71        | 0.25%   |
| ROSA 2019.05       | 19        | 0.07%   |
| ROSA R2            | 16        | 0.06%   |
| ROSA R9-R11        | 15        | 0.05%   |
| ROSA 2012.0        | 12        | 0.04%   |
| ROSA Chrome 2.0    | 7         | 0.02%   |
| ROSA R4-R8         | 4         | 0.01%   |
| ROSA DX 1.0        | 4         | 0.01%   |
| ROSA Nickel 2019.0 | 3         | 0.01%   |
| ROSA DX 2.0        | 2         | 0.01%   |
| ROSA 2019.0        | 2         | 0.01%   |
| ROSA SX 1.0        | 1         | 0.003%  |
| ROSA R1            | 1         | 0.003%  |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| ROSA | 23956     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 2052      | 6.6%    |
| 3.14.44-nrj-desktop-2rosa-x86_64    | 1866      | 6.01%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 1826      | 5.88%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 1791      | 5.76%   |
| 4.1.25-nrj-desktop-1rosa-x86_64     | 1600      | 5.15%   |
| 4.1.15-nrj-desktop-1rosa-x86_64     | 1381      | 4.44%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 1154      | 3.71%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 971       | 3.12%   |
| 3.14.44-nrj-desktop-2rosa-i586      | 833       | 2.68%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 782       | 2.52%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 697       | 2.24%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 647       | 2.08%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 580       | 1.87%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 548       | 1.76%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 505       | 1.63%   |
| 4.9.76-nrj-desktop-1rosa-x86_64     | 502       | 1.62%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 491       | 1.58%   |
| 4.1.16-nrj-desktop-1rosa-x86_64     | 463       | 1.49%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 457       | 1.47%   |
| 4.1.15-nrj-desktop-1rosa-i586       | 452       | 1.45%   |
| 4.15.0-desktop-45.1rosa-i586        | 447       | 1.44%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 446       | 1.44%   |
| 5.4.32-generic-2rosa-x86_64         | 409       | 1.32%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 395       | 1.27%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 379       | 1.22%   |
| 5.4.83-generic-2rosa-x86_64         | 361       | 1.16%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 340       | 1.09%   |
| 4.15.0-desktop-94.1rosa-x86_64      | 334       | 1.07%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 311       | 1%      |
| 4.1.38-nrj-desktop-2rosa-i586       | 278       | 0.89%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 270       | 0.87%   |
| 3.14.53-nrj-desktop-1rosa-x86_64    | 270       | 0.87%   |
| 4.1.22-nrj-desktop-2rosa-x86_64     | 258       | 0.83%   |
| 4.1.33-nrj-desktop-1rosa-x86_64     | 250       | 0.8%    |
| 4.15.0-desktop-60.7rosa-x86_64      | 228       | 0.73%   |
| 3.14.25-nrj-desktop-1rosa           | 219       | 0.7%    |
| 4.1.13-nrj-desktop-1rosa-x86_64     | 200       | 0.64%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 195       | 0.63%   |
| 3.14.33-nrj-desktop-1rosa           | 190       | 0.61%   |
| 4.9.124-nrj-desktop-1rosa-i586      | 189       | 0.61%   |
| 5.10.71-generic-1rosa2021.1-x86_64  | 169       | 0.54%   |
| 4.1.16-nrj-desktop-1rosa-i586       | 164       | 0.53%   |
| 4.1.38-nrj-desktop-1rosa-x86_64     | 158       | 0.51%   |
| 4.1.19-nrj-desktop-3rosa-x86_64     | 152       | 0.49%   |
| 4.9.155-nrj-desktop-1rosa-i586      | 151       | 0.49%   |
| 5.4.32-generic-2rosa-i586           | 142       | 0.46%   |
| 4.9.41-nrj-desktop-1rosa-i586       | 141       | 0.45%   |
| 4.1.19-nrj-desktop-2rosa-x86_64     | 138       | 0.44%   |
| 4.9.87-nrj-desktop-2rosa-x86_64     | 137       | 0.44%   |
| 4.9.76-nrj-desktop-1rosa-i586       | 131       | 0.42%   |
| 4.15.0-desktop-51.4rosa-x86_64      | 111       | 0.36%   |
| 3.14.53-nrj-desktop-1rosa-i586      | 107       | 0.34%   |
| 4.15.0-desktop-54.1rosa-x86_64      | 104       | 0.33%   |
| 4.1.22-nrj-desktop-2rosa-i586       | 101       | 0.33%   |
| 4.15.0-desktop-68.5rosa-i586        | 99        | 0.32%   |
| 4.1.13-nrj-desktop-1rosa-i586       | 98        | 0.32%   |
| 3.14.39-nrj-desktop-4rosa-x86_64    | 96        | 0.31%   |
| 5.4.40-generic-1rosa-x86_64         | 89        | 0.29%   |
| 4.15.0-desktop-47.2rosa-i586        | 89        | 0.29%   |
| 4.1.33-nrj-desktop-1rosa-i586       | 86        | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 4348      | 14.28%  |
| 3.14.44 | 2695      | 8.85%   |
| 4.9.60  | 2592      | 8.51%   |
| 4.9.20  | 2316      | 7.61%   |
| 4.1.25  | 2172      | 7.13%   |
| 4.1.15  | 1832      | 6.02%   |
| 4.1.34  | 1349      | 4.43%   |
| 5.10.74 | 1183      | 3.89%   |
| 4.1.38  | 1110      | 3.65%   |
| 4.9.9   | 1002      | 3.29%   |
| 4.9.124 | 973       | 3.2%    |
| 4.9.155 | 670       | 2.2%    |
| 4.9.76  | 638       | 2.1%    |
| 4.1.16  | 631       | 2.07%   |
| 4.9.41  | 589       | 1.93%   |
| 5.4.32  | 550       | 1.81%   |
| 5.4.83  | 447       | 1.47%   |
| 4.1.19  | 390       | 1.28%   |
| 3.14.53 | 387       | 1.27%   |
| 4.1.22  | 366       | 1.2%    |
| 4.9.95  | 339       | 1.11%   |
| 4.1.33  | 339       | 1.11%   |
| 4.1.13  | 305       | 1%      |
| 4.9.111 | 244       | 0.8%    |
| 3.14.25 | 222       | 0.73%   |
| 3.14.33 | 196       | 0.64%   |
| 4.9.87  | 174       | 0.57%   |
| 5.10.71 | 169       | 0.56%   |
| 3.14.39 | 134       | 0.44%   |
| 4.9.14  | 109       | 0.36%   |
| 5.4.40  | 104       | 0.34%   |
| 4.9.34  | 80        | 0.26%   |
| 4.13.0  | 79        | 0.26%   |
| 3.14.15 | 66        | 0.22%   |
| 3.14.22 | 59        | 0.19%   |
| 3.10.34 | 54        | 0.18%   |
| 5.0.0   | 53        | 0.17%   |
| 5.15.32 | 52        | 0.17%   |
| 4.4.1   | 50        | 0.16%   |
| 4.4.16  | 34        | 0.11%   |
| 4.1.10  | 34        | 0.11%   |
| 4.18.0  | 31        | 0.1%    |
| 4.16.18 | 30        | 0.1%    |
| 4.19.0  | 29        | 0.1%    |
| 5.4.72  | 26        | 0.09%   |
| 4.8.14  | 25        | 0.08%   |
| 4.1.6   | 23        | 0.08%   |
| 3.10.42 | 21        | 0.07%   |
| 4.8.17  | 19        | 0.06%   |
| 5.4.60  | 18        | 0.06%   |
| 4.9.7   | 18        | 0.06%   |
| 4.6.2   | 17        | 0.06%   |
| 4.1.4   | 17        | 0.06%   |
| 5.4.0   | 16        | 0.05%   |
| 4.9.5   | 16        | 0.05%   |
| 4.5.7   | 16        | 0.05%   |
| 4.1.3   | 16        | 0.05%   |
| 3.10.19 | 16        | 0.05%   |
| 5.10.56 | 15        | 0.05%   |
| 4.7.2   | 15        | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 8424      | 30.57%  |
| 4.1     | 7556      | 27.42%  |
| 4.15    | 4362      | 15.83%  |
| 3.14    | 3541      | 12.85%  |
| 5.10    | 1359      | 4.93%   |
| 5.4     | 1156      | 4.2%    |
| 4.4     | 150       | 0.54%   |
| 4.13    | 108       | 0.39%   |
| 3.10    | 101       | 0.37%   |
| 4.8     | 77        | 0.28%   |
| 5.0     | 57        | 0.21%   |
| 5.15    | 56        | 0.2%    |
| 4.0     | 48        | 0.17%   |
| 4.7     | 47        | 0.17%   |
| 4.6     | 46        | 0.17%   |
| 4.16    | 44        | 0.16%   |
| 4.19    | 41        | 0.15%   |
| 4.18    | 40        | 0.15%   |
| 3.18    | 38        | 0.14%   |
| 4.14    | 32        | 0.12%   |
| 4.3     | 27        | 0.1%    |
| 4.2     | 26        | 0.09%   |
| 4.5     | 24        | 0.09%   |
| 5.16    | 21        | 0.08%   |
| 4.17    | 21        | 0.08%   |
| 4.11    | 17        | 0.06%   |
| 4.12    | 15        | 0.05%   |
| 5.5     | 14        | 0.05%   |
| 3.0     | 14        | 0.05%   |
| 5.3     | 12        | 0.04%   |
| 5.2     | 12        | 0.04%   |
| 4.10    | 9         | 0.03%   |
| 3.17    | 9         | 0.03%   |
| 5.9     | 7         | 0.03%   |
| 5.8     | 7         | 0.03%   |
| 5.6     | 6         | 0.02%   |
| 3.19    | 6         | 0.02%   |
| 5.17    | 4         | 0.01%   |
| 5.11    | 4         | 0.01%   |
| 5.13    | 3         | 0.01%   |
| 3.15    | 3         | 0.01%   |
| 5.7     | 2         | 0.01%   |
| 4.20    | 2         | 0.01%   |
| 5.14    | 1         | 0.004%  |
| 5.12    | 1         | 0.004%  |
| 3.8     | 1         | 0.004%  |
| 3.12    | 1         | 0.004%  |
| 2.6     | 1         | 0.004%  |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 18565     | 75.62%  |
| i686    | 5982      | 24.37%  |
| aarch64 | 2         | 0.01%   |
| e2k     | 1         | 0.004%  |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE4       | 17982     | 69.98%  |
| KDE5       | 5467      | 21.28%  |
| GNOME      | 733       | 2.85%   |
| LXQt       | 682       | 2.65%   |
| MATE       | 355       | 1.38%   |
| XFCE       | 219       | 0.85%   |
| LXDE       | 164       | 0.64%   |
| Unknown    | 87        | 0.34%   |
| KDE        | 4         | 0.02%   |
| X-Cinnamon | 1         | 0.004%  |
| Budgie     | 1         | 0.004%  |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 23024     | 94.91%  |
| Wayland | 1221      | 5.03%   |
| Tty     | 11        | 0.05%   |
| Unknown | 2         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| KDM     | 18150     | 71.1%   |
| SDDM    | 6010      | 23.54%  |
| GDM     | 1156      | 4.53%   |
| TDM     | 115       | 0.45%   |
| LightDM | 60        | 0.24%   |
| XDM     | 19        | 0.07%   |
| Unknown | 14        | 0.05%   |
| LXDM    | 1         | 0.004%  |
| LDM     | 1         | 0.004%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| Unknown     | 21086     | 85.18%  |
| ru_RU       | 3186      | 12.87%  |
| en_US       | 117       | 0.47%   |
| pl_PL       | 65        | 0.26%   |
| de_DE       | 63        | 0.25%   |
| es_ES       | 37        | 0.15%   |
| pt_BR       | 32        | 0.13%   |
| fr_FR       | 30        | 0.12%   |
| en_GB       | 29        | 0.12%   |
| it_IT       | 25        | 0.1%    |
| ru_UA       | 20        | 0.08%   |
| ro_RO       | 7         | 0.03%   |
| pt_PT       | 6         | 0.02%   |
| C           | 5         | 0.02%   |
| cs_CZ       | 4         | 0.02%   |
| fr_BE       | 3         | 0.01%   |
| es_MX       | 3         | 0.01%   |
| es_AR       | 3         | 0.01%   |
| bg_BG       | 3         | 0.01%   |
| tr_TR       | 2         | 0.01%   |
| sk_SK       | 2         | 0.01%   |
| nl_NL       | 2         | 0.01%   |
| lv_LV       | 2         | 0.01%   |
| hu_HU       | 2         | 0.01%   |
| es_VE       | 2         | 0.01%   |
| es_PE       | 2         | 0.01%   |
| es_CO       | 2         | 0.01%   |
| en_IN       | 2         | 0.01%   |
| tt_RU       | 1         | 0.004%  |
| sv_SE       | 1         | 0.004%  |
| sr_RS@latin | 1         | 0.004%  |
| ru_BY       | 1         | 0.004%  |
| ja_JP       | 1         | 0.004%  |
| es_UY       | 1         | 0.004%  |
| en_AU       | 1         | 0.004%  |
| el_GR       | 1         | 0.004%  |
| de_AT       | 1         | 0.004%  |
| da_DK       | 1         | 0.004%  |
| ca_AD       | 1         | 0.004%  |
| be_BY       | 1         | 0.004%  |
| ar_DZ       | 1         | 0.004%  |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 19665     | 80.31%  |
| EFI  | 4821      | 19.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Unknown  | 16470     | 64.67%  |
| Ext4     | 8567      | 33.64%  |
| Btrfs    | 286       | 1.12%   |
| Ext3     | 64        | 0.25%   |
| Ext2     | 23        | 0.09%   |
| Xfs      | 19        | 0.07%   |
| Aufs     | 14        | 0.05%   |
| SAMSUNG  | 6         | 0.02%   |
| F2fs     | 6         | 0.02%   |
| Reiserfs | 4         | 0.02%   |
| Overlay  | 2         | 0.01%   |
| Jfs      | 1         | 0.004%  |
| Exfat    | 1         | 0.004%  |
| 2G       | 1         | 0.004%  |
| 20G      | 1         | 0.004%  |
| 12G      | 1         | 0.004%  |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| MBR     | 15649     | 60.64%  |
| Unknown | 5211      | 20.19%  |
| GPT     | 4948      | 19.17%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 22363     | 90.89%  |
| Yes       | 2242      | 9.11%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 20528     | 82.08%  |
| Yes       | 4481      | 17.92%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| ASUSTek Computer               | 6502      | 27.14%  |
| Gigabyte Technology            | 2786      | 11.63%  |
| Lenovo                         | 2051      | 8.56%   |
| Hewlett-Packard                | 1988      | 8.3%    |
| Acer                           | 1919      | 8.01%   |
| MSI                            | 1471      | 6.14%   |
| ASRock                         | 1351      | 5.64%   |
| Dell                           | 1028      | 4.29%   |
| Samsung Electronics            | 886       | 3.7%    |
| Toshiba                        | 455       | 1.9%    |
| Intel                          | 392       | 1.64%   |
| Sony                           | 305       | 1.27%   |
| ECS                            | 277       | 1.16%   |
| Packard Bell                   | 258       | 1.08%   |
| Unknown                        | 204       | 0.85%   |
| Biostar                        | 187       | 0.78%   |
| Pegatron                       | 177       | 0.74%   |
| eMachines                      | 170       | 0.71%   |
| Foxconn                        | 163       | 0.68%   |
| Fujitsu Siemens                | 109       | 0.46%   |
| Apple                          | 105       | 0.44%   |
| Notebook                       | 97        | 0.4%    |
| Clevo                          | 93        | 0.39%   |
| Fujitsu                        | 85        | 0.35%   |
| DNS                            | 49        | 0.2%    |
| Quanta                         | 39        | 0.16%   |
| Medion                         | 36        | 0.15%   |
| WinFast                        | 33        | 0.14%   |
| EPoX Computer                  | 32        | 0.13%   |
| DEXP                           | 29        | 0.12%   |
| AMI                            | 28        | 0.12%   |
| Supermicro                     | 24        | 0.1%    |
| Prestigio                      | 23        | 0.1%    |
| IBM                            | 22        | 0.09%   |
| Huanan                         | 20        | 0.08%   |
| Digma                          | 20        | 0.08%   |
| Irbis                          | 19        | 0.08%   |
| Nvidia                         | 18        | 0.08%   |
| ABIT                           | 18        | 0.08%   |
| LG Electronics                 | 15        | 0.06%   |
| Infomash                       | 15        | 0.06%   |
| Compal                         | 15        | 0.06%   |
| Alienware                      | 15        | 0.06%   |
| ZOTAC                          | 13        | 0.05%   |
| Insyde                         | 13        | 0.05%   |
| BenQ                           | 13        | 0.05%   |
| Shuttle                        | 12        | 0.05%   |
| SiS Technology                 | 11        | 0.05%   |
| Matsushita Electric Industrial | 11        | 0.05%   |
| Gateway                        | 11        | 0.05%   |
| Hampoo                         | 10        | 0.04%   |
| AMD                            | 10        | 0.04%   |
| JW Technology                  | 9         | 0.04%   |
| DEPO Computers                 | 9         | 0.04%   |
| Positivo                       | 7         | 0.03%   |
| OEM                            | 7         | 0.03%   |
| Compaq                         | 7         | 0.03%   |
| Chuwi                          | 7         | 0.03%   |
| Aquarius                       | 7         | 0.03%   |
| 3Q                             | 7         | 0.03%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| ASUS All Series                            | 339       | 1.42%   |
| Unknown                                    | 306       | 1.28%   |
| HP Pavilion g6                             | 170       | 0.71%   |
| HP Pavilion dv6                            | 105       | 0.44%   |
| ASUS M5A78L-M LX3                          | 73        | 0.3%    |
| MSI MS-7817                                | 72        | 0.3%    |
| HP Notebook                                | 70        | 0.29%   |
| Lenovo G570 20079                          | 65        | 0.27%   |
| ASRock G31M-S                              | 65        | 0.27%   |
| ASUS M5A97 R2.0                            | 63        | 0.26%   |
| Acer Aspire V3-571G                        | 61        | 0.25%   |
| Gigabyte 970A-DS3P                         | 59        | 0.25%   |
| ASRock N68C-S UCC                          | 58        | 0.24%   |
| MSI MS-7529                                | 56        | 0.23%   |
| Lenovo B590 20206                          | 54        | 0.23%   |
| Gigabyte H61M-S1                           | 54        | 0.23%   |
| Gigabyte G31M-ES2L                         | 54        | 0.23%   |
| MSI MS-7592                                | 53        | 0.22%   |
| ASUS P5K                                   | 51        | 0.21%   |
| Packard Bell EasyNote TE11HC               | 50        | 0.21%   |
| Lenovo G50-30 80G0                         | 50        | 0.21%   |
| HP Pavilion g7                             | 50        | 0.21%   |
| HP Pavilion dv7                            | 49        | 0.2%    |
| Lenovo G500 20236                          | 48        | 0.2%    |
| HP Pavilion 15                             | 47        | 0.2%    |
| ASUS P5B                                   | 47        | 0.2%    |
| ASUS P8Z77-V LX                            | 46        | 0.19%   |
| ASUS P5KPL-AM                              | 46        | 0.19%   |
| Dell Inspiron N5110                        | 45        | 0.19%   |
| ASUS M5A97 LE R2.0                         | 45        | 0.19%   |
| ASUS P8H61-M LX3 R2.0                      | 44        | 0.18%   |
| MSI MS-7788                                | 43        | 0.18%   |
| MSI MS-7309                                | 43        | 0.18%   |
| Lenovo G50-45 80E3                         | 43        | 0.18%   |
| ASUS P5G41T-M LX2/GB                       | 43        | 0.18%   |
| Acer Aspire 5750G                          | 42        | 0.18%   |
| ASUS P5KPL-AM IN/ROEM/SI                   | 41        | 0.17%   |
| MSI MS-7721                                | 40        | 0.17%   |
| MSI MS-7693                                | 40        | 0.17%   |
| Acer Aspire 5742G                          | 40        | 0.17%   |
| Toshiba Satellite C660                     | 38        | 0.16%   |
| ASRock G41M-VS3                            | 38        | 0.16%   |
| ASUS M5A78L-M/USB3                         | 37        | 0.15%   |
| ASUS K53U                                  | 37        | 0.15%   |
| MSI MS-7369                                | 36        | 0.15%   |
| Lenovo G580 20150                          | 36        | 0.15%   |
| HP G62                                     | 36        | 0.15%   |
| Gigabyte H61M-S2PV                         | 36        | 0.15%   |
| Gigabyte G41M-Combo                        | 36        | 0.15%   |
| ASUS X101CH                                | 36        | 0.15%   |
| ASUS SABERTOOTH 990FX R2.0                 | 36        | 0.15%   |
| ASUS H110M-R                               | 36        | 0.15%   |
| Lenovo G580 20157                          | 34        | 0.14%   |
| ASUS P5GC-MX/1333                          | 34        | 0.14%   |
| Samsung 300V3A/300V4A/300V5A/200A4B/200A5B | 33        | 0.14%   |
| Lenovo B570e HuronRiver Platform           | 33        | 0.14%   |
| HP Laptop 15-bw0xx                         | 33        | 0.14%   |
| HP 15                                      | 33        | 0.14%   |
| ASUS P5Q SE2                               | 33        | 0.14%   |
| ASUS K50IJ                                 | 33        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 1381      | 5.76%   |
| HP Pavilion           | 614       | 2.56%   |
| Dell Inspiron         | 469       | 1.96%   |
| Lenovo IdeaPad        | 435       | 1.82%   |
| Toshiba Satellite     | 411       | 1.72%   |
| ASUS All              | 339       | 1.42%   |
| Lenovo ThinkPad       | 338       | 1.41%   |
| HP Compaq             | 336       | 1.4%    |
| Unknown               | 306       | 1.28%   |
| Packard Bell EasyNote | 203       | 0.85%   |
| Dell Latitude         | 199       | 0.83%   |
| ASUS M5A78L-M         | 197       | 0.82%   |
| HP ProBook            | 182       | 0.76%   |
| ASUS P8H61-M          | 174       | 0.73%   |
| Acer Extensa          | 160       | 0.67%   |
| ASUS P5KPL-AM         | 152       | 0.63%   |
| ASUS PRIME            | 148       | 0.62%   |
| ASUS M5A97            | 147       | 0.61%   |
| ASUS P5K              | 136       | 0.57%   |
| Dell OptiPlex         | 135       | 0.56%   |
| ASUS P8Z77-V          | 127       | 0.53%   |
| ASUS P5G41T-M         | 115       | 0.48%   |
| ASUS P5Q              | 104       | 0.43%   |
| HP Laptop             | 98        | 0.41%   |
| Lenovo G580           | 96        | 0.4%    |
| Dell Vostro           | 94        | 0.39%   |
| HP EliteBook          | 92        | 0.38%   |
| Lenovo B590           | 89        | 0.37%   |
| Acer TravelMate       | 82        | 0.34%   |
| Lenovo ThinkCentre    | 73        | 0.3%    |
| MSI MS-7817           | 72        | 0.3%    |
| HP Notebook           | 70        | 0.29%   |
| Lenovo G570           | 66        | 0.28%   |
| ASRock G31M-S         | 65        | 0.27%   |
| ASUS SABERTOOTH       | 62        | 0.26%   |
| Gigabyte 970A-DS3P    | 60        | 0.25%   |
| ASRock N68C-S         | 60        | 0.25%   |
| MSI MS-7529           | 56        | 0.23%   |
| ASUS P5B              | 55        | 0.23%   |
| HP ENVY               | 54        | 0.23%   |
| Gigabyte H61M-S1      | 54        | 0.23%   |
| Gigabyte G31M-ES2L    | 54        | 0.23%   |
| Samsung 355V4C        | 53        | 0.22%   |
| MSI MS-7592           | 53        | 0.22%   |
| ASUS P5GC-MX          | 53        | 0.22%   |
| Lenovo G50-30         | 50        | 0.21%   |
| HP Presario           | 49        | 0.2%    |
| HP Mini               | 49        | 0.2%    |
| Lenovo G500           | 48        | 0.2%    |
| Fujitsu LIFEBOOK      | 47        | 0.2%    |
| ASUS VivoBook         | 47        | 0.2%    |
| Notebook W65          | 45        | 0.19%   |
| Lenovo G50-45         | 45        | 0.19%   |
| ASUS P8B75-M          | 45        | 0.19%   |
| ASRock 970            | 44        | 0.18%   |
| Samsung 300V3A        | 43        | 0.18%   |
| MSI MS-7788           | 43        | 0.18%   |
| MSI MS-7309           | 43        | 0.18%   |
| ASUS M2N-MX           | 42        | 0.18%   |
| Dell Precision        | 41        | 0.17%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 3508      | 14.64%  |
| 2011    | 3257      | 13.6%   |
| 2010    | 2658      | 11.1%   |
| 2009    | 2264      | 9.45%   |
| 2013    | 2094      | 8.74%   |
| 2008    | 2030      | 8.47%   |
| 2007    | 1891      | 7.89%   |
| 2014    | 1288      | 5.38%   |
| 2006    | 1057      | 4.41%   |
| 2015    | 897       | 3.74%   |
| 2016    | 773       | 3.23%   |
| 2017    | 536       | 2.24%   |
| 2018    | 530       | 2.21%   |
| 2005    | 413       | 1.72%   |
| 2019    | 235       | 0.98%   |
| 2004    | 146       | 0.61%   |
| 2020    | 136       | 0.57%   |
| 2021    | 92        | 0.38%   |
| 2003    | 79        | 0.33%   |
| Unknown | 46        | 0.19%   |
| 2002    | 15        | 0.06%   |
| 2022    | 5         | 0.02%   |
| 2001    | 5         | 0.02%   |
| 2000    | 1         | 0.004%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 12122     | 50.6%   |
| Notebook       | 11405     | 47.61%  |
| All in one     | 219       | 0.91%   |
| Mini pc        | 108       | 0.45%   |
| Tablet         | 44        | 0.18%   |
| Server         | 33        | 0.14%   |
| Convertible    | 21        | 0.09%   |
| Stick pc       | 2         | 0.01%   |
| System on chip | 2         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 23954     | 99.98%  |
| Enabled  | 5         | 0.02%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 23949     | 99.97%  |
| Yes  | 7         | 0.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 8589      | 34.03%  |
| 8.01-16.0       | 4047      | 16.04%  |
| 4.01-8.0        | 3850      | 15.26%  |
| 1.01-2.0        | 3471      | 13.75%  |
| 2.01-3.0        | 2574      | 10.2%   |
| 16.01-24.0      | 1250      | 4.95%   |
| 0.51-1.0        | 735       | 2.91%   |
| Unknown         | 380       | 1.51%   |
| 32.01-64.0      | 209       | 0.83%   |
| 24.01-32.0      | 67        | 0.27%   |
| 0.01-0.5        | 38        | 0.15%   |
| 64.01-256.0     | 23        | 0.09%   |
| More than 256.0 | 3         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 13172     | 47.64%  |
| 1.01-2.0   | 10520     | 38.05%  |
| 2.01-3.0   | 1691      | 6.12%   |
| 0.01-0.5   | 1129      | 4.08%   |
| Unknown    | 447       | 1.62%   |
| 3.01-4.0   | 398       | 1.44%   |
| 4.01-8.0   | 261       | 0.94%   |
| 8.01-16.0  | 24        | 0.09%   |
| 16.01-24.0 | 5         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 16736     | 66.17%  |
| 2       | 5736      | 22.68%  |
| 3       | 1787      | 7.06%   |
| 4       | 536       | 2.12%   |
| 5       | 197       | 0.78%   |
| 0       | 195       | 0.77%   |
| 6       | 70        | 0.28%   |
| 7       | 14        | 0.06%   |
| Unknown | 10        | 0.04%   |
| 8       | 9         | 0.04%   |
| 9       | 4         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 16464     | 67.07%  |
| No        | 8083      | 32.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 23294     | 97.18%  |
| No        | 675       | 2.82%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 14427     | 59.52%  |
| No        | 9810      | 40.48%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 16231     | 66.64%  |
| Yes       | 8126      | 33.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Russia       | 13062     | 51.57%  |
| Unknown      | 8003      | 31.6%   |
| Ukraine      | 1041      | 4.11%   |
| Belarus      | 391       | 1.54%   |
| Germany      | 325       | 1.28%   |
| Poland       | 319       | 1.26%   |
| Kazakhstan   | 225       | 0.89%   |
| USA          | 179       | 0.71%   |
| Italy        | 174       | 0.69%   |
| France       | 167       | 0.66%   |
| Brazil       | 115       | 0.45%   |
| Spain        | 104       | 0.41%   |
| Canada       | 75        | 0.3%    |
| UK           | 72        | 0.28%   |
| Romania      | 64        | 0.25%   |
| Moldova      | 63        | 0.25%   |
| Latvia       | 49        | 0.19%   |
| Bulgaria     | 47        | 0.19%   |
| Mexico       | 41        | 0.16%   |
| Serbia       | 39        | 0.15%   |
| Austria      | 36        | 0.14%   |
| Israel       | 33        | 0.13%   |
| Czechia      | 30        | 0.12%   |
| Turkey       | 29        | 0.11%   |
| Slovakia     | 28        | 0.11%   |
| Australia    | 28        | 0.11%   |
| Lithuania    | 27        | 0.11%   |
| Estonia      | 27        | 0.11%   |
| Belgium      | 27        | 0.11%   |
| Netherlands  | 25        | 0.1%    |
| Switzerland  | 24        | 0.09%   |
| Finland      | 24        | 0.09%   |
| Uzbekistan   | 23        | 0.09%   |
| Greece       | 22        | 0.09%   |
| Argentina    | 20        | 0.08%   |
| Sweden       | 19        | 0.08%   |
| India        | 19        | 0.08%   |
| Colombia     | 19        | 0.08%   |
| Portugal     | 17        | 0.07%   |
| Hungary      | 17        | 0.07%   |
| Kyrgyzstan   | 14        | 0.06%   |
| Chile        | 14        | 0.06%   |
| Venezuela    | 13        | 0.05%   |
| Peru         | 13        | 0.05%   |
| Azerbaijan   | 13        | 0.05%   |
| Ireland      | 12        | 0.05%   |
| Japan        | 11        | 0.04%   |
| Indonesia    | 11        | 0.04%   |
| China        | 11        | 0.04%   |
| South Africa | 10        | 0.04%   |
| Egypt        | 10        | 0.04%   |
| Georgia      | 8         | 0.03%   |
| Denmark      | 8         | 0.03%   |
| Croatia      | 7         | 0.03%   |
| South Korea  | 6         | 0.02%   |
| Saudi Arabia | 6         | 0.02%   |
| Norway       | 6         | 0.02%   |
| Algeria      | 6         | 0.02%   |
| Senegal      | 5         | 0.02%   |
| New Zealand  | 5         | 0.02%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Unknown          | 8003      | 29.74%  |
| Moscow           | 2059      | 7.65%   |
| St Petersburg    | 884       | 3.28%   |
| Pecherskoye      | 759       | 2.82%   |
| Novosibirsk      | 456       | 1.69%   |
| Krasnodar        | 389       | 1.45%   |
| Yekaterinburg    | 358       | 1.33%   |
| Nizhniy Novgorod | 309       | 1.15%   |
| Samara           | 305       | 1.13%   |
| Rostov-on-Don    | 257       | 0.95%   |
| Chelyabinsk      | 240       | 0.89%   |
| Perm             | 237       | 0.88%   |
| Voronezh         | 224       | 0.83%   |
| Saratov          | 197       | 0.73%   |
| Krasnoyarsk      | 191       | 0.71%   |
| Omsk             | 159       | 0.59%   |
| Kazan’         | 151       | 0.56%   |
| Volgograd        | 146       | 0.54%   |
| Minsk            | 142       | 0.53%   |
| Khabarovsk       | 138       | 0.51%   |
| Barnaul          | 127       | 0.47%   |
| Tyumen           | 126       | 0.47%   |
| Stavropol        | 115       | 0.43%   |
| Ufa              | 114       | 0.42%   |
| Kyiv             | 112       | 0.42%   |
| Irkutsk          | 108       | 0.4%    |
| Kemerovo         | 107       | 0.4%    |
| Vladivostok      | 104       | 0.39%   |
| Yaroslavl        | 103       | 0.38%   |
| Kaliningrad      | 101       | 0.38%   |
| Tula             | 95        | 0.35%   |
| Bryansk          | 92        | 0.34%   |
| Novokuznetsk     | 90        | 0.33%   |
| Simferopol       | 87        | 0.32%   |
| Orenburg         | 87        | 0.32%   |
| Belgorod         | 82        | 0.3%    |
| Surgut           | 81        | 0.3%    |
| Ryazan           | 81        | 0.3%    |
| Ulyanovsk        | 80        | 0.3%    |
| Lipetsk          | 80        | 0.3%    |
| Astrakhan        | 80        | 0.3%    |
| Kirov            | 78        | 0.29%   |
| Tomsk            | 76        | 0.28%   |
| Izhevsk          | 76        | 0.28%   |
| Sevastopol       | 75        | 0.28%   |
| Tolyatti         | 74        | 0.27%   |
| Penza            | 74        | 0.27%   |
| Vitebsk          | 72        | 0.27%   |
| Ivanovo          | 70        | 0.26%   |
| Murmansk         | 66        | 0.25%   |
| Kharkiv          | 65        | 0.24%   |
| Abakan           | 65        | 0.24%   |
| Kaluga           | 64        | 0.24%   |
| Warsaw           | 63        | 0.23%   |
| Smolensk         | 60        | 0.22%   |
| Donetsk          | 60        | 0.22%   |
| Tver             | 59        | 0.22%   |
| Arkhangelsk      | 59        | 0.22%   |
| Kurgan           | 57        | 0.21%   |
| Chita            | 57        | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives  | Percent |
|---------------------|-----------|---------|---------|
| Seagate             | 8493      | 13163   | 25.73%  |
| WDC                 | 7935      | 12502   | 24.04%  |
| Hitachi             | 2832      | 3885    | 8.58%   |
| Toshiba             | 2652      | 3693    | 8.04%   |
| Samsung Electronics | 2580      | 3795    | 7.82%   |
| Kingston            | 1229      | 1674    | 3.72%   |
| HGST                | 849       | 1247    | 2.57%   |
| Unknown             | 756       | 983     | 2.29%   |
| SanDisk             | 495       | 682     | 1.5%    |
| MAXTOR              | 458       | 590     | 1.39%   |
| OCZ                 | 357       | 485     | 1.08%   |
| SPCC                | 320       | 442     | 0.97%   |
| A-DATA Technology   | 305       | 426     | 0.92%   |
| Fujitsu             | 297       | 359     | 0.9%    |
| China               | 292       | 367     | 0.88%   |
| HUAWEI              | 284       | 333     | 0.86%   |
| Intel               | 283       | 418     | 0.86%   |
| Crucial             | 261       | 356     | 0.79%   |
| PLEXTOR             | 244       | 365     | 0.74%   |
| Smartbuy            | 152       | 188     | 0.46%   |
| Transcend           | 135       | 191     | 0.41%   |
| Corsair             | 128       | 169     | 0.39%   |
| GOODRAM             | 107       | 138     | 0.32%   |
| Apacer              | 99        | 133     | 0.3%    |
| KingSpec            | 93        | 127     | 0.28%   |
| Patriot             | 87        | 110     | 0.26%   |
| SK Hynix            | 83        | 110     | 0.25%   |
| AMD                 | 81        | 93      | 0.25%   |
| TF CARD             | 72        | 94      | 0.22%   |
| KingDian            | 59        | 85      | 0.18%   |
| Apple               | 47        | 59      | 0.14%   |
| ZTE                 | 46        | 52      | 0.14%   |
| Kingmax             | 45        | 89      | 0.14%   |
| Micron Technology   | 43        | 54      | 0.13%   |
| Mass                | 33        | Unknown | 0.1%    |
| LITEONIT            | 31        | 47      | 0.09%   |
| IBM/Hitachi         | 31        | 36      | 0.09%   |
| Gigabyte Technology | 31        | 39      | 0.09%   |
| JMicron             | 30        | 31      | 0.09%   |
| Silicon Motion      | 26        | 32      | 0.08%   |
| LITEON              | 26        | 37      | 0.08%   |
| Team                | 23        | 28      | 0.07%   |
| XPG                 | 22        | 25      | 0.07%   |
| KingFast            | 21        | 28      | 0.06%   |
| OCZ-VERTEX3         | 19        | 28      | 0.06%   |
| PNY                 | 18        | 22      | 0.05%   |
| Hewlett-Packard     | 18        | 34      | 0.05%   |
| Intenso             | 17        | 20      | 0.05%   |
| FOXLINE             | 17        | 21      | 0.05%   |
| XrayDisk            | 16        | 22      | 0.05%   |
| Netac               | 16        | 19      | 0.05%   |
| Zheino              | 14        | 18      | 0.04%   |
| LONDISK             | 14        | 14      | 0.04%   |
| ExcelStor           | 12        | 19      | 0.04%   |
| TO Exter            | 11        | 13      | 0.03%   |
| QUMO                | 9         | 11      | 0.03%   |
| Mushkin             | 9         | 10      | 0.03%   |
| e2e4                | 9         | 15      | 0.03%   |
| WD MediaMax         | 8         | 12      | 0.02%   |
| PHISON              | 8         | 9       | 0.02%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500DM002-1BD142 500GB     | 466       | 1.29%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 399       | 1.11%   |
| Seagate ST500LT012-1DG142 500GB     | 358       | 0.99%   |
| Seagate ST9500325AS 500GB           | 334       | 0.93%   |
| Seagate ST3500418AS 500GB           | 329       | 0.91%   |
| Toshiba MQ01ABF050 500GB            | 279       | 0.77%   |
| Kingston SV300S37A120G 120GB SSD    | 276       | 0.76%   |
| Toshiba DT01ACA050 500GB            | 271       | 0.75%   |
| Seagate ST1000DM003-1CH162 1TB      | 260       | 0.72%   |
| Seagate ST9320325AS 320GB           | 226       | 0.63%   |
| Toshiba DT01ACA100 1TB              | 220       | 0.61%   |
| HGST HTS545050A7E680 500GB          | 211       | 0.58%   |
| Unknown xD/SD/M.S.                  | 207       | 0.57%   |
| Seagate ST3250410AS 250GB           | 185       | 0.51%   |
| Seagate ST380011A 80GB              | 181       | 0.5%    |
| WDC WD5000AAKX-001CA0 500GB         | 176       | 0.49%   |
| Hitachi HTS543232A7A384 320GB       | 176       | 0.49%   |
| Seagate ST500LT012-9WS142 500GB     | 174       | 0.48%   |
| Seagate ST9250315AS 250GB           | 171       | 0.47%   |
| Seagate ST3160815AS 160GB           | 167       | 0.46%   |
| Kingston SA400S37120G 120GB SSD     | 165       | 0.46%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 160       | 0.44%   |
| Seagate ST31000528AS 1TB            | 159       | 0.44%   |
| Seagate ST31000524AS 1TB            | 155       | 0.43%   |
| Seagate ST3250310AS 250GB           | 153       | 0.42%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 151       | 0.42%   |
| Toshiba MQ01ABD100 1TB              | 150       | 0.42%   |
| Seagate ST380815AS 80GB             | 150       | 0.42%   |
| Toshiba HDWD110 1TB                 | 141       | 0.39%   |
| Seagate ST320LT020-9YG142 320GB     | 137       | 0.38%   |
| Seagate ST1000DM003-1ER162 1TB      | 137       | 0.38%   |
| HGST HTS545050A7E380 500GB          | 137       | 0.38%   |
| Seagate ST1000DM010-2EP102 1TB      | 135       | 0.37%   |
| HUAWEI TF CARD Storage 16GB         | 134       | 0.37%   |
| HUAWEI SD Storage 8GB               | 134       | 0.37%   |
| Hitachi HTS547550A9E384 500GB       | 131       | 0.36%   |
| Hitachi HDS721050CLA362 500GB       | 128       | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB            | 125       | 0.35%   |
| HGST HTS541010A9E680 1TB            | 123       | 0.34%   |
| WDC WD3200BPVT-22JJ5T0 320GB        | 121       | 0.34%   |
| Hitachi HTS545025B9A300 250GB       | 119       | 0.33%   |
| Seagate ST3500413AS 500GB           | 116       | 0.32%   |
| SPCC Solid State Disk 120GB         | 112       | 0.31%   |
| Kingston SV300S37A60G 64GB SSD      | 111       | 0.31%   |
| WDC WD5000AADS-00S9B0 500GB         | 109       | 0.3%    |
| Hitachi HTS547575A9E384 752GB       | 107       | 0.3%    |
| HGST HTS721010A9E630 1TB            | 107       | 0.3%    |
| Kingston SA400S37240G 240GB SSD     | 105       | 0.29%   |
| Seagate ST3320620AS 320GB           | 104       | 0.29%   |
| Samsung HD080HJ 80GB                | 103       | 0.29%   |
| HGST HTS725050A7E630 500GB          | 103       | 0.29%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 100       | 0.28%   |
| Toshiba MQ01ABD050 500GB            | 99        | 0.27%   |
| Hitachi HTS545050A7E380 500GB       | 99        | 0.27%   |
| Seagate ST1000DM003-9YN162 1TB      | 98        | 0.27%   |
| Hitachi HDS721010CLA332 1TB         | 98        | 0.27%   |
| Seagate ST3320613AS 320GB           | 97        | 0.27%   |
| Seagate ST3250318AS 250GB           | 95        | 0.26%   |
| Seagate ST3160811AS 160GB           | 95        | 0.26%   |
| Seagate ST2000DM001-1CH164 2TB      | 95        | 0.26%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 8471      | 13114  | 33.89%  |
| WDC                 | 7698      | 12055  | 30.8%   |
| Hitachi             | 2832      | 3885   | 11.33%  |
| Toshiba             | 2536      | 3519   | 10.15%  |
| Samsung Electronics | 1694      | 2419   | 6.78%   |
| HGST                | 849       | 1247   | 3.4%    |
| MAXTOR              | 456       | 588    | 1.82%   |
| Fujitsu             | 295       | 356    | 1.18%   |
| IBM/Hitachi         | 31        | 36     | 0.12%   |
| Apple               | 26        | 33     | 0.1%    |
| Unknown             | 20        | 28     | 0.08%   |
| ExcelStor           | 12        | 19     | 0.05%   |
| Hewlett-Packard     | 11        | 15     | 0.04%   |
| WD MediaMax         | 8         | 12     | 0.03%   |
| IBM                 | 6         | 9      | 0.02%   |
| QUANTUM             | 5         | 5      | 0.02%   |
| ASMT                | 5         | 7      | 0.02%   |
| asmedia             | 5         | 12     | 0.02%   |
| PHD 3.0             | 2         | 2      | 0.01%   |
| Magnetic Data       | 2         | 2      | 0.01%   |
| Intenso             | 2         | 2      | 0.01%   |
| HPE                 | 2         | 2      | 0.01%   |
| HGST HTS            | 2         | 2      | 0.01%   |
| CLOVER              | 2         | 2      | 0.01%   |
| ZALMAN              | 1         | 1      | 0.004%  |
| USB3.0              | 1         | 1      | 0.004%  |
| USB 3.0             | 1         | 1      | 0.004%  |
| USB                 | 1         | 1      | 0.004%  |
| TPH01204000GB       | 1         | 1      | 0.004%  |
| TPH00100500GB       | 1         | 1      | 0.004%  |
| Speeding            | 1         | 1      | 0.004%  |
| SILICONMOTION       | 1         | 1      | 0.004%  |
| SILICON             | 1         | 1      | 0.004%  |
| sage                | 1         | 1      | 0.004%  |
| SABRENT             | 1         | 1      | 0.004%  |
| OEM                 | 1         | 2      | 0.004%  |
| MSCC                | 1         | 1      | 0.004%  |
| MR2020              | 1         | 1      | 0.004%  |
| MARSHAL             | 1         | 2      | 0.004%  |
| LEXAR               | 1         | 1      | 0.004%  |
| Inateck             | 1         | 1      | 0.004%  |
| FC-1307             | 1         | 1      | 0.004%  |
| External            | 1         | 1      | 0.004%  |
| Ext Hard            | 1         | 1      | 0.004%  |
| China               | 1         | 1      | 0.004%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1185      | 1617   | 18.51%  |
| Samsung Electronics | 794       | 1192   | 12.4%   |
| SanDisk             | 435       | 606    | 6.8%    |
| OCZ                 | 356       | 484    | 5.56%   |
| SPCC                | 317       | 437    | 4.95%   |
| WDC                 | 293       | 376    | 4.58%   |
| China               | 291       | 366    | 4.55%   |
| A-DATA Technology   | 275       | 380    | 4.3%    |
| Crucial             | 256       | 345    | 4%      |
| Intel               | 250       | 374    | 3.91%   |
| PLEXTOR             | 236       | 351    | 3.69%   |
| Smartbuy            | 148       | 183    | 2.31%   |
| Transcend           | 131       | 184    | 2.05%   |
| Corsair             | 127       | 168    | 1.98%   |
| Toshiba             | 109       | 154    | 1.7%    |
| GOODRAM             | 105       | 136    | 1.64%   |
| Apacer              | 96        | 129    | 1.5%    |
| KingSpec            | 93        | 127    | 1.45%   |
| Patriot             | 83        | 106    | 1.3%    |
| AMD                 | 74        | 86     | 1.16%   |
| KingDian            | 58        | 84     | 0.91%   |
| Kingmax             | 45        | 89     | 0.7%    |
| SK Hynix            | 35        | 51     | 0.55%   |
| Micron Technology   | 33        | 44     | 0.52%   |
| LITEONIT            | 31        | 47     | 0.48%   |
| LITEON              | 25        | 36     | 0.39%   |
| JMicron             | 25        | 27     | 0.39%   |
| Gigabyte Technology | 24        | 29     | 0.37%   |
| Team                | 22        | 26     | 0.34%   |
| KingFast            | 21        | 28     | 0.33%   |
| Apple               | 20        | 25     | 0.31%   |
| OCZ-VERTEX3         | 19        | 28     | 0.3%    |
| PNY                 | 18        | 22     | 0.28%   |
| FOXLINE             | 16        | 20     | 0.25%   |
| Intenso             | 15        | 18     | 0.23%   |
| Zheino              | 14        | 18     | 0.22%   |
| XrayDisk            | 14        | 20     | 0.22%   |
| Netac               | 14        | 17     | 0.22%   |
| LONDISK             | 14        | 14     | 0.22%   |
| TO Exter            | 11        | 13     | 0.17%   |
| Seagate             | 10        | 15     | 0.16%   |
| QUMO                | 9         | 11     | 0.14%   |
| Mushkin             | 9         | 10     | 0.14%   |
| OCZ-VERTEX          | 8         | 12     | 0.12%   |
| FASTDISK            | 8         | 10     | 0.12%   |
| e2e4                | 8         | 14     | 0.12%   |
| ASUS-PHISON         | 8         | 21     | 0.12%   |
| Palit               | 7         | 9      | 0.11%   |
| GLOWAY              | 7         | 7      | 0.11%   |
| GeIL                | 7         | 7      | 0.11%   |
| CHN25SATAS1         | 7         | 15     | 0.11%   |
| Verbatim            | 6         | 8      | 0.09%   |
| FORESEE             | 6         | 6      | 0.09%   |
| faspeed             | 6         | 6      | 0.09%   |
| Unknown             | 5         | 8      | 0.08%   |
| LDLC                | 5         | 8      | 0.08%   |
| Hewlett-Packard     | 5         | 8      | 0.08%   |
| Teclast             | 4         | 4      | 0.06%   |
| PHISON              | 4         | 5      | 0.06%   |
| KINGRICH            | 4         | 6      | 0.06%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 21055     | 37394  | 73.77%  |
| SSD     | 5765      | 8833   | 20.2%   |
| Unknown | 680       | 817    | 2.38%   |
| MMC     | 569       | 777    | 1.99%   |
| NVMe    | 471       | 644    | 1.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 23396     | 45870  | 92.17%  |
| SAS  | 947       | 1174   | 3.73%   |
| MMC  | 569       | 777    | 2.24%   |
| NVMe | 471       | 644    | 1.86%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 20114     | 34418  | 73.47%  |
| 0.51-1.0   | 6015      | 9816   | 21.97%  |
| 1.01-2.0   | 856       | 1406   | 3.13%   |
| 2.01-3.0   | 177       | 272    | 0.65%   |
| 3.01-4.0   | 175       | 250    | 0.64%   |
| 4.01-10.0  | 40        | 64     | 0.15%   |
| 10.01-20.0 | 1         | 1      | 0.004%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 6814      | 24.72%  |
| 251-500        | 6094      | 22.1%   |
| 1-20           | 3899      | 14.14%  |
| 51-100         | 3253      | 11.8%   |
| 501-1000       | 2933      | 10.64%  |
| 21-50          | 2480      | 9%      |
| 1001-2000      | 1162      | 4.21%   |
| Unknown        | 456       | 1.65%   |
| 2001-3000      | 283       | 1.03%   |
| More than 3000 | 195       | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 17865     | 64.91%  |
| 21-50          | 2587      | 9.4%    |
| 101-250        | 2061      | 7.49%   |
| 51-100         | 1760      | 6.4%    |
| 251-500        | 1409      | 5.12%   |
| 501-1000       | 891       | 3.24%   |
| Unknown        | 456       | 1.66%   |
| 1001-2000      | 344       | 1.25%   |
| 2001-3000      | 80        | 0.29%   |
| More than 3000 | 68        | 0.25%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB          | 240       | 332    | 2.04%   |
| Seagate ST500DM002-1BD142 500GB    | 181       | 238    | 1.54%   |
| Seagate ST500LT012-9WS142 500GB    | 169       | 214    | 1.44%   |
| Seagate ST3500418AS 500GB          | 160       | 219    | 1.36%   |
| Seagate ST9320325AS 320GB          | 132       | 164    | 1.12%   |
| Seagate ST9250315AS 250GB          | 116       | 145    | 0.99%   |
| Seagate ST3250410AS 250GB          | 116       | 149    | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 100       | 119    | 0.85%   |
| Seagate ST3250310AS 250GB          | 99        | 147    | 0.84%   |
| WDC WD5000AAKX-001CA0 500GB        | 93        | 117    | 0.79%   |
| Seagate ST500LT012-1DG142 500GB    | 93        | 115    | 0.79%   |
| HGST HTS545050A7E680 500GB         | 91        | 122    | 0.77%   |
| Seagate ST320LT020-9YG142 320GB    | 84        | 118    | 0.71%   |
| Seagate ST31000528AS 1TB           | 79        | 106    | 0.67%   |
| Hitachi HTS543232A7A384 320GB      | 76        | 94     | 0.65%   |
| Seagate ST3320613AS 320GB          | 75        | 104    | 0.64%   |
| Seagate ST3160815AS 160GB          | 68        | 81     | 0.58%   |
| HGST HTS545050A7E380 500GB         | 68        | 107    | 0.58%   |
| Seagate ST380011A 80GB             | 65        | 74     | 0.55%   |
| Seagate ST3160811AS 160GB          | 64        | 89     | 0.54%   |
| Samsung Electronics HD080HJ 80GB   | 64        | 79     | 0.54%   |
| Hitachi HTS545025B9A300 250GB      | 64        | 82     | 0.54%   |
| WDC WD5000AADS-00S9B0 500GB        | 62        | 73     | 0.53%   |
| Seagate ST31000524AS 1TB           | 58        | 84     | 0.49%   |
| Seagate ST320LT012-9WS14C 320GB    | 55        | 75     | 0.47%   |
| Samsung Electronics HD160JJ 160GB  | 55        | 85     | 0.47%   |
| Hitachi HTS547550A9E384 500GB      | 54        | 71     | 0.46%   |
| Hitachi HTS541612J9SA00 120GB      | 54        | 67     | 0.46%   |
| Hitachi HDS721616PLA380 164GB      | 54        | 71     | 0.46%   |
| Seagate ST1000DM003-1CH162 1TB     | 53        | 74     | 0.45%   |
| Toshiba MQ01ABD050 500GB           | 52        | 67     | 0.44%   |
| Hitachi HDS721050CLA362 500GB      | 52        | 66     | 0.44%   |
| Hitachi HTS547575A9E384 752GB      | 51        | 72     | 0.43%   |
| Hitachi HDP725050GLA360 500GB      | 51        | 69     | 0.43%   |
| Seagate ST3250318AS 250GB          | 50        | 67     | 0.42%   |
| Seagate ST1000DM003-9YN162 1TB     | 50        | 59     | 0.42%   |
| Hitachi HTS545050B9A300 500GB      | 50        | 70     | 0.42%   |
| Seagate ST380815AS 80GB            | 49        | 62     | 0.42%   |
| WDC WD3200AAJS-00L7A0 320GB        | 48        | 57     | 0.41%   |
| WDC WD10EARS-00Y5B1 1TB            | 48        | 79     | 0.41%   |
| Seagate ST31500341AS 1TB           | 48        | 68     | 0.41%   |
| Seagate ST9500420AS 500GB          | 47        | 68     | 0.4%    |
| Seagate ST3320620AS 320GB          | 47        | 63     | 0.4%    |
| Hitachi HTS542512K9SA00 120GB      | 47        | 56     | 0.4%    |
| Samsung Electronics HM160HI 160GB  | 46        | 56     | 0.39%   |
| Hitachi HTS545050A7E380 500GB      | 46        | 59     | 0.39%   |
| Hitachi HTS545032B9A300 320GB      | 45        | 55     | 0.38%   |
| Hitachi HDS721010CLA332 1TB        | 45        | 57     | 0.38%   |
| Seagate ST3500320AS 500GB          | 44        | 58     | 0.37%   |
| Samsung Electronics HD321KJ 320GB  | 44        | 53     | 0.37%   |
| Toshiba MQ01ABF050 500GB           | 42        | 47     | 0.36%   |
| Seagate ST9160821AS 160GB          | 41        | 50     | 0.35%   |
| Samsung Electronics HD161HJ 160GB  | 41        | 51     | 0.35%   |
| Toshiba MK3265GSX 320GB            | 40        | 53     | 0.34%   |
| Kingston SHFS37A120G 120GB SSD     | 40        | 52     | 0.34%   |
| Hitachi HTS541680J9SA00 80GB       | 40        | 54     | 0.34%   |
| Seagate ST3500413AS 500GB          | 39        | 41     | 0.33%   |
| MAXTOR STM3250310AS 250GB          | 39        | 52     | 0.33%   |
| Kingston SV300S37A120G 120GB SSD   | 39        | 44     | 0.33%   |
| WDC WD5000AAKX-00ERMA0 500GB       | 37        | 52     | 0.31%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 3881      | 5413   | 34.5%   |
| WDC                   | 2653      | 3677   | 23.58%  |
| Hitachi               | 1523      | 2025   | 13.54%  |
| Samsung Electronics   | 905       | 1218   | 8.04%   |
| Toshiba               | 820       | 1078   | 7.29%   |
| HGST                  | 276       | 390    | 2.45%   |
| MAXTOR                | 273       | 338    | 2.43%   |
| Kingston              | 161       | 201    | 1.43%   |
| Fujitsu               | 124       | 150    | 1.1%    |
| SanDisk               | 77        | 93     | 0.68%   |
| SPCC                  | 65        | 82     | 0.58%   |
| OCZ                   | 64        | 91     | 0.57%   |
| Intel                 | 59        | 68     | 0.52%   |
| A-DATA Technology     | 44        | 64     | 0.39%   |
| Corsair               | 40        | 50     | 0.36%   |
| Kingmax               | 31        | 54     | 0.28%   |
| Crucial               | 30        | 47     | 0.27%   |
| IBM/Hitachi           | 27        | 32     | 0.24%   |
| China                 | 18        | 21     | 0.16%   |
| PLEXTOR               | 16        | 21     | 0.14%   |
| KingSpec              | 16        | 23     | 0.14%   |
| LITEONIT              | 12        | 17     | 0.11%   |
| SK Hynix              | 10        | 15     | 0.09%   |
| AMD                   | 10        | 14     | 0.09%   |
| ExcelStor             | 8         | 10     | 0.07%   |
| Apple                 | 7         | 8      | 0.06%   |
| Transcend             | 6         | 8      | 0.05%   |
| OCZ-VERTEX3           | 5         | 10     | 0.04%   |
| Mushkin               | 5         | 5      | 0.04%   |
| Micron Technology     | 5         | 10     | 0.04%   |
| IBM                   | 5         | 7      | 0.04%   |
| Smartbuy              | 4         | 4      | 0.04%   |
| Patriot               | 4         | 4      | 0.04%   |
| WD MediaMax           | 3         | 5      | 0.03%   |
| SSSTC                 | 3         | 4      | 0.03%   |
| QUMO                  | 3         | 4      | 0.03%   |
| PNY                   | 3         | 5      | 0.03%   |
| KingDian              | 3         | 4      | 0.03%   |
| Intenso               | 3         | 3      | 0.03%   |
| Hewlett-Packard       | 3         | 4      | 0.03%   |
| Apacer                | 3         | 7      | 0.03%   |
| Unknown               | 2         | 2      | 0.02%   |
| Team                  | 2         | 2      | 0.02%   |
| Silicon Motion        | 2         | 3      | 0.02%   |
| QUANTUM               | 2         | 2      | 0.02%   |
| LITEON                | 2         | 2      | 0.02%   |
| KingFast              | 2         | 2      | 0.02%   |
| Espada                | 2         | 3      | 0.02%   |
| Zheino                | 1         | 1      | 0.01%   |
| XPG                   | 1         | 1      | 0.01%   |
| Verbatim              | 1         | 1      | 0.01%   |
| TPH00100500GB         | 1         | 1      | 0.01%   |
| TopSunligt            | 1         | 1      | 0.01%   |
| SMI                   | 1         | 1      | 0.01%   |
| SandForce             | 1         | 1      | 0.01%   |
| RunCore               | 1         | 1      | 0.01%   |
| Realtek Semiconductor | 1         | 1      | 0.01%   |
| PHISON                | 1         | 1      | 0.01%   |
| OCZ-REVODRIVE         | 1         | 4      | 0.01%   |
| Netac                 | 1         | 1      | 0.01%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3881      | 5413   | 37.11%  |
| WDC                 | 2631      | 3644   | 25.16%  |
| Hitachi             | 1523      | 2025   | 14.56%  |
| Samsung Electronics | 880       | 1191   | 8.41%   |
| Toshiba             | 815       | 1073   | 7.79%   |
| HGST                | 276       | 390    | 2.64%   |
| MAXTOR              | 273       | 338    | 2.61%   |
| Fujitsu             | 124       | 150    | 1.19%   |
| IBM/Hitachi         | 27        | 32     | 0.26%   |
| ExcelStor           | 8         | 10     | 0.08%   |
| IBM                 | 5         | 7      | 0.05%   |
| Apple               | 5         | 6      | 0.05%   |
| WD MediaMax         | 3         | 5      | 0.03%   |
| Hewlett-Packard     | 3         | 4      | 0.03%   |
| QUANTUM             | 2         | 2      | 0.02%   |
| TPH00100500GB       | 1         | 1      | 0.01%   |
| MARSHAL             | 1         | 2      | 0.01%   |
| HGST HTS            | 1         | 1      | 0.01%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9585      | 14294  | 92.45%  |
| SSD  | 772       | 1029   | 7.45%   |
| NVMe | 11        | 12     | 0.11%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB          | 13        | 14     | 3.38%   |
| Seagate ST31000528AS 1TB           | 12        | 14     | 3.12%   |
| Seagate ST31000524AS 1TB           | 7         | 8      | 1.82%   |
| Samsung Electronics HM321HI 320GB  | 7         | 9      | 1.82%   |
| HGST HTS545050A7E680 500GB         | 7         | 7      | 1.82%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 6         | 7      | 1.56%   |
| Seagate ST9500325AS 500GB          | 6         | 7      | 1.56%   |
| Seagate ST3500412AS 500GB          | 6         | 8      | 1.56%   |
| Hitachi HDS721010DLE630 1TB        | 6         | 8      | 1.56%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 5         | 6      | 1.3%    |
| Seagate ST9320325AS 320GB          | 5         | 6      | 1.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 5         | 5      | 1.3%    |
| Samsung Electronics HD502HJ 500GB  | 5         | 5      | 1.3%    |
| Toshiba MQ01ABD050 500GB           | 4         | 4      | 1.04%   |
| Toshiba MK6465GSX 640GB            | 4         | 6      | 1.04%   |
| Seagate ST9250315AS 250GB          | 4         | 4      | 1.04%   |
| Seagate ST500LT012-1DG142 500GB    | 4         | 4      | 1.04%   |
| Seagate ST3500410AS 500GB          | 4         | 5      | 1.04%   |
| Seagate ST31000333AS 1TB           | 4         | 4      | 1.04%   |
| Samsung Electronics SP0411N 34GB   | 4         | 5      | 1.04%   |
| Samsung Electronics HD502IJ 500GB  | 4         | 4      | 1.04%   |
| Samsung Electronics HD322GJ 320GB  | 4         | 5      | 1.04%   |
| HGST HTS545050A7E380 500GB         | 4         | 4      | 1.04%   |
| WDC WD5000AAKS-00V1A0 500GB        | 3         | 4      | 0.78%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 3         | 3      | 0.78%   |
| WDC WD3200AAJS-00L7A0 320GB        | 3         | 4      | 0.78%   |
| WDC WD1600BEVS-22RST0 160GB        | 3         | 4      | 0.78%   |
| WDC WD15EARS-00MVWB0 1TB           | 3         | 6      | 0.78%   |
| Toshiba MK3265GSX 320GB            | 3         | 3      | 0.78%   |
| Seagate ST3750528AS 752GB          | 3         | 3      | 0.78%   |
| Seagate ST32000542AS 2TB           | 3         | 5      | 0.78%   |
| MAXTOR 6Y080L0 82GB                | 3         | 3      | 0.78%   |
| Hitachi HTS547575A9E384 752GB      | 3         | 3      | 0.78%   |
| Hitachi HTS547550A9E384 500GB      | 3         | 4      | 0.78%   |
| HGST HTS721010A9E630 1TB           | 3         | 4      | 0.78%   |
| WDC WD5000BPVT-00HXZT1 500GB       | 2         | 2      | 0.52%   |
| WDC WD2500JS-22NCB1 250GB          | 2         | 3      | 0.52%   |
| Toshiba MK3259GSXP 320GB           | 2         | 2      | 0.52%   |
| Toshiba MK2565GSX 250GB            | 2         | 2      | 0.52%   |
| Toshiba MK1059GSM 1TB              | 2         | 3      | 0.52%   |
| Toshiba DT01ACA050 500GB           | 2         | 2      | 0.52%   |
| Seagate STM3500418AS 500GB         | 2         | 2      | 0.52%   |
| Seagate ST3640323AS 640GB          | 2         | 2      | 0.52%   |
| Seagate ST3320613AS 320GB          | 2         | 3      | 0.52%   |
| Seagate ST3250318AS 250GB          | 2         | 6      | 0.52%   |
| Seagate ST320LT020-9YG142 320GB    | 2         | 2      | 0.52%   |
| Seagate ST3160318AS 160GB          | 2         | 2      | 0.52%   |
| Seagate ST31500341AS 1TB           | 2         | 3      | 0.52%   |
| Samsung Electronics HM250HI 250GB  | 2         | 2      | 0.52%   |
| Samsung Electronics HM160HI 160GB  | 2         | 2      | 0.52%   |
| Samsung Electronics HD252HJ 250GB  | 2         | 6      | 0.52%   |
| Samsung Electronics HD251HJ 250GB  | 2         | 2      | 0.52%   |
| Samsung Electronics HD204UI 2TB    | 2         | 2      | 0.52%   |
| Samsung Electronics HD105SI 1TB    | 2         | 2      | 0.52%   |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 0.52%   |
| Hitachi HTS543232A7A384 320GB      | 2         | 2      | 0.52%   |
| Hitachi HTS543225A7A384 250GB      | 2         | 3      | 0.52%   |
| Hitachi HDT721032SLA380 320GB      | 2         | 2      | 0.52%   |
| Hitachi HDS721050DLE630 500GB      | 2         | 2      | 0.52%   |
| Hitachi HDS721025CLA382 250GB      | 2         | 2      | 0.52%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 120       | 146    | 31.25%  |
| WDC                 | 99        | 117    | 25.78%  |
| Samsung Electronics | 59        | 68     | 15.36%  |
| Toshiba             | 37        | 42     | 9.64%   |
| Hitachi             | 35        | 39     | 9.11%   |
| HGST                | 18        | 20     | 4.69%   |
| MAXTOR              | 10        | 10     | 2.6%    |
| Fujitsu             | 2         | 2      | 0.52%   |
| Apple               | 2         | 3      | 0.52%   |
| Hewlett-Packard     | 1         | 1      | 0.26%   |
| Corsair             | 1         | 1      | 0.26%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 16480     | 29803  | 56.8%   |
| Malfunc  | 10157     | 15335  | 35.01%  |
| Detected | 1993      | 2878   | 6.87%   |
| Failed   | 382       | 449    | 1.32%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 16868     | 63.7%   |
| AMD                              | 5050      | 19.07%  |
| Nvidia                           | 1458      | 5.51%   |
| JMicron Technology               | 1051      | 3.97%   |
| Marvell Technology Group         | 566       | 2.14%   |
| ASMedia Technology               | 336       | 1.27%   |
| VIA Technologies                 | 315       | 1.19%   |
| Silicon Integrated Systems [SiS] | 187       | 0.71%   |
| Samsung Electronics              | 143       | 0.54%   |
| Silicon Motion                   | 54        | 0.2%    |
| Silicon Image                    | 53        | 0.2%    |
| Sandisk                          | 49        | 0.19%   |
| Kingston Technology Company      | 49        | 0.19%   |
| Integrated Technology Express    | 41        | 0.15%   |
| ADATA Technology                 | 33        | 0.12%   |
| SK Hynix                         | 28        | 0.11%   |
| Phison Electronics               | 27        | 0.1%    |
| Realtek Semiconductor            | 20        | 0.08%   |
| LSI Logic / Symbios Logic        | 18        | 0.07%   |
| Lite-On Technology               | 17        | 0.06%   |
| ULi Electronics                  | 16        | 0.06%   |
| Adaptec                          | 13        | 0.05%   |
| Micron Technology                | 10        | 0.04%   |
| Union Memory (Shenzhen)          | 9         | 0.03%   |
| Toshiba America Info Systems     | 9         | 0.03%   |
| Micron/Crucial Technology        | 8         | 0.03%   |
| KIOXIA                           | 8         | 0.03%   |
| Promise Technology               | 7         | 0.03%   |
| OCZ Technology Group             | 7         | 0.03%   |
| Solid State Storage Technology   | 6         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 6         | 0.02%   |
| Hewlett-Packard                  | 5         | 0.02%   |
| ATI Technologies                 | 3         | 0.01%   |
| Broadcom / LSI                   | 2         | 0.01%   |
| Artop Electronic                 | 2         | 0.01%   |
| Tekram Technology                | 1         | 0.004%  |
| Shenzhen Longsys Electronics     | 1         | 0.004%  |
| Seagate Technology               | 1         | 0.004%  |
| MCST                             | 1         | 0.004%  |
| Lenovo                           | 1         | 0.004%  |
| Broadcom                         | 1         | 0.004%  |
| Apple                            | 1         | 0.004%  |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 1989      | 5.54%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 1855      | 5.17%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 1689      | 4.71%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 1657      | 4.62%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 1576      | 4.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 1423      | 3.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 1176      | 3.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 1137      | 3.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 992       | 2.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 809       | 2.25%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 682       | 1.9%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 672       | 1.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 670       | 1.87%   |
| Nvidia MCP61 SATA Controller                                                            | 642       | 1.79%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 636       | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 633       | 1.76%   |
| Nvidia MCP61 IDE                                                                        | 598       | 1.67%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 577       | 1.61%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 514       | 1.43%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 501       | 1.4%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 457       | 1.27%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 415       | 1.16%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 405       | 1.13%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 403       | 1.12%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 396       | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 389       | 1.08%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 385       | 1.07%   |
| JMicron JMB368 IDE controller                                                           | 364       | 1.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 334       | 0.93%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 323       | 0.9%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 320       | 0.89%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 309       | 0.86%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 307       | 0.86%   |
| AMD SB600 IDE                                                                           | 304       | 0.85%   |
| AMD FCH IDE Controller                                                                  | 303       | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 296       | 0.82%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 290       | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 253       | 0.7%    |
| Intel 82801IB (ICH9) 2 port SATA Controller [IDE mode]                                  | 223       | 0.62%   |
| Intel 7 Series/C210 Series Chipset Family 4-port SATA Controller [IDE mode]             | 219       | 0.61%   |
| Intel 7 Series/C210 Series Chipset Family 2-port SATA Controller [IDE mode]             | 219       | 0.61%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 216       | 0.6%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 202       | 0.56%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 190       | 0.53%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 188       | 0.52%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 175       | 0.49%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 174       | 0.48%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 169       | 0.47%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 162       | 0.45%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 162       | 0.45%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 158       | 0.44%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                                | 157       | 0.44%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 156       | 0.43%   |
| Intel 82801EB/ER (ICH5/ICH5R) IDE Controller                                            | 152       | 0.42%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 148       | 0.41%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                             | 141       | 0.39%   |
| Marvell Group 88SE6101/6102 single-port PATA133 interface                               | 140       | 0.39%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 137       | 0.38%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                         | 129       | 0.36%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                         | 127       | 0.35%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 16309     | 58.33%  |
| IDE  | 10528     | 37.65%  |
| RAID | 610       | 2.18%   |
| NVMe | 477       | 1.71%   |
| SCSI | 23        | 0.08%   |
| SAS  | 15        | 0.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 17682     | 73.8%   |
| AMD          | 6262      | 26.14%  |
| CentaurHauls | 11        | 0.05%   |
| ARM          | 2         | 0.01%   |
| MBE8C-PC     | 1         | 0.004%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 233       | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 209       | 0.87%   |
| Intel Pentium 4 CPU 3.00GHz                 | 199       | 0.82%   |
| Intel Atom CPU N450 @ 1.66GHz               | 162       | 0.67%   |
| Intel Pentium CPU B960 @ 2.20GHz            | 153       | 0.63%   |
| Intel Atom CPU N270 @ 1.60GHz               | 152       | 0.63%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 149       | 0.62%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 147       | 0.61%   |
| AMD Athlon II X2 250 Processor              | 147       | 0.61%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 143       | 0.59%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 142       | 0.59%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 141       | 0.58%   |
| AMD E-450 APU with Radeon HD Graphics       | 136       | 0.56%   |
| AMD FX-6300 Six-Core Processor              | 135       | 0.56%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 129       | 0.53%   |
| Intel Atom CPU N2600 @ 1.60GHz              | 126       | 0.52%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 125       | 0.52%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 124       | 0.51%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 123       | 0.51%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 122       | 0.51%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 121       | 0.5%    |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 121       | 0.5%    |
| Intel Core i3-2310M CPU @ 2.10GHz           | 119       | 0.49%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 118       | 0.49%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 114       | 0.47%   |
| Intel Atom CPU N455 @ 1.66GHz               | 109       | 0.45%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 107       | 0.44%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 103       | 0.43%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz        | 99        | 0.41%   |
| AMD FX-8350 Eight-Core Processor            | 99        | 0.41%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 98        | 0.41%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 98        | 0.41%   |
| Intel Atom CPU N570 @ 1.66GHz               | 98        | 0.41%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 96        | 0.4%    |
| Intel Core i5-4210U CPU @ 1.70GHz           | 94        | 0.39%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 89        | 0.37%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 86        | 0.36%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 85        | 0.35%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+  | 85        | 0.35%   |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 82        | 0.34%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 81        | 0.34%   |
| AMD FX-8320 Eight-Core Processor            | 78        | 0.32%   |
| AMD A10-4600M APU with Radeon HD Graphics   | 78        | 0.32%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 77        | 0.32%   |
| AMD FX-4300 Quad-Core Processor             | 77        | 0.32%   |
| Intel Celeron CPU N3050 @ 1.60GHz           | 76        | 0.31%   |
| Intel Core i3-3217U CPU @ 1.80GHz           | 75        | 0.31%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz        | 75        | 0.31%   |
| AMD Athlon II X2 240 Processor              | 75        | 0.31%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 74        | 0.31%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 74        | 0.31%   |
| Intel Core i7-3630QM CPU @ 2.40GHz          | 74        | 0.31%   |
| AMD Athlon 64 X2 Dual Core Processor 6000+  | 74        | 0.31%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 73        | 0.3%    |
| Intel Core i3-3120M CPU @ 2.50GHz           | 72        | 0.3%    |
| Intel Core i3 CPU 540 @ 3.07GHz             | 72        | 0.3%    |
| Intel Core i5-4460 CPU @ 3.20GHz            | 71        | 0.29%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 71        | 0.29%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 69        | 0.29%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 69        | 0.29%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 3351      | 13.9%   |
| Intel Core i3                  | 2557      | 10.61%  |
| Intel Core 2 Duo               | 1984      | 8.23%   |
| Intel Celeron                  | 1821      | 7.56%   |
| Intel Pentium                  | 1657      | 6.87%   |
| Intel Core i7                  | 1446      | 6%      |
| Intel Atom                     | 1144      | 4.75%   |
| Intel Pentium Dual-Core        | 821       | 3.41%   |
| AMD Athlon 64 X2               | 702       | 2.91%   |
| AMD FX                         | 701       | 2.91%   |
| AMD Athlon II X2               | 494       | 2.05%   |
| Intel Pentium 4                | 456       | 1.89%   |
| Intel Core 2 Quad              | 449       | 1.86%   |
| Intel Core 2                   | 397       | 1.65%   |
| Intel Pentium Dual             | 394       | 1.63%   |
| AMD A6                         | 340       | 1.41%   |
| Intel Xeon                     | 337       | 1.4%    |
| AMD A4                         | 318       | 1.32%   |
| AMD A8                         | 304       | 1.26%   |
| AMD Phenom II X4               | 296       | 1.23%   |
| AMD A10                        | 267       | 1.11%   |
| AMD E                          | 263       | 1.09%   |
| Intel Genuine                  | 221       | 0.92%   |
| AMD Athlon II X4               | 212       | 0.88%   |
| AMD Ryzen 5                    | 192       | 0.8%    |
| AMD E1                         | 169       | 0.7%    |
| Intel Pentium D                | 168       | 0.7%    |
| AMD Athlon 64                  | 158       | 0.66%   |
| AMD Athlon II X3               | 157       | 0.65%   |
| Intel Celeron M                | 134       | 0.56%   |
| AMD Turion 64 X2 Mobile        | 113       | 0.47%   |
| AMD Sempron                    | 110       | 0.46%   |
| AMD Phenom                     | 109       | 0.45%   |
| Intel Celeron Dual-Core        | 108       | 0.45%   |
| AMD E2                         | 105       | 0.44%   |
| AMD Athlon X4                  | 98        | 0.41%   |
| AMD Athlon                     | 98        | 0.41%   |
| AMD Phenom II                  | 96        | 0.4%    |
| Other                          | 94        | 0.39%   |
| Intel Pentium M                | 93        | 0.39%   |
| AMD Ryzen 3                    | 93        | 0.39%   |
| AMD Athlon II                  | 92        | 0.38%   |
| AMD Phenom II X6               | 88        | 0.37%   |
| AMD Athlon X2                  | 66        | 0.27%   |
| AMD Ryzen 7                    | 64        | 0.27%   |
| AMD C-60                       | 61        | 0.25%   |
| AMD Phenom II X2               | 59        | 0.24%   |
| Intel Celeron D                | 53        | 0.22%   |
| Intel Core Duo                 | 45        | 0.19%   |
| AMD C-50                       | 44        | 0.18%   |
| Intel Pentium Gold             | 38        | 0.16%   |
| AMD Turion X2 Dual-Core Mobile | 33        | 0.14%   |
| AMD Turion II Dual-Core        | 29        | 0.12%   |
| AMD Turion II                  | 29        | 0.12%   |
| AMD Turion 64 Mobile           | 25        | 0.1%    |
| AMD Athlon II Dual-Core        | 25        | 0.1%    |
| Intel Pentium Silver           | 23        | 0.1%    |
| AMD Phenom II X3               | 23        | 0.1%    |
| AMD Athlon Dual Core           | 19        | 0.08%   |
| AMD Athlon XP                  | 18        | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 14369     | 58.38%  |
| 4       | 5157      | 20.95%  |
| 1       | 2107      | 8.56%   |
| Unknown | 1870      | 7.6%    |
| 6       | 454       | 1.84%   |
| 3       | 417       | 1.69%   |
| 8       | 193       | 0.78%   |
| 12      | 23        | 0.09%   |
| 16      | 7         | 0.03%   |
| 10      | 6         | 0.02%   |
| 24      | 4         | 0.02%   |
| 192     | 2         | 0.01%   |
| 20      | 2         | 0.01%   |
| 120     | 1         | 0.004%  |
| 28      | 1         | 0.004%  |
| 5       | 1         | 0.004%  |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 23784     | 98.96%  |
| Unknown | 159       | 0.66%   |
| 2       | 82        | 0.34%   |
| 4       | 7         | 0.03%   |
| 8       | 2         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 14027     | 56.98%  |
| 2       | 8721      | 35.43%  |
| Unknown | 1870      | 7.6%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 22446     | 92.71%  |
| 32-bit         | 961       | 3.97%   |
| Unknown        | 626       | 2.59%   |
| 64-bit         | 179       | 0.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 2794      | 11.39%  |
| 0x306a9    | 2273      | 9.27%   |
| 0x1067a    | 2082      | 8.49%   |
| Unknown    | 1656      | 6.75%   |
| 0x306c3    | 1182      | 4.82%   |
| 0x6fd      | 960       | 3.91%   |
| 0x010000c8 | 891       | 3.63%   |
| 0x20655    | 783       | 3.19%   |
| 0x10676    | 588       | 2.4%    |
| 0x106ca    | 520       | 2.12%   |
| 0x06001119 | 490       | 2%      |
| 0x30678    | 434       | 1.77%   |
| 0x40651    | 420       | 1.71%   |
| 0x6fb      | 410       | 1.67%   |
| 0x20652    | 317       | 1.29%   |
| 0x506e3    | 309       | 1.26%   |
| 0x6f6      | 277       | 1.13%   |
| 0x03000027 | 258       | 1.05%   |
| 0x106c2    | 240       | 0.98%   |
| 0x05000119 | 235       | 0.96%   |
| 0x906e9    | 226       | 0.92%   |
| 0x0600084f | 222       | 0.9%    |
| 0x10661    | 221       | 0.9%    |
| 0x30661    | 217       | 0.88%   |
| 0x306d4    | 200       | 0.82%   |
| 0x406c4    | 185       | 0.75%   |
| 0x106e5    | 185       | 0.75%   |
| 0x06000852 | 177       | 0.72%   |
| 0x406e3    | 175       | 0.71%   |
| 0x010000b6 | 175       | 0.71%   |
| 0x6f2      | 161       | 0.66%   |
| 0x07030105 | 160       | 0.65%   |
| 0x010000db | 153       | 0.62%   |
| 0x906ea    | 151       | 0.62%   |
| 0x406c3    | 151       | 0.62%   |
| 0xf41      | 139       | 0.57%   |
| 0xf49      | 133       | 0.54%   |
| 0x6e8      | 130       | 0.53%   |
| 0x06003106 | 125       | 0.51%   |
| 0x010000c7 | 117       | 0.48%   |
| 0x6d8      | 115       | 0.47%   |
| 0x806e9    | 108       | 0.44%   |
| 0x0700010f | 107       | 0.44%   |
| 0xf65      | 106       | 0.43%   |
| 0x0600063d | 97        | 0.4%    |
| 0x6ec      | 95        | 0.39%   |
| 0x10677    | 91        | 0.37%   |
| 0xf29      | 82        | 0.33%   |
| 0x05000101 | 81        | 0.33%   |
| 0x506c9    | 79        | 0.32%   |
| 0x06000822 | 78        | 0.32%   |
| 0x05000029 | 77        | 0.31%   |
| 0x806ea    | 75        | 0.31%   |
| 0x010000dc | 70        | 0.29%   |
| 0xf43      | 68        | 0.28%   |
| 0x0700010b | 68        | 0.28%   |
| 0x01000098 | 67        | 0.27%   |
| 0x106a5    | 64        | 0.26%   |
| 0x06001116 | 61        | 0.25%   |
| 0x01000086 | 61        | 0.25%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| SandyBridge      | 2857      | 11.83%  |
| Penryn           | 2682      | 11.11%  |
| IvyBridge        | 2326      | 9.63%   |
| Core             | 2225      | 9.22%   |
| K10              | 1784      | 7.39%   |
| Haswell          | 1652      | 6.84%   |
| Westmere         | 1137      | 4.71%   |
| K8 Hammer        | 1106      | 4.58%   |
| Piledriver       | 1053      | 4.36%   |
| Bonnell          | 920       | 3.81%   |
| Silvermont       | 845       | 3.5%    |
| NetBurst         | 807       | 3.34%   |
| KabyLake         | 659       | 2.73%   |
| Skylake          | 507       | 2.1%    |
| Bobcat           | 464       | 1.92%   |
| Unknown          | 385       | 1.59%   |
| P6               | 329       | 1.36%   |
| K10 Llano        | 312       | 1.29%   |
| Nehalem          | 257       | 1.06%   |
| Broadwell        | 213       | 0.88%   |
| Puma             | 203       | 0.84%   |
| Bulldozer        | 187       | 0.77%   |
| Jaguar           | 175       | 0.72%   |
| Zen              | 173       | 0.72%   |
| Excavator        | 169       | 0.7%    |
| Steamroller      | 144       | 0.6%    |
| Zen+             | 136       | 0.56%   |
| K8 & K10 hybrid  | 114       | 0.47%   |
| Goldmont         | 82        | 0.34%   |
| Goldmont plus    | 62        | 0.26%   |
| Zen 2            | 61        | 0.25%   |
| CometLake        | 36        | 0.15%   |
| K6               | 26        | 0.11%   |
| Zen 3            | 21        | 0.09%   |
| Icelake          | 17        | 0.07%   |
| TigerLake        | 14        | 0.06%   |
| Tremont          | 2         | 0.01%   |
| Alderlake Hybrid | 1         | 0.004%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 10387     | 37.66%  |
| Nvidia                           | 9955      | 36.09%  |
| AMD                              | 7085      | 25.69%  |
| Silicon Integrated Systems [SiS] | 61        | 0.22%   |
| VIA Technologies                 | 48        | 0.17%   |
| Matrox Electronics Systems       | 19        | 0.07%   |
| ASPEED Technology                | 14        | 0.05%   |
| ATI Technologies                 | 7         | 0.03%   |
| S3 Graphics                      | 5         | 0.02%   |
| Trident Microsystems             | 1         | 0.004%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1969      | 6.64%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 1333      | 4.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 557       | 1.88%   |
| Intel Core Processor Integrated Graphics Controller                                      | 549       | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 499       | 1.68%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 491       | 1.66%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 419       | 1.41%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 403       | 1.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 369       | 1.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 361       | 1.22%   |
| Nvidia GT218 [GeForce 210]                                                               | 357       | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 351       | 1.18%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 351       | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 343       | 1.16%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 299       | 1.01%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 268       | 0.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 266       | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 258       | 0.87%   |
| Nvidia G94 [GeForce 9600 GT]                                                             | 242       | 0.82%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 236       | 0.8%    |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 233       | 0.79%   |
| Nvidia GK107 [GeForce GTX 650]                                                           | 227       | 0.77%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 219       | 0.74%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 208       | 0.7%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 207       | 0.7%    |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 206       | 0.69%   |
| Nvidia GF116 [GeForce GTX 550 Ti]                                                        | 202       | 0.68%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 193       | 0.65%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 192       | 0.65%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 190       | 0.64%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 186       | 0.63%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 177       | 0.6%    |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 174       | 0.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 173       | 0.58%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 166       | 0.56%   |
| Intel HD Graphics 5500                                                                   | 164       | 0.55%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 163       | 0.55%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 159       | 0.54%   |
| Nvidia G92 [GeForce GTS 250]                                                             | 158       | 0.53%   |
| Nvidia G84 [GeForce 8600 GT]                                                             | 157       | 0.53%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 156       | 0.53%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 154       | 0.52%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 152       | 0.51%   |
| Nvidia GK106 [GeForce GTX 660]                                                           | 146       | 0.49%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 146       | 0.49%   |
| Nvidia G92 [GeForce 9800 GT]                                                             | 137       | 0.46%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 136       | 0.46%   |
| Nvidia GT215 [GeForce GT 240]                                                            | 129       | 0.43%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 129       | 0.43%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 127       | 0.43%   |
| AMD RS780L [Radeon 3000]                                                                 | 124       | 0.42%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 119       | 0.4%    |
| Nvidia GK107 [GeForce GT 640]                                                            | 119       | 0.4%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 118       | 0.4%    |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 118       | 0.4%    |
| Nvidia GM108M [GeForce 840M]                                                             | 117       | 0.39%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 116       | 0.39%   |
| Nvidia GT218M [GeForce 310M]                                                             | 114       | 0.38%   |
| Nvidia GK104 [GeForce GTX 760]                                                           | 113       | 0.38%   |
| Nvidia GF106 [GeForce GTS 450]                                                           | 110       | 0.37%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| 1 x Nvidia                    | 7458      | 30.66%  |
| 1 x Intel                     | 7122      | 29.28%  |
| 1 x AMD                       | 5410      | 22.24%  |
| Intel + Nvidia                | 2436      | 10.02%  |
| 2 x AMD                       | 1012      | 4.16%   |
| Intel + AMD                   | 651       | 2.68%   |
| 1 x SiS                       | 61        | 0.25%   |
| 1 x VIA                       | 48        | 0.2%    |
| AMD + Nvidia                  | 34        | 0.14%   |
| 2 x Nvidia                    | 30        | 0.12%   |
| 1 x Matrox                    | 17        | 0.07%   |
| Other                         | 13        | 0.05%   |
| 1 x ASPEED                    | 9         | 0.04%   |
| 1 x S3 Graphics               | 4         | 0.02%   |
| 3 x AMD                       | 3         | 0.01%   |
| AMD + ASPEED                  | 3         | 0.01%   |
| 3 x Nvidia                    | 2         | 0.01%   |
| Nvidia + Matrox               | 2         | 0.01%   |
| Nvidia + ASPEED               | 2         | 0.01%   |
| 2 x AMD + 1 x Nvidia          | 1         | 0.004%  |
| 1 x Trident Microsystems      | 1         | 0.004%  |
| Intel + 2 x Nvidia            | 1         | 0.004%  |
| Intel + SiS + 1 x S3 Graphics | 1         | 0.004%  |
| AMD + 2 x Nvidia              | 1         | 0.004%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 20255     | 80.19%  |
| Proprietary | 3518      | 13.93%  |
| Unknown     | 1487      | 5.89%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 8078      | 31.67%  |
| 0.01-0.5   | 7002      | 27.45%  |
| Unknown    | 5116      | 20.05%  |
| 0.51-1.0   | 3707      | 14.53%  |
| 3.01-4.0   | 1240      | 4.86%   |
| 2.01-3.0   | 139       | 0.54%   |
| 7.01-8.0   | 128       | 0.5%    |
| 5.01-6.0   | 90        | 0.35%   |
| 8.01-16.0  | 10        | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 5294      | 22.23%  |
| AU Optronics            | 2633      | 11.06%  |
| LG Display              | 2120      | 8.9%    |
| Goldstar                | 2067      | 8.68%   |
| Acer                    | 1421      | 5.97%   |
| Chi Mei Optoelectronics | 1131      | 4.75%   |
| BenQ                    | 1000      | 4.2%    |
| Chimei Innolux          | 878       | 3.69%   |
| Philips                 | 811       | 3.41%   |
| ViewSonic               | 586       | 2.46%   |
| BOE                     | 530       | 2.23%   |
| Dell                    | 520       | 2.18%   |
| Ancor Communications    | 509       | 2.14%   |
| AOC                     | 419       | 1.76%   |
| LG Philips              | 403       | 1.69%   |
| Hewlett-Packard         | 391       | 1.64%   |
| Lenovo                  | 375       | 1.57%   |
| HannStar                | 311       | 1.31%   |
| NEC Computers           | 306       | 1.29%   |
| Sony                    | 199       | 0.84%   |
| CPT                     | 178       | 0.75%   |
| Iiyama                  | 121       | 0.51%   |
| InfoVision              | 118       | 0.5%    |
| Apple                   | 103       | 0.43%   |
| Plain Tree Systems      | 79        | 0.33%   |
| Toshiba                 | 73        | 0.31%   |
| Envision Peripherals    | 54        | 0.23%   |
| Fujitsu Siemens         | 52        | 0.22%   |
| InnoLux Display         | 49        | 0.21%   |
| Quanta Display          | 48        | 0.2%    |
| Packard Bell            | 47        | 0.2%    |
| Unknown                 | 46        | 0.19%   |
| ___                     | 39        | 0.16%   |
| Sharp                   | 39        | 0.16%   |
| Panasonic               | 39        | 0.16%   |
| MiTAC                   | 39        | 0.16%   |
| Belinea                 | 29        | 0.12%   |
| Hitachi                 | 24        | 0.1%    |
| Medion                  | 23        | 0.1%    |
| ASUSTek Computer        | 23        | 0.1%    |
| PANDA                   | 22        | 0.09%   |
| MStar                   | 21        | 0.09%   |
| Eizo                    | 21        | 0.09%   |
| JRY                     | 19        | 0.08%   |
| HKC                     | 19        | 0.08%   |
| VIE                     | 18        | 0.08%   |
| Nvidia                  | 18        | 0.08%   |
| KTC                     | 18        | 0.08%   |
| Haier                   | 16        | 0.07%   |
| CVT                     | 16        | 0.07%   |
| eMachines               | 15        | 0.06%   |
| IBM                     | 14        | 0.06%   |
| LSC                     | 13        | 0.05%   |
| BBK                     | 13        | 0.05%   |
| Hyundai ImageQuest      | 12        | 0.05%   |
| RoverScan               | 10        | 0.04%   |
| Sceptre Tech            | 9         | 0.04%   |
| S2-Tek                  | 9         | 0.04%   |
| RTK                     | 9         | 0.04%   |
| MSI                     | 9         | 0.04%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 328       | 1.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch             | 292       | 1.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 232       | 0.96%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch             | 203       | 0.84%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch      | 145       | 0.6%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch               | 130       | 0.54%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch      | 126       | 0.52%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                 | 119       | 0.49%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch             | 112       | 0.46%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch      | 108       | 0.45%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch      | 99        | 0.41%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 99        | 0.41%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch             | 97        | 0.4%    |
| Samsung Electronics SyncMaster SAM01B7 1280x1024 338x270mm 17.0-inch      | 94        | 0.39%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch      | 92        | 0.38%   |
| Lenovo LCD Monitor LEN40B0 1366x768 345x194mm 15.6-inch                   | 91        | 0.38%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch             | 91        | 0.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch  | 90        | 0.37%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch               | 86        | 0.35%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch      | 74        | 0.31%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 72        | 0.3%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch  | 71        | 0.29%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 68        | 0.28%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 66        | 0.27%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                       | 66        | 0.27%   |
| Acer AL1716 ACRAD46 1280x1024 338x270mm 17.0-inch                         | 65        | 0.27%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch               | 62        | 0.26%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch               | 60        | 0.25%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch           | 59        | 0.24%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 57        | 0.24%   |
| AU Optronics LCD Monitor AUO139E 1600x900 382x214mm 17.2-inch             | 57        | 0.24%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch             | 56        | 0.23%   |
| Goldstar W1942 GSM4B6F 1440x900 408x255mm 18.9-inch                       | 55        | 0.23%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch             | 55        | 0.23%   |
| HannStar HSD121PHW1 HSD04B6 1366x768 270x150mm 12.2-inch                  | 54        | 0.22%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch      | 53        | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 53        | 0.22%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch  | 53        | 0.22%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 480x270mm 21.7-inch                   | 51        | 0.21%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch               | 51        | 0.21%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch               | 51        | 0.21%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch      | 49        | 0.2%    |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch             | 49        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15BE 1366x768 344x193mm 15.5-inch           | 49        | 0.2%    |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch  | 49        | 0.2%    |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch      | 48        | 0.2%    |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch      | 48        | 0.2%    |
| LG Display LCD Monitor LGD01E8 1366x768 344x194mm 15.5-inch               | 48        | 0.2%    |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch           | 47        | 0.19%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 47        | 0.19%   |
| Samsung Electronics SME1920NR SAM06A4 1280x1024 376x301mm 19.0-inch       | 46        | 0.19%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 46        | 0.19%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 46        | 0.19%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch      | 46        | 0.19%   |
| Samsung Electronics LCD Monitor SAM0902 1920x1080 700x390mm 31.5-inch     | 46        | 0.19%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch       | 45        | 0.19%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch             | 44        | 0.18%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch      | 42        | 0.17%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch      | 42        | 0.17%   |
| HannStar HSD101PFW4A HSD03ED 1024x600 223x125mm 10.1-inch                 | 42        | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 6772      | 28.69%  |
| 1920x1080 (FHD)    | 6344      | 26.88%  |
| 1280x1024 (SXGA)   | 3133      | 13.28%  |
| 1600x900 (HD+)     | 1507      | 6.39%   |
| 1280x800 (WXGA)    | 1241      | 5.26%   |
| 1440x900 (WXGA+)   | 1081      | 4.58%   |
| 1680x1050 (WSXGA+) | 1063      | 4.5%    |
| 1024x600           | 579       | 2.45%   |
| 1920x1200 (WUXGA)  | 343       | 1.45%   |
| 1024x768 (XGA)     | 282       | 1.19%   |
| 1360x768           | 275       | 1.17%   |
| 3840x2160 (4K)     | 250       | 1.06%   |
| 2560x1440 (QHD)    | 146       | 0.62%   |
| 1600x1200          | 146       | 0.62%   |
| 2560x1080          | 82        | 0.35%   |
| 1920x540           | 59        | 0.25%   |
| 1280x720 (HD)      | 57        | 0.24%   |
| 1400x1050          | 47        | 0.2%    |
| 1152x864           | 36        | 0.15%   |
| 2288x1287          | 22        | 0.09%   |
| 1680x945           | 19        | 0.08%   |
| 2048x1536          | 16        | 0.07%   |
| 2048x1152          | 13        | 0.06%   |
| 3440x1440          | 12        | 0.05%   |
| 1920x1440          | 12        | 0.05%   |
| 1280x960           | 12        | 0.05%   |
| 2560x1600          | 9         | 0.04%   |
| 1280x768           | 8         | 0.03%   |
| 1024x576           | 8         | 0.03%   |
| 2160x1440          | 5         | 0.02%   |
| 3200x1800 (QHD+)   | 3         | 0.01%   |
| 2880x1800          | 3         | 0.01%   |
| 2736x1824          | 3         | 0.01%   |
| 2880x1920          | 2         | 0.01%   |
| Unknown            | 2         | 0.01%   |
| 832x624            | 1         | 0.004%  |
| 640x480            | 1         | 0.004%  |
| 3840x2560          | 1         | 0.004%  |
| 3840x1200          | 1         | 0.004%  |
| 1920x1280          | 1         | 0.004%  |
| 1792x768           | 1         | 0.004%  |
| 1792x1344          | 1         | 0.004%  |
| 1360x765           | 1         | 0.004%  |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 7421      | 31.05%  |
| 17      | 2667      | 11.16%  |
| 19      | 2190      | 9.16%   |
| 21      | 2084      | 8.72%   |
| 23      | 1728      | 7.23%   |
| 24      | 983       | 4.11%   |
| 18      | 951       | 3.98%   |
| 20      | 781       | 3.27%   |
| 14      | 779       | 3.26%   |
| 10      | 626       | 2.62%   |
| 13      | 610       | 2.55%   |
| 22      | 604       | 2.53%   |
| 27      | 589       | 2.46%   |
| 11      | 321       | 1.34%   |
| 12      | 248       | 1.04%   |
| Unknown | 189       | 0.79%   |
| 31      | 134       | 0.56%   |
| 72      | 120       | 0.5%    |
| 54      | 115       | 0.48%   |
| 40      | 98        | 0.41%   |
| 16      | 92        | 0.38%   |
| 32      | 89        | 0.37%   |
| 34      | 65        | 0.27%   |
| 52      | 51        | 0.21%   |
| 25      | 50        | 0.21%   |
| 84      | 43        | 0.18%   |
| 26      | 43        | 0.18%   |
| 8       | 34        | 0.14%   |
| 48      | 29        | 0.12%   |
| 46      | 20        | 0.08%   |
| 42      | 18        | 0.08%   |
| 43      | 16        | 0.07%   |
| 28      | 14        | 0.06%   |
| 37      | 12        | 0.05%   |
| 55      | 10        | 0.04%   |
| 29      | 8         | 0.03%   |
| 65      | 7         | 0.03%   |
| 47      | 6         | 0.03%   |
| 41      | 6         | 0.03%   |
| 39      | 6         | 0.03%   |
| 33      | 6         | 0.03%   |
| 50      | 5         | 0.02%   |
| 9       | 5         | 0.02%   |
| 99      | 4         | 0.02%   |
| 57      | 4         | 0.02%   |
| 142     | 3         | 0.01%   |
| 74      | 2         | 0.01%   |
| 60      | 2         | 0.01%   |
| 59      | 2         | 0.01%   |
| 49      | 2         | 0.01%   |
| 36      | 2         | 0.01%   |
| 115     | 1         | 0.004%  |
| 95      | 1         | 0.004%  |
| 75      | 1         | 0.004%  |
| 69      | 1         | 0.004%  |
| 64      | 1         | 0.004%  |
| 30      | 1         | 0.004%  |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 9701      | 40.96%  |
| 401-500        | 5096      | 21.52%  |
| 501-600        | 3218      | 13.59%  |
| 351-400        | 2913      | 12.3%   |
| 201-300        | 1597      | 6.74%   |
| 1001-1500      | 253       | 1.07%   |
| 601-700        | 189       | 0.8%    |
| Unknown        | 189       | 0.8%    |
| 1501-2000      | 168       | 0.71%   |
| 701-800        | 160       | 0.68%   |
| 801-900        | 119       | 0.5%    |
| 901-1000       | 38        | 0.16%   |
| 101-200        | 36        | 0.15%   |
| More than 2000 | 8         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 15543     | 67%     |
| 16/10   | 3598      | 15.51%  |
| 5/4     | 2934      | 12.65%  |
| 4/3     | 785       | 3.38%   |
| 3/2     | 176       | 0.76%   |
| 21/9    | 71        | 0.31%   |
| 6/5     | 55        | 0.24%   |
| Unknown | 21        | 0.09%   |
| 32/9    | 9         | 0.04%   |
| 1.00    | 4         | 0.02%   |
| 2.21    | 1         | 0.004%  |
| 2.00    | 1         | 0.004%  |
| 1.96    | 1         | 0.004%  |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 7160      | 30.09%  |
| 201-250        | 4614      | 19.39%  |
| 151-200        | 3633      | 15.27%  |
| 141-150        | 2241      | 9.42%   |
| 81-90          | 1030      | 4.33%   |
| 121-130        | 875       | 3.68%   |
| 41-50          | 629       | 2.64%   |
| 301-350        | 625       | 2.63%   |
| More than 1000 | 400       | 1.68%   |
| 251-300        | 330       | 1.39%   |
| 131-140        | 322       | 1.35%   |
| 51-60          | 321       | 1.35%   |
| 71-80          | 306       | 1.29%   |
| 351-500        | 295       | 1.24%   |
| 111-120        | 235       | 0.99%   |
| 61-70          | 229       | 0.96%   |
| 501-1000       | 193       | 0.81%   |
| Unknown        | 189       | 0.79%   |
| 91-100         | 136       | 0.57%   |
| 1-40           | 36        | 0.15%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 11569     | 49.71%  |
| 101-120       | 8904      | 38.26%  |
| 121-160       | 1925      | 8.27%   |
| 1-50          | 504       | 2.17%   |
| Unknown       | 189       | 0.81%   |
| 161-240       | 157       | 0.67%   |
| More than 240 | 25        | 0.11%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 22594     | 92.71%  |
| 2     | 1299      | 5.33%   |
| 0     | 440       | 1.81%   |
| 3     | 38        | 0.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 14546     | 39.5%   |
| Qualcomm Atheros                       | 7516      | 20.41%  |
| Intel                                  | 4106      | 11.15%  |
| Broadcom                               | 2754      | 7.48%   |
| Nvidia                                 | 1204      | 3.27%   |
| Marvell Technology Group               | 1007      | 2.73%   |
| Broadcom Limited                       | 797       | 2.16%   |
| Ralink                                 | 792       | 2.15%   |
| Huawei Technologies                    | 641       | 1.74%   |
| Ralink Technology                      | 546       | 1.48%   |
| VIA Technologies                       | 310       | 0.84%   |
| Qualcomm Atheros Communications        | 233       | 0.63%   |
| D-Link System                          | 200       | 0.54%   |
| D-Link                                 | 186       | 0.51%   |
| JMicron Technology                     | 168       | 0.46%   |
| ASUSTek Computer                       | 157       | 0.43%   |
| Attansic Technology                    | 147       | 0.4%    |
| TP-Link                                | 141       | 0.38%   |
| ZTE WCDMA Technologies MSM             | 131       | 0.36%   |
| Silicon Integrated Systems [SiS]       | 130       | 0.35%   |
| MediaTek                               | 108       | 0.29%   |
| Samsung Electronics                    | 73        | 0.2%    |
| Sundance Technology Inc / IC Plus      | 63        | 0.17%   |
| HTC (High Tech Computer)               | 57        | 0.15%   |
| Xiaomi                                 | 55        | 0.15%   |
| Gemtek                                 | 48        | 0.13%   |
| 3Com                                   | 45        | 0.12%   |
| NetGear                                | 43        | 0.12%   |
| Ericsson Business Mobile Networks      | 38        | 0.1%    |
| ASIX Electronics                       | 24        | 0.07%   |
| Hewlett-Packard                        | 23        | 0.06%   |
| LSI                                    | 22        | 0.06%   |
| T & A Mobile Phones                    | 21        | 0.06%   |
| Qualcomm                               | 21        | 0.06%   |
| IMC Networks                           | 20        | 0.05%   |
| ZyXEL Communications                   | 18        | 0.05%   |
| Sony Ericsson Mobile Communications AB | 18        | 0.05%   |
| Microsoft                              | 18        | 0.05%   |
| Lenovo                                 | 17        | 0.05%   |
| GCT Semiconductor                      | 16        | 0.04%   |
| AMD                                    | 15        | 0.04%   |
| Spreadtrum Communications              | 14        | 0.04%   |
| NTmore                                 | 14        | 0.04%   |
| Dell                                   | 14        | 0.04%   |
| Vimtron Electronics                    | 13        | 0.04%   |
| Edimax Technology                      | 13        | 0.04%   |
| Belkin Components                      | 13        | 0.04%   |
| Nokia Mobile Phones                    | 12        | 0.03%   |
| U-Blox                                 | 10        | 0.03%   |
| ULi Electronics                        | 9         | 0.02%   |
| Mercucys                               | 9         | 0.02%   |
| Linksys                                | 9         | 0.02%   |
| ICS Advent                             | 9         | 0.02%   |
| ZyDAS                                  | 8         | 0.02%   |
| Sierra Wireless                        | 8         | 0.02%   |
| Motorola PCS                           | 8         | 0.02%   |
| LG Electronics                         | 8         | 0.02%   |
| Davicom Semiconductor                  | 8         | 0.02%   |
| Android                                | 7         | 0.02%   |
| ADMtek                                 | 7         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 10285     | 25.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 2744      | 6.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1915      | 4.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 1150      | 2.81%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 843       | 2.06%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 830       | 2.03%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 692       | 1.69%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 572       | 1.4%    |
| Nvidia MCP61 Ethernet                                                   | 569       | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 558       | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 473       | 1.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 442       | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                           | 367       | 0.9%    |
| Huawei Modem/Networkcard                                                | 360       | 0.88%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                | 316       | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 302       | 0.74%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 301       | 0.74%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 281       | 0.69%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 276       | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 270       | 0.66%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                           | 267       | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 259       | 0.63%   |
| Ralink MT7601U Wireless Adapter                                         | 253       | 0.62%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 251       | 0.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 249       | 0.61%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 248       | 0.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 240       | 0.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 220       | 0.54%   |
| Intel 82579V Gigabit Network Connection                                 | 218       | 0.53%   |
| Intel WiFi Link 5100                                                    | 215       | 0.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 211       | 0.52%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 200       | 0.49%   |
| VIA VT6105/VT6106S [Rhine-III]                                          | 189       | 0.46%   |
| Qualcomm Atheros AR9271 802.11n                                         | 188       | 0.46%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 185       | 0.45%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 170       | 0.42%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                         | 166       | 0.41%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 165       | 0.4%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                 | 159       | 0.39%   |
| Intel Centrino Wireless-N 130                                           | 155       | 0.38%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 153       | 0.37%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                               | 150       | 0.37%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 150       | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 149       | 0.36%   |
| Intel Wireless 7260                                                     | 149       | 0.36%   |
| Attansic AR8152 v2.0 Fast Ethernet                                      | 147       | 0.36%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 140       | 0.34%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 137       | 0.33%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 134       | 0.33%   |
| Intel Ethernet Connection (2) I219-V                                    | 133       | 0.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 132       | 0.32%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 131       | 0.32%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 127       | 0.31%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                  | 126       | 0.31%   |
| Ralink RT5370 Wireless Adapter                                          | 125       | 0.31%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                              | 123       | 0.3%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 122       | 0.3%    |
| Intel Centrino Wireless-N 2230                                          | 122       | 0.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 115       | 0.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller               | 114       | 0.28%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 5437      | 36.4%   |
| Intel                                 | 2722      | 18.23%  |
| Realtek Semiconductor                 | 2117      | 14.17%  |
| Broadcom                              | 1881      | 12.59%  |
| Ralink                                | 792       | 5.3%    |
| Ralink Technology                     | 546       | 3.66%   |
| Broadcom Limited                      | 361       | 2.42%   |
| Qualcomm Atheros Communications       | 233       | 1.56%   |
| D-Link                                | 179       | 1.2%    |
| ASUSTek Computer                      | 140       | 0.94%   |
| TP-Link                               | 138       | 0.92%   |
| D-Link System                         | 110       | 0.74%   |
| NetGear                               | 42        | 0.28%   |
| MediaTek                              | 42        | 0.28%   |
| IMC Networks                          | 20        | 0.13%   |
| Microsoft                             | 17        | 0.11%   |
| ZyXEL Communications                  | 14        | 0.09%   |
| Edimax Technology                     | 13        | 0.09%   |
| Belkin Components                     | 12        | 0.08%   |
| Mercucys                              | 9         | 0.06%   |
| Linksys                               | 9         | 0.06%   |
| Sierra Wireless                       | 8         | 0.05%   |
| Marvell Technology Group              | 8         | 0.05%   |
| Dell                                  | 8         | 0.05%   |
| ZyDAS                                 | 7         | 0.05%   |
| Micro Star International              | 6         | 0.04%   |
| Gemtek                                | 6         | 0.04%   |
| Tenda                                 | 5         | 0.03%   |
| Sitecom Europe                        | 5         | 0.03%   |
| Sagem                                 | 5         | 0.03%   |
| Hewlett-Packard                       | 5         | 0.03%   |
| TRENDnet                              | 4         | 0.03%   |
| Fujitsu Siemens Computers             | 4         | 0.03%   |
| VIA Technologies                      | 3         | 0.02%   |
| Texas Instruments                     | 3         | 0.02%   |
| BUFFALO                               | 3         | 0.02%   |
| Accton Technology                     | 3         | 0.02%   |
| AboCom Systems                        | 3         | 0.02%   |
| Wacom                                 | 2         | 0.01%   |
| Qualcomm                              | 2         | 0.01%   |
| Qcom                                  | 2         | 0.01%   |
| ASUSTek Computer (wrong ID)           | 2         | 0.01%   |
| Z-Com                                 | 1         | 0.01%   |
| Silicon Integrated Systems [SiS]      | 1         | 0.01%   |
| Philips (or NXP)                      | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |
| Chu Yuen Enterprise                   | 1         | 0.01%   |
| AVM                                   | 1         | 0.01%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Computers | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 1915      | 12.72%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1150      | 7.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 830       | 5.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 692       | 4.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 572       | 3.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 473       | 3.14%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 442       | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 367       | 2.44%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 259       | 1.72%   |
| Ralink MT7601U Wireless Adapter                                               | 253       | 1.68%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 251       | 1.67%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 240       | 1.59%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 220       | 1.46%   |
| Intel WiFi Link 5100                                                          | 215       | 1.43%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 211       | 1.4%    |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 200       | 1.33%   |
| Qualcomm Atheros AR9271 802.11n                                               | 188       | 1.25%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 185       | 1.23%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                               | 166       | 1.1%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 165       | 1.1%    |
| Intel Centrino Wireless-N 130                                                 | 155       | 1.03%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 153       | 1.02%   |
| Intel Wireless 7260                                                           | 149       | 0.99%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 134       | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 132       | 0.88%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 131       | 0.87%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                        | 127       | 0.84%   |
| Ralink RT5370 Wireless Adapter                                                | 125       | 0.83%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 122       | 0.81%   |
| Intel Centrino Wireless-N 2230                                                | 122       | 0.81%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 106       | 0.7%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 101       | 0.67%   |
| Intel WiMAX/WiFi Link 5150                                                    | 98        | 0.65%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                              | 97        | 0.64%   |
| Intel Wireless 7265                                                           | 97        | 0.64%   |
| Intel Wireless 3165                                                           | 94        | 0.62%   |
| Intel Centrino Wireless-N 100                                                 | 93        | 0.62%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter                   | 90        | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                                    | 80        | 0.53%   |
| Ralink RT2870/RT3070 Wireless Adapter                                         | 79        | 0.52%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                                     | 77        | 0.51%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 75        | 0.5%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 72        | 0.48%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 69        | 0.46%   |
| Intel Centrino Advanced-N 6235                                                | 69        | 0.46%   |
| Intel Centrino Advanced-N 6200                                                | 69        | 0.46%   |
| Broadcom BCM43228 802.11a/b/g/n                                               | 69        | 0.46%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                          | 68        | 0.45%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 66        | 0.44%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 63        | 0.42%   |
| Broadcom BCM43227 802.11b/g/n                                                 | 62        | 0.41%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                       | 60        | 0.4%    |
| Ralink RT2561/RT61 rev B 802.11g                                              | 60        | 0.4%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                    | 60        | 0.4%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 60        | 0.4%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                               | 58        | 0.39%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                      | 56        | 0.37%   |
| Intel Wireless 3160                                                           | 54        | 0.36%   |
| D-Link 802.11 n WLAN                                                          | 52        | 0.35%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 46        | 0.31%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 13967     | 56.4%   |
| Qualcomm Atheros                       | 3160      | 12.76%  |
| Intel                                  | 2056      | 8.3%    |
| Nvidia                                 | 1203      | 4.86%   |
| Broadcom                               | 1146      | 4.63%   |
| Marvell Technology Group               | 1000      | 4.04%   |
| Broadcom Limited                       | 453       | 1.83%   |
| VIA Technologies                       | 299       | 1.21%   |
| JMicron Technology                     | 168       | 0.68%   |
| Attansic Technology                    | 147       | 0.59%   |
| Huawei Technologies                    | 141       | 0.57%   |
| Silicon Integrated Systems [SiS]       | 127       | 0.51%   |
| ZTE WCDMA Technologies MSM             | 121       | 0.49%   |
| D-Link System                          | 91        | 0.37%   |
| Samsung Electronics                    | 67        | 0.27%   |
| MediaTek                               | 64        | 0.26%   |
| Sundance Technology Inc / IC Plus      | 63        | 0.25%   |
| HTC (High Tech Computer)               | 57        | 0.23%   |
| Xiaomi                                 | 55        | 0.22%   |
| 3Com                                   | 45        | 0.18%   |
| Gemtek                                 | 42        | 0.17%   |
| ASIX Electronics                       | 24        | 0.1%    |
| Qualcomm                               | 19        | 0.08%   |
| T & A Mobile Phones                    | 18        | 0.07%   |
| ASUSTek Computer                       | 18        | 0.07%   |
| Sony Ericsson Mobile Communications AB | 17        | 0.07%   |
| GCT Semiconductor                      | 16        | 0.06%   |
| Lenovo                                 | 15        | 0.06%   |
| Spreadtrum Communications              | 14        | 0.06%   |
| NTmore                                 | 14        | 0.06%   |
| Vimtron Electronics                    | 13        | 0.05%   |
| ICS Advent                             | 9         | 0.04%   |
| ULi Electronics                        | 8         | 0.03%   |
| Davicom Semiconductor                  | 8         | 0.03%   |
| Motorola PCS                           | 7         | 0.03%   |
| D-Link                                 | 7         | 0.03%   |
| ADMtek                                 | 7         | 0.03%   |
| LG Electronics                         | 6         | 0.02%   |
| Android                                | 6         | 0.02%   |
| HMD Global                             | 5         | 0.02%   |
| ZyXEL Communications                   | 4         | 0.02%   |
| TP-Link                                | 3         | 0.01%   |
| Research In Motion                     | 3         | 0.01%   |
| OPPO Electronics                       | 3         | 0.01%   |
| LSI                                    | 3         | 0.01%   |
| Hewlett-Packard                        | 3         | 0.01%   |
| TOMTOM                                 | 2         | 0.01%   |
| SysKonnect                             | 2         | 0.01%   |
| National Semiconductor                 | 2         | 0.01%   |
| Lite-On Communications                 | 2         | 0.01%   |
| FS406                                  | 2         | 0.01%   |
| DisplayLink                            | 2         | 0.01%   |
| Digitech Systems                       | 2         | 0.01%   |
| Aquantia                               | 2         | 0.01%   |
| Accton Technology                      | 2         | 0.01%   |
| Yulong                                 | 1         | 0.004%  |
| Unknown                                | 1         | 0.004%  |
| Reply Group                            | 1         | 0.004%  |
| Prestigio                              | 1         | 0.004%  |
| OnePlus Technology (Shenzhen)          | 1         | 0.004%  |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 10285     | 41.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 2744      | 10.94%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 843       | 3.36%   |
| Nvidia MCP61 Ethernet                                                          | 569       | 2.27%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 558       | 2.23%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 316       | 1.26%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 302       | 1.2%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 301       | 1.2%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 281       | 1.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 276       | 1.1%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 270       | 1.08%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 267       | 1.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 249       | 0.99%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 248       | 0.99%   |
| Intel 82579V Gigabit Network Connection                                        | 218       | 0.87%   |
| VIA VT6105/VT6106S [Rhine-III]                                                 | 189       | 0.75%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 170       | 0.68%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 159       | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 150       | 0.6%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 150       | 0.6%    |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 149       | 0.59%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 147       | 0.59%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 140       | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 137       | 0.55%   |
| Intel Ethernet Connection (2) I219-V                                           | 133       | 0.53%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 126       | 0.5%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                                     | 123       | 0.49%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 115       | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 114       | 0.45%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                                     | 113       | 0.45%   |
| Intel WiMAX Connection 2400m                                                   | 113       | 0.45%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                              | 112       | 0.45%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 109       | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 107       | 0.43%   |
| Nvidia MCP77 Ethernet                                                          | 107       | 0.43%   |
| Nvidia CK804 Ethernet Controller                                               | 105       | 0.42%   |
| ZTE WCDMA MSM ZTE MSM                                                          | 104       | 0.41%   |
| Nvidia MCP51 Ethernet Controller                                               | 104       | 0.41%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 103       | 0.41%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                                  | 93        | 0.37%   |
| Intel 82577LM Gigabit Network Connection                                       | 93        | 0.37%   |
| Intel I211 Gigabit Network Connection                                          | 92        | 0.37%   |
| Nvidia MCP55 Ethernet                                                          | 90        | 0.36%   |
| Huawei E353/E3131                                                              | 89        | 0.35%   |
| Intel Ethernet Connection I217-V                                               | 85        | 0.34%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 77        | 0.31%   |
| Intel 82567LM Gigabit Network Connection                                       | 77        | 0.31%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 76        | 0.3%    |
| Nvidia MCP67 Ethernet                                                          | 75        | 0.3%    |
| Intel 82567LM-3 Gigabit Network Connection                                     | 75        | 0.3%    |
| Intel 82566DM-2 Gigabit Network Connection                                     | 75        | 0.3%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 74        | 0.3%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 71        | 0.28%   |
| Intel Ethernet Connection (2) I218-V                                           | 67        | 0.27%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 66        | 0.26%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 64        | 0.26%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 61        | 0.24%   |
| Nvidia MCP79 Ethernet                                                          | 58        | 0.23%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 54        | 0.22%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                                | 54        | 0.22%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 23278     | 60.47%  |
| WiFi     | 14426     | 37.47%  |
| Modem    | 764       | 1.98%   |
| Unknown  | 30        | 0.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 12930     | 52.93%  |
| WiFi     | 11486     | 47.02%  |
| Unknown  | 10        | 0.04%   |
| Modem    | 4         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 13024     | 54.03%  |
| 1     | 10613     | 44.03%  |
| 0     | 297       | 1.23%   |
| 3     | 153       | 0.63%   |
| 4     | 14        | 0.06%   |
| 6     | 2         | 0.01%   |
| 33    | 1         | 0.004%  |
| 16    | 1         | 0.004%  |
| 11    | 1         | 0.004%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 17114     | 67.82%  |
| Unknown | 8003      | 31.71%  |
| Yes     | 119       | 0.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Qualcomm Atheros Communications | 1287      | 15.65%  |
| Intel                           | 1090      | 13.26%  |
| Broadcom                        | 997       | 12.12%  |
| Realtek Semiconductor           | 728       | 8.85%   |
| Cambridge Silicon Radio         | 637       | 7.75%   |
| IMC Networks                    | 545       | 6.63%   |
| Foxconn / Hon Hai               | 545       | 6.63%   |
| Lite-On Technology              | 533       | 6.48%   |
| ASUSTek Computer                | 388       | 4.72%   |
| Ralink                          | 259       | 3.15%   |
| Hewlett-Packard                 | 222       | 2.7%    |
| Toshiba                         | 214       | 2.6%    |
| Dell                            | 186       | 2.26%   |
| Foxconn International           | 168       | 2.04%   |
| Apple                           | 107       | 1.3%    |
| Alps Electric                   | 72        | 0.88%   |
| Ralink Technology               | 59        | 0.72%   |
| Integrated System Solution      | 55        | 0.67%   |
| Chicony Electronics             | 20        | 0.24%   |
| Micro Star International        | 18        | 0.22%   |
| Taiyo Yuden                     | 15        | 0.18%   |
| MediaTek                        | 13        | 0.16%   |
| Askey Computer                  | 11        | 0.13%   |
| Qcom                            | 9         | 0.11%   |
| Roper                           | 8         | 0.1%    |
| USI                             | 7         | 0.09%   |
| Syntek                          | 4         | 0.05%   |
| Realtek                         | 4         | 0.05%   |
| Logitech                        | 4         | 0.05%   |
| Conwise Technology              | 4         | 0.05%   |
| Samsung Electronics             | 3         | 0.04%   |
| Belkin Components               | 3         | 0.04%   |
| Unknown                         | 2         | 0.02%   |
| Qualcomm Atheros                | 1         | 0.01%   |
| Primax Electronics              | 1         | 0.01%   |
| Marvell Semiconductor           | 1         | 0.01%   |
| D-Link                          | 1         | 0.01%   |
| Actiontec Electronics           | 1         | 0.01%   |
| AboCom Systems                  | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 637       | 7.74%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 502       | 6.1%    |
| Intel Bluetooth wireless interface                                                  | 495       | 6.02%   |
| Realtek Bluetooth Radio                                                             | 403       | 4.9%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 335       | 4.07%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 272       | 3.31%   |
| Ralink RT3290 Bluetooth                                                             | 259       | 3.15%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 201       | 2.44%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 194       | 2.36%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 189       | 2.3%    |
| Foxconn / Hon Hai Bluetooth Device                                                  | 185       | 2.25%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 166       | 2.02%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 163       | 1.98%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 156       | 1.9%    |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 147       | 1.79%   |
| Broadcom BCM2045 Bluetooth                                                          | 137       | 1.66%   |
| Realtek RTL8723B Bluetooth                                                          | 134       | 1.63%   |
| Lite-On Bluetooth Device                                                            | 131       | 1.59%   |
| IMC Networks Bluetooth Device                                                       | 119       | 1.45%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 115       | 1.4%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 111       | 1.35%   |
| Qualcomm Atheros Bluetooth                                                          | 97        | 1.18%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 96        | 1.17%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter                                               | 93        | 1.13%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 88        | 1.07%   |
| Toshiba Integrated Bluetooth HCI                                                    | 83        | 1.01%   |
| Broadcom HP Portable Valentine                                                      | 83        | 1.01%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 82        | 1%      |
| ASUS BT-270 Bluetooth Adapter                                                       | 75        | 0.91%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 70        | 0.85%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 69        | 0.84%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 69        | 0.84%   |
| IMC Networks Bluetooth Radio                                                        | 69        | 0.84%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 69        | 0.84%   |
| IMC Networks Bluetooth module                                                       | 68        | 0.83%   |
| Realtek RTL8723A Bluetooth                                                          | 65        | 0.79%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 64        | 0.78%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 60        | 0.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 56        | 0.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 45        | 0.55%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 43        | 0.52%   |
| Dell Wireless 360 Bluetooth                                                         | 41        | 0.5%    |
| Apple Bluetooth USB Host Controller                                                 | 41        | 0.5%    |
| Broadcom BCM20702A0                                                                 | 40        | 0.49%   |
| Toshiba Askey Bluetooth Module                                                      | 39        | 0.47%   |
| IMC Networks Bluetooth                                                              | 39        | 0.47%   |
| Dell Wireless 355 Bluetooth                                                         | 39        | 0.47%   |
| Apple Bluetooth Host Controller                                                     | 38        | 0.46%   |
| Integrated System Solution Bluetooth Device                                         | 36        | 0.44%   |
| IMC Networks Bluetooth USB Host Controller                                          | 36        | 0.44%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth                                       | 36        | 0.44%   |
| ASUS Bluetooth Adapter                                                              | 36        | 0.44%   |
| Toshiba RT Bluetooth Radio                                                          | 34        | 0.41%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 34        | 0.41%   |
| Qualcomm Atheros Bluetooth (AR3011)                                                 | 33        | 0.4%    |
| Lite-On Atheros Bluetooth                                                           | 33        | 0.4%    |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 33        | 0.4%    |
| Alps Electric BCM2046 Bluetooth Device                                              | 33        | 0.4%    |
| Intel AX200 Bluetooth                                                               | 32        | 0.39%   |
| Dell DW375 Bluetooth Module                                                         | 32        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 16649     | 52%     |
| AMD                                             | 7118      | 22.23%  |
| Nvidia                                          | 6236      | 19.48%  |
| C-Media Electronics                             | 534       | 1.67%   |
| Creative Labs                                   | 435       | 1.36%   |
| VIA Technologies                                | 211       | 0.66%   |
| Silicon Integrated Systems [SiS]                | 183       | 0.57%   |
| Creative Technology                             | 77        | 0.24%   |
| Logitech                                        | 61        | 0.19%   |
| JMTek                                           | 33        | 0.1%    |
| Texas Instruments                               | 32        | 0.1%    |
| Plantronics                                     | 25        | 0.08%   |
| Generalplus Technology                          | 24        | 0.07%   |
| Ensoniq                                         | 23        | 0.07%   |
| Tenx Technology                                 | 18        | 0.06%   |
| Pixart Imaging                                  | 18        | 0.06%   |
| ASUSTek Computer                                | 17        | 0.05%   |
| ULi Electronics                                 | 16        | 0.05%   |
| Yamaha                                          | 10        | 0.03%   |
| Shenzhen Rapoo Technology                       | 10        | 0.03%   |
| Razer USA                                       | 10        | 0.03%   |
| Aureal Semiconductor                            | 10        | 0.03%   |
| A4Tech                                          | 10        | 0.03%   |
| M-Audio                                         | 9         | 0.03%   |
| iCreate Technologies                            | 9         | 0.03%   |
| ESS Technology                                  | 9         | 0.03%   |
| Asahi Kasei Microsystems                        | 9         | 0.03%   |
| Guillemot                                       | 8         | 0.02%   |
| ATI Technologies                                | 8         | 0.02%   |
| Yealink Network Technology                      | 7         | 0.02%   |
| GYROCOM C&C                                     | 7         | 0.02%   |
| Focusrite-Novation                              | 7         | 0.02%   |
| Samson Technologies                             | 6         | 0.02%   |
| Philips (or NXP)                                | 6         | 0.02%   |
| Licensed by Sony Computer Entertainment America | 6         | 0.02%   |
| Fortemedia                                      | 6         | 0.02%   |
| Sony                                            | 5         | 0.02%   |
| Roland                                          | 5         | 0.02%   |
| Microsoft                                       | 5         | 0.02%   |
| Kingston Technology                             | 5         | 0.02%   |
| EGO SYStems                                     | 5         | 0.02%   |
| DigiTech                                        | 5         | 0.02%   |
| Corsair                                         | 5         | 0.02%   |
| XMOS                                            | 4         | 0.01%   |
| Thesycon Systemsoftware & Consulting            | 4         | 0.01%   |
| Sennheiser Communications                       | 4         | 0.01%   |
| Dell                                            | 4         | 0.01%   |
| Conexant Systems                                | 4         | 0.01%   |
| Veho                                            | 3         | 0.01%   |
| Unknown                                         | 3         | 0.01%   |
| Syntek                                          | 3         | 0.01%   |
| SAVITECH                                        | 3         | 0.01%   |
| QinHeng Electronics                             | 3         | 0.01%   |
| GN Netcom                                       | 3         | 0.01%   |
| Elite Silicon                                   | 3         | 0.01%   |
| BEHRINGER International                         | 3         | 0.01%   |
| Xilinx                                          | 2         | 0.01%   |
| X-TENSIONS                                      | 2         | 0.01%   |
| Winbond Electronics                             | 2         | 0.01%   |
| TerraTec Electronic                             | 2         | 0.01%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 3049      | 8.26%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2765      | 7.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 2537      | 6.88%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2503      | 6.78%   |
| AMD FCH Azalia Controller                                                                         | 1527      | 4.14%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 1386      | 3.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1270      | 3.44%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 1039      | 2.82%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 861       | 2.33%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 837       | 2.27%   |
| Nvidia High Definition Audio Controller                                                           | 743       | 2.01%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 640       | 1.73%   |
| Nvidia MCP61 High Definition Audio                                                                | 623       | 1.69%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 571       | 1.55%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 531       | 1.44%   |
| AMD Kabini HDMI/DP Audio                                                                          | 437       | 1.18%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 428       | 1.16%   |
| Intel 8 Series HD Audio Controller                                                                | 425       | 1.15%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 423       | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 419       | 1.14%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 405       | 1.1%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 397       | 1.08%   |
| AMD Wrestler HDMI Audio                                                                           | 388       | 1.05%   |
| AMD Trinity HDMI Audio Controller                                                                 | 378       | 1.02%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 374       | 1.01%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 374       | 1.01%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 354       | 0.96%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 325       | 0.88%   |
| Nvidia GF116 High Definition Audio Controller                                                     | 291       | 0.79%   |
| Nvidia GK106 HDMI Audio Controller                                                                | 284       | 0.77%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 281       | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 271       | 0.73%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 270       | 0.73%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 268       | 0.73%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 243       | 0.66%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 242       | 0.66%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 233       | 0.63%   |
| Intel Broadwell-U Audio Controller                                                                | 206       | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 205       | 0.56%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 205       | 0.56%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 201       | 0.54%   |
| AMD Juniper HDMI Audio [Radeon HD 5700 Series]                                                    | 193       | 0.52%   |
| C-Media Electronics CMI8738/CMI8768 PCI Audio                                                     | 189       | 0.51%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 187       | 0.51%   |
| Intel 200 Series PCH HD Audio                                                                     | 185       | 0.5%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 178       | 0.48%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 166       | 0.45%   |
| Intel 82801EB/ER (ICH5/ICH5R) AC'97 Audio Controller                                              | 164       | 0.44%   |
| Nvidia GF114 HDMI Audio Controller                                                                | 160       | 0.43%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 153       | 0.41%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 141       | 0.38%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 139       | 0.38%   |
| Nvidia GF106 High Definition Audio Controller                                                     | 132       | 0.36%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 126       | 0.34%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 125       | 0.34%   |
| Intel Cannon Lake PCH cAVS                                                                        | 124       | 0.34%   |
| Nvidia MCP79 High Definition Audio                                                                | 121       | 0.33%   |
| Creative Labs CA0106/CA0111 [SB Live!/Audigy/X-Fi Series]                                         | 120       | 0.33%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 116       | 0.31%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 114       | 0.31%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 8864      | 33.49%  |
| Samsung Electronics   | 3692      | 13.95%  |
| Kingston              | 3505      | 13.24%  |
| SK Hynix              | 3083      | 11.65%  |
| Micron Technology     | 1059      | 4%      |
| Crucial               | 848       | 3.2%    |
| Elpida                | 771       | 2.91%   |
| Nanya Technology      | 704       | 2.66%   |
| Corsair               | 596       | 2.25%   |
| Ramaxel Technology    | 490       | 1.85%   |
| A-DATA Technology     | 458       | 1.73%   |
| Patriot               | 227       | 0.86%   |
| AMD                   | 198       | 0.75%   |
| ASint Technology      | 178       | 0.67%   |
| Goldkey               | 152       | 0.57%   |
| GOODRAM               | 137       | 0.52%   |
| Transcend             | 134       | 0.51%   |
| 48spaces              | 122       | 0.46%   |
| Silicon Power         | 103       | 0.39%   |
| G.Skill               | 89        | 0.34%   |
| Kingmax               | 88        | 0.33%   |
| Qimonda               | 76        | 0.29%   |
| SHARETRONIC           | 75        | 0.28%   |
| Qumo                  | 72        | 0.27%   |
| Unifosa               | 66        | 0.25%   |
| Team                  | 66        | 0.25%   |
| Apacer                | 61        | 0.23%   |
| GeIL                  | 57        | 0.22%   |
| Kllisre               | 43        | 0.16%   |
| Unknown (ABCD)        | 30        | 0.11%   |
| Toshiba               | 29        | 0.11%   |
| KETECH                | 28        | 0.11%   |
| Foxline               | 21        | 0.08%   |
| Unknown               | 19        | 0.07%   |
| TakeMS                | 16        | 0.06%   |
| Smart                 | 16        | 0.06%   |
| Kingmax Semiconductor | 16        | 0.06%   |
| Ramos Technology      | 14        | 0.05%   |
| HEXON                 | 13        | 0.05%   |
| Exceleram             | 12        | 0.05%   |
| OCZ                   | 11        | 0.04%   |
| TwinMOS               | 9         | 0.03%   |
| pqi                   | 8         | 0.03%   |
| PNY                   | 8         | 0.03%   |
| atermiter             | 8         | 0.03%   |
| Aeneon                | 8         | 0.03%   |
| Infineon              | 7         | 0.03%   |
| Kreton                | 6         | 0.02%   |
| Avant                 | 6         | 0.02%   |
| Teikon                | 5         | 0.02%   |
| SGS/Thomson           | 5         | 0.02%   |
| Swissbit              | 4         | 0.02%   |
| Super Talent          | 4         | 0.02%   |
| Netlist               | 4         | 0.02%   |
| KingTiger             | 4         | 0.02%   |
| High Bridge           | 4         | 0.02%   |
| Axiom                 | 4         | 0.02%   |
| V-Color               | 3         | 0.01%   |
| Unigen                | 3         | 0.01%   |
| SMART Brazil          | 3         | 0.01%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                                  | 481       | 1.6%    |
| Unknown RAM Module 2048MB DIMM SDRAM                                         | 473       | 1.57%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                                       | 439       | 1.46%   |
| Unknown RAM Module 1024MB DIMM SDRAM                                         | 413       | 1.37%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                                      | 369       | 1.23%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                                      | 347       | 1.15%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s                                  | 319       | 1.06%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 304       | 1.01%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                                  | 248       | 0.82%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                                       | 247       | 0.82%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 229       | 0.76%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                                | 217       | 0.72%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s                        | 216       | 0.72%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                                  | 205       | 0.68%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s                        | 202       | 0.67%   |
| Unknown RAM Module 2048MB SODIMM DDR2                                        | 201       | 0.67%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 193       | 0.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 189       | 0.63%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s                     | 177       | 0.59%   |
| Unknown RAM Module 1024MB SODIMM DDR2                                        | 176       | 0.58%   |
| Unknown RAM Module 1024MB DIMM 667MT/s                                       | 163       | 0.54%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s                        | 161       | 0.54%   |
| Unknown RAM Module 2048MB DIMM 667MT/s                                       | 160       | 0.53%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                                 | 159       | 0.53%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                                | 156       | 0.52%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 154       | 0.51%   |
| Unknown RAM Module 2048MB DIMM 400MT/s                                       | 146       | 0.49%   |
| Unknown RAM Module 512MB DIMM SDRAM                                          | 141       | 0.47%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s                       | 139       | 0.46%   |
| Unknown RAM Module 1024MB DIMM                                               | 138       | 0.46%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                                      | 131       | 0.44%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s                        | 128       | 0.43%   |
| SK Hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 125       | 0.42%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                                 | 123       | 0.41%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s                        | 122       | 0.41%   |
| Unknown RAM Module 4096MB SODIMM DDR3                                        | 120       | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 119       | 0.4%    |
| Kingston RAM KHX1600C9D3/4GX 4096MB DIMM DDR3 2400MT/s                       | 119       | 0.4%    |
| 48spaces RAM 012345678901234567890123456789012345 2048MB SODIMM DDR2 667MT/s | 114       | 0.38%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                         | 108       | 0.36%   |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                            | 104       | 0.35%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                                | 102       | 0.34%   |
| Unknown RAM Module 4096MB DIMM 400MT/s                                       | 101       | 0.34%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                                  | 100       | 0.33%   |
| Unknown RAM Module 1024MB DIMM DDR2                                          | 100       | 0.33%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                                  | 99        | 0.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                                 | 96        | 0.32%   |
| Samsung RAM M471B5673FH0-CF8 2048MB SODIMM DDR3 1067MT/s                     | 95        | 0.32%   |
| Unknown RAM Module 1024MB SODIMM DDR                                         | 94        | 0.31%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s                       | 92        | 0.31%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                                       | 91        | 0.3%    |
| Unknown RAM Module 1024MB SODIMM DRAM                                        | 90        | 0.3%    |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s                        | 89        | 0.3%    |
| Unknown RAM Module 2048MB DIMM 1066MT/s                                      | 86        | 0.29%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s                        | 83        | 0.28%   |
| Unknown RAM Module 2048MB DIMM                                               | 82        | 0.27%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s                         | 82        | 0.27%   |
| Elpida RAM EBJ21UE8BFU0-DJ-F 2GB SODIMM DDR3 1334MT/s                        | 81        | 0.27%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                                       | 79        | 0.26%   |
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                                  | 77        | 0.26%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 11676     | 49.93%  |
| DDR2    | 3781      | 16.17%  |
| Unknown | 2975      | 12.72%  |
| SDRAM   | 2271      | 9.71%   |
| DDR4    | 1675      | 7.16%   |
| DDR     | 705       | 3.01%   |
| DRAM    | 188       | 0.8%    |
| LPDDR4  | 83        | 0.35%   |
| LPDDR3  | 25        | 0.11%   |
| EEPROM  | 3         | 0.01%   |
| SRAM    | 1         | 0.004%  |
| RAM     | 1         | 0.004%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| DIMM         | 11724     | 51.42%  |
| SODIMM       | 11006     | 48.27%  |
| Row Of Chips | 35        | 0.15%   |
| Chip         | 22        | 0.1%    |
| FB-DIMM      | 9         | 0.04%   |
| Unknown      | 6         | 0.03%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 2048    | 9440      | 34.77%  |
| 4096    | 9349      | 34.43%  |
| 1024    | 4386      | 16.15%  |
| 8192    | 2606      | 9.6%    |
| 512     | 935       | 3.44%   |
| 256     | 193       | 0.71%   |
| 16384   | 187       | 0.69%   |
| 32768   | 27        | 0.1%    |
| Unknown | 10        | 0.04%   |
| 128     | 6         | 0.02%   |
| 32      | 4         | 0.01%   |
| 1       | 3         | 0.01%   |
| 16      | 2         | 0.01%   |
| 32767   | 1         | 0.004%  |
| 1536    | 1         | 0.004%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 6508      | 25.55%  |
| 1333    | 3635      | 14.27%  |
| Unknown | 2495      | 9.8%    |
| 800     | 2224      | 8.73%   |
| 667     | 2149      | 8.44%   |
| 1334    | 2026      | 7.95%   |
| 2400    | 686       | 2.69%   |
| 1067    | 545       | 2.14%   |
| 2667    | 503       | 1.97%   |
| 400     | 494       | 1.94%   |
| 2133    | 477       | 1.87%   |
| 533     | 475       | 1.86%   |
| 4199    | 421       | 1.65%   |
| 1066    | 399       | 1.57%   |
| 1867    | 329       | 1.29%   |
| 333     | 294       | 1.15%   |
| 2048    | 235       | 0.92%   |
| 3200    | 195       | 0.77%   |
| 1866    | 158       | 0.62%   |
| 975     | 118       | 0.46%   |
| 266     | 105       | 0.41%   |
| 1800    | 97        | 0.38%   |
| 1639    | 73        | 0.29%   |
| 2933    | 60        | 0.24%   |
| 3266    | 49        | 0.19%   |
| 66      | 49        | 0.19%   |
| 2666    | 44        | 0.17%   |
| 3466    | 40        | 0.16%   |
| 2000    | 40        | 0.16%   |
| 3600    | 39        | 0.15%   |
| 2134    | 38        | 0.15%   |
| 3000    | 37        | 0.15%   |
| 1400    | 36        | 0.14%   |
| 200     | 31        | 0.12%   |
| 3400    | 30        | 0.12%   |
| 2800    | 26        | 0.1%    |
| 49926   | 24        | 0.09%   |
| 3066    | 15        | 0.06%   |
| 3533    | 14        | 0.05%   |
| 1648    | 14        | 0.05%   |
| 133     | 12        | 0.05%   |
| 65535   | 11        | 0.04%   |
| 2200    | 11        | 0.04%   |
| 3334    | 10        | 0.04%   |
| 2733    | 10        | 0.04%   |
| 2187    | 10        | 0.04%   |
| 2866    | 9         | 0.04%   |
| 50410   | 7         | 0.03%   |
| 5354    | 7         | 0.03%   |
| 3500    | 7         | 0.03%   |
| 3333    | 7         | 0.03%   |
| 3151    | 7         | 0.03%   |
| 3007    | 5         | 0.02%   |
| 2934    | 5         | 0.02%   |
| 2747    | 5         | 0.02%   |
| 1776    | 5         | 0.02%   |
| 933     | 5         | 0.02%   |
| 100     | 5         | 0.02%   |
| 3733    | 4         | 0.02%   |
| 2176    | 4         | 0.02%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 487       | 30.9%   |
| Canon                           | 365       | 23.16%  |
| Samsung Electronics             | 268       | 17.01%  |
| Seiko Epson                     | 159       | 10.09%  |
| Brother Industries              | 103       | 6.54%   |
| Xerox                           | 45        | 2.86%   |
| Panasonic (Matsushita)          | 37        | 2.35%   |
| Kyocera                         | 23        | 1.46%   |
| Ricoh                           | 20        | 1.27%   |
| Pantum                          | 18        | 1.14%   |
| Prolific Technology             | 12        | 0.76%   |
| QinHeng Electronics             | 8         | 0.51%   |
| Lexmark International           | 8         | 0.51%   |
| TSC Auto ID Technology          | 4         | 0.25%   |
| WinChipHead                     | 3         | 0.19%   |
| Sharp                           | 2         | 0.13%   |
| cab Produkttechnik GmbH & Co KG | 2         | 0.13%   |
| Yurex                           | 1         | 0.06%   |
| Toshiba TEC                     | 1         | 0.06%   |
| STMicroelectronics              | 1         | 0.06%   |
| Samsung Info. Systems America   | 1         | 0.06%   |
| NXP Semiconductors              | 1         | 0.06%   |
| Konica Minolta                  | 1         | 0.06%   |
| Kodak                           | 1         | 0.06%   |
| Fuji Xerox                      | 1         | 0.06%   |
| Dell                            | 1         | 0.06%   |
| Custom Engineering SPA          | 1         | 0.06%   |
| ATEN International              | 1         | 0.06%   |
| Apple                           | 1         | 0.06%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| HP LaserJet 1020                                             | 58        | 3.6%    |
| HP LaserJet 1018                                             | 43        | 2.67%   |
| Samsung SCX-4200 series                                      | 42        | 2.61%   |
| HP LaserJet P1102                                            | 41        | 2.55%   |
| Canon LBP2900                                                | 36        | 2.24%   |
| Seiko Epson Printer                                          | 34        | 2.11%   |
| Seiko Epson USB2.0 Printer (Hi-speed)                        | 24        | 1.49%   |
| Samsung SCX-3400 Series                                      | 24        | 1.49%   |
| Panasonic (Matsushita) KX-MB1500CX                           | 24        | 1.49%   |
| HP LaserJet 1010                                             | 24        | 1.49%   |
| Samsung SCX-3200 Series                                      | 22        | 1.37%   |
| Canon MF4410                                                 | 22        | 1.37%   |
| Canon MF3010                                                 | 22        | 1.37%   |
| HP LaserJet P1005                                            | 18        | 1.12%   |
| Seiko Epson L210 Series                                      | 17        | 1.06%   |
| Samsung ML-1640 Series Laser Printer                         | 17        | 1.06%   |
| Canon LBP3010/LBP3018/LBP3050                                | 15        | 0.93%   |
| Samsung ML-1210 Printer                                      | 14        | 0.87%   |
| Canon MF4010 series                                          | 14        | 0.87%   |
| Canon LaserShot LBP-1120 Printer                             | 14        | 0.87%   |
| HP Deskjet 2050 J510                                         | 13        | 0.81%   |
| Canon LBP810                                                 | 13        | 0.81%   |
| Canon LBP6000                                                | 13        | 0.81%   |
| Canon iP7200 series                                          | 13        | 0.81%   |
| Brother HL-2030 Laser Printer                                | 13        | 0.81%   |
| Prolific PL2305 Parallel Port                                | 12        | 0.75%   |
| HP LaserJet 1200                                             | 12        | 0.75%   |
| Canon MG2400 series                                          | 12        | 0.75%   |
| Samsung ML-2010P Mono Laser Printer                          | 11        | 0.68%   |
| Samsung M2070 Series                                         | 11        | 0.68%   |
| HP LaserJet 1000                                             | 11        | 0.68%   |
| HP DeskJet 2130 series                                       | 11        | 0.68%   |
| Canon PIXMA MG2500 Series                                    | 11        | 0.68%   |
| Canon LBP6020                                                | 11        | 0.68%   |
| Brother HL-1110 series                                       | 11        | 0.68%   |
| Xerox Phaser 3140 and 3155                                   | 10        | 0.62%   |
| Samsung SCX-4100 Scanner                                     | 10        | 0.62%   |
| Samsung M2020 Series                                         | 10        | 0.62%   |
| Panasonic (Matsushita) KX-MB2030 Multifunction Laser Printer | 10        | 0.62%   |
| HP LaserJet 1320                                             | 10        | 0.62%   |
| HP LaserJet 1022                                             | 10        | 0.62%   |
| Canon PIXMA MP250                                            | 10        | 0.62%   |
| Seiko Epson ME 340 Series/Stylus NX130 Series                | 9         | 0.56%   |
| Seiko Epson L110 Series                                      | 9         | 0.56%   |
| HP LaserJet P1006                                            | 9         | 0.56%   |
| Canon MF3200 series                                          | 9         | 0.56%   |
| Brother DCP-7057 scanner/printer                             | 9         | 0.56%   |
| Xerox Phaser 3010                                            | 8         | 0.5%    |
| Samsung SCX-4300 Series                                      | 8         | 0.5%    |
| Samsung ML-1865                                              | 8         | 0.5%    |
| QinHeng CH340S                                               | 8         | 0.5%    |
| Canon PIXMA MP280                                            | 8         | 0.5%    |
| Canon PIXMA MP230                                            | 8         | 0.5%    |
| Canon LBP7010C/7018C                                         | 8         | 0.5%    |
| Canon iP2700 series                                          | 8         | 0.5%    |
| Brother Printer                                              | 8         | 0.5%    |
| Xerox WorkCentre 3119 Series                                 | 7         | 0.44%   |
| Pantum M6500 series                                          | 7         | 0.44%   |
| HP LaserJet 1300                                             | 7         | 0.44%   |
| HP DeskJet F4200 series                                      | 7         | 0.44%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Canon                       | 168       | 36.29%  |
| Seiko Epson                 | 109       | 23.54%  |
| Hewlett-Packard             | 80        | 17.28%  |
| Mustek Systems              | 49        | 10.58%  |
| Ultima Electronics          | 18        | 3.89%   |
| Acer Peripherals (now BenQ) | 18        | 3.89%   |
| KYE Systems (Mouse Systems) | 7         | 1.51%   |
| Fujitsu                     | 4         | 0.86%   |
| Microtek International      | 2         | 0.43%   |
| Avision                     | 2         | 0.43%   |
| AGFA-Gevaert NV             | 2         | 0.43%   |
| Visioneer                   | 1         | 0.22%   |
| Plustek                     | 1         | 0.22%   |
| Papillon Systems            | 1         | 0.22%   |
| Canon Electronics           | 1         | 0.22%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                                                                | 31        | 6.68%   |
| Canon CanoScan LiDE 110                                                               | 26        | 5.6%    |
| HP ScanJet 2400c                                                                      | 25        | 5.39%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 20        | 4.31%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 17        | 3.66%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 17        | 3.66%   |
| Canon CanoScan LiDE 120                                                               | 17        | 3.66%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 16        | 3.45%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 14        | 3.02%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 13        | 2.8%    |
| Canon CanoScan LiDE 60                                                                | 11        | 2.37%   |
| Canon CanoScan LiDE 210                                                               | 11        | 2.37%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 10        | 2.16%   |
| Canon CanoScan LiDE 220                                                               | 9         | 1.94%   |
| Canon CanoScan LiDE 100                                                               | 9         | 1.94%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 8         | 1.72%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 8         | 1.72%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 7         | 1.51%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 7         | 1.51%   |
| Mustek Systems SNAPSCAN e22                                                           | 6         | 1.29%   |
| Canon CanoScan                                                                        | 6         | 1.29%   |
| Seiko Epson Perfection 660                                                            | 5         | 1.08%   |
| Mustek Systems BearPaw 2448 TA Plus                                                   | 5         | 1.08%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]                                     | 4         | 0.86%   |
| Mustek Systems BearPaw 2448 CU Pro                                                    | 4         | 0.86%   |
| HP ScanJet 3800c                                                                      | 4         | 0.86%   |
| HP Scanjet 200                                                                        | 4         | 0.86%   |
| Canon CanoScan LiDE 70                                                                | 4         | 0.86%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 4         | 0.86%   |
| Acer Peripherals (now BenQ) Benq 5560                                                 | 4         | 0.86%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 3         | 0.65%   |
| Mustek Systems BearPaw 2400 TA Plus                                                   | 3         | 0.65%   |
| HP ScanJet G3010                                                                      | 3         | 0.65%   |
| HP ScanJet 3970c                                                                      | 3         | 0.65%   |
| HP ScanJet 3770                                                                       | 3         | 0.65%   |
| HP ScanJet 3500c                                                                      | 3         | 0.65%   |
| HP PSC 1200                                                                           | 3         | 0.65%   |
| Fujitsu ScanSnap SV600                                                                | 3         | 0.65%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 3         | 0.65%   |
| Canon CanoScan LiDE 90                                                                | 3         | 0.65%   |
| Canon CanoScan LiDE 600F                                                              | 3         | 0.65%   |
| Canon CanoScan 4400F                                                                  | 3         | 0.65%   |
| Acer Peripherals (now BenQ) S2W 3300U/4300U                                           | 3         | 0.65%   |
| Acer Peripherals (now BenQ) Benq 5150/5250                                            | 3         | 0.65%   |
| Acer Peripherals (now BenQ) Benq 5000                                                 | 3         | 0.65%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 2         | 0.43%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 2         | 0.43%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 2         | 0.43%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 2         | 0.43%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 0.43%   |
| Mustek Systems BearPaw 1200 TA/CS                                                     | 2         | 0.43%   |
| Microtek International USB1200 Scanner                                                | 2         | 0.43%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid4                                          | 2         | 0.43%   |
| KYE Systems (Mouse Systems) ColorPage-Vivid 1200 XE                                   | 2         | 0.43%   |
| HP ScanJet G4050                                                                      | 2         | 0.43%   |
| HP ScanJet G4010                                                                      | 2         | 0.43%   |
| HP ScanJet G3110                                                                      | 2         | 0.43%   |
| HP ScanJet 6300c                                                                      | 2         | 0.43%   |
| HP ScanJet 5590                                                                       | 2         | 0.43%   |
| HP ScanJet 4300c                                                                      | 2         | 0.43%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 2788      | 21.59%  |
| Logitech                               | 1022      | 7.92%   |
| Acer                                   | 933       | 7.23%   |
| Suyin                                  | 900       | 6.97%   |
| Z-Star Microelectronics                | 818       | 6.34%   |
| IMC Networks                           | 792       | 6.13%   |
| Microdia                               | 768       | 5.95%   |
| Realtek Semiconductor                  | 696       | 5.39%   |
| Silicon Motion                         | 573       | 4.44%   |
| Sunplus Innovation Technology          | 536       | 4.15%   |
| Alcor Micro                            | 355       | 2.75%   |
| Cheng Uei Precision Industry (Foxlink) | 311       | 2.41%   |
| Syntek                                 | 296       | 2.29%   |
| ALi                                    | 157       | 1.22%   |
| Microsoft                              | 153       | 1.18%   |
| Ricoh                                  | 146       | 1.13%   |
| Quanta                                 | 134       | 1.04%   |
| Apple                                  | 126       | 0.98%   |
| KYE Systems (Mouse Systems)            | 124       | 0.96%   |
| DigiTech                               | 120       | 0.93%   |
| Pixart Imaging                         | 104       | 0.81%   |
| Arkmicro Technologies                  | 100       | 0.77%   |
| Cubeternet                             | 99        | 0.77%   |
| Aveo Technology                        | 94        | 0.73%   |
| GEMBIRD                                | 84        | 0.65%   |
| Samsung Electronics                    | 77        | 0.6%    |
| Lenovo                                 | 65        | 0.5%    |
| Lite-On Technology                     | 55        | 0.43%   |
| Importek                               | 54        | 0.42%   |
| Primax Electronics                     | 46        | 0.36%   |
| Creative Technology                    | 38        | 0.29%   |
| Genesys Logic                          | 32        | 0.25%   |
| OmniVision Technologies                | 25        | 0.19%   |
| Sunplus Technology                     | 23        | 0.18%   |
| Nokia Mobile Phones                    | 21        | 0.16%   |
| Guillemot                              | 21        | 0.16%   |
| Philips (or NXP)                       | 17        | 0.13%   |
| Image Processor                        | 16        | 0.12%   |
| Hewlett-Packard                        | 14        | 0.11%   |
| SiGma Micro                            | 11        | 0.09%   |
| Luxvisions Innotech Limited            | 10        | 0.08%   |
| Generalplus Technology                 | 10        | 0.08%   |
| Sonix Technology                       | 8         | 0.06%   |
| Foxconn / Hon Hai                      | 8         | 0.06%   |
| Canon                                  | 8         | 0.06%   |
| Trust                                  | 6         | 0.05%   |
| O2 Micro                               | 6         | 0.05%   |
| HTC (High Tech Computer)               | 6         | 0.05%   |
| Fitipower Integrated Technology        | 6         | 0.05%   |
| Unknown                                | 5         | 0.04%   |
| A4Tech                                 | 5         | 0.04%   |
| Nikon                                  | 4         | 0.03%   |
| lihappe8                               | 4         | 0.03%   |
| LG Electronics                         | 4         | 0.03%   |
| Sweex                                  | 3         | 0.02%   |
| Sony                                   | 3         | 0.02%   |
| Panasonic (Matsushita)                 | 3         | 0.02%   |
| Novatek Microelectronics               | 3         | 0.02%   |
| MacroSilicon                           | 3         | 0.02%   |
| Google                                 | 3         | 0.02%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Logitech Webcam C270                                        | 336       | 2.6%    |
| Chicony HD WebCam                                           | 284       | 2.2%    |
| Z-Star Venus USB2.0 Camera                                  | 277       | 2.14%   |
| Chicony Lenovo EasyCamera                                   | 267       | 2.07%   |
| Acer Lenovo EasyCamera                                      | 240       | 1.86%   |
| Acer Lenovo Integrated Webcam                               | 200       | 1.55%   |
| IMC Networks UVC VGA Webcam                                 | 197       | 1.52%   |
| Sunplus HD WebCam                                           | 186       | 1.44%   |
| Chicony USB 2.0 Camera                                      | 183       | 1.42%   |
| Z-Star A4 TECH USB2.0 PC Camera J                           | 160       | 1.24%   |
| Acer BisonCam, NB Pro                                       | 150       | 1.16%   |
| Chicony USB2.0 HD UVC WebCam                                | 149       | 1.15%   |
| Microdia Camera                                             | 143       | 1.11%   |
| Microdia Sonix USB 2.0 Camera                               | 117       | 0.91%   |
| Realtek Lenovo EasyCamera                                   | 115       | 0.89%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                    | 114       | 0.88%   |
| Z-Star Vimicro USB Camera (Altair)                          | 112       | 0.87%   |
| Silicon Motion WebCam SC-0311139N                           | 111       | 0.86%   |
| Chicony 2.0M UVC Webcam / CNF7129                           | 111       | 0.86%   |
| Syntek Lenovo EasyCamera                                    | 108       | 0.84%   |
| IMC Networks Integrated Webcam                              | 108       | 0.84%   |
| ALi Gateway Webcam                                          | 106       | 0.82%   |
| Chicony Integrated Camera                                   | 105       | 0.81%   |
| Alcor Micro Asus Integrated Webcam                          | 104       | 0.8%    |
| DigiTech USB 2.0 PC Camera                                  | 99        | 0.77%   |
| Suyin 1.3M HD WebCam                                        | 94        | 0.73%   |
| Realtek USB Camera                                          | 94        | 0.73%   |
| Sunplus Asus Webcam                                         | 90        | 0.7%    |
| Arkmicro USB2.0 PC CAMERA                                   | 90        | 0.7%    |
| Chicony HP TrueVision HD                                    | 87        | 0.67%   |
| Logitech Webcam C170                                        | 86        | 0.67%   |
| Chicony USB2.0 VGA UVC WebCam                               | 86        | 0.67%   |
| Chicony USB2.0 0.3M UVC WebCam                              | 83        | 0.64%   |
| Logitech Webcam C310                                        | 82        | 0.63%   |
| Logitech Webcam C210                                        | 81        | 0.63%   |
| Chicony 1.3M Webcam                                         | 80        | 0.62%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                        | 77        | 0.6%    |
| Chicony HP Webcam                                           | 77        | 0.6%    |
| Suyin Acer CrystalEye Webcam                                | 76        | 0.59%   |
| IMC Networks USB2.0 UVC HD Webcam                           | 76        | 0.59%   |
| IMC Networks USB 2.0 UVC VGA WebCam                         | 76        | 0.59%   |
| Chicony WebCam                                              | 74        | 0.57%   |
| Samsung Galaxy A5 (MTP)                                     | 73        | 0.56%   |
| Silicon Motion WebCam SCB-1100N                             | 71        | 0.55%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand) | 70        | 0.54%   |
| Silicon Motion WebCam SCB-0355N                             | 70        | 0.54%   |
| Chicony VGA Webcam                                          | 69        | 0.53%   |
| Suyin HP TrueVision HD                                      | 68        | 0.53%   |
| IMC Networks USB2.0 VGA UVC WebCam                          | 68        | 0.53%   |
| Logitech HD Webcam C525                                     | 66        | 0.51%   |
| Chicony CNF9055 Toshiba Webcam                              | 66        | 0.51%   |
| Microdia USB 2.0 Camera                                     | 63        | 0.49%   |
| Microdia Laptop_Integrated_Webcam_HD                        | 63        | 0.49%   |
| Suyin HD WebCam                                             | 62        | 0.48%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam-101        | 62        | 0.48%   |
| Silicon Motion WebCam SC-03FFL11939N                        | 61        | 0.47%   |
| Z-Star Webcam                                               | 59        | 0.46%   |
| Microdia Lenovo EasyCamera                                  | 56        | 0.43%   |
| Cheng Uei Precision Industry (Foxlink) Webcam               | 56        | 0.43%   |
| Realtek USB2.0 HD UVC WebCam                                | 53        | 0.41%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 411       | 43.58%  |
| AuthenTec                  | 221       | 23.44%  |
| Upek                       | 152       | 16.12%  |
| STMicroelectronics         | 74        | 7.85%   |
| LighTuning Technology      | 60        | 6.36%   |
| Elan Microelectronics      | 10        | 1.06%   |
| Synaptics                  | 7         | 0.74%   |
| Shenzhen Goodix Technology | 4         | 0.42%   |
| Microsoft                  | 2         | 0.21%   |
| Focal-systems.Corp         | 1         | 0.11%   |
| DigitalPersona             | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 138       | 14.63%  |
| Validity Sensors Fingerprint scanner                                       | 108       | 11.45%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 81        | 8.59%   |
| STMicroelectronics Fingerprint Reader                                      | 74        | 7.85%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 73        | 7.74%   |
| AuthenTec AES1600                                                          | 62        | 6.57%   |
| AuthenTec AES2810                                                          | 53        | 5.62%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 44        | 4.67%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 39        | 4.14%   |
| LighTuning Fingerprint Reader                                              | 39        | 4.14%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 30        | 3.18%   |
| Validity Sensors VFS491                                                    | 26        | 2.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 25        | 2.65%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 24        | 2.55%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 18        | 1.91%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 17        | 1.8%    |
| Upek TCS5B Fingerprint sensor                                              | 14        | 1.48%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 1.27%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 0.85%   |
| Elan ELAN:Fingerprint                                                      | 8         | 0.85%   |
| AuthenTec Fingerprint Sensor                                               | 7         | 0.74%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 7         | 0.74%   |
| Validity Sensors VFS Fingerprint sensor                                    | 5         | 0.53%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 0.42%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 0.42%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 0.42%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 3         | 0.32%   |
| Synaptics  WBDI                                                            | 2         | 0.21%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 0.21%   |
| Microsoft Fingerprint Reader                                               | 2         | 0.21%   |
| Unknown                                                                    | 2         | 0.21%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.11%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.11%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.11%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.11%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.11%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.11%   |
| DigitalPersona Fingerprint Scanner, U.are.U 2000                           | 1         | 0.11%   |
| AuthenTec AES2501                                                          | 1         | 0.11%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Broadcom                                | 97        | 32.77%  |
| O2 Micro                                | 52        | 17.57%  |
| Alcor Micro                             | 32        | 10.81%  |
| Lenovo                                  | 27        | 9.12%   |
| Upek                                    | 25        | 8.45%   |
| Aladdin Knowledge Systems               | 14        | 4.73%   |
| Advanced Card Systems                   | 11        | 3.72%   |
| OmniKey                                 | 8         | 2.7%    |
| Aktiv                                   | 6         | 2.03%   |
| Realtek Semiconductor                   | 5         | 1.69%   |
| Gemalto (was Gemplus)                   | 5         | 1.69%   |
| Athena Smartcard Solutions              | 4         | 1.35%   |
| Castles Technology                      | 2         | 0.68%   |
| ARDS                                    | 2         | 0.68%   |
| Reiner SCT Kartensysteme                | 1         | 0.34%   |
| In Focus Systems                        | 1         | 0.34%   |
| Future Technology Devices International | 1         | 0.34%   |
| Cherry                                  | 1         | 0.34%   |
| BIFIT                                   | 1         | 0.34%   |
| Avtor                                   | 1         | 0.34%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 64        | 21.62%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 36        | 12.16%  |
| Lenovo Integrated Smart Card Reader                                          | 27        | 9.12%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 25        | 8.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 25        | 8.45%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 8.11%   |
| O2 Micro Oz776 SmartCard Reader                                              | 16        | 5.41%   |
| Aladdin Knowledge Systems Token JC                                           | 14        | 4.73%   |
| Alcor Micro Watchdata W 1981                                                 | 8         | 2.7%    |
| OmniKey CardMan 1021                                                         | 6         | 2.03%   |
| Broadcom 5880                                                                | 6         | 2.03%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 5         | 1.69%   |
| Aktiv Rutoken lite                                                           | 5         | 1.69%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 4         | 1.35%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 1.35%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 1.01%   |
| Advanced Card Systems Token USB 64K                                          | 3         | 1.01%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 0.68%   |
| Castles Technology EZCCID Smart Card Reader                                  | 2         | 0.68%   |
| Broadcom 58200                                                               | 2         | 0.68%   |
| ARDS JaCarta                                                                 | 2         | 0.68%   |
| Advanced Card Systems ACR3901U                                               | 2         | 0.68%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.34%   |
| OmniKey CardMan 4321                                                         | 1         | 0.34%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.34%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.34%   |
| Future Technology Devices International Parsec Desktop Reader PR-EH08        | 1         | 0.34%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.34%   |
| BIFIT iBank2Key                                                              | 1         | 0.34%   |
| Avtor SecureToken                                                            | 1         | 0.34%   |
| Aktiv KAZTOKEN                                                               | 1         | 0.34%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.34%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.34%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 19613     | 78.63%  |
| 1     | 4444      | 17.82%  |
| 2     | 765       | 3.07%   |
| 3     | 95        | 0.38%   |
| 4     | 21        | 0.08%   |
| 5     | 2         | 0.01%   |
| 9     | 1         | 0.004%  |
| 7     | 1         | 0.004%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 2785      | 47.64%  |
| Fingerprint reader       | 941       | 16.1%   |
| Net/wireless             | 488       | 8.35%   |
| Bluetooth                | 346       | 5.92%   |
| Chipcard                 | 283       | 4.84%   |
| Communication controller | 226       | 3.87%   |
| Multimedia controller    | 225       | 3.85%   |
| Camera                   | 134       | 2.29%   |
| Storage                  | 118       | 2.02%   |
| Flash memory             | 95        | 1.63%   |
| Unassigned class         | 43        | 0.74%   |
| Sound                    | 34        | 0.58%   |
| Modem                    | 30        | 0.51%   |
| Card reader              | 26        | 0.44%   |
| Dvb card                 | 25        | 0.43%   |
| Net/ethernet             | 14        | 0.24%   |
| Network                  | 13        | 0.22%   |
| Tv card                  | 6         | 0.1%    |
| Video                    | 5         | 0.09%   |
| Storage/raid             | 4         | 0.07%   |
| Storage/ata              | 4         | 0.07%   |
| Wireless                 | 1         | 0.02%   |

