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

Total: 345

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Samsung       | 930X2K/931X2K               | Notebook    | [bc4f78f7e7](https://linux-hardware.org/?probe=bc4f78f7e7) | Apr 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [36ec2bb4c2](https://linux-hardware.org/?probe=36ec2bb4c2) | Apr 22, 2023 |
| HP            | ProBook 6570b               | Notebook    | [2b01f67020](https://linux-hardware.org/?probe=2b01f67020) | Apr 14, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [126c7a430c](https://linux-hardware.org/?probe=126c7a430c) | Apr 13, 2023 |
| Samsung       | 930X2K/931X2K               | Notebook    | [80d44eb98b](https://linux-hardware.org/?probe=80d44eb98b) | Apr 12, 2023 |
| HP            | EliteBook 8560p             | Notebook    | [2ecc0fe5bc](https://linux-hardware.org/?probe=2ecc0fe5bc) | Apr 07, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [8b4666305d](https://linux-hardware.org/?probe=8b4666305d) | Apr 07, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [33d6b0fbc8](https://linux-hardware.org/?probe=33d6b0fbc8) | Apr 05, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5f29b020ab](https://linux-hardware.org/?probe=5f29b020ab) | Apr 04, 2023 |
| Google        | Snappy                      | Notebook    | [16dda325bf](https://linux-hardware.org/?probe=16dda325bf) | Apr 02, 2023 |
| ASRock        | 970 Extreme3                | Desktop     | [906f9d6d04](https://linux-hardware.org/?probe=906f9d6d04) | Mar 30, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b72701d99c](https://linux-hardware.org/?probe=b72701d99c) | Mar 29, 2023 |
| Acer          | Aspire E1-431               | Notebook    | [f56a2c21cf](https://linux-hardware.org/?probe=f56a2c21cf) | Mar 26, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [457915fe10](https://linux-hardware.org/?probe=457915fe10) | Mar 23, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [d8fee2b6b1](https://linux-hardware.org/?probe=d8fee2b6b1) | Mar 08, 2023 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [2b64b38f7a](https://linux-hardware.org/?probe=2b64b38f7a) | Mar 01, 2023 |
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

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 23        | 9.35%   |
| Ubuntu 18.04                 | 17        | 6.91%   |
| OpenMandriva 4.2             | 16        | 6.5%    |
| Ubuntu 22.04                 | 13        | 5.28%   |
| OpenMandriva 4.3             | 7         | 2.85%   |
| OpenMandriva 23.01           | 7         | 2.85%   |
| Zorin 16                     | 6         | 2.44%   |
| Lubuntu 22.04                | 5         | 2.03%   |
| Debian 11                    | 5         | 2.03%   |
| Ubuntu 19.04                 | 4         | 1.63%   |
| Lubuntu 21.10                | 4         | 1.63%   |
| Linux Mint 20.2              | 4         | 1.63%   |
| Linux Mint 19.3              | 4         | 1.63%   |
| Fedora 36                    | 4         | 1.63%   |
| Raspbian 11                  | 3         | 1.22%   |
| OpenMandriva 23.03           | 3         | 1.22%   |
| Lubuntu 22.10                | 3         | 1.22%   |
| Lubuntu 21.04                | 3         | 1.22%   |
| Debian 10                    | 3         | 1.22%   |
| Zorin 15                     | 2         | 0.81%   |
| Xubuntu 20.04                | 2         | 0.81%   |
| UbuntuDDE 20.04              | 2         | 0.81%   |
| Ubuntu Studio 20.04          | 2         | 0.81%   |
| Ubuntu 22.10                 | 2         | 0.81%   |
| Ubuntu 21.04                 | 2         | 0.81%   |
| Pop!_OS 22.04                | 2         | 0.81%   |
| Pop!_OS 21.04                | 2         | 0.81%   |
| Pop!_OS 20.10                | 2         | 0.81%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.81%   |
| Manjaro 20.2.1               | 2         | 0.81%   |
| Manjaro                      | 2         | 0.81%   |
| Lubuntu 23.04                | 2         | 0.81%   |
| Lubuntu 20.04                | 2         | 0.81%   |
| Linux Mint 20.3              | 2         | 0.81%   |
| Linux Mint 20.1              | 2         | 0.81%   |
| Linux Mint 20                | 2         | 0.81%   |
| Kubuntu 23.04                | 2         | 0.81%   |
| KDE neon 20.04               | 2         | 0.81%   |
| Fedora 35                    | 2         | 0.81%   |
| Fedora 34                    | 2         | 0.81%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 64        | 28.57%  |
| OpenMandriva  | 32        | 14.29%  |
| Linux Mint    | 15        | 6.7%    |
| Fedora        | 13        | 5.8%    |
| Manjaro       | 11        | 4.91%   |
| Debian        | 10        | 4.46%   |
| Zorin         | 9         | 4.02%   |
| Lubuntu       | 9         | 4.02%   |
| Pop!_OS       | 8         | 3.57%   |
| ROSA          | 5         | 2.23%   |
| Kubuntu       | 4         | 1.79%   |
| KDE neon      | 4         | 1.79%   |
| Xubuntu       | 3         | 1.34%   |
| Raspbian      | 3         | 1.34%   |
| Elementary    | 3         | 1.34%   |
| Arch          | 3         | 1.34%   |
| UbuntuDDE     | 2         | 0.89%   |
| Ubuntu Unity  | 2         | 0.89%   |
| Ubuntu Studio | 2         | 0.89%   |
| openSUSE      | 2         | 0.89%   |
| Kali          | 2         | 0.89%   |
| Endless       | 2         | 0.89%   |
| EndeavourOS   | 2         | 0.89%   |
| ArcoLinux     | 2         | 0.89%   |
| Ubuntu MATE   | 1         | 0.45%   |
| Reborn OS     | 1         | 0.45%   |
| PureOS        | 1         | 0.45%   |
| Peppermint    | 1         | 0.45%   |
| Parrot        | 1         | 0.45%   |
| Nobara        | 1         | 0.45%   |
| LMDE          | 1         | 0.45%   |
| Clear Linux   | 1         | 0.45%   |
| ChimeraOS     | 1         | 0.45%   |
| BlackPanther  | 1         | 0.45%   |
| BigLinux      | 1         | 0.45%   |
| ALT Linux     | 1         | 0.45%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 16        | 5.97%   |
| 5.16.7-desktop-1omv4003  | 7         | 2.61%   |
| 5.4.0-42-generic         | 5         | 1.87%   |
| 6.1.1-desktop-1omv2290   | 4         | 1.49%   |
| 5.4.0-70-generic         | 4         | 1.49%   |
| 5.13.0-16-generic        | 4         | 1.49%   |
| 5.11.0-27-generic        | 4         | 1.49%   |
| 5.0.0-23-generic         | 4         | 1.49%   |
| 6.2.6-desktop-1omv2390   | 3         | 1.12%   |
| 5.8.0-50-generic         | 3         | 1.12%   |
| 5.4.0-77-generic         | 3         | 1.12%   |
| 5.19.0-26-generic        | 3         | 1.12%   |
| 5.15.0-52-generic        | 3         | 1.12%   |
| 5.0.0-25-generic         | 3         | 1.12%   |
| 6.2.0-18-generic         | 2         | 0.75%   |
| 6.1.4-desktop-1omv2301   | 2         | 0.75%   |
| 6.0.6-76060006-generic   | 2         | 0.75%   |
| 5.9.16-1-MANJARO         | 2         | 0.75%   |
| 5.8.0-7630-generic       | 2         | 0.75%   |
| 5.4.0-52-generic         | 2         | 0.75%   |
| 5.4.0-29-generic         | 2         | 0.75%   |
| 5.4.0-26-generic         | 2         | 0.75%   |
| 5.4.0-21-generic         | 2         | 0.75%   |
| 5.3.0-40-generic         | 2         | 0.75%   |
| 5.3.0-28-generic         | 2         | 0.75%   |
| 5.19.0-32-generic        | 2         | 0.75%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.75%   |
| 5.15.0-58-generic        | 2         | 0.75%   |
| 5.15.0-53-generic        | 2         | 0.75%   |
| 5.15.0-41-generic        | 2         | 0.75%   |
| 5.15.0-27-generic        | 2         | 0.75%   |
| 5.15.0-25-generic        | 2         | 0.75%   |
| 5.13.0-35-generic        | 2         | 0.75%   |
| 5.13.0-20-generic        | 2         | 0.75%   |
| 5.11.0-16-generic        | 2         | 0.75%   |
| 4.19.0-8-amd64           | 2         | 0.75%   |
| 4.15.0-112-generic       | 2         | 0.75%   |
| 6.2.7-200.fc37.x86_64    | 1         | 0.37%   |
| 6.2.0-custom             | 1         | 0.37%   |
| 6.2.0-20-generic         | 1         | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 14.29%  |
| 5.15.0  | 22        | 8.73%   |
| 5.10.14 | 16        | 6.35%   |
| 5.11.0  | 15        | 5.95%   |
| 4.15.0  | 12        | 4.76%   |
| 5.3.0   | 10        | 3.97%   |
| 5.13.0  | 10        | 3.97%   |
| 5.8.0   | 9         | 3.57%   |
| 5.0.0   | 9         | 3.57%   |
| 5.19.0  | 8         | 3.17%   |
| 5.10.0  | 8         | 3.17%   |
| 5.16.7  | 7         | 2.78%   |
| 6.1.1   | 6         | 2.38%   |
| 6.2.0   | 4         | 1.59%   |
| 6.2.6   | 3         | 1.19%   |
| 5.18.13 | 3         | 1.19%   |
| 4.19.0  | 3         | 1.19%   |
| 6.1.4   | 2         | 0.79%   |
| 6.1.2   | 2         | 0.79%   |
| 6.0.6   | 2         | 0.79%   |
| 5.9.16  | 2         | 0.79%   |
| 5.7.0   | 2         | 0.79%   |
| 4.18.0  | 2         | 0.79%   |
| 6.2.7   | 1         | 0.4%    |
| 6.1.6   | 1         | 0.4%    |
| 6.1.11  | 1         | 0.4%    |
| 6.1.0   | 1         | 0.4%    |
| 6.0.8   | 1         | 0.4%    |
| 6.0.7   | 1         | 0.4%    |
| 6.0.2   | 1         | 0.4%    |
| 6.0.11  | 1         | 0.4%    |
| 6.0.10  | 1         | 0.4%    |
| 5.9.9   | 1         | 0.4%    |
| 5.9.14  | 1         | 0.4%    |
| 5.9.11  | 1         | 0.4%    |
| 5.8.6   | 1         | 0.4%    |
| 5.6.19  | 1         | 0.4%    |
| 5.6.16  | 1         | 0.4%    |
| 5.6.14  | 1         | 0.4%    |
| 5.6.13  | 1         | 0.4%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 37        | 14.74%  |
| 5.10    | 31        | 12.35%  |
| 5.15    | 30        | 11.95%  |
| 5.11    | 19        | 7.57%   |
| 6.1     | 13        | 5.18%   |
| 5.19    | 12        | 4.78%   |
| 4.15    | 12        | 4.78%   |
| 5.13    | 11        | 4.38%   |
| 5.8     | 10        | 3.98%   |
| 5.3     | 10        | 3.98%   |
| 5.0     | 10        | 3.98%   |
| 6.2     | 8         | 3.19%   |
| 6.0     | 7         | 2.79%   |
| 5.16    | 7         | 2.79%   |
| 5.18    | 6         | 2.39%   |
| 5.9     | 5         | 1.99%   |
| 5.6     | 4         | 1.59%   |
| 4.19    | 4         | 1.59%   |
| 5.12    | 3         | 1.2%    |
| 4.18    | 3         | 1.2%    |
| 5.7     | 2         | 0.8%    |
| 5.14    | 2         | 0.8%    |
| 4.1     | 2         | 0.8%    |
| 5.2     | 1         | 0.4%    |
| 5.17    | 1         | 0.4%    |
| 4.9     | 1         | 0.4%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 203       | 96.21%  |
| i686   | 5         | 2.37%   |
| armv6l | 2         | 0.95%   |
| armv7l | 1         | 0.47%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 97        | 44.7%   |
| KDE5          | 44        | 20.28%  |
| Unknown       | 19        | 8.76%   |
| XFCE          | 13        | 5.99%   |
| LXQt          | 9         | 4.15%   |
| X-Cinnamon    | 8         | 3.69%   |
| MATE          | 6         | 2.76%   |
| KDE           | 4         | 1.84%   |
| Pantheon      | 3         | 1.38%   |
| LXDE          | 3         | 1.38%   |
| Unity         | 2         | 0.92%   |
| Openbox       | 2         | 0.92%   |
| i3            | 2         | 0.92%   |
| Deepin        | 2         | 0.92%   |
| Cinnamon      | 2         | 0.92%   |
| GNOME Classic | 1         | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 161       | 75.23%  |
| Wayland | 40        | 18.69%  |
| Unknown | 8         | 3.74%   |
| Tty     | 5         | 2.34%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 93        | 42.27%  |
| SDDM    | 54        | 24.55%  |
| GDM     | 24        | 10.91%  |
| GDM3    | 20        | 9.09%   |
| LightDM | 18        | 8.18%   |
| TDM     | 11        | 5%      |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 92        | 42.01%  |
| es_CR   | 82        | 37.44%  |
| Unknown | 19        | 8.68%   |
| es_ES   | 13        | 5.94%   |
| es_MX   | 3         | 1.37%   |
| en_GB   | 3         | 1.37%   |
| C       | 3         | 1.37%   |
| fr_FR   | 2         | 0.91%   |
| es_EC   | 1         | 0.46%   |
| de_DE   | 1         | 0.46%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 115       | 53.24%  |
| BIOS | 101       | 46.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 158       | 72.81%  |
| Overlay | 30        | 13.82%  |
| Btrfs   | 20        | 9.22%   |
| Unknown | 5         | 2.3%    |
| Xfs     | 2         | 0.92%   |
| Tmpfs   | 2         | 0.92%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 104       | 47.93%  |
| GPT     | 87        | 40.09%  |
| MBR     | 26        | 11.98%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 185       | 86.05%  |
| Yes       | 30        | 13.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 133       | 61.86%  |
| Yes       | 82        | 38.14%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 46        | 21.8%   |
| Hewlett-Packard         | 33        | 15.64%  |
| Lenovo                  | 22        | 10.43%  |
| ASUSTek Computer        | 21        | 9.95%   |
| Toshiba                 | 12        | 5.69%   |
| Gigabyte Technology     | 12        | 5.69%   |
| Acer                    | 12        | 5.69%   |
| MSI                     | 9         | 4.27%   |
| ASRock                  | 7         | 3.32%   |
| Apple                   | 6         | 2.84%   |
| Raspberry Pi Foundation | 3         | 1.42%   |
| Intel                   | 3         | 1.42%   |
| Unknown                 | 3         | 1.42%   |
| Samsung Electronics     | 2         | 0.95%   |
| Google                  | 2         | 0.95%   |
| ZOTAC                   | 1         | 0.47%   |
| TPV-INVENTA             | 1         | 0.47%   |
| System76                | 1         | 0.47%   |
| Supermicro              | 1         | 0.47%   |
| Sony                    | 1         | 0.47%   |
| Purism                  | 1         | 0.47%   |
| Pegatron                | 1         | 0.47%   |
| Olivetti                | 1         | 0.47%   |
| Microsoft               | 1         | 0.47%   |
| MACHINIST               | 1         | 0.47%   |
| Jumper                  | 1         | 0.47%   |
| HUAWEI                  | 1         | 0.47%   |
| Gateway                 | 1         | 0.47%   |
| Deffad                  | 1         | 0.47%   |
| Biostar                 | 1         | 0.47%   |
| AZW                     | 1         | 0.47%   |
| Alienware               | 1         | 0.47%   |
| ABIT                    | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 6         | 2.84%   |
| Dell OptiPlex 3020                       | 5         | 2.37%   |
| Dell Inspiron 7506 2n1                   | 4         | 1.9%    |
| Apple MacBookPro8,1                      | 4         | 1.9%    |
| Dell Inspiron 5584                       | 3         | 1.42%   |
| HP ProBook 6460b                         | 2         | 0.95%   |
| HP Pavilion Notebook                     | 2         | 0.95%   |
| HP Notebook                              | 2         | 0.95%   |
| HP Laptop 15-da0xxx                      | 2         | 0.95%   |
| Gigabyte B250M-DS3H                      | 2         | 0.95%   |
| Dell OptiPlex 7040                       | 2         | 0.95%   |
| ASUS TUF Gaming X570-PLUS                | 2         | 0.95%   |
| ASUS PRIME A320M-K                       | 2         | 0.95%   |
| ASRock B450 Steel Legend                 | 2         | 0.95%   |
| ZOTAC NM10                               | 1         | 0.47%   |
| TPV-INVENTA 18-2003LA                    | 1         | 0.47%   |
| Toshiba Satellite X205                   | 1         | 0.47%   |
| Toshiba Satellite S55-A                  | 1         | 0.47%   |
| Toshiba Satellite L655                   | 1         | 0.47%   |
| Toshiba Satellite L45-B                  | 1         | 0.47%   |
| Toshiba Satellite C855D                  | 1         | 0.47%   |
| Toshiba Satellite C845                   | 1         | 0.47%   |
| Toshiba Satellite C645D                  | 1         | 0.47%   |
| Toshiba Satellite C55-C                  | 1         | 0.47%   |
| Toshiba Satellite C55-B                  | 1         | 0.47%   |
| Toshiba Satellite C45-A                  | 1         | 0.47%   |
| Toshiba Satellite A305D                  | 1         | 0.47%   |
| Toshiba QOSMIO X775                      | 1         | 0.47%   |
| System76 Lemur                           | 1         | 0.47%   |
| Supermicro X9DAi                         | 1         | 0.47%   |
| Sony SVD13215PLB                         | 1         | 0.47%   |
| Samsung 930X2K/931X2K                    | 1         | 0.47%   |
| Samsung 930QAA                           | 1         | 0.47%   |
| RPi Raspberry Pi Model B Rev 2           | 1         | 0.47%   |
| RPi Raspberry Pi 3 Model B Plus Rev 1.3  | 1         | 0.47%   |
| RPi Raspberry Pi                         | 1         | 0.47%   |
| Purism Librem 15 v3                      | 1         | 0.47%   |
| Pegatron CQ2728LA                        | 1         | 0.47%   |
| Olivetti CL133A                          | 1         | 0.47%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 15        | 7.11%   |
| Lenovo ThinkPad       | 14        | 6.64%   |
| Toshiba Satellite     | 11        | 5.21%   |
| Dell Latitude         | 11        | 5.21%   |
| Dell OptiPlex         | 10        | 4.74%   |
| Acer Aspire           | 10        | 4.74%   |
| HP Pavilion           | 7         | 3.32%   |
| HP Laptop             | 6         | 2.84%   |
| Unknown               | 6         | 2.84%   |
| HP ProBook            | 5         | 2.37%   |
| Lenovo IdeaPad        | 4         | 1.9%    |
| HP EliteBook          | 4         | 1.9%    |
| Dell Precision        | 4         | 1.9%    |
| ASUS PRIME            | 4         | 1.9%    |
| Apple MacBookPro8     | 4         | 1.9%    |
| RPi Raspberry         | 3         | 1.42%   |
| Dell XPS              | 3         | 1.42%   |
| ASUS VivoBook         | 3         | 1.42%   |
| ASUS TUF              | 3         | 1.42%   |
| Lenovo IdeaPadFlex    | 2         | 0.95%   |
| HP Notebook           | 2         | 0.95%   |
| Gigabyte B250M-DS3H   | 2         | 0.95%   |
| Dell G3               | 2         | 0.95%   |
| ASUS STRIX            | 2         | 0.95%   |
| ASRock B450           | 2         | 0.95%   |
| ZOTAC NM10            | 1         | 0.47%   |
| TPV-INVENTA 18-2003LA | 1         | 0.47%   |
| Toshiba QOSMIO        | 1         | 0.47%   |
| System76 Lemur        | 1         | 0.47%   |
| Supermicro X9DAi      | 1         | 0.47%   |
| Sony SVD13215PLB      | 1         | 0.47%   |
| Samsung 930X2K        | 1         | 0.47%   |
| Samsung 930QAA        | 1         | 0.47%   |
| Purism Librem         | 1         | 0.47%   |
| Pegatron CQ2728LA     | 1         | 0.47%   |
| Olivetti CL133A       | 1         | 0.47%   |
| MSI Z390              | 1         | 0.47%   |
| MSI MS-7D77           | 1         | 0.47%   |
| MSI MS-7B86           | 1         | 0.47%   |
| MSI MS-7992           | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 28        | 13.27%  |
| 2020    | 18        | 8.53%   |
| 2014    | 18        | 8.53%   |
| 2018    | 17        | 8.06%   |
| 2012    | 16        | 7.58%   |
| 2011    | 16        | 7.58%   |
| 2017    | 14        | 6.64%   |
| 2016    | 14        | 6.64%   |
| 2013    | 14        | 6.64%   |
| 2015    | 12        | 5.69%   |
| 2021    | 9         | 4.27%   |
| 2008    | 7         | 3.32%   |
| 2022    | 6         | 2.84%   |
| 2010    | 6         | 2.84%   |
| 2007    | 4         | 1.9%    |
| 2009    | 3         | 1.42%   |
| 2006    | 3         | 1.42%   |
| Unknown | 3         | 1.42%   |
| 2005    | 2         | 0.95%   |
| 2023    | 1         | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 126       | 59.72%  |
| Desktop        | 67        | 31.75%  |
| Convertible    | 8         | 3.79%   |
| System on chip | 3         | 1.42%   |
| All in one     | 3         | 1.42%   |
| Tablet         | 2         | 0.95%   |
| Mini pc        | 1         | 0.47%   |
| Server         | 1         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 194       | 91.94%  |
| Enabled  | 17        | 8.06%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 208       | 98.58%  |
| Yes  | 3         | 1.42%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 46        | 21.5%   |
| 3.01-4.0        | 42        | 19.63%  |
| 8.01-16.0       | 42        | 19.63%  |
| 16.01-24.0      | 41        | 19.16%  |
| 32.01-64.0      | 18        | 8.41%   |
| 1.01-2.0        | 9         | 4.21%   |
| 64.01-256.0     | 5         | 2.34%   |
| 2.01-3.0        | 4         | 1.87%   |
| 24.01-32.0      | 3         | 1.4%    |
| 0.01-0.5        | 2         | 0.93%   |
| More than 256.0 | 1         | 0.47%   |
| 0.51-1.0        | 1         | 0.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 93        | 40.26%  |
| 2.01-3.0   | 56        | 24.24%  |
| 4.01-8.0   | 32        | 13.85%  |
| 3.01-4.0   | 23        | 9.96%   |
| 0.51-1.0   | 10        | 4.33%   |
| 8.01-16.0  | 7         | 3.03%   |
| 0.01-0.5   | 6         | 2.6%    |
| 16.01-24.0 | 3         | 1.3%    |
| 24.01-32.0 | 1         | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 145       | 67.13%  |
| 2      | 47        | 21.76%  |
| 3      | 13        | 6.02%   |
| 4      | 8         | 3.7%    |
| 8      | 1         | 0.46%   |
| 7      | 1         | 0.46%   |
| 5      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 121       | 56.54%  |
| Yes       | 93        | 43.46%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 187       | 88.63%  |
| No        | 24        | 11.37%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 166       | 77.93%  |
| No        | 47        | 22.07%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 57.87%  |
| No        | 91        | 42.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Costa Rica | 211       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San José     | 93        | 40.09%  |
| Heredia       | 43        | 18.53%  |
| Alajuela      | 18        | 7.76%   |
| Escazu        | 8         | 3.45%   |
| Rio Segundo   | 7         | 3.02%   |
| Cartago       | 7         | 3.02%   |
| Quesada       | 4         | 1.72%   |
| Grecia        | 4         | 1.72%   |
| Santa Ana     | 3         | 1.29%   |
| San Ramon     | 3         | 1.29%   |
| Puntarenas    | 3         | 1.29%   |
| Liberia       | 3         | 1.29%   |
| Tres Rios     | 2         | 0.86%   |
| Siquirres     | 2         | 0.86%   |
| Santa Fe      | 2         | 0.86%   |
| Santa Cruz    | 2         | 0.86%   |
| San Pedro     | 2         | 0.86%   |
| Palmares      | 2         | 0.86%   |
| Nosara        | 2         | 0.86%   |
| Naranjo       | 2         | 0.86%   |
| Esparza       | 2         | 0.86%   |
| Curridabat    | 2         | 0.86%   |
| Zarcero       | 1         | 0.43%   |
| Tibas         | 1         | 0.43%   |
| Santo Domingo | 1         | 0.43%   |
| Santiago      | 1         | 0.43%   |
| San Pablo     | 1         | 0.43%   |
| San Juan      | 1         | 0.43%   |
| San Francisco | 1         | 0.43%   |
| Sámara       | 1         | 0.43%   |
| Quepos        | 1         | 0.43%   |
| Pavas         | 1         | 0.43%   |
| Guacima       | 1         | 0.43%   |
| Colon         | 1         | 0.43%   |
| Bajo Perez    | 1         | 0.43%   |
| Bagaces       | 1         | 0.43%   |
| Alpes         | 1         | 0.43%   |
| Alajuelita    | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 44        | 72     | 15.12%  |
| WDC                   | 42        | 59     | 14.43%  |
| Toshiba               | 28        | 33     | 9.62%   |
| Samsung Electronics   | 23        | 40     | 7.9%    |
| Kingston              | 19        | 29     | 6.53%   |
| A-DATA Technology     | 17        | 17     | 5.84%   |
| Intel                 | 16        | 31     | 5.5%    |
| Unknown               | 13        | 18     | 4.47%   |
| HGST                  | 12        | 13     | 4.12%   |
| SanDisk               | 8         | 10     | 2.75%   |
| SK hynix              | 6         | 11     | 2.06%   |
| JMicron Technology    | 6         | 6      | 2.06%   |
| Hitachi               | 6         | 9      | 2.06%   |
| Patriot               | 5         | 6      | 1.72%   |
| Micron Technology     | 5         | 6      | 1.72%   |
| Crucial               | 5         | 5      | 1.72%   |
| XPG                   | 4         | 4      | 1.37%   |
| Realtek Semiconductor | 3         | 5      | 1.03%   |
| Netac                 | 3         | 3      | 1.03%   |
| ZOTAC                 | 2         | 3      | 0.69%   |
| Team                  | 2         | 2      | 0.69%   |
| Maxtor                | 2         | 2      | 0.69%   |
| LITEONIT              | 2         | 2      | 0.69%   |
| ADATA Technology      | 2         | 2      | 0.69%   |
| Unknown               | 2         | 2      | 0.69%   |
| Zheino                | 1         | 1      | 0.34%   |
| WD MediaMax           | 1         | 1      | 0.34%   |
| UMIS                  | 1         | 1      | 0.34%   |
| Transcend             | 1         | 1      | 0.34%   |
| T-FORCE               | 1         | 1      | 0.34%   |
| Silicon Motion        | 1         | 1      | 0.34%   |
| Phison Electronics    | 1         | 1      | 0.34%   |
| KIOXIA                | 1         | 1      | 0.34%   |
| Gigabyte Technology   | 1         | 2      | 0.34%   |
| Fujitsu               | 1         | 1      | 0.34%   |
| FORESEE               | 1         | 1      | 0.34%   |
| Dell                  | 1         | 1      | 0.34%   |
| CT120BX5              | 1         | 1      | 0.34%   |
| Apple                 | 1         | 2      | 0.34%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                   | 9         | 2.84%   |
| JMicron Generic 1TB                               | 6         | 1.89%   |
| A-DATA SU630 480GB SSD                            | 6         | 1.89%   |
| Toshiba MQ01ABF050 500GB                          | 5         | 1.58%   |
| Toshiba MQ01ABD100 1TB                            | 5         | 1.58%   |
| Toshiba DT01ACA100 1TB                            | 5         | 1.58%   |
| Intel H10 HBRPEKNX0203AO NVMe 32GB                | 4         | 1.26%   |
| Intel H10 HBRPEKNX0203A NVMe 1TB                  | 4         | 1.26%   |
| HGST HTS541075A9E680 752GB                        | 4         | 1.26%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                  | 3         | 0.95%   |
| WDC WD10EZEX-75WN4A1 1TB                          | 3         | 0.95%   |
| Toshiba KBG30ZMS256G NVMe 256GB                   | 3         | 0.95%   |
| Seagate ST1000LM035-1RK172 970GB                  | 3         | 0.95%   |
| Seagate ST1000DM003-1CH162 1TB                    | 3         | 0.95%   |
| Kingston SV300S37A120G 120GB SSD                  | 3         | 0.95%   |
| Intel SSDSC2BF180A4H 180GB                        | 3         | 0.95%   |
| Intel SSDSA2CW300G3 304GB                         | 3         | 0.95%   |
| HGST HTS541010A9E680 1TB                          | 3         | 0.95%   |
| XPG GAMMIX S11 Pro 1TB                            | 2         | 0.63%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 2         | 0.63%   |
| WDC WD5000LPCX-60VHAT0 500GB                      | 2         | 0.63%   |
| WDC WD20SPZX-08UA7 2TB                            | 2         | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 2         | 0.63%   |
| Unknown MMC Card  128GB                           | 2         | 0.63%   |
| Unknown 00000  32GB                               | 2         | 0.63%   |
| Toshiba NVMe SSD Drive 256GB                      | 2         | 0.63%   |
| SK hynix NVMe SSD Drive 128GB                     | 2         | 0.63%   |
| Seagate ST9500325AS 500GB                         | 2         | 0.63%   |
| Seagate ST8000DM004-2CX188 8TB                    | 2         | 0.63%   |
| Seagate ST500LT012-1DG142 500GB                   | 2         | 0.63%   |
| Seagate ST500LM021-1KJ152 500GB                   | 2         | 0.63%   |
| Seagate ST500DM002-1BD142 500GB                   | 2         | 0.63%   |
| Seagate ST380815AS 80GB                           | 2         | 0.63%   |
| Seagate ST2000LM007-1R8174 2TB                    | 2         | 0.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 2         | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB                    | 2         | 0.63%   |
| Samsung NVMe SSD Drive 256GB                      | 2         | 0.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 2         | 0.63%   |
| Patriot P210 256GB SSD                            | 2         | 0.63%   |
| Kingston SA400S37480G 480GB SSD                   | 2         | 0.63%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 70     | 33.07%  |
| WDC                 | 32        | 39     | 25.2%   |
| Toshiba             | 23        | 24     | 18.11%  |
| HGST                | 12        | 13     | 9.45%   |
| JMicron Technology  | 6         | 6      | 4.72%   |
| Hitachi             | 6         | 9      | 4.72%   |
| Maxtor              | 2         | 2      | 1.57%   |
| Unknown             | 1         | 1      | 0.79%   |
| Samsung Electronics | 1         | 1      | 0.79%   |
| Fujitsu             | 1         | 1      | 0.79%   |
| Apple               | 1         | 1      | 0.79%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 17        | 22     | 19.1%   |
| A-DATA Technology   | 13        | 13     | 14.61%  |
| Samsung Electronics | 10        | 23     | 11.24%  |
| WDC                 | 9         | 15     | 10.11%  |
| Intel               | 9         | 19     | 10.11%  |
| SanDisk             | 6         | 8      | 6.74%   |
| Patriot             | 4         | 5      | 4.49%   |
| Micron Technology   | 4         | 4      | 4.49%   |
| Crucial             | 4         | 4      | 4.49%   |
| ZOTAC               | 2         | 3      | 2.25%   |
| Team                | 2         | 2      | 2.25%   |
| Netac               | 2         | 2      | 2.25%   |
| LITEONIT            | 2         | 2      | 2.25%   |
| Transcend           | 1         | 1      | 1.12%   |
| Seagate             | 1         | 1      | 1.12%   |
| Gigabyte Technology | 1         | 2      | 1.12%   |
| FORESEE             | 1         | 1      | 1.12%   |
| CT120BX5            | 1         | 1      | 1.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 114       | 167    | 42.38%  |
| SSD     | 84        | 128    | 31.23%  |
| NVMe    | 53        | 87     | 19.7%   |
| MMC     | 14        | 19     | 5.2%    |
| Unknown | 4         | 5      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 175       | 283    | 68.9%   |
| NVMe | 53        | 87     | 20.87%  |
| MMC  | 14        | 19     | 5.51%   |
| SAS  | 12        | 17     | 4.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 119       | 165    | 57.77%  |
| 0.51-1.0   | 68        | 101    | 33.01%  |
| 1.01-2.0   | 12        | 14     | 5.83%   |
| 4.01-10.0  | 4         | 12     | 1.94%   |
| 3.01-4.0   | 1         | 1      | 0.49%   |
| 2.01-3.0   | 1         | 1      | 0.49%   |
| 10.01-20.0 | 1         | 1      | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 57        | 25%     |
| 251-500        | 40        | 17.54%  |
| 501-1000       | 37        | 16.23%  |
| 1-20           | 23        | 10.09%  |
| 51-100         | 21        | 9.21%   |
| 1001-2000      | 18        | 7.89%   |
| 21-50          | 12        | 5.26%   |
| More than 3000 | 10        | 4.39%   |
| 2001-3000      | 5         | 2.19%   |
| Unknown        | 5         | 2.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 104       | 44.07%  |
| 21-50          | 41        | 17.37%  |
| 101-250        | 25        | 10.59%  |
| 51-100         | 22        | 9.32%   |
| 251-500        | 21        | 8.9%    |
| 501-1000       | 8         | 3.39%   |
| Unknown        | 5         | 2.12%   |
| More than 3000 | 4         | 1.69%   |
| 1001-2000      | 4         | 1.69%   |
| 2001-3000      | 2         | 0.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Intel H10 HBRPEKNX0203A NVMe 1TB                    | 4         | 4      | 16%     |
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 4%      |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 4%      |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 4%      |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 4%      |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 4%      |
| Seagate ST9320310AS 320GB                           | 1         | 1      | 4%      |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 4%      |
| Seagate ST500LT012-1DG142 500GB                     | 1         | 1      | 4%      |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 2      | 4%      |
| Seagate ST1000DM003-1CH162 1TB                      | 1         | 1      | 4%      |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 2      | 4%      |
| Netac SSD 120GB                                     | 1         | 1      | 4%      |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 4%      |
| Maxtor STM3160215AS 160GB                           | 1         | 1      | 4%      |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 4%      |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 4%      |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 4%      |
| Hitachi HDE721010SLA330 1TB                         | 1         | 1      | 4%      |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 4%      |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 4%      |
| A-DATA Technology SX8100NP 256GB                    | 1         | 1      | 4%      |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 5         | 6      | 20%     |
| Intel             | 5         | 5      | 20%     |
| Toshiba           | 3         | 3      | 12%     |
| WDC               | 2         | 2      | 8%      |
| Hitachi           | 2         | 3      | 8%      |
| HGST              | 2         | 2      | 8%      |
| SanDisk           | 1         | 2      | 4%      |
| Netac             | 1         | 1      | 4%      |
| Micron Technology | 1         | 1      | 4%      |
| Maxtor            | 1         | 1      | 4%      |
| Kingston          | 1         | 1      | 4%      |
| A-DATA Technology | 1         | 1      | 4%      |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 6      | 33.33%  |
| Toshiba | 3         | 3      | 20%     |
| WDC     | 2         | 2      | 13.33%  |
| Hitachi | 2         | 3      | 13.33%  |
| HGST    | 2         | 2      | 13.33%  |
| Maxtor  | 1         | 1      | 6.67%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 14        | 17     | 58.33%  |
| NVMe | 5         | 5      | 20.83%  |
| SSD  | 5         | 6      | 20.83%  |

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
| Detected | 128       | 219    | 53.78%  |
| Works    | 87        | 159    | 36.55%  |
| Malfunc  | 23        | 28     | 9.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 152       | 59.38%  |
| AMD                          | 38        | 14.84%  |
| Samsung Electronics          | 13        | 5.08%   |
| ASMedia Technology           | 7         | 2.73%   |
| ADATA Technology             | 7         | 2.73%   |
| SK hynix                     | 5         | 1.95%   |
| SanDisk                      | 5         | 1.95%   |
| Realtek Semiconductor        | 5         | 1.95%   |
| Toshiba America Info Systems | 4         | 1.56%   |
| Nvidia                       | 3         | 1.17%   |
| Silicon Motion               | 2         | 0.78%   |
| Micron Technology            | 2         | 0.78%   |
| Kingston Technology Company  | 2         | 0.78%   |
| Union Memory (Shenzhen)      | 1         | 0.39%   |
| Silicon Image                | 1         | 0.39%   |
| Phison Electronics           | 1         | 0.39%   |
| OCZ Technology Group         | 1         | 0.39%   |
| Micron/Crucial Technology    | 1         | 0.39%   |
| Marvell Technology Group     | 1         | 0.39%   |
| LSI Logic / Symbios Logic    | 1         | 0.39%   |
| KIOXIA                       | 1         | 0.39%   |
| JMicron Technology           | 1         | 0.39%   |
| INNOGRIT                     | 1         | 0.39%   |
| Apple                        | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 25        | 8.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 13        | 4.58%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 13        | 4.58%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 13        | 4.58%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 11        | 3.87%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 3.52%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 8         | 2.82%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 2.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 8         | 2.82%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 7         | 2.46%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 6         | 2.11%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 2.11%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 6         | 2.11%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 5         | 1.76%   |
| Intel NVMe Controller                                                                  | 5         | 1.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 5         | 1.76%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 1.41%   |
| Intel SATA Controller [RAID mode]                                                      | 4         | 1.41%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 1.41%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 4         | 1.41%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 1.06%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.06%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 3         | 1.06%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 1.06%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.06%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 1.06%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 3         | 1.06%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 3         | 1.06%   |
| AMD FCH SATA Controller D                                                              | 3         | 1.06%   |
| AMD 400 Series Chipset SATA Controller                                                 | 3         | 1.06%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.7%    |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                        | 2         | 0.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                         | 2         | 0.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                         | 2         | 0.7%    |
| Realtek NVMe Controller                                                                | 2         | 0.7%    |
| Micron NVMe Storage Controller                                                         | 2         | 0.7%    |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 2         | 0.7%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 0.7%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 157       | 60.62%  |
| NVMe | 54        | 20.85%  |
| IDE  | 27        | 10.42%  |
| RAID | 19        | 7.34%   |
| SAS  | 1         | 0.39%   |
| SCSI | 1         | 0.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 165       | 78.2%   |
| AMD    | 43        | 20.38%  |
| ARM    | 3         | 1.42%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz                | 5         | 2.37%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 5         | 2.37%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 4         | 1.9%    |
| AMD Ryzen 5 3600 6-Core Processor               | 4         | 1.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz               | 3         | 1.42%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 3         | 1.42%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 3         | 1.42%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 3         | 1.42%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 3         | 1.42%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 3         | 1.42%   |
| ARM BCM2835 Processor                           | 3         | 1.42%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 0.95%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 0.95%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 0.95%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 2         | 0.95%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 0.95%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 2         | 0.95%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 0.95%   |
| Intel Core i5-6400 CPU @ 2.70GHz                | 2         | 0.95%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 0.95%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 0.95%   |
| Intel Core i5-3230M CPU @ 2.60GHz               | 2         | 0.95%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 2         | 0.95%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 2         | 0.95%   |
| Intel Core i3-4130 CPU @ 3.40GHz                | 2         | 0.95%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 2         | 0.95%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 2         | 0.95%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 2         | 0.95%   |
| Intel Celeron CPU N3350 @ 1.10GHz               | 2         | 0.95%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 2         | 0.95%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 2         | 0.95%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 2         | 0.95%   |
| AMD Ryzen 7 5800X 8-Core Processor              | 2         | 0.95%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 0.95%   |
| AMD E1-1200 APU with Radeon HD Graphics         | 2         | 0.95%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 2         | 0.95%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz            | 1         | 0.47%   |
| Intel Xeon CPU X5667 @ 3.07GHz                  | 1         | 0.47%   |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1         | 0.47%   |
| Intel Xeon CPU E5405 @ 2.00GHz                  | 1         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 46        | 21.8%   |
| Intel Core i7                  | 38        | 18.01%  |
| Intel Core i3                  | 21        | 9.95%   |
| Intel Celeron                  | 17        | 8.06%   |
| Other                          | 15        | 7.11%   |
| AMD Ryzen 5                    | 9         | 4.27%   |
| AMD Ryzen 7                    | 8         | 3.79%   |
| Intel Xeon                     | 6         | 2.84%   |
| AMD FX                         | 5         | 2.37%   |
| Intel Pentium                  | 4         | 1.9%    |
| Intel Core 2 Duo               | 4         | 1.9%    |
| Intel Core 2                   | 4         | 1.9%    |
| AMD Ryzen 3                    | 4         | 1.9%    |
| AMD E1                         | 4         | 1.9%    |
| Intel Atom                     | 3         | 1.42%   |
| ARM BCM                        | 3         | 1.42%   |
| Intel Genuine                  | 2         | 0.95%   |
| AMD A8                         | 2         | 0.95%   |
| AMD A10                        | 2         | 0.95%   |
| Intel Xeon Silver              | 1         | 0.47%   |
| Intel Pentium Dual-Core        | 1         | 0.47%   |
| Intel Pentium 4                | 1         | 0.47%   |
| Intel Core M                   | 1         | 0.47%   |
| Intel Core i9                  | 1         | 0.47%   |
| Intel Core 2 Quad              | 1         | 0.47%   |
| AMD V120                       | 1         | 0.47%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.47%   |
| AMD Turion 64 X2               | 1         | 0.47%   |
| AMD Sempron                    | 1         | 0.47%   |
| AMD Ryzen 7 PRO                | 1         | 0.47%   |
| AMD Phenom II X4               | 1         | 0.47%   |
| AMD E2                         | 1         | 0.47%   |
| AMD Athlon                     | 1         | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 99        | 46.92%  |
| 4      | 68        | 32.23%  |
| 6      | 18        | 8.53%   |
| 8      | 13        | 6.16%   |
| 1      | 7         | 3.32%   |
| 10     | 2         | 0.95%   |
| 20     | 1         | 0.47%   |
| 16     | 1         | 0.47%   |
| 12     | 1         | 0.47%   |
| 3      | 1         | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 209       | 99.05%  |
| 2      | 2         | 0.95%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 129       | 61.14%  |
| 1      | 82        | 38.86%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 204       | 96.23%  |
| Unknown        | 6         | 2.83%   |
| 32-bit         | 2         | 0.94%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 22.37%  |
| 0x206a7    | 13        | 5.94%   |
| 0x306c3    | 12        | 5.48%   |
| 0x306a9    | 9         | 4.11%   |
| 0x40651    | 7         | 3.2%    |
| 0x08108109 | 7         | 3.2%    |
| 0x806e9    | 6         | 2.74%   |
| 0x506e3    | 6         | 2.74%   |
| 0x306d4    | 6         | 2.74%   |
| 0x906ea    | 5         | 2.28%   |
| 0x906e9    | 5         | 2.28%   |
| 0x806c1    | 5         | 2.28%   |
| 0x406c4    | 5         | 2.28%   |
| 0x806ec    | 4         | 1.83%   |
| 0x706a1    | 4         | 1.83%   |
| 0x406e3    | 4         | 1.83%   |
| 0x08701021 | 4         | 1.83%   |
| 0x806eb    | 3         | 1.37%   |
| 0x806ea    | 3         | 1.37%   |
| 0x20655    | 3         | 1.37%   |
| 0x05000119 | 3         | 1.37%   |
| 0x906eb    | 2         | 0.91%   |
| 0x706a8    | 2         | 0.91%   |
| 0x6fd      | 2         | 0.91%   |
| 0x6f6      | 2         | 0.91%   |
| 0x506c9    | 2         | 0.91%   |
| 0x306e4    | 2         | 0.91%   |
| 0x30678    | 2         | 0.91%   |
| 0x1067a    | 2         | 0.91%   |
| 0x10676    | 2         | 0.91%   |
| 0x08600104 | 2         | 0.91%   |
| 0x07030105 | 2         | 0.91%   |
| 0x06000852 | 2         | 0.91%   |
| 0x010000c8 | 2         | 0.91%   |
| 0xf49      | 1         | 0.46%   |
| 0xf29      | 1         | 0.46%   |
| 0xa0652    | 1         | 0.46%   |
| 0x906ed    | 1         | 0.46%   |
| 0x906ec    | 1         | 0.46%   |
| 0x906a3    | 1         | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 16.59%  |
| Haswell          | 22        | 10.43%  |
| SandyBridge      | 20        | 9.48%   |
| Skylake          | 13        | 6.16%   |
| IvyBridge        | 12        | 5.69%   |
| Unknown          | 10        | 4.74%   |
| Zen+             | 9         | 4.27%   |
| Zen 2            | 9         | 4.27%   |
| Silvermont       | 8         | 3.79%   |
| TigerLake        | 7         | 3.32%   |
| Broadwell        | 7         | 3.32%   |
| Penryn           | 6         | 2.84%   |
| Goldmont plus    | 6         | 2.84%   |
| Core             | 6         | 2.84%   |
| Westmere         | 4         | 1.9%    |
| Piledriver       | 4         | 1.9%    |
| K10              | 3         | 1.42%   |
| Excavator        | 3         | 1.42%   |
| Bobcat           | 3         | 1.42%   |
| Zen 3            | 2         | 0.95%   |
| Puma             | 2         | 0.95%   |
| NetBurst         | 2         | 0.95%   |
| Nehalem          | 2         | 0.95%   |
| IceLake          | 2         | 0.95%   |
| Goldmont         | 2         | 0.95%   |
| CometLake        | 2         | 0.95%   |
| Alderlake Hybrid | 2         | 0.95%   |
| Zen              | 1         | 0.47%   |
| P6               | 1         | 0.47%   |
| K8 Hammer        | 1         | 0.47%   |
| K8 & K10 hybrid  | 1         | 0.47%   |
| K10 Llano        | 1         | 0.47%   |
| Jaguar           | 1         | 0.47%   |
| Bulldozer        | 1         | 0.47%   |
| Bonnell          | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 139       | 58.16%  |
| Nvidia | 53        | 22.18%  |
| AMD    | 47        | 19.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 16        | 6.3%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 3.15%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 8         | 3.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 2.76%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 2.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 2.36%   |
| Intel HD Graphics 620                                                                    | 6         | 2.36%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.36%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.36%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 6         | 2.36%   |
| Intel UHD Graphics 620                                                                   | 5         | 1.97%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 4         | 1.57%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 1.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.57%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.57%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.57%   |
| Intel HD Graphics 630                                                                    | 4         | 1.57%   |
| Intel HD Graphics 530                                                                    | 4         | 1.57%   |
| Intel DG1 [Iris Xe MAX Graphics]                                                         | 4         | 1.57%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.57%   |
| AMD Renoir                                                                               | 4         | 1.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.57%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.18%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 3         | 1.18%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.18%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.18%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 3         | 1.18%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.79%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.79%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.79%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2         | 0.79%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.79%   |
| Intel HD Graphics 500                                                                    | 2         | 0.79%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.79%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 2         | 0.79%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 108       | 50.47%  |
| 1 x AMD        | 36        | 16.82%  |
| 1 x Nvidia     | 29        | 13.55%  |
| Intel + Nvidia | 22        | 10.28%  |
| 2 x AMD        | 6         | 2.8%    |
| Other          | 4         | 1.87%   |
| 2 x Intel      | 4         | 1.87%   |
| AMD + Nvidia   | 3         | 1.4%    |
| Intel + AMD    | 2         | 0.93%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 180       | 83.72%  |
| Proprietary | 29        | 13.49%  |
| Unknown     | 6         | 2.79%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 137       | 62.84%  |
| 1.01-2.0   | 26        | 11.93%  |
| 0.01-0.5   | 18        | 8.26%   |
| 0.51-1.0   | 13        | 5.96%   |
| 3.01-4.0   | 12        | 5.5%    |
| 5.01-6.0   | 7         | 3.21%   |
| 7.01-8.0   | 4         | 1.83%   |
| 8.01-16.0  | 1         | 0.46%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 38        | 15.02%  |
| LG Display              | 25        | 9.88%   |
| AOC                     | 25        | 9.88%   |
| Samsung Electronics     | 21        | 8.3%    |
| BOE                     | 20        | 7.91%   |
| Dell                    | 18        | 7.11%   |
| Chimei Innolux          | 17        | 6.72%   |
| Hewlett-Packard         | 15        | 5.93%   |
| Goldstar                | 9         | 3.56%   |
| Apple                   | 6         | 2.37%   |
| ViewSonic               | 5         | 1.98%   |
| Acer                    | 5         | 1.98%   |
| Sony                    | 4         | 1.58%   |
| Chi Mei Optoelectronics | 4         | 1.58%   |
| MSI                     | 3         | 1.19%   |
| BenQ                    | 3         | 1.19%   |
| ASUSTek Computer        | 3         | 1.19%   |
| Ancor Communications    | 3         | 1.19%   |
| AGO                     | 3         | 1.19%   |
| Sharp                   | 2         | 0.79%   |
| Panasonic               | 2         | 0.79%   |
| Lenovo                  | 2         | 0.79%   |
| CPT                     | 2         | 0.79%   |
| Xerox                   | 1         | 0.4%    |
| Unknown (XXX)           | 1         | 0.4%    |
| Sun                     | 1         | 0.4%    |
| RTK                     | 1         | 0.4%    |
| Royal Information       | 1         | 0.4%    |
| PRISM+                  | 1         | 0.4%    |
| Philips                 | 1         | 0.4%    |
| PAR                     | 1         | 0.4%    |
| LTM                     | 1         | 0.4%    |
| LG Philips              | 1         | 0.4%    |
| KDC                     | 1         | 0.4%    |
| Hitachi                 | 1         | 0.4%    |
| Haier                   | 1         | 0.4%    |
| GAOMON                  | 1         | 0.4%    |
| Envision                | 1         | 0.4%    |
| CVT                     | 1         | 0.4%    |
| ASRock                  | 1         | 0.4%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Dell AW2518HF DELA102 1920x1080 544x303mm 24.5-inch                  | 5         | 1.92%   |
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5         | 1.92%   |
| AU Optronics LCD Monitor AUO35EB 3840x2160 344x193mm 15.5-inch       | 4         | 1.53%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 4         | 1.53%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 1.15%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch       | 3         | 1.15%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 3         | 1.15%   |
| Sony TV SNY1B02 1360x768                                             | 2         | 0.77%   |
| Sony TV SNY0902 1360x768                                             | 2         | 0.77%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2         | 0.77%   |
| Panasonic TV MEIA296 1280x1024 698x392mm 31.5-inch                   | 2         | 0.77%   |
| MSI G271 MSI3CB5 1920x1080 598x336mm 27.0-inch                       | 2         | 0.77%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 2         | 0.77%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.77%   |
| Hewlett-Packard LCD Monitor E232 2944x1080                           | 2         | 0.77%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2         | 0.77%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch          | 2         | 0.77%   |
| Dell E207WFP DELD011 1680x1050 430x270mm 20.0-inch                   | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 0.77%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.77%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 2         | 0.77%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.77%   |
| AOC 2343 AOC2343 1920x1080 509x286mm 23.0-inch                       | 2         | 0.77%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 2         | 0.77%   |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                   | 1         | 0.38%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch        | 1         | 0.38%   |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch        | 1         | 0.38%   |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch            | 1         | 0.38%   |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                           | 1         | 0.38%   |
| ViewSonic LCD Monitor VX2260WM                                       | 1         | 0.38%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1         | 0.38%   |
| Sun SCEI MONITOR SCE0301 1920x1080 522x294mm 23.6-inch               | 1         | 0.38%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 1         | 0.38%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 1         | 0.38%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch    | 1         | 0.38%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 87        | 36.1%   |
| 1366x768 (WXGA)    | 64        | 26.56%  |
| 3840x2160 (4K)     | 19        | 7.88%   |
| 1600x900 (HD+)     | 14        | 5.81%   |
| 1440x900 (WXGA+)   | 10        | 4.15%   |
| 1280x800 (WXGA)    | 10        | 4.15%   |
| 1280x1024 (SXGA)   | 10        | 4.15%   |
| 2560x1440 (QHD)    | 5         | 2.07%   |
| 1920x1200 (WUXGA)  | 3         | 1.24%   |
| 1360x768           | 3         | 1.24%   |
| 3286x1080          | 2         | 0.83%   |
| 2944x1080          | 2         | 0.83%   |
| 2560x1080          | 2         | 0.83%   |
| 1680x1050 (WSXGA+) | 2         | 0.83%   |
| 1280x720 (HD)      | 2         | 0.83%   |
| Unknown            | 2         | 0.83%   |
| 3840x2400          | 1         | 0.41%   |
| 2560x1600          | 1         | 0.41%   |
| 1400x1050          | 1         | 0.41%   |
| 1280x960           | 1         | 0.41%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 66        | 26.09%  |
| 14      | 26        | 10.28%  |
| 13      | 25        | 9.88%   |
| 23      | 17        | 6.72%   |
| 24      | 15        | 5.93%   |
| 19      | 15        | 5.93%   |
| 17      | 13        | 5.14%   |
| 21      | 10        | 3.95%   |
| 18      | 10        | 3.95%   |
| 27      | 9         | 3.56%   |
| Unknown | 9         | 3.56%   |
| 12      | 5         | 1.98%   |
| 84      | 4         | 1.58%   |
| 72      | 4         | 1.58%   |
| 11      | 4         | 1.58%   |
| 31      | 3         | 1.19%   |
| 20      | 3         | 1.19%   |
| 57      | 2         | 0.79%   |
| 43      | 2         | 0.79%   |
| 34      | 2         | 0.79%   |
| 32      | 2         | 0.79%   |
| 16      | 2         | 0.79%   |
| 58      | 1         | 0.4%    |
| 54      | 1         | 0.4%    |
| 40      | 1         | 0.4%    |
| 36      | 1         | 0.4%    |
| 22      | 1         | 0.4%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 115       | 46%     |
| 501-600     | 40        | 16%     |
| 401-500     | 35        | 14%     |
| 201-300     | 18        | 7.2%    |
| 351-400     | 10        | 4%      |
| Unknown     | 9         | 3.6%    |
| 1501-2000   | 8         | 3.2%    |
| 701-800     | 6         | 2.4%    |
| 601-700     | 3         | 1.2%    |
| 1001-1500   | 3         | 1.2%    |
| 901-1000    | 2         | 0.8%    |
| 801-900     | 1         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 165       | 75.34%  |
| 16/10   | 28        | 12.79%  |
| 5/4     | 9         | 4.11%   |
| Unknown | 9         | 4.11%   |
| 4/3     | 5         | 2.28%   |
| 21/9    | 2         | 0.91%   |
| 0.56    | 1         | 0.46%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 65        | 25.79%  |
| 81-90          | 47        | 18.65%  |
| 201-250        | 32        | 12.7%   |
| 151-200        | 23        | 9.13%   |
| 141-150        | 14        | 5.56%   |
| More than 1000 | 12        | 4.76%   |
| 301-350        | 9         | 3.57%   |
| Unknown        | 9         | 3.57%   |
| 351-500        | 7         | 2.78%   |
| 251-300        | 7         | 2.78%   |
| 71-80          | 6         | 2.38%   |
| 121-130        | 5         | 1.98%   |
| 51-60          | 4         | 1.59%   |
| 501-1000       | 4         | 1.59%   |
| 111-120        | 3         | 1.19%   |
| 61-70          | 2         | 0.79%   |
| 131-140        | 2         | 0.79%   |
| 91-100         | 1         | 0.4%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 79        | 32.24%  |
| 101-120       | 75        | 30.61%  |
| 121-160       | 56        | 22.86%  |
| 1-50          | 11        | 4.49%   |
| More than 240 | 9         | 3.67%   |
| Unknown       | 9         | 3.67%   |
| 161-240       | 6         | 2.45%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 163       | 73.76%  |
| 2     | 48        | 21.72%  |
| 0     | 7         | 3.17%   |
| 3     | 3         | 1.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 123       | 37.96%  |
| Intel                           | 86        | 26.54%  |
| Qualcomm Atheros                | 44        | 13.58%  |
| Broadcom                        | 23        | 7.1%    |
| TP-Link                         | 8         | 2.47%   |
| Broadcom Limited                | 8         | 2.47%   |
| Xiaomi                          | 3         | 0.93%   |
| Ralink                          | 3         | 0.93%   |
| Nvidia                          | 3         | 0.93%   |
| MediaTek                        | 3         | 0.93%   |
| Huawei Technologies             | 3         | 0.93%   |
| Microchip Technology            | 2         | 0.62%   |
| Linksys                         | 2         | 0.62%   |
| ASIX Electronics                | 2         | 0.62%   |
| Standard Microsystems           | 1         | 0.31%   |
| Ralink Technology               | 1         | 0.31%   |
| Qualcomm Atheros Communications | 1         | 0.31%   |
| Marvell Technology Group        | 1         | 0.31%   |
| Lenovo                          | 1         | 0.31%   |
| JMicron Technology              | 1         | 0.31%   |
| Hewlett-Packard                 | 1         | 0.31%   |
| DisplayLink                     | 1         | 0.31%   |
| Dell                            | 1         | 0.31%   |
| Davicom Semiconductor           | 1         | 0.31%   |
| D-Link                          | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 73        | 18.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 5.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 2.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.33%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 8         | 2.07%   |
| Intel Wireless 7265                                               | 8         | 2.07%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.55%   |
| Intel Wireless 7260                                               | 6         | 1.55%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 6         | 1.55%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 6         | 1.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 1.55%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 5         | 1.29%   |
| Intel Wi-Fi 6 AX201                                               | 5         | 1.29%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.03%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.03%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.03%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.03%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 1.03%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.78%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                         | 3         | 0.78%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.78%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.78%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 3         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.78%   |
| Realtek 802.11ac NIC                                              | 3         | 0.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.78%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.78%   |
| Intel Wireless 8265 / 8275                                        | 3         | 0.78%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.78%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.78%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.78%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.52%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.52%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 64        | 36.57%  |
| Qualcomm Atheros                | 35        | 20%     |
| Realtek Semiconductor           | 34        | 19.43%  |
| Broadcom                        | 16        | 9.14%   |
| TP-Link                         | 8         | 4.57%   |
| Broadcom Limited                | 7         | 4%      |
| Ralink                          | 3         | 1.71%   |
| MediaTek                        | 2         | 1.14%   |
| Linksys                         | 2         | 1.14%   |
| Ralink Technology               | 1         | 0.57%   |
| Qualcomm Atheros Communications | 1         | 0.57%   |
| Dell                            | 1         | 0.57%   |
| D-Link                          | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 5.06%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 8         | 4.49%   |
| Intel Wireless 7265                                            | 8         | 4.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 3.37%   |
| Intel Wireless 7260                                            | 6         | 3.37%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 3.37%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 6         | 3.37%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 3.37%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 5         | 2.81%   |
| Intel Wi-Fi 6 AX201                                            | 5         | 2.81%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 2.81%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.25%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 2.25%   |
| TP-Link Archer T4U v2 [Realtek RTL8812AU]                      | 3         | 1.69%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.69%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 3         | 1.69%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 1.69%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 3         | 1.69%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 1.69%   |
| Realtek 802.11ac NIC                                           | 3         | 1.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 1.69%   |
| Intel Wireless 8265 / 8275                                     | 3         | 1.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 1.69%   |
| Intel Wireless-AC 9260                                         | 2         | 1.12%   |
| Intel Wireless 8260                                            | 2         | 1.12%   |
| Intel Wireless 3160                                            | 2         | 1.12%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 2         | 1.12%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.12%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.12%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2         | 1.12%   |
| Broadcom Limited BCM4311 802.11a/b/g                           | 2         | 1.12%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.12%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 2         | 1.12%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 1         | 0.56%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1         | 0.56%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.56%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.56%   |
| TP-Link 802.11ac WLAN Adapter                                  | 1         | 0.56%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 110       | 54.73%  |
| Intel                    | 44        | 21.89%  |
| Broadcom                 | 14        | 6.97%   |
| Qualcomm Atheros         | 12        | 5.97%   |
| Xiaomi                   | 3         | 1.49%   |
| Nvidia                   | 3         | 1.49%   |
| Huawei Technologies      | 3         | 1.49%   |
| Microchip Technology     | 2         | 1%      |
| ASIX Electronics         | 2         | 1%      |
| Standard Microsystems    | 1         | 0.5%    |
| MediaTek                 | 1         | 0.5%    |
| Marvell Technology Group | 1         | 0.5%    |
| Lenovo                   | 1         | 0.5%    |
| JMicron Technology       | 1         | 0.5%    |
| DisplayLink              | 1         | 0.5%    |
| Davicom Semiconductor    | 1         | 0.5%    |
| Broadcom Limited         | 1         | 0.5%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 73        | 35.1%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 11.06%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 10        | 4.81%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.88%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.92%   |
| Intel Ethernet Controller I225-V                                  | 4         | 1.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.92%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.44%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.44%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.44%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.44%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.44%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.96%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.96%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 2         | 0.96%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.96%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.96%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.96%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.96%   |
| Huawei ATU-L21                                                    | 2         | 0.96%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.96%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 2         | 0.96%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.96%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.48%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.48%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.48%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.48%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.48%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.48%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.48%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.48%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.48%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.48%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.48%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.48%   |
| MediaTek PRESIDENT_GOLD_10                                        | 1         | 0.48%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.48%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.48%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 186       | 52.69%  |
| WiFi     | 166       | 47.03%  |
| Modem    | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 123       | 56.42%  |
| Ethernet | 95        | 43.58%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 130       | 60.47%  |
| 1     | 71        | 33.02%  |
| 0     | 7         | 3.26%   |
| 3     | 6         | 2.79%   |
| 4     | 1         | 0.47%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 209       | 98.12%  |
| Yes  | 4         | 1.88%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 53        | 41.73%  |
| Realtek Semiconductor           | 15        | 11.81%  |
| Qualcomm Atheros Communications | 15        | 11.81%  |
| Cambridge Silicon Radio         | 9         | 7.09%   |
| Broadcom                        | 9         | 7.09%   |
| Apple                           | 6         | 4.72%   |
| Lite-On Technology              | 4         | 3.15%   |
| Toshiba                         | 3         | 2.36%   |
| ASUSTek Computer                | 3         | 2.36%   |
| IMC Networks                    | 2         | 1.57%   |
| Hewlett-Packard                 | 2         | 1.57%   |
| Foxconn / Hon Hai               | 2         | 1.57%   |
| Realtek                         | 1         | 0.79%   |
| MediaTek                        | 1         | 0.79%   |
| Marvell Semiconductor           | 1         | 0.79%   |
| Dell                            | 1         | 0.79%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                           | 19        | 14.96%  |
| Qualcomm Atheros  Bluetooth Device                           | 13        | 10.24%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 9         | 7.09%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 9         | 7.09%   |
| Realtek Bluetooth Radio                                      | 8         | 6.3%    |
| Intel AX201 Bluetooth                                        | 8         | 6.3%    |
| Realtek  Bluetooth 4.2 Adapter                               | 7         | 5.51%   |
| Intel AX200 Bluetooth                                        | 6         | 4.72%   |
| Apple Bluetooth Host Controller                              | 4         | 3.15%   |
| Intel Centrino Bluetooth Wireless Transceiver                | 3         | 2.36%   |
| Broadcom BCM43142A0 Bluetooth 4.0                            | 3         | 2.36%   |
| Toshiba Bluetooth Device                                     | 2         | 1.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                   | 2         | 1.57%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 2         | 1.57%   |
| Intel Wireless-AC 3168 Bluetooth                             | 2         | 1.57%   |
| Intel Bluetooth Device                                       | 2         | 1.57%   |
| Intel AX210 Bluetooth                                        | 2         | 1.57%   |
| HP Broadcom 2070 Bluetooth Combo                             | 2         | 1.57%   |
| Broadcom HP Portable SoftSailing                             | 2         | 1.57%   |
| Toshiba BCM43142A0                                           | 1         | 0.79%   |
| Realtek 802.11ac WLAN Adapter                                | 1         | 0.79%   |
| Qualcomm Atheros Bluetooth USB Host Controller               | 1         | 0.79%   |
| Qualcomm Atheros AR3011 Bluetooth                            | 1         | 0.79%   |
| MediaTek Wireless_Device                                     | 1         | 0.79%   |
| Marvell Bluetooth and Wireless LAN Composite Device          | 1         | 0.79%   |
| Lite-On Wireless_Device                                      | 1         | 0.79%   |
| Lite-On Bluetooth Device                                     | 1         | 0.79%   |
| IMC Networks Bluetooth Radio                                 | 1         | 0.79%   |
| IMC Networks Bluetooth                                       | 1         | 0.79%   |
| Foxconn / Hon Hai Bluetooth Device                           | 1         | 0.79%   |
| Foxconn / Hon Hai BCM20702A0                                 | 1         | 0.79%   |
| Dell Broadcom BCM20702A0 Bluetooth                           | 1         | 0.79%   |
| Broadcom HP Portable Bumble Bee                              | 1         | 0.79%   |
| Broadcom BCM43142 Bluetooth 4.0                              | 1         | 0.79%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                         | 1         | 0.79%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1         | 0.79%   |
| ASUS Qualcomm Bluetooth 4.1                                  | 1         | 0.79%   |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 1         | 0.79%   |
| ASUS Bluetooth Radio                                         | 1         | 0.79%   |
| Apple Bluetooth USB Host Controller                          | 1         | 0.79%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 161       | 56.1%   |
| AMD                     | 53        | 18.47%  |
| Nvidia                  | 41        | 14.29%  |
| C-Media Electronics     | 4         | 1.39%   |
| GN Netcom               | 3         | 1.05%   |
| Generalplus Technology  | 3         | 1.05%   |
| Sony                    | 2         | 0.7%    |
| Logitech                | 2         | 0.7%    |
| JMTek                   | 2         | 0.7%    |
| Soundprese              | 1         | 0.35%   |
| Realtek Semiconductor   | 1         | 0.35%   |
| Plantronics             | 1         | 0.35%   |
| Medeli Electronics      | 1         | 0.35%   |
| Lenovo                  | 1         | 0.35%   |
| Ensoniq                 | 1         | 0.35%   |
| DCMT Technology         | 1         | 0.35%   |
| Creative Labs           | 1         | 0.35%   |
| Corsair                 | 1         | 0.35%   |
| CMX Systems             | 1         | 0.35%   |
| Blue Microphones        | 1         | 0.35%   |
| BEHRINGER International | 1         | 0.35%   |
| Astro Gaming            | 1         | 0.35%   |
| Argosy Research         | 1         | 0.35%   |
| Afatech                 | 1         | 0.35%   |
| A-DATA Technology       | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 5.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 4.37%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 4.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 4.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 3.5%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 12        | 3.5%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 10        | 2.92%   |
| Intel Cannon Lake PCH cAVS                                                                        | 9         | 2.62%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 9         | 2.62%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.33%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.33%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.33%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 2.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 7         | 2.04%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 2.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.04%   |
| Intel Broadwell-U Audio Controller                                                                | 7         | 2.04%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 2.04%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 1.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 1.75%   |
| AMD FCH Azalia Controller                                                                         | 6         | 1.75%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.46%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.46%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 5         | 1.46%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 1.17%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.17%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 4         | 1.17%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.87%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 3         | 0.87%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 3         | 0.87%   |
| Intel Alder Lake-S HD Audio Controller                                                            | 3         | 0.87%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 0.87%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 0.87%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 0.87%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 0.87%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 32        | 22.7%   |
| SK hynix            | 22        | 15.6%   |
| Micron Technology   | 20        | 14.18%  |
| Kingston            | 20        | 14.18%  |
| Crucial             | 11        | 7.8%    |
| Corsair             | 8         | 5.67%   |
| A-DATA Technology   | 6         | 4.26%   |
| Unknown             | 5         | 3.55%   |
| Team                | 4         | 2.84%   |
| Nanya Technology    | 4         | 2.84%   |
| Patriot             | 2         | 1.42%   |
| Unknown (ABCD)      | 1         | 0.71%   |
| Super Talent        | 1         | 0.71%   |
| Ramaxel Technology  | 1         | 0.71%   |
| Kimtigo             | 1         | 0.71%   |
| G.Skill             | 1         | 0.71%   |
| fef5                | 1         | 0.71%   |
| Unknown             | 1         | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 5         | 3.11%   |
| Team RAM TEAMGROUP-SD4-2666 16GB SODIMM DDR4 2667MT/s            | 4         | 2.48%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 2.48%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s      | 4         | 2.48%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s                      | 4         | 2.48%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s                      | 4         | 2.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.86%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.86%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM DDR3 1600MT/s            | 3         | 1.86%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 1.24%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 1.24%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.24%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.24%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.24%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 1.24%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.24%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.24%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 1.24%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.24%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 1.24%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 2         | 1.24%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s             | 2         | 1.24%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s                      | 1         | 0.62%   |
| Unknown RAM Module 8GB SODIMM DDR3                               | 1         | 0.62%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 0.62%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.62%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.62%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 1         | 0.62%   |
| Super Talent RAM SUPERTALENT02 8GB SODIMM DDR3 1600MT/s          | 1         | 0.62%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1867MT/s                  | 1         | 0.62%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s                      | 1         | 0.62%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.62%   |
| SK hynix RAM HMT451U6AFR8C-PB 4096MB DIMM DDR3 1600MT/s          | 1         | 0.62%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.62%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.62%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s             | 1         | 0.62%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.62%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.62%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.62%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 1         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 53        | 44.54%  |
| DDR3    | 47        | 39.5%   |
| LPDDR4  | 7         | 5.88%   |
| SDRAM   | 4         | 3.36%   |
| DDR2    | 4         | 3.36%   |
| DDR5    | 2         | 1.68%   |
| Unknown | 2         | 1.68%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 75        | 65.22%  |
| DIMM         | 31        | 26.96%  |
| Row Of Chips | 7         | 6.09%   |
| Chip         | 1         | 0.87%   |
| Unknown      | 1         | 0.87%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 51        | 38.35%  |
| 8192  | 44        | 33.08%  |
| 16384 | 16        | 12.03%  |
| 2048  | 12        | 9.02%   |
| 32768 | 9         | 6.77%   |
| 1024  | 1         | 0.75%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 35        | 25.93%  |
| 2667    | 23        | 17.04%  |
| 3200    | 11        | 8.15%   |
| 1333    | 11        | 8.15%   |
| 2400    | 7         | 5.19%   |
| 1334    | 5         | 3.7%    |
| 667     | 5         | 3.7%    |
| 4267    | 4         | 2.96%   |
| 3600    | 4         | 2.96%   |
| 3266    | 4         | 2.96%   |
| 2133    | 4         | 2.96%   |
| 2933    | 3         | 2.22%   |
| 4800    | 2         | 1.48%   |
| 4199    | 2         | 1.48%   |
| Unknown | 2         | 1.48%   |
| 8400    | 1         | 0.74%   |
| 3866    | 1         | 0.74%   |
| 3466    | 1         | 0.74%   |
| 3400    | 1         | 0.74%   |
| 3100    | 1         | 0.74%   |
| 2934    | 1         | 0.74%   |
| 2800    | 1         | 0.74%   |
| 2666    | 1         | 0.74%   |
| 2448    | 1         | 0.74%   |
| 1867    | 1         | 0.74%   |
| 1866    | 1         | 0.74%   |
| 1800    | 1         | 0.74%   |
| 1067    | 1         | 0.74%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 3         | 37.5%   |
| Hewlett-Packard | 3         | 37.5%   |
| Canon           | 2         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L380 Series            | 1         | 12.5%   |
| Seiko Epson L3110 Series           | 1         | 12.5%   |
| Seiko Epson L222 Series            | 1         | 12.5%   |
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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 29        | 19.59%  |
| Microdia                               | 16        | 10.81%  |
| Realtek Semiconductor                  | 15        | 10.14%  |
| IMC Networks                           | 13        | 8.78%   |
| Sunplus Innovation Technology          | 11        | 7.43%   |
| Logitech                               | 9         | 6.08%   |
| Apple                                  | 7         | 4.73%   |
| Quanta                                 | 5         | 3.38%   |
| Microsoft                              | 5         | 3.38%   |
| Primax Electronics                     | 4         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.7%    |
| Suyin                                  | 3         | 2.03%   |
| Lite-On Technology                     | 3         | 2.03%   |
| Alcor Micro                            | 3         | 2.03%   |
| Z-Star Microelectronics                | 2         | 1.35%   |
| Syntek                                 | 2         | 1.35%   |
| Silicon Motion                         | 2         | 1.35%   |
| Luxvisions Innotech Limited            | 2         | 1.35%   |
| Acer                                   | 2         | 1.35%   |
| TANDBERG                               | 1         | 0.68%   |
| Philips (or NXP)                       | 1         | 0.68%   |
| LG Electronics                         | 1         | 0.68%   |
| Importek                               | 1         | 0.68%   |
| Huawei Technologies                    | 1         | 0.68%   |
| GEMBIRD                                | 1         | 0.68%   |
| Creative Technology                    | 1         | 0.68%   |
| Bison Electronics                      | 1         | 0.68%   |
| Aveo Technology                        | 1         | 0.68%   |
| Arkmicro Technologies                  | 1         | 0.68%   |
| Alpha Imaging Technology               | 1         | 0.68%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                    | 9         | 5.96%   |
| Realtek Integrated_Webcam_HD                     | 7         | 4.64%   |
| Chicony Integrated Camera                        | 7         | 4.64%   |
| Sunplus HD Webcam                                | 5         | 3.31%   |
| IMC Networks Integrated Camera                   | 5         | 3.31%   |
| Apple FaceTime HD Camera                         | 4         | 2.65%   |
| Sunplus Integrated_Webcam_HD                     | 3         | 1.99%   |
| Primax HP HD Webcam [Fixed]                      | 3         | 1.99%   |
| Microsoft LifeCam HD-3000                        | 3         | 1.99%   |
| Logitech Webcam C270                             | 3         | 1.99%   |
| Chicony TOSHIBA Web Camera - HD                  | 3         | 1.99%   |
| Syntek EasyCamera                                | 2         | 1.32%   |
| Realtek Integrated Webcam HD                     | 2         | 1.32%   |
| Realtek Integrated Webcam                        | 2         | 1.32%   |
| Quanta HD WebCam                                 | 2         | 1.32%   |
| Microdia USB 2.0 Camera                          | 2         | 1.32%   |
| Microdia Integrated Webcam                       | 2         | 1.32%   |
| Microdia Integrated Camera                       | 2         | 1.32%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 2         | 1.32%   |
| IMC Networks USB2.0 HD UVC WebCam                | 2         | 1.32%   |
| Chicony USB 2.0 Camera                           | 2         | 1.32%   |
| Chicony Integrated HP HD Webcam                  | 2         | 1.32%   |
| Chicony HP Truevision HD                         | 2         | 1.32%   |
| Chicony HP HD Webcam                             | 2         | 1.32%   |
| Chicony 720p HD Camera                           | 2         | 1.32%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 2         | 1.32%   |
| Z-Star Vimicro USB Camera (Altair)               | 1         | 0.66%   |
| Z-Star Vega USB2.0 Camera                        | 1         | 0.66%   |
| TANDBERG PrecisionHD Camera                      | 1         | 0.66%   |
| Suyin TOSHIBA Web Camera - HD                    | 1         | 0.66%   |
| Suyin HP TrueVision HD                           | 1         | 0.66%   |
| Suyin 1.3M HD WebCam                             | 1         | 0.66%   |
| Sunplus Laptop_Integrated_Webcam_HD              | 1         | 0.66%   |
| Sunplus HP HD Webcam [Fixed]                     | 1         | 0.66%   |
| Sunplus Dell Integrated Webcam                   | 1         | 0.66%   |
| Silicon Motion Silicon Motion Camera             | 1         | 0.66%   |
| Silicon Motion ATIV Real HD Camera               | 1         | 0.66%   |
| Realtek USB Camera                               | 1         | 0.66%   |
| Realtek Rear Camera                              | 1         | 0.66%   |
| Realtek HP Wide Vision FHD Camera                | 1         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 13        | 52%     |
| Synaptics                  | 5         | 20%     |
| Shenzhen Goodix Technology | 2         | 8%      |
| STMicroelectronics         | 1         | 4%      |
| Samsung Electronics        | 1         | 4%      |
| LighTuning Technology      | 1         | 4%      |
| Elan Microelectronics      | 1         | 4%      |
| AuthenTec                  | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 3         | 12%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 3         | 12%     |
| Validity Sensors VFS491                           | 2         | 8%      |
| Validity Sensors VFS471 Fingerprint Reader        | 2         | 8%      |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 8%      |
| Validity Sensors Synaptics WBDI                   | 2         | 8%      |
| Synaptics WBDI                                    | 2         | 8%      |
| Shenzhen Goodix  Fingerprint Device               | 2         | 8%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 4%      |
| Validity Sensors Fingerprint scanner              | 1         | 4%      |
| STMicroelectronics Fingerprint Reader             | 1         | 4%      |
| Samsung Fingerprint Device                        | 1         | 4%      |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 4%      |
| Elan ELAN:ARM-M4                                  | 1         | 4%      |
| AuthenTec AES1600                                 | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 152       | 69.41%  |
| 1     | 55        | 25.11%  |
| 2     | 8         | 3.65%   |
| 3     | 4         | 1.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 30%     |
| Net/wireless             | 17        | 21.25%  |
| Graphics card            | 15        | 18.75%  |
| Chipcard                 | 11        | 13.75%  |
| Communication controller | 3         | 3.75%   |
| Sound                    | 2         | 2.5%    |
| Multimedia controller    | 2         | 2.5%    |
| Unassigned class         | 1         | 1.25%   |
| Network                  | 1         | 1.25%   |
| Net/ethernet             | 1         | 1.25%   |
| Firewire controller      | 1         | 1.25%   |
| Card reader              | 1         | 1.25%   |
| Bluetooth                | 1         | 1.25%   |

