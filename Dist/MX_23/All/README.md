MX 23 - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for MX 23.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/MX_23/Desktop/README.md) and [notebooks](/Dist/MX_23/Notebook/README.md).

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

Total: 308

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [413b207df0](https://linux-hardware.org/?probe=413b207df0) | May 09, 2024 |
| Dell          | Latitude 3190               | Notebook    | [102011a182](https://linux-hardware.org/?probe=102011a182) | May 07, 2024 |
| Toshiba       | Satellite C50-B             | Notebook    | [4037de5266](https://linux-hardware.org/?probe=4037de5266) | May 06, 2024 |
| Lenovo        | Yoga Slim 7-14ARE05 82A2    | Notebook    | [c931a1a446](https://linux-hardware.org/?probe=c931a1a446) | May 05, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b9519853cd](https://linux-hardware.org/?probe=b9519853cd) | May 05, 2024 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [08cb15cda7](https://linux-hardware.org/?probe=08cb15cda7) | May 05, 2024 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [41e3014295](https://linux-hardware.org/?probe=41e3014295) | May 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [cbd3101c16](https://linux-hardware.org/?probe=cbd3101c16) | May 01, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | Notebook    | [6aca55ce35](https://linux-hardware.org/?probe=6aca55ce35) | May 01, 2024 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [bac49afb7f](https://linux-hardware.org/?probe=bac49afb7f) | Apr 30, 2024 |
| ASUSTek       | M4A89GTD-PRO                | Desktop     | [d40738eda7](https://linux-hardware.org/?probe=d40738eda7) | Apr 28, 2024 |
| ASRock        | 980DE3/U3S3                 | Desktop     | [9ed5c55a61](https://linux-hardware.org/?probe=9ed5c55a61) | Apr 28, 2024 |
| Intel         | AB2L .A001                  | Mini pc     | [c83deebaf0](https://linux-hardware.org/?probe=c83deebaf0) | Apr 28, 2024 |
| Apple         | MacBookPro5,5               | Notebook    | [d1fbf194df](https://linux-hardware.org/?probe=d1fbf194df) | Apr 25, 2024 |
| Dell          | XPS 13 9305                 | Notebook    | [62621a436b](https://linux-hardware.org/?probe=62621a436b) | Apr 25, 2024 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [c44f97261d](https://linux-hardware.org/?probe=c44f97261d) | Apr 24, 2024 |
| Dell          | 0K095G A02                  | Desktop     | [a5f4dd8567](https://linux-hardware.org/?probe=a5f4dd8567) | Apr 24, 2024 |
| Dell          | 0K095G A02                  | Desktop     | [0d7d9ad04d](https://linux-hardware.org/?probe=0d7d9ad04d) | Apr 24, 2024 |
| Lenovo        | G505s 20255                 | Notebook    | [b7d2ec7d4d](https://linux-hardware.org/?probe=b7d2ec7d4d) | Apr 24, 2024 |
| Acer          | Aspire A515-47              | Notebook    | [dc0e4e49bb](https://linux-hardware.org/?probe=dc0e4e49bb) | Apr 24, 2024 |
| Acer          | Aspire A515-47              | Notebook    | [feba2802f3](https://linux-hardware.org/?probe=feba2802f3) | Apr 22, 2024 |
| Samsung       | N150/N210/N220              | Notebook    | [73f5edc5e5](https://linux-hardware.org/?probe=73f5edc5e5) | Apr 22, 2024 |
| AMI           | Intel                       | Desktop     | [212fd4a0d8](https://linux-hardware.org/?probe=212fd4a0d8) | Apr 22, 2024 |
| AMI           | Intel                       | Desktop     | [2044003b5c](https://linux-hardware.org/?probe=2044003b5c) | Apr 22, 2024 |
| SGIN          | M15                         | Notebook    | [68c2d94db7](https://linux-hardware.org/?probe=68c2d94db7) | Apr 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [9e43e9df38](https://linux-hardware.org/?probe=9e43e9df38) | Apr 19, 2024 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [b3e2fd82b1](https://linux-hardware.org/?probe=b3e2fd82b1) | Apr 18, 2024 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [980252a20c](https://linux-hardware.org/?probe=980252a20c) | Apr 18, 2024 |
| GPU Compan... | GWTN116-3                   | Notebook    | [30fba12411](https://linux-hardware.org/?probe=30fba12411) | Apr 18, 2024 |
| GPU Compan... | GWTN116-3                   | Notebook    | [a11ace542b](https://linux-hardware.org/?probe=a11ace542b) | Apr 18, 2024 |
| Toshiba       | Satellite C55D-B            | Notebook    | [0d2ecb9207](https://linux-hardware.org/?probe=0d2ecb9207) | Apr 17, 2024 |
| Acer          | Aspire E1-572               | Notebook    | [a91f9fc37a](https://linux-hardware.org/?probe=a91f9fc37a) | Apr 15, 2024 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [70446389fb](https://linux-hardware.org/?probe=70446389fb) | Apr 13, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [e717cc9856](https://linux-hardware.org/?probe=e717cc9856) | Apr 13, 2024 |
| Google        | Cyan                        | Notebook    | [46c86ddfe0](https://linux-hardware.org/?probe=46c86ddfe0) | Apr 12, 2024 |
| Google        | Cyan                        | Notebook    | [e2c458d3a7](https://linux-hardware.org/?probe=e2c458d3a7) | Apr 11, 2024 |
| Acer          | AO756                       | Notebook    | [79847ca0b1](https://linux-hardware.org/?probe=79847ca0b1) | Apr 11, 2024 |
| Dell          | Latitude 3190               | Notebook    | [4f2b2351b3](https://linux-hardware.org/?probe=4f2b2351b3) | Apr 09, 2024 |
| HP            | Notebook                    | Notebook    | [414230182b](https://linux-hardware.org/?probe=414230182b) | Apr 06, 2024 |
| ASUSTek       | Z170-A                      | Desktop     | [30127a97b5](https://linux-hardware.org/?probe=30127a97b5) | Apr 06, 2024 |
| Google        | Magolor                     | Notebook    | [36145fc673](https://linux-hardware.org/?probe=36145fc673) | Apr 06, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | Notebook    | [0852701d67](https://linux-hardware.org/?probe=0852701d67) | Apr 05, 2024 |
| ASRock        | H77 Pro4-M                  | Desktop     | [4202019d78](https://linux-hardware.org/?probe=4202019d78) | Apr 03, 2024 |
| Dell          | Latitude 3190               | Notebook    | [c15e7df670](https://linux-hardware.org/?probe=c15e7df670) | Apr 02, 2024 |
| Dell          | Inspiron 3185               | Notebook    | [80090c69a3](https://linux-hardware.org/?probe=80090c69a3) | Mar 31, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [115bac67be](https://linux-hardware.org/?probe=115bac67be) | Mar 30, 2024 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [7f8a245399](https://linux-hardware.org/?probe=7f8a245399) | Mar 29, 2024 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [7b17376565](https://linux-hardware.org/?probe=7b17376565) | Mar 29, 2024 |
| Fujitsu       | LIFEBOOK T938               | Convertible | [791a897f07](https://linux-hardware.org/?probe=791a897f07) | Mar 28, 2024 |
| Gigabyte      | H81M-D2V                    | Desktop     | [6bc3e596e6](https://linux-hardware.org/?probe=6bc3e596e6) | Mar 28, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e8233f1a8a](https://linux-hardware.org/?probe=e8233f1a8a) | Mar 26, 2024 |
| Lenovo        | ThinkPad X280 20KES6M100    | Notebook    | [07c23b72ec](https://linux-hardware.org/?probe=07c23b72ec) | Mar 25, 2024 |
| HP            | 250 G1                      | Notebook    | [1061b55594](https://linux-hardware.org/?probe=1061b55594) | Mar 25, 2024 |
| Dell          | 0HMX8D A01                  | Desktop     | [8cd1470fc0](https://linux-hardware.org/?probe=8cd1470fc0) | Mar 25, 2024 |
| Apple         | MacBookPro7,1               | Notebook    | [bbfdefb7ef](https://linux-hardware.org/?probe=bbfdefb7ef) | Mar 25, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [2eb785461f](https://linux-hardware.org/?probe=2eb785461f) | Mar 23, 2024 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8099dc4885](https://linux-hardware.org/?probe=8099dc4885) | Mar 22, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | Notebook    | [cc230156f7](https://linux-hardware.org/?probe=cc230156f7) | Mar 19, 2024 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | Notebook    | [16070af93d](https://linux-hardware.org/?probe=16070af93d) | Mar 17, 2024 |
| Toshiba       | dynabook T552/36GB          | Notebook    | [9da00148f4](https://linux-hardware.org/?probe=9da00148f4) | Mar 14, 2024 |
| Medion        | Defender P30                | Notebook    | [34a9a3fde8](https://linux-hardware.org/?probe=34a9a3fde8) | Mar 13, 2024 |
| Medion        | Defender P30                | Notebook    | [459ac8cc46](https://linux-hardware.org/?probe=459ac8cc46) | Mar 13, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [91114bc213](https://linux-hardware.org/?probe=91114bc213) | Mar 13, 2024 |
| Apple         | Mac-F2268CC8                | All in one  | [fccb125880](https://linux-hardware.org/?probe=fccb125880) | Mar 12, 2024 |
| AMI           | Aptio CRB                   | Mini pc     | [771c9373e9](https://linux-hardware.org/?probe=771c9373e9) | Mar 11, 2024 |
| AZW           | SER V1.0                    | Mini pc     | [df839d09a2](https://linux-hardware.org/?probe=df839d09a2) | Mar 11, 2024 |
| Foxconn       | 45GM/45CM/45CM-S            | Desktop     | [4ed069d496](https://linux-hardware.org/?probe=4ed069d496) | Mar 09, 2024 |
| HP            | 2B5A 011                    | Desktop     | [8eb2546f52](https://linux-hardware.org/?probe=8eb2546f52) | Mar 09, 2024 |
| Toshiba       | Satellite P875              | Notebook    | [e1b998e44b](https://linux-hardware.org/?probe=e1b998e44b) | Mar 09, 2024 |
| Lenovo        | G50-30 80G0                 | Notebook    | [be5e190ea5](https://linux-hardware.org/?probe=be5e190ea5) | Mar 08, 2024 |
| ASUSTek       | T100TA                      | Notebook    | [d723bb2900](https://linux-hardware.org/?probe=d723bb2900) | Mar 07, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [e61abe174c](https://linux-hardware.org/?probe=e61abe174c) | Mar 04, 2024 |
| Google        | Magolor                     | Notebook    | [bf456da608](https://linux-hardware.org/?probe=bf456da608) | Mar 04, 2024 |
| HP            | Pavilion g6                 | Notebook    | [fd797ba3af](https://linux-hardware.org/?probe=fd797ba3af) | Mar 04, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [e4944abc1f](https://linux-hardware.org/?probe=e4944abc1f) | Mar 03, 2024 |
| Alienware     | 18                          | Notebook    | [b7402f0c82](https://linux-hardware.org/?probe=b7402f0c82) | Mar 03, 2024 |
| HP            | Pavilion g6                 | Notebook    | [7e4412a097](https://linux-hardware.org/?probe=7e4412a097) | Mar 03, 2024 |
| HP            | Pavilion dv6                | Notebook    | [14e50b9c6c](https://linux-hardware.org/?probe=14e50b9c6c) | Mar 01, 2024 |
| PC Special... | Lafite Pro III 17           | Notebook    | [41f1e90fb9](https://linux-hardware.org/?probe=41f1e90fb9) | Feb 29, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [c6209a30c6](https://linux-hardware.org/?probe=c6209a30c6) | Feb 28, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [3d502260aa](https://linux-hardware.org/?probe=3d502260aa) | Feb 28, 2024 |
| Dell          | 0M863N A01                  | Desktop     | [1db77a3f14](https://linux-hardware.org/?probe=1db77a3f14) | Feb 27, 2024 |
| Toshiba       | IS 1413G                    | Notebook    | [0f39b4b446](https://linux-hardware.org/?probe=0f39b4b446) | Feb 27, 2024 |
| Toshiba       | Satellite C55-A             | Notebook    | [9d0cd280a9](https://linux-hardware.org/?probe=9d0cd280a9) | Feb 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [527feb458b](https://linux-hardware.org/?probe=527feb458b) | Feb 26, 2024 |
| Gigabyte      | H310M S2H x.x               | Desktop     | [ce358b38bc](https://linux-hardware.org/?probe=ce358b38bc) | Feb 26, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [f31eac8a5d](https://linux-hardware.org/?probe=f31eac8a5d) | Feb 24, 2024 |
| Apple         | MacBookPro5,2               | Notebook    | [f34e05e096](https://linux-hardware.org/?probe=f34e05e096) | Feb 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [bb563ea8ac](https://linux-hardware.org/?probe=bb563ea8ac) | Feb 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2c9ffa4b20](https://linux-hardware.org/?probe=2c9ffa4b20) | Feb 23, 2024 |
| Toshiba       | IS 1413G                    | Notebook    | [c88a0acd8e](https://linux-hardware.org/?probe=c88a0acd8e) | Feb 22, 2024 |
| Dell          | Vostro 1014                 | Notebook    | [5fcabcc564](https://linux-hardware.org/?probe=5fcabcc564) | Feb 22, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [9b25d17d18](https://linux-hardware.org/?probe=9b25d17d18) | Feb 21, 2024 |
| Dell          | Latitude 3190               | Notebook    | [1396b535bf](https://linux-hardware.org/?probe=1396b535bf) | Feb 20, 2024 |
| I-life        | ZEDNOTE                     | Notebook    | [172d63ec33](https://linux-hardware.org/?probe=172d63ec33) | Feb 19, 2024 |
| Gigabyte      | X570 GAMING X               | Desktop     | [fab0b459e0](https://linux-hardware.org/?probe=fab0b459e0) | Feb 18, 2024 |
| Dell          | Vostro 15-3568              | Notebook    | [75d09cfc27](https://linux-hardware.org/?probe=75d09cfc27) | Feb 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [96859b01b7](https://linux-hardware.org/?probe=96859b01b7) | Feb 17, 2024 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [9e494a90c5](https://linux-hardware.org/?probe=9e494a90c5) | Feb 17, 2024 |
| HP            | OMEN by Gaming Laptop 16... | Notebook    | [39da02c65d](https://linux-hardware.org/?probe=39da02c65d) | Feb 16, 2024 |
| Dell          | Inspiron 7566               | Notebook    | [9d3c279e4c](https://linux-hardware.org/?probe=9d3c279e4c) | Feb 16, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | Notebook    | [70a8707a5c](https://linux-hardware.org/?probe=70a8707a5c) | Feb 15, 2024 |
| ASRock        | B450M Pro4-F                | Desktop     | [a98775e16e](https://linux-hardware.org/?probe=a98775e16e) | Feb 13, 2024 |
| Dell          | Latitude 3190               | Notebook    | [2f96d064fd](https://linux-hardware.org/?probe=2f96d064fd) | Feb 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [a7f40a3ffe](https://linux-hardware.org/?probe=a7f40a3ffe) | Feb 11, 2024 |
| Fujitsu Si... | AMILO Li 1818               | Notebook    | [1703fc6a96](https://linux-hardware.org/?probe=1703fc6a96) | Feb 11, 2024 |
| ASUSTek       | T100TAM                     | Notebook    | [2b6b08ce6c](https://linux-hardware.org/?probe=2b6b08ce6c) | Feb 10, 2024 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [de7b828cc8](https://linux-hardware.org/?probe=de7b828cc8) | Feb 10, 2024 |
| Dell          | XPS 13 9350                 | Notebook    | [24d22f38e9](https://linux-hardware.org/?probe=24d22f38e9) | Feb 08, 2024 |
| ASRock        | 970 Extreme4                | Desktop     | [973c66c65d](https://linux-hardware.org/?probe=973c66c65d) | Feb 07, 2024 |
| Dell          | Latitude 3190               | Notebook    | [f597a4ca06](https://linux-hardware.org/?probe=f597a4ca06) | Feb 06, 2024 |
| MSI           | GE63 Raider RGB 9SE         | Notebook    | [044863dd64](https://linux-hardware.org/?probe=044863dd64) | Feb 05, 2024 |
| Dell          | Latitude 120L               | Notebook    | [e5707dd6cb](https://linux-hardware.org/?probe=e5707dd6cb) | Feb 04, 2024 |
| Samsung       | 750XDA                      | Notebook    | [a7dd0472ed](https://linux-hardware.org/?probe=a7dd0472ed) | Feb 03, 2024 |
| Acidanther... | Mac-F221DCC8                | All in one  | [973ce60ef5](https://linux-hardware.org/?probe=973ce60ef5) | Feb 03, 2024 |
| Acidanther... | Mac-F221DCC8                | All in one  | [f610379068](https://linux-hardware.org/?probe=f610379068) | Feb 03, 2024 |
| VIT           | P3400                       | Notebook    | [036ee57838](https://linux-hardware.org/?probe=036ee57838) | Feb 02, 2024 |
| HP            | 09E8h                       | Desktop     | [413788d555](https://linux-hardware.org/?probe=413788d555) | Feb 02, 2024 |
| VIT           | P3400                       | Notebook    | [6b03e6574f](https://linux-hardware.org/?probe=6b03e6574f) | Feb 01, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [653f9c5fa5](https://linux-hardware.org/?probe=653f9c5fa5) | Feb 01, 2024 |
| Dell          | 00VTMF A01                  | Desktop     | [3298485dd9](https://linux-hardware.org/?probe=3298485dd9) | Jan 31, 2024 |
| Dell          | Latitude 3190               | Notebook    | [16f86af47d](https://linux-hardware.org/?probe=16f86af47d) | Jan 30, 2024 |
| HP            | Spectre x360 Convertible... | Convertible | [35aa462f74](https://linux-hardware.org/?probe=35aa462f74) | Jan 30, 2024 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [3f817efef4](https://linux-hardware.org/?probe=3f817efef4) | Jan 26, 2024 |
| HP            | 304Ah                       | Desktop     | [5e40a8acee](https://linux-hardware.org/?probe=5e40a8acee) | Jan 24, 2024 |
| Dell          | Latitude E6410              | Notebook    | [1b7b83010f](https://linux-hardware.org/?probe=1b7b83010f) | Jan 24, 2024 |
| Apple         | MacBookAir6,2               | Notebook    | [6eb8876e79](https://linux-hardware.org/?probe=6eb8876e79) | Jan 24, 2024 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [6ae01879d8](https://linux-hardware.org/?probe=6ae01879d8) | Jan 23, 2024 |
| HP            | 0A5Ch                       | Desktop     | [f886596563](https://linux-hardware.org/?probe=f886596563) | Jan 23, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [e03dc88f3e](https://linux-hardware.org/?probe=e03dc88f3e) | Jan 20, 2024 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [0da14a9376](https://linux-hardware.org/?probe=0da14a9376) | Jan 18, 2024 |
| HP            | Notebook                    | Notebook    | [0f5f8dd38d](https://linux-hardware.org/?probe=0f5f8dd38d) | Jan 17, 2024 |
| Google        | Barla                       | Notebook    | [f053c5164a](https://linux-hardware.org/?probe=f053c5164a) | Jan 16, 2024 |
| HP            | 8750                        | Desktop     | [6dd29a1c24](https://linux-hardware.org/?probe=6dd29a1c24) | Jan 16, 2024 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [33216d3bf8](https://linux-hardware.org/?probe=33216d3bf8) | Jan 16, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | Notebook    | [d0af07b360](https://linux-hardware.org/?probe=d0af07b360) | Jan 15, 2024 |
| Apple         | MacBookPro14,3              | Notebook    | [3b0c274172](https://linux-hardware.org/?probe=3b0c274172) | Jan 12, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [f782b74751](https://linux-hardware.org/?probe=f782b74751) | Jan 12, 2024 |
| Unknown       | GB01                        | Desktop     | [33016aa27b](https://linux-hardware.org/?probe=33016aa27b) | Jan 11, 2024 |
| Unknown       | GB01                        | Desktop     | [551b27fa9b](https://linux-hardware.org/?probe=551b27fa9b) | Jan 11, 2024 |
| Dell          | 0KV62T A00                  | Desktop     | [17aa442f24](https://linux-hardware.org/?probe=17aa442f24) | Jan 10, 2024 |
| Dell          | Latitude 3190               | Notebook    | [afdd5a1dbe](https://linux-hardware.org/?probe=afdd5a1dbe) | Jan 09, 2024 |
| HP            | Pavilion dv2700             | Notebook    | [957ec4cc30](https://linux-hardware.org/?probe=957ec4cc30) | Jan 09, 2024 |
| KEIAN         | KI8-BK                      | Tablet      | [aaf299df58](https://linux-hardware.org/?probe=aaf299df58) | Jan 08, 2024 |
| Sony          | SVF1521H1EW                 | Notebook    | [1939183179](https://linux-hardware.org/?probe=1939183179) | Jan 07, 2024 |
| ASUSTek       | PN52                        | Mini pc     | [5c770765da](https://linux-hardware.org/?probe=5c770765da) | Jan 05, 2024 |
| HP            | 8265                        | Desktop     | [da63a4f9c1](https://linux-hardware.org/?probe=da63a4f9c1) | Jan 05, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [71d03730b7](https://linux-hardware.org/?probe=71d03730b7) | Jan 03, 2024 |
| Dell          | Latitude 5400               | Notebook    | [9e318e9b78](https://linux-hardware.org/?probe=9e318e9b78) | Jan 03, 2024 |
| Dell          | Latitude 5400               | Notebook    | [59a90bd726](https://linux-hardware.org/?probe=59a90bd726) | Jan 03, 2024 |
| Google        | Barla                       | Notebook    | [585887bc42](https://linux-hardware.org/?probe=585887bc42) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [8f3ab867ea](https://linux-hardware.org/?probe=8f3ab867ea) | Dec 30, 2023 |
| HP            | 8265                        | Desktop     | [94344dbe98](https://linux-hardware.org/?probe=94344dbe98) | Dec 28, 2023 |
| HP            | Pavilion dv6                | Notebook    | [39515c70db](https://linux-hardware.org/?probe=39515c70db) | Dec 27, 2023 |
| HP            | Pavilion dv6                | Notebook    | [c29956a752](https://linux-hardware.org/?probe=c29956a752) | Dec 27, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [5647df79c0](https://linux-hardware.org/?probe=5647df79c0) | Dec 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [e0da711bcb](https://linux-hardware.org/?probe=e0da711bcb) | Dec 26, 2023 |
| Dell          | 033FF6 A00                  | Desktop     | [977367b99e](https://linux-hardware.org/?probe=977367b99e) | Dec 26, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [eade6242b7](https://linux-hardware.org/?probe=eade6242b7) | Dec 25, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [ab0b99f2f2](https://linux-hardware.org/?probe=ab0b99f2f2) | Dec 25, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [0da41c3e3b](https://linux-hardware.org/?probe=0da41c3e3b) | Dec 25, 2023 |
| Google        | Bobba                       | Notebook    | [c0e8038184](https://linux-hardware.org/?probe=c0e8038184) | Dec 22, 2023 |
| Google        | Bobba                       | Notebook    | [c03b219f2e](https://linux-hardware.org/?probe=c03b219f2e) | Dec 22, 2023 |
| Lenovo        | MIIX 300-10IBY 80NR         | Tablet      | [456c5b7613](https://linux-hardware.org/?probe=456c5b7613) | Dec 21, 2023 |
| Dell          | 033FF6 A00                  | Desktop     | [88cad415fb](https://linux-hardware.org/?probe=88cad415fb) | Dec 21, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [bc7fc2be74](https://linux-hardware.org/?probe=bc7fc2be74) | Dec 20, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [11f3b9c9d6](https://linux-hardware.org/?probe=11f3b9c9d6) | Dec 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f912bcd96a](https://linux-hardware.org/?probe=f912bcd96a) | Dec 20, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a7e488632e](https://linux-hardware.org/?probe=a7e488632e) | Dec 19, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [97e3b8d570](https://linux-hardware.org/?probe=97e3b8d570) | Dec 18, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [a6d28b0e6a](https://linux-hardware.org/?probe=a6d28b0e6a) | Dec 18, 2023 |
| HP            | 8265                        | Desktop     | [cc0b59e7f7](https://linux-hardware.org/?probe=cc0b59e7f7) | Dec 13, 2023 |
| HP            | Notebook                    | Notebook    | [d25691af9b](https://linux-hardware.org/?probe=d25691af9b) | Dec 13, 2023 |
| Gigabyte      | MRHM7AP                     | Desktop     | [ba4400c919](https://linux-hardware.org/?probe=ba4400c919) | Dec 13, 2023 |
| Dell          | Latitude 3190               | Notebook    | [faf8105e3c](https://linux-hardware.org/?probe=faf8105e3c) | Dec 12, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [10e35dbb2a](https://linux-hardware.org/?probe=10e35dbb2a) | Dec 12, 2023 |
| Dell          | Vostro 1320                 | Notebook    | [cf44765cd0](https://linux-hardware.org/?probe=cf44765cd0) | Dec 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [8fc19fa86c](https://linux-hardware.org/?probe=8fc19fa86c) | Dec 11, 2023 |
| Lenovo        | ThinkPad X201 3626GWG       | Notebook    | [023f7dd390](https://linux-hardware.org/?probe=023f7dd390) | Dec 11, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [3bbc394b2e](https://linux-hardware.org/?probe=3bbc394b2e) | Dec 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [6c558ca3cf](https://linux-hardware.org/?probe=6c558ca3cf) | Dec 06, 2023 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [442d7a2388](https://linux-hardware.org/?probe=442d7a2388) | Dec 03, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [d536392d03](https://linux-hardware.org/?probe=d536392d03) | Nov 30, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [bfe263dfe0](https://linux-hardware.org/?probe=bfe263dfe0) | Nov 30, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [339e20f716](https://linux-hardware.org/?probe=339e20f716) | Nov 24, 2023 |
| MSI           | A68HM-P33 V2                | Desktop     | [bee7ef1689](https://linux-hardware.org/?probe=bee7ef1689) | Nov 22, 2023 |
| Mediacom      | FlexBook edge11 - M-FBE1... | Notebook    | [9b0835e62d](https://linux-hardware.org/?probe=9b0835e62d) | Nov 21, 2023 |
| Dell          | Latitude 3190               | Notebook    | [3c5b8541c7](https://linux-hardware.org/?probe=3c5b8541c7) | Nov 21, 2023 |
| HP            | 8265                        | Desktop     | [d798ead6f7](https://linux-hardware.org/?probe=d798ead6f7) | Nov 20, 2023 |
| Acer          | Extensa 215-55              | Notebook    | [e1a2307332](https://linux-hardware.org/?probe=e1a2307332) | Nov 18, 2023 |
| Dell          | Precision 5570              | Notebook    | [7cb435d2dc](https://linux-hardware.org/?probe=7cb435d2dc) | Nov 16, 2023 |
| HP            | ProLiant DL380 G5           | Server      | [55414de640](https://linux-hardware.org/?probe=55414de640) | Nov 14, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [23196bda4d](https://linux-hardware.org/?probe=23196bda4d) | Nov 14, 2023 |
| Gateway       | NV57H                       | Notebook    | [e5f084f72c](https://linux-hardware.org/?probe=e5f084f72c) | Nov 11, 2023 |
| HP            | 3397                        | Desktop     | [67e178009d](https://linux-hardware.org/?probe=67e178009d) | Nov 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [751f4b0d96](https://linux-hardware.org/?probe=751f4b0d96) | Nov 08, 2023 |
| Intel         | NUC7JYB J67967-406          | Mini pc     | [600002b4a9](https://linux-hardware.org/?probe=600002b4a9) | Nov 08, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [25ab11fca1](https://linux-hardware.org/?probe=25ab11fca1) | Nov 08, 2023 |
| Dell          | Latitude 3190               | Notebook    | [309f968d10](https://linux-hardware.org/?probe=309f968d10) | Nov 07, 2023 |
| HP            | 2B34                        | Desktop     | [52737869e2](https://linux-hardware.org/?probe=52737869e2) | Nov 06, 2023 |
| HP            | ProBook 6470b               | Notebook    | [50c1d43281](https://linux-hardware.org/?probe=50c1d43281) | Nov 05, 2023 |
| AMI           | Unknown                     | Notebook    | [2512404fd7](https://linux-hardware.org/?probe=2512404fd7) | Nov 05, 2023 |
| ASRock        | A320M Pro4-F                | Desktop     | [7dab52cd8c](https://linux-hardware.org/?probe=7dab52cd8c) | Nov 05, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [e95902544f](https://linux-hardware.org/?probe=e95902544f) | Nov 03, 2023 |
| Dell          | Latitude 5490               | Notebook    | [fcee866d9a](https://linux-hardware.org/?probe=fcee866d9a) | Oct 31, 2023 |
| Dell          | Latitude 3190               | Notebook    | [dc68dc55c9](https://linux-hardware.org/?probe=dc68dc55c9) | Oct 31, 2023 |
| HONOR         | BMH-WDX9                    | Notebook    | [a1962fef8a](https://linux-hardware.org/?probe=a1962fef8a) | Oct 31, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0a5b6171b7](https://linux-hardware.org/?probe=0a5b6171b7) | Oct 30, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [52786d6efa](https://linux-hardware.org/?probe=52786d6efa) | Oct 30, 2023 |
| Intel         | H81                         | Desktop     | [2e37259d45](https://linux-hardware.org/?probe=2e37259d45) | Oct 29, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2cb1fb1ec9](https://linux-hardware.org/?probe=2cb1fb1ec9) | Oct 27, 2023 |
| HP            | 339A                        | Desktop     | [d0deadc097](https://linux-hardware.org/?probe=d0deadc097) | Oct 27, 2023 |
| Lenovo        | 376D SDK0T76465 WIN 3422... | Desktop     | [2a97bb6c00](https://linux-hardware.org/?probe=2a97bb6c00) | Oct 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a26f69cb33](https://linux-hardware.org/?probe=a26f69cb33) | Oct 24, 2023 |
| AZW           | SER V1                      | Desktop     | [8c734a7dfc](https://linux-hardware.org/?probe=8c734a7dfc) | Oct 21, 2023 |
| Dell          | Inspiron 16 7610            | Notebook    | [36eb2472ca](https://linux-hardware.org/?probe=36eb2472ca) | Oct 20, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [6c7d912754](https://linux-hardware.org/?probe=6c7d912754) | Oct 20, 2023 |
| Acer          | Aspire TC-1760              | Desktop     | [9e4ac23c4b](https://linux-hardware.org/?probe=9e4ac23c4b) | Oct 19, 2023 |
| Sony          | SVF1521A6EW                 | Notebook    | [dada2b85e8](https://linux-hardware.org/?probe=dada2b85e8) | Oct 17, 2023 |
| Dell          | Inspiron 5448               | Notebook    | [5901b49079](https://linux-hardware.org/?probe=5901b49079) | Oct 17, 2023 |
| Dell          | Latitude 3190               | Notebook    | [6524dff50f](https://linux-hardware.org/?probe=6524dff50f) | Oct 17, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [60e2d65ac4](https://linux-hardware.org/?probe=60e2d65ac4) | Oct 16, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [df7395bd63](https://linux-hardware.org/?probe=df7395bd63) | Oct 16, 2023 |
| Gigabyte      | Z690 UD AX DDR4             | Desktop     | [273e4a294a](https://linux-hardware.org/?probe=273e4a294a) | Oct 15, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [665eba904c](https://linux-hardware.org/?probe=665eba904c) | Oct 14, 2023 |
| Google        | Celes                       | Notebook    | [914ad131fd](https://linux-hardware.org/?probe=914ad131fd) | Oct 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [00fc33d73e](https://linux-hardware.org/?probe=00fc33d73e) | Oct 13, 2023 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [6f4fb2dff4](https://linux-hardware.org/?probe=6f4fb2dff4) | Oct 10, 2023 |
| Dell          | Latitude E6410              | Notebook    | [d6db17e35f](https://linux-hardware.org/?probe=d6db17e35f) | Oct 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [21aac15234](https://linux-hardware.org/?probe=21aac15234) | Oct 03, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [4b46fb8e6a](https://linux-hardware.org/?probe=4b46fb8e6a) | Oct 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4a6090c2f4](https://linux-hardware.org/?probe=4a6090c2f4) | Sep 29, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | Notebook    | [ee6e1996b9](https://linux-hardware.org/?probe=ee6e1996b9) | Sep 29, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [3c87964524](https://linux-hardware.org/?probe=3c87964524) | Sep 28, 2023 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | Notebook    | [2b7f074e47](https://linux-hardware.org/?probe=2b7f074e47) | Sep 27, 2023 |
| Dell          | Latitude 3190               | Notebook    | [8ebd8669f2](https://linux-hardware.org/?probe=8ebd8669f2) | Sep 26, 2023 |
| MSI           | G41M4                       | Desktop     | [0554e9757f](https://linux-hardware.org/?probe=0554e9757f) | Sep 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4054ad9d77](https://linux-hardware.org/?probe=4054ad9d77) | Sep 26, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [76d936bb5b](https://linux-hardware.org/?probe=76d936bb5b) | Sep 26, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [55dec782e7](https://linux-hardware.org/?probe=55dec782e7) | Sep 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [0c1f872edb](https://linux-hardware.org/?probe=0c1f872edb) | Sep 23, 2023 |
| Dell          | Precision 5570              | Notebook    | [27b003d343](https://linux-hardware.org/?probe=27b003d343) | Sep 22, 2023 |
| HP            | EliteBook 735 G6            | Notebook    | [0ad032f320](https://linux-hardware.org/?probe=0ad032f320) | Sep 19, 2023 |
| Dell          | Latitude 3190               | Notebook    | [0a698044d8](https://linux-hardware.org/?probe=0a698044d8) | Sep 19, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9e9652809d](https://linux-hardware.org/?probe=9e9652809d) | Sep 18, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [d66a3d9329](https://linux-hardware.org/?probe=d66a3d9329) | Sep 18, 2023 |
| Dell          | Latitude D620               | Notebook    | [65d2f56829](https://linux-hardware.org/?probe=65d2f56829) | Sep 18, 2023 |
| HP            | Pavilion dv2                | Notebook    | [ee227b3d35](https://linux-hardware.org/?probe=ee227b3d35) | Sep 16, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [82cae5303a](https://linux-hardware.org/?probe=82cae5303a) | Sep 16, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [db874f0737](https://linux-hardware.org/?probe=db874f0737) | Sep 16, 2023 |
| ASUSTek       | K54L                        | Notebook    | [4b62e4c882](https://linux-hardware.org/?probe=4b62e4c882) | Sep 15, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [fcfde3095d](https://linux-hardware.org/?probe=fcfde3095d) | Sep 12, 2023 |
| Dell          | Latitude 3190               | Notebook    | [a03ec42023](https://linux-hardware.org/?probe=a03ec42023) | Sep 12, 2023 |
| Dell          | XPS 17 9700                 | Notebook    | [e83ef4efd8](https://linux-hardware.org/?probe=e83ef4efd8) | Sep 11, 2023 |
| Lenovo        | ThinkPad L580 20LW000VFR    | Notebook    | [a7dfc5e0f5](https://linux-hardware.org/?probe=a7dfc5e0f5) | Sep 09, 2023 |
| Lenovo        | ThinkPad L580 20LW000VFR    | Notebook    | [e224a5dc53](https://linux-hardware.org/?probe=e224a5dc53) | Sep 09, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | Notebook    | [b906e23303](https://linux-hardware.org/?probe=b906e23303) | Sep 08, 2023 |
| HP            | ProBook 640 G2              | Notebook    | [318f1010b6](https://linux-hardware.org/?probe=318f1010b6) | Sep 08, 2023 |
| ASUSTek       | Z97-P                       | Desktop     | [d72c4b5cce](https://linux-hardware.org/?probe=d72c4b5cce) | Sep 06, 2023 |
| Dell          | Latitude 3190               | Notebook    | [7be68f9c9a](https://linux-hardware.org/?probe=7be68f9c9a) | Sep 06, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [baad816533](https://linux-hardware.org/?probe=baad816533) | Sep 05, 2023 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [a9fdf4f92b](https://linux-hardware.org/?probe=a9fdf4f92b) | Sep 03, 2023 |
| ASRock        | J4205-ITX                   | Desktop     | [8831793b97](https://linux-hardware.org/?probe=8831793b97) | Sep 03, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [9d8f7c345f](https://linux-hardware.org/?probe=9d8f7c345f) | Sep 01, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2e3c70287a](https://linux-hardware.org/?probe=2e3c70287a) | Aug 30, 2023 |
| Dell          | Latitude 3190               | Notebook    | [6e16da127a](https://linux-hardware.org/?probe=6e16da127a) | Aug 29, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [51ea627e30](https://linux-hardware.org/?probe=51ea627e30) | Aug 25, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [c8e9f89359](https://linux-hardware.org/?probe=c8e9f89359) | Aug 25, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [fcb0ac31fe](https://linux-hardware.org/?probe=fcb0ac31fe) | Aug 23, 2023 |
| Dell          | Latitude 3190               | Notebook    | [61ddf042df](https://linux-hardware.org/?probe=61ddf042df) | Aug 22, 2023 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [c6f294e543](https://linux-hardware.org/?probe=c6f294e543) | Aug 21, 2023 |
| Gigabyte      | MZGLKCP-00                  | Desktop     | [d6e0b89f34](https://linux-hardware.org/?probe=d6e0b89f34) | Aug 21, 2023 |
| Biostar       | H310MHC2                    | Desktop     | [12f3b0d269](https://linux-hardware.org/?probe=12f3b0d269) | Aug 20, 2023 |
| Dell          | Latitude E6430              | Notebook    | [27d598d911](https://linux-hardware.org/?probe=27d598d911) | Aug 18, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [b9134a5ee3](https://linux-hardware.org/?probe=b9134a5ee3) | Aug 16, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [e5661bef5b](https://linux-hardware.org/?probe=e5661bef5b) | Aug 16, 2023 |
| Beelink       | Gemini X                    | Notebook    | [d5c4e54794](https://linux-hardware.org/?probe=d5c4e54794) | Aug 14, 2023 |
| Dell          | Vostro 15-3568              | Notebook    | [b422d7c8cc](https://linux-hardware.org/?probe=b422d7c8cc) | Aug 12, 2023 |
| Toshiba       | Satellite T110              | Notebook    | [8180105119](https://linux-hardware.org/?probe=8180105119) | Aug 11, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [69123aa283](https://linux-hardware.org/?probe=69123aa283) | Aug 10, 2023 |
| Dell          | Inspiron 5415               | Notebook    | [9c28979b9d](https://linux-hardware.org/?probe=9c28979b9d) | Aug 10, 2023 |
| Dell          | Latitude E6540              | Notebook    | [758d587fbb](https://linux-hardware.org/?probe=758d587fbb) | Aug 10, 2023 |
| ASUSTek       | UL30A                       | Notebook    | [11f3b9cfad](https://linux-hardware.org/?probe=11f3b9cfad) | Aug 08, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [f30c6c7bb5](https://linux-hardware.org/?probe=f30c6c7bb5) | Aug 08, 2023 |
| Dell          | Inspiron 7391 2n1           | Convertible | [c7a3dd2647](https://linux-hardware.org/?probe=c7a3dd2647) | Aug 07, 2023 |
| Dell          | Inspiron 7391 2n1           | Convertible | [ed6fdbd235](https://linux-hardware.org/?probe=ed6fdbd235) | Aug 07, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [5777798e8f](https://linux-hardware.org/?probe=5777798e8f) | Aug 07, 2023 |
| ASUSTek       | ProArt StudioBook W5600Q... | Notebook    | [96211a5c87](https://linux-hardware.org/?probe=96211a5c87) | Aug 05, 2023 |
| Dell          | Latitude E6320              | Notebook    | [9b42be4945](https://linux-hardware.org/?probe=9b42be4945) | Aug 02, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a0270160ad](https://linux-hardware.org/?probe=a0270160ad) | Aug 02, 2023 |
| Dell          | Latitude 3190               | Notebook    | [c88a2ad597](https://linux-hardware.org/?probe=c88a2ad597) | Aug 01, 2023 |
| Lenovo        | 3000 C100 07612GU           | Notebook    | [3941ecc4f2](https://linux-hardware.org/?probe=3941ecc4f2) | Aug 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [095890a440](https://linux-hardware.org/?probe=095890a440) | Jul 31, 2023 |
| Dell          | Latitude 5340               | Notebook    | [5ab5c25167](https://linux-hardware.org/?probe=5ab5c25167) | Jul 28, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e235fb3a23](https://linux-hardware.org/?probe=e235fb3a23) | Jul 26, 2023 |
| Dell          | Latitude 3190               | Notebook    | [b1730d834d](https://linux-hardware.org/?probe=b1730d834d) | Jul 25, 2023 |
| Dell          | Latitude 3510               | Notebook    | [e1eb8b885c](https://linux-hardware.org/?probe=e1eb8b885c) | Jul 21, 2023 |
| Dell          | Latitude 5530               | Notebook    | [235731a6f1](https://linux-hardware.org/?probe=235731a6f1) | Jul 20, 2023 |
| Dell          | Latitude 5310               | Notebook    | [5b81040709](https://linux-hardware.org/?probe=5b81040709) | Jul 20, 2023 |
| Dell          | Precision 5510              | Notebook    | [ff4ea6ba94](https://linux-hardware.org/?probe=ff4ea6ba94) | Jul 17, 2023 |
| Sony          | VGN-S3HP                    | Notebook    | [6e2c92c447](https://linux-hardware.org/?probe=6e2c92c447) | Jul 17, 2023 |
| Dell          | Latitude 5530               | Notebook    | [37681b3327](https://linux-hardware.org/?probe=37681b3327) | Jul 17, 2023 |
| Dell          | Precision 3571              | Notebook    | [2123567cb0](https://linux-hardware.org/?probe=2123567cb0) | Jul 16, 2023 |
| Dell          | Latitude 3190               | Notebook    | [f067ca0dbf](https://linux-hardware.org/?probe=f067ca0dbf) | Jul 11, 2023 |
| Dell          | Latitude 3190               | Notebook    | [b895b6dced](https://linux-hardware.org/?probe=b895b6dced) | Jul 04, 2023 |
| Dell          | Latitude 3190               | Notebook    | [5f68b5235f](https://linux-hardware.org/?probe=5f68b5235f) | Jun 27, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [f47c68a2a7](https://linux-hardware.org/?probe=f47c68a2a7) | Jun 04, 2023 |
| Gigabyte      | H61MA-D3V                   | Desktop     | [a37deef915](https://linux-hardware.org/?probe=a37deef915) | Apr 24, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 6.1.0-17-amd64             | 31        | 12.81%  |
| 6.1.0-13-amd64             | 30        | 12.4%   |
| 6.1.0-10-amd64             | 27        | 11.16%  |
| 6.4.0-1mx-ahs-amd64        | 19        | 7.85%   |
| 6.5.0-1mx-ahs-amd64        | 18        | 7.44%   |
| 6.1.0-18-amd64             | 17        | 7.02%   |
| 6.1.0-20-amd64             | 9         | 3.72%   |
| 6.6.12-1-liquorix-amd64    | 8         | 3.31%   |
| 6.1.0-9-amd64              | 8         | 3.31%   |
| 6.1.0-11-amd64             | 8         | 3.31%   |
| 6.1.0-17-686-pae           | 5         | 2.07%   |
| 6.1.0-15-amd64             | 5         | 2.07%   |
| 6.1.0-12-amd64             | 5         | 2.07%   |
| 6.7.12-1-liquorix-amd64    | 4         | 1.65%   |
| 6.1.0-16-amd64             | 4         | 1.65%   |
| 6.7.5-1-liquorix-amd64     | 2         | 0.83%   |
| 6.6.9-1-liquorix-amd64     | 2         | 0.83%   |
| 6.6.11-amd64               | 2         | 0.83%   |
| 6.4.9-1-liquorix-amd64     | 2         | 0.83%   |
| 6.4.15-2-liquorix-amd64    | 2         | 0.83%   |
| 6.1.0-13-686-pae           | 2         | 0.83%   |
| 6.1.0-10-686-pae           | 2         | 0.83%   |
| 5.10.197-antix.1-amd64-smp | 2         | 0.83%   |
| 6.7.8-1-liquorix-amd64     | 1         | 0.41%   |
| 6.7.6-1-liquorix-amd64     | 1         | 0.41%   |
| 6.7.11-1-liquorix-amd64    | 1         | 0.41%   |
| 6.6.9-amd64                | 1         | 0.41%   |
| 6.6.8-2-liquorix-amd64     | 1         | 0.41%   |
| 6.6.7-x64v1-xanmod1        | 1         | 0.41%   |
| 6.6.0-custom               | 1         | 0.41%   |
| 6.5.5-2-liquorix-amd64     | 1         | 0.41%   |
| 6.5.11-1-liquorix-amd64    | 1         | 0.41%   |
| 6.5.10-1-liquorix-amd64    | 1         | 0.41%   |
| 6.5.0-2-amd64              | 1         | 0.41%   |
| 6.4.14-1-liquorix-amd64    | 1         | 0.41%   |
| 6.4.0-4mx-ahs-amd64        | 1         | 0.41%   |
| 6.4.0-3mx-ahs-amd64        | 1         | 0.41%   |
| 6.4.0-2mx-ahs-amd64        | 1         | 0.41%   |
| 6.3.9-1-liquorix-amd64     | 1         | 0.41%   |
| 6.3.0-2mx-ahs-amd64        | 1         | 0.41%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 6.1.0    | 150       | 64.94%  |
| 6.4.0    | 22        | 9.52%   |
| 6.5.0    | 19        | 8.23%   |
| 6.6.12   | 8         | 3.46%   |
| 6.7.12   | 4         | 1.73%   |
| 6.6.9    | 3         | 1.3%    |
| 6.7.5    | 2         | 0.87%   |
| 6.6.11   | 2         | 0.87%   |
| 6.4.9    | 2         | 0.87%   |
| 6.4.15   | 2         | 0.87%   |
| 5.10.197 | 2         | 0.87%   |
| 6.7.8    | 1         | 0.43%   |
| 6.7.6    | 1         | 0.43%   |
| 6.7.11   | 1         | 0.43%   |
| 6.6.8    | 1         | 0.43%   |
| 6.6.7    | 1         | 0.43%   |
| 6.6.0    | 1         | 0.43%   |
| 6.5.5    | 1         | 0.43%   |
| 6.5.11   | 1         | 0.43%   |
| 6.5.10   | 1         | 0.43%   |
| 6.4.14   | 1         | 0.43%   |
| 6.3.9    | 1         | 0.43%   |
| 6.3.0    | 1         | 0.43%   |
| 6.2.14   | 1         | 0.43%   |
| 6.1.77   | 1         | 0.43%   |
| 5.10.0   | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 151       | 65.65%  |
| 6.4     | 27        | 11.74%  |
| 6.5     | 22        | 9.57%   |
| 6.6     | 16        | 6.96%   |
| 6.7     | 8         | 3.48%   |
| 5.10    | 3         | 1.3%    |
| 6.3     | 2         | 0.87%   |
| 6.2     | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 214       | 94.27%  |
| i686    | 12        | 5.29%   |
| aarch64 | 1         | 0.44%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| XFCE             | 161       | 70.93%  |
| KDE5             | 53        | 23.35%  |
| fluxbox          | 4         | 1.76%   |
| X-Cinnamon       | 2         | 0.88%   |
| LXQt             | 2         | 0.88%   |
| lightdm-xsession | 2         | 0.88%   |
| MATE             | 1         | 0.44%   |
| GNOME Flashback  | 1         | 0.44%   |
| Unknown          | 1         | 0.44%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 224       | 98.68%  |
| Tty  | 2         | 0.88%   |
| Web  | 1         | 0.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 174       | 76.65%  |
| SDDM    | 53        | 23.35%  |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 110       | 48.03%  |
| de_DE   | 18        | 7.86%   |
| en_GB   | 14        | 6.11%   |
| it_IT   | 11        | 4.8%    |
| fr_FR   | 11        | 4.8%    |
| pl_PL   | 10        | 4.37%   |
| ru_RU   | 7         | 3.06%   |
| en_AU   | 7         | 3.06%   |
| es_ES   | 6         | 2.62%   |
| en_CA   | 4         | 1.75%   |
| pt_BR   | 3         | 1.31%   |
| C       | 3         | 1.31%   |
| ja_JP   | 2         | 0.87%   |
| hr_HR   | 2         | 0.87%   |
| es_VE   | 2         | 0.87%   |
| es_US   | 2         | 0.87%   |
| es_MX   | 2         | 0.87%   |
| en_IE   | 2         | 0.87%   |
| el_GR   | 2         | 0.87%   |
| uk_UA   | 1         | 0.44%   |
| tr_TR   | 1         | 0.44%   |
| sk_SK   | 1         | 0.44%   |
| nl_NL   | 1         | 0.44%   |
| ko_KR   | 1         | 0.44%   |
| hu_HU   | 1         | 0.44%   |
| fi_FI   | 1         | 0.44%   |
| en_NZ   | 1         | 0.44%   |
| en_IL   | 1         | 0.44%   |
| de_AT   | 1         | 0.44%   |
| Unknown | 1         | 0.44%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 166       | 72.81%  |
| BIOS | 62        | 27.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 188       | 82.82%  |
| Overlay | 27        | 11.89%  |
| Btrfs   | 9         | 3.96%   |
| Tmpfs   | 2         | 0.88%   |
| F2fs    | 1         | 0.44%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Computers | Percent |
|------|-----------|---------|
| GPT  | 174       | 76.65%  |
| MBR  | 53        | 23.35%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 184       | 80.7%   |
| Yes       | 44        | 19.3%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 142       | 62.01%  |
| Yes       | 87        | 37.99%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 37        | 16.3%   |
| Hewlett-Packard         | 36        | 15.86%  |
| Lenovo                  | 31        | 13.66%  |
| ASUSTek Computer        | 29        | 12.78%  |
| Gigabyte Technology     | 14        | 6.17%   |
| Apple                   | 13        | 5.73%   |
| ASRock                  | 6         | 2.64%   |
| Acer                    | 6         | 2.64%   |
| Toshiba                 | 5         | 2.2%    |
| Google                  | 5         | 2.2%    |
| Samsung Electronics     | 4         | 1.76%   |
| MSI                     | 4         | 1.76%   |
| Sony                    | 3         | 1.32%   |
| Intel                   | 3         | 1.32%   |
| Foxconn                 | 3         | 1.32%   |
| AMI                     | 3         | 1.32%   |
| HONOR                   | 2         | 0.88%   |
| GPU Company             | 2         | 0.88%   |
| AZW                     | 2         | 0.88%   |
| VIT                     | 1         | 0.44%   |
| SGIN                    | 1         | 0.44%   |
| Semp Toshiba            | 1         | 0.44%   |
| Raspberry Pi Foundation | 1         | 0.44%   |
| Pegatron                | 1         | 0.44%   |
| PC Specialist           | 1         | 0.44%   |
| Medion                  | 1         | 0.44%   |
| Mediacom                | 1         | 0.44%   |
| KEIAN                   | 1         | 0.44%   |
| IP3 Tech                | 1         | 0.44%   |
| I-life                  | 1         | 0.44%   |
| Gateway                 | 1         | 0.44%   |
| Fujitsu Siemens         | 1         | 0.44%   |
| Fujitsu                 | 1         | 0.44%   |
| Biostar                 | 1         | 0.44%   |
| Beelink                 | 1         | 0.44%   |
| Alienware               | 1         | 0.44%   |
| Acidanthera             | 1         | 0.44%   |
| Unknown                 | 1         | 0.44%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| HP Notebook                        | 3         | 1.32%   |
| HP Pavilion dv6                    | 2         | 0.88%   |
| HP EliteBook 840 G6                | 2         | 0.88%   |
| HP 250 15.6 inch G9 Notebook PC    | 2         | 0.88%   |
| Foxconn Pro3500 Series             | 2         | 0.88%   |
| Dell Latitude E6410                | 2         | 0.88%   |
| Dell Latitude 5530                 | 2         | 0.88%   |
| AZW SER                            | 2         | 0.88%   |
| Apple iMac7,1                      | 2         | 0.88%   |
| Unknown                            | 2         | 0.88%   |
| VIT P3400                          | 1         | 0.44%   |
| Toshiba Satellite P875             | 1         | 0.44%   |
| Toshiba Satellite C55D-B           | 1         | 0.44%   |
| Toshiba Satellite C55-A            | 1         | 0.44%   |
| Toshiba Satellite C50-B            | 1         | 0.44%   |
| Toshiba dynabook T552/36GB         | 1         | 0.44%   |
| Sony VGN-S3HP                      | 1         | 0.44%   |
| Sony SVF1521H1EW                   | 1         | 0.44%   |
| Sony SVF1521A6EW                   | 1         | 0.44%   |
| SGIN M15                           | 1         | 0.44%   |
| Semp Toshiba IS 1413G              | 1         | 0.44%   |
| Samsung RF511/RF411/RF711          | 1         | 0.44%   |
| Samsung N150/N210/N220             | 1         | 0.44%   |
| Samsung 750XDA                     | 1         | 0.44%   |
| Samsung 305E4A/305E5A/305E7A       | 1         | 0.44%   |
| RPi Raspberry Pi 4 Model B Rev 1.2 | 1         | 0.44%   |
| Pegatron 2AD5                      | 1         | 0.44%   |
| PC Specialist Lafite Pro III 17    | 1         | 0.44%   |
| MSI MS-7C95                        | 1         | 0.44%   |
| MSI MS-7895                        | 1         | 0.44%   |
| MSI MS-7592                        | 1         | 0.44%   |
| MSI GE63 Raider RGB 9SE            | 1         | 0.44%   |
| Medion Defender P30                | 1         | 0.44%   |
| Mediacom FlexBook edge11 - M-FBE11 | 1         | 0.44%   |
| Lenovo Yoga Slim 7-14ARE05 82A2    | 1         | 0.44%   |
| Lenovo Yoga 710-11IKB 80V6         | 1         | 0.44%   |
| Lenovo V15 G3 ABA 82TV             | 1         | 0.44%   |
| Lenovo ThinkPad X280 20KES6M100    | 1         | 0.44%   |
| Lenovo ThinkPad X240 20AMS1JQ11    | 1         | 0.44%   |
| Lenovo ThinkPad X201 3626GWG       | 1         | 0.44%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Dell Latitude     | 15        | 6.61%   |
| Lenovo ThinkPad   | 11        | 4.85%   |
| Lenovo IdeaPad    | 7         | 3.08%   |
| HP Pavilion       | 7         | 3.08%   |
| Dell Inspiron     | 7         | 3.08%   |
| ASUS VivoBook     | 6         | 2.64%   |
| HP Compaq         | 5         | 2.2%    |
| Toshiba Satellite | 4         | 1.76%   |
| HP EliteBook      | 4         | 1.76%   |
| Dell XPS          | 4         | 1.76%   |
| Dell Precision    | 4         | 1.76%   |
| Dell OptiPlex     | 4         | 1.76%   |
| ASUS TUF          | 4         | 1.76%   |
| Acer Aspire       | 4         | 1.76%   |
| HP Notebook       | 3         | 1.32%   |
| HP Laptop         | 3         | 1.32%   |
| HP 250            | 3         | 1.32%   |
| Dell Vostro       | 3         | 1.32%   |
| ASUS PRIME        | 3         | 1.32%   |
| Apple MacBookPro5 | 3         | 1.32%   |
| Lenovo Yoga       | 2         | 0.88%   |
| Lenovo Legion     | 2         | 0.88%   |
| HP ProBook        | 2         | 0.88%   |
| Foxconn Pro3500   | 2         | 0.88%   |
| AZW SER           | 2         | 0.88%   |
| Apple iMac7       | 2         | 0.88%   |
| Unknown           | 2         | 0.88%   |
| VIT P3400         | 1         | 0.44%   |
| Toshiba dynabook  | 1         | 0.44%   |
| Sony VGN-S3HP     | 1         | 0.44%   |
| Sony SVF1521H1EW  | 1         | 0.44%   |
| Sony SVF1521A6EW  | 1         | 0.44%   |
| SGIN M15          | 1         | 0.44%   |
| Semp Toshiba IS   | 1         | 0.44%   |
| Samsung RF511     | 1         | 0.44%   |
| Samsung N150      | 1         | 0.44%   |
| Samsung 750XDA    | 1         | 0.44%   |
| Samsung 305E4A    | 1         | 0.44%   |
| RPi Raspberry     | 1         | 0.44%   |
| Pegatron 2AD5     | 1         | 0.44%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2022    | 27        | 11.89%  |
| 2019    | 22        | 9.69%   |
| 2021    | 20        | 8.81%   |
| 2013    | 20        | 8.81%   |
| 2023    | 19        | 8.37%   |
| 2018    | 14        | 6.17%   |
| 2012    | 13        | 5.73%   |
| 2009    | 13        | 5.73%   |
| 2020    | 12        | 5.29%   |
| 2011    | 11        | 4.85%   |
| 2016    | 9         | 3.96%   |
| 2015    | 9         | 3.96%   |
| 2014    | 8         | 3.52%   |
| 2017    | 7         | 3.08%   |
| 2010    | 6         | 2.64%   |
| 2008    | 5         | 2.2%    |
| 2007    | 5         | 2.2%    |
| 2006    | 4         | 1.76%   |
| 2005    | 2         | 0.88%   |
| Unknown | 1         | 0.44%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 143       | 63%     |
| Desktop        | 62        | 27.31%  |
| Mini pc        | 7         | 3.08%   |
| All in one     | 6         | 2.64%   |
| Convertible    | 5         | 2.2%    |
| Tablet         | 2         | 0.88%   |
| System on chip | 1         | 0.44%   |
| Server         | 1         | 0.44%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 218       | 96.04%  |
| Enabled  | 9         | 3.96%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 222       | 97.8%   |
| Yes  | 5         | 2.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 53        | 23.35%  |
| 3.01-4.0    | 43        | 18.94%  |
| 16.01-24.0  | 43        | 18.94%  |
| 8.01-16.0   | 35        | 15.42%  |
| 32.01-64.0  | 28        | 12.33%  |
| 1.01-2.0    | 13        | 5.73%   |
| 24.01-32.0  | 6         | 2.64%   |
| 64.01-256.0 | 4         | 1.76%   |
| 2.01-3.0    | 2         | 0.88%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 93        | 39.74%  |
| 1.01-2.0   | 75        | 32.05%  |
| 3.01-4.0   | 31        | 13.25%  |
| 4.01-8.0   | 28        | 11.97%  |
| 0.51-1.0   | 4         | 1.71%   |
| 8.01-16.0  | 2         | 0.85%   |
| 16.01-24.0 | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 158       | 69.3%   |
| 2      | 43        | 18.86%  |
| 3      | 18        | 7.89%   |
| 4      | 4         | 1.75%   |
| 7      | 2         | 0.88%   |
| 5      | 2         | 0.88%   |
| 6      | 1         | 0.44%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 155       | 68.28%  |
| Yes       | 72        | 31.72%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 80.62%  |
| No        | 44        | 19.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 201       | 88.55%  |
| No        | 26        | 11.45%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 155       | 68.28%  |
| No        | 72        | 31.72%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 46        | 20%     |
| Germany                | 20        | 8.7%    |
| Greece                 | 15        | 6.52%   |
| UK                     | 14        | 6.09%   |
| France                 | 12        | 5.22%   |
| Poland                 | 11        | 4.78%   |
| Italy                  | 10        | 4.35%   |
| Australia              | 10        | 4.35%   |
| Russia                 | 8         | 3.48%   |
| Canada                 | 8         | 3.48%   |
| Brazil                 | 7         | 3.04%   |
| Spain                  | 5         | 2.17%   |
| India                  | 4         | 1.74%   |
| Turkey                 | 3         | 1.3%    |
| Sweden                 | 3         | 1.3%    |
| Serbia                 | 3         | 1.3%    |
| Netherlands            | 3         | 1.3%    |
| Mexico                 | 3         | 1.3%    |
| Japan                  | 3         | 1.3%    |
| Algeria                | 3         | 1.3%    |
| Venezuela              | 2         | 0.87%   |
| Singapore              | 2         | 0.87%   |
| Romania                | 2         | 0.87%   |
| Portugal               | 2         | 0.87%   |
| New Zealand            | 2         | 0.87%   |
| Indonesia              | 2         | 0.87%   |
| Egypt                  | 2         | 0.87%   |
| Bosnia and Herzegovina | 2         | 0.87%   |
| Austria                | 2         | 0.87%   |
| Thailand               | 1         | 0.43%   |
| South Korea            | 1         | 0.43%   |
| South Africa           | 1         | 0.43%   |
| Slovakia               | 1         | 0.43%   |
| Norway                 | 1         | 0.43%   |
| Nigeria                | 1         | 0.43%   |
| Lithuania              | 1         | 0.43%   |
| Kazakhstan             | 1         | 0.43%   |
| Israel                 | 1         | 0.43%   |
| Ireland                | 1         | 0.43%   |
| Hungary                | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Athens         | 11        | 4.7%    |
| Melbourne      | 5         | 2.14%   |
| Sydney         | 4         | 1.71%   |
| Paris          | 4         | 1.71%   |
| Warsaw         | 3         | 1.28%   |
| Seattle        | 3         | 1.28%   |
| Otwock         | 3         | 1.28%   |
| Wandsworth     | 2         | 0.85%   |
| Vranje         | 2         | 0.85%   |
| Stuttgart      | 2         | 0.85%   |
| Singapore      | 2         | 0.85%   |
| Santa Clara    | 2         | 0.85%   |
| Salamina       | 2         | 0.85%   |
| Rio de Janeiro | 2         | 0.85%   |
| Ravensburg     | 2         | 0.85%   |
| Moscow         | 2         | 0.85%   |
| Milan          | 2         | 0.85%   |
| London         | 2         | 0.85%   |
| Le Haillan     | 2         | 0.85%   |
| Hamburg        | 2         | 0.85%   |
| Cazin          | 2         | 0.85%   |
| Cairo          | 2         | 0.85%   |
| Bengaluru      | 2         | 0.85%   |
| Belo Horizonte | 2         | 0.85%   |
| Auckland       | 2         | 0.85%   |
| Zaragoza       | 1         | 0.43%   |
| Yokohama       | 1         | 0.43%   |
| Yeovil         | 1         | 0.43%   |
| Yekaterinburg  | 1         | 0.43%   |
| Woodbridge     | 1         | 0.43%   |
| Wonju          | 1         | 0.43%   |
| Winston-Salem  | 1         | 0.43%   |
| Willoughby     | 1         | 0.43%   |
| Westminster    | 1         | 0.43%   |
| Vitebsk        | 1         | 0.43%   |
| Villeurbanne   | 1         | 0.43%   |
| Vigia          | 1         | 0.43%   |
| Vienna         | 1         | 0.43%   |
| Vallentuna     | 1         | 0.43%   |
| Uslar          | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 39        | 53     | 12.58%  |
| WDC                          | 37        | 46     | 11.94%  |
| Seagate                      | 27        | 32     | 8.71%   |
| SanDisk                      | 19        | 20     | 6.13%   |
| Unknown                      | 15        | 16     | 4.84%   |
| Toshiba                      | 15        | 15     | 4.84%   |
| Kingston                     | 14        | 15     | 4.52%   |
| Crucial                      | 13        | 25     | 4.19%   |
| SK hynix                     | 11        | 11     | 3.55%   |
| China                        | 9         | 13     | 2.9%    |
| Micron Technology            | 8         | 9      | 2.58%   |
| Intel                        | 8         | 9      | 2.58%   |
| Hitachi                      | 8         | 9      | 2.58%   |
| Unknown                      | 7         | 7      | 2.26%   |
| KIOXIA                       | 6         | 7      | 1.94%   |
| A-DATA Technology            | 6         | 7      | 1.94%   |
| SPCC                         | 5         | 5      | 1.61%   |
| PNY                          | 4         | 4      | 1.29%   |
| HGST                         | 4         | 4      | 1.29%   |
| Apple                        | 4         | 4      | 1.29%   |
| Apacer                       | 4         | 4      | 1.29%   |
| Team                         | 3         | 3      | 0.97%   |
| Netac                        | 3         | 4      | 0.97%   |
| LITEONIT                     | 3         | 3      | 0.97%   |
| Kingston Technology Company  | 3         | 3      | 0.97%   |
| Intenso                      | 3         | 3      | 0.97%   |
| Fujitsu                      | 3         | 3      | 0.97%   |
| Patriot                      | 2         | 2      | 0.65%   |
| X12                          | 1         | 1      | 0.32%   |
| WALRAM                       | 1         | 1      | 0.32%   |
| UMIS                         | 1         | 1      | 0.32%   |
| Timetec                      | 1         | 1      | 0.32%   |
| Space ke                     | 1         | 2      | 0.32%   |
| Silicon Motion               | 1         | 1      | 0.32%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.32%   |
| SABRENT                      | 1         | 3      | 0.32%   |
| Realtek Semiconductor        | 1         | 1      | 0.32%   |
| Realtek                      | 1         | 1      | 0.32%   |
| Plextor                      | 1         | 1      | 0.32%   |
| Phison Electronics           | 1         | 1      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 7         | 2.08%   |
| SanDisk NVMe SSD Drive 512GB     | 5         | 1.49%   |
| Toshiba MQ01ABF050 500GB         | 4         | 1.19%   |
| Samsung SSD 980 500GB            | 4         | 1.19%   |
| Samsung SSD 860 EVO 250GB        | 4         | 1.19%   |
| Toshiba HDWD120 2TB              | 3         | 0.89%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 2         | 0.6%    |
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 0.6%    |
| WDC WD5000AAKX-00ERMA0 500GB     | 2         | 0.6%    |
| WDC WD10EZEX-60WN4A0 1TB         | 2         | 0.6%    |
| WDC WD10EZEX-00BN5A0 1TB         | 2         | 0.6%    |
| Unknown SD/MMC/MS PRO 128GB      | 2         | 0.6%    |
| SK hynix HCG8e  64GB             | 2         | 0.6%    |
| Seagate ST500LT012-1DG142 500GB  | 2         | 0.6%    |
| Seagate ST500DM002-1BD142 500GB  | 2         | 0.6%    |
| Seagate ST320LT012-9WS14C 320GB  | 2         | 0.6%    |
| Seagate ST1000LM035-1RK172 1TB   | 2         | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB   | 2         | 0.6%    |
| SanDisk NVMe SSD Drive 2TB       | 2         | 0.6%    |
| SanDisk NVMe SSD Drive 1TB       | 2         | 0.6%    |
| Samsung SSD 870 EVO 250GB        | 2         | 0.6%    |
| Samsung SSD 860 EVO 1TB          | 2         | 0.6%    |
| Samsung MZVLB256HBHQ-000L2 256GB | 2         | 0.6%    |
| Patriot P210 256GB SSD           | 2         | 0.6%    |
| Micron MTFDKCD512TFK 512GB       | 2         | 0.6%    |
| KIOXIA KBG40ZNS512G NVMe 512GB   | 2         | 0.6%    |
| Kingston SA400S37480G 480GB SSD  | 2         | 0.6%    |
| Kingston SA400S37240G 240GB SSD  | 2         | 0.6%    |
| Intel SSDPEKNW010T8 1TB          | 2         | 0.6%    |
| Intel SSDPEKNU512GZ 512GB        | 2         | 0.6%    |
| HGST HTS545050A7E680 500GB       | 2         | 0.6%    |
| Crucial CT2000MX500SSD1 2TB      | 2         | 0.6%    |
| Crucial CT1000MX500SSD1 1TB      | 2         | 0.6%    |
| China SSD 512GB                  | 2         | 0.6%    |
| China SSD 256GB                  | 2         | 0.6%    |
| China SSD 240GB                  | 2         | 0.6%    |
| Apacer AS350 128GB SSD           | 2         | 0.6%    |
| A-DATA SU650 120GB SSD           | 2         | 0.6%    |
| X12 SSD 480GB                    | 1         | 0.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD | 1         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 27        | 31     | 31.76%  |
| WDC                 | 23        | 31     | 27.06%  |
| Toshiba             | 13        | 13     | 15.29%  |
| Hitachi             | 8         | 9      | 9.41%   |
| HGST                | 4         | 4      | 4.71%   |
| Fujitsu             | 3         | 3      | 3.53%   |
| Unknown             | 2         | 2      | 2.35%   |
| Space ke            | 1         | 2      | 1.18%   |
| Samsung Electronics | 1         | 1      | 1.18%   |
| SABRENT             | 1         | 3      | 1.18%   |
| Hewlett-Packard     | 1         | 5      | 1.18%   |
| Apple               | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 23        | 30     | 20.91%  |
| Kingston            | 10        | 11     | 9.09%   |
| China               | 9         | 13     | 8.18%   |
| Crucial             | 8         | 20     | 7.27%   |
| WDC                 | 7         | 7      | 6.36%   |
| A-DATA Technology   | 6         | 7      | 5.45%   |
| SanDisk             | 5         | 5      | 4.55%   |
| PNY                 | 4         | 4      | 3.64%   |
| SPCC                | 3         | 3      | 2.73%   |
| Micron Technology   | 3         | 4      | 2.73%   |
| LITEONIT            | 3         | 3      | 2.73%   |
| Intenso             | 3         | 3      | 2.73%   |
| Patriot             | 2         | 2      | 1.82%   |
| Netac               | 2         | 2      | 1.82%   |
| Apple               | 2         | 2      | 1.82%   |
| Apacer              | 2         | 2      | 1.82%   |
| X12                 | 1         | 1      | 0.91%   |
| WALRAM              | 1         | 1      | 0.91%   |
| Unknown             | 1         | 1      | 0.91%   |
| Team                | 1         | 1      | 0.91%   |
| Seagate             | 1         | 1      | 0.91%   |
| Plextor             | 1         | 1      | 0.91%   |
| Mushkin             | 1         | 1      | 0.91%   |
| LITEON              | 1         | 1      | 0.91%   |
| Intel               | 1         | 1      | 0.91%   |
| HS-SSD-C100         | 1         | 1      | 0.91%   |
| Gigabyte Technology | 1         | 1      | 0.91%   |
| GeIL                | 1         | 1      | 0.91%   |
| FORESEE             | 1         | 1      | 0.91%   |
| Fanxiang            | 1         | 1      | 0.91%   |
| Emtec               | 1         | 1      | 0.91%   |
| Corsair             | 1         | 1      | 0.91%   |
| CF400               | 1         | 1      | 0.91%   |
| ASMT109x            | 1         | 1      | 0.91%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 95        | 136    | 33.69%  |
| NVMe | 89        | 105    | 31.56%  |
| HDD  | 77        | 105    | 27.3%   |
| MMC  | 21        | 24     | 7.45%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 143       | 230    | 54.79%  |
| NVMe | 88        | 104    | 33.72%  |
| MMC  | 21        | 24     | 8.05%   |
| SAS  | 9         | 12     | 3.45%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 110       | 138    | 61.45%  |
| 0.51-1.0   | 44        | 68     | 24.58%  |
| 1.01-2.0   | 18        | 24     | 10.06%  |
| 2.01-3.0   | 3         | 4      | 1.68%   |
| 3.01-4.0   | 2         | 3      | 1.12%   |
| 4.01-10.0  | 2         | 4      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 62        | 26.72%  |
| 251-500        | 41        | 17.67%  |
| 1-20           | 34        | 14.66%  |
| 501-1000       | 28        | 12.07%  |
| 51-100         | 22        | 9.48%   |
| 21-50          | 16        | 6.9%    |
| 1001-2000      | 13        | 5.6%    |
| More than 3000 | 9         | 3.88%   |
| 2001-3000      | 7         | 3.02%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 111       | 48.05%  |
| 21-50          | 43        | 18.61%  |
| 101-250        | 27        | 11.69%  |
| 51-100         | 21        | 9.09%   |
| 1001-2000      | 9         | 3.9%    |
| 251-500        | 8         | 3.46%   |
| 501-1000       | 5         | 2.16%   |
| More than 3000 | 4         | 1.73%   |
| 2001-3000      | 3         | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                             | Computers | Drives | Percent |
|---------------------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB                          | 2         | 2      | 5.41%   |
| HGST HTS545050A7E680 500GB                        | 2         | 2      | 5.41%   |
| WDC WD5000LPVX-22V0TT0 500GB                      | 1         | 1      | 2.7%    |
| WDC WD40EZRX-00SPEB0 4TB                          | 1         | 1      | 2.7%    |
| WDC WD2500AAJS-00B4A0 250GB                       | 1         | 2      | 2.7%    |
| WDC WD1600BEKT-75PVMT0 160GB                      | 1         | 1      | 2.7%    |
| WDC WD10EARS-00Y5B1 1TB                           | 1         | 1      | 2.7%    |
| WDC WD Green 2.5 240GB                            | 1         | 1      | 2.7%    |
| Toshiba DT01ACA050 500GB                          | 1         | 1      | 2.7%    |
| Seagate ST9500325AS 500GB                         | 1         | 1      | 2.7%    |
| Seagate ST9320423AS 320GB                         | 1         | 1      | 2.7%    |
| Seagate ST500DM002-1BD142 500GB                   | 1         | 1      | 2.7%    |
| Seagate ST500DM002-1BC142 500GB                   | 1         | 1      | 2.7%    |
| Seagate ST320LT012-9WS14C 320GB                   | 1         | 1      | 2.7%    |
| Seagate ST320LT009-9WC142 320GB                   | 1         | 1      | 2.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 1         | 1      | 2.7%    |
| SanDisk SSD PLUS 480GB                            | 1         | 1      | 2.7%    |
| SanDisk SSD PLUS 1000GB                           | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 870 EVO 250GB             | 1         | 2      | 2.7%    |
| Samsung Electronics SSD 850 PRO 512GB             | 1         | 1      | 2.7%    |
| Netac SSD 512GB                                   | 1         | 1      | 2.7%    |
| Netac SSD 240GB                                   | 1         | 1      | 2.7%    |
| Micron Technology MTFDDAK2T0TDL-1AW1ZABHA 2TB SSD | 1         | 1      | 2.7%    |
| LITEONIT L8T-256L6G-HP 256GB SSD                  | 1         | 1      | 2.7%    |
| Kingston SV300S37A120G 120GB SSD                  | 1         | 1      | 2.7%    |
| Intel SSDSC2KF180H6L 180GB                        | 1         | 1      | 2.7%    |
| Hitachi HUA722020ALA331 2TB                       | 1         | 1      | 2.7%    |
| Hitachi HTS545050A7E380 500GB                     | 1         | 1      | 2.7%    |
| Hitachi HTS542525K9SA00 250GB                     | 1         | 1      | 2.7%    |
| Hitachi HTS541080G9AT00 80GB                      | 1         | 1      | 2.7%    |
| Hitachi HDP725025GLA380 250GB                     | 1         | 1      | 2.7%    |
| HGST HTS545050A7E380 500GB                        | 1         | 1      | 2.7%    |
| Fujitsu MHW2120BJ G2 120GB                        | 1         | 1      | 2.7%    |
| Crucial CT1000MX500SSD4 1TB                       | 1         | 11     | 2.7%    |
| A-DATA Technology SU900 256GB SSD                 | 1         | 2      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 19.44%  |
| WDC                 | 5         | 7      | 13.89%  |
| Hitachi             | 5         | 5      | 13.89%  |
| Toshiba             | 3         | 3      | 8.33%   |
| HGST                | 3         | 3      | 8.33%   |
| SanDisk             | 2         | 2      | 5.56%   |
| Samsung Electronics | 2         | 3      | 5.56%   |
| Netac               | 2         | 2      | 5.56%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| LITEONIT            | 1         | 1      | 2.78%   |
| Kingston            | 1         | 1      | 2.78%   |
| Intel               | 1         | 1      | 2.78%   |
| Fujitsu             | 1         | 1      | 2.78%   |
| Crucial             | 1         | 11     | 2.78%   |
| A-DATA Technology   | 1         | 2      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 7      | 30.43%  |
| Hitachi | 5         | 5      | 21.74%  |
| WDC     | 4         | 6      | 17.39%  |
| Toshiba | 3         | 3      | 13.04%  |
| HGST    | 3         | 3      | 13.04%  |
| Fujitsu | 1         | 1      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 22        | 25     | 62.86%  |
| SSD  | 13        | 25     | 37.14%  |

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
| Works    | 179       | 265    | 69.92%  |
| Detected | 42        | 55     | 16.41%  |
| Malfunc  | 35        | 50     | 13.67%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 137       | 49.28%  |
| AMD                          | 41        | 14.75%  |
| SanDisk                      | 19        | 6.83%   |
| Samsung Electronics          | 19        | 6.83%   |
| SK hynix                     | 8         | 2.88%   |
| Nvidia                       | 7         | 2.52%   |
| Kingston Technology Company  | 7         | 2.52%   |
| KIOXIA                       | 6         | 2.16%   |
| Micron/Crucial Technology    | 5         | 1.8%    |
| Micron Technology            | 5         | 1.8%    |
| Silicon Motion               | 4         | 1.44%   |
| Realtek Semiconductor        | 3         | 1.08%   |
| ASMedia Technology           | 3         | 1.08%   |
| Toshiba America Info Systems | 2         | 0.72%   |
| Phison Electronics           | 2         | 0.72%   |
| MAXIO Technology (Hangzhou)  | 2         | 0.72%   |
| Marvell Technology Group     | 2         | 0.72%   |
| Union Memory (Shenzhen)      | 1         | 0.36%   |
| TenaFe                       | 1         | 0.36%   |
| Shenzhen Longsys Electronics | 1         | 0.36%   |
| LSI Logic / Symbios Logic    | 1         | 0.36%   |
| JMicron Technology           | 1         | 0.36%   |
| Hewlett-Packard              | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 28        | 8.95%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 13        | 4.15%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 3.51%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 9         | 2.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 7         | 2.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 7         | 2.24%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 2.24%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 1.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 1.92%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 5         | 1.6%    |
| Nvidia MCP79 AHCI Controller                                                   | 5         | 1.6%    |
| Intel Alder Lake-P SATA AHCI Controller                                        | 5         | 1.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.6%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 4         | 1.28%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 1.28%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 4         | 1.28%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                          | 4         | 1.28%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.28%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 4         | 1.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 1.28%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 4         | 1.28%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 4         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.28%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 3         | 0.96%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 0.96%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                 | 3         | 0.96%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 3         | 0.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.96%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 3         | 0.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 3         | 0.96%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 3         | 0.96%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 0.96%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 3         | 0.96%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 3         | 0.96%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 0.96%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 3         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 0.96%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 3         | 0.96%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 0.96%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 153       | 53.31%  |
| NVMe | 85        | 29.62%  |
| IDE  | 26        | 9.06%   |
| RAID | 23        | 8.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 169       | 74.45%  |
| AMD    | 57        | 25.11%  |
| ARM    | 1         | 0.44%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel 12th Gen Core i5-1235U             | 5         | 2.2%    |
| AMD Ryzen 7 5700U with Radeon Graphics   | 4         | 1.76%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 3         | 1.32%   |
| Intel Core i7-3770 CPU @ 3.40GHz         | 3         | 1.32%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 3         | 1.32%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 3         | 1.32%   |
| Intel Celeron N4020 CPU @ 1.10GHz        | 3         | 1.32%   |
| Intel Atom CPU Z3735F @ 1.33GHz          | 3         | 1.32%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz  | 3         | 1.32%   |
| AMD Ryzen 5 5600H with Radeon Graphics   | 3         | 1.32%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 2         | 0.88%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz       | 2         | 0.88%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 2         | 0.88%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 2         | 0.88%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 2         | 0.88%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 0.88%   |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 2         | 0.88%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz    | 2         | 0.88%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz     | 2         | 0.88%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 2         | 0.88%   |
| Intel Core 2 Duo CPU E7600 @ 3.06GHz     | 2         | 0.88%   |
| Intel Celeron M processor 1.50GHz        | 2         | 0.88%   |
| Intel Celeron J4105 CPU @ 1.50GHz        | 2         | 0.88%   |
| Intel Celeron CPU N3350 @ 1.10GHz        | 2         | 0.88%   |
| Intel Celeron CPU N3050 @ 1.60GHz        | 2         | 0.88%   |
| Intel 12th Gen Core i5-12450H            | 2         | 0.88%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 2         | 0.88%   |
| Intel 11th Gen Core i5-11400 @ 2.60GHz   | 2         | 0.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 2         | 0.88%   |
| AMD Ryzen 7 5825U with Radeon Graphics   | 2         | 0.88%   |
| AMD Ryzen 5 7600 6-Core Processor        | 2         | 0.88%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 2         | 0.88%   |
| AMD Ryzen 5 2600 Six-Core Processor      | 2         | 0.88%   |
| AMD FX-6300 Six-Core Processor           | 2         | 0.88%   |
| Intel Xeon CPU X5650 @ 2.67GHz           | 1         | 0.44%   |
| Intel Xeon CPU E5320 @ 1.86GHz           | 1         | 0.44%   |
| Intel Pentium Silver N6000 @ 1.10GHz     | 1         | 0.44%   |
| Intel Pentium M processor 1.60GHz        | 1         | 0.44%   |
| Intel Pentium Dual CPU E2140 @ 1.60GHz   | 1         | 0.44%   |
| Intel Pentium CPU N3710 @ 1.60GHz        | 1         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 41        | 18.06%  |
| Other                | 32        | 14.1%   |
| Intel Core i7        | 30        | 13.22%  |
| Intel Celeron        | 19        | 8.37%   |
| AMD Ryzen 5          | 19        | 8.37%   |
| Intel Core 2 Duo     | 14        | 6.17%   |
| AMD Ryzen 7          | 13        | 5.73%   |
| Intel Core i3        | 8         | 3.52%   |
| Intel Atom           | 8         | 3.52%   |
| Intel Pentium        | 5         | 2.2%    |
| AMD Ryzen 3          | 5         | 2.2%    |
| Intel Pentium Silver | 3         | 1.32%   |
| AMD FX               | 3         | 1.32%   |
| Intel Xeon           | 2         | 0.88%   |
| Intel Genuine        | 2         | 0.88%   |
| Intel Core 2 Quad    | 2         | 0.88%   |
| Intel Core 2         | 2         | 0.88%   |
| Intel Celeron M      | 2         | 0.88%   |
| AMD Ryzen 9          | 2         | 0.88%   |
| AMD A8               | 2         | 0.88%   |
| AMD A6               | 2         | 0.88%   |
| Intel Pentium M      | 1         | 0.44%   |
| Intel Pentium Dual   | 1         | 0.44%   |
| Intel Pentium 4      | 1         | 0.44%   |
| AMD Turion Neo X2    | 1         | 0.44%   |
| AMD Turion 64 X2     | 1         | 0.44%   |
| AMD Ryzen 3 PRO      | 1         | 0.44%   |
| AMD Opteron          | 1         | 0.44%   |
| AMD Athlon X4        | 1         | 0.44%   |
| AMD Athlon II X2     | 1         | 0.44%   |
| AMD A4               | 1         | 0.44%   |
| AMD A10              | 1         | 0.44%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 81        | 35.68%  |
| 4       | 72        | 31.72%  |
| 6       | 34        | 14.98%  |
| 8       | 19        | 8.37%   |
| 10      | 8         | 3.52%   |
| 1       | 6         | 2.64%   |
| 14      | 2         | 0.88%   |
| 12      | 2         | 0.88%   |
| 3       | 2         | 0.88%   |
| Unknown | 1         | 0.44%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 226       | 99.56%  |
| Unknown | 1         | 0.44%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 141       | 62.11%  |
| 1       | 85        | 37.44%  |
| Unknown | 1         | 0.44%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 223       | 98.24%  |
| 32-bit         | 4         | 1.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 64        | 28.07%  |
| 0x306a9    | 12        | 5.26%   |
| 0x206a7    | 12        | 5.26%   |
| 0x1067a    | 9         | 3.95%   |
| 0x30678    | 7         | 3.07%   |
| 0x806ec    | 6         | 2.63%   |
| 0x306c3    | 6         | 2.63%   |
| 0x0a50000c | 6         | 2.63%   |
| 0x706a1    | 5         | 2.19%   |
| 0x906a4    | 4         | 1.75%   |
| 0x406c4    | 4         | 1.75%   |
| 0x08608103 | 4         | 1.75%   |
| 0x906ea    | 3         | 1.32%   |
| 0x806ea    | 3         | 1.32%   |
| 0x6fb      | 3         | 1.32%   |
| 0x6d8      | 3         | 1.32%   |
| 0x506e3    | 3         | 1.32%   |
| 0x506c9    | 3         | 1.32%   |
| 0x20655    | 3         | 1.32%   |
| 0x0a601206 | 3         | 1.32%   |
| 0xb06a3    | 2         | 0.88%   |
| 0x906e9    | 2         | 0.88%   |
| 0x906a3    | 2         | 0.88%   |
| 0x806c2    | 2         | 0.88%   |
| 0x706a8    | 2         | 0.88%   |
| 0x6fd      | 2         | 0.88%   |
| 0x406c3    | 2         | 0.88%   |
| 0x40651    | 2         | 0.88%   |
| 0x306d4    | 2         | 0.88%   |
| 0x0a50000d | 2         | 0.88%   |
| 0x0a404105 | 2         | 0.88%   |
| 0x08108109 | 2         | 0.88%   |
| 0x06006704 | 2         | 0.88%   |
| 0x0600611a | 2         | 0.88%   |
| 0xa0671    | 1         | 0.44%   |
| 0xa0655    | 1         | 0.44%   |
| 0x906ed    | 1         | 0.44%   |
| 0x906eb    | 1         | 0.44%   |
| 0x806e9    | 1         | 0.44%   |
| 0x806c1    | 1         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 26        | 11.45%  |
| Unknown          | 19        | 8.37%   |
| IvyBridge        | 18        | 7.93%   |
| Alderlake Hybrid | 17        | 7.49%   |
| Silvermont       | 14        | 6.17%   |
| SandyBridge      | 13        | 5.73%   |
| Zen 3            | 12        | 5.29%   |
| Penryn           | 11        | 4.85%   |
| Haswell          | 10        | 4.41%   |
| Goldmont plus    | 10        | 4.41%   |
| Core             | 10        | 4.41%   |
| TigerLake        | 8         | 3.52%   |
| Skylake          | 8         | 3.52%   |
| Zen+             | 5         | 2.2%    |
| Zen 2            | 5         | 2.2%    |
| Westmere         | 5         | 2.2%    |
| Excavator        | 5         | 2.2%    |
| Piledriver       | 4         | 1.76%   |
| P6               | 4         | 1.76%   |
| Icelake          | 3         | 1.32%   |
| Goldmont         | 3         | 1.32%   |
| CometLake        | 3         | 1.32%   |
| K8 Hammer        | 2         | 0.88%   |
| Broadwell        | 2         | 0.88%   |
| Zen              | 1         | 0.44%   |
| Tremont          | 1         | 0.44%   |
| Steamroller      | 1         | 0.44%   |
| Puma             | 1         | 0.44%   |
| NetBurst         | 1         | 0.44%   |
| K10 Llano        | 1         | 0.44%   |
| K10              | 1         | 0.44%   |
| Jaguar           | 1         | 0.44%   |
| Bulldozer        | 1         | 0.44%   |
| Bonnell          | 1         | 0.44%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 138       | 53.28%  |
| Nvidia | 62        | 23.94%  |
| AMD    | 59        | 22.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 4.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4.14%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 8         | 3.01%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 3.01%   |
| AMD Lucienne                                                                             | 7         | 2.63%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.26%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 2.26%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 1.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.5%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 1.5%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.5%    |
| AMD Barcelo                                                                              | 4         | 1.5%    |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 3         | 1.13%   |
| Nvidia C79 [GeForce 9400M]                                                               | 3         | 1.13%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 1.13%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 3         | 1.13%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 1.13%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.13%   |
| Intel Alder Lake-UP3 GT2 [UHD Graphics]                                                  | 3         | 1.13%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 3         | 1.13%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 1.13%   |
| AMD RV610/M74 [Mobility Radeon HD 2400 XT]                                               | 3         | 1.13%   |
| AMD Rembrandt [Radeon 680M]                                                              | 3         | 1.13%   |
| AMD Raphael                                                                              | 3         | 1.13%   |
| Nvidia TU106 [GeForce RTX 2070 Rev. A]                                                   | 2         | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 2         | 0.75%   |
| Nvidia GK110 [GeForce GTX 780]                                                           | 2         | 0.75%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 2         | 0.75%   |
| Nvidia GA104 [GeForce RTX 3070]                                                          | 2         | 0.75%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 2         | 0.75%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 2         | 0.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.75%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                                | 2         | 0.75%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.75%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 99        | 43.42%  |
| 1 x AMD        | 47        | 20.61%  |
| 1 x Nvidia     | 35        | 15.35%  |
| Intel + Nvidia | 21        | 9.21%   |
| 2 x Intel      | 10        | 4.39%   |
| Intel + AMD    | 7         | 3.07%   |
| AMD + Nvidia   | 4         | 1.75%   |
| 2 x Nvidia     | 2         | 0.88%   |
| 2 x AMD        | 2         | 0.88%   |
| Other          | 1         | 0.44%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 201       | 88.55%  |
| Proprietary | 22        | 9.69%   |
| Unknown     | 4         | 1.76%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 138       | 60.26%  |
| 0.01-0.5   | 41        | 17.9%   |
| 1.01-2.0   | 18        | 7.86%   |
| 0.51-1.0   | 11        | 4.8%    |
| 7.01-8.0   | 7         | 3.06%   |
| 3.01-4.0   | 6         | 2.62%   |
| 2.01-3.0   | 4         | 1.75%   |
| 5.01-6.0   | 2         | 0.87%   |
| 4.01-5.0   | 1         | 0.44%   |
| 8.01-16.0  | 1         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 32        | 13.06%  |
| Samsung Electronics     | 31        | 12.65%  |
| BOE                     | 23        | 9.39%   |
| Chimei Innolux          | 18        | 7.35%   |
| LG Display              | 15        | 6.12%   |
| Apple                   | 13        | 5.31%   |
| Goldstar                | 11        | 4.49%   |
| Dell                    | 9         | 3.67%   |
| Hewlett-Packard         | 7         | 2.86%   |
| Chi Mei Optoelectronics | 7         | 2.86%   |
| Acer                    | 7         | 2.86%   |
| Sharp                   | 6         | 2.45%   |
| AOC                     | 6         | 2.45%   |
| Philips                 | 5         | 2.04%   |
| Lenovo                  | 5         | 2.04%   |
| InfoVision              | 5         | 2.04%   |
| ViewSonic               | 4         | 1.63%   |
| BenQ                    | 4         | 1.63%   |
| Ancor Communications    | 4         | 1.63%   |
| Sony                    | 2         | 0.82%   |
| LG Philips              | 2         | 0.82%   |
| CHD                     | 2         | 0.82%   |
| ASUSTek Computer        | 2         | 0.82%   |
| Yeyian                  | 1         | 0.41%   |
| Vizio                   | 1         | 0.41%   |
| Unknown (XXX)           | 1         | 0.41%   |
| Unknown (ADE)           | 1         | 0.41%   |
| Toshiba                 | 1         | 0.41%   |
| SKG                     | 1         | 0.41%   |
| SGT                     | 1         | 0.41%   |
| Sceptre Tech            | 1         | 0.41%   |
| Quanta Display          | 1         | 0.41%   |
| PANDA                   | 1         | 0.41%   |
| Panasonic               | 1         | 0.41%   |
| Packard Bell            | 1         | 0.41%   |
| NECCI                   | 1         | 0.41%   |
| MVM                     | 1         | 0.41%   |
| Mi                      | 1         | 0.41%   |
| LG Electronics          | 1         | 0.41%   |
| JRY                     | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 3         | 1.2%    |
| Apple Color LCD APP9C6B 1680x1050 433x270mm 20.1-inch                    | 3         | 1.2%    |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.8%    |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.8%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch    | 2         | 0.8%    |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 2         | 0.8%    |
| LG Display LCD Monitor LGD0709 1920x1080 344x194mm 15.5-inch             | 2         | 0.8%    |
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                         | 2         | 0.8%    |
| Dell U2311H DELA05F 1920x1080 510x290mm 23.1-inch                        | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.8%    |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 2         | 0.8%    |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 2         | 0.8%    |
| BOE LCD Monitor BOE08C2 1920x1080 344x194mm 15.5-inch                    | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 2         | 0.8%    |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                         | 2         | 0.8%    |
| AOC 24B2W1 AOC2402 1920x1080 527x296mm 23.8-inch                         | 2         | 0.8%    |
| Acer KA220HQ ACR0467 1920x1080 477x268mm 21.5-inch                       | 2         | 0.8%    |
| Yeyian YMG-4K27-01 YEY2700 3840x2160 600x330mm 27.0-inch                 | 1         | 0.4%    |
| Vizio E500i-A1 VIZ1004 1920x1080 1095x616mm 49.5-inch                    | 1         | 0.4%    |
| ViewSonic VX3276-UHD VSC5138 3840x2160 700x390mm 31.5-inch               | 1         | 0.4%    |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch            | 1         | 0.4%    |
| ViewSonic VP2780 SERIES VSC9C30 3840x2160 597x336mm 27.0-inch            | 1         | 0.4%    |
| ViewSonic VG2228 SERIES VSCEE29 1920x1080 477x268mm 21.5-inch            | 1         | 0.4%    |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1209x680mm 54.6-inch           | 1         | 0.4%    |
| Unknown (ADE) TSLED22D ADEB22D 1920x1080 477x268mm 21.5-inch             | 1         | 0.4%    |
| Toshiba TV TSB0206 1920x1080                                             | 1         | 0.4%    |
| Sony TV SNY3002 1920x1080 531x299mm 24.0-inch                            | 1         | 0.4%    |
| Sony TV SNY2C02 1920x1080 886x498mm 40.0-inch                            | 1         | 0.4%    |
| SKG AF24H1 SKG2409 1920x1080 530x300mm 24.0-inch                         | 1         | 0.4%    |
| Sharp LQ133M1JW01 SHP141B 1920x1080 294x165mm 13.3-inch                  | 1         | 0.4%    |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                  | 1         | 0.4%    |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch                  | 1         | 0.4%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 1         | 0.4%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 1         | 0.4%    |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 1         | 0.4%    |
| SGT F156P1 SGT1600 1920x1080 345x194mm 15.6-inch                         | 1         | 0.4%    |
| Sceptre Tech Sceptre F24 SPT09AB 1920x1080 530x290mm 23.8-inch           | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0609 1920x1080 510x290mm 23.1-inch     | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM0117 1280x1024 312x234mm 15.4-inch     | 1         | 0.4%    |
| Samsung Electronics SMS19A100 SAM0867 1366x768 410x230mm 18.5-inch       | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 108       | 45.19%  |
| 1366x768 (WXGA)    | 56        | 23.43%  |
| 3840x2160 (4K)     | 14        | 5.86%   |
| 2560x1440 (QHD)    | 12        | 5.02%   |
| 1280x800 (WXGA)    | 11        | 4.6%    |
| 1920x1200 (WUXGA)  | 10        | 4.18%   |
| 1440x900 (WXGA+)   | 6         | 2.51%   |
| 1600x900 (HD+)     | 5         | 2.09%   |
| 1680x1050 (WSXGA+) | 4         | 1.67%   |
| 1280x1024 (SXGA)   | 3         | 1.26%   |
| 3840x2400          | 2         | 0.84%   |
| 3440x1440          | 1         | 0.42%   |
| 3200x1800 (QHD+)   | 1         | 0.42%   |
| 3072x1920          | 1         | 0.42%   |
| 2560x1600          | 1         | 0.42%   |
| 2560x1080          | 1         | 0.42%   |
| 1360x768           | 1         | 0.42%   |
| 1024x768 (XGA)     | 1         | 0.42%   |
| Unknown            | 1         | 0.42%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 67        | 27.13%  |
| 13      | 22        | 8.91%   |
| 21      | 18        | 7.29%   |
| 14      | 17        | 6.88%   |
| 27      | 16        | 6.48%   |
| 23      | 15        | 6.07%   |
| 24      | 13        | 5.26%   |
| 18      | 11        | 4.45%   |
| 17      | 11        | 4.45%   |
| 16      | 10        | 4.05%   |
| 11      | 9         | 3.64%   |
| 31      | 7         | 2.83%   |
| 54      | 5         | 2.02%   |
| 20      | 5         | 2.02%   |
| 12      | 4         | 1.62%   |
| 19      | 3         | 1.21%   |
| 34      | 2         | 0.81%   |
| 84      | 1         | 0.4%    |
| 74      | 1         | 0.4%    |
| 65      | 1         | 0.4%    |
| 61      | 1         | 0.4%    |
| 55      | 1         | 0.4%    |
| 49      | 1         | 0.4%    |
| 46      | 1         | 0.4%    |
| 39      | 1         | 0.4%    |
| 32      | 1         | 0.4%    |
| 28      | 1         | 0.4%    |
| 25      | 1         | 0.4%    |
| Unknown | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 97        | 40.08%  |
| 501-600     | 40        | 16.53%  |
| 401-500     | 36        | 14.88%  |
| 201-300     | 28        | 11.57%  |
| 351-400     | 15        | 6.2%    |
| 1001-1500   | 10        | 4.13%   |
| 601-700     | 9         | 3.72%   |
| 701-800     | 3         | 1.24%   |
| 1501-2000   | 2         | 0.83%   |
| 801-900     | 1         | 0.41%   |
| Unknown     | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 178       | 80.54%  |
| 16/10   | 34        | 15.38%  |
| 5/4     | 2         | 0.9%    |
| 4/3     | 2         | 0.9%    |
| 3/2     | 2         | 0.9%    |
| 21/9    | 2         | 0.9%    |
| Unknown | 1         | 0.45%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 27.57%  |
| 201-250        | 33        | 13.58%  |
| 81-90          | 28        | 11.52%  |
| 301-350        | 16        | 6.58%   |
| 151-200        | 15        | 6.17%   |
| 141-150        | 12        | 4.94%   |
| 71-80          | 11        | 4.53%   |
| 351-500        | 11        | 4.53%   |
| More than 1000 | 10        | 4.12%   |
| 51-60          | 9         | 3.7%    |
| 111-120        | 9         | 3.7%    |
| 121-130        | 7         | 2.88%   |
| 251-300        | 5         | 2.06%   |
| 61-70          | 4         | 1.65%   |
| 131-140        | 3         | 1.23%   |
| 501-1000       | 2         | 0.82%   |
| Unknown        | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 73        | 30.67%  |
| 51-100        | 72        | 30.25%  |
| 101-120       | 64        | 26.89%  |
| 161-240       | 15        | 6.3%    |
| 1-50          | 9         | 3.78%   |
| More than 240 | 4         | 1.68%   |
| Unknown       | 1         | 0.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 189       | 82.89%  |
| 2     | 36        | 15.79%  |
| 0     | 3         | 1.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 114       | 31.75%  |
| Intel                           | 92        | 25.63%  |
| Broadcom                        | 37        | 10.31%  |
| Qualcomm Atheros                | 33        | 9.19%   |
| MediaTek                        | 15        | 4.18%   |
| TP-Link                         | 14        | 3.9%    |
| Nvidia                          | 6         | 1.67%   |
| Ralink Technology               | 5         | 1.39%   |
| Marvell Technology Group        | 5         | 1.39%   |
| Broadcom Limited                | 4         | 1.11%   |
| Samsung Electronics             | 3         | 0.84%   |
| Qualcomm Atheros Communications | 3         | 0.84%   |
| OPPO Electronics                | 3         | 0.84%   |
| Xiaomi                          | 2         | 0.56%   |
| Qualcomm                        | 2         | 0.56%   |
| Huawei Technologies             | 2         | 0.56%   |
| D-Link                          | 2         | 0.56%   |
| ASIX Electronics                | 2         | 0.56%   |
| ZyDAS                           | 1         | 0.28%   |
| Tenda                           | 1         | 0.28%   |
| T & A Mobile Phones             | 1         | 0.28%   |
| Sierra Wireless                 | 1         | 0.28%   |
| Ralink                          | 1         | 0.28%   |
| NetGear                         | 1         | 0.28%   |
| Motorola PCS                    | 1         | 0.28%   |
| Microsoft                       | 1         | 0.28%   |
| Linksys                         | 1         | 0.28%   |
| Fujitsu Siemens Computers       | 1         | 0.28%   |
| Edimax Technology               | 1         | 0.28%   |
| DisplayLink                     | 1         | 0.28%   |
| Dell                            | 1         | 0.28%   |
| D-Link System                   | 1         | 0.28%   |
| ASUSTek Computer                | 1         | 0.28%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 73        | 17.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 2.88%   |
| Intel Wi-Fi 6 AX200                                                    | 10        | 2.4%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 7         | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 1.68%   |
| Realtek 802.11ac NIC                                                   | 7         | 1.68%   |
| Intel Wireless 8265 / 8275                                             | 7         | 1.68%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 6         | 1.44%   |
| Intel Ethernet Controller I225-V                                       | 6         | 1.44%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 6         | 1.44%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 5         | 1.2%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.2%    |
| Nvidia MCP79 Ethernet                                                  | 5         | 1.2%    |
| Intel Wireless 7265                                                    | 5         | 1.2%    |
| Intel Wi-Fi 6 AX201                                                    | 5         | 1.2%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 5         | 1.2%    |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 5         | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 5         | 1.2%    |
| Realtek 802.11n WLAN Adapter                                           | 4         | 0.96%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 4         | 0.96%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 4         | 0.96%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 4         | 0.96%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 0.96%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 0.96%   |
| Broadcom BCM4321 802.11a/b/g/n                                         | 4         | 0.96%   |
| Broadcom BCM43142 802.11b/g/n                                          | 4         | 0.96%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 3         | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 3         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.72%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.72%   |
| Ralink MT7601U Wireless Adapter                                        | 3         | 0.72%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 3         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.72%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 0.72%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 3         | 0.72%   |
| Intel Gemini Lake PCH CNVi WiFi                                        | 3         | 0.72%   |
| Intel Ethernet Connection (16) I219-LM                                 | 3         | 0.72%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 32.56%  |
| Realtek Semiconductor           | 39        | 18.14%  |
| Broadcom                        | 30        | 13.95%  |
| Qualcomm Atheros                | 26        | 12.09%  |
| MediaTek                        | 15        | 6.98%   |
| TP-Link                         | 12        | 5.58%   |
| Ralink Technology               | 5         | 2.33%   |
| Qualcomm Atheros Communications | 3         | 1.4%    |
| D-Link                          | 2         | 0.93%   |
| Broadcom Limited                | 2         | 0.93%   |
| ZyDAS                           | 1         | 0.47%   |
| Tenda                           | 1         | 0.47%   |
| Sierra Wireless                 | 1         | 0.47%   |
| Ralink                          | 1         | 0.47%   |
| Qualcomm                        | 1         | 0.47%   |
| NetGear                         | 1         | 0.47%   |
| Microsoft                       | 1         | 0.47%   |
| Linksys                         | 1         | 0.47%   |
| Fujitsu Siemens Computers       | 1         | 0.47%   |
| Edimax Technology               | 1         | 0.47%   |
| ASUSTek Computer                | 1         | 0.47%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 10        | 4.61%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 7         | 3.23%   |
| Realtek 802.11ac NIC                                           | 7         | 3.23%   |
| Intel Wireless 8265 / 8275                                     | 7         | 3.23%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 6         | 2.76%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 6         | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 5         | 2.3%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 5         | 2.3%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.3%    |
| Intel Wireless 7265                                            | 5         | 2.3%    |
| Intel Wi-Fi 6 AX201                                            | 5         | 2.3%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]        | 5         | 2.3%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 2.3%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 5         | 2.3%    |
| Realtek 802.11n WLAN Adapter                                   | 4         | 1.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 1.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.84%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 4         | 1.84%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 1.84%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 3         | 1.38%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.38%   |
| Ralink MT7601U Wireless Adapter                                | 3         | 1.38%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 1.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 1.38%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 3         | 1.38%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 3         | 1.38%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 1.38%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.38%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 2         | 0.92%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller    | 2         | 0.92%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 0.92%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 2         | 0.92%   |
| Ralink RT5572 Wireless Adapter                                 | 2         | 0.92%   |
| Qualcomm Atheros AR9271 802.11n                                | 2         | 0.92%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 2         | 0.92%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 2         | 0.92%   |
| Intel Wireless 8260                                            | 2         | 0.92%   |
| Intel Wireless 7260                                            | 2         | 0.92%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 97        | 49.24%  |
| Intel                    | 48        | 24.37%  |
| Qualcomm Atheros         | 10        | 5.08%   |
| Broadcom                 | 10        | 5.08%   |
| Nvidia                   | 6         | 3.05%   |
| Marvell Technology Group | 5         | 2.54%   |
| Samsung Electronics      | 3         | 1.52%   |
| OPPO Electronics         | 3         | 1.52%   |
| Xiaomi                   | 2         | 1.02%   |
| TP-Link                  | 2         | 1.02%   |
| Huawei Technologies      | 2         | 1.02%   |
| Broadcom Limited         | 2         | 1.02%   |
| ASIX Electronics         | 2         | 1.02%   |
| T & A Mobile Phones      | 1         | 0.51%   |
| Qualcomm                 | 1         | 0.51%   |
| Motorola PCS             | 1         | 0.51%   |
| DisplayLink              | 1         | 0.51%   |
| D-Link System            | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 73        | 37.06%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 12        | 6.09%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 3.55%   |
| Intel Ethernet Controller I225-V                                       | 6         | 3.05%   |
| Nvidia MCP79 Ethernet                                                  | 5         | 2.54%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 5         | 2.54%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                | 4         | 2.03%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 2.03%   |
| Intel Ethernet Connection (2) I219-V                                   | 4         | 2.03%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 1.52%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 1.52%   |
| Intel Ethernet Connection (16) I219-LM                                 | 3         | 1.52%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 1.52%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 1.02%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 1.02%   |
| OPPO SM8350-MTP _SN:9338D66C                                           | 2         | 1.02%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 1.02%   |
| Intel Ethernet Connection I217-LM                                      | 2         | 1.02%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 1.02%   |
| Intel Ethernet Connection (11) I219-LM                                 | 2         | 1.02%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 1.02%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 1.02%   |
| TP-Link USB 10/100 LAN                                                 | 1         | 0.51%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.51%   |
| T & A Mobile Phones TCL 20E                                            | 1         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 1         | 0.51%   |
| Qualcomm SAMSUNG_Android                                               | 1         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 1         | 0.51%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 1         | 0.51%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.51%   |
| OPPO CPH2591                                                           | 1         | 0.51%   |
| Nvidia MCP67 Ethernet                                                  | 1         | 0.51%   |
| Motorola PCS moto g(7) power                                           | 1         | 0.51%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.51%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.51%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.51%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 202       | 52.2%   |
| Ethernet | 183       | 47.29%  |
| Modem    | 2         | 0.52%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 148       | 63.52%  |
| Ethernet | 85        | 36.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 125       | 55.07%  |
| 1     | 89        | 39.21%  |
| 0     | 13        | 5.73%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 160       | 70.18%  |
| Yes  | 68        | 29.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 62        | 37.8%   |
| Realtek Semiconductor           | 16        | 9.76%   |
| Apple                           | 14        | 8.54%   |
| Qualcomm Atheros Communications | 13        | 7.93%   |
| Cambridge Silicon Radio         | 12        | 7.32%   |
| IMC Networks                    | 11        | 6.71%   |
| Broadcom                        | 11        | 6.71%   |
| Foxconn / Hon Hai               | 6         | 3.66%   |
| Dell                            | 5         | 3.05%   |
| Toshiba                         | 3         | 1.83%   |
| MediaTek                        | 3         | 1.83%   |
| Lite-On Technology              | 2         | 1.22%   |
| TP-Link                         | 1         | 0.61%   |
| Edimax Technology               | 1         | 0.61%   |
| Creative Technology             | 1         | 0.61%   |
| ASUSTek Computer                | 1         | 0.61%   |
| Alps Electric                   | 1         | 0.61%   |
| Unknown                         | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 14        | 8.54%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 7.32%   |
| Intel AX201 Bluetooth                               | 11        | 6.71%   |
| Intel Bluetooth wireless interface                  | 9         | 5.49%   |
| Intel AX200 Bluetooth                               | 9         | 5.49%   |
| Intel Bluetooth Device                              | 8         | 4.88%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 4.88%   |
| IMC Networks Wireless_Device                        | 8         | 4.88%   |
| Intel AX211 Bluetooth                               | 7         | 4.27%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 3.66%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 3.05%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 2.44%   |
| Apple Bluetooth Host Controller                     | 4         | 2.44%   |
| Apple Bluetooth HCI                                 | 4         | 2.44%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.83%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.83%   |
| MediaTek Wireless_Device                            | 3         | 1.83%   |
| Intel AX210 Bluetooth                               | 3         | 1.83%   |
| Foxconn / Hon Hai Wireless_Device                   | 3         | 1.83%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.22%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.22%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 1.22%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 1.22%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.22%   |
| TP-Link UB500 Adapter                               | 1         | 0.61%   |
| Toshiba Bluetooth Device                            | 1         | 0.61%   |
| Toshiba BCM43142A0                                  | 1         | 0.61%   |
| Toshiba Askey for                                   | 1         | 0.61%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.61%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.61%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.61%   |
| Intel Wireless-AC 3168 Bluetooth                    | 1         | 0.61%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.61%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.61%   |
| IMC Networks BCM20702A0                             | 1         | 0.61%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.61%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.61%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 1         | 0.61%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.61%   |
| Edimax Edimax Bluetooth Adapter                     | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 153       | 53.13%  |
| AMD                     | 59        | 20.49%  |
| Nvidia                  | 49        | 17.01%  |
| Creative Labs           | 3         | 1.04%   |
| C-Media Electronics     | 3         | 1.04%   |
| Texas Instruments       | 2         | 0.69%   |
| Realtek Semiconductor   | 2         | 0.69%   |
| Logitech                | 2         | 0.69%   |
| Sony                    | 1         | 0.35%   |
| Philips (or NXP)        | 1         | 0.35%   |
| Lenovo                  | 1         | 0.35%   |
| iConnectivity           | 1         | 0.35%   |
| Hewlett-Packard         | 1         | 0.35%   |
| GN Netcom               | 1         | 0.35%   |
| Giga-Byte Technology    | 1         | 0.35%   |
| Focusrite-Novation      | 1         | 0.35%   |
| Emotiva                 | 1         | 0.35%   |
| Corsair                 | 1         | 0.35%   |
| BR25                    | 1         | 0.35%   |
| BEHRINGER International | 1         | 0.35%   |
| ASUSTek Computer        | 1         | 0.35%   |
| AKAI Professional M.I.  | 1         | 0.35%   |
| Actions Semiconductor   | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 31        | 9.17%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 5.33%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 18        | 5.33%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 3.85%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 3.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 10        | 2.96%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 10        | 2.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.37%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 2.37%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.78%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 1.78%   |
| Nvidia MCP79 High Definition Audio                                                                | 5         | 1.48%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.48%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.48%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.48%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.48%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 1.48%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.48%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.18%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.18%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 1.18%   |
| Nvidia Audio device                                                                               | 4         | 1.18%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 4         | 1.18%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.18%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 4         | 1.18%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.18%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.18%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.18%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.18%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.18%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 3         | 0.89%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.89%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.89%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 3         | 0.89%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 0.89%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.89%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 59        | 22.01%  |
| SK hynix                                | 54        | 20.15%  |
| Unknown                                 | 28        | 10.45%  |
| Micron Technology                       | 25        | 9.33%   |
| Kingston                                | 21        | 7.84%   |
| Crucial                                 | 18        | 6.72%   |
| Corsair                                 | 11        | 4.1%    |
| G.Skill                                 | 9         | 3.36%   |
| A-DATA Technology                       | 8         | 2.99%   |
| Unknown (ABCD)                          | 7         | 2.61%   |
| Elpida                                  | 5         | 1.87%   |
| Unknown                                 | 4         | 1.49%   |
| Team                                    | 3         | 1.12%   |
| Ramaxel Technology                      | 3         | 1.12%   |
| Nanya Technology                        | 2         | 0.75%   |
| Timetec                                 | 1         | 0.37%   |
| Smart                                   | 1         | 0.37%   |
| Silicon Power Computer & Communications | 1         | 0.37%   |
| Qumo                                    | 1         | 0.37%   |
| Qimonda                                 | 1         | 0.37%   |
| Netlist                                 | 1         | 0.37%   |
| ff                                      | 1         | 0.37%   |
| CSX                                     | 1         | 0.37%   |
| Apacer                                  | 1         | 0.37%   |
| 4ea5                                    | 1         | 0.37%   |
| 48spaces                                | 1         | 0.37%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 2.12%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 5         | 1.77%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 1.77%   |
| Unknown                                                          | 4         | 1.41%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 1.06%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.06%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 1.06%   |
| Unknown RAM Module 8GB DIMM DDR3 1600MT/s                        | 2         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.71%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 2         | 0.71%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 2         | 0.71%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.71%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1067MT/s                     | 2         | 0.71%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 2         | 0.71%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.71%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.71%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.71%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 2         | 0.71%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.71%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.71%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 2         | 0.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.71%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.71%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.71%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.71%   |
| Samsung RAM M471A1G44CB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 0.71%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 0.71%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s              | 2         | 0.71%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.71%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s        | 2         | 0.71%   |
| Unknown RAM Module 8GB SODIMM DDR4 2400MT/s                      | 1         | 0.35%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 1         | 0.35%   |
| Unknown RAM Module 512MB SODIMM DDR 400MT/s                      | 1         | 0.35%   |
| Unknown RAM Module 512MB SODIMM DDR 100MT/s                      | 1         | 0.35%   |
| Unknown RAM Module 4GB SODIMM DDR3 1067MT/s                      | 1         | 0.35%   |
| Unknown RAM Module 4GB FB-DIMM DDR2 667MT/s                      | 1         | 0.35%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.35%   |
| Unknown RAM Module 2GB SODIMM DDR 800MT/s                        | 1         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 91        | 40.09%  |
| DDR3    | 75        | 33.04%  |
| DDR2    | 14        | 6.17%   |
| LPDDR4  | 12        | 5.29%   |
| DDR5    | 11        | 4.85%   |
| SDRAM   | 6         | 2.64%   |
| LPDDR3  | 6         | 2.64%   |
| LPDDR5  | 4         | 1.76%   |
| DDR     | 4         | 1.76%   |
| Unknown | 4         | 1.76%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 145       | 63.88%  |
| DIMM         | 59        | 25.99%  |
| Row Of Chips | 16        | 7.05%   |
| Unknown      | 4         | 1.76%   |
| Chip         | 2         | 0.88%   |
| FB-DIMM      | 1         | 0.44%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 85        | 36.17%  |
| 4096  | 60        | 25.53%  |
| 16384 | 35        | 14.89%  |
| 2048  | 35        | 14.89%  |
| 1024  | 9         | 3.83%   |
| 32768 | 8         | 3.4%    |
| 512   | 3         | 1.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 48        | 19.28%  |
| 1600    | 44        | 17.67%  |
| 2667    | 24        | 9.64%   |
| 2400    | 18        | 7.23%   |
| 1333    | 18        | 7.23%   |
| 2133    | 9         | 3.61%   |
| 1334    | 8         | 3.21%   |
| 667     | 8         | 3.21%   |
| 4800    | 7         | 2.81%   |
| 1067    | 7         | 2.81%   |
| 800     | 7         | 2.81%   |
| 3600    | 6         | 2.41%   |
| 1867    | 5         | 2.01%   |
| Unknown | 4         | 1.61%   |
| 6400    | 3         | 1.2%    |
| 4267    | 3         | 1.2%    |
| 1066    | 3         | 1.2%    |
| 6000    | 2         | 0.8%    |
| 4199    | 2         | 0.8%    |
| 2933    | 2         | 0.8%    |
| 2048    | 2         | 0.8%    |
| 1866    | 2         | 0.8%    |
| 1800    | 2         | 0.8%    |
| 975     | 2         | 0.8%    |
| 400     | 2         | 0.8%    |
| 7500    | 1         | 0.4%    |
| 5600    | 1         | 0.4%    |
| 5500    | 1         | 0.4%    |
| 4000    | 1         | 0.4%    |
| 3400    | 1         | 0.4%    |
| 3334    | 1         | 0.4%    |
| 3266    | 1         | 0.4%    |
| 3066    | 1         | 0.4%    |
| 2666    | 1         | 0.4%    |
| 533     | 1         | 0.4%    |
| 100     | 1         | 0.4%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 2         | 50%     |
| Dymo-CoStar        | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Computers | Percent |
|-----------------------------|-----------|---------|
| Dymo-CoStar LabelWriter 450 | 1         | 25%     |
| Canon PIXMA MG5600 Series   | 1         | 25%     |
| Canon PIXMA MG2500 Series   | 1         | 25%     |
| Brother HL-L2350DW series   | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500] | 1         | 50%     |
| Canon CanoScan 8800F                  | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 23        | 15.23%  |
| Realtek Semiconductor                  | 15        | 9.93%   |
| Microdia                               | 14        | 9.27%   |
| Apple                                  | 13        | 8.61%   |
| IMC Networks                           | 11        | 7.28%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.96%   |
| Quanta                                 | 8         | 5.3%    |
| Sunplus Innovation Technology          | 5         | 3.31%   |
| Luxvisions Innotech Limited            | 5         | 3.31%   |
| Logitech                               | 5         | 3.31%   |
| Lite-On Technology                     | 5         | 3.31%   |
| Bison Electronics                      | 5         | 3.31%   |
| Syntek                                 | 4         | 2.65%   |
| Suyin                                  | 4         | 2.65%   |
| Alcor Micro                            | 4         | 2.65%   |
| Acer                                   | 4         | 2.65%   |
| Importek                               | 3         | 1.99%   |
| Z-Star Microelectronics                | 2         | 1.32%   |
| Silicon Motion                         | 2         | 1.32%   |
| Ricoh                                  | 2         | 1.32%   |
| SunplusIT                              | 1         | 0.66%   |
| Samsung Electronics                    | 1         | 0.66%   |
| Lenovo                                 | 1         | 0.66%   |
| KYT-230807-A                           | 1         | 0.66%   |
| icSpring                               | 1         | 0.66%   |
| Hewlett-Packard                        | 1         | 0.66%   |
| Aveo Technology                        | 1         | 0.66%   |
| ARC International                      | 1         | 0.66%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Realtek Integrated_Webcam_HD                                               | 9         | 5.96%   |
| Apple Built-in iSight                                                      | 9         | 5.96%   |
| Microdia Integrated_Webcam_HD                                              | 8         | 5.3%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 6         | 3.97%   |
| Lite-On Integrated Camera                                                  | 4         | 2.65%   |
| Chicony Integrated Camera                                                  | 4         | 2.65%   |
| Syntek Integrated Camera                                                   | 3         | 1.99%   |
| Microdia Integrated_Webcam_FHD                                             | 3         | 1.99%   |
| Importek TOSHIBA Web Camera - HD                                           | 3         | 1.99%   |
| IMC Networks Integrated Camera                                             | 3         | 1.99%   |
| Suyin HP Truevision HD                                                     | 2         | 1.32%   |
| Ricoh HD Webcam                                                            | 2         | 1.32%   |
| Realtek Bluetooth Radio                                                    | 2         | 1.32%   |
| Quanta ov9734_techfront_camera                                             | 2         | 1.32%   |
| Quanta ACER HD User Facing                                                 | 2         | 1.32%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 2         | 1.32%   |
| Logitech C922 Pro Stream Webcam                                            | 2         | 1.32%   |
| IMC Networks EasyCamera                                                    | 2         | 1.32%   |
| Chicony USB2.0 Camera                                                      | 2         | 1.32%   |
| Chicony TOSHIBA Web Camera - HD                                            | 2         | 1.32%   |
| Chicony HP Truevision HD                                                   | 2         | 1.32%   |
| Chicony HD WebCam                                                          | 2         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 2         | 1.32%   |
| Bison Integrated RGB Camera                                                | 2         | 1.32%   |
| Apple FaceTime HD Camera (Built-in)                                        | 2         | 1.32%   |
| Alcor Micro USB 2.0 PC Camera                                              | 2         | 1.32%   |
| Acer Front Camera                                                          | 2         | 1.32%   |
| Z-Star Webcam                                                              | 1         | 0.66%   |
| Z-Star Traveler TV 6500 SF Dia-scanner                                     | 1         | 0.66%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.66%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 0.66%   |
| Suyin Asus Integrated Webcam [CN031B]                                      | 1         | 0.66%   |
| SunplusIT 720p HD Camera                                                   | 1         | 0.66%   |
| Sunplus Laptop Integrated Webcam FHD                                       | 1         | 0.66%   |
| Sunplus Integrated_Webcam_HD                                               | 1         | 0.66%   |
| Sunplus Integrated_Webcam_FHD                                              | 1         | 0.66%   |
| Sunplus HP HD Webcam [Fixed]                                               | 1         | 0.66%   |
| Sunplus Asus Webcam                                                        | 1         | 0.66%   |
| Silicon Motion WebCam SCB-1100N                                            | 1         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 30.43%  |
| Validity Sensors           | 6         | 26.09%  |
| Shenzhen Goodix Technology | 5         | 21.74%  |
| Elan Microelectronics      | 2         | 8.7%    |
| Upek                       | 1         | 4.35%   |
| STMicroelectronics         | 1         | 4.35%   |
| AuthenTec                  | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                    | 4         | 17.39%  |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 3         | 13.04%  |
| Validity Sensors Fingerprint scanner                   | 2         | 8.7%    |
| Validity Sensors VFS5011 Fingerprint Reader            | 1         | 4.35%   |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4.35%   |
| Validity Sensors VFS491                                | 1         | 4.35%   |
| Validity Sensors Synaptics WBDI                        | 1         | 4.35%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4.35%   |
| Synaptics WBDI Fingerprint Reader USB 102              | 1         | 4.35%   |
| Synaptics  WBDI                                        | 1         | 4.35%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 4.35%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 4.35%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 4.35%   |
| Shenzhen Goodix FingerPrint                            | 1         | 4.35%   |
| Elan ELAN:Fingerprint                                  | 1         | 4.35%   |
| Elan ELAN:ARM-M4                                       | 1         | 4.35%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Broadcom            | 9         | 64.29%  |
| Alcor Micro         | 3         | 21.43%  |
| O2 Micro            | 1         | 7.14%   |
| Chicony Electronics | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 6         | 42.86%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 21.43%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 14.29%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.14%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 144       | 63.16%  |
| 1     | 68        | 29.82%  |
| 2     | 14        | 6.14%   |
| 3     | 2         | 0.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 28        | 28.57%  |
| Fingerprint reader       | 22        | 22.45%  |
| Net/wireless             | 14        | 14.29%  |
| Chipcard                 | 14        | 14.29%  |
| Camera                   | 8         | 8.16%   |
| Card reader              | 3         | 3.06%   |
| Network                  | 2         | 2.04%   |
| Multimedia controller    | 2         | 2.04%   |
| Wireless                 | 1         | 1.02%   |
| Storage                  | 1         | 1.02%   |
| Flash memory             | 1         | 1.02%   |
| Communication controller | 1         | 1.02%   |
| Bluetooth                | 1         | 1.02%   |

