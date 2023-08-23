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

Total: 149

| Vendor    | Model                       | Probe                                                      | Date         |
|-----------|-----------------------------|------------------------------------------------------------|--------------|
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
| Xero Rolling | 110       | 93.22%  |
| Xero         | 8         | 6.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name | Notebooks | Percent |
|------|-----------|---------|
| Xero | 117       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version              | Notebooks | Percent |
|----------------------|-----------|---------|
| 6.4.3-arch1-2        | 12        | 9.68%   |
| 6.4.2-arch1-1        | 6         | 4.84%   |
| 6.4.4-arch1-1        | 4         | 3.23%   |
| 6.4.1-arch2-1        | 4         | 3.23%   |
| 6.0.12-arch1-1       | 4         | 3.23%   |
| 5.16.15-arch1-1      | 4         | 3.23%   |
| 6.2.6-arch1-1        | 3         | 2.42%   |
| 6.1.1-arch1-1        | 3         | 2.42%   |
| 6.4.9-arch1-1        | 2         | 1.61%   |
| 6.4.2-zen1-1-zen     | 2         | 1.61%   |
| 6.3.9-arch1-1        | 2         | 1.61%   |
| 6.3.8-arch1-1        | 2         | 1.61%   |
| 6.2.7-arch1-1        | 2         | 1.61%   |
| 6.0.7-arch1-1        | 2         | 1.61%   |
| 5.18.16-arch1-1      | 2         | 1.61%   |
| 5.18.11-arch1-1      | 2         | 1.61%   |
| 5.17.9-arch1-1       | 2         | 1.61%   |
| 5.16.8-arch1-1       | 2         | 1.61%   |
| 5.16.2-arch1-1       | 2         | 1.61%   |
| 5.16.1-arch1-1       | 2         | 1.61%   |
| 5.15.33-1-lts        | 2         | 1.61%   |
| 5.14.14-arch1-1      | 2         | 1.61%   |
| 6.4.8-arch1-1        | 1         | 0.81%   |
| 6.4.7-zen1-1-zen     | 1         | 0.81%   |
| 6.4.7-arch1-3        | 1         | 0.81%   |
| 6.4.7-arch1-1        | 1         | 0.81%   |
| 6.4.6-arch1-1        | 1         | 0.81%   |
| 6.4.1-arch1-1        | 1         | 0.81%   |
| 6.3.9-zen1-1-zen     | 1         | 0.81%   |
| 6.3.6-arch1-1        | 1         | 0.81%   |
| 6.3.4-arch1-1        | 1         | 0.81%   |
| 6.2.8-arch1-1        | 1         | 0.81%   |
| 6.2.2-arch2-1        | 1         | 0.81%   |
| 6.1.8-arch1-1        | 1         | 0.81%   |
| 6.1.7-arch1-1        | 1         | 0.81%   |
| 6.1.6-arch1-1        | 1         | 0.81%   |
| 6.1.4-arch1-1        | 1         | 0.81%   |
| 6.1.38-x64v3-xanmod1 | 1         | 0.81%   |
| 6.1.38-1-lts         | 1         | 0.81%   |
| 6.1.3-zen1-1-zen     | 1         | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4.3   | 12        | 9.68%   |
| 6.4.2   | 8         | 6.45%   |
| 6.4.1   | 5         | 4.03%   |
| 6.4.4   | 4         | 3.23%   |
| 6.0.12  | 4         | 3.23%   |
| 5.16.15 | 4         | 3.23%   |
| 6.4.7   | 3         | 2.42%   |
| 6.3.9   | 3         | 2.42%   |
| 6.2.6   | 3         | 2.42%   |
| 6.1.1   | 3         | 2.42%   |
| 5.14.16 | 3         | 2.42%   |
| 5.14.14 | 3         | 2.42%   |
| 6.4.9   | 2         | 1.61%   |
| 6.3.8   | 2         | 1.61%   |
| 6.2.7   | 2         | 1.61%   |
| 6.1.38  | 2         | 1.61%   |
| 6.0.8   | 2         | 1.61%   |
| 6.0.7   | 2         | 1.61%   |
| 5.18.16 | 2         | 1.61%   |
| 5.18.11 | 2         | 1.61%   |
| 5.17.9  | 2         | 1.61%   |
| 5.16.8  | 2         | 1.61%   |
| 5.16.2  | 2         | 1.61%   |
| 5.16.1  | 2         | 1.61%   |
| 5.15.33 | 2         | 1.61%   |
| 5.14.8  | 2         | 1.61%   |
| 6.4.8   | 1         | 0.81%   |
| 6.4.6   | 1         | 0.81%   |
| 6.3.6   | 1         | 0.81%   |
| 6.3.4   | 1         | 0.81%   |
| 6.2.8   | 1         | 0.81%   |
| 6.2.2   | 1         | 0.81%   |
| 6.1.8   | 1         | 0.81%   |
| 6.1.7   | 1         | 0.81%   |
| 6.1.6   | 1         | 0.81%   |
| 6.1.4   | 1         | 0.81%   |
| 6.1.3   | 1         | 0.81%   |
| 6.1.15  | 1         | 0.81%   |
| 6.1.12  | 1         | 0.81%   |
| 6.0.9   | 1         | 0.81%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.4     | 35        | 28.93%  |
| 5.16    | 14        | 11.57%  |
| 6.0     | 12        | 9.92%   |
| 6.1     | 11        | 9.09%   |
| 5.15    | 9         | 7.44%   |
| 5.14    | 9         | 7.44%   |
| 6.3     | 7         | 5.79%   |
| 6.2     | 7         | 5.79%   |
| 5.19    | 5         | 4.13%   |
| 5.18    | 5         | 4.13%   |
| 5.17    | 4         | 3.31%   |
| 5.10    | 3         | 2.48%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 117       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 108       | 91.53%  |
| XFCE     | 4         | 3.39%   |
| GNOME    | 3         | 2.54%   |
| LeftWM   | 1         | 0.85%   |
| KDE      | 1         | 0.85%   |
| Hyprland | 1         | 0.85%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 104       | 88.14%  |
| Wayland | 13        | 11.02%  |
| Unknown | 1         | 0.85%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 90        | 75%     |
| Unknown | 17        | 14.17%  |
| LightDM | 12        | 10%     |
| GDM     | 1         | 0.83%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 57        | 48.31%  |
| de_DE | 11        | 9.32%   |
| en_IN | 10        | 8.47%   |
| pl_PL | 4         | 3.39%   |
| C     | 4         | 3.39%   |
| ru_RU | 3         | 2.54%   |
| it_IT | 3         | 2.54%   |
| fr_FR | 3         | 2.54%   |
| es_MX | 3         | 2.54%   |
| en_AU | 3         | 2.54%   |
| vi_VN | 2         | 1.69%   |
| en_GB | 2         | 1.69%   |
| zh_CN | 1         | 0.85%   |
| tr_TR | 1         | 0.85%   |
| nb_NO | 1         | 0.85%   |
| hu_HU | 1         | 0.85%   |
| es_SV | 1         | 0.85%   |
| es_CL | 1         | 0.85%   |
| es_AR | 1         | 0.85%   |
| en_ZA | 1         | 0.85%   |
| en_PH | 1         | 0.85%   |
| en_DK | 1         | 0.85%   |
| en_CA | 1         | 0.85%   |
| en_AG | 1         | 0.85%   |
| ca_ES | 1         | 0.85%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 84        | 70.59%  |
| BIOS | 35        | 29.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Xfs     | 49        | 41.53%  |
| Btrfs   | 46        | 38.98%  |
| Ext4    | 19        | 16.1%   |
| Overlay | 4         | 3.39%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 88        | 73.95%  |
| Unknown | 17        | 14.29%  |
| MBR     | 14        | 11.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 95        | 79.17%  |
| Yes       | 25        | 20.83%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 74        | 62.71%  |
| Yes       | 44        | 37.29%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Lenovo           | 33        | 28.21%  |
| ASUSTek Computer | 21        | 17.95%  |
| Dell             | 18        | 15.38%  |
| Hewlett-Packard  | 16        | 13.68%  |
| Acer             | 8         | 6.84%   |
| Apple            | 6         | 5.13%   |
| MSI              | 3         | 2.56%   |
| Medion           | 2         | 1.71%   |
| HUAWEI           | 2         | 1.71%   |
| WEIGO            | 1         | 0.85%   |
| Toshiba          | 1         | 0.85%   |
| Timi             | 1         | 0.85%   |
| Pegatron         | 1         | 0.85%   |
| LNV              | 1         | 0.85%   |
| Fujitsu          | 1         | 0.85%   |
| Aquarius         | 1         | 0.85%   |
| Alienware        | 1         | 0.85%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Dell Precision M3800                       | 3         | 2.56%   |
| Dell Latitude 7480                         | 2         | 1.71%   |
| WEIGO CDA-141AU                            | 1         | 0.85%   |
| Toshiba TECRA A11                          | 1         | 0.85%   |
| Timi Redmi Book Pro 15 2022                | 1         | 0.85%   |
| Pegatron D15K                              | 1         | 0.85%   |
| MSI Katana GF66 11UE                       | 1         | 0.85%   |
| MSI GP73 Leopard 8RD                       | 1         | 0.85%   |
| MSI GF63 Thin 9SCX                         | 1         | 0.85%   |
| Medion P6816                               | 1         | 0.85%   |
| Medion Akoya P7818                         | 1         | 0.85%   |
| LNV L40-70                                 | 1         | 0.85%   |
| Lenovo Yoga 3 Pro-1370 80HE                | 1         | 0.85%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.85%   |
| Lenovo ThinkPad X230 2325HR9               | 1         | 0.85%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW0055MH | 1         | 0.85%   |
| Lenovo ThinkPad W530 24384CU               | 1         | 0.85%   |
| Lenovo ThinkPad T490s 20NX001KMX           | 1         | 0.85%   |
| Lenovo ThinkPad T480 20L6S2CE00            | 1         | 0.85%   |
| Lenovo ThinkPad T470p 20J6003DGE           | 1         | 0.85%   |
| Lenovo ThinkPad T460s 20F90057MS           | 1         | 0.85%   |
| Lenovo ThinkPad T460 20FMS1XX00            | 1         | 0.85%   |
| Lenovo ThinkPad T450 20BUS1BW01            | 1         | 0.85%   |
| Lenovo ThinkPad T440 20B7A0CYMH            | 1         | 0.85%   |
| Lenovo ThinkPad T430s 2356FG9              | 1         | 0.85%   |
| Lenovo ThinkPad T420 4236C92               | 1         | 0.85%   |
| Lenovo ThinkPad P72 20MCS0EU00             | 1         | 0.85%   |
| Lenovo ThinkPad P51 20HJS11Y00             | 1         | 0.85%   |
| Lenovo ThinkPad L450 20DT0000GE            | 1         | 0.85%   |
| Lenovo Legion Y740-15IRHg 81UH             | 1         | 0.85%   |
| Lenovo Legion Y540-15IRH-PG0 81SY          | 1         | 0.85%   |
| Lenovo Legion 5 Pro 16ARH7H 82RG           | 1         | 0.85%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.85%   |
| Lenovo Legion 5 15ACH6H 82JU               | 1         | 0.85%   |
| Lenovo IdeaPad S540-15IML D 81NG           | 1         | 0.85%   |
| Lenovo IdeaPad S340-15IIL 81VW             | 1         | 0.85%   |
| Lenovo IdeaPad S145-15IIL 81W8             | 1         | 0.85%   |
| Lenovo IdeaPad S145-15AST 81N3             | 1         | 0.85%   |
| Lenovo IdeaPad Gaming 3 15IHU6 82K1        | 1         | 0.85%   |
| Lenovo IdeaPad 5 15ITL05 82FG              | 1         | 0.85%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 15        | 12.82%  |
| Lenovo IdeaPad     | 11        | 9.4%    |
| HP Laptop          | 7         | 5.98%   |
| ASUS VivoBook      | 7         | 5.98%   |
| Acer Aspire        | 7         | 5.98%   |
| Dell Latitude      | 6         | 5.13%   |
| Lenovo Legion      | 5         | 4.27%   |
| Dell Inspiron      | 4         | 3.42%   |
| ASUS ASUS          | 4         | 3.42%   |
| Dell Precision     | 3         | 2.56%   |
| HP ENVY            | 2         | 1.71%   |
| ASUS ROG           | 2         | 1.71%   |
| Apple MacBookPro11 | 2         | 1.71%   |
| WEIGO CDA-141AU    | 1         | 0.85%   |
| Toshiba TECRA      | 1         | 0.85%   |
| Timi Redmi         | 1         | 0.85%   |
| Pegatron D15K      | 1         | 0.85%   |
| MSI Katana         | 1         | 0.85%   |
| MSI GP73           | 1         | 0.85%   |
| MSI GF63           | 1         | 0.85%   |
| Medion P6816       | 1         | 0.85%   |
| Medion Akoya       | 1         | 0.85%   |
| LNV L40-70         | 1         | 0.85%   |
| Lenovo Yoga        | 1         | 0.85%   |
| Lenovo Y520-15IKBN | 1         | 0.85%   |
| HUAWEI WRT-WX9     | 1         | 0.85%   |
| HUAWEI BOM-WXX9    | 1         | 0.85%   |
| HP ZBook           | 1         | 0.85%   |
| HP Victus          | 1         | 0.85%   |
| HP ProBook         | 1         | 0.85%   |
| HP Pavilion        | 1         | 0.85%   |
| HP OMEN            | 1         | 0.85%   |
| HP Notebook        | 1         | 0.85%   |
| HP 245             | 1         | 0.85%   |
| Fujitsu LIFEBOOK   | 1         | 0.85%   |
| Dell XPS           | 1         | 0.85%   |
| Dell Vostro        | 1         | 0.85%   |
| Dell Venue         | 1         | 0.85%   |
| Dell G5            | 1         | 0.85%   |
| Dell G3            | 1         | 0.85%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 21        | 17.95%  |
| 2020 | 17        | 14.53%  |
| 2021 | 15        | 12.82%  |
| 2018 | 9         | 7.69%   |
| 2017 | 8         | 6.84%   |
| 2013 | 8         | 6.84%   |
| 2012 | 8         | 6.84%   |
| 2014 | 7         | 5.98%   |
| 2015 | 5         | 4.27%   |
| 2011 | 5         | 4.27%   |
| 2022 | 4         | 3.42%   |
| 2016 | 4         | 3.42%   |
| 2010 | 3         | 2.56%   |
| 2009 | 2         | 1.71%   |
| 2008 | 1         | 0.85%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 117       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 117       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 117       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 45        | 38.46%  |
| 16.01-24.0  | 24        | 20.51%  |
| 8.01-16.0   | 22        | 18.8%   |
| 3.01-4.0    | 16        | 13.68%  |
| 32.01-64.0  | 7         | 5.98%   |
| 24.01-32.0  | 2         | 1.71%   |
| 64.01-256.0 | 1         | 0.85%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 40        | 33.06%  |
| 2.01-3.0   | 36        | 29.75%  |
| 4.01-8.0   | 22        | 18.18%  |
| 3.01-4.0   | 18        | 14.88%  |
| 8.01-16.0  | 2         | 1.65%   |
| 0.51-1.0   | 2         | 1.65%   |
| 16.01-24.0 | 1         | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 74        | 62.71%  |
| 2      | 37        | 31.36%  |
| 3      | 6         | 5.08%   |
| 4      | 1         | 0.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 93        | 79.49%  |
| Yes       | 24        | 20.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 85        | 72.65%  |
| No        | 32        | 27.35%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 114       | 97.44%  |
| No        | 3         | 2.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 103       | 88.03%  |
| No        | 14        | 11.97%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country               | Notebooks | Percent |
|-----------------------|-----------|---------|
| USA                   | 20        | 16.95%  |
| Germany               | 15        | 12.71%  |
| India                 | 12        | 10.17%  |
| France                | 6         | 5.08%   |
| Poland                | 4         | 3.39%   |
| Italy                 | 4         | 3.39%   |
| Turkey                | 3         | 2.54%   |
| Russia                | 3         | 2.54%   |
| Norway                | 3         | 2.54%   |
| Canada                | 3         | 2.54%   |
| Australia             | 3         | 2.54%   |
| Vietnam               | 2         | 1.69%   |
| Romania               | 2         | 1.69%   |
| Pakistan              | 2         | 1.69%   |
| Indonesia             | 2         | 1.69%   |
| Hungary               | 2         | 1.69%   |
| Greece                | 2         | 1.69%   |
| Egypt                 | 2         | 1.69%   |
| Chile                 | 2         | 1.69%   |
| Zambia                | 1         | 0.85%   |
| Togo                  | 1         | 0.85%   |
| Thailand              | 1         | 0.85%   |
| Switzerland           | 1         | 0.85%   |
| Sweden                | 1         | 0.85%   |
| Spain                 | 1         | 0.85%   |
| South Africa          | 1         | 0.85%   |
| Portugal              | 1         | 0.85%   |
| Philippines           | 1         | 0.85%   |
| Palestinian Territory | 1         | 0.85%   |
| Netherlands           | 1         | 0.85%   |
| Nepal                 | 1         | 0.85%   |
| Morocco               | 1         | 0.85%   |
| Mongolia              | 1         | 0.85%   |
| Mexico                | 1         | 0.85%   |
| Malaysia              | 1         | 0.85%   |
| Lebanon               | 1         | 0.85%   |
| Finland               | 1         | 0.85%   |
| El Salvador           | 1         | 0.85%   |
| Denmark               | 1         | 0.85%   |
| Colombia              | 1         | 0.85%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Longmont          | 3         | 2.52%   |
| Istanbul          | 3         | 2.52%   |
| Tangerang         | 2         | 1.68%   |
| Stuttgart         | 2         | 1.68%   |
| Pune              | 2         | 1.68%   |
| Madurai           | 2         | 1.68%   |
| Hamburg           | 2         | 1.68%   |
| Chennai           | 2         | 1.68%   |
| Cairo             | 2         | 1.68%   |
| Zurich            | 1         | 0.84%   |
| Zenica            | 1         | 0.84%   |
| Zalaegerszeg      | 1         | 0.84%   |
| Wolfsburg         | 1         | 0.84%   |
| Warsaw            | 1         | 0.84%   |
| Viburnum          | 1         | 0.84%   |
| Vejle             | 1         | 0.84%   |
| Vechelde          | 1         | 0.84%   |
| Valladolid        | 1         | 0.84%   |
| Ulan Bator        | 1         | 0.84%   |
| Ufa               | 1         | 0.84%   |
| Toronto           | 1         | 0.84%   |
| Tirana            | 1         | 0.84%   |
| Tigre             | 1         | 0.84%   |
| Tavarede          | 1         | 0.84%   |
| Taranto           | 1         | 0.84%   |
| Tampere           | 1         | 0.84%   |
| Stockholm         | 1         | 0.84%   |
| Stavropol         | 1         | 0.84%   |
| Stagno            | 1         | 0.84%   |
| Seattle           | 1         | 0.84%   |
| Santa Cruz        | 1         | 0.84%   |
| San Salvador      | 1         | 0.84%   |
| Sacramento        | 1         | 0.84%   |
| Ramallah          | 1         | 0.84%   |
| Pretoria          | 1         | 0.84%   |
| Poznan            | 1         | 0.84%   |
| Porcia            | 1         | 0.84%   |
| Pointe-a-la-Croix | 1         | 0.84%   |
| Pittsburgh        | 1         | 0.84%   |
| Pirmasens         | 1         | 0.84%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 28        | 32     | 17.39%  |
| Seagate                      | 19        | 22     | 11.8%   |
| Toshiba                      | 14        | 15     | 8.7%    |
| WDC                          | 10        | 11     | 6.21%   |
| Intel                        | 9         | 11     | 5.59%   |
| SK hynix                     | 7         | 7      | 4.35%   |
| SanDisk                      | 6         | 7      | 3.73%   |
| Kingston                     | 6         | 7      | 3.73%   |
| Micron Technology            | 5         | 6      | 3.11%   |
| Unknown                      | 4         | 4      | 2.48%   |
| KIOXIA                       | 4         | 5      | 2.48%   |
| HGST                         | 4         | 4      | 2.48%   |
| Crucial                      | 4         | 4      | 2.48%   |
| Transcend                    | 3         | 3      | 1.86%   |
| Apple                        | 3         | 3      | 1.86%   |
| Apacer                       | 3         | 3      | 1.86%   |
| Shenzhen Longsys Electronics | 2         | 2      | 1.24%   |
| OWC                          | 2         | 2      | 1.24%   |
| LITEONIT                     | 2         | 2      | 1.24%   |
| Kingston Technology Company  | 2         | 2      | 1.24%   |
| Hitachi                      | 2         | 2      | 1.24%   |
| A-DATA Technology            | 2         | 2      | 1.24%   |
| Vaseky                       | 1         | 1      | 0.62%   |
| SandWind                     | 1         | 1      | 0.62%   |
| SAGE                         | 1         | 1      | 0.62%   |
| S3+                          | 1         | 1      | 0.62%   |
| Realtek Semiconductor        | 1         | 1      | 0.62%   |
| Plextor                      | 1         | 1      | 0.62%   |
| Phison Electronics           | 1         | 1      | 0.62%   |
| Phison                       | 1         | 1      | 0.62%   |
| OSCOO                        | 1         | 1      | 0.62%   |
| Micron/Crucial Technology    | 1         | 1      | 0.62%   |
| LITEON                       | 1         | 1      | 0.62%   |
| KingFast                     | 1         | 1      | 0.62%   |
| JetFlash                     | 1         | 1      | 0.62%   |
| Intenso                      | 1         | 1      | 0.62%   |
| Inateck                      | 1         | 1      | 0.62%   |
| GOODRAM                      | 1         | 1      | 0.62%   |
| Emtec                        | 1         | 1      | 0.62%   |
| China                        | 1         | 1      | 0.62%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                              | 5         | 3.01%   |
| Seagate ST1000LM035-1RK172 1TB                      | 4         | 2.41%   |
| Seagate ST1000LM049-2GH172 1TB                      | 3         | 1.81%   |
| Seagate One Touch HDD 1TB                           | 3         | 1.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 3         | 1.81%   |
| WDC WD10SPZX-24Z10 1TB                              | 2         | 1.2%    |
| Unknown MMC Card  64GB                              | 2         | 1.2%    |
| Toshiba XG6 NVMe SSD Controller 512GB               | 2         | 1.2%    |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 1.2%    |
| Samsung SSD 860 EVO 250GB                           | 2         | 1.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 1.2%    |
| OWC Mercury Electra 3G SSD                          | 2         | 1.2%    |
| Micron 2210_MTFDHBA512QFD 512GB                     | 2         | 1.2%    |
| Kingston SA400S37480G 480GB SSD                     | 2         | 1.2%    |
| Apacer AS350 256GB SSD                              | 2         | 1.2%    |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.6%    |
| WDC WDBNCE0010PNC 1TB SSD                           | 1         | 0.6%    |
| WDC WD3200BEVT-22ZCT0 320GB                         | 1         | 0.6%    |
| WDC WD10SPZX-60Z10T0 1TB                            | 1         | 0.6%    |
| WDC PC SN720 SDAPNTW-512G-1027 512GB                | 1         | 0.6%    |
| WDC PC SN530 SDBPNPZ-256G-1114 256GB                | 1         | 0.6%    |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 1         | 0.6%    |
| WDC PC SN520 SDAPMUW-256G-1101 256GB                | 1         | 0.6%    |
| Vaseky V800/256G 256GB SSD                          | 1         | 0.6%    |
| Unknown SD/MMC/MS PRO 128GB                         | 1         | 0.6%    |
| Unknown G1J38E  64GB                                | 1         | 0.6%    |
| Transcend TS64GSSD370S 64GB                         | 1         | 0.6%    |
| Transcend TS512GMTS430S 512GB SSD                   | 1         | 0.6%    |
| Transcend TS256GMTS400 256GB SSD                    | 1         | 0.6%    |
| Toshiba XG4 NVMe SSD Controller 256GB               | 1         | 0.6%    |
| Toshiba MQ01ABF050M 500GB                           | 1         | 0.6%    |
| Toshiba MQ01ABF050 500GB                            | 1         | 0.6%    |
| Toshiba MK3261GSY 320GB                             | 1         | 0.6%    |
| Toshiba MK2555GSX 250GB                             | 1         | 0.6%    |
| Toshiba KBG40ZNT512G MEMORY 512GB                   | 1         | 0.6%    |
| Toshiba KBG30ZMV256G 256GB                          | 1         | 0.6%    |
| SK hynix SKHynix_HFS512GD9TNG-L5B0B 512GB           | 1         | 0.6%    |
| SK hynix PC711 HFS512GDE9X073N 512GB                | 1         | 0.6%    |
| SK hynix HFS128G3BTND-N210A 128GB SSD               | 1         | 0.6%    |
| SK hynix BC711 NVMe 512GB                           | 1         | 0.6%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 19        | 21     | 47.5%   |
| Toshiba             | 9         | 9      | 22.5%   |
| WDC                 | 4         | 4      | 10%     |
| HGST                | 4         | 4      | 10%     |
| Hitachi             | 2         | 2      | 5%      |
| Unknown             | 1         | 1      | 2.5%    |
| Samsung Electronics | 1         | 1      | 2.5%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 13     | 21.57%  |
| Crucial             | 4         | 4      | 7.84%   |
| Transcend           | 3         | 3      | 5.88%   |
| Kingston            | 3         | 3      | 5.88%   |
| Apple               | 3         | 3      | 5.88%   |
| Apacer              | 3         | 3      | 5.88%   |
| SanDisk             | 2         | 2      | 3.92%   |
| OWC                 | 2         | 2      | 3.92%   |
| LITEONIT            | 2         | 2      | 3.92%   |
| Intel               | 2         | 2      | 3.92%   |
| WDC                 | 1         | 1      | 1.96%   |
| Vaseky              | 1         | 1      | 1.96%   |
| SK hynix            | 1         | 1      | 1.96%   |
| SAGE                | 1         | 1      | 1.96%   |
| S3+                 | 1         | 1      | 1.96%   |
| Plextor             | 1         | 1      | 1.96%   |
| OSCOO               | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| LITEON              | 1         | 1      | 1.96%   |
| KingFast            | 1         | 1      | 1.96%   |
| Intenso             | 1         | 1      | 1.96%   |
| GOODRAM             | 1         | 1      | 1.96%   |
| Emtec               | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| Biostar             | 1         | 1      | 1.96%   |
| A-DATA Technology   | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 59        | 75     | 40.41%  |
| SSD     | 44        | 53     | 30.14%  |
| HDD     | 37        | 42     | 25.34%  |
| MMC     | 4         | 4      | 2.74%   |
| Unknown | 2         | 2      | 1.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 69        | 88     | 48.94%  |
| NVMe | 59        | 74     | 41.84%  |
| SAS  | 9         | 10     | 6.38%   |
| MMC  | 4         | 4      | 2.84%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 41        | 50     | 50.62%  |
| 0.51-1.0   | 39        | 44     | 48.15%  |
| 1.01-2.0   | 1         | 1      | 1.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 25        | 21.01%  |
| 251-500        | 23        | 19.33%  |
| More than 3000 | 15        | 12.61%  |
| 501-1000       | 15        | 12.61%  |
| 1001-2000      | 14        | 11.76%  |
| 51-100         | 9         | 7.56%   |
| Unknown        | 8         | 6.72%   |
| 2001-3000      | 4         | 3.36%   |
| 21-50          | 3         | 2.52%   |
| 1-20           | 3         | 2.52%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 33        | 27.5%   |
| 21-50          | 23        | 19.17%  |
| 51-100         | 19        | 15.83%  |
| 101-250        | 18        | 15%     |
| 251-500        | 8         | 6.67%   |
| Unknown        | 8         | 6.67%   |
| 2001-3000      | 4         | 3.33%   |
| 501-1000       | 4         | 3.33%   |
| More than 3000 | 2         | 1.67%   |
| 1001-2000      | 1         | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                           | Notebooks | Drives | Percent |
|-----------------------------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB                                          | 1         | 1      | 4.76%   |
| Toshiba MQ04ABF100 1TB                                          | 1         | 1      | 4.76%   |
| Toshiba MQ01ABF050M 500GB                                       | 1         | 1      | 4.76%   |
| Toshiba MQ01ABF050 500GB                                        | 1         | 1      | 4.76%   |
| Toshiba MK3261GSY 320GB                                         | 1         | 1      | 4.76%   |
| Toshiba MK2555GSX 250GB                                         | 1         | 1      | 4.76%   |
| SK hynix HFS128G3BTND-N210A 128GB SSD                           | 1         | 1      | 4.76%   |
| SK hynix BC711 HFM512GD3JX013N 512GB                            | 1         | 1      | 4.76%   |
| Seagate ST9500325AS 500GB                                       | 1         | 1      | 4.76%   |
| Seagate ST500LT012-1DG142 500GB                                 | 1         | 1      | 4.76%   |
| Seagate ST500LM000-SSHD-8GB                                     | 1         | 1      | 4.76%   |
| Seagate ST1000LM049-2GH172 1TB                                  | 1         | 1      | 4.76%   |
| Seagate ST1000LM048-2E7172 1TB                                  | 1         | 1      | 4.76%   |
| Seagate ST1000LM035-1RK172 1TB                                  | 1         | 1      | 4.76%   |
| Samsung Electronics NVMe SSD Controller SM961/PM961/SM963 256GB | 1         | 1      | 4.76%   |
| Samsung Electronics HM100UI 1TB                                 | 1         | 1      | 4.76%   |
| LITEONIT DMT-80M6M-11 mSATA 80GB SSD                            | 1         | 1      | 4.76%   |
| Hitachi HTS547575A9E384 752GB                                   | 1         | 1      | 4.76%   |
| HGST HTS725032A7E630 320GB                                      | 1         | 1      | 4.76%   |
| HGST HTS721010A9E630 1TB                                        | 1         | 1      | 4.76%   |
| Crucial CT480BX200SSD1 480GB                                    | 1         | 1      | 4.76%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 28.57%  |
| Toshiba             | 5         | 5      | 23.81%  |
| SK hynix            | 2         | 2      | 9.52%   |
| Samsung Electronics | 2         | 2      | 9.52%   |
| HGST                | 2         | 2      | 9.52%   |
| WDC                 | 1         | 1      | 4.76%   |
| LITEONIT            | 1         | 1      | 4.76%   |
| Hitachi             | 1         | 1      | 4.76%   |
| Crucial             | 1         | 1      | 4.76%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 6      | 37.5%   |
| Toshiba             | 5         | 5      | 31.25%  |
| HGST                | 2         | 2      | 12.5%   |
| WDC                 | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Hitachi             | 1         | 1      | 6.25%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 16        | 16     | 76.19%  |
| SSD  | 3         | 3      | 14.29%  |
| NVMe | 2         | 2      | 9.52%   |

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
| Works    | 86        | 118    | 65.65%  |
| Detected | 25        | 37     | 19.08%  |
| Malfunc  | 20        | 21     | 15.27%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 85        | 54.14%  |
| Samsung Electronics          | 18        | 11.46%  |
| AMD                          | 11        | 7.01%   |
| SanDisk                      | 8         | 5.1%    |
| SK hynix                     | 6         | 3.82%   |
| Toshiba America Info Systems | 5         | 3.18%   |
| Kingston Technology Company  | 5         | 3.18%   |
| Micron Technology            | 4         | 2.55%   |
| KIOXIA                       | 4         | 2.55%   |
| Shenzhen Longsys Electronics | 2         | 1.27%   |
| Phison Electronics           | 2         | 1.27%   |
| Nvidia                       | 2         | 1.27%   |
| Seagate Technology           | 1         | 0.64%   |
| Realtek Semiconductor        | 1         | 0.64%   |
| Micron/Crucial Technology    | 1         | 0.64%   |
| Marvell Technology Group     | 1         | 0.64%   |
| ADATA Technology             | 1         | 0.64%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 11        | 6.63%   |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 6.02%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 8         | 4.82%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 4.82%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 8         | 4.82%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 4.22%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 4.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 7         | 4.22%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 5         | 3.01%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 5         | 3.01%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 5         | 3.01%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 4         | 2.41%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 2.41%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 4         | 2.41%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 2.41%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 3         | 1.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.81%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.81%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.2%    |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 1.2%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 1.2%    |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                          | 2         | 1.2%    |
| SanDisk PC SN520 NVMe SSD                                                      | 2         | 1.2%    |
| Samsung S4LN053X01 AHCI SSD Controller(Apple slot)                             | 2         | 1.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 1.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 2         | 1.2%    |
| Phison E12 NVMe Controller                                                     | 2         | 1.2%    |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 1.2%    |
| Micron 2200S NVMe SSD [Cassandra]                                              | 2         | 1.2%    |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 1.2%    |
| Intel SSD 660P Series                                                          | 2         | 1.2%    |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 2         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 1.2%    |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 1.2%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.2%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.2%    |
| Toshiba America Info Systems XG4 NVMe SSD Controller                           | 1         | 0.6%    |
| SK hynix PC601 NVMe Solid State Drive                                          | 1         | 0.6%    |
| Shenzhen Longsys Non-Volatile memory controller                                | 1         | 0.6%    |
| Shenzhen Longsys Lexar NM760 NVME SSD (DRAM-less)                              | 1         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 82        | 50.93%  |
| NVMe | 59        | 36.65%  |
| RAID | 20        | 12.42%  |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 97        | 82.91%  |
| AMD    | 20        | 17.09%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 3.42%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 4         | 3.42%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 3.42%   |
| Intel Core i7-7820HQ CPU @ 2.90GHz            | 3         | 2.56%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 2.56%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 3         | 2.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.56%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 2.56%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 3         | 2.56%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 2         | 1.71%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 1.71%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 1.71%   |
| Intel Core i7-4712HQ CPU @ 2.30GHz            | 2         | 1.71%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.71%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.71%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.71%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 2         | 1.71%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 2         | 1.71%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.71%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 1.71%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 1.71%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 1.71%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 2         | 1.71%   |
| Intel Xeon E-2176M CPU @ 2.70GHz              | 1         | 0.85%   |
| Intel Processor 5Y70 CPU @ 1.10GHz            | 1         | 0.85%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.85%   |
| Intel Pentium CPU 4415U @ 2.30GHz             | 1         | 0.85%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1         | 0.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.85%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.85%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.85%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.85%   |
| Intel Core i7-4960HQ CPU @ 2.60GHz            | 1         | 0.85%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz            | 1         | 0.85%   |
| Intel Core i7-4702HQ CPU @ 2.20GHz            | 1         | 0.85%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 1         | 0.85%   |
| Intel Core i7-4650U CPU @ 1.70GHz             | 1         | 0.85%   |
| Intel Core i7-3720QM CPU @ 2.60GHz            | 1         | 0.85%   |
| Intel Core i7-2760QM CPU @ 2.40GHz            | 1         | 0.85%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 33        | 28.21%  |
| Intel Core i7           | 32        | 27.35%  |
| Other                   | 15        | 12.82%  |
| AMD Ryzen 5             | 10        | 8.55%   |
| Intel Core i3           | 8         | 6.84%   |
| AMD Ryzen 7             | 5         | 4.27%   |
| Intel Core 2 Duo        | 3         | 2.56%   |
| Intel Celeron           | 3         | 2.56%   |
| AMD Ryzen 3             | 3         | 2.56%   |
| Intel Xeon              | 1         | 0.85%   |
| Intel Pentium Dual-Core | 1         | 0.85%   |
| Intel Pentium           | 1         | 0.85%   |
| AMD A6                  | 1         | 0.85%   |
| AMD A4                  | 1         | 0.85%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 49        | 41.88%  |
| 4      | 48        | 41.03%  |
| 6      | 13        | 11.11%  |
| 8      | 6         | 5.13%   |
| 14     | 1         | 0.85%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 117       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 106       | 89.83%  |
| 1      | 12        | 10.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 117       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 48.74%  |
| 0x806c1    | 7         | 5.88%   |
| 0x806ec    | 6         | 5.04%   |
| 0x906ea    | 4         | 3.36%   |
| 0x306a9    | 4         | 3.36%   |
| 0x906e9    | 3         | 2.52%   |
| 0x806e9    | 3         | 2.52%   |
| 0x206a7    | 3         | 2.52%   |
| 0x08108109 | 3         | 2.52%   |
| 0x806eb    | 2         | 1.68%   |
| 0x706a8    | 2         | 1.68%   |
| 0x40651    | 2         | 1.68%   |
| 0x08108102 | 2         | 1.68%   |
| 0xa0652    | 1         | 0.84%   |
| 0x906ed    | 1         | 0.84%   |
| 0x906eb    | 1         | 0.84%   |
| 0x906a3    | 1         | 0.84%   |
| 0x806d1    | 1         | 0.84%   |
| 0x706e5    | 1         | 0.84%   |
| 0x406e3    | 1         | 0.84%   |
| 0x40661    | 1         | 0.84%   |
| 0x306d4    | 1         | 0.84%   |
| 0x306c3    | 1         | 0.84%   |
| 0x20652    | 1         | 0.84%   |
| 0x1067a    | 1         | 0.84%   |
| 0x0a404102 | 1         | 0.84%   |
| 0x0a404101 | 1         | 0.84%   |
| 0x08608104 | 1         | 0.84%   |
| 0x08608103 | 1         | 0.84%   |
| 0x08600106 | 1         | 0.84%   |
| 0x0810100b | 1         | 0.84%   |
| 0x06006705 | 1         | 0.84%   |
| 0x03000027 | 1         | 0.84%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 26.5%   |
| Haswell          | 13        | 11.11%  |
| TigerLake        | 11        | 9.4%    |
| Broadwell        | 8         | 6.84%   |
| IvyBridge        | 7         | 5.98%   |
| IceLake          | 7         | 5.98%   |
| Zen+             | 6         | 5.13%   |
| SandyBridge      | 5         | 4.27%   |
| Zen 2            | 4         | 3.42%   |
| Penryn           | 4         | 3.42%   |
| Unknown          | 4         | 3.42%   |
| Zen 3            | 3         | 2.56%   |
| Skylake          | 3         | 2.56%   |
| Goldmont plus    | 3         | 2.56%   |
| Westmere         | 2         | 1.71%   |
| CometLake        | 2         | 1.71%   |
| Zen              | 1         | 0.85%   |
| K10 Llano        | 1         | 0.85%   |
| Excavator        | 1         | 0.85%   |
| Alderlake Hybrid | 1         | 0.85%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 94        | 55.62%  |
| Nvidia | 52        | 30.77%  |
| AMD    | 23        | 13.61%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 4.12%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 6         | 3.53%   |
| Intel HD Graphics 5500                                                    | 6         | 3.53%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 6         | 3.53%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 6         | 3.53%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 3.53%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 6         | 3.53%   |
| Intel UHD Graphics 620                                                    | 5         | 2.94%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 5         | 2.94%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 2.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 4         | 2.35%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 4         | 2.35%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 4         | 2.35%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 4         | 2.35%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 4         | 2.35%   |
| Intel HD Graphics 630                                                     | 4         | 2.35%   |
| Intel HD Graphics 620                                                     | 4         | 2.35%   |
| Nvidia GP108M [GeForce MX150]                                             | 3         | 1.76%   |
| Nvidia GK107GLM [Quadro K1100M]                                           | 3         | 1.76%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.76%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 1.76%   |
| AMD Renoir                                                                | 3         | 1.76%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                | 2         | 1.18%   |
| Nvidia GP108M [GeForce MX250]                                             | 2         | 1.18%   |
| Nvidia GM108M [GeForce 940MX]                                             | 2         | 1.18%   |
| Nvidia GF108GLM [NVS 5200M]                                               | 2         | 1.18%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 1.18%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller              | 2         | 1.18%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.18%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 2         | 1.18%   |
| AMD Rembrandt [Radeon 680M]                                               | 2         | 1.18%   |
| AMD Lucienne                                                              | 2         | 1.18%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520/610 Mobile]          | 2         | 1.18%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 2         | 1.18%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.59%   |
| Nvidia TU117M                                                             | 1         | 0.59%   |
| Nvidia TU116M [GeForce GTX 1650 Ti Mobile]                                | 1         | 0.59%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 1         | 0.59%   |
| Nvidia TU106BM [GeForce RTX 2070 Mobile / Max-Q]                          | 1         | 0.59%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 47        | 40.17%  |
| Intel + Nvidia | 41        | 35.04%  |
| 1 x AMD        | 11        | 9.4%    |
| AMD + Nvidia   | 7         | 5.98%   |
| 1 x Nvidia     | 4         | 3.42%   |
| Intel + AMD    | 4         | 3.42%   |
| 2 x Intel      | 2         | 1.71%   |
| 2 x AMD        | 1         | 0.85%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 89        | 74.79%  |
| Proprietary | 30        | 25.21%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 84        | 71.19%  |
| 1.01-2.0   | 13        | 11.02%  |
| 0.01-0.5   | 9         | 7.63%   |
| 3.01-4.0   | 6         | 5.08%   |
| 5.01-6.0   | 3         | 2.54%   |
| 2.01-3.0   | 2         | 1.69%   |
| 0.51-1.0   | 1         | 0.85%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| BOE                 | 30        | 22.22%  |
| AU Optronics        | 28        | 20.74%  |
| LG Display          | 19        | 14.07%  |
| Chimei Innolux      | 17        | 12.59%  |
| Samsung Electronics | 12        | 8.89%   |
| Apple               | 7         | 5.19%   |
| Sharp               | 3         | 2.22%   |
| PANDA               | 3         | 2.22%   |
| TMX                 | 2         | 1.48%   |
| Dell                | 2         | 1.48%   |
| BenQ                | 2         | 1.48%   |
| Yamaha              | 1         | 0.74%   |
| Toshiba             | 1         | 0.74%   |
| Sceptre Tech        | 1         | 0.74%   |
| LGD                 | 1         | 0.74%   |
| Lenovo              | 1         | 0.74%   |
| ITE                 | 1         | 0.74%   |
| Hewlett-Packard     | 1         | 0.74%   |
| Goldstar            | 1         | 0.74%   |
| CSO                 | 1         | 0.74%   |
| Acer                | 1         | 0.74%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 2.22%   |
| Samsung Electronics LCD Monitor SAM0F14 3840x2160 1872x1053mm 84.6-inch | 2         | 1.48%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch            | 2         | 1.48%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch         | 2         | 1.48%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 2         | 1.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 1.48%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                   | 2         | 1.48%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 2         | 1.48%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch           | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch          | 2         | 1.48%   |
| Yamaha RX-V473 YMH3171 1920x540                                         | 1         | 0.74%   |
| Toshiba TV TSB0205 1360x768 886x498mm 40.0-inch                         | 1         | 0.74%   |
| TMX TL156VDXP0101 TMX1561 1920x1080 344x194mm 15.5-inch                 | 1         | 0.74%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 0.74%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 0.74%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                 | 1         | 0.74%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                 | 1         | 0.74%   |
| Sceptre Tech C27 SPT0ADD 1920x1080 598x336mm 27.0-inch                  | 1         | 0.74%   |
| Samsung Electronics SMBX2450L SAM071F 1920x1080 521x293mm 23.5-inch     | 1         | 0.74%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch       | 1         | 0.74%   |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch       | 1         | 0.74%   |
| Samsung Electronics S22C450 SAM09C7 1680x1050 473x291mm 21.9-inch       | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 344x194mm 15.5-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC434A 3200x1800 293x165mm 13.2-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SDC200F 1366x768 344x193mm 15.5-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 950x540mm 43.0-inch   | 1         | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 1         | 0.74%   |
| PANDA LCD Monitor NCP0063 1920x1080 344x194mm 15.5-inch                 | 1         | 0.74%   |
| PANDA LCD Monitor NCP0050 1920x1080 309x174mm 14.0-inch                 | 1         | 0.74%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch                 | 1         | 0.74%   |
| LGD LCD Monitor 1920x1080                                               | 1         | 0.74%   |
| LG Display LCD Monitor LGD6E01 1366x768 344x194mm 15.5-inch             | 1         | 0.74%   |
| LG Display LCD Monitor LGD05FE 1920x1080 344x194mm 15.5-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD05F2 1920x1080 344x194mm 15.5-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD057E 1920x1080 344x194mm 15.5-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 0.74%   |
| LG Display LCD Monitor LGD0533 1920x1080 344x194mm 15.5-inch            | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 75        | 58.14%  |
| 1366x768 (WXGA)    | 25        | 19.38%  |
| 3840x2160 (4K)     | 6         | 4.65%   |
| 1600x900 (HD+)     | 6         | 4.65%   |
| 1280x800 (WXGA)    | 3         | 2.33%   |
| 3200x1800 (QHD+)   | 2         | 1.55%   |
| 2560x1600          | 2         | 1.55%   |
| 3840x2400          | 1         | 0.78%   |
| 3200x2000          | 1         | 0.78%   |
| 2880x1800          | 1         | 0.78%   |
| 2560x1440 (QHD)    | 1         | 0.78%   |
| 2560x1080          | 1         | 0.78%   |
| 2160x1440          | 1         | 0.78%   |
| 1920x540           | 1         | 0.78%   |
| 1920x1200 (WUXGA)  | 1         | 0.78%   |
| 1680x1050 (WSXGA+) | 1         | 0.78%   |
| 1440x900 (WXGA+)   | 1         | 0.78%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 64        | 47.76%  |
| 13      | 21        | 15.67%  |
| 14      | 17        | 12.69%  |
| 17      | 8         | 5.97%   |
| 23      | 5         | 3.73%   |
| 84      | 3         | 2.24%   |
| 21      | 3         | 2.24%   |
| 31      | 2         | 1.49%   |
| 27      | 2         | 1.49%   |
| 16      | 2         | 1.49%   |
| Unknown | 2         | 1.49%   |
| 72      | 1         | 0.75%   |
| 28      | 1         | 0.75%   |
| 24      | 1         | 0.75%   |
| 18      | 1         | 0.75%   |
| 12      | 1         | 0.75%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 93        | 68.89%  |
| 201-300     | 11        | 8.15%   |
| 351-400     | 9         | 6.67%   |
| 501-600     | 8         | 5.93%   |
| 401-500     | 5         | 3.7%    |
| 1501-2000   | 4         | 2.96%   |
| 601-700     | 3         | 2.22%   |
| Unknown     | 2         | 1.48%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 105       | 88.24%  |
| 16/10   | 10        | 8.4%    |
| 32/9    | 1         | 0.84%   |
| 3/2     | 1         | 0.84%   |
| 21/9    | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 65        | 48.87%  |
| 81-90          | 32        | 24.06%  |
| 121-130        | 8         | 6.02%   |
| 201-250        | 7         | 5.26%   |
| 71-80          | 6         | 4.51%   |
| More than 1000 | 4         | 3.01%   |
| 351-500        | 2         | 1.5%    |
| 301-350        | 2         | 1.5%    |
| Unknown        | 2         | 1.5%    |
| 61-70          | 1         | 0.75%   |
| 251-300        | 1         | 0.75%   |
| 151-200        | 1         | 0.75%   |
| 141-150        | 1         | 0.75%   |
| 111-120        | 1         | 0.75%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 69        | 52.27%  |
| 101-120       | 32        | 24.24%  |
| 51-100        | 14        | 10.61%  |
| 161-240       | 8         | 6.06%   |
| More than 240 | 6         | 4.55%   |
| Unknown       | 2         | 1.52%   |
| 1-50          | 1         | 0.76%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 98        | 83.76%  |
| 2     | 17        | 14.53%  |
| 3     | 2         | 1.71%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 66        | 37.93%  |
| Realtek Semiconductor             | 58        | 33.33%  |
| Qualcomm Atheros                  | 13        | 7.47%   |
| Broadcom Limited                  | 7         | 4.02%   |
| Broadcom                          | 6         | 3.45%   |
| MediaTek                          | 5         | 2.87%   |
| TP-Link                           | 3         | 1.72%   |
| ASIX Electronics                  | 3         | 1.72%   |
| Sierra Wireless                   | 2         | 1.15%   |
| Samsung Electronics               | 2         | 1.15%   |
| Nvidia                            | 2         | 1.15%   |
| Ericsson Business Mobile Networks | 2         | 1.15%   |
| Ralink Technology                 | 1         | 0.57%   |
| Ralink                            | 1         | 0.57%   |
| Marvell Technology Group          | 1         | 0.57%   |
| Huawei Technologies               | 1         | 0.57%   |
| Dell                              | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                              | Notebooks | Percent |
|--------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller  | 40        | 18.69%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter           | 8         | 3.74%   |
| Intel Wi-Fi 6 AX201                                                | 8         | 3.74%   |
| Intel Wireless 8265 / 8275                                         | 7         | 3.27%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)              | 7         | 3.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                           | 6         | 2.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller              | 5         | 2.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter         | 5         | 2.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter      | 5         | 2.34%   |
| Intel Wireless 7260                                                | 5         | 2.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                           | 5         | 2.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                    | 5         | 2.34%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter           | 4         | 1.87%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                       | 4         | 1.87%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                    | 3         | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter         | 3         | 1.4%    |
| Intel Wireless 7265                                                | 3         | 1.4%    |
| Intel Wi-Fi 6 AX200                                                | 3         | 1.4%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                    | 3         | 1.4%    |
| Intel Ethernet Connection (4) I219-LM                              | 3         | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                  | 3         | 1.4%    |
| Intel Centrino Wireless-N 2230                                     | 3         | 1.4%    |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter         | 3         | 1.4%    |
| ASIX AX88179 Gigabit Ethernet                                      | 3         | 1.4%    |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                        | 2         | 0.93%   |
| Sierra Wireless EM7455                                             | 2         | 0.93%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)        | 2         | 0.93%   |
| Intel Wireless 8260                                                | 2         | 0.93%   |
| Intel Ethernet Connection (5) I219-LM                              | 2         | 0.93%   |
| Intel Ethernet Connection (3) I218-V                               | 2         | 0.93%   |
| Intel Centrino Ultimate-N 6300                                     | 2         | 0.93%   |
| Ericsson Business Mobile Networks H5321 gw Mobile Broadband Module | 2         | 0.93%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter         | 2         | 0.93%   |
| TP-Link 802.11ac NIC                                               | 1         | 0.47%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                     | 1         | 0.47%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter           | 1         | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                    | 1         | 0.47%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter           | 1         | 0.47%   |
| Realtek RTL8723DE Wireless Network Adapter                         | 1         | 0.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                         | 1         | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 65        | 53.72%  |
| Realtek Semiconductor | 21        | 17.36%  |
| Qualcomm Atheros      | 11        | 9.09%   |
| Broadcom Limited      | 6         | 4.96%   |
| MediaTek              | 5         | 4.13%   |
| Broadcom              | 5         | 4.13%   |
| TP-Link               | 3         | 2.48%   |
| Sierra Wireless       | 2         | 1.65%   |
| Ralink Technology     | 1         | 0.83%   |
| Ralink                | 1         | 0.83%   |
| Dell                  | 1         | 0.83%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 8         | 6.61%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 6.61%   |
| Intel Wireless 8265 / 8275                                     | 7         | 5.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 4.13%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 5         | 4.13%   |
| Intel Wireless 7260                                            | 5         | 4.13%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 5         | 4.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 4.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 3.31%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 4         | 3.31%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 2.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 3         | 2.48%   |
| Intel Wireless 7265                                            | 3         | 2.48%   |
| Intel Wi-Fi 6 AX200                                            | 3         | 2.48%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 2.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.48%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 2.48%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 3         | 2.48%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 2         | 1.65%   |
| Sierra Wireless EM7455                                         | 2         | 1.65%   |
| Intel Wireless 8260                                            | 2         | 1.65%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 1.65%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 1.65%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.83%   |
| Realtek RTL8852AE WiFi 6 802.11ax PCIe Adapter                 | 1         | 0.83%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 1         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.83%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.83%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.83%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.83%   |
| Ralink RT5572 Wireless Adapter                                 | 1         | 0.83%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.83%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 1         | 0.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 0.83%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 0.83%   |
| Intel Wireless-AC 9260                                         | 1         | 0.83%   |
| Intel Wireless 3165                                            | 1         | 0.83%   |
| Intel Wireless 3160                                            | 1         | 0.83%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 1         | 0.83%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 50        | 57.47%  |
| Intel                    | 24        | 27.59%  |
| Qualcomm Atheros         | 3         | 3.45%   |
| ASIX Electronics         | 3         | 3.45%   |
| Nvidia                   | 2         | 2.3%    |
| Broadcom                 | 2         | 2.3%    |
| Marvell Technology Group | 1         | 1.15%   |
| Huawei Technologies      | 1         | 1.15%   |
| Broadcom Limited         | 1         | 1.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 40        | 44.94%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 7.87%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 6.74%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.62%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 3.37%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 3.37%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 2.25%   |
| Intel Ethernet Connection (3) I218-V                              | 2         | 2.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.12%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 1.12%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 1.12%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 1.12%   |
| Nvidia MCP89 Ethernet                                             | 1         | 1.12%   |
| Nvidia MCP79 Ethernet                                             | 1         | 1.12%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 1         | 1.12%   |
| Intel Ethernet Connection I219-V                                  | 1         | 1.12%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.12%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.12%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 1.12%   |
| Intel Ethernet Connection (6) I219-V                              | 1         | 1.12%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 1.12%   |
| Intel Ethernet Connection (16) I219-LM                            | 1         | 1.12%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.12%   |
| Intel Ethernet Connection (13) I219-LM                            | 1         | 1.12%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.12%   |
| Huawei WLZ-AN00                                                   | 1         | 1.12%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 1         | 1.12%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 1         | 1.12%   |
| Broadcom Limited NetXtreme BCM57760 Gigabit Ethernet PCIe         | 1         | 1.12%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 114       | 56.16%  |
| Ethernet | 85        | 41.87%  |
| Modem    | 4         | 1.97%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 98        | 82.35%  |
| Ethernet | 21        | 17.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 74        | 63.25%  |
| 1     | 42        | 35.9%   |
| 0     | 1         | 0.85%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 72        | 61.54%  |
| Yes  | 45        | 38.46%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 52        | 50%     |
| Realtek Semiconductor           | 14        | 13.46%  |
| IMC Networks                    | 9         | 8.65%   |
| Broadcom                        | 6         | 5.77%   |
| Apple                           | 6         | 5.77%   |
| Qualcomm Atheros Communications | 5         | 4.81%   |
| Foxconn / Hon Hai               | 5         | 4.81%   |
| Lite-On Technology              | 4         | 3.85%   |
| Toshiba                         | 1         | 0.96%   |
| Realtek                         | 1         | 0.96%   |
| Dell                            | 1         | 0.96%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)  | 18        | 17.31%  |
| Intel Bluetooth wireless interface              | 16        | 15.38%  |
| Realtek Bluetooth Radio                         | 10        | 9.62%   |
| Intel AX201 Bluetooth                           | 10        | 9.62%   |
| Qualcomm Atheros  Bluetooth Device              | 5         | 4.81%   |
| Apple Bluetooth Host Controller                 | 5         | 4.81%   |
| IMC Networks Wireless_Device                    | 4         | 3.85%   |
| IMC Networks Bluetooth Radio                    | 4         | 3.85%   |
| Realtek  Bluetooth 4.2 Adapter                  | 3         | 2.88%   |
| Intel Centrino Bluetooth Wireless Transceiver   | 3         | 2.88%   |
| Intel AX200 Bluetooth                           | 3         | 2.88%   |
| Lite-On Atheros AR3012 Bluetooth                | 2         | 1.92%   |
| Broadcom BCM20702A0 Bluetooth                   | 2         | 1.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]      | 2         | 1.92%   |
| Toshiba Integrated Bluetooth HCI                | 1         | 0.96%   |
| Realtek RTL8821A Bluetooth                      | 1         | 0.96%   |
| Realtek 802.11ac WLAN Adapter                   | 1         | 0.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth      | 1         | 0.96%   |
| Lite-On Bluetooth Device                        | 1         | 0.96%   |
| Intel Wireless-AC 9260 Bluetooth Adapter        | 1         | 0.96%   |
| Intel AX210 Bluetooth                           | 1         | 0.96%   |
| IMC Networks BCM20702A0                         | 1         | 0.96%   |
| Foxconn / Hon Hai Wireless_Device               | 1         | 0.96%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter    | 1         | 0.96%   |
| Foxconn / Hon Hai Broadcom BCM20702A1 Bluetooth | 1         | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device              | 1         | 0.96%   |
| Foxconn / Hon Hai Acer Bluetooth module         | 1         | 0.96%   |
| Dell BCM20702A0 Bluetooth Module                | 1         | 0.96%   |
| Broadcom BCM2045B (BDC-2.1)                     | 1         | 0.96%   |
| Broadcom BCM2045A0                              | 1         | 0.96%   |
| Apple Bluetooth USB Host Controller             | 1         | 0.96%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Intel                      | 95        | 62.5%   |
| Nvidia                     | 28        | 18.42%  |
| AMD                        | 20        | 13.16%  |
| GN Netcom                  | 2         | 1.32%   |
| Samsung Electronics        | 1         | 0.66%   |
| Realtek Semiconductor      | 1         | 0.66%   |
| PreSonus Audio Electronics | 1         | 0.66%   |
| Lenovo                     | 1         | 0.66%   |
| JMTek                      | 1         | 0.66%   |
| Barco Display Systems      | 1         | 0.66%   |
| ASUSTek Computer           | 1         | 0.66%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 9.04%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 6.38%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 11        | 5.85%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 4.26%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 4.26%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 4.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 8         | 4.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 3.72%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 3.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 6         | 3.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 3.19%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 6         | 3.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 3.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2.66%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 5         | 2.66%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 2.13%   |
| Nvidia GA106 High Definition Audio Controller                              | 4         | 2.13%   |
| Intel CM238 HD Audio Controller                                            | 4         | 2.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 2.13%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 1.6%    |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.6%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.6%    |
| Nvidia TU106 High Definition Audio Controller                              | 2         | 1.06%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 1.06%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.06%   |
| Nvidia Audio device                                                        | 2         | 1.06%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 1.06%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.06%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 1.06%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 2         | 1.06%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 2         | 1.06%   |
| Samsung Electronics USBC Headset                                           | 1         | 0.53%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.53%   |
| PreSonus Audio Electronics AudioBox USB 96                                 | 1         | 0.53%   |
| Nvidia MCP89 High Definition Audio                                         | 1         | 0.53%   |
| Nvidia MCP79 High Definition Audio                                         | 1         | 0.53%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.53%   |
| Nvidia GP104 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia GM206 High Definition Audio Controller                              | 1         | 0.53%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 1         | 0.53%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 38        | 30.16%  |
| SK hynix            | 37        | 29.37%  |
| Micron Technology   | 19        | 15.08%  |
| Crucial             | 10        | 7.94%   |
| Kingston            | 7         | 5.56%   |
| Ramaxel Technology  | 6         | 4.76%   |
| Unknown             | 3         | 2.38%   |
| Timetec             | 1         | 0.79%   |
| Team                | 1         | 0.79%   |
| Nanya Technology    | 1         | 0.79%   |
| KingFast            | 1         | 0.79%   |
| Elpida              | 1         | 0.79%   |
| Corsair             | 1         | 0.79%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 5         | 3.82%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 5         | 3.82%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 4         | 3.05%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s        | 4         | 3.05%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                 | 2         | 1.53%   |
| SK hynix RAM HMT451S6MFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 2         | 1.53%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 1.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 1.53%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 2         | 1.53%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s      | 2         | 1.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s       | 2         | 1.53%   |
| SK hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s       | 2         | 1.53%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 1.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 2         | 1.53%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.53%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s     | 2         | 1.53%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s        | 2         | 1.53%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 1.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s        | 2         | 1.53%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s    | 2         | 1.53%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s    | 2         | 1.53%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s  | 2         | 1.53%   |
| Micron RAM 4ATF51264HZ-2G3E1 4GB SODIMM DDR4 2667MT/s        | 2         | 1.53%   |
| Unknown RAM Module 8GB SODIMM DDR3 1067MT/s                  | 1         | 0.76%   |
| Unknown RAM Module 4GB SODIMM LPDDR3 1600MT/s                | 1         | 0.76%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                    | 1         | 0.76%   |
| Timetec RAM Module 4GB SODIMM DDR3 1067MT/s                  | 1         | 0.76%   |
| Team RAM TEAMGROUP-SD4-2400 8GB SODIMM DDR4 8400MT/s         | 1         | 0.76%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2133MT/s                | 1         | 0.76%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.76%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.76%   |
| SK hynix RAM HMT41GS6MFR8C-PB 8GB SODIMM DDR3 1600MT/s       | 1         | 0.76%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 1         | 0.76%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s       | 1         | 0.76%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s       | 1         | 0.76%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB Row Of Chips DDR4 3200MT/s | 1         | 0.76%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 1         | 0.76%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 1         | 0.76%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2667MT/s    | 1         | 0.76%   |
| SK hynix RAM HMA851S6AFR6N-UH 4096MB SODIMM DDR4 2400MT/s    | 1         | 0.76%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 60        | 58.82%  |
| DDR3   | 30        | 29.41%  |
| LPDDR4 | 3         | 2.94%   |
| LPDDR3 | 3         | 2.94%   |
| DDR5   | 2         | 1.96%   |
| SDRAM  | 1         | 0.98%   |
| LPDDR5 | 1         | 0.98%   |
| DDR2   | 1         | 0.98%   |
| DDR    | 1         | 0.98%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 92        | 88.46%  |
| Row Of Chips | 11        | 10.58%  |
| Chip         | 1         | 0.96%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 56        | 50%     |
| 4096  | 37        | 33.04%  |
| 16384 | 13        | 11.61%  |
| 2048  | 5         | 4.46%   |
| 32768 | 1         | 0.89%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 35        | 30.17%  |
| 3200    | 24        | 20.69%  |
| 1600    | 22        | 18.97%  |
| 1333    | 6         | 5.17%   |
| 3266    | 5         | 4.31%   |
| 2400    | 5         | 4.31%   |
| 2133    | 5         | 4.31%   |
| 1067    | 3         | 2.59%   |
| 4800    | 2         | 1.72%   |
| 4267    | 2         | 1.72%   |
| 800     | 2         | 1.72%   |
| 8400    | 1         | 0.86%   |
| 6400    | 1         | 0.86%   |
| 4199    | 1         | 0.86%   |
| 1334    | 1         | 0.86%   |
| Unknown | 1         | 0.86%   |

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
| Chicony Electronics                    | 25        | 23.15%  |
| IMC Networks                           | 22        | 20.37%  |
| Realtek Semiconductor                  | 12        | 11.11%  |
| Sunplus Innovation Technology          | 7         | 6.48%   |
| Syntek                                 | 6         | 5.56%   |
| Microdia                               | 6         | 5.56%   |
| Quanta                                 | 5         | 4.63%   |
| Bison Electronics                      | 5         | 4.63%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.7%    |
| Acer                                   | 4         | 3.7%    |
| Apple                                  | 3         | 2.78%   |
| Luxvisions Innotech Limited            | 2         | 1.85%   |
| Lite-On Technology                     | 2         | 1.85%   |
| Suyin                                  | 1         | 0.93%   |
| Sonix Technology                       | 1         | 0.93%   |
| Ricoh                                  | 1         | 0.93%   |
| Alpha Imaging Technology               | 1         | 0.93%   |
| Alcor Micro                            | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 8         | 7.34%   |
| Syntek Integrated Camera                             | 6         | 5.5%    |
| Chicony integrated camera                            | 6         | 5.5%    |
| Realtek Integrated_Webcam_HD                         | 5         | 4.59%   |
| IMC Networks Integrated Camera                       | 5         | 4.59%   |
| Quanta HP TrueVision HD Camera                       | 4         | 3.67%   |
| Microdia Integrated_Webcam_HD                        | 3         | 2.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 3         | 2.75%   |
| Acer Integrated Camera                               | 3         | 2.75%   |
| Realtek Integrated Webcam_HD                         | 2         | 1.83%   |
| Lite-On Integrated Camera                            | 2         | 1.83%   |
| Chicony HP TrueVision HD Camera                      | 2         | 1.83%   |
| Chicony HD WebCam                                    | 2         | 1.83%   |
| Chicony EasyCamera                                   | 2         | 1.83%   |
| Bison ThinkPad Integrated Camera                     | 2         | 1.83%   |
| Apple Built-in iSight                                | 2         | 1.83%   |
| Suyin Asus Integrated Webcam                         | 1         | 0.92%   |
| Sunplus XiaoMi USB 2.0 Webcam                        | 1         | 0.92%   |
| Sunplus Lenovo EasyCamera                            | 1         | 0.92%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 0.92%   |
| Sunplus Laptop Integrated Webcam FHD                 | 1         | 0.92%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 0.92%   |
| Sunplus Integrated_Webcam_FHD                        | 1         | 0.92%   |
| Sunplus HP Truevision HD                             | 1         | 0.92%   |
| Sonix USB2.0 HD UVC WebCam                           | 1         | 0.92%   |
| Ricoh Integrated Webcam                              | 1         | 0.92%   |
| Realtek USB2.0 HD UVC WebCam                         | 1         | 0.92%   |
| Realtek Integrated Webcam                            | 1         | 0.92%   |
| Realtek Integrated Camera                            | 1         | 0.92%   |
| Realtek EasyCamera                                   | 1         | 0.92%   |
| Realtek Built-In Video Camera                        | 1         | 0.92%   |
| Quanta HD User Facing                                | 1         | 0.92%   |
| Microdia USB 2.0 Camera                              | 1         | 0.92%   |
| Microdia Laptop_Integrated_Webcam_E4HD               | 1         | 0.92%   |
| Microdia Dell Integrated HD Webcam                   | 1         | 0.92%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.92%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 0.92%   |
| IMC Networks VGA UVC WebCam                          | 1         | 0.92%   |
| IMC Networks UVC VGA Webcam                          | 1         | 0.92%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 1         | 0.92%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 5         | 35.71%  |
| Synaptics                  | 4         | 28.57%  |
| Shenzhen Goodix Technology | 2         | 14.29%  |
| LighTuning Technology      | 1         | 7.14%   |
| Elan Microelectronics      | 1         | 7.14%   |
| AuthenTec                  | 1         | 7.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 2         | 14.29%  |
| Shenzhen Goodix  Fingerprint Device               | 2         | 14.29%  |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 7.14%   |
| Validity Sensors Synaptics WBDI                   | 1         | 7.14%   |
| Synaptics WBDI                                    | 1         | 7.14%   |
| Synaptics UWP WBDI                                | 1         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader | 1         | 7.14%   |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 7.14%   |
| LighTuning Fingerprint Reader                     | 1         | 7.14%   |
| Elan ELAN:Fingerprint                             | 1         | 7.14%   |
| AuthenTec Fingerprint Sensor                      | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Alcor Micro | 5         | 38.46%  |
| Broadcom    | 4         | 30.77%  |
| Upek        | 2         | 15.38%  |
| Yubico.com  | 1         | 7.69%   |
| Clay Logic  | 1         | 7.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 5         | 38.46%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 15.38%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 15.38%  |
| Yubico.com Yubikey NEO(-N) OTP+CCID                        | 1         | 7.69%   |
| Clay Logic Nitrokey Pro                                    | 1         | 7.69%   |
| Broadcom 5880                                              | 1         | 7.69%   |
| Broadcom 58200                                             | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 83        | 70.34%  |
| 1     | 26        | 22.03%  |
| 2     | 8         | 6.78%   |
| 3     | 1         | 0.85%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 14        | 31.82%  |
| Chipcard              | 11        | 25%     |
| Graphics card         | 10        | 22.73%  |
| Multimedia controller | 5         | 11.36%  |
| Camera                | 2         | 4.55%   |
| Storage               | 1         | 2.27%   |
| Network               | 1         | 2.27%   |

