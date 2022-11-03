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

Total: 288

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 22        | 10.95%  |
| Ubuntu 18.04                 | 17        | 8.46%   |
| OpenMandriva 4.2             | 16        | 7.96%   |
| Ubuntu 22.04                 | 9         | 4.48%   |
| OpenMandriva 4.3             | 7         | 3.48%   |
| Ubuntu 19.04                 | 4         | 1.99%   |
| Lubuntu 22.04                | 4         | 1.99%   |
| Lubuntu 21.10                | 4         | 1.99%   |
| Linux Mint 20.2              | 4         | 1.99%   |
| Linux Mint 19.3              | 4         | 1.99%   |
| Fedora 36                    | 4         | 1.99%   |
| Debian 11                    | 4         | 1.99%   |
| Zorin 16                     | 3         | 1.49%   |
| Lubuntu 21.04                | 3         | 1.49%   |
| Debian 10                    | 3         | 1.49%   |
| Zorin 15                     | 2         | 1%      |
| Xubuntu 20.04                | 2         | 1%      |
| UbuntuDDE 20.04              | 2         | 1%      |
| Ubuntu Studio 20.04          | 2         | 1%      |
| Ubuntu 21.04                 | 2         | 1%      |
| Pop!_OS 21.04                | 2         | 1%      |
| Pop!_OS 20.10                | 2         | 1%      |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1%      |
| Manjaro 20.2.1               | 2         | 1%      |
| Lubuntu 20.04                | 2         | 1%      |
| Linux Mint 20.3              | 2         | 1%      |
| Linux Mint 20.1              | 2         | 1%      |
| Linux Mint 20                | 2         | 1%      |
| KDE neon 20.04               | 2         | 1%      |
| Fedora 35                    | 2         | 1%      |
| Fedora 34                    | 2         | 1%      |
| Fedora 32                    | 2         | 1%      |
| EndeavourOS Rolling          | 2         | 1%      |
| Debian Testing               | 2         | 1%      |
| Arch                         | 2         | 1%      |
| Zorin 12                     | 1         | 0.5%    |
| Xubuntu 18.04                | 1         | 0.5%    |
| Ubuntu Unity 18.04           | 1         | 0.5%    |
| Ubuntu Unity 16.04           | 1         | 0.5%    |
| Ubuntu MATE 18.04            | 1         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 56        | 29.79%  |
| OpenMandriva  | 24        | 12.77%  |
| Linux Mint    | 15        | 7.98%   |
| Fedora        | 12        | 6.38%   |
| Manjaro       | 9         | 4.79%   |
| Debian        | 9         | 4.79%   |
| Lubuntu       | 8         | 4.26%   |
| Zorin         | 6         | 3.19%   |
| Pop!_OS       | 6         | 3.19%   |
| ROSA          | 4         | 2.13%   |
| Xubuntu       | 3         | 1.6%    |
| KDE neon      | 3         | 1.6%    |
| Elementary    | 3         | 1.6%    |
| Arch          | 3         | 1.6%    |
| UbuntuDDE     | 2         | 1.06%   |
| Ubuntu Unity  | 2         | 1.06%   |
| Ubuntu Studio | 2         | 1.06%   |
| openSUSE      | 2         | 1.06%   |
| Kubuntu       | 2         | 1.06%   |
| Kali          | 2         | 1.06%   |
| Endless       | 2         | 1.06%   |
| EndeavourOS   | 2         | 1.06%   |
| Ubuntu MATE   | 1         | 0.53%   |
| Reborn OS     | 1         | 0.53%   |
| Raspbian      | 1         | 0.53%   |
| PureOS        | 1         | 0.53%   |
| Peppermint    | 1         | 0.53%   |
| Parrot        | 1         | 0.53%   |
| LMDE          | 1         | 0.53%   |
| Clear Linux   | 1         | 0.53%   |
| BlackPanther  | 1         | 0.53%   |
| ArcoLinux     | 1         | 0.53%   |
| ALT Linux     | 1         | 0.53%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 16        | 7.31%   |
| 5.16.7-desktop-1omv4003  | 7         | 3.2%    |
| 5.4.0-42-generic         | 5         | 2.28%   |
| 5.4.0-70-generic         | 4         | 1.83%   |
| 5.13.0-16-generic        | 4         | 1.83%   |
| 5.11.0-27-generic        | 4         | 1.83%   |
| 5.0.0-23-generic         | 4         | 1.83%   |
| 5.8.0-50-generic         | 3         | 1.37%   |
| 5.4.0-77-generic         | 3         | 1.37%   |
| 5.0.0-25-generic         | 3         | 1.37%   |
| 5.9.16-1-MANJARO         | 2         | 0.91%   |
| 5.8.0-7630-generic       | 2         | 0.91%   |
| 5.4.0-52-generic         | 2         | 0.91%   |
| 5.4.0-29-generic         | 2         | 0.91%   |
| 5.4.0-26-generic         | 2         | 0.91%   |
| 5.4.0-21-generic         | 2         | 0.91%   |
| 5.3.0-40-generic         | 2         | 0.91%   |
| 5.3.0-28-generic         | 2         | 0.91%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.91%   |
| 5.15.0-41-generic        | 2         | 0.91%   |
| 5.15.0-27-generic        | 2         | 0.91%   |
| 5.15.0-25-generic        | 2         | 0.91%   |
| 5.13.0-35-generic        | 2         | 0.91%   |
| 5.13.0-20-generic        | 2         | 0.91%   |
| 5.11.0-16-generic        | 2         | 0.91%   |
| 4.19.0-8-amd64           | 2         | 0.91%   |
| 4.15.0-112-generic       | 2         | 0.91%   |
| 6.0.2-2-MANJARO          | 1         | 0.46%   |
| 5.9.9-arch1-1            | 1         | 0.46%   |
| 5.9.14-arch1-1           | 1         | 0.46%   |
| 5.9.11-3-MANJARO         | 1         | 0.46%   |
| 5.8.6-1-MANJARO          | 1         | 0.46%   |
| 5.8.0-55-generic         | 1         | 0.46%   |
| 5.8.0-53-generic         | 1         | 0.46%   |
| 5.8.0-41-generic         | 1         | 0.46%   |
| 5.8.0-34-generic         | 1         | 0.46%   |
| 5.7.0-2parrot2-amd64     | 1         | 0.46%   |
| 5.7.0-1-amd64            | 1         | 0.46%   |
| 5.6.19-300.fc32.x86_64   | 1         | 0.46%   |
| 5.6.16-300.fc32.x86_64   | 1         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 17.56%  |
| 5.10.14 | 16        | 7.8%    |
| 5.15.0  | 15        | 7.32%   |
| 5.11.0  | 15        | 7.32%   |
| 4.15.0  | 12        | 5.85%   |
| 5.3.0   | 10        | 4.88%   |
| 5.13.0  | 10        | 4.88%   |
| 5.8.0   | 9         | 4.39%   |
| 5.0.0   | 9         | 4.39%   |
| 5.10.0  | 8         | 3.9%    |
| 5.16.7  | 7         | 3.41%   |
| 5.18.13 | 3         | 1.46%   |
| 4.19.0  | 3         | 1.46%   |
| 5.9.16  | 2         | 0.98%   |
| 5.7.0   | 2         | 0.98%   |
| 4.18.0  | 2         | 0.98%   |
| 6.0.2   | 1         | 0.49%   |
| 5.9.9   | 1         | 0.49%   |
| 5.9.14  | 1         | 0.49%   |
| 5.9.11  | 1         | 0.49%   |
| 5.8.6   | 1         | 0.49%   |
| 5.6.19  | 1         | 0.49%   |
| 5.6.16  | 1         | 0.49%   |
| 5.6.14  | 1         | 0.49%   |
| 5.6.13  | 1         | 0.49%   |
| 5.4.40  | 1         | 0.49%   |
| 5.2.11  | 1         | 0.49%   |
| 5.19.6  | 1         | 0.49%   |
| 5.19.4  | 1         | 0.49%   |
| 5.19.11 | 1         | 0.49%   |
| 5.18.16 | 1         | 0.49%   |
| 5.18.12 | 1         | 0.49%   |
| 5.18.0  | 1         | 0.49%   |
| 5.17.9  | 1         | 0.49%   |
| 5.15.32 | 1         | 0.49%   |
| 5.15.23 | 1         | 0.49%   |
| 5.15.13 | 1         | 0.49%   |
| 5.15.11 | 1         | 0.49%   |
| 5.14.14 | 1         | 0.49%   |
| 5.14.0  | 1         | 0.49%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 37        | 18.14%  |
| 5.10    | 31        | 15.2%   |
| 5.15    | 19        | 9.31%   |
| 5.11    | 19        | 9.31%   |
| 4.15    | 12        | 5.88%   |
| 5.13    | 11        | 5.39%   |
| 5.8     | 10        | 4.9%    |
| 5.3     | 10        | 4.9%    |
| 5.0     | 10        | 4.9%    |
| 5.16    | 7         | 3.43%   |
| 5.18    | 6         | 2.94%   |
| 5.9     | 5         | 2.45%   |
| 5.6     | 4         | 1.96%   |
| 4.19    | 4         | 1.96%   |
| 5.19    | 3         | 1.47%   |
| 5.12    | 3         | 1.47%   |
| 4.18    | 3         | 1.47%   |
| 5.7     | 2         | 0.98%   |
| 5.14    | 2         | 0.98%   |
| 4.1     | 2         | 0.98%   |
| 6.0     | 1         | 0.49%   |
| 5.2     | 1         | 0.49%   |
| 5.17    | 1         | 0.49%   |
| 4.9     | 1         | 0.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 172       | 96.63%  |
| i686   | 5         | 2.81%   |
| armv7l | 1         | 0.56%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 77        | 42.08%  |
| KDE5          | 33        | 18.03%  |
| Unknown       | 19        | 10.38%  |
| XFCE          | 13        | 7.1%    |
| X-Cinnamon    | 8         | 4.37%   |
| LXQt          | 7         | 3.83%   |
| MATE          | 6         | 3.28%   |
| KDE           | 4         | 2.19%   |
| Pantheon      | 3         | 1.64%   |
| LXDE          | 3         | 1.64%   |
| Unity         | 2         | 1.09%   |
| i3            | 2         | 1.09%   |
| Deepin        | 2         | 1.09%   |
| Cinnamon      | 2         | 1.09%   |
| Openbox       | 1         | 0.55%   |
| GNOME Classic | 1         | 0.55%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 141       | 78.33%  |
| Wayland | 28        | 15.56%  |
| Unknown | 8         | 4.44%   |
| Tty     | 3         | 1.67%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 44.57%  |
| SDDM    | 43        | 23.37%  |
| GDM     | 19        | 10.33%  |
| LightDM | 16        | 8.7%    |
| GDM3    | 13        | 7.07%   |
| TDM     | 11        | 5.98%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 75        | 40.76%  |
| es_CR   | 72        | 39.13%  |
| Unknown | 19        | 10.33%  |
| es_ES   | 10        | 5.43%   |
| C       | 3         | 1.63%   |
| en_GB   | 2         | 1.09%   |
| fr_FR   | 1         | 0.54%   |
| es_MX   | 1         | 0.54%   |
| de_DE   | 1         | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 96        | 53.04%  |
| BIOS | 85        | 46.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 137       | 74.86%  |
| Overlay | 25        | 13.66%  |
| Btrfs   | 14        | 7.65%   |
| Unknown | 5         | 2.73%   |
| Xfs     | 2         | 1.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 93        | 51.38%  |
| GPT     | 67        | 37.02%  |
| MBR     | 21        | 11.6%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 160       | 87.91%  |
| Yes       | 22        | 12.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 110       | 60.77%  |
| Yes       | 71        | 39.23%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 39        | 21.91%  |
| Hewlett-Packard         | 29        | 16.29%  |
| ASUSTek Computer        | 19        | 10.67%  |
| Lenovo                  | 18        | 10.11%  |
| Toshiba                 | 11        | 6.18%   |
| Gigabyte Technology     | 9         | 5.06%   |
| Acer                    | 9         | 5.06%   |
| MSI                     | 7         | 3.93%   |
| ASRock                  | 6         | 3.37%   |
| Apple                   | 6         | 3.37%   |
| Unknown                 | 3         | 1.69%   |
| Intel                   | 2         | 1.12%   |
| ZOTAC                   | 1         | 0.56%   |
| TPV-INVENTA             | 1         | 0.56%   |
| System76                | 1         | 0.56%   |
| Supermicro              | 1         | 0.56%   |
| Sony                    | 1         | 0.56%   |
| Samsung Electronics     | 1         | 0.56%   |
| Raspberry Pi Foundation | 1         | 0.56%   |
| Purism                  | 1         | 0.56%   |
| Pegatron                | 1         | 0.56%   |
| Olivetti                | 1         | 0.56%   |
| Microsoft               | 1         | 0.56%   |
| MACHINIST               | 1         | 0.56%   |
| HUAWEI                  | 1         | 0.56%   |
| Google                  | 1         | 0.56%   |
| Gateway                 | 1         | 0.56%   |
| Deffad                  | 1         | 0.56%   |
| Biostar                 | 1         | 0.56%   |
| AZW                     | 1         | 0.56%   |
| Alienware               | 1         | 0.56%   |
| ABIT                    | 1         | 0.56%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell OptiPlex 3020                       | 5         | 2.81%   |
| Unknown                                  | 5         | 2.81%   |
| Apple MacBookPro8,1                      | 4         | 2.25%   |
| Dell Inspiron 5584                       | 3         | 1.69%   |
| HP ProBook 6460b                         | 2         | 1.12%   |
| HP Pavilion Notebook                     | 2         | 1.12%   |
| HP Notebook                              | 2         | 1.12%   |
| HP Laptop 15-da0xxx                      | 2         | 1.12%   |
| Gigabyte B250M-DS3H                      | 2         | 1.12%   |
| Dell OptiPlex 7040                       | 2         | 1.12%   |
| ASUS PRIME A320M-K                       | 2         | 1.12%   |
| ASRock B450 Steel Legend                 | 2         | 1.12%   |
| ZOTAC NM10                               | 1         | 0.56%   |
| TPV-INVENTA 18-2003LA                    | 1         | 0.56%   |
| Toshiba Satellite X205                   | 1         | 0.56%   |
| Toshiba Satellite L655                   | 1         | 0.56%   |
| Toshiba Satellite L45-B                  | 1         | 0.56%   |
| Toshiba Satellite C855D                  | 1         | 0.56%   |
| Toshiba Satellite C845                   | 1         | 0.56%   |
| Toshiba Satellite C645D                  | 1         | 0.56%   |
| Toshiba Satellite C55-C                  | 1         | 0.56%   |
| Toshiba Satellite C55-B                  | 1         | 0.56%   |
| Toshiba Satellite C45-A                  | 1         | 0.56%   |
| Toshiba Satellite A305D                  | 1         | 0.56%   |
| Toshiba QOSMIO X775                      | 1         | 0.56%   |
| System76 Lemur                           | 1         | 0.56%   |
| Supermicro X9DAi                         | 1         | 0.56%   |
| Sony SVD13215PLB                         | 1         | 0.56%   |
| Samsung 930QAA                           | 1         | 0.56%   |
| RPi Raspberry Pi 3 Model B Plus Rev 1.3  | 1         | 0.56%   |
| Purism Librem 15 v3                      | 1         | 0.56%   |
| Pegatron CQ2728LA                        | 1         | 0.56%   |
| Olivetti CL133A                          | 1         | 0.56%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1         | 0.56%   |
| MSI MS-7B86                              | 1         | 0.56%   |
| MSI MS-7693                              | 1         | 0.56%   |
| MSI MS-7636                              | 1         | 0.56%   |
| MSI GF75 Thin 9SD                        | 1         | 0.56%   |
| MSI GF65 Thin 10SDR                      | 1         | 0.56%   |
| MSI GE60 2OC\2OD\2OE                     | 1         | 0.56%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 11        | 6.18%   |
| Dell Inspiron         | 11        | 6.18%   |
| Toshiba Satellite     | 10        | 5.62%   |
| Dell Latitude         | 10        | 5.62%   |
| Dell OptiPlex         | 9         | 5.06%   |
| HP Pavilion           | 7         | 3.93%   |
| Acer Aspire           | 7         | 3.93%   |
| HP Laptop             | 5         | 2.81%   |
| Unknown               | 5         | 2.81%   |
| Lenovo IdeaPad        | 4         | 2.25%   |
| HP ProBook            | 4         | 2.25%   |
| Dell Precision        | 4         | 2.25%   |
| ASUS PRIME            | 4         | 2.25%   |
| Apple MacBookPro8     | 4         | 2.25%   |
| HP EliteBook          | 3         | 1.69%   |
| ASUS VivoBook         | 3         | 1.69%   |
| Lenovo IdeaPadFlex    | 2         | 1.12%   |
| HP Notebook           | 2         | 1.12%   |
| Gigabyte B250M-DS3H   | 2         | 1.12%   |
| Dell XPS              | 2         | 1.12%   |
| Dell G3               | 2         | 1.12%   |
| ASUS TUF              | 2         | 1.12%   |
| ASUS Strix            | 2         | 1.12%   |
| ASRock B450           | 2         | 1.12%   |
| ZOTAC NM10            | 1         | 0.56%   |
| TPV-INVENTA 18-2003LA | 1         | 0.56%   |
| Toshiba QOSMIO        | 1         | 0.56%   |
| System76 Lemur        | 1         | 0.56%   |
| Supermicro X9DAi      | 1         | 0.56%   |
| Sony SVD13215PLB      | 1         | 0.56%   |
| Samsung 930QAA        | 1         | 0.56%   |
| RPi Raspberry         | 1         | 0.56%   |
| Purism Librem         | 1         | 0.56%   |
| Pegatron CQ2728LA     | 1         | 0.56%   |
| Olivetti CL133A       | 1         | 0.56%   |
| MSI Z390              | 1         | 0.56%   |
| MSI MS-7B86           | 1         | 0.56%   |
| MSI MS-7693           | 1         | 0.56%   |
| MSI MS-7636           | 1         | 0.56%   |
| MSI GF75              | 1         | 0.56%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 24        | 13.48%  |
| 2014    | 18        | 10.11%  |
| 2018    | 17        | 9.55%   |
| 2017    | 14        | 7.87%   |
| 2011    | 14        | 7.87%   |
| 2016    | 13        | 7.3%    |
| 2013    | 13        | 7.3%    |
| 2020    | 12        | 6.74%   |
| 2012    | 11        | 6.18%   |
| 2015    | 10        | 5.62%   |
| 2008    | 7         | 3.93%   |
| 2010    | 6         | 3.37%   |
| 2021    | 4         | 2.25%   |
| 2007    | 4         | 2.25%   |
| 2009    | 3         | 1.69%   |
| 2006    | 3         | 1.69%   |
| 2022    | 2         | 1.12%   |
| 2005    | 2         | 1.12%   |
| Unknown | 1         | 0.56%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 110       | 61.8%   |
| Desktop        | 58        | 32.58%  |
| Convertible    | 4         | 2.25%   |
| All in one     | 3         | 1.69%   |
| System on chip | 1         | 0.56%   |
| Tablet         | 1         | 0.56%   |
| Server         | 1         | 0.56%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 162       | 91.01%  |
| Enabled  | 16        | 8.99%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 176       | 98.88%  |
| Yes  | 2         | 1.12%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 40        | 22.22%  |
| 3.01-4.0        | 39        | 21.67%  |
| 8.01-16.0       | 38        | 21.11%  |
| 16.01-24.0      | 33        | 18.33%  |
| 32.01-64.0      | 11        | 6.11%   |
| 1.01-2.0        | 9         | 5%      |
| 2.01-3.0        | 4         | 2.22%   |
| 64.01-256.0     | 3         | 1.67%   |
| More than 256.0 | 1         | 0.56%   |
| 24.01-32.0      | 1         | 0.56%   |
| 0.51-1.0        | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 84        | 43.3%   |
| 2.01-3.0   | 46        | 23.71%  |
| 4.01-8.0   | 24        | 12.37%  |
| 3.01-4.0   | 20        | 10.31%  |
| 0.51-1.0   | 10        | 5.15%   |
| 8.01-16.0  | 4         | 2.06%   |
| 0.01-0.5   | 4         | 2.06%   |
| 24.01-32.0 | 1         | 0.52%   |
| 16.01-24.0 | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 125       | 68.31%  |
| 2      | 40        | 21.86%  |
| 3      | 9         | 4.92%   |
| 4      | 6         | 3.28%   |
| 8      | 1         | 0.55%   |
| 7      | 1         | 0.55%   |
| 5      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 98        | 54.14%  |
| Yes       | 83        | 45.86%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 160       | 89.89%  |
| No        | 18        | 10.11%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 139       | 77.22%  |
| No        | 41        | 22.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 101       | 55.8%   |
| No        | 80        | 44.2%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Costa Rica | 178       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San José     | 73        | 37.82%  |
| Heredia       | 42        | 21.76%  |
| Alajuela      | 16        | 8.29%   |
| Escazu        | 6         | 3.11%   |
| Cartago       | 6         | 3.11%   |
| Quesada       | 4         | 2.07%   |
| Grecia        | 4         | 2.07%   |
| San Ramon     | 3         | 1.55%   |
| Liberia       | 3         | 1.55%   |
| Tres Rios     | 2         | 1.04%   |
| Siquirres     | 2         | 1.04%   |
| Santa Fe      | 2         | 1.04%   |
| Santa Cruz    | 2         | 1.04%   |
| San Pedro     | 2         | 1.04%   |
| Palmares      | 2         | 1.04%   |
| Nosara        | 2         | 1.04%   |
| Naranjo       | 2         | 1.04%   |
| Esparza       | 2         | 1.04%   |
| Curridabat    | 2         | 1.04%   |
| Zarcero       | 1         | 0.52%   |
| Tibas         | 1         | 0.52%   |
| Santo Domingo | 1         | 0.52%   |
| Santiago      | 1         | 0.52%   |
| Santa Ana     | 1         | 0.52%   |
| San Pablo     | 1         | 0.52%   |
| San Juan      | 1         | 0.52%   |
| San Francisco | 1         | 0.52%   |
| Quepos        | 1         | 0.52%   |
| Puntarenas    | 1         | 0.52%   |
| Guacima       | 1         | 0.52%   |
| Colon         | 1         | 0.52%   |
| Bajo Perez    | 1         | 0.52%   |
| Bagaces       | 1         | 0.52%   |
| Alpes         | 1         | 0.52%   |
| Alajuelita    | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 38        | 51     | 15.64%  |
| Seagate               | 38        | 65     | 15.64%  |
| Toshiba               | 26        | 31     | 10.7%   |
| Samsung Electronics   | 19        | 32     | 7.82%   |
| A-DATA Technology     | 17        | 17     | 7%      |
| Kingston              | 15        | 24     | 6.17%   |
| Intel                 | 12        | 17     | 4.94%   |
| HGST                  | 10        | 11     | 4.12%   |
| Unknown               | 8         | 13     | 3.29%   |
| SanDisk               | 7         | 8      | 2.88%   |
| Hitachi               | 6         | 9      | 2.47%   |
| SK hynix              | 5         | 10     | 2.06%   |
| Crucial               | 5         | 5      | 2.06%   |
| XPG                   | 4         | 4      | 1.65%   |
| Patriot               | 4         | 4      | 1.65%   |
| Realtek Semiconductor | 3         | 4      | 1.23%   |
| Micron Technology     | 3         | 3      | 1.23%   |
| ZOTAC                 | 2         | 3      | 0.82%   |
| Team                  | 2         | 2      | 0.82%   |
| Maxtor                | 2         | 2      | 0.82%   |
| LITEONIT              | 2         | 2      | 0.82%   |
| JMicron Technology    | 2         | 2      | 0.82%   |
| Zheino                | 1         | 1      | 0.41%   |
| WD MediaMax           | 1         | 1      | 0.41%   |
| UMIS                  | 1         | 1      | 0.41%   |
| Transcend             | 1         | 1      | 0.41%   |
| Silicon Motion        | 1         | 1      | 0.41%   |
| Netac                 | 1         | 1      | 0.41%   |
| Fujitsu               | 1         | 1      | 0.41%   |
| FORESEE               | 1         | 1      | 0.41%   |
| Dell                  | 1         | 1      | 0.41%   |
| CT120BX5              | 1         | 1      | 0.41%   |
| Apple                 | 1         | 2      | 0.41%   |
| ADATA Technology      | 1         | 1      | 0.41%   |
| Unknown               | 1         | 1      | 0.41%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 7         | 2.65%   |
| A-DATA SU630 480GB SSD                 | 6         | 2.27%   |
| Toshiba MQ01ABF050 500GB               | 5         | 1.89%   |
| Toshiba MQ01ABD100 1TB                 | 5         | 1.89%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 3         | 1.14%   |
| WDC WD10EZEX-75WN4A1 1TB               | 3         | 1.14%   |
| Toshiba KBG30ZMS256G NVMe 256GB        | 3         | 1.14%   |
| Toshiba DT01ACA100 1TB                 | 3         | 1.14%   |
| Seagate ST1000DM003-1CH162 1TB         | 3         | 1.14%   |
| Kingston SV300S37A120G 120GB SSD       | 3         | 1.14%   |
| Intel SSDSC2BF180A4H 180GB             | 3         | 1.14%   |
| Intel SSDSA2CW300G3 304GB              | 3         | 1.14%   |
| HGST HTS541010A9E680 1TB               | 3         | 1.14%   |
| XPG GAMMIX S11 Pro 1TB                 | 2         | 0.76%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 2         | 0.76%   |
| WDC WD5000LPCX-60VHAT0 500GB           | 2         | 0.76%   |
| WDC WD10EZEX-08WN4A0 1TB               | 2         | 0.76%   |
| Toshiba NVMe SSD Drive 256GB           | 2         | 0.76%   |
| SK hynix NVMe SSD Drive 128GB          | 2         | 0.76%   |
| Seagate ST8000DM004-2CX188 8TB         | 2         | 0.76%   |
| Seagate ST380815AS 80GB                | 2         | 0.76%   |
| Seagate ST2000LM007-1R8174 2TB         | 2         | 0.76%   |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 0.76%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 2         | 0.76%   |
| Seagate ST1000DM010-2EP102 1TB         | 2         | 0.76%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 0.76%   |
| Patriot P210 256GB SSD                 | 2         | 0.76%   |
| JMicron Generic 500GB                  | 2         | 0.76%   |
| Intel SSDSC2MH250A2 250GB              | 2         | 0.76%   |
| HGST HTS541075A9E680 752GB             | 2         | 0.76%   |
| A-DATA SU650 120GB SSD                 | 2         | 0.76%   |
| ZOTAC ZTSSD-S11-240G-P 240GB           | 1         | 0.38%   |
| ZOTAC ZTSSD-S11-120G-MD 120GB          | 1         | 0.38%   |
| Zheino CHN 25SATAA3 240 240GB          | 1         | 0.38%   |
| XPG NVMe SSD Drive 512GB               | 1         | 0.38%   |
| XPG NVMe SSD Drive 1TB                 | 1         | 0.38%   |
| WDC WDS250G2B0B-00YS70 250GB SSD       | 1         | 0.38%   |
| WDC WDS120G1G0B-00RC30 120GB SSD       | 1         | 0.38%   |
| WDC WD800BEVT-75ZCT2 80GB              | 1         | 0.38%   |
| WDC WD7500BPVT-22HXZT3 752GB           | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 36        | 63     | 33.64%  |
| WDC     | 30        | 35     | 28.04%  |
| Toshiba | 21        | 22     | 19.63%  |
| HGST    | 10        | 11     | 9.35%   |
| Hitachi | 6         | 9      | 5.61%   |
| Maxtor  | 2         | 2      | 1.87%   |
| Fujitsu | 1         | 1      | 0.93%   |
| Apple   | 1         | 1      | 0.93%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 14        | 19     | 17.28%  |
| A-DATA Technology   | 13        | 13     | 16.05%  |
| Samsung Electronics | 10        | 19     | 12.35%  |
| Intel               | 9         | 13     | 11.11%  |
| WDC                 | 7         | 12     | 8.64%   |
| SanDisk             | 6         | 7      | 7.41%   |
| Patriot             | 4         | 4      | 4.94%   |
| Crucial             | 4         | 4      | 4.94%   |
| Micron Technology   | 3         | 3      | 3.7%    |
| ZOTAC               | 2         | 3      | 2.47%   |
| Team                | 2         | 2      | 2.47%   |
| LITEONIT            | 2         | 2      | 2.47%   |
| Transcend           | 1         | 1      | 1.23%   |
| Seagate             | 1         | 1      | 1.23%   |
| Netac               | 1         | 1      | 1.23%   |
| FORESEE             | 1         | 1      | 1.23%   |
| CT120BX5            | 1         | 1      | 1.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 97        | 144    | 43.3%   |
| SSD     | 76        | 106    | 33.93%  |
| NVMe    | 39        | 65     | 17.41%  |
| MMC     | 9         | 14     | 4.02%   |
| Unknown | 3         | 4      | 1.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 156       | 243    | 74.29%  |
| NVMe | 37        | 63     | 17.62%  |
| MMC  | 9         | 14     | 4.29%   |
| SAS  | 8         | 13     | 3.81%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 108       | 141    | 60.34%  |
| 0.51-1.0   | 56        | 84     | 31.28%  |
| 1.01-2.0   | 9         | 11     | 5.03%   |
| 4.01-10.0  | 4         | 12     | 2.23%   |
| 3.01-4.0   | 2         | 2      | 1.12%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 49        | 25.65%  |
| 251-500        | 35        | 18.32%  |
| 501-1000       | 30        | 15.71%  |
| 1-20           | 20        | 10.47%  |
| 51-100         | 19        | 9.95%   |
| 1001-2000      | 13        | 6.81%   |
| More than 3000 | 10        | 5.24%   |
| 21-50          | 8         | 4.19%   |
| Unknown        | 4         | 2.09%   |
| 2001-3000      | 3         | 1.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 88        | 44.9%   |
| 21-50          | 32        | 16.33%  |
| 101-250        | 23        | 11.73%  |
| 51-100         | 18        | 9.18%   |
| 251-500        | 16        | 8.16%   |
| 501-1000       | 6         | 3.06%   |
| More than 3000 | 4         | 2.04%   |
| Unknown        | 4         | 2.04%   |
| 1001-2000      | 3         | 1.53%   |
| 2001-3000      | 2         | 1.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| WDC WD5000LPCX-60VHAT0 500GB                        | 1         | 1      | 5.88%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 1         | 1      | 5.88%   |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 5.88%   |
| Toshiba MK6476GSX 640GB                             | 1         | 1      | 5.88%   |
| Toshiba MK2565GSXV 250GB                            | 1         | 1      | 5.88%   |
| Seagate ST9160412AS 160GB                           | 1         | 1      | 5.88%   |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 2      | 5.88%   |
| SanDisk SD6SB1M-128G-1006 128GB SSD                 | 1         | 1      | 5.88%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 5.88%   |
| Maxtor STM3160215AS 160GB                           | 1         | 1      | 5.88%   |
| Kingston SV300S37A120G 120GB SSD                    | 1         | 1      | 5.88%   |
| Intel SSDSC2BF180A4H 180GB                          | 1         | 1      | 5.88%   |
| Hitachi HTS547550A9E384 500GB                       | 1         | 2      | 5.88%   |
| Hitachi HDE721010SLA330 1TB                         | 1         | 1      | 5.88%   |
| HGST HTS721010A9E630 1TB                            | 1         | 1      | 5.88%   |
| HGST HTS545050A7E380 500GB                          | 1         | 1      | 5.88%   |
| A-DATA Technology SX8100NP 256GB                    | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 3         | 3      | 17.65%  |
| WDC               | 2         | 2      | 11.76%  |
| Seagate           | 2         | 3      | 11.76%  |
| Hitachi           | 2         | 3      | 11.76%  |
| HGST              | 2         | 2      | 11.76%  |
| SanDisk           | 1         | 1      | 5.88%   |
| Micron Technology | 1         | 1      | 5.88%   |
| Maxtor            | 1         | 1      | 5.88%   |
| Kingston          | 1         | 1      | 5.88%   |
| Intel             | 1         | 1      | 5.88%   |
| A-DATA Technology | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 3         | 3      | 25%     |
| WDC     | 2         | 2      | 16.67%  |
| Seagate | 2         | 3      | 16.67%  |
| Hitachi | 2         | 3      | 16.67%  |
| HGST    | 2         | 2      | 16.67%  |
| Maxtor  | 1         | 1      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 14     | 68.75%  |
| SSD  | 4         | 4      | 25%     |
| NVMe | 1         | 1      | 6.25%   |

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
| Detected | 104       | 191    | 53.61%  |
| Works    | 74        | 123    | 38.14%  |
| Malfunc  | 16        | 19     | 8.25%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 132       | 61.11%  |
| AMD                          | 33        | 15.28%  |
| Samsung Electronics          | 10        | 4.63%   |
| ADATA Technology             | 6         | 2.78%   |
| Realtek Semiconductor        | 5         | 2.31%   |
| ASMedia Technology           | 5         | 2.31%   |
| Toshiba America Info Systems | 4         | 1.85%   |
| SK hynix                     | 4         | 1.85%   |
| SanDisk                      | 4         | 1.85%   |
| Nvidia                       | 3         | 1.39%   |
| Union Memory (Shenzhen)      | 1         | 0.46%   |
| Silicon Motion               | 1         | 0.46%   |
| Silicon Image                | 1         | 0.46%   |
| OCZ Technology Group         | 1         | 0.46%   |
| Micron/Crucial Technology    | 1         | 0.46%   |
| Marvell Technology Group     | 1         | 0.46%   |
| LSI Logic / Symbios Logic    | 1         | 0.46%   |
| Kingston Technology Company  | 1         | 0.46%   |
| JMicron Technology           | 1         | 0.46%   |
| Apple                        | 1         | 0.46%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 22        | 9.05%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 13        | 5.35%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 4.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 11        | 4.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 4.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 3.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 7         | 2.88%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 7         | 2.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 2.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 2.47%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 2.06%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 5         | 2.06%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 5         | 2.06%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 1.65%   |
| Intel SATA Controller [RAID mode]                                                      | 4         | 1.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 4         | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 1.65%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 4         | 1.65%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 1.23%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.23%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 1.23%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 3         | 1.23%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 1.23%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.23%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 3         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 3         | 1.23%   |
| AMD 400 Series Chipset SATA Controller                                                 | 3         | 1.23%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.82%   |
| Realtek Realtek Non-Volatile memory controller                                         | 2         | 0.82%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 2         | 0.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 0.82%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                              | 2         | 0.82%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.82%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 0.82%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 2         | 0.82%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 136       | 61.54%  |
| NVMe | 38        | 17.19%  |
| IDE  | 27        | 12.22%  |
| RAID | 18        | 8.14%   |
| SAS  | 1         | 0.45%   |
| SCSI | 1         | 0.45%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 140       | 78.65%  |
| AMD    | 37        | 20.79%  |
| ARM    | 1         | 0.56%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz                | 5         | 2.81%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 4         | 2.25%   |
| AMD Ryzen 5 3600 6-Core Processor               | 4         | 2.25%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 3         | 1.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 3         | 1.69%   |
| Intel Core i7-2640M CPU @ 2.80GHz               | 3         | 1.69%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 3         | 1.69%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 3         | 1.69%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.12%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 1.12%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 1.12%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 1.12%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 2         | 1.12%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 1.12%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 2         | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.12%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 1.12%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 1.12%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 2         | 1.12%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 2         | 1.12%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 2         | 1.12%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 2         | 1.12%   |
| Intel Core 2 CPU T7200 @ 2.00GHz                | 2         | 1.12%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 2         | 1.12%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 2         | 1.12%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 1.12%   |
| AMD E1-1200 APU with Radeon HD Graphics         | 2         | 1.12%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 2         | 1.12%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz            | 1         | 0.56%   |
| Intel Xeon CPU X5667 @ 3.07GHz                  | 1         | 0.56%   |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1         | 0.56%   |
| Intel Xeon CPU E5405 @ 2.00GHz                  | 1         | 0.56%   |
| Intel Xeon CPU E5-2660 v2 @ 2.20GHz             | 1         | 0.56%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz             | 1         | 0.56%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz            | 1         | 0.56%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz     | 1         | 0.56%   |
| Intel Pentium CPU P6100 @ 2.00GHz               | 1         | 0.56%   |
| Intel Pentium CPU G3260 @ 3.30GHz               | 1         | 0.56%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1         | 0.56%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.56%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 39        | 21.91%  |
| Intel Core i7                  | 35        | 19.66%  |
| Intel Core i3                  | 20        | 11.24%  |
| Intel Celeron                  | 14        | 7.87%   |
| AMD Ryzen 5                    | 8         | 4.49%   |
| Intel Xeon                     | 6         | 3.37%   |
| AMD Ryzen 7                    | 6         | 3.37%   |
| Other                          | 5         | 2.81%   |
| Intel Pentium                  | 4         | 2.25%   |
| Intel Core 2 Duo               | 4         | 2.25%   |
| Intel Core 2                   | 4         | 2.25%   |
| AMD FX                         | 4         | 2.25%   |
| AMD E1                         | 4         | 2.25%   |
| Intel Atom                     | 3         | 1.69%   |
| AMD Ryzen 3                    | 3         | 1.69%   |
| Intel Genuine                  | 2         | 1.12%   |
| AMD A8                         | 2         | 1.12%   |
| AMD A10                        | 2         | 1.12%   |
| Intel Xeon Silver              | 1         | 0.56%   |
| Intel Pentium Dual-Core        | 1         | 0.56%   |
| Intel Pentium 4                | 1         | 0.56%   |
| Intel Core i9                  | 1         | 0.56%   |
| Intel Core 2 Quad              | 1         | 0.56%   |
| ARM BCM                        | 1         | 0.56%   |
| AMD V120                       | 1         | 0.56%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.56%   |
| AMD Turion 64 X2               | 1         | 0.56%   |
| AMD Sempron                    | 1         | 0.56%   |
| AMD Ryzen 7 PRO                | 1         | 0.56%   |
| AMD Phenom II X4               | 1         | 0.56%   |
| AMD E2                         | 1         | 0.56%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 88        | 49.44%  |
| 4      | 59        | 33.15%  |
| 6      | 14        | 7.87%   |
| 8      | 8         | 4.49%   |
| 1      | 5         | 2.81%   |
| 10     | 2         | 1.12%   |
| 20     | 1         | 0.56%   |
| 3      | 1         | 0.56%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 176       | 98.88%  |
| 2      | 2         | 1.12%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 105       | 58.99%  |
| 1      | 73        | 41.01%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 173       | 96.65%  |
| Unknown        | 4         | 2.23%   |
| 32-bit         | 2         | 1.12%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 29        | 15.93%  |
| 0x206a7    | 12        | 6.59%   |
| 0x306c3    | 11        | 6.04%   |
| 0x40651    | 7         | 3.85%   |
| 0x306a9    | 7         | 3.85%   |
| 0x806e9    | 6         | 3.3%    |
| 0x306d4    | 6         | 3.3%    |
| 0x08108109 | 6         | 3.3%    |
| 0x906ea    | 5         | 2.75%   |
| 0x906e9    | 5         | 2.75%   |
| 0x506e3    | 5         | 2.75%   |
| 0x406c4    | 5         | 2.75%   |
| 0x806ec    | 4         | 2.2%    |
| 0x706a1    | 4         | 2.2%    |
| 0x406e3    | 4         | 2.2%    |
| 0x08701021 | 4         | 2.2%    |
| 0x806eb    | 3         | 1.65%   |
| 0x806ea    | 3         | 1.65%   |
| 0x20655    | 3         | 1.65%   |
| 0x05000119 | 3         | 1.65%   |
| 0x906eb    | 2         | 1.1%    |
| 0x806c1    | 2         | 1.1%    |
| 0x706a8    | 2         | 1.1%    |
| 0x6fd      | 2         | 1.1%    |
| 0x6f6      | 2         | 1.1%    |
| 0x306e4    | 2         | 1.1%    |
| 0x30678    | 2         | 1.1%    |
| 0x1067a    | 2         | 1.1%    |
| 0x10676    | 2         | 1.1%    |
| 0x08600104 | 2         | 1.1%    |
| 0x07030105 | 2         | 1.1%    |
| 0x06000852 | 2         | 1.1%    |
| 0x010000c8 | 2         | 1.1%    |
| 0xf49      | 1         | 0.55%   |
| 0xf29      | 1         | 0.55%   |
| 0xa0652    | 1         | 0.55%   |
| 0x906ed    | 1         | 0.55%   |
| 0x906ec    | 1         | 0.55%   |
| 0x90672    | 1         | 0.55%   |
| 0x6ec      | 1         | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 34        | 19.1%   |
| Haswell         | 20        | 11.24%  |
| SandyBridge     | 16        | 8.99%   |
| Skylake         | 12        | 6.74%   |
| Zen 2           | 9         | 5.06%   |
| IvyBridge       | 9         | 5.06%   |
| Zen+            | 8         | 4.49%   |
| Silvermont      | 8         | 4.49%   |
| Penryn          | 6         | 3.37%   |
| Goldmont plus   | 6         | 3.37%   |
| Core            | 6         | 3.37%   |
| Broadwell       | 6         | 3.37%   |
| Westmere        | 4         | 2.25%   |
| TigerLake       | 3         | 1.69%   |
| Piledriver      | 3         | 1.69%   |
| K10             | 3         | 1.69%   |
| Excavator       | 3         | 1.69%   |
| Bobcat          | 3         | 1.69%   |
| Puma            | 2         | 1.12%   |
| NetBurst        | 2         | 1.12%   |
| Nehalem         | 2         | 1.12%   |
| IceLake         | 2         | 1.12%   |
| Unknown         | 2         | 1.12%   |
| Zen 3           | 1         | 0.56%   |
| P6              | 1         | 0.56%   |
| K8 Hammer       | 1         | 0.56%   |
| K8 & K10 hybrid | 1         | 0.56%   |
| K10 Llano       | 1         | 0.56%   |
| Jaguar          | 1         | 0.56%   |
| CometLake       | 1         | 0.56%   |
| Bulldozer       | 1         | 0.56%   |
| Bonnell         | 1         | 0.56%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 119       | 59.2%   |
| Nvidia | 43        | 21.39%  |
| AMD    | 39        | 19.4%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 6.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 3.79%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.32%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 2.84%   |
| Intel HD Graphics 620                                                                    | 6         | 2.84%   |
| Intel HD Graphics 5500                                                                   | 6         | 2.84%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.84%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.84%   |
| Intel UHD Graphics 620                                                                   | 5         | 2.37%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.9%    |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 1.9%    |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.9%    |
| Intel HD Graphics 630                                                                    | 4         | 1.9%    |
| Intel HD Graphics 530                                                                    | 4         | 1.9%    |
| AMD Renoir                                                                               | 4         | 1.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.9%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 3         | 1.42%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.42%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.42%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.42%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.42%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 1.42%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.95%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.95%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2         | 0.95%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.95%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.95%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.95%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.95%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.95%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.95%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.95%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 0.95%   |
| Nvidia TU117M                                                                            | 1         | 0.47%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 99        | 55.31%  |
| 1 x AMD        | 29        | 16.2%   |
| 1 x Nvidia     | 24        | 13.41%  |
| Intel + Nvidia | 16        | 8.94%   |
| 2 x AMD        | 5         | 2.79%   |
| AMD + Nvidia   | 3         | 1.68%   |
| Intel + AMD    | 2         | 1.12%   |
| Other          | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 156       | 86.19%  |
| Proprietary | 21        | 11.6%   |
| Unknown     | 4         | 2.21%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 113       | 61.41%  |
| 1.01-2.0   | 23        | 12.5%   |
| 0.01-0.5   | 17        | 9.24%   |
| 3.01-4.0   | 12        | 6.52%   |
| 0.51-1.0   | 11        | 5.98%   |
| 5.01-6.0   | 7         | 3.8%    |
| 7.01-8.0   | 1         | 0.54%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 28        | 13.27%  |
| AOC                     | 24        | 11.37%  |
| LG Display              | 20        | 9.48%   |
| Samsung Electronics     | 19        | 9%      |
| Chimei Innolux          | 17        | 8.06%   |
| BOE                     | 16        | 7.58%   |
| Hewlett-Packard         | 13        | 6.16%   |
| Dell                    | 12        | 5.69%   |
| Goldstar                | 10        | 4.74%   |
| Apple                   | 6         | 2.84%   |
| ViewSonic               | 5         | 2.37%   |
| Sony                    | 3         | 1.42%   |
| Chi Mei Optoelectronics | 3         | 1.42%   |
| BenQ                    | 3         | 1.42%   |
| AGO                     | 3         | 1.42%   |
| Acer                    | 3         | 1.42%   |
| Sharp                   | 2         | 0.95%   |
| Panasonic               | 2         | 0.95%   |
| Lenovo                  | 2         | 0.95%   |
| CPT                     | 2         | 0.95%   |
| ASUSTek Computer        | 2         | 0.95%   |
| Ancor Communications    | 2         | 0.95%   |
| Xerox                   | 1         | 0.47%   |
| Unknown (XXX)           | 1         | 0.47%   |
| Royal Information       | 1         | 0.47%   |
| Philips                 | 1         | 0.47%   |
| PAR                     | 1         | 0.47%   |
| MSI                     | 1         | 0.47%   |
| LTM                     | 1         | 0.47%   |
| LG Philips              | 1         | 0.47%   |
| KDC                     | 1         | 0.47%   |
| Hitachi                 | 1         | 0.47%   |
| Haier                   | 1         | 0.47%   |
| GAOMON                  | 1         | 0.47%   |
| Envision                | 1         | 0.47%   |
| CVT                     | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5         | 2.31%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 4         | 1.85%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3         | 1.39%   |
| Dell LCD Monitor DELA102 1920x1080 540x300mm 24.3-inch               | 3         | 1.39%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 1.39%   |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch       | 3         | 1.39%   |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 3         | 1.39%   |
| Sony TV SNY0902 1360x768                                             | 2         | 0.93%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2         | 0.93%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                   | 2         | 0.93%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 2         | 0.93%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.93%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2         | 0.93%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch          | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.93%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 2         | 0.93%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 2         | 0.93%   |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                   | 1         | 0.46%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch        | 1         | 0.46%   |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch        | 1         | 0.46%   |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch            | 1         | 0.46%   |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                           | 1         | 0.46%   |
| ViewSonic LCD Monitor VX2260WM                                       | 1         | 0.46%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1         | 0.46%   |
| Sony TV SNY1B02 1360x768 1600x900mm 72.3-inch                        | 1         | 0.46%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 1         | 0.46%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 1         | 0.46%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 700x390mm 31.5-inch    | 1         | 0.46%   |
| Samsung Electronics SyncMaster SAM058A 1920x1080 531x298mm 24.0-inch | 1         | 0.46%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 310x170mm 13.9-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch | 1         | 0.46%   |
| Samsung Electronics LCD Monitor SEC345A 1366x768 309x174mm 14.0-inch | 1         | 0.46%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 74        | 37.19%  |
| 1366x768 (WXGA)   | 55        | 27.64%  |
| 3840x2160 (4K)    | 14        | 7.04%   |
| 1600x900 (HD+)    | 12        | 6.03%   |
| 1440x900 (WXGA+)  | 10        | 5.03%   |
| 1280x800 (WXGA)   | 10        | 5.03%   |
| 1280x1024 (SXGA)  | 8         | 4.02%   |
| 2560x1440 (QHD)   | 3         | 1.51%   |
| 3286x1080         | 2         | 1.01%   |
| 2560x1080         | 2         | 1.01%   |
| 1360x768          | 2         | 1.01%   |
| 1280x720 (HD)     | 2         | 1.01%   |
| Unknown           | 2         | 1.01%   |
| 1920x1200 (WUXGA) | 1         | 0.5%    |
| 1400x1050         | 1         | 0.5%    |
| 1280x960          | 1         | 0.5%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 54        | 25.71%  |
| 14      | 25        | 11.9%   |
| 13      | 23        | 10.95%  |
| 23      | 15        | 7.14%   |
| 19      | 15        | 7.14%   |
| 24      | 12        | 5.71%   |
| 18      | 10        | 4.76%   |
| 17      | 10        | 4.76%   |
| 21      | 9         | 4.29%   |
| Unknown | 7         | 3.33%   |
| 27      | 5         | 2.38%   |
| 84      | 4         | 1.9%    |
| 12      | 4         | 1.9%    |
| 72      | 3         | 1.43%   |
| 32      | 3         | 1.43%   |
| 43      | 2         | 0.95%   |
| 40      | 2         | 0.95%   |
| 34      | 2         | 0.95%   |
| 31      | 2         | 0.95%   |
| 11      | 2         | 0.95%   |
| 54      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 97        | 46.19%  |
| 501-600     | 32        | 15.24%  |
| 401-500     | 31        | 14.76%  |
| 201-300     | 15        | 7.14%   |
| 351-400     | 9         | 4.29%   |
| 1501-2000   | 7         | 3.33%   |
| Unknown     | 7         | 3.33%   |
| 701-800     | 5         | 2.38%   |
| 801-900     | 2         | 0.95%   |
| 601-700     | 2         | 0.95%   |
| 901-1000    | 2         | 0.95%   |
| 1001-1500   | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 140       | 76.5%   |
| 16/10   | 22        | 12.02%  |
| 5/4     | 7         | 3.83%   |
| Unknown | 7         | 3.83%   |
| 4/3     | 5         | 2.73%   |
| 21/9    | 2         | 1.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 53        | 25.24%  |
| 81-90          | 44        | 20.95%  |
| 201-250        | 28        | 13.33%  |
| 151-200        | 20        | 9.52%   |
| 141-150        | 12        | 5.71%   |
| More than 1000 | 8         | 3.81%   |
| 351-500        | 7         | 3.33%   |
| Unknown        | 7         | 3.33%   |
| 71-80          | 6         | 2.86%   |
| 301-350        | 5         | 2.38%   |
| 251-300        | 5         | 2.38%   |
| 121-130        | 4         | 1.9%    |
| 501-1000       | 4         | 1.9%    |
| 51-60          | 2         | 0.95%   |
| 131-140        | 2         | 0.95%   |
| 61-70          | 1         | 0.48%   |
| 111-120        | 1         | 0.48%   |
| 91-100         | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 66        | 32.51%  |
| 51-100        | 65        | 32.02%  |
| 121-160       | 49        | 24.14%  |
| 1-50          | 7         | 3.45%   |
| 161-240       | 7         | 3.45%   |
| Unknown       | 7         | 3.45%   |
| More than 240 | 2         | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 146       | 77.66%  |
| 2     | 36        | 19.15%  |
| 0     | 4         | 2.13%   |
| 3     | 2         | 1.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 106       | 38.97%  |
| Intel                    | 67        | 24.63%  |
| Qualcomm Atheros         | 41        | 15.07%  |
| Broadcom                 | 19        | 6.99%   |
| Broadcom Limited         | 8         | 2.94%   |
| TP-Link                  | 6         | 2.21%   |
| Xiaomi                   | 3         | 1.1%    |
| Ralink                   | 3         | 1.1%    |
| Nvidia                   | 3         | 1.1%    |
| Linksys                  | 2         | 0.74%   |
| Huawei Technologies      | 2         | 0.74%   |
| ASIX Electronics         | 2         | 0.74%   |
| Standard Microsystems    | 1         | 0.37%   |
| Ralink Technology        | 1         | 0.37%   |
| MediaTek                 | 1         | 0.37%   |
| Marvell Technology Group | 1         | 0.37%   |
| Lenovo                   | 1         | 0.37%   |
| JMicron Technology       | 1         | 0.37%   |
| DisplayLink              | 1         | 0.37%   |
| Dell                     | 1         | 0.37%   |
| Davicom Semiconductor    | 1         | 0.37%   |
| D-Link                   | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65        | 19.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 6.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 2.13%   |
| Intel Wireless 7265                                               | 7         | 2.13%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.82%   |
| Intel Wireless 7260                                               | 6         | 1.82%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.82%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 5         | 1.52%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.52%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.22%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.22%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 1.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.91%   |
| TP-Link 802.11n NIC                                               | 3         | 0.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.91%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.91%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.91%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.91%   |
| Intel Wireless 8265 / 8275                                        | 3         | 0.91%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.91%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.91%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.61%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.61%   |
| Realtek 802.11ac NIC                                              | 2         | 0.61%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.61%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.61%   |
| Intel Wireless 8260                                               | 2         | 0.61%   |
| Intel Wireless 3160                                               | 2         | 0.61%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.61%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.61%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.61%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 51        | 34.69%  |
| Qualcomm Atheros      | 33        | 22.45%  |
| Realtek Semiconductor | 29        | 19.73%  |
| Broadcom              | 13        | 8.84%   |
| Broadcom Limited      | 7         | 4.76%   |
| TP-Link               | 6         | 4.08%   |
| Ralink                | 3         | 2.04%   |
| Linksys               | 2         | 1.36%   |
| Ralink Technology     | 1         | 0.68%   |
| Dell                  | 1         | 0.68%   |
| D-Link                | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 9         | 6.04%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 7         | 4.7%    |
| Intel Wireless 7265                                            | 7         | 4.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 4.03%   |
| Intel Wireless 7260                                            | 6         | 4.03%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 4.03%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 5         | 3.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 5         | 3.36%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 3.36%   |
| Broadcom BCM43142 802.11b/g/n                                  | 5         | 3.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 4         | 2.68%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 4         | 2.68%   |
| TP-Link 802.11n NIC                                            | 3         | 2.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.01%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 2.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 2.01%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 2.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 2.01%   |
| Intel Wireless 8265 / 8275                                     | 3         | 2.01%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 3         | 2.01%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 1.34%   |
| Realtek 802.11ac NIC                                           | 2         | 1.34%   |
| Intel Wireless 8260                                            | 2         | 1.34%   |
| Intel Wireless 3160                                            | 2         | 1.34%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 2         | 1.34%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 1.34%   |
| Broadcom Limited BCM4311 802.11a/b/g                           | 2         | 1.34%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 1         | 0.67%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                            | 1         | 0.67%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.67%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 1         | 0.67%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller      | 1         | 0.67%   |
| Realtek 802.11ac WLAN Adapter                                  | 1         | 0.67%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 0.67%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter         | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 96        | 55.49%  |
| Intel                    | 36        | 20.81%  |
| Broadcom                 | 12        | 6.94%   |
| Qualcomm Atheros         | 11        | 6.36%   |
| Xiaomi                   | 3         | 1.73%   |
| Nvidia                   | 3         | 1.73%   |
| Huawei Technologies      | 2         | 1.16%   |
| ASIX Electronics         | 2         | 1.16%   |
| Standard Microsystems    | 1         | 0.58%   |
| MediaTek                 | 1         | 0.58%   |
| Marvell Technology Group | 1         | 0.58%   |
| Lenovo                   | 1         | 0.58%   |
| JMicron Technology       | 1         | 0.58%   |
| DisplayLink              | 1         | 0.58%   |
| Davicom Semiconductor    | 1         | 0.58%   |
| Broadcom Limited         | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 65        | 36.11%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 12.78%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 3.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.22%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 2.22%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.67%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.67%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.67%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.67%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.67%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.11%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.11%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 1.11%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.11%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.11%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.11%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.11%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.11%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 1.11%   |
| Standard Microsystems Ethernet controller                         | 1         | 0.56%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.56%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.56%   |
| Nvidia MCP67 Ethernet                                             | 1         | 0.56%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.56%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 1         | 0.56%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 1         | 0.56%   |
| Lenovo Thinkpad LAN                                               | 1         | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.56%   |
| Intel PRO/100 VE Network Connection                               | 1         | 0.56%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.56%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.56%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.56%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.56%   |
| Intel Ethernet Connection I218-V                                  | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 159       | 53.36%  |
| WiFi     | 139       | 46.64%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 108       | 58.38%  |
| Ethernet | 77        | 41.62%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 116       | 64.44%  |
| 1     | 54        | 30%     |
| 3     | 5         | 2.78%   |
| 0     | 4         | 2.22%   |
| 4     | 1         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 177       | 98.88%  |
| Yes  | 2         | 1.12%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 41        | 39.81%  |
| Qualcomm Atheros Communications | 14        | 13.59%  |
| Realtek Semiconductor           | 13        | 12.62%  |
| Cambridge Silicon Radio         | 7         | 6.8%    |
| Broadcom                        | 7         | 6.8%    |
| Apple                           | 6         | 5.83%   |
| Toshiba                         | 3         | 2.91%   |
| Lite-On Technology              | 3         | 2.91%   |
| IMC Networks                    | 2         | 1.94%   |
| ASUSTek Computer                | 2         | 1.94%   |
| Realtek                         | 1         | 0.97%   |
| Marvell Semiconductor           | 1         | 0.97%   |
| Hewlett-Packard                 | 1         | 0.97%   |
| Foxconn / Hon Hai               | 1         | 0.97%   |
| Dell                            | 1         | 0.97%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                           | 18        | 17.48%  |
| Qualcomm Atheros  Bluetooth Device                           | 9         | 8.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 8         | 7.77%   |
| Realtek Bluetooth Radio                                      | 7         | 6.8%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 7         | 6.8%    |
| Realtek  Bluetooth 4.2 Adapter                               | 6         | 5.83%   |
| Intel AX200 Bluetooth                                        | 6         | 5.83%   |
| Apple Bluetooth Host Controller                              | 4         | 3.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                       | 3         | 2.91%   |
| Intel Centrino Bluetooth Wireless Transceiver                | 3         | 2.91%   |
| Intel AX201 Bluetooth                                        | 3         | 2.91%   |
| Broadcom BCM43142A0 Bluetooth 4.0                            | 3         | 2.91%   |
| Toshiba Bluetooth Device                                     | 2         | 1.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                   | 2         | 1.94%   |
| Intel Wireless-AC 3168 Bluetooth                             | 2         | 1.94%   |
| Toshiba BCM43142A0                                           | 1         | 0.97%   |
| Realtek Bluetooth Radio                                      | 1         | 0.97%   |
| Qualcomm Atheros Bluetooth USB Host Controller               | 1         | 0.97%   |
| Qualcomm Atheros AR3011 Bluetooth                            | 1         | 0.97%   |
| Marvell Bluetooth and Wireless LAN Composite Device          | 1         | 0.97%   |
| Lite-On Bluetooth Device                                     | 1         | 0.97%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 1         | 0.97%   |
| IMC Networks Bluetooth Radio                                 | 1         | 0.97%   |
| IMC Networks Bluetooth                                       | 1         | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                             | 1         | 0.97%   |
| Foxconn / Hon Hai Bluetooth Device                           | 1         | 0.97%   |
| Dell Broadcom BCM20702A0 Bluetooth                           | 1         | 0.97%   |
| Broadcom HP Portable SoftSailing                             | 1         | 0.97%   |
| Broadcom BCM43142 Bluetooth 4.0                              | 1         | 0.97%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                         | 1         | 0.97%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1         | 0.97%   |
| ASUS Qualcomm Bluetooth 4.1                                  | 1         | 0.97%   |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 1         | 0.97%   |
| Apple Bluetooth USB Host Controller                          | 1         | 0.97%   |
| Apple Bluetooth HCI                                          | 1         | 0.97%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 136       | 57.38%  |
| AMD                     | 45        | 18.99%  |
| Nvidia                  | 32        | 13.5%   |
| C-Media Electronics     | 4         | 1.69%   |
| Generalplus Technology  | 3         | 1.27%   |
| Logitech                | 2         | 0.84%   |
| JMTek                   | 2         | 0.84%   |
| GN Netcom               | 2         | 0.84%   |
| Soundprese              | 1         | 0.42%   |
| Realtek Semiconductor   | 1         | 0.42%   |
| Plantronics             | 1         | 0.42%   |
| Medeli Electronics      | 1         | 0.42%   |
| Lenovo                  | 1         | 0.42%   |
| Corsair                 | 1         | 0.42%   |
| CMX Systems             | 1         | 0.42%   |
| Blue Microphones        | 1         | 0.42%   |
| BEHRINGER International | 1         | 0.42%   |
| Argosy Research         | 1         | 0.42%   |
| Afatech                 | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 5.65%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 5.3%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 4.24%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 3.89%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 3.53%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 3.18%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.83%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.83%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 7         | 2.47%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 2.47%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.47%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 6         | 2.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.12%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.12%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.12%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 2.12%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.12%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.77%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.77%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.41%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.41%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.41%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.06%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.06%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.06%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.06%   |
| Generalplus Technology USB Audio Device                                                           | 3         | 1.06%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.06%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.06%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 1.06%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.71%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.71%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.71%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 24.58%  |
| SK hynix            | 20        | 16.95%  |
| Kingston            | 20        | 16.95%  |
| Micron Technology   | 15        | 12.71%  |
| Corsair             | 7         | 5.93%   |
| Crucial             | 6         | 5.08%   |
| A-DATA Technology   | 5         | 4.24%   |
| Unknown             | 4         | 3.39%   |
| Team                | 4         | 3.39%   |
| Nanya Technology    | 4         | 3.39%   |
| Patriot             | 2         | 1.69%   |
| Kimtigo             | 1         | 0.85%   |
| G.Skill             | 1         | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 5         | 3.68%   |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s      | 4         | 2.94%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 3         | 2.21%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 3         | 2.21%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 3         | 2.21%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM 1600MT/s          | 3         | 2.21%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s               | 3         | 2.21%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s               | 3         | 2.21%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 2         | 1.47%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 2         | 1.47%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 2         | 1.47%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 2         | 1.47%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.47%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.47%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4096MB SODIMM DDR3 1334MT/s   | 2         | 1.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 2         | 1.47%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s      | 2         | 1.47%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s               | 1         | 0.74%   |
| Unknown RAM Module 8GB SODIMM DDR3                        | 1         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3                        | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.74%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1867MT/s           | 1         | 0.74%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s               | 1         | 0.74%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1         | 0.74%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1         | 0.74%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s | 1         | 0.74%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s   | 1         | 0.74%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 0.74%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 0.74%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1         | 0.74%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 0.74%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 1         | 0.74%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 0.74%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s    | 1         | 0.74%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s    | 1         | 0.74%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 1         | 0.74%   |
| Samsung RAM M471B5674-H0-YK0--- 4GB Chip DDR3 1600MT/s    | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 47        | 47.47%  |
| DDR3   | 43        | 43.43%  |
| SDRAM  | 4         | 4.04%   |
| DDR2   | 4         | 4.04%   |
| LPDDR4 | 1         | 1.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 65        | 67.71%  |
| DIMM         | 27        | 28.13%  |
| Row Of Chips | 3         | 3.13%   |
| Chip         | 1         | 1.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 47        | 42.34%  |
| 8192  | 33        | 29.73%  |
| 16384 | 13        | 11.71%  |
| 2048  | 12        | 10.81%  |
| 32768 | 6         | 5.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 31        | 27.19%  |
| 2667    | 25        | 21.93%  |
| 1333    | 10        | 8.77%   |
| 3200    | 6         | 5.26%   |
| 2400    | 6         | 5.26%   |
| 1334    | 5         | 4.39%   |
| 667     | 5         | 4.39%   |
| 3266    | 3         | 2.63%   |
| 2133    | 3         | 2.63%   |
| 4199    | 2         | 1.75%   |
| 3600    | 2         | 1.75%   |
| 3400    | 2         | 1.75%   |
| Unknown | 2         | 1.75%   |
| 8400    | 1         | 0.88%   |
| 3866    | 1         | 0.88%   |
| 3466    | 1         | 0.88%   |
| 3100    | 1         | 0.88%   |
| 2934    | 1         | 0.88%   |
| 2933    | 1         | 0.88%   |
| 2800    | 1         | 0.88%   |
| 2666    | 1         | 0.88%   |
| 1867    | 1         | 0.88%   |
| 1866    | 1         | 0.88%   |
| 1800    | 1         | 0.88%   |
| 1067    | 1         | 0.88%   |

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
| Chicony Electronics                    | 25        | 20.16%  |
| Microdia                               | 15        | 12.1%   |
| Realtek Semiconductor                  | 11        | 8.87%   |
| IMC Networks                           | 11        | 8.87%   |
| Sunplus Innovation Technology          | 8         | 6.45%   |
| Logitech                               | 8         | 6.45%   |
| Apple                                  | 7         | 5.65%   |
| Microsoft                              | 5         | 4.03%   |
| Suyin                                  | 3         | 2.42%   |
| Quanta                                 | 3         | 2.42%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.42%   |
| Acer                                   | 3         | 2.42%   |
| Z-Star Microelectronics                | 2         | 1.61%   |
| Syntek                                 | 2         | 1.61%   |
| Primax Electronics                     | 2         | 1.61%   |
| Luxvisions Innotech Limited            | 2         | 1.61%   |
| Lite-On Technology                     | 2         | 1.61%   |
| Alcor Micro                            | 2         | 1.61%   |
| Silicon Motion                         | 1         | 0.81%   |
| Philips (or NXP)                       | 1         | 0.81%   |
| LG Electronics                         | 1         | 0.81%   |
| Importek                               | 1         | 0.81%   |
| Huawei Technologies                    | 1         | 0.81%   |
| GEMBIRD                                | 1         | 0.81%   |
| Creative Technology                    | 1         | 0.81%   |
| Aveo Technology                        | 1         | 0.81%   |
| Arkmicro Technologies                  | 1         | 0.81%   |
| Alpha Imaging Technology               | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD         | 9         | 7.09%   |
| Chicony Integrated Camera             | 5         | 3.94%   |
| IMC Networks Integrated Camera        | 4         | 3.15%   |
| Apple FaceTime HD Camera              | 4         | 3.15%   |
| Sunplus Integrated_Webcam_HD          | 3         | 2.36%   |
| Sunplus HD WebCam                     | 3         | 2.36%   |
| Realtek Integrated_Webcam_HD          | 3         | 2.36%   |
| Microsoft LifeCam HD-3000             | 3         | 2.36%   |
| Logitech Webcam C270                  | 3         | 2.36%   |
| Chicony TOSHIBA Web Camera - HD       | 3         | 2.36%   |
| Syntek EasyCamera                     | 2         | 1.57%   |
| Realtek Integrated Webcam HD          | 2         | 1.57%   |
| Realtek Integrated Webcam             | 2         | 1.57%   |
| Quanta HD WebCam                      | 2         | 1.57%   |
| Microdia USB 2.0 Camera               | 2         | 1.57%   |
| Microdia Integrated Webcam            | 2         | 1.57%   |
| IMC Networks USB2.0 VGA UVC WebCam    | 2         | 1.57%   |
| IMC Networks USB2.0 HD UVC WebCam     | 2         | 1.57%   |
| Chicony USB 2.0 Camera                | 2         | 1.57%   |
| Chicony Integrated HP HD Webcam       | 2         | 1.57%   |
| Chicony HP Truevision HD              | 2         | 1.57%   |
| Chicony 720p HD Camera                | 2         | 1.57%   |
| Z-Star Vega USB2.0 Camera             | 1         | 0.79%   |
| Z-Star USB2.0 Camera                  | 1         | 0.79%   |
| Suyin TOSHIBA Web Camera - HD         | 1         | 0.79%   |
| Suyin HP TrueVision HD                | 1         | 0.79%   |
| Suyin 1.3M HD WebCam                  | 1         | 0.79%   |
| Sunplus Laptop_Integrated_Webcam_HD   | 1         | 0.79%   |
| Sunplus HP HD Webcam [Fixed]          | 1         | 0.79%   |
| Silicon Motion Silicon Motion Camera  | 1         | 0.79%   |
| Realtek USB Camera                    | 1         | 0.79%   |
| Realtek Rear Camera                   | 1         | 0.79%   |
| Realtek HP Wide Vision FHD Camera     | 1         | 0.79%   |
| Realtek HP Truevision HD              | 1         | 0.79%   |
| Realtek Front Camera                  | 1         | 0.79%   |
| Quanta HP Webcam                      | 1         | 0.79%   |
| Primax webcam                         | 1         | 0.79%   |
| Primax HP HD Webcam [Fixed]           | 1         | 0.79%   |
| Philips (or NXP) SPC 1300NC PC Camera | 1         | 0.79%   |
| Microsoft Rear LifeCam                | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 11        | 50%     |
| Synaptics                  | 4         | 18.18%  |
| Shenzhen Goodix Technology | 2         | 9.09%   |
| STMicroelectronics         | 1         | 4.55%   |
| Samsung Electronics        | 1         | 4.55%   |
| LighTuning Technology      | 1         | 4.55%   |
| Elan Microelectronics      | 1         | 4.55%   |
| AuthenTec                  | 1         | 4.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader        | 3         | 13.64%  |
| Validity Sensors VFS 5011 fingerprint sensor      | 2         | 9.09%   |
| Validity Sensors Synaptics WBDI                   | 2         | 9.09%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 2         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device               | 2         | 9.09%   |
| Unknown                                           | 2         | 9.09%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 4.55%   |
| Validity Sensors VFS491                           | 1         | 4.55%   |
| Validity Sensors VFS471 Fingerprint Reader        | 1         | 4.55%   |
| Validity Sensors Fingerprint scanner              | 1         | 4.55%   |
| STMicroelectronics Fingerprint Reader             | 1         | 4.55%   |
| Samsung Fingerprint Device                        | 1         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor       | 1         | 4.55%   |
| Elan ELAN:ARM-M4                                  | 1         | 4.55%   |
| AuthenTec AES1600                                 | 1         | 4.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Broadcom                   | 4         | 30.77%  |
| Athena Smartcard Solutions | 4         | 30.77%  |
| O2 Micro                   | 3         | 23.08%  |
| OmniKey                    | 1         | 7.69%   |
| Alcor Micro                | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Athena Smartcard Solutions ASEDrive CCID                                     | 4         | 30.77%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 15.38%  |
| Broadcom 5880                                                                | 2         | 15.38%  |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 7.69%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.69%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 127       | 68.28%  |
| 1     | 48        | 25.81%  |
| 2     | 7         | 3.76%   |
| 3     | 4         | 2.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 29.58%  |
| Net/wireless             | 15        | 21.13%  |
| Graphics card            | 13        | 18.31%  |
| Chipcard                 | 10        | 14.08%  |
| Communication controller | 3         | 4.23%   |
| Sound                    | 2         | 2.82%   |
| Multimedia controller    | 2         | 2.82%   |
| Unassigned class         | 1         | 1.41%   |
| Network                  | 1         | 1.41%   |
| Net/ethernet             | 1         | 1.41%   |
| Firewire controller      | 1         | 1.41%   |
| Bluetooth                | 1         | 1.41%   |

