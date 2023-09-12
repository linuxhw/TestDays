Xero - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------

A project to collect tested hardware configurations for Xero.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 181

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
| Dell      | Inspiron 7460               | [03726302da](https://linux-hardware.org/?probe=03726302da) | Sep 07, 2023 |
| HP        | ProBook 455 15.6 inch G9... | [5b7ab92e89](https://linux-hardware.org/?probe=5b7ab92e89) | Sep 06, 2023 |
| Acer      | Aspire 5742                 | [ff917b0920](https://linux-hardware.org/?probe=ff917b0920) | Sep 02, 2023 |
| HUAWEI    | HN-WX9X                     | [efd67d7c17](https://linux-hardware.org/?probe=efd67d7c17) | Sep 02, 2023 |
| Dell      | Latitude 5420               | [2acb1da32c](https://linux-hardware.org/?probe=2acb1da32c) | Sep 02, 2023 |
| Lenovo    | IdeaPad 3 14ALC6 82KT       | [9de67aa419](https://linux-hardware.org/?probe=9de67aa419) | Sep 01, 2023 |
| Dell      | G15 5530                    | [ababfa6c5e](https://linux-hardware.org/?probe=ababfa6c5e) | Aug 31, 2023 |
| HP        | 255 G8 Notebook PC          | [92552fa038](https://linux-hardware.org/?probe=92552fa038) | Aug 30, 2023 |
| Acer      | Aspire A315-58              | [75ef08524c](https://linux-hardware.org/?probe=75ef08524c) | Aug 30, 2023 |
| Dell      | Latitude E6520              | [4918e66ad8](https://linux-hardware.org/?probe=4918e66ad8) | Aug 29, 2023 |
| Lenovo    | IdeaPad 3 14ALC6 82KT       | [fc7834595f](https://linux-hardware.org/?probe=fc7834595f) | Aug 29, 2023 |
| Acer      | Aspire V5-471               | [c5d2dabe27](https://linux-hardware.org/?probe=c5d2dabe27) | Aug 28, 2023 |
| Timi      | Redmi Book Pro 14 2022      | [8f85c500ec](https://linux-hardware.org/?probe=8f85c500ec) | Aug 27, 2023 |
| ASUSTek   | ASUS TUF Gaming A17 FA70... | [211472aacc](https://linux-hardware.org/?probe=211472aacc) | Aug 26, 2023 |
| HP        | Laptop 14-dq2xxx            | [0c46e2d419](https://linux-hardware.org/?probe=0c46e2d419) | Aug 26, 2023 |
| HP        | Laptop 15-da2xxx            | [01636af413](https://linux-hardware.org/?probe=01636af413) | Aug 25, 2023 |
| Google    | Pirika                      | [f0937aba65](https://linux-hardware.org/?probe=f0937aba65) | Aug 23, 2023 |
| Lenovo    | ThinkPad P50 20EQS4XN00     | [a517cc57b8](https://linux-hardware.org/?probe=a517cc57b8) | Aug 23, 2023 |
| VIT       | P2402                       | [fa87ae71d4](https://linux-hardware.org/?probe=fa87ae71d4) | Aug 22, 2023 |
| VIT       | P2402                       | [7b83628f3c](https://linux-hardware.org/?probe=7b83628f3c) | Aug 22, 2023 |
| ASUSTek   | X510UAR                     | [cdef569014](https://linux-hardware.org/?probe=cdef569014) | Aug 22, 2023 |
| HP        | Laptop 15-dy1xxx            | [e00521ec88](https://linux-hardware.org/?probe=e00521ec88) | Aug 22, 2023 |
| HUAWEI    | HVY-WXX9                    | [d63bd363bc](https://linux-hardware.org/?probe=d63bd363bc) | Aug 22, 2023 |
| ASUSTek   | ROG Strix G531GT_G531GT     | [882234a7b8](https://linux-hardware.org/?probe=882234a7b8) | Aug 22, 2023 |
| Dell      | Inspiron 5558               | [ee47d4b6a7](https://linux-hardware.org/?probe=ee47d4b6a7) | Aug 20, 2023 |
| HONOR     | BBR-WAX9                    | [1d013fbf4b](https://linux-hardware.org/?probe=1d013fbf4b) | Aug 20, 2023 |
| Lenovo    | Rev B 82KU                  | [114345f952](https://linux-hardware.org/?probe=114345f952) | Aug 18, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop X712... | [faaba537ca](https://linux-hardware.org/?probe=faaba537ca) | Aug 18, 2023 |
| Lenovo    | IdeaPad S145-15IIL 82DJ     | [d7ec063f46](https://linux-hardware.org/?probe=d7ec063f46) | Aug 16, 2023 |
| Lenovo    | ThinkPad X1 Carbon 3rd 2... | [c078e667a4](https://linux-hardware.org/?probe=c078e667a4) | Aug 15, 2023 |
| Lenovo    | IdeaPad Gaming 3 15IHU6 ... | [1c643cc90f](https://linux-hardware.org/?probe=1c643cc90f) | Aug 13, 2023 |
| Fujitsu   | LIFEBOOK A3510              | [3e830ffabc](https://linux-hardware.org/?probe=3e830ffabc) | Aug 12, 2023 |
| Dell      | G3 3590                     | [084d659110](https://linux-hardware.org/?probe=084d659110) | Aug 11, 2023 |
| LNV       | L40-70                      | [66fe107447](https://linux-hardware.org/?probe=66fe107447) | Aug 11, 2023 |
| Lenovo    | Yoga 3 Pro-1370 80HE        | [eee160a070](https://linux-hardware.org/?probe=eee160a070) | Aug 10, 2023 |
| HP        | Laptop 15s-eq3xxx           | [284cfb0f6d](https://linux-hardware.org/?probe=284cfb0f6d) | Aug 08, 2023 |
| ASUSTek   | ASUS TUF Gaming F15 FX50... | [c9c978701a](https://linux-hardware.org/?probe=c9c978701a) | Aug 08, 2023 |
| WEIGO     | CDA-141AU                   | [35c705bd70](https://linux-hardware.org/?probe=35c705bd70) | Aug 05, 2023 |
| Dell      | Inspiron 3558               | [5331913f13](https://linux-hardware.org/?probe=5331913f13) | Aug 04, 2023 |
| Lenovo    | IdeaPad Gaming 3 15IHU6 ... | [8b84e48f4c](https://linux-hardware.org/?probe=8b84e48f4c) | Aug 04, 2023 |
| HP        | Laptop 15-dy1xxx            | [6dbeaa5f27](https://linux-hardware.org/?probe=6dbeaa5f27) | Aug 04, 2023 |
| Acer      | Aspire V3-371               | [5d5a4b489b](https://linux-hardware.org/?probe=5d5a4b489b) | Aug 03, 2023 |
| Fujitsu   | LIFEBOOK A3510              | [7281304bf0](https://linux-hardware.org/?probe=7281304bf0) | Aug 02, 2023 |
| Dell      | G3 3590                     | [78aeeb1aa3](https://linux-hardware.org/?probe=78aeeb1aa3) | Aug 02, 2023 |
| Dell      | G3 3590                     | [47d3c9b9fe](https://linux-hardware.org/?probe=47d3c9b9fe) | Aug 02, 2023 |
| Dell      | XPS 15 7590                 | [39216c08ff](https://linux-hardware.org/?probe=39216c08ff) | Aug 01, 2023 |
| Lenovo    | ThinkPad T480 20L6S2CE00    | [eb14620792](https://linux-hardware.org/?probe=eb14620792) | Jul 30, 2023 |
| Apple     | MacBookPro11,1              | [3fb2cba3db](https://linux-hardware.org/?probe=3fb2cba3db) | Jul 29, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop X712... | [a467ce5440](https://linux-hardware.org/?probe=a467ce5440) | Jul 28, 2023 |
| Acer      | Aspire A315-42              | [3afa5a3034](https://linux-hardware.org/?probe=3afa5a3034) | Jul 27, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop X712... | [dc632de3b5](https://linux-hardware.org/?probe=dc632de3b5) | Jul 27, 2023 |
| HP        | Laptop 14-fq1xxx            | [5de59d7736](https://linux-hardware.org/?probe=5de59d7736) | Jul 27, 2023 |
| Apple     | MacBook7,1                  | [762861205a](https://linux-hardware.org/?probe=762861205a) | Jul 26, 2023 |
| Lenovo    | ThinkPad T470p 20J6003DG... | [5693ac5e4c](https://linux-hardware.org/?probe=5693ac5e4c) | Jul 25, 2023 |
| ASUSTek   | VivoBook_ASUS Laptop E41... | [032db75736](https://linux-hardware.org/?probe=032db75736) | Jul 23, 2023 |
| Dell      | XPS 15 7590                 | [f5174240a7](https://linux-hardware.org/?probe=f5174240a7) | Jul 23, 2023 |
| Dell      | Inspiron 3476               | [eb12521a96](https://linux-hardware.org/?probe=eb12521a96) | Jul 23, 2023 |
| Lenovo    | IdeaPad 330-15ARR 81D2      | [c95c0b0730](https://linux-hardware.org/?probe=c95c0b0730) | Jul 22, 2023 |
| Lenovo    | ThinkPad T420 4236C92       | [a7b56f640a](https://linux-hardware.org/?probe=a7b56f640a) | Jul 18, 2023 |
| Lenovo    | ThinkPad T480 20L6S2CE00    | [e88c64ac3c](https://linux-hardware.org/?probe=e88c64ac3c) | Jul 16, 2023 |
| Lenovo    | ThinkPad T450 20BUS1BW01    | [db28c39c19](https://linux-hardware.org/?probe=db28c39c19) | Jul 14, 2023 |
| Lenovo    | ThinkPad T460s 20F90057M... | [698c4a8958](https://linux-hardware.org/?probe=698c4a8958) | Jul 14, 2023 |
| ASUSTek   | GL553VW                     | [9946c63986](https://linux-hardware.org/?probe=9946c63986) | Jul 12, 2023 |
| HP        | Laptop 15-dy2xxx            | [06f4243bee](https://linux-hardware.org/?probe=06f4243bee) | Jul 12, 2023 |
| Lenovo    | ThinkPad T450 20BUS1BW01    | [91d748c376](https://linux-hardware.org/?probe=91d748c376) | Jul 11, 2023 |
| Lenovo    | ThinkPad P72 20MCS0EU00     | [394bdbc596](https://linux-hardware.org/?probe=394bdbc596) | Jul 11, 2023 |
| HP        | OMEN Laptop 15-en0xxx       | [a5d9143c99](https://linux-hardware.org/?probe=a5d9143c99) | Jul 10, 2023 |
| Lenovo    | ThinkPad T480 20L6S2CE00    | [bbc78272ea](https://linux-hardware.org/?probe=bbc78272ea) | Jul 10, 2023 |
| Apple     | MacBook5,1                  | [b5ddf3381c](https://linux-hardware.org/?probe=b5ddf3381c) | Jul 10, 2023 |
| Lenovo    | ThinkPad T470p 20J6003DG... | [a7632f8c4b](https://linux-hardware.org/?probe=a7632f8c4b) | Jul 09, 2023 |
| HP        | ENVY Laptop 13-aq0xxx       | [8fcda3580f](https://linux-hardware.org/?probe=8fcda3580f) | Jul 08, 2023 |
| Alienware | 17                          | [b8b8032da9](https://linux-hardware.org/?probe=b8b8032da9) | Jul 08, 2023 |
| Lenovo    | ThinkPad T460s 20F90057M... | [cd45163d47](https://linux-hardware.org/?probe=cd45163d47) | Jul 08, 2023 |
| Dell      | Latitude 7480               | [4c07c7b04a](https://linux-hardware.org/?probe=4c07c7b04a) | Jul 07, 2023 |
| ASUSTek   | VivoBook_ASUSLaptop X712... | [b23ba37244](https://linux-hardware.org/?probe=b23ba37244) | Jul 06, 2023 |
| Apple     | MacBookPro8,1               | [d25474786c](https://linux-hardware.org/?probe=d25474786c) | Jul 05, 2023 |
| Acer      | TravelMate 8572T            | [67f4a2af7e](https://linux-hardware.org/?probe=67f4a2af7e) | Jul 05, 2023 |
| Timi      | Redmi Book Pro 15 2022      | [7fee63007e](https://linux-hardware.org/?probe=7fee63007e) | Jul 02, 2023 |
| Acer      | Aspire 7715Z                | [b288a09d6e](https://linux-hardware.org/?probe=b288a09d6e) | Jul 01, 2023 |
| Lenovo    | ThinkPad T460s 20F90057M... | [a78e2b4096](https://linux-hardware.org/?probe=a78e2b4096) | Jun 29, 2023 |
| Medion    | Akoya P7818                 | [cfe9ae82fa](https://linux-hardware.org/?probe=cfe9ae82fa) | Jun 29, 2023 |
| Lenovo    | IdeaPad 320-15IKB 80XL      | [b67f86bedc](https://linux-hardware.org/?probe=b67f86bedc) | Jun 21, 2023 |
| Lenovo    | Legion 5 Pro 16ARH7H 82R... | [5314aeb7e0](https://linux-hardware.org/?probe=5314aeb7e0) | Jun 21, 2023 |
| Acer      | Aspire E5-573G              | [277ddf45b4](https://linux-hardware.org/?probe=277ddf45b4) | Jun 08, 2023 |
| Acer      | Aspire E1-572               | [6dc6a9d6f5](https://linux-hardware.org/?probe=6dc6a9d6f5) | May 29, 2023 |
| Lenovo    | Legion 5 15ACH6H 82JU       | [ba6e80b2b7](https://linux-hardware.org/?probe=ba6e80b2b7) | Apr 02, 2023 |
| Lenovo    | Legion 5 15ACH6H 82JU       | [195ab3d907](https://linux-hardware.org/?probe=195ab3d907) | Apr 02, 2023 |
| Lenovo    | ThinkPad T440 20B7A0CYMH    | [428491a9d5](https://linux-hardware.org/?probe=428491a9d5) | Mar 29, 2023 |
| HP        | Victus by Laptop 16-e0xx... | [f8cd7d94b2](https://linux-hardware.org/?probe=f8cd7d94b2) | Mar 23, 2023 |
| Dell      | G5 5500                     | [f9b3b5d852](https://linux-hardware.org/?probe=f9b3b5d852) | Mar 19, 2023 |
| Lenovo    | IdeaPad S340-15IIL 81VW     | [90ef6ca2b7](https://linux-hardware.org/?probe=90ef6ca2b7) | Mar 18, 2023 |
| Lenovo    | IdeaPad S340-15IIL 81VW     | [b769745990](https://linux-hardware.org/?probe=b769745990) | Mar 18, 2023 |
| Dell      | Latitude 5420               | [318da7f6c0](https://linux-hardware.org/?probe=318da7f6c0) | Mar 18, 2023 |
| ASUSTek   | TUF Gaming FX505DY_FX505... | [d1bf2f0a8b](https://linux-hardware.org/?probe=d1bf2f0a8b) | Mar 12, 2023 |
| Apple     | MacBookPro11,3              | [bccc889328](https://linux-hardware.org/?probe=bccc889328) | Mar 10, 2023 |
| Lenovo    | ThinkPad P51 20HJS11Y00     | [0843074b87](https://linux-hardware.org/?probe=0843074b87) | Mar 09, 2023 |
| Lenovo    | IdeaPad S540-15IML D 81N... | [31e144de96](https://linux-hardware.org/?probe=31e144de96) | Mar 08, 2023 |
| Dell      | Inspiron 3505               | [324020ca8b](https://linux-hardware.org/?probe=324020ca8b) | Feb 24, 2023 |
| Lenovo    | ThinkPad X1 Carbon Gen 9... | [efd9f878d2](https://linux-hardware.org/?probe=efd9f878d2) | Feb 12, 2023 |
| Lenovo    | ThinkPad X1 Carbon Gen 9... | [3c2d4cf289](https://linux-hardware.org/?probe=3c2d4cf289) | Feb 02, 2023 |
| Lenovo    | ThinkPad X1 Carbon Gen 9... | [0de8121880](https://linux-hardware.org/?probe=0de8121880) | Feb 01, 2023 |
| Lenovo    | ThinkPad X1 Carbon Gen 9... | [f39ab69b74](https://linux-hardware.org/?probe=f39ab69b74) | Feb 01, 2023 |
| HP        | ProBook 6565b               | [0ef00f6bcc](https://linux-hardware.org/?probe=0ef00f6bcc) | Jan 25, 2023 |
| ASUSTek   | ASUS TUF Gaming F15 FX50... | [5661d09dd0](https://linux-hardware.org/?probe=5661d09dd0) | Jan 15, 2023 |
| HP        | 245 G7 Notebook PC          | [3997d98a9a](https://linux-hardware.org/?probe=3997d98a9a) | Jan 11, 2023 |
| HUAWEI    | BOM-WXX9                    | [21fcd391f1](https://linux-hardware.org/?probe=21fcd391f1) | Jan 08, 2023 |
| Lenovo    | IdeaPad 3 14IGL05 81WH      | [86cf09380a](https://linux-hardware.org/?probe=86cf09380a) | Jan 02, 2023 |
| ASUSTek   | X540LA                      | [65f5548781](https://linux-hardware.org/?probe=65f5548781) | Dec 30, 2022 |
| HUAWEI    | BOM-WXX9                    | [fb1d454bc2](https://linux-hardware.org/?probe=fb1d454bc2) | Dec 29, 2022 |
| HUAWEI    | BOM-WXX9                    | [62010fe267](https://linux-hardware.org/?probe=62010fe267) | Dec 29, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [6b34107dcf](https://linux-hardware.org/?probe=6b34107dcf) | Dec 21, 2022 |
| HP        | ZBook 15 G4                 | [669d7e74a2](https://linux-hardware.org/?probe=669d7e74a2) | Dec 19, 2022 |
| HP        | ZBook 15 G4                 | [91391127d1](https://linux-hardware.org/?probe=91391127d1) | Dec 18, 2022 |
| HP        | Pavilion Gaming Laptop 1... | [3111a63a09](https://linux-hardware.org/?probe=3111a63a09) | Dec 16, 2022 |
| Lenovo    | ThinkPad T490s 20NX001KM... | [49f30d3eee](https://linux-hardware.org/?probe=49f30d3eee) | Dec 06, 2022 |
| ASUSTek   | ROG Zephyrus G14 GA401II... | [16f086de33](https://linux-hardware.org/?probe=16f086de33) | Nov 25, 2022 |
| Medion    | P6816                       | [3aadacefe7](https://linux-hardware.org/?probe=3aadacefe7) | Nov 17, 2022 |
| Dell      | Latitude E6530              | [c87c9abe22](https://linux-hardware.org/?probe=c87c9abe22) | Nov 14, 2022 |
| Toshiba   | TECRA A11                   | [ba91b9d331](https://linux-hardware.org/?probe=ba91b9d331) | Nov 09, 2022 |
| Lenovo    | ThinkPad L450 20DT0000GE    | [1a925e0302](https://linux-hardware.org/?probe=1a925e0302) | Nov 06, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop X421... | [4cd7aa6350](https://linux-hardware.org/?probe=4cd7aa6350) | Nov 01, 2022 |
| ASUSTek   | K53SJ                       | [8c85e545f2](https://linux-hardware.org/?probe=8c85e545f2) | Oct 23, 2022 |
| ASUSTek   | ROG Strix G513IC_G513IC     | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| HP        | Laptop 15s-fq2xxx           | [69e60dfe44](https://linux-hardware.org/?probe=69e60dfe44) | Oct 07, 2022 |
| ASUSTek   | ZenBook UX433FN_UX433FN     | [a7764ad0f6](https://linux-hardware.org/?probe=a7764ad0f6) | Oct 03, 2022 |
| MSI       | Katana GF66 11UE            | [36b2cba297](https://linux-hardware.org/?probe=36b2cba297) | Sep 05, 2022 |
| Lenovo    | ThinkPad X1 Carbon Gen 9... | [b28edd3886](https://linux-hardware.org/?probe=b28edd3886) | Aug 26, 2022 |
| Lenovo    | ThinkPad X1 Carbon Gen 9... | [97770c5716](https://linux-hardware.org/?probe=97770c5716) | Aug 26, 2022 |
| Lenovo    | ThinkPad T430s 2356FG9      | [9a10c152af](https://linux-hardware.org/?probe=9a10c152af) | Aug 17, 2022 |
| Aquarius  | NS585                       | [db9cbd5688](https://linux-hardware.org/?probe=db9cbd5688) | Aug 17, 2022 |
| Lenovo    | IdeaPad S145-15AST 81N3     | [7c46c8f737](https://linux-hardware.org/?probe=7c46c8f737) | Jul 15, 2022 |
| ASUSTek   | G551JM                      | [599c7b9eae](https://linux-hardware.org/?probe=599c7b9eae) | Jul 14, 2022 |
| ASUSTek   | G551JM                      | [9f4536df1c](https://linux-hardware.org/?probe=9f4536df1c) | Jul 14, 2022 |
| ASUSTek   | UX303LN                     | [9ce42e1b01](https://linux-hardware.org/?probe=9ce42e1b01) | Jun 12, 2022 |
| Dell      | Inspiron 1545               | [ce0e24a314](https://linux-hardware.org/?probe=ce0e24a314) | May 28, 2022 |
| Lenovo    | IdeaPad 330-17IKB 81DM      | [53475a6004](https://linux-hardware.org/?probe=53475a6004) | May 24, 2022 |
| ASUSTek   | VivoBook_ASUSLaptop X350... | [80d32848bf](https://linux-hardware.org/?probe=80d32848bf) | May 21, 2022 |
| Dell      | Precision M3800             | [7b63874768](https://linux-hardware.org/?probe=7b63874768) | Apr 25, 2022 |
| Dell      | Precision M3800             | [fbabacd835](https://linux-hardware.org/?probe=fbabacd835) | Apr 24, 2022 |
| Lenovo    | ThinkPad X230 2325HR9       | [a9d9d3fbb2](https://linux-hardware.org/?probe=a9d9d3fbb2) | Apr 21, 2022 |
| Acer      | Aspire A515-54G             | [52b660d8fb](https://linux-hardware.org/?probe=52b660d8fb) | Apr 11, 2022 |
| Dell      | Precision M3800             | [1ef57b39a7](https://linux-hardware.org/?probe=1ef57b39a7) | Apr 10, 2022 |
| Dell      | Precision M3800             | [9fc15d1ae6](https://linux-hardware.org/?probe=9fc15d1ae6) | Mar 31, 2022 |
| MSI       | GF63 Thin 9SCX              | [4501fa1556](https://linux-hardware.org/?probe=4501fa1556) | Mar 25, 2022 |
| Dell      | Latitude 7480               | [bf00ec6a76](https://linux-hardware.org/?probe=bf00ec6a76) | Mar 23, 2022 |
| HUAWEI    | WRT-WX9                     | [70ec26bed6](https://linux-hardware.org/?probe=70ec26bed6) | Mar 22, 2022 |
| Dell      | Latitude 7480               | [faddba28a8](https://linux-hardware.org/?probe=faddba28a8) | Mar 19, 2022 |
| Apple     | MacBookAir6,2               | [b71110144d](https://linux-hardware.org/?probe=b71110144d) | Mar 19, 2022 |
| HP        | Laptop 15-da0xxx            | [bb9074ccdf](https://linux-hardware.org/?probe=bb9074ccdf) | Mar 18, 2022 |
| Lenovo    | IdeaPad 3 15IML05 81WR      | [918c951cd1](https://linux-hardware.org/?probe=918c951cd1) | Mar 12, 2022 |
| Lenovo    | IdeaPad S145-15IIL 81W8     | [e251c9f079](https://linux-hardware.org/?probe=e251c9f079) | Mar 11, 2022 |
| Dell      | Venue 11 Pro 7130 vPro      | [57b302b119](https://linux-hardware.org/?probe=57b302b119) | Mar 05, 2022 |
| Lenovo    | ThinkPad T460 20FMS1XX00    | [78e82c6674](https://linux-hardware.org/?probe=78e82c6674) | Feb 24, 2022 |
| Dell      | Latitude E6430              | [e1de4e80fe](https://linux-hardware.org/?probe=e1de4e80fe) | Feb 15, 2022 |
| Lenovo    | Legion 5 15ARH05H 82B1      | [a3c5f00a2a](https://linux-hardware.org/?probe=a3c5f00a2a) | Feb 10, 2022 |
| Lenovo    | Legion 5 15ARH05H 82B1      | [e53fb31614](https://linux-hardware.org/?probe=e53fb31614) | Feb 10, 2022 |
| Lenovo    | Legion Y740-15IRHg 81UH     | [b0cc5e0cbc](https://linux-hardware.org/?probe=b0cc5e0cbc) | Jan 29, 2022 |
| Acer      | Aspire A315-58G             | [cb4f253c1c](https://linux-hardware.org/?probe=cb4f253c1c) | Jan 28, 2022 |
| Dell      | Latitude E6520              | [ee96960cec](https://linux-hardware.org/?probe=ee96960cec) | Jan 25, 2022 |
| HP        | Laptop 15s-eq0xxx           | [0df160c245](https://linux-hardware.org/?probe=0df160c245) | Jan 21, 2022 |
| Lenovo    | Legion Y540-15IRH-PG0 81... | [3df8a1c560](https://linux-hardware.org/?probe=3df8a1c560) | Jan 08, 2022 |
| Dell      | Vostro 3590                 | [9e77a2584c](https://linux-hardware.org/?probe=9e77a2584c) | Dec 30, 2021 |
| ASUSTek   | ASUS EXPERTBOOK B9400CEA... | [78e3fbdf6a](https://linux-hardware.org/?probe=78e3fbdf6a) | Dec 28, 2021 |
| HP        | Notebook                    | [c14ea64659](https://linux-hardware.org/?probe=c14ea64659) | Dec 23, 2021 |
| ASUSTek   | X510UNR                     | [0733a05806](https://linux-hardware.org/?probe=0733a05806) | Dec 21, 2021 |
| ASUSTek   | ASUS EXPERTBOOK B9400CEA... | [b4425de4a6](https://linux-hardware.org/?probe=b4425de4a6) | Dec 17, 2021 |
| ASUSTek   | ASUS TUF Gaming F15 FX50... | [6f3bd18b3f](https://linux-hardware.org/?probe=6f3bd18b3f) | Dec 06, 2021 |
| Pegatron  | D15K                        | [eaeaad8d39](https://linux-hardware.org/?probe=eaeaad8d39) | Nov 29, 2021 |
| MSI       | GP73 Leopard 8RD            | [5bafb43f78](https://linux-hardware.org/?probe=5bafb43f78) | Nov 21, 2021 |
| Acer      | Aspire A315-58G             | [911895fcf2](https://linux-hardware.org/?probe=911895fcf2) | Nov 19, 2021 |
| Acer      | Aspire A315-58G             | [5748b3cd05](https://linux-hardware.org/?probe=5748b3cd05) | Nov 12, 2021 |
| Lenovo    | ThinkPad W530 24384CU       | [d18d3495e0](https://linux-hardware.org/?probe=d18d3495e0) | Nov 05, 2021 |
| Acer      | Aspire A315-58G             | [905fce5118](https://linux-hardware.org/?probe=905fce5118) | Oct 29, 2021 |
| HP        | ENVY Sleekbook 4            | [ebea056239](https://linux-hardware.org/?probe=ebea056239) | Oct 29, 2021 |
| ASUSTek   | VivoBook_ASUSLaptop X509... | [2a54689fb3](https://linux-hardware.org/?probe=2a54689fb3) | Oct 24, 2021 |
| ASUSTek   | VivoBook_ASUS Laptop E41... | [fb95cbb063](https://linux-hardware.org/?probe=fb95cbb063) | Oct 19, 2021 |
| Lenovo    | IdeaPad 5 15ITL05 82FG      | [6cd76dfa2a](https://linux-hardware.org/?probe=6cd76dfa2a) | Oct 13, 2021 |
| ASUSTek   | ASUS TUF Gaming F15 FX50... | [e3a8d1ca32](https://linux-hardware.org/?probe=e3a8d1ca32) | Oct 11, 2021 |
| ASUSTek   | ASUS TUF Gaming F15 FX50... | [c7c4a74bb8](https://linux-hardware.org/?probe=c7c4a74bb8) | Oct 11, 2021 |
| ASUSTek   | ASUS TUF Gaming F15 FX50... | [68865693c7](https://linux-hardware.org/?probe=68865693c7) | Oct 09, 2021 |
| Lenovo    | Y520-15IKBN 80WK            | [e804a59920](https://linux-hardware.org/?probe=e804a59920) | Oct 02, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Xero Rolling | 137       | 94.48%  |
| Xero         | 8         | 5.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Xero | 144       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version               | Notebooks | Percent |
|-----------------------|-----------|---------|
| 6.4.9-arch1-1         | 13        | 8.55%   |
| 6.4.3-arch1-2         | 12        | 7.89%   |
| 6.4.12-arch1-1        | 8         | 5.26%   |
| 6.4.2-arch1-1         | 6         | 3.95%   |
| 6.4.4-arch1-1         | 4         | 2.63%   |
| 6.4.1-arch2-1         | 4         | 2.63%   |
| 6.0.12-arch1-1        | 4         | 2.63%   |
| 5.16.15-arch1-1       | 4         | 2.63%   |
| 6.2.6-arch1-1         | 3         | 1.97%   |
| 6.1.1-arch1-1         | 3         | 1.97%   |
| 6.4.2-zen1-1-zen      | 2         | 1.32%   |
| 6.4.11-arch2-1        | 2         | 1.32%   |
| 6.4.10-arch1-1        | 2         | 1.32%   |
| 6.3.9-arch1-1         | 2         | 1.32%   |
| 6.3.8-arch1-1         | 2         | 1.32%   |
| 6.2.7-arch1-1         | 2         | 1.32%   |
| 6.0.7-arch1-1         | 2         | 1.32%   |
| 5.18.16-arch1-1       | 2         | 1.32%   |
| 5.18.11-arch1-1       | 2         | 1.32%   |
| 5.17.9-arch1-1        | 2         | 1.32%   |
| 5.16.8-arch1-1        | 2         | 1.32%   |
| 5.16.2-arch1-1        | 2         | 1.32%   |
| 5.16.1-arch1-1        | 2         | 1.32%   |
| 5.15.33-1-lts         | 2         | 1.32%   |
| 5.14.14-arch1-1       | 2         | 1.32%   |
| 6.5.1-arch1-1         | 1         | 0.66%   |
| 6.4.8-arch1-1         | 1         | 0.66%   |
| 6.4.7-zen1-1-zen      | 1         | 0.66%   |
| 6.4.7-arch1-3         | 1         | 0.66%   |
| 6.4.7-arch1-1         | 1         | 0.66%   |
| 6.4.6-arch1-1         | 1         | 0.66%   |
| 6.4.11-arch1-1        | 1         | 0.66%   |
| 6.4.10-zen2-1-zen     | 1         | 0.66%   |
| 6.4.10-2-cachyos-bore | 1         | 0.66%   |
| 6.4.1-arch1-1         | 1         | 0.66%   |
| 6.3.9-zen1-1-zen      | 1         | 0.66%   |
| 6.3.6-arch1-1         | 1         | 0.66%   |
| 6.3.4-arch1-1         | 1         | 0.66%   |
| 6.2.8-arch1-1         | 1         | 0.66%   |
| 6.2.2-arch2-1         | 1         | 0.66%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4.9   | 13        | 8.55%   |
| 6.4.3   | 12        | 7.89%   |
| 6.4.2   | 8         | 5.26%   |
| 6.4.12  | 8         | 5.26%   |
| 6.4.1   | 5         | 3.29%   |
| 6.4.4   | 4         | 2.63%   |
| 6.4.10  | 4         | 2.63%   |
| 6.0.12  | 4         | 2.63%   |
| 5.16.15 | 4         | 2.63%   |
| 6.4.7   | 3         | 1.97%   |
| 6.4.11  | 3         | 1.97%   |
| 6.3.9   | 3         | 1.97%   |
| 6.2.6   | 3         | 1.97%   |
| 6.1.1   | 3         | 1.97%   |
| 5.14.16 | 3         | 1.97%   |
| 5.14.14 | 3         | 1.97%   |
| 6.3.8   | 2         | 1.32%   |
| 6.2.7   | 2         | 1.32%   |
| 6.1.38  | 2         | 1.32%   |
| 6.0.8   | 2         | 1.32%   |
| 6.0.7   | 2         | 1.32%   |
| 5.18.16 | 2         | 1.32%   |
| 5.18.11 | 2         | 1.32%   |
| 5.17.9  | 2         | 1.32%   |
| 5.16.8  | 2         | 1.32%   |
| 5.16.2  | 2         | 1.32%   |
| 5.16.1  | 2         | 1.32%   |
| 5.15.33 | 2         | 1.32%   |
| 5.14.8  | 2         | 1.32%   |
| 6.5.1   | 1         | 0.66%   |
| 6.4.8   | 1         | 0.66%   |
| 6.4.6   | 1         | 0.66%   |
| 6.3.6   | 1         | 0.66%   |
| 6.3.4   | 1         | 0.66%   |
| 6.2.8   | 1         | 0.66%   |
| 6.2.2   | 1         | 0.66%   |
| 6.1.8   | 1         | 0.66%   |
| 6.1.7   | 1         | 0.66%   |
| 6.1.6   | 1         | 0.66%   |
| 6.1.46  | 1         | 0.66%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4     | 60        | 40.54%  |
| 5.16    | 14        | 9.46%   |
| 6.1     | 12        | 8.11%   |
| 6.0     | 12        | 8.11%   |
| 5.15    | 9         | 6.08%   |
| 5.14    | 9         | 6.08%   |
| 6.3     | 7         | 4.73%   |
| 6.2     | 7         | 4.73%   |
| 5.19    | 5         | 3.38%   |
| 5.18    | 5         | 3.38%   |
| 5.17    | 4         | 2.7%    |
| 5.10    | 3         | 2.03%   |
| 6.5     | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 144       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 133       | 91.1%   |
| XFCE     | 6         | 4.11%   |
| GNOME    | 3         | 2.05%   |
| Hyprland | 2         | 1.37%   |
| LeftWM   | 1         | 0.68%   |
| KDE      | 1         | 0.68%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 130       | 89.66%  |
| Wayland | 14        | 9.66%   |
| Unknown | 1         | 0.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 115       | 77.7%   |
| Unknown | 17        | 11.49%  |
| LightDM | 15        | 10.14%  |
| GDM     | 1         | 0.68%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 69        | 47.59%  |
| de_DE | 11        | 7.59%   |
| en_IN | 10        | 6.9%    |
| es_MX | 7         | 4.83%   |
| pt_BR | 5         | 3.45%   |
| pl_PL | 5         | 3.45%   |
| ru_RU | 4         | 2.76%   |
| C     | 4         | 2.76%   |
| it_IT | 3         | 2.07%   |
| fr_FR | 3         | 2.07%   |
| en_GB | 3         | 2.07%   |
| en_AU | 3         | 2.07%   |
| vi_VN | 2         | 1.38%   |
| zh_CN | 1         | 0.69%   |
| tr_TR | 1         | 0.69%   |
| nl_NL | 1         | 0.69%   |
| nb_NO | 1         | 0.69%   |
| hu_HU | 1         | 0.69%   |
| es_VE | 1         | 0.69%   |
| es_SV | 1         | 0.69%   |
| es_CL | 1         | 0.69%   |
| es_AR | 1         | 0.69%   |
| en_ZA | 1         | 0.69%   |
| en_PH | 1         | 0.69%   |
| en_DK | 1         | 0.69%   |
| en_CA | 1         | 0.69%   |
| en_AG | 1         | 0.69%   |
| da_DK | 1         | 0.69%   |
| ca_ES | 1         | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 109       | 74.66%  |
| BIOS | 37        | 25.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 53        | 36.55%  |
| Btrfs   | 50        | 34.48%  |
| Ext4    | 38        | 26.21%  |
| Overlay | 4         | 2.76%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 113       | 77.4%   |
| Unknown | 17        | 11.64%  |
| MBR     | 16        | 10.96%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 120       | 81.63%  |
| Yes       | 27        | 18.37%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 62.07%  |
| Yes       | 55        | 37.93%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 39        | 27.08%  |
| ASUSTek Computer | 24        | 16.67%  |
| Dell             | 23        | 15.97%  |
| Hewlett-Packard  | 20        | 13.89%  |
| Acer             | 11        | 7.64%   |
| Apple            | 6         | 4.17%   |
| HUAWEI           | 4         | 2.78%   |
| MSI              | 3         | 2.08%   |
| Timi             | 2         | 1.39%   |
| Medion           | 2         | 1.39%   |
| WEIGO            | 1         | 0.69%   |
| VIT              | 1         | 0.69%   |
| Toshiba          | 1         | 0.69%   |
| Pegatron         | 1         | 0.69%   |
| LNV              | 1         | 0.69%   |
| HONOR            | 1         | 0.69%   |
| Google           | 1         | 0.69%   |
| Fujitsu          | 1         | 0.69%   |
| Aquarius         | 1         | 0.69%   |
| Alienware        | 1         | 0.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 2.08%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1        | 2         | 1.39%   |
| Dell Latitude E6520                        | 2         | 1.39%   |
| Dell Latitude 7480                         | 2         | 1.39%   |
| Dell Latitude 5420                         | 2         | 1.39%   |
| WEIGO CDA-141AU                            | 1         | 0.69%   |
| VIT P2402                                  | 1         | 0.69%   |
| Toshiba TECRA A11                          | 1         | 0.69%   |
| Timi Redmi Book Pro 15 2022                | 1         | 0.69%   |
| Timi Redmi Book Pro 14 2022                | 1         | 0.69%   |
| Pegatron D15K                              | 1         | 0.69%   |
| MSI Katana GF66 11UE                       | 1         | 0.69%   |
| MSI GP73 Leopard 8RD                       | 1         | 0.69%   |
| MSI GF63 Thin 9SCX                         | 1         | 0.69%   |
| Medion P6816                               | 1         | 0.69%   |
| Medion Akoya P7818                         | 1         | 0.69%   |
| LNV L40-70                                 | 1         | 0.69%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.69%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.69%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 0.69%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 0.69%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS0WK00   | 1         | 0.69%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 0.69%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 0.69%   |
| Lenovo ThinkPad T480 20L6S2CE00            | 1         | 0.69%   |
| Lenovo ThinkPad T470p 20J6003DGE           | 1         | 0.69%   |
| Lenovo ThinkPad T460s 20F90057MS           | 1         | 0.69%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 0.69%   |
| Lenovo ThinkPad T450 20BUS1BW01            | 1         | 0.69%   |
| Lenovo ThinkPad T440 20B7A0CYMH            | 1         | 0.69%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 0.69%   |
| Lenovo ThinkPad T420 4236C92               | 1         | 0.69%   |
| Lenovo ThinkPad P72 20MCS0EU00             | 1         | 0.69%   |
| Lenovo ThinkPad P51 20HJS11Y00             | 1         | 0.69%   |
| Lenovo ThinkPad P50 20EQS4XN00             | 1         | 0.69%   |
| Lenovo ThinkPad L450 20DT0000GE            | 1         | 0.69%   |
| Lenovo Rev B 82KU                          | 1         | 0.69%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 0.69%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 0.69%   |
| Lenovo Legion 5 Pro 16ARH7H 82RG           | 1         | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 17        | 11.81%  |
| Lenovo IdeaPad     | 14        | 9.72%   |
| Acer Aspire        | 10        | 6.94%   |
| HP Laptop          | 9         | 6.25%   |
| Dell Latitude      | 8         | 5.56%   |
| ASUS VivoBook      | 8         | 5.56%   |
| Dell Inspiron      | 6         | 4.17%   |
| Lenovo Legion      | 5         | 3.47%   |
| ASUS ASUS          | 4         | 2.78%   |
| Dell Precision     | 3         | 2.08%   |
| ASUS ROG           | 3         | 2.08%   |
| Timi Redmi         | 2         | 1.39%   |
| HP ProBook         | 2         | 1.39%   |
| HP ENVY            | 2         | 1.39%   |
| Apple MacBookPro11 | 2         | 1.39%   |
| WEIGO CDA-141AU    | 1         | 0.69%   |
| VIT P2402          | 1         | 0.69%   |
| Toshiba TECRA      | 1         | 0.69%   |
| Pegatron D15K      | 1         | 0.69%   |
| MSI Katana         | 1         | 0.69%   |
| MSI GP73           | 1         | 0.69%   |
| MSI GF63           | 1         | 0.69%   |
| Medion P6816       | 1         | 0.69%   |
| Medion Akoya       | 1         | 0.69%   |
| LNV L40-70         | 1         | 0.69%   |
| Lenovo Yoga        | 1         | 0.69%   |
| Lenovo Y520-15IKBN | 1         | 0.69%   |
| Lenovo Rev         | 1         | 0.69%   |
| HUAWEI WRT-WX9     | 1         | 0.69%   |
| HUAWEI HVY-WXX9    | 1         | 0.69%   |
| HUAWEI HN-WX9X     | 1         | 0.69%   |
| HUAWEI BOM-WXX9    | 1         | 0.69%   |
| HONOR BBR-WAX9     | 1         | 0.69%   |
| HP ZBook           | 1         | 0.69%   |
| HP Victus          | 1         | 0.69%   |
| HP Pavilion        | 1         | 0.69%   |
| HP OMEN            | 1         | 0.69%   |
| HP Notebook        | 1         | 0.69%   |
| HP 255             | 1         | 0.69%   |
| HP 245             | 1         | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 24        | 16.67%  |
| 2020 | 21        | 14.58%  |
| 2021 | 20        | 13.89%  |
| 2017 | 10        | 6.94%   |
| 2018 | 9         | 6.25%   |
| 2013 | 9         | 6.25%   |
| 2012 | 9         | 6.25%   |
| 2022 | 8         | 5.56%   |
| 2015 | 8         | 5.56%   |
| 2014 | 7         | 4.86%   |
| 2011 | 6         | 4.17%   |
| 2016 | 4         | 2.78%   |
| 2010 | 4         | 2.78%   |
| 2023 | 2         | 1.39%   |
| 2009 | 2         | 1.39%   |
| 2008 | 1         | 0.69%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 144       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 144       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 143       | 99.31%  |
| Yes  | 1         | 0.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 53        | 36.81%  |
| 8.01-16.0   | 31        | 21.53%  |
| 16.01-24.0  | 29        | 20.14%  |
| 3.01-4.0    | 19        | 13.19%  |
| 32.01-64.0  | 7         | 4.86%   |
| 24.01-32.0  | 3         | 2.08%   |
| 64.01-256.0 | 2         | 1.39%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 52        | 35.14%  |
| 2.01-3.0   | 45        | 30.41%  |
| 4.01-8.0   | 25        | 16.89%  |
| 3.01-4.0   | 20        | 13.51%  |
| 8.01-16.0  | 3         | 2.03%   |
| 0.51-1.0   | 2         | 1.35%   |
| 16.01-24.0 | 1         | 0.68%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 92        | 63.45%  |
| 2      | 46        | 31.72%  |
| 3      | 6         | 4.14%   |
| 4      | 1         | 0.69%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 80.56%  |
| Yes       | 28        | 19.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 71.53%  |
| No        | 41        | 28.47%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 141       | 97.92%  |
| No        | 3         | 2.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 129       | 89.58%  |
| No        | 15        | 10.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| USA                   | 23        | 15.86%  |
| Germany               | 15        | 10.34%  |
| India                 | 13        | 8.97%   |
| France                | 6         | 4.14%   |
| Turkey                | 5         | 3.45%   |
| Russia                | 5         | 3.45%   |
| Poland                | 5         | 3.45%   |
| Italy                 | 5         | 3.45%   |
| Mexico                | 4         | 2.76%   |
| Brazil                | 4         | 2.76%   |
| Vietnam               | 3         | 2.07%   |
| Norway                | 3         | 2.07%   |
| Netherlands           | 3         | 2.07%   |
| Chile                 | 3         | 2.07%   |
| Canada                | 3         | 2.07%   |
| Australia             | 3         | 2.07%   |
| Romania               | 2         | 1.38%   |
| Pakistan              | 2         | 1.38%   |
| Morocco               | 2         | 1.38%   |
| Indonesia             | 2         | 1.38%   |
| Hungary               | 2         | 1.38%   |
| Greece                | 2         | 1.38%   |
| Egypt                 | 2         | 1.38%   |
| Denmark               | 2         | 1.38%   |
| Zambia                | 1         | 0.69%   |
| Venezuela             | 1         | 0.69%   |
| UK                    | 1         | 0.69%   |
| Tunisia               | 1         | 0.69%   |
| Togo                  | 1         | 0.69%   |
| Thailand              | 1         | 0.69%   |
| Switzerland           | 1         | 0.69%   |
| Sweden                | 1         | 0.69%   |
| Spain                 | 1         | 0.69%   |
| South Africa          | 1         | 0.69%   |
| Portugal              | 1         | 0.69%   |
| Philippines           | 1         | 0.69%   |
| Palestinian Territory | 1         | 0.69%   |
| Nepal                 | 1         | 0.69%   |
| Mongolia              | 1         | 0.69%   |
| Malaysia              | 1         | 0.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Notebooks | Percent |
|--------------|-----------|---------|
| Longmont     | 3         | 2.05%   |
| Istanbul     | 3         | 2.05%   |
| Tangerang    | 2         | 1.37%   |
| Stuttgart    | 2         | 1.37%   |
| Pune         | 2         | 1.37%   |
| Norfolk      | 2         | 1.37%   |
| Madurai      | 2         | 1.37%   |
| Hamburg      | 2         | 1.37%   |
| Chennai      | 2         | 1.37%   |
| Cairo        | 2         | 1.37%   |
| Zurich       | 1         | 0.68%   |
| Zenica       | 1         | 0.68%   |
| Zeeland      | 1         | 0.68%   |
| Zalaegerszeg | 1         | 0.68%   |
| Zabrze       | 1         | 0.68%   |
| Wolfsburg    | 1         | 0.68%   |
| Wasilla      | 1         | 0.68%   |
| Warsaw       | 1         | 0.68%   |
| Viburnum     | 1         | 0.68%   |
| Vejle        | 1         | 0.68%   |
| Vechelde     | 1         | 0.68%   |
| Valladolid   | 1         | 0.68%   |
| Ulan Bator   | 1         | 0.68%   |
| Ufa          | 1         | 0.68%   |
| Ubatuba      | 1         | 0.68%   |
| Toronto      | 1         | 0.68%   |
| Toluca       | 1         | 0.68%   |
| Tirana       | 1         | 0.68%   |
| Tigre        | 1         | 0.68%   |
| Tavarede     | 1         | 0.68%   |
| Taranto      | 1         | 0.68%   |
| Tampere      | 1         | 0.68%   |
| Tallinn      | 1         | 0.68%   |
| Stupino      | 1         | 0.68%   |
| Stockholm    | 1         | 0.68%   |
| Stavropol    | 1         | 0.68%   |
| Stagno       | 1         | 0.68%   |
| Shelburne    | 1         | 0.68%   |
| Settat       | 1         | 0.68%   |
| Seattle      | 1         | 0.68%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 37        | 42     | 18.88%  |
| Seagate                      | 21        | 24     | 10.71%  |
| Toshiba                      | 15        | 16     | 7.65%   |
| WDC                          | 13        | 14     | 6.63%   |
| Sandisk                      | 12        | 13     | 6.12%   |
| Kingston                     | 12        | 13     | 6.12%   |
| Intel                        | 10        | 13     | 5.1%    |
| SK hynix                     | 8         | 8      | 4.08%   |
| Micron Technology            | 6         | 7      | 3.06%   |
| Unknown                      | 5         | 5      | 2.55%   |
| KIOXIA                       | 5         | 6      | 2.55%   |
| HGST                         | 4         | 4      | 2.04%   |
| Crucial                      | 4         | 4      | 2.04%   |
| Transcend                    | 3         | 3      | 1.53%   |
| Apple                        | 3         | 3      | 1.53%   |
| Apacer                       | 3         | 3      | 1.53%   |
| Shenzhen Longsys Electronics | 2         | 2      | 1.02%   |
| SAGE                         | 2         | 2      | 1.02%   |
| OWC                          | 2         | 2      | 1.02%   |
| LITEONIT                     | 2         | 2      | 1.02%   |
| Kingston Technology Company  | 2         | 2      | 1.02%   |
| Hitachi                      | 2         | 2      | 1.02%   |
| A-DATA Technology            | 2         | 2      | 1.02%   |
| Vaseky                       | 1         | 1      | 0.51%   |
| SandWind                     | 1         | 1      | 0.51%   |
| S3+                          | 1         | 1      | 0.51%   |
| Realtek Semiconductor        | 1         | 1      | 0.51%   |
| PNY                          | 1         | 1      | 0.51%   |
| Plextor                      | 1         | 1      | 0.51%   |
| Phison Electronics           | 1         | 1      | 0.51%   |
| Phison                       | 1         | 1      | 0.51%   |
| OSCOO                        | 1         | 1      | 0.51%   |
| Micron/Crucial Technology    | 1         | 1      | 0.51%   |
| LITEON                       | 1         | 1      | 0.51%   |
| KingFast                     | 1         | 1      | 0.51%   |
| JetFlash                     | 1         | 1      | 0.51%   |
| Intenso                      | 1         | 1      | 0.51%   |
| Inateck                      | 1         | 1      | 0.51%   |
| GOODRAM                      | 1         | 1      | 0.51%   |
| Emtec                        | 1         | 1      | 0.51%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                 | Notebooks | Percent |
|-------------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                                | 6         | 2.97%   |
| Seagate ST1000LM035-1RK172 1TB                        | 4         | 1.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB   | 4         | 1.98%   |
| WDC WD10SPZX-24Z10 1TB                                | 3         | 1.49%   |
| Seagate ST1000LM049-2GH172 1TB                        | 3         | 1.49%   |
| Seagate One Touch HDD 5TB                             | 3         | 1.49%   |
| Kingston SA400S37480G 480GB SSD                       | 3         | 1.49%   |
| Kingston SA400S37240G 240GB SSD                       | 3         | 1.49%   |
| Unknown MMC Card  64GB                                | 2         | 0.99%   |
| Toshiba XG6 NVMe SSD Controller 1024GB                | 2         | 0.99%   |
| Seagate ST750LM022 HN-M750MBB 752GB                   | 2         | 0.99%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1024GB     | 2         | 0.99%   |
| Samsung SSD 980 1TB                                   | 2         | 0.99%   |
| Samsung SSD 860 EVO 250GB                             | 2         | 0.99%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB  | 2         | 0.99%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1024GB | 2         | 0.99%   |
| Samsung MZVLQ512HBLU-00BH1 512GB                      | 2         | 0.99%   |
| SAGE 3639S 500GB                                      | 2         | 0.99%   |
| OWC Mercury Electra 3G SSD                            | 2         | 0.99%   |
| Micron 2210_MTFDHBA512QFD 512GB                       | 2         | 0.99%   |
| Micron 2200V_MTFDHBA512TCK 512GB                      | 2         | 0.99%   |
| Kingston SA400S37960G 960GB SSD                       | 2         | 0.99%   |
| Intel HBRPEKNX0101AHO 16GB                            | 2         | 0.99%   |
| Intel HBRPEKNX0101AH 256GB                            | 2         | 0.99%   |
| Apacer AS350 256GB SSD                                | 2         | 0.99%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                      | 1         | 0.5%    |
| WDC WDS100T1X0E-00AFY0 1TB                            | 1         | 0.5%    |
| WDC WDBNCE0010PNC 1TB SSD                             | 1         | 0.5%    |
| WDC WD3200BEVT-22ZCT0 320GB                           | 1         | 0.5%    |
| WDC WD10SPZX-60Z10T0 1TB                              | 1         | 0.5%    |
| WDC WD10JPVX-60JC3T0 1TB                              | 1         | 0.5%    |
| WDC PC SN720 SDAPNTW-512G-1027 512GB                  | 1         | 0.5%    |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB                  | 1         | 0.5%    |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                  | 1         | 0.5%    |
| WDC PC SN520 SDAPMUW-256G-1101 256GB                  | 1         | 0.5%    |
| Vaseky V800/256G 256GB SSD                            | 1         | 0.5%    |
| Unknown SD/MMC/MS PRO 1GB                             | 1         | 0.5%    |
| Unknown MMC Card  128GB                               | 1         | 0.5%    |
| Unknown G1J38E  64GB                                  | 1         | 0.5%    |
| Transcend TS64GSSD370S 64GB                           | 1         | 0.5%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 22     | 43.48%  |
| Toshiba             | 10        | 10     | 21.74%  |
| WDC                 | 6         | 6      | 13.04%  |
| HGST                | 4         | 4      | 8.7%    |
| SAGE                | 2         | 2      | 4.35%   |
| Hitachi             | 2         | 2      | 4.35%   |
| Unknown             | 1         | 1      | 2.17%   |
| Samsung Electronics | 1         | 1      | 2.17%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 16     | 22.58%  |
| Kingston            | 8         | 8      | 12.9%   |
| SanDisk             | 4         | 4      | 6.45%   |
| Crucial             | 4         | 4      | 6.45%   |
| Transcend           | 3         | 3      | 4.84%   |
| Apple               | 3         | 3      | 4.84%   |
| Apacer              | 3         | 3      | 4.84%   |
| WDC                 | 2         | 2      | 3.23%   |
| OWC                 | 2         | 2      | 3.23%   |
| LITEONIT            | 2         | 2      | 3.23%   |
| Intel               | 2         | 2      | 3.23%   |
| Vaseky              | 1         | 1      | 1.61%   |
| SK hynix            | 1         | 1      | 1.61%   |
| S3+                 | 1         | 1      | 1.61%   |
| PNY                 | 1         | 1      | 1.61%   |
| Plextor             | 1         | 1      | 1.61%   |
| OSCOO               | 1         | 1      | 1.61%   |
| Micron Technology   | 1         | 1      | 1.61%   |
| LITEON              | 1         | 1      | 1.61%   |
| KingFast            | 1         | 1      | 1.61%   |
| Intenso             | 1         | 1      | 1.61%   |
| GOODRAM             | 1         | 1      | 1.61%   |
| Emtec               | 1         | 1      | 1.61%   |
| China               | 1         | 1      | 1.61%   |
| Biostar             | 1         | 1      | 1.61%   |
| A-DATA Technology   | 1         | 1      | 1.61%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 75        | 93     | 41.9%   |
| SSD     | 53        | 64     | 29.61%  |
| HDD     | 43        | 48     | 24.02%  |
| MMC     | 5         | 5      | 2.79%   |
| Unknown | 3         | 3      | 1.68%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 82        | 103    | 47.13%  |
| NVMe | 75        | 92     | 43.1%   |
| SAS  | 12        | 13     | 6.9%    |
| MMC  | 5         | 5      | 2.87%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 64     | 54.08%  |
| 0.51-1.0   | 41        | 44     | 41.84%  |
| 4.01-10.0  | 3         | 3      | 3.06%   |
| 1.01-2.0   | 1         | 1      | 1.02%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 35        | 23.97%  |
| 251-500        | 32        | 21.92%  |
| 501-1000       | 18        | 12.33%  |
| 1001-2000      | 16        | 10.96%  |
| More than 3000 | 15        | 10.27%  |
| 51-100         | 9         | 6.16%   |
| Unknown        | 9         | 6.16%   |
| 21-50          | 5         | 3.42%   |
| 2001-3000      | 4         | 2.74%   |
| 1-20           | 3         | 2.05%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 45        | 30.61%  |
| 21-50          | 30        | 20.41%  |
| 51-100         | 24        | 16.33%  |
| 101-250        | 20        | 13.61%  |
| Unknown        | 9         | 6.12%   |
| 251-500        | 8         | 5.44%   |
| 2001-3000      | 4         | 2.72%   |
| 501-1000       | 4         | 2.72%   |
| More than 3000 | 2         | 1.36%   |
| 1001-2000      | 1         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                            | Notebooks | Drives | Percent |
|------------------------------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB                                           | 1         | 1      | 4.17%   |
| WDC WD10JPVX-60JC3T0 1TB                                         | 1         | 1      | 4.17%   |
| Toshiba MQ04ABF100 1TB                                           | 1         | 1      | 4.17%   |
| Toshiba MQ01ABF050M 500GB                                        | 1         | 1      | 4.17%   |
| Toshiba MQ01ABF050 500GB                                         | 1         | 1      | 4.17%   |
| Toshiba MK3261GSY 320GB                                          | 1         | 1      | 4.17%   |
| Toshiba MK2555GSX 250GB                                          | 1         | 1      | 4.17%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD                            | 1         | 1      | 4.17%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                             | 1         | 1      | 4.17%   |
| Seagate ST9500325AS 500GB                                        | 1         | 1      | 4.17%   |
| Seagate ST9320423AS 320GB                                        | 1         | 1      | 4.17%   |
| Seagate ST500LT012-1DG142 500GB                                  | 1         | 1      | 4.17%   |
| Seagate ST500LM000-SSHD-8GB                                      | 1         | 1      | 4.17%   |
| Seagate ST1000LM049-2GH172 1TB                                   | 1         | 1      | 4.17%   |
| Seagate ST1000LM048-2E7172 1TB                                   | 1         | 1      | 4.17%   |
| Seagate ST1000LM035-1RK172 1TB                                   | 1         | 1      | 4.17%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 1024GB | 1         | 1      | 4.17%   |
| Samsung Electronics HM100UI 1TB                                  | 1         | 1      | 4.17%   |
| SAGE 3639S 500GB                                                 | 1         | 1      | 4.17%   |
| LITEONIT DMT-80M6M-11 mSATA 80GB SSD                             | 1         | 1      | 4.17%   |
| Hitachi HTS547575A9E384 752GB                                    | 1         | 1      | 4.17%   |
| HGST HTS725032A7E630 320GB                                       | 1         | 1      | 4.17%   |
| HGST HTS721010A9E630 1TB                                         | 1         | 1      | 4.17%   |
| Crucial CT480BX200SSD1 480GB                                     | 1         | 1      | 4.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 29.17%  |
| Toshiba             | 5         | 5      | 20.83%  |
| WDC                 | 2         | 2      | 8.33%   |
| SK hynix            | 2         | 2      | 8.33%   |
| Samsung Electronics | 2         | 2      | 8.33%   |
| HGST                | 2         | 2      | 8.33%   |
| SAGE                | 1         | 1      | 4.17%   |
| LITEONIT            | 1         | 1      | 4.17%   |
| Hitachi             | 1         | 1      | 4.17%   |
| Crucial             | 1         | 1      | 4.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 7         | 7      | 36.84%  |
| Toshiba             | 5         | 5      | 26.32%  |
| WDC                 | 2         | 2      | 10.53%  |
| HGST                | 2         | 2      | 10.53%  |
| Samsung Electronics | 1         | 1      | 5.26%   |
| SAGE                | 1         | 1      | 5.26%   |
| Hitachi             | 1         | 1      | 5.26%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 19        | 19     | 79.17%  |
| SSD  | 3         | 3      | 12.5%   |
| NVMe | 2         | 2      | 8.33%   |

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
| Works    | 111       | 149    | 68.52%  |
| Detected | 28        | 40     | 17.28%  |
| Malfunc  | 23        | 24     | 14.2%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 102       | 53.13%  |
| Samsung Electronics          | 24        | 12.5%   |
| AMD                          | 14        | 7.29%   |
| SanDisk                      | 12        | 6.25%   |
| SK hynix                     | 7         | 3.65%   |
| Kingston Technology Company  | 6         | 3.13%   |
| Toshiba America Info Systems | 5         | 2.6%    |
| Micron Technology            | 5         | 2.6%    |
| KIOXIA                       | 5         | 2.6%    |
| Shenzhen Longsys Electronics | 2         | 1.04%   |
| Phison Electronics           | 2         | 1.04%   |
| Nvidia                       | 2         | 1.04%   |
| ADATA Technology             | 2         | 1.04%   |
| Seagate Technology           | 1         | 0.52%   |
| Realtek Semiconductor        | 1         | 0.52%   |
| Micron/Crucial Technology    | 1         | 0.52%   |
| Marvell Technology Group     | 1         | 0.52%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Volume Management Device NVMe RAID Controller                            | 14        | 6.83%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 14        | 6.83%   |
| Samsung NVMe SSD Controller 980                                                | 11        | 5.37%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 10        | 4.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 4.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 4.88%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 4.39%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 3.9%    |
| Intel Tiger Lake-LP SATA Controller                                            | 7         | 3.41%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 2.93%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 2.44%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 5         | 2.44%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 2.44%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 1.95%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.95%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.46%   |
| Micron 2200S NVMe SSD [Cassandra]                                              | 3         | 1.46%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 1.46%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 3         | 1.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.46%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.98%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.98%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.98%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.98%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 2         | 0.98%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 0.98%   |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 0.98%   |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 2         | 0.98%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 0.98%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.98%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 0.98%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 0.98%   |
| Intel SSD 660P Series                                                          | 2         | 0.98%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 0.98%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.98%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 0.98%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.98%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 99        | 49.5%   |
| NVMe | 75        | 37.5%   |
| RAID | 26        | 13%     |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 118       | 81.94%  |
| AMD    | 26        | 18.06%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 6         | 4.17%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 5         | 3.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 2.78%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 2.78%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 2.78%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 4         | 2.78%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 2.08%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 3         | 2.08%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 2.08%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 2.08%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 2.08%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 2.08%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 2.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.08%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 2.08%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 1.39%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 2         | 1.39%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.39%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 1.39%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 2         | 1.39%   |
| Intel 11th Gen Core i5-11320H @ 3.20GHz       | 2         | 1.39%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 1.39%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.39%   |
| AMD Ryzen 5 5625U with Radeon Graphics        | 2         | 1.39%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.39%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 2         | 1.39%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.39%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.39%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.39%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.69%   |
| Intel Xeon CPU E3-1505M v5 @ 2.80GHz          | 1         | 0.69%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.69%   |
| Intel Pentium Silver N6000 @ 1.10GHz          | 1         | 0.69%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.69%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 0.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.69%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.69%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.69%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 39        | 27.08%  |
| Intel Core i7           | 34        | 23.61%  |
| Other                   | 22        | 15.28%  |
| AMD Ryzen 5             | 15        | 10.42%  |
| Intel Core i3           | 12        | 8.33%   |
| AMD Ryzen 7             | 5         | 3.47%   |
| Intel Core 2 Duo        | 3         | 2.08%   |
| Intel Celeron           | 3         | 2.08%   |
| AMD Ryzen 3             | 3         | 2.08%   |
| Intel Xeon              | 2         | 1.39%   |
| Intel Pentium Silver    | 1         | 0.69%   |
| Intel Pentium Dual-Core | 1         | 0.69%   |
| Intel Pentium           | 1         | 0.69%   |
| AMD Athlon              | 1         | 0.69%   |
| AMD A6                  | 1         | 0.69%   |
| AMD A4                  | 1         | 0.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 60        | 41.67%  |
| 4      | 57        | 39.58%  |
| 6      | 18        | 12.5%   |
| 8      | 7         | 4.86%   |
| 14     | 1         | 0.69%   |
| 10     | 1         | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 144       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 132       | 91.03%  |
| 1      | 13        | 8.97%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 144       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 54.11%  |
| 0x806c1    | 7         | 4.79%   |
| 0x806ec    | 6         | 4.11%   |
| 0x08108109 | 5         | 3.42%   |
| 0x906ea    | 4         | 2.74%   |
| 0x306a9    | 4         | 2.74%   |
| 0x906e9    | 3         | 2.05%   |
| 0x806e9    | 3         | 2.05%   |
| 0x206a7    | 3         | 2.05%   |
| 0x08608103 | 3         | 2.05%   |
| 0x806eb    | 2         | 1.37%   |
| 0x706a8    | 2         | 1.37%   |
| 0x40651    | 2         | 1.37%   |
| 0x08108102 | 2         | 1.37%   |
| 0xa0652    | 1         | 0.68%   |
| 0x906ed    | 1         | 0.68%   |
| 0x906eb    | 1         | 0.68%   |
| 0x906a3    | 1         | 0.68%   |
| 0x806d1    | 1         | 0.68%   |
| 0x706e5    | 1         | 0.68%   |
| 0x506e3    | 1         | 0.68%   |
| 0x406e3    | 1         | 0.68%   |
| 0x40661    | 1         | 0.68%   |
| 0x306d4    | 1         | 0.68%   |
| 0x306c3    | 1         | 0.68%   |
| 0x20652    | 1         | 0.68%   |
| 0x1067a    | 1         | 0.68%   |
| 0x0a50000d | 1         | 0.68%   |
| 0x0a404102 | 1         | 0.68%   |
| 0x0a404101 | 1         | 0.68%   |
| 0x08608104 | 1         | 0.68%   |
| 0x08600106 | 1         | 0.68%   |
| 0x0810100b | 1         | 0.68%   |
| 0x06006705 | 1         | 0.68%   |
| 0x03000027 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 24.31%  |
| TigerLake        | 16        | 11.11%  |
| Haswell          | 13        | 9.03%   |
| Broadwell        | 10        | 6.94%   |
| Zen+             | 8         | 5.56%   |
| IvyBridge        | 8         | 5.56%   |
| IceLake          | 8         | 5.56%   |
| SandyBridge      | 7         | 4.86%   |
| Unknown          | 6         | 4.17%   |
| Zen 2            | 5         | 3.47%   |
| Zen 3            | 4         | 2.78%   |
| Skylake          | 4         | 2.78%   |
| Penryn           | 4         | 2.78%   |
| Westmere         | 3         | 2.08%   |
| Goldmont plus    | 3         | 2.08%   |
| CometLake        | 3         | 2.08%   |
| Alderlake Hybrid | 3         | 2.08%   |
| Zen              | 1         | 0.69%   |
| Tremont          | 1         | 0.69%   |
| K10 Llano        | 1         | 0.69%   |
| Excavator        | 1         | 0.69%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 115       | 56.93%  |
| Nvidia | 58        | 28.71%  |
| AMD    | 29        | 14.36%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 10        | 4.93%   |
| Intel HD Graphics 5500                                                    | 8         | 3.94%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 8         | 3.94%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 7         | 3.45%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 7         | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 7         | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 6         | 2.96%   |
| Intel UHD Graphics 620                                                    | 6         | 2.96%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 6         | 2.96%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 2.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 5         | 2.46%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 5         | 2.46%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 5         | 2.46%   |
| Intel HD Graphics 620                                                     | 5         | 2.46%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 2.46%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 4         | 1.97%   |
| Intel HD Graphics 630                                                     | 4         | 1.97%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 4         | 1.97%   |
| AMD Renoir                                                                | 4         | 1.97%   |
| AMD Lucienne                                                              | 4         | 1.97%   |
| Nvidia GP108M [GeForce MX150]                                             | 3         | 1.48%   |
| Nvidia GM108M [GeForce 940MX]                                             | 3         | 1.48%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 1.48%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.48%   |
| Intel Core Processor Integrated Graphics Controller                       | 3         | 1.48%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 0.99%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 0.99%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 0.99%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 0.99%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 0.99%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 0.99%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 0.99%   |
| AMD Rembrandt [Radeon 680M]                                               | 2         | 0.99%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]          | 2         | 0.99%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 0.99%   |
| AMD Barcelo                                                               | 2         | 0.99%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.49%   |
| Nvidia TU117M                                                             | 1         | 0.49%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.49%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.49%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 62        | 43.06%  |
| Intel + Nvidia | 47        | 32.64%  |
| 1 x AMD        | 17        | 11.81%  |
| AMD + Nvidia   | 7         | 4.86%   |
| 1 x Nvidia     | 4         | 2.78%   |
| Intel + AMD    | 4         | 2.78%   |
| 2 x Intel      | 2         | 1.39%   |
| 2 x AMD        | 1         | 0.69%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 113       | 77.4%   |
| Proprietary | 33        | 22.6%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 103       | 71.03%  |
| 1.01-2.0   | 17        | 11.72%  |
| 0.01-0.5   | 10        | 6.9%    |
| 3.01-4.0   | 8         | 5.52%   |
| 5.01-6.0   | 3         | 2.07%   |
| 2.01-3.0   | 2         | 1.38%   |
| 0.51-1.0   | 2         | 1.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| BOE                     | 40        | 23.81%  |
| AU Optronics            | 32        | 19.05%  |
| Chimei Innolux          | 24        | 14.29%  |
| LG Display              | 21        | 12.5%   |
| Samsung Electronics     | 14        | 8.33%   |
| Apple                   | 7         | 4.17%   |
| Sharp                   | 4         | 2.38%   |
| PANDA                   | 4         | 2.38%   |
| TMX                     | 2         | 1.19%   |
| Goldstar                | 2         | 1.19%   |
| Dell                    | 2         | 1.19%   |
| BenQ                    | 2         | 1.19%   |
| Yamaha                  | 1         | 0.6%    |
| Toshiba                 | 1         | 0.6%    |
| Sony                    | 1         | 0.6%    |
| Sceptre Tech            | 1         | 0.6%    |
| Philips                 | 1         | 0.6%    |
| LGD                     | 1         | 0.6%    |
| Lenovo                  | 1         | 0.6%    |
| ITE                     | 1         | 0.6%    |
| HUAWEI                  | 1         | 0.6%    |
| HKC                     | 1         | 0.6%    |
| Hewlett-Packard         | 1         | 0.6%    |
| CSO                     | 1         | 0.6%    |
| Chi Mei Optoelectronics | 1         | 0.6%    |
| Acer                    | 1         | 0.6%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 4         | 2.38%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                   | 3         | 1.79%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 1.19%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 1.19%   |
| Chimei Innolux P130ZFA-BA1 CMN8201 2160x1440 275x183mm 13.0-inch        | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 1.19%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 1.19%   |
| BOE LCD Monitor BOE0A81 1920x1080 344x194mm 15.5-inch                   | 2         | 1.19%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                   | 2         | 1.19%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 2         | 1.19%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch           | 2         | 1.19%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.19%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.6%    |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                         | 1         | 0.6%    |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 0.6%    |
| TMX TL156MDMP01-1 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 0.6%    |
| Sony TV SNY3002 1920x1080 886x498mm 40.0-inch                           | 1         | 0.6%    |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 0.6%    |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                 | 1         | 0.6%    |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 0.6%    |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 0.6%    |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 0.6%    |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 0.6%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.6%    |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 1         | 0.6%    |
| Samsung Electronics S24D300 SAM0B43 1920x1080 531x299mm 24.0-inch       | 1         | 0.6%    |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch       | 1         | 0.6%    |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 0.6%    |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1         | 0.6%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 0.6%    |
| Philips PHL 221S8L PHL091C 1920x1080 477x268mm 21.5-inch                | 1         | 0.6%    |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 0.6%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 91        | 57.23%  |
| 1366x768 (WXGA)    | 35        | 22.01%  |
| 3840x2160 (4K)     | 7         | 4.4%    |
| 1600x900 (HD+)     | 6         | 3.77%   |
| 2560x1600          | 3         | 1.89%   |
| 1280x800 (WXGA)    | 3         | 1.89%   |
| 3200x1800 (QHD+)   | 2         | 1.26%   |
| 2160x1440          | 2         | 1.26%   |
| 1440x900 (WXGA+)   | 2         | 1.26%   |
| 3840x2400          | 1         | 0.63%   |
| 3200x2000          | 1         | 0.63%   |
| 2880x1800          | 1         | 0.63%   |
| 2560x1440 (QHD)    | 1         | 0.63%   |
| 2560x1080          | 1         | 0.63%   |
| 1920x540           | 1         | 0.63%   |
| 1920x1200 (WUXGA)  | 1         | 0.63%   |
| 1680x1050 (WSXGA+) | 1         | 0.63%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 79        | 47.31%  |
| 13      | 25        | 14.97%  |
| 14      | 23        | 13.77%  |
| 17      | 9         | 5.39%   |
| 23      | 5         | 2.99%   |
| 24      | 4         | 2.4%    |
| 21      | 4         | 2.4%    |
| 84      | 3         | 1.8%    |
| 16      | 3         | 1.8%    |
| 31      | 2         | 1.2%    |
| 27      | 2         | 1.2%    |
| Unknown | 2         | 1.2%    |
| 72      | 1         | 0.6%    |
| 46      | 1         | 0.6%    |
| 28      | 1         | 0.6%    |
| 19      | 1         | 0.6%    |
| 18      | 1         | 0.6%    |
| 12      | 1         | 0.6%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 117       | 69.64%  |
| 201-300     | 12        | 7.14%   |
| 501-600     | 11        | 6.55%   |
| 351-400     | 11        | 6.55%   |
| 401-500     | 7         | 4.17%   |
| 1501-2000   | 4         | 2.38%   |
| 601-700     | 3         | 1.79%   |
| Unknown     | 2         | 1.19%   |
| 1001-1500   | 1         | 0.6%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 131       | 88.51%  |
| 16/10   | 12        | 8.11%   |
| 3/2     | 2         | 1.35%   |
| 32/9    | 1         | 0.68%   |
| 21/9    | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 81        | 48.8%   |
| 81-90          | 41        | 24.7%   |
| 201-250        | 10        | 6.02%   |
| 121-130        | 9         | 5.42%   |
| 71-80          | 7         | 4.22%   |
| More than 1000 | 4         | 2.41%   |
| 151-200        | 3         | 1.81%   |
| 351-500        | 2         | 1.2%    |
| 301-350        | 2         | 1.2%    |
| Unknown        | 2         | 1.2%    |
| 61-70          | 1         | 0.6%    |
| 251-300        | 1         | 0.6%    |
| 141-150        | 1         | 0.6%    |
| 111-120        | 1         | 0.6%    |
| 501-1000       | 1         | 0.6%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 83        | 50.3%   |
| 101-120       | 43        | 26.06%  |
| 51-100        | 18        | 10.91%  |
| 161-240       | 10        | 6.06%   |
| More than 240 | 7         | 4.24%   |
| 1-50          | 2         | 1.21%   |
| Unknown       | 2         | 1.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 119       | 82.64%  |
| 2     | 23        | 15.97%  |
| 3     | 2         | 1.39%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 80        | 38.1%   |
| Realtek Semiconductor             | 73        | 34.76%  |
| Qualcomm Atheros                  | 18        | 8.57%   |
| Broadcom                          | 8         | 3.81%   |
| Broadcom Limited                  | 7         | 3.33%   |
| MediaTek                          | 5         | 2.38%   |
| TP-Link                           | 3         | 1.43%   |
| ASIX Electronics                  | 3         | 1.43%   |
| Sierra Wireless                   | 2         | 0.95%   |
| Samsung Electronics               | 2         | 0.95%   |
| Nvidia                            | 2         | 0.95%   |
| Ericsson Business Mobile Networks | 2         | 0.95%   |
| Ralink Technology                 | 1         | 0.48%   |
| Ralink                            | 1         | 0.48%   |
| Marvell Technology Group          | 1         | 0.48%   |
| Huawei Technologies               | 1         | 0.48%   |
| Dell                              | 1         | 0.48%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 49        | 18.92%  |
| Intel Wi-Fi 6 AX201                                                | 12        | 4.63%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 9         | 3.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 9         | 3.47%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 8         | 3.09%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 8         | 3.09%   |
| Intel Wireless 8265 / 8275                                         | 7         | 2.7%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 6         | 2.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 6         | 2.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 5         | 1.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 5         | 1.93%   |
| Intel Wireless 7265                                                | 5         | 1.93%   |
| Intel Wireless 7260                                                | 5         | 1.93%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 5         | 1.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 4         | 1.54%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                    | 4         | 1.54%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 4         | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 3         | 1.16%   |
| Intel Wireless 8260                                                | 3         | 1.16%   |
| Intel Wi-Fi 6 AX200                                                | 3         | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                              | 3         | 1.16%   |
| Intel Centrino Wireless-N 2230                                     | 3         | 1.16%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 3         | 1.16%   |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 1.16%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 2         | 0.77%   |
| Sierra Wireless EM7455                                             | 2         | 0.77%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 0.77%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 2         | 0.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter         | 2         | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                   | 2         | 0.77%   |
| Intel Ethernet Connection (5) I219-LM                              | 2         | 0.77%   |
| Intel Ethernet Connection (3) I218-V                               | 2         | 0.77%   |
| Intel Ethernet Connection (2) I219-LM                              | 2         | 0.77%   |
| Intel Ethernet Connection (13) I219-V                              | 2         | 0.77%   |
| Intel Centrino Ultimate-N 6300                                     | 2         | 0.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                   | 2         | 0.77%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 0.77%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter         | 2         | 0.77%   |
| TP-Link 802.11ac NIC                                               | 1         | 0.39%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 78        | 52.7%   |
| Realtek Semiconductor | 29        | 19.59%  |
| Qualcomm Atheros      | 16        | 10.81%  |
| Broadcom Limited      | 6         | 4.05%   |
| Broadcom              | 6         | 4.05%   |
| MediaTek              | 5         | 3.38%   |
| TP-Link               | 3         | 2.03%   |
| Sierra Wireless       | 2         | 1.35%   |
| Ralink Technology     | 1         | 0.68%   |
| Ralink                | 1         | 0.68%   |
| Dell                  | 1         | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                            | 12        | 8.11%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 9         | 6.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 6.08%   |
| Intel Wireless 8265 / 8275                                     | 7         | 4.73%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 6         | 4.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 3.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 3.38%   |
| Intel Wireless 7265                                            | 5         | 3.38%   |
| Intel Wireless 7260                                            | 5         | 3.38%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 3.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 4         | 2.7%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 2.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 2.7%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 2.03%   |
| Intel Wireless 8260                                            | 3         | 2.03%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 2.03%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 2.03%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 3         | 2.03%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 1.35%   |
| Sierra Wireless EM7455                                         | 2         | 1.35%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 2         | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.35%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 1.35%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.35%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 1.35%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.68%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 0.68%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                 | 1         | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.68%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.68%   |
| Ralink RT5572 Wireless Adapter                                 | 1         | 0.68%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 0.68%   |
| Intel Wireless-AC 9260                                         | 1         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 57.55%  |
| Intel                    | 28        | 26.42%  |
| Qualcomm Atheros         | 4         | 3.77%   |
| Broadcom                 | 3         | 2.83%   |
| ASIX Electronics         | 3         | 2.83%   |
| Samsung Electronics      | 2         | 1.89%   |
| Nvidia                   | 2         | 1.89%   |
| Marvell Technology Group | 1         | 0.94%   |
| Huawei Technologies      | 1         | 0.94%   |
| Broadcom Limited         | 1         | 0.94%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 49        | 44.95%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 7.34%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 7.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 6         | 5.5%    |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 2.75%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 2.75%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 1.83%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 1.83%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 1.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.83%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 1.83%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.92%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.92%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.92%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.92%   |
| Nvidia MCP89 Ethernet                                             | 1         | 0.92%   |
| Nvidia MCP79 Ethernet                                             | 1         | 0.92%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 0.92%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.92%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.92%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 0.92%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.92%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 0.92%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.92%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 0.92%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.92%   |
| Huawei MLA-L11                                                    | 1         | 0.92%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 0.92%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 0.92%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 1         | 0.92%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 0.92%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 141       | 57.55%  |
| Ethernet | 102       | 41.63%  |
| Modem    | 2         | 0.82%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 82.76%  |
| Ethernet | 25        | 17.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 90        | 62.5%   |
| 1     | 53        | 36.81%  |
| 0     | 1         | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 90        | 62.5%   |
| Yes  | 54        | 37.5%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 65        | 50%     |
| Realtek Semiconductor           | 20        | 15.38%  |
| IMC Networks                    | 9         | 6.92%   |
| Qualcomm Atheros Communications | 8         | 6.15%   |
| Broadcom                        | 6         | 4.62%   |
| Apple                           | 6         | 4.62%   |
| Lite-On Technology              | 5         | 3.85%   |
| Foxconn / Hon Hai               | 5         | 3.85%   |
| Realtek                         | 3         | 2.31%   |
| Toshiba                         | 1         | 0.77%   |
| Dell                            | 1         | 0.77%   |
| Cambridge Silicon Radio         | 1         | 0.77%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 22        | 16.92%  |
| Intel Bluetooth wireless interface                  | 19        | 14.62%  |
| Intel AX201 Bluetooth                               | 16        | 12.31%  |
| Realtek Bluetooth Radio                             | 15        | 11.54%  |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 5.38%   |
| Apple Bluetooth Host Controller                     | 5         | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 3.08%   |
| IMC Networks Wireless_Device                        | 4         | 3.08%   |
| IMC Networks Bluetooth Radio                        | 4         | 3.08%   |
| Realtek 802.11ac WLAN Adapter                       | 3         | 2.31%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 2.31%   |
| Intel AX200 Bluetooth                               | 3         | 2.31%   |
| Lite-On Bluetooth Device                            | 2         | 1.54%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.54%   |
| Broadcom BCM20702A0 Bluetooth                       | 2         | 1.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 1.54%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.77%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.77%   |
| Qualcomm Atheros Bluetooth (AR3011)                 | 1         | 0.77%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1         | 0.77%   |
| Intel AX210 Bluetooth                               | 1         | 0.77%   |
| IMC Networks BCM20702A0                             | 1         | 0.77%   |
| Foxconn / Hon Hai Wireless_Device                   | 1         | 0.77%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 1         | 0.77%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1         | 0.77%   |
| Foxconn / Hon Hai BCM20702A0                        | 1         | 0.77%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 0.77%   |
| Dell BCM20702A0 Bluetooth Module                    | 1         | 0.77%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 1         | 0.77%   |
| Broadcom BCM2045B (BDC-2.1)                         | 1         | 0.77%   |
| Broadcom BCM2045A0                                  | 1         | 0.77%   |
| Apple Bluetooth USB Host Controller                 | 1         | 0.77%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 116       | 63.74%  |
| Nvidia                     | 31        | 17.03%  |
| AMD                        | 26        | 14.29%  |
| GN Netcom                  | 2         | 1.1%    |
| Samsung Electronics        | 1         | 0.55%   |
| Realtek Semiconductor      | 1         | 0.55%   |
| PreSonus Audio Electronics | 1         | 0.55%   |
| Lenovo                     | 1         | 0.55%   |
| JMTek                      | 1         | 0.55%   |
| Barco Display Systems      | 1         | 0.55%   |
| ASUSTek Computer           | 1         | 0.55%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 22        | 9.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 16        | 7.11%   |
| Intel Sunrise Point-LP HD Audio                                            | 14        | 6.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 10        | 4.44%   |
| Intel Broadwell-U Audio Controller                                         | 10        | 4.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 10        | 4.44%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 10        | 4.44%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 4%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 8         | 3.56%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 3.11%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 3.11%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 6         | 2.67%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 2.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 2.67%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 5         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.22%   |
| Intel Comet Lake PCH-LP cAVS                                               | 5         | 2.22%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 2.22%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 1.78%   |
| Intel CM238 HD Audio Controller                                            | 4         | 1.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.33%   |
| Nvidia Audio device                                                        | 3         | 1.33%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.33%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 3         | 1.33%   |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.89%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.89%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.89%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 2         | 0.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 2         | 0.89%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 0.89%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.44%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.44%   |
| PreSonus Audio Electronics AudioBox USB 96                                 | 1         | 0.44%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.44%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.44%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 49        | 30.25%  |
| Samsung Electronics | 45        | 27.78%  |
| Micron Technology   | 23        | 14.2%   |
| Crucial             | 14        | 8.64%   |
| Ramaxel Technology  | 9         | 5.56%   |
| Kingston            | 9         | 5.56%   |
| Unknown             | 3         | 1.85%   |
| Timetec             | 1         | 0.62%   |
| Team                | 1         | 0.62%   |
| Smart Brazil        | 1         | 0.62%   |
| Smart               | 1         | 0.62%   |
| PNY                 | 1         | 0.62%   |
| Nanya Technology    | 1         | 0.62%   |
| KingFast            | 1         | 0.62%   |
| GOODRAM             | 1         | 0.62%   |
| Elpida              | 1         | 0.62%   |
| Corsair             | 1         | 0.62%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s             | 6         | 3.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s              | 6         | 3.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s              | 4         | 2.37%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s              | 4         | 2.37%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s             | 3         | 1.78%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s              | 3         | 1.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s              | 3         | 1.78%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s        | 3         | 1.78%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                       | 2         | 1.18%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s             | 2         | 1.18%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s             | 2         | 1.18%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s          | 2         | 1.18%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s             | 2         | 1.18%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s            | 2         | 1.18%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 2         | 1.18%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s             | 2         | 1.18%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 2         | 1.18%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s             | 2         | 1.18%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s   | 2         | 1.18%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s              | 2         | 1.18%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s              | 2         | 1.18%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s              | 2         | 1.18%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s              | 2         | 1.18%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s              | 2         | 1.18%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s          | 2         | 1.18%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s          | 2         | 1.18%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s              | 2         | 1.18%   |
| Unknown RAM Module 8GB SODIMM DDR3 1067MT/s                        | 1         | 0.59%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                      | 1         | 0.59%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                          | 1         | 0.59%   |
| Timetec RAM Module 4GB SODIMM DDR3 1067MT/s                        | 1         | 0.59%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s               | 1         | 0.59%   |
| Smart RAM SF564128CJ8NWMNSEG 4GB SODIMM DDR3 1600MT/s              | 1         | 0.59%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s       | 1         | 0.59%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB Row Of Chips DDR4 2667MT/s | 1         | 0.59%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                       | 1         | 0.59%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                      | 1         | 0.59%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s             | 1         | 0.59%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s             | 1         | 0.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s             | 1         | 0.59%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 77        | 60.16%  |
| DDR3   | 36        | 28.13%  |
| LPDDR4 | 4         | 3.13%   |
| LPDDR3 | 3         | 2.34%   |
| DDR5   | 3         | 2.34%   |
| LPDDR5 | 2         | 1.56%   |
| SDRAM  | 1         | 0.78%   |
| DDR2   | 1         | 0.78%   |
| DDR    | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 114       | 85.71%  |
| Row Of Chips | 17        | 12.78%  |
| Chip         | 2         | 1.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 71        | 48.63%  |
| 4096  | 50        | 34.25%  |
| 16384 | 16        | 10.96%  |
| 2048  | 8         | 5.48%   |
| 32768 | 1         | 0.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 41        | 28.28%  |
| 3200    | 34        | 23.45%  |
| 1600    | 27        | 18.62%  |
| 1333    | 7         | 4.83%   |
| 3266    | 6         | 4.14%   |
| 2133    | 6         | 4.14%   |
| 2400    | 5         | 3.45%   |
| 4800    | 3         | 2.07%   |
| 1067    | 3         | 2.07%   |
| 6400    | 2         | 1.38%   |
| 4267    | 2         | 1.38%   |
| 1334    | 2         | 1.38%   |
| 800     | 2         | 1.38%   |
| 8400    | 1         | 0.69%   |
| 4199    | 1         | 0.69%   |
| 2933    | 1         | 0.69%   |
| 2666    | 1         | 0.69%   |
| Unknown | 1         | 0.69%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 30        | 21.9%   |
| IMC Networks                           | 29        | 21.17%  |
| Realtek Semiconductor                  | 12        | 8.76%   |
| Sunplus Innovation Technology          | 10        | 7.3%    |
| Bison Electronics                      | 9         | 6.57%   |
| Microdia                               | 8         | 5.84%   |
| Syntek                                 | 7         | 5.11%   |
| Quanta                                 | 6         | 4.38%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.65%   |
| Apple                                  | 4         | 2.92%   |
| Suyin                                  | 3         | 2.19%   |
| Luxvisions Innotech Limited            | 3         | 2.19%   |
| Lite-On Technology                     | 3         | 2.19%   |
| SunplusIT                              | 1         | 0.73%   |
| Sonix Technology                       | 1         | 0.73%   |
| Samsung Electronics                    | 1         | 0.73%   |
| Ricoh                                  | 1         | 0.73%   |
| OPPO Electronics                       | 1         | 0.73%   |
| Alpha Imaging Technology               | 1         | 0.73%   |
| ALi                                    | 1         | 0.73%   |
| Alcor Micro                            | 1         | 0.73%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                              | 10        | 7.25%   |
| Chicony Integrated Camera                                      | 9         | 6.52%   |
| Syntek Integrated Camera                                       | 7         | 5.07%   |
| IMC Networks Integrated Camera                                 | 6         | 4.35%   |
| Realtek Integrated_Webcam_HD                                   | 5         | 3.62%   |
| Quanta HP TrueVision HD Camera                                 | 4         | 2.9%    |
| Microdia Integrated_Webcam_HD                                  | 4         | 2.9%    |
| IMC Networks HD Camera                                         | 4         | 2.9%    |
| Lite-On Integrated Camera                                      | 3         | 2.17%   |
| IMC Networks USB2.0 VGA UVC WebCam                             | 3         | 2.17%   |
| Chicony HP TrueVision HD Camera                                | 3         | 2.17%   |
| Sunplus Laptop Integrated Webcam FHD                           | 2         | 1.45%   |
| Sunplus Integrated_Webcam_HD                                   | 2         | 1.45%   |
| Realtek Integrated Webcam_HD                                   | 2         | 1.45%   |
| Quanta HD User Facing                                          | 2         | 1.45%   |
| Microdia USB 2.0 Camera                                        | 2         | 1.45%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera            | 2         | 1.45%   |
| IMC Networks VGA UVC WebCam                                    | 2         | 1.45%   |
| Chicony HD WebCam                                              | 2         | 1.45%   |
| Chicony EasyCamera                                             | 2         | 1.45%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.45%   |
| Bison ThinkPad Integrated Camera                               | 2         | 1.45%   |
| Bison Integrated Camera                                        | 2         | 1.45%   |
| Bison HD Webcam                                                | 2         | 1.45%   |
| Apple Built-in iSight                                          | 2         | 1.45%   |
| Suyin Integrated_Webcam_HD                                     | 1         | 0.72%   |
| Suyin HD WebCam                                                | 1         | 0.72%   |
| Suyin Asus Integrated Webcam                                   | 1         | 0.72%   |
| SunplusIT XiaoMi USB 2.0 Webcam                                | 1         | 0.72%   |
| Sunplus XiaoMi USB 2.0 Webcam                                  | 1         | 0.72%   |
| Sunplus Lenovo EasyCamera                                      | 1         | 0.72%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 1         | 0.72%   |
| Sunplus Integrated_Webcam_FHD                                  | 1         | 0.72%   |
| Sunplus HP Truevision HD                                       | 1         | 0.72%   |
| Sunplus FHD Camera Microphone                                  | 1         | 0.72%   |
| Sonix USB2.0 HD UVC WebCam                                     | 1         | 0.72%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 1         | 0.72%   |
| Ricoh Integrated Webcam                                        | 1         | 0.72%   |
| Realtek USB2.0 HD UVC WebCam                                   | 1         | 0.72%   |
| Realtek Integrated Webcam                                      | 1         | 0.72%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 35%     |
| Shenzhen Goodix Technology | 5         | 25%     |
| Synaptics                  | 4         | 20%     |
| Elan Microelectronics      | 2         | 10%     |
| LighTuning Technology      | 1         | 5%      |
| AuthenTec                  | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 4         | 20%     |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 3         | 15%     |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 5%      |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 5%      |
| Validity Sensors VFS 5011 fingerprint sensor      | 1         | 5%      |
| Validity Sensors Synaptics WBDI                   | 1         | 5%      |
| Synaptics WBDI                                    | 1         | 5%      |
| Synaptics UWP WBDI                                | 1         | 5%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 5%      |
| Shenzhen Goodix Fingerprint Reader                | 1         | 5%      |
| LighTuning Fingerprint Reader                     | 1         | 5%      |
| Elan WBF Fingerprint Sensor                       | 1         | 5%      |
| Elan ELAN:ARM-M4                                  | 1         | 5%      |
| AuthenTec Fingerprint Sensor                      | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 5         | 35.71%  |
| Alcor Micro | 5         | 35.71%  |
| Upek        | 2         | 14.29%  |
| Yubico.com  | 1         | 7.14%   |
| Clay Logic  | 1         | 7.14%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 35.71%  |
| Broadcom BCM5880 Secure Applications Processor             | 3         | 21.43%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 14.29%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 7.14%   |
| Clay Logic Nitrokey Pro                                    | 1         | 7.14%   |
| Broadcom 5880                                              | 1         | 7.14%   |
| Broadcom 58200                                             | 1         | 7.14%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 103       | 71.03%  |
| 1     | 31        | 21.38%  |
| 2     | 10        | 6.9%    |
| 3     | 1         | 0.69%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 20        | 37.74%  |
| Chipcard              | 12        | 22.64%  |
| Graphics card         | 10        | 18.87%  |
| Multimedia controller | 5         | 9.43%   |
| Camera                | 3         | 5.66%   |
| Storage               | 2         | 3.77%   |
| Network               | 1         | 1.89%   |

