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

Total: 284

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 22        | 11.11%  |
| Ubuntu 18.04                 | 17        | 8.59%   |
| OpenMandriva 4.2             | 16        | 8.08%   |
| Ubuntu 22.04                 | 8         | 4.04%   |
| OpenMandriva 4.3             | 7         | 3.54%   |
| Ubuntu 19.04                 | 4         | 2.02%   |
| Lubuntu 22.04                | 4         | 2.02%   |
| Lubuntu 21.10                | 4         | 2.02%   |
| Linux Mint 20.2              | 4         | 2.02%   |
| Linux Mint 19.3              | 4         | 2.02%   |
| Fedora 36                    | 4         | 2.02%   |
| Zorin 16                     | 3         | 1.52%   |
| Lubuntu 21.04                | 3         | 1.52%   |
| Debian 11                    | 3         | 1.52%   |
| Debian 10                    | 3         | 1.52%   |
| Zorin 15                     | 2         | 1.01%   |
| Xubuntu 20.04                | 2         | 1.01%   |
| UbuntuDDE 20.04              | 2         | 1.01%   |
| Ubuntu Studio 20.04          | 2         | 1.01%   |
| Ubuntu 21.04                 | 2         | 1.01%   |
| Pop!_OS 21.04                | 2         | 1.01%   |
| Pop!_OS 20.10                | 2         | 1.01%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 1.01%   |
| Manjaro 20.2.1               | 2         | 1.01%   |
| Lubuntu 20.04                | 2         | 1.01%   |
| Linux Mint 20.3              | 2         | 1.01%   |
| Linux Mint 20.1              | 2         | 1.01%   |
| Linux Mint 20                | 2         | 1.01%   |
| KDE neon 20.04               | 2         | 1.01%   |
| Fedora 35                    | 2         | 1.01%   |
| Fedora 34                    | 2         | 1.01%   |
| Fedora 32                    | 2         | 1.01%   |
| EndeavourOS Rolling          | 2         | 1.01%   |
| Debian Testing               | 2         | 1.01%   |
| Arch                         | 2         | 1.01%   |
| Zorin 12                     | 1         | 0.51%   |
| Xubuntu 18.04                | 1         | 0.51%   |
| Ubuntu Unity 18.04           | 1         | 0.51%   |
| Ubuntu Unity 16.04           | 1         | 0.51%   |
| Ubuntu MATE 18.04            | 1         | 0.51%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 55        | 29.57%  |
| OpenMandriva  | 24        | 12.9%   |
| Linux Mint    | 15        | 8.06%   |
| Fedora        | 12        | 6.45%   |
| Manjaro       | 9         | 4.84%   |
| Lubuntu       | 8         | 4.3%    |
| Debian        | 8         | 4.3%    |
| Zorin         | 6         | 3.23%   |
| Pop!_OS       | 6         | 3.23%   |
| ROSA          | 4         | 2.15%   |
| Xubuntu       | 3         | 1.61%   |
| KDE neon      | 3         | 1.61%   |
| Elementary    | 3         | 1.61%   |
| Arch          | 3         | 1.61%   |
| UbuntuDDE     | 2         | 1.08%   |
| Ubuntu Unity  | 2         | 1.08%   |
| Ubuntu Studio | 2         | 1.08%   |
| openSUSE      | 2         | 1.08%   |
| Kubuntu       | 2         | 1.08%   |
| Kali          | 2         | 1.08%   |
| Endless       | 2         | 1.08%   |
| EndeavourOS   | 2         | 1.08%   |
| Ubuntu MATE   | 1         | 0.54%   |
| Reborn OS     | 1         | 0.54%   |
| Raspbian      | 1         | 0.54%   |
| PureOS        | 1         | 0.54%   |
| Peppermint    | 1         | 0.54%   |
| Parrot        | 1         | 0.54%   |
| LMDE          | 1         | 0.54%   |
| Clear Linux   | 1         | 0.54%   |
| BlackPanther  | 1         | 0.54%   |
| ArcoLinux     | 1         | 0.54%   |
| ALT Linux     | 1         | 0.54%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 16        | 7.41%   |
| 5.16.7-desktop-1omv4003  | 7         | 3.24%   |
| 5.4.0-42-generic         | 5         | 2.31%   |
| 5.4.0-70-generic         | 4         | 1.85%   |
| 5.13.0-16-generic        | 4         | 1.85%   |
| 5.11.0-27-generic        | 4         | 1.85%   |
| 5.0.0-23-generic         | 4         | 1.85%   |
| 5.8.0-50-generic         | 3         | 1.39%   |
| 5.4.0-77-generic         | 3         | 1.39%   |
| 5.0.0-25-generic         | 3         | 1.39%   |
| 5.9.16-1-MANJARO         | 2         | 0.93%   |
| 5.8.0-7630-generic       | 2         | 0.93%   |
| 5.4.0-52-generic         | 2         | 0.93%   |
| 5.4.0-29-generic         | 2         | 0.93%   |
| 5.4.0-26-generic         | 2         | 0.93%   |
| 5.4.0-21-generic         | 2         | 0.93%   |
| 5.3.0-40-generic         | 2         | 0.93%   |
| 5.3.0-28-generic         | 2         | 0.93%   |
| 5.18.13-200.fc36.x86_64  | 2         | 0.93%   |
| 5.15.0-41-generic        | 2         | 0.93%   |
| 5.15.0-27-generic        | 2         | 0.93%   |
| 5.15.0-25-generic        | 2         | 0.93%   |
| 5.13.0-35-generic        | 2         | 0.93%   |
| 5.13.0-20-generic        | 2         | 0.93%   |
| 5.11.0-16-generic        | 2         | 0.93%   |
| 4.19.0-8-amd64           | 2         | 0.93%   |
| 4.15.0-112-generic       | 2         | 0.93%   |
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
| 5.6.14-desktop-2bP       | 1         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 36        | 17.82%  |
| 5.10.14 | 16        | 7.92%   |
| 5.11.0  | 15        | 7.43%   |
| 5.15.0  | 14        | 6.93%   |
| 4.15.0  | 12        | 5.94%   |
| 5.3.0   | 10        | 4.95%   |
| 5.13.0  | 10        | 4.95%   |
| 5.8.0   | 9         | 4.46%   |
| 5.0.0   | 9         | 4.46%   |
| 5.16.7  | 7         | 3.47%   |
| 5.10.0  | 7         | 3.47%   |
| 5.18.13 | 3         | 1.49%   |
| 4.19.0  | 3         | 1.49%   |
| 5.9.16  | 2         | 0.99%   |
| 5.7.0   | 2         | 0.99%   |
| 4.18.0  | 2         | 0.99%   |
| 5.9.9   | 1         | 0.5%    |
| 5.9.14  | 1         | 0.5%    |
| 5.9.11  | 1         | 0.5%    |
| 5.8.6   | 1         | 0.5%    |
| 5.6.19  | 1         | 0.5%    |
| 5.6.16  | 1         | 0.5%    |
| 5.6.14  | 1         | 0.5%    |
| 5.6.13  | 1         | 0.5%    |
| 5.4.40  | 1         | 0.5%    |
| 5.2.11  | 1         | 0.5%    |
| 5.19.6  | 1         | 0.5%    |
| 5.19.4  | 1         | 0.5%    |
| 5.19.11 | 1         | 0.5%    |
| 5.18.16 | 1         | 0.5%    |
| 5.18.12 | 1         | 0.5%    |
| 5.18.0  | 1         | 0.5%    |
| 5.17.9  | 1         | 0.5%    |
| 5.15.32 | 1         | 0.5%    |
| 5.15.23 | 1         | 0.5%    |
| 5.15.13 | 1         | 0.5%    |
| 5.15.11 | 1         | 0.5%    |
| 5.14.14 | 1         | 0.5%    |
| 5.14.0  | 1         | 0.5%    |
| 5.13.9  | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 37        | 18.41%  |
| 5.10    | 30        | 14.93%  |
| 5.11    | 19        | 9.45%   |
| 5.15    | 18        | 8.96%   |
| 4.15    | 12        | 5.97%   |
| 5.13    | 11        | 5.47%   |
| 5.8     | 10        | 4.98%   |
| 5.3     | 10        | 4.98%   |
| 5.0     | 10        | 4.98%   |
| 5.16    | 7         | 3.48%   |
| 5.18    | 6         | 2.99%   |
| 5.9     | 5         | 2.49%   |
| 5.6     | 4         | 1.99%   |
| 4.19    | 4         | 1.99%   |
| 5.19    | 3         | 1.49%   |
| 5.12    | 3         | 1.49%   |
| 4.18    | 3         | 1.49%   |
| 5.7     | 2         | 1%      |
| 5.14    | 2         | 1%      |
| 4.1     | 2         | 1%      |
| 5.2     | 1         | 0.5%    |
| 5.17    | 1         | 0.5%    |
| 4.9     | 1         | 0.5%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 170       | 96.59%  |
| i686   | 5         | 2.84%   |
| armv7l | 1         | 0.57%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 75        | 41.67%  |
| KDE5          | 32        | 17.78%  |
| Unknown       | 19        | 10.56%  |
| XFCE          | 13        | 7.22%   |
| X-Cinnamon    | 8         | 4.44%   |
| LXQt          | 7         | 3.89%   |
| MATE          | 6         | 3.33%   |
| KDE           | 4         | 2.22%   |
| Pantheon      | 3         | 1.67%   |
| LXDE          | 3         | 1.67%   |
| Unity         | 2         | 1.11%   |
| i3            | 2         | 1.11%   |
| Deepin        | 2         | 1.11%   |
| Cinnamon      | 2         | 1.11%   |
| Openbox       | 1         | 0.56%   |
| GNOME Classic | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 139       | 78.53%  |
| Wayland | 27        | 15.25%  |
| Unknown | 8         | 4.52%   |
| Tty     | 3         | 1.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 82        | 45.3%   |
| SDDM    | 42        | 23.2%   |
| GDM     | 18        | 9.94%   |
| LightDM | 16        | 8.84%   |
| GDM3    | 12        | 6.63%   |
| TDM     | 11        | 6.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 74        | 40.66%  |
| es_CR   | 71        | 39.01%  |
| Unknown | 19        | 10.44%  |
| es_ES   | 10        | 5.49%   |
| C       | 3         | 1.65%   |
| en_GB   | 2         | 1.1%    |
| fr_FR   | 1         | 0.55%   |
| es_MX   | 1         | 0.55%   |
| de_DE   | 1         | 0.55%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 95        | 53.07%  |
| BIOS | 84        | 46.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 135       | 74.59%  |
| Overlay | 25        | 13.81%  |
| Btrfs   | 14        | 7.73%   |
| Unknown | 5         | 2.76%   |
| Xfs     | 2         | 1.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 93        | 51.96%  |
| GPT     | 65        | 36.31%  |
| MBR     | 21        | 11.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 158       | 87.78%  |
| Yes       | 22        | 12.22%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 60.89%  |
| Yes       | 70        | 39.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Dell                    | 39        | 22.16%  |
| Hewlett-Packard         | 29        | 16.48%  |
| ASUSTek Computer        | 19        | 10.8%   |
| Lenovo                  | 17        | 9.66%   |
| Toshiba                 | 11        | 6.25%   |
| Gigabyte Technology     | 9         | 5.11%   |
| Acer                    | 9         | 5.11%   |
| MSI                     | 6         | 3.41%   |
| ASRock                  | 6         | 3.41%   |
| Apple                   | 6         | 3.41%   |
| Unknown                 | 3         | 1.7%    |
| Intel                   | 2         | 1.14%   |
| ZOTAC                   | 1         | 0.57%   |
| TPV-INVENTA             | 1         | 0.57%   |
| System76                | 1         | 0.57%   |
| Supermicro              | 1         | 0.57%   |
| Sony                    | 1         | 0.57%   |
| Samsung Electronics     | 1         | 0.57%   |
| Raspberry Pi Foundation | 1         | 0.57%   |
| Purism                  | 1         | 0.57%   |
| Pegatron                | 1         | 0.57%   |
| Olivetti                | 1         | 0.57%   |
| Microsoft               | 1         | 0.57%   |
| MACHINIST               | 1         | 0.57%   |
| HUAWEI                  | 1         | 0.57%   |
| Google                  | 1         | 0.57%   |
| Gateway                 | 1         | 0.57%   |
| Deffad                  | 1         | 0.57%   |
| Biostar                 | 1         | 0.57%   |
| AZW                     | 1         | 0.57%   |
| Alienware               | 1         | 0.57%   |
| ABIT                    | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Dell OptiPlex 3020                       | 5         | 2.84%   |
| Unknown                                  | 5         | 2.84%   |
| Apple MacBookPro8,1                      | 4         | 2.27%   |
| Dell Inspiron 5584                       | 3         | 1.7%    |
| HP ProBook 6460b                         | 2         | 1.14%   |
| HP Pavilion Notebook                     | 2         | 1.14%   |
| HP Notebook                              | 2         | 1.14%   |
| HP Laptop 15-da0xxx                      | 2         | 1.14%   |
| Gigabyte B250M-DS3H                      | 2         | 1.14%   |
| Dell OptiPlex 7040                       | 2         | 1.14%   |
| ASUS PRIME A320M-K                       | 2         | 1.14%   |
| ASRock B450 Steel Legend                 | 2         | 1.14%   |
| ZOTAC NM10                               | 1         | 0.57%   |
| TPV-INVENTA 18-2003LA                    | 1         | 0.57%   |
| Toshiba Satellite X205                   | 1         | 0.57%   |
| Toshiba Satellite L655                   | 1         | 0.57%   |
| Toshiba Satellite L45-B                  | 1         | 0.57%   |
| Toshiba Satellite C855D                  | 1         | 0.57%   |
| Toshiba Satellite C845                   | 1         | 0.57%   |
| Toshiba Satellite C645D                  | 1         | 0.57%   |
| Toshiba Satellite C55-C                  | 1         | 0.57%   |
| Toshiba Satellite C55-B                  | 1         | 0.57%   |
| Toshiba Satellite C45-A                  | 1         | 0.57%   |
| Toshiba Satellite A305D                  | 1         | 0.57%   |
| Toshiba QOSMIO X775                      | 1         | 0.57%   |
| System76 Lemur                           | 1         | 0.57%   |
| Supermicro X9DAi                         | 1         | 0.57%   |
| Sony SVD13215PLB                         | 1         | 0.57%   |
| Samsung 930QAA                           | 1         | 0.57%   |
| RPi Raspberry Pi 3 Model B Plus Rev 1.3  | 1         | 0.57%   |
| Purism Librem 15 v3                      | 1         | 0.57%   |
| Pegatron CQ2728LA                        | 1         | 0.57%   |
| Olivetti CL133A                          | 1         | 0.57%   |
| MSI Z390 Gaming Trident X Plus (MS-B926) | 1         | 0.57%   |
| MSI MS-7B86                              | 1         | 0.57%   |
| MSI MS-7693                              | 1         | 0.57%   |
| MSI MS-7636                              | 1         | 0.57%   |
| MSI GF75 Thin 9SD                        | 1         | 0.57%   |
| MSI GE60 2OC\2OD\2OE                     | 1         | 0.57%   |
| Microsoft Surface with Windows 8 Pro     | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 11        | 6.25%   |
| Toshiba Satellite     | 10        | 5.68%   |
| Lenovo ThinkPad       | 10        | 5.68%   |
| Dell Latitude         | 10        | 5.68%   |
| Dell OptiPlex         | 9         | 5.11%   |
| HP Pavilion           | 7         | 3.98%   |
| Acer Aspire           | 7         | 3.98%   |
| HP Laptop             | 5         | 2.84%   |
| Unknown               | 5         | 2.84%   |
| Lenovo IdeaPad        | 4         | 2.27%   |
| HP ProBook            | 4         | 2.27%   |
| Dell Precision        | 4         | 2.27%   |
| ASUS PRIME            | 4         | 2.27%   |
| Apple MacBookPro8     | 4         | 2.27%   |
| HP EliteBook          | 3         | 1.7%    |
| ASUS VivoBook         | 3         | 1.7%    |
| Lenovo IdeaPadFlex    | 2         | 1.14%   |
| HP Notebook           | 2         | 1.14%   |
| Gigabyte B250M-DS3H   | 2         | 1.14%   |
| Dell XPS              | 2         | 1.14%   |
| Dell G3               | 2         | 1.14%   |
| ASUS TUF              | 2         | 1.14%   |
| ASUS Strix            | 2         | 1.14%   |
| ASRock B450           | 2         | 1.14%   |
| ZOTAC NM10            | 1         | 0.57%   |
| TPV-INVENTA 18-2003LA | 1         | 0.57%   |
| Toshiba QOSMIO        | 1         | 0.57%   |
| System76 Lemur        | 1         | 0.57%   |
| Supermicro X9DAi      | 1         | 0.57%   |
| Sony SVD13215PLB      | 1         | 0.57%   |
| Samsung 930QAA        | 1         | 0.57%   |
| RPi Raspberry         | 1         | 0.57%   |
| Purism Librem         | 1         | 0.57%   |
| Pegatron CQ2728LA     | 1         | 0.57%   |
| Olivetti CL133A       | 1         | 0.57%   |
| MSI Z390              | 1         | 0.57%   |
| MSI MS-7B86           | 1         | 0.57%   |
| MSI MS-7693           | 1         | 0.57%   |
| MSI MS-7636           | 1         | 0.57%   |
| MSI GF75              | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 24        | 13.64%  |
| 2014    | 18        | 10.23%  |
| 2018    | 17        | 9.66%   |
| 2017    | 14        | 7.95%   |
| 2011    | 14        | 7.95%   |
| 2016    | 13        | 7.39%   |
| 2013    | 13        | 7.39%   |
| 2020    | 11        | 6.25%   |
| 2012    | 11        | 6.25%   |
| 2015    | 10        | 5.68%   |
| 2008    | 7         | 3.98%   |
| 2010    | 6         | 3.41%   |
| 2021    | 4         | 2.27%   |
| 2007    | 4         | 2.27%   |
| 2009    | 3         | 1.7%    |
| 2022    | 2         | 1.14%   |
| 2006    | 2         | 1.14%   |
| 2005    | 2         | 1.14%   |
| Unknown | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 108       | 61.36%  |
| Desktop        | 58        | 32.95%  |
| Convertible    | 4         | 2.27%   |
| All in one     | 3         | 1.7%    |
| System on chip | 1         | 0.57%   |
| Tablet         | 1         | 0.57%   |
| Server         | 1         | 0.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 161       | 91.48%  |
| Enabled  | 15        | 8.52%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 174       | 98.86%  |
| Yes  | 2         | 1.14%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 39        | 21.91%  |
| 3.01-4.0        | 39        | 21.91%  |
| 8.01-16.0       | 38        | 21.35%  |
| 16.01-24.0      | 33        | 18.54%  |
| 32.01-64.0      | 11        | 6.18%   |
| 1.01-2.0        | 8         | 4.49%   |
| 2.01-3.0        | 4         | 2.25%   |
| 64.01-256.0     | 3         | 1.69%   |
| More than 256.0 | 1         | 0.56%   |
| 24.01-32.0      | 1         | 0.56%   |
| 0.51-1.0        | 1         | 0.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 83        | 43.23%  |
| 2.01-3.0   | 45        | 23.44%  |
| 4.01-8.0   | 24        | 12.5%   |
| 3.01-4.0   | 20        | 10.42%  |
| 0.51-1.0   | 10        | 5.21%   |
| 8.01-16.0  | 4         | 2.08%   |
| 0.01-0.5   | 4         | 2.08%   |
| 24.01-32.0 | 1         | 0.52%   |
| 16.01-24.0 | 1         | 0.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 123       | 67.96%  |
| 2      | 40        | 22.1%   |
| 3      | 9         | 4.97%   |
| 4      | 6         | 3.31%   |
| 8      | 1         | 0.55%   |
| 7      | 1         | 0.55%   |
| 5      | 1         | 0.55%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 97        | 54.19%  |
| Yes       | 82        | 45.81%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 158       | 89.77%  |
| No        | 18        | 10.23%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 137       | 76.97%  |
| No        | 41        | 23.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 100       | 55.87%  |
| No        | 79        | 44.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Costa Rica | 176       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| San José     | 72        | 37.89%  |
| Heredia       | 41        | 21.58%  |
| Alajuela      | 16        | 8.42%   |
| Escazu        | 6         | 3.16%   |
| Cartago       | 6         | 3.16%   |
| Quesada       | 4         | 2.11%   |
| San Ramon     | 3         | 1.58%   |
| Liberia       | 3         | 1.58%   |
| Grecia        | 3         | 1.58%   |
| Tres Rios     | 2         | 1.05%   |
| Siquirres     | 2         | 1.05%   |
| Santa Fe      | 2         | 1.05%   |
| Santa Cruz    | 2         | 1.05%   |
| San Pedro     | 2         | 1.05%   |
| Palmares      | 2         | 1.05%   |
| Nosara        | 2         | 1.05%   |
| Naranjo       | 2         | 1.05%   |
| Esparza       | 2         | 1.05%   |
| Curridabat    | 2         | 1.05%   |
| Zarcero       | 1         | 0.53%   |
| Tibas         | 1         | 0.53%   |
| Santo Domingo | 1         | 0.53%   |
| Santiago      | 1         | 0.53%   |
| Santa Ana     | 1         | 0.53%   |
| San Pablo     | 1         | 0.53%   |
| San Juan      | 1         | 0.53%   |
| San Francisco | 1         | 0.53%   |
| Quepos        | 1         | 0.53%   |
| Puntarenas    | 1         | 0.53%   |
| Guacima       | 1         | 0.53%   |
| Colon         | 1         | 0.53%   |
| Bajo Perez    | 1         | 0.53%   |
| Bagaces       | 1         | 0.53%   |
| Alpes         | 1         | 0.53%   |
| Alajuelita    | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 37        | 48     | 15.42%  |
| Seagate               | 37        | 64     | 15.42%  |
| Toshiba               | 26        | 31     | 10.83%  |
| Samsung Electronics   | 19        | 32     | 7.92%   |
| A-DATA Technology     | 17        | 17     | 7.08%   |
| Kingston              | 15        | 24     | 6.25%   |
| Intel                 | 12        | 17     | 5%      |
| HGST                  | 10        | 11     | 4.17%   |
| Unknown               | 8         | 13     | 3.33%   |
| SanDisk               | 7         | 8      | 2.92%   |
| Hitachi               | 6         | 9      | 2.5%    |
| SK hynix              | 5         | 10     | 2.08%   |
| Crucial               | 5         | 5      | 2.08%   |
| XPG                   | 4         | 4      | 1.67%   |
| Patriot               | 4         | 4      | 1.67%   |
| Micron Technology     | 3         | 3      | 1.25%   |
| ZOTAC                 | 2         | 3      | 0.83%   |
| Team                  | 2         | 2      | 0.83%   |
| Realtek Semiconductor | 2         | 3      | 0.83%   |
| Maxtor                | 2         | 2      | 0.83%   |
| LITEONIT              | 2         | 2      | 0.83%   |
| JMicron Technology    | 2         | 2      | 0.83%   |
| Zheino                | 1         | 1      | 0.42%   |
| WD MediaMax           | 1         | 1      | 0.42%   |
| UMIS                  | 1         | 1      | 0.42%   |
| Transcend             | 1         | 1      | 0.42%   |
| Silicon Motion        | 1         | 1      | 0.42%   |
| Netac                 | 1         | 1      | 0.42%   |
| Fujitsu               | 1         | 1      | 0.42%   |
| FORESEE               | 1         | 1      | 0.42%   |
| Dell                  | 1         | 1      | 0.42%   |
| CT120BX5              | 1         | 1      | 0.42%   |
| Apple                 | 1         | 2      | 0.42%   |
| ADATA Technology      | 1         | 1      | 0.42%   |
| Unknown               | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 7         | 2.69%   |
| A-DATA SU630 480GB SSD             | 6         | 2.31%   |
| Toshiba MQ01ABF050 500GB           | 5         | 1.92%   |
| Toshiba MQ01ABD100 1TB             | 5         | 1.92%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 3         | 1.15%   |
| WDC WD10EZEX-75WN4A1 1TB           | 3         | 1.15%   |
| Toshiba KBG30ZMS256G NVMe 256GB    | 3         | 1.15%   |
| Toshiba DT01ACA100 1TB             | 3         | 1.15%   |
| Seagate ST1000DM003-1CH162 1TB     | 3         | 1.15%   |
| Kingston SV300S37A120G 120GB SSD   | 3         | 1.15%   |
| Intel SSDSC2BF180A4H 180GB         | 3         | 1.15%   |
| Intel SSDSA2CW300G3 304GB          | 3         | 1.15%   |
| HGST HTS541010A9E680 1TB           | 3         | 1.15%   |
| XPG GAMMIX S11 Pro 512GB           | 2         | 0.77%   |
| WDC WD5000LPCX-60VHAT0 500GB       | 2         | 0.77%   |
| WDC WD10EZEX-08WN4A0 1TB           | 2         | 0.77%   |
| Toshiba NVMe SSD Drive 256GB       | 2         | 0.77%   |
| SK hynix NVMe SSD Drive 128GB      | 2         | 0.77%   |
| Seagate ST8000DM004-2CX188 8TB     | 2         | 0.77%   |
| Seagate ST380815AS 80GB            | 2         | 0.77%   |
| Seagate ST2000LM007-1R8174 2TB     | 2         | 0.77%   |
| Seagate ST1000LM035-1RK172 1TB     | 2         | 0.77%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 0.77%   |
| Seagate ST1000DM010-2EP102 1TB     | 2         | 0.77%   |
| Samsung NVMe SSD Drive 256GB       | 2         | 0.77%   |
| Patriot P210 256GB SSD             | 2         | 0.77%   |
| JMicron Generic 120GB              | 2         | 0.77%   |
| Intel SSDSC2MH250A2 250GB          | 2         | 0.77%   |
| HGST HTS541075A9E680 752GB         | 2         | 0.77%   |
| A-DATA SU650 120GB SSD             | 2         | 0.77%   |
| ZOTAC ZTSSD-S11-240G-P 240GB       | 1         | 0.38%   |
| ZOTAC ZTSSD-S11-120G-MD 120GB      | 1         | 0.38%   |
| Zheino CHN 25SATAA3 240 240GB      | 1         | 0.38%   |
| XPG NVMe SSD Drive 512GB           | 1         | 0.38%   |
| XPG NVMe SSD Drive 1TB             | 1         | 0.38%   |
| WDC WDS250G2B0B-00YS70 250GB SSD   | 1         | 0.38%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 1         | 0.38%   |
| WDC WDS120G1G0B-00RC30 120GB SSD   | 1         | 0.38%   |
| WDC WD800BEVT-75ZCT2 80GB          | 1         | 0.38%   |
| WDC WD7500BPVT-22HXZT3 752GB       | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 35        | 62     | 33.02%  |
| WDC     | 30        | 34     | 28.3%   |
| Toshiba | 21        | 22     | 19.81%  |
| HGST    | 10        | 11     | 9.43%   |
| Hitachi | 6         | 9      | 5.66%   |
| Maxtor  | 2         | 2      | 1.89%   |
| Fujitsu | 1         | 1      | 0.94%   |
| Apple   | 1         | 1      | 0.94%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 14        | 19     | 17.5%   |
| A-DATA Technology   | 13        | 13     | 16.25%  |
| Samsung Electronics | 10        | 19     | 12.5%   |
| Intel               | 9         | 13     | 11.25%  |
| WDC                 | 6         | 11     | 7.5%    |
| SanDisk             | 6         | 7      | 7.5%    |
| Patriot             | 4         | 4      | 5%      |
| Crucial             | 4         | 4      | 5%      |
| Micron Technology   | 3         | 3      | 3.75%   |
| ZOTAC               | 2         | 3      | 2.5%    |
| Team                | 2         | 2      | 2.5%    |
| LITEONIT            | 2         | 2      | 2.5%    |
| Transcend           | 1         | 1      | 1.25%   |
| Seagate             | 1         | 1      | 1.25%   |
| Netac               | 1         | 1      | 1.25%   |
| FORESEE             | 1         | 1      | 1.25%   |
| CT120BX5            | 1         | 1      | 1.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 96        | 142    | 43.24%  |
| SSD     | 76        | 105    | 34.23%  |
| NVMe    | 38        | 63     | 17.12%  |
| MMC     | 9         | 14     | 4.05%   |
| Unknown | 3         | 4      | 1.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 155       | 240    | 74.52%  |
| NVMe | 36        | 61     | 17.31%  |
| MMC  | 9         | 14     | 4.33%   |
| SAS  | 8         | 13     | 3.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 107       | 139    | 59.78%  |
| 0.51-1.0   | 56        | 83     | 31.28%  |
| 1.01-2.0   | 10        | 16     | 5.59%   |
| 4.01-10.0  | 5         | 8      | 2.79%   |
| 3.01-4.0   | 1         | 1      | 0.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 48        | 25.4%   |
| 251-500        | 35        | 18.52%  |
| 501-1000       | 30        | 15.87%  |
| 1-20           | 20        | 10.58%  |
| 51-100         | 18        | 9.52%   |
| 1001-2000      | 13        | 6.88%   |
| More than 3000 | 10        | 5.29%   |
| 21-50          | 8         | 4.23%   |
| Unknown        | 4         | 2.12%   |
| 2001-3000      | 3         | 1.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 86        | 44.56%  |
| 21-50          | 32        | 16.58%  |
| 101-250        | 22        | 11.4%   |
| 51-100         | 18        | 9.33%   |
| 251-500        | 16        | 8.29%   |
| 501-1000       | 6         | 3.11%   |
| More than 3000 | 4         | 2.07%   |
| Unknown        | 4         | 2.07%   |
| 1001-2000      | 3         | 1.55%   |
| 2001-3000      | 2         | 1.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


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

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


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

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


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

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


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

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 102       | 187    | 53.4%   |
| Works    | 73        | 122    | 38.22%  |
| Malfunc  | 16        | 19     | 8.38%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 131       | 61.21%  |
| AMD                          | 33        | 15.42%  |
| Samsung Electronics          | 10        | 4.67%   |
| ADATA Technology             | 6         | 2.8%    |
| Realtek Semiconductor        | 5         | 2.34%   |
| ASMedia Technology           | 5         | 2.34%   |
| Toshiba America Info Systems | 4         | 1.87%   |
| SK hynix                     | 4         | 1.87%   |
| SanDisk                      | 3         | 1.4%    |
| Nvidia                       | 3         | 1.4%    |
| Union Memory (Shenzhen)      | 1         | 0.47%   |
| Silicon Motion               | 1         | 0.47%   |
| Silicon Image                | 1         | 0.47%   |
| OCZ Technology Group         | 1         | 0.47%   |
| Micron/Crucial Technology    | 1         | 0.47%   |
| Marvell Technology Group     | 1         | 0.47%   |
| LSI Logic / Symbios Logic    | 1         | 0.47%   |
| Kingston Technology Company  | 1         | 0.47%   |
| JMicron Technology           | 1         | 0.47%   |
| Apple                        | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Computers | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 22        | 9.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 13        | 5.39%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 11        | 4.56%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 11        | 4.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 10        | 4.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 8         | 3.32%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]          | 7         | 2.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 7         | 2.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 6         | 2.49%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 2.49%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 5         | 2.07%   |
| ASMedia ASM1062 Serial ATA Controller                                                  | 5         | 2.07%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                            | 5         | 2.07%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                          | 4         | 1.66%   |
| Intel SATA Controller [RAID mode]                                                      | 4         | 1.66%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 4         | 1.66%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 4         | 1.66%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                       | 4         | 1.66%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                   | 3         | 1.24%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                             | 3         | 1.24%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 3         | 1.24%   |
| Realtek RTS5763DL NVMe SSD Controller                                                  | 3         | 1.24%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 3         | 1.24%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.24%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 3         | 1.24%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 3         | 1.24%   |
| AMD 400 Series Chipset SATA Controller                                                 | 3         | 1.24%   |
| SK hynix BC501 NVMe Solid State Drive                                                  | 2         | 0.83%   |
| Realtek Realtek Non-Volatile memory controller                                         | 2         | 0.83%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                | 2         | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 2         | 0.83%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 2         | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                             | 2         | 0.83%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                              | 2         | 0.83%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 2         | 0.83%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 2         | 0.83%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 0.83%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 2         | 0.83%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 2         | 0.83%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller          | 2         | 0.83%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 136       | 62.1%   |
| NVMe | 37        | 16.89%  |
| IDE  | 26        | 11.87%  |
| RAID | 18        | 8.22%   |
| SAS  | 1         | 0.46%   |
| SCSI | 1         | 0.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 138       | 78.41%  |
| AMD    | 37        | 21.02%  |
| ARM    | 1         | 0.57%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i5-4590 CPU @ 3.30GHz                | 5         | 2.84%   |
| Intel Core i5-2520M CPU @ 2.50GHz               | 4         | 2.27%   |
| AMD Ryzen 5 3600 6-Core Processor               | 4         | 2.27%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 3         | 1.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 3         | 1.7%    |
| Intel Core i7-2640M CPU @ 2.80GHz               | 3         | 1.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz               | 3         | 1.7%    |
| Intel Celeron CPU N3060 @ 1.60GHz               | 3         | 1.7%    |
| Intel Core i7-9750H CPU @ 2.60GHz               | 2         | 1.14%   |
| Intel Core i7-8665U CPU @ 1.90GHz               | 2         | 1.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 2         | 1.14%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 2         | 1.14%   |
| Intel Core i7-4800MQ CPU @ 2.70GHz              | 2         | 1.14%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 2         | 1.14%   |
| Intel Core i5-7400 CPU @ 3.00GHz                | 2         | 1.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 2         | 1.14%   |
| Intel Core i5-4200U CPU @ 1.60GHz               | 2         | 1.14%   |
| Intel Core i3-8130U CPU @ 2.20GHz               | 2         | 1.14%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 2         | 1.14%   |
| Intel Core i3-3220 CPU @ 3.30GHz                | 2         | 1.14%   |
| Intel Core i3 CPU M 380 @ 2.53GHz               | 2         | 1.14%   |
| Intel Celeron CPU N2840 @ 2.16GHz               | 2         | 1.14%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz               | 2         | 1.14%   |
| AMD Ryzen 7 4700U with Radeon Graphics          | 2         | 1.14%   |
| AMD E1-1200 APU with Radeon HD Graphics         | 2         | 1.14%   |
| AMD A10-9600P RADEON R5, 10 COMPUTE CORES 4C+6G | 2         | 1.14%   |
| Intel Xeon Silver 4114 CPU @ 2.20GHz            | 1         | 0.57%   |
| Intel Xeon CPU X5667 @ 3.07GHz                  | 1         | 0.57%   |
| Intel Xeon CPU W3565 @ 3.20GHz                  | 1         | 0.57%   |
| Intel Xeon CPU E5405 @ 2.00GHz                  | 1         | 0.57%   |
| Intel Xeon CPU E5-2660 v2 @ 2.20GHz             | 1         | 0.57%   |
| Intel Xeon CPU E5-2650 v2 @ 2.60GHz             | 1         | 0.57%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz            | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz     | 1         | 0.57%   |
| Intel Pentium CPU P6100 @ 2.00GHz               | 1         | 0.57%   |
| Intel Pentium CPU G3260 @ 3.30GHz               | 1         | 0.57%   |
| Intel Pentium CPU G2030 @ 3.00GHz               | 1         | 0.57%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 1         | 0.57%   |
| Intel Pentium 4 CPU 2.00GHz                     | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 39        | 22.16%  |
| Intel Core i7                  | 34        | 19.32%  |
| Intel Core i3                  | 20        | 11.36%  |
| Intel Celeron                  | 14        | 7.95%   |
| AMD Ryzen 5                    | 8         | 4.55%   |
| Intel Xeon                     | 6         | 3.41%   |
| AMD Ryzen 7                    | 6         | 3.41%   |
| Other                          | 5         | 2.84%   |
| Intel Pentium                  | 4         | 2.27%   |
| Intel Core 2 Duo               | 4         | 2.27%   |
| AMD FX                         | 4         | 2.27%   |
| AMD E1                         | 4         | 2.27%   |
| Intel Core 2                   | 3         | 1.7%    |
| Intel Atom                     | 3         | 1.7%    |
| AMD Ryzen 3                    | 3         | 1.7%    |
| Intel Genuine                  | 2         | 1.14%   |
| AMD A8                         | 2         | 1.14%   |
| AMD A10                        | 2         | 1.14%   |
| Intel Xeon Silver              | 1         | 0.57%   |
| Intel Pentium Dual-Core        | 1         | 0.57%   |
| Intel Pentium 4                | 1         | 0.57%   |
| Intel Core i9                  | 1         | 0.57%   |
| Intel Core 2 Quad              | 1         | 0.57%   |
| ARM BCM                        | 1         | 0.57%   |
| AMD V120                       | 1         | 0.57%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.57%   |
| AMD Turion 64 X2               | 1         | 0.57%   |
| AMD Sempron                    | 1         | 0.57%   |
| AMD Ryzen 7 PRO                | 1         | 0.57%   |
| AMD Phenom II X4               | 1         | 0.57%   |
| AMD E2                         | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 87        | 49.43%  |
| 4      | 59        | 33.52%  |
| 6      | 13        | 7.39%   |
| 8      | 8         | 4.55%   |
| 1      | 5         | 2.84%   |
| 10     | 2         | 1.14%   |
| 20     | 1         | 0.57%   |
| 3      | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 174       | 98.86%  |
| 2      | 2         | 1.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 104       | 59.09%  |
| 1      | 72        | 40.91%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 171       | 96.61%  |
| Unknown        | 4         | 2.26%   |
| 32-bit         | 2         | 1.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 28        | 15.56%  |
| 0x206a7    | 12        | 6.67%   |
| 0x306c3    | 11        | 6.11%   |
| 0x40651    | 7         | 3.89%   |
| 0x306a9    | 7         | 3.89%   |
| 0x806e9    | 6         | 3.33%   |
| 0x306d4    | 6         | 3.33%   |
| 0x08108109 | 6         | 3.33%   |
| 0x906ea    | 5         | 2.78%   |
| 0x906e9    | 5         | 2.78%   |
| 0x506e3    | 5         | 2.78%   |
| 0x406c4    | 5         | 2.78%   |
| 0x806ec    | 4         | 2.22%   |
| 0x706a1    | 4         | 2.22%   |
| 0x406e3    | 4         | 2.22%   |
| 0x08701021 | 4         | 2.22%   |
| 0x806eb    | 3         | 1.67%   |
| 0x806ea    | 3         | 1.67%   |
| 0x20655    | 3         | 1.67%   |
| 0x05000119 | 3         | 1.67%   |
| 0x906eb    | 2         | 1.11%   |
| 0x806c1    | 2         | 1.11%   |
| 0x706a8    | 2         | 1.11%   |
| 0x6fd      | 2         | 1.11%   |
| 0x6f6      | 2         | 1.11%   |
| 0x306e4    | 2         | 1.11%   |
| 0x30678    | 2         | 1.11%   |
| 0x1067a    | 2         | 1.11%   |
| 0x10676    | 2         | 1.11%   |
| 0x08600104 | 2         | 1.11%   |
| 0x07030105 | 2         | 1.11%   |
| 0x06000852 | 2         | 1.11%   |
| 0x010000c8 | 2         | 1.11%   |
| 0xf49      | 1         | 0.56%   |
| 0xf29      | 1         | 0.56%   |
| 0x906ed    | 1         | 0.56%   |
| 0x906ec    | 1         | 0.56%   |
| 0x90672    | 1         | 0.56%   |
| 0x6ec      | 1         | 0.56%   |
| 0x50654    | 1         | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 34        | 19.32%  |
| Haswell         | 20        | 11.36%  |
| SandyBridge     | 16        | 9.09%   |
| Skylake         | 12        | 6.82%   |
| Zen 2           | 9         | 5.11%   |
| IvyBridge       | 9         | 5.11%   |
| Zen+            | 8         | 4.55%   |
| Silvermont      | 8         | 4.55%   |
| Penryn          | 6         | 3.41%   |
| Goldmont plus   | 6         | 3.41%   |
| Broadwell       | 6         | 3.41%   |
| Core            | 5         | 2.84%   |
| Westmere        | 4         | 2.27%   |
| TigerLake       | 3         | 1.7%    |
| Piledriver      | 3         | 1.7%    |
| K10             | 3         | 1.7%    |
| Excavator       | 3         | 1.7%    |
| Bobcat          | 3         | 1.7%    |
| Puma            | 2         | 1.14%   |
| NetBurst        | 2         | 1.14%   |
| Nehalem         | 2         | 1.14%   |
| IceLake         | 2         | 1.14%   |
| Unknown         | 2         | 1.14%   |
| Zen 3           | 1         | 0.57%   |
| P6              | 1         | 0.57%   |
| K8 Hammer       | 1         | 0.57%   |
| K8 & K10 hybrid | 1         | 0.57%   |
| K10 Llano       | 1         | 0.57%   |
| Jaguar          | 1         | 0.57%   |
| Bulldozer       | 1         | 0.57%   |
| Bonnell         | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 117       | 59.09%  |
| Nvidia | 42        | 21.21%  |
| AMD    | 39        | 19.7%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 14        | 6.76%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 3.86%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 3.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 3.38%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 2.9%    |
| Intel HD Graphics 620                                                                    | 6         | 2.9%    |
| Intel HD Graphics 5500                                                                   | 6         | 2.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 2.9%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 2.9%    |
| Intel UHD Graphics 620                                                                   | 5         | 2.42%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.93%   |
| Intel HD Graphics 630                                                                    | 4         | 1.93%   |
| Intel HD Graphics 530                                                                    | 4         | 1.93%   |
| AMD Renoir                                                                               | 4         | 1.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 4         | 1.93%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 1.45%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 3         | 1.45%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 1.45%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 1.45%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.45%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3         | 1.45%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 1.45%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 2         | 0.97%   |
| Nvidia GT218 [GeForce 8400 GS Rev. 3]                                                    | 2         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.97%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.97%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.97%   |
| Nvidia GF108 [GeForce GT 430]                                                            | 2         | 0.97%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 2         | 0.97%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.97%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.97%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 2         | 0.97%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.97%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.97%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.97%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 2         | 0.97%   |
| Nvidia TU117M                                                                            | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 98        | 55.37%  |
| 1 x AMD        | 29        | 16.38%  |
| 1 x Nvidia     | 24        | 13.56%  |
| Intel + Nvidia | 15        | 8.47%   |
| 2 x AMD        | 5         | 2.82%   |
| AMD + Nvidia   | 3         | 1.69%   |
| Intel + AMD    | 2         | 1.13%   |
| Other          | 1         | 0.56%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 154       | 86.03%  |
| Proprietary | 21        | 11.73%  |
| Unknown     | 4         | 2.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 112       | 61.88%  |
| 1.01-2.0   | 22        | 12.15%  |
| 0.01-0.5   | 17        | 9.39%   |
| 3.01-4.0   | 12        | 6.63%   |
| 0.51-1.0   | 11        | 6.08%   |
| 5.01-6.0   | 6         | 3.31%   |
| 7.01-8.0   | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 27        | 12.92%  |
| AOC                     | 24        | 11.48%  |
| LG Display              | 20        | 9.57%   |
| Samsung Electronics     | 19        | 9.09%   |
| Chimei Innolux          | 17        | 8.13%   |
| BOE                     | 16        | 7.66%   |
| Hewlett-Packard         | 13        | 6.22%   |
| Dell                    | 12        | 5.74%   |
| Goldstar                | 10        | 4.78%   |
| Apple                   | 6         | 2.87%   |
| ViewSonic               | 5         | 2.39%   |
| Sony                    | 3         | 1.44%   |
| Chi Mei Optoelectronics | 3         | 1.44%   |
| BenQ                    | 3         | 1.44%   |
| AGO                     | 3         | 1.44%   |
| Acer                    | 3         | 1.44%   |
| Sharp                   | 2         | 0.96%   |
| Panasonic               | 2         | 0.96%   |
| CPT                     | 2         | 0.96%   |
| ASUSTek Computer        | 2         | 0.96%   |
| Ancor Communications    | 2         | 0.96%   |
| Xerox                   | 1         | 0.48%   |
| Unknown (XXX)           | 1         | 0.48%   |
| Royal Information       | 1         | 0.48%   |
| Philips                 | 1         | 0.48%   |
| PAR                     | 1         | 0.48%   |
| MSI                     | 1         | 0.48%   |
| LTM                     | 1         | 0.48%   |
| LG Philips              | 1         | 0.48%   |
| Lenovo                  | 1         | 0.48%   |
| KDC                     | 1         | 0.48%   |
| Hitachi                 | 1         | 0.48%   |
| Haier                   | 1         | 0.48%   |
| GAOMON                  | 1         | 0.48%   |
| Envision                | 1         | 0.48%   |
| CVT                     | 1         | 0.48%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| AOC 2370 AOC2370 1920x1080 509x286mm 23.0-inch                       | 5         | 2.34%   |
| Apple LCD Monitor APP9CC5 1280x800 286x179mm 13.3-inch               | 4         | 1.87%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 3         | 1.4%    |
| Dell LCD Monitor DELA102 1920x1080 540x300mm 24.3-inch               | 3         | 1.4%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 1.4%    |
| AU Optronics LCD Monitor AUO25ED 1920x1080 344x194mm 15.5-inch       | 3         | 1.4%    |
| AGO LCD Monitor AGO0001 1920x1080 256x192mm 12.6-inch                | 3         | 1.4%    |
| Sony TV SNY0902 1360x768                                             | 2         | 0.93%   |
| Samsung Electronics LCD Monitor SAM0A76 1280x720 949x543mm 43.0-inch | 2         | 0.93%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                   | 2         | 0.93%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 2         | 0.93%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch          | 2         | 0.93%   |
| Hewlett-Packard L1908w HWP26F0 1440x900 410x256mm 19.0-inch          | 2         | 0.93%   |
| Hewlett-Packard 22cwa HWP3183 1920x1080 476x268mm 21.5-inch          | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN1482 1600x900 309x174mm 14.0-inch      | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 2         | 0.93%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 2         | 0.93%   |
| Xerox XA3-17 XER7B10 1280x1024 337x270mm 17.0-inch                   | 1         | 0.47%   |
| ViewSonic VX2778 Series VSC8432 2560x1440 597x336mm 27.0-inch        | 1         | 0.47%   |
| ViewSonic VA2359 Series VSC6332 1920x1080 509x286mm 23.0-inch        | 1         | 0.47%   |
| ViewSonic VA1703wb-2 VSCA21F 1440x900 367x230mm 17.1-inch            | 1         | 0.47%   |
| ViewSonic LCD Monitor VX2458-mhd 3286x1080                           | 1         | 0.47%   |
| ViewSonic LCD Monitor VX2260WM                                       | 1         | 0.47%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 1         | 0.47%   |
| Sony TV SNY1B02 1360x768 1600x900mm 72.3-inch                        | 1         | 0.47%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch              | 1         | 0.47%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch              | 1         | 0.47%   |
| Samsung Electronics U32J59x SAM0F35 3840x2160 697x392mm 31.5-inch    | 1         | 0.47%   |
| Samsung Electronics SyncMaster SAM058A 1920x1080 531x298mm 24.0-inch | 1         | 0.47%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3847 1440x900 367x230mm 17.1-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC345A 1366x768 309x174mm 14.0-inch | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 73        | 37.06%  |
| 1366x768 (WXGA)   | 55        | 27.92%  |
| 3840x2160 (4K)    | 14        | 7.11%   |
| 1600x900 (HD+)    | 12        | 6.09%   |
| 1440x900 (WXGA+)  | 10        | 5.08%   |
| 1280x800 (WXGA)   | 10        | 5.08%   |
| 1280x1024 (SXGA)  | 8         | 4.06%   |
| 2560x1440 (QHD)   | 3         | 1.52%   |
| 3286x1080         | 2         | 1.02%   |
| 2560x1080         | 2         | 1.02%   |
| 1360x768          | 2         | 1.02%   |
| 1280x720 (HD)     | 2         | 1.02%   |
| Unknown           | 2         | 1.02%   |
| 1920x1200 (WUXGA) | 1         | 0.51%   |
| 1280x960          | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 53        | 25.48%  |
| 14      | 24        | 11.54%  |
| 13      | 23        | 11.06%  |
| 23      | 15        | 7.21%   |
| 19      | 15        | 7.21%   |
| 24      | 12        | 5.77%   |
| 18      | 10        | 4.81%   |
| 17      | 10        | 4.81%   |
| 21      | 9         | 4.33%   |
| Unknown | 7         | 3.37%   |
| 27      | 5         | 2.4%    |
| 84      | 4         | 1.92%   |
| 12      | 4         | 1.92%   |
| 72      | 3         | 1.44%   |
| 32      | 3         | 1.44%   |
| 43      | 2         | 0.96%   |
| 40      | 2         | 0.96%   |
| 34      | 2         | 0.96%   |
| 31      | 2         | 0.96%   |
| 11      | 2         | 0.96%   |
| 54      | 1         | 0.48%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 96        | 46.15%  |
| 501-600     | 32        | 15.38%  |
| 401-500     | 31        | 14.9%   |
| 201-300     | 14        | 6.73%   |
| 351-400     | 9         | 4.33%   |
| 1501-2000   | 7         | 3.37%   |
| Unknown     | 7         | 3.37%   |
| 701-800     | 5         | 2.4%    |
| 801-900     | 2         | 0.96%   |
| 601-700     | 2         | 0.96%   |
| 901-1000    | 2         | 0.96%   |
| 1001-1500   | 1         | 0.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 139       | 76.8%   |
| 16/10   | 22        | 12.15%  |
| 5/4     | 7         | 3.87%   |
| Unknown | 7         | 3.87%   |
| 4/3     | 4         | 2.21%   |
| 21/9    | 2         | 1.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 52        | 25%     |
| 81-90          | 44        | 21.15%  |
| 201-250        | 28        | 13.46%  |
| 151-200        | 20        | 9.62%   |
| 141-150        | 12        | 5.77%   |
| More than 1000 | 8         | 3.85%   |
| 351-500        | 7         | 3.37%   |
| Unknown        | 7         | 3.37%   |
| 71-80          | 6         | 2.88%   |
| 301-350        | 5         | 2.4%    |
| 251-300        | 5         | 2.4%    |
| 121-130        | 4         | 1.92%   |
| 501-1000       | 4         | 1.92%   |
| 51-60          | 2         | 0.96%   |
| 131-140        | 2         | 0.96%   |
| 61-70          | 1         | 0.48%   |
| 111-120        | 1         | 0.48%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 66        | 32.84%  |
| 51-100        | 65        | 32.34%  |
| 121-160       | 47        | 23.38%  |
| 1-50          | 7         | 3.48%   |
| 161-240       | 7         | 3.48%   |
| Unknown       | 7         | 3.48%   |
| More than 240 | 2         | 1%      |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 144       | 77.42%  |
| 2     | 36        | 19.35%  |
| 0     | 4         | 2.15%   |
| 3     | 2         | 1.08%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 105       | 39.03%  |
| Intel                    | 65        | 24.16%  |
| Qualcomm Atheros         | 41        | 15.24%  |
| Broadcom                 | 19        | 7.06%   |
| Broadcom Limited         | 8         | 2.97%   |
| TP-Link                  | 6         | 2.23%   |
| Xiaomi                   | 3         | 1.12%   |
| Ralink                   | 3         | 1.12%   |
| Nvidia                   | 3         | 1.12%   |
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

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 19.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 7.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 9         | 2.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 7         | 2.16%   |
| Intel Wireless 7265                                               | 7         | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.85%   |
| Intel Wireless 7260                                               | 6         | 1.85%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 1.85%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 5         | 1.54%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 5         | 1.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.54%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 1.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.23%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.23%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 4         | 1.23%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 0.93%   |
| TP-Link 802.11n NIC                                               | 3         | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.93%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 3         | 0.93%   |
| Realtek 802.11ac NIC                                              | 3         | 0.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 0.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 3         | 0.93%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 0.93%   |
| Intel Wireless 8265 / 8275                                        | 3         | 0.93%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.93%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.93%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 3         | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 2         | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.62%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 0.62%   |
| Intel Wireless 8260                                               | 2         | 0.62%   |
| Intel Wireless 3160                                               | 2         | 0.62%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.62%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 33.79%  |
| Qualcomm Atheros      | 33        | 22.76%  |
| Realtek Semiconductor | 29        | 20%     |
| Broadcom              | 13        | 8.97%   |
| Broadcom Limited      | 7         | 4.83%   |
| TP-Link               | 6         | 4.14%   |
| Ralink                | 3         | 2.07%   |
| Linksys               | 2         | 1.38%   |
| Ralink Technology     | 1         | 0.69%   |
| Dell                  | 1         | 0.69%   |
| D-Link                | 1         | 0.69%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Computers | Percent |
|-----------------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                                    | 9         | 6.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                                    | 7         | 4.76%   |
| Intel Wireless 7265                                                                           | 7         | 4.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 6         | 4.08%   |
| Intel Wireless 7260                                                                           | 6         | 4.08%   |
| Intel Wi-Fi 6 AX200                                                                           | 6         | 4.08%   |
| Realtek RTL8723DE Wireless Network Adapter                                                    | 5         | 3.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                                  | 5         | 3.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                                               | 5         | 3.4%    |
| Broadcom BCM43142 802.11b/g/n                                                                 | 5         | 3.4%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                               | 4         | 2.72%   |
| Broadcom BCM4331 802.11a/b/g/n                                                                | 4         | 2.72%   |
| TP-Link 802.11n NIC                                                                           | 3         | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                                      | 3         | 2.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 3         | 2.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                                    | 3         | 2.04%   |
| Realtek 802.11ac NIC                                                                          | 3         | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                                    | 3         | 2.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                                | 3         | 2.04%   |
| Intel Wireless 8265 / 8275                                                                    | 3         | 2.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                                      | 3         | 2.04%   |
| Realtek RTL8188EE Wireless Network Adapter                                                    | 2         | 1.36%   |
| Intel Wireless 8260                                                                           | 2         | 1.36%   |
| Intel Wireless 3160                                                                           | 2         | 1.36%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 2         | 1.36%   |
| Intel Centrino Advanced-N 6235                                                                | 2         | 1.36%   |
| Broadcom Limited BCM4311 802.11a/b/g                                                          | 2         | 1.36%   |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                         | 1         | 0.68%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 1         | 0.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 1         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                                      | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 1         | 0.68%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                                      | 1         | 0.68%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                                               | 1         | 0.68%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                                                        | 1         | 0.68%   |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller                                     | 1         | 0.68%   |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 1         | 0.68%   |
| Ralink MT7601U Wireless Adapter                                                               | 1         | 0.68%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                                        | 1         | 0.68%   |
| Ralink RT3062 Wireless 802.11n 2T/2R                                                          | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 95        | 55.56%  |
| Intel                    | 35        | 20.47%  |
| Broadcom                 | 12        | 7.02%   |
| Qualcomm Atheros         | 11        | 6.43%   |
| Xiaomi                   | 3         | 1.75%   |
| Nvidia                   | 3         | 1.75%   |
| Huawei Technologies      | 2         | 1.17%   |
| ASIX Electronics         | 2         | 1.17%   |
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

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 36.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 23        | 12.99%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 2.26%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 2.26%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1.69%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 1.69%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.69%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.13%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.13%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 2         | 1.13%   |
| Intel Ethernet Controller I225-V                                  | 2         | 1.13%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.13%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.13%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 1.13%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.13%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 1.13%   |
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
| MediaTek Nokia 5.1 Plus                                           | 1         | 0.56%   |
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

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 157       | 53.4%   |
| WiFi     | 137       | 46.6%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 107       | 58.47%  |
| Ethernet | 76        | 41.53%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 114       | 64.04%  |
| 1     | 54        | 30.34%  |
| 3     | 5         | 2.81%   |
| 0     | 4         | 2.25%   |
| 4     | 1         | 0.56%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 175       | 98.87%  |
| Yes  | 2         | 1.13%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 39.22%  |
| Qualcomm Atheros Communications | 14        | 13.73%  |
| Realtek Semiconductor           | 13        | 12.75%  |
| Cambridge Silicon Radio         | 7         | 6.86%   |
| Broadcom                        | 7         | 6.86%   |
| Apple                           | 6         | 5.88%   |
| Toshiba                         | 3         | 2.94%   |
| Lite-On Technology              | 3         | 2.94%   |
| IMC Networks                    | 2         | 1.96%   |
| ASUSTek Computer                | 2         | 1.96%   |
| Realtek                         | 1         | 0.98%   |
| Marvell Semiconductor           | 1         | 0.98%   |
| Hewlett-Packard                 | 1         | 0.98%   |
| Foxconn / Hon Hai               | 1         | 0.98%   |
| Dell                            | 1         | 0.98%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                           | 18        | 17.65%  |
| Qualcomm Atheros  Bluetooth Device                           | 9         | 8.82%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)               | 8         | 7.84%   |
| Realtek Bluetooth Radio                                      | 7         | 6.86%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)          | 7         | 6.86%   |
| Realtek  Bluetooth 4.2 Adapter                               | 6         | 5.88%   |
| Intel AX200 Bluetooth                                        | 6         | 5.88%   |
| Apple Bluetooth Host Controller                              | 4         | 3.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                       | 3         | 2.94%   |
| Intel Centrino Bluetooth Wireless Transceiver                | 3         | 2.94%   |
| Broadcom BCM43142A0 Bluetooth 4.0                            | 3         | 2.94%   |
| Toshiba Bluetooth Device                                     | 2         | 1.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                   | 2         | 1.96%   |
| Intel Wireless-AC 3168 Bluetooth                             | 2         | 1.96%   |
| Intel AX201 Bluetooth                                        | 2         | 1.96%   |
| Toshiba BCM43142A0                                           | 1         | 0.98%   |
| Realtek Bluetooth Radio                                      | 1         | 0.98%   |
| Qualcomm Atheros Bluetooth USB Host Controller               | 1         | 0.98%   |
| Qualcomm Atheros AR3011 Bluetooth                            | 1         | 0.98%   |
| Marvell Bluetooth and Wireless LAN Composite Device          | 1         | 0.98%   |
| Lite-On Bluetooth Device                                     | 1         | 0.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                     | 1         | 0.98%   |
| IMC Networks Bluetooth Radio                                 | 1         | 0.98%   |
| IMC Networks Bluetooth                                       | 1         | 0.98%   |
| HP Broadcom 2070 Bluetooth Combo                             | 1         | 0.98%   |
| Foxconn / Hon Hai Bluetooth Device                           | 1         | 0.98%   |
| Dell Broadcom BCM20702A0 Bluetooth                           | 1         | 0.98%   |
| Broadcom HP Portable SoftSailing                             | 1         | 0.98%   |
| Broadcom BCM43142 Bluetooth 4.0                              | 1         | 0.98%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                         | 1         | 0.98%   |
| Broadcom 2045 Bluetooth 2.0 USB-UHE Device with trace filter | 1         | 0.98%   |
| ASUS Qualcomm Bluetooth 4.1                                  | 1         | 0.98%   |
| ASUS Broadcom BCM20702A0 Bluetooth                           | 1         | 0.98%   |
| Apple Bluetooth USB Host Controller                          | 1         | 0.98%   |
| Apple Bluetooth HCI                                          | 1         | 0.98%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 134       | 57.51%  |
| AMD                     | 45        | 19.31%  |
| Nvidia                  | 31        | 13.3%   |
| C-Media Electronics     | 4         | 1.72%   |
| Generalplus Technology  | 3         | 1.29%   |
| Logitech                | 2         | 0.86%   |
| JMTek                   | 2         | 0.86%   |
| GN Netcom               | 2         | 0.86%   |
| Realtek Semiconductor   | 1         | 0.43%   |
| Plantronics             | 1         | 0.43%   |
| Medeli Electronics      | 1         | 0.43%   |
| Lenovo                  | 1         | 0.43%   |
| Corsair                 | 1         | 0.43%   |
| CMX Systems             | 1         | 0.43%   |
| Blue Microphones        | 1         | 0.43%   |
| BEHRINGER International | 1         | 0.43%   |
| Argosy Research         | 1         | 0.43%   |
| Afatech                 | 1         | 0.43%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 5.73%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 15        | 5.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 4.3%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 11        | 3.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 10        | 3.58%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 9         | 3.23%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.87%   |
| Intel Cannon Lake PCH cAVS                                                                        | 8         | 2.87%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.87%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 2.51%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.51%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 2.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.15%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 6         | 2.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 6         | 2.15%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 2.15%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 6         | 2.15%   |
| AMD FCH Azalia Controller                                                                         | 6         | 2.15%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 1.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.79%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.79%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.43%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.43%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 4         | 1.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 1.08%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 1.08%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.08%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 3         | 1.08%   |
| Generalplus Technology Usb Audio Device                                                           | 3         | 1.08%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 3         | 1.08%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 3         | 1.08%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 3         | 1.08%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 1.08%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.72%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 2         | 0.72%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.72%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29        | 24.79%  |
| Kingston            | 20        | 17.09%  |
| SK hynix            | 19        | 16.24%  |
| Micron Technology   | 15        | 12.82%  |
| Corsair             | 7         | 5.98%   |
| Crucial             | 6         | 5.13%   |
| A-DATA Technology   | 5         | 4.27%   |
| Unknown             | 4         | 3.42%   |
| Team                | 4         | 3.42%   |
| Nanya Technology    | 4         | 3.42%   |
| Patriot             | 2         | 1.71%   |
| Kimtigo             | 1         | 0.85%   |
| G.Skill             | 1         | 0.85%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Micron RAM 8KTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s       | 5         | 3.7%    |
| Team RAM TEAMGROUP-SD4-2666 8GB SODIMM DDR4 2667MT/s      | 4         | 2.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 3         | 2.22%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 3         | 2.22%   |
| Kingston RAM 9905584-015.A00LF 4GB DIMM 1600MT/s          | 3         | 2.22%   |
| Corsair RAM Module 8GB SODIMM DDR3 1333MT/s               | 3         | 2.22%   |
| Corsair RAM Module 4GB SODIMM DDR3 1333MT/s               | 3         | 2.22%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 2         | 1.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 2         | 1.48%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8192MB SODIMM DDR4 2667MT/s | 2         | 1.48%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 2         | 1.48%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.48%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 2         | 1.48%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s     | 2         | 1.48%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s      | 2         | 1.48%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 2         | 1.48%   |
| Kingston RAM 9905402-174.A00G 4GB DIMM DDR3 1600MT/s      | 2         | 1.48%   |
| Unknown RAM Module 8GB SODIMM DDR3 1333MT/s               | 1         | 0.74%   |
| Unknown RAM Module 8GB SODIMM DDR3                        | 1         | 0.74%   |
| Unknown RAM Module 4GB SODIMM DDR3                        | 1         | 0.74%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                | 1         | 0.74%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1867MT/s           | 1         | 0.74%   |
| SK hynix RAM Module 16GB DIMM DDR4 2667MT/s               | 1         | 0.74%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1         | 0.74%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s      | 1         | 0.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.74%   |
| SK hynix RAM HMT425S6CFR6A-PB 2048MB SODIMM DDR3 1600MT/s | 1         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 1         | 0.74%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s | 1         | 0.74%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s      | 1         | 0.74%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1333MT/s      | 1         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 1         | 0.74%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s    | 1         | 0.74%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s    | 1         | 0.74%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 1         | 0.74%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s   | 1         | 0.74%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s   | 1         | 0.74%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s | 1         | 0.74%   |
| SK hynix RAM HMA451S6AFR8N-TF 4096MB SODIMM DDR4 2133MT/s | 1         | 0.74%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s     | 1         | 0.74%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 46        | 46.94%  |
| DDR3   | 43        | 43.88%  |
| SDRAM  | 4         | 4.08%   |
| DDR2   | 4         | 4.08%   |
| LPDDR4 | 1         | 1.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 67.37%  |
| DIMM         | 27        | 28.42%  |
| Row Of Chips | 3         | 3.16%   |
| Chip         | 1         | 1.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 47        | 42.73%  |
| 8192  | 32        | 29.09%  |
| 16384 | 13        | 11.82%  |
| 2048  | 12        | 10.91%  |
| 32768 | 6         | 5.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 31        | 27.43%  |
| 2667    | 24        | 21.24%  |
| 1333    | 10        | 8.85%   |
| 3200    | 6         | 5.31%   |
| 2400    | 6         | 5.31%   |
| 1334    | 5         | 4.42%   |
| 667     | 5         | 4.42%   |
| 3266    | 3         | 2.65%   |
| 2133    | 3         | 2.65%   |
| 4199    | 2         | 1.77%   |
| 3600    | 2         | 1.77%   |
| 3466    | 2         | 1.77%   |
| 2933    | 2         | 1.77%   |
| Unknown | 2         | 1.77%   |
| 8400    | 1         | 0.88%   |
| 3400    | 1         | 0.88%   |
| 3100    | 1         | 0.88%   |
| 2934    | 1         | 0.88%   |
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

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 25        | 20.33%  |
| Microdia                               | 14        | 11.38%  |
| Realtek Semiconductor                  | 11        | 8.94%   |
| IMC Networks                           | 11        | 8.94%   |
| Sunplus Innovation Technology          | 8         | 6.5%    |
| Logitech                               | 8         | 6.5%    |
| Apple                                  | 7         | 5.69%   |
| Microsoft                              | 5         | 4.07%   |
| Suyin                                  | 3         | 2.44%   |
| Quanta                                 | 3         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.44%   |
| Acer                                   | 3         | 2.44%   |
| Z-Star Microelectronics                | 2         | 1.63%   |
| Syntek                                 | 2         | 1.63%   |
| Primax Electronics                     | 2         | 1.63%   |
| Luxvisions Innotech Limited            | 2         | 1.63%   |
| Lite-On Technology                     | 2         | 1.63%   |
| Alcor Micro                            | 2         | 1.63%   |
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

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD         | 10        | 7.94%   |
| Chicony Integrated Camera             | 5         | 3.97%   |
| IMC Networks Integrated Camera        | 4         | 3.17%   |
| Apple FaceTime HD Camera              | 4         | 3.17%   |
| Sunplus Integrated_Webcam_HD          | 3         | 2.38%   |
| Sunplus HD WebCam                     | 3         | 2.38%   |
| Realtek Integrated_Webcam_HD          | 3         | 2.38%   |
| Microsoft LifeCam HD-3000             | 3         | 2.38%   |
| Logitech Webcam C270                  | 3         | 2.38%   |
| Chicony TOSHIBA Web Camera - HD       | 3         | 2.38%   |
| Syntek EasyCamera                     | 2         | 1.59%   |
| Realtek Integrated Webcam HD          | 2         | 1.59%   |
| Realtek Integrated Webcam             | 2         | 1.59%   |
| Quanta HD WebCam                      | 2         | 1.59%   |
| Microdia Integrated Webcam            | 2         | 1.59%   |
| IMC Networks USB2.0 VGA UVC WebCam    | 2         | 1.59%   |
| IMC Networks USB2.0 HD UVC WebCam     | 2         | 1.59%   |
| Chicony USB 2.0 Camera                | 2         | 1.59%   |
| Chicony Integrated HP HD Webcam       | 2         | 1.59%   |
| Chicony HP Truevision HD              | 2         | 1.59%   |
| Chicony 720p HD Camera                | 2         | 1.59%   |
| Z-Star Vega USB2.0 Camera             | 1         | 0.79%   |
| Z-Star A4 TECH USB2.0 PC Camera E     | 1         | 0.79%   |
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
| Microsoft LifeCam Cinema              | 1         | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


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

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


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

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


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

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


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

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 125       | 68.31%  |
| 1     | 48        | 26.23%  |
| 2     | 6         | 3.28%   |
| 3     | 4         | 2.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21        | 30%     |
| Net/wireless             | 15        | 21.43%  |
| Graphics card            | 12        | 17.14%  |
| Chipcard                 | 10        | 14.29%  |
| Communication controller | 3         | 4.29%   |
| Sound                    | 2         | 2.86%   |
| Multimedia controller    | 2         | 2.86%   |
| Unassigned class         | 1         | 1.43%   |
| Network                  | 1         | 1.43%   |
| Net/ethernet             | 1         | 1.43%   |
| Firewire controller      | 1         | 1.43%   |
| Bluetooth                | 1         | 1.43%   |

