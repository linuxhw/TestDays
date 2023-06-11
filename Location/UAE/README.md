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

Total: 256

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 32        | 18.29%  |
| Ubuntu 18.04       | 16        | 9.14%   |
| Ubuntu 22.04       | 13        | 7.43%   |
| Fedora 37          | 5         | 2.86%   |
| Debian 11          | 5         | 2.86%   |
| Arch               | 5         | 2.86%   |
| Zorin 16           | 4         | 2.29%   |
| Ubuntu 19.10       | 4         | 2.29%   |
| Pop!_OS 22.04      | 4         | 2.29%   |
| Linux Mint 20.3    | 4         | 2.29%   |
| Fedora 36          | 4         | 2.29%   |
| Zorin 15           | 3         | 1.71%   |
| Ubuntu 22.10       | 3         | 1.71%   |
| Ubuntu 20.10       | 3         | 1.71%   |
| Debian 10          | 3         | 1.71%   |
| Ubuntu 21.10       | 2         | 1.14%   |
| Ubuntu 16.04       | 2         | 1.14%   |
| SteamOS 3.4.6      | 2         | 1.14%   |
| Pop!_OS 20.10      | 2         | 1.14%   |
| Pop!_OS 20.04      | 2         | 1.14%   |
| OpenMandriva 4.3   | 2         | 1.14%   |
| OpenMandriva 23.01 | 2         | 1.14%   |
| Lubuntu 22.04      | 2         | 1.14%   |
| Linux Mint 21.1    | 2         | 1.14%   |
| Kubuntu 22.04      | 2         | 1.14%   |
| KDE neon 20.04     | 2         | 1.14%   |
| Kali 2023.1        | 2         | 1.14%   |
| Fedora 35          | 2         | 1.14%   |
| Fedora 34          | 2         | 1.14%   |
| BlackPanther 18.1  | 2         | 1.14%   |
| ArcoLinux Rolling  | 2         | 1.14%   |
| Xubuntu 20.04      | 1         | 0.57%   |
| Xubuntu 16.04      | 1         | 0.57%   |
| Ubuntu Unity 18.04 | 1         | 0.57%   |
| Ubuntu MATE 20.04  | 1         | 0.57%   |
| Ubuntu 23.04       | 1         | 0.57%   |
| Ubuntu 21.04       | 1         | 0.57%   |
| Ubuntu 19.04       | 1         | 0.57%   |
| SteamOS 3.4.8      | 1         | 0.57%   |
| SteamOS 3.4.4      | 1         | 0.57%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Ubuntu       | 76        | 44.44%  |
| Fedora       | 13        | 7.6%    |
| Pop!_OS      | 8         | 4.68%   |
| Linux Mint   | 8         | 4.68%   |
| Debian       | 8         | 4.68%   |
| Zorin        | 7         | 4.09%   |
| OpenMandriva | 6         | 3.51%   |
| Manjaro      | 6         | 3.51%   |
| Arch         | 6         | 3.51%   |
| SteamOS      | 5         | 2.92%   |
| KDE neon     | 3         | 1.75%   |
| Xubuntu      | 2         | 1.17%   |
| Lubuntu      | 2         | 1.17%   |
| Kubuntu      | 2         | 1.17%   |
| Kali         | 2         | 1.17%   |
| Endless      | 2         | 1.17%   |
| BlackPanther | 2         | 1.17%   |
| ArcoLinux    | 2         | 1.17%   |
| Ubuntu Unity | 1         | 0.58%   |
| Ubuntu MATE  | 1         | 0.58%   |
| ROSA         | 1         | 0.58%   |
| Rocky Linux  | 1         | 0.58%   |
| Reborn OS    | 1         | 0.58%   |
| GNOME OS     | 1         | 0.58%   |
| Feren OS     | 1         | 0.58%   |
| EndeavourOS  | 1         | 0.58%   |
| Elementary   | 1         | 0.58%   |
| CachyOS      | 1         | 0.58%   |
| Alpine       | 1         | 0.58%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                     | Computers | Percent |
|-----------------------------|-----------|---------|
| 5.4.0-42-generic            | 7         | 3.7%    |
| 5.4.0-58-generic            | 4         | 2.12%   |
| 5.4.0-26-generic            | 4         | 2.12%   |
| 5.13.0-valve36-1-neptune    | 4         | 2.12%   |
| 5.4.0-37-generic            | 3         | 1.59%   |
| 5.11.0-40-generic           | 3         | 1.59%   |
| 4.15.0-50-generic           | 3         | 1.59%   |
| 6.1.1-desktop-1omv2290      | 2         | 1.06%   |
| 6.0.6-76060006-generic      | 2         | 1.06%   |
| 5.8.0-40-generic            | 2         | 1.06%   |
| 5.4.0-81-generic            | 2         | 1.06%   |
| 5.4.0-48-generic            | 2         | 1.06%   |
| 5.4.0-33-generic            | 2         | 1.06%   |
| 5.4.0-29-generic            | 2         | 1.06%   |
| 5.3.0-40-generic            | 2         | 1.06%   |
| 5.3.0-29-generic            | 2         | 1.06%   |
| 5.19.0-42-generic           | 2         | 1.06%   |
| 5.19.0-40-generic           | 2         | 1.06%   |
| 5.19.0-23-generic           | 2         | 1.06%   |
| 5.16.7-desktop-1omv4003     | 2         | 1.06%   |
| 5.0.0-23-generic            | 2         | 1.06%   |
| 6.3.1-4-cachyos             | 1         | 0.53%   |
| 6.2.7-060207-generic        | 1         | 0.53%   |
| 6.2.10-zen1-1-zen           | 1         | 0.53%   |
| 6.2.10-200.fc37.x86_64      | 1         | 0.53%   |
| 6.2.0-20-generic            | 1         | 0.53%   |
| 6.1.9-200.fc37.x86_64       | 1         | 0.53%   |
| 6.1.8-603.inttf.fc37.x86_64 | 1         | 0.53%   |
| 6.1.6-200.fc37.x86_64       | 1         | 0.53%   |
| 6.1.12-060112-generic       | 1         | 0.53%   |
| 6.1.11-76060111-generic     | 1         | 0.53%   |
| 6.1.0-kali7-amd64           | 1         | 0.53%   |
| 6.1.0-kali5-amd64           | 1         | 0.53%   |
| 6.0.12-arch1-1              | 1         | 0.53%   |
| 6.0.12-76060006-generic     | 1         | 0.53%   |
| 6.0.12-300.fc37.x86_64      | 1         | 0.53%   |
| 5.9.3-arch1-1               | 1         | 0.53%   |
| 5.9.16-1-MANJARO            | 1         | 0.53%   |
| 5.9.11-3-MANJARO            | 1         | 0.53%   |
| 5.9.1-050901-generic        | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 34        | 19.1%   |
| 4.15.0  | 14        | 7.87%   |
| 5.15.0  | 13        | 7.3%    |
| 5.19.0  | 12        | 6.74%   |
| 5.8.0   | 9         | 5.06%   |
| 5.11.0  | 9         | 5.06%   |
| 5.13.0  | 8         | 4.49%   |
| 5.3.0   | 6         | 3.37%   |
| 5.10.0  | 6         | 3.37%   |
| 6.0.12  | 3         | 1.69%   |
| 5.0.0   | 3         | 1.69%   |
| 6.2.10  | 2         | 1.12%   |
| 6.1.1   | 2         | 1.12%   |
| 6.1.0   | 2         | 1.12%   |
| 6.0.6   | 2         | 1.12%   |
| 5.7.14  | 2         | 1.12%   |
| 5.16.7  | 2         | 1.12%   |
| 5.14.0  | 2         | 1.12%   |
| 4.18.0  | 2         | 1.12%   |
| 6.3.1   | 1         | 0.56%   |
| 6.2.7   | 1         | 0.56%   |
| 6.2.0   | 1         | 0.56%   |
| 6.1.9   | 1         | 0.56%   |
| 6.1.8   | 1         | 0.56%   |
| 6.1.6   | 1         | 0.56%   |
| 6.1.12  | 1         | 0.56%   |
| 6.1.11  | 1         | 0.56%   |
| 5.9.3   | 1         | 0.56%   |
| 5.9.16  | 1         | 0.56%   |
| 5.9.11  | 1         | 0.56%   |
| 5.9.1   | 1         | 0.56%   |
| 5.8.7   | 1         | 0.56%   |
| 5.8.5   | 1         | 0.56%   |
| 5.8.12  | 1         | 0.56%   |
| 5.7.6   | 1         | 0.56%   |
| 5.6.16  | 1         | 0.56%   |
| 5.6.14  | 1         | 0.56%   |
| 5.5.11  | 1         | 0.56%   |
| 5.4.68  | 1         | 0.56%   |
| 5.4.2   | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 36        | 20.57%  |
| 5.15    | 17        | 9.71%   |
| 5.19    | 15        | 8.57%   |
| 4.15    | 14        | 8%      |
| 5.8     | 11        | 6.29%   |
| 6.1     | 9         | 5.14%   |
| 5.13    | 9         | 5.14%   |
| 5.11    | 9         | 5.14%   |
| 5.10    | 8         | 4.57%   |
| 5.3     | 6         | 3.43%   |
| 6.0     | 5         | 2.86%   |
| 5.16    | 5         | 2.86%   |
| 6.2     | 4         | 2.29%   |
| 5.9     | 3         | 1.71%   |
| 5.7     | 3         | 1.71%   |
| 5.14    | 3         | 1.71%   |
| 5.0     | 3         | 1.71%   |
| 4.18    | 3         | 1.71%   |
| 5.6     | 2         | 1.14%   |
| 5.18    | 2         | 1.14%   |
| 5.17    | 2         | 1.14%   |
| 4.19    | 2         | 1.14%   |
| 6.3     | 1         | 0.57%   |
| 5.5     | 1         | 0.57%   |
| 5.12    | 1         | 0.57%   |
| 4.4     | 1         | 0.57%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 164       | 98.8%   |
| i686   | 2         | 1.2%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 102       | 59.3%   |
| KDE5       | 25        | 14.53%  |
| Unknown    | 19        | 11.05%  |
| X-Cinnamon | 7         | 4.07%   |
| XFCE       | 5         | 2.91%   |
| KDE        | 4         | 2.33%   |
| MATE       | 3         | 1.74%   |
| LXQt       | 2         | 1.16%   |
| Unity      | 1         | 0.58%   |
| Pantheon   | 1         | 0.58%   |
| DWM        | 1         | 0.58%   |
| bspwm      | 1         | 0.58%   |
| awesome    | 1         | 0.58%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 119       | 70.41%  |
| Wayland | 39        | 23.08%  |
| Unknown | 11        | 6.51%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 93        | 54.71%  |
| GDM     | 26        | 15.29%  |
| GDM3    | 22        | 12.94%  |
| SDDM    | 19        | 11.18%  |
| LightDM | 8         | 4.71%   |
| TDM     | 2         | 1.18%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 125       | 74.85%  |
| Unknown | 17        | 10.18%  |
| en_GB   | 8         | 4.79%   |
| C       | 6         | 3.59%   |
| ru_RU   | 2         | 1.2%    |
| en_AU   | 2         | 1.2%    |
| pl_PL   | 1         | 0.6%    |
| hu_HU   | 1         | 0.6%    |
| en_IN   | 1         | 0.6%    |
| en_AG   | 1         | 0.6%    |
| el_GR   | 1         | 0.6%    |
| de_DE   | 1         | 0.6%    |
| ar_AE   | 1         | 0.6%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 95        | 54.91%  |
| BIOS | 78        | 45.09%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 132       | 79.52%  |
| Btrfs   | 18        | 10.84%  |
| Overlay | 9         | 5.42%   |
| Xfs     | 4         | 2.41%   |
| Tmpfs   | 1         | 0.6%    |
| Ext2    | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 96        | 57.14%  |
| GPT     | 61        | 36.31%  |
| MBR     | 11        | 6.55%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 150       | 89.82%  |
| Yes       | 17        | 10.18%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 109       | 64.5%   |
| Yes       | 60        | 35.5%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                        | Computers | Percent |
|-----------------------------|-----------|---------|
| Hewlett-Packard             | 42        | 25.3%   |
| Lenovo                      | 39        | 23.49%  |
| Dell                        | 20        | 12.05%  |
| ASUSTek Computer            | 19        | 11.45%  |
| Toshiba                     | 6         | 3.61%   |
| Valve                       | 5         | 3.01%   |
| Intel                       | 4         | 2.41%   |
| Gigabyte Technology         | 4         | 2.41%   |
| Acer                        | 4         | 2.41%   |
| Notebook                    | 3         | 1.81%   |
| MSI                         | 3         | 1.81%   |
| Sony                        | 2         | 1.2%    |
| Microsoft                   | 2         | 1.2%    |
| Google                      | 2         | 1.2%    |
| Apple                       | 2         | 1.2%    |
| YJKC                        | 1         | 0.6%    |
| win element                 | 1         | 0.6%    |
| LG Electronics              | 1         | 0.6%    |
| I-Life Digital Technologies | 1         | 0.6%    |
| HUAWEI                      | 1         | 0.6%    |
| ECS                         | 1         | 0.6%    |
| Biostar                     | 1         | 0.6%    |
| AZW                         | 1         | 0.6%    |
| A-DATA Technology           | 1         | 0.6%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Valve Jupiter                               | 5         | 3.01%   |
| HP Pavilion Notebook                        | 2         | 1.2%    |
| HP Pavilion 15                              | 2         | 1.2%    |
| HP ENVY Laptop 13-aq0xxx                    | 2         | 1.2%    |
| HP All-in-One 22-c0xx                       | 2         | 1.2%    |
| Dell G5 5587                                | 2         | 1.2%    |
| ASUS All Series                             | 2         | 1.2%    |
| YJKC vBOOK Plus                             | 1         | 0.6%    |
| win element MoreFine S500+                  | 1         | 0.6%    |
| Toshiba TECRA X40-D                         | 1         | 0.6%    |
| Toshiba TECRA A50-C                         | 1         | 0.6%    |
| Toshiba Satellite L850-B434                 | 1         | 0.6%    |
| Toshiba Satellite C850-A966                 | 1         | 0.6%    |
| Toshiba Satellite C660                      | 1         | 0.6%    |
| Toshiba Satellite A300                      | 1         | 0.6%    |
| Sony VGN-NS10J_S                            | 1         | 0.6%    |
| Sony SVE14A25CAB                            | 1         | 0.6%    |
| Notebook PD5x_7xPNP_PNN_PNT                 | 1         | 0.6%    |
| Notebook P95_96_97Ex,Rx                     | 1         | 0.6%    |
| Notebook NV4XMB,ME,MZ                       | 1         | 0.6%    |
| MSI PS63 Modern 8RD                         | 1         | 0.6%    |
| MSI MS-7850                                 | 1         | 0.6%    |
| MSI Modern 14 B5M                           | 1         | 0.6%    |
| Microsoft Surface Pro 4                     | 1         | 0.6%    |
| Microsoft Surface Pro 3                     | 1         | 0.6%    |
| LG C500-G.AEF5BE1                           | 1         | 0.6%    |
| Lenovo Yoga S730-13IWL 81J0                 | 1         | 0.6%    |
| Lenovo Yoga Creator 7 15IMH05 82DS          | 1         | 0.6%    |
| Lenovo Yoga 2 Pro 20266                     | 1         | 0.6%    |
| Lenovo ThinkPad Yoga 260 20FD000GAD         | 1         | 0.6%    |
| Lenovo ThinkPad Yoga 11e 4th Gen 20HUS00000 | 1         | 0.6%    |
| Lenovo ThinkPad X240 20AMS6GB00             | 1         | 0.6%    |
| Lenovo ThinkPad X230 2325DV8                | 1         | 0.6%    |
| Lenovo ThinkPad X1 Yoga 4th 20QF0015US      | 1         | 0.6%    |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK001HUS | 1         | 0.6%    |
| Lenovo ThinkPad X1 Carbon Gen 9 20XW00A9US  | 1         | 0.6%    |
| Lenovo ThinkPad T61 76653JG                 | 1         | 0.6%    |
| Lenovo ThinkPad T490 20N2004JAD             | 1         | 0.6%    |
| Lenovo ThinkPad T480s 20L8S3FV00            | 1         | 0.6%    |
| Lenovo ThinkPad T480s 20L7001PAD            | 1         | 0.6%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 19        | 11.45%  |
| HP Pavilion          | 11        | 6.63%   |
| Lenovo IdeaPad       | 9         | 5.42%   |
| HP EliteBook         | 7         | 4.22%   |
| ASUS ROG             | 6         | 3.61%   |
| Valve Jupiter        | 5         | 3.01%   |
| HP Laptop            | 5         | 3.01%   |
| Dell Latitude        | 5         | 3.01%   |
| Toshiba Satellite    | 4         | 2.41%   |
| ASUS PRIME           | 4         | 2.41%   |
| Lenovo Yoga          | 3         | 1.81%   |
| HP ProBook           | 3         | 1.81%   |
| HP ENVY              | 3         | 1.81%   |
| Dell XPS             | 3         | 1.81%   |
| Dell Precision       | 3         | 1.81%   |
| Dell Inspiron        | 3         | 1.81%   |
| ASUS VivoBook        | 3         | 1.81%   |
| Acer Aspire          | 3         | 1.81%   |
| Toshiba TECRA        | 2         | 1.2%    |
| Microsoft Surface    | 2         | 1.2%    |
| Lenovo ThinkCentre   | 2         | 1.2%    |
| Lenovo IdeaPadFlex   | 2         | 1.2%    |
| HP All-in-One        | 2         | 1.2%    |
| Dell OptiPlex        | 2         | 1.2%    |
| Dell G5              | 2         | 1.2%    |
| ASUS All             | 2         | 1.2%    |
| YJKC vBOOK           | 1         | 0.6%    |
| win element MoreFine | 1         | 0.6%    |
| Sony VGN-NS10J       | 1         | 0.6%    |
| Sony SVE14A25CAB     | 1         | 0.6%    |
| Notebook PD5x        | 1         | 0.6%    |
| Notebook P95         | 1         | 0.6%    |
| Notebook NV4XMB      | 1         | 0.6%    |
| MSI PS63             | 1         | 0.6%    |
| MSI MS-7850          | 1         | 0.6%    |
| MSI Modern           | 1         | 0.6%    |
| LG C500-G.AEF5BE1    | 1         | 0.6%    |
| Lenovo Legion        | 1         | 0.6%    |
| Lenovo G500          | 1         | 0.6%    |
| Lenovo G50-80        | 1         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 19        | 11.45%  |
| 2019 | 19        | 11.45%  |
| 2018 | 18        | 10.84%  |
| 2021 | 17        | 10.24%  |
| 2013 | 14        | 8.43%   |
| 2016 | 11        | 6.63%   |
| 2012 | 11        | 6.63%   |
| 2022 | 10        | 6.02%   |
| 2017 | 9         | 5.42%   |
| 2010 | 9         | 5.42%   |
| 2014 | 8         | 4.82%   |
| 2011 | 7         | 4.22%   |
| 2015 | 5         | 3.01%   |
| 2008 | 3         | 1.81%   |
| 2007 | 3         | 1.81%   |
| 2009 | 2         | 1.2%    |
| 2005 | 1         | 0.6%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 117       | 70.48%  |
| Desktop     | 32        | 19.28%  |
| Convertible | 8         | 4.82%   |
| Mini pc     | 3         | 1.81%   |
| All in one  | 3         | 1.81%   |
| Tablet      | 2         | 1.2%    |
| Server      | 1         | 0.6%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 149       | 89.22%  |
| Enabled  | 18        | 10.78%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 164       | 98.8%   |
| Yes  | 2         | 1.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 39        | 23.49%  |
| 16.01-24.0      | 34        | 20.48%  |
| 8.01-16.0       | 34        | 20.48%  |
| 3.01-4.0        | 22        | 13.25%  |
| 32.01-64.0      | 17        | 10.24%  |
| 64.01-256.0     | 8         | 4.82%   |
| 24.01-32.0      | 4         | 2.41%   |
| 0.51-1.0        | 3         | 1.81%   |
| 2.01-3.0        | 2         | 1.2%    |
| 1.01-2.0        | 2         | 1.2%    |
| More than 256.0 | 1         | 0.6%    |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 50        | 28.09%  |
| 2.01-3.0   | 45        | 25.28%  |
| 4.01-8.0   | 40        | 22.47%  |
| 3.01-4.0   | 26        | 14.61%  |
| 8.01-16.0  | 8         | 4.49%   |
| 0.51-1.0   | 6         | 3.37%   |
| 0.01-0.5   | 2         | 1.12%   |
| 16.01-24.0 | 1         | 0.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 118       | 70.66%  |
| 2      | 31        | 18.56%  |
| 3      | 8         | 4.79%   |
| 4      | 4         | 2.4%    |
| 6      | 2         | 1.2%    |
| 0      | 2         | 1.2%    |
| 9      | 1         | 0.6%    |
| 8      | 1         | 0.6%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 119       | 71.69%  |
| Yes       | 47        | 28.31%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 122       | 73.49%  |
| No        | 44        | 26.51%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 87.95%  |
| No        | 20        | 12.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 74.4%   |
| No        | 43        | 25.6%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| UAE     | 166       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Dubai            | 81        | 47.65%  |
| Abu Dhabi        | 50        | 29.41%  |
| Sharjah          | 20        | 11.76%  |
| Al Ain City      | 8         | 4.71%   |
| Ajman            | 5         | 2.94%   |
| Al Fujairah City | 4         | 2.35%   |
| Ras al-Khaimah   | 1         | 0.59%   |
| Al Halah         | 1         | 0.59%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 39        | 57     | 17.41%  |
| WDC                         | 38        | 42     | 16.96%  |
| Seagate                     | 23        | 32     | 10.27%  |
| Toshiba                     | 19        | 23     | 8.48%   |
| Crucial                     | 11        | 12     | 4.91%   |
| Unknown                     | 10        | 17     | 4.46%   |
| Intel                       | 10        | 12     | 4.46%   |
| HGST                        | 8         | 9      | 3.57%   |
| SanDisk                     | 6         | 7      | 2.68%   |
| Micron Technology           | 6         | 6      | 2.68%   |
| Kingston                    | 6         | 6      | 2.68%   |
| SK hynix                    | 4         | 5      | 1.79%   |
| Hitachi                     | 4         | 4      | 1.79%   |
| Silicon Motion              | 3         | 3      | 1.34%   |
| Apple                       | 3         | 4      | 1.34%   |
| Realtek Semiconductor       | 2         | 2      | 0.89%   |
| Phison                      | 2         | 2      | 0.89%   |
| Micron/Crucial Technology   | 2         | 2      | 0.89%   |
| Lexar                       | 2         | 2      | 0.89%   |
| Kingston Technology Company | 2         | 2      | 0.89%   |
| USB3.0                      | 1         | 1      | 0.45%   |
| Transcend                   | 1         | 1      | 0.45%   |
| Team                        | 1         | 1      | 0.45%   |
| Super Talent                | 1         | 1      | 0.45%   |
| Phison Electronics          | 1         | 1      | 0.45%   |
| Patriot                     | 1         | 1      | 0.45%   |
| OCZ                         | 1         | 1      | 0.45%   |
| O2 Micro                    | 1         | 1      | 0.45%   |
| Maxtor                      | 1         | 1      | 0.45%   |
| Lite-On                     | 1         | 1      | 0.45%   |
| Lenovo                      | 1         | 1      | 0.45%   |
| LaCie                       | 1         | 1      | 0.45%   |
| KIOXIA                      | 1         | 4      | 0.45%   |
| KingSpec                    | 1         | 2      | 0.45%   |
| JMicron Technology          | 1         | 1      | 0.45%   |
| Gigabyte Technology         | 1         | 1      | 0.45%   |
| Fujitsu                     | 1         | 1      | 0.45%   |
| External                    | 1         | 1      | 0.45%   |
| Corsair                     | 1         | 1      | 0.45%   |
| China                       | 1         | 1      | 0.45%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 256GB                        | 4         | 1.69%   |
| HGST HTS725050A7E630 500GB                          | 4         | 1.69%   |
| WDC WD10JPCX-24UE4T0 1TB                            | 3         | 1.27%   |
| Toshiba MQ01ABD075 752GB                            | 3         | 1.27%   |
| Toshiba DT01ACA100 1TB                              | 3         | 1.27%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 1.27%   |
| Intel NVMe SSD Drive 512GB                          | 3         | 1.27%   |
| HGST HTS721010A9E630 1TB                            | 3         | 1.27%   |
| Crucial CT500MX500SSD1 500GB                        | 3         | 1.27%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.84%   |
| WDC WD10SPZX-08Z10 1TB                              | 2         | 0.84%   |
| WDC WD1002FAEX-00Z3A0 1TB                           | 2         | 0.84%   |
| WDC PC SN730 SDBQNTY-1T00-1001 1TB                  | 2         | 0.84%   |
| Unknown SD/MMC/MS PRO 64GB                          | 2         | 0.84%   |
| Unknown MMC Card  64GB                              | 2         | 0.84%   |
| Unknown MMC Card  16GB                              | 2         | 0.84%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1TB | 2         | 0.84%   |
| Seagate ST500VT000-1DK142 500GB                     | 2         | 0.84%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 0.84%   |
| Samsung SSD 970 EVO Plus 500GB                      | 2         | 0.84%   |
| Samsung SSD 860 EVO 500GB                           | 2         | 0.84%   |
| Samsung SSD 850 PRO 1TB                             | 2         | 0.84%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.84%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 2         | 0.84%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 2         | 0.84%   |
| Kingston Company OM3PDP3 NVMe SSD 256GB             | 2         | 0.84%   |
| Intel SSDPEKNW512G8H 512GB                          | 2         | 0.84%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.42%   |
| WDC WDS250G2B0A 250GB SSD                           | 1         | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 1         | 0.42%   |
| WDC WDS120G1G0A-00SS50 120GB SSD                    | 1         | 0.42%   |
| WDC WDS100T3X0C-00SJG0 1TB                          | 1         | 0.42%   |
| WDC WD800BB-55JHC0 80GB                             | 1         | 0.42%   |
| WDC WD6400AAKS-22A7B0 640GB                         | 1         | 0.42%   |
| WDC WD5000LPVX-60V0TT0 500GB                        | 1         | 0.42%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 0.42%   |
| WDC WD5000LPCX-22VHAT1 500GB                        | 1         | 0.42%   |
| WDC WD5000BPVT-00A1YT0 500GB                        | 1         | 0.42%   |
| WDC WD5000AAKS-65V0A0 500GB                         | 1         | 0.42%   |
| WDC WD5000AAKS-00A7B2 500GB                         | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| WDC      | 26        | 30     | 30.59%  |
| Seagate  | 23        | 32     | 27.06%  |
| Toshiba  | 16        | 20     | 18.82%  |
| HGST     | 8         | 9      | 9.41%   |
| Hitachi  | 4         | 4      | 4.71%   |
| Unknown  | 2         | 5      | 2.35%   |
| Apple    | 2         | 2      | 2.35%   |
| USB3.0   | 1         | 1      | 1.18%   |
| Maxtor   | 1         | 1      | 1.18%   |
| Fujitsu  | 1         | 1      | 1.18%   |
| External | 1         | 1      | 1.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 25     | 29.41%  |
| Crucial             | 8         | 9      | 15.69%  |
| WDC                 | 7         | 7      | 13.73%  |
| Kingston            | 3         | 3      | 5.88%   |
| SanDisk             | 2         | 2      | 3.92%   |
| Transcend           | 1         | 1      | 1.96%   |
| Team                | 1         | 1      | 1.96%   |
| Super Talent        | 1         | 1      | 1.96%   |
| SK hynix            | 1         | 1      | 1.96%   |
| Patriot             | 1         | 1      | 1.96%   |
| Micron Technology   | 1         | 1      | 1.96%   |
| Lexar               | 1         | 1      | 1.96%   |
| LaCie               | 1         | 1      | 1.96%   |
| KingSpec            | 1         | 2      | 1.96%   |
| JMicron Technology  | 1         | 1      | 1.96%   |
| Intel               | 1         | 1      | 1.96%   |
| Gigabyte Technology | 1         | 1      | 1.96%   |
| Corsair             | 1         | 1      | 1.96%   |
| China               | 1         | 1      | 1.96%   |
| Carlstein           | 1         | 1      | 1.96%   |
| Unknown             | 1         | 1      | 1.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 75        | 96     | 37.88%  |
| HDD  | 75        | 106    | 37.88%  |
| SSD  | 40        | 63     | 20.2%   |
| MMC  | 8         | 12     | 4.04%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 98        | 158    | 52.13%  |
| NVMe | 75        | 96     | 39.89%  |
| MMC  | 8         | 12     | 4.26%   |
| SAS  | 7         | 11     | 3.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 67        | 86     | 54.92%  |
| 0.51-1.0   | 44        | 59     | 36.07%  |
| 1.01-2.0   | 8         | 16     | 6.56%   |
| 3.01-4.0   | 2         | 7      | 1.64%   |
| 4.01-10.0  | 1         | 1      | 0.82%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 54        | 31.76%  |
| 101-250        | 39        | 22.94%  |
| 501-1000       | 21        | 12.35%  |
| 51-100         | 12        | 7.06%   |
| 21-50          | 11        | 6.47%   |
| 1001-2000      | 10        | 5.88%   |
| 1-20           | 8         | 4.71%   |
| Unknown        | 7         | 4.12%   |
| 2001-3000      | 5         | 2.94%   |
| More than 3000 | 3         | 1.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1-20      | 73        | 40.78%  |
| 21-50     | 40        | 22.35%  |
| 101-250   | 20        | 11.17%  |
| 51-100    | 19        | 10.61%  |
| 251-500   | 12        | 6.7%    |
| Unknown   | 7         | 3.91%   |
| 501-1000  | 6         | 3.35%   |
| 2001-3000 | 1         | 0.56%   |
| 1001-2000 | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                        | Computers | Drives | Percent |
|----------------------------------------------|-----------|--------|---------|
| WDC WD10JPVX-60JC3T1 1TB                     | 1         | 1      | 14.29%  |
| WDC WD10EARS-00MVWB0 1TB                     | 1         | 1      | 14.29%  |
| WDC WD Blue SA510 2.5 500GB                  | 1         | 1      | 14.29%  |
| Seagate ST500LT012-1DG142 500GB              | 1         | 1      | 14.29%  |
| Samsung Electronics MZVLQ256HBJD-00BH1 256GB | 1         | 1      | 14.29%  |
| Micron Technology 1100 SATA 512GB SSD        | 1         | 1      | 14.29%  |
| Intel SSDSC2BB480G7 480GB                    | 1         | 1      | 14.29%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 3         | 3      | 42.86%  |
| Seagate             | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |
| Micron Technology   | 1         | 1      | 14.29%  |
| Intel               | 1         | 1      | 14.29%  |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 66.67%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 3      | 40%     |
| HDD  | 2         | 3      | 40%     |
| NVMe | 1         | 1      | 20%     |

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
| Detected | 109       | 175    | 63.74%  |
| Works    | 58        | 95     | 33.92%  |
| Malfunc  | 4         | 7      | 2.34%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 120       | 57.97%  |
| Samsung Electronics          | 26        | 12.56%  |
| SanDisk                      | 8         | 3.86%   |
| AMD                          | 7         | 3.38%   |
| Micron Technology            | 5         | 2.42%   |
| Kingston Technology Company  | 5         | 2.42%   |
| Silicon Motion               | 4         | 1.93%   |
| Micron/Crucial Technology    | 4         | 1.93%   |
| Toshiba America Info Systems | 3         | 1.45%   |
| SK hynix                     | 3         | 1.45%   |
| Phison Electronics           | 3         | 1.45%   |
| ASMedia Technology           | 3         | 1.45%   |
| Realtek Semiconductor        | 2         | 0.97%   |
| LSI Logic / Symbios Logic    | 2         | 0.97%   |
| VIA Technologies             | 1         | 0.48%   |
| OCZ Technology Group         | 1         | 0.48%   |
| O2 Micro                     | 1         | 0.48%   |
| Nvidia                       | 1         | 0.48%   |
| Marvell Technology Group     | 1         | 0.48%   |
| Lite-On Technology           | 1         | 0.48%   |
| Lenovo                       | 1         | 0.48%   |
| KIOXIA                       | 1         | 0.48%   |
| JMicron Technology           | 1         | 0.48%   |
| Broadcom / LSI               | 1         | 0.48%   |
| Apple                        | 1         | 0.48%   |
| ADATA Technology             | 1         | 0.48%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 15        | 6.61%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 5.29%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 9         | 3.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 9         | 3.96%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 3.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 8         | 3.52%   |
| Samsung NVMe SSD Controller 980                                                | 7         | 3.08%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 7         | 3.08%   |
| Intel Volume Management Device NVMe RAID Controller                            | 6         | 2.64%   |
| Intel SSD 660P Series                                                          | 6         | 2.64%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 6         | 2.64%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 5         | 2.2%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 5         | 2.2%    |
| Micron NVMe Storage Controller                                                 | 5         | 2.2%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 5         | 2.2%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 4         | 1.76%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 1.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 4         | 1.76%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 1.32%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.32%   |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.32%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 3         | 1.32%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 2         | 0.88%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 2         | 0.88%   |
| Realtek NVMe Controller                                                        | 2         | 0.88%   |
| Micron/Crucial P5 Plus NVMe PCIe SSD                                           | 2         | 0.88%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 2         | 0.88%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 2         | 0.88%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 2         | 0.88%   |
| Intel SATA Controller [RAID mode]                                              | 2         | 0.88%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 2         | 0.88%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 2         | 0.88%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 2         | 0.88%   |
| Intel C610/X99 series chipset sSATA Controller [AHCI mode]                     | 2         | 0.88%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 2         | 0.88%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 2         | 0.88%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 2         | 0.88%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 2         | 0.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 2         | 0.88%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 2         | 0.88%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 95        | 46.34%  |
| NVMe | 75        | 36.59%  |
| RAID | 25        | 12.2%   |
| IDE  | 8         | 3.9%    |
| SAS  | 1         | 0.49%   |
| SCSI | 1         | 0.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 145       | 87.35%  |
| AMD    | 21        | 12.65%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz           | 5         | 3.01%   |
| Intel Core i5-8265U CPU @ 1.60GHz           | 5         | 3.01%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 5         | 3.01%   |
| AMD Custom APU 0405                         | 5         | 3.01%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 4         | 2.41%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 4         | 2.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 4         | 2.41%   |
| Intel Xeon CPU E5620 @ 2.40GHz              | 3         | 1.81%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 3         | 1.81%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 1.81%   |
| Intel Core i7-5500U CPU @ 2.40GHz           | 3         | 1.81%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 3         | 1.81%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 3         | 1.81%   |
| Intel Core i3-10110U CPU @ 2.10GHz          | 3         | 1.81%   |
| Intel 12th Gen Core i7-12700H               | 3         | 1.81%   |
| Intel Core i9-10885H CPU @ 2.40GHz          | 2         | 1.2%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 2         | 1.2%    |
| Intel Core i7-3770K CPU @ 3.50GHz           | 2         | 1.2%    |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 1.2%    |
| Intel Core i7-10750H CPU @ 2.60GHz          | 2         | 1.2%    |
| Intel Core i5-9400T CPU @ 1.80GHz           | 2         | 1.2%    |
| Intel Core i5-7400 CPU @ 3.00GHz            | 2         | 1.2%    |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 1.2%    |
| Intel Core i5-2410M CPU @ 2.30GHz           | 2         | 1.2%    |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.2%    |
| AMD Ryzen 9 5900HX with Radeon Graphics     | 2         | 1.2%    |
| AMD Ryzen 5 5500U with Radeon Graphics      | 2         | 1.2%    |
| Intel Xeon Silver 4214 CPU @ 2.20GHz        | 1         | 0.6%    |
| Intel Xeon CPU E5-2609 v2 @ 2.50GHz         | 1         | 0.6%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 1         | 0.6%    |
| Intel Pentium 4 CPU 2.80GHz                 | 1         | 0.6%    |
| Intel Core m5-6Y54 CPU @ 1.10GHz            | 1         | 0.6%    |
| Intel Core i9-9980HK CPU @ 2.40GHz          | 1         | 0.6%    |
| Intel Core i9-8950HK CPU @ 2.90GHz          | 1         | 0.6%    |
| Intel Core i9-10900K CPU @ 3.70GHz          | 1         | 0.6%    |
| Intel Core i7-9850H CPU @ 2.60GHz           | 1         | 0.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.6%    |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.6%    |
| Intel Core i7-8650U CPU @ 1.90GHz           | 1         | 0.6%    |
| Intel Core i7-7740X CPU @ 4.30GHz           | 1         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 54        | 32.53%  |
| Intel Core i5           | 46        | 27.71%  |
| Other                   | 18        | 10.84%  |
| Intel Core i3           | 9         | 5.42%   |
| AMD Ryzen 5             | 6         | 3.61%   |
| Intel Core i9           | 5         | 3.01%   |
| Intel Xeon              | 4         | 2.41%   |
| Intel Celeron           | 4         | 2.41%   |
| Intel Core 2 Duo        | 3         | 1.81%   |
| AMD Ryzen 9             | 3         | 1.81%   |
| AMD Ryzen 7             | 3         | 1.81%   |
| Intel Xeon Silver       | 1         | 0.6%    |
| Intel Pentium Dual-Core | 1         | 0.6%    |
| Intel Pentium 4         | 1         | 0.6%    |
| Intel Core m5           | 1         | 0.6%    |
| Intel Core 2 Quad       | 1         | 0.6%    |
| Intel Celeron M         | 1         | 0.6%    |
| Intel Atom              | 1         | 0.6%    |
| AMD Sempron             | 1         | 0.6%    |
| AMD Ryzen Threadripper  | 1         | 0.6%    |
| AMD Ryzen 7 PRO         | 1         | 0.6%    |
| AMD A6                  | 1         | 0.6%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 61        | 36.75%  |
| 2      | 59        | 35.54%  |
| 6      | 18        | 10.84%  |
| 8      | 15        | 9.04%   |
| 14     | 4         | 2.41%   |
| 1      | 4         | 2.41%   |
| 16     | 3         | 1.81%   |
| 12     | 1         | 0.6%    |
| 10     | 1         | 0.6%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 163       | 98.19%  |
| 2      | 3         | 1.81%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 142       | 85.54%  |
| 1      | 24        | 14.46%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 163       | 98.19%  |
| 32-bit         | 2         | 1.2%    |
| Unknown        | 1         | 0.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 45        | 26.16%  |
| 0x306a9    | 10        | 5.81%   |
| 0x406e3    | 9         | 5.23%   |
| 0x906ea    | 8         | 4.65%   |
| 0x806ec    | 8         | 4.65%   |
| 0x40651    | 8         | 4.65%   |
| 0x806c1    | 7         | 4.07%   |
| 0x206a7    | 7         | 4.07%   |
| 0x806ea    | 5         | 2.91%   |
| 0x306c3    | 5         | 2.91%   |
| 0x906e9    | 4         | 2.33%   |
| 0x806e9    | 4         | 2.33%   |
| 0xa0652    | 3         | 1.74%   |
| 0x206c2    | 3         | 1.74%   |
| 0x20655    | 3         | 1.74%   |
| 0xa0655    | 2         | 1.16%   |
| 0x906ed    | 2         | 1.16%   |
| 0x906a3    | 2         | 1.16%   |
| 0x806eb    | 2         | 1.16%   |
| 0x6fd      | 2         | 1.16%   |
| 0x506e3    | 2         | 1.16%   |
| 0x306f2    | 2         | 1.16%   |
| 0x306d4    | 2         | 1.16%   |
| 0x0a50000c | 2         | 1.16%   |
| 0x08608103 | 2         | 1.16%   |
| 0x08108109 | 2         | 1.16%   |
| 0xf29      | 1         | 0.58%   |
| 0x806d1    | 1         | 0.58%   |
| 0x706a1    | 1         | 0.58%   |
| 0x6fb      | 1         | 0.58%   |
| 0x6e8      | 1         | 0.58%   |
| 0x506c9    | 1         | 0.58%   |
| 0x406c4    | 1         | 0.58%   |
| 0x406c3    | 1         | 0.58%   |
| 0x306e4    | 1         | 0.58%   |
| 0x20652    | 1         | 0.58%   |
| 0x106e5    | 1         | 0.58%   |
| 0x1067a    | 1         | 0.58%   |
| 0x0a601203 | 1         | 0.58%   |
| 0x0a50000d | 1         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 45        | 27.11%  |
| Haswell          | 19        | 11.45%  |
| Skylake          | 14        | 8.43%   |
| IvyBridge        | 13        | 7.83%   |
| Unknown          | 11        | 6.63%   |
| SandyBridge      | 9         | 5.42%   |
| Westmere         | 8         | 4.82%   |
| TigerLake        | 7         | 4.22%   |
| CometLake        | 7         | 4.22%   |
| Broadwell        | 5         | 3.01%   |
| Zen 3            | 4         | 2.41%   |
| Zen+             | 3         | 1.81%   |
| Core             | 3         | 1.81%   |
| Alderlake Hybrid | 3         | 1.81%   |
| Zen 2            | 2         | 1.2%    |
| Silvermont       | 2         | 1.2%    |
| Penryn           | 2         | 1.2%    |
| Zen              | 1         | 0.6%    |
| Piledriver       | 1         | 0.6%    |
| P6               | 1         | 0.6%    |
| NetBurst         | 1         | 0.6%    |
| Nehalem          | 1         | 0.6%    |
| K8 Hammer        | 1         | 0.6%    |
| Icelake          | 1         | 0.6%    |
| Goldmont plus    | 1         | 0.6%    |
| Goldmont         | 1         | 0.6%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 119       | 53.13%  |
| Nvidia                     | 69        | 30.8%   |
| AMD                        | 35        | 15.63%  |
| Matrox Electronics Systems | 1         | 0.45%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 4.89%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 11        | 4.89%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 3.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8         | 3.56%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 8         | 3.56%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 3.11%   |
| Intel UHD Graphics 620                                                                   | 6         | 2.67%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.67%   |
| Intel HD Graphics 620                                                                    | 5         | 2.22%   |
| Intel HD Graphics 5500                                                                   | 5         | 2.22%   |
| AMD VanGogh [AMD Custom GPU 0405]                                                        | 5         | 2.22%   |
| Nvidia GM108M [GeForce MX130]                                                            | 4         | 1.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 4         | 1.78%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 4         | 1.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.78%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 3         | 1.33%   |
| Nvidia GM108M [GeForce MX110]                                                            | 3         | 1.33%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 1.33%   |
| Intel HD Graphics 530                                                                    | 3         | 1.33%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 1.33%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 3         | 1.33%   |
| AMD Lucienne                                                                             | 3         | 1.33%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.89%   |
| Nvidia GP108BM [GeForce MX250]                                                           | 2         | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.89%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.89%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 2         | 0.89%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 2         | 0.89%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 2         | 0.89%   |
| Intel HD Graphics 630                                                                    | 2         | 0.89%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2         | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.89%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.89%   |
| AMD Renoir                                                                               | 2         | 0.89%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.89%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.44%   |
| Nvidia TU117M                                                                            | 1         | 0.44%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 63        | 37.95%  |
| Intel + Nvidia     | 43        | 25.9%   |
| 1 x Nvidia         | 23        | 13.86%  |
| 1 x AMD            | 21        | 12.65%  |
| Intel + AMD        | 12        | 7.23%   |
| AMD + Nvidia       | 2         | 1.2%    |
| 1 x Matrox         | 1         | 0.6%    |
| Intel + 2 x Nvidia | 1         | 0.6%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 128       | 76.65%  |
| Proprietary | 32        | 19.16%  |
| Unknown     | 7         | 4.19%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 99        | 58.93%  |
| 1.01-2.0   | 25        | 14.88%  |
| 3.01-4.0   | 12        | 7.14%   |
| 0.01-0.5   | 12        | 7.14%   |
| 7.01-8.0   | 6         | 3.57%   |
| 0.51-1.0   | 6         | 3.57%   |
| 5.01-6.0   | 4         | 2.38%   |
| 2.01-3.0   | 2         | 1.19%   |
| 16.01-24.0 | 1         | 0.6%    |
| 8.01-16.0  | 1         | 0.6%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 26        | 14.53%  |
| BOE                     | 23        | 12.85%  |
| Samsung Electronics     | 22        | 12.29%  |
| LG Display              | 21        | 11.73%  |
| Chimei Innolux          | 17        | 9.5%    |
| Goldstar                | 9         | 5.03%   |
| Hewlett-Packard         | 8         | 4.47%   |
| Dell                    | 5         | 2.79%   |
| BenQ                    | 5         | 2.79%   |
| Valve                   | 4         | 2.23%   |
| Lenovo                  | 4         | 2.23%   |
| Sharp                   | 3         | 1.68%   |
| CSO                     | 3         | 1.68%   |
| Ancor Communications    | 3         | 1.68%   |
| ViewSonic               | 2         | 1.12%   |
| Philips                 | 2         | 1.12%   |
| LG Philips              | 2         | 1.12%   |
| InfoVision              | 2         | 1.12%   |
| Chi Mei Optoelectronics | 2         | 1.12%   |
| Apple                   | 2         | 1.12%   |
| Sony                    | 1         | 0.56%   |
| Seiko/Epson             | 1         | 0.56%   |
| RTK                     | 1         | 0.56%   |
| Panasonic               | 1         | 0.56%   |
| Mi                      | 1         | 0.56%   |
| LGD                     | 1         | 0.56%   |
| LG Electronics          | 1         | 0.56%   |
| Hitachi                 | 1         | 0.56%   |
| Gigabyte Technology     | 1         | 0.56%   |
| CTX                     | 1         | 0.56%   |
| CMN                     | 1         | 0.56%   |
| ASUSTek Computer        | 1         | 0.56%   |
| AOC                     | 1         | 0.56%   |
| Analogix                | 1         | 0.56%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                     | 4         | 2.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch       | 3         | 1.65%   |
| LG Display LCD Monitor LGD0575 1920x1080 309x174mm 14.0-inch            | 2         | 1.1%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.1%    |
| Hewlett-Packard ALL-in-One HPN401F 1920x1080 476x268mm 21.5-inch        | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch        | 2         | 1.1%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 2         | 1.1%    |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                    | 2         | 1.1%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                   | 2         | 1.1%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                    | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO272B 3840x2160 293x165mm 13.2-inch          | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch          | 2         | 1.1%    |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch          | 2         | 1.1%    |
| ViewSonic VG2439 Series VSCD22B 1920x1080 521x293mm 23.5-inch           | 1         | 0.55%   |
| ViewSonic VA1918wm VSCC821 1440x900 410x256mm 19.0-inch                 | 1         | 0.55%   |
| Sony BM320 SNY050A 1920x1080 708x399mm 32.0-inch                        | 1         | 0.55%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                 | 1         | 0.55%   |
| Sharp LCD Monitor SHP14B9 3840x2160 344x194mm 15.5-inch                 | 1         | 0.55%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                 | 1         | 0.55%   |
| Seiko/Epson LCD Monitor 1280x800                                        | 1         | 0.55%   |
| Samsung Electronics U28E590 SAM0C4D 1680x1050 610x350mm 27.7-inch       | 1         | 0.55%   |
| Samsung Electronics SMB1930N SAM0632 1366x768 410x230mm 18.5-inch       | 1         | 0.55%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5741 1280x800 261x163mm 12.1-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4341 1366x768 344x194mm 15.5-inch    | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC424A 3200x1800 293x165mm 13.2-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC4157 3840x2160 344x194mm 15.5-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch   | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0FEF 3840x2160 1872x1053mm 84.6-inch | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.55%   |
| Samsung Electronics LCD Monitor SAM0D74 1920x1080 1210x680mm 54.6-inch  | 1         | 0.55%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch       | 1         | 0.55%   |
| Samsung Electronics C27R500 SAM0F9D 1920x1080 598x336mm 27.0-inch       | 1         | 0.55%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                  | 1         | 0.55%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 80        | 46.24%  |
| 1366x768 (WXGA)   | 41        | 23.7%   |
| 3840x2160 (4K)    | 15        | 8.67%   |
| 2560x1440 (QHD)   | 6         | 3.47%   |
| 800x1280          | 5         | 2.89%   |
| 1920x1200 (WUXGA) | 4         | 2.31%   |
| 1600x900 (HD+)    | 4         | 2.31%   |
| 1280x800 (WXGA)   | 4         | 2.31%   |
| 2880x1800         | 2         | 1.16%   |
| 2560x1600         | 2         | 1.16%   |
| 2560x1080         | 2         | 1.16%   |
| 1440x900 (WXGA+)  | 2         | 1.16%   |
| 3440x1440         | 1         | 0.58%   |
| 3200x1800 (QHD+)  | 1         | 0.58%   |
| 2880x1920         | 1         | 0.58%   |
| 2736x1824         | 1         | 0.58%   |
| 2304x1440         | 1         | 0.58%   |
| 2160x1440         | 1         | 0.58%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 47        | 26.26%  |
| 14      | 27        | 15.08%  |
| 13      | 23        | 12.85%  |
| 21      | 10        | 5.59%   |
| 24      | 9         | 5.03%   |
| 27      | 8         | 4.47%   |
| 23      | 8         | 4.47%   |
| 12      | 7         | 3.91%   |
| Unknown | 5         | 2.79%   |
| 31      | 4         | 2.23%   |
| 16      | 4         | 2.23%   |
| 7       | 4         | 2.23%   |
| 84      | 3         | 1.68%   |
| 19      | 3         | 1.68%   |
| 11      | 3         | 1.68%   |
| 34      | 2         | 1.12%   |
| 18      | 2         | 1.12%   |
| 17      | 2         | 1.12%   |
| 65      | 1         | 0.56%   |
| 54      | 1         | 0.56%   |
| 52      | 1         | 0.56%   |
| 46      | 1         | 0.56%   |
| 36      | 1         | 0.56%   |
| 32      | 1         | 0.56%   |
| 20      | 1         | 0.56%   |
| 3       | 1         | 0.56%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 87        | 49.15%  |
| 501-600     | 24        | 13.56%  |
| 201-300     | 22        | 12.43%  |
| 401-500     | 15        | 8.47%   |
| 601-700     | 5         | 2.82%   |
| 1-100       | 5         | 2.82%   |
| Unknown     | 5         | 2.82%   |
| 701-800     | 4         | 2.26%   |
| 351-400     | 4         | 2.26%   |
| 1501-2000   | 3         | 1.69%   |
| 1001-1500   | 3         | 1.69%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 134       | 82.72%  |
| 16/10   | 15        | 9.26%   |
| Unknown | 5         | 3.09%   |
| 0.67    | 4         | 2.47%   |
| 21/9    | 2         | 1.23%   |
| 6/5     | 1         | 0.62%   |
| 3/2     | 1         | 0.62%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 26.26%  |
| 81-90          | 37        | 20.67%  |
| 201-250        | 19        | 10.61%  |
| 71-80          | 12        | 6.7%    |
| 151-200        | 9         | 5.03%   |
| 301-350        | 8         | 4.47%   |
| 61-70          | 7         | 3.91%   |
| 351-500        | 7         | 3.91%   |
| More than 1000 | 6         | 3.35%   |
| 1-40           | 5         | 2.79%   |
| Unknown        | 5         | 2.79%   |
| 111-120        | 4         | 2.23%   |
| 51-60          | 3         | 1.68%   |
| 251-300        | 3         | 1.68%   |
| 141-150        | 2         | 1.12%   |
| 121-130        | 2         | 1.12%   |
| 501-1000       | 2         | 1.12%   |
| 91-100         | 1         | 0.56%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 57        | 32.57%  |
| 101-120       | 42        | 24%     |
| 51-100        | 37        | 21.14%  |
| 161-240       | 21        | 12%     |
| More than 240 | 9         | 5.14%   |
| Unknown       | 5         | 2.86%   |
| 1-50          | 4         | 2.29%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 133       | 78.7%   |
| 2     | 25        | 14.79%  |
| 0     | 8         | 4.73%   |
| 3     | 3         | 1.78%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 99        | 41.42%  |
| Realtek Semiconductor    | 79        | 33.05%  |
| Qualcomm Atheros         | 19        | 7.95%   |
| Broadcom                 | 14        | 5.86%   |
| TP-Link                  | 5         | 2.09%   |
| Ralink                   | 5         | 2.09%   |
| Marvell Technology Group | 4         | 1.67%   |
| MediaTek                 | 3         | 1.26%   |
| ASIX Electronics         | 2         | 0.84%   |
| Wilocity                 | 1         | 0.42%   |
| VIA Technologies         | 1         | 0.42%   |
| SILICON Laboratories     | 1         | 0.42%   |
| Sigma Designs            | 1         | 0.42%   |
| Ralink Technology        | 1         | 0.42%   |
| Nvidia                   | 1         | 0.42%   |
| Lenovo                   | 1         | 0.42%   |
| D-Link                   | 1         | 0.42%   |
| Broadcom Limited         | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 15.79%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 5.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 9         | 3.16%   |
| Intel Wireless 7260                                               | 7         | 2.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 2.46%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.46%   |
| Intel Wireless 8260                                               | 6         | 2.11%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 2.11%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 2.11%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 5         | 1.75%   |
| Intel Wireless 8265 / 8275                                        | 5         | 1.75%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 5         | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 5         | 1.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 4         | 1.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 4         | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.4%    |
| Intel Wireless 7265                                               | 4         | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 4         | 1.4%    |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 3         | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 1.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 1.05%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 1.05%   |
| Intel Wireless 3165                                               | 3         | 1.05%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 1.05%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.05%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.05%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 3         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 1.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.7%    |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.7%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.7%    |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.7%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 2         | 0.7%    |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless                 | 2         | 0.7%    |
| Intel Wireless 3160                                               | 2         | 0.7%    |
| Intel I211 Gigabit Network Connection                             | 2         | 0.7%    |
| Intel I210 Gigabit Network Connection                             | 2         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 82        | 54.3%   |
| Realtek Semiconductor    | 27        | 17.88%  |
| Qualcomm Atheros         | 14        | 9.27%   |
| Broadcom                 | 9         | 5.96%   |
| TP-Link                  | 5         | 3.31%   |
| Ralink                   | 5         | 3.31%   |
| MediaTek                 | 3         | 1.99%   |
| Marvell Technology Group | 2         | 1.32%   |
| Wilocity                 | 1         | 0.66%   |
| Ralink Technology        | 1         | 0.66%   |
| D-Link                   | 1         | 0.66%   |
| Broadcom Limited         | 1         | 0.66%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter   | 9         | 5.96%   |
| Intel Wireless 7260                                        | 7         | 4.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                   | 7         | 4.64%   |
| Intel Wireless 8260                                        | 6         | 3.97%   |
| Intel Wi-Fi 6 AX201                                        | 6         | 3.97%   |
| Intel Wi-Fi 6 AX200                                        | 6         | 3.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter   | 5         | 3.31%   |
| Intel Wireless 8265 / 8275                                 | 5         | 3.31%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                     | 5         | 3.31%   |
| Intel Cannon Lake PCH CNVi WiFi                            | 5         | 3.31%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter            | 4         | 2.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                  | 4         | 2.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter | 4         | 2.65%   |
| Intel Wireless 7265                                        | 4         | 2.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                          | 4         | 2.65%   |
| Intel Comet Lake PCH CNVi WiFi                             | 4         | 2.65%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                     | 3         | 1.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter | 3         | 1.99%   |
| Intel Wireless 3165                                        | 3         | 1.99%   |
| Intel Alder Lake-P PCH CNVi WiFi                           | 3         | 1.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter            | 2         | 1.32%   |
| Realtek 802.11n WLAN Adapter                               | 2         | 1.32%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter | 2         | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter           | 2         | 1.32%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                    | 2         | 1.32%   |
| Marvell Group 88W8897 [AVASTAR] 802.11ac Wireless          | 2         | 1.32%   |
| Intel Wireless 3160                                        | 2         | 1.32%   |
| Intel Centrino Ultimate-N 6300                             | 2         | 1.32%   |
| Intel Centrino Advanced-N 6235                             | 2         | 1.32%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]               | 2         | 1.32%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter         | 2         | 1.32%   |
| Broadcom BCM43228 802.11a/b/g/n                            | 2         | 1.32%   |
| Wilocity Wil6200 802.11ad Wireless Network Adapter         | 1         | 0.66%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano] | 1         | 0.66%   |
| TP-Link 802.11ac WLAN Adapter                              | 1         | 0.66%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter   | 1         | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter   | 1         | 0.66%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter            | 1         | 0.66%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                 | 1         | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter        | 1         | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 64        | 51.61%  |
| Intel                    | 42        | 33.87%  |
| Broadcom                 | 6         | 4.84%   |
| Qualcomm Atheros         | 5         | 4.03%   |
| Marvell Technology Group | 2         | 1.61%   |
| ASIX Electronics         | 2         | 1.61%   |
| VIA Technologies         | 1         | 0.81%   |
| Nvidia                   | 1         | 0.81%   |
| Lenovo                   | 1         | 0.81%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 45        | 34.09%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 11.36%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 5.3%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3         | 2.27%   |
| Intel Ethernet Controller I225-V                                  | 3         | 2.27%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 2.27%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.27%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.27%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 2.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 1.52%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.52%   |
| Intel I210 Gigabit Network Connection                             | 2         | 1.52%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 1.52%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 1.52%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.52%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 1.52%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.52%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.52%   |
| ASIX AX88179 Gigabit Ethernet                                     | 2         | 1.52%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.76%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.76%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.76%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 1         | 0.76%   |
| Nvidia MCP61 Ethernet                                             | 1         | 0.76%   |
| Marvell Group 88E8070 based Ethernet Controller                   | 1         | 0.76%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 1         | 0.76%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.76%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.76%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.76%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.76%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.76%   |
| Intel Ethernet Connection (3) I218-V                              | 1         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.76%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.76%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.76%   |
| Intel 82566MM Gigabit Network Connection                          | 1         | 0.76%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 1         | 0.76%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 145       | 54.1%   |
| Ethernet | 121       | 45.15%  |
| Modem    | 2         | 0.75%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 120       | 70.59%  |
| Ethernet | 50        | 29.41%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 94        | 56.63%  |
| 1     | 66        | 39.76%  |
| 3     | 3         | 1.81%   |
| 8     | 1         | 0.6%    |
| 4     | 1         | 0.6%    |
| 0     | 1         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 129       | 77.25%  |
| Yes  | 38        | 22.75%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 66        | 52.8%   |
| Realtek Semiconductor           | 14        | 11.2%   |
| Qualcomm Atheros Communications | 7         | 5.6%    |
| IMC Networks                    | 5         | 4%      |
| Ralink                          | 4         | 3.2%    |
| Foxconn / Hon Hai               | 4         | 3.2%    |
| Cambridge Silicon Radio         | 4         | 3.2%    |
| Broadcom                        | 4         | 3.2%    |
| ASUSTek Computer                | 4         | 3.2%    |
| Toshiba                         | 3         | 2.4%    |
| MediaTek                        | 2         | 1.6%    |
| Marvell Semiconductor           | 2         | 1.6%    |
| Hewlett-Packard                 | 2         | 1.6%    |
| Dell                            | 2         | 1.6%    |
| Lite-On Technology              | 1         | 0.8%    |
| Apple                           | 1         | 0.8%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 22        | 17.6%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 17        | 13.6%   |
| Intel AX201 Bluetooth                                 | 10        | 8%      |
| Realtek Bluetooth Radio                               | 8         | 6.4%    |
| Intel AX200 Bluetooth                                 | 6         | 4.8%    |
| IMC Networks Bluetooth Radio                          | 5         | 4%      |
| Ralink RT3290 Bluetooth                               | 4         | 3.2%    |
| Intel AX210 Bluetooth                                 | 4         | 3.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 4         | 3.2%    |
| Realtek  Bluetooth 4.2 Adapter                        | 3         | 2.4%    |
| Qualcomm Atheros  Bluetooth Device                    | 3         | 2.4%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 3         | 2.4%    |
| Intel Bluetooth Device                                | 3         | 2.4%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 2         | 1.6%    |
| MediaTek Wireless_Device                              | 2         | 1.6%    |
| HP Broadcom 2070 Bluetooth Combo                      | 2         | 1.6%    |
| Foxconn / Hon Hai Bluetooth Device                    | 2         | 1.6%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2         | 1.6%    |
| Toshiba RT Bluetooth Radio                            | 1         | 0.8%    |
| Toshiba Integrated Bluetooth HCI                      | 1         | 0.8%    |
| Toshiba Bluetooth USB Host Controller                 | 1         | 0.8%    |
| Realtek RTL8821A Bluetooth                            | 1         | 0.8%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 1         | 0.8%    |
| Qualcomm Atheros Bluetooth USB Host Controller        | 1         | 0.8%    |
| Qualcomm Atheros AR9462 Bluetooth                     | 1         | 0.8%    |
| Qualcomm Atheros AR3011 Bluetooth                     | 1         | 0.8%    |
| Marvell Bluetooth and Wireless LAN Composite Device   | 1         | 0.8%    |
| Marvell Bluetooth and Wireless LAN Composite          | 1         | 0.8%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth            | 1         | 0.8%    |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 1         | 0.8%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter          | 1         | 0.8%    |
| Foxconn / Hon Hai Bluetooth USB Host Controller       | 1         | 0.8%    |
| Dell DW375 Bluetooth Module                           | 1         | 0.8%    |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.8%    |
| Broadcom HP Portable SoftSailing                      | 1         | 0.8%    |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 1         | 0.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 1         | 0.8%    |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]      | 1         | 0.8%    |
| ASUS Bluetooth Radio                                  | 1         | 0.8%    |
| ASUS Bluetooth Device                                 | 1         | 0.8%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 144       | 64.86%  |
| Nvidia                | 40        | 18.02%  |
| AMD                   | 25        | 11.26%  |
| Logitech              | 3         | 1.35%   |
| ASUSTek Computer      | 2         | 0.9%    |
| SteelSeries ApS       | 1         | 0.45%   |
| Solid State Logic     | 1         | 0.45%   |
| Realtek Semiconductor | 1         | 0.45%   |
| Lenovo                | 1         | 0.45%   |
| JMTek                 | 1         | 0.45%   |
| Griffin Technology    | 1         | 0.45%   |
| Dell                  | 1         | 0.45%   |
| Apogee Electronics    | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 20        | 7.87%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 13        | 5.12%   |
| Intel Haswell-ULT HD Audio Controller                                      | 11        | 4.33%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 11        | 4.33%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 4.33%   |
| Intel 8 Series HD Audio Controller                                         | 11        | 4.33%   |
| AMD Family 17h/19h HD Audio Controller                                     | 11        | 4.33%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 9         | 3.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 8         | 3.15%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.76%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 2.76%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 2.36%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 6         | 2.36%   |
| Nvidia GP107GL High Definition Audio Controller                            | 5         | 1.97%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 5         | 1.97%   |
| Intel Comet Lake PCH cAVS                                                  | 5         | 1.97%   |
| Intel Broadwell-U Audio Controller                                         | 5         | 1.97%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5         | 1.97%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 1.97%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.57%   |
| Nvidia GP106 High Definition Audio Controller                              | 4         | 1.57%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.57%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.57%   |
| Intel 200 Series PCH HD Audio                                              | 4         | 1.57%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.57%   |
| Nvidia GF108 High Definition Audio Controller                              | 3         | 1.18%   |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.18%   |
| Nvidia TU104 HD Audio Controller                                           | 2         | 0.79%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.79%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.79%   |
| Nvidia Audio device                                                        | 2         | 0.79%   |
| Intel CM238 HD Audio Controller                                            | 2         | 0.79%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 2         | 0.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 2         | 0.79%   |
| ASUSTek Computer USB Audio                                                 | 2         | 0.79%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 2         | 0.79%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 2         | 0.79%   |
| SteelSeries ApS SteelSeries Arctis 5                                       | 1         | 0.39%   |
| Solid State Logic SSL 2+                                                   | 1         | 0.39%   |
| Realtek Semiconductor USB Audio                                            | 1         | 0.39%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 28        | 31.11%  |
| SK hynix            | 17        | 18.89%  |
| Micron Technology   | 14        | 15.56%  |
| Crucial             | 9         | 10%     |
| Kingston            | 7         | 7.78%   |
| Corsair             | 6         | 6.67%   |
| Unknown             | 3         | 3.33%   |
| Ramaxel Technology  | 3         | 3.33%   |
| Wilk                | 1         | 1.11%   |
| Timetec             | 1         | 1.11%   |
| Gold Key            | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s      | 3         | 3.13%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s       | 2         | 2.08%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s      | 2         | 2.08%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s       | 2         | 2.08%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s       | 2         | 2.08%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s   | 2         | 2.08%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s     | 2         | 2.08%   |
| Crucial RAM CT16G4SFRA32A.M16FR 16GB SODIMM DDR4 3200MT/s   | 2         | 2.08%   |
| Wilk RAM W-HK32S32O 32GB SODIMM DDR4 3200MT/s               | 1         | 1.04%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                   | 1         | 1.04%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s              | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                  | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                  | 1         | 1.04%   |
| Timetec RAM SD3-1600 8GB SODIMM DDR3 1600MT/s               | 1         | 1.04%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s        | 1         | 1.04%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                | 1         | 1.04%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s      | 1         | 1.04%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s      | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1334MT/s      | 1         | 1.04%   |
| SK hynix RAM HMT31GR7BFR4A-H9 8GB DIMM DDR3 1333MT/s        | 1         | 1.04%   |
| SK hynix RAM HMT125S6TFR8C-G7 2GB SODIMM DDR3 1067MT/s      | 1         | 1.04%   |
| SK hynix RAM HMAA51S6AMR6N-UH 8GB SODIMM DDR4 2400MT/s      | 1         | 1.04%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s     | 1         | 1.04%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s      | 1         | 1.04%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s     | 1         | 1.04%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s     | 1         | 1.04%   |
| SK hynix RAM HMA82GR7JJR8N-WM 16384MB DIMM DDR4 2933MT/s    | 1         | 1.04%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s      | 1         | 1.04%   |
| SK hynix RAM H5ANAG6NCMR-XNC 8GB Row Of Chips DDR4 3200MT/s | 1         | 1.04%   |
| Samsung RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s      | 1         | 1.04%   |
| Samsung RAM Module 32GB SODIMM DDR4 3200MT/s                | 1         | 1.04%   |
| Samsung RAM M471B5673EH1-CH9 2GB SODIMM DDR3 1334MT/s       | 1         | 1.04%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s       | 1         | 1.04%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s       | 1         | 1.04%   |
| Samsung RAM M471A5244BB0-CPB 4GB SODIMM DDR4 2400MT/s       | 1         | 1.04%   |
| Samsung RAM M471A5143DB0-CPB 4GB SODIMM DDR4 2133MT/s       | 1         | 1.04%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s      | 1         | 1.04%   |
| Samsung RAM M471A1K44BM0-CRC 8GB SODIMM DDR4 2400MT/s       | 1         | 1.04%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s       | 1         | 1.04%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s       | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 50        | 66.67%  |
| DDR3   | 16        | 21.33%  |
| LPDDR3 | 4         | 5.33%   |
| DDR5   | 3         | 4%      |
| LPDDR4 | 1         | 1.33%   |
| DDR2   | 1         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 53        | 68.83%  |
| DIMM         | 14        | 18.18%  |
| Row Of Chips | 9         | 11.69%  |
| Chip         | 1         | 1.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 41        | 47.13%  |
| 16384 | 20        | 22.99%  |
| 4096  | 15        | 17.24%  |
| 32768 | 5         | 5.75%   |
| 2048  | 4         | 4.6%    |
| 65536 | 1         | 1.15%   |
| 1024  | 1         | 1.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 21        | 25.61%  |
| 2667  | 21        | 25.61%  |
| 1600  | 9         | 10.98%  |
| 2133  | 7         | 8.54%   |
| 2400  | 6         | 7.32%   |
| 1333  | 4         | 4.88%   |
| 4800  | 2         | 2.44%   |
| 3400  | 2         | 2.44%   |
| 1334  | 2         | 2.44%   |
| 6400  | 1         | 1.22%   |
| 4267  | 1         | 1.22%   |
| 3466  | 1         | 1.22%   |
| 3000  | 1         | 1.22%   |
| 2933  | 1         | 1.22%   |
| 1867  | 1         | 1.22%   |
| 1067  | 1         | 1.22%   |
| 667   | 1         | 1.22%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 2         | 50%     |
| Canon              | 1         | 25%     |
| Brother Industries | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


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

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 37        | 28.68%  |
| IMC Networks                           | 14        | 10.85%  |
| Cheng Uei Precision Industry (Foxlink) | 9         | 6.98%   |
| Microdia                               | 8         | 6.2%    |
| Realtek Semiconductor                  | 6         | 4.65%   |
| Syntek                                 | 5         | 3.88%   |
| Sunplus Innovation Technology          | 5         | 3.88%   |
| Bison Electronics                      | 5         | 3.88%   |
| Acer                                   | 5         | 3.88%   |
| Luxvisions Innotech Limited            | 4         | 3.1%    |
| Lite-On Technology                     | 4         | 3.1%    |
| Apple                                  | 4         | 3.1%    |
| Samsung Electronics                    | 3         | 2.33%   |
| Ricoh                                  | 3         | 2.33%   |
| Quanta                                 | 3         | 2.33%   |
| Microsoft                              | 3         | 2.33%   |
| Suyin                                  | 2         | 1.55%   |
| Logitech                               | 2         | 1.55%   |
| Creative Technology                    | 2         | 1.55%   |
| Ruision                                | 1         | 0.78%   |
| LG Electronics                         | 1         | 0.78%   |
| Lenovo                                 | 1         | 0.78%   |
| KYE Systems (Mouse Systems)            | 1         | 0.78%   |
| Alcor Micro                            | 1         | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 13        | 10.08%  |
| IMC Networks USB2.0 HD UVC WebCam                               | 6         | 4.65%   |
| Syntek Integrated Camera                                        | 4         | 3.1%    |
| Microdia Integrated_Webcam_HD                                   | 4         | 3.1%    |
| IMC Networks Integrated Camera                                  | 4         | 3.1%    |
| Samsung Galaxy series, misc. (MTP mode)                         | 3         | 2.33%   |
| Lite-On HP Wide Vision HD Camera                                | 3         | 2.33%   |
| Chicony Integrated Camera (1280x720@30)                         | 3         | 2.33%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                                 | 3         | 2.33%   |
| Acer BisonCam,NB Pro                                            | 3         | 2.33%   |
| Sunplus HP HD Webcam [Fixed]                                    | 2         | 1.55%   |
| Ricoh HD Webcam                                                 | 2         | 1.55%   |
| Realtek Integrated_Webcam_HD                                    | 2         | 1.55%   |
| Realtek HP Truevision HD                                        | 2         | 1.55%   |
| Quanta HP TrueVision HD Camera                                  | 2         | 1.55%   |
| Microdia Laptop_Integrated_Webcam_HD                            | 2         | 1.55%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 2         | 1.55%   |
| Logitech Webcam C270                                            | 2         | 1.55%   |
| Chicony TOSHIBA Web Camera - FHD                                | 2         | 1.55%   |
| Chicony Lenovo EasyCamera                                       | 2         | 1.55%   |
| Chicony HP Truevision HD                                        | 2         | 1.55%   |
| Chicony HP HD Webcam [Fixed]                                    | 2         | 1.55%   |
| Chicony HD WebCam                                               | 2         | 1.55%   |
| Chicony EasyCamera                                              | 2         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 2         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera  | 2         | 1.55%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam             | 2         | 1.55%   |
| Syntek EasyCamera                                               | 1         | 0.78%   |
| Suyin HP TrueVision HD                                          | 1         | 0.78%   |
| Suyin 1.3M HD WebCam                                            | 1         | 0.78%   |
| Sunplus Integrated_Webcam_HD                                    | 1         | 0.78%   |
| Sunplus Integrated_Webcam_FHD                                   | 1         | 0.78%   |
| Sunplus Integrated Webcam                                       | 1         | 0.78%   |
| Ruision UVC Camera                                              | 1         | 0.78%   |
| Ricoh Sony Vaio Integrated Webcam                               | 1         | 0.78%   |
| Realtek Lenovo EasyCamera                                       | 1         | 0.78%   |
| Realtek Integrated Webcam                                       | 1         | 0.78%   |
| Quanta HD Camera                                                | 1         | 0.78%   |
| Microsoft LifeCam Studio                                        | 1         | 0.78%   |
| Microsoft LifeCam Rear                                          | 1         | 0.78%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 17        | 44.74%  |
| Validity Sensors                   | 13        | 34.21%  |
| Elan Microelectronics              | 4         | 10.53%  |
| STMicroelectronics                 | 1         | 2.63%   |
| Shenzhen Goodix Technology         | 1         | 2.63%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 2.63%   |
| LighTuning Technology              | 1         | 2.63%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Synaptics UWP WBDI                                              | 4         | 10.53%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 4         | 10.53%  |
| Elan ELAN:ARM-M4                                                | 4         | 10.53%  |
| Validity Sensors VFS471 Fingerprint Reader                      | 3         | 7.89%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 3         | 7.89%   |
| Validity Sensors VFS491                                         | 2         | 5.26%   |
| Validity Sensors Synaptics WBDI                                 | 2         | 5.26%   |
| Synaptics UWP WBDI Device                                       | 2         | 5.26%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor               | 1         | 2.63%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 2.63%   |
| Validity Sensors VFS495 Fingerprint Reader                      | 1         | 2.63%   |
| Validity Sensors VFS Fingerprint sensor                         | 1         | 2.63%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 2.63%   |
| Validity Sensors Fingerprint scanner                            | 1         | 2.63%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 1         | 2.63%   |
| Synaptics WBDI                                                  | 1         | 2.63%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 1         | 2.63%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 2.63%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 2.63%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 2.63%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 2.63%   |
| LighTuning Fingerprint Sensor                                   | 1         | 2.63%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 42.86%  |
| Alcor Micro | 3         | 42.86%  |
| Upek        | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 3         | 42.86%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 87        | 51.48%  |
| 1     | 61        | 36.09%  |
| 2     | 18        | 10.65%  |
| 3     | 3         | 1.78%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 38        | 37.62%  |
| Graphics card            | 21        | 20.79%  |
| Net/wireless             | 11        | 10.89%  |
| Camera                   | 8         | 7.92%   |
| Chipcard                 | 7         | 6.93%   |
| Bluetooth                | 4         | 3.96%   |
| Unassigned class         | 3         | 2.97%   |
| Multimedia controller    | 3         | 2.97%   |
| Communication controller | 3         | 2.97%   |
| Sound                    | 2         | 1.98%   |
| Modem                    | 1         | 0.99%   |

