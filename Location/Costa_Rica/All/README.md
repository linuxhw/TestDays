Linux in Costa Rica - Tested Hardware & Statistics
--------------------------------------------------

A project to collect tested hardware configurations for Linux in Costa Rica.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Costa_Rica/Desktop/README.md) and [notebooks](/Location/Costa_Rica/Notebook/README.md).

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

Total: 329

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Inspiron 7506 2n1           | Convertible | [3479df4ab9](https://linux-hardware.org/?probe=3479df4ab9) | Feb 26, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [b02e34a7f9](https://linux-hardware.org/?probe=b02e34a7f9) | Feb 25, 2023 |
| MSI           | 970A GAMING PRO CARBON      | Desktop     | [0649eea8a9](https://linux-hardware.org/?probe=0649eea8a9) | Feb 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [d6fea43eb5](https://linux-hardware.org/?probe=d6fea43eb5) | Feb 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [6707aef886](https://linux-hardware.org/?probe=6707aef886) | Feb 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [21335c1268](https://linux-hardware.org/?probe=21335c1268) | Feb 23, 2023 |
| Intel         | NUC12WSBi7 M46422-303       | Mini pc     | [1942c9f528](https://linux-hardware.org/?probe=1942c9f528) | Feb 11, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [dcecd700f9](https://linux-hardware.org/?probe=dcecd700f9) | Feb 10, 2023 |
| Raspberry ... | Raspberry Pi Model B Rev... | Soc         | [4995c8c687](https://linux-hardware.org/?probe=4995c8c687) | Feb 06, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ae644e258a](https://linux-hardware.org/?probe=ae644e258a) | Jan 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cc2d26e52e](https://linux-hardware.org/?probe=cc2d26e52e) | Jan 22, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [8761a4096a](https://linux-hardware.org/?probe=8761a4096a) | Jan 22, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [7099ccff2f](https://linux-hardware.org/?probe=7099ccff2f) | Jan 22, 2023 |
| Dell          | 0D28YY A00                  | Desktop     | [394be1956b](https://linux-hardware.org/?probe=394be1956b) | Jan 22, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f33868aba0](https://linux-hardware.org/?probe=f33868aba0) | Jan 15, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [927415e3d5](https://linux-hardware.org/?probe=927415e3d5) | Jan 07, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [46ea5b81b7](https://linux-hardware.org/?probe=46ea5b81b7) | Jan 07, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [f5ff2f8568](https://linux-hardware.org/?probe=f5ff2f8568) | Jan 06, 2023 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [e6028c8640](https://linux-hardware.org/?probe=e6028c8640) | Jan 04, 2023 |
| Jumper        | EZpad                       | Tablet      | [cfa761d534](https://linux-hardware.org/?probe=cfa761d534) | Jan 03, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [b1a7532cf1](https://linux-hardware.org/?probe=b1a7532cf1) | Dec 23, 2022 |
| ZOTAC         | NM10                        | Desktop     | [98b6981431](https://linux-hardware.org/?probe=98b6981431) | Dec 21, 2022 |
| Gigabyte      | B150-HD3-CF                 | Desktop     | [173dde2177](https://linux-hardware.org/?probe=173dde2177) | Dec 14, 2022 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [485240a680](https://linux-hardware.org/?probe=485240a680) | Dec 13, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [75a9a0c076](https://linux-hardware.org/?probe=75a9a0c076) | Dec 12, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [15695e4deb](https://linux-hardware.org/?probe=15695e4deb) | Dec 11, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [71137ab051](https://linux-hardware.org/?probe=71137ab051) | Dec 08, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [651f6f4d18](https://linux-hardware.org/?probe=651f6f4d18) | Dec 07, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [de8272cf2e](https://linux-hardware.org/?probe=de8272cf2e) | Dec 05, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [0ade3eaab1](https://linux-hardware.org/?probe=0ade3eaab1) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [a3746e8985](https://linux-hardware.org/?probe=a3746e8985) | Dec 01, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [09129dad50](https://linux-hardware.org/?probe=09129dad50) | Nov 28, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [88ca303518](https://linux-hardware.org/?probe=88ca303518) | Nov 28, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [f278eb7e59](https://linux-hardware.org/?probe=f278eb7e59) | Nov 27, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [c188e01f20](https://linux-hardware.org/?probe=c188e01f20) | Nov 20, 2022 |
| HP            | Unknown                     | Notebook    | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Toshiba       | Satellite S55-A             | Notebook    | [d5e9f0d98a](https://linux-hardware.org/?probe=d5e9f0d98a) | Nov 19, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | Notebook    | [a6f536ca3d](https://linux-hardware.org/?probe=a6f536ca3d) | Oct 25, 2022 |
| Lenovo        | ThinkPad T60 1952F75        | Notebook    | [813bd112f8](https://linux-hardware.org/?probe=813bd112f8) | Oct 25, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [5d99fbefc1](https://linux-hardware.org/?probe=5d99fbefc1) | Oct 17, 2022 |
| MSI           | GF65 Thin 10SDR             | Notebook    | [1c2a3b90e2](https://linux-hardware.org/?probe=1c2a3b90e2) | Oct 04, 2022 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [5d789a1783](https://linux-hardware.org/?probe=5d789a1783) | Sep 28, 2022 |
| Dell          | Inspiron 3493               | Notebook    | [b1f8d22e3e](https://linux-hardware.org/?probe=b1f8d22e3e) | Sep 25, 2022 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [425dd57672](https://linux-hardware.org/?probe=425dd57672) | Sep 24, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [1bb8ad599d](https://linux-hardware.org/?probe=1bb8ad599d) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [b49d726ab0](https://linux-hardware.org/?probe=b49d726ab0) | Sep 03, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [ee80be714e](https://linux-hardware.org/?probe=ee80be714e) | Sep 03, 2022 |
| ASRock        | N68-S UCC                   | Desktop     | [1d38f1f08e](https://linux-hardware.org/?probe=1d38f1f08e) | Aug 30, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [9b23c4b82c](https://linux-hardware.org/?probe=9b23c4b82c) | Aug 30, 2022 |
| Dell          | G3 3579                     | Notebook    | [a3fc82fe9a](https://linux-hardware.org/?probe=a3fc82fe9a) | Aug 30, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [68d1385b7e](https://linux-hardware.org/?probe=68d1385b7e) | Aug 28, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [99faef3f00](https://linux-hardware.org/?probe=99faef3f00) | Aug 20, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fb77adfb99](https://linux-hardware.org/?probe=fb77adfb99) | Aug 16, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [992b4f4910](https://linux-hardware.org/?probe=992b4f4910) | Aug 06, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b932802b52](https://linux-hardware.org/?probe=b932802b52) | Aug 04, 2022 |
| ASUSTek       | GL552VW                     | Notebook    | [cd24503d2f](https://linux-hardware.org/?probe=cd24503d2f) | Aug 02, 2022 |
| Acer          | Aspire E5-576               | Notebook    | [a31ceb9a36](https://linux-hardware.org/?probe=a31ceb9a36) | Jul 31, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [da4a098248](https://linux-hardware.org/?probe=da4a098248) | Jul 22, 2022 |
| MACHINIST     | X79 V2.82H                  | Desktop     | [0e06f3fdf5](https://linux-hardware.org/?probe=0e06f3fdf5) | Jul 22, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [f4efe63bf8](https://linux-hardware.org/?probe=f4efe63bf8) | Jul 13, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [a06c4e1f6b](https://linux-hardware.org/?probe=a06c4e1f6b) | Jul 13, 2022 |
| Deffad        | Unknown                     | Notebook    | [af38c7120e](https://linux-hardware.org/?probe=af38c7120e) | Jul 04, 2022 |
| Dell          | Inspiron 3520               | Notebook    | [b865370f11](https://linux-hardware.org/?probe=b865370f11) | Jun 28, 2022 |
| Lenovo        | ThinkPad P50 20EN001PUS     | Notebook    | [52ef9383a4](https://linux-hardware.org/?probe=52ef9383a4) | Jun 09, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [46afe6a354](https://linux-hardware.org/?probe=46afe6a354) | Jun 02, 2022 |
| Lenovo        | ThinkPad T440s 20ARS29U0... | Notebook    | [50de8ad2e9](https://linux-hardware.org/?probe=50de8ad2e9) | Jun 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [b64c215325](https://linux-hardware.org/?probe=b64c215325) | May 30, 2022 |
| Dell          | Latitude 7400               | Notebook    | [caf85903ad](https://linux-hardware.org/?probe=caf85903ad) | May 19, 2022 |
| Dell          | Inspiron 5565               | Notebook    | [d5a8629a31](https://linux-hardware.org/?probe=d5a8629a31) | May 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [1aba67a1ac](https://linux-hardware.org/?probe=1aba67a1ac) | May 15, 2022 |
| Lenovo        | ThinkPad L420 7829AA4       | Notebook    | [9c1bbe8cf2](https://linux-hardware.org/?probe=9c1bbe8cf2) | May 14, 2022 |
| HP            | 0AECh D                     | Desktop     | [68adfe0740](https://linux-hardware.org/?probe=68adfe0740) | May 12, 2022 |
| HP            | 83EE                        | Desktop     | [55171637ca](https://linux-hardware.org/?probe=55171637ca) | Apr 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6ad1b34a48](https://linux-hardware.org/?probe=6ad1b34a48) | Apr 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [637af2dcc6](https://linux-hardware.org/?probe=637af2dcc6) | Apr 29, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [1f14473753](https://linux-hardware.org/?probe=1f14473753) | Apr 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f74cae630d](https://linux-hardware.org/?probe=f74cae630d) | Apr 16, 2022 |
| ZOTAC         | NM10                        | Desktop     | [b2983fdd9d](https://linux-hardware.org/?probe=b2983fdd9d) | Apr 15, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [e04e7a6bc9](https://linux-hardware.org/?probe=e04e7a6bc9) | Apr 13, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a1130d8070](https://linux-hardware.org/?probe=a1130d8070) | Apr 13, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [8e31fed1d4](https://linux-hardware.org/?probe=8e31fed1d4) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [ff072aa20b](https://linux-hardware.org/?probe=ff072aa20b) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [9cd507e648](https://linux-hardware.org/?probe=9cd507e648) | Apr 07, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [e5b52520a8](https://linux-hardware.org/?probe=e5b52520a8) | Apr 07, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [6a631fae48](https://linux-hardware.org/?probe=6a631fae48) | Mar 22, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [e1386a38c7](https://linux-hardware.org/?probe=e1386a38c7) | Mar 20, 2022 |
| Dell          | Latitude E5500              | Notebook    | [13be4a0a1b](https://linux-hardware.org/?probe=13be4a0a1b) | Mar 16, 2022 |
| Dell          | Latitude E5500              | Notebook    | [d5f8fd7890](https://linux-hardware.org/?probe=d5f8fd7890) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [a8531f3837](https://linux-hardware.org/?probe=a8531f3837) | Mar 13, 2022 |
| Dell          | Latitude D630               | Notebook    | [b7b428082a](https://linux-hardware.org/?probe=b7b428082a) | Mar 05, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [8807d99cb4](https://linux-hardware.org/?probe=8807d99cb4) | Mar 01, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [c0adf77f3f](https://linux-hardware.org/?probe=c0adf77f3f) | Feb 26, 2022 |
| Sony          | SVD13215PLB                 | Notebook    | [82c4287f85](https://linux-hardware.org/?probe=82c4287f85) | Feb 23, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [b355ea1ff3](https://linux-hardware.org/?probe=b355ea1ff3) | Feb 20, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [8468cd0da9](https://linux-hardware.org/?probe=8468cd0da9) | Feb 19, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [80e2f3c47e](https://linux-hardware.org/?probe=80e2f3c47e) | Feb 19, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Dell          | 0RW203 A00                  | Desktop     | [21ac06a9f6](https://linux-hardware.org/?probe=21ac06a9f6) | Feb 12, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [ce15566bc3](https://linux-hardware.org/?probe=ce15566bc3) | Feb 12, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [8fc6552bc9](https://linux-hardware.org/?probe=8fc6552bc9) | Feb 08, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [dbc7cbcfe1](https://linux-hardware.org/?probe=dbc7cbcfe1) | Feb 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [ac53ba49ef](https://linux-hardware.org/?probe=ac53ba49ef) | Jan 28, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [5e026ae9b0](https://linux-hardware.org/?probe=5e026ae9b0) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [3f953ad7f3](https://linux-hardware.org/?probe=3f953ad7f3) | Jan 14, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [eecedd12b2](https://linux-hardware.org/?probe=eecedd12b2) | Jan 14, 2022 |
| Samsung       | 930QAA                      | Convertible | [56758d8bfb](https://linux-hardware.org/?probe=56758d8bfb) | Jan 10, 2022 |
| Samsung       | 930QAA                      | Convertible | [206f508be5](https://linux-hardware.org/?probe=206f508be5) | Jan 10, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [6837cca618](https://linux-hardware.org/?probe=6837cca618) | Jan 02, 2022 |
| Gigabyte      | Z690 UD AX DDR4             | Desktop     | [9158036ed3](https://linux-hardware.org/?probe=9158036ed3) | Dec 30, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [b482ef13ea](https://linux-hardware.org/?probe=b482ef13ea) | Dec 26, 2021 |
| ASUSTek       | H81M-C                      | Desktop     | [0b0241baf7](https://linux-hardware.org/?probe=0b0241baf7) | Dec 08, 2021 |
| MSI           | H55M-E33                    | Desktop     | [f0786be9c3](https://linux-hardware.org/?probe=f0786be9c3) | Nov 14, 2021 |
| HP            | 18E4                        | Desktop     | [692c64d7c1](https://linux-hardware.org/?probe=692c64d7c1) | Nov 08, 2021 |
| HP            | 18E4                        | Desktop     | [499e85c152](https://linux-hardware.org/?probe=499e85c152) | Nov 07, 2021 |
| MSI           | H55M-E33                    | Desktop     | [3d8c474259](https://linux-hardware.org/?probe=3d8c474259) | Nov 06, 2021 |
| Dell          | Latitude 5490               | Notebook    | [c5c1f555f1](https://linux-hardware.org/?probe=c5c1f555f1) | Nov 03, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [b6ac4539d1](https://linux-hardware.org/?probe=b6ac4539d1) | Oct 28, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8264430178](https://linux-hardware.org/?probe=8264430178) | Oct 28, 2021 |
| Dell          | Inspiron 3595               | Notebook    | [1df662506b](https://linux-hardware.org/?probe=1df662506b) | Oct 27, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e7e870c6cc](https://linux-hardware.org/?probe=e7e870c6cc) | Oct 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [a271c08df2](https://linux-hardware.org/?probe=a271c08df2) | Oct 21, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [5bb3c9bc8b](https://linux-hardware.org/?probe=5bb3c9bc8b) | Oct 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [bfadd59ae5](https://linux-hardware.org/?probe=bfadd59ae5) | Oct 18, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [2a9e8d32e2](https://linux-hardware.org/?probe=2a9e8d32e2) | Oct 15, 2021 |
| Acer          | Aspire 5750                 | Notebook    | [ff12aa7481](https://linux-hardware.org/?probe=ff12aa7481) | Oct 15, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [f0a9d13afb](https://linux-hardware.org/?probe=f0a9d13afb) | Oct 14, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [2a83508f22](https://linux-hardware.org/?probe=2a83508f22) | Oct 10, 2021 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1dbff2c4f9](https://linux-hardware.org/?probe=1dbff2c4f9) | Oct 09, 2021 |
| TPV-INVENT... | 2AF2 A01                    | Desktop     | [23e967d7f5](https://linux-hardware.org/?probe=23e967d7f5) | Oct 06, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [da71bb02c1](https://linux-hardware.org/?probe=da71bb02c1) | Oct 03, 2021 |
| Dell          | Latitude D620               | Notebook    | [1dc8e001f5](https://linux-hardware.org/?probe=1dc8e001f5) | Sep 28, 2021 |
| ZOTAC         | NM10                        | Desktop     | [94313faa27](https://linux-hardware.org/?probe=94313faa27) | Sep 27, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [29a6b45091](https://linux-hardware.org/?probe=29a6b45091) | Sep 26, 2021 |
| Acer          | Aspire Z1-601               | All in one  | [5ed9f083e1](https://linux-hardware.org/?probe=5ed9f083e1) | Sep 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [3a8451c3d2](https://linux-hardware.org/?probe=3a8451c3d2) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [0a7625c3ec](https://linux-hardware.org/?probe=0a7625c3ec) | Sep 25, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2c4c85f574](https://linux-hardware.org/?probe=2c4c85f574) | Sep 20, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [dcf03222dc](https://linux-hardware.org/?probe=dcf03222dc) | Sep 12, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [00b3e62e2e](https://linux-hardware.org/?probe=00b3e62e2e) | Sep 10, 2021 |
| MSI           | GF75 Thin 9SD               | Notebook    | [e70d1b33e1](https://linux-hardware.org/?probe=e70d1b33e1) | Sep 09, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a7cc7fb98c](https://linux-hardware.org/?probe=a7cc7fb98c) | Aug 27, 2021 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [6972dfc45b](https://linux-hardware.org/?probe=6972dfc45b) | Aug 25, 2021 |
| ZOTAC         | NM10                        | Desktop     | [f735937235](https://linux-hardware.org/?probe=f735937235) | Aug 22, 2021 |
| MSI           | MPG Z390I GAMING EDGE AC    | Desktop     | [391c21db23](https://linux-hardware.org/?probe=391c21db23) | Aug 16, 2021 |
| Dell          | 0PU052                      | Desktop     | [25ce6d5bbd](https://linux-hardware.org/?probe=25ce6d5bbd) | Aug 05, 2021 |
| Olivetti      | CL133A                      | Notebook    | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| HP            | Pavilion g4                 | Notebook    | [3f01790d4e](https://linux-hardware.org/?probe=3f01790d4e) | Jul 21, 2021 |
| AZW           | GT-R                        | Notebook    | [115230aa47](https://linux-hardware.org/?probe=115230aa47) | Jul 19, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [a5a9cfcd44](https://linux-hardware.org/?probe=a5a9cfcd44) | Jul 18, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [689b83e978](https://linux-hardware.org/?probe=689b83e978) | Jul 18, 2021 |
| Olivetti      | CL133A                      | Notebook    | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| ASUSTek       | U46E                        | Notebook    | [720dec33c4](https://linux-hardware.org/?probe=720dec33c4) | Jul 14, 2021 |
| HP            | ProBook 6460b               | Notebook    | [b39eb9b256](https://linux-hardware.org/?probe=b39eb9b256) | Jul 13, 2021 |
| Dell          | G3 3590                     | Notebook    | [3781e31377](https://linux-hardware.org/?probe=3781e31377) | Jul 12, 2021 |
| Olivetti      | CL133A                      | Notebook    | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | Notebook    | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [9e01fd5e8c](https://linux-hardware.org/?probe=9e01fd5e8c) | Jun 20, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [e937e8ba7e](https://linux-hardware.org/?probe=e937e8ba7e) | Jun 20, 2021 |
| HP            | EliteBook 8570p             | Notebook    | [ab19b80507](https://linux-hardware.org/?probe=ab19b80507) | Jun 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b05fbab283](https://linux-hardware.org/?probe=b05fbab283) | Jun 06, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Dell          | 05WNJ2 A02                  | Server      | [2d1d9030e8](https://linux-hardware.org/?probe=2d1d9030e8) | May 31, 2021 |
| HP            | Pavilion dv6000 (RP297UA... | Notebook    | [5f6d9f025a](https://linux-hardware.org/?probe=5f6d9f025a) | May 29, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [ebffa34fe2](https://linux-hardware.org/?probe=ebffa34fe2) | May 28, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [3e92571a0c](https://linux-hardware.org/?probe=3e92571a0c) | May 26, 2021 |
| Toshiba       | Satellite C845              | Notebook    | [e3b90e238b](https://linux-hardware.org/?probe=e3b90e238b) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [6f3c2aa3be](https://linux-hardware.org/?probe=6f3c2aa3be) | May 24, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [8ccda2ce59](https://linux-hardware.org/?probe=8ccda2ce59) | May 24, 2021 |
| Toshiba       | Satellite C845              | Notebook    | [4d346e2691](https://linux-hardware.org/?probe=4d346e2691) | May 24, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [5e2e76f838](https://linux-hardware.org/?probe=5e2e76f838) | May 20, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [0a87ab06c5](https://linux-hardware.org/?probe=0a87ab06c5) | May 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [4a32129550](https://linux-hardware.org/?probe=4a32129550) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [93286a0d38](https://linux-hardware.org/?probe=93286a0d38) | May 15, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [796f490bbb](https://linux-hardware.org/?probe=796f490bbb) | May 15, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [1da876ea0b](https://linux-hardware.org/?probe=1da876ea0b) | May 06, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [0216a041d2](https://linux-hardware.org/?probe=0216a041d2) | May 05, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [b91d32b11a](https://linux-hardware.org/?probe=b91d32b11a) | May 03, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [604b735ad8](https://linux-hardware.org/?probe=604b735ad8) | May 02, 2021 |
| Acer          | Aspire A515-43              | Notebook    | [3c87a86111](https://linux-hardware.org/?probe=3c87a86111) | May 02, 2021 |
| HP            | Pavilion dv6                | Notebook    | [a181ae8691](https://linux-hardware.org/?probe=a181ae8691) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [d363966e4c](https://linux-hardware.org/?probe=d363966e4c) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [204cd9c44f](https://linux-hardware.org/?probe=204cd9c44f) | Apr 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [e20fc33e2b](https://linux-hardware.org/?probe=e20fc33e2b) | Apr 29, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [3cca89aa74](https://linux-hardware.org/?probe=3cca89aa74) | Apr 28, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [fd209ac377](https://linux-hardware.org/?probe=fd209ac377) | Apr 24, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U10... | Notebook    | [38c505f6bd](https://linux-hardware.org/?probe=38c505f6bd) | Apr 23, 2021 |
| Intel         | D33217CK G76541-302         | Desktop     | [1db9d29c38](https://linux-hardware.org/?probe=1db9d29c38) | Apr 19, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [a0590a2529](https://linux-hardware.org/?probe=a0590a2529) | Apr 18, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5afa66a433](https://linux-hardware.org/?probe=5afa66a433) | Apr 17, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e990abe7f1](https://linux-hardware.org/?probe=e990abe7f1) | Apr 11, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [41c14db0ef](https://linux-hardware.org/?probe=41c14db0ef) | Apr 11, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [48f003363a](https://linux-hardware.org/?probe=48f003363a) | Apr 09, 2021 |
| Dell          | 096JG8 A01                  | Desktop     | [1cf6d1daea](https://linux-hardware.org/?probe=1cf6d1daea) | Apr 02, 2021 |
| Supermicro    | X9DAi                       | Desktop     | [ff94b1201c](https://linux-hardware.org/?probe=ff94b1201c) | Mar 31, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [2ff9864ce6](https://linux-hardware.org/?probe=2ff9864ce6) | Mar 29, 2021 |
| Dell          | G3 3590                     | Notebook    | [3c952dbc96](https://linux-hardware.org/?probe=3c952dbc96) | Mar 26, 2021 |
| Toshiba       | QOSMIO X775                 | Notebook    | [d8f82a3984](https://linux-hardware.org/?probe=d8f82a3984) | Mar 26, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [127ea1feb8](https://linux-hardware.org/?probe=127ea1feb8) | Mar 13, 2021 |
| HP            | Pavilion g4                 | Notebook    | [1e7372e4f2](https://linux-hardware.org/?probe=1e7372e4f2) | Mar 01, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [e00317dc4d](https://linux-hardware.org/?probe=e00317dc4d) | Mar 01, 2021 |
| Unknown       | Unknown                     | Notebook    | [941e941403](https://linux-hardware.org/?probe=941e941403) | Feb 27, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [16fca1f86b](https://linux-hardware.org/?probe=16fca1f86b) | Feb 24, 2021 |
| Google        | Celes                       | Notebook    | [b30c090b2b](https://linux-hardware.org/?probe=b30c090b2b) | Feb 22, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [41ba11dbb4](https://linux-hardware.org/?probe=41ba11dbb4) | Feb 18, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [8570b15385](https://linux-hardware.org/?probe=8570b15385) | Feb 14, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [34bf1da3fe](https://linux-hardware.org/?probe=34bf1da3fe) | Feb 13, 2021 |
| ASRock        | 970 Extreme3                | Desktop     | [48548effcd](https://linux-hardware.org/?probe=48548effcd) | Feb 13, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [660afa073b](https://linux-hardware.org/?probe=660afa073b) | Feb 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [840e0e2818](https://linux-hardware.org/?probe=840e0e2818) | Feb 04, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [e10690d1d2](https://linux-hardware.org/?probe=e10690d1d2) | Feb 04, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [e0de5d87e6](https://linux-hardware.org/?probe=e0de5d87e6) | Feb 04, 2021 |
| HP            | Laptop 14-dq1xxx            | Notebook    | [84c932e071](https://linux-hardware.org/?probe=84c932e071) | Feb 02, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [473419d486](https://linux-hardware.org/?probe=473419d486) | Jan 24, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [738e03e488](https://linux-hardware.org/?probe=738e03e488) | Jan 23, 2021 |
| Dell          | Precision M4800             | Notebook    | [f24be700aa](https://linux-hardware.org/?probe=f24be700aa) | Jan 21, 2021 |
| Dell          | Precision M4800             | Notebook    | [316c7dd34b](https://linux-hardware.org/?probe=316c7dd34b) | Jan 21, 2021 |
| HP            | Laptop 14-bp0xx             | Notebook    | [4badbab2db](https://linux-hardware.org/?probe=4badbab2db) | Jan 19, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [1a731e13e0](https://linux-hardware.org/?probe=1a731e13e0) | Jan 18, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [6a0e9eff49](https://linux-hardware.org/?probe=6a0e9eff49) | Jan 16, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [76fe08b67a](https://linux-hardware.org/?probe=76fe08b67a) | Jan 14, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [8d9be2defd](https://linux-hardware.org/?probe=8d9be2defd) | Jan 13, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [6917b5bc30](https://linux-hardware.org/?probe=6917b5bc30) | Jan 11, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [cfa1367cf6](https://linux-hardware.org/?probe=cfa1367cf6) | Jan 10, 2021 |
| Dell          | Inspiron 5584               | Notebook    | [60a171b505](https://linux-hardware.org/?probe=60a171b505) | Jan 10, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [6c9d42b55d](https://linux-hardware.org/?probe=6c9d42b55d) | Jan 08, 2021 |
| Unknown       | i845G-W83627HF              | Desktop     | [9ff8161bec](https://linux-hardware.org/?probe=9ff8161bec) | Jan 08, 2021 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [6706c380ab](https://linux-hardware.org/?probe=6706c380ab) | Dec 21, 2020 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [93308d477a](https://linux-hardware.org/?probe=93308d477a) | Dec 18, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [a481e8e9c0](https://linux-hardware.org/?probe=a481e8e9c0) | Dec 16, 2020 |
| HP            | Laptop 14-bp0xx             | Notebook    | [266b8d7543](https://linux-hardware.org/?probe=266b8d7543) | Dec 16, 2020 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [a305c14111](https://linux-hardware.org/?probe=a305c14111) | Dec 13, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2d9e84acd0](https://linux-hardware.org/?probe=2d9e84acd0) | Dec 13, 2020 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [3c6c9b7bd3](https://linux-hardware.org/?probe=3c6c9b7bd3) | Dec 11, 2020 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [3070faaf5e](https://linux-hardware.org/?probe=3070faaf5e) | Dec 03, 2020 |
| Alienware     | 06G6JW A01                  | Desktop     | [812527d15d](https://linux-hardware.org/?probe=812527d15d) | Dec 02, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| Dell          | Latitude 7480               | Notebook    | [2e569dcaed](https://linux-hardware.org/?probe=2e569dcaed) | Oct 22, 2020 |
| Dell          | Latitude 7480               | Notebook    | [1cc0a03f18](https://linux-hardware.org/?probe=1cc0a03f18) | Oct 22, 2020 |
| HP            | 2B54 100                    | All in one  | [161455efd7](https://linux-hardware.org/?probe=161455efd7) | Oct 17, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [9f10520397](https://linux-hardware.org/?probe=9f10520397) | Oct 11, 2020 |
| Dell          | G3 3590                     | Notebook    | [4c2ddd8b88](https://linux-hardware.org/?probe=4c2ddd8b88) | Oct 01, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [6acb0908ff](https://linux-hardware.org/?probe=6acb0908ff) | Sep 18, 2020 |
| HP            | Unknown                     | Notebook    | [a446c81ca9](https://linux-hardware.org/?probe=a446c81ca9) | Sep 10, 2020 |
| HP            | 2B54 100                    | All in one  | [8e21d2bb01](https://linux-hardware.org/?probe=8e21d2bb01) | Sep 06, 2020 |
| HP            | EliteBook 8570p             | Notebook    | [48e494142e](https://linux-hardware.org/?probe=48e494142e) | Aug 27, 2020 |
| Toshiba       | Satellite X205              | Notebook    | [b0d5e7d0dd](https://linux-hardware.org/?probe=b0d5e7d0dd) | Aug 26, 2020 |
| Toshiba       | Satellite X205              | Notebook    | [45e52f3631](https://linux-hardware.org/?probe=45e52f3631) | Aug 26, 2020 |
| Dell          | 042P49 A01                  | Desktop     | [36ddd61132](https://linux-hardware.org/?probe=36ddd61132) | Aug 12, 2020 |
| Acer          | Aspire 4739Z                | Notebook    | [44ec59d132](https://linux-hardware.org/?probe=44ec59d132) | Aug 11, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [4bdd603282](https://linux-hardware.org/?probe=4bdd603282) | Aug 06, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [4114f58581](https://linux-hardware.org/?probe=4114f58581) | Aug 06, 2020 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [d8a8eb467a](https://linux-hardware.org/?probe=d8a8eb467a) | Aug 02, 2020 |
| Dell          | Latitude E5440              | Notebook    | [9d31b1e38d](https://linux-hardware.org/?probe=9d31b1e38d) | Jul 29, 2020 |
| Gateway       | FMCP7AM                     | Desktop     | [58e88b2df5](https://linux-hardware.org/?probe=58e88b2df5) | Jul 28, 2020 |
| ABIT          | AW9D-MAX                    | Desktop     | [fca26e4a11](https://linux-hardware.org/?probe=fca26e4a11) | Jul 21, 2020 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [c00d0feee3](https://linux-hardware.org/?probe=c00d0feee3) | Jul 21, 2020 |
| MSI           | 970 GAMING                  | Desktop     | [73c5756fdd](https://linux-hardware.org/?probe=73c5756fdd) | Jul 01, 2020 |
| Dell          | G3 3590                     | Notebook    | [e2fa394ba6](https://linux-hardware.org/?probe=e2fa394ba6) | Jun 28, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [8119688776](https://linux-hardware.org/?probe=8119688776) | Jun 27, 2020 |
| Dell          | XPS 15 9560                 | Notebook    | [d2a2900148](https://linux-hardware.org/?probe=d2a2900148) | Jun 20, 2020 |
| ASRock        | B450 Steel Legend           | Desktop     | [7d9ad3146b](https://linux-hardware.org/?probe=7d9ad3146b) | Jun 12, 2020 |
| Dell          | Inspiron 5559               | Notebook    | [4619502a6b](https://linux-hardware.org/?probe=4619502a6b) | May 28, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [b9c266ed55](https://linux-hardware.org/?probe=b9c266ed55) | May 20, 2020 |
| HP            | ProBook 455 G4              | Notebook    | [6b6fe8e0c1](https://linux-hardware.org/?probe=6b6fe8e0c1) | May 18, 2020 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [6252910769](https://linux-hardware.org/?probe=6252910769) | May 11, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [8fc4603f6c](https://linux-hardware.org/?probe=8fc4603f6c) | May 10, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [33cd43676f](https://linux-hardware.org/?probe=33cd43676f) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [1a81d95494](https://linux-hardware.org/?probe=1a81d95494) | May 09, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [cd09b6b8a5](https://linux-hardware.org/?probe=cd09b6b8a5) | May 09, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [9311532f56](https://linux-hardware.org/?probe=9311532f56) | Apr 23, 2020 |
| HP            | 245 G4 Notebook PC          | Notebook    | [b662f230b2](https://linux-hardware.org/?probe=b662f230b2) | Apr 23, 2020 |
| Apple         | Mac-DB15BD556843C820 iMa... | All in one  | [3c2d508fc2](https://linux-hardware.org/?probe=3c2d508fc2) | Apr 23, 2020 |
| HP            | Notebook                    | Notebook    | [5815277bb0](https://linux-hardware.org/?probe=5815277bb0) | Apr 22, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [1dc3e83e11](https://linux-hardware.org/?probe=1dc3e83e11) | Apr 18, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [2f87bcd627](https://linux-hardware.org/?probe=2f87bcd627) | Apr 07, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [16ff51d343](https://linux-hardware.org/?probe=16ff51d343) | Apr 07, 2020 |
| Acer          | Aspire V3-471               | Notebook    | [024d5b0563](https://linux-hardware.org/?probe=024d5b0563) | Apr 06, 2020 |
| Dell          | G3 3590                     | Notebook    | [26a4f7e20b](https://linux-hardware.org/?probe=26a4f7e20b) | Mar 22, 2020 |
| Dell          | G3 3590                     | Notebook    | [96d9b68953](https://linux-hardware.org/?probe=96d9b68953) | Mar 21, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [fcea840696](https://linux-hardware.org/?probe=fcea840696) | Mar 04, 2020 |
| Toshiba       | Satellite C855D             | Notebook    | [9246f32b7e](https://linux-hardware.org/?probe=9246f32b7e) | Mar 01, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [9398ebaa03](https://linux-hardware.org/?probe=9398ebaa03) | Feb 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [1419b6c5e7](https://linux-hardware.org/?probe=1419b6c5e7) | Feb 29, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [2bbf18e9e5](https://linux-hardware.org/?probe=2bbf18e9e5) | Feb 20, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [68895d1461](https://linux-hardware.org/?probe=68895d1461) | Feb 20, 2020 |
| HP            | ProBook 6460b               | Notebook    | [121b074dd0](https://linux-hardware.org/?probe=121b074dd0) | Feb 19, 2020 |
| Dell          | Latitude 5500               | Notebook    | [3a7f8e19f1](https://linux-hardware.org/?probe=3a7f8e19f1) | Feb 17, 2020 |
| ASUSTek       | K52F                        | Notebook    | [9dde03d12c](https://linux-hardware.org/?probe=9dde03d12c) | Feb 13, 2020 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [750ccde7c5](https://linux-hardware.org/?probe=750ccde7c5) | Jan 19, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [9eb64d7269](https://linux-hardware.org/?probe=9eb64d7269) | Jan 17, 2020 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [8211b13acf](https://linux-hardware.org/?probe=8211b13acf) | Jan 17, 2020 |
| ASRock        | 775i65GV                    | Desktop     | [0367c8a291](https://linux-hardware.org/?probe=0367c8a291) | Jan 07, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [5662d620a5](https://linux-hardware.org/?probe=5662d620a5) | Jan 03, 2020 |
| Lenovo        | IdeaPadFlex 4-1480 80VD     | Convertible | [bd9a062902](https://linux-hardware.org/?probe=bd9a062902) | Jan 03, 2020 |
| ASRock        | 775i65GV                    | Desktop     | [d0a8b9d7da](https://linux-hardware.org/?probe=d0a8b9d7da) | Dec 25, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [73da3dccf1](https://linux-hardware.org/?probe=73da3dccf1) | Nov 14, 2019 |
| HP            | 240 G6 Notebook PC          | Notebook    | [efeee7f2fc](https://linux-hardware.org/?probe=efeee7f2fc) | Nov 14, 2019 |
| Dell          | 042P49 A01                  | Desktop     | [ce3194fcde](https://linux-hardware.org/?probe=ce3194fcde) | Oct 28, 2019 |
| System76      | Lemur                       | Notebook    | [a9cc263cb4](https://linux-hardware.org/?probe=a9cc263cb4) | Oct 09, 2019 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [4ddf2bb220](https://linux-hardware.org/?probe=4ddf2bb220) | Oct 06, 2019 |
| HP            | ProBook 450 G2              | Notebook    | [c7959cccb3](https://linux-hardware.org/?probe=c7959cccb3) | Sep 30, 2019 |
| HP            | Notebook                    | Notebook    | [163fc3e9dd](https://linux-hardware.org/?probe=163fc3e9dd) | Sep 14, 2019 |
| Biostar       | H61MGV3                     | Desktop     | [911486bcc2](https://linux-hardware.org/?probe=911486bcc2) | Sep 08, 2019 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [c34161a66d](https://linux-hardware.org/?probe=c34161a66d) | Sep 02, 2019 |
| System76      | Lemur                       | Notebook    | [01bbf99115](https://linux-hardware.org/?probe=01bbf99115) | Sep 02, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | Notebook    | [47182bd3e3](https://linux-hardware.org/?probe=47182bd3e3) | Sep 01, 2019 |
| Lenovo        | ThinkPad P53 20QNS00P00     | Notebook    | [2105fa4def](https://linux-hardware.org/?probe=2105fa4def) | Sep 01, 2019 |
| HP            | Notebook                    | Notebook    | [b7e9995b67](https://linux-hardware.org/?probe=b7e9995b67) | Aug 18, 2019 |
| HP            | Notebook                    | Notebook    | [273d0bcc2e](https://linux-hardware.org/?probe=273d0bcc2e) | Aug 18, 2019 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [2e5b92af00](https://linux-hardware.org/?probe=2e5b92af00) | Aug 17, 2019 |
| Dell          | Latitude E5450              | Notebook    | [3336801ccf](https://linux-hardware.org/?probe=3336801ccf) | Aug 10, 2019 |
| Toshiba       | Satellite A305D             | Notebook    | [ebf0a9c89e](https://linux-hardware.org/?probe=ebf0a9c89e) | Aug 08, 2019 |
| Acer          | SW5-017P                    | Notebook    | [fbf9b74a34](https://linux-hardware.org/?probe=fbf9b74a34) | Jul 29, 2019 |
| Dell          | Latitude 5480               | Notebook    | [f488cfd08f](https://linux-hardware.org/?probe=f488cfd08f) | Jun 22, 2019 |
| Biostar       | H61MGV3                     | Desktop     | [0b1e8f1f08](https://linux-hardware.org/?probe=0b1e8f1f08) | Jun 12, 2019 |
| Intel         | DG41WV AAE90316-103         | Desktop     | [7b2dc235f8](https://linux-hardware.org/?probe=7b2dc235f8) | May 18, 2019 |
| ASUSTek       | Strix 17 GL703GE            | Notebook    | [328975f3a5](https://linux-hardware.org/?probe=328975f3a5) | May 15, 2019 |
| Dell          | Latitude 5480               | Notebook    | [694ca16d49](https://linux-hardware.org/?probe=694ca16d49) | May 04, 2019 |
| Lenovo        | SHARKBAY 31900003 STD       | Desktop     | [e7164fcda2](https://linux-hardware.org/?probe=e7164fcda2) | Dec 01, 2018 |
| Purism        | Librem 15 v3                | Notebook    | [00259367c8](https://linux-hardware.org/?probe=00259367c8) | Oct 29, 2018 |
| Purism        | Librem 15 v3                | Notebook    | [c5e1ab1520](https://linux-hardware.org/?probe=c5e1ab1520) | Oct 29, 2018 |
| ASUSTek       | X555LAB                     | Notebook    | [243803142a](https://linux-hardware.org/?probe=243803142a) | Aug 01, 2018 |
| Toshiba       | Satellite C645D             | Notebook    | [9d50eb7fdb](https://linux-hardware.org/?probe=9d50eb7fdb) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 23        | 9.87%   |
| Ubuntu 18.04                 | 17        | 7.3%    |
| OpenMandriva 4.2             | 16        | 6.87%   |
| Ubuntu 22.04                 | 12        | 5.15%   |
| OpenMandriva 4.3             | 7         | 3%      |
| Zorin 16                     | 6         | 2.58%   |
| OpenMandriva 23.01           | 6         | 2.58%   |
| Lubuntu 22.04                | 5         | 2.15%   |
| Ubuntu 19.04                 | 4         | 1.72%   |
| Lubuntu 21.10                | 4         | 1.72%   |
| Linux Mint 20.2              | 4         | 1.72%   |
| Linux Mint 19.3              | 4         | 1.72%   |
| Fedora 36                    | 4         | 1.72%   |
| Debian 11                    | 4         | 1.72%   |
| Raspbian 11                  | 3         | 1.29%   |
| Lubuntu 22.10                | 3         | 1.29%   |
| Lubuntu 21.04                | 3         | 1.29%   |
| Debian 10                    | 3         | 1.29%   |
| Zorin 15                     | 2         | 0.86%   |
| Xubuntu 20.04                | 2         | 0.86%   |
| UbuntuDDE 20.04              | 2         | 0.86%   |
| Ubuntu Studio 20.04          | 2         | 0.86%   |
| Ubuntu 21.04                 | 2         | 0.86%   |
| Pop!_OS 22.04                | 2         | 0.86%   |
| Pop!_OS 21.04                | 2         | 0.86%   |
| Pop!_OS 20.10                | 2         | 0.86%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.86%   |
| Manjaro 20.2.1               | 2         | 0.86%   |
| Manjaro                      | 2         | 0.86%   |
| Lubuntu 20.04                | 2         | 0.86%   |
| Linux Mint 20.3              | 2         | 0.86%   |
| Linux Mint 20.1              | 2         | 0.86%   |
| Linux Mint 20                | 2         | 0.86%   |
| KDE neon 20.04               | 2         | 0.86%   |
| Fedora 35                    | 2         | 0.86%   |
| Fedora 34                    | 2         | 0.86%   |
| Fedora 32                    | 2         | 0.86%   |
| EndeavourOS Rolling          | 2         | 0.86%   |
| Debian Testing               | 2         | 0.86%   |
| Arch                         | 2         | 0.86%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 61        | 28.24%  |
| OpenMandriva  | 30        | 13.89%  |
| Linux Mint    | 15        | 6.94%   |
| Fedora        | 13        | 6.02%   |
| Manjaro       | 10        | 4.63%   |
| Zorin         | 9         | 4.17%   |
| Lubuntu       | 9         | 4.17%   |
| Debian        | 9         | 4.17%   |
| Pop!_OS       | 8         | 3.7%    |
| ROSA          | 5         | 2.31%   |
| Kubuntu       | 4         | 1.85%   |
| Xubuntu       | 3         | 1.39%   |
| Raspbian      | 3         | 1.39%   |
| KDE neon      | 3         | 1.39%   |
| Elementary    | 3         | 1.39%   |
| Arch          | 3         | 1.39%   |
| UbuntuDDE     | 2         | 0.93%   |
| Ubuntu Unity  | 2         | 0.93%   |
| Ubuntu Studio | 2         | 0.93%   |
| openSUSE      | 2         | 0.93%   |
| Kali          | 2         | 0.93%   |
| Endless       | 2         | 0.93%   |
| EndeavourOS   | 2         | 0.93%   |
| ArcoLinux     | 2         | 0.93%   |
| Ubuntu MATE   | 1         | 0.46%   |
| Reborn OS     | 1         | 0.46%   |
| PureOS        | 1         | 0.46%   |
| Peppermint    | 1         | 0.46%   |
| Parrot        | 1         | 0.46%   |
| Nobara        | 1         | 0.46%   |
| LMDE          | 1         | 0.46%   |
| Clear Linux   | 1         | 0.46%   |
| ChimeraOS     | 1         | 0.46%   |
| BlackPanther  | 1         | 0.46%   |
| BigLinux      | 1         | 0.46%   |
| ALT Linux     | 1         | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 16        | 6.3%    |
| 5.16.7-desktop-1omv4003  | 7         | 2.76%   |
| 5.4.0-42-generic         | 5         | 1.97%   |
| 5.4.0-70-generic         | 4         | 1.57%   |
| 5.13.0-16-generic        | 4         | 1.57%   |
| 5.11.0-27-generic        | 4         | 1.57%   |
| 5.0.0-23-generic         | 4         | 1.57%   |
| 6.1.1-desktop-1omv2290   | 3         | 1.18%   |
| 5.8.0-50-generic         | 3         | 1.18%   |
| 5.4.0-77-generic         | 3         | 1.18%   |
| 5.19.0-26-generic        | 3         | 1.18%   |
| 5.15.0-52-generic        | 3         | 1.18%   |
| 5.0.0-25-generic         | 3         | 1.18%   |
| 6.1.4-desktop-1omv2301   | 2         | 0.79%   |
| 6.0.6-76060006-generic   | 2         | 0.79%   |
| 5.9.16-1-MANJARO         | 2         | 0.79%   |
| 5.8.0-7630-generic       | 2         | 0.79%   |
| 5.4.0-52-generic         | 2         | 0.79%   |
| 5.4.0-29-generic         | 2         | 0.79%   |
| 5.4.0-26-generic         | 2         | 0.79%   |
| 5.4.0-21-generic         | 2         | 0.79%   |
| 5.3.0-40-generic         | 2         | 0.79%   |
| 5.3.0-28-generic         | 2         | 0.79%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.79%   |
| 5.15.0-58-generic        | 2         | 0.79%   |
| 5.15.0-53-generic        | 2         | 0.79%   |
| 5.15.0-41-generic        | 2         | 0.79%   |
| 5.15.0-27-generic        | 2         | 0.79%   |
| 5.15.0-25-generic        | 2         | 0.79%   |
| 5.13.0-35-generic        | 2         | 0.79%   |
| 5.13.0-20-generic        | 2         | 0.79%   |
| 5.11.0-16-generic        | 2         | 0.79%   |
| 4.19.0-8-amd64           | 2         | 0.79%   |
| 4.15.0-112-generic       | 2         | 0.79%   |
| 6.2.0-custom             | 1         | 0.39%   |
| 6.1.6-custom             | 1         | 0.39%   |
| 6.1.2-desktop-1omv2301   | 1         | 0.39%   |
| 6.1.2-arch1-1            | 1         | 0.39%   |
| 6.1.11-custom            | 1         | 0.39%   |
| 6.1.1-arch1-1            | 1         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 15.06%  |
| 5.15.0  | 22        | 9.21%   |
| 5.10.14 | 16        | 6.69%   |
| 5.11.0  | 15        | 6.28%   |
| 4.15.0  | 12        | 5.02%   |
| 5.3.0   | 10        | 4.18%   |
| 5.13.0  | 10        | 4.18%   |
| 5.8.0   | 9         | 3.77%   |
| 5.0.0   | 9         | 3.77%   |
| 5.10.0  | 8         | 3.35%   |
| 5.16.7  | 7         | 2.93%   |
| 6.1.1   | 5         | 2.09%   |
| 5.19.0  | 5         | 2.09%   |
| 5.18.13 | 3         | 1.26%   |
| 4.19.0  | 3         | 1.26%   |
| 6.1.4   | 2         | 0.84%   |
| 6.1.2   | 2         | 0.84%   |
| 6.0.6   | 2         | 0.84%   |
| 5.9.16  | 2         | 0.84%   |
| 5.7.0   | 2         | 0.84%   |
| 4.18.0  | 2         | 0.84%   |
| 6.2.0   | 1         | 0.42%   |
| 6.1.6   | 1         | 0.42%   |
| 6.1.11  | 1         | 0.42%   |
| 6.1.0   | 1         | 0.42%   |
| 6.0.8   | 1         | 0.42%   |
| 6.0.7   | 1         | 0.42%   |
| 6.0.2   | 1         | 0.42%   |
| 6.0.11  | 1         | 0.42%   |
| 6.0.10  | 1         | 0.42%   |
| 5.9.9   | 1         | 0.42%   |
| 5.9.14  | 1         | 0.42%   |
| 5.9.11  | 1         | 0.42%   |
| 5.8.6   | 1         | 0.42%   |
| 5.6.19  | 1         | 0.42%   |
| 5.6.16  | 1         | 0.42%   |
| 5.6.14  | 1         | 0.42%   |
| 5.6.13  | 1         | 0.42%   |
| 5.4.40  | 1         | 0.42%   |
| 5.2.11  | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 37        | 15.55%  |
| 5.10    | 31        | 13.03%  |
| 5.15    | 29        | 12.18%  |
| 5.11    | 19        | 7.98%   |
| 6.1     | 12        | 5.04%   |
| 4.15    | 12        | 5.04%   |
| 5.13    | 11        | 4.62%   |
| 5.8     | 10        | 4.2%    |
| 5.3     | 10        | 4.2%    |
| 5.0     | 10        | 4.2%    |
| 5.19    | 8         | 3.36%   |
| 6.0     | 7         | 2.94%   |
| 5.16    | 7         | 2.94%   |
| 5.18    | 6         | 2.52%   |
| 5.9     | 5         | 2.1%    |
| 5.6     | 4         | 1.68%   |
| 4.19    | 4         | 1.68%   |
| 5.12    | 3         | 1.26%   |
| 4.18    | 3         | 1.26%   |
| 5.7     | 2         | 0.84%   |
| 5.14    | 2         | 0.84%   |
| 4.1     | 2         | 0.84%   |
| 6.2     | 1         | 0.42%   |
| 5.2     | 1         | 0.42%   |
| 5.17    | 1         | 0.42%   |
| 4.9     | 1         | 0.42%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 195       | 96.06%  |
| i686   | 5         | 2.46%   |
| armv6l | 2         | 0.99%   |
| armv7l | 1         | 0.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 93        | 44.5%   |
| KDE5          | 40        | 19.14%  |
| Unknown       | 19        | 9.09%   |
| XFCE          | 13        | 6.22%   |
| LXQt          | 9         | 4.31%   |
| X-Cinnamon    | 8         | 3.83%   |
| MATE          | 6         | 2.87%   |
| KDE           | 4         | 1.91%   |
| Pantheon      | 3         | 1.44%   |
| LXDE          | 3         | 1.44%   |
| Unity         | 2         | 0.96%   |
| Openbox       | 2         | 0.96%   |
| i3            | 2         | 0.96%   |
| Deepin        | 2         | 0.96%   |
| Cinnamon      | 2         | 0.96%   |
| GNOME Classic | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 157       | 76.21%  |
| Wayland | 36        | 17.48%  |
| Unknown | 8         | 3.88%   |
| Tty     | 5         | 2.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 92        | 43.6%   |
| SDDM    | 51        | 24.17%  |
| GDM     | 22        | 10.43%  |
| LightDM | 18        | 8.53%   |
| GDM3    | 17        | 8.06%   |
| TDM     | 11        | 5.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 88        | 41.9%   |
| es_CR   | 79        | 37.62%  |
| Unknown | 19        | 9.05%   |
| es_ES   | 13        | 6.19%   |
| en_GB   | 3         | 1.43%   |
| C       | 3         | 1.43%   |
| es_MX   | 2         | 0.95%   |
| fr_FR   | 1         | 0.48%   |
| es_EC   | 1         | 0.48%   |
| de_DE   | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 111       | 53.37%  |
| BIOS | 97        | 46.63%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 153       | 73.21%  |
| Overlay | 28        | 13.4%   |
| Btrfs   | 20        | 9.57%   |
| Unknown | 5         | 2.39%   |
| Xfs     | 2         | 0.96%   |
| Tmpfs   | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 103       | 49.52%  |
| GPT     | 81        | 38.94%  |
| MBR     | 24        | 11.54%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 180       | 86.96%  |
| Yes       | 27        | 13.04%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 129       | 62.32%  |
| Yes       | 78        | 37.68%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 44        | 21.67%  |
| Hewlett-Packard         | 31        | 15.27%  |
| Lenovo                  | 22        | 10.84%  |
| ASUSTek Computer        | 20        | 9.85%   |
| Toshiba                 | 12        | 5.91%   |
| Gigabyte Technology     | 12        | 5.91%   |
| Acer                    | 11        | 5.42%   |
| MSI                     | 9         | 4.43%   |
| ASRock                  | 7         | 3.45%   |
| Apple                   | 6         | 2.96%   |
| Raspberry Pi Foundation | 3         | 1.48%   |
| Intel                   | 3         | 1.48%   |
| Unknown                 | 3         | 1.48%   |
| ZOTAC                   | 1         | 0.49%   |
| TPV-INVENTA             | 1         | 0.49%   |
| System76                | 1         | 0.49%   |
| Supermicro              | 1         | 0.49%   |
| Sony                    | 1         | 0.49%   |
| Samsung Electronics     | 1         | 0.49%   |
| Purism                  | 1         | 0.49%   |
| Pegatron                | 1         | 0.49%   |
| Olivetti                | 1         | 0.49%   |
| Microsoft               | 1         | 0.49%   |
| MACHINIST               | 1         | 0.49%   |
| Jumper                  | 1         | 0.49%   |
| HUAWEI                  | 1         | 0.49%   |
| Google                  | 1         | 0.49%   |
| Gateway                 | 1         | 0.49%   |
| Deffad                  | 1         | 0.49%   |
| Biostar                 | 1         | 0.49%   |
| AZW                     | 1         | 0.49%   |
| Alienware               | 1         | 0.49%   |
| ABIT                    | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 6         | 2.96%   |
| Dell OptiPlex 3020                       | 5         | 2.46%   |
| Apple MacBookPro8,1                      | 4         | 1.97%   |
| Dell Inspiron 7506 2n1                   | 3         | 1.48%   |
| Dell Inspiron 5584                       | 3         | 1.48%   |
| HP ProBook 6460b                         | 2         | 0.99%   |
| HP Pavilion Notebook                     | 2         | 0.99%   |
| HP Notebook                              | 2         | 0.99%   |
| HP Laptop 15-da0xxx                      | 2         | 0.99%   |
| Gigabyte B250M-DS3H                      | 2         | 0.99%   |
| Dell OptiPlex 7040                       | 2         | 0.99%   |
| ASUS TUF Gaming X570-PLUS                | 2         | 0.99%   |
| ASUS PRIME A320M-K                       | 2         | 0.99%   |
| ASRock B450 Steel Legend                 | 2         | 0.99%   |
| ZOTAC NM10                               | 1         | 0.49%   |
| TPV-INVENTA 18-2003LA                    | 1         | 0.49%   |
| Toshiba Satellite X205                   | 1         | 0.49%   |
| Toshiba Satellite S55-A                  | 1         | 0.49%   |
| Toshiba Satellite L655                   | 1         | 0.49%   |
| Toshiba Satellite L45-B                  | 1         | 0.49%   |
| Toshiba Satellite C855D                  | 1         | 0.49%   |
| Toshiba Satellite C845                   | 1         | 0.49%   |
| Toshiba Satellite C645D                  | 1         | 0.49%   |
| Toshiba Satellite C55-C                  | 1         | 0.49%   |
| Toshiba Satellite C55-B                  | 1         | 0.49%   |
| Toshiba Satellite C45-A                  | 1         | 0.49%   |
| Toshiba Satellite A305D                  | 1         | 0.49%   |
| Toshiba QOSMIO X775                      | 1         | 0.49%   |
| System76 Lemur                           | 1         | 0.49%   |
| Supermicro X9DAi                         | 1         | 0.49%   |
| Sony SVD13215PLB                         | 1         | 0.49%   |
| Samsung 930QAA                           | 1         | 0.49%   |
| RPi Raspberry Pi Model B Rev 2           | 1         | 0.49%   |
| RPi Raspberry Pi 3 Model B Plus Rev 1.3  | 1         | 0.49%   |
| RPi Raspberry Pi                         | 1         | 0.49%   |
| Purism Librem 15 v3                      | 1         | 0.49%   |
| Pegatron CQ2728LA                        | 1         | 0.49%   |
| Olivetti CL133A                          | 1         | 0.49%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1         | 0.49%   |
| MSI MS-7D77                              | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 14        | 6.9%    |
| Dell Inspiron         | 14        | 6.9%    |
| Toshiba Satellite     | 11        | 5.42%   |
| Dell Latitude         | 11        | 5.42%   |
| Dell OptiPlex         | 10        | 4.93%   |
| Acer Aspire           | 9         | 4.43%   |
| HP Pavilion           | 7         | 3.45%   |
| HP Laptop             | 6         | 2.96%   |
| Unknown               | 6         | 2.96%   |
| Lenovo IdeaPad        | 4         | 1.97%   |
| HP ProBook            | 4         | 1.97%   |
| Dell Precision        | 4         | 1.97%   |
| ASUS PRIME            | 4         | 1.97%   |
| Apple MacBookPro8     | 4         | 1.97%   |
| RPi Raspberry         | 3         | 1.48%   |
| HP EliteBook          | 3         | 1.48%   |
| ASUS VivoBook         | 3         | 1.48%   |
| ASUS TUF              | 3         | 1.48%   |
| Lenovo IdeaPadFlex    | 2         | 0.99%   |
| HP Notebook           | 2         | 0.99%   |
| Gigabyte B250M-DS3H   | 2         | 0.99%   |
| Dell XPS              | 2         | 0.99%   |
| Dell G3               | 2         | 0.99%   |
| ASUS Strix            | 2         | 0.99%   |
| ASRock B450           | 2         | 0.99%   |
| ZOTAC NM10            | 1         | 0.49%   |
| TPV-INVENTA 18-2003LA | 1         | 0.49%   |
| Toshiba QOSMIO        | 1         | 0.49%   |
| System76 Lemur        | 1         | 0.49%   |
| Supermicro X9DAi      | 1         | 0.49%   |
| Sony SVD13215PLB      | 1         | 0.49%   |
| Samsung 930QAA        | 1         | 0.49%   |
| Purism Librem         | 1         | 0.49%   |
| Pegatron CQ2728LA     | 1         | 0.49%   |
| Olivetti CL133A       | 1         | 0.49%   |
| MSI Z390              | 1         | 0.49%   |
| MSI MS-7D77           | 1         | 0.49%   |
| MSI MS-7B86           | 1         | 0.49%   |
| MSI MS-7992           | 1         | 0.49%   |
| MSI MS-7693           | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 27        | 13.3%   |
| 2014    | 18        | 8.87%   |
| 2020    | 17        | 8.37%   |
| 2018    | 17        | 8.37%   |
| 2016    | 15        | 7.39%   |
| 2011    | 15        | 7.39%   |
| 2017    | 14        | 6.9%    |
| 2013    | 14        | 6.9%    |
| 2012    | 14        | 6.9%    |
| 2015    | 10        | 4.93%   |
| 2021    | 8         | 3.94%   |
| 2008    | 7         | 3.45%   |
| 2022    | 6         | 2.96%   |
| 2010    | 6         | 2.96%   |
| 2007    | 4         | 1.97%   |
| 2009    | 3         | 1.48%   |
| 2006    | 3         | 1.48%   |
| Unknown | 3         | 1.48%   |
| 2005    | 2         | 0.99%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 120       | 59.11%  |
| Desktop        | 66        | 32.51%  |
| Convertible    | 7         | 3.45%   |
| System on chip | 3         | 1.48%   |
| All in one     | 3         | 1.48%   |
| Tablet         | 2         | 0.99%   |
| Mini pc        | 1         | 0.49%   |
| Server         | 1         | 0.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 186       | 91.63%  |
| Enabled  | 17        | 8.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 201       | 99.01%  |
| Yes  | 2         | 0.99%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 43        | 20.98%  |
| 8.01-16.0       | 41        | 20%     |
| 3.01-4.0        | 40        | 19.51%  |
| 16.01-24.0      | 39        | 19.02%  |
| 32.01-64.0      | 18        | 8.78%   |
| 1.01-2.0        | 9         | 4.39%   |
| 2.01-3.0        | 4         | 1.95%   |
| 64.01-256.0     | 4         | 1.95%   |
| 24.01-32.0      | 3         | 1.46%   |
| 0.01-0.5        | 2         | 0.98%   |
| More than 256.0 | 1         | 0.49%   |
| 0.51-1.0        | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 89        | 40.27%  |
| 2.01-3.0   | 51        | 23.08%  |
| 4.01-8.0   | 32        | 14.48%  |
| 3.01-4.0   | 23        | 10.41%  |
| 0.51-1.0   | 10        | 4.52%   |
| 8.01-16.0  | 7         | 3.17%   |
| 0.01-0.5   | 6         | 2.71%   |
| 16.01-24.0 | 2         | 0.9%    |
| 24.01-32.0 | 1         | 0.45%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 139       | 66.83%  |
| 2      | 47        | 22.6%   |
| 3      | 12        | 5.77%   |
| 4      | 7         | 3.37%   |
| 8      | 1         | 0.48%   |
| 7      | 1         | 0.48%   |
| 5      | 1         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 56.1%   |
| Yes       | 90        | 43.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 182       | 89.66%  |
| No        | 21        | 10.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 77.07%  |
| No        | 47        | 22.93%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 57%     |
| No        | 89        | 43%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Costa Rica | 203       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San José     | 87        | 38.84%  |
| Heredia       | 43        | 19.2%   |
| Alajuela      | 17        | 7.59%   |
| Escazu        | 8         | 3.57%   |
| Cartago       | 7         | 3.13%   |
| Rio Segundo   | 6         | 2.68%   |
| Quesada       | 4         | 1.79%   |
| Grecia        | 4         | 1.79%   |
| Santa Ana     | 3         | 1.34%   |
| San Ramon     | 3         | 1.34%   |
| Puntarenas    | 3         | 1.34%   |
| Liberia       | 3         | 1.34%   |
| Tres Rios     | 2         | 0.89%   |
| Siquirres     | 2         | 0.89%   |
| Santa Fe      | 2         | 0.89%   |
| Santa Cruz    | 2         | 0.89%   |
| San Pedro     | 2         | 0.89%   |
| Palmares      | 2         | 0.89%   |
| Nosara        | 2         | 0.89%   |
| Naranjo       | 2         | 0.89%   |
| Esparza       | 2         | 0.89%   |
| Curridabat    | 2         | 0.89%   |
| Zarcero       | 1         | 0.45%   |
| Tibas         | 1         | 0.45%   |
| Santo Domingo | 1         | 0.45%   |
| Santiago      | 1         | 0.45%   |
| San Pablo     | 1         | 0.45%   |
| San Juan      | 1         | 0.45%   |
| San Francisco | 1         | 0.45%   |
| Sámara       | 1         | 0.45%   |
| Quepos        | 1         | 0.45%   |
| Pavas         | 1         | 0.45%   |
| Guacima       | 1         | 0.45%   |
| Colon         | 1         | 0.45%   |
| Bajo Perez    | 1         | 0.45%   |
| Bagaces       | 1         | 0.45%   |
| Alpes         | 1         | 0.45%   |
| Alajuelita    | 1         | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 42        | 69     | 15%     |
| WDC                   | 41        | 57     | 14.64%  |
| Toshiba               | 28        | 33     | 10%     |
| Samsung Electronics   | 22        | 38     | 7.86%   |
| Kingston              | 18        | 27     | 6.43%   |
| A-DATA Technology     | 17        | 17     | 6.07%   |
| Intel                 | 15        | 27     | 5.36%   |
| Unknown               | 12        | 17     | 4.29%   |
| HGST                  | 11        | 12     | 3.93%   |
| SanDisk               | 8         | 9      | 2.86%   |
| SK hynix              | 6         | 11     | 2.14%   |
| Hitachi               | 6         | 9      | 2.14%   |
| Patriot               | 5         | 6      | 1.79%   |
| Micron Technology     | 5         | 6      | 1.79%   |
| JMicron Technology    | 5         | 5      | 1.79%   |
| Crucial               | 5         | 5      | 1.79%   |
| XPG                   | 4         | 4      | 1.43%   |
| Realtek Semiconductor | 3         | 5      | 1.07%   |
| ZOTAC                 | 2         | 3      | 0.71%   |
| Team                  | 2         | 2      | 0.71%   |
| Netac                 | 2         | 2      | 0.71%   |
| Maxtor                | 2         | 2      | 0.71%   |
| LITEONIT              | 2         | 2      | 0.71%   |
| ADATA Technology      | 2         | 2      | 0.71%   |
| Unknown               | 2         | 2      | 0.71%   |
| Zheino                | 1         | 1      | 0.36%   |
| WD MediaMax           | 1         | 1      | 0.36%   |
| UMIS                  | 1         | 1      | 0.36%   |
| Transcend             | 1         | 1      | 0.36%   |
| T-FORCE               | 1         | 1      | 0.36%   |
| Silicon Motion        | 1         | 1      | 0.36%   |
| Phison Electronics    | 1         | 1      | 0.36%   |
| KIOXIA                | 1         | 1      | 0.36%   |
| Fujitsu               | 1         | 1      | 0.36%   |
| FORESEE               | 1         | 1      | 0.36%   |
| Dell                  | 1         | 1      | 0.36%   |
| CT120BX5              | 1         | 1      | 0.36%   |
| Apple                 | 1         | 2      | 0.36%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 8         | 2.62%   |
| A-DATA SU630 480GB SSD                              | 6         | 1.97%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 1.64%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 1.64%   |
| Toshiba DT01ACA100 1TB                              | 5         | 1.64%   |
| JMicron Generic 200GB                               | 5         | 1.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 3         | 0.98%   |
| WDC WD10EZEX-75WN4A1 1TB                            | 3         | 0.98%   |
| Toshiba KBG30ZMS256G NVMe 256GB                     | 3         | 0.98%   |
| Seagate ST1000DM003-1CH162 1TB                      | 3         | 0.98%   |
| Kingston SV300S37A120G 120GB SSD                    | 3         | 0.98%   |
| Intel SSDSC2BF180A4H 180GB                          | 3         | 0.98%   |
| Intel SSDSA2CW300G3 304GB                           | 3         | 0.98%   |
| Intel H10 HBRPEKNX0203AO NVMe 32GB                  | 3         | 0.98%   |
| Intel H10 HBRPEKNX0203A NVMe 1TB                    | 3         | 0.98%   |
| HGST HTS541075A9E680 752GB                          | 3         | 0.98%   |
| HGST HTS541010A9E680 1TB                            | 3         | 0.98%   |
| XPG GAMMIX S11 Pro 512GB                            | 2         | 0.66%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.66%   |
| WDC WD5000LPCX-60VHAT0 500GB                        | 2         | 0.66%   |
| WDC WD20SPZX-08UA7 2TB                              | 2         | 0.66%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2         | 0.66%   |
| Unknown MMC Card  128GB                             | 2         | 0.66%   |
| Unknown 00000  32GB                                 | 2         | 0.66%   |
| Toshiba NVMe SSD Drive 256GB                        | 2         | 0.66%   |
| SK hynix NVMe SSD Drive 128GB                       | 2         | 0.66%   |
| Seagate ST9500325AS 500GB                           | 2         | 0.66%   |
| Seagate ST8000DM004-2CX188 8TB                      | 2         | 0.66%   |
| Seagate ST500LM021-1KJ152 500GB                     | 2         | 0.66%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 0.66%   |
| Seagate ST380815AS 80GB                             | 2         | 0.66%   |
| Seagate ST2000LM007-1R8174 2TB                      | 2         | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 2         | 0.66%   |
| Seagate ST1000DM010-2EP102 1TB                      | 2         | 0.66%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 2         | 0.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2         | 0.66%   |
| Patriot P210 256GB SSD                              | 2         | 0.66%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.66%   |
| Intel SSDSC2MH250A2 250GB                           | 2         | 0.66%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 40        | 67     | 32.52%  |
| WDC                 | 32        | 39     | 26.02%  |
| Toshiba             | 23        | 24     | 18.7%   |
| HGST                | 11        | 12     | 8.94%   |
| Hitachi             | 6         | 9      | 4.88%   |
| JMicron Technology  | 5         | 5      | 4.07%   |
| Maxtor              | 2         | 2      | 1.63%   |
| Unknown             | 1         | 1      | 0.81%   |
| Samsung Electronics | 1         | 1      | 0.81%   |
| Fujitsu             | 1         | 1      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 16        | 21     | 18.82%  |
| A-DATA Technology   | 13        | 13     | 15.29%  |
| Samsung Electronics | 10        | 22     | 11.76%  |
| Intel               | 9         | 17     | 10.59%  |
| WDC                 | 8         | 14     | 9.41%   |
| SanDisk             | 6         | 7      | 7.06%   |
| Patriot             | 4         | 5      | 4.71%   |
| Micron Technology   | 4         | 4      | 4.71%   |
| Crucial             | 4         | 4      | 4.71%   |
| ZOTAC               | 2         | 3      | 2.35%   |
| Team                | 2         | 2      | 2.35%   |
| LITEONIT            | 2         | 2      | 2.35%   |
| Transcend           | 1         | 1      | 1.18%   |
| Seagate             | 1         | 1      | 1.18%   |
| Netac               | 1         | 1      | 1.18%   |
| FORESEE             | 1         | 1      | 1.18%   |
| CT120BX5            | 1         | 1      | 1.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 111       | 162    | 42.86%  |
| SSD     | 80        | 119    | 30.89%  |
| NVMe    | 51        | 82     | 19.69%  |
| MMC     | 13        | 18     | 5.02%   |
| Unknown | 4         | 5      | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 170       | 270    | 69.39%  |
| NVMe | 51        | 82     | 20.82%  |
| MMC  | 13        | 18     | 5.31%   |
| SAS  | 11        | 16     | 4.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 118       | 161    | 59.9%   |
| 0.51-1.0   | 59        | 90     | 29.95%  |
| 1.01-2.0   | 13        | 15     | 6.6%    |
| 4.01-10.0  | 5         | 13     | 2.54%   |
| 3.01-4.0   | 1         | 1      | 0.51%   |
| 2.01-3.0   | 1         | 1      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 56        | 25.69%  |
| 251-500        | 40        | 18.35%  |
| 501-1000       | 35        | 16.06%  |
| 1-20           | 20        | 9.17%   |
| 51-100         | 20        | 9.17%   |
| 1001-2000      | 17        | 7.8%    |
| More than 3000 | 10        | 4.59%   |
| 21-50          | 10        | 4.59%   |
| 2001-3000      | 5         | 2.29%   |
| Unknown        | 5         | 2.29%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 98        | 43.36%  |
| 21-50          | 40        | 17.7%   |
| 101-250        | 24        | 10.62%  |
| 51-100         | 22        | 9.73%   |
| 251-500        | 19        | 8.41%   |
| 501-1000       | 8         | 3.54%   |
| Unknown        | 5         | 2.21%   |
| More than 3000 | 4         | 1.77%   |
| 1001-2000      | 4         | 1.77%   |
| 2001-3000      | 2         | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Intel H10 HBRPEKNX0203A NVMe 1TB                    | 3         | 3      | 14.29%  |
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 4.76%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 4.76%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 4.76%   |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 4.76%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 4.76%   |
| Seagate ST9320310AS 320GB                           | 1         | 1      | 4.76%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 4.76%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 2      | 4.76%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 1      | 4.76%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 4.76%   |
| Maxtor STM3160215AS 160GB                           | 1         | 1      | 4.76%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 4.76%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 4.76%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 4.76%   |
| Hitachi HDE721010SLA330 1TB                         | 1         | 1      | 4.76%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 4.76%   |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 4.76%   |
| A-DATA Technology SX8100NP 256GB                    | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Intel             | 4         | 4      | 19.05%  |
| Toshiba           | 3         | 3      | 14.29%  |
| Seagate           | 3         | 4      | 14.29%  |
| WDC               | 2         | 2      | 9.52%   |
| Hitachi           | 2         | 3      | 9.52%   |
| HGST              | 2         | 2      | 9.52%   |
| SanDisk           | 1         | 1      | 4.76%   |
| Micron Technology | 1         | 1      | 4.76%   |
| Maxtor            | 1         | 1      | 4.76%   |
| Kingston          | 1         | 1      | 4.76%   |
| A-DATA Technology | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 23.08%  |
| Seagate | 3         | 4      | 23.08%  |
| WDC     | 2         | 2      | 15.38%  |
| Hitachi | 2         | 3      | 15.38%  |
| HGST    | 2         | 2      | 15.38%  |
| Maxtor  | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 12        | 15     | 60%     |
| NVMe | 4         | 4      | 20%     |
| SSD  | 4         | 4      | 20%     |

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
| Detected | 124       | 215    | 54.87%  |
| Works    | 82        | 148    | 36.28%  |
| Malfunc  | 20        | 23     | 8.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 147       | 59.04%  |
| AMD                          | 37        | 14.86%  |
| Samsung Electronics          | 12        | 4.82%   |
| ASMedia Technology           | 7         | 2.81%   |
| ADATA Technology             | 7         | 2.81%   |
| SK hynix                     | 5         | 2.01%   |
| SanDisk                      | 5         | 2.01%   |
| Realtek Semiconductor        | 5         | 2.01%   |
| Toshiba America Info Systems | 4         | 1.61%   |
| Nvidia                       | 3         | 1.2%    |
| Silicon Motion               | 2         | 0.8%    |
| Micron Technology            | 2         | 0.8%    |
| Kingston Technology Company  | 2         | 0.8%    |
| Union Memory (Shenzhen)      | 1         | 0.4%    |
| Silicon Image                | 1         | 0.4%    |
| Phison Electronics           | 1         | 0.4%    |
| OCZ Technology Group         | 1         | 0.4%    |
| Micron/Crucial Technology    | 1         | 0.4%    |
| Marvell Technology Group     | 1         | 0.4%    |
| LSI Logic / Symbios Logic    | 1         | 0.4%    |
| KIOXIA                       | 1         | 0.4%    |
| JMicron Technology           | 1         | 0.4%    |
| INNOGRIT                     | 1         | 0.4%    |
| Apple                        | 1         | 0.4%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 24        | 8.66%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 13        | 4.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 13        | 4.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 12        | 4.33%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 3.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 9         | 3.25%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 8         | 2.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 2.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 8         | 2.89%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 7         | 2.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 2.17%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 6         | 2.17%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 5         | 1.81%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 1.81%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 5         | 1.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 1.44%   |
| Intel SATA Controller [RAID mode]                                                      | 4         | 1.44%   |
| Intel Non-Volatile memory controller                                                   | 4         | 1.44%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 1.44%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 4         | 1.44%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 1.08%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.08%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 3         | 1.08%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 1.08%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.08%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 1.08%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 3         | 1.08%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.08%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 3         | 1.08%   |
| AMD 400 Series Chipset SATA Controller                                                 | 3         | 1.08%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.72%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 0.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 2         | 0.72%   |
| Realtek Realtek Non-Volatile memory controller                                         | 2         | 0.72%   |
| Micron Non-Volatile memory controller                                                  | 2         | 0.72%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 2         | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 0.72%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 0.72%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 0.72%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                              | 2         | 0.72%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 152       | 60.32%  |
| NVMe | 52        | 20.63%  |
| IDE  | 27        | 10.71%  |
| RAID | 19        | 7.54%   |
| SAS  | 1         | 0.4%    |
| SCSI | 1         | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 158       | 77.83%  |
| AMD    | 42        | 20.69%  |
| ARM    | 3         | 1.48%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz                | 5         | 2.46%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 4         | 1.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 4         | 1.97%   |
| AMD Ryzen 5 3600 6-Core Processor               | 4         | 1.97%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 3         | 1.48%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 3         | 1.48%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 3         | 1.48%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 3         | 1.48%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 3         | 1.48%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 3         | 1.48%   |
| ARM BCM2835 Processor                           | 3         | 1.48%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 0.99%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 0.99%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 0.99%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 2         | 0.99%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 0.99%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 2         | 0.99%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 0.99%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 2         | 0.99%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 0.99%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 0.99%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 2         | 0.99%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 2         | 0.99%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 2         | 0.99%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 2         | 0.99%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 2         | 0.99%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 2         | 0.99%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 2         | 0.99%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 2         | 0.99%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 2         | 0.99%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 0.99%   |
| AMD E1-1200 APU with Radeon HD Graphics         | 2         | 0.99%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 2         | 0.99%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz            | 1         | 0.49%   |
| Intel Xeon CPU X5667 @ 3.07GHz                  | 1         | 0.49%   |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1         | 0.49%   |
| Intel Xeon CPU E5405 @ 2.00GHz                  | 1         | 0.49%   |
| Intel Xeon CPU E5-2660 v2 @ 2.20GHz             | 1         | 0.49%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz             | 1         | 0.49%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz            | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 44        | 21.67%  |
| Intel Core i7                  | 38        | 18.72%  |
| Intel Core i3                  | 21        | 10.34%  |
| Intel Celeron                  | 15        | 7.39%   |
| Other                          | 13        | 6.4%    |
| AMD Ryzen 5                    | 9         | 4.43%   |
| AMD Ryzen 7                    | 8         | 3.94%   |
| Intel Xeon                     | 6         | 2.96%   |
| AMD FX                         | 5         | 2.46%   |
| Intel Pentium                  | 4         | 1.97%   |
| Intel Core 2 Duo               | 4         | 1.97%   |
| Intel Core 2                   | 4         | 1.97%   |
| AMD E1                         | 4         | 1.97%   |
| Intel Atom                     | 3         | 1.48%   |
| ARM BCM                        | 3         | 1.48%   |
| AMD Ryzen 3                    | 3         | 1.48%   |
| Intel Genuine                  | 2         | 0.99%   |
| AMD A8                         | 2         | 0.99%   |
| AMD A10                        | 2         | 0.99%   |
| Intel Xeon Silver              | 1         | 0.49%   |
| Intel Pentium Dual-Core        | 1         | 0.49%   |
| Intel Pentium 4                | 1         | 0.49%   |
| Intel Core i9                  | 1         | 0.49%   |
| Intel Core 2 Quad              | 1         | 0.49%   |
| AMD V120                       | 1         | 0.49%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.49%   |
| AMD Turion 64 X2               | 1         | 0.49%   |
| AMD Sempron                    | 1         | 0.49%   |
| AMD Ryzen 7 PRO                | 1         | 0.49%   |
| AMD Phenom II X4               | 1         | 0.49%   |
| AMD E2                         | 1         | 0.49%   |
| AMD Athlon                     | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 94        | 46.31%  |
| 4      | 66        | 32.51%  |
| 6      | 18        | 8.87%   |
| 8      | 12        | 5.91%   |
| 1      | 7         | 3.45%   |
| 10     | 2         | 0.99%   |
| 20     | 1         | 0.49%   |
| 16     | 1         | 0.49%   |
| 12     | 1         | 0.49%   |
| 3      | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 201       | 99.01%  |
| 2      | 2         | 0.99%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 124       | 61.08%  |
| 1      | 79        | 38.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 196       | 96.08%  |
| Unknown        | 6         | 2.94%   |
| 32-bit         | 2         | 0.98%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 42        | 20.1%   |
| 0x306c3    | 12        | 5.74%   |
| 0x206a7    | 12        | 5.74%   |
| 0x306a9    | 9         | 4.31%   |
| 0x40651    | 7         | 3.35%   |
| 0x08108109 | 7         | 3.35%   |
| 0x806e9    | 6         | 2.87%   |
| 0x506e3    | 6         | 2.87%   |
| 0x306d4    | 6         | 2.87%   |
| 0x906ea    | 5         | 2.39%   |
| 0x906e9    | 5         | 2.39%   |
| 0x806c1    | 5         | 2.39%   |
| 0x406c4    | 5         | 2.39%   |
| 0x806ec    | 4         | 1.91%   |
| 0x706a1    | 4         | 1.91%   |
| 0x406e3    | 4         | 1.91%   |
| 0x08701021 | 4         | 1.91%   |
| 0x806eb    | 3         | 1.44%   |
| 0x806ea    | 3         | 1.44%   |
| 0x20655    | 3         | 1.44%   |
| 0x05000119 | 3         | 1.44%   |
| 0x906eb    | 2         | 0.96%   |
| 0x706a8    | 2         | 0.96%   |
| 0x6fd      | 2         | 0.96%   |
| 0x6f6      | 2         | 0.96%   |
| 0x306e4    | 2         | 0.96%   |
| 0x30678    | 2         | 0.96%   |
| 0x1067a    | 2         | 0.96%   |
| 0x10676    | 2         | 0.96%   |
| 0x08600104 | 2         | 0.96%   |
| 0x07030105 | 2         | 0.96%   |
| 0x06000852 | 2         | 0.96%   |
| 0x010000c8 | 2         | 0.96%   |
| 0xf49      | 1         | 0.48%   |
| 0xf29      | 1         | 0.48%   |
| 0xa0652    | 1         | 0.48%   |
| 0x906ed    | 1         | 0.48%   |
| 0x906ec    | 1         | 0.48%   |
| 0x906a3    | 1         | 0.48%   |
| 0x90675    | 1         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 17.24%  |
| Haswell          | 22        | 10.84%  |
| SandyBridge      | 18        | 8.87%   |
| Skylake          | 13        | 6.4%    |
| IvyBridge        | 11        | 5.42%   |
| Zen+             | 9         | 4.43%   |
| Zen 2            | 9         | 4.43%   |
| Unknown          | 9         | 4.43%   |
| Silvermont       | 8         | 3.94%   |
| TigerLake        | 6         | 2.96%   |
| Penryn           | 6         | 2.96%   |
| Goldmont plus    | 6         | 2.96%   |
| Core             | 6         | 2.96%   |
| Broadwell        | 6         | 2.96%   |
| Westmere         | 4         | 1.97%   |
| Piledriver       | 4         | 1.97%   |
| K10              | 3         | 1.48%   |
| Excavator        | 3         | 1.48%   |
| Bobcat           | 3         | 1.48%   |
| Zen 3            | 2         | 0.99%   |
| Puma             | 2         | 0.99%   |
| NetBurst         | 2         | 0.99%   |
| Nehalem          | 2         | 0.99%   |
| IceLake          | 2         | 0.99%   |
| CometLake        | 2         | 0.99%   |
| Alderlake Hybrid | 2         | 0.99%   |
| P6               | 1         | 0.49%   |
| K8 Hammer        | 1         | 0.49%   |
| K8 & K10 hybrid  | 1         | 0.49%   |
| K10 Llano        | 1         | 0.49%   |
| Jaguar           | 1         | 0.49%   |
| Goldmont         | 1         | 0.49%   |
| Bulldozer        | 1         | 0.49%   |
| Bonnell          | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 133       | 57.83%  |
| Nvidia | 52        | 22.61%  |
| AMD    | 45        | 19.57%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 6.15%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 3.28%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.87%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 2.46%   |
| Intel HD Graphics 620                                                                    | 6         | 2.46%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.46%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.46%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.05%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 5         | 2.05%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5         | 2.05%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 1.64%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.64%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.64%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.64%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.64%   |
| Intel HD Graphics 630                                                                    | 4         | 1.64%   |
| Intel HD Graphics 530                                                                    | 4         | 1.64%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.64%   |
| AMD Renoir                                                                               | 4         | 1.64%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.64%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.23%   |
| Intel DG1 [Iris Xe MAX Graphics]                                                         | 3         | 1.23%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.23%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.23%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.82%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2         | 0.82%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.82%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.82%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.82%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.82%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.82%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.82%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.82%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 105       | 51.22%  |
| 1 x AMD        | 34        | 16.59%  |
| 1 x Nvidia     | 28        | 13.66%  |
| Intel + Nvidia | 21        | 10.24%  |
| 2 x AMD        | 6         | 2.93%   |
| Other          | 3         | 1.46%   |
| 2 x Intel      | 3         | 1.46%   |
| AMD + Nvidia   | 3         | 1.46%   |
| Intel + AMD    | 2         | 0.98%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 172       | 83.09%  |
| Proprietary | 29        | 14.01%  |
| Unknown     | 6         | 2.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 131       | 62.38%  |
| 1.01-2.0   | 26        | 12.38%  |
| 0.01-0.5   | 18        | 8.57%   |
| 3.01-4.0   | 12        | 5.71%   |
| 0.51-1.0   | 12        | 5.71%   |
| 5.01-6.0   | 7         | 3.33%   |
| 7.01-8.0   | 3         | 1.43%   |
| 8.01-16.0  | 1         | 0.48%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 35        | 14.4%   |
| AOC                     | 25        | 10.29%  |
| LG Display              | 22        | 9.05%   |
| Samsung Electronics     | 20        | 8.23%   |
| BOE                     | 20        | 8.23%   |
| Dell                    | 17        | 7%      |
| Chimei Innolux          | 17        | 7%      |
| Hewlett-Packard         | 15        | 6.17%   |
| Goldstar                | 10        | 4.12%   |
| Apple                   | 6         | 2.47%   |
| ViewSonic               | 5         | 2.06%   |
| Acer                    | 5         | 2.06%   |
| Sony                    | 4         | 1.65%   |
| Chi Mei Optoelectronics | 4         | 1.65%   |
| BenQ                    | 3         | 1.23%   |
| ASUSTek Computer        | 3         | 1.23%   |
| AGO                     | 3         | 1.23%   |
| Sharp                   | 2         | 0.82%   |
| Panasonic               | 2         | 0.82%   |
| MSI                     | 2         | 0.82%   |
| Lenovo                  | 2         | 0.82%   |
| CPT                     | 2         | 0.82%   |
| Ancor Communications    | 2         | 0.82%   |
| Xerox                   | 1         | 0.41%   |
| Unknown (XXX)           | 1         | 0.41%   |
| Sun                     | 1         | 0.41%   |
| RTK                     | 1         | 0.41%   |
| Royal Information       | 1         | 0.41%   |
| PRISM+                  | 1         | 0.41%   |
| Philips                 | 1         | 0.41%   |
| PAR                     | 1         | 0.41%   |
| LTM                     | 1         | 0.41%   |
| LG Philips              | 1         | 0.41%   |
| KDC                     | 1         | 0.41%   |
| Hitachi                 | 1         | 0.41%   |
| Haier                   | 1         | 0.41%   |
| GAOMON                  | 1         | 0.41%   |
| Envision                | 1         | 0.41%   |
| CVT                     | 1         | 0.41%   |
| ASR                     | 1         | 0.41%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                  | 5         | 1.99%   |
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5         | 1.99%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 4         | 1.59%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3         | 1.2%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 1.2%    |
| AU Optronics LCD Monitor AUO35EB 3840x2160 344x193mm 15.5-inch       | 3         | 1.2%    |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch       | 3         | 1.2%    |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 3         | 1.2%    |
| Sony TV SNY1B02 1360x768                                             | 2         | 0.8%    |
| Sony TV SNY0902 1360x768                                             | 2         | 0.8%    |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2         | 0.8%    |
| Panasonic TV MEIA296 3840x2160 1872x1053mm 84.6-inch                 | 2         | 0.8%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 2         | 0.8%    |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.8%    |
| Hewlett-Packard LCD Monitor E232 2944x1080                           | 2         | 0.8%    |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2         | 0.8%    |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch          | 2         | 0.8%    |
| Dell E207WFP DELD011 1680x1050 430x270mm 20.0-inch                   | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 0.8%    |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.8%    |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 2         | 0.8%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.8%    |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 2         | 0.8%    |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 2         | 0.8%    |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                   | 1         | 0.4%    |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch        | 1         | 0.4%    |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch        | 1         | 0.4%    |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch            | 1         | 0.4%    |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                           | 1         | 0.4%    |
| ViewSonic LCD Monitor VX2260WM                                       | 1         | 0.4%    |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1         | 0.4%    |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch               | 1         | 0.4%    |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 1         | 0.4%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 1         | 0.4%    |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch    | 1         | 0.4%    |
| Samsung Electronics SyncMaster SAM058A 1920x1080 531x298mm 24.0-inch | 1         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 84        | 36.21%  |
| 1366x768 (WXGA)    | 61        | 26.29%  |
| 3840x2160 (4K)     | 19        | 8.19%   |
| 1600x900 (HD+)     | 13        | 5.6%    |
| 1440x900 (WXGA+)   | 10        | 4.31%   |
| 1280x800 (WXGA)    | 10        | 4.31%   |
| 1280x1024 (SXGA)   | 10        | 4.31%   |
| 2560x1440 (QHD)    | 5         | 2.16%   |
| 1360x768           | 3         | 1.29%   |
| 3286x1080          | 2         | 0.86%   |
| 2944x1080          | 2         | 0.86%   |
| 2560x1080          | 2         | 0.86%   |
| 1920x1200 (WUXGA)  | 2         | 0.86%   |
| 1680x1050 (WSXGA+) | 2         | 0.86%   |
| 1280x720 (HD)      | 2         | 0.86%   |
| Unknown            | 2         | 0.86%   |
| 3840x2400          | 1         | 0.43%   |
| 1400x1050          | 1         | 0.43%   |
| 1280x960           | 1         | 0.43%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 62        | 25.41%  |
| 14      | 26        | 10.66%  |
| 13      | 24        | 9.84%   |
| 23      | 17        | 6.97%   |
| 24      | 15        | 6.15%   |
| 19      | 15        | 6.15%   |
| 17      | 13        | 5.33%   |
| 18      | 10        | 4.1%    |
| 21      | 9         | 3.69%   |
| Unknown | 9         | 3.69%   |
| 27      | 8         | 3.28%   |
| 84      | 4         | 1.64%   |
| 72      | 4         | 1.64%   |
| 12      | 4         | 1.64%   |
| 31      | 3         | 1.23%   |
| 20      | 3         | 1.23%   |
| 11      | 3         | 1.23%   |
| 57      | 2         | 0.82%   |
| 43      | 2         | 0.82%   |
| 34      | 2         | 0.82%   |
| 32      | 2         | 0.82%   |
| 16      | 2         | 0.82%   |
| 58      | 1         | 0.41%   |
| 54      | 1         | 0.41%   |
| 40      | 1         | 0.41%   |
| 36      | 1         | 0.41%   |
| 22      | 1         | 0.41%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 110       | 45.64%  |
| 501-600     | 39        | 16.18%  |
| 401-500     | 34        | 14.11%  |
| 201-300     | 16        | 6.64%   |
| 351-400     | 10        | 4.15%   |
| Unknown     | 9         | 3.73%   |
| 1501-2000   | 8         | 3.32%   |
| 701-800     | 6         | 2.49%   |
| 601-700     | 3         | 1.24%   |
| 1001-1500   | 3         | 1.24%   |
| 901-1000    | 2         | 0.83%   |
| 801-900     | 1         | 0.41%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 159       | 75.36%  |
| 16/10   | 26        | 12.32%  |
| 5/4     | 9         | 4.27%   |
| Unknown | 9         | 4.27%   |
| 4/3     | 5         | 2.37%   |
| 21/9    | 2         | 0.95%   |
| 0.56    | 1         | 0.47%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 61        | 25.1%   |
| 81-90          | 46        | 18.93%  |
| 201-250        | 31        | 12.76%  |
| 151-200        | 23        | 9.47%   |
| 141-150        | 14        | 5.76%   |
| More than 1000 | 12        | 4.94%   |
| Unknown        | 9         | 3.7%    |
| 301-350        | 8         | 3.29%   |
| 351-500        | 7         | 2.88%   |
| 251-300        | 7         | 2.88%   |
| 71-80          | 6         | 2.47%   |
| 121-130        | 5         | 2.06%   |
| 501-1000       | 4         | 1.65%   |
| 51-60          | 3         | 1.23%   |
| 111-120        | 3         | 1.23%   |
| 131-140        | 2         | 0.82%   |
| 61-70          | 1         | 0.41%   |
| 91-100         | 1         | 0.41%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 77        | 32.63%  |
| 101-120       | 71        | 30.08%  |
| 121-160       | 54        | 22.88%  |
| 1-50          | 11        | 4.66%   |
| Unknown       | 9         | 3.81%   |
| More than 240 | 7         | 2.97%   |
| 161-240       | 7         | 2.97%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 157       | 73.71%  |
| 2     | 46        | 21.6%   |
| 0     | 7         | 3.29%   |
| 3     | 3         | 1.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 119       | 38.26%  |
| Intel                           | 81        | 26.05%  |
| Qualcomm Atheros                | 42        | 13.5%   |
| Broadcom                        | 22        | 7.07%   |
| TP-Link                         | 8         | 2.57%   |
| Broadcom Limited                | 8         | 2.57%   |
| Xiaomi                          | 3         | 0.96%   |
| Ralink                          | 3         | 0.96%   |
| Nvidia                          | 3         | 0.96%   |
| MediaTek                        | 3         | 0.96%   |
| Microchip Technology            | 2         | 0.64%   |
| Linksys                         | 2         | 0.64%   |
| Huawei Technologies             | 2         | 0.64%   |
| ASIX Electronics                | 2         | 0.64%   |
| Standard Microsystems           | 1         | 0.32%   |
| Ralink Technology               | 1         | 0.32%   |
| Qualcomm Atheros Communications | 1         | 0.32%   |
| Marvell Technology Group        | 1         | 0.32%   |
| Lenovo                          | 1         | 0.32%   |
| JMicron Technology              | 1         | 0.32%   |
| Hewlett-Packard                 | 1         | 0.32%   |
| DisplayLink                     | 1         | 0.32%   |
| Dell                            | 1         | 0.32%   |
| Davicom Semiconductor           | 1         | 0.32%   |
| D-Link                          | 1         | 0.32%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 19.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 6.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 2.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.41%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 1.88%   |
| Intel Wireless 7265                                               | 7         | 1.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.61%   |
| Intel Wireless 7260                                               | 6         | 1.61%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.61%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 5         | 1.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 1.34%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.34%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.07%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.07%   |
| Intel Wi-Fi 6 AX201                                               | 4         | 1.07%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.07%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.07%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 1.07%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.8%    |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                         | 3         | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.8%    |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.8%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.8%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.8%    |
| Intel Wireless 8265 / 8275                                        | 3         | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.8%    |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.54%   |
| Realtek 802.11ac NIC                                              | 2         | 0.54%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.54%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.54%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 2         | 0.54%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 61        | 36.53%  |
| Qualcomm Atheros                | 33        | 19.76%  |
| Realtek Semiconductor           | 32        | 19.16%  |
| Broadcom                        | 15        | 8.98%   |
| TP-Link                         | 8         | 4.79%   |
| Broadcom Limited                | 7         | 4.19%   |
| Ralink                          | 3         | 1.8%    |
| MediaTek                        | 2         | 1.2%    |
| Linksys                         | 2         | 1.2%    |
| Ralink Technology               | 1         | 0.6%    |
| Qualcomm Atheros Communications | 1         | 0.6%    |
| Dell                            | 1         | 0.6%    |
| D-Link                          | 1         | 0.6%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 5.29%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 4.12%   |
| Intel Wireless 7265                                            | 7         | 4.12%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 3.53%   |
| Intel Wireless 7260                                            | 6         | 3.53%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 3.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 3.53%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 3.53%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 5         | 2.94%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.35%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 2.35%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 2.35%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                      | 3         | 1.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.76%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.76%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 1.76%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 1.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.76%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 1.18%   |
| Realtek 802.11ac NIC                                           | 2         | 1.18%   |
| Intel Wireless-AC 9260                                         | 2         | 1.18%   |
| Intel Wireless 8260                                            | 2         | 1.18%   |
| Intel Wireless 3160                                            | 2         | 1.18%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.18%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.18%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2         | 1.18%   |
| Broadcom Limited BCM4311 802.11a/b/g                           | 2         | 1.18%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.18%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.59%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1         | 0.59%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.59%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.59%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.59%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.59%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 107       | 54.87%  |
| Intel                    | 42        | 21.54%  |
| Broadcom                 | 14        | 7.18%   |
| Qualcomm Atheros         | 12        | 6.15%   |
| Xiaomi                   | 3         | 1.54%   |
| Nvidia                   | 3         | 1.54%   |
| Microchip Technology     | 2         | 1.03%   |
| Huawei Technologies      | 2         | 1.03%   |
| ASIX Electronics         | 2         | 1.03%   |
| Standard Microsystems    | 1         | 0.51%   |
| MediaTek                 | 1         | 0.51%   |
| Marvell Technology Group | 1         | 0.51%   |
| Lenovo                   | 1         | 0.51%   |
| JMicron Technology       | 1         | 0.51%   |
| DisplayLink              | 1         | 0.51%   |
| Davicom Semiconductor    | 1         | 0.51%   |
| Broadcom Limited         | 1         | 0.51%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 71        | 35.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 11.39%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 9         | 4.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.48%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.98%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.98%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.49%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.49%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.49%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.99%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.99%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 2         | 0.99%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.99%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.99%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.99%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.99%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.99%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.99%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.99%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.5%    |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.5%    |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.5%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.5%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.5%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 1         | 0.5%    |
| Nvidia MCP67 Ethernet                                             | 1         | 0.5%    |
| Nvidia MCP61 Ethernet                                             | 1         | 0.5%    |
| MediaTek moto e(6) plus                                           | 1         | 0.5%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.5%    |
| Lenovo Thinkpad LAN                                               | 1         | 0.5%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.5%    |
| Intel PRO/100 VE Network Connection                               | 1         | 0.5%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 181       | 53.24%  |
| WiFi     | 158       | 46.47%  |
| Modem    | 1         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 119       | 56.67%  |
| Ethernet | 91        | 43.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 127       | 61.35%  |
| 1     | 66        | 31.88%  |
| 0     | 7         | 3.38%   |
| 3     | 6         | 2.9%    |
| 4     | 1         | 0.48%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 202       | 98.54%  |
| Yes  | 3         | 1.46%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 41.67%  |
| Realtek Semiconductor           | 15        | 12.5%   |
| Qualcomm Atheros Communications | 14        | 11.67%  |
| Cambridge Silicon Radio         | 9         | 7.5%    |
| Broadcom                        | 8         | 6.67%   |
| Apple                           | 6         | 5%      |
| Lite-On Technology              | 4         | 3.33%   |
| Toshiba                         | 3         | 2.5%    |
| IMC Networks                    | 2         | 1.67%   |
| Foxconn / Hon Hai               | 2         | 1.67%   |
| ASUSTek Computer                | 2         | 1.67%   |
| Realtek                         | 1         | 0.83%   |
| MediaTek                        | 1         | 0.83%   |
| Marvell Semiconductor           | 1         | 0.83%   |
| Hewlett-Packard                 | 1         | 0.83%   |
| Dell                            | 1         | 0.83%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                           | 18        | 15%     |
| Qualcomm Atheros  Bluetooth Device                           | 9         | 7.5%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 9         | 7.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 9         | 7.5%    |
| Realtek Bluetooth Radio                                      | 8         | 6.67%   |
| Realtek  Bluetooth 4.2 Adapter                               | 7         | 5.83%   |
| Intel AX201 Bluetooth                                        | 6         | 5%      |
| Intel AX200 Bluetooth                                        | 6         | 5%      |
| Apple Bluetooth Host Controller                              | 4         | 3.33%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                       | 3         | 2.5%    |
| Intel Centrino Bluetooth Wireless Transceiver                | 3         | 2.5%    |
| Broadcom BCM43142A0 Bluetooth 4.0                            | 3         | 2.5%    |
| Toshiba Bluetooth Device                                     | 2         | 1.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                   | 2         | 1.67%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 2         | 1.67%   |
| Intel Wireless-AC 3168 Bluetooth                             | 2         | 1.67%   |
| Intel Bluetooth Device                                       | 2         | 1.67%   |
| Intel AX210 Bluetooth                                        | 2         | 1.67%   |
| Toshiba BCM43142A0                                           | 1         | 0.83%   |
| Realtek 802.11ac WLAN Adapter                                | 1         | 0.83%   |
| Qualcomm Atheros Bluetooth USB Host Controller               | 1         | 0.83%   |
| Qualcomm Atheros AR3011 Bluetooth                            | 1         | 0.83%   |
| MediaTek Wireless_Device                                     | 1         | 0.83%   |
| Marvell Bluetooth and Wireless LAN Composite Device          | 1         | 0.83%   |
| Lite-On Wireless_Device                                      | 1         | 0.83%   |
| Lite-On Bluetooth Device                                     | 1         | 0.83%   |
| IMC Networks Bluetooth Radio                                 | 1         | 0.83%   |
| IMC Networks Bluetooth                                       | 1         | 0.83%   |
| HP Broadcom 2070 Bluetooth Combo                             | 1         | 0.83%   |
| Foxconn / Hon Hai Bluetooth Device                           | 1         | 0.83%   |
| Foxconn / Hon Hai BCM20702A0                                 | 1         | 0.83%   |
| Dell Broadcom BCM20702A0 Bluetooth                           | 1         | 0.83%   |
| Broadcom HP Portable SoftSailing                             | 1         | 0.83%   |
| Broadcom HP Portable Bumble Bee                              | 1         | 0.83%   |
| Broadcom BCM43142 Bluetooth 4.0                              | 1         | 0.83%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                         | 1         | 0.83%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1         | 0.83%   |
| ASUS Qualcomm Bluetooth 4.1                                  | 1         | 0.83%   |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 1         | 0.83%   |
| Apple Bluetooth USB Host Controller                          | 1         | 0.83%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 154       | 55.8%   |
| AMD                     | 51        | 18.48%  |
| Nvidia                  | 41        | 14.86%  |
| C-Media Electronics     | 4         | 1.45%   |
| Generalplus Technology  | 3         | 1.09%   |
| Sony                    | 2         | 0.72%   |
| Logitech                | 2         | 0.72%   |
| JMTek                   | 2         | 0.72%   |
| GN Netcom               | 2         | 0.72%   |
| Soundprese              | 1         | 0.36%   |
| Realtek Semiconductor   | 1         | 0.36%   |
| Plantronics             | 1         | 0.36%   |
| Medeli Electronics      | 1         | 0.36%   |
| Lenovo                  | 1         | 0.36%   |
| Ensoniq                 | 1         | 0.36%   |
| DCMT Technology         | 1         | 0.36%   |
| Corsair                 | 1         | 0.36%   |
| CMX Systems             | 1         | 0.36%   |
| Blue Microphones        | 1         | 0.36%   |
| BEHRINGER International | 1         | 0.36%   |
| Astro Gaming            | 1         | 0.36%   |
| Argosy Research         | 1         | 0.36%   |
| Afatech                 | 1         | 0.36%   |
| A-DATA Technology       | 1         | 0.36%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 5.15%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 4.55%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 4.24%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 14        | 4.24%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 3.64%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 3.03%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 3.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.73%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 2.73%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.42%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.42%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 2.12%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.12%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 2.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 1.82%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.82%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.82%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.82%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.52%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.21%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.21%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.21%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.21%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.21%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.91%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.91%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.91%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 0.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 0.91%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.91%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.91%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.91%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.61%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 2         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 31        | 23.66%  |
| SK hynix            | 21        | 16.03%  |
| Kingston            | 20        | 15.27%  |
| Micron Technology   | 19        | 14.5%   |
| Crucial             | 8         | 6.11%   |
| Corsair             | 8         | 6.11%   |
| Unknown             | 5         | 3.82%   |
| A-DATA Technology   | 5         | 3.82%   |
| Team                | 4         | 3.05%   |
| Nanya Technology    | 4         | 3.05%   |
| Patriot             | 2         | 1.53%   |
| Unknown (ABCD)      | 1         | 0.76%   |
| Super Talent        | 1         | 0.76%   |
| Kimtigo             | 1         | 0.76%   |
| G.Skill             | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 5         | 3.31%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 4         | 2.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.65%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s                      | 4         | 2.65%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s                      | 4         | 2.65%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.99%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.99%   |
| Micron RAM 53E1G32D2NP-046 8GB Row Of Chips LPDDR4 4267MT/s      | 3         | 1.99%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s            | 3         | 1.99%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 1.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.32%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.32%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 2         | 1.32%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.32%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM 1334MT/s                  | 2         | 1.32%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.32%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s             | 2         | 1.32%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.66%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.66%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 0.66%   |
| Super Talent RAM SUPERTALENT02 4GB SODIMM DDR3 1600MT/s          | 1         | 0.66%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1867MT/s                  | 1         | 0.66%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                      | 1         | 0.66%   |
| SK hynix RAM HMT451U6BFR8C-PB 4096MB DIMM DDR3 1600MT/s          | 1         | 0.66%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s          | 1         | 0.66%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.66%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.66%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.66%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.66%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.66%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.66%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 51        | 45.95%  |
| DDR3    | 45        | 40.54%  |
| LPDDR4  | 5         | 4.5%    |
| SDRAM   | 4         | 3.6%    |
| DDR2    | 4         | 3.6%    |
| DDR5    | 1         | 0.9%    |
| Unknown | 1         | 0.9%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 72        | 66.67%  |
| DIMM         | 29        | 26.85%  |
| Row Of Chips | 6         | 5.56%   |
| Chip         | 1         | 0.93%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 49        | 39.52%  |
| 8192  | 41        | 33.06%  |
| 16384 | 14        | 11.29%  |
| 2048  | 12        | 9.68%   |
| 32768 | 8         | 6.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 33        | 25.98%  |
| 2667    | 24        | 18.9%   |
| 1333    | 11        | 8.66%   |
| 3200    | 8         | 6.3%    |
| 2400    | 7         | 5.51%   |
| 1334    | 5         | 3.94%   |
| 667     | 5         | 3.94%   |
| 3266    | 4         | 3.15%   |
| 2133    | 4         | 3.15%   |
| 4267    | 3         | 2.36%   |
| 2933    | 3         | 2.36%   |
| 4199    | 2         | 1.57%   |
| 3600    | 2         | 1.57%   |
| 3400    | 2         | 1.57%   |
| Unknown | 2         | 1.57%   |
| 8400    | 1         | 0.79%   |
| 4800    | 1         | 0.79%   |
| 3866    | 1         | 0.79%   |
| 3466    | 1         | 0.79%   |
| 3100    | 1         | 0.79%   |
| 2934    | 1         | 0.79%   |
| 2800    | 1         | 0.79%   |
| 2666    | 1         | 0.79%   |
| 1867    | 1         | 0.79%   |
| 1866    | 1         | 0.79%   |
| 1800    | 1         | 0.79%   |
| 1067    | 1         | 0.79%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 3         | 37.5%   |
| Hewlett-Packard | 3         | 37.5%   |
| Canon           | 2         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L380 Series            | 1         | 12.5%   |
| Seiko Epson L3110 Series           | 1         | 12.5%   |
| Seiko Epson L220 Series            | 1         | 12.5%   |
| HP DeskJet 2620 All-in-One Printer | 1         | 12.5%   |
| HP DeskJet 2130 series             | 1         | 12.5%   |
| HP Deskjet 2050 J510               | 1         | 12.5%   |
| Canon G2000 series                 | 1         | 12.5%   |
| Canon E400 series                  | 1         | 12.5%   |

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
| Chicony Electronics                    | 29        | 20.42%  |
| Microdia                               | 16        | 11.27%  |
| Realtek Semiconductor                  | 14        | 9.86%   |
| IMC Networks                           | 13        | 9.15%   |
| Sunplus Innovation Technology          | 10        | 7.04%   |
| Logitech                               | 9         | 6.34%   |
| Apple                                  | 7         | 4.93%   |
| Microsoft                              | 5         | 3.52%   |
| Quanta                                 | 4         | 2.82%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.82%   |
| Suyin                                  | 3         | 2.11%   |
| Lite-On Technology                     | 3         | 2.11%   |
| Alcor Micro                            | 3         | 2.11%   |
| Acer                                   | 3         | 2.11%   |
| Z-Star Microelectronics                | 2         | 1.41%   |
| Syntek                                 | 2         | 1.41%   |
| Primax Electronics                     | 2         | 1.41%   |
| Luxvisions Innotech Limited            | 2         | 1.41%   |
| TANDBERG                               | 1         | 0.7%    |
| Silicon Motion                         | 1         | 0.7%    |
| Philips (or NXP)                       | 1         | 0.7%    |
| LG Electronics                         | 1         | 0.7%    |
| Importek                               | 1         | 0.7%    |
| Huawei Technologies                    | 1         | 0.7%    |
| GEMBIRD                                | 1         | 0.7%    |
| Creative Technology                    | 1         | 0.7%    |
| Aveo Technology                        | 1         | 0.7%    |
| Arkmicro Technologies                  | 1         | 0.7%    |
| Alpha Imaging Technology               | 1         | 0.7%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 9         | 6.21%   |
| Chicony Integrated Camera                        | 7         | 4.83%   |
| Realtek Integrated_Webcam_HD                     | 6         | 4.14%   |
| IMC Networks Integrated Camera                   | 5         | 3.45%   |
| Sunplus HD WebCam                                | 4         | 2.76%   |
| Apple FaceTime HD Camera                         | 4         | 2.76%   |
| Sunplus Integrated_Webcam_HD                     | 3         | 2.07%   |
| Microsoft LifeCam HD-3000                        | 3         | 2.07%   |
| Logitech Webcam C270                             | 3         | 2.07%   |
| Chicony TOSHIBA Web Camera - HD                  | 3         | 2.07%   |
| Syntek EasyCamera                                | 2         | 1.38%   |
| Realtek Integrated Webcam HD                     | 2         | 1.38%   |
| Realtek Integrated Webcam                        | 2         | 1.38%   |
| Quanta HD WebCam                                 | 2         | 1.38%   |
| Microdia USB 2.0 Camera                          | 2         | 1.38%   |
| Microdia Integrated Webcam                       | 2         | 1.38%   |
| Microdia Integrated Camera                       | 2         | 1.38%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 1.38%   |
| IMC Networks USB2.0 HD UVC WebCam                | 2         | 1.38%   |
| Chicony USB 2.0 Camera                           | 2         | 1.38%   |
| Chicony Integrated HP HD Webcam                  | 2         | 1.38%   |
| Chicony HP Truevision HD                         | 2         | 1.38%   |
| Chicony HP HD Webcam                             | 2         | 1.38%   |
| Chicony 720p HD Camera                           | 2         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.38%   |
| Z-Star Vimicro USB Camera (Altair)               | 1         | 0.69%   |
| Z-Star Vega USB2.0 Camera                        | 1         | 0.69%   |
| TANDBERG PrecisionHD Camera                      | 1         | 0.69%   |
| Suyin TOSHIBA Web Camera - HD                    | 1         | 0.69%   |
| Suyin HP TrueVision HD                           | 1         | 0.69%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.69%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 1         | 0.69%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.69%   |
| Sunplus Dell Integrated Webcam                   | 1         | 0.69%   |
| Silicon Motion Silicon Motion Camera             | 1         | 0.69%   |
| Realtek USB Camera                               | 1         | 0.69%   |
| Realtek Rear Camera                              | 1         | 0.69%   |
| Realtek HP Wide Vision FHD Camera                | 1         | 0.69%   |
| Realtek HP Truevision HD                         | 1         | 0.69%   |
| Realtek Front Camera                             | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 47.83%  |
| Synaptics                  | 5         | 21.74%  |
| Shenzhen Goodix Technology | 2         | 8.7%    |
| STMicroelectronics         | 1         | 4.35%   |
| Samsung Electronics        | 1         | 4.35%   |
| LighTuning Technology      | 1         | 4.35%   |
| Elan Microelectronics      | 1         | 4.35%   |
| AuthenTec                  | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 3         | 13.04%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 13.04%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 8.7%    |
| Validity Sensors Synaptics WBDI                   | 2         | 8.7%    |
| Shenzhen Goodix  Fingerprint Device               | 2         | 8.7%    |
| Unknown                                           | 2         | 8.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 4.35%   |
| Validity Sensors VFS491                           | 1         | 4.35%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 4.35%   |
| Validity Sensors Fingerprint scanner              | 1         | 4.35%   |
| STMicroelectronics Fingerprint Reader             | 1         | 4.35%   |
| Samsung Fingerprint Device                        | 1         | 4.35%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 4.35%   |
| Elan ELAN:ARM-M4                                  | 1         | 4.35%   |
| AuthenTec AES1600                                 | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 4         | 28.57%  |
| Athena Smartcard Solutions | 4         | 28.57%  |
| O2 Micro                   | 3         | 21.43%  |
| SCM Microsystems           | 1         | 7.14%   |
| OmniKey                    | 1         | 7.14%   |
| Alcor Micro                | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Athena Smartcard Solutions ASEDrive CCID                                     | 4         | 28.57%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 14.29%  |
| Broadcom 5880                                                                | 2         | 14.29%  |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 7.14%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 7.14%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.14%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.14%   |
| Broadcom 58200                                                               | 1         | 7.14%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 148       | 70.14%  |
| 1     | 51        | 24.17%  |
| 2     | 8         | 3.79%   |
| 3     | 4         | 1.9%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 22        | 28.95%  |
| Net/wireless             | 16        | 21.05%  |
| Graphics card            | 14        | 18.42%  |
| Chipcard                 | 11        | 14.47%  |
| Communication controller | 3         | 3.95%   |
| Sound                    | 2         | 2.63%   |
| Multimedia controller    | 2         | 2.63%   |
| Unassigned class         | 1         | 1.32%   |
| Network                  | 1         | 1.32%   |
| Net/ethernet             | 1         | 1.32%   |
| Firewire controller      | 1         | 1.32%   |
| Card reader              | 1         | 1.32%   |
| Bluetooth                | 1         | 1.32%   |

