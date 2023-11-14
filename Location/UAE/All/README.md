Linux in UAE - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Linux in UAE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/UAE/Desktop/README.md) and [notebooks](/Location/UAE/Notebook/README.md).

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

Total: 295

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [600445b726](https://linux-hardware.org/?probe=600445b726) | Nov 05, 2023 |
| HP            | HPPavilionLaptop15-eh0xx... | Notebook    | [436064bfba](https://linux-hardware.org/?probe=436064bfba) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [92ed6d25c3](https://linux-hardware.org/?probe=92ed6d25c3) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [f4cbcd5ba1](https://linux-hardware.org/?probe=f4cbcd5ba1) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [34a347877f](https://linux-hardware.org/?probe=34a347877f) | Nov 05, 2023 |
| HP            | 1589                        | Desktop     | [61922d4b43](https://linux-hardware.org/?probe=61922d4b43) | Nov 05, 2023 |
| Gigabyte      | A5 X1                       | Notebook    | [981be88a61](https://linux-hardware.org/?probe=981be88a61) | Oct 30, 2023 |
| Lenovo        | ThinkPad E490 20N80006UE    | Notebook    | [4bb8e497d3](https://linux-hardware.org/?probe=4bb8e497d3) | Oct 28, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [2937846c1b](https://linux-hardware.org/?probe=2937846c1b) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [8678e7aace](https://linux-hardware.org/?probe=8678e7aace) | Oct 08, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [e6e1c9bac9](https://linux-hardware.org/?probe=e6e1c9bac9) | Sep 30, 2023 |
| I-Life Dig... | ZED AIR PRO                 | Notebook    | [7cb30879f6](https://linux-hardware.org/?probe=7cb30879f6) | Sep 28, 2023 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | Notebook    | [64a85b8eb3](https://linux-hardware.org/?probe=64a85b8eb3) | Sep 28, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [17bbb23241](https://linux-hardware.org/?probe=17bbb23241) | Sep 22, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [89bf6e640b](https://linux-hardware.org/?probe=89bf6e640b) | Sep 12, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [7f0de230c8](https://linux-hardware.org/?probe=7f0de230c8) | Sep 12, 2023 |
| Google        | Lick                        | Notebook    | [11aec9d97c](https://linux-hardware.org/?probe=11aec9d97c) | Sep 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [53b237137d](https://linux-hardware.org/?probe=53b237137d) | Aug 30, 2023 |
| HP            | 8446                        | All in one  | [9d508328d5](https://linux-hardware.org/?probe=9d508328d5) | Aug 19, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [0585143fdc](https://linux-hardware.org/?probe=0585143fdc) | Aug 19, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [de0ce7c424](https://linux-hardware.org/?probe=de0ce7c424) | Aug 06, 2023 |
| Dell          | Latitude 3420               | Notebook    | [cdecb64c4a](https://linux-hardware.org/?probe=cdecb64c4a) | Aug 04, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [c741db51a0](https://linux-hardware.org/?probe=c741db51a0) | Aug 03, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [18eceddda0](https://linux-hardware.org/?probe=18eceddda0) | Jul 26, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [3466d6ab26](https://linux-hardware.org/?probe=3466d6ab26) | Jul 23, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [94df828438](https://linux-hardware.org/?probe=94df828438) | Jul 22, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3539141ba9](https://linux-hardware.org/?probe=3539141ba9) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | Desktop     | [0c592730d7](https://linux-hardware.org/?probe=0c592730d7) | Jul 16, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [9b3b477b44](https://linux-hardware.org/?probe=9b3b477b44) | Jul 11, 2023 |
| ASRock        | E3C224D4I-14S               | Desktop     | [bd2d074d07](https://linux-hardware.org/?probe=bd2d074d07) | Jul 09, 2023 |
| Dell          | G15 Special Edition 5521    | Notebook    | [42890cd134](https://linux-hardware.org/?probe=42890cd134) | Jul 04, 2023 |
| Dell          | G15 Special Edition 5521    | Notebook    | [8a3a0f9375](https://linux-hardware.org/?probe=8a3a0f9375) | Jul 04, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [884a5ecd03](https://linux-hardware.org/?probe=884a5ecd03) | Jun 28, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [53ef3811fc](https://linux-hardware.org/?probe=53ef3811fc) | Jun 21, 2023 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [7dd15a9fa4](https://linux-hardware.org/?probe=7dd15a9fa4) | Jun 19, 2023 |
| Intel         | NUC9VXQNB K47179-402        | Mini pc     | [f3c7611dd0](https://linux-hardware.org/?probe=f3c7611dd0) | Jun 17, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [75eeeb7917](https://linux-hardware.org/?probe=75eeeb7917) | Jun 16, 2023 |
| Lenovo        | Yoga Creator 7 15IMH05 8... | Notebook    | [3bcc239452](https://linux-hardware.org/?probe=3bcc239452) | Jun 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [0c81d929ca](https://linux-hardware.org/?probe=0c81d929ca) | Jun 04, 2023 |
| HP            | 0B54h D                     | Desktop     | [f9634b51b9](https://linux-hardware.org/?probe=f9634b51b9) | May 28, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [589112cb44](https://linux-hardware.org/?probe=589112cb44) | May 25, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [2ae74516a9](https://linux-hardware.org/?probe=2ae74516a9) | May 24, 2023 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [cbd7b1dcc7](https://linux-hardware.org/?probe=cbd7b1dcc7) | May 24, 2023 |
| Lenovo        | ThinkPad T490 20N2004JAD    | Notebook    | [c765eed46d](https://linux-hardware.org/?probe=c765eed46d) | May 16, 2023 |
| Toshiba       | Satellite L850-B434         | Notebook    | [54e6cd2fc6](https://linux-hardware.org/?probe=54e6cd2fc6) | May 13, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [89747b6213](https://linux-hardware.org/?probe=89747b6213) | May 12, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [0a639ba55d](https://linux-hardware.org/?probe=0a639ba55d) | May 08, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [aabb19e388](https://linux-hardware.org/?probe=aabb19e388) | May 06, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [b9ef1562db](https://linux-hardware.org/?probe=b9ef1562db) | May 05, 2023 |
| Lenovo        | ThinkPad Yoga 11e 4th Ge... | Convertible | [02fa09745c](https://linux-hardware.org/?probe=02fa09745c) | May 05, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [856494ea85](https://linux-hardware.org/?probe=856494ea85) | May 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [c6e5e310b9](https://linux-hardware.org/?probe=c6e5e310b9) | May 02, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [1704454cdb](https://linux-hardware.org/?probe=1704454cdb) | May 02, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [d2f8737b9d](https://linux-hardware.org/?probe=d2f8737b9d) | May 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [78a3abdc19](https://linux-hardware.org/?probe=78a3abdc19) | Apr 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [59c225df6e](https://linux-hardware.org/?probe=59c225df6e) | Apr 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [6e2da1e766](https://linux-hardware.org/?probe=6e2da1e766) | Apr 21, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [00ed2824f0](https://linux-hardware.org/?probe=00ed2824f0) | Apr 20, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [7a4242a973](https://linux-hardware.org/?probe=7a4242a973) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [a0cf4fd00d](https://linux-hardware.org/?probe=a0cf4fd00d) | Apr 19, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [7ce26d7fd9](https://linux-hardware.org/?probe=7ce26d7fd9) | Apr 19, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d0c3e2bb4e](https://linux-hardware.org/?probe=d0c3e2bb4e) | Apr 19, 2023 |
| HP            | 15-dc1018ur                 | Notebook    | [7df35a90ad](https://linux-hardware.org/?probe=7df35a90ad) | Apr 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [a7b2caaba8](https://linux-hardware.org/?probe=a7b2caaba8) | Apr 16, 2023 |
| HP            | Pavilion 15                 | Notebook    | [199f3bb771](https://linux-hardware.org/?probe=199f3bb771) | Apr 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59db7a4f11](https://linux-hardware.org/?probe=59db7a4f11) | Apr 10, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [125884d17a](https://linux-hardware.org/?probe=125884d17a) | Apr 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1U20... | Notebook    | [99ea485cee](https://linux-hardware.org/?probe=99ea485cee) | Mar 27, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [83fb0eaf6e](https://linux-hardware.org/?probe=83fb0eaf6e) | Mar 26, 2023 |
| ASUSTek       | Q551LN                      | Notebook    | [3385f39150](https://linux-hardware.org/?probe=3385f39150) | Mar 26, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [1a46276700](https://linux-hardware.org/?probe=1a46276700) | Mar 05, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [2a8830034a](https://linux-hardware.org/?probe=2a8830034a) | Feb 26, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [452bd46c01](https://linux-hardware.org/?probe=452bd46c01) | Feb 22, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [fe78ef8424](https://linux-hardware.org/?probe=fe78ef8424) | Feb 22, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [83bef528a7](https://linux-hardware.org/?probe=83bef528a7) | Feb 19, 2023 |
| Lenovo        | G50-80 80E5                 | Notebook    | [64c385ee36](https://linux-hardware.org/?probe=64c385ee36) | Feb 16, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [54f7f241bf](https://linux-hardware.org/?probe=54f7f241bf) | Feb 15, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [8fc284c3b5](https://linux-hardware.org/?probe=8fc284c3b5) | Feb 15, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [3b09c5ed9e](https://linux-hardware.org/?probe=3b09c5ed9e) | Feb 04, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [be3ef90301](https://linux-hardware.org/?probe=be3ef90301) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [9fb41ee5bc](https://linux-hardware.org/?probe=9fb41ee5bc) | Feb 01, 2023 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | Notebook    | [a64ae29757](https://linux-hardware.org/?probe=a64ae29757) | Jan 31, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [f308688189](https://linux-hardware.org/?probe=f308688189) | Jan 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [83d050bdbe](https://linux-hardware.org/?probe=83d050bdbe) | Jan 25, 2023 |
| HP            | Laptop 14-dq2xxx            | Notebook    | [9a930173a0](https://linux-hardware.org/?probe=9a930173a0) | Jan 24, 2023 |
| HP            | 1998                        | Desktop     | [5fcedbdb28](https://linux-hardware.org/?probe=5fcedbdb28) | Jan 22, 2023 |
| Dell          | G5 5587                     | Notebook    | [96ca22c550](https://linux-hardware.org/?probe=96ca22c550) | Jan 21, 2023 |
| Dell          | G5 5587                     | Notebook    | [a070a8ba69](https://linux-hardware.org/?probe=a070a8ba69) | Jan 21, 2023 |
| Acer          | Aspire E5-471P              | Notebook    | [c50e807e64](https://linux-hardware.org/?probe=c50e807e64) | Jan 12, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [6d3966411f](https://linux-hardware.org/?probe=6d3966411f) | Jan 09, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [1405e2a7c8](https://linux-hardware.org/?probe=1405e2a7c8) | Jan 09, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [6206409322](https://linux-hardware.org/?probe=6206409322) | Jan 08, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [eab8778810](https://linux-hardware.org/?probe=eab8778810) | Dec 30, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [89c0ffe36d](https://linux-hardware.org/?probe=89c0ffe36d) | Dec 29, 2022 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [d27a1b703b](https://linux-hardware.org/?probe=d27a1b703b) | Dec 26, 2022 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [f048f7fcdb](https://linux-hardware.org/?probe=f048f7fcdb) | Dec 16, 2022 |
| AZW           | GTR V01                     | Mini pc     | [9f1097843c](https://linux-hardware.org/?probe=9f1097843c) | Dec 12, 2022 |
| Valve         | Jupiter                     | Notebook    | [fae62b5114](https://linux-hardware.org/?probe=fae62b5114) | Dec 11, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [c74d870263](https://linux-hardware.org/?probe=c74d870263) | Dec 04, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [8277ece293](https://linux-hardware.org/?probe=8277ece293) | Nov 30, 2022 |
| Dell          | 0F9N89 A00                  | Server      | [3a917876ba](https://linux-hardware.org/?probe=3a917876ba) | Nov 23, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [79119cca36](https://linux-hardware.org/?probe=79119cca36) | Nov 19, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [1b30c252bb](https://linux-hardware.org/?probe=1b30c252bb) | Nov 19, 2022 |
| HP            | 0AECh D                     | Desktop     | [9e2ddc5dbd](https://linux-hardware.org/?probe=9e2ddc5dbd) | Nov 18, 2022 |
| HP            | 0AECh D                     | Desktop     | [95b36ddda4](https://linux-hardware.org/?probe=95b36ddda4) | Nov 18, 2022 |
| HP            | 1495                        | Desktop     | [c4535d8ea8](https://linux-hardware.org/?probe=c4535d8ea8) | Nov 15, 2022 |
| Gigabyte      | EP45T-UD3R                  | Desktop     | [faf014b2e6](https://linux-hardware.org/?probe=faf014b2e6) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [d9af542480](https://linux-hardware.org/?probe=d9af542480) | Nov 08, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [7d3eac2c7d](https://linux-hardware.org/?probe=7d3eac2c7d) | Nov 05, 2022 |
| Gigabyte      | Q270M-D3H                   | Desktop     | [46874cc0a1](https://linux-hardware.org/?probe=46874cc0a1) | Nov 02, 2022 |
| Lenovo        | ThinkPad P1 Gen 5 21DC00... | Notebook    | [910b452558](https://linux-hardware.org/?probe=910b452558) | Oct 30, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [7406489511](https://linux-hardware.org/?probe=7406489511) | Oct 21, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [e8e0acd06e](https://linux-hardware.org/?probe=e8e0acd06e) | Oct 17, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [fdab72c478](https://linux-hardware.org/?probe=fdab72c478) | Oct 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b1590cf8fa](https://linux-hardware.org/?probe=b1590cf8fa) | Oct 03, 2022 |
| Intel         | NUC10i3FNB K61362-306       | Mini pc     | [e8130be6f2](https://linux-hardware.org/?probe=e8130be6f2) | Oct 03, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [df5fcf14f9](https://linux-hardware.org/?probe=df5fcf14f9) | Sep 26, 2022 |
| ASUSTek       | ROG Zephyrus M16 GU603ZW... | Notebook    | [472668e67b](https://linux-hardware.org/?probe=472668e67b) | Sep 12, 2022 |
| MSI           | Z97 PC Mate                 | Desktop     | [512c793b51](https://linux-hardware.org/?probe=512c793b51) | Sep 06, 2022 |
| Lenovo        | ThinkPad T61 76653JG        | Notebook    | [0fae1da16b](https://linux-hardware.org/?probe=0fae1da16b) | Aug 02, 2022 |
| Lenovo        | 81FV                        | Notebook    | [aa9e5c9f73](https://linux-hardware.org/?probe=aa9e5c9f73) | Jul 22, 2022 |
| Lenovo        | ThinkPad T480s 20L7001PA... | Notebook    | [de71ab8780](https://linux-hardware.org/?probe=de71ab8780) | Jul 21, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [b847a4a45d](https://linux-hardware.org/?probe=b847a4a45d) | Jul 03, 2022 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [0aa196cd0c](https://linux-hardware.org/?probe=0aa196cd0c) | Jul 03, 2022 |
| Dell          | 0MGK50 A02                  | Desktop     | [eca7a31c46](https://linux-hardware.org/?probe=eca7a31c46) | Jun 23, 2022 |
| Dell          | 0MGK50 A02                  | Desktop     | [134bf128f7](https://linux-hardware.org/?probe=134bf128f7) | Jun 23, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [0fbbdf9197](https://linux-hardware.org/?probe=0fbbdf9197) | Jun 07, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [ad2442631e](https://linux-hardware.org/?probe=ad2442631e) | May 28, 2022 |
| HP            | 8446                        | All in one  | [821752cb21](https://linux-hardware.org/?probe=821752cb21) | May 11, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [6c498d2ce5](https://linux-hardware.org/?probe=6c498d2ce5) | Apr 29, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS4... | Notebook    | [28c774c6de](https://linux-hardware.org/?probe=28c774c6de) | Apr 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [718b671125](https://linux-hardware.org/?probe=718b671125) | Apr 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [5e0763131c](https://linux-hardware.org/?probe=5e0763131c) | Mar 28, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4edc1d31b5](https://linux-hardware.org/?probe=4edc1d31b5) | Mar 06, 2022 |
| Google        | Terra                       | Notebook    | [54163369b2](https://linux-hardware.org/?probe=54163369b2) | Feb 23, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [f014fcba4f](https://linux-hardware.org/?probe=f014fcba4f) | Feb 14, 2022 |
| Dell          | Latitude E6230              | Notebook    | [a8aeb155b0](https://linux-hardware.org/?probe=a8aeb155b0) | Feb 10, 2022 |
| Biostar       | TZ77XE4                     | Desktop     | [081c3be70e](https://linux-hardware.org/?probe=081c3be70e) | Feb 07, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| Dell          | Latitude E5440              | Notebook    | [ebbb8ee138](https://linux-hardware.org/?probe=ebbb8ee138) | Jan 22, 2022 |
| Lenovo        | ThinkPad T480s 20L8S3FV0... | Notebook    | [78080db667](https://linux-hardware.org/?probe=78080db667) | Jan 13, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4670daefab](https://linux-hardware.org/?probe=4670daefab) | Jan 04, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [c36553e3a3](https://linux-hardware.org/?probe=c36553e3a3) | Dec 27, 2021 |
| Google        | Akemi                       | Notebook    | [aaf0a3e10e](https://linux-hardware.org/?probe=aaf0a3e10e) | Dec 20, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [927497310e](https://linux-hardware.org/?probe=927497310e) | Nov 16, 2021 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [7b77d5463d](https://linux-hardware.org/?probe=7b77d5463d) | Nov 13, 2021 |
| win elemen... | MoreFine S500+              | Notebook    | [ace08cf199](https://linux-hardware.org/?probe=ace08cf199) | Nov 11, 2021 |
| win elemen... | MoreFine S500+              | Notebook    | [0e31d4b6fa](https://linux-hardware.org/?probe=0e31d4b6fa) | Nov 11, 2021 |
| MSI           | PS63 Modern 8RD             | Notebook    | [519048dea2](https://linux-hardware.org/?probe=519048dea2) | Nov 01, 2021 |
| MSI           | PS63 Modern 8RD             | Notebook    | [6d3cd2f117](https://linux-hardware.org/?probe=6d3cd2f117) | Nov 01, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [24d1bd52cc](https://linux-hardware.org/?probe=24d1bd52cc) | Oct 28, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [41ff21e8e8](https://linux-hardware.org/?probe=41ff21e8e8) | Oct 06, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [6654adaf99](https://linux-hardware.org/?probe=6654adaf99) | Oct 04, 2021 |
| HP            | ProBook 6475b               | Notebook    | [9d60bf5397](https://linux-hardware.org/?probe=9d60bf5397) | Oct 02, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [eccb23bda1](https://linux-hardware.org/?probe=eccb23bda1) | Sep 24, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [888ca9b5de](https://linux-hardware.org/?probe=888ca9b5de) | Sep 04, 2021 |
| Apple         | MacBook9,1                  | Notebook    | [69119d1952](https://linux-hardware.org/?probe=69119d1952) | Sep 04, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [e1f91ca6de](https://linux-hardware.org/?probe=e1f91ca6de) | Sep 02, 2021 |
| HP            | 8446                        | All in one  | [430c02980a](https://linux-hardware.org/?probe=430c02980a) | Aug 13, 2021 |
| Sony          | VGN-NS10J_S                 | Notebook    | [31d1e0e91d](https://linux-hardware.org/?probe=31d1e0e91d) | Aug 12, 2021 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [e25c41c312](https://linux-hardware.org/?probe=e25c41c312) | Jul 03, 2021 |
| LG Electro... | C500-G.AEF5BE1              | Notebook    | [b78f4cd34d](https://linux-hardware.org/?probe=b78f4cd34d) | Jun 14, 2021 |
| Toshiba       | Satellite C850-A966         | Notebook    | [391d22d993](https://linux-hardware.org/?probe=391d22d993) | Jun 02, 2021 |
| Sony          | SVE14A25CAB                 | Notebook    | [78ddb916b5](https://linux-hardware.org/?probe=78ddb916b5) | May 30, 2021 |
| Sony          | SVE14A25CAB                 | Notebook    | [0a2c5cf1cd](https://linux-hardware.org/?probe=0a2c5cf1cd) | May 30, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5707e7ae37](https://linux-hardware.org/?probe=5707e7ae37) | May 28, 2021 |
| Dell          | OptiPlex 980                | Desktop     | [1fe360b027](https://linux-hardware.org/?probe=1fe360b027) | May 26, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [66cc8bd4a5](https://linux-hardware.org/?probe=66cc8bd4a5) | May 19, 2021 |
| Dell          | G5 5587                     | Notebook    | [2d2cf67a2d](https://linux-hardware.org/?probe=2d2cf67a2d) | May 08, 2021 |
| Dell          | Latitude E6510              | Notebook    | [06d38294ab](https://linux-hardware.org/?probe=06d38294ab) | May 03, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [e3b22a36fb](https://linux-hardware.org/?probe=e3b22a36fb) | Apr 22, 2021 |
| Lenovo        | Legion Y7000P 81LD          | Notebook    | [f5715022b7](https://linux-hardware.org/?probe=f5715022b7) | Apr 22, 2021 |
| HP            | 8446                        | All in one  | [a52aa6f1bd](https://linux-hardware.org/?probe=a52aa6f1bd) | Mar 10, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [6b82d5c050](https://linux-hardware.org/?probe=6b82d5c050) | Mar 07, 2021 |
| Acer          | Aspire 5755G                | Notebook    | [227244211b](https://linux-hardware.org/?probe=227244211b) | Mar 07, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [3c9d39abce](https://linux-hardware.org/?probe=3c9d39abce) | Mar 06, 2021 |
| Lenovo        | ThinkPad X230 2325DV8       | Notebook    | [11d5145d10](https://linux-hardware.org/?probe=11d5145d10) | Feb 12, 2021 |
| HP            | Elite Dragonfly             | Convertible | [87b2f82af5](https://linux-hardware.org/?probe=87b2f82af5) | Feb 01, 2021 |
| HP            | Elite Dragonfly             | Convertible | [6e1ef1920c](https://linux-hardware.org/?probe=6e1ef1920c) | Jan 31, 2021 |
| HP            | Elite Dragonfly             | Convertible | [215ff8ccba](https://linux-hardware.org/?probe=215ff8ccba) | Jan 31, 2021 |
| HP            | Pavilion dv6                | Notebook    | [317b81878c](https://linux-hardware.org/?probe=317b81878c) | Jan 27, 2021 |
| Lenovo        | 3098 NOK                    | Desktop     | [d0ccf5266d](https://linux-hardware.org/?probe=d0ccf5266d) | Jan 27, 2021 |
| ASUSTek       | Strix GL703GM_GL703GM       | Notebook    | [3d8ea2b061](https://linux-hardware.org/?probe=3d8ea2b061) | Jan 27, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [a3c15a6f74](https://linux-hardware.org/?probe=a3c15a6f74) | Jan 18, 2021 |
| HP            | Laptop 15-da1xxx            | Notebook    | [58bf01b1e7](https://linux-hardware.org/?probe=58bf01b1e7) | Jan 18, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [2e84869a9a](https://linux-hardware.org/?probe=2e84869a9a) | Jan 11, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1c5ef3cfe4](https://linux-hardware.org/?probe=1c5ef3cfe4) | Jan 11, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d071e37713](https://linux-hardware.org/?probe=d071e37713) | Jan 10, 2021 |
| HP            | 8446                        | All in one  | [a07d483bab](https://linux-hardware.org/?probe=a07d483bab) | Jan 07, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [6a02570e23](https://linux-hardware.org/?probe=6a02570e23) | Jan 03, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [092666f171](https://linux-hardware.org/?probe=092666f171) | Dec 31, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [93e3d5b038](https://linux-hardware.org/?probe=93e3d5b038) | Dec 25, 2020 |
| HP            | EliteBook 8460p             | Notebook    | [d24a3c768e](https://linux-hardware.org/?probe=d24a3c768e) | Dec 24, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [cb1c064071](https://linux-hardware.org/?probe=cb1c064071) | Dec 16, 2020 |
| Dell          | Latitude E6410              | Notebook    | [a2a46d21e9](https://linux-hardware.org/?probe=a2a46d21e9) | Dec 15, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [e2816ed19c](https://linux-hardware.org/?probe=e2816ed19c) | Nov 27, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [12a3adede5](https://linux-hardware.org/?probe=12a3adede5) | Nov 06, 2020 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [91e0e6c6bc](https://linux-hardware.org/?probe=91e0e6c6bc) | Nov 04, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6f0218a447](https://linux-hardware.org/?probe=6f0218a447) | Oct 28, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7ad824c6f9](https://linux-hardware.org/?probe=7ad824c6f9) | Oct 26, 2020 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [54531ec292](https://linux-hardware.org/?probe=54531ec292) | Oct 21, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f372424ac5](https://linux-hardware.org/?probe=f372424ac5) | Oct 18, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [387171a87d](https://linux-hardware.org/?probe=387171a87d) | Oct 08, 2020 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [b1cd303933](https://linux-hardware.org/?probe=b1cd303933) | Oct 08, 2020 |
| HP            | 2AA2                        | Desktop     | [ceebc6a90b](https://linux-hardware.org/?probe=ceebc6a90b) | Oct 04, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [7d3672caff](https://linux-hardware.org/?probe=7d3672caff) | Oct 04, 2020 |
| Intel         | D865PERL AAC27648-207       | Desktop     | [2a18eaa0ab](https://linux-hardware.org/?probe=2a18eaa0ab) | Oct 04, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [f9f212a509](https://linux-hardware.org/?probe=f9f212a509) | Oct 01, 2020 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [ab392f30cb](https://linux-hardware.org/?probe=ab392f30cb) | Sep 30, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [42c8711bea](https://linux-hardware.org/?probe=42c8711bea) | Sep 29, 2020 |
| Acer          | ChiefRiver Platform         | Notebook    | [23e2162b8e](https://linux-hardware.org/?probe=23e2162b8e) | Sep 20, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [22369a8f3c](https://linux-hardware.org/?probe=22369a8f3c) | Sep 20, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [d026d40366](https://linux-hardware.org/?probe=d026d40366) | Sep 17, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [18778a34f2](https://linux-hardware.org/?probe=18778a34f2) | Sep 10, 2020 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [ff1f32c975](https://linux-hardware.org/?probe=ff1f32c975) | Sep 10, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [94cbf8e66c](https://linux-hardware.org/?probe=94cbf8e66c) | Sep 10, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a25d4e5346](https://linux-hardware.org/?probe=a25d4e5346) | Sep 09, 2020 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c4c1a329af](https://linux-hardware.org/?probe=c4c1a329af) | Sep 06, 2020 |
| Dell          | Inspiron 5537               | Notebook    | [4ddf924081](https://linux-hardware.org/?probe=4ddf924081) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | Notebook    | [23a0e05047](https://linux-hardware.org/?probe=23a0e05047) | Sep 05, 2020 |
| Dell          | Latitude E6540              | Notebook    | [9abf14d168](https://linux-hardware.org/?probe=9abf14d168) | Aug 31, 2020 |
| HP            | 8446                        | All in one  | [08b9600cae](https://linux-hardware.org/?probe=08b9600cae) | Aug 29, 2020 |
| Dell          | Precision 5540              | Notebook    | [76f1cfa736](https://linux-hardware.org/?probe=76f1cfa736) | Aug 23, 2020 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [19af27b191](https://linux-hardware.org/?probe=19af27b191) | Aug 20, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [f555bad747](https://linux-hardware.org/?probe=f555bad747) | Aug 14, 2020 |
| I-Life Dig... | ZED AIR                     | Notebook    | [b40d7e9c7c](https://linux-hardware.org/?probe=b40d7e9c7c) | Aug 10, 2020 |
| I-Life Dig... | ZED AIR                     | Notebook    | [5662aa186c](https://linux-hardware.org/?probe=5662aa186c) | Aug 10, 2020 |
| HP            | 2AA2                        | Desktop     | [f20932c5c3](https://linux-hardware.org/?probe=f20932c5c3) | Aug 09, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | Notebook    | [81d46e4c4a](https://linux-hardware.org/?probe=81d46e4c4a) | Aug 02, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [670cc8a66c](https://linux-hardware.org/?probe=670cc8a66c) | Jul 26, 2020 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [aea3470496](https://linux-hardware.org/?probe=aea3470496) | Jul 21, 2020 |
| HP            | 2AA2                        | Desktop     | [424f0397a7](https://linux-hardware.org/?probe=424f0397a7) | Jul 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [b3dbd3f2af](https://linux-hardware.org/?probe=b3dbd3f2af) | Jul 14, 2020 |
| Toshiba       | TECRA A50-C                 | Notebook    | [adf7a73571](https://linux-hardware.org/?probe=adf7a73571) | Jul 03, 2020 |
| ASUSTek       | FX503VD                     | Notebook    | [d6c0a21749](https://linux-hardware.org/?probe=d6c0a21749) | Jul 02, 2020 |
| HP            | Pavilion 15                 | Notebook    | [499f0c72ee](https://linux-hardware.org/?probe=499f0c72ee) | Jun 29, 2020 |
| ASUSTek       | P7P55 LX                    | Desktop     | [dc74d7b188](https://linux-hardware.org/?probe=dc74d7b188) | Jun 25, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [dd5c9e8d9f](https://linux-hardware.org/?probe=dd5c9e8d9f) | Jun 23, 2020 |
| Dell          | Latitude E6410              | Notebook    | [06055ff260](https://linux-hardware.org/?probe=06055ff260) | Jun 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X420... | Notebook    | [b53cc32ed0](https://linux-hardware.org/?probe=b53cc32ed0) | Jun 19, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [fdc9496e84](https://linux-hardware.org/?probe=fdc9496e84) | Jun 19, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [fdbf1ae7da](https://linux-hardware.org/?probe=fdbf1ae7da) | Jun 19, 2020 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [0d398d9227](https://linux-hardware.org/?probe=0d398d9227) | Jun 14, 2020 |
| HP            | 2AA2                        | Desktop     | [24c07d9d0d](https://linux-hardware.org/?probe=24c07d9d0d) | Jun 11, 2020 |
| HP            | 8446                        | All in one  | [d64a9cef98](https://linux-hardware.org/?probe=d64a9cef98) | Jun 11, 2020 |
| Dell          | Latitude E6410              | Notebook    | [1b73d74e65](https://linux-hardware.org/?probe=1b73d74e65) | Jun 09, 2020 |
| Lenovo        | ThinkPad L480 20LS0012AD    | Notebook    | [e9b38b78d7](https://linux-hardware.org/?probe=e9b38b78d7) | May 30, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [83ae823929](https://linux-hardware.org/?probe=83ae823929) | May 23, 2020 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [af063f022b](https://linux-hardware.org/?probe=af063f022b) | May 23, 2020 |
| HP            | Presario C300 (RH208UA#A... | Notebook    | [50e95ff237](https://linux-hardware.org/?probe=50e95ff237) | May 14, 2020 |
| HP            | Presario C300 (RH208UA#A... | Notebook    | [6b4a8eab4c](https://linux-hardware.org/?probe=6b4a8eab4c) | May 14, 2020 |
| Toshiba       | TECRA X40-D                 | Notebook    | [3255796d07](https://linux-hardware.org/?probe=3255796d07) | May 10, 2020 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [49363e9553](https://linux-hardware.org/?probe=49363e9553) | May 07, 2020 |
| HP            | 8446                        | All in one  | [96d169caae](https://linux-hardware.org/?probe=96d169caae) | May 06, 2020 |
| HP            | 8446                        | All in one  | [835b1abcee](https://linux-hardware.org/?probe=835b1abcee) | May 02, 2020 |
| HP            | 8446                        | All in one  | [aa03445e30](https://linux-hardware.org/?probe=aa03445e30) | May 01, 2020 |
| HP            | 8446                        | All in one  | [d9db887931](https://linux-hardware.org/?probe=d9db887931) | May 01, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [887a19760b](https://linux-hardware.org/?probe=887a19760b) | May 01, 2020 |
| Lenovo        | ThinkPad X240 20AMS6GB00    | Notebook    | [3fa804be21](https://linux-hardware.org/?probe=3fa804be21) | May 01, 2020 |
| HP            | 8446                        | All in one  | [eab561395e](https://linux-hardware.org/?probe=eab561395e) | Apr 27, 2020 |
| HP            | 8446                        | All in one  | [ad2491858f](https://linux-hardware.org/?probe=ad2491858f) | Apr 25, 2020 |
| YJKC          | vBOOK Plus RVP7             | Notebook    | [d2328783da](https://linux-hardware.org/?probe=d2328783da) | Apr 24, 2020 |
| Dell          | Vostro 14-5480              | Notebook    | [1bba68101c](https://linux-hardware.org/?probe=1bba68101c) | Apr 20, 2020 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [aac474f532](https://linux-hardware.org/?probe=aac474f532) | Apr 18, 2020 |
| HP            | ProBook 450 G2              | Notebook    | [1ef49ff7a3](https://linux-hardware.org/?probe=1ef49ff7a3) | Apr 17, 2020 |
| HP            | Notebook                    | Notebook    | [4f154f82b0](https://linux-hardware.org/?probe=4f154f82b0) | Apr 01, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [5cd86dffe9](https://linux-hardware.org/?probe=5cd86dffe9) | Mar 16, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [7f0b4db18a](https://linux-hardware.org/?probe=7f0b4db18a) | Mar 12, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [87df29714d](https://linux-hardware.org/?probe=87df29714d) | Mar 11, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [04da794ff5](https://linux-hardware.org/?probe=04da794ff5) | Feb 25, 2020 |
| HP            | EliteBook 2760p             | Notebook    | [40333472c7](https://linux-hardware.org/?probe=40333472c7) | Feb 21, 2020 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [b12186f161](https://linux-hardware.org/?probe=b12186f161) | Feb 13, 2020 |
| HP            | Notebook                    | Notebook    | [a25a67e533](https://linux-hardware.org/?probe=a25a67e533) | Feb 02, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | Notebook    | [c2a7159d3a](https://linux-hardware.org/?probe=c2a7159d3a) | Jan 04, 2020 |
| Lenovo        | ThinkPad T460 20FMS1A200    | Notebook    | [028d728043](https://linux-hardware.org/?probe=028d728043) | Jan 04, 2020 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [d1ca80edff](https://linux-hardware.org/?probe=d1ca80edff) | Dec 24, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [420c738977](https://linux-hardware.org/?probe=420c738977) | Oct 15, 2019 |
| Toshiba       | Satellite A300              | Notebook    | [036dc7e829](https://linux-hardware.org/?probe=036dc7e829) | Oct 15, 2019 |
| Lenovo        | Yoga 2 Pro 20266            | Notebook    | [ab1c14d729](https://linux-hardware.org/?probe=ab1c14d729) | Oct 12, 2019 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [558c01fdce](https://linux-hardware.org/?probe=558c01fdce) | Oct 07, 2019 |
| Notebook      | P95_96_97Ex,Rx              | Notebook    | [d4ad7906b5](https://linux-hardware.org/?probe=d4ad7906b5) | Sep 11, 2019 |
| Dell          | 0NK70N A03                  | Desktop     | [8aa5224a4a](https://linux-hardware.org/?probe=8aa5224a4a) | Aug 01, 2019 |
| I-Life Dig... | ZED AIR                     | Notebook    | [514c494f7f](https://linux-hardware.org/?probe=514c494f7f) | Jul 23, 2019 |
| I-Life Dig... | ZED AIR                     | Notebook    | [a9fe92aa3c](https://linux-hardware.org/?probe=a9fe92aa3c) | Jul 23, 2019 |
| ASUSTek       | Rampage V EXTREME           | Desktop     | [309f371381](https://linux-hardware.org/?probe=309f371381) | May 27, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [1f8a20b199](https://linux-hardware.org/?probe=1f8a20b199) | May 25, 2019 |
| HP            | EliteBook 8440p             | Notebook    | [60d0e8dd5d](https://linux-hardware.org/?probe=60d0e8dd5d) | May 25, 2019 |
| HP            | ProBook 4540s               | Notebook    | [271be85705](https://linux-hardware.org/?probe=271be85705) | May 15, 2019 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [ab25f83cd0](https://linux-hardware.org/?probe=ab25f83cd0) | Mar 27, 2019 |
| ASUSTek       | ROG STRIX X299-XE GAMING    | Desktop     | [c8fdc5e958](https://linux-hardware.org/?probe=c8fdc5e958) | Dec 25, 2018 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [c48aa05e74](https://linux-hardware.org/?probe=c48aa05e74) | Oct 08, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 33        | 16.1%   |
| Ubuntu 22.04       | 20        | 9.76%   |
| Ubuntu 18.04       | 17        | 8.29%   |
| Debian 11          | 6         | 2.93%   |
| Pop!_OS 22.04      | 5         | 2.44%   |
| Fedora 38          | 5         | 2.44%   |
| Fedora 37          | 5         | 2.44%   |
| Arch               | 5         | 2.44%   |
| Zorin 16           | 4         | 1.95%   |
| Ubuntu 22.10       | 4         | 1.95%   |
| Ubuntu 19.10       | 4         | 1.95%   |
| Linux Mint 20.3    | 4         | 1.95%   |
| Fedora 36          | 4         | 1.95%   |
| Debian 12          | 4         | 1.95%   |
| Zorin 15           | 3         | 1.46%   |
| Ubuntu 23.04       | 3         | 1.46%   |
| Ubuntu 20.10       | 3         | 1.46%   |
| Kubuntu 22.04      | 3         | 1.46%   |
| Debian 10          | 3         | 1.46%   |
| ArcoLinux Rolling  | 3         | 1.46%   |
| Ubuntu 21.10       | 2         | 0.98%   |
| Ubuntu 16.04       | 2         | 0.98%   |
| SteamOS 3.4.6      | 2         | 0.98%   |
| Pop!_OS 20.10      | 2         | 0.98%   |
| Pop!_OS 20.04      | 2         | 0.98%   |
| OpenMandriva 4.3   | 2         | 0.98%   |
| OpenMandriva 23.01 | 2         | 0.98%   |
| Lubuntu 22.04      | 2         | 0.98%   |
| Linux Mint 21.1    | 2         | 0.98%   |
| KDE neon 20.04     | 2         | 0.98%   |
| Kali 2023.1        | 2         | 0.98%   |
| Fedora 35          | 2         | 0.98%   |
| Fedora 34          | 2         | 0.98%   |
| BlackPanther 18.1  | 2         | 0.98%   |
| Arch Rolling       | 2         | 0.98%   |
| Xubuntu 20.04      | 1         | 0.49%   |
| Xubuntu 16.04      | 1         | 0.49%   |
| Ubuntu Unity 18.04 | 1         | 0.49%   |
| Ubuntu MATE 20.04  | 1         | 0.49%   |
| Ubuntu 23.10       | 1         | 0.49%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 89        | 44.28%  |
| Fedora       | 18        | 8.96%   |
| Debian       | 13        | 6.47%   |
| Pop!_OS      | 9         | 4.48%   |
| Linux Mint   | 9         | 4.48%   |
| Zorin        | 7         | 3.48%   |
| OpenMandriva | 7         | 3.48%   |
| Arch         | 7         | 3.48%   |
| Manjaro      | 6         | 2.99%   |
| SteamOS      | 5         | 2.49%   |
| Kubuntu      | 3         | 1.49%   |
| KDE neon     | 3         | 1.49%   |
| ArcoLinux    | 3         | 1.49%   |
| Xubuntu      | 2         | 1%      |
| Lubuntu      | 2         | 1%      |
| Kali         | 2         | 1%      |
| Endless      | 2         | 1%      |
| BlackPanther | 2         | 1%      |
| Ubuntu Unity | 1         | 0.5%    |
| Ubuntu MATE  | 1         | 0.5%    |
| ROSA         | 1         | 0.5%    |
| Rocky Linux  | 1         | 0.5%    |
| Reborn OS    | 1         | 0.5%    |
| Guix         | 1         | 0.5%    |
| GNOME OS     | 1         | 0.5%    |
| Feren OS     | 1         | 0.5%    |
| EndeavourOS  | 1         | 0.5%    |
| Elementary   | 1         | 0.5%    |
| CachyOS      | 1         | 0.5%    |
| Alpine       | 1         | 0.5%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 7         | 3.18%   |
| 5.4.0-58-generic         | 4         | 1.82%   |
| 5.4.0-26-generic         | 4         | 1.82%   |
| 5.13.0-valve36-1-neptune | 4         | 1.82%   |
| 5.4.0-37-generic         | 3         | 1.36%   |
| 5.11.0-40-generic        | 3         | 1.36%   |
| 4.15.0-50-generic        | 3         | 1.36%   |
| 6.4.7-200.fc38.x86_64    | 2         | 0.91%   |
| 6.2.0-32-generic         | 2         | 0.91%   |
| 6.2.0-26-generic         | 2         | 0.91%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.91%   |
| 6.1.0-13-amd64           | 2         | 0.91%   |
| 6.0.6-76060006-generic   | 2         | 0.91%   |
| 5.8.0-40-generic         | 2         | 0.91%   |
| 5.4.0-81-generic         | 2         | 0.91%   |
| 5.4.0-48-generic         | 2         | 0.91%   |
| 5.4.0-33-generic         | 2         | 0.91%   |
| 5.4.0-29-generic         | 2         | 0.91%   |
| 5.3.0-40-generic         | 2         | 0.91%   |
| 5.3.0-29-generic         | 2         | 0.91%   |
| 5.19.0-46-generic        | 2         | 0.91%   |
| 5.19.0-45-generic        | 2         | 0.91%   |
| 5.19.0-42-generic        | 2         | 0.91%   |
| 5.19.0-40-generic        | 2         | 0.91%   |
| 5.19.0-23-generic        | 2         | 0.91%   |
| 5.16.7-desktop-1omv4003  | 2         | 0.91%   |
| 5.15.0-57-generic        | 2         | 0.91%   |
| 5.0.0-23-generic         | 2         | 0.91%   |
| 6.5.9-zen2-1-zen         | 1         | 0.45%   |
| 6.5.9-handcrafted        | 1         | 0.45%   |
| 6.5.5-200.fc38.x86_64    | 1         | 0.45%   |
| 6.5.0-10-generic         | 1         | 0.45%   |
| 6.4.8-desktop-2omv2390   | 1         | 0.45%   |
| 6.4.8-arch1-1            | 1         | 0.45%   |
| 6.4.12-200.fc38.x86_64   | 1         | 0.45%   |
| 6.4.0-0.deb12.2-amd64    | 1         | 0.45%   |
| 6.3.8-200.fc38.x86_64    | 1         | 0.45%   |
| 6.3.1-4-cachyos          | 1         | 0.45%   |
| 6.2.7-060207-generic     | 1         | 0.45%   |
| 6.2.6-76060206-generic   | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 35        | 16.75%  |
| 5.19.0  | 16        | 7.66%   |
| 5.15.0  | 16        | 7.66%   |
| 4.15.0  | 14        | 6.7%    |
| 5.8.0   | 9         | 4.31%   |
| 5.11.0  | 9         | 4.31%   |
| 6.2.0   | 8         | 3.83%   |
| 5.13.0  | 8         | 3.83%   |
| 5.3.0   | 6         | 2.87%   |
| 5.10.0  | 6         | 2.87%   |
| 6.1.0   | 4         | 1.91%   |
| 6.0.12  | 3         | 1.44%   |
| 5.0.0   | 3         | 1.44%   |
| 6.5.9   | 2         | 0.96%   |
| 6.4.8   | 2         | 0.96%   |
| 6.4.7   | 2         | 0.96%   |
| 6.2.10  | 2         | 0.96%   |
| 6.1.1   | 2         | 0.96%   |
| 6.0.6   | 2         | 0.96%   |
| 5.7.14  | 2         | 0.96%   |
| 5.16.7  | 2         | 0.96%   |
| 5.14.0  | 2         | 0.96%   |
| 4.18.0  | 2         | 0.96%   |
| 6.5.5   | 1         | 0.48%   |
| 6.5.0   | 1         | 0.48%   |
| 6.4.12  | 1         | 0.48%   |
| 6.4.0   | 1         | 0.48%   |
| 6.3.8   | 1         | 0.48%   |
| 6.3.1   | 1         | 0.48%   |
| 6.2.7   | 1         | 0.48%   |
| 6.2.6   | 1         | 0.48%   |
| 6.1.9   | 1         | 0.48%   |
| 6.1.8   | 1         | 0.48%   |
| 6.1.6   | 1         | 0.48%   |
| 6.1.24  | 1         | 0.48%   |
| 6.1.12  | 1         | 0.48%   |
| 6.1.11  | 1         | 0.48%   |
| 5.9.3   | 1         | 0.48%   |
| 5.9.16  | 1         | 0.48%   |
| 5.9.11  | 1         | 0.48%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 37        | 17.96%  |
| 5.15    | 21        | 10.19%  |
| 5.19    | 19        | 9.22%   |
| 4.15    | 14        | 6.8%    |
| 6.2     | 12        | 5.83%   |
| 6.1     | 12        | 5.83%   |
| 5.8     | 11        | 5.34%   |
| 5.13    | 9         | 4.37%   |
| 5.11    | 9         | 4.37%   |
| 5.10    | 8         | 3.88%   |
| 6.4     | 6         | 2.91%   |
| 5.3     | 6         | 2.91%   |
| 6.0     | 5         | 2.43%   |
| 5.16    | 5         | 2.43%   |
| 6.5     | 4         | 1.94%   |
| 5.9     | 3         | 1.46%   |
| 5.7     | 3         | 1.46%   |
| 5.14    | 3         | 1.46%   |
| 5.0     | 3         | 1.46%   |
| 4.18    | 3         | 1.46%   |
| 6.3     | 2         | 0.97%   |
| 5.6     | 2         | 0.97%   |
| 5.18    | 2         | 0.97%   |
| 5.17    | 2         | 0.97%   |
| 4.19    | 2         | 0.97%   |
| 5.5     | 1         | 0.49%   |
| 5.12    | 1         | 0.49%   |
| 4.4     | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 193       | 98.47%  |
| i686    | 2         | 1.02%   |
| aarch64 | 1         | 0.51%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 119       | 58.91%  |
| KDE5       | 31        | 15.35%  |
| Unknown    | 22        | 10.89%  |
| X-Cinnamon | 8         | 3.96%   |
| XFCE       | 6         | 2.97%   |
| KDE        | 4         | 1.98%   |
| MATE       | 3         | 1.49%   |
| LXQt       | 2         | 0.99%   |
| wlroots    | 1         | 0.5%    |
| Unity      | 1         | 0.5%    |
| Pantheon   | 1         | 0.5%    |
| DWM        | 1         | 0.5%    |
| Budgie     | 1         | 0.5%    |
| bspwm      | 1         | 0.5%    |
| awesome    | 1         | 0.5%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 132       | 66.33%  |
| Wayland | 52        | 26.13%  |
| Unknown | 13        | 6.53%   |
| Tty     | 2         | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 104       | 52%     |
| GDM3    | 32        | 16%     |
| GDM     | 28        | 14%     |
| SDDM    | 25        | 12.5%   |
| LightDM | 9         | 4.5%    |
| TDM     | 2         | 1%      |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 150       | 75.76%  |
| Unknown | 17        | 8.59%   |
| en_GB   | 11        | 5.56%   |
| C       | 7         | 3.54%   |
| ru_RU   | 3         | 1.52%   |
| en_AU   | 2         | 1.01%   |
| pl_PL   | 1         | 0.51%   |
| hu_HU   | 1         | 0.51%   |
| en_NG   | 1         | 0.51%   |
| en_IN   | 1         | 0.51%   |
| en_AG   | 1         | 0.51%   |
| el_GR   | 1         | 0.51%   |
| de_DE   | 1         | 0.51%   |
| ar_AE   | 1         | 0.51%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 115       | 56.65%  |
| BIOS | 88        | 43.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 146       | 74.49%  |
| Btrfs   | 24        | 12.24%  |
| Overlay | 9         | 4.59%   |
| Tmpfs   | 8         | 4.08%   |
| Xfs     | 6         | 3.06%   |
| Zfs     | 1         | 0.51%   |
| Ext2    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 103       | 52.02%  |
| GPT     | 82        | 41.41%  |
| MBR     | 13        | 6.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 178       | 90.36%  |
| Yes       | 19        | 9.64%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 130       | 65.33%  |
| Yes       | 69        | 34.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 47        | 23.98%  |
| Lenovo                      | 46        | 23.47%  |
| ASUSTek Computer            | 23        | 11.73%  |
| Dell                        | 22        | 11.22%  |
| Toshiba                     | 8         | 4.08%   |
| Gigabyte Technology         | 6         | 3.06%   |
| Valve                       | 5         | 2.55%   |
| Intel                       | 5         | 2.55%   |
| Acer                        | 4         | 2.04%   |
| Notebook                    | 3         | 1.53%   |
| MSI                         | 3         | 1.53%   |
| Google                      | 3         | 1.53%   |
| Apple                       | 3         | 1.53%   |
| Sony                        | 2         | 1.02%   |
| Microsoft                   | 2         | 1.02%   |
| I-Life Digital Technologies | 2         | 1.02%   |
| HUAWEI                      | 2         | 1.02%   |
| YJKC                        | 1         | 0.51%   |
| win element                 | 1         | 0.51%   |
| Razer                       | 1         | 0.51%   |
| Raspberry Pi Foundation     | 1         | 0.51%   |
| LG Electronics              | 1         | 0.51%   |
| ECS                         | 1         | 0.51%   |
| Biostar                     | 1         | 0.51%   |
| AZW                         | 1         | 0.51%   |
| ASRock                      | 1         | 0.51%   |
| A-DATA Technology           | 1         | 0.51%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                  | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Valve Jupiter                                         | 5         | 2.55%   |
| HP All-in-One 22-c0xx                                 | 3         | 1.53%   |
| Lenovo IdeaPadFlex 5 14ALC05 82HU                     | 2         | 1.02%   |
| HP ProBook 450 G2                                     | 2         | 1.02%   |
| HP Pavilion Notebook                                  | 2         | 1.02%   |
| HP Pavilion 15                                        | 2         | 1.02%   |
| HP ENVY Laptop 13-aq0xxx                              | 2         | 1.02%   |
| Dell G5 5587                                          | 2         | 1.02%   |
| ASUS VivoBook_ASUSLaptop X1404VA_X1404VA              | 2         | 1.02%   |
| ASUS All Series                                       | 2         | 1.02%   |
| YJKC vBOOK Plus                                       | 1         | 0.51%   |
| win element MoreFine S500+                            | 1         | 0.51%   |
| Toshiba TECRA X40-D                                   | 1         | 0.51%   |
| Toshiba TECRA A50-C                                   | 1         | 0.51%   |
| Toshiba Satellite L850-B434                           | 1         | 0.51%   |
| Toshiba Satellite L750                                | 1         | 0.51%   |
| Toshiba Satellite C850-A966                           | 1         | 0.51%   |
| Toshiba Satellite C660                                | 1         | 0.51%   |
| Toshiba Satellite A300                                | 1         | 0.51%   |
| Toshiba PORTEGE Z10t-A                                | 1         | 0.51%   |
| Sony VGN-NS10J_S                                      | 1         | 0.51%   |
| Sony SVE14A25CAB                                      | 1         | 0.51%   |
| Razer Blade 15 Advanced Model (Early 2020) - RZ09-033 | 1         | 0.51%   |
| RPi Raspberry Pi 4 Model B Rev 1.1                    | 1         | 0.51%   |
| Notebook PD5x_7xPNP_PNN_PNT                           | 1         | 0.51%   |
| Notebook P95_96_97Ex,Rx                               | 1         | 0.51%   |
| Notebook NV4XMB,ME,MZ                                 | 1         | 0.51%   |
| MSI PS63 Modern 8RD                                   | 1         | 0.51%   |
| MSI MS-7850                                           | 1         | 0.51%   |
| MSI Modern 14 B5M                                     | 1         | 0.51%   |
| Microsoft Surface Pro 4                               | 1         | 0.51%   |
| Microsoft Surface Pro 3                               | 1         | 0.51%   |
| LG C500-G.AEF5BE1                                     | 1         | 0.51%   |
| Lenovo Z50-70 20354                                   | 1         | 0.51%   |
| Lenovo Yoga S730-13IWL 81J0                           | 1         | 0.51%   |
| Lenovo Yoga Creator 7 15IMH05 82DS                    | 1         | 0.51%   |
| Lenovo Yoga 7 15ITL5 82BJ                             | 1         | 0.51%   |
| Lenovo Yoga 2 Pro 20266                               | 1         | 0.51%   |
| Lenovo ThinkPad Yoga 370 20JJS0SA00                   | 1         | 0.51%   |
| Lenovo ThinkPad Yoga 260 20FD000GAD                   | 1         | 0.51%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 22        | 11.22%  |
| HP Pavilion          | 11        | 5.61%   |
| Lenovo IdeaPad       | 9         | 4.59%   |
| HP EliteBook         | 7         | 3.57%   |
| ASUS ROG             | 7         | 3.57%   |
| HP Laptop            | 6         | 3.06%   |
| Dell Latitude        | 6         | 3.06%   |
| Valve Jupiter        | 5         | 2.55%   |
| Toshiba Satellite    | 5         | 2.55%   |
| ASUS VivoBook        | 5         | 2.55%   |
| Lenovo Yoga          | 4         | 2.04%   |
| HP ProBook           | 4         | 2.04%   |
| ASUS PRIME           | 4         | 2.04%   |
| Lenovo IdeaPadFlex   | 3         | 1.53%   |
| HP ENVY              | 3         | 1.53%   |
| HP All-in-One        | 3         | 1.53%   |
| Dell XPS             | 3         | 1.53%   |
| Dell Precision       | 3         | 1.53%   |
| Dell Inspiron        | 3         | 1.53%   |
| Acer Aspire          | 3         | 1.53%   |
| Toshiba TECRA        | 2         | 1.02%   |
| Microsoft Surface    | 2         | 1.02%   |
| Lenovo ThinkCentre   | 2         | 1.02%   |
| I-Life Digital ZED   | 2         | 1.02%   |
| Dell OptiPlex        | 2         | 1.02%   |
| Dell G5              | 2         | 1.02%   |
| ASUS All             | 2         | 1.02%   |
| YJKC vBOOK           | 1         | 0.51%   |
| win element MoreFine | 1         | 0.51%   |
| Toshiba PORTEGE      | 1         | 0.51%   |
| Sony VGN-NS10J       | 1         | 0.51%   |
| Sony SVE14A25CAB     | 1         | 0.51%   |
| Razer Blade          | 1         | 0.51%   |
| RPi Raspberry        | 1         | 0.51%   |
| Notebook PD5x        | 1         | 0.51%   |
| Notebook P95         | 1         | 0.51%   |
| Notebook NV4XMB      | 1         | 0.51%   |
| MSI PS63             | 1         | 0.51%   |
| MSI MS-7850          | 1         | 0.51%   |
| MSI Modern           | 1         | 0.51%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 23        | 11.73%  |
| 2020    | 23        | 11.73%  |
| 2019    | 19        | 9.69%   |
| 2018    | 19        | 9.69%   |
| 2013    | 15        | 7.65%   |
| 2022    | 14        | 7.14%   |
| 2017    | 12        | 6.12%   |
| 2016    | 12        | 6.12%   |
| 2012    | 12        | 6.12%   |
| 2014    | 10        | 5.1%    |
| 2010    | 9         | 4.59%   |
| 2011    | 7         | 3.57%   |
| 2015    | 6         | 3.06%   |
| 2008    | 5         | 2.55%   |
| 2023    | 3         | 1.53%   |
| 2007    | 3         | 1.53%   |
| 2009    | 2         | 1.02%   |
| 2005    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 136       | 69.39%  |
| Desktop        | 36        | 18.37%  |
| Convertible    | 11        | 5.61%   |
| All in one     | 5         | 2.55%   |
| Mini pc        | 4         | 2.04%   |
| Tablet         | 2         | 1.02%   |
| System on chip | 1         | 0.51%   |
| Server         | 1         | 0.51%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 175       | 88.83%  |
| Enabled  | 22        | 11.17%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 193       | 98.47%  |
| Yes  | 3         | 1.53%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 46        | 23.47%  |
| 8.01-16.0       | 40        | 20.41%  |
| 16.01-24.0      | 37        | 18.88%  |
| 3.01-4.0        | 26        | 13.27%  |
| 32.01-64.0      | 20        | 10.2%   |
| 64.01-256.0     | 14        | 7.14%   |
| 24.01-32.0      | 4         | 2.04%   |
| 1.01-2.0        | 3         | 1.53%   |
| 0.51-1.0        | 3         | 1.53%   |
| 2.01-3.0        | 2         | 1.02%   |
| More than 256.0 | 1         | 0.51%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 56        | 26.67%  |
| 2.01-3.0   | 54        | 25.71%  |
| 4.01-8.0   | 49        | 23.33%  |
| 3.01-4.0   | 28        | 13.33%  |
| 8.01-16.0  | 10        | 4.76%   |
| 0.51-1.0   | 7         | 3.33%   |
| 0.01-0.5   | 3         | 1.43%   |
| 16.01-24.0 | 2         | 0.95%   |
| 24.01-32.0 | 1         | 0.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 136       | 68.69%  |
| 2      | 36        | 18.18%  |
| 3      | 12        | 6.06%   |
| 4      | 6         | 3.03%   |
| 9      | 2         | 1.01%   |
| 6      | 2         | 1.01%   |
| 0      | 2         | 1.01%   |
| 8      | 1         | 0.51%   |
| 5      | 1         | 0.51%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 145       | 73.98%  |
| Yes       | 51        | 26.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 73.98%  |
| No        | 51        | 26.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 171       | 86.8%   |
| No        | 26        | 13.2%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 151       | 76.26%  |
| No        | 47        | 23.74%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UAE     | 196       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Dubai            | 96        | 47.76%  |
| Abu Dhabi        | 57        | 28.36%  |
| Sharjah          | 24        | 11.94%  |
| Al Ain City      | 10        | 4.98%   |
| Ajman            | 7         | 3.48%   |
| Al Fujairah City | 4         | 1.99%   |
| Ras al-Khaimah   | 2         | 1%      |
| Al Halah         | 1         | 0.5%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 47        | 69     | 17.41%  |
| WDC                         | 42        | 50     | 15.56%  |
| Seagate                     | 27        | 36     | 10%     |
| Toshiba                     | 23        | 28     | 8.52%   |
| Unknown                     | 14        | 22     | 5.19%   |
| Crucial                     | 14        | 16     | 5.19%   |
| Intel                       | 10        | 12     | 3.7%    |
| HGST                        | 10        | 12     | 3.7%    |
| Sandisk                     | 8         | 9      | 2.96%   |
| Micron Technology           | 8         | 8      | 2.96%   |
| Kingston                    | 6         | 6      | 2.22%   |
| Phison Electronics          | 5         | 5      | 1.85%   |
| SK hynix                    | 4         | 5      | 1.48%   |
| Kingston Technology Company | 4         | 4      | 1.48%   |
| Hitachi                     | 4         | 4      | 1.48%   |
| Silicon Motion              | 3         | 3      | 1.11%   |
| Realtek Semiconductor       | 3         | 4      | 1.11%   |
| Micron/Crucial Technology   | 3         | 3      | 1.11%   |
| Apple                       | 3         | 4      | 1.11%   |
| USB3.0                      | 2         | 2      | 0.74%   |
| Phison                      | 2         | 2      | 0.74%   |
| Lexar                       | 2         | 2      | 0.74%   |
| LaCie                       | 2         | 2      | 0.74%   |
| ADATA Technology            | 2         | 2      | 0.74%   |
| Transcend                   | 1         | 1      | 0.37%   |
| Team                        | 1         | 1      | 0.37%   |
| Super Talent                | 1         | 1      | 0.37%   |
| Pliant                      | 1         | 4      | 0.37%   |
| Patriot                     | 1         | 1      | 0.37%   |
| OCZ                         | 1         | 1      | 0.37%   |
| O2 Micro                    | 1         | 1      | 0.37%   |
| Maxtor                      | 1         | 1      | 0.37%   |
| Lite-On                     | 1         | 1      | 0.37%   |
| Lenovo                      | 1         | 1      | 0.37%   |
| KIOXIA                      | 1         | 4      | 0.37%   |
| KingSpec                    | 1         | 2      | 0.37%   |
| JMicron Technology          | 1         | 1      | 0.37%   |
| Gigabyte Technology         | 1         | 1      | 0.37%   |
| Fujitsu                     | 1         | 1      | 0.37%   |
| External                    | 1         | 1      | 0.37%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| HGST HTS721010A9E630 1TB                              | 5         | 1.74%   |
| Toshiba DT01ACA100 1TB                                | 4         | 1.39%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB                | 4         | 1.39%   |
| Phison E12 NVMe Controller 1TB                        | 4         | 1.39%   |
| HGST HTS725050A7E630 500GB                            | 4         | 1.39%   |
| WDC WD10SPZX-08Z10 1TB                                | 3         | 1.04%   |
| WDC WD10JPCX-24UE4T0 1TB                              | 3         | 1.04%   |
| Unknown SD/MMC/MS PRO 16GB                            | 3         | 1.04%   |
| Toshiba MQ01ABD075 752GB                              | 3         | 1.04%   |
| Seagate ST500LT012-1DG142 500GB                       | 3         | 1.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB     | 3         | 1.04%   |
| Intel NVMe SSD Drive 512GB                            | 3         | 1.04%   |
| Crucial CT500MX500SSD1 500GB                          | 3         | 1.04%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 2         | 0.69%   |
| WDC WD1002FAEX-00Z3A0 1TB                             | 2         | 0.69%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                    | 2         | 0.69%   |
| USB3.0 Super Speed 2TB                                | 2         | 0.69%   |
| Unknown MMC Card  64GB                                | 2         | 0.69%   |
| Unknown MMC Card  32GB                                | 2         | 0.69%   |
| Unknown MMC Card  16GB                                | 2         | 0.69%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB | 2         | 0.69%   |
| Seagate ST500VT000-1DK142 500GB                       | 2         | 0.69%   |
| Seagate ST500LT012-9WS142 500GB                       | 2         | 0.69%   |
| Seagate ST500DM002-1BD142 500GB                       | 2         | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB                        | 2         | 0.69%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 2         | 0.69%   |
| Samsung SSD 980 PRO 2TB                               | 2         | 0.69%   |
| Samsung SSD 970 EVO Plus 500GB                        | 2         | 0.69%   |
| Samsung SSD 970 EVO Plus 1TB                          | 2         | 0.69%   |
| Samsung SSD 860 EVO 500GB                             | 2         | 0.69%   |
| Samsung SSD 850 PRO 1TB                               | 2         | 0.69%   |
| Samsung SSD 850 EVO 250GB                             | 2         | 0.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB    | 2         | 0.69%   |
| Samsung MZVLQ512HALU-000H1 512GB                      | 2         | 0.69%   |
| Samsung MZALQ256HAJD-000L2 256GB                      | 2         | 0.69%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                 | 2         | 0.69%   |
| Micron 2400_MTFDKBA512QFM 512GB                       | 2         | 0.69%   |
| LaCie Mobile SSD 1TB                                  | 2         | 0.69%   |
| Kingston Company SNV2S2000G 2TB                       | 2         | 0.69%   |
| Kingston Company OM3PDP3 NVMe SSD 512GB               | 2         | 0.69%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 30        | 38     | 29.7%   |
| Seagate  | 27        | 36     | 26.73%  |
| Toshiba  | 19        | 24     | 18.81%  |
| HGST     | 10        | 12     | 9.9%    |
| Hitachi  | 4         | 4      | 3.96%   |
| Unknown  | 3         | 6      | 2.97%   |
| USB3.0   | 2         | 2      | 1.98%   |
| Apple    | 2         | 2      | 1.98%   |
| Maxtor   | 1         | 1      | 0.99%   |
| Fujitsu  | 1         | 1      | 0.99%   |
| External | 1         | 1      | 0.99%   |
| ASMT     | 1         | 2      | 0.99%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 17        | 28     | 29.82%  |
| Crucial             | 11        | 13     | 19.3%   |
| WDC                 | 7         | 7      | 12.28%  |
| Kingston            | 3         | 3      | 5.26%   |
| SanDisk             | 2         | 2      | 3.51%   |
| LaCie               | 2         | 2      | 3.51%   |
| Transcend           | 1         | 1      | 1.75%   |
| Toshiba             | 1         | 1      | 1.75%   |
| Team                | 1         | 1      | 1.75%   |
| Super Talent        | 1         | 1      | 1.75%   |
| SK hynix            | 1         | 1      | 1.75%   |
| Patriot             | 1         | 1      | 1.75%   |
| Micron Technology   | 1         | 1      | 1.75%   |
| Lexar               | 1         | 1      | 1.75%   |
| KingSpec            | 1         | 2      | 1.75%   |
| Intel               | 1         | 1      | 1.75%   |
| Gigabyte Technology | 1         | 1      | 1.75%   |
| Corsair             | 1         | 1      | 1.75%   |
| China               | 1         | 1      | 1.75%   |
| Carlstein           | 1         | 1      | 1.75%   |
| Unknown             | 1         | 1      | 1.75%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 95        | 120    | 39.58%  |
| HDD     | 87        | 129    | 36.25%  |
| SSD     | 46        | 71     | 19.17%  |
| MMC     | 11        | 16     | 4.58%   |
| Unknown | 1         | 4      | 0.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 111       | 184    | 48.9%   |
| NVMe | 93        | 118    | 40.97%  |
| SAS  | 12        | 22     | 5.29%   |
| MMC  | 11        | 16     | 4.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 72        | 91     | 50%     |
| 0.51-1.0   | 53        | 73     | 36.81%  |
| 1.01-2.0   | 11        | 19     | 7.64%   |
| 3.01-4.0   | 5         | 13     | 3.47%   |
| 10.01-20.0 | 2         | 3      | 1.39%   |
| 4.01-10.0  | 1         | 1      | 0.69%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 61        | 30.35%  |
| 101-250        | 44        | 21.89%  |
| 501-1000       | 22        | 10.95%  |
| 1001-2000      | 16        | 7.96%   |
| 51-100         | 16        | 7.96%   |
| 21-50          | 14        | 6.97%   |
| 1-20           | 9         | 4.48%   |
| 2001-3000      | 7         | 3.48%   |
| Unknown        | 7         | 3.48%   |
| More than 3000 | 5         | 2.49%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 84        | 39.81%  |
| 21-50          | 48        | 22.75%  |
| 101-250        | 25        | 11.85%  |
| 51-100         | 21        | 9.95%   |
| 251-500        | 12        | 5.69%   |
| 501-1000       | 9         | 4.27%   |
| Unknown        | 7         | 3.32%   |
| 1001-2000      | 3         | 1.42%   |
| More than 3000 | 1         | 0.47%   |
| 2001-3000      | 1         | 0.47%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                   | Computers | Drives | Percent |
|---------------------------------------------------------|-----------|--------|---------|
| WDC WD40PURZ-85TTDY0 4TB                                | 1         | 2      | 10%     |
| WDC WD40EFRX-68WT0N0 4TB                                | 1         | 2      | 10%     |
| WDC WD10JPVX-60JC3T1 1TB                                | 1         | 1      | 10%     |
| WDC WD10EARS-00MVWB0 1TB                                | 1         | 1      | 10%     |
| WDC WD Blue SA510 2.5 500GB                             | 1         | 1      | 10%     |
| Seagate ST500LT012-1DG142 500GB                         | 1         | 1      | 10%     |
| Samsung Electronics MZVLQ256HBJD-00BH1 256GB            | 1         | 1      | 10%     |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 1TB | 1         | 1      | 10%     |
| Micron Technology 1100 SATA 512GB SSD                   | 1         | 1      | 10%     |
| Intel SSDSC2BB480G7 480GB                               | 1         | 1      | 10%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 5         | 7      | 50%     |
| Seagate               | 1         | 1      | 10%     |
| Samsung Electronics   | 1         | 1      | 10%     |
| Realtek Semiconductor | 1         | 1      | 10%     |
| Micron Technology     | 1         | 1      | 10%     |
| Intel                 | 1         | 1      | 10%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 4         | 6      | 80%     |
| Seagate | 1         | 1      | 20%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 4         | 7      | 50%     |
| NVMe | 2         | 2      | 25%     |
| SSD  | 2         | 3      | 25%     |

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
| Detected | 128       | 209    | 61.84%  |
| Works    | 72        | 119    | 34.78%  |
| Malfunc  | 7         | 12     | 3.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 137       | 55.24%  |
| Samsung Electronics          | 33        | 13.31%  |
| SanDisk                      | 10        | 4.03%   |
| AMD                          | 9         | 3.63%   |
| Phison Electronics           | 7         | 2.82%   |
| Micron Technology            | 7         | 2.82%   |
| Kingston Technology Company  | 7         | 2.82%   |
| Micron/Crucial Technology    | 5         | 2.02%   |
| Silicon Motion               | 4         | 1.61%   |
| Toshiba America Info Systems | 3         | 1.21%   |
| SK hynix                     | 3         | 1.21%   |
| Realtek Semiconductor        | 3         | 1.21%   |
| LSI Logic / Symbios Logic    | 3         | 1.21%   |
| ASMedia Technology           | 3         | 1.21%   |
| Broadcom / LSI               | 2         | 0.81%   |
| ADATA Technology             | 2         | 0.81%   |
| VIA Technologies             | 1         | 0.4%    |
| OCZ Technology Group         | 1         | 0.4%    |
| O2 Micro                     | 1         | 0.4%    |
| Nvidia                       | 1         | 0.4%    |
| Marvell Technology Group     | 1         | 0.4%    |
| Lite-On Technology           | 1         | 0.4%    |
| Lenovo                       | 1         | 0.4%    |
| KIOXIA                       | 1         | 0.4%    |
| JMicron Technology           | 1         | 0.4%    |
| Apple                        | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 16        | 5.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 4.44%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 4.07%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 11        | 4.07%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 11        | 4.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 3.7%    |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 3.33%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 2.96%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 2.59%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 6         | 2.22%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2.22%   |
| Phison E12 NVMe Controller                                                     | 6         | 2.22%   |
| Intel SSD 660P Series                                                          | 6         | 2.22%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 1.85%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 5         | 1.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.48%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.48%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 3         | 1.11%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 1.11%   |
| Kingston Company NV2 NVMe SSD SM2267XT                                         | 3         | 1.11%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.11%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.11%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.11%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 3         | 1.11%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 3         | 1.11%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.11%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)            | 2         | 0.74%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 2         | 0.74%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 2         | 0.74%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 2         | 0.74%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 2         | 0.74%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 2         | 0.74%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 0.74%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.74%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 2         | 0.74%   |
| Intel Tiger Lake-LP SATA Controller                                            | 2         | 0.74%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                               | 2         | 0.74%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.74%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.74%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 110       | 44.9%   |
| NVMe | 93        | 37.96%  |
| RAID | 29        | 11.84%  |
| IDE  | 9         | 3.67%   |
| SAS  | 3         | 1.22%   |
| SCSI | 1         | 0.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 169       | 86.22%  |
| AMD    | 26        | 13.27%  |
| ARM    | 1         | 0.51%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz           | 6         | 3.06%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 6         | 3.06%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 2.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 5         | 2.55%   |
| AMD Custom APU 0405                         | 5         | 2.55%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 4         | 2.04%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 2.04%   |
| Intel 12th Gen Core i7-12700H               | 4         | 2.04%   |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 4         | 2.04%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 3         | 1.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 3         | 1.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 1.53%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 1.53%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 3         | 1.53%   |
| Intel Core i5-9400T CPU @ 1.80GHz           | 3         | 1.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.53%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 1.53%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 3         | 1.53%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 3         | 1.53%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 2         | 1.02%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2         | 1.02%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 1.02%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.02%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2         | 1.02%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 1.02%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 1.02%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 2         | 1.02%   |
| Intel Core i5-2450M CPU @ 2.50GHz           | 2         | 1.02%   |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.02%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.02%   |
| Intel 13th Gen Core i7-1355U                | 2         | 1.02%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.02%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 2         | 1.02%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz        | 1         | 0.51%   |
| Intel Xeon E-2286M CPU @ 2.40GHz            | 1         | 0.51%   |
| Intel Xeon CPU E5-2697 v2 @ 2.70GHz         | 1         | 0.51%   |
| Intel Xeon CPU E5-2609 v2 @ 2.50GHz         | 1         | 0.51%   |
| Intel Xeon CPU E3-1265L v3 @ 2.50GHz        | 1         | 0.51%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.51%   |
| Intel Pentium 4 CPU 2.80GHz                 | 1         | 0.51%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 57        | 29.08%  |
| Intel Core i5           | 53        | 27.04%  |
| Other                   | 26        | 13.27%  |
| Intel Core i3           | 9         | 4.59%   |
| AMD Ryzen 5             | 8         | 4.08%   |
| Intel Xeon              | 7         | 3.57%   |
| Intel Celeron           | 6         | 3.06%   |
| Intel Core i9           | 5         | 2.55%   |
| AMD Ryzen 9             | 5         | 2.55%   |
| Intel Core 2 Duo        | 4         | 2.04%   |
| AMD Ryzen 7             | 4         | 2.04%   |
| Intel Atom              | 2         | 1.02%   |
| Intel Xeon Silver       | 1         | 0.51%   |
| Intel Pentium Dual-Core | 1         | 0.51%   |
| Intel Pentium 4         | 1         | 0.51%   |
| Intel Core m5           | 1         | 0.51%   |
| Intel Core 2 Quad       | 1         | 0.51%   |
| Intel Celeron M         | 1         | 0.51%   |
| AMD Sempron             | 1         | 0.51%   |
| AMD Ryzen Threadripper  | 1         | 0.51%   |
| AMD Ryzen 7 PRO         | 1         | 0.51%   |
| AMD A6                  | 1         | 0.51%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 70        | 35.71%  |
| 2       | 66        | 33.67%  |
| 6       | 21        | 10.71%  |
| 8       | 20        | 10.2%   |
| 14      | 5         | 2.55%   |
| 1       | 4         | 2.04%   |
| 16      | 3         | 1.53%   |
| 10      | 3         | 1.53%   |
| 12      | 2         | 1.02%   |
| 24      | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 192       | 97.96%  |
| 2       | 3         | 1.53%   |
| Unknown | 1         | 0.51%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 162       | 82.65%  |
| 1       | 33        | 16.84%  |
| Unknown | 1         | 0.51%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 193       | 98.47%  |
| 32-bit         | 2         | 1.02%   |
| Unknown        | 1         | 0.51%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 66        | 32.51%  |
| 0x306a9    | 10        | 4.93%   |
| 0x406e3    | 9         | 4.43%   |
| 0x906ea    | 8         | 3.94%   |
| 0x806ec    | 8         | 3.94%   |
| 0x806c1    | 8         | 3.94%   |
| 0x40651    | 8         | 3.94%   |
| 0x206a7    | 7         | 3.45%   |
| 0x306c3    | 6         | 2.96%   |
| 0x906e9    | 5         | 2.46%   |
| 0x806ea    | 5         | 2.46%   |
| 0x806e9    | 5         | 2.46%   |
| 0xa0652    | 3         | 1.48%   |
| 0x906ed    | 3         | 1.48%   |
| 0x906a3    | 3         | 1.48%   |
| 0x206c2    | 3         | 1.48%   |
| 0x20655    | 3         | 1.48%   |
| 0x0a50000c | 3         | 1.48%   |
| 0xa0655    | 2         | 0.99%   |
| 0x806eb    | 2         | 0.99%   |
| 0x6fd      | 2         | 0.99%   |
| 0x506e3    | 2         | 0.99%   |
| 0x306f2    | 2         | 0.99%   |
| 0x306d4    | 2         | 0.99%   |
| 0x08608103 | 2         | 0.99%   |
| 0x08108109 | 2         | 0.99%   |
| 0xf29      | 1         | 0.49%   |
| 0xb06a3    | 1         | 0.49%   |
| 0xb0671    | 1         | 0.49%   |
| 0x806d1    | 1         | 0.49%   |
| 0x706a1    | 1         | 0.49%   |
| 0x6fb      | 1         | 0.49%   |
| 0x6e8      | 1         | 0.49%   |
| 0x506c9    | 1         | 0.49%   |
| 0x406c4    | 1         | 0.49%   |
| 0x406c3    | 1         | 0.49%   |
| 0x306e4    | 1         | 0.49%   |
| 0x20652    | 1         | 0.49%   |
| 0x106e5    | 1         | 0.49%   |
| 0x1067a    | 1         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 51        | 26.02%  |
| Haswell          | 22        | 11.22%  |
| Unknown          | 16        | 8.16%   |
| Skylake          | 14        | 7.14%   |
| IvyBridge        | 14        | 7.14%   |
| SandyBridge      | 11        | 5.61%   |
| TigerLake        | 10        | 5.1%    |
| Westmere         | 8         | 4.08%   |
| CometLake        | 8         | 4.08%   |
| Zen 3            | 6         | 3.06%   |
| Broadwell        | 5         | 2.55%   |
| Alderlake Hybrid | 5         | 2.55%   |
| Zen+             | 3         | 1.53%   |
| Zen 2            | 3         | 1.53%   |
| Silvermont       | 3         | 1.53%   |
| Penryn           | 3         | 1.53%   |
| Core             | 3         | 1.53%   |
| Icelake          | 2         | 1.02%   |
| Goldmont plus    | 2         | 1.02%   |
| Zen              | 1         | 0.51%   |
| Piledriver       | 1         | 0.51%   |
| P6               | 1         | 0.51%   |
| NetBurst         | 1         | 0.51%   |
| Nehalem          | 1         | 0.51%   |
| K8 Hammer        | 1         | 0.51%   |
| Goldmont         | 1         | 0.51%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 138       | 52.27%  |
| Nvidia                     | 81        | 30.68%  |
| AMD                        | 43        | 16.29%  |
| Matrox Electronics Systems | 1         | 0.38%   |
| ASPEED Technology          | 1         | 0.38%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 4.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 12        | 4.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 3.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 9         | 3.4%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 3.02%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 3.02%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.64%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.26%   |
| Intel HD Graphics 620                                                                    | 6         | 2.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.26%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 2.26%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.89%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.89%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 5         | 1.89%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 5         | 1.89%   |
| Nvidia GM108M [GeForce MX130]                                                            | 4         | 1.51%   |
| Nvidia GM108M [GeForce MX110]                                                            | 4         | 1.51%   |
| Intel HD Graphics 630                                                                    | 4         | 1.51%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.51%   |
| AMD Lucienne                                                                             | 4         | 1.51%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.13%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 1.13%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 3         | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.13%   |
| Intel HD Graphics 530                                                                    | 3         | 1.13%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.13%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.13%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.13%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.13%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3         | 1.13%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.75%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 0.75%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.75%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.75%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.75%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.75%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 2         | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 74        | 37.76%  |
| Intel + Nvidia     | 50        | 25.51%  |
| 1 x Nvidia         | 25        | 12.76%  |
| 1 x AMD            | 25        | 12.76%  |
| Intel + AMD        | 13        | 6.63%   |
| AMD + Nvidia       | 5         | 2.55%   |
| Other              | 1         | 0.51%   |
| 1 x Matrox         | 1         | 0.51%   |
| Intel + 2 x Nvidia | 1         | 0.51%   |
| 1 x ASPEED         | 1         | 0.51%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 150       | 76.14%  |
| Proprietary | 38        | 19.29%  |
| Unknown     | 9         | 4.57%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 122       | 61.62%  |
| 1.01-2.0   | 26        | 13.13%  |
| 3.01-4.0   | 14        | 7.07%   |
| 0.01-0.5   | 14        | 7.07%   |
| 7.01-8.0   | 6         | 3.03%   |
| 0.51-1.0   | 6         | 3.03%   |
| 5.01-6.0   | 4         | 2.02%   |
| 2.01-3.0   | 2         | 1.01%   |
| 8.01-16.0  | 2         | 1.01%   |
| 4.01-5.0   | 1         | 0.51%   |
| 16.01-24.0 | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 29        | 13.88%  |
| BOE                     | 28        | 13.4%   |
| Chimei Innolux          | 24        | 11.48%  |
| Samsung Electronics     | 23        | 11%     |
| LG Display              | 23        | 11%     |
| Hewlett-Packard         | 10        | 4.78%   |
| Goldstar                | 10        | 4.78%   |
| Dell                    | 6         | 2.87%   |
| BenQ                    | 6         | 2.87%   |
| Valve                   | 4         | 1.91%   |
| Lenovo                  | 4         | 1.91%   |
| CSO                     | 4         | 1.91%   |
| Ancor Communications    | 4         | 1.91%   |
| Sharp                   | 3         | 1.44%   |
| InfoVision              | 3         | 1.44%   |
| ASUSTek Computer        | 3         | 1.44%   |
| Apple                   | 3         | 1.44%   |
| ViewSonic               | 2         | 0.96%   |
| Philips                 | 2         | 0.96%   |
| LGD                     | 2         | 0.96%   |
| LG Philips              | 2         | 0.96%   |
| Chi Mei Optoelectronics | 2         | 0.96%   |
| Sony                    | 1         | 0.48%   |
| Seiko/Epson             | 1         | 0.48%   |
| RTK                     | 1         | 0.48%   |
| Panasonic               | 1         | 0.48%   |
| Mi                      | 1         | 0.48%   |
| LG Electronics          | 1         | 0.48%   |
| Hitachi                 | 1         | 0.48%   |
| Gigabyte Technology     | 1         | 0.48%   |
| CTX                     | 1         | 0.48%   |
| CMN                     | 1         | 0.48%   |
| AOC                     | 1         | 0.48%   |
| Analogix                | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 4         | 1.89%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 4         | 1.89%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 3         | 1.42%   |
| Hewlett-Packard ALL-in-One HPN401F 1920x1080 476x268mm 21.5-inch        | 3         | 1.42%   |
| ASUSTek Computer PG32UQ AUS32E1 3840x2160 708x399mm 32.0-inch           | 3         | 1.42%   |
| LGD LCD Monitor 1366x768                                                | 2         | 0.94%   |
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch            | 2         | 0.94%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 0.94%   |
| CSO LCD Monitor CSO1603 2560x1600 344x215mm 16.0-inch                   | 2         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 2         | 0.94%   |
| BOE LCD Monitor BOE06B3 1920x1080                                       | 2         | 0.94%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 2         | 0.94%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO272B 3840x2160 293x165mm 13.2-inch          | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch          | 2         | 0.94%   |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch          | 2         | 0.94%   |
| ViewSonic VG2439 Series VSCD22B 1920x1080 521x293mm 23.5-inch           | 1         | 0.47%   |
| ViewSonic VA1918wm VSCC821 1440x900 410x256mm 19.0-inch                 | 1         | 0.47%   |
| Sony onn. TV SNY050A 1920x1080 930x520mm 41.9-inch                      | 1         | 0.47%   |
| Sharp LCD Monitor SHP14BA 1920x1080 340x190mm 15.3-inch                 | 1         | 0.47%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 0.47%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                 | 1         | 0.47%   |
| Seiko/Epson LCD Monitor 1280x800                                        | 1         | 0.47%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch       | 1         | 0.47%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.47%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5741 1280x800 261x163mm 12.1-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch   | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch   | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4341 1366x768 344x194mm 15.5-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch   | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch   | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC4157 3840x2160 344x194mm 15.5-inch   | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch   | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 94        | 46.77%  |
| 1366x768 (WXGA)   | 47        | 23.38%  |
| 3840x2160 (4K)    | 18        | 8.96%   |
| 2560x1440 (QHD)   | 7         | 3.48%   |
| 800x1280          | 5         | 2.49%   |
| 1920x1200 (WUXGA) | 5         | 2.49%   |
| 1600x900 (HD+)    | 4         | 1.99%   |
| 1280x800 (WXGA)   | 4         | 1.99%   |
| 2560x1600         | 3         | 1.49%   |
| 2560x1080         | 3         | 1.49%   |
| 2880x1800         | 2         | 1%      |
| 2160x1440         | 2         | 1%      |
| 1440x900 (WXGA+)  | 2         | 1%      |
| 3440x1440         | 1         | 0.5%    |
| 3200x1800 (QHD+)  | 1         | 0.5%    |
| 2880x1920         | 1         | 0.5%    |
| 2736x1824         | 1         | 0.5%    |
| 2304x1440         | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 56        | 26.79%  |
| 14      | 29        | 13.88%  |
| 13      | 28        | 13.4%   |
| 21      | 12        | 5.74%   |
| 24      | 10        | 4.78%   |
| 23      | 9         | 4.31%   |
| 27      | 8         | 3.83%   |
| 12      | 8         | 3.83%   |
| Unknown | 6         | 2.87%   |
| 16      | 5         | 2.39%   |
| 11      | 5         | 2.39%   |
| 31      | 4         | 1.91%   |
| 7       | 4         | 1.91%   |
| 84      | 3         | 1.44%   |
| 32      | 3         | 1.44%   |
| 19      | 3         | 1.44%   |
| 34      | 2         | 0.96%   |
| 18      | 2         | 0.96%   |
| 17      | 2         | 0.96%   |
| 65      | 1         | 0.48%   |
| 54      | 1         | 0.48%   |
| 52      | 1         | 0.48%   |
| 46      | 1         | 0.48%   |
| 42      | 1         | 0.48%   |
| 41      | 1         | 0.48%   |
| 40      | 1         | 0.48%   |
| 28      | 1         | 0.48%   |
| 20      | 1         | 0.48%   |
| 3       | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 102       | 49.28%  |
| 201-300     | 27        | 13.04%  |
| 501-600     | 26        | 12.56%  |
| 401-500     | 17        | 8.21%   |
| 601-700     | 6         | 2.9%    |
| Unknown     | 6         | 2.9%    |
| 701-800     | 5         | 2.42%   |
| 1-100       | 5         | 2.42%   |
| 351-400     | 4         | 1.93%   |
| 1501-2000   | 3         | 1.45%   |
| 1001-1500   | 3         | 1.45%   |
| 901-1000    | 2         | 0.97%   |
| 801-900     | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 155       | 82.45%  |
| 16/10   | 17        | 9.04%   |
| Unknown | 6         | 3.19%   |
| 0.67    | 4         | 2.13%   |
| 21/9    | 3         | 1.6%    |
| 3/2     | 2         | 1.06%   |
| 6/5     | 1         | 0.53%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 56        | 26.79%  |
| 81-90          | 43        | 20.57%  |
| 201-250        | 21        | 10.05%  |
| 71-80          | 13        | 6.22%   |
| 151-200        | 10        | 4.78%   |
| 351-500        | 9         | 4.31%   |
| 61-70          | 8         | 3.83%   |
| 301-350        | 8         | 3.83%   |
| More than 1000 | 6         | 2.87%   |
| Unknown        | 6         | 2.87%   |
| 51-60          | 5         | 2.39%   |
| 1-40           | 5         | 2.39%   |
| 251-300        | 5         | 2.39%   |
| 111-120        | 5         | 2.39%   |
| 501-1000       | 4         | 1.91%   |
| 141-150        | 2         | 0.96%   |
| 121-130        | 2         | 0.96%   |
| 91-100         | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 71        | 34.63%  |
| 101-120       | 48        | 23.41%  |
| 51-100        | 42        | 20.49%  |
| 161-240       | 25        | 12.2%   |
| More than 240 | 10        | 4.88%   |
| Unknown       | 6         | 2.93%   |
| 1-50          | 3         | 1.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 154       | 77%     |
| 2     | 29        | 14.5%   |
| 0     | 13        | 6.5%    |
| 3     | 4         | 2%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 117       | 40.91%  |
| Realtek Semiconductor    | 92        | 32.17%  |
| Qualcomm Atheros         | 22        | 7.69%   |
| Broadcom                 | 15        | 5.24%   |
| TP-Link                  | 6         | 2.1%    |
| MediaTek                 | 6         | 2.1%    |
| Ralink                   | 5         | 1.75%   |
| Marvell Technology Group | 5         | 1.75%   |
| Xiaomi                   | 3         | 1.05%   |
| ASIX Electronics         | 3         | 1.05%   |
| Sigma Designs            | 2         | 0.7%    |
| Wilocity                 | 1         | 0.35%   |
| VIA Technologies         | 1         | 0.35%   |
| SILICON Laboratories     | 1         | 0.35%   |
| Sierra Wireless          | 1         | 0.35%   |
| Ralink Technology        | 1         | 0.35%   |
| Nvidia                   | 1         | 0.35%   |
| Lenovo                   | 1         | 0.35%   |
| D-Link                   | 1         | 0.35%   |
| Broadcom Limited         | 1         | 0.35%   |
| Aquantia                 | 1         | 0.35%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 15.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 4.39%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 2.92%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 2.63%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 2.34%   |
| Intel Wireless 8265 / 8275                                        | 7         | 2.05%   |
| Intel Wireless 7260                                               | 7         | 2.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 7         | 2.05%   |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 1.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.75%   |
| Intel Wireless 8260                                               | 6         | 1.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 1.46%   |
| Intel Wireless 7265                                               | 5         | 1.46%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 5         | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.17%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.17%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.17%   |
| Intel I210 Gigabit Network Connection                             | 4         | 1.17%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 1.17%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 0.88%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 3         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 3         | 0.88%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.88%   |
| Intel Wireless 3165                                               | 3         | 0.88%   |
| Intel Ethernet Controller I225-V                                  | 3         | 0.88%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 0.88%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 0.88%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 0.88%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.88%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 2         | 0.58%   |
| Sigma Designs Aeotec Z-Stick Gen5 (ZW090) - UZB                   | 2         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 96        | 53.63%  |
| Realtek Semiconductor    | 32        | 17.88%  |
| Qualcomm Atheros         | 17        | 9.5%    |
| Broadcom                 | 10        | 5.59%   |
| TP-Link                  | 6         | 3.35%   |
| MediaTek                 | 6         | 3.35%   |
| Ralink                   | 5         | 2.79%   |
| Marvell Technology Group | 2         | 1.12%   |
| Wilocity                 | 1         | 0.56%   |
| Sierra Wireless          | 1         | 0.56%   |
| Ralink Technology        | 1         | 0.56%   |
| D-Link                   | 1         | 0.56%   |
| Broadcom Limited         | 1         | 0.56%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 5.59%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 5.03%   |
| Intel Wireless 8265 / 8275                                     | 7         | 3.91%   |
| Intel Wireless 7260                                            | 7         | 3.91%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 7         | 3.91%   |
| Intel Wi-Fi 6 AX200                                            | 7         | 3.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 3.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 6         | 3.35%   |
| Intel Wireless 8260                                            | 6         | 3.35%   |
| Intel Wireless 7265                                            | 5         | 2.79%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 5         | 2.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 2.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 2.23%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 4         | 2.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 2.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 2.23%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 3         | 1.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 1.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 1.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 3         | 1.68%   |
| Intel Wireless 3165                                            | 3         | 1.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 2         | 1.12%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 1.12%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 1.12%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.12%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 2         | 1.12%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 2         | 1.12%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless              | 2         | 1.12%   |
| Intel Wireless-AC 9260                                         | 2         | 1.12%   |
| Intel Wireless 3160                                            | 2         | 1.12%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 1.12%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.12%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.12%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter   | 2         | 1.12%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.12%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter             | 1         | 0.56%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 76        | 50.67%  |
| Intel                    | 49        | 32.67%  |
| Qualcomm Atheros         | 6         | 4%      |
| Broadcom                 | 6         | 4%      |
| Xiaomi                   | 3         | 2%      |
| Marvell Technology Group | 3         | 2%      |
| ASIX Electronics         | 3         | 2%      |
| VIA Technologies         | 1         | 0.67%   |
| Nvidia                   | 1         | 0.67%   |
| Lenovo                   | 1         | 0.67%   |
| Aquantia                 | 1         | 0.67%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 52        | 32.5%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 9.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 5%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 5         | 3.13%   |
| Intel I210 Gigabit Network Connection                             | 4         | 2.5%    |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 3         | 1.88%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.88%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.88%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.88%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.88%   |
| Intel Ethernet Connection (4) I219-V                              | 3         | 1.88%   |
| Intel 82579V Gigabit Network Connection                           | 3         | 1.88%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.88%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.25%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.25%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.25%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.25%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.25%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.25%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.63%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 0.63%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.63%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.63%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.63%   |
| Marvell Group 88E8070 based Ethernet Controller                   | 1         | 0.63%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.63%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.63%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.63%   |
| Intel Ethernet Controller I226-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.63%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.63%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.63%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 170       | 53.63%  |
| Ethernet | 144       | 45.43%  |
| Modem    | 3         | 0.95%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 138       | 70.41%  |
| Ethernet | 58        | 29.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 111       | 56.63%  |
| 1     | 76        | 38.78%  |
| 3     | 4         | 2.04%   |
| 0     | 3         | 1.53%   |
| 8     | 1         | 0.51%   |
| 4     | 1         | 0.51%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 147       | 74.62%  |
| Yes  | 50        | 25.38%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 80        | 52.98%  |
| Realtek Semiconductor           | 18        | 11.92%  |
| Qualcomm Atheros Communications | 9         | 5.96%   |
| IMC Networks                    | 7         | 4.64%   |
| Cambridge Silicon Radio         | 5         | 3.31%   |
| Toshiba                         | 4         | 2.65%   |
| Ralink                          | 4         | 2.65%   |
| Foxconn / Hon Hai               | 4         | 2.65%   |
| Broadcom                        | 4         | 2.65%   |
| ASUSTek Computer                | 4         | 2.65%   |
| MediaTek                        | 3         | 1.99%   |
| Marvell Semiconductor           | 2         | 1.32%   |
| Hewlett-Packard                 | 2         | 1.32%   |
| Dell                            | 2         | 1.32%   |
| Apple                           | 2         | 1.32%   |
| Lite-On Technology              | 1         | 0.66%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 25        | 16.56%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 19        | 12.58%  |
| Intel AX201 Bluetooth                                 | 15        | 9.93%   |
| Realtek Bluetooth Radio                               | 11        | 7.28%   |
| Intel AX200 Bluetooth                                 | 7         | 4.64%   |
| Intel AX210 Bluetooth                                 | 6         | 3.97%   |
| IMC Networks Bluetooth Radio                          | 5         | 3.31%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 5         | 3.31%   |
| Realtek  Bluetooth 4.2 Adapter                        | 4         | 2.65%   |
| Ralink RT3290 Bluetooth                               | 4         | 2.65%   |
| Qualcomm Atheros  Bluetooth Device                    | 3         | 1.99%   |
| MediaTek Wireless_Device                              | 3         | 1.99%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 1.99%   |
| Intel Bluetooth Device                                | 3         | 1.99%   |
| Toshiba Bluetooth USB Host Controller                 | 2         | 1.32%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 2         | 1.32%   |
| Qualcomm Atheros AR3011 Bluetooth                     | 2         | 1.32%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 2         | 1.32%   |
| IMC Networks Wireless_Device                          | 2         | 1.32%   |
| HP Broadcom 2070 Bluetooth Combo                      | 2         | 1.32%   |
| Foxconn / Hon Hai Bluetooth Device                    | 2         | 1.32%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2         | 1.32%   |
| Toshiba RT Bluetooth Radio                            | 1         | 0.66%   |
| Toshiba Integrated Bluetooth HCI                      | 1         | 0.66%   |
| Realtek RTL8821A Bluetooth                            | 1         | 0.66%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 0.66%   |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1         | 0.66%   |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.66%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 1         | 0.66%   |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 0.66%   |
| Marvell Bluetooth and Wireless LAN Composite          | 1         | 0.66%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1         | 0.66%   |
| Foxconn / Hon Hai Wireless_Device                     | 1         | 0.66%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 0.66%   |
| Dell DW375 Bluetooth Module                           | 1         | 0.66%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.66%   |
| Broadcom HP Portable SoftSailing                      | 1         | 0.66%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1         | 0.66%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 1         | 0.66%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]      | 1         | 0.66%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 166       | 62.88%  |
| Nvidia                | 48        | 18.18%  |
| AMD                   | 31        | 11.74%  |
| Logitech              | 3         | 1.14%   |
| JMTek                 | 3         | 1.14%   |
| ASUSTek Computer      | 3         | 1.14%   |
| SteelSeries ApS       | 2         | 0.76%   |
| Lenovo                | 2         | 0.76%   |
| Solid State Logic     | 1         | 0.38%   |
| Samsung Electronics   | 1         | 0.38%   |
| Realtek Semiconductor | 1         | 0.38%   |
| Griffin Technology    | 1         | 0.38%   |
| Dell                  | 1         | 0.38%   |
| Apogee Electronics    | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 21        | 6.95%   |
| AMD Family 17h/19h HD Audio Controller                                     | 16        | 5.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 14        | 4.64%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 4.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 4.3%    |
| Intel 8 Series HD Audio Controller                                         | 13        | 4.3%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 12        | 3.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 12        | 3.97%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 2.98%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 2.32%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 7         | 2.32%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 1.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 1.99%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.66%   |
| Nvidia GP106 High Definition Audio Controller                              | 5         | 1.66%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.66%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.66%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 5         | 1.66%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5         | 1.66%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.32%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.32%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.32%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.32%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.32%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.99%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 0.99%   |
| Nvidia GA106 High Definition Audio Controller                              | 3         | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 0.99%   |
| ASUSTek Computer USB Audio                                                 | 3         | 0.99%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.66%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.66%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.66%   |
| Nvidia Audio device                                                        | 2         | 0.66%   |
| JMTek USB PnP Audio Device                                                 | 2         | 0.66%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 2         | 0.66%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.66%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 36        | 32.73%  |
| SK hynix            | 20        | 18.18%  |
| Micron Technology   | 18        | 16.36%  |
| Crucial             | 10        | 9.09%   |
| Kingston            | 8         | 7.27%   |
| Corsair             | 7         | 6.36%   |
| Ramaxel Technology  | 4         | 3.64%   |
| Unknown             | 3         | 2.73%   |
| Wilk                | 1         | 0.91%   |
| Timetec             | 1         | 0.91%   |
| Gold Key            | 1         | 0.91%   |
| 4ea5                | 1         | 0.91%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 3         | 2.56%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 3         | 2.56%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.71%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 2         | 1.71%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 2         | 1.71%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.71%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 1.71%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 2         | 1.71%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s      | 2         | 1.71%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s         | 2         | 1.71%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s    | 2         | 1.71%   |
| Wilk RAM W-HK32S32O 32GB SODIMM DDR4 3200MT/s                | 1         | 0.85%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 1         | 0.85%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s               | 1         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 1         | 0.85%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 1         | 0.85%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s                | 1         | 0.85%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s         | 1         | 0.85%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                 | 1         | 0.85%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 1         | 0.85%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s         | 1         | 0.85%   |
| SK hynix RAM HMT125S6TFR8C-G7 2GB SODIMM DDR3 1067MT/s       | 1         | 0.85%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s       | 1         | 0.85%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s      | 1         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s       | 1         | 0.85%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 0.85%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 0.85%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 1         | 0.85%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s      | 1         | 0.85%   |
| SK hynix RAM HMA82GR7JJR8N-WM 16384MB DIMM DDR4 2933MT/s     | 1         | 0.85%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 1         | 0.85%   |
| SK hynix RAM H5ANAG6NCMR-XNC 8GB Row Of Chips DDR4 3200MT/s  | 1         | 0.85%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s       | 1         | 0.85%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                 | 1         | 0.85%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s        | 1         | 0.85%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s        | 1         | 0.85%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 1         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s  | 1         | 0.85%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 1         | 0.85%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 58        | 65.17%  |
| DDR3    | 19        | 21.35%  |
| LPDDR3  | 4         | 4.49%   |
| DDR5    | 3         | 3.37%   |
| LPDDR4  | 2         | 2.25%   |
| DDR2    | 2         | 2.25%   |
| Unknown | 1         | 1.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 60        | 65.22%  |
| DIMM         | 17        | 18.48%  |
| Row Of Chips | 13        | 14.13%  |
| Chip         | 1         | 1.09%   |
| Unknown      | 1         | 1.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 49        | 47.57%  |
| 16384 | 22        | 21.36%  |
| 4096  | 18        | 17.48%  |
| 32768 | 6         | 5.83%   |
| 2048  | 6         | 5.83%   |
| 65536 | 1         | 0.97%   |
| 1024  | 1         | 0.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 28        | 28.28%  |
| 2667  | 22        | 22.22%  |
| 1600  | 11        | 11.11%  |
| 2400  | 7         | 7.07%   |
| 2133  | 7         | 7.07%   |
| 1333  | 4         | 4.04%   |
| 4800  | 3         | 3.03%   |
| 3400  | 2         | 2.02%   |
| 3000  | 2         | 2.02%   |
| 1867  | 2         | 2.02%   |
| 1334  | 2         | 2.02%   |
| 6400  | 1         | 1.01%   |
| 4267  | 1         | 1.01%   |
| 3733  | 1         | 1.01%   |
| 3466  | 1         | 1.01%   |
| 2933  | 1         | 1.01%   |
| 1866  | 1         | 1.01%   |
| 1067  | 1         | 1.01%   |
| 800   | 1         | 1.01%   |
| 667   | 1         | 1.01%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Canon              | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| HP Deskjet F2280 series   | 1         | 25%     |
| HP DeskJet 2300 series    | 1         | 25%     |
| Canon PIXMA MG3600 Series | 1         | 25%     |
| Brother MFC-9330CDW       | 1         | 25%     |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 41        | 26.45%  |
| IMC Networks                           | 19        | 12.26%  |
| Cheng Uei Precision Industry (Foxlink) | 11        | 7.1%    |
| Bison Electronics                      | 10        | 6.45%   |
| Realtek Semiconductor                  | 8         | 5.16%   |
| Microdia                               | 8         | 5.16%   |
| Syntek                                 | 7         | 4.52%   |
| Luxvisions Innotech Limited            | 7         | 4.52%   |
| Sunplus Innovation Technology          | 6         | 3.87%   |
| Apple                                  | 6         | 3.87%   |
| Lite-On Technology                     | 4         | 2.58%   |
| Samsung Electronics                    | 3         | 1.94%   |
| Ricoh                                  | 3         | 1.94%   |
| Quanta                                 | 3         | 1.94%   |
| Microsoft                              | 3         | 1.94%   |
| Alcor Micro                            | 3         | 1.94%   |
| Suyin                                  | 2         | 1.29%   |
| Logitech                               | 2         | 1.29%   |
| Creative Technology                    | 2         | 1.29%   |
| Acer                                   | 2         | 1.29%   |
| Ruision                                | 1         | 0.65%   |
| LG Electronics                         | 1         | 0.65%   |
| Lenovo                                 | 1         | 0.65%   |
| KYE Systems (Mouse Systems)            | 1         | 0.65%   |
| Google                                 | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 13        | 8.33%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 8         | 5.13%   |
| Syntek Integrated Camera                                        | 6         | 3.85%   |
| IMC Networks Integrated Camera                                  | 5         | 3.21%   |
| Microdia Integrated_Webcam_HD                                   | 4         | 2.56%   |
| Chicony Integrated Camera (1280x720@30)                         | 4         | 2.56%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 4         | 2.56%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 3         | 1.92%   |
| Realtek Integrated_Webcam_HD                                    | 3         | 1.92%   |
| Lite-On HP Wide Vision HD Camera                                | 3         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 3         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 3         | 1.92%   |
| Sunplus Integrated_Webcam_HD                                    | 2         | 1.28%   |
| Sunplus HP HD Webcam [Fixed]                                    | 2         | 1.28%   |
| Ricoh HD Webcam                                                 | 2         | 1.28%   |
| Realtek HP Truevision HD                                        | 2         | 1.28%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 1.28%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 2         | 1.28%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 2         | 1.28%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 2         | 1.28%   |
| Logitech Webcam C270                                            | 2         | 1.28%   |
| Chicony TOSHIBA Web Camera - HD                                 | 2         | 1.28%   |
| Chicony TOSHIBA Web Camera - FHD                                | 2         | 1.28%   |
| Chicony Lenovo EasyCamera                                       | 2         | 1.28%   |
| Chicony HP Truevision HD                                        | 2         | 1.28%   |
| Chicony HP HD Webcam [Fixed]                                    | 2         | 1.28%   |
| Chicony HP HD Webcam                                            | 2         | 1.28%   |
| Chicony HD WebCam                                               | 2         | 1.28%   |
| Chicony EasyCamera                                              | 2         | 1.28%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 2         | 1.28%   |
| Bison Lenovo EasyCamera                                         | 2         | 1.28%   |
| Bison Integrated Camera                                         | 2         | 1.28%   |
| Bison BisonCam,NB Pro                                           | 2         | 1.28%   |
| Alcor Micro USB 2.0 Camera                                      | 2         | 1.28%   |
| Syntek EasyCamera                                               | 1         | 0.64%   |
| Suyin HP TrueVision HD                                          | 1         | 0.64%   |
| Suyin 1.3M HD WebCam                                            | 1         | 0.64%   |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 0.64%   |
| Sunplus Integrated Webcam                                       | 1         | 0.64%   |
| Ruision UVC Camera                                              | 1         | 0.64%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 19        | 40.43%  |
| Validity Sensors                   | 16        | 34.04%  |
| Elan Microelectronics              | 5         | 10.64%  |
| Shenzhen Goodix Technology         | 3         | 6.38%   |
| STMicroelectronics                 | 2         | 4.26%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.13%   |
| LighTuning Technology              | 1         | 2.13%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                                | 5         | 10.64%  |
| Validity Sensors Synaptics WBDI                                 | 4         | 8.51%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 4         | 8.51%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 6.38%   |
| Synaptics UWP WBDI                                              | 3         | 6.38%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 3         | 6.38%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 2         | 4.26%   |
| Validity Sensors VFS491                                         | 2         | 4.26%   |
| Synaptics WBDI                                                  | 2         | 4.26%   |
| Synaptics UWP WBDI Device                                       | 2         | 4.26%   |
| STMicroelectronics Fingerprint Reader                           | 2         | 4.26%   |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 4.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 2.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 2.13%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 2.13%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 2.13%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.13%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 1         | 2.13%   |
| Synaptics TouchPad                                              | 1         | 2.13%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 2.13%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 2.13%   |
| Synaptics Fingerprint reader [HP G6]                            | 1         | 2.13%   |
| Shenzhen Goodix  Fingerprint Device                             | 1         | 2.13%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.13%   |
| LighTuning Fingerprint Sensor                                   | 1         | 2.13%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 37.5%   |
| Alcor Micro | 3         | 37.5%   |
| Upek        | 1         | 12.5%   |
| Aktiv       | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 37.5%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Aktiv Rutoken lite                                                           | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 100       | 49.75%  |
| 1     | 74        | 36.82%  |
| 2     | 22        | 10.95%  |
| 3     | 5         | 2.49%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 46        | 36.51%  |
| Graphics card            | 27        | 21.43%  |
| Net/wireless             | 15        | 11.9%   |
| Camera                   | 8         | 6.35%   |
| Chipcard                 | 7         | 5.56%   |
| Multimedia controller    | 5         | 3.97%   |
| Communication controller | 5         | 3.97%   |
| Bluetooth                | 4         | 3.17%   |
| Unassigned class         | 3         | 2.38%   |
| Sound                    | 3         | 2.38%   |
| Wireless                 | 2         | 1.59%   |
| Modem                    | 1         | 0.79%   |

