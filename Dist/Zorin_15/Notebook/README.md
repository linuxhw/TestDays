Zorin 15 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 15.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

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

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | S10-3                       | [19cd43f2f7](https://linux-hardware.org/?probe=19cd43f2f7) | Nov 29, 2021 |
| Dell          | Inspiron 14-3452            | [b0fb64bf16](https://linux-hardware.org/?probe=b0fb64bf16) | Nov 27, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [c23b71e54e](https://linux-hardware.org/?probe=c23b71e54e) | Nov 27, 2021 |
| HP            | Pavilion g7                 | [e8dcea99ad](https://linux-hardware.org/?probe=e8dcea99ad) | Nov 26, 2021 |
| Toshiba       | Satellite L750              | [836cf1ca10](https://linux-hardware.org/?probe=836cf1ca10) | Nov 25, 2021 |
| Toshiba       | Satellite L750              | [827e07a075](https://linux-hardware.org/?probe=827e07a075) | Nov 24, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [b7ebd50e73](https://linux-hardware.org/?probe=b7ebd50e73) | Nov 21, 2021 |
| Fujitsu Si... | AMILO Li1705                | [397611b48d](https://linux-hardware.org/?probe=397611b48d) | Nov 20, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | [d543e2cd80](https://linux-hardware.org/?probe=d543e2cd80) | Nov 19, 2021 |
| HP            | Pavilion dv7                | [33202c35ad](https://linux-hardware.org/?probe=33202c35ad) | Nov 19, 2021 |
| HP            | Pavilion dv7                | [66ec298a1c](https://linux-hardware.org/?probe=66ec298a1c) | Nov 18, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [641218d2e6](https://linux-hardware.org/?probe=641218d2e6) | Nov 16, 2021 |
| HP            | Pavilion dv9500             | [bef50ae82a](https://linux-hardware.org/?probe=bef50ae82a) | Nov 15, 2021 |
| HP            | Compaq nx8220 (PG801ET#A... | [60c7204131](https://linux-hardware.org/?probe=60c7204131) | Nov 14, 2021 |
| Samsung       | 370E4K                      | [f076dae1f9](https://linux-hardware.org/?probe=f076dae1f9) | Nov 12, 2021 |
| Medion        | P8610                       | [122043c04d](https://linux-hardware.org/?probe=122043c04d) | Nov 08, 2021 |
| Medion        | P8610                       | [4d519680a1](https://linux-hardware.org/?probe=4d519680a1) | Nov 07, 2021 |
| ASUSTek       | K42F                        | [a0fc0b335f](https://linux-hardware.org/?probe=a0fc0b335f) | Nov 07, 2021 |
| MAXDATA       | ECO4000IW                   | [5a5fb011c7](https://linux-hardware.org/?probe=5a5fb011c7) | Nov 06, 2021 |
| Apple         | MacBookAir4,1               | [01eb7627e2](https://linux-hardware.org/?probe=01eb7627e2) | Nov 06, 2021 |
| Dell          | XPS M1330                   | [3fcb1bf591](https://linux-hardware.org/?probe=3fcb1bf591) | Nov 06, 2021 |
| Intel         | HURONRIVER                  | [5ded89b4a5](https://linux-hardware.org/?probe=5ded89b4a5) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | [e18dd8b896](https://linux-hardware.org/?probe=e18dd8b896) | Nov 01, 2021 |
| HP            | 255 G5                      | [5614e34f51](https://linux-hardware.org/?probe=5614e34f51) | Oct 28, 2021 |
| Toshiba       | Satellite U400              | [abcf2eee75](https://linux-hardware.org/?probe=abcf2eee75) | Oct 27, 2021 |
| Acer          | Acadia V1.42                | [01122f69f4](https://linux-hardware.org/?probe=01122f69f4) | Oct 23, 2021 |
| Acer          | Acadia V1.42                | [11b24034fc](https://linux-hardware.org/?probe=11b24034fc) | Oct 23, 2021 |
| HP            | 255 G5                      | [02e4b753ca](https://linux-hardware.org/?probe=02e4b753ca) | Oct 22, 2021 |
| HP            | EliteBook 8460p             | [24535d9a4b](https://linux-hardware.org/?probe=24535d9a4b) | Oct 20, 2021 |
| HP            | EliteBook 8460p             | [cf78694aa7](https://linux-hardware.org/?probe=cf78694aa7) | Oct 20, 2021 |
| Dell          | System XPS 15Z              | [751ffeefa0](https://linux-hardware.org/?probe=751ffeefa0) | Oct 20, 2021 |
| HP            | Presario CQ42               | [d82c04d026](https://linux-hardware.org/?probe=d82c04d026) | Oct 19, 2021 |
| Acer          | Aspire ES1-531              | [a7058244ce](https://linux-hardware.org/?probe=a7058244ce) | Oct 16, 2021 |
| Dell          | Inspiron N5010              | [eca5c4cbf7](https://linux-hardware.org/?probe=eca5c4cbf7) | Oct 15, 2021 |
| HP            | Laptop 15-da0xxx            | [3054954ea5](https://linux-hardware.org/?probe=3054954ea5) | Oct 14, 2021 |
| Dell          | Inspiron N5010              | [2495309045](https://linux-hardware.org/?probe=2495309045) | Oct 14, 2021 |
| HP            | Laptop 15-da0xxx            | [dd3b21ba26](https://linux-hardware.org/?probe=dd3b21ba26) | Oct 14, 2021 |
| Dell          | Inspiron N5050              | [1dd1c022a2](https://linux-hardware.org/?probe=1dd1c022a2) | Oct 13, 2021 |
| Dell          | Inspiron N5050              | [8866975539](https://linux-hardware.org/?probe=8866975539) | Oct 13, 2021 |
| American M... | 255/259 Series              | [e8761321aa](https://linux-hardware.org/?probe=e8761321aa) | Oct 13, 2021 |
| Acer          | Aspire E1-572               | [dc154fe7c0](https://linux-hardware.org/?probe=dc154fe7c0) | Oct 13, 2021 |
| ASUSTek       | N61Jv                       | [0e300bafe8](https://linux-hardware.org/?probe=0e300bafe8) | Oct 12, 2021 |
| Toshiba       | Satellite Pro C660          | [14a96b5cec](https://linux-hardware.org/?probe=14a96b5cec) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| HP            | Laptop 15-db0xxx            | [a49c0e5d41](https://linux-hardware.org/?probe=a49c0e5d41) | Oct 08, 2021 |
| Sony          | VPCEA20FB                   | [de4d94232e](https://linux-hardware.org/?probe=de4d94232e) | Oct 07, 2021 |
| Sony          | VPCEA20FB                   | [52e6abba3c](https://linux-hardware.org/?probe=52e6abba3c) | Oct 07, 2021 |
| Matsushita... | CF-19CHB23BE                | [7024487bcd](https://linux-hardware.org/?probe=7024487bcd) | Oct 07, 2021 |
| Acer          | AOD255                      | [79fa37e2d3](https://linux-hardware.org/?probe=79fa37e2d3) | Sep 30, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [4cd46a616f](https://linux-hardware.org/?probe=4cd46a616f) | Sep 29, 2021 |
| Digibras      | NH4CU53                     | [f0615abf72](https://linux-hardware.org/?probe=f0615abf72) | Sep 27, 2021 |
| Toshiba       | Satellite C50-B             | [0914aeed54](https://linux-hardware.org/?probe=0914aeed54) | Sep 25, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1070... | [c77dd4d1b4](https://linux-hardware.org/?probe=c77dd4d1b4) | Sep 23, 2021 |
| Philco        | 14F                         | [093b9632e8](https://linux-hardware.org/?probe=093b9632e8) | Sep 23, 2021 |
| Dell          | Inspiron 6000               | [f48bad44cd](https://linux-hardware.org/?probe=f48bad44cd) | Sep 22, 2021 |
| Dell          | Inspiron 6000               | [9b3cde9b5f](https://linux-hardware.org/?probe=9b3cde9b5f) | Sep 22, 2021 |
| ASUSTek       | UX430UAR                    | [57d695a843](https://linux-hardware.org/?probe=57d695a843) | Sep 21, 2021 |
| HP            | ProBook 4540s               | [ccac6a82ca](https://linux-hardware.org/?probe=ccac6a82ca) | Sep 20, 2021 |
| Fujitsu Si... | AMILO M7440D                | [e23f21b9b4](https://linux-hardware.org/?probe=e23f21b9b4) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | [bce3e66350](https://linux-hardware.org/?probe=bce3e66350) | Sep 19, 2021 |
| Positivo      | Mobile                      | [6f701d72fd](https://linux-hardware.org/?probe=6f701d72fd) | Sep 17, 2021 |
| ASUSTek       | F5SL                        | [e6e93168a6](https://linux-hardware.org/?probe=e6e93168a6) | Sep 15, 2021 |
| Toshiba       | Satellite PRO C850-1H8      | [ea23c035b2](https://linux-hardware.org/?probe=ea23c035b2) | Sep 15, 2021 |
| HP            | EliteBook 6930p             | [8f38de340d](https://linux-hardware.org/?probe=8f38de340d) | Sep 15, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [445f079c6d](https://linux-hardware.org/?probe=445f079c6d) | Sep 15, 2021 |
| Lenovo        | ThinkPad T61 765818U        | [7bae831cdf](https://linux-hardware.org/?probe=7bae831cdf) | Sep 12, 2021 |
| Acer          | Lugano M                    | [5c114a6e41](https://linux-hardware.org/?probe=5c114a6e41) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | [54ddef7aa7](https://linux-hardware.org/?probe=54ddef7aa7) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | [8c00427976](https://linux-hardware.org/?probe=8c00427976) | Sep 11, 2021 |
| Acer          | Aspire 3610                 | [fc6953a3f9](https://linux-hardware.org/?probe=fc6953a3f9) | Sep 10, 2021 |
| HP            | ProBook 6460b               | [b0f0eaf216](https://linux-hardware.org/?probe=b0f0eaf216) | Sep 09, 2021 |
| Acer          | Aspire 3610                 | [4718ed26ca](https://linux-hardware.org/?probe=4718ed26ca) | Sep 08, 2021 |
| Pendo Indu... | PNDFWXUFD11BLK6             | [06d0750e6e](https://linux-hardware.org/?probe=06d0750e6e) | Sep 08, 2021 |
| Acer          | Aspire 3610                 | [3ab0387498](https://linux-hardware.org/?probe=3ab0387498) | Sep 08, 2021 |
| Dell          | Inspiron 1010               | [ee05ebef50](https://linux-hardware.org/?probe=ee05ebef50) | Sep 07, 2021 |
| Dell          | Inspiron 1010               | [8805be4e5c](https://linux-hardware.org/?probe=8805be4e5c) | Sep 07, 2021 |
| Lenovo        | ThinkPad T61 765818U        | [df384e1ab4](https://linux-hardware.org/?probe=df384e1ab4) | Sep 06, 2021 |
| GPD           | MicroPC                     | [d0ffed23be](https://linux-hardware.org/?probe=d0ffed23be) | Sep 05, 2021 |
| Unknown       | T3 MRD                      | [0687d6609d](https://linux-hardware.org/?probe=0687d6609d) | Sep 03, 2021 |
| Dell          | Latitude D630               | [6b4af154d5](https://linux-hardware.org/?probe=6b4af154d5) | Sep 03, 2021 |
| Dell          | Latitude D630               | [84729ea67f](https://linux-hardware.org/?probe=84729ea67f) | Sep 03, 2021 |
| Acer          | Aspire 9410                 | [d6632fcd8b](https://linux-hardware.org/?probe=d6632fcd8b) | Sep 02, 2021 |
| HP            | 530                         | [cc7cc97ae3](https://linux-hardware.org/?probe=cc7cc97ae3) | Aug 31, 2021 |
| HP            | 530                         | [20bf2422fc](https://linux-hardware.org/?probe=20bf2422fc) | Aug 31, 2021 |
| ASUSTek       | X55U                        | [b37f7fdf24](https://linux-hardware.org/?probe=b37f7fdf24) | Aug 30, 2021 |
| Acer          | Aspire 8920                 | [8a006e9280](https://linux-hardware.org/?probe=8a006e9280) | Aug 28, 2021 |
| ASUSTek       | 1001PX                      | [1b8954cf9f](https://linux-hardware.org/?probe=1b8954cf9f) | Aug 27, 2021 |
| Lenovo        | ThinkPad R61e 7650ELU       | [7c29fad093](https://linux-hardware.org/?probe=7c29fad093) | Aug 26, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | [285a023dd8](https://linux-hardware.org/?probe=285a023dd8) | Aug 26, 2021 |
| ASUSTek       | UX430UAR                    | [88f301b39f](https://linux-hardware.org/?probe=88f301b39f) | Aug 26, 2021 |
| HP            | Mini 110-3100               | [2bca9a30ab](https://linux-hardware.org/?probe=2bca9a30ab) | Aug 25, 2021 |
| Dell          | Inspiron 6000               | [fae1a81289](https://linux-hardware.org/?probe=fae1a81289) | Aug 24, 2021 |
| Dell          | Inspiron 6000               | [f4ae3e605a](https://linux-hardware.org/?probe=f4ae3e605a) | Aug 24, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [ab8a4f01d9](https://linux-hardware.org/?probe=ab8a4f01d9) | Aug 22, 2021 |
| Panasonic     | CF-31JEGAX1M                | [c5acecef3a](https://linux-hardware.org/?probe=c5acecef3a) | Aug 22, 2021 |
| HP            | Compaq Presario CQ61        | [c7c1d06954](https://linux-hardware.org/?probe=c7c1d06954) | Aug 21, 2021 |
| Positivo      | Mobile                      | [e4a47e39b6](https://linux-hardware.org/?probe=e4a47e39b6) | Aug 21, 2021 |
| Samsung       | RV419                       | [ba6f454b7d](https://linux-hardware.org/?probe=ba6f454b7d) | Aug 20, 2021 |
| Samsung       | N150                        | [86914b23ac](https://linux-hardware.org/?probe=86914b23ac) | Aug 19, 2021 |
| Positivo      | Q232A                       | [f76d2dc489](https://linux-hardware.org/?probe=f76d2dc489) | Aug 19, 2021 |
| HP            | ProBook 4430s               | [0235e3c344](https://linux-hardware.org/?probe=0235e3c344) | Aug 18, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [5ab0429d85](https://linux-hardware.org/?probe=5ab0429d85) | Aug 17, 2021 |
| HP            | ENVY 17                     | [7c9143912d](https://linux-hardware.org/?probe=7c9143912d) | Aug 17, 2021 |
| ASUSTek       | X441SA                      | [f23d4d50be](https://linux-hardware.org/?probe=f23d4d50be) | Aug 16, 2021 |
| Itautec       | Infoway                     | [f66edac6bd](https://linux-hardware.org/?probe=f66edac6bd) | Aug 16, 2021 |
| Itautec       | Infoway                     | [94c198d530](https://linux-hardware.org/?probe=94c198d530) | Aug 16, 2021 |
| HP            | Pavilion 17                 | [b628f70687](https://linux-hardware.org/?probe=b628f70687) | Aug 15, 2021 |
| SiS           | M672 Board SI94B-20+SI96... | [8268c73ee9](https://linux-hardware.org/?probe=8268c73ee9) | Aug 14, 2021 |
| HP            | Pavilion g7                 | [cf766b8d76](https://linux-hardware.org/?probe=cf766b8d76) | Aug 13, 2021 |
| Quanta        | QL5 TBD                     | [be465dec60](https://linux-hardware.org/?probe=be465dec60) | Aug 13, 2021 |
| Toshiba       | Satellite L505D             | [b7b43a605d](https://linux-hardware.org/?probe=b7b43a605d) | Aug 12, 2021 |
| Toshiba       | Satellite L505D             | [8560337601](https://linux-hardware.org/?probe=8560337601) | Aug 12, 2021 |
| Acer          | Aspire 8920                 | [9ac1d0a471](https://linux-hardware.org/?probe=9ac1d0a471) | Aug 12, 2021 |
| Lenovo        | Z50-70 20354                | [1eba114602](https://linux-hardware.org/?probe=1eba114602) | Aug 11, 2021 |
| Lenovo        | Z50-70 20354                | [528ab497b2](https://linux-hardware.org/?probe=528ab497b2) | Aug 11, 2021 |
| Lenovo        | Z50-70 20354                | [a31c1f0fda](https://linux-hardware.org/?probe=a31c1f0fda) | Aug 11, 2021 |
| HP            | Pavilion dv6700             | [ebf6b956cb](https://linux-hardware.org/?probe=ebf6b956cb) | Aug 10, 2021 |
| Apple         | MacBookPro7,1               | [da4107ffc3](https://linux-hardware.org/?probe=da4107ffc3) | Aug 10, 2021 |
| Samsung       | RV419                       | [66823b7d4d](https://linux-hardware.org/?probe=66823b7d4d) | Aug 10, 2021 |
| ASUSTek       | X51R                        | [1d1aad3900](https://linux-hardware.org/?probe=1d1aad3900) | Aug 08, 2021 |
| Dell          | Inspiron 3521               | [d0814fcb72](https://linux-hardware.org/?probe=d0814fcb72) | Aug 08, 2021 |
| Acer          | Extensa 5220                | [c2e39c0d39](https://linux-hardware.org/?probe=c2e39c0d39) | Aug 07, 2021 |
| HP            | Compaq 2510p                | [ea3c7d2fe2](https://linux-hardware.org/?probe=ea3c7d2fe2) | Aug 07, 2021 |
| HP            | Compaq 2510p                | [31449a4b42](https://linux-hardware.org/?probe=31449a4b42) | Aug 07, 2021 |
| Dell          | Inspiron 3421               | [dc8767625f](https://linux-hardware.org/?probe=dc8767625f) | Aug 07, 2021 |
| Acer          | Extensa 5220                | [b0da636247](https://linux-hardware.org/?probe=b0da636247) | Aug 07, 2021 |
| Dell          | Inspiron 3421               | [52f396865d](https://linux-hardware.org/?probe=52f396865d) | Aug 07, 2021 |
| Positivo      | CHT14B                      | [c8d89d2cde](https://linux-hardware.org/?probe=c8d89d2cde) | Aug 06, 2021 |
| Acer          | Aspire E5-575               | [9d4f584337](https://linux-hardware.org/?probe=9d4f584337) | Aug 06, 2021 |
| Lenovo        | ThinkPad T61 6468AE2        | [58f1efa783](https://linux-hardware.org/?probe=58f1efa783) | Aug 06, 2021 |
| Dell          | Latitude E5500              | [0688139a45](https://linux-hardware.org/?probe=0688139a45) | Aug 04, 2021 |
| Lenovo        | ThinkPad T61 6465CTO        | [d93258840e](https://linux-hardware.org/?probe=d93258840e) | Aug 04, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [1b40831803](https://linux-hardware.org/?probe=1b40831803) | Aug 04, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [a7b5b1d518](https://linux-hardware.org/?probe=a7b5b1d518) | Aug 04, 2021 |
| Dell          | Inspiron 3521               | [d32389b4e2](https://linux-hardware.org/?probe=d32389b4e2) | Jul 30, 2021 |
| Acer          | Extensa 5220                | [e8b82c756d](https://linux-hardware.org/?probe=e8b82c756d) | Jul 26, 2021 |
| Acer          | Extensa 5220                | [82ae089b21](https://linux-hardware.org/?probe=82ae089b21) | Jul 26, 2021 |
| Unknown       | MEDION                      | [021ba4d5b5](https://linux-hardware.org/?probe=021ba4d5b5) | Jul 25, 2021 |
| Unknown       | MEDION                      | [5df19c2a06](https://linux-hardware.org/?probe=5df19c2a06) | Jul 25, 2021 |
| Unknown       | MEDION                      | [e9c5e99e0b](https://linux-hardware.org/?probe=e9c5e99e0b) | Jul 25, 2021 |
| HP            | Compaq CQ58                 | [96df68c59e](https://linux-hardware.org/?probe=96df68c59e) | Jul 25, 2021 |
| Dell          | Latitude 5480               | [1b32299688](https://linux-hardware.org/?probe=1b32299688) | Jul 24, 2021 |
| HP            | Notebook                    | [71959b30db](https://linux-hardware.org/?probe=71959b30db) | Jul 23, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [8d72c96d15](https://linux-hardware.org/?probe=8d72c96d15) | Jul 23, 2021 |
| Dell          | Inspiron N5010              | [4a76f84bf5](https://linux-hardware.org/?probe=4a76f84bf5) | Jul 22, 2021 |
| Dell          | Inspiron 3521               | [68ad133ec2](https://linux-hardware.org/?probe=68ad133ec2) | Jul 17, 2021 |
| Lenovo        | Y70-70 Touch 80DU           | [36fb0f3df5](https://linux-hardware.org/?probe=36fb0f3df5) | Jul 16, 2021 |
| Sony          | SVE14A2V1EW                 | [2b1ce53eca](https://linux-hardware.org/?probe=2b1ce53eca) | Jul 16, 2021 |
| HP            | 250 G7 Notebook PC          | [846febb191](https://linux-hardware.org/?probe=846febb191) | Jul 14, 2021 |
| HP            | EliteBook 820 G2            | [8c035c3e82](https://linux-hardware.org/?probe=8c035c3e82) | Jul 14, 2021 |
| ASUSTek       | G50V                        | [ec1ddd4644](https://linux-hardware.org/?probe=ec1ddd4644) | Jul 11, 2021 |
| Samsung       | N145P/N250P/N260P           | [e60ff3401a](https://linux-hardware.org/?probe=e60ff3401a) | Jul 11, 2021 |
| Sony          | VPCEH16EA                   | [189be303f7](https://linux-hardware.org/?probe=189be303f7) | Jul 09, 2021 |
| Sony          | VPCEH16EA                   | [c93e5aee87](https://linux-hardware.org/?probe=c93e5aee87) | Jul 08, 2021 |
| HP            | 255 G7 Notebook PC          | [b543fedfd0](https://linux-hardware.org/?probe=b543fedfd0) | Jul 08, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [508ac5b4d5](https://linux-hardware.org/?probe=508ac5b4d5) | Jul 07, 2021 |
| Sony          | VPCSB25FB                   | [6de928a758](https://linux-hardware.org/?probe=6de928a758) | Jul 07, 2021 |
| Gateway       | MX8711                      | [185e86b37e](https://linux-hardware.org/?probe=185e86b37e) | Jul 06, 2021 |
| Acer          | Aspire A515-45              | [42249c6e47](https://linux-hardware.org/?probe=42249c6e47) | Jul 02, 2021 |
| HP            | Pavilion dv6700             | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| ASUSTek       | K54HR                       | [8fcbeb49c1](https://linux-hardware.org/?probe=8fcbeb49c1) | Jun 26, 2021 |
| Sony          | VPCSB16FG                   | [ead356e548](https://linux-hardware.org/?probe=ead356e548) | Jun 24, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f3430744d8](https://linux-hardware.org/?probe=f3430744d8) | Jun 24, 2021 |
| HP            | Laptop 15-da0xxx            | [77fba11f44](https://linux-hardware.org/?probe=77fba11f44) | Jun 21, 2021 |
| Lenovo        | G40-30 80FY                 | [114ba38c36](https://linux-hardware.org/?probe=114ba38c36) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [0cb7e73af9](https://linux-hardware.org/?probe=0cb7e73af9) | Jun 19, 2021 |
| Dell          | Precision 7520              | [9b19302ca7](https://linux-hardware.org/?probe=9b19302ca7) | Jun 18, 2021 |
| Dell          | Inspiron N4010              | [d385bb7617](https://linux-hardware.org/?probe=d385bb7617) | Jun 15, 2021 |
| Dell          | Inspiron N4010              | [be79fbc95c](https://linux-hardware.org/?probe=be79fbc95c) | Jun 15, 2021 |
| Samsung       | N150/N210/N220              | [8e03d52f53](https://linux-hardware.org/?probe=8e03d52f53) | Jun 12, 2021 |
| Lenovo        | Unknown                     | [108d3cba46](https://linux-hardware.org/?probe=108d3cba46) | Jun 10, 2021 |
| HP            | Stream Notebook             | [806c24449c](https://linux-hardware.org/?probe=806c24449c) | Jun 09, 2021 |
| HCL Infosy... | HCL ME Laptop               | [0aaf1b69bc](https://linux-hardware.org/?probe=0aaf1b69bc) | Jun 08, 2021 |
| Dell          | Latitude E6520              | [04a7f10801](https://linux-hardware.org/?probe=04a7f10801) | Jun 08, 2021 |
| Lenovo        | G40-30 80FY                 | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| Sony          | VGN-BX51VN                  | [debf4b3290](https://linux-hardware.org/?probe=debf4b3290) | Jun 06, 2021 |
| ASUSTek       | Q524UQ                      | [442c1c8b06](https://linux-hardware.org/?probe=442c1c8b06) | Jun 05, 2021 |
| HP            | Pavilion dv5                | [94cfdbc88f](https://linux-hardware.org/?probe=94cfdbc88f) | Jun 03, 2021 |
| Unknown       | Unknown                     | [3ce5819b57](https://linux-hardware.org/?probe=3ce5819b57) | Jun 02, 2021 |
| Apple         | MacBookPro12,1              | [f7f5736b13](https://linux-hardware.org/?probe=f7f5736b13) | Jun 01, 2021 |
| Sony          | VGN-BX51VN                  | [055903703c](https://linux-hardware.org/?probe=055903703c) | Jun 01, 2021 |
| Toshiba       | Satellite M70               | [67580c50df](https://linux-hardware.org/?probe=67580c50df) | Jun 01, 2021 |
| Acer          | Aspire 3100                 | [d38f5b09d2](https://linux-hardware.org/?probe=d38f5b09d2) | Jun 01, 2021 |
| Acer          | Aspire 3100                 | [fbcd23ac31](https://linux-hardware.org/?probe=fbcd23ac31) | May 31, 2021 |
| Toshiba       | Satellite P300              | [feb13460e8](https://linux-hardware.org/?probe=feb13460e8) | May 30, 2021 |
| Toshiba       | Satellite P300              | [8b5034adc9](https://linux-hardware.org/?probe=8b5034adc9) | May 30, 2021 |
| Lenovo        | G40-30 80FY                 | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| HP            | Pavilion g7                 | [582c1aa224](https://linux-hardware.org/?probe=582c1aa224) | May 29, 2021 |
| Dell          | Inspiron 3521               | [9fc71241e6](https://linux-hardware.org/?probe=9fc71241e6) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| ARIMA         | W351UI                      | [6cbffa9177](https://linux-hardware.org/?probe=6cbffa9177) | May 25, 2021 |
| Dell          | Latitude D520               | [7a817a0426](https://linux-hardware.org/?probe=7a817a0426) | May 25, 2021 |
| HP            | Pavilion dv6700             | [b30d13bbba](https://linux-hardware.org/?probe=b30d13bbba) | May 25, 2021 |
| ASUSTek       | UX31A                       | [edeed3b99b](https://linux-hardware.org/?probe=edeed3b99b) | May 23, 2021 |
| ASUSTek       | UX31A                       | [7f750ead39](https://linux-hardware.org/?probe=7f750ead39) | May 23, 2021 |
| Google        | Candy                       | [f6b5b1fd81](https://linux-hardware.org/?probe=f6b5b1fd81) | May 23, 2021 |
| ASUSTek       | X540YA                      | [369ebd51b8](https://linux-hardware.org/?probe=369ebd51b8) | May 23, 2021 |
| ASUSTek       | F5N                         | [414786c3d5](https://linux-hardware.org/?probe=414786c3d5) | May 22, 2021 |
| Dell          | Inspiron 3521               | [ef65e1a0f7](https://linux-hardware.org/?probe=ef65e1a0f7) | May 21, 2021 |
| Dell          | Latitude E7240              | [9e790ba3f0](https://linux-hardware.org/?probe=9e790ba3f0) | May 21, 2021 |
| Dell          | Latitude E7240              | [7fbfcffd54](https://linux-hardware.org/?probe=7fbfcffd54) | May 21, 2021 |
| HP            | 255 G5                      | [cbd6a96f91](https://linux-hardware.org/?probe=cbd6a96f91) | May 20, 2021 |
| ASUSTek       | T100TA                      | [bca3c06314](https://linux-hardware.org/?probe=bca3c06314) | May 20, 2021 |
| ASUSTek       | T100TA                      | [f232d2395d](https://linux-hardware.org/?probe=f232d2395d) | May 19, 2021 |
| Dell          | G5 5587                     | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [d9592ead1e](https://linux-hardware.org/?probe=d9592ead1e) | May 18, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [bc6920fa56](https://linux-hardware.org/?probe=bc6920fa56) | May 16, 2021 |
| HP            | 435                         | [65bbde1e13](https://linux-hardware.org/?probe=65bbde1e13) | May 16, 2021 |
| HP            | 435                         | [fe5a82cf02](https://linux-hardware.org/?probe=fe5a82cf02) | May 16, 2021 |
| ASUSTek       | K54C                        | [af86f8b1ed](https://linux-hardware.org/?probe=af86f8b1ed) | May 14, 2021 |
| Dell          | Inspiron 14-3467            | [511f638394](https://linux-hardware.org/?probe=511f638394) | May 14, 2021 |
| Acer          | V5-131                      | [d78c3cc207](https://linux-hardware.org/?probe=d78c3cc207) | May 14, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1070... | [e20eb6e1ff](https://linux-hardware.org/?probe=e20eb6e1ff) | May 13, 2021 |
| Dell          | Inspiron 1525               | [22f4b67d9b](https://linux-hardware.org/?probe=22f4b67d9b) | May 12, 2021 |
| Dell          | Inspiron 7520               | [fdf52a6676](https://linux-hardware.org/?probe=fdf52a6676) | May 11, 2021 |
| Samsung       | RF712                       | [a3624b29fa](https://linux-hardware.org/?probe=a3624b29fa) | May 11, 2021 |
| Samsung       | RF712                       | [652fb28adb](https://linux-hardware.org/?probe=652fb28adb) | May 11, 2021 |
| ASUSTek       | K54C                        | [9e994cd1f2](https://linux-hardware.org/?probe=9e994cd1f2) | May 11, 2021 |
| HP            | ProBook 4510s               | [dbdd169cb4](https://linux-hardware.org/?probe=dbdd169cb4) | May 10, 2021 |
| Dell          | Inspiron 14-3467            | [2fd207a33d](https://linux-hardware.org/?probe=2fd207a33d) | May 10, 2021 |
| Fujitsu       | FMVNF40UK                   | [8648b42278](https://linux-hardware.org/?probe=8648b42278) | May 09, 2021 |
| Dell          | Inspiron 14-3467            | [173baf5fdb](https://linux-hardware.org/?probe=173baf5fdb) | May 09, 2021 |
| Toshiba       | Satellite P200              | [5fff6be5f0](https://linux-hardware.org/?probe=5fff6be5f0) | May 05, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [0c612ea2a3](https://linux-hardware.org/?probe=0c612ea2a3) | May 04, 2021 |
| Lenovo        | 406822U                     | [68080373ce](https://linux-hardware.org/?probe=68080373ce) | May 03, 2021 |
| Lenovo        | 406822U                     | [5d498a42cc](https://linux-hardware.org/?probe=5d498a42cc) | May 03, 2021 |
| ASUSTek       | X540SA                      | [0f79fb429b](https://linux-hardware.org/?probe=0f79fb429b) | May 02, 2021 |
| Acer          | Aspire 5538                 | [b01066567a](https://linux-hardware.org/?probe=b01066567a) | May 02, 2021 |
| Acer          | Aspire 5538                 | [39c929202c](https://linux-hardware.org/?probe=39c929202c) | May 02, 2021 |
| Acer          | AOD255E                     | [202573d3f1](https://linux-hardware.org/?probe=202573d3f1) | May 02, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [21666fb8b5](https://linux-hardware.org/?probe=21666fb8b5) | May 01, 2021 |
| TrekStor      | Notebook Slim S130          | [3ee0251799](https://linux-hardware.org/?probe=3ee0251799) | May 01, 2021 |
| HP            | ENVY Notebook               | [00123e7e27](https://linux-hardware.org/?probe=00123e7e27) | May 01, 2021 |
| Positivo      | S14CT01                     | [d6ad6f67a7](https://linux-hardware.org/?probe=d6ad6f67a7) | Apr 30, 2021 |
| Dell          | Latitude D630               | [ce166d946d](https://linux-hardware.org/?probe=ce166d946d) | Apr 30, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [dc22e810b4](https://linux-hardware.org/?probe=dc22e810b4) | Apr 29, 2021 |
| Itautec       | Infoway                     | [01e1f5151c](https://linux-hardware.org/?probe=01e1f5151c) | Apr 28, 2021 |
| Fujitsu       | LIFEBOOK U772               | [e2c74983d8](https://linux-hardware.org/?probe=e2c74983d8) | Apr 28, 2021 |
| Lenovo        | ThinkPad X131e 3372A14      | [3c79681783](https://linux-hardware.org/?probe=3c79681783) | Apr 26, 2021 |
| Acer          | Aspire E5-523               | [7acc074ffd](https://linux-hardware.org/?probe=7acc074ffd) | Apr 26, 2021 |
| Acer          | Aspire E5-523               | [349b8662d9](https://linux-hardware.org/?probe=349b8662d9) | Apr 26, 2021 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [4cffaa3991](https://linux-hardware.org/?probe=4cffaa3991) | Apr 23, 2021 |
| Acer          | Unknown                     | [cd6b0eabe2](https://linux-hardware.org/?probe=cd6b0eabe2) | Apr 23, 2021 |
| Acer          | Aspire 5333                 | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| Toshiba       | IS 1422                     | [f52456fce9](https://linux-hardware.org/?probe=f52456fce9) | Apr 22, 2021 |
| Toshiba       | IS 1422                     | [9443f68502](https://linux-hardware.org/?probe=9443f68502) | Apr 22, 2021 |
| Samsung       | 550XCJ/550XCR               | [2a2a56b6d4](https://linux-hardware.org/?probe=2a2a56b6d4) | Apr 22, 2021 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [d8340c053a](https://linux-hardware.org/?probe=d8340c053a) | Apr 22, 2021 |
| Packard Be... | EasyNote_BU45               | [7d3e06e670](https://linux-hardware.org/?probe=7d3e06e670) | Apr 21, 2021 |
| Packard Be... | EasyNote_BU45               | [c97faabab8](https://linux-hardware.org/?probe=c97faabab8) | Apr 21, 2021 |
| Dell          | Latitude D620               | [116568909e](https://linux-hardware.org/?probe=116568909e) | Apr 19, 2021 |
| Dell          | Latitude D520               | [4e8b58ab28](https://linux-hardware.org/?probe=4e8b58ab28) | Apr 16, 2021 |
| Acer          | Aspire 5333                 | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A             | [6670c58f24](https://linux-hardware.org/?probe=6670c58f24) | Apr 15, 2021 |
| Dell          | Inspiron 5759               | [7fcec2352e](https://linux-hardware.org/?probe=7fcec2352e) | Apr 15, 2021 |
| HP            | Pavilion dv5                | [901dd6f4bc](https://linux-hardware.org/?probe=901dd6f4bc) | Apr 14, 2021 |
| Toshiba       | Satellite C55-A             | [7862f9a6e6](https://linux-hardware.org/?probe=7862f9a6e6) | Apr 14, 2021 |
| Toshiba       | Satellite P200              | [be67fe4734](https://linux-hardware.org/?probe=be67fe4734) | Apr 11, 2021 |
| Toshiba       | Satellite P200              | [f6b3c134f2](https://linux-hardware.org/?probe=f6b3c134f2) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | [8351e652e0](https://linux-hardware.org/?probe=8351e652e0) | Apr 11, 2021 |
| Dell          | Latitude D620               | [f0eb74cd27](https://linux-hardware.org/?probe=f0eb74cd27) | Apr 11, 2021 |
| Dell          | Latitude D620               | [599e543d6b](https://linux-hardware.org/?probe=599e543d6b) | Apr 11, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [24f7a90612](https://linux-hardware.org/?probe=24f7a90612) | Apr 10, 2021 |
| Lenovo        | ThinkPad W540 20BHS1MX00    | [762a1d15ab](https://linux-hardware.org/?probe=762a1d15ab) | Apr 09, 2021 |
| Toshiba       | dynabook R731/E             | [108510a130](https://linux-hardware.org/?probe=108510a130) | Apr 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [cdf6743f68](https://linux-hardware.org/?probe=cdf6743f68) | Apr 08, 2021 |
| Positivo      | Mobile                      | [340616710c](https://linux-hardware.org/?probe=340616710c) | Apr 07, 2021 |
| Toshiba       | QOSMIO X300                 | [7f3b22129c](https://linux-hardware.org/?probe=7f3b22129c) | Apr 07, 2021 |
| Toshiba       | QOSMIO X300                 | [c1e66d512d](https://linux-hardware.org/?probe=c1e66d512d) | Apr 07, 2021 |
| HP            | 15                          | [69d2aa2538](https://linux-hardware.org/?probe=69d2aa2538) | Apr 05, 2021 |
| HP            | EliteBook Folio 9480m       | [c878c10e7b](https://linux-hardware.org/?probe=c878c10e7b) | Apr 03, 2021 |
| Gigabyte      | AERO 15-SA                  | [b162082414](https://linux-hardware.org/?probe=b162082414) | Apr 03, 2021 |
| Compaq        | Presario CQ-17              | [d1ae1543d9](https://linux-hardware.org/?probe=d1ae1543d9) | Apr 02, 2021 |
| HP            | Stream Notebook PC 11       | [a2a25ee9ac](https://linux-hardware.org/?probe=a2a25ee9ac) | Apr 02, 2021 |
| HP            | Stream Notebook PC 11       | [bb9c9dc740](https://linux-hardware.org/?probe=bb9c9dc740) | Apr 01, 2021 |
| HP            | Laptop 15-dw1xxx            | [276153c011](https://linux-hardware.org/?probe=276153c011) | Mar 31, 2021 |
| HP            | Laptop 15-dw1xxx            | [7dc5cad98d](https://linux-hardware.org/?probe=7dc5cad98d) | Mar 31, 2021 |
| Gigabyte      | AERO 15-SA                  | [26957c118d](https://linux-hardware.org/?probe=26957c118d) | Mar 30, 2021 |
| Toshiba       | QOSMIO F50                  | [d9d565847f](https://linux-hardware.org/?probe=d9d565847f) | Mar 29, 2021 |
| HP            | ProBook 4540s               | [94b1064fc6](https://linux-hardware.org/?probe=94b1064fc6) | Mar 28, 2021 |
| HP            | ProBook 4540s               | [c6e6b05536](https://linux-hardware.org/?probe=c6e6b05536) | Mar 28, 2021 |
| ASUSTek       | X200CA                      | [fd66b80491](https://linux-hardware.org/?probe=fd66b80491) | Mar 28, 2021 |
| Gigabyte      | AERO 15-SA                  | [536dfb993f](https://linux-hardware.org/?probe=536dfb993f) | Mar 28, 2021 |
| Lenovo        | ThinkPad T430s 2356DH2      | [86d756fb89](https://linux-hardware.org/?probe=86d756fb89) | Mar 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8S... | [327b8352df](https://linux-hardware.org/?probe=327b8352df) | Mar 27, 2021 |
| HP            | Mini 110-1100               | [05039f09e2](https://linux-hardware.org/?probe=05039f09e2) | Mar 26, 2021 |
| HP            | Mini 110-1100               | [5192a10f03](https://linux-hardware.org/?probe=5192a10f03) | Mar 26, 2021 |
| ASUSTek       | 1011PX                      | [3d23090e46](https://linux-hardware.org/?probe=3d23090e46) | Mar 26, 2021 |
| HP            | Compaq Presario CQ61        | [58db0eef1f](https://linux-hardware.org/?probe=58db0eef1f) | Mar 25, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [729ef4d91f](https://linux-hardware.org/?probe=729ef4d91f) | Mar 25, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [a092c49f22](https://linux-hardware.org/?probe=a092c49f22) | Mar 25, 2021 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [125911ba8d](https://linux-hardware.org/?probe=125911ba8d) | Mar 21, 2021 |
| Apple         | MacBookPro5,4               | [e1ff6cd3c6](https://linux-hardware.org/?probe=e1ff6cd3c6) | Mar 20, 2021 |
| ASUSTek       | X555LD                      | [cf0c496200](https://linux-hardware.org/?probe=cf0c496200) | Mar 20, 2021 |
| ASUSTek       | X555LD                      | [25834ccc9f](https://linux-hardware.org/?probe=25834ccc9f) | Mar 20, 2021 |
| HP            | ProBook 470 G1              | [7358a0ab88](https://linux-hardware.org/?probe=7358a0ab88) | Mar 20, 2021 |
| HP            | ProBook 470 G1              | [9a754ec32f](https://linux-hardware.org/?probe=9a754ec32f) | Mar 20, 2021 |
| Lenovo        | ThinkPad T420 41786UU       | [3965832137](https://linux-hardware.org/?probe=3965832137) | Mar 20, 2021 |
| Dell          | Latitude D610               | [faaf3b4f3d](https://linux-hardware.org/?probe=faaf3b4f3d) | Mar 18, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [fd9fa3feec](https://linux-hardware.org/?probe=fd9fa3feec) | Mar 15, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [65dc37550e](https://linux-hardware.org/?probe=65dc37550e) | Mar 15, 2021 |
| Panasonic     | CF-31JEGAX1M                | [4636e611d8](https://linux-hardware.org/?probe=4636e611d8) | Mar 14, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [9707772e02](https://linux-hardware.org/?probe=9707772e02) | Mar 13, 2021 |
| Acer          | Aspire 5610Z                | [ba43bff53e](https://linux-hardware.org/?probe=ba43bff53e) | Mar 13, 2021 |
| ASUSTek       | E402SA                      | [eec3171b5f](https://linux-hardware.org/?probe=eec3171b5f) | Mar 13, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [85703241b5](https://linux-hardware.org/?probe=85703241b5) | Mar 13, 2021 |
| MSI           | GX60 1AC                    | [774db4f685](https://linux-hardware.org/?probe=774db4f685) | Mar 12, 2021 |
| Hometech      | ELITE TAB 10                | [8bfad5d181](https://linux-hardware.org/?probe=8bfad5d181) | Mar 09, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [8a0395042b](https://linux-hardware.org/?probe=8a0395042b) | Mar 08, 2021 |
| Toshiba       | Satellite P300-17Q          | [72b5282501](https://linux-hardware.org/?probe=72b5282501) | Mar 08, 2021 |
| Gateway       | NV55C                       | [3f5377a2de](https://linux-hardware.org/?probe=3f5377a2de) | Mar 08, 2021 |
| Acer          | Aspire 5735                 | [cde827bd2e](https://linux-hardware.org/?probe=cde827bd2e) | Mar 07, 2021 |
| Acer          | Aspire 5735                 | [9730b9273d](https://linux-hardware.org/?probe=9730b9273d) | Mar 07, 2021 |
| HP            | 255 G7 Notebook PC          | [f5600011bb](https://linux-hardware.org/?probe=f5600011bb) | Mar 05, 2021 |
| HP            | 255 G7 Notebook PC          | [19e8d1a155](https://linux-hardware.org/?probe=19e8d1a155) | Mar 05, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1070... | [0f786e52cb](https://linux-hardware.org/?probe=0f786e52cb) | Mar 05, 2021 |
| Toshiba       | Satellite U920t             | [26b9e489aa](https://linux-hardware.org/?probe=26b9e489aa) | Mar 04, 2021 |
| HP            | 255 G5                      | [6f8d03c3a9](https://linux-hardware.org/?probe=6f8d03c3a9) | Mar 03, 2021 |
| Toshiba       | Satellite NB10t-A           | [c1c084e42c](https://linux-hardware.org/?probe=c1c084e42c) | Feb 28, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [dfc0744775](https://linux-hardware.org/?probe=dfc0744775) | Feb 28, 2021 |
| Multilaser    | PC024                       | [abaddb333b](https://linux-hardware.org/?probe=abaddb333b) | Feb 27, 2021 |
| Multilaser    | PC024                       | [54e46489ac](https://linux-hardware.org/?probe=54e46489ac) | Feb 27, 2021 |
| HP            | Compaq 6510b (GR690ET#AB... | [b9b8fa550a](https://linux-hardware.org/?probe=b9b8fa550a) | Feb 26, 2021 |
| HP            | Compaq 6510b (GR690ET#AB... | [4529dc90b2](https://linux-hardware.org/?probe=4529dc90b2) | Feb 26, 2021 |
| ASUSTek       | X555LD                      | [665cf4701a](https://linux-hardware.org/?probe=665cf4701a) | Feb 25, 2021 |
| Dell          | Inspiron 3543               | [cfc4c1a529](https://linux-hardware.org/?probe=cfc4c1a529) | Feb 24, 2021 |
| ASUSTek       | X751SJ                      | [81295695f3](https://linux-hardware.org/?probe=81295695f3) | Feb 24, 2021 |
| Dell          | Inspiron 3543               | [6b53f592ed](https://linux-hardware.org/?probe=6b53f592ed) | Feb 22, 2021 |
| HP            | ZBook 17 G2                 | [7213996a6e](https://linux-hardware.org/?probe=7213996a6e) | Feb 22, 2021 |
| Samsung       | 370E4K                      | [9d25cf824e](https://linux-hardware.org/?probe=9d25cf824e) | Feb 20, 2021 |
| Dell          | Inspiron 7737               | [ffaf611204](https://linux-hardware.org/?probe=ffaf611204) | Feb 20, 2021 |
| Dell          | Inspiron 7737               | [eada1070d2](https://linux-hardware.org/?probe=eada1070d2) | Feb 20, 2021 |
| ASUSTek       | K52N                        | [0139461f57](https://linux-hardware.org/?probe=0139461f57) | Feb 19, 2021 |
| ASUSTek       | U36SD                       | [981c7e8da7](https://linux-hardware.org/?probe=981c7e8da7) | Feb 19, 2021 |
| ASUSTek       | X550ZA                      | [503250e6f1](https://linux-hardware.org/?probe=503250e6f1) | Feb 19, 2021 |
| HP            | 255 G5                      | [2ffdcec174](https://linux-hardware.org/?probe=2ffdcec174) | Feb 19, 2021 |
| Dell          | XPS 13 9333                 | [0166a2e7b9](https://linux-hardware.org/?probe=0166a2e7b9) | Feb 17, 2021 |
| Dell          | XPS 13 9333                 | [4e08aeb5c5](https://linux-hardware.org/?probe=4e08aeb5c5) | Feb 17, 2021 |
| HP            | Compaq Presario CQ61        | [e72ebb6663](https://linux-hardware.org/?probe=e72ebb6663) | Feb 14, 2021 |
| Toshiba       | Satellite L855              | [941b946e5e](https://linux-hardware.org/?probe=941b946e5e) | Feb 14, 2021 |
| Toshiba       | Satellite L855              | [4cfe29288e](https://linux-hardware.org/?probe=4cfe29288e) | Feb 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [622900874e](https://linux-hardware.org/?probe=622900874e) | Feb 14, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [2b5732689b](https://linux-hardware.org/?probe=2b5732689b) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [0005b66219](https://linux-hardware.org/?probe=0005b66219) | Feb 13, 2021 |
| HP            | ENVY 15                     | [ab6ef5e4cf](https://linux-hardware.org/?probe=ab6ef5e4cf) | Feb 12, 2021 |
| HP            | Compaq Presario CQ61        | [bcf179fa51](https://linux-hardware.org/?probe=bcf179fa51) | Feb 12, 2021 |
| ASUSTek       | X510UAR                     | [e194fe9742](https://linux-hardware.org/?probe=e194fe9742) | Feb 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [c7c4c6fe88](https://linux-hardware.org/?probe=c7c4c6fe88) | Feb 11, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1070... | [b14a3d0adb](https://linux-hardware.org/?probe=b14a3d0adb) | Feb 09, 2021 |
| Acer          | V5-131                      | [8434293097](https://linux-hardware.org/?probe=8434293097) | Feb 09, 2021 |
| NEC Comput... | PC-VY12FBHEW                | [c65bc992c6](https://linux-hardware.org/?probe=c65bc992c6) | Feb 08, 2021 |
| Dell          | Inspiron 1012               | [e5ec198a6d](https://linux-hardware.org/?probe=e5ec198a6d) | Feb 07, 2021 |
| HP            | Stream Laptop 11-y0XX       | [1a6227c6cf](https://linux-hardware.org/?probe=1a6227c6cf) | Feb 07, 2021 |
| Toshiba       | Satellite Pro L550          | [b6870f2fea](https://linux-hardware.org/?probe=b6870f2fea) | Feb 07, 2021 |
| Lenovo        | ThinkPad R61 8943DKG        | [fd7beeb674](https://linux-hardware.org/?probe=fd7beeb674) | Feb 06, 2021 |
| Lenovo        | ThinkPad R61 8943DKG        | [6a3c7e3263](https://linux-hardware.org/?probe=6a3c7e3263) | Feb 06, 2021 |
| Acer          | TravelMate 6592             | [9b2c049705](https://linux-hardware.org/?probe=9b2c049705) | Feb 06, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [067995d50f](https://linux-hardware.org/?probe=067995d50f) | Feb 05, 2021 |
| Unknown       | ARCELIK ANB 573 D SR        | [7ef8639d95](https://linux-hardware.org/?probe=7ef8639d95) | Feb 04, 2021 |
| Unknown       | ARCELIK ANB 573 D SR        | [70b60f77cc](https://linux-hardware.org/?probe=70b60f77cc) | Feb 04, 2021 |
| Lenovo        | G560 0679                   | [ebf2298ba0](https://linux-hardware.org/?probe=ebf2298ba0) | Feb 04, 2021 |
| Dell          | Latitude E6400              | [99e1f46388](https://linux-hardware.org/?probe=99e1f46388) | Feb 03, 2021 |
| HP            | EliteBook 2560p             | [f741035d0d](https://linux-hardware.org/?probe=f741035d0d) | Feb 02, 2021 |
| Dell          | Latitude D520               | [038841ada5](https://linux-hardware.org/?probe=038841ada5) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2dd10bb86f](https://linux-hardware.org/?probe=2dd10bb86f) | Feb 01, 2021 |
| HP            | G42                         | [532d273aec](https://linux-hardware.org/?probe=532d273aec) | Feb 01, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [18ceaaebaf](https://linux-hardware.org/?probe=18ceaaebaf) | Feb 01, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [90149b2d99](https://linux-hardware.org/?probe=90149b2d99) | Feb 01, 2021 |
| ASUSTek       | X555LD                      | [eb3be3f63f](https://linux-hardware.org/?probe=eb3be3f63f) | Jan 31, 2021 |
| Sony          | VGN-AR630E                  | [2e155fc628](https://linux-hardware.org/?probe=2e155fc628) | Jan 31, 2021 |
| Panasonic     | CF-30K3PAZN2                | [9a9c09f250](https://linux-hardware.org/?probe=9a9c09f250) | Jan 30, 2021 |
| Panasonic     | CF-30K3PAZN2                | [a1b4116c85](https://linux-hardware.org/?probe=a1b4116c85) | Jan 30, 2021 |
| ASUSTek       | U36SD                       | [5267c17fbb](https://linux-hardware.org/?probe=5267c17fbb) | Jan 30, 2021 |
| HP            | Pavilion zd8000 (PW934EA... | [640a4d1741](https://linux-hardware.org/?probe=640a4d1741) | Jan 29, 2021 |
| Olidata       | U40SI1                      | [60dd97276a](https://linux-hardware.org/?probe=60dd97276a) | Jan 28, 2021 |
| Olidata       | U40SI1                      | [cca9468e85](https://linux-hardware.org/?probe=cca9468e85) | Jan 28, 2021 |
| ASUSTek       | U36SD                       | [15288996d1](https://linux-hardware.org/?probe=15288996d1) | Jan 28, 2021 |
| Lenovo        | ThinkPad X240 20AM006KMN    | [7c40d08353](https://linux-hardware.org/?probe=7c40d08353) | Jan 28, 2021 |
| Acer          | Aspire E1-570G              | [19e6d6afd7](https://linux-hardware.org/?probe=19e6d6afd7) | Jan 28, 2021 |
| Toshiba       | Satellite L500              | [f9341665f3](https://linux-hardware.org/?probe=f9341665f3) | Jan 27, 2021 |
| Dell          | Latitude E5470              | [72db68119a](https://linux-hardware.org/?probe=72db68119a) | Jan 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [00f0257410](https://linux-hardware.org/?probe=00f0257410) | Jan 27, 2021 |
| HP            | ZBook 17 G6                 | [63c3d95bd5](https://linux-hardware.org/?probe=63c3d95bd5) | Jan 27, 2021 |
| Dell          | Latitude D630               | [efc4256a09](https://linux-hardware.org/?probe=efc4256a09) | Jan 26, 2021 |
| Dell          | Latitude E6400              | [91be1b1bd7](https://linux-hardware.org/?probe=91be1b1bd7) | Jan 26, 2021 |
| Acer          | Aspire E1-570G              | [bffb99b092](https://linux-hardware.org/?probe=bffb99b092) | Jan 26, 2021 |
| Acer          | Aspire E1-570G              | [f8f4880823](https://linux-hardware.org/?probe=f8f4880823) | Jan 26, 2021 |
| Toshiba       | Satellite L635              | [ca6d27fd9c](https://linux-hardware.org/?probe=ca6d27fd9c) | Jan 24, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [158b3578e3](https://linux-hardware.org/?probe=158b3578e3) | Jan 23, 2021 |
| Unknown       | Unknown                     | [0c6628ea31](https://linux-hardware.org/?probe=0c6628ea31) | Jan 23, 2021 |
| Dell          | Latitude E6400              | [fc052ebe8f](https://linux-hardware.org/?probe=fc052ebe8f) | Jan 23, 2021 |
| Apple         | MacBookPro11,1              | [b27a2d92e2](https://linux-hardware.org/?probe=b27a2d92e2) | Jan 22, 2021 |
| Sony          | SVE14A2V1EW                 | [baaf829145](https://linux-hardware.org/?probe=baaf829145) | Jan 20, 2021 |
| Dell          | Latitude E5430 non-vPro     | [db6d4d3deb](https://linux-hardware.org/?probe=db6d4d3deb) | Jan 20, 2021 |
| HP            | ProBook 6560b               | [4771c30f72](https://linux-hardware.org/?probe=4771c30f72) | Jan 18, 2021 |
| Lenovo        | ThinkPad X220 4290NC9       | [f90fbc6c88](https://linux-hardware.org/?probe=f90fbc6c88) | Jan 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | [1dfeaa1b83](https://linux-hardware.org/?probe=1dfeaa1b83) | Jan 17, 2021 |
| Toshiba       | Satellite L850-1HP          | [1e0aa7f353](https://linux-hardware.org/?probe=1e0aa7f353) | Jan 17, 2021 |
| Toshiba       | Satellite U920t             | [35e0de41d7](https://linux-hardware.org/?probe=35e0de41d7) | Jan 17, 2021 |
| Toshiba       | Satellite U920t             | [566f573caf](https://linux-hardware.org/?probe=566f573caf) | Jan 17, 2021 |
| Itautec       | Infoway a7420               | [d32d9bf816](https://linux-hardware.org/?probe=d32d9bf816) | Jan 16, 2021 |
| Quanta        | MW1/HW1                     | [ebab0a47f8](https://linux-hardware.org/?probe=ebab0a47f8) | Jan 16, 2021 |
| Unknown       | Unknown                     | [1fddcd5f95](https://linux-hardware.org/?probe=1fddcd5f95) | Jan 15, 2021 |
| Lenovo        | V145-15AST 81MT             | [ecaaa0fccb](https://linux-hardware.org/?probe=ecaaa0fccb) | Jan 14, 2021 |
| Lenovo        | ThinkPad Edge E530 3259A... | [e7ef3a9e86](https://linux-hardware.org/?probe=e7ef3a9e86) | Jan 14, 2021 |
| HP            | Presario V6000 (GF814EA#... | [1cb2345540](https://linux-hardware.org/?probe=1cb2345540) | Jan 12, 2021 |
| HP            | Compaq 6730s                | [71a2587c96](https://linux-hardware.org/?probe=71a2587c96) | Jan 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell          | Inspiron 3521               | [2e84869a9a](https://linux-hardware.org/?probe=2e84869a9a) | Jan 11, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [a8a6e06472](https://linux-hardware.org/?probe=a8a6e06472) | Jan 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9088e2aaad](https://linux-hardware.org/?probe=9088e2aaad) | Jan 09, 2021 |
| HP            | Pavilion (EH735UA#ABA)      | [f01f51c47c](https://linux-hardware.org/?probe=f01f51c47c) | Jan 09, 2021 |
| HP            | Pavilion (EH735UA#ABA)      | [d3c610e2b0](https://linux-hardware.org/?probe=d3c610e2b0) | Jan 08, 2021 |
| HP            | 255 G5                      | [e49f09a1d5](https://linux-hardware.org/?probe=e49f09a1d5) | Jan 08, 2021 |
| Acer          | Aspire V5-571               | [1d56503d52](https://linux-hardware.org/?probe=1d56503d52) | Jan 06, 2021 |
| Packard Be... | EasyNote TS11HR             | [ab603b2fe8](https://linux-hardware.org/?probe=ab603b2fe8) | Jan 06, 2021 |
| Dell          | Inspiron M5040              | [1cac82f558](https://linux-hardware.org/?probe=1cac82f558) | Jan 06, 2021 |
| Acer          | Aspire 5100                 | [a009c7e619](https://linux-hardware.org/?probe=a009c7e619) | Jan 05, 2021 |
| HP            | ProBook 6560b               | [0b69385e25](https://linux-hardware.org/?probe=0b69385e25) | Jan 04, 2021 |
| HP            | Pavilion g7                 | [dea98a2e2c](https://linux-hardware.org/?probe=dea98a2e2c) | Jan 04, 2021 |
| ASUSTek       | G74Sx                       | [17e1f90630](https://linux-hardware.org/?probe=17e1f90630) | Jan 04, 2021 |
| HP            | Compaq 6730s                | [00acad5ef5](https://linux-hardware.org/?probe=00acad5ef5) | Jan 03, 2021 |
| HP            | Pavilion g7                 | [12f3858f34](https://linux-hardware.org/?probe=12f3858f34) | Jan 03, 2021 |
| HP            | 250 G5 Notebook PC          | [a79116f681](https://linux-hardware.org/?probe=a79116f681) | Jan 03, 2021 |
| Dell          | XPS 13 9300                 | [0d6592676a](https://linux-hardware.org/?probe=0d6592676a) | Jan 02, 2021 |
| Packard Be... | EasyNote TS11HR             | [343249d2da](https://linux-hardware.org/?probe=343249d2da) | Jan 02, 2021 |
| HP            | 250 G5 Notebook PC          | [393c8ee706](https://linux-hardware.org/?probe=393c8ee706) | Jan 01, 2021 |
| Dell          | Inspiron 3541               | [e194f83f11](https://linux-hardware.org/?probe=e194f83f11) | Jan 01, 2021 |
| Dell          | Inspiron 3541               | [6d747c6598](https://linux-hardware.org/?probe=6d747c6598) | Jan 01, 2021 |
| Panasonic     | CF-31JEGAX1M                | [c0745f5a94](https://linux-hardware.org/?probe=c0745f5a94) | Dec 31, 2020 |
| HP            | ProBook 6560b               | [d6d7748e86](https://linux-hardware.org/?probe=d6d7748e86) | Dec 30, 2020 |
| Dell          | Inspiron 7737               | [494c51dbea](https://linux-hardware.org/?probe=494c51dbea) | Dec 30, 2020 |
| HP            | Compaq Presario CQ61        | [82c51cc214](https://linux-hardware.org/?probe=82c51cc214) | Dec 29, 2020 |
| HP            | Compaq Presario CQ61        | [a28099fd90](https://linux-hardware.org/?probe=a28099fd90) | Dec 29, 2020 |
| BGH           | C46G                        | [e61ae53564](https://linux-hardware.org/?probe=e61ae53564) | Dec 29, 2020 |
| HP            | Pavilion g7                 | [df2771c104](https://linux-hardware.org/?probe=df2771c104) | Dec 28, 2020 |
| Dell          | Inspiron 6000               | [7158c9692c](https://linux-hardware.org/?probe=7158c9692c) | Dec 27, 2020 |
| Insyde        | CherryTrail                 | [3d9eb0babd](https://linux-hardware.org/?probe=3d9eb0babd) | Dec 26, 2020 |
| BGH           | C46G                        | [515be17b75](https://linux-hardware.org/?probe=515be17b75) | Dec 26, 2020 |
| HP            | Mini 110-3100               | [f716ec84db](https://linux-hardware.org/?probe=f716ec84db) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | [25dadb6466](https://linux-hardware.org/?probe=25dadb6466) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | [72bfd374e3](https://linux-hardware.org/?probe=72bfd374e3) | Dec 26, 2020 |
| HP            | 255 G5                      | [0dc71b4d28](https://linux-hardware.org/?probe=0dc71b4d28) | Dec 24, 2020 |
| HP            | 255 G5                      | [61641daa75](https://linux-hardware.org/?probe=61641daa75) | Dec 24, 2020 |
| Acer          | Aspire 5715Z                | [8e6e0fd1c6](https://linux-hardware.org/?probe=8e6e0fd1c6) | Dec 24, 2020 |
| Ematic        | EWT127                      | [c48f491ddd](https://linux-hardware.org/?probe=c48f491ddd) | Dec 24, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [d3a90166ed](https://linux-hardware.org/?probe=d3a90166ed) | Dec 23, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [67aa607a3e](https://linux-hardware.org/?probe=67aa607a3e) | Dec 23, 2020 |
| Acer          | Aspire 5738                 | [27df1aad94](https://linux-hardware.org/?probe=27df1aad94) | Dec 22, 2020 |
| Lenovo        | G700 20251                  | [2bf9eaa028](https://linux-hardware.org/?probe=2bf9eaa028) | Dec 22, 2020 |
| HP            | Stream Notebook PC 14       | [515632d3df](https://linux-hardware.org/?probe=515632d3df) | Dec 22, 2020 |
| Dell          | Inspiron M5040              | [92b8392e21](https://linux-hardware.org/?probe=92b8392e21) | Dec 22, 2020 |
| Dell          | Inspiron M5040              | [aa3db87a20](https://linux-hardware.org/?probe=aa3db87a20) | Dec 22, 2020 |
| Dell          | Latitude E6540              | [a210e1c5b0](https://linux-hardware.org/?probe=a210e1c5b0) | Dec 21, 2020 |
| Lenovo        | G700 20251                  | [33926859e5](https://linux-hardware.org/?probe=33926859e5) | Dec 20, 2020 |
| Dell          | Inspiron 6000               | [2cb0530e89](https://linux-hardware.org/?probe=2cb0530e89) | Dec 20, 2020 |
| Acer          | Aspire E1-570G              | [54c4be3905](https://linux-hardware.org/?probe=54c4be3905) | Dec 19, 2020 |
| Acer          | Aspire E1-570G              | [121a7fd35e](https://linux-hardware.org/?probe=121a7fd35e) | Dec 19, 2020 |
| Phoenix/Si... | M720SR                      | [019e901528](https://linux-hardware.org/?probe=019e901528) | Dec 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [7148c9a870](https://linux-hardware.org/?probe=7148c9a870) | Dec 19, 2020 |
| HP            | 550                         | [43d983a998](https://linux-hardware.org/?probe=43d983a998) | Dec 16, 2020 |
| Dell          | Precision 3520              | [688878db51](https://linux-hardware.org/?probe=688878db51) | Dec 16, 2020 |
| Toshiba       | Satellite L40               | [1ec0f32bdf](https://linux-hardware.org/?probe=1ec0f32bdf) | Dec 14, 2020 |
| HP            | Stream Laptop 11-y0XX       | [ed04aa76f7](https://linux-hardware.org/?probe=ed04aa76f7) | Dec 13, 2020 |
| HP            | Stream Laptop 11-y0XX       | [a45597a09a](https://linux-hardware.org/?probe=a45597a09a) | Dec 13, 2020 |
| ASUSTek       | G74Sx                       | [79afc26e90](https://linux-hardware.org/?probe=79afc26e90) | Dec 13, 2020 |
| Acer          | Aspire ES1-111              | [89f4d8b69a](https://linux-hardware.org/?probe=89f4d8b69a) | Dec 13, 2020 |
| Acer          | Aspire ES1-111              | [d0f8154669](https://linux-hardware.org/?probe=d0f8154669) | Dec 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS37D0... | [c35140641b](https://linux-hardware.org/?probe=c35140641b) | Dec 13, 2020 |
| NEC Comput... | PC-VY16AWZE4                | [c395763d53](https://linux-hardware.org/?probe=c395763d53) | Dec 12, 2020 |
| Dell          | Inspiron 3737               | [db241e053d](https://linux-hardware.org/?probe=db241e053d) | Dec 11, 2020 |
| HP            | ZBook 17 G5                 | [ca21d7e31d](https://linux-hardware.org/?probe=ca21d7e31d) | Dec 11, 2020 |
| NEC Comput... | PC-VY16AWZE4                | [eb1884e7bd](https://linux-hardware.org/?probe=eb1884e7bd) | Dec 10, 2020 |
| Insyde        | CAVION BASE 8 MS            | [b2a146e87c](https://linux-hardware.org/?probe=b2a146e87c) | Dec 09, 2020 |
| Insyde        | CAVION BASE 8 MS            | [9a210b4ebc](https://linux-hardware.org/?probe=9a210b4ebc) | Dec 09, 2020 |
| HP            | Laptop 15-bw0xx             | [577608cf6f](https://linux-hardware.org/?probe=577608cf6f) | Dec 08, 2020 |
| HP            | Laptop 15-bw0xx             | [f20b348140](https://linux-hardware.org/?probe=f20b348140) | Dec 08, 2020 |
| HP            | ProBook 450 G3              | [68d5e14ae0](https://linux-hardware.org/?probe=68d5e14ae0) | Dec 08, 2020 |
| HP            | Mini 110-1000               | [b0b1659e5a](https://linux-hardware.org/?probe=b0b1659e5a) | Dec 07, 2020 |
| Toshiba       | NB500                       | [fa6b10012f](https://linux-hardware.org/?probe=fa6b10012f) | Dec 06, 2020 |
| HP            | Pavilion dv9700             | [c2e755bbd2](https://linux-hardware.org/?probe=c2e755bbd2) | Dec 06, 2020 |
| HP            | ProBook 450 G3              | [a2e08c9405](https://linux-hardware.org/?probe=a2e08c9405) | Dec 06, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [bb6425b804](https://linux-hardware.org/?probe=bb6425b804) | Dec 06, 2020 |
| HP            | Laptop 15s-eq0xxx           | [31f7a22aab](https://linux-hardware.org/?probe=31f7a22aab) | Dec 04, 2020 |
| HP            | Laptop 15s-eq0xxx           | [411cb199ce](https://linux-hardware.org/?probe=411cb199ce) | Dec 04, 2020 |
| Acer          | V5-131                      | [bfdf441399](https://linux-hardware.org/?probe=bfdf441399) | Dec 03, 2020 |
| HP            | EliteBook 2560p             | [704777ce16](https://linux-hardware.org/?probe=704777ce16) | Dec 03, 2020 |
| Fujitsu       | CELSIUS H710                | [03fea3325c](https://linux-hardware.org/?probe=03fea3325c) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | [1214e804ff](https://linux-hardware.org/?probe=1214e804ff) | Dec 01, 2020 |
| Dell          | Latitude E6410              | [073ae61394](https://linux-hardware.org/?probe=073ae61394) | Nov 30, 2020 |
| HP            | G7000                       | [9596f449f8](https://linux-hardware.org/?probe=9596f449f8) | Nov 30, 2020 |
| HP            | G7000                       | [ae575e12ab](https://linux-hardware.org/?probe=ae575e12ab) | Nov 30, 2020 |
| Notebook      | RIM2020                     | [2b494bfd6c](https://linux-hardware.org/?probe=2b494bfd6c) | Nov 28, 2020 |
| Dell          | Inspiron 15-3552            | [762c5e70ba](https://linux-hardware.org/?probe=762c5e70ba) | Nov 28, 2020 |
| Dell          | Inspiron 15-3552            | [fc13827e05](https://linux-hardware.org/?probe=fc13827e05) | Nov 28, 2020 |
| Dell          | Latitude E6410              | [c17a248879](https://linux-hardware.org/?probe=c17a248879) | Nov 28, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [b6570c8388](https://linux-hardware.org/?probe=b6570c8388) | Nov 28, 2020 |
| HP            | 530                         | [8f3bc43ec5](https://linux-hardware.org/?probe=8f3bc43ec5) | Nov 27, 2020 |
| HP            | 530                         | [b062349456](https://linux-hardware.org/?probe=b062349456) | Nov 27, 2020 |
| Notebook      | RIM2020                     | [a8a163c8b0](https://linux-hardware.org/?probe=a8a163c8b0) | Nov 27, 2020 |
| Dell          | Vostro A860                 | [beffd605b7](https://linux-hardware.org/?probe=beffd605b7) | Nov 27, 2020 |
| HP            | 530                         | [4d719de8d0](https://linux-hardware.org/?probe=4d719de8d0) | Nov 26, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4be164a8cb](https://linux-hardware.org/?probe=4be164a8cb) | Nov 26, 2020 |
| HP            | 2000                        | [031b9cf2af](https://linux-hardware.org/?probe=031b9cf2af) | Nov 25, 2020 |
| HP            | Pavilion dv6                | [678f6ed857](https://linux-hardware.org/?probe=678f6ed857) | Nov 24, 2020 |
| eMachines     | eM350                       | [2bafdd62aa](https://linux-hardware.org/?probe=2bafdd62aa) | Nov 23, 2020 |
| eMachines     | eM350                       | [03b9a0de29](https://linux-hardware.org/?probe=03b9a0de29) | Nov 23, 2020 |
| HP            | Presario V6500              | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Pavilion Notebook           | [a021bfc757](https://linux-hardware.org/?probe=a021bfc757) | Nov 23, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4accc1011e](https://linux-hardware.org/?probe=4accc1011e) | Nov 23, 2020 |
| HP            | 2000                        | [2090a455f6](https://linux-hardware.org/?probe=2090a455f6) | Nov 23, 2020 |
| HP            | 2000                        | [39c1685ce9](https://linux-hardware.org/?probe=39c1685ce9) | Nov 23, 2020 |
| HP            | Presario V6500              | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [7fe15caabf](https://linux-hardware.org/?probe=7fe15caabf) | Nov 23, 2020 |
| eMachines     | E525                        | [a5c37bf711](https://linux-hardware.org/?probe=a5c37bf711) | Nov 22, 2020 |
| Dell          | Inspiron 3737               | [7dced8b5ca](https://linux-hardware.org/?probe=7dced8b5ca) | Nov 22, 2020 |
| Dell          | Vostro1710                  | [a359187c45](https://linux-hardware.org/?probe=a359187c45) | Nov 22, 2020 |
| Dell          | Vostro1710                  | [748c9cec43](https://linux-hardware.org/?probe=748c9cec43) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | [07cc1e0952](https://linux-hardware.org/?probe=07cc1e0952) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | [7388498d54](https://linux-hardware.org/?probe=7388498d54) | Nov 22, 2020 |
| Dell          | Latitude D430               | [77ef794b1d](https://linux-hardware.org/?probe=77ef794b1d) | Nov 21, 2020 |
| Dell          | Latitude D430               | [c028c146b6](https://linux-hardware.org/?probe=c028c146b6) | Nov 21, 2020 |
| Acer          | V5-131                      | [1a017773a1](https://linux-hardware.org/?probe=1a017773a1) | Nov 21, 2020 |
| Dell          | Inspiron 3737               | [80df1af89c](https://linux-hardware.org/?probe=80df1af89c) | Nov 20, 2020 |
| Dell          | Latitude E6410              | [4879940968](https://linux-hardware.org/?probe=4879940968) | Nov 19, 2020 |
| HP            | Pavilion x2 Detachable      | [742f34e12f](https://linux-hardware.org/?probe=742f34e12f) | Nov 19, 2020 |
| Acer          | Aspire 5253                 | [5700a5a6f1](https://linux-hardware.org/?probe=5700a5a6f1) | Nov 19, 2020 |
| Dell          | Latitude E5420              | [816b9060e4](https://linux-hardware.org/?probe=816b9060e4) | Nov 19, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [6e9cf39149](https://linux-hardware.org/?probe=6e9cf39149) | Nov 18, 2020 |
| HP            | Compaq Mini 110c-1100       | [36bc2c3cdf](https://linux-hardware.org/?probe=36bc2c3cdf) | Nov 18, 2020 |
| Acer          | Aspire one                  | [455b9d5ac3](https://linux-hardware.org/?probe=455b9d5ac3) | Nov 17, 2020 |
| Acer          | Aspire E1-570G              | [3ac799a86e](https://linux-hardware.org/?probe=3ac799a86e) | Nov 17, 2020 |
| HP            | Pavilion x2 Detachable      | [14c5b0631b](https://linux-hardware.org/?probe=14c5b0631b) | Nov 17, 2020 |
| Toshiba       | Satellite Pro L550          | [0bd37ae304](https://linux-hardware.org/?probe=0bd37ae304) | Nov 16, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [539997bcef](https://linux-hardware.org/?probe=539997bcef) | Nov 16, 2020 |
| HP            | Pavilion dv6                | [b9e6c75b90](https://linux-hardware.org/?probe=b9e6c75b90) | Nov 15, 2020 |
| Dell          | Latitude E5440              | [b010db49f4](https://linux-hardware.org/?probe=b010db49f4) | Nov 15, 2020 |
| Acer          | Aspire 5630                 | [7479658951](https://linux-hardware.org/?probe=7479658951) | Nov 15, 2020 |
| Dell          | Latitude E6410              | [415cdc7c74](https://linux-hardware.org/?probe=415cdc7c74) | Nov 15, 2020 |
| HP            | EliteBook 840 G3            | [ec506b9770](https://linux-hardware.org/?probe=ec506b9770) | Nov 14, 2020 |
| Lenovo        | G550 20023                  | [9d67fb8d8b](https://linux-hardware.org/?probe=9d67fb8d8b) | Nov 13, 2020 |
| Fujitsu Si... | LIFEBOOK E8410              | [d79b3878a5](https://linux-hardware.org/?probe=d79b3878a5) | Nov 13, 2020 |
| Dell          | Latitude E6410              | [11be79ed72](https://linux-hardware.org/?probe=11be79ed72) | Nov 13, 2020 |
| Dell          | Inspiron 1545               | [3a0512d317](https://linux-hardware.org/?probe=3a0512d317) | Nov 13, 2020 |
| Dell          | Inspiron 1545               | [0c78c7bd9e](https://linux-hardware.org/?probe=0c78c7bd9e) | Nov 13, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [0470427c68](https://linux-hardware.org/?probe=0470427c68) | Nov 12, 2020 |
| HP            | Pavilion dv5000 (EP413UA... | [d8592798be](https://linux-hardware.org/?probe=d8592798be) | Nov 12, 2020 |
| ASUSTek       | M50Vm                       | [152f954015](https://linux-hardware.org/?probe=152f954015) | Nov 11, 2020 |
| ASUSTek       | M50Vm                       | [46b6e6863b](https://linux-hardware.org/?probe=46b6e6863b) | Nov 11, 2020 |
| HP            | Pavilion dv5                | [8be4ce3c5a](https://linux-hardware.org/?probe=8be4ce3c5a) | Nov 11, 2020 |
| Toshiba       | Satellite C660              | [a5ce6d0206](https://linux-hardware.org/?probe=a5ce6d0206) | Nov 11, 2020 |
| Notebook      | RIM2520                     | [771a897694](https://linux-hardware.org/?probe=771a897694) | Nov 11, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [2c5e88fe3a](https://linux-hardware.org/?probe=2c5e88fe3a) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [cb23a45745](https://linux-hardware.org/?probe=cb23a45745) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [ccdf1d9de6](https://linux-hardware.org/?probe=ccdf1d9de6) | Nov 10, 2020 |
| HP            | EliteBook 820 G2            | [d57310a957](https://linux-hardware.org/?probe=d57310a957) | Nov 10, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [4c0fec3ac5](https://linux-hardware.org/?probe=4c0fec3ac5) | Nov 09, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [d568aab65e](https://linux-hardware.org/?probe=d568aab65e) | Nov 09, 2020 |
| Lenovo        | S20-30 Touch 20434          | [bbac27d1f0](https://linux-hardware.org/?probe=bbac27d1f0) | Nov 08, 2020 |
| Lenovo        | ThinkPad T530 23595JU       | [2cce5c789a](https://linux-hardware.org/?probe=2cce5c789a) | Nov 08, 2020 |
| HP            | ENVY 15                     | [1fc6315caf](https://linux-hardware.org/?probe=1fc6315caf) | Nov 08, 2020 |
| HP            | ENVY 15                     | [996ca9b894](https://linux-hardware.org/?probe=996ca9b894) | Nov 08, 2020 |
| Dell          | Latitude D520               | [48ca9c477c](https://linux-hardware.org/?probe=48ca9c477c) | Nov 08, 2020 |
| Lenovo        | S20-30 Touch 20434          | [344bc8046a](https://linux-hardware.org/?probe=344bc8046a) | Nov 08, 2020 |
| HP            | Pavilion g6                 | [a1e12ac11a](https://linux-hardware.org/?probe=a1e12ac11a) | Nov 07, 2020 |
| HP            | 15                          | [a322932224](https://linux-hardware.org/?probe=a322932224) | Nov 07, 2020 |
| HP            | Pavilion g6                 | [c9fef7b025](https://linux-hardware.org/?probe=c9fef7b025) | Nov 07, 2020 |
| Toshiba       | Satellite C660              | [d5f99c156c](https://linux-hardware.org/?probe=d5f99c156c) | Nov 07, 2020 |
| Toshiba       | Satellite C660              | [45404bd97a](https://linux-hardware.org/?probe=45404bd97a) | Nov 07, 2020 |
| ASUSTek       | 1001PXD                     | [d50b2e1307](https://linux-hardware.org/?probe=d50b2e1307) | Nov 05, 2020 |
| Dell          | Inspiron 3421               | [e08c38affc](https://linux-hardware.org/?probe=e08c38affc) | Nov 04, 2020 |
| Dell          | Inspiron N7110              | [df14fcf89e](https://linux-hardware.org/?probe=df14fcf89e) | Nov 04, 2020 |
| HP            | Compaq Presario CQ60        | [dd9a86b9e4](https://linux-hardware.org/?probe=dd9a86b9e4) | Nov 04, 2020 |
| HP            | Compaq Presario CQ60        | [04db08c84c](https://linux-hardware.org/?probe=04db08c84c) | Nov 04, 2020 |
| Acer          | Aspire 5742G                | [9bc7704a4f](https://linux-hardware.org/?probe=9bc7704a4f) | Nov 02, 2020 |
| Packard Be... | EasyNote TJ65               | [f4459e22c9](https://linux-hardware.org/?probe=f4459e22c9) | Nov 02, 2020 |
| Acer          | Aspire V5-531               | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Acer          | Aspire 5742G                | [214289d932](https://linux-hardware.org/?probe=214289d932) | Oct 29, 2020 |
| HP            | 255 G5                      | [e0fe2872e1](https://linux-hardware.org/?probe=e0fe2872e1) | Oct 29, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [5e797005c4](https://linux-hardware.org/?probe=5e797005c4) | Oct 27, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3e49c517bb](https://linux-hardware.org/?probe=3e49c517bb) | Oct 25, 2020 |
| Acer          | Extensa 5635Z               | [c0b6900751](https://linux-hardware.org/?probe=c0b6900751) | Oct 24, 2020 |
| Toshiba       | Satellite P100              | [60e53b8e68](https://linux-hardware.org/?probe=60e53b8e68) | Oct 22, 2020 |
| Toshiba       | Satellite M70               | [b99abfd9d6](https://linux-hardware.org/?probe=b99abfd9d6) | Oct 21, 2020 |
| Sony          | SVE15115ENB                 | [fb5da6e89d](https://linux-hardware.org/?probe=fb5da6e89d) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6A... | [9565cc6937](https://linux-hardware.org/?probe=9565cc6937) | Oct 20, 2020 |
| HP            | Notebook                    | [8057d8104a](https://linux-hardware.org/?probe=8057d8104a) | Oct 19, 2020 |
| HP            | Compaq Presario CQ60        | [3b01f6d9e5](https://linux-hardware.org/?probe=3b01f6d9e5) | Oct 19, 2020 |
| HP            | Pavilion dv6                | [6fd2a79436](https://linux-hardware.org/?probe=6fd2a79436) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FA706IU_TUF70... | [4408c079e4](https://linux-hardware.org/?probe=4408c079e4) | Oct 17, 2020 |
| ASUSTek       | K53BR                       | [11d1b669d5](https://linux-hardware.org/?probe=11d1b669d5) | Oct 17, 2020 |
| Unknown       | Unknown                     | [4b9298725d](https://linux-hardware.org/?probe=4b9298725d) | Oct 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [3a3de52609](https://linux-hardware.org/?probe=3a3de52609) | Oct 16, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [7e7adfbb13](https://linux-hardware.org/?probe=7e7adfbb13) | Oct 16, 2020 |
| Dell          | Vostro 3578                 | [aca3bf63fc](https://linux-hardware.org/?probe=aca3bf63fc) | Oct 16, 2020 |
| Lenovo        | ThinkPad T400 64752C3       | [1729f0708e](https://linux-hardware.org/?probe=1729f0708e) | Oct 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [b572236a74](https://linux-hardware.org/?probe=b572236a74) | Oct 14, 2020 |
| Dell          | Inspiron 15-3567            | [42a82239c5](https://linux-hardware.org/?probe=42a82239c5) | Oct 13, 2020 |
| HP            | Mini 5103                   | [d51f4ebf17](https://linux-hardware.org/?probe=d51f4ebf17) | Oct 13, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [6c015911fb](https://linux-hardware.org/?probe=6c015911fb) | Oct 12, 2020 |
| HP            | 2000                        | [36cb1ae33f](https://linux-hardware.org/?probe=36cb1ae33f) | Oct 12, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [7f2d533ddf](https://linux-hardware.org/?probe=7f2d533ddf) | Oct 12, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [00f264d5ce](https://linux-hardware.org/?probe=00f264d5ce) | Oct 12, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [78f452a46b](https://linux-hardware.org/?probe=78f452a46b) | Oct 12, 2020 |
| HP            | Pavilion dv6                | [5b878286a6](https://linux-hardware.org/?probe=5b878286a6) | Oct 10, 2020 |
| Lenovo        | Kona                        | [7490728355](https://linux-hardware.org/?probe=7490728355) | Oct 09, 2020 |
| HP            | Notebook                    | [0d023159fc](https://linux-hardware.org/?probe=0d023159fc) | Oct 08, 2020 |
| HP            | Notebook                    | [60b847baba](https://linux-hardware.org/?probe=60b847baba) | Oct 08, 2020 |
| HP            | Pavilion Notebook           | [8e441f98e8](https://linux-hardware.org/?probe=8e441f98e8) | Oct 08, 2020 |
| ASUSTek       | G60VX                       | [737170838e](https://linux-hardware.org/?probe=737170838e) | Oct 07, 2020 |
| Panasonic     | CF-31JQH7MDM                | [bd9af285fe](https://linux-hardware.org/?probe=bd9af285fe) | Oct 07, 2020 |
| Dell          | Latitude E5470              | [a1ae53e261](https://linux-hardware.org/?probe=a1ae53e261) | Oct 06, 2020 |
| Dell          | Vostro 1510                 | [b2e8cb8306](https://linux-hardware.org/?probe=b2e8cb8306) | Oct 06, 2020 |
| Toshiba       | NB100                       | [0136048af7](https://linux-hardware.org/?probe=0136048af7) | Oct 06, 2020 |
| ASUSTek       | 1015PX                      | [4c53e6b790](https://linux-hardware.org/?probe=4c53e6b790) | Oct 05, 2020 |
| Acer          | AOD260                      | [df3f6056c4](https://linux-hardware.org/?probe=df3f6056c4) | Oct 05, 2020 |
| HP            | Presario C700 (GY219LA#A... | [4154ef951b](https://linux-hardware.org/?probe=4154ef951b) | Oct 03, 2020 |
| HP            | Presario C700 (GY219LA#A... | [322081e0c8](https://linux-hardware.org/?probe=322081e0c8) | Oct 03, 2020 |
| Fujitsu       | LIFEBOOK T730               | [79e7520c34](https://linux-hardware.org/?probe=79e7520c34) | Oct 02, 2020 |
| Fujitsu       | LIFEBOOK T730               | [df7fc1fcdd](https://linux-hardware.org/?probe=df7fc1fcdd) | Oct 02, 2020 |
| ASUSTek       | K54C                        | [b82b607833](https://linux-hardware.org/?probe=b82b607833) | Oct 02, 2020 |
| Toshiba       | Satellite A100              | [05371b4921](https://linux-hardware.org/?probe=05371b4921) | Oct 02, 2020 |
| HUAWEI        | HN-WX9X                     | [2b80873c58](https://linux-hardware.org/?probe=2b80873c58) | Oct 02, 2020 |
| Acer          | Aspire 6930G                | [e68197eded](https://linux-hardware.org/?probe=e68197eded) | Sep 30, 2020 |
| Apple         | MacBook5,2                  | [47c45ae46f](https://linux-hardware.org/?probe=47c45ae46f) | Sep 30, 2020 |
| Acer          | AOD270                      | [4d7f40e97b](https://linux-hardware.org/?probe=4d7f40e97b) | Sep 30, 2020 |
| Apple         | MacBookPro8,1               | [7b095a0a58](https://linux-hardware.org/?probe=7b095a0a58) | Sep 30, 2020 |
| ASUSTek       | K54C                        | [cf39adc51e](https://linux-hardware.org/?probe=cf39adc51e) | Sep 30, 2020 |
| ASUSTek       | K54C                        | [a15a6332bf](https://linux-hardware.org/?probe=a15a6332bf) | Sep 30, 2020 |
| Lenovo        | 3000 N200 0769B6G           | [7e9967fb0e](https://linux-hardware.org/?probe=7e9967fb0e) | Sep 30, 2020 |
| HP            | 530                         | [c330f06c15](https://linux-hardware.org/?probe=c330f06c15) | Sep 30, 2020 |
| HP            | ZBook 17 G2                 | [0d0b182c79](https://linux-hardware.org/?probe=0d0b182c79) | Sep 27, 2020 |
| Dell          | Latitude D630               | [fa947637f9](https://linux-hardware.org/?probe=fa947637f9) | Sep 25, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | [fffe9391c2](https://linux-hardware.org/?probe=fffe9391c2) | Sep 25, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [31e0cd8ca1](https://linux-hardware.org/?probe=31e0cd8ca1) | Sep 24, 2020 |
| Acer          | Extensa 5620                | [2cd43c8065](https://linux-hardware.org/?probe=2cd43c8065) | Sep 24, 2020 |
| HP            | Laptop 15-bw0xx             | [9067f67190](https://linux-hardware.org/?probe=9067f67190) | Sep 24, 2020 |
| Acer          | Swift SF314-42              | [03a2ad0203](https://linux-hardware.org/?probe=03a2ad0203) | Sep 23, 2020 |
| Sony          | VGN-SZ4VWN_X                | [b5f136ce13](https://linux-hardware.org/?probe=b5f136ce13) | Sep 23, 2020 |
| Fujitsu Si... | AMILO Li3710                | [4e11c10492](https://linux-hardware.org/?probe=4e11c10492) | Sep 23, 2020 |
| Fujitsu Si... | AMILO Li3710                | [a5d32c72d2](https://linux-hardware.org/?probe=a5d32c72d2) | Sep 23, 2020 |
| Sony          | VGN-CR120E                  | [8569f91c17](https://linux-hardware.org/?probe=8569f91c17) | Sep 23, 2020 |
| HP            | EliteBook 840 G4            | [adec24022c](https://linux-hardware.org/?probe=adec24022c) | Sep 22, 2020 |
| ASUSTek       | W7J                         | [70078e77fa](https://linux-hardware.org/?probe=70078e77fa) | Sep 22, 2020 |
| Acer          | Swift SF314-42              | [a243f6284c](https://linux-hardware.org/?probe=a243f6284c) | Sep 21, 2020 |
| Dell          | Inspiron 1110               | [01517be2d7](https://linux-hardware.org/?probe=01517be2d7) | Sep 20, 2020 |
| ASUSTek       | G74Sx                       | [76f3c2d574](https://linux-hardware.org/?probe=76f3c2d574) | Sep 20, 2020 |
| AMI           | Cherry Trail CR             | [a1343de48d](https://linux-hardware.org/?probe=a1343de48d) | Sep 20, 2020 |
| Toshiba       | Satellite C660              | [ba30a12748](https://linux-hardware.org/?probe=ba30a12748) | Sep 19, 2020 |
| HP            | ENVY Notebook               | [fab3ee0d2e](https://linux-hardware.org/?probe=fab3ee0d2e) | Sep 19, 2020 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [fe11f72b06](https://linux-hardware.org/?probe=fe11f72b06) | Sep 19, 2020 |
| HP            | ProBook 4540s               | [9ca21222f5](https://linux-hardware.org/?probe=9ca21222f5) | Sep 19, 2020 |
| HP            | Compaq Presario C700        | [4e8ba77ee3](https://linux-hardware.org/?probe=4e8ba77ee3) | Sep 18, 2020 |
| HP            | Compaq Presario C700        | [b9b510693c](https://linux-hardware.org/?probe=b9b510693c) | Sep 18, 2020 |
| Acer          | AO722                       | [d4c9b21741](https://linux-hardware.org/?probe=d4c9b21741) | Sep 18, 2020 |
| Toshiba       | NA 1402                     | [e1d38cee7f](https://linux-hardware.org/?probe=e1d38cee7f) | Sep 17, 2020 |
| HP            | Mini 210-1100               | [3b76e02a8f](https://linux-hardware.org/?probe=3b76e02a8f) | Sep 17, 2020 |
| Packard Be... | EasyNote ENTF71BM           | [b6c8ba71e9](https://linux-hardware.org/?probe=b6c8ba71e9) | Sep 17, 2020 |
| Packard Be... | EasyNote ENTF71BM           | [e09802de6b](https://linux-hardware.org/?probe=e09802de6b) | Sep 17, 2020 |
| HP            | Laptop 15-bw0xx             | [ca58f62a6f](https://linux-hardware.org/?probe=ca58f62a6f) | Sep 15, 2020 |
| Dell          | Inspiron 5577               | [17862346f8](https://linux-hardware.org/?probe=17862346f8) | Sep 15, 2020 |
| Acer          | Aspire 7520                 | [d8ae16fc0b](https://linux-hardware.org/?probe=d8ae16fc0b) | Sep 14, 2020 |
| Unknown       | Unknown                     | [2c52151f77](https://linux-hardware.org/?probe=2c52151f77) | Sep 13, 2020 |
| Acer          | AO722                       | [39f920ae53](https://linux-hardware.org/?probe=39f920ae53) | Sep 13, 2020 |
| Dell          | Inspiron 5577               | [dc9d469caf](https://linux-hardware.org/?probe=dc9d469caf) | Sep 12, 2020 |
| ASUSTek       | N750JK                      | [e140f6e3e4](https://linux-hardware.org/?probe=e140f6e3e4) | Sep 12, 2020 |
| Unknown       | Unknown                     | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| HP            | 530                         | [e0ea19e1dc](https://linux-hardware.org/?probe=e0ea19e1dc) | Sep 10, 2020 |
| HP            | Pavilion dv5                | [f5a369d166](https://linux-hardware.org/?probe=f5a369d166) | Sep 10, 2020 |
| HP            | Pavilion dv5                | [f9f9a9ca5f](https://linux-hardware.org/?probe=f9f9a9ca5f) | Sep 09, 2020 |
| Acer          | Aspire A315-21              | [07fb4fed45](https://linux-hardware.org/?probe=07fb4fed45) | Sep 08, 2020 |
| HP            | 530                         | [8d751d7d91](https://linux-hardware.org/?probe=8d751d7d91) | Sep 07, 2020 |
| Lenovo        | ThinkPad T520 4239CTO       | [fa8846ee61](https://linux-hardware.org/?probe=fa8846ee61) | Sep 07, 2020 |
| Dell          | Inspiron 5577               | [da6490c410](https://linux-hardware.org/?probe=da6490c410) | Sep 06, 2020 |
| Toshiba       | Satellite L855D             | [a14d72d23c](https://linux-hardware.org/?probe=a14d72d23c) | Sep 06, 2020 |
| ASUSTek       | W7J                         | [c505a80ea5](https://linux-hardware.org/?probe=c505a80ea5) | Sep 06, 2020 |
| Dell          | Vostro 3700                 | [c9b764a48b](https://linux-hardware.org/?probe=c9b764a48b) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | [4ddf924081](https://linux-hardware.org/?probe=4ddf924081) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | [23a0e05047](https://linux-hardware.org/?probe=23a0e05047) | Sep 05, 2020 |
| HP            | EliteBook 840 G6            | [4a5bac87d8](https://linux-hardware.org/?probe=4a5bac87d8) | Sep 04, 2020 |
| Dell          | Inspiron N4010              | [59357480b7](https://linux-hardware.org/?probe=59357480b7) | Sep 04, 2020 |
| Toshiba       | Satellite C650D             | [c661cb7e35](https://linux-hardware.org/?probe=c661cb7e35) | Sep 03, 2020 |
| HP            | Laptop 15-bw0xx             | [02c0bf156d](https://linux-hardware.org/?probe=02c0bf156d) | Sep 03, 2020 |
| HP            | Presario CQ57               | [2dcab385bd](https://linux-hardware.org/?probe=2dcab385bd) | Sep 03, 2020 |
| Dell          | Inspiron 3542               | [9661146a6a](https://linux-hardware.org/?probe=9661146a6a) | Sep 02, 2020 |
| Acer          | Aspire one                  | [37b4d70de4](https://linux-hardware.org/?probe=37b4d70de4) | Sep 01, 2020 |
| Toshiba       | Satellite C55-A-16D         | [ffb7e1e547](https://linux-hardware.org/?probe=ffb7e1e547) | Aug 31, 2020 |
| Dell          | Inspiron 15-3567            | [f9903ce5d2](https://linux-hardware.org/?probe=f9903ce5d2) | Aug 31, 2020 |
| Toshiba       | Satellite Pro L550          | [02e28c5706](https://linux-hardware.org/?probe=02e28c5706) | Aug 30, 2020 |
| Apple         | MacBookAir3,1               | [a3168c57ea](https://linux-hardware.org/?probe=a3168c57ea) | Aug 30, 2020 |
| Dell          | Inspiron 1520               | [6d520f3f75](https://linux-hardware.org/?probe=6d520f3f75) | Aug 29, 2020 |
| HP            | Laptop 14-dk1xxx            | [f72e36a4c1](https://linux-hardware.org/?probe=f72e36a4c1) | Aug 28, 2020 |
| Dell          | Inspiron N4010              | [f80559862a](https://linux-hardware.org/?probe=f80559862a) | Aug 27, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [a2b597141c](https://linux-hardware.org/?probe=a2b597141c) | Aug 27, 2020 |
| HP            | Pavilion g4                 | [55dec82070](https://linux-hardware.org/?probe=55dec82070) | Aug 26, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [de3f00fc50](https://linux-hardware.org/?probe=de3f00fc50) | Aug 26, 2020 |
| Lenovo        | G475 20080                  | [c97ad59308](https://linux-hardware.org/?probe=c97ad59308) | Aug 26, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6b7781d4f0](https://linux-hardware.org/?probe=6b7781d4f0) | Aug 25, 2020 |
| Acer          | Aspire one                  | [ea29714624](https://linux-hardware.org/?probe=ea29714624) | Aug 24, 2020 |
| Acer          | Aspire A515-52G             | [86a890eb18](https://linux-hardware.org/?probe=86a890eb18) | Aug 23, 2020 |
| Acer          | Aspire A515-52G             | [5034bf6bc3](https://linux-hardware.org/?probe=5034bf6bc3) | Aug 23, 2020 |
| Dell          | Inspiron MM061              | [a34d3a0236](https://linux-hardware.org/?probe=a34d3a0236) | Aug 22, 2020 |
| Unknown       | Unknown                     | [858431dd69](https://linux-hardware.org/?probe=858431dd69) | Aug 22, 2020 |
| HP            | EliteBook 725 G2            | [f9f5c68624](https://linux-hardware.org/?probe=f9f5c68624) | Aug 22, 2020 |
| Dell          | Inspiron 1545               | [0502d22a6e](https://linux-hardware.org/?probe=0502d22a6e) | Aug 22, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [955166808e](https://linux-hardware.org/?probe=955166808e) | Aug 22, 2020 |
| Lenovo        | 4068RZ7                     | [a019743ebe](https://linux-hardware.org/?probe=a019743ebe) | Aug 20, 2020 |
| Lenovo        | 4068RZ7                     | [8b55712014](https://linux-hardware.org/?probe=8b55712014) | Aug 20, 2020 |
| Dell          | Inspiron 1545               | [20a0eaa36a](https://linux-hardware.org/?probe=20a0eaa36a) | Aug 20, 2020 |
| Toshiba       | Satellite L670D             | [746e1de754](https://linux-hardware.org/?probe=746e1de754) | Aug 19, 2020 |
| Unknown       | Unknown                     | [55906c4bf1](https://linux-hardware.org/?probe=55906c4bf1) | Aug 19, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [47f5ea43b8](https://linux-hardware.org/?probe=47f5ea43b8) | Aug 18, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [712e524505](https://linux-hardware.org/?probe=712e524505) | Aug 18, 2020 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [188c3f31c6](https://linux-hardware.org/?probe=188c3f31c6) | Aug 18, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [55d79e4d6a](https://linux-hardware.org/?probe=55d79e4d6a) | Aug 17, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [19b6cecfad](https://linux-hardware.org/?probe=19b6cecfad) | Aug 17, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [5faf279c4f](https://linux-hardware.org/?probe=5faf279c4f) | Aug 17, 2020 |
| HP            | Laptop 15-bs0xx             | [45004f5195](https://linux-hardware.org/?probe=45004f5195) | Aug 17, 2020 |
| Medion        | ERAZER X7853 MD60604        | [1216fcc86c](https://linux-hardware.org/?probe=1216fcc86c) | Aug 16, 2020 |
| Medion        | ERAZER X7853 MD60604        | [6be345d7bd](https://linux-hardware.org/?probe=6be345d7bd) | Aug 16, 2020 |
| Samsung       | 400B4B/400B5B/200B4B/200... | [299e17392c](https://linux-hardware.org/?probe=299e17392c) | Aug 15, 2020 |
| Acer          | Aspire one                  | [c2802686dc](https://linux-hardware.org/?probe=c2802686dc) | Aug 15, 2020 |
| Dell          | G5 5505                     | [9d7d4c771b](https://linux-hardware.org/?probe=9d7d4c771b) | Aug 14, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [72b1361358](https://linux-hardware.org/?probe=72b1361358) | Aug 13, 2020 |
| Toshiba       | STI NA 1402                 | [d75672b88f](https://linux-hardware.org/?probe=d75672b88f) | Aug 13, 2020 |
| Alienware     | 15                          | [4b1d9f9153](https://linux-hardware.org/?probe=4b1d9f9153) | Aug 13, 2020 |
| Alienware     | 15                          | [dfde91faf2](https://linux-hardware.org/?probe=dfde91faf2) | Aug 13, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [7aa50f99e0](https://linux-hardware.org/?probe=7aa50f99e0) | Aug 13, 2020 |
| Toshiba       | Satellite C650              | [0b2880b414](https://linux-hardware.org/?probe=0b2880b414) | Aug 12, 2020 |
| Dell          | G5 5505                     | [c4a555abaa](https://linux-hardware.org/?probe=c4a555abaa) | Aug 12, 2020 |
| Acer          | Aspire 5715Z                | [c96a3eeac7](https://linux-hardware.org/?probe=c96a3eeac7) | Aug 12, 2020 |
| MSI           | GT72 2PC                    | [464657ada9](https://linux-hardware.org/?probe=464657ada9) | Aug 11, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [a95dcd9354](https://linux-hardware.org/?probe=a95dcd9354) | Aug 11, 2020 |
| Acer          | Aspire 5532                 | [6d1ed17c3a](https://linux-hardware.org/?probe=6d1ed17c3a) | Aug 10, 2020 |
| HP            | 255 G3                      | [4d659eb265](https://linux-hardware.org/?probe=4d659eb265) | Aug 10, 2020 |
| Bluechip C... | Crestline & ICH8M Chipse... | [9b8c4353cc](https://linux-hardware.org/?probe=9b8c4353cc) | Aug 09, 2020 |
| HP            | G62                         | [79f5cf8c86](https://linux-hardware.org/?probe=79f5cf8c86) | Aug 08, 2020 |
| HP            | 14                          | [b7289075c1](https://linux-hardware.org/?probe=b7289075c1) | Aug 08, 2020 |
| Acer          | Aspire 5742G                | [9e136aade0](https://linux-hardware.org/?probe=9e136aade0) | Aug 07, 2020 |
| Dell          | Vostro 15-3568              | [3b1e04b2da](https://linux-hardware.org/?probe=3b1e04b2da) | Aug 07, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [df9004d133](https://linux-hardware.org/?probe=df9004d133) | Aug 07, 2020 |
| HP            | ProBook 650 G1              | [3790f3b233](https://linux-hardware.org/?probe=3790f3b233) | Aug 07, 2020 |
| Toshiba       | Satellite C55-A             | [8fb6762361](https://linux-hardware.org/?probe=8fb6762361) | Aug 06, 2020 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [b9fddd15e8](https://linux-hardware.org/?probe=b9fddd15e8) | Aug 05, 2020 |
| Toshiba       | Satellite L670D             | [d28122373c](https://linux-hardware.org/?probe=d28122373c) | Aug 05, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [2ac44f315b](https://linux-hardware.org/?probe=2ac44f315b) | Aug 05, 2020 |
| Toshiba       | Satellite L670D             | [c204b4536e](https://linux-hardware.org/?probe=c204b4536e) | Aug 05, 2020 |
| HP            | EliteBook 8460p             | [452088e655](https://linux-hardware.org/?probe=452088e655) | Aug 03, 2020 |
| Dell          | Inspiron MP061              | [7355e190ca](https://linux-hardware.org/?probe=7355e190ca) | Aug 03, 2020 |
| HP            | Pavilion g4                 | [4fc16d6e09](https://linux-hardware.org/?probe=4fc16d6e09) | Aug 02, 2020 |
| HP            | Pavilion g4                 | [0b9fc56cd1](https://linux-hardware.org/?probe=0b9fc56cd1) | Aug 02, 2020 |
| Unknown       | Unknown                     | [59c9ce7401](https://linux-hardware.org/?probe=59c9ce7401) | Aug 02, 2020 |
| Dell          | Latitude E5450              | [884ee42c35](https://linux-hardware.org/?probe=884ee42c35) | Aug 01, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [f70de4a51f](https://linux-hardware.org/?probe=f70de4a51f) | Aug 01, 2020 |
| ASUSTek       | GX501VIK                    | [de4780e6e4](https://linux-hardware.org/?probe=de4780e6e4) | Aug 01, 2020 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [18b9136e87](https://linux-hardware.org/?probe=18b9136e87) | Aug 01, 2020 |
| HP            | G62                         | [1ba7e38fa9](https://linux-hardware.org/?probe=1ba7e38fa9) | Aug 01, 2020 |
| HP            | G62                         | [2c304963c6](https://linux-hardware.org/?probe=2c304963c6) | Jul 31, 2020 |
| Dell          | Inspiron N5050              | [cb18c38bd3](https://linux-hardware.org/?probe=cb18c38bd3) | Jul 30, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [dc8ed0c837](https://linux-hardware.org/?probe=dc8ed0c837) | Jul 30, 2020 |
| HP            | EliteBook 2760p             | [ef84151f18](https://linux-hardware.org/?probe=ef84151f18) | Jul 29, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3db826b463](https://linux-hardware.org/?probe=3db826b463) | Jul 29, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [3fd417f684](https://linux-hardware.org/?probe=3fd417f684) | Jul 29, 2020 |
| HP            | ProBook 6470b               | [fe3206ee5f](https://linux-hardware.org/?probe=fe3206ee5f) | Jul 28, 2020 |
| Toshiba       | Satellite L670D             | [91a4aad7d7](https://linux-hardware.org/?probe=91a4aad7d7) | Jul 28, 2020 |
| Toshiba       | Satellite L670D             | [10658a729f](https://linux-hardware.org/?probe=10658a729f) | Jul 28, 2020 |
| HP            | 1000                        | [d0cdc87248](https://linux-hardware.org/?probe=d0cdc87248) | Jul 27, 2020 |
| Lenovo        | G560 20042                  | [fb76f0edee](https://linux-hardware.org/?probe=fb76f0edee) | Jul 27, 2020 |
| Acer          | Aspire 5741                 | [6fa0f96d6b](https://linux-hardware.org/?probe=6fa0f96d6b) | Jul 27, 2020 |
| HP            | 1000                        | [36db752887](https://linux-hardware.org/?probe=36db752887) | Jul 26, 2020 |
| Sony          | VPCYB35AB                   | [6cc28f56ff](https://linux-hardware.org/?probe=6cc28f56ff) | Jul 26, 2020 |
| Sony          | VPCYB35AB                   | [4b5b2115c1](https://linux-hardware.org/?probe=4b5b2115c1) | Jul 26, 2020 |
| ASUSTek       | G750JM                      | [9b3a5ac253](https://linux-hardware.org/?probe=9b3a5ac253) | Jul 25, 2020 |
| Dell          | Inspiron 1545               | [57675258c0](https://linux-hardware.org/?probe=57675258c0) | Jul 25, 2020 |
| Compal        | HGL31I                      | [8f7aac30a8](https://linux-hardware.org/?probe=8f7aac30a8) | Jul 25, 2020 |
| Dell          | Latitude E6420              | [0de23594ba](https://linux-hardware.org/?probe=0de23594ba) | Jul 24, 2020 |
| Acer          | Aspire 5750                 | [fbb8795c20](https://linux-hardware.org/?probe=fbb8795c20) | Jul 24, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [c9eb825434](https://linux-hardware.org/?probe=c9eb825434) | Jul 24, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [8dd238e5a1](https://linux-hardware.org/?probe=8dd238e5a1) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d65a2f5a5a](https://linux-hardware.org/?probe=d65a2f5a5a) | Jul 24, 2020 |
| HP            | 14                          | [143464e093](https://linux-hardware.org/?probe=143464e093) | Jul 24, 2020 |
| Dell          | Vostro 3460                 | [ecdbc21896](https://linux-hardware.org/?probe=ecdbc21896) | Jul 24, 2020 |
| Acer          | Aspire 5715Z                | [68f23b69e9](https://linux-hardware.org/?probe=68f23b69e9) | Jul 22, 2020 |
| Positivo      | Mobile                      | [b5b4e22b05](https://linux-hardware.org/?probe=b5b4e22b05) | Jul 21, 2020 |
| Dell          | Vostro 15-3568              | [7ef51b8ffe](https://linux-hardware.org/?probe=7ef51b8ffe) | Jul 20, 2020 |
| Dell          | Vostro 15-3568              | [7ba1b7b850](https://linux-hardware.org/?probe=7ba1b7b850) | Jul 19, 2020 |
| Digibras      | NH4CU03                     | [3bad8b713e](https://linux-hardware.org/?probe=3bad8b713e) | Jul 19, 2020 |
| HP            | ElitePad 1000 G2            | [a8871cdcff](https://linux-hardware.org/?probe=a8871cdcff) | Jul 19, 2020 |
| HP            | Notebook                    | [875e3886d1](https://linux-hardware.org/?probe=875e3886d1) | Jul 18, 2020 |
| HP            | ElitePad 1000 G2            | [58738fe100](https://linux-hardware.org/?probe=58738fe100) | Jul 17, 2020 |
| Dell          | Studio 1737                 | [b08787e998](https://linux-hardware.org/?probe=b08787e998) | Jul 17, 2020 |
| Acer          | Aspire 5715Z                | [929559cae0](https://linux-hardware.org/?probe=929559cae0) | Jul 17, 2020 |
| HP            | Laptop 14-dq1xxx            | [1e49fe5909](https://linux-hardware.org/?probe=1e49fe5909) | Jul 16, 2020 |
| Google        | Chell                       | [fb663766c0](https://linux-hardware.org/?probe=fb663766c0) | Jul 16, 2020 |
| Google        | Chell                       | [af33f4bc7b](https://linux-hardware.org/?probe=af33f4bc7b) | Jul 15, 2020 |
| HP            | EliteBook 840 G2            | [a2a8e9d267](https://linux-hardware.org/?probe=a2a8e9d267) | Jul 13, 2020 |
| Sony          | VGN-P11Z_G                  | [7615c6d02b](https://linux-hardware.org/?probe=7615c6d02b) | Jul 11, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [8164d6222a](https://linux-hardware.org/?probe=8164d6222a) | Jul 11, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [478d2b6718](https://linux-hardware.org/?probe=478d2b6718) | Jul 11, 2020 |
| Lenovo        | BP PV CLASSMATE+            | [0e381612fb](https://linux-hardware.org/?probe=0e381612fb) | Jul 11, 2020 |
| Toshiba       | Satellite C660              | [b15da8cdfc](https://linux-hardware.org/?probe=b15da8cdfc) | Jul 11, 2020 |
| HP            | ElitePad 1000 G2            | [b2c793bfb4](https://linux-hardware.org/?probe=b2c793bfb4) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [152f8e9ebd](https://linux-hardware.org/?probe=152f8e9ebd) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [5054174795](https://linux-hardware.org/?probe=5054174795) | Jul 08, 2020 |
| ASUSTek       | GX501VIK                    | [0dc513d440](https://linux-hardware.org/?probe=0dc513d440) | Jul 07, 2020 |
| UMAX          | Visionbook 14Wg Pro         | [5d2b6ed775](https://linux-hardware.org/?probe=5d2b6ed775) | Jul 06, 2020 |
| UMAX          | Visionbook 14Wg Pro         | [ef59c33668](https://linux-hardware.org/?probe=ef59c33668) | Jul 06, 2020 |
| Dell          | Latitude E6520              | [c11c08470c](https://linux-hardware.org/?probe=c11c08470c) | Jul 06, 2020 |
| Dell          | Latitude E6520              | [d3b4a01055](https://linux-hardware.org/?probe=d3b4a01055) | Jul 06, 2020 |
| ECS           | G410                        | [38bad5d8cb](https://linux-hardware.org/?probe=38bad5d8cb) | Jul 05, 2020 |
| Samsung       | N150                        | [76e856e9e9](https://linux-hardware.org/?probe=76e856e9e9) | Jul 04, 2020 |
| Samsung       | N150                        | [cf90fb442b](https://linux-hardware.org/?probe=cf90fb442b) | Jul 04, 2020 |
| Lenovo        | ThinkPad X140e 20BMS00E0... | [ee2280ecd4](https://linux-hardware.org/?probe=ee2280ecd4) | Jul 04, 2020 |
| Toshiba       | Satellite C40-A             | [672cca96fd](https://linux-hardware.org/?probe=672cca96fd) | Jul 04, 2020 |
| Acer          | Aspire 5000                 | [c3722a65f4](https://linux-hardware.org/?probe=c3722a65f4) | Jul 04, 2020 |
| WIPRO         | WIVNB7B1623-0002            | [4669989193](https://linux-hardware.org/?probe=4669989193) | Jul 03, 2020 |
| Acer          | Aspire 5000                 | [d91f2c3af1](https://linux-hardware.org/?probe=d91f2c3af1) | Jul 03, 2020 |
| Dell          | Latitude E6440              | [521818b099](https://linux-hardware.org/?probe=521818b099) | Jul 02, 2020 |
| HP            | ProBook 450 G3              | [cf66568c1a](https://linux-hardware.org/?probe=cf66568c1a) | Jul 01, 2020 |
| HP            | Notebook                    | [1b077e7d7e](https://linux-hardware.org/?probe=1b077e7d7e) | Jun 30, 2020 |
| HP            | G60                         | [2c11d20a74](https://linux-hardware.org/?probe=2c11d20a74) | Jun 29, 2020 |
| Toshiba       | Satellite C645              | [962d89d16d](https://linux-hardware.org/?probe=962d89d16d) | Jun 29, 2020 |
| Toshiba       | Satellite C645              | [bec8895749](https://linux-hardware.org/?probe=bec8895749) | Jun 29, 2020 |
| Toshiba       | Satellite S50-B             | [2e8165ca6a](https://linux-hardware.org/?probe=2e8165ca6a) | Jun 28, 2020 |
| Dell          | Inspiron 1525               | [754b2de717](https://linux-hardware.org/?probe=754b2de717) | Jun 27, 2020 |
| Dell          | Vostro 3450                 | [6ecdf91891](https://linux-hardware.org/?probe=6ecdf91891) | Jun 27, 2020 |
| Alienware     | M17x                        | [4a26920858](https://linux-hardware.org/?probe=4a26920858) | Jun 26, 2020 |
| Toshiba       | Satellite L655              | [d03c7bb948](https://linux-hardware.org/?probe=d03c7bb948) | Jun 26, 2020 |
| Toshiba       | Satellite L655              | [002ace5d32](https://linux-hardware.org/?probe=002ace5d32) | Jun 26, 2020 |
| Acer          | Aspire A515-51              | [636d176056](https://linux-hardware.org/?probe=636d176056) | Jun 25, 2020 |
| Dell          | Latitude E6440              | [1ffde1aa78](https://linux-hardware.org/?probe=1ffde1aa78) | Jun 24, 2020 |
| UMAX          | Visionbook 14Wg Pro         | [a50a75e674](https://linux-hardware.org/?probe=a50a75e674) | Jun 21, 2020 |
| HP            | EliteBook 6930p             | [afcfa0b2bb](https://linux-hardware.org/?probe=afcfa0b2bb) | Jun 21, 2020 |
| Acer          | Aspire S3                   | [431c5f1360](https://linux-hardware.org/?probe=431c5f1360) | Jun 20, 2020 |
| Acer          | Aspire S3                   | [2ecc528f99](https://linux-hardware.org/?probe=2ecc528f99) | Jun 20, 2020 |
| ASUSTek       | TP300LA                     | [a24e3e59e4](https://linux-hardware.org/?probe=a24e3e59e4) | Jun 20, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [c2f7f39a83](https://linux-hardware.org/?probe=c2f7f39a83) | Jun 20, 2020 |
| HP            | ProBook 6470b               | [37be0cfc66](https://linux-hardware.org/?probe=37be0cfc66) | Jun 19, 2020 |
| Lenovo        | G50-30 80G0                 | [d9f9497fd7](https://linux-hardware.org/?probe=d9f9497fd7) | Jun 19, 2020 |
| Qbex          | K131                        | [4f86406fcd](https://linux-hardware.org/?probe=4f86406fcd) | Jun 18, 2020 |
| Toshiba       | Satellite C55D-B            | [8e66b0c5f9](https://linux-hardware.org/?probe=8e66b0c5f9) | Jun 17, 2020 |
| HP            | Pavilion dm1                | [cfa6ec6eee](https://linux-hardware.org/?probe=cfa6ec6eee) | Jun 17, 2020 |
| HP            | Laptop 15-bw0xx             | [b19bfe7909](https://linux-hardware.org/?probe=b19bfe7909) | Jun 16, 2020 |
| HP            | Compaq Mini                 | [bb593c0696](https://linux-hardware.org/?probe=bb593c0696) | Jun 16, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [006200c0c0](https://linux-hardware.org/?probe=006200c0c0) | Jun 16, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [e93673aae9](https://linux-hardware.org/?probe=e93673aae9) | Jun 15, 2020 |
| Dell          | Inspiron 14-3452            | [c83e4c2dd8](https://linux-hardware.org/?probe=c83e4c2dd8) | Jun 15, 2020 |
| Samsung       | N130                        | [4e60aa279e](https://linux-hardware.org/?probe=4e60aa279e) | Jun 14, 2020 |
| HP            | ProBook 6470b               | [f5cc0bfea1](https://linux-hardware.org/?probe=f5cc0bfea1) | Jun 14, 2020 |
| Toshiba       | Satellite C55-A             | [7c435001c2](https://linux-hardware.org/?probe=7c435001c2) | Jun 14, 2020 |
| HP            | EliteBook 6930p             | [521bd09de6](https://linux-hardware.org/?probe=521bd09de6) | Jun 13, 2020 |
| ASUSTek       | K75DE                       | [ab5984d317](https://linux-hardware.org/?probe=ab5984d317) | Jun 13, 2020 |
| ASUSTek       | K75DE                       | [3a77ccc6d1](https://linux-hardware.org/?probe=3a77ccc6d1) | Jun 13, 2020 |
| HP            | ProBook 450 G3              | [7c8e952de0](https://linux-hardware.org/?probe=7c8e952de0) | Jun 12, 2020 |
| HP            | ENVY TS m7                  | [3186cbcb82](https://linux-hardware.org/?probe=3186cbcb82) | Jun 12, 2020 |
| ASUSTek       | UX331UA                     | [064e95c086](https://linux-hardware.org/?probe=064e95c086) | Jun 10, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [16396354a6](https://linux-hardware.org/?probe=16396354a6) | Jun 10, 2020 |
| Apple         | MacBookAir3,1               | [e31264d63b](https://linux-hardware.org/?probe=e31264d63b) | Jun 09, 2020 |
| Apple         | MacBookAir3,1               | [7ebb47dc43](https://linux-hardware.org/?probe=7ebb47dc43) | Jun 09, 2020 |
| Acer          | AOD270                      | [3a0d567ba7](https://linux-hardware.org/?probe=3a0d567ba7) | Jun 09, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [27b21d21f9](https://linux-hardware.org/?probe=27b21d21f9) | Jun 09, 2020 |
| Toshiba       | PORTEGE Z20t-C              | [4e2285206e](https://linux-hardware.org/?probe=4e2285206e) | Jun 07, 2020 |
| HP            | Laptop 17-by0xxx            | [95415bf222](https://linux-hardware.org/?probe=95415bf222) | Jun 06, 2020 |
| HP            | Laptop 17-by0xxx            | [9fb0632ef6](https://linux-hardware.org/?probe=9fb0632ef6) | Jun 06, 2020 |
| Fujitsu Si... | LIFEBOOK S7220              | [f3c44830da](https://linux-hardware.org/?probe=f3c44830da) | Jun 06, 2020 |
| Toshiba       | Satellite A100              | [eddce8db1a](https://linux-hardware.org/?probe=eddce8db1a) | Jun 05, 2020 |
| HP            | Pavilion dv6700             | [a53258f04c](https://linux-hardware.org/?probe=a53258f04c) | Jun 05, 2020 |
| ASUSTek       | X555LD                      | [5fcb4e6866](https://linux-hardware.org/?probe=5fcb4e6866) | Jun 03, 2020 |
| Dell          | Latitude XT2                | [5970770ec5](https://linux-hardware.org/?probe=5970770ec5) | Jun 03, 2020 |
| Dell          | Latitude XT2                | [bc35b5f660](https://linux-hardware.org/?probe=bc35b5f660) | Jun 03, 2020 |
| Dell          | Latitude XT2                | [0f863604a4](https://linux-hardware.org/?probe=0f863604a4) | Jun 03, 2020 |
| ASUSTek       | ROG Strix G531GT_G531GT     | [76c2001b93](https://linux-hardware.org/?probe=76c2001b93) | Jun 03, 2020 |
| ASUSTek       | UX331UA                     | [8ca766622f](https://linux-hardware.org/?probe=8ca766622f) | Jun 02, 2020 |
| HP            | EliteBook 8770w             | [9bba8e0daf](https://linux-hardware.org/?probe=9bba8e0daf) | Jun 01, 2020 |
| Lenovo        | ThinkPad W520 42844LG       | [9bc21e2e76](https://linux-hardware.org/?probe=9bc21e2e76) | Jun 01, 2020 |
| Dell          | Vostro 5470                 | [c519aedd88](https://linux-hardware.org/?probe=c519aedd88) | Jun 01, 2020 |
| Acer          | Aspire A315-51              | [b524806f7a](https://linux-hardware.org/?probe=b524806f7a) | May 31, 2020 |
| HP            | Pavilion dv6000 (RP986EA... | [1e4d134edf](https://linux-hardware.org/?probe=1e4d134edf) | May 30, 2020 |
| HP            | 635                         | [4c1e9766eb](https://linux-hardware.org/?probe=4c1e9766eb) | May 30, 2020 |
| HP            | Laptop 15-dw0xxx            | [3717bb5ab4](https://linux-hardware.org/?probe=3717bb5ab4) | May 29, 2020 |
| Notebook      | P570WM                      | [1694f6a1b4](https://linux-hardware.org/?probe=1694f6a1b4) | May 28, 2020 |
| Insyde        | TW36                        | [7038a5c61c](https://linux-hardware.org/?probe=7038a5c61c) | May 28, 2020 |
| Dell          | Inspiron 5480               | [aeaf1790c2](https://linux-hardware.org/?probe=aeaf1790c2) | May 28, 2020 |
| HP            | 635                         | [fec1f36696](https://linux-hardware.org/?probe=fec1f36696) | May 27, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [0508854129](https://linux-hardware.org/?probe=0508854129) | May 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [e6a298846b](https://linux-hardware.org/?probe=e6a298846b) | May 27, 2020 |
| Dell          | Latitude XT2                | [760d50a6bc](https://linux-hardware.org/?probe=760d50a6bc) | May 26, 2020 |
| Durabook      | S15H                        | [2599b1778a](https://linux-hardware.org/?probe=2599b1778a) | May 26, 2020 |
| Durabook      | S15H                        | [3563afb99e](https://linux-hardware.org/?probe=3563afb99e) | May 26, 2020 |
| Dell          | Inspiron 14-3452            | [33a29d72b1](https://linux-hardware.org/?probe=33a29d72b1) | May 26, 2020 |
| Dell          | Inspiron 14-3452            | [f894499ac3](https://linux-hardware.org/?probe=f894499ac3) | May 26, 2020 |
| Dell          | Inspiron 1440               | [51cbf53227](https://linux-hardware.org/?probe=51cbf53227) | May 26, 2020 |
| HP            | 15                          | [c39075bd80](https://linux-hardware.org/?probe=c39075bd80) | May 25, 2020 |
| Lenovo        | ThinkPad X140e 20BMS00E0... | [38efdd0635](https://linux-hardware.org/?probe=38efdd0635) | May 25, 2020 |
| ASUSTek       | Z450LA                      | [e64dcdf564](https://linux-hardware.org/?probe=e64dcdf564) | May 24, 2020 |
| Lenovo        | ThinkPad X140e 20BMS00E0... | [edc9f5d43a](https://linux-hardware.org/?probe=edc9f5d43a) | May 24, 2020 |
| Acer          | Aspire one                  | [610bb91d45](https://linux-hardware.org/?probe=610bb91d45) | May 23, 2020 |
| ASUSTek       | P552SA                      | [cd07bb014c](https://linux-hardware.org/?probe=cd07bb014c) | May 23, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [43e3fadb97](https://linux-hardware.org/?probe=43e3fadb97) | May 23, 2020 |
| Acer          | Aspire 5755G                | [58e9aedfca](https://linux-hardware.org/?probe=58e9aedfca) | May 23, 2020 |
| Acer          | AOD270                      | [1f0edfd757](https://linux-hardware.org/?probe=1f0edfd757) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | [206613fa48](https://linux-hardware.org/?probe=206613fa48) | May 22, 2020 |
| Lenovo        | V145-15AST 81MT             | [6570cd4d9d](https://linux-hardware.org/?probe=6570cd4d9d) | May 22, 2020 |
| HP            | Pavilion (EC436AV#ABA)      | [16430a960e](https://linux-hardware.org/?probe=16430a960e) | May 22, 2020 |
| Acer          | AOD270                      | [e254f3b7e5](https://linux-hardware.org/?probe=e254f3b7e5) | May 22, 2020 |
| Sony          | VGN-AW11Z_B                 | [71a7a9f1f3](https://linux-hardware.org/?probe=71a7a9f1f3) | May 22, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [29131d3d86](https://linux-hardware.org/?probe=29131d3d86) | May 21, 2020 |
| HP            | ZBook 17 G5                 | [81b70e2c63](https://linux-hardware.org/?probe=81b70e2c63) | May 21, 2020 |
| ASUSTek       | 1005P                       | [a2b309ff12](https://linux-hardware.org/?probe=a2b309ff12) | May 21, 2020 |
| HP            | EliteBook 840 G1            | [a39e33b1f4](https://linux-hardware.org/?probe=a39e33b1f4) | May 20, 2020 |
| HP            | EliteBook 840 G1            | [4f773edbaa](https://linux-hardware.org/?probe=4f773edbaa) | May 20, 2020 |
| Dell          | Inspiron 1420               | [1269d54a19](https://linux-hardware.org/?probe=1269d54a19) | May 20, 2020 |
| ASUSTek       | K84L                        | [01c734a603](https://linux-hardware.org/?probe=01c734a603) | May 19, 2020 |
| Acer          | Aspire ES1-711              | [f0d922b2a0](https://linux-hardware.org/?probe=f0d922b2a0) | May 19, 2020 |
| ASUSTek       | K50AB                       | [96ccf326a8](https://linux-hardware.org/?probe=96ccf326a8) | May 19, 2020 |
| Advantec      | CX23200W                    | [3c46531687](https://linux-hardware.org/?probe=3c46531687) | May 18, 2020 |
| HP            | EliteBook 6930p             | [c9c059345d](https://linux-hardware.org/?probe=c9c059345d) | May 18, 2020 |
| HP            | EliteBook 6930p             | [0659c564f2](https://linux-hardware.org/?probe=0659c564f2) | May 17, 2020 |
| Dell          | Latitude E5570              | [7e63fb0312](https://linux-hardware.org/?probe=7e63fb0312) | May 17, 2020 |
| HP            | Presario V5000 (EX096PA#... | [f3c46cc46c](https://linux-hardware.org/?probe=f3c46cc46c) | May 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [97b8fc8686](https://linux-hardware.org/?probe=97b8fc8686) | May 17, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [ccaf6537a8](https://linux-hardware.org/?probe=ccaf6537a8) | May 17, 2020 |
| Lenovo        | Lenovo                      | [ff60458293](https://linux-hardware.org/?probe=ff60458293) | May 17, 2020 |
| Lenovo        | Lenovo                      | [04a22263e1](https://linux-hardware.org/?probe=04a22263e1) | May 17, 2020 |
| Lenovo        | Lenovo                      | [2176e7fb78](https://linux-hardware.org/?probe=2176e7fb78) | May 17, 2020 |
| Samsung       | N150P/N210P/N220P           | [ef94f890dd](https://linux-hardware.org/?probe=ef94f890dd) | May 16, 2020 |
| Acer          | V5-131                      | [9d9e227434](https://linux-hardware.org/?probe=9d9e227434) | May 16, 2020 |
| Acer          | AO722                       | [822175ace8](https://linux-hardware.org/?probe=822175ace8) | May 16, 2020 |
| Samsung       | R425D/R525D                 | [8e54082560](https://linux-hardware.org/?probe=8e54082560) | May 16, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [3784b38e25](https://linux-hardware.org/?probe=3784b38e25) | May 16, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V6555        | [abf8542459](https://linux-hardware.org/?probe=abf8542459) | May 16, 2020 |
| ASUSTek       | UX331UA                     | [0a0319493d](https://linux-hardware.org/?probe=0a0319493d) | May 15, 2020 |
| Acer          | Aspire 8943G                | [1b520f3904](https://linux-hardware.org/?probe=1b520f3904) | May 15, 2020 |
| MSI           | GL63 8RD                    | [c291440c2f](https://linux-hardware.org/?probe=c291440c2f) | May 14, 2020 |
| MSI           | GL63 8RD                    | [96120d0ebb](https://linux-hardware.org/?probe=96120d0ebb) | May 14, 2020 |
| HP            | Pavilion dv7                | [d7bfa6ea91](https://linux-hardware.org/?probe=d7bfa6ea91) | May 13, 2020 |
| HP            | Notebook                    | [dbed542e5a](https://linux-hardware.org/?probe=dbed542e5a) | May 12, 2020 |
| Dell          | Latitude E6330              | [7f58dd399d](https://linux-hardware.org/?probe=7f58dd399d) | May 12, 2020 |
| Dell          | Latitude E6330              | [1e167b4d43](https://linux-hardware.org/?probe=1e167b4d43) | May 12, 2020 |
| Dell          | Precision M4800             | [028edf486d](https://linux-hardware.org/?probe=028edf486d) | May 11, 2020 |
| Durabook      | S15H                        | [1a1add4428](https://linux-hardware.org/?probe=1a1add4428) | May 11, 2020 |
| Lenovo        | ThinkPad X240 20AMS72T00    | [e24475b169](https://linux-hardware.org/?probe=e24475b169) | May 11, 2020 |
| Medion        | ERAZER X7853 MD60604        | [adfafba25e](https://linux-hardware.org/?probe=adfafba25e) | May 10, 2020 |
| Lenovo        | ThinkPad E585 20KV0010US    | [43f18a12b0](https://linux-hardware.org/?probe=43f18a12b0) | May 09, 2020 |
| HP            | EliteBook Folio 9480m       | [3956d54072](https://linux-hardware.org/?probe=3956d54072) | May 09, 2020 |
| ASUSTek       | X750JA                      | [d03ab2ced2](https://linux-hardware.org/?probe=d03ab2ced2) | May 08, 2020 |
| Acer          | AOD255                      | [c9feab0ae6](https://linux-hardware.org/?probe=c9feab0ae6) | May 07, 2020 |
| Acer          | AOD255                      | [189b187df9](https://linux-hardware.org/?probe=189b187df9) | May 07, 2020 |
| Acer          | AOD255                      | [685122de57](https://linux-hardware.org/?probe=685122de57) | May 07, 2020 |
| Acer          | AOD255                      | [67a9842a83](https://linux-hardware.org/?probe=67a9842a83) | May 07, 2020 |
| Acer          | AOD255                      | [8f8f4e61eb](https://linux-hardware.org/?probe=8f8f4e61eb) | May 07, 2020 |
| HP            | Pavilion dv7                | [886f774f58](https://linux-hardware.org/?probe=886f774f58) | May 07, 2020 |
| HP            | 15                          | [e4ffb09704](https://linux-hardware.org/?probe=e4ffb09704) | May 07, 2020 |
| Dell          | Vostro 3550                 | [aeb508b54b](https://linux-hardware.org/?probe=aeb508b54b) | May 07, 2020 |
| Acer          | Aspire 5315                 | [eed274f8c5](https://linux-hardware.org/?probe=eed274f8c5) | May 07, 2020 |
| HP            | Compaq 6735s                | [d5aff5abe3](https://linux-hardware.org/?probe=d5aff5abe3) | May 07, 2020 |
| Fujitsu       | LIFEBOOK S752               | [3150f82299](https://linux-hardware.org/?probe=3150f82299) | May 06, 2020 |
| HP            | Laptop 15-rb0xx             | [0d840277dc](https://linux-hardware.org/?probe=0d840277dc) | May 06, 2020 |
| ASUSTek       | T100TA                      | [84f83e4bff](https://linux-hardware.org/?probe=84f83e4bff) | May 06, 2020 |
| ASUSTek       | X302LA                      | [a994852110](https://linux-hardware.org/?probe=a994852110) | May 06, 2020 |
| HP            | Pavilion dv6                | [f1cc639edf](https://linux-hardware.org/?probe=f1cc639edf) | May 04, 2020 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [5e583d58df](https://linux-hardware.org/?probe=5e583d58df) | May 03, 2020 |
| Positivo      | S14CT01                     | [493497d221](https://linux-hardware.org/?probe=493497d221) | May 03, 2020 |
| Positivo      | S14CT01                     | [518301afe9](https://linux-hardware.org/?probe=518301afe9) | May 03, 2020 |
| Dell          | Inspiron 7548               | [b951e05771](https://linux-hardware.org/?probe=b951e05771) | May 03, 2020 |
| Dell          | Latitude E6400              | [a50bb7e32a](https://linux-hardware.org/?probe=a50bb7e32a) | May 03, 2020 |
| Dell          | Inspiron N4050              | [e64e5a4e36](https://linux-hardware.org/?probe=e64e5a4e36) | May 02, 2020 |
| ASUSTek       | UL20A                       | [de8a903a2b](https://linux-hardware.org/?probe=de8a903a2b) | May 01, 2020 |
| HP            | ProBook 450 G2              | [887a19760b](https://linux-hardware.org/?probe=887a19760b) | May 01, 2020 |
| HP            | Pavilion x2 Detachable      | [4b6ec5f44b](https://linux-hardware.org/?probe=4b6ec5f44b) | May 01, 2020 |
| Dell          | Studio 1737                 | [50af5c4e99](https://linux-hardware.org/?probe=50af5c4e99) | May 01, 2020 |
| HP            | EliteBook Folio 9480m       | [41b9926566](https://linux-hardware.org/?probe=41b9926566) | May 01, 2020 |
| Medion        | E5217                       | [a6b33d3a94](https://linux-hardware.org/?probe=a6b33d3a94) | Apr 30, 2020 |
| Acer          | Nitro AN515-42              | [8b9ad27475](https://linux-hardware.org/?probe=8b9ad27475) | Apr 29, 2020 |
| Dixonsxp      | Unknown                     | [e9bf36b6e0](https://linux-hardware.org/?probe=e9bf36b6e0) | Apr 29, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [bf1e5c9655](https://linux-hardware.org/?probe=bf1e5c9655) | Apr 29, 2020 |
| HP            | Pavilion dv6                | [887b97f4e8](https://linux-hardware.org/?probe=887b97f4e8) | Apr 28, 2020 |
| Dell          | Inspiron 5570               | [1e1ab08268](https://linux-hardware.org/?probe=1e1ab08268) | Apr 28, 2020 |
| IBM           | ThinkPad X40 2371H4G        | [190737f754](https://linux-hardware.org/?probe=190737f754) | Apr 28, 2020 |
| HP            | Compaq Presario CQ60        | [2539260c46](https://linux-hardware.org/?probe=2539260c46) | Apr 28, 2020 |
| ASUSTek       | T100TA                      | [bebdfd359d](https://linux-hardware.org/?probe=bebdfd359d) | Apr 27, 2020 |
| HP            | Laptop 15-dw0xxx            | [47a44c4ed7](https://linux-hardware.org/?probe=47a44c4ed7) | Apr 26, 2020 |
| ASUSTek       | T100TA                      | [c1abf7906c](https://linux-hardware.org/?probe=c1abf7906c) | Apr 26, 2020 |
| Toshiba       | Satellite L550              | [73f10216d6](https://linux-hardware.org/?probe=73f10216d6) | Apr 25, 2020 |
| HP            | Laptop 15-da0xxx            | [34c85393d6](https://linux-hardware.org/?probe=34c85393d6) | Apr 24, 2020 |
| HP            | 15                          | [54d9c92866](https://linux-hardware.org/?probe=54d9c92866) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | [634f000249](https://linux-hardware.org/?probe=634f000249) | Apr 24, 2020 |
| ASUSTek       | UX331UA                     | [94be2c2ea7](https://linux-hardware.org/?probe=94be2c2ea7) | Apr 24, 2020 |
| Dell          | Inspiron 15-3567            | [0e9d3a198e](https://linux-hardware.org/?probe=0e9d3a198e) | Apr 24, 2020 |
| Sony          | VGN-AW11Z_B                 | [6a64f15800](https://linux-hardware.org/?probe=6a64f15800) | Apr 23, 2020 |
| Notebook      | N750BU                      | [e3f870729f](https://linux-hardware.org/?probe=e3f870729f) | Apr 23, 2020 |
| ASUSTek       | T100TA                      | [6cd72a2a26](https://linux-hardware.org/?probe=6cd72a2a26) | Apr 23, 2020 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [f35ddd7bef](https://linux-hardware.org/?probe=f35ddd7bef) | Apr 22, 2020 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [e6c010695a](https://linux-hardware.org/?probe=e6c010695a) | Apr 22, 2020 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [53b078eba2](https://linux-hardware.org/?probe=53b078eba2) | Apr 22, 2020 |
| ASUSTek       | X553MA                      | [dabe283d4d](https://linux-hardware.org/?probe=dabe283d4d) | Apr 21, 2020 |
| HP            | Presario V3700              | [0eac5f43d5](https://linux-hardware.org/?probe=0eac5f43d5) | Apr 21, 2020 |
| Dell          | Inspiron 1720               | [5bbab2bc27](https://linux-hardware.org/?probe=5bbab2bc27) | Apr 21, 2020 |
| ASUSTek       | TP300LA                     | [c3f624dcbd](https://linux-hardware.org/?probe=c3f624dcbd) | Apr 20, 2020 |
| HP            | 255 G2                      | [2e24d05e40](https://linux-hardware.org/?probe=2e24d05e40) | Apr 19, 2020 |
| HP            | Pavilion dv1000 (ET735UA... | [6eea6e679b](https://linux-hardware.org/?probe=6eea6e679b) | Apr 19, 2020 |
| HP            | Pavilion dv9500             | [24a912a8a2](https://linux-hardware.org/?probe=24a912a8a2) | Apr 19, 2020 |
| Sony          | VPCEB3M1E                   | [de0457eba6](https://linux-hardware.org/?probe=de0457eba6) | Apr 19, 2020 |
| Dell          | Inspiron 7537               | [58c5b959e4](https://linux-hardware.org/?probe=58c5b959e4) | Apr 19, 2020 |
| HP            | 2133 (FU338EA)              | [d9b0c55ac8](https://linux-hardware.org/?probe=d9b0c55ac8) | Apr 18, 2020 |
| Sony          | VGN-AW11Z_B                 | [c831660ca5](https://linux-hardware.org/?probe=c831660ca5) | Apr 18, 2020 |
| HP            | 2133 (FU338EA)              | [47933a37d6](https://linux-hardware.org/?probe=47933a37d6) | Apr 18, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [45f9fd21d8](https://linux-hardware.org/?probe=45f9fd21d8) | Apr 18, 2020 |
| Gateway       | MX3225                      | [2b23ba49b1](https://linux-hardware.org/?probe=2b23ba49b1) | Apr 18, 2020 |
| Gateway       | MX3225                      | [b3844e839e](https://linux-hardware.org/?probe=b3844e839e) | Apr 18, 2020 |
| Lenovo        | ThinkPad T420 42368H6       | [f65f8c3464](https://linux-hardware.org/?probe=f65f8c3464) | Apr 18, 2020 |
| HP            | 550                         | [078cde1a1b](https://linux-hardware.org/?probe=078cde1a1b) | Apr 18, 2020 |
| Lenovo        | ThinkPad T420 42368H6       | [806064d978](https://linux-hardware.org/?probe=806064d978) | Apr 18, 2020 |
| MSI           | GT72 2PC                    | [25fcea9dec](https://linux-hardware.org/?probe=25fcea9dec) | Apr 18, 2020 |
| AXIOO         | NEON CNW                    | [64edfa7923](https://linux-hardware.org/?probe=64edfa7923) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [d27bf3c005](https://linux-hardware.org/?probe=d27bf3c005) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [5d25f725c9](https://linux-hardware.org/?probe=5d25f725c9) | Apr 18, 2020 |
| Sony          | VPCYB35AL                   | [a96bfb28b5](https://linux-hardware.org/?probe=a96bfb28b5) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [eae7b8a990](https://linux-hardware.org/?probe=eae7b8a990) | Apr 17, 2020 |
| ASUSTek       | N46VB                       | [ab1938abc6](https://linux-hardware.org/?probe=ab1938abc6) | Apr 17, 2020 |
| Clevo         | M7x0S                       | [2dc8a215f6](https://linux-hardware.org/?probe=2dc8a215f6) | Apr 17, 2020 |
| Clevo         | M7x0S                       | [562739a94b](https://linux-hardware.org/?probe=562739a94b) | Apr 17, 2020 |
| Acer          | E1-510                      | [933b2f30b0](https://linux-hardware.org/?probe=933b2f30b0) | Apr 17, 2020 |
| HP            | ProBook 450 G2              | [1ef49ff7a3](https://linux-hardware.org/?probe=1ef49ff7a3) | Apr 17, 2020 |
| HP            | EliteBook 8460p             | [41c3cb6523](https://linux-hardware.org/?probe=41c3cb6523) | Apr 17, 2020 |
| HP            | EliteBook 8460p             | [e5283d7a27](https://linux-hardware.org/?probe=e5283d7a27) | Apr 17, 2020 |
| Sony          | VGN-AW11Z_B                 | [57a0d65d23](https://linux-hardware.org/?probe=57a0d65d23) | Apr 16, 2020 |
| Samsung       | RV410/RV510/S3510/E3510     | [a63c3876d5](https://linux-hardware.org/?probe=a63c3876d5) | Apr 16, 2020 |
| ASUSTek       | T100TA                      | [487d046945](https://linux-hardware.org/?probe=487d046945) | Apr 16, 2020 |
| Dell          | Latitude E6440              | [d2eaa5d809](https://linux-hardware.org/?probe=d2eaa5d809) | Apr 16, 2020 |
| ASUSTek       | S400CA                      | [ddc5a34acb](https://linux-hardware.org/?probe=ddc5a34acb) | Apr 16, 2020 |
| ASUSTek       | S400CA                      | [959d3bcbb2](https://linux-hardware.org/?probe=959d3bcbb2) | Apr 16, 2020 |
| Acer          | Aspire 5580                 | [791259386e](https://linux-hardware.org/?probe=791259386e) | Apr 16, 2020 |
| HP            | Pavilion 17                 | [d54ff69694](https://linux-hardware.org/?probe=d54ff69694) | Apr 16, 2020 |
| HP            | Gaming PC                   | [472ccadaa3](https://linux-hardware.org/?probe=472ccadaa3) | Apr 16, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [e2a5957771](https://linux-hardware.org/?probe=e2a5957771) | Apr 15, 2020 |
| Lenovo        | ThinkPad Edge E440 20C50... | [bc9d3d1f9c](https://linux-hardware.org/?probe=bc9d3d1f9c) | Apr 15, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [7c86e73d6e](https://linux-hardware.org/?probe=7c86e73d6e) | Apr 15, 2020 |
| Dell          | Latitude E5550              | [37d3c8c386](https://linux-hardware.org/?probe=37d3c8c386) | Apr 15, 2020 |
| HP            | 2133 (FU338EA)              | [029ce5169b](https://linux-hardware.org/?probe=029ce5169b) | Apr 15, 2020 |
| Acer          | Aspire 5610Z                | [65a4d9621d](https://linux-hardware.org/?probe=65a4d9621d) | Apr 14, 2020 |
| Dell          | Latitude E6510              | [ca17782e8f](https://linux-hardware.org/?probe=ca17782e8f) | Apr 14, 2020 |
| Dell          | Latitude E6510              | [a276d0e4e8](https://linux-hardware.org/?probe=a276d0e4e8) | Apr 14, 2020 |
| Apple         | MacBookPro10,1              | [37327526d9](https://linux-hardware.org/?probe=37327526d9) | Apr 13, 2020 |
| Nuvision      | L1W6_I1101_G Hampoo Rese... | [0277194797](https://linux-hardware.org/?probe=0277194797) | Apr 13, 2020 |
| Dell          | Latitude E6410              | [54dd58d213](https://linux-hardware.org/?probe=54dd58d213) | Apr 13, 2020 |
| eMachines     | G630                        | [2f15422dcd](https://linux-hardware.org/?probe=2f15422dcd) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | [4d48cc531a](https://linux-hardware.org/?probe=4d48cc531a) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | [ad2f026926](https://linux-hardware.org/?probe=ad2f026926) | Apr 13, 2020 |
| Dell          | Inspiron 3442               | [07a7a6e630](https://linux-hardware.org/?probe=07a7a6e630) | Apr 13, 2020 |
| MSI           | MS-1688                     | [e6a4077b27](https://linux-hardware.org/?probe=e6a4077b27) | Apr 13, 2020 |
| MSI           | MS-1688                     | [d0d5f98071](https://linux-hardware.org/?probe=d0d5f98071) | Apr 12, 2020 |
| Clevo         | D900C Revision D            | [1fb3feea04](https://linux-hardware.org/?probe=1fb3feea04) | Apr 12, 2020 |
| ASUSTek       | X200CA                      | [3c52d09634](https://linux-hardware.org/?probe=3c52d09634) | Apr 12, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [85350a43d3](https://linux-hardware.org/?probe=85350a43d3) | Apr 12, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [0fb509f423](https://linux-hardware.org/?probe=0fb509f423) | Apr 12, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [20eeb3f580](https://linux-hardware.org/?probe=20eeb3f580) | Apr 12, 2020 |
| Ematic        | EW147                       | [4dd070feda](https://linux-hardware.org/?probe=4dd070feda) | Apr 12, 2020 |
| Ematic        | EW147                       | [1176adc6a1](https://linux-hardware.org/?probe=1176adc6a1) | Apr 12, 2020 |
| Lenovo        | V130-15IGM 81HL             | [11251407bd](https://linux-hardware.org/?probe=11251407bd) | Apr 11, 2020 |
| Acer          | One S1002                   | [83314e9687](https://linux-hardware.org/?probe=83314e9687) | Apr 11, 2020 |
| Lenovo        | V130-15IGM 81HL             | [37f223475f](https://linux-hardware.org/?probe=37f223475f) | Apr 11, 2020 |
| HP            | Pavilion 15                 | [2f38c60e21](https://linux-hardware.org/?probe=2f38c60e21) | Apr 11, 2020 |
| HP            | Pavilion 15                 | [5b41ba3e4e](https://linux-hardware.org/?probe=5b41ba3e4e) | Apr 11, 2020 |
| Acer          | Extensa 5620                | [9501d84629](https://linux-hardware.org/?probe=9501d84629) | Apr 11, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | [15057e288d](https://linux-hardware.org/?probe=15057e288d) | Apr 11, 2020 |
| Apple         | MacBookAir4,2               | [5f84027e54](https://linux-hardware.org/?probe=5f84027e54) | Apr 11, 2020 |
| Acer          | Aspire 5741G                | [2a4c7dd1d5](https://linux-hardware.org/?probe=2a4c7dd1d5) | Apr 10, 2020 |
| Lenovo        | V130-15IGM 81HL             | [21a5c2580f](https://linux-hardware.org/?probe=21a5c2580f) | Apr 10, 2020 |
| Lenovo        | ThinkPad 11e 20DAS0YW00     | [90ca183e3d](https://linux-hardware.org/?probe=90ca183e3d) | Apr 10, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [2d92e882fd](https://linux-hardware.org/?probe=2d92e882fd) | Apr 10, 2020 |
| AXIOO         | NEON CNW                    | [b31fc0c0dd](https://linux-hardware.org/?probe=b31fc0c0dd) | Apr 10, 2020 |
| Fujitsu Si... | AMILO PRO V2030             | [67b8c113f9](https://linux-hardware.org/?probe=67b8c113f9) | Apr 10, 2020 |
| Fujitsu Si... | AMILO PRO V2030             | [fde47ff20c](https://linux-hardware.org/?probe=fde47ff20c) | Apr 10, 2020 |
| Fujitsu Si... | AMILO PRO V2030             | [432926e63e](https://linux-hardware.org/?probe=432926e63e) | Apr 10, 2020 |
| Lenovo        | G580 20157                  | [30a8d59bdc](https://linux-hardware.org/?probe=30a8d59bdc) | Apr 09, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | [ba943d4bc5](https://linux-hardware.org/?probe=ba943d4bc5) | Apr 09, 2020 |
| Lenovo        | G580 20157                  | [fc6eaad779](https://linux-hardware.org/?probe=fc6eaad779) | Apr 09, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [0248492e22](https://linux-hardware.org/?probe=0248492e22) | Apr 08, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b19f7181b4](https://linux-hardware.org/?probe=b19f7181b4) | Apr 08, 2020 |
| Gateway       | ML6228                      | [3fd17b9f82](https://linux-hardware.org/?probe=3fd17b9f82) | Apr 08, 2020 |
| Packard Be... | EasyNote TJ65               | [3008be40c7](https://linux-hardware.org/?probe=3008be40c7) | Apr 06, 2020 |
| Lenovo        | ThinkPad T440s 20AQ009HU... | [695389401a](https://linux-hardware.org/?probe=695389401a) | Apr 06, 2020 |
| Toshiba       | Satellite A200              | [b66adc41e3](https://linux-hardware.org/?probe=b66adc41e3) | Apr 05, 2020 |
| Toshiba       | Satellite A200              | [9b9a8bf80f](https://linux-hardware.org/?probe=9b9a8bf80f) | Apr 05, 2020 |
| Toshiba       | Satellite A200              | [59ab95abbb](https://linux-hardware.org/?probe=59ab95abbb) | Apr 05, 2020 |
| Acer          | Aspire 5741G                | [8ea2a664b6](https://linux-hardware.org/?probe=8ea2a664b6) | Apr 05, 2020 |
| Dell          | Latitude E6400              | [5a96047b26](https://linux-hardware.org/?probe=5a96047b26) | Apr 05, 2020 |
| Dell          | Latitude D520               | [69f550a570](https://linux-hardware.org/?probe=69f550a570) | Apr 05, 2020 |
| Toshiba       | Satellite C850D-B810        | [bfa7a5b4b3](https://linux-hardware.org/?probe=bfa7a5b4b3) | Apr 04, 2020 |
| Toshiba       | Satellite C850D-B810        | [d911f2bb34](https://linux-hardware.org/?probe=d911f2bb34) | Apr 04, 2020 |
| Toshiba       | Satellite L450              | [b18b01a081](https://linux-hardware.org/?probe=b18b01a081) | Apr 04, 2020 |
| Acer          | Aspire 5742G                | [c83a4dfe3c](https://linux-hardware.org/?probe=c83a4dfe3c) | Apr 04, 2020 |
| HP            | Mini 5103                   | [c60a2a2852](https://linux-hardware.org/?probe=c60a2a2852) | Apr 04, 2020 |
| Dell          | Inspiron 3179               | [4f8f1dd9c8](https://linux-hardware.org/?probe=4f8f1dd9c8) | Apr 04, 2020 |
| HP            | G62                         | [65f362927c](https://linux-hardware.org/?probe=65f362927c) | Apr 04, 2020 |
| HP            | G62                         | [7c0c376cdf](https://linux-hardware.org/?probe=7c0c376cdf) | Apr 04, 2020 |
| Dell          | Latitude X1                 | [47f2bd6300](https://linux-hardware.org/?probe=47f2bd6300) | Apr 03, 2020 |
| Dell          | Latitude X1                 | [d753de9b00](https://linux-hardware.org/?probe=d753de9b00) | Apr 03, 2020 |
| Acer          | Aspire A315-41              | [ec505d4ab7](https://linux-hardware.org/?probe=ec505d4ab7) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | [a602b4a98e](https://linux-hardware.org/?probe=a602b4a98e) | Apr 02, 2020 |
| NEC Comput... | PC-VY24GXZ7A                | [bc0996781f](https://linux-hardware.org/?probe=bc0996781f) | Apr 02, 2020 |
| Dell          | Latitude E6410              | [147488a290](https://linux-hardware.org/?probe=147488a290) | Apr 02, 2020 |
| Acer          | Nitro AN515-51              | [d6b01aa670](https://linux-hardware.org/?probe=d6b01aa670) | Apr 01, 2020 |
| Dell          | Latitude E6410              | [766122819f](https://linux-hardware.org/?probe=766122819f) | Apr 01, 2020 |
| Acer          | Extensa 5620                | [8926ac8c1f](https://linux-hardware.org/?probe=8926ac8c1f) | Mar 31, 2020 |
| Acer          | Extensa 5620                | [2cc79b3cc5](https://linux-hardware.org/?probe=2cc79b3cc5) | Mar 31, 2020 |
| Lenovo        | ThinkPad R400 7440WWQ       | [ac4c4ee6d7](https://linux-hardware.org/?probe=ac4c4ee6d7) | Mar 31, 2020 |
| HP            | ProBook 4525s               | [cb0a6c08db](https://linux-hardware.org/?probe=cb0a6c08db) | Mar 31, 2020 |
| Lenovo        | IdeaPad Y570 20091          | [2a38b92cb1](https://linux-hardware.org/?probe=2a38b92cb1) | Mar 31, 2020 |
| ASUSTek       | Strix 17 GL703GE            | [2a761bfaee](https://linux-hardware.org/?probe=2a761bfaee) | Mar 30, 2020 |
| Acer          | Aspire A315-41              | [59c568e03a](https://linux-hardware.org/?probe=59c568e03a) | Mar 30, 2020 |
| Sony          | VPCM13M1E                   | [eb20399d8b](https://linux-hardware.org/?probe=eb20399d8b) | Mar 30, 2020 |
| Acer          | Aspire A315-41              | [592d008d70](https://linux-hardware.org/?probe=592d008d70) | Mar 30, 2020 |
| ASUSTek       | X553MA                      | [47e6377b3b](https://linux-hardware.org/?probe=47e6377b3b) | Mar 30, 2020 |
| ASUSTek       | X553MA                      | [cadae4a0d5](https://linux-hardware.org/?probe=cadae4a0d5) | Mar 30, 2020 |
| ASUSTek       | X553MA                      | [561d99c708](https://linux-hardware.org/?probe=561d99c708) | Mar 30, 2020 |
| ASUSTek       | X553MA                      | [63e00b46e2](https://linux-hardware.org/?probe=63e00b46e2) | Mar 30, 2020 |
| ASUSTek       | 1101HAGG                    | [1ecc8fa4d3](https://linux-hardware.org/?probe=1ecc8fa4d3) | Mar 29, 2020 |
| HP            | Notebook                    | [6d16eabcdb](https://linux-hardware.org/?probe=6d16eabcdb) | Mar 29, 2020 |
| ASUSTek       | 1101HAGG                    | [8d2c258ed7](https://linux-hardware.org/?probe=8d2c258ed7) | Mar 29, 2020 |
| HP            | OMEN by HP Laptop           | [eec0858042](https://linux-hardware.org/?probe=eec0858042) | Mar 29, 2020 |
| Dell          | Inspiron 1520               | [146388e7f0](https://linux-hardware.org/?probe=146388e7f0) | Mar 29, 2020 |
| HP            | ProBook 4525s               | [dc9164d939](https://linux-hardware.org/?probe=dc9164d939) | Mar 28, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcbfe2da9a](https://linux-hardware.org/?probe=bcbfe2da9a) | Mar 28, 2020 |
| Samsung       | 305V4A/305V5A/3415VA        | [118b531086](https://linux-hardware.org/?probe=118b531086) | Mar 28, 2020 |
| Samsung       | 305V4A/305V5A/3415VA        | [4d70e47759](https://linux-hardware.org/?probe=4d70e47759) | Mar 28, 2020 |
| Samsung       | 800G5M/800G5W               | [f8a5c21d24](https://linux-hardware.org/?probe=f8a5c21d24) | Mar 28, 2020 |
| HP            | Pavilion g6                 | [cfe67dc8eb](https://linux-hardware.org/?probe=cfe67dc8eb) | Mar 27, 2020 |
| HP            | Pavilion g6                 | [502b653111](https://linux-hardware.org/?probe=502b653111) | Mar 27, 2020 |
| HP            | Pavilion g6                 | [058cce86bb](https://linux-hardware.org/?probe=058cce86bb) | Mar 27, 2020 |
| ASUSTek       | N750JK                      | [172ea4a7d1](https://linux-hardware.org/?probe=172ea4a7d1) | Mar 27, 2020 |
| Dell          | Inspiron 1520               | [0bd42bbb3a](https://linux-hardware.org/?probe=0bd42bbb3a) | Mar 27, 2020 |
| Dell          | Inspiron 5570               | [922814f637](https://linux-hardware.org/?probe=922814f637) | Mar 27, 2020 |
| Dell          | Inspiron 5570               | [b8ac8ae9e4](https://linux-hardware.org/?probe=b8ac8ae9e4) | Mar 27, 2020 |
| HP            | Pavilion 10 TS              | [87484a7033](https://linux-hardware.org/?probe=87484a7033) | Mar 27, 2020 |
| Panasonic     | CF-31ACJAXPM                | [44a7635515](https://linux-hardware.org/?probe=44a7635515) | Mar 27, 2020 |
| eMachines     | eME728                      | [26425bd7a4](https://linux-hardware.org/?probe=26425bd7a4) | Mar 26, 2020 |
| Acer          | Aspire A315-31              | [1755330821](https://linux-hardware.org/?probe=1755330821) | Mar 26, 2020 |
| HP            | Pavilion dv9700             | [7567e3c677](https://linux-hardware.org/?probe=7567e3c677) | Mar 26, 2020 |
| Dell          | Latitude E5440              | [d5e19d53dc](https://linux-hardware.org/?probe=d5e19d53dc) | Mar 25, 2020 |
| MSI           | GE62 6QF                    | [f951247a44](https://linux-hardware.org/?probe=f951247a44) | Mar 25, 2020 |
| HP            | ProBook 6550b               | [9cd41d9853](https://linux-hardware.org/?probe=9cd41d9853) | Mar 25, 2020 |
| Dell          | XPS 15 9560                 | [0f39d105a8](https://linux-hardware.org/?probe=0f39d105a8) | Mar 25, 2020 |
| Dell          | XPS 15 9560                 | [9453dadbd6](https://linux-hardware.org/?probe=9453dadbd6) | Mar 25, 2020 |
| HP            | Pavilion dv5                | [009a4aed18](https://linux-hardware.org/?probe=009a4aed18) | Mar 25, 2020 |
| HP            | Presario C500 (RY510EA#A... | [e69a3bef68](https://linux-hardware.org/?probe=e69a3bef68) | Mar 24, 2020 |
| Toshiba       | Satellite C660              | [38c32074a0](https://linux-hardware.org/?probe=38c32074a0) | Mar 24, 2020 |
| HP            | ZBook 14u G4                | [2843fde2a7](https://linux-hardware.org/?probe=2843fde2a7) | Mar 23, 2020 |
| Dell          | Inspiron 1520               | [5ccfcc44f0](https://linux-hardware.org/?probe=5ccfcc44f0) | Mar 23, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [e274c73209](https://linux-hardware.org/?probe=e274c73209) | Mar 23, 2020 |
| Toshiba       | Satellite L455D             | [1d8583d691](https://linux-hardware.org/?probe=1d8583d691) | Mar 23, 2020 |
| HP            | Pavilion 15                 | [b37a8bd4ff](https://linux-hardware.org/?probe=b37a8bd4ff) | Mar 22, 2020 |
| HP            | Pavilion x2 Detachable      | [27c5f0f340](https://linux-hardware.org/?probe=27c5f0f340) | Mar 22, 2020 |
| Lenovo        | ThinkPad T510 4349AW2       | [e8351b04a1](https://linux-hardware.org/?probe=e8351b04a1) | Mar 22, 2020 |
| HP            | ProBook 6550b               | [08a8d59e31](https://linux-hardware.org/?probe=08a8d59e31) | Mar 22, 2020 |
| Lenovo        | G510 20238                  | [9130b68bf4](https://linux-hardware.org/?probe=9130b68bf4) | Mar 22, 2020 |
| Sony          | SVF15A17CLB                 | [6f9e42f276](https://linux-hardware.org/?probe=6f9e42f276) | Mar 22, 2020 |
| Lenovo        | ThinkPad T510 4349AW2       | [428a0150aa](https://linux-hardware.org/?probe=428a0150aa) | Mar 21, 2020 |
| Samsung       | R519/R719                   | [df651d6929](https://linux-hardware.org/?probe=df651d6929) | Mar 21, 2020 |
| HP            | Pavilion Notebook 15-bc5... | [712dd83a31](https://linux-hardware.org/?probe=712dd83a31) | Mar 21, 2020 |
| HP            | G62                         | [10f3f45b4c](https://linux-hardware.org/?probe=10f3f45b4c) | Mar 21, 2020 |
| HP            | G62                         | [6f4776017d](https://linux-hardware.org/?probe=6f4776017d) | Mar 21, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [a2d8924557](https://linux-hardware.org/?probe=a2d8924557) | Mar 21, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [35a6f133b6](https://linux-hardware.org/?probe=35a6f133b6) | Mar 21, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [4511e5932e](https://linux-hardware.org/?probe=4511e5932e) | Mar 21, 2020 |
| ASUSTek       | F3Sg                        | [149527329c](https://linux-hardware.org/?probe=149527329c) | Mar 20, 2020 |
| Unknown       | Unknown                     | [268c0d4b3e](https://linux-hardware.org/?probe=268c0d4b3e) | Mar 20, 2020 |
| HP            | Pavilion 11 x360 PC         | [fd49842929](https://linux-hardware.org/?probe=fd49842929) | Mar 20, 2020 |
| HP            | Pavilion 11 x360 PC         | [079561668f](https://linux-hardware.org/?probe=079561668f) | Mar 20, 2020 |
| HP            | Pavilion Notebook 15-bc5... | [b67aef950d](https://linux-hardware.org/?probe=b67aef950d) | Mar 19, 2020 |
| HP            | Pavilion Notebook 15-bc5... | [c2b75c6e1a](https://linux-hardware.org/?probe=c2b75c6e1a) | Mar 19, 2020 |
| HP            | Compaq 8510p                | [df003f9b94](https://linux-hardware.org/?probe=df003f9b94) | Mar 19, 2020 |
| HP            | Compaq 8510p                | [6a272fe91c](https://linux-hardware.org/?probe=6a272fe91c) | Mar 19, 2020 |
| HP            | Unknown                     | [0720ac35fc](https://linux-hardware.org/?probe=0720ac35fc) | Mar 19, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | [a351ec49d6](https://linux-hardware.org/?probe=a351ec49d6) | Mar 19, 2020 |
| HP            | Pavilion Laptop 14-ce0xx... | [824e8de596](https://linux-hardware.org/?probe=824e8de596) | Mar 19, 2020 |
| Dell          | Inspiron 1520               | [e603a6de90](https://linux-hardware.org/?probe=e603a6de90) | Mar 19, 2020 |
| HP            | G42                         | [81475e20fc](https://linux-hardware.org/?probe=81475e20fc) | Mar 19, 2020 |
| Lenovo        | ThinkPad L412 058542G       | [1bc705430b](https://linux-hardware.org/?probe=1bc705430b) | Mar 18, 2020 |
| HP            | Unknown                     | [7ebfd4d205](https://linux-hardware.org/?probe=7ebfd4d205) | Mar 18, 2020 |
| HP            | Pavilion tx1000             | [5f8a15817c](https://linux-hardware.org/?probe=5f8a15817c) | Mar 18, 2020 |
| HP            | Pavilion tx1000             | [76f5c62167](https://linux-hardware.org/?probe=76f5c62167) | Mar 18, 2020 |
| Toshiba       | Satellite L305              | [e3b6115f5e](https://linux-hardware.org/?probe=e3b6115f5e) | Mar 17, 2020 |
| Toshiba       | Satellite L305              | [7d2f3a78fe](https://linux-hardware.org/?probe=7d2f3a78fe) | Mar 17, 2020 |
| Lenovo        | Yoga 300-11IBR 80M1         | [b19ba42878](https://linux-hardware.org/?probe=b19ba42878) | Mar 17, 2020 |
| HP            | ProBook 640 G4              | [9240c255ae](https://linux-hardware.org/?probe=9240c255ae) | Mar 16, 2020 |
| Lenovo        | ThinkPad S3-S440 20AY00B... | [86e1d115b9](https://linux-hardware.org/?probe=86e1d115b9) | Mar 15, 2020 |
| HP            | Pavilion dv9700             | [98979886b3](https://linux-hardware.org/?probe=98979886b3) | Mar 15, 2020 |
| Dell          | Inspiron 6000               | [e81704d568](https://linux-hardware.org/?probe=e81704d568) | Mar 15, 2020 |
| HP            | Pavilion dv9700             | [60bcd3ac92](https://linux-hardware.org/?probe=60bcd3ac92) | Mar 15, 2020 |
| Lenovo        | Y70-70 Touch 80DU           | [6ab7a0c0f5](https://linux-hardware.org/?probe=6ab7a0c0f5) | Mar 15, 2020 |
| ASUSTek       | N750JK                      | [7b51fed304](https://linux-hardware.org/?probe=7b51fed304) | Mar 13, 2020 |
| Dell          | Inspiron 7560               | [bdfbbe481f](https://linux-hardware.org/?probe=bdfbbe481f) | Mar 13, 2020 |
| Acer          | Aspire E1-572G              | [cc8b5532c5](https://linux-hardware.org/?probe=cc8b5532c5) | Mar 12, 2020 |
| HP            | Pavilion dv7                | [61bbb3da8a](https://linux-hardware.org/?probe=61bbb3da8a) | Mar 12, 2020 |
| Acer          | Ferrari 4000                | [a1626355ea](https://linux-hardware.org/?probe=a1626355ea) | Mar 11, 2020 |
| Acer          | Ferrari 4000                | [b894026368](https://linux-hardware.org/?probe=b894026368) | Mar 11, 2020 |
| Acer          | Ferrari 4000                | [fa404be8fd](https://linux-hardware.org/?probe=fa404be8fd) | Mar 11, 2020 |
| Dell          | Latitude E5440              | [7582be2134](https://linux-hardware.org/?probe=7582be2134) | Mar 11, 2020 |
| HP            | ProBook 4320s               | [92478c20d5](https://linux-hardware.org/?probe=92478c20d5) | Mar 11, 2020 |
| ASUSTek       | TAICHI21                    | [608a903011](https://linux-hardware.org/?probe=608a903011) | Mar 11, 2020 |
| Apple         | MacBookPro9,2               | [81823b3c54](https://linux-hardware.org/?probe=81823b3c54) | Mar 11, 2020 |
| Dell          | Latitude XT2                | [bf5cd05553](https://linux-hardware.org/?probe=bf5cd05553) | Mar 10, 2020 |
| Samsung       | N102                        | [40dba99330](https://linux-hardware.org/?probe=40dba99330) | Mar 10, 2020 |
| Apple         | MacBookPro9,2               | [ccde97eb8a](https://linux-hardware.org/?probe=ccde97eb8a) | Mar 10, 2020 |
| Apple         | MacBookPro9,2               | [289d3eb3d3](https://linux-hardware.org/?probe=289d3eb3d3) | Mar 10, 2020 |
| HP            | Compaq 615                  | [20f4720634](https://linux-hardware.org/?probe=20f4720634) | Mar 08, 2020 |
| Dell          | Latitude E5440              | [a03a2405a2](https://linux-hardware.org/?probe=a03a2405a2) | Mar 08, 2020 |
| Lenovo        | ThinkPad T430s 23563RB      | [a011b81975](https://linux-hardware.org/?probe=a011b81975) | Mar 07, 2020 |
| Lenovo        | ThinkPad T430s 23563RB      | [8ce2fe5d52](https://linux-hardware.org/?probe=8ce2fe5d52) | Mar 07, 2020 |
| HP            | EliteBook 840 G2            | [b23a6cc526](https://linux-hardware.org/?probe=b23a6cc526) | Mar 06, 2020 |
| Dixonsxp      | Unknown                     | [d51d943904](https://linux-hardware.org/?probe=d51d943904) | Mar 06, 2020 |
| HP            | Pavilion 11 x360 PC         | [27c2ab2a74](https://linux-hardware.org/?probe=27c2ab2a74) | Mar 05, 2020 |
| HP            | Pavilion 11 x360 PC         | [330524da7c](https://linux-hardware.org/?probe=330524da7c) | Mar 05, 2020 |
| HP            | Pavilion 11 x360 PC         | [e5d46d214b](https://linux-hardware.org/?probe=e5d46d214b) | Mar 05, 2020 |
| HP            | ProBook 4320s               | [96b40c5d0e](https://linux-hardware.org/?probe=96b40c5d0e) | Mar 05, 2020 |
| Lenovo        | Flex 2-15 20405             | [b673427507](https://linux-hardware.org/?probe=b673427507) | Mar 03, 2020 |
| Google        | Gnawty                      | [6f3ac8ce74](https://linux-hardware.org/?probe=6f3ac8ce74) | Mar 01, 2020 |
| Samsung       | 340XAA/350XAA/550XAA        | [5b1e502fce](https://linux-hardware.org/?probe=5b1e502fce) | Mar 01, 2020 |
| Fujitsu Si... | AMILO M1451G Series         | [ae442cc174](https://linux-hardware.org/?probe=ae442cc174) | Feb 26, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [9344a74aa9](https://linux-hardware.org/?probe=9344a74aa9) | Feb 26, 2020 |
| ASUSTek       | X555LD                      | [c3ba184dbb](https://linux-hardware.org/?probe=c3ba184dbb) | Feb 25, 2020 |
| HP            | EliteBook 840 G1            | [cd0a628cc6](https://linux-hardware.org/?probe=cd0a628cc6) | Feb 23, 2020 |
| HP            | Pavilion dm1                | [e4a08b8741](https://linux-hardware.org/?probe=e4a08b8741) | Feb 23, 2020 |
| MSI           | GT72 2PC                    | [2314176c88](https://linux-hardware.org/?probe=2314176c88) | Feb 22, 2020 |
| Google        | Enguarde                    | [1b6835ab9d](https://linux-hardware.org/?probe=1b6835ab9d) | Feb 21, 2020 |
| ASUSTek       | GX501VIK                    | [717e762d70](https://linux-hardware.org/?probe=717e762d70) | Feb 20, 2020 |
| Apple         | MacBook4,1                  | [4eb748a8df](https://linux-hardware.org/?probe=4eb748a8df) | Feb 20, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b253180703](https://linux-hardware.org/?probe=b253180703) | Feb 20, 2020 |
| ASUSTek       | GX501VIK                    | [a8d5bc13f9](https://linux-hardware.org/?probe=a8d5bc13f9) | Feb 19, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [ad43873fae](https://linux-hardware.org/?probe=ad43873fae) | Feb 19, 2020 |
| HP            | ProBook 4530s               | [639dbf3714](https://linux-hardware.org/?probe=639dbf3714) | Feb 16, 2020 |
| Bak USA Te... | Atlas                       | [faa71e71eb](https://linux-hardware.org/?probe=faa71e71eb) | Feb 16, 2020 |
| ASUSTek       | A6Km                        | [674156522d](https://linux-hardware.org/?probe=674156522d) | Feb 16, 2020 |
| Bak USA Te... | Atlas                       | [0c83137c86](https://linux-hardware.org/?probe=0c83137c86) | Feb 16, 2020 |
| Bak USA Te... | Atlas                       | [15c4b4ee0d](https://linux-hardware.org/?probe=15c4b4ee0d) | Feb 16, 2020 |
| Bak USA Te... | Atlas                       | [d67327054b](https://linux-hardware.org/?probe=d67327054b) | Feb 15, 2020 |
| Bak USA Te... | Atlas                       | [c1049c49c9](https://linux-hardware.org/?probe=c1049c49c9) | Feb 15, 2020 |
| Bak USA Te... | Atlas                       | [f82c7a7577](https://linux-hardware.org/?probe=f82c7a7577) | Feb 14, 2020 |
| Bak USA Te... | Atlas                       | [4e1dd1b730](https://linux-hardware.org/?probe=4e1dd1b730) | Feb 14, 2020 |
| NEC Comput... | PC-VY25AACZ9                | [87e4d3dd9a](https://linux-hardware.org/?probe=87e4d3dd9a) | Feb 14, 2020 |
| Toshiba       | PORTEGE Z30-A               | [897030a5ea](https://linux-hardware.org/?probe=897030a5ea) | Feb 13, 2020 |
| Dell          | Vostro 3550                 | [edfe8875af](https://linux-hardware.org/?probe=edfe8875af) | Feb 12, 2020 |
| IBM           | ThinkPad T43 26688AG        | [ce6973ce12](https://linux-hardware.org/?probe=ce6973ce12) | Feb 12, 2020 |
| Toshiba       | Satellite L55-C             | [acebd8101e](https://linux-hardware.org/?probe=acebd8101e) | Feb 11, 2020 |
| Dell          | Vostro 3750                 | [73e23c8357](https://linux-hardware.org/?probe=73e23c8357) | Feb 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [91ba437052](https://linux-hardware.org/?probe=91ba437052) | Feb 11, 2020 |
| Toshiba       | PORTEGE Z30-A               | [8b26c24d93](https://linux-hardware.org/?probe=8b26c24d93) | Feb 11, 2020 |
| ASUSTek       | E203NA                      | [09dbcdcddc](https://linux-hardware.org/?probe=09dbcdcddc) | Feb 10, 2020 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [d9fdcbf4d8](https://linux-hardware.org/?probe=d9fdcbf4d8) | Feb 10, 2020 |
| HUAWEI        | BOHK-WAX9X                  | [10d5285055](https://linux-hardware.org/?probe=10d5285055) | Feb 07, 2020 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | [d80811a73d](https://linux-hardware.org/?probe=d80811a73d) | Feb 05, 2020 |
| Lenovo        | G505 20240                  | [3208a023bf](https://linux-hardware.org/?probe=3208a023bf) | Feb 04, 2020 |
| Lenovo        | ThinkPad E550 20DF0040US    | [ce3ebef6dc](https://linux-hardware.org/?probe=ce3ebef6dc) | Feb 04, 2020 |
| Samsung       | 305E4A/305E5A/305E7A        | [e9238fd8ed](https://linux-hardware.org/?probe=e9238fd8ed) | Feb 03, 2020 |
| TrekStor      | Notebook Slim S130          | [e0e1b59385](https://linux-hardware.org/?probe=e0e1b59385) | Feb 01, 2020 |
| Acer          | Nitro AN515-42              | [1811818f9f](https://linux-hardware.org/?probe=1811818f9f) | Feb 01, 2020 |
| Acer          | Nitro AN515-42              | [2a79ec1346](https://linux-hardware.org/?probe=2a79ec1346) | Feb 01, 2020 |
| Acer          | Nitro AN515-42              | [a1d38e2afe](https://linux-hardware.org/?probe=a1d38e2afe) | Feb 01, 2020 |
| Acer          | Aspire 5735                 | [e517ff7dc7](https://linux-hardware.org/?probe=e517ff7dc7) | Jan 31, 2020 |
| HP            | Pavilion dv7                | [1359dd6ebc](https://linux-hardware.org/?probe=1359dd6ebc) | Jan 31, 2020 |
| Acer          | Aspire 5336                 | [7827c16291](https://linux-hardware.org/?probe=7827c16291) | Jan 30, 2020 |
| HP            | Pavilion dv6700             | [11b6b91acc](https://linux-hardware.org/?probe=11b6b91acc) | Jan 29, 2020 |
| HP            | Compaq Presario CQ50        | [1e88106854](https://linux-hardware.org/?probe=1e88106854) | Jan 28, 2020 |
| HP            | ProBook 450 G1              | [7393534af1](https://linux-hardware.org/?probe=7393534af1) | Jan 26, 2020 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [7282fec433](https://linux-hardware.org/?probe=7282fec433) | Jan 26, 2020 |
| Toshiba       | Satellite L55-B             | [cbf62518f7](https://linux-hardware.org/?probe=cbf62518f7) | Jan 25, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [d84c64a7b4](https://linux-hardware.org/?probe=d84c64a7b4) | Jan 23, 2020 |
| Acer          | AOA150                      | [0b619b41c1](https://linux-hardware.org/?probe=0b619b41c1) | Jan 23, 2020 |
| Lenovo        | IdeaPad N581 7505           | [2d053580c5](https://linux-hardware.org/?probe=2d053580c5) | Jan 22, 2020 |
| Acer          | AOA150                      | [2bba1020f4](https://linux-hardware.org/?probe=2bba1020f4) | Jan 18, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c20e4254c8](https://linux-hardware.org/?probe=c20e4254c8) | Jan 18, 2020 |
| HP            | Split 13 x2 Detachable P... | [508422072e](https://linux-hardware.org/?probe=508422072e) | Jan 17, 2020 |
| HP            | Split 13 x2 Detachable P... | [8ef1114860](https://linux-hardware.org/?probe=8ef1114860) | Jan 17, 2020 |
| Acer          | AOA150                      | [286aa36d50](https://linux-hardware.org/?probe=286aa36d50) | Jan 16, 2020 |
| Acer          | AOA150                      | [041850cdfc](https://linux-hardware.org/?probe=041850cdfc) | Jan 16, 2020 |
| Acer          | AOA150                      | [9b7a0e62bc](https://linux-hardware.org/?probe=9b7a0e62bc) | Jan 16, 2020 |
| Acer          | AOA150                      | [479c699e7d](https://linux-hardware.org/?probe=479c699e7d) | Jan 16, 2020 |
| Lenovo        | V155-15API 81V5             | [62d9f6fd7f](https://linux-hardware.org/?probe=62d9f6fd7f) | Jan 16, 2020 |
| Acer          | AOA150                      | [570e78181f](https://linux-hardware.org/?probe=570e78181f) | Jan 16, 2020 |
| Acer          | AOA150                      | [fe78dbe525](https://linux-hardware.org/?probe=fe78dbe525) | Jan 16, 2020 |
| AMI           | Board                       | [4d89af9f9b](https://linux-hardware.org/?probe=4d89af9f9b) | Jan 16, 2020 |
| Acer          | AOA150                      | [822393626a](https://linux-hardware.org/?probe=822393626a) | Jan 16, 2020 |
| Acer          | AOA150                      | [94fa7756d5](https://linux-hardware.org/?probe=94fa7756d5) | Jan 15, 2020 |
| Toshiba       | Satellite L55-B             | [67b00cee9e](https://linux-hardware.org/?probe=67b00cee9e) | Jan 15, 2020 |
| Acer          | Aspire 5750                 | [b4b48d57a5](https://linux-hardware.org/?probe=b4b48d57a5) | Jan 15, 2020 |
| Lenovo        | V155-15API 81V5             | [7b0192d941](https://linux-hardware.org/?probe=7b0192d941) | Jan 12, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [db6935033e](https://linux-hardware.org/?probe=db6935033e) | Jan 11, 2020 |
| Lenovo        | IdeaPad 100-14IBY 80MH      | [c0265e0fd2](https://linux-hardware.org/?probe=c0265e0fd2) | Jan 11, 2020 |
| Samsung       | R710                        | [f9cd84fa75](https://linux-hardware.org/?probe=f9cd84fa75) | Jan 10, 2020 |
| Packard Be... | EasyNote MH36               | [ce56ea59c0](https://linux-hardware.org/?probe=ce56ea59c0) | Jan 06, 2020 |
| Packard Be... | EasyNote MH35               | [219fd394d3](https://linux-hardware.org/?probe=219fd394d3) | Jan 06, 2020 |
| Packard Be... | EasyNote MH35               | [c686755748](https://linux-hardware.org/?probe=c686755748) | Jan 06, 2020 |
| Packard Be... | EasyNote MH36               | [e3390abf19](https://linux-hardware.org/?probe=e3390abf19) | Jan 06, 2020 |
| Packard Be... | EasyNote MH36               | [35d768055a](https://linux-hardware.org/?probe=35d768055a) | Jan 06, 2020 |
| Packard Be... | EasyNote MH36               | [2d39a2c052](https://linux-hardware.org/?probe=2d39a2c052) | Jan 05, 2020 |
| Acer          | Aspire 4752                 | [4e0f6ed499](https://linux-hardware.org/?probe=4e0f6ed499) | Jan 05, 2020 |
| Acer          | Aspire 4752                 | [ef80f122b5](https://linux-hardware.org/?probe=ef80f122b5) | Jan 05, 2020 |
| Toshiba       | Satellite A215              | [47dcd6e7bf](https://linux-hardware.org/?probe=47dcd6e7bf) | Jan 02, 2020 |
| Toshiba       | Satellite A215              | [d631681834](https://linux-hardware.org/?probe=d631681834) | Jan 02, 2020 |
| Toshiba       | Satellite A215              | [746c66b8c6](https://linux-hardware.org/?probe=746c66b8c6) | Jan 02, 2020 |
| Packard Be... | EasyNote MH36               | [f967b7877c](https://linux-hardware.org/?probe=f967b7877c) | Jan 02, 2020 |
| Packard Be... | EasyNote MH36               | [d68bbadfa1](https://linux-hardware.org/?probe=d68bbadfa1) | Jan 01, 2020 |
| HP            | Laptop 15-bw0xx             | [defb99f1cc](https://linux-hardware.org/?probe=defb99f1cc) | Jan 01, 2020 |
| Packard Be... | EasyNote TJ65               | [11c8b385a6](https://linux-hardware.org/?probe=11c8b385a6) | Jan 01, 2020 |
| Dell          | Latitude E6420              | [22ac950018](https://linux-hardware.org/?probe=22ac950018) | Dec 31, 2019 |
| Dell          | Latitude E6420              | [c0dcaf12d6](https://linux-hardware.org/?probe=c0dcaf12d6) | Dec 31, 2019 |
| Packard Be... | EasyNote MH36               | [2e94c86fec](https://linux-hardware.org/?probe=2e94c86fec) | Dec 31, 2019 |
| Lenovo        | V155-15API 81V5             | [72487c3d1b](https://linux-hardware.org/?probe=72487c3d1b) | Dec 31, 2019 |
| Lenovo        | V155-15API 81V5             | [c379f2d81b](https://linux-hardware.org/?probe=c379f2d81b) | Dec 31, 2019 |
| Dell          | Latitude E6420              | [57a24730d1](https://linux-hardware.org/?probe=57a24730d1) | Dec 31, 2019 |
| Samsung       | 340XAA/350XAA/550XAA        | [561a2b1118](https://linux-hardware.org/?probe=561a2b1118) | Dec 31, 2019 |
| Packard Be... | EasyNote MH36               | [ac81f5e5b3](https://linux-hardware.org/?probe=ac81f5e5b3) | Dec 31, 2019 |
| Packard Be... | EasyNote MH36               | [6aa9449017](https://linux-hardware.org/?probe=6aa9449017) | Dec 31, 2019 |
| Packard Be... | EasyNote MH36               | [2acbacb783](https://linux-hardware.org/?probe=2acbacb783) | Dec 30, 2019 |
| Dell          | Latitude D630               | [aa6eee7a18](https://linux-hardware.org/?probe=aa6eee7a18) | Dec 30, 2019 |
| MSI           | GT70                        | [c86693c4ea](https://linux-hardware.org/?probe=c86693c4ea) | Dec 29, 2019 |
| NEC Comput... | PC-LC900HJ                  | [76bec35362](https://linux-hardware.org/?probe=76bec35362) | Dec 29, 2019 |
| HP            | Presario F500 (GL935UA#A... | [974afae9cf](https://linux-hardware.org/?probe=974afae9cf) | Dec 27, 2019 |
| Toshiba       | Satellite L775D             | [936a9682fa](https://linux-hardware.org/?probe=936a9682fa) | Dec 27, 2019 |
| Dell          | Inspiron 5566               | [f0139b5341](https://linux-hardware.org/?probe=f0139b5341) | Dec 26, 2019 |
| Dell          | Latitude E6530              | [813731ab25](https://linux-hardware.org/?probe=813731ab25) | Dec 26, 2019 |
| Lenovo        | V155-15API 81V5             | [c65abd0640](https://linux-hardware.org/?probe=c65abd0640) | Dec 26, 2019 |
| Lenovo        | V155-15API 81V5             | [2c4c5c9c36](https://linux-hardware.org/?probe=2c4c5c9c36) | Dec 26, 2019 |
| Lenovo        | V155-15API 81V5             | [0d5995a5ff](https://linux-hardware.org/?probe=0d5995a5ff) | Dec 26, 2019 |
| Lenovo        | V155-15API 81V5             | [8a74f889ca](https://linux-hardware.org/?probe=8a74f889ca) | Dec 26, 2019 |
| Dell          | Latitude E6530              | [e27a23f80b](https://linux-hardware.org/?probe=e27a23f80b) | Dec 24, 2019 |
| HP            | EliteBook 2540p             | [4663deb0dd](https://linux-hardware.org/?probe=4663deb0dd) | Dec 23, 2019 |
| Unknown       | Unknown                     | [ebb7e1b084](https://linux-hardware.org/?probe=ebb7e1b084) | Dec 22, 2019 |
| AMI           | Cherry Trail FFD            | [c62d47b2a1](https://linux-hardware.org/?probe=c62d47b2a1) | Dec 22, 2019 |
| Unknown       | Unknown                     | [a0cdc78762](https://linux-hardware.org/?probe=a0cdc78762) | Dec 22, 2019 |
| HP            | Laptop 15-db0xxx            | [3b491b92b3](https://linux-hardware.org/?probe=3b491b92b3) | Dec 21, 2019 |
| HP            | EliteBook 2760p             | [6d298da4a5](https://linux-hardware.org/?probe=6d298da4a5) | Dec 20, 2019 |
| Dell          | Latitude E5420              | [4673399116](https://linux-hardware.org/?probe=4673399116) | Dec 19, 2019 |
| Dell          | Inspiron 7520               | [e5cda35a9a](https://linux-hardware.org/?probe=e5cda35a9a) | Dec 16, 2019 |
| Dell          | Latitude E6430              | [39d47c0f09](https://linux-hardware.org/?probe=39d47c0f09) | Dec 16, 2019 |
| Minix         | NEO Z83-4 V1.1              | [c298c38fa6](https://linux-hardware.org/?probe=c298c38fa6) | Dec 16, 2019 |
| HP            | EliteBook 2760p             | [6ca3976164](https://linux-hardware.org/?probe=6ca3976164) | Dec 16, 2019 |
| Minix         | NEO Z83-4 V1.1              | [8de9a4ef47](https://linux-hardware.org/?probe=8de9a4ef47) | Dec 15, 2019 |
| HP            | Compaq nc6220 (PL814AV)     | [a770cf025e](https://linux-hardware.org/?probe=a770cf025e) | Dec 15, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [f4689330d7](https://linux-hardware.org/?probe=f4689330d7) | Dec 14, 2019 |
| Acer          | Aspire ES1-531              | [0949108352](https://linux-hardware.org/?probe=0949108352) | Dec 14, 2019 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [d651477524](https://linux-hardware.org/?probe=d651477524) | Dec 14, 2019 |
| Dell          | Latitude E6430              | [65ccc430a7](https://linux-hardware.org/?probe=65ccc430a7) | Dec 14, 2019 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [7c53a00cb0](https://linux-hardware.org/?probe=7c53a00cb0) | Dec 12, 2019 |
| Lenovo        | IdeaPad Z400 Touch VIWZ1    | [4b9dba4d4a](https://linux-hardware.org/?probe=4b9dba4d4a) | Dec 12, 2019 |
| NEC Comput... | PC-VY25AACZ9                | [67db0cd3e1](https://linux-hardware.org/?probe=67db0cd3e1) | Dec 12, 2019 |
| MSI           | GT72 2PC                    | [dbe1269ea7](https://linux-hardware.org/?probe=dbe1269ea7) | Dec 11, 2019 |
| MSI           | GL62M 7RDX                  | [b8aa5ef26c](https://linux-hardware.org/?probe=b8aa5ef26c) | Dec 09, 2019 |
| MSI           | GL62M 7RDX                  | [9c863ea710](https://linux-hardware.org/?probe=9c863ea710) | Dec 09, 2019 |
| ASUSTek       | W2P                         | [bae8402d0d](https://linux-hardware.org/?probe=bae8402d0d) | Dec 08, 2019 |
| ASUSTek       | 1001PX                      | [e368a28816](https://linux-hardware.org/?probe=e368a28816) | Dec 04, 2019 |
| Dell          | Studio 1735                 | [586b67318a](https://linux-hardware.org/?probe=586b67318a) | Dec 03, 2019 |
| Dell          | Studio 1735                 | [b90b1732fc](https://linux-hardware.org/?probe=b90b1732fc) | Dec 03, 2019 |
| bq            | Tesla2 W10                  | [d404a738dc](https://linux-hardware.org/?probe=d404a738dc) | Dec 03, 2019 |
| ASUSTek       | X550CC                      | [b2fb796fab](https://linux-hardware.org/?probe=b2fb796fab) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [5b4aff6fe8](https://linux-hardware.org/?probe=5b4aff6fe8) | Dec 03, 2019 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [abeaa01348](https://linux-hardware.org/?probe=abeaa01348) | Dec 03, 2019 |
| HP            | EliteBook 6930p             | [94af8c86b1](https://linux-hardware.org/?probe=94af8c86b1) | Dec 03, 2019 |
| Dell          | Inspiron 15-3567            | [f952dc6f5d](https://linux-hardware.org/?probe=f952dc6f5d) | Dec 03, 2019 |
| Unknown       | Unknown                     | [8b11eb98d3](https://linux-hardware.org/?probe=8b11eb98d3) | Dec 02, 2019 |
| Unknown       | Unknown                     | [cd4af41624](https://linux-hardware.org/?probe=cd4af41624) | Nov 30, 2019 |
| ASUSTek       | 1000H                       | [22b31ccf0f](https://linux-hardware.org/?probe=22b31ccf0f) | Nov 29, 2019 |
| HP            | Pavilion dv6                | [fdc46ce1cd](https://linux-hardware.org/?probe=fdc46ce1cd) | Nov 26, 2019 |
| Dell          | Latitude E6540              | [25a99fe356](https://linux-hardware.org/?probe=25a99fe356) | Nov 25, 2019 |
| Dell          | Latitude E6540              | [fab2125ce9](https://linux-hardware.org/?probe=fab2125ce9) | Nov 25, 2019 |
| Apple         | MacBookPro11,1              | [25987883b0](https://linux-hardware.org/?probe=25987883b0) | Nov 24, 2019 |
| Dell          | Latitude E6520              | [4384225066](https://linux-hardware.org/?probe=4384225066) | Nov 21, 2019 |
| Compal        | Unknown                     | [718c425aa1](https://linux-hardware.org/?probe=718c425aa1) | Nov 19, 2019 |
| Medion        | S6421 MD60702               | [b2abbfcf51](https://linux-hardware.org/?probe=b2abbfcf51) | Nov 16, 2019 |
| Dell          | Latitude E6520              | [5f41cfdbb1](https://linux-hardware.org/?probe=5f41cfdbb1) | Nov 16, 2019 |
| Lenovo        | G710 20252                  | [d11fbec88a](https://linux-hardware.org/?probe=d11fbec88a) | Nov 14, 2019 |
| ASUSTek       | B9440UA                     | [7f6afd4c6b](https://linux-hardware.org/?probe=7f6afd4c6b) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | [370c185f25](https://linux-hardware.org/?probe=370c185f25) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | [b6aec97c45](https://linux-hardware.org/?probe=b6aec97c45) | Nov 11, 2019 |
| ASUSTek       | B9440UA                     | [2831200d03](https://linux-hardware.org/?probe=2831200d03) | Nov 11, 2019 |
| ASUSTek       | B9440UA                     | [e1c1659815](https://linux-hardware.org/?probe=e1c1659815) | Nov 11, 2019 |
| ASUSTek       | B9440UA                     | [79c10ef42c](https://linux-hardware.org/?probe=79c10ef42c) | Nov 11, 2019 |
| Alienware     | M14xR1                      | [8be5b82b62](https://linux-hardware.org/?probe=8be5b82b62) | Nov 10, 2019 |
| Lenovo        | G710 20252                  | [21ae1ec676](https://linux-hardware.org/?probe=21ae1ec676) | Nov 10, 2019 |
| HP            | ProBook 6470b               | [ef310ee8d7](https://linux-hardware.org/?probe=ef310ee8d7) | Nov 09, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [e3a70e566b](https://linux-hardware.org/?probe=e3a70e566b) | Nov 07, 2019 |
| Sony          | VPCZ227GG                   | [6e74a95929](https://linux-hardware.org/?probe=6e74a95929) | Oct 23, 2019 |
| HP            | 15                          | [918baa5980](https://linux-hardware.org/?probe=918baa5980) | Oct 22, 2019 |
| Lenovo        | G550 2958                   | [7a2714efe5](https://linux-hardware.org/?probe=7a2714efe5) | Oct 21, 2019 |
| Acer          | Aspire 6930G                | [00dd5c3407](https://linux-hardware.org/?probe=00dd5c3407) | Oct 19, 2019 |
| Samsung       | 305E4A/305E5A/305E7A        | [460d3c193d](https://linux-hardware.org/?probe=460d3c193d) | Oct 18, 2019 |
| AMI           | Cherry Trail CR             | [b0d2ba14cc](https://linux-hardware.org/?probe=b0d2ba14cc) | Oct 17, 2019 |
| AMI           | Cherry Trail CR             | [0a982341da](https://linux-hardware.org/?probe=0a982341da) | Oct 15, 2019 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [a605c98275](https://linux-hardware.org/?probe=a605c98275) | Oct 13, 2019 |
| Toshiba       | Satellite A210              | [afeba73834](https://linux-hardware.org/?probe=afeba73834) | Oct 12, 2019 |
| Dell          | Latitude E6430              | [eb05a0d70d](https://linux-hardware.org/?probe=eb05a0d70d) | Oct 11, 2019 |
| Dell          | Latitude E6430              | [3aa2fae20e](https://linux-hardware.org/?probe=3aa2fae20e) | Oct 11, 2019 |
| Dell          | Latitude E6430              | [35e84bfd49](https://linux-hardware.org/?probe=35e84bfd49) | Oct 11, 2019 |
| Toshiba       | Satellite L845              | [f39187603d](https://linux-hardware.org/?probe=f39187603d) | Oct 09, 2019 |
| HP            | ProBook 450 G2              | [b87761d1c1](https://linux-hardware.org/?probe=b87761d1c1) | Oct 07, 2019 |
| Toshiba       | Satellite A210              | [9aa0cba799](https://linux-hardware.org/?probe=9aa0cba799) | Sep 28, 2019 |
| HP            | EliteBook 8560p             | [ea58ac738c](https://linux-hardware.org/?probe=ea58ac738c) | Sep 25, 2019 |
| Toshiba       | Satellite A210              | [e87c4898cc](https://linux-hardware.org/?probe=e87c4898cc) | Sep 21, 2019 |
| Toshiba       | Satellite A210              | [64a6ba8511](https://linux-hardware.org/?probe=64a6ba8511) | Sep 21, 2019 |
| Toshiba       | Satellite A210              | [8017271f37](https://linux-hardware.org/?probe=8017271f37) | Sep 21, 2019 |
| Alienware     | M14xR2                      | [6bf9694a56](https://linux-hardware.org/?probe=6bf9694a56) | Sep 17, 2019 |
| HP            | ProBook 640 G2              | [c4ee36c621](https://linux-hardware.org/?probe=c4ee36c621) | Sep 15, 2019 |
| HP            | 630                         | [8cb4c328bb](https://linux-hardware.org/?probe=8cb4c328bb) | Sep 10, 2019 |
| Lenovo        | Z50-70 20354                | [93800ed65a](https://linux-hardware.org/?probe=93800ed65a) | Sep 06, 2019 |
| Lenovo        | Edge 2-1580 80QF            | [b1950e5bff](https://linux-hardware.org/?probe=b1950e5bff) | Sep 04, 2019 |
| Purism        | Librem 13 v2                | [fa805c25c3](https://linux-hardware.org/?probe=fa805c25c3) | Aug 31, 2019 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [2a2ba2584f](https://linux-hardware.org/?probe=2a2ba2584f) | Aug 30, 2019 |
| Positivo      | Mobile                      | [7ceaddd485](https://linux-hardware.org/?probe=7ceaddd485) | Aug 29, 2019 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [6821f97b7e](https://linux-hardware.org/?probe=6821f97b7e) | Aug 28, 2019 |
| Dell          | Latitude E5470              | [0652d6a102](https://linux-hardware.org/?probe=0652d6a102) | Aug 26, 2019 |
| HP            | 15                          | [9bafe7cbbc](https://linux-hardware.org/?probe=9bafe7cbbc) | Aug 21, 2019 |
| Acer          | Nitro AN515-42              | [c5d12ef3a9](https://linux-hardware.org/?probe=c5d12ef3a9) | Aug 21, 2019 |
| Lenovo        | IdeaPad Z570 10243VU        | [b668fbf73f](https://linux-hardware.org/?probe=b668fbf73f) | Aug 20, 2019 |
| Panasonic     | CF-SX2JDQZF5                | [6986c9f2d2](https://linux-hardware.org/?probe=6986c9f2d2) | Aug 17, 2019 |
| Dell          | Latitude E6410              | [1ab976aaff](https://linux-hardware.org/?probe=1ab976aaff) | Aug 15, 2019 |
| Toshiba       | Satellite E45t-B            | [156d965d57](https://linux-hardware.org/?probe=156d965d57) | Aug 14, 2019 |
| HP            | 3085B                       | [eeb9f3af7f](https://linux-hardware.org/?probe=eeb9f3af7f) | Aug 11, 2019 |
| Panasonic     | CF-191FYC51M                | [beedf64235](https://linux-hardware.org/?probe=beedf64235) | Aug 11, 2019 |
| Panasonic     | CF-191FYC51M                | [77a0f7454e](https://linux-hardware.org/?probe=77a0f7454e) | Aug 11, 2019 |
| Dell          | Studio XPS 1640             | [549588a8f2](https://linux-hardware.org/?probe=549588a8f2) | Aug 10, 2019 |
| Acer          | Aspire E1-571               | [16eca8b913](https://linux-hardware.org/?probe=16eca8b913) | Aug 09, 2019 |
| Sony          | VPCEH17FG                   | [68a12a9dfa](https://linux-hardware.org/?probe=68a12a9dfa) | Aug 08, 2019 |
| Sony          | VPCEH17FG                   | [f5b54a27c8](https://linux-hardware.org/?probe=f5b54a27c8) | Aug 08, 2019 |
| Lenovo        | ThinkPad T460s 20FAS3J30... | [9ffffef6da](https://linux-hardware.org/?probe=9ffffef6da) | Aug 06, 2019 |
| Ematic        | EWT147                      | [7ccb76ba13](https://linux-hardware.org/?probe=7ccb76ba13) | Aug 06, 2019 |
| Lenovo        | ThinkPad T530 2392APU       | [364e945cdb](https://linux-hardware.org/?probe=364e945cdb) | Aug 04, 2019 |
| Intel         | Crestline & ICH8M Chipse... | [6b7d39e528](https://linux-hardware.org/?probe=6b7d39e528) | Aug 04, 2019 |
| Intel         | Crestline & ICH8M Chipse... | [3ddc525fa7](https://linux-hardware.org/?probe=3ddc525fa7) | Aug 04, 2019 |
| Intel         | Crestline & ICH8M Chipse... | [46e388cd1c](https://linux-hardware.org/?probe=46e388cd1c) | Aug 04, 2019 |
| Intel         | Crestline & ICH8M Chipse... | [12a25c12c5](https://linux-hardware.org/?probe=12a25c12c5) | Aug 04, 2019 |
| Dell          | Inspiron 5521               | [5e78d3fef1](https://linux-hardware.org/?probe=5e78d3fef1) | Jul 29, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [c61c9e33f6](https://linux-hardware.org/?probe=c61c9e33f6) | Jul 28, 2019 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [d0006f445b](https://linux-hardware.org/?probe=d0006f445b) | Jul 28, 2019 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [7957c03703](https://linux-hardware.org/?probe=7957c03703) | Jul 28, 2019 |
| HP            | ENVY m6                     | [a978f2ca38](https://linux-hardware.org/?probe=a978f2ca38) | Jul 25, 2019 |
| Dell          | XPS 15 9570                 | [7a9639f003](https://linux-hardware.org/?probe=7a9639f003) | Jul 24, 2019 |
| Dell          | XPS 15 9570                 | [9ca695a346](https://linux-hardware.org/?probe=9ca695a346) | Jul 24, 2019 |
| HP            | EliteBook 840 G1            | [a6a99375a8](https://linux-hardware.org/?probe=a6a99375a8) | Jul 22, 2019 |
| HP            | Pavilion tx1000             | [4a6a073320](https://linux-hardware.org/?probe=4a6a073320) | Jul 22, 2019 |
| TUXEDO        | Unknown                     | [087a8f3344](https://linux-hardware.org/?probe=087a8f3344) | Jul 21, 2019 |
| HP            | Compaq nc6400 (RM100ET#A... | [9f51d8d813](https://linux-hardware.org/?probe=9f51d8d813) | Jul 21, 2019 |
| Dell          | Inspiron 3521               | [b471f52a9a](https://linux-hardware.org/?probe=b471f52a9a) | Jul 20, 2019 |
| HP            | EliteBook 840 G1            | [6b7fcf488f](https://linux-hardware.org/?probe=6b7fcf488f) | Jul 20, 2019 |
| HP            | EliteBook 840 G1            | [3383755a58](https://linux-hardware.org/?probe=3383755a58) | Jul 20, 2019 |
| HP            | EliteBook 840 G1            | [9af22b6c49](https://linux-hardware.org/?probe=9af22b6c49) | Jul 20, 2019 |
| HP            | EliteBook 840 G1            | [b3bb828c5a](https://linux-hardware.org/?probe=b3bb828c5a) | Jul 19, 2019 |
| Apple         | MacBookPro5,1               | [e6f14346be](https://linux-hardware.org/?probe=e6f14346be) | Jul 15, 2019 |
| HP            | Laptop 15-dw0xxx            | [70f1f2130b](https://linux-hardware.org/?probe=70f1f2130b) | Jul 15, 2019 |
| HP            | Pavilion g7                 | [fef9011be9](https://linux-hardware.org/?probe=fef9011be9) | Jul 13, 2019 |
| HP            | Pavilion g7                 | [586d054ba7](https://linux-hardware.org/?probe=586d054ba7) | Jul 13, 2019 |
| Toshiba       | Satellite C55D-A            | [98772b73bb](https://linux-hardware.org/?probe=98772b73bb) | Jul 12, 2019 |
| HP            | Laptop 15-dw0xxx            | [3c4f4aba16](https://linux-hardware.org/?probe=3c4f4aba16) | Jul 09, 2019 |
| Dell          | Inspiron 7520               | [8529fa049a](https://linux-hardware.org/?probe=8529fa049a) | Jul 04, 2019 |
| Dell          | Inspiron 7520               | [3227e98bbe](https://linux-hardware.org/?probe=3227e98bbe) | Jul 04, 2019 |
| Sony          | VPCZ227GG                   | [9109d4a264](https://linux-hardware.org/?probe=9109d4a264) | Jul 03, 2019 |
| HP            | ProBook 450 G4              | [4fb036ba95](https://linux-hardware.org/?probe=4fb036ba95) | Jul 03, 2019 |
| HP            | ProBook 4730s               | [ed98a45d81](https://linux-hardware.org/?probe=ed98a45d81) | Jul 01, 2019 |
| Sony          | SVF1521B1EW                 | [20f5b70678](https://linux-hardware.org/?probe=20f5b70678) | Jun 28, 2019 |
| Dell          | Latitude E7240              | [9cc6b87f3a](https://linux-hardware.org/?probe=9cc6b87f3a) | Jun 25, 2019 |
| ASUSTek       | X541UVK                     | [baf89919e7](https://linux-hardware.org/?probe=baf89919e7) | Jun 24, 2019 |
| ASUSTek       | T300CHI                     | [1211294e7c](https://linux-hardware.org/?probe=1211294e7c) | Jun 23, 2019 |
| Toshiba       | Satellite P755              | [d9fc00d39e](https://linux-hardware.org/?probe=d9fc00d39e) | Jun 17, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | [7d66aa72d3](https://linux-hardware.org/?probe=7d66aa72d3) | Jun 10, 2019 |
| ASUSTek       | T102HA                      | [1a0e086ef8](https://linux-hardware.org/?probe=1a0e086ef8) | Jun 10, 2019 |
| HP            | Pavilion tx1000             | [a783eb7140](https://linux-hardware.org/?probe=a783eb7140) | Jun 08, 2019 |
| Toshiba       | Satellite A215              | [08d2d708f8](https://linux-hardware.org/?probe=08d2d708f8) | May 23, 2019 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.3.0-40-generic        | 68        | 6.74%   |
| 5.4.0-42-generic        | 62        | 6.14%   |
| 5.3.0-46-generic        | 54        | 5.35%   |
| 5.3.0-51-generic        | 48        | 4.76%   |
| 5.0.0-37-generic        | 47        | 4.66%   |
| 5.4.0-47-generic        | 38        | 3.77%   |
| 5.3.0-53-generic        | 37        | 3.67%   |
| 5.3.0-42-generic        | 36        | 3.57%   |
| 5.4.0-45-generic        | 32        | 3.17%   |
| 5.4.0-58-generic        | 31        | 3.07%   |
| 5.4.0-48-generic        | 31        | 3.07%   |
| 5.4.0-65-generic        | 28        | 2.78%   |
| 5.4.0-80-generic        | 26        | 2.58%   |
| 5.4.0-72-generic        | 24        | 2.38%   |
| 5.4.0-52-generic        | 23        | 2.28%   |
| 5.4.0-73-generic        | 21        | 2.08%   |
| 5.4.0-81-generic        | 19        | 1.88%   |
| 5.4.0-70-generic        | 19        | 1.88%   |
| 5.3.0-62-generic        | 19        | 1.88%   |
| 5.3.0-45-generic        | 18        | 1.78%   |
| 5.4.0-66-generic        | 17        | 1.68%   |
| 5.4.0-54-generic        | 17        | 1.68%   |
| 5.3.0-59-generic        | 17        | 1.68%   |
| 5.3.0-28-generic        | 17        | 1.68%   |
| 4.18.0-25-generic       | 16        | 1.59%   |
| 5.4.0-87-generic        | 15        | 1.49%   |
| 5.4.0-77-generic        | 14        | 1.39%   |
| 5.4.0-64-generic        | 13        | 1.29%   |
| 5.0.0-36-generic        | 13        | 1.29%   |
| 4.18.0-21-generic       | 13        | 1.29%   |
| 5.4.0-89-generic        | 12        | 1.19%   |
| 4.18.0-22-generic       | 12        | 1.19%   |
| 5.4.0-74-generic        | 11        | 1.09%   |
| 5.4.0-56-generic        | 11        | 1.09%   |
| 5.3.0-61-generic        | 11        | 1.09%   |
| 5.4.0-53-generic        | 10        | 0.99%   |
| 5.3.0-26-generic        | 9         | 0.89%   |
| 5.4.0-90-generic        | 8         | 0.79%   |
| 5.4.0-67-generic        | 8         | 0.79%   |
| 5.4.0-62-generic        | 8         | 0.79%   |
| 5.4.0-84-generic        | 7         | 0.69%   |
| 5.4.0-51-generic        | 7         | 0.69%   |
| 5.0.0-25-generic        | 7         | 0.69%   |
| 5.0.0-23-generic        | 7         | 0.69%   |
| 5.0.0-32-generic        | 6         | 0.59%   |
| 5.0.0-31-generic        | 6         | 0.59%   |
| 5.4.0-60-generic        | 5         | 0.5%    |
| 5.4.0-59-generic        | 4         | 0.4%    |
| 5.4.0-86-generic        | 3         | 0.3%    |
| 5.0.0-29-generic        | 3         | 0.3%    |
| 5.4.0-71-generic        | 2         | 0.2%    |
| 5.0.0-27-generic        | 2         | 0.2%    |
| 4.18.0-24-generic       | 2         | 0.2%    |
| 5.9.12-050912-generic   | 1         | 0.1%    |
| 5.9.0-rc4+              | 1         | 0.1%    |
| 5.7.1-050701-generic    | 1         | 0.1%    |
| 5.6.0-999-lowlatency    | 1         | 0.1%    |
| 5.6.0-050600rc7-generic | 1         | 0.1%    |
| 5.4.1-050401-generic    | 1         | 0.1%    |
| 5.4.0-58-lowlatency     | 1         | 0.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 478       | 51.29%  |
| 5.3.0   | 313       | 33.58%  |
| 5.0.0   | 90        | 9.66%   |
| 4.18.0  | 43        | 4.61%   |
| 5.6.0   | 2         | 0.21%   |
| 5.9.12  | 1         | 0.11%   |
| 5.9.0   | 1         | 0.11%   |
| 5.7.1   | 1         | 0.11%   |
| 5.4.1   | 1         | 0.11%   |
| 5.10.35 | 1         | 0.11%   |
| 5.10.16 | 1         | 0.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 479       | 51.39%  |
| 5.3     | 313       | 33.58%  |
| 5.0     | 90        | 9.66%   |
| 4.18    | 43        | 4.61%   |
| 5.9     | 2         | 0.21%   |
| 5.6     | 2         | 0.21%   |
| 5.10    | 2         | 0.21%   |
| 5.7     | 1         | 0.11%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 734       | 81.37%  |
| i686   | 168       | 18.63%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 489       | 53.62%  |
| XFCE       | 329       | 36.07%  |
| Unknown    | 90        | 9.87%   |
| KDE        | 2         | 0.22%   |
| X-Cinnamon | 1         | 0.11%   |
| Unity      | 1         | 0.11%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 838       | 91.89%  |
| Unknown | 63        | 6.91%   |
| Wayland | 11        | 1.21%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 853       | 93.74%  |
| LightDM | 31        | 3.41%   |
| GDM3    | 12        | 1.32%   |
| GDM     | 8         | 0.88%   |
| TDM     | 6         | 0.66%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 285       | 31.39%  |
| pt_BR   | 74        | 8.15%   |
| Unknown | 61        | 6.72%   |
| it_IT   | 45        | 4.96%   |
| de_DE   | 45        | 4.96%   |
| en_GB   | 40        | 4.41%   |
| en_IN   | 34        | 3.74%   |
| en_CA   | 29        | 3.19%   |
| pl_PL   | 24        | 2.64%   |
| es_ES   | 23        | 2.53%   |
| pt_PT   | 21        | 2.31%   |
| fr_FR   | 17        | 1.87%   |
| C       | 17        | 1.87%   |
| es_AR   | 15        | 1.65%   |
| ru_RU   | 13        | 1.43%   |
| en_AU   | 12        | 1.32%   |
| cs_CZ   | 12        | 1.32%   |
| tr_TR   | 10        | 1.1%    |
| nl_NL   | 9         | 0.99%   |
| es_MX   | 9         | 0.99%   |
| es_CL   | 8         | 0.88%   |
| ja_JP   | 7         | 0.77%   |
| fr_CA   | 7         | 0.77%   |
| en_ZA   | 7         | 0.77%   |
| en_NZ   | 6         | 0.66%   |
| el_GR   | 6         | 0.66%   |
| de_AT   | 6         | 0.66%   |
| sv_SE   | 5         | 0.55%   |
| da_DK   | 5         | 0.55%   |
| ru_UA   | 4         | 0.44%   |
| ro_RO   | 4         | 0.44%   |
| hu_HU   | 4         | 0.44%   |
| es_PE   | 4         | 0.44%   |
| en_PH   | 4         | 0.44%   |
| sk_SK   | 3         | 0.33%   |
| es_CO   | 3         | 0.33%   |
| nl_BE   | 2         | 0.22%   |
| fi_FI   | 2         | 0.22%   |
| es_VE   | 2         | 0.22%   |
| es_PA   | 2         | 0.22%   |
| es_EC   | 2         | 0.22%   |
| en_IL   | 2         | 0.22%   |
| de_CH   | 2         | 0.22%   |
| bg_BG   | 2         | 0.22%   |
| sr_RS   | 1         | 0.11%   |
| sl_SI   | 1         | 0.11%   |
| nb_NO   | 1         | 0.11%   |
| ko_KR   | 1         | 0.11%   |
| is_IS   | 1         | 0.11%   |
| id_ID   | 1         | 0.11%   |
| hr_HR   | 1         | 0.11%   |
| es_UY   | 1         | 0.11%   |
| es_HN   | 1         | 0.11%   |
| en_ZM   | 1         | 0.11%   |
| en_SG   | 1         | 0.11%   |
| en_IE   | 1         | 0.11%   |
| de_BE   | 1         | 0.11%   |
| bs_BA   | 1         | 0.11%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 622       | 68.05%  |
| EFI  | 292       | 31.95%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 848       | 93.81%  |
| Overlay | 30        | 3.32%   |
| Unknown | 14        | 1.55%   |
| Btrfs   | 6         | 0.66%   |
| Ext2    | 5         | 0.55%   |
| Ext3    | 1         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 885       | 98.22%  |
| MBR     | 10        | 1.11%   |
| GPT     | 6         | 0.67%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 828       | 91.39%  |
| Yes       | 78        | 8.61%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 658       | 72.55%  |
| Yes       | 249       | 27.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Hewlett-Packard                | 220       | 24.42%  |
| Dell                           | 132       | 14.65%  |
| Lenovo                         | 115       | 12.76%  |
| ASUSTek Computer               | 83        | 9.21%   |
| Acer                           | 80        | 8.88%   |
| Toshiba                        | 62        | 6.88%   |
| Samsung Electronics            | 26        | 2.89%   |
| Sony                           | 19        | 2.11%   |
| Apple                          | 15        | 1.66%   |
| Unknown                        | 13        | 1.44%   |
| Positivo                       | 9         | 1%      |
| Fujitsu Siemens                | 9         | 1%      |
| Packard Bell                   | 8         | 0.89%   |
| MSI                            | 8         | 0.89%   |
| Panasonic                      | 6         | 0.67%   |
| Fujitsu                        | 6         | 0.67%   |
| HUAWEI                         | 5         | 0.55%   |
| Notebook                       | 4         | 0.44%   |
| NEC Computers                  | 4         | 0.44%   |
| Medion                         | 4         | 0.44%   |
| Gateway                        | 4         | 0.44%   |
| eMachines                      | 4         | 0.44%   |
| AMI                            | 4         | 0.44%   |
| Semp Toshiba                   | 3         | 0.33%   |
| Itautec                        | 3         | 0.33%   |
| Insyde                         | 3         | 0.33%   |
| Google                         | 3         | 0.33%   |
| Ematic                         | 3         | 0.33%   |
| Alienware                      | 3         | 0.33%   |
| TrekStor                       | 2         | 0.22%   |
| Quanta                         | 2         | 0.22%   |
| Intel                          | 2         | 0.22%   |
| IBM                            | 2         | 0.22%   |
| Durabook                       | 2         | 0.22%   |
| Digibras                       | 2         | 0.22%   |
| Clevo                          | 2         | 0.22%   |
| ARIMA                          | 2         | 0.22%   |
| WIPRO                          | 1         | 0.11%   |
| UMAX                           | 1         | 0.11%   |
| TUXEDO                         | 1         | 0.11%   |
| SiS                            | 1         | 0.11%   |
| Qbex                           | 1         | 0.11%   |
| Purism                         | 1         | 0.11%   |
| Phoenix/SiS                    | 1         | 0.11%   |
| Philco                         | 1         | 0.11%   |
| Pendo Industries               | 1         | 0.11%   |
| Olidata                        | 1         | 0.11%   |
| Nuvision                       | 1         | 0.11%   |
| Multilaser                     | 1         | 0.11%   |
| Minix                          | 1         | 0.11%   |
| Matsushita Electric Industrial | 1         | 0.11%   |
| Hometech                       | 1         | 0.11%   |
| HCL Infosystems Limited        | 1         | 0.11%   |
| GPD                            | 1         | 0.11%   |
| Gigabyte Technology            | 1         | 0.11%   |
| ECS                            | 1         | 0.11%   |
| Dixonsxp                       | 1         | 0.11%   |
| Compaq                         | 1         | 0.11%   |
| Compal                         | 1         | 0.11%   |
| Bluechip Computer              | 1         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 20        | 2.22%   |
| HP Pavilion dv6                     | 6         | 0.67%   |
| HP Notebook                         | 6         | 0.67%   |
| Positivo Mobile                     | 5         | 0.55%   |
| HP Pavilion dv7                     | 5         | 0.55%   |
| HP Pavilion dv6700                  | 5         | 0.55%   |
| Toshiba Satellite C660              | 4         | 0.44%   |
| HP Laptop 15-bw0xx                  | 4         | 0.44%   |
| HP Compaq Presario CQ61             | 4         | 0.44%   |
| HP 530                              | 4         | 0.44%   |
| HP 15                               | 4         | 0.44%   |
| Dell Latitude E6410                 | 4         | 0.44%   |
| Dell Latitude E6400                 | 4         | 0.44%   |
| Dell Latitude D630                  | 4         | 0.44%   |
| Toshiba Satellite C55-A             | 3         | 0.33%   |
| Samsung 340XAA/350XAA/550XAA        | 3         | 0.33%   |
| Packard Bell EasyNote TJ65          | 3         | 0.33%   |
| HUAWEI BOHK-WAX9X                   | 3         | 0.33%   |
| HP ProBook 4540s                    | 3         | 0.33%   |
| HP Pavilion g7                      | 3         | 0.33%   |
| HP Pavilion dv5                     | 3         | 0.33%   |
| HP EliteBook 8460p                  | 3         | 0.33%   |
| HP EliteBook 840 G1                 | 3         | 0.33%   |
| HP EliteBook 6930p                  | 3         | 0.33%   |
| HP Compaq Presario CQ60             | 3         | 0.33%   |
| Dell Latitude D520                  | 3         | 0.33%   |
| Dell Inspiron N4010                 | 3         | 0.33%   |
| Dell Inspiron 7520                  | 3         | 0.33%   |
| Dell Inspiron 6000                  | 3         | 0.33%   |
| Dell Inspiron 3521                  | 3         | 0.33%   |
| Dell Inspiron 1545                  | 3         | 0.33%   |
| Dell Inspiron 1520                  | 3         | 0.33%   |
| Dell Inspiron 15-3567               | 3         | 0.33%   |
| Acer Aspire one                     | 3         | 0.33%   |
| TrekStor Notebook Slim S130         | 2         | 0.22%   |
| Toshiba Satellite M70               | 2         | 0.22%   |
| Toshiba Satellite A215              | 2         | 0.22%   |
| Toshiba Satellite A100              | 2         | 0.22%   |
| Samsung 305E4A/305E5A/305E7A        | 2         | 0.22%   |
| Positivo S14CT01                    | 2         | 0.22%   |
| Lenovo Z50-70 20354                 | 2         | 0.22%   |
| Lenovo Y70-70 Touch 80DU            | 2         | 0.22%   |
| Lenovo V145-15AST 81MT              | 2         | 0.22%   |
| Lenovo IdeaPad Slim 1-14AST-05 81VS | 2         | 0.22%   |
| Lenovo IdeaPad S130-11IGM 81J1      | 2         | 0.22%   |
| Lenovo IdeaPad 330-15AST 81D6       | 2         | 0.22%   |
| Lenovo IdeaPad 330-14AST 81D5       | 2         | 0.22%   |
| Lenovo IdeaPad 100S-14IBR 80R9      | 2         | 0.22%   |
| Lenovo G40-30 80FY                  | 2         | 0.22%   |
| Itautec Infoway                     | 2         | 0.22%   |
| HP ProBook 450 G3                   | 2         | 0.22%   |
| HP ProBook 450 G2                   | 2         | 0.22%   |
| HP Pavilion x2 Detachable           | 2         | 0.22%   |
| HP Pavilion tx1000                  | 2         | 0.22%   |
| HP Pavilion Notebook                | 2         | 0.22%   |
| HP Pavilion Laptop 15-cs0xxx        | 2         | 0.22%   |
| HP Pavilion g6                      | 2         | 0.22%   |
| HP Pavilion dv9500                  | 2         | 0.22%   |
| HP Pavilion dm1                     | 2         | 0.22%   |
| HP Pavilion 17                      | 2         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Dell Inspiron            | 63        | 6.99%   |
| HP Pavilion              | 57        | 6.33%   |
| Acer Aspire              | 57        | 6.33%   |
| Toshiba Satellite        | 55        | 6.1%    |
| Lenovo ThinkPad          | 45        | 4.99%   |
| Dell Latitude            | 44        | 4.88%   |
| Lenovo IdeaPad           | 37        | 4.11%   |
| HP EliteBook             | 26        | 2.89%   |
| HP ProBook               | 23        | 2.55%   |
| HP Compaq                | 21        | 2.33%   |
| Unknown                  | 20        | 2.22%   |
| HP Laptop                | 16        | 1.78%   |
| Dell Vostro              | 10        | 1.11%   |
| HP Presario              | 9         | 1%      |
| Packard Bell EasyNote    | 8         | 0.89%   |
| HP Mini                  | 7         | 0.78%   |
| HP Notebook              | 6         | 0.67%   |
| HP ENVY                  | 6         | 0.67%   |
| HP 255                   | 6         | 0.67%   |
| Positivo Mobile          | 5         | 0.55%   |
| HP Stream                | 5         | 0.55%   |
| HP 530                   | 5         | 0.55%   |
| Fujitsu Siemens AMILO    | 5         | 0.55%   |
| Dell XPS                 | 5         | 0.55%   |
| ASUS VivoBook            | 5         | 0.55%   |
| HP ZBook                 | 4         | 0.44%   |
| HP 15                    | 4         | 0.44%   |
| Fujitsu LIFEBOOK         | 4         | 0.44%   |
| ASUS ROG                 | 4         | 0.44%   |
| Acer Extensa             | 4         | 0.44%   |
| Samsung 340XAA           | 3         | 0.33%   |
| Itautec Infoway          | 3         | 0.33%   |
| HUAWEI BOHK-WAX9X        | 3         | 0.33%   |
| Dell Studio              | 3         | 0.33%   |
| Dell Precision           | 3         | 0.33%   |
| ASUS ZenBook             | 3         | 0.33%   |
| ASUS TUF                 | 3         | 0.33%   |
| TrekStor Notebook        | 2         | 0.22%   |
| Toshiba QOSMIO           | 2         | 0.22%   |
| Toshiba PORTEGE          | 2         | 0.22%   |
| Samsung N150             | 2         | 0.22%   |
| Samsung 305E4A           | 2         | 0.22%   |
| Positivo S14CT01         | 2         | 0.22%   |
| Lenovo Z50-70            | 2         | 0.22%   |
| Lenovo Y70-70            | 2         | 0.22%   |
| Lenovo V145-15AST        | 2         | 0.22%   |
| Lenovo G560              | 2         | 0.22%   |
| Lenovo G550              | 2         | 0.22%   |
| Lenovo G40-30            | 2         | 0.22%   |
| IBM ThinkPad             | 2         | 0.22%   |
| HP G42                   | 2         | 0.22%   |
| HP 635                   | 2         | 0.22%   |
| HP 550                   | 2         | 0.22%   |
| HP 250                   | 2         | 0.22%   |
| HP 2000                  | 2         | 0.22%   |
| HP 14                    | 2         | 0.22%   |
| Fujitsu Siemens LIFEBOOK | 2         | 0.22%   |
| Fujitsu Siemens ESPRIMO  | 2         | 0.22%   |
| Durabook S15H            | 2         | 0.22%   |
| Dell G5                  | 2         | 0.22%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 102       | 11.32%  |
| 2011    | 91        | 10.1%   |
| 2018    | 82        | 9.1%    |
| 2009    | 76        | 8.44%   |
| 2008    | 70        | 7.77%   |
| 2010    | 62        | 6.88%   |
| 2013    | 59        | 6.55%   |
| 2012    | 54        | 5.99%   |
| 2014    | 49        | 5.44%   |
| 2007    | 44        | 4.88%   |
| 2020    | 43        | 4.77%   |
| 2015    | 43        | 4.77%   |
| 2016    | 39        | 4.33%   |
| 2017    | 35        | 3.88%   |
| 2006    | 25        | 2.77%   |
| 2005    | 21        | 2.33%   |
| 2021    | 5         | 0.55%   |
| Unknown | 1         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 901       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 838       | 92.8%   |
| Enabled  | 65        | 7.2%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 897       | 99.56%  |
| Yes  | 4         | 0.44%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 294       | 32.41%  |
| 4.01-8.0    | 188       | 20.73%  |
| 1.01-2.0    | 157       | 17.31%  |
| 8.01-16.0   | 102       | 11.25%  |
| 2.01-3.0    | 58        | 6.39%   |
| 16.01-24.0  | 49        | 5.4%    |
| 0.51-1.0    | 47        | 5.18%   |
| 32.01-64.0  | 9         | 0.99%   |
| 24.01-32.0  | 2         | 0.22%   |
| 64.01-256.0 | 1         | 0.11%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 463       | 48.28%  |
| 2.01-3.0  | 200       | 20.86%  |
| 0.51-1.0  | 154       | 16.06%  |
| 3.01-4.0  | 81        | 8.45%   |
| 4.01-8.0  | 49        | 5.11%   |
| 0.01-0.5  | 9         | 0.94%   |
| 8.01-16.0 | 3         | 0.31%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 701       | 76.95%  |
| 2      | 179       | 19.65%  |
| 3      | 22        | 2.41%   |
| 4      | 3         | 0.33%   |
| 0      | 3         | 0.33%   |
| 5      | 2         | 0.22%   |
| 6      | 1         | 0.11%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 512       | 56.64%  |
| No        | 392       | 43.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 804       | 89.04%  |
| No        | 99        | 10.96%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 876       | 97.12%  |
| No        | 26        | 2.88%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 516       | 56.83%  |
| No        | 392       | 43.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 166       | 18.34%  |
| Brazil       | 86        | 9.5%    |
| Germany      | 56        | 6.19%   |
| UK           | 46        | 5.08%   |
| Italy        | 46        | 5.08%   |
| Canada       | 40        | 4.42%   |
| India        | 37        | 4.09%   |
| Poland       | 25        | 2.76%   |
| Portugal     | 23        | 2.54%   |
| Spain        | 21        | 2.32%   |
| France       | 21        | 2.32%   |
| Argentina    | 18        | 1.99%   |
| Netherlands  | 17        | 1.88%   |
| Mexico       | 16        | 1.77%   |
| Czechia      | 15        | 1.66%   |
| Australia    | 15        | 1.66%   |
| Sweden       | 14        | 1.55%   |
| Romania      | 13        | 1.44%   |
| Indonesia    | 13        | 1.44%   |
| Turkey       | 10        | 1.1%    |
| Russia       | 10        | 1.1%    |
| Greece       | 10        | 1.1%    |
| South Africa | 9         | 0.99%   |
| New Zealand  | 9         | 0.99%   |
| Switzerland  | 8         | 0.88%   |
| Austria      | 8         | 0.88%   |
| Serbia       | 7         | 0.77%   |
| Japan        | 7         | 0.77%   |
| Chile        | 7         | 0.77%   |
| Ukraine      | 6         | 0.66%   |
| Philippines  | 6         | 0.66%   |
| Egypt        | 6         | 0.66%   |
| Denmark      | 6         | 0.66%   |
| Colombia     | 6         | 0.66%   |
| Belgium      | 6         | 0.66%   |
| Peru         | 5         | 0.55%   |
| Israel       | 5         | 0.55%   |
| Bulgaria     | 5         | 0.55%   |
| Slovakia     | 4         | 0.44%   |
| Norway       | 4         | 0.44%   |
| Kenya        | 4         | 0.44%   |
| Hungary      | 4         | 0.44%   |
| Ecuador      | 4         | 0.44%   |
| UAE          | 3         | 0.33%   |
| Tunisia      | 3         | 0.33%   |
| Thailand     | 3         | 0.33%   |
| Panama       | 3         | 0.33%   |
| Ireland      | 3         | 0.33%   |
| Finland      | 3         | 0.33%   |
| Bangladesh   | 3         | 0.33%   |
| Vietnam      | 2         | 0.22%   |
| Venezuela    | 2         | 0.22%   |
| Sri Lanka    | 2         | 0.22%   |
| South Korea  | 2         | 0.22%   |
| Malaysia     | 2         | 0.22%   |
| Lithuania    | 2         | 0.22%   |
| Iraq         | 2         | 0.22%   |
| Iran         | 2         | 0.22%   |
| Croatia      | 2         | 0.22%   |
| Zambia       | 1         | 0.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Milan          | 8         | 0.84%   |
| São Paulo     | 7         | 0.73%   |
| Vienna         | 6         | 0.63%   |
| Rome           | 6         | 0.63%   |
| Prague         | 6         | 0.63%   |
| Johannesburg   | 6         | 0.63%   |
| Delhi          | 6         | 0.63%   |
| Buenos Aires   | 6         | 0.63%   |
| Sydney         | 5         | 0.52%   |
| Stuttgart      | 5         | 0.52%   |
| Rio de Janeiro | 5         | 0.52%   |
| Mexico City    | 5         | 0.52%   |
| Lisbon         | 5         | 0.52%   |
| Istanbul       | 5         | 0.52%   |
| Berlin         | 5         | 0.52%   |
| Belgrade       | 5         | 0.52%   |
| Auckland       | 5         | 0.52%   |
| Zurich         | 4         | 0.42%   |
| Winnipeg       | 4         | 0.42%   |
| Warsaw         | 4         | 0.42%   |
| Surabaya       | 4         | 0.42%   |
| Stockholm      | 4         | 0.42%   |
| Sofia          | 4         | 0.42%   |
| Paris          | 4         | 0.42%   |
| Nairobi        | 4         | 0.42%   |
| Munich         | 4         | 0.42%   |
| Montreal       | 4         | 0.42%   |
| Lima           | 4         | 0.42%   |
| Jakarta        | 4         | 0.42%   |
| Hyderabad      | 4         | 0.42%   |
| Cairo          | 4         | 0.42%   |
| Bucharest      | 4         | 0.42%   |
| Brooklyn       | 4         | 0.42%   |
| Athens         | 4         | 0.42%   |
| Toronto        | 3         | 0.31%   |
| Salvador       | 3         | 0.31%   |
| Portland       | 3         | 0.31%   |
| Perth          | 3         | 0.31%   |
| Panama City    | 3         | 0.31%   |
| Miami          | 3         | 0.31%   |
| Madrid         | 3         | 0.31%   |
| Kyiv           | 3         | 0.31%   |
| Kolkata        | 3         | 0.31%   |
| Kennesaw       | 3         | 0.31%   |
| João Pessoa   | 3         | 0.31%   |
| Jaipur         | 3         | 0.31%   |
| Indore         | 3         | 0.31%   |
| Helsinki       | 3         | 0.31%   |
| Genoa          | 3         | 0.31%   |
| Gdansk         | 3         | 0.31%   |
| Florence       | 3         | 0.31%   |
| Düsseldorf    | 3         | 0.31%   |
| Davis          | 3         | 0.31%   |
| Copenhagen     | 3         | 0.31%   |
| Bengaluru      | 3         | 0.31%   |
| Belfast        | 3         | 0.31%   |
| Ankara         | 3         | 0.31%   |
| Volos          | 2         | 0.21%   |
| Vestal         | 2         | 0.21%   |
| Venice         | 2         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| WDC                       | 163       | 196    | 16.01%  |
| Seagate                   | 156       | 186    | 15.32%  |
| Toshiba                   | 126       | 142    | 12.38%  |
| Samsung Electronics       | 97        | 132    | 9.53%   |
| Unknown                   | 84        | 115    | 8.25%   |
| Hitachi                   | 82        | 95     | 8.06%   |
| Kingston                  | 44        | 49     | 4.32%   |
| SanDisk                   | 37        | 44     | 3.63%   |
| HGST                      | 32        | 40     | 3.14%   |
| Crucial                   | 28        | 35     | 2.75%   |
| Fujitsu                   | 22        | 22     | 2.16%   |
| Intel                     | 20        | 24     | 1.96%   |
| SK Hynix                  | 11        | 14     | 1.08%   |
| A-DATA Technology         | 8         | 8      | 0.79%   |
| China                     | 7         | 7      | 0.69%   |
| Transcend                 | 6         | 15     | 0.59%   |
| Micron Technology         | 6         | 6      | 0.59%   |
| Intenso                   | 6         | 6      | 0.59%   |
| Apple                     | 6         | 6      | 0.59%   |
| PNY                       | 5         | 5      | 0.49%   |
| LITEON                    | 5         | 7      | 0.49%   |
| Team                      | 4         | 4      | 0.39%   |
| Phison                    | 4         | 5      | 0.39%   |
| Patriot                   | 4         | 5      | 0.39%   |
| SABRENT                   | 3         | 3      | 0.29%   |
| OCZ                       | 3         | 3      | 0.29%   |
| LITEONIT                  | 3         | 3      | 0.29%   |
| Zheino                    | 2         | 2      | 0.2%    |
| TCSUNBOW                  | 2         | 2      | 0.2%    |
| SPCC                      | 2         | 2      | 0.2%    |
| PLEXTOR                   | 2         | 2      | 0.2%    |
| KingDian                  | 2         | 2      | 0.2%    |
| JMicron                   | 2         | 2      | 0.2%    |
| IBM/Hitachi               | 2         | 3      | 0.2%    |
| GOODRAM                   | 2         | 2      | 0.2%    |
| ASMT                      | 2         | 2      | 0.2%    |
| Verbatim                  | 1         | 1      | 0.1%    |
| USB30                     | 1         | 1      | 0.1%    |
| TrekStor                  | 1         | 1      | 0.1%    |
| TO Exter                  | 1         | 1      | 0.1%    |
| PNY USB                   | 1         | 1      | 0.1%    |
| Pioneer                   | 1         | 1      | 0.1%    |
| Pacific Sun               | 1         | 1      | 0.1%    |
| OWC                       | 1         | 1      | 0.1%    |
| moweek                    | 1         | 1      | 0.1%    |
| Micron/Crucial Technology | 1         | 1      | 0.1%    |
| MAXTOR                    | 1         | 1      | 0.1%    |
| Leven                     | 1         | 1      | 0.1%    |
| Kston                     | 1         | 1      | 0.1%    |
| KIOXIA                    | 1         | 1      | 0.1%    |
| Kingmax                   | 1         | 1      | 0.1%    |
| KingFast                  | 1         | 1      | 0.1%    |
| HUAWEI                    | 1         | 1      | 0.1%    |
| HS-SSD-C100               | 1         | 1      | 0.1%    |
| Hewlett-Packard           | 1         | 1      | 0.1%    |
| faspeed                   | 1         | 1      | 0.1%    |
| EMTEC                     | 1         | 1      | 0.1%    |
| DOGFISH                   | 1         | 1      | 0.1%    |
| BIWIN                     | 1         | 1      | 0.1%    |
| Biostar                   | 1         | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Unknown MMC Card  32GB               | 39        | 3.74%   |
| Toshiba MQ01ABF050 500GB             | 21        | 2.02%   |
| Unknown MMC Card  64GB               | 14        | 1.34%   |
| Seagate ST500LT012-1DG142 500GB      | 13        | 1.25%   |
| Seagate ST1000LM035-1RK172 1TB       | 11        | 1.06%   |
| Kingston SA400S37240G 240GB SSD      | 10        | 0.96%   |
| Toshiba MQ04ABF100 1TB               | 9         | 0.86%   |
| Seagate ST9500325AS 500GB            | 9         | 0.86%   |
| Seagate ST500LM012 HN-M500MBB 500GB  | 9         | 0.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 9         | 0.86%   |
| Unknown MMC Card  16GB               | 8         | 0.77%   |
| Toshiba MQ01ABD100 1TB               | 8         | 0.77%   |
| HGST HTS725050A7E630 500GB           | 8         | 0.77%   |
| Samsung NVMe SSD Drive 512GB         | 7         | 0.67%   |
| Samsung HM160HI 160GB                | 7         | 0.67%   |
| Kingston SA400S37480G 480GB SSD      | 7         | 0.67%   |
| Hitachi HTS545032B9A300 320GB        | 7         | 0.67%   |
| Hitachi HTS543232A7A384 320GB        | 7         | 0.67%   |
| Crucial CT240BX500SSD1 240GB         | 7         | 0.67%   |
| Unknown MMC Card  128GB              | 6         | 0.58%   |
| Seagate ST9250315AS 250GB            | 6         | 0.58%   |
| Samsung NVMe SSD Drive 256GB         | 6         | 0.58%   |
| Kingston SA400S37120G 120GB SSD      | 6         | 0.58%   |
| HGST HTS541010A9E680 1TB             | 6         | 0.58%   |
| WDC WD3200BEVT-22ZCT0 320GB          | 5         | 0.48%   |
| WDC WD10JPVX-60JC3T0 1TB             | 5         | 0.48%   |
| Seagate ST9320325AS 320GB            | 5         | 0.48%   |
| Seagate ST9160314AS 160GB            | 5         | 0.48%   |
| Seagate ST500LT012-9WS142 500GB      | 5         | 0.48%   |
| Samsung SSD 860 EVO 250GB            | 5         | 0.48%   |
| Samsung SSD 850 EVO 500GB            | 5         | 0.48%   |
| Samsung HM321HI 320GB                | 5         | 0.48%   |
| Intel NVMe SSD Drive 512GB           | 5         | 0.48%   |
| HGST HTS721010A9E630 1TB             | 5         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD     | 4         | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD     | 4         | 0.38%   |
| WDC WD5000LPVX-22V0TT0 500GB         | 4         | 0.38%   |
| WDC WD2500BEVT-22A23T0 250GB         | 4         | 0.38%   |
| WDC WD1600BEVT-22A23T0 160GB         | 4         | 0.38%   |
| WDC WD10JPVX-60JC3T1 1TB             | 4         | 0.38%   |
| WDC WD10JPVX-22JC3T0 1TB             | 4         | 0.38%   |
| WDC WD10JPCX-24UE4T0 1TB             | 4         | 0.38%   |
| Toshiba MQ01ABD032 320GB             | 4         | 0.38%   |
| Seagate ST9250827AS 250GB            | 4         | 0.38%   |
| Seagate ST500LM021-1KJ152 500GB      | 4         | 0.38%   |
| Seagate ST2000LM007-1R8174 2TB       | 4         | 0.38%   |
| Seagate ST1000LM014-1EJ164 1TB       | 4         | 0.38%   |
| Seagate Expansion 1TB                | 4         | 0.38%   |
| Samsung MZ7LN128HAHQ-000L2 128GB SSD | 4         | 0.38%   |
| Kingston SV300S37A120G 120GB SSD     | 4         | 0.38%   |
| Hitachi HTS547575A9E384 752GB        | 4         | 0.38%   |
| Hitachi HTS547550A9E384 500GB        | 4         | 0.38%   |
| Hitachi HTS545050A7E380 500GB        | 4         | 0.38%   |
| Hitachi HTS545016B9A300 160GB        | 4         | 0.38%   |
| Hitachi HTS543216L9A300 160GB        | 4         | 0.38%   |
| Hitachi HTS541616J9SA00 160GB        | 4         | 0.38%   |
| HGST HTS545050A7E680 500GB           | 4         | 0.38%   |
| HGST HTS545050A7E380 500GB           | 4         | 0.38%   |
| HGST HTS541010B7E610 1TB             | 4         | 0.38%   |
| Crucial CT500MX500SSD1 500GB         | 4         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 154       | 180    | 26.32%  |
| WDC                 | 152       | 177    | 25.98%  |
| Toshiba             | 115       | 129    | 19.66%  |
| Hitachi             | 82        | 95     | 14.02%  |
| HGST                | 32        | 40     | 5.47%   |
| Fujitsu             | 22        | 22     | 3.76%   |
| Samsung Electronics | 21        | 28     | 3.59%   |
| IBM/Hitachi         | 2         | 3      | 0.34%   |
| ASMT                | 2         | 2      | 0.34%   |
| Unknown             | 1         | 4      | 0.17%   |
| TO Exter            | 1         | 1      | 0.17%   |
| Apple               | 1         | 1      | 0.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 58        | 78     | 20.42%  |
| Kingston            | 38        | 42     | 13.38%  |
| SanDisk             | 28        | 33     | 9.86%   |
| Crucial             | 28        | 35     | 9.86%   |
| WDC                 | 14        | 19     | 4.93%   |
| Intel               | 14        | 15     | 4.93%   |
| SK Hynix            | 9         | 12     | 3.17%   |
| A-DATA Technology   | 8         | 8      | 2.82%   |
| Toshiba             | 7         | 8      | 2.46%   |
| China               | 7         | 7      | 2.46%   |
| Transcend           | 6         | 15     | 2.11%   |
| PNY                 | 5         | 5      | 1.76%   |
| Micron Technology   | 5         | 5      | 1.76%   |
| LITEON              | 5         | 7      | 1.76%   |
| Apple               | 5         | 5      | 1.76%   |
| Team                | 4         | 4      | 1.41%   |
| Patriot             | 4         | 5      | 1.41%   |
| Intenso             | 4         | 4      | 1.41%   |
| OCZ                 | 3         | 3      | 1.06%   |
| LITEONIT            | 3         | 3      | 1.06%   |
| TCSUNBOW            | 2         | 2      | 0.7%    |
| SPCC                | 2         | 2      | 0.7%    |
| PLEXTOR             | 2         | 2      | 0.7%    |
| KingDian            | 2         | 2      | 0.7%    |
| JMicron             | 2         | 2      | 0.7%    |
| GOODRAM             | 2         | 2      | 0.7%    |
| Zheino              | 1         | 1      | 0.35%   |
| Verbatim            | 1         | 1      | 0.35%   |
| USB30               | 1         | 1      | 0.35%   |
| Unknown             | 1         | 1      | 0.35%   |
| TrekStor            | 1         | 1      | 0.35%   |
| Seagate             | 1         | 1      | 0.35%   |
| PNY USB             | 1         | 1      | 0.35%   |
| Pioneer             | 1         | 1      | 0.35%   |
| Pacific Sun         | 1         | 1      | 0.35%   |
| OWC                 | 1         | 1      | 0.35%   |
| MAXTOR              | 1         | 1      | 0.35%   |
| Leven               | 1         | 1      | 0.35%   |
| Kingmax             | 1         | 1      | 0.35%   |
| EMTEC               | 1         | 1      | 0.35%   |
| DOGFISH             | 1         | 1      | 0.35%   |
| BIWIN               | 1         | 1      | 0.35%   |
| BHT                 | 1         | 1      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 572       | 682    | 57.37%  |
| SSD     | 271       | 342    | 27.18%  |
| MMC     | 83        | 113    | 8.32%   |
| NVMe    | 52        | 67     | 5.22%   |
| Unknown | 19        | 21     | 1.91%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 807       | 1010   | 83.89%  |
| MMC  | 83        | 113    | 8.63%   |
| NVMe | 49        | 64     | 5.09%   |
| SAS  | 23        | 38     | 2.39%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 667       | 801    | 79.59%  |
| 0.51-1.0   | 161       | 210    | 19.21%  |
| 1.01-2.0   | 8         | 11     | 0.95%   |
| 4.01-10.0  | 2         | 2      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 328       | 35.57%  |
| 251-500        | 233       | 25.27%  |
| 51-100         | 116       | 12.58%  |
| 501-1000       | 89        | 9.65%   |
| 21-50          | 71        | 7.7%    |
| 1-20           | 41        | 4.45%   |
| 1001-2000      | 31        | 3.36%   |
| More than 3000 | 6         | 0.65%   |
| Unknown        | 4         | 0.43%   |
| 2001-3000      | 3         | 0.33%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 606       | 63.59%  |
| 21-50          | 152       | 15.95%  |
| 51-100         | 73        | 7.66%   |
| 101-250        | 63        | 6.61%   |
| 251-500        | 35        | 3.67%   |
| 501-1000       | 9         | 0.94%   |
| 1001-2000      | 6         | 0.63%   |
| More than 3000 | 4         | 0.42%   |
| Unknown        | 4         | 0.42%   |
| 2001-3000      | 1         | 0.1%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 2         | 2      | 20%     |
| WDC WD3200BPVT-55ZEST0 320GB                        | 1         | 1      | 10%     |
| Toshiba MK5061GSY 500GB                             | 1         | 1      | 10%     |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 10%     |
| Seagate ST9160314AS 160GB                           | 1         | 1      | 10%     |
| Seagate ST9120822AS 120GB                           | 1         | 1      | 10%     |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 10%     |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 10%     |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 60%     |
| WDC               | 1         | 1      | 10%     |
| Toshiba           | 1         | 1      | 10%     |
| Micron Technology | 1         | 1      | 10%     |
| Hitachi           | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 66.67%  |
| WDC     | 1         | 1      | 11.11%  |
| Toshiba | 1         | 1      | 11.11%  |
| Hitachi | 1         | 1      | 11.11%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 9      | 90%     |
| SSD  | 1         | 1      | 10%     |

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
| Detected | 878       | 1197   | 97.23%  |
| Works    | 15        | 18     | 1.66%   |
| Malfunc  | 10        | 10     | 1.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 679       | 75.19%  |
| AMD                              | 122       | 13.51%  |
| Nvidia                           | 23        | 2.55%   |
| Samsung Electronics              | 22        | 2.44%   |
| Silicon Integrated Systems [SiS] | 20        | 2.21%   |
| Sandisk                          | 7         | 0.78%   |
| VIA Technologies                 | 6         | 0.66%   |
| Kingston Technology Company      | 6         | 0.66%   |
| Toshiba America Info Systems     | 5         | 0.55%   |
| JMicron Technology               | 4         | 0.44%   |
| Phison Electronics               | 3         | 0.33%   |
| Union Memory (Shenzhen)          | 1         | 0.11%   |
| SK Hynix                         | 1         | 0.11%   |
| Micron/Crucial Technology        | 1         | 0.11%   |
| Micron Technology                | 1         | 0.11%   |
| Marvell Technology Group         | 1         | 0.11%   |
| KIOXIA                           | 1         | 0.11%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 74        | 6.97%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 68        | 6.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 66        | 6.21%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 64        | 6.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 62        | 5.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 52        | 4.9%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 45        | 4.24%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 42        | 3.95%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 37        | 3.48%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 30        | 2.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 28        | 2.64%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 28        | 2.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 28        | 2.64%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 23        | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 22        | 2.07%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 21        | 1.98%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 20        | 1.88%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 18        | 1.69%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 16        | 1.51%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 14        | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 14        | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 14        | 1.32%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 13        | 1.22%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 13        | 1.22%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 11        | 1.04%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 11        | 1.04%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 9         | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 9         | 0.85%   |
| AMD IXP SB4x0 IDE Controller                                                           | 9         | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 8         | 0.75%   |
| Nvidia MCP67 AHCI Controller                                                           | 7         | 0.66%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 7         | 0.66%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 7         | 0.66%   |
| AMD FCH IDE Controller                                                                 | 7         | 0.66%   |
| Nvidia MCP67 IDE Controller                                                            | 6         | 0.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 6         | 0.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 6         | 0.56%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 6         | 0.56%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 5         | 0.47%   |
| Nvidia MCP79 AHCI Controller                                                           | 5         | 0.47%   |
| Intel SSD 660P Series                                                                  | 5         | 0.47%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 5         | 0.47%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 5         | 0.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 0.38%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                           | 4         | 0.38%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                       | 4         | 0.38%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                  | 4         | 0.38%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                       | 4         | 0.38%   |
| AMD SB600 Non-Raid-5 SATA                                                              | 4         | 0.38%   |
| AMD SB600 IDE                                                                          | 4         | 0.38%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 4         | 0.38%   |
| VIA VT8237A SATA 2-Port Controller                                                     | 3         | 0.28%   |
| Sandisk WD Blue SN550 NVMe SSD                                                         | 3         | 0.28%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 0.28%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                               | 3         | 0.28%   |
| Nvidia MCP51 Serial ATA Controller                                                     | 3         | 0.28%   |
| Nvidia MCP51 IDE                                                                       | 3         | 0.28%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] IDE Controller                             | 3         | 0.28%   |
| Intel Comet Lake SATA AHCI Controller                                                  | 3         | 0.28%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 0.28%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 657       | 66.97%  |
| IDE  | 227       | 23.14%  |
| NVMe | 50        | 5.1%    |
| RAID | 47        | 4.79%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 757       | 84.02%  |
| AMD          | 143       | 15.87%  |
| CentaurHauls | 1         | 0.11%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1.55%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 13        | 1.44%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 12        | 1.33%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 12        | 1.33%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 12        | 1.33%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 11        | 1.22%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 11        | 1.22%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 9         | 1%      |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 9         | 1%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 0.89%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 8         | 0.89%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 8         | 0.89%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 8         | 0.89%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 8         | 0.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.78%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 7         | 0.78%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 7         | 0.78%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 7         | 0.78%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 7         | 0.78%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 7         | 0.78%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 7         | 0.78%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 7         | 0.78%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 7         | 0.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.78%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 6         | 0.67%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 0.67%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.67%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 6         | 0.67%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 6         | 0.67%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 6         | 0.67%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 6         | 0.67%   |
| AMD E-450 APU with Radeon HD Graphics         | 6         | 0.67%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 5         | 0.55%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 5         | 0.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.55%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 5         | 0.55%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 5         | 0.55%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 5         | 0.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.55%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 5         | 0.55%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 5         | 0.55%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 5         | 0.55%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 0.55%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 5         | 0.55%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 5         | 0.55%   |
| Intel Core 2 Duo CPU T6500 @ 2.10GHz          | 5         | 0.55%   |
| Intel Core 2 Duo CPU T6400 @ 2.00GHz          | 5         | 0.55%   |
| Intel Core 2 CPU T5500 @ 1.66GHz              | 5         | 0.55%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 5         | 0.55%   |
| Intel Celeron CPU 900 @ 2.20GHz               | 5         | 0.55%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 5         | 0.55%   |
| AMD E1-2100 APU with Radeon HD Graphics       | 5         | 0.55%   |
| AMD C-50 Processor                            | 5         | 0.55%   |
| Intel Pentium M processor 1.73GHz             | 4         | 0.44%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 4         | 0.44%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 4         | 0.44%   |
| Intel Core i7-3632QM CPU @ 2.20GHz            | 4         | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 4         | 0.44%   |
| Intel Core i5-5300U CPU @ 2.30GHz             | 4         | 0.44%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 151       | 16.76%  |
| Intel Core i7           | 121       | 13.43%  |
| Intel Core 2 Duo        | 101       | 11.21%  |
| Intel Core i3           | 93        | 10.32%  |
| Intel Celeron           | 76        | 8.44%   |
| Intel Atom              | 75        | 8.32%   |
| Intel Pentium           | 29        | 3.22%   |
| Intel Genuine           | 22        | 2.44%   |
| Intel Pentium M         | 17        | 1.89%   |
| Intel Pentium Dual-Core | 17        | 1.89%   |
| Intel Pentium Dual      | 14        | 1.55%   |
| Intel Core 2            | 14        | 1.55%   |
| AMD A6                  | 13        | 1.44%   |
| AMD A4                  | 13        | 1.44%   |
| Intel Celeron M         | 11        | 1.22%   |
| AMD Ryzen 5             | 11        | 1.22%   |
| AMD E                   | 10        | 1.11%   |
| AMD Ryzen 3             | 9         | 1%      |
| AMD E1                  | 9         | 1%      |
| AMD Turion 64 X2 Mobile | 8         | 0.89%   |
| AMD Turion 64 Mobile    | 7         | 0.78%   |
| AMD Ryzen 7             | 6         | 0.67%   |
| AMD A10                 | 6         | 0.67%   |
| Intel Celeron Dual-Core | 5         | 0.55%   |
| AMD C-50                | 5         | 0.55%   |
| AMD A8                  | 5         | 0.55%   |
| Intel Core Duo          | 4         | 0.44%   |
| AMD Mobile Sempron      | 4         | 0.44%   |
| AMD E2                  | 4         | 0.44%   |
| AMD C-60                | 4         | 0.44%   |
| AMD Athlon X2           | 4         | 0.44%   |
| AMD Athlon 64 X2        | 4         | 0.44%   |
| Other                   | 3         | 0.33%   |
| AMD Sempron             | 3         | 0.33%   |
| AMD Turion Dual-Core    | 2         | 0.22%   |
| AMD Ryzen 9             | 2         | 0.22%   |
| AMD Phenom II           | 2         | 0.22%   |
| AMD Athlon II           | 2         | 0.22%   |
| Intel Xeon              | 1         | 0.11%   |
| Intel Pentium 4         | 1         | 0.11%   |
| Intel Core m7           | 1         | 0.11%   |
| Intel Core m3           | 1         | 0.11%   |
| Intel Core M            | 1         | 0.11%   |
| Intel Core 2 Quad       | 1         | 0.11%   |
| Intel Core 2 Extreme    | 1         | 0.11%   |
| CentaurHauls VIA C7     | 1         | 0.11%   |
| AMD V120                | 1         | 0.11%   |
| AMD Turion II Dual-Core | 1         | 0.11%   |
| AMD Turion II           | 1         | 0.11%   |
| AMD Quad-Core           | 1         | 0.11%   |
| AMD Athlon II Dual-Core | 1         | 0.11%   |
| AMD Athlon 64           | 1         | 0.11%   |
| AMD Athlon              | 1         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 619       | 68.7%   |
| 4      | 151       | 16.76%  |
| 1      | 112       | 12.43%  |
| 6      | 13        | 1.44%   |
| 8      | 5         | 0.55%   |
| 3      | 1         | 0.11%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 901       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 452       | 50.17%  |
| 1      | 449       | 49.83%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 834       | 92.46%  |
| 32-bit         | 67        | 7.43%   |
| Unknown        | 1         | 0.11%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 92        | 10.1%   |
| 0x206a7    | 91        | 9.99%   |
| 0x1067a    | 63        | 6.92%   |
| 0x306a9    | 57        | 6.26%   |
| 0x6fd      | 44        | 4.83%   |
| 0x40651    | 40        | 4.39%   |
| 0x20655    | 31        | 3.4%    |
| 0x106ca    | 26        | 2.85%   |
| 0x406e3    | 25        | 2.74%   |
| 0x306c3    | 25        | 2.74%   |
| 0x306d4    | 21        | 2.31%   |
| 0x806e9    | 20        | 2.2%    |
| 0x6d8      | 19        | 2.09%   |
| 0x406c4    | 19        | 2.09%   |
| 0x10676    | 19        | 2.09%   |
| 0x806ea    | 18        | 1.98%   |
| 0x6e8      | 17        | 1.87%   |
| 0x30678    | 17        | 1.87%   |
| 0x106c2    | 17        | 1.87%   |
| 0x406c3    | 15        | 1.65%   |
| 0x06006705 | 13        | 1.43%   |
| 0x05000119 | 13        | 1.43%   |
| 0x6f6      | 12        | 1.32%   |
| 0x906ea    | 11        | 1.21%   |
| 0x20652    | 11        | 1.21%   |
| 0x10661    | 11        | 1.21%   |
| 0x906e9    | 10        | 1.1%    |
| 0x6ec      | 9         | 0.99%   |
| 0x6fb      | 8         | 0.88%   |
| 0x506c9    | 8         | 0.88%   |
| 0x0700010f | 8         | 0.88%   |
| 0x05000029 | 8         | 0.88%   |
| 0x806ec    | 7         | 0.77%   |
| 0x08108109 | 7         | 0.77%   |
| 0x08108102 | 7         | 0.77%   |
| 0x06001119 | 7         | 0.77%   |
| 0x706a1    | 6         | 0.66%   |
| 0x0810100b | 6         | 0.66%   |
| 0x03000027 | 6         | 0.66%   |
| 0x806eb    | 5         | 0.55%   |
| 0x30673    | 5         | 0.55%   |
| 0x010000c8 | 5         | 0.55%   |
| 0x6fa      | 4         | 0.44%   |
| 0x07030105 | 4         | 0.44%   |
| 0x02000057 | 4         | 0.44%   |
| 0x02000032 | 4         | 0.44%   |
| 0x706e5    | 3         | 0.33%   |
| 0x6f2      | 2         | 0.22%   |
| 0x6d6      | 2         | 0.22%   |
| 0x506e3    | 2         | 0.22%   |
| 0x30661    | 2         | 0.22%   |
| 0x08600104 | 2         | 0.22%   |
| 0x08600102 | 2         | 0.22%   |
| 0x07030106 | 2         | 0.22%   |
| 0x07030104 | 2         | 0.22%   |
| 0x07000110 | 2         | 0.22%   |
| 0x06006704 | 2         | 0.22%   |
| 0xf41      | 1         | 0.11%   |
| 0xa0660    | 1         | 0.11%   |
| 0xa0652    | 1         | 0.11%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SandyBridge     | 91        | 10.1%   |
| Penryn          | 90        | 9.99%   |
| Core            | 87        | 9.66%   |
| KabyLake        | 79        | 8.77%   |
| Haswell         | 71        | 7.88%   |
| Silvermont      | 66        | 7.33%   |
| IvyBridge       | 61        | 6.77%   |
| P6              | 47        | 5.22%   |
| Westmere        | 46        | 5.11%   |
| Bonnell         | 46        | 5.11%   |
| Skylake         | 30        | 3.33%   |
| K8 Hammer       | 26        | 2.89%   |
| Bobcat          | 22        | 2.44%   |
| Broadwell       | 21        | 2.33%   |
| Excavator       | 17        | 1.89%   |
| Zen+            | 14        | 1.55%   |
| Jaguar          | 10        | 1.11%   |
| Puma            | 8         | 0.89%   |
| Piledriver      | 8         | 0.89%   |
| K8 & K10 hybrid | 8         | 0.89%   |
| K10             | 8         | 0.89%   |
| Goldmont        | 8         | 0.89%   |
| Zen             | 7         | 0.78%   |
| Goldmont plus   | 7         | 0.78%   |
| Zen 2           | 6         | 0.67%   |
| K10 Llano       | 6         | 0.67%   |
| IceLake         | 3         | 0.33%   |
| Steamroller     | 2         | 0.22%   |
| CometLake       | 2         | 0.22%   |
| Unknown         | 2         | 0.22%   |
| NetBurst        | 1         | 0.11%   |
| Nehalem         | 1         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 633       | 61.04%  |
| AMD                              | 205       | 19.77%  |
| Nvidia                           | 175       | 16.88%  |
| Silicon Integrated Systems [SiS] | 18        | 1.74%   |
| VIA Technologies                 | 6         | 0.58%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 81        | 7.13%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 57        | 5.02%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 50        | 4.4%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 43        | 3.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 42        | 3.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 39        | 3.43%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 37        | 3.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 37        | 3.26%   |
| Intel Core Processor Integrated Graphics Controller                                      | 37        | 3.26%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 28        | 2.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 27        | 2.38%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 27        | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 26        | 2.29%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 25        | 2.2%    |
| Intel HD Graphics 620                                                                    | 25        | 2.2%    |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 18        | 1.58%   |
| Intel HD Graphics 5500                                                                   | 18        | 1.58%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 16        | 1.41%   |
| Intel UHD Graphics 620                                                                   | 16        | 1.41%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 16        | 1.41%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 14        | 1.23%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 1.06%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 12        | 1.06%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 0.88%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.88%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 9         | 0.79%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 8         | 0.7%    |
| Intel HD Graphics 630                                                                    | 8         | 0.7%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 8         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.62%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 7         | 0.62%   |
| Intel HD Graphics 500                                                                    | 7         | 0.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.62%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.62%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 6         | 0.53%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 6         | 0.53%   |
| AMD Renoir                                                                               | 6         | 0.53%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.44%   |
| Nvidia G72M [Quadro NVS 110M/GeForce Go 7300]                                            | 5         | 0.44%   |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 5         | 0.44%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 5         | 0.44%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 5         | 0.44%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 5         | 0.44%   |
| AMD RV370/M22 [Mobility Radeon X300]                                                     | 5         | 0.44%   |
| AMD RS780M [Mobility Radeon HD 3200]                                                     | 5         | 0.44%   |
| AMD Kabini [Radeon HD 8210]                                                              | 5         | 0.44%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 4         | 0.35%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 0.35%   |
| Nvidia GF108M [GeForce GT 525M]                                                          | 4         | 0.35%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 4         | 0.35%   |
| Nvidia G72M [GeForce Go 7400]                                                            | 4         | 0.35%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 4         | 0.35%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 4         | 0.35%   |
| AMD Wrestler [Radeon HD 6290]                                                            | 4         | 0.35%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 4         | 0.35%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 4         | 0.35%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 0.26%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 3         | 0.26%   |
| Nvidia GT218M [NVS 3100M]                                                                | 3         | 0.26%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.26%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 501       | 55.48%  |
| 1 x AMD        | 143       | 15.84%  |
| Intel + Nvidia | 89        | 9.86%   |
| 1 x Nvidia     | 79        | 8.75%   |
| Intel + AMD    | 42        | 4.65%   |
| 1 x SiS        | 18        | 1.99%   |
| 2 x AMD        | 15        | 1.66%   |
| 1 x VIA        | 6         | 0.66%   |
| AMD + Nvidia   | 5         | 0.55%   |
| 2 x Nvidia     | 3         | 0.33%   |
| Other          | 2         | 0.22%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 779       | 86.17%  |
| Proprietary | 69        | 7.63%   |
| Unknown     | 56        | 6.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 603       | 66.41%  |
| 0.01-0.5   | 164       | 18.06%  |
| 1.01-2.0   | 61        | 6.72%   |
| 0.51-1.0   | 53        | 5.84%   |
| 3.01-4.0   | 21        | 2.31%   |
| 7.01-8.0   | 3         | 0.33%   |
| 5.01-6.0   | 2         | 0.22%   |
| 2.01-3.0   | 1         | 0.11%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 175       | 20.33%  |
| LG Display              | 138       | 16.03%  |
| Samsung Electronics     | 133       | 15.45%  |
| Chimei Innolux          | 84        | 9.76%   |
| BOE                     | 72        | 8.36%   |
| Chi Mei Optoelectronics | 48        | 5.57%   |
| LG Philips              | 33        | 3.83%   |
| Apple                   | 17        | 1.97%   |
| InfoVision              | 15        | 1.74%   |
| Lenovo                  | 14        | 1.63%   |
| Toshiba                 | 11        | 1.28%   |
| Goldstar                | 11        | 1.28%   |
| HannStar                | 9         | 1.05%   |
| Dell                    | 9         | 1.05%   |
| CPT                     | 8         | 0.93%   |
| Sharp                   | 7         | 0.81%   |
| Seiko/Epson             | 7         | 0.81%   |
| Quanta Display          | 7         | 0.81%   |
| PANDA                   | 5         | 0.58%   |
| InnoLux Display         | 5         | 0.58%   |
| Sony                    | 4         | 0.46%   |
| LGD                     | 4         | 0.46%   |
| Eizo                    | 4         | 0.46%   |
| AOC                     | 4         | 0.46%   |
| Acer                    | 4         | 0.46%   |
| Unknown                 | 3         | 0.35%   |
| Nvidia                  | 3         | 0.35%   |
| Hewlett-Packard         | 3         | 0.35%   |
| ___                     | 2         | 0.23%   |
| ViewSonic               | 2         | 0.23%   |
| Philips                 | 2         | 0.23%   |
| Panasonic               | 2         | 0.23%   |
| Iiyama                  | 2         | 0.23%   |
| BenQ                    | 2         | 0.23%   |
| Vizio                   | 1         | 0.12%   |
| Vestel Elektronik       | 1         | 0.12%   |
| Vestel                  | 1         | 0.12%   |
| Unknown (AAA)           | 1         | 0.12%   |
| TCL                     | 1         | 0.12%   |
| STD                     | 1         | 0.12%   |
| SKY                     | 1         | 0.12%   |
| MTD                     | 1         | 0.12%   |
| LPL                     | 1         | 0.12%   |
| KLF                     | 1         | 0.12%   |
| Daewoo                  | 1         | 0.12%   |
| cPATH                   | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 13        | 1.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch           | 13        | 1.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 8         | 0.92%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 340x190mm 15.3-inch            | 8         | 0.92%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 7         | 0.81%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 7         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 6         | 0.69%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 6         | 0.69%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 5         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 5         | 0.58%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 5         | 0.58%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 5         | 0.58%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 5         | 0.58%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch                  | 5         | 0.58%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch             | 5         | 0.58%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 5         | 0.58%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.58%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 0.58%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 5         | 0.58%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 4         | 0.46%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 340x190mm 15.3-inch     | 4         | 0.46%   |
| InfoVision LCD Monitor IVO0489 1366x768 260x140mm 11.6-inch              | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 220x130mm 10.1-inch            | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch            | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 340x190mm 15.3-inch            | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 4         | 0.46%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 340x190mm 15.3-inch            | 4         | 0.46%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 367x230mm 17.1-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch     | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch     | 3         | 0.35%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch              | 3         | 0.35%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 3         | 0.35%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 3         | 0.35%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 3         | 0.35%   |
| Lenovo LCD Monitor LEN40B0 1366x768 344x194mm 15.5-inch                  | 3         | 0.35%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch              | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 340x190mm 15.3-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 350x190mm 15.7-inch          | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch          | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 310x170mm 13.9-inch          | 3         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1719 1600x900 382x215mm 17.3-inch | 3         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 350x190mm 15.7-inch | 3         | 0.35%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 3         | 0.35%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 3         | 0.35%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 3         | 0.35%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO733C 1366x768 309x173mm 13.9-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 340x190mm 15.3-inch           | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO492D 1920x1080 293x165mm 13.2-inch           | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO31D2 1024x600 223x125mm 10.1-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO313C 1366x768 310x170mm 13.9-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 310x170mm 13.9-inch            | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch           | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch           | 3         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 383       | 44.95%  |
| 1920x1080 (FHD)    | 174       | 20.42%  |
| 1280x800 (WXGA)    | 97        | 11.38%  |
| 1600x900 (HD+)     | 61        | 7.16%   |
| 1024x600           | 33        | 3.87%   |
| 1440x900 (WXGA+)   | 29        | 3.4%    |
| 3840x2160 (4K)     | 14        | 1.64%   |
| 1920x1200 (WUXGA)  | 12        | 1.41%   |
| 1680x1050 (WSXGA+) | 8         | 0.94%   |
| 1280x768           | 6         | 0.7%    |
| 1024x768 (XGA)     | 6         | 0.7%    |
| 2560x1600          | 4         | 0.47%   |
| 1280x1024 (SXGA)   | 4         | 0.47%   |
| 1360x768           | 3         | 0.35%   |
| 2560x1440 (QHD)    | 2         | 0.23%   |
| 1680x945           | 2         | 0.23%   |
| 1400x1050          | 2         | 0.23%   |
| 1024x576           | 2         | 0.23%   |
| 5760x2160          | 1         | 0.12%   |
| 3840x1080          | 1         | 0.12%   |
| 3200x1800 (QHD+)   | 1         | 0.12%   |
| 2880x1800          | 1         | 0.12%   |
| 2560x1080          | 1         | 0.12%   |
| 2288x1287          | 1         | 0.12%   |
| 2160x1440          | 1         | 0.12%   |
| 2048x1152          | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |
| Unknown            | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 387       | 44.79%  |
| 13      | 102       | 11.81%  |
| 14      | 98        | 11.34%  |
| 17      | 73        | 8.45%   |
| 10      | 36        | 4.17%   |
| 11      | 35        | 4.05%   |
| Unknown | 28        | 3.24%   |
| 12      | 22        | 2.55%   |
| 24      | 12        | 1.39%   |
| 27      | 11        | 1.27%   |
| 21      | 10        | 1.16%   |
| 23      | 7         | 0.81%   |
| 72      | 5         | 0.58%   |
| 18      | 5         | 0.58%   |
| 22      | 4         | 0.46%   |
| 20      | 4         | 0.46%   |
| 40      | 3         | 0.35%   |
| 31      | 3         | 0.35%   |
| 8       | 3         | 0.35%   |
| 84      | 2         | 0.23%   |
| 74      | 1         | 0.12%   |
| 59      | 1         | 0.12%   |
| 58      | 1         | 0.12%   |
| 54      | 1         | 0.12%   |
| 49      | 1         | 0.12%   |
| 46      | 1         | 0.12%   |
| 44      | 1         | 0.12%   |
| 41      | 1         | 0.12%   |
| 34      | 1         | 0.12%   |
| 33      | 1         | 0.12%   |
| 32      | 1         | 0.12%   |
| 29      | 1         | 0.12%   |
| 19      | 1         | 0.12%   |
| 16      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 533       | 61.9%   |
| 201-300     | 129       | 14.98%  |
| 351-400     | 89        | 10.34%  |
| 501-600     | 29        | 3.37%   |
| Unknown     | 28        | 3.25%   |
| 401-500     | 24        | 2.79%   |
| 1501-2000   | 8         | 0.93%   |
| 601-700     | 5         | 0.58%   |
| 1001-1500   | 5         | 0.58%   |
| 801-900     | 3         | 0.35%   |
| 701-800     | 3         | 0.35%   |
| 101-200     | 3         | 0.35%   |
| 901-1000    | 2         | 0.23%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 629       | 77.65%  |
| 16/10   | 141       | 17.41%  |
| Unknown | 24        | 2.96%   |
| 4/3     | 9         | 1.11%   |
| 5/4     | 4         | 0.49%   |
| 32/9    | 1         | 0.12%   |
| 3/2     | 1         | 0.12%   |
| 21/9    | 1         | 0.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 387       | 45%     |
| 81-90          | 169       | 19.65%  |
| 121-130        | 40        | 4.65%   |
| 41-50          | 36        | 4.19%   |
| 51-60          | 35        | 4.07%   |
| 131-140        | 29        | 3.37%   |
| Unknown        | 28        | 3.26%   |
| 71-80          | 27        | 3.14%   |
| 61-70          | 21        | 2.44%   |
| 201-250        | 21        | 2.44%   |
| More than 1000 | 11        | 1.28%   |
| 301-350        | 11        | 1.28%   |
| 151-200        | 11        | 1.28%   |
| 141-150        | 9         | 1.05%   |
| 351-500        | 7         | 0.81%   |
| 501-1000       | 7         | 0.81%   |
| 251-300        | 4         | 0.47%   |
| 91-100         | 4         | 0.47%   |
| 1-40           | 3         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 408       | 48.23%  |
| 121-160       | 194       | 22.93%  |
| 51-100        | 180       | 21.28%  |
| Unknown       | 28        | 3.31%   |
| 161-240       | 23        | 2.72%   |
| 1-50          | 9         | 1.06%   |
| More than 240 | 4         | 0.47%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 771       | 84.17%  |
| 2     | 81        | 8.84%   |
| 0     | 60        | 6.55%   |
| 3     | 4         | 0.44%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 459       | 30.08%  |
| Intel                                  | 339       | 22.21%  |
| Qualcomm Atheros                       | 284       | 18.61%  |
| Broadcom                               | 174       | 11.4%   |
| Broadcom Limited                       | 52        | 3.41%   |
| Marvell Technology Group               | 36        | 2.36%   |
| Silicon Integrated Systems [SiS]       | 20        | 1.31%   |
| Nvidia                                 | 20        | 1.31%   |
| Ralink                                 | 18        | 1.18%   |
| JMicron Technology                     | 11        | 0.72%   |
| TP-Link                                | 9         | 0.59%   |
| Ralink Technology                      | 9         | 0.59%   |
| Xiaomi                                 | 7         | 0.46%   |
| Sierra Wireless                        | 6         | 0.39%   |
| ASUSTek Computer                       | 6         | 0.39%   |
| ASIX Electronics                       | 6         | 0.39%   |
| AMD                                    | 6         | 0.39%   |
| VIA Technologies                       | 5         | 0.33%   |
| Samsung Electronics                    | 5         | 0.33%   |
| Qualcomm Atheros Communications        | 5         | 0.33%   |
| Dell                                   | 5         | 0.33%   |
| Motorola PCS                           | 4         | 0.26%   |
| Huawei Technologies                    | 4         | 0.26%   |
| Hewlett-Packard                        | 4         | 0.26%   |
| Edimax Technology                      | 4         | 0.26%   |
| NetGear                                | 3         | 0.2%    |
| MediaTek                               | 3         | 0.2%    |
| D-Link                                 | 3         | 0.2%    |
| Attansic Technology                    | 3         | 0.2%    |
| OPPO Electronics                       | 2         | 0.13%   |
| Micro Star International               | 2         | 0.13%   |
| Davicom Semiconductor                  | 2         | 0.13%   |
| ZyDAS                                  | 1         | 0.07%   |
| T & A Mobile Phones                    | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| Sitecom Europe                         | 1         | 0.07%   |
| Lite-On Technology                     | 1         | 0.07%   |
| Linksys                                | 1         | 0.07%   |
| Ericsson Business Mobile Networks      | 1         | 0.07%   |
| DisplayLink                            | 1         | 0.07%   |
| D-Link System                          | 1         | 0.07%   |
| Belkin Components                      | 1         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 213       | 11.66%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 153       | 8.37%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 62        | 3.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 41        | 2.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 41        | 2.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 38        | 2.08%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 35        | 1.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 34        | 1.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 32        | 1.75%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 32        | 1.75%   |
| Intel Wireless 7260                                                     | 32        | 1.75%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 28        | 1.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.48%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 22        | 1.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 21        | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 20        | 1.09%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 19        | 1.04%   |
| Intel WiFi Link 5100                                                    | 18        | 0.99%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 17        | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 16        | 0.88%   |
| Intel Wireless 3165                                                     | 16        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 16        | 0.88%   |
| Intel Wireless 8265 / 8275                                              | 15        | 0.82%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 15        | 0.82%   |
| Intel Wireless 7265                                                     | 14        | 0.77%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 14        | 0.77%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 14        | 0.77%   |
| Intel Ethernet Connection I218-LM                                       | 13        | 0.71%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 13        | 0.71%   |
| Intel Wireless 3160                                                     | 12        | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 11        | 0.6%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 11        | 0.6%    |
| Intel Ethernet Connection I217-LM                                       | 11        | 0.6%    |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.6%    |
| Broadcom BCM4401-B0 100Base-TX                                          | 11        | 0.6%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 10        | 0.55%   |
| Intel Centrino Wireless-N 2230                                          | 10        | 0.55%   |
| Intel 82567LM Gigabit Network Connection                                | 10        | 0.55%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 10        | 0.55%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 9         | 0.49%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 9         | 0.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.49%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 9         | 0.49%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 9         | 0.49%   |
| Intel 82577LM Gigabit Network Connection                                | 9         | 0.49%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                     | 9         | 0.49%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 9         | 0.49%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 8         | 0.44%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 8         | 0.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 8         | 0.44%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 8         | 0.44%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 0.44%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                         | 8         | 0.44%   |
| Ralink MT7601U Wireless Adapter                                         | 7         | 0.38%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.38%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 7         | 0.38%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 7         | 0.38%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                   | 7         | 0.38%   |
| Nvidia MCP67 Ethernet                                                   | 7         | 0.38%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 304       | 31.8%   |
| Qualcomm Atheros                | 242       | 25.31%  |
| Realtek Semiconductor           | 165       | 17.26%  |
| Broadcom                        | 128       | 13.39%  |
| Broadcom Limited                | 40        | 4.18%   |
| Ralink                          | 18        | 1.88%   |
| Ralink Technology               | 9         | 0.94%   |
| TP-Link                         | 8         | 0.84%   |
| Sierra Wireless                 | 6         | 0.63%   |
| ASUSTek Computer                | 6         | 0.63%   |
| Qualcomm Atheros Communications | 5         | 0.52%   |
| Edimax Technology               | 4         | 0.42%   |
| NetGear                         | 3         | 0.31%   |
| D-Link                          | 3         | 0.31%   |
| Micro Star International        | 2         | 0.21%   |
| MEDIATEK                        | 2         | 0.21%   |
| Hewlett-Packard                 | 2         | 0.21%   |
| Dell                            | 2         | 0.21%   |
| ZyDAS                           | 1         | 0.1%    |
| Xiaomi                          | 1         | 0.1%    |
| Sitecom Europe                  | 1         | 0.1%    |
| Lite-On Technology              | 1         | 0.1%    |
| Linksys                         | 1         | 0.1%    |
| D-Link System                   | 1         | 0.1%    |
| Belkin Components               | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                | 62        | 6.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 41        | 4.26%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                         | 41        | 4.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 38        | 3.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                           | 35        | 3.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 32        | 3.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)       | 32        | 3.32%   |
| Intel Wireless 7260                                                           | 32        | 3.32%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                             | 28        | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 27        | 2.8%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                               | 22        | 2.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                    | 21        | 2.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 20        | 2.08%   |
| Intel WiFi Link 5100                                                          | 18        | 1.87%   |
| Intel Wireless 3165                                                           | 16        | 1.66%   |
| Broadcom BCM43142 802.11b/g/n                                                 | 16        | 1.66%   |
| Intel Wireless 8265 / 8275                                                    | 15        | 1.56%   |
| Intel Wireless 7265                                                           | 14        | 1.45%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection                 | 14        | 1.45%   |
| Broadcom BCM4311 802.11b/g WLAN                                               | 14        | 1.45%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                                  | 13        | 1.35%   |
| Intel Wireless 3160                                                           | 12        | 1.25%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 11        | 1.14%   |
| Intel Centrino Ultimate-N 6300                                                | 11        | 1.14%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 10        | 1.04%   |
| Realtek RTL8723DE Wireless Network Adapter                                    | 10        | 1.04%   |
| Intel Centrino Wireless-N 2230                                                | 10        | 1.04%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                                     | 10        | 1.04%   |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 9         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 9         | 0.93%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                      | 9         | 0.93%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller           | 9         | 0.93%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                      | 8         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                | 8         | 0.83%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                       | 8         | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                               | 8         | 0.83%   |
| Ralink MT7601U Wireless Adapter                                               | 7         | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 7         | 0.73%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                              | 7         | 0.73%   |
| Intel Wireless 8260                                                           | 7         | 0.73%   |
| Intel Wi-Fi 6 AX200                                                           | 7         | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                            | 6         | 0.62%   |
| Realtek RTL8188EE Wireless Network Adapter                                    | 6         | 0.62%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)                | 6         | 0.62%   |
| Intel Centrino Advanced-N 6235                                                | 6         | 0.62%   |
| Broadcom BCM43224 802.11a/b/g/n                                               | 6         | 0.62%   |
| Realtek 802.11ac NIC                                                          | 5         | 0.52%   |
| Qualcomm Atheros AR9271 802.11n                                               | 5         | 0.52%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                     | 5         | 0.52%   |
| Intel Centrino Advanced-N 6200                                                | 5         | 0.52%   |
| Broadcom Limited BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller   | 5         | 0.52%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                        | 5         | 0.52%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 4         | 0.42%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                                     | 4         | 0.42%   |
| Qualcomm Atheros AR2413/AR2414 Wireless Network Adapter [AR5005G(S) 802.11bg] | 4         | 0.42%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                              | 4         | 0.42%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 4         | 0.42%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter                    | 4         | 0.42%   |
| Broadcom BCM43225 802.11b/g/n                                                 | 4         | 0.42%   |
| TP-Link TL WN823N RTL8192EU                                                   | 3         | 0.31%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 398       | 48.13%  |
| Intel                                  | 143       | 17.29%  |
| Qualcomm Atheros                       | 78        | 9.43%   |
| Broadcom                               | 67        | 8.1%    |
| Marvell Technology Group               | 36        | 4.35%   |
| Nvidia                                 | 20        | 2.42%   |
| Silicon Integrated Systems [SiS]       | 19        | 2.3%    |
| Broadcom Limited                       | 15        | 1.81%   |
| JMicron Technology                     | 11        | 1.33%   |
| Xiaomi                                 | 6         | 0.73%   |
| ASIX Electronics                       | 6         | 0.73%   |
| VIA Technologies                       | 5         | 0.6%    |
| Samsung Electronics                    | 4         | 0.48%   |
| Motorola PCS                           | 4         | 0.48%   |
| Huawei Technologies                    | 3         | 0.36%   |
| Attansic Technology                    | 3         | 0.36%   |
| OPPO Electronics                       | 2         | 0.24%   |
| Davicom Semiconductor                  | 2         | 0.24%   |
| TP-Link                                | 1         | 0.12%   |
| T & A Mobile Phones                    | 1         | 0.12%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.12%   |
| MediaTek                               | 1         | 0.12%   |
| DisplayLink                            | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 213       | 25.69%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 153       | 18.46%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 34        | 4.1%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 19        | 2.29%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter                  | 17        | 2.05%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 16        | 1.93%   |
| Intel Ethernet Connection I218-LM                                              | 13        | 1.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 11        | 1.33%   |
| Intel Ethernet Connection I217-LM                                              | 11        | 1.33%   |
| Broadcom BCM4401-B0 100Base-TX                                                 | 11        | 1.33%   |
| Intel 82567LM Gigabit Network Connection                                       | 10        | 1.21%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 9         | 1.09%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                           | 9         | 1.09%   |
| Intel 82577LM Gigabit Network Connection                                       | 9         | 1.09%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 9         | 1.09%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 8         | 0.97%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 8         | 0.97%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 7         | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 7         | 0.84%   |
| Nvidia MCP67 Ethernet                                                          | 7         | 0.84%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 7         | 0.84%   |
| Intel Ethernet Connection I219-LM                                              | 7         | 0.84%   |
| Intel 82579V Gigabit Network Connection                                        | 7         | 0.84%   |
| Intel 82566MM Gigabit Network Connection                                       | 7         | 0.84%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                         | 7         | 0.84%   |
| Nvidia MCP79 Ethernet                                                          | 6         | 0.72%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 6         | 0.72%   |
| Intel PRO/100 VE Network Connection                                            | 6         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                                          | 6         | 0.72%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 5         | 0.6%    |
| VIA VT6102/VT6103 [Rhine-II]                                                   | 5         | 0.6%    |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 5         | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 5         | 0.6%    |
| JMicron JMC260 PCI Express Fast Ethernet Controller                            | 5         | 0.6%    |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile           | 5         | 0.6%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 5         | 0.6%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 5         | 0.6%    |
| Broadcom Limited BCM4401-B0 100Base-TX                                         | 5         | 0.6%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 4         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 4         | 0.48%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 4         | 0.48%   |
| Nvidia MCP77 Ethernet                                                          | 4         | 0.48%   |
| Motorola PCS moto g(6) plus                                                    | 4         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                                           | 4         | 0.48%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 4         | 0.48%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express                       | 4         | 0.48%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                                | 4         | 0.48%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 3         | 0.36%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 3         | 0.36%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.36%   |
| Nvidia MCP51 Ethernet Controller                                               | 3         | 0.36%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 3         | 0.36%   |
| Marvell Group 88E8042 PCI-E Fast Ethernet Controller                           | 3         | 0.36%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 3         | 0.36%   |
| Intel WiMAX Connection 2400m                                                   | 3         | 0.36%   |
| Huawei DRA-L01                                                                 | 3         | 0.36%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                       | 3         | 0.36%   |
| Attansic AR8152 v2.0 Fast Ethernet                                             | 3         | 0.36%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 3         | 0.36%   |
| Silicon Integrated Systems [SiS] SiS900 PCI Fast Ethernet                      | 2         | 0.24%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 875       | 51.08%  |
| Ethernet | 803       | 46.88%  |
| Modem    | 35        | 2.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 723       | 74.31%  |
| Ethernet | 248       | 25.49%  |
| Modem    | 2         | 0.21%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 751       | 83.35%  |
| 1     | 118       | 13.1%   |
| 0     | 29        | 3.22%   |
| 3     | 3         | 0.33%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 851       | 93.83%  |
| Yes  | 56        | 6.17%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 139       | 26.73%  |
| Qualcomm Atheros Communications | 73        | 14.04%  |
| Realtek Semiconductor           | 59        | 11.35%  |
| Broadcom                        | 57        | 10.96%  |
| Dell                            | 28        | 5.38%   |
| Hewlett-Packard                 | 26        | 5%      |
| Lite-On Technology              | 24        | 4.62%   |
| Foxconn / Hon Hai               | 19        | 3.65%   |
| IMC Networks                    | 14        | 2.69%   |
| Apple                           | 14        | 2.69%   |
| Toshiba                         | 11        | 2.12%   |
| Cambridge Silicon Radio         | 9         | 1.73%   |
| Alps Electric                   | 8         | 1.54%   |
| Realtek                         | 7         | 1.35%   |
| Ralink                          | 7         | 1.35%   |
| ASUSTek Computer                | 7         | 1.35%   |
| Foxconn International           | 5         | 0.96%   |
| Taiyo Yuden                     | 3         | 0.58%   |
| Ralink Technology               | 3         | 0.58%   |
| Dynex                           | 2         | 0.38%   |
| Askey Computer                  | 2         | 0.38%   |
| Qcom                            | 1         | 0.19%   |
| MediaTek                        | 1         | 0.19%   |
| Chicony Electronics             | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 91        | 17.47%  |
| Realtek Bluetooth Radio                                                             | 35        | 6.72%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 32        | 6.14%   |
| Intel Bluetooth Device                                                              | 17        | 3.26%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 14        | 2.69%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 13        | 2.5%    |
| Realtek  Bluetooth 4.2 Adapter                                                      | 12        | 2.3%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 12        | 2.3%    |
| Realtek 802.11n WLAN Adapter                                                        | 10        | 1.92%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 10        | 1.92%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 1.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 1.73%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 9         | 1.73%   |
| Broadcom BCM2045 Bluetooth                                                          | 9         | 1.73%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 8         | 1.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 8         | 1.54%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 1.54%   |
| Realtek Bluetooth Radio                                                             | 7         | 1.34%   |
| Ralink RT3290 Bluetooth                                                             | 7         | 1.34%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 1.34%   |
| Intel AX200 Bluetooth                                                               | 7         | 1.34%   |
| Apple Bluetooth Host Controller                                                     | 7         | 1.34%   |
| Dell Wireless 365 Bluetooth                                                         | 6         | 1.15%   |
| Dell DW375 Bluetooth Module                                                         | 6         | 1.15%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 0.96%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.96%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 5         | 0.96%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.96%   |
| Broadcom BCM20702A0                                                                 | 5         | 0.96%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 5         | 0.96%   |
| Toshiba Bluetooth Device                                                            | 4         | 0.77%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 4         | 0.77%   |
| Lite-On Bluetooth Device                                                            | 4         | 0.77%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 0.77%   |
| Dell Wireless 350 Bluetooth                                                         | 4         | 0.77%   |
| Dell BCM20702A0                                                                     | 4         | 0.77%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 4         | 0.77%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 4         | 0.77%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 3         | 0.58%   |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]                                       | 3         | 0.58%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 3         | 0.58%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 3         | 0.58%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 3         | 0.58%   |
| Dell Wireless 360 Bluetooth                                                         | 3         | 0.58%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 3         | 0.58%   |
| Broadcom BCM2046 Bluetooth Device                                                   | 3         | 0.58%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]                                    | 3         | 0.58%   |
| ASUS BT-253 Bluetooth Adapter                                                       | 3         | 0.58%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 3         | 0.58%   |
| Apple Bluetooth USB Host Controller                                                 | 3         | 0.58%   |
| Alps Electric UGTZ4 Bluetooth                                                       | 3         | 0.58%   |
| Toshiba Integrated Bluetooth HCI                                                    | 2         | 0.38%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 2         | 0.38%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.38%   |
| Ralink CSR BS8510                                                                   | 2         | 0.38%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.38%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 0.38%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 2         | 0.38%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 0.38%   |
| Foxconn / Hon Hai BCM43142A0                                                        | 2         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 697       | 71.12%  |
| AMD                              | 151       | 15.41%  |
| Nvidia                           | 85        | 8.67%   |
| Silicon Integrated Systems [SiS] | 20        | 2.04%   |
| VIA Technologies                 | 6         | 0.61%   |
| C-Media Electronics              | 5         | 0.51%   |
| Tenx Technology                  | 3         | 0.31%   |
| Creative Technology              | 3         | 0.31%   |
| Yamaha                           | 2         | 0.2%    |
| Generalplus Technology           | 2         | 0.2%    |
| ZOOM                             | 1         | 0.1%    |
| Texas Instruments                | 1         | 0.1%    |
| OPPO Electronics                 | 1         | 0.1%    |
| Logitech                         | 1         | 0.1%    |
| Hewlett-Packard                  | 1         | 0.1%    |
| AKAI Professional M.I.           | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 83        | 7.05%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 76        | 6.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 75        | 6.37%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 75        | 6.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 72        | 6.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 57        | 4.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 47        | 3.99%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 43        | 3.65%   |
| Intel 8 Series HD Audio Controller                                                                | 43        | 3.65%   |
| AMD FCH Azalia Controller                                                                         | 38        | 3.23%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 36        | 3.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 28        | 2.38%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 28        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 27        | 2.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 21        | 1.78%   |
| Intel Broadwell-U Audio Controller                                                                | 21        | 1.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 19        | 1.61%   |
| AMD Wrestler HDMI Audio                                                                           | 19        | 1.61%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 1.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 19        | 1.61%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 18        | 1.53%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 17        | 1.44%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 17        | 1.44%   |
| AMD High Definition Audio Controller                                                              | 16        | 1.36%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 15        | 1.27%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 1.1%    |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 1.1%    |
| Intel CM238 HD Audio Controller                                                                   | 10        | 0.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 0.85%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 8         | 0.68%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.68%   |
| Nvidia MCP67 High Definition Audio                                                                | 7         | 0.59%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 0.59%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 0.59%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 7         | 0.59%   |
| Nvidia MCP79 High Definition Audio                                                                | 6         | 0.51%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 6         | 0.51%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 6         | 0.51%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 5         | 0.42%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 5         | 0.42%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 0.42%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 5         | 0.42%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 4         | 0.34%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 4         | 0.34%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.34%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 4         | 0.34%   |
| AMD RV635 HDMI Audio [Radeon HD 3650/3730/3750]                                                   | 4         | 0.34%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 3         | 0.25%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.25%   |
| Nvidia MCP89 High Definition Audio                                                                | 3         | 0.25%   |
| Nvidia MCP51 High Definition Audio                                                                | 3         | 0.25%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 3         | 0.25%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.25%   |
| Intel US15W/US15X/US15L/UL11L SCH [Poulsbo] HD Audio Controller                                   | 3         | 0.25%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.25%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 3         | 0.25%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.25%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 3         | 0.25%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.25%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK Hynix            | 53        | 28.19%  |
| Samsung Electronics | 38        | 20.21%  |
| Unknown             | 26        | 13.83%  |
| Micron Technology   | 16        | 8.51%   |
| Kingston            | 16        | 8.51%   |
| Nanya Technology    | 8         | 4.26%   |
| Ramaxel Technology  | 5         | 2.66%   |
| Elpida              | 5         | 2.66%   |
| Smart               | 3         | 1.6%    |
| Unknown (ABCD)      | 2         | 1.06%   |
| High Bridge         | 2         | 1.06%   |
| A-DATA Technology   | 2         | 1.06%   |
| Walton Chaintech    | 1         | 0.53%   |
| Transcend           | 1         | 0.53%   |
| Toshiba             | 1         | 0.53%   |
| Team                | 1         | 0.53%   |
| SMART Brazil        | 1         | 0.53%   |
| SHARETRONIC         | 1         | 0.53%   |
| Qimonda             | 1         | 0.53%   |
| Nayna               | 1         | 0.53%   |
| HBS                 | 1         | 0.53%   |
| COS Memory          | 1         | 0.53%   |
| Corsair             | 1         | 0.53%   |
| Avant               | 1         | 0.53%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s       | 6         | 2.9%    |
| SK Hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s        | 4         | 1.93%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s         | 4         | 1.93%   |
| SK Hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s          | 3         | 1.45%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s       | 3         | 1.45%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s          | 3         | 1.45%   |
| Unknown RAM Module 512MB SODIMM DDR                            | 2         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                     | 2         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                     | 2         | 0.97%   |
| Unknown RAM Module 2GB SODIMM DDR                              | 2         | 0.97%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                         | 2         | 0.97%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM DDR4 2400MT/s | 2         | 0.97%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1066MT/s                  | 2         | 0.97%   |
| SK Hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR 975MT/s           | 2         | 0.97%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s         | 2         | 0.97%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s   | 2         | 0.97%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s         | 2         | 0.97%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s      | 2         | 0.97%   |
| SK Hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s         | 2         | 0.97%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s          | 2         | 0.97%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 0.97%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s          | 2         | 0.97%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s        | 2         | 0.97%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s          | 2         | 0.97%   |
| Micron RAM 8JSF25664HZ-1G4D1 2048MB SODIMM DDR3 1334MT/s       | 2         | 0.97%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s        | 2         | 0.97%   |
| Walton Chaintech RAM AS2G833-13GH905 2048MB SODIMM DDR2        | 1         | 0.48%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                    | 1         | 0.48%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                 | 1         | 0.48%   |
| Unknown RAM Module 512MB SODIMM DRAM                           | 1         | 0.48%   |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                   | 1         | 0.48%   |
| Unknown RAM Module 4GB SODIMM DDR2 667MT/s                     | 1         | 0.48%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                 | 1         | 0.48%   |
| Unknown RAM Module 4096MB SODIMM DDR3                          | 1         | 0.48%   |
| Unknown RAM Module 256MB SODIMM DRAM 400MT/s                   | 1         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                  | 1         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2 800MT/s                  | 1         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                  | 1         | 0.48%   |
| Unknown RAM Module 2048MB SODIMM DDR2                          | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                     | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR2                             | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR                              | 1         | 0.48%   |
| Unknown RAM Module 1GB SODIMM 400MT/s                          | 1         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM SDRAM                         | 1         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                  | 1         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DRAM 400MT/s                  | 1         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                  | 1         | 0.48%   |
| Unknown RAM Module 1024MB SODIMM DDR2 533MT/s                  | 1         | 0.48%   |
| Unknown RAM ICF 2GB SODIMM DDR2                                | 1         | 0.48%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s            | 1         | 0.48%   |
| Toshiba RAM 8HTF12864HDY-800G1 2GB SODIMM 1066MT/s             | 1         | 0.48%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s              | 1         | 0.48%   |
| Team RAM Elite-1600 8GB SODIMM DDR3 1600MT/s                   | 1         | 0.48%   |
| Team RAM Elite-1333 8GB SODIMM DDR3 1334MT/s                   | 1         | 0.48%   |
| Smart RAM SH564568FJ8NZRNSDR 2GB SODIMM DDR3 1600MT/s          | 1         | 0.48%   |
| Smart RAM SH564128FJ8NZRNSDG 4096MB SODIMM DDR3 1600MT/s       | 1         | 0.48%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s          | 1         | 0.48%   |
| Smart RAM SH564128FH8NZPHSCR 4GB DIMM DDR3 1333MT/s            | 1         | 0.48%   |
| SMART Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s   | 1         | 0.48%   |
| SK Hynix RAM Module 8GB SODIMM DDR4 2133MT/s                   | 1         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 74        | 45.12%  |
| DDR2    | 35        | 21.34%  |
| DDR4    | 28        | 17.07%  |
| SDRAM   | 13        | 7.93%   |
| DDR     | 4         | 2.44%   |
| LPDDR4  | 3         | 1.83%   |
| DRAM    | 3         | 1.83%   |
| LPDDR3  | 2         | 1.22%   |
| Unknown | 2         | 1.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 147       | 94.23%  |
| Row Of Chips | 5         | 3.21%   |
| DIMM         | 3         | 1.92%   |
| Chip         | 1         | 0.64%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 60        | 32.09%  |
| 2048  | 59        | 31.55%  |
| 8192  | 31        | 16.58%  |
| 1024  | 24        | 12.83%  |
| 512   | 7         | 3.74%   |
| 16384 | 4         | 2.14%   |
| 256   | 2         | 1.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 46        | 25.99%  |
| 2667    | 20        | 11.3%   |
| 667     | 17        | 9.6%    |
| 1334    | 15        | 8.47%   |
| 1333    | 11        | 6.21%   |
| Unknown | 11        | 6.21%   |
| 2133    | 8         | 4.52%   |
| 4199    | 7         | 3.95%   |
| 1066    | 7         | 3.95%   |
| 2400    | 6         | 3.39%   |
| 800     | 6         | 3.39%   |
| 533     | 6         | 3.39%   |
| 975     | 5         | 2.82%   |
| 2048    | 3         | 1.69%   |
| 400     | 3         | 1.69%   |
| 1067    | 2         | 1.13%   |
| 3733    | 1         | 0.56%   |
| 3266    | 1         | 0.56%   |
| 3200    | 1         | 0.56%   |
| 1639    | 1         | 0.56%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 5         | 41.67%  |
| Canon              | 3         | 25%     |
| Brother Industries | 2         | 16.67%  |
| STMicroelectronics | 1         | 8.33%   |
| Seiko Epson        | 1         | 8.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 8.33%   |
| Seiko Epson PX-105 Series                                 | 1         | 8.33%   |
| HP Laserjet P1505                                         | 1         | 8.33%   |
| HP LaserJet 1020                                          | 1         | 8.33%   |
| HP DeskJet 2700 series                                    | 1         | 8.33%   |
| HP Deskjet 1510                                           | 1         | 8.33%   |
| HP DeskJet 1110 series                                    | 1         | 8.33%   |
| Canon PIXMA MX340                                         | 1         | 8.33%   |
| Canon PIXMA MG3600 Series                                 | 1         | 8.33%   |
| Canon MG2100 series                                       | 1         | 8.33%   |
| Brother MFC-L2730DW series                                | 1         | 8.33%   |
| Brother DCP-T300                                          | 1         | 8.33%   |

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
| Chicony Electronics                    | 189       | 27.92%  |
| Microdia                               | 68        | 10.04%  |
| Realtek Semiconductor                  | 50        | 7.39%   |
| Suyin                                  | 48        | 7.09%   |
| Acer                                   | 46        | 6.79%   |
| IMC Networks                           | 43        | 6.35%   |
| Sunplus Innovation Technology          | 36        | 5.32%   |
| Cheng Uei Precision Industry (Foxlink) | 25        | 3.69%   |
| Silicon Motion                         | 23        | 3.4%    |
| Quanta                                 | 17        | 2.51%   |
| Apple                                  | 15        | 2.22%   |
| Alcor Micro                            | 15        | 2.22%   |
| Lite-On Technology                     | 14        | 2.07%   |
| Syntek                                 | 13        | 1.92%   |
| Ricoh                                  | 12        | 1.77%   |
| Importek                               | 11        | 1.62%   |
| ALi                                    | 9         | 1.33%   |
| Z-Star Microelectronics                | 7         | 1.03%   |
| OmniVision Technologies                | 5         | 0.74%   |
| Samsung Electronics                    | 4         | 0.59%   |
| Logitech                               | 4         | 0.59%   |
| GEMBIRD                                | 3         | 0.44%   |
| Primax Electronics                     | 2         | 0.3%    |
| Luxvisions Innotech Limited            | 2         | 0.3%    |
| Lenovo                                 | 2         | 0.3%    |
| Genesys Logic                          | 2         | 0.3%    |
| Trust                                  | 1         | 0.15%   |
| Sunplus Technology                     | 1         | 0.15%   |
| Microsoft                              | 1         | 0.15%   |
| LG Electronics                         | 1         | 0.15%   |
| Intel                                  | 1         | 0.15%   |
| HD WEBCAM                              | 1         | 0.15%   |
| Generalplus Technology                 | 1         | 0.15%   |
| Foxconn / Hon Hai                      | 1         | 0.15%   |
| eMPIA Technology                       | 1         | 0.15%   |
| Elecom                                 | 1         | 0.15%   |
| Creative Technology                    | 1         | 0.15%   |
| Camera                                 | 1         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 16        | 2.36%   |
| Acer Lenovo EasyCamera                                         | 13        | 1.92%   |
| Realtek Integrated_Webcam_HD                                   | 11        | 1.62%   |
| Chicony USB 2.0 Camera                                         | 11        | 1.62%   |
| Microdia Integrated Webcam                                     | 10        | 1.47%   |
| Chicony EasyCamera                                             | 10        | 1.47%   |
| Microdia Sonix USB 2.0 Camera                                  | 9         | 1.33%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 9         | 1.33%   |
| Chicony HP Truevision HD camera                                | 9         | 1.33%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                       | 8         | 1.18%   |
| Sunplus Integrated_Webcam_HD                                   | 8         | 1.18%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 8         | 1.18%   |
| Chicony Lenovo EasyCamera                                      | 8         | 1.18%   |
| Chicony HP HD Webcam                                           | 8         | 1.18%   |
| Suyin HP Truevision HD                                         | 7         | 1.03%   |
| Realtek Integrated Webcam                                      | 7         | 1.03%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 7         | 1.03%   |
| Chicony TOSHIBA Web Camera - HD                                | 7         | 1.03%   |
| Chicony HP Truevision HD                                       | 7         | 1.03%   |
| ALi Gateway Webcam                                             | 7         | 1.03%   |
| Quanta HP Webcam                                               | 6         | 0.88%   |
| Microdia Integrated_Webcam_HD                                  | 6         | 0.88%   |
| Lite-On Integrated Camera                                      | 6         | 0.88%   |
| Chicony VGA Webcam                                             | 6         | 0.88%   |
| Chicony HP Webcam                                              | 6         | 0.88%   |
| Chicony HD WebCam                                              | 6         | 0.88%   |
| Chicony CNF9055 Toshiba Webcam                                 | 6         | 0.88%   |
| Acer Integrated Camera                                         | 6         | 0.88%   |
| Sunplus HP HD Webcam [Fixed]                                   | 5         | 0.74%   |
| Sunplus HD WebCam                                              | 5         | 0.74%   |
| Silicon Motion Web Camera                                      | 5         | 0.74%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 5         | 0.74%   |
| Chicony USB2.0 HD UVC WebCam                                   | 5         | 0.74%   |
| Chicony HP Wide Vision HD Camera                               | 5         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD        | 5         | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 5         | 0.74%   |
| Apple iPhone 5/5C/5S/6/SE                                      | 5         | 0.74%   |
| Alcor Micro USB 2.0 Camera                                     | 5         | 0.74%   |
| Z-Star Webcam                                                  | 4         | 0.59%   |
| Syntek EasyCamera                                              | 4         | 0.59%   |
| Silicon Motion WebCam SCB-0355N                                | 4         | 0.59%   |
| Samsung Galaxy A5 (MTP)                                        | 4         | 0.59%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 4         | 0.59%   |
| Realtek 2SF022                                                 | 4         | 0.59%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 0.59%   |
| OmniVision OV2640 Webcam                                       | 4         | 0.59%   |
| Importek TOSHIBA Web Camera - HD                               | 4         | 0.59%   |
| IMC Networks ov9734_azurewave_camera                           | 4         | 0.59%   |
| Chicony Integrated HP HD Webcam                                | 4         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) Webcam                  | 4         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 4         | 0.59%   |
| Apple FaceTime Camera                                          | 4         | 0.59%   |
| Alcor Micro HP Webcam-101                                      | 4         | 0.59%   |
| Acer EasyCamera                                                | 4         | 0.59%   |
| Suyin HP Webcam-101                                            | 3         | 0.44%   |
| Suyin Acer CrystalEye Webcam                                   | 3         | 0.44%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 3         | 0.44%   |
| Sunplus Asus Webcam                                            | 3         | 0.44%   |
| Silicon Motion Lenovo EasyCamera                               | 3         | 0.44%   |
| Ricoh Integrated Webcam                                        | 3         | 0.44%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 66        | 56.41%  |
| AuthenTec                  | 22        | 18.8%   |
| Upek                       | 8         | 6.84%   |
| STMicroelectronics         | 8         | 6.84%   |
| Shenzhen Goodix Technology | 6         | 5.13%   |
| Synaptics                  | 3         | 2.56%   |
| Elan Microelectronics      | 3         | 2.56%   |
| LighTuning Technology      | 1         | 0.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 14        | 11.97%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 8.55%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 7.69%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 6.84%   |
| STMicroelectronics Fingerprint Reader                                      | 8         | 6.84%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 7         | 5.98%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 5.13%   |
| Validity Sensors VFS491                                                    | 5         | 4.27%   |
| AuthenTec AES1600                                                          | 5         | 4.27%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 3.42%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 3.42%   |
| AuthenTec AES2810                                                          | 4         | 3.42%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.56%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 2.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.71%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.71%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.71%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.85%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.85%   |
| Synaptics  WBDI                                                            | 1         | 0.85%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.85%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.85%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.85%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.85%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 22        | 46.81%  |
| O2 Micro              | 10        | 21.28%  |
| Alcor Micro           | 9         | 19.15%  |
| Upek                  | 2         | 4.26%   |
| Lenovo                | 2         | 4.26%   |
| SCM Microsystems      | 1         | 2.13%   |
| Realtek Semiconductor | 1         | 2.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 27.66%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 9         | 19.15%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 17.02%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 5         | 10.64%  |
| Broadcom 5880                                                                | 4         | 8.51%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.26%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 4.26%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 4.26%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 2.13%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 2.13%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 575       | 62.91%  |
| 1     | 273       | 29.87%  |
| 2     | 59        | 6.46%   |
| 3     | 5         | 0.55%   |
| 7     | 1         | 0.11%   |
| 4     | 1         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 116       | 29.15%  |
| Graphics card            | 91        | 22.86%  |
| Net/wireless             | 66        | 16.58%  |
| Chipcard                 | 46        | 11.56%  |
| Modem                    | 20        | 5.03%   |
| Storage                  | 15        | 3.77%   |
| Bluetooth                | 10        | 2.51%   |
| Sound                    | 7         | 1.76%   |
| Flash memory             | 7         | 1.76%   |
| Multimedia controller    | 5         | 1.26%   |
| Camera                   | 5         | 1.26%   |
| Communication controller | 4         | 1.01%   |
| Net/ethernet             | 3         | 0.75%   |
| Card reader              | 2         | 0.5%    |
| Storage/ata              | 1         | 0.25%   |

